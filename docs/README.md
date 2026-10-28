# 📚 GDG Tarija — Guía de trabajo del equipo

Lineamientos básicos para trabajar en los proyectos de la org **GDG-Tarija**.

Son proyectos de comunidad: la idea es tener un orden mínimo que todos puedan seguir sin fricción, no un proceso rígido. Si algo no encaja con un caso en particular, propón cómo mejorarlo y coméntalo con el equipo.

## Lo esencial en 30 segundos

1. Todo trabajo empieza con un **item (WI) en GitHub Projects**.
2. Crea una rama con el número del WI (ejemplos): `feat/42-login-page` (en la landing: `devfest2026/42-speakers-section`).
3. Haz commits con el formato `type(scope): description`.
4. Abre un **PR hacia `develop`** con `Closes #42`.
5. Con **1 aprobación** de un organizer o de la mayoría del equipo de desarrollo, se puede hacer merge.
6. Cuando `develop` está estable, se pasa a producción y se crea una **release**.

> Ramas, commits y títulos de PR se escriben **en inglés**.

## Páginas


| Página                            | Contenido                                |
| --------------------------------- | ---------------------------------------- |
| [Work Items](work-items.md)       | Cómo usar GitHub Projects                |
| [Ramas](branches.md)              | Ramas principales y cómo nombrar tu rama |
| [Commits](commits.md)             | Formato de los mensajes de commit        |
| [Pull Requests](pull-requests.md) | Cómo abrir, revisar y mergear un PR      |
| [Releases](releases.md)           | Versionado y cómo publicar una versión   |
| [Agentes de IA](ai-agents.md)     | Reglas para Claude, Copilot, Cursor, etc. |

## Repos de la org

| Repo | Producción | Integración |
| --- | --- | --- |
| [gdg-tarija](https://github.com/GDG-Tarija/gdg-tarija) (landing) | `master` | `develop` |
| [eventos-gdg-tarija](https://github.com/GDG-Tarija/eventos-gdg-tarija) | `main` | `dev` |
| [back-office-gdg-tarija](https://github.com/GDG-Tarija/back-office-gdg-tarija) | `main` | `dev` |


## ¿Dudas?

Pregunta en el issue relacionado o en el grupo del equipo (WhatsApp/Discord).