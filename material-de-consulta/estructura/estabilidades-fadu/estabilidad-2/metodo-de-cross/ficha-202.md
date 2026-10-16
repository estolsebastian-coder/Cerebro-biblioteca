---
type: libro
title: "Ficha%202"
author: "ili"
categoria: "ESTRUCTURA"
paginas: 84
extraccion: "texto (OCR pendiente)"
fuente: "local:E:/MATERIAL DE CONSULTA/ESTRUCTURA/ESTABILIDADES FADU/estabilidad 2/metodo de cross/Ficha%202.pdf"
convertido: 2026-10-16
---

# Ficha%202

> Texto extraído de `ESTRUCTURA\ESTABILIDADES FADU\estabilidad 2\metodo de cross\Ficha%202.pdf` (84 páginas, texto (OCR pendiente)). El PDF original está en el disco E: (MATERIAL DE CONSULTA); `<!-- p. N -->` marca el inicio de cada página.

<!-- p. 1 -->

2006

FICHA 2 | APUNTES SOBRE MÉTODO DE CROSS

Estabilidad de las Construcciones 2 | Facultad de Arquitectura | UdelaR

<!-- p. 2 -->

1

Se presenta en estos apuntes una exposición de las partes fundamentales del método
de Cross, que consideramos el más adecuado para un primer contacto de los estudiantes de
arquitectura con las estructuras hiperestáticas. Se trata de un método sencillo y fácil en su
parte operativa. A través de su aplicación y en cada una de sus etapas se visualiza el
comportamiento de la estructura, y los conceptos que se utilizan son fácilmente comprensibles
(momentos freno, rigideces, reparticiones, transmisiones).
El método seguido en la exposición es el que se viene desarrollando desde hace varios
años en el curso de Estabilidad 2do. el que, a su vez, está basado en lo fundamental, en la
tradición seguida en esta Facultad para la exposición del método, y que se remonta a las
clases dictadas por el Arq. Alberto Sayagués, sintetizadas en el libro del I.C.E,”Método de
Cross”, publicación Nº13, y posteriormente expuestas, con algunas variaciones, en los cursos
dictados por el Arq. Julio García Mantegazza.
Pretendemos con estos apuntes presentar un material de ayuda directa en el curso de
Estabilidad 2do, a los efectos de agilizar y sintetizar la exposición del tema en el desarrollo del
curso. Colaboraron en la realización de los originales, los Arqtos. Juan Sarachu (resolución de
los problemas), Diana Spatakis (gráficos y fórmulas) y Ma. Del Carmen Fontana (dactilografía.)

Arq. H. CHAMLIAN.
\1985.

Hemos entendido conveniente ampliar los apuntes sobre Método de Cross, con distintos
complementos tal como se han dictado en el Curso de Estabilidad 2do. en los últimos años.
El índice de los mismos es:

1 - ASPECTOS GENERALES.
2 - PROBLEMAS REFERENTES A MOMENTOS INICIALES DEL 1er CROSS.
3 - ESTRUCTURAS CON NUDOS DESPLAZABLES.
4 - RELACIÓN FORMA-SOLICITACIONES. (PARCIALIZACIÓN DEL TODO ESTRUCTURAL (1))
5 - PROBLEMA DE LOS APOYOS. (PARCIALIZACIÓN DEL TODO ESTRUCTURAL (2))
6 - DETERMINACIÓN DE ESFUERZOS AXILES.
7 - TEMAS PRÁCTICOS.
8 - TABLAS Y ÁBACOS.

Arq. H. CHAMLIAN.
1991

<!-- p. 3 -->

2

INTRODUCCIÓN

a) En análisis de estructuras, a los efectos del estudio de las solicitaciones, se distingue
entre estructuras isostáticas e hiperestáticas.
Particularizando al caso de estructuras cuyo estudio puede esquematizarse en el plano,
las condiciones analíticas de equilibrio de un sistema de fuerzas son tres: proyección de las
fuerzas sobre dos ejes cualesquiera debe ser cero, y momento respecto a cualquier punto del
plano también debe ser nulo.
Las estructuras cuyos sistemas de fuerzas actuantes pueden ser equilibradas, en sus
vínculos exteriores, recurriendo solamente a la aplicación de las tres ecuaciones anteriormente
indicadas, se llaman isostáticas. Estas estructuras presentan los mínimos vínculos para ser
estables.
Las estructuras que no pueden ser resueltas solamente con la aplicación de las
ecuaciones de equilibrio, se llaman hiperestáticas. En este caso debe recurrirse a ecuaciones
complementarias que expresen condiciones de deformaciones.
La distinción entre estructuras isostáticas e hiperestáticas es solamente a los efectos de
su análisis. En general, no interesa, como determinante, en el momento de la ideación de la
estructura resistente y que sea acorde con un determinado planteo arquitectónico. (Una
excepción lo constituyen ciertos tipos de suelos que pueden aconsejar el diseño de una
estructura isostática, o hiperestática de menor grado).
En el caso de tramos solicitados por flectores axiles y cortantes, que provocan giros,
acortamientos o alargamientos, y distorsiones, las únicas deformaciones que se considerarán
son los giros; se desprecian los restantes.

b) El método de CROSS posee las tres cualidades que deben exigirse a un método:
\-generalidad,
\-sencillez,
\-exactitud.

\*El método es aplicable a cualquier estructura, por complicada que sea, incluso con
tramos curvos, estructuras espaciales, etc.
\*La aplicación del método es sencilla, como consecuencia de la claridad intuitiva de su
procedimiento. Podemos imaginar qué es lo que ocurre en la estructura en cada etapa del
proceso de su resolución.
No es preciso recordar ni convenciones artificiosas, ni fórmulas complicadas; sólo tener
presente el sentido físico del problema y considerar el artificio del método: el mecanismo
natural de la transformación de una estructura con nudos frenados, a la verdadera, mediante
liberación gradual, permitiendo sucesivamente las deformaciones de un nudo: giros y
desplazamientos.

Cada barra viene definida por sus rigideces y los coeficientes de transmisión, que le son
propios y que no dependen de la situación que ocupa en la estructura.
La parte operativa del cálculo se reduce a simples operaciones aritméticas.
\*La exactitud del método deriva de la sencillez de su aplicación, que entraña un menor
riesgo de error, y de tener los cálculos siempre a la vista, progresando desde el primer
momento hacia el resultado final.

<!-- p. 4 -->

3

Es un método por aproximaciones sucesivas, lo que no quiere decir que sea un método
aproximado. La iteración es un método basado en la repetición de un cierto proceso; en este
método, los valores van acercándose cada vez más al resultado final. Ya que cada paso
mejora los valores de las incógnitas, pueden obtenerse resultados con la exactitud deseada sin
más que repetir el proceso un número suficiente de veces. El número de pasos depende de lo
acentuado que sea la convergencia de los resultados al valor final, y del grado de aproximación
necesario.
Por lo anterior, la exactitud se regula a voluntad, lo que es muy interesante para los
tanteos previos.

c) La determinación de solicitaciones, en estructuras hiperestáticas requiere, previamente,
de una definición formal de la misma.
A través de ésta se determinan, no solamente los valores de las cargas (donde deberán
incluirse los pesos propios de los tramos), sino los valores de rigideces, transmisiones,
momentos freno, coeficientes de repartición, etc.
Una vez halladas las solicitaciones, deben verificarse las secciones críticas. Como
resultado, pueden producirse dos situaciones: que las formas, proyectadas sean viables o no.
En esta última situación deberán ajustarse las formas, en las secciones no viables.
El ajuste del anteproyecto puede ser en algunos sectores, o en toda la estructura.
Debe determinarse si los ajustes realizados justifican o no, un reestudio de las
solicitaciones, pues producirán variaciones de los valores anteriormente indicados. Por
supuesto, no existen reglas fijas para indicar los caminos a seguir.
Para una etapa de anteproyecto, vamos a citar a algunos autores americanos (Urquhart,
O´Rourke y Winter). Establecen que no será necesario repetir el cálculo de los momentos salvo
en los casos en que las rigideces relativas resultantes difieran de las estimadas para el cálculo
inicial en más de un 30%, aproximadamente. Debe observarse, a este respecto, que las
variables que condicionan el dimensionamiento son las relaciones entre las rigideces, y no los
valores absolutos de estas últimas. Si en los cálculos de un anteproyecto, se hubieran
estimado por defecto las dimensiones de todas las piezas, en un mismo porcentaje, los
resultados del cálculo no quedarían afectados por el error indicado; quedaría por estudiar la
entidad de la variación del peso propio.

Puede ser válido el estudio de secciones en los bordes de las formas:

M N

<!-- p. 5 -->

4

1.1 En el estudio de estructuras hiperestáticas, es necesario considerar el problema de las
deformaciones.
En el caso que estamos tratando, estructuras esquematizables en un plano y compuestas
por tramos lineales, las solicitaciones que existen son momento flector, y esfuerzos axiles y
cortantes. Cada una de ellas producen deformaciones, pero las únicas que se consideran, por
su entidad, son las deformaciones producidas por el momento flector. Por tanto debemos
estudiar giros en tramos flexados y, en particular, se los estudiará en los extremos de los
tramos.

Como primera parte, se determinarán expresiones cómodas para la determinación de los
valores de los ángulos de giro, en los dos extremos, A y B, de tramos aislados simplemente
apoyados, y para tres casos de carga:

\-acción normal al eje del tramo y/o momento aplicado en el tramo.
\-solamente acción de un momento en el apoyo izquierdo A.
\-solamente acción de un momento en el apoyo derecho B.

Estas tres situaciones configuran un primer caso, que son la base para el estudio de
situaciones más complejas de apoyos, que se resuelven mediante superposición de los
primeros.
En el transcurso de esta parte, se definirán los conceptos de rigidez, transmisión y
momentos de fijación.

<!-- p. 6 -->

5

DETERMINACIÓN DE LAS EXPRESIONES DE LOS ÁNGULOS DE GIRO EN LOS APOYOS
DE TRAMOS FLEXADOS.

EXPRESIONES MATEMÁTICAS AUXILIARES Y ANTECEDENTES DEL MÉTODO DE
CROSS.

1.2 En un tramo en flexión, se considera un elementodx , y se trata de determinar, en primera
1
instancia, el valor :
r

Las deformaciones: total y unitaria, de las fibras,
tienen las expresiones generales:

d θ F ⋅ L δ σ
r δ = ε = = E ⋅ A L Ε
1
σ 1 y al nivel y1 se produce: ε1 = E

dx
El valor del ángulo dθ es: dθ =
y1 dx d θ r

δ
Pero también: dθ =
δ 1y

dx δ
Igualando: =
r 1y

En este caso: L = dx entonces:

1 δ 1 ε σ 1 = ⋅ = =
r dx y 1 y 1 y 1 ⋅ E

La expresión general de Navier para la determinación de tensiones normales para tramos en
M ⋅ y1flexión es: σ1 = I

1 M
Por lo tanto: = (1) r E ⋅ I

<!-- p. 7 -->

6

1.3 Tomando un tramo AB simplemente apoyado y flexado:

Se trata de hallar, en segunda
2 instancia, y12 , que es la distancia,
medida sobre una vertical, entre la
sección 1 y el corte con la tangente
dθ en 2.

x dx M
dy ≅ x tg dθ ≅ x dθ = = x dx
r E ⋅ I r

