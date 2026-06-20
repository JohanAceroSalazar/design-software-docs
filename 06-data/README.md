# Datos

> Estado: 🟡 Pendiente | Ultima actualizacion: 2026-06-18
> Autor: Por definir | Equipo: Por definir

## Contenido

Documenta modelos de datos, diccionario y estrategia de migracion.

> **Diferencia con `02-domain`:** esta seccion describe la implementacion de persistencia (tablas, columnas, tipos, relaciones, indices, migraciones). Las entidades de negocio y sus reglas se documentan en [`02-domain/`](../02-domain/).

> **Diferencia con `09-microservices`:** aqui vive el modelo de datos global del sistema. El modelo transaccional propio de cada servicio se documenta en `09-microservices/services/<servicio>/data-model.md`.

## Archivos

| Archivo | Descripcion | Estado |
|---------|-------------|--------|
| [models.md](./models.md) | Modelos conceptuales, logicos o fisicos de datos | 🟡 |
| [data-dictionary.md](./data-dictionary.md) | Diccionario de entidades, campos y reglas | 🟡 |
| [migration-strategy.md](./migration-strategy.md) | Estrategia para cambios y migraciones de datos | 🟡 |
