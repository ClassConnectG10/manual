---
title: Historial de Eventos
nav_order: 3
layout: default
parent: Guía del Administrador
---

# Historial de Eventos

El panel de administración incluye una funcionalidad para registrar eventos importantes que ocurren en la aplicación. Esto es útil para rastrear acciones críticas y mantener un registro de las actividades del sistema y quiénes las realizaron.

## Tipos de Eventos Registrados

Tiene la posibilidad de visualizar eventos de diferentes tipos, como:

- **Registro de Administradores**: Eventos relacionados con la creación de administradores
- **Bloqueo de Usuarios**: Eventos que indican que un usuario ha sido bloqueado
- **Desbloqueo de Usuarios**: Eventos que indican que un usuario ha sido desbloqueado

## Información de los Eventos

Todos estos eventos cuentan con:

- **Identificador único**: Cada evento tiene un ID único para su identificación
- **Fecha y hora**: Registro preciso de cuándo ocurrió el evento
- **Usuario ejecutor**: Quién realizó la acción
- **Usuario afectado**: Quién fue afectado por la acción (cuando aplique)
- **Tipo de evento**: La naturaleza de la acción realizada

## Funcionalidades de la Tabla de Eventos

Todos estos datos se visualizan en una tabla que permite:

- **Filtrar**: Puede filtrar los eventos por cualquier campo, como tipo de evento, usuario afectado o fecha
- **Ordenar**: Puede ordenar los eventos por cualquier campo, como fecha o tipo de evento
- **Buscar**: Puede buscar eventos específicos utilizando palabras clave
- **Paginación**: Si hay muchos eventos, puede navegar a través de ellos utilizando la paginación donde el número de eventos por página se puede configurar
- **Exportar**: Puede descargar el historial de eventos en formato CSV para análisis externos o respaldos

![Pantalla de Eventos del Panel de Administración]({{site.baseurl}}/assets/admin/events.jpeg)

## Utilidad del Historial

Este historial de eventos es fundamental para:

- **Auditoría**: Mantener un registro de todas las acciones administrativas
- **Seguridad**: Identificar actividades sospechosas o no autorizadas
- **Cumplimiento**: Satisfacer requisitos de trazabilidad y transparencia
- **Resolución de problemas**: Facilitar la identificación de la causa de incidentes
