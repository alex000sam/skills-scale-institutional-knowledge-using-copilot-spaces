```markdown
# OctoAcme — Release Checklist

Purpose: a concise pre-release and post-release checklist to reduce risk and make releases consistent.

Pre-release (must be completed before a release is approved)
- [ ] All PRs merged and linked to issues with acceptance criteria
- [ ] CI green for all merged changes; security scans passed
- [ ] Integration and smoke tests executed in staging
- [ ] Rollback plan documented and validated
- [ ] Release notes drafted and reviewed (Technical Writer + PdM)
- [ ] Release window scheduled and communicated to stakeholders
- [ ] Support / On-call notified and runbooks updated
- [ ] Feature flags and rollout plan defined (if applicable)
- [ ] Release Manager approval obtained

Deployment
- [ ] Backup / snapshot (if applicable)
- [ ] Automated pipeline executed or manual steps followed
- [ ] Post-deploy smoke tests executed
- [ ] Verify key metrics and health checks

Post-release
- [ ] Confirm success with stakeholders and support
- [ ] Publish release notes to external/internal channels
- [ ] Update the Risk Register with any new observations
- [ ] Capture any follow-up action items and owners
- [ ] Retrospective entry (if release had notable issues)

Roles typically responsible (example)
- Release Manager: overall owner of checklist
- Developers / QA: validation and post-deploy verification
- Technical Writer: release notes
- PM / PdM: stakeholder communication and success validation
```