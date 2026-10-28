# Design.md — Especificación visual para agentes IA

## Objetivo

Crear una página clara y acogedora para una protectora de animales. Debe ayudar a descubrir animales en adopción y explicar cómo colaborar. Esta especificación describe el diseño existente; no implica publicar el sitio.

## Estructura

- Cabecera con marca y menú principal.
- Contenido centrado con una barra lateral y una sección de artículos.
- Tarjetas repetidas para animales, con un espacio reservado para imagen, datos y enlace.
- Panel con información de adopción y enlaces útiles.
- Pie con identidad, redes sociales y copyright.
- Enlace circular fijo en la esquina inferior derecha para volver al inicio.

## Layout

- Flexbox es el sistema principal para alinear y distribuir elementos.
- El contenedor utiliza un ancho fluido del 92% con un máximo de 1400 px.
- En escritorio, la barra lateral aparece junto al contenido.
- A 700 px o menos, el menú, la barra lateral y el contenido se apilan.
- Las tarjetas usan `flex-wrap` y pueden pasar a filas nuevas según el espacio.

## Identidad visual

- Fondo claro y superficies blancas para transmitir limpieza y confianza.
- Verde bosque como color principal; ámbar como acento cálido.
- Montserrat para títulos y marca; Open Sans para textos.
- Fuentes de Google Fonts y Material Icons cargadas desde CDN.
- Fotografías de animales en las tarjetas e iconos SVG de redes sociales en el pie.
- Bordes discretos, esquinas redondeadas y sombras ligeras.

## Reglas para cambios

- Mantener HTML semántico y navegación por teclado.
- Mantener Flexbox como pilar del layout; no sustituirlo por Grid.
- Definir colores, fuentes y medidas comunes en `:root` de `css/style.css`.
- Mantener las interacciones sencillas y legibles, sin animaciones innecesarias.
- No añadir dependencias ni cambiar la temática sin una petición expresa.
