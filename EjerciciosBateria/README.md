# EjerciciosBateria

Batería de ejercicios de JavaScript sobre cadenas, arrays y números aleatorios.

## Ejercicios

| Archivo | Ejercicio | Estado |
| --- | --- | --- |
| `Ejercicio1MediadeNumeros.html` | Media de una serie de números | Terminado |
| `Ejercicio2CharyRandom.html` | Carácter aleatorio de una frase | Terminado |
| `Ejercicio3IndexOf.html` | Buscar un queso con `indexOf` | Terminado |
| `Ejercicio4CifradoCesar.html` | Cifrado César | Terminado |
| `Ejercicio5CuadradosAleatorios.html` | Cuadrados de colores aleatorios | Terminado |

### Ejercicio 1 - Media de números

Se van escribiendo números y, al introducir un 0, se calcula la media de todos. Se puede hacer de dos formas:

- **Añadir** guarda en un array el número escrito en la caja. Al escribir 0 se muestra la media.
- **Hacerlo con prompt** va pidiendo los números con `prompt()` dentro de un bucle `do...while` hasta que se escribe 0.

### Ejercicio 2 - charAt y random

Se escribe una frase y la función `aleatorio()` devuelve un carácter al azar usando `Math.random()` y `charAt()`.

- **Caracter de parada** elige un carácter de la frase como parada.
- **Ver** va sacando caracteres al azar hasta que sale el de parada.

### Ejercicio 3 - indexOf

Hay dos cadenas con los mismos quesos, una en minúsculas y otra con mayúsculas. Se escribe un queso y el programa dice en qué posición y en cuál de las dos cadenas está, o avisa de que no está en ninguna.

### Ejercicio 4 - Cifrado César

Cifra un texto desplazando cada carácter tantas posiciones como indique la clave. La función `cifrar()` recorre el texto, suma la clave al código de cada carácter con `charCodeAt()` y lo vuelve a convertir en letra con `String.fromCharCode()`.

Para descifrar basta con usar la misma clave en negativo.

### Ejercicio 5 - Cuadrados aleatorios

Un bucle `for` dibuja 2000 cuadrados con `document.write()`, cada uno con un color RGB y una posición aleatorios.

## Qué se practica

- `charAt()` e `indexOf()`
- `charCodeAt()` y `String.fromCharCode()`
- `Math.random()` y `Math.floor()`
- Arrays y `push()`
- Bucles `for` y `do...while`
- `parseInt()`, `parseFloat()` e `isNaN()`
- `alert()`, `prompt()` y `document.write()`
- Estilos en línea generados desde JavaScript

## Cómo probarlo

Abre cualquiera de los archivos `.html` en el navegador.
