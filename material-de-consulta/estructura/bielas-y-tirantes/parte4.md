---
type: libro
title: "Parte4"
author: "lauri"
categoria: "ESTRUCTURA"
paginas: 28
extraccion: "texto"
fuente: "local:E:/MATERIAL DE CONSULTA/ESTRUCTURA/BIELAS Y TIRANTES/Parte4.pdf"
convertido: 2026-10-16
---

# Parte4

> Texto extraído de `ESTRUCTURA\BIELAS Y TIRANTES\Parte4.pdf` (28 páginas, texto). El PDF original está en el disco E: (MATERIAL DE CONSULTA); `<!-- p. N -->` marca el inicio de cada página.

<!-- p. 1 -->

Parte 4

Ejemplos

63

<!-- p. 2 -->

:

64

<!-- p. 3 -->

Ejemplo 1a: Diseño de una viga de gran altura
de acuerdo con ACI 318-02

Claudia M. Uribe

Sergio M. Alcocer

Sinopsis

Se diseñó una viga de gran altura cargada con dos cargas concentradas en su parte superior,
de acuerdo con el Apéndice A del Código ACI 318-02. El análisis y diseño usando modelo
de bielas y tirantes se realizaron de manera eficiente y directa. La metodología de bielas y
tirantes proporciona un marco que permite comprender y evaluar el flujo de fuerzas y los
mecanismos resistentes. Además, constituye una valiosa herramienta para lograr un
correcto detallado de los miembros dúctiles de hormigón.

Claudia M. Uribe fue investigador asistente en el Área de Ingeniería Estructural y
Geotecnia en el Centro Nacional para la Prevención de Desastres (CENAPRED). Posee un
B.Sc. de EAFIT, Medellín, Colombia y un M.Sc. de la Universidad Autónoma de México
(UNAM). Sus investigaciones incluyen el comportamiento sísmico de las estructuras de
hormigón armado.

Sergio M. Alcocer, FACI, es profesor e investigador en el Instituto de Ingeniería de la
UNAM y Director de Investigaciones en el CENAPRED. Es miembro de los Comités ACI
318, Requisitos del Código de Construcción, y 374, Diseño Sísmico de Edificios de
Hormigón; también es miembro del Comité conjunto ACI-ASCE 352, Juntas y Uniones en
Estructuras de Hormigón Monolítico. Preside el Comité sobre Normas para Mampostería y
es miembro del comité sobre Normas para Hormigón Armado del Código de Construcción
de la Ciudad de México. Sus investigaciones incluyen el diseño sismorresistente de
estructuras de mampostería y hormigón.

65

<!-- p. 4 -->

Ejemplo 1a: Diseño de una viga de gran altura de acuerdo con ACI 318-02

1 Planteo del problema

Diseñar la viga simplemente apoyada cargada con dos cargas concentradas factoreadas de
134k x 1,6 = 214k (952 kN) cada una en un tramo libre de 12 ft. (3,66 m), como se ilustra
en la Figura (1-1).
La viga tiene un ancho de 14 in. (356 mm) y una altura total de 48 in. (1,22 m). La longitud
de la placa de apoyo bajo cada una de las cargas concentradas es de 16 in. (406 mm) y su
ancho es el mismo de la viga, es decir, 14 in. (356 mm).
Usar fc' = 4000 psi (27,6 MPa) y fy = 60.000 psi (414 MPa). Despreciar el peso propio de la
viga.

134 k (596 kN) 134 k (596 kN) cargas de servicio

4´-0" (1,22 m) 4´-0" (1,22 m) Corte

48"
(1,22 m)

16" 12´0" (3,66 m) 16" 14"
(406 mm) (406 mm) (356 mm)

P = 134k × 1,6 = 214k (952kN)
b = 14in.(356mm)
h = 48in.(1,22m)
f c´ = 4000psi (27,6MPa)
f y = 60.000psi(414MPa)

Figura 1-1: Miembro y cargas

66

<!-- p. 5 -->

Ejemplo 1a: Diseño de una viga de gran altura de acuerdo con ACI 318-02

2 Parámetros del modelo de bielas y tirantes

2.1 Resistencia a la compresión del hormigón (Secciones A.3.2 y A.5.2 de ACI 318-
\2002)

fcu = 0,85β2fc' β2 = factor que toma en cuenta los efectos de la fisuración y la
armadura de confinamiento sobre la resistencia efectiva a la
compresión de una biela, βs, o una zona nodal, βn
fc' = resistencia a la compresión especificada del hormigón
fcu = 0,85 x 4000 x β2 = 3400 β2, psi (23,4 β2; MPa) (1-1)

En este ejemplo los valores de β2 son
Bielas, βs (Sección A.3.2 de ACI 318-2002):
a. Bielas en zonas no fisuradas y ubicadas de manera tal que la sección
transversal a la mitad de la biela es igual a la sección en los nodos, tales
como la zona comprimida de una viga (a los fines de este ejemplo, bielas
tipo a) 1,00
c. Bielas ubicadas de manera tal que el ancho de la biela en su parte media es o
puede ser mayor que el ancho en los nodos, con armadura que satisface
A.3.3 (a los fines de este ejemplo, bielas tipo c) 0,75

Zonas nodales, βn (Sección A.5.2 de ACI 318-2002):
e. Zonas nodales limitadas por bielas o áreas de apoyo, o ambas (Tipo CCC) 1,00
f. Zonas nodales que anclan un tirante en una sola dirección (Tipo CCT) 0,80
g. Zonas nodales que anclan tirantes en más de una dirección (Tipo CTT) 0,60

Tabla 1-1: Resistencia del hormigón en bielas y zonas nodales

Bielas Zonas nodales
Tipo β2 = βs fcu, psi* (MPa) Tipo β2 = βn fcu, psi* (MPa)
a. Cordón no 1,0 3400 (23,4) e. CCC 1,0 3400 (23,4)
fisurado (prismática)
c. Biela inclinada 0,75 2550 (17,6) f. CCT 0,8 2720 (18,8)
(en forma de botella) g. CTT 0,6 2040 (14,1)
\* de la ecuación (1-1) en este ejemplo

