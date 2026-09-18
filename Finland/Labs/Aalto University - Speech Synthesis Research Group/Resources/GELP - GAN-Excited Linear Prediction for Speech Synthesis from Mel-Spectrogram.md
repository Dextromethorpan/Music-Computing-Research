---
title: GELP - GAN-Excited Linear Prediction for Speech Synthesis from Mel-Spectrogram
org: Aalto University - Speech Synthesis Research Group
org_type: Lab
country: Finland
type: paper
authors: Lauri Juvela, Bajibabu Bollepalli, Junichi Yamagishi, Paavo Alku
year: 2019
url: https://arxiv.org/abs/1904.03976
date_added: 2026-08-12
---

Turning text into spoken audio usually needs a "vocoder" — a component that converts a compact description of speech (like a spectrogram, a picture of which frequencies are loud over time) into an actual sound wave. Older neural vocoders like WaveNet sound great but generate audio one tiny sample at a time, which is slow. This paper combines a generative adversarial network (GAN, two neural networks that compete — one creates fake data, the other tries to catch it, and the "creator" gets better as a result) with classic linear prediction (a decades-old technique for modeling how the vocal tract shapes sound) so the GAN only has to generate the buzzy "excitation" signal from the vocal cords, while a fast, simple filter still produces the final waveform. The result generates speech faster than WaveNet while matching or beating its quality in tests. GELP won the IEEE best student paper award at ICASSP 2016 (for related earlier work) and this paper was presented at Interspeech 2019.

## Concepts
- [[Speech Synthesis]]
- [[Source-Filter Model]]
- [[Neural Networks for Audio]]
