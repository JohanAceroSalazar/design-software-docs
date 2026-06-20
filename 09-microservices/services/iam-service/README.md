# iam-service

> Estado: 🟡 En progreso | Ultima actualizacion: 2026-06-18
> Owner: Por definir
> Equipo: SENA - Diseño de Software
> Repo: Por definir
> Base de datos: `iam_db`

## Responsabilidad

Gestion de identidad, autenticacion y autorizacion para usuarios, roles, permisos y sesiones.

## Bounded context

Contiene la logica de acceso de la plataforma y no debe depender de reglas de negocio de otros dominios.

## Dependencias

| Servicio | Tipo | Motivo |
|----------|------|--------|
| reference-data-service | Sincronico | Catalogos para estados, tipos y parametros de acceso. |
| audit-service | Asincronico | Registro de inicios de sesion, cambios de rol y eventos de seguridad. |
| monitoring-service | Asincronico | Alertas y metricas de autenticacion. |

## Links

- [API Contract](./api-contract.md)
- [Data Model](./data-model.md)
- [Events](./events.md)
- [Runbook](./runbook.md)
