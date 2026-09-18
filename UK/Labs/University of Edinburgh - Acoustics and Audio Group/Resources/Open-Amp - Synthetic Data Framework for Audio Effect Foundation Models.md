---
title: Open-Amp - Synthetic Data Framework for Audio Effect Foundation Models
org: University of Edinburgh - Acoustics and Audio Group
org_type: Lab
country: UK
type: paper
authors: Alistair Carson et al. (University of Edinburgh)
year: 2024
url: https://arxiv.org/html/2411.14972v1
date_added: 2026-08-12
---

Training a neural network to imitate a specific guitar amplifier or effects pedal normally requires recording real audio through that real piece of hardware — slow and expensive if you want to cover many devices. Open-Amp instead generates large amounts of synthetic (computer-created) training data that mimics a wide range of amplifier and distortion behaviors, so a single general-purpose "foundation" model can be trained to emulate many different audio effects without needing physical hardware for each one. This points toward more flexible, all-purpose neural audio-effect models rather than one narrow model per device.

## Concepts
- [[Neural Networks for Audio]]
- [[True Analog Emulation (TAE)]]
