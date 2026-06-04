# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

---

## Core Roles

### Developers

#### Role Summary
Developers design, build, test, and deliver software components. They collaborate with product and project leads to implement features that meet acceptance criteria and quality standards.

#### Responsibilities
- Implement features and fixes to meet acceptance criteria
- Write and maintain tests and documentation
- Participate in design and code reviews
- Assist in estimating and planning work
- Help identify technical risks and propose mitigations

#### Goals
- Deliver reliable, maintainable code
- Reduce cycle time from idea to production
- Maintain high test coverage and observability

#### Typical Communication
- Daily standups and sprint planning
- PR descriptions and code review comments
- Technical design docs when needed

#### Interactions with Other Roles
- **Product Manager**: Clarify requirements, discuss trade-offs, provide acceptance feedback
- **Project Manager**: Report blockers, provide estimates, escalate risks
- **QA/Testing**: Collaborate on test strategy, provide builds for testing
- **DevOps Engineer**: Coordinate deployments, troubleshoot production issues
- **UX Designer**: Discuss implementation feasibility, review UI/UX specifications

---

### Product Managers

#### Role Summary
Product Managers define what should be built to deliver customer and business value. They own the product vision, prioritize the backlog, and measure outcomes.

#### Responsibilities
- Define problem statements and success metrics
- Prioritize the roadmap and backlog
- Collaborate with stakeholders and engineering on trade-offs
- Validate solutions through user research and metrics

#### Goals
- Maximize customer value and impact
- Make clear, data-driven prioritization decisions
- Ensure product-market fit and usability

#### Typical Communication
- Weekly alignment with PM and engineering leads
- Roadmap updates and stakeholder briefings
- Acceptance criteria and feature specs

#### Interactions with Other Roles
- **Project Manager**: Weekly syncs, roadmap alignment, milestone planning
- **Developers**: Requirements clarification, acceptance criteria definition, technical feasibility discussions
- **QA/Testing**: Test strategy definition, acceptance criteria validation
- **Data Analyst**: Review metrics, validate success indicators, analyze user behavior
- **UX Designer**: Collaborate on feature definition, user research, design validation

---

### Project Managers

#### Role Summary
Project Managers coordinate delivery activities, manage schedules, risks, and communications. They enable the team to deliver on commitments efficiently.

#### Responsibilities
- Create and maintain project plans and timelines
- Manage risks, dependencies, and resource constraints
- Facilitate meetings (kickoff, planning, retrospectives)
- Ensure consistent project documentation and status reporting
- Coordinate cross-team and stakeholder communication

#### Goals
- Deliver projects on time and within scope
- Minimize unplanned work and escalations
- Maintain transparency and alignment across stakeholders

#### Typical Communication
- Weekly status updates and stakeholder reports
- Risk registers and decision logs
- Coordination via project boards and meeting facilitation

#### Interactions with Other Roles
- **Product Manager**: Weekly syncs, roadmap planning, prioritization
- **Developers**: Sprint planning, risk identification, blocker resolution
- **QA/Testing**: Test timeline coordination, acceptance criteria verification
- **DevOps Engineer**: Deployment scheduling, release planning
- **Scrum Master**: Process optimization, sprint facilitation
- **Stakeholders**: Status updates, decision escalation, risk communication

---

### QA/Testing

#### Role Summary
QA professionals and testers validate that solutions meet quality standards and acceptance criteria. They design test strategies, execute tests, identify defects, and ensure features are ready for production.

#### Responsibilities
- Design comprehensive test strategies
- Execute manual and automated tests
- Identify and document defects with reproduction steps
- Validate acceptance criteria are met
- Perform end-to-end testing and user workflow validation
- Coordinate security and performance testing
- Support production verification and monitoring

#### Goals
- Ensure high-quality releases
- Catch defects early and reduce production issues
- Validate user acceptance criteria

#### Typical Communication
- Test plans and test cases
- Defect reports with clear reproduction steps
- Test coverage and quality metrics
- Acceptance validation checkpoints

