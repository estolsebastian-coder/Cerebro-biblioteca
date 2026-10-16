---
type: libro
title: "PRESIONES EN ZAPATAS RGIDAS DE FORMA ARBITRARIA SOMETIDAS A CARGA AXIAL EXCNTRICA"
author: "eperez"
categoria: "ESTRUCTURA"
paginas: 16
extraccion: "texto"
fuente: "local:E:/MATERIAL DE CONSULTA/ESTRUCTURA/SUELOS/FUNDACIONES/Presiones_en_zapatas_de_forma_arbitraria.pdf"
convertido: 2026-10-16
---

# PRESIONES EN ZAPATAS RGIDAS DE FORMA ARBITRARIA SOMETIDAS A CARGA AXIAL EXCNTRICA

> Texto extraído de `ESTRUCTURA\SUELOS\FUNDACIONES\Presiones_en_zapatas_de_forma_arbitraria.pdf` (16 páginas, texto). El PDF original está en el disco E: (MATERIAL DE CONSULTA); `<!-- p. N -->` marca el inicio de cada página.

<!-- p. 1 -->

PRESIONES EN ZAPATAS RÍGIDAS DE FORMA ARBITRARIA
SOMETIDAS A CARGA AXIAL EXCÉNTRICA

J. A. Rodríguez-Gutiérrez1 y J. Darío Aristizabal-Ochoa2

Resumen: Un modelo para el análisis de zapatas superficiales rígidas de formas arbitrarias
bajo fuerza axial y flexión biaxial es propuesto. El modelo permite calcular la posición del eje
neutro y la presión máxima bajo una zapata superficial de forma arbitraria con o sin vacíos
sometida a carga axial y momentos flectores dados biaxiales. Tres modelos de distribución de
presiones bajo una zapata son utilizados: uniforme, lineal y parabólico. Una serie de
monogramas o ayudas de diseño son desarrolladas para el cálculo de las presiones de contacto
entre zapatas rígidas y el suelo elástico soportante. Se presenta un algoritmo basado en la
integral de Gauss para los casos de zapatas de forma irregular o con vacíos interiores
(agujeros). Tres ejemplos numéricos son incluidos para mostrar la capacidad del algoritmo
propuesto y verificar los resultados con los de otros métodos.

CONTACT PRESSURE CAUSED BY A RIGID FOOTING OF ANY SHAPE
SUBJECTED TO ECCENTRIC AXIAL LOAD

Abstract: The stress analysis of an elastic soil supporting a rigid footing of arbitrary shape
subjected to axial load with eccentricities about two axes is presented. The proposed model
calculates the position of the neutral axis and the maximum contact pressure in the soil. Three
different models for the contact pressure distribution are utilized: uniform, linear and
parabolic. A series of monograms or design aids are developed to facilitate the stress analysis
of elastic soils supporting rigid footings subjected to eccentric axial loads. For footing areas
of irregular shapes or with cutoffs or interior openings, a computer algorithm based on the
Gauss integral method is presented. Three numerical examples are included to verify the
proposed method and to show its effectiveness.

INTRODUCCIÓN

En el análisis y diseño de estructuras, el cálculo de las presiones en el suelo soportante y la localización de las
fuerzas resultantes en las zapatas son de vital importancia para garantizar el buen comportamiento bajo las cargas
aplicadas. Existen en la literatura técnica ayudas de diseño para calcular la presión máxima bajo zapata rectangulares y
circulares. Plock (1963) presenta gráficas para el cálculo de la posición del eje neutro y de la presión máxima bajo
zapatas rectangulares bajo flexión biaxial (basado en una distribución lineal de presiones). Zweig (1966) presenta ayudas
para obtener las presiones bajo zapatas trapezoidales cargadas excéntricamente. Gurfinkel (1970) presenta un algoritmo
que permite obtener la posición del eje neutro y la presión máxima en zapatas rectangulares utilizando tres modelos de
distribución de presiones bajo la zapata. Kramrisch (1985) presenta ayudas para obtener las presiones máximas bajo
zapatas de forma rectangular, circular poligonal y en forma de anillo y fórmulas cerradas para obtener las presiones
máximas y mínimas bajo zapatas en forma de T sometidas a carga excéntrica, Hackman (1977) presenta un método para
obtener presiones de soporte bajo zapatas de puentes sometidas a flexión biaxial. Jarquio y Jarquio (1983) presentan
ayudas para dimensionar zapatas rectangulares bajo flexión biaxial. Highter y Anders (1985) presentan ayudas para
calcular el área efectiva a compresión en una zapata rectangular o circular bajo carga excéntrica (suponiendo que la
forma del bloque de presiones es prismática). Irles y Irles (1994) obtienen expresiones cerradas para calcular los
esfuerzos bajo una zapata rectangular con carga excéntrica.
Sin embargo, no siempre es posible construir zapatas rectangulares o circulares, ya sea por limitaciones de espacio o
por modificaciones de la geometría de la zapata después de construida. En ocasiones es necesario tener cortes o vacíos
(o agujeros) en zapatas originalmente circulares o rectangulares y se requiere conocer si la presión máxima transmitida
al suelo no supera la presión admisible del suelo con la nueva geometría. Existe poca información sobre la distribución
de presiones bajo zapatas superficiales de formas arbitrarias bajo flexión biaxial. Estos casos sólo pueden ser resueltos