67

<!-- p. 6 -->

Ejemplo 1a: Diseño de una viga de gran altura de acuerdo con ACI 318-02

2.2 Resistencia de bielas, tirantes y zonas nodales

Se deberá satisfacer la siguiente condición:
φFn ≥ Fu (Ec. A-1) Fu = fuerza en la biela o tirante, o fuerza que actúa en un nodo
debido a las cargas factoreadas
Fn = resistencia nominal de la biela
φ = factor de reducción de la resistencia (según 9.3.2.6); para
todos los elementos del reticulado, φ = 0,75

Resistencia de las bielas (Sección A.3)
Fns = fcuAc (Ec. A-2) Fns = resistencia nominal a la compresión del hormigón en una
biela
fcu = resistencia efectiva a la compresión
Ac = menor sección transversal efectiva de la biela

Resistencia de los tirantes (Sección A.4)
Debido a que el tirante está compuesto por armadura no pretensada:
Fnt = Astfy (Ec. A-6) Fnt = resistencia nominal de un tirante
Ast = sección de armadura no pretensada en un tirante
fy = resistencia a la fluencia especificada del tirante no
pretensado

Resistencia de las zonas nodales (Sección A.5)
Fnn = fcuAn (Ec. A-6) Fnn = resistencia nominal a la compresión de una zona nodal
fcu = resistencia efectiva a la compresión de una zona nodal
An = área de la cara de la zona nodal

68

<!-- p. 7 -->

Ejemplo 1a: Diseño de una viga de gran altura de acuerdo con ACI 318-02

3 Procedimiento de diseño mediante bielas y tirantes (Sección A.2 de
ACI 318-2002)

3.1 Diseño a flexión

Para desarrollar el modelo de bielas y tirantes es conveniente conocer el tamaño (altura)
del bloque de hormigón comprimido.
Suponiendo que se disponen dos capas de barras No. 8 para el momento positivo, la altura
efectiva sería:
d = h − recubrimiento − db estribo No.5 − db No.8 − ½ sv (1-2)
\= 48 in. − 1,5 in. − 0,625 in. − 1,0 in. − ½ in. = 44,4 in. (1,13 m)
donde sv es la separación vertical entre las dos capas de barras No. 8.

De acuerdo con la Sección R9.1 de ACI 318-2002
Mu ≤ φ Mn

V = 214 k V = 214 k (952 kN)

214 k 214 k

R=214 k 214 K
56" 48" 56"

V
Vmax = 214 k
(952 kN)

M

Mmax = 11 984 k in. (1354 kN m)

Figura 1-2: Diagramas de corte y momento flector

69

<!-- p. 8 -->

Ejemplo 1a: Diseño de una viga de gran altura de acuerdo con ACI 318-02

donde:
φ = factor de reducción de la resistencia. Para flexión, φ = 0,9 (Sección 9.3.2.1)
Mu = 11.984 k⋅in. (1354 kN m).
 a   A s f y 
M u = A s f y  d −  = A s f y  d − ´  (1-3)
 2   2 × 0,85f c b 

Por lo tanto,
 A s × 60.000psi  11.984 k⋅in ≤ 0,9As x 60.000 psi  44,4 − 
 2 × 0,85 × 4000psi × 14in. 
resolviendo para As, As ≥ 5,4 in.2 (3480 mm2), c = 8,5 in. (216 mm)

3.2 Modelo de bielas y tirantes

De 3.1: c (distancia entre la fibra extrema comprimida y el eje neutro) = 8,5 in (216 mm).
Para el modelo de bielas y tirantes intentar con una profundidad de biela horizontal (a)
igual a 10 in. (254 mm) (en la región de momento constante).
La Figura (1-3) muestra el modelo de bielas y tirantes propuesto.

V = 214k V = 214k

5
1 2
2 4 5

48 3 5 4 z = 39

6 54,32º 3
7 1 6 4

R

16 20 28 48 28 28 8

No. de identificcación del nodo bielas

No. de identificcación del elemento del reticulado tirantes

V = 214.000lb(952kN) b = 14in.(356mm)
R = 214.000lb(952kN) h = 48in.(1,22mm)
f c´ = 4000psi(27,6MPa) l b = 16in.(406mm)
f y = 60.000psi(414MPa) a = 10in.(254mm)

Figura 1-3: Modelo de bielas y tirantes propuesto (z = 39 in. [990 mm])

70

<!-- p. 9 -->

Ejemplo 1a: Diseño de una viga de gran altura de acuerdo con ACI 318-02

3.3 Resolución del reticulado

En la Figura (1-4) se ilustran las fuerzas en el reticulado calculadas en base a su geometría.

214k 214k

14,6" 16"

17,7" 154k 307k 10"
18,8"
263k 263k

214k
263k
263k

8,0"
154k 307k

214k 214k
16" 23,2"

Figura 1-4: Fuerzas en el reticulado

3.4 Verificación de las resistencias de las bielas y zonas nodales

La verificación de las resistencias de las bielas y zonas nodales se debería realizar
comparando el área de biela o zona nodal disponible con el área requerida. En este
ejemplo, debido a que el ancho de la viga y el ancho de las placas de apoyo y apoyos son
iguales (es decir, 14 in. ó 356 mm), la verificación se hará comparando el ancho de biela o
zona nodal disponible, wprob, con el requerido, wreq. Por lo tanto, para las bielas y nodos,
wreq. se calculará usando la Ecuación (1-4). Ver Figuras (1-5a) a (1-5d).
Fu Fu w req = = ´ (1-4)
φf cu b φ0,85β 2 f c b

Nodo 1

