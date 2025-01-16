# Números y Matemáticas

Se podría decir que una computadora no es más que una calculadora sofisticada. Te dejaremos debatir la validez de ese dicho. Pero no se puede negar que las matemáticas son una de las operaciones más comunes que realizarás. JavaScript tiene un conjunto completo de opciones disponibles para ti.

## Tipos Numéricos

JavaScript utiliza el tipo de dato Number para representar tanto números enteros como de punto flotante. Internamente, los números se almacenan en formato de punto flotante de 64 bits, siguiendo el estándar IEEE 754.

```javascript
let entero = 42;
let decimal = 3.14;
```

## Operadores Aritméticos Básicos

JavaScript soporta los operadores aritméticos estándar:

- Suma: `+`
- Resta: `-`
- Multiplicación: `*`
- División: `/`
- Módulo (resto): `%`
- Exponenciación: `**`

Ejemplo:
```javascript
let suma = 5 + 3;      // 8
let producto = 4 * 2;   // 8
let potencia = 2 ** 3; // 8
```

## Objeto Math

El objeto Math proporciona propiedades y métodos para operaciones matemáticas más avanzadas:

### Constantes Matemáticas

- `Math.PI`: El valor de π (aproximadamente 3.14159)
- `Math.E`: El número de Euler (aproximadamente 2.71828)

### Métodos Útiles

- `Math.abs(x)`: Devuelve el valor absoluto de x
- `Math.round(x)`: Redondea x al entero más cercano
- `Math.floor(x)`: Redondea x hacia abajo
- `Math.ceil(x)`: Redondea x hacia arriba
- `Math.max(x, y, ...)`: Devuelve el valor más grande entre los argumentos
- `Math.min(x, y, ...)`: Devuelve el valor más pequeño entre los argumentos
- `Math.random()`: Genera un número aleatorio entre 0 (inclusive) y 1 (exclusive)

Ejemplo:
```javascript
let maximo = Math.max(5, 10, 15); // 15
let aleatorio = Math.random();    // Número entre 0 y 1
```

## Lecturas Adicionales

- [Matemáticas](https://developer.mozilla.org/es/docs/Web/JavaScript/Reference/Global_Objects/Math)
