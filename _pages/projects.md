---
layout: single
title: "Projects"
permalink: /projects/
author_profile: true
---

<div class="custom-grid">
  <!-- Project 1 -->
  <div class="project-card">
    <h3>Activity-Dependent Structural Sparsification for Deep Neural Networks</h3>
    <p><strong>Timeline:</strong> Jan. 2026 – Present | <strong>Affiliation:</strong> Independent | <strong>Supervisor:</strong> Deep Learning</p>
    <ul>
      <li>Designed a dynamic structural sparsification framework mimicking activity-dependent synapse elimination in biological nervous systems during developmental learning.</li>
      <li>Developed an online pruning mechanism in PyTorch that accumulates connection saliency scores over data distributions using custom backward hook gradient tracking.</li>
      <li>Conducted layer-wise sparsity analysis demonstrating that the model organically preserves early visual feature extractors (0% sparsity) while selectively gutting deep convolutional layers (75%–92% sparsity).</li>
      <li>Pruned VGG-16 to 98.41% sparsity (63× compression) on MNIST maintaining 98.72% accuracy (vs. 99.49% baseline), and to 72.79% sparsity on CIFAR-10 with 84.64% accuracy (vs. 82.94% baseline).</li>
      <li>Demonstrated extreme single-shot parameter compression while consistently outperforming state-of-the-art dynamic sparsity methods like RigL.</li>
    </ul>
  </div>

  <!-- Project 2 -->
  <div class="project-card">
    <h3>Olfactory System Inspired Named Entity Recognition (NER)</h3>
    <p><strong>Timeline:</strong> Dec. 2025 – Present | <strong>Affiliation:</strong> Independent | <strong>Supervisor:</strong> Self-supervised</p>
    <ul>
      <li>Designed a biologically inspired global mixing module for NER based on principles of distributed sensing and pattern activation in the human olfactory system.</li>
      <li>Implemented an Olfaction Module + BiLSTM-CRF architecture.</li>
      <li>Developed and evaluated a strong BiLSTM-CRF baseline.</li>
      <li>Conducted ablation studies to analyse the impact of non-local feature interactions on entity boundary detection and rare entity recognition.</li>
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
