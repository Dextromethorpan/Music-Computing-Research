---
title: Ableton Link - Cross-Application Tempo Synchronization
org: Ableton
org_type: Company
country: Germany
type: project
authors: Ableton (engineering team)
year: 2016
url: https://github.com/Ableton/link
date_added: 2026-08-09
---

Ableton Link is an open-source technology (with an accompanying technical guide, "Ableton Link Guidelines") that keeps the musical tempo and beat of multiple apps and devices in sync over a local wireless network, without needing MIDI cables or a single "master" clock. Any participant can start, stop, or change the tempo, and the others follow automatically, which solves a longstanding practical problem in electronic live performance: getting several laptops, tablets, or synth apps to play in time together. Under the hood it works by continuously estimating the relationship between each device's internal clock and a shared notion of "beat time," correcting for network jitter and audio-output latency. Link is built into Ableton Live and has been adopted by dozens of third-party apps (synth apps, DJ software, looper apps), making it a de facto standard for tempo-synced jamming. The project is maintained publicly on GitHub with full source code and a formal test plan for other developers who want to add Link support to their own software.

## Concepts
- [[Human-Computer Interaction in Music]]
- [[New Interfaces for Musical Expression (NIME)]]
- [[Open Source Research Tools]]
