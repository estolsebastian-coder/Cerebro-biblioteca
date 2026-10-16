---
type: libro
title: "ESTABILIDAD DE LAS CONSTRUCCIONES III"
author: "xp"
categoria: "ESCRITORIO RALKAN"
paginas: 37
extraccion: "texto"
fuente: "local:E:/MATERIAL DE CONSULTA/ESCRITORIO RALKAN/escritorio trabajo/MATERIAL/Losas_2.pdf"
convertido: 2026-10-16
---

# ESTABILIDAD DE LAS CONSTRUCCIONES III

> Texto extraído de `ESCRITORIO RALKAN\escritorio trabajo\MATERIAL\Losas_2.pdf` (37 páginas, texto). El PDF original está en el disco E: (MATERIAL DE CONSULTA); `<!-- p. N -->` marca el inicio de cada página.

<!-- p. 1 -->

E S T A B I L I D A D D E L A S
C O N S T R U C C I O N E S III
L O S A S 2
LOSAS CONTINUAS

CUERPO DOCENTE DE ESTABILIDAD III - 2007

<!-- p. 2 -->

ESTABILIDAD DE LAS CONSTRUCCIONES III 2

CUERPO DOCENTE DE ESTABILIDAD DE LAS CONSTRUCCIONES III

Arq. JORGE SCHINCA
Arq. ORLANDO LASSUS
Arq. MARÍA E. FERNÁNDEZ
Arq. FERNANDO RISCHEWSKI
Arq. LAURA DOMINGO
Arq. ALEJANDRO NOCETTI
Arq. JOSÉ L. SOLARES
Arq. SANTIAGO MERLO

LOSAS

<!-- p. 3 -->

ESTABILIDAD DE LAS CONSTRUCCIONES III 3

LOSAS
LOSAS CONTINUAS

PROLOGO

Esta nueva presentación del tema revisa y amplía a la anterior versión del año 1990 y responde
a la forma en que el tema es tratado en la actualidad en el curso de Estabilidad de las
Construcciones III.

En esta segunda sección se aborda la consideración de los modelos correspondientes a los
casos de losas continuas y con su plano medio horizontal.

En la exposición del tema se recoge la experiencia del dictado del mismo en los últimos 10
años, en él ha participado, cubriendo distintos aspectos, la totalidad del cuerpo docente del
curso.

Abril de 2007

LOSAS

<!-- p. 4 -->

ESTABILIDAD DE LAS CONSTRUCCIONES III 4

LOSAS

<!-- p. 5 -->

ESTABILIDAD DE LAS CONSTRUCCIONES III 5

CAPÍTULO I
GENERALIDADES

La determinación de solicitaciones en estructuras hiperestáticas requiere definir un criterio base
que permita completar las ecuaciones de equilibrio.

En esta publicación se abordan dos formas de establecer ese criterio:

\1. En la primera se modeliza al hormigón armado como un material homogéneo, continuo
y elástico. A partir de este modelo del material es factible definir el área y la inercia de
la sección y consecuentemente determinar deformaciones y comparar rigideces entre
distintos tramos, para así establecer ecuaciones de compatibilidad de deformaciones
que permiten, junto con las condiciones de equilibrio hallar los valores de las
solicitaciones. Esta modelización es conocida como modelo lineal, clásico o elástico y
coincide con la que se hace en las estructuras de tramos con forma de barra.

\2. En la segunda se parte de definir una forma de organización de las armaduras que se
considera conveniente. Sobre esta base que permite establecer la capacidad resistente
de las secciones de apoyo se definen, respetando las leyes de la estática, los
momentos de apoyo y tramo en las diferentes losas. Esta modelización reconoce la
capacidad de adaptación de las estructuras hiperestáticas de hormigón armado a
distintas soluciones de armadura.

Aceptado el comportamiento del hormigón armado como material homogéneo, continuo y
elástico, se valida la proporcionalidad entre momentos flectores y curvatura que se acepta para
este tipo de material.

Sea AB un trozo de una barra de sección constante, de inercia I, flexada por un momento
flector M:

O

B"
A"
M M
A B

A' B'
C'
OA
a
paralela

LOSAS

<!-- p. 6 -->

ESTABILIDAD DE LAS CONSTRUCCIONES III 6

OA = OB = r
AB = r.Θ
ángulo C’BB’ = Θ

A’C’ = AB

C’B’ = alargamiento total de A’B’
C’B’ = BB’.Θ

C' B'
ε = al arg amiento unitario de A ' B' =
A ' C'

BB'⋅Θ
ε =
AB

BB '⋅Θ BB '
ε = =
r ⋅ Θ r

A partir de este valor de la deformación unitaria se puede determinar la tensión máxima:

BB'
σ = E ⋅ ε = E
r

Paralelamente aplicando la ley de Navier se tiene para la tensión máxima el valor:

M
σ = BB'
I

Igualando los dos valores de σ resulta:

BB' M
E = BB'
r I

E M
\=
r I

1 M
\=
r E ⋅ I

Por definición la curvatura ρ de una curva es la magnitud inversa al radio de la misma, por lo
tanto se puede escribir:

M
ρ =
E ⋅ I

La hipótesis de que el material es elástico supone la constancia de E, las hipótesis de material
homogéneo y continuo permiten hallar I que será una constante si se mantiene la geometría de
la sección. En consecuencia queda reconocida la proporcionalidad entre M y ρ.

A partir de esta proporcionalidad se construyen los métodos de resolución de solicitaciones de
estructuras hiperestáticas construidas en materiales homogéneos, continuos y elásticos que se
conocen como métodos lineales o clásicos.1

1
En el curso de Estabilidad II se vieron métodos de resolución matricial y el método de Cross.
LOSAS

<!-- p. 7 -->

ESTABILIDAD DE LAS CONSTRUCCIONES III 7

Dentro de este modelo, en el capítulo II se expondrá una extensión del Método de Cross a
estructuras en base a placas2.

Sin embargo el hormigón armado no es un material homogéneo ya que es suma de hormigón y
acero, no es elástico puesto que el hormigón no lo es y tampoco es continuo ya que el
hormigón traccionado se fisura. En consecuencia es discutible la aplicación de un modelo lineal
para la resolución de las solicitaciones en estructuras hiperestáticas construidas en hormigón
armado.

En base a estas observaciones se desarrolla en el capítulo III un método que se basa en
criterios que se apartan de los que integran el modelo lineal pero que sin embargo lo incluyen
como una de sus posibles soluciones.

2
Alguna de la simplificaciones que se admiten en la aplicación de este método tienen de alguna forma vínculos con el
otro método.
LOSAS

<!-- p. 8 -->

ESTABILIDAD DE LAS CONSTRUCCIONES III 8

LOSAS

<!-- p. 9 -->

ESTABILIDAD DE LAS CONSTRUCCIONES III 9

CAPÍTULO II
MÉTODOS LINEALES DE RESOLUCIÓN DE SOLICITACIONES EN LOSAS
CONTINUAS

En este capítulo se expone la determinación de solicitaciones en casos de losas continuas, en
base a considerar que el material que forma las placas es homogéneo, continuo y elástico.

Si se trata de un conjunto de losas continuas sobre apoyos paralelos, el estudio de las
solicitaciones y el posterior dimensionado se resuelve a través del estudio de fajas
representativas de ancho unitario, es decir del estudio de una estructura compuesta por barras.
Son aplicables en estos casos todos los métodos conocidos para estructuras formadas por
barras3.

Si se trata de un conjunto de losas rectangulares apoyadas en todo su perímetro se utiliza un
método que aplica el mismo esquema de trabajo que el Método de Cross para estructuras de
barras4:

\- Una situación inicial ficticia de la estructura en la cual no se permite el giro de los
apoyos. (apoyos frenados)
\- La determinación de momentos de apoyo y tramo en esa situación ficticia. (momentos
freno en los apoyos y los correspondientes momentos de tramo)
\- La determinación de rigideces de los distintos tramos de la estructura y su comparación.
(coeficientes de repartición)
\- Determinación de las consecuencias que se producen en el resto de la estructura al
liberar el freno en un apoyo. (repartición y transmisión)

La determinación de los momentos de apoyo y tramo para los casos de carga uniforme y carga
hidráulica, se puede realizar a través de las tablas incluidas en la publicación del IC “Tablas y
ábacos para el proyecto de estructuras”5.

