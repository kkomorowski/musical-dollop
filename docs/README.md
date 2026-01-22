# OctoAcme Project Management Documentation

This README is a landing page for all essential OctoAcme project management process documents stored in the docs/ folder. It provides a high-level summary of how OctoAcme runs projects, followed by direct links to each process doc.

## Overview

OctoAcme runs projects through a lightweight, staged lifecycle: Initiation, Planning, Execution, Release, and Close/Retrospective. Initiation uses a Project One‑pager to capture the problem, SMART goals, success metrics, stakeholders, and a high‑level timeline; projects move to planning only after success metrics, priority, and resourcing are confirmed. Planning breaks approved work into a prioritized, estimated backlog using a standard backlog‑item template, defines a Definition of Done, records dependencies and risks in a Risk Register, and produces a release/milestone map.

Day‑to‑day delivery is driven by predictable workflows and an explicit project board (Backlog → Ready → In Progress → In Review → QA → Done). The pull‑request workflow favors small PRs (<= 400 lines when possible), requires issue links and acceptance criteria in PR descriptions, runs CI (tests, linting, security scans) before review, and enforces at least one approval before merge unless a team policy says otherwise. Team rhythm includes short daily standups for progress and blockers, weekly delivery syncs for progress and risks, and demos/reviews at sprint or milestone boundaries; blockers escalate from team triage to PM → Product Lead → Sponsor.

Roles and responsibilities are explicit and persona‑focused. Product Managers (PdM) define problems, prioritize the backlog, and own success metrics; Project Managers (PM) coordinate plans, timelines, risk registers, and stakeholder communications; Developers implement features, write tests, and participate in reviews; QA validates acceptance criteria and leads manual acceptance when needed; stakeholders provide inputs and approvals. These role descriptions clarify ownership for artifacts (one‑pager, roadmap, backlog, DoD, risk register, retrospectives) and expected communication patterns.

Quality assurance and release practices combine automated and manual checks with observable deployments. New code should include unit tests, integration tests where applicable, and end‑to‑end smoke tests for critical flows; CI enforces tests, linting, and security scanning. Releases follow a checklist (passing CI/security, release notes, rollback/mitigation plan, smoke tests) with staging verification and automated pipelines preferred for production. Post‑release retrospectives capture 2–3 prioritized action items (tracked back into the backlog) to drive continuous improvement.

## Documents

- [octoacme-project-management-overview.md](octoacme-project-management-overview.md)
- [octoacme-project-initiation.md](octoacme-project-initiation.md)
- [octoacme-project-planning.md](octoacme-project-planning.md)
- [octoacme-execution-and-tracking.md](octoacme-execution-and-tracking.md)
- [octoacme-risks-and-communication.md](octoacme-risks-and-communication.md)
- [octoacme-release-and-deployment.md](octoacme-release-and-deployment.md)
- [octoacme-retrospective-and-continuous-improvement.md](octoacme-retrospective-and-continuous-improvement.md)
- [octoacme-roles-and-personas.md](octoacme-roles-and-personas.md)

## Acceptance Criteria

- [x] Content aligns with existing process docs
- [x] Update improves clarity or closes a documented gap
- [ ] Proposed content has been reviewed with stakeholders (if needed)
