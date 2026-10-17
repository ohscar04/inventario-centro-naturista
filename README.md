# Sistema Básico de Control de Inventario para un Centro Naturista

## Descripción del proyecto
Proyecto académico de diseño arquitectónico para un sistema que permita registrar productos naturales, consultar existencias y actualizar cantidades disponibles en un centro naturista.

El alcance se limita al control básico de inventario. No incluye ventas, facturación ni gestión de proveedores.

## Objetivo
Proponer y documentar decisiones arquitectónicas que favorezcan la mantenibilidad, la integridad de datos y la interoperabilidad del sistema.

## Decisiones arquitectónicas (ADR)
- [ADR-001: Arquitectura en capas](docs/adr/ADR-001.md) — Mantenibilidad.
- [ADR-002: Persistencia mediante MySQL](docs/adr/ADR-002.md) — Integridad de datos.
- [ADR-003: Comunicación mediante API REST](docs/adr/ADR-003.md) — Interoperabilidad.

## Vista arquitectónica C4
- [Diagrama de contenedores](docs/c4/diagrama-contenedores.md)

## Escenarios de calidad
- [Escenarios de calidad y verificaciones propuestas](docs/escenarios-calidad.md)

## Estado del proyecto
El proyecto se encuentra en fase de diseño arquitectónico. Los ADR, el diagrama C4 simplificado y los escenarios de calidad constituyen documentación propuesta. No se afirma que exista una implementación funcional ni pruebas ejecutadas.

## Contexto académico
Maestría en Ingeniería de Software — Módulo 8: Automatización de proceso de software.

Actividad: Arquitectura: decisiones difíciles de cambiar y su registro.
