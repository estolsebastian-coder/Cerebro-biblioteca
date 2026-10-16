---
type: libro
title: "Parte2"
author: "lauri"
categoria: "ESTRUCTURA"
paginas: 34
extraccion: "texto"
fuente: "local:E:/MATERIAL DE CONSULTA/ESTRUCTURA/BIELAS Y TIRANTES/Parte2.pdf"
convertido: 2026-10-16
---

# Parte2

> Texto extraído de `ESTRUCTURA\BIELAS Y TIRANTES\Parte2.pdf` (34 páginas, texto). El PDF original está en el disco E: (MATERIAL DE CONSULTA); `<!-- p. N -->` marca el inicio de cada página.

<!-- p. 1 -->

Parte 2

Derivación de modelos de bielas y tirantes para el Código ACI 2002

James G. MacGregor

Sinopsis

Este trabajo documenta las decisiones tomadas por el Comité ACI 318 para introducir los
modelos de bielas y tirantes en el Código ACI 2002. Las Secciones 3 y 4 de este trabajo
repasan el contenido del código referente a los modelos de bielas y tirantes. En la Sección
5 se presentan los formatos y valores de la resistencia efectiva a la compresión de las
bielas. El primer paso fue derivar una resistencia efectiva a la compresión con la cual,
usando el Apéndice A, se obtuviera la misma sección transversal y resistencia requeridas
por otros códigos para la misma resistencia del hormigón y las mismas cargas no
factoreadas. Para la selección final de los valores de diseño de la resistencia efectiva a la
compresión se consideraron resultados de ensayo, valores de diseño de otra bibliografía,
valores de otros códigos y las resistencias de diseño del Código ACI para situaciones de
esfuerzos similares. En la Sección 6 del trabajo se resume una derivación similar de las
resistencias efectivas a la compresión de las zonas nodales. Describir la geometría de las
zonas nodales utilizando el lenguaje del código no resultó sencillo. En la Sección 7 de este
trabajo se describe el diseño de tirantes; en la Sección 8 los requisitos para armadura
nominal. La armadura nominal se provee para agregar ductilidad, mejorar la posibilidad de
redistribución de las fuerzas internas y limitar la fisuración bajo cargas de servicio.

James G. MacGregor recibió un B.Sc. en Ingeniería Civil de la Universidad de Alberta,
Canadá, en 1956, y un Ph.D. de la Universidad de Illinois en 1960. Se unió al
Departamento de Ingeniería Civil de la Universidad de Alberta en 1960, donde continuó
hasta 1993. El Dr. McGregor trabaja en los comités técnicos de ACI sobre corte y torsión,
columnas, y el comité para el Código ACI. Presidió los comités del Código Canadiense
sobre diseño de hormigón armado y diseño estructural. Durante 1992-93 fue presidente de
ACI. El Dr. MacGregor es Miembro Honorario de ACI, miembro de la Royal Society of
Canada y miembro de la Canadian Academy of Engineering. En 1998 recibió un
Doctorado Honorario de la Universidad de Lakehead, y en 1999 un Doctorado Honorario
de la Universidad de Alberta.

<!-- p. 2 -->

Parte 2: Derivación de modelos de bielas y tirantes para el Código ACI 2002

1 Introducción

El Código ACI 2002 incluye un nuevo Apéndice A, “Modelos de Bielas y Tirantes”, y se
han modificado varias secciones del código para permitir el empleo de modelos de bielas y
tirantes (STM, según sus siglas en inglés) en el diseño. Durante el desarrollo del Apéndice
A se tomaron conceptos de la Especificación AASHTO LRFD (1998), el Código modelo
CEB/FIP (1993) según su interpretación en las Recomendaciones FIP (1999) y el Código
de diseño del hormigón de Canadá, CSA A23.3-94 (1994). Los informes de investigación
[Comité ACI 445 (1997)] también aportaron algunas de las bases para el apéndice. Este
trabajo, juntamente con el Comentario del Apéndice A de ACI 318 [ACI (2002)] explica
las decisiones tomadas y las hipótesis asumidas durante el desarrollo del Apéndice A.

2 Importancia

Este trabajo documenta las decisiones tomadas durante el desarrollo del Apéndice A,
“Modelos de Bielas y Tirantes”, del Código ACI 2002.

3 Qué son los modelos de bielas y tirantes?

3.1 Regiones B y Regiones D

Las estructuras de hormigón se pueden dividir en regiones tipo viga donde son aplicables
las hipótesis de distribución lineal de las deformaciones de la teoría flexional, y regiones
perturbadas, adyacentes a los cambios abruptos de carga correspondientes a cargas
concentradas y reacciones, o adyacentes a cambios abruptos de geometría tales como
huecos o cambios de sección transversal. En estas secciones perturbadas las distribuciones
de deformaciones no son lineales. Estas diferentes zonas se conocen como regiones B y
regiones D, respectivamente.
En las regiones B se aplican la teoría de flexión tradicional para hormigón armado, y el
enfoque de diseño tradicional (Vc + Vs) para el corte. Por el contrario, en las regiones D
una gran proporción de la carga es transmitida directamente a los apoyos por las fuerzas de
compresión en el plano del hormigón y las fuerzas de tracción en la armadura, por lo cual
es necesario utilizar otro enfoque de diseño. Las regiones D se pueden modelar usando
reticulados hipotéticos compuestos por bielas de hormigón comprimidas y tirantes de
acero traccionados, que se encuentran en uniones llamadas nodos. Estos reticulados se
conocen como modelos de bielas y tirantes (STMs). El modelo de bielas y tirantes de una
viga de gran altura de un solo tramo ilustrado en la Figura 1 se compone de dos bielas

8

<!-- p. 3 -->

Parte 2: Derivación de modelos de bielas y tirantes para el Código ACI 2002

inclinadas y un tirante horizontal unidos en tres nodos [ACI 318 (2002)]. Los nodos se
ubican dentro de zonas nodales que transfieren fuerzas de las bielas a los tirantes y
reacciones. Se asume que los modelos de bielas y tirantes fallan debido a la fluencia de los
tirantes, aplastamiento de las bielas, falla de las zonas nodales que conectan las bielas y los
tirantes, o falla de anclaje de los tirantes. Se asume que las bielas y las zonas nodales
llegan a su capacidad cuando las tensiones de compresión que actúan en los extremos de
las bielas o en las caras de las zonas nodales llegan a la correspondiente resistencia
efectiva a la compresión, fcu.

P
Biela en forma
de botella Zona nodal

Biela prismática
idealizada

Tirante

Figura 1: Modelo de bielas y tirantes para una viga de gran altura

El principio de St. Venanat y análisis elásticos de tensiones sugieren que el efecto
localizado de una carga concentrada o una discontinuidad geométrica desaparecerá a una
distancia de alrededor de una profundidad del miembro a partir de la carga o
discontinuidad. Por este motivo se asume que las regiones D se extienden
aproximadamente una profundidad del miembro a partir de la carga o discontinuidad.
Enfatizamos los términos “alrededor de” y “aproximadamente” debido a que la extensión
de las regiones D puede variar según el caso. (Ver ACI Sección A.1.)
Si dos regiones D, cada una de ellas de una longitud menor o igual a d, se encuentran o
superponen, el Apéndice A considera que actúan como una región D combinada. Para un
tramo de corte en una viga de gran altura la región D combinada tiene una profundidad
igual a d y una longitud de hasta 2d hacia un lado o hacia dos lados de la perturbación.
Esto establece el menor ángulo entre una biela y un tirante unido a un extremo de la biela
como arctan (d / 2d) = 26,5 grados, redondeado a 25 grados. (Ver ACI Sección A.2.5.)

9

<!-- p. 4 -->

Parte 2: Derivación de modelos de bielas y tirantes para el Código ACI 2002

La Figura 2, reproducida de la publicación “Prestressed Concrete Structures” [Collins y
Mitchell (1991)], compara las resistencias al corte empíricas de vigas simplemente
apoyadas con diferentes relaciones longitud de corte/profundidad, a/d, comprendidas entre
1 y 7. El comportamiento de región B controla las resistencias de las vigas con relaciones
a/d mayores que 2,5 como lo indica la línea aproximadamente horizontal a la derecha de
a/d = 2,5. El comportamiento de región D controla las resistencias de las vigas con
relaciones a/d menores que aproximadamente 2,5 como lo indica la línea de fuerte
pendiente a la izquierda de a/d = 2,5 en la Figura 2.
El Comité ACI 318 limitó las longitudes máximas de regiones D aisladas a d, y a 2d para
el caso de las regiones D superpuestas. Los modelos de bielas y tirantes también se pueden
usar para el diseño de regiones B [Marti (1985)]. Sin embargo, el término Vc no está
incluido en la ecuación tradicional de ACI para resistencia al corte.
Los modelos de bielas y tirantes bidimensionales se utilizan para representar estructuras
planas tales como vigas de gran altura, ménsulas y uniones. Los modelos de bielas y
tirantes tridimensionales se usan para estructuras tales como cabezales para dos o más filas
de pilotes.

placa 6 x 6 x 1 in (152 x 152 x 25 mm)
69 placa 6 x 9 x 2 in (152 x 229 x 51 mm)
0,25 placa 6 x 6 x 0,38 in (152 x 76 x 95 mm)

V V 67 a a

0,20
24 in
(610 mm)

