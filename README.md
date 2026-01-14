# Método de Euler para una Ecuación Diferencial Separable

## Problema

Se considera la ecuación diferencial separable:

dy/dt = y^2,  con y(0) = 1

La solución exacta usando separación de variables es:

y(t) = 1 / (1 - t)

## Método de Euler

Se implementa el método de Euler para aproximar la solución en el intervalo [0,1] con paso h = 0.2.

## Resultados

El script `euler.py` imprime los valores aproximados usando Euler y los compara con la solución exacta, además de generar un gráfico.
