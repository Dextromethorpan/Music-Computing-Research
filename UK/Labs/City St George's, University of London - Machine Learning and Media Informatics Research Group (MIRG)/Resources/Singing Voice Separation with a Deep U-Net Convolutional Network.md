---
title: Singing Voice Separation with a Deep U-Net Convolutional Network
org: City St George's, University of London - Machine Learning and Media Informatics Research Group (MIRG)
org_type: Lab
country: UK
type: paper
authors: Andreas Jansson, Eric J. Humphrey, Nicola Montecchio, Rachel M. Bittner, Aparna Kumar, Tillman Weyde
year: 2017
url: https://archives.ismir.net/ismir2017/paper/000171.pdf
date_added: 2026-08-12
---

This ISMIR 2017 paper (which won a Best Poster award) shows how to separate a song into its singing voice and its instrumental backing track using a "U-Net" — a neural network design originally invented for spotting details in medical scans. The trick is to treat the problem like image editing: turn the audio into a spectrogram (a picture of sound, showing which frequencies are loud at each moment) and have the network learn to paint a mask over the parts belonging to the voice versus the instruments. The result, at the time, gave state-of-the-art results at pulling clean vocal and instrumental tracks out of a single mixed recording — useful for karaoke tracks, remixing, and sampling.

## Concepts
- [[Music Source Separation]]
- [[Neural Networks for Audio]]
