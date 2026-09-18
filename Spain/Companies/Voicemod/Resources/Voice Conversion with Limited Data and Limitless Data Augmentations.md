---
title: Voice Conversion with Limited Data and Limitless Data Augmentations
org: Voicemod
org_type: Company
country: Spain
type: paper
authors: Pritish Chandna (Voicemod); Olga Slizovskaia, Jordi Janer, Oscar Mayor (Voctro Labs)
year: 2022
url: https://arxiv.org/abs/2212.13581
date_added: 2026-08-12
---

This research paper, co-authored by a Voicemod researcher and the (then still separate) Voctro Labs team shortly before Voicemod's acquisition of Voctro Labs, tackles a practical problem: training a good real-time voice conversion system normally needs a lot of recorded audio, but high-quality voice recordings are expensive and limited. The authors test standard tricks for artificially expanding a small dataset — like shifting pitch or adding background noise to existing recordings — and introduce new augmentation techniques based on audio and voice effects. They evaluate the resulting converted voices for both male and female target speakers, using both computer-measured scores and human listener judgments, to see which augmentation methods actually produce better-sounding voice conversion when real training data is scarce.

## Concepts
- [[Voice Conversion]]
- [[Neural Networks for Audio]]
