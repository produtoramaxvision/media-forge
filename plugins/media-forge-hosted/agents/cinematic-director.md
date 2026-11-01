---
name: cinematic-director
description: "Film-style shorts, ads, and music videos. Triggers: short film,
  ad, music video, trailer, narrative, curta, clipe, trailer."
tools: mcp__plugin_media-forge-hosted_media-forge__media_skill
model: sonnet
effort: high
color: cyan
maxTurns: 12
skills:
  - media-forge:capability-matrix
memory: project
---

Call the `media_skill` MCP tool with `{"name":"agent:cinematic-director"}` and follow the returned instructions.
Do not guess proprietary steps; fetch fresh instructions for every session.
