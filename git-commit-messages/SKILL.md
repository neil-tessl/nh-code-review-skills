---
name: git-commit-messages
description: Write clear, conventional commit messages that explain the why behind changes.
---

# Git Commit Messages

## Format

Follow Conventional Commits:

```
<type>(<scope>): <description>

[optional body]
```

### Types

- `feat` — new feature
- `fix` — bug fix
- `refactor` — restructuring without behavior change
- `chore` — maintenance, deps, CI
- `docs` — documentation only
- `test` — adding or fixing tests

## Guidelines

1. **Subject line** — imperative mood, under 72 characters, no period
2. **Body** — explain *why*, not *what* (the diff shows what)
3. **Scope** — use the module or area affected (e.g. `auth`, `api`, `db`)
4. **Breaking changes** — add `BREAKING CHANGE:` footer

## Examples

### Good

```
feat(notifications): add email templates for eval run results

Users need visibility into eval outcomes without checking the dashboard.
Three templates cover success, partial failure, and pipeline failure.
```

### Bad

```
updated stuff
```
