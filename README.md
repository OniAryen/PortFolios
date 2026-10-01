# TechnoCell — Excel Data Analysis Portfolio

![Excel](https://img.shields.io/badge/Microsoft_Excel-Intermediate/Advanced%2B-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white)
![Status](https://img.shields.io/badge/Status-Completed-success?style=for-the-badge)

## Contexto del Proyecto

Este repositorio contiene un caso de estudio simulado de análisis de datos para **TechnoCell**, una empresa minorista de tecnología. El objetivo principal es demostrar el dominio de modelado de datos, formulación dinámica, automatización de consultas, auditoría de rendimiento y creación de cuadros de mando (*dashboards*) ejecutivos interactivos utilizando Microsoft Excel.

El proyecto aborda la consolidación de ventas, el rastreo de cuotas comerciales y la evaluación del desempeño de la fuerza de ventas mediante arquitecturas de fórmulas escalables e inmunes a errores de referencia.

---

## Autor

- **Nombre:** Aryen Gabriel Arauz Castillo
- **Formación:** Estudiante de Ingeniería en Tecnologías de Información (ITI)
- **Institución:** Universidad Técnica Nacional (UTN), Sede del Pacífico

---

## Tecnologías y Funciones Aplicadas

El libro de trabajo está estructurado con las siguientes capacidades técnicas:

- **Búsqueda y Referenciación Dinámica:** `BUSCARV` (`VLOOKUP`), encadenado con `SI.ERROR` (`IFERROR`) para garantizar la integridad visual y evitar la propagación de errores (`#N/A`).
- **Lógica Condicional Avanzada:** `SI` (`IF`), `SI` anidado, `SUMAR.SI` (`SUMIF`) y `CONTAR.SI` (`COUNTIF`).
- **Estadística Descriptiva:** `PROMEDIO` (`AVERAGE`), `MAX`, `MIN`, `CONTARA` (`COUNTA`).
- **Modelado e Interactividad:**
  - Tablas Dinámicas (*Pivot Tables*) y Gráficos Dinámicos (*Pivot Charts*).
  - Segmentadores de Datos (*Slicers*) por región geográfica.
  - Validación de datos e implementación de formato condicional.
  - Diseño de KPI Cards / Dashboard Ejecutivo.

---

## Arquitectura del Libro (`.xlsx`)

El archivo `Portfolio_Intermediate_Excel_Aryen_Arauz.xlsx` está compuesto por 6 pestañas organizadas modularmente:

```text
├── Cover              # Ficha técnica del proyecto, autoría y objetivos.
├── Master Data        # Tablas de referencia inmutables (Catálogo de Productos y Directorio de Vendedores).
├── Sales Sheet        # Log de 40 transacciones de ventas con automatización de precios y cálculos totales.
├── Performance Level  # Matriz de evaluación de vendedores (cuotas, niveles de desempeño y estadísticas globales).
├── Dashboard          # Cuadro de mando interactivo con KPIs automatizados, tabla/gráfico dinámico y Slicer.
└── Methodology        # Documentación técnica paso a paso de las fórmulas e implementación.
