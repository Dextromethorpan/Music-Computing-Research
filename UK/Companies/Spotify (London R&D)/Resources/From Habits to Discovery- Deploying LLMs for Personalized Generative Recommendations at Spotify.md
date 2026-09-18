---
title: From Habits to Discovery- Deploying LLMs for Personalized Generative Recommendations at Spotify
org: Spotify (London R&D)
org_type: Company
country: UK
type: paper
authors: Reid Wilbur, Tarun Chillara, Vladan Radosavljevic, Pooja Chitkara, Sainath Adapa, Juan Elenter, Bernd Huber, Jacqueline Wood, Saaketh Vedantam, Jan Stypka, Sandeep Ghael, Martin D. Gould, David Murgatroyd, Yves Raimond, Mounia Lalmas, Paul N. Bennett
year: 2026
url: https://research.atspotify.com/publications/from-habits-to-discovery-deploying-llms-personalized-generative-recommendations-spotify
date_added: 2026-08-12
---

Podcast listeners often stick to a handful of favorite shows, but their interests also drift over time — so a good recommender needs to balance "more of what you already like" with "help me discover something new." This paper introduces GLIDE, a system Spotify runs in production that uses a large language model (LLM) to generate podcast recommendations. It represents the whole podcast catalog using compact "Semantic IDs" (short codes that capture what a show is about) so the LLM can generate a valid recommendation the way it would generate a sentence, conditioned on a listener's recent history and a summary of their longer-term taste. Tested on millions of real users, GLIDE increased "non-habitual" podcast listening (moving beyond a person's usual shows) by up to 5.4%, and discovery of brand-new shows by up to 14.3%, while still running fast and cheaply enough for production. Co-authored by Mounia Lalmas, Spotify's London-based Head of Tech Research for Personalization; presented at ACM KDD 2026.

## Concepts
- [[Music Recommendation Systems]]
- [[Machine Learning for Music]]
