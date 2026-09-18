---
title: Weakly Labelled AudioSet Tagging with Attention Neural Networks
org: University of Surrey — CVSSP Audio and Music AI
org_type: Lab
country: UK
type: paper
authors: Qiuqiang Kong, Changsong Yu, Turab Iqbal, Yong Xu, Wenwu Wang, Mark D. Plumbley
year: 2019
url: https://arxiv.org/abs/1903.00765
date_added: 2026-08-12
---

This paper tackles a practical problem in teaching AI to recognise sounds: most large audio datasets only tell you that a sound "is somewhere" in a clip, not exactly when it starts or stops (this is called "weak labelling," since the labelling is incomplete compared to marking the precise start/end times). The authors build "attention" neural networks that automatically learn to focus on the most relevant parts of an audio clip when deciding what sound is present, similar to how a listener's ear would naturally tune into the loudest or most distinctive part of a noisy recording. Tested on AudioSet (the same 2-million-clip YouTube sound dataset used across this lab's work), the attention-based approach improved tagging accuracy and became one of the standard techniques used in later sound-recognition systems.

## Concepts
- [[Sound Event Detection]]
- [[Neural Networks for Audio]]
