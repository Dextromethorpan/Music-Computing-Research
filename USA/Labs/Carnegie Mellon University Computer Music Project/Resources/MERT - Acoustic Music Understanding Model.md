---
title: MERT - Acoustic Music Understanding Model
org: Carnegie Mellon University Computer Music Project
org_type: Lab
country: USA
type: paper
authors: Yizhi Li, Ruibin Yuan, Ge Zhang, et al. (including Roger Dannenberg)
year: 2023
url: https://arxiv.org/abs/2306.00107
date_added: 2026-08-10
---

MERT is a large neural network trained to "understand" music audio without needing humans to label millions of examples first — a technique called self-supervised learning, where the model learns by predicting hidden or masked parts of the audio itself. Roger Dannenberg is a co-author. To get music-specific understanding (not just generic audio understanding), the model is trained against two "teacher" signals: one focused on general acoustic detail, and one built on the Constant-Q Transform, a way of representing sound that lines up well with musical pitch. The resulting model, once trained, can be reused as a foundation for many downstream tasks — like recognizing beat, key, genre, or instrument — without training a brand-new model from scratch for each one, and it reached state-of-the-art results across 14 such music-understanding tasks.

## Concepts
- [[Self-Supervised Learning for Audio]]
- [[Music Information Retrieval]]
- [[Neural Networks for Audio]]
