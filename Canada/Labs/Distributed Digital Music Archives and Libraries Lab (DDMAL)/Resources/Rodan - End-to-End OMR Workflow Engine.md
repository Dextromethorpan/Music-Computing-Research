---
title: Rodan - End-to-End OMR Workflow Engine
org: Distributed Digital Music Archives and Libraries Lab (DDMAL)
org_type: Lab
country: Canada
type: project
authors: DDMAL (Distributed Digital Music Archives and Libraries Lab)
year: 2019
url: https://ddmal.ca/e2e-omr-documentation/
date_added: 2026-08-12
---

Rodan is a web-based "workflow engine" built by DDMAL as the backbone of its optical music recognition (OMR) pipeline. Rather than being one single program, Rodan lets researchers chain together a series of processing steps — for example: clean up a scanned page image, detect the staff lines, identify the note symbols, then export the result as structured music data — into a repeatable pipeline that can run on many manuscripts at once. It's built with standard web technologies (Python, Django, and a task queue called Celery) and is designed so new processing steps can be added as modules. Rodan is the practical, production tool that powers much of DDMAL's large-scale OMR work on digitized chant and early music manuscripts under the SIMSSA project.

## Concepts
- [[Optical Music Recognition]]
- [[Open Source Research Tools]]
