---
title: Simultaneous Music Separation and Generation Using Multi-Track Latent Diffusion Models
org: UC San Diego CREATE and CRCA
org_type: Lab
country: USA
type: paper
authors: Tornike Karchkhadze, Mohammad Rasool Izadi, Shlomo Dubnov
year: 2025
url: https://arxiv.org/abs/2409.12346
date_added: 2026-08-10
---

This ICASSP 2025 paper (from Shlomo Dubnov's group) presents an AI model that can do two related jobs with one system: split a song into its separate instrument tracks (source separation), and also generate new instrument tracks that fit alongside existing ones (music generation). It works using a "latent diffusion model" — a type of AI that learns to gradually turn random noise into structured data, here applied to a compressed representation of multi-track audio — trained to understand how different instrument tracks in a song relate to each other musically. Because the model learns the shared relationship between tracks, it can be asked either to isolate one instrument from a mix or to compose a plausible new part (like a bassline) to accompany given tracks. It was trained and tested on Slakh2100, a dataset of synthesized multi-track songs.

## Concepts
- [[Diffusion Models for Audio]]
- [[Music Source Separation]]
- [[AI Music Generation]]
