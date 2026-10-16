---
type: libro
title: "metodo de Ritter (arquitectura)"
author: "aperezg"
categoria: "ESTRUCTURA"
paginas: 8
extraccion: "texto"
fuente: "local:E:/MATERIAL DE CONSULTA/ESTRUCTURA/metodo de Ritter (arquitectura).pdf"
convertido: 2026-10-16
---

# metodo de Ritter (arquitectura)

> Texto extraído de `ESTRUCTURA\metodo de Ritter (arquitectura).pdf` (8 páginas, texto). El PDF original está en el disco E: (MATERIAL DE CONSULTA); `<!-- p. N -->` marca el inicio de cada página.

<!-- p. 1 -->

Cálculo de celosías planas de
nudos articulados con el método de
Ritter

Apellidos, Nombre Pérez García, Agustín (aperezg@mes.upv)
Guardiola Víllora, Arianna (aguardio@mes.upv)

Departamento Mecánica del Medio Continuo y Teoría de
Estructuras
Centro Escuela Técnica Superior de Arquitectura de
Valencia

<!-- p. 2 -->

1 Resumen de las ideas clave
En este documento se explica el método de Ritter o de los cortes para obtener los
axiles en las barras de las celosías planas estáticamente determinadas.

2 Introducción
Para determinar los esfuerzos en las barras de las celosías planas estáticamente
determinadas [1] existen diversos métodos: método de los nudos, método de
Maxwell-Cremona, el método de Ritter o de las secciones y el método matricial.
El Método de Ritter o de las secciones consiste en realizar una serie de cortes en la
celosía, y plantear las ecuaciones de equilibrio con objeto de determinar las
solicitaciones en las barras.
La principal ventaja de este método es que se permite calcular el axil en una barra
determinada sin tener que resolver toda la celosía, y que la fuerza obtenida es
directamente la solicitación de la barra, siendo más fácil para el alumno interpretar
el signo del axil.

3 Objetivos
El principal objetivo de este documento es mostrar al alumno el proceso de cálculo
de una celosía plana de nudos articulados isostáticamente determinada, del tipo
de las de la figura 1.
Así pues, una vez que el alumno se lea con detenimiento este documento, será
capaz de:

 Obtener las reacciones en los apoyos de la celosía
 Transformar la carga repartida sobre la celosía en carga puntual en los
nudos
 Seleccionar el punto por el que seccionar la celosía
 Determinar los axiles de las barras de las celosías.

cordones diagonales montantes

cordones
diagonales
montantes

cordones diagonales

Figura 1. Celosías planas trianguladas de nudos articulados

Aplicación del método de Ritter
2

<!-- p. 3 -->

4 Aplicación del método

4.1 Hipótesis adoptadas

El modelo del sistema estructural se analiza adoptando las siguientes hipótesis:
 Sólo se consideran cargas aplicadas en los nudos.
 Los nudos se suponen articulados (el momento flector de todas las barras que
concurren a un nudo es nulo).
 Las barras son rectas y están sometidas únicamente a esfuerzo axil.
 Las deformaciones y los desplazamientos son pequeños.

Si se cumplen todas ellas se pueden utilizar los métodos simplificados de obtención
de solicitaciones en celosías de nudos articulados. En tal caso, sólo hay una
solicitación incógnita por barra: el axil.

4.2 Etapas del proceso de cálculo

4.2.1 Obtención de las reacciones
A efectos de obtención de las reacciones en los apoyos de la celosía, ésta se
considera como una viga simple.
En la figura 2 se muestran dos celosías con carga uniformemente repartida, las vigas
simples equivalentes y las ecuaciones de equilibrio que permiten obtener el valor de
las reacciones en los apoyos.

4.2.2 Cargas sobre los nudos
Si la carga aplicada sobre el modelo de la celosía es una carga uniformemente
repartida, ésta se debe transformar en carga puntual para poder aplicar el método
de Ritter.
Para ello, se considera el ámbito de carga que corresponde a cada nudo (igual a
la semidistancia entre nudos a ambos lados del nudo considerado), tal y como
muestra la figura 3 sin olvidar que los nudos extremos tendrán una carga mitad.

