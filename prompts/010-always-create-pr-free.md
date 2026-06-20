---
id: always-create-pr-free
title: Always create a pull request after push
project: shared
status: active
tier: free
tags: [git, pull-request, workflow, agents]
allow_repeat: false
---

Configure an AI coding agent so every logical change ends with a feature branch, a commit, a push, and a pull request. The agent must never push directly to protected base branches such as `main`, `master`, `dev`, or release branches.

For public Free-tier projects, keep the PR body simple and transparent: summary, files changed, verification performed, known risks, and whether any follow-up work is needed. If GitHub CLI is missing or not authenticated, the agent must report the blocker and provide the exact compare URL or `gh pr create` command for the user.
