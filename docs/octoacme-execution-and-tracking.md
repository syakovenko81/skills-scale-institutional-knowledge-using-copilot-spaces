# OctoAcme — Execution & Tracking

## Purpose
Guidance for managing day-to-day execution and tracking progress toward project milestones.

## Team Rhythm
- Daily standups (15 min) — focus on progress, blockers, dependencies *(Facilitated by Scrum Master)*
- Weekly delivery sync — show progress, updates, and flagged risks *(Project Manager leads)*
- Demo/Review at the end of each sprint or milestone *(Scrum Master facilitates, team presents)*
- Design review sessions for UI/UX feedback *(UX/UI Designer leads)*
- Documentation review cycles aligned with releases *(Technical Writer coordinates)*

## Workflows
- Use the project board (e.g., GitHub Projects) with columns: Backlog, Ready, In Progress, In Review, QA, Done
- Pull Request workflow:
  - Small PRs (<= 400 lines when possible)
  - Include issue link and acceptance criteria in PR description
  - Run automated tests and linting in CI before requesting review *(Developer)*
  - Design review for UI changes (screenshots/recordings required) *(UX/UI Designer reviews)*
  - Require at least one approval before merging (or team-defined policy) *(Developer peer review)*
  - Move to QA column for testing *(QA/Tester validates)*
- Blocker resolution coordinated by Scrum Master with Project Manager escalation as needed

## Quality & Testing
**QA/Tester Responsibilities:**
- Unit tests for new logic *(Developers write, QA reviews coverage)*
- Integration tests where applicable *(Developers and QA collaborate)*
- End-to-end smoke tests for critical flows before release *(QA/Tester owns)*
- Security scanning in CI *(Automated, Developer and QA review results)*
- Manual QA for feature acceptance when needed *(QA/Tester executes)*
- Accessibility testing for UI changes *(QA/Tester with UX/UI Designer)*
- Bug triage and prioritization *(QA, Developer, Product Manager collaborate)*

**Quality Handoffs:**
- Developer → QA: Feature complete with passing tests
- QA → Product Manager: Validated against acceptance criteria
- UX/UI Designer → QA: Design validation checklist for UI features

## Reporting & Metrics
- Track velocity and burndown
- Monitor success metrics identified in the Project One-pager
- Use dashboards for key signals (errors, latency, usage)

## Blocker Escalation
- Level 1: Team-level triage in daily standup *(Scrum Master facilitates)*
- Level 2: PM escalates to Product Lead and dependent teams *(Project Manager)*
- Level 3: Sponsor-level escalation for business-impacting issues *(Project Manager, Product Manager)*

**Cross-role coordination for blockers:**
- Technical blockers: Developer → Scrum Master → Project Manager
- Requirements clarification: Developer/QA → Business Analyst → Product Manager
- Design blockers: Developer → UX/UI Designer → Project Manager
- Resource constraints: Scrum Master → Project Manager

## Execution Checklist
- [ ] Branching and PR conventions documented in repo *(Technical Lead)*
- [ ] CI configured for tests and lint *(Developer)*
- [ ] Regular demos scheduled *(Scrum Master, Project Manager)*
- [ ] Risk register updated weekly *(Project Manager)*
- [ ] QA test plans aligned with sprint goals *(QA/Tester)*
- [ ] Design review process established for UI work *(UX/UI Designer)*
- [ ] Documentation updates tracked in project board *(Technical Writer)*
- [ ] Team velocity and burndown monitored *(Scrum Master, Project Manager)*