La rigidez de cada placa está definida por el valor:

E ⋅ h 3
χ = α
L

E: módulo de deformación longitudinal de hormigón
h: altura real de la placa
L: lado de la placa perpendicular a donde se está midiendo la rigidez
α: coeficiente dependiente del tipo de apoyos6

Los coeficientes de repartición de la diferencia de momentos a un lado y otro del apoyo se
hallan igual que en el Método de Cross para barras como:

χ i χ d ri = r d = ri + r d = 1
χ i + χ d χ i + χ d

3
Métodos matriciales o el Método de Cross. Para consulta sobre los mismos ver la bibliografía del curso de Estabilidad
de las Construcciones II.
4
Hace unos años se modelizaban también estos casos como fajas en dos sentidos y se aplicaban los métodos de
correspondientes a estructuras de barras. Hoy se ha descartado esta solución por considerársela un modelo muy
alejado del comportamiento real de las losas apoyadas en todo el perímetro.
5
Facultad de Arquitectura, Universidad de la República, Montevideo Uruguay, 1995.
6
En la publicación citada antes se incluyen tablas para su determinación.
LOSAS

<!-- p. 10 -->

ESTABILIDAD DE LAS CONSTRUCCIONES III 10

En las placas al liberar un apoyo de la situación ficticia de empotramiento perfecto se deben
considerar transmisiones de momentos hacia los otros tres apoyos y hacia el centro del tramo
en las dos direcciones. También en “Tablas y ábacos para el proyecto de estructuras” se
encuentras los correspondientes coeficientes a la transmisión según distintos tipos de apoyo.

En el libro de J. Hahn “Vigas continuas, pórticos y placas”7, páginas 201 a 203, se señalan dos
simplificaciones importantes en la aplicación de este método:

\- Con respecto a la rigidez, se dice que para placas de espesor constante y cuyas
dimensiones no difieran mucho entre sí se puede suponer que son muy parecidas y por
lo tanto asumir coeficientes de repartición de valor 0,5 para ambas.8
\- Con respecto a la transmisión, se establece que en las placas con momentos flectores
en dos direcciones perpendiculares la transmisión hacia los otros apoyos presenta
valores que son muy pequeños y que por lo tanto es suficiente realizar una única
repartición en cada apoyo transmitiendo solamente hacia el centro de tramo.

Estas dos simplificaciones permiten un trabajo muy rápido y es importante señalar que más allá
de pretender lograr una mayor aproximación en el valor del momento del apoyo lo que se
busca es obtener un conjunto de valores de los momentos de apoyo y tramo que son
coherentes dentro de cada losa.

Ejemplo 1.
Conjunto de seis losas iguales.
Carga total por metro cuadrado: 800daN
Hormigón C20
Acero ADN500

3.00 3.00 3.00

2.80
1 2 3

2.80
4 5 6

Para la determinación de solicitaciones se usarán las tablas 4.1.2, 4.1.4 y 4.2.2 de Tablas y
ábacos para el proyecto de estructuras, edición 1995.

Primera etapa: determinación de los momentos de tramo y apoyo en la situación ficticia de
apoyos frenados.

7
Gustavo Gili, Barcelona, 1972.
8
Si la relación de las luces en el sentido perpendicular al apoyo donde se está determinando la rigidez es de 1 a 2 los
coeficientes serían 0,47 y 053.
LOSAS

<!-- p. 11 -->

ESTABILIDAD DE LAS CONSTRUCCIONES III 11

Ly Lx Ly/Lx p pLyLx c1 mx my m1 m2 m3 m4 Mx My M1 M2 M3 M4

1 2,80 3,00 0,93 800 6720 1,151 40,59 34.69 15,00 17,31 - - 191 223 488 388 0 0

2 2,80 3,00 0,93 800 6720 1 46,37 45,32 21,35 18,72 - 18,72 145 148 315 359 0 359

3 2,80 3,00 0,93 800 6720 1,151 40,59 34.69 15,00 17,31 - - 191 223 488 388 0 0

4 2,80 3,00 0,93 800 6720 1,151 40,59 34.69 15,00 17,31 - - 191 223 488 388 0 0

5 2,80 3,00 0,93 800 6720 1 46,37 45,32 21,35 18,72 - 18,72 145 148 315 359 0 359

6 2,80 3,00 0,93 800 6720 1,151 40,59 34.69 15,00 17,31 - - 191 223 488 388 0 0

Los valores de c1 tomados de la tabla 4.1.4 son de aplicación para el caso de las losas de
esquina, es decir que poseen un vértice al cual concurren dos bordes libres. En estos casos no
existe armadura en la cara superior de un ángulo por lo cual se deben aumentar los momentos
de tramo. A los efectos de dar coherencia al cuadro de valores se adjudica el valor 1 en el resto
de las losas.

Resulta conveniente visualizar los resultados en una planta:

0 0 0

223 148 223
0 191 388 359 145 359 388 191 0

448 1 315 2 448 3

448 315 448

223 148 223
0 191 388 359 145 359 388 191 0

0 4 0 5 0 6

Solamente en los apoyos 1-2, 2-3, 4-5 y 5-6 los momentos son distintos a un lado y otro del
mismo. Corresponde realizar la repartición de la diferencia, 29 daN.m.

Admitiendo la simplificación de que todas las losas tienen la misma rigidez la repartición
significa aumentar un momento 14,5 daN.m y disminuir el otro en la misma cantidad.

388-14,5 = 373,5
359+14,5 = 373,5

Resulta suficiente aproximación redondear el momento de apoyo a 374 daN.m.

Con respecto a la siguiente etapa del proceso de determinación de solicitaciones, la
transmisión de los momentos hacia el centro de las losas, es conveniente hacer las siguientes
precisiones:

\- Los coeficientes de la tabla 4.2.2 tienen signo positivo o negativo.
\- La adjudicación de ese signo es coherente con adjudicar signo positivo a los momentos
de tramo y signo negativo a los momentos de apoyo.
\- Cuando en la repartición un momento disminuye se asume que esa disminución es un
valor positivo.
LOSAS

<!-- p. 12 -->

ESTABILIDAD DE LAS CONSTRUCCIONES III 12

\- Cuando en la repartición un momento aumenta se asume que ese aumento es un valor
negativo.
\- Los momentos de tramo que se producen en la situación de tener los apoyos impedidos
de girar son los mínimos que se admiten.
\- Como consecuencia solamente se habilitan las transmisiones cuando significan un
aumento del momento de tramo:
 sólo se transmiten valores positivos cuando el
coeficiente es positivo
 sólo se transmiten valores negativos cuando el
coeficiente es negativo.

En la losa 1 y sus iguales 3, 4, y 6 el momento de apoyo disminuye, por lo tanto el valor a
transmitir es +14,5 y los coeficientes son bx=-0,0065 y by=+0,117, se transmite por lo tanto en la
dirección y:

14,5 x 0,117 = +1,7 daN.m

valor que se aproxima a 2.

En la losa 2 y su simétrica, la 5, el momento de apoyo aumenta, por lo tanto el valor a transmitir
es -14,5 daN.m y los coeficientes son bx=-0,0055 y by=+0,1095, se transmite por lo tanto en la
dirección x:

14,5 x 0,0055 = +0,08 daN.m

valor absolutamente despreciable.

Resultan así los siguientes valores finales para los momentos:

0 0 0

225 148 225
0 191 374 374 145 374 374 191 0

448 1 315 2 448 3

448 315 448

225 148 225
0 191 374 374 145 374 374 191 0

0 4 0 5 0 6

Con estos valores se procederá al dimensionado:

\- Como altura de la losa se tomarán 10cm, valor que claramente supera a 1/50 de la luz
menor de las losas.
\- Las alturas útiles son 8 y 7 cm.
\- En función del tipo de acero elegido la cuantía mínima es 0,15.d, las áreas mínimas de
acero son 1,2 cm2 y 1,05 cm2.

LOSAS

<!-- p. 13 -->

ESTABILIDAD DE LAS CONSTRUCCIONES III 13

Previamente a encarar el dimensionado es conveniente establecer el criterio de organización
de armaduras. Este criterio es dependiente del método que se haya usado para la
determinación de solicitaciones, dentro de los métodos lineales se recomienda que la
organización de armaduras responda a los siguientes criterios:

