# 🏦 Predicción de Fuga de Clientes Bancarios con Machine Learning

Este proyecto utiliza algoritmos de clasificación para anticipar la fuga de clientes en el sector bancario, aplicando técnicas de machine learning y análisis exploratorio de datos.

El objetivo es permitir que los equipos comerciales y de retención identifiquen clientes con alta probabilidad de abandono y tomen acciones preventivas basadas en datos.

---

## 🚀 Resultados clave

- Se entrenaron dos modelos: **Random Forest** y **XGBoost**
- **XGBoost obtuvo mejor desempeño**, con una precisión del **86.95%**
- El modelo mejoró el F1-score de clientes que abandonan de **0.58 → 0.63**
- Las variables más influyentes fueron: **Edad, Saldo, Créditos activos y País**

---

## 🧰 Tecnologías utilizadas

- Python 3, pandas, numpy
- Visualización: seaborn, matplotlib
- Modelado: scikit-learn, xgboost
- Jupyter Notebook
- Git & GitHub

---

## 📁 Estructura del proyecto

📦 churn-prediction-banco/ 
├── 01_churn_exploracion.ipynb # Análisis exploratorio y visualización 
├── 02_modelo_predictivo.ipynb # Entrenamiento y evaluación de modelos 
├── dataset/Churn_Modelling.csv # Fuente de datos original 
├── README.md # Documentación del proyecto

---

## 📌 Recomendaciones futuras

- Probar técnicas de balanceo como **SMOTE**
- Desplegar el modelo en un microservicio o aplicación web
- Integrar un dashboard de riesgo de fuga en Power BI o Streamlit
- Evaluar impacto financiero de las predicciones en campañas reales

---

## 👤 Autor

**Iván Pino Z.**  
Estudiante de Ingeniería en Ciencias de Datos · Santiago de Chile  
Apasionado por el análisis de datos, machine learning aplicado y soluciones reales de negocio.  
[LinkedIn](https://www.linkedin.com/in/codelancer/) · [Portafolio](https://github.com/ivandatadev)

