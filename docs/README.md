# OctoAcme Project Management Documentation

## Welcome

This directory contains the complete OctoAcme project management framework used to run all cross-functional projects. Our documentation provides structured guidance, templates, and workflows to help teams execute projects consistently, communicate effectively, and continuously improve.

## Our Approach

OctoAcme follows a **customer-first, iterative delivery model** with clear ownership, data-driven decisions, and psychological safety. Our framework guides teams through five key lifecycle phases: **Initiation → Planning → Execution → Release → Retrospective**.

### Key Principles
- **Customer-first:** Prioritize customer value and usability
- **Iterative delivery:** Deliver small, testable increments
- **Clear ownership:** Each project has named Project Manager (PM) and Product Lead
- **Data-informed:** Measure impact and iterate based on evidence
- **Psychological safety:** Encourage feedback and learning

---

## OctoAcme Project Management: Process Overview

OctoAcme employs a structured, lifecycle-based approach to project management that emphasizes customer value, iterative delivery, and clear ownership. The methodology spans five key phases: **Initiation**, **Planning**, **Execution**, **Release**, and **Close & Retrospective**. During initiation, teams validate business need and establish alignment through a lightweight Project One-pager that defines the problem statement, success metrics, stakeholders, and resource needs. Once approved by the Product Lead and sponsors, the project moves into planning, where work is broken into shippable increments with clear acceptance criteria, dependencies are mapped, and a Definition of Done is established.

Execution and delivery are managed through a disciplined workflow centered on small, reviewable pull requests (≤400 lines when possible), automated CI/CD pipelines with testing and security scanning, and a project board with standardized columns (Backlog, Ready, In Progress, In Review, QA, Done). The team maintains a predictable cadence with daily standups focused on progress and blockers, weekly delivery syncs with the Product and Project Managers, and regular demos to stakeholders. Quality is ensured through unit tests, integration tests, end-to-end smoke tests for critical flows, and manual QA where needed. Risk management is continuous—blockers are triaged in standups, escalated through a three-level escalation path (team → PM → Product Lead → Sponsor), and tracked in a living Risk Register updated weekly.

Release and deployment follow a standardized process with clear pre-release requirements: all acceptance criteria must be met, CI and security scans must pass, release notes must be drafted, and a rollback plan must be documented. Deployments proceed through staging verification before production, with post-deploy verification and stakeholder communication. Finally, OctoAcme closes each project or sprint with a retrospective—a 45–75 minute meeting that captures what went well, identifies improvements, and tracks 2–3 prioritized action items with clear owners and due dates. These action items feed back into future backlogs, creating a continuous improvement cycle.

**Core roles** in OctoAcme are clearly defined: the **Project Manager** coordinates delivery, schedules, risks, and communications; the **Product Manager** defines outcomes, prioritizes the backlog, and measures success; **Developers** implement features with quality and testability in mind; and **QA/Testing** validates acceptance criteria. Communication is systematic—weekly PM/PdM syncs, twice-weekly standups, monthly stakeholder updates, and ad-hoc escalations for risks or incidents. All key artifacts (charter, roadmap, sprint backlog, risk register, retrospective notes) are centralized in the project repository, ensuring transparency and enabling new team members to quickly understand the project state, decisions, and rationale.

---

## Core Processes

### 1. **Project Initiation** — Validate & Align
Define the business problem, identify stakeholders, confirm success metrics, and make a go/no-go decision to move into planning.

→ [Read the Project Initiation Guide](./octoacme-project-initiation.md)

**Key Deliverables:**
- Project One-pager (Problem, Goal, Success Metrics)
- Stakeholder list & communication plan
- High-level timeline and key milestones
- Initial risk list

---

### 2. **Project Planning** — Build the Roadmap
Break work into shippable increments, estimate scope, define acceptance criteria, identify dependencies, and create a release plan.

→ [Read the Project Planning Guide](./octoacme-project-planning.md)

**Key Activities:**
- Kickoff meeting with stakeholders and delivery team
- Create prioritized backlog with acceptance criteria
- Estimate scope (T-shirt sizing or story points)
- Define Definition of Done (DoD)
- Identify dependencies and integration points

---

### 3. **Execution & Tracking** — Deliver with Visibility
Manage day-to-day execution, maintain quality standards, track progress, and escalate blockers.

→ [Read the Execution & Tracking Guide](./octoacme-execution-and-tracking.md)

**Key Workflows:**
- Small PRs (≤ 400 lines when possible)
- Daily standups (15 min) focused on progress and blockers
- Weekly delivery syncs to show progress and flagged risks
- Automated CI with tests, linting, and security scanning
- Regular demos and reviews

---

### 4. **Release & Deployment** — Deploy Safely
Standardize release processes with pre-release checks, staged deployments, and rollback procedures.

