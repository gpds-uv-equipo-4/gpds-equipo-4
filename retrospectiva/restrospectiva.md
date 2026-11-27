# Retrospectiva del Equipo 4 — Metodología XP

## 3 Ventajas observadas en el trabajo del equipo
1. **Detección temprana de errores mediante integración continua (GitHub Actions):**
   * *Ejemplo:* Al configurar las pruebas automáticas de sintaxis PHP y las validaciones de nombres y fechas en cada `push` o Pull Request, evitamos integrar código roto a la rama `main`.
2. **Mejor calidad de código gracias a la revisión por pares en Pull Requests:**
   * *Ejemplo:* Antes de fusionar las historias `GE4-26` (consulta de tareas) y `GE4-27` (actualización de estado), otro integrante revisó los cambios en GitHub y detectó detalles de validación antes del merge.
3. **Trazabilidad clara entre el código y el tablero de Jira:**
   * *Ejemplo:* Al nombrar las ramas y commits con la clave de la historia (`GE4-24`, `GE4-28`), todo el equipo pudo ver en Jira qué Pull Request correspondía a cada funcionalidad sin perder tiempo preguntando avances.

## 3 Desventajas o áreas de mejora identificadas
1. **Acumulación de movimientos en el tablero de Jira cerca del cierre del sprint:**
   * *Ejemplo:* Varias tarjetas permanecieron en *En progreso* o *En revisión* durante varios días y se movieron a *Done* casi al final, lo que redujo la visibilidad diaria en el gráfico de burndown.
2. **Retrasos en la aprobación de Pull Requests por falta de disponibilidad simultánea:**
   * *Ejemplo:* Una historia terminada tuvo que esperar varias horas para fusionarse a `main` porque los revisores estaban trabajando en sus propias ramas y no se notificó de inmediato por el canal del equipo.
3. **Falta de detalle inicial en algunos criterios de aceptación y comentarios de seguimiento:**
   * *Ejemplo:* Al refinar historias con validaciones específicas (como los 4 casos de nombres y 6 de fechas), tuvimos que aclarar por chat qué mensajes de error mostrar porque no estaban explícitos desde el inicio en la tarjeta.
