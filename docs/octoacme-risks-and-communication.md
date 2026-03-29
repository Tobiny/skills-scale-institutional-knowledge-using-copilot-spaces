# OctoAcme — Risk Management & Communication

## Purpose
Explain how to identify, manage, and communicate risks and dependencies.

## Risk Register
Maintain a simple table with:
- ID
- Description
- Impact (High/Med/Low)
- Likelihood (High/Med/Low)
- Owner
- Mitigation plan
- Status

## Risk Lifecycle
- Identify: during planning and ongoing execution
- Assess: estimate impact and likelihood
- Mitigate: reduced via actions, contingency plans
- Monitor: review at weekly syncs and update status

## Stakeholder Communication
- Identify stakeholder groups and communication needs (e.g., engineering, sales, support)
- Provide regular updates (weekly or milestone-based)
- Use a single source of truth (project README or release doc) for status

## Communication Templates

### Weekly Status Template
- Progress this week:
- Next steps:
- Risks & blockers:
- Ask / decisions needed:

### Incident Communication Template
- **Triage summary:** Brief description of the incident and its impact
- **Actions being taken:** What is actively being done to resolve it
- **Expected timeline:** Estimated resolution time
- **Escalation status:** Who has been notified (see Escalation Paths below)
- **Post-incident blameless retrospective:** Scheduled date and owner

## Escalation Paths

All team members should be familiar with these escalation paths:

| Level | Trigger | Who to Notify |
|---|---|---|
| Level 1 | Team-level blocker | Raise in daily standup; team triages |
| Level 2 | Cross-team dependency or unresolved blocker | PM escalates to Product Lead and dependent teams |
| Level 3 | Business-impacting issue or sponsor decision needed | PM or Product Lead escalates to project sponsor |
| Security | Any security incident | Follow the security incident runbook; notify Security on-call immediately |

> **Note:** For incidents during a release, also trigger the [Release & Deployment rollback playbook](octoacme-release-and-deployment.md).

## Risk & Communication Checklist
- [ ] Risk register created and shared with the team
- [ ] All identified risks have an owner and mitigation plan
- [ ] Stakeholder communication plan documented
- [ ] Escalation paths communicated to team at project kickoff
- [ ] Weekly syncs include a risk register review
- [ ] Incident communication template ready and accessible to on-call team members
