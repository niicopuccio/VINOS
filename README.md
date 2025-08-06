# Título: Análisis de Vinos - Predicción del Ranking
# Alumno: Nicolás Puccio
# Curso: CoderHouse - Data Science I
# Dataset: VINOS.xlsx
# Objetivo: Aplicar técnicas de selección de variables, entrenar un modelo de regresión utilizando el dataset elegido.
from google.colab import drive
drive.mount('/content/drive')

import pandas as pd

# Reemplazar con la ruta correcta si lo subís a tu Drive
file_path = '/content/drive/MyDrive/DATA SCIENCE I/VINOS.xlsx'

df = pd.read_excel(file_path, sheet_name='VINOS')
df.head()
