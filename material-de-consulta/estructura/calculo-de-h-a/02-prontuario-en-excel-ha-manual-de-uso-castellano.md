---
type: libro
title: "PRONTUARIO EN EXCEL DE HORMIGÓN ARMADO"
author: "HP"
categoria: "ESTRUCTURA"
paginas: 71
extraccion: "texto (OCR pendiente)"
fuente: "local:E:/MATERIAL DE CONSULTA/ESTRUCTURA/CÁLCULO DE H.A/02. Prontuario_en_Excel_HA- Manual de Uso (Castellano).pdf"
convertido: 2026-10-16
---

# PRONTUARIO EN EXCEL DE HORMIGÓN ARMADO

> Texto extraído de `ESTRUCTURA\CÁLCULO DE H.A\02. Prontuario_en_Excel_HA- Manual de Uso (Castellano).pdf` (71 páginas, texto (OCR pendiente)). El PDF original está en el disco E: (MATERIAL DE CONSULTA); `<!-- p. N -->` marca el inicio de cada página.

<!-- p. 1 -->



<!-- p. 2 -->

Prontuario en Excel de Hormigón Armado (Adaptado a EHE-08)

ÍNDICE

RESUMEN ................................................................................................................................. 3

A. INTRODUCCIÓN DE DATOS E INTERPRETACIÓN DE RESULTADOS ....................................... 4

CRITERIOS GENERALES ................................................................................................. 5

INTRODUCIÓN DE DATOS ........................................................................................ 5

INTERPRETACIÓN DE RESULTADOS .......................................................................... 6

POSIBLE ERROR EN LA LECTURA DE RESULTADOS .................................................... 7

B. DESCRIPCIÓN DE LAS HOJAS PROCEDIMIENTOS DE CÁLCULO .......................................... 8

FLEXIÓN SIMPLE ........................................................................................................... 9

DIMENSIONADO ...................................................................................................... 9

COMPROBACIÓN ................................................................................................... 10

FLEXIÓN COMPUESTA ................................................................................................ 11

DIMENSIONADO .................................................................................................... 11

COMPROBACIÓN ................................................................................................... 12

COMPROBACIÓN A FLEXOCOMPRESIÓN SIMÉTRICA U OBLICUA ............................... 14

CORTANTE ................................................................................................................. 16

DIMENSIONADO .................................................................................................... 16

COMPROBACIÓN ................................................................................................... 17

TORSIÓN .................................................................................................................... 18

DIMENSIONADO .................................................................................................... 18

COMPROBACIÓN ................................................................................................... 19

PUNZONAMIENTO ..................................................................................................... 22

RASANTE .................................................................................................................... 24

ANCLAJE DE ARMADURAS.......................................................................................... 25

EMPALME POR SOLAPO ............................................................................................. 26

INESTABILIDAD DE SOPORTES (PANDEO) ................................................................... 27

DEFORMACIÓN .......................................................................................................... 28

FISURACIÓN ............................................................................................................... 31

C. SIMBOLOGÍA Y ARTICULADO .......................................................................................... 32

FLEXIÓN SIMPLE – SECCIONES RECTANGULARES ....................................................... 33

FLEXIÓN SIMPLE – SECCIONES EN T ............................................................................ 35

FLEXIÓN COMPUESTA – SECCIONES RECTANGULARES ............................................... 37

FLEXIÓN COMPUESTA- SECCIONES EN T..................................................................... 39

FLEXOCOMPRESIÓN SIMÉTRICA O ESVIADA .............................................................. 41

Manual de uso 1

<!-- p. 3 -->

Prontuario en Excel de Hormigón Armado (Adaptado a EHE-08)

CORTANTE ................................................................................................................. 42

TORSIÓN – SECCIONES RECTANGULARES ................................................................... 46

TORSIÓN – SECCIONES HUECAS ................................................................................. 50

PUNZONAMITENTO ................................................................................................... 54

DIMENSIONADO A RASANTE SECCIONES RECTANGULARES ....................................... 56

ANCLAJE DE BARRAS O MALLAS ................................................................................. 57

ANCLAJE POR SOLAPO ............................................................................................... 58

INESTABILIDAD DE SOPORTES .................................................................................... 59

DEFORMACIONES ...................................................................................................... 60

FISURACIÓN ............................................................................................................... 64

ANEJO 1. CÁLCULO DE ARMADURAS.......................................................................... 65

D. ANEJO ............................................................................................................................. 66

TUTORIALES DE EXCEL ................................................................................................ 67

FUNCIÓN SOLVER .................................................................................................. 67

Manual de uso 2

<!-- p. 4 -->

Prontuario en Excel de Hormigón Armado (Adaptado a EHE-08)

RESUMEN

Este documento es el Manual de Uso del Prontuario en Excel de
Hormigón Armado, que ayudará al usuario en la utilización y
comprensión de las distintas hojas de cálculo que componen el
prontuario. El manual dispone de cuatro partes diferenciadas: en la
primera se muestran los criterios generales de funcionamiento del
programa, en la segunda se describe el funcionamiento de cada
hoja, seguidamente la simbología de cada hoja y por último un
anejo con un tutorial necesario para poder utilizar correctamente
una de las hojas de cálculo.

Manual de uso 3

<!-- p. 5 -->

Prontuario en Excel de Hormigón Armado (Adaptado a EHE-08)

A. INTRODUCCIÓN DE DATOS E
INTERPRETACIÓN DE RESULTADOS

Manual de uso 4

<!-- p. 6 -->

Prontuario en Excel de Hormigón Armado (Adaptado a EHE-08)

CRITERIOS GENERALES

Todas las hojas de Excel se han diseñado con criterios prácticamente idénticos para que los
datos y los resultados sean fácilmente interpretables para el usuario.

INTRODUCIÓN DE DATOS

Hay tres tipos de datos que el usuario puede introducir:
\1) Características de la sección y de los materiales:

h 0,50 m
fyk 500 N/mm²
Este tipo de datos se destacan con casillas con fondo azul y letra “Calibri” en
negro.
\2) Coeficientes de seguridad y factor de cansancio del hormigón.

γs 1,15 u
γc 1,50 u
αcc 1,00 u
Estos datos están introducidos por defecto según lo determinado por EHE-08,
pero se han dejado editables para facilitar su modificación en caso de algún
futuro cambio normativo o por necesidad de modificación por el usuario.
\3) Pestañas desplegables: Se han creado dos tipos de pestañas desplegables.
a. El primer tipo de pestañas, se muestran en una casilla rectangular gris, con
fondo blanco, con el símbolo de una flecha negra dentro de un recuadro gris.
Al clicar esta flecha, se muestra una lista. La opción seleccionada se verá
mostrada en azul, y aparecerá en la casilla cuando la tabla esté plegada.

Esta tabla se ha creado para los casos en que la normativa da a escoger entre
diversas opciones que se tienen en consideración en los cálculos.
b. En algunos casos se han tenido que crear listas desplegables debido a las
limitaciones propias de la hoja de cálculo, y no por limitaciones de normativa.
Estas listas se mostrarán como una casilla de introducción de datos de color
azul, pero al clicar en ella, al usuario le aparecerá la lista, en lugar de la
posibilidad de editar el texto:

Manual de uso 5

<!-- p. 7 -->

Prontuario en Excel de Hormigón Armado (Adaptado a EHE-08)

\4) Botón de selección: en algunos casos, se ha preferido crear un botón de selección en
lugar de una lista desplegable, si bien su función es la misma. El usuario deberá clicar
sobre el botón que sea oportuno, este se remarcará en negro, y los demás
permanecerán en blanco.

INTERPRETACIÓN DE RESULTADOS

Los resultados de cálculos intermedios, requeridos para la obtención del resultado final de la
hoja de cálculo, que además se consideran datos importantes para el usuario; se representan
con letra gris y en cursiva.
fyd 434,8 N/mm²
FC,LIM 925,3 kN

Se facilitan, además dos tipos de “Resultados finales”, los favorables y los desfavorables. Los
favorables, como se muestra a continuación, aparecen resaltados con fondo amarillo y letra
negrita, si un resultado final resulta desfavorable, aparecerá grafiado en color rojo.
AS1 11,85 cm²

En algunos casos, como en las tablas de dimensionado de las armaduras, en que se muestran
diversos resultados posibles, se le muestran al usuario algunos valores que son erróneos, pero
que pueden resultar de interés. Para evitar posibles confusiones se han destacado en rojo y se
han tachado, dejando visibles los valores pero mostrando que no son válidos.
SREAL 11,85 cm

En el caso de resultados o factores que vengan determinados por tablas de la EHE-08 se han
incluido dichas tablas. En ellas se resaltan la fila y la columna en las que se encuentra el
resultado y la intersección de ambas se muestra con un tono más ocre y con las letras en
negrita.

m

fyk
fck
400 500
25 1,2 1,5
30 1,0 1,3
35 0,9 1,2
40 0,8 1,1
45 0,7 1,0
50 0,7 1,0

En el caso de las hojas de Comprobación y en el caso de las hojas de Dimensionado en que se
tenga que calcular la resistencia del hormigón, se pueden encontrar estos dos tipos de
resultados:

Manual de uso 6

<!-- p. 8 -->

Prontuario en Excel de Hormigón Armado (Adaptado a EHE-08)

\1) Resultados favorables que cumplen los requerimientos marcados por la normativa.
Resaltados en verde, negrita y cursiva.
VU1 675,00 kN
b0 × d Cumple

\2) Resultados desfavorables, que no cumplen los requerimientos de la normativa.
Resaltados en rojo, cursiva y en negrita.
VU1 675,00 kN
Tal como se describe en el apartado de Descripción de las hojas, en las hojas de comprobación
de secciones, se han realizado anotaciones que aparecen de modo automático que ayudan a la
interpretación de los resultados.

POSIBLE ERROR EN LA LECTURA DE RESULTADOS

En algún caso, es probable que al introducir los datos en la hoja de cálculo, el resultado se
muestre del siguiente modo:

VSU ###### kN
Estas almohadillas no implican necesariamente un error en el cálculo, puede ser debido a que
el resultado sea una cifra demasiado grande y que no quepa en la casilla.
Existen dos modos de poder ver el resultado, el primero y más sencillo es que el usuario sitúe
el cursor sobre la casilla donde le aparece dicho “error”; en unos segundos aparecerá un
recuadro con el valor que las almohadillas ocultan:

Si, por comodidad, el usuario desea que ese resultado sea visible permanentemente en su hoja
de cálculo, y dado que no puede modificar el tipo ni el tamaño de letra de las casillas de
resultados, otra posible solución es aumentar o disminuir el zoom de la hoja:

Las casillas de resultados están diseñadas para que admitan un máximo de 3 decimales, y se
han modificado sus tamaños procurando que no se de este error; pero esto puede variar en
función del ordenador y del Pack de Office que se utilice.

Manual de uso 7

<!-- p. 9 -->

Prontuario en Excel de Hormigón Armado (Adaptado a EHE-08)

B. DESCRIPCIÓN DE LAS HOJAS
PROCEDIMIENTOS DE CÁLCULO

Manual de uso 8

<!-- p. 10 -->

Prontuario en Excel de Hormigón Armado (Adaptado a EHE-08)

FLEXIÓN SIMPLE

Para el cálculo de secciones sometidas a flexión simple (donde solo aparece momento flector)
se ha utilizado el Diagrama Rectangular, reflejado en el Artículo 39.5 de la EHE-08, es un
método aproximado pero muy efectivo que se basa en el hecho de que, a partir de un
determinado momento flector, denominado Momento Límite (MLIM) disponer únicamente de
armadura a tracción deja de ser eficaz. Esto es así dado que debe existir siempre un equilibrio
de fuerzas entre la parte comprimida del hormigón y la zona traccionada, si la parte
comprimida aumenta, el brazo mecánico va disminuyendo, por lo que la armadura necesita
una sección exponencialmente mayor para resistir los esfuerzos.

El MLIM se calcula a partir de xLIM, que viene determinada en los Dominios de Deformación que
aparecen en el Artículo 42.1.3 de la EHE-08.

DIMENSIONADO

La hoja de cálculo solicita inicialmente que el usuario introduzca las características de los
materiales, las dimensiones de la sección y el esfuerzo al que está sometido.

Es condición indispensable introducir los valores en el mismo sentido que se muestra en el
croquis. El Momento Flector siempre será positivo y en el sentido que se muestra en la citada
figura:

Si el momento flector real es negativo, se introducirá su
As2 valor absoluto y el usuario deberá interpretar que As1 en su
caso se situará en la parte superior de la sección y As2 en la
d inferior.h Md

De todos los datos introducidos se extraerán algunos valores
As1 característicos de la sección, es decir, los límite (yLIM, Fc,LIM y
r i MLIM) y se calculan los valores “reales” (Fc e y); todos ellos se
muestran en el apartado de Cálculos. Sobre los valores
“reales” aparecerá automáticamente uno de los siguientes casos: 0\<Md≤Mlim o Md>Mlim el
primero indica que el esfuerzo es inferior al Momento límite, y que por lo tanto la sección no
requiere armadura mecánica mínima a compresión; el segundo caso, determina que el
esfuerzo es mayor al límite, y que por lo tanto se deberá aumentar la armadura comprimida,
AS2, para que el dimensionado de la armadura de la sección sea el óptimo.

Una vez determinados esos valores se facilitan tanto la armadura mecánica requerida como la
geométrica mínima de norma.

La hoja de cálculo detecta cuáles son los valores más elevados, y los destaca en amarillo y
negrita. Dichos valores destacados son los que utiliza en el último apartado, en que determina
cuántas barras se requerirían para cualquier diámetro y determina tanto la separación real
como la mínima. La hoja detectará qué resultados cumplen o no destacando los que sí lo
hagan y tachando a los que no. Esto supone que se reflejarán varios resultados aptos, y el
usuario deberá determinar cuál es el óptimo.

Manual de uso 9

<!-- p. 11 -->

Prontuario en Excel de Hormigón Armado (Adaptado a EHE-08)

AS1
ØS1 #barras AREAL SREAL SMIN
(mm) (ud) (cm²) (cm) (cm)

14 8 12,32 0,54 2,00
16 6 12,06 1,08 2,00
20 4 12,57 2,33 2,00
25 3 14,73 3,75 2,50
32 2 16,08 8,6 3,20
40 1 12,57 ― 4,00

Si todos los valores de la tabla aparecieran tachados, es decir, ninguno cumple las
separaciones mínimas que establece la normativa, aparecerá una anotación en la parte
superior de la tabla, que indica que se debe aumentar la sección.

COMPROBACIÓN

