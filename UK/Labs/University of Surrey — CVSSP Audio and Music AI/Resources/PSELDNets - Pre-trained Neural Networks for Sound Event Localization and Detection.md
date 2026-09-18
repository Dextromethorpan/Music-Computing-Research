---
title: PSELDNets - Pre-trained Neural Networks for Sound Event Localization and Detection
org: University of Surrey — CVSSP Audio and Music AI
org_type: Lab
country: UK
type: paper
authors: Jinbo Hu, Yin Cao, Ming Wu, Fang Kang, Feiran Yang, Wenwu Wang, Mark D. Plumbley, Jun Yang
year: 2024
url: https://arxiv.org/abs/2411.06399
date_added: 2026-08-12
---

Sound Event Localization and Detection (SELD) means figuring out not just what sound is happening (a car horn, a dog bark) but also which direction it's coming from, using recordings made with multiple microphones arranged to capture 3D sound. Training good SELD systems usually needs a lot of realistic labelled recordings, which are expensive to collect. This paper builds a very large synthetic (computer-simulated) training set — over 1,000 hours of audio spanning 170 sound categories, created by digitally placing sound recordings into simulated rooms — and pretrains neural networks on it before fine-tuning on real data. The resulting "PSELDNets" outperform previous state-of-the-art systems on every public SELD benchmark tested, showing that large-scale synthetic pretraining is a practical shortcut for this normally data-hungry task.

## Concepts
- [[Sound Event Detection]]
- [[Immersive Spatial Audio]]
