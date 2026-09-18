---
title: MusicGen - Simple and Controllable Music Generation
org: Meta AI (FAIR Paris)
org_type: Company
country: France
type: paper
authors: Jade Copet, Felix Kreuk, Itai Gat, Tal Remez, David Kant, Gabriel Synnaeve, Yossi Adi, Alexandre Défossez
year: 2023
url: https://github.com/facebookresearch/audiocraft
date_added: 2026-08-09
---

MusicGen is an AI model that generates original music from a short text description (for example, "upbeat electronic track with a driving bassline") and can optionally also follow a melody you hum or hum-record. It works by first turning music into a compact sequence of discrete tokens (like turning audio into a kind of "vocabulary"), then using a single language-model-style AI — the same basic idea behind text chatbots, but trained on music tokens instead of words — to generate new sequences of those tokens, which are then converted back into audio. It was presented at NeurIPS 2023, one of the top AI research conferences, and released as open-source code and models.

## Concepts
- [[Text-to-Music Generation]]