La introducción de los datos en la hoja de comprobación es similar a la descrita en el apartado
anterior, deberán introducirse características geométricas de la sección, características de los
materiales, esfuerzos de cálculo (que deberán introducirse con su valor absoluto) y las
características geométricas de las barras.

El procedimiento utilizado para la obtención de los resultados de esta hoja se basa en la
aplicación de una hipótesis previa, que establece que ambas armaduras trabajan a su
capacidad mecánica y que se hallan en Dominio 2. Así se obtienen unos valores estimados, que
no se muestran dado que no siempre son reales. Estos valores estimados, son comparados con
los valores límite (que determinan el límite entre los dominios 3 y 4), estos últimos valores se
muestran en el apartado de Cálculos junto con los resultados de las capacidades mecánicas de
las armaduras.

En el apartado de Resultados, se muestran los valores de Fc, yREAL y MU y además se determina
el dominio de deformación en el que se halla la sección. El momento último (MU) determina el
momento máximo que puede resistir la sección.

En caso de que la armadura de la sección no fuera suficiente, es decir, que el MU fuera menor
a Md, el resultado se verá destacado en rojo. Independientemente del resultado, siempre
aparecerá una nota que ayudará a su interpretación y además facilitará información adicional.

Interpretación de resultados:
No cumple, insuficientes armaduras S1 y S2

Esta nota determinará si la sección cumple o no, y además le facilitará al usuario información
sobre el motivo de su incumplimiento: si es debido a AS1, a AS2 o a ambas. No se muestran
resultados numéricos dado que se trata de una comprobación. Para el correcto dimensionado
de las barras puede utilizarse tanto la hoja de comprobación mediante tanteo, como la hoja
anterior (de dimensionado).

Manual de uso 10

<!-- p. 12 -->

Prontuario en Excel de Hormigón Armado (Adaptado a EHE-08)

FLEXIÓN COMPUESTA

En esta hoja se utiliza el Método de Ehlers, que establece que «todo problema de flexión
compuesta, puede reducirse a uno de flexión simple, sin más que tomar como momento, el que
produce el esfuerzo normal con respecto a la armadura de tracción Md=Nd·e»

Una vez realizada esta simplificación, se podrá utilizar el mismo método que para la flexión
simple, Diagrama Rectangular, reflejado en el Artículo 39.5 de la EHE-08, es un método
aproximado pero muy efectivo que se basa en el hecho de que, a partir de un determinado
momento flector, denominado Momento Límite (MLIM) disponer únicamente de armadura a
tracción deja de ser eficaz. Esto es así dado que debe existir siempre un equilibrio de fuerzas
entre la parte comprimida del hormigón y la zona traccionada, si la parte comprimida
aumenta, el brazo mecánico va disminuyendo, por lo que la armadura necesita una sección
exponencialmente mayor para resistir los esfuerzos.

El MLIM se calcula a partir de xLIM, que viene determinada en los Dominios de Deformación que
aparecen en el Artículo 42.1.3 de la EHE-8.

DIMENSIONADO

La hoja de cálculo solicita inicialmente que el usuario introduzca las características de los
materiales, las dimensiones de la sección y el esfuerzo al que está sometido.

Es indispensable que el usuario introduzca el momento flector en el mismo sentido que
establece la figura, si bien podrá variarse el sentido del axil, estableciéndose como valor
positivo el de las compresiones y como valor
As2 negativo el de las tracciones.
Md

Si el momento flector real es negativo, se
d
h Nd introducirá su valor absoluto y el usuario deberá
interpretar que As1 en su caso se situará en la parte
superior de la sección y As2 en la inferior.
As1 Tracción[-]
r i Con la introducción de las acciones aparecerá un
nuevo momento flector denominado Md’, que se obtiene de la aplicación del Método de
Ehlers, y es el sumatorio del Momento flector más el momento generado por el Axil.

De todos los datos introducidos se extraerán algunos valores característicos de la sección, es
decir, los límite (yLIM, Fc,LIM y MLIM) y se calculan los valores “reales” (Fc e y); todos ellos se
muestran en el apartado de Cálculos. Sobre los valores “reales” aparecerá automáticamente
uno de los siguientes casos: 0\<Md≤Mlim o Md>Mlim el primero indica que el esfuerzo es
inferior al Momento límite, y que por lo tanto la sección no requiere armadura mecánica
mínima a compresión; el segundo caso, determina que el esfuerzo es mayor al límite, y que por
lo tanto se deberá aumentar la armadura comprimida, AS2, para que el dimensionado de la
armadura de la sección sea el óptimo.

Manual de uso 11

<!-- p. 13 -->

Prontuario en Excel de Hormigón Armado (Adaptado a EHE-08)

Una vez determinados esos valores se facilitan tanto la armadura mecánica requerida como la
geométrica mínima de norma.
Armadura mecánica mínima Armadura geométrica mínima
AS1 11,85 cm² AS1 3,50 cm²
AS2 0,00 cm² AS2 1,05 cm²

La hoja de cálculo detecta cuáles son los valores más elevados, y los destaca en amarillo y
negrita. Dichos valores destacaos son los que utiliza en el último apartado, en que determina
cuántas barras se requerirían para cualquier diámetro y determina tanto la separación real
como la mínima. En caso de que ese conjunto de barras incumpliera, los resultados se verían
tachados en rojo, si cumplen, se destacarán en amarillo y negrita. Esto supone que se
reflejarán varios resultados aptos, y el usuario deberá determinar cuál es el óptimo.
AS1
ØS1 #barras AREAL SREAL SMIN
(mm) (ud) (cm²) (cm) (cm)

14 8 12,32 0,54 2,00
16 6 12,06 1,08 2,00
20 4 12,57 2,33 2,00
25 3 14,73 3,75 2,50
32 2 16,08 8,6 3,20
40 1 12,57 ― 4,00

Si todos los valores de la tabla aparecieran tachados, es decir, ninguno cumple las
separaciones mínimas que establece la normativa, aparecerá una anotación en la parte
superior de la tabla, que indica que se debe aumentar la sección.

COMPROBACIÓN

La introducción de los datos en la hoja de comprobación es similar a la descrita en el apartado
anterior, deberán introducirse características geométricas de la sección, características de los
materiales y esfuerzos de cálculo: recordemos que el momento flector deberá introducirse en
valor absoluto, pero es importante que el axil se introduzca con el signo adecuado (positivo
para las compresiones y negativo para las tracciones), siguiendo los criterios determinados por
la figura de la hoja.

El procedimiento utilizado para la obtención de los resultados de esta hoja se basa en la
aplicación de una hipótesis previa, que establece que ambas armaduras trabajan a su
capacidad mecánica y que se hallan en Dominio 2. Así se obtienen unos valores estimados, que
no se muestran dado que no siempre son reales. Estos valores estimados, son comparados con
los valores límite (que determinan el límite entre los dominios 3 y 4), estos últimos valores se
muestran en el apartado de Cálculos junto con los resultados de las capacidades mecánicas de
las armaduras.

En el apartado de Resultados, se muestran los valores de Fc, yREAL, MU‘, MU y NU. Los dos últimos
valores son obtenidos proporcionalmente a partir de MU’, Md y Nd, dado que MU’ no es el

Manual de uso 12

<!-- p. 14 -->

Prontuario en Excel de Hormigón Armado (Adaptado a EHE-08)

momento aplicado real, y se pretende darle al usuario una idea aproximada de los valores que
puede soportar la sección.

Resultados
DOMINIO 4
yreal 0,24 m
Fc 984,0 kN
Mu' 405,3 m·kN
Mu 405,3 m·kN
Nu 0,0 kN

En caso de que la armadura de la sección no fuera suficiente, es decir, que el MU fuera menor a
Md, el resultado se verá destacado en rojo. Independientemente del resultado, siempre
aparecerá una nota que ayudará a su interpretación y además facilitará información adicional.

Interpretación de resultados:
No cumple, insuficientes armaduras S1 y S2

Esta nota determinará si la sección cumple o no, y además le facilitará al usuario información
sobre el motivo de su incumplimiento: si es debido a AS1, a AS2 o a ambas. No se muestran
resultados numéricos dado que se trata de una comprobación. Para el correcto dimensionado
de las barras puede utilizarse tanto la hoja de comprobación mediante tanteo, como la hoja
anterior (de dimensionado).

Manual de uso 13

<!-- p. 15 -->

Prontuario en Excel de Hormigón Armado (Adaptado a EHE-08)

COMPROBACIÓN A FLEXOCOMPRESIÓN SIMÉTRICA U OBLICUA

Esta hoja de cálculo establece el lugar en que se sitúa el eje neutro de la pieza y los equilibrios
de fuerzas, utilizando como criterio que el axil sea igual al axil de cálculo.

En el apartado de Datos se solicitan las dimensiones de la sección, las características de los
materiales, los esfuerzos de cálculo y el armado.

Para determinar la armadura se solicitan tres datos: el diámetro, el número de barras en el
sentido del eje y y el número de barras en el sentido del eje x. Por las limitaciones que supone
el uso de Excel, se ha creado una lista desplegable, en lugar de permitir que el usuario
introduzca cualquier valor. En esta lista, el usuario puede escoger entre 2 y 8 barras en cada
sentido:

Para que sea más gráfico y sencillo para el usuario, y para que éste pueda estar seguro de
haber introducido correctamente los valores, se ha creado una gráfica de la sección, que se
modifica en función de los valores introducidos.

Así, si el usuario establece que en el sentido vertical hay 3 barras y en el horizontal hay 4,
aparecerá este dibujo:

Manual de uso 14

<!-- p. 16 -->

Prontuario en Excel de Hormigón Armado (Adaptado a EHE-08)

Si elige 5 barras horizontales y 2 verticales, aparecerá el siguiente gráfico:

Y así sucesivamente para todas las combinaciones posibles.

Como se puede observar, en los dos gráficos mostrados la línea del eje neutro es idéntica, esto
es debido a que para que la hoja calcule este resultado, debe utilizarse la aplicación Solver.
Para ello debe activarse esta opción en el Excel, dado que por defecto aparece desactivada en
la versión Microsoft Excel 2010. La activación de esta opción y el uso de la misma se muestra
en el Anejo de este mismo documento, denominado “Función Solver”.

Una vez se han hecho los cálculos podremos observar los resultados, se ha creado una tabla en
la que aparecen todas las armaduras con sus respectivas coordenadas, y se indica si están
traccionadas o comprimidas, cuál es el momento flector que resiste cada una de ellas y su
deformación unitaria.

En el apartado de resultados se muestran los equilibrios de esfuerzos, los valores para el
grafiado del eje neutro (su inclinación y ángulo) y una tabla con los vértices del eje neutro
(para que al usuario le resulte más sencillo determinar su grafiado si lo precisa).

Manual de uso 15

<!-- p. 17 -->

Prontuario en Excel de Hormigón Armado (Adaptado a EHE-08)

CORTANTE

Para la realización de los cálculos de esta hoja se han seguido escrupulosamente los
procedimientos establecidos en el Artículo 44 de la EHE-08. Por este motivo no se procederá a
su explicación detallada, en este apartado tan solo se explicará una relación de los datos a
introducir y una breve explicación sobre la interpretación de los cálculos y los resultados.

Tanto en las hojas de Dimensionado como de Comprobación se han realizado las
comprobaciones necesarias en cuanto a Momento de fisuración (MFIS), esfuerzo cortante de
agotamiento por compresión oblicua (VU1) y esfuerzo cortante de agotamiento por tracción en
el alma (VU2), y además se muestra la contribución tanto del hormigón (VCU) como de la
armadura (VSU) a la resistencia a esfuerzo cortante.

DIMENSIONADO

La introducción de datos y los cálculos de esta hoja pueden resultar un tanto complicados para
el usuario dado que exige la introducción de muchos datos aunque se ha intentado simplificar
al máximo.

En el primer apartado de la hoja se solicitan 4 tipos de datos:
\- Los relativos a la sección, son prácticamente idénticos a los de cualquier otra hoja del
aplicativo, aunque con un pequeño matiz: se solicita b0, que es el menor ancho
presente en la sección.
\- Características de los materiales.
\- Disposición de lar armaduras: es necesario que se introduzcan los datos de la
armadura longitudinal de la sección y los criterios de colocación de las armaduras
transversales. También se pueden introducir los valores de: St,cercos (separación entre
cercos) y #RAMAS (número de ramas); cuando el usuario quiera introducir estos datos
verá que puede escoger una serie de valores de una lista o escoger la opción ns/nc (no
sabe / no contesta), esto es así porque puede suponer que el usuario sepa de
antemano qué separaciones quiere que tengan los cercos o el número de ramas que le
conviene colocar, o puede ser que el usuario prefiera que estos datos se los facilite la
hoja de cálculo.
\- Esfuerzos de cálculo.

En el apartado de Cálculos se muestran dos columnas, en la primera aparecen todos los
factores y coeficientes utilizados, y en la segunda columna se muestran todas las
comprobaciones que exige la normativa. Para facilitar la interpretación de resultados se han
añadido anotaciones automáticas que determinan si la sección cumple o no, si fisura o no y si
requiere armadura transversal.

Con respecto a los Resultados también se muestran distintos valores que pese a no determinar
la armadura necesaria, se consideran importantes. Estos valores son las separaciones
transversales (entre ramas) máximas y mínimas establecidas por la normativa, y la separación
real (así se puede determinar si se cumple o no con la norma) y el área de armadura tanto
geométrica como mecánica (y del mismo modo que en el resto de hojas, se destacará el mayor
de los dos valores). A partir de estos valores, de los datos introducidos por el usuario y de los
cálculos realizados, se determinará el diámetro, número de ramas y separación transversal
entre cercos óptimos para la sección. En el caso de que el número de ramas o la separación

Manual de uso 16

<!-- p. 18 -->

Prontuario en Excel de Hormigón Armado (Adaptado a EHE-08)

entre cercos hayan sido determinados por el usuario, en estas casillas se repetirán dichos
valores.

COMPROBACIÓN

La introducción de datos de esta hoja es poco más extensa (aunque solo por 2 casillas) que la
del apartado anterior, se solicitan de igual modo los datos relativos a la sección, características
de los materiales, esfuerzos de cálculo y la disposición de las armaduras, una diferencia
esencial en la introducción de los datos es que en esta hoja el usuario es libre de poner
cualquier valor de separación transversal y de número de ramas.

En el apartado de Cálculos tan solo se muestran los valores de los coeficientes y los factores
utilizados para la obtención de VU1 y VU2. A diferencia del apartado anterior, estos cálculos no
se muestran en este apartado dado que son a la vez cálculos y comprobaciones del
cumplimiento de la sección.

