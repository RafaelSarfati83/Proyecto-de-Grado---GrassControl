Modelo de Datos (Estructura Relacional)

La base de datos está estructurada en Google Sheets mediante las siguientes tablas y relaciones:

1. Tabla: Usuario
- ID_Usuario (Clave Primaria)
- Nombre
- Rol (Administrador / Operador)
- Correo

2. Tabla: Pradera
- ID_Pradera (Clave Primaria)
- Nombre_Potrero
- Area_Hectareas
- Ubicacion

3. Tabla: Producto
- ID_Producto (Clave Primaria)
- Nombre_Comercial
- Tipo (Agroquímico / Fertilizante)
- Periodo_Retiro_Dias

4. Tabla: Aplicacion
- ID_Aplicacion (Clave Primaria)
- ID_Pradera (Clave Foránea)
- ID_Usuario (Clave Foránea)
- Fecha_Hora
- Agua_Utilizada_Lts
- Estado (Abierto / Cerrado)

5. Tabla: Detalle_Aplicacion
- ID_Detalle (Clave Primaria)
- ID_Aplicacion (Clave Foránea)
- ID_Producto (Clave Foránea)
- Dosis_Aplicada
