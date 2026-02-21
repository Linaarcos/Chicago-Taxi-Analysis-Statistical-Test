# 🚕 Análisis de Servicios de Taxi en Chicago: Impacto del Clima y Demanda

## 📝 Descripción del Proyecto
Este proyecto analiza el comportamiento del mercado de taxis en Chicago durante noviembre de 2017. El objetivo principal es identificar patrones de demanda por barrios y determinar si factores externos, como las condiciones climáticas, afectan significativamente la duración de los viajes desde el centro (The Loop) hasta el Aeropuerto Internacional O'Hare.

## 🎯 Objetivos Principales
1.  **Análisis de Flota:** Identificar las empresas de taxis con mayor volumen de viajes en fechas específicas.
2.  **Geolocalización de Demanda:** Determinar los 10 barrios principales donde finalizan los recorridos para entender los núcleos de actividad.
3.  **Análisis Predictivo/Estadístico:** Probar la hipótesis de que el clima lluvioso los días sábados altera la duración promedio de los viajes al aeropuerto.

## 🛠️ Tecnologías y Metodologías
* **SQL:** Recuperación y filtrado de datos desde bases de datos relacionales.
* **Python (Pandas, NumPy):** Procesamiento de datos y limpieza de tipos.
* **Matplotlib & Seaborn:** Visualización de la competitividad de empresas y popularidad de barrios.
* **Estadística Inferencial (SciPy):** Aplicación de **T-Test** para la validación de hipótesis climáticas.

## 📊 Hallazgos Clave
* **Top de Barrios:** Identificación de los sectores con mayor tráfico de pasajeros, permitiendo una optimización de la distribución de unidades.
* **Prueba de Hipótesis:** * **H0 (Nula):** La duración promedio de los viajes los sábados lluviosos es igual a la de los sábados despejados.
    * **H1 (Alternativa):** La duración promedio de los viajes cambia significativamente según el clima.
    * **Resultado:** Se determinó con un nivel de significancia (alpha) del 5% si el impacto de la lluvia es estadísticamente relevante para el negocio.

## 📂 Estructura del Repositorio
* `/datasets/`: Archivos CSV procesados (`project_sql_result_01.csv`, `04.csv`, `07.csv`).
* `chicago_taxi_analysis.ipynb`: Notebook con el proceso completo de limpieza, visualización y pruebas estadísticas.
