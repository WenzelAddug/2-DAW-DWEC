# Ejercicios Arrays, Set y Map

Batería de ejercicios de JavaScript sobre String, Arrays, Set y Map.

## Ejercicios

| Archivo | Ejercicio | Estado |
| --- | --- | --- |
| `Ejercicio1ArraySinRepetidos.html` | Array sin elementos repetidos | Terminado |
| `Ejercicio2CifradoPolialfabetico.html` | Cifrado polialfabético | Terminado |
| `Ejercicio3LoteriaPrimitiva.html` | 50 combinaciones de la primitiva | Terminado |
| `Ejercicio4Asteriscos.html` | Asteriscos para un array | Terminado |
| `Ejercicio5Frecuencias.html` | Frecuencias de `Math.random()` | Terminado |
| `Ejercicio6Palindromos.html` | Palíndromos | Terminado |

### Ejercicio 1 - Array sin repetidos

A partir de un array con números repetidos se obtiene otro sin repetidos. Se recorre el array con `for...of` y se guardan con `push()` solo los números que todavía no están (`includes()`).

### Ejercicio 2 - Cifrado polialfabético

Se pide un mensaje y una clave formada solo por números. A cada carácter del mensaje se le suma el número de la clave que le toca, usando `charCodeAt()` y `String.fromCharCode()`. Cuando se acaba la clave se vuelve a empezar por el principio.

Si la clave no es un número (`isNaN()`) se vuelve a pedir con un `do...while`.

Ejemplo: con el mensaje `Este es el mensaje.` y la clave `12345` sale `Fuwi%fu#iq!ohrxblh2`.

### Ejercicio 3 - Lotería primitiva

Muestra 50 combinaciones de seis números del 1 al 49. Cada combinación se guarda en un `Set` y se van añadiendo números aleatorios con `add()` hasta que `size` vale 6, así no se repite ninguno.

### Ejercicio 4 - Asteriscos

Se crea un array con 20 números aleatorios del 1 al 50 y se recorre mostrando en cada línea tantos asteriscos como indique el número.

### Ejercicio 5 - Frecuencias

Para comprobar si `Math.random()` es realmente aleatoria se calculan 10.000 números del 1 al 10 y se cuenta cuántas veces sale cada uno. Se usa un `Map` donde la clave es el número y el valor las veces que ha salido.

### Ejercicio 6 - Palíndromos

Se pide un texto y se indica si es un palíndromo. Antes de comprobarlo se pasa a minúsculas, se quitan las tildes y diéresis y se ignoran los espacios y signos de puntuación. Después se le da la vuelta con `split("")`, `reverse()` y `join("")` y se compara con el original.

## Qué se practica

- Arrays: `push()`, `includes()`, `reverse()` y `join()`
- `Set`: `add()`, `size` y conversión a array con `[...conjunto]`
- `Map`: `set()`, `get()` y recorrido con `for ([clave,valor] of mapa)`
- `charCodeAt()`, `String.fromCharCode()`, `indexOf()`, `includes()`, `toLowerCase()` y `split()`
- `Math.random()` y `Math.floor()`
- Bucles `for`, `for...of`, `while` y `do...while`
- `isNaN()` y `parseInt()`
- `prompt()` y `document.write()`

## Cómo probarlo

Abre cualquiera de los archivos `.html` en el navegador.