dx
x 2 M
x dx (2) Por lo tanto: y 12 = E ⋅ I x∫1
A B
1 2

dy
y d θ
12 2 en tg.

x 1 x
x 2

Si las secciones son las
3 extremas del tramo:
y BA A B θ A ≅ tg θ A = L
y AB θA θB θ B ≅ tg θ B = L

Por lo que:
yAB yBA
L x ⋅′ M ⋅ dx
θ A = (3) ∫ 0 L ⋅ E ⋅ I

L x ⋅ M ⋅ dx
θ B = (4) ∫ 0 L ⋅ E ⋅ I
x x´
L

<!-- p. 8 -->

7

Tomando la expresión para θ A , sacando E y L fuera de la integral y, dentro de ésta,
multiplicando y dividiendo entre I m inercia mínima del tramo, obtenemos:

1 L M ⋅ I m ⋅ x ⋅′ dx 1 L M ⋅ I m ⋅ x ⋅′ dx θ A = = E ⋅ L ∫ 0 I ⋅ I m E ⋅ I m ⋅ L ∫ 0 I

La expresión M ⋅ I m / I implica un diagrama de momentos reducido pues Im / I es un
número menor o igual a 1.

4

Entonces la integral es igual al momento estático θA1 θB1
del diagrama de momentos reducido con respecto al
A B extremo opuesto al que se está considerando:

A1 1
G θA1 = A1 ⋅ x1′ E ⋅ Im⋅ L

dx
1
x x´ θB 1 = A1 ⋅ x1
1x x´1 E . Im . L

E . Im
Definimos RIGIDEZ como el valor: χ=
L

La rigidez indica la mayor o menor oposición del tramo a ser deformado por giro. Dentro
de su valor, hay términos de discutible determinación pero que, al intervenir en el proceso del
método con valores relativos, se disminuye la importancia de no tenerlos bien definidos.

La inercia es una característica geométrica con repercusiones mecánicas: indica la
distribución de materia alrededor del centro de gravedad y la resistencia a la flexión. En caso
del hormigón armado, no se conoce en esta etapa su valor, pues es una incógnita el valor de
las armaduras, la sección fisurada, etc.

Por lo tanto, las expresiones anteriores quedan:

A1 . x´1 A1 . x1 θA1 = 2 (5) θB1 = 2 (6) χ.L χ.L

<!-- p. 9 -->

8

1.4 DETERMINACION DE LOS COEFICIENTES PARA LA RIGIDEZ (γ ó α) Y DE
TRANSMISION (β).

1.4.1 Se considerarán dos casos. El primero de ellos es el de un tramo simplemente apoyado,
con un momento MA en el apoyo izquierdo.

5

MA θ θ El área A2 se forma con un momento A2 B2 aplicado igual a 1, por lo tanto:

M A . A2 . x´2 M A θA 2 = 2 = (7) A B χ. L χ.γA
L

L2 A2 siendo: γA = (8) 1 G A 2 .x´ 2

x2 x´2
γ
En general se acostumbra trabajar con: α= (9)
4
A B
Con esta expresión se aclara que la rigidez es el momento que es necesario aplicar en el
M Aextremo de un tramo para producir un giro unidad, pues: χ.γA = θA
Sí θA = 1 , entonces: χ.γA = M A

El valor de γ implica la consideración del tipo de apoyos en el concepto de rigidez.
1 θAPor otra parte: =
χ.γA M A
1
Y sí MA = 1; entonces: = θA χ.γA
1
por lo que es el giro en A cuando actúa un momento unitario.
χ.γA

M A . A2 . x 2Del mismo modo: θB 2 = 2 (10) χ.L
L2
Para inercia constante,γA adopta el valor: γA = ∴ γA = 3 ; αA = .075 L 2 L
.1 .
2 3

<!-- p. 10 -->

9

Si actúa MB:

6
M B . A3 . x´3
θA 3 = 2 (11) χ.L MB
θ A3 θB3
M B . A3 . x 3 M B
θB 3 = 2 = (12) χ.L χ.γB
A B
L 2 L
γB = (13)
A3 .x 3 A3
1 G

A B x x´3

1.4.2 Como segundo caso, se considerará un tramo con un extremo apoyado y el otro fijo
(situación ficticia, comúnmente denominada de empotramiento perfecto) y con un
momento en el extremo apoyado.

Veremos dos situaciones:

A)

MA θA MB
θB =0

A B
M A y M B
SON DEL MISMO SENTIDO 7a

Se observa que en el apoyo B aparece un momento M B , cuyo valor se determinará a
continuación.

MA M B θA 2 θB2
A B A B θ A 3 θB3 L
A2
1 G
x 3 x´3
x2 x´2 G
A3 1
7b 7c

<!-- p. 11 -->

10

Las expresiones de los giros son:

M A . A2 . x´ 2 M B . A3 . x´3
θA 2 = 2 θA 3 = 2 χ.L χ.L

M A . A2 . x 2 M B . A3 . x 3
θB 2 = 2 θB 3 = 2 χ.L χ.L

El giro en B es nulo, por lo tanto:

θB 2 = θB 3 entonces: M A . A2 . x 2 = M B . A3 . x 3

A2 . x 2 A2 . x 2 M B = M A = βAB .M A (14) siendo: βAB = (15)
A3 . x 3 A3 . x 3

Para inercia constante βAB adopta el valor:
L
A2 . 1 3 βAB = ∴ β = 2 2
A3 . L 3
Posteriormente veremos otra manera de expresar βAB (fórmula 15)
La expresión del giro en A es:
θA = θA 2 − θA 3

M A ⎛ A2 . x´ 2 A3 . x´3 ⎞
θA = ⎜ 2 − βAB 2 ⎟ χ ⎝ L L ⎠

M A ⎡ ⎛ x´ 3 ⎞ ⎤ 1 M A
θA = ⎢ A2 ⎜⎜ x´ 2 − x 2 ⎟⎟ ⎥ 2 = (16) χ ⎣ ⎝ x 3 ⎠ ⎦ L χ.γA

L2
Siendo: γA = (17)
⎛ x´3 ⎞
A2 ⎜⎜ x´ 2 − x 2 ⎟⎟ A B ⎝ x 3 ⎠

Para inercia constante,γA adopta el valor:
L2
γA = ∴ γA = 4 ∴ αA = 1
⎛ L ⎞
⎜ ⎟ L 2 L L 3 ⎜ − ⋅ ⎟
2 3 3 2 L ⎜ ⎟
⎝ 3 ⎠

<!-- p. 12 -->

11

B) Si las condiciones de apoyo fueran inversas:

MA B MB
θA=0
A
B
8a

M A yM B
SON DEL MISMO SENTIDO

8b 8c
MA MB
θA3 θ B3
A θA2 θ B2 B A B

A3
1
G

1 G x 3 x´3 A2

x2 x´2

Las expresiones de los giros son:

M A . A2 . x´ 2 M B . A3 . x´3
θA 2 = 2 θA 3 = 2 χ.L χ.L

M A . A2 . x 2 M B . A3 . x 3
θB 2 = 2 θB 3 = 2 χ.L χ.L

El giro en A es nulo, por lo tanto:
θA 2 = θA 3 entonces: M A . A2 . x´ 2 = M B . A3 . x´ 3

A3 .x´ 3 A3 . x´3 M A = M B = βBA .M B (18) siendo: βBA = (19)
A2 .x´ 2 A2 . x´ 2

Posteriormente veremos otra manera de expresar βBA (fórmula 19)
La expresión del giro en B es: θB = θB 3 − θB 2

M B ⎛ A3 . x 3 A2 . x 2 ⎞
θB = ⎜ 2 − βBA 2 ⎟ χ ⎝ L L ⎠

<!-- p. 13 -->

12

M B ⎡ ⎛ x 2 ⎞ ⎤ 1 M B
θB = ⎢ A3 ⎜⎜ x 3 − x´3 ⎟⎟ ⎥ 2 = (20) χ ⎣ ⎝ x´ 2 ⎠ ⎦ L χ.γB

L2
siendo: γB = (21)
⎛ x 2 ⎞
A3 ⎜⎜ x 3 − x´3 ⎟⎟ A B ⎝ x´ 2 ⎠

1.5 DETERMINACION DE LOS MOMENTOS FRENO.

A continuación se determinarán momentos en los extremos de las barras con la
condición de deformación de giro nulo en los mismos. Se hará para dos situaciones: ambos
extremos sin giro (biempotrado) e impedimento de giro en uno de ellos y articulado en el otro
(empotrado-apoyado).
A su vez se estudiarán dos situaciones: valores de los momentos para cargas normales
al eje de la barra y/o momentos aplicados en el tramo, y para una situación de desplazamiento
de uno o de los dos extremos de la barra (sin cargas ni momentos en el tramo).
Es necesario aclarar aquí el sentido de los momentos que convenimos utilizar.
Existen dos tipos de convenciones de signos;

a) acción de la barra sobre el nudo:

b) acción del nudo sobre la barra (es la acción que ejerce el resto de las barras sobre el
tramo que se estudia);

Como este es el sentido de los momentos que se utilizan para hallar diagramas de
solicitaciones en el tramo, esta segunda convención es la que se aplicará en lo que sigue.

Para operar algebraicamente, utilizaremos los siguientes signos:

sentido antihorario sentido horario
signo signo - +

<!-- p. 14 -->

13

1.5.1 Tramo con cargas normales a su eje y con los dos extremos frenados (empotramiento
perfecto en ambos apoyos).

Se aplica superposición de tres casos:

MA MB 9a
θA=0 θB=0

A B

MA MB θA2 θB2 θ A3 θB3
A B A B A B θA1 θB1

A1
A 2 A3
M 0 G 1 G G 1

x1 x´1 x2 x´2 x3 x´3
9b 9c 9d

Las expresiones de los giros son:

A1 . x´1 M A . A2 . x´ 2 M B . A3 . x´3
θA1 = 2 θA 2 = 2 θA 3 = 2 χ.L χ.L χ. L

A1 . x1 M A . A2 . x 2 M B . A3 . x 3
θB1 = 2 θB 2 = 2 θB 3 = 2 χ.L χ.L χ.L

Los giros en los apoyos son nulos, por tanto:

θA1 − θA 2 − θA 3 = 0 A1 . x´1 − M A . A2 .x´ 2 − M B . A3 . x´3 = 0 (a)

θB1 −θB 2 −θB 3 = 0 A1 . x1 − M A . A2 . x 2 − M B . A3 . x 3 = 0 (b)

<!-- p. 15 -->

14

Multiplicando (a) por 3x y (b) por 3x restando ambas y despejando M A :

A1 x´1 x 3 − x1 x´3 M A = ⋅ (22)
A2 x 3 x´ 2 − x´3 x 2

Multiplicando (a) por 2x y (b) por 2´x , restando ambas y despejando M B :

A1 x´1 x 2 − x1 x´ 2 M B = ⋅ (23)
A3 x´3 x 2 − x 3 x´ 2

Para inercia constante, y carga uniformemente repartida:

2 L 2 L L
M 0 . L ⋅ L − ⋅ 2 2 3 2 3 2 3 2 2 p. L p.L p.2L M A = ⋅ = M 0 = ⋅ pues M 0 = ∴ M A = L 2 2 L L 3 3 8 8 12 L ⋅ L − ⋅
2 3 3 3 3

