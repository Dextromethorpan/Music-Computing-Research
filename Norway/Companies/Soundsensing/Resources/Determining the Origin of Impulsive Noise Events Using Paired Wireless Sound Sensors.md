---
title: Determining the Origin of Impulsive Noise Events Using Paired Wireless Sound Sensors
org: Soundsensing
org_type: Company
country: Norway
type: paper
authors: Fabian Nemazi, Jon Nordby
year: 2021
url: https://arxiv.org/pdf/2108.11758
date_added: 2026-08-09
---

This paper tackles a practical noise-monitoring problem: if a neighbor hears a loud bang, how do you automatically tell whether it came from a specific noisy facility (like a shooting range) or from somewhere else? The authors placed one wireless sound sensor at the known noise source and another near the affected neighborhood, then trained machine-learning models on each sensor's data and combined their outputs to decide whether a detected noise event really originated at the facility being monitored. The system correctly identified the source in the large majority of test cases, while keeping raw audio private by converting sound into a privacy-safe visual representation (a spectrogram) before any analysis or transmission.

## Concepts
- [[Sound Event Detection]]
- [[Sound Perception and Psychoacoustics]]
