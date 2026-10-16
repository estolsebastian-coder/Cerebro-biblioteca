---
type: libro
title: "Ejemplos2y3"
author: "lauri"
categoria: "ESTRUCTURA"
paginas: 38
extraccion: "texto"
fuente: "local:E:/MATERIAL DE CONSULTA/ESTRUCTURA/BIELAS Y TIRANTES/Ejemplos2y3.pdf"
convertido: 2026-10-16
---

# Ejemplos2y3

> Texto extraído de `ESTRUCTURA\BIELAS Y TIRANTES\Ejemplos2y3.pdf` (38 páginas, texto). El PDF original está en el disco E: (MATERIAL DE CONSULTA); `<!-- p. N -->` marca el inicio de cada página.

<!-- p. 1 -->

Ejemplo 2: Viga T con extremos entallados
soportada por una viga T invertida

David H. Sanders

Sinopsis

En los extremos de las vigas con extremos entallados la transferencia de carga del apoyo
hacia la viga constituye una región D. Los modelos de bielas y tirantes son una herramienta
excelente para modelar estas regiones. En numerosas aplicaciones, por ejemplo en
estructuras para edificios de estacionamiento, se utilizan vigas con extremos entallados en
combinación con vigas T invertidas. En cada punto donde la carga de la viga con extremos
entallados se apoya sobre la viga T invertida se forma una región D. En el siguiente
ejemplo se utilizó el Apéndice A de ACI 318-02 para diseñar tanto la región de los
extremos de la viga con extremos entallados como los estribos y armadura vertical
necesarios para cada punto de carga en la viga T invertida. Las regiones B convencionales
de la viga con extremos entallados se diseñaron utilizando el diseño convencional adoptado
por ACI para el diseño de vigas.

David H. Sanders, miembro de ACI, recibió su título de Ingeniero Civil de la Iowa State
University y su master y doctorado de la Universidad de Texas en Austin. Preside el
Comité ACI 341, Puentes de Hormigón Sismorresistentes, y es miembro de TAC. Sus
investigaciones se relacionan con el comportamiento y diseño de sistemas de hormigón,
con particular énfasis en el diseño de puentes y aplicaciones sísmicas.

<!-- p. 2 -->

Ejemplo 2: Viga T con extremos entallados soportada por una viga T invertida

1 Geometría y cargas

Una viga T de hormigón con extremos entallados es soportada por una viga T invertida. El
alma tiene 10 in. (254 mm) de ancho y la sección tiene una altura total de 19 in. (483 mm)
(ver Figura 2-1). La viga T invertida también tiene una altura de 19 in. (483 mm) y un
ancho de asiento de 7 in. (178 mm) (ver Figura 2-2). Las vigas T están ubicadas con una
separación de 10 pies (3048 mm) sobre la longitud de la viga T invertida y tienen una
longitud de 32 pies (9900 mm). Hay una sobrecarga de 100 psf (4,79 kN/m2) y una carga
permanente superpuesta de 10 psf (0,48 kN/m2).
El ancho de la zona de influencia de cada una de las vigas T es de 10 pies (3048 mm). Por
lo tanto, la sobrecarga efectiva es 1,0 k/ft (14,6 kN/m) y la carga permanente incluyendo la
carga permanente superpuesta es 0,87 k/ft (12,7 kN/m). Esto produce una carga distribuida
factoreada de 2,64 k/ft (38,6 kN/m), calculada en base a 1,2 D + 1,6 L. El momento de
diseño positivo (Mu) es 1/8 x 2,64 x 32,52 x 12 = 4183 in-kips (473 kN-m). La fuerza
horizontal en el apoyo se toma como 10 kips (44,5 kN).
La resistencia del hormigón es 5500 psi (38 MPa). La armadura tiene una tensión de
fluencia igual a 60.000 psi (414 MPa).

5"
(127)

14"
(356)

10" 110" 10"
(254) (2790 mm) (254)

Figura 2-1: Geometría de la viga T

5" 6"
(127) (152)

1" (25)

9" (229)

Detalles y 1" (25)
dimensiones
iguales a ambos 9" (229)
lados

1" (25)
9" 3"
(229) (76)
tramo 32,5 ft (9900 mm)

Figura 2-2: Detalles de la viga con extremos entallados y de la viga T invertida

92

<!-- p. 3 -->

Ejemplo 2: Viga T con extremos entallados soportada por una viga T invertida

2 Procedimiento de diseño

La estructura es una combinación de regiones D en los extremos entallados de la viga T y
cerca de los puntos de carga de la viga T invertida. Las restantes zonas de las vigas
constituyen regiones B. La viga T con extremos entallados simplemente apoyada se
diseñará al momento y corte de forma tradicional. El modelo de bielas y tirantes se usará
para hacer la transición de las fuerzas entre la sección de la viga y la carga concentrada en
el apoyo. Luego la carga concentrada en el apoyo se distribuirá a la viga T invertida.
Se seguirán los siguientes pasos:
− Paso 1: Diseño a flexión de las regiones B.
− Paso 2: Diseño al corte de las regiones B.
− Paso 3: Modelo de bielas y tirantes para los extremos entallados.
− Paso 4: Diseño y verificación de las capacidades de las bielas, tirantes y nodos.
− Paso 5: Modelo de bielas y tirantes para la viga T invertida.
− Paso 6: Diseño y verificación de las capacidades de las bielas, tirantes y nodos.

3 Cálculos

3.1 Paso 1: Diseño a flexión de las regiones B

Se asumió que la armadura de tracción consiste en 2 filas de barras #9 (29 mm). Por lo
tanto, la profundidad efectiva d = 19 − 1,5 − 3/8 − 9/8 − 1,25/2 = 15,375 in. (391 mm), ver
Figura 2-3. Las barras centrales ilustradas en la Figura 2-3 se usarán como parte del
modelo de bielas y tirantes en la región correspondiente a los extremos entallados; no
formarán parte del diseño tradicional a flexión.
El ancho efectivo be = bw + 16 (t) = 10 + 16 (5) = 90 in. (2286 mm)
Fijando Mu = 4183 in-kips = Φ Mn = 0,9 As fy (d − a/2)
As = 5,21 in.2 (3363 mm2) y a = 0,74 in. (19 mm)
Usar 6 barras #9 (29 mm); As = 6,0 in.2 (3871 mm2)
La cantidad de armadura de tracción satisface tanto As mínimo como As máximo.

93

<!-- p. 4 -->

Ejemplo 2: Viga T con extremos entallados soportada por una viga T invertida

Recubrimiento = 1,5 in. (38 mm)
15,375" (391 mm) Estribos #3 (10 mm)

Separación vertical entre barras
3,625 (92 mm) longitudinales = 1,25 in. (32 mm)

Figura 2-3: Sección transversal de la viga T

3.2 Paso 2: Diseño al corte

ACI 318 (1) permite realizar el diseño al corte a una distancia d a partir de la cara del
apoyo. Debido a los extremos entallados, el diseño al corte se determinó a una distancia d a
partir de la cara de la sección corta (d = 7 in. (178 mm)).
Vu = 2,64/12 × (32,5/ 2 × 12 − 4 − 7) = 40,5kips (180kN)
Vc = 2 f´c b w d = 2 5.500 10 × 15,375/1000 = 22,8kips (101kN)

Vu = 40,5 = Φ Vn = Φ (Vc + Vs ) = 0,75(22,8 + Vs ) ⇒ Vs = 31,2kips (139kN)

Vs = 31,2 = A v f y d /s = A v /s60 × 15,375 ⇒ A v /s = 0,0338in 2 /in. (0,86mm 2 / mm)
Si se utilizan aros #3 (10 mm) Av = 0,22 in.2 (142 mm2) y s = 6 in. (152 mm).
Verifica ya que s \< d/2 = 7,7 in. (196 mm).

3.3 Paso 3: Desarrollo de un modelo de bielas y tirantes para la viga con extremos
entallados

En la Figura 2-4 se ilustra el modelo de bielas y tirantes supuesto. Sobre el costado derecho
del modelo de bielas y tirantes se asume que el tirante de la parte inferior de la sección está
ubicado en el centro de la armadura longitudinal de tracción. Se asume que la biela de la
parte superior de la sección está ubicada a una profundidad igual al 10% de la altura total.
Esta también se podría tomar en el centro de la zona de compresión de acuerdo con lo
calculado en el paso 1. La distancia entre los ejes de la biela superior y el tirante inferior es
igual a (15,375 − 0,1 x 19) = 13,48 in. (342 mm). La carga distribuida se reparte al nodo
más cercano usando el ancho de la zona de influencia a cada lado del nodo.
Para determinar el resto de la geometría del modelo de bielas y tirantes es necesario
suponer una ubicación para el Tirante AD, el Tirante BC y el Tirante EF. La ubicación del
Tirante AD permite espacio suficiente para una placa de extremo y los requisitos sobre
recubrimiento de las armaduras (1,5 in. (38 mm)). El Tirante BC estará formado por varios
94