1 Ingeniero Consultor, Calle 83 #45-29, Medellín-Colombia.
2
Profesor Generación 125-Años, Facultad de Minas, Universidad Nacional, Medellín-Colombia. E-mail: jdaristi2@yahoo.com

Rev. Int. de Desastres Naturales, Accidentes e Infraestructura Civil. Vol. 4(1) 67

<!-- p. 2 -->

suponiendo que la zapata es una placa sobre fundación elástica ("mat foundation") utilizando programas de elementos
finitos o diferencias finitas, o utilizando los momentos de inercia de la zapata; herramientas no siempre disponibles en
las oficinas de ingeniería. Bowles (1977) presenta un ejemplo de distribución de presiones bajo una zapata con un corte
(con una carga axial aplicada en el centroide de la zapata cuadrada original, pero al hacerse el corte cambia el centroide
de la zapata y se produce flexión biaxial).
La flexión biaxial es un efecto que no puede ser ignorado al dimensionar zapatas, ya que no es posible garantizar que
solamente carga axial es transmitida por la estructura al suelo de fundación. Esta situación generalmente ocurre en
pilares de puentes, chimeneas altas y edificios sometidos a cargas de viento o terremotos y estructuras de contención.
Cuando la excentricidad de la carga axial es a lo largo del eje de simetría se genera flexión uniaxial alrededor del eje
normal. Ahora se genera flexión biaxial cuando existen momentos alrededor de los ejes globales XY o cuando sólo
existe momento flector en uno de los ejes, pero la forma de la zapata es asimétrica. Para el caso biaxial, sería
conveniente generalizar las ayudas de diseño existentes para el cálculo de las presiones máximas bajo una zapata para
las formas geométricas más utilizadas, y para las formas geométricas no convencionales presentar un modelo fácil de
programar. Estos son precisamente los dos objetivos de esta publicación.
El objetivo principal de esta publicación es presentar un método general para el análisis de zapatas de forma
arbitraria soportadas superficialmente por suelos elásticos bajo carga axial y flexión biaxial. El modelo propuesto calcula
la posición del eje neutro y la presión máxima en el suelo de contacto con la zapata. Tres modelos diferentes de
distribución de la presión de contacto son utilizados: uniforme, lineal, y parabólico. Además, se presentan una serie de
nomogramas y fórmulas (i.e., ayudas de diseño) para facilitar el análisis de zapatas rígidas de forma regular sujetas a
cargas axiales excéntricas. Para zapatas de forma irregular (con vacíos y discontinuidades) se presenta un algoritmo
basado en el método de la integral de Gauss. Se incluyen tres ejemplos numéricos para mostrar la capacidad del
algoritmo propuesto y verificar los resultados con los de otros métodos disponibles en la literatura técnica.

MODELO ESTRUCTURAL

