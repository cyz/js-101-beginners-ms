Cuando se aprende un nuevo lenguaje de programación, es tradicional comenzar con un programa "Hola, mundo". En Node.js, crear este programa es sencillo y directo. Aquí te muestro cómo hacerlo:

1. Crea un nuevo archivo llamado `hola_mundo.js` en tu editor de código favorito.

2. Escribe el siguiente código en el archivo:

```javascript
console.log("Hola, mundo!");
```

3. Guarda el archivo.

4. Abre una terminal o línea de comandos.

5. Navega hasta el directorio donde guardaste el archivo.

6. Ejecuta el programa con el siguiente comando:

```
node hola_mundo.js
```

7. Verás la salida "Hola, mundo!" en tu terminal.

Este simple programa demuestra cómo Node.js puede ejecutar código JavaScript fuera del navegador. El método `console.log()` es una función incorporada en Node.js que imprime texto en la consola.

Para expandir un poco más allá del "Hola, mundo" básico, podrías crear un pequeño servidor web:

```javascript
const http = require('http');

const servidor = http.createServer((req, res) => {
  res.statusCode = 200;
  res.setHeader('Content-Type', 'text/plain');
  res.end('Hola, mundo!');
});

servidor.listen(3000, 'localhost', () => {
  console.log('Servidor ejecutándose en http://localhost:3000/');
});
```

Este código crea un servidor HTTP que responde con "Hola, mundo!" cuando accedes a http://localhost:3000 en tu navegador.

Recuerda que Node.js es un entorno de ejecución de JavaScript del lado del servidor, lo que te permite utilizar JavaScript para crear aplicaciones de red escalables.
