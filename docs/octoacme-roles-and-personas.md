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

## QA / Testing

### Role Summary
QA/Testing engineers validate that features meet acceptance criteria and that quality standards are upheld before release. They serve as the last gate before code reaches production.

### Responsibilities
- Review and execute test plans against acceptance criteria
- Report, track, and verify bug fixes
- Define and maintain the Definition of Done (DoD) quality requirements
- Perform exploratory and regression testing
- Collaborate with Developers on testability and test coverage

### Goals
- Prevent defects from reaching production
- Maintain a fast, reliable feedback loop between development and testing
- Continuously improve test coverage and automation

### Typical Communication
- Sprint ceremonies (planning, demos, retrospectives)
- Bug reports and QA sign-off tickets
- Coordination with Release Manager before deployments

### Interactions with other roles
- **Developers**: receive completed work items; raise defects and verify fixes
- **Project Manager**: communicate QA status and blockers that affect release timelines
- **Product Manager**: clarify acceptance criteria and edge cases
- **Release Manager**: provide formal QA sign-off before deployment windows
- **Business Analyst**: confirm that implemented behavior matches requirements

---

## Stakeholders

### Role Summary
Stakeholders are individuals or groups with a vested interest in the project outcome. They provide business context, approve priorities, and receive regular status updates.

### Responsibilities
- Provide input on business requirements and priorities
- Review and approve key project milestones (e.g., One-pager, release plan)
- Participate in demos and retrospectives when needed
- Escalate business-critical concerns to the Project Manager

### Goals
- Ensure the delivered product meets business and customer needs
- Maintain visibility into project progress and risks
- Provide timely decisions to avoid delivery delays

### Typical Communication
- Monthly stakeholder updates and ad-hoc briefings
- Sprint demos and review sessions
- Decision approvals via email or recorded meeting notes

### Interactions with other roles
- **Project Manager**: primary point of contact for status and escalations
- **Product Manager**: collaborates on roadmap priorities and outcome validation
- **Business Analyst**: works with BA to articulate requirements and acceptance criteria

---

## Scrum Master

### Role Summary
The Scrum Master facilitates agile ceremonies, removes impediments, and coaches the team on agile practices. They protect the team from scope creep and external distractions to sustain a healthy delivery cadence.

### Responsibilities
- Facilitate sprint planning, daily standups, reviews, and retrospectives
- Identify and remove blockers that impede team progress
- Shield the team from unplanned interruptions and scope changes mid-sprint
- Coach team members on agile principles and continuous improvement
- Maintain and communicate sprint metrics (velocity, burndown)

### Goals
- Sustain a predictable, healthy team delivery cadence
- Foster a culture of continuous improvement and psychological safety
- Drive down cycle time and reduce impediments

### Typical Communication
- Daily standups and sprint ceremony facilitation
- Impediment logs and escalation notes
- Sprint retrospective actions and improvement tracking

### Interactions with other roles
- **Project Manager**: aligns on delivery timeline, escalations, and cross-team dependencies
- **Product Manager**: ensures the backlog is refined and sprint goals are clear
- **Developers**: removes blockers; coaches on estimation and WIP limits
- **QA/Testing**: surfaces testing bottlenecks and DoD gaps during retrospectives
- **Stakeholders**: manages stakeholder requests that arrive mid-sprint to prevent disruption

---

## Release Manager

### Role Summary
The Release Manager coordinates and oversees all release activities, including scheduling deployment windows, verifying readiness checklists, and communicating release status to stakeholders.

### Responsibilities
- Plan and communicate deployment windows and change-freeze periods
- Own the release readiness checklist and gate decisions (go/no-go)
- Coordinate with Developers, QA, and infrastructure teams during deployments
- Draft and publish release notes and post-deployment announcements
- Manage rollback procedures when required

### Goals
- Deliver releases safely with minimal disruption to users
- Maintain a clear, auditable record of what was released and when
- Reduce mean time to recover (MTTR) for failed deployments

### Typical Communication
- Release schedule and change window notifications
- Go/no-go decisions shared with PM, QA, and Developers
- Post-release summaries distributed to Stakeholders

