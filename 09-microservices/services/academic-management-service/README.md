# academic-management-service

> Estado: 🟡 En progreso | Ultima actualizacion: 2026-06-18
> Owner: Por definir
> Equipo: SENA - Diseño de Software
> Repo: Por definir
> Base de datos: `academic_management_db`

## Responsabilidad

Gestion de programas, competencias, fichas, grupos y oferta academica.

## Bounded context

Este servicio concentra las reglas academicas que estructuran la formacion y habilitan la planificacion de horarios.

## Dependencias

| Servicio | Tipo | Motivo |
|----------|------|--------|
| reference-data-service | Sincronico | Catalogos y codigos academicos. |
| audit-service | Asincronico | Trazabilidad de cambios academicos. |
| monitoring-service | Asincronico | Seguimiento de estados y desviaciones. |

## Links

- [API Contract](./api-contract.md)
- [Data Model](./data-model.md)
- [Events](./events.md)
- [Runbook](./runbook.md)
