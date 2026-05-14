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
