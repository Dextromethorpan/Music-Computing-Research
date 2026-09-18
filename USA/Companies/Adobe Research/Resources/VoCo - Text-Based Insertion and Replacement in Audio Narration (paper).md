---
title: "VoCo: Text-Based Insertion and Replacement in Audio Narration (paper)"
org: Adobe Research
org_type: Company
country: USA
type: paper
authors: Zeyu Jin, Gautham Mysore, Stephen DiVerdi, Jingwan Lu, Adam Finkelstein
year: 2017
url: https://research.adobe.com/publication/voco-text-based-insertion-and-replacement-in-audio-narration-2/
date_added: 2026-08-09
---

This is the research paper (published at SIGGRAPH 2017, a major computer graphics conference) behind Adobe's famous "Project VoCo" demo. It describes a system that lets someone edit a spoken recording the same way they'd edit a text document: type a new word, and the tool generates that word in the original speaker's voice and stitches it seamlessly into the existing audio. It works by analyzing about 20 minutes of a person's speech, breaking it into small sound units called phonemes (the basic building blocks of speech sounds, like the "k" in "cat"), and recombining and adjusting those units to match the new sentence. The paper explains the underlying "text-to-speech synthesis" (turning written text into spoken audio) and blending techniques used to make the edits sound natural.

## Concepts
- [[Speech Synthesis]]
- [[Voice Conversion]]
- [[Corpus-Based Concatenative Synthesis]]
