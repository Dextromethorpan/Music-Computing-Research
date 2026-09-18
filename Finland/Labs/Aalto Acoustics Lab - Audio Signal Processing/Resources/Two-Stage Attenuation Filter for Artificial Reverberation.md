---
title: Two-Stage Attenuation Filter for Artificial Reverberation
org: Aalto Acoustics Lab - Audio Signal Processing
org_type: Lab
country: Finland
type: paper
authors: Vesa Välimäki, Karolina Prawda, Sebastian J. Schlecht
year: 2024
url: https://ieeexplore.ieee.org/document/10387752/
date_added: 2026-08-12
---

Artificial reverberation is the digital effect that makes a dry recording sound as if it were played in a room, hall, or cathedral. One common way to build it is a "delay network": the audio signal loops through several delay lines, and each loop has a filter that gradually quietens (attenuates) the sound at different frequencies to mimic how real rooms absorb high and low tones at different rates. This paper introduces a more accurate way to design that attenuation filter, splitting the job into two stages — a simple filter that gets the overall shape of the decay right, followed by a second, more precise filter (an equalizer) that fine-tunes the decay speed at specific frequencies. The result is a reverb effect that matches the decay characteristics of real rooms more faithfully than earlier single-stage filter designs, while remaining efficient enough to run in real time.

## Concepts
- [[Artificial Reverberation]]
