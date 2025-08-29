# RNA para Compuertas Lógicas en Wolfram

Este proyecto implementa Redes Neuronales Artificiales (RNA) simples en Wolfram Language para simular el comportamiento de las compuertas lógicas AND, OR y XOR.


## Objetivo

- Mostrar cómo entrenar una red neuronal con datos básicos de verdad.
- Comparar la capacidad de la RNA para aprender compuertas separables linealmente (AND, OR) y no lineal (XOR)


## Requisitos

- Wolfram Mathematica o Engine
- Archivo en formato ``` .nb ```


## Tablas de verdad

### AND
|  x_1  |  x_2  |  Salida  |
| ----- | ----- | -------- |
|   0   |   0   |     0    |
|   0   |   1   |     0    |
|   1   |   0   |     0    |
|   1   |   1   |     1    |


### OR
|  x_1  |  x_2  |  Salida  |
| ----- | ----- | -------- |
|   0   |   0   |     0    |
|   0   |   1   |     1    |
|   1   |   0   |     1    |
|   1   |   1   |     1    |


### XOR
|  x_1  |  x_2  |  Salida  |
| ----- | ----- | -------- |
|   0   |   0   |     0    |
|   0   |   1   |     1    |
|   1   |   0   |     1    |
|   1   |   1   |     0    |


## Ejecución
1. Abrir ``` RNA_OR-AND-XOR.nb ``` en Wolfram Mathematica.
2. Evaluar las celdas (``` ctrl + Shift + Enter ```).
3. Ver resultados y predicciones de cada compuerta.

## Resultados
- Para AND y OR, la red aprende rápido y predice sin error.
- Para XOR, la red necesita más neuronas, pero finalmente logra clasificar correctamente.
