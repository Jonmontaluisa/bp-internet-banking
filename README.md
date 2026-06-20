# BP Internet Banking — Solution Architecture (Deliverable)

Architecture exercise for **BP** (Banca por Internet), Ecuador retail context.

## Task (summary)

Design a digital banking platform where customers can:

- View movement history
- Transfer between own accounts and interbank (SWIFT)
- Use **web (SPA)** and **mobile** (multiplatform framework)
- Authenticate with **OAuth 2.0** (Auth0), including **facial onboarding** on mobile
- Integrate **Core Banking** + **Client Detail** legacy systems via **API Gateway**
- Notify movements via **email + SMS**; maintain **immutable audit** and **cache** for frequent clients
- Meet **HA, DR, security, monitoring** on **AWS**, documented with **C4** (Context → Containers → Components) and **ADRs**

## Deliverables

| Item | Location |
|------|----------|
| **Live architecture (diagrams, docs, ADRs)** | [Structurizr on Railway](https://bankinfra-production.up.railway.app/workspace/1) |
| **PDF export (C4 diagrams)** | Add your PDF file in this folder |

## Source repository

Implementation and DSL: sibling folder [`reto`](../reto).
