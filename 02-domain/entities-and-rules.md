# Entities and Rules

> Estado: 🟡 | Ultima actualizacion: 2026-06-18
> Autor: Por definir | Equipo: Por definir

## Entidades clave

| Entidad | Regla principal |
|---------|-----------------|
| Usuario | Debe tener rol(es) validos y estado activo para operar. |
| Programa | Debe pertenecer a una familia o linea formativa definida. |
| Ficha | Debe asociarse a un programa, periodo y estado academico. |
| Ambiente | Debe tener capacidad, tipo y disponibilidad trazable. |
| Horario | No puede generar cruces de tiempo para el mismo recurso. |
| Reserva | Debe respetar ventanas de uso y autorizacion. |
| Documento | Debe conservar version, autor y estado de aprobacion. |
| Evento de auditoria | Debe ser append-only y conservar correlacion. |

## Reglas de negocio

- Un ambiente no puede reservarse para dos sesiones simultaneas.
- Un instructor no puede quedar asignado a sesiones traslapadas.
- Una ficha debe consultar solo horarios asociados a su plan formativo.
- Toda aprobacion o cambio sensible debe quedar en auditoria.
- Los catalogos maestros deben ser versionables y consistentes entre servicios.
