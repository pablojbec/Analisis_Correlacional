# Análisis Correlacional
Este repositorio contiene el análisis correlacional realizado a los datos de una plataforma de comercio electrónico para identificar factores de comportamiento del cliente asociados con el ingreso anual generado en el año 2024.

El dataset `novaretail_comportamiento_clientes_2024` contiene datos de comportamientos de clientes de la plataforma electrónica.


## 📂 Contenido del repositorio

- `/Analisis_correlacional.ipynb`
  → Notebook principal con limpieza, análisis de correlaciones y conclusiones.
- Dataset →Links a dataset trabajado

## ▶️ Cómo ejecutar el notebook

Puedes ejecutar este notebook de las siguientes formas:

### Opción 1: Abrir en Google Colab
- Ve a Google Colab
- Haz clic en “File” > “Open notebook”
- Selecciona la pestaña “GitHub”
- Pega el enlace de este repositorio
- Abre el archivo .ipynb

### Opción 2: Ejecutar en local

- Clona este repositorio:
git clone [https://github.com/pablojbec/Analisis_Correlacional]
- Accede a la carpeta del proyecto:
- cd repositorio

- Abre Jupyter Notebook:
  - jupyter notebook
  - Selecciona el archivo .ipynb y ejecútalo

## 🔁 Guía de reproducción
Para reproducir los resultados:

- Instala las dependencias necesarias (recomendado usar entorno virtual o Anaconda):
pip install -r requirements.txt
- Asegúrate de tener los datos en la ruta correcta (ver carpeta /data si aplica)
- Ejecuta las celdas del notebook en orden, desde el inicio
- Verifica que no haya errores y que los outputs coincidan con los esperados

## 🧠 Objetivo del análisis

- Identificar problemas de calidad de datos
- Realizar la limpieza del datasets
- Analizar correlaciones entre diferentes tipos de datos con ayuda de Heatmaps y scatterplots.
- Calcular los coeficientes de correlación entre las variables numéricas y categóricas usando las meotdologías de Pearson, Punto biserial y V de Cramr.
- Generar insights para ayudar definir cuales son las correlaciones son las más fuertes y porqué.
-Proporcionar recomendaciones de acuerdo con el análisis realizado y las limitaciones mencionadas.

## 🧩Etapas de análisis realizadas

- Se realizó la limpieza y validación de los datos
- Se visualizaron las correlaciones entre las variables numéricas en un Heatmap
- Se visualizaron scatterplots entre los pares de variables clave y se proporcionaron conclusiones a partir de estos
- Se calcularon los coeficientes de correlación con los métodos de Pearson entre variables numéricas, Punto biserial entre variables numéricas y categóricas, y V de Cramér entre variables categóricas
- Se proporcionaron hallazgos clave entre pares de variables
- Se mencionaron las limitaciones del análisis y se aconsejan los próximos pasos a seguir en el análisis
