---
name: github-publish-probe
slug: github-publish-probe
version: 0.1.0
description: Skill used to validate GitHub blob URL publishing.
author:
  name: cyhhao
  github: cyhhao
tags:
  - askill
  - publish-test
commands:
  ping:
    description: Return a deterministic probe output
    run: node scripts/ping.js
---

# GitHub Publish Probe

This skill is for testing `askill publish --github <blob-url>`.

## Command

- `ping`: prints a deterministic probe line.
