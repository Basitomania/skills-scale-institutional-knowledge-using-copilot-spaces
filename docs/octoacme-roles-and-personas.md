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

## QA Engineers

### Role Summary
QA Engineers validate quality and ensure acceptance criteria are met before features reach production. They design test strategies, execute test plans, and identify defects early in the development cycle.

### Responsibilities
- Design and maintain test plans and test cases
- Execute manual and automated testing (unit, integration, end-to-end)
- Validate features against acceptance criteria
- Report and track defects through resolution
- Collaborate with developers on testability and bug fixes
- Contribute to Definition of Done and quality standards

### Goals
- Ensure high-quality releases with minimal production defects
- Reduce regression risk through comprehensive test coverage
- Enable fast, reliable feedback loops for developers

### Typical Communication
- Daily standups to report testing status and blockers
- PR reviews for testability and edge cases
- Bug reports with clear reproduction steps
- Test sign-off and release readiness reports

### Collaboration & Handoffs
- **With Developers**: Receives code for testing after PR approval; provides feedback on bugs and testability improvements
- **With Release Manager**: Confirms test completion and quality gates before release approval
- **With Product Managers**: Validates features against acceptance criteria and user scenarios

---

## UX Designer

### Role Summary
UX Designers research user needs, design intuitive interfaces, and ensure product experiences are accessible and delightful. They translate user requirements into design specifications that guide implementation.

### Responsibilities
- Conduct user research and usability testing
- Create wireframes, mockups, and interactive prototypes
- Design user flows and information architecture
- Establish and maintain design systems and patterns
- Validate designs with users and iterate based on feedback
- Collaborate with developers on implementation feasibility

### Goals
- Deliver intuitive, accessible user experiences
- Reduce user friction and support costs through good design
- Ensure design consistency across the product

### Typical Communication
- Design reviews and critique sessions
- User research findings and persona updates
- Figma/Sketch files and design specifications
- Accessibility and usability recommendations

### Collaboration & Handoffs
- **With Product Managers**: Receives feature requirements and user stories; provides design feasibility input and user insights
- **With Developers**: Delivers design specifications and assets; collaborates on implementation details and design trade-offs
- **With QA Engineers**: Defines expected UI behavior and interaction patterns for test validation
- **With Data Analysts**: Uses analytics data to inform design decisions and measure design impact

---

## Data Analyst

### Role Summary
Data Analysts collect, analyze, and interpret data to inform product decisions and measure success. They provide insights that help teams understand user behavior, validate hypotheses, and optimize features.

### Responsibilities
- Define and track key product metrics and KPIs
- Design and implement analytics instrumentation
- Analyze usage patterns and user behavior
- Create dashboards and reports for stakeholders
- Conduct A/B test analysis and statistical validation
- Provide data-driven recommendations for product improvements

### Goals
- Enable data-informed decision making across the organization
- Measure and communicate product impact clearly
- Identify opportunities for optimization and growth

### Typical Communication
- Weekly metrics reviews and insights reports
- Ad-hoc analysis requests and findings
- Dashboard demonstrations and documentation
- A/B test results and statistical significance reports

### Collaboration & Handoffs
- **With Product Managers**: Receives requests for metrics and analysis; provides insights that inform prioritization and feature decisions
- **With UX Designers**: Shares user behavior data to inform design decisions; validates design impact through metrics
- **With Developers**: Specifies analytics events and instrumentation requirements; validates data collection implementation
- **With Project Managers**: Provides success metrics for project one-pagers and status reporting

---

## Release Manager

### Role Summary
Release Managers coordinate and execute production releases, ensuring deployments are safe, well-communicated, and reversible. They own the release process and act as the central point of coordination across teams.

### Responsibilities
- Plan and schedule releases across multiple projects
- Coordinate pre-release readiness checks (testing, documentation, rollback plans)
- Execute deployment procedures and monitor release health
- Communicate release status to stakeholders and support teams
- Manage release notes and change documentation
- Facilitate post-release reviews and process improvements

### Goals
- Deliver reliable, low-risk production releases
- Minimize deployment-related incidents and downtime
- Maintain predictable release cadence and clear communication

### Typical Communication
- Release planning meetings and go/no-go decisions
- Deployment announcements and status updates
- Incident notifications and rollback coordination
- Release retrospectives and process improvements

### Collaboration & Handoffs
- **With QA Engineers**: Receives test sign-off and quality gate confirmation before approving releases
- **With Developers**: Coordinates code freeze timing, verifies CI/CD pipeline status, and manages hotfix deployments
- **With DevOps Engineers**: Collaborates on deployment automation, infrastructure readiness, and monitoring setup
- **With Product Managers**: Aligns release timing with feature readiness and customer communication plans
- **With Project Managers**: Provides release schedule input for project timelines and milestone planning

---

## DevOps Engineer

### Role Summary
DevOps Engineers build and maintain the infrastructure, tooling, and automation that enable teams to develop, test, and deploy software efficiently and reliably. They bridge development and operations concerns.

### Responsibilities
- Design and maintain CI/CD pipelines and automation
- Manage cloud infrastructure and environment configurations
- Implement monitoring, logging, and alerting systems
- Ensure security, compliance, and disaster recovery capabilities
- Optimize build times and deployment processes
- Provide tooling and platform support to development teams

### Goals
- Enable fast, safe, automated deployments
- Maintain high availability and system reliability
- Reduce manual operations toil through automation

### Typical Communication
- Infrastructure changes and maintenance windows
- CI/CD pipeline updates and build status
- Incident response and on-call handoffs
- Capacity planning and performance reports

### Collaboration & Handoffs
- **With Developers**: Provides CI/CD infrastructure and build support; receives requirements for new environments and tooling
- **With Release Manager**: Ensures deployment automation is functional; provides infrastructure readiness confirmation
- **With QA Engineers**: Provisions test environments and data; ensures testing infrastructure is reliable
- **With Project Managers**: Communicates infrastructure risks, dependencies, and maintenance schedules that impact project timelines

---

## Roles Summary Table

| Role | Primary Focus | Key Handoff Partners | Main Artifacts |
|------|---------------|---------------------|----------------|
| **Product Manager** | What to build, prioritization | Developers, Data Analysts, UX Designers | Roadmap, backlog, feature specs |
| **Project Manager** | Delivery coordination, risk management | All roles | Project plans, status reports, risk registers |
| **Developer** | Feature implementation, code quality | QA Engineers, UX Designers, DevOps Engineers | Code, tests, technical docs |
| **QA Engineer** | Quality validation, testing | Developers, Release Manager | Test plans, bug reports, sign-offs |
| **UX Designer** | User experience, interface design | Product Managers, Developers, Data Analysts | Wireframes, mockups, design specs |
| **Data Analyst** | Metrics, insights, analysis | Product Managers, UX Designers | Dashboards, reports, analysis findings |
| **Release Manager** | Release coordination, deployment | QA Engineers, DevOps Engineers, Developers | Release notes, deployment plans |
| **DevOps Engineer** | Infrastructure, automation, reliability | Developers, Release Manager, QA Engineers | CI/CD pipelines, infrastructure docs |

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

