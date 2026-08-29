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

## QA/Testing Lead

### Role Summary
QA/Testing Leads define quality standards, develop test strategies, and validate that features meet acceptance criteria before release. They work closely with developers and product managers to ensure software quality across all project phases.

### Responsibilities
- Define test strategy and approach for each feature or release
- Execute acceptance testing and validate acceptance criteria compliance
- Conduct end-to-end and integration testing before release
- Create and maintain test cases and automation frameworks
- Identify and document bugs with clear reproduction steps
- Collaborate on quality gates and release readiness assessments
- Validate security scanning and compliance checks before deployment

### Goals
- Ensure features meet quality standards and acceptance criteria before release
- Reduce production defects and customer-impacting issues
- Build reliable, testable software through early collaboration
- Establish consistent quality metrics and reporting

### Typical Communication
- Sprint planning and refinement sessions (input on testability)
- Daily standups and test status updates
- Acceptance criteria reviews with Product Managers and Developers
- Pre-release verification meetings and deployment checklists
- Quality metrics and test coverage reports

### Interaction with Other Roles
- **With Developers**: Reviews acceptance criteria for testability, provides test feedback, collaborates on test design and automation
- **With Product Managers**: Validates acceptance criteria clarity, supports definition of quality standards, reports on release readiness
- **With Project Managers**: Communicates blockers and risks related to testing, updates timeline if additional testing is needed
- **With Security/Compliance Officer**: Coordinates on security test scenarios and compliance validation

---

## Stakeholder/Sponsor

### Role Summary
Stakeholders and Sponsors provide business context, strategic alignment, and authoritative approval for project scope, budget, and major decisions. They ensure projects deliver business value and stay aligned with organizational priorities.

### Responsibilities
- Define business requirements and success metrics
- Provide strategic context and business justification for projects
- Review and approve project charter, scope, and budget
- Participate in key milestone reviews and go/no-go decisions
- Escalate business-impacting risks and blockers
- Receive and act on regular project status updates
- Approve scope changes and manage expectations with other stakeholders

### Goals
- Ensure projects deliver measurable business value
- Maintain alignment with organizational strategy and priorities
- Minimize scope creep and timeline overruns
- Enable informed decision-making at critical project gates

### Typical Communication
- Project kickoff and approval meetings
- Monthly or milestone-based status updates
- Escalation and decision gate reviews
- Budget and resource approval meetings
- Stakeholder updates and announcements

### Interaction with Other Roles
- **With Project Managers**: Reviews status, approves scope changes, escalates decisions
- **With Product Managers**: Validates business value and success metrics, approves roadmap prioritization
- **With Developers and QA**: Reviews progress, receives demo updates at milestones
- **With Security/Compliance Officer**: Approves security and compliance requirements and trade-offs

---

## Scrum Master / Agile Coach

### Role Summary
Scrum Masters and Agile Coaches facilitate agile ceremonies, remove impediments, and coach teams on agile best practices. They enable continuous improvement and optimize team velocity and collaboration.

### Responsibilities
- Facilitate sprint ceremonies (planning, standups, reviews, retrospectives)
- Identify and help remove team impediments and blockers
- Coach team on agile principles, practices, and ceremony effectiveness
- Track and monitor team metrics (velocity, burndown, cycle time)
- Drive continuous improvement initiatives based on retrospectives
- Protect team from external interruptions and scope creep
- Foster psychological safety and encourage knowledge sharing

### Goals
- Optimize team velocity and delivery predictability
- Build a culture of continuous improvement and learning
- Reduce cycle time and improve time-to-market
- Increase team collaboration and psychological safety

### Typical Communication
- Daily standups (facilitation and coaching)
- Sprint planning and retrospective facilitation
- One-on-ones with team members (coaching and support)
- Metrics and trends reports to Project Manager and Product Manager
- Process improvement discussions and follow-up on action items

### Interaction with Other Roles
- **With Project Managers**: Escalates blockers and risks, provides team metrics and health updates
- **With Product Managers**: Communicates capacity and velocity trends, supports backlog refinement facilitation
- **With Developers and QA**: Coaches on agile practices, removes impediments, facilitates collaboration
- **With Stakeholders**: Communicates delivery predictability and team capacity constraints

---

## Security/Compliance Officer

### Role Summary
Security and Compliance Officers ensure projects meet security requirements and compliance standards. They collaborate on risk assessment, validate security practices, and oversee incident response processes.

### Responsibilities
- Define security requirements and compliance standards for projects
- Review architectural designs for security risks
- Coordinate security scanning and penetration testing
- Validate compliance with regulatory requirements (e.g., data protection, accessibility)
- Approve deployment and release readiness from security perspective
- Manage incident response and coordinate post-incident reviews
- Maintain security and compliance documentation and training

### Goals
- Ensure projects meet security and compliance requirements before production
- Reduce security vulnerabilities and compliance gaps
- Build security into development processes from inception
- Enable rapid, secure incident response

### Typical Communication
- Project planning and security requirements discussion
- Architecture reviews and security design meetings
- Pre-release security validation and approval
- Security scanning and vulnerability reports
- Incident response and post-incident retrospectives

### Interaction with Other Roles
- **With Developers**: Collaborates on security design, reviews code for vulnerabilities, provides security best practices guidance
- **With QA/Testing Lead**: Coordinates on security test scenarios and compliance validation in acceptance testing
- **With Project Managers**: Escalates security risks, communicates timeline impact of security activities
- **With Stakeholders/Sponsors**: Reports on security posture and compliance status, escalates critical vulnerabilities

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
