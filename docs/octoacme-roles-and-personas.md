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

### Key Interactions
- **With Product Managers**: clarify requirements and acceptance criteria
- **With Designers**: implement UI/UX designs and provide feedback on feasibility
- **With DevOps Engineers**: collaborate on deployment, monitoring, and infrastructure
- **With QA/Testing**: ensure quality standards and test coverage

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

### Key Interactions
- **With Project Managers**: align on timelines and resource needs
- **With Developers**: discuss trade-offs, feasibility, and technical constraints
- **With User Researchers**: validate assumptions and incorporate customer insights
- **With Designers**: collaborate on user-centered design and prioritization
- **With Support Lead**: incorporate customer feedback and pain points

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

### Key Interactions
- **With Product Managers**: align on priorities and resource allocation
- **With Team Leads (Dev, QA, Design)**: manage capacity and track progress
- **With Executive Sponsor**: escalate blockers and report on milestones
- **With Support Lead**: coordinate communication to impacted customers

---

## Designers

### Role Summary
Designers own user experience and interface design, ensuring solutions are usable, accessible, and aligned with product vision. They bridge customer needs and technical feasibility.

### Responsibilities
- Conduct or incorporate user research into design decisions
- Create wireframes, prototypes, and design systems
- Collaborate with Product and Developers on feasibility and implementation
- Participate in design and code reviews
- Document design decisions and handoff specs to engineering
- Advocate for user experience and accessibility

### Goals
- Deliver intuitive, accessible user experiences
- Reduce friction between customer needs and technical implementation
- Maintain design consistency across products

### Typical Communication
- Design reviews and feedback sessions
- Figma or design tool links in PRs and issues
- Collaboration meetings with Product and Engineering
- Accessibility and usability documentation

### Key Interactions
- **With Product Managers**: validate design against user research and business goals
- **With Developers**: ensure designs are feasible and implementable; provide detailed specs
- **With QA/Testing**: define acceptance criteria for visual and usability testing
- **With User Researchers**: incorporate research findings into design iterations

---

## User Researchers

### Role Summary
User Researchers plan, conduct, and communicate research that informs product decisions. They provide deep insights into customer needs, behaviors, and usability to guide the team.

### Responsibilities
- Plan and conduct user research (interviews, surveys, usability testing, etc.)
- Synthesize findings and communicate insights to the team
- Validate assumptions before and after features are built
- Collaborate with Product and Design on research prioritization
- Advocate for the user's voice in decision-making

### Goals
- Ensure product decisions are grounded in customer reality
- Reduce risk through early validation
- Build empathy and shared understanding across the team

### Typical Communication
- Research reports and findings documents
- Usability testing sessions and demos
- Regular sync meetings with Product and Design
- Insights shared in standups and retrospectives

### Key Interactions
- **With Product Managers**: prioritize research questions that inform roadmap decisions
- **With Designers**: provide design validation and usability insights
- **With Developers**: communicate customer context to guide implementation decisions
- **With Support Lead**: incorporate frontline customer feedback into research

---

## QA / Testing

### Role Summary
QA and Testing professionals ensure product quality, validate acceptance criteria, and identify issues before they reach customers. They partner with the team to build quality into every release.

### Responsibilities
- Define test plans and testing strategies
- Create and maintain automated and manual test cases
- Validate acceptance criteria before marking work as done
- Identify and log defects with clear reproduction steps
- Participate in sprint planning to understand requirements early
- Advise on test coverage and risk assessment

### Goals
- Ensure releases meet quality and acceptance standards
- Identify regressions and edge cases early
- Reduce production incidents and customer-facing issues

### Typical Communication
- Test plans and test case documentation
- Defect reports and triage meetings
- Acceptance criteria walkthroughs
- Quality dashboards and metrics

### Key Interactions
- **With Developers**: clarify acceptance criteria and review implementation for testability
- **With Product Managers**: validate feature completeness and usability
- **With Support Lead**: communicate known issues and workarounds to support team
- **With DevOps Engineers**: coordinate smoke testing and production verification

---

## DevOps Engineer

