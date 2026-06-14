# OctoAcme — Cross-Functional Role Interaction Checklist

## Purpose
Provide a structured checklist to ensure all relevant cross-functional roles are identified, informed, and coordinated during project phases.

## When to Use
- **Project Kickoff**: Ensure all stakeholders are identified and communication plans are established
- **Planning & Design**: Confirm technical, design, and reliability considerations are incorporated
- **Execution**: Verify ongoing coordination and escalation paths are clear
- **Release**: Confirm operational and customer-facing teams are prepared

---

## Project Initiation & Kickoff

### Core Product & Delivery
- [ ] **Project Manager** assigned and has created project charter / one-pager
- [ ] **Product Manager** defined problem statement, success metrics, and initial roadmap
- [ ] **Tech Lead** identified and involved in technical approach discussion
- [ ] **Engineering Manager** confirmed team staffing and capacity
- [ ] **Developers** (key contributors) present and understand scope

### Extended & Cross-Functional
- [ ] **UX Researcher/Designer** involved if feature has user-facing changes
- [ ] **Data Analyst** defined success metrics and measurement strategy
- [ ] **Customer Success Liaison** provided customer context and known pain points
- [ ] **QA/Testing** understands acceptance criteria and has provided initial test strategy
- [ ] **Release Engineer** aware of release timeline and any special deployment needs
- [ ] **SRE** identified reliability and operational requirements

### Outputs
- [ ] Stakeholder list created with contact info and role descriptions
- [ ] Communication cadence established (standups, syncs, reviews)
- [ ] Decision escalation paths documented
- [ ] Risk register initiated with cross-team dependencies

---

## Planning & Design Phase

### Requirements & Design
- [ ] **Product Manager** has prioritized backlog with clear acceptance criteria
- [ ] **Tech Lead** has reviewed technical approach and identified risks
- [ ] **UX Researcher/Designer** has validated design with users (if applicable)
- [ ] **Data Analyst** has instrumentation plan defined
- [ ] **QA/Testing** has contributed to acceptance criteria and test strategy

### Operational & Deployment
- [ ] **Release Engineer** has confirmed deployment approach and dependencies
- [ ] **SRE** has documented reliability requirements and SLOs
- [ ] **Tech Lead** has collaborated with SRE on observability and resilience patterns
- [ ] **Engineering Manager** confirmed team capacity and skill fit for planned work

### Stakeholder & Customer
- [ ] **Customer Success Liaison** reviewed acceptance criteria for customer impact
- [ ] **Project Manager** identified cross-team dependencies and risks
- [ ] **Product Manager** and **Engineering Manager** aligned on priority and trade-offs

### Outputs
- [ ] Sprint backlog or iteration plan finalized
- [ ] Definition of Done includes quality, testing, and deployment criteria
- [ ] Dependency map created (cross-team and technical)
- [ ] Risk register updated with mitigation plans
- [ ] Release plan and timeline confirmed with Release Engineer and SRE

---

## Execution Phase

### Daily Coordination
- [ ] **Daily standups** include representation from Dev, QA, Release Engineer (if needed)
- [ ] **Tech Lead** available for design reviews and technical decisions
- [ ] **Project Manager** tracking blockers and escalating as needed
- [ ] **Engineering Manager** aware of team challenges and supporting unblock

### Quality & Validation
- [ ] **QA/Testing** actively validating features against acceptance criteria
- [ ] **Developers** incorporating UX Researcher feedback and QA findings
- [ ] **Data Analyst** implementing instrumentation alongside feature work
- [ ] **SRE** engaged if reliability or operational changes are detected

### Risk Management
- [ ] **Project Manager** updating risk register weekly
- [ ] **Tech Lead** escalating technical risks and blockers
- [ ] **Engineering Manager** escalating people/capacity risks
- [ ] **Customer Success Liaison** surfacing customer-impacting issues

### Outputs
- [ ] Feature branches and PRs include clear descriptions and acceptance criteria
- [ ] Code reviews involve Tech Lead and peer developers
- [ ] QA sign-off documented before merge
- [ ] Risk register updated with emerging issues
- [ ] Weekly status provided to stakeholders

---

## Pre-Release Phase

### Quality & Readiness
- [ ] **QA/Testing** completed smoke tests and acceptance validation
- [ ] **Tech Lead** confirmed code quality and design adherence
- [ ] **Developers** reviewed and resolved all QA findings
- [ ] **Data Analyst** confirmed instrumentation is in place and working

### Operational Readiness
- [ ] **Release Engineer** confirmed deployment plan and automation
- [ ] **SRE** validated monitoring, alerting, and runbooks are ready
- [ ] **Tech Lead** collaborated with Release Engineer and SRE on deployment strategy
- [ ] **Project Manager** confirmed communication and rollback plans

### Stakeholder Readiness
- [ ] **Product Manager** finalized release notes and announcement
- [ ] **Customer Success Liaison** prepared customer communication and support guidance
- [ ] **Engineering Manager** confirmed team availability for deployment support
- [ ] **Project Manager** scheduled deployment window and notified stakeholders

