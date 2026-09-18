---
title: Real-Time Guitar Amplifier Emulation with Deep Learning
org: Aalto Acoustics Lab - Audio Signal Processing
org_type: Lab
country: Finland
type: paper
authors: Alec Wright, Eero-Pekka Damskägg, Lauri Juvela, Vesa Välimäki
year: 2020
url: https://www.mdpi.com/2076-3417/10/3/766
date_added: 2026-08-12
---

This paper shows how a computer can "listen" to a real guitar amplifier or distortion pedal and learn to imitate its sound using a neural network — a type of machine-learning model loosely inspired by how brain cells connect. The team trained two kinds of neural networks (one based on a model called WaveNet, one a "recurrent" network that processes audio step by step) on recordings from three popular pedals: an Ibanez Tube Screamer, a Boss DS-1, and an Electro-Harmonix Big Muff Pi. Remarkably, only about three minutes of recorded audio was enough to train a convincing model of each pedal's sound. Because the resulting models run fast enough to process a live guitar signal without noticeable delay, this technique lets a plug-in reproduce the "colour" of expensive vintage hardware entirely in software.

## Concepts
- [[Neural Networks for Audio]]
- [[Virtual Analog Modeling]]
