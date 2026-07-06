# ✈️ Proyecto de Análisis de Datos: Pipeline ETL y Modelado Data Vault 2.0 para Auditoría de Vuelos

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/14jBB_t4uzxGHspANWA_AqsQ2WbCJw64c?usp=sharing)

Este proyecto de **Análisis de Datos** fue creado por mí como parte de mi portafolio profesional en Data Engineering y Analytics. El objetivo principal es demostrar la capacidad de diseñar, construir y automatizar un flujo de datos (pipeline) escalable, desde la extracción de datos crudos hasta la generación de un modelo analítico avanzado directamente dentro del entorno de Google Colab.

## 📌 Contexto del Negocio

En el sector de la aviación, la puntualidad es crítica. Este proyecto audita un dataset masivo de operaciones aéreas para rastrear, estructurar y analizar las métricas de retrasos en vuelos. Al tener los datos correctamente modelados, es posible identificar cuellos de botella logísticos (por aerolínea o aeropuerto) y tomar decisiones estratégicas fundamentadas en datos.

## 🛠️ Stack Tecnológico y Arquitectura

Para resolver este desafío, implementamos metodologías avanzadas de ingeniería dentro de este notebook:
* **Lenguaje Core:** Python 3 (Pandas para procesamiento vectorial).
* **Ingesta Automatizada:** API nativa de Kaggle (`kagglehub`).
* **Arquitectura de Datos (Data Vault 2.0):** Implementación de algoritmos de encriptación (Hashes MD5) para separar los datos en *Hubs* (Entidades), *Links* (Relaciones) y *Satélites* (Contexto), garantizando un modelo auditable y escalable.
* **Visualización y Analytics Dinámico:** Uso de Plotly Express y Plotly Graph Objects para generar dashboards interactivos directamente en el entorno de ejecución.

## 🗺️ Fases del Pipeline (Hoja de Ruta)

El proceso se ejecuta de manera automatizada en el notebook:
1. **Aprovisionamiento e Ingesta:** Descarga automática desde la API de Kaggle.
2. **Preprocesamiento:** Estandarización de metadatos (schemas) y limpieza de nulos.
3. **Motor de Transformación:** Generación de llaves subrogadas y construcción del modelo Data Vault 2.0.
4. **Persistencia Física:** Empaquetado y exportación de los resultados en formato comprimido (ZIP).
5. **Master Dashboard Interactivo:** Analytics descriptivo avanzado (rankings, mapas de calor, y distribuciones de retrasos) integrado en el notebook.

## 🚀 Cómo Ejecutar el Proyecto

Puedes probar y visualizar todo el análisis de datos directamente en el **[notebook de Google Colab](https://colab.research.google.com/drive/14jBB_t4uzxGHspANWA_AqsQ2WbCJw64c?usp=sharing)** haciendo clic en el botón superior.

## 👨‍💻 Autor

* **Creado por:** Luis Armando Ramírez Cárdenas
* **Especialidad:** Análisis y Ingeniería de Datos
