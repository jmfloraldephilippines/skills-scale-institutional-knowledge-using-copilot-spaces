# OctoAcme Project Management Documentation

## Overview

OctoAcme's project management framework is built on five core principles:

- **Customer-first**: Prioritize customer value and usability in all decisions
- **Iterative Delivery**: Deliver small, testable increments to reduce risk and gather feedback
- **Clear Ownership**: Each project has a named Project Manager (PM) and Product Lead
- **Data-informed Decisions**: Measure impact and iterate based on evidence
- **Psychological Safety**: Encourage feedback, learning, and continuous improvement

This framework applies to all cross-functional projects that deliver product features, services, or integrations.

## Project Lifecycle Overview

OctoAcme projects follow a structured five-phase lifecycle:

```
Initiation → Planning → Execution & Tracking → Release & Deployment → Retrospective & CI
```

Each phase has clear objectives, deliverables, and decision gates to ensure alignment and reduce risk.

### Core Roles

- **Project Manager (PM)**: Coordinates delivery, schedules, risks, and communications
- **Product Manager (PdM)**: Defines outcomes, prioritizes backlog, and measures success
- **Developers**: Implement features, collaborate on design and testability
- **QA/Testing**: Validate quality and acceptance criteria
- **Stakeholders**: Provide inputs, feedback, and approvals

## Quick Navigation

### Project Lifecycle Phases

1. **[Project Initiation](octoacme-project-initiation.md)**
   - Validate business need and measurable outcome
   - Identify stakeholders and champions
   - Define success criteria and initial timeline
   - Create Project One-pager and make go/no-go decision

2. **[Project Planning](octoacme-project-planning.md)**
   - Break work into shippable increments
   - Create prioritized backlog with acceptance criteria
   - Estimate scope and define Definition of Done
   - Identify dependencies, risks, and release milestones

3. **[Execution & Tracking](octoacme-execution-and-tracking.md)**
   - Manage day-to-day delivery and progress
   - Run daily standups and weekly delivery syncs
   - Maintain project board and track metrics
   - Escalate blockers and risks systematically

4. **[Release & Deployment](octoacme-release-and-deployment.md)**
   - Standardize release processes and reduce deployment risk
   - Prepare pre-release requirements and smoke tests
   - Execute deployment with verified rollback plans
   - Announce releases and monitor for issues

5. **[Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)**
   - Capture learnings after sprints, releases, or milestones
   - Identify what went well and what could improve
   - Convert insights into actionable improvements
   - Measure impact and celebrate wins

### Cross-cutting Topics

- **[Project Management Overview](octoacme-project-management-overview.md)**
  - High-level framework, key artifacts, and communication cadence
  - Start here for a 10-minute introduction to OctoAcme's approach

- **[Risk Management & Communication](octoacme-risks-and-communication.md)**
  - Maintain risk registers and escalation paths
  - Communicate status, blockers, and incidents to stakeholders
  - Templates for weekly status updates and incident communication

- **[Roles & Personas](octoacme-roles-and-personas.md)**
  - Detailed descriptions of key roles and responsibilities
  - Communication patterns and goals for each persona

## Key Artifacts

Every OctoAcme project should maintain these core documents:

| Artifact | Purpose | Owned by |
|----------|---------|----------|
| Project Charter / One-pager | Align on problem, goal, and success metrics | PM + PdM |
| Backlog & Roadmap | Prioritized work and release timeline | PdM |
| Sprint/Iteration Backlog | Current iteration's work and status | PM |
| Risk Register | Identified risks, mitigation plans, and status | PM |
| Project Board | Visual workflow of work (Backlog → Done) | PM |
| Retrospective Notes | Learnings and action items for improvement | PM |

## Communication Cadence

- **Daily**: Team standups (15 min) — progress, blockers, dependencies
- **Weekly**: PM + PdM sync and delivery team standups
- **Weekly**: Risk register review and stakeholder updates
- **Sprint/Milestone**: Demo/review and retrospective (45–75 min)
- **Monthly**: Stakeholder updates and metrics review
- **Ad-hoc**: Escalations for blockers and incidents

## How to Use These Docs

### Getting Started
1. **New to OctoAcme?** Start with [Project Management Overview](octoacme-project-management-overview.md) for a comprehensive introduction
2. **Starting a project?** Follow the [Project Initiation Guide](octoacme-project-initiation.md) to validate and authorize work
3. **Need a template?** Look for checklists and templates in each phase document

### During Execution
- Reference the appropriate phase document as your project progresses
- Use checklists to standardize execution and ensure nothing is missed
- Keep the Project Charter, Risk Register, and Project Board updated
- Review the [Risk Management & Communication](octoacme-risks-and-communication.md) guide for escalation and status reporting

### After Delivery
- Run a retrospective using the [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) guide
- Convert learnings into process improvements
- Feed validated improvements back into these living documents

## Adding Content to These Docs

To propose updates, enhancements, or new content:

1. Use the **[Add Content to Project Management Process Docs](https://github.com/jmfloraldephilippines/skills-scale-institutional-knowledge-using-copilot-spaces/issues/new?template=add-update-content-to-process-docs.yml)** issue template
2. Describe the new content, why it's needed, and any suggested text
3. The team will review and incorporate validated improvements
4. This keeps our documentation current and responsive to team needs

## Document Index

```
docs/
├── README.md (this file)
├── octoacme-project-management-overview.md
├── octoacme-project-initiation.md
├── octoacme-project-planning.md
├── octoacme-execution-and-tracking.md
├── octoacme-release-and-deployment.md
├── octoacme-retrospective-and-continuous-improvement.md
├── octoacme-risks-and-communication.md
└── octoacme-roles-and-personas.md
```

---

**Last Updated**: 2026-07-16  
**Maintained by**: OctoAcme Project Management Team
