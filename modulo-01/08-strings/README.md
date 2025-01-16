# Strings

Las strings en JavaScript son colecciones de cero o más caracteres. Trabajar con strings es una de las habilidades básicas que todas las Personas Desarrolladoras necesitan saber. Afortunadamente, JavaScript proporciona varias formas de manipular y trabajar con strings.

## Creación de Strings

Existen tres formas principales de crear strings en JavaScript:

1. Comillas simples: `'Hola, mundo!'`
2. Comillas dobles: `"Hola, mundo!"`
3. Template literals: ```Hola, mundo!```

Los template literals, introducidos en ECMAScript 6, ofrecen funcionalidades adicionales como interpolación de strings y strings multilínea.

## Manipulación de Strings

JavaScript proporciona varios métodos para manipular strings:

- `length`: Devuelve la longitud de la string.
- `slice()`: Extrae una parte de la string.
- `substring()`: Similar a `slice()`, pero trata los valores negativos como 0.
- `substr()`: Extrae una parte de la string, especificando la longitud.
- `replace()`: Reemplaza una parte de la string por otra.
- `toUpperCase()` y `toLowerCase()`: Convierten la string a mayúsculas o minúsculas.
- `trim()`: Elimina los espacios en blanco del principio y final de la string.

## Template Literals

Los template literals ofrecen una sintaxis más flexible para crear strings:

```javascript
const nombre = 'Juan';
const saludo = `Hola, ${nombre}!`;
console.log(saludo); // Salida: Hola, Juan!
```

Permiten la interpolación de expresiones y la creación de strings multilínea de forma más sencilla.

## Lecturas adicionales

- [String](https://developer.mozilla.org/es/docs/Web/JavaScript/Reference/Global_Objects/String)
- [Template literals](https://developer.mozilla.org/es/docs/Web/JavaScript/Reference/Template_literals)
