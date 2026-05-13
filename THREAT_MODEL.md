
---

# `THREAT_MODEL.md`

```markdown
# Threat Model

## Project Overview

Security+ Training Simulations is a static, browser-based training platform for cybersecurity education and Security+ exam readiness.

The project is hosted through GitHub Pages and uses HTML, CSS, and JavaScript.

There is no backend server, database, login system, student account system, analytics platform, or data collection workflow.

---

## System Scope

In scope:

- Static HTML pages
- Shared CSS
- Client-side JavaScript
- GitHub Pages hosting
- Simulation content
- Dashboard navigation
- Browser-based interaction

Out of scope:

- GitHub platform infrastructure
- User devices
- User networks
- Browser extensions
- Unofficial forks
- Instructor recordkeeping outside this project
- Third-party systems not included in the repository

---

## Assets

Primary assets:

- Original instructional content
- Simulation answer keys
- Scenario logic
- JavaScript interaction logic
- Repository source code
- Project documentation
- Project reputation and trustworthiness

User-related assets:

- User privacy
- Student learning experience
- Confidence that no personal data is collected

---

## Trust Boundaries

### Browser Boundary

All simulation activity occurs in the user's browser.

No simulation data is intentionally transmitted outside the browser by project code.

### GitHub Pages Boundary

GitHub Pages serves static project files.

GitHub may process hosting logs according to GitHub's policies, but the project code does not collect or submit user data.

### Repository Boundary

Maintainers control project source files through Git and GitHub.

Unauthorized or accidental changes to content, links, or JavaScript could affect simulation accuracy or usability.

---

## Data Flow

Typical user flow:

```text
User opens GitHub Pages site
        ↓
Browser loads static HTML/CSS/JS
        ↓
User launches a simulation
        ↓
User interacts with local JavaScript
        ↓
Browser displays feedback locally
        ↓
No project data is submitted or stored