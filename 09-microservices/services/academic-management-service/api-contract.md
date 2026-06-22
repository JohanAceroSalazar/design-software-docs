# Contrato API - academic-management-service

## Principales endpoints

### GET /api/v1/programs
- Descripcion: Lista programas academicos.
- Respuesta: `200 OK`

### POST /api/v1/programs
- Descripcion: Crea un programa academico.
- Respuesta: `201 Created`

### GET /api/v1/groups
- Descripcion: Lista fichas o grupos.
- Respuesta: `200 OK`

### POST /api/v1/groups
- Descripcion: Crea una ficha o grupo academico.
- Respuesta: `201 Created`

### PUT /api/v1/groups/{id}
- Descripcion: Actualiza el estado o configuracion de una ficha.
- Respuesta: `200 OK`

## Errores comunes

- `400 Bad Request`: Datos academicos invalidos.
- `404 Not Found`: Programa o ficha no existe.
- `409 Conflict`: Codigo academico repetido.
- `500 Internal Server Error`: Error de plataforma.
