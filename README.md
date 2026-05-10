# 🧠 Spurious Forgetting in Continual Learning of Language Models

## Full Project Replication — ICLR 2025

**Paper:** urlSpurious Forgetting in Continual Learning of Language Models[https://arxiv.org/abs/2501.13453](https://arxiv.org/abs/2501.13453)
**Original Repository:** urlOfficial GitHub Repository[https://github.com/zzz47zzz/spurious-forgetting](https://github.com/zzz47zzz/spurious-forgetting)

---

# 📌 Overview

This project is a simplified yet faithful replication of the paper:

> **“Spurious Forgetting in Continual Learning of Language Models”**

The project investigates whether large language models truly “forget” previously learned information during continual learning, or whether this forgetting is only *spurious* — meaning the knowledge still exists internally but becomes difficult to retrieve.

The notebook reproduces the key ideas of the paper using:

* Synthetic biography datasets
* Sequential task learning
* GPT-style transformer models
* Continual learning experiments
* Forgetting evaluation metrics
* Representation and probing analysis

The implementation is optimized for:

* Google Colab
* Consumer GPUs
* Educational understanding
* Research reproduction

---

# 🎯 Objectives

The goals of this project are:

* Understand catastrophic forgetting in language models
* Reproduce continual learning experiments from the paper
* Analyze whether forgetting is real or retrieval-based
* Explore parameter updates across sequential tasks
* Study representation preservation during continual learning

---

# 🧪 Key Concepts

## Continual Learning

Continual learning refers to training a model on multiple tasks sequentially without retraining from scratch.

Example:

1. Train on Task A
2. Then train on Task B
3. Evaluate whether Task A knowledge is retained

---

## Catastrophic Forgetting

Traditional neural networks often lose performance on old tasks after learning new tasks.

This phenomenon is called:

> Catastrophic Forgetting

---

## Spurious Forgetting

The paper proposes that:

* The model may still internally store old knowledge
* The issue may instead be retrieval interference
* Hidden representations remain partially preserved
* Output performance alone may not reflect true forgetting

This project experimentally demonstrates that idea.

---

# 🏗️ Project Architecture

## Workflow

1. Generate synthetic biography dataset
2. Split into sequential tasks