#### Interactions with Other Roles
- **Developers**: Defect collaboration, reproduction clarification, test environment setup
- **Product Manager**: Acceptance criteria clarification, success metric validation
- **Project Manager**: Test timeline coordination, quality gate decisions
- **UX Designer**: Usability validation, accessibility testing, user flow verification
- **DevOps Engineer**: Test environment setup, deployment verification, smoke testing

---

## Extended Roles

These roles are common in larger or more specialized OctoAcme teams and should be explicitly defined in your project. Add these roles based on your team size and project scope.

### UX Designer

#### Role Summary
UX Designers craft user experiences and interfaces to ensure features are usable, accessible, and delightful. They collaborate with Product Managers and Developers to validate that solutions meet user needs and accessibility standards.

#### Responsibilities
- Design user interfaces and interaction flows
- Conduct user research and usability testing
- Define accessibility requirements and standards
- Collaborate on requirements definition with Product Manager
- Participate in design reviews and provide feedback to developers
- Ensure design specifications are clear and implementable
- Validate design implementation during QA phase

#### Goals
- Create intuitive, accessible user experiences
- Reduce user friction and support burden
- Ensure brand consistency and design coherence

#### Typical Communication
- Design reviews with Developers and Product Manager
- Usability testing sessions and findings
- Accessibility requirement documentation
- Design specification documents

#### Interactions with Other Roles
- **Product Manager**: Collaborate on feature definition, user needs validation, success criteria
- **Developers**: Design review, implementation feasibility, specification clarity
- **QA/Testing**: Usability validation, accessibility testing, user flow verification
- **Data Analyst**: User behavior insights, design validation metrics

#### When to Include
- Projects with significant UI/UX components
- Teams building consumer-facing products
- Organizations with accessibility requirements
- Projects involving major design changes or new interfaces

---

### DevOps Engineer

#### Role Summary
DevOps Engineers own CI/CD infrastructure, deployment pipelines, and system reliability. They ensure smooth deployments, monitor system health, and collaborate with Developers and QA to maintain high availability and performance.

#### Responsibilities
- Build and maintain CI/CD pipelines
- Manage infrastructure and deployment environments
- Ensure security scanning and compliance in deployment processes
- Monitor system performance and reliability
- Manage rollback procedures and incident response
- Collaborate with Developers on deployment readiness
- Provide post-deployment verification and monitoring

#### Goals
- Enable fast, safe deployments to production
- Maintain system reliability and performance
- Minimize deployment risks and incidents

#### Typical Communication
- Deployment coordination with Project Manager and Developers
- Release readiness checklists
- Incident response and status updates
- Performance and reliability metrics

#### Interactions with Other Roles
- **Developers**: Deployment support, pipeline troubleshooting, build coordination
- **Project Manager**: Deployment scheduling, release coordination, incident escalation
- **QA/Testing**: Deployment verification, environment setup, smoke test support
- **Scrum Master**: Process automation opportunities, efficiency improvements

#### When to Include
- Projects with frequent releases (weekly or more)
- Complex infrastructure or microservices
- High-availability or mission-critical systems
- Distributed or cloud-based deployments
- Organizations with strong DevOps culture

---

### Data Analyst

#### Role Summary
Data Analysts gather, analyze, and present data to support product and business decisions. They work with Product Managers to track success metrics, identify patterns, and generate actionable insights from project outcomes and user behavior.

#### Responsibilities
- Define and track success metrics aligned to project goals
- Analyze project and product data
- Generate reports and dashboards for stakeholders
- Identify trends and insights from user behavior
- Validate hypothesis and test results
- Provide data-driven recommendations for improvements
- Support post-release analysis and iterations

#### Goals
- Provide clear, actionable data insights
- Enable data-driven decision making
- Measure impact of delivered features

#### Typical Communication
- Metric definitions and success criteria
- Weekly/monthly analytics reports
- Dashboard and KPI presentations
- Data-driven recommendations

#### Interactions with Other Roles
- **Product Manager**: Define success metrics, analyze product performance, inform prioritization
- **Project Manager**: Track delivery metrics, provide project performance insights
- **Developers**: Understand feature usage, identify performance issues
- **QA/Testing**: Test coverage metrics, quality trend analysis

