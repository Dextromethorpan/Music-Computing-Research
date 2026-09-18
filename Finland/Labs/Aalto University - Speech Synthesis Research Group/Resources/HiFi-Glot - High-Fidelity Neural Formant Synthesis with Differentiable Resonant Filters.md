---
title: HiFi-Glot - High-Fidelity Neural Formant Synthesis with Differentiable Resonant Filters
org: Aalto University - Speech Synthesis Research Group
org_type: Lab
country: Finland
type: paper
authors: Yicheng Gu, Pablo Pérez Zarazaga, Chaoren Wang, Zhizheng Wu, Zofia Malisz, Gustav Eje Henter, Lauri Juvela
year: 2024
url: https://arxiv.org/abs/2409.14823
date_added: 2026-08-12
---

"Formants" are the resonant frequencies of the vocal tract that give vowels their distinct character — they're what a speech scientist or a voice therapist needs to control precisely, for example to study how speech sounds are perceived, or to help someone adjust the pitch and resonance of their voice. Older tools like Praat can adjust formants but tend to introduce audible glitches; newer neural (AI-based) speech generators sound more natural but don't let you dial in formants precisely. HiFi-Glot combines both worlds: it uses a "source-filter" design (a neural network generates the raw vocal-cord buzz, then a mathematically well-behaved, adjustable digital filter — one built so that a training algorithm can tune it directly, i.e. it is "differentiable" — shapes that buzz into the desired vowel sound). Listening tests showed it beats both Praat and a prior neural baseline on naturalness while giving more accurate, controllable formant manipulation. The work is a collaboration between Aalto University and KTH Royal Institute of Technology, Sweden.

## Concepts
- [[Differentiable Digital Signal Processing]]
- [[Speech Synthesis]]
- [[Source-Filter Model]]
