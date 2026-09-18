---
title: kNN-SVC
org: UC San Diego CREATE and CRCA
org_type: Lab
country: USA
type: paper
authors: Keren Shao, Ke Chen, Matthew Baas, Shlomo Dubnov
year: 2025
url: https://arxiv.org/abs/2504.05686
date_added: 2026-08-10
---

kNN-SVC is an ICASSP 2025 paper on "zero-shot" singing voice conversion — changing a singing recording so it sounds like it was sung by a different singer, without needing the AI to be specially retrained for that target voice first ("zero-shot" means it can work with a singer's voice it has never trained on, from just a short reference clip). It builds on an existing technique called kNN-VC, which converts voices by finding and stitching together the closest-matching chunks of a target speaker's reference audio, and fixes two of that method's weaknesses: it adds back missing harmonic detail (so the converted voice doesn't sound dull or "ringy"), and it smooths the transitions between stitched-together audio chunks so the joins sound natural. A demo page with audio examples is linked from the paper.

## Concepts
- [[Voice Conversion]]
- [[Singing Voice Synthesis]]