Para calcular la presión máxima y la posición del eje neutro en una zapata superficial, se deberán resolver
simultáneamente las ecuaciones no lineales (2a)-(2c) en A, b y qo. “A” es la tangente del ángulo α de inclinación del
eje neutro con respecto al eje global X, “b” es el intercepto del eje neutro con el eje global Y y “q” es la presión máxima
bajo la zapata.
El modelo propuesto permite analizar zapatas con vacíos o agujeros. Cada vacío es tratado en forma idéntica al
perímetro exterior excepto que los vértices de cada vacío son numerados en sentido contrario a las agujas del reloj. Los
vacíos circulares son aproximados por polígonos de dieciséis lados y sus vértices son generados conocidos el radio y la
posición del centro del vacío respecto a los ejes globales XY. En el caso de vacíos rectangulares los vértices son
generados conocidos el ancho, largo y centro del agujero respecto a los ejes globales XY. Si la forma del vacío es
arbitraria, es necesario entrar las coordenadas de cada vértice. El modelo propuesto es similar al utilizado por Rodríguez
y Aristizabal-Ochoa (1999) para analizar o diseñar columnas de concreto reforzado.
Analicemos una zapata superficial de forma arbitraria que se muestra en la Figura 1a. La forma de la zapata es
aproximada por líneas rectas y la contribución del área efectiva a compresión consiste de trapecios formados por los
vértices utilizados para definir la forma de la zapata (con coordenadas Xi, Yi respecto al sistema global de ejes XY). El
centroide de la zapata es generalmente elegido como el origen del sistema de ejes X Y, aunque se puede seleccionar
algún otro punto.
El sistema local de ejes xy es formado por el eje neutro y por la línea normal bajada desde el vértice más alejado a
compresión (con coordenadas globales Xe, Ye). El sistema local xy es utilizado para definir las presiones bajo la zapata,
y también para efectuar las integraciones numéricas necesarias.
Dos vértices consecutivos i y i+1 definen la línea recta y = aix+bi en el sistema local xy, las dos líneas
perpendiculares trazadas desde los vértices i y i+1, el eje neutro x y la recta y = aix+bi definen un trapecio, para los
vértices que cumplen Yi>AXi+b

ABS ( AX e − Ye + b ) c = (1a)
2 A + 1

Xa = Xe+ c sinα (1b)

Ya = Ye− c cosα (1c)

ri = xi= (Xi−Xa)cosα+(Yi−Ya)cosα (1d)

Rev. Int. de Desastres Naturales, Accidentes e Infraestructura Civil. Vol. 4(1) 68

<!-- p. 3 -->

si = xi+1= (Xi+1−Xa)cosα+(Yi+1−Ya)sinα (1e)

yi = (Yi−Ya)cosα−(Xi−Xa)sinα (1f)

yi+1 = (Yi+1−Ya)cosα−(Xi+1−Xa)sinα (1g)

ai = (yi+1−yi)/(xi+1−xi) (1h)

bi = yi−aixi (1i)

Figura 1: modelo de una zapata superficial de forma arbitraria bajo flexión biaxial:
(a) Parámetros geométricos; y (b) Modelos de distribución de presiones bajo una zapata.

Cuando el eje neutro cruza el perímetro de la zapata, los puntos de intersección se encuentran como sigue:

Cuando Yi \< Yi+1, entonces: ri = −bi/ai (1j)

Cuando Yi > Yi+1, entonces: si = −bi/ai (1k)

Si después de elegir los ejes globales XY, se desea analizar la zapata para carga axial con excentricidades en los
cuadrantes 3 y 4, es necesario que los ejes roten de tal forma que las excentricidades queden en el primer o segundo
cuadrante con relación a la nueva orientación de los ejes como se muestra en la Figura 2.
Se denotara con Pn a la carga axial y con Pn, MnX = PneY, y MnX = PneX representan la carga axial y momentos
flectores nominales alrededor de los ejes X y Y, respectivamente. Estas cantidades se suponen conocidas. Las
ecuaciones de equilibrio producen:

tn
\= ∑ iP (2a) Pn i =1

tn tn tn
\+ cos α ∑ M = sin α ∑ M + Ya ∑ iP (2b) ix iy M nX i =1 i =1 i =1

tn tn tn
− sin α ∑ M = cos α ∑ M + X a ∑ iP (2c) ix iy M nY i =1 i =1 i =1

Rev. Int. de Desastres Naturales, Accidentes e Infraestructura Civil. Vol. 4(1) 69

<!-- p. 4 -->

Figura 2: Rotación de los ejes globales x y para considerar cargas con excentricidades
en los cuadrantes 3 y 4: (a) Posición original de los ejes XY; (b) Ejes X-Y rotados

En las ecuaciones (2ª)-(2c), Pi, Mix y Miy son las contribuciones del trapecio i a la carga axial y momentos flectores,
respectivamente (con respecto a los ejes locales x y). Estas tres cantidades pueden ser calculadas integrando sobre el área
de cada trapecio como sigue:

s i a i x + b i
P = q dy dx (3a) i ∫∫r i o

s a x +b i i i M = ∫∫r o q y dy dx (3b) ix i

s a x + b i i i M = q x dy dx (3c) iy ∫∫r o i

