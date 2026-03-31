# OctoAcme Project Management Docs

Welcome! This README is the entry point for all OctoAcme project management process documentation. It provides a high-level summary of our methodology and structured navigation to each process guide, so new team members and contributors can quickly orient themselves and find what they need.

## Project Management Process Overview

OctoAcme runs cross-functional projects using a lightweight, iterative lifecycle — **Initiation → Planning → Execution & Tracking → Release & Deployment → Retrospective/Continuous Improvement** — with risk management and communication woven throughout. Every initiative starts with a **Project One-pager** covering the problem statement, SMART goals, success metrics, stakeholder map, and an initial risk list, which acts as a decision gate before detailed planning begins. Once approved, the team builds a **prioritized backlog with acceptance criteria**, produces effort estimates (T-shirt sizing or story points), agrees on a Definition of Done, maps dependencies, and aligns on a milestone and release plan.

Roles are clearly defined to drive accountability: **Project Managers (PMs)** own schedules, risk tracking, and stakeholder communications; **Product Managers (PdMs)** define outcomes, prioritize the backlog, and measure success; **Developers** build, test, document, and contribute to design and code reviews; **QA/Testing** validates quality and acceptance criteria; and **Stakeholders/Sponsors** supply input, prioritization alignment, and escalation authority. Day-to-day execution is managed via a project board with the flow **Backlog → Ready → In Progress → In Review → QA → Done**, with work broken into small, shippable increments for steady progress and fast feedback. PRs are expected to be small and focused, linking to an issue and stating acceptance criteria clearly, with CI checks (tests, lint, security scan) and at least one approval required before merge.

Communication follows a structured cadence: **daily standups** surface progress and blockers; a **weekly delivery sync** tracks risk and overall progress; **end-of-sprint demos** keep stakeholders aligned; and weekly PM+PdM sessions plus periodic stakeholder updates use standardized status templates (progress, next steps, risks/blockers, decisions needed). Risks and dependencies are logged in a **Risk Register** (impact, likelihood, owner, mitigation, status) reviewed weekly, with blockers escalating from team triage to PM coordination, then to product leadership, and to sponsors when business impact demands it.

Quality assurance is built into both execution and release. During development OctoAcme requires **unit tests for new logic**, **integration tests where applicable**, **end-to-end smoke tests for critical flows**, and **security scanning in CI**, supplemented by manual QA for feature acceptance when needed. Releases follow a standardized checklist — acceptance criteria met, CI/security scans passing, release notes drafted, and a rollback plan ready — followed by staged deployment, post-deploy verification, and a retrospective that converts learnings into owned, time-bound action items tracked in the backlog.

## Docs Index

- [Project Management Overview](./octoacme-project-management-overview.md)
- [Project Initiation Guide](./octoacme-project-initiation.md)
- [Project Planning](./octoacme-project-planning.md)
- [Execution and Tracking](./octoacme-execution-and-tracking.md)
- [Risk Management & Communication](./octoacme-risks-and-communication.md)
- [Release & Deployment Guide](./octoacme-release-and-deployment.md)
- [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)
- [Roles and Personas](./octoacme-roles-and-personas.md)

_This README is designed to accelerate onboarding and process clarity for all contributors._
