# 🤖 Agentes de IA

Si usas Claude Code, Copilot, Cursor, Antigravity u otro agente, este también debe seguir la guía. Los agentes leen el archivo `AGENTS.md` (o `CLAUDE.md`) del repo, así que cada repo debería incluir esta sección:

```markdown
## Git conventions

Follow https://github.com/GDG-Tarija/.github/blob/master/docs/README.md

- Branches: `<type>/<WI>-<short-description>` (event landings: `<event><year>/<WI>-<short-description>`, e.g. `devfest2026/42-speakers-section`)
- Commits and PR titles: Conventional Commits **in English** — `type(scope): description`
- Open PRs against `develop`, never push to `master`/`main` or `develop`
- Add `Closes #<WI>` to the PR description
```

## Recuerda

- Revisa lo que hace el agente antes de abrir el PR: **tú eres responsable del código**.
- Si el agente crea ramas con su propio nombre (`claude/...`, `copilot/...`), renómbralas al formato del equipo antes de abrir el PR.
