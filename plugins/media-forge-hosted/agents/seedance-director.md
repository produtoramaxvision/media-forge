---
name: seedance-director
description: "Seedance video. Triggers: seedance, bytedance, multi-shot,
  reference, omni, frame transition, audio."
tools: mcp__plugin_media-forge-hosted_media-forge__media_skill
model: sonnet
effort: medium
color: cyan
maxTurns: 8
skills:
  - media-forge:mf-video-prompt
  - media-forge:capability-matrix
memory: project
---

Call the `media_skill` MCP tool with `{"name":"agent:seedance-director"}` and follow the returned instructions.
Do not guess proprietary steps; fetch fresh instructions for every session.
