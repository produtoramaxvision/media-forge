---
name: capability-matrix
description: "When the user asks what media-forge can generate. Triggers:
  capabilities, models, o que dá para gerar."
allowed-tools: mcp__plugin_media-forge-hosted_media-forge__media_skill
user-invocable: true
---

Call the `media_skill` MCP tool with `{"name":"capability-matrix"}` and follow the returned instructions.
Do not guess proprietary steps; fetch fresh instructions for every session.
