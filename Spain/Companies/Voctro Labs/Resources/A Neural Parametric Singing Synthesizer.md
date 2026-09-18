---
title: A Neural Parametric Singing Synthesizer
org: Voctro Labs
org_type: Company
country: Spain
type: paper
authors: Merlijn Blaauw, Jordi Bonada
year: 2017
url: https://arxiv.org/abs/1704.03809
date_added: 2026-08-12
---

This paper by Voctro Labs co-founders Merlijn Blaauw and Jordi Bonada (published while both were also affiliated with MTG-UPF) introduces a machine-learning model that generates a realistic singing voice from a musical score and lyrics. Instead of directly predicting the raw sound wave (which is very hard to control), the model predicts intermediate features from a "vocoder" — a tool that separates a voice into pitch (how high or low a note is) and timbre (what makes a voice sound like itself, e.g., breathy, bright, nasal). Separating these two lets the system easily retune a recorded performance to hit any target melody while keeping the singer's characteristic sound. The approach is a modified version of WaveNet, a neural network architecture originally built for generating audio sample-by-sample, adapted here to need much less training data and to run faster than a plain WaveNet would. This work became a foundation for later Voctro Labs products, including the voice-cloning technology behind Holly+.

## Concepts
- [[Singing Voice Synthesis]]
- [[Neural Networks for Audio]]
- [[Source-Filter Model]]
