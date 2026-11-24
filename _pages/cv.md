---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

[Download CV (PDF)]({{ base_path }}/files/CV_Caini_PAN.pdf)

Education
======
* **Ph.D. in Physics & Medical Imaging**, Université Paris-Saclay, Dec 2024 – Dec 2027 (expected)
* **Engineer's Degree (MS in Engineering)**, Télécom Paris, Institut Polytechnique de Paris, 2022 – 2024
* **B.S. in Electronic Information Engineering**, Xidian University, China, 2018 – 2022

Research experience
======
* **Ph.D. research — High-resolution 4D fMRI at 11.7 T** (Dec 2024 – present)
  * MIND team (Inria & CEA), NeuroSpin
  * Designing optimised spatio-temporal sampling strategies for fast fMRI; simulation-based benchmarking of dynamic vs. static sampling; in vivo validation of the SNAKE fMRI simulator.

* **Research intern — Learning k-space trajectories** (Apr – Oct 2024)
  * MIND team (Inria & CEA), NeuroSpin
  * Differentiable NUFFT in MRI-NUFFT; end-to-end trajectory learning under compressed-sensing reconstruction via bi-level optimisation.

* **Research intern — Computational pathology** (Nov 2021 – Jun 2022)
  * Medical Imaging System and Application Lab, Xidian University
  * Extended attention-based multiple instance learning (CLAM) to pixel-level epicardium segmentation on whole-slide histology images, with clinical experts from Fuwai Hospital.

* **Research project — Multimodal knowledge distillation** (Sept 2023 – Feb 2024)
  * Multimodal-to-single-modality knowledge distillation (LTCI, Télécom Paris).

Projects & open source
======
* **[HearSay](https://github.com/alineyyy/Hearsay)** — multi-agent LLM fact-checking of administrative advice (AWS Agents for Humans hackathon, 2026)
* **[MRI-NUFFT](https://github.com/mind-inria/mri-nufft)** — contributor, JOSS co-author
* **[SNAKE-fMRI](https://github.com/mind-inria/snake-fmri)** — contributor

Skills
======
* **Machine learning:** PyTorch, TensorFlow, OpenCV; implicit neural representations, multiple instance learning, knowledge distillation
* **LLMs & agents:** Strands Agents, Amazon Bedrock, multi-agent pipelines, BM25 retrieval
* **Programming:** Python, C/C++, MATLAB, JavaScript, SQL, Git, LaTeX
* **Languages:** English (fluent), French (proficient), Chinese (native)

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
