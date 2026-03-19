---
title: "Against Best Practices"
description: "Why blindly following 'best practices' can be worse than thinking for yourself, and how to tell the difference."
date: 2026-02-15
cover_color: "#dce8d8"
tags: [engineering, opinion]
---

"Best practice" is one of the most dangerous phrases in software engineering. Not because the advice is always wrong — but because it discourages the most important engineering skill: thinking about your specific context.

## The context problem

Every best practice was born in a specific context. Microservices emerged from companies with hundreds of engineers who needed to deploy independently. Test-driven development was refined in environments where requirements were clear upfront. "Always use a queue" makes sense when you actually need asynchronous processing.

Strip away the context, and you get cargo cult engineering — teams adopting patterns because they're "best practices" without understanding the problems those patterns were designed to solve.

## Examples I've seen go wrong

**Microservices for a three-person team.** The operational overhead of managing a dozen services consumed more time than the entire feature development. A monolith would have shipped in a quarter of the time.

**100% test coverage as a mandate.** The team spent more time writing tests for trivial getters and setters than building features. Meanwhile, the complex business logic — the stuff that actually broke — had superficial tests because the developers were exhausted from testing boilerplate.

**"Never use inheritance."** A team so allergic to inheritance that they built a labyrinthine composition system that was harder to understand than any class hierarchy could have been.

## A better frame

Instead of "best practices," I prefer "default choices" — things you do unless you have a reason not to. The distinction matters:

- A best practice is a rule. Breaking it feels like a violation.
- A default choice is a starting point. Deviating from it is just engineering.

When someone tells you something is a best practice, ask: "Best for whom? In what context? What are the trade-offs?" If they can't answer, it's not a practice — it's a superstition.
