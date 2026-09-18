---
title: Structure-informed Positional Encoding for Music Generation
org: Télécom Paris — S2A (ADASP)
org_type: Lab
country: France
type: paper
authors: Manvi Agarwal, Changhong Wang, Gaël Richard
year: 2024
url: https://adasp.telecom-paris.fr/resources/2024-04-11-icassp-agarwal/
date_added: 2026-08-09
---

Computers that generate music note-by-note (like an AI composer) often lose the plot over time — the melody can wander without any sense of verses, choruses, or repeated sections, the way a piece of real music usually has. This paper, presented at the ICASSP 2024 signal processing conference, tackles that problem by teaching the AI system about the music's underlying structure while it is generating notes. Instead of just remembering the previous few notes, the model gets extra positional information that hints at "where in the song's larger structure" each note sits, similar to giving the model a map of the song's sections instead of only a compass. The result is generated music that stays more coherent and organized over longer stretches, rather than drifting into repetitive or aimless patterns.

## Concepts
- [[AI Music Generation]]
- [[Positional Encoding]]
