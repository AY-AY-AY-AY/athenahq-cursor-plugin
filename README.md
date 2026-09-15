# AthenaHQ Cursor plugin

Track how AI assistants mention, cite, and rank your brand and competitors with AthenaHQ.

This is the public Cursor / Grok Bot Marketplace package for AthenaHQ. It mirrors the ChatGPT Apps skill: a skill plus the remote AthenaHQ MCP server.

## Install

Once listed, install from the [Cursor Marketplace](https://cursor.com/marketplace). Until then you can load this repo as a local or team plugin.

## MCP server

```text
https://api.athenahq.ai/api/mcp
```

Cursor Marketplace installs use the server's OAuth sign-in flow. MCP clients that need an API key can send an `x-api-key` header using a key from [AthenaHQ API settings](https://app.athenahq.ai/settings/api). Do not commit API keys.

Docs: [AthenaHQ MCP](https://docs.athenahq.ai/api-reference/mcp)

## License

MIT
