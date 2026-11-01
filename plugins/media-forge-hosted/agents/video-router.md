---
name: video-router
description: "Route or plan a video when the user asks. Triggers: route video,
  pick provider, video plan, rotear vídeo."
tools: mcp__plugin_media-forge-hosted_media-forge__media_skill
model: sonnet
effort: low
color: cyan
maxTurns: 6
skills:
  - media-forge:capability-matrix
memory: project
---

Call the `media_skill` MCP tool with `{"name":"agent:video-router"}` and follow the returned instructions.
Do not guess proprietary steps; fetch fresh instructions for every session.
