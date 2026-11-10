ConnectaTel | Análisis de Datos de Telecomunicaciones con Python

Este repositorio contiene el análisis de datos desarrollado durante el Sprint 7, basado en el caso de estudio de ConnectaTel, una empresa de telecomunicaciones con operaciones en México y Colombia.

El proyecto tiene como propósito analizar el comportamiento de consumo de los clientes en los servicios móviles de llamadas y mensajes, identificando patrones de uso, comportamientos atípicos y diferencias entre segmentos de usuarios.

Mediante técnicas de exploración, limpieza y análisis de datos con Python, se busca generar información confiable que contribuya a optimizar la oferta comercial y mejorar la experiencia de los clientes.

📂 Contenido del repositorio

El análisis utiliza tres fuentes principales de información:

datasets/plans.csv: Información de los planes comerciales, incluyendo precios, minutos y datos móviles incluidos, así como costos por consumo adicional.
datasets/users_latam.csv: Información de los clientes, como edad, ciudad, fecha de registro y plan contratado.
datasets/usage.csv: Registro del consumo real de los usuarios, incluyendo duración de llamadas y cantidad de mensajes.

🧠 Objetivo del análisis

Explorar y analizar los patrones de consumo de los clientes de ConnectaTel para identificar diferencias en el comportamiento de uso de los servicios móviles y detectar oportunidades de mejora en la estrategia comercial.

🔍 Etapas del análisis

-Exploración de datos: Revisión de la estructura, dimensiones, tipos de variables y calidad de los datasets.
-Limpieza de datos: Identificación y tratamiento de valores nulos, duplicados, sentinels e inconsistencias.
-Tratamiento de outliers: Evaluación de valores extremos y análisis de su impacto en las distribuciones.
-Transformación de datos: Conversión de tipos de datos, estandarización y preparación de variables.
-Análisis exploratorio (EDA): Estudio de distribuciones, estadísticas descriptivas y patrones de consumo.
-Análisis por segmentos: Comparación del comportamiento de los usuarios según su ubicación y plan contratado.
-Generación de insights: Interpretación de resultados para identificar oportunidades de optimización comercial.

📘 Cómo reproducir el análisis

Clona o descarga este repositorio.
Abre el notebook S7 Version-Estudiante-Project-ConnectaTel.
Instala las librerías necesarias.
Ejecuta las celdas en orden.
El notebook carga los datasets desde la carpeta /data/ o desde un enlace público, según la configuración del proyecto.

🛠️ Herramientas y tecnologías

-Python: Procesamiento y análisis de datos.
-Pandas: Limpieza, transformación y manipulación de datasets.
-NumPy: Operaciones y validaciones numéricas.
-Matplotlib: Visualización de datos.
-Seaborn: Análisis de distribuciones y patrones de consumo.
-Jupyter Notebook: Desarrollo y documentación del análisis.

📈 Resultados del proyecto

El análisis permite construir una visión estructurada del comportamiento de los clientes, identificar problemas de calidad en las fuentes de información y explorar diferencias en los patrones de consumo de los servicios móviles.

Los resultados proporcionan una base para identificar segmentos de clientes, evaluar el uso de los planes comerciales y generar recomendaciones orientadas a mejorar la oferta de servicios.


