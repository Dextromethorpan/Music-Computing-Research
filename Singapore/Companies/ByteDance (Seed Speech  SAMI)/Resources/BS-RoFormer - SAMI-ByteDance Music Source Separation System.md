---
title: BS-RoFormer - SAMI-ByteDance Music Source Separation System
org: ByteDance (Seed Speech / SAMI)
org_type: Company
country: Singapore
type: paper
authors: Ju-Chiang Wang, Wei-Tsung Lu, Qiuqiang Kong, Yun-Ning Hung
year: 2023
url: https://sdx-workshop.github.io/papers/Wang.pdf
date_added: 2026-08-09
---

"Music source separation" is the task of taking a finished song and splitting it back apart into its original components — vocals, drums, bass, and other instruments — as if you had access to the original studio recording tracks. This paper describes BS-RoFormer, the system ByteDance's SAMI (Speech, Audio & Music Intelligence) team built to compete in the 2023 Sound Demixing Challenge, an international competition for this exact task. It works by first splitting the audio's frequency spectrum into different "bands" (like separating a signal into bass frequencies, midrange, and treble), then uses a neural network architecture called a Transformer (the same family of AI model behind large language models) to figure out which sounds in each band belong to which instrument. BS-RoFormer won first place in the competition's main track, beating the next-best system by a wide margin, and achieving state-of-the-art results on the standard MUSDB18HQ benchmark dataset used to measure source separation quality.

## Concepts
- [[Music Source Separation]]
