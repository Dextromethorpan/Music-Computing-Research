---
title: True Analog Emulation (TAE) Technology Overview
org: Arturia
org_type: Company
country: France
type: blog post
authors: Arturia
year: Not found
url: https://www.arturia.com/technology/tae
date_added: 2026-08-09
---

Old analog synthesizers make sound using physical electronic circuits (oscillators and filters made of real wires, capacitors and transistors), which naturally have tiny imperfections — slight pitch drift, a bit of noise, a "not-quite-perfect" waveform shape — that many musicians find warm and pleasing. TAE (True Analog Emulation) is Arturia's proprietary technique for recreating that same warmth entirely in software, by mathematically modeling how those circuits actually misbehave rather than just recording samples of them. The page explains that TAE oscillators are "free-running" (continuously generated in real time, not replayed from a stored sample) and are deliberately built to avoid a common digital synthesis defect called aliasing (see the Aliasing concept note) even during techniques like pulse-width modulation. It also describes how TAE reproduces analog filters and "soft clipping" (a gentle way of preventing a signal from getting too loud), which are both key ingredients of the classic analog synth sound. This is a marketing-facing technical explainer rather than an academic paper, but it does describe real, specific DSP modeling choices Arturia's engineers made.

## Concepts
- [[True Analog Emulation (TAE)]]
- [[Aliasing (Digital Audio)]]
