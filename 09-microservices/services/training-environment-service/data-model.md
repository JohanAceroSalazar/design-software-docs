# Modelo de datos - training-environment-service

## Entidades principales

- `environments`
- `environment_types`
- `assets`
- `reservations`
- `reservation_events`

## Reglas

- Un ambiente tiene capacidad y tipo.
- Una reserva no puede traslaparse con otra valida.
- El inventario debe poder auditarse por cambio.
