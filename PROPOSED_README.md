<p align="center">
  <img src="https://assets-global.website-files.com/652f44778393e5066c1f728c/659103e22b0c1b7535492d52_AdobeStock_343603407%20(1)-p-500.jpg" alt="FluentPDF - AI PDF To Audio Web App" width="800"/>
</p>

<h1 align="center">FluentPDF-AI-PDF-To-Audio-Web-App</h1>

<p align="center">
  <a href="https://github.com/chirag127/FluentPDF-AI-PDF-To-Audio-Web-App/actions/workflows/ci.yml">
    <img src="https://img.shields.io/github/actions/workflow/status/chirag127/FluentPDF-AI-PDF-To-Audio-Web-App/ci.yml?branch=main&style=flat-square" alt="Build Status">
  </a>
  <a href="https://codecov.io/gh/chirag127/FluentPDF-AI-PDF-To-Audio-Web-App">
    <img src="https://img.shields.io/codecov/c/github/chirag127/FluentPDF-AI-PDF-To-Audio-Web-App?style=flat-square" alt="Code Coverage">
  </a>
  <a href="https://github.com/chirag127/FluentPDF-AI-PDF-To-Audio-Web-App">
    <img src="https://img.shields.io/badge/Tech%20Stack-JavaScript%20%7C%20Vite%20%7C%20Gemini%20AI-blueviolet?style=flat-square" alt="Tech Stack">
  </a>
  <a href="https://github.com/chirag127/FluentPDF-AI-PDF-To-Audio-Web-App">
    <img src="https://img.shields.io/badge/Lint%2FFormat-Biome-informational?style=flat-square" alt="Lint/Format">
  </a>
  <a href="https://github.com/chirag127/FluentPDF-AI-PDF-To-Audio-Web-App/blob/main/LICENSE">
    <img src="https://img.shields.io/badge/License-CC%20BY--NC%204.0-lightgrey?style=flat-square" alt="License">
  </a>
  <a href="https://github.com/chirag127/FluentPDF-AI-PDF-To-Audio-Web-App/stargazers">
    <img src="https://img.shields.io/github/stars/chirag127/FluentPDF-AI-PDF-To-Audio-Web-App?style=flat-square&colorA=white&colorB=blue" alt="GitHub Stars">
  </a>
</p>

<p align="center">
  Star ⭐ this Repo
</p>

---

## 🚀 Overview

FluentPDF transforms complex technical PDFs into accessible, natural-sounding audio content directly in your browser. Leveraging Google Gemini AI, it intelligently optimizes documents for text-to-speech, fostering multimodal learning and enhancing accessibility.

This 100% browser-based web application offers advanced text extraction, robust offline processing capabilities, customizable AI prompts for nuanced content adaptation, and an intuitive user interface, making specialized knowledge more digestible for everyone.

---

## 🏛️ Architecture

FluentPDF is structured as a modular, client-side web application, emphasizing clear separation of concerns and efficient data flow.


.
├── public/                 # Static assets (index.html, favicon)
├── src/                    # All application source code
│   ├── app/                # Core application logic and initialization
│   │   ├── api/            # Gemini API integration and response handling
│   │   ├── config/         # Application settings and constants
│   │   └── services/       # Core services (PDF processing, TTS engine)
│   ├── features/           # Feature-specific modules
│   │   ├── document-upload/  # PDF upload and initial parsing
│   │   ├── text-extraction/  # Advanced text extraction logic
│   │   ├── ai-optimization/  # AI prompt management and content transformation
│   │   ├── audio-playback/   # Audio player and controls
│   │   └── settings/         # User preferences and customization
│   ├── shared/             # Reusable components, utilities, and types
│   │   ├── components/     # UI components (buttons, modals, input fields)
│   │   ├── hooks/          # React hooks or similar patterns for state logic
│   │   ├── lib/            # Utility functions (date, string manipulation)
│   │   └── types/          # TypeScript type definitions
│   ├── styles/             # Global stylesheets and Tailwind configuration
│   └── main.js             # Application entry point
├── .github/                # GitHub-specific files (workflows, issue templates)
├── .vscode/                # VS Code settings
├── node_modules/           # Project dependencies
├── package.json            # Project metadata and scripts
├── vite.config.js          # Vite configuration
├── tailwind.config.js      # Tailwind CSS configuration
├── biome.json              # Biome linter/formatter configuration
├── vitest.config.js        # Vitest configuration
└── README.md