<!-- p. 5 -->

Ejemplo 2: Viga T con extremos entallados soportada por una viga T invertida

estribos y, por lo tanto, el baricentro se debe ubicar alejado del extremo de la viga. El
Tirante EF se colocó a una distancia igual a dos separaciones de los estribos (12 in. (305
mm)) a partir de BC. Ver Figura 2-4.
A partir de consideraciones geométricas surge:
tan θ1 = 5,1/8 ⇒θ1 = 32,5º tan θ 2 = 5,1/ 7 ⇒θ 2 = 36,1º
tan θ 3 = 8,38/ 7 ⇒θ 3 = 50,1º tan θ 4 = 5,1/5 ⇒θ 4 = 45,6º

A partir de consideraciones estáticas tenemos:
Biela AB = 78,2 kips (348 kN) Tirante AD = 76,0 kips (338 kN)
Biela BD = 62,9 kips (280 kN) Biela BE = 15,2 kips (67,6 kN)
Tirante BC = 76,9 kips (342 kN) Biela CD = 100 kips (445 kN)
Tirante CF = 64,3 kips (286 kN) Tirante EF = 37,0 kips (164 kN)
Biela DE = 55,9 kips (249 kN)

Reacción vertical = 43,6 kips (194 kN)
Reacción Horizontal = 10 kips (44,5 kN)

1,5 k 2,2 k 2,9 k
(6,7) (9,8) (12,9)
1,90"
B
7" (48)
E
(178)
A θ1 θ2 D θ4 10 k 2"
(44,5) 13,48" (51)
(342)

10"
(25) 43,6 k θ3
(194) 3,63"
C F (92)

3" 4" 4" 7" 5" (mm ó N)
(76) (102) (102) (178) (127)

Figura 2-4: Modelo de bielas y tirantes supuesto

95

<!-- p. 6 -->

Ejemplo 2: Viga T con extremos entallados soportada por una viga T invertida

3.4 Paso 4: Diseño y verificación de las capacidades de las bielas, tirantes y nodos

3.4.1 Nodo A
Es necesario verificar el Nodo A, es decir, la unión de la Biela AB y el Tirante AD en el
apoyo extremo (ver Figura 2-5). La superficie de apoyo es 4 in. x 7 in. (102 mm x 178
mm). La longitud de desarrollo potencial para el Tirante AD se extiende hasta el punto
donde el Tirante AD abandona la Biela AB. Debido a la escasa longitud de desarrollo, a fin
de proveer desarrollo es necesario utilizar una placa en el extremo de la armadura del
tirante. Esta placa también se tomó de 4 in. x 7 in. (102 mm x 178 mm). Si se proveyera
mayor distancia más allá del apoyo o armadura adicional en el tirante puede que no fuera
necesario utilizar la placa de extremo. El Código ACI actual no permite reducir la longitud
de desarrollo aún cuando haya una elevada carga de compresión en la barra.
Para el nodo βn es igual a 0,80 porque hay un tirante anclado. Para la Biela AB βs puede
ser 0,60 ó 0,75 si se colocan estribos suficientes: Σ Asi /bsi sin γi ≥ 0,003. AB => 0,22 /
(10x2) x sin (90 − 32,5) = 0,009 >> 0,003. De modo que se podría usar βs = 0,75 si los
estribos #3 (10 mm) se prolongaran hacia el extremo entallado. Se demostrará que esto no
es necesario para proveer capacidad.

Capacidad de apoyo (A) = 0,75 (0,85 x 0,8 x 5,5) (4 x 7) =
79 kips (351 kN) > 43,6 kips (194 kN) Verifica
Capacidad de la placa de apoyo del tirante (A) = 0,75 (0,85 x 0,8 x 5,5) (4 x 7) =
79 kips (351 kN) > 75,9 kips (338 kN) Verifica
Armadura del tirante (AD) => 75,9 kips = 0,75 (As,AD) 60 => As,AD = 1,69 in.2 (1090 mm2)
Usar 3 barras #7 (22 mm); As,AD = 1,80 in.2 (1161 mm2) (Si se desea acortar la longitud de
desarrollo o aumentar el tamaño del nodo se podría usar más de una capa.)

Ancho Biela AB (perpendicular a la línea de acción) = l b sin θ1 + h t cos θ1 =

\= 4 sin (32,5) + 4 cos (32,5) = 5,52 in. (140 mm)
Asumir que el ancho de la biela es igual al ancho de la viga (10 in. (254 mm)).
Capacidad Biela AB = 0,75 (0,85 x 0,6 x 5,5) (5,52 x 10) = 116 kips (516 kN)
\> 78,2 kips (348 kN) Verifica. No es necesario colocar armadura en la biela.

La dimensión dada en la Figura 2-5 para la distancia entre la parte inferior de la sección y
el Tirante CF es ligeramente diferente a la dimensión de la Figura 2-4, utilizada para
calcular los ángulos. Esto se debe a la necesidad de acomodar la armadura del Tirante BC.
Debido a que la variación fue insignificante las fuerzas y los ángulos no se calcularon
nuevamente.

96

<!-- p. 7 -->

Ejemplo 2: Viga T con extremos entallados soportada por una viga T invertida

El nodo está distribuido sobre
6"(152) los cuatro estribos #3 (10)
3#5 (16)
2,31" (59) B E 1,9" (48)

2#3 (10)
4,69" (119)
D

2" (51) A 3#7 (22) 13,29" (337)
\> l d
5,06" (129)
\> ld C F 6#9 (29)

2,25" (57)
3,81" (97)
2,69" (68)

Todas las placas 4" (102) recubrimiento
requerido = 1,5" (38) son 4" (102) 2" (51) 4" (102) 2" (51)
pulgadas (mm)
\> l d

Figura 2-5: Detalles de las bielas y tirantes con la armadura propuesta

3.4.2 Nodo B
Para el Nodo B βn es igual a 0,80 porque está anclando un tirante. Para la Biela BE βs es
igual a 1. Como el nodo tiene un β menor que la Biela BE, esta última no será
determinante. Para las Bielas AB y BD los valores de βs son 0,60 y por lo tanto serán
determinantes para el diseño a compresión. El tamaño de las bielas es determinado por el
ancho del Tirante BC.
Tirante BC = 76,8 kips = 0,75 (As,BC) 60 => As,BC = 1,71 in.2 (1103 mm2)
Usar 3 estribos #5 (16 mm); As,BC = 1,86 in.2 (1200 mm2)
La Figura 2-5 muestra la configuración del Nodo B. Los estribos #5 (16 mm) se colocaron
con una separación de 2 in. (51 mm), creando una cara nodal de 2 x 2 + 2 = 6 in. (152
mm). Las 2 in. (51 mm) adicionales surgen de permitir que el ancho del tirante se extienda
algo más allá de la armadura (separación/2).

AnchoBiela AB = l b sin θ + h t cos θ =
6/ 2(32,5) + 3,8cos(32,5) = 4,82in. (122mm)
Ancho Biela BD = l b sin θ+ h t cos θ =
6/ 2sin(36,1) + 3,8cos(36,1) = 4,84in. (123mm)

Para las Bielas AB y BD considerar el ancho de la biela igual al ancho del alma de la viga
(10 in. (25 mm)). Si se desprecia la armadura βs para las bielas es 0,60 (bielas en forma de
botella). Por lo tanto, βs se podría aumentar a 0,75 si se dispone armadura que satisfaga
97

<!-- p. 8 -->

Ejemplo 2: Viga T con extremos entallados soportada por una viga T invertida

A3.3.1 (Σ Asi /bsi sin γi ≥ 0,003). En la figura 2-5 no se muestra el límite superior de la
Biela BD porque toda el área está en compresión. Además, la biela se dirige al Nodo D,
que es un nodo distribuido.

Capacidad Bielas AB y BD = 0,75 (0,85 x 0,6 x 5,5) (4,8 x 10) = 101 kips (449 kN)
\> 78,2 y 62,9 kips (348 y 280 kN) Verifica

La longitud de desarrollo para el Tirante BC en el Nodo B está determinada por las
verificaciones del desarrollo de los estribos de las Secciones 12.13 y 7.1.3 de ACI 318. El
tirante debe anclarse tanto en su parte superior como en su parte inferior.

