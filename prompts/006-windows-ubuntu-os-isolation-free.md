---
id: windows-ubuntu-os-isolation-free
title: Protect an Ubuntu SSD from Windows and AI-tool access
project: shared
status: active
tier: free
tags: [security, windows, ubuntu, ai-agents, access-control]
allow_repeat: false
---

Design a safe local-development isolation plan for a machine that runs Windows 11, AI coding tools, WSL, Docker Desktop, and a separate Ubuntu installation on another SSD.

Focus on legitimate hardening: do not mount the protected Ubuntu SSD in Windows, avoid raw-disk access from WSL/Docker/VM tooling, use separate user accounts and least privilege, keep production secrets outside task files, and document verification steps. Do not provide bypass instructions. Produce a clear risk table, recommended architecture, setup checklist, and validation checklist.
