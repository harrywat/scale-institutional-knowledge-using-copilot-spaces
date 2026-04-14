# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

---

## Developers

### Role Summary
Developers design, build, test, and deliver software components. They collaborate with product and project leads to implement features that meet acceptance criteria and quality standards.

### Responsibilities
- Implement features and fixes to meet acceptance criteria
- Write and maintain tests and documentation
- Participate in design and code reviews
- Assist in estimating and planning work
- Help identify technical risks and propose mitigations

### Goals
- Deliver reliable, maintainable code
- Reduce cycle time from idea to production
- Maintain high test coverage and observability

### Typical Communication
- Daily standups and sprint planning
- PR descriptions and code review comments
- Technical design docs when needed

---

## Product Managers

### Role Summary
Product Managers define what should be built to deliver customer and business value. They own the product vision, prioritize the backlog, and measure outcomes.

### Responsibilities
- Define problem statements and success metrics
- Prioritize the roadmap and backlog
- Collaborate with stakeholders and engineering on trade-offs
- Validate solutions through user research and metrics

### Goals
- Maximize customer value and impact
- Make clear, data-driven prioritization decisions
- Ensure product-market fit and usability

### Typical Communication
- Weekly alignment with PM and engineering leads
- Roadmap updates and stakeholder briefings
- Acceptance criteria and feature specs

---

## Project Managers

### Role Summary
Project Managers coordinate delivery activities, manage schedules, risks, and communications. They enable the team to deliver on commitments efficiently.

### Responsibilities
- Create and maintain project plans and timelines
- Manage risks, dependencies, and resource constraints
- Facilitate meetings (kickoff, planning, retrospectives)
- Ensure consistent project documentation and status reporting
- Coordinate cross-team and stakeholder communication

### Goals
- Deliver projects on time and within scope
- Minimize unplanned work and escalations
- Maintain transparency and alignment across stakeholders

### Typical Communication
- Weekly status updates and stakeholder reports
- Risk registers and decision logs
- Coordination via project boards and meeting facilitation

---

## UX Designer

### Role Summary
UX Designers own the user experience of the product. They create wireframes, prototypes, and visual assets; conduct user research; and ensure usability is considered at every stage of delivery.

### Responsibilities
- Create wireframes, mockups, and interactive prototypes
- Conduct user research, usability tests, and synthesize findings
- Translate product requirements into clear design specs and user flows
- Collaborate on design reviews and iterate based on feedback
- Maintain a design system or style guide for visual consistency

### Goals
- Deliver intuitive, accessible experiences that meet user needs
- Reduce usability issues discovered late in the cycle
- Ensure design decisions are grounded in user evidence

### Typical Communication
- Design review sessions with Product Manager and Developers
- Annotated mockups and design specs shared via design tools
- Attendance at kickoff, demo, and sprint review meetings

### Interactions
- **Product Manager:** Translates product goals into user flows and validates design direction against success metrics.
- **Developers:** Provides detailed design specs and is available to answer implementation questions; reviews built UI against specs.
- **QA Lead:** Shares acceptance criteria for UX (e.g., visual parity, accessibility standards) so QA can validate designs are correctly implemented.
- **Project Manager:** Flags design-scope changes that may affect timeline or resources.
- **Stakeholders:** Presents prototypes and usability findings to gather feedback before implementation begins.

---

## DevOps Engineer

### Role Summary
DevOps Engineers design, maintain, and automate deployment pipelines, manage cloud infrastructure, and ensure the reliability and repeatability of build and release processes.

### Responsibilities
- Set up and maintain CI/CD pipelines and release automation
- Manage cloud infrastructure, environments (dev/staging/prod), and access controls
- Monitor system reliability, performance, and security posture
- Advise on deployment risks, rollback strategies, and incident response
- Support QA and Developers with test environment provisioning

### Goals
- Maximize deployment frequency while minimizing change-failure rate
- Reduce mean time to recovery (MTTR) for production incidents
- Ensure infrastructure is secure, cost-effective, and observable

### Typical Communication
- Deployment readiness updates before each release
- Incident reports and post-mortems
- Infrastructure runbooks and environment documentation

