---
layout: page
title: Interactive statistics teaching site
description: Interactive distribution explorers with live in-browser Python.
img:
importance: 2
category: software
---

An interactive statistics teaching site ([naren-p.com](https://www.naren-p.com/)) built with Astro, TypeScript, and Rust.

The site turns textbook statistics into manipulable objects: distribution explorers driven by D3 with live, editable Python running in the browser through a Pyodide web worker, plus free-text explanation grading.

## Highlights

- Distribution explorers driven by D3, with live editable Python in the browser via a Pyodide web worker
- Rust corpus-preparation tool behind an in-browser grader that scores free-text explanations against on-device WASM embeddings
- Three-stage CI gate on every push: type checks, lint, Vitest units, Playwright and axe-core suites, supply-chain auditing
