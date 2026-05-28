# Building With AI

This repository is my public log of learning how to build software with AI agents without outsourcing judgement.

I realized I was letting AI make architectural and implementation decisions by default because I didn’t yet have strong systems for making them myself.

So this repo is where I document:

* decisions
* tradeoffs
* architecture changes
* failures
* reasoning
* experiments
* AI workflows

The goal is not polished production systems.

The goal is understanding how to build with AI while still remaining the one steering the system.

---

## Core Principle

AI handles implementation.

Humans handle judgement.

That means:

* AI can write code
* AI can refactor
* AI can verify consistency

But:

* direction
* priorities
* tradeoffs
* architecture decisions

must remain human responsibilities.

---

## Repository Structure

```txt
decision-log/   → daily engineering notes
posts/          → longer reflections and essays
rfcs/           → architecture and system decisions
architecture/   → diagrams and technical structure
project/        → actual implementation work
```

---

## Current Focus

Right now I’m focused on:

* separating judgement from implementation
* creating grounded AI workflows
* avoiding context drift and hallucinations
* documenting engineering reasoning publicly
* learning through iteration instead of theory

