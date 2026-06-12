---
layout: single
title: "Activity-Dependent Structural Sparsification: Biologically Inspired Dynamic Neural Pruning"
collection: publications
category: manuscripts
permalink: /publication/2026-06-05-dadp-pruning
date: 2026-06-05
venue: "Working Paper"
excerpt: "A dynamic neural pruning algorithm based on biological synapse elimination, achieving 72.79% structural sparsity on VGG-16 while improving CIFAR-10 baseline accuracy by +1.70%."
---

Deep learning models suffer from severe over-parameterization, resulting in high computational footprints. Biological systems resolve this via activity-dependent synapse elimination. We introduce **Dynamic Activity-Dependent Pruning (DADP)**, a structural sparsification algorithm bridging backpropagation with Hebbian structural plasticity.

### Abstract
As deep learning architectures scale to unprecedented sizes, they become notoriously over-parameterized, incurring massive computational and memory costs. Biological nervous systems resolve similar efficiency challenges through activity-dependent synapse elimination, where connections are dynamically pruned based on functional contribution. In this paper, we translationally map this principle into modern deep learning frameworks by proposing Dynamic Activity-Dependent Pruning (DADP), a novel structural sparsification algorithm that bridges backpropagation with Hebbian structural plasticity. DADP continuously evaluates connection utility during training using an expected Gradient \\(\\times\\) Activation metric (\\(E [\\lVert a_i \\cdot \\frac{\\partial L}{\\partial y_j} \\rVert]\\)), permanently masking connections that consistently fail to contribute to error reduction. We evaluate DADP across MLP, CNN, and VGG-16 architectures on the MNIST and CIFAR-10 datasets, comparing it against established pruning methods including SNIP, RigL, and Magnitude-based pruning. Extensive empirical results demonstrate that DADP acts as a powerful structural regularizer; on CIFAR-10, it achieves 72.79% sparsity on VGG-16 and 63.59% sparsity on a CNN while improving baseline test accuracy by +1.70% (reaching 84.64% accuracy) and +1.44% (reaching 70.25% accuracy), respectively. On MNIST, DADP compresses VGG-16 by 15\\(\\times\\) (93.38% sparsity) with a negligible accuracy drop of only -0.04% (99.45% vs. 99.49% baseline) and a CNN by 91.61% sparsity with a +0.85% accuracy boost. Ultimately, DADP offers a computationally efficient, single-pass training methodology that achieves extreme model compression and generalization improvements without expensive post-hoc prune-retrain cycles.

### 📊 Core Accomplishments & Metrics
* Continually tracks weight connection values via an expected Gradient \\(\\times\\) Activation metric (\\(E [\\lVert a_i \\cdot \\frac{\\partial L}{\\partial y_j} \\rVert]\\)).
* Achieved **72.79% structural sparsity on VGG-16** while simultaneously improving baseline test accuracy on CIFAR-10 by **+1.70%** (reaching 84.64%).
* Achieved **91.61% sparsity on CNNs on MNIST** alongside a **+0.85% validation accuracy boost**.

[View Code Repository](https://github.com/bhushan1729)