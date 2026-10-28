# ✍️ Commits

Usamos [Conventional Commits](https://www.conventionalcommits.org/), **en inglés**.

```
<type>(<scope>): <description>
```

- **type**: qué tipo de cambio es (tabla de abajo).
- **scope** (opcional): la parte del proyecto afectada (`navbar`, `members`) o el evento (`devfest2026`).
- **description**: corta, en imperativo (`add`, `fix`, `update`; no `added` ni `adds`) y sin punto final.

## Tipos

| Type | Cuándo usarlo | Ejemplo |
| --- | --- | --- |
| `feat` | Algo nuevo | `feat(devfest2026): add speakers section` |
| `fix` | Arreglar un error | `fix(navbar): align logo on mobile` |
| `docs` | Solo documentación | `docs: add setup steps to README` |
| `style` | Formato, sin cambiar lógica | `style: format files with Prettier` |
| `refactor` | Reordenar código sin cambiar lo que hace | `refactor(card): simplify image rendering` |
| `chore` | Dependencias, configuración, CI | `chore(deps): upgrade Astro to 6.2` |

¿Un cambio que rompe algo existente? Agrega `!`: `feat(api)!: remove v1 endpoints`.

## ✅ / ❌

```
✅ feat(devfest2026): add registration button
✅ fix(members): show organizer role badge
✅ chore: update dependencies

❌ changes                      (no dice nada)
❌ Fixed stuff                  (sin tipo, en pasado)
❌ feat: agregar ponentes       (en español)
```

> No te preocupes demasiado por los commits intermedios de tu rama: al hacer merge usamos *squash*, y el **título del PR** queda como commit final. Ver [Pull Requests](pull-requests.md).
