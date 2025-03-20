# first-neuronal-network

En este proyecto, hemos desarrollado una red neuronal utilizando TensorFlow/Keras para predecir la presencia de diabetes en pacientes en función de diversos factores de salud. A lo largo del proceso, implementamos técnicas clave para mejorar el rendimiento del modelo.


Preprocesamiento de Datos:

Se utilizó el dataset de Pima Indians Diabetes, el cual fue limpiado y normalizado mediante StandardScaler para mejorar la convergencia del modelo.
Se dividieron los datos en un 80% para entrenamiento y 20% para prueba.

Arquitectura de la Red Neuronal:

La red neuronal mejorada cuenta con tres capas ocultas (Dense con activación ReLU).
Se agregaron capas de Dropout (0.3) para prevenir el sobreajuste.
La capa de salida usa una activación Sigmoid para clasificación binaria (0: No tiene diabetes, 1: Tiene diabetes).

Entrenamiento y Evaluación:

Se entrenó el modelo con 50 épocas y batch size de 10.
Se utilizó binary_crossentropy como función de pérdida y adam como optimizador.
La precisión alcanzada en el conjunto de prueba se imprimió como resultado final.

Para acceder al archivo usar el siguiente link:
https://colab.research.google.com/drive/1q_jDJGAtmB17uUjnVD8esxswSwkE-6F7#scrollTo=pDhvgSkIs2NS&uniqifier=1
