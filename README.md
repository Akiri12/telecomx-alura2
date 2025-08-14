# 📡 Telecom X – Parte 2: Predicción de Cancelación (Churn)

## 📖 Descripción del Proyecto

Este proyecto corresponde a la **segunda fase** del reto de análisis de cancelación de clientes para la empresa **ficticia** **Telecom X** y forman parte de un ejercicio académico. Después de un análisis exploratorio inicial, ahora el objetivo es **predecir qué clientes tienen mayor probabilidad de cancelar sus servicios** mediante modelos de **Machine Learning**.  

---

## 🔗 Repositorios del Desafío

- **Parte 1 – ETL y Análisis Exploratorio:**  
  En esta etapa se realizó un **proceso ETL** (Extracción, Transformación y Carga) para limpiar, transformar y aplanar la información de clientes, seguido de un análisis exploratorio de datos (EDA) para identificar patrones y comportamientos relacionados con la cancelación.  
  📎 [https://github.com/Akiri12/Telecom_X_Alura.git](https://github.com/Akiri12/Telecom_X_Alura.git)

- **Parte 2 – Predicción de Cancelación:**  
  📎 [https://github.com/Akiri12/telecomx-alura2.git](https://github.com/Akiri12/telecomx-alura2.git)

---

## 🎯 Objetivos

1. **Preparación de datos**  
   - Limpieza, tratamiento de valores faltantes.  
   - Codificación de variables categóricas.  
   - Normalización y escalado de características.  

2. **Análisis y selección de variables**  
   - Matriz de correlación.  
   - Identificación de variables más relevantes para la predicción de churn.

3. **Entrenamiento de modelos de clasificación**  
   - Al menos dos algoritmos distintos (ej. Logistic Regression, Random Forest, XGBoost, etc.).  

4. **Evaluación de modelos**  
   - Uso de métricas como Accuracy, Precision, Recall, F1-Score, ROC-AUC.  

5. **Interpretación y conclusiones estratégicas**  
   - Variables más influyentes en la cancelación.  
   - Recomendaciones sobre el perfil de cliente en riesgo.

---

## 🧰 Tecnologías y Librerías Usadas

- **Python** (>= 3.9)  
- **Pandas**, **NumPy** → Manipulación y análisis de datos.  
- **Matplotlib**, **Seaborn** → Visualización de datos.  
- **Scikit-learn** → Preprocesamiento, entrenamiento y evaluación de modelos.  

---

#### 📂 Estructura del Repositorio
```
📦 telecomx-churn-prediction
┣ 📂 data
┃ ┣ telecomx-data-limpio.csv
┣ 📂 images
┃ ┣ heatmap0.2
┃ ┣ heatmap-matriz-correlacion-1
┣ 📂 models
┃ ┣ modelo_randomforest.pkl
┃ ┣ modelo_logistic.pkl
┣ 📂 notebooks
┃ ┣ TelecomX_LATAM.ipynb
┃ ┣ telecomx-latam-2.ipynb
┣ 📜 README.md
```
---

## 🚀 Cómo Ejecutar el Proyecto

**Clonar el repositorio**  
   ```bash
   git clone https://github.com/Akiri12/telecomx-alura2.git
   cd telecomx-alura2