Los resultados son, esencialmente, la interpretación de los valores de Momento de fisuración
(MFIS), esfuerzo cortante de agotamiento por compresión oblicua (VU1) y esfuerzo cortante de
agotamiento por tracción en el alma (VU2), diferenciando entre VCU y VSU. Para la interpretación
de estos resultados se han añadido anotaciones automáticas que determinan su cumplimiento
o no, si existe fisuración o no y si requiere armadura. Además se ha añadido un segundo
subapartado en el que aparece la interpretación sintetizada de todos los resultados.

Al tratarse de una comprobación, se indicará al usuario si existe algún error o incumplimiento
de la normativa en algún punto de los cálculos, y cual es este fallo, si bien no se facilitará un
valor de dimensionado óptimo, puesto que este puede depender de las preferencias del
usuario. El correcto dimensionado se puede realizar mediante la hoja de Dimensionado a
Cortante o mediante tanteo con la misma hoja de comprobación.

Manual de uso 17

<!-- p. 19 -->

Prontuario en Excel de Hormigón Armado (Adaptado a EHE-08)

TORSIÓN

Siguiendo los criterios establecidos por la normativa, se han realizado los cálculos para dos
tipos de secciones: secciones rectangulares y secciones huecas. En esencia, los cálculos para
ambos casos son los mismos, y tan solo varían algunos valores en la introducción de datos, y
algunas fórmulas posteriores dado que en las secciones huecas puede colocarse armadura en
la parte interior y en la exterior, cosa que no sucede en las secciones rectangulares; y que en el
caso de las secciones huecas es necesario determinar el espesor de la pared. Estas
diferenciaciones son sencillas, pero se ha preferido diferenciar estos dos casos en dos hojas,
para facilitar la introducción de datos y simplificar los cálculos.

La normativa establece el dimensionado a torsión pura, torsión combinada con flexión y axil y
torsión combinada con cortante. No se ha realizado la combinación de torsión con flexión y axil
dado que la normativa determina que «las armaduras longitudinales necesarias para torsión y
flexocompresión o flexotracción se calcularán por separado suponiendo la actuación de ambos
tipos de esfuerzo de forma independiente». Si bien todas las hojas admiten la introducción de
esfuerzo cortante. Si el usuario introduce este valor, la hoja de cálculo realizará la
comprobación establecida por la normativa; si, en cambio, el usuario establece que Vd=0, estos
cálculos no aparecerán.

DIMENSIONADO

Con respecto a la introducción de datos, en estas hojas se solicitan las dimensiones de la
sección, las características de los materiales, la disposición de las armaduras a torsión, los
esfuerzos de cálculo y el dimensionado de la armadura longitudinal comprimida. Es importante
remarcar, que la armadura longitudinal AS’ (o AS2 en otras hojas) no corresponde a la armadura
longitudinal mínima a torsión, sino que depende de la tensión generada por el axil, es decir, si
el valor del axil es 0, el dimensionado de AS’ no interfiere en los cálculos, dado que tan solo se
utiliza para la obtención del coeficiente K, pero si Nd>0 sí que será necesario.

En el apartado de cálculos se muestran las comprobaciones de los momentos torsores
máximos que pueden resistir las bielas comprimidas del hormigón (TU1), las armaduras
transversales (TU2) y las armaduras longitudinales (TU3).

La comprobación de las armaduras transversales y longitudinales, en el caso del dimensionado,
siempre cumplirán, dado que se obtienen del resultado del dimensionado, y siempre serán
iguales al esfuerzo torsor aplicado a la pieza. El único apartado que puede no cumplir es el que
depende de las dimensiones de la sección (del hormigón), en caso de no cumplir, aparecerá
una nota con el texto que se muestra en rojo a continuación:

M. torsores máximos que puede resistir
TU1 75,6 m·kN No cumple: Δ(b*h)
TU2 400,0 m·kN
TU3 400,0 m·kN Cumple
Esto significa que TU1 “no cumple”, por lo que se debe aumentar el área de hormigón (b*h).

Si el usuario determina que existe combinación con cortante, en el mismo apartado de
Cálculos aparecerá el apartado: Torsión combinada con cortante¸ donde se muestra el cálculo

Manual de uso 18

<!-- p. 20 -->

Prontuario en Excel de Hormigón Armado (Adaptado a EHE-08)

intermedio necesario (VU1) y el Cortante máximo que la pieza, en las condiciones marcadas por
el usuario, puede resistir. Pueden darse tres casos:

\- Vrd,MAX= Error : con los datos facilitados la sección no admite ningún cortante en
interacción con el momento torsor.
\- Vrd,MAX\<Vrd : la sección admite la aplicación de cortante, pero inferior al introducido.
\- Vrd,MAX≥Vrd : la sección cumple a interacción con cortante.

Torsión combinada con cortante
VU1 980,00 kN
Vrd,MAX Error kN No admite Cortante

La interpretación de estas tres posibilidades se verá destacada en ese mismo apartado,
mediante las frases: “No admite Cortante”, “No cumple” y “Cumple”.

Finalmente, en el apartado de Resultados se muestran la armadura transversal necesaria y la
separación entre cercos y el área total de armadura longitudinal mínima necesaria. Debajo de
estos resultados se muestran dos tablas, la primera muestra el diámetro de la armadura que
compone el/los cerco/s. En el caso de secciones rectangulares o secciones huecas en que solo
haya armadura en el perímetro exterior, tan solo aparecerá 1 cerco, en el caso de secciones
huecas con armadura en ambas caras de la sección, aparecerán 2 cercos.

La tabla de dimensionado de la armadura longitudinal establece los diámetros y números de
barras necesarios suponiendo que ambas armaduras fueran iguales. No es posible diferenciar
entre AS1 y AS2 (como en otras hojas) dado que no se solicita ningún momento flector de
cálculo.

COMPROBACIÓN

La hoja de comprobación a Torsión, resulta más sencilla que la de dimensionado, porque, pese
a que el usuario debe introducir algunos valores adicionales, se muestran menos resultados, y
además se han creado anotaciones automáticas que explican cada uno de los casos.

En el apartado de Datos el usuario debe facilitar las dimensiones de la sección, las
disposiciones de las armaduras longitudinales y transversales, las características de los
materiales y los esfuerzos de cálculo.

Puede suceder, que al introducir el valor de la separación transversal de los estribos éste valor
se torne rojo y aparezca la siguiente anotación: \<\<*El valor de st es mayor al establecido por
art.45.2.3>>. Esto quiere decir que el valor de la separación transversal es mayor al establecido
por la normativa, el usuario puede decidir mantener ese valor erróneo o modificarlo, pero si
no lo modifica repercutirá en los resultados finales (tal como se explica más adelante).

En el apartado de cálculos tan solo se muestran las características geométricas propias de la
sección, los coeficientes que se utilizan en los cálculos y, si existe cortante, los valores de
cálculo utilizados para la determinación del cortante máximo que puede resistir la pieza.

Manual de uso 19

<!-- p. 21 -->

Prontuario en Excel de Hormigón Armado (Adaptado a EHE-08)

Si no existe interacción con cortante, en el apartado de Resultados, tan solo se mostrarán los
momentos torsores máximos que pueden resistir el hormigón, las armaduras longitudinales y
las armaduras transversales, y un apartado de interpretación de resultados.

Junto a los valores de TU1, TU2 y TU3 aparecerán las notas “Cumple” o “No cumple”, que
llamarán la atención del usuario, haciéndole fácilmente visible los puntos en que falla la
sección. Y además el apartado de Interpretación de resultados le ayudará a comprender
porqué falla la sección. En este punto aparecerá una anotación automática que determinará si
la sección cumple en todos los puntos (p.e.: Cumple, el dimensionado es correcto) o si falla el
dimensionado de la sección o de alguna de sus armaduras (p.e.: No cumple, es necesario
aumentar la sección y la armadura transversal).

Puede suceder que en el apartado de Resultados el usuario se encuentre con el caso de que
junto al valor de TU2, aun siendo este mayor a Td, le aparezca la nota \<\<No cumple>>, esto es
debido a que el valor de st que ha introducido el usuario era superior al marcado por la
normativa, esto implica que la fórmula que establece TU2 no es correcta dado que, al
encontrarse los cercos demasiado separados, no trabajarán al 100% de su capacidad. En
consecuencia el Momento Torsor máximo (TU,MAX) que podrá resistir la pieza será menor a
cualquiera de los tres resultados previos (TU1, TU2 y TU3).

Momentos torsores máximos que puede resistir
TU1 48,0 m·kN Cumple
TU2 32,2 m·kN No cumple
TU3 67,0 m·kN Cumple
Torsor máximo que puede resistir:
TU,MAX 32,00 m·kN limitado por st,MAX = 6,00 cm

El valor de TU,MAX que se toma es 2/3·TU1, dado que se deduce que el acero no trabaja
correctamente y que es el hormigón por si solo el que deberá resistir la torsión.

Si existe cortante, además de los momentos torsores máximos que resisten el hormigón y las
armaduras, también aparece una tabla con el cortante máximo que admite la sección. Igual
que en el apartado de dimensionado, pueden darse tres casos, en lo que a cortante se refiere:

Vrd,MAX= Error : con los datos facilitados la sección no admite ningún cortante en interacción
con el momento torsor.

Vrd,MAX\<Vrd : la sección admite la aplicación de cortante, pero inferior al introducido.

Vrd,MAX≥Vrd : la sección cumple a interacción con cortante.

La interpretación de estas tres posibilidades se verá destacada en ese mismo apartado,
mediante las frases: “No admite Cortante”, “No cumple” y “Cumple”.

En este caso, la Interpretación de resultados puede determinar que:

“Cumple, el dimensionado es correcto” que significa que está correctamente dimensionada
tanto para torsión pura como para la interacción con cortante

Manual de uso 20

<!-- p. 22 -->

Prontuario en Excel de Hormigón Armado (Adaptado a EHE-08)

"El dimensionado es incorrecto" que implica que incumple al menos uno de los momentos
torsores máximos que puede resistir y que no admite cortante o que el cortante es mayor al
que la sección puede resistir.

"No cumple, es necesario aumentar [...]" que implica que pese a admitir la interacción con
cortante, no cumple alguno de los momentos torsores máximos que pueden resistir el
hormigón o las armaduras.

“La armadura transversal no cumple las separaciones de norma, Tu,max=2/3·Tu” el usuario
debe revisar el valor de st, dado que incumple normativa, y por lo tanto no se toman en cuenta
los demás cálculos.

Manual de uso 21

<!-- p. 23 -->

Prontuario en Excel de Hormigón Armado (Adaptado a EHE-08)

PUNZONAMIENTO

Para la utilización de esta hoja de cálculo es imprescindible el uso de su respectiva hoja de
simbología. Esto es debido a dos motivos: el primero es la gran cantidad de datos que el
usuario debe añadir, con cuyas siglas/simbología probablemente no esté muy habituado; y en
segundo lugar porque, dado que en la normativa utiliza en diversos apartados la misma
simbología para representar distintos valores, se han debido añadir subíndices que no
aparecen en la norma, y que por lo tanto el usuario no puede conocer.

En el apartado Datos, pese a su dimensión, el usuario no tiene que introducir demasiados
datos, tan solo las disposiciones relativas al soporte (pilar) y a la losa, las relativas a las
armaduras, las características de los materiales y el esfuerzo de cálculo. La mayor diferencia
entre esta hoja y las demás es que, en este apartado, aparecen ya algunos cálculos
intermedios.

Dado que los datos relativos a la las armaduras de punzonamiento pueden llevar a equívoco
por la similitud entre diversos datos, a continuación se explicará en qué consiste cada uno de
ellos, pese a estar definidos en el apartado de simbología citado anteriormente.

Disposición de las armaduras
α Ángulo de las armaduras con el eje de la pieza
smax Distancia máxima en dirección radial de los perímetros concéntricos de la armadura.
Distancia en dirección radial de los perímetros concéntricos de la armadura, utilizado para el
s
cálculo.
s1,min Distancia mínima en dirección radial entre el soporte y la primera línea de armaduras (0,5·d)
s1,max Distancia máxima en dirección radial entre el soporte y la primera línea de armaduras (0,5·d)
(user) Distancia en dirección radial entre el soporte y la primera línea de armaduras, escogida por el
s1
usuario.
bx2 Ancho del perímetro un,ef en x.
by2 Ancho del perímetro un,ef en y.
ρl Cuantía geométrica total de la armadura principal de la losa, dentro del perímetro un,ef*

Los datos de separaciones de las armaduras que debe introducir el usuario son s, que
corresponde a la separación entre los distintos perímetros de barras y s1 (user) que es la
separación entre el soporte y la primera línea de barras, sobre este valor aparecen s1,max y
s1,min, estos valores son los máximos y mínimos de norma, por lo que el usuario deberá facilitar
un valor intermedio entre ellos. Se ha introducido por defecto una fórmula que calcula la
media entre ambos, pero el usuario podrá modificarla a placer. Para evitar posibles errores en
la introducción de datos, las fórmulas vinculadas a s1 (user) estarán limitadas, de modo que si el
usuario introduce un s1 superior al máximo, las fórmulas tomaran como correcto el valor s1,max,
y si es inferior al mínimo tomarán como correcto el valor s1,min.

Con respecto al subapartado de esfuerzos de cálculo, se puede observar como no se solicita un
valor de Md, sino que tan solo se pide si existen o no momentos aplicados. Esto es así porque
es la única especificación que solicita la normativa, y se ha estimado más sencillo, porque el
usuario puede desconocer este dato exacto, pese a saber que existe un momento flector
aplicado.

Manual de uso 22

<!-- p. 24 -->

Prontuario en Excel de Hormigón Armado (Adaptado a EHE-08)

En el apartado de Cálculos y comprobaciones aparecen los coeficientes y valores que puedan
resultar de interés al usuario, y cuatro apartados de comprobaciones:

\- Comprobaciones para losas sin armadura de punzonamiento: este apartado
comprueba si es o no necesaria la armadura de punzonamiento. Además de aparecer
los valores de la tensión tangencial nominal de cálculo y la tensión máxima resistente
del perímetro crítico, se mostrará una interpretación de resultados.
\- Dimensionado de armadura transversal de punzonamiento: mostrará el área de
armadura requerida en cm2.
\- Comprobación de la zona exterior a la armadura de punzonamiento: su
incumplimiento determina la necesidad de añadir armadura de punzonamiento en la
zona exterior al perímetro crítico.
\- Comprobación de la limitación de la zona adyacente al soporte: corresponde a la
comprobación de que el esfuerzo máximo de punzonamiento cumple la limitación:
Fsd,ef/(u₀d)≤ 0,5*f1cd.

Manual de uso 23

<!-- p. 25 -->

Prontuario en Excel de Hormigón Armado (Adaptado a EHE-08)

RASANTE