3.4.3 Nodo C
Para el nodo βn es igual a 0,60 porque está anclando dos tirantes. El ancho inferior del
nodo se fijó en función de la armadura vertical del Tirante BC, 6 in. (152 mm). En la
Figura 2-5 se ilustra una placa de apoyo, la cual se podría eliminar moviendo el
nodo/centro de la armadura hacia la derecha o aumentando la distancia entre la armadura
vertical. La longitud de desarrollo se mide a partir del límite extremo derecho del nodo
hacia la placa de apoyo.
Armadura Tirante CF => 64,2 kips = 0,75 (As,CF) 60 => As,CF = 1,43 in.2 (920 mm2). Si las
6 barras #9 (29 mm) se prolongan hacia el interior del Nodo C As,CF = 6,0 in.2 (3871 mm2).
La armadura adicional ayudará a reducir la longitud de desarrollo necesaria, pero aún así
será mayor que la disponible. La distancia disponible para desarrollar el Tirante CF en el
nodo es la distancia desde el borde del hormigón menos el recubrimiento hasta el punto
donde el tirante abandona la Biela CD: 6 − 1,5 + 2 tan (50,1) = 6,9 in. (175 mm). En este
caso a las barras #9 (29 mm) se agregó una placa de apoyo de 5 in. x 7 in. (127 mm x 178
mm).

Capacidad placa de apoyo Tirante CF = 0,75 (0,85 x 0,6 x 5,5) (5 x 7)
\= 73,6 kips (327 kN) > 64,2 kips (286 kN) Verifica
Ancho Biela CD = l b sin θ+ h t cos θ = 6 sin (50,1) + 4 cos (50,1) = 7,2 in. (182 mm)
Asumir que el ancho de la biela es igual al ancho de la viga (10 in. (254 mm)) y que βs =
0,6.
Capacidad Biela CD = 0,75 (0,85 x 0,6 x 5,5) (7,2 x 10) = 179 kips (796 kN)
100 kips (445 kN) Verifica

3.4.4 Nodo D
Para el Nodo D sólo hay que determinar la longitud de desarrollo del Tirante AD. Las
bielas que ingresan al Nodo D están distribuidas. En el Nodo D el ancho de una biela será
mayor o igual que el ancho de la biela en el otro extremo (Nodo B y Nodo C). Por lo tanto,
98

<!-- p. 9 -->

Ejemplo 2: Viga T con extremos entallados soportada por una viga T invertida

en el Nodo D las verificaciones de capacidad quedan satisfechas por las verificaciones
realizadas en 3.4.3 y 3.4.4. Se asumió que el ancho de la biela era constante entre los
Nodos C y D. Con esto queda definido el límite izquierdo del nodo y el punto a partir del
cual se puede desarrollar el Tirante AD.
Longitud de desarrollo para AD => ld/db = 60.000 (1) (1) (1) (25 5500 ) =>

ld = 28,3 in. (719 mm) medidos a partir del lado izquierdo del Nodo D.

3.4.5 Nodos E y F
Ambos nodos están distribuidos sobre múltiples estribos. El número de estribos depende de
la fuerza en el Tirante EF.
Tirante EF = 37,0 kips = 0,75 (As,EF) 60 => As,EF = 0,82 in.2 (529 mm2). Usar 4 estribos #3
(10 mm) con una separación de 4 in. (102 mm). As,EF = 0,88 in.2 (567 mm2). Con la
separación de 4 in. (102 mm) se obtiene un baricentro sobre la recta EF y una distribución
de los estribos entre el Nodo C y el Nodo F.

3.4.6 Modelos Alternativos
Se han desarrollado otros modelos potenciales para vigas con extremos entallados. Las
Recomendaciones FIP "Diseño práctico del hormigón estructural" (2) contiene uno de
estos modelos (ver Figura 2-6). Ensayos realizados indican que se forma una fisura en la
esquina hacia la derecha del apoyo. En el primer modelo (ver Figura 2-4) una biela (BD)
atraviesa la fisura, mientras que en este modelo no existe esa área de compresión. Esto es
más compatible con la formación de fisuras, ya que permitiría que el área traccionada se
extienda más aún hacia el interior de la viga. En el modelo alternativo el valor del Tirante
AD es igual al ilustrado en el primer modelo, pero los valores de los Tirantes BC y CF son
mucho menores en el modelo FIP. Esta es una solución aceptable para el modelo de bielas
y tirantes.
1,5 k 1,7 k 2,4 k
(6,7) (7,6) (10,7)
1,90"
B (48)
7" E
fisura (178)
A θ1 D 2" 10 k 13,48"
(51) (44,5) (342)

10"
(25) 43,6 k θ2 (194)
3,63"
C F (92)

3" 4" 4" 7" (mm ó N)
(76) (102) (102) (178)

Figura 2-6: Modelo alternativo

99

<!-- p. 10 -->

Ejemplo 2: Viga T con extremos entallados soportada por una viga T invertida

A partir de consideraciones geométricas surge:
tan θ1 = 5,1/8 ⇒θ1 = 32,5º tan θ 2 = 8,38/ 7 ⇒θ 2 = 50,1º

A partir de consideraciones estáticas tenemos:
Biela AB = 78,2 kips (348 kN) Tirante AD = 76,0 kips (338 kN)
Biela BE = 76,0 kips (338 kN) Tirante BC = 40,4 kips (180 kN)
Biela BC = 52,7 kips (234 kN) Tirante DF = 38,0 kips (169 kN)
Tirante CF = 33,8 kips (150 kN)

Reacción vertical = 43,6 kips (194 kN)
Reacción Horizontal = 10 kips (44,6 kN)

3.5 Paso 5: Modelo de bielas y tirantes para la viga T invertida

La Figura 2-7 ilustra el modelo de bielas y tirantes supuesto. A lo largo del eje longitudinal
de la viga T invertida se utilizará la teoría tradicional de vigas.
A partir de consideraciones geométricas surge: tan θ = (5,1)/6,625 ⇒ θ = 37,6º
A partir de consideraciones estáticas tenemos:
Biela AC = 71,5 kips (318 kN) Tirante AB = 66,6 kips (296 kN)
Tirante CE = 43,6 kips (194 kN) Biela CD = 56,6 kips (252 kN)

2,625" 4,75" 2,625" E 43,6 k 10 k
(67) (121) (67) (194 kN) (44,5 kN)

F E 0,5" (13) 43,6 k 43,6 k
A 1,5" (38) (194 kN) (194 kN)
10 k 10 k 10" (254) B θ 1,5" (38)
(44,5 kN) (44,5 kN)
0,5" (13)
2" (51) B
A θ D 3,1" (79)
5,1" (130) C
D C 0,1h = 1,9" (48)
0,1h = 1,9" (48)
2,625" 2" 2" 2" 1" 3" 6,625" 4,75" 6,625" 3" (mm) (mm) (67) (51) (51) (51) (25) (76) (168) (121) (168) (76)

Figura 2-7: Modelo de bielas y tirantes Figura 2-8: Detalles de las bielas y
para la viga T invertida tirantes

100

<!-- p. 11 -->

Ejemplo 2: Viga T con extremos entallados soportada por una viga T invertida

3.6 Paso 6: Diseño y verificación de las capacidades de las bielas, tirantes y nodos de
una viga T invertida

3.6.1 Nodo A
Es necesario verificar/diseñar la resultante de la Biela AC y el Tirante AB en el apoyo de
la viga T invertida (ver Figura 2-8). La superficie de apoyo para la saliente de la viga T es
de 4 in. x 7 in. (127 mm x 178 mm). Debido a la escasa longitud de desarrollo es necesario
usar una placa de extremo. Esta placa también se tomó de 4 in. x 7 in. (102 mm x 178
mm). Utilizar este tipo de placas y soldar las barras a la placa constituyen prácticas
habituales.
Para el nodo βs es igual a 0,80 porque está anclando un tirante. Para la Biela AB βs puede
ser 0,60 ó 0,75 si se colocan estribos suficientes: Σ Asi /bsi sin γi ≥ 0,003.

Capacidad de apoyo = 0,75 (0,85 x 0,8 x 5,5) (4 x 7) = 78,5 kips (349 kN)
\> 43,6 kips (194 kN) Verifica
Capacidad de la placa de apoyo del tirante = 0,75 (0,85 x 0,8 x 5,5) (4 x 7) =
78,5 kips (349 kN) > 66,6 kips (796 kN) Verifica
Armadura del tirante AB => 66,6 kips = 0,75 (As,AB) 60 => As,AB = 1,48 in.2
Usar 3 barras #7 (22 mm); As,AB = 1,80 in.2 (1161 mm2)

Ancho Biela AC (perpendicular a la línea de acción) = l b sin θ+ h t cos θ =
\= 4 sin (37,6) + 4 cos (37,6) = 5,61 in. (142 mm)
Asumir que el ancho de la biela es igual al ancho de la sección (10 in. (254 mm)).
Capacidad Biela AC en (A) = 0,75 (0,85 x 0,6 x 5,5) (5,61 x 10) = 118 kips (525 kN)
\> 71,5 kips (318 kN) Verifica.

