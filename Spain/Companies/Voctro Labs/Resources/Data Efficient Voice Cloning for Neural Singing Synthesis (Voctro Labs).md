---
title: Data Efficient Voice Cloning for Neural Singing Synthesis (Voctro Labs)
org: Voctro Labs
org_type: Company
country: Spain
type: paper
authors: Merlijn Blaauw, Jordi Bonada, Ryunosuke Daido
year: 2019
url: https://arxiv.org/pdf/1902.07292
date_added: 2026-08-12
---

This paper (ICASSP 2019) by Voctro Labs co-founders Merlijn Blaauw and Jordi Bonada, with Yamaha researcher Ryunosuke Daido, tackles a practical problem: normally, training a computer to sing convincingly in a specific person's voice needs a large amount of recorded singing from that person. The authors show that if a model is first trained on many different singers combined, it only needs a couple of minutes of a brand-new target voice to convincingly "clone" that voice afterward — a technique called voice cloning or speaker adaptation. Listening tests (where real people compared audio clips) showed the cloned voices sounded about as good as voices trained the traditional, data-heavy way. This "learn from many, then adapt with just a little data" method is the direct technical ancestor of Holly+, Voctro Labs' voice-clone project built with musician Holly Herndon, and of Voctro Labs' broader voice-cloning tools.

## Concepts
- [[Voice Conversion]]
- [[Singing Voice Synthesis]]
- [[Neural Networks for Audio]]