\- La malla inferior se organiza con barras rectas hacia los apoyos internos y doblando
una cada tres al quinto de la luz menor de la losa hacia los apoyos externos.
\- La armadura en la cara superior en los apoyos se organiza con barras rectas que
penetran en cada losa un cuarto de la luz menor de la losa.

Dimensionado en los centros de tramo:

LOSA MOMENTOS Md=1,6M d Md/d2 w As (nec) Asmin ORGANIZACIÓN As (real)
x 19.100 30.560 7 624 0,18 1,05 1,05 Φ6c/20 1,41
1
y 22.500 36.000 8 563 0,16 1,07 1,2 Φ6c/20 1,41
x 14.500 23.200 7 473 0,14 0,82 1,05 Φ6c/20 1,41
2
y 14.800 23.680 8 370 0,105 0,70 1,2 Φ6c/20 1,41
x 19.100 30.560 7 624 0,18 1,05 1,05 Φ6c/20 1,41
3
y 22.500 36.000 8 563 0,16 1,07 1,2 Φ6c/20 1,41
x 19.100 30.560 7 624 0,18 1,05 1,05 Φ6c/20 1,41
4
y 22.500 36.000 8 563 0,16 1,07 1,2 Φ6c/20 1,41
x 14.500 23.200 7 473 0,14 0,82 1,05 Φ6c/20 1,41
5
y 14.800 23.680 8 370 0,11 0,73 1,2 Φ6c/20 1,41
x 19.100 30.560 7 624 0,18 1,05 1,05 Φ6c/20 1,41
6
y 22.500 36.000 8 563 0,16 1,07 1,2 Φ6c/20 1,41

Dimensionado en los apoyos:

APOYO MOMENTOS Md=1,6M d Md/d2 w As (nec) Asmin ORGANIZACIÓN As (real)
1-2 37.400 59.840 8 935 0,28 1,88 1,2 Φ6c/15 1,88
2-3 37.400 59.840 8 935 0,28 1,88 1,2 Φ6c/15 1,88
4-5 37.400 59.840 8 935 0,28 1,88 1,2 Φ6c/15 1,88
5-6 37.400 59.840 8 935 0,28 1,88 1,2 Φ6c/15 1,88
1-4 44.800 71.680 8 1.120 0,33 2,21 1,2 Φ6c/12 2,35
2-5 31.500 50.400 8 788 0,23 1,54 1,2 Φ6c/18 1,57
3-6 44.800 71.680 8 1.120 0,33 2,21 1,2 Φ6c/12 2,35

3.00 3.00 3.00

55 70 70 55 70 70 55
55 FØ6c/15 FØ6c/15 55
Ø6
Ø6 Ø6
Ø6
10 20 10 20 2.80 Ø6 10 20 Ø6
1 20 2 3 20 20

70 70 FØ6c/12 70 FØ6c/18 FØ6c/12

70 70 70 70
70 70 70
55 FØ6c/15 FØ6c/15
Ø6 Ø6
Ø6 Ø6
10 20 2.80 Ø6 Ø6 10 20 10 20
20 6 55 20 5
20 4

55 55 55

LOSAS

<!-- p. 14 -->

ESTABILIDAD DE LAS CONSTRUCCIONES III 14

Ejemplo 2.
El mismo conjunto de losas que el ejemplo anterior, al que se le han agregado hacia la
izquierda de las losas 1 y 4 una losa en ménsula que vuela 1 m.

1.00 3.00 3.00 3.00

2.80
1 2 3

2.80
4 5 6

Este ejemplo permite establecer los criterios que se deben manejar en las continuidades de las
ménsulas.

Para iniciar la primera etapa del método, ee aplicará el principio de superposición dividiendo el
problema en dos:

\- Primero se determinan los momentos de apoyo y tramo del conjunto de losas sin la
ménsula, frenando todos los apoyos y tal como si la ménsula no existiese, se repiten los
valores del ejemplo anterior.

0 0 0

223 148 223
0 191 388 359 145 359 388 191 0

448 1 315 2 448 3

448 315 448

223 148 223
0 191 388 359 145 359 388 191 0

0 4 0 5 0 6

LOSAS

<!-- p. 15 -->

ESTABILIDAD DE LAS CONSTRUCCIONES III 15

\- Luego se considera solamente actuando la carga sobre la ménsula, estando frenados
todos los apoyos incluso el de la ménsula.

\- El momento de la ménsula en su apoyo se determina con independencia de la
continuidad, aplicando las leyes de la estática. Si la carga es solamente la uniforme de
800daN/m2 ese valor es:

800 ⋅ 12
M m = = 400 daN.m
2

400

1 2 3

400

4 5 6

\- La siguiente etapa es quitar los frenos de los apoyos. En una primera situación
solamente se libera el apoyo de la ménsula y se transmite el momento diferencia al
centro del tramo y como excepción también a los otros apoyos, este valor debe
considerarse negativo. De acuerdo con H. Chamlian9 se debe corregir, solamente a los
efectos de estas transmisiones, el momento de la ménsula multiplicándolo por el factor
1,273:

400 x 1,273 = 509

bx by b1 b2
coeficientes
\-0,0055 0,1095 -0,2805 -0,067

Mx My M1 M2
momentos
3 -54 143 34

\- Se debe recordar la regla de signos que se estableció en el ejemplo anterior: momentos
de tramo positivos y momentos de apoyo negativos por lo que los momentos luego de la
transmisión son:

9
Losas. Estabilidad II – F. de Arq. Universidad de la República. Montevideo, Olceda 1990
LOSAS

<!-- p. 16 -->

ESTABILIDAD DE LAS CONSTRUCCIONES III 16

0 0 0

169 148 223
400 400 194 354 359 145 359 388 191 0

305 1 315 2 448 3

305 315 448

169 148 223
400 400 194 354 359 145 359 388 191 0

0 4 0 5 0 6

\- Ahora se está en condiciones de iniciar el proceso en el conjunto de las losas.
\- La diferencia en los apoyos de las losas 1-2 y 4-5 es mínima por lo cual se promedian
los momentos en el apoyo pero no se transmite al tramo.
\- La diferencia en los apoyos 2-3 y 5-6 coincide con la estudiada en el ejemplo 1 por lo
que se toman los valores hallados en dicha oportunidad.

Los siguientes son los valores finales para los momentos de tramo y apoyo con los que se está
habilitado para realizar el dimensionado10:

0 0 0

169 148 225
400 400 194 357 357 145 374 374 191 0

305 1 315 2 448 3

305 315 448

169 148 225
400 400 194 357 357 145 374 374 191 0

0 4 0 5 0 6

10
En esta exposición no se realiza el dimensionado, el estudiante está capacitado para realizar la tarea siguiendo el
ejemplo 1.
LOSAS

<!-- p. 17 -->

ESTABILIDAD DE LAS CONSTRUCCIONES III 17

Descargas sobre los apoyos.

De acuerdo con UNIT 1050 en su artículo 51.2.5.2.2, las descargas sobre los apoyos se
determinan según la geometría de la figura 79. En Tablas y ábacos para el proyecto de
estructuras del IC se encuentran coeficientes que permiten determinar las áreas de descarga
sobre cada apoyo11.

Las reacciones transmitidas a los apoyos por las losas cargadas uniformemente y
armadas en dos direcciones se deben calcular de acuerdo a las áreas dadas por
la subdivisión de la planta en trapecios y triángulos según la figura 80.

bordes apoyados

45°

60°

60° 45°

bordes empotrados

Figura 80

Cuando en una esquina se unen dos bordes de losa con el mismo tipo de apoyo,
el ángulo de repartición debe ser de 45° . Si la unión corresponde a un borde
totalmente empotrado con uno libremente apoyado, el ángulo de repartición del
lado del empotramiento debe ser de 60°.

Se debe tener presente que los valores que se obtienen son el total de carga sobre el apoyo.
En general se admite que se distribuya uniformemente ese total de carga en la longitud del
apoyo.

Cuando existen ménsulas, la descarga de la ménsula se realiza sobre su único apoyo y para
decidir la situación de la losa interna se debe comparar el momento de la ménsula multiplicado
por 1,273 con los momentos en los apoyos internos. Si 1,273 Mm es menor que la mitad del
momento en el apoyo interno se considerará que el borde con ménsula es un borde sin
continuidad, en los otros casos se considerará que existe continuidad.