V V
V 0,15 l´c = 3940 psi (272 MPa)
bdf'c
max ag.= 3/4 in (10 mm

d = 21,2 in (538 mm)

b = 6,1 in (155 mm)
As = 3,55 in² (2277 mm²)
y =53,9 ksi (372 MPa) 0,10 72 f

61

65
76 74 75 0,05
71 63 66 79

modelo de bielas y tirantes modelo seccional

0
0 1 2 3 4 5 6 7

a/d

Fig. 2: Resistencia de vigas de hormigón que fallan en corte para diferentes relaciones a/d

10

<!-- p. 5 -->

Parte 2: Derivación de modelos de bielas y tirantes para el Código ACI 2002

3.2 Decisiones necesarias para desarrollar reglas de diseño para los modelos de
bielas y tirantes

A fin de codificar los modelos de bielas y tirantes para el diseño, los principales elementos
a definir y especificar son los siguientes:

(a) la geometría de los modelos de bielas y tirantes,
(b) cuáles son las resistencias efectivas del hormigón y factores φ a utilizar,
(c) la forma y resistencia de las bielas,
(d) la geometría y resistencia de las zonas nodales,
(e) la geometría, resistencia y anclaje de los tirantes, y
(f) los requisitos de detallado

Las definiciones de estos elementos difieren considerablemente en los diferentes códigos y
documentos usados para el diseño. La resistencia efectiva del hormigón y los factores de
reducción de la resistencia del Apéndice A originalmente se derivaron usando los factores
de carga y resistencia del Capítulo 9 del Código ACI 1999. A continuación presentamos
brevemente los cambios que requieren los nuevo factores de carga y resistencia del Código
ACI 2002.

3.3 Geometría de los modelos de bielas y tirantes

Un modelo de bielas y tirantes es un reticulado hipotético que transmite fuerzas desde los
puntos de carga hacia los apoyos. En “Toward a Consistent Design of Structural Concrete”
[Schlaich, Schäfer y Jennewein (1987)], “Prestressed Concrete Structures” [Collins y
Mitchell (1991)], “Basic Tools of Reinforced Concrete Beam Design” [Marti (1985) y
“Reinforced Concrete: Mechanics and Design” [MacGregor (1997)] se discuten la
selección de los modelos de bielas y tirantes, el cálculo de las fuerzas en las bielas y los
tirantes y el diseño de la armadura de los tirantes, a la vez que se presentan ejemplos.
El Apéndice A está formulado bajo la hipótesis que en el diseño se usarán modelos de
bielas y tirantes. No es su intención reducir el diseño a ecuaciones para el corte resistido
por las bielas y la armadura de corte. La selección del modelo y la elaboración de un
esquema del modelo son partes integrales del Apéndice A [ACI (2002)]; el Comentario
RA.2.1 contiene un procedimiento paso a paso para diseñar un modelo de bielas y tirantes.
Diferentes autores también han sugerido métodos para hacerlo [ACI (1999), Collins y
Mitchell (1991), Schlaich, Schäfer y Jennewein (1987) y MacGregor (1997)].
Generalmente el punto de partida es el cálculo de las reacciones para la estructura y las
cargas dadas. En términos generales, el modelo de bielas y tirantes que minimiza la
cantidad de armadura se aproxima al modelo ideal. Para el caso de las estructuras

11

<!-- p. 6 -->

Parte 2: Derivación de modelos de bielas y tirantes para el Código ACI 2002

bidimensionales, algunos autores [Schlaich, Schäfer y Jennewein (1987)] recomiendan
realizar un análisis por elementos finitos para determinar las trayectorias de los esfuerzos
para una situación de carga dada. Luego las bielas se alinean a ±15º de las fuerzas de
compresión resultantes de dicho análisis, y los tirantes a ±15º de las fuerzas de tracción
resultantes.
Por otra parte, el Código Canadiense [CSA (1994)] exige que el análisis por elementos
finitos sea verificado mediante análisis independientes que satisfagan el equilibrio, y
sugiere utilizar para esta verificación los modelos de bielas y tirantes.
Durante el desarrollo de un modelo de bielas y tirantes para una aplicación determinada a
menudo resulta útil seleccionar ubicaciones iniciales tentativas para los nodos y utilizar
estas ubicaciones en el ciclo inicial de cálculo de las fuerzas en los miembros. Si se pueden
conseguir fotografías del patrón de fisuración en estructuras similares, es posible ubicar las
bielas y tirantes dentro de la estructura de manera tal que las bielas se ubiquen entre las
fisuras. Las bielas no deben atravesar regiones fisuradas.
La Sección A.2 del código ACI 2002 presenta varios requisitos fundamentales que debe
satisfacer un modelo de bielas y tirantes:

\1. Primero y principal, el modelo de bielas y tirantes debe estar en equilibrio con las
cargas aplicadas factoreadas y las cargas permanentes factoreadas. (ACI, Sección
A.2.2). El cálculo de las reacciones y las fuerzas en las bielas y tirantes es estático.
Por lo tanto produce un campo de fuerzas estáticamente admisible.
\2. Las resistencias de las bielas, tirantes y zonas nodales deben ser iguales o mayores
que las fuerzas en dichos miembros. (ACI, Sección A.2.6.) Si en cualquier sección
transversal la resistencia es mayor o igual que la resistencia requerida por el análisis
del punto 1 se dice que la estructura tiene una distribución de resistencias segura.
\3. Durante las primeras etapas del diseño de una región D puede ser suficiente
considerar sólo los ejes de las bielas y tirantes. Sin embargo, al diseñar un modelo de
bielas y tirantes, generalmente es necesario considerar los anchos de las bielas,
tirantes, zonas nodales y regiones de apoyo. (Sección A.2.3.)
\4. Las bielas no se deben cruzar ni superponer. (Sección A.2.4.) Los anchos de las bielas
se eligen de manera tal que soporten las fuerzas en las bielas usando la resistencia
efectiva del hormigón de las bielas. Si las bielas se superpusieran, las partes
superpuestas de las bielas resultarían sobrecargadas.
\5. Los tirantes pueden cruzar otros tirantes u otras bielas. (Sección A.2.4.)
\6. El menor ángulo entre una biela y un tirante unidos en un nodo se ha fijado en 25º.
(Sección A.2.5.)

Un diseño estructural estáticamente admisible y seguro satisface los requisitos de una
solución límite inferior en la teoría de plasticidad. Esto implica que la carga de falla

12

<!-- p. 7 -->

Parte 2: Derivación de modelos de bielas y tirantes para el Código ACI 2002

calculada mediante el modelo de bielas y tirantes subestima la carga de falla real. Para
que esto sea cierto, la estructura debe tener ductilidad suficiente para acomodar cualquier
redistribución de fuerzas necesaria.

4 Fuerzas en bielas y tirantes; factores de reducción de la resistencia, φ

Una vez seleccionado el modelo inicial de bielas y tirantes se calculan las reacciones a los
pesos propios y cargas aplicadas. Después de calcular las reacciones se calculan las
fuerzas, Fu, en todas las bielas, tirantes y zonas nodales usando análisis de pórticos. Luego
las bielas, tirantes y zonas nodales se dimensionan en base a:
φFn ≥ Fu (1)

donde Fu es la fuerza en el miembro (biela, tirante o zona nodal) debida a las cargas
factoreadas, Fn es la resistencia nominal del miembro y φ es un factor de reducción de la
resistencia. Las resistencias nominales de bielas, tirantes y zonas nodales son Fns, Fnt y Fnn,
respectivamente.
La Ecuación 1 incluye la resistencia factoreada φFn. En el Código Modelo CEB/FIP
(1993), el Código Canadiense [CSA (1994)] y las Recomendaciones FIP (1999) se aplican
factores de reducción de resistencia de los materiales, φc y φs, ó γc y γs, a las resistencias del
hormigón y el acero, fc' y fy'. El Código ACI 1999 usaba diferentes factores de reducción
de la resistencia para cada tipo de resistencia estructural, φf = 0,9 para flexión y φv = 0,85
para corte en vigas, ménsulas y vigas de gran altura. (En este trabajo hemos agregados
subíndices a los diferentes factores φ a fin de indicar la acción estructural correspondiente
a cada uno de ellos.)
En el Código ACI 2002 las combinaciones de carga y los factores φ del Apéndice C de
ACI 318-99 se intercambiaron con los del Capítulo 9 de ACI 318-99. En el Código 2002,
φv y φSTM se cambiaron a 0,75 para el diseño de modelos de bielas y tirantes usando los
factores de carga y factores de reducción de la resistencia del Capítulo 9 del Código ACI
\2002. Una reevaluación del factor φ correspondiente a flexión indicó que φf podía
permanecer igual a 0,90.

El Código ACI 318-99 incluyó una nueva Sección 18.13 referente al diseño de zonas de
anclajes de tendones postensados, en parte basada en los modelos de bielas y tirantes. El
código especificaba que φPA = 0,85 para el diseño de zonas de anclaje de tendones
postensados, junto con un factor de carga de 1,2 (Sección 9.2.8) para la fuerza de
pretensado. Los modelos de bielas y tirantes de las zonas de anclaje de tendones
pretensados mantienen este factor φ y este factor de carga porque las fuerzas en el tendón y
el factor de carga para las fuerzas en los tendones no se modifican.

13

<!-- p. 8 -->

Parte 2: Derivación de modelos de bielas y tirantes para el Código ACI 2002

5 Bielas

5.1 Tipos de bielas

La forma de las bielas es variable. Generalmente, en los modelos de bielas y tirantes se las
idealiza como miembros prismáticos o uniformemente ahusados como lo indican los lados
rectos de las bielas prismáticas idealizadas en los tramos de corte de la viga de gran altura
de la Figura 1. En este modelo de bielas y tirantes, el hormigón comprimido a la mitad de
la longitud de las bielas tiende a expandirse lateralmente. Si hay lugar para que
efectivamente ocurra esta expansión se dice que las bielas son en forma de botella. En los
modelos bidimensionales la mayoría de las bielas serán en forma de botella.

5.2 Diseño de bielas

Las bielas se diseñan de manera de satisfacer las Ecuaciones 1 a 4. La resistencia
factoreada de una biela se calcula como:
Fns = f cu A c (2)

donde fcu es la resistencia efectiva a la compresión del hormigón de la biela, que se toma
igual a:
f cu =νf c´ (3)

ó
φf cu = φν f c´ = φ STM α1β s f c´ (4)
donde ν (nu) se denomina factor de efectividad, Ac es el área del extremo de la biela sobre
la cual actúa fcu. φSTM es el valor de φ correspondiente a bielas, tirantes y zonas nodales en
modelos de bielas y tirantes, α1 es el factor 0,85 de ACI Sección 10.2.7.1 y βs es el factor
de efectividad para una biela. Si fcu es diferente en los dos extremos de una biela, la biela
se idealiza como uniformemente ahusada. En la derivación de la Ecuación 4 fue necesario
incluir el término ν como un paso intermedio, ya que diferentes códigos e investigadores
incluyen diferentes factores en sus definiciones de resistencia efectiva a la compresión.

5.3 Resistencia efectiva a la compresión de las bielas, fcu

5.3.1 Factores que afectan la resistencia efectiva a la compresión del hormigón de las
bielas

14

<!-- p. 9 -->

Parte 2: Derivación de modelos de bielas y tirantes para el Código ACI 2002

Se asume que la tensión que actúa en una biela es constante en toda la sección transversal
del extremo de la biela. En los siguientes párrafos describimos tres importantes factores
que afectan el factor de efectividad. Los valores de fcu varían entre código y código
dependiendo del énfasis que otorgan a cada uno de estos factores al derivar los valores del
factor de efectividad.
(a) Efectos de la duración de las cargas. La resistencia efectiva de las bielas está dada
por las Ecuaciones 1 y 4, donde ν = α1 βs, y α1 es el factor 0,85 definido en ACI Sección
10.2.7.1; diferentes referencias explican que este factor considera los efectos de la duración
de las cargas, o considera diferentes regímenes de carga en los cilindros y diagramas de
flexión, o considera la migración vertical del agua de sangrado. En la Ecuación 4 α1 se
tomó igual a 0,85 de ACI Sección 10.2.7.1. Probablemente este factor debería ser función
de fc', y disminuir a medida que fc' aumenta [Ibrahim y MacGregor (1997)]. Recientemente
se han sugerido varias relaciones para reemplazar α1 = 0,85 en ACI Sección 10.2.7.1. En
caso que una de las revisiones propuestas sea aceptada, en la Ecuación 4 se modificaría α1
de manera consecuente. El subíndice "s" del término βs se refiere a biela. /Inicial de strut,
término inglés./
(b) Fisuración de las bielas. Típicamente, las bielas desarrollan fisuras axiales,
diagonales o transversales. En los siguientes párrafos explicamos la consiguiente reducción
de la resistencia a la compresión de las bielas.
(i) Bielas en forma de botella. Con frecuencia las bielas son más anchas en su parte
central que en sus extremos; esto se debe a que el ancho de hormigón hacia el cual se
pueden expandir las tensiones es mayor en la parte central que en los extremos de la biela.
Los contornos curvos de las bielas de la Figura 1, indicados con línea discontinua,
representan los límites efectivos de una biela típica. Este tipo de biela se denomina biela en
forma de botella. Para el diseño las bielas en forma de botella se idealizan como las bielas
prismáticas indicadas con línea continua en la Figura 1.
La divergencia de las fuerzas a lo largo de la longitud de la biela tiende a provocar
fisuración longitudinal cerca de los extremos de la biela, tal como se indica en la Figura 3.
En ausencia de armadura que confine esta fisuración las fisuras podrían debilitar la biela.
Schlaich et al. (1987) analizaron este tipo de fisuración y anticipan que ocurrirá cuando la
tensión de compresión en el extremo de la biela supere aproximadamente 0,55fc'. Schlaich
et al. y Breen et al. (1994) sugieren que las bielas divergentes de la Figura 3 tienen una
pendiente de 1:2 como se indica en la figura.
(ii) Bielas fisuradas. La biela puede estar atravesada por fisuras que tienden a debilitarla
[Schlaich, Schäfer y Jennewein (1987)]. Las resistencias efectivas a la compresión dadas
en el Apéndice A y la Sección 5.3.5 de este trabajo reflejan este concepto.
(iii) Deformaciones transversales por tracción. Las deformaciones transversales por
tracción perpendiculares al eje de una biela fisurada conectada a un tirante pueden reducir
la resistencia a la compresión de la biela [Vecchio y Collins (1972)]. En el Código
Canadiense [CSA (1994)] y las Especificaciones AASHTO (1998) se asume que la

15

<!-- p. 10 -->

Parte 2: Derivación de modelos de bielas y tirantes para el Código ACI 2002

resistencia de una biela es función de la deformación transversal por tracción de la biela
debida al tirante unido en uno u otro extremo de la biela, calculada como una función del
ángulo formado por el eje de la biela y el eje del tirante. Los ensayos realizados por
Vecchio y Collins (1982) en paneles cuadrados de hormigón solicitados uniformemente
dieron origen a los valores de fcu dados por las Ecuaciones 11 y 12 de la Sección 5.3.3.
(c) Confinamiento del hormigón que rodea las bielas. En las estructuras de hormigón
tridimensionales tales como cabezales de pilotes, la resistencia a la compresión de una
biela puede aumentar debido al confinamiento provocado por el gran volumen de
hormigón que rodea la biela. Adebar y Zhou (1993) propusieron ecuaciones para la
resistencia efectiva a la compresión a utilizar en el diseño de cabezales de pilotes.

Figura 3: Fisuración longitudinal de una biela en forma de botella

5.3.2 Resistencia efectiva a la compresión de las bielas − según ensayos y bibliografía

Diversos investigadores han propuesto valores para el factor de efectividad ν. En este
trabajo presentamos algunas comparaciones. En la Bibliografía sobre Modelos de Bielas y
Tirantes, compilada por el comité ACI-ASCE sobre Corte y Torsión [ACI 445 (1997)] se
listan muchas otras referencias.
− En base al ensayo de veinticuatro vigas de gran altura de uno y dos tramos, Rogowsky
y MacGregor (1986) propusieron fcu = νfc' = 0,85fc'. Ellos observaron que la selección
de un modelo reticulado adecuado era más importante que la selección de ν.
− Ricketts (1985) informó relaciones entre resistencias de ensayo y resistencias
calculadas de seis vigas continuas de gran altura de dos tramos. Las cargas de falla
anticipadas usando modelos de bielas y tirantes tuvieron una relación promedio
resistencia de ensayo / resistencia calculada igual a 0,96 para ν = 1,0. Cuando tomaron

16

<!-- p. 11 -->

Parte 2: Derivación de modelos de bielas y tirantes para el Código ACI 2002

ν = 0,6 la relación promedio resistencia de ensayo / resistencia calculada aumentó a
1,13. Esto indica que ν estaba más próximo a 1,0 que a 0,6.
− Rogowsky (1983) sostuvo que ν = 1,0 anticipa de manera conservadora las resistencias
de las ménsulas ensayadas por Kriz y Raths (1965). Virtualmente todos los ensayos de
ménsulas tuvieron factores de efectividad, ν, comprendidos entre 1,0 y 1,3.
− Ramirez y Breen (1991) propusieron una relación entre ν y cf' , donde ν varía entre
0,55 y 0,39 para una variación de fc' entre 3000 y 6000 psi.
− Bergmeister et al. (1991) relacionaron ν y fc', con ν variando de 0,77 a 0,69 para
resistencias del hormigón comprendidas entre 3000 y 6000 psi.
− Schlaich et al. (1987) recomendaron valores de ν similares a los indicados en la
Sección 5.3.5 de este trabajo.
− Marti (1985) sugirió un valor constante ν = 0,6.

5.3.3 Resistencia efectiva del hormigón de las bielas − de otros códigos

Debido a que otros códigos tienen diferentes factores de carga, diferentes factores de
resistencia y diferentes maneras de especificar la resistencia del hormigón, los valores βs
de otros códigos no se pueden usar directamente en el Apéndice A. Otra complicación es el
hecho que los factores de carga y resistencia del Capítulo 9 del Código ACI 2002 difieren
de los del Capítulo 9 del Código ACI 1999.
Los valores iniciales de φSTMα1βs correspondientes a los factores de carga del Código ACI
1999 y la definición ACI de fc' se derivaron por calibración respecto de las
Recomendaciones FIP (1999). Las secciones transversales de las bielas requeridas por las
Recomendaciones FIP, por ejemplo, se calcularon para las fuerzas axiales en una biela
hipotética debidas a combinaciones supuestas de carga permanente y sobrecarga, en base a
los factores de carga de las Recomendaciones FIP y para las correspondientes resistencias
del hormigón, fc'.
Luego se calcularon los valores de φSTMα1βs necesarios en el Código ACI de manera que
con las secciones de biela de ambos códigos se obtuvieran las mismas capacidades de
carga:
φSTM = 0,85 y α1 = 0,85

Recomendaciones FIP. Las Recomendaciones FIP (1999) dan la sección transversal de
una biela requerida para una determinada combinación de cargas como:
FuFIP A c,FIP = (5)
f cdeff

17

<!-- p. 12 -->

Parte 2: Derivación de modelos de bielas y tirantes para el Código ACI 2002

donde AcFIP es la sección transversal de la biela calculada usando las Recomendaciones
FIP, FuFIP es la fuerza en la biela debida a la suma de las cargas factoreadas que actúan en
la biela, y fcd,eff es la resistencia efectiva a la compresión del hormigón según FIP. Para una
carga permanente no factoreada en la biela de 1000 kips y sobrecargas de 50 ó 200 kips, se
calcularon los valores de AcFIP usando la Ecuación 5 para resistencias del hormigón
especificadas, fc', de 3000 psi y 6000 psi. Estas se igualaron con las correspondientes áreas,
AcACI, del Apéndice A:
FuACI A c,ACI = ´ (6)
φSTM α1β s f c

donde Ac,ACI es el área de la biela o el diagrama de compresión para un miembro diseñado
usando el Código ACI, y FuACI es la fuerza en la biela debida a las cargas factoreadas de
ACI en el modelo de bielas y tirantes.
Igualando AcFIP y AcACI, suponiendo que las cargas no factoreadas se definen de la misma
manera tanto en ACI como en FIP y reordenando se obtiene:
FuACI f cdeff φSTM β s = ´ (7)
α1f c FuFIP
donde α1 es el factor de ACI Sección 10.2.7.1.
Factores de carga y combinaciones de cargas. La combinación de cargas básica
considerada es carga permanente más sobrecarga (D + L), donde D = 100 kips, siendo L
igual a 50 kips (0,5D) o bien 200 kips (2,0D). Es razonable suponer que D y L se definen
de manera similar en los códigos americanos y europeos.
En FIP, la combinación de cargas básica es U = 1,35D + 1,5L; donde U representa la carga
última. Para L = 0,5D; U = 2,10D (210 kips) y para L = 2D; U = 4,35D (435 kips).
En la Sección 9.2.1 del Código ACI 1999 U = 1,4D + 1,7L. Para L = 0,5D; U = 2,25D
(225 kips) y para L = 2D; U = 4,8D (480 kips).
En la Sección 9.2.1 del Código ACI 2002 la combinación de cargas básica pasa a ser U =
1,2D + 1,6L obteniéndose U = 200 kips y 440 kips para ambos casos de cargas.
Resistencias del hormigón. Se consideraron dos resistencias del hormigón, 3000 kips y
6000 psi.
Hormigón de 3000 psi. Consideremos hormigón de 3000 psi (20,7 MPa) con una
desviación estándar de 450 psi (3,1 MPa) y un coeficiente de variación de 0,15. De acuerdo
con ACI Sección 5.3.2.1, la resistencia promedio requerida, fcr' = 3000 + 1,34 x 450 = 3600
psi. FIP define la resistencia del hormigón usando la resistencia característica o del
porcentil 5, fck, la cual es una fracción menor que la usada en ACI para definir fc'. Para
hormigón con una resistencia especificada según ACI de 3000 psi,
f ck = 3600 (1 − 1,645 × 0,15 ) = 2710psi (18,7MPa )

18

<!-- p. 13 -->

Parte 2: Derivación de modelos de bielas y tirantes para el Código ACI 2002

La resistencia de diseño para compresión uniaxial según FIP es:
f ck f1cd = α× (8)
γ c
donde α = 0,85 es similar a α1 = 0,85 de ACI 10.2.7.1 y la Ecuación 4, y γc es un factor de
resistencia para el hormigón igual a 1,5. Para fc' = 3000 psi:
0,85 × 2710
f1cd = = 1540psi
1,5

Hormigón de 6000 psi. Consideremos hormigón de 6000 psi (41,4 MPa) con una
desviación estándar de 600 psi (4,14 MPa) y un coeficiente de variación de 0,10. De
acuerdo con ACI Sección 5.3.2.1, la resistencia promedio requerida, fcr' = (6000 + 2,33 x
\600) - 500 = 6900 psi. FIP utiliza la resistencia correspondiente al porcentil 5, fck = fcr' (1−
1,645 x 0,10) = 5760 psi (39,8 MPa). De la Ecuación 8, la resistencia de diseño para
compresión uniaxial de acuerdo con FIP es f1cd = 3260 psi.
En las Recomendaciones FIP la resistencia del hormigón de una biela se toma como el
menor valor de:
f cd,eff = ν1f1cd (9)