#### When to Include
- Projects with quantified success metrics
- Data-driven product decisions required
- Need to measure ROI and business impact
- Complex analytics or user behavior analysis needed
- Organizations focused on evidence-based product management

---

### Scrum Master / Agile Coach

#### Role Summary
Scrum Masters and Agile Coaches facilitate sprint ceremonies, remove process obstacles, and coach teams on Agile practices. They help optimize delivery processes and maintain team health and psychological safety.

#### Responsibilities
- Facilitate sprint planning, standups, reviews, and retrospectives
- Remove process obstacles and blockers
- Coach team members on Agile practices and principles
- Maintain sprint board and backlog hygiene
- Track team velocity and sprint metrics
- Support continuous improvement initiatives
- Escalate systemic issues to Project Manager or Product Manager

#### Goals
- Maximize team efficiency and collaboration
- Maintain sustainable pace and team health
- Enable continuous process improvement

#### Typical Communication
- Sprint ceremony facilitation
- Retrospective action items
- Process improvement recommendations
- Team health and velocity metrics

#### Interactions with Other Roles
- **Project Manager**: Process optimization, sprint coordination, blocker escalation
- **Developers**: Impediment removal, velocity tracking, retrospective participation
- **Product Manager**: Sprint planning support, backlog refinement, stakeholder alignment
- **All Roles**: Process coaching, ceremony facilitation, continuous improvement

#### When to Include
- Distributed or remote teams needing process structure
- First-time Agile implementations
- Large teams (8+ people) needing facilitation
- Organizations prioritizing team health and continuous improvement
- Projects with multiple sprints or ongoing delivery

---

## Role Selection Guide

### Team Size: 1-3 People (Startup/Small Project)
**Core Roles**: Developers, Product Manager (part-time), Project Manager (part-time)
- One person may wear multiple hats
- Focus on direct communication and lightweight process
- Add QA when quality becomes a concern

### Team Size: 4-8 People (Growing Team)
**Recommended Roles**: 
- Developers (2-4)
- Product Manager (dedicated)
- Project Manager (dedicated)
- QA/Testing (1 person)
- Optional: Scrum Master if more structure is needed

### Team Size: 8-15 People (Medium Team)
**Recommended Roles**:
- Developers (5-8)
- Product Manager (dedicated)
- Project Manager (dedicated)
- QA/Testing (1-2)
- DevOps Engineer (dedicated or shared)
- Scrum Master (dedicated or part-time)
- Consider adding: UX Designer, Data Analyst

### Team Size: 15+ People (Large/Enterprise)
**Recommended Roles**: All roles defined in this document
- Multiple specialists per role as needed
- Clear hand-offs and escalation paths
- Dedicated roles for UX, DevOps, Data Analytics
- Multiple Scrum Masters/Agile Coaches for team structure

---

## Role Interaction Matrix

| Primary Role | Collaborates With | Key Touchpoints | Frequency |
|------|---|---|---|
| Product Manager | PM, Developers, QA, UX Designer, Data Analyst | Requirements, acceptance criteria, metrics | Weekly |
| Project Manager | PM, All technical roles, Stakeholders | Timeline, risks, status, escalations | Daily/Weekly |
| Developers | PM, QA, UX Designer, DevOps Engineer, Scrum Master | Features, estimates, code review, deployments | Daily |
| QA/Testing | Developers, PM, UX Designer, Project Manager | Test strategy, defect reports, verification | Daily |
| DevOps Engineer | Developers, Project Manager, QA | Deployments, CI/CD, release readiness | Per release |
| UX Designer | Product Manager, Developers, QA | Design specs, implementation, usability testing | Per feature |
| Data Analyst | Product Manager, Project Manager, All roles | Metrics, insights, success validation | Weekly/Monthly |
| Scrum Master | All roles, Project Manager | Process, ceremonies, continuous improvement | Daily/Weekly |

---

## Role Hand-Offs Throughout Project Lifecycle

### Project Initiation Phase
- **Product Manager** → **Project Manager**: Problem statement, goals, success metrics
- **Project Manager** → **Stakeholders**: Scope, timeline, resource needs
- **Product Manager** → **Developers & QA**: Initial requirements and constraints

