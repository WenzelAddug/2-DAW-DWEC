# Ejercicios con Cruzado (en clase)

Ejercicios hechos en clase. Son formularios pequeños para practicar lo básico de JavaScript: condicionales, bucles, arrays y acceso a los elementos de la página.

## Ejercicios

| Archivo | Qué hace | Qué se practica |
| --- | --- | --- |
| `Formulario Colores.html` | Muestra una lista de colores en un `textarea` | Arrays y bucle `for` |
| `Formulario Contador.html` | Contador que baja de 10 a 0 con un botón | `parseInt()` e `if` |
| `Formulario Fruita.html` | Consulta el precio por kilo de una fruta | `switch` |
| `FormularioExtrasCoche.html` | Elige forma de pago y extras del coche y muestra un informe con el precio total | `input` tipo `radio` y `checkbox`, `checked` y `switch` |
| `FormularioControldeEdad.html` | Pide nombre y edad y deja entrar solo a mayores de 18 | `const`, `if / else if` e `isNaN()` |
| `FormularioFechaNacimiento.html` | Calcula la edad a partir de la fecha de nacimiento y dice si es mayor de edad | Objeto `Date` y operador ternario |
| `FormularioUsuarioClave.html` | Comprueba que usuario y clave no estén vacíos | Bucle `do...while` |
| `UsoPrompt.html` | Pide un número con `window.prompt()` y muestra su tipo | `prompt()` y `typeof` |
| `UsoSelectMusica.html` | Select múltiple de tipos de música que muestra lo elegido en un `textarea` | `select`, `options` y `selected` |

## Notas

- `Formulario Fruita.html` distingue mayúsculas y tildes: hay que escribir la fruta tal cual, por ejemplo `Naranjas` o `Plátanos`.
- `FormularioUsuarioClave.html` y `UsoPrompt.html` escriben el resultado en la consola, así que hay que abrir las herramientas de desarrollo (F12) para verlo.
- En `UsoPrompt.html` se ve que `prompt()` siempre devuelve un `string`, aunque se escriba un número.
- En `FormularioExtrasCoche.html` y `UsoSelectMusica.html` el HTML es el del profesor y el script lo he hecho yo desde cero. Los campos se cogen con `document.forms[0].elements[n]`, `getElementsByName` y `getElementsByTagName`, sin usar `getElementById`.
- En `UsoSelectMusica.html` para elegir varias opciones hay que mantener pulsado Ctrl al hacer clic.

## Cómo probarlo

Abre cualquiera de los archivos `.html` en el navegador.
