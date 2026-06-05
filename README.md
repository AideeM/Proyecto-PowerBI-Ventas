# Proyecto Power BI — Análisis de Ventas

Dashboard interactivo de 3 páginas para analizar tendencias de ventas por producto, región y sucursal, desarrollado con Power BI Desktop.

## Objetivo

Identificar patrones de comportamiento en ventas a lo largo del tiempo, comparar el desempeño entre regiones y sucursales, y detectar productos con mayor rotación, utilizando un dataset simulado de escenario retail.

## Contenido del repositorio

```
 proyecto-powerbi-ventas/
├──  Proyecto_Aide Muñoz.pbix      # Archivo Power BI (abrir con Power BI Desktop)
├──  data/
│   └── ventas_dataset.xlsx       # Dataset fuente (Excel)
└──  README.md
```

## Páginas del dashboard

| Página | Descripción |
|--------|-------------|
| 1. Tendencias por producto | Unidades vendidas por mes y categoría; análisis de estacionalidad |
| 2. Comparativa regional | Desempeño por sucursal y región; promedio de unidades por zona |
| 3. Detalle temporal | Desglose por año, trimestre y mes con drill-down interactivo |

## Proceso de desarrollo

1. **Limpieza de datos** — Transformación y normalización del dataset en Power Query
2. **Modelado** — Creación del modelo de datos y relaciones entre tablas
3. **Medidas DAX** — Cálculo de KPIs: suma de unidades, promedio por región, participación porcentual
4. **Visualizaciones** — Gráficas de barras, líneas y segmentadores interactivos
5. **Análisis** — Estacionalidad mensual, comparativa entre 10 sucursales y 4 regiones (2024–2026)

## Herramientas

![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=flat&logo=powerbi&logoColor=black)
![DAX](https://img.shields.io/badge/DAX-0078D4?style=flat&logo=microsoft&logoColor=white)
![Power Query](https://img.shields.io/badge/Power%20Query-217346?style=flat&logo=microsoft-excel&logoColor=white)
![Excel](https://img.shields.io/badge/Excel-217346?style=flat&logo=microsoft-excel&logoColor=white)

## Cómo abrir el proyecto

1. Descarga el archivo `Proyecto_Aide Muñoz.pbix`
2. Ábrelo con [Power BI Desktop](https://powerbi.microsoft.com/desktop/) (gratuito)
3. El dataset Excel ya está incluido como fuente de datos local

## Autora

**Aide Guadalupe Muñoz Palacio**
Estudiante de Ingeniería en Sistemas Computacionales — ITS Saltillo
