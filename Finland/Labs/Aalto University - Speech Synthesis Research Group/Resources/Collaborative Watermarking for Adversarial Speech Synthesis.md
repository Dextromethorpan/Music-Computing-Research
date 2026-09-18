---
title: Collaborative Watermarking for Adversarial Speech Synthesis
org: Aalto University - Speech Synthesis Research Group
org_type: Lab
country: Finland
type: paper
authors: Lauri Juvela, Xin Wang
year: 2024
url: https://arxiv.org/abs/2309.15224
date_added: 2026-08-12
---

Modern speech-synthesis systems can now clone a voice convincingly from just a few seconds of audio, which makes it important to be able to tell synthetic speech apart from real human speech (a "deepfake" audio detection problem). Instead of only trying to catch fakes after the fact, this paper proposes making the speech generator actively cooperate with the detector during training — a "collaborative watermarking" scheme where a neural vocoder (the component that turns acoustic features into a sound wave) is trained side-by-side with a synthetic-speech detector so that the generated audio carries subtle, machine-detectable traces of its artificial origin, while still sounding natural to a human listener. Tests show this consistently improves detection accuracy over training a detector alone, and the effect holds up even after the audio is compressed or time-stretched. This work was accepted at ICASSP 2024, a top conference for speech and audio signal processing.

## Concepts
- [[Audio Watermarking]]
- [[AI-Generated Music Detection]]
