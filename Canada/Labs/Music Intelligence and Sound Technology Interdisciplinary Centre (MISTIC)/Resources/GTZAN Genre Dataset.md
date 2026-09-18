---
title: GTZAN Genre Dataset
org: Music Intelligence and Sound Technology Interdisciplinary Centre (MISTIC)
org_type: Lab
country: Canada
type: project
authors: George Tzanetakis, Perry Cook
year: 2002
url: https://www.tensorflow.org/datasets/catalog/gtzan
date_added: 2026-08-12
---

GTZAN is a collection of 1,000 short (30-second) music clips split evenly across ten genres — blues, classical, country, disco, hip-hop, jazz, metal, pop, reggae, and rock — assembled by George Tzanetakis between 2000 and 2001 from CDs, radio, and microphone recordings to accompany his genre-classification research. A "dataset" like this is the labeled example set a machine-learning model trains and is tested on; GTZAN was the first publicly available dataset of its kind for genre recognition and, because of that head start, became the default yardstick almost every subsequent genre-classification paper measured itself against. It is now built into popular machine-learning libraries (this link points to its listing in Google's TensorFlow Datasets catalog) so researchers can load it with a couple of lines of code. Later studies found flaws in it — duplicate tracks, some mislabeled songs — which is now taught alongside the dataset itself as a lesson in why benchmark datasets need to be scrutinized, not just reused blindly.

## Concepts
- [[Music Genre Classification]]
- [[Machine Learning for Music]]
