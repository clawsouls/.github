<div align="center">

<img src="https://raw.githubusercontent.com/clawsouls/clawsouls/main/assets/logo.png" width="180" alt="ClawSouls" />

# ClawSouls

### When you change your AI's soul, you don't just change the AI. You change yourself.

**Open-spec platform for shareable AI agent personas.**

[![Website](https://img.shields.io/badge/clawsouls.ai-Visit-blueviolet?style=for-the-badge)](https://clawsouls.ai)
[![CLI](https://img.shields.io/npm/v/clawsouls?style=for-the-badge&label=CLI&color=orange)](https://www.npmjs.com/package/clawsouls)
[![License](https://img.shields.io/badge/License-Apache%202.0-blue?style=for-the-badge)](https://github.com/clawsouls/clawsouls/blob/main/LICENSE)
[![X](https://img.shields.io/badge/@ClawSoulsAI-Follow-black?style=for-the-badge&logo=x)](https://x.com/ClawSoulsAI)

---

*79+ curated personas. One command to install. Open spec. LLM-agnostic. Platform-portable.*

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

Or visit **[clawsouls.ai](https://clawsouls.ai)** to browse the gallery.

## 🎭 Featured Souls

| Soul | Vibe | For |
|------|------|-----|
| 🧠 **[surgical-coder](https://clawsouls.ai/en/souls/clawsouls/surgical-coder)** | Disciplined, minimal, goal-driven | Precise coding |
| 🅱️ **[brad](https://clawsouls.ai/en/souls/clawsouls/brad)** | Formal, professional | Development partner |
| ⚡ **[minimalist](https://clawsouls.ai/en/souls/clawsouls/minimalist)** | Less is more | Developers who hate fluff |
| 🎮 **[gamedev-mentor](https://clawsouls.ai/en/souls/clawsouls/gamedev-mentor)** | Patient teacher | Game development |
| 🔧 **[devops-veteran](https://clawsouls.ai/en/souls/clawsouls/devops-veteran)** | Battle-scarred pragmatist | Infrastructure & ops |
| 📊 **[data-scientist](https://clawsouls.ai/en/souls/clawsouls/data-scientist)** | Numbers don't lie | Data-driven insights |

**[Browse all 79+ souls →](https://clawsouls.ai/en/souls)**

## 🏗️ Repositories

| Repo | Description |
|------|-------------|
| [`clawsouls`](https://github.com/clawsouls/clawsouls) | Soul Spec, docs & standards |
| [`clawsouls-cli`](https://github.com/clawsouls/clawsouls-cli) | CLI tool (`npx clawsouls`) |
| [`clawsouls-skill`](https://github.com/clawsouls/clawsouls-skill) | OpenClaw integration skill |

## 🤝 Create & Publish

```bash
# Scaffold a new soul
npx clawsouls init my-soul

# Edit the files, then publish
npx clawsouls publish ./my-soul/
```

Follow the **[Soul Spec v0.3](https://github.com/clawsouls/clawsouls/blob/main/docs/soul-spec-v0.3.md)** to build your own. Get your publish token at [clawsouls.ai/dashboard](https://clawsouls.ai/en/dashboard).

## 📄 Resources

- 📜 [The Soul Thesis](https://clawsouls.ai/en/manifesto) — Our manifesto
- 📄 [Research Paper](https://doi.org/10.5281/zenodo.18678616) — "Soul-Driven Interaction Design" (Lee, 2026)
- 📋 [License Guide](https://clawsouls.ai/en/licenses) — Allowed licenses (permissive only)
- 📖 [Community Guidelines](https://clawsouls.ai/en/guidelines)

## 📜 License

Apache 2.0 — open spec, open tools, your data stays yours.

<div align="center">

---

**Built for the [OpenClaw](https://github.com/openclaw/openclaw) ecosystem** 🦞

*Souls are LLM-agnostic. Use them with Claude, GPT, Gemini, Llama, or anything else.*

*Not affiliated with or endorsed by OpenClaw.*

</div>
