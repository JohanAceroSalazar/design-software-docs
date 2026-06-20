# audit-service

> Estado: 🟡 En progreso | Ultima actualizacion: 2026-06-18
> Owner: Por definir
> Equipo: SENA - Diseño de Software
> Repo: Por definir
> Base de datos: `audit_db`

## Responsabilidad

Registro append-only de auditoria para trazabilidad y cumplimiento.

## Bounded context

Este servicio conserva la historia de eventos y acciones relevantes sin permitir edicion destructiva.

## Dependencias

| Servicio | Tipo | Motivo |
|----------|------|--------|
| reference-data-service | Sincronico | Tipos y clasificaciones de auditoria. |

## Links

- [API Contract](./api-contract.md)
- [Data Model](./data-model.md)
- [Events](./events.md)
- [Runbook](./runbook.md)
