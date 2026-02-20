# ADR-001 – Arquitectura en Capas

## Estado
Aceptado

## Contexto
El módulo CRM requiere una estructura organizada que permita separar responsabilidades entre interfaz, lógica de negocio y persistencia.

## Decisión
Se adopta una arquitectura en capas con la siguiente estructura:

UI → API → Dominio → Persistencia

- UI: Interfaces diseñadas en Figma.
- API: Controladores que gestionan solicitudes.
- Dominio: Entidad Cliente y reglas de negocio.
- Persistencia: Repositorio conectado a base de datos.

## Consecuencias
- Facilita mantenibilidad.
- Permite escalabilidad del módulo.
- Asegura separación clara de responsabilidades.
