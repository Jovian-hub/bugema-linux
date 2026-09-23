# Bugema Linux Governance

## 1. Purpose

This document defines the governance structure, decision-making processes, roles, responsibilities, and contribution authority for the **Bugema Linux** project.

Bugema Linux is an open-source project of the **Bugema Open Source Community (BOSC)** at **Bugema University, Uganda**.

The governance model is designed to ensure that the project remains:

* Technically sustainable
* Open and collaborative
* Secure
* Transparent
* Educational
* Maintainable beyond individual student cohorts
* Aligned with Bugema University's institutional interests

## 2. Governance Principles

Bugema Linux follows these principles:

### 2.1 Open Development

Development should take place openly through GitHub issues, discussions, branches, Pull Requests, reviews, and documented decisions wherever practical.

### 2.2 Merit Through Contribution

Technical responsibility should progressively be earned through demonstrated contribution, technical competence, reliability, and understanding of the project.

### 2.3 Education and Mentorship

Students are encouraged to contribute actively while receiving appropriate mentorship from lecturers, technical staff, maintainers, and experienced contributors.

### 2.4 Institutional Sustainability

The project should not depend on one individual or one student cohort.

Project knowledge, infrastructure, documentation, and technical decisions should therefore be documented and transferred between teams.

### 2.5 Security and Quality

Security, reliability, testing, and maintainability take priority over rapidly merging untested changes.

### 2.6 Open-Source Collaboration

The project welcomes contributions from the wider open-source community, subject to the project's technical, security, licensing, and governance requirements.

---

# 3. Governance Structure

The project uses the following structure:

```text
Bugema University
        │
        ▼
Bugema Open Source Community (BOSC)
        │
        ▼
Bugema Linux Project
        │
        ├── Project Maintainers
        │
        ├── Technical Team Leads
        │
        ├── Contributors
        │
        └── Student Contributors
```

The structure separates institutional oversight from day-to-day technical development.

---

# 4. Institutional Context

Bugema Linux operates under the broader activities of the **Bugema Open Source Community (BOSC)**.

Institutional matters that require formal University approval should follow the applicable Bugema University administrative procedures.

GitHub project governance does not replace University policies, regulations, or approval processes.

---

# 5. Project Maintainers

Maintainers are responsible for the technical health and continuity of Bugema Linux.

Maintainer responsibilities include:

* Reviewing Pull Requests
* Maintaining project standards
* Coordinating releases
* Reviewing significant architectural changes
* Managing project permissions
* Maintaining the repository
* Coordinating technical teams
* Ensuring documentation is maintained
* Supporting contributor onboarding
* Coordinating security responses
* Protecting the integrity of the `main` branch

Maintainers should not merge their own significant changes without appropriate review.

---

# 6. Project Lead

The Project Lead provides overall technical and organizational coordination for Bugema Linux.

Responsibilities may include:

* Coordinating project direction
* Coordinating BOSC and Bugema Linux activities
* Facilitating institutional engagement
* Supporting resource mobilization
* Coordinating major releases
* Resolving escalated technical or organizational issues
* Supporting continuity between student cohorts

The Project Lead should work with maintainers and technical leads rather than functioning as the sole developer.

---

# 7. Technical Team Leads

Bugema Linux may establish specialized technical teams as the project grows.

Potential teams include:

```text
Core Systems
Desktop & UX
Applications & Packages
Installer
Testing & Quality Assurance
Security
DevOps & CI/CD
Documentation
```

Team leads are responsible for:

* Coordinating work within their technical area
* Reviewing relevant Pull Requests
* Helping contributors
* Creating technical tasks
* Identifying testing requirements
* Maintaining documentation
* Reporting significant technical issues to maintainers

---

# 8. Contributors

Contributors include:

* Bugema University students
* Academic staff
* Technical staff
* Researchers
* Alumni
* Open-source developers
* External collaborators

Contributors work through GitHub issues and Pull Requests.

Contributors do not automatically receive project administration privileges.

---

# 9. Student Contributors

Students are important contributors to Bugema Linux.

Students may:

* Create issues
* Work on assigned tasks
* Create branches
* Submit Pull Requests
* Review peer contributions
* Write documentation
* Conduct testing
* Participate in technical teams
* Propose new features

Student contributors should normally operate with the minimum permissions necessary to perform their assigned work.

Students should not receive repository or organization administration privileges simply because they are enrolled in a course.

---

# 10. Open Source Systems Course

Bugema Linux may be used as a practical project for the **Open Source Systems** course.

The course and the production project remain related but distinct.

The course provides:

* Learning objectives
* Assignments
* Student assessment
* Team activities
* Practical exercises

The Bugema Linux project provides:

* Real development tasks
* Real issues
* Technical review
* Production-quality standards
* Open-source contribution experience

Academic assessment decisions remain under the appropriate academic authority.

