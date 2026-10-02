# 🚨 Panel de Inteligencia de Emergencias ECU 911 (Big Data & BI)

![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![Data](https://img.shields.io/badge/Data-11.3M%20Registros-success?style=for-the-badge)

## 📌 Contexto del Proyecto
Desarrollo de un modelo analítico avanzado y un "Explorador de Emergencias" interactivo para el ECU 911. El objetivo fue procesar y estructurar un volumen histórico masivo para agilizar la toma de decisiones directivas a nivel nacional, abarcando 24 provincias y 7 tipos de servicios durante el periodo 2023-2026.

## ⚙️ Arquitectura de Datos y Modelado (DAX)
* **ETL y Big Data:** Procesamiento, limpieza y modelado relacional de **11.33 millones de registros** utilizando Power Query.
* **Métricas Estratégicas (DAX):** Desarrollo de KPIs orientados a la evaluación de riesgos, incluyendo:
  * Riesgo Anual por Habitante (emergencias por cada 100,000 habitantes).
  * Tasas de variación interanual.
  * Análisis de carga operativa.

## 📊 Hallazgos Críticos y Diseño UX/UI
* **Insights de Seguridad:** Se evidenció estadísticamente que la "Seguridad Ciudadana" concentra más del 67% de los incidentes (destacando 2.80 millones de incidentes solo por "Patrullaje policial").
* **Interfaz de Usuario:** Creación de navegación jerárquica (Provincia > Cantón > Servicio > Subtipo).
* **Visualizaciones Complejas:** Implementación de "Radiografía de Riesgo Cantonal" mediante gráficos de dispersión y matrices de estacionalidad.

## 📂 Estructura de este Repositorio
- `/data`: Diccionario de datos y muestra representativa.
- `/dashboards`: Archivo `.pbix` original del proyecto.
- `/docs`: Diapositivas de la defensa ejecutiva del modelo y capturas de pantalla del dashboard.

---
*Este proyecto formó parte de una simulación de licitación corporativa para la ESPOL, defendiendo la viabilidad técnica y estratégica frente a un jurado evaluador en un pitch de 5 minutos.*
