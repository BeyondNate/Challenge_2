# Challenge 1: Pipeline de Machine Learning

**Caso Tipo A: Minería de Asteroides**

## Datos generales

- **Curso:** Machine Learning
- **Unidad:** Fundamentos de Machine Learning
- **Unidad N.°:** 2
- **Docente:** Yannick Patrick Carrasco Merma
- **Fecha de preparación:** 06/10/2026
- **Modalidad:** Individual
- **Herramientas:** GitHub, Google Colab y Python

## 1. Presentación del caso y problema

### Descripción del caso

La minería de asteroides se plantea como un escenario de exploración en el que se busca identificar muestras que contengan materiales de interés, como platino, níquel, cobalto y tierras raras.

Este proyecto desarrolla una simulación computacional de exploración, recolección y clasificación de muestras minerales, integrando algoritmos de búsqueda e inteligencia artificial.

### Planteamiento del problema

¿Cómo puede un sistema inteligente explorar zonas de un asteroide simulado, identificar muestras candidatas y predecir su contenido mineral para apoyar la selección de materiales de interés?

### Objetivo general

Implementar un pipeline de Inteligencia Artificial y Machine Learning que represente la exploración de un asteroide, permita buscar muestras candidatas y utilice un modelo predictivo para estimar una propiedad cuantitativa de las muestras.

### Justificación

Los algoritmos de búsqueda permiten explorar un espacio de estados y encontrar rutas hacia zonas de interés. Por otra parte, Machine Learning permite entrenar un modelo con características de las muestras para estimar una variable objetivo.

La integración de ambas técnicas permite simular un proceso de exploración y selección de materiales mediante herramientas computacionales.

### Alcance

Se utilizarán datos sintéticos y un entorno simplificado. Los resultados representan una demostración académica y no constituyen estimaciones verificadas de depósitos minerales reales.

## 2. Espacio de estados

El problema se representa mediante estados, operadores y restricciones.

- **Estado inicial:** explorador ubicado en la base.
- **Estados intermedios:** zonas pendientes, zonas exploradas y muestras recolectadas.
- **Estados finales:** muestras clasificadas y materiales seleccionados.
- **Operadores:** explorar, desplazarse, recolectar, clasificar y seleccionar muestras.
- **Objetivo:** identificar y seleccionar muestras que cumplan los criterios establecidos.
- **Restricciones:** límite de recolección, zonas accesibles y criterios de selección.

La representación visual del espacio de estados se encuentra en `docs/espacio-estados.md`.

## 3. Pipeline de razonamiento, búsqueda y resultados

**Notebook:** `notebooks/01_Razonamiento_Busqueda.ipynb`

Este pipeline desarrolla las siguientes etapas:

1. Definición del problema.
2. Construcción del espacio de estados.
3. Representación de zonas mediante un grafo.
4. Exploración utilizando búsqueda en amplitud (BFS).
5. Recolección simulada de muestras.
6. Presentación de las zonas visitadas y los resultados obtenidos.

El algoritmo BFS permite recorrer el grafo por niveles y encontrar rutas con el menor número de aristas en un grafo no ponderado.

## 4. Pipeline del modelo de predicción y visualización

**Notebook:** `notebooks/02_Modelo_Predictivo.ipynb`

Se desarrollará un modelo de regresión lineal múltiple para estimar el contenido mineral sintético de una muestra a partir de variables numéricas.

### Variables del modelo

- Densidad de la muestra.
- Indicador espectral sintético.
- Temperatura simulada.
- Contenido mineral estimado como variable objetivo.

### Etapas del pipeline

1. Generación y exploración de datos sintéticos.
2. Selección de variables predictoras y objetivo.
3. División de los datos en entrenamiento y prueba.
4. Entrenamiento del modelo de regresión.
5. Generación de predicciones.
6. Evaluación mediante MAE y R².
7. Visualización de valores reales y predichos.

### Justificación del modelo

La regresión lineal múltiple permite estudiar la relación entre varias variables numéricas y una variable objetivo continua. Su simplicidad facilita interpretar los resultados y establecer una referencia inicial de desempeño.

## 5. Tecnologías utilizadas

- **GitHub:** control de versiones y documentación.
- **Google Colab:** desarrollo y ejecución de notebooks.
- **Python:** implementación del pipeline.
- **NumPy y Pandas:** generación y organización de datos.
- **Matplotlib:** visualización de resultados.
- **Scikit-learn:** entrenamiento y evaluación del modelo.

## 6. Estructura del repositorio

```text
assets/       Recursos gráficos
css/          Estilos de la página web
datos/        Dataset sintético
docs/         Documentación del proyecto
js/           Búsqueda, gráficos y lógica web
notebooks/    Pipelines ejecutables
README.md     Documento principal
index.html    Página de presentación
```

## 7. Resultados esperados

- Representación formal del problema.
- Exploración de zonas mediante BFS.
- Registro de las muestras recolectadas.
- Entrenamiento y evaluación de un modelo de regresión.
- Gráficos para interpretar las predicciones.
- Documentación reproducible y accesible desde GitHub.

## 8. Limitaciones

Los datos son sintéticos y las relaciones utilizadas para generarlos son simplificaciones didácticas. El desempeño obtenido no demuestra que el modelo pueda predecir concentraciones minerales reales en asteroides.

## 9. Autoría

Proyecto individual desarrollado para el curso de Machine Learning, Unidad 2: Fundamentos de Machine Learning.
