# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

> **Note:** This document has been expanded based on [Issue #4](https://github.com/kkomorowski/musical-dollop/issues/4) to include additional personas and role interaction details to improve project management clarity and accountability.

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
Business Analysts bridge the gap between stakeholders and the technical team by eliciting, translating, and documenting business requirements. They ensure that all requirements are traceable and aligned with business objectives.

### Responsibilities
- Elicit and document stakeholder requirements and business processes
- Define success metrics and key performance indicators (KPIs)
- Ensure requirements traceability throughout the project lifecycle
- Create and maintain business process documentation
- Validate that delivered solutions meet business needs

### Goals
- Ensure clear understanding of business requirements across all teams
- Maintain accurate and up-to-date requirements documentation
- Bridge communication gaps between business and technical stakeholders
- Support data-driven decision making with clear success metrics

### Typical Communication
- Requirements gathering sessions with stakeholders
- Backlog refinement meetings with Product Managers and Developers
- Requirements reviews and sign-offs
- Business process documentation and workflow diagrams

---

## Quality Assurance Lead

### Role Summary
Quality Assurance Leads establish and maintain quality standards across the project. They develop comprehensive test strategies, oversee test execution, and serve as the final quality gate before production releases.

### Responsibilities
- Establish testing standards and quality benchmarks
- Develop test plans, test cases, and test automation strategies
- Oversee execution of test cycles across all environments
- Report and track defects through resolution
- Approve releases for production based on quality criteria
- Lead test automation initiatives

### Goals
- Ensure high-quality deliverables that meet acceptance criteria
- Minimize production defects and customer-impacting issues
- Improve test coverage and efficiency through automation
- Foster a quality-first culture across the team

### Typical Communication
- Test plan reviews with Product Managers and Developers
- Daily defect triage and status updates
- Quality metrics reporting to stakeholders
- Release go/no-go decision meetings
- Test automation planning sessions with DevOps

---

## Stakeholder Liaison

### Role Summary
Stakeholder Liaisons maintain consistent and transparent communication with all project stakeholders. They act as the primary point of contact for stakeholder inquiries, manage expectations, and ensure stakeholder satisfaction throughout the project lifecycle.

### Responsibilities
- Maintain regular communication with external and internal stakeholders
- Gather ongoing feedback and communicate it to the project team
- Manage stakeholder expectations and address concerns proactively
- Coordinate stakeholder reviews and approvals
- Track and report on stakeholder satisfaction metrics
- Escalate critical stakeholder issues appropriately

### Goals
- Maintain high stakeholder satisfaction and engagement
- Ensure transparency in project status and decisions
- Prevent surprises through proactive communication
- Build and maintain strong stakeholder relationships

### Typical Communication
- Regular stakeholder status updates and briefings
- Stakeholder feedback sessions and surveys
- Escalation communications for critical issues
- Stakeholder review and approval coordination
- Executive summaries and reports

---

## Agile Coach

### Role Summary
Agile Coaches guide teams in adopting and continuously improving Agile practices. They facilitate key ceremonies, remove impediments, and mentor team members on Agile principles to maximize team efficiency and effectiveness.

### Responsibilities
- Guide team adoption and adherence to Agile best practices
- Facilitate retrospectives and help teams act on improvement opportunities
- Identify and resolve team impediments and blockers
- Mentor team members on Agile principles and mindsets
- Support continuous improvement initiatives
- Coach Scrum Masters and Product Owners in their roles

### Goals
- Improve team velocity and delivery predictability
- Foster a culture of continuous improvement and learning
- Reduce waste and inefficiencies in team processes
- Build self-organizing, high-performing teams

### Typical Communication
- Facilitation of sprint retrospectives and planning
- One-on-one coaching sessions with team members
- Process improvement workshops
- Agile maturity assessments and recommendations
- Collaboration with Scrum Masters and leadership on team health

---

## Security Champion

### Role Summary
Security Champions promote secure coding practices and integrate security throughout the software development lifecycle. They serve as the primary security resource for their teams, ensuring that security is considered in all decisions and activities.

### Responsibilities
- Promote secure coding standards and best practices
- Ensure security reviews are integrated into development workflows
- Participate in threat modeling and security design reviews
- Serve as the go-to resource for security questions and concerns
- Monitor and respond to security vulnerabilities and alerts
- Collaborate on security testing and penetration testing activities

### Goals
- Shift security left by integrating it early in the development process
- Reduce security vulnerabilities in production code
- Build security awareness and capability across the team
- Ensure compliance with security policies and standards

### Typical Communication
- Security design reviews with Developers and Architects
- Vulnerability triage with DevOps and QA teams
- Security training and awareness sessions
- Threat modeling workshops during planning
- Security incident response coordination

---

## Role Interaction Matrix

This table summarizes how each role interacts with others and contributes to project success:

| Role | Primary Interactions | Key Contributions to Project Success |
|------|---------------------|-------------------------------------|
| **Developers** | Product Managers, QA Lead, Security Champion, Agile Coach | Deliver high-quality, maintainable code; implement features meeting acceptance criteria |
| **Product Managers** | Developers, Project Managers, Business Analyst, Stakeholder Liaison | Define product vision, prioritize work, ensure customer value delivery |
| **Project Managers** | All roles | Coordinate delivery, manage risks/timelines, facilitate communication |
| **Business Analyst** | Product Managers, Developers, Stakeholders, Stakeholder Liaison | Translate business needs into clear requirements, ensure traceability |
| **QA Lead** | Developers, DevOps, Product Managers, Security Champion | Ensure quality standards, validate acceptance criteria, gate releases |
| **Stakeholder Liaison** | Project Managers, Business Analyst, Product Managers, All Stakeholders | Maintain stakeholder satisfaction, manage expectations, ensure transparency |
| **Agile Coach** | Scrum Masters, Product Managers, All team members | Improve team processes, remove impediments, foster continuous improvement |
| **Security Champion** | Developers, QA Lead, DevOps, Architects | Integrate security throughout SDLC, reduce vulnerabilities, ensure compliance |

---

## Role Responsibilities Handoff Checklist

This checklist clarifies key handoffs between roles to ensure smooth collaboration:

### Requirements Definition Handoff (Business Analyst → Product Manager → Developers)
- [ ] Business requirements documented and validated with stakeholders
- [ ] Success metrics and KPIs clearly defined
- [ ] User stories created with acceptance criteria
- [ ] Requirements reviewed and prioritized in backlog
- [ ] Dependencies and risks identified
- [ ] Developers understand requirements and acceptance criteria

### Development Handoff (Developers → QA Lead)
- [ ] Code implemented and unit tests passing
- [ ] PR submitted with issue links and description
- [ ] Code review completed and approved
- [ ] Security review completed (with Security Champion if needed)
- [ ] Test environment deployed and accessible
- [ ] QA Lead notified and test plan reviewed

### Quality Assurance Handoff (QA Lead → Product Manager/Stakeholder Liaison)
- [ ] Test plan executed and documented
- [ ] All critical and high-priority defects resolved
- [ ] Acceptance criteria validated
- [ ] Release notes prepared
- [ ] Stakeholder demo/review completed
- [ ] Go/no-go decision documented

### Release Handoff (Project Manager → DevOps → Operations)
- [ ] Release checklist completed
- [ ] Production deployment plan reviewed
- [ ] Rollback procedures documented and tested
- [ ] Monitoring and alerting configured
- [ ] Stakeholders notified of release schedule
- [ ] Post-release support plan in place

### Retrospective Handoff (Agile Coach → Project Manager → Team)
- [ ] Retrospective facilitated and action items captured
- [ ] Action items prioritized (top 2-3)
- [ ] Owners assigned to each action item
- [ ] Action items added to project backlog
- [ ] Progress tracked in subsequent retrospectives
- [ ] Process improvements documented and shared

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- The Role Interaction Matrix helps visualize dependencies and collaboration patterns.
- The Handoff Checklist ensures clear accountability during key project transitions.

