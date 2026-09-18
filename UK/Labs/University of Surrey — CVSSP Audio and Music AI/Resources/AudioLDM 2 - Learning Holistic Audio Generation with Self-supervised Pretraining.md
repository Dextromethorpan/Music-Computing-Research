---
title: AudioLDM 2 - Learning Holistic Audio Generation with Self-supervised Pretraining
org: University of Surrey — CVSSP Audio and Music AI
org_type: Lab
country: UK
type: paper
authors: Haohe Liu, Qiao Tian, Yi Yuan, Xubo Liu, Xinhao Mei, Qiuqiang Kong, Yuping Wang, Wenwu Wang, Yuxuan Wang, Mark D. Plumbley
year: 2023
url: https://arxiv.org/abs/2308.05734
date_added: 2026-08-12
---

AudioLDM 2 is a single AI system that can generate speech, music, and general sound effects from a short text description (e.g. "a dog barking while it rains"), instead of needing separate specialised models for each. It works by first translating whatever input it's given (text, audio, or an image) into an in-between representation the authors call the "language of audio," and then uses a "diffusion model" — an AI technique that starts from random noise and gradually refines it into a realistic result — to turn that representation into a finished audio clip. The novelty is treating speech, music, and sound effects as fundamentally the same generation problem rather than three separate ones. The system was developed by CVSSP researchers together with collaborators and became one of the most widely used open-source text-to-audio generators.

## Concepts
- [[AI Music Generation]]
- [[Diffusion Models for Audio]]
