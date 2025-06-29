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

- `index.md` - Página principal
- `admin/` - Documentación para administradores
- `user/` - Documentación para usuarios

## TODOs Pendientes

Los siguientes elementos están marcados con comentarios TODO en la documentación y requieren atención:

### Imágenes Faltantes

- Pantalla de creación de tareas
- Pantalla de edición de tareas  
- Pantalla de publicación de tareas
- Vista de actividades para estudiantes y docentes
- Interfaz de corrección automática con IA
- Barra de secciones del curso

### Funcionalidades Incompletas

- Sistema completo de exámenes (en desarrollo)
- Corrección automática de tareas con IA (documentación detallada)
- Sistema de notas y reseñas de alumnos

### Enlaces a Verificar

- Enlaces relativos entre secciones
- Navegación desde módulos a actividades
- Enlaces a notificaciones desde home

### Contenido a Expandir

- Descripción detallada de secciones del curso
- Información completa sobre el sistema de notificaciones
- Documentación de tipos de preguntas para exámenes

Para buscar todos los TODOs en el proyecto:

```bash
grep -r "TODO" --include="*.md" .
```
