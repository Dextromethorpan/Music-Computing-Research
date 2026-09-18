---
title: Basic Pitch - A Lightweight Instrument-Agnostic Model for Polyphonic Note Transcription and Multipitch Estimation
org: Spotify Research
org_type: Company
country: USA
type: paper
authors: Rachel M. Bittner, Juan José Bosch, David Rubinstein, Gabriel Meseguer-Brocal, Sebastian Ewert
year: 2022
url: https://ieeexplore.ieee.org/abstract/document/9746549
date_added: 2026-08-09
---

This paper (presented at ICASSP 2022, a major audio/speech signal processing conference) describes a small, fast neural network that listens to a recording of almost any instrument — including a singing voice — and figures out which musical notes are being played and when. This task is called "automatic music transcription": turning raw audio into a symbolic format like sheet music or MIDI (a standard file format that stores notes, timing, and pitch rather than actual sound). "Polyphonic" means the model can handle multiple notes playing at once, not just a single melody line. The model also detects "pitch bends" (small sliding changes in pitch, common in guitar or vocal performances) and works well even though it was not trained separately for every possible instrument, which is why it is called "instrument-agnostic." This research became the basis for Spotify's free open-source tool Basic Pitch, released the same year.

## Concepts
- [[Automatic Music Transcription]]
- [[Pitch Estimation]]
- [[Music Information Retrieval]]
