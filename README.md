# Proyecto de Análisis de Series Temporales – RSAFSNA

## Descripción

En este proyecto comparamos cuatro familias de modelos de pronóstico para las ventas minoristas y los servicios de alimentación de Estados Unidos, utilizando datos mensuales de la serie RSAFSNA, desde enero de 1992 hasta septiembre de 2026.

Evaluamos modelos de suavizamiento exponencial, SARIMA, regresión con tendencia y estacionalidad, y regresión dinámica con errores ARIMA.

El modelo seleccionado fue SARIMA(2,1,3)(0,1,1)[12], con un RMSE de 8307.27 millones de dólares y un MAPE de 0.98 % en el conjunto de prueba.

## Archivos

- `Proyecto series final.qmd`: artículo científico y código de análisis.
- `datos_RSAFSNA.csv`: datos utilizados.
- `referencias.bib`: referencias bibliográficas.
- `apa.csl`: estilo de citación APA.

## Reproducción del artículo

Para generar el PDF se requiere R, Quarto, un sistema LaTeX y los paquetes de R `forecast`, `ggplot2` y `astsa`.

1. Descargar los archivos del repositorio en una misma carpeta.
2. Instalar los paquetes necesarios de R.
3. Abrir `Proyecto series final.qmd` en RStudio.
4. Presionar **Render** para generar el artículo en PDF.

## Autores

Michael Umaña Guillén, Leonardo Chinchilla Segura y Carlos Chacón Sanabria.

Universidad de Costa Rica, 2026.
