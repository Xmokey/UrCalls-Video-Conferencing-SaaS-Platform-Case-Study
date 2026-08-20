# UrCalls

## Video collaboration for SMEs, solopreneurs and independent professionals

**Role:** Product / Project Director & Delivery Lead  
**Product:** Video conferencing and virtual-engagement SaaS  
**Audience:** SMEs, solopreneurs, service providers, online educators, coaches and similar users  
**Status:** Delivered

---

## The product problem

The collaboration market sits between two extremes.

Enterprise collaboration platforms can provide extensive capability, but often bring complexity, cost and operational overhead that smaller organisations do not need. Basic meeting tools solve the call itself, but can fall short when users need structured collaboration around the meeting.

UrCalls was built for the middle ground:

> **Not so enterprise-heavy that it becomes complicated, and not so basic that it lacks the capabilities required for serious collaborative work.**

The product therefore had to balance **capability, simplicity and accessible usage models** rather than compete on feature volume alone.

![UrCalls meeting experience](assets/UrCalls%20Meeting%20Screen%20UI.png)

---

## Product strategy

I helped shape the product around a simple principle: give smaller organisations and independent professionals the capabilities they actually need to run professional virtual work without forcing them into an enterprise collaboration model.

That meant treating meetings, webinars, recordings, collaboration and organisation controls as connected product capabilities rather than unrelated features.

The resulting platform combined:

**Meetings · Webinars · Recording · AI meeting notes · Breakout rooms · Whiteboard · Team/seat management · Branding/customisation**

![UrCalls dashboard](assets/UrCalls%20Dashboard.png)

---

## Decision 1: distinguish collaboration from audience-scale engagement

Meetings and webinars serve different jobs.

**Meetings** support ongoing collaboration between teams, clients and participants.

**Webinars** support structured, larger-scale audience engagement such as training, events and presentations.

Rather than treating webinars as simply a larger meeting room, UrCalls gave them a distinct operational and commercial model.

![UrCalls webinar management](assets/UrCalls%20Dashboard---%20Webinar%20Tab.png)

This distinction allowed the product to support both everyday collaborative work and higher-scale virtual engagement without turning the entire product into an enterprise event platform.

---

## Decision 2: scale webinar usage without enterprise-style fixed pricing

Webinars introduced a different cost and capacity profile from ordinary meetings.

The product therefore used a usage-based model:

**Subscription → Webinar eligibility → Credits → Attendee tier → Session consumption**

Business and Premium users could access webinar functionality, while webinar sessions consumed credits according to the selected attendee tier.

The product decision was to let occasional users access higher-scale engagement without forcing them into a permanently high-cost enterprise plan.

This was directly connected to the original positioning: **capability should scale with the user's actual need.**

---

## Decision 3: separate recording from AI processing

Recording was designed with two distinct modes.

**Local recording** remained on the user's device and did not consume platform storage.

**Cloud recording** was managed by the platform and uses organisational storage according to the applicable storage entitlement.

AI meeting notes and related AI functionality are **platform-processed independently of the user's storage allocation**. AI processing is therefore not gated by whether the user has available recording storage.

![UrCalls recording management](assets/UrCalls%20Dashboard---%20Recording%20Tab.png)

This distinction keeps two different product concerns separate:

**Recording → Storage entitlement**

**Meeting content → AI processing**

---

## Decision 4: keep AI as a productivity layer

AI was deliberately positioned as an enhancement to collaboration, not as the identity of the product.

AI-generated meeting notes, summaries and analytics reduce the administrative work that follows a meeting while leaving the core collaboration experience unchanged.

The AI capability is handled as a platform service rather than as a feature gated by the user's storage capacity.

The product remained a video collaboration platform first, with AI improving what happens after or around collaborative sessions.

---

## Decision 5: make organisation controls part of the product

UrCalls was designed as a multi-user business platform rather than a collection of individual meeting accounts.

Organisation and seat management provided a structure for teams, permissions and plan entitlements. Branding and customisation could also be controlled at the organisation level so customer-facing experiences remained consistent across hosts.

This mattered particularly for service providers, educators, coaches and businesses using virtual meetings as part of their professional delivery.

![UrCalls meeting environment](assets/Urcalls%20Meeting%20Room.png)

---

## Technical product challenge

The product promise created a technical requirement: the experience needed to remain usable for customers operating under varying network conditions while supporting real-time communication at scale.

I worked with engineering around WebRTC performance, network reliability, latency, scalability and infrastructure cost.

The product therefore required trade-offs between:

**Experience quality ↔ Network resilience ↔ Scale ↔ Infrastructure cost**

This was technical product work because the customer promise—professional collaboration without enterprise overhead—depended on the underlying system behaving reliably in real-world conditions.

---

## My role

I operated across product definition and technical delivery, translating business requirements into structured product and engineering work and coordinating execution across frontend, backend, infrastructure, design, marketing and operations.

My responsibilities included:

- shaping product scope and delivery priorities
- translating business requirements into implementable workflows
- coordinating frontend, backend and infrastructure dependencies
- working through real-time communication and reliability constraints with engineering
- aligning product readiness with launch and marketing activity
- overseeing post-launch stabilisation and iteration
- validating that delivered capabilities matched the intended product behaviour

The contribution was not simply coordinating a list of features. It was helping turn the product positioning into a coherent set of capabilities, commercial rules and technical constraints.

---

## Evidence

The repository contains deeper product documentation, implementation context and additional interface evidence.

Selected screens demonstrate the product's main operating surfaces:

![Meeting pre-join](assets/UrCalls%20Meeting%20Pre-join%20screen.png)

![Meeting grid](assets/Urcalls%20Meeting%20Room%202.png)

![Support](assets/UrCalls%20Dashboard---%20Support%20Tab.png)

---

## Outcome

UrCalls was delivered as a video conferencing and virtual-engagement platform designed to occupy the gap between enterprise-heavy collaboration systems and basic meeting tools.

The product combined professional meeting capability with webinars, recording, AI-assisted documentation, collaboration features, organisation controls and customisation—while using usage-based webinar economics to support higher-scale activity without requiring every customer to adopt an enterprise-style model.

Specific commercial or adoption metrics are not claimed here.

The product outcome that can be demonstrated is the translation of a clear market gap into a working SaaS platform with differentiated product, commercial and technical decisions.

---

## Repository

The [README](README.md) provides the deeper product and delivery documentation, while this case study presents the high-level product story and key decisions.

[View the UrCalls live product](https://urcalls.com)
