# Runbook - audit-service

## Requisitos previos

- Base de datos `audit_db`.
- Conectores de eventos activos.

## Despliegue

1. Aplicar migraciones.
2. Verificar recepcion de eventos.
3. Confirmar consultas historicas.

## Troubleshooting

- Si faltan registros, revisar conectividad con productores.
- Si hay retrasos, revisar cola, retencion y capacidad de almacenamiento.
