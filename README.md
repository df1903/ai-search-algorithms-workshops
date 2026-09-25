# Talleres de Algoritmos de Búsqueda e IA

## Integrantes

- Jorge Iván García Torres
- Daniel Felipe Franco Rincón

## Descripción breve de la actividad

Conjunto de talleres prácticos de la asignatura **Sistemas Inteligentes I**, enfocados en algoritmos de resolución de problemas mediante búsqueda. Se abordan estrategias de búsqueda no informada e informada, así como algoritmos de búsqueda adversarial (juegos con dos jugadores), incluyendo su implementación en Python y análisis de resultados.

## Relación de los notebooks

| Notebook | Contenido |
|---|---|
| `1_Resolucion_Problemas_Busqueda_NoInformada.ipynb` | Búsqueda no informada: BFS y DFS. Representación de problemas mediante espacio de estados. |
| `2_Resolucion_Problemas_Busqueda_Informada.ipynb` | Búsqueda informada: Costo Uniforme, A* y Beam Search. Uso de g(n), h(n) y f(n). |
| `3_Poda_Alfa_Beta.ipynb` | Búsqueda adversarial: poda Alfa-Beta como optimización de Minimax. |
| `4_Minimax.ipynb` | Búsqueda adversarial: algoritmo Minimax para juegos de dos jugadores. |

## Instrucciones mínimas para ejecutar el trabajo

1. Clonar el repositorio:
   ```bash
   git clone <url-del-repositorio>
   cd ai-search-algorithms-workshops
   ```
2. Tener instalado Python 3.9+ y Jupyter (Notebook o JupyterLab):
   ```bash
   pip install notebook matplotlib
   ```
3. Abrir cada notebook en orden con:
   ```bash
   jupyter notebook
   ```
4. Ejecutar las celdas de cada notebook de forma secuencial (de arriba hacia abajo).
