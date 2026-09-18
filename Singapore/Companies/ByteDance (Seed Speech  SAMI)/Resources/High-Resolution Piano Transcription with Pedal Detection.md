---
title: High-Resolution Piano Transcription with Pedal Detection
org: ByteDance (Seed Speech / SAMI)
org_type: Company
country: Singapore
type: paper
authors: Qiuqiang Kong, Bochen Li, Xuchen Song, Yuan Wan, Yuxuan Wang (ByteDance)
year: 2020
url: https://arxiv.org/abs/2010.01815
date_added: 2026-08-09
---

"Automatic music transcription" means turning an audio recording of music into sheet-music-like symbolic data — which notes were played, when, how hard, and for how long. This ByteDance paper presents a neural-network system that listens to a recording of solo piano and outputs a very precise transcription, including not just the notes but also when the sustain pedal was pressed (which changes how notes ring out and blend together — a detail earlier transcription systems tended to ignore). The team demonstrated the system by using its transcriptions to recreate famous, highly detailed piano performances (such as Liszt's "La Campanella" and Bach's "Goldberg Variations") as new, high-quality audio. The accompanying code was released publicly on GitHub.

## Concepts
- [[Automatic Music Transcription]]
