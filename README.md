# Alerta de estaciones sin bicis con aprendizaje en flujo de datos

Proyecto de la asignatura **Aprendizaje Automático en Series Temporales y Flujos de Datos** (Máster en Inteligencia Artificial Aplicada, UC3M).

A partir del dataset [`Bikes`](https://riverml.xyz/latest/api/datasets/Bikes/) de [River](https://riverml.xyz) (estación *pomme*, Toulouse, 2016), se simula un flujo de datos con una instancia cada 30 minutos. Sobre ese flujo se predice si dentro de 2 horas la estación tendrá 2 bicis o menos. Además, se detecta el *data drift* y el *concept drift* y se comparan estrategias de adaptación.

## Contenido

| Fichero | Descripción |
|---|---|
| `01_Flujo_y_Exploratorio_Bicis.ipynb` | Construcción del flujo y análisis exploratorio |
| `02_Modelado_y_Deteccion_Drift.ipynb` | Modelos online y detección de *data drift* y *concept drift* |
| `03_Drift_Controlado_y_Adaptacion.ipynb` | *Concept drift* controlado y estrategias de adaptación |
| `flujo_pomme_30min.csv` | Flujo de datos generado por el notebook 1 |
| `memoria/` | Memoria del proyecto (Typst) |


## Autores

Álvaro Alonso Haya · Antonio Ángel Bello Castro · Martín Hernández Tonzán