ó
f cd,eff = ν 2 f1cd (10)

donde la Ecuación 9 sólo es aplicable en las zonas comprimidas de vigas o columnas
cargadas axialmente que se suponen uniformemente solicitadas con fcd,eff = ν1 f1cd actuando
en la distancia c entre el eje neutro y la fibra extrema comprimida. Debido a que esto ubica
la fuerza de compresión resultante a una distancia c/2 de la fibra extrema comprimida, y no
a/2 como se supone en el diagrama rectangular de tensiones del Código ACI, los valores de
fcd,eff basados en ν1 no serán considerados.
FIP define ν2 de la Ecuación 10 mediante las siguientes descripciones:
5.3.2(3) a) Bielas no fisuradas con distribución uniforme de deformaciones. ν2 = 1,00
Para hormigón de 3000 psi fcd,eff es 1,00 x 1540 psi = 1540 psi. Para φSTM = 0,85 el valor de
βs variaba entre 0,76 y 0,83 para los factores de carga de 1999. Para los factores de carga y
resistencia de 2002 el valor de βs varía entre 0,77 y 0,86.
5.3.2(3) b) Bielas con fisuras paralelas a la biela y armadura transversal adherente. La
reducción de resistencia de la biela se debe a la tracción transversal y a las perturbaciones
provocadas por la armadura y las superficies irregulares de las fisuras. FIP indica ν2 =
0,80. Para los factores de carga de ACI 1999 α1 ν βs φ = 0,75 los valores de βs variaban
entre 0,61 y 0,63. Para los factores de carga y factores φ de 2002 el rango es de 0,64 a 0,66.

