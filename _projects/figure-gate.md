---
layout: page
title: figure-gate
description: CI-gated, pip-packaged pipeline for statistically rigorous, colorblind-accessible figures.
img:
importance: 1
category: software
---

`figure-gate` is a CI-gated, pip-packaged Python pipeline for generating publication-quality statistical diagrams — distributions, posterior updates, and uncertainty intervals — under colorblind-accessible palettes (Okabe-Ito, Viridis).

It was written as the authoring toolchain for the UCLA Bayesian statistics module (see [teaching]({{ site.baseurl }}/teaching/)) and is packaged and licensed for reuse outside the course. It enforces reproducibility by making the figure-generation step part of the build: the same script that produces the diagrams also checks them at the gate.

## Highlights

- Distribution, posterior, and uncertainty-interval diagrams driven from a single declarative spec
- Colorblind-safe palettes enforced by default
- CI-gated output so figures can't silently drift from the code that generates them
- Package and license available for reuse outside its original course
