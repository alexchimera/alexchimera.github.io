---
title: "Why Every Programmer Should Learn a Hardware Language"
description: "Software abstractions are powerful, but understanding what happens beneath them changes how you think about code forever."
date: 2026-03-15
cover_color: "#d8e2e8"
tags: [programming, hardware]
---

I spent six months writing Verilog last year. Not because I needed to — I build web apps for a living — but because I had a nagging suspicion that I was missing something fundamental.

I was right.

## The abstraction trap

Modern software development is layers of abstraction stacked impossibly high. You write Python that calls C that talks to an OS that schedules instructions on silicon you've never thought about. This is good — it's what makes us productive. But it's also a kind of blindness.

When I started describing circuits in Verilog, something shifted. Suddenly, "everything runs in parallel" wasn't an abstract concept. It was the default. Sequential execution — the thing I'd taken for granted my entire career — was the special case, the thing you had to explicitly construct.

## What changed in my thinking

After the Verilog detour, I came back to my day job and noticed I was reasoning differently:

**About concurrency.** I stopped thinking of threads as scary. When your mental model starts with "everything happens at once," adding synchronization feels natural rather than frightening.

**About memory.** I'd always known that cache misses were expensive. Now I could visualize why — the physical distance signals travel, the clock cycles spent waiting. I started writing cache-friendlier code almost unconsciously.

**About trade-offs.** Hardware forces you to think about area, power, and timing simultaneously. Software usually lets you ignore two of those. Coming back to software, I found myself making more deliberate choices about where to spend computational resources.

## You don't need to go deep

I'm not suggesting everyone write a CPU from scratch (though it's a great exercise). Even a weekend project — blinking an LED with an FPGA, building a simple ALU — gives you enough exposure to shift your mental model.

The goal isn't to become a hardware engineer. It's to understand the machine you're actually programming.
