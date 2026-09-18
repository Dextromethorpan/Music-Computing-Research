---
title: The Vicomtech Audio Deepfake Detection System Based on Wav2vec2 for the 2022 ADD Challenge
org: Vicomtech
org_type: Lab
country: Spain
type: paper
authors: Juan M. Martin-Donas, Aitor Alvarez
year: 2022
url: https://arxiv.org/abs/2203.01573
date_added: 2026-08-12
---

An "audio deepfake" is a fake voice or sound clip generated or manipulated by AI to sound like a real recording (for example, a cloned voice saying something the real person never said). This paper describes the system Vicomtech built to enter the 2022 Audio Deepfake Detection (ADD) Challenge, a competition for spotting fake audio automatically. Their system is built on wav2vec2, a pretrained AI model originally designed to understand raw speech audio, which they adapt to instead judge whether a clip is genuine or synthetic. Fine-tuning it this way lets the system reuse a huge amount of speech knowledge already learned by wav2vec2, rather than starting from scratch.

## Concepts
- [[AI-Generated Music Detection]]
- [[Voice Biometrics and Speaker Verification]]
