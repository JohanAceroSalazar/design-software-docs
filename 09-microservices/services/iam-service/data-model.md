# Modelo de datos - iam-service

## Entidades principales

- `users`
- `roles`
- `permissions`
- `sessions`
- `user_roles`
- `role_permissions`

## Relaciones

- Un usuario puede tener varios roles.
- Un rol puede contener varios permisos.
- Una sesion pertenece a un usuario.

## Reglas

- El usuario debe conservar estado activo/inactivo.
- Las sesiones deben expirar y poder revocarse.
- Los cambios de acceso deben registrarse en auditoria.
