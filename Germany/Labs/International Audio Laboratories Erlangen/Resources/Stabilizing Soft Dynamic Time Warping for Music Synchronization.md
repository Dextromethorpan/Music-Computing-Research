---
title: Stabilizing Soft Dynamic Time Warping for Music Synchronization
org: International Audio Laboratories Erlangen
org_type: Lab
country: Germany
type: project
authors: Johannes Zeitler, Meinard Müller, and collaborators
year: 2024-2025
url: https://github.com/groupmm/stabilizing_sdtw
date_added: 2026-08-09
---

Dynamic Time Warping (DTW) is a classic algorithm for lining up two sequences that unfold at different speeds — for instance, matching a printed sheet-music score to an actual recorded performance that speeds up and slows down. "Soft" and "differentiable" versions of DTW make this alignment technique compatible with modern neural-network training, so a computer can learn to align music data even when labels are imperfect or missing. This open-source toolset provides working code so other researchers can train their own music-alignment or transcription models using these newer, trainable alignment techniques, and an accompanying ISMIR 2025 paper studies why some versions of soft-DTW produce unwanted "artifacts" in the alignment.

## Concepts
- [[Music Synchronization (Audio Alignment)]]
- [[Machine Learning for Music]]
