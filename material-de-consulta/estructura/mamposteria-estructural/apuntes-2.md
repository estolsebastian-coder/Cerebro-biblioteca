---
type: libro
title: "apuntes_2"
author: "dpastori"
categoria: "ESTRUCTURA"
paginas: 52
extraccion: "texto"
fuente: "local:E:/MATERIAL DE CONSULTA/ESTRUCTURA/MAMPOSTERÍA ESTRUCTURAL/apuntes_2.pdf"
convertido: 2026-10-16
---

# apuntes_2

> Texto extraído de `ESTRUCTURA\MAMPOSTERÍA ESTRUCTURAL\apuntes_2.pdf` (52 páginas, texto). El PDF original está en el disco E: (MATERIAL DE CONSULTA); `<!-- p. N -->` marca el inicio de cada página.

<!-- p. 1 -->

MAMPOSTERÍA ESTRUCTURAL – DISEÑO I.E.T.

\3. DISEÑO

3.1. GENERALIDADES

Los principales aspectos que definen a la seguridad estructural son:

El diseño de la estructura.

El conocimiento de las características de los materiales a emplear (incluyendo las
deformaciones).

Una correcta estimación de las cargas a considerar.

Los coeficientes de seguridad elegidos.

Con el diseño estructural, el ingeniero debe asegurar que la estructura cumpla su función durante la
vida útil sin colapsar, sin deformaciones o fisuraciones inadmisibles e incorporando el aspecto
económico.

Tanto las características de los materiales como las cargas que actúan son consideradas con valores
tomados de las mejores aproximaciones. Una desafortunada combinación puede, en la práctica,
llevar a un colapso. Los procedimientos de cálculo deben conducir a que la probabilidad de ese
colapso sea muy pequeña.

Los coeficientes de seguridad se presentan en forma distinta en los métodos:

Tensiones admisibles: Trabajar con tensiones admisibles que resulten de dividir el límite
elástico entre un único factor de seguridad, es solamente posible para materiales 100% elásticos.

Incremento de cargas: Este es un método utilizado antiguamente cuando el diseño se basaba
en prácticamente en la experiencia, donde simplemente se conocía la carga que producía la falla
de un elemento y para prodecer al dimensionado simplemente se multiplicaban las cargas
existentes por algún factor, por ejemplo 2.

Estado límite: aquí los coeficientes de seguridad varían según los parámetros que se
consideran, por lo que se optimiza el resultado.

\- 44 -

<!-- p. 2 -->

MAMPOSTERÍA ESTRUCTURAL – DISEÑO I.E.T.

3.1.1. Diseño en estado límite

Se dice que una estructura alcanza un estado límite cuando se vuelve inapropiada para llevar a
cabo la función para la cual fue diseñada, bajo la acción de determinada solicitación.

Se producirá la falla si la solicitación existente (S ) alcanza la solicitación última resistente (S UR ) .
Se diseñará entonces para que no ocurra la falla, por ende, para que la solicitación existente nunca
alcance la solicitación última resistente.

Dado que no se puede conocer inequívocamente cual es el valor de la solicitación última resistente,
la misma se tomará como el valor característico reducido mediante un factor de seguridad γ m .

S UR
S u \< ( 3-1)
γ m

Se debe calcular entonces la máxima solicitación existente. Esta solicitación estará generada por
diferentes tipos de cargas, las cuales pueden o no actuar en conjunto, por lo que habrá que hacer
hipótesis para los diferentes “estados de carga” y habrá que tomar “coeficientes de seguridad para
las cargas aplicadas (fγ ) ” dado que es imposible conocerlas con total exactitud. La máxima
solicitación será entonces función de las cargas aplicadas y los coeficientes de seguridad tomados
en cada estado, como se expresa en la ecuación ( 3-2):

S u = f (γ f ⋅ S K ) ( 3-2)

S K es el valor característico de la solicitación generado cargas externas aplicadas. Como se dijo
antes, γ m es el coeficiente de seguridad parcial para de los materiales y mano de obra. Este
coeficiente tiene en cuenta la variabilidad de las propiedades de los materiales. fγ es un coeficiente
de seguridad parcial que tiene en cuenta no solo los problemas de estimación de las cargas
aplicadas, sino también errores de diseño y tolerancias constructivas. Alguna normas toman
distintos valores para estos coeficientes dependiendo de las consecuencias que puede tener el
colapso de la estructura. Por ejemplo, no es tan importante el colapso de un depósito como el de un
salón de clases.

En este punto, se puede analizar cual es la probabilidad de que ocurra la falla. Esto se muestra en la
ecuación ( 3-3):

P (S UR ≤ S u ) = p ( 3-3)

Imponiendo que p = 1 ⋅ 10 − 6 se podrían determinar γ m y fγ , pero trabajar con valores de cargas y
resistencias de materiales en forma estadística es casi imposible. Como consecuencia, γ m y fγ
surgen de la experiencia en la construcción y de ensayos de laboratorio.

\- 45 -

<!-- p. 3 -->

MAMPOSTERÍA ESTRUCTURAL – DISEÑO I.E.T.

3.1.1.1. Estados de carga

Las cargas características Fk que se pueden presentar en una estructura son:

Gk: carga característica permanente.
Qk: sobrecarga característica.
Wk: carga característica de viento (calculada según la norma UNIT 50-84).

Las posibles combinaciones de cargas que propone la bibliografía [1] son:

a) Cargas permanentes + Sobrecargas

En este caso hay dos posibilidades, mostradas en las ecuación ( 3-4):

(9.0 ó 4.1 ) ⋅ G K + (0 ó 6.1 ) ⋅ Q K ( 3-4)

Estos coeficientes pueden eventualmente variar con cada carga y dependerán de si la misma es
centrada o no.

b) Cargas permanentes + Viento

Las diferentes posibilidades se muestran en la ecuación ( 3-5):

(9.0 ó 4.1 ) ⋅ G K + (4.1 ⋅ WK ó .0 015 ⋅ G K ) ( 3-5)

Para las cargas de viento puede tomarse 1.2 en lugar de 1.4 para el caso de elementos que no
afecten la estabilidad global.

c) Cargas permanentes + Sobrecargas + Viento

En este caso se toman coeficientes porque es menor la probabilidad de todas las cargas actúen al
mismo tiempo en su máxima magnitud.

2.1 ⋅ G K + 2.1 ⋅ Q K + (2.1 ⋅ WK ó .0 015 ⋅ G K ) ( 3-6)

Luego de tener cada combinación de cargas, habrá que analizar cuales son las solicitaciones
generadas por las mismas y a partir de ellas realizar el diseño de la pieza en cuestión.

\- 46 -

<!-- p. 4 -->

MAMPOSTERÍA ESTRUCTURAL – DISEÑO I.E.T.

3.1.1.2. Coeficiente de seguridad parcial de materiales

γ m depende de varios factores:

Control de fabricación.
Control de las partidas del material.
Control de los procedimientos de construcción.

En bibliografía [1] se especifican dos niveles de control:

A. Control de los mampuestos.

A.1) Categoría especial.
A.2) Categoría normal.

B. Control de ejecución en obra.

B.1) Categoría especial.
B.2) Categoría normal.

En la Tabla 3-1 se muestran los valores Factor de seguridad parcial de los materiales
del coeficiente de seguridad parcial para Control de ejecución
los materiales que recomienda [1]. de la obra Especial Normal
Control de mampuestos
Para el caso de trabajar con Especial 3,5 4,4
mampostería confinada, los valores se
pueden reducir al 70% de los indicados Normal 4,0 5,0
en dicha tabla. Tabla 3-1 – Valores de fγ según bibliografía [1]

\- 47 -

<!-- p. 5 -->

MAMPOSTERÍA ESTRUCTURAL – DISEÑO I.E.T.

A modo de ejemplo analizamos las cargas a tomar en una determinada sección:

γ

Figura 3-1

0.015∗

Figura 3-2
En el segundo caso, las cargas G K son las cargas permanentes aplicadas sobre la sección a
considerar.

\- 48 -

<!-- p. 6 -->

MAMPOSTERÍA ESTRUCTURAL – DISEÑO DE ELEMENTOS COMPRIMIDOS I.E.T.

3.2. DISEÑO DE ELEMENTOS CON SOLICITACIÓN PREDOMINANTE DE COMPRESIÓN

3.2.1. Determinación de la Esbeltez de los muros

Se define la esbeltez geométrica de un muro según la ecuación ( 3-7):

h
λ g = c ⋅ ( 3-7)
t e

Donde:
h es la distancia libre entre apoyos horizontales de la pared (entrepisos,
borde superior de fundaciones, etc. h
te es el espesor efectivo de la pared sin considerar revoques (este
parámetro será analizado con profundidad más adelante). L
c es un coeficiente que depende de las condiciones de apoyo de la pared.

La Tabla 3-2 resume los valores de c recomendados por la bibliografía [1].

Valores de c en función de las condiciones de borde del muro

Condiciones
de
borde

h h
.2 65 − 3.1 ⋅ .1 75 −
Valores de c 2 2 1 1 L L
.0 65 ≤ c ≤ 2 .065 ≤ c ≤ 1

Tabla 3-2 – Valores de c según bibliografía [1].

Se entiende por apoyo a la restricción de los desplazamientos que es capaz de llevar la reacción a
las fuerzas horizontales actuantes y además el 2.5% de las cargas verticales. Esta última condición
es por la posibilidad de desplome de la pared, es solamente a efectos de estabilidad, el elemento de
soporte no necesita ser diseñado para soportar esta fuerza adicional.
t2
t1
Por ejemplo, supongamos que se tiene el muro con
t1 contrafuertes de la Figura 3-3 sometido a una carga de
viento uniforme. El muro de espesor 1t deberá resistir la
carga de viento y las transmitirá a los contrafuertes (de
espesor 1t en el ejemplo) y 2t deberá ser suficiente
como para que el contrafuerte resista las cargas
horizontales. Si no fuese así, ese contrafuerte no podría
ser considerado como apoyo vertical en la verificación
del muro.

Figura 3-3 – Muro con contrafuertes

\- 49 -

<!-- p. 7 -->

MAMPOSTERÍA ESTRUCTURAL – DISEÑO DE ELEMENTOS COMPRIMIDOS I.E.T.

Si te tiene un muro de planta baja apoyado en una fundación (por ejemplo un patín corrido), o un
muro entre dos losas realizadas in situ, es lógico suponer que en los extremos del muro hay cierto
grado de restricción al giro. Las alturas efectivas de los muros podrían calcularse en base a los
cálculos de Euler, pero en mampostería las restricciones al giro no son perfectas, por lo que no suele
usarse el término “empotramiento” sino el término “restricción mejorada”. La altura efectiva
tomada en muros por la norma BS 5628, para el caso de restricciones mejoradas es h ef = .0 75 ⋅ h
como se indica en la Figura 3-4.

Losa de Hormigón

Restringe el desplazamiento
horizontal y el giro en cierta medida.

hef = 0.75 h

Se puede considerar que no
hay giro en el apoyo inferior.

Figura 3-4 – Esquema de muro de PB.

Un esquema aproximado para un muro con entrepisos podría ser el de la Figura 3-5 puesto que el
entrepiso no puede restringir los giros. En este caso se habla de restricción simple, por lo que la
altura efectiva del muro es h ef = h . Tampoco en este caso se consideran apoyos verticales.

Restringe el desplazamiento
horizontal pero no el giro.

hef = h

Restringe el desplazamiento
horizontal pero no el giro.

Figura 3-5 – Muro con entrepisos.

\- 50 -

<!-- p. 8 -->

MAMPOSTERÍA ESTRUCTURAL – DISEÑO DE ELEMENTOS COMPRIMIDOS I.E.T.

3.2.2. Cálculo del espesor efectivo

La bibliografía [1] presenta la Tabla 3-3 para el cálculo del espesor efectivo.

Espesor efectivo " t e" de diferentes elementos de mampostería estructural
Tipo de Pared con contrafuertes
Pared simple Pared con cavidad Columna
elemento Simple Con cavidad
lc
t2 t
Esquema t tc t2
t1 tc t
t1 b
b ≤ 4 ⋅ t

Maximo valor de: Maximo valor de:
t o b
a) 2 ⋅ ( t 1 + t 2 ) . a) 2 ⋅ (t 1 + K ⋅ t 2 ) .Valor de te t 3 . t ⋅ K 3 . dependiendo de la b) t1 . b) t1 .
dirección en que flexa
c) t2 . c) K ⋅ t 2 .

