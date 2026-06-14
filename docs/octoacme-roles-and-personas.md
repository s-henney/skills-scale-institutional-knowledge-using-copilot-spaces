# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

---

## Core Product & Delivery Roles

## Developers

### Role Summary
Developers design, build, test, and deliver software components. They collaborate with product and project leads to implement features that meet acceptance criteria and quality standards.

### Responsibilities
- Implement features and fixes to meet acceptance criteria
- Write and maintain tests and documentation
- Participate in design and code reviews
- Assist in estimating and planning work
- Help identify technical risks and propose mitigations
- Collaborate on system design and architecture decisions

### Goals
- Deliver reliable, maintainable code
- Reduce cycle time from idea to production
- Maintain high test coverage and observability

### Typical Communication
- Daily standups and sprint planning
- PR descriptions and code review comments
- Technical design docs when needed
- Architecture discussions with Tech Lead

### Key Interactions
- **Tech Lead**: Receives technical direction and design guidance; escalates blockers and architectural concerns
- **Product Manager**: Clarifies requirements and acceptance criteria; provides user context
- **QA/Testing**: Collaborates on testability and acceptance test design
- **Release Engineer**: Coordinates with deployment and release processes

---

## Product Managers

### Role Summary
Product Managers define what should be built to deliver customer and business value. They own the product vision, prioritize the backlog, and measure outcomes.

### Responsibilities
- Define problem statements and success metrics
- Prioritize the roadmap and backlog
- Collaborate with stakeholders and engineering on trade-offs
- Validate solutions through user research and metrics
- Champion user needs and customer feedback

### Goals
- Maximize customer value and impact
- Make clear, data-driven prioritization decisions
- Ensure product-market fit and usability

### Typical Communication
- Weekly alignment with PM and engineering leads
- Roadmap updates and stakeholder briefings
- Acceptance criteria and feature specs
- User research summaries and customer feedback

### Key Interactions
- **UX Researcher/Designer**: Collaborates on user research and design validation
- **Data Analyst**: Defines success metrics and interprets feature impact
- **Project Manager**: Aligns on prioritization and dependency management
- **Customer Success Liaison**: Incorporates customer feedback into roadmap

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
- Escalate blockers and ensure team unblock

### Goals
- Deliver projects on time and within scope
- Minimize unplanned work and escalations
- Maintain transparency and alignment across stakeholders

### Typical Communication
- Weekly status updates and stakeholder reports
- Risk registers and decision logs
- Coordination via project boards and meeting facilitation
- Cross-team dependency and escalation management

### Key Interactions
- **Engineering Manager**: Coordinates staffing, capacity, and people-related blockers
- **Release Engineer**: Aligns on deployment windows and release readiness
- **SRE**: Incorporates reliability requirements and operational feedback
- **Product Manager**: Prioritizes trade-offs and scope decisions

---

## Extended & Cross-Functional Roles

## Tech Lead

### Role Summary
Tech Leads provide technical direction for the team, own system design decisions, and ensure architectural integrity. They mentor developers and escalate technical risks to stakeholders.

### Responsibilities
- Define system architecture and technical approach
- Own design decisions and trade-offs
- Conduct code and design reviews
- Mentor developers and grow technical capability
- Identify technical risks and propose mitigations
- Ensure code quality, testability, and observability standards
- Partner with Release Engineer and SRE on deployability and reliability

### Goals
- Deliver a scalable, maintainable codebase
- Reduce technical debt and rework
- Enable team to make sound technical decisions

### Typical Communication
- Technical design reviews and architecture discussions
- Code review feedback and mentoring
- Risk escalation to Project Manager
- Collaboration on testability and deployment strategies

### Key Interactions
- **Developers**: Provides technical direction and mentoring; reviews designs and code
- **Product Manager**: Translates requirements into technical solutions; discusses trade-offs
- **Project Manager**: Escalates technical risks and dependencies
- **QA/Testing**: Collaborates on testability and acceptance test strategy
- **Release Engineer**: Partners on deployment architecture and automation
- **SRE**: Works on observability, reliability patterns, and operational requirements

