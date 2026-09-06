# 🚀 Portfolio de Proyectos: Machine Learning & Bases de Datos

Repositorio enfocado en el desarrollo y práctica de **Ciencia de Datos, Machine Learning y Gestión de Bases de Datos**, integrando el procesamiento de información tabular y consultas estructuradas.

---

## 📁 Contenido del Repositorio

* **`train.csv` & `test.csv`**: Datasets del clásico problema de Machine Learning del Titanic (entrenamiento y prueba).
* **`gender_submission.csv`**: Archivo de ejemplo con el formato requerido para las predicciones.
* **`API 3_BD.db`**: Base de datos relacional en SQLite utilizada para la gestión y consulta de información estructurada.
* **`Api_2_ML.ipynb`**: Jupyter Notebook con el flujo completo de Machine Learning (preprocesamiento, entrenamiento y evaluación del modelo).
* **`Api_2__AYV.pdf`**: Documentación y consignas orientativas de la actividad.

---

## 🛠️ Tecnologías y Librerías Utilizadas
* **Lenguaje:** Python 🐍
* **Manipulación de Datos:** Pandas, NumPy
* **Machine Learning:** Scikit-Learn
* **Bases de Datos:** SQLite / SQL
* **Visualización:** Matplotlib, Seaborn

---

## 📊 Descripción de Proyectos

### 1. Modelo Predictivo - Titanic (Machine Learning)
* **Objetivo:** Predecir la supervivencia de los pasajeros a partir de variables sociodemográficas y de viaje (`Pclass`, `Sex`, `Age`, `Fare`, etc.).
* **Fases del proyecto:**
  1. Análisis Exploratorio de Datos (EDA) y detección de valores faltantes.
  2. Limpieza e imputación de nulos (edades, tarifas, etc.).
  3. Transformación de variables categóricas a numéricas.
  4. Entrenamiento de un modelo de clasificación y evaluación de métricas de desempeño.

### 2. Gestión de Bases de Datos (`API 3_BD.db`)
* **Objetivo:** Almacenamiento, estructuración y consulta de datos mediante SQL para la extracción de información clave.

---
## ⚙️ Cómo ejecutar el proyecto localmente

git clone https://github.com/Santiago-DataHealthcare/healthcare-data-analytics.git

Asegúrate de tener instaladas las librerías necesarias:

Bash
pip install pandas numpy scikit-learn matplotlib seaborn
Abre el entorno de Jupyter Notebook para explorar el código:

Bash
jupyter notebook
