
# Copilot Workspace Instructions

**Mandatory Dev Checklist**
- [ ] Lint: `uv run ruff check .`
- [ ] Build: `uv sync`
- [ ] Test: `uv run pytest`

**Project:**  
Social Bingo game (Python, FastAPI, Jinja2, HTMX).

**Key Commands:**  
- Dev server: `uv run uvicorn app.main:app --reload --port 8000`
- Lint: `uv run ruff check .`
- Test: `uv run pytest`

**Structure:**  
- App: `app/` (logic, templates, static)
- Tests: `tests/`
- Guides: `workshop/`

**Styling:**  
Custom CSS utilities in `app/static/css/app.css`  
(see `.github/instructions/css-utilities.instructions.md`)

**State:**  
`GameSession` (server-side, signed cookies), HTMX for partial updates.

**More:**  
See [README.md](README.md) and `.github/instructions/` for details.