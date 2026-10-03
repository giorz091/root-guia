# Root — Guía de Mesa

Guía interactiva en español del juego de mesa **Root** y de la expansión
**Los Ribereños**. Pensada para tenerla abierta **durante la partida**, en
un portátil o una tablet, y para que la use **cualquier jugador**: cada
facción tiene su propia pestaña y las herramientas de mesa son comunes.

**→ https://giorz091.github.io/root-guia/**

## Qué trae

| | |
|---|---|
| **Preparar** | Ruta de 4 pasos para quien empieza, selector de jugadores, calculadora de **alcance** en vivo, mezclas válidas calculadas y **lista de montaje generada** para las facciones elegidas, con casillas que se guardan |
| **Mesa** | **Entrenador de turno** (te saca los pasos exactos de la facción que juega, en la fase en la que vais), marcador, calculadora de **quién gobierna**, **resolutor de combate** y seguimiento de turno |
| **Tablero** | Esquema interactivo de los **12 claros** del mapa de Otoño con cinco modos: palos, huecos de edificio, vecinos, **montaje** (te coloca la fortaleza, el nido en la diagonal y el Culto) y **dominio** |
| **6 facciones** | Marquesa de los Gatos · Dinastías de las Águilas · Alianza del Bosque · Vagabundo (6 personajes) · **Culto Reptiliano** · **Compañía del Río** |
| **Marquesa Mecánica** | El autómata: competitivo, cooperativo, solitario y campaña |
| **Reglas base** | Gobernar, mover, fabricar, cartas, dominio, piezas, mapa |
| **Combate** | Los tres pasos y las peculiaridades de cada facción |
| **Chuletario** | Turno de las seis facciones, todas las vías de puntos y los diez errores habituales |
| **Dudas** | 18 preguntas de reglas |

Más: **galería de las 16 piezas** del juego con icono y para qué sirve, y
**fotografías de una partida real** (tablero, tablero de la Marquesa y de
las Águilas).

Además: buscador global con resaltado, modo de texto grande para la mesa,
tema oscuro, responsive e imprimible.

## Cómo está hecho

`index.html` y cuatro fotos en `img/`. Sin dependencias, sin CDN y sin
build: los iconos, el mapa y los diagramas son **SVG en línea**, y el
estado se guarda en `localStorage`. Funciona **sin conexión**, que es lo
que hace falta en una mesa.

Los creditos y licencias de las imagenes estan en
[`img/CREDITOS.md`](img/CREDITOS.md).

`guia.html` es una redirección a `index.html`, para no romper los enlaces
antiguos.

## Fuentes

Las reglas vienen del reglamento oficial: *The Law of Root* (juego base) y
*Learning to Play — The Riverfolk Expansion* (Leder Games).

Donde un dato está **impreso en un tablero de facción** y no en el
reglamento, la guía dice **qué espacio mirar** en vez de dar un número que
podría estar mal. Así están los **puntos** de los tracks de la Marquesa,
las Águilas y la Alianza.

Sí llevan número los verificados: los **costes de madera** de la Marquesa
(0·1·2·3·3·4, leídos de la foto del tablero) y el **track de jardines**
del Culto. Del mapa, la guía da los **palos, huecos y caminos** —exactos—
y deja fuera el río, los bosques y las ruinas, que no pude verificar.
