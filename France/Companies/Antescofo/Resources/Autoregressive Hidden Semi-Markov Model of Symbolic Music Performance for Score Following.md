---
title: Autoregressive Hidden Semi-Markov Model of Symbolic Music Performance for Score Following
org: Antescofo
org_type: Company
country: France
type: paper
authors: Eita Nakamura, Philippe Cuvillier, Arshia Cont, Nobutaka Ono, Shigeki Sagayama
year: 2015
url: https://inria.hal.science/hal-01183820v1/document
date_added: 2026-08-09
---

This paper improves the statistical model at the heart of score-following systems like Antescofo — the part that predicts how a human performer's timing and note durations will unfold, based on probability. A "hidden Markov model" is a common way for software to guess an unseen state (here, "which note is being played right now") from what it can actually observe (the incoming sound); this paper extends that idea to also account for how one note's timing tends to depend on the notes just before it, which better matches how real musicians actually play with natural tempo flow, improving tracking accuracy. It was published at ISMIR, the main international research conference for music information retrieval.

## Concepts
- [[Score Following]]
