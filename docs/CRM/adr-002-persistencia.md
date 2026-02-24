# ADR-002 – Persistencia de Datos

## Estado
Aceptado

## Contexto
El módulo CRM requiere almacenar información estructurada de clientes, incluyendo datos personales y comerciales.

## Decisión
Se utilizará una base de datos relacional para almacenar los datos del módulo CRM.

## Justificación
- Permite integridad referencial.
- Facilita consultas estructuradas.
- Compatible con el resto del ERP.

## Consecuencias
- Requiere diseño de entidad Cliente.
- Permite integración futura con módulos como Facturación e Inventario.
