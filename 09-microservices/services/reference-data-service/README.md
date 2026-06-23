# reference-data-service

> Estado: 🟡 En progreso | Ultima actualizacion: 2026-06-18
> Owner: Por definir
> Equipo: SENA - Diseño de Software
> Repo: Por definir
> Base de datos: `reference_data_db`

## Responsabilidad

Administracion de catalogos maestros, parametros de configuracion y codigos transversales usados por la plataforma.

## Bounded context

Este servicio define la fuente oficial de datos de referencia para los demas servicios.

## Dependencias

| Servicio | Tipo | Motivo |
|----------|------|--------|
| audit-service | Asincronico | Registro de cambios en catalogos. |
| monitoring-service | Asincronico | Seguimiento de cambios masivos o fallos de sincronizacion. |

## Links

- [API Contract](./api-contract.md)
- [Data Model](./data-model.md)
- [Events](./events.md)
- [Runbook](./runbook.md)
