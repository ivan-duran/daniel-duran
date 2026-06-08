# Daniel Duran Vilches Portfolio

Portfolio visual de Daniel Duran Vilches, periodista y creador audiovisual. El sitio presenta una seleccion editorial de fotografia, video, cobertura y diseno, con una experiencia de galeria como pieza principal.

## Stack

- Astro
- Fancybox para lightbox de imagenes y videos
- Astro Assets para optimizacion de imagenes
- Biome, Stylelint y Astro Check para validacion

## Estructura

- `src/pages/index.astro`: pagina unica con portada, bitacora seleccionada, capacidades y contacto.
- `src/components/MediaGrid.astro`: grilla justificada con fotos, videos, captions y lightbox.
- `src/components/HeroCard.astro`: bloques editoriales para capacidades visuales.
- `src/images`: material fotografico, audiovisual y metadatos `.md`.

## Desarrollo

```sh
pnpm install
pnpm run dev
pnpm run check
pnpm run build
```

## Contenido

Las fotos y videos viven en `src/images`. Cuando un archivo multimedia tiene un `.md` con el mismo nombre, ese archivo alimenta el caption del lightbox con titulo, ubicacion, fecha, descripcion y tags.
