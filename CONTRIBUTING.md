# Internal Contribution Guidelines

Welcome to the E3 Electric GitHub organisation. This guide outlines how all internal developers should contribute to codebases across squads.

---

## 🏗 Repository Naming Convention

All repositories must follow this standard format:

`<squad>-<domain>-<type>[-optional-details]`

Examples:
- `ai-pothole-detection-model`
- `web-admin-dashboard-react`
- `utils-data-uploader-script`

See full details in [README.md](./profile/README.md#teams--repositories).

---

## 🧠 Engineering Principles

- Prioritize **readable and maintainable** code
- Follow the **single-responsibility principle**
- Prefer **modular**, **reusable**, and **testable** functions
- Avoid code duplication, overengineering, or magic

---

## 📄 Repo Requirements

Each repo must contain:

- `README.md`: Overview, setup, usage, team contact
- `LICENSE` (internal use license or NDA notice)
- `.env.example`: Sample environment config
- `Makefile` or `run.sh` for common workflows (if needed)
- Clear folder structure (`src/`, `tests/`, `docs/`, etc.)

---

## 🔧 Branching Strategy

- `main` should always be deployable
- Create feature branches:  
`feature/<task-name>`
`bugfix/<issue-description>`
`refactor/<area>`
- Avoid pushing directly to `main` or `master` (default branch)

---

## ✅ Commit Standards

Follow [Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/) Standards

Examples:
- `feat(auth): add JWT refresh logic`
- `fix(api): handle null response case`
- `chore(deps): upgrade numpy to 1.25`

---

## 🛡 Code Review Process

- Every PR must be reviewed by at least 1 other developer (if required)
- Include a meaningful title and description
- Use **Draft PRs** for WIP or collaborative features
- Run all tests before requesting a review

---

## 🔐 Secrets & Access

- Never commit secrets, tokens, or passwords — use secret managers or `.env`
- Use `.gitignore` to exclude sensitive files or local configs
- Request GitHub access via the IT team or the Squad Lead

---

## 📌 Notes

- Keep your local branch synced with `main` regularly
- Archive old repos if unused for >6 months
- Raise internal PRs early for visibility

---

## 🧭 Questions?

Reach out on the internal MS Teams channel for your respective team or ping your squad lead on teams.

Happy building! 🚀
