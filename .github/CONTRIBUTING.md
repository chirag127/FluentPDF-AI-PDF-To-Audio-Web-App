# 🤝 Contributing to SpokablePDF-AI-Powered-PDF-To-Speech-Web-App

As the Apex Technical Authority mandates, contributions to this project must adhere to the highest standards of quality, performance, and architectural integrity. We treat this codebase as a professional, future-proof asset.

## 1. Core Principles (The Apex Mandate)

All contributions must align with the following architectural philosophies:

*   **SOLID:** Single Responsibility, Open/Closed, Liskov Substitution, Interface Segregation, Dependency Inversion.
*   **DRY:** Don't Repeat Yourself. Refactor duplicated logic immediately.
*   **YAGNI:** You Ain't Gonna Need It. Avoid premature abstraction or feature creep.
*   **Zero-Defect Velocity:** High-quality commits over speed. Automated checks must pass before PR submission.

## 2. Development Environment Setup

This project utilizes a modern JavaScript/TypeScript stack managed via Vite and assumes Node.js (LTS/Current). We utilize Biome for integrated linting and formatting.

1.  **Clone the Repository:**
    bash
    git clone https://github.com/chirag127/SpokablePDF-AI-Powered-PDF-To-Speech-Web-App.git
    cd SpokablePDF-AI-Powered-PDF-To-Speech-Web-App
    

2.  **Install Dependencies (using npm/yarn/pnpm):**
    bash
    npm install
    

3.  **Run Local Checks (Pre-flight Validation):**
    Ensure your local environment passes all static analysis checks before committing.
    bash
    # Run formatting and linting checks enforced by Biome
    npm run lint
    # Run unit tests using Vitest
    npm run test:unit
    

## 3. Contribution Workflow

We follow a standard feature-branch workflow managed through Pull Requests (PRs).

1.  **Branch Out:** Create a feature or fix branch from `main`.
    bash
    git checkout -b feat/short-descriptive-name
    

2.  **Develop & Test:** Implement changes. Ensure any new logic is accompanied by corresponding unit/integration tests to maintain high coverage (>90%).

3.  **Commit Standards:** Use conventional commits (e.g., `feat:`, `fix:`, `refactor:`, `chore:`).
    bash
    git commit -m "feat: Implement Gemini processing pipeline for PDF chunking"
    

4.  **Push and Open PR:** Push your branch and open a Pull Request targeting the `main` branch.

## 4. Pull Request (PR) Requirements

Every PR **must** satisfy the following criteria to be considered for review:

*   **Clarity:** The PR description must reference the relevant issue (if applicable) and clearly state the technical change implemented.
*   **Verification:** All automated checks (CI/CD pipeline defined in `.github/workflows/ci.yml`) must pass successfully. Do not request a review until checks pass.
*   **Scope:** PRs should address a single, logical change set. Large, multi-feature PRs will be sent back for splitting.
*   **Documentation Updates:** If new features or significant refactors are introduced, update `README.md`, `AGENTS.md`, and any other relevant documentation.

## 5. Reporting Issues

If you discover a bug, security vulnerability, or have a feature suggestion, please utilize the provided templates:

*   **Bug Reports:** Use the template found in `.github/ISSUE_TEMPLATE/bug_report.md`.
*   **Feature Requests:** Use the standard Issue creation tool, ensuring technical feasibility and alignment with the project's core mission (PDF-to-TTS transformation).

## 6. Code of Conduct

Be professional, respectful, and constructive in all interactions. Refer to the principles outlined in our Security Policy and general community standards. We seek high technical discourse, not personal conflict.

--- 
*Thank you for contributing to the advancement of accessible digital content transformation.*