4.2.3 Corte de la celosía y obtención de axiles
El punto de corte de la celosía se selecciona en función de los axiles que se
pretende calcular, seccionando aquellas barras de las que interesa obtener la
solicitación.
El corte no debe seccionar más de tres barras, ya que las ecuaciones de equilibrio
en estructuras planas son sólo tres: sumatorio de cargas verticales, sumatorio de
cargas horizontales y sumatorio de momentos flectores.
Si el objetivo es obtener el máximo axil en los cordones, montantes y diagonales, lo
usual es realizar dos cortes, uno en el centro del vano y otro cerca del extremo, tal y
como se aprecia en la figura 4, y comparar los valores obtenidos.

3

<!-- p. 4 -->

Una vez elegido el punto de corte de la celosía, se sustituye una de las partes
seccionadas por los axiles (incógnitas a calcular) en las barras. Es recomendable
suponer que los axiles son positivos (salientes de la barra) tal y como se aprecia en
la figura 4.
De este modo, si al calcular su valor, el signo que se obtiene es positivo, significa
que el sentido supuesto coincide con el sentido de la fuerza; esto es, la barra está
traccionada. Si el signo obtenido al calcular el valor del axil es negativo, significa
que es contrario al supuesto, es decir, que la fuerza es entrante y la barra está
comprimida.

q d q d

A B A
L L1 B L2 C
q d q d
A B A
L L 1 B L2 C
q d q d
A B A
B C
R 1 R 2 R 1 R 2

Fverticales  0;  qd  L  R1  R2  0 Fverticales  0;  qd  L  R1  R2  0 

M A  0;  q d   R2  L1  0 L (L1  L2 )2 M A  0;  qd  L   R2  L  0  2 2
q d  L q d  (L1  L2 )2R1  R2  R2  ; R1  q d  (L1  L2 )  R2
2 L1

Figura 2. Obtención de reacciones

ámbito de carga
F1,d F1,d F1,d F1,d F1,d F2,d F2,d q d

A B A B
L L

q d  L q d  L F1,d  ; F2,d  ;
6 12

Figura 3. Cargas en los nudos

Aplicación del método de Ritter
4

<!-- p. 5 -->

F1,d F1,d F1,d F1,d F1,d F1,d F1,d F1,d F1,d F1,d F2,d F2,d F2,d F2,d
H N HI I J K L M N H I J N JK K L M N

N HC N JE
A B A B
N AC C D E F G C D N DE E F G
R 1 R 2 R 1 R 2
L L

Figura 4. Cortes de la celosía

CORTE 1: Permite calcular el valor del axil de la barra HI (NHI) F1,d planteando la ecuación de sumatorio de momentos en C igual a F2,d
cero. Tal como se observa en la figura 5, se elige el punto C por N HI I ser punto de paso de las incógnitas NHC y NAC H
d
N HC  h
MC  0; R1  b  NHI  h  F2,d  b  0 N AC C  A
R1
b
Planteando el sumatorio de momentos en punto H, se obtiene el
axil de la barra AC (NAC) Figura 5. Corte del
primer recuadro

M H  0; N AC  0 

El axil de la diagonal HC (NHC) se calcula planteando el sumatorio de momentos
igual a cero en el nudo I. La distancia d se obtiene conocido el ángulo  indicado
en la figura, siendo

b d
  actg ; sen  ; d  h  sen
h h

CORTE 2: Permite calcular el valor del axil de la F1,d F1,d F1,d barra JK (NJK) planteando la ecuación de F2,d
sumatorio de momentos en E igual a cero. Tal N JK K como se observa en la figura 6, se elige el punto E H I J
por ser punto de paso de las incógnitas NDE y NJE. d h
N JE 
M E  0; A  C D N DE E
R1  3  b  N JK  h  F2,d  3  b  F1,d  2  b  F1,d  b  0
Planteando el sumatorio de momentos en J, se R1
obtiene el valor del axil de la barra DE (NDE) b b b

Figura 6. Corte del tercer recuadro

5

<!-- p. 6 -->

M J  0; R1  2  b  N DE  h  F2,d  2  b  F1,d  b  0 

Para obtener el axil en la barra JE (NJE) se plantea el sumatorio de momentos
flectores en el punto K, siendo la distancia d la misma que la del corte 1.

