# Contrato API - iam-service

## Principales endpoints

### POST /api/v1/auth/login
- Descripcion: Inicia sesion y entrega tokens de acceso.
- Request:
```json
{"username":"string","password":"string"}
```
- Respuesta: `200 OK`

### POST /api/v1/auth/refresh
- Descripcion: Renueva el token de acceso.
- Respuesta: `200 OK`

### GET /api/v1/users/{id}
- Descripcion: Consulta un usuario por identificador.
- Respuesta: `200 OK`

### POST /api/v1/roles
- Descripcion: Crea un rol.
- Respuesta: `201 Created`

### PUT /api/v1/users/{id}/roles
- Descripcion: Asigna o actualiza roles de un usuario.
- Respuesta: `200 OK`

## Errores comunes

- `400 Bad Request`: Credenciales o payload invalido.
- `401 Unauthorized`: Token faltante o invalido.
- `403 Forbidden`: Usuario sin permisos.
- `404 Not Found`: Recurso no existe.
- `409 Conflict`: Usuario o rol en estado incompatible.
- `500 Internal Server Error`: Error de plataforma.
