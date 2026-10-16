---
type: libro
title: "Ejemplo6"
author: "lauri"
categoria: "ESTRUCTURA"
paginas: 22
extraccion: "texto"
fuente: "local:E:/MATERIAL DE CONSULTA/ESTRUCTURA/BIELAS Y TIRANTES/Ejemplo6.pdf"
convertido: 2026-10-16
---

# Ejemplo6

> Texto extraído de `ESTRUCTURA\BIELAS Y TIRANTES\Ejemplo6.pdf` (22 páginas, texto). El PDF original está en el disco E: (MATERIAL DE CONSULTA); `<!-- p. N -->` marca el inicio de cada página.

<!-- p. 1 -->

Ejemplo 6: Viga pretensada

Adolfo Matamoros

Julio Ramirez

Sinopsis

Se presenta el diseño de la región del extremo de una viga pretensada según el Apéndice A
del Código ACI 318-2002. Se consideran dos alternativas, la primera de ellas con cables
rectos desadheridos hacia los extremos del miembro a fin de controlar las tensiones en la
transferencia. El segundo caso es con cables deformados. Se desarrollan y analizan
modelos de bielas y tirantes para cada una de las dos alternativas y se dimensionan las
armaduras para resistir los esfuerzos internos calculados. Los requisitos sobre longitud de
anclaje fueron un factor crítico a la hora de seleccionar la configuración de los modelos
reticulados.

Adolfo Matamoros recibió su MS y Doctorado de la Universidad de Illinois, Urbana
Champaign. Se desempeña como Profesor Asistente en la Universidad de Kansas. Sus
investigaciones abarcan el diseño al corte y detallado del hormigón estructural. Es
Secretario del Comité ACI 408, Adherencia y Desarrollo de las Armaduras.

Julio Ramirez es Profesor de Ingeniería Estructural en la Universidad de Purdue. Es
miembro de ACI y ha sido galardonado con el premio Delmar Bloem. Es miembro de los
Comités ACI sobre Actividades Técnicas, Publicaciones, 318, Código de Construcción
Estructural, Comité 408, Adherencia y Desarrollo de las Armaduras, Comité Conjunto
ACI-ASCE 445, Corte y Torsión, Comité Conjunto ACI-ASCE 423, Hormigón
Pretensado.

<!-- p. 2 -->

Ejemplo 6: Viga pretensada

1 Geometría y cargas

Se diseña la región del extremo de una viga pretensada simplemente apoyada sometida a
una carga uniformemente distribuida, wu, usando el Apéndice A del Código ACI 3182002. En la Figura 6-1 se indican las dimensiones de la viga. La distancia entre apoyos es
de 30 ft. (9144 mm) y la longitud total de la viga es de 32 ft.- 8 in. (9957 mm).

A
30' (9144 mm)

28" (711 mm)

Sección transversal de la viga
28" (711 mm)

12" (305 mm)
Figura 6-1: Dimensiones del miembro (en mm)

Las cargas de diseño y propiedades de los materiales de la viga son los siguientes:

wu = 0,30 kip/in. (53 N/mm) fse = 150 ksi (1034 MPa)
fc' = 7,5 ksi (52 MPa) fy = 60 ksi (414 MPa)
b = 12 in. (305 mm)

Para detallar el extremo de la viga se consideraron dos alternativas diferentes. En el primer
caso se considera un patrón de cables horizontales, incluyendo la opción de desadherir
algunos de los cables en secciones ubicadas a 15 in. (381 mm) y 45 in. (1143 mm) del eje
de los apoyos (Figura 6-2). En la segunda alternativa el extremo de la viga se diseña
usando una combinación de cables rectos y algunos cables deformados en el punto D de la
Figura 6-2, ubicado a 91 in. (2311 mm) del extremo de la viga. La distancia entre el centro
del apoyo y el extremo de la viga es de 16 in. (406 mm). Las dimensiones de la placa de
apoyo supuesta son 6 x 12 in. (152 x 305 mm):

15" 30" 30" 8'-9" 15'

A B C D L c

Figura 6-2: Dimensiones de la viga y ubicación de las secciones críticas
del modelo de bielas y tirantes

164

<!-- p. 3 -->

Ejemplo 6: Viga pretensada

2 Procedimiento de diseño

El diseño global de las regiones D y B del miembro se puede realizar usando el Apéndice
A del Código 318-02 (ACI, 2002). En la práctica es probable que las partes de la viga que
se diseñan como regiones B sean diseñadas usando los procedimientos incluidos en el
cuerpo principal del código. A los fines de este trabajo el miembro se diseñará usando los
requisitos incluidos en el Apéndice A así como otras secciones relevantes del Código ACI
318-2002. Los pasos a seguir son los siguientes:
• Paso 1: Determinar los límites entre las regiones D y las regiones B de la viga y
calcular las demandas de momento y corte en estas ubicaciones.
• Paso 2: Establecer un modelo de bielas y tirantes inicial para la región a diseñar en base
a las dimensiones de la biela horizontal y el tirante horizontal obtenidas a partir de los
requisitos flexionales. Verificar que las fuerzas en las bielas horizontal e inclinada
críticas permanezcan por debajo de las máximas resistencias efectivas permitidas por
los requisitos de ACI. Si la resistencia de las bielas es adecuada en función de los
límites especificados en el Apéndice A, proceder a dimensionar la armadura. Caso
contrario optar entre ajustar el ancho o la altura de las bielas, la resistencia a la
compresión uniaxial del hormigón o el ancho de la viga, según cuál opción sea más
factible.
• Paso 3: Determinar el número de cables necesario para satisfacer la demanda de fuerza
en el tirante principal. Verificar que los cables estén anclados adecuadamente.
• Paso 4: Dimensionar armadura no pretensada para satisfacer las demandas de fuerza
que actúan en los tirantes. En los miembros pretensados se puede usar acero no
pretensado para suplementar la resistencia provista por el acero de pretensado. Esto
puede resultar crítico en las regiones próximas a los extremos de las vigas donde la
transferencia del pretensado se produce por adherencia. Asegurar que la armadura
mínima y la separación máxima satisfagan los requisitos de ACI 318-02.

