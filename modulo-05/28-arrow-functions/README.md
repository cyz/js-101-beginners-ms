# Funciones flecha

Las funciones flecha, también conocidas como funciones anónimas, permiten crear funciones sin un nombre. Esto es especialmente útil al trabajar con callbacks y promesas, que son comunes en JavaScript.

## Sintaxis básica

La sintaxis básica de una función flecha es la siguiente:

```javascript
(parametros) => { 
  // cuerpo de la función
}
```

Para funciones simples de una sola línea, se puede omitir las llaves y la palabra clave `return`:

```javascript
const suma = (a, b) => a + b;
```

## Características principales

1. Sintaxis concisa: Ideal para funciones cortas y simples.

2. No tienen su propio `this`: Heredan el `this` del contexto circundante.

3. No pueden ser usadas como constructores: No se pueden usar con `new`.

4. No tienen objeto `arguments`: Se recomienda usar parámetros rest en su lugar.

5. Retorno implícito: Para expresiones de una sola línea.

## Ejemplos de uso

```javascript
// Función flecha como callback
const numeros = [1, 2, 3, 4, 5];
const cuadrados = numeros.map(num => num * num);

// Función flecha con múltiples parámetros
const multiplicar = (a, b) => a * b;

// Función flecha sin parámetros
const saludar = () => console.log("Hola mundo");
```

Las funciones flecha son particularmente útiles en situaciones donde se necesitan funciones cortas y donde mantener el contexto de `this` es importante, como en callbacks y métodos de array.

## Lecturas adicionales

- [Funciones](https://developer.mozilla.org/es/docs/Glossary/Function)

Citations:
[1] https://www.w3schools.com/js/js_arrow_function.asp
[2] https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Functions/Arrow_functions
[3] https://www.geeksforgeeks.org/arrow-functions-in-javascript/
[4] https://www.freecodecamp.org/news/javascript-arrow-functions-in-depth/
[5] https://www.youtube.com/watch?v=fRRRkognpOs
[6] https://info.codecast.io/blog/javascript-arrow-functions-how-why-and-why-not
