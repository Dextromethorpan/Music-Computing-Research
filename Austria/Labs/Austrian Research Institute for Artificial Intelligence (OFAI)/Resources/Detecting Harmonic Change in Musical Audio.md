---
title: Detecting Harmonic Change in Musical Audio
org: Austrian Research Institute for Artificial Intelligence (OFAI)
org_type: Lab
country: Austria
type: paper
authors: Christopher Harte, Mark Sandler, Martin Gasser
year: 2006
url: https://www.ofai.at/~martin.gasser/papers/oefai-tr-2006-13.pdf
date_added: 2026-08-09
---

This paper introduces a method for automatically detecting the moments in a piece of recorded music where the harmony changes — for example, where a chord changes from C major to G major. It works by extracting a "chroma" representation of the audio (a way of summarizing which of the 12 musical pitch classes, like C, C#, D, etc., are present at each moment, regardless of octave) and then measuring how much that representation shifts from one instant to the next. Detecting harmonic change automatically is a building block for other tasks, like automatic chord recognition or splitting a song into structural sections (verse, chorus, bridge). It was written jointly with researchers from Queen Mary University of London's Centre for Digital Music, reflecting the kind of international collaboration common between European music-computing labs.

## Concepts
- [[Music Information Retrieval]]
