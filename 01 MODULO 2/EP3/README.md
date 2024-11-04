# Nursing Hospital - Proyecto Web

Este proyecto es una página web para Nursing Hospital, diseñada para ser responsiva, modular y de fácil mantenimiento. Utiliza Sass con el patrón 7-1, metodología BEM para la estructura de clases y Bootstrap para una base de diseño rápido y eficiente.

## Estructura de Sass y Modularización

La estructura de los archivos Sass sigue el patrón 7-1, una metodología que organiza los estilos en diferentes directorios y archivos parciales para mejorar la organización y facilitar el mantenimiento. La estructura principal del sitio es la siguiente:

sass/
|
|– base/
|   |– _typography.scss       
|
|– components/
|   |– _buttons.scss           
|
|– layout/
|   |– _grid.scss              
|   |– _header.scss           
|   |– _footer.scss            
|
|– pages/
|   |– _index.scss            
|   |– _contacto.scss         
|   |– _equipo.scss            
|
|– utils/
|   |– _mixins.scss            
|
|– vendors/
|   |– _jquery.scss            
|
`– main.scss                   

### Uso de Mixins

Se integró un mixin llamado `title` en `_mixins.scss` para estilizar de manera consistente varios títulos en el sitio web. El mixin establece una fuente y color específicos, aplicándose a selectores como `.quienes__title`, `.servicios__title`, etc. Esto facilita el mantenimiento de los estilos de título en una sola ubicación.

## Metodología BEM

La metodología BEM (Block Element Modifier) se emplea para mantener una estructura de clases clara y escalable. Cada componente tiene un bloque principal y elementos hijos, que ayudan a identificar el propósito de cada clase. Ejemplos de nombres de clases según BEM:

- `.header__logo`: Logo dentro del bloque de `header`.
- `.servicios__card`: Tarjeta dentro del bloque de `servicios`.
- `.testimonios__title`: Título dentro del bloque de `testimonios`.

Esta estructura facilita la comprensión de los elementos y mejora la escalabilidad del proyecto.

## Integración de Bootstrap

Bootstrap se integró para proporcionar una estructura de diseño rápida y responsiva. Los archivos de Bootstrap se importan desde el directorio `node_modules` y se complementaron con Sass para personalizar ciertos estilos y mantener una apariencia uniforme en todo el sitio. Además, se utilizaron componentes de Bootstrap como la barra de navegación y el carrusel, que fueron adaptados a las necesidades del proyecto.

## Visualización del Proyecto en un Navegador

Para ver el proyecto en un navegador:

1. Clonar el repositorio en tu computadora.
2. Asegurar de tener `node_modules` instalado. Ejecuta `npm install` si no lo tienes.
3. Compila los archivos Sass ejecutando un compilador de Sass (como `node-sass` o `sass`) para generar el CSS final en `assets/css/main.css`.
4. Abre el archivo `index.html` en tu navegador preferido para visualizar el proyecto.

## Recursos

- **Bootstrap**: [https://getbootstrap.com](https://getbootstrap.com)
- **Sass**: [https://sass-lang.com](https://sass-lang.com)
- **Metodología BEM**: [https://getbem.com](https://getbem.com)


