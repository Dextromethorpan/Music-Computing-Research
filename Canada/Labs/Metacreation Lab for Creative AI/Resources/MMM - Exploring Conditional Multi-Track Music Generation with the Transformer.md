---
title: MMM - Exploring Conditional Multi-Track Music Generation with the Transformer
org: Metacreation Lab for Creative AI
org_type: Lab
country: Canada
type: paper
authors: Jeff Ens, Philippe Pasquier
year: 2020
url: https://arxiv.org/abs/2008.06048
date_added: 2026-08-12
---

MMM (Multi-Track Music Machine) is the Metacreation Lab's flagship generative music system. "Multi-track" means a piece made of several instrument parts playing together (drums, bass, piano, etc.) — a "MIDI file" is just a digital score that stores which notes play when, without any actual audio. Instead of interleaving all the instruments into one long mixed-up sequence, MMM lays out each track as its own ordered sequence of musical events and then strings the tracks together, letting a Transformer (the same type of AI architecture behind large language models) learn long-range musical relationships between them. This lets a user regenerate just one track, or just one section (a "bar"), while keeping everything else fixed — a technique called inpainting, borrowed from image-editing AI. The result is a tool that composers can steer: pick the instruments, ask the AI to fill in a bass line under an existing melody, or generate a whole arrangement from scratch. This paper is the technical foundation behind Calliope and MMM4Live.

## Concepts
- [[AI Music Generation]]
- [[Algorithmic Composition]]
