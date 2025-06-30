---
title: Tareas
nav_order: 1
layout: default
parent: Actividades
grand_parent: Secciones del Curso
---

# Tareas

Las tareas son actividades que los estudiantes deben completar enviando un archivo a modo de entrega. Estas tareas pueden incluir ejercicios prácticos, proyectos o cualquier otro tipo de actividad que requiera la entrega de un archivo.

## Creación de una tarea

Para crear una tarea, el docente debe seguir estos pasos:

1. Ir a la sección **Actividades** del curso
2. Presionar el botón **Crear actividad** (con un símbolo "+")
3. Seleccionar la opción **Crear una nueva tarea**
4. Completar con los datos de la tarea:

   - **Nombre**: Nombre descriptivo de la tarea
   - **Instrucciones**: Instrucciones detalladas sobre lo que se espera en la entrega
   - **Fecha límite**: Fecha y hora límite para la entrega de la tarea
   - **Módulo**: El módulo al que pertenece la tarea

   ![Creación de una tarea]({{site.baseurl}}/assets/user/courses/activities/tasks/create_task.png)

5. Agregar _(de forma opcional)_ el **archivo de consigna**, el cual contiene la consigna de la tarea y puede ser un PDF, Word, etc.
6. Presionar el botón **Crear tarea**

Una vez hecho esto, la tarea estará creada pero **no publicada**.

## Edición de una tarea

Si la tarea **no ha sido publicada todavía**, los docentes del curso tienen la opción de editarla. Para ello, deben ir a la vista de información de la tarea y hacer clic en el botón **Editar tarea** (arriba a la derecha de la pantalla, con un icono de lápiz). Esto les permitirá modificar los detalles de la tarea, como el nombre, las instrucciones, la fecha límite y el archivo de consigna. Una vez que se realicen los cambios, se debe presionar el botón de arriba a la derecha para que se apliquen las modificaciones.

Desde esta pantalla, también se puede eliminar la tarea si es necesario, utilizando el botón **Borrar tarea**.

![Edición de una tarea]({{site.baseurl}}/assets/user/courses/activities/tasks/edit_task.png)

## Publicación de una tarea

Para que los estudiantes puedan ver y entregar la tarea, el docente debe publicarla. Esto se hace desde la vista de información de la tarea, donde se puede activar la opción de **Publicar tarea**.

![Publicación de una tarea]({{site.baseurl}}/assets/user/courses/activities/tasks/publish_task.png)

## Entrega de una tarea

Una vez que la tarea está publicada, los estudiantes pueden acceder a ella desde la sección **Actividades** del curso. Al entrar a la vista de información de la tarea, observarán los detalles de la misma. Desde ahí pueden realizar su entrega agregando un archivo con su resolución y presionando el botón **Enviar respuesta**.

![Entrega de una tarea]({{site.baseurl}}/assets/user/courses/activities/tasks/submit_task.png)

## Visualización de entregas de una tarea

Los docentes, en la pantalla de información de la tarea, pueden acceder a la lista de entregas de los estudiantes, presionando el botón **Ver entregas**.

![Botón de Ver Entregas]({{site.baseurl}}/assets/user/courses/activities/tasks/view_submissions_button.png)

Allí puede ver una lista de todos los alumnos del curso, tanto los que han entregado la tarea como los que no, pudiendo filtrarlos según ese criterio. Para cada alumno, se muestra el nombre y el estado de la entrega (entregada o pendiente), indicando el tiempo de antelación con que la entregó o el tiempo restante para la entrega si aún no se ha enviado.

![Lista de entregas]({{site.baseurl}}/assets/user/courses/activities/tasks/submissions_list.png)

Al hacer clic en el nombre de un alumno, se puede ver el detalle de su entrega, incluyendo la fecha de entrega y el archivo enviado. Además, si la entrega ya ha sido corregida, se mostrará la calificación y los comentarios del docente.

![Detalles de la entrega]({{site.baseurl}}/assets/user/courses/activities/tasks/submission_details.png)

## Corrección de una tarea

Desde la vista de información de la entrega de un alumno, el docente puede corregir la tarea presionando el botón **Calificar entrega**. Al hacer esto, aparecerán en la pantalla un selector para asignar una **calificación entre 0 y 10** y un campo de texto para dejar un **comentario de retroalimentación**.

![Corrección de una tarea]({{site.baseurl}}/assets/user/courses/activities/tasks/task_revision.png)

Una vez que se complete la corrección, el docente debe presionar el botón **Confirmar calificación** para que los cambios se apliquen. Esto actualizará la calificación y los comentarios en la entrega del alumno. Cabe aclarar que una vez realizada la corrección, el docente puede volver a editarla en cualquier momento, modificando la calificación y los comentarios si es necesario.

## Corrección automática de tareas con IA

Las tareas también pueden ser corregidas automáticamente utilizando inteligencia artificial. Para ello, en la vista de información de la entrega, el docente debe presionar el botón **Corregir con IA** (en la parte superior derecha de la pantalla) y luego **Aceptar**.

![Corrección con IA]({{site.baseurl}}/assets/user/courses/activities/tasks/start_ai_autorevision.png)

> **Nota**: Para que la corrección automática esté disponible, se deben cumplir dos condiciones:
>
> 1. La tarea debe tener un archivo de consigna cargado
> 2. Tanto el archivo de consigna como el archivo de entrega del alumno deben ser archivos PDF, TXT, DOC o DOCX

Esto iniciará el proceso de corrección automática, que puede tardar varios segundos. Una vez finalizado, le llegará una notificación al docente para avisarle que la corrección ha sido completada. Si el docente abandonó la pantalla de corrección mientras se corregía con IA, al volver debe presionar el botón **Corregir con IA** nuevamente para obtener los resultados.

![Corrección con IA completada]({{site.baseurl}}/assets/user/courses/activities/tasks/ai_autorevision_completed.png)

Si el docente presiona **Aceptar**, se mostrará la nota y comentarios generados por la IA. Desde ahí, el docente puede decidir si acepta la corrección automática en ese estado o si prefiere corregir manualmente la entrega (para este caso debe presionar el botón **Descartar**). De forma adicional, el docente puede volver a corregir la entrega con IA en cualquier momento, presionando nuevamente el botón **Corregir con IA**.

Llegado este punto, la corrección sigue de la misma forma que una corrección manual. Se muestra un cartel que indica "Corrección realizada con IA", que desaparece si el usuario modifica la calificación o los comentarios.

> **NOTA**: la indicación de "Corrección realizada con IA" es visible únicamente para el docente. Es indistinguible para
> el alumno si la corrección fue realizada manualmente o con IA.

## Visualización de entrega y calificación como alumno

El alumno de la plataforma puede ver su entrega presionando la tarea desde la sección **Actividades** del curso. Al entrar a la vista de información de la tarea, podrá ver los detalles de la misma, así como su entrega y calificación (si ya ha sido corregida).

![Visualización de entrega como alumno]({{site.baseurl}}/assets/user/courses/activities/tasks/submission_view_student.png)
