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

## Business Analyst

### Role Summary
Business Analysts bridge the gap between technical and business teams. They capture requirements, clarify priorities, and translate business needs into technical implementation guidance that developers and engineers can execute.

### Responsibilities
- Elicit and document business requirements from stakeholders
- Translate business needs into technical specifications and user stories
- Facilitate requirement workshops and backlog grooming sessions
- Analyze business processes and identify improvement opportunities
- Create functional specifications, process flows, and data models
- Validate that delivered solutions meet business objectives

### Goals
- Ensure clear, actionable requirements that reduce rework
- Bridge communication gaps between business and technical teams
- Support data-driven decision making with impact analysis
- Maintain alignment between business strategy and technical delivery

### Typical Communication
- Requirement clarification sessions with Product Owner and stakeholders
- Weekly syncs with Project Manager on requirement status and dependencies
- Backlog refinement sessions with Development team
- Regular updates to stakeholders on requirement delivery status

### Key Interactions
- **Product Owner**: Collaborates during backlog grooming to ensure business value is clearly articulated and prioritized
- **Project Manager**: Regular syncs to ensure business goals align with project timelines and communicate requirement changes
- **Developers**: Translates business requirements into technical specifications and clarifies acceptance criteria
- **Product Managers**: Works together to validate requirements match product vision and customer needs

---

## Quality Assurance Lead

### Role Summary
Quality Assurance Leads own and drive testing strategies across the project. They coordinate with developers to ensure deliverables meet quality standards and act as the final gatekeeper before release to production.

### Responsibilities
- Define and maintain test strategies and quality standards
- Plan and coordinate testing activities across sprints and releases
- Lead test case design, execution, and defect tracking
- Perform risk-based testing and prioritize test coverage
- Facilitate test environment setup and data management
- Drive quality metrics reporting and continuous improvement
- Conduct final sign-off before production releases

### Goals
- Ensure high-quality deliverables that meet acceptance criteria
- Minimize production defects and customer-impacting issues
- Optimize test coverage and efficiency
- Foster a culture of quality throughout the development lifecycle

### Typical Communication
- Daily standups to track testing progress and blockers
- Test planning sessions with Project Manager and Developers
- Defect triage meetings with Development team
- Pre-release quality gates and sign-off meetings
- Quality metrics reporting to stakeholders

### Key Interactions
- **Developers**: Coordinates test schedules, reviews test results, and collaborates on defect resolution
- **Project Manager**: Aligns testing activities with project timelines and communicates quality risks
- **DevOps Engineer**: Coordinates test environment setup, deployment validation, and automated test integration
- **Product Owner**: Validates acceptance criteria and confirms quality standards for feature acceptance

---

## Change Manager

### Role Summary
Change Managers oversee change requests throughout the project lifecycle. They ensure all changes are evaluated, approved, and communicated, and that impact analysis is reflected in project planning to minimize disruption.

### Responsibilities
- Manage the change control process and change request log
- Evaluate impact of proposed changes on scope, schedule, and resources
- Facilitate change review board meetings and decision-making
- Ensure proper documentation and approval of all changes
- Communicate approved changes to all affected stakeholders
- Track cumulative change impact on project baseline
- Report change metrics and trends to program leadership

### Goals
- Maintain project stability while enabling necessary adaptations
- Ensure transparent, consistent change evaluation process
- Minimize scope creep and unplanned work
- Maintain clear audit trail of project decisions

### Typical Communication
- Change review board meetings (weekly or as needed)
- Impact assessment discussions with Project Manager and tech leads
- Change notifications to all affected team members
- Monthly change reports to program leadership and sponsors

### Key Interactions
- **Project Manager**: Partners to assess change impact on timelines and resource allocation
- **Product Owner**: Evaluates changes against business priorities and customer value
- **All Team Leads**: Assesses technical and operational impact ahead of major releases
- **Stakeholders**: Communicates change decisions and manages expectations

---

## DevOps Engineer

### Role Summary
DevOps Engineers focus on deployment automation, pipeline efficiency, and infrastructure reliability. They support both development and operations teams to ensure smooth integration, delivery, and production stability.

### Responsibilities
- Design and maintain CI/CD pipelines and deployment automation
- Manage infrastructure as code and environment configurations
- Implement monitoring, logging, and alerting solutions
- Coordinate deployment activities and release orchestration
- Support incident response and production troubleshooting
- Optimize build and deployment performance
- Ensure security and compliance in delivery pipelines

### Goals
- Enable fast, reliable, automated deployments
- Minimize deployment failures and rollback needs
- Maintain high availability and system reliability
- Reduce manual toil through automation

### Typical Communication
- Daily coordination with Development team on build and deployment issues
- Pre-deployment sync with QA Lead on environment readiness
- Infrastructure change notifications to all stakeholders
- Incident retrospectives and post-mortem reviews
- Regular updates on pipeline health and deployment metrics

### Key Interactions
- **Developers**: Provides deployment support, troubleshoots build issues, and collaborates on pipeline improvements
- **Quality Assurance Lead**: Ensures test environment availability and supports deployment validation
- **Project Manager**: Coordinates deployment schedules and communicates infrastructure changes
- **Change Manager**: Ensures infrastructure and deployment changes follow change control process

---

## Product Owner

### Role Summary
Product Owners represent the voice of the customer and business stakeholders. They prioritize the backlog based on business value, make final decisions on feature acceptance, and ensure the product delivers maximum value to users and the organization.

### Responsibilities
- Own and prioritize the product backlog
- Define and communicate product vision and strategy
- Make final acceptance decisions on delivered features
- Balance competing priorities and stakeholder needs
- Represent customer needs and market requirements
- Collaborate with Product Manager on roadmap planning
- Facilitate backlog refinement and sprint planning

### Goals
- Maximize business value delivered in each release
- Ensure product features meet customer needs and expectations
- Maintain clear, actionable, and prioritized backlog
- Drive product success through strategic prioritization

### Typical Communication
- Sprint planning and backlog refinement sessions
- Daily availability for clarification questions from team
- Weekly alignment with Product Manager and Project Manager
- Sprint reviews to accept or reject delivered features
- Stakeholder updates on backlog priorities and trade-offs

### Key Interactions
- **Product Manager**: Aligns on product strategy, roadmap, and success metrics
- **Business Analyst**: Collaborates during backlog grooming to ensure business requirements are properly captured
- **Developers**: Clarifies acceptance criteria and provides timely feedback on delivered work
- **Project Manager**: Balances priorities with project constraints and timelines
- **Quality Assurance Lead**: Validates acceptance criteria and participates in final feature sign-off

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

