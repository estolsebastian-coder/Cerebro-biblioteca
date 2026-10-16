---
type: libro
title: "Mathcad - tp3"
author: "CARLOS_SALOMONE"
categoria: "ESTRUCTURA"
paginas: 33
extraccion: "texto (OCR pendiente)"
fuente: "local:E:/MATERIAL DE CONSULTA/ESTRUCTURA/ESTABILIDADES FADU/tp3.pdf"
convertido: 2026-10-16
---

# Mathcad - tp3

> Texto extraído de `ESTRUCTURA\ESTABILIDADES FADU\tp3.pdf` (33 páginas, texto (OCR pendiente)). El PDF original está en el disco E: (MATERIAL DE CONSULTA); `<!-- p. N -->` marca el inicio de cada página.

<!-- p. 1 -->

TRABAJO PRÁCTICO Nº 3 - RESOLUCIÓN ESTÁTICA DE LOSAS

Efectuar la resolución estática de las losas de la planta tipo (s/PB y s/1º).

Como ejemplo se realizará el análisis de cargas de la planta s/2º (de azotea) y
s/azotea.

Planta s/2º y s/ azotea

En el trabajo práctico anterior (TP Nº 2) se ha efectuado el análisis de cargas
de las losas, en el presente (TP Nº 3) se procederá a realizar la resolución
estática de dichas losas. Esto significa, determinar para cada losa los
momentos flexores tanto en los tramos como en los apoyos entre las losas y
las reacciones sobre los apoyos.

Para la determinación de los momentos flexores y las reacciones se acudirá a
las tablas de Kalmanok, adaptadas en su nomenclatura y que se agregan en
anexo al final de este apunte.

Para el caso de las losas unidireccionales, en los casos en que sea necesario
resolver sistemas hiperestáticos, y dado que dicho tema se incluirá más
adelante, se resolverá simplificadamente por tablas que también se agregan
en anexo.

<!-- p. 2 -->

LOSA 201-207

En este caso se trata de losas en voladizo que responden al siguiente
esquema estructural:

gmamp
q l201 := 1m

1.00

Según surge del trabajo práctico anterior, la carga distribuida resulta:

kgf
q201 := 1039
m2
Asimismo, poseen una carga en el extremo del voladizo correspondiente a un
muro de mamposterìa de cierre de la azotea que también fue determinado en
el trabajo práctico anterior.

kgf
gmamp201 := 384
m

Resolución Estática

SRy201 := gmamp201 + q201 ⋅ l201

kgf
SRy201 = 1423
m

q201 ⋅ l2012
SMex201 := − gmamp201 ⋅ l201 −
2

m
SMex201 = − 904 kgf ⋅
m

Como se puede apreciar en la última expresión, los momentos se expresan en
unidades de momento (Kgf m) sobre fajas de un metro (m). En este caso no se
simplifican los metros.

<!-- p. 3 -->

LOSA 202

En esta oportunidad se trata de una losa bidireccional. Por lo tanto, se
debe resolver por tablas, buscando el caso correspondiente.

Esquema:

Lx = 4.00m

Se utiliza la tabla T29.
202 3.90m
\=
Ly

Datos:

kgf
q202 := 787
m2
lx := 4.00m

ly := 3.90m

ly
ε202 :=
lx

ε202 = 0.975

Se ingresa a la tabla desde abajo y se adopta el valor más cercano (0.95).

Mex := − 0.0696
Mx := 0.0232

Mey := − 0.0724

My := 0.0262

Rx := 0.180
Rex := 0.370

Ry := 0.163
Rey := 0.341

<!-- p. 4 -->

Se multiplica el valor de cada coeficiente por la carga y po la luz menor al
cuadrado y se obtiene el valor de cada momento.

SMex := Mex ⋅ q202 ⋅ ly2
m
SMex = − 833 kgf ⋅
m
SMx := Mx ⋅ q202 ⋅ ly2
m
SMx = 278kgf ⋅
m
SMey := Mey ⋅ q202 ⋅ ly2
m
SMey = − 867 kgf ⋅
m
SMy := My ⋅ q202 ⋅ ly2
m
SMy = 314kgf ⋅
m

