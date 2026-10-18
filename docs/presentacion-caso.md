# Presentación del caso: Minería de Asteroides

## 1. Datos generales

- **Curso:** Machine Learning
- **Unidad:** Fundamentos de Machine Learning
- **Docente:** Yannick Patrick Carrasco Merma
- **Fecha de preparación:** 06/10/2026
- **Caso:** Tipo A — Minería de Asteroides
- **Modalidad:** Individual

## 2. Descripción del caso

La minería de asteroides se plantea como un escenario de exploración espacial en el que se busca identificar materiales de interés, como platino, níquel, cobalto y tierras raras.

El proyecto propone simular la exploración de diferentes zonas de un asteroide, recolectar muestras y clasificarlas mediante un sistema computacional. Posteriormente, se empleará un modelo de Machine Learning para predecir el contenido mineral estimado de cada muestra a partir de sus características.

## 3. Planteamiento del problema

¿Cómo puede un sistema inteligente explorar las zonas de un asteroide simulado, identificar muestras candidatas y predecir su contenido mineral para apoyar la selección de materiales de interés?

## 4. Objetivo general

Desarrollar un pipeline de Inteligencia Artificial y Machine Learning que permita explorar un entorno simulado, buscar muestras minerales y predecir su contenido mineral mediante un modelo de regresión.

## 5. Justificación de la Inteligencia Artificial

La Inteligencia Artificial permite representar el proceso de exploración como un problema de búsqueda. Mediante un grafo y el algoritmo de búsqueda en amplitud (BFS), el sistema puede recorrer las zonas disponibles y encontrar rutas hacia zonas de interés.

Machine Learning permite aprender relaciones entre las características de las muestras y una variable numérica objetivo. Se utilizará regresión lineal para estimar el contenido mineral a partir de datos sintéticos.

La combinación de ambas técnicas permite integrar la exploración con la predicción de propiedades de las muestras.

## 6. Alcance

El proyecto se desarrollará en Python mediante Google Colab y se documentará en GitHub. Se utilizarán datos sintéticos definidos directamente en el código, sin depender de archivos externos.

Los resultados constituyen una simulación académica y no representan mediciones reales de asteroides ni estimaciones verificadas de recursos minerales.
