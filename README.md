# PathFinding

## Integrantes
> ---
> ---
> ---

## Enunciado
Implementar **eficientemente** los siguientes algoritmos de búsqueda en grafos y aplicarlo al problema de PathFinding de manera visual.
- Dijkstra
- A*
- Greedy BSF (Opcional, +0.5 examen final)

> **Nota:**
> - El código debe ser original, si se evidencia copia completa, copia parcial o copia estructural, la nota del ejercicio será de 0 y se penaliza con -10 puntos en evaluación contínua.
> - Deben usar sus propios contenedores. 


**Representación del Grafo**:
- Cada celda representa un vertice del grafo
- Los vertices adyacentes son los vecinos en vertical (2), horizontal (2) y diagonal (4). Como máximo 8 vertices adyacentes.
- Considerar como costo de movimiento:
  * Movimiento en horizontal y vertical: 10
  * Movimiento en diagonal: 14
- Implementar dos heurísticas: distancia manhattan y distancia euclidiana

![image](https://github.com/utec-cs-aed/PathFinding/assets/48141762/48c513ba-4a34-4f42-874e-a32a1e50cc72)


**Visualización**:
- Visualizar la ejecución del algoritmo de manera interactiva en consola. 
- Pueden usar interfaz gráfica de usuario (GUI) con cualquier libreria gráfica (Opcional, +1 examen final):
    * [SFML](https://www.sfml-dev.org/)
    * [QT Open Source](https://www.qt.io/download-open-source#source)
    * [WxWidgets](https://www.wxwidgets.org/)
    * [Visual Studio C++](https://visualstudio.microsoft.com/es/vs/features/cplusplus/)
    * [C++ Builder](https://www.embarcadero.com/es/products/cbuilder)

![image](https://github.com/utec-cs-aed/PathFinding/assets/48141762/0836d9ad-ca21-4382-b515-9feb4e467023)



