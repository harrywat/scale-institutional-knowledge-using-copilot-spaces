# OctoAcme Cross-functional Handoff Checklist

Use this checklist at each major phase transition to confirm that all artifacts, approvals, and ownership transfers are complete before the next phase begins. Adapt it to your project's size and context.

---

## How to Use

1. At the start of each transition, assign an **owner** for the handoff (typically the Project Manager).
2. Work through the relevant section below and tick each item when complete.
3. If an item is not applicable, mark it `N/A` with a brief note.
4. Obtain sign-off from the **Accepting Role** before marking the handoff done.

---

## Handoff 1 — Requirements → Design

**Handing off:** Business Analyst / Product Manager  
**Accepting:** UX Designer

### Checklist

- [ ] User stories written with clear, testable acceptance criteria
- [ ] Process flows or journey maps available for all in-scope features
- [ ] Out-of-scope items documented and agreed upon
- [ ] Known constraints (technical, legal, brand) communicated to UX Designer
- [ ] Relevant user research findings or customer data shared
- [ ] Stakeholder sign-off on requirements obtained (or explicitly deferred with rationale)
- [ ] Glossary / terminology guide shared to ensure shared language
- [ ] Questions list reviewed — all blockers resolved or flagged

**Artifacts to hand over**

| Artifact | Owner | Location |
|----------|-------|----------|
| User stories / backlog | Business Analyst / PdM | Project backlog |
| Acceptance criteria | Business Analyst | User stories |
| Process flow diagrams | Business Analyst | Project repo / wiki |
| Research findings | Product Manager | Shared drive / wiki |

**Sign-off**

| Name | Role | Date |
|------|------|------|
| | UX Designer | |
| | Product Manager | |

---

## Handoff 2 — Design → Implementation

**Handing off:** UX Designer  
**Accepting:** Developers

### Checklist

- [ ] Final mockups / prototypes shared in agreed tool (e.g., Figma, design system)
- [ ] All user flows and edge-case states documented (empty states, errors, loading)
- [ ] Interaction and animation specifications included
- [ ] Accessibility requirements noted (WCAG level, color contrast, keyboard nav)
- [ ] Design assets exported and accessible (icons, images, tokens)
- [ ] Responsive breakpoints specified if applicable
- [ ] Design Q&A session held with Developers; open questions resolved
- [ ] Design approved by Product Manager before handoff

**Artifacts to hand over**

| Artifact | Owner | Location |
|----------|-------|----------|
| Final mockups / prototypes | UX Designer | Design tool link |
| Design spec / annotations | UX Designer | Design tool / wiki |
| Exported assets | UX Designer | Shared asset library |
| Interaction notes | UX Designer | Design tool / wiki |

**Sign-off**

| Name | Role | Date |
|------|------|------|
| | Lead Developer | |
| | UX Designer | |

---

## Handoff 3 — Implementation → QA

**Handing off:** Developers  
**Accepting:** QA Lead

### Checklist

- [ ] All in-scope stories implemented and code merged to the QA branch
- [ ] Unit and integration tests passing in CI
- [ ] Known defects or deferred scope listed with status
- [ ] Test environment provisioned and accessible (coordinate with DevOps Engineer)
- [ ] Test data / seed data prepared
- [ ] Build deployed to QA environment and smoke-tested by Developer
- [ ] Acceptance criteria reviewed with QA Lead before testing begins
- [ ] Feature flags or toggles documented if applicable
- [ ] Release notes draft available for QA review

**Artifacts to hand over**

| Artifact | Owner | Location |
|----------|-------|----------|
| QA build / deployed environment | DevOps Engineer | Environment URL |
| Known-issues list | Developer | Bug tracker |
| Release notes draft | Project Manager | Project wiki |
| Test data guide | Developer | Project repo / wiki |

**Sign-off**

| Name | Role | Date |
|------|------|------|
| | QA Lead | |
| | Lead Developer | |

