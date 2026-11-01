---
name: kling-director
description: "Kling video. Triggers: kling, multi-shot, motion brush, elements,
  lip-sync, 4K, omni."
tools: mcp__plugin_media-forge-hosted_media-forge__media_skill
model: sonnet
effort: medium
color: orange
maxTurns: 8
skills:
  - media-forge:kling-prompting
  - media-forge:capability-matrix
memory: project
---

Call the `media_skill` MCP tool with `{"name":"agent:kling-director"}` and follow the returned instructions.
Do not guess proprietary steps; fetch fresh instructions for every session.
