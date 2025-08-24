# Simulación marcha aleatoria una dimensión

Este programa simula una marcha aleatoria demostrando el Teorema del Límite Central y el cálculo de la constante de difusión.

Parámetros de entrada

'a'es la longitud del paso
'N' es la cantidad de pasos
'repeticiones' es la cantidad de veces que se repite la simulación

Para la gráfica titulada 'Simulación marcha aleatoria' se utilizaron los siguientes parámetros:

'a' = 1
'N' = 1000
'repeticiones' = 100000

A medida que se aumentan el número de pasos y repeticiones, el histograma de la simulación adquiere la forma de una distribución gaussiana. De hecho, si se cambian los parámetros 'N' = 10000 y 'repeticiones' = 1000000, el programa se demora aproximadamente tres minutos en ejecutar pero, se logra visualizar un histograma con una distribución gaussiana casi idéntica.

Posteriormente, se tomaron las siguientes cantidades de pasos N = [100, 1000, 10000, 100000] con 100000 repeticiones con el fin de calcular los promedios de <x> y <x^{2}>. Adicionalmente, al graficar <x^{2}> vs N se puede evidenciar que son directamente proporcionales pues, tienen casi un comportamiento lineal perfecto.

Luego, teniendo en cuenta la solución de la ecuación de difusión, sabemos que la varianza crece a un factor de 2D linealmente.

El resultado de la constante de difusión 'D' fue 0.496.

