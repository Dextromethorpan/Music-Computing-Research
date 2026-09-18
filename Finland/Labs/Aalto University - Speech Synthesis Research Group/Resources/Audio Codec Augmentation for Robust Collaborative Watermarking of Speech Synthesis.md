---
title: Audio Codec Augmentation for Robust Collaborative Watermarking of Speech Synthesis
org: Aalto University - Speech Synthesis Research Group
org_type: Lab
country: Finland
type: paper
authors: Lauri Juvela, Xin Wang
year: 2025
url: https://arxiv.org/abs/2409.13382
date_added: 2026-08-12
---

A follow-up to the group's collaborative-watermarking work above. A weakness of most audio watermarks (hidden, machine-detectable signals embedded in generated audio) is that they can be scrubbed out simply by compressing the audio with a standard audio codec — something almost every piece of audio goes through before reaching a listener, e.g. when uploaded to a streaming platform. This paper trains the watermarking system while simulating that compression step, including both traditional codecs (like MP3-style compression) and newer AI-based "neural audio codecs," so the watermark survives real-world distribution. The results show the watermark keeps working reliably across codec types and bitrates, with only a small, mostly inaudible quality cost. Presented at ICASSP 2025.

## Concepts
- [[Audio Watermarking]]
- [[AI-Generated Music Detection]]
