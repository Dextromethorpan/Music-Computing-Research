---
title: PeakNetFP - Peak-based Neural Audio Fingerprinting Robust to Extreme Time Stretching
org: BMAT
org_type: Company
country: Spain
type: paper
authors: Guillem Cortès-Sebastià, Benjamin Martin, Emilio Molina, Xavier Serra, Romain Hennequin
year: 2025
url: https://arxiv.org/abs/2506.21086
date_added: 2026-08-12
---

Winner of the Dolby Barcelona Scientific Paper Award 2025, this ISMIR 2025 paper (a collaboration between BMAT, Deezer Research, and the Music Technology Group at Universitat Pompeu Fabra) tackles a real broadcast-monitoring problem: songs are often sped up or slowed down (for example in DJ mixes, or to fit a program's exact runtime), which normally breaks "audio fingerprinting" systems used to recognize tracks automatically. Traditional fingerprinting looks at the loudest points ("peaks") in a song's spectrogram (a picture of which frequencies are loud when); PeakNetFP combines this classic peak-based approach with a neural network (a machine-learning model) so the fingerprint stays recognizable even when a track is stretched or compressed by as much as half or double its original speed. It keeps a Top-1 identification accuracy above 90% across that whole stretching range, while being far smaller and faster than comparable neural systems — and, importantly, it can still work with the huge catalogs of fingerprints that broadcast-monitoring companies like BMAT have already computed using older, non-neural methods.

## Concepts
- [[Audio Fingerprinting]]
- [[Neural Networks for Audio]]