19

<!-- p. 14 -->

Parte 2: Derivación de modelos de bielas y tirantes para el Código ACI 2002

5.3.2(3) c) Bielas que transfieren compresión a través de fisuras con anchos de fisura
normales, por ejemplo, en almas de vigas. FIP da ν2 = 0,60. Para los factores de carga y
factores φ del Código de 1999 βs variaba entre 0,46 y 0,50. Para los factores de carga y
resistencia de 2002 el rango es de 0,46 a 0,52.
5.3.2(3) d) Bielas que transfieren compresión a través de fisuras muy grandes, por
ejemplo, en miembros con tracción axial o alas traccionadas. FIP da ν2 = 0,45. Para
hormigón de 3000 psi, los correspondientes valores de βs variaban entre 0,34 y 0,37 para el
Código 1999. Para el Código 2002 el rango es de 0,35 a 0,39.
Estos valores se listan en la Tabla 1 para su comparación con los valores de βs derivados de
otros códigos y los propuestos para el Apéndice A. Debido a que las descripciones verbales
empleadas en el Apéndice A del Código ACI difieren de las dadas en las Recomendaciones
FIP, algunos casos FIP se superponen con casos ACI y aparecen listados dos o más veces.
Código Canadiense y Especificación AASHTO LRFD. Estos dos códigos definen fcu en
base a las deformaciones transversales por tracción en las bielas. Se supone que una sola
definición de fcu se aplica para todos los tipos de bielas.
En el Código Canadiense [CSA (1994)] el diseño se realiza usando una resistencia del
hormigón factoreada φc fc' y una resistencia del acero factoreada φs fy donde φc = 0,60 y φs =
0,85. La resistencia del hormigón se define de la misma manera que en ACI 318. En el
Código Canadiense los factores de carga son U = 1,25D + 1,5L. La resistencia efectiva a la
compresión del hormigón de las bielas es:
f c´ ´ f cu = ≤ 0,85f c (11)
0,80 + 170ε1

donde
ε1 = ε s + ( ε s + 0,002 ) cot 2 θ s (12)

εs = deformación por tracción en el tirante
θ = menor ángulo entre el eje de la biela comprimida y el eje del tirante unido a un extremo
de la biela.
En el modelo de bielas y tirantes de la Figura 1, la biela está anclada por el tirante
longitudinal y cruzada por estribos o armadura mínima. En este caso θs se toma como el
ángulo entre el eje de la biela y el tirante, que de acuerdo con la Sección A.2.5 de ACI está
limitado a un valor de 25º y por implicancia tiene un límite superior de 90 − 25 = 65º con
respecto al tirante. Al calcular θs y ε1 se ignoran los estribos y la armadura superficial
mínima.

20

<!-- p. 15 -->

Parte 2: Derivación de modelos de bielas y tirantes para el Código ACI 2002

TABLA 1 − Valores de βs para bielas en modelos de bielas y tirantes. φfcu = φSTMα1βsfc'

β s para φ = 0,85 β n para φ = 0,75
α 1 = 0,85 α 1 = 0,85
Case Código
factores de carga 1999 factores de carga 2002
Valores Elegido Valores Elegido
A.3.2.1 − Bielas en las cuales el ACI Ap. A 1,0 1,0
área de la sección transversal a la
mitad de la longitud de la biela es
igual al área en las zonas nodales,
tales como la zona comprimida
de una viga
• Biela no fisurada con FIP 5.3.2(3)a) 0,76-0,83 0,77-0,86
distribución uniforme de
deformaciones, ν2 = 1,00
• Zona comprimida de una viga ACI 10.2.7 1,06 1,20
• Zona comprimida de una ACI Capítulo 10 0,82 0,87
columna zunchada

A.3.2.2 − Bielas ubicadas de ACI Ap. A 0,75 0,75
manera tal que el ancho de la
sección transversal de la biela a la
mitad de su longitud es mayor
que el ancho en las zonas nodales
(Bielas en forma de botella)
(a) con armadura que satisface
A.3.3
• Bielas con fisuras y armadura FIP 5.3.2(3)b) 0,61-0,66 0,61-0,69
transversal adherente,
ν2 = 0,80
• Bielas que transfieren com- FIP 5.3.2(3)c) 0,46-0,50 0,46-0,52
presión a través de fisuras de
ancho normal, ν2 = 0,6
• Bielas en las zonas de anclaje ACI 18.13 0,82 λ
postensado de modelos de
bielas y tirantes
• Bielas atravesadas por CSA θ = 60º 0,683
armadura que forma un θ = 45º 0,513
ángulo θ respecto del eje de θ = 30º 0,293
la biela
• Calculado a partir de ensayos Ref. 21 0,95
de vigas de uno y dos tramos
(b) sin armadura que satisfaga ACI Ap. A 0,60 λ 0,60 λ
A.3.3

21

<!-- p. 16 -->

Parte 2: Derivación de modelos de bielas y tirantes para el Código ACI 2002

β s para φ = 0,85 β n para φ = 0,75
α 1 = 0,85 α 1 = 0,85
Case Código
factores de carga 1999 factores de carga 2002
Valores Elegido Valores Elegido
• Bielas que transfieren com- FIP 5.3.2(3)c) 0,46-0,50 0,46-0,52
presión a través de fisuras de
ancho normal, ν2 = 0,60

A.3.2.3 − Bielas en miembros ACI Ap. A 0,40 0,40
traccionados, o en las alas
traccionadas de un miembro
• Bielas que transfieren FIP 5.3.2(3)d) 0,34-0,37 0,35-0,39
compresión a través de
grandes fisuras
A.3.2.4 − Para todos los demás ACI Ap. A 0,60 0,60
casos

Para θs = 60º y εs = εy = 0,002 la Ecuación 11 del Código Canadiense [CSA (1994)] da fcu
\= 0,73fc'.
Para θs = 45º y εs = 0,002 la Ecuación 11 da fcu = 0,55fc'.
Para θs = 30º y εs = 0,002 se obtiene fcu = 0,31fc'.
Suponiendo que φ fcu = φSTM α1 βs fc', para estos ángulos θ los valores de βs son 0,68; 0,51 y
0,29 respectivamente, en base a α1 = 0,85 y φSTM = 0,85.

Para los modelos de bielas y tirantes, la Especificación AASHTO LRFD [AASHTO
(2002)] da los siguientes valores de φ:
• Para compresión en modelos de bielas y tirantes ...................................... 0,70
• Para compresión en zonas de anclaje:
− hormigón de peso normal ................................................................. 0,80
− hormigón liviano .............................................................................. 0,65

Para modelos de bielas y tirantes de las zonas de anclaje pretensadas AASHTO indica
f cu = 0,7 φf c´

excepto que, en áreas donde el hormigón puede estar muy fisurado bajo cargas últimas
debido a otros efectos de las fuerzas, o si se anticipan grandes rotaciones inelásticas, la
resistencia efectiva a la compresión factoreada se limita a 0,6 φ fc'.
22

<!-- p. 17 -->

Parte 2: Derivación de modelos de bielas y tirantes para el Código ACI 2002

Igualando φfcu con φα1βsfc' y despreciando las diferencias de los factores de carga se
obtiene βs = 0,82 y 0,71 para φfcu = 0,7φfc' y 0,6φfc' respectivamente, con α1 = 0,85.

5.3.4 Resistencia efectiva del hormigón de las bielas − según otras secciones de ACI
318-99

La resistencia efectiva del hormigón de una biela está dada como el producto φfcu =
φSTMα1βsfc'. En los siguientes tres casos sería deseable que φνfc' concordara con φSTMα1βsfc'
a fin de minimizar las diferencias en la interfase entre las regiones B, diseñadas usando la
teoría tradicional de flexión y corte, y las regiones D, diseñadas usando modelos de bielas
y tirantes.
Diagrama rectangular de tensiones por flexión en vigas. Según el Código ACI 1999, para
flexión, φf = 0,90 y α1 = 0,85 la fuerza de compresión por flexión, Cu, que actúa en la
altura, a = β1c, del diagrama rectangular de tensiones es:
C u,flex = φ f α1f c´ a b (13)