Tabla 3-3 – Valores del espesor efectivo de diferentes elementos según bibliografía [1].

Los valores de K para el caso de paredes con contrafuertes se muestran en la Tabla 3-4.

C   . Valores de K para el cálculo Relación entre el espesor del contrafuerte y la pared  t
del espesor efectivo en  t 
paredes con contrafuertes 1 2 3

6 1 1,4 2
Relación de espaciado
 l  10 1 1,2 1,4
de contrafuertes  .  Cl  20 1 1 1

Tabla 3-4 – Valores de K para el cálculo de te según [1].

La relación de espaciado de contrafuertes se define como el cociente entre la longitud horizontal
entre ejes de contrafuertes contiguos (l) y el ancho del contrafuerte (lC).

\- 51 -

<!-- p. 9 -->

MAMPOSTERÍA ESTRUCTURAL – DISEÑO DE ELEMENTOS COMPRIMIDOS I.E.T.

3.2.3. Efectos a considerar en el cálculo de un muro a compresión

\1) Esfuerzos normales por cargas verticales.

Se deberá hallar la carga de compresión que transmite al muro la parte de la estructura que está por
encima de la sección que se desea verificar.

\2) Excentricidad de las cargas aplicadas por la forma en que se introducen las mismas.

Cuando se tiene una losa que descarga en un muro de borde (Figura 3-6) se toma como hipótesis
una descarga triangular, debido a que al poder deformarse, la losa cargará más el borde interior del
muro que el exterior. Esta introducción de cargas genera una excentricidad en la sección superior
t
cuyo valor es .
3

Cuando se tiene una losa con un apoyo intermedio generado por un muro interior (Figura 3-7), se
toman como si fuesen dos losas independientes, cada una apoyada en la mitad de muro, generando
una distribución triangular.

Figura 3-6 – Descarga de losa extrema. Figura 3-7 – Descarga de losa en muro intermedio.

t
En este caso se tiene una descarga P1 con una excentricidad hacia un lado y otra descarga P2 con
6
t
excentricidad hacia el otro lado, debiéndose entonces hallar la excentricidad de la resultante
6
R = P1 + P2 hacia la derecha (ver Figura 3-7) según la ecuación ( 3-8).

t ( P2 − P1 ) e 0 = ⋅ ( 3-8)
6 P1 + P2

Si estas cargas fuesen iguales la resultante sería centrada. Cuando la losa a izquierda y derecha tiene
la misma carga y las luces no difieren en más del 40% puede tomarse como aproximación válida la
descarga centrada.

\- 52 -

<!-- p. 10 -->

MAMPOSTERÍA ESTRUCTURAL – DISEÑO DE ELEMENTOS COMPRIMIDOS I.E.T.

En la Figura 3-8 se muestra la descarga de una losa extrema sobre un muro con cavidad y en la
Figura 3-9 se muestra el caso de la descarga en un muro intermedio.

Figura 3-8 – Descarga de losa extrema en muro con cavidad. Figura 3-9 - Descarga de losa en muro intermedio con cavidad.

\3) Excentricidad por no coincidencia del eje del muro superior con el muro que se está
verificando.
P
Supongamos que tenemos un muro que llega a la losa
inferior con una carga centrada. Si este el eje del muro
superior no coincide con el eje del muro inferior, este
último estará recibiendo una carga descentrada.

\- 53 -

<!-- p. 11 -->

MAMPOSTERÍA ESTRUCTURAL – DISEÑO DE ELEMENTOS COMPRIMIDOS I.E.T.

0
Con lo visto en los puntos 2) y 3)
se puede calcular la excentricidad e0en la sección superior del muro.

Para conocer la influencia de la
excentricidad de las cargas
externas en las diferentes
secciones del muro, se toma como
hipótesis que esa excentricidad
disminuye hasta llegar
completamente centrada a la base
del muro (ver Figura 3-10) h

Si se está verificando la sección
superior del muro, se debe trabajar
con una excentricidad por cargas
externas eCE = 0e , si se desea
verificar por ejemplo la sección
ubicada a 0. 4 ⋅ h por debajo del
borde superior del muro, se debe
trabajar con una excentricidad por
cargas externas eCE = 0 . 6 ⋅ e 0 . Figura 3-10 – Variación de la excentricidad generada por las cargas externas.

\4) Efectos de esbeltez.

Los efectos de esbeltez del muro se tienen en cuenta h/10
a través de una excentricidad por pandeo e P .
h/10
0.4 h
La hipótesis tomada para dicha excentricidad se toma
h/10
como se muestra en la Figura 3-11.

h/10
Si se desea por ejemplo verificar la sección superior
del muro esta excentricidad es nula, pero al verificar h/10 eC
en la sección ubicada 0. 4 ⋅ h por debajo del borde h 0.2 h
superior del muro toma un valor máximo e P = e C h/10
dado por la ecuación ( 3-9).
h/10

h/10 λg 2 t e e C = ⋅ t e − ( 3-9) 0.4 h
2400 70 h/10

Cabe resaltar que en esta última ecuación se utilizó el h/10
espesor efectivo del muro y la esbeltez geométrica.
Es la única excentricidad en la cual se utilizan dichos
parámetros. Figura 3-11 – Variación de la excentricidad por pandeo

Es importante tener en cuenta que esta excentricidad debe ser considerada en la dirección más
desfavorable.

\- 54 -

<!-- p. 12 -->

MAMPOSTERÍA ESTRUCTURAL – DISEÑO DE ELEMENTOS COMPRIMIDOS I.E.T.

\5) Defectos constructivos

ea
La existencia de defectos en la construcción del muro es
tenida en cuenta por una excentricidad accidental. Para
esta excentricidad se asume una variación lineal con un
máximo en el extremo superior del muro y nula en el
extremo inferior.
Esta variación es igual a la tomada como hipótesis de
cálculo para la excentricidad por cargas externas, por lo
que valen los mismos comentarios realizados h
anteriormente.
El valor máximo de esta excentricidad se calcula según la
ecuación ( 3-10).

t h
eDC = + ( 3-10)
50 500
Se debe recalcar que en esta ecuación se utiliza el espesor
real del muro a verificar y la altura real del muro. Figura 3-12 – Excentricidad por defectos constructivos.

\6) Efectos de cargas horizontales

Los efectos de las cargas horizontales son tenidos en cuenta a través de una excentricidad dada por
la relación Momento flector – Directa en la sección a verificar. No existe un criterio general pues en
casa caso se deberá ver el tipo de cargas horizontales actuantes así como las condiciones de borde
asumidas para el muro.

3.2.4. Método de diseño de muros comprimidos

La Figura 3-13 muestra la variación de las diferentes excentricidades a lo alto del muro.

Ecentricidad Ecentricidad Ecentricidad
por cargas por defectos por pandeo
externas constructivos
e0 ea

h/10

h/10
0.4 h
h/10

h/10

h/10 eC h 0.2 h
h/10

h/10

h/10
0.4 h
h/10

h/10

Figura 3-13 – Comparación de las diferentes excentricidades.

\- 55 -

<!-- p. 13 -->

MAMPOSTERÍA ESTRUCTURAL – DISEÑO DE ELEMENTOS COMPRIMIDOS I.E.T.

Estas excentricidades, junto con la excentricidad por cargas horizontales he permiten calcular la
excentricidad en cada sección del muro. Claro está resultaría engorroso, al menos sin la utilización
de computadoras verificar cada sección del muro, por lo que habrá que analizar las secciones más
comprometidas y verificar dichas secciones.

Nu En la Figura 3-14 se muestra el esquema de cálculo
seguido para el diseño en estado último para una t/2-e*
sección sometida a una carga de compresión
e* excéntrica, en la que no se admite la existencia de
tracciones, o sea, se considera que la sección no
soporta tensiones de tracción.

La máxima reacción que puede dar el muro en el
momento en que se produce la falla (estado último) es
la generada por una distribución de tensiones
t uniforme en la que en cada fibra se ha alcanzado la
tensión característica de compresión kf . La reacción
máxima por unidad de largo del muro está dada por la
ecuación ( 3-11):

