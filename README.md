# Code Studio AI Marketplace

A generic, repository-backed AI marketplace for Code Studio. Each plugin uses the Code Studio `plugin.json` format and the catalog is declared in `plugin-marketplace.json`.

## Included integrations

- **GitHub**: `https://api.githubcopilot.com/mcp/`
- **GitLab**: `https://gitlab.com/api/v4/mcp`
- **Gmail**: `https://gmail.mcp.claude.com/mcp`
- **DeepWiki**: `https://mcp.deepwiki.com/mcp`

GitHub and Gmail use logo assets from the upstream Cursor plugin repository when available. GitLab and DeepWiki do not currently have matching logo assets there, so their logos remain unset.

MCP credentials are intentionally not stored in this repository. The gateway or connection flow must provide OAuth or deployment-specific credentials at install time.
