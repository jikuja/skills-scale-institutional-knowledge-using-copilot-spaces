# OctoAcme — Cross-Functional Collaboration Guide

## Purpose
Clarify how different roles and personas interact, communicate, and share responsibility across the project lifecycle. This guide reduces silos and ensures alignment across Product, Engineering, Design, Research, Operations, and Support.

## Overview
Successful projects require seamless collaboration between multiple specialized roles. This document maps key interaction points, communication cadences, and decision-making responsibilities across the OctoAcme project lifecycle.

---

## Interaction Matrix: Key Touchpoints by Phase

### Project Initiation
| Primary | Collaborators | Activity |
|---------|--------------|----------|
| **PM + Product Manager** | Executive Sponsor, Stakeholders | Define problem, success metrics, and business case |
| **Product Manager** | User Researcher | Validate customer need and assumptions |
| **Project Manager** | PM, Team Leads | Identify resource needs and dependencies |
| **Executive Sponsor** | Project Manager, Product Manager | Approve project charter and funding |

### Project Planning
| Primary | Collaborators | Activity |
|---------|--------------|----------|
| **Product Manager** | Developers, Designer, QA | Prioritize backlog and define acceptance criteria |
| **Designer** | Product Manager, User Researcher | Validate design direction and user flows |
| **Developers** | Designer, DevOps Engineer | Identify technical feasibility and infrastructure needs |
| **Project Manager** | All Leads | Create timeline, estimate, and identify dependencies |
| **Security Lead** | Product Manager, Developers | Assess security requirements and design controls |

### Design & Development
| Primary | Collaborators | Activity |
|---------|--------------|----------|
| **Designer** | User Researcher, Developers, QA | Refine design; conduct reviews; provide specs to engineering |
| **Developers** | Designer, QA, DevOps Engineer, Security Lead | Implement features; seek design/spec clarity; ensure buildability |
| **User Researcher** | Designer, Product Manager | Validate design assumptions; conduct usability testing |
| **QA** | Developers, Product Manager | Define test strategy; review acceptance criteria |
| **DevOps Engineer** | Developers, Security Lead | Prepare environments; integrate security scanning |

### Testing & Quality
| Primary | Collaborators | Activity |
|---------|--------------|----------|
| **QA** | Developers, Product Manager, Support Lead | Execute test plans; verify acceptance criteria; identify defects |
| **Developers** | QA, Designer | Address defects and edge cases |
| **Product Manager** | QA, Designer | Validate feature completeness and usability |
| **Support Lead** | QA, Developers | Prepare support materials and known issues list |

### Release & Deployment
| Primary | Collaborators | Activity |
|---------|--------------|----------|
| **DevOps Engineer** | Developers, QA, Security Lead | Coordinate deployment; run smoke tests; monitor health |
| **Project Manager** | All Leads, Stakeholders | Communicate release status and timelines |
| **Support Lead** | Product Manager, Developers | Prepare customer communications and incident response |
| **Security Lead** | DevOps Engineer, Developers | Verify security controls and compliance checks |

### Incident Response & Rollback
| Primary | Collaborators | Activity |
|---------|--------------|----------|
| **DevOps Engineer + On-call** | Developers, Security Lead, Support Lead | Triage and respond to critical incidents |
| **Support Lead** | DevOps Engineer, Product Manager | Communicate incident status to customers |
| **Project Manager** | All Leads | Coordinate post-incident review and action items |

---

## Communication Protocols by Role Pair

### Product Manager ↔ Project Manager
- **Weekly 1:1**: review priorities, timeline, and blockers
- **Decision gates**: scope changes, timeline adjustments
- **Artifacts**: backlog updates, risk register, stakeholder communications

### Developers ↔ Designer
- **Design review sessions**: before and during implementation
- **Spec documentation**: detailed component specs and design rationale
- **Code review**: ensure implementation matches design intent
- **Design debt tracking**: document deviations and rationale

### Developers ↔ QA
- **Acceptance criteria review**: ensure testability before starting work
- **Test case collaboration**: developers provide test data and scenarios
- **Defect triage**: prioritize and address quality issues
- **Automation planning**: discuss test automation opportunities

### Product Manager ↔ User Researcher
- **Research prioritization**: align on what questions to answer
- **Insights sharing**: regular reviews of research findings
- **Assumption validation**: plan studies to test key hypotheses
- **Roadmap impact**: incorporate user research into prioritization

### DevOps Engineer ↔ Developers
- **Infrastructure reviews**: ensure application meets production readiness
- **CI/CD feedback**: surface build/deploy issues early
- **Monitoring integration**: agree on metrics and alerting
- **Performance optimization**: collaborate on scaling and efficiency

