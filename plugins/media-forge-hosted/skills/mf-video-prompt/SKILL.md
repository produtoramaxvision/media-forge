---
name: media-forge:mf-video-prompt
description: "When the user asks to write or improve a video prompt. Triggers:
  video prompt, write prompt, translate prompt, prompt de vídeo, T2V, I2V, Veo,
  Kling, Higgsfield, Seedance."
allowed-tools: mcp__plugin_media-forge-hosted_media-forge__media_skill
---

Call the `media_skill` MCP tool with `{"name":"mf-video-prompt"}` and follow the returned instructions.
Do not guess proprietary steps; fetch fresh instructions for every session.
