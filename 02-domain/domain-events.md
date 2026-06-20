# Domain Events

> Estado: 🟡 | Ultima actualizacion: 2026-06-18
> Autor: Por definir | Equipo: Por definir

## Eventos relevantes

| Evento | Emisor | Significado |
|--------|--------|-------------|
| `ProgramCreated` | `academic-management-service` | Se creo un nuevo programa academico. |
| `SchedulePlanned` | `scheduling-service` | Se genero una propuesta o version de horario. |
| `EnvironmentReserved` | `training-environment-service` | Se bloqueo un ambiente para una sesion. |
| `ActorAssigned` | `actors-service` | Se asigno un actor a un grupo, sesion o actividad. |
| `DocumentApproved` | `document-service` | Un documento completo paso a estado aprobado. |
| `AlertRaised` | `monitoring-service` | Se detecto una desviacion o umbral critico. |
| `AuditEventRecorded` | `audit-service` | Se registro un evento de trazabilidad. |

## Reglas de eventos

- Todo evento debe incluir `eventId`, `occurredAt`, `correlationId` y `source`.
- Los eventos deben ser idempotentes.
- La semantica del evento debe reflejar un hecho, no una accion futura.
