
# Análisis Exploratorio de Datos - Precios de Viviendas

En este proyecto se enfatiza un **análisis descriptivo** sobre el conjunto de datos de los precios de viviendas, con el fin de obtener una idea de los factores que afectan los precios de las viviendas; con la ayuda de la herramienta _**Jupyter Notebook**_ y con el lenguaje _**Python**_. Además, se construye un modelo de **Regresión Lineal** con la ayuda de la librería de _**Scikit-learn**_ para la predicción de los precios de las viviendas.

<p align="center">
  <img src="./images/vivienda.jpg" />
</p>

Dado el conjunto de datos de las viviendas vendidas entre mayo de 2014 y mayo de 2015 en el condado de King (_Seattle, USA_), que dicha fuente de datos se recurrió al repositorio [Kaggle](https://www.kaggle.com/harlfoxem/housesalesprediction).


## Objetivo

* Realizar un análisis descriptivo para verificar la consistencia de los datos, tales como: _valores faltantes_, _valores atípicos_, _correlaciones entre variables_, y entre otros que se puedan presentar.
* Desarrollar e implementar un modelo de _Regresión Lineal_ para predecir el precio de las viviendas en función de sus características.
* Y por último realizar una evaluación del “Accuracy” (_precisión_) sobre el modelo construido, apoyándonos con los métodos de _ridge_ y _lasso_ para contraer los coeficientes de regresión.


## Descripción del conjunto de Datos

_Dimensiones:_ 21613 x 21 (_filas x columnas_)

_Formato:_ csv

_Descripción de las columnas:_

* **id:** código
* **date:** fecha
* **price:** precio
* **bedrooms:** nro. de dormitorios
* **bathrooms:** nro. de baños
* **sqft_living:** pies cuadrados de la casa
* **sqft_lot:** pies cuadrados del lote
* **floors:** nro. de pisos
* **waterfront:** vista al mar, si (1) o no (0)
* **view:** buena vista panorámica, si (1) o no (0)
* **condition:** estado de la vivienda, calificación de 1 a 5
* **grade:** calificación de usuarios a la vivienda (1 - 13)
* **sqft_above:** pies cuadrados del piso superior
* **sqft_basement:** pies cuadrados del sotano
* **yr_built:** año de construcción
* **yr_renovated:** año de la renovación de la construcción
* **zipcode:** código postal
* **lat:** coordenada de latitud
* **long:** coordenada de longitud
* **sqft_living15:** pies cuadrados de la casa, después de 15 años
* **sqft_lot15:** pies cuadrados del lote, después de 15 años


- [x] _Para ver el desarrollo y el código a detalle, ingrese a la carpeta_ **“notebooks”**.




