# Arrays

Los arrays en JavaScript proporcionan una forma poderosa de almacenar y manipular listas de elementos. Ofrecen diversas funcionalidades para trabajar con colecciones de datos de manera eficiente.

## Creación de arrays

Hay varias formas de crear un array en JavaScript:

1. Usando la notación de corchetes (recomendada):
   ```javascript
   const frutas = ['manzana', 'plátano', 'naranja'];
   ```

2. Usando el constructor Array:
   ```javascript
   const numeros = new Array(1, 2, 3, 4, 5);
   ```

## Acceso y modificación de elementos

Los elementos de un array se pueden acceder y modificar utilizando su índice:

```javascript
const colores = ['rojo', 'verde', 'azul'];
console.log(colores[0]); // 'rojo'
colores[1] = 'amarillo';
```

## Métodos comunes de arrays

JavaScript proporciona varios métodos útiles para trabajar con arrays:

### Añadir y eliminar elementos

- `push()`: Añade uno o más elementos al final del array.
- `pop()`: Elimina el último elemento del array.
- `unshift()`: Añade uno o más elementos al inicio del array.
- `shift()`: Elimina el primer elemento del array.

### Buscar y filtrar

- `indexOf()`: Encuentra el índice de un elemento en el array.
- `filter()`: Crea un nuevo array con todos los elementos que pasan una prueba.

### Transformación

- `map()`: Crea un nuevo array con los resultados de llamar a una función para cada elemento.
- `reduce()`: Reduce el array a un solo valor aplicando una función acumuladora.

### Iteración

- `forEach()`: Ejecuta una función para cada elemento del array.

## Propiedades importantes

- `length`: Devuelve el número de elementos en el array.

## Ejemplo práctico

```javascript
const numeros = [1, 2, 3, 4, 5];
const duplicados = numeros.map(num => num * 2);
console.log(duplicados); // [2, 4, 6, 8, 10]

const pares = numeros.filter(num => num % 2 === 0);
console.log(pares); // [2, 4]

const suma = numeros.reduce((acc, num) => acc + num, 0);
console.log(suma); // 15
```

Los arrays son estructuras de datos fundamentales en JavaScript, ofreciendo una gran flexibilidad para almacenar y manipular colecciones de elementos de manera eficiente.

## Lecturas adicionales

- [Array](https://developer.mozilla.org/es/docs/Web/JavaScript/Reference/Global_Objects/Array)