z = 17,89in.[454,4mm] 17,7"
3 α = 26,6º ; θ = 54,3º
263k z´= l b sin θ + w t cos θ =
z' 54,32° 16 sin54,3º + 8 cos54,3º = 17,7in. z
8" 154k
α Por lo tanto, para la biela 3
214k w prov = 17,7in.(450mm)
16"

Figura 1-5a: Nodo 1

71

<!-- p. 10 -->

Ejemplo 1a: Diseño de una viga de gran altura de acuerdo con ACI 318-02

Nodo 2

14,6"
Para la biela 1, wprov = 10 in. (254 mm) (del
α diseño a flexión) 154k
1 10" z' = 17,69 in. (449 mm)
54,32°
Por lo tanto,
263k 214k ancho de la zona nodal = 14,6 in. (371 mm)
3 17,7"

Figura 1-5b: Nodo 2

Nodo 3

18,8"
El ancho de 18,8 in. se obtiene de la 4
214k solución del Nodo 4 (Figura 1-5d).
263k
5
54,32°
154k 6 7 307k 8,0"

23,2"

Figura 1-5c: Nodo 3

Nodo 4

214k
z = 18,88in. [480mm]
16" α = 32º ; θ = 54,3º
α z´= l b sin θ + w t cos θ =
1 154k 307k 2 16" z 16 sin54,3º + 10 cos54,3º = 18,8in.
z'
Por lo tanto, para la biela 4
263k
w prov = 18,8in.(478mm) 4
54,32°

Figura 1-5d: Nodo 4

72

<!-- p. 11 -->

Ejemplo 1a: Diseño de una viga de gran altura de acuerdo con ACI 318-02

Biela 1 (cálculo ilustrativo)
Fu Fu 153.661w req = = ´ = = 4,3in.(109mm)
φf cu b w φ0,85β 2 f c b w 0,75 × 0,85 × 1,0 × 4000 × 14

donde
β2 = 1,0; se trata de una cuerda no fisurada, biela Tipo a, de la Tabla (1-1)
b = ancho del miembro = 14 in.
De acuerdo con la geometría de la zona nodal, ilustrada en la Figura (1-5b), se puede
proponer un ancho de 10,0 in. (254 mm) (wprov = 10 in.). Por lo tanto es adecuado.
La verificación de la resistencia de las demás bielas se indica en la Tabla (1-2) y para los
nodos en la Tabla (1-3) y la Figura (1-5).

Tabla 1-2: Verificación de la resistencia de las bielas

Elemento β2 1 θ2 Fuc3 wreq 4 wprov 5 Solución
Nodo √: Verifica propuesta
\# i - j (º) lb (kN) in. (mm) in. (mm)
1 2-4 1,00 0 153.661 (684) 4,3 (109) 10,0 (254) √
√ 10,0 (254)
2 4-5 1,00 0 307.323 (1367) 8,6 (219) 10,0 (254) √
√ 10,0 (254)
3 1-2 0,80 54,32 263.454 (1172) 9,2 (234) 17,7 (450) √
√ 17,7 (450)
4 3-4 0,80 54,32 263.454 (1172) 9,2 (234) 18,8 (478) √
√ 18,8 (478)

Notas: 1 De la Tabla 1-1
2 Del modelo de bielas y tirantes propuesto, Figura (1-3); β2 = βs
3 De la resolución del reticulado (Sección 3.3 y Figura (1-4) de este ejemplo)
4 Ancho requerido para las bielas (de la ecuación (1-4))
5 Ancho provisto para las bielas, considerando la geometría y las condiciones
de apoyo.

73

<!-- p. 12 -->

Ejemplo 1a: Diseño de una viga de gran altura de acuerdo con ACI 318-02

Tabla 1-3: Verificación de la resistencia de las zonas nodales

Nodo β21 Tipo2 Fuerza3 Fu4 wp req5 wp prov 6 Solución
√: Verifica
lb (kN) in. (mm) in. (mm) propuesta
1 0,8 CCT R 214.000 (952) 7,5 (190) 16,0 (406) √

S1-2 263.454 (1172) 9,2 (234) 17,7 (450) √

T1-3 153.661 (684) 5,4 (137) 8,0 (203) √

2 0,8 CCT S2-1 263.454 (1172) 9,2 (234) 17,7 (450) √

S2-4 153.661 (684) 5,4 (137) 10,0 (254) √

T2-3 214.000 (952) 7,5 (190) 54,0 (1372) √

3 0,6 CTTT S3-4 263.454 (1172) 12,3 (312) 18,8 (478) √

T3-2 214.000 (952) 10 (254) 54,0 (1372) √

T3-1 153.661 (684) 7,2 (182) 8,0 (203) √
Distribuc. T3-6 307.323 (1367) 14,3 (364) 8,0 (203) ×
de la
armadura
4 1,0 CCCC V 214.000 (952) 6,0 (152) 16,0 (406) √

S4-3 263.454 (1172) 7,4 (187) 18,8 (478) √

S4-2 153.661 (684) 4,3 (109) 10,0 (254) √

S4-5 307.323 (1367) 8,6 (219) 10,0 (254) √

Notas: 1 De la Tabla 1-1; β2 = βs
2 Del modelo de bielas y tirantes propuesto, Figura (1-3)
3 R = reacción; S = biela; T = tirante; V = carga concentrada
4 De la resolución del reticulado (Sección 3.3 y Figura (1-4) de este ejemplo)
4 Ancho requerido para los nodos (de la ecuación (1-4))
5 Ancho provisto para los nodos, considerando la geometría y las condiciones
de apoyo.

Verificación de la resistencia de apoyo en los puntos de carga y reacción

De la Figura (1-2), la carga última y las reacciones son
V = R = 214k (952kN)

Como la placa de carga es de 16 x 14 in., su área es
A A = 16 × 14in.2 (406 × 356mm 2 )
74

<!-- p. 13 -->

Ejemplo 1a: Diseño de una viga de gran altura de acuerdo con ACI 318-02

Por lo tanto, la tensión de compresión es igual a

 V 
σ A =  = 1274psi  ( 8,78MPa ) (1-5)
 φA A 
