# Contributing to TweetStorm-Real-Time-Social-Media-Web-App

## 1. Philosophy and Alignment

Welcome to the development of **TweetStorm-Real-Time-Social-Media-Web-App**. As defined by the Apex Technical Authority, all contributions must adhere to the **Zero-Defect, High-Velocity, Future-Proof** philosophy. We treat this repository as a professional, high-availability system.

Before submitting a contribution, please ensure you have reviewed the **`AGENTS.md`** file to understand the core architectural mandates (SOLID, DRY, FSD/Modular Monolith principles depending on context) and the technology stack.

## 2. Repository Context and Stack

This project is a modern, full-stack JavaScript/TypeScript application designed for real-time interaction. Contributions should target the established modern toolchain:

*   **Language:** TypeScript (Strict Mode)
*   **Build/Bundling:** Vite 7+
*   **Styling:** TailwindCSS v4
*   **Real-Time:** WebSockets (e.g., Socket.io or native WS implementation)
*   **Testing:** Vitest (Unit) and Playwright (E2E)
*   **Architecture:** Feature-Sliced Design (FSD) for frontend modularity.

## 3. Code of Conduct

This project adheres to the Contributor Covenant, Version 2.1. All contributors are expected to uphold these standards. Report any unacceptable behavior via a direct message to user `chirag127` or through the appropriate GitHub reporting mechanism.

## 4. Contribution Workflow

We follow a structured workflow to maintain integrity and velocity:

### Step 1: Preparation

1.  **Fork the Repository:** Create a fork of `chirag127/TweetStorm-Real-Time-Social-Media-Web-App`.
2.  **Clone:** Clone your fork locally:
    bash
    git clone https://github.com/YOUR_USERNAME/TweetStorm-Real-Time-Social-Media-Web-App.git
    cd TweetStorm-Real-Time-Social-Media-Web-App
    
3.  **Create a Feature Branch:** Ensure your branch name clearly indicates the scope of your change (e.g., `feat/websocket-reconnect`, `fix/feed-rendering-bug`, `refactor/auth-service`).
    bash
    git checkout -b <branch-name>
    

### Step 2: Development and Verification

1.  **Implement Changes:** Focus on creating clean, well-documented code that aligns with the established FSD/Modular architecture.
2.  **Linting and Formatting:** Before committing, ensure all code passes the necessary checks enforced by Biome (or equivalent for JS/TS stack):
    bash
    npm run lint
    npm run format
    
3.  **Testing:** **All new features MUST include corresponding unit and/or integration tests.** Existing tests must pass.
    bash
    npm run test:unit  # Run Vitest
    npm run test:e2e     # Run Playwright
    
4.  **Documentation Update:** If you modify APIs, core logic, or introduce new concepts, update the relevant documentation files (`README.md`, `AGENTS.md`, etc.).

### Step 3: Submission

1.  **Commit Messages:** Use Conventional Commits (e.g., `feat:`, `fix:`, `chore:`, `refactor:`).
2.  **Push:** Push your changes to your fork:
    bash
    git push origin <branch-name>
    
3.  **Open a Pull Request (PR):** Navigate to the main repository and open a PR from your feature branch targeting the `main` branch.

## 5. Pull Request Requirements

Every PR must use the **PULL_REQUEST_TEMPLATE.md** and meet these criteria:

*   **Automated Checks:** All GitHub Actions workflows (CI build, linting, testing) must pass successfully.
*   **Self-Review:** Review your own changes for clarity, adherence to SOLID/DRY principles, and performance implications.
*   **Context:** Clearly describe *what* was changed and *why* it was changed, referencing any relevant issues.

## 6. Reporting Issues and Security Vulnerabilities

*   **Bugs:** Use the **Bug Report** issue template located in `.github/ISSUE_TEMPLATE/bug_report.md`.
*   **Security:** Please follow responsible disclosure protocols. Report security concerns privately via **SECURITY.md** guidelines or directly to `security@chirag127.com` before making a public issue.

## 7. Repository Links (Static References)

For immediate reference during development, here are key development standards:

| Standard | Location |
| :--- | :--- |
| **CI/CD Pipeline** | `.github/workflows/ci.yml` |
| **Testing Requirements** | `AGENTS.md` |
| **License Terms** | `LICENSE` (CC BY-NC 4.0) |
| **Project Metadata** | `badges.yml` |

*Thank you for investing your time and expertise into this project. We appreciate high-quality contributions.*