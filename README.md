# Huellas Felices · Maquetación con Flexbox

Boilerplate de una página de adopción de animales realizado con HTML semántico y CSS Flexbox.

## Estructura

```
index.html
css/reset.css   (reset propio)
css/style.css   (variables, Flexbox y estilos)
images/         (añade aquí tus fotografías)
README.md
design.md
```

## Características

- Cabecera, navegación, contenido principal, barra lateral y pie semánticos.
- Diseño fluido centrado, con ancho máximo de 1400 px.
- Flexbox para distribuir la navegación, la barra lateral y las tarjetas.
- Menú y contenido apilados en pantallas de 700 px o menos.
- Reset CSS propio, variables globales y fuentes de Google Fonts.
- Fotografías de animales y enlaces con iconos de redes sociales incluidos en `images/`.
- Enlace fijo para volver al inicio y foco visible para teclado.
- Metadatos descriptivos.

## Imágenes e iconos

Las tarjetas muestran las fotografías `perra.webp`, `gato.webp` y `perro.webp`. El pie incluye iconos SVG para Facebook, Instagram y X. Todos estos recursos están en `images/`; puedes sustituirlos por otros manteniendo las rutas o actualizando sus referencias en `index.html`.

## Ejecución

Abre `index.html` en un navegador o inicia un servidor local, por ejemplo con `python -m http.server`.

La especificación visual y las reglas para mantener el diseño están en [design.md](./design.md).
