# sprint7-final-project

**📡 Análisis de Telecomunicaciones: Estrategia ConnectaTel**

**🎯 Objetivo del Proyecto**
El objetivo central de este análisis para ConnectaTel (operaciones en México y Colombia) es identificar patrones de uso y comportamientos atípicos en los servicios de llamadas y mensajes. Buscamos comprender las necesidades de los distintos segmentos de clientes para optimizar la oferta comercial y mejorar la experiencia del usuario final.

**📊 Datasets Utilizados**
Para construir esta visión 360°, integramos tres fuentes de datos principales:

plans.csv: Catálogo de planes, precios y beneficios de minutos/GB.

users_latam.csv: Información demográfica (edad, ciudad) y contractual de los clientes.

usage.csv: Detalle del uso real de servicios (duración de llamadas y longitud de mensajes).

**🛠️ Etapas del Análisis**
El proyecto se ejecutó siguiendo un flujo de trabajo de Ciencia de Datos:

Integración y Limpieza: Consolidación de fuentes y tratamiento de valores nulos (identificando un 92% de usuarios activos en la columna de churn).

Validación de Datos: Estandarización de tipos de datos y corrección de inconsistencias.

Perfilamiento Estadístico: Análisis de la distribución de uso por cliente y segmentos demográficos.

Detección de Outliers: Identificación de comportamientos atípicos mediante el método IQR y visualizaciones tipo Boxplot.

Segmentación Estratégica: Clasificación de usuarios por nivel de uso ('Bajo', 'Medio', 'Alto') y grupos de edad ('Joven', 'Adulto', 'Adulto Mayor').

Visualización e Insights: Generación de gráficos e informes para la toma de decisiones comerciales.

**💡 Insights de Negocio**
Segmentación de Uso: La mayoría de los clientes presentan un 'Bajo uso', lo que representa una oportunidad para crear planes de retención más económicos.

Comportamientos Atípicos: Se detectaron "Heavy Users" (outliers) que superan significativamente el promedio de consumo; estos usuarios son vitales para la rentabilidad por cargos de excedentes.

Perfil Demográfico: ConnectaTel posee una base de usuarios muy equilibrada en edad, lo que permite diversificar las campañas de marketing según las necesidades de cada generación.

**💻 Stack Tecnológico**
Lenguaje: Python

Librerías: Pandas, NumPy, Matplotlib, Seaborn

Entorno: Jupyter Notebook
