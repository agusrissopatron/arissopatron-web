# arissopatron-web

Página profesional de la Dra. Agustina Risso Patrón (MN 139791), publicada en arissopatron.netlify.app.

- `index.html`: la página.
- `novedades.json`: novedades epidemiológicas que muestra la sección "Novedades". Cada propuesta llega como Pull Request y se publica solo cuando se aprueba (Merge).

Formato de cada novedad:

```json
{ "fecha": "2026-11-06", "tipo": "Alerta", "titulo": "…", "resumen": "…", "fuente": "Ministerio de Salud de la Nación", "url": "https://…" }
```