→ [Read the Release & Deployment Guide](./octoacme-release-and-deployment.md)

**Pre-Release Requirements:**
- All acceptance criteria met and PRs merged
- Passing CI and security scans
- Release notes drafted
- Rollback / mitigation plan documented
- Smoke tests prepared

---

### 5. **Retrospectives & Improvement** — Learn & Iterate
Capture learnings, convert them into actionable improvements, and feed action items back into the backlog.

→ [Read the Retrospective & Continuous Improvement Guide](./octoacme-retrospective-and-continuous-improvement.md)

**Retrospective Structure:**
- What went well
- What could be improved
- 2–3 prioritized action items (owner, due date)
- Follow-up on previous action items

---

## Key References

### Risk Management & Communication
Learn how to identify, manage, and communicate risks and dependencies throughout the project lifecycle.

→ [Read the Risk Management & Communication Guide](./octoacme-risks-and-communication.md)

**Topics:**
- Risk Register structure and lifecycle
- Stakeholder communication templates
- Escalation paths (team → PM → Product Lead → Sponsor)

---

### Roles & Personas
Understand the responsibilities and communication style of key roles: Developers, Product Managers, and Project Managers.

→ [Read the Roles & Personas Guide](./octoacme-roles-and-personas.md)

**Roles Defined:**
- **Developers** — Design, build, test, and deliver software components
- **Product Managers** — Define what should be built and measure outcomes
- **Project Managers** — Coordinate delivery, manage schedules, risks, and communications

---

### Project Management Overview
A concise, shareable introduction to OctoAcme's approach, principles, lifecycle, and key artifacts.

→ [Read the Project Management Overview](./octoacme-project-management-overview.md)

---

## Quick Start

### New to OctoAcme?
Start with the **[Project Management Overview](./octoacme-project-management-overview.md)** for a concise introduction to our approach and key artifacts.

### Starting a New Project?
Follow this sequence:
1. [Project Initiation Guide](./octoacme-project-initiation.md) — Validate need and align stakeholders
2. [Project Planning Guide](./octoacme-project-planning.md) — Break work into shippable increments
3. [Execution & Tracking Guide](./octoacme-execution-and-tracking.md) — Manage day-to-day delivery

### Managing Risks or Dependencies?
See the [Risk Management & Communication Guide](./octoacme-risks-and-communication.md).

### Preparing for Release?
See the [Release & Deployment Guide](./octoacme-release-and-deployment.md).

### Learning from a Sprint or Project?
See the [Retrospective & Continuous Improvement Guide](./octoacme-retrospective-and-continuous-improvement.md).

---

## Communication Cadence

- **Daily:** Standups (15 min) focused on progress and blockers
- **Weekly:** PM + PdM sync; delivery team syncs
- **Milestone-based:** Demos, stakeholder updates, retrospectives
- **Ad-hoc:** Risk escalations, incident communications

---

## Document Index

| Document | Purpose |
|----------|---------|
| [octoacme-project-management-overview.md](./octoacme-project-management-overview.md) | Concise intro to approach, roles, artifacts, and lifecycle |
| [octoacme-project-initiation.md](./octoacme-project-initiation.md) | Guide for validating need, aligning stakeholders, and go/no-go decisions |
| [octoacme-project-planning.md](./octoacme-project-planning.md) | Guide for breaking work into increments, estimating, and planning releases |
| [octoacme-execution-and-tracking.md](./octoacme-execution-and-tracking.md) | Guide for day-to-day execution, quality standards, and blocker escalation |
| [octoacme-risks-and-communication.md](./octoacme-risks-and-communication.md) | Guide for risk management, communication templates, and escalation paths |
| [octoacme-release-and-deployment.md](./octoacme-release-and-deployment.md) | Guide for standardizing releases, pre-release checks, and rollback procedures |
| [octoacme-retrospective-and-continuous-improvement.md](./octoacme-retrospective-and-continuous-improvement.md) | Guide for capturing learnings and driving continuous improvement |
| [octoacme-roles-and-personas.md](./octoacme-roles-and-personas.md) | Definitions of key roles, responsibilities, and communication styles |

---

## How to Use This Documentation

- **Keep the Project Charter updated** in your project repo
- **Add process-specific docs** to `.copilot/` if you want Copilot Spaces to use them as context
- **Use the templates and checklists** in each guide to standardize execution
- **Reference the Risk Register** and communication templates when coordinating cross-team work
- **Capture action items from retrospectives** and feed them back into your project backlog

---

## Questions or Updates?

If you have feedback, notice a gap, or want to propose an update to these processes, please open an issue using the [Add Content to Project Management Process Docs](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) template.

---

*Last Updated: September 2026*