1.5.2 Tramo con cargas normales a su eje y con el extremo izquierdo articulado y el derecho
frenado.
Se consideran las figuras 9b y 9d:

θB1 − θB 3 = 0 A1 . x1 − M B . A3 . x 3 = 0

A1 . x1 M B = (24)
A3 . x 3

1.5.3 Tramo con cargas normales a su eje y con el extremo izquierdo frenado y el derecho
articulado.
Se consideran las figuras 9c y 9b:

θA1 −θA 2 = 0 A1 . x´1 − M A . A2 . x´ 2 = 0

A1 . x´1 M A = (25)
A2 . x´ 2
2 L
M 0 .L.
3 2 Para inercia constante y carga uniformemente repartida: M A = = M 0 L 2
⋅ L
2 3
p. L2
∴ M A = 8

<!-- p. 16 -->

15

1.5.4 Momentos freno para tramos con corrimientos de apoyos.

Los casos que se pueden producir son los que se detallan a continuación:

a) La pieza se desplaza sobre su
propio eje la misma cantidad. No
A A´ B B´
hay deformación de flexión
cualquiera sea el vínculo.

b) La pieza se desplaza paralelamente
A B a sí misma la misma cantidad.
Tampoco hay deformaciones de
A´ B´ flexión para este caso, cualesquiera
sean las condiciones de apoyo.

c) A B B´ Se desplaza un solo apoyo, por la
condición de los vínculos pueden
darse varios casos;

A´

c.1) A B B´ Ambos apoyos articulados; no hay
L deformación por flexión.

A´

Un apoyo impedido de girar y sec.2)
A L A desplaza uno de los apoyos:
B B´ B B´
En este caso hay deformación por
A´ flexión A´

c.3) Los dos apoyos impedidos de girar:
A L En este caso también hay
BB´ deformación por flexión.

LOS SENTIDOS DE LOS
A´ MOMENTOS SON IGUALES

d) Los dos extremos se desplazan
L B´ arbitrariamente.
A Se puede encarar como la
B combinación de dos movimientos
anteriores: 1) Se desplazan los dos
A´ apoyos paralelamente (caso b); 2)
L
Desplazamiento como en el caso c,
y pueden darse cualquiera de las
tres situaciones, que tiene dos casos
en que hay deformaciones por
flexión.

<!-- p. 17 -->

16

De lo descripto anteriormente, pueden extraerse tres reglas para determinar
deformaciones en barras con nudos desplazables e impedidos de girar (iniciación del 2º Cross):

\1) La deformación ∆ se mide sobre una recta perpendicular al eje de la barra en su
posición inicial, y el segmento se determina por la proyección, sobre esa recta, de los dos
extremos de la barra en su posición deformada.
\2) La proyección de los extremos del tramo, luego de la deformación, sobre una recta
coincidente con el eje de la barra, antes de la deformación, se mantiene igual a L (luz del
tramo).
\3) En los nudos frenados, (impedidos de girar), luego de la deformación, la tangente a la
deformada es paralela o coincide con el eje de la barra, antes de su deformación.

Se verán a continuación los procedimientos para la determinación de momentos freno,
con corrimientos de nudos.

1.5.5 Tramo con corrimiento de apoyos y con los dos extremos frenados.

Se aplica superposición de tres casos:

Aθ=0
MB
A

MA 10a
θB=0

MA θA2 θB2 MB
A B B A A B ψ θA3 θB3 .
x2 x´2

. ψ
G
1 G 1 L

x3 x´3 10b 10c 10d

<!-- p. 18 -->

17

Las expresiones de los giros son:

∆ M A . A2 . x´ 2 M B . A3 . x´3
ψ = θA 2 = 2 θA 3 = 2 L χ.L χ. L

M A . A2 . x 2 M B . A3 . x 3
θB 2 = 2 θB 3 = 2 χ.L χ.L

A los efectos de facilitar las expresiones, aplicaremos el teorema de la reciprocidad de las
deformaciones de BETI-MAXWELL:

1 1

A B A B
θA 2 θB2 θA 3 θB3

El giro del punto de aplicación del primer momento unitario originado por el segundo
momento unitario, es igual al giro del punto de aplicación del segundo momento unitario
originado por el primer momento unitario.
θA 3 = θB 2

De donde se concluye: A2 . x 2 = A3 . x´ 3 (26)

Con esta igualdad podemos plantear nuevamente las expresiones (15) y (19):

x3´ x 2 βAB = (15´) βBA = (19´)
x 3 ´x 2

Los giros en los apoyos son nulos, por lo tanto:

∆ M A . A2 . x´ 2 M B . A3 . x´3
θA = ψ− θA 2 + θA 3 = 0 − 2 + 2 = 0 (c) L χ.L χ. L

∆ M A . A2 . x 2 M B . A3 . x 3
θB = ψ+ θB 2 −θB 3 = 0 + 2 − 2 = 0 (d) L χ.L χ.L

<!-- p. 19 -->

18

Multiplicando (c) por 3x , (d) por 3´x , sumando ambas, despejando M A y multiplicando y
dividiendo el segundo término por 3x :

∆ L2 ( x 3 + x´3 ) ∆ L 2 x´3 ⎞
1 ⎟⎟ M A = χ = χ ⎛+⎜⎜ L A2 ( x´ 2 x 3 − x 2 x´ 3 ) L ⎛ x´ 3 ⎞ ⎝ x 3 ⎠
A2 ⎜⎜ x´ 2 − x 2 ⎟⎟ ⎝ x 3 ⎠

∆ M A = χ4αA (1 + βAB ) (27)
L A B

Obteniéndose αA a partir de la ecuación (17).
Multiplicando (c) por 2x , (d) por 2´x y operando análogamente:

∆ M B = χ4αB (1 + βBA ) (28) L

Obteniéndose αB a partir de la ecuación (21).

Para inercia constante:

∆ ∆ M A = M B = ⋅ χ⋅ 4 ⋅ 1 ⋅ (1 + 5.0 ) ∴ M A = M B = .6χ. L L

1.5.6 Tramo con corrimiento de apoyo derecho y con el extremo izquierdo articulado y el
derecho frenado.

B θ=0B A

11
MB

La aplicación de la expresión (28), con βBA = 0 , conduce a:

∆
M B = χ4αB (29)
L A B

Obteniéndose αB de la fórmula (13).

<!-- p. 20 -->

19

1.5.7 Tramo con corrimiento de apoyo izquierdo y con el extremo izquierdo frenado y el
derecho articulado.

θ=0 A
A B

MA 12

La aplicación de la expresión (27), con βAB = 0 conduce a:

∆
M A = χ4αA (30) L A B

Obteniéndose αA de la fórmula (8).
Para inercia constante:

∆
M A = χ4⋅ .075 L

∆
M A = 3χ L

<!-- p. 21 -->

20

\2. REPARTICIÓN

2.1 Hasta este momento, se han estudiado tramos aislados, con cualquier tipo de vínculos, y
cualquier tipo de cargas.
A partir de ahora, veremos qué ocurre cuando a un nudo concurren varios tramos,
acercándonos a la situación real de una estructura.
En esta parte se definirá el concepto de repartición, y se visualizará el artificio del método
de Cross para un ejemplo elemental.

1

2

4

3

2.2 Supongamos un nudo A, al cual concurren barras con distintos vínculos en su otro extremo,
existiendo cargas solamente en la ménsula.

1 MA

2

A

4

3

Inmovilizando el nudo A, aparece un momento freno MA, con el sentido indicado, que
producirá giro nulo en los extremos de los tramos.

<!-- p. 22 -->

21

2.2.1 Si quitamos el freno en A, el nudo gira, produciéndose las deformaciones que se indican,
provocadas por − M A .
El problema planteado es determinar el valor de los momentos en el nudo A, de los
tramos que concurren al mismo.

Aθ1 θA2

MA1
MA2

MA3 -MA

Aθ3

Por hipótesis se admite que todos los tramos concurrentes al nudo tienen el mismo giro:

θA1 = θA 2 = θA 3

Siendo la relación entre deformaciones (giros) y causas que las producen (momentos):

M A1 M A 2 M A 3 θA1 = θA 2 = θA3 = γ .χ1 γ2 .χ2 γ3 .χ3 1

Por otra parte, el momento en el nudo: − M A , se reparte entre los tramos, debiéndose
cumplir:

M A1 + M A 2 + M A 3 = − M A

La ménsula no colabora, pues ante la acción del momento − M A en el nudo, gira sin
oponer resistencia.

De ambas relaciones obtenemos:

M A1 M A 2 M A 3 M A M A = = = − = −
γi χi γ1χ1 γ2χ2 γ3χ3 γ1χ1 + γ2χ2 + γ3χ3 ∑

<!-- p. 23 -->

22

Particularizando al tramo 1:

M A1 M A = −
γi χi γ1χ1 ∑
γ1χ1 M A1 = − M A
γi χi ∑

Y generalizando para un tramo cualquiera:

γi χi M Ai = − M A ∑γi χi

Se define coeficiente de repartición al valor:

γi χi ir =
γi χi ∑

Por lo que:

M Ai = − ri M A

Esta expresión resuelve el problema planteado: la determinación de los momentos M Ai .

A los efectos prácticos, es conveniente simplificar la expresión del coeficiente de
repartición:
Dividiendo numerador y denominador entre 4, aparece el valor α y, como generalmente
operamos con barras del mismo material, se simplifica el valor E en la expresión de χ.
Resulta entonces:

I mi αi
L i ri =
I mi ∑αi L i

<!-- p. 24 -->

23

2.2.2 Otra simplificación sumamente práctica consiste en no operar con los valores de I m
(inercia mínima del tramo) sino con relaciones de inercia.
Se adopta como valor 1 a la menor de las inercias mínimas de los tramos que intervienen
con coeficientes de repartición. El valor de las inercias del resto de los tramos estará dado de
acuerdo con su relación con el de la inercia mínima.

⎡ I mi ⎤
⎢⎣ menorI m ⎥⎦ αi
Li ri =
⎡ I m ⎤
⎢ ⎥ menorI m α ⎥ ∑ ⎢ ⎢ L ⎥
⎢ ⎥ ⎣ ⎦

De acuerdo a lo ya visto, se debe aclarar que la suma de los coeficientes de repartición
de las barras que concurren a un nudo, debe ser igual a 1.00, y que al repartir se debe
equilibrar (cambio de signo del momento).

En síntesis, la condición que regula la repartición de un momento no equilibrado, es el
hecho que las barras que concurren al mismo nudo, deben girar un mismo ángulo. Entonces,
ese momento se debe distribuir en cada barra en proporción al momento necesario para hacer
girar cada extremo un mismo ángulo.
Si la rigidez es el momento que es necesario aplicar al extremo de un tramo para producir
un giro unidad, entonces el momento no equilibrado se distribuye entre los tramos concurrentes
a un nudo, proporcionalmente a sus rigideces.

<!-- p. 25 -->

24

2.3 ARTIFICIO DEL METODO DE CROSS APLICADO A UN CASO SENCILLO
A través de un ejemplo muy sencillo veremos las partes sustanciales del artificio y etapas
del Método de Cross.
El proceso se ha exagerado en cuanto a cantidad de secuencias, para facilitar la
comprensión del mismo.
Inicialmente se aplican frenos a los nudos donde concurren tramos con momentos
desconocidos, que les impiden girar y desplazarse.

