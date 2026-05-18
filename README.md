# EVA Ecosystem

EVA Ecosystem is the main landing repository for the EVA healthcare platform.
It presents the relationship between the EVA applications, shared engineering patterns, and the overall platform architecture without merging the repositories into a monorepo structure.

## Hero

Multi-application healthcare ecosystem focused on modular Flutter architecture, role-oriented workflows, and scalable engineering patterns.

---

## EVA Ecosystem Overview

The platform is organized into separate operational applications, each responsible for a specific part of the healthcare workflow.

The ecosystem separates:

* patient-facing experiences
* clinician workflows
* hospital operations
* commerce and transaction flows

This repository acts as the ecosystem overview and navigation entry point for the EVA platform.

---

## Shared Engineering Patterns

* Feature-driven Flutter architecture
* Riverpod-based state management
* AutoRoute-generated navigation
* Shared API communication patterns
* Arabic / English localization support
* Reusable UI and workflow conventions
* Role-oriented application boundaries

---

## Ecosystem Applications

| Application           | Responsibility                                                             | Repository                                                                               |
| --------------------- | -------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------- |
| EVA Client Showcase   | Patient booking, consultations, records, and engagement workflows          | [eva-client-showcase](https://github.com/1-abdelrahman-khalil-1/eva-client-showcase)     |
| EVA Doctor Showcase   | Doctor scheduling, consultations, reviews, and clinician workflows         | [eva-doctor-showcase](https://github.com/1-abdelrahman-khalil-1/eva-doctor-showcase)     |
| EVA Hospital Showcase | Hospital-side operations, service management, and administrative workflows | [eva-hospital-showcase](https://github.com/1-abdelrahman-khalil-1/eva-hospital-showcase) |
| EVA Store Showcase    | Marketplace operations, orders, and commerce workflows                     | [eva-store-showcase](https://github.com/1-abdelrahman-khalil-1/eva-store-showcase)       |

---

## Screenshots / GIFs

Add ecosystem screenshots and workflow previews here when available.

Suggested assets:

* Patient booking flow
* Doctor scheduling flow
* Hospital dashboard
* Store order workflow

---

## System Architecture Overview

```text
                EVA Ecosystem
 ┌─────────────────────────────────────┐
 │         Shared Backend APIs         │
 └─────────────────────────────────────┘
        ▲         ▲         ▲         ▲
        │         │         │         │
   Client App  Doctor App  Hospital  Store
```

---

## Engineering Stack

### Mobile

* Flutter
* Dart
* Riverpod
* AutoRoute
* Dio


### Engineering Practices

* Feature-first architecture
* Modular workflows
* Shared state patterns
* Reusable UI systems
* RTL / LTR localization support

---

## Operational Workflow Overview

1. Patients interact through EVA Client.
2. Consultation and booking workflows connect with EVA Doctor.
3. Hospital-side operations are handled through EVA Hospital.
4. Product and commerce flows are handled through EVA Store.
5. Shared APIs and engineering patterns keep the ecosystem consistent while allowing each application to remain independent.

---

## Repository Notes

* This repository is presentation-focused and documentation-oriented.
* Source code remains inside the individual EVA repositories.
* The ecosystem intentionally keeps repositories separated instead of using a monorepo structure.
* This repository acts as the primary navigation and architecture overview for the EVA platform.
