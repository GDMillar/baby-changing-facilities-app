# Competitor Analysis

This document reviews the existing solutions parents use, directly or indirectly, to find and assess baby‑changing facilities. The goal is not to critique apps, but to extract patterns, gaps, and design signals that inform the product direction.

Competitors fall into two categories:

- Direct: apps explicitly designed for baby‑changing or family facilities
- Indirect: general‑purpose platforms parents repurpose for this need

---

## 1. Direct Competitors

### BabyChange (NCT)

#### Pattern

Directory-style list of facilities with basic details

#### Strengths

- Recognised brand (NCT)
- Simple interface
- Some community-sourced data

#### Weaknesses

- Sparse coverage
- Outdated entries
- No photos
- No quality indicators beyond text reviews
- Slow update cadence

#### Signals

Parents want this to existm but the execution hasn't kept pace with expectations.

---

### SitorSquat (by Charmin)

#### Pattern

Toilet-finder app with changing as a tag.

#### Strengths

- Large dataset in some regions
- Simple green/red rating system
- Map-first UI

#### Weaknesses

- US-centric
- Inconsistent tagging
- Low trust in data accuracy
- Cluttered UI

#### Signals

Binary ratings work. Over-complexity does not. 

---

### Baby Facilities Apps (various small UK apps)

#### Pattern

Hyper-local, volunteer-maintained directories.

#### Strengths

- Passion-driven
- Good local knowledge in pockets

#### Weaknesses

- Very limited coverage
- No sustained maintenance
- No UX consistency
- No critical mass

#### Signals

The problem is real, but no-one has achieved scale or trust.

---

## 2. Indirect Competitors

### Google Maps (broadly captures other major mapping solutions like Apple and Bing)

#### Pattern

General-purpose location search with reviews.

#### Strengths

- Ubiquitous
- Fast
- Familiar
- Rich navigation

#### Weaknesses

- Baby-changing is not a first-class attribute
- Reviews rarely mention facilities
- Tagging is inconsistent
- No structured data

#### Signals

Parents default here because it's the only thing they trust, even though it's not built for this use case. 

### TripAdvisor / Yelp

#### Pattern

Venue-level reviews.

#### Strengths

- Large review base
- Photos
- Some mention of family-friendliness

#### Weaknesses

- Not facility specific
- Hard to filter
- Too much noise

#### Signals

Parents want *facility-level* insight, not venue-level sentiment. 

### Local Council Websites

#### Pattern:

Static lists of public amenities

#### Strengths

- Official source
- Sometimes includes acessibility info

#### Weaknesses:

- Outdated
- Incomplete
- Hard to find
- Not mobile-friendly

#### Signals

Official data is unreliable; user generated data is essential.

### Parenting Groups (Facebook, WhatsApp, Forums, etc)

#### Pattern

Word of mouth recommnedations

#### Strengths

- High trust
- Real, recent experiences
- Hyper-local knowledge

#### Weaknesses

- Not searchable
- Not structured
- Not persistent
- Not accessible to newcomers

#### Signals

Parents trust other parents more than institutions or apps.

---

## 3. Cross Competitor Pattern Summary

Across all competitors, several patterns emerge:

#### What works

- **Simplicity** (binary ratings, map-first UI)
- **Photos** (high trust, low cognitive load)
- **Recency** (parents care about "last updated")
- **Crowd-sourcing** (the only way to keep data fresh)

#### What consistently fails

- **Long reviews** (too slow to parse in stressful moments)
- **Over-complex filters** (parents don't have the attention)
- **Venue-level data** (doesn't answer the real question: "Is the facility good?")
- **Static datasets** (decay quickly)

#### What no-one has solved

- A trusted, unified directory
- Structured, facility-level data
- Lightweight contribution flows
- Accessibility metadata
- Offline friendly UX
- A one-handed, time-pressured design

---

## 4. Imprications for Our Product

From the competitor landscape, several design principles emerge:

- **Trust is the differentiator** - recency, photos, and parent‑level insights matter more than polish.
- **Speed beats completeness** - parents need a fast, confident answer, not a long list.
- **Crowd‑sourcing is mandatory** - no official dataset is sufficient.
- **Facility‑level granularity is the gap** - this is where we can win.
- **One‑handed UX is a competitive advantage** - no one optimises for this.
- **Offline capability is a differentiator** - especially for travel and poor‑signal areas.

These insights feed directly into constraints, opportunities, and the decision log.
