---
concept: Digital Dither and Quantization Noise
date_first_seen: 2026-08-12
---

When a computer converts a continuous sound wave into digital numbers, or reduces how many bits are used to store each sample, it has to round each value to the nearest number it can represent — this rounding step is called quantization. That rounding introduces a form of distortion that isn't random: it's mathematically tied to the shape of the original signal, which makes it sound harsh, "gritty," or adds strange overtones, especially in quiet passages. "Dither" is a small amount of noise deliberately added to the signal before it's rounded. Counterintuitively, this makes the result sound better: it breaks the mathematical link between the distortion and the original signal, turning it into plain, unstructured noise (a faint hiss) that is far less objectionable to human hearing than the pattern-like distortion it replaces. Dither theory (including how much noise to add, what statistical shape it should have, and "noise shaping" to push the added noise into frequencies we hear less well) underlies nearly all professional digital audio processing, from CD mastering to modern bit-depth reduction in music software.

## Seen in
- [[Quantization and Dither - A Theoretical Survey]] — Audio Research Group (University of Waterloo), Canada
- [[Dither in Digital Audio]] — Audio Research Group (University of Waterloo), Canada
- [[Retrospective - University of Waterloo Audio Research Group]] — Audio Research Group (University of Waterloo), Canada
