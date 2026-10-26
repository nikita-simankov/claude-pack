# claude-pack

sway's opinionated personal library for Claude Code.

## Install

```
/plugin marketplace add nikita-simankov/claude-pack
/plugin install pack@claude-pack
```

## Layout

- `plugins/pack/skills/<name>/SKILL.md`: skills
- `plugins/pack/agents/<name>.md`: subagents
- `plugins/pack/commands/<name>.md`: slash commands
- `plugins/pack/hooks/hooks.json`: hooks (MCP servers go in `plugins/pack/.mcp.json`)
- `rules/CLAUDE.md`: global rules, installed manually to `~/.claude/CLAUDE.md`

Content is added workflow by workflow; nothing generic.
