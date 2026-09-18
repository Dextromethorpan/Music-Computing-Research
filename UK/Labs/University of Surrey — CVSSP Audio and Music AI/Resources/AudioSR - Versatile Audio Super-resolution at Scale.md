---
title: AudioSR - Versatile Audio Super-resolution at Scale
org: University of Surrey — CVSSP Audio and Music AI
org_type: Lab
country: UK
type: paper
authors: Haohe Liu, Ke Chen, Qiao Tian, Wenwu Wang, Mark D. Plumbley
year: 2023
url: https://arxiv.org/abs/2309.07314
date_added: 2026-08-12
---

AudioSR is a tool that takes low-quality or narrow-bandwidth audio (think of a muffled old recording, or audio that's missing its higher frequencies) and reconstructs a full, high-quality 48kHz version — a task the authors call "audio super-resolution," borrowing the term from image upscaling. It works on any kind of audio: speech, music, or sound effects, which is unusual since most earlier tools were built for just one type. It also functions as a "plug-and-play" quality booster that can be attached after other AI audio generators (including AudioLDM and MusicGen) to sharpen their output. Under the hood it uses a diffusion model, the same generate-by-refining-noise approach used in image generators like Stable Diffusion, adapted for sound.

## Concepts
- [[Diffusion Models for Audio]]
- [[Audio Restoration and Digital Preservation]]