Si suponemos que la fuerza de compresión en un modelo de bielas y tirantes de la misma
viga también es igual a Cu:
C u,STM = φSTM α1β s f c´ a b (14)

Igualando y reemplazando φSTM = 0,85 se obtiene βs = φf / φSTM = 1,06.
Para el mismo caso usando φSTM = 0,75 y φf = 0,90 del Código ACI 2002, βs = 0,90 / 0,75
\= 1,20.
Diagrama de tensiones por flexión en columnas que fallan en compresión. El factor φ
correspondiente a columnas zunchadas es φtc = 0,70 y para columnas con armadura en
espiral φsc = 0,75. Para el Código ACI 1999, φtc ν fc' = φSTM α1 βs fc'. El correspondiente
valor de βs es 0,70 / 0,85 = 0,82 para columnas zunchadas y 0,88 para columnas con
armadura en espiral. Este valor para la zona comprimida de una columna zunchada es
menor que el valor de βs para la zona comprimida de una viga porque los factores φ de ACI
para columnas arbitriamente se fijaron menores que los factores φ para flexión a fin de
tomar en cuenta la mayor severidad y naturaleza frágil de las fallas en columnas.
Zonas de anclaje de tendones pretensados. ACI 318-99 Sección 18.13.4.2. En 1999 ACI
318 incluyó una nueva Sección 18.13 sobre zonas de anclaje de tendones en gran parte
basada en los modelos de bielas y tirantes. Esta revisión utilizó fcu = 0,7 λfc' y φ = 0,85.
Rescribiendo la expresión para fcu como φfcu = φSTM α1 βs fc' se obtiene βs = 0,7 λ / α1 =
0,824 λ.

5.3.5 Selección de fcu para las bielas para el Apéndice A

23

<!-- p. 18 -->

Parte 2: Derivación de modelos de bielas y tirantes para el Código ACI 2002

Los valores de fcu presentados en el Apéndice A del Código ACI fueron seleccionados de
manera de satisfacer cuatro criterios:
(a) Sencillez de aplicación.
(b) Compatibilidad con ensayos de regiones D, tales como vigas de gran altura, extremos
entallados o ménsulas.
(c) Compatibilidad con otras secciones de ACI 318.
(d) Compatibilidad con otros códigos o recomendaciones para el diseño.
Debido a que para una aplicación dada estos cuatro criterios conducen a diferentes valores
de fcu, para seleccionar los valores de fcu fue necesario aplicar el criterio profesional.
En la Tabla 1 se resumen los valores de βs. Los títulos numerados A.3.2.1 a A.3.2.4
describen los tipos de bielas usadas en el Apéndice A de ACI 318-02. En cada sección
también se listan valores de βs para casos relacionados. En los diversos códigos citados se
dan dos métodos diferentes para especificar fcu: (a) FIP utiliza descripciones de la
fisuración de las bielas para seleccionar los valores de ν aplicables. (b) CSA y AASHTO
basan fcu en las Ecuaciones 11 y 12 lo cual requiere calcular εs. La primera opción depende
de hallar descripciones no ambiguas del estado de fisuración del miembro. La segunda
depende de la posibilidad de calcular una deformación mal definida en el alma del
miembro. En el Apéndice A se adoptó la primera opción, es decir, la descripción verbal.
En los siguientes párrafos las frases en cursiva fueron tomadas directamente de ACI 31802.

A.3.2.1 Para bielas cuya sección transversal es uniforme en la totalidad de su
longitud,.......................................................................................................βs = 1,0.
La Tabla 1 lista valores de βs comprendidos entre 0,76 y 1,20 para los casos relacionados.
βs se tomó igual a 1,0 ó se ha propuesto βs = 0,85 para corresponder con el diagrama
rectangular de tensiones correspondiente a flexión. Al momento de tomar esta decisión se
consideró también la evidencia que βs se aproxima a 1,0 en ensayos.

A.3.2.2 Para bielas ubicadas de manera tal que el ancho de la sección transversal de la
biela a la mitad de su longitud es mayor que el ancho en los nodos (bielas en
forma de botella):
(a) con armadura que satisface A.3.3 ........................................................βs = 0,75
Otros códigos dan βs entre 0,46 y 0,824. Los valores del código CSA se basan en un
concepto diferente y por lo tanto los ignoraremos. En experimentos se obtuvieron valores
de βs de hasta 0,94.
(b) sin armadura que satisface A.3.3 .......................................................βs = 0,60λ

24

<!-- p. 19 -->

Parte 2: Derivación de modelos de bielas y tirantes para el Código ACI 2002

El término λ para fisuración del hormigón liviano se incluyó en el valor de βs de A.3.2.2(b)
porque no está presente el efecto estabilizador de la armadura transversal para las bielas y
se asume que la falla se produce poco después de la fisuración.

A.3.2.3 Para bielas en miembros traccionados, o en las alas traccionadas de los miembros
.....................................................................................................................βs = 0,40
El caso similar de FIP corresponde a βs = 0,34 a 0,37.

A.3.2.4 Para todos los demás casos .......................................................................βs = 0,60
Los valores de βs seleccionados generalmente son mayores que los de otros códigos porque
se le dio mayor peso a los valores de fcu correspondientes a los casos de diseño
relacionados del Código ACI y a los valores de fcu de ensayo que a los valores de fcu de
otros códigos.

6 Nodos y zonas nodales

6.1 Clasificación de nodos y zonas nodales

Es importante distinguir entre nodos y zonas nodales. Los nodos son los puntos donde se
intersecan las fuerzas axiales de las bielas y tirantes, mientras que las zonas nodales son las
regiones alrededor de las zonas de unión donde están conectados los miembros. Para que
en un nodo de una estructura plana tal como una viga de gran altura exista equilibrio
vertical y horizontal es necesario que haya un mínimo de tres fuerzas actuando sobre el
nodo.
Los nodos se clasifican de acuerdo con los tipos de fuerzas que se encuentran en los
mismos. De este modo, un nodo C-C-C ancla tres bielas, un nodo C-C-T ancla dos bielas y
un tirante, un nodo C-T-T ancla una biela y dos tirantes. El Apéndice A asume que las
caras de una zona nodal cargadas en compresión tienen el mismo ancho que los extremos
de las bielas. El ancho de las caras que anclan tirantes se discutirá en profundidad en la
Sección 7.1.

6.2 Tipos de zonas nodales y su empleo en modelos de bielas y tirantes

La bibliografía sobre modelos de bielas y tirantes se basa en dos conceptos bastante
diferentes.
Zonas nodales hidrostáticas. Originalmente se asumía que todas las caras de las zonas
nodales estaban sometidas a tensiones iguales. Debido a que el círculo de Mohr para las
tensiones que actúan en estas zonas nodales se grafica como un punto, este tipo de nodo se
25

<!-- p. 20 -->

Parte 2: Derivación de modelos de bielas y tirantes para el Código ACI 2002

denominó zona nodal hidrostática. Si las tensiones son iguales en todos los lados de la
zona nodal, las relaciones entre las longitudes de los lados de una zona nodal hidrostática
es wn1:wn2:wn3 son proporcionales a las fuerzas C1 : C2 :C3 que actúan sobre los lados.
Las zonas nodales hidrostáticas se extendieron a los nodos C-C-T o C-T-T suponiendo que
los tirantes se extendían a través de las zonas nodales para ser anclados del lado más
alejado del nodo mediante ganchos o adherencia. Este concepto se representa usando una
placa de anclaje hipotética detrás de la unión. El área de la placa de anclaje hipotética se
selecciona de manera tal que la presión de apoyo sobre la placa sea igual a las tensiones
que actúan en los otros lados de la zona nodal. El área efectiva del tirante es la fuerza en el
tirante dividida por la tensión de apoyo admisible para las bielas que concurren en un nodo.
El requisito que exige tensiones iguales en todas las caras de una zona nodal hidrostática
tiende a complicar el empleo de este tipo de zonas nodales.
Zonas nodales extendidas. Son zonas nodales limitadas por los contornos de las zonas
comprimidas en la intersección de:
(a) las bielas,
(b) las reacciones, y
(c) los anchos supuestos de los tirantes incluyendo un prisma de hormigón concéntrico con
los tirantes
Esto se ilustra en la Figura 4(a), donde el área sombreada más oscura representa la zona
nodal hidrostática y el área sombreada total es la zona nodal extendida. La zona nodal
extendida cae dentro del área comprimida por efecto de las reacciones y bielas. Las
tensiones de compresión ayudan a la transferencia de fuerzas entre biela y biela, o entre
biela y tirante. En general el Apéndice A utiliza zonas nodales extendidas en lugar de
zonas nodales hidrostáticas.
Relaciones entre las dimensiones de una zona nodal. Es posible derivar ecuaciones que
relacionen los anchos de las bielas, tirantes y áreas de apoyo si se supone que las tensiones
son iguales en los tres miembros que concurren en una zona nodal C-C-T.
w s = w t cos θ + A b sin θ (15)

donde ws es el ancho de la biela, wt es el ancho efectivo del tirante, ℓb es la longitud de la
placa de apoyo y θ es el ángulo entre el eje de la biela y el eje horizontal del miembro. Esta
relación resulta útil para ajustar el tamaño de las zonas nodales en los modelos de bielas y
tirantes. El ancho de una biela se puede ajustar variando wt ó ℓb, una dimensión a la vez.
Una vez ajustado el ancho de biela, es necesario verificar las tensiones en todas las caras
de la zona nodal. La precisión de la Ecuación 15 disminuye a medida que las tensiones en
las caras se vuelven más desiguales. La Ecuación 15 fue incluida en la Figura 4 (ACI
Figura RA.1.6), pero no así en el propio código. Los futuros comités deberían considerar
agregar estas ecuaciones en el Comentario.

26

<!-- p. 21 -->

Parte 2: Derivación de modelos de bielas y tirantes para el Código ACI 2002

ws = wtcosθ + ℓbsinθ

wtcosθ

ℓbsinθ

wt
θ
ℓb

ℓa,

(a) Una capa de armadura

wtcosθ

ℓbsinθ

wt

θ
ℓb

ℓa,
(b) Armadura distribuida

Figura 4: Zona nodal extendida

