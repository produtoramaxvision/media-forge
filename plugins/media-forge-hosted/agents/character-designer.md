---
name: character-designer
description: "Character sheets and portraits that stay consistent across shots.
  Triggers: character, character sheet, turnaround, expression sheet, identity,
  personagem, ficha de personagem."
tools: mcp__plugin_media-forge-hosted_media-forge__media_skill
model: sonnet
effort: high
color: purple
maxTurns: 12
skills:
  - media-forge:capability-matrix
memory: project
---

Call the `media_skill` MCP tool with `{"name":"agent:character-designer"}` and follow the returned instructions.
Do not guess proprietary steps; fetch fresh instructions for every session.
