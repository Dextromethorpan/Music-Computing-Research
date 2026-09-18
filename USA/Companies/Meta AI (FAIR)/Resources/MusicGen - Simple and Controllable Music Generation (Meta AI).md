---
title: MusicGen - Simple and Controllable Music Generation (Meta AI)
org: Meta AI (FAIR)
org_type: Company
country: USA
type: paper
authors: Jade Copet, Felix Kreuk, Itai Gat, Tal Remez, David Kant, Gabriel Synnaeve, Yossi Adi, Alexandre Défossez
year: 2023
url: https://arxiv.org/abs/2306.05284
date_added: 2026-08-10
---

MusicGen is Meta AI's text-to-music model: you type a description (and optionally hum or provide a reference melody) and it generates a matching piece of music. Unlike some earlier approaches that needed several separate models chained together, MusicGen uses a single "autoregressive" model (one that predicts the next chunk of sound based on everything generated so far) operating over compressed audio tokens produced by the EnCodec codec. This simpler, single-stage design made it both easier to train and faster to run than prior multi-stage systems, while still producing high-quality, controllable music. MusicGen is the flagship model of Meta's open-source AudioCraft framework.

## Concepts
- [[Text-to-Music Generation]]
- [[AI Music Generation]]
- [[Audio Compression and Codecs]]
