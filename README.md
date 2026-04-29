# codex-computer-use

Agent Skill for using Codex.app Computer Use through `codex exec`.

This skill lets Claude Code or another shell-capable coding agent delegate macOS GUI work to Codex.app through `codex exec`.

## Install

```sh
npx skills add schroneko/codex-computer-use -g -a claude-code -a codex -y
```

## Contents

- `SKILL.md`: skill instructions
- `agents/openai.yaml`: Codex skill metadata

## Requirements

- Codex.app installed
- Codex.app bundled `codex` CLI available
- Computer Use plugin enabled in Codex.app
- Target app approved for Computer Use
