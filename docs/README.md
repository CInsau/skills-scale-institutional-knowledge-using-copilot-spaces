# OctoAcme Project Management Docs

Welcome to OctoAcme's central location for project management process documentation. This README helps all teammates quickly understand our approach, roles, and key workflows, and provides direct links to each core process document.

## Brief Project Management Process Overview

OctoAcme uses a structured, iterative, and customer-first approach, designed for cross-functional delivery. Projects follow five lifecycle phases—**Initiation, Planning, Execution, Release, and Retrospective**. The framework is grounded in five core principles:

- **Customer-first**: Prioritize customer value and usability
- **Iterative delivery**: Deliver small, testable increments  
- **Clear ownership**: Each project has a named Project Manager and Product Lead
- **Data-informed decisions**: Measure impact and iterate based on evidence
- **Psychological safety**: Encourage feedback and learning

### Core Roles & Responsibilities

- **Project Managers**: Coordinate delivery, manage schedules, risks, and cross-team communications
- **Product Managers**: Define outcomes, prioritize backlog, and measure success metrics
- **Developers**: Build features, write and maintain tests, participate in code reviews, identify technical risks
- **QA/Testing**: Validate quality and acceptance criteria

### Key Workflows & Communication Cadence

**Planning & Execution:**
- Projects start with a lightweight One-pager (problem, goal, success metrics, stakeholders, timeline)
- Prioritized backlog with acceptance criteria and risk registers
- GitHub Projects board tracking (Backlog → Ready → In Progress → In Review → QA → Done)
- Daily standups (15 min): progress, blockers, dependencies
- Weekly delivery syncs: progress updates, risk review, and alignment
- Weekly PM/PdM alignment on priorities and blockers

**Quality & Code Review:**
- Pull Request workflow: small PRs (≤400 lines), issue links, automated CI/lint, peer approval
- Unit, integration, and end-to-end smoke tests
- Security scanning in CI pipeline
- Manual QA for feature acceptance when needed

**Risk & Communication Management:**
- Risk Register (ID, description, impact, likelihood, owner, mitigation) updated weekly
- Escalation path for blockers: Team → PM → Product Lead → Sponsor
- Monthly stakeholder updates and ad-hoc incident communication

**Continuous Improvement:**
- Retrospectives after each sprint, release, or milestone (45–75 min)
- Action items tracked in backlog with clear owners and due dates
- Impact measurement to reinforce iterative learning culture

## Process Documents

Browse the process documents linked below. Start with the **[Project Management Overview](octoacme-project-management-overview.md)** for a quick introduction.

- **[Project Management Overview](octoacme-project-management-overview.md)** — High-level introduction to OctoAcme's approach, roles, and key artifacts
- **[Project Initiation Guide](octoacme-project-initiation.md)** — How to validate work and authorize new initiatives
- **[Project Planning](octoacme-project-planning.md)** — How to turn approved initiatives into actionable plans and backlogs
- **[Execution & Tracking](octoacme-execution-and-tracking.md)** — How to manage day-to-day execution and track progress toward milestones
- **[Risk Management & Communication](octoacme-risks-and-communication.md)** — How to identify, manage, and communicate risks and dependencies
- **[Release & Deployment Guide](octoacme-release-and-deployment.md)** — How to standardize releases and reduce deployment risk
- **[Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)** — How to capture learnings and drive improvements
- **[Roles & Personas](octoacme-roles-and-personas.md)** — Detailed definitions of typical roles and responsibilities

## Getting Started

- **New to OctoAcme?** Start with the [Project Management Overview](octoacme-project-management-overview.md).
- **Starting a new project?** Follow the [Project Initiation Guide](octoacme-project-initiation.md).
- **Managing ongoing work?** Reference [Execution & Tracking](octoacme-execution-and-tracking.md) for best practices.
- **Need to escalate a risk?** See [Risk Management & Communication](octoacme-risks-and-communication.md).

## Keep This Docs Updated

As new process documents are added or existing documents are revised, update the links and overview sections in this README. Use the [Add Content to Project Management Process Docs](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) issue template to propose updates.
