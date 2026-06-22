# Contrato API - training-environment-service

## Principales endpoints

### GET /api/v1/environments
- Descripcion: Lista ambientes disponibles.
- Respuesta: `200 OK`

### POST /api/v1/environments
- Descripcion: Crea un ambiente.
- Respuesta: `201 Created`

### POST /api/v1/reservations
- Descripcion: Crea una reserva de ambiente.
- Respuesta: `201 Created`

### PUT /api/v1/reservations/{id}/cancel
- Descripcion: Cancela una reserva.
- Respuesta: `200 OK`

## Errores comunes

- `400 Bad Request`: Fecha, capacidad o payload invalido.
- `404 Not Found`: Ambiente o reserva no encontrada.
- `409 Conflict`: Cruce de reserva o estado incompatible.
- `500 Internal Server Error`: Error de plataforma.