---

## Engineering Manager

### Role Summary
Engineering Managers handle people management, resource planning, and career development. They help unblock team-level organizational issues and align engineering capacity with business priorities.

### Responsibilities
- Manage and develop engineers (hiring, performance, career growth)
- Plan resource allocation and staffing for projects
- Provide performance feedback and 1-on-1 mentoring
- Escalate organizational blockers (e.g., staffing gaps, role conflicts)
- Align team capacity with product and project priorities
- Foster team culture, psychological safety, and learning

### Goals
- Build a high-performing, engaged engineering team
- Align engineering capacity with business goals
- Reduce turnover and improve retention

### Typical Communication
- Regular 1-on-1s with direct reports
- Weekly or bi-weekly syncs with Product Manager and Project Manager
- Team meetings, retrospectives, and skip-level conversations
- Performance reviews and career development planning

### Key Interactions
- **Project Manager**: Coordinates on staffing and capacity planning
- **Product Manager**: Aligns on priorities and helps balance competing demands
- **Developers**: Provides mentoring, performance feedback, and career guidance
- **Tech Lead**: Collaborates on technical growth opportunities

---

## QA / Testing

### Role Summary
QA professionals validate quality and ensure features meet acceptance criteria. They design test strategies, execute tests, and identify defects early in the development cycle.

### Responsibilities
- Design test plans and acceptance test strategies
- Execute manual and automated testing
- Identify and document defects with clear reproduction steps
- Validate acceptance criteria before merging PRs
- Collaborate on test automation and CI/CD pipelines
- Identify edge cases and edge-case coverage gaps

### Goals
- Catch defects early and reduce production issues
- Ensure features meet acceptance criteria
- Enable fast, confidence-building feedback loops

### Typical Communication
- Acceptance test collaboration with developers
- Defect reports and test summary reports
- Definition of Done refinement in sprint planning
- Pre-release smoke test coordination

### Key Interactions
- **Developers**: Collaborates on testability and acceptance criteria
- **Tech Lead**: Discusses test strategy and automation approach
- **Product Manager**: Clarifies acceptance criteria and edge cases
- **Release Engineer**: Validates pre-release smoke tests

---

## Release / Build Engineer

### Role Summary
Release and Build Engineers maintain CI/CD pipelines, manage release automation, and own release verification and rollback procedures. They enable fast, safe deployments.

### Responsibilities
- Build and maintain CI/CD pipelines and automation
- Manage release processes and versioning
- Execute and coordinate deployments
- Own rollback procedures and disaster recovery testing
- Monitor deployment health and alert on failures
- Reduce friction in the build-to-deploy workflow
- Partner with SRE on infrastructure and monitoring

### Goals
- Enable frequent, safe, automated deployments
- Reduce release cycles and time-to-fix
- Minimize deployment-related incidents

### Typical Communication
- Release notes and deployment schedules
- Post-deployment verification and health checks
- Coordination with SRE on infrastructure changes
- Incident escalation and rollback decisions

### Key Interactions
- **Developers**: Ensures build stability and provides CI feedback
- **Project Manager**: Coordinates deployment windows and release timing
- **Tech Lead**: Partners on deployment architecture and automation strategy
- **SRE**: Works together on infrastructure, monitoring, and operational readiness
- **QA/Testing**: Collaborates on smoke test execution and pre-release validation

---

## Site Reliability Engineer (SRE)

### Role Summary
SREs own operational reliability, incident response, and post-production monitoring. They ensure systems are observability, resilient, and degradation paths are well-understood.

### Responsibilities
- Design for reliability, scalability, and fault tolerance
- Establish SLOs, SLIs, and alerting strategies
- Respond to and triage production incidents
- Create and maintain runbooks and incident playbooks
- Perform capacity planning and infrastructure scaling
- Collaborate on observability and logging strategies
- Improve deployment safety through staged rollouts

