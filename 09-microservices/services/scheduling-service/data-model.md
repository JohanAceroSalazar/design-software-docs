# Modelo de datos - scheduling-service

## Entidades principales

- `schedules`
- `schedule_versions`
- `schedule_entries`
- `conflicts`
- `validation_results`

## Reglas

- Un horario puede tener multiples versiones.
- Cada entrada del horario debe asociar sesion, ambiente e instructor.
- Los conflictos detectados deben conservar evidencia.
