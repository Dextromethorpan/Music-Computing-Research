---
title: JackTrip - Under the Hood of an Engine for Network Audio
org: CCRMA
org_type: Lab
country: USA
type: paper
authors: Juan-Pablo Caceres, Chris Chafe
year: 2009
url: https://ccrma.stanford.edu/groups/soundwire/publications/papers/2009-caceres_chafe-ICMC-jacktrip.pdf
date_added: 2026-08-09
---

This is the founding paper for JackTrip, open-source software built at CCRMA that lets musicians in different physical locations play together over the internet in something close to real time, sending raw, uncompressed audio instead of compressed formats (like the ones used for phone calls or Zoom, which add delay). It explains the software's internal design and how it was built on top of an existing free audio tool (JACK, the Jack Audio Connection Kit) to keep the time delay ("latency") as low as possible. It also describes the origin of the odd name: an engineer's early test connected three ("triple") sites, which got shortened to "trip" and combined with "Jack." Presented at the International Computer Music Conference (ICMC), it is one of the foundational works behind today's field of networked/telematic music performance.

## Concepts
- [[Networked Music Performance]]
- [[Latency]]
