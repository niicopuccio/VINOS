# Proyecto Final - Data Science I

## Título:
**Predicción del Ranking de Vinos**

## Alumno:
Nicolas Puccio  
Curso de Data Science I - CoderHouse

## Dataset:
Archivo: `VINOS.xlsx`  
- **Fuente:** [Kaggle - Wine Reviews Dataset](https://www.kaggle.com/datasets/zynicide/wine-reviews?select=winemag-data-130k-v2.csv)

## Objetivo:
El objetivo de este proyecto es aplicar técnicas de selección de variables, entrenar un modelo de regresión para predecir el ranking de calidad de los vinos, y evaluar su rendimiento

---

## Metodología

1.   - Modelos utilizados:
     - `Random Forest Regressor`
2. **Evaluación**
   - Análisis de importancia de variables

---

## Resultados

- El modelo `Random Forest` muestra un buen desempeño para calcular las variables con mayor importancia para calcular la predicción del ranking.
- Se encontró que el PRECIO del vino es la variable más influyente en la predicción.
- Otras variables como AÑO, VARIEDAD o PROVINCIA tuvieron menor peso en este conjunto de datos.

---

## Herramientas utilizadas

- Pandas
- NumPy
- sklearn
- Matplotlib

---

## Conclusiones

El precio resultó ser la principal variable. Para mejorar el modelo, se podrían aplicar EL uso de modelos más avanzados como XGBoost.
