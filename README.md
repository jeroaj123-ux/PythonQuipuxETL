 Análisis de Enfermedades del Corazón con Python

 Descripción general
Este proyecto tiene como objetivo analizar un conjunto de datos de enfermedades cardíacas utilizando herramientas de análisis de datos en Python.  
El propósito es identificar patrones, relaciones y posibles factores de riesgo que influyen en la presencia de una enfermedad del corazón, apoyándonos en librerías como pandas, matplotlib y seaborn.

El trabajo se desarrolló paso a paso en un cuaderno de Jupyter Notebook, desde la carga y limpieza de datos hasta la creación de gráficas interpretativas.

 Contenido del proyecto

 Carga y limpieza de datos
- Se cargó el dataset en formato CSV.  
- Se verificaron los valores nulos y se corrigieron posibles inconsistencias.  
- Se revisaron las columnas para asegurar que todos los datos fueran del tipo correcto.

En esta parte se trabajó también con la detección de valores faltantes en columnas como `ca` y `thal`, pero sin alterar demasiado los datos originales para mantener la integridad del conjunto.

 Transformaciones y filtraciones
- Se creó una nueva columna llamada `cholesterol_rango`, clasificando los niveles de colesterol en:
  - Normal
  - Alto
  - Muy alto
- Además, se organizaron los grupos de edad para facilitar los análisis comparativos.

 Esto ayudó a visualizar mejor cómo varía el colesterol según la edad y el riesgo cardíaco.

 Visualización de datos
Se generaron varias gráficas con matplotlib y seaborn, incluyendo:

- Distribución de los rangos de colesterol.  
- Promedio de colesterol por grupo de edad.  
- Comparativa entre frecuencia cardíaca máxima (`thalach`) y niveles de colesterol.  
- Gráficas adicionales de correlación entre edad, presión arterial y tipo de dolor de pecho.

Las gráficas se personalizaron usando el estilo `plt.style.use("seaborn-v0_8-muted")` para mantener una estética limpia y profesional.

 Conclusión y reflexión
El análisis mostró una relación evidente entre el aumento del colesterol y la edad, además de que ciertos tipos de dolor de pecho se asocian más con valores altos de presión y colesterol.  
En general, este proyecto refuerza la importancia de la **prevención temprana** y el **control de hábitos saludables** para reducir el riesgo de enfermedad cardíaca.

Reflexión personal:
 Me pareció muy interesante ver cómo los datos pueden contar una historia. No solo es programar o graficar, sino entender lo que hay detrás: cada número representa una persona, y analizar estos datos puede servir para salvar vidas. Me dejó con la idea de que la ciencia de datos no solo es técnica, también tiene un lado muy humano.
