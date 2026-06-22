# Runbook - monitoring-service

## Requisitos previos

- Base de datos `monitoring_db`.
- Fuentes de metricas y eventos activas.

## Despliegue

1. Aplicar migraciones.
2. Verificar ingreso de metricas de prueba.
3. Validar creacion y confirmacion de alertas.

## Troubleshooting

- Si no hay metricas, revisar consumidores y programacion de captura.
- Si las alertas no se notifican, revisar canales y colas.
