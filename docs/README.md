# OctoAcme Project Management Documentation

Welcome to the OctoAcme Project Management process documentation. This folder contains comprehensive guides for managing projects from initiation through delivery and continuous improvement.

## Quick Start

New to OctoAcme projects? Start with the [Project Management Overview](octoacme-project-management-overview.md) for a concise introduction to our approach, roles, and key artifacts.

## OctoAcme Project Management Overview

OctoAcme follows a structured, customer-focused approach to project delivery built on five core principles:

- **Customer-first**: Prioritize customer value and usability
- **Iterative delivery**: Deliver small, testable increments
- **Clear ownership**: Each project has a named Project Manager (PM) and Product Lead
- **Data-informed decisions**: Measure impact and iterate based on evidence
- **Psychological safety**: Encourage feedback and learning

Our projects are coordinated by cross-functional teams with clearly defined roles—Product Managers define outcomes and priorities, Project Managers coordinate delivery and risk, Developers build and test features, and Stakeholders provide direction and approvals. We maintain a consistent communication cadence with daily standups, weekly syncs, and regular retrospectives to ensure alignment and continuous improvement.

## Project Lifecycle

OctoAcme follows a structured project lifecycle across five key phases:

### 1. Initiation
**Goal**: Validate business needs, align stakeholders, and decide go/no-go for planning

- [Project Initiation Guide](octoacme-project-initiation.md)
  - Confirm business need and measurable outcome
  - Identify stakeholders and champions
  - Create a Project One-pager with problem statement, goals, and success metrics
  - Establish high-level timeline and key milestones
  - Decision gate: Move to planning when success metrics are clear and stakeholders align

### 2. Planning
**Goal**: Break work into shippable increments and create the delivery roadmap

- [Project Planning](octoacme-project-planning.md)
  - Conduct project kickoff with stakeholders and delivery team
  - Create a prioritized backlog with clear acceptance criteria
  - Estimate scope using t-shirt sizing or story points
  - Define Definition of Done (DoD)
  - Identify dependencies and integration points
  - Create release plan and milestone map

### 3. Execution & Tracking
**Goal**: Manage day-to-day delivery, maintain team rhythm, and track progress

- [Execution & Tracking](octoacme-execution-and-tracking.md)
  - Execute daily standups (15 min) and weekly delivery syncs
  - Use the project board (GitHub Projects) with columns: Backlog, Ready, In Progress, In Review, QA, Done
  - Follow the Pull Request workflow: small PRs, issue links, automated CI/lint, and minimum one approval
  - Ensure quality through unit tests, integration tests, and smoke tests
  - Track velocity, burndown, and delivery metrics
  - Escalate blockers through structured levels: team triage → PM → Product Lead → Sponsor

### 4. Release & Deployment
**Goal**: Standardize production releases and minimize deployment risk

- [Release & Deployment Guide](octoacme-release-and-deployment.md)
  - Categorize releases as Patch, Minor, or Major
  - Verify pre-release requirements: acceptance criteria met, CI passing, security scans complete, release notes drafted
  - Execute deployment checklist: staging tests, production deploy, post-deploy verification, stakeholder announcement
  - Maintain rollback and incident playbooks for rapid response to issues

### 5. Close & Continuous Improvement
**Goal**: Capture learnings and drive actionable improvements

- [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)
  - Hold retrospectives after each sprint, release, or important milestone
  - Structure: What went well, what could improve, and action items with owners and due dates
  - Prioritize 2–3 top action items to avoid overload
  - Track improvements and measure impact
  - Build a continuous improvement culture with iterative changes

## Cross-Cutting Guidance

### Risk Management & Communication
- [Risk Management & Communication](octoacme-risks-and-communication.md)
  - Maintain a Risk Register with ID, Description, Impact, Likelihood, Owner, Mitigation, and Status
  - Risk lifecycle: Identify → Assess → Mitigate → Monitor
  - Stakeholder communication with templates for status updates and incident response
  - Clear escalation paths for different issue types

### Roles & Personas
- [Roles and Personas](octoacme-roles-and-personas.md)
  - **Project Managers**: Coordinate delivery, manage schedules, risks, and communications
  - **Product Managers**: Define outcomes, prioritize backlog, and measure success
  - **Developers**: Implement features and collaborate on design and testability
  - **QA/Testing**: Validate quality and acceptance criteria
  - **Stakeholders**: Provide inputs and approvals

## How to Use These Docs

1. **Start here**: New team members should read the [Project Management Overview](octoacme-project-management-overview.md)
2. **Follow the lifecycle**: Use the relevant phase guide at each stage of your project
3. **Keep your charter updated**: Maintain your Project Charter in your project repo
4. **Add Copilot context**: Reference these docs in `.copilot/` to give Copilot Spaces context-specific guidance
5. **Contribute improvements**: Submit updates using the [Add Content to Project Management Process Docs](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) issue template

## Document Index

| Document | Phase | Purpose |
|----------|-------|---------|
| [Project Management Overview](octoacme-project-management-overview.md) | — | High-level introduction to OctoAcme approach and roles |
| [Project Initiation Guide](octoacme-project-initiation.md) | Initiation | Validate needs and align stakeholders |
| [Project Planning](octoacme-project-planning.md) | Planning | Create backlog and delivery roadmap |
| [Execution & Tracking](octoacme-execution-and-tracking.md) | Execution | Manage day-to-day delivery and progress |
| [Risk Management & Communication](octoacme-risks-and-communication.md) | Cross-cutting | Manage risks and stakeholder communications |
| [Release & Deployment Guide](octoacme-release-and-deployment.md) | Release | Standardize production releases |
| [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) | Close | Capture learnings and drive improvements |
| [Roles and Personas](octoacme-roles-and-personas.md) | Cross-cutting | Define project roles and responsibilities |

---

**Last Updated**: October 2026  
**Maintained By**: OctoAcme Project Management Team
