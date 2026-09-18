---
title: Multi-Class-Token Transformer for Multitask Self-supervised Music Information Retrieval
org: Deezer
org_type: Company
country: France
type: paper
authors: Yuexuan Kong, Vincent Lostanlen, Romain Hennequin, Mathieu Lagrange, Gabriel Meseguer-Brocal
year: 2025
url: https://arxiv.org/abs/2507.12996
date_added: 2026-08-09
---

Teaching a computer to understand music (what instruments are playing, what key a song is in, where the beat falls, and so on) usually needs a huge number of songs that have been manually labeled by humans, which is slow and expensive. This paper explores "self-supervised learning" — training a model using clues that already exist in the raw audio itself, without needing human labels. The team builds a single model (based on a "Transformer," a type of neural network good at finding patterns and relationships) that can learn two different kinds of musical understanding at once, using two separate internal "summary tokens." One token specializes in recognizing broad categories like instruments, the other in more structured tasks like identifying musical key. The result performs better than models trained on just one type of task, and does so with far fewer parameters (adjustable internal settings) than comparable models like MERT.

## Concepts
- [[Self-Supervised Learning for Audio]]
- [[Music Information Retrieval]]
