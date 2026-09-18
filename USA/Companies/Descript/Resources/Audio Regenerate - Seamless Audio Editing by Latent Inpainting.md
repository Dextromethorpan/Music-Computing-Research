---
title: Audio Regenerate - Seamless Audio Editing by Latent Inpainting
org: Descript
org_type: Company
country: USA
type: project
authors: Alejandro Luebs, Mithilesh Vaidya, Ishaan Kumar, Stephen W. Bailey, Sumukh Badam, Matthew Bendel, Jose Sotelo, Xingzhe He
year: 2026
url: https://descriptinc.github.io/uvm-v2/
date_added: 2026-08-10
---

Audio Regenerate is Descript's current research project behind the "type-to-edit" feature in its app: you edit the text transcript of a recording, and the system regenerates only the changed words in the original speaker's voice, tone, and room acoustics, so the edit is inaudible. It works in two stages — a neural audio codec that compresses speech into a compact set of numbers, and a "flow-matching" generator that fills in the missing/changed span conditioned on the surrounding audio and the new text. Unlike Overdub's original voice-cloning approach, this system is "zero-shot," meaning it does not need a lengthy voice-training step — it infers the speaker's voice from just 5-6 seconds of surrounding audio. This is the direct technical descendant of Lyrebird's original voice-cloning research, now focused on seamless editing rather than open-ended text-to-speech.

## Concepts
- [[Audio Inpainting]]
- [[Speech Synthesis]]
