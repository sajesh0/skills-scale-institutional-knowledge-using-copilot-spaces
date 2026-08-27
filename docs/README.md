# OctoAcme Project Management Documentation

Welcome to OctoAcme's project management process library. This folder contains comprehensive guidance for running projects that deliver customer value through clear ownership, iterative delivery, and data-informed decision-making.

## Quick Start

New to OctoAcme? Start here: [OctoAcme Project Management Overview](./octoacme-project-management-overview.md)

## Project Lifecycle

OctoAcme projects follow a structured lifecycle:

1. **[Initiation](./octoacme-project-initiation.md)** — Validate business need, align stakeholders, confirm go/no-go
2. **[Planning](./octoacme-project-planning.md)** — Define scope, build backlog, estimate, and create release plan
3. **[Execution & Tracking](./octoacme-execution-and-tracking.md)** — Build, test, and track progress through daily standups and demos
4. **[Release & Deployment](./octoacme-release-and-deployment.md)** — Deploy to production safely with rollback plans
5. **[Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)** — Capture learnings and drive improvements

## Core Documents

- **[Roles & Personas](./octoacme-roles-and-personas.md)** — Understand key roles (PM, PdM, Developers, QA) and their responsibilities
- **[Risk Management & Communication](./octoacme-risks-and-communication.md)** — Manage risks, escalate issues, and keep stakeholders informed

## OctoAcme Project Management Overview

OctoAcme follows a customer-first, data-informed approach to project management built on five core principles: clear ownership, iterative delivery, psychological safety, and measurable outcomes. The framework defines three complementary roles—**Product Managers** who prioritize the roadmap and validate solutions; **Project Managers** who coordinate delivery, manage risks, and maintain stakeholder alignment; and **Developers** who implement features and drive technical quality. 

The structured project lifecycle ensures consistent execution across all initiatives:

- **Initiation** validates business need and establishes success metrics through a lightweight Project One-pager, confirming stakeholder alignment before proceeding
- **Planning** breaks work into shippable increments with clear acceptance criteria, estimates, and a prioritized backlog while identifying dependencies and risks
- **Execution & Tracking** uses a project board workflow, daily standups, and weekly delivery syncs to monitor progress, with small PRs (≤400 lines), automated CI/CD, and at least one approval before merging
- **Release & Deployment** ensures quality through pre-release checklists, smoke testing, security scanning, and documented rollback plans
- **Retrospective & Continuous Improvement** captures learnings through structured retrospectives and converts action items into improvements, reinforcing a culture of iterative learning

Quality is embedded throughout the process via unit tests, integration tests, end-to-end smoke tests, and security scanning in CI. Risk management is systematic—risks are identified during planning, assessed for impact and likelihood, and reviewed weekly using a simple Risk Register with mitigation plans. Communication is consistent and transparent: weekly syncs between PM and PdM, twice-weekly standups, monthly stakeholder updates, and ad-hoc escalations following a three-level escalation path (team-level triage → PM escalation to Product Lead → sponsor-level escalation). This commitment to documentation, clear roles, and continuous feedback creates a scalable foundation for delivering customer value while reducing single-person dependency and accelerating onboarding.

## Using This Library

Each document includes:
- Clear purpose and scope
- Step-by-step activities and checklists
- Templates for common artifacts (one-pagers, status reports, etc.)

Use the navigation above to find the guide relevant to your current project phase.

## Key Roles at a Glance

| Role | Primary Focus | Key Deliverables |
|------|---------------|------------------|
| **Product Manager** | Vision, prioritization, outcomes | Roadmap, backlog, success metrics |
| **Project Manager** | Delivery, schedule, risk, communication | Project plan, status updates, risk register |
| **Developer** | Implementation, quality, design | Code, tests, technical documentation |
| **QA/Testing** | Quality validation | Test plans, acceptance criteria verification |

## Getting Started

1. **For new projects**: Start with [Initiation](./octoacme-project-initiation.md) to validate the business case
2. **For planning activities**: Review [Project Planning](./octoacme-project-planning.md) for backlog and timeline guidance
3. **For day-to-day work**: Use [Execution & Tracking](./octoacme-execution-and-tracking.md) to manage standups, PRs, and progress
4. **For releases**: Follow [Release & Deployment](./octoacme-release-and-deployment.md) to ensure safe, observable deployments
5. **For continuous improvement**: Conduct retrospectives using [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)

Have questions or want to contribute to these docs? See the issue template at `.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml` to propose updates.
