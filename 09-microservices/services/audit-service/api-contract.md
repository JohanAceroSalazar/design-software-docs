# Contrato API - audit-service

## Principales endpoints

### GET /api/v1/audit-events
- Descripcion: Lista eventos de auditoria.
- Respuesta: `200 OK`

### GET /api/v1/audit-events/{id}
- Descripcion: Consulta un evento especifico.
- Respuesta: `200 OK`

## Errores comunes

- `400 Bad Request`: Filtro invalido.
- `404 Not Found`: Evento no encontrado.
- `500 Internal Server Error`: Error de plataforma.
