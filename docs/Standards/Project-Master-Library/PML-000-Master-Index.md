# PML-000 — Project Master Library Master Index & Document Control

**Project:** Trading Intelligence Platform (TIP)
**Document ID:** PML-000
**Version:** 1.0.0
**Status:** Approved (Initial Baseline)
**Classification:** Project Governing Standard
**Owner:** TIP Architecture & Engineering Team

---

# 1. Purpose

The **Project Master Library (PML)** is the governing body of standards for the Trading Intelligence Platform (TIP).

It defines the engineering principles, architecture standards, coding standards, documentation standards, testing standards, operational procedures, and governance processes that every contributor shall follow.

The PML is the **authoritative source of truth** for all implementation activities.

---

# 2. Scope

The PML applies to:

* Software architecture
* MQL5 development
* Python development
* Database development
* AI components
* APIs
* Infrastructure
* Documentation
* Testing
* Security
* DevOps
* Deployment
* Release management

Every component of the Trading Intelligence Platform shall comply with the applicable PML standards.

---

# 3. Engineering Rule ER-001

**Every implementation produced for the Trading Intelligence Platform shall comply with the Project Master Library (PML).**

Where a conflict exists between implementation and the PML:

1. The PML shall be considered authoritative.
2. Any required deviation shall be documented through an approved Architecture Decision Record (ADR).
3. The PML shall be updated only through the project's formal change management process.

---

# 4. Document Hierarchy

The governing hierarchy for the project is:

1. Project Master Library (PML)
2. Architecture Decision Records (ADR)
3. Volumes 1–4 (Architecture & Design)
4. Source Code
5. Tests
6. Deployment Artifacts

---

# 5. Project Documentation Structure

```text
Trading-Intelligence-Platform/

docs/

    Standards/
        Project-Master-Library/

    Volume-01/
    Volume-02/
    Volume-03/
    Volume-04/

    ADR/
    UML/
    API/
```

---

# 6. Project Master Library Index

## Governance

* PML-000 — Master Index & Document Control
* PML-001 — Project Charter
* PML-002 — Governance Framework
* PML-003 — Document Control Standard
* PML-004 — Configuration Management
* PML-005 — Change Management

## Architecture

* PML-100 — Enterprise Architecture Principles
* PML-101 — Layered Architecture
* PML-102 — Domain Model
* PML-103 — Component Architecture
* PML-104 — Event-Driven Architecture
* PML-105 — Technology Stack

## Development

* PML-200 — Coding Standards
* PML-201 — MQL5 Coding Standard
* PML-202 — Python Coding Standard
* PML-203 — Naming Standard
* PML-204 — Documentation Standard
* PML-205 — Logging Standard
* PML-206 — Error Handling Standard
* PML-207 — Dependency Injection Standard
* PML-208 — Repository Pattern Standard

## Quality

* PML-300 — Testing Standards
* PML-301 — Unit Testing
* PML-302 — Integration Testing
* PML-303 — Performance Testing
* PML-304 — Security Testing
* PML-305 — Code Review Standard

## Operations

* PML-400 — DevOps Standard
* PML-401 — Git Workflow
* PML-402 — CI/CD Standard
* PML-403 — Release Management
* PML-404 — Deployment Standard
* PML-405 — Monitoring & Observability

## Knowledge Base

* PML-500 — Design Patterns
* PML-501 — Templates
* PML-502 — Checklists
* PML-503 — Architecture Decision Records
* PML-504 — Project Glossary

---

# 7. Versioning

The PML follows Semantic Versioning:

* Major — Significant structural or governance changes.
* Minor — New standards or expanded guidance.
* Patch — Corrections, clarifications, or editorial improvements.

Example:

* 1.0.0
* 1.1.0
* 1.1.1
* 2.0.0

---

# 8. Change Control

Changes to the PML shall:

* Be proposed through Git.
* Be reviewed before approval.
* Include revision history.
* Reference any associated ADRs.
* Be merged only after review.

---

# 9. Compliance

All software modules, documentation, tests, and deployment artefacts shall reference the relevant PML standards where applicable.

Compliance with the PML is mandatory for inclusion in the official Trading Intelligence Platform repository.

---

# 10. Initial Baseline

PML Version 1.0 establishes the initial engineering governance framework for the Trading Intelligence Platform and serves as the foundation for all future development activities.