### Interactions
- **Developers:** Collaborates on build and test pipeline configuration; provides feedback on code packaging and environment compatibility.
- **QA Lead:** Provisions test environments, ensures parity between test and production, and coordinates deployment windows for QA sign-off.
- **Project Manager:** Communicates deployment timelines, environment availability, and risk factors that may affect release dates.
- **Product Manager:** Flags infrastructure constraints or costs that could influence feature scoping or release windows.
- **Stakeholders:** Provides release status updates and post-deployment health summaries.

---

## Business Analyst

### Role Summary
Business Analysts bridge the gap between stakeholders and the delivery team by capturing requirements, mapping processes, and ensuring user stories are clear and actionable before development begins.

### Responsibilities
- Elicit, document, and validate business and functional requirements
- Map current-state and future-state processes; identify gaps
- Author user stories with clear acceptance criteria in collaboration with Product Manager
- Support backlog refinement and prioritization sessions
- Track requirement traceability throughout the project lifecycle

### Goals
- Ensure requirements are complete, consistent, and unambiguous before work starts
- Reduce rework caused by misunderstood or incomplete requirements
- Maintain alignment between stakeholder expectations and delivery output

### Typical Communication
- Requirements workshops and discovery sessions with stakeholders
- Written user stories and process-flow diagrams shared with the team
- Regular sync with Product Manager during backlog refinement

### Interactions
- **Product Manager:** Co-owns the backlog; refines problem statements into user stories and acceptance criteria.
- **Stakeholders:** Facilitates requirements gathering sessions; validates outputs to confirm shared understanding.
- **Developers:** Clarifies acceptance criteria and expected behavior during sprint planning and development.
- **QA Lead:** Reviews test cases against acceptance criteria to confirm coverage before QA begins.
- **Project Manager:** Flags scope changes or ambiguities discovered during analysis that may affect project plans.

---

## QA Lead

### Role Summary
QA Leads oversee test planning, quality strategy, and defect management. They ensure that shipped features meet acceptance criteria and that quality gates are well-defined and consistently applied.

### Responsibilities
- Define the overall test approach (functional, regression, performance, accessibility)
- Create and maintain test plans, test cases, and test data
- Coordinate and execute test cycles; track and triage defects
- Report quality status to the team and stakeholders
- Establish Definition of Done criteria that include quality standards

### Goals
- Prevent defects from reaching production by catching them early
- Provide timely, actionable quality signals throughout the sprint
- Continuously improve test coverage and efficiency

### Typical Communication
- Test summary reports at end of each sprint or release cycle
- Defect triage sessions with Developers and Product Manager
- Attendance at sprint planning to assess testability and acceptance criteria

### Interactions
- **Developers:** Aligns on expected behavior, provides early test feedback, and collaborates on testability improvements.
- **Product Manager:** Reviews acceptance criteria and confirms quality standards before stories are accepted as done.
- **UX Designer:** Validates that the built UI matches design specs and meets accessibility requirements.
- **DevOps Engineer:** Coordinates environment readiness and deployment windows for test execution.
- **Business Analyst:** Reviews test cases against acceptance criteria to confirm full requirement coverage.
- **Project Manager:** Communicates quality risks, test completion status, and any release-blocking defects.

---

## Customer Success Manager

### Role Summary
Customer Success Managers guide onboarding, adoption, and ongoing success for end users and customers post-release. They act as the voice of the customer inside the project team.

### Responsibilities
- Conduct product walkthroughs and onboarding sessions for customers and end users
- Gather and synthesize post-release feedback, feature requests, and pain points
- Escalate post-release issues or high-priority enhancement requests to the product team
- Develop customer-facing documentation, training materials, and FAQs
- Track adoption and satisfaction metrics; surface trends to inform the roadmap

### Goals
- Maximize customer adoption and time-to-value after each release
- Minimize post-release escalations through proactive enablement
- Build a feedback loop between customers and the product team

### Typical Communication
- Customer onboarding meetings and training sessions
- Post-release feedback summaries shared with Product Manager and Project Manager
- Regular syncs with Stakeholders and end-user groups during rollout

### Interactions
- **Product Manager:** Shares customer feedback, feature requests, and adoption data to inform roadmap prioritization.
- **Project Manager:** Coordinates customer-enablement activities within the release and post-launch plan.
- **Developers:** Escalates post-release defects or unexpected behaviors discovered by customers.
- **UX Designer:** Relays usability feedback gathered during onboarding and customer sessions.
- **Stakeholders:** Keeps business stakeholders informed of customer reception and adoption progress after go-live.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

