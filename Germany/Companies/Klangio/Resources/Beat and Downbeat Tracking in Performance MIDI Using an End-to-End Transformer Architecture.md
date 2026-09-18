---
title: Beat and Downbeat Tracking in Performance MIDI Using an End-to-End Transformer Architecture
org: Klangio
org_type: Company
country: Germany
type: paper
authors: Sebastian Murgul, Michael Heizmann (and co-authors)
year: 2025
url: https://arxiv.org/abs/2507.00466
date_added: 2026-08-09
---

To turn a musical performance into readable sheet music, software first needs to know where the beats and the "downbeats" (the strong first beat of each bar) actually fall. Most existing tools figure this out from raw audio, but this paper instead works from performance MIDI — the note-by-note timing data captured from an instrument like a digital piano. The authors built a transformer-based model (the same family of neural network used in modern language AI) that reads a MIDI performance and predicts where the beats and downbeats are, and showed it beats older statistical methods (hidden Markov models) and prior deep-learning approaches across several test datasets and musical styles.

## Concepts
- [[Automatic Music Transcription]]
- [[Machine Learning for Music]]
