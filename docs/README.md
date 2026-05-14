# Security+ Training Simulations

A browser-based Security+ training simulation platform built to help students strengthen cybersecurity reasoning, scenario analysis, and performance-style exam readiness.

This project contains original, instructor-created simulations designed for students preparing for the CompTIA Security+ certification and entry-level cybersecurity analyst roles. The simulations focus on high-return Security+ concepts that students often struggle with when they move from definitions to applied scenarios.

The goal is not just to help students memorize terms.

The goal is to help students think like analysts.

---

## Live Simulation Platform

[Launch Security+ Training Simulations](https://shanemckenney.github.io/Security-Plus-Training-Simulations/)

Interactive Security+ training simulations focused on:

- Attack identification and remediation
- Firewall ACL analysis
- Host-based incident response
- Physical security controls
- Secure remote access workflows

---

## Project Purpose

As a cybersecurity instructor, I built these simulations to give students practical, repeatable exposure to Security+ concepts before they encounter scenario-driven questions, hands-on labs, or certification-style performance tasks.

Many students can define a concept but struggle when they must apply that concept in context.

These simulations help bridge that gap by requiring students to:

- Read realistic security scenarios carefully
- Identify key indicators and context clues
- Eliminate distractors
- Select appropriate security controls or responses
- Understand why an answer is correct or incorrect
- Practice applied cybersecurity decision-making

---

## AI-Assisted Development / “Vibe Coding” Approach

This project was also built as a proof-of-concept for AI-assisted software development workflows.

The simulations and platform architecture were developed using a combination of:

- ChatGPT
- Claude
- VS Code
- GitHub
- GitHub Pages

The development process combined instructor expertise, cybersecurity knowledge, simulation design, and iterative AI-assisted coding workflows.

Rather than treating AI as a replacement for software engineering or instructional design, this project used AI as a collaborative development accelerator for:

- UI/UX refinement
- Refactoring
- Styling consistency
- Documentation generation
- Static-site architecture planning
- Testing workflows
- GitHub Pages deployment
- Secure SDLC documentation
- Threat modeling
- Simulation interaction design
- Educational content iteration

The instructional logic, simulation concepts, answer validation expectations, and cybersecurity reasoning objectives were intentionally guided and reviewed by a human instructor throughout development.

This repository represents both:

1. A practical cybersecurity training platform
2. A proof-of-concept demonstrating how AI-assisted “vibe coding” workflows can rapidly build structured educational tools when combined with strong human oversight and domain expertise

The project intentionally emphasizes:

- Human-in-the-loop review
- Iterative testing
- Git-based version control
- Secure development practices
- Maintainable static-site architecture
- Clear instructional intent
- Responsible AI-assisted development

The goal was not simply to generate code.

The goal was to explore how modern AI tooling can accelerate the creation of useful, structured educational cybersecurity experiences while maintaining quality, security, and instructional control.

---

## Current Simulation Library

### 1. Attack Identification & Remediation

Students review scenario clues, identify the most likely attack type, and select the best remediation.

**Skills reinforced:**

- Attack recognition
- Threat behavior analysis
- Remediation selection
- Scenario clue interpretation
- Security+ threat pattern recognition

---

### 2. Firewall ACL Analysis

Students analyze firewall rules, determine whether traffic is allowed or blocked, and identify insecure configurations.

**Skills reinforced:**

- Firewall rule analysis
- ACL logic
- Port and protocol recognition
- Least privilege
- Misconfiguration detection
- Exposure analysis

---

### 3. Host-Based Incident Response

Students interact with a simulated command-line environment to investigate suspicious host activity, validate indicators, stop active behavior, and remove persistence.

**Skills reinforced:**

- Incident response workflow
- Process and network correlation
- Command output interpretation
- Persistence detection
- Containment and eradication sequencing
- Analyst decision-making

---

### 4. Physical Security Controls

Students match physical security controls to appropriate locations based on threat type and protection need.

**Skills reinforced:**

- Physical security control selection
- Facility protection
- Threat-to-control mapping
- Layered defense
- Security control purpose

---

### 5. Secure Remote Access Workflow

Students arrange the correct sequence of a secure remote access process.

**Skills reinforced:**

- Secure access workflow
- Authentication
- Authorization
- Least privilege
- Logging and accountability
- Secure remote access reasoning

---

## Instructional Design Approach

These simulations are built around an applied learning model:

```text
Scenario exposure → Student action → Immediate feedback → Explanation → Retry
```

Each activity is designed to give students a practical decision-making experience rather than a passive review experience.

The simulations can be used for:

- Instructor-led review
- Individual student practice
- Small-group activities
- Exam readiness sessions
- Topic reinforcement
- Scenario-based discussion
- Cybersecurity fundamentals practice

---

## Repository Structure

```text
Security-Plus-Training-Simulations/
│
├── archive-originals/
│   ├── attacks-remediations-original.html
│   ├── firewall-acl-analysis-original.html
│   ├── host-based-incident-response-original.html
│   ├── physical-security-original.html
│   └── secure-remote-access-workflow-original.html
│
├── docs/
│   ├── index.html
│   ├── styles.css
│   └── simulations/
│       ├── attack-identification-remediation/
│       │   └── index.html
│       ├── firewall-acl-analysis/
│       │   └── index.html
│       ├── host-based-incident-response/
│       │   └── index.html
│       ├── physical-security-controls/
│       │   └── index.html
│       └── secure-remote-access-workflow/
│           └── index.html
│
├── templates/
│
├── CHANGELOG.md
├── LICENSE
├── PRIVACY.md
├── README.md
├── SECURITY.md
├── SECURE_SDLC_CHECKLIST.md
├── TEST_PLAN.md
└── THREAT_MODEL.md
```

---

## Technology Stack

This project intentionally uses a simple, transparent, and portable technology stack:

- HTML
- CSS
- JavaScript
- GitHub Pages

No frameworks, backend services, databases, analytics, tracking scripts, or external libraries are required.

This keeps the platform:

- Easy to inspect
- Easy to host
- Easy to modify
- Easy to test
- Easy to use in class
- Low-risk from a privacy and security standpoint

---

## Security and Privacy Design

Because this project is cybersecurity-focused, it is built with secure development principles in mind.

Current safeguards include:

- Static-site architecture 
- No user accounts
- No authentication system
- No backend database
- No student data collection
- No analytics or tracking
- No hidden form submission
- No external dependencies
- No third-party scripts
- No score storage
- No personally identifiable information collection

Supporting project documentation includes:

- `SECURE_SDLC_CHECKLIST.md`
- `THREAT_MODEL.md`
- `SECURITY.md`
- `PRIVACY.md`
- `TEST_PLAN.md`

---

## Privacy Statement

These simulations run in the browser and do not collect, transmit, or store student information.

The project does not collect:

- Names
- Email addresses
- Student IDs
- Scores
- Completion data
- Interaction logs
- Device information
- Analytics data

Any scoring or feedback occurs locally in the browser during the activity.

---

## How to Use

### Use Through GitHub Pages

Open the published GitHub Pages site and launch simulations from the dashboard.

### Run Locally

Clone the repository:

```bash
git clone https://github.com/shanemckenney/Security-Plus-Training-Simulations.git
```

Open the project folder in VS Code or another editor.

For best results, use a local development server such as the VS Code Live Server extension and launch:

```text
docs/index.html
```

---

## Recommended Instructor Use

These simulations work best as active learning activities.

Suggested classroom flow:

1. Introduce the topic briefly.
2. Have students attempt the simulation individually or in small groups.
3. Ask students to explain their reasoning.
4. Review the feedback together.
5. Connect the scenario back to Security+ concepts and analyst workflows.
6. Allow students to retry after discussion.

The strongest learning occurs when students explain why an answer is correct, not just whether they selected the right option.

---

## Recommended Student Use

Students should approach each simulation as a cybersecurity reasoning exercise.

Recommended process:

1. Read the scenario carefully.
2. Identify the technical clues.
3. Watch for distractors.
4. Choose the best answer based on the evidence.
5. Review the explanation.
6. Retry until the reasoning makes sense.

The goal is not just to get the answer right.

The goal is to understand why the answer is right.

---

## Content Disclaimer

This project contains original, instructor-created training content.

It does not contain actual CompTIA exam questions, exam dumps, proprietary certification content, or confidential testing material.

The simulations are designed to reinforce general cybersecurity concepts and applied reasoning skills.

Security+ is a trademark of CompTIA. This project is independent and is not affiliated with, endorsed by, or sponsored by CompTIA.

---

## Accessibility and Mobile Use

The project is designed to be lightweight and usable from modern browsers, including mobile devices.

Current design goals include:

- Responsive layouts
- Clear instructions
- Readable text
- Consistent navigation
- Consistent feedback patterns
- Simple browser-based access
- No installation requirement

Some drag-and-drop activities may work best on larger screens depending on the device and browser.

---

## Development Workflow

Recommended update workflow:

```text
Plan change → Update one simulation → Test locally → Commit → Push → Verify GitHub Pages
```

Suggested Git workflow:

```bash
git status
git add .
git commit -m "Describe the update"
git push
```

For simulation updates, avoid changing answer keys, grading logic, or scenario meaning unless the instructional content is intentionally being revised.

---

## Future Development Ideas

Possible future improvements include:

- Additional Security+ domain simulations
- More incident response scenarios
- Expanded CLI-based investigations
- More firewall and network analysis activities
- Instructor notes for each simulation
- Student reflection prompts
- Difficulty tiers
- Practice mode and assessment mode across all simulations
- Improved mobile support for drag-and-drop interactions
- Keyboard accessibility improvements
- Printable instructor guides
- Expanded test plan documentation

---

## Project Philosophy

This project is built around one core idea:

Students need practice thinking through security problems, not just memorizing security terms.

A strong Security+ student should be able to:

- Recognize patterns
- Interpret scenarios
- Explain reasoning
- Select appropriate controls
- Think through risk
- Apply concepts in context
- Make defensible security decisions

These simulations are designed to support that kind of learning.

---

## Author

Created by a cybersecurity instructor, mentor, simulation developer, and AI-assisted workflow builder focused on:

- Security+ exam readiness
- Scenario-based learning
- Secure development practices
- Entry-level cybersecurity analyst preparation
- AI-assisted educational tooling workflows

This project reflects a practical teaching and development approach that combines:

- Cybersecurity instruction
- Simulation design
- Secure SDLC thinking
- Git/GitHub workflow
- Modern AI-assisted development methodologies
- Human-in-the-loop validation and testing

---

## License

See the `LICENSE` file for details.

---

## Contributions

This project is currently maintained as an instructor-developed training resource and AI-assisted development proof-of-concept.

Suggestions for:

- Simulation improvements
- Accessibility enhancements
- Documentation updates
- Additional scenarios
- UI/UX improvements
- Educational tooling ideas

are welcome through the appropriate GitHub workflow.

Please do not submit:

- Copied exam questions
- Exam dumps
- Proprietary certification content
- Confidential testing material

---

## Final Note

These simulations are designed to help learners build confidence, strengthen cybersecurity judgment, and stay in the fight as they prepare for Security+ and entry-level cybersecurity roles.

At the same time, this repository demonstrates how modern AI-assisted “vibe coding” workflows can be combined with human expertise, cybersecurity instruction, secure development practices, and iterative testing to rapidly build meaningful educational technology projects.