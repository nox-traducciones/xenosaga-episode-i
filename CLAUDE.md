# Reglas del repo

Traducción de *xenosaga-episode-i* al español con el kit de traducción de juegos (`~/.claude/loc-kit`: METHOD.md y REPO.md).

- Empezar o retomar el proyecto: skill `loc-start`. Traducir un lote: skill `loc-batch`.
- `main` está protegido: todo cambio va en una rama y un pull request, sin firma de Claude. El usuario fusiona; Claude nunca fusiona.
- Al cerrar un lote o una fase: casillas del PLAN, `loc.py progress --readme`, commit, push y pull request, sin pedir permiso.
- Sin spoilers en los documentos, los commits, los pull requests y el chat: se nombran zonas o archivos, nunca hechos de la historia.
- En el repo nunca van archivos del juego: lo extraído vive fuera, en `../local/xenosaga-episode-i/`.
- No se inventan reglas: solo valen STYLE.md, TECH.md, GLOSSARY.md, las fichas de `characters/` y DECISIONS.md. Lo que no cubren va a PENDING.md.
- Antes de lanzar agentes, estimar el costo y pedir el visto bueno; nunca más de unos 3 a la vez.
