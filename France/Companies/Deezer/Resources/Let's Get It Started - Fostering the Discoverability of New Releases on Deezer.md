---
title: Let's Get It Started - Fostering the Discoverability of New Releases on Deezer
org: Deezer
org_type: Company
country: France
type: paper
authors: Léa Briand, Théo Bontempelli, Walid Bendada, Mathieu Morlon, François Rigaud, Benjamin Chapus, Thomas Bouabça, Guillaume Salha-Galvan
year: 2024
url: https://arxiv.org/abs/2401.02827
date_added: 2026-08-09
---

Deezer has hundreds of thousands of new songs and albums uploaded every week, and most of them have no listening history yet — which makes it hard for a normal recommendation system to know who might like them (this is called the "cold start problem," since there's no data yet to "warm up" the recommendation). This paper (presented as an ECIR 2024 Industry Talk) describes how Deezer's team built a system called CF-Cold-Start that predicts, right from a new release's launch, roughly what kind of listeners will enjoy it, based on metadata like the artist and label rather than past plays. They also added a technique called a "contextual bandit," which occasionally recommends promising-but-less-obvious new albums to keep suggestions varied instead of always playing it safe. Real-world testing on Deezer showed the new system triples the number of new albums shown to users and roughly triples click rates on them.

## Concepts
- [[Music Recommendation Systems]]
- [[Cold Start Problem]]
