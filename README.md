# ClassConnect - Manual de Usuario

Manual de usuario del trabajo práctico grupal ClassConnect de la materia [Ingeniería de Software II](https://ingenieria-del-software-2.github.io/) (TA049), curso Rojas. Desarrollado con:

- [Jekyll](https://jekyllrb.com/)
- [Just the Docs](https://just-the-docs.github.io/just-the-docs/) theme
- [GitHub Pages](https://pages.github.com/)

## Ejecución (modo desarrollo)

### Requisitos previos

Asegúrate de tener instalado:

- [Ruby](https://www.ruby-lang.org/es/) (versión 2.7 o superior)
- [Jekyll](https://jekyllrb.com/docs/installation/)
- [Bundler](https://bundler.io/)

### Pasos para ejecutar

1. Instalar las dependencias necesarias:

   ```bash
   bundle install
   ```

2. Iniciar el servidor de desarrollo:

   ```bash
   bundle exec jekyll serve
   ```

3. Abrir el navegador y navegar a: `http://localhost:4000`

El sitio se construirá automáticamente y se guardará en el directorio `_site`.

## Estructura del Manual

El manual está organizado con la siguiente estructura de carpetas y archivos:

### Carpetas Principales

- `admin/` - Documentación para administradores del sistema
- `user/` - Documentación para usuarios (estudiantes, docentes, asistentes)
- `assets/` - Imágenes y recursos multimedia organizados por sección
- `_includes/` - Componentes reutilizables de Jekyll
- `_site/` - Sitio web generado (no editar manualmente)
- `vendor/` - Dependencias de Ruby/Jekyll

### Archivos de Configuración

- `_config.yml` - Configuración principal de Jekyll
- `Gemfile` - Dependencias de Ruby
- `Gemfile.lock` - Versiones específicas de dependencias
- `index.md` - Página principal del manual
- `README.md` - Este archivo de documentación
- `LICENSE` - Licencia del proyecto
