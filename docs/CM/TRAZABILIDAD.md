# Registro de Trazabilidad (#4)

## Convencion de mensajes de commit
- chore: tareas de configuracion
- docs: documentacion
- feat: nueva funcionalidad
- fix: correccion de bugs
- audit: auditoria de configuracion
- test: pruebas

Todos los commits deben referenciar el issue: (#N)

## Tabla de trazabilidad

| Issue | PR | Commit | Release | Evidencia |
|---|---|---|---|---|
| #1 Secretos y versionado | PR merge a main | chore: remove secrets (#1) | v1.1.0 | .gitignore + .env.example |
| #2 Auditoria fisica | PR audit/fisica-2 | audit: add checklist (#2) | v1.2.0 | CHECKLIST_AUDITORIA.md |
| #3 Auditoria funcional | PR audit/funcional-3 | docs: functional audit (#3) | v1.2.0 | AUDITORIA_FUNCIONAL.md |
| #4 Trazabilidad | PR docs/trazabilidad-4 | docs: add traceability (#4) | v1.2.0 | TRAZABILIDAD.md |
| #5 Release v1.2.0 | PR release/v1.2.0 | chore: release v1.2.0 (#5) | v1.2.0 | CHANGELOG + tag |