En el Apéndice I se presentan formas explícitas de las integrales anteriores para varios modelos de distribución de
presiones bajo la zapata (uniforme, lineal o parabólica) como lo muestra la Figura 1(b). La Figura 3 muestra el diagrama
de flujo utilizado en el análisis de una zapata bajo flexión biaxial.

AYUDAS GRÁFICAS

La Figura 4 muestra la variación de la presión máxima con la excentricidad para una zapata circular. Las Figuras 5
(a)-(c) muestran gráficas para calcular la presión máxima en una zapata rectangular bajo carga axial y flexión biaxial.
Las Figuras 6(a)-(c) muestran gráficas para calcular la presión máxima bajo una zapata en forma de anillo circular bajo
carga axial excéntrica.

Rev. Int. de Desastres Naturales, Accidentes e Infraestructura Civil. Vol. 4(1) 70

<!-- p. 5 -->

Figura 3: Diagrama de flujo del programa de computador.

Figura 4: Presión máxima bajo una zapata circular.

Rev. Int. de Desastres Naturales, Accidentes e Infraestructura Civil. Vol. 4(1) 71

<!-- p. 6 -->

Figura 5: Presión máxima bajo una zapata rectangular con distribución
de presiones: (a) uniforme; (b) lineal; y (c) parabólica.

Rev. Int. de Desastres Naturales, Accidentes e Infraestructura Civil. Vol. 4(1) 72

<!-- p. 7 -->

Figura 6: Presión máxima bajo una zapata de forma de anillo con distribución
de presiones: (a) uniforme; (b) lineal; y (c) parabólica.

Rev. Int. de Desastres Naturales, Accidentes e Infraestructura Civil. Vol. 4(1) 73

<!-- p. 8 -->

EJEMPLOS DE ANÁLISIS DE ZAPATAS IRREGULARES

Ejemplo 1

Este ejemplo ilustra cómo pueden construirse ayudas gráficas para calcular la presión máxima bajo una zapata en
forma de trapecio isósceles que son usualmente usadas como fundaciones combinadas. En este ejemplo ω=70°,
B2/B1=3. Los resultados se muestran en la Figura 7.

Figura 7: Ejemplo 1. Presión máxima bajo una zapata trapezoidal.

Ejemplo 2

Calcule la presión máxima de contacto entre el suelo y una zapata cuadrada con un corte en una esquina como se
muestra en la figura 8. Suponga que: L= 10 pies (3.048 m), y un corte de esquina de 3.0 × 1.50 pies (0.914 × 0.457 m).
La fuerza axial aplicada es de axial 540 kip (2,402.028 kN) localizada en el centro del cuadrado. Compare los resultados
calculados con los resultados presentados por Bowles (1977).

7.0 3.0

1.5
Y

5.0

10 X O
8.5

5.0

10
Dimensiones en pies
1 pie = 0.3048 m
Figura 8: Ejemplo 2. Zapata cuadrada con un corte en una esquina bajo flexión biaxial.

Rev. Int. de Desastres Naturales, Accidentes e Infraestructura Civil. Vol. 4(1) 74

<!-- p. 9 -->

Solución:

Bowles (1977) analizó este problema utilizando tres modelos diferentes: 1) la zapata como una zapata rígida y
obtuvo una presión contacto máxima en el vértice de 4 de magnitud 6.90 kip/pie2 (330.37 kN/m²); 2) la zapata como una
losa rígida (“mat foundation”) con la columna articulada en el extremo inferior y obtuvo una presión contacto máxima
en el vértice de 4 de magnitud 6.629 kip/pie2 (317.396 kN/m²); y finalmente 3) ) la zapata como una losa rígida (“mat
foundation”) con la columna empotrada en el extremo inferior y obtuvo una presión contacto máxima en el vértice de 3
de magnitud 5.755 kip/ft2 (275.549 kN/m² ). La localización del eje neutro no fue reportada o discutida por Bowles
(1977).
Este problema fue analizado con el algoritmo propuesto en esta publicación para zapatas irregulares con las tres
distribuciones de presión (uniforme, lineal y parabólica) suponiendo los siguientes valores iniciales: α = −30°, b = −4
pie (−1.219 m), y qo = 5.40 kip/pie2 (258.552 kN/m²).
Para el caso de distribución uniforme, la presión de contacto máxima fue en el vértice 2 de magnitud 5.929 kip/pie2
(283.88 kN/m²) y el eje neutro está localizado por α = −25.27° y b = −5.315 pies (−1.62 m). Para el caso de distribución
lineal, la presión de contacto máxima fue en el vértice 4 de magnitud 6.904 kip/pie2 (330.563 kN/m²) y el eje neutro esta
localizado por α=−39.55° y b=−36.387 pies (−11.09 m). Finalmente, para el caso de distribución parabólica, la presión
de contacto máxima fue en el vértice 4 de magnitud 6.798 kip/pie2 (325.488 kN/m²) y el eje neutro está localizado por
α = −39.51° con b = −18.752 pies (−5.715 m).

