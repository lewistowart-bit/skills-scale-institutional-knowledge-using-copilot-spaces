# OctoAcme — Ownership & Handoffs

## Purpose
Provide clear role ownership for key project artifacts and activities, define handoff checklists between roles, and document escalation/decision points to reduce ambiguity and improve accountability across the project lifecycle.

For full role definitions, see [Roles and Personas](octoacme-roles-and-personas.md).

---

## RACI Overview

**Key:** R = Responsible | A = Accountable | C = Consulted | I = Informed

| Artifact / Activity | PM | PdM | Scrum Master | Dev | QA | UX/UI | Tech Writer | BA | Release Mgr | Stakeholders |
|---|---|---|---|---|---|---|---|---|---|---|
| Project One-pager | R | A | I | C | I | C | I | C | I | C |
| Backlog creation & prioritisation | C | A | C | C | C | C | I | R | I | I |
| User stories & acceptance criteria | C | C | I | C | C | C | I | R/A | I | C |
| Definition of Done (DoD) | C | C | A | R | R | C | C | C | C | I |
| Sprint planning & commitment | I | C | A | R | R | I | I | C | I | I |
| Design specs & prototypes | I | C | I | C | C | A/R | I | C | I | I |
| Risk Register | A/R | C | C | C | C | I | I | C | I | I |
| Release plan & schedule | A | C | C | R | C | I | I | C | R | I |
| Release notes | I | C | I | C | C | I | R | I | A | I |
| QA sign-off | I | I | I | C | A/R | I | I | C | C | I |
| Stakeholder updates | R | C | I | I | I | I | C | I | C | A |
| Post-release retrospective | A | C | R | C | C | C | I | C | C | I |

---

## Handoff Checklists

### 1. Product Manager → Developer (PdM→Dev)
_Triggered when a backlog item is moved to "Ready for Development"._

- [ ] User story is written with clear acceptance criteria
- [ ] Business Analyst has validated requirements against stakeholder needs
- [ ] UX/UI design assets and specifications are attached (if UI work is involved)
- [ ] Dependencies on other teams or services are identified and noted
- [ ] Technical risks or constraints are flagged in the ticket
- [ ] DoD criteria for this item are understood by the Developer

### 2. Design → Developer (UX/UI→Dev)
_Triggered when a design is approved and handed off for implementation._

- [ ] High-fidelity design files are published and shared (e.g., Figma link)
- [ ] Interaction and state specifications are documented (hover, error, empty states)
- [ ] Accessibility requirements are noted (colour contrast, ARIA labels, keyboard nav)
- [ ] Design assets (icons, images) are exported in required formats
- [ ] Developer has reviewed designs and raised any feasibility concerns
- [ ] Designer is available for implementation questions during the sprint

### 3. Developer → QA (Dev→QA)
_Triggered when a PR is merged and the feature is deployed to a test environment._

- [ ] PR is merged and CI is green
- [ ] Feature is deployed to the test/staging environment
- [ ] Developer has completed a self-review against acceptance criteria
- [ ] Unit and integration tests are passing
- [ ] Any known limitations or deferred items are documented in the ticket
- [ ] Test environment configuration or data setup notes are provided if needed

### 4. QA → Release Manager (QA→Release)
_Triggered when QA testing is complete and the release window is approaching._

- [ ] All acceptance criteria are verified and marked as passed
- [ ] All critical and high-severity defects are resolved or have accepted deferrals
- [ ] Regression tests have been run and passed
- [ ] QA sign-off is documented in the release ticket or project board
- [ ] Known issues for the release notes are communicated to the Technical Writer
- [ ] Release Manager is notified of go/no-go decision

### 5. Release Manager → Stakeholders (Release→Stakeholders)
_Triggered after a successful production deployment._

- [ ] Deployment completed and post-deploy verification passed
- [ ] Release notes are published and contain: summary, notable changes, migration steps (if any), known issues
- [ ] Stakeholder communication sent (email, Slack, or agreed channel)
- [ ] Support team is briefed on changes that may generate user queries
- [ ] Monitoring dashboards checked for anomalies post-release
- [ ] Rollback plan confirmed as no longer needed (or incident initiated if required)

---

## Escalation & Decision Points

| Situation | First Owner | Escalation Path | Decision Maker |
|---|---|---|---|
| Requirement ambiguity | Business Analyst | BA → PdM → Stakeholder | Product Manager |
| Scope change request mid-sprint | Scrum Master | SM → PM → PdM | Product Manager + Project Manager |
| Blocked backlog item (technical) | Developer | Dev → PM (daily standup) → PdM if priority needed | Project Manager |
| QA go/no-go dispute | QA | QA → Release Manager → PM | Project Manager |
| Design–dev feasibility conflict | UX/UI Designer | Designer → Developer → PM | Project Manager |
| Release date risk | Release Manager | Release Mgr → PM → Stakeholders | Project Manager + Sponsor |
| Security or compliance concern | Developer / QA | Dev/QA → PM → Security on-call | Security Lead / Sponsor |
| Post-release critical incident | Release Manager | Release Mgr → PM → on-call Engineer | Incident Commander (PM or Release Mgr) |
