---
title: Spatially Selective Speaker Separation Using a DNN With a Location-Dependent Feature Extraction
org: ASPIRE (Ghent University - imec)
org_type: Lab
country: Belgium
type: paper
authors: Alexander Bohlender, Ann Spriet, Wouter Tirry, Nilesh Madhu
year: 2024
url: https://ieeexplore.ieee.org/document/10361549/
date_added: 2026-08-13
---

Imagine a room with several people talking at once, picked up by a small set of microphones (like on a hearing aid or a smart speaker). This paper is about a computer program that can "point" at one specific direction and pull out just the voice coming from there, using a neural network. The key idea, called "location-dependent feature extraction," is to let part of the network specialize itself for each specific direction the target speaker might be in, rather than treating all directions the same way. This makes the separation more accurate than earlier location-guided methods, while still being flexible about where the target speaker actually is. It builds directly on the beamforming idea of pointing a virtual "listening spotlight," but adds machine learning to sharpen it.

## Concepts
- [[Beamforming (Microphone Arrays)]]
