# OctoAcme — Execution & Tracking

## Purpose
Guidance for managing day-to-day execution and tracking progress toward project milestones.

## Team Rhythm
- Daily standups (15 min) — focus on progress, blockers, dependencies
- Weekly delivery sync — show progress, updates, and flagged risks
- Demo/Review at the end of each sprint or milestone

## Workflows
- Use the project board (e.g., GitHub Projects) with columns: Backlog, Ready, In Progress, In Review, QA, Done
- Pull Request workflow:
  - Small PRs (<= 400 lines when possible)
  - Include issue link and acceptance criteria in PR description
  - Run automated tests and linting in CI before requesting review
  - Require at least one approval before merging (or team-defined policy)

## Quality & Testing
- Unit tests for new logic (Developers)
- Integration tests where applicable (Developers, QA Lead)
- End-to-end smoke tests for critical flows before release (QA Lead)
- Security scanning in CI (DevOps Engineer)
- Manual QA for feature acceptance when needed (QA Lead)
- Usability testing and design validation (UX Designer)
- Performance and load testing (DevOps Engineer, as needed)

## Reporting & Metrics
- Track velocity and burndown (Project Manager)
- Monitor success metrics identified in the Project One-pager (Data Analyst, Product Manager)
- Use dashboards for key signals (errors, latency, usage) (DevOps Engineer, Data Analyst)
- Track customer feedback and satisfaction trends (Customer Success Manager)

## Blocker Escalation
- Level 1: Team-level triage in daily standup
- Level 2: PM escalates to Product Lead and dependent teams
- Level 3: Sponsor-level escalation for business-impacting issues

## Execution Checklist
- [ ] Branching and PR conventions documented in repo
- [ ] CI configured for tests and lint (DevOps Engineer)
- [ ] Regular demos scheduled (Project Manager)
- [ ] Risk register updated weekly (Project Manager)
- [ ] Design mockups and prototypes approved (UX Designer)
- [ ] Test cases reviewed and test environments ready (QA Lead)
- [ ] Monitoring and observability in place (DevOps Engineer)
- [ ] Success metrics instrumented and validated (Data Analyst)
