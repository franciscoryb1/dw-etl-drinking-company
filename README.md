# 📊 Data Warehouse y ETL para The Drinking Company

Repositorio académico del proyecto de **Bases de Datos II** orientado al diseño e implementación de un **Data Warehouse (DW)** con procesos **ETL** para una empresa ficticia de bebidas.

---

## 🎯 Propósito

Consolidar datos provenientes de múltiples fuentes en un **DW en SQL Server** y habilitar el análisis mediante **Power BI**, con foco en ventas, stock y precios.

---

## 🧱 Alcance

- Integración de fuentes **heterogéneas** (SQLite, Excel y TXT).
- **ETL con SSIS** para extracción, transformación y carga.
- **Modelo dimensional** con tablas de hechos y dimensiones.
- **Visualización** con dashboards y métricas en Power BI.

---

## 🛠 Tecnologías

- **Visual Studio 2022** (SSIS)
- **SQL Server** (almacenamiento y modelado del DW)
- **SQLite, Excel, TXT** (fuentes de datos)
- **Power BI** (visualización)

---

## 🗂 Estructura del repositorio

- **Paquetes SSIS** con los flujos ETL.
- **Scripts SQL** para creación y carga del esquema dimensional.
- **Archivos fuente** con datos de ventas, stock y precios.
- **Reporte Power BI** con métricas y visualizaciones.

---

## 🏢 Contexto del negocio

**The Drinking Company** es una empresa ficticia dedicada a la venta de bebidas. El DW integra:

- **Ventas**: transacciones históricas.
- **Stock**: movimientos y disponibilidad.
- **Precios**: variaciones por producto y período.
- **Catálogo**: atributos del producto (ml, tipo de envase, etc.).

---

## 🚀 Ejecución

1. Clonar el repositorio.
2. Abrir la solución en **Visual Studio 2022**.
3. Configurar conexiones a **SQL Server, SQLite, Excel y TXT**.
4. Ejecutar los **paquetes SSIS** para poblar el DW.
5. Abrir el **reporte en Power BI** para explorar los tableros.

---

## 👥 Autores

- **Francisco Ryb**
- **Lucía Masciángelo**

_Tecnicatura Universitaria en Inteligencia Artificial - FCEIA - UNR_
