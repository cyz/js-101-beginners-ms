# Variables

Las variables son espacios reservados para almacenar información que usarás en tu aplicación. Pueden ser relativamente pequeñas, como un número, o grandes, como objetos complejos. Independientemente de los datos que la variable almacenará, las declararás todas de la misma manera. Lo que cambiará es dónde quieres que exista la variable y la capacidad de modificarla.

En JavaScript moderno, hay tres formas principales de declarar variables:

## const

Se usa para declarar constantes, es decir, variables cuyo valor no cambiará después de su asignación inicial.

```javascript
const PI = 3.14159;
```

## let

Se utiliza para declarar variables que pueden ser reasignadas. Su alcance está limitado al bloque en el que se declara.

```javascript
let contador = 0;
contador = contador + 1;
```

## var

Es la forma más antigua de declarar variables en JavaScript. Tiene un alcance de función o global, lo que puede llevar a comportamientos inesperados. En el código moderno, se prefiere usar `let` y `const`.

```javascript
var nombre = "Juan";
```

Es importante elegir el tipo de declaración adecuado según el uso previsto de la variable:

- Usa `const` para valores que no cambiarán
- Usa `let` para variables que necesitarás reasignar
- Evita usar `var` en código nuevo, a menos que tengas una razón específica para hacerlo

## Lecturas adicionales

- [const](https://developer.mozilla.org/es/docs/Web/JavaScript/Reference/Statements/const)
- [let](https://developer.mozilla.org/es/docs/Web/JavaScript/Reference/Statements/let)
- [var](https://developer.mozilla.org/es/docs/Web/JavaScript/Reference/Statements/var)
