# Trabajo práctico N°2:

- Flexbox
- Grids
- Media queries
- Modularización CSS (import url(...))

## Grupo 15
## Integrantes
- Andy Moore (andymoore01)
- Augusto Fedigatti (Agusfedredhunter)
- Joaquin Pelizza (joacopelizza)
- Jesus Lima (yss2805)
- Iñaki Urdampilleta (Iniakiur)
- Ramiro Morel (ramiromorel93-debug)

## Características de la entrega

Hemos integrado el diseño y maquetación de "Cine Aurora" cumpliendo con los siguientes requerimientos técnicos:

- **Responsive Web Design:** Aplicamos Media Queries para asegurar la correcta legibilidad de la grilla de películas en Desktop, Tablets y Dispositivos celulares.

- **CSS Architecture:** Se implementó el paradigma modular mediante el directorio `css/components` que divide botones, layouts, grillas de películas y variables de interfaz. Todos centralizados mediante el uso de `@import` en `style.css`.

- **Flexbox y CSS Grid:** Utilizados extensivamente en layouts de páginas, centrado de login (`display: flex`) y distribución repetible de tarjetas de películas (`display: grid; grid-template-columns: repeat(...)`).

- **Variables y theming:** Se configuró un entorno de variables nativas en CSS (`:root`) manejando la paleta "Cine Premium" con tonos Dark Mode.

- **Micro-interacciones:** Agregamos reglas de interactividad con `:hover` y transiciones en botones (`transform: translateY(-8px)`).

- **Semántica HTML:** Ajustamos las etiquetas base implementando clases mediante notación Kebab Case (`movie-card-title`, `main-nav`).
