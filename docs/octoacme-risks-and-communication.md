# OctoAcme — Risk Management & Communication

## Purpose
Explain how to identify, manage, and communicate risks and dependencies.

## Risk Register
Maintain a structured record of risks using the [Risk Register Template](octoacme-risk-register-template.md).

**Owner:** Project Manager (PM)
**Review cadence:** Weekly at delivery sync; full review at major milestones and release gates

Key fields to track per risk:
- ID, Description, Category
- Impact (High/Med/Low), Likelihood (High/Med/Low), Exposure
- Owner, Mitigation plan, Contingency
- Status (Open/Mitigated/Closed), Last Updated

## Risk Lifecycle
- **Identify:** during planning and ongoing execution
- **Assess:** estimate impact and likelihood; assign Owner
- **Mitigate:** reduce via actions, contingency plans
- **Monitor:** review at weekly syncs and update status
- **Close:** mark Mitigated or Closed when no longer applicable

## Stakeholder Communication
- Identify stakeholder groups and communication needs (e.g., engineering, sales, support)
- Publish weekly [Project Status Updates](octoacme-weekly-status-template.md) — owned by PM
- Use a single source of truth (project README or release doc) for status
- Log key decisions in the [Decision Log](octoacme-decision-log-template.md)

## Communication Templates

### Weekly Status Update
Use the [Weekly Status Update Template](octoacme-weekly-status-template.md) for consistent stakeholder updates:
- Status indicator (🟢 On Track / 🟡 At Risk / 🔴 Off Track)
- Progress this week
- Next steps
- Risks & blockers
- Decisions needed / asks

### Incident Communication
- Triage summary
- Actions being taken
- Expected timeline
- Post-incident blameless retrospective scheduled

## Escalation Paths
- Team-level → PM → Product Lead (PdM) → Sponsor/Stakeholder
- For security incidents, follow the security incident runbook and notify Security on-call
