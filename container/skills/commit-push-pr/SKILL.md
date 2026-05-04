---
name: commit-push-pr
description: Commit staged/unstaged changes, push to a branch, and open a GitHub PR — all in one shot. Use when ready to ship a change.
---

## Context

Before acting, gather:
- Current git status: run `git status`
- Current git diff (staged and unstaged): run `git diff HEAD`
- Current branch: run `git branch --show-current`

## Your task

Based on the above changes:

1. **Create a new branch** if currently on `main` or `master` — use a short descriptive name
2. **Stage all relevant changes** with `git add`
3. **Create a single commit** with an appropriate, descriptive message
4. **Push the branch** to origin
5. **Open a pull request** using `gh pr create` with a clear title and summary body

Do all of the above in a single response. Do not ask for confirmation — proceed directly.

## Allowed tools

`git checkout -b`, `git add`, `git status`, `git diff`, `git push`, `git commit`, `gh pr create`
