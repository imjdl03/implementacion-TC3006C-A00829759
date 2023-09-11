# Version Final Evidencia 2 - Modulo 2 ML

- **Estructura del repositorio:** En esta carpeta se tiene el notebook principal el cual funge como reporte realizado. Dentro de este notebook se tiene tanto el desarrollo tecnico (codigo del procesamiento e implementación del modelo) como tambien la descripción del mismo y el analisis de los resultados:
    - README.md: descripcion de la entrega y estructura del repositorio
    - final/M2_ML/Ev_02/ML_from_framework.ipynb: reporte y notebook del codigo fuente del modelo

- **Liga notebook:** https://colab.research.google.com/drive/1OVa4RdI_LRNSA5zla2e3EZElquLlJHoC?usp=sharing

- **Archivos a revisar:** final/M2_ML/Ev_02/ML_from_framework.ipynb

- **Cambios implementados:**
   - Se añadió el numero de registros del dataset utilizado
   - Se añadió la descripción de las metricas de evaluacion para el subconjunto de pruebas.
   - Se añadieron predicciones realizadas con el modelo entrenado, para datos diferentes a los de entrenamiento.
   - Se hizo una comparación entre las predicciones generadas y los valores que debieron obtenerse.


- **Descripción del Modelo utilizado:** Se eligio este modelo debido al tipo de problema que el dataset seleccionado requiere, donde acorde a las variables presentes, se busca hacer una tarea de clasificacion binaria, la cual puede ser abordada con el modelo de regresión logistica, el cual es diseñado especificamente para esta tarea. El modelo de regresión logística es una técnica utilizada para modelar la relación entre una variable binaria dependiente y una o más variables independientes, que pueden ser continuas o categóricas. Este modelo de regresión se utiliza en problemas de clasificación, donde el objetivo es predecir a cuál de las dos clases pertenece una observación. La principal idea detrás de la regresión logística es que la relación entre las variables independientes y la probabilidad de que ocurra un evento (la variable binaria dependiente) se modela utilizando la función logística, también conocida como curva en forma de "S". Esta función toma cualquier valor de entrada y lo transforma en un valor entre 0 y 1, que puede interpretarse como la probabilidad de que el evento ocurra. 

- **Dataset utilizado:** Heart Failure Prediction
  
- **Descripción y contexto del problema a resolver:** Las enfermedades cardiovasculares son la principal causa de muerte en todo el mundo, cobrando cerca de 17.9 millones de vidas al año y representando el 31% de todas las muertes. La mayoría de estas muertes son por ataques cardíacos y accidentes cerebrovasculares, y muchas ocurren prematuramente en personas menores de 70 años. La insuficiencia cardíaca también es común debido a estas enfermedades. Un conjunto de datos con 11 características puede ayudar a predecir posibles problemas cardíacos. Las personas con enfermedades cardíacas o alto riesgo cardiovascular, debido a factores como hipertensión o diabetes, necesitan detección temprana y manejo, donde un modelo de aprendizaje automático puede ser muy útil.

- **Atributos o campos:**
  - Age: edad del paciente
      - años
  - Sex: sexo del paciente
      - M: Male, F: Female
  - ChestPainType: tipo de dolor de pecho
      - TA: Typical Angina, ATA: Atypical Angina, NAP: Non-Anginal Pain, ASY: Asymptomatic
  - RestingBP: presión arterial en reposo
      - mm Hg
  - Cholesterol: colesterol
      - mm/dl
  - FastingBS: azucar en la sangre en ayunas
      - 1: si FastingBS > 120 mg/dl, 0: otro
  - RestingECG: resultados de electrocardiograma en reposo
      - Normal: Normal, ST: Anomalía de la onda ST-T (inversiones de onda T y/o elevación o depresión del segmento ST > 0.05 mV), LVH: mostrando hipertrofia ventricular izquierda probable o definitiva según los criterios de Estes.
  - MaxHR: frecuencia cardíaca máxima alcanzada
      - Valor numero entre 60 y 202
  - ExerciseAngina: angina inducida por el ejercicio
      - Y: Yes, N: No
  - Oldpeak: Descenso antiguo = ST
      - Valor numerico
  - ST_Slope: La pendiente del segmento ST durante el ejercicio máximo
      - Up: upsloping, Flat: flat, Down: downsloping
  - HeartDisease: salida
      - 1: heart disease, 0: Normal
  - Numero de registros: 918

- **Enlace:** https://www.kaggle.com/datasets/fedesoriano/heart-failure-prediction?resource=download

- **Descripcion del problema:** En este dataset se busca hacer un modelo de clasificación, donde se tienen dos clases posibles para predecir: "heart disease(1)" y "normal(1)".

