# Diseño de Pantallas – Módulo Inventario

## Lista de Productos

Permite visualizar todos los productos registrados.
Incluye:
- Código
- Descripción
- Unidad
- Stock actual
- Filtro por código o descripción

---

## Nuevo Producto

Formulario para registrar productos.
Campos:
- Código
- Descripción
- Unidad
- Stock inicial

Validaciones:
- Todos los campos obligatorios
- Stock debe ser número positivo

---

## Registro de Movimientos

Permite registrar entradas y salidas de inventario.

Campos:
- Tipo (Entrada / Salida)
- Producto
- Cantidad

Validaciones:
- Cantidad mayor a cero
- Stock suficiente en caso de salida

