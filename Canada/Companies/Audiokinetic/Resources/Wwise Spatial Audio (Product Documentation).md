---
title: Wwise Spatial Audio (Product Documentation)
org: Audiokinetic
org_type: Company
country: Canada
type: product documentation
authors: Audiokinetic
year: 2026
url: https://www.audiokinetic.com/en/wwise/wwise-spatial-audio/
date_added: 2026-08-13
---

Wwise is a piece of software ("middleware") that game developers use to build the sound and music systems inside a video game, instead of writing all of that low-level audio code themselves. This page documents Wwise's Spatial Audio system, which figures out in real time how sound should travel and bounce around a game's 3D level — for example, making a voice sound muffled through a doorway, or letting reverb change automatically as a character walks from a hallway into a large room. It works by having level designers mark up "rooms" and "portals" (doorways/openings) in a game level, and the engine automatically computes realistic-sounding paths for sound between them, rather than a sound designer manually scripting every case.

## Concepts
- [[Game Audio Middleware]]
- [[Room Acoustics]]
