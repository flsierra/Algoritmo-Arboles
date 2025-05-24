# Algoritmo de Árboles de Decisión - Análisis de Datos UNAD

Este repositorio contiene el desarrollo de un modelo basado en **Árboles de Decisión** como parte del proceso de **Análisis de Datos** realizado en la UNAD. El proyecto fue desarrollado en **Python** utilizando **Anaconda** y **Jupyter Notebooks**.

## 📋 Estructura del Proyecto

El flujo de trabajo implementado en el análisis sigue los siguientes pasos:

1. **Análisis Exploratorio de los Datos**
   - Revisión general del dataset.
   - Estadísticas descriptivas.
   - Visualización de patrones, correlaciones y distribución de variables.

2. **Procesamiento de los Datos**
   - Limpieza de datos (valores nulos, outliers).
   - Transformación de datos para facilitar el aprendizaje del modelo.
   - Estandarización o codificación si es necesario.

3. **Selección de Características**
   - Identificación de las variables más relevantes.
   - Uso de técnicas como `SelectKBest`, importancia de características del árbol, entre otras.

4. **División del Dataset**
   - Separación en conjunto de entrenamiento y prueba (`train_test_split`).
   - Control de aleatoriedad para reproducibilidad.

5. **Entrenamiento del Modelo**
   - Configuración de un árbol de decisión con `scikit-learn`.
   - Ajuste de hiperparámetros como profundidad máxima, criterios de división, número mínimo de muestras por hoja, etc.

6. **Evaluación del Modelo**
   - Evaluación en el conjunto de prueba.
   - Métricas utilizadas: precisión, recall, F1-score.
   - Validación de la capacidad predictiva del modelo.

7. **Visualización de Resultados**
   - Gráficas del árbol de decisión.
   - Importancia de características.
   - Matriz de confusión y métricas visuales.

## 🧰 Herramientas Utilizadas

- Python 3.9+
- Anaconda
- Jupyter Notebooks
- Bibliotecas:
  - `pandas`
  - `numpy`
  - `matplotlib`
  - `seaborn`
  - `scikit-learn`
  - `graphviz` (para visualizar árboles)

## 📦 Instalación

Clona este repositorio y asegúrate de tener las dependencias instaladas. Puedes usar el siguiente comando:

```bash
pip install -r requirements.txt
