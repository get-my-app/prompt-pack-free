---
id: agent-commit-push-pr-free
title: Commit, push, and PR workflow for AI agents
project: shared
status: active
tier: free
tags: [git, workflow, agents, pull-request]
allow_repeat: false
---

Create or configure an AI coding-agent workflow where every completed logical change is committed separately, pushed to the current feature branch, and followed by a pull request into the base branch.

Keep it safe for public/open-core work: do not commit secrets, `.env` files, private keys, generated binaries, paid-tier implementation details, or unrelated user changes. Require the agent to run `git status`, inspect the diff, run the project checks, push only a non-protected feature branch, and create or update a PR with a concise summary, verification notes, and risk notes. If GitHub CLI or permissions are missing, the agent must report the exact blocker and provide the PR creation command or URL instead of pretending the PR was created.
