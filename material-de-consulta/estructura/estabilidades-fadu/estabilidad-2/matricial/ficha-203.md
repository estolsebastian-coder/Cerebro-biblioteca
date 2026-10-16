---
type: libro
title: "Ficha%203"
author: "Estabilidad"
categoria: "ESTRUCTURA"
paginas: 55
extraccion: "texto (OCR pendiente)"
fuente: "local:E:/MATERIAL DE CONSULTA/ESTRUCTURA/ESTABILIDADES FADU/estabilidad 2/matricial/Ficha%203.pdf"
convertido: 2026-10-16
---

# Ficha%203

> Texto extraído de `ESTRUCTURA\ESTABILIDADES FADU\estabilidad 2\matricial\Ficha%203.pdf` (55 páginas, texto (OCR pendiente)). El PDF original está en el disco E: (MATERIAL DE CONSULTA); `<!-- p. N -->` marca el inicio de cada página.

<!-- p. 1 -->

2006

APUNTES DE ANÁLISIS MATRICIALFICHA 3 | DE ESTRUCTURAS

Estabilidad de las Construcciones 2 | Facultad de Arquitectura | UdelaR

<!-- p. 2 -->

APUNTES DE ANÁLISIS MATRICIAL DE ESTRUCTURAS

CASES DICTADAS POR EL INGENIERO ATILIO MORQUIO

EDITADOS CON LA COLABORACIÓN DE LAS ARQUITECTAS MARIANA
JAURI, LAURA BOZZO, CRISTINA DUFRECHOU Y MÓNICA UMPIERRE Y DE
LA BR. CLAUDIA CHOCCA.

Estas notas de clase son una versión corregida de las clases dictadas en el
primer y segundo semestre del año 1998.

<!-- p. 3 -->

1

RELACION ENTRE p, V y M PARA UNA VIGA RECTA

Aplicando las ecuaciones de equilibrio, buscamos hallar una relación diferencial entre la carga
distribuida p, el cortante V y el momento flector M.
Para hallar esta relación se elige un sistema de Y
ejes (X e Y) y se considera el equilibrio de un
elemento infinitesimal de viga RR’ de longitud dx.
Este elemento considerado como cuerpo libre está p
sometido al cortante y momento flector que actúan
en las dos secciones de corte y a la carga elemental
transversal p.dx. (Eventualmente se podría R R´ X
considerar una fuerza axil N como caso más dx
xgeneral).
x+dx

p.dxEl elemento diferencial debe cumplir con las
ecuaciones de equilibrio.

\1) Proyectando según la dirección vertical se
tiene: M(x) V(x) V(x+dx) M(x+dx)

V(x) + pdx - V(x +dx)=0 P
N(x) N(x+dx) X pdx = V(x+dx) - V(x)

R R´
dx
x x+dx

Resultando que:

dV
p ( x ) = = V ´( x ) ( I )
dx

2)Proyectando según la dirección horizontal resulta:

N(x+dx) - N(x) = 0 o sea:

N(x+dx) = N(x)
O sea que en ausencia de fuerzas horizontales aplicadas, como en nuestro caso, deberá ser la
fuerza axial constante.

\3) Momentos en relación al punto P.
Los momentos tomados en sentido horario nos proporcionan otra ecuación.

<!-- p. 4 -->

2

pdx 2
M ( x ) + V ( x ) dx + − M ( x + dx ) = 0
2

O sea resulta también:

M ( x + dx ) − M ( x ) pdx
\= V ( x ) +
dx 2

Cuando dx tiende a cero el término de la derecha se convierte en la derivada del momento y p.dx
también tiende a cero, con lo cual es posible eliminarlo resultando

dM
V ( x ) = = M ´( x ) (II)
dx

Finalmente combinando las relaciones (I) y (II), se concluye que

dV d 2 M
p ( x ) = = V ´( x ) = = M (" x ) (III) 2 dx dx

Esta ecuación diferencial relaciona la carga distribuida, el cortante y el momento flector para una
viga recta. Observese que las tres magnitudes relacionadas son en general funciones de x, o sea
de la coordenada del punto.

<!-- p. 5 -->

3

RELACIÓN ENTRE EL MOMENTO FLECTOR Y EL RADIO DE CURVATURA.

Para relacionar las solicitaciones en una viga con su deformada, se acepta (dado que normalmente
el efecto producido por el cortante es muy pequeño comparado con el producido por el momento
flector) que puede considerarse solamente la influencia del momento flector. O sea, dicho de otra
manera, para la obtención de la deformada (conocida también como elástica) de una viga, puede
normalmente ser despreciado el esfuerzo cortante.
También normalmente se considera válida la hipótesis de Bernoulli, o sea que las secciones
planas y perpendiculares al eje, luego de deformada la viga, se mantienen planas y perpendiculares
al eje.
El radio de curvatura (r) de la deformada de una C
viga puede ser obtenido a partir del momento
CD = r flector existente.
Según se indica en la figura tomaremos la
coordenada x en la dirección de la viga y
analizaremos el problema imaginando un trozo
de la viga de longitud dx.
Si consideramos que para ese valor de x existe M M
un momento flector M (que en general será
función de x), tenemos que la viga que
originalmente era recta (con un radio de A3 D B3 curvatura infinito) se va a deformar alcanzando
la forma de un segmento de circunferencia de
radio de curvatura r (en la medida que M sea
función de x, el radio de curvatura también lo
será). dx dx
2 2 Elegiremos un punto genérico A4 definido por la
coordenada ξ. Notaremos el punto antes de que
A2 A´2 B´2 B2 la viga se deforme como A4 y luego de
deformada como A’4. Para los demás puntos
A4 A´4 B´4 B4 se empleará la misma notación.
Por tener todos los lados paralelos los triángulos
A´3=A3 LN ξ B3=B´3 A3, A4, A’4 y C, D, A3 son semejantes de donde
resulta que: A4 B 4
A4 A´ 4 2 =
A´1 A1 B1 B´1 r ξ

o lo que es lo mismo: ξ 2 A4 A´ 4 = dx r A4 B 4

Pero por otro lado resulta que la deformación de la fibra A4 B4 (definida por la coordenada ξ) viene
dada por:
A4 A´ 4 + B 4 B´ 4 2 A4 A´ 4 ε (ξ ) = =
A4 B 4 A4 B 4
ξJuntando las dos últimas igualdades resulta: ε (ξ ) =
r

ξy como el material es elástico, la tensión en esa fibra será: σ (ξ ) = E
r

<!-- p. 6 -->

4

Finalmente el momento flector producido por estas tensiones en la sección se obtendrá integrando
las tensiones multiplicadas por el brazo correspondiente en toda la sección, resultando:

E 2 E 2 EI dA = M = ∫ σ ( ξ )ξ dA = ∫ ξ dA = ∫ ξ r r r

Sección Sección Sección

Es claro que el módulo de elasticidad y el radio de curvatura son constantes en toda la sección y
por eso pueden ser sacados afuera de la integral. La última igualdad es evidente pues la integral
que queda no es otra cosa que la definición de la inercia de la sección.
La igualdad obtenida anteriormente puede ser también expresada en la forma:

1 M
\=
r EI

Esta expresión fue hallada para un determinado punto de coordenada x. Es claro que en general
el momento varía con x y en consecuencia el radio de curvatura también variará. La inercia de la
sección puede ser constante o variable según x. Los dos términos de la igualdad serán entonces
funciones de x, pero la igualdad deberá cumplirse para todo x.

ECUACION DE LA ELASTICA.

La deformada de una viga puede ser expresada
como una función y (x) según se indica en la figura.
Si se acepta (como hemos aceptado) la hipótesis
de pequeños desplazamientos, con
consideraciones de geometría analítica (que
omitiremos) se puede establecer que:

1 d 2 y
\= 2 r dx
Y
Por otro lado para pequeños ángulos de giro θ se
tiene que la tangente del ángulo puede ser asimilada
con el ángulo, cuando este es medido en radianes.
Resultando que:
tg
θ(x) dy
\= tg θ ≅ θ
dx
y(x)
Juntando las anteriores conclusiones tendremos
x X que:

d 2 y dθ 1 M
\= = =
dx 2 dx r EI

En la anterior igualdad, como ya había sido analizado, cada término será función de la coordenada
x. En general el momento flector es función de x, la inercia de la sección también puede serlo (si
la viga no tiene una sección constante). El módulo de elasticidad podría variar solamente si el
material no fuera homogéneo. En nuestro curso descartaremos esta última posibilidad.

<!-- p. 7 -->

5

ANALOGIA DE MOHR

Resumiendo los resultados obtenidos anteriormente tenemos dos expresiones básicas, una que
relaciona los esfuerzos en la viga y otra que relaciona el momento con la deformada y el giro, que
son:
dV d 2 M M dθ d 2 y
p = = y = =
dx dx 2 EI dx dx 2

Obsérvese que ambas ecuaciones (son llamadas ecuaciones diferenciales, pues en ellas
intervienen las derivadas de distintas funciones) tienen una clara coincidencia, en cuanto a su
forma.
Esto llevó a Mohr a imaginar una analogía entre una y otra ecuación. Para ello pensó que si
sustituimos en la primera la carga distribuída p por el diagrama de M / EI el diagrama de cortante
que obtendremos será en realidad el diagrama correspondiente al angulo θ y el diagrama de
momentos que obtenemos no será otra cosa que la deformada de la viga.
Esta afirmación en el caso de la viga simplemente apoyada es totalmente válida. En el caso de
una viga con otros vínculos debe hacerse alguna consideración adicional, en la cual no entraremos.
En nuestro curso nos limitaremos a usar el caso de la viga simplemente apoyada.
Resumiendo las conclusiones de la analogía de Mohr podemos decir que para una viga
simplemente apoyada los diagramas de los ángulos θ y de la deformada de la viga, pueden
obtenerse considerando que la viga está sometida a una carga distribuída de valor M/ EI. Con
esa carga ficticia los diagramas de cortante y momento que se obtienen serán en realidad los
diagramas del giro y de la elástica respectivamente.

Con la carga real será: Con la carga ficticia será:

p(x) p=M
EI

V V´=θ θB

θA

M M´=y

El cortante ficticio (giro en la realidad) en el extremo de la viga (o sea en el apoyo) será igual a las
reacciones verticales ficticias en dichos apoyos (giros en los extremos en la realidad).
Podría hacerse un análisis más preciso teniendo en cuenta el signo de cada uno de los términos,
pero esto no parece necesario pues conocido el sentido de las cargas p es bastante evidente
cual es el sentido de los giros que se producen en los apoyos.

<!-- p. 8 -->

6

Normalmente en las vigas las cargas p están
dirigidas hacia abajo y entonces la deformada y
los ángulos de giro tendrán los signos que se
indican en la figura (en A el giro se produce en p
sentido horario y en B en sentido antihorario). Si
fuera otro el sentido de la carga distribuída p de
todas maneras se obtendría fácilmente el sentido
de los ángulos de giro.

La analogía de Mohr será usada a continuación para
Deformada establecer las expresiones del giro que se produce
en los extremos de una viga simplemente apoyada.
En particular se trabajará con tres situaciones tipo.
θA θB Un estado de carga más complejo que los tres
elegidos como tipos, será resuelto como una
combinación lineal de ellos, en virtud de la validez
del principio de superposición.

GIROS EN LOS EXTREMOS DE UNA VIGA SIMPLEMENTE APOYADA.

Viga con dos apoyos

Ao= área Si cargamos la viga con el diagrama de momentos,
y más aún, con M por la analogía establecida, las
G p=M EI reacciones que se obtienen son θA y θB. EI

R
R.b A0 b θ A = θ A =
VA´=θA VB´=θB a + b L

Ra A0 a θ B = θ B = a b a + b L

L

De esa manera llegamos a un procedimiento para determinar los giros en los extremos de la viga.
θA y θB quedan expresados en radianes. Como la viga es simplemente apoyada los
desplazamientos yA e yB serán cero.
Para facilitar el estudio de aquí en adelante, el término que es usado como la carga distribuída
ficticia puede ser reagrupado de la siguiente manera:

M 1 I min = M
EI EI min I

Donde Imin será el valor de la inercia mínima de la viga.
La carga ficticia puede de esa manera, ser dividida en tres términos. El primero de ellos no depende

<!-- p. 9 -->

7

de x (es constante para toda la viga) pues ni el módulo de elasticidad ni la inercia mínima dependen
de la coordenada x. El segundo factor es el diagrama de momentos y el tercer factor es el cociente
entre la inercia mínima y la inercia en cada punto.
Este tercer factor en el caso que la viga tenga inercia constante será igual a 1 y puede ser eliminado.
En el caso que la inercia de la sección sea variable el tercer factor será una función de x que solo
depende de la geometría de la viga.
El primer factor por su parte al ser constante puede ser usado para dividir a la carga ficticia que se
coloca en la viga o más sencillo todavía, hacer esa reducción al final luego de obtenidos los
valores de las reacciones producidas por la carga ficticia. Esta última posibilidad será la que
emplearemos en lo sucesivo.
O sea resumiendo: tomaremos como carga ficticia el producto del diagrama de momentos por el
tercer factor (en el caso que la viga sea de sección constante alcanzará con tomar solamente el
diagrama de momentos). Luego de obtenidas las reacciones ficticias tendremos que multiplicarlas
por el primer factor para obtener los giros de los extremos.
Con estas consideraciones pasamos a definir las tres aplicaciones tipos que nos servirán en lo
sucesivo:

APLICACIONES

a) Carga ubicada en el tramo