3.6.2 Nodo C
Para el Nodo C hay una tracción transversal originada por la flexión longitudinal de la viga
T invertida. Por lo tanto βs es 0,60 ya que habría dos o más tirantes anclados en un modelo
de bielas y tirantes tridimensional. Para las Bielas AC y CD βs sería 0,4 ya que están
ubicadas en la zona traccionada del miembro.

Armadura del tirante CE => 43,6 kips = 0,75 (As,CE) 60 => As,CE = 0,97 in.2. Usar 4 barras
\#5 (16 mm); As,CE = 1,24 in.2 (800 mm2). Distribuir las barras como se indica en la Figura
2-9. Las barras estarán a 3 in. (76 mm) entre centro y centro a lo largo del eje longitudinal
de la viga T invertida. La separación de 3 in. (76 mm) proporciona una distribución de los
estribos en el ancho de asiento de la viga T.

101

<!-- p. 12 -->

Ejemplo 2: Viga T con extremos entallados soportada por una viga T invertida

La ubicación del Nodo C se tomó a 0,1h de la parte inferior de la viga, por lo tanto la altura
del nodo es el doble de dicho valor ó 3,8 in. (96 mm). El ancho del nodo es determinado
por la armadura vertical (Tirante CE). El ancho se tomó como el tamaño de las barras más
1 in. (25 mm) a cada lado. Actualmente el Apéndice A no contiene este tipo de
lineamientos. El ancho de la Biela AC es igual a l b sin θ + h t cos θ = (2,62) sin (37,6) +
(3,8) cos (37,6) = 4,61 in. (117 mm). El ancho de la biela es igual al ancho de la armadura
del Tirante CE en el eje longitudinal de la viga T invertida (9 in.) más la mitad de la
separación (1,5 in. (38 mm)) a cada lado de la armadura (11,5 in. (292 mm)). Capacidad
Biela AC en (A) = 0,75 (0,85 x 0,4 x 5,5) (4,61 x 11,5) = 74,4 kips (331 kN) > 71,5 kips
(318 kN) Verifica.

El espesor de la Biela CD es igual al de la Biela AC (11,5 in. (292 mm)) y el ancho es 1,9
x 2 = 3,8 in. (96 mm).
Capacidad Biela CD en (C) = 0,75 (0,85 x 0,4 x 5,5) (3,8 x 11,5) = 61,3 kips (273 kN) >
56,6 kips (252 kN) Verifica.

Debido al mayor valor de β en comparación con el de las bielas, el nodo no determina el
diseño.

A Corte A-A
4 #5 (16) a 3" (76)

pulgadas (mm)
10"
(254) Todas las placas
son de 4 " (102)

2" recubrimiento
(51) 1,5" (38)

9"
(209) 3 # 7 (22)
a 3" (76)

A 0,5" 3" 3" 3" 0,5"
(13) (76) (76) (76) (13)

Figura 2-9: Detalles de las armaduras para la viga T invertida

4 Conclusiones

El ejemplo muestra cómo los requisitos del Apéndice A permiten modelar el flujo de las
fuerzas a través de una estructura. Los modelos le proporcionan al ingeniero una
herramienta de diseño racional para las partes de una estructura en las cuales no se puede
aplicar la teoría de vigas tradicional.

102

<!-- p. 13 -->

Ejemplo 2: Viga T con extremos entallados soportada por una viga T invertida

5 Notación

a = altura del diagrama rectangular de tensiones equivalente, in. (mm)
As = sección de armadura de tracción no pretensada, in.2 (mm2)
Asi = sección de armadura superficial en la capa i que atraviesa una biela
As,IJ = sección de armadura en el Tirante IJ, in.2 (mm2)
Av = sección de armadura de corte en una distancia s, in.2 (mm2)
b = ancho de un miembro, in. (mm)
be = ancho efectivo de alas de una viga T, in. (mm)
d = distancia entre la fibra extrema comprimida y el baricentro de las barras
traccionadas (profundidad efectiva), in. (mm)
fc' = resistencia a la compresión especificada del hormigón, psi (MPa)
fy = resistencia a la fluencia especificada de la armadura no pretensada, psi (MPa)
ht = altura efectiva de un tirante, in. (mm)
lb = longitud de la superficie de apoyo, in. (mm)
Mu = momento factoreado en una sección, in.-kips (kN-m)
s = separación de los estribos sobre el eje longitudinal de un miembro, in. (mm)
si = separación de la armadura en la capa i adyacente a la superficie de un miembro,
in. (mm)
Vc = resistencia nominal al corte provista por el hormigón, kips (kN)
Vn = resistencia nominal al corte en una sección, kips (kN)
Vs = resistencia nominal al corte provista por la armadura de corte, kips (kN)
Vu = carga de corte factoreada, kips (kN)
βb = factor que toma en cuenta los efectos de la resistencia de anclaje de una zona
nodal
βs = factor que toma en cuenta los efectos de la fisuración y la armadura de
confinamiento sobre la resistencia efectiva a la compresión del hormigón de una
biela
γi = ángulo formado por el eje de una biela y las barras en la capa i de armadura que
atraviesa dicha biela, grados
Φ = factor de reducción de la resistencia
θ = ángulo formado por dos bielas o tirantes en un nodo, grados

103

<!-- p. 14 -->

Ejemplo 2: Viga T con extremos entallados soportada por una viga T invertida

6 Referencias

American Concrete Institute (2002): Apéndice A de ACI 318-02 (Building Code
Requirements for Structural Concrete) y ACI 318R-02 (Commentary).
Recomendaciones FIP (1999): Practical Design of Structural Concrete.
Comisión FIP 3: "Practical Design", Sept. 1996.
Publ.: SETO, Londres, Sept. 1999. (Distribuido por: fib, Lausanne)

104

<!-- p. 15 -->

Ejemplo 3.1: Ménsula en una columna

Tjen N. Tjhin

Daniel A. Kuchma

Sinopsis

Se diseñó una ménsula que se proyecta a partir de una columna cuadrada de 14 in. (356
mm) de lado usando el método de bielas y tirantes de acuerdo con el Apéndice A de ACI
318-02. La ménsula ha de soportar la fuerza de reacción de una viga premoldeada, Vu,
igual a 56,2 kips (250 kN) actuando a una distancia 4 in. (102 mm) de la cara de la
columna. Se asume que en la parte superior de la ménsula se desarrolla una fuerza de
tracción horizontal, Nuc, igual a 11,2 kips (49,8 kN), la cual toma en cuenta las
deformaciones por fluencia lenta y retracción. En la Figura (3.1-1) se describen la
estructura y las cargas. Se considera hormigón de peso normal con una resistencia a la
compresión especificada, fc', igual a 5 ksi (34,5 MPa). La resistencia a la fluencia de la
armadura, fy, se toma igual a 60 ksi (414 MPa).
En la Figura (3.1-2) se muestran las dimensiones seleccionadas para la ménsula,
incluyendo su placa de apoyo. La relación longitud de corte / profundidad correspondiente,
a/d, es igual a 0,24. A fin de satisfacer los requisitos del código se seleccionó el modelo de
bielas y tirantes sencillo ilustrado en la Figura (3.1-3). La armadura principal del tirante
dispuesta es de 5 barras #4 (#13 mm). Estas barras están soldadas a un perfil de acero
estructural de 3½ in. x 3½ in. x ½ in. (89 mm x 89 mm x 13 mm). En la Figura (3.1-5) se
indican los detalles de las armaduras.

Tjen N. Tjhin es candidato al doctorado en el Departamento de Ingeniería Civil y
Ambiental de la Universidad de Illinois en Urbana-Champaign. Sus investigaciones
abarcan el análisis no lineal y el diseño de estructuras de hormigón.

Daniel (Dan) A. Kuchma es Profesor Adjunto de Ingeniería Civil y Ambiental de la
Universidad de Illinois en Urbana-Champaign. Es miembro del Subcomité ACI 318E,
Corte y Torsión, y también del Comité conjunto ACI-ASCE 445, Corte y Torsión, y su
Subcomité 445-A, Bielas y Tirantes.

<!-- p. 16 -->

Ejemplo 3.1: Ménsula en una columna

1 Geometría y cargas

En la Figura (3.1-1) se ilustran la ménsula a diseñar y sus cargas.

Vu = 56,2 kips
(250 kN)
4" (102 mm)
N uc = 11,2 kips
(49,8 kN)

14"
\=
A A b

14"

14" Corte A-A
(356 mm)

Figura 3.1-1: Geometría y cargas de la ménsula

Resistencias de los materiales:
fc' = 5 ksi (34,5 MPa) (hormigón de peso normal)
fy = 60 ksi (414 MPa)

106

<!-- p. 17 -->

