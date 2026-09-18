---
title: EnCodec - High Fidelity Neural Audio Compression
org: Meta AI (FAIR)
org_type: Company
country: USA
type: paper
authors: Alexandre Défossez, Jade Copet, Gabriel Synnaeve, Yossi Adi
year: 2022
url: https://arxiv.org/abs/2210.13438
date_added: 2026-08-10
---

EnCodec is a neural network that compresses audio — squeezing a sound file down to a much smaller size — and then reconstructs it, aiming to sound as close to the original as possible even at very low file sizes. It works in real time (fast enough to be used live, not just for offline processing) and outputs a stream of discrete "tokens," short numeric codes that stand in for chunks of sound. Those tokens turned out to be extremely useful beyond compression: they became the building blocks that later text-to-music and text-to-audio generation models, including Meta's own MusicGen, are trained to predict. EnCodec is a key example of an audio codec (a compression system) doubling as a foundation for generative AI.

## Concepts
- [[Audio Compression and Codecs]]
- [[Neural Networks for Audio]]
