# Comentarios

Los **comentarios** te permiten dejar notas sobre lo que tu código está haciendo. También son una herramienta poderosa para hacer anotaciones, lo cual es maravilloso para aprender el código.

En JavaScript, hay tres tipos principales de comentarios:

## Comentarios de una línea

Se utilizan para comentarios breves y comienzan con `//`. Todo lo que sigue en esa línea se considera un comentario.

```javascript
// Este es un comentario de una línea
console.log("Hola mundo"); // También puedes poner comentarios al final de una línea de código
```

## Comentarios de bloque

Son útiles para comentarios más largos y se delimitan con `/*` y `*/`. Pueden abarcar múltiples líneas.

```javascript
/* Este es un comentario
   de bloque que puede
   abarcar múltiples líneas */
console.log("Hola mundo");
```

## Comentarios hashbang

Son un tipo especial de comentario que comienza con `#!` y solo es válido al inicio absoluto de un script o módulo. Se utilizan principalmente en entornos no navegador como Node.js.

```javascript
#!/usr/bin/env node
console.log("Hola mundo");
```

Los comentarios son ignorados por el intérprete de JavaScript y no afectan la ejecución del código. Son extremadamente útiles para:

- Explicar el propósito y la lógica del código
- Desactivar temporalmente partes del código durante el desarrollo
- Agregar notas para futuros desarrolladores (incluyéndote a ti mismo)
- Generar documentación automática del código

## Lecturas adicionales

- [Comentarios en MDN](https://developer.mozilla.org/es/docs/Web/JavaScript/Reference/Lexical_grammar#comentarios)
