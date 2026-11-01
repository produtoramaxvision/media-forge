---
name: kling-prompting
description: "When the user is planning a Kling video. Triggers: kling,
  multi-shot, omni, prompt."
allowed-tools: mcp__plugin_media-forge-hosted_media-forge__media_skill
---

Call the `media_skill` MCP tool with `{"name":"kling-prompting"}` and follow the returned instructions.
Do not guess proprietary steps; fetch fresh instructions for every session.
