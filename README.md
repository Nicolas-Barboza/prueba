# Practica Angular

Aplicacion desarrollada con Angular 21 y Bootstrap para la materia Programacion y Servicios Web. El proyecto esta organizado en tres vistas principales accesibles desde una barra de navegacion superior.

## Descripcion general

La aplicacion presenta tres ejercicios o secciones:

1. `Punto 1`: carrusel de eventos con navegacion manual, imagen destacada y descripcion.
2. `Punto 2`: catalogo de productos con carrito de compras, control de stock y calculo de total.
3. `Punto 3`: juego de memoria con intentos limitados, cartas emparejadas y estados de victoria o derrota.

## Tecnologias utilizadas

- Angular 21
- TypeScript
- Bootstrap 5
- Bootstrap Icons
- HTML y CSS
- Vitest para pruebas unitarias

## Estructura principal

```text
src/
  app/
    components/
      layout/
        navbar/
        footer/
      pages/
        punto1/
        punto2/
        punto3/
    models/
    services/
  assets/
    img/
      cartas/
      eventos/
      productos/
```

## Funcionalidades

### Punto 1 - Carrusel de eventos

- Muestra una coleccion de eventos cargados desde `EventoService`.
- Permite avanzar y retroceder entre eventos.
- Usa imagenes locales y un diseno visual tipo showcase.

### Punto 2 - Tienda con carrito

- Lista productos obtenidos desde `ProductoService`.
- Permite agregar productos al carrito.
- Actualiza cantidades desde un modal.
- Descuenta y repone stock en tiempo real.
- Calcula el total de la compra.

### Punto 3 - Juego de memoria

- Genera un tablero con pares de cartas mezcladas aleatoriamente.
- Controla intentos disponibles.
- Detecta aciertos y errores.
- Informa si el jugador gana o pierde.

## Instalacion y ejecucion

1. Instalar dependencias:

```bash
npm install
```

2. Levantar el servidor de desarrollo:

```bash
ng serve
```

3. Abrir en el navegador:

```text
http://localhost:4200
```

## Scripts disponibles

- `npm start`: inicia la aplicacion en modo desarrollo.
- `npm run build`: genera el build de produccion.
- `npm run watch`: recompila en modo desarrollo ante cambios.
- `npm test`: ejecuta las pruebas unitarias.

## Rutas de la aplicacion

- `/punto1`
- `/punto2`
- `/punto3`

La ruta inicial redirige automaticamente a `/punto1`.

## Recursos visuales

Las imagenes utilizadas por la aplicacion se encuentran en:

- `src/assets/img/eventos`
- `src/assets/img/productos`
- `src/assets/img/cartas`

## Capturas del proyecto

En esta seccion se pueden agregar capturas de pantalla de la web para mostrar la interfaz de cada punto.

### Punto 1

Pegar aqui la captura correspondiente al carrusel de eventos.

### Punto 2

Pegar aqui la captura correspondiente a la tienda con carrito.

### Punto 3

Pegar aqui la captura correspondiente al juego de memoria.

## Notas

- El proyecto usa componentes y servicios separados para mantener la logica organizada.
- Bootstrap se carga desde `angular.json`.
- Los assets locales se publican desde `src/assets`.
