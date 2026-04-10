# Proyecto Módulo 4 - Análisis Exploratorio de Datos para Decisiones Comerciales

## Descripción
Proyecto de análisis exploratorio de datos (EDA) aplicado a un caso de e-commerce, desarrollado con Python. El trabajo aborda la generación y exploración de un dataset comercial, estadística descriptiva, detección de outliers, análisis de correlación, regresión lineal y visualizaciones avanzadas con Seaborn y Matplotlib para apoyar decisiones estratégicas.

## Objetivo
Aplicar técnicas de análisis exploratorio de datos sobre un conjunto de variables comerciales y de comportamiento de clientes, con el fin de identificar patrones, relaciones relevantes, valores atípicos y segmentos de mayor valor, entregando hallazgos útiles para la toma de decisiones en ventas y marketing.

## Tecnologías utilizadas
- Python
- Pandas
- NumPy
- Seaborn
- Matplotlib
- statsmodels
- scikit-learn

## Estructura del proyecto
- `data/raw/`: dataset base utilizado en el análisis
- `data/interim/`: archivos intermedios del proceso analítico
- `data/processed/`: archivos procesados o consolidados
- `notebooks/`: notebook principal del proyecto
- `notebooks/outputs/`: gráficos exportados en PNG y PDF
- `docs/`: informe técnico final
- `README.md`: descripción general del proyecto

## Desarrollo del proyecto
El notebook principal se organiza en seis etapas:

1. Generación del dataset e inspección inicial  
2. Estadística descriptiva  
3. Correlación  
4. Regresiones lineales  
5. Análisis visual con Seaborn  
6. Visualizaciones finales con Matplotlib  

## Principales hallazgos
- El segmento **Premium** presenta el mayor monto promedio de compra.
- El segmento **Oro** también muestra un desempeño superior al de Plata y Bronce.
- Las variables `visitas_sitio`, `tiempo_sitio_min`, `compras_realizadas` y `monto_total` muestran relaciones positivas relevantes.
- La variable `dias_desde_ultima_compra` presenta relaciones negativas con actividad transaccional y satisfacción.
- El modelo de regresión múltiple obtuvo un mayor poder explicativo que el modelo simple.
- El canal **Instagram** mostró el mayor monto promedio dentro del análisis realizado.

## Archivos principales
- `notebooks/proyecto_modulo_4_eda.ipynb`
- `outputs/pairplot_variables_comerciales.png`
- `outputs/violinplot_monto_segmento.png`
- `outputs/jointplot_visitas_monto.png`
- `outputs/heatmap_correlaciones.png`
- `outputs/facetgrid_compras_monto.png`
- `outputs/boxplot_monto_canal.png`
- `outputs/dashboard_ejecutivo_matplotlib.png`
- `outputs/dashboard_ejecutivo_matplotlib.pdf`
- `outputs/scatter_anotado_visitas_monto.png`
- `outputs/scatter_anotado_visitas_monto.pdf`
- `outputs/distribuciones_finales_matplotlib.png`
- `outputs/distribuciones_finales_matplotlib.pdf`

## Resultados
El proyecto permitió construir un análisis exploratorio integral con foco técnico y comercial, transformando datos en evidencia útil para comprender mejor el comportamiento de los clientes y apoyar decisiones de segmentación, retención, fidelización y captación.

## Autor
Juan Carlos Castro Encina
