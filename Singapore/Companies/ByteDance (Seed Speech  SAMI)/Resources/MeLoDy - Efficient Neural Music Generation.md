---
title: MeLoDy - Efficient Neural Music Generation
org: ByteDance (Seed Speech / SAMI)
org_type: Company
country: Singapore
type: paper
authors: Max W. Y. Lam, Qiao Tian, Tang Li, Zongyu Yin, Siyuan Feng, and others (ByteDance SAMI)
year: 2023
url: https://arxiv.org/abs/2305.15719
date_added: 2026-08-09
---

MeLoDy ("M for music, L for language model, D for diffusion") is a ByteDance SAMI research project that generates music audio from text descriptions, similar in goal to Google's MusicLM but designed to be much faster to run. It was trained on a huge dataset — about 257,000 hours of music, drawn from 6.4 million audio files — filtered to focus on instrumental (non-vocal) music. The key technical contribution is combining a language model (which plans the overall musical structure) with a diffusion model (which fills in the actual audio detail), cutting the number of computation steps needed by 95–99% compared to prior systems while keeping audio quality and how well the music matches the text prompt competitive with or better than earlier models. This kind of efficiency matters because it makes AI music generation practical to run cheaply at scale, e.g., inside consumer apps.

## Concepts
- [[Text-to-Music Generation]]
- [[Diffusion Models for Audio]]
- [[AI Music Generation]]
