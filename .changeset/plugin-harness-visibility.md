---
'harness-score': patch
---

Recognize Claude Code and Cursor plugin default layouts when scanning a plugin repository root (`.claude-plugin/plugin.json` or `.cursor-plugin/plugin.json`), and include user-scoped Claude Code plugin installs from `~/.claude/plugins/installed_plugins.json` in the effective score when `--scope user` is enabled.

Thanks to [@almerindo](https://github.com/almerindo) for reporting this.
