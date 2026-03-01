# Diseño de Algoritmos y Backtesting Avanzado

## Objetivo
Este proyecto implementa y evalúa una estrategia de momentum con backtesting realista (costes, ejecuciones y benchmark SPY), y resume resultados en los notebooks finales.

## Entorno asumido
La práctica está diseñada para usar únicamente estas librerías externas:
- numpy
- pandas
- yfinance
- matplotlib
- seaborn
- scipy
- pyarrow

La versión de python usada para los notebooks es: 3.13.5
Además, se usan módulos nativos de Python (stdlib).  
No se incluye `requirements.txt` porque la corrección se realiza en un entorno docente con estas librerías disponibles.

## Estructura
- `Notebook_1_Carga_de_Datos.ipynb`
- `Notebook_2_EDA_y_preparacion.ipynb`
- `Notebook_3_Implementacion_estrategia.ipynb`
- `Notebook_4_Ejecucion_y_costes.ipynb`
- `Notebook_5_Benchmarks_metricas_y_analisis.ipynb`
- `data/raw/` datos base
- `data/processed/` artefactos intermedios y finales

## Orden de ejecución
Ejecutar en este orden:
1. Notebook 1
2. Notebook 2
3. Notebook 3
4. Notebook 4
5. Notebook 5

## Reproducibilidad
- El proyecto usa rutas relativas dentro de la carpeta del repositorio.
- Para revisión rápida, se incluyen también artefactos en `data/processed/`.

## Nota para corrección
Si el entorno ya tiene instaladas las librerías permitidas, no hace falta ninguna instalación adicional.


