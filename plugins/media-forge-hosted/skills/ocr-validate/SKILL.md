---
name: ocr-validate
description: "Check text that appears in a generated image. Triggers: ocr, text
  in image, texto na imagem."
allowed-tools: mcp__plugin_media-forge-hosted_media-forge__media_skill
user-invocable: false
---

Call the `media_skill` MCP tool with `{"name":"ocr-validate"}` and follow the returned instructions.
Do not guess proprietary steps; fetch fresh instructions for every session.
