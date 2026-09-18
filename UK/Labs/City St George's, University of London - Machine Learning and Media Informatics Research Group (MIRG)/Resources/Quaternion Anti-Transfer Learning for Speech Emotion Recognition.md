---
title: Quaternion Anti-Transfer Learning for Speech Emotion Recognition
org: City St George's, University of London - Machine Learning and Media Informatics Research Group (MIRG)
org_type: Lab
country: UK
type: paper
authors: Eric Guizzo, Tillman Weyde, Giacomo Tarroni, Danilo Comminiello
year: 2023
url: https://ieeexplore.ieee.org/document/10248082/
date_added: 2026-08-12
---

Detecting emotion from someone's voice (are they angry, happy, sad?) is tricky because a model can accidentally learn to key off the specific words said or the speaker's identity rather than genuine emotional cues. "Anti-transfer learning" is a training trick that deliberately discourages the network from relying on those unwanted shortcuts, making it focus on emotion instead. This paper combines that idea with "quaternion" neural networks — a way of processing four numbers together as a single mathematical unit, which turns out to be an efficient, compact way to represent audio features — to build a speech emotion recognizer that is both more accurate and computationally lighter than standard approaches.

## Concepts
- [[Affective Computing (Music)]]
- [[Speech Synthesis]]