Como se aprecia, las unidades corresponden a momentos por ancho de faja
de 1.00 m.

A continuación se obtienen las reacciones para lo cual se repite el
procedimiento cnsistente en multiplicar los coeficientes de la tabla por la
carga y la luz menor. Ademàs, hay que tener en cuenta que las tablas dan los
valores de las reacciones para toda la línea. Esto implica que la nomenclatura
se debe entender de acuerdo al siguiente gráfico. Por último, se debe tener
en cuenta que estos valores se deben dividir por la longitud del lado para
obtener las cargas por metro.

Rx

Rey 202 Ry

Rex

ly2 kgf
SRex := Rex ⋅ q202 ⋅ SRex = 1107
lx m

ly2
SRx := Rx ⋅ q202 ⋅ kgf SRx = 539 lx m

<!-- p. 5 -->

ly2
SRey := Rey ⋅ q202 ⋅
ly kgf
SRey = 1047
m
ly2
SRy := Ry ⋅ q202 ⋅ kgf ly SRy = 500
m

LOSA 203

En este caso se trata de losas en voladizo que responden al siguiente
esquema estructural:

l203 := 2m

q

A

B
2.00

En este caso se trata de un sistema hiperestático por lo cual no tiene
resolución con las ecuaciones de la estática. A los fines prácticos, se ha
incluido una tabla donde se indican coeficientes que permiten resolver estos
casos y que se agrega en anexo.

Tomando en cuenta que el esquema observado es equivalente estáticamente
al de dos vigas continuas con luces y cargas iguales, se adopta el primer caso
de la tabla T51, agregada en anexo.

Para utilizar esta tabla es necesario en primer lugar determinar la relación que
existe entre cargas permanente y totales (permanentes + sobrecargas) porque
considera que las sobrecargas se aplican o bien en uno de los tramos o en la
totalidad de los tramos. Esto se debe a que de esa manera se obtienen los
casos más desfavorables para los momentos de tramo, apoyo y esfuerzos de
corte. Sin embargo, no es necesario realizar una determinación precisa ya que
las diferencias son pequeñas y por tal motivo, se establece que las cargas
permanentes son el 70% de las cargas totales. De ahí:

g203
\= 0.7
q203

<!-- p. 6 -->

Del TP2, se obtiene la carga permanente

kgf
q203 := 692
m2

De la tabla T51 se obtienen los siguientes valores:

m1 := 12.90 (coeficiente del momento de tramo)

mB := − 9.41 (coeficiente del momento de apoyo)

q1A := 2.54 (coeficiente del esfuerzo de corte en apoyo articulado)

q1B := − 1.65 (coeficiente del esfuerzo de corte en apoyo empotrado)

Resolución Estática

l203
SRA := q203 ⋅
q1A
kgf
SRA = 545
m

l203
SRB := q203 ⋅
q1B
kgf
SRB = − 839
m

l2032
SMx203 := q203 ⋅
m1
m
SMx203 = 215kgf ⋅
m

l2032
SMex203 := q203 ⋅
mB
m
SMex203 = − 294 kgf ⋅
m

<!-- p. 7 -->

LOSA 204

En esta oportunidad se trata de una losa bidireccional con dos apoyos en
voladizo. Por lo tanto, se debe resolver por tablas, buscando el caso
correspondiente.

Esquema:

Lx = 2.00m

Se utiliza la tabla T29.
1.30m 204
\=
Ly

Datos:

kgf
q204 := 692
m2
lx := 2.00m

ly := 1.30m

ly
ε204 :=
lx

ε204 = 0.65

Se ingresa a la tabla desde abajo y se adopta el valor más cercano (0.95).

Mex := − 0.0773
Mx := 0.0153

Mey := − 0.1047

My := 0.0462

Rx := 0.356
Rex := 0.670

<!-- p. 8 -->

Ry := 0.159
Rey := 0.350

