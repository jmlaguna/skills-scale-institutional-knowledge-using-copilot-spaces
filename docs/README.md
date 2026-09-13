# OctoAcme Project Management Docs

Welcome to OctoAcme's centralized project management documentation. These guides standardize how we run projects, define roles, manage risks, and deliver value to customers.

## Quick Overview

OctoAcme follows a **lifecycle-based approach** to project delivery:

1. **Initiation** - Validate the business case and align stakeholders
2. **Planning** - Break work into deliverables and identify dependencies
3. **Execution** - Build, test, and iterate with regular feedback
4. **Release** - Deploy to production with confidence and observability
5. **Retrospective** - Capture learnings and improve continuously

Our approach prioritizes customer value, iterative delivery, clear ownership, and psychological safety.

### Project Lifecycle & Workflows

OctoAcme's five-phase project lifecycle is gated by clear decision points and deliverables. During **Initiation**, the team validates the business need by creating a lightweight Project One-pager that captures the problem statement, SMART goals, success metrics, stakeholders, and initial risks. Once stakeholders align and the go/no-go decision is made, projects move into **Planning**, where work is broken into shippable increments with prioritized backlogs, acceptance criteria, and a Definition of Done. Throughout **Execution**, teams follow a structured rhythm of daily standups (15 min), weekly delivery syncs, and sprint-based iterations using GitHub Projects with standardized columns (Backlog, Ready, In Progress, In Review, QA, Done). Pull requests are kept small (≤400 lines when possible) and require at least one approval before merging. Before **Release**, all acceptance criteria must be met, CI/security scans must pass, and smoke tests must be prepared. Post-deployment, the team runs verification checks and communicates the release to stakeholders. Finally, **Retrospectives** are held after sprints, releases, or milestones to capture learnings and convert them into 2–3 prioritized action items.

### Core Roles & Responsibilities

OctoAcme operates with clearly defined roles to ensure accountability and ownership. **Project Managers (PMs)** coordinate delivery timelines, manage risks and dependencies, maintain project documentation, and facilitate stakeholder communication through weekly status updates and risk registers. **Product Managers (PdMs)** define what should be built by owning the product vision, prioritizing the backlog, and measuring outcomes through success metrics and user feedback. **Developers** implement features, write tests, participate in design reviews, and help identify technical risks. **QA/Testing teams** validate quality and acceptance criteria. This role clarity is reinforced by the principle that "each project has a named Project Manager and Product Lead," preventing confusion and ensuring consistent communication across the organization.

### Communication & Risk Management

Communication is structured and cadenced: weekly syncs between PM and PdM, twice-weekly standups for delivery teams, and monthly stakeholder updates with ad-hoc escalations as needed. Risk management follows a formal lifecycle—risks are identified during planning and execution, assessed for impact and likelihood, mitigated through actions and contingency plans, and monitored weekly. The organization maintains a simple Risk Register (ID, Description, Impact, Likelihood, Owner, Mitigation, Status) that feeds into weekly syncs. Escalation follows a three-level path: Level 1 (team-level triage in standups) → Level 2 (PM escalates to Product Lead and dependent teams) → Level 3 (sponsor-level for business-impacting issues). Status communication uses a standard template covering progress, next steps, risks/blockers, and decisions needed, with a single source of truth (project README or release documentation) to ensure transparency.

### Quality Assurance & Continuous Improvement

Quality is embedded throughout the delivery cycle. Teams implement **unit tests for new logic, integration tests where applicable, and end-to-end smoke tests for critical flows** before release. **Security scanning is integrated into CI**, and **manual QA validates feature acceptance when needed**. The team tracks velocity and burndown, monitors success metrics from the Project One-pager, and uses dashboards to track key signals (errors, latency, usage). Continuous improvement is formalized through retrospectives (45–75 minutes, conducted after sprints/milestones) that identify what went well, what could improve, and assign 2–3 action items with owners and due dates. These action items are added to the project backlog with clear success criteria, and their impact is measured and celebrated, embedding a culture of iterative learning into the organization's DNA.

## Documentation Index

### Core Guidance
- **[OctoAcme Project Management Overview](octoacme-project-management-overview.md)** - High-level introduction to roles, principles, and artifacts
- **[OctoAcme Roles and Personas](octoacme-roles-and-personas.md)** - Detailed responsibilities for PMs, PdMs, developers, and stakeholders

### Project Lifecycle
- **[Project Initiation Guide](octoacme-project-initiation.md)** - Steps to validate and authorize a new project
- **[Project Planning](octoacme-project-planning.md)** - Create actionable plans, backlogs, and release timelines
- **[Execution & Tracking](octoacme-execution-and-tracking.md)** - Day-to-day workflows, standups, and quality checks
- **[Release & Deployment Guide](octoacme-release-and-deployment.md)** - Standardized release process and rollback procedures
- **[Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)** - Capture learnings and iterate on processes

### Cross-Cutting Concerns
- **[Risk Management & Communication](octoacme-risks-and-communication.md)** - Risk registers, escalation paths, and stakeholder updates

## Getting Started by Project Stage

**Starting a new project?** Read in this order:
1. Project Management Overview (context)
2. Roles and Personas (understand team structure)
3. Project Initiation Guide (first steps)
4. Project Planning (detailed planning)

**Running a project?** Reference:
- Execution & Tracking (daily guidance)
- Risk Management & Communication (ongoing)

**Preparing to release?** Consult:
- Release & Deployment Guide (pre-release checklist)
- Risk Management & Communication (stakeholder updates)

**After a milestone or release?**
- Retrospective & Continuous Improvement (capture learnings)
