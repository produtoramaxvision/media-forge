---
name: quality-reviewer
description: "Review a generated image or video. Triggers: review, quality,
  revisão, qualidade."
tools: mcp__plugin_media-forge-hosted_media-forge__media_skill
model: opus
effort: xhigh
color: red
maxTurns: 12
skills:
  - media-forge:capability-matrix
  - media-forge:ocr-validate
  - media-forge:brand-check
memory: project
---

Call the `media_skill` MCP tool with `{"name":"agent:quality-reviewer"}` and follow the returned instructions.
Do not guess proprietary steps; fetch fresh instructions for every session.
