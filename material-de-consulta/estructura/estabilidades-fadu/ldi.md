---
type: libro
title: "LDI"
author: ""
categoria: "ESTRUCTURA"
paginas: 5
extraccion: "texto"
fuente: "local:E:/MATERIAL DE CONSULTA/ESTRUCTURA/ESTABILIDADES FADU/LDI.pdf"
convertido: 2026-10-16
---

# LDI

> Texto extraído de `ESTRUCTURA\ESTABILIDADES FADU\LDI.pdf` (5 páginas, texto). El PDF original está en el disco E: (MATERIAL DE CONSULTA); `<!-- p. N -->` marca el inicio de cada página.

<!-- p. 1 -->

L´INEAS DE INFLUENCIA

1 Introducci´on

El concepto de la l´ınea de inﬂuencia es ´util para establecer las condiciones m´as desfavorables de
solicitaci´on en estructuras que presentan un comportamiento lineal y soportan cargas m´oviles, por
ejemplo puentes.
Una carga m´ovil produce distintos efectos como ser: reacciones, esfuerzos internos (Mf, Mt, N, Q),
desplazamientos, etc.
El efecto considerado en cada caso se designa ”Inc´ognita” X. En el caso lineal es suﬁciente determinar
el valor de i (x) de la misma para una carga unitaria 1 (x) actuando en la posici´on gen´erica deﬁnida
por la coordenada x.
El valor de la inc´ognita producida por una carga m´ovil P actuando en x es:

X(x) = P i(x) (1)

Donde:
X(x) : valor de la inc´ognita X producido por la carga P acutuando en x.
i(x) : coeﬁciente de inﬂuencia que depende de la coordenada x.
Se denomina l´ınea de inﬂuencia de una inc´ognita X al diagrama cuyas ordenadas η (x) en una cierta
escala repesentan al coeﬁciente de inﬂuencia deﬁnido en (1). La l´ınea de inﬂuencia es una representaci´on
gr´aﬁca de la ”inﬂuencia” variable i (x) seg´un la posici´on de la carga P.
En el curso de Est´atica se estudian las l´ıneas de inﬂuencia para reacciones y esfuerzos internos en
estructuras isost´aticas. Aplicando el pricipio de Trabajos Virtuales se puede demostrar que el diagrama
de desplazamientos verticales es igual a la l´ınea de inﬂuencia en una cierta escala.
En el presente cap´ıtulo se extiende el concepto de l´ıneas de inﬂuencia al caso de estructuras deformables, en general hiperest´aticas. Se comienza determinando las l´ıneas de inﬂuencia de desplazamientos
y giros, y se contin´ua con las l´ıneas de inﬂuencia de esfuerzos internos y reacciones en sistemas hiperest´aticos.

2 Teorema de Reciprocidad para s´olidos linealmente el´asticos

El Teorema de Reciprocidad, que es sumamente ´util desde el punto de vista conceptual y pr´actico,
surge como corolario del principio de Trabajos Virtuales (T.V.) aplicado a s´olidos linealmente el´asticos.
A continuaci´on se demuestra este teorema para el caso de una viga simple.
Sup´ongase un estado de cargas I, asociado a las cargas P1I , P2I , ..., Pn,I para el cual se determina el
estado de solicitaciones internas y reacciones, y otro estado II asociado a otras cargas P1II , P 2II , ..., PnII .

1

<!-- p. 2 -->

Aplicando la ecuaci´on de T.V. para el estado I y tomando como desplazamiento virtual el desplazamiento el´astico provocado por las fuerzas del estado II se obtiene:
n ·Z Z ¸ X
PiI δIIi − MIχIIdx + QIγIIdx = 0
(2) i=1 | {z } | {z }
Trabajo fuerzas externas Trabajo fuerzas Internas

N´otese que los desplazamientos δIIi son causados por las cargas P jII pero se reﬁeren al punto de
aplicaci´on de las cargas PiI . Rec´ıprocamente, se puede plantear:
m ·Z Z ¸ X
PjII δIj − MIIχIdx + QIIγIdx = 0 (3)
j=1