---

## Handoff 4 — QA → Release

**Handing off:** QA Lead  
**Accepting:** DevOps Engineer / Project Manager

### Checklist

- [ ] All test cases executed; test summary report complete
- [ ] No open Severity-1 or Severity-2 defects (or exceptions explicitly approved)
- [ ] Open defects triaged with agreed dispositions (fix now / defer / accept)
- [ ] Acceptance criteria signed off by Product Manager
- [ ] Performance and security tests completed (if in scope) with results shared
- [ ] Accessibility checks completed
- [ ] Release notes finalized and reviewed by stakeholders
- [ ] Go/no-go decision recorded with attendees and outcome

**Artifacts to hand over**

| Artifact | Owner | Location |
|----------|-------|----------|
| Test summary report | QA Lead | Project wiki / shared drive |
| Defect list with dispositions | QA Lead | Bug tracker |
| QA sign-off record | QA Lead | Project wiki |
| Finalized release notes | Project Manager | Project wiki |

**Sign-off**

| Name | Role | Date |
|------|------|------|
| | Product Manager | |
| | QA Lead | |
| | Project Manager | |

---

## Handoff 5 — Release → Customer Enablement

**Handing off:** Project Manager / DevOps Engineer  
**Accepting:** Customer Success Manager

### Checklist

- [ ] Production deployment verified as healthy (monitoring dashboards checked)
- [ ] Feature flags enabled / configurations applied as per release plan
- [ ] Customer-facing documentation / release notes published
- [ ] Internal runbook updated with any new operational steps
- [ ] Rollback plan confirmed and ready if needed
- [ ] Customer Success Manager briefed on new capabilities, known issues, and workarounds
- [ ] Onboarding materials and training collateral ready
- [ ] Stakeholder announcement sent (or scheduled)
- [ ] Support team notified and briefed

**Artifacts to hand over**

| Artifact | Owner | Location |
|----------|-------|----------|
| Release notes (published) | Project Manager | Docs / changelog |
| Onboarding materials | Customer Success Manager | Shared drive / LMS |
| Operational runbook | DevOps Engineer | Project wiki |
| Known-issues summary | QA Lead | Support portal |

**Sign-off**

| Name | Role | Date |
|------|------|------|
| | Customer Success Manager | |
| | Project Manager | |

---

## Handoff 6 — Post-release → Retrospective & Close

**Handing off:** Customer Success Manager / Project Manager  
**Accepting:** Product Manager / Project Manager

### Checklist

- [ ] Post-release monitoring period completed (define window per project)
- [ ] Customer adoption metrics collected and shared with Product Manager
- [ ] Post-release feedback summary prepared by Customer Success Manager
- [ ] Any critical post-release defects resolved or formally tracked
- [ ] Retrospective meeting scheduled and facilitated
- [ ] Action items from retrospective documented and owners assigned
- [ ] Project artifacts archived and repo/board cleaned up
- [ ] Final status update sent to stakeholders

**Artifacts to hand over**

| Artifact | Owner | Location |
|----------|-------|----------|
| Adoption / feedback summary | Customer Success Manager | Project wiki |
| Retrospective notes | Project Manager | Project wiki |
| Action-item tracker | Project Manager | Project board |

**Sign-off**

| Name | Role | Date |
|------|------|------|
| | Product Manager | |
| | Project Manager | |

---

## Notes and Customization

- Not all phases apply to every project. Skip or merge phases as appropriate.
- For smaller releases, combine sign-off into a single lightweight review.
- Store completed checklists in the project repository for audit and retrospective reference.

---

## Related Documents

- [Roles & Personas](octoacme-roles-and-personas.md)
- [RACI / Ownership Matrix Template](octoacme-raci-matrix.md)
- [Release & Deployment Guide](octoacme-release-and-deployment.md)
- [Project Management Overview](octoacme-project-management-overview.md)
