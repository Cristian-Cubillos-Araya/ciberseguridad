# 🧭 Proyecto: Implementación de un Sistema de Gestión de Seguridad de la Información (SGSI)

**Duración:** 4 semanas  
**Enfoque:** ISO 27001 / ISO 27002 / NIST / Ciberseguridad aplicada  
**Modalidad:** Trabajo grupal práctico-teórico  

---

## Objetivo General
Diseñar, implementar y auditar un Sistema de Gestión de Seguridad de la Información (SGSI) en una empresa hipotética, considerando tanto la seguridad de la información como la ciberseguridad técnica.

---

## Semana 1 — Fundamentos y Diagnóstico

### Objetivo
Comprender los principios de la gestión de seguridad de la información y realizar un diagnóstico inicial de una empresa ficticia.

### Contenidos
- Conceptos de **Seguridad de la Información vs Ciberseguridad**  
- Introducción a **ISO 27001** (requisitos del SGSI)  
- **ISO 27002:** Controles y buenas prácticas  
- **NIST Cybersecurity Framework:** Identificar, Proteger, Detectar, Responder, Recuperar  

### Actividades
1. **Definir la empresa ficticia:**  
   - Nombre, rubro, tamaño, infraestructura, datos sensibles.  
2. **Identificar activos de información:**  
   - Equipos, servidores, software, bases de datos, información crítica, personal, procesos.  
3. **Clasificar los activos:**  
   - Según criticidad, confidencialidad, integridad, disponibilidad.  
4. **Identificar amenazas y vulnerabilidades.**

### Entregable
- Documento de **Inventario y Clasificación de Activos**  
- **Mapa de Riesgos inicial (Matriz de Riesgos)**  

---

## Semana 2 — Diseño del SGSI

### Objetivo
Planificar la estructura de seguridad de la empresa según ISO 27001 e ISO 27002.

### Contenidos
- Ciclo **PDCA (Plan-Do-Check-Act)**  
- **Política de Seguridad de la Información**  
- **Comité de Seguridad de la Información**  
- Controles de ISO 27002 (acceso, comunicaciones, continuidad, etc.)  

### Actividades
1. Elaborar una **Política de Seguridad**.  
2. Diseñar la estructura organizativa del **Comité de Seguridad**.  
3. Asignar roles y responsabilidades (Administrador, Oficial de Seguridad, Usuarios, etc.).  
4. Desarrollar **políticas y procedimientos específicos**, por ejemplo:  
   - Control de acceso  
   - Uso aceptable de recursos  
   - Gestión de incidentes  
   - Backup y recuperación  
   - Seguridad en dispositivos extraíbles  
5. Asociar cada política a los **controles ISO 27002** correspondientes.

### Entregable
- **Plan de Seguridad de la Información** completo  
- **Mapa de controles vs políticas (ISO 27002)**  

---

## Semana 3 — Implementación técnica (Windows Server)

### Objetivo
Aplicar políticas de seguridad en un entorno técnico controlado.

### Contenidos
- Introducción a **Active Directory** y **Group Policy Objects (GPO)**  
- Control de usuarios y permisos  
- Buenas prácticas de endurecimiento de sistemas  

### Actividades
1. **Levantar Windows Server** (virtualizado o físico).  
2. Crear **3 perfiles de usuario:**  
   - Administrador (control total)  
   - Usuario intermedio (uso limitado, sin instalación)  
   - Usuario básico (sólo lectura, sin ejecución de .exe ni acceso a USB).  
3. Aplicar **GPOs de seguridad:**  
   - Bloquear ejecución de .exe  
   - Deshabilitar lectura/escritura de USB  
   - Control de contraseñas seguras  
   - Auditoría de inicio/cierre de sesión  
4. Documentar la configuración de seguridad aplicada.  

### Entregable
- **Informe técnico de configuración**  
- **Capturas de políticas GPO implementadas**  

---

## Semana 4 — Auditoría, Contingencia y Mejora

### Objetivo
Evaluar, auditar y fortalecer el SGSI implementado.

### Contenidos
- Auditoría interna del SGSI (ISO 27001)  
- Planes de contingencia y continuidad operacional  
- Plan de mejora continua  

### Actividades
1. Realizar una **auditoría simulada**:  
   - Aplicar checklist basado en la **matriz de riesgos y controles**.  
   - Identificar no conformidades.  
2. Elaborar un **Plan de Contingencia** para activos críticos.  
3. Generar un **informe de auditoría final**, con hallazgos y recomendaciones.

### Entregable
- **Checklist de auditoría**  
- **Plan de contingencia y mejora**  
- **Informe final del SGSI implementado**  

---

## Herramientas Sugeridas
- Microsoft Windows Server  
- VirtualBox / VMware  
- Microsoft Excel / Google Sheets (matriz de riesgo, checklist)  
- Draw.io / Lucidchart (diagramas del SGSI)  
- ISO 27001:2022, ISO 27002:2022, NIST CSF (documentación de referencia)

---

## Criterios de Evaluación

| Criterio | Ponderación |
|-----------|--------------|
| Diagnóstico y análisis de riesgos | 20% |
| Diseño del SGSI y políticas | 25% |
| Implementación técnica en servidor | 25% |
| Auditoría y plan de contingencia | 20% |
| Presentación y documentación final | 10% |

---