En este caso usaremos el subíndice 1 para
A1 identificar este tipo de carga. Para resolverlo
G colocaremos como carga distribuida ficticia el
diagrama MImin ,
I(x)
A R(A1) B (usaremos directamente el diagrama de
momentos M en el caso de inercia constante).
Para este diagrama de carga distribuída las
reacciones pueden ser calculadas planteando
equilibrio de fuerzas. A las reacciones así
obtenidas tendremos que dividirlas entre EImin
x1 x´1 (EI en el caso de inercia constante) para obtener
los giros en los apoyos. En definitiva obtenemos:

L
A1 x´1 A1 x1 θ A1 = θ BI =
EI min L EI min L
EI min (para el método de Cross χ será llamado rigidez de la viga).Si definimos χ =
L

Si la inercia es constante, A1 es el área
A1 x´1
θ A1 = 2 correspondiente al diagrama de momentos. χL

A1 x1
θ B 1 = 2 χL

<!-- p. 10 -->

8

b) Momento de valor unitario, ubicado en el extremo izquierdo del tramo.
Para este caso usaremos el subíndice 2. En este caso será:

A2 x´ 2
M2(x) θ A 2 = 2 χ L
A B
A2 x 2
θ B 2 = 2 χL
M=1

L
A2 MImín Y si la inercia es constante: A2 =
I 2
G

2 1
x´2 = L x 2 = L
3 3

1 1
θ A 2 = θ B 2 = x2 x´2 3 χ 6 χ

L

c) Momento de valor unitario, ubicado en el extremo derecho del tramo. Para este caso usaremos
el subíndice 3. En este caso será:

M3(x) A3 x´ 3
θ A 3 = 2 χL A B

M=1
A3 x 3
θ B 3 = 2 χ L
A3
L G A3 =
2
Y si la inercia es constante: ,

1 2
x´3= L x 3 = L
3 3
x3 x´3

1 1
L θ A 3 = θ B 3 =
6 χ 3 χ

<!-- p. 11 -->

9

RELACIONES FUERZAS-DESPLAZAMIENTOS EN UNA VIGA
EMPOTRADA EN LOS DOS EXTREMOS.

A) Caso General:
Con los elementos que hemos visto hasta ahora podemos encarar este problema, que es básico
para luego ver los diferentes métodos de resolución de estructuras.
Se trata de determinar las relaciones entre las fuerzas aplicadas en los extremos de una viga y
los deplazamientos de estos puntos. Más precisamente, (en nuestro caso, que estudiaremos
métodos de los desplazamientos ) interesará colocar las fuerzas en los extremos de la viga en
función de los desplazamientos de esos extremos. Supondremos por ahora que no hay fuerzas
aplicadas en los puntos intermedios de la viga.
En función de lo anterior tendremos que cualquiera sean los desplazamientos y giros que se
produzcan en los extremos y cualquiera sean las fuerzas y momentos que estén aplicados en los
smos estos pueden resumirse en las siguientes figuras.
vA vB YA YB

uA uB XA XB

A B A B
θA θB MA MB

θA θB
vA vB

uA uB

Para simplificar nuestro lenguaje, cuando digamos desplazamientos estaremos hablando
indistintamente de desplazamientos o giros. De esa manera tendremos 6 desplazamientos
posibles. Lo mismo haremos cuando digamos fuerzas, estaremos hablando indistintamente de
fuerzas o momentos aplicados. En total tendremos 6 fuerzas aplicadas posibles.
Los sentidos que están dibujados corresponden a los signos que consideraremos positivos para
cada una de las magnitudes. En lo sucesivo debemos prestar particular atención a estos signos.
Nuestro problema quedará resuelto cuando logremos colocar las 6 fuerzas en función de los 6
desplazamientos.
Como es válida la hipótesis de superposición podemos estudiar cada movimiento por separado.
Luego la suma de dos o más movimientos estará producida por la suma de las fuerzas aplicadas
correspondientes a cada uno de los desplazamientos.

En general sabemos que para una viga simplemente apoyada, los giros en sus extremos pueden
ser obtenidos superponiendo los tres estados tipos vistos anteriormente. En este estudio en la
medida que no hay cargas aplicadas al interior del tramo, se puede prescindir del caso tipo 1 y
alcanza con superponer los casos tipos 2 y 3.
Prestando atención a los sentidos de los giros que hemos elegido como positivos, se puede
concluir que en una viga simplemente apoyada, sometida a momentos MA y MB en sus extremos,
los giros θA y θB en sus extremos son los siguientes:

θ A = M Aθ A 2 − M Bθ A 3

θ B = − M Aθ B 2 + M Bθ B 3

<!-- p. 12 -->

10

Mientras que para que haya equilibrio estático las reacciones verticales deberán ser:
M A + M B Y A =
L
− ( M A + M B ) Y B =
L
B)Caso particular con giro en A solamente.
Comenzaremos estudiando cuando θA ≠ 0 y todo los demás desplazamientos son nulos. En este
caso se debe cumplir que:
θ A= M Aθ A 2 − M B θ A 3

0 = θ B = − M Aθ B 2 + M Bθ B 3
Debemos recordar que θA2, θA3, θB2 y θB3, son propiedades de la geometría de la viga, o sea que
para una viga dada son datos conocidos. También θA es un dato, pues es un giro que imponemos.
De lo anterior resulta que tenemos un sistema de dos ecuaciones con dos incógnitas que son MA
y MB. Estas dos incógnitas pueden ser despejadas obteniéndose las siguientes expresiones:

M A = 4 χα Aθ A

M B = β AB M A
MB
θA En las que αA y βAB vienen dadas por las siguien-
tes expresiones:
A B
L2
MA L α A =
MA  x´ 3 
2  x´ 2 − x 2  MA+MB MA+MB 4 A  x 3 
L L
A2 x 2 x´ 3 β AB = =
A3 x 3 x 3
C) Caso particular con giro en A solamente y sección constante (I=cte.)
Cuando la sección es constante las expresiones de las constantes se simplifican y se obtienen
los siguientes valores: 1
I = I min = cte. α A = 1 β AB =
2
Con esos valores los momentos y fuerzas aplicadas 4 EI M A = θ A
sobre los extremos de la viga serán: L
2 EI
M B = θ A
L
6 EI
Y A = 2 θ A L
− 6 EI
Y B = 2 θ A L

Teniendo en consideración que no hay ningún estiramiento ni acortamiento de la viga, resulta finalmente que: XA =0
XB =0

<!-- p. 13 -->

11

D) Caso particular con giro en B solamente.
Estudiaremos ahora cuando θB = 0 y todo los demás desplazamientos son nulos. Este caso es
similar al anterior, reemplazando en las ecuaciones y despejando los momentos en los extremos
se obtiene:
M B = 4 χα Bθ B

M A = β AB M B
MB
Donde las constantes αB y βBA vienen dadas por
A B las siguientes expresiones:

2 θB L
α B = MA  x´ 3 x 2 
4 A3  x 3 − 
2  L  x´

MA+MB MA+MB
A3 x´ 3 x 2 L L β BA = =
A2 x´ 2 x´ 2
E) Caso particular con giro en B solamente y sección constante (I=cte.)
Nuevamente se cumple que:
1
I = I min = cte. α B = 1 β BA =
2
Y las fuerzas aplicadas en los extremos resultan:

2 EI
M A = θ B
L
4 EI
M B = θ B
L
6 EI
Y A = 2 θ B L
− 6 EI
YB = 2 θ B L
X A = 0
X B = 0

F) Caso particular con desplazamiento vertical en A, solamente
Estudiaremos ahora cuando v A ≠ 0 y todos los demás desplazamientos son nulos. Este caso es
aparentemente más complejo pero puede ser reducido a una situación similar a las anteriores.
Para hacer esta simplificación el movimiento de la viga puede ser descompuesto en dos
movimientos. Un primer movimiento que es meramente un giro de la viga que se mantiene recta
o sea sin ninguna carga aplicada. Un segundo movimiento que será el indicado en la figura o sea
que estamos en el caso de una viga simplemente apoyada con dos ángulos de giro en sus
extremos que son: ν A θ A = θ B =
L
Y con las ecuaciones que quedan:
v A M Aθ A 2 − M Bθ A 3 =
L

v A − M Aθ B 2 + M Bθ B 3 =
L

<!-- p. 14 -->

12

Resultando: v A M A = 4 χα A (1 + β AB )
vA = L

v A M B = 4 χα B (1 + β BA )
vA + θA vA L

Donde α y β son los mismos coeficientes ya vA θΒ indicados anteriormente.

G) Caso particular con desplazamiento vertical en A, solamente y con I=cte.
En este caso resulta:
I = I mín = cte. α = α A = α B = 1 β = β AB = β BA = 1 / 2

Y en consecuencia: 6 EI
M A = 2 v A L
6 EI
M B = 2 v A L
12 EI
Y A = 3 v A L
12 EI
Y B = − 3 v A L
X A = 0
X B = 0

H) Caso particular con desplazamiento vertical en B.
En este caso será νB ≠ 0 y todos los demás desplazamientos = 0
Producir un cierto desplazamiento en el punto B, implica aplicar las mismas fuerzas que para
producir el desplazamiento contrario en el punto A.
En consecuencia el problema puede ser estudiado como si fuera el caso F pero tomando νA=−νB.

I) Caso particular con desplazamiento vertical en B y con I = cte.
De sustituir resultan α y β igual que en el caso G, y

