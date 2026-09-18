---
title: PromptVC - Flexible Stylistic Voice Conversion in Latent Space Driven by Natural Language Prompts
org: A*STAR Institute for Infocomm Research (I2R)
org_type: Lab
country: Singapore
type: paper
authors: Jixun Yao, Yuguang Yang, Yi Lei, Ziqian Ning, Yanni Hu, Yu Pan, Jingjing Yin, Hongbin Zhou, Chang Huai You (I2R), Heng Lu, Lei Xie
year: 2024
url: https://arxiv.org/abs/2309.09262
date_added: 2026-08-09
---

PromptVC tackles "style" voice conversion — changing not just who a voice sounds like, but how it's delivered (e.g. more cheerful, calmer, more formal). Instead of forcing users to pick from a fixed list of style labels or supply a matching reference recording, PromptVC lets a user describe the desired speaking style in plain natural-language text (a "prompt"). Internally, it uses a technique called a latent diffusion model — a type of generative AI that gradually turns random noise into a meaningful result — to turn that text description into a "style vector" that then guides the voice conversion. It also uses a pretrained speech model (HuBERT) to represent the linguistic content of the input separately from its style. I2R scientist Chang Huai You is a co-author on this ICASSP 2024 paper, alongside teams from Northwestern Polytechnical University and Ximalaya Inc.

## Concepts
- [[Voice Conversion]]
- [[Speech Synthesis]]
