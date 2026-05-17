# Constraints

This document captures the constraints that shape the solution space for the Baby Changing Facilities App. These constraints are not obstacles; they are *design boundaries* that help focus the product on what matters: speed, trust, and one‑handed usability in high‑stress moments.

Constraints fall into four categories: technical, product, operational, and UX.

---

## 1. Technical Constraints

### 1.1. PWA, not native

The product must be a **Progressive Web Application**.

- Zero installation friction
- Cross-platform reach
- Offline capability
- Lightweight updates

This rules out native-only features and pushes the architecture toward web-first patterns.

---

### 1.2. No login, no accounts, no authentication

Parents will not create accounts for this use case.

- No personalised profiles
- No saved favourites tied to identity
- No email based verification
- No social login

All contribution flows must work anonymously.

---

### 1.3. Minimal backend

To keep the system simple and low-maintenance.

- No complex server-side logic
- No heavy databases
- No real-time sync requirements

The backend should be a thin layer.

- Storing facility data
- Storing contributions
- Serving static assets

---

### 1.4. Privacy-first, minimal data collection

Parents are sensitive to location and child-related data. 

- No tracking beyond essential analytics
- No personal data storage
- No behavioural profiling
- No unnecessary permissions

Trust is a feature.

---

### 1.5. Offline-tolerant

Parents ofter search in:

- Shopping centres
- Car parks
- Travel hubs
- Rural area

The app must:

- Cache local areas
- Load instantly ecen with poor signal
- Allow contributions offline and sync later

---

## 2. Product Constraints

### 2.1. No real-time occupancy or sensor integrations

The product cannot rely on:

- IoT sensors
- Vendor provided APIs
- Live occupancy feeds

All data is static or user-generated. 

---

### 2.2 No venue-side dashboard or management tools

Venues are not stakeholders in v1.

This Means:

- No venue onboarding
- No venue verification
- No venue-submitted updates

The product is parent-first, not venue first.

---

### 2.3. No moderation queue or complex review system

Moderation must be:

- Lightweight
- Automated where possible
- Human-in-the-loop only when essential

No heavy admin tooling.

---

### 2.4. No map-provider custom integrations

The app must rely on:

- Standard web map libraries
- Public APIs
- No proprietary or paid map integrations in v1

This keeps costs predicatable.

---

## 3. Operational Constraints

### 3.1. Early venue participation is passive

Venues will not actively contribute data.

All early data must come from:

- Parents
- Open data
- Manual seeding

---

### 3.2. Zero dependency on venue cooperation

The product must work even if:

- Venues never engage
- Councils never update datasets
- No official data exists

Crowd-sourcing is the backbone.

---

### 3.3. No field-team operations

There will be:

- No on-time-ground verification
- No photography teams
- No manual audits

The system must scale without human operations.

---

## UX Constraints

### 4.1. One-handed usability

Parents often hold a baby or push a pram.

The app must be operable with:

- One thumb
- Minimal gestures
- No typing where possible

---

### 4.2. Ultra-low cognitive load

Parents are stressed and time‑pressured.

The app must:

- Surface the answer immediately
- Avoid dense text
- Use clear visual cues
- Prioritise photos and structured data

---

### 4.3. No onboarding or tutorials

Parents will not read instructions.
The app must be:

- Self‑explanatory
- Immediately usable
- Zero‑learning‑curve

---

## 5. Constraint Summary

These constraints define the shape of the MVP:

- PWA
- No login
- Minimal backend
- Privacy‑first
- Offline‑friendly
- Crowd‑sourced data
- One‑handed, low‑cognitive‑load UX
- No venue involvement
- No complex moderation

They ensure the product remains lightweight, trustworthy, and optimised for the real‑world context of parents on the move.