Observación y crítica.

El hormigón armado no es un material elástico puesto que el hormigón no lo es, no es
homogéneo ya que es suma de hormigón y acero y tampoco es continuo ya que el hormigón
traccionado se fisura. En consecuencia:

\- No existe un valor constante para E. En el hormigón no se habla de módulo de
elasticidad sino de módulo de deformación longitudinal que es el valor que liga
tensiones con deformaciones y que es variable para cada valor de la deformación.

11
Tabla 4.1.6
LOSAS

<!-- p. 18 -->

ESTABILIDAD DE LAS CONSTRUCCIONES III 18

\- En el hormigón armado es incierta la determinación e la inercia, se trabaja con valores
convencionales de dudosa representatividad12.

Estas observaciones hacen que no sea sostenible la proporcionalidad momento flector –
curvatura, por lo que un modelo lineal para la resolución de las solicitaciones en estructuras
hiperestáticas construidas en hormigón armado no es un modelo que interprete el fenómeno en
forma absoluta.

En el estado actual del conocimiento conviven en el análisis estructural los métodos de
modelización lineal del comportamiento de las estructuras de hormigón armado con métodos
no lineales aunque en general estos últimos son aceptados por las normas solamente en el
estudio de las losas continuas.

12
La no homogeneidad hace que, al proceder a la integración de los productos de los diferenciales área por sus
distancias al eje al cuadrado, los diferenciales de área pertenecientes a la zona de hormigón posean distinta cualidad
que los diferenciales de área pertenecientes a las zonas de acero, por lo que en forma arbitraria se debe establecer
una relación de valor entre ellos. La fisuración hace que no todas las secciones de una barra sean iguales, habrá
secciones que serán plenas y habrá secciones que sean parciales con una variación no previsible.
LOSAS

<!-- p. 19 -->

ESTABILIDAD DE LAS CONSTRUCCIONES III 19

CAPÍTULO III
MÉTODO NO LINEAL DE RESOLUCIÓN DE SOLICITACIONES EN LOSAS
CONTINUAS

En este capítulo se desarrollará un método no lineal para la determinación de solicitaciones en
losas rectangulares continuas apoyadas en todo su perímetro.

El modelo no lineal que se desarrollará en este texto parte de observar la capacidad de
adaptación de las estructuras hiperestáticas de hormigón armado a distintas soluciones de
armadura.

Sea un conjunto de seis losas continuas armadas de acuerdo con los resultados de su estudio
según el método lineal, las deformaciones resultan según el esquema, las continuidades son
función de la rigidez relativa de las losas:

Debido a que las estructuras hiperestáticas cumplen condiciones de apoyo que son
superabundantes para garantizar el equilibrio, es factible resolver el proyecto de estructura sin
colocar armaduras sobre los apoyos. En ese caso se producen fisuras localizadas sobre las
líneas de apoyo que separan entre sí a las losas y que funcionan como juntas de trabajo. Cada
losa pasa a comportarse como simplemente apoyada y si en el centro del tramo existe la
armadura suficiente para resistir los momentos correspondientes a la situación de simple
apoyo, sigue siendo una estructura estable, cada losa es capaz de lograr su equilibrio con
independencia de las demás.

La estructura resultante, si bien es estable, puede no cumplir condiciones de servicio ya que
esa fisura única sobre la línea de apoyo puede convertirse en un defecto constructivo13 que
afecte las terminaciones y que incluso comprometa la durabilidad de la estructura.

13
Debe distinguirse esta situación de la microfisuración inherente al hormigón armado flexado.
LOSAS

<!-- p. 20 -->

ESTABILIDAD DE LAS CONSTRUCCIONES III 20

Se corrige esta observación colocando una cierta cantidad de armadura sobre los apoyos que
permita moderar la fisuración, para que deje de ser una única fisura localizada y se transforme
en una microfisuración.

Se genera de esa forma sobre los apoyos lo que se denomina una articulación plástica es
decir, que se sustituye una articulación ideal que permite el libre giro de las losas entre sí, con
momento cero, por una articulación plástica capaz de moderar el giro y que resiste un valor de
momento distinto de cero.

En la figura se representa un apoyo sin armadura superior y el libre giro de las losas sobre el
mismo que se deforman con tangentes t1 y t2 sobre el apoyo:

t2
t1

Si existe una cierta cantidad de armadura, la deformación sobre el apoyo se hace común a las
dos losas, con concavidad negativa. Las pendientes de las tangentes t1’ y t2’ son menores a
las de t1 y t2 de la figura anterior.

t2'
t1'

La cantidad de armadura que se resuelve colocar en los apoyos es arbitraria, siempre se
obtienen soluciones estables. Para una altura de losa dada, cada valor posible de área de
acero significa un valor distinto del momento capaz de la articulación plástica y una distinta
deformación con distinta posibilidad de giro de las losas.

La relación momento curvatura en esa zona no es lineal. Se considera dentro del modelo la
existencia de la fisuración del hormigón y que por lo tanto no hay inercia constante. Se admite
un comportamiento no proporcional, plástico.

La colocación de armadura sobre los apoyos permite superar la observación realizada sobre la
posible no verificación de las condiciones de servicio. Se verifican ahora no solamente las
condiciones de equilibrio sino que también lo hacen las de servicio, salvo en los casos en los
que de debe verificar el estado límite de fisuración controlada.

LOSAS

<!-- p. 21 -->

ESTABILIDAD DE LAS CONSTRUCCIONES III 21

La conveniencia de que exista armadura sobre los apoyos ha traído como consecuencia la
aparición de momentos no nulos sobre los mismos y la posibilidad de disminuir los momentos
de tramo.

Dado que los valores posibles del momento sobre el apoyo son infinitos, dependen solamente
de los infinitos valores posibles del área de acero que se coloque, el número de soluciones
para las solicitaciones es también infinito14.

Existe por lo tanto la capacidad de definir las solicitaciones que resulten congruentes con un
criterio de armado preferido.

Desde el punto de vista constructivo en las soluciones de losas rectangulares apoyadas en
todo su perímetro utilizadas en obras con controles medios se prefiere trabajar con armaduras
de poca área sobre los apoyos.

Esta preferencia deriva del hecho de la dificultad de lograr una ejecución confiable de las
armaduras que se colocan en la cara superior de las losas ya que van a sufrir acciones en la
etapa de ejecución que tienden a moverlas de la posición proyectada.

Un criterio de armado que se considera muy conveniente es lograr la armadura sobre el apoyo
mediante el doblado de una barra cada tres de las que forman la malla en el centro de los
tramos de las losas apoyadas en él.

En congruencia se obtendrán valores bajos del momento sobre los apoyos y valores mayores
en los centros de las losas

Un método para determinar solicitaciones en losas rectangulares continuas apoyadas sobre su
perímetro que es coherente con este tipo de armado es el que está contenido en la norma
francesa de hormigón armado B.A.E.L.15 en su versión del año 1983.

Método derivado de la Norma B.A.E.L. 83

En el apartado B.6.2.21 de esta norma se dan las bases del método a aplicar en entrepisos
sobre los que actúan sobrecargas moderadas.16

Este método resultará aplicable cuando, según apartado B.6.2.210 de dicha norma:

\- Se trata de construcciones en las cuales la carga de uso es a lo sumo igual a dos veces
la carga permanente y no supera los 500 daN/m2.
\- Todos las losas continuas poseen a priori la misma altura.
\- No es necesario verificar el estado límite de fisuración controlada.
\- Las luces sucesivas están en una relación comprendida entre 0,8 y 1,25.

La primera condición es satisfecha por la mayor parte de las construcciones. En los sistemas
constructivos corrientes con estructuras de hormigón armado, las cargas permanentes nunca
son la mitad de las eventuales y de acuerdo con UNIT 33-91 solamente se superan los 500
daN/m2 en algunos depósitos y garajes.

La segunda condición es regla corriente en el proyecto de estructura dado que disponer alturas
distintas para las losas crearía una dificultad constructiva no conveniente.

