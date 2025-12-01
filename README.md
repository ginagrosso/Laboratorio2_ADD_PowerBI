#  Laboratorio 2: Business Intelligence con Power BI

Este repositorio contiene la entrega final del segundo laboratorio de la especialización en **Data Analytics**. El proyecto consiste en un proceso integral de Business Intelligence (BI) aplicado a un dataset de ventas, desde la ingesta de datos hasta la visualización interactiva.

##  Objetivos del Proyecto
El objetivo principal fue transformar datos crudos en información valiosa para la toma de decisiones, cumpliendo con los siguientes hitos:
* Realizar un proceso **ETL** (Extracción, Transformación y Carga) para limpiar y normalizar múltiples fuentes de datos.
* Diseñar un **Modelo de Datos Relacional** eficiente (Esquema Copo de Nieve).
* Implementar cálculos avanzados utilizando **DAX** e Inteligencia de Tiempo.
* Construir un **Dashboard interactivo** que permita el análisis visual de KPIs.

##  Tecnologías y Herramientas
* **Power BI Desktop**: Herramienta principal de desarrollo.
* **Power Query**: Para la limpieza, normalización de texto y corrección de formatos regionales.
* **DAX**: Para la creación de medidas explícitas y tablas calculadas.

##  Contenido del Repositorio

### 1. Informe Power BI (`.pbix`)
El archivo **`Laboratorio2_PowerBI.pbix`** es el entregable principal. Contiene:
* **Conexiones de datos** a las 4 fuentes CSV.
* **Pasos de transformación** aplicados en Power Query.
* **Modelo de Datos** con relaciones configuradas y tabla Calendario.
* **Medidas DAX** para Ventas Totales, Cantidad de Pedidos y Ticket Promedio.
* **Dashboard** con mapa, gráficos de tendencia y segmentadores.

### 2. Documentación (`.pdf`)
El archivo **`Informe_Laboratorio2.pdf`** detalla el proceso técnico, justificando las decisiones tomadas durante el ETL y el modelado.

### 3. Fuentes de Datos (`.csv`)
Se incluyen los archivos originales utilizados para asegurar la reproducibilidad del proyecto:
* `orders.csv`: Tabla de hechos con transacciones.
* `accounts.csv`: Tabla dimensional de clientes.
* `sales_reps.csv`: Tabla dimensional de vendedores.
* `region.csv`: Tabla dimensional de regiones.

##  Características del Dashboard
El panel de control permite responder preguntas de negocio clave:
* **¿Dónde vendemos más?** Visualización geoespacial mediante mapa de burbujas.
* **¿Cuál es la tendencia?** Análisis temporal de ventas por año y mes.
* **¿Quién rinde mejor?** Comparativa de ventas por región.
* **Segmentación:** Capacidad de filtrar todo el informe según el tamaño del pedido (Grande/Mediano/Pequeño).

---
**Informatorio 2025 - Especialización en Data Analytics**
**Alumno:** Gina Grosso
