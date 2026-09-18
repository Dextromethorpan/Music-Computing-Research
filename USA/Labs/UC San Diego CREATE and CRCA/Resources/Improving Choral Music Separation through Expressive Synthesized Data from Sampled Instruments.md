---
title: Improving Choral Music Separation through Expressive Synthesized Data from Sampled Instruments
org: UC San Diego CREATE and CRCA
org_type: Lab
country: USA
type: paper
authors: Ke Chen, Hao-Wen Dong, Yi Luo, Julian McAuley, Taylor Berg-Kirkpatrick, Miller Puckette, Shlomo Dubnov
year: 2022 (ISMIR)
url: https://arxiv.org/abs/2209.02871
date_added: 2026-08-09
---

"Music source separation" is the task of taking a mixed recording — say, a choir singing together — and splitting it back apart into its individual voice parts (soprano, alto, tenor, bass), the way an audio engineer might want to isolate one singer. Training a computer model to do this well normally needs lots of real recordings where each individual part is already known, which is expensive and rare for choral music. This paper, co-authored by UCSD's Miller Puckette and Shlomo Dubnov, builds an automated pipeline that generates realistic-sounding synthetic choir recordings from sampled-instrument software (letting researchers control how "expressive" — i.e. how human and varied — each synthetic voice sounds), and shows that training separation models on this synthetic data measurably improves their performance on real choir recordings.

## Concepts
- [[Music Source Separation]]
- [[Synthetic Training Data for Audio Machine Learning]]
