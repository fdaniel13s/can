# Complexity Algorithm 202401 Notes

## Dijkstra vs DFS

Dijkstra es una versión base de DFS.
Relajacion es un concepto que busca el camino mas corto
Utiliza cola de prioridad


Busquedas informadas vs Busquedas no informadas.

Busqueda de informacion -> informacion del objetivo  -> heuristicas -> medidas de distancia y medidas de similitud y etc. con distancias euclidiana y distancia manhattan. 
bUSQUEDA DE NO INFORMADA -> no hay info del objetivo

Algoritmo A* (Astar)
Diferencia a dijkstra este contiene informacion (heuristica).

f(V) = G(V) + H(V)

g(U) = COSTO TOTAL DE S HASTA U

H(V) = heuristica de v hsta t

https://qiao.github.io/PathFinding.js/visual/

REPASAR PARA PARCIAL ALGORITMO A STAR 
