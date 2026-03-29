# OctoAcme Project Management Process Docs

This README provides an overview and entry point to all of OctoAcme's project management knowledge and process documentation. New team members should start here.

## OctoAcme Project Management Summary

OctoAcme project management follows these core principles and phases:

- **Customer-first:** Prioritize value and usability.
- **Iterative delivery:** Work delivered in small, testable increments.
- **Clear ownership:** Named Project Manager and Product Lead per project.
- **Data-informed decisions:** Metrics and feedback drive planning and improvement.
- **Psychological safety:** Feedback and learning are encouraged.

### Key Phases

1. **Initiation:** Problem/goal definition, stakeholder alignment, high-level timeline.
2. **Planning:** Scope, backlog, milestones, dependencies.
3. **Execution:** Progress tracking, delivery syncs, demos, QA/test, risk escalation.
4. **Release & Deployment:** Standardized checklists and rollback plans.
5. **Retrospective:** Continuous improvement and documenting learnings.

## Docs Table of Contents

| Document | Description | Required? |
|---|---|---|
| [Project Management Overview](octoacme-project-management-overview.md) | Core principles, roles, artifacts, and lifecycle | ✅ Minimum |
| [Project Initiation Guide](octoacme-project-initiation.md) | Checklist and template for starting a project | ✅ Minimum |
| [Project Planning](octoacme-project-planning.md) | Backlog, milestones, and sprint planning guidance | ✅ Minimum |
| [Execution & Tracking](octoacme-execution-and-tracking.md) | Day-to-day workflow, PR practices, QA, and escalation | ✅ Minimum |
| [Risk Management & Communication](octoacme-risks-and-communication.md) | Risk register, incident communication, and escalation paths | ✅ Minimum |
| [Release & Deployment Guide](octoacme-release-and-deployment.md) | Pre-release checklist, deployment steps, and rollback | ✅ Minimum |
| [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) | Retrospective format and continuous improvement tracking | ✅ Minimum |
| [Roles and Personas](octoacme-roles-and-personas.md) | Role definitions, responsibilities, and escalation contacts | 📘 Reference |

> **Minimum** docs must be reviewed and applied to every project. **Reference** docs provide supporting context and should be consulted as needed.

## Incident & Escalation Quick Reference

For incidents or blockers, use the following escalation path:

1. **Team-level triage** — raise in daily standup or async in team channel
2. **PM escalation** — PM notifies Product Lead and dependent teams
3. **Sponsor-level** — PM or Product Lead escalates to project sponsor for business-impacting issues
4. **Security incidents** — follow the security incident runbook and notify Security on-call immediately

For communication templates (status updates, incident summaries), see [Risk Management & Communication](octoacme-risks-and-communication.md).

## How to Use These Docs Collaboratively

- **Onboarding:** New team members should read the [Project Management Overview](octoacme-project-management-overview.md) and [Roles and Personas](octoacme-roles-and-personas.md) first.
- **Starting a project:** Work through the [Project Initiation Guide](octoacme-project-initiation.md) checklist before moving to planning.
- **Each phase has a checklist:** Use the checklist in each phase doc to confirm readiness before advancing.
- **Living documents:** These docs should be updated as processes evolve. Add them to `.copilot/` in your project repo for Copilot Spaces context.
- **Propose improvements:** Use the issue template in [`.github/ISSUE_TEMPLATE/`](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) to suggest additions, corrections, or new content for any process doc.

---

For details on how to contribute, update, or use these docs, see issue templates in `.github/ISSUE_TEMPLATE/`.
