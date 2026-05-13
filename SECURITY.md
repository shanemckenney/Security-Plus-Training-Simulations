# Security Policy

## Project Security Overview

Security+ Training Simulations is a static HTML, CSS, and JavaScript project designed for cybersecurity training and Security+ exam readiness practice.

The project is intentionally designed to minimize security risk by avoiding backend services, user accounts, databases, external dependencies, analytics, and data collection.

---

## Supported Versions

This project is maintained through the main branch of the repository.

| Version | Supported |
| ------- | --------- |
| Current main branch | Yes |
| Archived original files | No |

Files in `archive-originals/` are retained for reference and are not considered the active production version of the training platform.

---

## Security Design Principles

This project follows these security principles:

- Static-site architecture
- No backend database
- No authentication system
- No student accounts
- No collection of personal data
- No analytics or tracking scripts
- No external JavaScript libraries
- No third-party CDN dependencies
- No hidden form submissions
- No server-side processing
- Clear content disclaimer
- Manual testing before publishing

---

## Threat Model Summary

The primary risks for this project are related to:

- Accidental introduction of external dependencies
- Broken links or incorrect GitHub Pages paths
- JavaScript errors that break simulation behavior
- Unintended data collection
- Content accuracy issues
- Accessibility or usability issues
- Accidental inclusion of proprietary exam content

This project is not designed to process sensitive data or perform privileged operations.

---

## Reporting a Vulnerability

If you discover a security issue, please report it by opening a GitHub issue or contacting the repository maintainer through the appropriate GitHub workflow.

When reporting a security concern, please include:

- A clear description of the issue
- Affected file or simulation
- Steps to reproduce the issue
- Potential impact
- Suggested fix, if known

Please do not include sensitive personal data in public issue reports.

---

## Out of Scope

The following are generally out of scope for this project:

- Issues caused by GitHub Pages hosting infrastructure
- Browser-specific behavior outside the project code
- Local device security issues
- User-installed browser extensions
- Network filtering or institutional firewall behavior
- Unofficial forks or modified copies of the project

---

## Dependency Policy

This project should avoid external dependencies unless there is a clear instructional or accessibility need.

Before adding any external dependency, consider:

- Is it necessary?
- Can the feature be built with plain HTML, CSS, and JavaScript?
- Does it introduce supply chain risk?
- Does it collect user data?
- Does it require a CDN?
- Does it reduce GitHub Pages portability?

Current preferred approach:

```text
No external dependencies unless explicitly approved and documented.