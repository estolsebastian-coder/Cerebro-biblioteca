---
type: libro
title: "CERCHAS"
author: "Usuario"
categoria: "ESTRUCTURA"
paginas: 20
extraccion: "texto (OCR pendiente)"
fuente: "local:E:/MATERIAL DE CONSULTA/ESTRUCTURA/ESTRUCTURAS NO CONVENCIONALES/CERCHAS.pdf"
convertido: 2026-10-16
---

# CERCHAS

> Texto extraído de `ESTRUCTURA\ESTRUCTURAS NO CONVENCIONALES\CERCHAS.pdf` (20 páginas, texto (OCR pendiente)). El PDF original está en el disco E: (MATERIAL DE CONSULTA); `<!-- p. N -->` marca el inicio de cada página.

<!-- p. 1 -->

\1. TEORÍA GENERAL DE ESTRUCTURAS ARTICULADAS PLANAS.

Una forma fácil de formar una estructura articulada simple e indeformable es
partir de un triángulo formado por tres barras unidas en tres nudos no alineados e ir
añadiendo luego barras de dos en dos que se unen en un vértice (figura 1). Solo la
estructura triangular se comporta como un cuerpo rígido, pudiendo considerarse como la
forma mas simple de celosía (cualquier celosía poligonal no es rígida (ver figura abajo).

Estructura Triangular Canónica (cada triangulo solo esta en contacto con uno
anterior y otro posterior).

Figura 1

Simple no canónica. Deformable (no simple).

n = 5 ⎫
⎬ n = 5 ⎫
b = 7 ⎭ ⎬
b = 7 ⎭

Figura 3

Figura 2

La única condición que han de cumplir las dos barras para que se produzca
siempre una estructura rígida, es que no estén alineadas.

El nudo 5, en la posición de la figura 3, no tiene impedido su movimiento
vertical.

Mecanismo.

1

<!-- p. 2 -->

Las estructuras articuladas que se pueden generar en esta forma, es decir,
partiendo de un triangulo y añadiendo dos barras por nudo sucesivamente, se
denominan “celosías simples”. En estas estructuras, su llamamos:

b: número de barras
n: número de nudos

como añadimos dos barras por nudo a partir de los tres nudos y barras iniciales se
cumple:

barras = b nudos = n
b- 3 n-3
(barras añadidas) (nudos añadidos)

luego el número total de barras será

3 + b – 3 =3 + 2(n-3)
b – 3 = 2(n – 3) Ψ b = 2n –3

Esta ecuación nos da el número mínimo de barras necesario para que una
estructura de n nudos sea indeformable. Este número de barras es el mínimo, puesto que
n nudos tienen en el plano 2n grados de libertad, y si queremos formar con ellos un
sistema rígido pero libre en el plano, y por tanto con tres gados de libertad1, debemos
añadir 2n – 3 enlaces simples, es decir, 2n – 3 barras articuladas. Una celosía plana
indeformable que cumple que la relación b = 2n -3, se dice que es “estrictamente
indeformable”. Si una estructura articulada plana esta formada únicamente por
triángulos (figura 1), se dice que es una estructura “triangulada”. En el caso en que las
barras formen una sucesión de triángulos tales que cada uno de ellos únicamente es
adyacente al anterior y al posterior, se dice que tenemos una “estructura canónica”. En
la práctica se construyen muchas celosías trianguladas y canónicas; resultando para ellas
muy simple el cálculo de esfuerzos.

2 x8 − 3 = 13

2 x8 − 3 = 13

1 Nota : los movimientos en el plano son: Ux, Uy, φ

2

<!-- p. 3 -->

2 x 7 − 3 = 11

\2. ISOSTATISMO E HIPERESTATISMO.

Una celosía simple, formada a partir de un triangulo, es un cuerpo rígido que
tiene tres grados de libertad. Para impedir totalmente su movimiento, se han de disponer
tres vínculos que la unan al cimiento (figura 4).

r + b = 2 n

Figura 4

Si formamos una celosía simple partiendo directamente del cimiento (figura 5),
el numero de barras necesario para formar una celosía de n nudos es de b=2n.

1
A

4
2 C
5
6 8
9

E 3 7 10
B D

Figura 5

A diferencia del caso anterior, la celosía no tiene ningún posible movimiento de
sólido rígido. En ambos casos pues, podemos concluir lo mismo: para inmovilizar
completamente n nudos en el plano, tenemos que unirlos entre si y con el cimiento,
mediante m =2n enlaces simples (barras o vínculos equivalentes)2.

Esta condición no debe tomarse como una condición suficiente y pensar que
uniendo de cualquier modo n nudos con 2n vínculos vamos a tener un sistema rígido.

2 Debe notarse que un apoyo fijo( ) es equivalente a dos barras infinitamente rígidas, no

paralelas que unen el cimiento ( ) y uno móvil ( ) lo es una sola ( ). A veces se elige esta forma

de representar los apoyos.

3

<!-- p. 4 -->

Por ejemplo, el de la figura 6 es un sistema con 8 nudos y 16 vínculos y sin
embargo, es evidente que no es un sistema rígido. Por lo tanto, debemos establecer que
un sistema de n nudos es un sistema rígido cuando esta sujeto a m =2n vínculos
distribuidos adecuadamente.

n = 8 ; 2 n = 16
r = 3 ⎫
⎬ b + 3 = 16 b = 13 ⎭
2 n − 3 = 13

Figura 6

Una estructura que cumple las anteriores condiciones de ser rígida y de que el
numero de vínculos m=2n se dice que es “isostática” o “estáticamente determinada”, ya
que las 2n ecuaciones de equilibrio de los nudos permiten determinar los valores de los
2n vínculos, ya sean esfuerzos en barras o reacciones en los apoyos.

Cuando en una estructura m \< 2n el conjunto no es rígido y será un mecanismo
que sólo puede estar en equilibrio si las cargas exteriores cumplen ciertas condiciones.
En otras palabras, puesto que existen 2n ecuaciones de equilibrio y menor número de
incógnitas, aquellas impondrán también ciertas condiciones a las cargas exteriores para
que se puedan satisfacer.

r = 3
m = 4 + 3 = 7 \< 2 n
2 n = 4·2 = 8

Figura 7

La estructura de la figura 7 sólo puede estar en equilibrio si las cargas sobre 1 y
2 son verticales o no existe ninguna carga.

En el caso en que una estructura se de que m > 2n, la estructura se dice
“hiperestática” o “estáticamente indeterminada”, ya que el numero de incógnitas por
determinar es mayor que el numero de ecuaciones que nos proporciona la estática.
Cualquier vinculo de una celosía que exceda a los necesarios y suficientes para asegurar
su rigidez se denomina “vínculo superabundante”. La retirada de uno de estos vínculos
no hará inestable la estructura. En la figura 8 se ven algunos ejemplos de estructuras
hiperestáticas.

Figura 8

2 x 4 = 8 \< 9 2 x 4 = 8 \< 9

4

<!-- p. 5 -->

Las estructuras más comunes en la práctica suelen constituir un cuerpo rígido en
si mismo (figura 8) independientemente de los apoyos, y pueden tener movimientos
como cuerpo rígido los cuales se impiden con aquellos. Suele ser frecuente en tales
casos distinguir el hiperestatismo o isostatismo de la estructura en si misma y el debido
a los apoyos. Se pueden distinguir los casos siguientes, llamando “r” al número de
incógnitas en los apoyos:

• Hiperestática Externa r >3 (vínculos superabundantes, ver figuras superiores)
• Isostática Externa r = 3
• Inestable Externa r \<3
• Hiperestática Interna b > 2n-3
• Isostática Interna b = 2n-3 (Estrictamente indeformable)
• Inestable Interna b \< 2n-3

Algunos ejemplos se pueden ver en la figura 9.

r = 3 r = 4
b = 5 b = 6
n = 4 n = 4
5 = 4·2 − 3 6 > 4·2 − 3
b + r = 8 = 2 n b + r = 10 \< 2 n

r = 2
r = 3
b = 6
b = 4
n = 4
n = 4
6 > 4·2 − 3
4 \< 4·2 − 3
b + r = 8 = 2 n
b + r = 7 \< 2 n

(Una cualquiera de las barras 1,2,3,4, (Uno cualquiera de los apoyos móviles puede

puede ser eliminada sin que la movilidad ser considerado como igualmente supera-

desaparezca, cualquiera, es igualmente bundante, pero no la barra1, que impide el
superabundante). movimientoS horizontal).
Figura 9

5

<!-- p. 6 -->

Siempre que la estructura sea isostática interna y externa lo será en su conjunto.
No obstante, existen casos en el que la estructura es inestable internamente e
hiperestática externa, y el conjunto es isostático.

En la figura se pueden ver dos ejemplos de esto. En ellos, cada vinculo externo
de más sustituye a un vinculo interno, de modo que se sigue cumpliendo la condición de
isostatismo, es decir, que la estructura sea rígida, y se cumple que m=2n.

Hiperestática Externa
Inestable Interna
Isostática de Conjunto

Figura 10

r = 4 r = 6
b = 2 b = 6
b + r = 6 = 2 n b + r = 12 = 2 n
b = 2 \< 2 n − 3 b = 6 \< 2 n − 3

Como se dijo anteriormente, la condición de m=2n no es una condición
suficiente para que una estructura se estable y estáticamente determinada. Ya se vio, en
la estructura de la figura 6, un caso donde se cumplía que m=2n y la estructura tenia
partes con barras “superabundantes” y además era un mecanismo.

Existen casos en los que cumpliéndose m=2n, se presentan disposiciones de
barra tales que la estructura es estáticamente indeterminada, peor sin embargo, otras
formas geométricas próximas a aquellas no lo son. Estas estructuras son las que hemos
dicho que tienen una forma crítica. En la figura 11 se reproducen algunas de las formas
criticas antes mostradas. La estructura de la figura 11, que ha sido obtenida formando un
triangulo con dos barras alineadas, si se encuentra cargada como se muestra, se
comportara como si el nudo 5 no existiera y por tanto será estáticamente indeterminada.

b=7=2n-3 Formas no críticas
Forma crítica

Figura 11

6

<!-- p. 7 -->

\3. TIPOLOGÍA.

La disposición de la barras de una celosía dependerá, principalmente, de la
necesidades constructivas y arquitectónicas de la obra. En esencia, la función de toda
celosía es, fundamentalmente, la de una gran viga, sostener cargas a través de un vano.

Las estructuras articuladas planas que se utilizan en la práctica con mayor
profusión son las estructuras trianguladas. En estas fundamentalmente se distinguen tres
tipos.

En todas estas estructuras la parte superior del perímetro se llama cordón
superior, y la parte inferior, cordón inferior. Las barras de triangulación se llaman
montantes si son verticales y diagonales si son inclinadas.

\3. 1. Jácenas: son estructuras formadas normalmente por triángulos adosados en
fila o composición de formas obtenidas de este modo. Tienen forma alargada que en
muchos casos es rectangular. En la figura 12 se representan algunas de ellas.

Montantes

Tipo Warren

Cordon Superior

Diagonales

Cordon Inferior

Tipo Howe

Tipo Pratt

Tipo K

Figura 12

7

<!-- p. 8 -->

3.2. Armaduras de Cubierta. El contorno de la estructura es triangular generalmente (figura 13).

Inglesa

Polonceau

Tipo Swan

Belga

En diente de Sierra

Figura 13

8

<!-- p. 9 -->

3.3. Arcos y pórticos. (figura 14)

Figura 14

\4. SISTEMAS RETICULARES PLANOS DE NUDOS ARTICULADOS. MÉTODOS DE CÁLCULO DE SISTEMAS ISOSTÁTICOS.

4.1 Introducción.

Estudiaremos aquí únicamente los métodos de cálculo de sistemas estáticamente determinados; es decir, sistemas cuyos esfuerzos en barras y reacciones
pueden ser obtenidos con la sola aplicación de las ecuaciones de equilibrio que
proporciona la estática. Estos sistemas serán normalmente sistemas isostáticos internos
(b = 2n-3) y externos ( r = 3). Sólo en algunos casos particulares serán sistemas, como
los pórticos triarticulados, donde un vínculo externo sustituye a uno interno.

4.2. Cálculo de las Reacciones.

Una fase previa a todos lo métodos de calculo que se estudian es la
determinación de las reacciones. Estas se pueden obtener fácilmente por la simple
aplicación de las ecuaciones de equilibrio al sistema de fuerzas exteriores, incluyendo
las reacciones que actúan sobre la estructura completa, si esta es estrictamente
indeformable, o a cada parte que lo sea, si el conjunto no lo es (figura 15).

9

<!-- p. 10 -->

F2
F1 F1

F2

R1

R2 R3 R2 R4

R1 R3

3 Ecuaciones 6 ecuaciones
3 Incógnitas 6 Incógnitas

Figura 15

4.3 Flexión en las estructuras articuladas planas.

Tanto las cargas aplicadas sobre la celosía, como el peso propio de las barras,
producen la flexión de la celosía, principalmente en su propio plano. Los alargamientos
o acortamientos de las barras producen deformación de la celosía, dando origen en cada
barra a esfuerzos de tracción o compresión, o sea, a esfuerzos axiles o normales; las
correspondientes tensiones de las barras se llaman tensiones principales.

En el caso de celosías con uniones soldadas o roblonadas, la flexión del conjunto
origina también flexión en las barras, debido a la rigidez de los nudos; esta flexión de
las barras da lugar a tensiones adicionales, que se denominan tensiones secundarias. Sin
embargo, si las barras están convenientemente dispuestas de modo que sus ejes
converjan en cada nudo a un punto, hallaremos que la presencia de las tensiones
secundarias no afectará prácticamente la magnitud de las tensiones principales; así, en el
cálculo se puede prescindir de la rigidez de las uniones y suponer las barras articuladas.

Aún en el uso real de una celosía con uniones articuladas, existirá alguna flexión
en las barras debidas a su propio peso, pero es comúnmente de pequeño valor; es
práctica usual despreciar y remplazar el peso distribuido de cada barra por dos fuerzas
iguales concentradas en sus extremos, o sea, suponer el peso de la estructura
concentrado en sus nudos.

4.4. Métodos de los nudos.

Este método permite calcular los esfuerzos en las barras de celosías simples. El
método básicamente consiste en considerar sucesivamente cada uno de los nudos de la
estructura como sólido aislado y aplicar en ellos las condiciones de equilibrio; lo que se
hace fácilmente tanto de una manera grafica como analítica. Si se toman los nudos en un
orden tal, que en ninguno de ellos aparezcan más de dos fuerzas de magnitud y sentido
desconocidos pero de dirección conocida, se pueden ir determinando sucesivamente los
valores de estas fuerzas, que son los esfuerzos de las barras. En las celosías simples, por
su propia ley de formación, siempre es posible encontrar de una forma sucesiva, nudos

10

<!-- p. 11 -->

en los que solo existen dos incógnitas. En efecto, el último nudo formado, solo puede
tener las dos incógnitas de las barras que lo unen al resto (figura 16). Una vez
calculadas estas, el penúltimo nudo que se formo, también tendrá solo dos incógnitas
correspondientes a las barras que lo formaron. Así, yendo hacia atrás, podemos recorrer
todos los nudos hasta el triangulo original, en el que a cada nudo llegan solamente dos
barras.

7 5 3

8
6 4 2

1

Figura 16

Veamos la forma de proceder, sobre un ejemplo sencillo. Consideremos la
estructura de la figura 17, cargada con dos cargas de valor de P.

P
3 2 Determinación de las
reacciones:
3 Pl 5
M 5 = 0 ; Pl + = 2lR1 ; R1 = ∑ 2 4
5 3
5 1 R2 = 2 P − P = P 4 4 4
P
5/4P 3/4P

Figura 17

se debe adoptar un sentido de giro para recorrer las barras de cada nudo,
comenzando por los conocidos.

Figura 18

11

<!-- p. 12 -->

Considerando el equilibrio de la estructura completa, se obtienen fácilmente los
valores de las reacciones, de valor 5/4P y 3/4P.

Empezamos el análisis por el nudo 1, en el que conocemos la reacción y la
dirección de las otras dos fuerzas que intervienen. Dibujamos la reacción y, por sus
extremos, dibujamos paralelas a las direcciones de la barras 1-2 y 1-4. Para que se
cumpla que el nudo esté en equilibrio, las tres fuerzas han de formar un polígono
cerrado; condición esta que se nos permite determinar las fuerzas en las barras 1-2 y1-4.
Ambas tienen unan magnitud determinada por el segmento que va desde el extremo
correspondiente de 5/4P hasta el punto de intersección de las paralelas a las barras 1-2 y
1-4. El sentido de las fuerzas es el que produce un polígono cerrado. Hay que tener en
cuenta que las fuerzas obtenidas son las ejercidas por las barras sobre el nudo. Para que
cada barra este en equilibrio, ha de ejercer una fuerza igual y de sentido contrario sobre
el nudo de su otro extremo.

Pasamos al nudo 2. En el conocemos la carga externa P y la correspondiente a la
barra 1-2. Dibujamos ambas fuerzas, una a continuación de la otra, teniendo en cuenta
que el sentido de 1-2 es el contrario al que tenía en el nudo 1. Trazamos, por los
extremos de la resultante de P y 1-2, paralelas a las barras de fuerzas desconocidas y
procedemos igual que antes. Así se determinan 2-3 y 2-4. Pasando al nudo 3 se
obtendrán 3-4 y 3-5. por ultimo con el equilibrio del nudo 4 se obtiene 4-53 .

Como es lógico, al igual que se ha considerado gráficamente el equilibrio de los
nudos de una forma sucesiva para obtener dos incógnitas en cada uno de ellos, se
pueden escribir las condiciones de equilibrio de los nudos de una forma algebraica,
haciendo ∑ Fx = 0 y ∑ Fy = 0, para obtener igualmente dos incógnitas por nudo. Esto se
hará lógicamente en el mismo orden sucesivo, de modo que al plantear el equilibrio de
un nudo solo queden en él dos incógnitas por determinar. Para aplicar el método de esta
forma, se le asigna un sentido a cada fuerza desconocida, por ejemplo saliendo siempre
del nudo de modo que todas las barras trabajarían a tracción (figura 19). Si al aplicar las
ecuaciones de equilibrio la fuerza resulta positiva, el sentido supuesto es el correcto, si
no, lo es el contrario.

Figura 19

3 Del equilibrio del nudo 4 solo se obtiene una fuerza y no es necesario establecer el equilibrio de

5 que se cumplirá automáticamente. Esto no es más que una consecuencia de haber utilizado tres

ecuaciones de equilibrio para determinar las reacciones, y por lo que sólo quedaban 2n-3 ecuaciones

linealmente independientes por establecer.

12

<!-- p. 13 -->

Las ecuaciones de equilibrio son:

Nudo 1:
1 ⎫
− N 1− 4 − N 1− 2 = 0 2 ⎪⎪ N 1− 2 = − ,1 44 P
⎬
5 3 ⎪ N 1− 4 = ,0 72 P P + N 1− 2 = 0 ⎪ 4 2 ⎭

Nudo 2:

1 1 ⎫
N 1− 2 − N 2 − 4 − N 2 −3 = 0 2 2 ⎪⎪ N 2 − 4 = ,0 289 P
⎬
3 3 N 2 − 3 = − ,08645 P ⎪ − P − N 1− 2 − N 2 − 4 = 0 ⎪ 2 2 ⎭

Nudo 3:

1 1 ⎫ N + N − N = 0 2 − 3 3 − 4 3 − 5 = − N = ,086445 P 2 2 ⎪⎪ N 3 − 4 3 − 5
⎬
3 3 ⎪ N 3 − 5 = N 2 − 3 = − ,08645 P − N − N = 0 3 − 4 3 − 5 ⎪ 2 2 ⎭

Nudo 4:
1 1
− N + N + N − N = 0 ; 4 − 5 1− 4 2 − 4 3 − 4
2 2
1 1
N = − N + N + N = ,0 43 p 4 − 5 3 − 4 2 − 4 1− 4
2 2

4.5. Método de las Secciones. Método de Ritter.

Por este método podemos determinar el esfuerzo en una barra cualquiera sin
necesidad de calcular el resto de la estructura, siempre que sea posible dar una sección a
la estructura que la divida en dos partes y solo corte a tres barras, una o varias de la
cuales son las que pretendemos calcular (figura 20.a).

Conocidas las fuerzas exteriores y las reacciones que actúan sobre la estructura,
se considera el equilibrio de cualquiera de las dos partes es que se ha dividido la
estructura (figura 20.b). El esfuerzo en cada barra se obtiene fácilmente tomando
equilibrio de momentos respecto al punto de intersección de las otras dos. Si dos barras
son paralelas o se cortan en un punto muy lejano se pueden calcular los esfuerzos de
esas dos en la forma antes dicha y para la tercera tomar equilibrio de fuerzas según una

13

<!-- p. 14 -->

dirección4. En cualquier caso, hay tres ecuaciones de equilibrio y tres incógnitas. La
sección se puede dar de modo que corte a tres barras, o a un nudo y una barra. El nudo
implica dos fuerzas desconocidas y la barra que se pretende calcular la tercera.

a

b Figura 20.a

c

a)

