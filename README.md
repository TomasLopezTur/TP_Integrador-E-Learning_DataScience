# TP_Integrador-E-Learning_DataScience
Trabajo integrador del curso de Data Sceince de UTN E-Learning


# Análisis de Tipos de Cambio con Data Science

## Descripción

Este proyecto forma parte del trabajo integrador del curso Codo a Codo 4.0 - Big Data / Data Analytics. Su objetivo es aplicar herramientas de Data Science en el análisis de los tipos de cambio de divisas, específicamente USD/JPY, USD/EUR y USD/ARS. A través de este estudio, se busca entender la volatilidad del mercado financiero y explorar patrones en la evolución de las divisas.

## Motivación

Inicialmente, se consideró trabajar con datos relacionados con el turismo, pero los datasets disponibles no cumplían con las expectativas en términos de integridad y relevancia. Por ello, se optó por los datos financieros, que ofrecen una base más sólida para el análisis y la aplicación de modelos predictivos.

## Tecnologías Utilizadas

Python

#### Librerías: yfinance, pandas, matplotlib, seaborn, Prophet, sklearn

#### Fuentes de Datos

Los datos se obtienen a través de la API de Yahoo Finance utilizando la librería yfinance. Se han seleccionado los siguientes pares de divisas:

* USD/JPY (Dólar - Yen Japonés)

* USD/EUR (Dólar - Euro)

* USD/ARS (Dólar - Peso Argentino)

## Análisis y Visualización

Se realizaron los siguientes pasos en el análisis:

Carga y limpieza de datos: Eliminación de columnas irrelevantes y ajuste de formatos de fechas.

## Análisis exploratorio:

Visualización de la evolución de los precios de cierre.

Cálculo de métricas descriptivas (media, mediana, desviación estándar, máximos y mínimos).

Histogramas y distribución de los datos.

## Modelado predictivo:

Uso de Prophet para la predicción de tendencias futuras.

Evaluación de modelos con MAE y MSE.

## Resultados

Se identificaron tendencias y patrones en la fluctuación de las divisas.

Se evidenció una marcada devaluación del peso argentino frente al dólar.

Se implementaron modelos de predicción para estimar posibles valores futuros.
