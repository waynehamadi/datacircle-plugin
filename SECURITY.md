# Security

## Reporting a vulnerability

Email wayne@datacircle.dev with what you found and how to reproduce it. Please don't open a public issue for a vulnerability.

## What this plugin does

This repository holds configuration only: manifests for Claude Code, Cursor and Gemini CLI, a skill (`skills/datacircle/SKILL.md`) and a logo. It runs no code on your machine and installs no package. It declares one remote MCP server, `https://api.datacircle.dev/mcp`, run by Datacircle over HTTPS. The server is open to anyone, with no key, and reads only the sheet. No credential is stored in this repository.

The server's own security is covered by the privacy policy: https://datacircle.dev/privacy.
