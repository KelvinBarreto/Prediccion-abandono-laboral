# TFM - Predicción del abandono laboral en la empresa
Es un proyecto para predecir la probabilidad de abandono de los empleados de una empresa
# 📌 Predicción del abandono laboral y su impacto económico

Este proyecto forma parte de mi Trabajo Fin de Máster (TFM) y tiene como objetivo **predecir la rotación laboral dentro de una empresa** utilizando técnicas de Machine Learning, y evaluar el **impacto económico asociado a la pérdida de talento**.

---

## 🔎 1. El problema
La **rotación laboral** supone un gran reto para las organizaciones, ya que implica:
- Costes elevados de reemplazo y formación.
- Pérdida de conocimiento y productividad.
- Impacto negativo en la cultura y el clima organizacional.

En este contexto, surge la necesidad de **predecir qué empleados tienen mayor probabilidad de abandonar la empresa** y diseñar estrategias para mejorar la retención.

---

## 📊 2. La exploración
Se parte de un dataset de **223 registros y 19 variables**, con información sobre características de los empleados, su desempeño y condiciones laborales.  
Las fases realizadas incluyen:
- Limpieza y preprocesamiento de datos (gestión de valores nulos, codificación de variables, escalado).  
- Análisis exploratorio (EDA) para detectar patrones iniciales.  
- Estudio del impacto económico de la rotación sobre la organización.

---

## 🤖 3. La solución
Se desarrollaron y compararon distintos modelos de Machine Learning:
- **Regresión Logística**  
- **Random Forest**  
- **XGBoost**

Se aplicaron técnicas de optimización de hiperparámetros (Grid Search, Random Search) y de balanceo de clases (SMOTE).  
Además, se incorporaron herramientas de **interpretabilidad del modelo** (SHAP) para comprender qué variables influyen más en la predicción.

---

## ✅ 4. Conclusiones
- El modelo que mejor rendimiento obtuvo fue **XGBoost**, con un AUC-ROC superior al 0.80.  
- La interpretabilidad mostró que factores como el salario, la ubicación y la jornada laboral influyen de manera significativa en la rotación.  
- La predicción permite actuar de forma proactiva sobre empleados en riesgo.

---

## 💡 5. Impacto
Implementar este modelo de predicción tiene beneficios clave:
- **Reducción de la rotación estimada en un 30%.**  
- **Ahorro económico anual superior a 180.000 €** en costes asociados a la salida de empleados.  
- Mejora en la **retención de talento y en la planificación de RRHH**.

---

## 🚀 Tecnologías utilizadas
- Python (Pandas, NumPy, Scikit-learn, XGBoost, SHAP, Matplotlib, Seaborn)  
- Jupyter Notebooks  
- Power BI para visualización de resultados  

---

## 📂 Estructura del repositorio
├── data/ # Datos utilizados (si son públicos o ficticios)
├── notebooks/ # Notebooks con EDA, modelos y evaluaciones
├── src/ # Código fuente (funciones auxiliares, scripts)
├── reports/ # Informes y gráficas del análisis
├── README.md # Documentación principal del proyecto
