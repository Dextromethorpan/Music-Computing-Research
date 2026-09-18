---
title: VampNet - Music Generation via Masked Acoustic Token Modeling
org: Northwestern Interactive Audio Lab
org_type: Lab
country: USA
type: paper
authors: Hugo Flores Garcia, Prem Seetharaman, Rithesh Kumar, Bryan Pardo
year: 2023
url: https://interactiveaudiolab.github.io/assets/papers/ismir2023-flores-seetharaman-pardo.pdf
date_added: 2026-08-10
---

VampNet is an AI model that generates music audio by first converting sound into a sequence of discrete "tokens" (a bit like turning audio into a string of code words a computer can process, similar to how text is broken into words) and then learning to fill in tokens that have been hidden, or "masked." By choosing which parts of a piece to mask and regenerate, a user can get VampNet to compress music, fill in a gap (inpainting), extend a track (outpainting/continuation), or create a repeating variation of a loop ("vamping" — a jazz term for a repeated backing pattern). Because it processes all tokens at once rather than one at a time, it can generate a full clip in far fewer computational steps than older step-by-step generation methods, while still sounding coherent. A live demo and open-source code are both publicly available.

## Concepts
- [[AI Music Generation]]
- [[Neural Networks for Audio]]
