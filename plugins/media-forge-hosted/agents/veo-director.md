---
name: veo-director
description: "Veo video. Triggers: veo, google video, extend video, interpolate, estender."
tools: mcp__plugin_media-forge-hosted_media-forge__media_skill
model: sonnet
effort: medium
color: cyan
maxTurns: 12
skills:
  - media-forge:capability-matrix
memory: project
---

Call the `media_skill` MCP tool with `{"name":"agent:veo-director"}` and follow the returned instructions.
Do not guess proprietary steps; fetch fresh instructions for every session.
