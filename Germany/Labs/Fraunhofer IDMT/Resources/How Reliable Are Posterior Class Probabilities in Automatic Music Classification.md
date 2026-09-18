---
title: How Reliable Are Posterior Class Probabilities in Automatic Music Classification
org: Fraunhofer IDMT
org_type: Lab
country: Germany
type: paper
authors: Hanna Lukashevich, Sascha Grollmisch, Jakob Abeßer, Sebastian Stober, Joachim Bös
year: 2023
url: https://publica.fraunhofer.de/handle/publica/456747
date_added: 2026-08-09
---

When an AI model classifies a song's genre, it usually also outputs a confidence score (a "probability") alongside its guess. This paper asks whether those confidence scores can actually be trusted — if a model says "90% sure this is jazz," is it really right 90% of the time? The authors test several music genre classifiers and find that raw confidence scores are often overconfident or poorly calibrated, then explore ways to make them more reliable. This matters for real-world metadata systems, where a human reviewer might only want to double-check the tracks the AI is genuinely uncertain about.

## Concepts
- [[Music Information Retrieval]]
- [[Machine Learning for Music]]
