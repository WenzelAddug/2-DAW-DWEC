# Calculadora

Calculadora sencilla que suma, resta, multiplica y divide.

## Archivos

- `calculadora.html`: la página con los botones y el script.

## Cómo funciona

- Los botones van añadiendo números y operadores a la pantalla con `concatenar()`.
- El botón `=` calcula el resultado con `calcular()`, que evalúa la operación escrita con `eval()`.
- El botón `C` borra la pantalla con `borrar()`.
- También se puede escribir con el teclado y pulsar **Enter** para calcular. La función `teclaenter()` detecta la tecla con `event.key` y usa `preventDefault()` para que el navegador no haga nada más.

## Qué se practica

- Eventos `onclick` y `onkeydown`
- Leer y cambiar el `value` de un `input`
- `document.getElementById()`
- `eval()`

## Cómo probarlo

Abre `calculadora.html` en el navegador.
