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

## Product Owner

### Role Summary
The Product Owner is accountable for the value delivered by the project and for prioritizing the work that maximizes business outcomes. They are the single point of accountability for backlog priorities and accepted deliverables within the project.

### Responsibilities
- Define and prioritize the highest-value work based on customer and business needs
- Clarify scope, trade-offs, and acceptance criteria for each feature or milestone
- Accept or reject work as complete based on agreed outcomes and quality standards
- Partner with stakeholders to translate business needs into actionable requirements
- Resolve day-to-day prioritization questions and make decisions when trade-offs are needed

### Decisions Owned
- Priority of work items and release sequencing
- Scope adjustments within approved project boundaries
- Acceptance of deliverables against agreed outcomes

### Typical Interaction with Other Roles
- Works with Project Managers to align priorities with timelines, dependencies, and resource constraints
- Collaborates with Product Managers and stakeholders to maintain business alignment and validate outcomes
- Provides decision-ready requirements to Developers and Business Analysts for implementation
- Works with Quality Assurance Lead to confirm the feature meets business intent and acceptance criteria

### When this role may be combined
- On smaller projects, the Product Owner role may be combined with the Product Manager or Project Manager role when the project scope is limited and stakeholder decisions are centralized.

---

## Project Sponsor

### Role Summary
The Project Sponsor provides strategic direction, funding support, and escalation authority for the initiative. They ensure the project remains aligned with organizational goals and that major risks or decisions receive executive attention.

### Responsibilities
- Champion the project vision, business case, and strategic outcomes
- Approve scope, budget, and major milestone commitments
- Resolve escalated conflicts, policy exceptions, or cross-functional decision blockers
- Monitor benefits realization and executive-level reporting
- Support stakeholder alignment and sponsorship across business units

### Decisions Owned
- Business case and funding approval
- Major scope changes that affect project value or strategic intent
- Escalation authority for unresolved issues that require executive action

### Typical Interaction with Other Roles
- Partners with Project Managers to review progress, risks, and decisions that affect delivery commitments
- Aligns with Product Managers and Product Owners on strategic priorities and expected business outcomes
- Escalates decisions to senior leadership when trade-offs exceed team authority
- Works with Communications Lead to ensure consistent senior stakeholder messaging and sponsorship visibility

### When this role may be combined
- In small teams, the Project Sponsor may be the same person as the Product Manager, Project Manager, or executive leader sponsoring the initiative.

---

## Business Analyst

### Role Summary
The Business Analyst turns stakeholder needs into clear requirements, process understanding, and measurable acceptance criteria. They help the team and stakeholders agree on what “done” looks like before work is implemented.

### Responsibilities
- Elicit, document, and validate business requirements and workflows
- Analyze current processes, pain points, and opportunities for improvement
- Define user stories, business rules, and acceptance criteria with measurable outcomes
- Support requirements traceability throughout planning, delivery, and testing
- Facilitate alignment between business stakeholders and technical teams

### Decisions Owned
- Requirement clarity and interpretation
- Process and workflow definition within the approved scope
- Acceptance criteria quality and validation readiness

### Typical Interaction with Other Roles
- Works closely with Product Owners and Product Managers to confirm the problem statement and business value
- Collaborates with Developers to clarify technical implications of requirements and edge cases
- Coordinates with Project Managers on dependencies, milestones, and sign-off checkpoints
- Supports Quality Assurance Lead by providing testable conditions and business validation criteria

### When this role may be combined
- On smaller projects, the Business Analyst may be absorbed by the Product Owner, Project Manager, or a senior Developer when business analysis needs are limited.

---

## Quality Assurance Lead

### Role Summary
The Quality Assurance Lead defines the validation approach, coordinates testing activities, and ensures the project meets agreed quality standards before release. They provide the quality gate for readiness and confidence in the outcome.

### Responsibilities
- Define the overall test strategy, validation approach, and quality gates
- Coordinate test planning, execution, regression coverage, and defect triage
- Work with Developers and Product Owners to confirm that requirements are testable and complete
- Track defects, risks, and release readiness against agreed standards
- Support decision-making around launch, rollback, or remediation when quality issues arise

### Decisions Owned
- Quality threshold for readiness and release sign-off
- Risk-based validation prioritization and test approach
- Escalation of unresolved defects or quality risks

### Typical Interaction with Other Roles
- Partners with Developers to validate implementation quality and identify edge cases
- Works with Product Owners and Business Analysts to ensure acceptance criteria are measurable
- Coordinates with Project Managers on milestone readiness, validation timing, and issue tracking
- Provides quality evidence to Project Sponsors and stakeholders during status reviews and approval checkpoints

### When this role may be combined
- Smaller projects may combine QA leadership with a Developer, Product Owner, or Project Manager when testing is lighter and validation is handled collaboratively.

---

## Communications Lead

### Role Summary
The Communications Lead coordinates stakeholder messaging, project updates, and change communications so that everyone receives timely, accurate information. They help maintain alignment and reduce confusion during delivery.

### Responsibilities
- Maintain stakeholder maps, communication plans, and update cadence
- Draft and distribute project status updates, milestone notices, and change communications
- Coordinate messaging around risks, dependencies, and approvals
- Support stakeholder engagement and adoption planning
- Align internal and external messaging with project objectives and sponsor expectations

### Decisions Owned
- Communication cadence and stakeholder audiences
- Messaging priorities for key milestones, risks, or changes
- Approvals for stakeholder-facing updates in partnership with sponsors and PMs

### Typical Interaction with Other Roles
- Works with Project Managers to keep status updates accurate and consistent with delivery reality
- Coordinates with Product Owners and Sponsors on communications that affect priorities or scope decisions
- Supports Business Analysts when requirement changes or process updates need stakeholder explanation
- Helps Quality Assurance Lead communicate release readiness and risk-based decisions clearly to stakeholders

### When this role may be combined
- On smaller teams, the Communications Lead responsibilities may be owned by the Project Manager, Product Manager, or Sponsor depending on the level of stakeholder complexity.

---

## Role overlap and scaling

OctoAcme projects may vary in size and maturity. In smaller projects, one person may hold multiple roles, and responsibilities can be combined to reduce overhead without reducing accountability. The key is to keep ownership clear: every decision should have a named approver, and every handoff should be documented.

This means a team may combine Product Management, Product Ownership, and Project Management responsibilities on smaller initiatives, while larger programs may separate them to improve focus and governance.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- These roles are intended to clarify decision ownership, stakeholder handoffs, and collaboration patterns across the project lifecycle.

