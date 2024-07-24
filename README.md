# Análisis de Riesgo de Sequía en Australia

## Descripción del Proyecto

Este proyecto tiene como objetivo analizar y predecir el riesgo de sequía en diversas regiones de Australia utilizando datos históricos meteorológicos. El análisis incluye la preprocesamiento de datos, ingeniería de características, y la aplicación de varios modelos de aprendizaje automático para tareas de regresión y clasificación. Las predicciones finales del modelo se visualizan mediante mapas interactivos para proporcionar una comprensión geográfica del riesgo de sequía.

## Tabla de Contenidos

1. [Descripción del Proyecto](#descripción-del-proyecto)
2. [Descripción de los Datos](#descripción-de-los-datos)
3. [Estructura del Proyecto](#estructura-del-proyecto)
4. [Instalación y Configuración](#instalación-y-configuración)
5. [Preprocesamiento de Datos](#preprocesamiento-de-datos)
6. [Modelado](#modelado)
7. [Resultados](#resultados)
8. [Visualización](#visualización)
9. [Conclusión](#conclusión)
10. [Trabajo Futuro](#trabajo-futuro)
11. [Licencia](#licencia)

## Descripción de los Datos

El conjunto de datos contiene información meteorológica recopilada de varias ubicaciones en Australia. Las características clave incluyen:

- **Fecha**: La fecha de observación.
- **Ubicación**: La ubicación de la estación meteorológica.
- **MinTemp**: La temperatura mínima registrada.
- **MaxTemp**: La temperatura máxima registrada.
- **Lluvia**: La cantidad de lluvia registrada.
- **Temp9am**: Temperatura a las 9 AM.
- **Temp3pm**: Temperatura a las 3 PM.
- **Latitud** y **Longitud**: Coordenadas geográficas de la ubicación.

El conjunto de datos se ha preprocesado para manejar valores faltantes, valores atípicos y datos no numéricos.

## Estructura del Proyecto

- `data/`: Contiene el conjunto de datos utilizado para el análisis.
- `notebooks/`: Jupyter Notebooks con análisis detallados de datos, preprocesamiento y entrenamiento de modelos.
- `src/`: Código fuente para procesamiento de datos e implementación de modelos.
- `visualizations/`: Incluye gráficos y mapas generados durante el análisis.
- `README.md`: Este archivo, proporcionando una visión general del proyecto.

## Instalación y Configuración

Para ejecutar el proyecto, necesitarás Python 3.x y las siguientes bibliotecas:

- pandas
- numpy
- scikit-learn
- seaborn
- matplotlib
- folium

Puedes instalar los paquetes necesarios usando:

```bash
pip install -r requirements.txt
