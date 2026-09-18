---
title: Probing Low-Level Acoustic Attribute Encoding in CLAP Audio Embeddings
org: BandLab Technologies
org_type: Company
country: Singapore
type: paper
authors: Héctor Martel, Joe Hennessy-Priest, Taemin Cho
year: 2026
url: https://arxiv.org/abs/2607.03806
date_added: 2026-08-09
---

This is a peer-reviewed research paper by BandLab Technologies' machine learning team, accepted at DAFx 2026 (the International Conference on Digital Audio Effects, a leading academic venue for audio engineering research). It studies CLAP, an AI model that turns any short audio clip into a compact list of numbers (an "embedding") that captures what the sound is about, and can also match audio to matching text descriptions. The researchers test whether basic acoustic properties — how reverberant a room sounds, how loud a clip is, and its general pitch/brightness — can be recovered from these embeddings using simple prediction models. They find that reverberation and loudness are captured in a fairly straightforward ("linear") way inside the embedding, while brightness/pitch-related information is present but tangled up in a more complex way that needs a more powerful decoder to extract. This matters practically: if a single general-purpose audio AI model already "knows" about reverb and loudness, that knowledge could be reused for tasks like automatically fixing a mix's levels or effects, instead of building separate specialized tools for each one.

## Concepts
- [[Neural Networks for Audio]]
- [[Self-Supervised Learning for Audio]]
