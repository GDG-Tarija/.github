# 🚀 Releases

## Versionado

Usamos [SemVer](https://semver.org/): `MAJOR.MINOR.PATCH`.

| Cambio | Sube | Ejemplo |
| --- | --- | --- |
| Solo arreglos (`fix`) | `PATCH` | `0.1.0` → `0.1.1` |
| Algo nuevo (`feat`), como una nueva landing de evento | `MINOR` | `0.1.1` → `0.2.0` |
| Cambio grande o que rompe lo existente (rediseño, `!`) | `MAJOR` | `0.2.0` → `1.0.0` |

## Cómo publicar una versión

1. Cuando `develop` está estable, abre un PR **`develop` → producción** (`master`/`main`). Título: `chore(release): 0.2.0`.
2. En ese PR, actualiza la versión en `package.json` (si el proyecto lo tiene).
3. Con el merge hecho, ve a **Releases → Draft a new release**:
   - **Tag**: la versión, creada sobre la rama de producción (`0.2.0`).
   - **Título**: versión y evento, si aplica (`0.2.0 – DevFest 2026`).
   - Presiona **Generate release notes** y listo.

En la landing, el deploy a GitHub Pages es automático al hacer merge a `master`.

## Arreglo urgente en producción (hotfix)

Si algo se rompe en producción y `develop` tiene trabajo sin terminar:

1. Crea la rama desde producción: `fix/<WI>-<description>` (en la landing también puedes usar `<event><year>/<WI>-...`).
2. Abre un PR **directo a producción**. Al hacer merge, crea una release `PATCH`.
3. Abre un PR de producción → `develop` para que el arreglo no se pierda.
