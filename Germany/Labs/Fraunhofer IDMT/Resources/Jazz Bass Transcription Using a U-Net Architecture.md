---
title: Jazz Bass Transcription Using a U-Net Architecture
org: Fraunhofer IDMT
org_type: Lab
country: Germany
type: paper
authors: Jakob Abeßer, Meinard Müller
year: 2021
url: https://www.mdpi.com/2079-9292/10/6/670
date_added: 2026-08-09
---

Automatic music transcription means teaching a computer to listen to a recording and write down which notes were played, similar to a musician transcribing sheet music by ear. This paper adapts a neural network design called "U-Net" (originally built for medical image analysis) to isolate and transcribe the bass line from jazz recordings, even when a full band is playing at the same time. The authors also test tricks like pitch-shifting the training audio to make the model more robust to different keys and playing styles. It's a concrete example of Music Information Retrieval applied to a hard sub-problem: pulling out one instrument's notes from a busy musical mix.

## Concepts
- [[Automatic Music Transcription]]
- [[Machine Learning for Music]]
- [[Music Source Separation]]
