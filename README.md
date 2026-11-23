 VetPluas Móvil — Control de Inventario Farmacéutico y Citas

**Proyecto Áulico de Programación Móvil (DSHI-314)**  
**Carrera de Desarrollo de Software · Instituto Superior Tecnológico Guayaquil**  
**Período:** 2026-S2 · Paralelo C  
**Docente:** Mgtr. Luis Alberto Constante Navarro  
**Estudiante / Desarrollador:** Elias Daniel Pluas Mazzini ([@danielpluasm27-oss](https://github.com/danielpluasm27-oss))

---

 1. Descripción del Proyecto
VetPluas Móvil es una aplicación nativa para Android desarrollada en Kotlin que moderniza la gestión operativa de **Veterinaria Pluas**, un centro veterinario y farmacéutico ubicado en la Calle 29 y Callejón Parra (Guayaquil). 

La aplicación resuelve la falta de control de inventario de medicamentos en percha y la descoordinación en la reserva de turnos de peluquería canina, sustituyendo los apuntes manuales en cuaderno por una plataforma móvil intuitiva con interfaces adaptadas para celular y tablet.

---

 2. Objetivos

### Objetivo General
Desarrollar una aplicación móvil nativa en Android con Kotlin que permita gestionar el inventario de fármacos, el registro de citas veterinarias y la comunicación directa con el cliente en la Veterinaria Pluas, para reducir las pérdidas de productos y mejorar la eficiencia en la atención diaria.

### Objetivos Específicos
1. **Avance 1 (11 dic 2026):** Diseñar e implementar las interfaces adaptadas para smartphone y tablet (`sw600dp`) con un catálogo interactivo con `RecyclerView` e integración de `Intent` implícito de notificación directa vía WhatsApp al cliente.
2. **Avance 2 (15 ene 2027):** Construir la capa de persistencia local offline mediante SQLite (Room) con operaciones CRUD completas y validaciones en formularios.
3. **Producto Final (10-12 feb 2027):** Integrar el consumo de un servicio web REST y reporte de balance diario de ventas con manejo de fallas de red.

---

 3. Integrante y Roles
- **Elias Daniel Pluas Mazzini:**
  - Coordinación y gestión del repositorio.
  - Diseño de interfaces y layouts adaptativos (`XML` / `ConstraintLayout`).
  - Lógica de negocio y persistencia de datos (`Kotlin` / `Room`).

---

 4. Entregables y Estado por Avance

| Avance | Fecha | Estado | Entregable principal |
| :--- | :---: | :---: | :--- |
| **Propuesta Inicial** | 22 Nov 2026 | ✅ Entregada | Documento de propuesta institucional aprobado y repositorio inicializado. |
| **Avance 1** | 11 Dic 2026 | 🟡 En Desarrollo | Release `v0.1`, 4 pantallas adaptadas (celular y tablet), `RecyclerView`, Intent implícito y video de 3 min. |
| **Avance 2** | 15 Ene 2027 | ⚪ Pendiente | Release `v0.2`, Persistencia con Room/SQLite, CRUD y validaciones. |
| **Producto Final** | 10-12 Feb 2027 | ⚪ Pendiente | Release `v1.0`, Consumo de API REST, APK instalable y defensa oral. |

---

 5. Especificaciones Técnicas
- **Lenguaje:** Kotlin
- **IDE:** Android Studio Rabbit 2 (2026.2.2)
- **SDK Mínimo:** Android 8.0 (API 26)
- **Compile / Target SDK:** Android 14+ (API 37)
- **Diseño UI:** ConstraintLayout, Material Components 3, soporte responsivo `res/layout` y `res/layout-sw600dp`.
- **Integraciones:** Intent implícito hacia WhatsApp Messenger (`ACTION_VIEW`) y llamadas telefónicas (`ACTION_DIAL`).

---

 6. Declaración de Autoría y Uso de Inteligencia Artificial
En cumplimiento con las normas académicas de la asignatura DSHI-314:
- El código fuente de esta aplicación es de autoría propia de **Elias Daniel Pluas Mazzini**.
- Se utilizó Inteligencia Artificial (asistente Antigravity / Gemini) de manera declarada exclusivamente como apoyo formativo para el formateo de documentación, refinamiento de redacción de requerimientos y depuración conceptual.
- El estudiante comprende y está en plena capacidad de defender individualmente cada línea de código y decisión técnica ante el docente en la sustentación oral.