Technical acceptance into Bugema Linux remains under the project's contribution and review process.

---

# 11. Decision-Making

Decisions should normally be made at the lowest appropriate technical level.

### Routine technical decisions

Technical team leads may make routine decisions within their areas.

### Cross-team decisions

Issues affecting multiple technical areas should involve the relevant maintainers and team leads.

### Architectural decisions

Major architectural changes should be discussed openly and documented before implementation.

Examples include:

* Changing the Linux base distribution
* Major desktop environment changes
* New build architecture
* Installer architecture
* Major security architecture
* Repository restructuring
* Major dependency changes

### Institutional decisions

Decisions involving University policy, official institutional branding, deployment across University infrastructure, financial commitments, or formal partnerships should follow appropriate Bugema University procedures.

---

# 12. Pull Request Authority

The normal process is:

```text
Contributor
    ↓
Pull Request
    ↓
Peer Review
    ↓
Technical Review
    ↓
Approval
    ↓
Maintainer Merge
```

No contributor should bypass the review process for significant changes.

---

# 13. Main Branch

The `main` branch represents the stable project development line.

Direct pushes to `main` should be restricted once repository branch protection has been configured.

Changes should normally enter `main` through reviewed Pull Requests.

---

# 14. Releases

Bugema Linux releases should be documented and reproducible as far as technically practical.

Each significant release should include:

* Version number
* Release date
* Release notes
* Major changes
* Known issues
* Testing information
* Installation information
* Checksums where applicable

Example:

```text
Bugema Linux Alpha 0.1
Bugema Linux Alpha 0.2
Bugema Linux Beta 0.1
Bugema Linux 1.0
```

Release maturity should reflect the actual level of testing and stability.

---

# 15. Security Governance

Security-sensitive changes require additional review.

Security issues should be handled according to the project's security reporting process.

Maintainers may temporarily restrict information about a vulnerability when public disclosure could increase risk.

---

# 16. Conflict Resolution

Technical disagreements should first be handled through evidence-based discussion.

Contributors should consider:

* Technical requirements
* Security
* Maintainability
* Testing evidence
* Compatibility
* Project objectives
* User requirements

If a disagreement cannot be resolved within a technical team, it may be escalated to the project maintainers.

Institutional matters may be escalated through the appropriate Bugema University structures.

---

# 17. Contributor Conduct

All contributors are expected to communicate respectfully and professionally.

Harassment, discrimination, intimidation, malicious behavior, and deliberate disruption of the project are not acceptable.

The project's Code of Conduct will provide additional guidance.

---

# 18. Permissions

Repository and organization permissions should follow the principle of least privilege.

Recommended general approach:

| Role                  | Typical Access                             |
| --------------------- | ------------------------------------------ |
| Student Contributor   | Write/Issue access as required             |
| Contributor           | Appropriate repository contribution access |
| Technical Team Lead   | Write/Maintain as required                 |
| Maintainer            | Maintain                                   |
| Project Administrator | Administrative access                      |
| Organization Owner    | Limited institutional administrators       |

Administrative privileges should be restricted to trusted individuals who require them.

---

# 19. Succession and Continuity

Bugema Linux should remain operational when students complete their courses or graduate.

To support continuity:

* Documentation should be maintained.
* Technical decisions should be recorded.
* Team responsibilities should be documented.
* Maintainer knowledge should be transferred.
* Important infrastructure should not depend on personal accounts.
* Access should be reviewed when project members leave their roles.

Each academic year should include a transition process between student cohorts where applicable.

---

# 20. Transparency

Important project decisions should be documented through appropriate GitHub mechanisms, including:

* Issues
* Pull Requests
* Discussions
* Documentation
* Release notes

This creates an institutional technical history that future contributors can understand.

---

# 21. Changes to Governance

This governance document may evolve as Bugema Linux grows.

Changes should normally be proposed through a GitHub issue or Pull Request and reviewed by project maintainers.

Changes affecting institutional authority or University policy should follow the appropriate University procedures.

---

# 22. Long-Term Direction

Bugema Linux is intended to evolve from an educational open-source project into a sustainable institutional technology platform.

Possible future areas include:

* University laboratory deployment
* Research computing
* IoT development
* AI and machine learning
* Cybersecurity education
* Software engineering laboratories
* Developer workstations
* Offline educational computing
* Open educational resources
* Institutional computing environments
* Collaboration with other universities
* Research and innovation projects

The project's technical architecture should therefore prioritize sustainability and maintainability from the beginning.
## 23. Roles and responsibilities
* This defines the organisation chart who exists what they can do, what is expected of them.
## 24. Becoming a maintainer
* This defines the promotion path, the criteria and process for gaining power.

---

## Maintained By

**Bugema Open Source Community (BOSC)**
**Bugema University, Uganda**
 **Learn. Build. Share. Innovate.**
