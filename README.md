<div align="center">

🌐 [Português (BR)](README.pt_BR.md) | [Español](README.es.md)

# 🎱 Soc Ops

**Social Bingo for in-person mixers** — find people who match, get 5 in a row, win the room.

[![Python](https://img.shields.io/badge/Python-3.13-3776ab?logo=python&logoColor=white)](https://www.python.org/)
[![FastAPI](https://img.shields.io/badge/FastAPI-0.115+-009688?logo=fastapi&logoColor=white)](https://fastapi.tiangolo.com/)
[![HTMX](https://img.shields.io/badge/HTMX-powered-3d72d7?logo=html5&logoColor=white)](https://htmx.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![GitHub Copilot](https://img.shields.io/badge/Built%20with-GitHub%20Copilot-8957e5?logo=github&logoColor=white)](https://github.com/features/copilot)

</div>

---

## ✨ What is Soc Ops?

Soc Ops is a **live Social Bingo web app** designed to break the ice at in-person events. Each player gets a unique 5×5 bingo card filled with fun prompts — *"has lived in another country"*, *"can juggle"*, *"loves spicy food"* — and has to mingle to find real people who match.

No app download needed. No accounts. Just open a browser and play.

> 🏆 First to get **5 in a row** wins — horizontally, vertically, or diagonally!

---

## 🛠️ Tech Stack

| Layer | Technology |
|-------|-----------|
| **Backend** | Python 3.13 + FastAPI |
| **Templating** | Jinja2 |
| **Interactivity** | HTMX (no JavaScript framework!) |
| **Styling** | Custom CSS utilities |
| **State** | Server-side sessions (signed cookies) |
| **Dev tooling** | uv, Ruff, pytest |

---

## 🚀 Quick Start

```bash
# 1. Clone the repo
git clone https://github.com/Blessed-K/my-soc-ops-python.git
cd my-soc-ops-python

# 2. Install dependencies (requires uv)
uv sync

# 3. Start the dev server
uv run uvicorn app.main:app --reload --port 8000
```

Open **http://localhost:8000** and start playing! 🎉

> 💡 **Tip:** Use the included [Dev Container](.devcontainer/) for a zero-setup, pre-configured environment in VS Code.

---

## 🎮 Features

- 🃏 **Unique cards** — every player gets a freshly shuffled board
- ⚡ **Instant updates** — HTMX-powered clicks with no full page reloads
- 🆓 **Free space** — center square is always pre-marked
- 🏅 **Win detection** — automatic bingo check across all rows, columns & diagonals
- 🔄 **Reset anytime** — start a fresh game without leaving the page
- 🌐 **No sign-up** — session state lives in a secure cookie

---

## 🧪 Running Tests & Linting

```bash
# Run tests
uv run pytest

# Lint
uv run ruff check .
```

---

## 📚 Workshop Lab Guide

This repo doubles as a **hands-on GitHub Copilot Agent workshop** (~1 hour, intermediate level). Work through the parts below to level up your AI-assisted development skills.

| Part | Title | Time | What you'll do |
|------|-------|------|----------------|
| [**00**](https://copilot-dev-days.github.io/agent-lab-python/docs/step.html?step=00-overview) | Overview & Checklist | — | Prerequisites & environment check |
| [**01**](https://copilot-dev-days.github.io/agent-lab-python/docs/step.html?step=01-setup) | Setup & Context Engineering | 15 min | Teach Copilot about your codebase |
| [**02**](https://copilot-dev-days.github.io/agent-lab-python/docs/step.html?step=02-design) | Design-First Frontend | 15 min | Redesign the UI with creative themes |
| [**03**](https://copilot-dev-days.github.io/agent-lab-python/docs/step.html?step=03-quiz-master) | Custom Quiz Master | 10 min | Create your own quiz themes with custom agents |
| [**04**](https://copilot-dev-days.github.io/agent-lab-python/docs/step.html?step=04-multi-agent) | Multi-Agent Development | 20 min | Build new features with TDD + design agents |

> 📝 Lab guides are also available in the [`workshop/`](workshop/) folder for offline reading.

### 🎯 What you'll learn

- **Context Engineering** — write instructions that make AI understand your project
- **Agentic Workflows** — CLI sessions, cloud agents, and custom agent definitions
- **Design-First Development** — iterate on UI while you guide the vision
- **Test-Driven Development** — use TDD agents for reliable, well-tested features

---

## 🤝 Contributing

Contributions are welcome! Please read [CONTRIBUTING.md](CONTRIBUTING.md) and follow the [Code of Conduct](CODE_OF_CONDUCT.md).

---

## 📄 License

[MIT](LICENSE) © Blessed-K
