# Código Asíncrono

El desarrollo de aplicaciones modernas implica la comunicación con otros sistemas. Estas comunicaciones pueden llevar tiempo y podrían hacer que tu aplicación se detenga y no pueda realizar otras operaciones.

JavaScript es capaz de manejar operaciones de larga duración mediante el uso de promesas. Una promesa es similar a un [IOU](https://es.wikipedia.org/wiki/IOU); el código promete que te avisará cuando se complete y ejecutará la función proporcionada. Puedes usar promesas directamente para especificar cómo quieres que tu código responda cuando una llamada a un sistema remoto regrese.

Recientemente, ha surgido un nuevo patrón. Basado en promesas, `async`/`await` te permite crear código que parece síncrono, pero es asíncrono. Esto ayuda a hacer el código más legible al mismo tiempo que permite un mejor rendimiento.

## Promesas

Las promesas representan un valor que puede no estar disponible inmediatamente. Tienen tres estados posibles: pendiente, cumplida o rechazada.

```javascript
const miPromesa = new Promise((resolve, reject) => {
  // Operación asíncrona
  setTimeout(() => {
    resolve("Éxito");
    // o
    // reject("Error");
  }, 1000);
});

miPromesa
  .then(resultado => console.log(resultado))
  .catch(error => console.error(error));
```

## async/await

`async`/`await` es una sintaxis más limpia para trabajar con código basado en promesas:

```javascript
async function miFuncionAsincrona() {
  try {
    const resultado = await miPromesa;
    console.log(resultado);
  } catch (error) {
    console.error(error);
  }
}

miFuncionAsincrona();
```

El uso de `async`/`await` hace que el código asíncrono se lea y se comporte de manera más similar al código síncrono, lo que facilita su comprensión y mantenimiento.

## Lecturas adicionales

- [Promise](https://developer.mozilla.org/es/docs/Web/JavaScript/Reference/Global_Objects/Promise)
- [async](https://developer.mozilla.org/es/docs/Web/JavaScript/Reference/Statements/async_function)
- [await](https://developer.mozilla.org/es/docs/Web/JavaScript/Reference/Operators/await)
