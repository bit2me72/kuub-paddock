# Publicar con Cloudflare Pages

1. En GitHub, crea el repositorio público `kuub-paddock` y sube estos archivos junto con `index.html`.
2. En Cloudflare: Workers & Pages → Create → Pages → Connect to Git → elige el repositorio.
3. Framework preset: None. Build command: vacío. Build output directory: `/` (raíz).
4. Deploy. Obtendrás una URL `*.pages.dev`; después puedes añadir un dominio propio.
5. Cada cambio en la rama principal se publica solo. Las otras ramas generan una vista previa.

## Cuando el archivo crezca
Si `index.html` pasa de ~15-20 MB, mover imágenes a `assets/` y cargar los trazados bajo demanda.

## Equipos y pilotos
Pendiente para diciembre 2026, con listas oficiales de inscritos. Irán en `data/` como un archivo JSON por serie y temporada.