\* ) ( 3-11) N UR = f K ⋅ 1 ⋅ (t − 2 ⋅ e
Figura 3-14 – Método de diseño en compresión.

La condición de diseño según la ecuación ( 3-1) es la indicada en la ecuación ( 3-12)

N UR
N u \< ( 3-12)
γm

Se obtiene entonces:

 e * 
f K ⋅ t ⋅ 1 ⋅  1 − 2 ⋅   t  ( 3-13) N u \<
γm

Dado que se trabaja por unidad de longitud, podemos decir que ⋅t 1 es el área media del pilar Am .
Se define el coeficiente β según la ecuación ( 3-14):

 e* 
β =  1 − 2 ⋅  ( 3-14)  t 

Se obtiene entonces:

f K ⋅ Am ⋅ β
N U \< (3-15)
γm

No se debe creer que N U es simplemente el mayor valor de las directas obtenidas a partir de los
diferentes estados de carga analizados en 3.1.1.1. , pues se debe considerar también la excentricidad
obtenida en cada estado, la cual está incluida en el término β .

\- 56 -

<!-- p. 14 -->

MAMPOSTERÍA ESTRUCTURAL – DISEÑO DE ELEMENTOS COMPRIMIDOS I.E.T.

3.2.4.1. Cálculos recomendados por I.E.T.

La bibliografía [1] propone realizar verificaciones en la sección superior del muro y en la sección
ubicada 0. 4 ⋅ h por debajo del borde superior, por lo que propone verificar con los valores de *e
dados en las Ecuaciones ( 3-16) y ( 3-17).

e * = e 0 + e a + e h ( he calculada en la sección superior) . ( 3-16)

e * = 0 . 6 ⋅ (e 0 + e a ) + e C + e h ( he calculada a 0. 4 ⋅ h del borde superior) ( 3-17)

Es importante aclarar que habiendo cargas horizontales, los diagramas de momentos pueden hacer
que haya una excentricidad máxima en un punto cualquiera, por lo que en dicho caso habría que
hacer una verificación en dicha sección.

Esta recomendación exige λ≥ 27 y t ≥ 11 cm .

3.2.4.2. Cálculos exigidos por la norma BS 5628

La norma BS 5628 [5] realiza el cálculo en compresión en forma análoga a la (3-15), pero
introduciendo un factor 1.1, esto se muestra en la ecuación (3-18).

\1. 1 ⋅ β⋅ f K ⋅ Am
N U \< (3-18)
γm

Los valores de β utilizados por la norma británica pueden extraerse de la gráfica mostrada en la
Figura 3-15 o de la Tabla 3-5 extraída de la bibliografía [3], cuyos valores fueron extraídos de la
gráfica antes mencionada.

Coeficiente β según Norma BS 5628
Esbeltez Exentricidad en el borde superior del muro
hef (e0)
t ef Hasta 0,05 t 0,1 t 0,2 t 0,3 t
0 1,00 0,88 0,66 0,44
6 1,00 0,88 0,66 0,44
8 1,00 0,88 0,66 0,44
10 0,97 0,88 0,66 0,44
12 0,93 0,87 0,66 0,44
14 0,89 0,83 0,66 0,44
16 0,83 0,77 0,64 0,44
18 0,77 0,7 0,57 0,44
20 0,70 0,64 0,51 0,37
22 0,62 0,56 0,43 0,3
24 0,53 0,47 0,34
26 0,45 0,38
27 0,40 0,33

Nota 1: No es necesario considerar efectos de
excentricidades hasta 0,05 t
Nota 2: Se permite interpolar linealmente entre
excentricidades y esbelteces.
Figura 3-15 – β según BS 5628 Tabla 3-5 – β según BS 5628

\- 57 -

<!-- p. 15 -->

MAMPOSTERÍA ESTRUCTURAL – DISEÑO DE ELEMENTOS COMPRIMIDOS I.E.T.

e
Según los cálculos utilizados por la norma BS 5628, para el caso = 0. 05 se obtiene β = 1 , pero
t
dado que aparece el factor 1.1 en la ecuación (3-18) se obtiene como condición de diseño lo
mostrado en la Euación (3-19).
\1. 1 ⋅ f K ⋅ Am
N U \< (3-19)
γm
Por otra parte si se realiza el cálculo según la “Recomendación para la Construcción en
e
Mampostería Estructural” realizada por el I.E.T., para = 0. 05 se obtiene β = 1 − 2 ⋅ 0. 05 = 0. 9 , por
t
lo que la condición de diseño es la indicada en la ecuación (3-20).

\0. 9 ⋅ f K ⋅ Am
N U \< (3-20)
γm
Se puede observar que el diseño según la Recomendación del I.E.T. ( [1] ) es más restrictiva, y por
tanto más segura, que la indicada en la norma BS 5628. Esto se contrarresta con la reducción de la
resistencia característica a la compresión que toma la norma BS 5628 para el caso de muros de un
' f Ksolo mampuesto de espesor. Para este caso considera f K = .
1.15

3.2.5. Diseño de columnas comprimidas

Se entiende por columna a aquel elemento cuya sección cumple que
b1 ≤ 4 ⋅ b 2 (siendo b1 > b 2 ), si esta condición no se cumple se considera b2
que es un muro.
En las columnas, sea la carga centrada o no, se tiene la posibilidad de que
pandee en cualquiera de sus direcciones principales, por lo que se deberá
b1verificar a compresión con el método descrito anteriormente, pero
considerando las excentricidades y esbelteces correspondientes a cada Figura 3-16 – Columna
dirección.

Ejemplo: y
Supongamos que se tiene la columna cuya sección se muestra en la
Figura 3-17 sometida a una carga de compresión de módulo P, con ex P
b yexcentricidades xe respecto al eje “y” y e y respecto al eje “x”. ey
x
Se debe verificar la columna considerando el pandeo en ambas
direcciones. Según la dirección y, con una carga que tiene una
excentricidad e y y un espesor t = b y para el cálculo de la esbeltez; y
b xsegún la dirección x, considerando una excentricidad xe y un
espesor t = b x para el cálculo de la esbeltez. Figura 3-17 – Ejemplo de verificación de
columnas comprimidas.
Se debe tener en cuenta además las condiciones de borde que
existan en cada dirección.
Para el caso que e y > e x , b y \< b x y las condiciones de borde de la columna sean iguales en las dos
direcciones, solamente será necesaria la verificación considerando el pandeo según el eje “y”
Si el área de la sección de la columna es inferior a 0. 2 m 2 se reduce la resistencia característica a
compresión como lo muestra la ecuación (3-21)
f K' = (0 .7 + 1. 5 ⋅ AM ) ⋅ f K (3-21)
Esto es en realidad un incremento de γm que tiene en cuenta que la heterogeneidad de la
mampostería es mas relevante en el caso que la sección sea muy pequeña (con que un solo
mampuesto sea defectuoso, puede ser crítico)

\- 58 -

<!-- p. 16 -->

MAMPOSTERÍA ESTRUCTURAL – DISEÑO DE ELEMENTOS COMPRIMIDOS I.E.T.

En la Figura 3-18 se muestra una viga
apoyada sobre una columna.

La viga evita que la sección superior de la
columna tenga desplazamientos en la
dirección “y”, por lo que en ese caso es
una buena aproximación utilizar para el
pandeo según “y” el esquema de un pilar
apoyado-apoyado ( hef = h ). En la
dirección “x” genera poca resistencia , por
lo que en ese caso sería mejor el esquema
de un pilar empotrado-libre ( hef = 2 ⋅ h ).

Figura 3-18 – Consideraciones sobre esbelteces en columnas

y
En la Figura 3-19 se muestra una columna con
cavidad. Si se estudia el muro considerando pandeo t1
según “y”, el espesor será el máximo valor entre 1t , x
2 t22t o ⋅ (t 1 + t 2 ) , pero al estudiar el muro
3
considerando pandeo según el eje “x” el espesor b
efectivo será b.
Figura 3-19 – Espesor efectivo de columna con cavidad.
En la Figura 3-20 se muestran distintos valores de alturas efectivas para columnas según el tipo de
restricciones ( bibliografía [3] ).

Figura 3-20 – Valores de altura efectiva indicados en bibliografía [3].

\- 59 -

<!-- p. 17 -->

MAMPOSTERÍA ESTRUCTURAL – DISEÑO DE ELEMENTOS COMPRIMIDOS I.E.T.

3.2.5.1. Columnas formadas por aberturas

Muchos muros contienen puertas, ventanas o algún otro tipo de aberturas, las cuales muchas veces
están cercanas unas de otras, de forma tal que la sección de muro que queda entre ellas se vuelve
muy angosta. En caso de que dicha sección cumpla los requisitos para ser considerada columna
( b \< 4 ⋅ t ) la altura efectiva de la columna será mayor que la del muro, pero menor que la de la
columna considerada asilada del resto.

h1

h
h2

Figura 3-21 – Columnas formadas por aberturas.
En el muro portante de la Figura 3-21 se forma una columna entre las aberturas indicadas. Para
verificar esta columna la norma BS 5628 distingue dos casos.

Cuando el muro tiene simplemente restringido el desplazamiento horizontal (por ejemplo por un
entrepiso) la altura efectiva de la columna se toma igual a la altura real del muro (distancia entre
apoyos horizontales), como se muestra en la ecuación (3-22):

hef = h (3-22)

Cuando las características del apoyo son tales que restringen los giros, por ejemplo cuando se tiene
una losa hecha en sitio la altura efectiva del muro se calcula según la ecuación (3-23):

hef = 0. 75 ⋅ h + 0 . 25 ⋅ h 2 (3-23)

donde h 2 es la máxima altura de las aberturas.

\- 60 -

<!-- p. 18 -->

MAMPOSTERÍA ESTRUCTURAL – DISEÑO DE ELEMENTOS COMPRIMIDOS I.E.T.

3.2.6. Muros con descargas concentradas

Cuando una losa descarga sobre un muro, si bien no lo hace en forma completamente uniforme, no
es de esperarse que hayan grandes variaciones en las tensiones introducidas en el muro a lo largo de
la línea de apoyo. Distinto es el caso de la descarga de una viga. En este caso el muro va a tener en
una sección relativamente pequeña una determinada carga que probablemente genere tensiones altas
en el muro.

En caso de vigas de hormigón de importante
rigidez, apoyando la viga directamente sobre el
muro, dado que las deflexiones de la viga son
pequeñas, se puede asumir una descarga lineal
(ver Figura 3-22).

Cuando se tienen vigas de acero de importante
altura, generalmente las cargas transmitidas son
grandes, por lo que resultaría difícil poder
realizar la descarga sin interponer un macizo de
hormigón (generalmente llamado “muerto de
hormigón”) que permita aumentar el área en la
cual se distribuye la carga, obteniendo así una
tensión menor. En este caso también se obtiene
una distribución uniforme de tensiones en la
introducción de cargas.

En el caso de vigas de acero de pequeña rigidez,
en general las cargas transmitidas son pequeñas,
por lo que no suelen usarse macizos de
hormigón. En este caso se asume una
distribución triangular de tensiones dado que ya
no resulta tan despreciable el giro del perfil en su Figura 3-22
apoyo.

Localmente se permite incrementar la resistencia última de la pared para verificar su resistencia a
los esfuerzos concentrados que se dan en la zona de una descarga de viga o pilar. Esto es debido que
las cargas concentradas generan deformaciones localizadas, la mampostería cercana al área de
descarga tendrá deformaciones menores, por lo que se crea un efecto de compresión triaxial que es
favorable.

\- 61 -

<!-- p. 19 -->

MAMPOSTERÍA ESTRUCTURAL – DISEÑO DE ELEMENTOS COMPRIMIDOS I.E.T.

La norma BS 5628 define distintos tipos de apoyos para los cuales da diferentes posibilidades de
incremento de la resistencia característica a compresión.

3.2.6.1. Apoyos Tipo 1

Figura 3-23 Figura 3-24

En las tres figuras anteriores se muestran los apoyos
denominados “Tipo 1” por la norma BS 5628, al igual
que la bibliografía [1].

En estos casos se permite incrementar la resistencia
característica a la compresión en un 25% para
verificar la descarga como se muestra en la ecuación
(3-24):

f K' = 1 . 25 ⋅ f K (3-24)

Figura 3-25

\- 62 -

<!-- p. 20 -->

MAMPOSTERÍA ESTRUCTURAL – DISEÑO DE ELEMENTOS COMPRIMIDOS I.E.T.

3.2.6.2. Apoyos Tipo 2

Figura 3-26 Figura 3-27

Para los apoyos indicados en la Figura 3-26 y Figura 3-27 la norma BS 5628 (al igual que la
Recomendación el I.E.T.) permiten incrementar la resistencia característica a compresión en un
50% para verificar la descarga como se muestra en la ecuación (3-25)

f K' = 1 . 5 ⋅ f K (3-25)

La Norma BS 5628 admite incrementar la resistencia característica a compresión en un 100% para
la verificación de la descarga en el caso de utilizar macizos de hormigón. La Recomendación del
I.E.T. no considera este tipo de apoyo.

Además de verificar la descarga, se debe verificar el muro por las cargas transmitidas. En la
Figura 3-28 se muestra la distribución de tensiones, que se asume a 45º. En las demás secciones a
verificar no se considera incremento alguno de la resistencia característica a compresión de la
mampostería.

Figura 3-28

\- 63 -

<!-- p. 21 -->

MAMPOSTERÍA ESTRUCTURAL – DISEÑO DE ELEMENTOS COMPRIMIDOS I.E.T.

En la Figura 3-29 se muestra un esquema extraído de bibliografía [6] en el que se aprecia una
descarga concentrada sobre un muro, la forma asumida para la dispersión de las cargas y los valores
con los que se deben comparar dichas cargas.

Figura 3-29 – Descarga concentrada y verificaciones según BS5628 y Recomendación del I.E.T.
La Figura 3-30 es extraída de la norma británica BS 5628 ( [6] ). En dicha figura se muestra un
esquema de las cargas generadas por una descarga concentrada cuando se utiliza un macizo de
hormigón como elemento dispersador. La norma indica que el diagrama de tensiones debajo de la
carga concentrada debe derivarse de un cálculo según la Teoría de la Elasticidad.
Cabe aclarar que la verificación indicada en la figura considera el “Apoyo tipo 3” indicado en la
norma antes mencionada (no previsto por la recomendación del I.E.T.) por lo que se incrementa la
resistencia característica a compresión en un 100%.

Figura 3-30 – Descarga concentrada en muro con introducción de elemento dispersador de cargas.

\- 64 -

<!-- p. 22 -->

MAMPOSTERÍA ESTRUCTURAL – DISEÑO DE ELEMENTOS COMPRIMIDOS I.E.T.

3.2.7. Descargas de muros portantes sobre pórticos de hormigón

El caso de estudio es el indicado en la Figura 3-31 donde un muro, cuyo peso propio por unidad de
área es “g”, recibe una carga uniformemente distribuida “p”.
p

g

Figura 3-31 – Muro de mampostería sobre pórtico de hormigón.

La consideración usual es asumir que el muro simplemente transmite la carga p a la viga, por lo que
la viga recibe una carga uniformemente distribuida de valor p+g tal como se indica en la Figura
3-32.
p+g

Figura 3-32 – Consideración usual.
Según dicho esquema el momento máximo de la viga se da en la sección media y su valor es el
indicado en la ecuación (3-26)

2 (p + g ) ⋅ t ⋅ l
M max = (3-26)
8

\- 65 -

<!-- p. 23 -->

MAMPOSTERÍA ESTRUCTURAL – DISEÑO DE ELEMENTOS COMPRIMIDOS I.E.T.

En realidad el memento flector generado en la viga es inferior al indicado en la ecuación (3-26)
debido al aporte (en la rigidez del conjunto) que da la mampostería.

Davier y Ahmed (de la universidad de Edinburgo) realizan un estudio por el método de los
elementos finitos y presentan un procedimiento de cálculo para determinar el máximo momento
flector generado en la viga. El desarrollo que sigue está basado en el trabajo presentado por los
autores antes mencionados, que se encuentra en la bibliografía [7].

3.2.7.1. Máxima tensión vertical en la pared

Básicamente el comportamiento del conjunto es como el de un arco atensorado, en el cual el arco se
forma en el muro y el tensor es la viga.

Las máximas concentraciones de tensiones en el muro se dan en su base en las zonas extremas de la
viga (apoyos del arco). En la mayoría de los casos, estas tensiones verticales de compresión son las
determinantes de la falla del conjunto.

La grado de concentración de las tensiones verticales en el muro es influenciado principalmente por
el parámetro de rigidez flexional definido por la ecuación (3-27):

H 3 ⋅ t ⋅ E M R = 4 (3-27)
I b ⋅ E b

Donde:
H es la altura del muro.
t es el espesor del muro.
EM es el módulo de elasticidad de la mampostería.
Ib es el momento de inercia de la viga.
Eb es el módulo de elasticidad del hormigón.

Un valor alto de R indica un importante efecto de arco y por el contrario un valor pequeño de R
indica que predomina la rigidez de la viga.

La tensión media de compresión en el muro se define como:

(p + g )
f med = (3-28) L ⋅ t

Se debe entonces hallar los valores máximos, pues estos son los que determinan en estado último
del muro.

\- 66 -

<!-- p. 24 -->

MAMPOSTERÍA ESTRUCTURAL – DISEÑO DE ELEMENTOS COMPRIMIDOS I.E.T.

Los resultado numéricos obtenidos a partir de análisis de elementos finitos muestran que hay una
relación lineal entre el parámetro R y la concentración de tensiones.

Figura 3-33 – Variación de la máxima concentración de tensiones verticales.

La máxima tensión vertical está relacionada con la tensión media como se indica en la ecuación
(3-29):

f máx = f med ⋅ (1 + β ⋅ R ) (3-29)

donde β es un coeficiente que depende de la relación entre la altura H y el largo L del muro y se
obtiene a partir de la Figura 3-34.

Sustituyendo la Ecuación (3-28) en la (3-29) se obtiene

(p + g ) fmáx = ⋅ (1 + β ⋅ R ) (3-30) L ⋅ t

\- 67 -

<!-- p. 25 -->

MAMPOSTERÍA ESTRUCTURAL – DISEÑO DE ELEMENTOS COMPRIMIDOS I.E.T.

Figura 3-34 – Relación entre β y H/L.

Para una viga muy poco rígida, correspondiente a un alto valor de R, la distribución de las tensiones
verticales es triangular con una alta concentración en los apoyos. Por otra parte, en muros apoyados
en vigas muy rígidas, con bajos valores de R, las tensiones se dispersan hacia el centro, dando como
resultado menor concentración de tensiones. La distribución de dichas tensiones en este caso se
aproxima mucho a un polinomio de tercer grado. En situaciones intermedias, con valores
intermedios de R, la distribución de tensiones se puede aproximar por una parábola simple.

Los tres casos anteriores pueden ser
relacionados con límites en el parámetro
R tal como se muestra en la
Figura 3-35.

Si R ≥ 7 Æ Distribución triangular de
tensiones.

Si 5 \< R \< 7 Æ Distribución parabólica.

Si R ≤ 5 Æ Distribución polinómica
cúbica.

Figura 3-35 – Distribución vertical de tensiones en la interfase muro-viga.

\- 68 -

<!-- p. 26 -->

MAMPOSTERÍA ESTRUCTURAL – DISEÑO DE ELEMENTOS COMPRIMIDOS I.E.T.

3.2.7.2. Directa en la viga

Puede asumirse que la directa en la viga de apoyo depende principalmente del parámetro de rigidez
axial definido por la Ecuación (3-31):

H ⋅ t ⋅ E M K = (3-31)
A ⋅ E b

Donde:
A es el área de la sección de la viga.

La máxima directa en una viga simplemente apoyada se da en la sección media de la misma y varía
linealmente con el parámetro K anteriormente definido. La relación lineal puede ser expresada de la
siguiente forma:

N = (p + g ) ⋅ (α − γ ⋅ K ) (3-32)

donde α y γ son coeficientes que al igual que β dependen de H/L y se obtienen a partir de la
Figura 3-36.

Figura 3-36 – Variación de α y γ con H/L.

\- 69 -

<!-- p. 27 -->

MAMPOSTERÍA ESTRUCTURAL – DISEÑO DE ELEMENTOS COMPRIMIDOS I.E.T.

Teniendo en cuenta que la directa depende entonces la dependencia de los parámetros α y γ con
H/L, se puede graficar la directa en la viga en función de K para distintos valores de H/L, resultando
así las rectas indicadas en la Figura 3-37.

Figura 3-37 – Directa en la viga en función de K y H/L.

\- 70 -

<!-- p. 28 -->

MAMPOSTERÍA ESTRUCTURAL – DISEÑO DE ELEMENTOS COMPRIMIDOS I.E.T.

3.2.7.3. Máxima tensión rasante entre viga y pared

Para que el muro y la viga trabajen en conjunto como se ha supuesto hasta ahora es necesario que la
resistencia al corte en la interfase muro-viga sea adecuada para transferir las tensiones de corte
generadas como resultado de la acción del arco. La Figura 3-38 muestra las tensiones que se
producen en un diferencial de elemento de interacción muro-viga.

Figura 3-38 – Interacción muro-viga en un elemento diferencial.

Analizando el equilibrio horizontal del elemento de viga se obtiene:

∂Nx
τ xy ⋅ t ⋅ dx = ⋅ dx (3-33) ∂x

Integrando ambos lados de la Ecuación (3-33) entre 0 y L/2 se obtiene:

L / 2
xy ⋅ t ⋅ dx = N L / 2 (3-34) τ∫
0

\- 71 -

<!-- p. 29 -->

MAMPOSTERÍA ESTRUCTURAL – DISEÑO DE ELEMENTOS COMPRIMIDOS I.E.T.

Para poder hallar la máxima tensión
rasante producida por el efecto de arco
se asumir un diagrama de tensiones
verticales y de corte. Se analizará para
comenzar el caso de diagrama lineal de
tensiones verticales para el cual se
asume como simplificación de aquí en
adelante diagrama lineal de tensiones
rasantes en la interfase muro-viga,
como se muestra en la Figura 3-39.

Figura 3-39 – Diagrama de tensiones verticales y rasantes para R ≥ 7 .

De los resultados del análisis de elementos finitos, los autores indican que la longitud en la cual
aparecen tensiones rasantes (Cl ) es entre dos y tres veces la longitud en las cuales hay tensiones
verticales(l V ) , recomendando asumir una relación l C = 2 ⋅ l V .

Por equilibrio vertical se obtiene

f máx ⋅ l V ⋅ t = (p + g ) (3-35)

Si se despeja lV de la ecuación anterior:
(p + g )
l V = (3-36)
f máx ⋅ t

Si se sustituye el valor de fmáx según la Ecuación (3-30) se obtiene:

L
lV = (3-37)
1 + β ⋅ R

por lo que lc resulta:
2 ⋅ L
lC = (3-38)
1 + β ⋅ R

Evaluando la integral de la Ecuación (3-34) se obtiene:

τ máx ⋅ l C ⋅ t = N L / 2 (3-39) 2

Sustituyendo N por lo indicado en la ecuación (3-32) y lc según la ecuación (3-38) se obtiene:

(p + g ) ⋅ (α − γ ⋅ K ) ⋅ (1 + β ⋅ R )
τ máx = (3-40) L ⋅ t

\- 72 -

<!-- p. 30 -->

MAMPOSTERÍA ESTRUCTURAL – DISEÑO DE ELEMENTOS COMPRIMIDOS I.E.T.

3.2.7.4. Momento flector en la viga

La viga está sometida a la acción de cargas verticales y tensiones rasantes en la interfase muro-viga.
Estas últimas son excéntricas respecto al eje de la viga, y por tanto causan una importante reducción
en los momentos flectores generados por las cargas verticales. El momento flector máximo en la
viga se genera muy cerca de los apoyos.

El momento flector debido a las cargas verticales es máximo en el centro de la luz y se calcula
según la ecuación (3-41):

r ⋅ l V M V = (p + g ) ⋅ (3-41)
2
por lo que se puede despejar l V :
2 ⋅ M V
l V = (3-42) (p + g ) ⋅ r

donde r es la distancia entre el borde de la
viga y el punto donde pasa la resultante de
la distribución de las tensiones verticales
(ver Figura 3-40) depende del tipo de
distribución asumida, la cual a su vez
depende del factor de rigidez flexional R.

Figura 3-40 – Interpretación del factor r.
Imponiendo equilibrio de fuerzas:

(p + g )
\= λ ⋅ f máx ⋅ l V ⋅ t (3-43)
2

donde λ es un coeficiente que depende de la forma del diagrama de tensiones.

Sustituyendo l V de la ecuación (3-42) en la ecuación (3-43) se obtiene:

2 ⋅ r (p + g )
M V = (3-44)
4 ⋅ f máx ⋅ λ ⋅ t

(p + g )pero en la ecuación (3-30) se tenía que f máx = ⋅ (1 + β ⋅ R ) con lo que el momento central L ⋅ t
generado por las tensiones verticales es:

(p + g ) ⋅ r ⋅ L
M V = (3-45) 4 ⋅ λ ⋅ (1 + β ⋅ R )

\- 73 -

<!-- p. 31 -->

MAMPOSTERÍA ESTRUCTURAL – DISEÑO DE ELEMENTOS COMPRIMIDOS I.E.T.

El momento flector producido por las tensiones rasantes a una distancia x del apoyo es el dado por
d
la ecuación (3-46) donde sale fuera de la integral pues el brazo de par de las tensiones rasantes es
2
constante.
d x
M H = − xy ⋅ t dx (3-46) ⋅ ∫ τ 2 0
Se obtiene entonces:
d
M H = − ⋅ N x (3-47)
2
Recordando que en la ecuación (3-32) se dedujo x
N(x)que N máx = (p + g ) ⋅ (α − γ ⋅ K ) y considerando que
la directa es generada por las tensiones rasantes, Nmáx
la directa tiene la misma variación, se puede
calcular la directa a una distancia x del apoyo: Figura 3-41 – Variación de la directa.

2 ⋅ N máx 2 ⋅ (p + g ) ⋅ (α − γ ⋅ K ) N x = ⋅ x = ⋅ x (3-48)
L L

obteniéndose un momento por las fuerzas horizontales:

d ⋅ (p + g ) ⋅ (α − γ ⋅ K )
MH = − ⋅ x (3-49)
L

El momento total será la suma de los momentos anteriormente calculados:

M Total = M V + M H (3-50)

Por lo que el momento en el punto central de la viga es:

(p + g ) ⋅ r ⋅ L d ⋅ (p + g ) ⋅ (α − γ ⋅ K )
M C = − (3-51) 4 ⋅ λ ⋅ (1 + β ⋅ R ) 2

lo que se puede expresar como:

(p + g ) ⋅ (L ⋅ r − 2 ⋅ d ⋅ (α − γ ⋅ K ) ⋅ (1 + β ⋅ R ))
M C = (3-52) 4 ⋅ λ ⋅ (1 + β ⋅ R )

Los autores indican que el momento máximo en la viga se da aproximadamente a una distancia del
apoyo igual a la distancia de contacto lV = L . Dado que el momento generado por las tensiones
1 + β ⋅ R
verticales es constante en el tramo centra (dado que en ese tramo el cortante es constante) el
momento máximo se calcula como:

(p + g ) ⋅ r ⋅ L 2 ⋅ (p + g ) ⋅ (α − γ ⋅ K ) L
M máx = − ⋅ (3-53) 4 ⋅ λ ⋅ (1 + β ⋅ R ) L 1 + β ⋅ R
lo que se puede expresar como:
(p + g ) ⋅ (L ⋅ r − 2 ⋅ d ⋅ (α − γ ⋅ K ))
M máx = (3-54) 4 ⋅ λ ⋅ (1 + β ⋅ R )

\- 74 -

<!-- p. 32 -->

MAMPOSTERÍA ESTRUCTURAL – DISEÑO DE ELEMENTOS COMPRIMIDOS I.E.T.

Los tres casos considerados de acuerdo a la magnitud del factor de rigidez flexional son los
siguientes:

 R ≤ 5 Æ Viga rígida.

r = 2.0 y λ = .0 25

(p + g ) M Máx = ⋅ [L − 10 ⋅ d ⋅ (α − γ ⋅ K )] (3-55) 5 ⋅ (1 + β ⋅ R )

(p + g ) M Central = ⋅ [L − 5.2 ⋅ d ⋅ (α − γ ⋅ K ) ⋅ (1 + β ⋅ R )] (3-56) 5 ⋅ (1 + β ⋅ R )

 5 \< R \< 7 Æ Viga flexible.

r = .0 25 y λ = .0 33

(p + g ) M Máx = ⋅ [L − .2 66 ⋅ d ⋅ (α − γ ⋅ K )] (3-57) .5 33 ⋅ (1 + β ⋅ R )

(p + g ) M Central = ⋅ [L − 5.2 ⋅ d ⋅ (α − γ ⋅ K ) ⋅ (1 + β ⋅ R )] (3-58) 5 ⋅ (1 + β ⋅ R )

 R ≥ 7 Æ Viga muy flexible.

r = .0 33 y λ = 5.0

(p + g ) M Máx = ⋅ [L − 6 ⋅ d ⋅ (α − γ ⋅ K )] (3-59) 6 ⋅ (1 + β ⋅ R )

(p + g ) M Central = ⋅ [L − 3 ⋅ d ⋅ (α − γ ⋅ K ) ⋅ (1 + β ⋅ R )] (3-60) 6 ⋅ (1 + β ⋅ R )

\- 75 -

<!-- p. 33 -->

MAMPOSTERÍA ESTRUCTURAL – DISEÑO DE ELEMENTOS SOMETIDOS A CORTE I.E.T.

3.3. VERIFICACIÓN DE CORTANTE

En cualquier estructura sometida por ejemplo a la acción del viento, se tienen muros sometidos a
solicitaciones de corte. Un ejemplo es el mostrado en la Figura 3-42.

Planta Corte AA
A A
V

1

2

Figura 3-42 – Ejemplo en el que se tiene un muro sometido a corte.

A la izquierda se observa una planta de una habitación donde el muro de la izquierda recibe una
carga horizontal. Ese muro, que deberá ser capas de resistir dichas cargas y luego transmitir parte de
esta a los muros 1 y 2 y parte a la losa superior e inferior. Dichos muros tendrán entonces, además
de la carga de compresión que puedan estar recibiendo, una carga horizontal en el propio plano que
contiene al muro transmitida por la losa superior (indicada como V en la Figura 3-42), y una
pequeña carga transmitida directamente por el muro (la cual puede en muchos casos ser
despreciable).

Será necesario hacer una verificación para ver si el muro es capaz de soportar dichas cargas
horizontales.
La verificación, basada en el método de diseño para estado último, es la mostrada en la Ecuación
(3-61):
VUR
VU \< (3-61)
γm
donde VU es la solicitación de corte en la sección horizontal considerada, y VUR es la resistencia
última al corte dada por el mínimo de los valores obtenidos por las Ecuaciones (3-62) y (3-63).
VUR = (τ0 K + 0. 6 ⋅ σ0 ) ⋅ Á M (3-62)

VUR = 1 . 5 ⋅τ0 K ⋅ AM (3-63)
τ0 K es la resistencia característica al corte, σ0 es la tensión media de compresión obtenida
considerando el 85% de las cargas permanentes, y AM es el área bruta de la sección considerada.

\- 76 -

<!-- p. 34 -->

MAMPOSTERÍA ESTRUCTURAL – DISEÑO DE ELEMENTOS PREDOMINANTEMENTE FLEXADOS I.E.T.

3.4. DISEÑO DE ELEMENTOS CON SOLICITACIÓN PREDOMINANTE DE FLEXIÓN

Cuando se tiene un muro sometido a presoflexión, dependiendo de la relación entre la carga y el
momento aplicado será si la sección está totalmente comprimida, parte comprimida y parte
traccionada, o se ha producido una fisura, tal como se muestra en la Figura 3-43.

Si la tensión de tracción excede la resistencia a tracción de la mampostería se produce la fisuración
de la sección. La fisuración puede también ocurrir cuando la mampostería no puede resistir
esfuerzos de tracción por ejemplo cuando existe alguna membrana de impermeabilización incapaz
de transmitir tensiones de tracción a través de la junta.

Figura 3-43 – Variación de las tensiones internas con la excentricidad de la carga aplicada.

El Caso 1 indicado en la Figura 3-43 corresponde por ejemplo a un muro intermedio o inferior de
una estructura portante. En el caso de los últimos pisos, especialmente en estructuras de techo
liviano donde suelen predominar succiones que hacen que la carga P sea pequeña, como se indica
en el Caso 2 de la misma figura, generándose así tensiones de tracción. Como la mampostería
resiste mejor la compresión que la tracción, las tensiones antes mencionadas suelen ser el factor
condicionante del diseño. En el Caso 3, la resistencia a tracción por flexión de la mampostería (si
existe) fue excedida, por lo que la condición dominante es la compresión.

\- 77 -

<!-- p. 35 -->

MAMPOSTERÍA ESTRUCTURAL – DISEÑO DE ELEMENTOS PREDOMINANTEMENTE FLEXADOS I.E.T.

3.4.1. Método de diseño admitiendo tracciones

En la práctica, es frecuente la existencia de paredes de mampostería simple (sin armadura) que
delimitan terrenos y que no forman parte de construcciones, así como también la existencia de
paredes de cerramiento exteriores en estructuras de hormigón armado. En estos casos la acción del
viento introduce solicitaciones de flexión. La resistencia a tracción por flexión será un factor
determinante del estado último de estos elementos.

Anteriormente se analizaron muros sometidos a una
solicitación preponderante de compresión. En esos
casos no se admite la existencia de tensiones de
tracción. En esos casos se utiliza el diagrama de
tensiones uniforme que se muestra en la Figura 3-44.

Figura 3-44 – Tensiones para compresión predominante

Cuando la flexión es preponderante, se admite
considerar la resistencia a tracción por flexión de la
mampostería suponiendo un diagrama lineal de
tensiones en el espesor de la sección a verificar.

En este caso se debe verificar que el valor máximo
de tracción no supere la resistencia a tracción por
flexión de la mampostería en la dirección que
corresponda ( f K x o f K y ) .
Figura 3-45 – Tensiones para flexión predominante

Las verificaciones a realizar dependen de si las fuerzas que actúan en el muro generan un momento
flector con vector paralelo o perpendicular a la junta (o ambos). La dirección del momento flector
actuante dependerá de las condiciones de borde que tenga el muro.

3.4.1.1. Paneles con vector momento paralelo a la junta

En la Figura 3-46 se muestra un panel con un único apoyo y
inferior. Este es el caso típico de muros divisorios entre
terrenos (sin contrafuertes).

En este caso el efecto del viento simplemente genera un
momento flector predominantecon vector paralelo a la junta.

Figura 3-46 – Panel con apoyo inferior.
Trabajando sobre una sección horizontal, la máxima tensión normal de tracción generada (por
unidad de longitud) es la indicada en la ecuación (3-64) donde “m y” es el momento por unidad de
largo producido por las fuerzas externas, “Z” es el módulo resistente de la sección, “γ ” es el peso
específico de la mampostería e “y” es la altura de muro por sobre la sección que se desea verificar.

my
σMáx Tracción = + γ ⋅ y (3-64)
Z

\- 78 -

<!-- p. 36 -->

MAMPOSTERÍA ESTRUCTURAL – DISEÑO DE ELEMENTOS PREDOMINANTEMENTE FLEXADOS I.E.T.

La condición de diseño será que dicha tensión no supere a f K y reducida por el coeficiente de
seguridad para los materiales γm . Imponiendo esta condición en la Ecuación (3-64) se obtiene la
ecuación de diseño mostrada en la (3-65).

 f K y 
m y ≤  − γ ⋅ y  ⋅ Z (3-65)
 γm 

Otro caso donde puede predominar esta solicitación es en
el mostrado en la Figura 3-47. Un ejemplo sería un panel
de cerramiento en una estructura de hormigón armado,
acuñado en su borde superior, pero con una considerable
distancia entre pilares, de forma tal de poder despreciar los
apoyos verticales.
Figura 3-47 – Panel con apoyo inferior y superior.

3.4.1.2. Paneles con vector momento perpendicular a la junta

En la Figura 3-48 se muestra un panel con apoyos laterales.
Este es el caso típico de muros con contrafuertes. En estos
casos es de esperar que también exista apoyo inferior pero la
relación largo alto hace despreciable este último.

En este caso el efecto del viento simplemente genera un
momento flector predominante con vector perpendicular a la
junta. Figura 3-48 – Panel con apoyos laterales.

La verificación es similar a la realizada en el punto 4.4.2 salvo que en lugar de considerar “m y” se
considera “m x”. Entonces, se debe cumplir:

 f K x 
(3-66) m x ≤  ⋅ Z
 γ m 

En este caso el peso propio del panel no se considera, ya que, como se puede observar, no está
contribuyendo en esa dirección.

\- 79 -

<!-- p. 37 -->

MAMPOSTERÍA ESTRUCTURAL – DISEÑO DE ELEMENTOS PREDOMINANTEMENTE FLEXADOS I.E.T.

3.4.1.3. Paneles con flexión en ambos sentidos

Para el caso de paneles apoyados en mas de dos lados la falla se puede dar en cualquiera de las dos
direcciones consideradas, por lo que se debe verificar tracción por flexión en ambos sentidos.

Dado que la mampostería es un material
anisótropo tanto en resistencia ( f K y ≠ f K x )
como en rigidez ( E y ≠ E x ) resulta un
análisis muy complejo. Se sigue en este
caso un análisis por líneas de fractura, lo
que resulta en un método simplificado pero
que sus resultados fueron corroborados por
ensayos de laboratorio según se indica en
bibliografía [4].

Figura 3-49 – Comparación entre el método de líneas de fractura y la
figuración real de la mampostería

Anteriormente se definió la relación ortogonal (µ )de la mampostería, que depende básicamente del
tipo de mampuesto y mortero utilizado.

f ky
µ = (3-67)
f kx

Para calcular los momentos generados en estos paneles, se utiliza un parámetro α que está tabulado
en la norma BS 5628 [3] y en la Recomendación del I.E.T. [1]. Los parámetros de entrada de estas
h
tablas son la relación ortogonal µ, la relación alto-largo del panel y las condiciones de borde
L
existentes (apoyos horizontales y verticales). Si la relación alto-largo es tan grande que cae fuera de
la tabla, los apoyos horizontales están tal alejados que el comportamiento se puede aproximar por el
h
de un panel con apoyos verticales según el apartado 0, pero si es muy pequeño, los apoyos
L
verticales están muy alejados, por lo que el comportamiento del panel es similar al de un panel con
apoyos horizontales según se analizó en 3.4.1.1.

\- 80 -

<!-- p. 38 -->

MAMPOSTERÍA ESTRUCTURAL – DISEÑO DE ELEMENTOS PREDOMINANTEMENTE FLEXADOS I.E.T.

Una vez determinado dicho parámetro, el momento flector debido a las cargas externas ( m x ) por
unidad de altura, cuyo vector es perpendicular a la junta , se calcula según la Ecuación (3-68),

m x = α ⋅ Wk ⋅ γ f ⋅ l 2 (3-68)

A su vez el momento flector debido a las cargas externas ( m y ) por unidad de longitud (de altura),
cuyo vector es paralelo a la junta , se calcula según la Ecuación (3-69),

m y = µ ⋅ α ⋅ Wk ⋅ γ f ⋅ l 2 (3-69)

Estos valores serán comparados con los momentos resistentes dados por las Ecuaciones (3-70) y
(3-71) respectivamente:

 f K x 
m rx =   ⋅ Z (3-70) γm  

 f K y 
m ry =   ⋅ Z (3-71) γm  

La norma BS 5628 [3] considera el efecto favorable del peso propio del muro a través de una
modificación de la relación ortogonal que se utiliza en las tablas que permiten determinar el
parámetro α. La relación ortogonal modificada se muestra en la Ecuación (3-72).

f ky + g
µ= (3-72)
f kx

con g dado por la Ecuación (3-73), en donde se utilizará γf = 0. 9 dado que el peso propio del muro
tiene un efecto favorable.
γf ⋅ G K
g = (3-73)
AM

\- 81 -

<!-- p. 39 -->

MAMPOSTERÍA ESTRUCTURAL – DISEÑO DE ELEMENTOS PREDOMINANTEMENTE FLEXADOS I.E.T.

3.4.1.4. Casos Particulares

3.4.1.4.1 Muros con contrafuertes

Si se desea, por ejemplo, hacer un muro que separe dos terrenos, dicho muro va a estar sometido a
importantes cargas de viento. Probablemente este muro deba tener un gran espesor para poder
diseñarlo si se lo considera como un panel con un único apoyo inferior, según se muestra en la
Figura 3-46, lo que conduciría a un diseño poco económico. La solución a este problema es colocar
contrafuertes.

En un muro con contrafuertes, cada segmento contenido
entre los mismos sigue el esquema de la Figura 3-50. Se
calculará este panel según lo indicado anteriormente en el
punto 3.4.1.3. , para lo cuál habrán dos parámetros en
juego, la separación entre apoyos verticales y el espesor
del muro (suponiendo fijas las características resistentes de Figura 3-50 – Panel con apoyo horizontal
la mampostería). inferior y apoyos verticales laterales.

Una vez realizado este cálculo, el muro transmitirá la carga a los contrafuertes. Si la unión entre los
contrafuertes y el panel se realiza solamente trabando los mampuestos, se deberá verificar que las
tensiones rasantes en la unión no superen en valor característico. En caso contrario se deberá
colocar conectores.

En las condiciones antes mencionadas el panel central transmite la carga a los contrafuertes, los que
deberán poder resistir las solicitaciones generadas. Para esto la bibliografía [3] indica considerar
que parte del muro colabora con el contrafuerte en resistir dicha flexión.

lc

t

dc

Figura 3-51 – Ancho colaborante para contrafuertes según bibliografía [3].

El ancho colaborante dc será el mínimo valor entre:

 La separación entre ejes de contrafuertes.
 El espesor del contrafuerte (lc) más doce veces el espesor defectivo del muro (en este caso t).
 La tercera parte de la altura efectiva del muro.

\- 82 -

<!-- p. 40 -->

MAMPOSTERÍA ESTRUCTURAL – DISEÑO DE ELEMENTOS PREDOMINANTEMENTE FLEXADOS I.E.T.

3.4.1.4.2 Muros dobles

En caso de haber muros dobles es importante tener en cuenta si existen o no conectores que hagan
que trabajen juntos.

En la Figura 3-52 se muestra un muro doble con cavidad que no tiene elementos conectores. En este
caso el muro exterior es el encargado de soportar toda la carga aplicada y por tanto el único que
flexa. En contrapartida, en la Figura 3-53 se muestra un muro doble en el que sí se utilizan
conectores. En este caso ambos muros flexan en conjunto, por lo que para determinar que
porcentaje de la carga está llevando cada muro se debe imponer que tengan igual flecha.

Figura 3-52 – Flecha en un muro doble sin conectores. Figura 3-53 – Flecha en un muro doble con conectores.

Se considera el muro de la Figura 3-53. Sea Wext la carga que lleva el muro exterior y Wint la que
lleva el muro interior. Si W es la carga total aplicada por unidad de superficie, es claro que:

Wint + Wext = W (3-74)

Si se analiza por ejemplo el caso de un muro solamente con apoyos inferior y superior y se trabaja
por unidad de longitud las flechas en el punto medio de ambos muros estarán dadas por las
Ecuaciones (3-75)

5 Wint ⋅ h 3 5 Wext ⋅ h 3
δ int = ⋅ y δ ext = ⋅ (3-75)
384 E int ⋅ I int 384 E ext ⋅ I ext

Considerando que E int = E ext , al imponer que las flechas sean iguales se llega a la Ecuación:

Wint Wext
\= (3-76)
I int I ext

Esta ecuación, junto con la (3-74) forman un sistema de dos ecuaciones con dos incógnitas que
permiten determinar Wint y Wext y de esta forma obtener la carga W que produce la falla de uno de
esos muros.

W ⋅ I int W ⋅ I ext
Wint = y Wext = (3-77)
I int + I ext I int + I ext

\- 83 -

<!-- p. 41 -->

MAMPOSTERÍA ESTRUCTURAL – DISEÑO DE ELEMENTOS PREDOMINANTEMENTE FLEXADOS I.E.T.

3.4.1.5. Limitaciones de esbelteces para paneles sin compresión

En las siguientes figuras se muestran limitaciones a la esbeltez impuestas para muros con distintas
condiciones de borde por la norma Británica.

Para el caso de muros don dos apoyos solamente:

Figura 3-54 – Muro con dos apoyos

Para el caso de muros con tres apoyos:

Figura 3-55 – Muro con tres apoyos – 2 o más continuos. Figura 3-56 – Muro con tres apoyos – Resto de los casos.

Para muros con cuatro apoyos:

Figura 3-58 – Muros con cuatro apoyos – Resto de los casos.Figura 3-57 – Muro con cuatro apoyos – 3 o más continuos.

\- 84 -

<!-- p. 42 -->

MAMPOSTERÍA ESTRUCTURAL – DISEÑO DE ELEMENTOS PREDOMINANTEMENTE FLEXADOS I.E.T.

3.4.2. Método de diseño sin admitir tracciones

En secciones donde no puede desarrollarse resistencia a Momento
tracción por flexión, el momento resistente a las cargas aplicado M
laterales está provisto solamente por el momento
estabilizante producido por el peso propio del elemento Mínima carga
aplicadaconsiderado.
(centrada) P
Lo anterior se muestra en la Figura 3-67. Bajo la acción del Sección que no
momento aplicado M, la sección tiende a girar en torno a resiste tracción
una recta (llamada “borde de cuchillo”). La tendencia al giro t/2
es resistida por la acción de la carga centrada generada por
el peso de la porción de muro ubicado por encima de la
sección en estudio. La condición de no-vuelco está dada por t
la Ecuación (3-78) en la que deberán incluirse los factores de
seguridad
t
M ≤ P ⋅ (3-78)
2 Figura 3-59 – Diseño con sección fisurada.

NuLa hipótesis de “borde de cuchillo” no es válida en
mampostería, pues las tensiones de compresión en el borde Mext
serían tan altas que generarían una falla local. El verdadero
ancho del área de contacto es difícil de hallar, por lo que W
para simplificar el diseño se asume un diagrama de fk / γm
tensiones uniforme. En la norma BS 5628 se considera
dicho diagrama, donde en la falla, el valor de la tensión es
la resistencia característica a compresión de la
mampostería ( f K ) dividida por el coeficiente de seguridad
parcial de los materiales ( γ m ). La norma británica t
incrementa f K en un 10% debido a la simplificación
utilizada, esto no será hecho en este texto.
Figura 3-60 – Esquema de cálculo.

En la Figura 3-60 Nu es la mínima carga vertical existente en la sección, Mext es el momento
generado por las cargas externas en dicha sección y “w” es el ancho de la sección en la que se
asume el diagrama de tensiones uniforme. El valor de “w” será tal que se equilibren la carga Nu.

f K w ⋅ = N U (3-79)
γ m

Despejando obtenemos:
γ m ⋅ N U
w = (3-80)
f K

El momento estabilizante generado por la carga Un es:

 t w 
M estabilizante = N U ⋅  −  (3-81)
 2 2 

\- 85 -

<!-- p. 43 -->

MAMPOSTERÍA ESTRUCTURAL – DISEÑO DE ELEMENTOS PREDOMINANTEMENTE FLEXADOS I.E.T.

Sustituyendo la Ecuación (3-80) en la (3-81) e imponiendo que el momento estabilizante sea mayor
que el momento externo, se obtiene la condición de diseño:

N U  γ m ⋅ N U 
M ext ≤ ⋅  t −  (3-82) 2  f K 

En la carga Nu ya se incluyen los coeficientes de seguridad fγ , pero se debe tener en cuenta que al
aumentar Nu aumenta el momento estabilizante.

Hector Gallegos en la bibliografía [4] muestra esquemas de ensayos de flexo-compresión con los
que obtiene el diagrama de interacción indicado en la Figura 3-61, en la que Po es la carga axial de
rotura y Mk es el momento de rotura cuando la carga axial cae en el borde del núcleo central de la
sección.

Figura 3-61 – Diagramas de interacción para flexo-compresión.

\- 86 -

<!-- p. 44 -->

MAMPOSTERÍA ESTRUCTURAL – DISEÑO DE ELEMENTOS PREDOMINANTEMENTE FLEXADOS I.E.T.

3.4.3. Métodos de diseños basados en el colapso del muro

3.4.3.1. Método del arco vertical

3.4.3.1.1 Muros sin apoyos verticales

Levantamiento
Justo antes de colapsar, un muro con carga
lateral tiende a levantar la estructura que está
por encima de ella, tal como se muestra en la
Figura 3-62.

Un análisis aproximado respecto al colapso de
esta estructura se basa en las siguientes
Cargahipótesis:
lateral
 Se desprecian las deformaciones elásticas
(particularmente la de los apoyos del muro).
 La falla ocurre cuando se forma una fisura
horizontal en el centro y bordes superior e
inferior del muro, generando así una rotación.

Figura 3-62 – Esquema de colapso por el Método del Arco Vertical.
En la Figura 3-63 se muestra el esquema de cálculo utilizado para este método. Una primera
observación es que resulta necesario para el equilibrio que el muro tenga una carga de compresión.
σ σ ⋅ t ⋅ L σ ⋅ t ⋅ L
q ⋅ h ⋅ L
q ⋅ h ⋅ L 2
2
h/4

h/2
q ⋅ h ⋅ L
2
q

h

σ ⋅ t ⋅ L

a
t-a

q ⋅ h ⋅ L
2

t
σ ⋅ t ⋅ L

Figura 3-63 – Esquema de cálculo para el método del arco vertical en un muro sin apoyos vertical.

\- 87 -

<!-- p. 45 -->

MAMPOSTERÍA ESTRUCTURAL – DISEÑO DE ELEMENTOS PREDOMINANTEMENTE FLEXADOS I.E.T.

Planteando equilibrio de momentos a la mitad superior del muro se obtiene:

q ⋅ h ⋅ L h σ ⋅ t ⋅ L ⋅ (t − a ) = ⋅ (3-83)
2 4

Despejando q se obtiene la Ecuación (3-84):

t ⋅ (t − a ) q = 8 ⋅ σ ⋅ 2 (3-84) h

h
La norma BS permite despreciar “a” ( a ≈)0 cuando ≤ 25 , dado que en muros muy esbeltos el
t
valor de “a” en el colapso no es despreciable frente a “t”. Si se toma a = 0 la carga máxima de
viento que puede soportar el muro es la indicada en la Ecuación (3-85):

t 2 1
q u 0 = 8 ⋅ σ ⋅ 2 (3-85) h

donde σ es la tensión de compresión del aplicada sobre el muro, t es el espesor del muro y h es la
luz libre entre apoyos horizontales. Si el muro es doble y solo uno de ellos está soportando carga
vertical, t es el espesor del muro que soporta la carga.

3.4.3.1.2 Muro con apoyos verticales

En los casos en los que además de apoyos horizontales existen apoyos verticales, parte de la carga
lateral es llevada por estos últimos. En la Figura 3-64 se muestra el esquema de colapso para el caso
de un muro que tiene un solo apoyo vertical y el la Figura 3-65 el caso de un muro con dos apoyos
verticales.

Dos apoyos verticales Un apoyo vertical

45°
45°

Figura 3-64 – Esquema de colapso simplificado Figura 3-65 – Esquema de colapso simplificado para un muro con dos
para muros con un apoyo vertical. apoyos verticales.

1 El subíndice 0 indica que no hay apoyos verticales.
\- 88 -

<!-- p. 46 -->

MAMPOSTERÍA ESTRUCTURAL – DISEÑO DE ELEMENTOS PREDOMINANTEMENTE FLEXADOS I.E.T.

Para analizar la carga última en el caso de un solo apoyo vertical se estudiará la carga máxima en
analizando el equilibrio de la mitad superior del muro, en forma análoga a lo realizado en la Figura
3-63. Para realizar el cálculo de la carga generada por el viento sobre la parte suprior del muro, se
considera la diferencia indicada en la Figura 3-66.

L
h/2 1 2

45°

h = -

Figura 3-66 – Cálculo de la carga lateral sobre el muro.

h h
La carga resultante en el caso 1 es q ⋅ ⋅ L y está aplicada a una distancia desde el borde
2 4
1 h  2 q ⋅ h 2 2 h hsuperior. En el caso 2 la resultante es q ⋅ ⋅  = y está aplicada a una distancia ⋅ = .
2  2  8 3 2 3

σ σ ⋅ t ⋅ L σ ⋅ t ⋅ L

q ⋅ h ⋅ L q ⋅ h 2
−
2 8
q ⋅ h ⋅ L
2
h/4
h/3
q ⋅ h ⋅ L
h/2 2
q ⋅ h 2
8
q

h

σ ⋅ t ⋅ L

a
t-a

q ⋅ h ⋅ L
2

t
σ ⋅ t ⋅ L

Figura 3-67 – Esquema de cálculo para el método del arco vertical en un muro con un solo apoyo vertical.

\- 89 -

<!-- p. 47 -->

MAMPOSTERÍA ESTRUCTURAL – DISEÑO DE ELEMENTOS PREDOMINANTEMENTE FLEXADOS I.E.T.

Planteando equilibrio de momentos se obtiene:

q ⋅ h ⋅ L h q ⋅ h 2 h σ ⋅ t ⋅ L ⋅ (t − a ) = ⋅ − ⋅ (3-86)
2 4 8 3

Agrupando:
q ⋅ h 2  1 h  σ ⋅ t ⋅ L/ ⋅ (t − a ) = ⋅ L/ ⋅  1 − ⋅  (3-87)
8  3 L 

Definiendo un parámetro α como la relación largo-alto del muro:

L
α = (3-88)
h
Tomando nuevamente a = 0 la carga última para el caso de un muro con un solo soporte vertical
está dado por la Ecuación (3-89):
t 2
8 ⋅ σ ⋅
h 2 q u 0 q u 1 = = (3-89)
 1   1   1 −   1 − 
 3 ⋅ α   3 ⋅ α 

Para el caso de un muro con dos apoyos verticales el razonamiento es análogo, solo que hay que
q ⋅ h ⋅ L h
restar dos triángulos, por lo que se obtiene en total una carga aplicada a una distancia
2 4
q ⋅ h 2 h
del borde superior y otra (opuesta) de aplicada a una distancia .
4 3

Planteando equilibrio de momentos se obtiene:

q ⋅ h ⋅ L h q ⋅ h 2 h σ ⋅ t ⋅ L ⋅ (t − a ) = ⋅ − ⋅ (3-90)
2 4 4 3

Repitiendo el razonamiento anterior y tomando a = 0 la carga última para el caso de un muro dos
apoyos verticales está dado por la Ecuación (3-91):

q u 0
q u 2 =
 2  (3-91)  1 − 
 3 ⋅ α 

\- 90 -

<!-- p. 48 -->

MAMPOSTERÍA ESTRUCTURAL – DISEÑO DE ELEMENTOS PREDOMINANTEMENTE FLEXADOS I.E.T.

 L En la Figura 3-68 se muestra como varía la carga última con la relación largo-alto α =   . Puede
 h 
observarse que para valores superiores a α = 2 casi no hay diferencia entre la carga última. Esto se
explica si concuerda con la hipótesis generalmente utilizada de despreciar los apoyos verticales
cuando están muy separados.

Carga última horizontal en función de la relación Largo-Alto
qu / qu0

20
Sin soportes verticales Un soporte Vertical Dos Soportes verticales

15

10

5

0
0 0,2 0,4 0,6 0,8 1 1,2 1,4 1,6 1,8 2 2,2 2,4 2,6 2,8 3
Relación Largo-Alto

Figura 3-68 – Variación de la carga última con la relación Largo-Alto para diferentes condiciones de borde.

La gráfica anterior aparece indicada en bibliografía [2] y respaldada por algunos ensayos de muros
a flexión.

Según los razonamientos antes explicados,
la carga de colapso de un muro sometido a
esfuerzos laterales y a compresiones es
independiente del tipo de material que se
utilice. Esto se debe a que en dichos
razonamientos se supuso que el muro gira
respecto a una recta, por la cual pasa una
carga igual a la integral de σ en toda la
sección del muro. Es lógico pensar que en
estas condiciones va a producirse un efecto
de aplastamiento localizado tal como se
esquematiza en la Figura 3-69.
Aquí es donde entra en juego el material
utilizado, pues el grado de aplastamiento
obtenido dependerá de las características
resistentes de la mampostería con la que se
construyó el muro. Figura 3-69 – Aplastamiento

\- 91 -

<!-- p. 49 -->

MAMPOSTERÍA ESTRUCTURAL – DISEÑO DE ELEMENTOS PREDOMINANTEMENTE FLEXADOS I.E.T.

En bibliografía [2] se muestra la gráfica indicada en la Figura 3-70 derivada de un análisis analítico
en el cual se tiene en cuenta la deformación del muro. Cada curva indicada en dicha gráfica
representa un tipo de mampostería distinta, la cual está caracterizada por su resistencia a la
compresión.

Figura 3-70 – Máxima presión lateral vs. Tensión de compresión para distintos valores de fk según bibliografía [2]

Como puede observarse en la Figura 3-70, la máxima presión lateral que puede soportar el muro se
obtiene cuando la tensión de compresión es aproximadamente la mitad de la resistencia a
compresión de la mampostería utilizada.

Otra observación importante que puede realizarse a partir de la gráfica indicada en la Figura 3-70 es
que todas las curvas comparten en su tramo inicial una zona recta, y que además para cada tipo de
mampostería, la zona recta es alcanzada hasta aproximadamente la cuarta parte de la resistencia a
compresión fk (por ejemplo para fk = 6.9Mpa la zona recta llega casi hasta 2Mpa). Esto es
importante pues el método del arco vertical es utilizado para muros que están soportando cargas
verticales y el propio método de diseño a compresión del muro, considerando los altos coeficientes
de seguridad utilizados para los materiales, hace que prácticamente no se supere esa zona, por lo
que la aproximación lineal que puede hacerse al inicio, termina siendo válida en el rango de cargas
de compresión que puede admitirse en el diseño.

\- 92 -

<!-- p. 50 -->

MAMPOSTERÍA ESTRUCTURAL – DISEÑO DE ELEMENTOS PREDOMINANTEMENTE FLEXADOS I.E.T.

3.4.3.2. Método del arco horizontal

Para el caso de muros con mínima carga axial pero construidos entre soportes rígidos, existe un
método de diseño basado en la hipótesis de que bajo cargas laterales, se forma un arco horizontal
que transmite las cargas por compresión, tal como se muestra en la Figura 3-71.

Elemento capaz de soportar t t
fuerzas laterales 10 T 10
T
q ⋅ L
q⋅ L 2
2
L/4

L/2
q ⋅ L
2
q

L

T

t t
10 10

a

q⋅ L
2

T
t t
10

Figura 3-71 – Esquema de cálculo para el método del arco horizontal.
Este método asume que hay un aplastamiento el los bordes laterales y en el centro del muro, cuyo
t f Kespesor es y en el que se genera una tensión de compresión uniforme de valor σ = 5.1 ⋅ (se
10 γ m
considera aquí ya el factor de seguridad parcial de los materiales γ m ) pues se plantea una condición
de diseño en lugar de una de colapso). La resultante de compresión generada en el arco está dada
por la Ecuación (3-92):
3 f K ⋅ t T = ⋅ (3-92)
20 γ m

