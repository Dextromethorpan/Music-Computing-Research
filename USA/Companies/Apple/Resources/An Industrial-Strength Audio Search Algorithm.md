---
title: An Industrial-Strength Audio Search Algorithm
org: Apple
org_type: Company
country: USA
type: paper
authors: Avery Li-Chun Wang
year: 2003
url: https://www.ee.columbia.edu/~dpwe/papers/Wang03-shazam.pdf
date_added: 2026-08-10
---

This is the foundational paper behind Shazam, published at ISMIR 2003 by Avery Wang, the algorithm's inventor. It explains "audio fingerprinting": turning a song into a sparse map of the loudest time-and-frequency points in its spectrogram (like a star chart), then hashing pairs of those points into compact codes. To identify a song from a noisy phone recording, the same process is run on the sample and the resulting codes are matched against a huge database of pre-fingerprinted tracks, looking for many matches that line up at a consistent time offset. The approach is famous for working even with heavy background noise, voice-call compression, and multiple songs playing at once. It remains the conceptual basis for how Shazam (and much of the music-recognition industry) identifies songs today.

## Concepts
- [[Audio Fingerprinting]]
- [[Music Information Retrieval]]
- [[Signal Processing]]