− 6 EI
M A = 2 v B L
− 6 EI
M B = 2 v B L
12 EI
Y A = − 3 v B L
12 EI
Y B = 3 v B L
X A = 0
X B = 0

<!-- p. 15 -->

13

J) uA ≠ 0 y todos los demás desplazamientos nulos.

Estas deformaciones generalmente son
pequeñas comparadas con las otras. El método X A X B = − X A
matricial las considera de todas maneras. El
método de Cross en cambio las desprecia.
u A En este caso si aceptamos que el área A de la
sección es constante, se tendrá que la
deformación:
− u A − Eu A − EAu A ε = , la tensión σ = , la fuerza axil X =
L L L
− EA
y en consecuencia − x A = x B = u A o sea: M A = 0
L
M B = 0
Y A = 0
Y B = 0
EA
X A = u A
L
EA
X B = − u A
L

K) uB≠ 0 y todos los demás desplazamientos = 0, aceptamos también que A = cte.

Es lo mismo que hacer: u A = −u B

Resultando que: M A = 0
M B = 0
Y A = 0
Y B = 0
EA
X A = − u B
L
EA
X B = u B
L

<!-- p. 16 -->

14

EXPRESION GENERAL

Para el caso de sección constante si se superponen los seis estados analizados previamente se
obtienen las siguientes expresiones:

EA EA
X A = u A − u B
L L

12 EI 6 EI 12 EI 6 EI
Y A = 3 v A + 2 θ A − 3 v B + 2 θ B L L L L

6 EI 4 EI 6 EI 2 EI
M A = 2 v A + θ A − 2 v B + θ B L L L L

EA EA
X B = − u A + u B
L L

12 EI 6 EI 12 EI 6 EI
Y B = − 3 v A − 2 θ A + 3 v B − 2 θ B L L L L

6 EI 2 EI 6 EI 4 EI M B = 2 v A + θ A − 2 v B + θ B L L L L

Estas relaciones permiten expresar las fuerzas y momentos aplicados sobre los extremos de la
viga, en función de los seis desplazamientos posibles de los extremos. Este había sido nuestro
objetivo inicial.

Obsérvese que las líneas trazadas dividen los términos en cuatro zonas. La primera zona corresponde a la influencia de los desplazamientos en A sobre las fuerzas en A. En general cada una de
las zonas expresa la influencia de los desplazamientos de un punto sobre las fuerzas en ese
mismo o en el otro punto.

Si la viga no fuera de sección constante los coeficientes serían diferentes (más complicada la
expresión, pero con el mismo andamiento).
Para expresar las ecuaciones hemos colocado los desplazamientos en columnas dejando los
espacios libres cuando no hay términos.

Los coeficientes que multiplican a los desplazamientos dependen exclusivamente de las características de la viga (A, E, I, L) y en el caso de sección variable tendrán una expresión más
compleja, pero en última instancia dependen también de las propiedades geométricas y del módulo de elasticidad de la viga.

Estos coeficientes pueden ser colocados formando una matriz (forma matemática constituida
por un conjunto de n*m números colocados en filas y columnas). De la utilización de esta forma
matemática
proviene el nombre del método de análisis estructural conocido como «análisis matricial de estructuras».
La matriz (conjunto de coeficientes) es denominada matriz de rigidez de la viga.
En nuestro curso no vamos a emplear esta herramienta matemática, pues no ha sido dada en los
cursos previos.
Eludiremos su uso buscando dar una explicación con un lenguaje accesible para el estudiante.

<!-- p. 17 -->

15

RELACION FUERZAS-DESPLAZAMIENTOS EN UNA PIEZA EMPOTRADA-ARTICULADA

A) Caso general
Complementaremos el caso de la viga empotrada en los dos extremos ya estudiada, con el caso
de la viga que tiene un extremo empotrado y otro articulado. Supondremos que el extremo B está
articulado, debiendo ser en consecuencia MB =0.

v A v B Y A YB

u A u B X A XB

θ A θ B MA MB = 0

En este caso se pueden despejar todas las fuerzas y momentos incógnitas que serán en este
caso cinco (pues MB es nulo y en consecuencia conocido) con todos los desplazamientos menos
θB. O sea en definitiva se puede establecer una relación de 5 fuerzas con 5 desplazamientos. θB
puede ser obtenido como consecuencia de los demás desplazamientos y será en general diferente
de cero.
Solo veremos dos casos, que son los que interesan para nuestro estudio.

B) Giro en A y los otros cuatro desplazamientos nulos.
Como MB es nulo las ecuaciones que nos daban los ángulos de giro en A y B se simplifican y solo
dependen de MA. La primera de ellas queda:
θ A = M Aθ A 2

θ A

M A

M A M A
L L

El resultado que se obtiene, de sustituir el giro θA2 será:

M A = 4 χα Aθ A M B = 0

Donde L2
α A =
4 A2 x´ 2

C) Giro en A y los otros cuatro desplazamientos nulos, con I=cte.
En este caso resulta:
L2
α A = = .075 L 2 L
4
2 3

Y en consecuencia será:
3 EI
M A = 3 χθ A = θ A M B = 0
L

<!-- p. 18 -->

16

D) Desplazamiento vertical en A y todos los otros cuatro desplazamientos cero.
En este caso se puede descomponer el desplazamiento en dos como en el caso empotrada
empotrada y queda equivalente a un giro de valor vA / L. Las expresiones quedan:

v A M A = 4 χα A M B = 0
L

Donde αA será la expresión ya definida en el caso B.

E) Desplazamiento vertical en A y todos los otros cuatro desplazamientos cero, con I=cte.
En este caso resulta nuevamente:
α A = .075
Y los momentos
v A 3 EI
M A = 3 χ = 2 v A M B = 0 L L

ALGUNAS CONSIDERACIONES SOBRE EL MÉTODO DE CROSS

En Cross definimos rigidez como el valor:
EI mín χ =
L

El coeficiente α actúa corrigiendo la rigidez en base a la variación de la sección y también de los
vínculos en los extremos.

El valor β determina el momento que se trasmite para el otro extremo. Es llamado coeficiente de
transmisión.

Para inercia constante, estos valores son conocidos y ya han sido vistos. Cuando la inercia es
variable, hay que recurrir a tablas.

Las expresiones en cada uno de los casos están resumidas en el cuadro que está a continuación.
El método de Cross será retomado más adelante.

<!-- p. 19 -->



<!-- p. 20 -->

18

FUERZAS Y MOMENTOS DE EMPOTRAMIENTO PERFECTO

A) Barra doblemente empotrada
Llamaremos fuerzas y momentos de empotramiento perfecto (también llamados momentos freno)
a las reacciones que se producen en los apoyos de la viga cuando son aplicadas las cargas.
Cuando la viga es considerada doblemente empotrada el estado de carga puede ser estudiado
como la superposición de tres estados.
Estos tres estados de carga los consideraremos para una viga simplemente apoyada y serán los
tres estados elementales ya estudiados, que hemos denominado con los subíndices 1,2 y 3. Los
momentos en los extremos son incógnitas de modo que los estados 2 y 3 que correspondían a
un momento unidad deberán ser multiplicados por el valor de los momentos incógnitas.
Como la viga se encuentra empotrada en los dos extremos tendremos que imponer dos
condiciones, pues sabemos que los ángulos serán nulos en los dos extremos.

p
θ A θ B
A B A B

M A M B
Recordando que: A1 x´1 A2 x´ 2 A3 x´ 3
θ A1 = 2 θ A 2 = 2 θ A 3 = 2 χ L χL χ L

A1 x1 A2 x 2 A3 x 3
θ B1 = 2 θ B 2 = 2 θ B 3 = 2 χL χL χL

Esta condición queda establecida por las ecuaciones siguientes:

θ A = −θ A1 + M Aθ A 2 + M Bθ A 3 = 0

θ B = −θ B 1 + M Aθ B 2 + M Bθ B 3 = 0

Este puede ser considerado un sistema de dos ecuaciones lineales con dos incógnitas MA y MB.
Para resolver este sistema de ecuaciones, podemos multiplicar la primera ecuación por θB3 y
luego restarle la de abajo multiplicada por θA3. De esa manera se elimina MB y queda como única
incógnita MA.
Análogamente puede ser multiplicada la segunda ecuación por θA2 y restarle la primera multiplicada
por θB2. De esa manera se elimina MA y queda como única incognita MB.
Obteniendo las siguientes ecuaciones:
M A (θ A 2θ B 3 − θ B 2θ A 3 ) = θ A1θ B 3 − θ B 1θ A 3
M B (θ A 2θ B 3 − θ B 2θ A 3 ) = θ A 2θ B 1 − θ A1θ B 2

Luego si sustituimos los ángulos θ por sus respectivos valores tendremos que:

A1 x´1 x 3 − x1 x´3 A1 x1 x´ 2 − x´1 x 2 M A = M B =
A2 x 3 x´ 2 − x´ 3 x 2 A3 x 3 x´ 2 − x´3 x 2

<!-- p. 21 -->

19

Aplicaciones

a) Si I=cte. y p=cte. Se tiene que:

1

L pL3 pL2
A1 =
12 8

L L L 2 L
Y que: A2 = A3 = x1 = x´1 = x 2 = x´3 = x 3 = x´2 =
2 2 3 3
Sustituyendo obtengo: 3
pL  L 2 L L L  1  −  2 2
12  2 3 2 3  pL 6 pL M A = = =
L  2 L 2 L L L  6 1 12  − 
2  3 3 3 3  3

Y para la otra expresión si se realiza la sustitución se obtiene que: 2 pL
M B = M A =
12

b) Si se tiene una carga distribuida de la forma que se indica sustituyendo se obtiene:

p

A B
M A M B

a b

pa 2  a a 2  pa 2  a a 2 
M A =  6 − 8 + 3 2  M B =  4 − 3 2  12  L L  12  L L 

c) Si se tiene una carga concentrada de la forma que se indica sustituyendo se obtiene:

P

A B
M A M B
a b

Pab 2 Pa 2 b
M A = 2 M B = 2 L L

<!-- p. 22 -->

20

B) Barra con el extremo izquierdo empotrado.
En este caso el extremo derecho está articulado pudiendo girar libremenete. El momento
reacción en ese extremo será nulo.
Luego la única incógnita será MA y la única condición conocida será que el extremo A no gira.

p

A B
M A

La condición en el extremo A, quedará expresada por la ecuación:
θ A = −θ A1 + M Aθ A 2 = 0

Despejando el momento MA y sustituyendo los ángulos θ A1 y θA2 por sus valores se obtiene
que:
A1 x´1 M A =
A2 x´ 2

Aplicaciones

a) Si se tiene I=cte. y p=cte. entonces: pL3 L
12 2 pL2 M A = ⇒ M A =
L 2 L 8
2 3

b) Si se tiene una carga distribuida como la indicada en la figura será:

p

A B
M A
a b

pa 2 a  2 M A = − 2 
8  L 

<!-- p. 23 -->

21

c) Si se tiene una carga concentrada como la que se indica resulta:

P

A B
M A

a b

