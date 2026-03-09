# Analisis de Ventas de Videojuegos

Este proyecto presenta un analisis del mercado global de videojuegos utilizando conjuntos de datos historicos. El objetivo principal es identificar patrones de exito comercial y tendencias de consumo que sirven como base para la toma de decisiones en futuros lanzamientos.

## Objetivo del Proyecto
Identificar las variables clave (**plataforma, genero y clasificacion**) que presentan mayor correlacion con las ventas globales para optimizar estrategias de marketing y planificacion comercial.

## Stack Tecnologico
* **Lenguaje:** Python 3.12.3
* **Librerias principales:**
    * **Pandas:** Limpieza y manipulacion de datos (ETL).
    * **Matplotlib & Seaborn:** Analisis visual y exploratorio de tendencias.
    * **NumPy:** Procesamiento numerico y operaciones vectorizadas.

## Metodologia y Hallazgos
El analisis se divide en las siguientes fases tecnicas:

1. **Limpieza de Datos:** Tratamiento de valores ausentes y normalizacion de tipos de datos, especificamente en las metricas de calificacion de usuarios y criticos (`user_score` / `critic_score`).
2. **Analisis por Plataforma:** Evaluacion del ciclo de vida de las consolas lideres y proyeccion de su vigencia en el mercado global.
3. **Perfil Regional:** Comparativa de habitos de consumo y generos preferidos en Norteamerica, Europa y Japon para identificar oportunidades de localizacion.
4. **Analisis de Correlacion:** Estudio del impacto de las reseñas de expertos sobre el volumen de ventas finales por region.

## Estructura del Repositorio
* `notebook.ipynb`: Desarrollo completo del analisis, desde la ingesta de datos hasta las conclusiones finales.
* `requirements.txt`: Lista de dependencias y versiones necesarias para la ejecucion del entorno.
* `README.md`: Documentacion tecnica del proyecto.

---
*Desarrollado como parte del programa de Data Analytics en TripleTen.*