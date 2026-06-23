# Eventos - scheduling-service

## Publicados

- `ScheduleCreated`
- `ScheduleValidated`
- `SchedulePublished`
- `ScheduleConflictDetected`

## Consumidos

- `ProgramCreated`
- `EnvironmentReserved`
- `ActorAssigned`

## Notas

- Los eventos deben permitir reconstruir una version del horario.
- La validacion y publicacion deben quedar separadas.
