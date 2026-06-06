---
layout: single
title: "Activity-Dependent Structural Sparsification: Biologically Inspired Dynamic Neural Pruning"
collection: publications
permalink: /publication/2026-06-05-dadp-pruning
date: 2026-06-05
venue: "Independent Research / Working Paper"
excerpt: "A dynamic neural pruning algorithm based on biological synapse elimination, achieving 72.79% structural sparsity on VGG-16 while improving CIFAR-10 baseline accuracy by +1.70%."
---

Deep learning models suffer from severe over-parameterization, resulting in high computational footprints. Biological systems resolve this via activity-dependent synapse elimination. We introduce **Dynamic Activity-Dependent Pruning (DADP)**, a structural sparsification algorithm bridging backpropagation with Hebbian structural plasticity.

### 📊 Core Accomplishments & Metrics
* Continually tracks weight connection values via an expected Gradient $\times$ Activation metric ($E [||a_i \cdot \frac{\partial L}{\partial y_j}||]$).
* Achieved **72.79% structural sparsity on VGG-16** while simultaneously improving baseline test accuracy on CIFAR-10 by **+1.70%** (reaching 84.64%).
* Achieved **91.61% sparsity on CNNs on MNIST** alongside a **+0.85% validation accuracy boost**.

[View Code Repository](https://github.com/bhushan1729)