Resolución de las fuerzas que actúan sobre una zona nodal. Si hay más de tres fuerzas
actuando sobre una zona nodal, muchas veces es necesario resolver algunas de las fuerzas
para poder trabajar con tres fuerzas que se intersecan. Alternativamente, los nodos de
modelos de bielas y tirantes sobre los cuales actúan más de tres fuerzas se podrían analizar
suponiendo que todas las fuerzas de las bielas y tirantes actúan a través del nodo,
resolviendo todas las fuerzas a un lado de la zona nodal para obtener una única resultante
para la biela durante el diseño de la zona nodal. Este concepto se ilustra en la Figura
RA.2.3 del Comentario ACI.

27

<!-- p. 22 -->

Parte 2: Derivación de modelos de bielas y tirantes para el Código ACI 2002

6.3 Resistencia efectiva a la compresión de las zonas nodales

6.3.1 Resistencia efectiva a la compresión de las zonas nodales obtenida mediante
ensayos

Hay muy pocos ensayos de la resistencia de las zonas nodales disponibles. Ensayos
realizados sobre diez zonas nodales C-C-T y nueve zonas nodales C-T-T aisladas
informados por Jirsa et al. (1991) indican que en estas zonas nodales, siempre que estén
adecuadamente detalladas, se puede desarrollar fcu = 0,80 fc'. Para las zonas nodales C-C-T
la relación resistencia de ensayo/resistencia calculada promedio fue de 1,17 con una
desviación estándar de 0,14. Para las zonas nodales C-T-T la relación resistencia de ensayo
/resistencia calculada promedio fue de 1,02. Suponiendo φ = 1,0 para comparar con la
resistencia de las probetas de ensayo y α1 = 0,85 esto corresponde a βn = 0,94.

6.3.2 Resistencia efectiva a la compresión de las zonas nodales según otros códigos

6.3.2.1 Recomendaciones FIP "Diseño práctico del Hormigón Estructural"
Las Recomendaciones FIP limitan fcu en las zonas nodales a los siguientes valores:
• para regiones nodales que anclan uno o más tirantes: 0,85 f1cd donde f1cd está dado por
la Ecuación 8.
Para α1 = 0,85 y φSMT esto corresponde a βn = 0,65 a 0,71.
• para zonas nodales C-C-C cargadas de forma biaxial o triaxial que anclan solamente
bielas:
− estado biaxial de tensiones: hasta 1,20 f1cd (βn = 0,91)
− estado triaxial de tensiones: hasta 3,88 f1cd (βn = 2,9)

6.3.2.2 Código Canadiense y Especificación AASHTO LRFD
El Código Canadiense (1994) define la resistencia efectiva a la compresión de las zonas
nodales, φfcu, como:
• para zonas nodales solicitadas por bielas comprimidas y áreas de apoyo: 0,85 φ fc'
• para zonas nodales que anclan sólo un tirante: 0,75 φ fc'
• para zonas nodales que anclan más de un tirante: 0,65 φ fc'
donde φc = 0,60 en el Código Canadiense.
La intención de los valores βn es reflejar el efecto debilitante de la discontinuidad de
deformaciones introducida cuando hay tirantes traccionados anclados en un nodo solicitado
por compresión. Los valores del código Canadiense equivalen a βn = 0,80; 0,70 y 0,61 en
ACI.

28

<!-- p. 23 -->

Parte 2: Derivación de modelos de bielas y tirantes para el Código ACI 2002

La Especificación AASHTO LRFD usa valores de fcu similares.

6.3.3 Selección de la resistencia efectiva a la compresión de las zonas nodales, fcu

En la Tabla 2 se resumen los valores de fcu para zonas nodales de acuerdo con otros
códigos. Para el Código 1999, el factor de reducción de la resistencia para zonas nodales se
tomó como φSTM = 0,85. La resistencia efectiva a la compresión, fcu, se basará en los
valores de AASHTO y CSA, modificados para concordar con los factores de carga de ACI,
el factor α1 y φSTM = 0,85 usando la Ecuación 4.
Se seleccionaron los siguientes valores para su inclusión en el Código ACI 2002:
• para zonas nodales C-C-C limitadas por bielas comprimidas y
áreas de apoyo .................................................................................. βn = 1,0
• para zonas nodales C-C-T que anclan sólo un tirante ...................... βn = 0,80
• para zonas nodales C-T-T o T-T-T que anclan tirantes en más de
una dirección .................................................................................... βn = 0,60
La Tabla 2 muestra que estos valores se ajustan razonablemente a los valores de βn para
cada tipo de zona nodal.

7 Tirantes

7.1 Tirantes en los modelos de bielas y tirantes

En los modelos de bielas y tirantes basados en zonas nodales hidrostáticas la armadura de
los tirantes se distribuye en la altura del tirante según el siguiente cálculo:
Fu / φ w t = (16)
f cu b w

Se asume que el tirante está formado por la armadura más un prisma de hormigón
hipotético concéntrico con el eje de la fuerza de tracción. Por lo tanto, la Sección A.4.2 de
ACI requiere que la armadura de los tirantes se distribuya de manera aproximadamente
uniforme en el ancho del tirante, wt. Esto puede implicar la colocación de la armadura en
varias capas como se ilustra en la Figura 4(b), y no concentrarla en la cara traccionada de
la viga como se ilustra en la Figura 4(a).
Si se utilizan zonas nodales extendidas, el valor extremo menor de la altura del tirante
corresponde al acero colocado en una capa tomando wt igual al diámetro de las barras más
dos veces el recubrimiento de las barras como en la Figura 4(a). (Ver también la Sección
RA.4.2 del Comentario del Apéndice A.)

29

<!-- p. 24 -->

Parte 2: Derivación de modelos de bielas y tirantes para el Código ACI 2002

7.2 Resistencia de los tirantes

Se asume que un tirante no pretensado llega a su capacidad cuando la fuerza en el tirante
llega a
Tn = A s f y (17)

Para los tirantes pretensados se agrega un segundo término, la Ecuación A−6 de ACI
supone ∆fp igual a 60 ksi. Esta es una aproximación razonable para el cambio de tensión en
la armadura pretensada a medida que el miembro se carga hasta el punto de falla.
Generalmente el principal problema en el diseño de tirantes es el anclaje de los mismos en
una zona nodal. El prisma hipotético de hormigón concéntrico con el tirante no resiste
ninguna parte de la fuerza en el tirante. En las verificaciones de serviciabilidad la menor
deformación del tirante debida a este hormigón puede reducir el alargamiento del tirante,
produciendo menor deflexión en el miembro.

Tabla 2: Valores de βn recomendados para las zonas nodales en modelos de bielas y
tirantes, φ = 0,85 y factores de carga de 1999 y φ = 0,75 y factores de carga de 2002
φfcu = φα1βnfc'
Rango βn 1 y facto- Rango βn2 y factoCaso Código de βn res de carga de βn res de carga
de 1999 de 2002
Zonas nodales C-C-C CSA A23.3 0,79-0,80 1,0 0,76-0,83 1,0
• Zonas nodales que FIP 0,91-1,00 0,92-1,03
anclan sólo bielas
comprimidas
Zonas Nodales C-C-T CSA A23.3 0,70-0,71 0,80 0,67-0,73 0,80
• Zonas nodales que FIP 0,65-0,71 0,65-0,73
anclan uno o más tirantes

Zonas nodales C-T-T CSA A23.3 0,61 0,60 0,58-0,63 0,60
• Zonas nodales que FIP 0,65-0,71 0,65 - 0,73
anclan uno o más tirantes
Ensayos de zonas nodales. Ref. 15 0,94
Para los ensayos φ = 1,0
Notas: 1 El primer conjunto de valores de βn recomendados son para utilizar con los factores de carga de
1999, asumir α1 = 0,85 y φSTM = 0,85
2 El segundo conjunto de valores de βn recomendados son para utilizar con los factores de carga de
2002, asumir α1 = 0,85 y φSTM = 0,75.

30

<!-- p. 25 -->

Parte 2: Derivación de modelos de bielas y tirantes para el Código ACI 2002

7.3 Anclaje de los tirantes

Las Secciones A.4.3.1, A.4.3.2 y A.4.3.3 de ACI requieren que el anclaje de las fueras de
los tirantes se logre completamente antes que el baricentro geométrico de las barras de un
tirante abandone la zona nodal extendida. Esto se ilustra en la Figura 4. Es posible que sea
necesario utilizar ganchos o anclajes mecánicos. La Sección A.4.3 de ACI lista otros
requisitos para el anclaje de tirantes. En las zonas nodales de estructuras tipo viga en las
cuales las bielas diagonales están ancladas mediante estribos, el cambio de las fuerzas del
tirante en el nodo del reticulado debe ocurrir dentro del ancho de la zona nodal.

8 Requisitos de armadura

8.1 Efectos de la armadura mínima de confinamiento según ensayos

Es deseable contar con mallas de armadura en las caras laterales de las regiones D para
restringir las fisuras longitudinales cerca de los extremos de las bielas en forma de botella,
y también para darle algo de ductilidad a las bielas.
Tres vigas continuas de gran altura de dos tramos ensayadas por Rogowsky (1983) y
Ricketts (1985), con relaciones longitud de tramo/profundidad igual a 0,8 y estribos
verticales para una cuantía, ρv, de 0,0015 y sin armadura de corte horizontal, fallaron luego
que la armadura de momento positivo (armadura inferior) entrara en fluencia pero antes
que lo hiciera la armadura superior, y como resultado estas dos vigas no desarrollaron la
totalidad de su capacidad de carga plástica. Esta ρv no permitió una adecuada
redistribución de momentos.
Tres vigas similares con cuantías de estribos verticales del orden de 0,0035 − también en
este caso sin armadura de corte horizontal − tenían diferentes distribuciones de armadura
de flexión. En estas vigas las cantidades relativas de armadura superior e inferior, según un
análisis elástico de una viga esbelta, fueron de 4 barras superiores y 3 barras inferiores. Las
tres vigas variaban las cantidades de barras superiores e inferiores: 2 barras superiores y 5
barras inferiores en la primera viga, 4 barras superiores y 3 barras inferiores en la segunda
viga, y 5 barras superiores y 2 barras inferiores en la tercera viga. Las tres vigas fallaron
luego que tanto la armadura superior como la inferior entraran en fluencia. Esto requirió
redistribución de momentos. Las tendencias de estos y otros ensayos con cuantías variables
sugieren que en vigas con estribos verticales exclusivamente la totalidad de la capacidad
plástica se alcanzaría con una cuantía de armadura de estribos de 0,0025.

8.2 Armadura mínima requerida en las bielas en forma de botella

31

<!-- p. 26 -->

