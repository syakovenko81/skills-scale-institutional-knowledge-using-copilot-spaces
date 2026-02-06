# OctoAcme — Risk Management & Communication

## Purpose
Explain how to identify, manage, and communicate risks and dependencies.

## Risk Register
Maintain a simple table with:
- ID
- Description
- Impact (High/Med/Low)
- Likelihood (High/Med/Low)
- Owner
- Mitigation plan
- Status

**Role Responsibilities in Risk Management:**
- **Project Manager:** Maintains and reviews risk register, coordinates mitigation
- **Developers:** Identify technical and implementation risks
- **QA/Testers:** Flag quality, testing resource, and timeline risks
- **UX/UI Designers:** Raise design feasibility and usability risks
- **Business Analyst:** Identify requirements and stakeholder alignment risks
- **Product Manager:** Assess business impact and prioritize risk mitigation
- **Scrum Master:** Surface team capacity and process risks

## Risk Lifecycle
- Identify: during planning and ongoing execution
- Assess: estimate impact and likelihood
- Mitigate: reduced via actions, contingency plans
- Monitor: review at weekly syncs and update status

## Stakeholder Communication
- Identify stakeholder groups and communication needs (e.g., engineering, sales, support)
- Provide regular updates (weekly or milestone-based)
- Use a single source of truth (project README or release doc) for status

**Communication Roles:**
- **Project Manager:** Primary coordinator for stakeholder updates and status reporting
- **Product Manager:** Communicates product vision, roadmap, and business outcomes
- **Technical Writer:** Prepares stakeholder-facing documentation and release communications
- **Business Analyst:** Facilitates stakeholder requirements sessions and validation
- **Scrum Master:** Reports on team health and delivery predictability

## Communication Templates
Weekly Status Template *(Project Manager prepares, Technical Writer may assist)*:
- Progress this week:
- Next steps:
- Risks & blockers:
- Ask / decisions needed:

Incident Communication *(Project Manager leads, Technical Writer formats)*
- Triage summary
- Actions being taken
- Expected timeline
- Post-incident blameless retrospective scheduled *(Scrum Master facilitates)*

## Escalation Paths
- Team-level -> PM -> Product Lead -> Sponsor
- For security incidents, follow the security incident runbook and notify Security on-call
