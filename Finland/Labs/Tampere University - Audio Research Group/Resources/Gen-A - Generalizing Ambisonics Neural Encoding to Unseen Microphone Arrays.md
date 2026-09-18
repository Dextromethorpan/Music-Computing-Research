---
title: Gen-A - Generalizing Ambisonics Neural Encoding to Unseen Microphone Arrays
org: Tampere University - Audio Research Group
org_type: Lab
country: Finland
type: paper
authors: Mikko Heikkinen, Archontis Politis, Konstantinos Drossos, Tuomas Virtanen
year: 2025
url: https://arxiv.org/abs/2501.08047
date_added: 2026-08-12
---

Ambisonics is a way of recording sound so it can later be played back correctly no matter which direction a listener faces — useful for virtual reality and 360-degree video. Converting raw signals from a physical microphone array into the Ambisonics format ("encoding") can be done more accurately with a neural network (a machine-learning model that learns patterns from examples) than with older mathematical formulas, but until now each neural network had to be retrained from scratch for every different microphone array shape. This paper introduces a neural network that takes the physical layout of a microphone array as an extra input, so a single trained model can generalize to array shapes it has never seen before. Tests in simulated rooms show it improves on conventional (non-learned) encoding methods, especially for sound without echo.

## Concepts
- [[Ambisonics]]
- [[Neural Networks for Audio]]
