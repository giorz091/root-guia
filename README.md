# Root — Guía de Mesa

Guía interactiva en español del juego de mesa **Root** y de la expansión
**Los Ribereños**. Pensada para tenerla abierta **durante la partida**, en
un portátil o una tablet, y para que la use **cualquier jugador**: cada
facción tiene su propia pestaña y las herramientas de mesa son comunes.

**→ https://giorz091.github.io/root-guia/**

## Qué trae

| | |
|---|---|
| **Preparar** | Selector de jugadores, calculadora de **alcance** en vivo, mezclas válidas calculadas y **lista de montaje generada** para las facciones elegidas, con casillas que se guardan |
| **Mesa** | Marcador, calculadora de **quién gobierna** un claro, **resolutor de combate** (tope por guerreros, indefenso, Guerra de Guerrillas) y seguimiento de turno y fase |
| **6 facciones** | Marquesa de los Gatos · Dinastías de las Águilas · Alianza del Bosque · Vagabundo (6 personajes) · **Culto Reptiliano** · **Compañía del Río** |
| **Marquesa Mecánica** | El autómata: competitivo, cooperativo, solitario y campaña |
| **Reglas base** | Gobernar, mover, fabricar, cartas, dominio, piezas, mapa |
| **Combate** | Los tres pasos y las peculiaridades de cada facción |
| **Chuletario** | Turno de las seis facciones, todas las vías de puntos y los diez errores habituales |
| **Dudas** | 18 preguntas de reglas |

Además: buscador global con resaltado, modo de texto grande para la mesa,
tema oscuro, responsive e imprimible.

## Cómo está hecho

Un solo archivo, `index.html`. Sin dependencias, sin CDN y sin build: los
iconos son SVG en línea y el estado se guarda en `localStorage`. Funciona
**sin conexión**, que es lo que hace falta en una mesa.

`guia.html` es una redirección a `index.html`, para no romper los enlaces
antiguos.

## Fuentes

Las reglas vienen del reglamento oficial: *The Law of Root* (juego base) y
*Learning to Play — The Riverfolk Expansion* (Leder Games).

Donde un dato está **impreso en un tablero de facción** y no en el
reglamento —los puntos de los tracks de la Marquesa, las Águilas y la
Alianza— la guía dice **qué espacio mirar** en vez de dar un número que
podría estar mal.
