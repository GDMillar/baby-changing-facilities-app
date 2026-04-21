# Baby Changing Facilities App
![Status: Early Stage](https://img.shields.io/badge/status-early--stage-blue)

A lightweight, parent-first product for discovering and reviewing baby-changing facilities in public spaces.

## Overview
This repository contains the product documentation, architecture, and early implementation work for a *progressive web application* (PWA) designed to help parents and carers quickly find, assess, and review baby-changing facilities. The product is optimised for **one-handed**, **time-pressured** use, with **no login**, **minimal friction**, and **fast access** to trustworthy, parent-generated data.

The goal is to deliver a **simple**, **reliable**, **emotionally calming** experience for parents navigating high-stress moments in public environments.

## Problem
Parents often struggle to locate clean, accessible, and functional baby-changing facilities when out in public. Existing information is fragmented, outdated, or unavailable at the moment of need. This creates unnecessary stress during an already time-sensitive situation. 

## Solution
A fast, frictionless PWA that enables parents to:

- Find nearby baby-changing facilities
- View cleanliness, accessibility, and usability ratings
- Read recent parent reviews
- Submit quick, anonymous reviews in under 20 seconds
- Add missing facilities to improve coverage
- Access facility pages instantly via QR codes placed in venues

The product is intentionally lightweight, anonymous, and operationally simple. It is designed to scale through **community contribution**, not venue partnerships.

## Repository Structure

```
/docs
   /prd          → Product Requirements Documents (MVP, v1, v2)
   /architecture → System diagrams, data flow, and technical decisions
   /raido        → Risks, assumptions, issues, dependencies, opportunities
   /research     → User insights, behavioural notes, competitive scans
/src
   /pwa          → Front‑end PWA implementation (future)
   /functions    → Azure Functions backend (future)
README.md        → You are here
```

This structure reflects a **product-level boundary**, not a feature-level one. The repo will evolve as the product moves from MVP→V1→V2.

## MVP Summary
The MVP focuses on delivering the smallest coherent product that solves the core parent need:

- **Find** a facility
- **Assess** its suitability
- **Review** it with minimal effort

No accounts, no venue dashboards, no moderation queues, no native apps, and no operational overhead.

Full MVP PRD will be available in `/docs/prd/MVP.md`

## Technical Approach

- **PWA** hosted on Azure Static Web Apps
- **Serverless backend** using Azure Functions
- **Cosmos DB** or **Table Storage** for facility and review data
- **Blob Storage** for optional photos
- **Offline tolerance** for cached data and queued submissions

The architecture prioritises speed, simplicity, and low cost.

## Why This Repo Exists
This repo forms part of a broader product portfolio, demonstrating:

- Product sense
- Behavioural insight
- MVP discipline
- Technical fluency
- System-level thinking
- Clear, structured communication

It is designed to be read by engineers and product peers.

## Future Work (intended)
- v1.0: Improved facility taxonomy, richer review model, map enhancements
- v2.0: Venue verification, accessibility insights, trust mechanisms
- Long-term: Regional scaling, public-good partnerships, anonymised data insights

## Status
Early documentation and product definition. Implementation will follow once the MVP PRD and architecture are finalised.