Ejemplo 3 (paso a paso)

Una zapata rectangular con L = 6.0 m, B = 4.0 m fue proyectada para soportar una carga axial Pn = 500 kN y
momentos flectores MnX= 300 kN-m y MnY= 500 kN-m. Después de proyectada, es necesario abrir dos vacíos y hacer
un corte para ubicar un equipo mecánico como se muestra en la Figura 9(a). Analice los efectos de los vacíos y el corte
en la presión máxima bajo la zapata.

4.5 1.5
Y 2
Y uniforme 1 1.0 8 7 6 2120
9 19
1.0 10 18 3 parabolico 11 17
lineal 1.0 2.0 1213 14 15 16
4.0 X O X O
22 25
0.7
23 24
0.7 1.2

5 4
6.0

Dimensiones en metros
(a) (b)

Figura 9: Ejemplo 3. Zapata con cortes y vacíos bajo flexión biaxial:
(a) Geometría de la zapata; (b) Vértices utilizados para aproximar la forma de la zapata.

Rev. Int. de Desastres Naturales, Accidentes e Infraestructura Civil. Vol. 4(1) 75

<!-- p. 10 -->

Solución:

Paso 1: El perímetro exterior y los vacíos son aproximados por polígonos. La enumeración de los vértices exteriores se
hace en el sentido de las agujas del reloj mientras los vértices de los vacíos en sentido contrario como se muestra en la
Figura 9(b).

Paso 2: Los cálculos fueron comenzados con los siguientes valores de las variables: α =50°; b = −1.0 m; qo = kPn/(LB),
donde k>1. En este caso k = 5.0 por lo tanto qo=104.166 kN/m².

Paso 3: Las sumatorias de las ecuaciones 2a-2c son calculadas para el perímetro exterior y los dos vacíos y los valores
se presentan en las Tablas 1-4. Utilizando las ecuaciones 1a-1c tenemos Xa = 0.254 m, Ya = −1.303 m, c = 3.583 m.

Tabla 1: Sumatorias de las ecuaciones 2a-2c para el borde exterior.

Sumatorias Uniforme Lineal Parabólica

(1) (2) (3) (4)

n t 1521.499 619.044 910.724
∑ P i
i = 1

n t 2218.476 1244.422 1621.970
∑ M ix
i = 1

n t −1166.147 −336.369 −566.323
∑ M iy
i = 1

Tabla 2: Sumatorias de las ecuaciones 2a-2c para el vacío circular.

Sumatorias Uniforme Lineal Parabólica

(1) (2) (3) (4)

n t −79.725 −57.462 910.724
∑ P i
i = 1

n t −102.493 −76.594 −88.221
∑ M ix
i = 1

n t 153.74 110.807 129.904
∑ M iy
i = 1

Tabla 3: Sumatorias de las ecuaciones 2a-2c para el vacío rectangular.

Sumatorias Uniforme Lineal Parabólica

(1) (2) (3) (4)

n t −51.041 −39.355 −44.735
∑ P i
i = 1

n t −84.762 −66.323 −74.843
∑ M ix
i = 1

n t −37.571 −28.969 −32.929
∑ M iy
i = 1

Rev. Int. de Desastres Naturales, Accidentes e Infraestructura Civil. Vol. 4(1) 76

<!-- p. 11 -->

Paso 4: Las ecuaciones 2a-2c son transformadas en las ecuaciones 10a-10c como se indica en el Apéndice II y se eligen
los incrementos de las variables para obtener las derivadas parciales de las funciones ƒ, g y h: ∆A = ∆Tanα = 1×10−4,
∆b = 1×10−4 m, y ∆q o= 1×10−4 kN/m2. Para los valores iniciales de las variables tenemos para el modelo uniforme:
f(A,b,qo) = 890.732 kN; g(A,b,qo) = −2.934 kN-m; h(A,b,qo) = −735.339 kN-m.

Utilizamos la ecuación (13) para calcular las derivadas parciales de f, g y h:

