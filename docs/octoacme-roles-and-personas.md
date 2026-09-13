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

### Interactions with Other Roles
- **Technical Lead**: Receives mentoring, code review feedback, and architecture guidance
- **QA Lead**: Collaborates on test automation and testability improvements
- **DevOps Engineer**: Coordinates on CI/CD pipelines and deployment procedures
- **Security Lead**: Implements security requirements and participates in security reviews
- **Project Manager**: Provides estimates, status updates, and identifies blockers
- **Product Manager**: Receives acceptance criteria and clarification on requirements

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

### Interactions with Other Roles
- **Project Manager**: Partners on schedule, planning, and stakeholder communication
- **Developers**: Communicates requirements, acceptance criteria, and provides clarification
- **QA Lead**: Defines quality acceptance criteria and validates feature completeness
- **Technical Lead**: Discusses feasibility, trade-offs, and technical constraints
- **Security Lead**: Incorporates security requirements and compliance needs
- **Stakeholders**: Gathers requirements and provides regular updates on progress

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

### Interactions with Other Roles
- **Product Manager**: Partners on roadmap, prioritization, and stakeholder alignment
- **Technical Lead**: Identifies technical dependencies, risks, and feasibility concerns
- **Developers**: Tracks progress, manages sprint planning, and escalates blockers
- **QA Lead**: Coordinates release planning and quality sign-off timelines
- **DevOps Engineer**: Coordinates deployment schedules and release procedures
- **Security Lead**: Integrates security reviews into project timeline
- **Stakeholders**: Provides regular updates and manages expectations

---

## Quality Assurance Lead / Test Lead

### Role Summary
The QA Lead owns the test strategy, ensures quality acceptance criteria are met, and coordinates validation efforts throughout the project lifecycle. They work closely with developers and product managers to ensure deliverables meet quality standards before release.

### Responsibilities
- Define test strategy and quality acceptance criteria aligned with business requirements
- Plan and execute testing activities (unit, integration, end-to-end, regression)
- Validate acceptance criteria before marking work as "Done"
- Track and triage quality issues and regressions
- Collaborate with developers on testability and test automation
- Report quality metrics and risk status to PM and stakeholders
- Coordinate testing efforts across teams for cross-functional dependencies

### Goals
- Ensure all deliverables meet defined quality standards
- Reduce production defects and rework cycles
- Enable rapid, confident releases
- Build quality into the development process, not just at the end

### Typical Communication
- Quality status in weekly syncs and standups
- Test reports and risk assessments
- Quality acceptance sign-off before release
- Test strategy discussions and automation planning

### Interactions with Other Roles
- **Developers**: Collaborates on test automation, test coverage, and testability improvements
- **Product Manager**: Aligns on acceptance criteria and quality expectations
- **Project Manager**: Coordinates testing timelines and quality gates in the schedule
- **Technical Lead**: Discusses testing architecture and quality standards
- **DevOps Engineer**: Coordinates automated testing in CI/CD pipelines
- **Security Lead**: Incorporates security testing into the test strategy

---

## Technical Lead / Architect

### Role Summary
The Technical Lead makes key architectural and design decisions, mentors developers, and ensures technical quality and maintainability. They balance innovation with pragmatism, reducing technical debt while enabling rapid delivery.

### Responsibilities
- Lead technical design and architecture reviews
- Mentor developers and review code quality
- Identify and manage technical debt and risk
- Ensure alignment with existing systems and standards
- Support estimation and feasibility assessments
- Advocate for maintainability and testing practices
- Make trade-off decisions between speed, quality, and scalability

### Goals
- Deliver scalable, maintainable, and performant solutions
- Build team capability and code quality
- Reduce long-term technical risk and rework
- Establish and maintain technical standards and best practices

### Typical Communication
- Technical design reviews and architecture decisions
- Code review feedback and mentoring
- Technical risk identification and mitigation
- Feasibility assessments and estimation support

### Interactions with Other Roles
- **Developers**: Mentors, provides architectural guidance, and conducts code reviews
- **Product Manager**: Discusses feasibility and technical trade-offs impacting features
- **Project Manager**: Identifies technical dependencies, risks, and effort estimates
- **QA Lead**: Collaborates on testability, test automation architecture, and quality standards
- **DevOps Engineer**: Designs for deployability and operational stability
- **Security Lead**: Ensures security is built into the architecture from the start

---

## DevOps / Infrastructure Engineer

### Role Summary
The DevOps Engineer builds and maintains deployment pipelines, infrastructure, and operational monitoring to enable reliable releases and production stability. They enable the team to deploy frequently and respond quickly to incidents.