### Goals
- Maximize system uptime and reliability
- Reduce mean time to resolution (MTTR) for incidents
- Enable data-driven reliability improvements

### Typical Communication
- On-call schedules and incident response channels
- SLO and alerting dashboards
- Post-incident blameless retrospectives
- Infrastructure and reliability requirements in planning

### Key Interactions
- **Release Engineer**: Partners on safe deployment practices and infrastructure readiness
- **Tech Lead**: Collaborates on observability, resilience patterns, and system design
- **Developers**: Provides observability guidance and incident response support
- **Project Manager**: Escalates reliability risks and operational constraints

---

## UX Researcher / Designer

### Role Summary
UX Researchers and Designers conduct user research, create design prototypes, and validate usability. They ensure features are intuitive, accessible, and meet user needs.

### Responsibilities
- Conduct user research and usability testing
- Create wireframes, prototypes, and high-fidelity designs
- Define design systems and component libraries
- Ensure accessibility and inclusive design
- Validate designs with users and iterate
- Provide design and UX guidance to developers

### Goals
- Maximize user satisfaction and usability
- Reduce user friction and support costs
- Establish consistent, accessible design systems

### Typical Communication
- Design reviews and feedback on prototypes
- User research findings and synthesis
- Design specifications and component documentation
- Usability test results and recommendations

### Key Interactions
- **Product Manager**: Collaborates on user research to validate problem hypotheses
- **Developers**: Provides detailed design specs and works through implementation questions
- **QA/Testing**: Collaborates on acceptance criteria and usability validation

---

## Data Analyst / Insights Partner

### Role Summary
Data Analysts define measurement plans, implement instrumentation, and analyze feature impact. They provide dashboards and data-driven insights to inform prioritization.

### Responsibilities
- Define success metrics and measurement strategies
- Implement instrumentation and telemetry
- Analyze feature impact and user behavior
- Build dashboards for real-time insights
- Conduct statistical analysis and A/B testing
- Inform roadmap decisions with data

### Goals
- Enable data-driven product decisions
- Measure and maximize feature impact
- Reduce guesswork in prioritization

### Typical Communication
- Success metrics and instrumentation requirements in planning
- Regular dashboard updates and insights
- Feature impact analysis and reports
- Hypothesis validation and experiment results

### Key Interactions
- **Product Manager**: Collaborates on success metrics and impact analysis
- **Developers**: Works on instrumentation and telemetry implementation
- **Project Manager**: Provides metrics updates for stakeholder reporting

---

## Customer Success / Support Liaison

### Role Summary
Customer Success and Support teams surface customer feedback, validate fixes, and help prioritize high-impact bugs. They are the voice of the customer in project decisions.

### Responsibilities
- Surface customer feedback and pain points
- Validate bug fixes and feature completeness with customers
- Help prioritize issues based on customer impact
- Provide customer context during acceptance testing
- Feed customer insights into product roadmap
- Ensure timely communication of known issues and workarounds

### Goals
- Maximize customer satisfaction and retention
- Reduce customer-impacting bugs in production
- Accelerate feedback loops from customers to product

### Typical Communication
- Customer feedback summaries and impact assessments
- Bug escalation and high-priority issue reporting
- Participation in acceptance testing for customer-impacting features
- Release notes and customer communication

### Key Interactions
- **Project Manager**: Escalates customer-impacting issues and risks
- **Product Manager**: Provides customer feedback and helps prioritize roadmap items
- **Developers**: Provides customer context for issues and validates fixes
- **QA/Testing**: Collaborates on acceptance testing with customer perspective

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- When planning projects, refer to the **Key Interactions** section to identify who needs to be involved and when.
- Use the cross-functional role interaction checklist (see `docs/octoacme-role-interaction-checklist.md`) during project kickoffs to ensure all stakeholders are identified.
