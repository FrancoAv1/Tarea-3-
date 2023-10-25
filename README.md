# Tarea 3 - Algoritmos Metaheurísticos Inspirados en la Naturaleza
Autores:

-Franco Avilés I. (faviles@ing.ucsc.cl)

-Hector Contreras M. (hcontreras@ing.ucsc.cl)

Desarrollar una aplicación que implemente el Problema del Vendedor Viajero a través del método Extremal Optimization.

El código debe de tener al menos las siguientes funciones:
* Generar un número real randóminco entre [0 y 1].
* Generar un número entero randomico entre [1 y N].
* Inicializar el ecosistema.
* Función de evaluación del fitness de cada especie.
* Función de selección de una especie usando el método de la ruleta.
* Función de reemplazo de la especie seleccionada.
* Función de evaluación del ecosistema.

Se deben ingresar y sintonizar los siguientes parámetros:
* Archivo de entrada.
* Valor semilla generador valores randómicos.
* Condición de término o número de iteraciones.
* Valor de Tau.
## Instalación
Requisitos: Python 3.8.10 disponible en sistema operativo.

## Ejecución
Para ejecutar, escribir en consola o terminal:
```ruby
py mochila.py <Semilla> <Archivo> <Tamaño_Pob> <Iteraciones> <TI> <TF>
```
donde:
* Archivo: Archivo de entrada con los elementos de la mochila.
* Semilla: Valor entero que tomará última semilla a evaluar (desde el 1 hasta Semilla).
* Iteraciones: Condición de término o número de iteraciones. Valor entero.
* TI: Valor inicial de Tau.
* TF: Valor final de Tau.

* ## Ejemplo
```ruby
py mochila.py 
```
