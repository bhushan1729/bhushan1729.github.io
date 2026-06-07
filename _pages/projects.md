---
layout: single
title: "Projects"
permalink: /projects/
author_profile: true
---

<div class="custom-grid">
  <!-- Card 1 -->
  <div class="project-card">
    <div class="project-meta">
      <span><i class="fa-solid fa-building-columns icon-pad-right"></i> Independent</span>
      <span><i class="fa-solid fa-calendar-days icon-pad-right"></i> Jan. 2026 – Present</span>
    </div>
    <h3 class="project-title">Activity-Dependent Structural Sparsification for Deep Neural Networks</h3>
    <div class="project-subtitle">Supervisor: Deep Learning</div>
    <ul class="project-details">
      <li>Designed a dynamic structural sparsification framework mimicking activity-dependent synapse elimination in biological nervous systems during developmental learning.</li>
      <li>Developed an online pruning mechanism in PyTorch that accumulates connection saliency scores over data distributions using custom backward hook gradient tracking.</li>
      <li>Conducted layer-wise sparsity analysis demonstrating that the model organically preserves early visual feature extractors (0% sparsity) while selectively gutting deep convolutional layers (75%–92% sparsity).</li>
      <li>Pruned VGG-16 to 98.41% sparsity (63× compression) on MNIST maintaining 98.72% accuracy (vs. 99.49% baseline), and to 72.79% sparsity on CIFAR-10 with 84.64% accuracy (vs. 82.94% baseline).</li>
      <li>Demonstrated extreme single-shot parameter compression while consistently outperforming state-of-the-art dynamic sparsity methods like RigL.</li>
    </ul>
    <div class="project-tags">
      <span class="project-tag">Deep Learning</span>
      <span class="project-tag">PyTorch</span>
      <span class="project-tag">Sparsification</span>
      <span class="project-tag">Bio-inspired AI</span>
    </div>
  </div>

  <!-- Card 2 -->
  <div class="project-card">
    <div class="project-meta">
      <span><i class="fa-solid fa-building-columns icon-pad-right"></i> Independent</span>
      <span><i class="fa-solid fa-calendar-days icon-pad-right"></i> Dec. 2025 – Present</span>
    </div>
    <h3 class="project-title">Olfactory System Inspired Named Entity Recognition (NER)</h3>
    <div class="project-subtitle">Supervisor: Self-supervised</div>
    <ul class="project-details">
      <li>Designed a biologically inspired global mixing module for NER based on principles of distributed sensing and pattern activation in the human olfactory system.</li>
      <li>Implemented an Olfaction Module + BiLSTM-CRF architecture.</li>
      <li>Developed and evaluated a strong BiLSTM-CRF baseline.</li>
      <li>Conducted ablation studies to analyse the impact of non-local feature interactions on entity boundary detection and rare entity recognition.</li>
    </ul>
    <div class="project-tags">
      <span class="project-tag">NER</span>
      <span class="project-tag">NLP</span>
      <span class="project-tag">Bio-inspired AI</span>
      <span class="project-tag">BiLSTM-CRF</span>
      <span class="project-tag">PyTorch</span>
    </div>
  </div>

  <!-- Card 3 -->
  <div class="project-card">
    <div class="project-meta">
      <span><i class="fa-solid fa-building-columns icon-pad-right"></i> IISER Pune</span>
      <span><i class="fa-solid fa-calendar-days icon-pad-right"></i> Aug. 2023 - May 2024</span>
    </div>
    <h3 class="project-title">Scaling up data curation workflows using NLP</h3>
    <div class="project-subtitle">Supervisor: Prof. Joy Merwin Monteiro</div>
    <ul class="project-details">
      <li>Leveraged modern NLP techniques to develop workflows that accurately curate address data.</li>
      <li>A basic geocoding framework is created using Weak Supervision and Clustering methods.</li>
    </ul>
    <div class="project-tags">
      <span class="project-tag">NLP</span>
      <span class="project-tag">Data Curation</span>
      <span class="project-tag">Weak Supervision</span>
      <span class="project-tag">Clustering</span>
    </div>
  </div>

  <!-- Card 4 -->
  <div class="project-card">
    <div class="project-meta">
      <span><i class="fa-solid fa-building-columns icon-pad-right"></i> IISER Bhopal</span>
      <span><i class="fa-solid fa-calendar-days icon-pad-right"></i> May 2023 - Oct. 2023</span>
    </div>
    <h3 class="project-title">Normalization analysis with VGG16 on CIFAR</h3>
    <div class="project-subtitle">Supervisor: Prof. Akshay Agarwal, PhD</div>
    <ul class="project-details">
      <li>Implemented VGG16-based Convolutional Neural Network (CNN) for image processing tasks.</li>
      <li>Evaluated various normalization techniques and identified Group Normalization as the most effective.</li>
      <li>Validated findings on CIFAR10 and CIFAR100, where Group Normalization achieved the fastest convergence and highest accuracy.</li>
    </ul>
    <div class="project-tags">
      <span class="project-tag">Computer Vision</span>
      <span class="project-tag">CNN</span>
      <span class="project-tag">VGG16</span>
      <span class="project-tag">Normalization</span>
    </div>
  </div>

  <!-- Card 5 -->
  <div class="project-card">
    <div class="project-meta">
      <span><i class="fa-solid fa-building-columns icon-pad-right"></i> IISER Pune</span>
      <span><i class="fa-solid fa-calendar-days icon-pad-right"></i> Aug. 2022 - Dec. 2022</span>
    </div>
    <h3 class="project-title">Era prediction based on text analysis</h3>
    <div class="project-subtitle">Supervisor: Prof. Leelavati Narlikar</div>
    <ul class="project-details">
      <li>Developed a machine learning model to predict the era of a text using Markov models and log-likelihood analysis.</li>
      <li>Conducted text analysis on books from the 18th and 20th centuries.</li>
      <li>Implemented 0th and 1st-order Markov models, achieving an AUC of 83% with the first-order model.</li>
    </ul>
    <div class="project-tags">
      <span class="project-tag">NLP</span>
      <span class="project-tag">Markov Models</span>
      <span class="project-tag">Text Analysis</span>
      <span class="project-tag">Machine Learning</span>
    </div>
  </div>
</div>
