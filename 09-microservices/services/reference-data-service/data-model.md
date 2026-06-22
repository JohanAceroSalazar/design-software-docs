# Modelo de datos - reference-data-service

## Entidades principales

- `catalogs`
- `catalog_items`
- `catalog_versions`

## Relaciones

- Un catalogo tiene una o varias versiones.
- Una version contiene multiples items.

## Reglas

- Los catalogos deben tener codigo estable.
- Las versiones deben ser trazables.
- Los cambios deben preservarse para auditoria y sincronizacion.
