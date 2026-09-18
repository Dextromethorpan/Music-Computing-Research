---
title: Towards Improved Objective Perceptual Audio Quality Assessment
org: Fraunhofer IIS
org_type: Company
country: Germany
type: paper
authors: Fraunhofer IIS / International Audio Laboratories Erlangen researchers (incl. Matteo Torcoli)
year: 2024
url: https://arxiv.org/abs/2411.18222
date_added: 2026-08-09
---

When engineers develop a new audio codec, they need a fast way to check "does this still sound good?" without asking thousands of human listeners every time. This paper (Part 1 of a two-part study) improves PEAQ, an existing automated tool that tries to predict how a human would rate audio quality, by adding a machine-learning model that mimics how our brains judge the *severity* of different types of distortion rather than just detecting that a distortion exists. The result is a tool that generalizes better to distortion types it has never seen before, including audio compressed with newer, model-based ("parametric") codecs that don't just preserve the waveform. In plain terms: it's a smarter, more human-like automatic judge of "does this compressed audio sound bad, and how bad?"

## Concepts
- [[Sound Perception and Psychoacoustics]]
- [[Audio Compression and Codecs]]
