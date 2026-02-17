#  Proyecto ERP — Taller Aplicado Scrum

> Módulos: **Inventario · Compras · Facturación · RR.HH.**
> Herramientas: Notion · Figma · GitHub Projects

---

##  Visión del Proyecto

Construir un sistema ERP modular que permita a los usuarios gestionar compras, inventario, facturación y recursos humanos de forma integrada, trazable y con entregas incrementales mediante metodología Scrum.

---

##  Equipo

| Rol | Responsable |
|-----|-------------|
| Product Owner (PO) | _(nombre)_ |
| Scrum Master (SM) | _(nombre)_ |
| Developer / UX | _(nombre)_ |
| Developer / QA | _(nombre)_ |
| Developer | _(nombre)_ |

---

##  Módulos del ERP

| Módulo | Épica principal | Estado |
|--------|----------------|--------|
| 🛒 Compras | Solicitud, orden de compra, recepción | En progreso |
| 📦 Inventario | Altas/bajas, movimientos, stock | En progreso |
| 🧾 Facturación | Emisión, impuestos, pagos | En progreso |
| 👤 RR.HH. | Nómina simplificada, ausencias | En progreso |

---


##  Backlog y Gestión

- 📊 **Tablero Notion:** _(enlace al tablero)_
- 🗃️ **GitHub Projects:** _(enlace al proyecto)_

### Columnas del Tablero Kanban

| Columna | Límite WIP | Color |
|---------|-----------|-------|
| Backlog | — | Gris |
| To Do | — | Azul |
| In Progress | 3 por equipo | Amarillo |
| In Review | 2 por equipo | Naranja |
| Testing | 2 por equipo | Morado |
| Done | — | Verde |

---

##  Diseño UX/UI

- **Figma (Wireframes low-fi):** _(enlace a Figma)_
- Pantallas cubiertas en Sesión 2:
  - Formularios de registro (Inventario, Compras)
  - Vistas de lista con filtros
  - Flujos de entrada/salida de stock
  - Formulario de emisión de factura

---

##  Arquitectura

### Diagramas PlantUML disponibles

| Diagrama | Archivo | Descripción |
|----------|---------|-------------|
| Contexto del sistema | `diagrams/contexto.puml` | Actores externos, ERP core, DB, servicios |
| Componentes | `diagrams/componentes.puml` | UI, API, dominio, persistencia, integración |
| Secuencias (por módulo) | `diagrams/secuencias/` | Flujos con validaciones y errores |

### Architecture Decision Records (ADR)

| ID | Decisión | Estado |
|----|----------|--------|
| ADR-01 | Lenguaje y framework backend | _(borrador)_ |
| ADR-02 | Estrategia de persistencia (DB) | _(borrador)_ |
| ADR-03 | Patrón arquitectónico (ej. hexagonal) | _(borrador)_ |

> Ver detalle en `/docs/ADR/`

---

##  Definition of Ready (DoR)

Una historia está lista para el sprint si cumple:

- [ ] Valor claro y usuario identificado
- [ ] Criterios de aceptación completos en Gherkin
- [ ] Wireframe/prototipo en Figma enlazado
- [ ] Diagrama PlantUML inicial (componente o secuencia)
- [ ] Datos de prueba definidos
- [ ] Estimación en story points acordada

---

##  Definition of Done (DoD)

Una historia está terminada si cumple:

- [ ] Código en rama principal con PR aprobada
- [ ] Pruebas unitarias y funcionales pasan
- [ ] Criterios de aceptación verificados en demo
- [ ] Figma y PlantUML actualizados si hubo cambios
- [ ] Documentación en repositorio
- [ ] Historia movida a "Done" en tablero

---


### Checklist de PR

- [ ] Compila sin errores
- [ ] Pruebas pasan
- [ ] Criterios de aceptación cumplidos
- [ ] Diseño Figma actualizado (si aplica)
- [ ] Diagrama PlantUML actualizado (si aplica)
- [ ] Revisado por al menos 1 compañero

---

## 📅 Agenda de Sesiones

| Sesión | Enfoque | Estado |
|--------|---------|--------|
| 1 | Kickoff, visión, backlog inicial | ✅ Completada |
| 2 | Arquitectura y UX inicial | 🔄 En curso |
| 3 | Sprint Planning 1 + ejecución | ⏳ Pendiente |
| 4 | Daily coaching + diseño detallado | ⏳ Pendiente |
| 5 | Review + Retro 1 + Planning 2 | ⏳ Pendiente |
| 6 | Ejecución Sprint 2 + Demo final | ⏳ Pendiente |

---

##  Métricas del Sprint

> Se actualizan al cierre de cada sprint.

- **Stories completadas:** —
- **Story points entregados:** —
- **Defectos encontrados:** —
- **Burndown:** _(enlace o imagen)_

---


