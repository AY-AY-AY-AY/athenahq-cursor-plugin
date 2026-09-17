# AthenaHQ Cursor plugin

Track how AI assistants mention, cite, and rank your brand and competitors with AthenaHQ.

This is the public Cursor / Grok Bot Marketplace package for AthenaHQ: a skill plus the remote AthenaHQ MCP server.

## Install

Once listed, install from the [Cursor Marketplace](https://cursor.com/marketplace). Until then you can load this repo as a local or team plugin.

## MCP server

```text
https://api.athenahq.ai/api/mcp
```

Cursor Marketplace installations use the server's OAuth sign-in flow. The connection provides analytics tools and write tools. Writes are gated by the signed-in user's AthenaHQ role, use the same validation and audit logging as the dashboard, and include permanent delete operations. Review the [write tools and permissions](https://docs.athenahq.ai/api-reference/mcp#write-tools) before using them.

MCP clients that need an API key can send an `x-api-key` header using a key from [AthenaHQ API settings](https://app.athenahq.ai/settings/api). API keys receive write access within their configured scope. Do not commit API keys.

Docs: [AthenaHQ MCP](https://docs.athenahq.ai/api-reference/mcp)

## License

MIT
