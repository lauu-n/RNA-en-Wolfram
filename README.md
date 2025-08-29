# RNA para Compuertas Lógicas en Wolfram

Este proyecto implementa Redes Neuronales Artificiales (RNA) simples en Wolfram Language para simular el comportamiento de las compuertas lógicas AND, OR y XOR.


## Introducción 

- Una red neuronal es un modelo de aprendizaje automático que toma decisiones como el cerebro humano. Funciona reproduciendo cómo las neuronas en el cuerpo trabajan juntas para reconocer patrones, evaluar opciones y lograr resultados.
- Las compuertas lógicas son un ejemplo para entender cómo las RNA pueden modelar funciones booleanas. Las compuertas AND y OR son problemas linealmente separables, lo que significa que pueden resolverse con un solo perceptrón (una capa). En cambio, la compuerta XOR es un problema no linealmente separable, lo que requiere al menos dos capas o una combinación de perceptrones.


## Objetivos

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


## Descripción 

El código implementa perceptrones simples en Wolfram Language para simular compuertas lógicas:
- Función escalón (stepFunction): define la activación de las neuronas, devolviendo 0 o 1 según el valor de entrada.
- Compuertas AND y OR: implementadas con un único perceptrón, utilizando combinaciones lineales de las entradas y un umbral.
- Compuerta XOR: construida a partir de la combinación de dos perceptrones ocultos (OR y NAND) y una neurona de salida (AND).
- Generación de tablas de verdad: el código evalúa todas las combinaciones de entrada y muestra las salidas correspondientes de cada compuerta.

## Ejecución
1. Abrir ``` RNA_OR-AND-XOR.nb ``` en Wolfram Mathematica.
2. Evaluar las celdas (``` ctrl + Shift + Enter ```).
3. Ver resultados y predicciones de cada compuerta.

## Resultados
- Para AND y OR, la red aprende rápido y predice sin error.
- Para XOR, la red necesita más neuronas, pero finalmente logra clasificar correctamente.


### Referencias
[¿Qué es una red neuronal? (2025, febrero 21). IBM](https://www.ibm.com/es-es/think/topics/neural-networks)
[Compuertas lógicas – Sistemas Digitales. (s/f). Unam.mx](https://virtual.cuautitlan.unam.mx/intar/sistdig/compuertas-logicas/)

