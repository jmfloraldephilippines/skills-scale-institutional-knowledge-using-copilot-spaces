# OctoAcme Project Management Documentation

## Overview

OctoAcme's project management framework is built on **five core principles** that guide how we run cross-functional projects:

- **Customer-first**: Prioritize customer value and usability
- **Iterative delivery**: Deliver small, testable increments
- **Clear ownership**: Each project has named Project Manager (PM) and Product Lead
- **Data-informed decisions**: Measure impact and iterate based on evidence
- **Psychological safety**: Encourage feedback and learning

This documentation provides a comprehensive guide to how OctoAcme initiates, plans, executes, releases, and improves projects. It's designed to help new team members get up to speed quickly and serve as a reference for ongoing project management activities.

---

## Quick Start

**New to OctoAcme PM?** Start here:
1. Read the [Project Management Overview](octoacme-project-management-overview.md) (10 min)
2. Reference specific phase docs as your project progresses
3. Use checklists and templates to standardize execution

---

## Project Lifecycle Phases

OctoAcme projects follow a structured five-phase lifecycle:

### 1. [Project Initiation](octoacme-project-initiation.md)
**When**: Starting a new project idea or feature proposal  
**Purpose**: Validate business need, align stakeholders, and authorize work  
**Key Deliverables**: Project One-pager, stakeholder list, high-level timeline, risk list

### 2. [Project Planning](octoacme-project-planning.md)
**When**: After initiation approval  
**Purpose**: Turn approved initiatives into actionable plans and backlogs  
**Key Deliverables**: Prioritized backlog, release plan, Definition of Done, risk register

### 3. [Execution & Tracking](octoacme-execution-and-tracking.md)
**When**: During active development and delivery  
**Purpose**: Manage day-to-day execution and track progress toward milestones  
**Key Activities**: Daily standups, weekly syncs, PR reviews, quality gates, progress tracking

### 4. [Release & Deployment](octoacme-release-and-deployment.md)
**When**: Ready to ship to production  
**Purpose**: Standardize release processes to reduce risk and improve observability  
**Key Activities**: Pre-release checklist, smoke tests, deployment, rollback playbook

### 5. [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)
**When**: After each sprint, release, or important milestone  
**Purpose**: Capture learnings and convert them into actionable improvements  
**Key Activities**: Retrospective meeting, action item tracking, impact measurement

---

## Cross-Cutting Topics

### [Project Management Overview](octoacme-project-management-overview.md)
High-level framework overview including:
- Core roles (PM, Product Manager, Developers, QA, Stakeholders)
- Key artifacts (Charter, Roadmap, Backlog, Risk Register)
- Communication cadence
- Lifecycle summary

### [Risk Management & Communication](octoacme-risks-and-communication.md)
Guidance on identifying and managing risks including:
- Risk register structure and lifecycle
- Stakeholder communication templates
- Escalation paths
- Incident communication playbooks

### [Roles & Personas](octoacme-roles-and-personas.md)
Detailed definitions of typical roles and responsibilities:
- Developers
- Product Managers
- Project Managers
- How to use personas in exercises and scenarios

---

## Key Artifacts & Templates

Throughout the project lifecycle, you'll work with these key artifacts:

| Artifact | Phase | Purpose |
|----------|-------|---------|
| Project One-pager | Initiation | Define problem, goal, success metrics, stakeholders |
| Risk Register | Planning & Ongoing | Track risks, impact, mitigation strategies |
| Prioritized Backlog | Planning | Organize work into shippable increments |
| Definition of Done | Planning | Establish quality standards and acceptance |
| Sprint/Iteration Plan | Execution | Time-boxed deliverables with clear ownership |
| Risk Register (Updated) | Execution & Ongoing | Monitor and update risk status weekly |
| Release Notes | Release | Communicate changes to stakeholders |
| Retrospective Notes | Closure | Document learnings and action items |

