---
type: libro
title: "Ejercicio 3_1r"
author: "ili"
categoria: "ESTRUCTURA"
paginas: 16
extraccion: "texto (OCR pendiente)"
fuente: "local:E:/MATERIAL DE CONSULTA/ESTRUCTURA/ESTABILIDADES FADU/estabilidad 2/ejercicios/Ejercicio 3_1r.pdf"
convertido: 2026-10-16
---

# Ejercicio 3_1r

> Texto extraído de `ESTRUCTURA\ESTABILIDADES FADU\estabilidad 2\ejercicios\Ejercicio 3_1r.pdf` (16 páginas, texto (OCR pendiente)). El PDF original está en el disco E: (MATERIAL DE CONSULTA); `<!-- p. N -->` marca el inicio de cada página.

<!-- p. 1 -->



<!-- p. 2 -->

Determinación de la forma:

Tenemos barras de sección rectangular (AD y EB):

60

20

y sección nervada, por presencia de una losa maciza de 12 cm de espesor (DE):
92

12

60

20

be = .6h f + bw = .612 + 20 = 92 cm

Determinación de cargas:

TRAMOS CD, DE, EF:
Incluido en la descarga
12 de la losa

48 p.p. a incluir

p. p. = ,0 48 × ,0 20 × 2500 = 240 daN / m
Descarga de la losa = 1600 daN / m
Total = 1840 daN / m

TRAMOS AD Y BE:
p. p. = ,0 60 × ,0 20 × 2500 = 300 daN / m

Relación de Inercias:

Cálculo de la inercia por medio de la Tabla 2.6:

hf 12
ξ´= = = 2,0 3 3
h 60 .be .h ,0 40.92. 60 4 ⇒ψ = ,0 40 ⇒ I m =ψ = = 662400cm bw 20 12 12ξ = = = ,0 22
be 92

Barras AD y EB:

b.h 3 20.60 3 4 I = = = 360000cm
12 12

662400
I rel = = ,184
360000

2

<!-- p. 3 -->

Determinación de los coeficientes α y β, y las rigideces de los tramos:

Im i I r
TRAMO Li (m) Tipo de Sección Im i I r = χ= αi αi ⋅ χ β
I MIN L i

60 20.60 3
AD 2,50 1 0,4 1 0,4 0,5
12

20

92

12
.4,0 92.60 3
DE 7,34 60 1,84 0,25 1 0,25 0,5
12

20

60 20.60 3
EB 5,20 1 0,19 1 0,19 0,5
12

20

Determinación de los Coeficientes de Repartición:
3r
E
r4 0.25 2r

D
r1 0.19
0.40

A
B

Nudo D:

αi .χi = 4,0 + ,0 25 = ,0 65∑

4,0
r1 = = ,062
,0 65

,0 25
r2 = = ,038
,0 65

3

<!-- p. 4 -->

Nudo E:

αi .χi = ,0 25 + ,019 = ,0 44∑

,0 25
r3 = = ,057
,0 44

,019
r4 = = ,0 43
,0 44

Determinación de los Momentos Freno:

Ménsula CD:

1840daN/m

M 1840 × 5,1 2
M = = 2070 daN .mC 2 D
1,5

Ménsula EF:

1840daN/m

E 1840 × 2 2
M = = 3680 daN .m
F 2 M
2

Barra DE:

1840daN/m E
M ED

D
M DE 7

p. Li .L H 1840 ,7.34 7.M = = = 7878 daN .m
12 12

M DE = −7878daN .m

M ED = 7878daN .m

En las barras verticales AD y BE, no se genera momento de empotramiento perfecto dado que
el peso propio es una fuerza axil.

4

<!-- p. 5 -->

Artificio del 1º Cross:

Comenzamos por el nudo D

\-9
16
\-164
287 6090
31 -3022
\-82 1104
574 7878 -3680 -6659
\-1511 0.57 E
2207 -7
0.43
\-7878 -123 -2410 2070 0.38 -2280