Resulta crítico en este método tener apoyos laterales que sean capaces de soportar la directa fuerza
T sin tener deformaciones excesivas. Si esto no ocurriese el método queda completamente
invalidado.

Para que haya equilibrio de momentos en el sector de muro aislado en la Figura 3-71 se debe
cumplir:
 t t  L L
T ⋅  t − a − −  = q ⋅ ⋅ (3-93)
 20 20  2 4

\- 93 -

<!-- p. 51 -->

MAMPOSTERÍA ESTRUCTURAL – DISEÑO DE ELEMENTOS PREDOMINANTEMENTE FLEXADOS I.E.T.

Considerando a ≈ 0 se tiene:
9 ⋅ t L2
T ⋅ = q ⋅ (3-94)
10 8

Si se sustituye en la Ecuación (3-94) el valor de T indicado en la Ecuación (3-92) se obtiene:

27 f K ⋅ t 2 L2 ⋅ = q ⋅ (3-95)
200 γ m 8

Si se despeja q en la Ecuación (3-95) se obtiene la carga lateral máxima admisible en el diseño:

108 f K t  2 q = ⋅ ⋅  (3-96)
100 γ m  L 

108
La norma BS ignora el coeficiente por lo que establece la carga de diseño según la Ecuación
100
(3-97):
f K t  2 q = ⋅  (3-97)
γ m  L 
L
La restricción para poder tomar a = 0 es, análogamente al método del arco vertical, ≤ 25 .
t

