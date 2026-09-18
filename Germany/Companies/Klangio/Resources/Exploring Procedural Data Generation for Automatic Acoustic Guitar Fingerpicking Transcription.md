---
title: Exploring Procedural Data Generation for Automatic Acoustic Guitar Fingerpicking Transcription
org: Klangio
org_type: Company
country: Germany
type: paper
authors: Sebastian Murgul, Michael Heizmann
year: 2025
url: https://arxiv.org/abs/2508.07987
date_added: 2026-08-09
---

Training an AI model to transcribe guitar fingerpicking (a plucking style where individual strings are played with the fingers) normally requires lots of labeled real recordings, which are expensive to gather and often restricted by copyright. This paper instead builds a synthetic training pipeline: it automatically composes fingerpicking tablature, turns that into a MIDI performance, renders it into audio using a physical model of a guitar string (an extended version of the classic "Karplus-Strong" string-simulation algorithm), and then adds realistic effects like reverb and distortion. A transcription model trained mostly on this artificially generated audio, with just a little real audio added at the end, performed better than one trained purely on real recordings — suggesting synthetic data can help in music-AI tasks where real, labeled recordings are scarce.

## Concepts
- [[Automatic Music Transcription]]
- [[Physical Modeling Synthesis]]
