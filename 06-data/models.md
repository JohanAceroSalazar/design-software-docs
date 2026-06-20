# Models

> Estado: 🟡 | Ultima actualizacion: 2026-06-18
> Autor: Por definir | Equipo: Por definir

## Modelo conceptual

El modelo global agrupa entidades compartidas entre servicios como usuario, programa, ficha, ambiente, horario, reserva, documento y evento de auditoria.

## Modelo logico

- Cada servicio mantiene su esquema propio para datos transaccionales.
- Las entidades compartidas deben tener identificadores consistentes.
- Las relaciones entre dominios se resuelven por referencias y eventos, no por acoplamiento de tablas.

## Modelo fisico

- Claves primarias estables.
- Indices para consultas frecuentes.
- Campos de auditoria y control de version.