### Support Lead ↔ Product Manager
- **Customer feedback loops**: regular syncs on support trends and pain points
- **Feature requests**: prioritize customer-requested improvements
- **Known issues**: communicate product limitations and workarounds
- **Release readiness**: prepare support team for new features

### Security Lead ↔ All Technical Roles
- **Security reviews**: code and architecture reviews during development
- **Threat assessment**: identify and mitigate risks early
- **Compliance checks**: ensure adherence to standards and policies
- **Incident response**: coordinate response to security events

### Project Manager ↔ Executive Sponsor
- **Monthly/milestone briefings**: update on progress, risks, and metrics
- **Escalation coordination**: surface business-impacting decisions
- **Stakeholder management**: represent project interests
- **Resource approval**: request additional capacity or budget as needed

---

## Dependency Management Across Roles

### Critical Dependencies
- **Designer → Developers**: design specs and component library must be ready before dev starts
- **Product Manager → User Researcher**: research must inform prioritization before planning
- **DevOps Engineer → Developers**: infrastructure and CI/CD must support deployment before release
- **QA → Product Manager**: acceptance criteria must be clear before testing begins
- **Security Lead → DevOps Engineer**: security controls must be integrated into deployment pipeline

### Mitigation Strategies
- **Overlap phases**: Designer reviews design with Developers during planning to identify blockers early
- **Pre-planning research**: conduct user research during initiation to inform planning phase
- **Infrastructure staging**: DevOps Engineer sets up environments early so Developers can begin testing
- **Definition of Ready**: require product manager sign-off on acceptance criteria before backlog items enter "Ready" state
- **Security early**: Security Lead participates in design reviews, not just code review

---

## Decision Authority & Escalation

### Product Decisions
- **Authority**: Product Manager (with stakeholder input)
- **Escalation**: to Product Lead if conflicting customer/business requirements

### Technical Decisions
- **Authority**: Tech Lead / Lead Developer (within design guidelines)
- **Escalation**: to Architect/CTO if significant trade-offs; to Product Manager if impacts roadmap

### Timeline & Resource Decisions
- **Authority**: Project Manager (with PM and Team Lead input)
- **Escalation**: to Executive Sponsor if impacts business commitments

### Security & Compliance Decisions
- **Authority**: Security Lead (with team input)
- **Escalation**: to Executive Sponsor if business impact or policy violation

### Critical Issues
- **Authority**: Project Manager (with relevant Leads)
- **Escalation**: to Executive Sponsor if business-impacting

---

## Collaboration Best Practices

### 1. Start with Shared Understanding
- Begin each phase with a kickoff that includes all key personas
- Document assumptions, success criteria, and dependencies together
- Use a single source of truth (project README or charter) for context

### 2. Asynchronous Communication First
- Document decisions and findings in shared spaces (GitHub, wiki, design tools)
- Use PRs and design reviews as async feedback loops
- Schedule synchronous meetings only when decisions require real-time discussion

### 3. Early Feedback, Frequent Iteration
- Designer shares early prototypes with Developers and QA for feasibility feedback
- Developers share architecture decisions with Security Lead early
- QA reviews acceptance criteria during planning, not during testing

### 4. Clear Handoffs & Accountability
- Use checklists and templates to ensure nothing is missed
- Document who is responsible for each activity
- Confirm receipt and understanding before moving to next phase

### 5. Celebrate Cross-Functional Wins
- Highlight how collaboration led to better outcomes
- Include cross-functional participants in demos and retrospectives
- Recognize effort from often-overlooked roles (QA, DevOps, Security, Support)

---

## Monitoring Collaboration Health

### Signals of Good Collaboration
- ✅ Minimal surprises in testing, deployment, or post-release
- ✅ Few escalations or blocked dependencies
- ✅ Team retrospectives identify incremental improvements, not systemic issues
- ✅ Cross-functional feedback in PRs and reviews
- ✅ Roles feel heard and valued in decision-making

### Signals of Collaboration Breakdown
- ❌ Frequent rework due to missed requirements or design changes
- ❌ QA finds issues acceptance criteria should have caught
- ❌ Deployment blocked by infrastructure or security concerns
- ❌ Roles working in silos with limited visibility to each other
- ❌ Escalations due to miscommunication or misaligned expectations

### Improvement Cycle
- Review collaboration health monthly in retrospectives
- Identify bottlenecks and add them to the risk register
- Test interventions (e.g., earlier reviews, new sync cadence)
- Measure impact and iterate

---

## Using This Guide
- Reference the **Interaction Matrix** during project planning to identify who needs to be involved in each phase
- Use **Communication Protocols** to structure team meetings and async workflows
- Consult **Dependency Management** during risk reviews to identify and mitigate collaboration risks
- Apply **Collaboration Best Practices** to team working agreements and retrospectives