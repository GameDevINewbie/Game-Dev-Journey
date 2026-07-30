# Branch Naming Convention

## Format

```
<type>/<developer>
```

## Branch Types

| Branch | Purpose |
|--------|---------|
| `main` | Stable production branch |
| `develop` | Integration branch |
| `feature/<developer>` | New features |
| `bugfix/<developer>` | Bug fixes |
| `docs/<developer>` | Documentation |
| `experiment/<developer>` | Testing new ideas |
| `refactor/<developer>` | Code improvements |
| `hotfix/<developer>` | Urgent production fixes |

## Examples

```
feature/dhruv
feature/rahul

bugfix/amit

docs/dhruv

experiment/rahul

refactor/dhruv

hotfix/amit
```

## Rules

- Use lowercase.
- Use `/` to separate the branch type and developer.
- Use one branch per task.
- Merge into `develop` using a Pull Request.
- Delete the branch after merging.

## Workflow

```
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
refactor/*
hotfix/*
```