Se multiplica el valor de cada coeficiente por la carga y po la luz menor al
cuadrado y se obtiene el valor de cada momento.

SMex := Mex ⋅ q204 ⋅ ly2
m
SMex = − 90 kgf ⋅
m
SMx := Mx ⋅ q204 ⋅ ly2
m
SMx = 18kgf ⋅
m
SMey := Mey ⋅ q204 ⋅ ly2
m
SMey = − 122 kgf ⋅
m
SMy := My ⋅ q204 ⋅ ly2
m
SMy = 54kgf ⋅
m

Como se aprecia, las unidades corresponden a momentos por ancho de faja
de 1.00 m.

A continuación se obtienen las reacciones para lo cual se repite el
procedimiento cnsistente en multiplicar los coeficientes de la tabla por la
carga y la luz menor. Ademàs, hay que tener en cuenta que las tablas dan los
valores de las reacciones para toda la línea. Esto implica que la nomenclatura
se debe entender de acuerdo al siguiente gráfico. Por último, se debe tener
en cuenta que estos valores se deben dividir por la longitud del lado para
obtener las cargas por metro.

Rx
Rey 204 Ry
Rex

ly2 kgf
SRex := Rex ⋅ q204 ⋅ SRex = 392
lx m

<!-- p. 9 -->

ly2
SRx := Rx ⋅ q204 ⋅ kgf SRx = 208 lx m

ly2
SRey := Rey ⋅ q204 ⋅
ly kgf
SRey = 315
m
ly2
SRy := Ry ⋅ q204 ⋅ kgf ly SRy = 143
m

LOSA 205

En esta oportunidad se trata de una losa bidireccional. Por lo tanto, se
debe resolver por tablas, buscando el caso correspondiente.

Esquema:
Lx = 4.00m

Se utiliza la tabla T30.

3.90m 205
\=
Ly

En este caso, se deberá girar la losas sin rotar los ejes para utilizar la tabla.
De esta forma, los valores que se obtienen en x, corresponden a y y viceversa

Datos:

kgf
q205 := 787
m2
lx := 4.00m

ly := 3.90m

<!-- p. 10 -->

ly
ε205 :=
lx

ε205 = 0.975

Como hemos anticipado, es necesario girar la tabla. ingresa a la tabla desde
arriba y se adopta el valor más cercano (0.95). Los valores siguientes, ya
tienen hecha la transformación.

Mex := − 0.0556
Mx := 0.0193

Mey := − 0.0628

My := 0.0249

Rex := 0.343

Ry := 0.103
Rey := 0.264

Se multiplica el valor de cada coeficiente por la carga y po la luz menor al
cuadrado y se obtiene el valor de cada momento.

SMex := Mex ⋅ q205 ⋅ ly2
m
SMex = − 666 kgf ⋅
m
SMx := Mx ⋅ q205 ⋅ ly2
m
SMx = 231kgf ⋅
m
SMey := Mey ⋅ q205 ⋅ ly2
m
SMey = − 752 kgf ⋅
m
SMy := My ⋅ q205 ⋅ ly2
m
SMy = 298kgf ⋅
m

Como se aprecia, las unidades corresponden a momentos por ancho de faja
de 1.00 m.

A continuación se obtienen las reacciones para lo cual se repite el
procedimiento cnsistente en multiplicar los coeficientes de la tabla por la
carga y la luz menor. Ademàs, hay que tener en cuenta que las tablas dan los

<!-- p. 11 -->

g y y q q
valores de las reacciones para toda la línea. Esto implica que la nomenclatura
se debe entender de acuerdo al siguiente gráfico. Por último, se debe tener
en cuenta que estos valores se deben dividir por la longitud del lado para
obtener las cargas por metro.

Rex

Ry 205 Rey

Rex

ly2 kgf
SRex := Rex ⋅ q205 ⋅ SRex = 1026
lx m
ly2
SRey := Rey ⋅ q205 ⋅
ly kgf
SRey = 810
m
ly2
SRy := Ry ⋅ q205 ⋅ kgf ly SRy = 316
m