De acuerdo con la sección 2.1 de este ejemplo, se debe satisfacer que σA ≤ fu, es decir, σA
≤ φ 0,85 β2 fc'.
Para el nodo 4, tipo CCC,
1274 psi (8,78 MPa) ≤ φ 0,85 β2 fc' = φ 3400 psi = 2550 psi (17,6 MPa) (Verifica)
Para el nodo 1, tipo CCT,
1274 psi (8,78 MPa) ≤ φ 0,85 β2 fc' = φ 2720 psi = 2040 psi (14,1 MPa) (Verifica)

3.5 Armadura requerida en los tirantes

Una vez verificada la resistencia de las bielas y los nodos, se determina la cantidad de
armadura requerida en los tirantes.

Tabla 1-4: Requisitos de armadura

Elemento 1 2 θ Fut As req As prov Solución Nodo β2 (º) lb (kN) in.2 (mm2) in.2 (mm2) √: Verifica propuesta# i - j
5 2-3 --- 90 214.000 (952) 4,8 (3100) 4,96 (3200) √ 8 Estribos No. 5
@ 4 in.
6 1-3 --- 0 153.661 (684) 3,4 (2190) 4,74 (3060) √ As = 6 No. 8
7 3-6 --- 0 307.323 (1367) 6,8 (4390) 7,2 (4650) √ As = 8 No. 8 y
2 No. 6

Notas: 1 Sección de tirantes requerida (As = Fut/φfy); φ = 0,75
2 Sección de tirantes provista.
3 Para el tirante 7, para permitir su distribución se utilizaron barras No. 6 y No. 8
en vez de barras No. 10.

Tirante 6 (del nodo 1 al nodo 3)
De la Tabla (1-4)
As req = 3,4 in.2 (2190 mm2): Usar 6 barras No. 8 (As prov = 4,74 in.2 [3060 mm2])
en dos capas
Es necesario anclar las barras mediante ganchos, barras con cabeza, anclajes mecánicos o
desarrollo lineal de las barras (Sección A.4.3 de ACI 318-2002).
75

<!-- p. 14 -->

Ejemplo 1a: Diseño de una viga de gran altura de acuerdo con ACI 318-02

De la Sección 12.5.2 de ACI 318-2002, la longitud de anclaje de una barra terminada en
gancho a 90º es
0,02βλ f y
l dh = d b = 19in. (483 mm) para barras No. 8 (1-6)
f c´
donde β = 1; λ = 1; db = diámetro de la barra (en este caso, db = 1 in. [25,4 mm])
ldh está modificado por el factor (a) de la Sección 12.5.3
Sección 12.5.3.a: factor = 0,7 debido a que se provee un recubrimiento de hormigón de
espesor ≥ 2½ in. (64 mm) en la dirección perpendicular al plano del gancho, y un
recubrimiento de hormigón de espesor ≥ 2 in. (51 mm) en la dirección de la extensión de la
barra.
Por lo tanto, ldh = 19 in. x 0,7 = 13,3 in. (338 mm) para las barras No. 8.
El anclaje disponible es (Figura 1-6):
ldh disponible = longitud de la zona nodal extendida − recubrimiento − db de la armadura
horizontal de corte
ldh disponible = 16 + 4 / tan 54,3º − 1,5 − 0,625 = 16,7 in. (425 mm)
ldh disponible > ldh (Verifica)

54,32°

8"
α 4"

16"
4 / tan 54,32°

Figura 1-6: Longitud de anclaje disponible en la zona nodal extendida en el Nodo 1

Tirante 7 (del nodo 3 al nodo 6)
De la Tabla (1-4)
As req = 6,8 in.2 (4390 mm2)
Es evidente que no alcanza con extender las 6 barras No. 8 del tirante 6. Por lo tanto, se
requiere una sección adicional de armadura, la cual se calcula como 6,8 in.2 − 4,74 in.2 =
2,06 in.2. Usar ocho barras No. 8 y dos barras No. 6 (As prov = 7,2 in.2 [4650 mm2]).
Es conveniente distribuir la armadura uniformemente en un área de hormigón al menos
igual a la fuerza de tracción en el tirante dividida por la tensión de compresión limitante
aplicable para el nodo. En este ejemplo,

76

<!-- p. 15 -->

Ejemplo 1a: Diseño de una viga de gran altura de acuerdo con ACI 318-02

Fu tirante7 307.323 2 2 A = = = 151in. (97.420mm ) (1-7)
f cu 2040
w = 151/ b = 11in. (279mm) (1-8)

Por lo tanto, distribuir las ocho barras No. 8 y las dos barras No. 6 verticalmente en una
altura de 11 in. (279 mm).
Para anclar las barras No. 6 usar la tabla de la Sección 12.2.2 de ACI 318-2002
f y αβλ d b
l d = (1-9)
25 f c´
60.000 × 1,0 × 1,0 × 1,0 × 0,75
l d = = 28,5in. (724mm)
25 4000

Se asumió que:
α = 1,0 (no se cuelan más de 12 in. (305 mm) debajo de las barras),
β = 1,0 (armadura sin recubrimiento epoxi), y
λ = 1,0 (hormigón de peso normal).
El anclaje disponible es:
ldh disponible = distancia entre la sección crítica y el borde de la viga − recubrimiento −
db de la armadura horizontal de corte, Figura (1-3)
ldh disponible = 36 in. − 1,5 in. − 0,625 in. = 33,9 in. (861 mm)
ldh disponible > ldh (Verifica)
Por lo tanto, colocar las barras No. 8 con una separación (vertical) de 3 in. (76 mm) y con
ld = 34 in. (864 mm) (para mejorar el confinamiento en la zona nodal). Las barras rectas
No. 6 se extienden en la totalidad de la longitud de la viga.

Tirante 5 (del nodo 2 al nodo 3)
De la Tabla (1-4)
As req = 4,8 in.2 (3100 mm2)
De la Sección 11.8.4 de ACI 318-2002
 d /5 = 8,9in.(226mm) (controles)
