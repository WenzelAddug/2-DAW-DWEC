# Imagenes

Carrusel que va pasando imágenes al pulsar un botón.

## Archivos

- `Imagenes.html`: la página con el botón y el script.
- `bbl.jpg`, `images.jpg`, `madara.jpg`, `Minato.jpg`, `tobirama.jpg`: las imágenes del carrusel.

## Cómo funciona

Los nombres de las imágenes están guardados en un array y la variable `posicion` indica cuál se está viendo.

Al pulsar **PASAR**, la función `pasar()` suma uno a `posicion` y cambia el `src` de la imagen. Cuando llega al final del array vuelve a la posición 0, así que el carrusel no se acaba nunca.

## Qué se practica

- Arrays y la propiedad `length`
- Variables globales para guardar el estado
- Cambiar el `src` de una imagen desde JavaScript

## Cómo probarlo

Abre `Imagenes.html` en el navegador. Las imágenes tienen que estar en la misma carpeta que el HTML.
