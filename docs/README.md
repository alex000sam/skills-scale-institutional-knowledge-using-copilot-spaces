# OctoAcme Project Management Docs — README

OctoAcme’s project management approach is lightweight, iterative, and outcome-driven. Projects start with a concise Project One‑pager that captures the problem, objective, success metrics, stakeholders, and a high-level timeline. A go/no‑go decision gate moves approved initiatives into planning where work is broken into prioritized, shippable backlog items with clear acceptance criteria, estimates, and a documented Definition of Done. Planning captures dependencies, creates a milestone/release map, and records initial risks in the Risk Register.

Execution follows a board-driven workflow (Backlog → Ready → In Progress → In Review → QA → Done) and favors small, reviewable pull requests that include acceptance criteria and the linked issue. Continuous integration runs tests, linters, and security scans prior to review; at least one code review approval is required before merging. Team rhythm includes short daily standups for blockers, a weekly delivery sync for progress and escalations, sprint demos for stakeholder visibility, and a PM/PdM alignment cadence. Project READMEs and release notes serve as the single source of truth for status and announcements.

Roles and responsibilities are explicit: Product Managers define outcomes and success metrics, Project Managers coordinate delivery and communications, Developers implement and test, QA validates acceptance, and Stakeholders provide inputs and approvals. Quality assurance and risk controls are embedded in the pipeline — unit/integration tests, end‑to‑end smoke tests for critical flows, security scans in CI, manual QA as required, and a pre‑release checklist (passing CI/security scans, release notes, rollback plan, smoke tests). Retrospectives after sprints, releases, or incidents capture learnings and convert them into tracked action items.

Docs in this folder (entry points)
- docs/octoacme-project-management-overview.md
- docs/octoacme-project-initiation.md
- docs/octoacme-project-planning.md
- docs/octoacme-execution-and-tracking.md
- docs/octoacme-risks-and-communication.md
- docs/octoacme-release-and-deployment.md
- docs/octoacme-retrospective-and-continuous-improvement.md
- docs/octoacme-roles-and-personas.md

- docs/copilot-spaces-guide.md

How to use this README
- Use this file as the landing page for program-level process docs.
- Keep the Project One‑pager and release README updated in each project repo.
- Raise process changes as issues using the “Add Content to Project Management Process Docs” template (.github/ISSUE_TEMPLATE).