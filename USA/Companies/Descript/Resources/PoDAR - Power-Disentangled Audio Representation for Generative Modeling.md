---
title: PoDAR - Power-Disentangled Audio Representation for Generative Modeling
org: Descript
org_type: Company
country: USA
type: paper
authors: Alejandro Luebs, Mithilesh Vaidya, Ishaan Kumar, Sumukh Badam, Stephen W. Bailey, Matthew Bendel, Jose Sotelo, Xingzhe He
year: 2026
url: https://arxiv.org/abs/2605.10084
date_added: 2026-08-10
---

PoDAR describes the neural audio codec used inside Descript's Audio Regenerate system. A "codec" compresses audio into a compact numeric representation and can rebuild the sound from it; PoDAR improves on Descript's earlier codec (called DAC) by compressing audio about four times more while keeping quality high, and by separating a clip's loudness ("signal power") from its other content into its own dedicated channel. This separation makes it much easier for a generative model to learn to fill in edited speech at the correct volume, without the loudness "leaking" awkwardly into the wrong parts of the model. It's a good example of how unglamorous representation-design choices (how you encode sound as numbers) can be the key enabler behind flashier AI features like voice editing.

## Concepts
- [[Audio Compression and Codecs]]
- [[Audio Embeddings]]
