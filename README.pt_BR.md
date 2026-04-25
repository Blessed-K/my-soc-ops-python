<!-- l10n-sync: source-file="README.md" -->
<div align="center">

🌐 [Português (BR)](README.pt_BR.md) | [Español](README.es.md)

# 🎱 Soc Ops

**Bingo Social para encontros presenciais** — encontre pessoas que se encaixam, consiga 5 em linha, conquiste a sala.

[![Python](https://img.shields.io/badge/Python-3.13-3776ab?logo=python&logoColor=white)](https://www.python.org/)
[![FastAPI](https://img.shields.io/badge/FastAPI-0.115+-009688?logo=fastapi&logoColor=white)](https://fastapi.tiangolo.com/)
[![HTMX](https://img.shields.io/badge/HTMX-powered-3d72d7?logo=html5&logoColor=white)](https://htmx.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![GitHub Copilot](https://img.shields.io/badge/Built%20with-GitHub%20Copilot-8957e5?logo=github&logoColor=white)](https://github.com/features/copilot)

</div>

---

## ✨ O que é o Soc Ops?

Soc Ops é um **aplicativo web de Bingo Social ao vivo** criado para quebrar o gelo em eventos presenciais. Cada jogador recebe um cartão de bingo 5×5 único com perguntas divertidas — *"já morou em outro país"*, *"sabe fazer malabarismos"*, *"ama comida apimentada"* — e precisa socializar para encontrar pessoas que se encaixem.

Sem download de app. Sem contas. Basta abrir o navegador e jogar.

> 🏆 Quem primeiro conseguir **5 em linha** vence — na horizontal, vertical ou diagonal!

---

## 🛠️ Stack Tecnológico

| Camada | Tecnologia |
|--------|-----------|
| **Backend** | Python 3.13 + FastAPI |
| **Templating** | Jinja2 |
| **Interatividade** | HTMX (sem framework JavaScript!) |
| **Estilização** | CSS utilitário personalizado |
| **Estado** | Sessões no servidor (cookies assinados) |
| **Ferramentas** | uv, Ruff, pytest |

---

## 🚀 Primeiros Passos

```bash
# 1. Clone o repositório
git clone https://github.com/Blessed-K/my-soc-ops-python.git
cd my-soc-ops-python

# 2. Instale as dependências (requer uv)
uv sync

# 3. Inicie o servidor de desenvolvimento
uv run uvicorn app.main:app --reload --port 8000
```

Abra **http://localhost:8000** e comece a jogar! 🎉

> 💡 **Dica:** Use o [Dev Container](.devcontainer/) incluído para um ambiente pré-configurado no VS Code, sem configuração manual.

---

## 🎮 Funcionalidades

- 🃏 **Cartões únicos** — cada jogador recebe um tabuleiro embaralhado de forma diferente
- ⚡ **Atualizações instantâneas** — cliques com HTMX sem recarregar a página
- 🆓 **Espaço livre** — a casa do centro sempre vem pré-marcada
- 🏅 **Detecção de vitória** — verificação automática de bingo em linhas, colunas e diagonais
- 🔄 **Reinicie quando quiser** — comece um novo jogo sem sair da página
- 🌐 **Sem cadastro** — o estado da sessão fica em um cookie seguro

---

## 🧪 Testes e Linting

```bash
# Executar testes
uv run pytest

# Linting
uv run ruff check .
```

---

## 📚 Guia do Lab

Este repositório também funciona como um **workshop prático de GitHub Copilot Agent** (~1 hora, nível intermediário). Siga as partes abaixo para aprimorar suas habilidades de desenvolvimento assistido por IA.

| Parte | Título | Tempo | O que você vai fazer |
|-------|--------|-------|----------------------|
| [**00**](https://copilot-dev-days.github.io/agent-lab-python/docs/step.html?step=00-overview) | Visão Geral & Lista de Verificação | — | Pré-requisitos e verificação do ambiente |
| [**01**](https://copilot-dev-days.github.io/agent-lab-python/docs/step.html?step=01-setup) | Configuração & Engenharia de Contexto | 15 min | Ensine o Copilot sobre o seu projeto |
| [**02**](https://copilot-dev-days.github.io/agent-lab-python/docs/step.html?step=02-design) | Frontend Design-First | 15 min | Redesenhe a UI com temas criativos |
| [**03**](https://copilot-dev-days.github.io/agent-lab-python/docs/step.html?step=03-quiz-master) | Quiz Master Personalizado | 10 min | Crie seus próprios temas com agentes personalizados |
| [**04**](https://copilot-dev-days.github.io/agent-lab-python/docs/step.html?step=04-multi-agent) | Desenvolvimento Multi-Agente | 20 min | Construa novas funcionalidades com TDD + agentes de design |

> 📝 Os guias do lab também estão disponíveis na pasta [`workshop/`](workshop/) para leitura offline.

### 🎯 O que você vai aprender

- **Engenharia de Contexto** — escreva instruções que fazem a IA entender o seu projeto
- **Fluxos de Trabalho Agênticos** — sessões CLI, agentes na nuvem e definições de agentes personalizados
- **Desenvolvimento Design-First** — itere na UI enquanto guia a visão
- **Desenvolvimento Orientado a Testes** — use agentes TDD para funcionalidades confiáveis e bem testadas

---

## 🤝 Contribuindo

Contribuições são bem-vindas! Leia o [CONTRIBUTING.md](CONTRIBUTING.md) e siga o [Código de Conduta](CODE_OF_CONDUCT.md).

---

## 📄 Licença

[MIT](LICENSE) © Blessed-K
