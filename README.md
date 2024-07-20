# Análisis de Datos de Vino

Este proyecto realiza un análisis de datos de los vinos tinto y blanco utilizando conjuntos de datos provenientes de [UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/186/wine+quality). Los archivos de datos utilizados en este análisis son `winequality-red-cleaned.csv` y `winequality-white-cleaned.csv`.

## Descripción del Proyecto

Este proyecto tiene como objetivo analizar y comparar la calidad del vino tinto y blanco a partir de los siguientes pasos:

1. **Carga y Limpieza de Datos**
   - Los datos de vino blanco y vino tinto son cargados y limpiados, eliminando las comillas en los nombres de las columnas y normalizando las características.
   
2. **Análisis Exploratorio de Datos (EDA)**
   - **Distribución de la Calidad del Vino**: Se visualiza la distribución de la calidad del vino mediante histogramas y se calcula la media de calidad para cada tipo de vino.
   - **Matriz de Correlación**: Se analiza la correlación entre las diferentes características del vino.
   - **Diagramas de Dispersión**: Se explora la relación entre el contenido de alcohol y la calidad del vino.

3. **Modelado Predictivo**
   - Se divide el dataset en conjuntos de entrenamiento y prueba.
   - Se entrena un modelo de `RandomForestClassifier` para predecir la calidad del vino.
   - Se evalúa el modelo mediante un informe de clasificación y precisión.

4. **Comparación entre Vino Tinto y Blanco**
   - **Visualización de Distribuciones**: Se comparan las distribuciones de la calidad de ambos vinos mediante histogramas interactivos.
   - **Comparación Estadística**: Se realiza una prueba t de Student para comparar las medias de calidad entre el vino tinto y blanco.
   - **Análisis Visual Interactivo**: Se utilizan gráficos interactivos de Plotly para explorar y comparar las características del vino tinto y blanco, incluyendo PCA, diagramas de dispersión, matrices de dispersión, boxplots y violin plots.

## Archivos del Proyecto

- `Vino_rojo.ipynb`: Notebook que contiene el análisis y modelado del vino tinto.
- `Vino_blanco.ipynb`: Notebook que contiene el análisis y modelado del vino blanco.
- `diferencia_calidad_entre_vinos.ipynb`: Notebook que compara la calidad entre los vinos tinto y blanco.

## Requerimientos

Asegúrate de tener instaladas las siguientes bibliotecas en tu entorno de Python. Puedes instalar las dependencias utilizando el archivo `requirements.txt` proporcionado.

