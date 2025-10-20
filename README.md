---
# Dashboard de Energía Eólica en Colombia

Este es un dashboard interactivo desarrollado con Streamlit para visualizar y analizar datos relacionados con el potencial y desarrollo de la energía eólica en Colombia. La aplicación permite explorar la información a través de métricas clave, gráficos dinámicos y un mapa interactivo.

## Descripción

El objetivo de este proyecto es ofrecer una herramienta visual para entender la distribución y las características del potencial eólico en el país. Los usuarios pueden filtrar los datos por departamento y categoría, y explorar las relaciones entre diferentes métricas a través de visualizaciones interactivas.

## Características Principales

La aplicación está organizada en varias secciones navegables:

### **Página de Inicio**
### **Análisis Descriptivo**
- **Filtros Globales**: Permite filtrar los datos por `Departamento` y `Categoría` para un análisis más específico.
- **Visualización de Datos**: Muestra los datos filtrados en una tabla expandible.
- **Gráficos Dinámicos**:
    - **Box Plot**: Para entender la distribución de valores por categoría.
    - **Gráfico de Barras**: Muestra el valor promedio por departamento.
- **Estadísticas Detalladas**:
    - **Análisis por Categoría**: Tabla con estadísticas descriptivas (media, desviación estándar, etc.).
    - **Matriz Comparativa**: Una tabla pivote y un mapa de calor (heatmap) que comparan los valores promedio entre departamentos y categorías.
    - **Análisis de Correlación**: Un gráfico de dispersión (scatter plot) para visualizar la correlación entre dos categorías seleccionadas.

### **Mapa Interactivo**
- **Visualización Geográfica**: Un mapa de Colombia (creado con Folium) que muestra la ubicación de los datos.
- **Capas de Visualización**: Permite cambiar entre diferentes vistas:
    - **Marcadores**: Puntos en el mapa cuyo tamaño varía según el valor.
    - **Mapa de Calor (Heatmap)**: Muestra la concentración de datos.
    - **Clusters**: Agrupa marcadores cercanos para una visualización más limpia.
- **Filtro por Categoría**: Permite seleccionar qué categoría específica se desea visualizar en el mapa.

## Tecnologías Utilizadas

- **Python**: Lenguaje de programación principal.
- **Streamlit**: Framework para la creación de la aplicación web.
- **Pandas**: Para la manipulación y análisis de datos.
- **Plotly Express**: Para la generación de gráficos interactivos.
- **Folium**: Para la creación de mapas interactivos.
- **Docker**: Para la contenerización y despliegue de la aplicación.

## Estructura del Proyecto

```
.
├── Dockerfile
├── requirements.txt
├── streamlit_app.py
└── energia_eolica.csv
```


## Fuente de Datos

Los datos utilizados en esta aplicación provienen del siguiente repositorio:
*   **GitHub - Datos_DATAVIZ**: [https://github.com/Kalbam/Datos_DATAVIZ](https://github.com/Kalbam/Datos_DATAVIZ)
