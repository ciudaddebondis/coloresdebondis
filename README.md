# @ciudaddebondis/colores

Colores de las líneas de colectivo de Ciudad de Bondis, publicados como paquete npm.

## Instalación

```bash
npm install @ciudaddebondis/colores
```

## Uso

```js
const colores = require('@ciudaddebondis/colores');
// [
//   { "slug": "122", "name": "Línea 122",
//     "color_main": "#...", "color_accent_1": "#...",
//     "color_accent_2": "#...", "color_txt": "#..." },
//   ...
// ]
```

## ¿Qué criterio se usa para actualizar los colores?

La actualización de los colores se va haciendo desde nuestro lado, ya que son exportadas desde un panel admin y de allí se vuelcan al archivo colors.json

Por lo tanto, si querés sugerirnos cambiar algunos colores, podés crear un issue e indicarnoslo.
Intentaremos dar los créditos correspondientes en el commit.

## Atribución (obligatoria)

Licencia **CC BY 4.0**. Cualquier proyecto que use este asset debe mencionarlo:

> Colors by "Ciudad de Bondis" (ciudaddebondis) - https://github.com/ciudaddebondis/coloresdebondis - Licencia CC BY 4.0.
