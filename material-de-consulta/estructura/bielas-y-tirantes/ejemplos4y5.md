---
type: libro
title: "Ejemplos4y5"
author: "lauri"
categoria: "ESTRUCTURA"
paginas: 34
extraccion: "texto"
fuente: "local:E:/MATERIAL DE CONSULTA/ESTRUCTURA/BIELAS Y TIRANTES/Ejemplos4y5.pdf"
convertido: 2026-10-16
---

# Ejemplos4y5

> Texto extraído de `ESTRUCTURA\BIELAS Y TIRANTES\Ejemplos4y5.pdf` (34 páginas, texto). El PDF original está en el disco E: (MATERIAL DE CONSULTA); `<!-- p. N -->` marca el inicio de cada página.

<!-- p. 1 -->

Ejemplo 4: Viga de gran altura con una abertura

Lawrence C. Novak, SE

Heiko Sprenger

Sinopsis

El problema elegido para este trabajo, es decir una viga de gran altura con una abertura
rectangular, representa un buen ejemplo de la aplicación de modelos de bielas y tirantes
para estructuras de hormigón armado. Debido a que la totalidad de la viga constituye una
región D, este ejemplo demuestra los principios y métodos que se pueden usar para
resolver una gran variedad de problemas. El Ejemplo #4 ha sido ampliamente evaluado de
acuerdo con los requisitos del Apéndice A de ACI 318-02.

Lawrence C. Novak, SE es Miembro Asociado de Skidmore, Owings & Merrill LLP, 224
South Michigan Ave., Chicago, IL 60604. También es miembro de ACI, SEAOI y ASCE,
y miembro votante de ACI-209.

Heiko Sprenger se graduó recientemente de la Universidad de Stuttgart y es Ingeniero
Pasante en Skidmore, Owings & Merrill LLP, 224 South Michigan Ave., Chicago, IL
\60604.

<!-- p. 2 -->

Ejemplo 4: Viga de gran altura con una abertura

1 Sistema

La viga de gran altura con una abertura (Figura 4.1) se diseñó de acuerdo con el Apéndice
A de ACI 318-02 − Modelos de Bielas y Tirantes. El sistema en su conjunto se considera
una región D debido a la presencia de discontinuidades de fuerzas y geométricas.
Para simplificar los cálculos el peso propio de la estructura se ha considerado aumentando
adecuadamente la carga puntual aplicada.
Materiales:
Hormigón − Resistencia a la compresión especificada del hormigón
'  N 
f c = 4500psi  2   31mm 
Acero − Resistencia a la fluencia especificada de la armadura no pretensada

 N 
f y = 60.000psi  414 2 
 mm 

15712" 315"
(4000 mm) (8000 mm)

