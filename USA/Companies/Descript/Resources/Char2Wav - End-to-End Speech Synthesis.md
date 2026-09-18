---
title: Char2Wav - End-to-End Speech Synthesis
org: Descript
org_type: Company
country: USA
type: paper
authors: Jose Sotelo, Soroush Mehri, Kundan Kumar, João Felipe Santos, Kyle Kastner, Aaron Courville, Yoshua Bengio
year: 2017
url: https://openreview.net/pdf?id=B1VWyySKx
date_added: 2026-08-10
---

Char2Wav is an early "end-to-end" text-to-speech system built by Jose Sotelo, Kundan Kumar and collaborators at MILA (University of Montreal) — two years before they founded the voice-cloning startup Lyrebird, which Descript later acquired to build its Overdub feature. Instead of the traditional pipeline of separate hand-built stages, Char2Wav uses one neural network (a "reader" with attention) to turn text into acoustic features, and a second neural network (a vocoder based on SampleRNN) to turn those features directly into a raw sound wave. This proved that a computer could learn to read text aloud almost entirely by training on examples, without needing linguists to hand-code pronunciation rules. It's a foundational piece of the research lineage that eventually became Descript's Overdub voice-cloning technology.

## Concepts
- [[Speech Synthesis]]
- [[Neural Networks for Audio]]
