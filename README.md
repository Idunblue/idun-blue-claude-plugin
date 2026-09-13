# Idun Blue for Claude Code

Installs the Idun Blue operating manual as a skill and connects the live MCP
server (https://api.idun.blue/mcp). Generated from the server; do not edit by hand — run
`bun scripts/generate-agent-plugin.ts --write` in the idun-blue repo.

## Install

```
claude plugin marketplace add idunblue/idun-blue-claude-plugin
claude plugin install idun-blue@idun-blue
claude mcp login idun-blue
```

The last line opens the creator’s browser for Idun OAuth. Nothing about her
subscription is stored by Idun; the plugin holds no key.

Skill version: 4.12.0.