B

1 C

2

A

4

3

D

2.3.1 Se aislan los tramos quedando cada uno de ellos en situación ya estudiada, de extremos
con giros nulos (ambos o uno de ellos). Esta es una situación ficticia pero conocida; en etapas
sucesivas se va aproximando a la situación de giro real para el nudo. Con las fórmulas ya
vistas, (o utilizando valores tabulados), pueden determinarse los momentos frenos (acción del
nudo sobre el tramo).

1
30

2
70 20

50
4

3

<!-- p. 26 -->

25

2.3.2 Se unen los tramos disponiendo en los extremos de cada uno los momentos hallados en
la etapa anterior.

1

30
2
70 20

4 50

3

2.3.3 En los nudos en los que existe más de un momento, se procede a la determinación de su
valor resultante.

B

1
C

2
100
A
4

3

D

<!-- p. 27 -->

26

2.3.4 Se determinan los coeficientes de repartición para los extremos de los tramos que
concurren al nudo A.
Se quita el freno en el nudo A, y se produce un giro del mismo con sentido contrario al del
momento freno.

θ θ

0.2
100 0.5
0
θ

0.3

θ

2.3.5 Se reparte el momento entre las distintas barras, de acuerdo al coeficiente de repartición
de cada una de ellas. Los momentos repartidos se trasmitirán al otro extremo de los tramos,
cuando corresponda, es decir, cuando el otro extremo pueda resistir momentos.

10

β = 0,5 25

20 β = 0,5

50
0
30

<!-- p. 28 -->

27

2.3.6 Se unen nuevamente los tramos y los valores hallados se disponen en la estructura.

10

25

50

20

30

2.3.7 Se superponen los momentos hallados en las etapas 3 (momentos frenos) y 7 (momentos
repartidos y transmitidos, que aparecen una vez retirado el freno).

10
25

30
50
20

20

70
50

30

<!-- p. 29 -->

28

2.3.8 Se suman los momentos que aparecen en cada sección (extremos de tramos). Se hace
notar que en el nudo A, donde se colocó el freno inicialmente, existe equilibrio de momentos.
En B y C no se quitará el freno, pues esa es la situación teórica de apoyo de esos
extremos.
10
B

5

C
20

70
70 A

20

D

2.3.9 Se aislan los tramos, disponiendo los momentos finales obtenidos en 8, iniciándose el
estudio de las solicitaciones en todos los tramos, de acuerdo a procedimientos ya conocidos.

10

1 5

2
20
70 70
20
4

3

<!-- p. 30 -->

29

3.1 Ya estamos en condiciones de abordar la solución de una estructura hiperestática más
compleja por el Método de Cross.
El procedimiento que se seguirá ahora es resolver un ejemplo concreto, bastante
completo, e ir indicando, paso a paso mientras se resuelve el mismo, las distintas secuencias
generales del estudio (guión del método).
A su vez, se irán agregando complementos y artificios del método, no vistos hasta ahora
(procedimiento del 2ºCross, etc.).

3.2 El objetivo del método es la determinación de momentos en secciones convenientemente
elegidas, a partir de los cuales pueden obtenerse las solicitaciones en todos los tramos, así
como descargas y reacciones en los apoyos. Para ello debe partirse de una definición formal
de la estructura como un dato de partida, ya sea en cuanto a esquema como a forma y
dimensiones de todas las secciones.

3.3 Determinación de los coeficientes α y β:
Las expresiones de los valores de α (para determinar coeficientes de repartición) y de β
(de transmisión de momentos) para los casos más generales se encuentran en la primera parte
de esta publicación.
Para algunos casos particulares de variaciones de inercia, los coeficientes se encuentran
en las tablas 5.2.1., 5.2.2., 5.2.3., de la publicación Tablas y Abacos, del I.C. La determinación

<!-- p. 31 -->

30

de valores se hace en función de la relación de la inercia mínima sobre la máxima del mismo
tramo, pues da una relación fácil de abarcar, comprendida entre 0 y 1.
Para relaciones intermedias respecto a las tabuladas, es válida la interpolación lineal,
incluso para valores intermedios de las cartelas.
Una vez determinado el coeficiente α (para el nudo), y a los solos efectos de determinar
el coeficiente de repartición, la barra se presenta frente a las demás como si fuera de inercia
constante con el menor valor.
En caso de inercia constante, los valores de β y α son:
\- tramo con ambos extremos fijos (o frenados): α=1; β =0.5
\- tramo con un extremo articulado y el otro fijo: α=0.75
Los valores de estos coeficientes convienen indicarlos sobre el esquema de la estructura.

CA AC
apoyo con cartela apoyo sin cartela
I m ⎛ .030 ⎞ 3 TRAMO AC = ⎜ ⎟ = ,0 053 α= ,9907 α = ,2 202
I 0 ⎝ .080 ⎠
tabla II-6 a/L=1 β = ,0 231 β = ,1041

TRAMO CD I = constante α = 1 β = 5,0

TRAMO DB I = constante α = 1 β = 5,0

α = 1 D
β = 0,5
α = 1
β = 0,5
C α = 1
β = 0,5
α = 9,907
β = 0,231

A B

<!-- p. 32 -->

31

3.4 Determinación de las rigideces de los tramos y los coeficientes de repartición: para las
luces deben tomarse los valores reales de las mismas, no su proyección. Las dimensiones de
las secciones se hallan en caso de inercia variable, hasta los extremos del tramo en el
esquema.
Los valores de las inercias de las secciones se encuentran en general, en la tabla 2.5., de
la publicación Tablas y Abacos. En caso de hormigón armado, la determinación de las inercias
se hace considerando la sección total de hormigón sin fisurar, y sin considerar el acero (valor
aún desconocido). Si la sección es nervada, la definición de la misma se hace de la siguiente
manera:
\- sección en L : ancho del ala be = ,225 hf + bw
\- sección en T : ancho del ala be = 6 hf + bw
debiendo ser el espesor del ala hf mayor o igual a 7 cm para ser considerado.

Por comodidad operativa se aconseja tomar a la menor de las inercias mínimas de los
tramos que intervienen con sus rigideces, (es decir, se exceptúan los tramos en cuyos
extremos ya se conocen los momentos finales, como por ejemplo, ménsulas), o la inercia del
tramo si es de sección constante, como de valor unidad.
Los valores de la inercia de los demás tramos (su inercia mínima si es de sección
variable, o la inercia del tramo, si es de sección constante) serán expresados en relación a la
unidad, resultando valores iguales o mayores que 1.

Para determinar la inercia del tramo (respecto al que se dió valor unidad), se recomienda
plantear la relación con los valores completos de los términos y luego simplificar; no es
necesario, pues, determinar los valores reales de las inercias ya que lo que interviene en el
coeficiente de repartición es la relación.
Luego se plantean las sumatorias de las rigideces (multiplicadas por α) en cada nudo, y
se hallan los coeficientes de repartición. La sumatoria de los coeficientes de repartición en cada
nudo debe valer 1.
Todo este proceso se recomienda hacerlo también en el esquema de la estructura para
evitar errores.

1
TRAMO AC I 1 = 1 L1 = ,492 m χ1 = = ,0 20 ,492

⎛ 80 ⎞ 3 19
TRAMO CD I 2 = ⎜⎝ 30 ⎟⎠ = 19 L2 = 14,14 m χ2 = 14,14 = ,134

⎛ 50 ⎞ 3 ,463
TRAMO DB I 3 = ⎜⎝ 30 ⎟⎠ = ,463 L3 = ,689 m χ3 = ,689 = ,067

<!-- p. 33 -->

32

D Σαχ = 2,01 αχ = 1,34
Σαχ = 3,32 αχ = 1,34 0,67
0,33 αχ = 0,67 C
0,40 αχ = 1,98
0,60

A B

,198 ,134
rCA = = ,060 rDC = = ,067 ,332 ,2 01

,134 ,067
rCD = = ,0 40 rDB = = ,033 ,332 ,201

3.5 Determinación de los momentos de fijación, o de empotramiento perfecto, provocados por
cargas perpendiculares al eje del tramo, o por momentos aplicados en el mismo:
Las expresiones de esos momentos en su forma más general en cuanto a tipo de carga y
variación de inercia del tramo, se encuentran en la primera parte de esta publicación.
Para casos especiales de variación de inercia, y ciertos tipos de carga (uniformemente
repartida en todo el tramo y concentrada en ciertas secciones) se encuentra el valor fácilmente
en las tablas 5.2.1., 5.2.2., 5.2.3., de la publicación Tablas y Abacos, a través de los
coeficientes m y m .
Si el tramo es de inercia constante, para numerosos casos de carga, las fórmulas se
hallan en la tabla 5.1.1. Para inercia constante y ciertas cargas (uniformemente repartida
parcial y concentrada) en las tablas 5.1.2., se determinan los valores de los momentos, si no se
desea utilizar las expresiones generales de la tabla 5.1.1.
Para los momentos de fijación, acción del nudo sobre la barra, se adoptará,
convencionalmente, un signo: (+) para el sentido horario y (-) para el sentido antihorario.

DETERMINACIÓN DE CARGAS.
(Sólo a efectos del p.p.: las barras de I variable se toman con carga uniformemente repartida
con su altura promedio).

,030 + ,080
TRAMO AC pp = × .030 × .2500 = 413 daN / m tramo
2
descarga de la cubierta = 500 daN/m tramo
carga total = 913 daN / m tramo
TRAMO CD pp = ,080 × ,030 × .2500 = 600 daN / m tramo
descarga de la cubierta = 500 daN/m tramo
carga total = .1100 daN / m tramo

<!-- p. 34 -->

33

TRAMO DB pp = ,050 × ,030 × .2500 = 375 daN / m tramo
descarga de la cubierta = 500 daN / m tramo
carga total = 875 daN / m tramo

,0 20 + ,0 40
MENSULA pp = × .030 × .2500 = 225 daN / m tramo
2
descarga de la cubierta = 500 daN / m tramo
carga total = 725 daN / m tramo

descarga de la ménsula sobre el tramo.

fuerza = 725 × ,250 = .1813 daN
725 × ,250 2
momento = = .2265 daNm
2

DETERMINACION DE MOMENTOS DE FIJACION O DE EMPOTRAMIENTO PERFECTO.

apoyo con cartela apoyo sin cartela
I m ⎛ 30 ⎞ 3 TRAMO AC = ⎜ ⎟ = ,005 m = ,01402 m = ,00422
I 0 ⎝ 80 ⎠

MCA MCA
C

o bién:

A
MAC
MAC

M CA = ,01402 × 371 × ,492 2 = .1259 daNm M CA = ,01402 × .2246 × ,200 2 = .1259 daNm
M AC = ,00422 × 371× ,492 2 = 379 daNm M AC = ,00422 × .2246 × ,200 2 = 379 daNm

<!-- p. 35 -->

34

TRAMO CD

D

C

D

MDC
C 2 .1089 ×14,14
M CD = M DC = = 18.145 daNm
MCD 12

o bien:
D

MDC
C 2 .1111× 14, 00
M CD = M DC = = 18 .145 daNm
MCD 12

TRAMO DB

M DB1 M DB2 M DB3
D D D

B B B
M BD1 M BD2 MBD3

