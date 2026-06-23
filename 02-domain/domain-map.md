# Domain Map

> Estado: 🟡 | Ultima actualizacion: 2026-06-18
> Autor: Por definir | Equipo: Por definir

## Contextos principales

| Contexto | Responsabilidad | Relacion |
|----------|-----------------|----------|
| Identidad y acceso | Usuarios, roles, permisos y sesiones | `iam-service` |
| Datos maestros | Parametros, catalogos y codigos comunes | `reference-data-service` |
| Gestion academica | Programas, fichas, competencias y oferta | `academic-management-service` |
| Ambientes y recursos | Ambientes, inventario y reservas | `training-environment-service` |
| Horarios | Planificacion de sesiones y conflictos | `scheduling-service` |
| Actores | Instructores, aprendices y empresas | `actors-service` |
| Documentos | Versiones, plantillas y aprobaciones | `document-service` |
| Seguimiento | Indicadores, alertas y planes de mejora | `monitoring-service` |
| Auditoria | Trazabilidad inmutable de eventos | `audit-service` |

## Flujo de alto nivel

1. Los datos maestros alimentan la gestion academica.
2. La gestion academica y de actores habilita la planificacion.
3. Scheduling valida disponibilidad con ambientes y recursos.
4. Los cambios relevantes publican eventos.
5. Auditoria y monitoreo consumen eventos para trazabilidad y seguimiento.
