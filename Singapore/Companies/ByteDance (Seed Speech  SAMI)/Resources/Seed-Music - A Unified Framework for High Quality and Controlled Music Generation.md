---
title: Seed-Music - A Unified Framework for High Quality and Controlled Music Generation
org: ByteDance (Seed Speech / SAMI)
org_type: Company
country: Singapore
type: paper
authors: Ye Bai, Haonan Chen, Jitong Chen, Zhuo Chen, Yi Deng, Xiaohong Dong, Lamtharn Hantrakul, Weituo Hao, Qingqing Huang, and 27 others (ByteDance Seed Team)
year: 2024
url: https://arxiv.org/abs/2409.09214
date_added: 2026-08-09
---

Seed-Music is a technical report from ByteDance describing a set of AI systems that generate full songs, including vocals, from a variety of inputs. A user can steer the output with a text description of the desired style ("upbeat pop with female vocals"), a reference audio clip, a musical score, or even a recording of their own voice. The system combines two different AI approaches: "auto-regressive language modeling" (predicting the next piece of audio step by step, the way text-generating AI predicts the next word) and "diffusion" (a technique that starts from random noise and gradually refines it into a finished result). Beyond generating songs from scratch, Seed-Music also supports editing already-generated tracks — for example, changing the lyrics or the vocal melody without regenerating the whole song. It powers music features inside ByteDance's Doubao chatbot product. The paper is a ByteDance Seed technical report rather than a peer-reviewed conference paper, but it documents real, deployed research.

## Concepts
- [[Text-to-Music Generation]]
- [[Diffusion Models for Audio]]
- [[AI Music Generation]]
