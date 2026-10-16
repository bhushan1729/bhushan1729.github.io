---
layout: single
title: "Projects"
permalink: /projects/
author_profile: true
---

<div class="custom-grid">
  <!-- Project 1 -->
  <div class="project-card">
    <h3>Dynamic Activity-Dependent Pruning (DADP)</h3>
    <p><strong>Timeline:</strong> Mar. 2026 – Sep. 2026 | <strong>Role:</strong> First Author | <strong>Status:</strong> Under Review, ICLR 2027 (<a href="https://arxiv.org/abs/2610.11853">arXiv:2610.11853</a>)</p>
    <ul>
      <li>Built a single-pass pruning method inspired by synaptic plasticity to compress neural networks efficiently.</li>
      <li>Discovered that pruned vision models naturally retain early sensory layers, while transformers keep late context layers.</li>
      <li>Pruned VGG-16 to 98.41% sparsity (63× compression) on MNIST maintaining 98.72% accuracy, and to 72.79% sparsity on CIFAR-10 with +1.70% accuracy improvement over dense baseline.</li>
    </ul>
    <p><a href="/publication/2026-06-05-dadp-pruning">View Publication Page &raquo;</a></p>
  </div>

  <!-- Project 2 -->
  <div class="project-card">
    <h3>Olfactory-Inspired Sparse Combinatorial Coding</h3>
    <p><strong>Timeline:</strong> Dec. 2025 – Jun. 2026 | <strong>Role:</strong> Independent, First Author | <strong>Preprint:</strong> <a href="https://arxiv.org/abs/2606.21895">arXiv:2606.21895</a></p>
    <ul>
      <li>Designed a biologically inspired sparse compression layer based on mammalian olfactory circuits.</li>
      <li>Implemented an Olfaction Module + BiLSTM-CRF architecture.</li>
      <li>Reduced model parameters by 44% while improving low-resource F1 score by up to 6.23% over dense baselines.</li>
    </ul>
    <p><a href="/publication/2025-10-01-olfactory-inspired-ner">View Publication Page &raquo;</a></p>
  </div>

  <!-- Project 3 -->
  <div class="project-card">
    <h3>Retrieval-Augmented Large Code Generation and Evaluation (MS Thesis)</h3>
    <p><strong>Timeline:</strong> May 2024 – May 2025 | <strong>Affiliation:</strong> Coriolis Technologies / IISER Pune</p>
    <ul>
      <li>Developed RAG system to synthesize complex 600–800-line Python code, improving zero-shot baseline accuracy from 20% to 65–70%.</li>
      <li>Designed an iterative generation and self-correction loop with feedback, lifting overall accuracy to 90%.</li>
      <li>Formulated an LLM-as-a-Judge evaluation framework to assess synthesized code generated in every iteration.</li>
      <li>Benchmarked hallucination dynamics and instruction-following across 12+ open-source models (1B–24B parameters) under 40 GB VRAM.</li>
    </ul>
  </div>

  <!-- Project 3 -->
  <div class="project-card">
    <h3>Scaling up data curation workflows using NLP</h3>
    <p><strong>Timeline:</strong> Aug. 2023 – May 2024 | <strong>Affiliation:</strong> IISER Pune | <strong>Supervisor:</strong> Prof. Joy Merwin Monteiro</p>
    <ul>
      <li>Leveraged modern NLP techniques to develop workflows that accurately curate address data.</li>
      <li>A basic geocoding framework is created using Weak Supervision and Clustering methods.</li>
    </ul>
  </div>

  <!-- Project 4 -->
  <div class="project-card">
    <h3>Normalization analysis with VGG16 on CIFAR</h3>
    <p><strong>Timeline:</strong> May 2023 – Oct. 2023 | <strong>Affiliation:</strong> IISER Bhopal | <strong>Supervisor:</strong> Prof. Akshay Agarwal, PhD</p>
    <ul>
      <li>Implemented VGG16-based Convolutional Neural Network (CNN) for image processing tasks.</li>
      <li>Evaluated various normalization techniques and identified Group Normalization as the most effective.</li>
      <li>Validated findings on CIFAR10 and CIFAR100, where Group Normalization achieved the fastest convergence and highest accuracy.</li>
    </ul>
  </div>

  <!-- Project 5 -->
  <div class="project-card">
    <h3>Era prediction based on text analysis</h3>
    <p><strong>Timeline:</strong> Aug. 2022 – Dec. 2022 | <strong>Affiliation:</strong> IISER Pune | <strong>Supervisor:</strong> Prof. Leelavati Narlikar</p>
    <ul>
      <li>Developed a machine learning model to predict the era of a text using Markov models and log-likelihood analysis.</li>
      <li>Conducted text analysis on books from the 18th and 20th centuries.</li>
      <li>Implemented 0th and 1st-order Markov models, achieving an AUC of 83% with the first-order model.</li>
    </ul>
  </div>
</div>
