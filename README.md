# 📦 Global GitHub Templates

This repository contains global configuration files and templates that apply to all repositories under the **@Matyslgr** GitHub account.

It is used to standardize and streamline workflows across all personal and organizational projects.

---

## 📁 Contents

### 1. 🔖 Issue Templates (`.github/ISSUE_TEMPLATE/`)

Reusable issue templates to encourage structured contributions.

| Template              | Purpose                                                 |
|-----------------------|---------------------------------------------------------|
| `bug_report.yaml`     | Report a bug with steps to reproduce and context        |
| `feature_request.yaml`| Propose a new feature or improvement                    |
| `refactor_request.yaml` | Suggest internal code improvements / restructuring     |
| `hotfix_request.yaml` | Submit critical fixes for urgent production issues      |

➡️ All templates include support for GitHub Project metadata when applicable.

### 2. 🚀 Pull Request Templates (`.github/PULL_REQUEST_TEMPLATE/`)

Modular pull request templates tailored for different types of changes:

| Template         | Purpose                          |
|------------------|----------------------------------|
| `bug.md`         | Fixing a bug                     |
| `feature.md`     | Implementing a new feature       |
| `refactor.md`    | Structural or non-functional changes |
| `hotfix.md`      | Urgent fix, often for production issues |

> To use these, PR creators simply select the appropriate template when opening a pull request.

### 3. 🛠️ Repository Configuration (`config.yml`)

Central configuration for issue template UI (menu)
Located at: `.github/ISSUE_TEMPLATE/config.yml`

---

## 📌 Usage

These templates are automatically applied to all repositories that **do not override them with their own local `.github/` folder**.

You can override any template in a specific repository by creating a local `.github/ISSUE_TEMPLATE/` or `.github/PULL_REQUEST_TEMPLATE/`.

---

## 🤖 Coming Soon (optional)

Planned additions:

- ✅ GitHub Actions for automatic labeling and project linking
- 📄 Contributor guidelines and security policy templates
- 🚨 Issue auto-triage based on labels and title analysis

---

## 🧪 Maintainer Notes

This repository is maintained manually. To update or test changes:

1. Make the changes here
2. Push to `main`
3. Verify template propagation on a fresh test repo

---

## 📎 References

- [GitHub: Managing a .github repository](https://docs.github.com/en/communities/setting-up-your-project-for-healthy-contributions/creating-a-default-community-health-file)
- [GitHub Issue Forms](https://docs.github.com/en/issues/using-issues/configuring-issue-templates-for-your-repository)
- [GitHub PR Templates](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/about-pull-request-templates)

---

Maintained by [@MatysLgr](https://github.com/MatysLgr)
