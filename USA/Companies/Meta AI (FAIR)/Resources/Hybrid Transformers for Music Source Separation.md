---
title: Hybrid Transformers for Music Source Separation
org: Meta AI (FAIR)
org_type: Company
country: USA
type: paper
authors: Simon Rouard, Francisco Massa, Alexandre Défossez
year: 2023
url: https://arxiv.org/abs/2211.08553
date_added: 2026-08-10
---

This paper introduces Hybrid Transformer Demucs, an upgraded version of Meta's Demucs music source separation model. It combines two views of the audio at once — the raw waveform and the spectrogram (a picture-like frequency-over-time view) — and adds "Transformer" layers (the same attention-based neural network component used in large language models) so the model can better relate distant parts of a song to each other. The result was, at the time, a new state-of-the-art for separating a song into vocals, drums, bass, and other instruments, and the model became the default engine behind later versions of the widely used Demucs open-source tool.

## Concepts
- [[Music Source Separation]]
- [[Neural Networks for Audio]]
