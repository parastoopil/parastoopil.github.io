---
title: "Recti-Q: Feature-Space Rectification for OOD-Robust Quantized Perception in Edge Robotics"
collection: publications
category: conferences
permalink: /publication/2026-recti-q
excerpt: 'Identifies and quantifies the OOD robustness gap introduced by 4-bit PTQ in large vision backbones on resource-constrained robotic platforms, and proposes a frozen-backbone LoRA adapter trained on source data only that preserves PTQ memory savings while closing most of the robustness gap.'
date: 2026-01-01
venue: 'IROS 2026'
citation: 'H. Yaghoubi*, P. Pilevar*, M. Lin (*equal contribution). &quot;Recti-Q: Feature-Space Rectification for OOD-Robust Quantized Perception in Edge Robotics.&quot; <i>IROS 2026</i>.'
---

**H. Yaghoubi\*, P. Pilevar\*, M. Lin** (\*equal contribution). *IROS 2026.*

We identify and quantify the out-of-distribution (OOD) robustness gap introduced by 4-bit post-training quantization (PTQ) in large vision backbones deployed on resource-constrained robotic platforms. We then propose **Recti-Q**, a feature-space rectification method that trains a small frozen-backbone LoRA adapter using source-domain data only. Recti-Q preserves the memory savings of PTQ while closing most of the robustness gap under real-world sensor noise and weather corruption.
