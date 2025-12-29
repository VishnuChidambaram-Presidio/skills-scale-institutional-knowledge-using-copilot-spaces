# OctoAcme Role Interaction Matrix

## Purpose
This document clarifies collaboration touchpoints, communication flows, and hand-offs between different roles in OctoAcme projects. Use this matrix to understand who works with whom, when, and why.

---

## Primary Collaboration Patterns

### Project Initiation Phase

| Role | Collaborates With | Purpose | Frequency |
|------|-------------------|---------|-----------|
| Project Manager | Product Manager, Product Owner, Stakeholders | Define project charter, scope, and success criteria | Kickoff + Weekly |
| Business Analyst | Product Owner, Stakeholders, Project Manager | Elicit requirements, identify constraints | Kickoff + As needed |
| Product Owner | Product Manager, Business Analyst | Align on product vision and initial backlog | Kickoff + Weekly |
| DevOps Engineer | Developers, Project Manager | Plan infrastructure and deployment needs | Kickoff + As needed |
| Change Manager | Project Manager, Stakeholders | Establish change control process | Kickoff |

### Planning Phase

| Role | Collaborates With | Purpose | Frequency |
|------|-------------------|---------|-----------|
| Project Manager | All roles | Create project plan, assign resources, identify dependencies | Planning sessions |
| Business Analyst | Product Owner, Developers | Refine requirements into user stories and acceptance criteria | Weekly + Backlog refinement |
| QA Lead | Developers, Project Manager | Define test strategy, identify test environments | Planning sessions |
| DevOps Engineer | Developers, QA Lead | Setup environments and CI/CD pipelines | Planning + As needed |
| Product Owner | Business Analyst, Developers, Project Manager | Prioritize backlog and define sprint goals | Sprint planning |

### Execution Phase

| Role | Collaborates With | Purpose | Frequency |
|------|-------------------|---------|-----------|
| Developers | Product Owner, Business Analyst, QA Lead | Implement features, clarify requirements, coordinate testing | Daily standups |
| QA Lead | Developers, Product Owner, DevOps Engineer | Execute tests, track defects, validate acceptance criteria | Daily + Test cycles |
| Business Analyst | Developers, Product Owner | Clarify requirements, validate delivered functionality | As needed + Sprint review |
| DevOps Engineer | Developers, QA Lead | Deploy to test environments, troubleshoot infrastructure | Daily + Deployments |
| Project Manager | All roles | Track progress, manage risks, remove blockers | Daily standups + Weekly sync |
| Change Manager | Project Manager, All team leads | Review and approve change requests | Weekly change board |

### Release & Deployment Phase

| Role | Collaborates With | Purpose | Frequency |
|------|-------------------|---------|-----------|
| QA Lead | Product Owner, DevOps Engineer | Final quality gate, sign-off for production | Pre-release |
| DevOps Engineer | Developers, QA Lead, Project Manager | Execute deployment, monitor production health | Release window |
| Product Owner | QA Lead, Project Manager | Final acceptance and go/no-go decision | Pre-release |
| Change Manager | Project Manager, DevOps Engineer | Validate all changes are approved and documented | Pre-release |
| Project Manager | All roles | Coordinate release activities, communicate status | Release window |

### Retrospective Phase

| Role | Collaborates With | Purpose | Frequency |
|------|-------------------|---------|-----------|
| Project Manager | All roles | Facilitate retrospective, capture learnings | End of sprint/project |
| All roles | Each other | Share feedback, identify improvements | End of sprint/project |

---

## Key Hand-off Points

### Requirements to Development
- **From**: Business Analyst / Product Owner
- **To**: Developers
- **Artifacts**: Refined user stories, acceptance criteria, designs
- **Quality Gate**: Backlog refinement completed, stories meet Definition of Ready

### Development to Testing
- **From**: Developers
- **To**: QA Lead
- **Artifacts**: Code in test environment, PR with test instructions
- **Quality Gate**: Code review approved, unit tests passing, deployment successful

