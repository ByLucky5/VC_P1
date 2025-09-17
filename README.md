# VC_P1

Práctica realizada por el grupo 15 (Lucía Motas Guedes y Raúl Marrero Marichal)

## Ejercicio 1

Se comienza generando una imagen de fondo completamente negro de dimensión 800x800 px.

Para lograr el efecto de tablero de ajedrez, se itera a través de las "casillas", pintando cuadrados blancos de 100x100 px de forma alterna en función del índice de fila (i) y columna (j). No es necesario pintar cuadrados negros ya que el propio fondo es del color deseado.

La salida se guarda en el archivo _[ajedrez.jpg](https://github.com/ByLucky5/VC_P1/blob/main/ajedrez.jpg)_.

## Ejercicio 2

En este ejercicio, se parte de una imagen de fondo blanco de 800x800 px.

Se continúa generando rectángulos de distintos colores y posteriormente líneas horizontales y verticales, simulando el estilo del pintor Mondrian. Como las líneas se añaden después que los rectángulos, se muestran sobre los mismos, lo que se puede aprovechar para simplificar los cálculos a la hora de determinar el tamaño exacto de los rectángulos y el grosor de las líneas.

La salida se guarda en el archivo _[mondrian.jpg](https://github.com/ByLucky5/VC_P1/blob/main/mondrian.jpg)_.

## Ejercicio 3

En el tercer ejercicio, sencillamente se invierte el valor del plano azul de un vídeo entrante.

## Ejercicio 4

Para el cuarto ejercicio, se obtienen las posiciones del píxel más claro y oscuro de la imagen mediante la función minMaxLoc y se dibuja un círculo blanco sobre la más oscura y un círculo negro sobre la más clara para que sean fácilmente identificables.

Luego se repite el proceso, pero con bloques de 8x8, usando la suma de los valores de cada región.

Además, este proceso se lleva a cabo y se actualiza en tiempo real sobre una entrada de vídeo.

## Ejercicio 5

En este ejercicio, se busca lograr un efecto similar al ejemplo propuesto por la práctica, pero se opta por usar líneas horizontales blancas sobre un fondo negro. Estas líneas se forman a partir de rectángulos a los que se les varía su altura en función de la intensidad de cada región, dando la impresión de que las líneas varían su grosor.

Para lograr un efecto más notorio, se reduce la resolución del vídeo de entrada y así lograr que los fotogramas resultantes estén claramente formandos por líneas, pero aún así se pueda reconocer la imagen.

### Fuentes consultadas

[Drawing functions - OpenCV](https://docs.opencv.org/4.x/dc/da5/tutorial_py_drawing_functions.html)
