# Sprint 1 – Reporte de Ejecución

## Sprint Planning

Duración del Sprint: 1 semana  
Objetivo: Implementar la funcionalidad básica del módulo de Inventario.

Se seleccionaron las historias con mayor valor de negocio y menor complejidad técnica inicial.

---

## Flujo de trabajo Git

Se definió el siguiente esquema de ramas:

- main → versión estable
- dev → integración
- feature/INV-01-registrar-producto
- feature/INV-02-registrar-movimiento
- feature/INV-04-consultar-inventario

Convención de commits:
- feat: nueva funcionalidad
- fix: corrección de error
- test: pruebas
- docs: documentación

Ejemplo:
feat: implementar endpoint POST productos (INV-01)

---

## Definition of Done aplicado

Una historia se considera terminada cuando:

- Código subido a rama dev
- Pull Request aprobado
- Pruebas pasan correctamente
- Criterios de aceptación verificados
- Historia movida a Done en Jira

---

## Avance funcional alcanzado

Durante el Sprint 1 se logró:

- Registro de nuevos productos
- Registro de movimientos de entrada y salida
- Actualización automática del stock
- Consulta básica del inventario
