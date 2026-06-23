# Runbook - iam-service

## Requisitos previos

- Base de datos `iam_db`.
- Variables de entorno de autenticacion.
- Conectividad con broker de eventos si aplica.

## Despliegue

1. Aplicar migraciones.
2. Publicar configuracion del ambiente.
3. Levantar la aplicacion.
4. Verificar login y consulta de usuario.

## Troubleshooting

- Si falla login, revisar credenciales, expiracion y configuracion del proveedor de tokens.
- Si no hay auditoria, revisar publicacion de eventos y conectividad con `audit-service`.
