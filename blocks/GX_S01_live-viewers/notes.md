# GX_S01 — Live Viewers

## Qué hace
Social proof dinámico: “X personas viendo desde {ciudad}”.

## Dónde se pega (Shopify)
- PDP → cerca del buybox/precio (arriba del ATC o debajo del precio).
- Ideal: Custom Liquid / HTML section.

## Dependencias
- CSS + JS ya incluidos dentro del bloque.
- No requiere librerías externas.

## Custom values (qué cambias)
- BLOCK_ID (único por página si lo usas más de 1 vez)
- INTERVAL_MS, MAX_COUNT, WEIGHTED
- CITIES_JSON (lista de ciudades)
- Colores/gradiente (COLOR_DOT, GRAD_START/END, etc.)

## QA checklist
- No se duplica el mismo BLOCK_ID en la misma página.
- Mobile: se ve alineado y legible.
- “prefers-reduced-motion” respeta accesibilidad.
