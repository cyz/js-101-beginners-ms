# Objetos y JSON

Los objetos permiten crear tipos de datos complejos. Debido a la flexibilidad de JavaScript, puedes crearlos rápidamente mediante la notación de objetos JavaScript o JSON (JavaScript Object Notation).

## Objetos en JavaScript

Los objetos son colecciones de pares clave-valor que pueden contener propiedades y métodos. Se pueden crear de dos formas principales:

1. Usando la notación literal de objeto:

```javascript
const persona = {
  nombre: "Juan",
  edad: 30,
  saludar() {
    console.log(`Hola, soy ${this.nombre}`);
  }
};
```

2. Usando el constructor Object():

```javascript
const coche = new Object();
coche.marca = "Toyota";
coche.modelo = "Corolla";
```

## JSON (JavaScript Object Notation)

JSON es un formato ligero de intercambio de datos, basado en la sintaxis de objetos de JavaScript, pero independiente del lenguaje. Características principales:

- Formato de texto plano, fácil de leer y escribir para humanos y máquinas.
- Se utiliza comúnmente para transmitir datos en aplicaciones web.
- Soporta tipos de datos como strings, números, booleanos, null, arrays y objetos.

Ejemplo de objeto JSON:

```json
{
  "nombre": "María",
  "edad": 28,
  "ciudad": "Madrid",
  "hobbies": ["lectura", "viajes", "fotografía"]
}
```

## Trabajando con JSON en JavaScript

JavaScript proporciona métodos nativos para trabajar con JSON:

1. JSON.parse(): Convierte una cadena JSON en un objeto JavaScript.

```javascript
const jsonString = '{"nombre": "Pedro", "edad": 35}';
const objeto = JSON.parse(jsonString);
console.log(objeto.nombre); // "Pedro"
```

2. JSON.stringify(): Convierte un objeto JavaScript en una cadena JSON.

```javascript
const objeto = { nombre: "Ana", edad: 27 };
const jsonString = JSON.stringify(objeto);
console.log(jsonString); // '{"nombre":"Ana","edad":27}'
```

Es importante tener en cuenta que JSON tiene algunas diferencias con los objetos JavaScript regulares:

- Las claves en JSON deben ser strings con comillas dobles.
- JSON no admite comentarios ni funciones.
- JSON es más estricto en cuanto a la sintaxis (por ejemplo, no permite comas finales en arrays u objetos).

El uso de objetos y JSON es fundamental en el desarrollo web moderno, especialmente en la comunicación entre cliente y servidor en aplicaciones AJAX y APIs RESTful.

## Lecturas adicionales

- [Objetos](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object)
- [JSON](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/JSON)
