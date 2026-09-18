---
title: Arco - A Flexible Audio Processing Framework
org: Carnegie Mellon University Computer Music Project
org_type: Lab
country: USA
type: paper
authors: Roger Dannenberg
year: 2025
url: https://www.cs.cmu.edu/~rbd/papers/arco-icmc2025-web.pdf
date_added: 2026-08-10
---

Arco is a lightweight sound-synthesis engine, presented at ICMC 2025, designed to run as a small embedded "server" that other software can plug into — for example, inside a bigger application, as its own separate process, or even on a low-power computer like a Raspberry Pi. Rather than reinventing synthesis algorithms from scratch, Arco delegates the actual sound-generation math to Faust (an existing audio programming language), while letting other programming languages control it in real time over a network-friendly communication system called O2 (also developed by Dannenberg's group). This design lets composers and developers connect Arco to many different front-end tools without being locked into one specific programming environment.

## Concepts
- [[Signal Processing]]
- [[Open Source Research Tools]]
