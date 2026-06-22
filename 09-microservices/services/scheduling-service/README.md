# scheduling-service

> Estado: 🟡 En progreso | Ultima actualizacion: 2026-06-18
> Owner: Por definir
> Equipo: SENA - Diseño de Software
> Repo: Por definir
> Base de datos: `scheduling_db`

## Responsabilidad

Planificacion de horarios, sesiones y resolucion de conflictos.

## Bounded context

Este servicio orquesta la asignacion temporal de sesiones, instructores y ambientes.

## Dependencias

| Servicio | Tipo | Motivo |
|----------|------|--------|
| academic-management-service | Sincronico | Programas, fichas y oferta academica. |
| training-environment-service | Sincronico | Disponibilidad de ambientes. |
| actors-service | Sincronico | Disponibilidad de instructores y grupos. |
| audit-service | Asincronico | Trazabilidad de cambios en horarios. |
| monitoring-service | Asincronico | Alertas por conflicto o incumplimiento. |

## Links

- [API Contract](./api-contract.md)
- [Data Model](./data-model.md)
- [Events](./events.md)
- [Runbook](./runbook.md)