### Project Planning Phase
- **Product Manager** → **UX Designer**: Feature requirements and user flows
- **UX Designer** → **Developers**: Design specifications and accessibility requirements
- **Product Manager** & **Developers** → **QA**: Test strategy and acceptance criteria
- **Project Manager** → **All roles**: Timeline, milestones, dependencies
- **Data Analyst** → **Product Manager**: Success metrics and tracking approach

### Execution & Development Phase
- **Developers** ↔ **QA**: Builds for testing, defect reports, test results
- **Developers** ↔ **UX Designer**: Implementation questions, design clarification
- **Project Manager** → **All roles**: Status tracking, risk management, blocker resolution
- **Scrum Master** → **All roles**: Sprint facilitation, process support, impediment removal
- **Data Analyst** → **Product Manager**: Delivery progress metrics, early signals

### Release Phase
- **Developers** → **DevOps Engineer**: Build deployment, deployment coordination
- **QA** → **DevOps Engineer**: Final verification, smoke test coordination
- **DevOps Engineer** → **Project Manager**: Deployment status, rollback readiness
- **Project Manager** → **Stakeholders**: Release announcement, status updates

### Post-Release & Retrospective Phase
- **Data Analyst** → **Product Manager & Project Manager**: Success metrics analysis, impact measurement
- **All roles** → **Scrum Master & Project Manager**: Retrospective participation, lessons learned
- **Product Manager** → **Data Analyst**: Next iteration prioritization based on metrics

---

## Clarifying Overlapping Responsibilities

| Responsibility | Primary Role | Supporting Roles |
|---|---|---|
| Define success metrics | Product Manager | Data Analyst, Project Manager |
| Measure success metrics | Data Analyst | Product Manager, Project Manager |
| Create project timeline | Project Manager | Developers (estimation), Product Manager (prioritization) |
| Manage project risks | Project Manager | All roles (identification), Product Manager (prioritization) |
| Design features | Product Manager & UX Designer | Developers (feasibility input) |
| Implement features | Developers | QA (test planning), UX Designer (specification clarification) |
| Test features | QA | Developers (defect resolution), UX Designer (usability validation) |
| Deploy to production | DevOps Engineer | Developers (build coordination), QA (verification) |
| Monitor post-release | DevOps Engineer & Data Analyst | Product Manager (business impact), Developers (technical issues) |

---

## How These Personas Are Used

### In Project Initiation
- **Project Manager** leads kickoff with stakeholder alignment
- **Product Manager** presents problem statement and success metrics
- **Key contributors** (Developers, QA, UX Designer if applicable) identify risks and dependencies

### In Project Planning
- **Product Manager** defines requirements with input from **UX Designer**
- **Developers** and **QA** estimate effort and discuss test strategy
- **Project Manager** creates timeline with **Scrum Master** facilitation
- **Data Analyst** (if applicable) defines success metrics

### During Execution
- **Scrum Master** facilitates daily standups and sprint ceremonies
- **Developers** implement features with **UX Designer** and **QA** collaboration
- **DevOps Engineer** ensures CI/CD pipeline health
- **Project Manager** tracks risks and escalates blockers
- **Data Analyst** monitors delivery metrics and early success signals

### At Release
- **DevOps Engineer** coordinates deployment
- **QA** performs final verification and smoke tests
- **Project Manager** communicates release status
- **Product Manager** coordinates announcement
- **Data Analyst** prepares success metric dashboards

### Post-Release
- **Data Analyst** measures success against baseline metrics
- **Developers** monitor for production issues
- **Product Manager** gathers user feedback
- **Project Manager** leads retrospective with **Scrum Master** facilitation
- **All Roles** contribute learnings and improvements

---

## Updating and Maintaining This Document

As your team grows or your processes evolve:
1. Review this document at least quarterly
2. Add new roles as they emerge in your organization
3. Update interactions and touchpoints based on actual team experience
4. Use retrospectives to identify gaps in role clarity
5. Document hand-off improvements discovered through practice
6. Share updates with team members to maintain alignment

Use the [Process Doc Update template](.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) to propose changes to this document.
