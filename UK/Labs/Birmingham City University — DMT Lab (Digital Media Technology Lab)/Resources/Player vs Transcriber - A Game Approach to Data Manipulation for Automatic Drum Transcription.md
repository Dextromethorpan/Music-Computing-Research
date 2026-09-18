---
title: Player vs Transcriber - A Game Approach to Data Manipulation for Automatic Drum Transcription
org: Birmingham City University — DMT Lab (Digital Media Technology Lab)
org_type: Lab
country: UK
type: paper
authors: Carl Southall, Ryan Stables, Jason Hockman
year: 2018
url: https://github.com/CarlSouthall/Player-Vs-Transcriber
date_added: 2026-08-12
---

Machine-learning systems for drum transcription need lots of labelled training audio (recordings with a human-verified answer key of exactly which drum was hit when), and it's easy for the system to just memorize the specific recordings it trained on rather than learning general drum-recognition skills. This ISMIR 2018 paper frames training as a competitive "game": a "player" model tries to subtly alter or complicate the training audio to make transcription harder, while a "transcriber" model has to keep learning to correctly identify drum hits despite the player's changes. This adversarial back-and-forth forces the transcriber to become more robust, similar in spirit to how a sparring partner sharpens a boxer's skills. The authors released the code as open-source software.

## Concepts
- [[Automatic Music Transcription]]
- [[Machine Learning for Music]]
- [[Open Source Research Tools]]
