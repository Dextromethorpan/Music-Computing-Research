---
title: Music Transformer - Generating Music with Long-Term Structure
org: Google (Magenta)
org_type: Company
country: USA
type: paper
authors: Cheng-Zhi Anna Huang, Ashish Vaswani, Jakob Uszkoreit, Noam Shazeer, Ian Simon, Curtis Hawthorne, Andrew M. Dai, Matthew D. Hoffman, Monica Dinculescu, Douglas Eck
year: 2018
url: https://magenta.tensorflow.org/music-transformer
date_added: 2026-08-10
---

Music Transformer adapted the "Transformer" architecture (the same family of neural network later used in large language models like GPT) to the problem of generating symbolic music — sequences of musical notes, similar to a digital sheet-music file, rather than raw audio. Earlier note-generating models tended to lose track of musical structure over time, repeating themselves or wandering aimlessly after a few seconds. Music Transformer introduced a more efficient way for the model to pay attention to how far apart two notes are in time ("relative position"), letting it keep coherent musical themes and repeated patterns over much longer passages — minutes rather than seconds. It remains a foundational reference for symbolic (note-based, as opposed to audio-based) AI music generation.

## Concepts
- [[AI Music Generation]]
- [[Symbolic Music Notation and Representation]]
