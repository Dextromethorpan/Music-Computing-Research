---
title: Pedalboard
org: Spotify Research
org_type: Company
country: USA
type: project
authors: Peter Sobot and the Spotify Audio Intelligence Lab
year: 2021
url: https://github.com/spotify/pedalboard
date_added: 2026-08-09
---

Pedalboard is a free, open-source software library (a Python package, meaning programmers can install it and call its functions from their own code) that lets a computer program load, edit, and save audio with studio-quality effects such as reverb, distortion, compression, and pitch shifting. It can also load professional plugin formats used by real recording-studio software (VST3 and Audio Unit), so a programmer can reuse existing high-quality effect tools instead of writing new ones from scratch. Inside Spotify, the tool is used behind the scenes to make training data for machine-learning models more varied (for example, by adding realistic distortions to sound so a model learns to handle messy real-world audio), and it powers consumer features like the AI DJ and AI Voice Translation. Because it runs very fast, it can process audio effects much quicker than playing them back in real time.

## Concepts
- [[Signal Processing]]
- [[Open Source Research Tools]]
- [[Automatic Mixing and Mastering]]