Pab L + b )) M A = 2 ( 2 L

Análogamente podrían ser obtenidos los momentos cuando el extremo derecho es el que se
encuentra empotrado.
Para el cálculo de los momentos de empotramiento perfecto (momentos freno) normalmente
utilizaremos tablas. Estas contemplan las situaciones más usuales de cargas y vínculos (publicación de tablas y ábacos)

<!-- p. 24 -->

22

DESARROLLO DEL METODO

Desarrollaremos los pasos principales del método, empleando un ejemplo simple. En este ejemplo
algunos pasos no serán necesarios. Para estos pasos que por ahora no usaremos dejaremos
números libres.Luego veremos, para un caso más general, en que consisten estos espacios que
hemos dejado en blanco.
Supongamos la siguiente estructura plana:

y

P

1 2 3 1 2 3 o x

L L L

PASO 1- Definición de los nodos
Dividiremos la estructura (en este caso, una viga) en tres tramos, según se indica en la figura.
Llamaremos nodos a los puntos extremos de los tramos, con los cuales pueden éstos ser definidos.
En este caso tendremos 4 nodos.
El nodo 2 fue colocado en el punto de aplicación de la carga “P” para evitar tener cargas al interior
de los tramos, ya que las fórmulas vistas hasta ahora solo hacen referencia a fuerzas en los
nodos. Más adelante será visto como se resuelve el problema con cargas al interior de los tramos.
Tomaremos las longitudes de los tramos iguales entre si (L), para simplificar las expresiones.
Para definir un nodo alcanza con indicar sus coordenadas. Los 4 nodos quedan definidos en un
sistema de ejes x e y, como se indica:

COORDENADAS
NODO X Y
1 0 0
2 L 0
3 2L 0
4 3L 0

PASO 2- Definición de los elementos
A los tramos les llamaremos elementos. Los elementos quedan definidos por sus dos extremos,
o sea por dos nodos que llamaremos nodo inicial del elemento y nodo final del elemento.
De acuerdo a las consideraciones anteriores, en nuestro ejemplo tendremos 3 elementos que
podemos definir de la siguiente forma:

ELEMENTO NODO NODO
INICIAL FINAL
1 1 2
2 2 3
3 3 4

Al par de números correspondientes a los nodos que definen un elemento le llamaremos
conectividad. El sentido de este nombre proviene de considerar que el elemento conecta los dos
nodos.

<!-- p. 25 -->

23

PASO 3 – Definición de las propiedades de los elementos
Otro dato necesario para definir la estructura son las propiedades de los elementos. Las
propiedades necesarias para encarar el problema, serán para cada elemento, el módulo de
elasticidad del material, el área de la sección y su inercia.
En nuestro ejemplo para simplificar las expresiones consideraremos que todos los elementos
tienen las mismas propiedades que notaremos E, A e I respectivamente.

PASO 4 – Definición de los desplazamientos de los nodos y de las fuerzas aplicadas en los
nodos.
Con los datos que ya disponemos quedan definidos los desplazamientos y las fuerzas
correspondientes a cada elemento. Cada uno de estos tiene 6 desplazamientos de los nodos, 6
fuerzas aplicadas en ellos y 6 ecuaciones que ya fueron vistas, que nos dan las fuerzas aplicadas
en los nodos en función de los desplazamientos de los nodos:
v A v B Y A YB

u A u B XA XB

θ A θ B MA M B

Para cada elemento tendremos 6 ecuaciones. En total tendríamos 6 x 3 = 18 desplazamientos y
18 fuerzas.
Pero los desplazamientos de los nodos resultan los mismos para ambas barras (esto sucede en
los nodos 2 y 3).
De modo que podemos reducir los desplazamientos de los nodos a 4 x 3 = 12 desplazamientos
(en general se verificará que los desplazamientos de los nodos =Nº de nodos x 3). Los
desplazamientos de los nodos se encuentran indicados en la figura:

1v v 2 v 3 v 4 u 2 u 3
u 1 1 2 3 u 4

θ 1

En los nodos 2 y 3 tenemos fuerzas aplicadas sobre una y otra barra, pero en realidad lo que nos
interesa es la fuerza total que esta aplicada sobre el nodo, de manera que debemos sumar estas
fuerzas y tomar la resultante en cada nodo. De esa manera las resultantes o sea las fuerzas
aplicadas en los nodos resultan también igual cantidad que los desplazamientos, o sea 12 en
este caso.
θ 2 θ 3 θ 4
Y 1 Y 2 Y 3 Y 4 X2 X 3
X 1 1 2 3 X 4

M1 M2 M3 M4

De lo anterior resulta que tanto los desplazamientos de los nodos, como las fuerzas aplicadas en
los nodos serán 12. De forma general serán el número de nodos multiplicado por tres. Es interesante
señalar también que existe una correspondencia bien clara, una a una, entre fuerzas y
desplazamientos.

<!-- p. 26 -->

24

PASO 5- Cálculo de las ecuaciones de cada uno de los elementos.

En general deberán determinarse las ecuaciones correspondientes a cada elemento. Para ello
debemos conocer las propiedades de cada elemento, o sea E, A e I y su longitud L que estará
definida por la distancia existente entre el nodo inicial y el nodo final del elemento.
En nuestro caso particular como hemos considerado A, E, I y L iguales para todos los elementos,
las seis ecuaciones de un elemento serán las mismas que las de otro elemento, con la única
diferencia que A y B deben ser sustituidos por los nodos respectivos o sea:

NODO
ELEM ENTO A B
1 1 2
2 2 3
3 3 4

PASO 6- No es necesario para esta estructura, será visto más adelante.

PASO 7- Cálculo de las ecuaciones globales de toda la estructura

Con las ecuaciones de cada barra y sumando las fuerzas correspondientes a diferentes elementos,
en cada nodo, se obtienen las expresiones de 12 fuerzas aplicadas en los nodos en función de
los 12 desplazamientos de los nodos. De esa manera se tiene un sistema de 12 ecuaciones.
Estas ecuaciones ya no son ecuaciones de cada elemento sino que son ecuaciones generales
de la estructura.
En el nodo 1 de la estructura, las fuerzas aplicadas dependerán exclusivamente de los
desplazamientos del elemento 1 (o sea de los desplazamientos de los nodos 1 y 2), en el nodo 2
de los elementos 1 y 2 (o sea de los desplazamientos de los nodos 1, 2 y 3), en el nodo 3 de los
elementos 2 y 3 (o sea de los desplazamientos de los nodos 2, 3 y 4) y en el nodo 4 del elemento
3 exclusivamente (o sea de los desplazamientos de los nodos 3 y 4).
Veamos como se obtienen los términos de las fuerzas en los nodos donde se da la superposición
(nodos 2 y 3 , fuerzas X2, Y2,M2 y X3, Y3, M3). Para ello tenemos que sumar los términos de cada uno
de los elementos que confluyen a cada uno de esos nodos.

Elemento 1 Elemento 2

EA EA EA EA EA EA EA
X2= − u1 + u 2 + u 2 − u 3 = − u1 + 2 u 2 − u 3
L L L L L L L

Elemento 1 Elemento 2

EI EI EI EI EI EI EI EI EI EI EI EI EI
Y2= − 12 3 v1 − 6 2 θ1 + 12 3 v 2 − 6 2 θ 2 + 12 3 v 2 + 6 2 θ 2 − 12 3 v3 + 6 2 θ 3 = − 12 3 v1 − 6 2 θ1 + 2 × 12 3 v 2 − 12 3 v3 + 6 2 θ 3
L L L L L L L L L L L L L

Elemento 1 Elemento 2

EI EI EI EI EI EI EI EI EI EI EI EI EI
M2= 6 2 v1 + 2 θ1 − 6 2 v 2 + 4 θ 2 + 6 2 v 2 + 4 θ 2 − 6 2 v3 + 2 θ 3 = 6 2 v1 + 2 θ1 + 2 × 4 θ 2 − 6 2 v3 + 2 θ 3 L L L L L L L L L L L L L

<!-- p. 27 -->

25

Elemento 1 Elemento 2

EA EA EA EA EA EA EA
X3= − u 2 + u 3 + u 3 − u 4 = − u 2 + 2 u 3 − u 4
L L L L L L L

Elemento 1 Elemento 2

EI EI EI EI EI EI EI EI EI EI EI EI EI
Y3= − 12 3 v2 − 6 2 θ 2 + 12 3 v3 − 6 2 θ 3 + 12 3 v3 + 6 2 θ 3 − 12 3 v 4 + 6 2 θ 4 = −12 3 v 2 − 6 2 θ 2 + 2 × 12 3 v3 − 12 3 v 4 + 6 2 θ 4 L L L L L L L L L L L L L

Elemento 1 Elemento 2

EI EI EI EI EI EI EI EI EI EI EI EI EI
M3= 6 2 v 2 + 2 θ 2 − 6 2 v 3 + 4 θ 3 + 6 2 v3 + 4 θ 3 − 6 2 v 4 + 2 θ 4 = 6 2 v 2 + 2 θ 2 + 2 × 4 θ 3 − 6 2 v 4 + 2 θ 4 L L L L L L L L L L L L L

Las 12 ecuaciones resultantes pueden ser colocadas formando una cuadrícula, de la siguiente
forma:

1u 1v θ 1 u 2 2v θ 2 3u 3v θ 3 u 4 4v θ 4

X = EA EA
1 1u − u 2
L L
1Y = EI EI EI EI 12 3 v1 + 6 2 θ 1 − 12 3 v2 + 6 2 θ 2 L L L L
M 1 = EI EI EI EI 6 2 v1 + 4 θ 1 − 6 2 v 2 + 2 θ 2 L L L L
X 2 = EA EA EA − 1u + 2 u 2 − 3u
L L L
Y2 = EI EI EI EI EI − 12 3 v1 − 6 2 θ1 + 24 3 v2 − 12 3 v 3 + 6 2 θ 3 L L L L L
M 2 = EI EI EI EI EI 6 2 v1 + 2 θ 1 + 8 θ 2 − 6 2 v3 + 2 θ 3 L L L L L

X 3 = EA EA EA − u 2 + 2 u 3 − u 4
L L L

EI EI EI EI v 3Y = − 12 3 − 12 3 v2 − 6 2 θ 2 + 24 EIL3 3 v4 + 6 2 θ 4
L L L L
M 3 = EI EI EI EI EI 6 2 v 2 + 2 θ 2 + 8 θ 3 − 6 2 v 4 + 2 θ 4
L L L L L
X 4 = EA EA − 3u + u 4
L L
Y4 = EI EI EI EI − 12 3 v3 − 6 2 θ 3 + 12 3 v 4 − 6 2 θ 4 L L L L
M 4 = EI EI EI EI 6 2 v3 + 2 θ 3 − 6 2 v 4 + 4 θ 4 L L L L

<!-- p. 28 -->

26

En definitiva se suman los términos correspondientes a uno y otro elemento. Este procedimiento
es conocido como el montaje de las ecuaciones. Si uno observa los términos que aporta cada
elemento verá que los mismos afectan una zona de la cuadrícula, o sea la zona donde se cruzan
las fuerzas y los desplazamientos correspondientes (filas y columnas respectivamente) a los
nodos inicial y final del elemento. Si los nodos del elemento son consecutivos (como sucede en
nuestro ejemplo) la zona será de 6 x 6 términos, mientras que si los nodos no son consecutivos
serán cuatro zonas de 3 x 3, como se indica en la figura siguiente.

P P

1 2 3 1 2 3
1 2 3 4 1 4 2 3

1 1 1

2 2 3 2
3

3 3 3

1 2 1
2

Obsérvese que este procedimiento repite para cada elemento las mismas operaciones sin
necesidad de realizar ninguna consideración particular, lo que lo hace especialmente conveniente
para ser utilizado por computadoras. Con este procedimiento podríamos plantear las ecuaciones
para cualquier pórtico.

PASO 8- Definición de las restricciones de los nodos.
La estructura siempre debe tener algunos vínculos a tierra, o dicho de otra manera existen nodos
que tienen restringida la posibilidad de moverse.
En nuestro ejemplo dados los empotramientos en los nodos 1 y 4 y el apoyo deslizante en el nodo
3, aparecerán restricciones a los desplazamientos, que podemos expresar como:
u1=v1=θ1=v3=u4=v4=θ4=0
Estas condiciones permiten eliminar de las ecuaciones todos los términos que involucraban a
estos desplazamientos, por cada condición estaremos eliminando una columna de la cuadrícula.

PASO 9- Definición de las cargas aplicadas en los nodos.
Los valores de las cargas aplicadas en los nodos, deben ser otro dato del problema.
En nuestro ejemplo las fuerzas (fuerzas o momentos) son las siguientes:
a) en el nodo 2 hay una fuerza vertical descendente por lo tanto Y2 =-P, en tanto que no hay
fuerzas aplicadas horizontal o momento, o sea X2=M2=0
b) en el nodo 3 habrá una reacción vertical que desconocemos, pero sabemos que no hay
fuerzas aplicadas horizontal ni momento, o sea X3=M3=0.