3 Cálculos para la región del extremo de la viga con cables rectos

La porción de la viga relevante para este ejemplo de diseño está ubicada entre el borde de
la viga y la sección D (Figura 6-2), la cual corresponde al límite entre las regiones D y B.
La ubicación de la sección D se eligió de manera tal que está a una distancia
aproximadamente igual a la profundidad efectiva a partir de la sección de desadherencia
más próxima a la línea de centro de la viga. Siguiendo el procedimiento delineado en la
Sección 2 se desarrolla un modelo de bielas y tirantes capaz de transferir las fuerzas entre
la sección D y el extremo de la viga.

165

<!-- p. 4 -->

Ejemplo 6: Viga pretensada

Tabla 6-1: Demandas calculadas en el límite de la región a diseñar

Distancia desde el apoyo Mu x 103 Vu
in. (mm) kip in. (kN mm) kips (kN)

75 (1905) 3,21 (362) 31,5 (140)

3.1 Determinar las demandas de momento flector y corte en el límite de la región a
diseñar

La demanda de momento flector y corte en el límite de la región a diseñar se determinan en
base a los principios del equilibrio. En la Tabla 6-1 se resumen la magnitud del momento
flector y el esfuerzo de corte.

3.2 Definir el modelo de bielas y tirantes

La configuración del modelo y bielas y tirantes se define en base a la altura de la biela
horizontal y a la altura del tirante horizontal, según se describió en el paso 2 del
procedimiento sugerido. La altura del tirante flexional principal se define como dos veces
la distancia entre el fondo de la viga y el baricentro de los cables. Los cables están
distribuidos en dos capas separadas 2 in. (51 mm), como se puede ver en la Figura 6-3.

Biela

28" (711 mm)

Tirante
2" (51 mm)
Capas de
armadura
2" (51 mm)

12" (305 mm)

Figura 6-3: Ubicación de los cables para la viga con cables horizontales

166

<!-- p. 5 -->

Ejemplo 6: Viga pretensada

En la Figura 6-4 se ilustra el modelo de bielas y tirantes idealizado para la región a diseñar.
Las líneas llenas corresponden a los elementos traccionados, mientras que las líneas
discontinuas representan las bielas. En la sección D, ubicada a 75 in. (1905 mm) del apoyo
(Figura 6-4) se asume que el número total de cables está distribuido de forma uniforme
entre las dos capas (Figura 6-3). En consecuencia, la altura del tirante (N6 - N4 - N2 en la
Figura 6-4) es de 6 in. (152 mm) y su baricentro está ubicado a 3 in. (76 mm) de la cara
inferior de la viga. Se asume que la altura de la biela horizontal (N5 - N3 - N1 en la Figura
6-4) es de 3 in. (76 mm), lo cual corresponde aproximadamente al ancho calculado para el
diagrama rectangular de tensiones en el borde de la región D (a = 2,5 in.). Una vez
calculados los esfuerzos internos se investigará la posibilidad de desadherir parte del
número total de cables, ya que sería útil lograr un adecuado control de las tensiones en
transferencia y bajo niveles de cargas de servicio.
Las cargas verticales aplicadas en los nodos del modelo de bielas y tirantes (Figura 6-4)
consideran los efectos de la carga distribuida que actúa sobre la viga. La configuración del
modelo se seleccionó de manera que el ángulo de inclinación de la primera biela (elemento
9, Figura 6-4) sea mayor que el de las otras dos bielas a fin de lograr una mejor
representación del abanico de compresión que se forma en la región que rodea al apoyo. El
ángulo de inclinación de la segunda y tercera biela (α en la Figura 6-4) se calculó en base a
las dimensiones del tirante horizontal, la biela horizontal y la distancia entre tirantes
verticales. Para el modelo de bielas y tirantes ilustrado (Figura 6-4) α = 38,1º; este valor es
mayor que el límite inferior de 25º establecido por el Código ACI (2002).

3.3 Verificar la altura total del modelo y determinar los esfuerzos internos en todas
las bielas y tirantes

La cupla formada por las fuerzas Cc y Ts debe ser igual al momento externo que actúa en el
punto D (Figura 6-4). Por lo tanto,

3,21 × 10 3 kip in.
C c = Ts = = 136 kip (607 kN) (6-1)
23,5 in.

Las fuerzas en los elementos se determinan en base a la condición de equilibrio para cada
uno de los seis nodos ilustrados en la Figura 6-4. En la Tabla 6-2 se resumen los
resultados. Los signos negativos indican compresión.

167

<!-- p. 6 -->

Ejemplo 6: Viga pretensada

9,38 kip 9,38 kip 3,75 kip
(42 kN) (42 kN) (17 kN)

Cc N5 F5 N3 F2 N1

F9 F6
F7 F3 F1 23,5 in. F10 (597mm)
α
N6 F8 F4 F0 Ts
N4 N2

54 kip
(240 kN) 31,5 kip
(140 kN)

B C

15 in. 30 in. 30 in.
(381 mm) (862 mm) (862 mm)
A D

Figura 6-4: Modelo de bielas y tirantes para el extremo de la viga
con cables horizontales