14
Dentro de las infinitas soluciones posibles para las solicitaciones estará la que coincida en valores con la solución
lineal.
15 B.A.E.L.: Béton Armé suivant la méthode des États Limites (Hormigón armado por estados límites). Editorial
Eyrolles, París 1985
16
Se dice “Méthode Forfaitaire”, literalmente Método destajista haciendo referencia la determinación previa de la
proporción entre los momentos.
LOSAS

<!-- p. 22 -->

ESTABILIDAD DE LAS CONSTRUCCIONES III 22

La tercera condición sí es restrictiva y el método no dará solución cuando se deba proyectar,
por ejemplo, un tanque de agua.

La cuarta condición obligará a formular criterios para generalizar el método cuando la misma no
se cumpla.

De cumplirse las condiciones el método se aplica siguiendo la definición que del mismo hace la
norma:

“El método consiste en evaluar los valores de los momentos de tramo y de apoyo como
porcentajes fijados previamente del valor del momento flector M0 del “tramo de referencia”, es
decir de un tramo independiente de la misma luz que el tramo considerado y sometido a las
mismas cargas. Dichos porcentajes prefijados deben surgir de la experiencia”.17

Los valores de partida serán los de los momentos en el tramo considerando cada losa como
simplemente apoyada. En particular el mayor de los dos que se transforma en valor de
referencia para fijar los momentos sobre los apoyos.

Multiplicando ese valor de referencia por los porcentajes prefijados se obtienen los valores de
los momentos de apoyo.

Esos porcentajes deben ser coherentes con la organización de armaduras que se desea
obtener. Los que recomienda la norma y que son refrendados por la experiencia en nuestro
medio son:

\- 0% para los apoyos externos. (coeficiente 0)
\- 50% ó 35% en los apoyos internos. (coeficiente 0,5 ó 0,35)

Con respecto a los momentos en el tramo se deben cumplir las leyes de la estática por lo cual
en una determinada dirección se deberá cumplir que la semisuma de los momentos de apoyo
más el momento de tramo sea igual al momento en esa dirección cuando la losa está
simplemente apoyada.

M izquierdoapoyo + M apoyoderecho
\+ M tramo = M o
2

Como los apoyos se comportan como rótulas plásticas y parte de la carga sobre la losa va a
ser una acción eventual, las aplicaciones sucesivas de la misma pueden llegar a aumentar la
curvatura en el apoyo al sumarse deformaciones residuales. Como consecuencia de que
aumenta el giro de los apoyos van a aumentar los momentos de tramo por lo que se aconseja
que la igualdad planteada se realice no con Mo sino con un valor mayor: 1,25Mo.

M izquierdoapoyo + M apoyoderecho
\+ M tramo = ,125 M o
2

En esta igualdad se puede poner en evidencia que los tres momentos a determinar son función
de Mo (porcentajes fijados previamente), llamando coeficiente αi a esos respectivos porcentajes
resulta:

α izquierdoapoyo M o + α apoyoderecho M o
\+ α tramo M o = ,125 M o
2

α izquierdoapoyo + α apoyoderecho
\+ α tramo = ,125
2

17
Norma B.A.E.L., apartado B.6.2.211
LOSAS

<!-- p. 23 -->

ESTABILIDAD DE LAS CONSTRUCCIONES III 23

Definidos los coeficientes de apoyo se puede hallar el coeficiente de tramo que resulta
coherente con ellos según la expresión anterior que refleja las leyes de la estática.

El momento de tramo no será nunca mayor al que se corresponde con la situación de simple
apoyo por lo cual αt no será nunca mayor que 1.

A partir de la combinación de posibles condiciones de apoyo surgen cinco casos tipo de
combinaciones de coeficientes (el grisado indica apoyo con continuidad):

0 0 0 0 0,5

1 1 1 1 0,75
0 1 0,35 0 1 0,35 0,5 0,75 0,5 0,5 0,75 0,5 0,5 0,75 0,5

0 0,35 0 0,5 0,5

Ejemplo 1.
Conjunto de seis losas iguales.
Carga total por metro cuadrado: 800daN
Hormigón C20
Acero ADN500
3.00 3.00 3.00

2.80
1 2 3

2.80
4 5 6

Para la determinación de solicitaciones se usarán las tablas 4.1.2, y 4.1.4 de Tablas y ábacos
para el proyecto de estructuras.

Primera etapa: determinación de los momentos de tramo en la situación referencial de apoyos
sin continuidad.

Ly Lx Ly/Lx p pLyLx c1 mx my Mx My

1 2,80 3,00 0,93 800 6720 1,349 29,8 25,48 304 356

2 2,80 3,00 0,93 800 6720 1 29,8 25,48 226 264

3 2,80 3,00 0,93 800 6720 1,349 29,8 25,48 304 356

4 2,80 3,00 0,93 800 6720 1,349 29,8 25,48 304 356

5 2,80 3,00 0,93 800 6720 1 29,8 25,48 226 264

6 2,80 3,00 0,93 800 6720 1,349 29,8 25,48 304 356

LOSAS

<!-- p. 24 -->

ESTABILIDAD DE LAS CONSTRUCCIONES III 24

Los valores de c1 tomados de la tabla 4.1.4 son de aplicación para el caso de las losas de
esquina, es decir que poseen un vértice al cual concurren dos bordes libres. En estos casos no
existe armadura en la cara superior de un ángulo por lo cual se deben aumentar los momentos
de tramo. A los efectos de dar coherencia al cuadro de valores se adjudica el valor 1 en el resto
de las losas.

De la aplicación de los casos tipo de combinaciones de coeficientes surge:

0 0 0

1 1 1
0 1 0.35 0.5 0.75 0.5 0.35 1 0

0.35 1 0.5 2 0.35 3
0.35 0.5 0.35

0 1 0.35 0.5 0.75 0.5 0.35 1 0
1 1 1

0 4 0 5 0 6

A partir de los momentos de referencia obtenidos en la tabla anterior, multiplicándolos
ordenadamente por los coeficientes se obtienen los siguientes valores para los momentos de
apoyo y tramo:

0 0 0

0 304 125 132 170 132 125 304 0
356 264 356

125 1 132 2 125 3

125 132 125

356 264 356
0 304 125 132 170 132 125 304 0

0 4 0 5 0 6

Se debe señalar:

\- Los momentos de apoyo de una losa se determinan en función de un único momento: el
mayor de los dos que se producen en el tramo considerando a la losa simplemente
apoyada. Es decir que los momentos en todos los apoyos con continuidad de una
misma losa resultan iguales.
\- Los momentos en el tramo surgen de aplicar los correspondientes coeficientes a los
momentos que se producen en el tramo considerando a la losa simplemente apoyada.

LOSAS

<!-- p. 25 -->

ESTABILIDAD DE LAS CONSTRUCCIONES III 25

Se está en condiciones de pasar al dimensionado. En los apoyos en los que se producen
momentos distintos a un lado y otro se dimensiona con el valor mayor.

\- Como altura de la losa se tomarán 10cm, valor que claramente supera a 1/50 de la luz
menor de las losas.
\- Las alturas útiles son 8 y 7 cm.
\- En función del tipo de acero elegido la cuantía mínima es 0,15.d, las áreas mínimas de
acero son 1,2 cm2 y 1,05 cm2.

Previamente a encarar el dimensionado es conveniente establecer el criterio de organización
de armaduras. Este criterio es dependiente del método que se haya usado para la
determinación de solicitaciones, dentro del método no lineal que se está exponiendo se
recomienda que la organización de armaduras responda a los siguientes criterios:

\- La malla se organiza doblando una barra cada tres al quinto de la luz menor de la losa
hacia los apoyos externos e internos.
\- En los apoyos internos la barra doblada se prolonga hacia la otra losa un cuarto de la
luz menor de esa losa.

Dimensionado en los centros de tramo:

LOSA MOMENTOS Md = 1,6M d Md/d2 w As nec Asmin ORGANIZACIÓN As real

Mx 30.400 48.640 7 993 0,3 1,76 1,05 F6c/16 1,76
1
My 35.600 56.960 8 890 0,27 1,81 1,20 F6c/15 1,88

Mx 17.000 27.200 7 555 0,165 0,97 1,05 F6c/20 1,41
2
My 26.400 42.240 8 660 0,2 1,34 1,20 F6c/20 1,41

Mx 30.400 48.640 7 993 0,3 1,76 1,05 F6c/16 1,76
3
My 35.600 56.960 8 890 0,27 1,81 1,20 F6c/15 1,88

