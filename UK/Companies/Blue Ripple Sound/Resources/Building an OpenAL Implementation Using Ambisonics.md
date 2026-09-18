---
title: Building an OpenAL Implementation Using Ambisonics
org: Blue Ripple Sound
org_type: Company
country: UK
type: paper
authors: Richard W. Furse
year: 2009
url: https://www.aes.org/e-lib/browse.cfm?elib=15174
date_added: 2026-08-12
---

OpenAL is a standard way for game software to ask a sound engine to place noises in 3D space. In this paper, Blue Ripple Sound's founder Richard Furse explains how he built an OpenAL "driver" (the piece of software that actually does the 3D placement) using Ambisonics, a mathematical framework for representing a whole 3D "soundfield" rather than fixed speaker channels. He splits the system into three parts: one that tracks where sounds and listeners are, one that turns that into an abstract soundfield, and one that "decodes" the soundfield for whatever speakers or headphones the player has. This let games get consistent, high-quality 3D audio regardless of the player's exact speaker setup.

## Concepts
- [[Ambisonics]]
