---
title: STONE - Self-supervised Tonality Estimator
org: Deezer
org_type: Company
country: France
type: paper
authors: Yuexuan Kong, Vincent Lostanlen, Gabriel Meseguer-Brocal, Stella Wong, Mathieu Lagrange, Romain Hennequin
year: 2024
url: https://arxiv.org/abs/2407.07408
date_added: 2026-08-09
---

"Key" in music (like "C major" or "A minor") describes which set of notes a song is built around, and figuring it out automatically has traditionally required a lot of manually labeled training examples. STONE is the first tool of its kind to estimate a song's musical key without needing any human-labeled data at all. It works by training a neural network to notice how much a short audio clip has been artificially pitch-shifted compared to another clip from the same song, without ever being told the key outright — and this task turns out to teach the network to recognize key signatures on its own. The team then extended the method with a little bit of human-labeled data to also distinguish major keys from minor keys sharing the same signature (e.g., C major vs. A minor). Tested on a new dataset of 5,489 real songs, the lightly-supervised version matched the accuracy of a fully human-labeled model while needing far less manual labeling.

## Concepts
- [[Self-Supervised Learning for Audio]]
- [[Music Information Retrieval]]
