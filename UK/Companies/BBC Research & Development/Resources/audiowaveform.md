---
title: audiowaveform
org: BBC Research & Development
org_type: Company
country: UK
type: project
authors: BBC R&D (Chris Needham et al.)
year: 2013
url: https://github.com/bbc/audiowaveform
date_added: 2026-08-12
---

audiowaveform is an open-source command-line tool from BBC R&D that takes an audio file and generates the data needed to draw a "waveform" picture of it — the zig-zag shape you see in audio editors showing how loud the sound is at each moment. Rather than recalculating this every time a webpage or app needs to show a waveform, audiowaveform pre-computes small data files (or waveform images directly) that can be reused efficiently. It is a foundational piece of infrastructure behind the BBC's own web-based audio tools, and is widely used elsewhere as a lightweight, well-tested building block for audio interfaces.

## Concepts
- [[Open Source Research Tools]]
- [[Signal Processing]]