La hoja de dimensionado a esfuerzo rasante en juntas entre hormigones, en el apartado de
Datos solicita disposiciones relativas a la sección, características de los materiales, disposición
de las armaduras y esfuerzos de cálculo.

En los esfuerzos de cálculo se solicita la variación de la resultante de los bloques de tensiones
normales, en lugar del axil de cálculo más habitual en otros apartados.

También se solicita la determinación de la rugosidad de la pieza, donde se puede escoger entre
tres casos:

\- Rugosidad alta.
\- Rugosidad alta con imbricación.
\- Rugosidad baja.
Se solicitan estos tres valores dado que en la comprobación de secciones sin armadura
transversal, el coeficiente β depende de esos tres factores.

En la comprobación de secciones con armadura transversal, el valor de β depende tan solo de
si la rugosidad es alta o baja, por lo que tanto la “rugosidad alta con imbricación” como la
“rugosidad alta” se considerarán simplemente “alta”. Debido a que β corresponde a dos
valores distintos en función de la comprobación que se realice, se ha establecido un
superíndice siendo: β1 el correspondiente a la comprobación SIN armadura transversal, y β² el
correspondiente a la comprobación con armadura transversal.

En el apartado de Cálculos se muestran las dos comprobaciones citadas y se determina su
cumplimiento o incumplimiento según establecen los artículos 47.2.1 y 47.2.2 de la EHE-08.

Armadura transversal Dimensionado de la armadura (para 1ml)
Ast,min 0,80 cm² #b,TOTAL 10,00 ud
Ast 12,30 cm² Øst 14,00 mm

Manual de uso 24

<!-- p. 26 -->

Prontuario en Excel de Hormigón Armado (Adaptado a EHE-08)

ANCLAJE DE ARMADURAS

Esta hoja se ha creado siguiendo el método simplificado establecido en el Artículo 69.5 de la
EHE-08.

Es un método muy sencillo, cuyos cálculos diferencian entre dos tipos de barras: las
certificadas y las no certificadas, por lo tanto es un dato que el usuario deberá especificar.

Para el cálculo de lb de las primeras se requieren el diámetro (Ø), y los límites elásticos del
hormigón y del acero (fyk y fck); para las no certificadas es necesario hallar la tensión de
adherencia (τbd) que depende de la resitencia a tracción de cálculo del hormigón (fctd) y del
diámetro.

Para establecer la lb,neta es necesario conocer dos valores más: β y As,mec/As,real; para obtenerlos
se requieren: el recubrimiento (c), As,mec, As,real y determinar el tipo de anclaje (patilla, gancho,
prolongación recta…).

Se ha creado un apartado denominado Factores y Coeficientes en el que se le facilitan al
usuario todos los valores necesarios para el cálculo de lb y de lb,neta. Estos valores no suelen
facilitarse, pero se ha considerado apropiado siguiendo con el carácter didáctico de todo el
proyecto.

En los Resultados se muestra una tabla con todas las longitudes de anclaje netas en función del
diámetro, de si éstas trabajan a compresión o a tracción o de su tipo de adherencia
(adherencia buena: Posición I, y adherencia deficiente: Posición II).

Certificada (cm)
lbnet
Ø TRACCION COMPRESIÓN
POS. I POS. II POS. I POS. II
6 15,00 15,00 15,00 20,20
8 15,00 20,00 18,85 26,93
10 23,57 33,67 23,57 33,67
12 28,28 40,40 28,28 40,40
14 33,00 47,14 33,00 47,14
16 37,71 53,87 37,71 53,87
20 47,14 67,34 47,14 67,34
25 58,92 84,17 58,92 84,17
32 75,42 107,74 75,42 107,74
40 94,27 134,67 94,27 134,67

Se muestra esta tabla por dos motivos: el primero es que se ha considerado más útil de cara a
su uso en cualquier tipo de proyecto y porque simplifica la introducción de datos. Si se
pretendiera dar un único resultado sería necesario que el usuario determinara tanto el tipo de
adherencia, como si se encuentran comprimidas o traccionadas y su diámetro.

Manual de uso 25

<!-- p. 27 -->

Prontuario en Excel de Hormigón Armado (Adaptado a EHE-08)

EMPALME POR SOLAPO

En una primera instancia se planteaba realizar el cálculo del empalme por solapo en la misma
hoja de cálculo que los anclajes, pero se ha considerado oportuno hacerlo por separado
porque, pese que algunos datos son idénticos, para estos cálculos es necesario conocer
muchos más datos que para el cálculo de los Anclajes.

Finalmente se ha creado una hoja en cuyo apartado de datos se solicita: las características de
los materiales (acero y hormigón) y las características de la armadura: diámetro, separaciones
entre empalmes, áreas mecánicas y reales, si se tratan de barras aisladas o grupos de barras, la
adherencia y si son o no certificadas.

Se ha creado un apartado de factores y coeficientes donde se muestran los valores de m y β.

Dado que se solicitan muchos datos, el apartado de Resultados se ve notablemente
simplificado. En este caso, como es necesario conocer tanto los valores de lb como de lb,neta
para la correcta disposición de los empalmes, se facilitan estos dos datos, junto con la longitud
de solapo (ls) y, en los casos en que es necesario, también se facilitan la separación entre
empalmes (semp) y la longitud de la barra suplementaria (lsupl).

Manual de uso 26

<!-- p. 28 -->

Prontuario en Excel de Hormigón Armado (Adaptado a EHE-08)

INESTABILIDAD DE SOPORTES (PANDEO)

Esta hoja sirve para la comprobación de soportes con respecto a su posible pandeo. Los
cálculos, se realizan siguiendo el Artículo 43 de la EHE.

Para una correcta introducción de los datos de esta hoja de cálculo, es imprescindible que el
usuario observe los esquemas de acciones y el esquema de barras que se facilitan, porque,
pese a que son unos datos aparentemente sencillos, son numerosos y además es bastante
habitual que haya errores al confundir los ejes de la estructura. El Excel tan solo calcula la
estructura bidimensionalmente, por lo tanto, si el usuario pretende calcular un pórtico
tridimensional deberá introducir los datos dos veces, una para cada sentido.

Los datos que se solicitan son: primero determinar si se trata de una estructura traslacional o
intraslacional (tal como se indica en la Figura 43.1.1 de la normativa), las características de los
materiales, los esfuerzos y las características de las barras que conforman el pórtico a
comprobar. De éstas barras se solicita su longitud L, y sus dimensiones b y h, teniendo en
cuenta que h es la paralela al eje y , y b es paralela al eje z. Estos datos se distinguen entre sí
por un subíndice (por ejemplo: AB) que determina de qué barra se trata.
E

x
Md,zA
D F
h A

b

C B G

x
H

y z

En el apartado Cálculos y Resultados se facilitan los factores utilizados para los cálculos, las
esbelteces de la pieza y su longitud de pandeo. Si el soporte no pandea, no aparece ningún
otro resultado y se muestra la nota “No pandea”, si pandea ésta nota se modifica “El soporte
pandea” y aparece una nueva lista de resultados con las excentricidades y esfuerzos de cálculo
en el eje Z. Estos esfuerzos establecen que el axil será igual y que el momento se verá
incrementado debido a la excentricidad generada por el pandeo del soporte.

Manual de uso 27

<!-- p. 29 -->

Prontuario en Excel de Hormigón Armado (Adaptado a EHE-08)

DEFORMACIÓN

Estas hojas de cálculo, siguen los procedimientos establecidos por el Artículo 50 de la EHE-08 y
por el Anejo 8, Apartados 2.2 y 2.3, que lo complementan. Pero antes, para la obtención de los
Momentos flectores máximos y las deformaciones máximas producidas por las acciones de las
barras, se han seguido las formulaciones del Prontuario Ensidesa y del Prontuario de
Estructuras del CEDEX.

Se ha creado un único documento para hablar de las Deformaciones, pese a que existen dos
hojas de cálculo, porque la diferencia entre ellas es ínfima de cara a su uso. Pese a que los
cálculos realizados difieren entre ambas, las necesidades de introducción de datos y los
resultados son tan semejantes que no merece la pena abrumar al usuario con dos apartados
que, en esencia, darán la misma información.

Dado que estas hojas “tan solo” pretenden darle al usuario los valores de Momentos flectores
máximos a los que está sometida la barra objeto de cálculo y las deformaciones máximas,
diferidas, totales y activas. Se ha simplificado al máximo la introducción de datos, si bien, como
utilizan una simbología poco habitual, y como en algunos casos concretos existen unas
limitaciones en la introducción de los valores de algunas cargas, no es de extrañar que sea
necesario consultar este manual al menos la primera vez que se utilice la hoja.

El procedimiento para utilizar esta hoja es el siguiente:

1º. Identificar el tipo de vano y de sistema estructural de la barra:

2º. Introducir las dimensiones de la sección y de la barra, las características de los materiales y
el armado. Una vez hecho esto puede ser recomendable dirigirse al apartado Cálculos Previos,
donde aparece la relación Luz/Canto, y determina si es necesario (según la Tabla 50.2.2.1.a de
la EHE-08) hacer la comprobación de las deformaciones.

3º. En el subapartado Acciones de Cálculo, el usuario deberá introducir los valores de las cargas
aplicadas en la barra. Se han distinguido entre cuatro tipos:

Manual de uso 28

<!-- p. 30 -->

Prontuario en Excel de Hormigón Armado (Adaptado a EHE-08)

qd P q
qi + M

g
L a b c d e f

\- Repartida trapezoidal de extremo a extremo de la barra: esta carga sirve tanto para
calcular cargas repartidas uniformes como triangulares.
\- Puntual
\- Momento flector aplicado
\- Repartida uniforme en un tramo de la barra.

Existe una limitación, y es que en las barras cuyos extremos son iguales (biapoyadas o
biempotradas) la carga repartida trapezoidal siempre debe cumplir que qi nunca puede ser
mayor a qd.

Para evitar posibles errores, a continuación se muestra una tabla con todos los tipos de cargas
y su posible distribución en función del tipo de vano.

Bi-empotrada

q i= qd q i = 0 q i\< qd

Apoyada-Empotrada

q i= qd q i> qd q i\< qd

q i = 0 qd= 0

Manual de uso 29

<!-- p. 31 -->

Prontuario en Excel de Hormigón Armado (Adaptado a EHE-08)

Bi-apoyada

q i= qd q i = 0 q i\< qd

Voladizo

q i= qd q i> qd q i\< qd

q i = 0 qd= 0

Una vez introducidos todos estos datos, la hoja calcula los momentos flectores máximos para
el descimbrado y en n días, este valor, que se muestra en el apartado de Resultados, sirve para
establecer los momentos de inercia que se utilizarán en el cálculo de las deformaciones.

El procedimiento es el siguiente: se compara el Momento Flector máximo con el Momento de
fisuración de la pieza. Si se establece que la pieza fisura, con estos dos datos, junto con el
momento de inercia bruto de la pieza, se calculará Ie (el Momento de Inercia Equivalente), que
será el utilizado para el cálculo de las deformaciones máximas. Si la pieza no fisura el Momento
de Inercia que se utiliza para el cálculo es Ib (Momento de Inercia Bruto).

Los valores de los Momentos de Inercia, se muestran en el apartado Cálculos Previos junto con
los Módulos de Deformación y algunos otros datos de interés como el Mf (Momento de
fisuración) y el módulo de deformación del acero.

Finalmente, en el apartado de Resultados, se muestran los Momentos Flectores máximos a los
que está sometida la barra y las deformaciones máximas generadas por las acciones. Junto a
estos valores se ha creado una pestaña desplegable donde se debe escoger la duración de las
cargas, para poder establecer el valor de λ, tal como establece el Artículo 50.2.2.3 de la
EHE-08.

Con este valor de calculan las flechas diferidas, y se pueden obtener, finalmente las flechas
total y activa de la barra.

Manual de uso 30

<!-- p. 32 -->

Prontuario en Excel de Hormigón Armado (Adaptado a EHE-08)

FISURACIÓN

Esta hoja de cálculo sirve para comprobar si un elemento fisura o no, y si la abertura
característica de sus fisuras superan las máximas determinadas por la normativa en la Tabla
5.1.1.2.

Para poder realizar esta comprobación será necesario que el usuario facilite las dimensiones
de la sección, las características de los materiales, si las acciones son directas o indirectas, las
características de la armadura principal a tracción y también deberá determinar el modo de
trabajo de la sección. Esto último sirve para obtener el área eficaz del hormigón (Ac,ef).

Para poder determinar Ac,ef se muestran cuatro figuras, que se han denominado Caso 1a, Caso
1b, Caso 2 y Caso 3. Estas figuras se han copiado de la Figura 49.2.4.b y se pueden escoger
mediante una pestaña desplegable situada en el subapartado “Area eficaz del hormigón”.

En el apartado de resultados, si se diera el improbable caso de que la sección no fisurara,
simplemente aparecería la nota “La sección no fisura”, en el caso de que si lo haga se mostrará
el valor de wk (abertura característica de la fisura) y un fragmento de la Tabla 5.1.1.2 de la
EHE-08.

En esta tabla se resaltarán en verde y con fondo amarillo los valores para los que la abertura
de la fisura cumple la normativa, y en rojo para los que no cumpla, del siguiente modo:

Abertura característica de la fisura
wk 0,30 mm

Abertura máxima de fisura
Clases de exposición wmáx [mm]
I 0,4
IIa, IIb, H 0,3
IIIa, IIIb,IV,F,Qa 0,2
IIIc, Qb, Qc 0,1

Manual de uso 31

<!-- p. 33 -->

Prontuario en Excel de Hormigón Armado (Adaptado a EHE-08)

C. SIMBOLOGÍA Y ARTICULADO

Manual de uso 32

<!-- p. 34 -->

Prontuario en Excel de Hormigón Armado (Adaptado a EHE-08)

FLEXIÓN SIMPLE – SECCIONES RECTANGULARES

DIMENSIONADO

Dimensiones de la sección Articulado EHE-08
h Canto
b Base
rMEC,INF Recubrimiento mecánico de la armadura inferior
37.2.4. (rec. nominal)
rMEC,SUP Recubrimiento mecánico de la armadura superior
d Canto útil: d=h-rMEC,INF

Características de los materiales
fyk Límite elástico característico del acero.
fck Límite elástico característico del hormigón.
T.M.A. Tamaño máximo del árido.
γs Coeficiente parcial de seguridad del acero.
Tabla 15.3
γc Coeficiente parcial de seguridad del hormigón.
αcc Factor de cansancio del hormigón. 39.4
fyd Resistencia de cálculo del acero (en armaduras pasivas) 38.3
fcd Resistencia de cálculo del hormigón. 39.4

