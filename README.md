## Descripción del Proyecto
Este proyecto esta creado para analizar el comportamiento de las temperaturas máximas en la ciudad de Culiacán, Sinaloa. El sistema extrae datos en tiempo real desde los servidores del Servicio Meteorológico Nacional (SMN) y la Comisión Nacional del Agua (CONAGUA), transformando registros en bruto en información estadística visual y analítica.

## Objetivos
* **Extracción Automatizada:** Uso de técnicas de scraping para obtener datos históricos sin intervención manual.
* **Procesamiento y Limpieza:** Depuración de información, manejo de valores nulos (NaN) y estandarización de formatos numéricos.
* **Análisis Estadístico:** Cálculo de medidas de tendencia central (media, mediana, moda) y dispersión (varianza, desviación estándar, rango).
* **Visualización de Datos:** Generación de histogramas, diagramas de caja (boxplots) y gráficos de dispersión para identificar patrones y valores atípicos (*outliers*).

## Tecnologías Utilizadas
* **Lenguaje:** Python
* **Entorno:** Jupyter Notebook / VS Code
* **Librerías Principales:**
    * `Pandas`: Manipulación y limpieza de estructuras de datos.
    * `Numpy`: Operaciones matemáticas y manejo de arreglos.
    * `Matplotlib`: Creación de visualizaciones estáticas.
