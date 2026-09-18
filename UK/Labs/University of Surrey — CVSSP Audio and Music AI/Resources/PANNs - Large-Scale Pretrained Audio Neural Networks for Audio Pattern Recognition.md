---
title: PANNs - Large-Scale Pretrained Audio Neural Networks for Audio Pattern Recognition
org: University of Surrey — CVSSP Audio and Music AI
org_type: Lab
country: UK
type: paper
authors: Qiuqiang Kong, Yin Cao, Turab Iqbal, Yuxuan Wang, Wenwu Wang, Mark D. Plumbley
year: 2020
url: https://arxiv.org/abs/1912.10211
date_added: 2026-08-12
---

PANNs are a family of neural networks trained on AudioSet, a huge collection of over 2 million short YouTube audio clips labelled with 527 kinds of sounds (from "dog bark" to "acoustic guitar"). Rather than training a brand-new network from scratch every time you want to recognise sounds in a new project, the idea is to train one very capable network once and then reuse — or "transfer" — what it has learned for other, more specific tasks: identifying music genres, detecting speech emotion, classifying acoustic scenes, and more. This "pretrain once, reuse everywhere" approach was hugely influential; the PANNs models and code became a standard building block that many later audio and music AI systems (including some described elsewhere in this vault) build on top of.

## Concepts
- [[Neural Networks for Audio]]
- [[Audio Embeddings]]
