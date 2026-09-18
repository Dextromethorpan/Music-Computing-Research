---
title: You Say Search, I Say Recs- A Scalable Agentic Approach to Query Understanding and Exploratory Search at Spotify
org: Spotify (London R&D)
org_type: Company
country: UK
type: paper
authors: Enrico Palumbo, Marcus Isaksson, Alexandre Tamborrino, Maria Movin, Catalin Dincu, Ali Vardasbi, Lev Nikeshkin, Oksana Gorobets, Anders Nyman, Poppy Newdick, Hugues Bouchard, Paul Bennett, Mounia Lalmas, Dani Doro, Christine Doig Cardet, Ziad Sultan
year: 2025
url: https://research.atspotify.com/publications/you-say-search--i-say-recs-a-scalable-agentic-approach-to-query-understanding-and-exploratory-search-at-spotify
date_added: 2026-08-12
---

Some searches, like "new releases for me," aren't really about matching keywords — they're about exploring and discovering things tailored to you, which is normally what a recommendation system (not a search box) is good at. This paper describes how Spotify built an "agentic" system — meaning it uses an AI model as a kind of router or dispatcher — that reads what a user typed, figures out the real intent behind it, and sends the request to whichever backend (search or recommendation) will serve it best, using specialised "sub-agents" for different tasks. Testing on real traffic at Spotify showed large improvements, including a 115% jump in successfully finding similar artists, and a 91% jump in finding new music releases through search. Co-authored by Mounia Lalmas, Spotify's London-based Head of Tech Research for Personalization; presented at ACM RecSys 2025.

## Concepts
- [[Music Recommendation Systems]]
- [[Music Information Retrieval]]
