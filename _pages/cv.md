---
layout: archive
title: "Curriculum Vitae"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

<p><a href="{{ base_path }}/files/Bhushan_Deshpande_CV.pdf" class="btn btn--primary"><i class="fa fa-download"></i> Download Full CV (PDF)</a></p>

Research Summary
======
My research interests lie at the intersection of **Brain-Inspired AI, Computational Neuroscience, and Efficient Deep Learning**. I study how biological principles, like pruning, plasticity, information bottlenecks, and inductive biases, can be formalized into architectures and learning rules to improve parameter efficiency, generalization, and representation learning in artificial neural networks.

Education
======
* **BS-MS Dual Degree in Interdisciplinary Sciences (MS Thesis in Data Science)**  
  [Indian Institute of Science Education and Research (IISER), Pune](https://www.iiserpune.ac.in/) (2020 – 2025)
  * **Master of Science (CGPA: 8.4/10)** | Bachelor of Science (CGPA: 7.6/10)
  * Recipient of the prestigious **DST INSPIRE Scholarship** and **Infosys Foundation Scholarship** (2020–2025).
  * *Relevant Coursework:* NLP, Bayesian Theory, Parameter Estimation and Inverse Theory, Generalized Linear Models, Computational Neuroscience.

Research Projects
======
* **Dynamic Activity-Dependent Pruning (DADP)** *(Mar. 2026 – Sep. 2026)*  
  *First Author* | **Status: Under Review, ICLR 2027** | [arXiv:2610.11853](https://arxiv.org/abs/2610.11853)
  * Built a single-pass pruning method inspired by synaptic plasticity to compress neural networks efficiently.
  * Discovered that pruned vision models naturally retain early sensory layers, while transformers keep late context layers.

* **Olfactory-Inspired Sparse Combinatorial Coding** *(Dec. 2025 – Jun. 2026)*  
  *Independent, First Author* | [Preprint: arXiv:2606.21895](https://arxiv.org/abs/2606.21895)
  * Designed a biologically inspired sparse compression layer based on mammalian olfactory circuits.
  * Implemented an Olfaction Module + BiLSTM-CRF architecture.
  * Reduced model parameters by 44% while improving low-resource F1 score by up to 6.23% over dense baselines.

* **Retrieval-Augmented Large Code Generation and Evaluation (Master of Science Thesis)** *(May 2024 – May 2025)*  
  [Coriolis Technologies](https://www.coriolis.co.in/home/) / [IISER Pune](https://www.iiserpune.ac.in/)
  * Developed RAG system to synthesize complex 600–800-line Python code. Improved zero-shot baseline accuracy from 20% to 65–70%.
  * Designed an iterative generation and self-correction loop with feedback, improving accuracy to 90%.
  * Formulated an LLM-as-a-Judge evaluation framework to assess synthesized code generated in every iteration.
  * Benchmarked hallucination dynamics and instruction-following across 12+ open-source models (1B–24B parameters) under 40 GB VRAM.

Industry Experience
======
* **Data Scientist (Project MIRA)**  
  [Coriolis Technologies Pvt. Ltd.](https://www.coriolis.co.in/home/), Pune, India (*Nov. 2025 – Present*)
  * Developed pretraining, SFT, IFT, and RLHF data acquisition and synthesis pipelines.
  * Designed high emotional quotient (EQ) synthetic text and audio data generation pipelines.
  * Built a SOTA language identification model (**MIRA-IndicLID**) for 22 constitutional code-mixed Indian languages.
  * Built **[Orpheus-3B-TTS-Hindi](https://huggingface.co/CoriolisTechnologies/orpheus-3b-tts-hindi)**, a speech-LLM fine-tuned for English-mixed Hindi speech synthesis.
  * Distilled larger teacher LLMs into smaller student SLMs for structured solution generation of physics problems.

* **Member of Technical Staff & Research Intern**  
  [Coriolis Technologies Pvt. Ltd.](https://www.coriolis.co.in/home/), Pune, India (*May 2024 – Oct. 2025*)
  * *Roles:* MTS (May 2025 – Oct. 2025) | Research Intern (MS Thesis) (May 2024 – May 2025)
  * Deployed code-generation tool that cut script development time from 2 days to under 4 hours.
  * Built an automated testing pipeline to catch model errors and code syntax bugs before production.
  * Led a team of 4 engineers to implement research findings in production environment.

Publications & Preprints
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Invited Talks & Conferences
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>

Technical & Theoretical Skills
======
* **Languages:** Python (Advanced), R (Intermediate)
* **Libraries:** PyTorch, NumPy, SciPy, Pandas, t-SNE, UMAP
* **Frameworks:** Hugging Face, LlamaIndex, Git, Linux, Docker, LaTeX
* **Techniques:** Few-Shot Learning, RAG, LLM-as-a-Judge, Fine-tuning (LLMs, TTS models), Knowledge Distillation

Leadership, Communication & Outreach
======
* Mentored two research interns on fine-tuning, evaluating, and open-sourcing speech models.
* Led a team of 4 engineers during research internship, translating research findings and client requirements into production implementation.
* Delivered two invited research seminars at the Chennai Mathematical Institute on Indic NLP and LLMs.
* **Exoplanet Conference (Aug. 2023):** Volunteered in event coordination and operations for *“Strange New Worlds: The Exploration of Exoplanets”* at IISER Pune.
* **Industry–Academia Conclave (Aug. 2023):** Coordinated logistics and speaker sessions at IISER Pune, hosting 100+ industry and academic delegates.
* Experience in teaching and mentoring graduate-level students in data science courses.

Honors & Achievements
======
* **DST INSPIRE Scholarship (SHE) (2020–2025):** Awarded by the Department of Science & Technology, Govt. of India, to top 1% performers in Higher Secondary examinations for academic excellence in natural and basic sciences across BS-MS studies.
* **Infosys Foundation Scholarship (2020–2025):** Merit-based full financial scholarship awarded throughout the 5-year BS-MS dual degree program.
* **Graduate Aptitude Test in Engineering (GATE) – Statistics (2024):** Secured **All India Rank (AIR) 266** in the national competitive examination.
