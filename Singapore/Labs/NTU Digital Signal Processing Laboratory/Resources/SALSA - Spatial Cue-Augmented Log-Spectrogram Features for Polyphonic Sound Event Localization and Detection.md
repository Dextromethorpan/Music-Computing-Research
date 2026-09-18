---
title: SALSA - Spatial Cue-Augmented Log-Spectrogram Features for Polyphonic Sound Event Localization and Detection
org: NTU Digital Signal Processing Laboratory
org_type: Lab
country: Singapore
type: paper
authors: Thi Ngoc Tho Nguyen, Douglas L. Jones, Karn N. Watcharasupat, Huy Phan, Woon-Seng Gan
year: 2022
url: https://arxiv.org/abs/2110.00275
date_added: 2026-08-10
---

SALSA tackles a problem called Sound Event Localization and Detection (SELD): given audio recorded on several microphones at once, figure out both what sounds are happening (a dog barking, a door slamming) and where they are coming from in space. Many overlapping sounds at once ("polyphonic") makes this hard. SALSA is a way of preparing the raw multi-microphone audio into a format ("features") that keeps both the frequency information and the spatial (directional) cues lined up together, which makes it much easier for a neural network to learn to detect and locate sounds accurately. It was published in IEEE/ACM Transactions on Audio, Speech, and Language Processing, and the method has been widely used since as a baseline in this research area.

## Concepts
- [[Sound Event Detection]]
- [[Signal Processing]]