Tabla 6-2: Fuerzas en los elementos del modelo de bielas y tirantes de la Figura 6-4

Nombre del elemento Fuerza
Tipo de elemento
(Figura 6-4) kip (kN)

Bielas horizontales F2 -91 (-407)
F5 -34 (-153)
Bielas inclinadas F1 -57 (-254)
F6 -72 (-322)
F9 -64 (-285)
Tirantes F0 136 (607)
horizontales
F4 91 (407)
F8 34 (153)
Tirantes verticales F3 35 (157)
F7 45 (199)
F10 32 (140)
168

<!-- p. 7 -->

Ejemplo 6: Viga pretensada

3.4 Verificar la capacidad de las bielas horizontales e inclinadas

La capacidad nominal de las bielas se determina usando la resistencia efectiva a la
compresión dada por la Ecuación A-3 del Código ACI (2002):
f cu = 0,85β s f c´ [ACI Sección A.3.2, Ec. (A-3)]

De acuerdo con la Sección A.3.2 del Código ACI, la resistencia efectiva a la compresión
debería ser la resistencia del hormigón en la biela o la resistencia del hormigón en la zona
nodal, según cuál valor sea el menor. La biela horizontal crítica del modelo reticulado
ilustrado en la Figura 6-4 es el elemento 2, ubicado cerca del límite de la región bajo
estudio. El Nodo 3, ubicado en el extremo izquierdo de la Biela 2, se clasifica como nodo
C-C-T porque en él convergen dos bielas y un tirante. De acuerdo con el Apéndice A del
Código ACI, el factor de resistencia para una biela ubicada en la zona comprimida de una
viga es βs = 1,0 y el factor de resistencia para un nodo con un tirante es βn = 0,8. Dada la
menor capacidad del hormigón del nodo, βn = 0,8 determina la capacidad nominal de la
biela.
Por lo tanto, la resistencia de diseño de la biela horizontal es:
f cu = 0,85 × 0,8 × 7,5 ksi = 5,1 ksi (35MPa) (6-2)
φFns = 0,75 × f cu × A c [ACI Sección A.3.1, Ec. (A-2)]
φFns = 0,75 × f cu × 12in. × 3in. = 138 kip (613kN) (6-3)

donde φ es el factor de reducción de la resistencia que, de acuerdo con la Sección 9.3.2.6
del Código ACI, es igual a 0,75 para las bielas, tirantes, zonas nodales y áreas de apoyo de
los modelos de bielas y tirantes. La Ecuación 6-3 muestra que la capacidad de la biela
horizontal es mayor que la demanda sobre la biela, igual a 91 kip (407 kN) (Tabla 6-2). Por
lo tanto la resistencia de la biela es adecuada.
Se investigaron las bielas inclinadas 6 y 9 para determinar cuál de las dos tenía la mayor
demanda. Debido a que hay un tirante anclado en cada uno de los nodos 5 y 6, ubicados en
los extremos de la Biela 9 (F9, Figura 6-4), el factor de reducción de la resistencia para los
nodos es βn = 0,80. Se considera que el elemento 9 es una biela en forma de botella porque
su ancho se puede expandir entre nodos. En consecuencia, de acuerdo con la Sección
A.3.2.2 del Código ACI, el factor de resistencia para la biela es βs = 0,6. Este valor es
menor que el factor de resistencia para los nodos. Aunque la Sección A.3.2.2 permite
utilizar un factor mayor βs = 0,75 si se dispone armadura que satisfaga la Sección A.3.3, en
este caso se asumió que no se disponía este tipo de armadura y por lo tanto se usó el factor
más conservador. Por lo tanto, la resistencia nominal del hormigón en la Biela 9 es:
f cu = 0,85 × 0,6 × 7,5ksi = 3,83ksi (26MPa) (6-4)

169

<!-- p. 8 -->

Ejemplo 6: Viga pretensada

Para determinar la capacidad nominal de la biela es primero necesario calcular su ancho.
La Figura 6-5 muestra el Nodo 6, ubicado en el apoyo. El ancho en la parte inferior de la
Biela 9 está dado por la Ecuación 6-5:
w st = l bp sin α + h t cos α (6-5)

donde lbp es el ancho de la placa de apoyo y ht es la altura del tirante horizontal. De
acuerdo con la Ecuación 6-5, el ancho de la Biela 9 en su parte inferior es:
w 9b = 6in.sin57,5º +6in. cos57,5º = 8,3in. (210mm) (6-6)

El ancho en la parte superior de la Biela 9 (w9t), la parte inferior de la Biela 6 (w6b) y la
parte superior de la Biela 6 (w6b) (Figura 6-4) también se calculan usando la Ecuación 6-5.
El modelo geométrico de estos nodos es similar al ilustrado en la Figura 6-5, excepto que
la longitud lbp se toma como la mitad del ancho del tirante vertical que converge al nodo y
ht se toma como la altura de la biela (3 in. 76 mm). Por lo tanto, se debe calcular el ancho
del Tirante 7 para obtener el ancho de la Biela 9 en el Nodo 5. La Sección RA.4.2 del
Comentario del Código ACI (2002) sugiere calcular un límite para el ancho del tirante en
base a la tensión de apoyo admisible de la región nodal. Siguiendo estas recomendaciones
obtenemos el ancho del Tirante 7 en base a la tensión admisible en el Nodo 5:
F7 45 kip w tirante7 = ´ = = 1 in. (25mm) (6-7)
φ0,85β n f c b 0,75 × 0,85 × 0,80 × 7,5 ksi × 12in.

