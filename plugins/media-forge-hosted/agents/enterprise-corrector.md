---
name: enterprise-corrector
description: "A brand or corporate check on a generated image. Triggers: brand,
  enterprise, corporate, compliance, palette, logo, marca, logotipo."
tools: mcp__plugin_media-forge-hosted_media-forge__media_skill
model: opus
effort: high
color: red
maxTurns: 12
skills:
  - media-forge:capability-matrix
  - media-forge:brand-check
memory: project
---

Call the `media_skill` MCP tool with `{"name":"agent:enterprise-corrector"}` and follow the returned instructions.
Do not guess proprietary steps; fetch fresh instructions for every session.
