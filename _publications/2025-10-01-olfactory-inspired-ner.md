---
layout: single
title: "Olfactory-Inspired Sparse Combinatorial Coding for Low-Resource Named Entity Recognition"
collection: publications
category: manuscripts
permalink: /publication/2025-10-01-olfactory-inspired-ner
date: 2025-10-01
venue: "Working Paper"
excerpt: "Introducing a biological receptor-glomerular bottleneck modeling olfactory priors into sequence models, boosting low-resource NER performance by +6.23% F1 in Bangla and +4.31% F1 in Tamil."
---

Named Entity Recognition (NER) in data-scarce languages suffers due to missing high-quality pretrained embeddings and limited supervision. This project designs a structural inductive bias modeling a biological olfactory receptor-glomerular bottleneck architecture positioned between standard token embeddings and a sequence-level BiLSTM-CRF layer.

### Abstract
Named Entity Recognition (NER) in low-resource languages suffers from limited supervision and a lack of high-quality pretrained embeddings. Biological olfaction, which relies on sparse combinatorial coding through receptor and glomerular organization, offers a compelling paradigm for learning robust representations under uncertainty. In this paper, we introduce a **receptor-glomerular bottleneck**—a loosely inspired olfactory architecture—between standard token embeddings and a BiLSTM-CRF sequence model. We evaluate our architecture across six multilingual datasets trained entirely from scratch (without pre-trained embeddings) under varied data-scale conditions, including a strict 1k-sentence low-resource control. Our results demonstrate that this structured inductive bias yields F1 score improvements, particularly under severe data scarcity. In the low-resource simulation (1k capped sentences), at least one olfactory-inspired configuration achieves the highest mean F1 score across all six datasets—with the largest improvements in **Bangla (+6.23% F1)** and **English (+2.61% F1)**, and more modest gains or nearties on Marathi and Tamil—while stabilizing training variance. We also observe improvements in the ultra-low-resource **Telugu setting (+4.43% F1)** at full-scale, and find that sparse specialization emerges within the receptor layer. Our findings suggest that structured sparse coding inspired by olfactory networks serves as an effective inductive bias and regularizer when representations must be learned from limited or noisy supervision.

### 📊 Core Accomplishments & Metrics
* Evaluated comprehensively across six distinct multilingual datasets without relying on pretrained foundational setups.
* In strict 1k capped sentence tracking, the olfactory constraint acted as an excellent regularizer, yielding massive gains of up to **+6.23% F1 in Bangla** and **+4.31% F1 in Tamil**.
* Substantially minimized training performance variance across random initialization seeds.

[View Code Repository](https://github.com/bhushan1729/olfaction-inspired-ner)