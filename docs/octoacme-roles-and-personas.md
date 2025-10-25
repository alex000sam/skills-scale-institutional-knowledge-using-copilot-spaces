```markdown
# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.
It has been expanded to include additional personas and clear interaction patterns to reduce ambiguity
and improve accountability during planning, execution, releases, and documentation.

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

## (New) Release Manager

### Role Summary
Coordinates and owns the release pipeline and schedule for a project or product area. Focuses on reducing deployment risk and ensuring release readiness.

### Responsibilities
- Create and maintain release schedule and cutover plans
- Ensure pre-release requirements are met (CI, tests, rollbacks, release notes)
- Coordinate cross-team release activities (QA, infra, support, documentation)
- Lead release readiness checks and post-release verification
- Maintain rollback and mitigation playbooks

### Interaction
- Works closely with PM for scheduling and stakeholder communication
- Collaborates with Developers and QA to validate readiness
- Partners with Technical Writer for release notes and communications
- Notifies Support and On-call teams prior to release windows

---

## (New) Scrum Master

### Role Summary
Supports teams practicing agile methods by facilitating ceremonies, removing impediments, and helping the team improve its delivery process.

### Responsibilities
- Facilitate sprint ceremonies (planning, daily standup, review, retrospective)
- Track and remove team blockers or escalate where needed
- Coach the team on agile practices, flow, and continuous improvement
- Help maintain a healthy sprint backlog and support estimation sessions

### Interaction
- Works with Project Manager to align delivery cadence and escalations
- Supports Developers and QA to improve flow and throughput
- Coordinates with Product Manager to ensure backlog readiness

---

## (New) Technical Writer

### Role Summary
Produces and maintains user-facing and internal documentation required for adoption, support, and compliance.

### Responsibilities
- Draft and maintain release notes, user guides, runbooks, and API docs
- Ensure documentation is updated as part of the Definition of Done
- Coordinate reviews with SMEs (Developers, QA, PM)
- Maintain a documentation checklist and publishing workflow

### Interaction
- Works with Developers and QA to verify accuracy
- Collaborates with Release Manager to publish release notes
- Partners with Product Manager to align documentation with product messaging

---

## (New) Business Analyst

### Role Summary
Bridges stakeholders and the delivery team by refining requirements, creating acceptance criteria, and defining measurable outcomes.

### Responsibilities
- Elicit, document, and validate functional and non-functional requirements
- Define acceptance criteria and success metrics for backlog items
- Model business flows and help identify edge cases
- Support stakeholder alignment and clarify priority trade-offs

### Interaction
- Works with Product Manager to translate vision into backlog items
- Engages Developers and QA to ensure requirements are actionable and testable
- Coordinates with Project Manager to surface dependency impacts

---

## Interaction patterns & responsibility mapping

- Planning
  - Product Manager (PdM) owns backlog prioritization; Business Analyst refines requirements; Project Manager ensures timelines; Scrum Master organizes planning.
- Execution
  - Developers implement work; QA validates; Technical Writer updates documentation as part of DoD; Scrum Master removes impediments.
- Release
  - Release Manager owns schedule and readiness checks; Developers and QA complete verification; Technical Writer publishes release notes; Project Manager informs stakeholders.
- Escalation
  - Team -> Scrum Master / PM -> Product Lead -> Sponsor. For security incidents follow the security runbook and notify Security on-call.

---

## How to use these personas
- Use these persona definitions to clarify handoffs in project plans and checklists.
- Add role assignments to the Project One-pager and to backlog items (Owner field).
- For exercises and Copilot prompts, use these persona summaries to simulate stakeholder perspectives.
```