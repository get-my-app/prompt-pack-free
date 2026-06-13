---
id: bashrc-manager-free-spec
title: "Build Free BashRC Manager"
project: bashrc-manager
status: active
tier: free
tags: [architecture, planning, shell]
allow_repeat: false
created: 2026-06-13
updated: 2026-06-13
---

Design and implement the public Free tier of an Ubuntu-first `.bashrc.d` manager. Include safe backup of `.bashrc`, migration of existing content into `.bashrc.d/main.sh`, creation of a loader `.bashrc`, module add/list/disable flows, and `bash -n` validation. Keep Windows WSL and Android Termux notes as public documentation only.
