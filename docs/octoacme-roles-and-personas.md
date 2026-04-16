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

## UX Designer

### Role Summary
UX Designers create user interfaces and workflows that align with user needs and business objectives. They champion usability, accessibility, and design system consistency throughout the product lifecycle.

### Responsibilities
- Design user interfaces, wireframes, and interactive prototypes
- Conduct user research and usability testing to validate design decisions
- Ensure accessibility standards and design system consistency across features
- Iterate on designs based on feedback from Product Managers, Developers, and end users
- Maintain and contribute to the shared design system and component library

### Goals
- Deliver intuitive, accessible, and visually consistent user experiences
- Reduce usability issues discovered late in development
- Bridge the gap between business requirements and end-user expectations

### Typical Communication
- Design review sessions with Product Managers and Developers
- Annotated wireframes and prototype links shared in project channels
- Usability test reports and design iteration notes

### Key Interactions
- Works with Product Manager to turn feature ideas into user flows before handoff to Developers
- Collaborates with Developers during implementation to ensure design fidelity
- Participates in user testing and validation sessions alongside Stakeholders

---

## Business Analyst

### Role Summary
Business Analysts elicit requirements and translate business needs into functional specifications. They serve as the bridge between stakeholders and delivery teams, ensuring clarity and alignment throughout the project lifecycle.

### Responsibilities
- Elicit, document, and validate requirements from stakeholders
- Translate business needs into functional specifications and user stories
- Map out process flows and define measurable acceptance criteria
- Identify gaps, risks, and dependencies in proposed solutions
- Support prioritization and feasibility discussions with Product Managers

### Goals
- Reduce ambiguity and misunderstandings during implementation
- Ensure delivered solutions meet defined business and user needs
- Improve requirement quality and traceability

### Typical Communication
- Requirements workshops and stakeholder interviews
- Functional specification documents and process flow diagrams
- Acceptance criteria updates within sprint backlog items

### Key Interactions
- Clarifies requirements for new backlog items, reducing misunderstandings during implementation
- Works with Product Manager on prioritization and feasibility as defined in `octoacme-project-planning.md`
- Supports Project Manager in dependency mapping and risk identification per `octoacme-risks-and-communication.md`

---

## QA Automation Engineer

### Role Summary
QA Automation Engineers develop and maintain automated test suites to ensure functional correctness and regression stability. They integrate quality practices into the development workflow and CI/CD pipelines.

### Responsibilities
- Develop, maintain, and expand automated test suites for functional and regression testing
- Define test strategies and coverage goals in collaboration with Developers and Project Managers
- Integrate automated tests into CI/CD pipelines to enable fast feedback loops
- Track and report defects, test gaps, and quality metrics
- Support release validation activities and sign-off processes

### Goals
- Increase test coverage and reduce the cost of defect detection
- Enable confident, frequent releases by maintaining a reliable automated test suite
- Shift quality left by embedding testing early in the development cycle

### Typical Communication
- Test plans and coverage reports shared with Developers and Project Managers
- Defect reports and triage sessions
- CI pipeline status updates and quality dashboards

### Key Interactions
- Brings bugs and test gaps to the Developers' attention early, improving code quality
- Collaborates with Developers and Product Managers on definition of done and acceptance criteria
- Supports release validation processes described in `octoacme-release-and-deployment.md`

---

## Scrum Master

### Role Summary
Scrum Masters facilitate Agile ceremonies and coach the team on Agile principles. They act as servant-leaders who remove impediments, foster psychological safety, and drive continuous improvement.

### Responsibilities
- Facilitate Agile ceremonies including standups, sprint planning, reviews, and retrospectives
- Identify and remove blockers and impediments affecting team velocity
- Coach team members on Agile principles and practices
- Track team health and promote a culture of continuous improvement
- Shield the team from external interruptions and scope creep

### Goals
- Maximize team efficiency and predictability of delivery
- Foster a self-organizing, high-performing team culture
- Ensure retrospective insights translate into actionable improvements

### Typical Communication
- Daily standup facilitation and impediment tracking
- Sprint velocity and team health metrics
- Retrospective action items and follow-up notes

### Key Interactions
- Facilitates discussions that surface blockers and foster team ownership across Developers, Product Managers, and Project Managers
- Works with Project Manager on sprint planning and capacity management per `octoacme-project-planning.md`
- Drives retrospective action items referenced in `octoacme-retrospective-and-continuous-improvement.md`

---

## Stakeholder (Customer/User Representative)

### Role Summary
Stakeholders represent end-user and customer perspectives, providing feedback that ensures delivered solutions address real-world needs. They participate in key decision points throughout the project lifecycle to maintain alignment with business priorities.

### Responsibilities
- Provide end-user perspective, feedback, and clarification on business priorities
- Participate in milestone reviews and User Acceptance Testing (UAT)
- Validate that delivered solutions meet defined success criteria
- Collaborate with Product Managers and Project Managers for ongoing alignment
- Contribute to risk identification from a business impact perspective

### Goals
- Ensure delivered solutions provide measurable value to end users
- Maintain visibility into project progress and upcoming changes
- Reduce misalignment between delivered features and actual user needs

### Typical Communication
- Milestone review meetings and UAT sessions
- Feedback submitted through established channels (demos, surveys, review meetings)
- Regular alignment check-ins with Product Manager and Project Manager

### Key Interactions
- Helps set success measures and validate solutions against real-world needs alongside Product Managers
- Provides input during project initiation activities per `octoacme-project-initiation.md`
- Participates in demos and release reviews as outlined in `octoacme-release-and-deployment.md`

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- The eight personas (Developers, Product Managers, Project Managers, UX Designer, Business Analyst, QA Automation Engineer, Scrum Master, and Stakeholder) represent a full cross-functional team and can be combined to simulate realistic project scenarios.
- Assign one or more personas to explore how different roles would approach the same project challenge, such as planning, risk identification, or retrospective facilitation.