a

Figura 20.b
b

c
b)

Vamos , por último, a considerar el método que se suele llamar “de la doble
sección de Ritter”, que se puede aplicar para calcular fuerzas en barras cuando, no es
posible trazar una sección que corte solamente a tres barras y separe a la estructura en
dos, pero si es posible trazar dos secciones que cada una de ellas separe a la estructura
en dos partes y corte a cuatro barras de las que dos son comunes a ambas secciones. En
la figura 21 y 22 se muestran dos casos donde es aplicable esta solución. Centrándonos
en el primero de ellos, se puede ver fácilmente que, tomando equilibrio de momentos
para cada una de las partes respecto al punto de corte de las barras no comunes, se
obtiene un sistema de dos ecuaciones con dos incógnitas que son las fuerzas en las dos

m m'

Figura 21.a

4 O tomar momentos respecto a cualquier nudo que no contenga a la 3ª fuerza.

14

<!-- p. 15 -->

m m' Seccion m-n
∑ M=0;∑ Pa + O
T3 T1
O=O'
T2
Figura 21.b
T4

n n'

Figura 22

barras comunes. Si llamamos M1 a los momentos de la fuerzas exteriores del lado
izquierdo de m-n respecto a O y M2 a los momentos de las fuerzas exteriores del lado
derecho respecto a O’ tenemos:

N · r · r − N + M = 0 ⎫ a a b b 1
⎬ ⇒ N a y N B − N · r ' − N · r ' + M = 0 a a b b 2 ⎭

Las fuerzas en las barras no comunes son fácilmente calculadas, una vez
conocidas Na y Nb, considerando el equilibrio de cada una de las partes de la estructura.
Se puede notar que el sistema de ecuaciones anterior no tiene solución si su
determinante es nulo; esto es, cuando ra/rb = r’a/r’b. Esto sucede cuando el punto de
corte de las barras a y b esta alineado con O-O’. En estas circunstancias es posible un
giro pequeñísimo alrededor del punto de corte de las rectas a y b. Nos encontramos ante
una forma crítica no deseable.

15

<!-- p. 16 -->

\5. IMÁGENES

16

<!-- p. 17 -->

CERCHAS EMPOTRADAS

17

<!-- p. 18 -->

18

<!-- p. 19 -->

CERCHAS EN VOLADIZO

19

<!-- p. 20 -->

20
