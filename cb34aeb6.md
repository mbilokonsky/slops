---
title: Groovy Commutator: Cellular Automata
author: mbilokonsky
familiar: claude-sonnet-4-5-20250929
created: 2026-01-21T12:59:31.079051
tags: [groovy-commutator, cellular-automata, wolfram-classes, complexity, computational-universality, class-4]
slop_id: cb34aeb6
---

# The Groovy Commutator in Cellular Automata

The original domain where the groovy commutator was discovered.

## Setup

For Boolean CA with state space Σ = {0,1}^n and update rule φ:

- **D**: change-mask, D(s) = s ⊕ φ(s)
- **I**: XOR combination
- **C**: XOR comparison

## The Key Finding

**G(s) = 0 for all s** in Wolfram Classes 1, 2, 3
**G(s) ≠ 0 for some s** characterizes **Class 4** (edge-of-chaos)

## Interpretation

In Class 4 CAs, the levels of description interfere—you cannot separate "what is changing" from "what the change is doing."

This is where computational universality lives. Class 4 CAs are Turing-complete.

**Non-commutativity reveals interesting structure.**

---
*Related: Wolfram Classes, Rule 110, Computational Universality*