Tenemos conocidas en total 5 fuerzas y 7 restricciones a los desplazamientos. Las fuerzas
correspondientes a las restricciones son desconocidas y constituyen las reacciones producidas
por los vínculos. (Cada vez que impongo una restricción a los desplazamientos aparece la fuerza
como incógnita y viceversa).

<!-- p. 29 -->

27

El sistema de ecuaciones queda ahora con 12 ecuaciones, 7 fuerzas incógnitas que son las
reacciones o sea X1, Y1, M1, Y3, X4, Y4 y M4 y 5 desplazamientos incógnitas o sea u2, v2, θ2, u3 y θ3.
Las ecuaciones quedan:

EA
X1= − u 2
L

EI EI
Y1= − 12 3 v 2 + 6 2 θ 2 L L

EI EI
M1= − 6 2 v 2 + 2 θ 2 L L

EA EA
0 = X2 = 2 u 2 − u 3 (A)
L L

EI EI
\- P = Y2 = 24 3 v 2 + 6 2 θ 3 (B) L L

EI EI
0 = M2 = 8 θ 2 + 2 θ 3 (C)
L L

EA EA
0 = X3 = − u 2 + 2 u 3 (D)
L L

EI EI
Y3 = − 12 3 v2 − 6 2 θ 2 L L

EI EI EI
0 = M3 = 6 2 v 2 + 2 θ 2 + 8 θ 3 (E) L L L

EA
X4 = − u 3
L

EI
Y4 = − 6 2 θ 3 L

EI
M4 = 2 θ 3
L

PASO 10- No se necesita en nuestro ejemplo, se verá más adelante.

PASO 11- Resolución de las ecuaciones. Cálculo de los desplazamientos.
El sistema anterior es un sistema de 12 ecuaciones con 7 fuerzas incógnitas y con 5
desplazamientos incógnitas. O sea en definitiva un sistema de 12 ecuaciones con 12 incógnitas.
La igualdad entre incógnitas y ecuaciones permitirá resolverlo.
Dentro de este sistema se puede formar un subsistema de 5 ecuaciones (A), (B), (C), (D) y (E)
con 5 incógnitas (desplazamientos u2, u3, v2, θ2, θ3) que podemos resolver, pues los términos de la
izquierda son conocidos en las 5 ecuaciones.

<!-- p. 30 -->

28

Obtenidos esos desplazamientos, las 7 ecuaciones restantes me permiten hallar las fuerzas no
conocidas (o sea las reacciones: X1, Y1, M1, Y3, X4, Y4, M4).

Si se tratara de otra estructura cualquiera la cantidad de desplazamientos incógnitas variaría pero
tendríamos también el mismo número de fuerzas conocidas y podríamos resolver el subsistema.
Ello es debido a que donde hay un desplazamiento incógnita es porque no hay un vínculo que
impida su desplazamiento y en consecuencia la fuerza aplicada correspondiente deberá ser un
dato del problema.
La resolución del subsistema, que es un sistema de ecuaciones lineales, es un problema que
tiene diversas formas de ser resuelto por métodos computacionales, con procedimientos
sistematizados que pueden ser aplicados para cualquier caso.
Para continuar con nuestro ejemplo podemos resolver manualmente el sistema de ecuaciones
resultante. Para ello es conveniente observar que el subsistema de 5 x 5 puede a su vez ser
subdividido pues las ecuaciones (A) y (D) nos vinculan los u sin que aparezcan los v ni los θ y las
ecuaciones (B), (C) y (E) vinculan los v y los θ, sin que aparezcan las u, por lo que podemos
resolver primero las ecuaciones (A) y (D) y luego en forma separada las ecuaciones (B), (C) y (E).

Veamos las dos ecuaciones en u:

LSi multiplico (A) por queda: 2u2 = u3
EA
EA EA EASustituyo en (D) u3, nos queda: − u + 4 u = 0 ⇒ 3 u = 0 ⇒ u = 0
L 2 L 2 L 2 2

Luego se concluye que; u2=u3=0

Veamos ahora las otras tres ecuaciones:

L
Si multiplico (C) por resulta: θ 3 = −4θ 2 2 EI

EI EI EI
Sustituyendo en (E) obtengo: 6 v + 2 θ − 32 θ = 0 2 2 2 2 L L L

L v 2Si ahora multiplico por , queda: 6 − 30θ 2 = 0 ⇒ v 2 = 5θ 2 L EI L
EI EI PL2
Sustituyendo en (B) tendremos que: − P = 24 2 5θ 2 − 24 θ 2 y entonces −EI = 96θ L2 L2

PL2
Y luego sustituyendo resulta: θ 3 = −4θ 2 =
24 EI

Y 5 PL3 PL2
v 2 = 5θ 2 L = − ⇒ θ 2 = −
96 EI 96 EI

Resumiendo, podemos decir que la solución buscada del sistema de ecuaciones lineales es la
siguiente:
PL2 PL2 5 PL 2
u 2 = u 3 = 0 θ 2 = − θ 3 = v 2 = −
96 EI 24 EI 96 EI

<!-- p. 31 -->

29

PASO12- Resolución de las ecuaciones. Cálculo de las reacciones.

Conocidos los 5 desplazamientos incógnitas para calcular las reacciones alcanza con utilizar las
7 ecuaciones restantes. Sustituyendo los desplazamientos por los valores calculados en el paso
anterior resulta:

11
X 1 = X 4 = 0 Y3 = P
16

9 P
Y1 = P Y4 = −
16 4

7 PL
M 1 = PL M 4 =
24 12

PASO 13- No se necesita en nuestro ejemplo, se verá más adelante.

PASO 14- Cálculo de las fuerzas aplicadas en los extremos de cada elemento.

Conociendo los desplazamientos de los extremos de cada elemento y empleando las ecuaciones
de cada elemento se pueden calcular las fuerzas aplicadas sobre cada elemento en sus extremos.
Para el elemento 1 será:

Y A Y B

XA XB

MA M B

X A = 0

− 12 EI − 5 PL3   6 EI − PL2  9
YA =  3   +  2   = P  L  96 EI   L  96 EI  16

− 6 EI − 5 PL3   2 EI − PL2  7
MA =  2   +    = PL  L  96 EI   L  96 EI  24

De igual modo se puede continuar con las restantes fuerzas aplicadas en el elemento 1 en el
punto B, así como en los restantes elementos.

PASO 15- No se necesita en nuestro ejemplo, se verá más adelante.

PASO 16- Impresión de Resultados
Los programas normalmente imprimen los desplazamientos de los nodos, las reacciones en los
apoyos y las fuerzas aplicadas en los extremos de cada elemento, calculadas en los pasos
anteriores.

<!-- p. 32 -->

30

PASO 17- Diagramas de solicitaciones de los elementos y deformada de la estructura.

Con los resultados obtenidos podemos plantear los diagramas de solicitaciones y la deformada
de la estructura. En muchos casos estos diagramas son realizados por el propio programa, en
nuestro caso los realizaremos manualmente. Los diagramas de solicitaciones obtenidos son los
siguientes.

P
9P 4
16 V
1 2 3 4

7P
16

PL
PL
7PL 6
12
24
1 2 3 4 M

13PL
48

0 N

En esta etapa haremos las verificaciones que corresponden. Sea cual sea el método de
cálculo:ΣFx=0 (suma de cargas y reacciones horizontales), ΣFy=0 (suma de cargas y reacciones
verticales), ΣM=0 (suma de momentos con relación a un punto cualquiera, producidos tanto por
fuerzas como por momentos, de todas las cargas y reacciones) y relacionaremos la concavidad
de la elástica en función del diagrama de momentos.

La deformada tiene la siguiente forma:

θ 3〉 0
p..i
1 2 3 4
Elástica
p..i

p..i

θ 2 〈 0 p.i. = punto de inflexión

<!-- p. 33 -->

31

ETAPAS DEL MÉTODO

\* PASO 1- Ubicamos los nodos. (Determino cantidad y coordenadas).

\* PASO 2- Definimos los elementos. (Cantidad y conectividades).

\* PASO 3- Definimos las propiedades de los elementos (área, inercia y módulo de elasticidad).

\- PASO 4- Quedan así definidos los desplazamientos y las fuerzas (no sus valores, pero si su
disposición). En nuestro ejemplo serán 12 desplazamientos y 12 fuerzas: Nº de nodos por 3
(4x3).

\- PASO 5- Se calculan los términos de la rigidez (relaciones entre fuerzas y desplazamientos
para cada barra: 6 x 6).

\- PASO 6- (Transformación de coordenadas, se verá más adelante).

\- PASO 7- Se construye la rigidez global (ecuaciones generales de toda la estructura). En nuestro
ejemplo, llegamos a un sistema de 12 ecuaciones con 12 desplazamientos y 12 fuerzas: 12
x12.

\* PASO 8- Definimos las restricciones producidas por los vínculos a tierra (7 desplazamientos
en nuestro ejemplo) y eliminamos los términos correspondientes en las ecuaciones.

\* PASO 9- Ubicamos las cargas en los nodos.

\+ PASO 10- (Se relaciona con cargas que no están en los nodos, se verá más adelante).

\+ PASO 11- Resolvemos el sistema: Hallamos los desplazamientos desconocidos: 5 en nuestro
ejemplo, sistema de 5 ecuaciones.

\- PASO12- Con los desplazamientos hallados utilizamos las 7 ecuaciones restantes. Obtenemos
las fuerzas desconocidas o sea las reacciones.

\- PASO 13- (Transformación de coordenadas globales a locales: se verá más adelante).

\- PASO 14- Con los desplazamientos conocidos vamos a las ecuaciones de cada barra
obtenidas en el PASO 5 y hallamos las fuerzas en los extremos de cada una.

\- PASO 15- (Se verá más adelante).

\+ PASO 16- Resultados: Imprimimos desplazamientos en los nodos, reacciones y las fuerzas
en los extremos de cada elemento.

\- PASO 17- En el caso de este programa dibujamos manualmente diagramas y verificamos
reacciones.

\* Instancias en que introducimos datos al programa.
\+ Instancias en que obtenemos datos del programa

<!-- p. 34 -->

32

CASOS EN QUE LOS ELEMENTOS NO SON PARALELOS

