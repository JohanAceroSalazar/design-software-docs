# monitoring-service

> Estado: 🟡 En progreso | Ultima actualizacion: 2026-06-18
> Owner: Por definir
> Equipo: SENA - Diseño de Software
> Repo: Por definir
> Base de datos: `monitoring_db`

## Responsabilidad

Seguimiento de KPI, alertas, notificaciones y planes de mejora.

## Bounded context

Este servicio agrupa la observabilidad funcional del negocio y la comunicación de alertas operativas.

## Dependencias

| Servicio | Tipo | Motivo |
|----------|------|--------|
| audit-service | Asincronico | Registro de alertas y acciones correctivas. |
| reference-data-service | Sincronico | Catalogos de tipos de alerta y estados. |

## Links

- [API Contract](./api-contract.md)
- [Data Model](./data-model.md)
- [Events](./events.md)
- [Runbook](./runbook.md)