s ≤
12in.(305mm)
Usar ocho estribos cerrados No. 5 (As prov = 4,96 in.2 [3200 mm2]). Usar dos barras No. 5
dentro de las esquinas superiores continuas a lo largo de la viga. Estos estribos deberán
tener codos a 135 grados alternando alrededor de una u otra barra. Colocar los estribos con
una separación de 4 in. (102 mm).
77

<!-- p. 16 -->

Ejemplo 1a: Diseño de una viga de gran altura de acuerdo con ACI 318-02

3.6 Armadura para las bielas en forma de botella 3 y 4

En la Sección A.3.3 se especifica que las bielas 3 y 4 deben ser cruzadas por capas o
mallas de armadura paralelas al plano del miembro.
Además, debido a que el ancho del alma es mayor que 8 in. (203 mm), es conveniente
colocar una capa o malla de armadura próxima a cada cara.
De la ecuación (A-4)

sin γ i = ρ vi sin γ i ≥ 0,003 (Ec. A-4) ∑ A si bs i

donde
Asi = sección total de armadura con separación si en una capa de armadura con barras
formando un ángulo γi respecto del eje de la biela.
Supongamos que sólo se coloca armadura horizontal y que γi = 54,32º
2A si 0,003 = (1-10)
bs i sin54,3º

asi ≥ 0,0259 si Pero de la Sección 11.8.5 de ACI 318-2002
 d /5 = 8,9in. (226mm) (controles)
s ≤
12in. (305mm)
Supongamos s = 7 in. (178 mm), asvh ≥ 0,18 in.2 (116 mm2). Usar barras No. 4 con
separación de 7 in. (178 mm) en cada cara.

4 Disposición de la armadura

En la Figura 1-7 se ilustra la disposición final de la armadura.

10 No. 4 @ 7 (178 mm)

6

@ 2 2 18
(51 mm) 5 2 8
2 12 14
6 8 No. 5 @ 4 No. 5 @ 6 8 No. 8 2 No. 6 2 12
(102 mm) (152 mm)
Dimensiones en in.; 1 in. = 25,4 mm

Figura 1-7: Disposición de la armadura
78

<!-- p. 17 -->

Ejemplo 1a: Diseño de una viga de gran altura de acuerdo con ACI 318-02

5 Modelos opcionales

El modelo de bielas y tirantes resuelto (ver Figura 1-3) es uno entre varios modelos que se
podrían haber seleccionado. En el modelo supuesto se consideró que la transferencia de
cargas se lograba mediante la formación de un reticulado compuesto por dos bielas
inclinadas próximas a cada apoyo. Este modelo se seleccionó por su sencillez y porque
requería estribos a lo largo de la longitud de corte, lo cual se consideró un detalle de
seguridad.
Opcionalmente se podrían haber seleccionado otros dos modelos de bielas y tirantes. En la
Figura 1-8 se presenta el modelo de bielas y tirantes recomendado en las Recomendaciones
FIP 1999. En este modelo parte de la carga se transfiere directamente de la placa de carga
al apoyo a través de una biela inclinada. El resto es resistido por los estribos mediante un
reticulado simple, similar al supuesto en la resolución de este ejemplo. Las
Recomendaciones FIP consideran que se pueden superponer ambos mecanismos portantes
(es decir, biela directa y mecanismo reticulado). La distribución de la carga entre estos dos
mecanismos depende de la relación entre la longitud de corte y el brazo de palanca interno,
y se determina por medio de ecuaciones que han sido verificadas mediante resultados de
ensayos.

V=214k V=214k
F2 F1 16

7,7 6

36.6 38
48

49,92° 49,92°

44,36° 4 3,7

56
bielas
R R
tirantes
16
Dimensiones en in.; 1 in. = 25,4 mm
Figura 1-8: Modelo de acuerdo con FIP 1999

Otro modelo de bielas y tirantes que se podría haber seleccionado considera que en cada
extremo de la viga la carga es transferida al apoyo por medio de una sola biela inclinada
(Figura 1-9). Este modelo no requiere estribos verticales a lo largo de la longitud de corte
(es decir, entre la placa de carga y el apoyo de la viga) para mantener el equilibrio. En
ausencia de estribos es dable esperar grandes fisuras con cargas muy por debajo de la carga
última y, por lo tanto, no se recomienda utilizar este modelo para el diseño. Sin embargo,
se podría argumentar a favor de un modelo similar a este, siempre que se disponga
armadura vertical mínima de estribos.

79

<!-- p. 18 -->

Ejemplo 1a: Diseño de una viga de gran altura de acuerdo con ACI 318-02

V = 214k V = 214k

5

39
48

34,85°

4

56 48 56
R bielas R

tirantes
Dimensiones en in.; 1 in. = 25,4 mm
Figura 1-9: Carga transferida directamente al apoyo

6 Comentarios finales

El análisis del modelo de bielas y tirantes seleccionado resultó rápido y directo, y el diseño
y verificación de la resistencia se efectuó con sencillez. Se halló que la metodología de
bielas y tirantes proporciona un marco que permite comprender y evaluar el flujo de
fuerzas y los mecanismos resistentes. Además, se demostró que constituye una valiosa
herramienta para lograr un correcto detallado de los miembros dúctiles de hormigón.

Referencias

ACI 318-2002: Building Code Requirements for Reinforced Concrete and Commentary.
ACI Committee 318, American Concrete Institute, Farmington Hills, Michigan, 2002.
FIP Recommendations (1999): Practical Design of Structural Concrete.
FIP-Commission 3 "Practical Design", Setiembre 1996.
Publ. SETO, Londres, Setiembre 1999. (Distribuido por: fib, Lausana)

Agradecimientos

Los autores agradecen la participación y contribución del Sr. Leonardo Flores en la
preparación de la versión final de este trabajo.

80

<!-- p. 19 -->

