---
title: Waveform Generation for Text-to-Speech Synthesis Using Pitch-Synchronous Multi-Scale GANs
org: Aalto University - Speech Synthesis Research Group
org_type: Lab
country: Finland
type: paper
authors: Lauri Juvela, Bajibabu Bollepalli, Vassilis Tsiaras, Paavo Alku
year: 2018
url: https://arxiv.org/abs/1810.12598
date_added: 2026-08-12
---

This early paper (predating GELP) explores using generative adversarial networks — pairs of competing neural networks that push each other to produce more realistic output — to generate the actual sound waveform for text-to-speech systems, instead of relying on the slow, one-sample-at-a-time approach of WaveNet. The authors test two versions: generating the full speech signal directly, and generating only the "glottal excitation" (the raw buzz produced by vocal cord vibration, before it's shaped into vowels and consonants by the mouth). Listening tests showed that generating the full waveform directly still lagged behind WaveNet in quality, but the glottal-excitation approach reached comparable quality and speaker similarity — an early sign that combining GANs with classic voice-production models (rather than replacing them entirely) was a promising direction, one this group has continued to build on.

## Concepts
- [[Speech Synthesis]]
- [[Neural Networks for Audio]]
