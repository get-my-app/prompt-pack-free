---
id: local-file-converter-free-spec
title: "Build Free Local File Converter"
project: local-file-converter
status: active
tier: free
tags: [architecture, planning, files, conversion]
allow_repeat: false
created: 2026-06-13
updated: 2026-06-13
---

Design and implement a local-only Free tier file conversion CLI for `doc`, `docx`, `jpg`, `jpeg`, and `pdf`. Support single-file conversions between office documents, images, and PDFs by orchestrating locally installed tools such as LibreOffice, Poppler, and ImageMagick. Do not upload files, do not require network access, and make every missing dependency visible through clear diagnostics.