Esfuerzos de cálculo
Md Momento flector de cálculo.

Diagrama rectangular 39.5
xLIM Eje que delimita MLIM, teniendo en cuenta Ɛcu y Ɛy 42.1.3
yLIM=λ(x)h Profundidad de aplicación de fuerzas de compresión límite
y Profundidad de aplicación de fuerzas de compresión.
FC,LIM Fuerza del hormigón comprimido límite.
Fc Fuerza del hormigón comprimido (Fc=η(x)·fcd· λ(x)h
MLIM Momento flector límite.

Armadura mecánica mínima
AS1 Armadura principal (inferior) a tracción.
AS2 Armadura secundaria (a compresión) superior.

Resultados, Dimensionado de la armadura.
ØS Diámetro de la armadura. 32.2
\#barras Número de barras.
AREAL Área real de acero.
SREAL Separación nominal real entre las barras.
SMIN Separación mínima de norma entre barras. 69.4.1.1

Manual de uso 33

<!-- p. 35 -->

Prontuario en Excel de Hormigón Armado (Adaptado a EHE-08)

COMPROBACIÓN

Dimensiones de la sección Articulado EHE-08
h Canto
b Base
rMEC,INF Recubrimiento mecánico de la armadura inferior
37.2.4. (rec. nominal)
rMEC,SUP Recubrimiento mecánico de la armadura superior
d Canto útil: d=h-rMEC,INF

Características de los materiales
fyk Límite elástico característico del acero.
fck Límite elástico característico del hormigón.
T.M.A. Tamaño máximo del árido.
γs Coeficiente parcial de seguridad del acero.
Tabla 15.3
γc Coeficiente parcial de seguridad del hormigón.
αcc Factor de cansancio del hormigón. 39.4
fyd Resistencia de cálculo del acero (en armaduras pasivas) 38.3
fcd Resistencia de cálculo del hormigón. 39.4

Disposición de las armaduras
\#bS1 Número de barras de la armadura principal a tracción.
ØS1 Diámetro de las barras de la armadura principal a tracción.
AS1 Área total de armadura traccionada.
\#bS2 Número de barras de la armadura sec. a compresión.
ØS2 Diámetro de las barras de la armadura sec. a compresión.
AS2 Área total de la armadura comprimida

Esfuerzos de cálculo
Md Momento flector de cálculo.

Cálculos previos
US1 Capacidad mecánica de la armadura traccionada.
US2 Capacidad mecánica de la armadura comprimida

Diagrama rectangular 39.5
xLIM Eje que delimita MLIM, teniendo en cuenta Ɛcu y Ɛy 42.1.3
yLIM=λ(x)h Profundidad de aplicación de fuerzas de compresión límite
MLIM Momento flector límite.

Resultados, Dimensionado de la armadura.
YREAL Profundidad de aplicación de fuerzas real. 32.2
Fc Fuerza del hormigón comprimido (Fc=η(x)·fcd· λ(x)h
MU Momento último que resiste la pieza.

Manual de uso 34

<!-- p. 36 -->

Prontuario en Excel de Hormigón Armado (Adaptado a EHE-08)

FLEXIÓN SIMPLE – SECCIONES EN T

DIMENSIONADO

Dimensiones de la sección Articulado EHE-08
hALA Canto del ala.
hALMA Canto del alma
bALA Base del ala.
bALMA Base del alma.
rMEC,INF Recubrimiento mecánico de la armadura inferior
37.2.4. (rec. nominal)
rMEC,SUP Recubrimiento mecánico de la armadura superior
d Canto útil: d=h-rMEC,INF

Características de los materiales
fyk Límite elástico característico del acero.
fck Límite elástico característico del hormigón.
T.M.A. Tamaño máximo del árido.
γs Coeficiente parcial de seguridad del acero. 15.3
γc Coeficiente parcial de seguridad del hormigón.
αcc Factor de cansancio del hormigón. 39.4
fyd Resistencia de cálculo del acero (en armaduras pasivas) 38.3
fcd Resistencia de cálculo del hormigón. 39.4

Esfuerzos de cálculo
Md Momento flector de cálculo.

Diagrama rectangular 39.5
xLIM Eje que delimita MLIM, teniendo en cuenta Ɛcu y Ɛy 42.1.3
yLIM=λ(x)h Profundidad de aplicación de fuerzas de compresión límite
y Profundidad de aplicación de fuerzas de compresión.
FC,LIM Fuerza del hormigón comprimido límite.
Fc Fuerza del hormigón comprimido (Fc=η(x)·fcd· λ(x)h
MLIM Momento flector límite.

Armadura mecánica mínima
AS1 Armadura principal (inferior) a tracción.
AS2 Armadura secundaria (a compresión) superior.

Resultados, Dimensionado de la armadura.
ØS Diámetro de la armadura. 32.2
\#barras Número de barras.
AREAL Área real de acero.
SREAL Separación nominal real entre las barras.
SMIN Separación mínima de norma entre barras. 69.4.1.1

Manual de uso 35

<!-- p. 37 -->

Prontuario en Excel de Hormigón Armado (Adaptado a EHE-08)

COMPROBACIÓN

Dimensiones de la sección Articulado EHE-08
hALA Canto del ala.
hALMA Canto del alma
bALA Base del ala.
bALMA Base del alma.
rMEC,INF Recubrimiento mecánico de la armadura inferior
37.2.4. (rec. nominal)
rMEC,SUP Recubrimiento mecánico de la armadura superior
d Canto útil: d=h-rMEC,INF

Características de los materiales
fyk Límite elástico característico del acero.
fck Límite elástico característico del hormigón.
T.M.A. Tamaño máximo del árido.
γs Coeficiente parcial de seguridad del acero.
Tabla 15.3
γc Coeficiente parcial de seguridad del hormigón.
αcc Factor de cansancio del hormigón. 39.4
fyd Resistencia de cálculo del acero (en armaduras pasivas) 38.3
fcd Resistencia de cálculo del hormigón. 39.4

Disposición de las armaduras
\#bS1 Número de barras de la armadura principal a tracción.
ØS1 Diámetro de las barras de la armadura principal a tracción.
AS1 Área total de armadura traccionada.
\#bS2 Número de barras de la armadura sec. a compresión.
ØS2 Diámetro de las barras de la armadura sec. a compresión.
AS2 Área total de la armadura comprimida

Esfuerzos de cálculo
Md Momento flector de cálculo.

Cálculos previos
US1 Capacidad mecánica de la armadura traccionada.
US2 Capacidad mecánica de la armadura comprimida

Diagrama rectangular 39.5
xLIM Eje que delimita MLIM, teniendo en cuenta Ɛcu y Ɛy 42.1.3
yLIM=λ(x)h Profundidad de aplicación de fuerzas de compresión límite
yest Profundidad de aplicación de fuerzas de compresión.
MLIM Momento flector límite.
MU Momento último que resiste la pieza.

Armadura mecánica mínima
AS1 Armadura principal (inferior) a tracción.
AS2 Armadura secundaria (a compresión) superior.

Resultados, Dimensionado de la armadura.
ØS Diámetro de la armadura. 32.2
\#barras Número de barras.
AREAL Área real de acero.
SREAL Separación nominal real entre las barras.
SMIN Separación mínima de norma entre barras. 69.4.1.1

Manual de uso 36

<!-- p. 38 -->

Prontuario en Excel de Hormigón Armado (Adaptado a EHE-08)

FLEXIÓN COMPUESTA – SECCIONES RECTANGULARES

DIMENSIONADO

Dimensiones de la sección Articulado EHE-08
h Canto
b Base
rMEC,INF Recubrimiento mecánico de la armadura inferior 37.2.4. (rec. nominal)
rMEC,SUP Recubrimiento mecánico de la armadura superior
d Canto útil: d=h-rMEC,INF

Características de los materiales
fyk Límite elástico característico del acero.
fck Límite elástico característico del hormigón.
T.M.A. Tamaño máximo del árido.
γs Coeficiente parcial de seguridad del acero.
Tabla 15.3
γc Coeficiente parcial de seguridad del hormigón.
αcc Factor de cansancio del hormigón. 39.4
fyd Resistencia de cálculo del acero (en armaduras pasivas) 38.3
fcd Resistencia de cálculo del hormigón. 39.4

Esfuerzos de cálculo
Md Momento flector de cálculo.
Nd Axil de cálculo.
Md’ Momento flector de cálculo (Transformación de Ehlers)

Diagrama rectangular 39.5
xLIM Eje que delimita MLIM, teniendo en cuenta Ɛcu y Ɛy 42.1.3
yLIM=λ(x)h Profundidad de aplicación de fuerzas de compresión límite
y Profundidad de aplicación de fuerzas de compresión.
FC,LIM Fuerza del hormigón comprimido límite.
Fc Fuerza del hormigón comprimido (Fc=η(x)·fcd· λ(x)h
MLIM Momento flector límite.

Armadura mecánica mínima
AS1 Armadura principal (inferior) a tracción.
AS2 Armadura secundaria (a compresión) superior.

Resultados, Dimensionado de la armadura.
ØS Diámetro de la armadura. 32.2
\#barras Número de barras.
AREAL Área real de acero.
SREAL Separación nominal real entre las barras.
SMIN Separación mínima de norma entre barras. 69.4.1.1

Manual de uso 37

<!-- p. 39 -->

Prontuario en Excel de Hormigón Armado (Adaptado a EHE-08)

COMPROBACIÓN

Dimensiones de la sección Articulado EHE-08
h Canto
b Base
rMEC,INF Recubrimiento mecánico de la armadura inferior
37.2.4. (rec. nominal)
rMEC,SUP Recubrimiento mecánico de la armadura superior
d Canto útil: d=h-rMEC,INF

Características de los materiales
fyk Límite elástico característico del acero.
fck Límite elástico característico del hormigón.
T.M.A. Tamaño máximo del árido.
γs Coeficiente parcial de seguridad del acero.
Tabla 15.3
γc Coeficiente parcial de seguridad del hormigón.
αcc Factor de cansancio del hormigón. 39.4
fyd Resistencia de cálculo del acero (en armaduras pasivas) 38.3
fcd Resistencia de cálculo del hormigón. 39.4

Disposición de las armaduras
\#bS1 Número de barras de la armadura principal a tracción.
ØS1 Diámetro de las barras de la armadura principal a tracción.
AS1 Área total de armadura traccionada.
\#bS2 Número de barras de la armadura sec. a compresión.
ØS2 Diámetro de las barras de la armadura sec. a compresión.
AS2 Área total de la armadura comprimida

Esfuerzos de cálculo
Md Momento flector de cálculo.
Nd Axil de cálculo.
Md’ Momento flector de cálculo (Transformación de Ehlers)

Cálculos previos
US1 Capacidad mecánica de la armadura traccionada.
US2 Capacidad mecánica de la armadura comprimida

Diagrama rectangular 39.5
xLIM Eje que delimita MLIM, teniendo en cuenta Ɛcu y Ɛy 42.1.3
yLIM=λ(x)h Profundidad de aplicación de fuerzas de compresión límite
MLIM Momento flector límite.
FcLIM Fuerza del hormigón comprimido límite

Resultados, Dimensionado de la armadura.
YREAL Profundidad de aplicación de fuerzas real. 32.2
Fc Fuerza del hormigón comprimido (Fc=η(x)·fcd· λ(x)h
MU’ Momento último Ehlers que resiste la pieza.
MU Momento último estimado que resiste la pieza.
NU Axil último estimado que resiste la pieza.

Manual de uso 38

<!-- p. 40 -->

Prontuario en Excel de Hormigón Armado (Adaptado a EHE-08)

FLEXIÓN COMPUESTA- SECCIONES EN T

DIMENSIONADO

Dimensiones de la sección Articulado EHE-08
hALA Canto del ala.
hALMA Canto del alma
bALA Base del ala.
bALMA Base del alma.
rMEC,INF Recubrimiento mecánico de la armadura inferior
37.2.4. (rec. nominal)
rMEC,SUP Recubrimiento mecánico de la armadura superior
d Canto útil: d=h-rMEC,INF

Características de los materiales
fyk Límite elástico característico del acero.
fck Límite elástico característico del hormigón.
T.M.A. Tamaño máximo del árido.
γs Coeficiente parcial de seguridad del acero. 15.3
γc Coeficiente parcial de seguridad del hormigón.
αcc Factor de cansancio del hormigón. 39.4
fyd Resistencia de cálculo del acero (en armaduras pasivas) 38.3
fcd Resistencia de cálculo del hormigón. 39.4

Esfuerzos de cálculo
Md Momento flector de cálculo.
Nd Axil de cálculo.
Md’ Momento flector de cálculo (Transformación de Ehlers)

Diagrama rectangular 39.5
xLIM Eje que delimita MLIM, teniendo en cuenta Ɛcu y Ɛy 42.1.3
yLIM=λ(x)h Profundidad de aplicación de fuerzas de compresión límite
y Profundidad de aplicación de fuerzas de compresión.
FC,LIM Fuerza del hormigón comprimido límite.
Fc Fuerza del hormigón comprimido (Fc=η(x)·fcd· λ(x)h
MLIM Momento flector límite.

Armadura mecánica mínima
AS1 Armadura principal (inferior) a tracción.
AS2 Armadura secundaria (a compresión) superior.

Resultados, Dimensionado de la armadura.
ØS Diámetro de la armadura. 32.2
\#barras Número de barras.
AREAL Área real de acero.
SREAL Separación nominal real entre las barras.
SMIN Separación mínima de norma entre barras. 69.4.1.1

Manual de uso 39

<!-- p. 41 -->

Prontuario en Excel de Hormigón Armado (Adaptado a EHE-08)

COMPROBACIÓN

Dimensiones de la sección Articulado EHE-08
hALA Canto del ala.
hALMA Canto del alma
bALA Base del ala.
bALMA Base del alma.
rMEC,INF Recubrimiento mecánico de la armadura inferior
37.2.4. (rec. nominal)
rMEC,SUP Recubrimiento mecánico de la armadura superior
d Canto útil: d=h-rMEC,INF

Características de los materiales
fyk Límite elástico característico del acero.
fck Límite elástico característico del hormigón.
T.M.A. Tamaño máximo del árido.
γs Coeficiente parcial de seguridad del acero.
Tabla 15.3
γc Coeficiente parcial de seguridad del hormigón.
αcc Factor de cansancio del hormigón. 39.4
fyd Resistencia de cálculo del acero (en armaduras pasivas) 38.3
fcd Resistencia de cálculo del hormigón. 39.4

Disposición de las armaduras
\#bS1 Número de barras de la armadura principal a tracción.
ØS1 Diámetro de las barras de la armadura principal a tracción.
AS1 Área total de armadura traccionada.
\#bS2 Número de barras de la armadura sec. a compresión.
ØS2 Diámetro de las barras de la armadura sec. a compresión.
AS2 Área total de la armadura comprimida

Esfuerzos de cálculo
Md Momento flector de cálculo.
Nd Axil de cálculo.
Md’ Momento flector de cálculo (Transformación de Ehlers)

Cálculos previos
US1 Capacidad mecánica de la armadura traccionada.
US2 Capacidad mecánica de la armadura comprimida
MMAX,ALA Momento máximo del ala

Diagrama rectangular 39.5
xLIM Eje que delimita MLIM, teniendo en cuenta Ɛcu y Ɛy 42.1.3
yLIM=λ(x)h Profundidad de aplicación de fuerzas de compresión límite
FC,LIM Fuerza del hormigón comprimido límite.
MLIM Momento flector límite.

Resultados, Dimensionado de la armadura.
YREAL Profundidad de aplicación de fuerzas real. 32.2
Fc Fuerza del hormigón comprimido (Fc=η(x)·fcd· λ(x)h
MU’ Momento último Ehlers que resiste la pieza.
MU Momento último estimado que resiste la pieza.
NU Axil último estimado que resiste la pieza.

Manual de uso 40

<!-- p. 42 -->

Prontuario en Excel de Hormigón Armado (Adaptado a EHE-08)

FLEXOCOMPRESIÓN SIMÉTRICA O ESVIADA

Dimensiones de la sección Articulado EHE-08
b Base.
h Canto
rH Recubrimiento horizontal.
rV Recubrimiento vertical.

Características de los materiales
fck Límite elástico característico del hormigón.
fyk Límite elástico característico del acero.
γc Coeficiente parcial de seguridad del hormigón.
Tabla 15.3
γs Coeficiente parcial de seguridad del acero.
fy,cd Resistencia de cálculo del acero a compresión 38.3

Esfuerzos de cálculo
Nd Axil de cálculo.
My,d Momento flector de cálculo en eje y
Mx,d Momento flector de cálculo en eje x

Resultados de acero
εs Deformación del acero.

Resultados del hormigón
h Canto total.
d Canto útil total
x Eje neutro
y Bloque de compresiones
xcdg Coord. X centro de gravedad
ycdg Coord. Y centro de gravedad

Solver
φ Ángulo eje neutro.
ξ Profundidad eje neutro

Manual de uso 41

<!-- p. 43 -->

Prontuario en Excel de Hormigón Armado (Adaptado a EHE-08)

CORTANTE

DIMENSIONADO

Dimensiones de la sección Articulado EHE-08
h Canto
b0 Anchura neta mínima del elemento 40.3.5
rMEC,INF Recubrimiento mecánico de la armadura inferior 37.2.4. (rec. nominal)
rMEC,SUP Recubrimiento mecánico de la armadura superior
d Canto útil: d=h-rMEC,INF

Características de los materiales
fyk Límite elástico característico del acero.
fyα,k Límite elástico característico de la armadura transversal
fck Límite elástico característico del hormigón.
fcv Resistencia efectiva del hormigón a cortante 44.2.3.2.2
T.M.A. Tamaño máximo del árido.
γs Coeficiente parcial de seguridad del acero.
Tabla 15.3
γc Coeficiente parcial de seguridad del hormigón.
αcc Factor de cansancio del hormigón. 39.4
fyd Resistencia de cálculo del acero (en armaduras pasivas) 38.3
fyα,d Resistencia de cálculo de la armadura transversal 44.2.3.2.2
fcd Resistencia de cálculo del hormigón. 39.4
Es Módulo de elasticidad del acero 38.4

Disposición de las armaduras
\#bS' Número de barras de la armadura a compresión.
ØS' Diámetro de barras de la armadura a compresión.
AS' Área total de la sección de la armadura comprimida.
\#bS Número de barras de la armadura a tracción
ØS Diámetro de barras de la armadura a tracción.
AS Área total de la sección de la armadura traccionada.
θt Ángulo entre bielas de compresión y el eje de la pieza 44.2.3.1
αt Ángulo entre las armaduras y el eje de la pieza 44.2.3.1
St,cercos Separación entre cercos
\#RAMAS Número de ramas

Esfuerzos de cálculo
Vrd Esfuerzo cortante efectivo de cálculo. 44.2.2
Nd Axil de cálculo.
Md Momento flector de cálculo

Relativos a los materiales
f1cd Resistencia a compresión del hormigón 44.2.3.1
fct,k Resistencia característica del hormigón a tracción 39.1
fct,d Resistencia de cálculo a tracción del hormigón
fct,m Resistencia media del hormigón a tracción 39.1

Relativos a los esfuerzos
K Coeficiente que depende del esfuerzo axil. 44.2.3.1
σ'cd Tensión axil efectiva en el hormigón (compresión positiva) 44.2.3.1

Manual de uso 42

<!-- p. 44 -->

Prontuario en Excel de Hormigón Armado (Adaptado a EHE-08)

Relativos a la sección
Iz Momento de inercia de la sección transversal. 44.2.3.2.1.1.
S Momento estático de la sección transversal 4.2.3.2.1.1.
ξ Coeficiente adimensional 44.2.3.2.1.2
Cuantía geométrica de la armadura longitudinal principal
ρl 44.2.3.2.1.2
de tracción.
θe Ángulo de referencia de inclinación de las fisuras 44.2.3.2.2.
β Coeficiente adimensional 44.2.3.2.2.

Armadura mecánica mínima
AS1 Armadura principal (inferior) a tracción.
AS2 Armadura secundaria (a compresión) superior.

Agotamiento por compresión oblicua del alma
Esfuerzo cortante de agotamiento por compresión oblicua
VU1 44.2.3.1.
en el alma.

Agotamiento por tracción del alma
Esfuerzo cortante de agotamiento por compresión oblicua
Mfis 44.2.3.1.
en el alma.
VU2 Esfuerzo cortante de agotamiento por tracción en el alma 44.2.3.2
Contribución del hormigón a la resistencia a esfuerzo
VCU 44.2.3.2.2
cortante
Contribución de la armadura transversal de alma a la
VSU 44.2.3.2.2
resistencia a esfuerzo cortante

Armadura transversal
Aα,mec Área de la armadura transversal.
Área de la armadura transversal geométrica mínima
Aα,geom
normalizada.
St,trans MAX Separación entre cercos máxima.
St,trans MIN Separación entre cercos mínima.
St,trans REAL Separación entre cercos real.

Dimensionado de la armadura
ØS,t Diámetro de los cercos.
\#ramas Número de ramas
st,cercos Separación entre cercos

Manual de uso 43

<!-- p. 45 -->

Prontuario en Excel de Hormigón Armado (Adaptado a EHE-08)

COMPROBACION

Dimensiones de la sección Articulado EHE-08
h Canto
b0 Anchura neta mínima del elemento 40.3.5
rMEC,INF Recubrimiento mecánico de la armadura inferior 37.2.4. (rec. nominal)
rMEC,SUP Recubrimiento mecánico de la armadura superior
d Canto útil: d=h-rMEC,INF

Características de los materiales
fyk Límite elástico característico del acero.
fyα,k Límite elástico característico de la armadura transversal
fck Límite elástico característico del hormigón.
fcv Resistencia efectiva del hormigón a cortante 44.2.3.2.2
T.M.A. Tamaño máximo del árido.
γs Coeficiente parcial de seguridad del acero.
Tabla 15.3
γc Coeficiente parcial de seguridad del hormigón.
αcc Factor de cansancio del hormigón. 39.4
fyd Resistencia de cálculo del acero (en armaduras pasivas) 38.3
fyα,d Resistencia de cálculo de la armadura transversal 44.2.3.2.2
fcd Resistencia de cálculo del hormigón. 39.4
Es Módulo de elasticidad del acero 38.4

Disposición de las armaduras
\#bS' Número de barras de la armadura a compresión.
ØS' Diámetro de barras de la armadura a compresión.
AS' Área total de la sección de la armadura comprimida.
\#bS Número de barras de la armadura a tracción
ØS Diámetro de barras de la armadura a tracción.
AS Área total de la sección de la armadura traccionada.
θt Ángulo entre bielas de compresión y el eje de la pieza 44.2.3.1
αt Ángulo entre las armaduras y el eje de la pieza 44.2.3.1
St,cercos Separación entre cercos
\#RAMAS Número de ramas

Esfuerzos de cálculo
Vrd Esfuerzo cortante efectivo de cálculo. 44.2.2
Nd Axil de cálculo.
Md Momento flector de cálculo

Relativos a los materiales
f1cd Resistencia a compresión del hormigón 44.2.3.1
fct,k Resistencia característica del hormigón a tracción 39.1
fct,d Resistencia de cálculo a tracción del hormigón
fct,m Resistencia media del hormigón a tracción 39.1

Relativos a los esfuerzos
K Coeficiente que depende del esfuerzo axil. 44.2.3.1
σ'cd Tensión axil efectiva en el hormigón (compresión positiva) 44.2.3.1

Manual de uso 44

<!-- p. 46 -->

Prontuario en Excel de Hormigón Armado (Adaptado a EHE-08)

Relativos a la sección
Iz Momento de inercia de la sección transversal. 44.2.3.2.1.1.
S Momento estático de la sección transversal 4.2.3.2.1.1.
ξ Coeficiente adimensional 44.2.3.2.1.2
Cuantía geométrica de la armadura longitudinal principal
ρl 44.2.3.2.1.2
de tracción.
θe Ángulo de referencia de inclinación de las fisuras 44.2.3.2.2.
β Coeficiente adimensional 44.2.3.2.2.
z Brazo mecánico 44.2.3.2.2

Cortante que la sección puede resistir
Esfuerzo cortante de agotamiento por compresión oblicua
Mfis 44.2.3.1.
en el alma.
Esfuerzo cortante de agotamiento por compresión oblicua
VU1 44.2.3.1.
en el alma.
VU2 Esfuerzo cortante de agotamiento por tracción en el alma 44.2.3.2
Contribución del hormigón a la resistencia a esfuerzo
VCU 44.2.3.2.2
cortante
Contribución de la armadura transversal de alma a la
VSU 44.2.3.2.2
resistencia a esfuerzo cortante

Manual de uso 45

<!-- p. 47 -->

Prontuario en Excel de Hormigón Armado (Adaptado a EHE-08)

TORSIÓN – SECCIONES RECTANGULARES

DIMENSIONADO

Dimensiones de la sección Articulado EHE-08
h Canto
b Base
rMEC,INF Recubrimiento mecánico de la armadura inferior 37.2.4. (rec. nominal)
rMEC,SUP Recubrimiento mecánico de la armadura superior
d Canto útil: d=h-rMEC,INF

Características de los materiales
fyk Límite elástico característico del acero.
fck Límite elástico característico del hormigón.
T.M.A. Tamaño máximo del árido.
γs Coeficiente parcial de seguridad del acero.
Tabla 15.3
γc Coeficiente parcial de seguridad del hormigón.
αcc Factor de cansancio del hormigón. 39.4
fyd Resistencia de cálculo del acero (en armaduras pasivas) 38.3
f1cd Resistencia a compresión del hormigón. 45.2.2.1

Disposición de la armadura a torsión
θt Ángulo entre bielas de compresión y eje de la pieza.
αt

Armadura longitudinal a compresión
\#bS' Número de barras de armadura longitudinal a compresión.
ØS' Diámetro de la armadura longitudinal a compresión.
AS' Área de la armadura longitudinal a compresión

Esfuerzos de cálculo
Nd Áxil de cálculo.
Td Momento torsor de cálculo en la sección. 45.2.2
Vrd Esfuerzo cortante de cálculo efectivo

Coeficientes
K Coeficiente que depende del esfuerzo axil. 44.2.3.1
α Coeficiente adimensional. 45.2.2.1
β Coeficiente adimensional 45.3.2.2

Características de la sección
he Espesor eficaz de la pared de la sección de cálculo. 45.2.1
Área encerrada por la línea media de la sección hueca
Ae 45.2.1
eficaz de cálculo.
Perímetro de la línea media de la sección hueca eficaz de
ue 45.2.1
cálculo

Manual de uso 46

<!-- p. 48 -->

Prontuario en Excel de Hormigón Armado (Adaptado a EHE-08)

M. torsores máximos que puede resistir
Máximo momento torsor que pueden resistir las bielas
TU1 45.2.2.1
comprimidas de hormigón.
Máximo momento torsor que pueden resistir las
TU2 45.2.2.2
armaduras transversales.
Máximo momento torsor que pueden resistir las
TU3 45.2.2.3
armaduras longitudinales

Torsión combinada con cortante
Esfuerzo cortante de agotamiento por compresión oblicua
VU1 44.2.3.1.
en el alma.
Vrd,MAX Esfuerzo cortante efectivo de cálculo máximo. 44.2.2

Armadura transversal a torsión
At Área de la armadura transversal a torsión.
St Separación de la armadura transversal a torsión.
ØSt Diametro de la armadura transversal a torsión
\#cercos Número de cercos

Armadura transversal a torsión
Al,MIN Área de la armadura longitudinal mínima.
Sl Separación de la armadura longitudinal a torsión.
ØSl Diametro de la armadura longitudinal a torsión
\#barras Número de barras

Manual de uso 47

<!-- p. 49 -->

Prontuario en Excel de Hormigón Armado (Adaptado a EHE-08)

COMPROBACIÓN

Dimensiones de la sección Articulado EHE-08
h Canto
b Base
rMEC,INF Recubrimiento mecánico de la armadura inferior 37.2.4. (rec. nominal)
rMEC,SUP Recubrimiento mecánico de la armadura superior
d Canto útil: d=h-rMEC,INF

Disposición de las armaduras
\#bS' Número de barras de la armadura a compresión.
ØS' Diámetro de barras de la armadura a compresión.
\#bS Número de barras de la armadura a tracción
ØS Diámetro de barras de la armadura a tracción.
ØSt Diámetro de los cercos.
St Distancia entre cercos
At Área total de la sección de cada rama de cercos.
θt Ángulo entre bielas de compresión y eje de la pieza. 44.2.3.1
αt Ángulo entre las armaduras y el eje de la pieza 44.2.3.1

Características de los materiales
fyk Límite elástico característico del acero.
fck Límite elástico característico del hormigón.
T.M.A. Tamaño máximo del árido.
γs Coeficiente parcial de seguridad del acero.
Tabla 15.3
γc Coeficiente parcial de seguridad del hormigón.
αcc Factor de cansancio del hormigón. 39.4
fyd Resistencia de cálculo del acero (en armaduras pasivas) 38.3
fcd Resistencia de cálculo del hormigón. 39.4
f1cd Resistencia a compresión del hormigón. 45.2.2.1

Esfuerzos de cálculo
Nd Axil de cálculo.
Td Momento torsor de cálculo en la sección. 45.2.2
Vrd Esfuerzo cortante de cálculo efectivo

Características de la sección
he Espesor eficaz de la pared de la sección de cálculo. 45.2.1
Área encerrada por la línea media de la sección hueca
Ae 45.2.1
eficaz de cálculo.
Perímetro de la línea media de la sección hueca eficaz de
ue 45.2.1
cálculo

Torsión combinada con cortante
Esfuerzo cortante de agotamiento por compresión oblicua
VU1 44.2.3.1.
en el alma.

Coeficientes
K Coeficiente que depende del esfuerzo axil. 44.2.3.1
α Coeficiente adimensional. 45.2.2.1
β Coeficiente adimensional 45.3.2.2

Manual de uso 48

<!-- p. 50 -->

Prontuario en Excel de Hormigón Armado (Adaptado a EHE-08)

M. torsores máximos que puede resistir
Máximo momento torsor que pueden resistir las bielas
TU1 45.2.2.1
comprimidas de hormigón.
Máximo momento torsor que pueden resistir las
TU2 45.2.2.2
armaduras transversales.
Máximo momento torsor que pueden resistir las
TU3 45.2.2.3
armaduras longitudinales

Cortante máximo que puede resistir
Vrd,MAX Esfuerzo cortante efectivo de cálculo máximo. 44.2.2

Manual de uso 49

<!-- p. 51 -->

Prontuario en Excel de Hormigón Armado (Adaptado a EHE-08)

TORSIÓN – SECCIONES HUECAS

DIMENSIONADO

Dimensiones de la sección Articulado EHE-08
h Canto
b Base
h0 Espesor real de la pared
rMEC,INF Recubrimiento mecánico de la armadura inferior 37.2.4. (rec. nominal)
rMEC,SUP Recubrimiento mecánico de la armadura superior
d Canto útil: d=h-rMEC,INF

Características de los materiales
fyk Límite elástico característico del acero.
fck Límite elástico característico del hormigón.
T.M.A. Tamaño máximo del árido.
γs Coeficiente parcial de seguridad del acero.
Tabla 15.3
γc Coeficiente parcial de seguridad del hormigón.
αcc Factor de cansancio del hormigón. 39.4
fyd Resistencia de cálculo del acero (en armaduras pasivas) 38.3
fcd Resistencia de cálculo del hormigón. 39.4
f1cd Resistencia a compresión del hormigón. 45.2.2.1

Esfuerzos de cálculo
Nd Axil de cálculo.
Td Momento torsor de cálculo en la sección. 45.2.2
Vrd Esfuerzo cortante de cálculo efectivo

Disposición de la armadura a torsión
θt Ángulo entre bielas de compresión y eje de la pieza. 44.2.3.1
αt Ángulo entre las armaduras y el eje de la pieza 44.2.3.1

Armadura longitudinal a compresión
\#bS' Número de barras de armadura longitudinal a compresión.
ØS' Diámetro de la armadura longitudinal a compresión.
AS' Área de la armadura longitudinal a compresión

Características de la sección
he Espesor eficaz de la pared de la sección de cálculo. 45.2.1
Área encerrada por la línea media de la sección hueca
Ae 45.2.1
eficaz de cálculo.
Perímetro de la línea media de la sección hueca eficaz de
ue 45.2.1
cálculo

Coeficientes
K Coeficiente que depende del esfuerzo axil. 44.2.3.1
α Coeficiente adimensional. 45.2.2.1
β Coeficiente adimensional 45.3.2.2

Manual de uso 50

<!-- p. 52 -->

Prontuario en Excel de Hormigón Armado (Adaptado a EHE-08)

M. torsores máximos que puede resistir
Máximo momento torsor que pueden resistir las bielas
TU1 45.2.2.1
comprimidas de hormigón.
Máximo momento torsor que pueden resistir las
TU2 45.2.2.2
armaduras transversales.
Máximo momento torsor que pueden resistir las
TU3 45.2.2.3
armaduras longitudinales

Torsión combinada con cortante
Esfuerzo cortante de agotamiento por compresión oblicua
VU1 44.2.3.1.
en el alma.
Vrd,MAX Esfuerzo cortante efectivo de cálculo máximo. 44.2.2

Armadura transversal a torsión
At Área de la armadura transversal a torsión.
St Separación de la armadura transversal a torsión.
ØSt Diámetro de la armadura transversal a torsión
\#cercos Número de cercos

Armadura longitudinal
Al, Área de la armadura longitudinal.
ØSl Diámetro de la armadura longitudinal a torsión
\#barras Número de barras

Manual de uso 51

<!-- p. 53 -->

Prontuario en Excel de Hormigón Armado (Adaptado a EHE-08)

COMPROBACIÓN

Dimensiones de la sección Articulado EHE-08
h Canto
b Base
h0 Espesor real de la pared
rMEC,INF Recubrimiento mecánico de la armadura inferior 37.2.4. (rec. nominal)
rMEC,SUP Recubrimiento mecánico de la armadura superior
d Canto útil: d=h-rMEC,INF

Disposición de las armaduras
\#bS' Número de barras de la armadura a compresión.
ØS' Diámetro de barras de la armadura a compresión.
\#bS Número de barras de la armadura a tracción
ØS Diámetro de barras de la armadura a tracción.
AL Área total de la sección de la armadura longitudinal.
ØSt Diámetro de los cercos.
St Distancia entre cercos
At Área total de la sección de cada rama de cercos.
θt Ángulo entre bielas de compresión y eje de la pieza. 44.2.3.1
αt Ángulo entre las armaduras y el eje de la pieza 44.2.3.1

Esfuerzos de cálculo
Nd Axil de cálculo.
Td Momento torsor de cálculo en la sección. 45.2.2
Vrd Esfuerzo cortante de cálculo efectivo

Características de los materiales
fyk Límite elástico característico del acero.
fck Límite elástico característico del hormigón.
T.M.A. Tamaño máximo del árido.
γs Coeficiente parcial de seguridad del acero.
Tabla 15.3
γc Coeficiente parcial de seguridad del hormigón.
αcc Factor de cansancio del hormigón. 39.4
fyd Resistencia de cálculo del acero (en armaduras pasivas) 38.3
fcd Resistencia de cálculo del hormigón. 39.4
f1cd Resistencia a compresión del hormigón. 45.2.2.1

Características relativas a la sección
he Espesor eficaz de la pared de la sección de cálculo. 45.2.1
Área encerrada por la línea media de la sección hueca
Ae 45.2.1
eficaz de cálculo.
Perímetro de la línea media de la sección hueca eficaz de
ue 45.2.1
cálculo

Interacción con cortante
Esfuerzo cortante de agotamiento por compresión oblicua
VU1 44.2.3.1.
en el alma.

Manual de uso 52

<!-- p. 54 -->

Prontuario en Excel de Hormigón Armado (Adaptado a EHE-08)

Coeficientes
K Coeficiente que depende del esfuerzo axil. 44.2.3.1
α Coeficiente adimensional. 45.2.2.1
β Coeficiente adimensional 45.3.2.2
M. torsores máximos que puede resistir
Máximo momento torsor que pueden resistir las bielas
TU1 45.2.2.1
comprimidas de hormigón.
Máximo momento torsor que pueden resistir las
TU2 45.2.2.2
armaduras transversales.
Máximo momento torsor que pueden resistir las
TU3 45.2.2.3
armaduras longitudinales

Cortante máximo que puede resistir
Vrd,MAX Esfuerzo cortante efectivo de cálculo máximo. 44.2.2

Manual de uso 53

<!-- p. 55 -->

Prontuario en Excel de Hormigón Armado (Adaptado a EHE-08)

PUNZONAMITENTO

Disposiciones relativas al soporte Articulado EHE-08
c₁ (x) Canto del soporte en el eje de las x Figura 46.2.a, b y c
c₂ (y) Canto del soporte en el eje de las y
Menor distancia entre el borde del soporte y el del
lx
hormigón en el eje de las x.
Menor distancia entre el borde del soporte y el del
ly
hormigón en el eje de las y.

Disposiciones relativas a la losa
h Canto de la losa
rmec,inf Recubrimiento mecánico de la armadura inferior 37.2.4. (rec. nominal)
d Canto útil de la losa
u₁ Perímetro crítico Figura 46.2.d y e
bx1 Ancho del perímetro crítico en x. Figura 46.2.a, b y c (1)
Ax Área definida por el lado bx y el canto. 46.3
by1 Ancho del perímetro crítico en y. Figura 46.2.a, b y c (1)
Ay Área definida por el lado by y el canto. 46.3

Características de los materiales
fck Límite elástico característico del hormigón. Tabla 15.3
γc Coeficiente parcial de seguridad del hormigón.
fcd Resistencia de cálculo del hormigón. 39.4
f1cd Resistencia a compresión del hormigón. 46.3
fcv Resistencia efectiva del hormigón a cortante.
Límite elástico característico de la armadura de
fyα,k
punzonamiento.
γs Coeficiente parcial de seguridad del acero. Tabla 15.3
fyα,d Resistencia de cálculo del acero.

Disposición de las armaduras
α Ángulo de las armaduras con el eje de la pieza
Distancia máxima en dirección radial de los perímetros
smax
concéntricos de la armadura.
Distancia en dirección radial de los perímetros
s
concéntricos de la armadura, utilizado para el cálculo.
Distancia mínima en dirección radial entre el soporte y la
s1,min Figura 46.5.b
primera línea de armaduras (0,5·d)
Distancia máxima en dirección radial entre el soporte y la
s1,max Figura 46.5.b
primera línea de armaduras (0,5·d)
(user) Distancia en dirección radial entre el soporte y la primera
s1
línea de armaduras, escogida por el usuario.
bx2 Ancho del perímetro un,ef en x. (2)
Figura 46.5.a
by2 Ancho del perímetro un,ef en y.
Cuantía geométrica total de la armadura principal de la
ρl
losa, dentro del perímetro un,ef*

Manual de uso 54

<!-- p. 56 -->

Prontuario en Excel de Hormigón Armado (Adaptado a EHE-08)

Esfuerzos de cálculo Artículo 46.3
Fsd Esfuerzo de punzonamiento de cálculo
Fuerzas longitudinales en la superficie crítica procedentes
Nd,x , Nd,y
de una carga.
Md Momento transferido entre losa y soporte

Coeficientes
β Coeficiente según la excentricidad 46.3
ξ Coeficiente adimensional 46.3

Otros valores de interés
σ'cd Tensión axial media en la sup. crítica de comprobación 46.3
un,ef Perímetro continente de la armadura de punzonamiento Figura 46.5.a
u₀ Perímetro de comprobación Figura 46.4.3
τrd¹ Tensión resistente del perímetro crítico
46.3
τrd²,min Valor mínimo de la tensión resistente del perímetro crítico

Comprobaciones para losas sin armadura de punzonamiento 46.3
τsd Tensión tangencial nominal de cálculo
Tensión máxima resistente del perímetro crítico (la mayor
τrd
entre τrd¹ y τrd²,min )

Dimensionado de armadura transversal de punzonamiento
Área total de armadura de punzonamiento en un
Asw 46.4.1
perímetro concéntrico al soporte o área de carga.

Comprobación de la zona exterior a la a. de punzonamiento 46.4.2
Fsd,ef Esfuerzo efectivo de punzonamiento
Fext Esfuerzo de punzonamiento del perímetro exterior.

(1) (2) Se han tenido que añadir los subíndices 1 y 2 para distinguir ambos valores entre sí, dado
que la normativa utiliza la misma nomenclatura para ambos pese a ser distintos.

\* Equivalente a la raíz cuadrada de la armadura en x y la armadura en y, con un valor máximo
de 2‰.

Manual de uso 55

<!-- p. 57 -->

Prontuario en Excel de Hormigón Armado (Adaptado a EHE-08)

DIMENSIONADO A RASANTE - SECCIONES RECTANGULARES

Dimensiones de la sección Articulado EHE-08
h Canto
b Base
p Superficie de contacto por unidad de longitud

Características de los materiales
fck Límite elástico característico del hormigón.
γs Coeficiente parcial de seguridad del acero.
Tabla 15.3
γc Coeficiente parcial de seguridad del hormigón.
αcc Factor de cansancio del hormigón. 39.4
fcd Resistencia de cálculo del hormigón. 39.4
fct,d Resistencia de cálculo a tracción del hormigón
fyα,d Resistencia de cálculo de la armadura transversal 44.2.3.2.2

Disposición de la armadura a torsión
s Separación entre cercos
α Ángulo entre las armaduras y el eje de la pieza 44.2.3.1

Esfuerzos de cálculo
Variación de la resultante de los bloques de tensiones
ΔC o ΔT
normales (en Compresión o Tracción)
σcd Tensión externa de cálculo normal al plano de la junta

Coeficientes
Coeficiente adimensional para cálculo sin armadura β1 47.2.2.2
transversal.
Coeficiente adimensional para cálculo con armadura β2 47.2.2.2
transversal.
μ Coeficiente adimensional 47.2.2.2

Cálculos previos
τr,d Tensión rasante de cálculo 47.1

Comprobación en secciones sin armadura transversal
τr,u Tensión rasante de agotamiento 47.2.1 o 47.2.2

Armadura transversal
Ast,min Área de los cercos mínima.
Ast Área de los cercos.

Dimensionado de la armadura (para 1ml)
\#b,TOTAL Número total de cercos en 1 metro lineal
ØSt Diámetro de los cercos

Manual de uso 56

<!-- p. 58 -->

Prontuario en Excel de Hormigón Armado (Adaptado a EHE-08)

ANCLAJE DE BARRAS O MALLAS

Características de los materiales
fck Límite elástico característico del hormigón.
γs Coeficiente parcial de seguridad del acero.
Tabla 15.3
γc Coeficiente parcial de seguridad del hormigón.
αcc Factor de cansancio del hormigón. 39.4
fcd Resistencia de cálculo del hormigón. 39.4
fct,d Resistencia de cálculo a tracción del hormigón
fyd Resistencia de cálculo del acero (en armaduras pasivas) 38.3

Características de las barras
Ø Diámetro de la barra.
c1 Recubrimiento geométrico
As,mec. Área de la armadura mecánica.
As,real Armadura real a partir de la cual se ancla la armadura.
τbd Tensión de adherencia constante 69.5.1.2

Longitud básica de anclaje
lb Longitud básica de anclaje. 69.5.1.2

Longitud neta de anclaje
lb,neta Longitud básica de anclaje. 69.5.1.2

Manual de uso 57

<!-- p. 59 -->

Prontuario en Excel de Hormigón Armado (Adaptado a EHE-08)

ANCLAJE POR SOLAPO

Características de los materiales Articulado EHE-08
fck Límite elástico característico del hormigón.
γc Coeficiente parcial de seguridad del hormigón.
fct,d Resistencia a tracción de cálculo del hormigón. 39.4 , 39.1
fyk Límite elástico característico del acero.
γs Coeficiente parcial de seguridad del acero. 15.3
fyd Resistencia de cálculo del acero (en armaduras pasivas)

Características de las barras
Ø Diámetro de las barras a solapar.
a Separación entre empalmes más próximos Figura 69.5.2.2
AS,mec.tot Armadura mecánica de cálculo total.
AS1,real Área de acero sometida normalmente a tracción
AS2,real Area de acero sometida normalmente a compresión.
As,real Area de acero total real
%As,tracc. Porcentaje de armadura traccionada.
τbd Tensión de adherencia 69.5.1.2

Longitud básica de anclaje
lb Longitud básica de anclaje 69.5.1.2

Longitud neta de anclaje
lb,neta Longitud neta de anclaje 69.5.1.2, 69.5.1.4

Longitud de solapo
ls Longitud de solapo 69.5.2.2
lsupl Longitud de la barra suplementaria
69.5.2.3
Sempalmes Separación entre empalmes

Manual de uso 58

<!-- p. 60 -->

Prontuario en Excel de Hormigón Armado (Adaptado a EHE-08)

INESTABILIDAD DE SOPORTES

Datos del pórtico EHE-08 Artículos
bAB Base de la sección del pilar A-B
hAB Altura de la sección del pilar A-B
LAB Longitud del pilar A-B
dAB' Recubrimiento mecánico de la armadura inferior
d Canto útil: d=h- dAB'
Ac Área de la sección del pilar A-B
IAB,z Momento de inercia en eje z para pilar A-B

Datos de la viga
bDA Base de la sección de la viga D-A
hDA Altura de la sección de la viga D-A
LDA Longitud de la viga D-A
IDA,z Momento de inercia en eje z de la viga D-A

Caracteristica de los materiales
fck Límite elástico característico del hormigón.
γc Coeficiente parcial de seguridad del hormigón.
fcd Resistencia de cálculo del hormigón. 39.4
fyk Límite elástico característico del acero.
γs Coeficiente parcial de seguridad del acero. 15.3
fyd Resistencia de cálculo del acero (armadura pasiva) 38.3
εy Deformación del acero para fyd 43.5.1
E Módulo de elasticidad del acero 38.4

Esfuerzos de cálculo
Md,z A Momento flector de cálculo en pilar A
Md,z B Momento flector de cálculo en pilar B
Nd Axil de cálculo.

Factores y coeficientes
ψA Coeficiente relativo a las rigideces en el extremo A 43.4
ψB Coeficiente relativo a las rigideces en el extremo A 43.4
Excentricidad de primer orden en el extremo del soporte
43.1.2
e₁ con mayor momento.
Excentricidad de primer orden en el extremo del soporte
43.1.2
e₂ con menor momento.
υ Axil adimensional 43.1.2
C Coeficiente que depende de la disposición de armaduras 43.1.2
β Factor de armado 43.5.1

Esbelteces
λinf Esbeltez límite inferior 43.1.2
λmec Esbeltez mecánica 43.1.1

Longitud de pandeo
α Factor para la longitude de pandeo 43.4
l₀ Longitud de pandeo 43.4

Manual de uso 59

<!-- p. 61 -->

Prontuario en Excel de Hormigón Armado (Adaptado a EHE-08)

DEFORMACIONES

SECCIONES RECTANGULARES

Dimensiones de la sección Articulado EHE-08
L Luz
hc Canto
bc Base
rinf Recubrimiento mecánico inferior de las armaduras 37.2.4.
dc Canto útil

Características de los materiales
fck Límite elástico característico del hormigón.
fctm,fl Resistencia media a flexotracción del hormigón 39.1
fyk Límite elástico característico del acero.
γs Coeficiente parcial de seguridad del acero. 15.3
fyd Resistencia de cálculo del acero (armadura pasiva) 38.3

Disposición de las armaduras
\#bS1 Número de barras de la armadura traccionada.
ØS1 Diámetro de la armadura sometida a tracción.
AS1 Área total de la armadura traccionada.
\#bS2 Número de barras de la armadura comprimida.
ØS2 Diámetro de la armadura sometida a compresión
AS2 Aárea total de la armadura comprimida.
ρS,TOTAL Cuantía geométrica total de acero en tanto por mil.

Acciones: iniciales (descimbrado) / a los n días.
qizq (i)/(n) Valor de la carga repartida en el extremo izquierdo
qder(i)/(n) Valor de la carga repartida en el extremo derecho
P(i)/(n) Carga puntual
Distancia entre el extremo derecho de la barra y la carga
a puntual
Distancia entre la carga puntual y el extremo izquierdo de
b la barra
M(i)/(n) Momento flector aplicado.
Distancia entre el extremo derecho de la barra y el
c momento flector
Distancia entre el momento flector y el extremo izquierdo
d de la barra
Carga uniformemente repartida que ocupa un tramo de la
q(i)/(n) barra
Distancia entre el extremo derecho de la barra y el centro
e de la carga uniformemente repartida.
Distancia entre el centro de la carga uniformemente
f repartida y el extremo izquierdo de la barra
g Ancho del tramo afectado por la carga uniforme.

Comprobación previa:
L/d Relación luz/canto útil
Relación L/d mínimo para no requerir comprobación de
L/d * *Tabla 50.2.2.1.a
deformaciones

Manual de uso 60

<!-- p. 62 -->

Prontuario en Excel de Hormigón Armado (Adaptado a EHE-08)

Cálculos previos: descimbrado y n días
Es Módulo de deformación del acero 38.4
Mf Momento nominal de fisuración 50.2.2.2
X/d Profundidad relativa de la fibra neutra Anejo 8 art.2.2
Ib Momento de inercia bruta
If Momento de inercia de la sección fisurada Anejo 8 art.2.2

Inercias y módulos de deformación
Ec(i)/(n) Módulo de deformación del hormigón 39.6
Ie(i)/(n) Momento de inercia equivalente 50.2.2.2
I(i)/(n) Momento de inercia utilizado para el cálculo (Ib o Ie)

Esfuerzos y deformaciones máximos
MMAXi Momento flector máximo en el descimbrado.
finsti Flecha instantánea en el descimbrado
MMAXn Momento flector máximo a los n días
finstn Flecha instantánea máxima a los n días

Factor λ (cálculo de fdif) 50.2.2.3
λ Factor para el cálculo de la flecha diferida
ξ Coeficiente en función de la duración de la carga
ρ' Cuantía geométrica de la armadura a compresión

Cálculo de las flechas totales y activas 50.2.2.3
fdifi Flecha diferida de las cargas de descimbrado.
fdifn Flecha diferida de las cargas a los n días.
ftoti Flecha total de las cargas de descimbrado.
ftotn Flecha total de las cargas a los n días.
fACTIVA Flecha activa.

Manual de uso 61

<!-- p. 63 -->

Prontuario en Excel de Hormigón Armado (Adaptado a EHE-08)

SECCIONES EN T

Dimensiones de la sección Articulado EHE-08
L Luz
hALA Canto del ala
hALMA Canto del alma
bALA Base del ala
bALMA Base del alma
rinf Recubrimiento mecánico inferior de las armaduras 37.2.4.
dc Canto útil

Características de los materiales
fck Límite elástico característico del hormigón.
fctm,fl Resistencia media a flexotracción del hormigón 39.1
fyk Límite elástico característico del acero.
γs Coeficiente parcial de seguridad del acero. 15.3
fyd Resistencia de cálculo del acero (armadura pasiva) 38.3

Disposición de las armaduras
\#bS1 Número de barras de la armadura traccionada.
ØS1 Diámetro de la armadura sometida a tracción.
AS1 Área total de la armadura traccionada.
\#bS2 Número de barras de la armadura comprimida.
ØS2 Diámetro de la armadura sometida a compresión
AS2 Aárea total de la armadura comprimida.
ρS,TOTAL Cuantía geométrica total de acero en tanto por mil.

Acciones: iniciales (descimbrado) / a los n días.
qizq (i)/(n) Valor de la carga repartida en el extremo izquierdo
qder(i)/(n) Valor de la carga repartida en el extremo derecho
P(i)/(n) Carga puntual
Distancia entre el extremo derecho de la barra y la carga
a puntual
Distancia entre la carga puntual y el extremo izquierdo de
b la barra
M(i)/(n) Momento flector aplicado.
Distancia entre el extremo derecho de la barra y el
c momento flector
Distancia entre el momento flector y el extremo izquierdo
d de la barra
Carga uniformemente repartida que ocupa un tramo de la
q(i)/(n) barra
Distancia entre el extremo derecho de la barra y el centro
e de la carga uniformemente repartida.
Distancia entre el centro de la carga uniformemente
f repartida y el extremo izquierdo de la barra
g Ancho del tramo afectado por la carga uniforme.

Comprobación previa:
L/d Relación luz/canto útil
Relación L/d mínimo para no requerir comprobación de
L/d * *Tabla 50.2.2.1.a
deformaciones

Manual de uso 62

<!-- p. 64 -->

Prontuario en Excel de Hormigón Armado (Adaptado a EHE-08)

Cálculos previos: descimbrado y n días
Es Módulo de deformación del acero 38.4
Mf Momento nominal de fisuración 50.2.2.2
X/d Profundidad relativa de la fibra neutra Anejo 8 art.2.2 y 2.3
Ib Momento de inercia bruta
If Momento de inercia de la sección fisurada Anejo 8 art.2.2 y 2.3

Inercias y módulos de deformación
Ec(i)/(n) Módulo de deformación del hormigón 39.6
Ie(i)/(n) Momento de inercia equivalente 50.2.2.2
I(i)/(n) Momento de inercia utilizado para el cálculo (Ib o Ie)

Esfuerzos y deformaciones máximos
MMAXi Momento flector máximo en el descimbrado.
finsti Flecha instantánea en el descimbrado
MMAXn Momento flector máximo a los n días
finstn Flecha instantánea máxima a los n días

Factor λ (cálculo de fdif) 50.2.2.3
λ Factor para el cálculo de la flecha diferida
ξ Coeficiente en función de la duración de la carga
ρ' Cuantía geométrica de la armadura a compresión

Cálculo de las flechas totales y activas 50.2.2.3
fdifi Flecha diferida de las cargas de descimbrado.
fdifn Flecha diferida de las cargas a los n días.
ftoti Flecha total de las cargas de descimbrado.
ftotn Flecha total de las cargas a los n días.
fACTIVA Flecha activa.

Manual de uso 63

<!-- p. 65 -->

Prontuario en Excel de Hormigón Armado (Adaptado a EHE-08)

FISURACIÓN

Dimensiones de la sección EHE-08 Artículos
hc Canto de la sección
bc Ancho de la sección
c Recubrimiento mecánico de la armadura inferior.
d Canto util: d= hc - c

Armadura principal a tracción
ØS Diametro de la armadura
\#bS Número de barras
S Distancia entre barras
As Area total de la armadura

Caracteristcas de los materiales
fck,j Resistencia característica del hormigón para j dias 49.2.1
fctm,fl Resistencia media a flexotracción del hormigón 39.1
Coeficiente en función de las acciones (indirectas o otros
49.2.4
β casos)

Esfuerzos de cáculo
Nd Axil de cálculo.
Md Momento de cálculo

Calculos
Mf Momento de fisuración. 50.2.2.2
σs Tensión de servicio de la armadura. 49.2.4
σsr Tensión de la armadura en la sección fisurada. 49.2.4
sm Separación media de fisuras 49.2.4
εsm Alargamiento medio de las armaduras 49.2.4

Manual de uso 64

<!-- p. 66 -->

Prontuario en Excel de Hormigón Armado (Adaptado a EHE-08)

ANEJO 1. CÁLCULO DE ARMADURAS

Simbologia EHE-08 Artículos
Øs Diámetro de las barras
\#barras Numero de barras
bc Ancho de la sección de hormigón
hc Canto de la sección de hormigón
As Área total de la armadura
Ac Área total de la sección de hormigón
ρl Cuantía geométrica en tanto por mil

Manual de uso 65

<!-- p. 67 -->

Prontuario en Excel de Hormigón Armado (Adaptado a EHE-08)

D. ANEJO

Manual de uso 66

<!-- p. 68 -->

Prontuario en Excel de Hormigón Armado (Adaptado a EHE-08)

TUTORIALES DE EXCEL

FUNCIÓN SOLVER

Para resolución de alguna de la hoja de Flexo-compresión, será necesario aplicar la función
solver, puesto que algunos cálculos no se efectúan automáticamente. Es un procedimiento
muy sencillo, pero es habitual que en Excel 2007 o 2010 la función solver (o solve ) esté oculta.
De modo que, para poder acceder a ella, deberemos proceder del siguiente modo:

Primero clicamos sobre la pestaña “Archivo”, apareciendo una lista de opciones en el lado
izquierdo de la pantalla.

Deberemos clicar en el apartado “Opciones de Excel”, que hará que se abra una ventana. Y se
elige la opción “Complementos”.

En la parte inferior de la ventana que se abre, aparece la palabra Administrar y junto a ella una
lista desplegable:

Manual de uso 67

<!-- p. 69 -->

Prontuario en Excel de Hormigón Armado (Adaptado a EHE-08)

Debe seleccionarse la opción “Complementos de Excel” y pulsar Ir…

Llegados a este punto, se selecciona la opción □Solver y se pulsa Aceptar.

Si se está utilizando Excel 2007, puede suceder que el ordenador solicite permiso para la
instalación de este complemento, se debe aceptar la instalación.

Una vez realizado todo este procedimiento, la opción solver ya será visible. Se encontrará en la
pestaña Datos en el subapartado denominado Análisis.

Al clicar la opción Solver se abrirá una ventana, en la que no se deberá modificar nada, tan solo
clicar el botón Resolver.

Manual de uso 68

<!-- p. 70 -->

Prontuario en Excel de Hormigón Armado (Adaptado a EHE-08)

A continuación se abre una ventana en la que podemos seleccionar diversas opciones, por
defecto aparece marcado Conservar solución de Solver, por lo que se debe Aceptar (si no
saliera marcada esta opción por defecto, deberá seleccionarse).

Seguidamente, se podrá observar como se modifican los datos del apartado de Resultados de
la hoja de cálculo y cómo cambia el grafiado del eje neutro.

Manual de uso 69

<!-- p. 71 -->

Prontuario en Excel de Hormigón Armado (Adaptado a EHE-08)

Manual de uso 70