Ejemplo 3.1: Ménsula en una columna

2 Procedimiento de diseño

La totalidad de la estructura considerada constituye una región perturbada debido a que
presenta cambios abruptos en su geometría y está próxima a fuerzas concentradas. La
estructura se diseñará usando el método de bielas y tirantes de acuerdo con el Apéndice A
de ACI 318-02. El procedimiento paso a paso es el siguiente:
− Paso 1: Determinar las dimensiones de la placa de apoyo.
− Paso 2: Seleccionar las dimensiones de la ménsula.
− Paso 3: Establecer el modelo de bielas y tirantes.
− Paso 4: Determinar las fuerzas requeridas en el reticulado.
− Paso 5: Seleccionar la armadura de los tirantes.
− Paso 6: Diseñar las zonas nodales y verificar los anclajes.
− Paso 7: Verificar las bielas.
− Paso 8: Calcular la armadura mínima requerida para limitar la fisuración.
− Paso 9: Detallar la armadura.

3 Cálculos

3.1 Paso 1: Determinar las dimensiones de la placa de apoyo

La zona nodal debajo de la placa de apoyo constituye un nodo solicitado por compresión y
tracción (CCT). La correspondiente resistencia efectiva a la compresión es
f cu = 0,85β n f c´ [ACI Sección A.5.2 ec. (A-8)]
\= 0,85(0,80)(5000) = 3400psi.

Seleccionamos una placa de apoyo de 12 in. x 6 in. (305 mm x 152 mm). La superficie de
la placa de apoyo es 12 x 6 = 72 in.2 (46.451 mm2), y la tensión de apoyo es 56,2 (1000)/72
\= 781 psi (5,38 MPa). Como este valor es menor que la tensión de apoyo límite, es decir,
φfcu = 0,75 (3400) = 2550 psi (17,58 MPa), las dimensiones de la placa de apoyo
seleccionada son adecuadas.

3.2 Paso 2: Seleccionar las dimensiones de la ménsula

Para poder utilizar el Apéndice A de ACI, la Sección 11.9.1 del código requiere una
relación longitud de corte/profundidad, a/d, menor que 2. Para la ménsula seleccionamos

107

<!-- p. 18 -->

Ejemplo 3.1: Ménsula en una columna

una profundidad total en la cara de la columna igual a 18 in. (457 mm). Además, la
Sección 11.9.2 de ACI requiere que la profundidad en la parte exterior de esta área de
apoyo sea al menos la mitad de la profundidad en la cara de la columna. Para satisfacer
este requisito seleccionamos una profundidad de 9 in. (229 mm) en el extremo libre de la
ménsula. La Figura (3.1-2) resume las dimensiones seleccionadas para la ménsula.

Placa de apoyo
12" x 6"
(305 mm x 152 mm)

2" 6" 1"

9" mm)
(457
18" 9"

9" 14"
(229 mm) (356 mm)

Figura 3.1-2: Dimensiones seleccionadas para la ménsula

3.3 Paso 3: Establecer el modelo de bielas y tirantes

Con el objeto de considerar las excentricidades de las cargas y las tolerancias de
fabricación, la posición de Vu se traslada 1 in. desde el centro de la placa de apoyo hacia el
borde exterior de la ménsula. Por lo tanto, la nueva posición con respecto a la cara de la
columna es 1 + 6/2 + 1 = 5 in.
Seleccionamos un modelo de bielas y tirantes sencillo. En la Figura (3.1-3) se indica su
geometría. Se asume que el centro del tirante CB está ubicado a una distancia de 1,6 in. a
partir de la parte superior de la ménsula, considerando una capa de barras de armadura y
aproximadamente 1 in. de recubrimiento de hormigón. Por lo tanto,
d = 18 − 1,6 = 16,4in.(417mm) [ACI Sección 11.9.1)]

Se asume que el tirante horizontal DA está ubicado sobre la recta horizontal que atraviesa
el extremo inclinado de la ménsula.

108

<!-- p. 19 -->

Ejemplo 3.1: Ménsula en una columna

La posición del eje de la biela DD' se puede hallar calculando el ancho de biela ws, el cual
se puede obtener planteando la ecuación de momentos respecto del nodo A de la siguiente
manera:
 w s 
56,2(0,32 + 5 + 12) + 11,2(16,4) = Fu,DD´  12 −  (3.1-1)
 2 
donde Fu,DD' = φ fcu bws es la fuerza de compresión requerida en la biela DD' y b es la
dimensión fuera del plano de la ménsula. Al igual que el nodo debajo de la placa de apoyo
(nodo C), el nodo D es también un nodo CCT. Por lo tanto, según la Sección A.5.2 de ACI,
su tensión está limitada a φfcu = 2550 psi (17,58 MPa), y Fu,DD' = 2550 (14) ws / 1000 =
35,7ws.
Reemplazando Fu,DD' en la ecuación (3.1-1) y resolviendo se obtiene Fu,DD' = 111 kips (494
kN) y ws = 3,10 in. (79 mm).
De esta manera queda corregida la geometría del reticulado.

Vu= 56,2 kips
(250 kN) Resultante

0,32" 5"
N uc = 11,2 kips
1,6" 34,8 k
C (155 kN) B
kN)

k kN) mm) (-288 16,4" (-60,9 k (-271
\= 54,6 k) (243 d (417 kN) -64,7 67,3° 57,5°
11,2 k
D (49,8 kN) A

k
111
D´ A´

12" 2"

φfcu

ws= 3,10" (79 mm)

Figura 3.1-3: Modelo de bielas y tirantes seleccionado

109

<!-- p. 20 -->

Ejemplo 3.1: Ménsula en una columna

3.4 Paso 4: Determinar las fuerzas requeridas en el reticulado

Las fuerzas requeridas en todos los miembros del reticulado se determinan en base a
consideraciones estáticas; estas fuerzas se resumen en la Tabla (3.1-1). Un signo positivo
(+) indica que el miembro está traccionado; un signo negativo (-) indica que el miembro
está comprimido.

Tabla 3.1-1: Fuerzas en el reticulado

Miembro CD CB BD BA DA DD'
Fuerza -60,9 +34,8 -64,7 +54,6 +11,2 -111
(kips) (-271 kN) (+155 kN) (-288 kN) (+243 kN) (+49,8 kN) (-494 kN)

3.5 Paso 5: Seleccionar la armadura de los tirantes

La sección de armadura requerida para el tirante CB es
Fu,CB 34,8 2 = = 0,77in. [ACI Secciones A.2.6 y A.4.1]
φf y 0,75(60)

La sección de armadura provista debe ser de al menos
f c´ 0,04(5) 2 0,04 bd = (14)(16,4) = 0,77in. [ACI Sección 11.9.5]
f y 60
Adoptamos 4 barras #4 (#13 mm), Ast = 4 (0,20) = 0,80 in.2 (516 mm2).
Como se indica en la Tabla (3.1-1), el tirante BA está más traccionado que el tirante CB.
Sin embargo, esta fuerza del tirante debe ser resistida mediante la armadura longitudinal de
la columna. Por lo tanto prolongamos las 4 barras #4 hacia abajo en la columna sólo para
tener suficiente longitud de desarrollo.
La sección de armadura requerida para el Tirante DA es
Fu,DA 11,2 2 = = 0,25in. [ACI Secciones A.2.6 y A.4.1]
φf y 0,75(60)

Seleccionamos 2 estribos de columna adicionales #3 (#10 mm) en la posición DA,
Ast = 2 (2) (0,11) = 0,44 in.2 (284 mm2). Estas barras están separadas 2 in. (51 mm) entre
centros.

110

<!-- p. 21 -->

Ejemplo 3.1: Ménsula en una columna

3.6 Paso 6: Diseñar las zonas nodales y verificar los anclajes

El ancho ws de la zona nodal D ya fue seleccionado en la Sección 3.3 de manera de
satisfacer la tensión límite en dicha zona nodal. Por lo tanto en esta sección sólo
verificaremos la zona nodal C.
Para satisfacer la tensión límite en la zona nodal C es necesario que el ancho efectivo del
tirante, wt, sea al menos igual a
Fu,CB 34,8(1000) = = 0,97in. (25mm) [ACI Secciones A.2.6 y A.5.1]
φf cu b 2550(14)

Este límite se satisface fácilmente porque el ancho de tirante disponible es 2 (1,6) = 3,2 in.
(81 mm). Ver Figura (3.1-4).
Para anclar el tirante CB soldar las 4 barras #4 a un perfil de acero de 3½ in. x 3½ in. x ½
in. (89 mm x 89 mm x 13 mm). En la Figura (3.1-5) se indican los detalles.

3.7 Paso 7: Verificar las bielas

La biela CD se verificará en base a las dimensiones determinadas por las zonas nodales C y
D. Las demás bielas se verificarán calculando los anchos de las mismas y verificando si
cabrán en el espacio disponible.
La resistencia nominal de la biela CD está limitada a
Fns = f cu A c [ACI Sección A.3.1 ec. (A-2)]

donde
f cu = 0,85β s f c´ [ACI Sección A.3.2 ec. (A-3)]
\= 0,85(0,75)(5000) = 3188psi

y Ac es la menor de las áreas en los extremos de la biela. De la Figura (3.1-4), Ac = 14
(2,86) = 40,04 in.2. Por lo tanto, Fns = 3188 (40,04)/1000 = 128 kips. De la Tabla 3.1-1, la
carga factoreada de la biela CD es 60,9 kips (271 kN). Debido a que este valor es menor
que el límite, es decir, φFns = 0,75 (128) = 96 kips (427 kN), la biela CD resulta adecuada.
Como se ha asumido βs = 0,75 se colocará armadura mínima; los cálculos se incluyen en la
sección siguiente.
La resistencia efectiva a la compresión de la biela BD también está limitada a fcu = 3188
psi. En consecuencia el ancho requerido para la biela BD es
Fu,BD 64,7(1000) = = 1,93in. [ACI Sección A.2.6 y A.3.1]
φf cu b 0,75(3188)(14)

111

<!-- p. 22 -->

Ejemplo 3.1: Ménsula en una columna

Adoptamos un ancho de 2 in. (51 mm) para la biela BD. El ancho requerido para la biela
DD' ya fue determinado en la Sección 3.2, habiéndose obtenido un ancho de 3,10 in. (79
mm).
Como se ilustra en la Figura (3.1-4), todos los anchos de las bielas caben dentro de los
límites de la región de la ménsula. En consecuencia esta solución es aceptable.

