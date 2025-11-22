# 🛠️ Global GitHub Configuration

This repository serves as the central hub for **Community Health Files** and **Issue/PR Templates** for all projects under the **@Matyslgr** account.

It utilizes GitHub's **default community health file** mechanism. Any repository created under this account automatically inherits these standards unless explicitly overridden, ensuring consistency, security, and professionalism across the entire portfolio.

---

## 🛡️ Governance & Community

These files define the rules of engagement, security protocols, and onboarding processes for contributors.

| File | Description |
| :--- | :--- |
| [**CONTRIBUTING.md**](CONTRIBUTING.md) | The technical onboarding guide. Explains the branching strategy, commit conventions (Conventional Commits), and how to run tests. |
| [**CODE_OF_CONDUCT.md**](CODE_OF_CONDUCT.md) | Enforces a safe environment. Based on the **Contributor Covenant v3.0**. |
| [**SECURITY.md**](SECURITY.md) | Defines the Responsible Disclosure policy and how to report vulnerabilities privately. |
| [**SUPPORT.md**](SUPPORT.md) | Guiding users to the right support channels (Discussions, Email) to keep Issues clean. |

---

## 📝 Issue Tracking (Forms)

We use **YAML-based GitHub Issue Forms** to enforce structured data entry. This ensures every issue contains the necessary context (reproduction steps, environment, etc.) before submission.

| Template | Type | Purpose |
| :--- | :--- | :--- |
| [**Bug Report**](.github/ISSUE_TEMPLATE/bug_report.yml) | `bug_report.yml` | Standardized form for reporting errors, requiring logs and environment details. |
| [**Feature Request**](.github/ISSUE_TEMPLATE/feature_request.yml) | `feature_request.yml` | Focuses on the "Problem Statement" vs "Proposed Solution" separation. |
| [**Refactor Request**](.github/ISSUE_TEMPLATE/refactor_request.yml) | `refactor_request.yml` | For proposing code cleanups. Requires ROI justification and risk analysis. |
| [**Epic**](.github/ISSUE_TEMPLATE/epic.yml) | `epic.yml` | For tracking high-level initiatives and managing sub-tasks via Task Lists. |
| [**Question**](.github/ISSUE_TEMPLATE/question.yml) | `question.yml` | Simple form for clarifications and Q&A. |

---

## 🚀 Code Review & Merging

We use a unified, comprehensive template for all Pull Requests to ensure quality control before merging.

### [Pull Request Template](.github/PULL_REQUEST_TEMPLATE.md)
Located at `.github/PULL_REQUEST_TEMPLATE.md`, it enforces:
* **Context:** Linking to related issues (Fixes #...).
* **Type of Change:** Visual classification (Bug, Feature, Refactor...).
* **Testing Proof:** Explicit instructions on how the reviewer can verify the changes (Manual or Automated).
* **Self-Review Checklist:** Ensures linting, commenting, and no regressions.

---

## 📚 Developer Resources

This repository also contains templates intended for **manual use** in specific projects (not inherited automatically).

| File | Purpose | Location |
| :--- | :--- | :--- |
| **CITATION.cff** | Template for academic citations. Copy to project root if needed. | [`templates/CITATION.cff`](templates/CITATION.cff) |

---

## ⚡ How It Works

GitHub checks for community health files in the following order:
1.  In the specific repository's `.github/` directory.
2.  **In this repository** (the fallback).

This allows specific projects to override these defaults if necessary, while maintaining a strong baseline for all others.

---

_Maintained by [@MatysLgr](https://github.com/MatysLgr)_