ƒA(A,b,qo) = 293.370 kN; gA(A,b,qo) = 391.160 kN-m; hA(A,b,qo) = −574.389 kN-m
ƒb(A,b,qo) = −349.624 kN/m; gb(A,b,qo) = −4.89x10−9 kN; hb(A,b,qo) = 293.37 kN
ƒqo(A,b,qo) = 13.351 m2; gqo(A,b,qo) = 2.851 m3; hqo(A,b,qo) = 11.859 m3

Tabla 4: Total borde exterior más vacíos.

Sumatorias Uniforme Lineal Parabólica

(1) (2) (3) (4)

n t 1390.732 522.226 798.624
∑ P i
i = 1

n t 2031.220 1101.503 1458.905
∑ M ix
i = 1

n t −1049.978 −254.531 −469.348
∑ M iy
i = 1

Paso 5: Ahora utilizamos para el modelo uniforme las ecuaciones 12a-12c

\293. 370 − 349. 624 13 .351
DET = 391. 160 0 .2 851 = 3,481,217.556
− 574. 389 293. 370 11. 859

− 890.732 − 349. 624 13 .351
1
D = .2 934 0 .2 851 = 0.431 A DET
735 .339 293. 370 11. 859

\293. 370 − 890. 732 13 . 351
1
D = 391. 160 .2 934 .2851 = 0.689 m b DET − 574. 389 735. 339 11 .859

\293. 370 − 349. 624 − 890 .732
1
D q = 391 . 160 0 .2 934 = −58.153 kN-m
o DET − 574 .389 293. 370 735 . 339

Rev. Int. de Desastres Naturales, Accidentes e Infraestructura Civil. Vol. 4(1) 77

<!-- p. 12 -->

Paso 6: Utilizamos las ecuaciones 11a-11c para corregir las variables

A2 = A1+DA= −1.191+0.431 = 0.760

b2 = b1+Db = −1.0 m+0.689 m = −0.311 m

qo2 = qo1 + Dqo = 104.166 kN/m2−58.153 kN/m² = 46.013 kN/m2

De forma similar, los cálculos de los pasos 4-6 pueden ser realizados para los modelos lineal y parabólico. Los pasos
2−6 descritos arriba se repiten, y se calcularon nuevos valores para A, b, q0 hasta que se alcanza la convergencia. Los
valores numéricos de las principales variables y la convergencia para los tres modelos se resumen en las Tablas 5 y 6.

Tabla 5: Parámetros importantes en la solución del problema del Ejemplo 3.

A= tan α b (m) qo (kN/m²)
Iteración Uniforme Lineal Parabólica Uniforme Lineal Parabólica Uniforme Lineal Parabólica

(1) (2) (3) (4) (5) (6) (7) (8) (9) (10)

Initial −1.191 −1.191 −1.191 −1.0 −1.0 −1.0 104.166 104.166 104.166
1 −0.760 −0.624 −0.731 −0.311 −1.652 −0.722 46.013 70.129 64.274
2 −0.687 −0.736 −0.723 0.049 −1.374 −0.625 49.855 74.596 66.010
3 −0.708 −0.731 −0.723 0.027 −1.337 −0.626 50.821 77.221 66.070
4 −0.709 −0.732 0.028 −1.338 50.841 77.225

Tabla 6: Error máximo en las ecuaciones (10a) y (10c).

Iteración Uniforme Lineal Parabólica

(1) (2) (3) (4)

Initial 890.732 313.212 519.320
1 51.966 102.524 10.943
2 26.181 15.329 0.662
3 0.340 0.184 1.2x10−4
4 1.3x10−4 4.2x10−5

RESUMEN Y CONCLUSIONES

Se propuso un modelo para encontrar la posición del eje neutro y la presión máxima bajo una zapata superficial
rígida de forma arbitraria sometida a carga axial y momentos flectores biaxiales se puede estudiar los efectos de vacíos
(agujeros) y cortes en zapatas rigidas. Las losas de fundación ("mat foundations") y zapatas combinadas pueden ser
analizadas reduciendo las cargas axiales y los momentos transmitidos por columnas o pilares, a una carga axial
resultante y momentos flectores netos y considerando que la zapata se comporta rígidamente.
La flexión biaxial es un efecto que no puede ser ignorado al dimensionar zapatas. Esta situación generalmente ocurre
en pilares de puentes, chimeneas, y en edificios sometidos a cargas de viento o terremotos y estructuras de contención.
Cuando la excentricidad de la carga axial es a lo largo del eje de simetría se genera flexión uniaxial alrededor del eje
normal. Cuando existen momentos alrededor de los ejes globales XY o cuando sólo existe momento flector en uno de
los ejes, pero la forma de la zapata es asimétrica ocurre flexión biaxial. Para el caso biaxial, se presentan ayudas de
diseño para el cálculo de las presiones máximas bajo zapatas con las formas geométricas más utilizadas, y para las
formas geométricas no convencionales se presenta un algoritmo basado en la integral de Gauss. Se presentan tres
modelos de distribución de presiones bajo la zapata. Los elementos matemáticos básicos del modelo se utilizan de tal
forma que pueda ser fácilmente programado. Tres ejemplos de zapatas irregulares incluyendo uno con detalles de
cálculo “paso a paso” son presentados.