Ejemplo 1b: Diseño alternativo para la viga no esbelta
(viga de gran altura)

Tjen N. Tjhin

Daniel A. Kuchma

Sinopsis

Se diseñó una viga de 20 ft (6,10 m) de longitud empleando el método de bielas y tirantes
de acuerdo con el Apéndice A de ACI 318-02. LA viga tiene 20 in. (508 mm) de ancho y
80 in. (2032 mm) de altura, y soporta dos cargas concentradas factoreadas, Vu, de 360 kips
(1601 kN) cada una. En todos los puntos de carga y apoyo se dispusieron placas de apoyo
de 18 in. x 20 in. (457 mm x 508 mm). Para el diseño se despreció el peso propio. La
resistencia a la compresión del hormigón, fc', y la resistencia a la fluencia del acero, fy, se
tomaron como 4 ksi (27,6 MPa) y 60 ksi (414 MPa), respectivamente.
Para el diseño se utilizó el modelo de bielas y tirantes sencillo ilustrado en la Figura (1b-2).
La armadura provista para el tirante principal consiste en dos capas de cinco barras No. 9
(# 29 mm). El anclaje de estas barras se logra mediante ganchos normales a 90º. En la
Figura (1b-6) se indican los detalles de la armadura.

Tjen N. Tjhin es candidato al doctorado en el Departamento de Ingeniería Civil y
Ambiental de la Universidad de Illinois en Urbana-Champaign. El área de sus
investigaciones incluye el análisis no lineal y el diseño de estructuras de hormigón.

Daniel (Dan) A. Kuchma es Profesor Adjunto de Ingeniería Civil y Ambiental de la
Universidad de Illinois en Urbana-Champaign. Es miembro del Subcomité ACI 318E,
Corte y Torsión, y también del Comité conjunto ACI-ASCE 445, Corte y Torsión y su
Subcomité 445-A, Bielas y Tirantes.

81

<!-- p. 20 -->

Ejemplo 1b: Diseño alternativo para la viga no esbelta (viga de gran altura)

1 Geometría y cargas

En la Figura (1b-1) se ilustran la estructura y las cargas consideradas

todas las placas de apoyo son Vu = 360 kips
(1601 kN) Vu= 360 kips 18" x 20" (457 mm x 508 mm)

80" 80" 80"

mm) 80"
80" =