### Testing to Acceptance
- **From**: QA Lead
- **To**: Product Owner
- **Artifacts**: Test results, defect status, acceptance test evidence
- **Quality Gate**: All acceptance tests passed, critical defects resolved

### Acceptance to Deployment
- **From**: Product Owner / QA Lead
- **To**: DevOps Engineer
- **Artifacts**: Approved release package, deployment runbook
- **Quality Gate**: Product Owner sign-off, change approval obtained

### Change Request Flow
- **Initiator**: Any role
- **To**: Change Manager
- **To**: Project Manager + relevant team leads
- **To**: Approval authority (Project Manager / Product Owner / Sponsor)
- **Back to**: Originator with decision and impact assessment

---

## Communication Responsibility Matrix (RACI)

### Key Activities

| Activity | PM | PdM | PO | Dev | QA Lead | BA | DevOps | Change Mgr |
|----------|----|----|----|----|---------|----|---------|----|
| Project Planning | **R** | C | C | I | C | C | C | I |
| Requirement Elicitation | C | C | C | I | I | **R** | I | I |
| Backlog Prioritization | C | A | **R** | C | I | C | I | I |
| Sprint Planning | **R** | I | A | C | C | C | C | I |
| Feature Development | C | I | C | **R** | I | C | C | I |
| Test Planning | C | I | C | C | **R** | I | C | I |
| Change Evaluation | C | C | C | C | C | C | C | **R** |
| Deployment | C | I | I | C | C | I | **R** | C |
| Release Sign-off | C | I | **A** | I | C | I | C | C |
| Risk Management | **R** | C | C | C | C | C | C | C |

**Legend:**
- **R** = Responsible (does the work)
- **A** = Accountable (final authority/approval)
- **C** = Consulted (provides input)
- **I** = Informed (kept updated)

---

## Escalation Paths

### Technical Issues
Developer → QA Lead / DevOps Engineer → Project Manager → Product Manager / Sponsor

### Requirement Clarity
Developer → Business Analyst → Product Owner → Product Manager

### Scope Changes
Any role → Change Manager → Project Manager + Product Owner → Sponsor (if needed)

### Quality Concerns
QA Lead → Project Manager + Product Owner → Product Manager / Sponsor

### Resource Constraints
Project Manager → Product Manager / Resource Manager → Sponsor

---

## Meeting Cadence by Role

### Daily Participation
- **Project Manager**: Daily standup (facilitate)
- **Developers**: Daily standup
- **QA Lead**: Daily standup, daily test coordination with developers
- **DevOps Engineer**: As needed for standup, daily infrastructure monitoring

### Weekly Participation
- **Project Manager**: All weekly meetings (facilitate)
- **Product Manager**: Weekly PM + PdM sync, weekly stakeholder update
- **Product Owner**: Weekly backlog refinement, sprint planning, sprint review
- **Business Analyst**: Weekly requirement review, backlog refinement
- **Change Manager**: Weekly change review board
- **QA Lead**: Weekly test status review
- **DevOps Engineer**: Weekly infrastructure review

### Sprint/Milestone Events
- **All roles**: Sprint planning, sprint review, retrospective (as applicable)

---

## Tips for Effective Collaboration

1. **Establish Clear Owners**: Every artifact and decision should have a clear owner
2. **Document Hand-offs**: Use checklists and quality gates to ensure nothing is missed
3. **Over-communicate**: When in doubt, share information with relevant stakeholders
4. **Use Asynchronous Updates**: Leverage project boards, documentation, and status updates
5. **Respect Role Boundaries**: Understand who has authority to make which decisions
6. **Create Feedback Loops**: Regularly validate that collaboration patterns are working

---

## Related Documents
- [OctoAcme Roles and Personas](./octoacme-roles-and-personas.md)
- [OctoAcme Project Management Overview](./octoacme-project-management-overview.md)
- [OctoAcme Execution and Tracking](./octoacme-execution-and-tracking.md)
