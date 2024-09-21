## **Clasificación de Reseñas de Películas con Procesamiento de Lenguaje Natural**

**Introducción**

Este proyecto tiene como objetivo desarrollar un modelo de clasificación capaz de determinar si una reseña de película es positiva o negativa utilizando técnicas de Procesamiento del Lenguaje Natural (PLN) y Aprendizaje Automático.

**Modelado**

Se evaluaron diversos modelos de clasificación, incluyendo:

* **Modelo 1:** Constante
* **Modelo 2:** Lematización, TF-IDF y Regresión Logística
* **Modelo 3:** Lematización con spaCy, TF-IDF y  Regresión Logística
* **Modelo 4:** Lematización con spaCy, TF-IDF y LGBMClassifier

**Resultados**

* **Mejor Modelo:** El Modelo 4 (spaCy, TF-IDF y LGBMClassifier) obtuvo el mejor desempeño con un valor F1 de 0.8889.
* **Métricas:** Se evaluaron los modelos utilizando métricas como precisión, recall y F1-score.


**Conclusiones**

* El Modelo 4 demostró ser el más efectivo en la clasificación de nuevas reseñas, superando el umbral de rendimiento establecido.
* Las técnicas de PLN utilizadas, como la lematización y el uso de TF-IDF, fueron fundamentales para mejorar la precisión de los modelos.
* Los resultados obtenidos muestran el potencial de las técnicas de PLN y aprendizaje automático para analizar opiniones y sentimientos en texto.
