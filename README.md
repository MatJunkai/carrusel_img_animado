# Galería de imágenes

Proyecto web de una galería interactiva dedicada a criaturas y personajes del
folclore japonés. Las imágenes aparecen como tarjetas comprimidas y se amplían
al seleccionarlas para mostrar su descripción.

## Cómo funciona

- En escritorio, las tarjetas se muestran en una fila. Al hacer clic en una,
  esta se ensancha y aparece el texto asociado.
- Solo puede haber una tarjeta activa a la vez: al seleccionar otra, la anterior
  vuelve a su tamaño inicial.
- En pantallas de hasta 768 px de ancho, las tarjetas se colocan en columna. La
  tarjeta seleccionada crece en altura en lugar de anchura.
- Algunas imágenes se cargan de forma diferida (`loading="lazy"`) para evitar
  cargar todas antes de que sean necesarias.

## Archivos del proyecto

- `root/galeria.html`: estructura de la página, imágenes y descripciones.
- `css/style.css`: estilos de la galería, animaciones y diseño adaptable.
- `js/script.js`: interacción de clic que activa una tarjeta y desactiva las demás.
- `img/`: imágenes utilizadas en la galería.

## Cómo abrirla

Abre `root/galeria.html` desde un servidor web que tenga la carpeta del proyecto
como raíz. La página utiliza rutas como `/css/style.css`, `/js/script.js` y
`/img/...`, por lo que abrir el HTML directamente desde el explorador de archivos
puede impedir que esas rutas se resuelvan correctamente.

No se necesitan bibliotecas externas: la galería está hecha con HTML, CSS y
JavaScript.