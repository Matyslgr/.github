# 🤝 Contributing Guidelines

First off, thank you for considering contributing to this project!
We value your time and effort. Following these guidelines helps us maintain high code quality and streamlines the review process.

---

## Table of Contents
1. [Getting Started](#-getting-started)
2. [Branching Strategy](#-branching-strategy)
3. [Development Workflow](#-development-workflow)
4. [Commit Convention](#-commit-convention)
5. [Pull Request Process](#-pull-request-process)
6. [Coding Standards](#-coding-standards)
7. [Community & Conduct](#-community--conduct)

---

## 🚀 Getting Started

Before you start writing code, please ensure your environment is set up correctly.

1.  **Read the README**: Every project has specific installation instructions (dependencies, environment variables) in its `README.md`.
2.  **Fork & Clone**: Fork the repository to your account, then clone it locally.
3.  **Install Dependencies**: Run the build/install commands specified in the project's documentation.

> **Tip:** If you are unsure about the setup, please open a [Question Issue](../../issues/new?template=question.yml) before starting.

---

## 🌿 Branching Strategy

We follow a standard **Feature Branch Workflow**.

- **`main` (or `master`)**: The stable branch. Do not push directly to it.
- **`dev`** (if applicable): The integration branch for the next release.

### Naming Convention
Name your branches descriptively using the following prefixes:

- `feature/` → New features (e.g., `feature/login-system`)
- `fix/` → Bug fixes (e.g., `fix/header-alignment`)
- `refactor/` → Code improvements (e.g., `refactor/auth-middleware`)
- `docs/` → Documentation changes (e.g., `docs/api-reference`)
- `chore/` → Maintenance tasks (e.g., `chore/update-dependencies`)

---

## 🔄 Development Workflow

1.  **Sync**: Always pull the latest changes from the upstream `main` (or `dev` if exists) branch before creating your branch.
2.  **Create Branch**: `git checkout -b feature/my-awesome-feature`
3.  **Code**: Make your changes. Keep them focused and atomic.
4.  **Test**: Run the project's test suite locally to ensure no regressions.
5.  **Push**: `git push origin feature/my-awesome-feature`

---

## 💬 Commit Convention

We follow the **[Conventional Commits](https://www.conventionalcommits.org/)** specification. This allows us to generate changelogs automatically.

**Format:**
```text
<type>(<scope>): <short description>
```

**Types:**
- `feat`: A new feature
- `fix`: A bug fix
- `docs`: Documentation only changes
- `style`: Changes that do not affect the meaning of the code (white-space, formatting, etc)
- `refactor`: A code change that neither fixes a bug nor adds a feature
- `perf`: A code change that improves performance
- `test`: Adding missing tests or correcting existing tests
- `chore`: Changes to the build process or auxiliary tools/libraries

**Examples:**
- `feat(auth): add JWT token validation`
- `fix(ui): correct button padding on mobile`
- `chore(deps): upgrade react to v18`

---

## 📥 Pull Request Process

When you are ready to submit your contribution:

1.  **Self-Review**: Look through your changes one last time. Did you leave any console logs or commented-out code?
2.  **Open PR**: Select the appropriate template (Bug Fix, Feature, etc.).
3.  **Link Issues**: Use keywords like `Closes #123` or `Fixes #456` in the description.
4.  **CI Checks**: Ensure all GitHub Actions (Linter, Tests) pass. Green is good! ✅

**Review Expectations:**
- We aim to review PRs within a few days.
- Be open to feedback. Code review is a discussion, not a judgment.

---

## 📐 Coding Standards

Quality is paramount. Please adhere to the following rules:

- **Language Style**: Follow the project's linter configuration (e.g., ESLint for JS, PEP8 for Python, Clang-Format for C++).
- **Clean Code**:
    - Variable and function names should be descriptive (in English).
    - Functions should be small and do one thing well.
- **Comments**: Comment *why* you did something, not *what* the code does (the code should explain itself).

---

## 🤝 Community & Conduct

Please note that this project is released with a [Code of Conduct](CODE_OF_CONDUCT.md). By participating in this project you agree to abide by its terms.

**Respect and constructive criticism are the pillars of our collaboration.**

---

Thank you for helping us build better software! 🚀
