# Eventos - training-environment-service

## Publicados

- `EnvironmentCreated`
- `EnvironmentUpdated`
- `EnvironmentReserved`
- `ReservationCancelled`

## Consumidos

- `ReferenceDataUpdated`

## Notas

- Las reservas deben ser idempotentes.
- Los cambios de capacidad o estado deben quedar trazados.
