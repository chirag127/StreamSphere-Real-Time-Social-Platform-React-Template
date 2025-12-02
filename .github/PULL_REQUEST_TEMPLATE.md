# 🚀 Pull Request Template: Apex Contribution Standard

**Project:** `TweetStorm-Real-Time-Social-Media-Web-App`

By submitting this Pull Request (PR), you affirm adherence to the **Apex Technical Authority** guidelines: Zero-Defect, High-Velocity, Future-Proof.

---

## ✅ Checklist

Before submitting, please verify the following:

- [ ] **Self-Review:** Have you reviewed your changes against the **Architectural Principles** (SOLID, DRY)?
- [ ] **Testing:** Have you added or updated necessary unit/integration tests? (See Verification Commands below).
- [ ] **Linting/Formatting:** Does the code pass local checks using the Apex toolchain? (`npm run lint` or equivalent).
- [ ] **Documentation:** Are relevant sections of `README.md` or related documentation updated?
- [ ] **Branch:** Is the source branch up-to-date with `main`/`master` (squash/rebase recommended)?

---

## 📝 Description of Changes

**BLUF (Bottom Line Up Front):** Briefly summarize the feature, fix, or refactor this PR introduces. (Max 3 sentences).

<!-- Detailed breakdown of the changes, why they were made, and any trade-offs considered. -->

## 🧠 Architectural Alignment

How does this change align with the current architecture (Feature-Sliced/Modular Monolith)?

*   **Feature/Module Affected:** 
*   **Impact Assessment:** (e.g., Increased coupling, performance uplift, security enhancement).

## 🔗 Related Issues

Closes, references, or addresses issues:

*   `Closes #<ISSUE_NUMBER>`
*   `Fixes #<ISSUE_NUMBER>`

---

## 🤖 Agent Directives Verification (Crucial for CI)

Ensure your local environment validates against the standards defined in `.github/AGENTS.md`.

**For this JavaScript/TypeScript stack, execute the following:**

bash
# 1. Dependency Resolution & Setup (using uv/npm standards)
npm install

# 2. Fast Linting & Formatting Check (Biome)
npm run format:check

# 3. Unit Testing (Vitest)
npm run test:unit

# 4. End-to-End Verification (Playwright/Cypress)
npm run test:e2e


Failure in any of these steps indicates a required rollback or correction before merging.