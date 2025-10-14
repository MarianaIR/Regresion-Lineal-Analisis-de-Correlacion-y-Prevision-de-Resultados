# 📉 REGRESIÓN LINEAL: ANÁLISIS DE CORRELACIÓN Y PREVISIÓN DE RESULTADOS

[![Python](https://img.shields.io/badge/Python-3670A0?style=flat&logo=python&logoColor=ffdd54)](https://www.python.org/)  
[![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat&logo=pandas&logoColor=white)](https://pandas.pydata.org/)  
[![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat&logo=numpy&logoColor=white)](https://numpy.org/)  
[![Scikit-learn](https://img.shields.io/badge/Scikit--learn-F7931E?style=flat&logo=scikit-learn&logoColor=white)](https://scikit-learn.org/)  
[![Seaborn](https://img.shields.io/badge/Seaborn-0099CC?style=flat&logo=seaborn&logoColor=white)](https://seaborn.pydata.org/)  
[![Matplotlib](https://img.shields.io/badge/Matplotlib-11557c?style=flat&logo=matplotlib&logoColor=white)](https://matplotlib.org/)

Este proyecto se enfoca en la implementación y análisis del modelo de **Regresión Lineal Simple y Múltiple**. Se utiliza para **prever o pronosticar resultados futuros** basados en la relación lineal entre variables, siendo una técnica fundamental en Data Science para predecir valores continuos.

---

## 🧠 Contenido del Proyecto

### 1️⃣ Análisis Exploratorio y Correlación
- **Visualización Gráfica:** Se enfatiza el uso de **diagramas de dispersión** para identificar la presencia de una **relación lineal** entre la variable dependiente (Y) y las variables explicativas (X's).
- **Análisis de Distribución:** Mediante un **histograma**, se realiza una evaluación preliminar para determinar si la variable dependiente sigue una **distribución normal**.
- **Medición de Correlación:** Se calcula el **Coeficiente de Correlación** (entre -1 y +1) para medir la asociación lineal entre dos variables.
- **Gráfico Bivariado:** Se utiliza la función **`jointplot()` de Seaborn** para visualizar la relación entre dos variables junto con sus respectivas distribuciones de frecuencia.

### 2️⃣ Modelado y Estimación (Regresión Lineal)
- **Modelos:** Se implementa un modelo de **Regresión Lineal** utilizando Scikit-learn (inferido por ser la librería estándar y la temática).
- **Estimación de Parámetros:** Se obtiene la estimación de los coeficientes del modelo.

### 3️⃣ Evaluación del Modelo
- **Métricas Clave:** La precisión del modelo se evalúa mediante:
    * **Error Cuadrático Medio (ECM):** Métrica que **debe minimizarse**.
    * **R² (Coeficiente de Determinación):** Métrica que **debe maximizarse**.

### 4️⃣ Persistencia del Modelo
- **Guardado del Modelo:** Se utiliza la biblioteca **`pickle`** para **guardar el modelo estimado** en un archivo binario (`pickle.dump()`), permitiendo su **reutilización** sin necesidad de reejecutar el proceso de estimación.
- **Carga del Modelo:** Se utiliza `pickle.load()` para cargar el modelo almacenado en memoria.

---

## 🛠️ Librerías Utilizadas

| Librería       | Uso principal                               |
|----------------|---------------------------------------------|
| **Pandas**     | Carga y manipulación de datos|
| **NumPy**      | Cálculos numéricos y manejo de *arrays*|
| **Seaborn**    | Visualización de gráficos estadísticos (`jointplot()`)|
| **Matplotlib** | Generación de gráficos (Histogramas, Dispersión)|
| **Scikit-learn**| Implementación del modelo de Regresión Lineal y cálculo de métricas (ECM, R²)|
| **Pickle**     | Serialización/deserialización del modelo estimado (`pickle.dump()`, `pickle.load()`)|

---

## 🎯 Objetivo del Proyecto
Aplicar y validar la **Regresión Lineal** como herramienta predictiva. El proyecto busca establecer un flujo de trabajo completo que incluye el **análisis gráfico** de la relación entre variables, la estimación del modelo y la **persistencia del modelo** para su uso futuro, todo ello en el marco del Machine Learning Supervisado.

---

## 📈 Resultados Clave
- Se confirma la importancia del **análisis gráfico** como técnica estadística vital en la creación de modelos.
- Se establece que para evaluar el rendimiento, el **Error Cuadrático Medio (ECM) debe ser bajo** y el **R² debe ser alto**.
- Se implementa un método para **guardar y cargar el modelo** usando `pickle`, asegurando la reutilización del modelo sin repetir el entrenamiento.

