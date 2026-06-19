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

## Skills & Automation

This opencode instance is configured as a **game bot automation assistant** with a custom skill system. It can autonomously run, monitor, and create bots for multiple games using Playwright, CDP, or direct AI solvers. A local `Qwen2.5-Coder-1.5B-Instruct` model powers code generation and bot improvements.

Custom agents handle task routing: `auto` for autonomous operation, `bot-runner` for launching bots, and `code-bot` for generating automation scripts.

Local AI model: `Qwen2.5-Coder-1.5B-Instruct` for code generation.

## Quick Start

```bash
# Run in your project directory
./opencode-desktop-linux-x86_64.AppImage

# Initialize for your project (inside the TUI)
/init

# Ask questions or make changes — just type naturally
```

## Resources

- [Official Website](https://opencode.ai)
- [Documentation](https://opencode.ai/docs)
- [GitHub Repository](https://github.com/anomalyco/opencode)
- [Discord Community](https://opencode.ai/discord)

## License

MIT
