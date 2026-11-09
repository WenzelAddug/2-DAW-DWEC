# Dado

Simulación del lanzamiento de un dado de seis caras.

## Archivos

- `dado.html`: la página con el botón y el script.
- `dado1.jpg` a `dado6.jpg`: una imagen por cada cara del dado.

## Cómo funciona

Al pulsar **LANZAR**, la función `lanzar()`:

1. Genera un número aleatorio del 1 al 6 con `Math.floor(Math.random() * 6) + 1`.
2. Cambia el `src` de la imagen por `dado` + número + `.jpg`.
3. Escribe en el `textarea` el número que ha salido.

## Qué se practica

- `Math.random()` y `Math.floor()`
- `document.getElementsByTagName()`
- Cambiar el `src` de una imagen desde JavaScript

## Cómo probarlo

Abre `dado.html` en el navegador. Las imágenes tienen que estar en la misma carpeta que el HTML.