3.8 Paso 8: Calcular la armadura mínima requerida para limitar la fisuración

La Sección 11.9.4 de ACI requiere zunchos o estribos cerrados paralelos a la armadura
requerida para el tirante CB, uniformemente distribuidos en dos tercios de la profundidad
efectiva adyacente al tirante CB, es decir, 2/3 (16,4) = 10,9 in. Adoptamos 10,5 in. La
sección de estos estribos debe ser mayor que
A h = 0,5 ( A st − A n ) [ACI Sección 11.9.4]

donde An es la sección de armadura que resiste la fuerza de tracción Nuc y Ast ≡ As según la
Sección 11.9 de ACI. Por lo tanto, la sección mínima requerida es
A h = 0,5 ( A st − A n )
 N uc   11,2  2 = 0,5  A st −  = 0,5  0,80 −  = 0,29in.  0,85(60)   φf y  
Intentamos con 3 estribos cerrados #3, Av = 3 (2) (0,11) = 0,66 in.2, con una separación
media de 10,5 / 3 = 3,5 in.
Como para las bielas diagonales usamos βs = 0,75 la armadura mínima provista también
debe satisfacer

sin γ i ≥ 0,0030 [ACI Sección A.3.3.1 ec. (A-4)] ∑ A si bs i
donde γi es el ángulo formado por el eje de la armadura mínima y el eje de la biela. De
acuerdo con la Sección A.3.3.2 de ACI γi debe ser mayor que 40º porque solamente se
provee armadura horizontal. En base a la armadura provista y al ángulo de la biela BD, es
decir el menor ángulo entre una biela y la armadura mínima,

sin γ i = sin57,5º = 0,0038 > 0,003. ∑ A si 2(0,11) bs i 14(3,5)

Como esta cantidad de armadura satisface ambos requisitos, disponemos 3 estribos
cerrados #3 (#10 mm) con una separación de 3,5 in. (89 mm), distribuidos en una
profundidad de 10,5 in. (267 mm) a partir del tirante CB.

112

<!-- p. 23 -->

Ejemplo 3.1: Ménsula en una columna

Zona l b = 5,5" (140 mm)
Nodal C
C Tirante CB
Perfil de acero wt = 3,2" (81 mm)
1" 1" 1"
3 2 x 3 2 x 2

Zona nodal
extendida C Biela (51 2" mm) CD
BD
2,86" Biela mm) (73

Zona Tirante DA mm)
nodal D D 4"
(102
DD´
Biela

3,10"
(79 mm)

Figura 3.1-4: Dimensiones de los componentes del modelo de bielas y tirantes

113

<!-- p. 24 -->

Ejemplo 3.1: Ménsula en una columna

3.9 Paso 9: Detallar la armadura

En la Figura (3.1-5) se ilustran los detalles de las armaduras.

Placa de apoyo
12 x 6"
(305 mm x 52 mm)

Perfil de acero 4 barras principales
31"2 x 31"2 x 1"2 #4 (#13 mm)
soldadas al perfil de acero
1,6" 2" 1"
A A 3 estribos #3 (#10 mm)
a 3,5" (89 mm)
mm) 9"
3 barras #4 mm) (457 20"
2 estribos #3 a 2" 18" 9" (508

Nota: No se ilustra la armadura
9" 14" de la columna
(229 mm) (356 mm)

4 barras principales #4 (#13 mm)

14"

9" 14"
(229 mm) (356 mm)

Corte A-A

Figura 3.1-5: Detalles de las armaduras

114

<!-- p. 25 -->

Ejemplo 3.1: Ménsula en una columna

4 Resumen

Se presenta el diseño de una ménsula. Este diseño se completó usando el Apéndice A de
ACI 318-02 "Modelos de Bielas y Tirantes" y la Sección 11.9 de ACI 318-02 "Requisitos
Especiales para Ménsulas y Cartelas".
Los principales pasos del diseño consisten en definir la región D y las fuerzas de borde que
actúan sobre dicha región, seleccionar un modelo de bielas y tirantes que soporte las
fuerzas de borde de la región D, resolver el modelo de bielas y tirantes para hallar las
fuerzas en los miembros, disponer armadura que conforme los tirantes de acero,
dimensionar las bielas y nodos, y proveer armadura distribuida para limitar la fisuración y
lograr ductilidad.
En este ejemplo la totalidad de la ménsula constituye la región D, para cuyo diseño se
utilizó un modelo de bielas y tirantes sencillo.
Esto se debe a que existen discontinuidades estáticas, es decir, fuerzas concentradas, y
discontinuidades geométricas a una distancia menor que una altura flexional de la sección
de la ménsula a cada lado de la discontinuidad. Para el diseño se utilizó un modelo de
bielas y tirantes sencillo. Este modelo de bielas y tirantes dio por resultado el uso de una
capa de 4 barras #4 (#13 mm) para el tirante principal. Este tirante requiere suficiente
anclaje para garantizar que pueda soportar la fuerza requerida sin que se produzcan fallas
de anclaje. Esto se logró soldando todas las barras principales a un perfil de acero
estructural.

Referencias

ACI 318-02: Building Code Requirements for Reinforced Concrete and Commentary. ACI
Committee 318, American Concrete Institute, Detroit, Michigan, 2002, 443 pp.

115

<!-- p. 26 -->

Ejemplo 3.1: Ménsula en una columna

116

<!-- p. 27 -->

Ejemplo 3.2: Ménsula doble

Tjen N. Tjhin

Daniel A. Kuchma

Sinopsis

Se diseñó una ménsula doble que se proyecta a partir de una columna interior usando el
método de bielas y tirantes de acuerdo con el Apéndice A de ACI 318-02. La ménsula
transfiere las fuerzas de reacción de una viga premoldeada, Vu, igual a 61,8 kips (275 kN)
actuando en ambos lados a una distancia de 6 in. (152 mm) a partir de la cara de la
columna. Para tomar en cuenta las deformaciones por fluencia lenta y retracción, se asume
que a cada lado de la parte superior de la ménsula se desarrolla una fuerza horizontal
factoreada, Nuc, igual a 14,3 kips (63,6 kN). La columna es cuadrada, de 14 in. (356 mm)
de lado. La columna superior soporta una carga factoreada de compresión axial, Pu, igual a
275 kips (1223 kN). La resistencia a la compresión del hormigón, fc', y la resistencia a la
fluencia de las armaduras, fy, se tomaron como 4 ksi (27,6 MPa) y 60 ksi (414 MPa),
respectivamente. Se considera hormigón de peso normal.
En la Figura (3.2-2) se muestran las dimensiones seleccionadas, incluyendo las placas de
apoyo. La relación longitud de corte / profundidad, a/d, es igual a 0,38. Para el diseño se
utilizó el modelo de bielas y tirantes sencillo ilustrado en la Figura (3.2-3). La armadura
principal del tirante dispuesta es de 7 barras #4 (#13 mm). El anclaje de estas barras se
logra soldando cada extremo de las barras a un perfil de acero estructural de 4 in. x 4 in. x
½ in. (102 mm x 102 mm x 13 mm). En la Figura (3.2-5) se indican los detalles de las
armaduras.

