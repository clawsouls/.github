<div align="center">

<img src="https://raw.githubusercontent.com/clawsouls/clawsouls/main/assets/new_logo/full_logo_light.png" width="180" alt="ClawSouls" />

# ClawSouls

### When you change your AI's soul, you don't just change the AI. You change yourself.

**Open-spec platform for shareable AI agent personas.**

[![Website](https://img.shields.io/badge/clawsouls.ai-Visit-blueviolet?style=for-the-badge)](https://clawsouls.ai)
[![CLI](https://img.shields.io/npm/v/clawsouls?style=for-the-badge&label=CLI&color=orange)](https://www.npmjs.com/package/clawsouls)
[![MCP](https://img.shields.io/npm/v/soul-spec-mcp?style=for-the-badge&label=MCP&color=green)](https://www.npmjs.com/package/soul-spec-mcp)
[![License](https://img.shields.io/badge/License-Apache%202.0-blue?style=for-the-badge)](https://github.com/clawsouls/clawsouls/blob/main/LICENSE)
[![Docs](https://img.shields.io/badge/Docs-Read-informational?style=for-the-badge)](https://docs.clawsouls.ai)
[![X](https://img.shields.io/badge/@ClawSoulsAI-Follow-black?style=for-the-badge&logo=x)](https://x.com/ClawSoulsAI)

---

*80+ curated personas. One command to install. Open spec. LLM-agnostic. Platform-portable.*

📜 **[Read The Soul Thesis →](https://clawsouls.ai/en/manifesto)**

</div>

## 🧠 What is a Soul?

A Soul is a set of markdown files that give an AI agent a consistent personality, voice, and behavior.

Anthropic Skills define **what** an agent can do. Souls define **who** it is when it does it.

```
my-soul/
├── soul.json       # metadata & config
├── SOUL.md         # core personality
├── IDENTITY.md     # name, emoji, vibe
├── AGENTS.md       # behavioral guidelines
├── STYLE.md        # writing voice & tone
├── HEARTBEAT.md    # periodic checks
└── README.md       # documentation
```

No code. No API keys. No vendor lock-in. Just text files that any AI can read.

## ⚡ Quick Start

```bash
# Install a soul
npx clawsouls install clawsouls/surgical-coder

# Apply it to your workspace
npx clawsouls use clawsouls/surgical-coder

# Restart your agent — done!
openclaw gateway restart
```

Or visit **[clawsouls.ai](https://clawsouls.ai)** to browse the gallery — you can also **[create a soul in the browser](https://clawsouls.ai/en/dashboard/editor/new)**.

## 🎭 Featured Souls

| Soul | Vibe | For |
|------|------|-----|
| 🧠 **[surgical-coder](https://clawsouls.ai/en/souls/clawsouls/surgical-coder)** | Disciplined, minimal, goal-driven | Precise coding |
| 🅱️ **[brad](https://clawsouls.ai/en/souls/TomLeeLive/brad)** | Formal, professional | Development partner |
| ⚡ **[minimalist](https://clawsouls.ai/en/souls/clawsouls/minimalist)** | Less is more | Developers who hate fluff |
| 🎮 **[gamedev-mentor](https://clawsouls.ai/en/souls/clawsouls/gamedev-mentor)** | Patient teacher | Game development |
| 🔧 **[devops-veteran](https://clawsouls.ai/en/souls/clawsouls/devops-veteran)** | Battle-scarred pragmatist | Infrastructure & ops |
| 📊 **[data-scientist](https://clawsouls.ai/en/souls/clawsouls/data-scientist)** | Numbers don't lie | Data-driven insights |

**[Browse all 80+ souls →](https://clawsouls.ai/en/souls)**

## 🏗️ Repositories

| Repo | Description |
|------|-------------|
| [`soulspec`](https://github.com/clawsouls/soulspec) | **Soul Spec** — open standard for AI agent personas |
| [`clawsouls`](https://github.com/clawsouls/clawsouls) | Platform overview, docs & examples |
| [`clawsouls-cli`](https://github.com/clawsouls/clawsouls-cli) | CLI tool (`npx clawsouls`) — 22 commands |
| [`soul-spec-mcp`](https://github.com/clawsouls/soul-spec-mcp) | MCP server for Claude, Cursor, Windsurf |
| [`scan-rules`](https://github.com/clawsouls/scan-rules) | SoulScan security rules (53 patterns) |
| [`clawsouls-skill`](https://github.com/clawsouls/clawsouls-skill) | OpenClaw integration skill |

## 🤝 Create & Publish

```bash
# Scaffold a new soul
npx clawsouls init my-soul

# For robotics/embodied agents
npx clawsouls init my-robot --spec 0.5

# Edit the files, then publish
npx clawsouls publish ./my-soul/
```

Or **[create in the browser →](https://clawsouls.ai/en/dashboard/editor/new)** with real-time validation & SoulScan.

Follow the **[Soul Spec v0.5](https://github.com/clawsouls/soulspec/blob/main/soul-spec-v0.5.md)** to build your own.

## 🔌 Compatible Frameworks

Soul Spec works with any SOUL.md-compatible agent:

**[OpenClaw](https://openclaw.ai)** · **[Claude Code](https://docs.anthropic.com/en/docs/claude-code)** · **[Claude Desktop](https://claude.ai)** · **[Cursor](https://cursor.sh)** · **[Windsurf](https://codeium.com/windsurf)** · and more

## 📄 Resources

- 📜 [The Soul Thesis](https://clawsouls.ai/en/manifesto) — Our manifesto
- 🌐 [soulspec.org](https://soulspec.org) — Spec website
- 📄 [Research Paper](https://doi.org/10.5281/zenodo.18758910) — "Soul-Driven Interaction Design" (Lee, 2026)
- 🔒 [SoulScan](https://clawsouls.ai/en/soulscan) — Security validation for AI personas
- 📋 [License Guide](https://clawsouls.ai/en/licenses) — Allowed licenses (permissive only)

## 📜 License

Apache 2.0 — open spec, open tools, your data stays yours.

<div align="center">

---

**Built for OpenClaw, works with any SOUL.md-compatible agent** 🦞

*Souls are LLM-agnostic. Use them with Claude, GPT, Gemini, Llama, or anything else.*

*Not affiliated with or endorsed by OpenClaw.*

</div>
