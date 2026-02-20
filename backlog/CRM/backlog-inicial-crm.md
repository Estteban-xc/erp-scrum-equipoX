# Backlog Inicial – Módulo CRM

## 1. Visión del Módulo

Para empresas que necesitan gestionar la información de sus clientes y mantener relaciones comerciales organizadas,  
nuestro módulo CRM permite registrar, actualizar, eliminar y generar reportes de clientes dentro del ERP,  
facilitando el control comercial y la toma de decisiones estratégicas.

---

## 2. Épica Principal

### Gestión de Clientes

Como organización  
Queremos administrar la información de nuestros clientes  
Para mejorar la trazabilidad y el análisis comercial.

---

## 3. Historias de Usuario

---

## EIE-1 – Registrar Cliente

**Historia:**

Como usuario del sistema  
Quiero registrar un cliente  
Para gestionar su información y relaciones comerciales  

**Criterios de Aceptación (Gherkin):**

Dado que el usuario está en el formulario de registro  
Cuando ingresa los datos válidos y guarda  
Entonces el sistema registra el cliente y muestra confirmación  

---

## EIE-2 – Editar Cliente

**Historia:**

Como usuario del sistema  
Quiero editar un cliente  
Para mantener actualizada su información  

**Criterios de Aceptación (Gherkin):**

Dado que el cliente existe  
Cuando el usuario modifica los datos y guarda  
Entonces el sistema actualiza la información correctamente  

---

## EIE-3 – Eliminar Cliente

**Historia:**

Como usuario del sistema  
Quiero eliminar un cliente  
Para retirar clientes inactivos o duplicados  

**Criterios de Aceptación (Gherkin):**

Dado que el cliente existe  
Cuando el usuario confirma la eliminación  
Entonces el sistema elimina el cliente y notifica al usuario  

---

## EIE-11 – Generar Reporte de Clientes

**Historia:**

Como usuario del sistema  
Quiero generar un reporte de clientes  
Para analizar la cartera y las relaciones comerciales  

**Criterios de Aceptación (Gherkin):**

Dado que existen clientes registrados  
Cuando el usuario solicita generar el reporte  
Entonces el sistema genera un reporte con la información consolidada  

---

## 4. Priorización Inicial

| ID | Historia | Prioridad |
|----|----------|-----------|
| EIE-1 | Registrar Cliente | Alta |
| EIE-2 | Editar Cliente | Alta |
| EIE-3 | Eliminar Cliente | Media |
| EIE-11 | Generar Reporte de Clientes | Media |

---

## 5. Definition of Ready (DoR)

Una historia está lista para desarrollo cuando:

- Tiene formato "Como – Quiero – Para"
- Tiene criterios de aceptación claros
- Está priorizada
- Está estimada
- No tiene dependencias bloqueantes
- Está aprobada por el Product Owner

---

## 6. Definition of Done (DoD)

Una historia se considera terminada cuando:

- Está desarrollada en una rama feature/EIE-XX-descripcion
- Tiene Pull Request aprobado hacia develop
- Cumple todos los criterios de aceptación
- Fue probada funcionalmente
- Figma y diagramas están actualizados (si aplica)
- Está movida a Done en el tablero Scrum
- Tiene commits trazables con referencia a la historia
