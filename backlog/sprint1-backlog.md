# Sprint 1 – Backlog

## Objetivo del Sprint

Implementar el flujo básico del módulo de Inventario que permita:
- Registrar nuevos productos
- Registrar movimientos de entrada y salida
- Consultar el stock actualizado

El objetivo es entregar una funcionalidad mínima operativa para el usuario (jefe de almacén y operario).

---

## Historias seleccionadas

### INV-01 – Registrar nuevo producto
Como jefe de almacén quiero registrar un nuevo producto con código, descripción, unidad y stock inicial para tenerlo disponible en el sistema.

Story Points: 3  
Prioridad: Alta

---

### INV-02 – Registrar movimiento
Como operario quiero registrar una entrada o salida de stock para actualizar existencias tras una compra o venta.

Story Points: 5  
Prioridad: Alta

---

### INV-04 – Consultar inventario
Como jefe de almacén quiero consultar el stock actual por producto para tomar decisiones de reabastecimiento.

Story Points: 3  
Prioridad: Media

---

## Desglose técnico por historia

### INV-01 – Registrar producto

Tareas técnicas:
- Crear entidad Producto
- Crear endpoint POST /productos
- Validar campos obligatorios
- Guardar producto en base de datos
- Crear prueba unitaria básica

---

### INV-02 – Registrar movimiento

Tareas técnicas:
- Crear entidad Movimiento
- Crear endpoint POST /movimientos
- Validar cantidad positiva
- Validar stock suficiente en salidas
- Actualizar stock del producto
- Crear prueba unitaria básica

---

### INV-04 – Consultar inventario

Tareas técnicas:
- Crear endpoint GET /productos
- Implementar filtros por código y descripción
- Mostrar stock actual
- Crear prueba funcional básica

Actualización inicial 2 del Sprint 1.

---

## Total estimado del Sprint

Total Story Points comprometidos: 11 SP

