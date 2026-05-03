# Product Requirements Document | Baby Changing Facilities App | Minimum Viable Product

## Table of Contents
- [1. Problem / Pain Summary](#1-problem--pain-summary)
  - [1.1. Core Problem](#11-core-problem)
  - [1.2. Behavioural Moment](#12-behavioural-moment)
  - [1.3. Emotional Stress](#13-emotional-stress)
  - [1.4. Information Gap](#14-information-gap)
  - [1.5. Venue Gap](#15-venue-gap)
  - [1.6. Why Existing Solutions Fail](#16-why-existing-solutions-fail)
  - [1.7. The Job to be Done](#17-the-job-to-be-done)
  - [1.8. Problem Summary](#18-problem-summary)
 
- [2. Users](#2-users)
  - [2.1. User Identification](#21-user-identification)
    - [2.1.1. Primary User - The On-the-Go Parent or Carer](#211-primary-user--the-on-the-go-parent-or-carer)
    - [2.1.2. Secondary User - Venue Staff / Facility Managers](#212-secondary-user--venue-staff--dacility-managers)
    - [2.1.3. Tertiary User - Other Parents (Asynchronus Consumers)](#213-tertiary-user--other-parents-asynchronus-consumers)
  - [2.2. User Scenarios](#22-user-scenarios)
    - [2.2.1. Scenario 1: The High-Stress, Immediate Need](#221-scenario-1-the-high-stress-immediate-need)
    - [2.2.2. Scenario 2: The "I'm Already in a Venue" Moment](#222-scenario-2-the-im-already-in-a-venue-moment)
    - [2.2.3. Scenario 3: The Planning Ahead Parent](#223-scenario-3-the-planning-ahead-parent)

- [3. Success Criteria / What Good Looks Like](#3-success-criteria--what-good-looks-like)
  - [3.1. Functional Success Criteria](#31-functional-success-criteria)
    - [3.1.1. Parents can find a facility in under 10 seconds](#311-parents-can-find-a-facility-in-under-10-seconds)
    - [3.1.2. Parents can assess facility usability at a glance](#312-parents-can-assess-facility-usability-at-a-glance)
    - [3.1.3. Parents can leave a review in under 20 seconds](#313-parents-can-leave-a-review-in-under-20-seconds)
    - [3.1.4. Parents can add a new or missing facility in under 30 seconds](#314-parents-can-add-a-new-or-missing-facility-in-under-30-seconds)
    - [3.1.5. The product must work instantly via QR entry](#315-the-product-must-work-instantly-via-qr-entry)

  - [3.2. Experience Success Criteria](#32-experience-success-criteria)
    - [3.2.1. One handed, time pressured usability](#321-one-handed-time-pressured-usability)
    - [3.2.2. Zero friction access (no login, no account)](#322-zero-friction-access-no-login-no-account)
    - [3.2.3. Trustworthy, parent generated data](#323-trustworthy-parent-generated-data)
    - [3.2.4. Clear, simple, emotionally calming UI](#324-clear-simple-emotionally-calming-ui)

  - [3.3. Data and Quality Success Criteria](#33-data-and-quality-success-criteria)
    - [3.3.1. Facilities must have at least one parent generated data point](#331-facilities-must-have-at-least-one-parent-generated-data-point)
    - [3.3.2. Reviews must be timestamped and visible](#332-reviews-must-be-timestamped-and-visible)
    - [3.3.3. The system must avoid storing unnecessary personal data](#333-the-system-must-avoid-storing-unnecessary-personal-data)

  - [3.4. Technical Success Criteria](#34-technical-success-criteria)
    - [3.4.1. PWA loads in under 2 seconds on a typical 4G connection](#341-pwa-loads-in-under-2-seconds-on-a-typical-4g-connection)
    - [3.4.2. Works reliably offline or with poor connectivity](#342-works-reliably-offline-or-with-poor-connectivity)
    - [3.4.3. No backend complexity required for MVP](#343-no-backend-complexity-required-for-mvp)

  - [3.5. Behavioural Success Criteria](#35-behavioural-success-criteria)
    - [3.5.1. Parents choose the product over guesswork](#351-parents-choose-the-product-over-guesswork)
    - [3.5.2. Parents contribute data without being asked twice](#352-parents-contribute-data-without-being-asked-twice)
    - [3.5.3. Venues adopt QR codes voluntarily](#353-venues-adopt-qr-codes-voluntarily)

- [Success Summary](#success-summary)

---

## 1. Problem / Pain Summary

### 1.1. Core Problem

Parents and carers often struggle to find clean, safe, and available baby-changing facilities when they are out in public. The information environment is fragmented, unreliable, and often completely absent at the moment of need. This creates unnecessary stress during an already time-sensitive, high pressure situation.

---

### 1.2. Behavioural Moment

The pain occurs in a specific, high-friction moment:

- A parent is out in public
- The baby needs changing now
- They have limited time, limited mobility, and often only one free hand
- They need to know where a facility is, whether it is usable, and how clean it is
- Existing apps, maps, and venue websites do not provide this information
- The parent is forced into guesswork, trial-and-error, or uncomfortable improvisation

This is a high frequency, high stress, low information moment.

---

### 1.3. Emotional Stress

This is not a trivial inconvenience, rather it includes:

- Stress - The baby is uncomfortable and crying
- Hygiene concerns - Parents worry about cleanliness and safety
- Embarrassment - Especially in public or crowded venues
- Time Pressure - Nappies leak, babies wriggle, queues form
- Trust erosion - Parents remember venues that fail them

The emotional load amplifies the functional problem.

---

### 1.4. Information Gap

Parents currently have:

- No reliable way to know if a facility exists
- No way to know if it's clean or usable
- No way to know if it's functional or out of order
- No way to contribute feedback to help others
- No consistent standard across venues

This is a data sparse environment where the people who need information most have the least access to it. 

---

### 1.5. Venue Gap

Venues also suffer from:

- No visibility of how their facilities are perceived
- No structured feedback loop
- No easy way to demonstrate hygiene standards
- No mechanism to build trust with parents
- No incentive to improve without data

The absence of a shared system hurts both sides.

---

### 1.6. Why Existing Solutions Fail

- Maps (e.g. Google, Apple, Bing) and venue websites rarely list baby-changing details
- Reviews are inconsistent, buried, or irrelevant
- "Parenting apps" are either outdated, too broad, or not location-aware
- No solution captures real time, facility specific, parent generated data
- No solution is optimised for the one handed, time pressured moment of need

There is a lot of overwhelmed demand for quality information, but no reliable supply

---

### 1.7. The Job to be Done

"When I'm out with my baby and I need to change them urgently, I want to quickly find a clean, available, trustworthy facility nearby, so I can reduce stress and take care of my child safely."

---

### 1.8. Problem Summary

Parents face a high stress, time critical need to locate clean and reliable baby changing facilities, but the current information ecosystem is fragmented, unreliable, and not designed for real time decision making. Venues lack visibility and feedback loops, and parents lack trustworthy data. The result is unnecessary stress, poor experiences, and avoidable hygiene risks.

---

## 2. Users

### 2.1. User Identification

#### 2.1.1. Primary User - The On‑the‑Go Parent or Carer

This is the core user whose pain is most acute and whose behaviour defines the MVP.

**Profile**  

- Parent or carer of an infant (0–24 months)  
- Frequently out in public (shopping centres, cafés, parks, transport hubs)  
- Often alone or with limited support  
- Typically carrying bags, prams, or holding the baby  
- Time‑pressured and often one‑handed  

**Behaviours**

- Makes rapid decisions under stress  
- Prioritises hygiene, safety, and convenience  
- Uses mobile devices for quick information  
- Avoids apps requiring accounts or heavy onboarding  
- Values peer‑generated, trustworthy information  

**Needs**  

- Immediate clarity on where to go  
- Confidence that the facility is clean and usable  
- A quick way to contribute feedback  
- A frictionless, no‑login experience  

**Why they matter**

They experience the problem most intensely and most frequently. Their behaviour defines the MVP’s success.

#### 2.1.2. Secondary User - Venue Staff / Facility Managers

Not the primary user, but they benefit from the system and influence adoption.

**Profile**  

- Staff at cafés, restaurants, shops, leisure centres, transport hubs  
- Responsible for hygiene, customer experience, or compliance  

**Behaviours**

- Respond to complaints reactively  
- Have limited visibility of facility conditions  
- Want to improve customer satisfaction but lack data  

**Needs**

- A simple way to see feedback trends  
- A way to demonstrate cleanliness and care  
- A mechanism to close the loop with parents  

**Why they matter**

They are the supply side of the ecosystem. Their participation improves data quality and trust.

#### 2.1.3. Tertiary User - Other Parents (Asynchronous Consumers)

Parents who are not currently in crisis but benefit from the data.

**Profile**

- Planning outings  
- Comparing venues  
- Choosing between cafés, shops, or attractions  

**Behaviours**

- Browse reviews  
- Prefer reliable, recent information  
- Use data to plan ahead rather than in‑the‑moment decisions  

---

### 2.2. User Scenarios

#### 2.2.1. Scenario 1: The High‑Stress, Immediate Need (Primary Scenario)

Sarah is out alone with her 8‑month‑old baby in a busy shopping centre. After 45 minutes of walking, she notices the baby is fussing and smells a dirty nappy. She is carrying bags, pushing a pram, and has only one free hand.

She doesn’t know:

- where the nearest baby‑changing facility is  
- whether it is clean  
- whether it is available  

She feels time pressure, stress, and embarrassment as the baby becomes increasingly upset. She needs a fast, trustworthy way to find a usable facility **right now**.

This is the core behavioural moment the MVP must serve.

#### 2.2.2. Scenario 2: The “I’m Already in a Venue” Moment (Secondary Scenario)

James is in a café with his newborn. The baby suddenly needs changing. The café has a toilet, but he doesn’t know:

- if it includes a baby‑changing table  
- whether it’s clean  
- whether it’s currently usable  

He doesn’t want to pack everything up and leave unless he has to. He needs a quick way to check what other parents have said about the facility so he can make a confident decision without disrupting his visit or making multiple trips.

This scenario reinforces the need for ultra‑low‑friction, venue‑specific information.

#### 2.2.3. Scenario 3: The Planning‑Ahead Parent (Tertiary Scenario)

Priya is planning a day out with her 6‑month‑old. She wants to choose between two cafés and a museum. She checks online reviews but finds nothing specific about baby‑changing facilities.

She wants to know which venues have clean, reliable facilities **before she leaves home**, so she can avoid stress later.

This scenario supports the long‑tail value of aggregated, trustworthy data.

---

#### Scenario Summary

Parents experience the problem in two primary contexts:

1. **An urgent, high‑stress moment** where they need to find a clean, trustworthy facility immediately.  
2. **A venue‑specific moment** where they need clarity without disrupting their visit.  

A third, lower‑intensity scenario involves parents planning ahead and relying on aggregated data.

These scenarios anchor the behavioural requirements for the MVP.

---

## 3. Success Criteria / What Good Looks Like

### 3.1. Functional Success Criteria

#### 3.1.1. Parents can find a facility in under 10 seconds

The product must enable a parent, often one handed and under stress, to identify a nearby baby changing facility with minimal friction.

#### 3.1.2. Parents can assess facility usability at a glance

The facility detail view must provide enough clarity (cleanliness, usability, parent feedback) for a parent to make a confident decision without trial and error.

#### 3.1.3. Parents can leave a review in under 20 seconds

Submitting feedback must be a fast, lightweight, and possible with one hand. No login, no account creation, no heavy forms.

#### 3.1.4. Parents can add a new or missing facility in under 30 seconds

The system must allow rapid contribution of new facilities to improve coverage and data quality. 

#### 3.1.5. The product must work instantly via QR entry

Scanning a QR code in a venue must open the Progressive Web Application (PWA) immediately, with no installation or onboarding.

---

### 3.2. Experience Success Criteria

#### 3.2.1. One handed, time pressured usability

All core interactions must be achievable with one hand, under stress, in a public environment.

#### 3.2.2. Zero friction access (no login, no account)

Parents must be able to use the product without authentication, registration, or profile creation.

#### 3.2.3. Trustworthy, parent generated data

Information must feel credible, recent, and relevant - driven by real parent reviews, not venue marketing.

#### 3.2.4. Clear, simple, emotionally calming UI

The interface must reduce cognitive load in a stressful moment, with minimal text, clear 
icons, and fast paths to action.

---

### 3.3. Data and Quality Success Criteria

#### 3.3.1. Facilities must have at least one parent generated data point

A facility is only considered "usable" in the system once it has a review, rating, or confirmation.

#### 3.3.2. Reviews must be timestamped and visible

Parents must be able to see how recent the information is to assess reliability.

#### 3.3.3. The system must avoid storing unnecessary personal data

Data collection must be minimal, privacy-first, and compliant with relevant regulations - GDPR(UK), DPA(2018), etc

---

### 3.4. Technical Success Criteria

#### 3.4.1. PWA loads in under 2 seconds on a typical 4G connection

Speed is critical in the moment of need.

#### 3.4.2. Works reliably offline or with poor connectivity

Core flows (viewing cached facility information, leaving a review to sync later) must function even with intermittent signal.

#### 3.4.3. No backend complexity required for MVP

The MVP must rely on lightweight storage and simple APIs to minimise operational overhead. 

---

### 3.5. Behavioural Success Criteria

#### 3.5.1. Parents choose the product over guesswork

The product must be faster and more reliable than wandering around or asking staff.

#### 3.5.2. Parents contribute data without being asked twice

The review flow must be so lightweight that parents naturally add feedback after using a facility.

#### 3.5.3. Venues adopt QR codes voluntarily

The value proposition must be clear enough that cafes, shops, and public venues choose to display QR codes without incentives.

---

### Success Summary

The product is successful if parents can find and assess a baby changing facility in under 10 seconds, leave feedback in under 20 seconds, and trust the information they see - all without login, installation, or friction. The system must be fast, lightweight, privacy first, and usable one handed under stress. Data must be parent generated, recent, and credible. Venues must find it easy to participate by displaying QR codes. The MVP must deliver these outcomes with minimal technical complexity.

---

## 4. Constraints 

### 4.1. Technical Constraints

#### 4.1.1. PWA, not native

The MVP must be delivered as a lightweight Progressive Web Application (PWA). No native app development, no app store distribution, no installation friction.

#### 4.1.2. No login, no accounts, no authentication

The product must function entirely without user accounts. This eliminates backend complexity, reduces privacy risk, and preserves one handed immediacy. 

#### 4.1.3. Minimal backend

The MVP must rely on simple, lightweight storage and APIs. No complex infrastructure, no microservices, no heavy data pipelines.

#### 4.1.4. Privacy first, minimal data collection

The system must not collect personal data beyond what is strictly necessary for functionality. No tracking, no analytics requiring consent banners, no behaviour profiling. 

#### 4.1.5. Offline tolerant

The PWA must degrade gracefully in low connectivity environments. Cached facility data and queued reviews must function without a stable connection. 

---

### 4.2. Product Constraints

#### 4.2.1. No real time occupancy or sensor integrations

The MVP must not attempt to detect whether a facility is currently occupied or available. No IoT, no staff updated dashboards, no live status feeds.

#### 4.2.2. No venue side dashboard or management tools

Venues are not part of the MVP's operational model. No onboarding, no admin accounts, no analytics.

#### 4.2.3. No moderation queue or complex review system

Reviews must be lightweight and self policing. No manual moderation, no content workflows, no dispute resolution.

#### 4.2.4. No map provider custom integrations

The MVP must use standard mapping APIs without custom layers or paid enterprise features.

---

### 4.3. Operational Constraints

#### 4.3.1. Early venue participation is passive

QR codes will be placed unilaterally in early stages to seed usage and data. No formal venue partnerships, no approval workflows, no sales motion.

#### 4.3.2. Zero dependency on venue cooperation

The product must deliver value even if venues ignore, remove, or never adopt QR codes.

#### 4.3.3. No field team operations

There will be no staff visiting venues, auditing facilities, or collecting data manually.

---

### 4.4. UX Constraints

#### 4.4.1. One handed usability

All core interactions must be achievable with one hand, under stress, in public.

#### 4.4.2. Ultra low cognitive load

The interface must avoid heavy text, complex navigation, or multi-step flows.

#### 4.4.3. No onboarding or tutorials

The product must be instantly usable on first load.

---

### 4.5. Compliance and Legal Constraints

#### 4.5.1. No storage of sensitive personal data

The system must avoid collecting or storing any data that could create GDPR or COPPA obligations.

#### 4.5.2. No claims of venue affiliation

QR codes and facility listings must not imply endorsement or partnership unless explicitly agreed.

#### 4.5.3. No liability for facility conditions

The product must not guarantee cleanliness, safety, or availability - only report user generated feedback.

---

### Constraint Summary

The MVP must be a lightweight, privacy first PWA with no accounts, no real time data, no venue dashboards, and minimal backend complexity. It must deliver value without venue cooperation, support one handed use under stress, and avoid any features that introduce operational overhead, legal exposure, or technical heaviness. Early adoption will be seeded unilaterally through QR codes, with venues treated as passive participants. 

