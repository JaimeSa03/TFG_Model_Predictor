#Trabajo Fin de Grado

#Predicción de coste de la luz en base a los factores que lo determinan en España

## Autores

Daniel Lafuente Bazo, Jaime Sánchez Izquierdo y Jaime Isaar Muñoz

## Descripción

El objetivo de este proyecto, es el de desarrollar modelos
predictivos capaces de estimar el precio diario o por horas de la electricidad en el mercado diario
español (pool eléctrico). En base a los conocimientos aprendidos durante la carrera, se han
elegido ciertos modelos con los que realizar este proyecto para poder comprobar
si un aumento en la complejidad y esfuerzo son realmente útiles o no.
Para ello, se han estudiado y analizado los modelos Lineales de Series Temporales,
de Métodos Ensamblados y Redes Neuronales con el fin de encontrar el mejor
ajuste de cada uno consiguiendo una predicción lo mas corecta posible.

## Objetivos

- Analizar los principales factores que influyen en el precio de la electricidad.
- Recopilar y preparar datos históricos del mercado eléctrico español.
- Analizar la relación entre generación, demanda, climatología y precio.
- Desarrollar modelos de series temporales para predecir el precio de la electricidad.
- Comparar diferentes modelos y evaluar su capacidad predictiva.

## Datos

Los datos utilizados en el proyecto proceden principalmente de:

- OMIE: precios del mercado eléctrico.
- REE / ESIOS: demanda y generación eléctrica por tecnología.
- Copernicus ERA5 / AEMET: datos meteorológicos y otras variables exógenas.

El periodo de estudio comprende los años 2020-2024.

## Metodología

El proyecto comprende las siguientes etapas:

1. Estudio del mercado eléctrico español y recopilación de datos.
2. Limpieza y tratamiento de los datos.
3. Análisis exploratorio.
4. Preparación de las variables para el modelado.
5. Desarrollo y ejecución de los modelos.
6. Evaluación y comparación de los resultados.

Entre los modelos estudiados se encuentran:

- AR, MA, ARMA, ARIMA, SARIMA, SARIMAX
- LightGBM, XGBoost, CatBoost
- GRU, LSTM

## Recursos adicionales

Algunos archivos y recursos utilizados durante el desarrollo del proyecto,
que por su tamaño o naturaleza no se incluyen directamente en el repositorio,
están disponibles en la siguiente carpeta:

https://drive.google.com/drive/u/1/folders/1k0xrbdfGC4SHZyjCtm_hme3w7HjT-OHl