<!-- p. 36 -->

35

.2621× ,230 2
M DB1 = M BD1 = = .1155 daNm 12

.1813 ×,1 42 × ,088 .1 813 × ,1 42 × ,088
M DB2 = 2 ⋅ ,088 = 377 daNm M BD2 = 2 ⋅,1 42 = 608 daNm ,230 ,230

.2265 × ,088 ,088 ⎞ .2265 × ,1 42 ,1 42 ⎞ = ⎛−⎜ 2 3 ⎟ = 207 daNmM DB3 = ⎛−⎜ 2 3 ⎟ = 739 daNm M BD3
,230 ⎝ ,230 ⎠ ,230 ⎝ ,230 ⎠

M DB = M DB1 + M DB 2 + M DB3 = −.1155 − 377 + 739 = − 793daNm

M BD = M BD1 + M BD2 + M BD3 = + .1 155 + 608 + 207 = +.1970 daNm

3.6 La etapa siguiente consiste en partir de una situación ficticia, pero conocida, de los nudos
(o de algunos de ellos). Se colocarán aparatos fijadores que les impida girar y desplazarse,
situación que se impondrá solamente a aquellos nudos a los cuales concurran barras con
momentos desconocidos en sus extremos, por lo que se hace necesario examinar atentamente
la estructura y determinar valores de momentos en los extremos de las barras, cuando sea
posible, por procedimientos ya conocidos.
Determinados los momentos de fijación (o de empotramiento perfecto) en los extremos
de los tramos que corresponda, se procede a quitar los aparatos fijadores, es decir se les
permite girar, a cada nudo por vez, en un cierto orden. Aparecerá un momento desequilibrante;
se equilibra repartiendo entre las barras que correspondan, y se transmite a los demás
extremos de las barras, cuando corresponda.
Equilibrado el nudo, se vuelve a colocar el aparato fijador y se sigue el mismo proceso en
el siguiente mudo frenado, si existe. El proceso se sigue hasta obtener valores de momentos
cuya diferencia con el del mismo, en la vuelta anterior, se considera despreciable.
No debe terminarse el proceso con una transmisión, salvo que se realice a un nudo al
que no se le quitará el freno.
Terminado el proceso hemos llegado a una posición de los nudos de la estructura en la
cual se les ha permitido girar, partiendo de una posición ficta y conocida de impedimento de
giro, a través de un proceso de liberación gradual.
Se suman los momentos en los extremos de cada barra, incluyendo los de fijación
iniciales, debiendo existir equilibrio en cada nudo. El proceso descripto se conoce como 1º
Cross, y es conveniente realizarlo sobre el esquema de la estructura.

<!-- p. 37 -->

36

18145
0,67 D
−793
−18145
0,33
0,40 C 1.259
0,60

A B
−379 SITUACION FICTICIA (CONOCIDA) 1970

−11.626
18.145
−5.726 0,67 −5.813 −793
−18.145
0,33
0,40
1.259
0,60

−379 1970
− 2.863

8.124
−15.3856 −13
3 20
−7 −204
41 304 −8124
−102 −3.042 −7 608 4540 −100 −11.626 −1.521 −1.498 15.856 18.145 9.080 −5.726 4 0,67 −5.813 −793 61 −18.145 913 D 0,33
13.619 0,40 0.5 β 1.259 C 0.5
0,60 β
β
0,5
0,231
A B
−379 1970
3.146 − 2.863
211 −749
14 −50
1 −3
2993 −1695

<!-- p. 38 -->

37

3.7 Se estudia cada tramo aislado con las cargas actuantes y los momentos hallados en (3.6
momentos del 1º Cross), y se determinan las descargas en los extremos de los tramos.
Se aconseja el siguiente procedimiento, válido en la mayoría de los casos:

\-si la barra no es vertical, descargar según verticales;
\-si la barra es vertical, descargar según horizontales.

Logradas esas descargas, se suman en cada nudo, y se descomponen en caminos
materiales, intentando llevarlas a los apoyos, donde deben encontrar su equilibrio. Pueden
darse dos casos:
A) Por caminos materiales, todas las descargas o van hacia los apoyos de la
estructura o se equilibran a través de barras, solicitando axilmente las barras que transitan.
Entonces, los momentos hallados en (3.6) son los definitivos en los extremos de los tramos, y
corresponde hallar los diagramas de solicitaciones, de acuerdo a la parte (3.12), que se verá
más adelante.
B) Hay fuerzas que, por caminos materiales, no se pueden transmitir a los apoyos o
equilibrar a través de las barras. Entonces se producirán deformaciones por flexión que
afectarán los momentos hallados en (3.6). A las fuerzas causantes de esa situación se les
denomina fuerzas F de desviación. En esta situación corresponde cumplir la etapa siguiente.

D

C

D

C

A B

<!-- p. 39 -->

38

F

3.8 Planteada la estructura bajo la acción solamente de la(s) fuerza(s) de desviación, se hace
un trazado de la deformada con los nudos frenados, sin giro, pero con posibilidad de
desplazamientos. Los desplazamientos de los nudos de cada barra son perpendiculares a su
eje (ver los casos posibles en la primera parte de esta publicación).
Se plantean las relaciones entre los desplazamientos de los nudos. En general esa
relación se hará a través de un triángulo, pudiendo darse como caso particular bastante
frecuente, un segmento de recta.
Se plantean momentos de fijación ficticios en los nudos que correspondan, pero
relacionados correctamente entre sí. Pueden seguirse dos procedimientos: dar un valor
arbitrario a un momento, o a un desplazamiento.
Con estos momentos se procede de igual manera a lo indicado en la etapa (3.6). Este
proceso se llama2º Cross.

MDC
MDB
MCD

MCA

MAC MBD

∆ 1 ,435 M AC = 4 ⋅ αAC (1 + βAC ) χ1 ⋅ = 4 × ,2 202 (1 + ,1041) ,0 203 ⋅ = ,3 227
L1 ,492
∆ 1 ,435 M CA = 4 ⋅ αCA (1 + βCA ) χ1 ⋅ = 4 × ,9907 (1 + ,0 231) ,0 203 ⋅ = ,8 755
L1 ,492
∆ 2 ,305 M CD = M DC = 6χ2 ⋅ = 6 × ,134 ⋅ = ,1734
L 2 14,14
∆ 3 ,376 M DB = M BD = 6χ3 ⋅ = 6 × ,0 67 ⋅ = ,2194
L3 ,689

<!-- p. 40 -->

39

Multiplicamos los valores obtenidos por 1000, de manera de mantener la proporción entre ellos
y obtener valores más cómodos para trabajar.

2.528
−3
4
4.339 −42
8 63 −2.528
−21 −632 −1 1.404 126 −21 1.734 −4.339 −316 0,67 D −312 2.808 −2.194 13 1.734 190 0,33
4.213 0,40 0.5 C β −8.755 0.5
0,60 β
β
0,5
0,231
A B
−3.227 −2.194
973 −156
44 −11
3 −2.361 −2.207

3.9 Se plantean las descargas en los nudos con las mismas consideraciones vistas en (3.7),
pero sin las cargas exteriores, solamente con los momentos en los extremos de las barras
hallados en (3.8).
Se deberá llegar a una fuerza de desviación F´ cuyo valor no será igual al hallado en
(3.7), pero de la misma dirección y sentido contrario.

D

C

D

C

A B

<!-- p. 41 -->

40

D

C F´

A B

3.10 Se halla la relación α=F/F´, y se multiplican los momentos hallados en (3.8) por α. Estos
momentos se suman a los hallados al terminar el proceso del 1º Cross, en (3.6), obteniéndose
los momentos finales, que era el objetivo del método, en los extremos de los tramos.

F .4 751
α= = = ,176
F ´ .2695

M (1er. CROSS) α M (2do. CROSS) M. FINALES.
MAC
MCA
MCD
MDC
MDB
MBD

3.11 Con los momentos finales hallados en (3.10), se plantean las descargas finales en los
nudos (con las cargas exteriores actuantes y esos momentos finales). Se puede proceder
también por superposición: los hallados en (3.9) multiplicados por α, más las descargas
halladas en (3.7).
Finalmente, al plantear la transmisión de carga a los apoyos, no debe existir fuerza de
desviación; debe darse equilibrio a través de los apoyos de la estructura o a través de las
barras.

<!-- p. 42 -->

41

D

C

D

C

B
A

D

C

A B

<!-- p. 43 -->

42

3.12 Se plantea la situación de cada tramo aislado y en equilibrio, con las acciones exteriores,
los momentos finales en los extremos de las barras, los axiles que transitan por la misma, y con
las iguales y contrarias a las descargas de los tramos.
Planteado el tramo de ese modo resultará fácil determinar los diagramas de solicitaciones
(momento flector, esfuerzo axil y cortante) de acuerdo a lo ya conocido.

D

C

V

X0

M

M 0

C
N

<!-- p. 44 -->

43

C C

C

A A

V M N

D

C

B

V M N

D

C

A B

REACCIONES

<!-- p. 45 -->

44

\4. CASOS DE SIMETRIA.
En estructuras simétricas (de forma, de carga, de esquema, etc.) el procedimiento de
Cross se simplifica notablemente, por lo cual se analizarán a continuación las dos situaciones
que puede presentarse.

4.1 Eje de simetría por un nudo.

Los momentos freno son iguales, pero de
sentidos contrarios y, a cada lado del apoyo
llegarán momentos trasmitidos, desde el otro
extremo de cada tramo, iguales, pero también
A de sentido contrario.

Por tanto, se puede estudiar media
estructura quedando el nudo central en
condición de frenado siempre, y el momento
en ese extremo es el inicial (de empotramiento
perfecto) más los trasmitidos.

4.2 Eje de simetría por el tramo.

En A y B aparecerán momentos iguales
pero de sentido contrario, siendo ambos ángulos
de giro también iguales y con sentidos contrarios.
A B
La expresión del momento en un apoyo es,
en general: M θA θB M

M = γ⋅ χ⋅θ Expresión (7) – pág. 6.

Si trabajamos con media estructura (por ejemplo, la parte izquierda), cuando expresemos
el valor del momento en A debemos incluir la influencia del momento en B.
Expresión(14)-pág.8.
Por tanto: M A = θA ⋅γA ⋅ χ + β(θB ⋅γB ⋅ χ)

Por simetría: γA = γB ,y por lo ya visto: θA = −θB

M A = (1 − β) γA ⋅ χ⋅θA

<!-- p. 46 -->

45

Esto significa que podemos operar con media estructura, siempre que en el tramo central
se afecte su rigidez (para determinar los coeficientes de repartición) por el valor (1-β).
En inercia constante: (1-β)=0,5.
Los demás valores, momentos de empotramiento perfecto, , etc. debe determinarse con
la luz real del tramo.

A continuación se estudia un ejemplo en donde se presentan ambos casos de simetría.
Atención: para hacer las descargas por caminos materiales conviene trabajar con la
estructura completa.

4.3 HALL DE EXPOSICIONES DE LA TOKYO INTERNACIONAL TRADE CENTER
CORPORATION, TOKYO, JAPON.
(documento: BAUEN IN STAHL 2,pág.107).

