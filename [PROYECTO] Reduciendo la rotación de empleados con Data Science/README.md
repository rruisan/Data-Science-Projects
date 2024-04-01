
# Análisis y Predicción de la Rotación de Empleados

## Descripción
Este proyecto proporciona una solución de análisis y predicción de la rotación de empleados utilizando datos históricos de una empresa. Se analiza el abandono de los empleados, se identifican factores clave que influyen en la rotación y se cuantifica el impacto económico de este problema. Utilizando Machine Learning, creamos un modelo que predice la probabilidad de abandono de los empleados, permitiendo a la empresa tomar medidas preventivas.

## Contenido del Repositorio
- `analisis_prediccion_rotacion_empleados.ipynb`: Jupyter Notebook que contiene todo el análisis de datos, la creación y validación del modelo predictivo.
- `dashboard_final.png`: Imagen del dashboard interactivo desarrollado en Tableau.
- `requirements.txt`: Archivo con las dependencias necesarias para reproducir el análisis.
- `data/`: Carpeta que contiene el conjunto de datos `AbandonoEmpleados.csv` utilizado en el análisis.

## Instalación
Para instalar las dependencias del proyecto, ejecute el siguiente comando:
```bash
pip install -r requirements.txt
```

## Uso
Para ejecutar el notebook, inicie Jupyter Notebook o JupyterLab y abra el archivo `analisis_prediccion_rotacion_empleados.ipynb`. Siga las celdas en orden, ejecutando cada una para reproducir el análisis y los resultados.

## Metodología
El proyecto sigue un flujo de trabajo estructurado que comienza con la carga y limpieza de datos, seguido de un Análisis Exploratorio de Datos (EDA) tanto para variables categóricas como numéricas. Luego cuantificamos el problema de abandono, generamos insights y finalmente construimos un modelo de clasificación utilizando un Árbol de Decisión.

## Resultados
El proyecto concluye con la predicción del riesgo de abandono por empleado y la interpretación de los resultados, incluyendo la importancia de las variables. Se presenta un diagrama del árbol de decisión y se discute su relevancia en el contexto empresarial.

## Contribuciones
Las contribuciones son bienvenidas. Si tiene sugerencias o mejoras, no dude en forkear el repositorio y abrir un pull request.

## Licencia
Este proyecto está licenciado bajo los términos de la licencia MIT.