51 D
4589 937 0.62
3601

1801 A -1140
2296 469 B -62 -1206
26 -4

NudoD = 4589 + 2070 − 6659 = 0∑

NudoE = 6090 − 3680 − 2410 = 0∑

Resumen:

\-3680
6090 E
\-2410

2070 -6659
D
4589

2296 A
B -1206

5

<!-- p. 6 -->

Descargas en los nodos:

Barra DE:

1840daN/m E
6090

6753

81
6659 D

6753 6672

81

6834

1840 × ,734 6659 − 6090
\= 6753daN = 81daN
2 7

Barra DA:

4589daN.m

D 2754daN
p. p. = 6,0 × ,0 20 × 2500 = 300daN / m
300 × ,250 = 750 daN
2,5 300daN/m
4589 + 2296
2754daN = 2754 daN
A ,250
2296daN.m

750daN

Barra EB:

2410daN.m E
695daN

2410 + 1206
\= 695daN
5,2 ,5 20 300daN/m

300 × ,5 20 = 1560 daN

695daN
B
1206daN.m

1560daN

6

<!-- p. 7 -->

Ménsula CD:

1840daN/m

2070
C F = 1840 × ,150 = 2760daN
1,5 D

2760

Ménsula EF:

1840daN/m

3680
F F = 1840 × 2 = 3680 daN E 2

3680

Descargas totales de la estructura y descomposición según caminos materiales:
218
6672 3680

695

F=2159 E 729 2760 6834
2888
2754

D
866

2754 A
B 695
750

1560

y 2,2 2754 2,2.
x tgα = = ⇒ y = = 866 daN y 2754 7 7
2754 7 2754,7.34
2754 cosα= = ⇒ x = = 2888daN
x ,734 7

695 2,2.
y = = 218 daN 695 7
y 695 ,7.34 x x = = 729 daN
7

7

<!-- p. 8 -->

Al descomponer las cargas queda una fuerza F que no tiene caminos materiales a los apoyos
ni encuentra equilibrio a través de la barra.

Trazado de la deformada:

Planteada la estructura bajo la acción solamente de la fuerza de desviación, se hace un
trazado de la deformada con los nodos frenados, sin giro pero con posibilidad de
desplazamientos.

• Los desplazamientos son perpendiculares a la barra por el nudo.
• La proyección de la longitud del tramo deformado sobre una paralela al eje del
mismo, es igual a la luz de la barra.
• La tangente a la deformada se mantiene paralela al eje de la barra.

MEB E
L

L

D
MDA

MAD
A MBE
B

Del trazado de la deformada obtenemos los siguientes datos:

• Qué barras se deforman
• Ubicación y sentido de los momentos
• El desplazamiento tomado con un valor proporcional al real

En este caso sólo sufren desplazamientos los nudos D y E y, dado que la barra DE debe
mantener su longitud, los desplazamientos de dichos nudos serán iguales.

∆1 = ∆ 2

y tomamos un valor arbitrario ∆ = 1000

Momentos para 2º Cross:

.6χ.∆ .4,0.6 1000
M AD = M DA = = = 960 daN .m
L 5,2
.6χ.∆ ,0.619.1000
M EB = M BE = = = 219 daN .m
L 2,5

8

<!-- p. 9 -->

Artificio del 2º Cross:

1
\-2
202
21
182
\-4 0.57
372 11 E 1
0.43
365 16 -202
0.38
\-219
\-7
D -372 595 0.62
\-960

\-960 A -219
\-211 -666 298 B 8
\-4

Descargas en los nudos usando solamente los momentos del 2º Cross:

Barra DE:

E

202

82
202 + 372
\= 82 daN
7
372 D

82

Barra AD:

372

D
415

666 + 372
\= 415daN
2,5 5,2

415
A
666

9

<!-- p. 10 -->

Barra EB:

202 E
79

5,2 202 + 211 = 79daN
2,5

79
B
211

Descomposición según caminos materiales:

25
82

79

E
F´=518 83

130 82

415