h (2032

16" 3 @ 80" = 240" (6096 mm) 16"
(406 mm) b = 20" (508 mm)
Vu= 360 kips Vu= 360 kips Corte

Figura 1b-1: Estructura y cargas

Resistencias de los materiales:
fc' = 4 ksi (27,6 MPa) (hormigón de peso normal)
fy = 60 ksi (414 MPa)

2 Procedimiento de diseño

La totalidad de la viga de gran altura constituye una región perturbada debido a que está
próxima a discontinuidades estáticas, es decir, las fuerzas concentradas, a una distancia
menor que una altura de la viga a cada lado de la discontinuidad. Sin embargo, para
completar el diseño sólo es necesario considerar el tercio izquierdo de la estructura porque
la geometría y las cargas son simétricas respecto a un eje vertical que pasa por la mitad de
la longitud de la viga. La estructura se diseñará usando el método de bielas y tirantes de
acuerdo con el Apéndice A de ACI 318-02. El procedimiento paso a paso es el siguiente:
− Paso 1: Verificar la capacidad portante en los puntos de carga y apoyo.
− Paso 2: Establecer el modelo de bielas y tirantes y determinar las fuerzas requeridas en
el reticulado.
− Paso 3: Seleccionar la armadura del tirante.

82

<!-- p. 21 -->

Ejemplo 1b: Diseño alternativo para la viga no esbelta (viga de gran altura)

− Paso 4: Diseñar las zonas nodales y verificar los anclajes.
− Paso 5: Verificar las bielas diagonales.
− Paso 6: Calcular la armadura mínima requerida para limitar la fisuración.
− Paso 7: Detallar la armadura.

3 Cálculos

3.1 Paso 1: Verificar la capacidad portante en los puntos de carga y apoyo

El área de la placa de apoyo es Ac = 18 (20) = 360 in.2 (232.258 mm2)
Las tensiones de apoyo en los puntos de carga y apoyo son
Vu 360(1000) = = 1000psi (6,89MPa)
A c 360

Según la definición de la Sección A.5.2 de ACI, la zona nodal debajo de los puntos de
carga constituye un nodo totalmente comprimido (CCC). La resistencia efectiva a la
compresión de este nodo está limitada a
f cu = 0,85β n f c´ [ACI Sección A.5.2 ec. (A-8)]
\= 0,85(1,00)(4000) = 3400psi

La zona nodal sobre los puntos de apoyo constituye un nodo tanto comprimido como
traccionado (CCT). La resistencia efectiva a la compresión de este nodo es
f cu = 0,85β n f c´ [ACI Sección A.5.2 ec. (A-8)]
\= 0,85(0,80)(4000) = 2720psi

Como las tensiones de apoyo son menores que los límites correspondientes, es decir, φfcu =
0,75 (3400) = 2550 psi (17,58 MPa) en los puntos de carga y φfcu = 0,75 (2720) = 2040 psi
(14,07 MPa) en los apoyos, el área de las placas de apoyo provistas es adecuada.

3.2 Paso 2: Establecer el modelo de bielas y tirantes y determinar las fuerzas
requeridas en el reticulado

En la Figura (1b-2) se ilustra el modelo de bielas y tirantes seleccionado. El reticulado
consiste en una biela directa AB (o biela CD) que se extiende desde la carga aplicada hasta
el apoyo. La biela BC y el tirante AD son necesarios para equilibrar el reticulado. Como se
muestra en la Figura (1b-3), esta biela y este tirante forman un par de fuerzas,
Fu,BC = Fu,AD (1b-1)

83

<!-- p. 22 -->

Ejemplo 1b: Diseño alternativo para la viga no esbelta (viga de gran altura)

Vu= 360 kips Vu= 360 kips

80" 80" 80"

B Fu, BC C
mm) Fu,AB Fu, CD 80"
θ θ (2032
Fu, AD D A

16" 3 @ 80" = 240" (6096 mm) 16"
(406 mm)
Vu = 360 kips (1601 kN) Vu= 360 kips

Figura 1b-2: Modelo de bielas y tirantes seleccionado

Es fácil definir la posición horizontal de los nodos A y B, pero es necesario estimar o
determinar la posición vertical de estos nodos. Para utilizar plenamente la viga estos nodos
deben estar tan cerca como sea posible de las partes superior e inferior de la misma. En
otras palabras, se debe maximizar el brazo de palanca, jd, del par de fuerzas, y esto
significa que se deben minimizar el ancho de la biela BC, ws, y el ancho para anclar el
tirante AD, wt.
Para minimizar ws la fuerza en la biela BC, Fu,BC, debe alcanzar su capacidad definida en la
Sección A.3.2 de ACI, o bien
Fu,BC = φFnc = φf cu A c = φ (0,85β s f c´ )bw s , donde β s = 1,0(prismática) (1b-2)

Para minimizar wt la fuerza en el tirante AD, Fu,AD, debe alcanzar la capacidad del nodo
para anclar este tirante, la cual se define en la Sección A.5.2 de ACI, o bien
Fu,AD = φFnt = φf cu A c = φ (0,85β n f c´ )bw t , donde β n = 0,8 (nodo CCT) (1b-3)

Sustituyendo las ecuaciones (1b-2) y (1b-3) en la ecuación (1b-1) se obtiene wt = 1,25 ws y
jd = 80 − w s / 2 − w t / 2 = 80 − 1,125w s (1b-4)

Escribiendo la ecuación de equilibrio de momentos respecto del punto A como se describe
en la ecuación (1b-5) y reemplazando las ecuaciones (1b-2) y (1b-4) en esta ecuación se
obtiene ws = 7,95 in., y por lo tanto wt = 9,94 in.
Vu (80) − Fu,BC jd = 0 (1b-5)

84

<!-- p. 23 -->

Ejemplo 1b: Diseño alternativo para la viga no esbelta (viga de gran altura)

Vu= 360 kips Eje

φ fcu = φ 0,85 βs f'c
Fu, BC ws
B

AB
Fu, jd = 80 - 1,125 ws

θ A wt Fu, AD
φ fcu = φ 0,85 βs f'c
80"
(2032 mm)
Vu = 360 kips (1601 kN)

Figura 1b-3: Diagrama de cuerpo libre del tercio izquierdo de la viga de gran altura

Si los valores de ws y wt así obtenidos se utilizan para las dimensiones de las bielas y
tirantes, la tensión en la biela BC, Fu,BC, estará en su valor límite y la fuerza en el tirante
AD, Fu,AD, estará anclada en un área apenas suficiente. En este diseño se selecciona ws = 8
in. (203 mm) y wt = 10 in. (254 mm). Por lo tanto, d = 80 − 10/2 = 75 in., jd = 80 − 8/2 =
71 in. y Fu,BC = Fu,AD = 360 (80) / 71 = 406 kips (1806 kN). La biela BC está ubicada a 8/2
\= 4 in. (102 mm) de la parte superior de la viga y el tirante AD está ubicado a 10/2 in. (127
mm) de la parte inferior de la misma. En la Figura 1b-4 se ilustra la geometría corregida
del reticulado.
El ángulo y la fuerza de la biela diagonal AB son θ = arctan (71/80) = 41,6º y Fu,AB =
360/sin 41,6º = 542 kips (2411 kN), respectivamente.

Vu = 360 kips
Eje

ws = 8" (203 mm)
Fu,BC= 406 k
B (1806 kN)
k kN) 542
\= jd = 71" (1803 mm) Fu,BC (2411
θ = 41,6º
A
Fu,AD= 406 k

80"
(2032 mm)
Vu = 360 kips (1601 kN)

Figura 1b-4: Dimensiones y fuerzas del modelo de bielas y tirantes
85

<!-- p. 24 -->

Ejemplo 1b: Diseño alternativo para la viga no esbelta (viga de gran altura)

3.3 Paso 3: Seleccionar la armadura del tirante

La armadura mínima provista para el tirante debe satisfacer
φFnt = φA st f y ≥ Fu,AD = 406 kips (1806kN) [ACI Secciones A.4.1 y A.2.6]

Por lo tanto, la sección de armadura requerida para el tirante AD es
Fu,AD 406 2 = = 9,02in.
φf y 0,75(60)

Consideramos las tres disposiciones de armadura siguientes:
− 1 capa de 6 barras # 11, Ast = 6 (1,56) = 9,36 in.2, a 5 in. de la parte inferior
− 2 capas de 5 barras # 9, Ast = 2 (5) (1,00) = 10 in.2, a 2,5 y 7,5 in. de la parte inferior
− 3 capas de 6 barras # 7, Ast = 10,8 in.2, a 2, 5 y 8 in. de la parte inferior
Para una mejor distribución del acero y para facilitar el requisito sobre longitud de anclaje,
seleccionamos 2 capas de 5 barras # 9 (# 29 mm), Ast = 10 in.2 (6452 mm2).

3.4 Paso 4: Diseñar las zonas nodales y verificar los anclajes

Para anclar el tirante AD se utiliza un gancho normal a 90º. La longitud de anclaje
requerida es
0,02f y d b 9,02 0,02(60.000)(1,128)
l dh = λ = = 19,3in. [ACI Sección 12.5]
f c´ 10,0 4000

A st requeridodonde λ = representa el factor de corrección para exceso de armadura.
A st provisto

La Sección A.4.3.2 de ACI requiere que esta longitud de desarrollo empiece en el punto
donde el baricentro de la armadura de un tirante abandona la zona nodal extendida e
ingresa al tramo. Como se puede observar en la parte izquierda de la Figura (1b-5), la
longitud de desarrollo disponible es 27,0 in. (686 mm). Como este valor es mayor que 19,3
in. (490 mm), la longitud de anclaje es adecuada.

