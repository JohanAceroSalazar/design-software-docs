# Runbook - training-environment-service

## Requisitos previos

- Base de datos `training_environment_db`.
- Catalogos de tipos y estados.

## Despliegue

1. Aplicar migraciones.
2. Validar carga de ambientes base.
3. Verificar creacion y cancelacion de reservas.

## Troubleshooting

- Si una reserva falla, revisar traslape, capacidad y estado del ambiente.
- Si el inventario no coincide, revisar el historial de cambios.
