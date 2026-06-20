# Contrato API - actors-service

## Principales endpoints

### GET /api/v1/instructors
- Descripcion: Lista instructores.
- Respuesta: `200 OK`

### POST /api/v1/instructors
- Descripcion: Crea un instructor.
- Respuesta: `201 Created`

### GET /api/v1/apprentices
- Descripcion: Lista aprendices.
- Respuesta: `200 OK`

### POST /api/v1/companies
- Descripcion: Registra una empresa o actor externo.
- Respuesta: `201 Created`

## Errores comunes

- `400 Bad Request`: Documento o payload invalido.
- `404 Not Found`: Actor no encontrado.
- `409 Conflict`: Registro duplicado.
- `500 Internal Server Error`: Error de plataforma.
