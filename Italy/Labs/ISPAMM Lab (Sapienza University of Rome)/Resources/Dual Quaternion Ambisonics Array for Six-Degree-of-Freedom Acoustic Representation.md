---
title: Dual Quaternion Ambisonics Array for Six-Degree-of-Freedom Acoustic Representation
org: ISPAMM Lab (Sapienza University of Rome)
org_type: Lab
country: Italy
type: paper
authors: Eleonora Grassucci, Gioia Mancini, Christian Brignone, Aurelio Uncini, Danilo Comminiello
year: 2023
url: https://arxiv.org/abs/2204.01851
date_added: 2026-08-14
---

This paper is about capturing 3D sound in a way that lets a listener move around a virtual space, not just turn their head. Normal "Ambisonics" recordings (a way of capturing sound from every direction using a special microphone) let you look around a fixed point, but not physically walk through the space — that limitation is why the researchers wanted "six degrees of freedom" (three for rotation, three for movement). They use two Ambisonics microphone recordings together and combine them mathematically using "dual quaternions," a compact 8-number system (an extension of complex numbers) that is good at representing both a position and a rotation at once. The result is a neural network that can estimate where sounds are coming from in a moving, 3D sense, which is useful for VR/AR audio. The authors also released their code publicly.

## Concepts
- [[Head-Related Transfer Functions (HRTF)]]
- [[Auralization]]