### Outputs
- [ ] Release notes created and reviewed
- [ ] Deployment runbook prepared and tested
- [ ] Rollback procedure documented
- [ ] Customer communication drafted
- [ ] On-call schedule confirmed for post-deployment support
- [ ] Pre-release checklist signed off by Tech Lead, QA, Release Engineer, and SRE

---

## Release & Deployment Phase

### Deployment Execution
- [ ] **Release Engineer** executing deployment with pre-planned process
- [ ] **SRE** monitoring health and alerting on anomalies
- [ ] **Tech Lead** available for technical escalation
- [ ] **Project Manager** coordinating communication and status updates

### Post-Deployment Validation
- [ ] **QA/Testing** executing post-deployment smoke tests
- [ ] **Data Analyst** confirming instrumentation is working and capturing correct data
- [ ] **SRE** validating SLOs and performance metrics
- [ ] **Customer Success Liaison** confirming with key customers that feature works as expected

### Incident Response (if needed)
- [ ] **Project Manager** activates incident response protocol
- [ ] **Tech Lead** involved in root cause triage
- [ ] **Release Engineer** prepared with rollback if necessary
- [ ] **SRE** leading incident response and communication
- [ ] **Engineering Manager** supporting team during incident

### Outputs
- [ ] Deployment verification sign-off from QA and SRE
- [ ] Release announcement sent to stakeholders and customers
- [ ] Post-deployment metrics tracked and reviewed
- [ ] Incident log (if any) created with action items

---

## Post-Release & Retrospective Phase

### Learning & Improvement
- [ ] **Project Manager** schedules and facilitates retrospective
- [ ] **All key roles** participate (Product Manager, Tech Lead, Developers, QA, Release Engineer, SRE, etc.)
- [ ] **Data Analyst** presents feature impact and key metrics
- [ ] **Customer Success Liaison** shares customer feedback and issues

### Continuous Improvement
- [ ] **Action items** identified with clear owners and due dates
- [ ] **Tech Lead** captures technical learnings and refactoring opportunities
- [ ] **SRE** documents reliability learnings and updates runbooks
- [ ] **Product Manager** incorporates feedback into future prioritization
- [ ] **Release Engineer** identifies CI/CD improvements

### Outputs
- [ ] Retrospective notes documented and shared
- [ ] Action items added to backlog or risk register
- [ ] Metrics summary prepared for stakeholders
- [ ] Team celebration / recognition for successful delivery

---

## Role Interaction Matrix

| Role | Kickoff | Planning | Execution | Pre-Release | Release | Post-Release |
|------|---------|----------|-----------|-------------|---------|---------------|
| **Product Manager** | ✓ Lead | ✓ Lead | ✓ Consult | ✓ Support | Support | ✓ Lead |
| **Project Manager** | ✓ Lead | ✓ Facilitate | ✓ Lead | ✓ Lead | ✓ Lead | ✓ Facilitate |
| **Tech Lead** | ✓ Participate | ✓ Lead | ✓ Lead | ✓ Lead | Support | ✓ Participate |
| **Developers** | ✓ Participate | ✓ Participate | ✓ Lead | Support | Support | ✓ Participate |
| **QA / Testing** | ✓ Participate | ✓ Participate | ✓ Lead | ✓ Lead | ✓ Lead | ✓ Participate |
| **Engineering Manager** | ✓ Participate | ✓ Participate | Support | Support | Support | ✓ Participate |
| **UX Researcher / Designer** | Support | ✓ Participate | ✓ Consult | Support | — | Support |
| **Data Analyst** | Support | ✓ Participate | ✓ Participate | ✓ Verify | ✓ Verify | ✓ Lead |
| **Release Engineer** | Support | ✓ Participate | Support | ✓ Lead | ✓ Lead | ✓ Participate |
| **SRE** | Support | ✓ Participate | Support | ✓ Lead | ✓ Lead | ✓ Participate |
| **Customer Success Liaison** | ✓ Provide Context | Support | ✓ Feedback | ✓ Prepare | Support | ✓ Lead Feedback |

**Legend**: ✓ Lead = Drives; ✓ Facilitate = Coordinates; ✓ Participate = Active involvement; Consult = Input on decision; Support = Available if needed; — = Not typically involved

---

## Using This Checklist in Your Projects

1. **Customize for Your Context**: Not all projects require all roles. Use this as a template and adapt based on your team structure.
2. **Assign Owners**: For each section, assign a primary owner (usually the Project Manager) to ensure items are tracked.
3. **Review Regularly**: Check the checklist weekly during planning and execution phases.
4. **Adapt Over Time**: After each project, reflect on which interactions were most valuable and which can be streamlined.
5. **Escalate Gaps**: If a role is missing or unavailable, escalate to Engineering Manager or Product Manager for trade-off discussion.
