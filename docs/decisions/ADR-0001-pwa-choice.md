# ADR-0001 - Choice to Build as a Progressive Web App (PWA)

## Status
Accepted

## Context
Parents search for baby changing facilities while mobile, time pressured, often one handed, and frequently in environments with poor signal (shopping centres, car parks, travel hubs). Discovery shows the will not install an app, prefer not to create accounts, and need instant access in moments of stress. 
Technical constraints emphasise minimal backend, offline tolerance, privacy first operation, and cross platform reach.
No competitor provides a fast, lightweight, universally accessible experience. Most rely on native apps or heavy web experiences.

## Decision
The product will be delivered as a PWA rather than a native mobile application. 

## Rationale

### A PWA aligns directly with user behaviours and constraints:
  - **Zero friction** - no installation, no app store dependency, immediate access when needed.
  - **Cross platform reach** - works on any device parents already have.
  - **Offline capability** - caching enables use in low signal environments.
  - **Lightweight updates** - no app store release cycles; fixes and improvements ship instantly.
  - **Minimal backend** - avoids account creation, permissions, and platform level data collection.

### Alternatives considered:
  - **Native mobile app** - rejected due to installation friction, slower update cycles, higher development cost, and reduced accessiblity for casual or urgent use. 
  - **Responsive website without PWA features** - rejected due to lack of offline capability, slower preceived performance, and weaker "app-like" ergonomics.

## Consequences

### Positive
  - Faster access in real world parent scenarios.
  - Lower operational and hosting costs.
  - Simpler architecture and maintenance.
  - Offline first UX becomes feasible.
  - Broader reach witrhout platform constraints.

### Negative
  - Limited access to native device APIs (eg. advanced camera features)
  - Some OS-specific behaviours (eg. iOS PWA quirks) require workarounds.
  - No app store presence, reducing one potential discovery channel.

### Neutral / Enabling
  - Forces a web first design discipline.
  - Shapes subsequent decisions: data model, offline strategy, contribution flow, and map provider choice.

## Links
  - (Related decisions)
  - (Relevant discovery documents)
  - (Architecture artefacts)
  - (External references (if applicable))
