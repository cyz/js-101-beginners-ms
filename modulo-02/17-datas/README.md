# Fechas

Las fechas pueden ser un poco complicadas de manejar en el código. A menudo, se necesita realizar operaciones matemáticas, manejar conversiones y otras operaciones. JavaScript proporciona un objeto `Date` para dar acceso a fechas y horas.

## Creación de objetos Date

Hay varias formas de crear un objeto Date en JavaScript:

1. Fecha y hora actual:
   ```javascript
   const ahora = new Date();
   ```

2. Fecha específica:
   ```javascript
   const fechaEspecifica = new Date("2025-01-15T22:00:00-03:00");
   ```

3. Componentes individuales:
   ```javascript
   const fecha = new Date(2025, 0, 15, 22, 0, 0); // Año, mes (0-11), día, hora, minuto, segundo
   ```

## Métodos útiles

El objeto Date proporciona varios métodos para trabajar con fechas:

- `getFullYear()`: Obtiene el año (4 dígitos)
- `getMonth()`: Obtiene el mes (0-11)
- `getDate()`: Obtiene el día del mes (1-31)
- `getHours()`, `getMinutes()`, `getSeconds()`: Obtienen la hora, minutos y segundos

## Operaciones con fechas

Puedes realizar operaciones matemáticas con fechas:

```javascript
const fecha1 = new Date("2025-01-15");
const fecha2 = new Date("2025-01-20");
const diferencia = fecha2 - fecha1; // Diferencia en milisegundos
const diasDiferencia = diferencia / (1000 * 60 * 60 * 24); // Convertir a días
```

## Formateo de fechas

Para formatear fechas, puedes usar métodos como `toLocaleDateString()`:

```javascript
const fecha = new Date("2025-01-15");
console.log(fecha.toLocaleDateString("es-MX")); // Formato: 15/1/2025
```

Es importante tener en cuenta que el objeto Date trabaja con la zona horaria local del sistema por defecto. Para trabajar con UTC o zonas horarias específicas, se pueden usar métodos como `getUTCFullYear()` o considerar el uso de bibliotecas especializadas para un manejo más robusto de fechas y zonas horarias.

## Lecturas adicionales

- [Date](https://developer.mozilla.org/es/docs/Web/JavaScript/Reference/Global_Objects/Date)
