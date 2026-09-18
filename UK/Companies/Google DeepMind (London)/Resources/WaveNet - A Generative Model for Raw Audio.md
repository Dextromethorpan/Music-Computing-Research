---
title: WaveNet - A Generative Model for Raw Audio
org: Google DeepMind (London)
org_type: Company
country: UK
type: paper
authors: Aaron van den Oord, Sander Dieleman, Heiga Zen, Karen Simonyan, Oriol Vinyals, Alex Graves, Nal Kalchbrenner, Andrew Senior, Koray Kavukcuoglu
year: 2016
url: https://arxiv.org/abs/1609.03499
date_added: 2026-08-12
---

WaveNet was a breakthrough neural network that generates audio one tiny sample at a time (tens of thousands of samples per second) rather than using older shortcut methods that stitch together or heavily simplify pre-recorded sound. Because it works directly on the raw sound wave, it produces speech that human listeners rated as dramatically more natural than the best text-to-speech systems of the time, and a single model can imitate many different voices. Trained on piano music instead of speech, the same network could also generate original, often realistic-sounding musical fragments — showing the technique wasn't specific to speech. WaveNet's ideas went on to influence a huge wave of later AI audio and music generation research.

## Concepts
- [[Neural Networks for Audio]]
- [[Speech Synthesis]]
- [[AI Music Generation]]
