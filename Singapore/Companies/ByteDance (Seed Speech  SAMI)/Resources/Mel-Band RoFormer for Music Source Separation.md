---
title: Mel-Band RoFormer for Music Source Separation
org: ByteDance (Seed Speech / SAMI)
org_type: Company
country: Singapore
type: paper
authors: Ju-Chiang Wang, Wei-Tsung Lu, Minz Won
year: 2023
url: https://arxiv.org/abs/2310.01809
date_added: 2026-08-09
---

This is a follow-up paper to ByteDance SAMI's award-winning BS-RoFormer music source separation system (the model that splits a song back into vocals, drums, bass, and other instruments). The improvement here is in how the model divides up the audio's frequency spectrum before analyzing it: instead of splitting frequencies into evenly-sized "bands," it uses a "Mel-scale" split, which is modeled on how human hearing actually perceives pitch (we're more sensitive to small pitch differences at low frequencies than at high ones). Combined with the same "Rotary Position Embedding" technique used in modern language models (which helps the neural network keep track of where each moment of audio sits in time), this Mel-Band RoFormer approach further improved separation quality over the original band-split design.

## Concepts
- [[Music Source Separation]]
