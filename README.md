# Crianbluff-Animate

Es una libreria de animaciones empaquetadas en mixin de Sass. Insipirada en animate.css.
## Características de EDboilerplate:

* Usa gulp para automatizar tareas
* Esta basado en Sass, Pug y ES6.
* Compila Sass con autoprefixer y muestra los cambios en tiempo real
* Compila Pug y actualiza el navegador con cada cambio
* Compila ES6 con soporte para módulos ES6 (importar y exportar modulos)
* Detecta nuevos archivos añadidos al proyecto sin tener que reiniciar gulp
* Captura errores en Sass, Pug y Js evitando que gulp se detenga.
* Crea los sourcemaps de los archivos compilados
* Tiene una estructura lista de estilos (con Sass) basada en SMACSS y ITCSS
* Tiene una estructura lista para HTML (con Pug) que divide páginas e includes.
* Tiene una estructura lista para importar y exportar modulos ES6

## ¿Como usuarlo?

Puedes usar Crianbluff-Animate con css o con sass (recomendable).

## Con CSS
Descarga el archivo `public/css/crianbluff-animate.css` e incluyelo en tu proyecto.
Luego puedes agregar las siguientes clases a los elementos que deseas que se animen:
```language-css
.fadein o fade-in
.fadeout o fade-out
.slideleft o slide-left
.slideright o slide-right
.slidetop o slide-top
.slidebottom o slide-bottom
.slidedown o slide-down
.slideup o slide-up
.zoomin o zoom-in
.zoomout o zoom-out
.bounceleft o bounce-left
.bounceright o bounce-right
.bouncetop o bounce-top
.bouncebottom o bounce-bottom
.animatedborders o animated-borders
```

## Con SASS
* Instale Crianbluff-Animate con el comando `npm install --save-dev Crianbluff-Animate`
* Establezca la variable `$CrianbluffAnimateHelpers: false` parar compilar solo lo necesario (debe hacerlo antes de importar Crianbluff-Animate).
* Importe `crianbluff-animate/crianbluff-animate` en su proyecto.
* Los mixins disponibles son:
```language-scss
fadeIn($time)
fadeOut($time)
slideLeft($time)
slideRight($time)
slideTop($time)
slideBottom($time)
slideDown($time, $height)
slideUp($time, $height)
zoomIn($time)
zoomOut($time)
bounceLeft($time)
bounceRight($time)
bounceTop($time)
bounceBottom($time)
animatedBorders($time, $color)
```