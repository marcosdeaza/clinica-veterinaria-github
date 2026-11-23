# Clínica Veterinaria · Sistema de gestión

Proyecto de la asignatura **Introducción a la Ingeniería del Software** (Universidad Europea).
Actividad: *Coordinación y gestión del trabajo con GitHub (caso de uso clínica veterinaria)*.

**Equipo:** Marcos de Aza Riesco y Álvaro Rovira.

## Alcance
Sistema para gestionar **citas**, **clientes (propietarios)**, **mascotas** e **historiales médicos** de una clínica veterinaria.
Continúa el trabajo de las entregas anteriores: modelado UML (casos de uso, clases, estados de la cita), sprint Scrum de 10 puntos y backlog en Jira.

## Organización del equipo
| Integrante | Rol en el proyecto | Responsabilidades |
|---|---|---|
| Marcos de Aza | Product Owner + desarrollador (clientes y citas) | Prioriza el backlog, mantiene el tablero, modelo de datos, gestión de citas y agenda |
| Álvaro Rovira | Scrum Master + desarrollador (mascotas, historial y pruebas) | Detecta y elimina bloqueos, modera las Discussions, fichas de mascota, historial médico, pruebas |

Regla de revisión: cada Issue la revisa el integrante que **no** la ha desarrollado.

## Cómo trabajamos en GitHub
- **Issues**: una por actividad, con descripción, criterios de terminado, prioridad (`prioridad: alta/media/baja`), módulo y responsable.
- **Milestone**: `Sprint 1` (2 semanas, 10 puntos de historia).
- **GitHub Projects**: tablero con columnas *Pendiente → En desarrollo → Finalizado*.
- **Dependencias y bloqueos**: se registran como comentarios en la Issue y con las etiquetas `dependencia` y `bloqueada`.
- **Decisiones**: se debaten en **GitHub Discussions**, con alternativas y justificación, y se enlazan desde las Issues afectadas.
- **Ramas**: `main` estable; una rama `feature/<issue>-<nombre>` por Issue y Pull Request con `Closes #n`.

## Documentación
- [`docs/backlog.md`](docs/backlog.md) — historias de usuario, estimación y responsables.
