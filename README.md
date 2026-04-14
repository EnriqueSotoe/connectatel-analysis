ConnectaTel Customer Analysis

Descripción del proyecto
Este proyecto analiza el comportamiento de los clientes de ConnectaTel, una empresa de telecomunicaciones en Latinoamérica, con el objetivo de identificar patrones de uso, segmentar clientes y generar recomendaciones estratégicas para el negocio.
El análisis se basa en datos de uso de servicios móviles (llamadas y mensajes) registrados hasta 2024.

Objetivos
Analizar el comportamiento de consumo de los usuarios
Detectar patrones y diferencias entre planes
Identificar segmentos de clientes
Encontrar oportunidades de mejora en la oferta comercial

Herramientas utilizadas
Python
Pandas
NumPy
Matplotlib
Seaborn
Jupyter Notebook

Limpieza de datos
Se realizaron las siguientes acciones:
Reemplazo de valores inválidos (age = -999) por la mediana
Estandarización de valores en city ("?") a valores nulos
Identificación de valores nulos como MAR (Missing At Random) en usage
Corrección de fechas fuera de rango (año 2026)

Análisis exploratorio
Se analizaron variables clave como:
Edad de los usuarios
Cantidad de mensajes
Cantidad de llamadas
Minutos de llamada

Hallazgos principales:
La edad no influye significativamente en la elección del plan
Mensajes y llamadas no muestran diferencias claras entre planes
Los minutos de llamada sí diferencian a los usuarios Premium
Se identificaron usuarios con consumo elevado (heavy users)

Outliers
Se detectaron outliers en variables de uso:
Mensajes
Llamadas
Minutos de llamada
Estos representan comportamientos reales (usuarios intensivos), por lo que no fueron eliminados.

Segmentación de clientes
Por nivel de uso:
Bajo uso
Uso medio
Alto uso
La mayoría de los usuarios pertenece a uso medio

Por edad:
Joven (<30)
Adulto (<60)
Adulto Mayor (≥60)
Predominan los adultos

Insights clave
El comportamiento de los usuarios depende más del nivel de uso que de la edad
Los minutos de llamada son el principal diferenciador entre planes
Existen heavy users que representan oportunidades comerciales
Los planes actuales no están claramente diferenciados en mensajes y llamadas

Recomendaciones
Diseñar planes específicos para usuarios de alto consumo
Crear estrategias para aumentar el uso en usuarios de uso medio
Evitar segmentación basada en edad
Mejorar la diferenciación entre planes Básico y Premium

Cómo ejecutar el proyecto
Clonar el repositorio
Abrir el notebook en Jupyter Notebook o Google Colab
Ejecutar todas las celdas
