# System Brief

## Nombre del Sistema
Sistema de Gestión de Tareas

## Problema
Los estudiantes suelen gestionar sus tareas de forma desorganizada utilizando papel o aplicaciones de mensajería, lo que provoca olvidos y bajo control académico.

## Stakeholders
- Estudiantes
- Docentes
- Administrador del sistema

## Scope (Incluido)
- Crear tareas
- Editar tareas
- Marcar tareas como completadas
- Eliminar tareas
- Visualizar lista de tareas

## No-Scope (Fuera del alcance actual)
- Integración con plataformas educativas
- Notificaciones automáticas
- Aplicación móvil nativa
- Sistema de calificaciones

## Diagrama de Contexto

```mermaid
graph TD
Estudiante --> Sistema
Docente --> Sistema
Sistema --> BaseDeDatos
