# Detección de Tumores Cerebrales con Redes Neuronales

Este proyecto se centra en la detección de diferentes tipos de tumores cerebrales mediante el uso de una red neuronal convolucional. El conjunto de datos utilizado proviene de Kaggle y contiene cuatro clases de tumores: Glioma, Meningioma, No Tumor y Pituitario.

## Conjunto de Datos

El conjunto de datos se puede encontrar en el siguiente enlace de Kaggle: [Brain Tumor Classification MRI](https://www.kaggle.com/sartajbhuvaji/brain-tumor-classification-mri). Se utilizaron solo los datos de entrenamiento y prueba para el desarrollo del modelo.

## Configuración del Entorno

- Se empleó TensorFlow para el desarrollo de la red neuronal.
- Las imágenes fueron redimensionadas a un tamaño de 150x150 píxeles.
- Se utilizó un conjunto de entrenamiento y otro de prueba, con un tamaño de lote de 32.

## Estructura del Modelo

La arquitectura del modelo se diseñó utilizando capas de convolución, pooling y capas completamente conectadas. La función de activación utilizada en las capas convolucionales fue ReLU, y se aplicó una capa de dropout para evitar el sobreajuste.

## Entrenamiento del Modelo

El modelo se entrenó durante un número específico de épocas, con una función de pérdida de entropía cruzada categórica y el optimizador Adam. Se implementó Early Stopping para prevenir el sobreajuste y se ajustaron los hiperparámetros según sea necesario.

## Resultados

Se observó una brecha significativa entre el rendimiento en el conjunto de entrenamiento y el de prueba, lo que sugiere cierto grado de sobreajuste. Se utilizaron técnicas como la omisión de la carpeta de validación para mejorar el rendimiento, y se realizaron ajustes en la arquitectura del modelo.

## Evaluación del Modelo

Se evaluó el modelo utilizando métricas como precisión, recall y puntuación F1. Se generó una matriz de confusión y se visualizaron las métricas de clasificación.

## Conclusiones

A pesar de los esfuerzos para mejorar el rendimiento, el modelo aún muestra cierta distancia entre los conjuntos de entrenamiento y prueba. Se exploraron diferentes enfoques arquitectónicos, y se presentan los resultados y desafíos encontrados durante el proceso de desarrollo.

Este es el accuracy y el loss de la red neuronal:

<p align="center">
  <img src=https://github.com/Yorchz/Red-Deteccion-Tumores-Cerebrales/assets/90764289/cc33fc8e-0cd2-4742-a318-85df74ae3e92>
</p>



## Contribuciones

¡Se alientan activamente las contribuciones y sugerencias! Si tienes ideas para mejorar la eficiencia, implementar nuevas estrategias de particionamiento, o cualquier mejora en la multiplicación de matrices con Hadoop, ¡no dudes en enviar una solicitud de extracción!

Este proyecto pretende ser un recurso práctico y educativo para aquellos interesados en abordar la multiplicación de matrices en un entorno distribuido utilizando Hadoop. ¡Explora, aprende y contribuye!

