---
title: Sound Event Detection with Audio-Text Models and Heterogeneous Temporal Annotations
org: Tampere University - Audio Research Group
org_type: Lab
country: Finland
type: paper
authors: Manu Harju, Annamaria Mesaros
year: 2025
url: https://arxiv.org/abs/2508.20703
date_added: 2026-08-12
---

Training a computer to spot specific sounds in a recording (a dog bark, a car horn) usually needs "strong labels" — someone marking the exact start and end time of every sound event, which is slow and expensive to produce by hand. This paper explores using short machine-generated text captions (like "a car passes by") as a cheaper, complementary source of training information alongside a smaller set of precisely time-marked examples. The authors show that mixing in these text captions, especially in a "text-guided" model that reads both audio and language, improves detection accuracy compared to a standard detector — even when only half of the training recordings have precise time labels. This points toward training sound-recognition systems with much less manual labelling effort.

## Concepts
- [[Sound Event Detection]]
- [[Audio Captioning]]