Suponiendo proporcionalidad entre tensi´on y deformaci´on:
¡ ¢ ¡ ¢
χI = 1 MI γI = 1 QI EI AcG
¡ ¢ ¡ ¢
χII = 1 MII γII = 1 QII EI AcG

Reemplazando estas expresiones en (2) y (3) y restando miembro a miembro se obtiene:

Xn Xm
I II Pn I Pm II Pi δIIi − Pj δIj = 0 ∴ i=1 Pi δIIi = j=1 Pj δIj (4)
i=1 j=1

El Teorema de Reciprocidad se sintetiza en la expresi´on (4) que expresa que el trabajo de las fuerzas
del estado I a trav´es de los desplazamientos de sus puntos de aplicaci´on en el estado II es igual al
trabajo de las fuerzas del estado II a trav´es de los desplazamientos en el estado I.

Es importante destacar que el teorema de reciprocidad es s´olo v´alido para sistemas lineales, mientras
que el principio de T.V. es aplicable a cualquier sistema de fuerzas en equilibrio.

Entre las aplicaciones del teorema de reciprocidad para sistemas linealmente el´asticos se destacan dos:
i) Probar la simetr´ıa de la matriz de Flexibilidad en el m´etodo de las Fuerzas, y de la matriz de
Rigidez en el m´etodo de los Desplazamientos.
ii) Trazado de l´ıneas de inﬂuencia de reacciones y solicitaciones en sistemas hiperest´aticos y de
deformaciones en sistemas isost´aticos e hiperest´aticos.

A manera de ejemplo, el valor num´erico del giro (en unidades consistentes) en el extremo de una viga
simple causado por una carga unitaria (1 Kg) actuando en el centro de la misma es por reciprocidad
igual al desplazamiento transversal del centro de la viga causada por un momento unitario (1 Kg×m)
actuando en el extremo.

θA = δc (5)

Como ejercicio, el lector puede calcular por separado θA y δc y comprobar la validez del teorema.

2

<!-- p. 3 -->

3 L´ıneas de Inﬂuencia como aplicaci´on del Teorema de Reciprocidad

En el curso de Est´atica se aplic´o el principio de T.V. para determinar las l´ıneas de inﬂuencia de sistemas
isost´aticos. En esta secci´on se desarrolla un planteo similar aplicando el teorema de reciprocidad para:
a) Probar que la el´astica causada por una fuerza unitaria es la l´ınea de inﬂuencia en una cierta
escala.
b) Determinar la escala y el signo.

3.1 L´ınea de inﬂuencia del desplazamiento de un punto en una viga

En la viga de la ﬁgura interesa determinar la inﬂuencia i (x) del descenso del punto central C.
Se considera como estado I al correspondiente a la carga P colocada en x. El estado II corresponde a
una carga unitaria en el punto para el cual interesa determinar la l´ınea de inﬂuencia del desplazamiento.
Sup´ongase conocida a trav´es de cualquier procedimiento de c´alculo la el´astica η (x) correspondiente al
estado II. Por el teorema de reciprocidad:⃗

1 · δc = Pη (x)

Por deﬁnici´on de coeﬁciente de inﬂuencia:

δc = P · i (x)

sustituyendo se tiene:

η (x) = i (x) (6)

3.2 Conclusi´on

La l´ınea de inﬂuencia del desplazamiento de un punto coincide con la el´astica asociada a una carga
unitaria aplicada en dicho punto.

3

<!-- p. 4 -->

4 L´ıneas de inﬂuencia en sistemas hiperest´aticos

4.1 L´ınea de inﬂuencia del momento ﬂector

