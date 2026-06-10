# Chakras — SVG vectoriales

Dos sets de símbolos de los 7 chakras, en la paleta terrosa de Círculo Dorado.

## Sets

### `line/` — chakras-line
Dibujo geométrico de línea (trazo fino, formas que no se tocan — apto para
usar con opacidad sin que se generen manchas de superposición).
Cada chakra en dos versiones:

- `0N-nombre.svg` — con su tono terroso fijo
- `0N-nombre-currentcolor.svg` — usa `currentColor`: hereda el color del CSS

### `artsy/` — chakras-artsy
Diseño orgánico ondulado (extraído de `assets/chakras.svg`), recoloreado
a la paleta terrosa. Formas rellenas, un solo color por símbolo.

- `0N-nombre.svg` — color terroso pleno
- `0N-nombre-soft.svg` — con opacidad 0.4 baked-in (para fondos sutiles)

## Paleta terrosa

| # | Chakra | Tono |
|---|---|---|
| 01 | Muladhara | `#9C5542` terracota |
| 02 | Svadhisthana | `#BA7A3F` naranja tierra |
| 03 | Manipura | `#B5953B` ocre |
| 04 | Anahata | `#7C8A57` verde salvia |
| 05 | Vishuddha | `#5F808C` azul petróleo |
| 06 | Ajna | `#6A6386` índigo apagado |
| 07 | Sahasrara | `#82627E` ciruela apagado |

## Uso

- **Web:** `<img src="assets/chakras/artsy/01-muladhara.svg" width="40">` o inline para animar
- **Illustrator / Figma:** abrir o arrastrar el archivo directamente
- **Cambiar color (line currentcolor):** `color: #A8821A;` en el contenedor
- **Animación (line):** cada pétalo es un `<path>` separado — stroke-dashoffset
  (efecto "se dibuja"), rotación, opacidad, etc.

El sitio usa actualmente el set **artsy** (íconos del recorrido y fondos del programa).
Escalan a cualquier tamaño sin perder calidad (vector puro).
