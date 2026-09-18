---
title: A Fourier Explanation of AI-music Artifacts
org: Deezer
org_type: Company
country: France
type: paper
authors: Darius Afchar, Gabriel Meseguer-Brocal, Kamil Akesbi, Romain Hennequin
year: 2025
url: https://arxiv.org/abs/2506.19108
date_added: 2026-08-09
---

With AI tools like Suno and Udio now able to generate entire songs, this ISMIR 2025 paper looks at how to tell whether a piece of music was made by a person or by an AI model. The researchers found that a specific technical step used inside most AI music generators (an "upsampling" or "deconvolution" step, which is how the model builds up a full audio waveform from a lower-resolution internal representation) leaves behind tiny, repeating spike patterns when you look at the sound's frequency content — similar to a faint, regular pattern you might see in a badly printed image. Because this pattern comes from the model's basic design rather than from what music it was trained on, it shows up reliably across different AI music generators. The team used this insight to build a simple, easy-to-understand detector that spots AI-generated music with over 99% accuracy in several tests, performing as well as much more complicated deep-learning detectors.

## Concepts
- [[AI-Generated Music Detection]]
- [[Music Information Retrieval]]