2312"
(600 mm)
F = 450 kips (2000 kN)
34"mm)
78 mm)
(2000 9812" (2500
mm) 34"mm)
78 23614" (6000 (2000 4"mm)
34"mm) 1373(3500
78 (2000
133 4" 783 4" 15712" 8812" 1473 4" 133 4"
(350 mm) (2000 mm) (4000 mm) (2250 mm) (3750 mm) (350 mm)

500"
(12700 mm)
153 4" 153 4"
(400 mm) (400 mm)

Ancho de la viga = Ancho de la placa de apoyo = 12" (305 mm)

Figura 4-1: Geometría de la viga de gran altura

130

<!-- p. 3 -->

Ejemplo 4: Viga de gran altura con una abertura

2 Modelo de bielas y tirantes

2.1 Elección del modelo

La estructura se comporta como una viga de gran altura superior que se extiende entre
columnas inclinadas apoyadas sobre una viga de gran altura inferior. En base al
comportamiento anticipado se desarrolló el modelo de bielas y tirantes ilustrado en la
Figura 4-2. Los modelos de bielas y tirantes se pueden basar en el criterio del ingeniero o
bien en un análisis por elementos finitos del flujo de las cargas. En general un modelo de
bielas y tirantes se elige de manera tal que los tirantes estén ubicados donde el ingeniero
prevé que se dispondrá la armadura principal por motivos constructivos (en este caso por
encima y por debajo de la abertura y en el fondo de la viga de gran altura inferior).
Nota: De acuerdo con la Sección RA.1 de ACI 318-02 − Definiciones − Región D − en una
región D el menor ángulo permitido entre una biela y un tirante es de 25 grados. En el
modelo seleccionado el menor ángulo es de 34 grados.

55" 10212" 10212" 55"
(1400 mm) (2600 mm) (2600 mm) (1400 mm)
Nodo A F1 = F2

C0
4"mm) C1 C2
743(1900 T1

mm)
8612" C3 C4
(2200

T2 T3 C5 C6 C12 4"mm) C11 C7 C8 C9 C10
T4 T5 T6
T8 T9 T10 703(1800 T7

Nodo B Nodo C
R1 R2
105" 105" 105" 783 4" 783 4"
(2667 mm) (2667 mm) (2667 mm) (2000 mm) (2000 mm)

Figura 4-2: Geometría del modelo de bielas y tirantes seleccionado

131

<!-- p. 4 -->

Ejemplo 4: Viga de gran altura con una abertura

2.2 Fuerzas

Para las fuerzas externas determinar las reacciones planteando momentos respecto del
apoyo inferior izquierdo (ver Figura 4-1).
M = 450 kips ⋅ 157,5"− R 2 ⋅ 472,5"
→ R 2 = 150 kips (667 kN)
→ R 1 = 300 kips (1333 kN)

F1 = F2 = 225 (2000)

Nodo A

C2= (1685) C0 = 310 381
381 (1379) (1685) =
C1
T1 = 167 (743)

C4
\= (1183) 266 266
\= (1183) C3
C5 = 167 (743)
C12 = T2 = 143 (636) T3 = 34 (151) C5 = 77 (342) C11
75 75 224 225 (596) (596) (596) = = = = 224 150 134 134 (996) (333) 134 (333) = = (1000) = T5 T4 (667) (996) C7 C8 C9 T6 C10= T7 = 111 (494) T8 = 222 (998) T9 = 333 (1481)
T10 = 167 (743)
Nodo B Nodo C

R1 = 300 (1333) R2 = 150 (667)

Figura 4-3: Fuerzas (C - Compresión, T - Tracción) del modelo de bielas y tirantes
determinadas según el método de los nudos (en kips, kN entre paréntesis)

3 Cálculos

Factor de reducción de la resistencia de acuerdo con el Capítulo 9.3.2.6 de ACI 318-02:
φ = 0,75

3.1 Verificación de la resistencia de apoyo

Nota: El ancho de la placa de apoyo es igual al ancho de la viga.
ACI 318-02, Ecuación A-1:

132

<!-- p. 5 -->

Ejemplo 4: Viga de gran altura con una abertura

φ⋅ Fn ≥ Fu

y ACI 318-02, Ecuación 10.17.1
Fn = 0,85 ⋅ f c' ⋅ A

con
f c' = 4500psi
→ Fn = 3825psi ⋅ A

Placa en el nodo A
P = 450 kips

A = 23 1 "⋅ 12" = 282in 2 2
→ 0,75 ⋅ 3825psi ⋅ 282in 2 = 809kips ≥ 450kips ( 3598kN ≥ 2000kN ) → Verifica

Placa en los nodos B y C
R 1 = 300kips ≥ 150kips = R 2

A = 15 3 "⋅ 12" = 189in 2 4
→ 0,75 ⋅ 3825kips ⋅ 189in 2 = 542kips ≥ 300kips ( 2410kN ≥ 1333kN ) → Verifica

Nota: Típicamente las verificaciones de los nodos del Apéndice A tendrán prioridad sobre
las verificaciones de los apoyos del Capítulo 10 de ACI 318-02.

3.2 Tirantes

ACI 318-02, Ecuación A-1
Fu φ⋅ Fn ≥ Fu → Fn =
φ

con la Ecuación A-6 de ACI 318-02 − resistencia nominal de un tirante
Fnt = A st ⋅ f y + A ps ⋅ (f se + ∆ f p )
A ps = 0 ( nopretensada ) → Fnt = A st ⋅ f y

además
yf = 60.000psi = 60ksi

133

<!-- p. 6 -->

Ejemplo 4: Viga de gran altura con una abertura

 
Fnt Fu Fu Fu  Fu  → A st, req = = = =  
 f y φ⋅ f y 0,75 ⋅ 60ksi 40ksi  276 N 2  mm 

Tabla 4-1: Armaduras de los tirantes
Fu Fu Ast, req Ast/barra No. de Ast, prov Distribución
[kips] [kN] [in.2] Barras [in.2] barras [in.2]
T1 = 167 744 3,72 #10 1,27 4 5,08 4#10
T2 = 143 636 3,18 #8 0,79 4 3,16 4#8
T3 = 34 151 0,75 #8 0,79 4 3,16 4#8
T4 = 75 333 1,66 #4 0,20 10 2,00 10#4 @ 18 in.
T5 = 75 333 1,66 #4 0,20 10 2,00 10#4 @ 18 in.
T6 = 150 667 3,33 #4 0,20 18 3,60 18#4 @ 9 in.
T7 = 111 493 2,46 #10 1,27 6 7,62 6#10
T8 = 222 987 4,93 #10 1,27 6 7,62 6#10
T9 = 333 1480 7,40 #10 1,27 6 7,62 6#10
T10 = 167 741 3,70 #10 1,27 6 7,62 6#10

La Tabla 4-1 indica los tirantes Ti junto con las fuerzas (ver Figura 4-3), la sección de
armadura requerida, el tamaño de barra con la sección de armadura correspondiente a cada
barra, el número de barras, la sección de armadura provista y la manera en que se
distribuyen las barras en cada tirante.

3.3 Bielas

ACI 318-02, Ecuación A-1
φ⋅ Fn ≥ Fu

con la Ecuación A-2 de ACI 318-02 − resistencia nominal a la compresión de una biela sin
armadura longitudinal
Fns = f cu ⋅ A c

y la Ecuación A-3 de ACI 318-02 para la resistencia efectiva a la compresión del hormigón
de una biela
f cu = 0,85 ⋅β s ⋅ f´c

con
fc' = 4500 psi
βs = 0,60 ⋅ λ (sin armadura que satisfaga A.3.3 del Apéndice A de ACI 318-02)

134

<!-- p. 7 -->

Ejemplo 4: Viga de gran altura con una abertura

λ = 1,0 para hormigón de peso normal (ACI 318-02, Capítulo 11.7.4.3)

A c,req = w s,req ⋅ 12"

→ f cu = 2869psi = 2,869ksi
→φ⋅ Fn = 0,75 ⋅ Fn = 0,75 ⋅ 2,869ksi ⋅ A c ≥ Fu

 
Fu Fu  Fu  → A c,req ≥ =   0,75 ⋅ 2,869ksi 2,152ksi kN  14,85 2   mm 

 
Fu Fu  Fu  → w s,req ≥ =   2,152ksi ⋅ 12" kips kN 25,82  4525,9 
in  mm 
El factor βs = 0,60λ se toma de manera conservadora ya que es posible que se desarrollen
bielas en forma de botella. Si la armadura satisface A.3.3 del Apéndice A de ACI 318-02
(resistencia a la fuerza de tracción transversal en la biela) se podría usar βs = 0,75.
La Tabla 4-2 indica las bielas Ci junto con las fuerzas (ver Figura 4-3) y los anchos
requeridos y provistos para las bielas con un espesor de 12 in. Si ws, prov "verifica" significa
que la geometría del modelo provee área suficiente.

Tabla 4-2: Propiedades de las bielas
Fu Fu Ws, req Ws, prov
[kips] [kN] [in.] [in.]
C1 = 381 1695 15 verifica
C2 = 381 1695 15 verifica
C3 = 266 1185 10 verifica
C4 = 266 1185 10 verifica
C5 = 77 343 3 4", verifica
C6 = 167 741 6 verifica
C7 = 225 1000 9 27½", verifica
C8 = 134 595 5 verifica
C9 = 134 595 5 verifica
C10 = 134 595 5 verifica
C11 = 224 997 9 verifica
C12 = 224 997 9 verifica

135

<!-- p. 8 -->

Ejemplo 4: Viga de gran altura con una abertura

3.4 Nodos

3.4.1 Generalidades

De acuerdo con el Capítulo A-1 de ACI 318-02, el nodo en el punto A es un nodo Tipo CC-C compuesto por tres bielas; por lo tanto βn = 1,0 (ACI 318-02, Sección A.5.2.1). Los
nodos en los puntos B y C son nodos Tipo C-C-T ya que cada uno de ellos ancla un tirante
y por lo tanto para estos nodos βn = 0,8 (ACI 318-02, Sección A.5.2.2).

ACI 318-02, Ecuación A-7 − resistencia nominal a la compresión de una zona nodal
Fnn = fcu ⋅ An
con la Ecuación A-8 de ACI 318-02 − tensión efectiva calculada en la cara de una zona
nodal
φ⋅ f cu = (0,75) ⋅ 0,85 ⋅β n ⋅ f´c

y ACI 318-02, Ecuación A-1
φ⋅ Fn ≥ Fu

3.4.2 Nodo A

1F = 225kips
C 0 = 310kips
C1 = 383kips

69,8
θ = arctan = 35,92º
96,4
β n = 1,0

136

<!-- p. 9 -->

Ejemplo 4: Viga de gran altura con una abertura

2312"
(600 mm)

l b= 113 4"
(298 mm)

ZONA NODAL F1

C0 10" mm)
\=t
w (254 lb sin φ
C1

wt cos φ w 35,92° s

Figura 4-4: Geometría del nodo A

w " = l b = 11 3 1F 4
w C 0 = 10" (altura aproximada del bloque de compresión C0)
w C1 = w s = l b sin θ+ w t cos θ = 15 in.

A F1 = 11 3 4 "⋅ 12" = 141in 2
A C 0 = 10"⋅ 12" = 120in 2
A C1 = 15"⋅ 10" = 150in 2

2397kN ) Fnn,F1 = 0,85 ⋅ 1,0 ⋅ 4500psi ⋅ 141in 2 = 539kips (
2042kN ) Fnn,C 0 = 0,85 ⋅ 1,0 ⋅ 4500psi ⋅ 120in 2 = 459kips (
2553kN ) Fnn,C1 = 0,85 ⋅ 1,0 ⋅ 4500psi ⋅ 150in 2 = 574kips (

0,75 ⋅ 539kips = 404kips ≥ 225kips = F1 (1797kN ≥ 1000kN = F1 )
0,75 ⋅ 459kips = 344kips ≥ 310kips = C 0 (1530kN ≥ 1379kN = C 0 )
0,75 ⋅ 574kips = 431kips ≥ 383kips = C1 (1917kN ≥ 1704kN = C1 )

→El Nodo A es aceptable.

137

<!-- p. 10 -->

Ejemplo 4: Viga de gran altura con una abertura

3.4.3 Nodo B

55,98°
Resultante C7,8= 319 kips 69,68°
(1419kN)
C7= 225 kips 34,02 (1000 kN)

C8= 134 kips
(596 kN)

wt cos (phi)
ws
lbsin (phi)

GANCHO NORMAL
(TIP.) ZONA NODAL EXTENDIDA
C7,8

11" mm) T7
\=t
w (279 69,68°

ZONA NODAL
R1

5 78" 15 3 4" 2"
(149 mm) (400 mm) (51 mm)

212" 5" 16 18"
(64 mm) (127 mm) (409 mm)

LAS BARRAS TRACCIONADAS DEBEN
DESARROLLARSE DENTRO DE ESTA ZONA
Figura 4-5: Geometría del nodo B

A C 7,8 = 18 1 2 "⋅ 12" = 222in 2

2571kN ) Fnn,R 1 = 0,85 ⋅ 0,8 ⋅ 4500psi ⋅ 189in 2 = 578kips (
1757kN ) Fnn,T1 = 0,85 ⋅ 0,8 ⋅ 4500psi ⋅ 129in 2 = 395kips (
3020kN ) Fnn,C 7,8 = 0,85 ⋅ 0,8 ⋅ 4500psi ⋅ 222in 2 = 679kips (

0,75 ⋅ 578kips = 434kips ≥ 300kips = R 1 (1930kN ≥ 1333kN = R 1 )
0,75 ⋅ 395kips = 296kips ≥ 111kips = T7 (1317kN ≥ 494kN = T7 )
0,75 ⋅ 679kips = 509kips ≥ 319kips = C 7,8 ( 2264kN ≥ 1418kN = C 7,8 )

138

<!-- p. 11 -->

Ejemplo 4: Viga de gran altura con una abertura

R1 = 300 kips
T7 = 111 kips
C7,8 = 319 kips
θ = 69,68º
βn = 0,8

w R 1 = l b = 15 3 4 "
w T7 = w t = 2 ⋅ 2"+ 3 ⋅ 1 1 4 "+ 2 ⋅ 1 1 2 " = 10 3 4 "
w C 7,8 = w s = l b sin θ+ w t cos θ = 18 1 2 "

A R 1 = 15 3 4 "⋅ 12" = 189in 2
A T7 = 10 3 4 "⋅ 12" = 129in 2

3.4.4 Nodo C

ws wt cos θ

lb sin θ
GANCHO NORMAL
ZONA NODAL EXTENDIDA (TIP.)

C12

T10 11" mm)
\=
wt(279 41,99°

ZONA NODAL
R2
6" 15 3 4" 5 7 8"
(152 mm) (400 mm) (149 mm)

20 18" 5" 2 12"
(511 mm) (127 mm) (64 mm)
LA ARMADURA DE TRACCION SE DEBE
DESARROLLAR EN ESTA ZONA

Figura 4-6: Geometría del nodo C

139

<!-- p. 12 -->

Ejemplo 4: Viga de gran altura con una abertura

R2 = 150 kips
T10 = 167 kips
C12 = 224 kips
θ = 41,99º
βn = 0,8

w R 2 = l b = 15 3 4 "
w T10 = w t = 2 ⋅ 2"+ 3 ⋅ 1 1 4 "+ 2 ⋅ 1 1 2 " = 10 3 4 "
w C12 = w s = l b sin θ+ w t cos θ = 18 1 2 "

A R 2 = 15 3 4 in ⋅ 12in = 189in 2
A T10 = 10 3 4 in ⋅ 12in = 129in 2
A C12 = 18 1 2 in ⋅ 12in = 222in 2

2571kN ) Fnn,R 2 = 0,85 ⋅ 0,8 ⋅ 4500psi ⋅ 189in 2 = 578kips (
1757kN ) Fnn,T10 = 0,85 ⋅ 0,8 ⋅ 4500psi ⋅ 129in 2 = 395kips (
3020kN ) Fnn,C12 = 0,85 ⋅ 0,8 ⋅ 4500psi ⋅ 222in 2 = 679kips (

0,75 ⋅ 578kips = 434kips ≥ 150kips = R 2 (1930kN ≥ 667kN = R 2 )
0,75 ⋅ 395kips = 296kips ≥ 167kips = T10 (1317kN ≥ 743kN = C10 )
0,75 ⋅ 679kips = 509kips ≥ 224kips = C12 ( 2264kN ≥ 997kN = C12 )

3.4.5 Longitud de desarrollo

El nodo B es determinante porque en este nodo la longitud de anclaje para el gancho es
menor que la longitud de anclaje en el nodo C.
De acuerdo con la Ecuación 12.5.2 de ACI 318-02, la longitud de desarrollo, ldh, de un
gancho normal es:
0,02 ⋅β⋅λ⋅ f y
l dh = ⋅ d b
f c´

140

<!-- p. 13 -->

Ejemplo 4: Viga de gran altura con una abertura

Siguiendo el Capítulo 12.5.4 de ACI 318-02, el cual para un recubrimiento más allá del
gancho menor que 2,5 in. requiere una separación de los estribos no mayor que 3db a lo
largo de ldh, y estando el primer estribo a una distancia menor o igual que 2db de la parte
exterior del codo, según el Capítulo 12.5.3(a) de ACI 318-02 ldh se puede multiplicar por
0,7 y por lo tanto se reduce a
l dh = 0,7 ⋅ 22 3 " = 16" (404mm) 4
La longitud de anclaje es suficiente para ambos nodos siendo la
w t
l a, NodoB = 2 + 15 3 "+ 5 7 "− 2 1 "− 5" = 16 1 " (409mm) tan 69,68º 4 8 2 8

w t
l a, NodoC = 2 + 15 3 "+ 5 7 "− 2 1 "− 5" = 20 1 " (510mm) tan 41,99º 4 8 2 8

l dh = 16" ≤ 16 1 " (404mm ≤ 409mm) 8
→Los nodos B y C son aceptables.

ldh se podría reducir aún más multiplicando por la relación entre As,req y As,prov (3,7/7,62 =
0,49) según el Capítulo 12.5.3(d) de ACI 318-02. No hemos considerado esta reducción
adicional de ldh ya que no alteraría los resultados.

3.5 Mínima armadura de temperatura y retracción

ACI 318-02, Ecuación 7.12.2.1(b) − la relación entre la sección de armadura y la sección
bruta de hormigón es
A s ρ = = 0,0018
A C

Adoptamos una armadura de barras #4 con una separación de 18 in., ya que de acuerdo con
el Capítulo 7.12.2.2 de ACI 318-02 la separación no debe ser mayor que 18 in., con Ast =
0,20 in.2. Siendo el ancho del muro 12 in.:

2 ⋅ 0,20in 2
ρ = = 0,0019 ≥ 0,0018 → Verifica
18"⋅ 12"
Conclusión: Disponer como mínimo barras #4 cada 18 in. en cada dirección y cada cara.

141

<!-- p. 14 -->

Ejemplo 4: Viga de gran altura con una abertura

3.6 Mínima armadura superficial

Verificando los requisitos del Capítulo A.3.3 de ACI 318-02, se colocará exclusivamente
la armadura horizontal y vertical de retracción y temperatura indicada en 3.2. Si la
profundidad efectiva de una viga es mayor que 36 in., de acuerdo con el Capítulo 10.6.7 de
ACI 318-02 es necesario disponer armadura superficial. Esta armadura se debe distribuir
en una distancia d/2, con una separación no mayor que el menor valor entre ssk > d/6, ssk >
12 in. y ssk > 1000 Ab / (d−30):
1000 ⋅ 0,31in 2
\= 7 1 " → s sk ≥ 7 1 " (193mm) 70 1 "− 30'' 2 2 4
Por lo tanto, para la parte inferior de la viga de gran altura y la parte sobre la abertura en
una profundidad de 37 in., cambiaremos la armadura horizontal consistente en barras #4
con separación de 18 in. por barras #5 a 7½ in.

4 Disposición de las armaduras

2 #7 4#10
(colocar en dos filas)
4 filas de diagonal #5
(5 juegos asi)
\#5 a 7 12" sobre L = 63" #4 a 18" la abertura (a menos que se
especifique lo contrario)

2 #7
\#4 a 18"
(a menos que
se especifique
lo contrario)

gancho normal
(típ.)
5 filas de
3 filas de #4 a 4"
\#4 a 4"
4 filas de #5 a 4 #8 6 #10 9 filas de
7 12" sobre el (colocar en 2 filas) (colocar en 2 filas) #4 a 9"
fondo de recubrim.
la viga 1 12" (típ.)

Figura 4-7: Disposición final de las armaduras de acuerdo con
el modelo de bielas y tirantes

142

<!-- p. 15 -->

Ejemplo 5: Viga con cargas y apoyos indirectos

Wiryanto Dewobroto

Karl-Heinz Reineck

Sinopsis

El diseño incorrecto de los apoyos indirectos ha provocado una variedad de daños
estructurales y prácticamente ha llevado a la falla algunas vigas de hormigón estructural.
La mayoría de los códigos, incluyendo el ACI 318, no tratan este caso adecuadamente. Sin
embargo, los modelos de bielas y tirantes conducen casi automáticamente a reforzar
correctamente estas regiones de discontinuidad críticas. Este ejemplo combina apoyos
indirectos con cargas aplicadas de manera indirecta, y demuestra la aplicación de modelos
de bielas y tirantes de acuerdo con el Apéndice A de ACI 318-2002.

Wiryanto Dwobroto es profesor de Ingeniería Civil en la Universidad de Pelita Harapan,
Indonesia. Obtuvo su título de Ingeniero Civil de la Universidad de Gadjahmada en 1989.
Luego de su graduación trabajó en una empresa de consultores en ingeniería y posee
experiencia en el diseño y supervisión de numerosas estructuras, especialmente edificios
industriales en altura y puentes. En 1998 obtuvo su maestría en Ingeniería Estructural de la
Universidad de Indonesia. De mayo a julio de 2002 fue investigador invitado en la
Universidad de Stuttgart, alemania.

Karl-Heinz Reineck obtuvo su título de Ingeniero y Doctor en Ingeniería de la
Universidad de Stuttgart. Es investigador y docente en el Instituto para el Diseño
Conceptual y Estructural de Estructuras Livianas de la Universidad de Stuttgart. Sus
investigaciones abarcan el diseño mediante modelos de bielas y tirantes, el diseño al corte
y el detallado del hormigón estructural. Preside el Comité conjunto ASCE-ACI 445-1 y es
miembro del Grupo de Trabajo "Diseño Práctico" de fib.

<!-- p. 16 -->

Ejemplo 5: Viga con cargas y apoyos indirectos

1 Geometría y cargas

La viga T ilustrada en la Figura 5-1 está apoyada indirectamente en el apoyo B por medio
de una viga de transferencia ilustrada en el corte II-II. Tampoco las cargas están aplicadas
directamente en el alma, sino que son transferidas por las vigas ilustradas en el corte I-I.
Las cargas están aplicadas simétricamente, por lo cual no se induce torsión.

300 2000 1600 2000
(11,81 in) (78,74 in.) (62,99 in.) (78,74 in.) in.)
2 Fu 2 Fu 150 (5,9
in)
in.)
600 450 (17,7 (23,62
A 200 (7,87 in.) 200 B
2200 1400 1800 200
(86,61 in) (55,12 in) (70,87 in)

Corte I-I Corte II-II
200 550 700 550 200 700
in.) (7,87 in) (27,56 in)
150 Fu Fu (5,9
in.)
in.)
600 450 (17,7 (23,62 775 250
(30,51 in.) (9,84 in.) uF uF
2200 200 1800 200
(86,61 in.) (7,87 in) (70,87 in) (7,87 in)

Figura 5-1: Miembro con cargas factoreadas y apoyos indirectos

Especificaciones para el diseño:

Carga factoreada: Fu = 160 kN (36 kips)
Hormigón: fc' = 31,6 MPa (4580 psi)
Armaduras: fy = 500 MPa (72.500 psi)

144

<!-- p. 17 -->

Ejemplo 5: Viga con cargas y apoyos indirectos

2 Procedimiento de diseño

El diseño se basa en un Modelo de Bielas y Tirantes de acuerdo con el Apéndice A de ACI
318-02 y se realiza siguiendo los pasos siguientes:
− Paso 1: Análisis
− Paso 2: Diseño a flexión de la viga principal y cálculo del brazo de palanca interno
− Paso 3: Diseño de los estribos para la viga principal y cálculo del ángulo de las bielas
en el alma
− Paso 4: Verificación de la longitud de anclaje en los nodos A y B
− Paso 5: Diseño de la viga que transfiere las cargas a la viga principal
− Paso 6: Diseño de la viga que soporta la viga principal
− Paso 7: Disposición de las armaduras

Nota editorial: Los cálculos se realizan en unidades del SI; los resultados principales
también se presentan entre paréntesis en unidades inglesas.

3 Cálculos

3.1 Paso 1: Análisis

La Figura 5-2 ilustra los diagramas de corte y momento flector correspondientes a la viga
principal.

2000 1600 2000
(78,74 in.) (63 in.) (78,74 in.)

320 B
A (72 kips) 320 VU (kN)
(72 kips)

A B
M (kNm)
640 U
(5669,3 kips-in)

Figura 5-2: Corte y momento flector en la viga principal
(1 kN = 0,2248 kips; 1 kN-m = 8,8496 kips-in.)

145

<!-- p. 18 -->

Ejemplo 5: Viga con cargas y apoyos indirectos

Vigas que transfieren la carga a la viga principal (Figura 5-1, Corte I-I):

Mu = 144 kN-m (1275 kips-in.)
Vu = 160 kN (36 kips)
Para la viga que soporta la viga principal en el apoyo B (Figura 5-1, Corte II-II) son
válidos los mismos valores.

3.2 Paso 2: Diseño a flexión de la viga principal

Usamos una distribución rectangular equivalente de las tensiones en el hormigón en base a
la Sección 10.2.7:
f c´ = 31,6MPa →β1 = 0,85 − 0,005(31,6 − 27,6) / 6,89 = 0,82

0,638f c´β1 600 ρ max = 0,75 ρ b = = 0,018
f y 600 + f y
ρ max f y
ωmax = ´ = 0,285
f c

M u 640 M n ≥ = = 711,1 kN-m (6290 kips-in.)
φ 0,9

Asumimos que la zona comprimida está dentro del ala (Figura 5-3) y que el acero entrará
en fluencia.

700
150 εc 0,85fc
c
Fc
z d=525 a=150 Fs
Tensión Deformación
250

Figura 5-3: Distribución de las tensiones y deformaciones a mitad de tramo
de la viga principal (1 mm = 0,03937 in.)

M n 711,1*10 6 2 ´ = 2 = 0,117 →ω = 0,126 \< ωmax = 0,285
bd f c 700*525 *31,6

f c´ 31,6 2 2 A s = ω bd = 0,126* *700*525 = 2926mm (4,54in )
f y 500

146

<!-- p. 19 -->

Ejemplo 5: Viga con cargas y apoyos indirectos

usar 6 ∅ 25 A s = 2945mm 2 (4,56in 2 )

Verificamos la hipótesis:
A s ⋅ f y 2926*500
a = = = 79mm \< h f = 150mm Verifica
0,85 ⋅ f c ⋅ b 0,85*31,6*700
A s ⋅ f y
a = = 3,11in. \< h f = 5,91in.
0,85 ⋅ f c ⋅ b

En la figura 5-4 se ilustra la disposición de las barras principales. (1 mm = 0,03937 in.)

20
10

6060 6 diam.25

72,5
\=
1 250 30 d

Figura 5-4: Distribución propuesta para las barras de la viga principal
(1 mm = 0,03937 in.)

Los valores actualizados para la profundidad efectiva y el brazo de palanca interno son los
siguientes:
d = h − d1 = 600 − 72,5 = 527,5 mm (20,78 in.) > 525 mm (20,67 in.)
z = jd = d − 0,5a = 527,5 − (0,5 * 79) = 488 mm (19,21 in.)
j = z / d = 0,925

3.3 Paso 3: Diseño de los estribos para la viga principal

Dimensionamos los estribos de acuerdo con el Capítulo 11 de ACI 318. Luego obtenemos
el ángulo θ para las bielas inclinadas del alma de manera de poder determinar el modelo de
bielas y tirantes para las regiones D.
φVn ≥ Vu

Vu 320 Vn ≥ = = 427kN (96kips)
φ 0,75
Vn = Vc + Vs

147

<!-- p. 20 -->

Ejemplo 5: Viga con cargas y apoyos indirectos

Para miembros sometidos exclusivamente a corte y flexión la Ecuación 11.3.1.1 da:

Vc = 0,17 f c´ b w d

Vc = 0,17* 31,6 *250*527,5 = 126.024 N = 126 kN (28,3kips)

Con la ecuación alternativa 11.3.2.1 se obtiene:
 ´ Vu d  ´ Vc =  0,16 f c + 17 ρ w  b w d ≤ 0,29 f c b w d
 M u 

donde
Vu d 320*0,5275 = = 0,2637 ≤ 1,0
M u 640

A s 2945 ρ w = = = 0,0223
b w d 250*527,5

de manera que

0,16 31,6 + 17*0,0233*0,2637 250*527,5 ≤ 0,29 31,6 *250*527,5 Vc = ( )
Vc = 132kN ( 29,67kips ) ≤ 215kN (48,32kips)

Para diseñar los estribos usamos Vc de la ecuación alternativa:
Vs = Vn − Vc
Vs = 427 − 132 = 295kN (66,3kips)
\< 0,68 f c´ b w d = 504kN (113,3kips)
\> 0,34 f c´ b w d = 252kN (56,6kips) →≤s d / 4 = 131mm(5,16in)

A v Vs 295.000 mm = = = 1,12 mm2 = 1120 mmm 2 (0,0441 inin2 )
s f y ⋅ d 500*527,5

 A v  mm usar estribos φ 10 con separación de 125 mm → 2 in 2 = 1250 m (0,0492 in )  
 s  prov

Ahora que conocemos la cantidad de estribos podemos calcular el ángulo θ que forman las
bielas inclinadas en el alma del modelo reticulado. El diagrama de cuerpo libre ilustrado en
la Figura 5-5 muestra que la fuerza de corte en la región B debe ser tomada por las fuerzas
en los estribos en la longitud (z cot θ):

148

<!-- p. 21 -->

Ejemplo 5: Viga con cargas y apoyos indirectos

Vn = (A v /s)f y z cot θ

y en base a esto el ángulo θ se puede calcular de la siguiente manera:
s Vn 1 427.000 cot θ = ⋅ = * = 1,5625 →θ = 32,6º
A v f y z 1,12 500*488

z = 488 mm
θA θ Vn
d1= 72,5 mm

Vn (Av / s) fy z cot θ
Figura 5-5: Campos de compresión para las bielas inclinadas (1 mm = 0,03937 in.)

3.4 Paso 4: Verificación de las longitudes de anclaje en los nodos A y B

3.4.1 Verificación de la longitud de desarrollo de las barras longitudinales

De acuerdo con la Sección 12.11 de ACI 318-02, la longitud de desarrollo de las barras
debe satisfacer los siguientes requisitos (ver también la Figura 5-6):
\1. Al menos un tercio de la armadura longitudinal se debe extender sobre la misma cara
del miembro hacia el apoyo en una distancia mayor o igual que 150 mm.
\2. En los apoyos simples el diámetro de las armaduras debe ser lo suficientemente
pequeño como para que la longitud de desarrollo calculada, ld, de las barras satisfaga la
siguiente condición:
M n l d ≤ + l a
Vu

donde
Mn es la resistencia nominal al momento suponiendo que toda la armadura en la
sección (en el apoyo) está solicitada hasta la resistencia a la fluencia especificada, fy.

Por lo tanto, del Paso 2, se puede calcular como
Mn = As fy z
Mn = 2945 * 500 * 488 = 719 x 106 N-mm = 719 kN-m.
Vu es la carga de corte factoreada en la sección (Vu = 320 kN).
la en el apoyo debe ser la longitud de empotramiento más allá del centro del apoyo.
149

<!-- p. 22 -->

Ejemplo 5: Viga con cargas y apoyos indirectos

4 suspensores diam.12

l a M n / V u
280

(ld )prov la = 95,5

(a) Apoyo directo (Nodo A) (b) Apoyo indirecto (Nodo B)

Figura 5-6: Longitud de desarrollo de la barra positiva (1mm = 0,03937 in.)

Por motivos de simplicidad extendemos todas las barras hasta el apoyo.
La sección de la viga en el apoyo es similar a la Figura 5-4, el diámetro de la barra es 25
mm, por lo tanto, de acuerdo con la Sección 12.2.2, la longitud de desarrollo se puede
calcular de la siguiente manera:
 f y αβλ 
l d =   d b (in.)  ´   20 f c 
Esta ecuación se aplica para el caso de hormigón de peso normal (λ = 1,0), armadura sin
recubrimiento epoxi (β = 1,0) y barras con diámetro mayor que las barras No. 7 ó 22 mm
(α = 1,0). Para fc' = 4583 psi y fy = 72.500 psi:
 72.500*1,0*1,0*1,0 
(l d ) req =   d b = 54d b = 1350mm (53,15in)
 20 4583 

Verificación del nodo A:
M n (l d ) prov = 1,3* + l a = 1,3* 715.000 + 280 = 3185mm (98,98in.) Vu 320
(l d ) prov = 3185mm (98,98in) > (l d ) req → Verifica

Verificación del nodo B:
M n (l d ) prov = + l a = 715.000 + 95 = 2234mm (87,95in) > (l d ) req. → Verifica Vu 320

Se satisfacen los requisitos de la Sección 12.11 referidos al desarrollo de la armadura
longitudinal. Sin embargo, esto no constituye una verificación de la longitud de anclaje
directamente en el apoyo.

150

<!-- p. 23 -->

Ejemplo 5: Viga con cargas y apoyos indirectos

3.4.2 Verificación de la longitud de anclaje en el apoyo directo A

En los apoyos usamos ganchos normales en los extremos de las barras. La verificación de
la longitud de anclaje en el apoyo directo se realiza de acuerdo con la Sección 12.5.2 para
un gancho normal según A.4.3.2. De acuerdo con la Sección A.4.3.2 de ACI, la longitud de
desarrollo comienza en el punto donde el baricentro de la armadura del tirante abandona la
zona nodal extendida. Por motivos de simplicidad aquí se toma la cara interna del apoyo y,
como se ilustra en la Figura 5-7, la longitud de desarrollo (ld) así calculada es igual a 380
mm.

12db
d b

3 diam.25
3 diam.25

280 100

l dh = 380

Figura 5-7: Longitud de desarrollo en el apoyo directo (Nodo A) (1 mm = 0,03937 in.)

De acuerdo con la Sección 12.5.2 la longitud de desarrollo es:

l dh = (0,02 β λ f y / f c´ ) d b

donde
β y λ son 1,0 para hormigón de peso normal y armadura sin recubrimiento epoxi
fc' = 4580 psi
fy = 72.500 psi
por lo tanto
l dh = (0,02*1,0*1,0*72.500/ 4580)d b = 21d b

De acuerdo con la Sección 12.5.3 cuando no se requiere específicamente anclaje o
desarrollo para fy, la armadura en exceso de la requerida por análisis se puede multiplicar
por
l dh = (A s,req / A s,prov ) 21d b

Para poder calcular As,req es necesario conocer la fuerza de tracción (FsA) ilustrada en la
Figura 5-8. En base a la Sección 6.5.2.1 de las Recomendaciones FIP (1999), el ángulo θA

151

<!-- p. 24 -->

Ejemplo 5: Viga con cargas y apoyos indirectos

de la resultante del campo de compresión en forma de abanico sigue la geometría del
abanico (Figura 5-8):
cot θ A =  0,5a 1 / z + ( d1 / z + 0,5 ) cot θ 

1,2695 →θ A = 38,2º cot θ A = 125/ 488 + ( 72,5/ 488 + 0,5 ) 1,5625  =

FsA = Vn cot θ A = 427*1,2695 = 542kN (122 kips)
A s,req = FsA / f y = 542.000/500 = 1084mm 2 (1,68 in.2)

A s,prov = 6 ∅ 25(2945mm 2 ) (4,56 in.2)

Por lo tanto: l dh,req = (A s,req / A s,prov ) 21d b
l dh,req = (1084/ 2945) 21 d b = 7,73d b = 193mm \< l dh,prov = 280mm
l dh,req = 7,60in \< l dh,prov = 11,02in.

La longitud de anclaje en el apoyo directo (Nodo A) es adecuada.

z=488 mm
Vn
θA θ
1= 72,5 FsA d

n 0,5a1=125 V

Figura 5-8: Fuerza de tracción (FsA) a anclar en el apoyo (1 mm = 0,03937 in.)

3.4.3 Suspensores en el apoyo indirecto

En un apoyo indirecto el modelo de bielas y tirantes del alma es igual que el
correspondiente a los apoyos directos [Reineck (1996)]. Sin embargo, en el nodo B la
reacción de la viga principal debe ser transferida a la viga de apoyo mediante suspensores
(Figura 5-9). La sección de suspensores requerida se puede calcular de la siguiente manera:
A s = Vn / f y = 427.000/500 = 854mm 2 (1,32 in.2)
Usar 4 estribos φ 12; As = 905 mm2 (1,40 in.2)

152

<!-- p. 25 -->

Ejemplo 5: Viga con cargas y apoyos indirectos

200 100

suspensores

eje de Vn
db la biela θA
3 diam.25
3 diam.25
la= 318

Figura 5-9: Modelo y longitud de desarrollo en el apoyo indirecto (Nodo B)
(1 mm = 0,03937 in.)

3.4.4 Verificación de la longitud de desarrollo en el apoyo indirecto B

Para poder colocar los suspensores debajo de los ganchos normales en el apoyo indirecto,
la viga principal se debería extender 100 mm más allá del borde de la viga de transferencia
(Figura 5-9). Si esto no ocurre el anclaje de la armadura principal no es suficiente.
De acuerdo con la Sección A.4.3.2, la longitud de desarrollo se puede calcular a partir del
punto donde el baricentro de un tirante abandona la zona nodal extendida. Como se puede
ver en la Figura 5-9, la longitud de desarrollo (la) así calculada es igual a 318 mm. Este
valor es mayor que ldh de cálculos anteriores, por lo tanto la longitud de desarrollo en el
apoyo indirecto es adecuada.

Nota: Es evidente que los requisitos sobre longitud de anclaje de ACI 318 no distinguen
entre apoyos directos y apoyos indirectos. Sin embargo, el estado de tensiones en un
apoyo indirecto es obviamente más desfavorable porque las tensiones de tracción
transversal reducen la resistencia de la adherencia acero-hormigón. Por este motivo
la longitud de anclaje requerida debería ser mayor en el caso de un apoyo indirecto.

3.5 Paso 5: Viga que transfiere la carga a la viga principal

3.5.1 Modelo de bielas y tirantes

La totalidad de la viga de gran altura constituye una región D. A fin de satisfacer el
equilibrio en el punto C de la Figura 5-10, para las fuerzas hacia arriba de los tirantes
hacen falta suspensores. Estos estribos deben estar ubicados dentro de la intersección del
alma de la viga principal y la viga que transfiere la carga.
Se puede suponer el modelo de bielas y tirantes ilustrado en la Figura 5-10.

153

<!-- p. 26 -->

Ejemplo 5: Viga con cargas y apoyos indirectos

1800 200

Fu Fu

A θ D D B
z = 485 h = 600 θ = 29,89º
C C Fu = 160 kN

Figura 5-10: Modelo de bielas y tirantes de la viga que transfiere la carga
(1 mm = 0,03937 in.; 1 kN = 0,2248 kips)

El ángulo de la biela es mayor que 25º, por lo tanto es aceptable. Sin embargo, según A.3.3
del Apéndice A de ACI 318-2002 se requiere una cierta cantidad mínima de armadura
transversal como se calcula a continuación. Por este motivo se puede decir que este modelo
no es totalmente transparente como tal (ver también Schlaich et al. (1987)) ya que no
demuestra la necesidad de disponer armadura transversal. Por lo tanto se puede considerar
el modelo de bielas y tirantes para cargas puntuales próximas a un apoyo usado en las
Recomendaciones FIP (1999) "Diseño Práctico del Hormigón Estructural"; esto también
fue propuesto por MacGregor en la Parte 2 de esta Publicación Especial.

3.5.2 Diseño de los suspensores

Las fuerzas ascendentes en C-D deben ser resistidas por suspensores, los cuales ya fueron
calculados en la Sección 3.4.3.

3.5.3 Diseño de los tirantes

Calcular la fuerza en el tirante horizontal (Tu) en los nodos A y B de la siguiente manera:
Tu = Fu / tan θ = 160 / tan 29,9º = 278,2 kN (62,5 kips)
Tn ≥ Tu / φ = 278,2 / 0,75 = 371 kN (83,4 kips)
As = Tn / fy = 371.000 / 500 = 742 mm2 (1,15 in.2)
Usar 3 φ 19; As = 850 mm2 (1,31 in.2)

3.5.4 Resistencia de la zona nodal

La resistencia nominal a la compresión de una zona nodal es:
Fnn = fcu An

154

<!-- p. 27 -->

Ejemplo 5: Viga con cargas y apoyos indirectos

donde
fcu = 0,85 βn fc'
βn = 0,8
fcu = 0,85 * 0,8 * 31,6 = 21,5 MPa (3,12 ksi)
An = área de la zona nodal tomada perpendicularmente a la fuerza resultante, mm2

Fu

Zona nodal
w =120 t
Zona nodal extendida θ
wt cos θ Cu
lb sin θ
l b=200 w s

Figura 5-11: Zona nodal en el punto de carga (1 mm = 0,03937 in.)

Verificamos la zona nodal bajo la fuerza de apoyo (Fu) como se ilustra en la Figura 5-11)
An = b lb = 200 * 200 = 40.000 mm2 (62,0 in.2)
de manera que
Fnn = fcu An = 21,5 * 40.000 = 860.000 N = 860 kN (193 kips)
φ Fnn = 0,75 * 860 kN = 645 kN (145 kips) > Fu = 160 kN →Verifica
Verificamos la zona nodal bajo la acción de la biela (Cu):
Cu = Fu / sin θ = 160 / sin 29,9º = 321 kN (72,2 kips)
An = b ws = b (wt cos θ + lb sin θ)
\= 200 (120 cos 29,9º + 200 sin 29,9º) = 40.745 mm2 (63,15 in.2)
de manera que
Fnn = fcu An = 21,5 * 40.745 = 876.000 N = 876 kN (197 kips)
φ Fnn = 0,75 * 876 kN = 657 kN (148 kips) > Cu = 321 kN →Verifica
Para anclar las armaduras se disponen ganchos, sin verificaciones adicionales.

3.5.5 Resistencia de las bielas inclinadas

155

<!-- p. 28 -->

Ejemplo 5: Viga con cargas y apoyos indirectos

La resistencia nominal a la compresión de una biela se toma como
Fns = fcu Ac
donde
Ac = sección transversal en un extremo de la biela
Ac = b ws = b (wt cos θ + lb sin θ)
fcu = 0,85 βs fc'
βs = 0,75 (biela en forma de botella con armadura que satisface la Sección A.3.3 de
ACI 318-02)
por lo tanto
fcu = 0,85 * 0,75 * 31,6 = 20,1 MPa (2,92 ksi)
Ac = 200 (120 cos 29,9 + 200 sin 29,9) = 40.700 mm2 (63,09 in.2)
Fns = 20,1 * 40.700 = 819.000 N = 819 kN (184 kips)
φ Fns = 0,75 * 819 = 614 kN (138 kips) > Cu →Verifica

Diseñamos la armadura que atraviesa la biela diagonal de manera de satisfacer la Sección
A.3.3 del Apéndice A, ACI 318 (Figura 5-12):

Eje de la
biela

Limite de Limite la de θ la biela biela γ
Asi

si is

Figura 5-12: Armadura que atraviesa la biela diagonal

La armadura se colocará en una sola dirección (sólo vertical) formando un ángulo γ
respecto del eje de la biela diagonal de manera que γ no sea menor que 40º.
γ = 90 − θ = 90 − 29,9 = 60,1º
Para fc' ≤ 41,4 MPa (6000 psi) la cantidad de armadura se calcula de la siguiente manera:

156

<!-- p. 29 -->

Ejemplo 5: Viga con cargas y apoyos indirectos

 A si  b   ≥ 0,003
 s i  prov sin γ

de manera que
 A si  200 mm   ≥ 0,003* = 0,692 mm2 = 692 mmm 2 (0,0272 in.in.2
 s i  min sin 60,1
Probamos con estribos φ10 separados 200 mm (8 in.)
 A si  mm   = 785 m 2 (0,031 in.in.2 )
 s i  prov

3.6 Paso 6: Viga que soporta la viga principal

El diseño es similar al de la viga anterior. Observar que el modelo (Figura 5-13) está
invertido respecto de la viga que transfiere la carga.
Fu = 160 kN
C C
600
\= θ
D D h θ = 29,89º
A B
1800 200
F u F u

Figura 5-13: Modelo de bielas y tirantes para la viga que soporta la viga principal
(1 mm = 0,03937 in.; 1 kN = 0,2248 kips)

4 Disposición de las armaduras

La disposición de las armaduras se ilustra en las Figuras 5-14 a 5-16.

157

<!-- p. 30 -->

Ejemplo 5: Viga con cargas y apoyos indirectos

C C

124
200 100 152 200100
24 suspensores
diam.10-125
diam.10-125 estribos diam.22 inferior 2 indirecto estribos indirecto armadura diam.25 diam.25 3 3 apoyo apoyo con 200
B B con viga
viga la
la diam.12 de suspensores
de 4 diam.10-250 A A diam.10-250 diam.8-125 planta elevación estribo estribos estribo en en
200
Vista Vista diam.12 suspensores diam.10-250/125 apoyo) 4
estribos de(zona diam.25
6 A
las 700 diam.22 250 alas 2 Corte
las muesetran de 150 450 normales se 600
No barras
ganchos Nota:

250

700

Figura 5-14: Vista y corte de una de las vigas con apoyo indirecto
(1 mm = 0,03937 in.)

158

<!-- p. 31 -->

Ejemplo 5: Viga con cargas y apoyos indirectos

4 suspensores
diam.12 200 3 diam.19 D
3 diam.19

estribos diam.8-125 600 estribos diam.8-125

2 diam.16
2 diam.16 D
Corte B Corte D

Figura 5-15: Vista en elevación y corte de la viga que transfiere la carga
(Nodo A) (1 mm = 0,03937 in.)

4 suspensores
2 diam.16 diam.12 E 200

2 diam.16
estribos diam.8-125 600 estribos diam.8-125

3 diam.19
3 diam.19 E
Corte C Corte E

Figura 5-16: Vista y corte de la viga que soporta la viga principal (Nodo B)
(1 mm = 0,03937 in.)

5 Resumen

En la actualidad los apoyos indirectos se tratan mediante reglas para el diseño al corte, a
pesar de que representan regiones D críticas. Usando modelos de bielas y tirantes se hace
evidente la necesidad de colocar suspensores para la totalidad de la fuerza en el apoyo. El
diseño al corte del alma adyacente es igual que para un apoyo directo.
Otro tema crítico es el anclaje de la armadura longitudinal en los apoyos indirectos, ya que
en los nodos TTC las tensiones de tracción transversal reducen la capacidad de adherencia
acero-hormigón. Por lo tanto se requieren longitudes de anclajes mayores que en los
apoyos directos, nodos TCC, donde la compresión transversal favorece las tensiones de
adherencia y en consecuencia la longitud de anclaje requerida.

159

<!-- p. 32 -->

Ejemplo 5: Viga con cargas y apoyos indirectos

Notación

fc' = resistencia a la compresión especificada del hormigón
fy = resistencia a la fluencia especificada de la armadura no pretensada
d = distancia entre la fibra extrema comprimida y el baricentro de las barras
traccionadas (profundidad efectiva)
db = diámetro nominal de una barra
Fu = fuerza factoreada que actúa en una biela, tirante, área de apoyo o zona nodal
de un modelo de bielas y tirantes, kN
Cu = compresión factoreada en una biela de un modelo de bielas y tirantes, kN
Tu = tracción factoreada en un tirante de un modelo de bielas y tirantes, kN
An = superficie de la cara de la zona nodal sobre la cual actúa Fu, considerada
perpendicularmente a la recta de acción de Fu, o la fuerza resultante en la
sección, mm2
Ac = sección transversal efectiva en uno de los extremos de una biela de un
modelo de bielas y tirantes, considerada perpendicularmente al eje de la
biela, mm2
si = separación de la armadura en la capa i adyacente a la superficie del miembro,
mm
ws = ancho efectivo de una biela, mm
wt = ancho efectivo de un tirante, mm
β1 = factor definido en la Sección 10.2.7.3 de ACI 318-02
βs = factor que toma en cuenta los efectos de la fisuración y la armadura de
confinamiento sobre la resistencia efectiva a la compresión de una zona nodal
γ = ángulo formado por el eje de una biela y las barras que atraviesan dicha biela
θ = ángulo formado por el eje de una biela o campo de compresión y el cordón
traccionado del miembro
φ = factor de reducción de la resistencia
lb = ancho de apoyo, mm
z = brazo de palanca interno

Referencias

American Concrete Institute (2002): Apéndice A de ACI 318-02 (Building Code
Requirements for Structural Concrete) y ACI 318R-02 (Commentary).
Recomendaciones FIP (1999): Practical Design of Structural Concrete.
Comisión FIP 3: "Practical Design", Sept. 1996.
Publ.: SETO, Londres, Sept. 1999. (Distribuido por: fib, Lausanne)

160

<!-- p. 33 -->

Ejemplo 5: Viga con cargas y apoyos indirectos

Reineck, K.H. (1996): Rational Models for Detailing and Design, p. 101-134, en: Large
Concrete Buildings: Rangan, B.V. y Warner, R.F. (Editores), Longman Group Ltd., Burnt
Mill, Harlow, Inglaterra, 1996
Schlaich, J.; Schäfer, K.; Jennewein, M. (1987): Toward a Consistent Design for
Structural Concrete, PCI - Journal Vol. 32 (1987), No. 3, 75-150, 1987

161

<!-- p. 34 -->

Ejemplo 5: Viga con cargas y apoyos indirectos

162
