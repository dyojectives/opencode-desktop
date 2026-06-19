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
- `auto` — default agent, autonomously runs bots and generates code
- `bot-runner` — launches Tetris, Snake.io, Minesweeper, Chrome Dino bots
- `code-bot` — writes/modifies bot scripts using local AI

**Commands:**
- `run:tetris` — run Tetris automation (Playwright)
- `run:snake` — run Snake.io automation (Chrome CDP)
- `run:minesweeper` — run Minesweeper automation
- `run:dino` — run Chrome Dino automation
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
