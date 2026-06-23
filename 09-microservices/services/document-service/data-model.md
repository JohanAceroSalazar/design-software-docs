# Modelo de datos - document-service

## Entidades principales

- `documents`
- `document_versions`
- `document_templates`
- `approvals`

## Reglas

- Cada documento debe conservar historial de versiones.
- Una aprobacion debe quedar asociada a un usuario y fecha.
- Las plantillas deben poder reutilizarse sin perder versionado.