86

<!-- p. 25 -->

Ejemplo 1b: Diseño alternativo para la viga no esbelta (viga de gran altura)

l =b 18" (457 mm)

w = 19,4" (493 mm)
sb B ws = 8" (203 mm)
θ = 41,6°
l a= 27,0"
(686 mm)
θ = 41,6° A
wst = 17,9" (455 mm) w = 10"

Zona Zona nodal
Nodal A l b= 18" extendida A

Figura 1b-5: Zonas nodales A y B

3.5 Paso 5: Verificar las bielas diagonales

De la Sección 3.2, el ángulo de la biela AB (o CD) es θ = 41,6º, y la fuerza es
Fu,AB = 542kips (2411kN)

Como se indica en la Figura (1b-5), el ancho en la parte superior de la biela es
w st = l b sin θ + w t cos θ
\= 18sin 41,6º + 8cos41,6º = 17,9in. (455mm)

y el ancho en la parte inferior de la biela es
w sb = l b sin θ+ w t cos θ
\= 18sin 41,6º +10cos41,6º = 19,4in. (493mm)

Se anticipa que la biela AB será una biela en forma de botella. Asumiendo que se utiliza
suficiente armadura de control de la fisuración para resistir la fuerza de estallido en la biela
(βs = 0,75), la capacidad de la biela AB está limitada a:
φFns =φ (0,85βsfc')bwst
\= 0,75 (0,85) (0,75) (4) (20) (17,9) [ACI Secciones A.2.6 y A.3.2]
\= 685 kips (3047 kN).
Como este valor es mayor que la fuerza requerida, la biela AB (o CD) resulta adecuada.

3.6 Paso 6: Calcular la armadura mínima requerida para limitar la fisuración

La armadura de corte vertical provista debe ser al menos
Av = 0,0025bs [ACI Sección 11.8.4]

87

<!-- p. 26 -->

Ejemplo 1b: Diseño alternativo para la viga no esbelta (viga de gran altura)

y la armadura de corte horizontal provista debe ser al menos
Avh = 0,0015bs2 [ACI Sección 11.8.5]
donde s y s2 no pueden ser mayores que d/5 ni 12 in.
Para la armadura de corte vertical usar barras # 5 (# 16 mm) separadas 12 in. (305 mm) en
cada cara en la totalidad de la longitud, Av / bs = 2 (0,31) / 20 / 12 = 0,0026 > 0,0025.
Para la armadura de corte horizontal usar barras # 4 (# 13 mm) separadas 12 in. (305 mm)
en cada cara en la totalidad de la longitud, Avh / bs2 = 2 (0,20) / 20 / 12 = 0,0017 > 0,0015.
Como para calcular la resistencia de la biela AB se utilizó βs = 0,75 la armadura mínima
provista también debe satisfacer

sin γ i ≥ 0,0030 [ACI Sección A.3.3.1 ec. (A-4)] ∑ A si bs i
donde γi es el ángulo formado por el eje de la armadura mínima y el eje de la biela. En base
a la armadura de corte provista,

sin γ i = 0,0017 sin 41,6º + 0,0026 sin 48,4º = 0,0031 ≥ 0,003. ∑ A si bs i

3.7 Paso 7: Detallar la armadura

En la Figura (1b-6) se ilustran los detalles de las armaduras.

2 barras #9
Eje
A Placas de apoyo 18'' x 20''
(457 mm x 508 mm) (típico

Armadura de corte horizontal
mm) #4 (# 13 mm) @ 12'' (305 mm)
80" en cada cara (típico)
5" (2032 Armadura de corte vertical
(127 mm) #5 (# 16 mm) @ 12'' (305 mm)
en cada cara (típico)
2,5"
A 2 capas de 5 barras #9
(63,3 mm) 20" 16" 80" 40" (# 29 mm)
(508 mm) (406 mm) (2032 mm) (1016 mm)
Corte A-A

Figura 1b-6: Detalles de las armaduras

88

<!-- p. 27 -->

Ejemplo 1b: Diseño alternativo para la viga no esbelta (viga de gran altura)

4 Resumen

Se presenta un diseño de una viga de gran altura simplemente apoyada solicitada por dos
cargas puntuales. Este diseño se efectuó usando los requisitos del Apéndice A de ACI 31802, "Modelos de Bielas y Tirantes."
Los pasos más importantes en el proceso de diseño de esta viga de gran altura implican
definir la región D y las fuerzas de borde que actúan sobre dicha región, visualizar un
reticulado que lleve las fuerzas de borde en la región D (es decir, el modelo de bielas y
tirantes), resolver las fuerzas en los miembros del reticulado, proveer armadura que
conforme los tirantes de acero, dimensionar las bielas y nodos y proveer armadura
distribuida para lograr ductilidad.
La totalidad de la viga de gran altura constituye una región D debido a que está próxima a
discontinuidades estáticas, es decir, las fuerzas concentradas, a una distancia menor que
una altura de la viga a cada lado de la discontinuidad. Para el diseño se utilizó un modelo
de bielas y tirantes sencillo. Este modelo de bielas y tirantes dio por resultado el uso de 2
capas de 5 barras # 9 (# 29 mm) para el tirante principal. Se prestó particular atención al
anclaje de este tirante principal a fin de garantizar que pueda transferir la fuerza requerida
sin que se produzcan fallas de anclaje. Los requisitos de anclaje se satisficieron usando
ganchos normales a 90º.

Referencias

ACI 318-2002: Building Code Requirements for Reinforced Concrete and Commentary.
ACI Committee 318, American Concrete Institute, Detroit, Michigan, 2002, 443 pp.

89

<!-- p. 28 -->

Ejemplo 1b: Diseño alternativo para la viga no esbelta (viga de gran altura)

90
