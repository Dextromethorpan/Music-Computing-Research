---
title: Pesto - Real-Time Pitch Estimation with Self-supervised Transposition-equivalent Objective
org: Sony CSL Paris
org_type: Company
country: France
type: paper
authors: Alain Riou, Bernardo Torres, Ben Hayes, Stefan Lattner, Gaëtan Hadjeres, Gaël Richard, Geoffroy Peeters
year: 2025
url: https://transactions.ismir.net/articles/10.5334/tismir.251
date_added: 2026-08-09
---

"Pitch" is how high or low a musical note sounds — for example, telling apart a low bass note from a high flute note. PESTO is an AI system that listens to audio and figures out exactly which pitch is being played, extremely fast (fast enough to run live, in real time, as a musician plays) and while using very little computing power (the paper reports it running about 800 times faster than a well-known older method called CREPE, with a much smaller model). What makes it clever is how it was trained: instead of needing humans to manually label the correct pitch of thousands of audio clips, it teaches itself by learning that shifting a sound up or down in pitch should shift the model's answer by the same amount — a trick called "self-supervised learning." This kind of fast, accurate pitch detection is a basic building block used in tuners, auto-tune style effects, and other music AI tools.

## Concepts
- [[Self-Supervised Learning for Audio]]
- [[Pitch Estimation]]
