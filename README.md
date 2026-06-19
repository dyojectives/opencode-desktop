# OpenCode Desktop

OpenCode is an **open source AI coding agent** that helps you write code in your terminal, desktop, or IDE. It supports **75+ LLM providers** (Claude, GPT, Gemini, local models) and is privacy-first — your code never gets stored.

[![GitHub stars](https://img.shields.io/github/stars/anomalyco/opencode?style=flat-square)](https://github.com/anomalyco/opencode)
[![License](https://img.shields.io/badge/license-MIT-blue?style=flat-square)](LICENSE)

## Download

### Linux (AppImage)

| Version | Download |
|---|---|
| v1.0.0 | [opencode-desktop-linux-x86_64.AppImage](https://github.com/dyojectives/opencode-desktop/releases/download/v1.0.0/opencode-desktop-linux-x86_64.AppImage) (150MB) |

```bash
# Download
wget https://github.com/dyojectives/opencode-desktop/releases/download/v1.0.0/opencode-desktop-linux-x86_64.AppImage

# Make executable
chmod +x opencode-desktop-linux-x86_64.AppImage

# Run
./opencode-desktop-linux-x86_64.AppImage
```


## Features

- Interactive TUI built with Bubble Tea
- 75+ AI providers (Anthropic, OpenAI, Google Gemini, local Ollama, etc.)
- Session management with SQLite storage
- File editing, code generation, shell access
- LSP integration for code intelligence
- Plugin system with TypeScript support
- GitHub integration (`/opencode` in issues/PRs)

## Skill: bot-automation

A custom skill for running and creating game bots autonomously.

**Agents:**
- Plan / Build modes — Toggle with Tab. Plan mode explores without writing code; Build mode makes changes.
- MCP servers — Connect any Model Context Protocol (https://opencode.ai/docs/mcp-servers/) server for additional tools (databases, APIs, filesystem, etc.)
- Agents & subagents — Spawn parallel agents to work on different tasks simultaneously
- Skills — Load specialized instructions/workflows for specific tasks (like the one you loaded just now)
- Custom tools — Define your own tools via plugins or MCP/ACP
- LSP integration — Automatically loads language servers to give the LLM project-aware context
- Multi-session — Multiple independent agents on the same project
- Themes, keybinds, commands — Fully customizable terminal UI
- /init, /undo, /redo, /share — Built-in commands for project setup, revert, and sharing sessions
- Any model provider — 75+ providers, including local models, through Zen or direct API keys

**Commands:**
- `run:minesweeper` — run Minesweeper automation
- `code:generate` — create bot code via Qwen2.5-Coder-1.5B-Instruct

**Model:** `ai/models/Qwen2.5-Coder-1.5B-Instruct/` — local code generation

## Quick Start

```bash
# Run in your project directory
./opencode-desktop-linux-x86_64.AppImage

# Initialize for your project (inside the TUI)
/init

# Ask questions or make changes — just type naturally
```

## License

MIT