Rev. Int. de Desastres Naturales, Accidentes e Infraestructura Civil. Vol. 4(1) 78

<!-- p. 13 -->

REFERENCIAS

Bowles, J. E. (1977). Foundation Analysis and Design, 2nd Ed., McGraw Hill, New York.
Gurfinkel, G. (1970). "Analysis of footings subjected to biaxial bending," Journal of the Structural Division, ASCE,
93(6), pp. 1049-1059.
Hackman, M. (1977). "Bearing pressures on bridge footings," Civil Engineering, (11), pp. 37-39.
Highter, W. H., y Anders, J. C. (1985). "Dimensioning footings subjected to eccentric loads," Journal of Geotechnical
Engineering Div., ASCE, 111(5), pp. 659-665
Irles, R., y Irles, F. (1994). "Explicit stresses under rectangular footings," Journal of Geotechnical Engineering.,
ASCE, 120(2), pp. 444-450.
Jarquio, R, y Jarquio, V. (1983). "Design footing area with biaxial bending," Journal of Geotechnical Engineering.
Div., ASCE, 109(10), pp.1337-1341.
Kramrisch, F. (1985). "Footings" Chapter 5 in Handbook of Concrete Engineering, Second Edition, M. Fintel, Editor,
Nostrand Reinhold Company, New York.
Plock, H. J. (1963). "Fast way to find Pressure under Footings," Engineering News-Record, April 25, pp 50-51.
Rodríguez, J. A., Aristizabal-Ochoa, Dario, J. (1999)."Biaxial interaction diagrams for short R/C columns of any
cross section,” Journal of Structural. Engineering, ASCE, 125(6), pp. 672-683.
Yen, J. R. (1991). "Quasi-Newton method for reinforced concrete column analysis and design," Journal of Structural.
Engineering, ASCE, 117(3), pp 657-666.
Zweig, A. (1966). "Eccentrically loaded trapezoidal or round footings," Proceedings ASCE, ST-1, pp. 161-168.

APÉNDICE I. DERIVACIÓN DE FORMAS EXPLÍCITAS PARA LAS INTEGRALES (3a)-(3b)

\1. Distribución uniforme de presiones bajo la zapata [q = q0]

Para ai = 0:
Pi = q0(si − ri)bi (4a)
1 2 M ix = q o ( is − ir ) ib (4b) 2
1 2 2 M iy = q o ( is − ir ) ib (4c) 2
Para ai ≠ 0:
⎡ a i is a iri ⎤
iP = q o is ( + ib ) − ir ( + ib ) (5a) 2 2 ⎢⎣ ⎥⎦
⎡ a i 3 3 ib 2 2 ⎤ M iy = q o ( is − ir ) + ( is − ir ) (5b) 3 2 ⎢⎣ ⎥⎦
q o 3 3 M (5c) ix = [( a i is + ib ) − ( a iri + ib ) ] 6 a i
\2. Distribución lineal de presiones bajo la zapata [q =qoy/c]
Para ai = 0:
1 2
iP = q o ( is − ir ) ib (6a) 2 c
1 3 M ix = q o ( is − ir ) ib (6b) 3c
1 2 2 2 M = q (s − )b (6c) iy 4c o i ir i
Para ai ≠ 0:
q o 3 3 ( a (7a) iP = [ i is + ib ) − ( a iri + ib ) ] 6 a c i

Rev. Int. de Desastres Naturales, Accidentes e Infraestructura Civil. Vol. 4(1) 79

<!-- p. 14 -->

