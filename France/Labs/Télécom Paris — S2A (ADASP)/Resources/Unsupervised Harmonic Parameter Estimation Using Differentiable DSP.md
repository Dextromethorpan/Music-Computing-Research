---
title: Unsupervised Harmonic Parameter Estimation Using Differentiable DSP and Spectral Optimal Transport
org: Télécom Paris — S2A (ADASP)
org_type: Lab
country: France
type: paper
authors: Bernardo Torres, Geoffroy Peeters, Gaël Richard
year: 2024
url: https://adasp.telecom-paris.fr/resources/2024-04-11-icassp-torres/
date_added: 2026-08-09
---

To make computer music tools that can re-create or manipulate a sound (for example, a synthesizer that imitates a violin), the software needs to figure out the pitch of a note directly from an audio recording, without a human labelling it first. This ICASSP 2024 paper combines classic sound-synthesis engineering ("DSP" — digital signal processing, the traditional math-based way of building and analyzing sound) with modern machine learning to estimate this pitch information automatically and without labeled training examples. The key trick is making the sound-synthesis steps "differentiable," meaning a machine-learning system can nudge and improve them automatically during training, and using a mathematical tool called "optimal transport" to compare a real sound to a generated one in a way that is more forgiving of small pitch differences. The approach improves how reliably pitch-tracking systems learn from raw audio alone.

## Concepts
- [[Differentiable Digital Signal Processing]]
- [[Pitch Estimation]]
