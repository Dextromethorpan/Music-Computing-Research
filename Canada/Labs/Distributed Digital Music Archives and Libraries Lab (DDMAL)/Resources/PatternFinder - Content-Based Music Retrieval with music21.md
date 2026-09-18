---
title: PatternFinder - Content-Based Music Retrieval with music21
org: Distributed Digital Music Archives and Libraries Lab (DDMAL)
org_type: Lab
country: Canada
type: paper
authors: David Garfinkle, Claire Arthur, Peter Schubert, Julie Cumming, Ichiro Fujinaga
year: 2017
url: https://dl.acm.org/doi/10.1145/3144749.3144751
date_added: 2026-08-12
---

PatternFinder is a tool that searches for a short musical passage (a "query," like a melodic fragment) inside a large collection of digitized scores, and finds every place that pattern occurs or nearly occurs — even if it's transposed to a different key, sped up, slowed down, or slightly altered. This is much harder than searching text because music can have multiple simultaneous melodic lines (polyphony) and the "same" musical idea can appear in many rhythmic disguises. Built on top of the Python music toolkit "music21," PatternFinder implements several geometric search algorithms originally developed at the University of Helsinki. The DDMAL team demonstrated it by having musicologists search for borrowed melodic material across Renaissance-era "imitation masses" (pieces that quote earlier compositions), showing how the tool speeds up the kind of pattern-hunting that scholars used to do by eye.

## Concepts
- [[Music Information Retrieval]]
- [[Melodic Similarity]]
- [[Symbolic Music Notation and Representation]]
