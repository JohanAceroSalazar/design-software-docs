# Data Dictionary

> Estado: 🟡 | Ultima actualizacion: 2026-06-18
> Autor: Por definir | Equipo: Por definir

## Entidades compartidas

| Entidad | Campos base | Uso |
|---------|-------------|-----|
| Usuario | id, documento, nombre, estado, created_at | IAM y trazabilidad |
| Programa | id, codigo, nombre, version, estado | Gestion academica |
| Ficha | id, numero, programa_id, periodo, estado | Planificacion academica |
| Ambiente | id, codigo, tipo, capacidad, estado | Reservas y horarios |
| Horario | id, periodo, ficha_id, estado | Planificacion |
| Reserva | id, ambiente_id, inicio, fin, estado | Disponibilidad |
| Documento | id, tipo, version, estado | Control documental |
| EventoAuditoria | id, fuente, correlation_id, payload, created_at | Cumplimiento |

## Reglas de diccionario

- Cada campo debe tener un unico significado.
- Los codigos maestros deben venir de catalogos versionados.
- Los campos sensibles deben tratarse segun las reglas de seguridad documental.