En la Figura 3-72 se muestra un ejemplo de
muro en el cual se puede utilizar el método del
arco horizontal para verificar cuando el mismo
se encuentra sometido a cargas laterales
(extraído de bibliografía [3])

Figura 3-72

Otro ejemplo extraído de bibliografía [3] es el muro continuo indicado en la Figura 3-73.

Figura 3-73

\- 94 -

<!-- p. 52 -->

MAMPOSTERÍA ESTRUCTURAL – BIBLIOGRAFÍA I.E.T.

\4. BIBLIOGRAFÍA

[1] - “Recomendaciones para la construcción en Mampostería Estructural en Uruguay, Parte 1 –
Mampostería simple”, Primera versión 1998. I.E.T., Universidad de la república Oriental del
Uruguay.

[2] - “Load Bearing Brickwork Design”
A.W. Hendry, B. P. Sinha, S. R. Davies
University of Edinburgh
Ellis Horwood Series in Civil Engineering
Halsted Press: a division of John Wiley & Sons
ISBN 0-745-0183-1987

[3] - “Structural Masonry Designers’ Manual”
W. G. Curtin, G. Shaw, J. K. Beck, W. A. Bray
Granada
ISBN 0-246-11208-5-1982

[4] - “Albañilería Estructural”
Héctor Gallegos
Fondo Editorial de la Pontífica Universidad Católica del Perú
Library of Congress TA 670-1989.

[5] - Norma Británica BS 5628 ‘Code of practice for Structural use of masonry’.

[6] - BS 3921 ‘ Specification for Clay bricks and blocks’.

[7] – “An aproximate method for analysing composite wall/beams”
S.R. Davies & A..E. Ahmed, University of Edinburgh.

\- 95 -
