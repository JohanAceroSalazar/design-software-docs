# Runbook - actors-service

## Requisitos previos

- Base de datos `actors_db`.
- Catalogos de tipos y estados.

## Despliegue

1. Aplicar migraciones.
2. Verificar consulta de actores base.
3. Validar carga de relaciones historicas.

## Troubleshooting

- Si un actor no aparece, revisar estado, tipo y filtros.
- Si hay duplicados, revisar llaves de negocio y proceso de carga.
