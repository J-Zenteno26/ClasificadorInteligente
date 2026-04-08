# Clasificador de Prendas con Redes Neuronales (Deep Learning)

Este proyecto implementa un modelo de clasificación de imágenes utilizando Redes Neuronales Artificiales (RNA) y técnicas de Deep Learning para identificar distintos tipos de prendas de vestir a partir de imágenes.

## Objetivo

Desarrollar un modelo capaz de clasificar automáticamente prendas de ropa en distintas categorías, utilizando datos de imágenes y técnicas de aprendizaje profundo, con el fin de simular un sistema de reconocimiento visual aplicado a e-commerce o sistemas inteligentes.

## Enfoque del Proyecto

El proyecto se desarrolla en las siguientes etapas:

### 1. Preparación de Datos
- Uso del dataset Fashion MNIST
- Normalización de imágenes
- División en conjuntos de entrenamiento y prueba

### 2. Modelado con Redes Neuronales
- Implementación de redes neuronales artificiales
- Uso de arquitecturas de Deep Learning (incluyendo CNN)
- Entrenamiento del modelo

### 3. Evaluación del Modelo
- Métricas de desempeño (accuracy, precision, recall, f1-score)
- Análisis de resultados por clase
- Validación del modelo

### 4. Visualización de Resultados
- Curvas de entrenamiento (loss y accuracy)
- Matriz de confusión
- Predicciones del modelo sobre imágenes reales

## Resultados

El modelo alcanza un desempeño sólido en la clasificación de prendas:

- Accuracy global: 0.91 :contentReference[oaicite:0]{index=0}  
- Loss: 0.2545 :contentReference[oaicite:1]{index=1}  

Se observa un buen rendimiento en categorías como:
- Trouser, Sandal, Bag y Sneaker (alta precisión)

Y mayor dificultad en:
- Shirt (menor precisión relativa)

## Ejemplos de Predicción

El modelo es capaz de identificar correctamente distintas prendas, como pantalones, camisetas, calzado y accesorios, incluso en imágenes no vistas durante el entrenamiento.

## Tecnologías Utilizadas

- Python
- TensorFlow / Keras
- NumPy
- Matplotlib
- Scikit-Learn

## Valor del Proyecto

Este proyecto demuestra la capacidad de:

- Implementar modelos de Deep Learning
- Trabajar con imágenes y datos no estructurados
- Evaluar modelos de clasificación
- Interpretar resultados de redes neuronales

## Conclusión

Las redes neuronales permiten resolver problemas complejos de clasificación de imágenes con un alto nivel de precisión. Este tipo de modelos tiene aplicaciones directas en sistemas de recomendación, e-commerce y visión computacional.
