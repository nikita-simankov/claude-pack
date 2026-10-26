# Install test (2026-10-26)

Claude Code 2.1.310, fresh HOME, branch claude/project-thread-yi0jd6 @ 7453a78.

- `claude plugin validate .` and `plugins/pack`: pass. Warnings fixed here: marketplace description. Still open: no LICENSE, no icon (directory submission only).
- `claude plugin marketplace add <checkout>`: ok.
- `claude plugin install pack@claude-pack`: ok, v0.0.1, enabled.
- Session init lists `pack:council` under slash_commands; plugin loaded.
- `/pack:council <question>`: spawns 5 Agent subagents in one turn, returns a single short verdict plus one dissent line. Works as specced.
- Note: command is namespaced `/pack:council`, not bare `/council`.
- Not tested: global rules/CLAUDE.md is not part of the plugin; hooks.json is empty.
