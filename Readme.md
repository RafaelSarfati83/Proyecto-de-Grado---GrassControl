# Proyecto-de-Grado-GrassControl

**GrassControl**  
Es un sistema de Control y Trazabilidad para la Gestión de Praderas e Insumos Agropecuarios.  
El proyecto está desarrollado bajo un enfoque Low-Code utilizando AppSheet y Google Workspace.

---

## Descripción General

**GrassControl:** Es una solución digital diseñada para la optimización y estándar en el registro, en los seguimientos y consulta de las aplicaciones de agroquímicos y fertilizantes en praderas.

El sistema reemplaza las bitácoras físicas tradicionales expuestas a deterioro e inconsistencias generadas manualmente, el sistema permite la captura de datos en campo mediante dispositivos móviles, la automatización del almacenamiento en la nube y el control de los periodos de retiro para dar cumplimiento a las normativas de Buenas Prácticas Ganaderas (BPG) e ICA.

---

## Arquitectura y Diagramas del Sistema

### Arquitectura del Sistema
![Arquitectura GRASS CONTROL](assets/Arquitectura_GRASS_CONTROL.svg)

### Flujo e Integración Lógica
1. **Captura (Capa de Acceso):** Dispositivos móviles (Android/iOS) utilizados en campo por operadores y administradores.
2. **Lógica y Presentación (AppSheet):** Formulario dinámico, validaciones en tiempo real, alertas de tiempo de retiro y control de usuarios.
3. **Almacenamiento (Google Workspace):**
   - **Google Sheets:** Base de datos relacional (Praderas, Aplicaciones, Productos, Usuarios, Detalle).
   - **Google Drive:** Repositorio en la nube para respaldos y archivos adjuntos.

---

### Casos de Uso
![Casos de Uso GRASS CONTROL](assets/Casos_de_uso_GRASS_CONTROL.svg)

---

### Flujo de Registro y Cierre
![Flujo de Registro y Cierre GRASS CONTROL](assets/Flujo_registro_y_cierre_GRASS_CONTROL.svg)

---

### Modelo Lógico de Datos
![Modelo Lógico GRASS CONTROL](assets/Modelo_logico_GRASS_CONTROL.svg)

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
- `assets/`: Diagramas de arquitectura, casos de uso, flujo y modelo lógico (`.svg`)
- `Diccionario_de_datos_GRASS_CONTROL.pdf`: Especificación de datos del sistema
- `Manual_de_usuario_GRASS_CONTROL.pdf`: Guía operativa para el usuario
- `Nota_de_acc_restringido_GRASS_CONTROL.pdf`: Documento de confidencialidad y restricciones
- Documentación de análisis y diseño:
  - `Diagnostico.md`
  - `Requisitos.md`
  - `Metodologia.md`
  - `Modelo de datos.md`

---

## Declaración de Autoría y Originalidad

El diseño, configuración y desarrollo funcional de la aplicación GRASS CONTROL son de autoría propia. La documentación presentada fue elaborada a partir del análisis directo del aplicativo desarrollado en Google AppSheet. El proyecto cuenta con autorización de la empresa para su utilización con fines académicos y se conserva en un repositorio privado debido a la naturaleza corporativa de la información.

## 🎬 Video Demostrativo / Sustentación

Puedes ver la grabación y demostración completa del funcionamiento del sistema GRASS CONTROL en el siguiente enlace:

- 📽️ [Ver Video Demostrativo en Youtube]https://www.youtube.com/watch?v=AEfq7mlnWkE