---

## Communication Cadence

- **Daily**: Team standups (15 min) — progress, blockers, dependencies
- **Weekly**: PM + Product Lead sync; delivery team standups (2x week or as agreed)
- **Bi-weekly/Monthly**: Stakeholder updates and demos
- **As-needed**: Escalations, incident response, ad-hoc alignment

---

## Core Roles at a Glance

| Role | Primary Responsibility | Key Activities |
|------|----------------------|-----------------|
| **Project Manager** | Coordinate delivery, manage schedules, risks, communications | Planning, standups, status reporting, risk management, escalation |
| **Product Manager** | Define outcomes, prioritize backlog, measure success | Roadmap setting, acceptance criteria, metrics tracking |
| **Developers** | Implement features, collaborate on design and testing | Coding, code review, testing, design participation |
| **QA/Testing** | Validate quality and acceptance criteria | Test planning, manual QA, test automation, acceptance sign-off |
| **Stakeholders** | Provide inputs, approvals, and business context | Decision-making, requirement input, progress review |

*See [Roles & Personas](octoacme-roles-and-personas.md) for detailed descriptions.*

---

## How to Use These Docs

1. **First time on a project?**
   - Start with the [Project Management Overview](octoacme-project-management-overview.md)
   - Skim the phase that matches your current project state

2. **Running a specific activity?** (e.g., sprint planning, release)
   - Jump to the relevant phase doc
   - Use the checklists and templates provided

3. **Scaling or improving processes?**
   - Review the [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) guide
   - Submit process document updates via the [Add Content to Project Management Process Docs](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) issue template

4. **Managing risks or stakeholders?**
   - Use [Risk Management & Communication](octoacme-risks-and-communication.md) for templates and escalation paths

5. **Onboarding a new team member?**
   - Share this README as your starting point
   - Point them to role-specific sections (e.g., Developers should review [Execution & Tracking](octoacme-execution-and-tracking.md))

---

## Continuous Improvement

OctoAcme's processes evolve based on team feedback and learnings. To contribute updates or improvements:

1. **Identify a gap or improvement** in an existing process doc
2. **Create an issue** using the [Add Content to Project Management Process Docs](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) template
3. **Submit a pull request** with proposed changes
4. **Gather feedback** from the PM, Product Lead, and delivery team
5. **Merge and communicate** the update

---

## Document Index

| Document | Purpose | Best For |
|----------|---------|----------|
| [octoacme-project-management-overview.md](octoacme-project-management-overview.md) | Framework overview, roles, artifacts | Quick introduction, onboarding |
| [octoacme-project-initiation.md](octoacme-project-initiation.md) | Project validation and authorization | Starting new projects |
| [octoacme-project-planning.md](octoacme-project-planning.md) | Planning, estimation, risk management | Project kickoff, release planning |
| [octoacme-execution-and-tracking.md](octoacme-execution-and-tracking.md) | Day-to-day execution, quality, metrics | Active development, standups |
| [octoacme-release-and-deployment.md](octoacme-release-and-deployment.md) | Release processes, deployment checklists | Preparing for release, rollback |
| [octoacme-retrospective-and-continuous-improvement.md](octoacme-retrospective-and-continuous-improvement.md) | Retrospectives, action items, learnings | Post-project review, improvement tracking |
| [octoacme-risks-and-communication.md](octoacme-risks-and-communication.md) | Risk management, escalation, communication | Risk management, stakeholder updates |
| [octoacme-roles-and-personas.md](octoacme-roles-and-personas.md) | Role definitions and responsibilities | Understanding team structure, exercises |

---

## Questions or Feedback?

If you have questions about these processes or ideas for improvements:
- Ask in your team's standup or sync meeting
- Create an issue using the process docs update template
- Reach out to your Project Manager or Product Lead

---

**Last Updated**: 2026-07-16  
**Maintained By**: OctoAcme Project Management Team