Para poder generalizar lo visto anteriormente debemos resolver las dos limitaciones que tiene el
ejemplo anterior. Ellas son que no había cargas al interior de los elementos (caso que será visto
más adelante) y que los elementos eran paralelos.
Debido a que los elementos eran paralelos los desplazamientos en un extremo de un elemento
coincidían con los desplazamientos en los extremos del elemento contiguo.

De esa manera, teníamos 3 elementos, pero no teníamos 3x6=18 desplazamientos pues en los
nodos 2 y 3 coinciden los desplazamientos de un elemento con los del otro. Solo teníamos 12
desplazamientos (3 x Nº de nodos, con Nº de nodos=4).

Para las fuerzas en los nodos se hacía la misma simplificación, pues las fuerzas sobre cada barra
se podían sumar obteniendo las fuerzas totales aplicadas en lo nodos. De modo que resultaban
también 12 fuerzas en los nodos.

Cuando los elementos no son paralelos, como es el caso de la figura, esta simplificación ya no es
posible, pues los desplazamientos de un extremo no serán los mismos que los del otro extremo.
Para resolver esta dificultad es conveniente establecer dos sistemas de coordenadas: uno Local
y otro Global.

El sistema de coordenadas Locales se establece con el eje “x” coincidente con el eje del elemento
y el eje “y” perpendicular al anterior.

El sistema de coordenadas Globales será el utilizado para definir los nodos, normalmente elegido
con el eje XG horizontal y el eje YG vertical como se indica en la figura.

X YG
Y B

A

X G

Usaremos la notación siguiente:
Para el nodo A: uA, vA, θA en coordenadas locales.
uAG, vAG, θAG en coordenadas globales.
Para el nodo B: uB, vB, θB en coordenadas locales.
uBG, vBG, θBG en coordenadas globales.
vB uB
Tenemos entonces los desplazamientos y fuerzas en θB
coordenadas locales que son: B X

YB
vA MB
A θ
uA
YA

XA
MA

<!-- p. 35 -->

33

Los desplazamientos y fuerzas en coordenadas globales serán:
v BG
u BG

Y BG
θ BG
X BG
v AG
M BG
u AG
θ AG
Y AG

X AG M AG

La resolución del problema pasa por referir las relaciones fuerzas-desplazamientos (que ya
conocemos en coordenadas locales) a coordenadas globales. O sea relacionando XAG, YAG, MAG,
XBG, YBG y MBG, con uAG, vAG, θAG, uBG, vBG y θBG.

Las relaciones en coordenadas locales para las fuerzas en A son:

EA EA
X A = u A − u B
L L

EI EI EI EI
Y A = 12 3 v A + 6 2 θ A − 12 3 v B + 6 2 θ B Expresiones (1) L L L L

EI EI EI EI
M A = 6 2 v A + 4 θ A − 6 2 v B + 2 θ B L L L L

Del mismo modo se pueden expresar las fuerzas en B:

EA EA
X B = − u A + u B
L L

EI EI EI EI
Y B = −12 3 v A − 6 2 θ A + 12 3 v B − 6 2 θ B L L L L

EI EI EI EI
M B = 6 2 v A + 2 θ A − 6 2 v B + 4 θ B L L L L

Veremos como pasamos de las expresiones en coordenadas locales a coordenadas globales.
Supondremos primero que tenemos un desplazamiento uAG y luego que tenemos uno vAG.

<!-- p. 36 -->

34

Veremos en coordenadas locales como resultan estos desplazamientos. Para ello
descompondremos vAG, y uAG según los ejes locales:

v AG . cos α
α
u AG . cos α u AG.sen α u AG v AG . sen α
α α
u AG
u A = u AG . cos α u A = v AG .senα
v A = u AG .senα v A = v AG . cos α
Un giro del extremo del elemento θAG representará en coordenadas locales el mismo giro, esto es:

θA=θAG

Si superponemos ahora los dos desplazamientos tendremos que:
uA=uAG cos α + vAG sen α
vA=-uAG sen α + vAG cos α Expresiones (2)
θA = θAG

Análogamente para el nodo B resulta:
uB=uBG cos α + vBG sen α
vB=-uBG sen α + vBG cos α
θB = θBG

Si invierto el problema y quiero poner las coordenadas globales en función de las coordenadas
locales, tengo que pasar de una a otra coordenada, ahora con un ángulo -α.

Sabiendo que: cos -α = cos α
sen -α = −sen α
Tendré las siguientes expresiones:
uAG = uA cos α - vA sen α uBG = uB cos α - vB sen α
vAG = uA sen α + vA cos α vBG = uB sen α + vB cos α
θAG = θA θBG = θB

Este razonamiento se realizó con los desplazamientos, pero si hubiéramos razonado con las
fuerzas aplicadas hubiera sido una situación totalmente análoga.
Luego la relación de las fuerzas referidas en coordenadas globales y locales será:
XAG=XA cos α - YA sen α
YAG = XA sen α + YA cos α
MAG=MA
Y en el nodo B: Expresiones (3)
XBG=XB cos α - YB sen α
YBG = XB sen α + YB cos α
MBG=MB

<!-- p. 37 -->

35

Ahora podemos sustituir en las expresiones (1), los valores de uA, vA, θA, uB, vB y θB de las expresiones
(2).

Me quedan XA, YA y MA (fuerzas en coordenadas locales) en función de los desplazamientos en
coordenadas globales.
Con las expresiones de XB, YB y MB puedo hacer lo mismo.
Finalmente puedo sustituir los XA, YA, MA, XB, YB y MB (obtenidos de las últimas sustituciones) en
las expresiones (3) y quedarán relacionadas las fuerzas en coordenadas globales con los
desplazamientos en coordenadas globales como queríamos.
La expresión que se obtiene es la que emplea el programa para realizar el cambio de las ecuaciones
de coordenadas locales a coordenadas globales.
Para diferentes elementos variarán las propiedades del elemento (E, A, I), su longitud (L) y el
ángulo α y con ello los coeficientes de las expresiones que relacionan fuerzas y desplazamientos
globales y entonces puedo reducir los desplazamientos incógnitas, como en el caso visto
anteriormente a 3 x Nº de nodos.
Análogamente las fuerzas en coordenadas globales tendrán las mismas direcciones y pueden
ser sumadas en cada nodo, igual que en el caso visto anteriormente.

Este pasaje de las ecuaciones de un sistema de coordenadas a otro debe ser realizado antes de
montar las ecuaciones globales de la estructura y es uno de los pasos que habíamos dejado en
blanco. Podemos resumirlo en:

PASO 6- Pasaje de las ecuaciones que relacionan desplazamientos y fuerzas sobre los extremos
de las barras de coordenadas locales a coordenadas globales.

Cabe señalar finalmente que cuando tenga la solución de los desplazamientos en coordenadas
globales (paso 11), antes de calcular las fuerzas en los extremos de cada barra (paso 14) con las
ecuaciones de cada barra (que están en coordenadas locales), debo pasar los desplazamientos
del elemento de coordenadas globales a coordenadas locales. Esto puede resumirse:

PASO 13- Conversión de los desplazamientos de los nodos hallados en coordenadas globales
para las coordenadas locales de cada barra.

CARGAS QUE NO ESTÁN EN LOS NODOS.

Veamos ahora el otro caso que nos quedaba pendiente. La idea de este procedimiento se aplica
en cálculo matricial y también se aplica en el método de Cross. Para resolverlo descompondremos
el estado de cargas en dos estados (a y b) de manera que cada uno de ellos pueda ser resuelto
sencillamente. La suma de los dos estados será el verdadero estado de cargas aplicado sobre la
estructura.

a) b)

\= +

Fep -Σ Fep

<!-- p. 38 -->

36

En el estado a) consideraremos aplicadas todas las cargas que actúan sobre la estructura y
consideraremos que todos los nodos se encuentran fijos, o sea impedidos de desplazarse y de
girar.
En los nodos fijados se producirán reacciones, que evitarán los desplazamientos de los nodos de
la estructura.
Las fuerzas aplicadas en los nodos sobre las barras son las fuerzas de empotramiento perfecto
(Fep), que ya hemos estudiado.
Estas fuerzas de empotramiento perfecto pueden ser calculadas barra por barra.
O sea resumiendo, tendremos en este estado que
los deplazamientos son todos nulos y que las
solicitaciones en los nodos de las barrras son las
fuerzas de empotramiento perfecto.
Finalmente en cada nodo pueden ser calculadas
las reacciones producidas sumando las fuerzas de
empotramiento perfecto de todas las barras que
confluyen al nodo.
El estado b) deberá tener en cada nodo una carga igual y contraria a la suma de las fuerzas de
empotramiento perfecto obtenidas en la parte a). O dicho de otra manera, tendrá aplicada en
cada nodo la suma de las descargas (supuestas las barras con empotramiento perfecto) de cada
una de las barras que llegan al nodo.
De esa manera al superponer los dos estados, las fuerzas de empotramiento perfecto se
contrarrestan con las descargas y solo quedan las cargas verdaderamente aplicadas sobre la
estructura. Esto es necesario pues nosotros imaginamos en la parte a) que existían reacciones
en todos los nodos, pero en la realidad esto no es así. Se trata de una suposición para facilitar el
cálculo.

El estado de cargas a) puede ser calculado barra por barra empleando fórmulas analíticas o a
través de tablas.
El estado de cargas b) solo tiene cargas en los nodos por lo que puede ser calculado sin problemas.
El diagrama de momentos y los deplazamientos que tenga la estructura será la suma de a) y b).

Resumiendo puede decirse que descompongo el estado de cargas en dos estados que luego
superpongo. El primer estado no significa ningún desplazamiento de los nodos y produce fuerzas
de empotramiento perfecto en los nodos.
Estas fuerzas calculadas por elementos, convertidas a coordenadas globales, sumadas y
cambiadas de signo (descargas) se incorporan a las carga en los nodos (Paso 10). De esa manera
el programa calcula el estado b).

Finalmente debemos realizar la suma de los dos estados.
Esto se realiza en el paso 15 luego de calculados los desplazamientos en coordenadas globales
(Paso 11), de haberlos llevado a coordenadas locales (Paso 13) y de haber calculado los esfuerzos
en los extremos de los elementos (Paso 14) producidos por los desplazameintos (estado de
cargas b). En el paso siguiente debo agregar los esfuerzos producidos por el estado de cargas a)
(que ya fueron calculados en 10) para obtener los esfuerzos totales.
A los desplazamientos calculados en b) no hay que agregarle nada pues en el estado a) los
nodos no tienen desplazamientos.
Resumiendo lo anterior, los pasos que faltaban quedan definidos por:
PASO 10- Calculo los momentos y fuerzas de empotramiento perfecto en cada barra y los guardo
para introducirlos en el paso 15. Además los cambio de signo para obtener las descargas y los
paso a coordenadas globales y los agrego como cargas en los nudos.
PASO 15- Al estado obtenido por las cargas aplicadas en los nodos (estado b) debo sumarle el
estado a) ya calculado en el paso 10. Sumando los dos estados obtengo las solicitaciones totales
en los nodos.

<!-- p. 39 -->

37

CONSIDERACIONES SOBRE EL PROGRAMA