Parte 2: Derivación de modelos de bielas y tirantes para el Código ACI 2002

Las Secciones A.3.2.2(a) y (b) de ACI permiten usar βs = 0,75 para el cálculo de la
resistencia efectiva a la compresión de bielas en forma de botella con armadura que
satisface la Sección A.3.3 de ACI. Si no se provee esta armadura el valor de βs se reduce a
0,60 λ. La Sección A.3.3 de ACI requiere armadura transversal al eje de la biela
dimensionada de manera de resistir la fuerza de tracción que se pierde cuando la biela se
fisura debido a la expansión de las fuerzas de la biela. La Sección A.3.3 de ACI permite
que el diseñador calcule la armadura necesaria ya sea mediante un modelo de bielas y
tirantes ideal, localizado, de la biela como se ilustra en la Figura 3(b) o bien, para el caso
de vigas con hormigón de resistencia menor o igual a 6000 psi, la Sección A.3.3.1 de ACI
permite aproximar los resultados del modelo de bielas y tirantes usando la ecuación
empírica, Ecuación A-4. Esta ecuación se derivó asumiendo que la tensión normal, σ1, que
actúa en la fisura resultante de una capa de armadura de confinamiento es:
A s1f s1 σ1 = sin γ 1 (18)
bs1
donde As1 es la sección de las barras en una dirección y el ángulo γ1 es el ángulo entre la
fisura y la componente de la fuerza en la barra en cuestión. La dirección de la barra se
selecciona de manera tal que una fuerza de tracción en la barra provoque una fuerza de
compresión en el hormigón perpendicular a la fisura. A fin de simplificar la presentación
se ha escrito sin el término fsi.
A.3.3.1 permite satisfacer este requisito mediante capas de armadura que cruzan la biela y
que satisfacen

sin γ i ≥ 0,003 (19) ∑ A si
b s i

donde Asi es la sección total de armadura con separación si en una capa de barras que
forma un ángulo γi respecto del eje de la biela. La Sección A.3.3.1 de ACI establece que
esta armadura generalmente se dispone en forma de malla en dos direcciones ortogonales
en cada cara, pero permite colocarla en una sola capa en casos tales como las ménsulas o
cartelas.

8.3 Mínima armadura de corte en vigas de gran altura

Existe una gran discontinuidad en la cantidad de armadura de corte requerida en el límite
entre vigas de gran altura y vigas de poca altura en los códigos de 1999 y anteriores. Las
Recomendaciones FIP (1998) proporcionan una transición de una región D a una región B
para relaciones a/d próximas al límite de 2. Para longitudes de corte con a/z entre 0,5 y 2,
siendo z = jd el brazo de palanca interno entre las fuerzas resultantes de tracción y
compresión en flexión, FIP requiere que una parte, V2, del corte total, V, en la longitud de

32

<!-- p. 27 -->

Parte 2: Derivación de modelos de bielas y tirantes para el Código ACI 2002

corte sea transferido a los apoyos mediante una biela inclinada, y el resto, V1 = V − V2, sea
transferido mediante armadura de corte vertical.
Para a/z comprendido entre 0,5 y 2,0 V1 está dado por:
 2a 
 − 1 
 z  V1 = V (20)
3
En los límites a/z = 0,5 y 2,0 esta ecuación da por resultado V1 = 0 y V1 = V. Por lo tanto,
para a/z = 0,5 FIP recomienda que todo el corte V sea transferido mediante la biela
inclinada, y para a/z = 2 FIP recomienda que todo el corte sea resistido por estribos. El
Subcomité ACI 318 E debería considerar la posibilidad de agregar al Apéndice A este
requisito u otro similar. Este requisito impide la existencia de modelos de bielas y tirantes
con bielas que forman ángulos demasiado pequeños respecto del eje longitudinal del
miembro. Por el mismo motivo, la Sección A.2.5 de ACI limita este ángulo a 25º.

8.4 Mínima armadura de corte según diferentes códigos

• El Código CSA 1994 requiere una malla ortogonal de barras de armadura próxima a
cada cara con una relación entre sección total de armadura y sección bruta de hormigón en
cada dirección de al menos 0,002. Esto se conoce como armadura para limitación de la
fisuración. La porción de esta armadura paralela a un tirante y ubicada dentro de la sección
transversal supuesta para el tirante se puede considerar como parte de la armadura del
tirante.
• AASHTO (2002) contiene requisitos similares a los del CSA, pero fija la cuantía
mínima total en cada dirección igual a 0,003. El Comentario de la Especificación
AASHTO LRFD establece que, en miembros más esbeltos, debería haber una malla de
barras en cada cara, mientras que en miembros más gruesos podría ser necesario disponer
múltiples mallas en todo el ancho.
• Las Recomendaciones FIP (1999) sugieren que las vigas de gran altura deberían tener
una cuantía mínima de 0,001 en cada dirección, en cada cara, totalizando no menos de
0,002 en cada sentido.
• Las Secciones 11.8.4 y 11.8.5 de ACI 318-99 requieren cuantías mínimas de armadura
de corte vertical y horizontal de 0,0015bws y 0,0025bws2, respectivamente, en vigas de gran
altura.
Estas cantidades mínimas proveen una capacidad de corte considerable. Cada 0,001bws de
armadura de corte vertical corresponde a una resistencia al corte, Vs correspondiente a v =
60 psi, calculada usando la Ecuación 11-15 de ACI. La armadura de corte horizontal es
mucho menos eficiente para transferir corte. La capacidad adicional provista por la

33

<!-- p. 28 -->

Parte 2: Derivación de modelos de bielas y tirantes para el Código ACI 2002

armadura de corte vertical no está implícitamente incluida en el cálculo de resistencia
usando las Ecuaciones A-1 y A-2 de ACI. Se toma en cuenta mediante el aumento de βs.
Para algunas regiones D, como por ejemplo las de una viga de gran altura, resulta factible
proveer mallas ortogonales de armadura próximas a las caras de la viga. En otros casos,
tales como ménsulas o extremos entallados, es más sencillo colocar la armadura en una
sola dirección, horizontal en el caso de una ménsula. La Sección A.3.3.2 de ACI permite
armadura de confinamiento unidireccional en ménsulas o casos similares. Si se la coloca en
una sola capa, la armadura se coloca en una dirección que forme un ángulo de al menos 40º
respecto del eje de la biela.
En algunas estructuras tridimensionales, como por ejemplo los cabezales para más de dos
pilotes, a menudo no resulta posible colocar armadura de corte en el modelo de bielas y
tirantes. En estos casos la Sección A.3.2.2(b) de ACI requiere reducir la resistencia de las
bielas.

8.5 Selección de la mínima armadura de corte

En una región D la mínima armadura de corte tiene dos funciones estructurales: resistir la
tracción transversal en las áreas en forma de botella próximas a los extremos de la biela
una vez que se produce la fisuración por tracción por compresión diametral, y proveer
ductilidad a las bielas y zonas nodales mediante confinamiento. En la Ecuación A-4 la
armadura mínima se da en términos de cantidades equivalentes perpendiculares al eje de la
biela.
En los ensayos de Rogowsky (1983) y Ricketts (1985) citados anteriormente, la totalidad
de la capacidad plástica se obtuvo con una cuantía de armadura vertical igual a 0,0035.
Estas vigas no tenían armadura de corte horizontal. El modelo de bielas y tirantes de la
región de falla indicó que la biela crítica tenía una pendiente de alrededor de 55º respecto
de la armadura vertical.
La cuantía crítica de armadura de corte tomada perpendicularmente a la biela es ρv sinγ,
donde γ es el ángulo formado por la armadura y el eje de la biela. En los ensayos de
Rogowsky y Ricketts citados en el párrafo precedente, γ fue de 55º y la cantidad de
armadura provista fue equivalente a

sin γ i = 0,0029 ∑ A si
b s i

