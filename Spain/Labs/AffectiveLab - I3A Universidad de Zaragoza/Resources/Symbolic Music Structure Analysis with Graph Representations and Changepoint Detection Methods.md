---
title: Symbolic Music Structure Analysis with Graph Representations and Changepoint Detection Methods
org: AffectiveLab - I3A Universidad de Zaragoza
org_type: Lab
country: Spain
type: paper
authors: Carlos Hernandez-Olivan, Jose R. Beltran
year: 2025
url: https://www.sciencedirect.com/science/article/pii/S0925231225028802
date_added: 2026-08-12
---

This paper tackles "music structure analysis" — automatically finding where a piece of music changes section (like verse to chorus). Instead of working with audio recordings, it works with symbolic music, meaning music represented as note data (like a digital score or a MIDI file) rather than as sound waves. The authors represent a piece as a graph — a network of notes connected by their musical relationships — and then apply "changepoint detection," a statistical technique for spotting the exact moments where the pattern of the music shifts. They introduce two new graph-based methods (called G-PELT and G-Window) and test them on real datasets of classical and folk music, finding they detect section boundaries better than older feature-based approaches. The best method was added to musicaiz, an open-source toolkit the same group built, so other researchers can reuse it.

## Concepts
- [[Computational Musicology]]
- [[Symbolic Music Notation and Representation]]
- [[Music Information Retrieval]]
