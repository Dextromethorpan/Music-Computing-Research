---
title: Less Is More - Why Audio on SoundCloud Looks Different
org: SoundCloud
org_type: Company
country: Germany
type: blog post
authors: Joe Reid
year: 2026
url: https://developers.soundcloud.com/blog/less-is-more-why-soundcloud-low-passes-its-aac-transcodings
date_added: 2026-08-09
---

SoundCloud upgraded the AAC encoder (the software that compresses uploaded audio for streaming) it uses to Fraunhofer's libfdk_aac, and this post explains a side effect that looks alarming on a spectrogram (a visual chart of a sound's frequency content over time) but is actually a quality improvement: the new encoder cuts off very high frequencies (above roughly 17 kHz) that almost no adult can reliably hear. Because a compressed audio format only has a limited number of bits to "spend" on describing a sound, deliberately giving up inaudible high frequencies frees up bits to more accurately represent the frequency range humans are most sensitive to (roughly 2-5 kHz), producing audio that measurably sounds better even though it looks "less complete" on a graph. It's a clear, beginner-friendly explanation of how perceptual audio coding trades off what you can't hear against what you can.

## Concepts
- [[Audio Compression and Codecs]]
- [[Sound Perception and Psychoacoustics]]
