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

### Interactions
- Works with **Delivery Lead** on sprint commitments and blockers
- Collaborates with **Engineering Manager** on technical direction and mentorship
- Partners with **QA** on test coverage and acceptance criteria
- Engages with **Security Engineer** on secure coding practices

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

### Interactions
- Works with **Project Manager** on scheduling and risk management
- Collaborates with **UX Researcher** on user validation and design trade-offs
- Partners with **Data Analyst** on success metrics and product instrumentation
- Engages with **Support Lead** on customer feedback and impact prioritization

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

### Interactions
- Works with **Product Manager** on priorities and scope
- Collaborates with **Delivery Lead** on execution and sprint planning
- Escalates issues to **Engineering Manager** and **Release Manager** as needed
- Communicates status to **Stakeholders** and dependent teams

---

## Delivery Lead

### Role Summary
Delivery Leads manage day-to-day execution and sprint commitments. They own cross-team dependencies, remove blockers, and ensure release readiness by coordinating between technical and operational teams.

### Responsibilities
- Coordinate daily standup and sprint execution
- Manage sprint commitments and track progress against milestones
- Identify and resolve blockers in real-time
- Own cross-team dependencies and coordination
- Prepare and monitor release readiness
- Report progress and risks to Project Manager

### Goals
- Keep team focused on sprint goals
- Unblock the team quickly to maintain velocity
- Ensure smooth, timely releases
- Maintain transparency on execution status

### Typical Communication
- Daily standups and ad-hoc blocker resolution
- Sprint status updates to PM and stakeholders
- Coordination with Release Manager and QA before releases
- Escalation to Engineering Manager for technical impediments

### Interactions
- Works closely with **Project Manager** on scheduling and risk escalation
- Collaborates with **Developers** and **QA** on sprint execution and blockers
- Partners with **Release Manager** on release coordination
- Engages with **Engineering Manager** on resource and technical constraints
- Communicates with **Support Lead** on production issues during releases

---

## Engineering Manager

### Role Summary
Engineering Managers provide technical leadership, mentor developers, plan team capacity, and establish code quality standards. They ensure technical excellence and team growth while supporting delivery commitments.

### Responsibilities
- Provide technical direction and architectural guidance
- Mentor and develop team members
- Plan team capacity and resource allocation
- Establish and maintain code quality standards
- Conduct code reviews and design reviews
- Identify and mitigate technical risks
- Collaborate with Product and Project leadership on feasibility

### Goals
- Build a high-performing, well-mentored engineering team
- Maintain technical excellence and code quality
- Reduce technical debt and improve system reliability
- Enable consistent, sustainable velocity

### Typical Communication
- One-on-ones with team members (regular cadence)
- Technical design reviews and architecture discussions
- Escalations with Product Manager and Delivery Lead on feasibility
- Quarterly planning and capacity discussions with Project Manager

### Interactions
- Works with **Developers** on technical mentorship and code quality
- Collaborates with **Delivery Lead** on resource constraints and sprint feasibility
- Partners with **Product Manager** on technical trade-offs and feasibility assessment
- Engages with **Security Engineer** on secure architecture and design patterns
- Supports **QA** on test strategy and coverage goals

---

## UX Researcher

### Role Summary
UX Researchers conduct user research, validate design assumptions, and synthesize insights to guide product decisions. They ensure features are usable, valuable, and aligned with customer needs.

### Responsibilities
- Conduct user interviews, surveys, and usability testing
- Validate design concepts and feature prototypes
- Synthesize research findings into actionable insights
- Identify usability issues and pain points
- Recommend design improvements based on evidence
- Collaborate on persona development and journey mapping

### Goals
- Ensure features are usable and meet customer expectations
- Reduce design rework through early validation
- Provide data-driven insights to inform product decisions
- Improve overall product adoption and satisfaction

### Typical Communication
- Research findings presentations to Product and Design teams
- Usability testing sessions with stakeholders
- Design review feedback and recommendations
- Regular sync with Product Manager on research priorities

### Interactions
- Partners with **Product Manager** on research hypotheses and validation needs
- Collaborates with **Designers** on design concepts and iterations
- Engages with **Developers** on implementation feasibility and design trade-offs
- Works with **Data Analyst** on quantitative validation of research insights
- Provides input to **Delivery Lead** on user acceptance criteria

---

## Release Manager

### Role Summary
Release Managers own the end-to-end release process, including deployment planning, coordination, verification, and rollback execution. They ensure smooth, safe releases with minimal customer impact.

### Responsibilities
- Plan and schedule release windows
- Coordinate with Delivery Lead, QA, and Support on release readiness
- Execute deployments following established procedures
- Run post-deployment verification and smoke tests
- Document and communicate release notes
- Manage rollback procedures and incident response during releases
- Track and resolve release-related issues

