# OctoAcme — Persona Hand-off Checklist & Requirements-Gathering Worksheet

> Added in response to [issue #4](https://github.com/XabiAbaunz/skills-scale-institutional-knowledge-using-copilot-spaces/issues/4).
> This template standardizes cross-role hand-offs and requirements-gathering steps to reduce ambiguity and improve onboarding for new team members.
>
> For full role definitions, see [`octoacme-roles-and-personas.md`](octoacme-roles-and-personas.md).

---

## 1. Discovery → Planning Hand-off (Business Analyst to Product Manager)

Use this checklist when transferring requirements from a Business Analyst discovery phase into the planning backlog.

- [ ] Business requirements document (BRD) or user story set completed and shared
- [ ] Acceptance criteria drafted for each major requirement
- [ ] Assumptions and constraints documented
- [ ] Out-of-scope items explicitly listed
- [ ] Stakeholder sign-off on requirements captured (email, meeting notes, or comment)
- [ ] Open questions or ambiguities flagged for resolution before sprint planning

---

## 2. Design → Development Hand-off (UX Designer to Developers)

Use this checklist when design artifacts are ready for implementation.

- [ ] Wireframes or high-fidelity mockups shared in agreed design tool (link: __________)
- [ ] User flows and edge cases documented
- [ ] Accessibility requirements noted (WCAG level, contrast ratios, keyboard nav)
- [ ] Design tokens / component references aligned with design system
- [ ] Open design questions resolved with Product Manager
- [ ] Developers and UX Designer have completed a design walk-through
- [ ] Usability acceptance criteria added to relevant backlog items

---

## 3. Sprint Planning Readiness Check (Scrum Master)

Use this checklist before committing work into a sprint.

- [ ] Backlog items meet the Definition of Ready (clear title, description, acceptance criteria, estimate)
- [ ] Dependencies identified and mitigated or accepted
- [ ] Team capacity confirmed (leave, on-call rotations, etc.)
- [ ] UX design assets available for any UI-facing items
- [ ] Business Analyst available for clarification questions during the sprint
- [ ] Data instrumentation requirements included in relevant stories
- [ ] Sprint goal articulated and agreed by the team

---

## 4. Feature Delivery → Analytics Hand-off (Developers to Data Analyst)

Use this checklist when a feature ships and analytics tracking needs to be verified.

- [ ] Instrumentation implemented per agreed spec (events, properties, naming convention)
- [ ] Data Analyst confirmed tracking is firing correctly in staging/production
- [ ] Dashboard or report updated to include new feature metrics
- [ ] Baseline metrics captured before release (for before/after comparison)
- [ ] Success metric thresholds defined and communicated to Project Manager and Product Manager

---

## 5. Release → Stakeholder Communication Hand-off (Project Manager)

Use this checklist to ensure stakeholders are informed after release.

- [ ] Release notes drafted and reviewed (see [`octoacme-release-and-deployment.md`](octoacme-release-and-deployment.md))
- [ ] Business Analyst validates delivered solution against original requirements
- [ ] UX Designer confirms any UI changes match approved designs
- [ ] Data Analyst confirms analytics are live and metrics are being tracked
- [ ] Stakeholder announcement sent (email, Slack, or agreed channel)
- [ ] Known issues or follow-up items logged in the backlog

---

## 6. Business Analyst Requirements-Gathering Worksheet

Use this worksheet to structure requirements discovery sessions with stakeholders.

### Project / Feature Name
> _(e.g., "Self-service billing portal")_

### Business Problem Statement
> _(Describe the problem stakeholders are experiencing and why it needs to be solved.)_

### Stakeholders Consulted
| Name | Role | Date Consulted |
|------|------|----------------|
|      |      |                |

### Business Requirements
| ID  | Requirement Description | Priority (MoSCoW) | Acceptance Criteria | Owner |
|-----|------------------------|-------------------|---------------------|-------|
| BR-1 |                        |                   |                     |       |
| BR-2 |                        |                   |                     |       |

### Assumptions
- 
- 

### Constraints
- 
- 

### Out of Scope
- 
- 

### Open Questions
| # | Question | Owner | Due Date | Resolution |
|---|----------|-------|----------|------------|
| 1 |          |       |          |            |

### Sign-off
| Stakeholder | Date | Notes |
|-------------|------|-------|
|             |      |       |

---

_Last updated: refer to git history. For questions about this template, see the project's process documentation in `docs/` or contact the Project Manager._
