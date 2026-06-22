# Contrato API - monitoring-service

## Principales endpoints

### GET /api/v1/kpis
- Descripcion: Lista indicadores.
- Respuesta: `200 OK`

### POST /api/v1/alerts
- Descripcion: Registra una alerta.
- Respuesta: `201 Created`

### POST /api/v1/alerts/{id}/acknowledge
- Descripcion: Confirma recepcion de una alerta.
- Respuesta: `200 OK`

## Errores comunes

- `400 Bad Request`: Indicador o payload invalido.
- `404 Not Found`: Alerta no encontrada.
- `409 Conflict`: Estado incompatible.
- `500 Internal Server Error`: Error de plataforma.
