---
title: NSynth - Neural Audio Synthesis
org: Google (Magenta)
org_type: Company
country: USA
type: paper
authors: Jesse Engel, Cinjon Resnick, Adam Roberts, Sander Dieleman, Karen Simonyan, Mohammad Norouzi, Douglas Eck
year: 2017
url: https://magenta.tensorflow.org/nsynth
date_added: 2026-08-10
---

NSynth ("Neural Synthesis") was one of Magenta's earliest and most influential projects, a collaboration between Google Brain and DeepMind. Instead of programming a synthesizer with hand-designed rules for how a sound should behave, NSynth trains a neural network (a "WaveNet-style autoencoder," a model that learns to compress and then rebuild raw audio waveforms) directly on recordings of real instruments. Because the model learns its own internal representation of timbre, it can smoothly morph between the sound of, say, a flute and a sitar, creating entirely new hybrid instrument sounds that don't exist physically. NSynth also came with a large public dataset of individually-labeled musical notes that other researchers still use today to benchmark audio models.

## Concepts
- [[Neural Networks for Audio]]
- [[Audio Sampling (Sample-Based Synthesis)]]
