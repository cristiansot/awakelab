# Proyecto Nursing Hospital

## Descripción del Proyecto
Este proyecto es un sitio web para Nursing Hospital, diseñado para ofrecer información sobre los servicios médicos, el equipo médico y cómo contactar con el hospital. El enfoque está en la usabilidad y la estética, proporcionando una experiencia fluida y atractiva para los usuarios.

## Modularización de Estilos y Media Queries
Para mantener el código CSS limpio y manejable, implementé una **modularización de estilos** utilizando SASS. Cada componente del sitio (cabecera, secciones de contenido, formulario de contacto, pie de página) tiene su propio archivo parcial. Esto permite que los estilos se mantengan organizados y se puedan modificar fácilmente sin afectar otras partes del proyecto.

### Media Queries
Las **media queries** se utilizan para hacer que el diseño sea responsivo. He definido varias consultas para adaptar el diseño a diferentes tamaños de pantalla:
- **1024px**: Cambia el diseño de la sección de servicios a dos columnas.
- **768px**: Modifica el diseño de la cabecera y la barra de navegación para facilitar su uso en dispositivos móviles.
- **480px**: Adapta completamente el diseño a una sola columna para asegurar la legibilidad y la facilidad de uso en pantallas pequeñas.

## Estructura de SASS
La estructura de SASS está organizada en archivos parciales, donde cada archivo se encarga de una sección específica del diseño:

- **header.scss**: Estilos relacionados con la cabecera y la navegación.
- **index.scss**: Estilos para la página principal, incluyendo la sección de quiénes somos y servicios.
- **equipo.scss**: Estilos para la sección del equipo médico.
- **contacto.scss**: Estilos para la página de contacto, incluyendo el formulario.
- **footer.scss**: Estilos para el pie de página.

Los archivos se importan en un archivo principal (e.g., `main.scss`), lo que permite una compilación sencilla y efectiva.


