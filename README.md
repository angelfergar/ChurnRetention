# 📊 Proyecto de Predicción de Churn

Este proyecto utiliza Machine Learning (estándar y Spark) para predecir la probabilidad de que un cliente de telecomunicaciones abandone el servicio (**Churn**). Se comparan diferentes modelos y se simulan estrategias de retención para evaluar su impacto en el negocio.

---

## 📌 **Estructura del Proyecto**

```/ChurnRetention-SP
│── /data
│   ├── raw_customerChurn.csv
│   ├── cleaned_customerChurn.csv  # Listo para usarse en Power BI
│   ├── preprocessed_customerChurn.csv  # Listo para entrenar los modelos 
│── /models
│   ├── best_model.pkl  # Mejor modelo estándar
│   ├── best_spark_model.?? # Mejor modelo de Spark MLlib
│── /notebooks
│   ├── Exploratory_Analysis.ipynb  # Limpieza de datos & visualización
│   ├── Preprocessing.ipynb  # Preparación de los datos para entrenar los modelos
│   ├── Model_Training.ipynb  # Entrenamiento de modelos estándar y tuning
│   ├── Spark_Model_Training.ipynb  # Entrenamiento de modelos de la librería Spark MLlib
│   ├── Simulation.ipynb # Simulación de la reducción de Churn  
│── README.md```

---

## 📊 **1. Análisis Exploratorio**
El archivo ['Exploratory_Analysis.ipynb'](notebooks/Exploratory_Analysis.ipynb) contiene:  
✅ Carga y limpieza de datos  
✅ Visualización de tendencias de Churn con **Matplotlib & Seaborn**  
✅ Análisis de correlaciones y factores clave 

---
 
## 🤖 **2. Modelado y Evaluación**
El archivo ['Model_Training.ipynb'](notebooks/Model_Training.ipynb) desarrolla:  
✅ Modelos como **Regresión Logística, Random Forest, XGBoost y LightGBM**  
✅ **Optimización de hiperparámetros** con Grid Search  

📌 **El mejor modelo se guarda en** `/models/best_model.pkl`

---

## 🎯 **3. Simulación de Reducción de Churn**
 
El archivo ['Simulation.ipynb']
(notebooks/Model_Training.ipynb) calcula el impacto de estrategias de retención:
✅ Simulación de estrategias de retención como **descuentos y mejoras de soporte**
✅ **Cálculo del ahorro financiero y ROI**

---

## 🤖 **4. Modelado y Evaluación en Spark**
El archivo Spark_Model_Training.ipynb desarrolla modelos utilizando Spark MLlib, una librería optimizada para procesamiento en Big Data.
✅ Transformación de datos con **VectorAssembler** para trabajar con Spark.
✅ Entrenamiento de modelos como **Decision Tree, Random Forest y Gradient-Boosted Trees (GBTClassifier)**.
✅ Comparación de métricas con el best_model.pkl
✅ **Optimización con CrossValidator y ParamGridBuilder** para mejorar los hiperparámetros.

📌 **El mejor modelo de Spark se guarda en** /models/best_spark_model.??.

---

## ⚙️ **5. Instalación y Uso**
### 📥 **Descargar el Repositorio**
```bash
git clone https://github.com/angelfergar/ChurnRetention-SP.git
cd ChurnRetention-SP```

---

## 📈 **6. Resultados Clave**
* RELLENAR CON Resultados

📊 _RELLENAR CON Gráficos y visualizaciones detalladas en los notebooks y PowerBI._

---

## 🤝 **7. Contribución**
¡Sugerencias y mejoras son bienvenidas! 🚀

📌 **Desarrollado por**: Ángel Fernández
✉️ Contacto: anfernagar@gmail.com