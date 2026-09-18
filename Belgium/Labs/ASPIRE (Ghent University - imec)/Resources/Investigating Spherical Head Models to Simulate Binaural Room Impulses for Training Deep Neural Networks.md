---
title: Investigating Spherical Head Models to Simulate Binaural Room Impulses for Training Deep Neural Networks
org: ASPIRE (Ghent University - imec)
org_type: Lab
country: Belgium
type: paper
authors: Jasper Maes, Siyuan Song, Stijn Kindt, Pieter-Jan Maes, Bruno Masiero, Nilesh Madhu
year: 2023
url: http://hdl.handle.net/1854/LU-01H3VM4M8P370WBXBWXDTF0DR3
date_added: 2026-08-13
---

To train an AI system that locates sounds using two "ears" (binaural hearing, like a hearing aid does), researchers need huge amounts of example recordings of sound arriving at a simulated head from many different room shapes and directions. Recording all of that with a real human or a real dummy head would be far too slow and expensive. This paper tests whether a much simpler, cheaper approximation — modeling the head as a plain sphere instead of a realistic head-and-ear shape — is good enough to generate the training data these neural networks need. It's a practical study into how much anatomical detail actually matters when the end goal is training a machine-learning model rather than fooling a human ear.

## Concepts
- [[Head-Related Transfer Function (HRTF)]]
- [[Room Acoustics]]
