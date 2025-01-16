# Bucles

JavaScript ofrece varias formas de ejecutar código repetidamente y actuar sobre colecciones de datos. Afortunadamente, existen tres tipos principales que te servirán bien y cubrirán casi todas las situaciones que encuentres: `for`, `for...of` y `while`.

## Bucle for

El bucle `for` es versátil y comúnmente usado para iterar un número específico de veces:

```javascript
for (let i = 0; i < 5; i++) {
  console.log(i);
}
```

Este bucle tiene tres partes: inicialización, condición y expresión final.

## Bucle for...of

El bucle `for...of` es ideal para iterar sobre elementos de objetos iterables como arrays:

```javascript
const frutas = ['manzana', 'banana', 'naranja'];
for (const fruta of frutas) {
  console.log(fruta);
}
```

Este bucle simplifica la iteración sobre colecciones sin necesidad de un contador.

## Bucle while

El bucle `while` ejecuta un bloque de código mientras una condición sea verdadera:

```javascript
let n = 0;
while (n < 3) {
  console.log(n);
  n++;
}
```

Es útil cuando no sabes cuántas iteraciones se necesitarán de antemano.

Cada tipo de bucle tiene sus propias ventajas y casos de uso. El `for` es excelente para iteraciones con un número conocido de repeticiones, `for...of` simplifica la iteración sobre colecciones, y `while` es ideal para situaciones donde la condición de finalización no está basada en un contador simple.

## Lecturas adicionales

- [for](https://developer.mozilla.org/es/docs/Web/JavaScript/Reference/Statements/for)
- [for...of](https://developer.mozilla.org/es/docs/Web/JavaScript/Reference/Statements/for...of)
- [while](https://developer.mozilla.org/es/docs/Web/JavaScript/Reference/Statements/while)
