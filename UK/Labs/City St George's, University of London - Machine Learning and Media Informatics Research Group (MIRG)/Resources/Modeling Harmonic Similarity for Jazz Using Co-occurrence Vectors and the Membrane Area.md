---
title: Modeling Harmonic Similarity for Jazz Using Co-occurrence Vectors and the Membrane Area
org: City St George's, University of London - Machine Learning and Media Informatics Research Group (MIRG)
org_type: Lab
country: UK
type: paper
authors: Carey Bunks, Tillman Weyde, Simon Dixon, Bruno Di Giorgi
year: 2023
url: https://archives.ismir.net/ismir2023/paper/000090.pdf
date_added: 2026-08-12
---

How do you tell a computer that two jazz songs "feel" harmonically similar even after one has been reharmonized (had its chords substituted with jazzier alternatives)? This ISMIR 2023 paper borrows an idea from natural language processing — representing chords as vectors based on which other chords they tend to appear near, the way word meanings are learned from context — and turns a song's chord sequence into a path through that vector space. Comparing the shapes of two paths (using a geometric idea called the "membrane area" between them) gives a robust similarity score that survives reharmonization, which simpler chord-matching methods can't handle well.

## Concepts
- [[Melodic Similarity]]
- [[Computational Musicology]]
