# Proyecto4
Archivo de texto con comentarios del proyecto 4 sobre modulación digital

El tema central del proyecto 4 radica en la modulación digital QPSK, donde se trabaja con el código de la modulación BPSK, y 
se modifica este mismo, en cada etapa, para obtener las nuevas señales e imágenes. La modulación BPSK tiene dos símbolos posibles (0, 1) lo 
que implica un bit b1por símbolo, mientras que la modulación QPSK (Quadrature Phase-Shift Keying) tiene cuatro símbolos posibles (00, 01, 10, 11), 
con dos bits  𝑏1𝑏2 por simbolo. Para lograr la modulación se crea un vector de bits, se define la frecuencia de la portadora en Hz, la cantidad de 
muestras por periodo de onda portadora, un vector con la señal modulada, un valor con la potencia promedio [W], la onda portadora c(t) y la onda 
cuadrada moduladora (información).

Posteriormente se busca evaluar la estacionaridad segun los datos obtenidos de la señal senal_Tx. En este caso se visualiza
un histograma de los datos de senal_Tx y se denota  la estructura del histograma. Si tiene forma nomal(gaussiana) es estaciona-
rio, de lo contrario no es estacioanrio. Se puede notar también que existe una estacionaridad o no, si se evalúa la media y varianza.
Para esto se analizó  en multiples partes o secciones de los datos, si coinciden los valores o no, y se compara los resultados.

También se trabajó la ergodicidad de la señal. Para esto se busca determinar si el promedio temporal de los datos es igual o no al promedio del conjunto 
de los mismos. En este caso se implementa una función para conocer los valores.

Finalmente se determina y grafica la densidad espectral de potencia. Esto se logra con la ayuda de la transformada rápida de Fourier y el estable-
cimiento de los valores de frecuencia, etc. De tal manera que se alcanza los objetivos del proyecto.
