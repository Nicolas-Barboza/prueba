# prueba# Practica Angular

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
npm start
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

Pueden pegar las imagenes del trabajo en una carpeta como `docs/imagenes/` y luego referenciarlas aca.

Ejemplo:

```md
![Vista Punto 1](docs/imagenes/punto1.png)
![Vista Punto 2](docs/imagenes/punto2.png)
![Vista Punto 3](docs/imagenes/punto3.png)
```

Plantilla lista para completar:

### Punto 1

![Captura Punto 1](docs/imagenes/punto1.png)

### Punto 2

![Captura Punto 2](docs/imagenes/punto2.png)

### Punto 3

![Captura Punto 3](docs/imagenes/punto3.png)

## Notas

- El proyecto usa componentes y servicios separados para mantener la logica organizada.
- Bootstrap se carga desde `angular.json`.
- Los assets locales se publican desde `src/assets`.
