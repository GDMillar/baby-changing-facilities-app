# Research

This folder captures the discovery work underpinning the Baby Changing Facilities App. It documents the problem space, the landscape of existing solutions, user behaviours, and the constraints that shape viable product directions. The goal is to make the reasoning traceable: how we understand the world, what evidence we’re using, and how that informs the product decisions recorded elsewhere in the repo.

---

## Purpose

- Build a clear, evidence‑based understanding of the problem
- Surface constraints early so they shape design and architecture
- Identify opportunities that meaningfully improve the experience for parents and carers
- Provide a durable reference for future contributors and decision‑makers

---

## What this folder contains

- **Landscape analysis** - the current state of public baby‑changing facilities, data availability, and reporting mechanisms
- **Competitor review** - patterns, gaps, and differentiators across existing apps and directories
- **User behaviours** - how parents currently discover, evaluate, and share information about facilities
- **Constraints** - technical, regulatory, data‑quality, and operational constraints that shape the solution space
- **Opportunities** — where the product can create leverage, reduce friction, or deliver outsized value

---

## Structure

```
/docs/research/
│ README.md
│
├── discovery/
│   ├── 01-landscape.md
│   ├── 02-competitors.md
│   ├── 03-user-behaviours.md
│   ├── 04-constraints.md
│   └── 05-opportunities.md
│
└── notes/
    └── scratchpad.md   # optional: raw notes, links, early thinking
```

---

## How this connects to the rest of the repo

Discovery artefacts here directly inform:

- **PRD** - problem framing, user needs, and success criteria
- **Architecture** - data model, API choices, offline strategy
- **Decision log** - each ADR should reference the evidence captured here
- **MVP definition** - what’s essential vs. what can wait

---

## Working Principles

- Capture evidence early, even if rough
- Bias toward clarity over completeness
- Keep raw notes separate from structured artefacts
- Link out to decisions once they’re made
