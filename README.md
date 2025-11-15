# Taller de Rendimiento
Repositorio para el taller de evaluación de rendimiento

## Descripción 
Lo desarrollado en este trabajo fue el algoritmo clásico para la multiplicación de matrices, a través del cual se pudieron evaluar diferentes métodos de paralelismo, como el
uso de procesos con fork, otro con hilos POSIX y dos con directivas OpenMP (una simple
y la otra mejor optimizada por las filas).
En general, lo que se hizo fue ver el contraste entre los cambios de tiempo sobre las
distintas ejecuciones al modificar el tamaño de las matrices y la cantidad de hilos, así
como observar cómo los diferentes métodos utilizan los recursos del sistema, teniendo en
cuenta lo visto en las clases.

## Compilación 
Para correr el programa des linux primero se entra al archivo de CodigoRendimiento, luego el make y finalmente ./lanzador.pl

## Medición de Rendimiento
Se analizaron tiempos de ejecución variando:

Tamaño de matrices: 600×600, 800×800, 1200×1200, 2400×2400

Cantidad de hilos: 1, 2, 4, 12, 32
Cada combinación se ejecutó 30 veces, aplicando la ley de los grandes números para asegurar estabilidad en los datos.

## Autores 
Danna Gabriela Rojas Bernal

Christian Becerra Enciso

María Fernanda Velandia Gracia

Giovanny Andrés Durán Rentería

