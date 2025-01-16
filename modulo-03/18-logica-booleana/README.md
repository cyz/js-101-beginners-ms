# Lógica Booleana

La lógica booleana es fundamental para la toma de decisiones en programación. JavaScript ofrece dos estructuras principales para manejar la lógica de ramificación: `if`/`else` y `switch`/`case`.

## Estructura if/else

La estructura `if`/`else` permite ejecutar diferentes bloques de código basados en condiciones booleanas:

```javascript
if (condicion) {
  // Código a ejecutar si la condición es verdadera
} else if (otraCondicion) {
  // Código a ejecutar si otraCondicion es verdadera
} else {
  // Código a ejecutar si ninguna condición anterior es verdadera
}
```

Esta estructura evalúa cada condición en orden y ejecuta el bloque correspondiente a la primera condición verdadera.

## Estructura switch/case

La estructura `switch`/`case` es útil cuando se necesita comparar una expresión con múltiples valores posibles:

```javascript
switch (expresion) {
  case valor1:
    // Código a ejecutar si expresion === valor1
    break;
  case valor2:
    // Código a ejecutar si expresion === valor2
    break;
  default:
    // Código a ejecutar si ningún caso coincide
}
```

Esta estructura evalúa la `expresion` y ejecuta el bloque de código del `case` que coincida. El `break` es importante para evitar la ejecución en cascada.

## Comparación entre if/else y switch/case

- **if/else**: Más flexible, permite condiciones complejas.
- **switch/case**: Más eficiente para múltiples comparaciones de igualdad.

## Operadores lógicos

Los operadores lógicos son esenciales en la lógica booleana:

- `&&` (AND): Verdadero si ambas condiciones son verdaderas.
- `||` (OR): Verdadero si al menos una condición es verdadera.
- `!` (NOT): Invierte el valor booleano.

## Valores truthy y falsy

En JavaScript, los valores se consideran "truthy" o "falsy" en contextos booleanos:

- Falsy: `false`, `0`, `""`, `null`, `undefined`, `NaN`
- Truthy: Todos los demás valores

Es importante tener en cuenta estos valores al realizar evaluaciones condicionales.

## Lecturas adicionales

- [if/else](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/if...else)
- [switch](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/switch)