LOSA 206-209

En esta oportunidad se trata de una losa bidireccional. Por lo tanto, se
debe resolver por tablas, buscando el caso correspondiente.

Esquema:

Lx = 4.00m

Se utiliza la tabla T29.
206 3.90m
\=
Ly

<!-- p. 12 -->

Datos:

kgf
q206 := 787
m2

lx := 4.00m

ly := 3.90m
ly
ε206 :=
lx

ε206 = 0.975

Se ingresa a la tabla desde abajo y se adopta el valor más cercano (0.95).

Mex := − 0.0696
Mx := 0.0232

Mey := − 0.0724

My := 0.0262

Rx := 0.180
Rex := 0.370

Ry := 0.163
Rey := 0.341

Se multiplica el valor de cada coeficiente por la carga y po la luz menor al
cuadrado y se obtiene el valor de cada momento.

SMex := Mex ⋅ q206 ⋅ ly2
m
SMex = − 833 kgf ⋅
m
SMx := Mx ⋅ q206 ⋅ ly2
m
SMx = 278kgf ⋅
m
SMey := Mey ⋅ q206 ⋅ ly2
m
SMey = − 867 kgf ⋅
m
SMy := My ⋅ q206 ⋅ ly2
m
SMy = 314kgf ⋅
m

<!-- p. 13 -->

Como se aprecia, las unidades corresponden a momentos por ancho de
faja de 1.00 m.

A continuación se obtienen las reacciones para lo cual se repite el
procedimiento cnsistente en multiplicar los coeficientes de la tabla por la
carga y la luz menor. Ademàs, hay que tener en cuenta que las tablas dan
los valores de las reacciones para toda la línea. Esto implica que la
nomenclatura se debe entender de acuerdo al siguiente gráfico. Por último,
se debe tener en cuenta que estos valores se deben dividir por la longitud
del lado para obtener las cargas por metro.

Rx

Rey 206 Ry

Rex

ly2 kgf
SRex := Rex ⋅ q206 ⋅ SRex = 1107
lx m

ly2
SRx := Rx ⋅ q206 ⋅ kgf SRx = 539 lx m

ly2
SRey := Rey ⋅ q206 ⋅
ly kgf
SRey = 1047
m
ly2
SRy := Ry ⋅ q206 ⋅ kgf ly SRy = 500
m

LOSA 208

En esta oportunidad se trata de una losa bidireccional. Por lo tanto, se
debe resolver por tablas, buscando el caso correspondiente.

Esquema:

<!-- p. 14 -->

Lx = 4.00m

Se utiliza la tabla T30.
3.90m 208
\=
Ly

Datos:

kgf
q208 := 787
m2
lx := 4.00m

ly := 3.90m

ly
ε208 :=
lx
ε208 = 0.975

Se ingresa a la tabla desde abajo y se adopta el valor más cercano (0.95).

Mex := − 0.0626
Mx := 0.0230

Mey := − 0.0599

My := 0.0193

Rex := 0.293

Ry := 0.120
Rey := 0.320

<!-- p. 15 -->

Se multiplica el valor de cada coeficiente por la carga y po la luz menor al
cuadrado y se obtiene el valor de cada momento.

SMex := Mex ⋅ q208 ⋅ ly2
m
SMex = − 749 kgf ⋅
m
SMx := Mx ⋅ q208 ⋅ ly2
m
SMx = 275kgf ⋅
m
SMey := Mey ⋅ q208 ⋅ ly2
m
SMey = − 717 kgf ⋅
m
SMy := My ⋅ q208 ⋅ ly2
m
SMy = 231kgf ⋅
m

Como se aprecia, las unidades corresponden a momentos por ancho de faja
de 1.00 m.

A continuación se obtienen las reacciones para lo cual se repite el
procedimiento cnsistente en multiplicar los coeficientes de la tabla por la
carga y la luz menor. Ademàs, hay que tener en cuenta que las tablas dan los
valores de las reacciones para toda la línea. Esto implica que la nomenclatura
se debe entender de acuerdo al siguiente gráfico. Por último, se debe tener
en cuenta que estos valores se deben dividir por la longitud del lado para
obtener las cargas por metro.

