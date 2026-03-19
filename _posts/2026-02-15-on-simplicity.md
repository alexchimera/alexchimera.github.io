---
title: "On Simplicity"
description: "Why simple solutions are harder to build than complex ones, and how to cultivate the discipline of simplicity."
date: 2026-02-15
cover_color: "#e0dde8"
tags: [engineering, philosophy]
---

"I would have written a shorter letter, but I did not have the time." This line, often attributed to Pascal, captures something essential about simplicity: it's harder than complexity.

## Simplicity is not the absence of features

A common misconception is that simple means fewer features. But simplicity is really about coherence — every element serving a clear purpose, nothing extraneous, nothing missing.

A chef's knife is simple. It has one blade, one handle. But the geometry of that blade, the balance of the handle, the quality of the steel — these represent thousands of decisions refined over centuries.

## The discipline required

Building simple software requires saying no constantly. Every feature request that doesn't serve the core purpose gets rejected. Every clever abstraction that adds cognitive load gets flattened. Every configuration option that could have a sensible default gets removed.

This is uncomfortable. It means disappointing people. It means resisting the urge to demonstrate technical sophistication. It means trusting that less really is more.

## Simplicity in practice

Some principles I try to follow:

- **Start with the output** — what does the user actually need to see or do?
- **Resist premature abstraction** — duplication is cheaper than the wrong abstraction
- **Optimize for reading** — code is read far more often than it's written
- **Delete aggressively** — the best code is no code at all
