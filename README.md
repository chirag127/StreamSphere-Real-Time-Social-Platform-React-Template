# StreamSphere: Real-Time Social Platform Engine

[![Build Status](https://img.shields.io/github/actions/workflow/status/chirag127/StreamSphere-Real-Time-Social-Platform-React-Web-App/ci.yml?style=flat-square&label=Build)](https://github.com/chirag127/StreamSphere-Real-Time-Social-Platform-React-Web-App/actions/workflows/ci.yml)
[![Code Coverage](https://img.shields.io/codecov/c/github/chirag127/StreamSphere-Real-Time-Social-Platform-React-Web-App?style=flat-square)](https://codecov.io/gh/chirag127/StreamSphere-Real-Time-Social-Platform-React-Web-App)
[![License](https://img.shields.io/github/license/chirag127/StreamSphere-Real-Time-Social-Platform-React-Web-App?style=flat-square)](LICENSE)
[![GitHub Stars](https://img.shields.io/github/stars/chirag127/StreamSphere-Real-Time-Social-Platform-React-Web-App?style=flat-square)](https://github.com/chirag127/StreamSphere-Real-Time-Social-Platform-React-Web-App)

[![Tech Stack](https://img.shields.io/badge/Stack-TypeScript%20%7C%20Vite%20%7C%20Tailwind%20v4-blue?style=flat-square)](https://www.typescriptlang.org/)

**StreamSphere is a production-ready, high-concurrency boilerplate for scalable, real-time social media applications, engineered for peak frontend performance using the modern React/Vite ecosystem.** This repository serves as the foundational structure, showcasing advanced state management, architectural patterns, and immediate deployment readiness.

<p align="center">
  <a href="https://github.com/chirag127/StreamSphere-Real-Time-Social-Platform-React-Web-App" style="text-decoration: none;">
    <button style="padding: 10px 20px; font-size: 1.2em; cursor: pointer; border-radius: 5px; border: 1px solid #ccc; background-color: #f8f8f8;">
      ⭐ Star ⭐ this Repo to Support Real-Time Web Architecture!
    </button>
  </a>
</p>

---

## 1. Architecture Overview

This project strictly adheres to **Feature-Sliced Design (FSD)** principles layered upon a performant React foundation, ensuring maintainability and scale for complex user interactions.

ascii
StreamSphere Root
├── src/
│   ├── features/      (Business logic & UI Components)
│   │   ├── realtime-feed/
│   │   └── user-auth/
│   ├── pages/         (Route definitions)
│   ├── processes/     (Cross-feature logic/State synchronization)
│   ├── shared/        (Re-usable types, hooks, utilities)
│   └── app/           (Bootstrap, Providers, Routing)
├── public/
├── .github/
└── .husky/


## 2. Table of Contents

1.  [Architecture Overview](#1-architecture-overview)
2.  [Table of Contents](#2-table-of-contents)
3.  [Core Technology Stack](#3-core-technology-stack)
4.  [🤖 AI Agent Directives (Architectural Alignment)](#4-ai-agent-directives-architectural-alignment)
5.  [Getting Started](#5-getting-started)
    *   [Prerequisites](#prerequisites)
    *   [Installation](#installation)
    *   [Running Locally](#running-locally)
6.  [Development Standards & Principles](#6-development-standards--principles)
7.  [Contributing](#contributing)
8.  [License](#license)

## 3. Core Technology Stack

| Component | Technology | Version/Standard | Focus |
| :--- | :--- | :--- | :--- |
| **Language** | TypeScript | Strict Mode (ESNext) | Type Safety & Scalability |
| **Build Tool** | Vite | 5.x+ | Lightning-Fast Development Experience |
| **Styling** | TailwindCSS | v4 (JIT/AOT) | Utility-First Design System |
| **Testing (Unit)** | Vitest | Latest | High-Speed Unit Verification |
| **Testing (E2E)** | Playwright | Latest | Cross-Browser Functional Validation |
| **Linter/Formatter** | Biome | Latest | Unified Code Quality Enforcement |
| **State Mgmt** | Signals/Zustand | (TBD by feature) | Performant Reactive Primitives |

## 4. 🤖 AI Agent Directives (Architectural Alignment)

<details>
  <summary>Click to review mandatory Architectural and Verification Directives for Autonomous Agents</summary>

# SYSTEM: APEX TECHNICAL AUTHORITY & ELITE ARCHITECT (DECEMBER 2025 EDITION)

## 1. IDENTITY & PRIME DIRECTIVE
**Role:** You are a Senior Principal Software Architect and Master Technical Copywriter with **40+ years of elite industry experience**. You operate with absolute precision, enforcing FAANG-level standards and the wisdom of "Managing the Unmanageable."
**Context:** Current Date is **December 2025**. You are building for the 2026 standard.
**Output Standard:** Deliver **EXECUTION-ONLY** results. No plans, no "reporting"—only executed code, updated docs, and applied fixes.
**Philosophy:** "Zero-Defect, High-Velocity, Future-Proof."

---

## 2. INPUT PROCESSING & COGNITION
*   **SPEECH-TO-TEXT INTERPRETATION PROTOCOL:**
    *   **Context:** User inputs may contain phonetic errors (homophones, typos).
    *   **Semantic Correction:** **STRICTLY FORBIDDEN** from executing literal typos. You must **INFER** technical intent based on the project context.
    *   **Logic Anchor:** Treat the `README.md` as the **Single Source of Truth (SSOT)**.
*   **MANDATORY MCP INSTRUMENTATION:**
    *   **No Guessing:** Do not hallucinate APIs. Verify network interactions against known WebSocket/SSE protocols.
    *   **Research First:** Use `linkup`/`brave` to search for **December 2025 Industry Standards**, **Real-Time Performance Bottlenecks**, and **2026 UI Trends**.
    *   **Validation:** Use `docfork` to verify *every* React hook signature and Tailwind JIT configuration.
    *   **Reasoning:** Engage `clear-thought-two` to architect complex asynchronous data synchronization flows *before* writing client-side code.

---

## 3. CONTEXT-AWARE APEX TECH STACKS (LATE 2025 STANDARDS)
**Directives:** This repository (`StreamSphere-Real-Time-Social-Platform-React-Web-App`) is a **WEB / APP / GUI** project.

*   **PRIMARY SCENARIO: WEB / APP / GUI (Modern Frontend)**
    *   **Stack:** TypeScript (Strict), Vite 7 (Rolldown), TailwindCSS v4 (Utility-First).
    *   **Lint/Test:** Biome (Speed) + Vitest (Unit) + Playwright (E2E).
    *   **Architecture:** Feature-Sliced Design (FSD) is mandatory for component organization. State synchronization must leverage Reactive Primitives (Signals) for minimal re-renders.

---

## 4. ARCHITECTURAL VERIFICATION & ENFORCEMENT

**CRITICAL PRINCIPLES:**
1.  **SOLID:** Apply Dependency Inversion (DIP) to all API clients interfacing with the real-time backend (e.g., WebSocket handlers).
2.  **DRY:** Utility functions in `shared/` must be idempotent and pure.
3.  **Performance:** Zero unnecessary re-renders. Use `useMemo`/`useCallback` only when profiling indicates a bottleneck, otherwise rely on Signals/memoization provided by FSD components.

**MANDATORY VERIFICATION COMMANDS (Use these to validate changes):**

*   **LINT/FORMAT CHECK:** `npx @biomejs/biome check --error-on-warnings .`
*   **UNIT TEST EXECUTION:** `npx vitest run --coverage`
*   **E2E TEST EXECUTION:** `npx playwright test`
*   **BUILD CHECK:** `npx vite build`

**ACTION:** Agents must prioritize code clarity, performance benchmarking via included test scripts, and strict adherence to the FSD structure defined in the repository map.

</details>

## 5. Getting Started

### Prerequisites

Ensure you have the following installed on your system:

*   Node.js (Version 20.x LTS or higher)
*   npm or Yarn/pnpm (npm is default for scripts)

### Installation

Clone the repository and navigate into the project directory:

bash
git clone https://github.com/chirag127/StreamSphere-Real-Time-Social-Platform-React-Web-App.git
cd StreamSphere-Real-Time-Social-Platform-React-Web-App

npm install


### Running Locally

Start the development server with hot module replacement enabled:

bash
npm run dev


The application will typically be available at `http://localhost:5173` (Vite default).

### Scripts Table

| Script Name | Command | Description |
| :--- | :--- | :--- |
| `dev` | `npm run dev` | Runs the application in development mode with HMR. |
| `build` | `npm run build` | Compiles the application for production deployment. |
| `test:unit` | `npm run test:unit` | Runs Vitest unit tests with coverage reporting. |
| `test:e2e` | `npm run test:e2e` | Runs Playwright end-to-end tests. |
| `lint` | `npm run lint` | Runs Biome Linter across the codebase. |
| `format` | `npm run format` | Automatically formats code using Biome Formatter. |

## 6. Development Standards & Principles

This project is built on the following immutable architectural tenets:

*   **SOLID:** Strict adherence to the five principles, particularly Dependency Inversion (DIP) for external services.
*   **DRY:** Duplication detection is enforced by Biome checks; refactor immediately.
*   **YAGNI:** Do not build features that are not explicitly required today. Keep the boilerplate minimal yet extensible.
*   **Performance First:** Client-side performance is paramount. Leverage Vite's optimized bundling and utilize React Signals for granular state updates.

## 7. Contributing

Please read our detailed guidelines in [.github/CONTRIBUTING.md](https://github.com/chirag127/StreamSphere-Real-Time-Social-Platform-React-Web-App/blob/main/.github/CONTRIBUTING.md) before submitting Pull Requests or filing issues.

## 8. License

This project is licensed under the **Creative Commons Attribution-NonCommercial 4.0 International License**. See the [LICENSE](LICENSE) file for details.
