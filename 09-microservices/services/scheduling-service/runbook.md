# Runbook - scheduling-service

## Requisitos previos

- Base de datos `scheduling_db`.
- Acceso a servicios de academico, ambientes y actores.

## Despliegue

1. Aplicar migraciones.
2. Verificar conectividad con dependencias.
3. Probar validacion y publicacion de horarios.

## Troubleshooting

- Si la validacion falla, revisar datos maestros y conflictos.
- Si una publicacion no genera eventos, revisar broker y auditoria.
