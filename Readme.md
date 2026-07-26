# Proyecto-de-Grado-GrassControl

**GrassControl**  
Es un sistema de Control y Trazabilidad para la Gestión de Praderas e Insumos Agropecuarios.  
El proyecto está desarrollado bajo un enfoque Low-Code utilizando AppSheet y Google Workspace.

---

## Descripción General

**GrassControl:** Es una solución digital diseñada para la optimización y estándar en el registro, en los seguimientos y consulta de las aplicaciones de agroquímicos y fertilizantes en praderas.

El sistema reemplaza las bitácoras físicas tradicionales expuestas a deterioro e inconsistencias generadas manualmente, el sistema permite la captura de datos en campo mediante dispositivos móviles, la automatización del almacenamiento en la nube y el control de los periodos de retiro para dar cumplimiento a las normativas de Buenas Prácticas Ganaderas (BPG) e ICA.

---

## Arquitectura del Sistema

![Arquitectura del Sistema](assets/arquitectura.png)

### Flujo e Integración Lógica
1. **Captura (Capa de Acceso):** Dispositivos móviles (Android/iOS) utilizados en campo por operadores y administradores.
2. **Lógica y Presentación (AppSheet):** Formulario dinámico, validaciones en tiempo real, alertas de tiempo de retiro y control de usuarios.
3. **Almacenamiento (Google Workspace):**
   - **Google Sheets:** Base de datos relacional (Praderas, Aplicaciones, Productos, Usuarios, Detalle).
   - **Google Drive:** Repositorio en la nube para respaldos y archivos adjuntos.

---

## Características Principales

- **Mobile-First:** Interfaz optimizada para el registro ágil en entorno de campo.
- **Trazabilidad Completa:** Captura automática de fecha/hora (timestamps), responsable, potrero, producto y dosis aplicadas.
- **Alertas de Periodo de Retiro:** Notificaciones preventivas para evitar el ingreso de ganado a potreros tratados antes del tiempo permitido.
- **Consultas e Históricos:** Filtros por pradera para auditorías e inspecciones de calidad.
- **Sincronización Automática:** Datos respaldados en la nube sin riesgo de pérdida por deterioro físico.

---

## Tecnologías Utilizadas

- **Plataforma Low-Code:** Google AppSheet
- **Base de Datos / Backend:** Google Sheets
- **Almacenamiento de Archivos:** Google Drive
- **Diseño y Control de Procesos:** Metodología Agile (Scrum)

---

## Estructura del Repositorio

- `README.md`: Documentación principal del proyecto
- `docs/`
  - `01-diagnostico.md`: Caracterización del proceso y hallazgos
  - `02-requisitos.md`: Requisitos Funcionales (RF) y No Funcionales (RNF)
  - `03-metodologia.md`: Gestión del proyecto por Sprints (Scrum)
- `assets/`
  - `arquitectura.png`: Diagrama de arquitectura / flujo del sistema
- `data/`
  - `modelo_datos.md`: Definición de entidades y relaciones

---

## Declaración de Autoría y Originalidad

El diseño, configuración y desarrollo funcional de la aplicación GRASS CONTROL son de autoría propia. La documentación presentada fue elaborada a partir del análisis directo del aplicativo desarrollado en Google AppSheet. El proyecto cuenta con autorización de la empresa para su utilización con fines académicos y se conserva en un repositorio privado debido a la naturaleza corporativa de la información.
