# Requirements

## Backlog
Link del tablero (Trello/Jira/GitHub Projects):
(https://trello.com/b/QYYFeER6/sistema-de-gestion-de-tareas-backlog)

---

# User Stories

### US01 - Crear tarea
Prioridad: Must

Como estudiante quiero crear una tarea para organizar mis pendientes.

**Criterios de aceptación (Given/When/Then)**

Given el estudiante está en el sistema  
When ingresa título y descripción de la tarea  
Then la tarea se guarda correctamente en la lista  

Given la tarea fue creada  
When el estudiante visualiza su lista  
Then la tarea aparece en estado pendiente  

---

### US02 - Editar tarea
Prioridad: Must

Como estudiante quiero editar una tarea para actualizar información.

**Criterios de aceptación (Given/When/Then)**

Given existe una tarea registrada  
When el estudiante modifica la información  
Then el sistema guarda los cambios correctamente  

---

### US03 - Marcar tarea como completada
Prioridad: Must

Como estudiante quiero marcar una tarea como completada para llevar control de progreso.

Criterios:
- El sistema cambia el estado a completada
- La tarea se visualiza como finalizada

---

### US04 - Eliminar tarea
Prioridad: Should

Como estudiante quiero eliminar una tarea que ya no necesito.

Criterios:
- La tarea desaparece de la lista
- El sistema actualiza correctamente la vista

---

### US05 - Asignar fecha límite
Prioridad: Should

---

### US06 - Filtrar tareas por estado
Prioridad: Could

---

### US07 - Categorizar tareas
Prioridad: Could

---

### US08 - Compartir tareas con docente
Prioridad: Won't