El ancho del elemento 9 en la parte superior de la biela se calcula en base al ancho del
tirante y el ancho de la biela horizontal:
w tirante 1in. w 9t = sin α + h t cos α = sin57,5º +3in. cos57,5º = 2in. (52mm) (6-8) 2 2

De manera similar, el ancho de la Biela 6 en la parte superior de la biela se calcula en base
a la altura del tirante y la tensión admisible en el Nodo 3. El ancho del Tirante 3 es:
F3 32kip w tirante3 = ´ = = 0,7in. (18mm) (6-9)
φ 0,85β n f c b 0,75 × 0,85 × 0,80 × 7,5 ksi × 12in.

170

<!-- p. 9 -->

Ejemplo 6: Viga pretensada

α ht cos α
lbp sin α

ht

zona nodal
extendida

lbp

la

Figura 6-5: Ancho de una biela en función de las dimensiones nodales

Por lo tanto, el ancho de la Biela 6 está dado por:
w 6t = 0,35in.sin38,1º +3in. cos38,1º = 2,6in. (65mm) (6-10)

La capacidad de la Biela 9 se calcula en la sección de menor ancho, la cual ocurre en la
parte superior de la biela, y está dada por:
φFns = 0,75 × f cu × 12in. × 2in. = 69kip (307kN) (6-11)

Esto es mayor que la demanda en la biela (64 kip, 285 kN, Tabla 6-2). De manera similar,
la capacidad de la Biela 6 está dada por:
φFns = 0,75 × f cu × 12in. × 2,6in. = 90kip (400kN) (6-12)

Esto también es mayor que la demanda en la biela (72 kip, 322 kN, Tabla 6-2). Habiendo
verificado que la resistencia de las bielas es adecuada, el siguiente paso consiste en
dimensionar la armadura. Si alguna biela no satisface el criterio de mínima resistencia,
para satisfacer los requisitos del Código es necesario ajustar la profundidad de la biela, la
resistencia a la compresión del hormigón o el ancho de la viga.

171

<!-- p. 10 -->

Ejemplo 6: Viga pretensada

3.5.1 Calcular la armadura necesaria para los tirantes horizontales

En la Tabla 6-2 presentamos la demanda de fuerza en cada uno de los tres tirantes
horizontales. El número de cabes requerido para cada tirante se determina usando la
Ecuación A-6 del Código ACI, la cual define la resistencia nominal de un tirante de la
siguiente manera:
Fnt = A st f y + A ps (f se + ∆ f p ) [ACI Sección A.4.1, Ec. (A-6)]

Utilizamos cables con diámetro nominal de ½ in. (12,5 mm); estos cables poseen una
sección nominal de 0,153 in.2 (99 mm2). La Sección A.4.1 del Código ACI permite que el
diseñador asuma un valor ∆fp = 60 ksi (414 MPa). La sección total de cables de pretensado
requerida es:
Th tirante
A ps = (6-13) φ ( f se + ∆ f p )