D
435

415 A
B 79

La fuerza F’ debe tener sentido contrario a F.

415 2,2.
415 y = = 130 daN
7
y
x 415 ,7.34 x = = 435 daN
7

79 2,2.
79 y = = 25 daN
7
y
x 79 ,7.34 x = = 83daN
7

10

<!-- p. 11 -->

Momentos Finales:

F 2159
α= = = ,4168
F ´ 518

Mom. Finales = Momº1. Cross + α× Mom2. º Cross

Momº1. Cross α× Mom2. º Cross Mom. Finales
M AD 2296 -2776 -480
M DA 4589 -1550 3039
M DE -6659 1550 -5109
M ED 6090 842 6932
M EB -2410 -842 -3252
M BE -1206 -875 -2081

ΣM D = M DA + M DE + M men = 3039 − 5109 + 2070 = 0
ΣM E = M ED + M EB + M men = 6932 − 3252 − 3680 = 0

Debe verificarse que los nudos están en equilibrio.

Descargas Finales en los nodos:

Se descargan las cargas actuantes y momentos finales.

Barra DE:

E 1840daN/m
6932

6753

260
5109 D 6932 − 5109
\= 260 daN
7 6753 7013

260

6493

11

<!-- p. 12 -->

Barra AD:
3039

D 1024

2,5 3039 − 480
\= 1024daN 300daN/m 5,2
A 1024

480

750

Barra EB:
3252 E
1025

5,2
3252 + 2081 300daN/m = 1025daN
2,5

1025 B
2081

1560

Componemos la estructura con las cargas en los nudos y descomponemos las fuerzas por
caminos materiales.
322
7013 3680

1025

E
1074 2760 6493
1074
1024

D
322

1024 A
B 1026
750

1560

12

<!-- p. 13 -->

Las fuerzas se equilibran en la propia barra.

1024 2,2.
x y = = 322 daN y 7
1024 ,7.34
1024 x = = 1074 daN
7

1025 2,2.
y = = 322 daN 1025 7
y 1025 ,7.34
x x = = 1074 daN
7

Equilibrio de cada tramo y Diagrama de Solicitaciones:

Barra DE:
E 1074

6932

1840daN/m
D 7013

1074 E 2102 5109 1074

6932
6493 1754,8daN/m
6688
D 551,5daN/m
1074
1946 5109

6192

x ,2 20 1840,2. 20
senα= = ⇒ x = = 5515,daN
y 1840 ,734 ,734
1840
y 7 18407.
cosα = = ⇒ y = = 17548,daN
x 1840 ,734 ,734

6493,2. 20
x = = 1946 daN
y ,734 6493
\64937.
y = = 6192 daN
x ,734

7013,2. 20
x = = 2102 daN
y ,734
7013
\70137.
y = = 6688daN
,734 x

13

<!-- p. 14 -->

6493
x0 = = ,35288 m
1840

E 1028

1754,8daN/m 6932
6688
D 551,5daN/m
3020
5109
\=10925
6192 6192X3.52882

6688
V(daN) 6192

6932 x=3.5288

5109
M(daNm)

5816=5109-10925

T 1028

3020
C
N(daN)

Ménsula CD:

1840daN/m

2070
C
1,5 D

2760

V(daN) 2760

M(daNm) 2070

N(daN) 0

14

<!-- p. 15 -->

Ménsula EF:

1840daN/m

3680

F
E 2

3680

3680
V(daN)

3680
M(daNm)

0 N(daN)
Barra AD:

9575 V(daN) M(daNm) N(daN)
3039
D 1024 1024 3039 9575

2,5 C 300daN/m

1024
A
1024 480 10325
480

10325

Barra EB:

10371 V(daN) M(daNm) N(daN)

3256 1026 1026 3256 10371

E

5,2 C 300daN/m

B
1026

2081 1026 2081 11931

11931

15

<!-- p. 16 -->

Reacciones en Apoyos:
E F

C D

A 1024
B 1026
480
2081
10325
11931

16
