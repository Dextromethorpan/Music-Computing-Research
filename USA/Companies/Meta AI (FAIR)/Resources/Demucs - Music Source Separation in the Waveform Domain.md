---
title: Demucs - Music Source Separation in the Waveform Domain
org: Meta AI (FAIR)
org_type: Company
country: USA
type: paper
authors: Alexandre Défossez, Nicolas Usunier, Léon Bottou, Francis Bach
year: 2019
url: https://arxiv.org/abs/1911.13254
date_added: 2026-08-10
---

Demucs tackles "music source separation" — the task of taking a finished song and splitting it back apart into its individual ingredients, such as vocals, drums, bass, and everything else. Older approaches typically worked by analyzing the audio's spectrogram (a picture-like representation of frequencies over time); Demucs instead works directly on the raw waveform (the actual up-and-down wiggle of the sound signal), using a U-Net-shaped neural network (one that shrinks the signal down and then rebuilds it, with shortcut connections that preserve fine detail) combined with a recurrent network for handling longer-term patterns over time. This waveform-domain approach matched or beat the previous best spectrogram-based methods and became one of the most widely used open-source separation tools in both research and music production.

## Concepts
- [[Music Source Separation]]
- [[Neural Networks for Audio]]