M K  0; R1  3  b  F2,d  3  b  F1,d  2  b  F1,d  b  N JK  d  NED  h  0 

Comparando los valores de los axiles calculados para los cordones, montantes y
diagonales en el corte 1 y el corte 2, se obtiene el máximo axil en cordones,
montantes y diagonales de toda la celosía, dado que ésta es simétrica en
geometría y cargas.
Si lo que se pretende es obtener el axil en todos los tramos de los cordones y cada
uno de los montantes y diagonales, se debería realizar un corte por las barras IJ, ID y
CD siguiendo el procedimiento expuesto.

CORTE 3: Para obtener el axil en el montante F1,d AH, se corta la celosía por esa esquina F2,d
(véase la figura 7) y se plantea el sumatorio
de fuerzas verticales igual a cero: H I
Fverticales  0; R1  N AH  0; N AH R1  N AH h
A
El valor que se obtiene para el axil de la N AC C
barra AH es negativo, es decir, signo
R 1 contrario al supuesto, lo que indica que la b
barra AH está comprimida.
Figura 7. Corte alrededor del apoyo izquierdo

CORTE 4: En cuanto al montante central, se F1,d F1,d F1,d
corta (véase la figura 8) alrededor del nudo
K, se suponen todos los axiles positivos tal y
J N JK K N KL L como se ha comentado al principio de este
epígrafe, y se plantea el sumatorio de fuerzas N KE
verticales igual a cero.
Fverticales  0; F1,d  N KE  0; N KE F1,d  D E F
Figura 8. Corte alrededor del nudo K

Siendo el valor del axil en el montante
negativo (signo menos) de igual valor que la
carga aplicada al nudo.

Aplicación del método de Ritter
6

<!-- p. 7 -->

4.2.4 Resultados obtenidos
Finalizados los cortes necesarios para obtener los axiles de las barras de la celosía
(todas las barras o sólo un número determinado de ellas), se genera un tabla con
los valores obtenidos, indicando, en función del signo del axil, si las barras están
comprimidas o traccionadas.

BARRA AXIL SIGNO
AC 0
AH -R1 compresión
KE -F1,d compresión
HC tracción

5 Conclusiones
A lo largo de este documento se ha expuesto el proceso de cálculo de axiles de las
barras de las celosías planas de nudos articulados con el método de Ritter, indicando
cuales son las hipótesis de partida para poder aplicar el método y cual es la mejor
estrategia a seguir en la elección del punto de corte y las ecuaciones de equilibrio a
plantear.
Este método se puede combinar con el método de los nudos para obtener los axiles
de todas las barras de la celosía. El método de los nudos plantea las ecuaciones de
equilibrio en cada uno de los nudos de la celosía para obtener los axiles.
El combinar ambos métodos exige saber interpretar los signos de las fuerzas obtenidas,
ya que en el método de los nudos se obtienen fuerzas en nudos y en el método de los
cortes o de Ritter fuerzas en las barras, (tienen signos contrarios).

6 Ejercicio propuesto
Con objeto de afianzar los conocimientos adquiridos, se propone al alumno obtener
los máximos axiles del cordón inferior (barra A-B-C-D-E-F-G) y los faldones de la celosía
(barras A-L-K-J y J-I-H-G) de la figura 9.

q d = 8,7 kN/m

J
K
I
L
H 1,5 m
33,75 kN A G
B C D E F

12 m

Figura 9. Ejercicio propuesto

7

<!-- p. 8 -->

7 Solución al ejercicio propuesto
Los faldones se encuentran comprimidos, siendo el tramo más solicitado, el tramo AL
con un axil de compresión de -179,35 kN.
El cordón inferior se encuentra traccionado, siendo los tramos más solicitado el AB y BC
con un axil de tracción de 140,25 kN.

8 Bibliografía

8.1 Libros

[1] A. Perez-Garcia, A. Martinez, E. Fenollosa, and A. Alonso, Introducción a las
estructuras de edificación. Valencia: Editorial UPV, 2007, p. 300.

8.2 Imágenes
Todos los dibujos de este documento han sido realizados por los autores.

Aplicación del método de Ritter
8