Mx 30.400 48.640 7 993 0,3 1,76 1,05 F6c/16 1,76
4
My 35.600 56.960 8 890 0,27 1,81 1,20 F6c/15 1,88

Mx 17.000 27.200 7 555 0,165 0,97 1,05 F6c/20 1,41
5
My 26.400 42.240 8 660 0,2 1,34 1,20 F6c/20 1,41

Mx 30.400 48.640 7 993 0,3 1,76 1,05 F6c/16 1,76
6
My 35.600 56.960 8 890 0,27 1,81 1,20 F6c/15 1,88

Dimensionado en los apoyos:

2 1/3 HIERROS
APOYO MOMENTO Md = 1,6M d Md/d w As nec Asmin As izq As der compl. suma F
1-2 13.200 21.120 8 330 _ _ 1,20 1,88 1,41 1,1 _ _

2-3 13.200 21.120 8 330 _ _ 1,20 1,41 1,88 1,1 _ _

4-5 13.200 21.120 8 330 _ _ 1,20 1,88 1,41 1,1 _ _

5-6 13.200 21.120 8 330 _ _ 1,20 1,41 1,88 1,1 _ _

4-1 12.500 20.000 8 313 _ _ 1,20 1,88 1,88 1,25 _ _

5-2 13.200 21.120 8 330 _ _ 1,20 1,41 1,41 0,94 0,26 F6c/50

6-3 12.500 20.000 8 313 _ _ 1,20 1,88 1,88 1,25 _ _

Sobre el dimensionado en los apoyos se aclara:

\- En las lecturas sobre el ábaco de dimensionado no se obtuvieron valores para w, esto
significa que corresponde dimensionar según la cuantía mínima.

LOSAS

<!-- p. 26 -->

ESTABILIDAD DE LAS CONSTRUCCIONES III 26

\- De acuerdo con el criterio de organización de armaduras establecido previamente se
contará en la cara superior del apoyo con un tercio de la armadura existente en el
tramo, se opera por lo tanto con los valores de la armadura de tramo a izquierda y a
derecha del apoyo, sumándolas y tomando luego un tercio de la suma.
\- Si ese tercio es suficiente se termina con el dimensionado, si no lo es se deberá colocar
como complemento el área de acero diferencia entre lo necesario y lo disponible. En el
ejemplo esto sucede en el apoyo 5-2, se necesitan 1,20cm2 y se dispone de 0,94cm2, la
diferencia 0,26cm2 se debe lograr colocando barras F. Esta diferencia se cubriría con
una barra de 6 mm de diámetro espaciada 1,08m, se recomienda que cuando se
colocan complementos lo mínimo sea una barra de 6mm espaciada 50cm.

Para proyectar las armaduras complementarias sobre los apoyos se procede por tanteo. Se
dispone como datos del valor del área a cubrir: Asdif, y de las áreas de las barras de acero
según su diámetro.
A s dif
\= n
A s Φ

de esta forma se obtiene la cantidad de barras de diámetro Φ que se deben colocar en un
ancho de un metro, por lo tanto:
100
\= s
n

es el valor en cm de la separación que debe existir entre las barras de diámetro Φ para tener
en un metro de ancho al área de acero Asdif.

3.00 3.00 3.00

55 55 55
55 55 70 70 55 55
Ø6
Ø6 Ø6
Ø6
Ø6 10 20 Ø6
10 16 10 16 2.80
20 2 55 70 15 1 70 55 15 3

70 70 70 70
55 55 55

55 55 55
70 70 70 70
70 55 55 55 55 70 FØ6c/50
Ø6
Ø6 Ø6
2.80 Ø6 Ø6 10 20 Ø6 10 16 10 16
20 5 55 70 15 6 15 4 70 55

55 55 55

LOSAS

<!-- p. 27 -->

ESTABILIDAD DE LAS CONSTRUCCIONES III 27

Ejemplo2.
Planta tipo de un bloque de viviendas
Carga total por metro cuadrado: 600daN - Carga total por metro cuadrado en losas
descendidas: 900daN
Hormigón C15
Acero ADM420

2.00 1.35 4.35

1.80 4 4

4.60
1 2 2 1

6.30
5 5
2.10
6
3.50 3 3

3.35 3.20 2.30

A través de la resolución de este ejemplo se planteará la generalización del método para
cualquier conformación de planta.

Las losas 2 no son continuas con el resto por estar en otro plano y las que forman la escalera
tampoco lo son porque el proceso de construcción hace que su ejecución se desfase en el
tiempo.

Se mantienen como exigencias absolutas para la aplicación del método las ya enunciadas:

\- Se trata de construcciones en las cuales la carga de uso es a lo sumo igual a dos veces
la carga permanente y no supera los 500 daN/m2.
\- Todos las losas continuas poseen a priori la misma altura.
\- No es necesario verificar el estado límite de fisuración controlada.

En este ejemplo, a diferencia de lo que caracterizaba al ejemplo 1, las losas no están definidas
por una cuadrícula regular:

\- no son siempre continuas en toda la longitud del lado,
\- en cortes, según x y según y, las luces de los distintos tramos son distintas,
\- la relación entre los lados de algunas de las losas no están en el entorno 0,5-2, por lo
que la determinación de sus solicitaciones se hará como si fuesen apoyadas en lados
paralelos.

LOSAS

<!-- p. 28 -->

ESTABILIDAD DE LAS CONSTRUCCIONES III 28

Todas estas diferencias deben ser analizadas a los efectos de valorar como afectan a la
continuidad de las losas.

a.- Cuando dos losas no son continuas en todo el lado en común. Por ejemplo: 3 con 1, 5 con 3
y 5 con 6. No existen dudas de la continuidad de las losas que tienen cubierto todo el lado en
común, pero si las existen con respecto a la losa que tiene solamente parte del lado común
continuo.

El criterio a aplicar es que si la continuidad afecta al 60% o más del lado se valida la
continuidad.

\- Losa 3 con losa 1: 2,00/3,35 = 0,597 (aprox. 60%) se considera continua, coeficiente
0,35.
\- Losa 5 con losa 3: 3,35/6,30 = 0,53 (53%) no se considera continua, coeficiente 0.
\- Losa 5 con losa 6: 2,10/6,30 = 0,33 (33%) no se considera continua, coeficiente 0.

b.- Cuando las luces sucesivas, en la dirección perpendicular al lado común, de dos losas
continuas no están en una relación comprendida entre 0,8 y 1,25.

Se aplica el criterio de que la losa de menor luz es continua con respecto a la de mayor luz
correspondiendo los valores de coeficiente que resulten del caso tipo.

Con respecto a la losa de mayor luz, si esta no duplica a la de la losa de menor luz se
considera un valor de continuidad expresada por el coeficiente 0,35, si duplica a la luz de la
menor se considera no continua, coeficiente 0.

\- Losa 3 y losa 1: 3,50/4,60 = 0,76, coeficientes según caso tipo para la losa 3 y 0,35
para la losa 1.
\- Losa 5 y losa 4: 6,30/1,80 = 3,50, coeficiente 0 para la losa 5 y según caso tipo para la
losa 4.
\- Losa 5 y losa 6: 3,20/2,30 = 1,39, coeficiente 0,35 para losa 5 y según caso tipo para la
losa 6.

c.- Cuando en una de las losas la relación entre sus lados no está en el entorno 0,5-2.
En estos casos se toma como criterio que la losa que se calculará como apoyada en lados
paralelos no se considerará continua y que la otra losa, si es continua en el lado largo de la
losa de dos apoyos se rige por el caso tipo que le corresponda y si es continua por el lado corto
de la losa de dos apoyos no se considera continua.

\- Losa 1: Ly/Lx = 4,60/2,00 = 2,3, por lo tanto del estudio de la continuidad entre la losa 3
y la losa 1 surge: no continuidad, coeficiente 0, para la losa 1 y no continuidad,
coeficiente 0 para la losa 3 porque es continua por el lado menor de la losa 1.
\- Losa 4: Ly/Lx = 1,80/4,35 = 0,41, por lo tanto del estudio de la continuidad entre la losa 5
y la losa 4 surge: caso tipo para la losa 5 y no continuidad, coeficiente 0, para la losa 4.

