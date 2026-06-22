# Runbook - academic-management-service

## Requisitos previos

- Base de datos `academic_management_db`.
- Catalogos maestros cargados.

## Despliegue

1. Aplicar migraciones.
2. Verificar integridad de programas y fichas.
3. Revisar que las versiones academicas queden publicadas.

## Troubleshooting

- Si una ficha no aparece, revisar estado, periodo y version academica.
- Si una version historica cambia, revisar auditoria y eventos publicados.