En el diseño esta limitación de la fisuración se logra disponiendo armadura de corte
mínima que satisfaga:
ρ vi sin γ i ) ≥ 0,003 (21) ∑ (

34

<!-- p. 29 -->

Parte 2: Derivación de modelos de bielas y tirantes para el Código ACI 2002

donde ρvi es la cuantía para la armadura de corte que forma un ángulo γi respecto del eje de
la biela.

8.6 Comparación de modelos de bielas y tirantes con ensayos en vigas de gran
altura

Durante el desarrollo de los requisitos del Código ACI correspondientes a modelos de
bielas y tirantes se consideraron una variedad de resultados de ensayos, según se informó
en la Sección 5.3.2 de este trabajo. Además, los requisitos finales del código se
compararon con ensayos realizados en ambos extremos de seis vigas de gran altura de un
solo tramo ensayadas por Rogowsky y MacGregor (1986). Estas vigas eran relativamente
grandes, con alturas totales de 500 a 1000 mm y longitudes de 2000 mm, y relaciones a/d
de 1,03; 1,86 y 2,21.
Se asumió que cada viga tendría cinco estados límites de falla, desde fluencia de los
tirantes hasta aplastamiento de cada extremo de cada biela y aplastamiento de las zonas
nodales en cada extremo de cada biela. La resistencia de cada longitud de corte se tomó
como la menor de las cinco resistencias al corte para dicha longitud de corte. Las
relaciones entre el menor valor de ensayo y la resistencia al corte calculada estuvieron
comprendidas entre 0,96 y 2,14 con un promedio de 1,54 y un coeficiente de variación de
0,247. Las relaciones medias ensayo/cálculo disminuyeron desde 2,0 para vigas con a/d =
1,06 hasta 1,32 para vigas con a/d = 2,0. Esto concuerda razonablemente con los datos de
ensayos de corte. En otro trabajo presentado en este simposio, D. Mitchell presenta otros
controles respecto de datos de ensayo.

9 Otros detalles

9.1 Cambios en las Secciones 10.7.1 y 11.8 del Código ACI 1999

Cuando se introdujeron los modelos de bielas y tirantes fue necesario cambiar las
definiciones de vigas de gran altura de las Secciones 10.7.1 y 11.8.1 del código ACI 1999.
Las nuevas definiciones se basan en la definición de viga de gran altura dada en la Sección
A.1 de ACI 2002.
Las ecuaciones de diseño del Código ACI 1999 y anteriores para vigas de gran altura se
basaban en el enfoque (Vc + Vs) para el corte. Se eliminaron las Ecuaciones 11-29 y 11-30
para Vc y Vs del Código 1999, sin reemplazarlas en el Capítulo 11, ya que estas ecuaciones
no reflejaban el comportamiento real de las vigas de gran altura. Esto es particularmente
cierto en el caso de vigas continuas de gran altura en las cuales el momento tiende a cero
en la sección crítica definida en la Sección 11.8.5 de ACI. En consecuencia, el segundo
término del lado derecho de la Ecuación 11-29 de ACI para Vc tiende a cero. Además,
35

<!-- p. 30 -->

Parte 2: Derivación de modelos de bielas y tirantes para el Código ACI 2002

existía una discontinuidad muy importante en la magnitud de Vs de la Ecuación 11-30 de
ACI 1999. Para ℓn/d = 5,0 el Vs provisto por estribos horizontales caía de 0,5Avfy para ℓn/d
\= 4,99 a cero para ℓn/d = 5,01. En la misma región el Vs provisto por estribos verticales
aumentaba de 0,5 a 1,0 Avfy.
La Sección 11.8 de ACI, "Vigas de Gran Altura", se acortó omitiendo estas secciones, y se
permitió el diseño ya sea mediante análisis no lineales o mediante modelos de bielas y
tirantes.

9.2 Cabezales de pilotes

Se revisó la Sección 15.5.3 de ACI para permitir el empleo de modelos de bielas y tirantes
en el diseño de cabezales de pilotes. En un cabezal de pilotes el modelo de bielas y tirantes
es tridimensional. Las zonas nodales también son tridimensionales, con las bielas de los
diferentes pilotes convergiendo en la zona nodal en la base de la columna. La intención de
la Sección A.5.3 es simplificar el diseño de modelos tridimensionales de bielas y tirantes,
requiriendo que el área de cada una de las caras individuales de la zona nodal se calcule
mediante la Ecuación A-7, pero no exigiendo una correspondencia exacta entre la
geometría en el extremo de la biela y la correspondiente geometría de la cara de la zona
nodal sobre la cual actúa la biela, siempre que se provea suficiente superficie de apoyo.

9.3 Serviciabilidad

El último párrafo de RA.2.1 menciona la serviciabilidad. Las deflexiones se pueden
estimar usando un análisis de pórtico elástico del modelo de bielas y tirantes. La rigidez
axial de las bielas se puede modelar como regiones fisuradas con rigideces axiales iguales
a AsEs/ℓcr y regiones no fisuradas con rigideces axiales iguales AcEc/ℓuncr, donde ℓcr y ℓuncr
son las porciones de la longitud de biela que se puede asumir poseen una rigidez de sección
fisurada y la fracción que posee rigidez de sección no fisurada, respectivamente. Esto
permite modelar el alargamiento del tirante de manera más sencilla. Sobre este tema se
deberían realizar estudios más profundos.

10 Resumen

Se explica el desarrollo del Apéndice A del Código ACI 2002 y la selección de los factores
φ y las resistencias efectivas del hormigón. Se analizan las características de los modelos
de bielas y tirantes.

36

<!-- p. 31 -->

Parte 2: Derivación de modelos de bielas y tirantes para el Código ACI 2002

11 Agradecimientos

El Apéndice A del Código ACI fue desarrollado por el Comité ACI 318, Subcomité E,
Corte y Torsión, presidido por J.O. Jirsa. Posteriormente, durante el período en el cual el
Apéndice fue sometido a consideración y revisión, la presidencia fue ocupada por J.K.
Wight. El Comité ACI 445, "Modelos de Bielas y Tirantes", presidido por K.H. Reineck,
ofreció su ayuda y una gran variedad de verificaciones de diseño. Las verificaciones de
diseño y las comparaciones con ensayos fueron realizadas por los miembros de ACI 445.A.
El Apéndice A fue revisado por el Comité ACI 318 y aprobado en un proceso de votación.

12 Notación

En este trabajo se utiliza la siguiente notación:
wn1, wn2, wn3 = longitudes de las caras de una zona nodal.
Ac = menor área de extremo de una biela.
Av = sección de armadura de corte vertical en una separación s.
bw = ancho del alma de una viga.
fc' = resistencia a la compresión especificada del hormigón.
Fcd eff = resistencia del hormigón de una biela − FIP.
fcu = resistencia efectiva a la compresión de las bielas o zonas nodales − ACI.
f1cd = resistencia de diseño del hormigón para compresión uniaxial − FIP.
Fn, Fnn, Fns, Fnt = resistencia nominal, resistencia nominal de una zona nodal, resistencia
nominal de una biela y resistencia nominal de un tirante.
Fu = fuerza en una biela, tirante o nodo debida a las cargas factoreadas.
jd = brazo de palanca interno entre las fuerzas resultantes de tracción y compresión en
una viga, de la Sección 10.2.7 de ACI.
s = separación de la armadura de corte vertical.
Vc = resistencia al corte provista por el hormigón.
Vs = resistencia al corte provista por los estribos.
wt = altura de un tirante y el hormigón que lo rodea.
z = brazo de palanca interno entre las fuerzas resultantes de tracción y compresión en
una viga

37

<!-- p. 32 -->

Parte 2: Derivación de modelos de bielas y tirantes para el Código ACI 2002

α1 = relación entre la tensión promedio del diagrama rectangular de tensiones y la
resistencia del hormigón.
βs, βn = relación entre la resistencia de diseño del hormigón en una biela o nodo y la
resistencia especificada.
ε1 = deformación por tensión principal en el hormigón.
ε2 = deformación en un tirante.
φ, φf, φv, φSTM = factor de reducción de la resistencia, factores de reducción de la
resistencia para flexión, para corte, para modelos de bielas y tirantes.
γ = ángulo entre el eje de una biela y el eje de una capa de armadura de
confinamiento.
λ = factor de corrección para la resistencia del hormigón liviano.
ν = factor de efectividad.
ρv A v = cuantía de armadura de corte vertical =
b w s

13 Referencias

AASHTO (1998): LRFD Bridge Specifications and Commentary. 2da Edición, American
Association of Highway and Transportation Officials, Washington, 1998, 1216 pp.
ACI Committee 318 (2002): Building Code Requirements for Structural Concrete (ACI
318-02) and Commentary (ACI 318R-02). American Concrete Institute, Farmington Hills,
MI, 2002, 443pp.
ACI Committee 445 (1997): Strut-and-Tie Bibliography, ACI Bibliography No. 16, 1997,
50 pp.
ACI ASCE Committee 445 (1998): Recent approaches to shear design of structural
concrete. State-of-the-Art-Report by ASCE-ACI Committee 445 on Shear and Torsion.
ASCE Journal of Structural Engineering 124 (1998), No. 12, 1375-1417 (ver también ACI
445R-99, American Concrete Institute, Farmington Hills, MI (1999), 55 pp.).
Adebar, P. and Zhou, Z. (1993): Bearing Strength of Compressive Struts Confined by
Plain Concrete. ACI Structural Journal, Vol. 90 (1993), No. 5, Setiembre-Octubre 1993, pp
534-541.
Bergmeister, K., Breen, J.E. y Jirsa, J.O. (1991): Dimensioning of Nodal zones and
Anchorage of Reinforcement, Structural Concrete. IABSE Colloquium Structural Concrete,
Stuttgart, 1991, pp 551-564.

38

<!-- p. 33 -->

Parte 2: Derivación de modelos de bielas y tirantes para el Código ACI 2002

Breen, J.E.; Burdet, O; Roberts, C; Sanders, D; Wollmann, G: y Falconer, B. (1994):
NCHRP Report 356, Transportation Research Board, National Academy Press,
Washington, D.C.
Canadian Standards Association (CSA) (1994): A23.3-94, Design of Concrete Structures,
Canadian Standards Association, Rexdale, Dic. 1994, 199 pp.
CEB-FIP Model Code 1990 (1993): Design of concrete structures. Comité EuroInternational du Beton, Thomas Telford Services Ltd., Londres, 1993, 437 pp.
Collins, M P and Mitchell, Denis (1991): Prestressed Concrete Structures, Prentice Hall
Inc., Englewood Cliffs, 1991, 766 pp.
FIP Recommendations (1999): Practical Design of Structural Concrete. FIP-Commission 3
"Practical Design", Sept. 1996. Publ.: SETO, Londres, Sept. 1999. (Distribuido por: fib,
Lausanne).
Ibrahim, Hisham H.H. y MacGregor, James G. (1997): Modification of the ACI
Rectangular Stress Block for High-Strength Concrete. ACI Structural Journal Vol. 94
(1997), No. 1, Enero- Febrero 1997, pp 40-48.
Jirsa, J.O., Bergmeister, K., Anderson, R., Breen, J.E., Barton, D., y Bouadi, H. (1991):
Experimental Studies of Nodes in Strut-and-Tie Models. Structural Concrete, IABSE
Colloquium Structural Concrete, Stuttgart, 1991, pp 525-532.
Kriz, L.B. y Raths, C.H. (1965): Connections in Precast Concrete Structures: Strength of
Corbels. PCI Journal, Vol. 10 (1965), No. 1, 1965, pp 16-47.
MacGregor, J.G. (1997): Reinforced Concrete. Mechanics and Design, 3ra Edición.
Prentice Hall, 1997, 939 pp.
Marti, P. (1985): Basic Tools of Reinforced Concrete Beam Design. ACI Journal, Vol. 82
(1985), No. 1, Enero-Febrero 1985, pp 46-56.
Ramirez, J.A. y Breen, J.E. (1991): Evaluation of a Modified Truss-Model Approach for
Beams in Shear. ACI Structural Journal, Vol. 88 (1991), No. 5, Sept.-Oct. 1991, pp 562571.
Ricketts, D. (1985): Continuous Reinforced Concrete Deep Beams. Tesis Doctoral,
University of Alberta, Edmonton, 1985.
Rogowsky, D.M. y MacGregor, J.G. (1986): Design of Deep Reinforced Concrete
Continuous Beams. Concrete International: Design and Construction, Vol. 8 (1986), No. 8,
Agosto, pp 49-58.
Rogowsky, D.M. (1983): Shear Strength of Deep Reinforced Concrete Continuous Beams.
Tesis Doctoral, University of Alberta, Nov. 1983, 178 pp.
Schlaich, J.; Schäfer, K.; Jennewein, M. (1987): Toward a Consistent Design of Structural
Concrete. PCI Journal, Vol. 32 (1987), No. 3, Mayo-Junio, p. 74-150.

39

<!-- p. 34 -->

Parte 2: Derivación de modelos de bielas y tirantes para el Código ACI 2002

Vecchio, F.J.; Collins, M.P. (1982): The Response of Reinforced Concrete to Inplane Shear and Normal Stresses. Publicación 82-03, Departamento de Ingeniería
Civil, Universidad de Toronto, Toronto, Marzo 1982, 332 pp.

40
