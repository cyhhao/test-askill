---
name: local-publish-probe
slug: local-publish-probe
version: 0.1.0
description: Skill used to validate local path publishing.
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

# Local Publish Probe

This skill is for testing `askill publish <local-path>`.

## Command

- `ping`: prints a deterministic probe line.
