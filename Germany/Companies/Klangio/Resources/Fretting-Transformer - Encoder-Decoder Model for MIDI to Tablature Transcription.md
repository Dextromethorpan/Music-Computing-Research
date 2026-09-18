---
title: Fretting-Transformer - Encoder-Decoder Model for MIDI to Tablature Transcription
org: Klangio
org_type: Company
country: Germany
type: paper
authors: Anna Hamberger, Sebastian Murgul, Jochen Schmidt, Michael Heizmann
year: 2025
url: https://arxiv.org/abs/2506.14223
date_added: 2026-08-09
---

MIDI is a common digital format for storing which notes were played and when, but it doesn't say which string and fret a guitarist should use to play those notes — and the same note can often be played in several different places on the neck. This paper introduces the "Fretting-Transformer," an AI model (based on the T5 transformer architecture, a type of neural network originally built for translating text) that automatically converts MIDI note sequences into playable guitar tablature, choosing sensible string-and-fret combinations. The model was trained on several guitar datasets and can also adjust for a different tuning or a capo. In tests, it outperformed both a traditional algorithm (A*) and a popular commercial guitar-tablature program. The paper was accepted at the International Computer Music Conference (ICMC) 2025.

## Concepts
- [[Automatic Music Transcription]]
- [[Symbolic Music Notation and Representation]]
