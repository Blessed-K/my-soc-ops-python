<!-- l10n-sync: source-file="README.md" -->
<div align="center">

🌐 [Português (BR)](README.pt_BR.md) | [Español](README.es.md)

# 🎱 Soc Ops

**Bingo Social para encuentros presenciales** — encuentra personas que coincidan, consigue 5 en fila, gana la sala.

[![Python](https://img.shields.io/badge/Python-3.13-3776ab?logo=python&logoColor=white)](https://www.python.org/)
[![FastAPI](https://img.shields.io/badge/FastAPI-0.115+-009688?logo=fastapi&logoColor=white)](https://fastapi.tiangolo.com/)
[![HTMX](https://img.shields.io/badge/HTMX-powered-3d72d7?logo=html5&logoColor=white)](https://htmx.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![GitHub Copilot](https://img.shields.io/badge/Built%20with-GitHub%20Copilot-8957e5?logo=github&logoColor=white)](https://github.com/features/copilot)

</div>

---

## ✨ ¿Qué es Soc Ops?

Soc Ops es una **aplicación web de Bingo Social en vivo** diseñada para romper el hielo en eventos presenciales. Cada jugador recibe una tarjeta de bingo 5×5 única con preguntas divertidas — *"ha vivido en otro país"*, *"puede hacer malabares"*, *"ama la comida picante"* — y debe socializar para encontrar personas que coincidan.

Sin descargas. Sin cuentas. Solo abre el navegador y juega.

> 🏆 ¡El primero en conseguir **5 en fila** gana — en horizontal, vertical o diagonal!

---

## 🛠️ Stack Tecnológico

| Capa | Tecnología |
|------|------------|
| **Backend** | Python 3.13 + FastAPI |
| **Plantillas** | Jinja2 |
| **Interactividad** | HTMX (¡sin framework JavaScript!) |
| **Estilos** | CSS personalizado |
| **Estado** | Sesiones del lado del servidor (cookies firmadas) |
| **Herramientas** | uv, Ruff, pytest |

---

## 🚀 Primeros Pasos

```bash
# 1. Clona el repositorio
git clone https://github.com/Blessed-K/my-soc-ops-python.git
cd my-soc-ops-python

# 2. Instala dependencias (requiere uv)
uv sync

# 3. Inicia el servidor de desarrollo
uv run uvicorn app.main:app --reload --port 8000
```

Abre **http://localhost:8000** y ¡empieza a jugar! 🎉

> 💡 **Consejo:** Usa el [Dev Container](.devcontainer/) incluido para un entorno pre-configurado sin configuración en VS Code.

---

## 🎮 Características

- 🃏 **Tarjetas únicas** — cada jugador recibe un tablero recién barajado
- ⚡ **Actualizaciones instantáneas** — clics con HTMX sin recargas de página completa
- 🆓 **Espacio libre** — la casilla central siempre está pre-marcada
- 🏅 **Detección de victoria** — verificación automática de bingo en filas, columnas y diagonales
- 🔄 **Reinicia en cualquier momento** — comienza un nuevo juego sin salir de la página
- 🌐 **Sin registro** — el estado de la sesión vive en una cookie segura

---

## 🧪 Pruebas y Linting

```bash
# Ejecutar pruebas
uv run pytest

# Linting
uv run ruff check .
```

---

## 📚 Guía del Laboratorio

Este repositorio también funciona como un **taller práctico de GitHub Copilot Agent** (~1 hora, nivel intermedio). Trabaja en las partes a continuación para mejorar tus habilidades de desarrollo asistido por IA.

| Parte | Título | Tiempo | Qué harás |
|-------|--------|--------|-----------|
| [**00**](https://copilot-dev-days.github.io/agent-lab-python/docs/step.html?step=00-overview) | Visión General y Lista de Verificación | — | Requisitos previos y verificación del entorno |
| [**01**](https://copilot-dev-days.github.io/agent-lab-python/docs/step.html?step=01-setup) | Configuración y Context Engineering | 15 min | Enseña a Copilot sobre tu proyecto |
| [**02**](https://copilot-dev-days.github.io/agent-lab-python/docs/step.html?step=02-design) | Desarrollo Frontend Orientado al Diseño | 15 min | Rediseña la UI con temas creativos |
| [**03**](https://copilot-dev-days.github.io/agent-lab-python/docs/step.html?step=03-quiz-master) | Quiz Master Personalizado | 10 min | Crea tus propios temas con agentes personalizados |
| [**04**](https://copilot-dev-days.github.io/agent-lab-python/docs/step.html?step=04-multi-agent) | Desarrollo Multi-Agente | 20 min | Construye nuevas funciones con TDD + agentes de diseño |

> 📝 Las guías del laboratorio también están disponibles en la carpeta [`workshop/`](workshop/) para lectura sin conexión.

### 🎯 Lo que aprenderás

- **Context Engineering** — escribe instrucciones que hagan que la IA entienda tu proyecto
- **Flujos de Trabajo Agénticos** — sesiones CLI, agentes en la nube y definiciones de agentes personalizados
- **Desarrollo Orientado al Diseño** — itera en la UI mientras guías la visión
- **Desarrollo Orientado a Pruebas** — usa agentes TDD para funcionalidades confiables y bien probadas

---

## 🤝 Contribuir

¡Las contribuciones son bienvenidas! Lee [CONTRIBUTING.md](CONTRIBUTING.md) y sigue el [Código de Conducta](CODE_OF_CONDUCT.md).

---

## 📄 Licencia

[MIT](LICENSE) © Blessed-K
