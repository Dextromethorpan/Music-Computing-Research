---
title: Adversarial Synthesis of Drum Sounds
org: Birmingham City University — DMT Lab (Digital Media Technology Lab)
org_type: Lab
country: UK
type: paper
authors: Jake Drysdale, Maciek Tomczak, Jason Hockman
year: 2020
url: https://github.com/SoMA-group/ADS
date_added: 2026-08-12
---

Instead of transcribing existing drum sounds, this DAFx 2020 paper flips the problem around and generates brand-new ones. The system is a "generative adversarial network" (GAN) — a pair of neural networks where one (the generator) learns to create realistic drum sounds and the other (the discriminator) learns to spot fakes, with the two improving each other through competition, similar to a forger and an art detective sharpening each other's skills over time. The generator can be steered by a label (e.g. "kick drum" or "snare") and by a continuous input value that lets a user smoothly morph between different sound characteristics. In listening tests, people often couldn't reliably tell the generated drum sounds apart from real recordings. The DMT Lab released a working TensorFlow implementation of the system as open-source code.

## Concepts
- [[AI Music Generation]]
- [[Neural Networks for Audio]]
- [[Open Source Research Tools]]