En la elección final de coeficientes, cuando un apoyo ha aparecido en más de un estudio
particular, se debe optar por el más restrictivo de la continuidad. Surgen así para este caso los
siguientes coeficientes:

\- Losa 1 con losa 3: coeficiente 0.
\- Losa 3 con losa 1: coeficiente 0.
\- Losa 4 con losa 5: coeficiente 0.
\- Losa 5 con losa 4: coeficiente 0.
\- Losa 5 con losa 3: coeficiente 0.
\- Losa 5 con losa 6: coeficiente 0.

LOSAS

<!-- p. 29 -->

ESTABILIDAD DE LAS CONSTRUCCIONES III 29

0 0 0 0 0 0

0 1 0 0 1 0

0 0

0 0
0 1 0 0 1 0 0 1 0 0 1 0

0 0 1 1 0 0
0 0 1 0 0 0 1 0 0

1
0,5 0,75 0,5
1 1
0 1 0,35 0 0,35 1 0

0 0 0 0

Generalizada de esta forma la aplicación del método para una conformación cualquiera de la
planta corresponde hallar los momentos de referencia:

Ly Lx Ly/Lx p pLyLx c1 mx my Mx My

1 4,60 2,00 2,30 600 - - - - 300 0

2 4,60 1,35 3,41 900 - - - - 205 0

3 3,50 3,35 1,04 600 7035 1,351 26,25 28,88 362 329

4 1,80 4,35 0,41 600 - - - - 0 243

5 6,30 3,20 1,97 600 12096 1,122 21,15 84,59 642 160

6 2,10 2.30 0,91 600 2898 1 30,68 24,85 94 117

Combinando estos valores con los coeficientes determinados con anterioridad surgen los
siguientes momentos para apoyos y tramos:

0 0 0 0 0 0

0 243 0 0 0 243 0 0

0 0

0 0
0 0 300
0 0 205 0 0 205 0 0 3000 0
0 0

0 0 0 0
0 0 642 0 0 0 642 0 0
160 160 59 71 59
117
0 362 127 0 127 362 0
329 329

0 0 0 0

LOSAS

<!-- p. 30 -->

ESTABILIDAD DE LAS CONSTRUCCIONES III 30

A los efectos de proceder al dimensionado se establece:
\- Como altura de la losa se tomarán 10cm, valor que claramente supera a 1/50 de la luz
menor de la losa 3 que es la que define el predimensionado.
\- Las alturas útiles son 8 y 7 cm.
\- En función del tipo de acero elegido la cuantía mínima es 0,25.d, las áreas mínimas de
acero son 2 cm2 y 1,75 cm2.

La organización de armaduras responderá a los criterios ya definidos en coherencia con el
método aplicado:
\- La malla se organiza doblando una barra cada tres al quinto de la luz menor de la losa
hacia los apoyos externos e internos.
\- En los apoyos internos la barra doblada se prolonga hacia la otra losa un cuarto de la
luz menor de esa losa.

Dimensionado en los centros de tramo:
LOSA MOMENTOS Md = 1,6M d Md/d2 w As nec Asmin ORGANIZACIÓN As real
Mx 30.000 48.000 8 750 0,22 1,76 2,00 F6c/14 2,02
1
My 0 0 7 - - 0,44 - F6c/20 1,41
Mx 20.500 32.800 8 512 0,15 1,2 2,00 F6c/14 2,02
2
My 0 0 7 - - 0,3 - F6c/20 1,41
Mx 36.200 57.900 8 905 0,27 2,16 2,00 F6c/13 2,17
3
My 32.900 52.600 7 1.073 0,32 2,24 1,75 F6c/12 2,35
Mx 0 0 7 - - 0,36 - F6c/20 1,41
4
My 24.300 38.900 8 609 0,18 1,44 2,00 F6c/14 2,02
Mx 64.200 102.700 8 1.605 0,5 4,00 2,00 F8c/12 4,19
5
My 16.000 25.600 7 522 0,16 1,12 1,75 F6c/16 1,76
Mx 7.050 11.300 7 231 - - 1,75 F6c/16 1,76
6
My 11.700 18.700 8 292 - - 2,00 F6c/14 2,02

Con respecto a los valores contenidos en este cuadro corresponde establecer:
\- En las losas 1, 2 y 4 se indica como área necesaria en el sentido de los momentos 0 a
la cuarta parte de la armadura necesaria en el sentido portante.
\- En la losa 6 no se leen valores para w, corresponde construirla con cuantías mínimas.
\- En la losa 3 se produce la contradicción de que, siendo las barras en las dos
direcciones de igual diámetro, las barras que van a menor distancia se deben colocar
arriba de las que están a mayor distancia. Se recomienda especificar el menor
espaciamiento en los dos sentidos.

Ø6 Ø6
Ø 6 Ø 6
10 20 10 20

14 4 14 4

Ø6 Ø6
Ø 6 Ø6 Ø6 Ø 6
10 14 Ø6 10 14 Ø6 10 14 10 14
20 1 20 2 20 2 20 1

Ø6 Ø6
Ø 8 Ø 8
10 12 Ø6 10 12
16 5 Ø 6 16 5
Ø6 10 16 Ø6
Ø 6 14 6 Ø 6
10 12 10 12
12 3 12 3

LOSAS

<!-- p. 31 -->

ESTABILIDAD DE LAS CONSTRUCCIONES III 31

El dimensionado en los apoyos se debe realizar solamente en los únicos con momento distinto
de 0, valen para este dimensionado las mismas consideraciones realizadas en el ejemplo1:

2 1/3 HIERROS
APOYO MOMENTO Md = 1,6M d Md/d w As nec Asmin As izq As der compl. suma F
3-5 12.700 20.320 8 318 _ _ 2,00 2,35 4,19 2,18 _ _

5-6 5.900 9.440 8 148 _ _ 2,00 4,19 1,76 1,97 _ _

La organización de armaduras mantiene el criterio general predeterminado:

\- La malla se organiza doblando una barra cada tres al quinto de la luz menor de la losa
hacia los apoyos externos e internos.
\- En los apoyos internos la barra doblada se prolonga hacia la otra losa un cuarto de la
luz menor de esa losa.

30 35 35 35 35 30
40 40
35 35 45

45 35 35

45 45
35 35 35 35

40 40 65 65 40 40
80 80

40 40 40 40

65 65 65 65

50 50
40 40 40 40

65 65 40 65 65
85 85

85 65 65 50 50 65 65 85

65 65 80 80 40 40 80 80 65 65

40

85 65 65 65 65 85

65 65 65 65 65 65

Corresponde señalar:

\- El criterio general de organización de la armadura en los apoyos internos se aplica en
todos ellos aún en los que en el proceso de cálculo se les adjudicó momento 0. Esta
determinación tiene que ver con asegurar las condiciones de servicio.

\- Las losas descendidas no son continuas ni en el proceso de cálculo ni en el diseño de
las armaduras.

\- En cada losa se indicaran tantos cortes de la armadura como sea necesario para la
comprensión de las distintas situaciones que se presentan.

LOSAS

<!-- p. 32 -->

ESTABILIDAD DE LAS CONSTRUCCIONES III 32

Recomendaciones para la aplicación de los valores de los coeficientes de apoyo.

0 0,35 0,5

APOYOS INTERNOS DE
LOSAS DE ESQUINA GENERAL APOYOS INTERNOS EN
APOYOS EXTERNOS
GENERAL

ÚNICO APOYO INTERNO CRITERIO

APOYO INTERNO DE
APOYOS INTERNOS EN
APOYO INTERNO LOSAS DE ESQUINA O
GENERAL CON CONTINUIDAD CONTINUO EN MENOS UNICO APOYO INTERNO
CONTINUIDAD ENTRE EL 60
DEL 60% DE SU CON CONTINUIDAD ENTRE
Y EL 100% DE SU CON PARCAIL LONGITUD EL 60 Y EL 100% DE SU LONGITUD
LONGITUD
APOYOS