Se estudiará una de las costillas de hormigón armado que, ubicadas a distancias iguales,
sostienen el entrepiso para público y el techo metálico.
El entrepiso está formado por una losa nervada de doble carpeta (5cm c/u), cuyos moldes
llegan hasta la costilla y descarga, en total, 8.000 daN/m. El techo descarga una acción
concentrada, en G, de 130.000 daN.

G 130.000 daN

C F
D E

A ancho de costilla 30cm B

<!-- p. 47 -->

46

G ∑ αχ= ,2129 r1 = ,0 27
r2 = ,0 43
r3 = ,030

C D E F

A B

<!-- p. 48 -->

47

G

C D

D

D

D E
A
G

FC
D E

A B

<!-- p. 49 -->

48

Reacciones.

<!-- p. 50 -->

49

V (daN)

C

C

C

N (daN)

<!-- p. 51 -->

50

M (daNm)
tracciones por flector

<!-- p. 52 -->

51

COMPLEMENTOS

1 - PROBLEMAS REFERENTES A MOMENTOS INICIALES DEL 1er CROSS.

Como ya quedó dicho, a través del estudio de las estructuras por el método de Cross, se
obtienen los momentos en los extremos de las barras, siempre que no puedan ser
determinados por otros procedimientos; concretamente, veremos el tratamiento aconsejado
para el caso de: a) barras que se prolongan en ménsulas, y b) el caso de estructuras con
vínculos isostáticos con los apoyos exteriores.

a) Lo veremos a través de dos ejemplos.

A B C

El único momento de apoyo desconocido es el B, (A y C tienen momentos conocidos). Se
actúa por superposición:

A B C

momentos trasmitidos

\+

finalmente el momento en B
se determina asi :
A B C

2
p l coeficientes de repartición suponeindo articulaciones en A y C.
\= 4.000km
8 momentos frenos.
p l2
\= 9.000km momentos repartidos.
8 MOM. EN B ( FINALES).

<!-- p. 53 -->

52

Un caso más completo es el presentado en el ejercicio 8

D E

Solamente se desconocen los momentos en
C de la barra CA y CB. C
Los momentos en B y el momento en C de la
F G barra CD son conocidos.

Se actúa por superposición:
A B

D E

C
\+ F G

B B

Finalmente, los momentos en C desconocidos se
determinan de la siguiente manera:

<!-- p. 54 -->

53

b) Un caso que puede producirse es el de estructuras con apoyos exteriores isostáticos, es
decir, que con sólo las ecuaciones de equilibrio pueden determinarse las reacciones de
apoyos. Pero con estos valores, no pueden determinarse los momentos en los extremos de
todos los tramos, pero sí en algunos de ellos. Lo veremos a través de algunos ejemplos:
Tema 10

B

C E D

A

Por procedimientos conocidos (MA=0 para media estructura) puede hallarse la resultante
derecha en B: HB
Una vez determinada HB puede hallarse el momento en E del tramo EB. También se
determinan los momentos: D del volado CD, y los momentos freno de los tramos DE, DA, y AE.
De esta manera, quedan determinados los momentos iniciales del 1er Cross, de acuerdo
a lo que se indica en el siguiente gráfico:
(el tramo EB será tratado como una ménsula, con su carga repartida y una carga
concentrada HB en B).

(los valores son aproximados)
Una vez hallados los momentos finales, las descargas de tramo, las descargas de nudos,
y las descomposiciones de las fuerzas en caminos materiales, en D y E aparecerán fuerzas con
dirección del tramo DE, iguales y de sentidos contrarios.

<!-- p. 55 -->

54

Tema 3:

C

D
E F
R B

A B

R A

En esta estructura pueden determinarse RA y RB, y conocida ésta, puedo hallar el
momento en E del tramo EF (este tramo se considera como una ménsula con sus cargas
repartidas y RB en el extremo).
De la misma manera que el tema anterior, la situación inicial para el 1er Cross se indica
en la figura siguiente, y la etapa final de descomposición de las fuerzas en los nudos, debe
existir equilibrio a través de la barra DE.

<!-- p. 56 -->

55

Tema 14:

Esta estructura tiene un solo apoyo; continuamos el mismo con su dispositivo de
cimentación (supuesto un patín).

C

B
R

A a

\-R

El dispositivo de cimentación, con la reacción del tramo (de resultante –R), se lo trata
como una ménsula en el nudo A, y la situación de iniciación del 1er Cross sé gráfica a
continuación:

R a

(los valores son aproximados)

<!-- p. 57 -->

56

2 - ESTRUCTURAS CON NUDOS DESPLAZABLES.

a) El Ing. Español Carlos Fernández Casado establece las clases de desplazamientos de
los nudos en los siguientes:

Desplazamientos de nudos.

Grupo a)

α) β)

Grupo b)

γ) δ) η) ε)

Diversas clases de desplazamientos que pueden producirse.

Se estudiarán los desplazamientos que pueden producirse en la estructura,
considerándolos en dos grupos:
a) Los que son consecuencia de la variación de longitud de ciertas barras.
b) Los que corresponden a deformaciones transversales sin cambio de longitud de
las barras.
Los primeros son debidos a las siguientes causas:
Ι) Variaciones termohigrométricas.
ΙΙ) Esfuerzos longitudinales.
Y los del segundo grupo, a:
ΙΙΙ) Asiento de los apoyos.
ΙV) Fuerzas exteriores (viento, empuje de tierra, etc.)
V) Disimetría en las características de la estructura o en la solicitación.
VΙ) Empuje de las barras curvas o poligonales.
En otra parte del texto, indica:
Los desplazamientos pueden ser de cinco clases:
\1) Desplazamientos conocidos, como los debidos a dilataciones o contracciones de las
barras por variaciones de temperatura o retracción de fraguado, asiento de los apoyos, etc.
\2) Desconocidos, pero dependiendo directamente de las fuerzas exteriores; por ejemplo,
los desplazamientos laterales de una estructura elevada sometida a la acción del viento.
\3) Desconocidos, pero dependiendo directamente de los esfuerzos canalizados por la
estructura; es decir, consecuencia de los acortamientos y alargamientos producidos por los
esfuerzos longitudinales.

<!-- p. 58 -->

57

\4) Originados por desplazamiento lateral de la estructura al existir disimetría sus
características geométricas o elásticas o en la distribución de las fuerzas.
\5) Originadas por los empujes correspondientes a barras curvas o combinaciones de
barras rectas equivalentes a un arco.
De esta última clasificación, podemos hacer una nueva reagrupación:
2), 4), 5),son los casos comunes ya vistos y desarrollados hasta el momento;
\3) estos desplazamientos no se consideran, pudiéndose despreciar, según ya hemos
visto, por lo menos en un cálculo manual; se consideran en cálculo matricial con computadoras;
\1) para estas situaciones, al ser los desplazamientos conocidos (aunque muy difícil de
cuantificar) los momentos de 2do Cross serán los verdaderos, no necesitándose corrección a
través del coeficiente α.

b) Veremos, a continuación, una serie de ejemplos con casos de estructuras de nudos
desplazables. Se esquematizará el esquema de la estructura y se indicará a trazos gruesos la
figura deformada con los nudos frenados, es decir, la iniciación correspondiente al 2do Cross.
Se particularizará para casos de una fuerza de desviación (o para el caso de dos, cuando son
iguales).

F

2

1 3

2
1 F

3

<!-- p. 59 -->

58

F

2

1 3

2 3

F F

1 4

F F
2 3

1
4

<!-- p. 60 -->

59

F

2 F
4

1 5

3

2

1

3

<!-- p. 61 -->

60

c) Vamos a analizar, brevemente, cuando al terminar el 1er Cross tenemos más de una
fuerza de desviación distintas. Lo estudiaremos, genéricamente, para dos ejemplos:

F1 F2

Al terminar el 1er Cross se obtienen dos fuerzas de desviación: F1 y F2.
Debe procederse en dos etapas para el proceso del 2do Cross, pues la relación entre F1 y
F2 no se mantiene en un solo 2do Cross.
Se realiza superposición, permitiendo un desplazamiento y luego el otro (se dibujan las
deformaciones con los nudos frenados, y las fuerzas de desviación finales, luego de terminado
cada 2do Cross.) (los sentidos de las fuerzas son arbitrarios):

F´1 F´2 F´´1 F´´2

PRIMER SEGUNDO
2do CROSS 2do CROSS

Se plantean dos ecuaciones de equilibrio:
F1-αxF´1-βxF´´1=0
F2-αxF´2-βxF´´2=0
Signos algebraicos coherentes con los sentidos de los gráficos.
Resuelto el sistema de ecuaciones, se hallan los coeficientes α y β de corrección de
momentos.
Los momentos finales en los extremos de los tramos son:
M.FINALES = M.1erCROSS + αx M.primer 2do Cross + βx M.segundo 2do Cross.

<!-- p. 62 -->

61

F12)

2F

3F

Se indican las fuerzas de desviación, al terminar el 1er Cross. (En los gráficos, los
sentidos de las fuerzas se han fijado arbitrariamente).

F´1 F´´1 F´´´1

F´2 F´´2 F´´´2

F´3 F´´3 F´´´3

Como variante puede operarse, también de la siguiente manera:

F´1 F´´1 F´´´1

F´2 F´´2 F´´´2

F´3 F´´3 F´´´3

El sistema de ecuaciones es:
F1-αxF´1-βxF´´ 1-γxF´´´1=0
F2-αxF´2-βxF´´ 2-γxF´´´2=0
F3-αxF´3-βxF´´ 3-γxF´´´3=0
( signos algebraicos coherentes con los sentidos de las fuerzas en los gráficos).
Resuelto, es decir, hallando α, β y γ se procede para hallar los momentos finales, del
mismo modo que en el caso anterior.

<!-- p. 63 -->

62

3 - RELACION FORMA-SOLICITACIONES.
PARCIALIZACION DEL TODO ESTRUCTURAL.(1)

a) En ejemplos sencillos se observará la relación forma- solicitaciones:
Ι) En la página siguiente se muestra una estructura simple de esquema, y en los cinco
casos se varía la relación de inercias de los tramos horizontales respecto a los verticales.
Se observa para cada uno de ellos la variación de los diagramas de flectores; tenemos
dos casos extremos:
\* tramo horizontal biempotrado, para inercia del mismo pequeña respecto a los
tramos verticales;
\* tramo horizontal biarticulado, cuando el dintel es mucho más rígido que los tramos
verticales.
ΙΙ) En la otra página se distinguen los dos diagramas de flectores correspondientes a dos
tipos de vínculos en A y B.
Para empotramientos en A y B se observa que los momentos en los apoyos son mayores,
en tanto que para articulaciones en A y B aumentan los momentos de tramo.
ΙΙΙ) Al final se indican casos de inercia variable, en donde en la 1era situación se observa
aumento de momentos en C y D, zonas donde se ha aumentado la forma (acartelamiento).
En el caso extremo de variación de la forma, hemos disminuido la altura en A, B y E de tal
modo que al no resistir flectores, podemos esquematizar con articulaciones en esas secciones.
Se llegó entonces a una estructura isostárica, cuyos diagramas de flectores son familiares.

<!-- p. 64 -->

63

2l
8
p

I

5

p lTEORICO:
LÍMITE

2l
p 8

4

2l
p 8

3

l

2l
p 8
2l 2
p 12

2l
p 8

1

pTEORICO:

2l
p 24LÍMITE

<!-- p. 65 -->

64

