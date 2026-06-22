# Contrato API - scheduling-service

## Principales endpoints

### GET /api/v1/schedules
- Descripcion: Lista horarios o versiones de horario.
- Respuesta: `200 OK`

### POST /api/v1/schedules
- Descripcion: Crea una propuesta de horario.
- Respuesta: `201 Created`

### POST /api/v1/schedules/{id}/validate
- Descripcion: Valida conflictos de la propuesta.
- Respuesta: `200 OK`

### PUT /api/v1/schedules/{id}/publish
- Descripcion: Publica una version de horario.
- Respuesta: `200 OK`

## Errores comunes

- `400 Bad Request`: Datos academicos o de tiempo invalidos.
- `409 Conflict`: Cruce de ambiente, instructor o ficha.
- `422 Unprocessable Entity`: La propuesta no supera validaciones.
- `500 Internal Server Error`: Error de plataforma.