### Interactions with other roles
- **Project Manager**: aligns release dates with project milestones and stakeholder commitments
- **Developers**: confirms that all PRs are merged, CI is green, and environment configs are ready
- **QA/Testing**: receives formal sign-off before opening a deployment window
- **Product Manager**: collaborates on release notes content and feature announcements
- **Stakeholders**: communicates release timelines and post-release outcomes

---

## UX / UI Designer

### Role Summary
UX/UI Designers advocate for user needs and translate them into intuitive, accessible designs. They collaborate early in the product lifecycle to ensure solutions are usable before development begins.

### Responsibilities
- Conduct user research and synthesize insights into design requirements
- Create wireframes, prototypes, and high-fidelity design assets
- Define interaction patterns, style guides, and accessibility standards
- Participate in design reviews and usability testing
- Hand off design specifications and assets to Developers

### Goals
- Deliver designs that are user-centered, accessible, and technically feasible
- Reduce rework by validating designs with users before development
- Maintain a coherent, consistent product experience

### Typical Communication
- Design reviews and prototype walkthroughs with PdM, PM, and Developers
- Annotated design files and component specifications (e.g., Figma)
- Usability test reports shared with Product Manager and Stakeholders

### Interactions with other roles
- **Product Manager**: collaborates on problem framing, user personas, and acceptance criteria
- **Developers**: provides detailed specs and assets; participates in implementation reviews to ensure design fidelity
- **Project Manager**: communicates design milestones and flags scope impacts of design changes
- **Business Analyst**: incorporates business rules and requirements into design solutions
- **Stakeholders**: presents prototypes and usability findings for feedback and approval

---

## Technical Writer

### Role Summary
Technical Writers create and maintain clear, accurate documentation for users and developers. They ensure that product changes are reflected in documentation and that knowledge is accessible across the organization.

### Responsibilities
- Author user guides, API references, runbooks, and release notes
- Collaborate with Developers and PdM to understand features and changes
- Review and update documentation as part of the Definition of Done
- Maintain a documentation style guide and content standards
- Identify and close documentation gaps identified during QA or retrospectives

### Goals
- Ensure every feature ships with accurate, complete documentation
- Reduce support burden through clear self-service content
- Maintain documentation quality and consistency over time

### Typical Communication
- Participation in sprint planning and demos to capture documentation needs
- Asynchronous review of PRs and release notes for accuracy
- Doc review cycles with PdM, QA, and Release Manager before release

### Interactions with other roles
- **Developers**: sources technical details, reviews code comments, and verifies accuracy of technical docs
- **Product Manager**: aligns on feature intent and user-facing messaging
- **QA/Testing**: incorporates bug and edge-case findings into documentation
- **Release Manager**: contributes to and reviews release notes before publication
- **Stakeholders**: produces stakeholder-facing summaries and user communication content

---

## Business Analyst

### Role Summary
Business Analysts bridge business needs and technical solutions. They facilitate requirements gathering, document acceptance criteria, and ensure that delivered solutions solve the right problems.

### Responsibilities
- Elicit and document business and functional requirements
- Translate stakeholder needs into user stories and acceptance criteria
- Facilitate workshops and requirements review sessions
- Maintain a traceability matrix linking requirements to deliverables
- Validate that implemented solutions satisfy business requirements

### Goals
- Ensure clarity and shared understanding of requirements across all roles
- Reduce ambiguity that leads to rework or missed expectations
- Support data-driven decision-making with well-defined success criteria

### Typical Communication
- Requirements workshops with Stakeholders, PM, and PdM
- User story refinement sessions with Developers and QA
- Acceptance criteria sign-off before sprint commitment

### Interactions with other roles
- **Product Manager**: co-authors requirements and backlog items; aligns on priorities
- **Project Manager**: flags scope changes, risks to timeline from requirement shifts
- **Developers**: clarifies requirements during implementation; reviews solutions against criteria
- **QA/Testing**: co-defines acceptance criteria and edge-case scenarios for test plans
- **Stakeholders**: primary liaison for capturing, validating, and communicating requirements
- **UX/UI Designer**: ensures designs reflect business rules and functional requirements

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- For a full view of role ownership across project activities and handoff points, see [Ownership and Handoffs](octoacme-ownership-and-handoffs.md).

