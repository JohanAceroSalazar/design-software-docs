# Contrato API - document-service

## Principales endpoints

### GET /api/v1/documents
- Descripcion: Lista documentos.
- Respuesta: `200 OK`

### POST /api/v1/documents
- Descripcion: Registra un documento.
- Respuesta: `201 Created`

### POST /api/v1/documents/{id}/versions
- Descripcion: Crea una version nueva.
- Respuesta: `201 Created`

### PUT /api/v1/documents/{id}/approve
- Descripcion: Aprueba un documento.
- Respuesta: `200 OK`

## Errores comunes

- `400 Bad Request`: Tipo o payload invalido.
- `404 Not Found`: Documento no encontrado.
- `409 Conflict`: Estado incompatible para aprobar o versionar.
- `500 Internal Server Error`: Error de plataforma.