### Role Summary
DevOps Engineers design, maintain, and optimize the infrastructure, deployment pipelines, and monitoring systems that enable the team to deliver reliably and at scale.

### Responsibilities
- Build and maintain CI/CD pipelines and automation
- Manage cloud infrastructure and environments (dev, staging, production)
- Implement monitoring, logging, and alerting
- Coordinate deployments and manage release processes
- Support incident response and rollback procedures
- Optimize performance, security, and cost of infrastructure

### Goals
- Enable fast, reliable deployments with minimal manual work
- Maintain high system uptime and performance
- Reduce mean time to recovery (MTTR) from incidents

### Typical Communication
- Deployment runbooks and incident response docs
- Infrastructure and cost reports
- Collaboration on CI/CD improvements
- On-call rotations and incident coordination

### Key Interactions
- **With Developers**: advise on buildability, deployability, and observability of code
- **With QA/Testing**: coordinate environment setup and smoke test execution
- **With Project Manager**: communicate deployment windows and infrastructure blockers
- **With Security Lead**: implement security controls and scanning in pipelines

---

## Support Lead

### Role Summary
The Support Lead is the central point of contact between customers and the product team. They coordinate support activities, escalate issues, and ensure customer feedback informs product decisions.

### Responsibilities
- Triage and prioritize customer support requests and issues
- Escalate critical issues to engineering and product teams
- Communicate product updates and workarounds to customers
- Gather and synthesize customer feedback for product team
- Coordinate communication during incidents and outages
- Maintain support documentation and knowledge base

### Goals
- Maintain high customer satisfaction and response times
- Reduce time to resolution for critical issues
- Bridge the gap between customer needs and product decisions

### Typical Communication
- Incident notifications and status updates
- Customer feedback summaries
- Support metrics and trends reports
- Collaboration with Product and Engineering on issue resolution

### Key Interactions
- **With Product Managers**: provide customer feedback and pain points to inform prioritization
- **With Developers**: coordinate on issue investigation, fixes, and workarounds
- **With Project Manager**: communicate customer impact of delays or changes
- **With DevOps Engineer**: coordinate during infrastructure incidents and outages

---

## Security Lead

### Role Summary
The Security Lead identifies, assesses, and mitigates security risks. They advise the team on best practices, coordinate security reviews, and lead incident response.

### Responsibilities
- Conduct security threat assessments and risk analysis
- Review code and architecture for security vulnerabilities
- Advise on secure coding practices and compliance requirements
- Coordinate security scanning in CI/CD pipelines
- Lead security incident response and post-incident reviews
- Stay current on security threats and industry best practices

### Goals
- Prevent security breaches and protect customer data
- Build security into every release and process
- Maintain compliance with security standards and regulations

### Typical Communication
- Security review findings and recommendations
- Incident response and severity assessments
- Security training and best practices documentation
- Compliance and audit reports

### Key Interactions
- **With Developers**: review code for vulnerabilities; provide security guidance
- **With DevOps Engineers**: coordinate security scanning and infrastructure hardening
- **With Product Managers**: advise on security trade-offs and customer data handling
- **With Project Manager**: escalate security blockers and critical findings

---

## Executive Sponsor

### Role Summary
The Executive Sponsor provides strategic oversight, secures organizational support, and removes blockers at the leadership level. They champion the project and ensure it aligns with broader business goals.

### Responsibilities
- Champion the project and secure executive alignment
- Remove organizational blockers and resource constraints
- Approve major decisions and trade-offs
- Participate in key project reviews and decision gates
- Escalate business-impacting issues beyond the team
- Communicate strategic context and business drivers to the team

### Goals
- Ensure project delivers business value and strategic alignment
- Remove barriers to team success
- Maintain executive visibility and stakeholder confidence

### Typical Communication
- Monthly or milestone-based status briefings
- Executive decision meetings
- Escalation and approval processes
- Strategic roadmap alignment

### Key Interactions
- **With Project Manager**: receive status updates and escalations
- **With Product Manager**: align on business goals and prioritization
- **With Team Leads**: communicate strategic context and unblock resources
- **With Stakeholders**: represent project interests and manage expectations

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Refer to "Key Interactions" sections to understand cross-functional collaboration and dependencies.