# Espacio de Estados: Minería de Asteroides

## 1. Estado inicial

El explorador se encuentra en la base del asteroide y todavía no ha recolectado muestras.

## 2. Estados del sistema

- **Base:** punto inicial de la exploración.
- **Zona pendiente:** zona que todavía no ha sido visitada.
- **Zona explorada:** zona inspeccionada por el sistema.
- **Muestra recolectada:** muestra incorporada al inventario.
- **Muestra clasificada:** muestra evaluada según sus características.
- **Muestra seleccionada:** muestra que cumple los criterios definidos.
- **Proceso finalizado:** se alcanza el límite de recolección o no quedan zonas por explorar.

## 3. Operadores

1. Explorar una zona conectada.
2. Desplazarse a una zona vecina.
3. Recolectar una muestra disponible.
4. Clasificar una muestra.
5. Seleccionar una muestra candidata.
6. Finalizar la exploración.

## 4. Restricciones

- El explorador solo puede desplazarse entre zonas conectadas.
- Una zona no debe procesarse repetidamente.
- El límite de recolección será de 10 muestras.
- La clasificación se realizará mediante criterios definidos en el programa.

## 5. Estado objetivo

Identificar y seleccionar muestras que cumplan los criterios establecidos o finalizar cuando no existan más zonas disponibles.

## 6. Algoritmo de búsqueda

Se utilizará BFS (Breadth-First Search o búsqueda en amplitud), que explora primero los vecinos más cercanos y permite encontrar rutas con el menor número de aristas en un grafo no ponderado.

## 7. Flujo conceptual

Base → Exploración → Búsqueda de zonas → Recolección → Clasificación → Selección de muestras → Resultado.
