---
title: Beyond Collaborative Filtering - Using Transformers for Personalized Music Recommendation
org: Amazon
org_type: Company
country: USA
type: paper
authors: Amina Shabbeer et al.
year: 2025
url: https://www.amazon.science/publications/beyond-collaborative-filtering-using-transformers-for-personalized-music-recommendation
date_added: 2026-08-10
---

Music recommendation is tricky because a listener's taste is both stable (their favorite genres) and momentary (what mood they're in right now). Traditional "collaborative filtering" methods mostly compare users to other similar users, but struggle to weigh recent listening against long-term preference. This Amazon Music paper adapts a transformer — the same family of neural network architecture behind large language models — to model a listener's playback history as a sequence, and shows that removing a restriction called "causal masking" (which normally forces the model to only look backward in time) lets it better capture overall taste rather than just what comes next. The result was roughly a 28% improvement in prediction accuracy over a standard neural baseline.

## Concepts
- [[Music Recommendation Systems]]
- [[Machine Learning for Music]]
