# Descripcion
Codigo en C++ que implementa: 
 -	Búsqueda en profundidad (escogiendo un sucesor al azar)
 -	Búsqueda por costo uniforme
 -	Búsqueda greedy
 -	A*

 1. Se crea un struct "nodo" , que contiene la información del nodo, como su nombre, heurística, etc. Además, contiene un vector que apunta a sus nodos vecinos para representar las aristas del grafo. 
 2. Dependiendo del tipo de búsqueda seleccionado, se escoge el siguiente nodo del vector de nodos vecinos para la siguiente iteración del algoritmo, dentro de un bucle que se ejecuta hasta encontrar un nodo hoja (sin vecinos) o el nodo solución (o la solución óptima), según la búsqueda seleccionada. 
 3. Finalmente, al encontrar un nodo hoja (sin vecinos) o el nodo solución (o la solución óptima) se detendrá la búsqueda, y además, se almacena el camino, costo, nodos expandidos.

# Instrucciones

