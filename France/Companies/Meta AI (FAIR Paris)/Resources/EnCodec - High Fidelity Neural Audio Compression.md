---
title: EnCodec - High Fidelity Neural Audio Compression
org: Meta AI (FAIR Paris)
org_type: Company
country: France
type: paper
authors: Alexandre Défossez, Jade Copet, Gabriel Synnaeve, Yossi Adi
year: 2022
url: https://github.com/facebookresearch/audiocraft/blob/main/docs/ENCODEC.md
date_added: 2026-08-09
---

EnCodec is an AI-based audio compressor: it squeezes audio files down to a much smaller size while keeping high sound quality, similar in purpose to how MP3 compresses music, but using a neural network trained to find the most efficient way to represent sound rather than following a fixed set of rules. Along the way, it turns the audio into a short sequence of numeric "codes" — this same code representation turns out to be exactly what's needed to let other AI models like MusicGen treat music as a sequence of tokens they can generate, similar to how a language model generates a sequence of words.

## Concepts
- [[Audio Compression and Codecs]]
