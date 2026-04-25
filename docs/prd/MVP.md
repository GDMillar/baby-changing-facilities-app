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

---

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

---

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

---

#### 2.2.2. Scenario 2: The “I’m Already in a Venue” Moment (Secondary Scenario)

James is in a café with his newborn. The baby suddenly needs changing. The café has a toilet, but he doesn’t know:

- if it includes a baby‑changing table  
- whether it’s clean  
- whether it’s currently usable  

He doesn’t want to pack everything up and leave unless he has to. He needs a quick way to check what other parents have said about the facility so he can make a confident decision without disrupting his visit or making multiple trips.

This scenario reinforces the need for ultra‑low‑friction, venue‑specific information.

---

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
