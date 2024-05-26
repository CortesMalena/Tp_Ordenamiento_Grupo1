# :trollface: Tp_Ordenamiento_Grupo1
Grupo1

## :purple_heart: Integrantes 
- Barrozo Julieta
- Celis Marilyn
- Contrera Franco
- Cortes Malena

## Proyecto: Ordenamiento.
~~~ Python 
  def ordenamiento_danza(numeros): #Algoritmo de burbuja
    start_time = time.time()  # tiempo de inicio
    
    lista_numeros = len(numeros)  # Esto guarda la longitud de la lista
    # Se itera sobre todos los elementos
    for i in range(lista_numeros): 
        for j in range(0, lista_numeros - i - 1): 
            if numeros[j] > numeros[j+1]: #numero[j] es el primer elemento / numero[j] > numero[j+1] verifica si el número actual es mayor que el siguiente número
                numeros[j], numeros[j+1] = numeros[j+1], numeros[j] # Si es mayor, se realiza un intercambio de valores entre numeros[j] y numeros[j+1]
    
    end_time = time.time()  # Finaliza el tiempo
    elapsed_time = end_time - start_time  # Calcula el tiempo transcurrido
    print("Tiempo de ejecución Algoritmo Ordenamiento_Danza:", elapsed_time, "segundos")
    
    return numeros
~~~

## :walking: Descripción:
En base a este video https://www.youtube.com/watch?v=kdtYU6VNfww&t=1s se detallaron el paso a paso:

Primera ronda :one: :
- Paso 1: El 0 y el 3 se enfrentan y cambian de posición.
- Paso 2: El 3 y el 1 cambian de lugar.
- Paso 3: El 1 y el 0 se enfrentan pero no cambian.
- Paso 4: El 3 y el 4 se enfrentan sin cambio.
- Paso 5: El 7 y el 4 se enfrentan sin cambio.
- Paso 6: El 7 y el 2 cambian de lugar.
- Paso 7: El 2 cambia con el 4.
- Paso 8: El 2 cambia con el 3.
- Paso 9: El 2 y el 1 se enfrentan sin cambio.
- Paso 10: El 7 y el 5 cambian de lugar.
- Paso 11: El 5 y el 4 se enfrentan sin cambio.
- Paso 12: El 7 y el 6 cambian de lugar.

Segunda ronda :two: :
- Paso 1: El 0 y el 3 cambian de lugar.
- Paso 2: El 3 cambia con el 1.
- Paso 3: El 3 y el 4 se enfrentan sin cambio.
- Paso 4: El 4 y el 7 se enfrentan sin cambio.
- Paso 5: El 7 y el 2 cambian de lugar.
- Paso 6: El 7 cambia con el 5.
- Paso 7: El 7 cambia con el 6.
- Paso 8: El 0 y el 1 se enfrentan sin cambio.
- Paso 9: El 1 y el 3 se enfrentan sin cambio.
- Paso 10: El 3 y el 4 se enfrentan sin cambio.
- Paso 11: El 2 y el 4 cambian de lugar.
- Paso 12: El 4 y el 5 se enfrentan sin cambio.
- Paso 13: El 5 y el 6 se enfrentan sin cambio.
- Paso 14: El 1 y el 0 se enfrentan sin cambio.
- Paso 15: El 3 y el 1 se enfrentan sin cambio.
- Paso 16: El 2 y el 3 cambian de lugar.

## :heavy_check_mark: :x: Ventajas y Desventajas
Algoritmo de Danza :dancer:
- Tiempo de ejecucion: 0,069 segundos
- Numero de comparaciones: Este algoritmo por cada iteracion compara un numero con el siguiente
- para determinar si es necesario realizar un intercambio,
- Ventajas: Es un algoritmo simple y facil de entender y es para listas chicas o casi ordenadas
- Desventajas: Tiene un mal rendimiento con listas grandes debido a su complejidad cuadratica

Algoritmo de Seleccion :point_left:
- Tiempo de ejecucion: 0,026 Segundos
- Numero de comparaciones: Similar al algoritmo de Danza, el algoritmo de Selección también
  realiza comparaciones entre elementos para encontrar el elemento mínimo en cada
  iteración.
- Ventajas: Es simple y requiere menos intercambios que el de Danza, lo que es beneficioso cuando los intercambios son grandes
- Desventajas: Es mas eficiente que el algoritmo anterior pero tiene mas complejidad cuadratica, lo que hace que sea mas a corde con listas mas
  grandes

Algoritmo de ordenamiento rapido (QuickSort) :running:
- Tiempo de ejecucion: 0,015 Segundos
- Numero de comparaciones: Utiliza un enfoque de dividir y conquistar, implica comparaciones menos directas que los anteriores. Divide elementos
  para posteriormente ser comparados entre si
- Ventajas: Es muy eficiente en la mayoria de los casos especialmente en grandes listas, Es muy rapido en comparacion con los algoritmos de
  complejidad cuadratica (Danza y selection)
- Desventajas: Su complejidad es mas grande que la de algunos algoritmos 

## :page_with_curl: Conclusion
El algoritmo de Quick Sort se destaca como el más eficiente en términos de tiempo de ejecución para esta lista en específica. Aunque tiene una complejidad mas alta que los otros dos algoritmos, su rendimiento promedio es significativamente mejor que los otros dos algoritmos. Esto sugiere que, para casos generales de ordenamiento, Quick Sort es la mejor opcion debido a su eficiencia y rendimiento consistentemente alto.
Sin embargo, la elección del algoritmo de ordenamiento también puede depender de otros factores, como la memoria disponible, la estabilidad del algoritmo y la facilidad de implementación. 

## :link: Link al proyecto
- [QuickSort](https://onlinegdb.com/OPZZ4EQI3)
- [Coreografia](https://onlinegdb.com/aHRJ6hFYK)


---