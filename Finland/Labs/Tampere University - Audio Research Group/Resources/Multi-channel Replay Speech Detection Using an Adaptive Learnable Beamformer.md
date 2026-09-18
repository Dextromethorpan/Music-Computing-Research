---
title: Multi-channel Replay Speech Detection Using an Adaptive Learnable Beamformer
org: Tampere University - Audio Research Group
org_type: Lab
country: Finland
type: paper
authors: Michael Neri, Tuomas Virtanen
year: 2025
url: https://arxiv.org/abs/2502.13473
date_added: 2026-08-12
---

Voice-based security systems (e.g. "confirm your identity by speaking") can be fooled by a "replay attack" — playing a recording of someone's real voice through a loudspeaker instead of them speaking live. This paper proposes a system that uses several microphones at once, combined through a "beamformer" (an algorithm that combines microphone signals to focus on sound coming from one direction, similar to a directional spotlight for hearing), and lets a neural network learn the best way to steer that beamformer for telling live speech apart from played-back recordings. Because a loudspeaker playing a recording has subtly different spatial and acoustic properties than a real human voice, the multi-microphone, learned-beamforming approach catches replay attacks more reliably than prior single-microphone methods, especially in acoustically difficult rooms.

## Concepts
- [[Beamforming (Microphone Arrays)]]
- [[Voice Biometrics and Speaker Verification]]
