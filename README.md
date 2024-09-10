# Información de Vuelos con Cuenta Regresiva

Este proyecto es una página web simple que muestra la información de vuelos para dos grupos de personas (desde Málaga y Madrid) con tablas organizadas y una cuenta regresiva dinámica hasta la salida del primer vuelo.

## Características

- **Tablas de vuelos**: La información de los vuelos se muestra claramente usando tablas, organizadas por origen (Málaga y Madrid).
- **Cuenta regresiva**: Una cuenta atrás en tiempo real que muestra cuánto falta para el vuelo de salida desde Málaga (27 de septiembre a las 07:00).
  
## Cómo usar

1. Descarga o clona este repositorio.
2. Abre el archivo `index.html` en cualquier navegador web para visualizar la tabla y la cuenta regresiva.
  
## Estructura del Proyecto

- `index.html`: Página principal que contiene el código HTML y JavaScript para mostrar las tablas de vuelos y la cuenta regresiva.
- `README.md`: Documento que describe el propósito y la funcionalidad del proyecto.

## Personalización

### Actualización de datos de vuelos:
Si necesitas actualizar la información de los vuelos:
1. Abre el archivo `index.html`.
2. Busca las secciones correspondientes dentro de las tablas para cambiar las fechas, horas y número de vuelos.

### Cambio en la fecha del vuelo para la cuenta regresiva:
Para cambiar la fecha de salida del vuelo que usa la cuenta regresiva:
1. Abre el archivo `index.html`.
2. Busca la sección de JavaScript en el archivo (a partir de la línea 78).
3. Modifica la variable `vueloFecha` con la nueva fecha y hora del vuelo:

```javascript
var vueloFecha = new Date("Sept 27, 2024 07:00:00").getTime();
