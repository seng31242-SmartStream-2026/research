# Contributing to `research`

**Project:** SmartStream – Integrated Business Management System
**Group:** Group 07 – NextGen Developers

---

## Branching Strategy

| Branch | Purpose |
|--------|---------|
| `main` | Protected. Merge via Pull Request only, minimum 1 approval. |
| `draft/<document>` | Working branch for a research artefact in progress. e.g. `draft/competitive-analysis` |
| `fix/<issue-number>` | Corrective changes after review feedback. e.g. `fix/18` |

---

## Commit Message Format

```
<type>(scope): short summary

Closes #<issue-number>
```

| Type | When to use |
|------|-------------|
| `docs` | Adding or updating research notes, interviews, or analysis |
| `feat` | Adding a new research artefact or finding |
| `fix` | Correcting an error or review feedback |
| `chore` | README, .gitignore housekeeping |

**Good:** `docs(interviews): add summary for client interview #2`
**Bad:** `updated notes`, `research`, `final`

---

## Pull Request Rules

- Minimum **1 approving review** before merging into `main`
- PR must reference the related issue: `Closes #<number>`
- No unresolved comments before merging
- Author must **not** merge their own PR

---

## Key Rules

- All fact-finding artefacts must be committed within **24 hours** of the session
- Survey responses must be **anonymised** before committing
- Never commit directly to `main`
