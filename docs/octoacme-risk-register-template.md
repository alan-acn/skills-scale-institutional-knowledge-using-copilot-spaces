# OctoAcme — Risk Register Template

## Purpose
Provide a reusable template for tracking project risks, their likelihood, impact, owners, and mitigation actions throughout the project lifecycle.

**Owner:** Project Manager (PM)
**Reviewed by:** PM, PdM, Engineering Manager/Tech Lead
**Review cadence:** Weekly (at weekly sync); additionally after any significant project change

---

## Risk Register Table

| ID | Description | Category | Impact | Likelihood | Exposure | Owner | Mitigation Plan | Contingency | Status | Last Updated |
|---|---|---|---|---|---|---|---|---|---|---|
| R-001 | [Risk description] | [Technical / Schedule / Resource / External / Security] | High/Med/Low | High/Med/Low | High/Med/Low | [Name/Role] | [Action to reduce likelihood or impact] | [Action if risk occurs] | Open/Mitigated/Closed | YYYY-MM-DD |
| R-002 | | | | | | | | | | |

### Exposure Matrix
| | **High Likelihood** | **Med Likelihood** | **Low Likelihood** |
|---|---|---|---|
| **High Impact** | 🔴 Critical | 🔴 High | 🟡 Medium |
| **Med Impact** | 🔴 High | 🟡 Medium | 🟢 Low |
| **Low Impact** | 🟡 Medium | 🟢 Low | 🟢 Low |

---

## Risk Categories
- **Technical:** Architecture, integration, or technology uncertainty
- **Schedule:** Timeline, dependency, or resource availability risks
- **Resource:** Staffing, skill gaps, or budget constraints
- **External:** Third-party, vendor, regulatory, or market risks
- **Security:** Security vulnerabilities, compliance, or data risks

---

## Risk Lifecycle

1. **Identify** — Capture risks during planning and on an ongoing basis
2. **Assess** — Assign Impact, Likelihood, and Exposure; assign an Owner
3. **Mitigate** — Define Mitigation Plan and Contingency actions
4. **Monitor** — Review at weekly sync; update Status and Last Updated date
5. **Close** — Mark as `Mitigated` or `Closed` once the risk no longer applies

---

## Review Cadence
- **Weekly:** PM reviews open risks at the weekly delivery sync; updates status and notes
- **At major milestones:** Full risk review with PdM, Engineering Manager/Tech Lead, and relevant stakeholders
- **After incidents:** Add new risks surfaced by the incident; link to retrospective action items
- **At release gate:** Review all open risks as part of the [Release Readiness Checklist](octoacme-release-readiness-checklist.md)

---

## Example Entry

| ID | Description | Category | Impact | Likelihood | Exposure | Owner | Mitigation Plan | Contingency | Status | Last Updated |
|---|---|---|---|---|---|---|---|---|---|---|
| R-003 | Third-party API deprecation may break core integration | External | High | Med | 🔴 High | PM + Lead Dev | Monitor vendor announcements; evaluate fallback API | Implement abstraction layer; switch to alternative | Open | 2025-01-15 |
