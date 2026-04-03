# OpenClaude

> **The open-source coding agent that puts you in control.**

OpenClaude is an open-source coding-agent CLI that works with **200+ model providers** including OpenAI, Gemini, GitHub Models, Codex, Ollama, and any OpenAI-compatible API.

[![GitHub stars](https://img.shields.io/github/stars/Gitlawb/openclaude?style=social)](https://github.com/Gitlawb/openclaude/stargazers)
[![npm](https://img.shields.io/npm/v/@gitlawb/openclaude)](https://www.npmjs.com/package/@gitlawb/openclaude)
[![License](https://img.shields.io/github/license/Gitlawb/openclaude)](LICENSE)

---

## Why OpenClaude

OpenClaude gives you **freedom of choice** in the AI coding agent landscape:

| Feature | OpenClaude | Claude Code | Cursor |
|---------|------------|-------------|--------|
| Open-source | ✅ | ❌ | ❌ |
| 200+ model providers | ✅ | ❌ | ❌ |
| Local Ollama support | ✅ | ❌ | ❌ |
| NPM install | ✅ | ❌ | ❌ |
| GitHub Models built-in | ✅ | ❌ | ❌ |
| MCP support | ✅ | ✅ | ✅ |
| Slash commands | ✅ | ✅ | ✅ |

### Core Philosophy

- **Provider Agnostic** — Switch between OpenAI, Gemini, GitHub Models, Ollama, and any OpenAI-compatible API with a single command
- **Terminal-First** — Stay in your workflow, no GUI required
- **Developer Freedom** — Open-source, no vendor lock-in
- **Production Ready** — Battle-tested by thousands of developers

---

## Use Cases

### 1. Multi-Cloud Development
Use OpenAI for production, Gemini for experimentation, and Ollama for local development — all with the same interface.

### 2. Cost Optimization
Route requests based on task complexity. Use cheaper models for simple refactoring, premium models for complex architecture decisions.

### 3. Local-First Development
Run fully offline with Ollama. Perfect for:
- Air-gapped environments
- Privacy-sensitive projects
- Rapid prototyping without API costs

### 4. GitHub Models Integration
Get started in seconds with GitHub's free coding agent models — no API key needed for GitHub users.

---

## Quick Start

### Install

```bash
npm install -g @gitlawb/openclaude
```

### Configure a Provider

```bash
openclaude
# Inside: /provider
```

Choose from:
- **OpenAI** — GPT-4o, o3, o4-mini
- **Gemini** — Gemini 2.5 Pro, Flash
- **GitHub Models** — Free coding agents (GitHub login required)
- **Ollama** — Local models (Llama, Qwen, DeepSeek)
- **Custom** — Any OpenAI-compatible API

### Quick OpenAI Setup

```bash
export OPENAI_API_KEY=sk-your-key
openclaude
```

---

## Architecture

```
openclaude
├── /provider     # Manage model providers
├── /onboard      # Interactive setup
├── bash          # Execute shell commands
├── File tools    # Read, write, edit files
├── grep/glob     # Search codebase
├── agents        # Multi-agent workflows
├── tasks         # Task delegation
├── MCP           # Model Context Protocol tools
└── Web tools     # Browse and search
```

---

## Community & Support

- 📖 [Documentation](https://github.com/Gitlawb/openclaude#readme)
- 💬 [Discussions](https://github.com/Gitlawb/openclaude/discussions)
- 🐛 [Issues](https://github.com/Gitlawb/openclaude/issues)
- ⭐ [Star History](https://star-history.com/#Gitlawb/openclaude&Date)

---

## Contributing

Contributions welcome! See [CONTRIBUTING.md](CONTRIBUTING.md).

---

*Built by the community, for the community.*
