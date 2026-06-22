# Authentication

> Estado: 🟡 | Ultima actualizacion: 2026-06-18
> Autor: Por definir | Equipo: Por definir

## Estrategia

- Autenticacion centralizada en `iam-service`.
- Tokens con expiracion y renovacion controlada.
- Autorizacion basada en roles y permisos.

## Reglas

- Cada solicitud protegida debe incluir credenciales validas.
- Los servicios deben validar el token y el alcance necesario.
- Las rutas publicas deben estar explicitamente marcadas.
