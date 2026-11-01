# media-forge hosted — install

1. Create an API key at https://api.media-forge.cloud (dashboard → API Keys).
2. Export it: `export MEDIA_FORGE_API_KEY="mfk_…"`
3. Add marketplace: `claude plugin marketplace add produtoramaxvision/media-forge`
4. Install: `claude plugin install media-forge-hosted@media-forge`
5. Run `/media-forge:setup` in Claude Code to verify the connection.
