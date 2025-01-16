# Tipos de Datos

JavaScript es un lenguaje de [tipado débil](https://es.wikipedia.org/wiki/Tipado_fuerte_y_d%C3%A9bil), lo que significa que no almacena el tipo de datos mientras escribes tu código. Sin embargo, soporta varios tipos de datos y mantiene el tipo de datos que una variable está almacenando en tiempo de ejecución. Incluso puedes consultar una variable para determinar su tipo de datos.

## Tipos de datos primitivos

JavaScript tiene siete tipos de datos primitivos:

1. **String**: Representa texto. Se define entre comillas simples, dobles o backticks.
   Ejemplo: `"Hola, mundo!"`, `'JavaScript'`, ``` `Plantilla literal` ```

2. **Number**: Representa valores numéricos, incluyendo enteros y números de punto flotante.
   Ejemplo: `42`, `3.14`, `NaN`, `Infinity`

3. **Boolean**: Representa un valor lógico verdadero o falso.
   Ejemplo: `true`, `false`

4. **Undefined**: Representa una variable que ha sido declarada pero no ha recibido un valor.
   Ejemplo: `let x;` // x es undefined

5. **Null**: Representa la ausencia intencional de cualquier valor u objeto.
   Ejemplo: `let y = null;`

6. **Symbol**: Representa un identificador único e inmutable.
   Ejemplo: `const id = Symbol('id');`

7. **BigInt**: Representa números enteros de precisión arbitraria.
   Ejemplo: `9007199254740991n`

## Tipo de dato complejo

Además de los tipos primitivos, JavaScript tiene un tipo de dato complejo:

8. **Object**: Representa una colección de datos relacionados y/o funcionalidades.
   Ejemplo: `{nombre: "Juan", edad: 30}`

   Los arrays y las funciones también se consideran objetos en JavaScript.

## Verificación de tipos de datos

Para verificar el tipo de una variable en JavaScript, puedes usar el operador `typeof`. Por ejemplo:

```javascript
let nombre = "Alice";
console.log(typeof nombre); // "string"

let edad = 25;
console.log(typeof edad); // "number"

let activo = true;
console.log(typeof activo); // "boolean"

let persona = {nombre: "Bob", edad: 30};
console.log(typeof persona); // "object"
```

Es importante notar que `typeof null` devuelve `"object"`, lo cual se considera un error histórico en el lenguaje.

## Conversión de tipos

JavaScript realiza conversiones de tipos automáticamente en muchas operaciones. Esto puede llevar a resultados inesperados si no se maneja adecuadamente:

```javascript
console.log("5" + 3); // "53" (string)
console.log("5" - 3); // 2 (number)
```

Por esta razón, es crucial estar consciente de los tipos de datos al manipular variables en JavaScript para evitar comportamientos no deseados en tu código.

## Lecturas adicionales

- [typeof (MDN)](https://developer.mozilla.org/es/docs/Web/JavaScript/Reference/Operators/typeof)
- [Tipos de datos y estructuras en JavaScript (MDN)](https://developer.mozilla.org/es/docs/Web/JavaScript/Data_structures)
