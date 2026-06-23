# Patrones de comunicacion

> Estado: 🟡 | Ultima actualizacion: 2026-06-18
> Autor: Equipo SENA - Arquitectura

## Sincrona (REST / gRPC)

- Uso principal para consultas y transacciones breves.
- Endpoints REST versionados en la ruta.
- Autenticacion y autorizacion gestionadas por `iam-service`.
- Timeouts recomendados: 3-5s para UI, 10s para integraciones backend.

### Buenas practicas

- Validar payloads en la entrada.
- Usar HTTP 4xx para validaciones y 5xx para fallos de plataforma.
- Documentar cada endpoint en `api-contract.md` y, cuando exista, en OpenAPI.

## Asincrona (eventos)

- El ecosistema usa eventos para desacoplar servicios y distribuir cambios.
- `reference-data-service` comparte catalogos maestros.
- `monitoring-service`, `audit-service` y `document-service` consumen eventos de dominio.
- Se recomienda un broker con persistencia y entrega al menos una vez.

### Principios

- Event-driven para cambios en estados criticos.
- Eventos idempotentes y con metadatos de correlacion.
- Sagas o choreographies cuando un flujo distribuido necesita consistencia eventual.

## Resiliencia

- Retries con backoff exponencial para llamadas transitorias.
- Circuit breaker para proteger dependencias lentas.
- Bulkheads logicos para aislar procesos asincronos.
- Monitoreo de disponibilidad, latencia y tasas de error en `monitoring-service`.

### Recuperacion

1. Detectar y registrar el fallo.
2. Reintentar cuando sea seguro.
3. Degradar de forma controlada si persiste el problema.
4. Disparar alertas automaticas.
