---
title: Web-Based Networked Music Performances via WebRTC - A Low-Latency PCM Audio Solution
org: Internet Media Group (Politecnico di Torino)
org_type: Lab
country: Italy
type: paper
authors: Matteo Sacchetto, Paolo Gastaldi, Chris Chafe, Cristina Rottondi, Antonio Servetti
year: 2022
url: https://doi.org/10.17743/jaes.2022.0021
date_added: 2026-08-14
---

This paper (published in the Journal of the Audio Engineering Society) tackles a practical problem: web browsers weren't built to carry the pristine, uncompressed audio that musicians need to play together remotely in real time. The standard browser video-call technology, WebRTC, normally compresses audio in ways that add delay and lose quality. The researchers built a workaround that sends raw, uncompressed digital audio (PCM, the same basic format used on CDs) through a browser's lower-level data channel instead, cutting delay down to as little as 40 milliseconds — fast enough that two musicians in different cities can keep time together, since anything much slower feels like a lag when playing music live.

## Concepts
- [[Latency]]