q o 4 4 (7b) M = [(a isi + b )i − (a iri + b )i ] ix 12a c i
q o 3 3 M = (7c) iy (a isi + b )i (3a isi − b )i − (a iri + b )i (3a iri − b ])i 2 [ 24a c i
\3. Distribución Parabólica de presiones bajo la zapata [q= q0(y/c)½]
Para ai = 0
2 q o 3 / 2
iP = b i (s i − )ir (8a) 3 c
2q o 5/2 M = b (s − (8b) ix i i )ir 5 c
2q o 3/2 2 2 M = b (s − ) (8c) iy i i ir 3 c
Para ai ≠ 0:
4q o 5/2 5/2 (9a) iP = [ (a isi + b )i − (a iri + b )i ] 15a c i
4q o 7/2 7/2 (9b) M ix = [(a isi + b )i − (a iri + b )i ] 35a c i
4q o 5/2 5/2 M = (9c) iy (a isi + b )i (5a isi − 2b )i − (a iri + b )i (5a iri − 2b ])i 2 [ 105a c i

APÉNDICE II. ALGORITMO “QUASI-NEWTON” PARA LA SOLUCIÓN DE LAS ECUACIONES (2a)-(2c)

Para resolver el conjunto acoplado de ecuaciones (2a)-(2c) (las cuales son altamente no lineales), es necesario replantearlas como lo ha sugerido Yen (1991) en la siguiente forma:

ƒ(A, b, qo) = Pn −F(A, b,qo) = 0 (10a)

g(A, b, qo) = eY Pn −G(A, b,qo) = 0 (10b)

h(A, b, qo) = eX Pn −H(A, b,qo) = 0 (10c)

Las ecuaciones (11) son luego utilizadas para corregir cada una de las tres variables, así:

Aj+1 = Aj+DA

(11a)

bj+1 = bj+Db

(11b)

q o = q o + D qo (11c) j j +1

donde DA, Db y D q son los residuos después de cada iteración los cuales se pueden evaluar de las siguientes tres
o
expresiones:

Rev. Int. de Desastres Naturales, Accidentes e Infraestructura Civil. Vol. 4(1) 80

<!-- p. 15 -->

− f ( A, b , q o ) f b ( A, b , q o ) f qo ( A, b , q o ) 1
D A = − g ( A, b , q o ) g b ( A, b , q o ) g qo ( A, b , q o ) (12a) DET
qo ( A, b , q o ) − h ( A, b , q o ) hb ( A, b , q o ) h

f ( A, b , q o ) − f ( A, b , q o ) f q ( A, b , q o ) A
o 1
D = g A b ( A, b , q o ) − g ( A, b , q o ) g qo ( A, b , q o ) (12b) DET
h A ( A, b , q o ) − h ( A, b , q o ) h qo ( A, b , q o )

f A ( A, b , q o ) f b ( A, b , q o ) − f ( A, b , q o ) 1
g A D qo = ( A, b , q o ) g b ( A, b , q o ) − g ( A, b , q o ) (12c) DET
h o ) A ( A, b , q o ) hb ( A, b , q o ) − h ( A, b , q

donde DET es el valor numérico del determinante dado por la ecuación (12d).

f ( A, b, q ) f ( A, b, q ) f ( A, b, q )
A o b o q o
o
DET = g ( A, b, q ) g ( A, b, q ) g ( A, b, q ) (12d)
A o b o q o
o
h ( A, b, q ) h ( A, b, q ) h ( A, b, q )
A o b o q o
o

La fórmula de diferencias finitas (“central difference”) es utilizada para el cálculo aproximado de las derivadas
parciales como lo muestran la ecuación (13).

f ( A + ∆A, b , q ) − f ( A − ∆A, b , q o ) o ƒA(A, b, qo) = (13)
2 ( ∆A)

APÉNDICE III. NOTACIÓN

A = tan α;
ai = Tangente de la línea definida por los vértices i e i+1 de un trapecio i en el sistema x,y;
b = Intercepto del eje neutro con el eje Y
c = Distancia del vértice extremo a compresión (Xe, Ye) al eje neutro;
eX, eY = Excentricidades alrededor de los ejes XY;
nt = Número de trapecios usados para aproximar la zona de la zapata bajo compresión.
qo = Máxima presión bajo la zapata;
Xa, Ya = Coordenadas del origen O’ con respecto a los ejes globales XY;
Xe,Ye = Coordenadas del punto más alejado a compresión con respecto a los ejes globales XY;
α = Ángulo de inclinación del eje neutro con respecto al eje X;
θ = tan−1(MnX/MnY).

Rev. Int. de Desastres Naturales, Accidentes e Infraestructura Civil. Vol. 4(1) 81

<!-- p. 16 -->

Rev. Int. de Desastres Naturales, Accidentes e Infraestructura Civil. Vol. 4(1) 82
