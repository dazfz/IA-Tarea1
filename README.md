# Descripcion
Codigo en C++ que implementa: 
 -	Búsqueda en profundidad (escogiendo un sucesor al azar)
 -	Búsqueda por costo uniforme
 -	Búsqueda greedy
 -	A*

Para hacerlo, se crea un struct nodo, que contiene los datos del nodo (nombre, heuristica, etc.) y un vector que apunta a sus nodos vecinos.  
Luego, dependiendo del tipo de busqueda, se escoge un nodo del vector que apunta a los vecinos para la siguiente itercion (todo dentro de un loop).  
Finalmente, al encontrar un nodo hoja (sin vecinos) o el nodo solución, se detendra la busqueda.
# Instrucciones

