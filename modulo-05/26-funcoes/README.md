# Funciones

Las funciones o métodos te permiten crear bloques de código reutilizables. El uso de funciones hace que tu código sea más modular y fácil de leer. No temas agregar funciones para dividir tu código en partes lógicas.

## Definición de funciones

En JavaScript, hay varias formas de definir funciones:

### Declaración de función

```javascript
function saludar(nombre) {
  return `Hola, ${nombre}!`;
}
```

### Expresión de función

```javascript
const saludar = function(nombre) {
  return `Hola, ${nombre}!`;
};
```

### Función flecha

```javascript
const saludar = (nombre) => `Hola, ${nombre}!`;
```

## Parámetros y argumentos

Las funciones pueden recibir parámetros y devolver valores:

```javascript
function sumar(a, b) {
  return a + b;
}

let resultado = sumar(3, 5); // resultado = 8
```

## Funciones como objetos de primera clase

En JavaScript, las funciones son objetos de primera clase, lo que significa que pueden:

- Asignarse a variables
- Pasarse como argumentos a otras funciones
- Devolverse desde otras funciones

```javascript
function ejecutar(fn, valor) {
  return fn(valor);
}

let duplicar = (x) => x * 2;
let resultado = ejecutar(duplicar, 5); // resultado = 10
```

## Ámbito y clausuras

Las funciones en JavaScript crean su propio ámbito, lo que permite la creación de clausuras:

```javascript
function crearContador() {
  let count = 0;
  return function() {
    return ++count;
  };
}

let contador = crearContador();
console.log(contador()); // 1
console.log(contador()); // 2
```

Las funciones son una parte fundamental de JavaScript y su uso adecuado puede mejorar significativamente la estructura y mantenibilidad de tu código.

## Lecturas adicionales

- [Functions](https://developer.mozilla.org/es/docs/Web/JavaScript/Reference/Functions)
