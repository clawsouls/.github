<div align="center">

<img src="https://raw.githubusercontent.com/clawsouls/clawsouls/main/assets/logo.png" width="180" alt="ClawSouls" />

# ClawSouls

### Give your AI a soul.

**The open platform for AI agent personas.**

[![Website](https://img.shields.io/badge/clawsouls.ai-Visit-blueviolet?style=for-the-badge)](https://clawsouls.ai)
[![CLI](https://img.shields.io/npm/v/clawsouls?style=for-the-badge&label=CLI&color=orange)](https://www.npmjs.com/package/clawsouls)
[![License](https://img.shields.io/badge/License-Apache%202.0-blue?style=for-the-badge)](https://github.com/clawsouls/clawsouls/blob/main/LICENSE)
[![X](https://img.shields.io/badge/@ClawSoulsAI-Follow-black?style=for-the-badge&logo=x)](https://x.com/ClawSoulsAI)

---

*Souls are portable personality packages for AI agents — markdown files that define who your AI is, how it thinks, and how it speaks. No vendor lock-in. Works with any LLM.*

</div>

## 🧠 What is a Soul?

A Soul is a set of files (`SOUL.md`, `IDENTITY.md`, `STYLE.md`, and more) that give an AI agent a consistent personality, voice, and behavior. Think of it as a character sheet for your AI.

```
my-soul/
├── clawsoul.json    # metadata & config
├── SOUL.md          # core personality
├── IDENTITY.md      # name, emoji, vibe
├── AGENTS.md        # behavioral guidelines
├── STYLE.md         # writing voice & tone
└── examples/        # good & bad outputs
```

## ⚡ Quick Start

```bash
# Install a soul
npx clawsouls install minimalist

# Apply it to your workspace
npx clawsouls use minimalist

# Browse all souls
npx clawsouls list
```

Or visit **[clawsouls.ai](https://clawsouls.ai)** to explore the gallery.

## 🎭 Featured Souls

| Soul | Vibe | For |
|------|------|-----|
| ⚡ **minimalist** | Less is more | Developers who hate fluff |
| 🎮 **gamedev-mentor** | Patient teacher | Game development guidance |
| 🔧 **devops-veteran** | Battle-scarred pragmatist | Infrastructure & ops |
| 🔍 **code-reviewer** | Constructive critic | Pull request reviews |
| ✍️ **storyteller** | Narrative weaver | Creative writing & worldbuilding |
| 📊 **data-analyst** | Numbers don't lie | Data-driven insights |

**[Browse all 10 souls →](https://clawsouls.ai/souls)**

## 🏗️ Architecture

| Repo | Description |
|------|-------------|
| [`clawsouls`](https://github.com/clawsouls/clawsouls) | Spec, docs & standards |
| [`clawsouls-cli`](https://github.com/clawsouls/clawsouls-cli) | CLI tool (`npx clawsouls`) |
| [`clawsouls-web`](https://github.com/clawsouls/clawsouls-web) | Web platform & API |
| [`souls`](https://github.com/clawsouls/souls) | Official soul packages |
| [`clawsouls-skill`](https://github.com/clawsouls/clawsouls-skill) | OpenClaw integration |

## 🤝 Create Your Own

Anyone can create and share a soul. Follow the **[SOUL_SPEC](https://github.com/clawsouls/clawsouls/blob/main/docs/SOUL_SPEC_v0.2.md)** to build one, then publish it to the community.

## 📜 License

Apache 2.0 — open spec, open tools, your data stays yours.

<div align="center">

---

**Built for the [OpenClaw](https://openclaw.ai) ecosystem** 🦞

*Souls are LLM-agnostic. Use them with Claude, GPT, Gemini, Llama, or anything else.*

</div>