### Responsibilities
- Design and maintain CI/CD pipelines
- Manage infrastructure, provisioning, and scaling
- Implement monitoring, logging, and alerting
- Support deployment planning and rollback procedures
- Ensure security and compliance in deployment processes
- Coordinate incident response and post-incident reviews
- Enable automated testing and quality gates in the deployment pipeline

### Goals
- Enable fast, reliable, and repeatable deployments
- Maintain high availability and system performance
- Reduce operational toil and manual work
- Support rapid iteration while maintaining stability

### Typical Communication
- Deployment readiness checklists and release coordination
- Incident alerts and post-incident reviews
- Infrastructure and pipeline improvements
- Performance and reliability metrics

### Interactions with Other Roles
- **Developers**: Supports CI/CD pipeline configuration and deployment troubleshooting
- **Project Manager**: Coordinates deployment schedules and release procedures
- **QA Lead**: Integrates automated testing into CI/CD pipelines
- **Technical Lead**: Designs infrastructure for scalability and reliability
- **Security Lead**: Ensures secure deployment processes and infrastructure hardening
- **Stakeholders**: Provides uptime and performance visibility

---

## Security Lead

### Role Summary
The Security Lead ensures security requirements are integrated into the development and deployment lifecycle and manages security risk and compliance. They shift security left, embedding it early in the design and development process.

### Responsibilities
- Define security requirements and acceptance criteria
- Review designs and code for security vulnerabilities
- Coordinate security testing and scanning in CI
- Manage security incidents and escalations
- Ensure compliance with organizational and regulatory standards
- Educate team on secure coding practices
- Participate in threat modeling and risk assessments

### Goals
- Deliver secure, compliant software
- Reduce security vulnerabilities in production
- Maintain stakeholder and customer trust
- Build security awareness and capability across the team

### Typical Communication
- Security requirements and acceptance criteria
- Security risk assessments and incident reports
- Security training and best practices guidance
- Threat modeling and design review results

### Interactions with Other Roles
- **Developers**: Provides security requirements, reviews code for vulnerabilities, and offers secure coding guidance
- **Product Manager**: Ensures security requirements are included in acceptance criteria
- **Project Manager**: Integrates security reviews into project timeline and escalates security risks
- **Technical Lead**: Reviews architecture for security design, discusses threat models
- **QA Lead**: Coordinates security testing and penetration testing activities
- **DevOps Engineer**: Ensures secure deployment pipelines and infrastructure hardening
- **Stakeholders**: Communicates security risk status and compliance updates

---

## Stakeholder / Business Owner

### Role Summary
Stakeholders and Business Owners provide business context, set priorities, and provide approval authority for project decisions. They represent customer interests, business goals, and organizational constraints.

### Responsibilities
- Define business objectives and success metrics
- Prioritize requirements and trade-offs
- Approve major decisions and scope changes
- Communicate business context and constraints to the team
- Remove blockers and escalations requiring business-level decisions
- Participate in sign-off and acceptance activities

### Goals
- Ensure project delivers business value
- Manage stakeholder expectations and satisfaction
- Align project outcomes with organizational strategy
- Make timely decisions to keep projects moving

### Typical Communication
- Monthly stakeholder updates and reviews
- Decision approvals and trade-off discussions
- Business metric reporting and success validation
- Risk escalations and blockers requiring business input

### Interactions with Other Roles
- **Product Manager**: Partners on requirements, prioritization, and outcome measurement
- **Project Manager**: Receives status updates, provides decisions, and approves changes
- **Developers**: Provides business context and clarifies requirements when needed
- **All Team Members**: Communicates business goals, priorities, and constraints

---

## Scrum Master / Agile Coach (Optional)

### Role Summary
The Scrum Master / Agile Coach facilitates agile ceremonies, removes impediments, and coaches the team on agile practices. This role is optional and may be combined with Project Manager responsibilities for smaller teams.

### Responsibilities
- Facilitate daily standups, sprint planning, reviews, and retrospectives
- Identify and remove impediments blocking team progress
- Coach the team on agile practices and continuous improvement
- Maintain the sprint board and ensure process compliance
- Foster team collaboration and psychological safety
- Escalate systemic issues that impact delivery

### Goals
- Enable team self-organization and ownership
- Maximize team velocity and delivery predictability
- Build a high-performing, collaborative team culture
- Drive continuous improvement through retrospectives

### Typical Communication
- Daily standups and sprint ceremonies
- One-on-one coaching and impediment resolution
- Retrospective facilitation and action item tracking
- Process improvement recommendations

### Interactions with Other Roles
- **All Team Members**: Facilitates collaboration, removes blockers, and coaches on agile practices
- **Project Manager**: May combine with PM role or coordinate on timeline and escalation management
- **Product Manager**: Ensures backlog is well-groomed and prioritized for sprint planning

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Understand the interaction patterns between roles to better simulate cross-functional collaboration and communication.
