<div align="center">

# Galería de imágenes

**Un recorrido interactivo por las criaturas del folclore japonés.**

Las imágenes se despliegan como tarjetas: selecciona una para descubrirla.

![HTML](https://img.shields.io/badge/HTML-estructura-e34f26?style=flat-square&logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS-animaciones-1572b6?style=flat-square&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-interacci%C3%B3n-f7df1e?style=flat-square&logo=javascript&logoColor=222)
![Diseño adaptable](https://img.shields.io/badge/dise%C3%B1o-adaptable-218c74?style=flat-square)

<img src="img/jorogumo-spider-woman-folklore.webp" alt="Ilustración de Jorogumo, la mujer araña del folclore japonés" width="800">

</div>

## Explora

| Interacción | En escritorio | En móvil |
| --- | --- | --- |
| Haz clic en una tarjeta para ampliarla y mostrar su descripción. | Las tarjetas se alinean en una fila y la seleccionada se ensancha. | Hasta 768 px, se apilan y la seleccionada crece en altura. |

Solo una tarjeta permanece activa a la vez. Las imágenes secundarias usan carga diferida para ayudar a reducir la carga inicial.

La galería reúne Jorogumo, Kappa, Rokurokubi, Tengu y Tsuchinoko, además de una imagen decorativa.

## Ponla en marcha

Desde la carpeta del proyecto, inicia un servidor local:

```powershell
python -m http.server 8000
```

Abre [http://localhost:8000/root/galeria.html](http://localhost:8000/root/galeria.html) en el navegador. También puedes abrir `root/galeria.html` con una extensión de servidor local de VS Code.

> Las rutas de recursos empiezan desde la raíz (`/css`, `/js` y `/img`), así que la página debe servirse desde la carpeta del proyecto; abrir el archivo directamente puede dejar las imágenes y estilos sin cargar.

## Dentro del proyecto

| Ruta | Contenido |
| --- | --- |
| `root/galeria.html` | Estructura, imágenes y descripciones de las tarjetas. |
| `css/style.css` | Estilos, transiciones y diseño adaptable. |
| `js/script.js` | Selección de una tarjeta y cierre de las demás. |
| `img/` | Imágenes de la galería. |

Hecha con **HTML, CSS y JavaScript**, sin bibliotecas externas.
