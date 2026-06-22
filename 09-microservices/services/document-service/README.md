# document-service

> Estado: 🟡 En progreso | Ultima actualizacion: 2026-06-18
> Owner: Por definir
> Equipo: SENA - Diseño de Software
> Repo: Por definir
> Base de datos: `document_db`

## Responsabilidad

Administracion de documentos, versiones, plantillas y aprobaciones.

## Bounded context

Este servicio gestiona el ciclo de vida documental y la evidencia de aprobacion.

## Dependencias

| Servicio | Tipo | Motivo |
|----------|------|--------|
| reference-data-service | Sincronico | Tipos de documento y clasificaciones. |
| audit-service | Asincronico | Trazabilidad de versiones y aprobaciones. |
| monitoring-service | Asincronico | Seguimiento de pendientes y vencimientos. |

## Links

- [API Contract](./api-contract.md)
- [Data Model](./data-model.md)
- [Events](./events.md)
- [Runbook](./runbook.md)
