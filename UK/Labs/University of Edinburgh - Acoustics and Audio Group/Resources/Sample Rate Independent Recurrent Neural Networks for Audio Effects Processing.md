---
title: Sample Rate Independent Recurrent Neural Networks for Audio Effects Processing
org: University of Edinburgh - Acoustics and Audio Group
org_type: Lab
country: UK
type: paper
authors: Alistair Carson, Alec Wright, Stefan Bilbao (University of Edinburgh)
year: 2024
url: https://arxiv.org/pdf/2406.06293
date_added: 2026-08-12
---

Many guitar-amp and distortion-pedal simulators use neural networks trained to imitate real analog gear. The problem: once trained on audio recorded at one sample rate (say 44,100 samples per second), these models sound wrong if you try to run them at a different rate, because the model has implicitly "memorized" that specific rate. This paper, which won the Best Presentation award at the DAFx-24 conference, redesigns the recurrent neural network architecture so it approximately generalizes across sample rates, letting a single trained model process audio correctly at rates it never saw during training. That is a practical fix that matters for real audio software, which runs at many different sample rates depending on a user's setup.

## Concepts
- [[Neural Networks for Audio]]
- [[True Analog Emulation (TAE)]]
