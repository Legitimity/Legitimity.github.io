---
layout: cv
permalink: /cv/
title: CV
nav: true
nav_order: 5
cv_pdf: /assets/pdf/cv.pdf
description: A detailed overview of my academic background, research projects, and programming achievements.
toc:
  sidebar: left
---

## Education

**Peking University**
*B.S. in Information and Computing Science, School of EECS*
- **Expected:** Jun 2029
- **Core Coursework:**
  - *Mathematics & AI:* Fundamentals of Artificial Intelligence, Mathematical Analysis II, Advanced Algebra II, Intermediate Algorithms and Applications
  - *Honor Tracks:* Practice of Programming in C&C++, Introduction to Computing A

---

## Research & Project Experience

**Tencent Spark Challenge - nanoGPT Speedrun**
*Project Lead / Core Developer* | Aug 2026
- Conducted structural iterations on the GPT-2 architecture, successfully evolving a baseline model into a ~170M-parameter Dense Speedrun model[cite: 6].
- Engineered a fused QKVG GEMM and integrated a 1-bank Value Embedding and ReLU² FFN, significantly optimizing A100 GPU throughput without inflating computational overhead[cite: 6].
- Implemented WSD (Warmup-Stable-Decay) scheduling and tailored optimization strategies under a strict 4-hour wall-clock limit, achieving a highly competitive final validation loss of 3.005883[cite: 6].

**Guobiao Mahjong AI - Fundamentals of AI Course Project**
*Core Developer* | Spring 2026
- Developed a ResNet-based supervised learning model trained on over 98,000 expert self-play matches for Guobiao Mahjong[cite: 5].
- Resolved severe memory leaks and CPU/IO bottlenecks by implementing an in-worker LRU Cache with lazy-loading and a Locality-aware MatchBlockSampler[cite: 5].
- Engineered an online 12x symmetry data augmentation pipeline to maximize NPU utilization, achieving 88.18% masked accuracy and consistently ranking Top 5 on the Botzone competition platform[cite: 5].

---

## Honors & Awards

**University Level**
- **Team Representative**, ICPC Asia Nanjing Regional Contest (2025)

**Pre-University Level**
- **Gold Medal**, National Olympiad in Informatics Winter Camp (NOI WC)
- **Gold Medal**, National Olympiad in Informatics Summer Camp (NOI D)
- **Silver Medal**, National Olympiad in Informatics (NOI)
- **Silver Medal**, Asia-Pacific Informatics Olympiad (APIO, 2023)

---

## Technical Skills

- **Programming Languages:** C/C++, Python.
- **Deep Learning Frameworks:** PyTorch.
- **Tools & Environments:** Linux/Ubuntu, Git, GitHub Actions.
- **Languages:** Mandarin (Native), English (Proficient).
