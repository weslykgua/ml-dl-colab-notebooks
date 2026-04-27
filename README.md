# 🚀 Portafolio de estudio Machine Learning & Deep Learning

Bienvenido a mi repositorio principal de Machine Learning. Aquí documento mi progreso, experimentación y desarrollo de modelos predictivos, abarcando desde el análisis exploratorio de datos (EDA) tradicional hasta la implementación de redes neuronales y algoritmos de optimización desde cero.

Todas las implementaciones siguen la metodología **CRISP-DM** para garantizar un enfoque estructurado y orientado al negocio.

## 📁 Proyectos Destacados en este Repositorio

A continuación, se detallan los notebooks y proyectos incluidos, ordenados por área de enfoque:

### 1. Análisis Exploratorio y Preprocesamiento
* **`CRISP_DM_EDA_Data_Preparation_ML_Project.ipynb`**
  * **Descripción:** Pipeline completo de preparación de datos utilizando el dataset `tips`. Incluye tratamiento de valores atípicos (outliers) mediante winsorización (capado IQR), imputación de datos, estandarización escalada (RobustScaler, StandardScaler) y codificación de variables categóricas (OneHotEncoder).
  * **Stack:** `pandas`, `seaborn`, `scikit-learn` (Pipelines, ColumnTransformer).

### 2. Aprendizaje Supervisado (Clasificación y Regresión)
* **`Supervised_ML_Wine_Classification_and_Regression.ipynb`**
  * **Descripción:** Modelado predictivo sobre la calidad y características de cultivares de vino. Implementación de balanceo de clases sintético (`RandomOverSampler`), entrenamiento y evaluación exhaustiva de múltiples modelos (Random Forest, SVM, KNN, Regresión Logística).
  * **Métricas:** R², RMSE, F1-Score, ROC-AUC, Matriz de Confusión.

### 3. Aprendizaje No Supervisado (Clustering)
* **`CRISP_DM_Unsupervised_Learning_Wine_Clustering.ipynb`**
  * **Descripción:** Segmentación automatizada de perfiles de vino sin etiquetas previas. Uso de reducción de dimensionalidad (PCA) para visualización 2D y métodos de evaluación como *Elbow Method* y *Silhouette Score* para determinar el número óptimo de clusters (k=3).
  * **Modelos:** K-Means, Agglomerative Clustering.

### 4. Deep Learning & Regularización
* **`Generalizacion_y_Overfitting_Keras.ipynb`** & **`Regularizacion_y_Dropout_Keras.ipynb`**
  * **Descripción:** Entrenamiento de redes neuronales Feed-Forward para clasificación de imágenes complejas (CIFAR-10 y MNIST). Análisis práctico del fenómeno de *overfitting* en conjuntos de entrenamiento vs. validación, mitigado mediante técnicas de regularización como *Dropout* y ajuste de hiperparámetros.
  * **Stack:** `TensorFlow`, `Keras`.

### 5. Algoritmos de Optimización desde Cero
* **`1_6_3_Actividad_Optimizadores.ipynb`**
  * **Descripción:** Implementación pura (usando matemáticas y NumPy) de los algoritmos de optimización más utilizados en el entrenamiento de redes neuronales, visualizados mediante gráficos de contorno interactivos.
  * **Algoritmos:** Descenso del Gradiente Vanilla, Momentum, RMSProp, Adam.

---

## 🛠️ Tecnologías y Herramientas

* **Lenguaje:** Python 3.x
* **Manipulación y Visualización:** NumPy, Pandas, Matplotlib, Seaborn
* **Machine Learning Clásico:** Scikit-Learn, Imbalanced-Learn
* **Deep Learning:** TensorFlow, Keras
* **Entorno:** Jupyter Notebook / Google Colab
