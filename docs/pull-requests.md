# 🔀 Pull Requests

## Reglas

- Todo cambio a `develop` o a producción entra **por PR**.
- **Título** con el mismo formato que un commit, en inglés: `feat(devfest2026): add speakers section`.
- En la descripción, enlaza el WI: `Closes #42`. El issue se cierra solo al hacer merge.
- (Opcional) Si hay cambios visuales, agrega un screenshot.
- Se necesita **1 aprobación** de un organizer o de la mayoría del equipo de desarrollo para hacer merge.

## Merge

| De → a | Cómo |
| --- | --- |
| tu rama → `develop` | **Squash and merge** (queda un solo commit con el título del PR) |
| `develop` → producción | **Create a merge commit** |

Después del merge, borra tu rama (GitHub muestra el botón).

## Plantilla

La plantilla se carga sola al abrir un PR en cualquier repo de la org (está en el repo `.github`). Llena lo que aplique y borra lo que no.

## Revisar un PR

No hace falta ser experto: revisa que se entienda, que funcione localmente si puedes y que siga estos lineamientos. Si algo no está claro, pregunta en un comentario.
