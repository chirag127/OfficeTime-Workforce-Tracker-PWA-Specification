# 🤝 Contributing to OfficeTimeTracker-Progressive-Web-App-Specification

Thank you for considering contributing to the `OfficeTimeTracker-Progressive-Web-App-Specification`. As an Apex Authority Project, we demand adherence to the highest standards of clarity, rigor, and future-proofing. Contributions should focus on enhancing the architectural fidelity, requirement depth, and technical precision of this PWA specification.

## 1. Foundational Principles (Apex Mandates)

All contributions must align with the following architectural and operational mandates, as defined in the repository's internal documentation:

1.  **Zero-Defect Mentality:** Specifications must be unambiguous and testable. Ambiguity will result in immediate rejection or mandatory revision.
2.  **Future-Proofing (2026 Standard):** Favor technologies and patterns that represent the leading edge (e.g., TypeScript Strict Mode, latest Vite/Tailwind standards, modern PWA lifecycle management).
3.  **DRY & SOLID Adherence:** Architectural suggestions must demonstrate clear separation of concerns (e.g., distinguishing between Manifest requirements, Service Worker logic, and UI components).
4.  **Specification Integrity:** Do not submit partial code snippets unless they explicitly illustrate a non-obvious architectural decision within the specification documents.

## 2. Contribution Workflow

We use a standard, yet rigorous, GitHub flow:

1.  **Fork:** Fork the repository (`https://github.com/chirag127/OfficeTimeTracker-Progressive-Web-App-Specification`).
2.  **Clone:** Clone your fork locally.
3.  **Branch:** Create a new, descriptive feature branch (e.g., `feature/enhance-offline-sync` or `fix/manifest-schema`).
4.  **Commit:** Commit changes following the [Conventional Commits specification](https://www.conventionalcommits.org/en/v1.0.0/).
    *   *Example:* `feat(pwa-manifest): Add required icons for iOS 18 support`
5.  **Pull Request (PR):** Open a Pull Request against the `main` branch of the original repository.

## 3. The Pull Request Template

Your PR **MUST** utilize the provided `PULL_REQUEST_TEMPLATE.md` to structure your submission. Ensure you clearly address:

*   **What problem** this change solves or what feature this specification adds.
*   **Which specification files** (`ARCHITECTURE.md`, `REQUIREMENTS.md`, etc.) were modified.
*   **How this aligns** with the core PWA principles and the established tech stack (TS/Vite/Tailwind).

## 4. Security Disclosure

If you discover a security vulnerability, **DO NOT** open a public issue or pull request. Please follow the documented security process:

1.  Refer to the **Security Policy** located at `.github/SECURITY.md`.
2.  Contact the maintainer directly via the disclosed secure channel.

## 5. Code Style and Formatting

While this repository primarily contains specification documents (Markdown, YAML), any associated configuration files (e.g., `.github/workflows/*.yml`, `badges.yml`) must adhere to the following:

*   **Linting/Formatting:** Configuration files must be valid and easily parsable. If automated linting rules were established (e.g., using Biome or a similar tool within CI), adhere strictly to those output standards.
*   **Clarity:** Use verbose, self-documenting YAML/Markdown syntax.

## 6. Reporting Issues

If you find issues with the *current specification* (e.g., outdated standards, logical inconsistencies, or clarity gaps), please report them using the bug report template:

*   **Template Location:** `.github/ISSUE_TEMPLATE/bug_report.md`

We appreciate your rigorous attention to detail in advancing this critical project specification.