### Goals
- Execute smooth, on-time releases with minimal downtime
- Reduce deployment-related incidents and rework
- Maintain clear communication with all stakeholders during releases
- Enable fast, safe rollbacks when needed

### Typical Communication
- Pre-release checklists and readiness reviews
- Deployment status updates during release windows
- Post-release verification reports
- Release notes and customer communications
- Incident updates if issues occur during deployment

### Interactions
- Coordinates with **Delivery Lead** on release scheduling and team coordination
- Works with **QA** on smoke testing and acceptance criteria verification
- Partners with **Engineering Manager** on deployment procedures and contingency planning
- Engages with **Support Lead** on customer impact and escalation procedures
- Communicates with **Security Engineer** on security gating and compliance verification
- Reports to **Project Manager** on release status and metrics

---

## Support Lead (Customer Operations Lead)

### Role Summary
Support Leads serve as the first-line escalation owner for production issues, triaging customer-impacting problems and communicating status to stakeholders. They bridge customer needs and internal teams.

### Responsibilities
- Triage and prioritize production issues and customer escalations
- Communicate incident status to affected customers and stakeholders
- Coordinate with Engineering and Release Manager on issue resolution
- Provide escalation path for critical, customer-impacting issues
- Gather customer feedback and impact assessment
- Feed customer insights back to Product and Support teams
- Document lessons learned from incidents

### Goals
- Minimize customer impact and resolution time for critical issues
- Provide clear, timely communication during incidents
- Improve customer satisfaction and trust
- Identify patterns in issues to inform product improvements

### Typical Communication
- Incident response and status updates (internal and external)
- Escalations to Delivery Lead and Release Manager
- Customer communications and impact assessments
- Post-incident retrospectives with Engineering and Release Manager
- Regular feedback to Product Manager on customer-facing issues

### Interactions
- Works with **Release Manager** during rollouts and deployment issues
- Escalates to **Delivery Lead** and **Engineering Manager** for production incidents
- Coordinates with **Security Engineer** for security-related incidents
- Provides customer feedback to **Product Manager** and **UX Researcher**
- Communicates with **Data Analyst** on incident metrics and SLA tracking

---

## Security Engineer

### Role Summary
Security Engineers conduct security reviews, perform threat modeling, and advise on secure design practices. They ensure products are built with security as a core principle and help the team respond to vulnerabilities.

### Responsibilities
- Conduct security code reviews and threat modeling
- Review architecture and design for security vulnerabilities
- Advise on secure coding practices and patterns
- Triage and prioritize security vulnerabilities
- Coordinate security scanning and testing in CI/CD
- Provide security training and guidance to the team
- Support incident response for security-related issues

### Goals
- Build security into the product from the start
- Reduce security vulnerabilities and risk exposure
- Enable the team to make informed security trade-offs
- Maintain customer trust and regulatory compliance

### Typical Communication
- Security design reviews during planning phase
- Code review comments on security concerns
- Vulnerability reports and remediation guidance
- Security training and best practices documentation
- Incident response for security issues

### Interactions
- Engages early with **Developers** and **Engineering Manager** on secure design
- Reviews with **Product Manager** on security implications of features
- Collaborates with **Release Manager** for security gating before deployments
- Partners with **Support Lead** on security incident response
- Works with **Delivery Lead** on security risk escalation

---

## Data Analyst

### Role Summary
Data Analysts define success metrics, produce dashboards, and validate experiment results. They enable data-driven decision-making and help the team measure product impact.

### Responsibilities
- Define and track success metrics aligned with project goals
- Build and maintain dashboards for key performance indicators
- Validate experiment results and A/B test outcomes
- Instrument telemetry and tracking for new features
- Provide data-driven insights to inform product decisions
- Identify trends and anomalies in product usage
- Support post-release analysis and impact measurement

### Goals
- Enable data-driven product and business decisions
- Provide clear visibility into product performance and health
- Validate that features deliver expected business value
- Identify opportunities for optimization and improvement

### Typical Communication
- Metric definitions and dashboard reviews with Product Manager
- Weekly or bi-weekly metric updates and insights
- Analysis of experiment results and recommendations
- Regular sync with Developers on instrumentation and data quality
- Reporting to Project Manager and Stakeholders on project metrics

### Interactions
- Works with **Product Manager** on metric definition and success criteria
- Collaborates with **Developers** and **QA** to instrument telemetry
- Partners with **UX Researcher** on quantitative validation of insights
- Provides metrics reporting to **Project Manager** and stakeholders
- Engages with **Support Lead** on SLA and incident metrics

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Reference the "Interactions" section to understand cross-functional dependencies and communication flows.
- When planning projects, ensure all relevant personas are identified and their responsibilities are clear to avoid gaps and improve accountability.