La longitud de desarrollo es crítica para los Tirantes 4 y 8. De acuerdo con la Sección 12.9
del Código ACI (2002), la longitud de desarrollo de un cable está dada por:
 f se  f ps − f se ) d b [ACI Sección 12.9, Ec. (12-2)] l d =   d b + (
 3 

Reemplazando en esta ecuación el diámetro nominal del cable y los valores de tensión
correspondientes, la longitud de anclaje requerida para desarrollar plenamente la tensión en
el cable es:

 150ksi 
l d =  + 60ksi  × 0,5in. = 55in. (1397mm) (6-14)
 3 
Para tirantes cuya longitud de anclaje es menor que la requerida para ∆fp = 60 ksi (414
MPa), la Sección 12.9.1.1 permite usar menor empotramiento siempre que la tensión en el
cable no supere los valores obtenidos mediante la Ecuación 12-2 del Código.
En consecuencia, la Ecuación 12-2 se puede reordenar de manera de obtener la máxima
tensión que puede soportar el cable en función de la longitud de anclaje disponible, la:
l a 2f se f ps = + (6-15)
d b 3

La Ecuación 6-15 se debe aplicar solamente cuando la longitud de anclaje está
comprendida entre la longitud de transferencia (25 in., 635 mm para un cable de ½ in. de
diámetro) y la longitud de desarrollo. En otros casos se debe seguir un enfoque de análisis
por tramos como se describe en la Sección R12.9.1.1 del Comentario del Código ACI.
De acuerdo con las Secciones A.4.3.2 y A.4.3.3 del código ACI (2002), la fuerza en los
tirantes horizontales se debe desarrollar en el punto donde el baricentro de la armadura

172

<!-- p. 11 -->

Ejemplo 6: Viga pretensada

abandona la zona nodal extendida (Figura 6-5). En el caso de los nodos 2, 4 y 6 la distancia
entre el centro del nodo y el punto donde el baricentro de la armadura abandona la zona
nodal extendida está dada por:
w tirante  tan α  l a1 = 1 +  (6-16)
2  tan ( 90 −α ) 
donde α es el ángulo de inclinación de la biela y wtirante es el ancho del tirante vertical que
converge en el nudo. La distancia la1 se suma a la distancia entre el centro del nodo y el
borde de la viga para calcular la longitud de anclaje disponible; esto se indica en la Tabla
6-3. Para cada tirante la máxima tensión admisible se calcula usando la Ecuación 6-15, y la
armadura requerida se calcula usando la Ecuación 6-13 (Tabla 6-3).

Tabla 6-3: Dimensionamiento de los tirantes horizontales
Nombre del Th tirante la fps (6-15) Aps (6-13) Número de
elemento kip (kN) in. (mm) ksi (MPa) in2 (mm2) cables

F0 136 (607) 61,6 (1564) 210 (1450) 0,86 (557) 6
F4 91 (407) 31,8 (808) 164 (1128) 0,74 (477) 5
F8 43 (153) 26,4 (671) 153 (1054) 0,37 (242) 3

Ensayos realizados han demostrado que si una fisura inclinada (corte en el alma) penetra la
longitud de transferencia en aproximadamente 50db, en este caso 25 in. (636 mm), se
puede perder el anclaje del cable y las consecuencias pueden ser catastróficas (Peterman et
al., 2000). En este ejemplo la configuración de la viga es tal que la zona de la longitud de
transferencia del cable se extiende más allá de la línea de centro del apoyo, donde es
probable que se produzca una fisura por corte. Para solucionar este problema el Tirante 7
se diseñó para la totalidad de la fuerza de corte de manera que pueda restringir
efectivamente el crecimiento de la fisura inclinada. Un enfoque alternativo sería calcular
la tensión que puede soportar el cable con la longitud de anclaje reducida y proveer
armadura para soportar la tensión en exceso de la máxima tensión que puede desarrollar el
cable (Ramirez, 1994).
Los resultados de la Tabla 6-3 demuestran que dados los requisitos sobre longitud de
anclaje no es mucho el beneficio que se puede obtener desadhiriendo los cables. Un cable
se puede desadherir a 6,6 in. (168 mm) del borde. Esto se atribuye parcialmente a lo
próxima que se encuentra la región que estamos diseñando del borde de la viga, lo que
limita la distancia disponible para el correcto anclaje de los cables. Otro motivo es la
interacción entre corte y tracción en la armadura horizontal que habitualmente se observa
en los modelos de bielas y tirantes de vigas esbeltas. La componente horizontal de la fuerza
de compresión en las bielas inclinadas debe ser equilibrada por una fuerza en el tirante
horizontal, la cual se debe sumar a la fuerza necesaria para resistir la demanda por flexión.

173

<!-- p. 12 -->

Ejemplo 6: Viga pretensada

3.5.2 Calcular la armadura para los tirantes verticales

En la Tabla 6-2 se resumen las fuerzas en los tirantes verticales. La sección de armadura se
determina en base a una tensión de fluencia de 414 MPa, como se indica en la Ecuación 617:
Fu tirante
A st = (6-17)
φf y

Si usamos estribos en U formados por barras No. 4 (diámetro 9,5 mm), la sección total de
armadura vertical para cada tirante es 0,4 in.2 (258 mm2) que surge de dos ramas de 0,2 in.2
(129 mm2) cada una. La Sección A.4.3.4 del Código ACI estipula que los estribos se deben
anclar siguiendo las prácticas habituales, según lo especificado en la Sección 12.13. En la
Tabla 6-4 se resume el número de estribos requerido para cada tirante vertical, los cuales se
colocan próximos al centro de los tirantes. En las áreas de la región del extremo de la viga
comprendidas entre los tirantes verticales se coloca la armadura mínima requerida por el
Código ACI. De acuerdo con la Sección 11.5.4 del Código ACI (2002), para miembros
pretensados la máxima separación entre estribos es 0,75h, que en el caso de la viga
analizada es igual a 21 in. (533 mm). Se adopta una separación de 15 in. (381 mm),
correspondiente a la distancia entre las secciones A y B (Figura 6-4). La armadura mínima
del alma está dada por:

0,75 f c´ b w s 50b w s A v = ≥ [ACI Sección 11.5.5.3, Ec. (11-13)]
f y f y

0,75 7.500 12 × 15 2 2
A v = = 0,19in (126mm ) (6-18)
60.000
Para simplificar la fabricación de la jaula de armaduras se coloca un estribo No. 4 en el
punto medio entre las secciones B y C, y C y D (Av = 0,4 in.2; 258 mm2), además de la
armadura requerida en la ubicación de cada uno de los tirantes verticales.

Tabla 6-4: Dimensionamiento de los tirantes verticales

Nombre del Fu tirante Ast (6-17) Número de
elemento estribos, No.4 kip (kN) in2 (mm2)

F3 35 (107) 0,78 (502) 2
F7 45 (199) 1,00 (645) 3
F10 32 (140) 0,71 (458) 2

174

<!-- p. 13 -->

Ejemplo 6: Viga pretensada

3.6 Verificar la capacidad de apoyo

Las tensiones de apoyo en el nodo N6, ubicado en el apoyo de la viga (Figura 6-4), deben
permanecer dentro de los límites establecidos por el Código. La tensión de apoyo se
calcula dividiendo la fuerza de reacción por la superficie de la placa de apoyo:

54kip
f b = = 0,75ksi (5MPa) (6-19)
6in. × 12in.

Debido a que hay un tirante anclado en él, el nodo N6 es un nodo C-C-T. La resistencia de
apoyo es (βn = 0,8):
φFcu = 0,75 × 0,85 × 0,8 × 7,5ksi = 3,83ksi (26MPa) (6-20)

Por lo tanto la capacidad de apoyo del nodo es adecuada.

3.7 Disposición de la armadura en la región del extremo de la viga

En la Figura 6-6 se ilustra la disposición de la armadura en el extremo de la viga para el
caso de cables horizontales.

estribo 3 estribos 2 estribos 2 estribos
No.4 No.4 @ 2 in. No.4 @ 2 in. No.4 @ 2 in.

estribo No.4 estribo No.4

7 in.
(178 mm)

6 cables 5
cables

A B C D
Figura 6-6: Configuración de las armaduras para la región del extremo de la viga

175

<!-- p. 14 -->

Ejemplo 6: Viga pretensada

4 Cálculos para la región del extremo de la viga con cables deformados

En vista de las diferencias en la ubicación de los cables dentro de la región a diseñar es
necesario usar un modelo de bielas y tirantes diferente entre los puntos A y D (Figura 6-7).

4.1 Determinar las demandas de momento flector y corte para la viga

Las demandas de momento flector y corte en el borde de la región del extremo de la viga
son las indicadas en la Tabla 6-1.

4.2 Definir la configuración del reticulado

La configuración del reticulado se define en base a la altura de las bielas horizontales y la
altura de los tirantes horizontales. Igual que en la alternativa con cables horizontales, se
asumió que la altura de los tirantes horizontales es igual a 6 in. (152 mm) y la altura de las
bielas horizontales es igual a 3 in. (76 mm). La inclinación de las bielas es similar al caso
con cables horizontales (α = 38,1º). En el modelo con cables deformados (Figura 6-7) hay
nueve elementos adicionales y tres nodos adicionales en el reticulado, los cuales son
necesarios para modelar el gradiente de tensiones en la zona correspondiente a la longitud
de transferencia de los cables.

2,25 kip 6,75 kip 9 kip 4,5 kip
(10 kN) (30 kN) (40 kN) (20 kN)

CC N7 F10 N5 F6 N3 F2 N 1
F16
6,5" N8 F15 F11 F9
FD2 N9 F7 F5 F3 23,5"
F14 FD1 F1 (597 mm) F17
17" F12
F8 N6
F13 N4 N 2 F4
N10
T S
A B C D

8" 8" 15" 30" 30"
31,5 kip
(140 kN)

Figura 6-7: Modelo de bielas y tirantes para la región del extremo de la viga con cables
deformados

176

<!-- p. 15 -->

Ejemplo 6: Viga pretensada

Los elementos FD1 y FD2 representan los cables deformados. Se utilizan dos elementos
diferentes y se agrega el Nodo 9 (Figura 6-7) para modelar el efecto de la longitud de
transferencia sobre la tensión en los cables deformados. El reticulado ilustrado en la Figura
6-7 es estáticamente indeterminado. Para simplificar el cálculo de las fuerzas en los
elementos del reticulado se predeterminan las fuerzas en los tirantes FD1 y FD2 tomando en
cuenta la longitud de desarrollo de los cables. Hay un total de dos cables, correspondientes
al 33% de la fuerza de pretensado total, deformados en la sección D (Figura 6-7). Como se
mencionó anteriormente, la Sección A.4.3.2 del Código ACI (2002) estipula que la fuerza
en el tirante se debe desarrollar en el punto donde el baricentro de la armadura abandona la
zona nodal extendida. Para determinar la longitud de anclaje del cable analizamos las
dimensiones de la zona nodal 8 y las bielas que rodean y enmarcan esta zona nodal (Figura
6-8).
La dimensión de 6 in. indicada en la Figura 6-8 se seleccionó de manera de garantizar que
la capacidad de las bielas 11 y 14 sea adecuada. Las dimensiones la y lao se determinan
mediante consideraciones geométricas:
8in. l ao = = 8,2in. (207mm) (6-21) cos11,58º

La distancia entre la parte posterior del nodo y el punto donde el tirante abandona la zona
nodal extendida (Figura 6-8) se calcula usando la ley de los senos:

sin53,2º
l a − l ao = 4,1 in. × = 5,5in. (139mm) (6-22)
sin36,8º

Por lo tanto la longitud de anclaje total es:
al = 8,2in. + 5,5in. = 13,7in. (348mm) (6-23)

En este caso la longitud de anclaje disponible es menor que la longitud de transferencia. En
consecuencia la tensión mínima en el cable entre los Nodos 8 y 9 está dada por:
3 l a 3 × 13,7 f ps = = = 82ksi (567MPa) (6-24)
d b 0,5

Como hay un total de dos cables deformados, la fuerza en el Tirante FD2 está dada por:
FD2 = 2A ps f se = 2 × 0,153in.2 × 82ksi = 25kip (111kN) (6-25)

177

<!-- p. 16 -->

Ejemplo 6: Viga pretensada

lao

50,7º

6 in. (152 mm)
11,58º

53,2º

la

Figura 6-8: Longitud de desarrollo de los cables anclados en el Nodo 8

De forma similar, la fuerza en el Tirante FD1 se calcula en base a la longitud de anclaje en
el punto donde el tirante abandona la zona nodal extendida del Nodo 9. La distancia entre
los nodos N8 y N9 se puede calcular usando la ley de los senos, y es igual a 17 in. (432
mm). La distancia entre el centro del Nodo 9 y el punto donde el tirante abandona la zona
nodal extendida se calcula en base al ancho de la Biela 14 (8,3 in; 210 mm), como la
mitad del ancho de la biela dividido por el coseno del ángulo comprendido entre la normal
a la biela y el eje del tirante (21º). La longitud de anclaje es:
al = 8,2 + 17 + 4,4 = 29,6in. (752mm) (6-26)

Como la longitud de anclaje disponible es mayor que la longitud de transferencia, la
mínima tensión en el cable entre los Nodos 8 y 9 se puede determinar usando la Ecuación
6-15:
29,6 2 × 150
f ps = + = 159ksi (1096MPa) (6-27)
0,5 3

La fuerza en el Tirante FD1 está dada por:
FD1 = 2A ps f se = 2 × 0,153in 2 × 159ksi = 49kip (216kN) (6-28)

178

<!-- p. 17 -->

Ejemplo 6: Viga pretensada

4.3 Calcular las fuerzas en los elementos del reticulado

Una vez conocidas las fuerzas en los Tirantes FD1 y FD2, las fuerzas en el reticulado se
pueden calcular usando el principio de equilibrio. En la Tabla 6-5 se resumen los
resultados.

Tabla 6-5: Fuerzas en los elementos

Nombre del elemento Fuerza
Tipo de elemento
(Figura 6-7) kip (kN)
Bielas horizontales F2 -103 (-458)
F6 -58 (-258)
F10 -16 (-71)
Bielas inclinadas F3 -42 (-187)
F7 -57 (-254)
F11 -78 (-347)
F12 -27 (-120)
F14 -55 (-245)
F16 -21 (-93)
F17 -20 (-89)
Tirantes horizontales F4 88 (391)
F8 54 (240)
F13 21 (93)
Tirantes verticales F1 22 (98)
F5 26 (116)
F9 59 (262)
F15 11 (49)

4.4 Verificar la capacidad de las bielas horizontales e inclinadas

La biela horizontal crítica del modelo reticulado ilustrado en la Figura 6-7 es el elemento
F2. La capacidad de este elemento ya fue calculada en la Sección 3.4 (Ecuación 6-3) y se
determinó que es igual a 138 kip (613 kN), valor mayor que la demanda en el elemento F2.
La biela inclinada con mayor demanda es el elemento F11. Para calcular el ancho de la
Biela 11 en el Nodo 5 es necesario calcular primero el ancho del Tirante 9. El ancho del
Tirante 9 se calcula en base a la tensión admisible en el Nodo 5:

179

<!-- p. 18 -->

Ejemplo 6: Viga pretensada

F9 59kipw tirante = = = 1,29in. (33mm) (6-29)
φ0,85β n f cu b 0,75 × 0,85 × 0,80 × 7,5ksi × 12in.

El ancho del elemento F11 en la parte superior de la biela se calcula en base al ancho del
tirante y el ancho de la biela horizontal que enmarcan la zona nodal. Usando la Ecuación 66:
1,29in. w 1l t = sin32,6º +3in.cos32,6º = 2,9in. (73mm) (6-30) 2
La capacidad de la biela se calcula usando un factor βs = 0,6 (correspondiente a bielas en
forma de botella y también porque el Nodo 9 es un nodo tipo C-T-T):
φFns = 0,75 × f cu × 12in. × 2,9in. = 99kip (440kN) (6-31)

Este valor es mayor que la demanda en la biela (78 kip; 347 kN).

4.5 Calcular el número de cables necesarios en los tirantes horizontales

La Tabla 6-5 muestra la demanda de fuerza en cada uno de los tres tirantes horizontales.
El procedimiento es similar a los cálculos indicados en la Sección 3.5 para la viga con
cables horizontales. Usando la Ecuación 6-15 se calculó la máxima tensión admisible para
cada uno de los tirantes; la cantidad de armadura requerida se calculó usando la Ecuación
6-13 (Tabla 6-6).
La Tabla 6-6 muestra que si en el tirante horizontal se mantienen cuatro cables la cantidad
de armadura será suficiente para sostener la demanda calculada. Los comentarios incluidos
en la Sección 3.5 respecto de las consecuencias catastróficas de la formación de una fisura
de corte en la longitud de transferencia de un cable también son aplicables a este modelo
de bielas y tirantes.

Tabla 6-6: Dimensionamiento de los tirantes horizontales

Nombre del Th tirante la fps (6-15) Aps (6-13) Número de
elemento kip (kN) in. (mm) ksi (MPa) in2 (mm2) cables
F4 88 (391) 61,6 (1564) 210 (1450) 0,56 (360) 4
F8 54 (240) 31,8 (808) 164 (808) 0,44 (283) 3
F13 21 (93) 26,4 (671) 153 (1054) 0,18 (118) 2

4.6 Calcular la armadura para los tirantes verticales

Las Tablas 6-5 y 6-7 muestran las fuerzas calculadas para los tirantes verticales. De
manera similar al caso de la región extrema con cables horizontales, utilizamos estribos en
U formados por barras No. 4 (diámetro 9,5 mm) como armadura vertical (la sección total
de cada tirante es 0,4 in.2; 258 mm2). La Tabla 6-7 muestra la sección de armadura

180

<!-- p. 19 -->

Ejemplo 6: Viga pretensada

requerida por cada tirante, determinada mediante la Ecuación 6-17, y el correspondiente
número de estribos.

Tabla 6-7: Dimensionamiento de los tirantes verticales

Nombre del Fu tirante Ast (6-17) Número de
elemento kip (kN) in2 (mm2) estribos, No.4
F1 22 (98) 0,49 (315) 2
F5 26 (116) 0,58 (373) 2
F9 59 (262) 1,31 (846) 4
F15 11 (49) 0,24 (158) 1

Como se indica en la Tabla 6-7, la mayor demanda corresponde al elemento 9 y requiere el
uso de 4 estribos No. 4. Una parte significativa de la fuerza soportada por el elemento 9
tiene su origen en la diferencia entre las magnitudes de las fuerzas FD1 y FD2. Esta
diferencia se debe al enfoque seguido para modelar el anclaje de los cables, que de hecho
acumula la fuerza transferida entre los nodos 8 y 9 en el Nodo 9 (Figura 6-7). En realidad
la transferencia se produce de forma gradual a través de toda la longitud del cable, y por
este motivo parece más adecuado distribuir la armadura uniformemente entre los puntos A
y B que concentrarla en la ubicación del Tirante 9 (Figura 6-9).

4.7 Disposición de las armaduras

En la Figura 6-9 se ilustra la disposición de las armaduras para la viga. Se ha colocado
armadura transversal mínima de acuerdo con lo indicado en la Sección 3.6.

5 estribos No.4
2 estribos No.4 2 estribos No.4 @ 5 in. (125 mm)

estribo No.4 estribo No.4

2 cables

4 cables

A B C D

Figura 6-9: Configuración de las armaduras en el extremo de la viga

181

<!-- p. 20 -->

Ejemplo 6: Viga pretensada

5 Resumen

Se presenta el diseño de la región del extremo de una viga pretensada según el Apéndice A
del Código ACI 318-2002 − Modelos de Bielas y Tirantes. La configuración de los
modelos de bielas y tirantes se seleccionaron de manera de representar los efectos de la
transferencia de tensiones en los cables, las elevadas tensiones de corte que se producen
cerca del apoyo y los efectos de deformar parte de los cables.
El factor más crítico al momento de seleccionar la configuración de los modelos de bielas
y tirantes fueron los requisitos sobre longitud de desarrollo y longitud de anclaje de los
cables. La ubicación de los nodos se seleccionó con el objetivo de desarrollar modelos que
pudieran representar el aumento de la tensión en los cables en función de la longitud de
anclaje. Una vez seleccionados los modelos adecuados, se calcularon los esfuerzos internos
en los elementos de los reticulados y se verificó que satisficieran los requisitos del Código
ACI (2002).
Entre las principales diferencias entre ambos modelos se encuentra el efecto de la
componente vertical de la fuerza de pretensado en la viga con cables deformados. El
elemento 1 del modelo con cables deformados está sometido a una fuerza de compresión
igual a la componente vertical de la fuerza en los cables deformados (Nodo 10, Figura 67). El equilibrio de las fuerzas verticales en el Nodo 1 (Figura 6-7) requiere que la fuerza
de compresión del elemento 1 se reste de la fuerza de corte de 31,5 kip (140 kN) aplicada
en el nodo. En consecuencia, los tirantes verticales y bielas inclinadas del modelo se
diseñan para la fuerza de corte en la sección D reducida por la componente vertical de la
fuerza de pretensado en los cables deformados.
Otra diferencia importante entre ambos modelos se debe al enfoque usado para modelar el
efecto de las tensiones de adherencia sobre las fuerzas en los tirantes. De manera
conservadora se asumió que la fuerza en los tirantes es igual a la fuerza mínima que se
puede desarrollar en el nodo más próximo al borde de la viga. El resultado de seguir este
enfoque fue una diferencia de 24 kip (107 kN) entre las fuerzas FD1 y FD2 en el Nodo 9 del
modelo con cables deformados (Figura 6-7). Esta fuerza de 24 kip, paralela a la orientación
de los cables deformados, es resistida por los elementos 11 y 12 del modelo (Figura 6-7).
Como la fuerza de compresión en estos dos elementos tiene una componente vertical,
provoca un aumento de la tracción en el Tirante 9 (Figura 6-7) y en consecuencia una
mayor demanda de armadura vertical. En el modelo con cables horizontales (Figura 6-4)
los efectos de la adherencia no son tan significativos dada la interacción entre las bielas
inclinadas y los tirantes horizontales. Aunque parecería que los estribos adicionales
implican mayores costos en la alternativa con cables deformados, el análisis mediante
modelo de bielas y tirantes sólo examina la condición última. La elección final de las
armaduras se debe hacer considerando las tensiones en el momento de la relajación y bajo
niveles de cargas de servicio.

182

<!-- p. 21 -->

Ejemplo 6: Viga pretensada

Notación

Aps sección de armadura pretensada
Ast sección de armadura no pretensada
Av,min mínima sección de armadura de corte en una distancia s
b ancho de la viga
db diámetro de un cable o barra
fb resistencia efectiva de apoyo del hormigón
fcu resistencia efectiva a la compresión del hormigón en una biela o zona nodal
fse tensión efectiva en la armadura pretensada
fy resistencia a la fluencia de la armadura
f’ c resistencia a la compresión del hormigón
Fns resistencia nominal de una biela
Fnt resistencia nominal de un tirante
ht altura de un tirante
lbp longitud de la placa de apoyo
ld longitud de desarrollo de las barras
ldh longitud de desarrollo de un gancho
Mu momento flector factoreado en el borde de una región D
Vu esfuerzo de corte factoreado en el borde de una región D
wu carga distribuida factoreada que actúa sobre una viga
wst ancho de una biela
α ángulo de inclinación de una biela
βs factor que toma en cuenta los efectos de la fisuración y la armadura de
confinamiento sobre la resistencia efectiva a la compresión del hormigón de una
biela
βn factor que toma en cuenta los efectos del anclaje de los tirantes sobre la resistencia
efectiva a la compresión del hormigón de una zona nodal
∆fp aumento de tensión en los tendones de pretensado debido a las cargas factoreadas
φ factor de reducción de la resistencia

183

<!-- p. 22 -->

Ejemplo 6: Viga pretensada

Referencias

ACI 318-02: Building Code Requirements for Reinforced Concrete and Commentary. ACI
Committee 318, American Concrete Institute, Farmington Hills, Michigan 2002.

Peterman, R., Ramirez, J., y Olek, J., "Influence of flexure-shear cracking on strand
development length in prestressed concrete members," PCI Journal, v. 45, n. 5, Sep. 2000,
pp. 76-94.

Ramirez, J., "Strut-and-Tie Shear Design of Pretensioned Concrete," ACI Structural
Journal, v. 91, n. 5, Sep.-Oct. 1994, pp. 572-578.

184
