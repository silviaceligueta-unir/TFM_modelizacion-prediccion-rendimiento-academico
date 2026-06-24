# TFM - Modelización y predicción del rendimiento académico mediante técnicas estadísticas y modelos de inteligencia artificial aplicados a datos longitudinales de grupos-clase

## Autores

- Andrea Campano Berrocal
- Silvia Celigueta Rebolé
- Eder García Martínez

## Contenido del repositorio

- `TFM_PredicciónDeNotas.ipynb`: notebook principal con todo el proceso de preparación de datos, análisis exploratorio, entrenamiento y evaluación de los modelos predictivos, así como la integración de un modelo de lenguaje mediante Ollama para la generación automática de informes.

## Requisitos

- Python 3.13
- Jupyter Notebook
- Librerías:
  - pandas
  - numpy
  - fsspec
  - matplotlib
  - seaborn
  - scikit-learn
  - xgboost
  - lightgbm
  - catboost
  - ollama

## Datos

Se incluye un archivo JSON donde se guardan las métricas obtenidas para utilizarlo como datos de entrada en Ollama; y el archivo .txt que incluye el informe generado.

Los conjuntos de datos utilizados en este trabajo no se incluyen en el repositorio, ya que han sido proporcionados exclusivamente para la realización del TFM.

## Reproducción

Para reproducir el análisis se debe:

1. Disponer de los conjuntos de datos originales.
2. Abrir el notebook `TFM_PredicciónDeNotas.ipynb`.
3. Ejecutar todas las celdas en orden.

**Nota**: para que la última parte del notebook funcione, es necesario tener instalado *Ollama* y disponer del modelo *Llama3*.
