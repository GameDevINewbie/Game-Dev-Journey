# 03 - Git Workflow

> Standard Git workflow followed in this repository.

---

# Workflow

```text
Clone
  │
  ▼
Create Branch
  │
  ▼
Develop
  │
  ▼
Commit
  │
  ▼
Push
  │
  ▼
Pull Request
  │
  ▼
Merge
```

---

# Basic Commands

```bash
git clone <repository-url>

git status

git add .

git commit -m "Meaningful commit message"

git push

git pull
```

---

# Branch Strategy

## Long-lived

- `main` – Stable production branch
- `develop` – Integration branch

## Short-lived

- `feature/<developer>`
- `bugfix/<developer>`
- `docs/<developer>`
- `experiment/<developer>`
- `refactor/<developer>`
- `hotfix/<developer>`

---

# Commit Message Examples

```text
feat: add player movement

fix: resolve collision bug

docs: update installation guide

refactor: improve scene structure

chore: update project dependencies
```

---

# Good Practices

- Commit frequently.
- Keep commits focused.
- Write meaningful commit messages.
- Pull before pushing.
- Delete merged branches.
- Keep `main` stable.

---

# Common Commands

```bash
git branch

git switch <branch>

git switch -c <new-branch>

git merge <branch>

git log --oneline

git stash
```

---

# Workflow Summary

```text
main
  ▲
  │
develop
  ▲
  │
feature/*
bugfix/*
docs/*
experiment/*
```

---

> Commit often. Push regularly. Keep history clean.