A) ENTRADA Y SALIDA DE DATOS
El programa admite la entrada de los datos por archivo o teclado, la salida de los resultados
puede ser por pantalla, archivo o impresora.
Se recomienda usar la salida por archivo, pues no se pierde la información, incluso el archivo
puede ser impreso posteriormente, usando cualquier editor, si uno lo desea.
En la salida por pantalla no caben todos los resultados en la pantalla, solamente se ve el final de
ellos. Solo es útil cuando se están haciendo pruebas y se quiere ver si corre el programa.
La salida por impresora puede no funcionar (depende de la impresora que se dispone).
En cuanto a la entrada se recomienda también usar la entrada por archivo.
El archivo de entrada debe ser editado y deben colocarse los datos en la forma correcta, ello
debe hacerse antes de correr el programa. Si cuando se corre el programa se encuentra que
existe algún error del archivo de entrada, este puede ser editado nuevamente y se corrigen
solamente los errores.
En cambio si la entrada de datos se hace por teclado y se comete algún error, para correr otra vez
el programa los datos deberán ser digitados todos nuevamente.
En resumen se sugiere entrar y salir por archivo.

Usaremos archivos con terminación .DAT para los archivos de datos y terminación .SOL para los
archivos de salida de datos o solución del problema.

B) VERIFICACION CON LA SALIDA DE DATOS
El programa aunque no ruede completo (se interrumpa su ejecución) siempre va a producir algún
archivo de salida de datos. Esta salida debe ser editada luego de correr el programa, en ella
puede verificarse hasta donde los datos leídos son correctos. De esa manera se determina
fácilmente el lugar del archivo de datos donde se encuentra el error y en el que debemos realizar
la modificación correspondiente. Este proceso continúa hasta que la salida de datos esté completa.

C) ERROR EN LA ESTRUCTURA
El programa puede leer todos los datos e imprimirlos todos, de forma aparentemente correcta y
no correr totalmente, esto es interrrumpirse sin dar todos los resultados.
Generalmente, cuando esto ocurre, en algún lugar está dividiendo entre 0 y esto indica que el
sistema de ecuaciones no tiene solución. En este caso el formato de los datos está siendo correcto
pero no sus valores.
Y si los datos estuvieran bien y continúa dando error, entonces la que está mal es la estructura
diseñada.
Seguramente le falta algún vínculo o algún elemento. No es una estructura estable y por eso no
puede ser resuelta.

D) UNIDADES
Las unidades son solicitadas por el programa pero este solo las guarda y las devuelve en la
salida. La coherencia de las unidades empleadas es responsabilidad nuestra. Debemos elegir
una unidad para las longitudes y otra para las fuerzas (por ejemplo centímetros y decanewton).
Las demás magnitudes deberán ser expresadas en función de estas unidades (áreas en
centímetros cuadrados, inercias en centímetros a la cuarta, momentos en decanewton centímetro,
módulo de elasticidad en decanewton por centímetro cuadrado). Los ángulos son adimensionados
y se expresan en radianes.

E) VERIFICACION DE LOS DATOS
Es conveniente verificar los datos, para ello uno deja a un lado el esquema de la estructura y
empleando solamente el archivo de salida vuelve a construir la estructura, coloca sus apoyos y
coloca sus cargas. Luego se coteja con el esquema inicial para verificar si está todo correcto.

<!-- p. 40 -->

38

F) VERIFICACION DE LAS REACCIONES
Es conveniente verificar si las reacciones neutralizan efectivamente las cargas externas, para
ello se proyectan las reacciones y las cargas sobre el eje x, sobre el eje y, y finalmente se toma su
momento en relación a algún punto.

G) DIAGRAMAS DE SOLICITACIONES
Los diagramas de fuerzas axiles, cortante y momentos deben ser dibujados a mano, con los
datos que proporciona el programa para los extremos de las barras y teniendo en cuenta las
cargas aplicadas en la barra.

H) DEFORMADA DE LA ESTRUCTURA
El programa proporciona los desplazamientos y giros de los nodos, con estos resultados y los
diagramas de los momentos (que nos dan una idea de la concavidad de la deformada de los
elementos) se puede dibujar la deformada de la estructura. Esta es una verificación muy
conveniente.

I) CARGAS
El programa admite tres tipos de cargas.
En primer lugar se introducen los datos de ls carga en los nodos (fuerzas y momentos). Estas
cargas estan referidas en coordenadas globales, serán positivas según el eje x global, según el
eje y global y en sentido antihorario para los momentos.
En segundo lugar admite cargas distribuídas (constantes) en las barras, éstas deben ser
perpendiculares a las barras y estarán referidas en coordenadas locales de la barra, según las
convenciones que veremos más adelante.
En tercer lugar admite cargas concentradas en las barras, éstas deben ser perpendiculares a las
barras y estarán referidas en coordenadas locales de la barra, según las convencionees que
veremos más adelante.

J) CONVENCIONES PARA CARGAS EN LAS BARRAS
Las cargas en las barras estarán referidas siempre en coordenadas locales.
Convendremos que para analizar las cargas y luego los esfuerzos en una viga uno debe colocarse
de frente a la viga y viendo el primer nodo de la misma a nuestra izquierda. Por ejemplo para la
viga 1,2 será:
F
2

p

1 a b c Observador

Las cargas, tanto distribuidas como concentradas, que apuntan hacia el observador, tendrán por
convención signo negativo (como es el caso de las indicadas en la figura).
Las distancias serán medidas siempre desde el primer nodo.
Para cargas distribuídas (constantes) se deberá conocer el número de la barra, la carga distribuída
con signo, la distancia desde el punto donde se inicia la carga al primer nodo y la distancia desde
el punto donde terminan las cargas al primer nodo (de acuerdo a la figura serán a y b
respectivamente).
Para carga concentrada se deberá conocer el número de la barra, la carga concentrada con
signo y la distancia desde el punto de aplicación al primer nodo (de acuerdo a la figura será c).

<!-- p. 41 -->

39

K) CARGAS NO PERPENDICULARES
Si hay cargas en los elementos, no perpendiculares al elemento, la carga puede ser descompuesta
en una componente normal a la barra y otra de tipo axial, como se indica en la figura siguiente:

q qN qL
qL
\= + q
α
qN
α

El programa que estamos empleando admite las cargas perpendiculares, pero no admite las
cargas axiales. (Esta es una limitación de este programa, otros programas admiten este tipo de
cargas).

Veremos como se resuelve el problema en el caso de las cargas axiales:
Para ello podemos superponer dos estados de carga.
Un estado a) en el que no hay ningún desplazamiento de los nodos y aparecen solamente fuerzas
axiles de empotramiento perfecto.
Otro estado b) en el que aparecen las cargas de empotramiento perfecto con signo cambiado
(descargas) en los nodos.
a) b)
F2 -F2

L
q = q +

F1 -F1

En el caso q=cte. Será qL F1=F2=qL T 2

Para el caso a) el diagrama de fuerza axil será el
siguiente:
qL
2 C

Los demás esfuerzos en la barra y en todas las demás barras son todos iguales a cero.
a) Puede ser resuelto manualmente,
b) Puede ser resuelto por el programa si colocamos las descargas que corresponden en los
nodos.

<!-- p. 42 -->

40

La resolución de a) depende de las cargas aplicadas. Para carga distribuída constante a lo largo
de toda la barra las fuerzas de empotramiento perfecto y los diagramas de fuerzas axiles son los
indicados en la figura.
Luego de tener los resultados obtenidos con el programa de la parte b) o sea de las descargas
consideradas en los nodos, junto lógicamente con todas las demás cargas que actúan sobre la
estructura, se puede al final superponer manualmente los diagramas de fuerza directa de la
carga a) y luego obtener los diagramas de solicitaciones totales.

L) CONVENCIONES DE SIGNOS PARA LOS DIAGRAMAS DE ESFUERZOS EN LAS BARRAS
Normalmente se ha usado para los diagramas de cortante y momento la convención que se
expresa en la figura:

q

\+ +
_ _
V

_ _

M
\+

Esta convención, no debe confundirse con la convención empleada para descargar las cargas
sobre los nodos, según la cual los momentos son del mismo sentido cuando siguen el sentido
horario o antihorario. (En este caso hemos convenido que para el método matricial el sentido
antihorario sería el positivo y que para el método de Cross sería positivo el sentido horario).
En el caso de los diagramas de momento, la convención sobre el sentido de los momentos que
se ha empleado viene dada por la forma que se flexan los elementos, de manera que los diagramas
se dibujan hacia el lado que se encuentran las fibras traccionadas.
Nosotros ahora vamos a hacer un acuerdo sobre los signos de los diagramas de cortante y
momento.
Los cortantes dibujados hacia arriba, serán de signo positivo y cuando sean hacia abajo serán
negativos.
En relación con los momentos acordaremos que son positivos cuando están dibujados hacia
abajo y son negativos cuando están hacia arriba. Estas son las convenciones más normalmente
usadas.
Cuando la viga no es horizontal usaremos las mismas convenciones, ubicándonos en la posición
del observador ya expuesta anteriormente (de frente a la barra y con el nodo inicial a la izquierda).
Para los esfuerzos axiles consideraremos que son positivos cuando son de tracción y negativos
cuando son de compresión.
En función de lo anterior para un pequeño tramo de una barra los sentidos positivos serán los
indicados en la figura: M
f N

V

i = nodo inicial observador V f = nodo final i
M

N

<!-- p. 43 -->

41

F) MEDIO ANCHO DE BANDA
Vamos a comparar para la misma estructura dos numeraciones de nodos diferentes, lo haremos
con la estructura del ejemplo ya analizado anteriormente.
Para la estructura I teníamos, según ya fue
I Pvisto que cuando colocábamos las doce
fuerzas en función de los doce 1 2 3 4
desplazamientos, la relación podía ser
agrupada en 16 cuadrados de 3x3, mostrando
la influencia de los desplazamientos de un
nodo sobre las fuerzas que se producen en
otro nodo. De esa manera podía subdividirse II P
esa relación de 12 por 12 en 16 partes en las
que cada una expresa la acción de tres 1 4 2 3
desplazamientos sobre tres fuerzas. En la
estructura I aparecían 6 cuadrados que tienen
todo cero, según se indica en la figura.
Para la estructura II cambian la ubicación de dichos cuadrados pero también aparecen los 6
cuadrados igual a cero, como indicamos en la figura.

X X 0 0 X 0 0 X
MAB

X X X 0 0 X X X
MAB

0 X X X 0 X X 0

0 0 X X X X 0 X

MAB=6 MAB =12

0=cero
X=diferente de cero

En el caso I puede observarse una banda en el centro rodeada de ceros. Podemos definir el
medio ancho de banda según se indica en la figura.
En el caso II la banda vendría a ser todo el cuadrado y el medio ancho de banda será el doble que
en el caso anterior.
Para la resolución del sistema de ecuaciones el número de operaciones necesarias es menor
cuando el medio ancho de banda es menor, un número menor de operaciones implica menos
tiempo de cálculo y además implica cometer menos errores de redondeo, o sea resultados mas
rápidos y más precisos.
El menor ancho de banda permite también disminuir el espacio de memoria que se utiliza, o sea
con la misma memoria empleada se puede resolver una estructura mayor.
De manera que debemos buscar que nuestro medio ancho de banda sea lo mas pequeño
posible. Esto lo lograremos si buscamos que la diferencia entre dos nodos que están contiguos
no sea muy grande. En la estructura I la máxima diferencia entre nodos contiguos es de 1, en
cambio en la estructura II es de 3.
Cuando se realiza la numeración de los nodos debe buscarse que no queden contiguos dos
nodos con diferencia de numeración muy grande. El programa da el medio ancho de banda de la
estructura, para que sea tenido en cuenta.

<!-- p. 44 -->

42

En el caso que se muestra a continuación es claro que es mejor la solución II.

I II
5 6 9 10

4 7 7 8

3 8 5 6

2 9 3 4

1 10 1 2