Rex

208 Ry Rey

Rx
ly2 kgf
SRex := Rex ⋅ q208 ⋅ SRex = 877
lx m

<!-- p. 16 -->

ly2
SRey := Rey ⋅ q208 ⋅
ly kgf
SRey = 982
m

ly2
SRy := Ry ⋅ q208 ⋅ kgf ly SRy = 368
m

LOSA 301

En esta oportunidad se trata de una losa bidireccional. Por lo tanto, se
debe resolver por tablas, buscando el caso correspondiente.

Esquema:

Lx = 2.00m

Se utiliza la tabla T26.

3.90m 301
\=
Ly

Datos:

kgf
q301 := 592
m2
lx := 2.00m

ly := 3.90m
lx
ε301 :=
ly

ε301 = 0.513

Se ingresa a la tabla desde arriba y se adopta el valor más cercano (0.50).
Mx := 0.0965

My := 0.0174

<!-- p. 17 -->

Rx := 0.269

Ry := 0.731

Se multiplica el valor de cada coeficiente por la carga y po la luz menor al
cuadrado y se obtiene el valor de cada momento.

SMx := Mx ⋅ q301 ⋅ ly2
m
SMx = 869kgf ⋅
m
SMy := My ⋅ q301 ⋅ ly2
m
SMy = 157kgf ⋅
m

Como se aprecia, las unidades corresponden a momentos por ancho de faja
de 1.00 m.

A continuación se obtienen las reacciones para lo cual se repite el
procedimiento cnsistente en multiplicar los coeficientes de la tabla por la
carga y la luz menor. Ademàs, hay que tener en cuenta que las tablas dan los
valores de las reacciones para toda la línea. Esto implica que la nomenclatura
se debe entender de acuerdo al siguiente gráfico. Por último, se debe tener
en cuenta que estos valores se deben dividir por la longitud del lado para
obtener las cargas por metro.

Rx

Ry 301 Ry

Rx

ly2
SRx := Rx ⋅ q301 ⋅ kgf SRx = 1211 lx m

ly2
SRy := Ry ⋅ q301 ⋅ kgf ly SRy = 1688
m

LOSA ESCALERA

<!-- p. 18 -->

En este caso se trata de losas unidireccionales que funcionan en forma
similar a una viga simplemente apoyada:

qesc

lesc := 2.60m

2.60

Según surge del trabajo práctico anterior, la carga distribuida resulta:

kgf
qesc := 1039
m2

Resolución Estática

lesc
Rxesc := qesc ⋅
2

kgf
Rxesc = 1351
m

qesc ⋅ lesc2
Myesc :=
8
m
Myesc = 878kgf ⋅
m

Como se puede apreciar en la última expresión, los momentos se expresan en
unidades de momento (Kgf m) sobre fajas de un metro (m). En este caso no se
simplifican los metros.

<!-- p. 19 -->

COMPATABILIZACIÓN DE APOYOS

Hasta este momento se han calculado todas las losas como si fueran
losas aisladas lo que implica que se obtuvo un momento de tramo para
cada una de ellas. No ocurre lo mismo con los momentos de apoyo para
los cuales en muchos casos tenemos dos. También hay que tener en
cuenta que hasta aquí hemos presupuesto empotramientos cuya validez
debe ser verificada.

La compatibilización de apoyos consiste en reunir de nuevo toda la
planta, obtener los momentos de apoyo, verificar las hipótesis relativas a
empotramientos y, eventualmente, recalcular los tramos.

Para ello tomaremos el esquema de la planta e indicaremos dentro de
ella los momentos de apoyo.

Esquema:

<!-- p. 20 -->

Se analizan los diferentes apoyos:

Apoyo Losa 201-202

SMex202
rel := rel = 0.92 SMex201

