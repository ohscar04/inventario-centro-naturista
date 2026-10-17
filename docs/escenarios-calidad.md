# Escenarios de calidad — Sistema de Inventario para un Centro Naturista

**Estado:** Escenarios propuestos, pendientes de implementación y pruebas.

## Escenario 1: Mantenibilidad
**Decisión relacionada:** ADR-001 — Arquitectura en capas.

**Situación:** Se necesita modificar el diseño de la pantalla de consulta de productos.

**Respuesta esperada:** El cambio debe realizarse en la capa de presentación sin modificar las reglas de negocio que validan el inventario.

**Verificación propuesta:** Revisar los archivos modificados y ejecutar pruebas de regresión para comprobar que las operaciones de inventario continúan funcionando.

## Escenario 2: Integridad de datos
**Decisión relacionada:** ADR-002 — Persistencia mediante MySQL.

**Situación:** Un empleado actualiza la cantidad disponible de un producto natural.

**Respuesta esperada:** El sistema debe guardar correctamente la cantidad confirmada y rechazar valores negativos.

**Verificación propuesta:** Ejecutar pruebas con cantidades válidas y negativas, consultar el registro almacenado y verificar las restricciones de la base de datos.

## Escenario 3: Interoperabilidad
**Decisión relacionada:** ADR-003 — Comunicación mediante API REST.

**Situación:** Un cliente HTTP solicita consultar los productos registrados.

**Respuesta esperada:** La API debe devolver una respuesta JSON válida conforme al contrato definido.

**Verificación propuesta:** Enviar solicitudes HTTP a los endpoints implementados y comprobar el código de respuesta y la estructura del JSON.

## Estado de las evidencias
Los escenarios documentan los criterios de verificación del diseño propuesto. No representan resultados de pruebas ejecutadas. Cuando exista una implementación, deberán incorporarse las pruebas y sus resultados al repositorio.
