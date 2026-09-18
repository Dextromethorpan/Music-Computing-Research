---
title: An Industrial-Strength Audio Search Algorithm (Wang 2003)
org: Shazam
org_type: Company
country: UK
type: paper
authors: Avery Li-Chun Wang
year: 2003
url: https://www.ee.columbia.edu/~dpwe/papers/Wang03-shazam.pdf
date_added: 2026-08-12
---

This is the landmark paper (presented at ISMIR 2003) that describes the algorithm still powering Shazam today. The core idea is "audio fingerprinting": instead of storing or comparing whole songs, the system turns a recording into a spectrogram (a picture of which frequencies are loud at each moment in time) and picks out only the loudest, most distinctive points — like the brightest stars in a night sky. This sparse set of points is called a "time-frequency constellation," and pairs of nearby points are combined into compact codes ("hashes") that together form a fingerprint unique enough to identify a song even from a few noisy seconds recorded on a phone in a noisy bar. Because the fingerprint only depends on a small number of strong, robust points rather than the full audio signal, it survives background noise, low-quality microphones, and compression — which is why matching still works in real-world conditions. A huge database of songs is pre-fingerprinted, and a new recording's fingerprint is compared against millions of stored fingerprints almost instantly using the shared hash codes. This paper is the single most important resource for understanding Shazam's technology and is widely cited as the origin of practical, "industrial-strength" audio fingerprinting.

## Concepts
- [[Audio Fingerprinting]]
- [[Music Information Retrieval]]
- [[Signal Processing]]
