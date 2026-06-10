# Chakras — SVG vectoriales

Símbolos de los 7 chakras dibujados a partir de la referencia `assets/chakars.png`,
en la paleta terrosa de Círculo Dorado.

## Archivos

Cada chakra viene en dos versiones:

- `0N-nombre.svg` — con su tono terroso fijo
- `0N-nombre-currentcolor.svg` — usa `currentColor`: hereda el color del CSS
  donde se inserte (ideal para cambiar de color sin editar el archivo)

| # | Chakra | Tono terroso |
|---|---|---|
| 01 | Muladhara | `#9C5542` terracota |
| 02 | Svadhisthana | `#BA7A3F` naranja tierra |
| 03 | Manipura | `#B5953B` ocre |
| 04 | Anahata | `#7C8A57` verde salvia |
| 05 | Vishuddha | `#5F808C` azul petróleo |
| 06 | Ajna | `#6A6386` índigo apagado |
| 07 | Sahasrara | `#82627E` ciruela apagado |

## Uso

- **Web:** `<img src="assets/chakras/01-muladhara.svg" width="40">` o inline para animar
- **Illustrator / Figma:** abrir o arrastrar el archivo directamente
- **Cambiar color (versión currentcolor):** `color: #A8821A;` en el elemento contenedor
- **Cambiar grosor de línea:** editar `stroke-width` (1 = fino; el viewBox es 40×40)
- **Animación:** cada pétalo y figura es un `<path>` separado — se pueden animar
  con `stroke-dashoffset` (efecto "se dibuja"), rotación, opacidad, etc.

Escalan a cualquier tamaño sin perder calidad (vector puro).
