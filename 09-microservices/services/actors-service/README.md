# actors-service

> Estado: 🟡 En progreso | Ultima actualizacion: 2026-06-18
> Owner: Por definir
> Equipo: SENA - Diseño de Software
> Repo: Por definir
> Base de datos: `actors_db`

## Responsabilidad

Gestion de instructores, aprendices, empresas y etapas productivas.

## Bounded context

Este servicio concentra la informacion de actores academicos y externos usados por la operacion del sistema.

## Dependencias

| Servicio | Tipo | Motivo |
|----------|------|--------|
| reference-data-service | Sincronico | Tipos, estados y clasificaciones. |
| audit-service | Asincronico | Trazabilidad de cambios y vinculos. |
| monitoring-service | Asincronico | Seguimiento de cargas, estados y alertas. |

## Links

- [API Contract](./api-contract.md)
- [Data Model](./data-model.md)
- [Events](./events.md)
- [Runbook](./runbook.md)