VARIACIÓN DE TIPOS DE APO YO S EN A Y EN B .

II

EMPOTRADO ARTICULADO
EN A Y B . EN A Y B .

A B

ESTRUCTURA ISOSTÁTICA
DE 3 ARTICULACIONES:

INERCIA VARIABLE:
2 2
p l p l´
\=
8 2

C D C D

E
E

A B A B

DISMINUYEN LOS MOMENTOS
l EN LAS SECCIONES CON MENOR 2 III l´= ALTURA ( A,B Y E).

l

<!-- p. 66 -->

65

b) Complementamos los estudios anteriores con los gráficos extraídos de una publicación del
autor SCHUELLER; la observación atenta de las figuras permite extraer las conclusiones
correspondientes, que complementan lo ya dicho anteriormente.

L L
4 4

L

2M 2 M
3 3

M
M 3

k=1 k=2

M M
2 2
h h22
h M2 M M

COMPORTAMIENTO DE UN PORTICO EN FUNCIÓN DE LA RIGIDEZ RELATIVA DE LAS VIGAS Y COLUMNAS

c) Conocer las relaciones entre las formas (y las dimensiones) de las secciones de los
tramos que concurren a un nudo, y las solicitaciones, es de gran importancia en muchos
aspectos, principalmente para la adopción de hipótesis que, a veces, simplifican notablemente
la parte operativa en al análisis estructural. Por ejemplo, transcribimos parte de la anterior
norma Argentina (PRAEH), y que se refiere a los casos de estudio de estructuras corrientes de
edificación:
v) Vigas continuas.
v.1) Cálculo elástico.
v.1.1) Condiciones para el cálculo como vigas continuas.
v.1.1.1) Se permite calcular las vigas continuas sin tomar en cuenta los pilares o
columnas, o sea como vigas continuas sobre apoyos simples en los casos en que se cumplan
las siguientes condiciones:

<!-- p. 67 -->

66

i) De vínculo.
\1) Los nudos no sufran traslaciones, lo que estará asegurado por la presencia de
elementos de arriostramiento, estructurales o de cierre.
Jv / Lv ) ∑ ( 2) Cuando en cada nudo se verifique que ≥ 2 siendo Jv / Lv
Jp / Lp ) ∑ (
la relación entre momento de inercia y longitud de las vigas y Jp / Lp la misma relación para los
pilares. (rigideces de vigas mayores que los de los pilares).
ii) De cargas.
\1) Que ningún tramo supuesto simplemente apoyado tenga un momento máximo
que supere al triple del momento de tramo adyacente, supuesto en igual condición, si son de
igual signo, o igual al mismo si son de signos opuestos.
v.1.1.2) En los nudos en que la condición de vínculo v.1.1.1 i) 2) de valores:
Jv / Lv ) ∑ ( ∠ 1 (rigideces de vigas pequeñas en relación a la de los pilares) caso que
Jp / Lp ) ∑ (
podrá presentarse en la parte baja de esqueletos elevados, en que las columnas son muy
rígidas, deberá considerarse empotramientos perfectos en los extremos de las vigas, no
permitiéndose su cálculo como vigas continuas sobre apoyos simples.
v.1.1.3) En los casos en que los momentos correspondientes a los tramos supuestos
simplemente apoyados no cumplan la condición de cargas v.1.1.1.ii. (casos que se presentan
cuando hay grandes diferencias de cargas y/o luces en tramos sucesivos), sólo podrá
Jv / Lv ) ∑ (calcularse las vigas como vigas continuas sobre apoyos simples sí: ≥ 10
Jp / Lp ) ∑ (
(rigideces de vigas mucho mayores que la de pilares).
En los otros casos deberá resolverse la estructura aporticada indesplazable.
v.1.1.4) Los pilares extremos de apoyo de las vigas continuas, estando asegurada la
indesplazabilidad del sistema, serán considerados como un tramo más a cada lado y
calculados como tales.

<!-- p. 68 -->

67

4 - PROBLEMA DE LOS APOYOS.
PARCIALIZACION DEL TODO ESTRUCTURAL (2).

El tema resuelto en la publicación se hizo considerando una parte de la estructura, hasta
las secciones A y B, y aquí se dispusieron vínculos teóricos que más se aproximen a la
realidad.
El esquema adoptado fue suponer imposibilidad de giro en A y B:

A B
RA RB

Parcializar en partes la estructura es un recurso muy frecuente en la etapa de
anteproyectos (y algunas veces, en la etapa de proyecto), y, debe ser realizada con sumo
cuidado, siendo necesario, no solo experiencia, sino conocimiento del comportamiento del todo
estructural.

El esquema simplificado anterior puede corresponder, por ejemplo, a la siguiente realidad
(caso de dispositivos de cimentación en base a patines):

A B

C D

Nuevamente se plantea qué tipo de vínculos (en C y D) teóricos son los que más
concuerdan con la realidad; y aquí debemos considerar el tipo de suelo sobre el cual se apoyan
los patines.

<!-- p. 69 -->

68

Si el apoyo es sobre roca:

el esquema más adecuado es el nudo frenado (giro nulo) en C y D.

A B

C D

En caso de patines sobre arcilla (y de acuerdo al tipo de suelo), el tipo de vínculo
adecuado sea una situación intermedia entre el caso anterior y el que corresponde a
articulaciones en C y D:

A B

C D

<!-- p. 70 -->

69

Para el esquema inicial (empotramiento en A y B) y cimentación con pilotes, la realidad
correspondiente puede ser:

DESCARGA EN
EL APOYO A

La otra posibilidad de diseño para los apoyos en A y B, es articulación en ellos.
El esquema sería:

A B

RA RB

<!-- p. 71 -->

70

La realidad, para el caso de cimentación con patines, puede ser una de las dos
situaciones siguientes:

La articulación resiste una fuerza horizontal y otra vertical;
puede ser vista pues está sobre piso terminado.

La articulación resiste solamente una fuerza vertical; hay
más dificultades constructivas (pues está bajo suelo)

Para el caso de cimentación con pilotes, y de acuerdo a la entidad de las cargas,
principalmente, pueden producirse las siguientes situaciones:

<!-- p. 72 -->

71

Dijimos anteriormente: en general, que la estructura resistente sea hiperestática o
isostática no era una determinante previa, a la hora de proyectar (o anteproyectar) la misma.
En realidad, eso no es tan así. El tipo de suelo puede aportar determinantes que, a
veces, nos dan la pauta del tipo estructural que, al momento del análisis, resultará hiperestática
o isostática.
Determinados tipos de terreno pueden provocar asientos diferenciales (o mejor,
movimientos diferenciales, hacia arriba o hacia abajo, de los apoyos, y de cierta entidad), que
alteran las solicitaciones. Esto, en sí, no es de temer; el hecho es que ese fenómeno es difícil
de prever y de cuantificar.
Para estas situaciones es aconsejable proyectar estructuras que se vean afectadas en
poco grado, o en ninguno, en el trazado de las solicitaciones. Esto se logra con estructuras
isostáticas o hiperestáticas de poco grado.
Respecto a este tema, transcribimos las indicaciones que dan los autores: A. GUERRIN,
R. C. LAVAUR y PH. LECROQ:
Según la naturaleza de los apoyos, los apoyos sobre el suelo pueden ser articulados o
empotrado; las dos soluciones son posibles, viniendo la elección condicionada por
consideraciones sobre la naturaleza del terreno; el empotramiento de un pilar en la cimentación
sólo puede concebirse si el suelo es indeformable. En el caso contrario, el empotramiento en la
base del pilar impondrá al terreno solicitaciones variables, que introducirán al terreno
deformaciones variables entre uno y otro extremo de la zapata; ésta, pues, tendrá que girar, lo
que hará disminuir los momentos en la base del pilar; esto, bajo el punto de vista del
empotramiento del pilar, no supone ningún inconveniente, pero, por el contrario, sí que puede
serlo para el resto de la estructura, donde se incrementarán las solicitaciones. Sólo sobre
excelentes terrenos: rocas. margas secas o gravas arenosas, deben suponerse que se
consigue un empotramiento perfecto de la base de los pilares. En los pórticos con dos pilares,
si sólo se prevén articulaciones en las bases de los pilares, el sistema resulta hiperestárico;
para conseguir una construcción isostática, habrá que añadir otra articulación en un punto
cualquiera de la estructura. El problema se centra aquí en la elección del tipo que resulte de
más interés. Las consideraciones sobre el tipo de terreno van a jugar un importante papel. En
un mal terreno de cimentación, los asientos son de temer, pues, si se producen bajo las cargas
de servicio, producirán una redistribución de las leyes de momentos, si la estructura es
hiperestática, con riesgo de formación de fisuras y de desorganización general grave. Como
consecuencia, un sistema con tres articulaciones se impondrá en el caso de terrenos de
cimentación malos. En los otros casos es mejor adoptar una construcción hiperestática: es
ligeramente más económica desde el punto de vista de las cuantías de materiales y evita
también articulaciones relativamente costosas.
También relacionado con el tema que estamos tratando, WAYNE-C.TENG indica:
El giro de un patín, sometido a un momento o a una carga excéntrica, no puede ser más
que estimado por medio de cálculos simples basados en una buena experiencia.
Por ejemplo, un patín de pequeñas dimensiones, apoyado a poca profundidad sobre
arena, tiende a girar pues la arena “se escapa” fácilmente bajo los bordes del patín.
Si la profundidad es mayor, la arena está sometida a una presión debido al peso de las
partes adyacentes.
La importancia relativa de la influencia de los bordes disminuye cuando las dimensiones
del patín aumentan.
No se puede, pues, considerar como sin giro la base de un pilar que se apoya en un patín
de pequeñas dimensiones, a poca profundidad, en un terreno pulvurulento (arena).
Al contrario que las arenas, las arcillas y materiales arcillosos, se aproximan a un material
elástico y son capaces de resistir tensiones mayores en los bordes.

<!-- p. 73 -->

72

Además, una gran parte del asentamiento de patines apoyados sobre arcilla se prolongan
en un largo período (consolidación), los momentos flectores que actúan durante períodos
cortos, no provocan más que rotaciones sin importancia.

5 - DETERMINACION DE ESFUERZOS AXILES.