---

## 📖 Table of Contents

*   [🚀 Overview](#-overview)
*   [🏛️ Architecture](#️-architecture)
*   [📖 Table of Contents](#-table-of-contents)
*   [🤖 AI Agent Directives](#-ai-agent-directives)
*   [⚙️ Development Standards](#️-development-standards)
    *   [Setup](#setup)
    *   [Available Scripts](#available-scripts)
    *   [Core Development Principles](#core-development-principles)
*   [🤝 Contributing](#-contributing)
*   [🛡️ Security](#️-security)
*   [📜 License](#-license)

---

<details>
<summary><h2>🤖 AI Agent Directives</h2></summary>

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
    *   **No Guessing:** Do not hallucinate APIs.
    *   **Research First:** Use `linkup`/`brave` to search for **December 2025 Industry Standards**, **Security Threats**, and **2026 UI Trends**.
    *   **Validation:** Use `docfork` to verify *every* external API signature.
    *   **Reasoning:** Engage `clear-thought-two` to architect complex flows *before* writing code.

---

## 3. CONTEXT-AWARE APEX TECH STACKS (LATE 2025 STANDARDS)
**Directives:** This repository, `FluentPDF-AI-PDF-To-Audio-Web-App`, is a 100% browser-based JavaScript web application leveraging Google Gemini AI for content transformation.

*   **PRIMARY SCENARIO: WEB / APP / GUI (Modern Frontend)**
    *   **Stack:** This project leverages **Modern JavaScript (ESM)**. Key tools include **Vite** (for fast development and optimized builds), **TailwindCSS v4** (for utility-first styling), and direct browser APIs for PDF processing and audio playback. **Google Gemini API** (`gemini-3-pro` by default) is integrated for AI-powered text optimization, ensuring modularity, secure API key handling, and robust error management.
    *   **Lint/Format:** **Biome** (for ultra-fast linting and formatting, ensuring code consistency and quality).
    *   **Testing:** **Vitest** (for unit and integration testing of JavaScript modules, ensuring core logic and AI integrations are robust). **Playwright** is recommended for future E2E browser testing.
    *   **Architecture:** Adheres to a **Modular Web Component-based Architecture** with clear separation of concerns (e.g., PDF parsing, AI processing, audio playback, UI components). Principles of **Feature-Sliced Design (FSD)** are applied at a conceptual level to organize features into self-contained slices, even without a formal framework.
    *   **Accessibility:** All UI components and interaction flows **MUST** prioritize WCAG 2.2 AA compliance, especially for an app focused on accessibility.

*   **SECONDARY SCENARIO B: SYSTEMS / PERFORMANCE (Rust/Go) - *Not applicable for this project. Reference only.***
    *   **Stack:** Rust (Cargo) or Go (Modules).
    *   **Lint:** Clippy / GolangCI-Lint.
    *   **Architecture:** Hexagonal Architecture (Ports & Adapters).

*   **SECONDARY SCENARIO C: DATA / AI / SCRIPTS (Python) - *Not applicable for this project. Reference only.***
    *   **Stack:** uv (Manager), Ruff (Linter), Pytest (Test).
    *   **Architecture:** Modular Monolith or Microservices.

---

## 4. APEX NAMING CONVENTION (THE "STAR VELOCITY" ENGINE)
*   **Formula:** `<Product-Name>-<Primary-Function>-<Platform>-<Type>`
*   **Current Project Name:** `FluentPDF-AI-PDF-To-Audio-Web-App`
*   **Compliance:** Adheres to the Apex Naming Convention, clearly indicating its product (`FluentPDF`), function (`AI-PDF-To-Audio`), platform (`Web`), and type (`App`).

---

## 5. APEX DEVELOPMENT LIFECYCLE DIRECTIVES
1.  **Version Control:** All work flows through feature branches (`feat/*`, `fix/*`, `chore/*`) merging into `main` via Squash & Merge Pull Requests.
2.  **Code Review:** Mandatory for all changes. Focus on correctness, maintainability, performance, and security.
3.  **Testing:** Comprehensive unit, integration, and (where applicable) E2E tests are required. Minimum 80% code coverage.
    *   **Unit Tests:** Use **Vitest** for JavaScript modules.
    *   **Integration Tests:** Simulate interactions between features and external APIs (mocked).
    *   **E2E Tests:** (Future consideration) Use **Playwright** for critical user flows in the browser.
4.  **CI/CD:** Automated pipelines (`.github/workflows/ci.yml`) for linting, testing, and deployment.
5.  **Documentation:** `README.md` as the SSOT. All significant features, APIs, and complex logic blocks require inline comments or dedicated documentation.
6.  **Security:** Implement secure coding practices. Proactive threat modeling, input validation, output encoding, and dependency scanning are paramount.
7.  **Performance:** Optimize for browser performance: lazy loading, efficient DOM manipulation, minimal re-renders, and optimized asset delivery.
8.  **Error Handling:** Robust, user-friendly error handling for all API interactions, file operations, and unexpected application states.
9.  **Scalability:** Design for future enhancements and potential increased data processing within the browser environment.
10. **Maintainability:** Adhere to clean code principles, clear naming conventions, and modular design to ensure long-term maintainability.

---

## 6. VERIFICATION & COMMANDS
To ensure the system is operating optimally, execute the following:

*   **Setup Dependencies:**
    bash
    npm install
    
*   **Run Linter & Formatter (Biome):**
    bash
    npm run lint
    npm run format
    
*   **Run Unit & Integration Tests (Vitest):**
    bash
    npm test
    
*   **Start Development Server (Vite):**
    bash
    npm run dev
    
*   **Build for Production:**
    bash
    npm run build
    
*   **Run Production Build Locally (Serve):**
    bash
    npm run preview
    

</details>

---

## ⚙️ Development Standards

### Setup

To get a local copy up and running, follow these simple steps.

1.  **Clone the repository:**
    bash
    git clone https://github.com/chirag127/FluentPDF-AI-PDF-To-Audio-Web-App.git
    cd FluentPDF-AI-PDF-To-Audio-Web-App
    
2.  **Install dependencies:**
    bash
    npm install
    
3.  **Configure Environment Variables (if any):**
    Create a `.env` file in the root directory and add your Google Gemini API key:
    
    VITE_GEMINI_API_KEY=YOUR_GEMINI_API_KEY
    
    (Note: For a client-side app, this key would typically be proxied or restricted to browser domains for security, or rely on user-provided keys for direct browser access.)

### Available Scripts

In the project directory, you can run:

| Script          | Description                                                    |
| :-------------- | :------------------------------------------------------------- |
| `npm run dev`   | Starts the development server with hot-reloading.              |
| `npm run build` | Builds the app for production to the `dist` folder.            |
| `npm run lint`  | Runs Biome to lint JavaScript/TypeScript files.                |
| `npm run format`| Runs Biome to format JavaScript/TypeScript files.              |
| `npm test`      | Runs the test suite using Vitest.                              |
| `npm run preview`| Serves the production build locally.                          |

### Core Development Principles

This project adheres to the following engineering principles to ensure high quality and maintainability:

*   **S.O.L.I.D Principles:** Applied to JavaScript modules and components for maintainable and scalable code.
*   **D.R.Y (Don't Repeat Yourself):** Avoid redundant code to minimize bugs and improve efficiency.
*   **Y.A.G.N.I (You Ain't Gonna Need It):** Implement only features that are currently required, preventing over-engineering.
*   **Modularity:** Emphasize small, focused, and reusable modules/components with clear responsibilities.
*   **Accessibility First:** Design and implement all UI/UX with a strong focus on WCAG 2.2 AA compliance.
*   **Security by Design:** Proactive measures in API key handling, input validation, and preventing client-side vulnerabilities.

---

## 🤝 Contributing

We welcome contributions! Please refer to our [Contributing Guidelines](.github/CONTRIBUTING.md) for details on how to get started, report bugs, or suggest features.

---

## 🛡️ Security

For information on security practices and how to report vulnerabilities, please refer to our [Security Policy](.github/SECURITY.md).

---

## 📜 License

This project is licensed under the [Creative Commons Attribution-NonCommercial 4.0 International License (CC BY-NC 4.0)](LICENSE).
