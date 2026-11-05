# Datacircle for Claude, Cursor and Gemini CLI

Find the best GTM APIs. We benchmark all the GTM APIs and we put the results on our website: https://datacircle.dev

Our MCP server is open to anyone, with no key. This plugin adds it to Claude, Cursor or Gemini CLI: `https://api.datacircle.dev/mcp`, Streamable HTTP. It answers from the sheet. `list_apis` lists the GTM APIs on it, and `search_plans` finds their plans by API, provider or price. Each plan comes with its score, and the best come first, as on the sheet.

## Setup

In Claude Code:

```
/plugin marketplace add waynehamadi/datacircle-plugin
/plugin install datacircle@datacircle
```

In Cursor, add the plugin from this repository, or put this in `mcp.json`:

```json
{ "mcpServers": { "datacircle": { "url": "https://api.datacircle.dev/mcp" } } }
```

In Gemini CLI: `gemini extensions install https://github.com/waynehamadi/datacircle-plugin`

Docs: https://datacircle.dev/docs/mcp. Privacy: https://datacircle.dev/privacy. Support: https://datacircle.dev/support. MIT license.
