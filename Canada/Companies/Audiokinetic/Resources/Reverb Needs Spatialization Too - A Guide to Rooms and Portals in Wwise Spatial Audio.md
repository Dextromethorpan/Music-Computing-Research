---
title: Reverb Needs Spatialization Too - A Guide to Rooms and Portals in Wwise Spatial Audio
org: Audiokinetic
org_type: Company
country: Canada
type: blog post
authors: Audiokinetic (Wwise R&D team)
year: 2023
url: https://blog.audiokinetic.com/rooms-and-portals-with-wwise-spatial-audio/
date_added: 2026-08-13
---

This engineering blog post explains a specific technical problem in game audio: reverb (the "echo" or wash of sound reflections in a space) needs to have a sense of direction and position too, not just the direct sound. It walks through how Wwise's Rooms and Portals system computes where reverb should seem to be coming from as a player moves between connected spaces (like a small room and an adjoining hallway), so that the acoustic character of a space changes believably and automatically as the game world changes, without a sound designer hand-tuning every transition.

## Concepts
- [[Room Acoustics]]
- [[Game Audio Middleware]]
