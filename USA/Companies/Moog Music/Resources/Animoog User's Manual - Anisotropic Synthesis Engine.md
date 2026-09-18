---
title: Animoog User's Manual - Anisotropic Synthesis Engine
org: Moog Music
org_type: Company
country: USA
type: product documentation
authors: Moog Music Inc.
year: 2015
url: https://api.moogmusic.com/sites/default/files/2018-10/AnimoogManual.pdf
date_added: 2026-08-13
---

Animoog is Moog's software synthesizer app, and its core sound-generating engine is a specifically named, documented mechanism called the Anisotropic Synthesis Engine (ASE). Instead of picking one waveform (one basic shape of sound wave) and sticking with it, ASE arranges 8 "timbres" (each built from 16 waveforms recorded from real Moog hardware) across a 2D grid. As a note plays, a moving point glides through that grid along a path you design, continuously blending between nearby waveforms — so the tone of a single held note can morph and evolve on its own, like a miniature animated journey through many related sounds instead of one static tone. The output is still run through a classic Moog-style filter and effects afterward. This is a genuinely distinct, officially documented synthesis architecture (not just a marketing name for ordinary wavetable synthesis), which is why it counts as its own technical innovation.

## Concepts
- [[Real-Time Sound Synthesis]]
