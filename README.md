# Challenge 1: Pipeline de Machine Learning

## 1. Datos generales

- **Docente:** Yannick Patrick Carrasco Merma
- **Curso:** Machine Learning
- **Unidad:** Fundamentos de Machine Learning
- **Fecha de preparación:** 06/10/2026
- **Caso:** Tipo A — Minería de asteroides

## 2. Presentación del caso

La minería de asteroides plantea la posibilidad de identificar y recuperar materiales de interés presentes en cuerpos celestes. Para este proyecto se propone un sistema inteligente que simula la exploración de un asteroide, detecta muestras minerales, clasifica los materiales encontrados y selecciona aquellos que cumplen los criterios establecidos para su recuperación.

El sistema representará las etapas de exploración, recolección, clasificación y selección de materiales mediante un pipeline computacional. Se utilizarán datos sintéticos para simular las características de las muestras, ya que el objetivo académico es estudiar la aplicación de técnicas de Inteligencia Artificial y Machine Learning en un escenario controlado.

## 3. Planteamiento del problema

Durante una exploración espacial simulada, el sistema debe decidir qué zonas visitar, qué muestras recolectar y cuáles presentan características compatibles con los materiales de interés. La exploración está limitada por la cantidad de muestras que se pueden recolectar y por los recursos disponibles.

El problema consiste en diseñar un sistema que explore las zonas disponibles, identifique las muestras candidatas y utilice un modelo predictivo para estimar una propiedad cuantitativa relacionada con su valor mineralógico.

## 4. Objetivo general

Desarrollar un pipeline de Inteligencia Artificial y Machine Learning que simule la exploración de un asteroide, permita buscar y clasificar muestras minerales y prediga una propiedad cuantitativa de interés para apoyar la selección de materiales.

## 5. Justificación del uso de Inteligencia Artificial y Machine Learning

La Inteligencia Artificial permite representar el proceso de exploración como un problema de búsqueda en un espacio de estados. Mediante algoritmos de exploración, el sistema puede recorrer zonas, identificar muestras y cumplir restricciones establecidas.

Por su parte, Machine Learning permite aprender relaciones entre las características de las muestras y una variable objetivo. En este proyecto se utilizará un modelo de regresión para predecir un indicador cuantitativo de contenido mineral a partir de datos sintéticos.

La combinación de ambas técnicas permite integrar la búsqueda de candidatos con la predicción de sus propiedades, aunque los resultados serán únicamente una simulación académica y no una estimación validada de recursos minerales reales.

## 6. Objetivos específicos

1. Definir el problema y representar formalmente sus estados, operadores y restricciones.
2. Implementar un algoritmo de búsqueda para explorar las zonas del asteroide.
3. Generar un conjunto de datos sintéticos con características de muestras minerales.
4. Entrenar y evaluar un modelo de regresión.
5. Visualizar los resultados para interpretar las predicciones y sus errores.

## 7. Alcance y limitaciones

El proyecto se desarrollará en Python mediante Google Colab y se documentará en GitHub. Se utilizarán datos sintéticos y una representación simplificada del entorno. Por ello, el sistema no representa una misión espacial real ni demuestra la viabilidad económica o técnica de extraer minerales de asteroides.
