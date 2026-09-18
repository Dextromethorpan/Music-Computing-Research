---
title: DDSP - Differentiable Digital Signal Processing
org: Google (Magenta)
org_type: Company
country: USA
type: paper
authors: Jesse Engel, Lamtharn (Hanoi) Hantrakul, Chenjie Gu, Adam Roberts
year: 2020
url: https://arxiv.org/abs/2001.04643
date_added: 2026-08-10
---

DDSP combines two normally-separate approaches to making sound with computers: classic, hand-built digital signal processing components (like oscillators and filters — building blocks audio engineers have used for decades, whose behavior is well understood and controllable) and modern deep learning. Instead of asking a neural network to output raw audio directly (which is hard to control and interpret), DDSP has the network output control parameters that feed into those classic DSP components. The result is a music/audio generation approach that is both high quality and "interpretable" — you can understand and steer what it's doing — while still being trained end-to-end like a typical neural network. It was presented at ICLR 2020, a top machine learning conference, and released as an open-source library.

## Concepts
- [[Differentiable Digital Signal Processing]]
- [[Neural Networks for Audio]]
