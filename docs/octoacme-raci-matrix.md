# OctoAcme RACI / Ownership Matrix Template

Use this template to clarify who is **R**esponsible, **A**ccountable, **C**onsulted, and **I**nformed for each core project activity. Fill it in at the start of planning and update it as the team composition changes.

**Key**

| Code | Meaning |
|------|---------|
| **R** | **Responsible** — does the work |
| **A** | **Accountable** — owns the outcome; signs off |
| **C** | **Consulted** — provides input before decisions are made |
| **I** | **Informed** — kept up to date on progress/decisions |

> Every activity should have exactly **one A**. Multiple Rs are fine.

---

## Project Details

| Field | Value |
|-------|-------|
| Project name | _\<project name\>_ |
| Date | _\<YYYY-MM-DD\>_ |
| Owner | _\<name / role\>_ |

---

## RACI Matrix

| Activity | Project Manager | Product Manager | Developer | UX Designer | DevOps Engineer | Business Analyst | QA Lead | Customer Success Manager | Stakeholders |
|----------|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|
| **Initiation** | | | | | | | | | |
| Define business need and goals | C | A | I | I | I | R | I | C | C |
| Identify and engage stakeholders | A | C | I | I | I | C | I | C | I |
| Draft project charter / one-pager | A | R | I | I | I | C | I | I | C |
| Gain project go/no-go approval | C | A | I | I | I | I | I | I | R |
| **Planning** | | | | | | | | | |
| Define scope and requirements | C | A | C | C | C | R | C | C | C |
| Create user stories and acceptance criteria | I | A | C | C | I | R | C | I | I |
| Develop project plan and timeline | A | C | C | I | C | I | I | I | I |
| Identify risks and mitigation strategies | A | C | C | I | C | C | I | I | I |
| Assign roles and resources | A | C | C | C | C | I | I | I | I |
| **Design** | | | | | | | | | |
| Create wireframes and prototypes | I | C | C | R/A | I | I | I | C | I |
| Conduct design reviews | C | C | C | A | I | I | I | I | C |
| Obtain design sign-off | C | A | I | R | I | I | I | I | C |
| **Development** | | | | | | | | | |
| Implement features | I | I | R/A | C | C | C | C | I | I |
| Code reviews and pull requests | I | I | R/A | I | I | I | I | I | I |
| Set up / maintain CI/CD and environments | I | I | C | I | R/A | I | C | I | I |
| **Quality Assurance** | | | | | | | | | |
| Define test plan and approach | C | C | C | I | C | C | R/A | I | I |
| Execute test cycles | I | I | C | I | C | I | R/A | I | I |
| Defect triage and resolution | C | C | R | I | C | I | A | I | I |
| QA sign-off for release | C | A | I | I | I | I | R | I | I |
| **Release & Deployment** | | | | | | | | | |
| Create release plan | A | C | C | I | C | I | C | C | I |
| Deploy to production | C | I | C | I | R/A | I | C | I | I |
| Post-deployment verification | C | C | C | I | R | I | A | I | I |
| Announce / communicate release | A | C | I | I | I | I | I | C | I |
| **Customer Enablement** | | | | | | | | | |
| Develop onboarding / training materials | I | C | I | C | I | I | I | R/A | C |
| Conduct customer onboarding | I | I | I | I | I | I | I | R/A | C |
| Gather post-release feedback | I | C | I | I | I | I | I | R/A | I |
| Escalate post-release issues | C | C | C | I | C | I | C | A | I |
| **Retrospective & Close** | | | | | | | | | |
| Facilitate retrospective | A | C | C | C | C | C | C | C | I |
| Document learnings and action items | A | C | C | C | C | C | C | C | I |
| Archive project artifacts | A | I | I | I | I | I | I | I | I |

---

## Notes and Customization

- Add or remove rows to match the activities relevant to your project.
- If a role does not apply to your project, remove that column.
- Revisit this matrix at each major phase transition to confirm ownership is still accurate.
- Store the completed RACI in the project repo alongside the project charter.

---

## Related Documents

- [Roles & Personas](octoacme-roles-and-personas.md)
- [Cross-functional Handoff Checklist](octoacme-cross-functional-handoff-checklist.md)
- [Project Management Overview](octoacme-project-management-overview.md)
