# training-environment-service

> Estado: 🟡 En progreso | Ultima actualizacion: 2026-06-18
> Owner: Por definir
> Equipo: SENA - Diseño de Software
> Repo: Por definir
> Base de datos: `training_environment_db`

## Responsabilidad

Administracion de ambientes, inventario de recursos y reservas de formacion.

## Bounded context

Modela disponibilidad y uso de espacios fisicos o logicos necesarios para la formacion.

## Dependencias

| Servicio | Tipo | Motivo |
|----------|------|--------|
| reference-data-service | Sincronico | Catalogos de tipo de ambiente y estado. |
| audit-service | Asincronico | Trazabilidad de reservas y cambios de inventario. |
| monitoring-service | Asincronico | Seguimiento de ocupacion y alertas. |

## Links

- [API Contract](./api-contract.md)
- [Data Model](./data-model.md)
- [Events](./events.md)
- [Runbook](./runbook.md)