DE APOYO INTERNO DE LA
LOSA DE MAYOR LUZ SI LA UNA DEL DE LUCES ESTÁ 1,25 RELACIÓN
\- COMPRENDIDA EN EL
0,8 APOYO INTERNO DE LA INTERVALO 1,25 - 2 APOYO INTERNO DE LA TIENEN FUERA LOSA DE MAYOR LUZ LOSA DE MENOR LUZ SISUCESIVAS SI LA RELACIÓN DE CORRESPONDE SEGÚN EL
LUCES ES MAYOR A 2 CRITERIO GENERAL APOYO INTERNO DE LA LOSAS LOSA DE MENOR LUZ SILUCES INTERVALO CORRESPONDE SEGÚN EL RELACIÓN LAS CRITERIO GENERALLAS

TODOS LOS APOYOS DEL UNA DE LA LOSA CUYA
RELACIÓN DE LADOS
2 - ESTÁ FUERA DEL APOYO INTERNO DE LAS APOYO INTERNO DE LAS TIENE FUERA INTERVALO 0,5 - 2 LOSAS CONTINUAS CON EL LOSAS CONTINUAS CON EL 0,5 LADO MAYOR DE UNA LADO MAYOR DE UNA
LOSA CUYA RELACIÓN DE LOSA CUYA RELACIÓN DE LOSAS LADOS APOYO DE LAS LOSAS LADOS ESTÁ FUERA DEL LADOS ESTÁ FUERA DEL
DE CONTINUAS CON EL INTERVALO 0,5 – 2, SI INTERVALO 0,5 – 2, SI LAS LADO MENOR DE UNA CORRESPONDE SEGÚN EL CORRESPONDE SEGÚN EL INTERVALO LOSA CUYA RELACIÓN CRITERIO GENERAL CRITERIO GENERAL DE DE LADOS ESTÁ
UNA FUERA DEL INTERVALO REALCIÓN 0,5 - 2

LOSAS

<!-- p. 33 -->

ESTABILIDAD DE LAS CONSTRUCCIONES III 33

Casos de continuidades con ménsulas.

Cuando en un apoyo existe una losa en ménsula resulta un apoyo de momento conocido ya
que aplicándose la definición de momento flector y las leyes de la estática se puede determinar
ese valor con independencia del resto de las losas.

En ese apoyo no se puede plantear que existe una rótula plástica de momento arbitrario ya que
la losa en ménsula es una losa que en sí misma es isostática y no es posible plantearse en ella
una redistribución de solicitaciones.

Sí debe analizarse la repercusión que ese momento tiene sobre la losa con respecto a la que la
ménsula es continua, se trata de un borde externo de momento conocido, distinto de cero. Para
evaluar esa repercusión, evaluar la importancia de la continuidad, se compara el momento de
la ménsula Mm con el momento de referencia Mo de la losa vecina.

La comparación se divide en tres entornos:

M m \< ,035 ⋅ M o
,035 ⋅ M o ≤ M m \< 5,0 ⋅ M o
5,0 ⋅ M o ≤ M m

Si el momento de la ménsula resulta menor al 35% del momento de referencia se desprecia la
influencia de la continuidad de la ménsula sobre la losa y valen para la misma los coeficientes
de los casos tipos para las losas sin ménsula.

Si el momento de la ménsula se encuentra en el segundo tramo de la comparación se valora
esa continuidad con un valor de 35% del momento de referencia por lo cual aparecen los
siguientes casos tipo de combinación de coeficientes para la losa.

0 0 0,35 0,35

1 1 0.9 0,9
0,35 0,9 0,35 0 1 0,35 0 1 0,35 0,35 0,9 0,35

0 0,35 0,35 0,35

0 0,35 0,35 0,35 0,35

1 0,9 1 0,9 0,83
0,35 0,9 0,35 0,35 0,9 0,35 0,5 0,75 0,5 0,5 0,75 0,5 0,5 0,75 0,5

0,35 0,35 0 0,35 0,5

Se observa, en comparación con los casos tipo generales, que en todos los casos se
mantienen los coeficientes sobre los apoyos y que aparecen dos nuevas combinaciones de
coeficientes de apoyo y tramo 0,35-0,9-0,35 y 0,5-0,83-0,35.

LOSAS

<!-- p. 34 -->

ESTABILIDAD DE LAS CONSTRUCCIONES III 34

A los efectos de determinar los momentos en la situación de simple apoyo, se debe tener en
cuenta que varía la situación de las esquinas y que salvo en un caso, en los demás no existen
esquinas a las que concurran dos bordes sin continuidad.

Si el momento de la ménsula es mayor al 50% del momento de referencia se valora la
continuidad con un coeficiente 0,5 obteniéndose los siguientes casos tipo:

0 0 0,5 0,5

1 1 0,75 0,75
0,5 0,75 0,5 0 1 0,35 0 1 0,35 0,5 0,75 0,5

0 0,5 0,5 0,5

0 0,5 0,5 0,5 0,5

1 0,75 1 0,75 0,75
0,5 0,75 0,5 0,5 0,75 0,5 0,5 0,75 0,5 0,5 0,75 0,5 0,5 0,75 0,5

0,5 0,5 0 0,5 0,5

De la comparación con los casos tipo generales surgen cambios en los coeficientes de los
apoyos internos opuestos a las ménsulas que pasan de 0,35 a 0,5.

Vale también la observación realizada antes con respecto a la transformación de las esquinas
que pasan a tener capacidad resistente frente al alabeo.

Descargas sobre los apoyos.

En el método derivado del reglamento B.A.E.L., los valores de los momentos sobre los apoyos
son sensiblemente menores de los que se obtienen por los métodos lineales, por lo cual se
recomienda, que si se ha realizado el dimensionado de las losas por este método no lineal, se
tomen las descargas sobre los apoyos en función de áreas de influencia definidas según el
gráfico:

45º 45º

45º 45º

45º 45º

45º 45º

\- Se debe tener presente que los valores que se obtienen son el total de carga sobre el
apoyo18. En general se admite que se distribuya uniformemente ese total de carga en la
longitud del apoyo.
\- Cuando existen ménsulas, la descarga de la ménsula se realiza sobre su único apoyo.

18
Estos valores se pueden obtener con la tabla 4.1.6, columna 1, de la publicación Tablas y ábacos para el proyecto
de estructuras. IC. Montevideo-Uruguay
LOSAS

<!-- p. 35 -->

ESTABILIDAD DE LAS CONSTRUCCIONES III 35

BIBLIOGRAFÍA

HAHN
Vigas continuas, pórticos y placas.
Gustavo Gili, Barcelona 1972

R. BARES
Tablas para el cálculo de placas y vigas pared.
Gustavo Gili, Barcelona 1981

FRITZ LEONHARDT
Estructuras de hormigón armado.
El Ateneo, Buenos Aires 1985

JIMENEZ MONTOYA, GARCÍA MESEGUER, MORÁN CABRÉ
Hormigón armado.
Gustavo Gili, Barcelona

JOSÉ CALAVERA
Proyecto y cálculo de estructuras de hormigón.
Intemac, Madrid

NORMAS UNIT
Proyecto y ejecución de estructuras en masa o armado. Norma 1050.
Unit, Montevideo 2005

IC
Tablas para proyecto de estructuras.
Facultad de Arquitectura–Universidad de la República, Montevideo, 1995

H. CHAMLIAN
Estabilidad 2 - Losas
Olceda, Montevideo 1990

COLECTION UTI – DOCUMENT TECHNIQUE UNIFIE
Règles Techniques de concepcion et de calcul des ouvrages et constructions en Béton Armé
suivant la méthode del États-Limites.
Eyrolles, Paris 1985

GEORGES DREUX
Calcul pratique du béton armé. Régles BAEL 80
Eyrolles, Paris 1981

ALBERT FUENTES
Cálculo práctico de estructuras de edificios en hormigón armado
eta, Barcelona 1976

ALBERT FUENTES
Nuevas bases de cálculo del hormigón armado – Importancia de la fisuración
eta, Barcelona 1982

LOSAS

<!-- p. 36 -->

ESTABILIDAD DE LAS CONSTRUCCIONES III 36

LOSAS

<!-- p. 37 -->

ESTABILIDAD DE LAS CONSTRUCCIONES III 37

ÍNDICE

PRÓLOGO 3

CAPÍTULO I
Generalidades 5

CAPÍTULO II
Métodos lineales de resolución de solicitaciones en losas continuas 9

CAPÍTULO III
Método no lineal de resolución de solicitaciones en losas continuas 19

BIBLIOGRAFÍA 35

LOSAS
