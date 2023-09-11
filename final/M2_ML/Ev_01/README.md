# Version final Evidencia 1 - Modulo 2

- **Estructura del repositorio:** En esta carpeta se tiene el notebook principal el cual funge como reporte realizado. Dentro de este notebook se tiene tanto el desarrollo tecnico (codigo del procesamiento e implementación del modelo) como tambien la descripción del mismo y el analisis de los resultados:
    - README.md: descripcion de la entrega y estructura del repositorio
    - ML_from_scratch.ipynb: reporte y notebook del codigo fuente del modelo

- **Liga notebook:** https://colab.research.google.com/drive/1MLHWhLg2s6TqnxqZ-Mh2Jc2WX3zWvHvH?usp=sharing

- **Archivos a revisar:** final/M2_ML/Ev_01/ ML_from_scratch.ipynb

- **Cambios implementados:**
    - Implementacion de dataset de mejor calidad.
    - Separación de datos de entrenamiento y datos de prueba.
    - Mejoramiento de validacion y evaluacion de los modelos.
    - Correción del contenido de los archivos readme.md del repositorio.
    - Re-organizacion del repositorio.
    - Re-organizacioón de la estructura del notebook.
    - Re-organizacioón de la estructura del reporte.
    - Mejoramiento del analisis de los resultados del modelo implementado.

- **Descripción del Modelo utilizado:** Se eligio este modelo debido al tipo de problema que el dataset seleccionado requiere, donde acorde a las variables presentes, se busca hacer una tarea de clasificacion, la cual puede ser abordada con el modelo de regresión logistica. El modelo de regresión logística es una técnica utilizada para modelar la relación entre una variable binaria dependiente y una o más variables independientes, que pueden ser continuas o categóricas. Este modelo de regresión se utiliza en problemas de clasificación, donde el objetivo es predecir a cuál de las dos clases pertenece una observación. La principal idea detrás de la regresión logística es que la relación entre las variables independientes y la probabilidad de que ocurra un evento (la variable binaria dependiente) se modela utilizando la función logística, también conocida como curva en forma de "S". Esta función toma cualquier valor de entrada y lo transforma en un valor entre 0 y 1, que puede interpretarse como la probabilidad de que el evento ocurra. La función logística permite capturar relaciones no lineales entre las variables independientes y la probabilidad de éxito.

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

- **Enlace:** https://www.kaggle.com/datasets/fedesoriano/heart-failure-prediction?resource=download

- **Descripcion del problema:** En este dataset se busca hacer un modelo de clasificación, donde se tienen dos clases posibles para predecir: "heart disease(1)" y "normal(1)".

- **Estructura del repositorio:** En esta carpeta se tiene el notebook principal el cual funge como reporte realizado. Dentro de este notebook se tiene tanto el desarrollo tecnico (codigo del procesamiento e implementación del modelo) como tambien la descripción del mismo y el analisis de los resultados.

- **Cambios implementados:**
    - Implementacion de dataset de mejor calidad.
    - Separación de datos de entrenamiento y datos de prueba.
    - Mejoramiento de validacion y evaluacion de los modelos.
    - Correción del contenido de los archivos readme.md del repositorio.
    - Re-organizacion del repositorio.
    - Re-organizacioón de la estructura del notebook.
    - Re-organizacioón de la estructura del reporte.
    - Mejoramiento del analisis de los resultados del modelo implementado.
