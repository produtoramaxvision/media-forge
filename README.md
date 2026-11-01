# Media Forge for Claude Code

Claude Code marketplace for the hosted Media Forge plugin. Media Forge picks the model for each job, reviews every take and charges only what it delivers. 1 credit = US$ 1, prepaid.

This repository holds only the thin client: it connects Claude Code to the hosted MCP server at `https://api.media-forge.cloud/mcp`. No generation code or production know-how runs on your machine.

## Install

```bash
export MEDIA_FORGE_API_KEY="mfk_…"
claude plugin marketplace add produtoramaxvision/media-forge
claude plugin install media-forge-hosted@media-forge
```

Then run `/media-forge:setup` in Claude Code. Details: [plugins/media-forge-hosted/ONBOARDING.md](plugins/media-forge-hosted/ONBOARDING.md).

Site, prices and credits: https://media-forge.cloud

© 2026 Produtora MaxVision. All rights reserved. See [LICENSE](LICENSE).
