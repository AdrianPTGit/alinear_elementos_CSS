# Maquetación en CSS

## 1. Propiedad `display`

- Por defecto todos los elementos HTML tienen una forma de comportarse a la hora de renderizarse en el navegador.
- Elementos HTML como `<div>` o `<p>` Actuan de forma distinta a `<a>` o `<span>`.
- Aunque no lo indiquemos de forma explicita todos los elemenntos HTML tienen una forma de representarse. Esta forma puede cambiarse mediante la propiedad `display`

| Propiedad | Valores    | Descripción                                           |
|-----------|------------|-------------------------------------------------------|
| display   | `none`, `block`, `inline`, `flex`, `grid`, etc. | Cambia el tipo o forma de representación del elemento. |

### tipos de representación que existen en CSS:

| Tipo         | Descripción                                                                                  | Más info              |
|--------------|----------------------------------------------------------------------------------------------|------------------------|
| `inline`       | Se coloca a continuación del otro (en horizontal). Ignora dimensiones.                       |                        |
| `block`        | Se coloca encima de otro (en vertical).                                                      |                        |
| `inline-block` | Híbrido en línea-bloque. Actúa como un elemento en línea, pero obedece dimensiones.          |                        |
| `flex`         | Utiliza el modelo de cajas flexibles de CSS. Ideal para estructuras de 1 dimensión.         | Ver Flex CSS           |
| `inline-flex`  | Versión en línea (ocupa sólo su contenido) del modelo de cajas flexibles de CSS.            |                        |
| `grid`         | Utiliza cuadrículas o rejillas con el modelo de cajas Grid CSS.                             | Ver Grid CSS           |
| `inline-grid`  | La versión en línea (ocupa sólo su contenido) del modelo de cajas Grid CSS.                 |                        |
| `list-item`    | Actúa como un ítem de una lista. Es el comportamiento de etiquetas como `<li>`.             | Ver listas HTML        |
| `table`        | Actúa como una tabla. Es el comportamiento de etiquetas como `<table>`.                     | Ver tablas HTML        |
| `table-cell`   | Actúa como la celda de una tabla. Es el comportamiento de etiquetas como `<th>` o `<td>`.   |                        |
| `table-row`    | Actúa como la fila de una tabla. Es el comportamiento de etiquetas como `<tr>`.             |                        |
| `contents`     | Ignora la caja del elemento. Útil para mantener Grid/Flex aún teniendo un wrapper intermedio.| Ver contents           |
| `none`         | No dibuja en el navegador el contenido del elemento ni sus hijos.                           | Ver visibilidad        |

## `inline`

- Elementos que se utilizan dentro de un párrafo, son de tipo `inline`.

  - 1️⃣ Los elementos se alinean uno detrás de otro **(en horizontal).**
  - 2️⃣ Su tamaño o dimensiones se adaptan al de su contenido.
  - 3️⃣ Aunque uses width o height, se ignora y no cambia tamaño.

- Elementos `<span>` o `<strong>` se comportan como elementos en línea **(inline)**, mientras que los elementos `<div>` por defecto se comportan como elementos en bloque.
- Los elementos `<div>` se comportan como si tuvieran un `display: block`.
- los elementos `<span>` se comportan como si tuvieran un `display: inline`.

## `block`

- Los elementos que se utilizan para agrupar otros elementos HTML, por norma general, son de tipo `block`.
  - 1️⃣ Los elementos se apilan uno encima de otro **(en vertical).**
  - 2️⃣ Por defecto, usa todo el ancho **(en horizontal)** disponible.
  - 3️⃣ Si usas `width` o `height`, obedece y cambia el tamaño del elemento.
  
- Todos los elementos `<div>` se comportan como elementos de bloque `block`.

