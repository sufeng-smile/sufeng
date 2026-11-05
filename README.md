# sufeng

This repository is maintained with the GitHub CLI (\gh\) and git on Windows.

## Environment

| Tool | Version | Notes |
|---|---|---|
| git | 2.56.0.windows.4 | credentials via \gh auth git-credential\ |
| gh  | 2.103.3 | token scopes: repo, read:org, workflow |

## Purpose

Smoke-test target for verifying the \gh\ + git push chain (commit -> push -> PR).
## Verification checklist

- [x] git push via gh credential helper
- [x] gh pr create
- [x] gh issue create