Máxima diferencia=9-2=7 Máxima diferencia=2

N) VINCULOS
Los vínculos se expresan indicando el nodo, luego la restricción según x, según y y finalmente la
restricción al giro. El número 0 indica que no hay restricción mientras que el número 1 indica que
existe restricción, o sea el nudo esta impedido de moverse en esa dirección.
Por ejemplo 2,0,1,0 indica que el nodo 2 no tiene restricciones según x, que según y esta impedido
de moverse y que puede girar libremente. Sería un vínculo de este tipo:

2

Si en cambio estuviera empotrado entonces las restricciones del nodo debieran ser expresadas
asi: 2,1,1,1 2

O) RESPONSABILIDAD
Los resultados obtenidos siempre deben ser verificados y analizados. La computadora realiza un
cálculo según nuestras indicaciones y no tendrá ni ella ni el programa, ninguna responsabilidad
sobre el proyecto estructural realizado. Del mismo modo que el uso de las calculadoras de mano
tampoco garantiza la corrección del proyecto. La computadora es una herramienta más poderosa
para el cálculo y esta puede ser su ventaja. Pero debe quedar claro que es solo una herramienta.
Pero el diseño estructural será por un largo tiempo responsabilidad exclusiva del técnico. Este
debe conocer si las hipótesis son adecuadas, saber sus limitaciones, ver si las cargas son correctas,
debe verificar críticamente resultados, etc.
En el diseño de una estructura no hay solo cálculos mecánicos, hay un conjunto de conceptos y
hay también aspectos de creación que solo puede realizar un técnico. Esto vale para cualquier
método de cálculo.
Visto de un ángulo diferente puede decirse que frente al colapso de una estructura por problemas
de cálculo habrá una responsabilidad moral y ética del técnico, pero también esta responsabilidad
puede llegar al terreno legal y hasta penal.
Volviendo a verlo del ángulo positivo puede decirse que durante muchos años seguirá siendo
necesario el técnico para el diseño estructural, difícilmente llegue a ser posible que un buen
operador PC pueda sustituirnos.
Por lo menos por algunas décadas esto parece casi imposible.

<!-- p. 45 -->

43

EN RELACION CON LA ENTRADA DE DATOS

\* Nombre del problema.
\* Cantidad de nodos.
\* Cantidad de elementos.

COORDENADAS DE LOS NODOS
\* Número del nodo, coordenada x, coordenada y. (Poner en orden los nodos desde el número
1 hasta el último, un renglón para cada uno)
CONECTIVIDADES
\* Número del elemento, número del nodo inicial, número del nodo final. (Poner en orden los
elementos desde el número 1 hasta el último, un renglón para cada uno).

RESTRICCIONES
\* Cantidad de nodos con restricciones.
\* Número del nodo, restricción según x, restricción según y, restricción al giro. (0 significa sin
restricción, 1 con restricción, colocar un renglón por cada nodo restringido).

PROPIEDADES DE LAS BARRAS
\* Cantidad de tipos diferentes de barras (en relación a sus propiedades geométricas, área e
inercia y a su módulo de elasticidad). Se deben utilizar las mismas unidades en que se
especificaron las cotas.
\* Area, inercia, módulo de elasticidad. (Propiedades del primer tipo de barras).
\* Cantidad de barras con estas propiedades.
\* Indicar uno a uno los números de las barras que tienen estas propiedades.
(Si hay más de un tipo de barra, se repiten los tres últimos renglones tantas veces como sea
necesario, hasta terminar)

CARGAS EN LOS NODOS (se indican en coordenadas globales).
\* Cantidad de nodos cargados. (si no hay ninguno, ingresar 0).
\* Nodo, fuerza según x, fuerza según y, momento. (Un renglón para cada nodo cargado).

CARGAS DISTRIBUIDAS EN LOS ELEMENTOS (Se indican en coordenadas locales)
\* Cantidad de cargas distribuídas (si no hay ninguna ingresar 0)
\* Número del elemento, valor de la carga distribuida, distancia desde el nodo inicial al principio
de la carga, distancia desde el nodo inicial al final de la carga. (un renglón para cada carga).

CARGAS CONCENTRADAS EN LOS ELEMENTOS (Se indican en coordenadas locales).
\* Cantidad de cargas concentradas en los elementos (si no hay ninguna ingresar 0)
\* Número del elemento, valor de la fuerza, distancia desde el nodo inicial a la fuerza (un renglón
para cada carga a ingresar).

EN RELACIÓN CON LA SALIDA DE DATOS

\* Repite todos los datos ingresados de la estructura.
\* Medio ancho de banda de la matriz.
\* Desplazamientos nodales (según orientación de los ejes de coordenadas globales).
\* Reacciones (según orientación de los ejes de coordenadas globales).
\* Fuerzas y momentos en los extremos de los elementos (para dibujar diagramas, según
convención indicada en el punto L de consideraciones sobre el programa).

<!-- p. 46 -->

44

EJEMPLO DE ARCHIVO DE DATOS

pórtico con ppropio (archivo de datos)
4
3
1,0,0
2,450,600
3,1350,0
4,1350,600
1,1,2
2,3,4
3,2,4
2
1,1,1,1
3,1,1,1
3
600,45000,200000
1
1
800,106667,200000
1
2
700,71458,200000
1
3
4
1,-270,-360,0
2,-270,-360,0
3,0,-600,0
4,0,-600,0
2
1,-0.9,0,750
3,-5.35,0,900
1
1,-135,450

unidades utilizadas para el ingreso de datos: cm
daN

<!-- p. 47 -->

45

III

2 4
I 0,20x0,35
7,50
0,20x0,40
0,20x0.30 II 6,00

1 3

4,50 9,00

ESQUEMA DE CARGAS

descomposición del peso propio
90daN/m
150 daN/m
120daN/m

535 daN/m = (360+175) daN/m

150 daN/m 2 III 4

I
135daN II
90 daN/m 200daN/m 4,50
120daN/m

1 3

<!-- p. 48 -->

46

CONSIDERACION DE LA COMPONENTE AXIL DEL PESO PROPIO.
APLICACIÓN DEL ARTIFICIO EXPUESTO, PARA LOS ELEMENTOS I Y II.

p´l 120 × ,750 p´l
\= = 450daN = 450daN
2 2 2

7,50
\= l

p´daN / m = p´daN / m +
120daN / m 120daN / m

p´l 120 × ,750 p´l
\= = 450daN = 450daN
2 2 2

Situación a Situación b
Se resuelve Se ingresa
manualmente al programa

ESQUEMA DE CARGAS TAL COMO SE INGRESAN AL PROGRAMA

(120 × ,750 )450 daN =
2
(200 × 6 ) 360 daN 600 daN =
360daN 2

270 daN ,535 daN / cm
270 daN
2 4 III

135 daN

II
,090 daN / cm

360 daN

270 daN 1 3
(200 × 6 ) 600 daN =
2

<!-- p. 49 -->

47

FACULTAD DE ARQUITECTURA
Curso de Estabilidad II 1999
Ejercicios de Pórticos

pórtico con ppropio

Las unidades de longitud son: cm

Las unidades de fuerza son: daN

Número de nodos 4
Número de elementos 3

Nodo Coordenada x Coordenada y

1 .00 .00
2 450.00 600.0
3 1350.00 .00
4 1350.00 600.00

Elemento Nodo inicial Nodo final

1 1 2
2 3 4
3 2 4

Clave para los tipos de apoyo de los nodos: 1 = apoyo, 0 = libre

Nodo Apoyo en x Apoyo en y Apoyo en r

1 1. 1. 1.
3 1. 1. 1.

Elemento Area Inercia Módulo

1 .60000E+03 .45000E+05 .20000E+06
2 .80000E+03 .10667E+06 .20000E+06
3 .70000E+03 .71458E+05 .20000E+06

Fuerzas aplicadas en los nodos

Nodo Carga x Carga y Momento

\1. -270.000 -360.000 .000
\2. -270.000 -360.000 .000
\3. .000 -600.000 .000
\4. .000 -600.000 .000

<!-- p. 50 -->

48

Fuerzas en los elementos:Carga distribuída

Elemento Carga dist. Principio de la carga Fin de la carga

\1. -.900 .000 750.000
\3. -5.350 .000 900.000

Fuerzas en los elementos: Carga concentrada

Elemento Carga concentrada Distancia desde el principio

\1. -135.000 450.000

MEDIO ANCHO DE BANDA = 9

DESPLAZAMIENTOS, REACCIONES Y FUERZAS EN LOS ELEMENTOS

Desplazamientos nodales:

Nodo Desp. x Desp. y Rotación z
1 .000000 .000000 .000000
2 1.370369 -1.051209 -.003362
3 .000000 .000000 .000000
4 1.358965 -.013346 .000460

Reacciones:

Nodo Fuerza x Fuerza y Momento z
1 1666.058 3062.124 137023.600
3 -1774.062 4158.870 515875.300

Fuerzas y momentos en los extremos de los elementos:

Elemento Nodo F. Axial (x) F. Cort. (y) Momento(z)

1 1 -2999.3410 504.4256 -137023.6000
1 2 -2999.3410 -305.5743 -52329.3500
2 3 -3558.8700 1774.0620 -515875.3000
2 4 -3558.8700 1774.0620 548561.7000
3 2 -1774.0470 1856.1310 -52329.3800
3 4 -1774.0470 -2958.8690 -548561.8000

\*****FIN DEL PROGRAMA*****

<!-- p. 51 -->

49

DIAGRAMAS DE SOLICITACIONES

1 135
daN I
Observ. 0.90
M 504
0 2
\= daN/cm
(
504
\+
2 99
) 1370 99 .4 36
50
− V
1370 305 daN
\=
13 13

523 M 450
C Situación daNm

a

2999
\+
T
450 Situación
b
C

3449 2999 N
\= daN

C

2549

<!-- p. 52 -->

50

3 4
II Observ.

1774 1774 V
daN

5159

M
daNm

5486

600
CSituacióna T 600 +
3559 3559

CSituación
b
N
4159 = daN

2959

C

<!-- p. 53 -->

51

5.35 daN/cm

2 4
I Observ.

1856
V daN

x 0 = ,3 47 m
x 0 = .347 m

2959

5486

M daNm 523

1856 × 3 . 47
2697 M 0 = − 523 = 2697
2

1774 1774
N daN C

<!-- p. 54 -->

52

REACCIONES

135× cos 53º α
α = 53º
135 × sen 53º

535 daN/m

4 2

135 daN

200 daN/m

150 daN/m

1666 daN 1 3 1774 daN
1370 daNm 5159 daNm

3062 daN 5159 daN

VERIFICACION DE LOS RESULTADOS

APLICACIÓN DE LAS ECUACIONES DEL EQUILIBRIO PARA ESTRUCTURAS
ESQUEMATIZABLES EN EL PLANO.

\1. ΣFVERT.=0

\-535x9-150x7,5-200x6-135.cos53º+3062,124+4159,87=0,006=0

\2. ΣFHORIZ=0

135.sen53º+1666,058-1774,062=0,004=0

\3. ΣM1=0 (Toma de momento con respecto al nodo 1)

\-150x7,50x2,25-535x9,00x9,00-200x6x13,50-135x4,50+4158,87x13,50+5158,753+1370,236
\=0,016=0

<!-- p. 55 -->

53

DEFORMADA

δ x 2 δ 4x 4
2 δ y 2 θ 4 δ y 4
θ 2

θ 4 θ 2 p..i p..i
p..i

1 3

p..i = punto inflexión
