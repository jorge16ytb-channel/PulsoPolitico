# CLAUDE.md / Instrucciones Operativas para Agentes IA (Pulso Político)

Este archivo define las reglas de operación obligatorias para asistentes de IA (Antigravity, Claude Code) en el repositorio **PulsoPolitico**.

---

## 🔒 Regla de Oro de Escritura
- **PROHIBIDO crear o modificar archivos en disco de forma unilateral.**
- Toda propuesta de archivo nuevo, cambio en guion, título o miniatura se presenta primero en el chat o en un artefacto de borrador.
- El asistente debe esperar la orden explícita de *"escribir"*, *"guardar"* o *"aprobar"* por parte del usuario antes de tocar el disco.

---

## 🚀 Protocolo de Inicio de Sesión
1. Consultar obligatoriamente `INDICE_CENTRAL.md` antes de iniciar cualquier tarea.
2. Identificar el video activo y su fase en `TAREAS_PENDIENTES.md`.
3. Reportar brevemente al usuario el estado del proyecto para alinear el trabajo.

---

## 🏁 Protocolo de Cierre de Sesión
1. Actualizar `TAREAS_PENDIENTES.md` con las acciones realizadas durante la sesión.
2. Si se crearon o modificaron videos, actualizar la tabla maestra en `INDICE_CENTRAL.md`.
3. No cerrar una sesión con cambios sin reflejar en estos dos archivos.

---

## 🧩 Sistema de Skills (4 Dominios Macro)
Toda habilidad nueva aprendida se categoriza dentro de su dominio en `.agents/skills/`:
- `imagenes/` -> Miniaturas, contrastes, foco único, reglas de scorer 85+ pts.
- `titulos/` -> Psicología del clic, curiosity gap, front-loading móvil (40 chars).
- `guiones/` -> Estructura de retención (gancho 10s, bardo, interrupciones de patrón 60-90s).
- `informes/` -> Auditorías, presentación de datos para el equipo, métricas.

---

## 📦 Commits de Git
- Formato: `tipo: descripción corta` (ej. `feat: agregar miniatura aprobada para video 06`).
- Tipos válidos: `feat`, `fix`, `docs`, `refactor`.
- Push solo con confirmación del usuario.