Tjen N. Tjhin es candidato al doctorado en el Departamento de Ingeniería Civil y
Ambiental de la Universidad de Illinois en Urbana-Champaign. Sus investigaciones
abarcan el análisis no lineal y el diseño de estructuras de hormigón.

Daniel (Dan) A. Kuchma es Profesor Adjunto de Ingeniería Civil y Ambiental de la
Universidad de Illinois en Urbana-Champaign. Es miembro del Subcomité ACI 318E,
Corte y Torsión, y también del Comité conjunto ACI-ASCE 445, Corte y Torsión y su
Subcomité 445-A, Bielas y Tirantes.

<!-- p. 28 -->

Ejemplo 3.2: Ménsula doble

1 Geometría y cargas

En la Figura (3.2-1) se ilustran la geometría y las cargas de la ménsula a diseñar.

Pu = 275 kips (1223 kN)

Vu = 61,8 kips Vu = 61,8 kips
(275 kN)
placa de apoyo
6" (152 mm) 6"
Nuc= 14,3 kips Nuc= 14,3 kips
(63,6 kN)

14"
A A =b

14"
14" Corte A-A
(356 mm)

Figura 3.2-1: Geometría y cargas de la ménsula

Resistencias de los materiales:
fc' = 4 ksi (27,6 MPa) (hormigón de peso normal)
fy = 60 ksi (414 MPa)

118

<!-- p. 29 -->

Ejemplo 3.2: Ménsula doble

2 Procedimiento de diseño

La totalidad de la ménsula constituye una región D debido a que presenta cambios abruptos
en su geometría y está próxima a fuerzas concentradas. La estructura se diseñará usando el
método de bielas y tirantes de acuerdo con el Apéndice A de ACI 318-02. El
procedimiento paso a paso es el siguiente:
− Paso 1: Determinar las dimensiones de la placa de apoyo.
− Paso 2: Seleccionar las dimensiones de la ménsula.
− Paso 3: Establecer el modelo de bielas y tirantes.
− Paso 4: Determinar las fuerzas requeridas en el reticulado.
− Paso 5: Seleccionar la armadura de los tirantes.
− Paso 6: Diseñar las zonas nodales y verificar los anclajes.
− Paso 7: Verificar las bielas.
− Paso 8: Calcular la armadura mínima requerida para limitar la fisuración.
− Paso 9: Detallar la armadura.

Debido a que la geometría y las cargas son simétricas respecto a un eje vertical que pasa
por el baricentro de la columna sólo será necesario considerar la mitad de la ménsula. Aún
así en casi todas las figuras mostraremos la totalidad de la ménsula para su mejor
comprensión.

3 Cálculos

3.1 Paso 1: Determinar las dimensiones de la placa de apoyo

La zona nodal debajo de la placa de apoyo constituye un nodo solicitado por compresión y
tracción (CCT). La resistencia efectiva a la compresión de este nodo está limitada a
f cu = 0,85β n f c´ [ACI Sección A.5.2 ec. (A-8)]
\= 0,85(0,80)(4000) = 2720psi

Seleccionamos una placa de apoyo de 12 in. x 6 in. (305 mm x 152 mm). La superficie de
la placa de apoyo es 12 x 6 = 72 in.2 (46.452 mm2). La tensión de apoyo es 61,8 (1000)/72
\= 858 psi (5,92 MPa). Como este valor es menor que la tensión de apoyo límite, es decir,
φfcu = 0,75 (2720) = 2040 psi (14,07 MPa), las dimensiones de la placa de apoyo
seleccionada son adecuadas.

119

<!-- p. 30 -->

Ejemplo 3.2: Ménsula doble

3.2 Paso 2: Seleccionar las dimensiones de la ménsula

Para poder utilizar el Apéndice A de ACI, la Sección 11.9.1 del código requiere una
relación longitud de corte/profundidad, a/d, menor que 2. Además, la Sección 11.9.2 de
ACI requiere que la profundidad en la parte exterior del área de apoyo sea al menos 0,5d.
Por lo tanto seleccionamos una profundidad de 18 in. (457 mm) en la cara de la columna y
una profundidad de 10 in. (254 mm) en el extremo libre de la ménsula. La Figura (3.2-2)
resume las dimensiones seleccionadas para la ménsula.

12" placa de apoyo (típ.)
3" 6" 3" 12" x 6"
(305 mm x 152 mm)

mm)
mm) 10" (254
(457
mm) 18" 8"
(203

12" 14" 12"
(305 mm) (356 mm)

Figura 3.2-2: Dimensiones seleccionadas para la ménsula

3.3 Paso 3: Establecer el modelo de bielas y tirantes

Con el objeto de considerar las excentricidades de las cargas y las tolerancias de
fabricación, la posición de la reacción, Vu, se traslada 1 in. desde el centro de la placa de
apoyo hacia el borde exterior de la ménsula. Por lo tanto, la nueva posición de Vu con
respecto a la cara de la columna es 3 + 6/2 + 1 = 7 in.
La Figura (3.2-3) ilustra la geometría del modelo de bielas y tirantes supuesto. Se asume
que el tirante AA' está ubicado a 2 in. de la parte superior de la ménsula, considerando dos
capas de barras y un recubrimiento de hormigón de aproximadamente 1 in. Por lo tanto,
d = 18 − 2 = 16in. (406mm) [ACI Sección 11.9.1]

Se asume que la totalidad de la biela BB' está ubicada sobre la recta horizontal que
atraviesa el extremo inclinado de la ménsula
120

<!-- p. 31 -->

Ejemplo 3.2: Ménsula doble

Como se ilustra en la Figura (3.2-3), la carga axial de la columna, Pu, se resuelve en dos
cargas paralelas cuyas rectas de acción coinciden con las bielas CB y C'B'. La posición del
eje de la biela CB se puede hallar calculando su ancho de biela, ws. Este ancho se puede
obtener como
Fu,CB
w s = [ACI Secciones A.3.1 y A.2.6] (3.2-1)
φf cu b

donde Fu,CB es la fuerza de compresión requerida en la biela CB, y b = 14 in. es la
dimensión fuera del plano de la ménsula. La fuerza en la biela CB es Fu,CB = 275/2 + 61,8
\= 199,3 kips. Debido a que la zona nodal B constituye un nodo totalmente comprimido
(CCC) y que la biela CB es de tipo prismática, la resistencia efectiva a la compresión, fcu,
es igual a
f cu = 0,85β n f c´ [ACI Sección A.3.2 ec. (A-3)]
\= 0,85(1,0)(4000) = 3400psi

Reemplazando estos valores en la ecuación (3.2-1) se obtiene ws = 5,58 in. (142 mm).
De esta manera queda corregida la geometría del modelo de bielas y tirantes.

Pu = 137,5 kips Pu = 137,5 kips
(612 kN)

D D´
Vu = 61,8 kips Vu = 61,8 kips Resultante
(275 kN)
0,46" 7"
N uc= 14,3 kips Nuc= 14,3 kips
2" 54,1 k (63,6 kN)
A (241 kN) A´
k k k 16" mm) 73,5 = k 73,5kN) d (406 137,5 137,5 57,2° (327
39,8 k
B B' 177 kN
k k
199,3 199,3

C C´

199,3 kips 199,3 kips (887 kN)
φfcu φfcu

w s= 5,58" ws = 5,58" (142 mm)

Figura 3.2-3: Modelo de bielas y tirantes seleccionado

121

<!-- p. 32 -->

Ejemplo 3.2: Ménsula doble

3.4 Paso 4: Determinar las fuerzas requeridas en el reticulado

Las fuerzas requeridas en todos los miembros del reticulado se determinan en base a
consideraciones estáticas; estas fuerzas se resumen en la Tabla (3.2-1). Un signo positivo
(+) indica que el miembro está traccionado; un signo negativo (-) indica que el miembro
está comprimido.

Tabla 3.2-1: Fuerzas en el reticulado

Miembro AA' AB = A'B' BB' CB = C'B' BD = B'D'
Fuerza (kips) +54,1 -73,5 -39,8 -199,3 -137,5
(+241 kN) (-327 kN) (-177 kN) (-887 kN) (-612 kN)

3.5 Paso 5: Seleccionar la armadura de los tirantes

La sección de armadura requerida para el tirante AA' es
Fu,AA´ 54,1 2 = = 1,20in. [ACI Secciones A.2.6 y A.4.1]
φf y 0,75(60)

Además, la sección de armadura provista debe ser de al menos
f c´ 0,04(4) 2 0,04 bd = (14)(16) = 0,60in. [ACI Sección 11.9.5]
f y 60
Adoptamos 6 barras #4 (#13 mm), Ast = 6 (0,20) = 1,20 in.2 (774 mm2). Estas barras se
disponen en dos capas como se ilustra en la Figura (3.2-5).

3.6 Paso 6: Diseñar las zonas nodales y verificar los anclajes

El ancho ws de la zona nodal B ya fue determinado en la Sección 3.3 de manera de
satisfacer la tensión límite en dicha zona nodal. Por lo tanto en esta sección sólo
verificaremos la zona nodal A.
Para satisfacer la tensión límite en la zona nodal A es necesario que la profundidad efectiva
de hormigón para la armadura del tirante, wt, sea al menos igual a
Fu,AA´ 54,1(1000) = = 1,89in. (48mm) [ACI Sec. A.2.6 y A.5.1]
φf cu b 2040(14)

Como se puede ver en la Figura (3.2-4) este límite se satisface fácilmente ya que la zona
nodal disponible es 2 (2) = 4 in. (102 mm).
Para anclar el tirante AA' soldar las 6 barras #4 a un perfil de acero de 4 in. x 4 in. x ½ in.
(102 mm x 102 mm x 13 mm). En la Figura (3.2-5) se indican los detalles.
122

<!-- p. 33 -->

Ejemplo 3.2: Ménsula doble

3.7 Paso 7: Verificar las bielas

La biela AB se verificará en base a las dimensiones determinadas por las zonas nodales A
y B. Las demás bielas se verificarán calculando los anchos de las mismas y verificando si
cabrán en el espacio disponible.
ACI define la resistencia nominal de la biela AB como
Fns = f cu A c [ACI Sección A.3.1 ec. (A-2)]

donde
f cu = 0,85β s f c´ [ACI Sección A.3.2 ec. (A-3)]
\= 0,85(0,75)(4000) = 2550psi

y Ac es la menor de las áreas en los extremos de la biela. De la Figura (3.2-4), Ac = 14
(4,88) = 68,32 in.2. Por lo tanto, Fns = 2550 (68,32)/1000 = 174 kips. De la Tabla 3.2-1, la
carga factoreada de la biela AB es 73,5 kips (327 kN). Debido a que este valor es menor
que el límite, es decir, φFns = 0,75 (174) = 131 kips (583 kN), la biela AB resulta adecuada.
Como se ha asumido βs = 0,75 se colocará armadura mínima; los cálculos se incluyen en la
sección siguiente.

l b= 6,5" (165 mm)
Zona
nodal A
A Tirante AA'
Perfil de acero wt = 4" (102 mm)
1
4" x 4" x 2" Biela Zona nodal
extendida A =A'B'AB BD =B'D' 4,88"mm) Biela (124

Zona
nodal B
Tirante BB' 2" mm)
B (51
CB =C'B'
Biela

5,58"
(142 mm)

Figura 3.2-4: Dimensiones de los componentes del modelo de bielas y tirantes

123

<!-- p. 34 -->

Ejemplo 3.2: Ménsula doble

La tensión de la biela horizontal BB' está limitada a

´ φf cu = 0,75 ( 0,85β s f c ) [ACI Secciones A.2.6 y A.3.2)]
\= 0,75 [ 0,85(1,0)(4000) ] = 2550psi

Por lo tanto, el ancho requerido para la biela BB' es
Fu,BB´ 39,8(1000) = = 1,11in. [ACI Secciones A.2.6 y A.3.1)]
φf cu b 2550(14)

