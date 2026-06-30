---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======

**University of Maryland, College Park** — *2025 – Present*
Ph.D. in Electrical and Computer Engineering · M.S. expected 2026 · GPA: 3.9/4.0
Advisor: [Ang Li](https://www.ang-li.com/) · [CASE Lab](https://www.ang-li.com/lab/)
Coursework: Advanced Numerical Optimization, Selected Topics in ML, Convex Optimization, Information Theory, Estimation and Detection Theory, Advanced Digital Signal Processing

**Sharif University of Technology** — *2015 – 2020*
B.S. in Electrical Engineering · GPA: 3.61/4.0
Advisor: Mohammadreza Pakravan · Tehran, Iran
Thesis: Hardware tester for JTAG chain, Ethernet, and E1 interfaces

---

Research Experience
======

**Graduate Research Assistant** — *2025 – Present*
University of Maryland, College Park — CASE Lab

- Designed and ran systematic post-training quantization (PTQ) experiments across multiple VLM architectures to study calibration-data sensitivity, demonstrating that modality-skewed calibration sets cause measurable accuracy degradation in compressed models.
- Implemented a feature-space rectification method for quantized vision backbones on SWaP-constrained edge platforms; trained a frozen-backbone LoRA adapter using source-domain data only, recovering most of the PTQ robustness gap under sensor noise and weather corruption.
- Built PTQ evaluation pipelines tracking accuracy, memory footprint, and latency trade-offs across 4-bit and 8-bit configurations on standard robustness benchmarks (ImageNet-C, PACS-style shifts).

**Research Assistant** — *2022 – 2023*
University of Tehran — Communication Networks Research Group · Supervisor: P. Shariatpanahi

- Designed and evaluated cache-replacement policies for edge networks using federated reinforcement learning and federated multi-armed bandit frameworks.
- Investigated privacy-preserving learning strategies in distributed multi-agent systems.

---

Publications
======

<ul>{% for post in site.publications reversed %}
  {% include archive-single-cv.html %}
{% endfor %}</ul>

---

Teaching
======

<ul>{% for post in site.teaching reversed %}
  {% include archive-single-cv.html %}
{% endfor %}</ul>

---

Technical Skills
======

**Programming Languages:** Python · MATLAB · C · SQL · Bash

**ML & Deep Learning:** PyTorch · TensorFlow · Keras · Hugging Face Transformers · scikit-learn

**Data & Scientific Computing:** NumPy · pandas · SciPy · PySpark · Matplotlib · Seaborn

**Systems & Tools:** Linux · Git
