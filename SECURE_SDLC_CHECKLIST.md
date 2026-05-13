
---

# `SECURE_SDLC_CHECKLIST.md`

```markdown
# Secure SDLC Checklist

## Purpose

This checklist supports secure development practices for the Security+ Training Simulations project.

The project is a static GitHub Pages training platform built with HTML, CSS, and JavaScript. The goal of this checklist is to help ensure updates remain safe, maintainable, privacy-conscious, and instructionally accurate.

---

## 1. Planning

Before making changes, confirm:

- [ ] The change has a clear instructional purpose.
- [ ] The change supports Security+ learning or platform usability.
- [ ] The change does not require student data collection.
- [ ] The change does not require accounts, logins, or authentication.
- [ ] The change can be implemented using static HTML, CSS, and JavaScript.
- [ ] The change does not introduce unnecessary complexity.
- [ ] The change does not include actual exam content or proprietary material.

---

## 2. Content Review

Before adding or changing simulation content:

- [ ] Scenarios are original and fictional.
- [ ] Content reinforces general cybersecurity concepts.
- [ ] No actual certification exam questions are included.
- [ ] No exam dumps or proprietary training content are included.
- [ ] Questions and explanations are accurate.
- [ ] Distractors are fair and instructionally useful.
- [ ] Feedback explains why the answer is correct.
- [ ] Content supports applied reasoning, not memorization only.
- [ ] Terminology is appropriate for Security+ learners.

---

## 3. Privacy Review

Before publishing:

- [ ] No names, emails, student IDs, or personal identifiers are included.
- [ ] No student performance data is stored.
- [ ] No analytics or tracking scripts are included.
- [ ] No third-party forms are embedded.
- [ ] No hidden data submission occurs.
- [ ] No cookies are intentionally created.
- [ ] No localStorage/sessionStorage is used unless documented.
- [ ] The privacy policy remains accurate.

---

## 4. Dependency Review

Before adding any library or external resource:

- [ ] Confirm the feature cannot reasonably be built with plain HTML/CSS/JS.
- [ ] Confirm the dependency does not collect data.
- [ ] Confirm the dependency does not require a CDN.
- [ ] Confirm the dependency does not introduce unnecessary supply chain risk.
- [ ] Document the dependency and reason for use.

Preferred project standard:

```text
Avoid external dependencies whenever possible.