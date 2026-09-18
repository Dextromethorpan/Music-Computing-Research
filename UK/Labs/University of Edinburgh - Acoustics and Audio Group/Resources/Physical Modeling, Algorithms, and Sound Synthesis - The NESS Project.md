---
title: Physical Modeling, Algorithms, and Sound Synthesis - The NESS Project
org: University of Edinburgh - Acoustics and Audio Group
org_type: Lab
country: UK
type: paper
authors: Stefan Bilbao, Craig J. Webb, Michele Ducceschi, et al.
year: 2019
url: https://direct.mit.edu/comj/article/43/2-3/15/94679/Physical-Modeling-Algorithms-and-Sound-Synthesis
date_added: 2026-08-12
---

NESS (Next Generation Sound Synthesis) was a five-year research project at Edinburgh that generated realistic instrument and room sounds not by recording anything, but by simulating the physics of vibrating objects (strings, drums, brass tubes) and of rooms, directly on a computer. Instead of shortcuts, the team used detailed numerical methods (essentially solving the physics equations bit by bit, moment by moment) which is very computationally heavy, so they ran the simulations on graphics cards (GPUs) built for video games to make it fast enough. The output is fully synthetic sound that reacts physically correctly to how you "play" the virtual instrument. This Computer Music Journal paper summarizes the algorithms, results, and later commercial plugins (Physical Audio) that came out of the project.

## Concepts
- [[Physical Modeling Synthesis]]
- [[Real-Time Sound Synthesis]]
- [[Room Acoustics]]
