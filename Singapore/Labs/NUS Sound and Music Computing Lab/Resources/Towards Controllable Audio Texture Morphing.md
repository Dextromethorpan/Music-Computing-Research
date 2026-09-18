---
title: Towards Controllable Audio Texture Morphing
org: NUS Sound and Music Computing Lab
org_type: Lab
country: Singapore
type: paper
authors: Chitralekha Gupta, Purnima Kamath, Yize Wei, Zhuoyao Li, Suranga Nanayakkara, Lonce Wyse
year: 2023
url: https://arxiv.org/abs/2304.11648
date_added: 2026-08-12
---

"Audio textures" are ambient, repetitive-but-varying sounds like wind, rain, or fire crackling. This paper trains a generative AI model (a GAN, or Generative Adversarial Network — two neural networks that compete with each other to produce realistic outputs) that can smoothly morph one texture into another, for example blending the sound of wind into the sound of water in a gradual, controllable way. It does this by learning "soft labels" — a flexible in-between description of a sound rather than a rigid category — from an audio classifier, then using those to steer the generation. It was presented at ICASSP 2023, a major signal processing conference, and could be useful for sound design, games, and film.

## Concepts
- [[Neural Networks for Audio]]
- [[Procedural Audio]]