Veremos de qué modo el Ing. Español Carlos Fernández Casado (“Cálculo de estructuras
reticulares”) expone los fundamentos del método para obtener solicitaciones (en particular,
axiles) que nosotros denominamos método tramo por tramo:
La hipótesis de partida en el método de Cross es la de empotramiento perfecto en los
nudos, llegando a la situación real (empotramiento elástico) de las barras en la estructura, por
la aplicación sucesiva de pares que van reduciendo (es decir, variando) los de empotramiento
perfecto. También podríamos partir de la hipótesis contraria, es decir, de articulación en todos
los nudos, a los cuales se aplicarían pares sucesivos hasta llegar a la situación real.
Esta segunda hipótesis no conviene para el cálculo de momentos, pero sí es valiosísima,
en ciertos casos, para el cálculo de los esfuerzos longitudinales y transversales, pues las
condiciones de la estructura no se alteran al introducir articulación en los nudos que sean
precisos, siempre que pasen a ser acciones exteriores los pares de empotramiento ( los
momentos en los extremos) correspondientes. Estos pares dan lugar a reacciones
hiperestáricas, que, combinadas con las isostáticas (las obtenidas suponiendo el tramo
biarticulado) y sumadas en cada nudo, proporcionan las fuerzas que es preciso descomponer
según las direcciones de las barras que concurren a él.
Más adelante indica:
Cálculo de los esfuerzos longitudinales. El problema es clásico cuando se suponen nudos
articulados y fuerzas actuando en ellos. (Se refiere al caso de estructuras trianguladas,
cerchas, a las que se aplica cremona).
Se suman en cada nudo las acciones en dicho extremo de todas las barras que en él se
juntan, obteniendo así la fuerza que actúa en el nudo, la cual se descompone en las
direcciones de dichas barras para obtener los esfuerzos longitudinales en las mismas. Si los
nudos no están articulados y las fuerzas actúan sobre las barras, podemos reducir el caso al
anterior, determinando también las acciones en los nudos, que ahora constan de términos
isostáticos (tramo biarticulado sin momentos en apoyos) e hiperestáticos (biarticulado y sólo
con momentos en apoyos) (éstos igualan a la suma de los pares de empotramiento
correspondientes a la barra, divididos por la luz).
El procedimiento operatorio se reduce a ir efectuando las descomposiciones de las
fuerzas de nudos, empezando por uno de segundo orden (es decir, que las fuerzas en el nudo
se descomponen en 2 direcciones) y continuando en los siguientes, a los que se llevan ya
conocidos los esfuerzos de las barras que proceden de los anteriores nudos.
La parte operativa del método, y un ejemplo, se indica en la parte SOLICITACIONES.
(Repartido en las primeras clases).

6 -TEMAS PRÁCTICOS.

Se presenta a continuación una serie de ejercicios que abarcan aplicaciones varias y que
tienen como objetivo completar la asimilación del tema.
Para algunos de ellos se complementa la presentación adjuntando documentos a partir de
los cuales se propusieron los temas, que se simplificaron a los afectos de posibilitar su
aplicación práctica en el curso.

<!-- p. 74 -->

73

\1) Hall de Exposición de La Tokio Internacional Trade Center Corporation, Tokio, Japón.
Documento: Bauen in Stahl 2, Pág.107.

G

C F
D E

A B

ancho de costilla 30cm ESC. 1.100

Se estudiará una de las costillas de hormigón armado que, ubicadas a distancias iguales,
sostienen el entrepiso para público y el techo metálico.
El entrepiso está formado por una losa nervada de doble carpeta (5 cm c/u), cuyos
moldes llegan hasta la costilla y descarga, en total, 8.000 daN/m.
El techo descarga una acción concentrada, en G, de 130.000 daN.
Estudio de solicitaciones con diagramado de flectores, axíl, cortante e indicación de zonas
de tracciones provocadas por el momento flector.
Verificar la sección que se considere más comprometida y propuesta de ajuste si se cree
conveniente.

<!-- p. 75 -->

74

\2) Pista cubierta para patinaje en hielo y otros deportes en Boulogne.
Documento: L´architecture d´aujourd´hui Nº. 64, pág.82.

ancho de costilla 30cm ESC. 1/200

Descarga total de los cierres sobre todos los tramos es de 500 daN/m. lineal de tramo.
Diagramas de solicitaciones y de tracciones provocadas por el flector. Descargas y
reacciones en los apoyos. Estudio de secciones de interés (críticas) y propuesta de ajuste, en
caso de ser necesario.

\3) Tribuna en la zona cubierta de Estadio en Zagreb, Yugoslavia.
Documento: L´architecture d´aujourd´hui Nº. 64. pág, 15.

Ancho de costillas 20 cm TENSOR
Descarga del techo: 600 daN/mi.

Diagrama de solicitaciones, y de tracciones provocadas por el flector. Descargas y
reacciones en los apoyos. Estudio de secciones de interés (críticas) y propuesta, de ajuste, en
caso de ser necesario.

<!-- p. 76 -->

75

\4) Tribuna descubierta del Estadio en Zagreb, Yugoslavia.
Documento: L´architecture d´aujourd´hui Nº. 64. pág, 15.

Ancho de costillas 30 cm
Descarga de las gradas 4500 daN/mh.

Diagramas de solicitaciones. Descargas y reacciones en los apoyos. Estudio de
secciones de interés (críticas) y propuesta de ajuste en caso de ser necesario.

\5) Tribuna descubierta del estadio de Pescara, Italia.
Documento: L´architecture d´aujourd´hui Nº. 76. pág, 6.

Ancho de costillas 30 cm
Descarga de los escalones prefabricados 2000 daN/mh

Diagramas de solicitaciones y tracciones provocadas por el flector. Descargas y
reacciones en los apoyos. Estudio de secciones de interés (críticas) y propuesta de ajuste en
caso de ser necesario.

<!-- p. 77 -->

76

\6) Tribuna cubierta del Estadio Deportivo de la ciudad de Dusseldorf (Alemania), para el
Mundial de 1974.
Documento: Boletín del Cemento Protland Argentino. Año V. Nº. 24. Setiembre- octubre
de 1971. pág. 2 y 3.

2ª. Prueba. Curso controlado. 29/10/72.
F 40.000 K

40.000 K

E

Las gradas, entre C y B, están
construidas con escalones prefabricados que
descargan en total, 5000 daN/m lineal medido
horizontalmente. D
La cubierta, formada por piezas
prefabricadas y pretensionadas, descarga en
la costilla acciones concentradas en E y F
con magnitud, dirección y sentido que se C
indican en el gráfico.

B

ESC. 1/200

ancho de costillas 50 cms.

A

Se pide diagramas de solicitaciones y de tracciones (provocadas por el momento flector)
solamente en los tramos DC y CB, realizando todas las operaciones previas necesarias a tal
fin. En esos tramos, estudiar la sección que se entienda más crítica y ajustar la forma en caso
de ser conveniente.

<!-- p. 78 -->

77

\7) Parte escrita del examen del 28/8/86. Tema basado en un pabellón dentro del
predio para exposiciones ganaderas (Prado)

cubierta liviana
2.000 K 4.000 K 2.000 K

I 4.000 K J 4.000 K K

D E F G H

500 k/m 350 k/m

A B C

ESC. 1/200
ancho 25 cms.

Se pide: *Diagramas de solicitaciones en todas las barras y diagramas de tracciones
provocadas por el flector.
\*Reacciones de apoyos.
\*Verificación de secciones críticas, con propuesta de ajuste en los casos en que
no fueran viables.
D
CORTE 1-1 E

\8) Prueba escrita 4to. período ordinario
del 14/11/72.
C
F G

Se indica la estructura de trampolín
armado, pulida y pintada al epoxi, que
conforma un trampolín el borde de una
piscina de dos plataformas de espesor
10 cm y que soportan una sobrecarga A B ESCALA 1/100
de 300 daN/m2. Ancho de costillas: 20 cms.
en A y B articulaciones fijas.

PLANTA

1 1

<!-- p. 79 -->

78

\9) Curso controlado 1987: 1ª prueba parcial, 6/9/87.

E F K L

C D I J

A B G H

15.000 daN 20.000 daN
2.500 k/m
Ancho 20 cm 4.500 daN/m
15.000 daN 20.000 daN
2.500 daN/m

Estructura continua de hormigón armado, basado en el anteproyecto para un Liceo en
Montevideo, cubriendo la parte central el SUM.
Las losas (macizas y de 15 cm de espesor) y las vigas transversales descargan sobre la
costilla según el esquema que se indica.
Diagramas de solicitaciones en todos los tramos, y de tracciones provocadas por el
flector. Determinar reacciones de apoyo.
Estudio de secciones comprometidas, y ajuste de forma en caso de ser necesario

<!-- p. 80 -->

79

\10) Edificio para alojamiento de los animales en el predio de una exposición- feria
ganadera. Zona boxes.

ancho costilla 25 cm

Se indica una de las costillas que, en H.A. y
ubicadas a distancias iguales, definen el
volumen y soportan el techo formado por
tirantería de madera y cubierta de chapa
acanalada de aluminio.
La descarga de este techo sobre cada
costilla es de 600 daN/ml. Según la dirección de
cada parte.
Diagrama de solicitaciones, y de tracciones
provocadas por el flector. Descargas y
reacciones en los apoyos. Estudio de secciones planta
de interés (crítica) y propuesta de ajuste en caso
de ser necesario.

\11) Pabellón de una exposición indicado en corte transversal.

pie derecho en
perfil metálico que
sostiene además
la vidriera.

continúa a patín de cimentación

vidriera de fachada ancho de costilla 25 cms. ESC. 1/100

<!-- p. 81 -->

80

Se muestra una de las costillas que, ubicadas cada 5 mts. Soporta la lámina de techo
construida en losa “Doublex” cuyos moldes llegan hasta la costilla.
El techo descarga en total, 2.000 daN/ml.
Diagrama de solicitaciones, y de tracciones provocadas por el flector.
Descargas y reacciones en los apoyos.
Estudio de secciones de interés (críticas) y propuesta de ajuste, en caso de ser
necesario.

\12) Examen, parte escrita , del 16/12/75.

D

C F E

A Ancho 25 cms. ESC. 1/100. B

Una seria de costillas de hormigón armado con la forma indicada en el corte adjunto,
soportan un techo formado por una losa maciza de 10 cm de espesor, definiendo el conjunto un
galpón para depósito.
El techo descarga 1.800 daN/ml. inclinado de tramo en la costilla.
Diagramas de solicitaciones en todos los tramos, y diagrama de tracciones provocadas
por el flector.
Determinar descargas y reacciones en los apoyos A y B.
Verificar secciones críticas y propuesta de ajuste si se cree conveniente.

\13) Estructura continua de hormigón armado que sostiene techo y entrepiso.

Descarga del techo: 3.000 daN/m en F-G-H.
Descarga del entrepiso. 5.000 daN/m en C-D-E.
Diagramas de solicitaciones (flector, axíl y cortante) en todos los tramos y diagrama de
tracciones provocadas por el flector.
Descargas y reacciones en los apoyos.
Verificación de secciones críticas y propuesta de ajuste si se entiende necesario.

<!-- p. 82 -->

81

G
F H

C E
D

A Ancho 25 cms. ESC.1/100. B

\14) Tramo de escalera para salvar un desnivel en una galería comercial.

ESC. 1/50

<!-- p. 83 -->

82

Se construye totalmente en hormigón armado revestido de alfombra de polivinilo para
pavimento, y se encuentra independizada de los entrepisos por juntas de construcción.
Diagramas de solicitaciones. Descargas y reacciones en los apoyos. Estudio de
secciones de interés (críticas) y propuesta de ajuste, en caso de ser necesario.

\15) Preau, con vinculación bilateral con los espacios exteriores, en una escuela de
enseñanza primaria.

El techo descarga 500 daN/m. lineal de tramo.
Diagramas de solicitaciones y de tracciones provocadas por el flector. Descargas y
reacciones en los apoyos. Estudio de secciones de interés (críticas) y propuesta de ajuste, en
caso de ser necesario.

ESC. 1/100
Ancho de costilla 20 cms.

<!-- p. 84 -->

83

8 –TABLAS Y ABACOS

Las tablas se pueden descargar de la página web de Estabilidad 2, siguiendo el siguiente
camino:

Material de Apoyo

Tablas y otras herramientas a utilizar en el práctico

Tema / Método de Cross