La tensión de la biela vertical BD está limitada a

´ φf cu = 0,75 ( 0,85β s f c ) [ACI Secciones A.2.6 y A.3.2)]
\= 0,75 [ 0,85(0,6)(4000) ] = 1800psi

Por lo tanto, el ancho requerido para la biela BD es
Fu,BD 137,5(1000) = = 5,46in. [ACI Secciones A.2.6 y A.3.1)]
φf cu b 1800(14)

Adoptamos un ancho de 2 in. (51 mm) para la biela BB', y fijamos el ancho de la biela BD
igual al ancho de la biela CB. El ancho requerido para la biela CB ya fue calculado en la
Sección 3.2, es decir 5,58 in. (142 mm).
Como se ilustra en la Figura (3.2-4), todos los anchos caben dentro de los límites de la
región de la ménsula. En consecuencia esta solución es aceptable.

3.8 Paso 8: Calcular la armadura mínima requerida para limitar la fisuración

La Sección 11.9.4 de ACI requiere zunchos o estribos cerrados paralelos a la armadura
requerida para el tirante AA', uniformemente distribuidos en 2/3 de la profundidad efectiva
adyacente al atirante CB, es decir, 2/3 (16) = 10,7 in. Adoptamos 10,5 in. La sección de
estos estribos debe ser mayor que
A h = 0,5 ( A st − A n ) [ACI Sección 11.9.4]

donde An es la sección de armadura que resiste la fuerza de tracción Nuc y Ast ≡ As según la
Sección 11.9 de ACI. Por lo tanto, la sección mínima requerida es

124

<!-- p. 35 -->

Ejemplo 3.2: Ménsula doble

 N uc   14,3  2 0,5 ( A st − A n ) = 0,5  A st −  = 0,5  1,40 −  = 0,56in.  0,85(60)   φf y  
Intentamos con 3 estribos cerrados #3, Av = 3 (2) (0,11) = 0,66 in.2, con una separación
media de 10,5/3 = 3,5 in.
Como para calcular la resistencia de la biela AB usamos βs = 0,75 la armadura mínima
provista también debe satisfacer

sin γ i ≥ 0,0030 [ACI Sección A.3.3.1 ec. (A-4)] ∑ A si bs i
donde γi es el ángulo formado por el eje de la armadura mínima y el eje de la biela. De
acuerdo con la Sección A.3.3.2 de ACI γi debe ser mayor que 40º porque solamente se
provee armadura horizontal. En base a la armadura provista,

sin γ i = sin57,2º = 0,0038 > 0,0030 ∑ A si 2(0,11) bs i 14(3,5)

Como esta cantidad de armadura satisface ambos requisitos, disponemos 3 estribos
cerrados #3 (#10 mm) con una separación de 3,5 in. (89 mm), distribuidos en una
profundidad de 10,5 in. (267 mm) a partir del tirante AA'.

125

<!-- p. 36 -->

Ejemplo 3.2: Ménsula doble

3.9 Paso 9: Detallar la armadura

En la Figura (3.2-5) se ilustran los detalles de las armaduras.

Placa de apoyo
12" x 6"
(305 mm x 152 mm)
Perfil de acero 3 estribos #3 (#10 mm)
1 @ 3,5" (89mm) 4" x 4" x 2"
4 barras #4 (#13 mm)
1,5" 2 barras #4
A A
mm) 10"
1,5"
(457 3 barras #4
18" 8"

12" 14" Nota: No se ilustra la armadura
(305 mm) (356 mm) de la columna

2 capas de 2 barras #4

2 barras #4 (13 mm)

14"

12" 14" 12"
(305 mm) (356 mm)

Corte A-A

Figura 3.2-5: Detalles de las armaduras

126

<!-- p. 37 -->

Ejemplo 3.2: Ménsula doble

4 Resumen

Se presenta el diseño de una ménsula doble. Este diseño se completó usando el Apéndice A
de ACI 318-02 "Modelos de Bielas y Tirantes" y la Sección 11.9 de ACI 318-02
"Requisitos Especiales para Ménsulas y Cartelas".
Los principales pasos del diseño consisten en definir la región D y las fuerzas de borde que
actúan sobre dicha región, seleccionar un modelo de bielas y tirantes que soporte las
fuerzas de borde de la región D, resolver el modelo de bielas y tirantes para hallar las
fuerzas en los miembros, disponer armadura que conforme los tirantes de acero,
dimensionar las bielas y nodos, y proveer armadura distribuida para limitar la fisuración y
lograr ductilidad.
La totalidad de la ménsula constituye la región D debido a que existen discontinuidades
estáticas, es decir, fuerzas concentradas, y discontinuidades geométricas a una distancia
menor que una altura flexional de la ménsula a cada lado de la discontinuidad. Para el
diseño se utilizó un modelo de bielas y tirantes sencillo. Este modelo de bielas y tirantes
dio por resultado el uso de 6 barras #4 (#13 mm) para el tirante principal. Se prestó
particular atención al anclaje del tirante principal a fin de garantizar que pueda transferir la
fuerza requerida sin que se produzcan fallas de anclaje. Para satisfacer los requisitos de
anclaje todas las barras principales se soldaron a un perfil de acero dispuesto en cada uno
de los extremos.

Referencias

ACI 318-02: Building Code Requirements for Reinforced Concrete and Commentary. ACI
Committee 318, American Concrete Institute, Detroit, Michigan, 2002, 443 pp.

127

<!-- p. 38 -->

Ejemplo 3.2: Ménsula doble

128
