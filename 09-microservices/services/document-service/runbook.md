# Runbook - document-service

## Requisitos previos

- Base de datos `document_db`.
- Almacenamiento de archivos si aplica.

## Despliegue

1. Aplicar migraciones.
2. Verificar subida y consulta de documentos.
3. Validar aprobacion y versionado.

## Troubleshooting

- Si no se descargan archivos, revisar storage y permisos.
- Si una version no se crea, revisar estado del documento.
