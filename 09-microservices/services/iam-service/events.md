# Eventos - iam-service

## Publicados

- `UserLoggedIn`
- `UserLoggedOut`
- `UserRoleAssigned`
- `UserPermissionChanged`

## Consumidos

- `ReferenceDataUpdated`
- `AuditEventRequested`

## Notas

- Los eventos deben incluir `correlationId`.
- Los cambios de seguridad deben ser idempotentes y auditables.
