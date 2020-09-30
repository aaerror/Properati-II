# **Proyecto 02**: Ingeniería de features, Modelos avanzados e Interpretación de modelos

## **Consigna**

En este proyecto profundizarás lo desarrollado en el Proyecto 01 (“Primer modelo de Machine Learning”). El objetivo es aplicar las técnicas incorporadas (Transformación de Datos, Optimización de Hiperparámetros, Modelos Avanzados, etc.) para generar un modelo que tenga un mejor desempeño que el modelo generado en el proyecto anterior. Luego, interpreta ese modelo para responder la siguiente pregunta: ¿qué podemos aprender de nuestro problema estudiando el modelo que generamos?

### Etapas

El trabajo se organiza en tres partes:

---
* **Parte A**: Transformación de Datos
  
    Elige cuáles de las siguientes tareas son apropiadas para su dataset. Justifica e implementa:
    * Encoding.    
    * Imputación de valores faltantes.
    * Detección y eliminación de Outliers.
    * Escalado de datos.
    * Generación de nuevas variables predictoras/reducción de dimensionalidad (SVD/PCA).
    
  
  Vuelve a entrenar el modelo implementado en la Entrega 01 —*en particular, el árbol de decisión—* y evalúa su desempeño a partir del dataset obtenido luego de transformar los datos. ¿Hay una mejora en su desempeño? Sea cual sea la respuesta, intenta explicar a qué se debe.

---

* **Parte B**: Modelos Avanzados

    * Elige dos de los modelos avanzados vistos (en el caso de regresión, considera una regresión lineal con atributos polinómicos y regularización). Entrénalos y evalúalos con sus argumentos por defecto. No te olvides de hacer un train/test split y usar Validación Cruzada.

    * Optimiza sus hiperparámetros mediante Validación Cruzada y Grid Search o Random Search.

    * Compara el desempeño de los nuevos modelos entre sí y con el modelo de la Parte A. ¿Cuál elegirías? Justifica.

---
* **Parte C**: Interpretación de modelos

    De acuerdo a lo que el modelo permite, responde algunas o todas las siguientes preguntas:

    * ¿Qué variables fueron relevantes para el modelo para hacer una predicción? ¿Cuáles no? Si usaste una regresión lineal con regularización, presta atención a los parámetros (pendientes) obtenidas. Si usaste un modelo de ensamble en árboles, además de ver la importancia de cada atributo, también elige algunos árboles al azar y observa qué atributos considera importantes. ¿En qué se diferencian esos árboles? ¿Por qué? Finalmente, responde, ¿coincide con lo que esperabas a partir de tu experiencia con este dataset?.

    * ¿Cómo es la distribución de errores (regresión) o qué clases se confunden entre sí (clasificación)? ¿Dónde falla? ¿A qué se debe?.
---

### DESAFÍO OPCIONAL

Aplica una técnica de Clustering sobre el dataset. Puedes combinar con técnicas de reducción de dimensionalidad para facilitar la visualización. ¿Qué clusters encuentras? ¿A qué pueden corresponder? Te dejamos preguntas que pueden servir como disparadoras: ¿qué barrios se parecen más entre sí? ¿qué tipos de propiedades se parecen más entre sí?