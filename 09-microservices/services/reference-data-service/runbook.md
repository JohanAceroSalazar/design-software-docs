# Runbook - reference-data-service

## Requisitos previos

- Base de datos `reference_data_db`.
- Carga inicial de catalogos maestros.

## Despliegue

1. Aplicar migraciones.
2. Cargar catalogos base si el ambiente es nuevo.
3. Validar consulta de catalogos y versionado.

## Troubleshooting

- Si faltan valores, revisar la version activa y el proceso de carga.
- Si un cambio no se refleja, validar eventos y cache de consumidores.