Por tratarse de un voladizo, en el cual el momento que se obtiene del cálculo
es el único que garantiza el cumplimiento del equilibrio estático, el momento
no se promedia y se adopta como momento del apoyo directamente el del
voladizo. Como la rel es mayor a 0.80, no se modifica el momento de tramo
Mx de la losa 202.

SMex201_202 := SMex201

m
SMex201_202 = − 904 kgf ⋅
m

Apoyo Losa 202-203

En este caso, se considera que la losa 203 está empotrada en la losa 202,
pero no a la inversa. Por tal motivo, el momento de apoyo es directamente el
de la losa 203 y no se modifica el momento de tramo x de esta losa.

SMex202_203 := SMex203

m
SMex202_203 = − 294 kgf ⋅
m

Apoyo Losa 203-204

En este caso, se considera que la losa 204 está empotrada en la losa 203,
pero no a la inversa. Por tal motivo, el momento de apoyo es directamente el
de la losa 204 y no se modifica el momento de tramo x de esta losa.

SMex203_204 := SMex204

m
SMex203_204 = − 90 kgf ⋅
m
Apoyo Losa 205-206

SMex205
rel := rel = 0.80 SMex206

<!-- p. 21 -->

En este caso la relación es mayor o igual a 0.80, por lo cual el momento en el
apoyo es el promedio de ambos momentos y no se modifican los momentos
de tramo.
SMex205 + SMex206
SMex205_206 :=
2

m
SMex205_206 = − 749 kgf ⋅
m

Apoyo Losa 207-208

SMex208
rel :=
SMex207 rel = 0.83

Por tratarse de un voladizo, en el cual el momento que se obtiene del cálculo
es el único que garantiza el cumplimiento del equilibrio estático, el momento
no se promedia y se adopta como momento del apoyo directamente el del
voladizo. Como la relación es mayor a 0.80, no se modifica el momento de
tramo Mx de la losa 208.

SMex207_208 := SMex201

m
SMex207_208 = − 904 kgf ⋅
m

Apoyo Losa 208-209

SMex208
rel :=
SMex209 rel = 0.90

En este caso la relación es mayor o igual a 0.80, por lo cual el momento en el
apoyo es el promedio de ambos momentos y no se modifican los momentos
de tramo.
SMex208 + SMex209
SMex208_209 :=
2
m
SMex208_209 = − 791 kgf ⋅
m

Apoyo Losa 202-205

<!-- p. 22 -->

SMey205
rel :=
SMey202 rel = 0.87

En este caso la relación es mayor o igual a 0.80, por lo cual el momento en el
apoyo es el promedio de ambos momentos y no se modifican los momentos
de tramo.
SMey202 + SMey205
SMey202_205 :=
2

m
SMey202_205 = − 809 kgf ⋅
m
Apoyo Losa 204-206

En este caso, se considera que la losa 204 está empotrada en la losa 206,
pero no a la inversa. Por tal motivo, el momento de apoyo es directamente el
de la losa 204 y no se modifica el momento de tramo y de esta losa.

SMey203_206 := SMey204

m
SMey203_206 = − 122 kgf ⋅
m

Apoyo Losa 205-208

SMey208
rel :=
SMey205 rel = 0.95

En este caso la relación es mayor o igual a 0.80, por lo cual el momento en el
apoyo es el promedio de ambos momentos y no se modifican los momentos
de tramo.
SMey205 + SMey208
SMey205_208 :=
2

m
SMey205_208 = − 734 kgf ⋅
m

Apoyo Losa 206-209

En este caso los momentos son iguales por lo que no hay que valen los
momentos obtenidos anteriormente.

<!-- p. 23 -->

Seguidamente se vuelcan en un diagrama los momentos de apoyo unificados.

<!-- p. 24 -->



<!-- p. 25 -->



<!-- p. 26 -->



<!-- p. 27 -->



<!-- p. 28 -->



<!-- p. 29 -->



<!-- p. 30 -->



<!-- p. 31 -->



<!-- p. 32 -->



<!-- p. 33 -->


