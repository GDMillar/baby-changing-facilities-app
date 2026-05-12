# User Behaviours

This document captures how parents and carers actually behave when trying to find and use baby‑changing facilities. It focuses on real‑world context: stress, time pressure, physical constraints, and the cognitive shortcuts people rely on. These behaviours shape the product’s UX, data model, and contribution flows.

## 1. Context of Use

Parents typically search for a facility when:

- They are **already out** (shops, parks, high streets, travel hubs)
- They are **carrying a baby**, a bag, or pushing a pram
- They are **time‑pressured** (crying baby, feeding schedule, nap window)
- They have **limited attention** (noise, weather, crowds, siblings)
- They are often **one‑handed** (holding the baby or managing a pram)

This is not a calm, exploratory scenario. It’s a “solve this now” scenario.

**Implication:**
The product must be fast, scannable, and operable with minimal interaction.

---

## 2. How Parents Currently Search

Parents use a mix of digital and physical cues:

- **Google Maps** as the default, even though it’s not designed for this
- **Walking around** hoping to find signage
- **Asking staff** in cafés, shops, or venues
- **Local parenting groups** for trusted recommendations
- **Mental maps** built over time (“I know John Lewis has good facilities”)

Search behaviour is pragmatic, not systematic.

**Implication:**
The product must reduce the need for trial‑and‑error and provide confidence quickly.

---

## 3. What Parents Look For

Parents care about a small set of high-calue attributes:

- **Cleanliness**
- **Space** (can I fit a pram?)
- **Safety** (stable table, working straps)
- **Accessibility** (step‑free, wide doors)
- **Amenities** (bin, sink, feeding area)
- **Recency** (is this still true?)
- **Photos** (trust anchor)

They do *not* want long reviews or dense text.

**Implication:**
The data model should prioritise structured, scannable attributes and photos.

---

## 4. Behaviour Under Stress

When stressed, parents:

- Avoid typing
- Avoid long lists
- Prefer **binary cues** (“good / avoid”)
- Rely on **visuals** over text
- Make decisions quickly
- Trust **recent parent‑generated content** over official sources

This is classic “fast‑thinking” behaviour (System 1, Kahneman/Tversky).

**Implication:**
The UI should minimise cognitive load and surface the most important signals first.

---

## 5. Contribution Behaviours

Parents are willing to contribute if:

- It’s fast
- It’s one‑handed
- It doesn’t require login
- It feels helpful to other parents
- It’s lightweight (photo + quick rating)

They are _not_ willing to:

- Fill long forms
- Write essays
- Create accounts
- Moderate others’ content

Contribution is opportunistic, not planned.

**Implication:**
The contribution flow must be frictionless and designed for micro‑moments.

---

## 6. Trust Behaviours

Parents trust:

- Photos
- Recent updates
- Other parents
- Simple ratings
- Consistency across entries

Parents distrust:

- Outdated data
- Overly polished marketing content
- Sparse entries
- Anonymous or generic reviews

Trust is earned through transparency and recency.

**Implication:**
Every entry should show “last updated”, contributor signals, and photos where possible.

---

## 7. Behavioural Constraints

These behaviours impose constraints on the product:

- Must work **one‑handed**
- Must load **fast on mobile data**
- Must work **offline or with poor signal**
- Must avoid **typing-heavy flows**
- Must avoid **complex navigation**
- Must provide **clear, immediate answers**
- Must support **quick contributions**

These constraints should shape both the UX and the technical architecture.

---

## 8. Behavioural Opportunities

Understanding these behaviours reveals opportunities:

- A **map‑first, photo‑first** interface
- A **binary or 3‑point rating system**
- **Structured attributes** instead of long reviews
- **One‑tap contributions**
- **Offline caching** of local areas
- **Recency indicators** to build trust
- **Accessibility metadata** as a differentiator

These opportunities feed directly into the constraints and opportunities documents.
