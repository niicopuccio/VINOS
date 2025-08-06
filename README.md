# 🧪 Proyecto Final - Data Science I

## 📌 Título:
**Predicción del Ranking de Vinos**

## 👤 Alumno:
Nicolas Puccio  
Curso de Data Science I - CoderHouse

## 📂 Dataset:
Archivo: `VINOS.xlsx`  
- **Fuente:** [Kaggle - Wine Reviews Dataset](https://www.kaggle.com/datasets/zynicide/wine-reviews?select=winemag-data-130k-v2.csv)

## 🎯 Objetivo:
El objetivo de este proyecto es aplicar técnicas de selección de variables, entrenar un modelo de regresión para predecir el ranking de calidad de los vinos, y evaluar su rendimiento mediante métricas apropiadas.

---

## 🧠 Metodología

1. **Carga y exploración del dataset**
2. **Preprocesamiento de los datos**
   - Eliminación de nulos
   - Codificación de variables categóricas
3. **Selección de características**
   - Método: `SelectKBest` con `f_regression`
4. **Entrenamiento del modelo**
   - Modelos utilizados:
     - `Random Forest Regressor`
     - `Gradient Boosting Regressor`
5. **Evaluación**
   - Métricas: `MSE`, `RMSE`, `R²`
   - Análisis de importancia de variables
6. **Conclusiones**

---

## 📈 Resultados

- El modelo `Random Forest` muestra un buen desempeño, pero `Gradient Boosting` logra captar mejor relaciones sutiles.
- Se encontró que **el precio del vino** es la variable más influyente en la predicción del ranking.
- Otras variables como `AÑO`, `VARIEDAD` o `PROVINCIA` tuvieron menor peso en este conjunto de datos.

---

## 🛠️ Herramientas utilizadas

- Python 3
- Google Colab
- Pandas, NumPy
- Scikit-Learn
- Matplotlib, Seaborn

---

## ✅ Conclusiones

El modelo Gradient Boosting demostró ser una opción sólida para predecir el ranking de vinos. El precio resultó ser la principal variable explicativa. Para mejorar el modelo, se podrían aplicar técnicas como el ajuste de hiperparámetros, uso de modelos más avanzados (XGBoost, LightGBM) y creación de nuevas variables derivadas.

---

## 📚 Referencias

- [Scikit-learn documentation](https://scikit-learn.org/)
- Curso de Data Science - CoderHouse
- Dataset provisto por la institución
