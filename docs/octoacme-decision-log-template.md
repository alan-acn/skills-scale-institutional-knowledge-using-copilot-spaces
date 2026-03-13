# OctoAcme — Decision Log Template

## Purpose
Track significant project decisions, their rationale, owners, and outcomes. The Decision Log ensures decisions are visible, traceable, and available for future reference — reducing repeated discussions and onboarding friction.

**Owner:** Project Manager (PM) maintains the log; Engineering Manager/Tech Lead owns technical decisions
**Updated by:** PM, PdM, Engineering Manager/Tech Lead, or any decision maker
**Reviewed:** Referenced during retrospectives and in weekly status updates

---

## Decision Log Table

| ID | Date | Decision | Context / Options Considered | Rationale | Decision Maker(s) | Status | Impact / Follow-up |
|---|---|---|---|---|---|---|---|
| D-001 | YYYY-MM-DD | [Short description of the decision] | [Options that were considered] | [Why this option was chosen] | [Name(s) / Role(s)] | Decided / Superseded / Under Review | [What changed, what to watch] |
| D-002 | | | | | | | |

---

## Decision Statuses
- **Decided:** Decision has been made and is in effect
- **Under Review:** Decision is being evaluated; not yet finalized
- **Superseded:** Decision was overridden by a later decision (link to superseding entry)

---

## When to Log a Decision
Log decisions that are:
- Significant in scope (architecture, technology choice, scope change, budget)
- Likely to affect multiple team members or stakeholders
- Difficult or costly to reverse
- Questioned or unclear in retrospect — pre-empt confusion by logging now

Do **not** log routine day-to-day execution choices (e.g., variable naming, minor implementation details).

---

## Example Entry

| ID | Date | Decision | Context / Options Considered | Rationale | Decision Maker(s) | Status | Impact / Follow-up |
|---|---|---|---|---|---|---|---|
| D-003 | 2025-02-10 | Adopt PostgreSQL for project data store | Options: PostgreSQL, MySQL, DynamoDB | Team expertise; compliance requirements; relational model fits data structure | Engineering Manager + PdM | Decided | Update infra docs; DevOps to provision RDS instance |

---

## Linking Decisions
- Reference decision IDs in PR descriptions, design docs, and the Risk Register
- Link major decisions in the relevant [Weekly Status Update](octoacme-weekly-status-template.md) under "Decisions Made"
