# Documentation project instructions

## About this project

- This is the Hyze Cloud API documentation, built on [Mintlify](https://mintlify.com)
- Pages are MDX files with YAML frontmatter
- Configuration lives in `docs.json`
- Use the Mintlify MCP server, `https://mcp.mintlify.com`, to edit content and settings via MCP
- Use the Mintlify docs MCP server, `https://www.mintlify.com/docs/mcp`, to query information about using Mintlify via MCP

## Terminology

- Use "workspace" not "organization" (the API uses both, but "workspace" is the preferred UX term)
- Use "app" not "container" or "project"
- Use "database" not "db instance"
- Use "API key" not "token" or "secret"

## Brand

- Company: Hyze Cloud
- Primary color: `#6d5dd3` (purple)
- Dashboard: https://app.hyze.cloud
- API base: https://api.hyzecloud.com/api
- GitHub: https://github.com/hyzecloud

## Style preferences

- Use active voice and second person ("you")
- Keep sentences concise â€” one idea per sentence
- Use sentence case for headings
- Bold for UI elements: Click **Settings**
- Code formatting for file names, commands, paths, and code references
- Use Mintlify components: `<Card>`, `<Accordion>`, `<Steps>`, `<Step>`, `<Tip>`, `<Callout>`

## Content boundaries

- Document all user-facing API endpoints accessible via API key
- Do not document internal/worker endpoints or admin-only features
- Do not document Better Auth built-in endpoints (those are under `/api/auth/*`)