---
title: Evaluating Podcast Recommendations with Profile-Aware LLM-as-a-Judge
org: Spotify (London R&D)
org_type: Company
country: UK
type: paper
authors: Francesco Fabbri, Gustavo Penha, Edoardo D'Amico, Alice Wang, Marco De Nadai, Jackie Doremus, Paul Gigioli, Andreas Damianou, Oskar Stål, Mounia Lalmas
year: 2025
url: https://research.atspotify.com/publications/evaluating-podcast-recommendations-with-profile-aware-LLM-as-a-Judge
date_added: 2026-08-12
---

Checking whether podcast recommendations are actually good is hard: showing every possible ranking to real users (an "A/B test") is slow and expensive, and simple offline scoring metrics can be misleading. This paper proposes using a large language model (an "LLM," a type of AI trained on huge amounts of text) as an automatic judge instead. First, the system builds a short, readable summary of each listener's interests and habits from 90 days of listening history. Then it gives that summary — rather than raw listening logs — to the LLM, and asks it to judge whether a recommended episode fits the listener, both as a single score and as head-to-head comparisons between episodes. In a study with 47 human participants, this "profile-aware" AI judge agreed with real human judgments about as well as (or better than) giving the AI raw listening history. Co-authored by Mounia Lalmas (London-based Head of Tech Research) and Andreas Damianou (UK-based Senior Research Manager), presented at ACM RecSys, the top academic conference on recommender systems.

## Concepts
- [[Music Recommendation Systems]]
- [[Machine Learning for Music]]
