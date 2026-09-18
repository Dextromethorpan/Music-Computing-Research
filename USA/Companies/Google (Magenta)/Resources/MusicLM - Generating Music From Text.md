---
title: MusicLM - Generating Music From Text
org: Google (Magenta)
org_type: Company
country: USA
type: paper
authors: Andrea Agostinelli, Timo I. Denk, Zalán Borsos, Jesse Engel, Mauro Verzetti, Antoine Caillon, Qingqing Huang, Aren Jansen, Adam Roberts, Marco Tagliasacchi, Matt Sharifi, Neil Zeghidour, Christian Frank
year: 2023
url: https://arxiv.org/abs/2301.11325
date_added: 2026-08-10
---

MusicLM is a Google Research/Google Brain model that turns a written description — like "a calming violin melody backed by a distorted guitar riff" — into a full, several-minutes-long piece of music at high audio quality. It works by breaking the problem into stages, first learning to represent audio as sequences of discrete "tokens" (a bit like turning sound into a string of symbols a language model can predict), then generating those token sequences conditioned on the text. It can also take a hummed or whistled melody as an additional input and re-render it in the style described by the text. This paper is a foundational reference point behind Google's later real-time and product-facing music generation tools.

## Concepts
- [[Text-to-Music Generation]]
- [[AI Music Generation]]
- [[Audio Embeddings]]
