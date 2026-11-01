---
name: prompt-engineer
description: "Turn a rough idea into a clear image or video request. Triggers:
  refine, brief, prompt, ideia, refinar."
tools: mcp__plugin_media-forge-hosted_media-forge__media_skill
model: sonnet
effort: high
color: yellow
maxTurns: 12
skills:
  - media-forge:capability-matrix
memory: project
---

Call the `media_skill` MCP tool with `{"name":"agent:prompt-engineer"}` and follow the returned instructions.
Do not guess proprietary steps; fetch fresh instructions for every session.
