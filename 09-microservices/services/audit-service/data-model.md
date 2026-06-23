# Modelo de datos - audit-service

## Entidades principales

- `audit_events`
- `audit_event_types`
- `audit_snapshots`

## Reglas

- El registro es append-only.
- No se permiten borrados fisicos operativos.
- El evento debe conservar actor, origen y correlacion.
