# Contrato API - reference-data-service

## Principales endpoints

### GET /api/v1/catalogs
- Descripcion: Lista los catalogos disponibles.
- Respuesta: `200 OK`

### GET /api/v1/catalogs/{code}
- Descripcion: Consulta un catalogo por codigo.
- Respuesta: `200 OK`

### POST /api/v1/catalogs
- Descripcion: Crea un catalogo maestro.
- Respuesta: `201 Created`

### PUT /api/v1/catalogs/{code}
- Descripcion: Actualiza un catalogo existente.
- Respuesta: `200 OK`

## Errores comunes

- `400 Bad Request`: Codigo o payload invalido.
- `404 Not Found`: Catalogo no encontrado.
- `409 Conflict`: Version o codigo duplicado.
- `500 Internal Server Error`: Error de plataforma.