A los efectos de ilustrar el desarrollo de la l´ınea de inﬂuencia del momento ﬂector en un sistema hiperest´atico se considera la viga continua de tres tramos indicada en la ﬁgura en la cual se determinar´a la
l´ınea de inﬂuencia del momento ﬂector en el centro del tramo de la izquierda. Para ello, se introduce
una articulaci´on en la secci´on en la que se desea la l´ınea de inﬂuencia del momento.

θ θ

θ θ
η

Para aplicar el teorema de reciprocidad se deﬁnen dos estados de carga, designados como I y II que
se indican en la ﬁgura. El estado I consiste en una carga unitaria aplicada en la secci´on x y el estado
II en dos momentos unitarios iguales y opuestos aplicados en la articulaci´on introducida.
Por reciprocidad se tiene:
¡ ¢
−P (x) · η (x) = −¯Mc · θIi + θId (7)

Por otro lado, el giro relativo nulo de las barras que concurren a la articulaci´on para la estructura
original se garantiza a trav´es de la siguiente ecuaci´on de compatibilidad de giros:
¡ ¢ ¡ ¢
Mc · θIIi + θIId + θIi + θId = 0 (8)

es decir:
¡ ¢
θIi + θId Mc = − ¡ ¢ (9)
θIIi + θIId

donde Mc es el momento ﬂector debido a la carga unitaria P (x) = 1 en la secci´on donde se introduce
la articulaci´on. Utilizando (7), la ecuaci´on (9) toma la siguiente forma:

(x) η (x) Mc = −P ¡ ¢ (10)
Mc¯ θIIi + θIId
y como P (x) = 1 y Mc¯ = 1 se obtiene ﬁnalmente:

η (x)
Mc = − ¡ ¢ (11)
θIIi + θIId

En conclusi´on, la l´ınea de inﬂuencia del momento ﬂector Mc es igual a la el´astica de la viga η (x)
producida por el momento Mc¯ = 1 aplicado a ambos lados de la articulaci´on introducida en la secci´on ¡ ¢
de inter´es. El t´ermino θIIi + θIId es un factor de escala.
Desde el punto de vista operativo s´olo es necesario determinar la el´astica η (x) del estado II, ya
que las deformaciones correspondientes al estado I se eliminan directamente al aplicar la ecuaci´on de
compatibilidad (8).

4

<!-- p. 5 -->

5 Otras formas de obtener las L´ıneas de Inﬂuencia

La propia deﬁnici´on del coeﬁciente de inﬂuencia proporciona una forma simple de calcularlo. Recordando la expresi´on (1):

X (x) = P i (x)

se observa que para una carga P unitaria el coeﬁciente de inﬂuencia es igual al valor de la inc´ognita.
Por lo tanto, la colocaci´on de una carga unitaria P=1 en una posici´on gen´erica x permite obtener el
valor de la inc´ognita por cualquier m´etodo ( trabajos virtuales, tres momentos, Castigliano, etc ).
El m´etodo de la el´astica ( reciprocidad ) tiene gran importancia conceptual ya que permite anticipar
sin ning´un c´alculo y en forma aproximada donde debe actuar una carga para producir la m´axima
inﬂuencia. Sin embargo, la utilizaci´on de programas computacionales de c´alculo permite automatizar
el c´alculo de las l´ıneas de inﬂuencia. En el caso de un reticulado para el que resulta necesario trazar una
l´ınea de inﬂuencia para cada barra, se puede utilizar un programa para determinar el esfuerzo en todas
las barras para varias posiciones de la carga m´ovil y ﬁnalmente seleccionar la m´axima solicitaci´on en
cada barra. En el caso de una viga continua, el programa puede calcular el momento ﬂector y el corte
en el centro de cada tramo y sobre los apoyos para varias posiciones de la carga, y luego determinar los
valores m´aximos de las solicitaciones en los puntos preﬁjados list´andolos con los resultados ﬁnales. El
c´alculo manual de las l´ıneas de inﬂuencia requiere un trazado para cada inc´ognita de inter´es mientras
que un programa de c´alculo puede proporcionar simult´aneamente todas las inc´ognitas preﬁjadas.

5
