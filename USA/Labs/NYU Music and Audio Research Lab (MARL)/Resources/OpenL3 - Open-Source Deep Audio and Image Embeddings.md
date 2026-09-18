---
title: OpenL3 - Open-Source Deep Audio and Image Embeddings
org: NYU Music and Audio Research Lab (MARL)
org_type: Lab
country: USA
type: project
authors: Aurora Cramer, Ho-Hsiang Wu, Justin Salamon, Juan Pablo Bello
year: 2019
url: https://github.com/marl/openl3
date_added: 2026-08-10
---

OpenL3 turns a short clip of audio (or a video frame) into a compact list of numbers called an "embedding" — a numeric fingerprint that captures what the sound is about, without needing labels for the specific task at hand. This is useful because instead of training a brand-new AI model from scratch for every audio task, developers can plug in these ready-made embeddings as a shortcut. The model was trained using a "Look, Listen, and Learn" approach, where the AI learns by matching video with its corresponding audio rather than from hand-labeled data (a technique called self-supervised learning). It reportedly outperforms earlier general-purpose sound-embedding tools like VGGish and SoundNet on several recognition tasks.

## Concepts
- [[Audio Embeddings]]
- [[Self-Supervised Learning for Audio]]
- [[Sound Event Detection]]
