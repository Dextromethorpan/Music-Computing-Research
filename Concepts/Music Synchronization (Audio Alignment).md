---
concept: Music Synchronization (Audio Alignment)
date_first_seen: 2026-08-09
---

Music synchronization (or audio alignment) is the task of automatically lining up two versions of the same piece of music that unfold at different speeds — for example, matching a printed sheet-music score to a live recording that speeds up and slows down, or aligning two different performances of the same song. A classic algorithm for this is Dynamic Time Warping (DTW), which stretches and compresses one sequence to best match another. Modern "differentiable" or "soft" versions of DTW make this technique compatible with training neural networks, so a computer can learn to align music data even when perfect labels aren't available. This matters for score-following systems, digitizing historical recordings against their scores, and any tool that needs to know "where am I in the piece right now."

## Seen in
- [[Stabilizing Soft Dynamic Time Warping for Music Synchronization]] — International Audio Laboratories Erlangen, Germany
- [[Web Applications for Automatic Audio-to-Score Synchronization with Iterative Refinement]] — LIM - Laboratorio di Informatica Musicale (University of Milan), Italy
- [[Exploiting Time-Synced Lyrics and Vocal Features for Music Emotion Detection]] — Musixmatch, Italy
