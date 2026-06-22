# API

> Estado: 🟡 Pendiente | Ultima actualizacion: 2026-06-18
> Autor: Por definir | Equipo: Por definir

## Contenido

Define lineamientos de API, autenticacion y ubicacion de contratos OpenAPI.

## Archivos

| Archivo | Descripcion | Estado |
|---------|-------------|--------|
| [guidelines.md](./guidelines.md) | Convenciones de diseno de APIs | 🟡 |
| [authentication.md](./authentication.md) | Estrategia de autenticacion y autorizacion | 🟡 |
| [contracts/openapi/](./contracts/openapi/) | Contratos OpenAPI validados y publicables | 🟡 |

## Donde va cada contrato

| Tipo de contrato | Donde vive | Cuando se usa |
|-----------------|------------|---------------|
| Contrato de implementacion (borrador, en evolucion) | `09-microservices/services/<svc>/api-contract.md` | Durante el desarrollo del servicio |
| Contrato OpenAPI publicable (estable, revisado) | `07-api/contracts/openapi/<svc>.yaml` | Cuando el contrato es estable y puede compartirse con consumidores externos |

**Regla:** el contrato en `07-api/contracts/openapi/` es la version aprobada por arquitectura. Si hay diferencia entre ambos, el de `07-api/` tiene precedencia para consumidores externos.
