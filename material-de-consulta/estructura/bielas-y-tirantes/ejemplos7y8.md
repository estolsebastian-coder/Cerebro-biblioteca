---
type: libro
title: "Ejemplos7y8"
author: "lauri"
categoria: "ESTRUCTURA"
paginas: 39
extraccion: "texto"
fuente: "local:E:/MATERIAL DE CONSULTA/ESTRUCTURA/BIELAS Y TIRANTES/Ejemplos7y8.pdf"
convertido: 2026-10-16
---

# Ejemplos7y8

> Texto extraído de `ESTRUCTURA\BIELAS Y TIRANTES\Ejemplos7y8.pdf` (39 páginas, texto). El PDF original está en el disco E: (MATERIAL DE CONSULTA); `<!-- p. N -->` marca el inicio de cada página.

<!-- p. 1 -->

Ejemplo 7: Modelo de bielas y tirantes para el tablero
de un puente atirantado

Robert B. Anderson

Sinopsis

Los modelos de bielas y tirantes hacen que el diseño de porciones de estructuras complejas
se pueda realizar de forma transparente. Este ejemplo, el tablero en la pila de un puente
atirantado, se desarrolla con el objeto de mostrar cómo se pueden utilizar los modelos de
bielas y tirantes para regiones que pueden estar sujetas a cargas cíclicas y cómo los
resultados de cargas alternantes se pueden superponer unos con otros. El tablero transmite
fuerzas desde el pilón, a través de una conexión integral con la superestructura, hacia los
pilares de apoyo. El tablero también crea un área para la transmisión de las fuerzas de la
superestructura. En este ejemplo se describe brevemente el desarrollo del modelo en base
al flujo de fuerzas percibido dentro de la estructura. Luego se detallan las armaduras de los
tirantes y se verifican las zonas nodales.

Robert B. Anderson es ingeniero calculista en jefe de URS Corporation, Tampa, Florida.
Recibió su Master en Ingeniería de la Universidad de Texas en Austin y su título de
Ingeniero Civil de la Universidad Estatal de Dakota del Sur. Durante su permanencia en la
Universidad de Texas sus investigaciones se concentraron en el ensayo a escala real de
modelos de bielas y tirantes para regiones nodales de hormigón. Posee experiencia tanto en
puentes de hormigón como en puentes de acero, desde estructuras de separación de poca
longitud hasta estructuras atirantadas de gran longitud.

<!-- p. 2 -->

Ejemplo 7: Modelo de bielas y tirantes para el tablero de un puente atirantado

1 Introducción y alcance

El objetivo de este ejemplo es demostrar cómo se puede usar el modelado mediante bielas
y tirantes para un área que puede sujeta a cargas cíclicas y cómo los resultados de cargas
alternantes se pueden superponer unos con otros. Este ejemplo, ilustrado en la Figura 7-1,
es un tablero de un puente atirantado. El tablero transmite las fuerzas desde el pilón, a
través de una conexión integral con la superestructura, hacia los pilares de apoyo
individuales. El tablero también crea un área para la transmisión de las fuerzas de la
superestructura. El detalle ampliado en la Figura 7-1 muestra cómo esta región se puede
modelar mediante un programa de análisis de pórtico plano o pórtico espacial y las fuerzas
de cuerpo libre que existen en las conexiones de los elementos. En la Figura 7-2 se ilustra
un corte de la estructura transversal al eje del puente.

AMPLIACIÓN
V N M TABLERO
PILON
20 ft. (6,1 m)
3 ft. (0,91 m) 14 ft. 3 ft. (0,91 m)
SUPERESTRUCTURA (4,3 m)

N N
ft. m)
V V
10 (3,1
M M

PILARES INFERIORES V N V N MODELO RETICULADO
SUBESTRUCTURA
M M
5 ft. (1,5 m) 15 ft. 5 ft. (1,5 m)
(4,6 m)

EJE TORRE
OHIO
EJE TORRE
KENTUCKY

EJE PILA DE
ANCLAJE
KENTUCKY EJE ANCLAJE
OHIO
EXPANSIÓN INTEGRAL INTEGRAL EXPANSIÓN

352,75 ft. 875,00 ft. 459,00 ft.
(107,5 m) (266,7 m) (139,9 m)

Figura 7-1: Disposición del tablero del puente

El alcance de este ejemplo se limita a desarrollar el modelo de bielas y tirantes para
transmitir las fuerzas del pilón a los pilares inferiores. No se investigarán los momentos,
cortes y cargas axiales desarrolladas en la parte superior de los pilares inferiores de la
subestructura, ilustrados en la Figura 7-1. La Figura 7-3 muestra un modelo de bielas y
tirantes para examinar las fuerzas de los elementos de la superestructura.
186

<!-- p. 3 -->

Ejemplo 7: Modelo de bielas y tirantes para el tablero de un puente atirantado

64,4 ft. (19,6m)
32,2 ft. (9,8m) 32,2 ft. (9,8m)

9 ft
(2,74 m)

2,5 ft. (0,76m) 2,5 ft. (0,76m)

2 ft. (0,61m) 2 ft. (0,61m)

PILON

ft.

TABLERO COLADO IN SITU VIGA CAJON 10,0 (3,1m)
PREMOLDEADA

EJE TIRANTE
TORRE Y PUENTE
12,5 ft. (3,8m) 12,5 ft. (3,8m) PILAR INFERIOR
25,0 ft. (17,6m)

Figura 7-2: Corte transversal

Potencialmente existen tirantes tanto en la parte superior como en la parte inferior de la
viga cajón debido a que la conexión integral es sometida tanto a momentos positivos como
a momentos negativos durante la etapa constructiva y bajo su estado de carga final. El
modelo de bielas y tirantes ilustrado en la Figura 7-3 produce solamente un tirante, ya sea
en la parte superior o inferior de la sección de la viga cajón, el cual se puede evaluar
aplicando un enfoque seccional (diseño tradicional a flexión) en vez de un modelo de
bielas y tirantes y tampoco será estudiado como parte de este ejemplo. Sin embargo, los
requisitos sobre armadura de los atirantes de cualquiera de estos casos omitidos se pueden
agregar al requisito derivado en el modelo de bielas y tirantes alternativo desarrollado en
este ejemplo.

8,5 ft. 8,5 ft.
(2,59m) (2,59m)

5
(Biela o Tirante)

3 4 ft.
N 2 8,5 (2,59m) N
V
V
1
(Biela o Tirante)
M a
10,0 ft 10,0 ft M b \< > M a
(3,05m) (3,05m)

Figura 7-3: Modelo de bielas y tirantes para transferencia de momentos
de la superestructura

187

<!-- p. 4 -->

Ejemplo 7: Modelo de bielas y tirantes para el tablero de un puente atirantado

2 Desarrollo y análisis del modelo de bielas y tirantes

Intuitivamente el diseñador puede visualizar una fuerza extendiéndose desde el pilón a los
pilares inferiores como se ilustra en la Figura 7-4 debido a la carga axial N. El aspecto más
difícil es derivar el flujo de fuerzas para los momentos y cortes (M y V) también
introducidos en la base del pilón. Un primer paso consiste en dividir la sección transversal
del pilón en cuatro segmentos.

M V
N

C C

C C

T T

T T

Figura 7-4: Flujo de las fuerzas del pilón en el tablero

Luego estos segmentos definirán puntos discretos (nodos) para el modelo de bielas y
tirantes. En la Figura 7-5 una fuerza unitaria descendente de 1000 kips (4448 kN) produce
en la sección transversal una presión uniforme (P/A) y el conjunto de fuerzas descendentes
discretas ilustradas en la Figura 7-5. Alternativamente, un momento unitario de 1000 kip-ft
(1356 kNm) produce tensiones de flexión (Mc/I) que también se representan de manera
discreta en la Figura 7-5. El equilibrio de momentos está asegurado; sin embargo, las
fuerzas dependen de la ubicación elegida para los nodos. En la Figura 7-6 se ha
desarrollado el modelo de bielas y tirantes que considera las fuerzas que se extienden del
pilón hacia los pilares inferiores. La Figura 7-7 muestra las dimensiones del modelo junto
con la numeración de los nodos y miembros, además de los casos de carga unitaria. Los
Nodos 5 a 7 en la parte superior del modelo corresponden a los puntos discretos derivados
del análisis de la sección transversal del pilón. El Caso de carga 1 muestra la situación para
la fuerza unitaria descendente de 1000 kips (4448 kN), mientras que el Caso de carga 2
muestra la carga para un momento unitario de 1000 kip-ft (1356 kNm).
El Caso de carga 3 se usa para la transferencia de las fuerzas de corte correspondiente a
fuerza de corte unitaria de 100 kips (445 kN) en la base del pilón. La Tabla 7-1 resume las
fuerzas desarrolladas en cada uno de los elementos del modelo de bielas y tirantes debido a
cada una de las cargas unitarias.

188

<!-- p. 5 -->

Ejemplo 7: Modelo de bielas y tirantes para el tablero de un puente atirantado

20,0 ft. (6,10 m)
X
3,0 ft. 7,0 ft. 7,0 ft. 3,0 ft.
Propiedades seccionales (0,91 m) (2,12 m) (2,12 m) (0,91 m)
en la base del pilón:
A = 106,6 ft^2 2,0 ft. ft. A2 = 14,0 ft^2 (1,30 m^2)
(9,90 m^2) (0,61 m) R=2
Ixx = 4544 ft^4 A1 = (0,61m) 25,3 ft^2 2,5 ft.
(39,2 m^4) (2,35 m^2) (0,76 m) 10,0 ft. y (3,05 m) 2,5 ft.
(0,76 m)
2,0 ft.
(0,61 m)

5,0 ft. 3,5 ft. 3,5 ft. 5,0 ft.
(1,52 m) (1,07 m) (1,07 m) (1,52 m)
Cuando N = 1000 k 237,4 k 262,7 k 262,7 k 237,4 k
(4448 kN) (1056 kN) (1168 kN) (1168 kN) (1056 kN)
N
σ =
50,5 k 21,6 k -21,6 k -50,5 k A Cuando M = 1000 k*ft.
(225 kN) (96,1 kN) (-96,1 kN) (-225 kN)
(1356 kN*m)
M c σ =
I

Figura 7-5: Representación discreta de las fuerzas

5,0 ft. 3,5 ft. 3,5 ft. 5,0 ft.
(1,52 m) (1,07 m) (1,07 m) (1,52 m)

9 10 11

7
m)
4 5 6 8 ft.
3 8,5 (2,59

1 2

10,00 ft. 10,00 ft.
(3,05 m) (3,05 m)

Figura 7-6: Modelo de bielas y tirantes para el tablero
(para transferencia de las fuerzas del pilón a la subestructura)

189

<!-- p. 6 -->

Ejemplo 7: Modelo de bielas y tirantes para el tablero de un puente atirantado

Caso de carga unitaria 1: 237,4 k 262,7 k 262,7 k 237,4 k
N = 1000 k (4448 kN) (1.056 kN) (1.168 kN) (1.168 kN) (1.056 kN)

50,5 k 21,6 k -21,6 k -50,5 k
Caso de carga unitaria 2: (225 kN) (96,1 kN) (-96,1 kN) (-225 kN)
M = 1000 k * ft (1356 kN * m)

25 k 25 k 25 k 25 k
Caso de carga unitaria 3: (111 kN) (111 kN) (111 kN) (111 kN)
V = 100 k (445 kN)
9 10 11

7

6 8 4 5
3

1 2

Figura 7-7: Aplicación de cargas unitarias

Cargas unitarias Cargas permanentes Sobrecargas

Axial Momento Corte Caso 1 Caso 2 Caso 1 Caso 2 Caso 3
unitaria unitario unitario Tiempo = Tiempo = Máxima Máxima carga Máximo Mínimo Máxima
(N) (M) (V) Día 1 Día ∞ carga axial momento Momento sobre-
permanente cargaMiembro
\-21.401 k = N -21.072 k = N (Mayor -1984 k = N -474 k = N -1525 k = N (Mayor
1000 k 1000 k-ft 100 k -17.793k-ft = M -19.450 k-ft = M tracción) -22.570 k-ft = M 17905 k-ft = M -37.856 k-ft = M tracción)
89 k = V 110 k = V 103 k = V -123 k = V 210 k = V

1 242,8 8,9 -67,5 5294,3 5214,8 5294,3 612,8 38,7 565,2 612,8

2 242,8 -8,9 -32,5 5008,6 4907,0 5008,6 247,2 314,4 -35,1 314,4

3 -241,1 -51,3 0,0 -6071,5 -6077,2 -6071,5 -1635,7 803,9 -2308,9 803,9

4 -330,7 0,0 -53,5 -7124,6 -7027,2 -7027,2 -710,9 -91,3 -616,1 -91,3

5 0,0 -28,0 55,1 -449,4 -484,1 -449,4 -575,1 433,6 -944,2 433,6

6 0,0 21,6 -42,5 346,9 373,7 373,7 444,0 -334,7 728,9 728,9

7 -330,7 0,0 53,5 -7030,4 -6910,2 -6910,2 -601,2 -222,2 -392,5 -222,2

8 -241,1 51,3 0,0 -4246,7 -4082,4 -4082,4 679,2 -1032,4 1573,7 1573,7

9 -41,9 -8,9 25,0 -1033,0 -1028,6 -1028,6 -258,4 109,0 -348,7 109,0

10 -242,8 8,9 -17,5 -5053,0 -4962,0 -4962,0 -298,9 -252,9 -70,1 -70,1

11 -41,9 8,9 -25,0 -760,2 -737,0 -737,0 92,2 -148,7 220,9 220,9

Tabla 7-1: Fuerzas en las bielas y tirantes para cargas unitarias y aplicadas

190

<!-- p. 7 -->

Ejemplo 7: Modelo de bielas y tirantes para el tablero de un puente atirantado

Los puentes atirantados se deben analizar para cientos de hipótesis de carga, incluyendo: 1)
cargas aplicadas permanentes, tal como los pesos propios, cargas de postesado y fuerzas
debidas a los efectos de la fluencia lenta y temperatura, y 2) cargas aplicadas transitorias
tales como las correspondientes a sobrecargas, cargas de viento y temperatura. El uso de un
enfoque con cargas unitarias ofrece una solución efectiva para desarrollar los efectos de
conjuntos de cargas a partir de los análisis globales. El modelo de bielas y tirantes ilustrado
en las Figuras 7-5, 7-6 y 7-7 continúan siendo válidos para todos los casos de cargas
siempre y cuando las bielas continúen siendo bielas (elementos comprimidos) y los tirantes
continúen siendo tirantes (elementos traccionados). También le permite al diseñador
apreciar las fuerzas desarrolladas en la conexión del tablero del puente en términos de las
fuerzas aplicadas. La Tabla 7-2 muestra un conjunto real de cargas y sobrecargas y su
sumatoria factoreada en base a los factores de carga de ACI. Como se puede observar, las
cargas descendentes de los pilones produjeron la mayor carga en cada una de las bielas y
tirantes.

Miembro Máxima carga Máxima Grupo 1
permanente sobrecarga (1,4D + 1,7L)
1 5294,3 612,8 8453,8
2 5008,6 314,4 7546,5
3 -6071,5 803,9 -7133,5
Fuerzas de diseño en
4 -7027,2 -91,3 -9993,1 los tirantes
5 -449,4 433,6 108,0*
6 373,7 728,9 1762,2
7 -6910,2 -222,2 -10.052,0 * La fuerza de tracción del
8 -4082,4 1573,7 -3040,1 Miembro 5 será cubierta por
armadura ortogonal de
9 -1028,6 109,0 -1254,8
temperatura y control de la
10 -4962,0 -70,1 -7066,0 retracción, no diseñada
11 -737,0 220,9 -656,2 explícitamente en el ejemplo.

Tabla 7-2: Fuerzas en las bielas y tirantes para cargas factoreadas

Obviamente pueden existir otras situaciones en las cuales una carga de vuelco, por ejemplo
debida al viento, podría desarrollar fuerzas de tracción en los elementos considerados
bielas. En este caso sería necesario desarrollar modelos alternativos.

3 Detallado de los tirantes y nodos

Este ejemplo se centra en el desarrollo de un modelo para analizar una estructura compleja
mediante un único modelo de bielas y tirantes y casos de carga unitaria que se combinan
para obtener los efectos de las cargas combinadas. Una vez desarrolladas las fuerzas en las

191

<!-- p. 8 -->

Ejemplo 7: Modelo de bielas y tirantes para el tablero de un puente atirantado

bielas y tirantes para cada una de las combinaciones de cargas, es posible dimensionar los
elementos individuales para que resistan estas fuerzas y comenzar un análisis detallado de
las regiones nodales. Puede ocurrir que la peor condición de cada uno de los elementos
individuales del modelo de bielas y tirantes sea provocada por diferentes combinaciones de
cargas. El diseñador sólo debe seleccionar las máximas fuerzas desarrolladas en los tirantes
bajo las diferentes combinaciones de cargas. A continuación presentamos el cálculo de las
armaduras requeridas (acero dilce y postesado).

4 Cálculos para dimensionar los tirantes y verificación de zonas
nodales

Tirante 1
Fuerza de diseño factoreada = Fut = 1,4 D + 1,7 L = 1,4 (5294,3 k) + 1,7 (612,8 k)
\= 8453,8 k (37.600 kN)

φ = 0,75 Sección 9.3.2.6
Seleccionar 60 barras de pretensado de 1-1/4" (32 mm) de diámetro.
Aps = 60 * 1,25 in.2 / barra = 75,0 in.2 (48.400 mm2)
fpy = 150 ksi (1034 MPa)
fse = 0,6 * 150 ksi = 90 ksi (621 MPa)
∆fp = 60 ksi (414 MPa) (adherente)
φFnt = φ (Astfy + Aps (fse + ∆fp)) Sección A.4.1
\= 0,75 (0 + 75,0 in.2 (90 ksi + 60 ksi))
\= 8437,5 k (0,2% sobretensado ~ Verifica)

Tirante 6
Fuerza de diseño factoreada = Fut = 1,4 D + 1,7 L = 1,4 (373,7 k) + 1,7 (728,9 k)
\= 1762,2 k (7838 kN)

φ = 0,75 Sección 9.3.2.6
Seleccionar 5 capas separadas 1'-0'' (305 mm) de 18 barras por capa de estribos #6 (19
mm)
En la Figura 10-8 se detallan
16 capas en 15'-0'' (4,57 m)
Aps = 5 * 18 * 0,44 in.2 / barra = 39,6 in.2 (25.550 mm2)
fy = 60 ksi (414 MPa)

192

<!-- p. 9 -->

Ejemplo 7: Modelo de bielas y tirantes para el tablero de un puente atirantado

φFnt = φ (Astfy + Aps (fse + ∆fp)) Sección A.4.1
\= 0,75 ((39,6 in.2) 60 ksi + 0)
\= 1782,0 k > 1762,2 k ~ Verifica
Distribuir esta armadura a cada lado del pilón correspondiente a la línea de centro de la
torre para tomar en cuenta un modelo alternativo (no ilustrado en este ejemplo) que es
imagen especular del seleccionado.

Zona nodal en la intersección de los miembros 2, 7 y 8

Fcu = 0,85 βn f'c Sección A.5.2
βn = 0,80
fc' = 5,5 ksi (38 MPa)
Fcu = 0,85 * 0,80 * 5,5 ksi = 3,74 ksi (25,8 MPa)

Verificación de la tensión en el nodo:
Ancho de la porción del
tablero colado in situ

σ = 8437,5 k / ((3 ft. * 12 in./ft.) * ( 20 ft. * 12 in./ft.)) = 0,98 ksi \< 3,74 ksi ~ Verifica

En la Figura 7-8 se ilustra el dimensionamiento de esta armadura. Se usan tres capas de
barras postesadas de 1-1/4" (32 mm) de diámetro para proveer el elemento resistente para
las fuerzas desarrolladas en los Miembros 1 y 2 del modelo de bielas y tirantes. Para el
Miembro 6 se proveen 18 estribos #6 (19 mm) cada 1"-0' (305 mm) de longitud. Estos
estribos se proveen a ambos lados de la línea de centro del pilón para tomar en cuenta el
modelo alternativo, imagen especular del modelo seleccionado. La cantidad de estribos
provista es mayor que la requerida, pero garantiza ductilidad al corte de la sección para
recorridos de cargas alternativos que podrían coexistir con el modelo seleccionado para
este ejemplo.

193

<!-- p. 10 -->

Ejemplo 7: Modelo de bielas y tirantes para el tablero de un puente atirantado

Tirante 6: estribos #6 (diam. 19mm)
con separación de 1'-0"
(18 estribos por espacio)
15´-0" (4,57 m)

9 10 11

4 7 5
6 8
3

ft. m) 1 2
3,0 (0,91

Tirante 1: Tres capas de Nodo CCT
barras de postensado
1-1/4 in. (diam. 32 mm)

Figura 7-8: Detallado de los tirantes y del Nodo CTT

5 Resumen

El Ejemplo 7 presenta un modelo de bielas y tirantes para una situación que existe en un
puente atirantado diseñado con pilón central y pilares duales para la subestructura. Este
ejemplo se centra en los recorridos de carga necesarios para transferir las cargas del pilón a
los pilares inferiores y cómo tratar de manera efectiva y eficiente los múltiples casos de
cargas que ocurren en las estructuras complejas.

194

<!-- p. 11 -->

Ejemplo 8: Muro de gran altura con dos aberturas

Robert W. Barnes

Sinopsis

En este ejemplo se resume la aplicación de los nuevos requisitos de ACI 318-02 sobre
modelado mediante bielas y tirantes a un muro con dos aberturas. Debido a que las
aberturas constituyen una porción significativa del muro, las versiones anteriores del
Código no contienen lineamientos relevantes para garantizar que el muro provea
resistencia adecuada a las cargas aplicadas. Es raro encontrar ejemplos de la aplicación de
modelos de bielas y tirantes para casos con cargas múltiples y/o cargas laterales. El muro
de este ejemplo se diseña para resistir múltiples combinaciones tanto de cargas
gravitatorias como de cargas laterales en el plano.
Se resume la construcción del modelo de bielas y tirantes para cada combinación de
cargas. Además, se discute el empleo de modelos de bielas y tirantes estáticamente
indeterminados para mejorar la eficiencia y serviciabilidad del diseño del muro. El ejemplo
también cubre la selección y el anclaje de las armaduras de los tirantes, como así también
verificaciones de la capacidad de las bielas y zonas nodales.

Robert W. Barnes recibió sus títulos M.S.E. y Ph.D. de la Universidad de Texas en
Austin. Se desempeña como Profesor Adjunto en el Departamento de Ingeniería Civil de la
Universidad de Auburn. Es miembro del Comité Conjunto ACI-ASCE 423, Hormigón
Pretensado, y miembro asociado del Comité Conjunto ACI-ASCE 445, Corte y Torsión.

<!-- p. 12 -->

Ejemplo 8: Muro de gran altura con dos aberturas

1 Geometría, materiales y cargas

Un muro de 16 in. (405 mm) con una altura de 640 in. (16,26 m) y un ancho de 320 in.
(8,13 m) contiene dos aberturas cuadradas de 120 in. (3,05 m) de lado como se ilustra en la
Figura (8-1). La resistencia de diseño del hormigón es de 4000 psi (26 MPa), y la
resistencia a la fluencia de diseño del acero es de 60.000 psi (410 MPa). El recubrimiento
mínimo es de 2 in. (50 mm). El muro se diseñará para las siguientes hipótesis de cargas
factoreadas:

− Hipótesis de carga 1: dos cargas verticales de 450 kips (2,0 MN).
− Hipótesis de carga 2: dos cargas laterales de 170 kips (0,76 MN) actuando del lado
derecho del muro.
− Hipótesis de carga 3: combinación de las cargas de las Hipótesis 1 y 2.
− Hipótesis de carga 4: dos cargas laterales de 170 kips (0,76 MN) actuando del lado
izquierdo del muro.
− Hipótesis de carga 5: combinación de las cargas de las Hipótesis 3 y 4.

100" 100"
(2540 mm) (2540 mm)

450 kips 450 kips
(2000 kN) (2000 kN)
170 kips 170 kips 508 20"
(760 kN) (760 kN)
120" (3048)

mm)
(6604 260"
120" (3048)
mm)

170 kips 170 kips (16.256 640" (2032)
80" (760 kN) (760 kN)

120" (3048)

mm)
(9144 360"

200" (5080)

20" 20"
280"
(508) (7112 mm) (508)

40" 120" 120" 40"

(1016) (3048) (3048) (1016)
Figura 8-1: Geometría y cargas del muro

196

<!-- p. 13 -->

Ejemplo 8: Muro de gran altura con dos aberturas

El muro está soportado por dos zapatas. La superficie de contacto disponible en cada
apoyo es de 16 in. (406 mm) de ancho (el espesor del muro) y 40 in. (1,02 m) de longitud,
de manera que el centro de cada apoyo está ubicado como se indica en la Figura (8-1). El
muro se idealiza como simplemente apoyado. Bajo la influencia de las cargas laterales
factoreadas se anticipa la fisuración del hormigón sobre el apoyo traccionado. La rigidez
de este hormigón con respecto a las fuerzas laterales será considerablemente menor que la
del hormigón sobre el apoyo comprimido. Por lo tanto, se confía en el apoyo comprimido
para transferir a la fundación todas las fuerzas laterales por fricción por corte.

2 Procedimiento de diseño

Debido a las aberturas y a las cargas y apoyos concentrados, la totalidad del muro
constituye una región D. ACI 318-99 provee pocos lineamientos para este tipo de
estructuras. El diseño se basa en el nuevo Apéndice A − Modelos de Bielas y Tirantes de
ACI 318-02 según lo permitido por la Sección 11.10.1 de dicho documento. A menos que
se especifique lo contrario, todas las futuras referencias incluidas en este ejemplo
mencionan secciones específicas de ACI 318-02.
El primer paso del diseño consiste en concebir un modelo de bielas y tirantes para cada una
de las hipótesis de carga. Otros pasos incluyen seleccionar la armadura de los tirantes,
verificar la capacidad de las zonas nodales y asegurar el correcto anclaje de la armadura de
los tirantes en los nodos.

3 Modelado

En las Figuras (8-2) a (8-6) se ilustran los modelos de bielas y tirantes para las cinco
hipótesis de carga. Las bielas se representan mediante líneas discontinuas, mientras que los
tirantes se representan mediante líneas llenas. Las bielas y tirantes se ubicaron
considerando: 1) los probables recorridos de las cargas hacia los apoyos, y 2) patrones de
armadura ortogonales.
El modelo para la Hipótesis de carga 1 es estáticamente indeterminado. Por lo tanto, las
fuerzas en las bielas y tirantes no se pueden determinar exclusivamente en base a la
condición de equilibrio. Durante el diseño preliminar el modelo se desarrolló asumiendo
que aproximadamente el sesenta por ciento de cada carga vertical viajaba alrededor del
contorno de la abertura debajo de dicha carga, mientras que el cuarenta por ciento restante
de ambas cargas pasaba a través de la región comprendida entre ambas aberturas. Luego
las bielas se ubicaron de manera de satisfacer esta hipótesis y la condición de equilibrio, a
la vez que exhibiendo claramente el flujo de cada fuerza hacia los apoyos. La hipótesis se
adoptó simplemente en base al criterio profesional respecto de cómo podrían fluir los
recorridos de las fuerzas alrededor de las aberturas. Siempre y cuando el modelo resultante
satisfaga el equilibrio y que las bielas, tirantes y zonas nodales satisfagan los requisitos del
Apéndice A, la estructura debería desarrollar la resistencia última requerida.

197

<!-- p. 14 -->

Ejemplo 8: Muro de gran altura con dos aberturas

Aunque no es necesario para el diseño por resistencia, se realizó un análisis lineal elástico
de tensiones planas por elementos finitos a fin de refinar el modelo y lograr mejor
comportamiento bajo condiciones de servicio. Grandes disparidades entre el modelo de
bielas y tirantes y la distribución de tensiones elásticas provocarán gran fisuración a
medida que la estructura se deforme para redistribuir las cargas de acuerdo con el patrón de
armaduras. Además, los modelos de bielas y tirantes que se ajustan a la distribución de
tensiones elásticas requieren menos armadura que los que no lo hacen [Schlaich, Schäfer y
Jennewein (1987)]. Se optó por un análisis por elementos finitos lineal porque éste ofrece
una adecuada indicación de la distribución de tensiones bajo cargas de servicio. También, a
criterio del ingeniero, se podría haber usado un análisis no lineal.

450 kips 450 kips

20" 40" 40" 28" 20" 72" 80" 20"

84 20"
136 53 161 245
290 160 190 260 85"

T1 T2 T3
136 84 215

190 260 150" 290 160

232 94 T4
232 198 104
290 160 190 260 50"
T5 138 T6
232 94 104 104

190 260 160 260 150""

0 29
T7 135 29

290 260
160 190
135 179" 106

T8 135
6"

20" 151,2" 28,2" 80" 20" 20"
450 kips) 450 kips
Figura 8-2: Modelo de bielas y tirantes para la Hipótesis de carga 1

198

<!-- p. 15 -->

Ejemplo 8: Muro de gran altura con dos aberturas

Como resultado del uso del análisis por elementos finitos sólo se modificaron ligeramente
la geometría del modelo y las fuerzas. Por ejemplo, el análisis por elementos finitos indica
que aproximadamente 58 por ciento de la carga de la derecha viaja alrededor del contorno
de la abertura superior y 64 por ciento de la carga de la izquierda viaja alrededor del
contorno de la abertura inferior, no 60 por ciento como supusimos anteriormente para
ambos casos. El modelo final se ilustra en la Figura (8-2).
En la Figura (8-2) la porción de la carga que pasa entre las dos aberturas en la Hipótesis de
carga 1 se divide en dos recorridos claramente diferenciados para aclarar cómo cada una de
las cargas de 450 kips (2,0 MN) viaja alrededor de cada abertura y se dirige a la fundación.
Esta diferenciación no es necesaria; en la parte central del modelo los dos recorridos se
podrían haber unificado. Por motivos de simplicidad, en los demás casos de carga no
hemos intentado separar la influencia de las dos cargas verticales en la región entre las
aberturas.
La necesidad de transformar las cargas laterales en reacciones verticales aumenta la
dificultad de visualizar los recorridos de las cargas para las Hipótesis de carga 2 a 5. En las
Figuras (8-3) a (8-6) se muestran los modelos de bielas y tirantes finales seleccionados. El
deseo de disponer armadura ortogonal hizo que los modelos correspondientes a estos casos
resultaran relativamente complejos. El requisito (A.2.4) que establece que las bielas no se
deben cruzar ni superponer impidió que formáramos los modelos para la combinación de
las Hipótesis de carga 3 y 5 simplemente superponiendo los modelos para las hipótesis más
elementales (1, 2 y 4). El requisito A.2.5 que establece que los ángulos formados por bielas
y tirantes deben ser mayores o iguales que 25 grados también condicionó la construcción
de partes de estos modelos. Finalmente, se hizo un esfuerzo por obtener consistencia en la
ubicación de los tirantes en las cinco hipótesis de carga. Aunque esto puede provocar un
grado de complejidad adicional a la hora de refinar los modelos de bielas y tirantes
individuales, también simplifica el proceso de selección de las armaduras (Sección 3) y
aumenta la eficiencia del diseño final.
Al igual que para la Hipótesis de carga 1, todos los modelos para las restantes hipótesis de
cargas son estáticamente indeterminados. Aunque para estas hipótesis es posible construir
modelos estáticamente determinados, para esta estructura no es recomendable hacerlo
debido a que estos modelos difieren considerablemente del flujo elástico de fuerzas. A
modo de ejemplo se puede considerar la Hipótesis de carga 2. Para este caso se podría
haber construido un modelo estáticamente determinado omitiendo el tirante (T1) del lado
derecho de la abertura superior y ajustando la geometría del modelo del lado izquierdo de
la abertura. Si usáramos este modelo sería dable anticipar grave fisuración en la región del
tirante omitido, posiblemente bajo condiciones de servicio. De hecho, el diseñador estaría
confiando en la región a la izquierda de la abertura para resistir las cargas aplicadas sin
ninguna contribución de la región del tirante omitido. El modelo estáticamente
determinado sería menos eficiente; la armadura adicional requerida para reforzar y
extender T2 y T4 a la izquierda de la abertura sobrepasaría en mucho la armadura que se
ahorraría al eliminar T1. Por lo tanto, aunque el empleo de un modelo indeterminado

199

<!-- p. 16 -->

Ejemplo 8: Muro de gran altura con dos aberturas

aumenta la complejidad del proceso de modelación, es posible que mejore la eficiencia y
serviciabilidad de la estructura.
20" 120" 40" 80" 40" 20"

20"170 kips
170
69 65"
T1

69
170
170 T2 120"

170
T3
50"
170 T4 243194
170 142 243 194
121 170 25" 170 kips
T13170 364 106 219 175 25"
T6 81 T8
76 T9 364 T7 40
75" 152 274
81 219
T10 449 312
287 T11
106 T12 75"
340 22 106
T13 T14
22

T15 146 312
283 146 595 165" 106
255

T16

106
20"

340
595
148,6" 60" 60" 20"
685 kips
595 kips

Figura 8-3: Modelo de bielas y tirantes para la Hipótesis de carga 2

El análisis de un modelo estáticamente indeterminado requiere determinar un número
suficiente de fuerzas redundantes para poder calcular las fuerzas restantes simplemente en
base a consideraciones de equilibrio. El procedimiento general usado para las Hipótesis de
carga 2 a 5 consiste en seleccionar las fuerzas en los elementos redundantes necesarios y
luego determinar el resto de las fuerzas de manera de satisfacer la condición de equilibrio.
Las bielas o tirantes ubicadas en las secciones de 40 in. (1,02 m) de ancho adyacentes a las
aberturas se seleccionaron como redundantes. Al igual que en la Hipótesis de carga 1, la

200

<!-- p. 17 -->

Ejemplo 8: Muro de gran altura con dos aberturas

magnitud de la fuerza en cada biela o tirante redundante se estimó en base a un análisis
plano por elementos finitos de la estructura.
También se podría haber usado cualquier otra estimación racional para las fuerzas
redundantes. La exactitud de la estimación sólo afectaría la eficiencia y serviciabilidad del
diseño. Nuevamente se empleó un análisis lineal por elementos finitos para obtener una
estructura eficiente y con buena serviciabilidad, sin hacer el diseño más difícil de lo
necesario. 450 kips 450 kips
20" 5" 35" 40" 40" 80" 40" 40" 20"

104 170 20"
170 kips 245 158 54 260 179 114 336 190 85"

T1 T2
117 40 179

336 46
53 329 100"
190
T3
151 19
177 85"
381 212 61
152 170 85"
106
T4 T5 293 84 25"
231 79 38 T6
152 35 19 75"
71 354
558 38 283
T7
188
425 75"

340 6
T8 270 T9

558
487
125 179" 430
84
6

T10 84

340
158,05" 60" 60" 20"
1045
145 kips
1099 kips

Figura 8-4: Modelo de bielas y tirantes para la Hipótesis de carga 3

201

<!-- p. 18 -->

Ejemplo 8: Muro de gran altura con dos aberturas

20" 100" 175" 25"

170 kips 103 20"
67 103
57 50
57 T1 50 T2 85"

T3 T4
171 104
171
171 7
228 T5 100"

T6
64 50
268 T740 75"
64 107
1
170 kips 178
27 170 25"
T8
341
471
295
226 T9 150"

291 340
T10 T11

291
49
300 300 74 165" 521
595 T12 T13

291 20"

340
20" 160" 108,6" 11,4" 595
595 kips 685 kips

Figura 8-5: Modelo de bielas y tirantes para la Hipótesis de carga 5

202

<!-- p. 19 -->

Ejemplo 8: Muro de gran altura con dos aberturas

450 kips 450 kips
20" 80" 40" 80" 80" 20"

170 160 20" 170 kips

135 145 292
143 307 140 370 85"
132
T1 T2
305 292

170 447
213 310 150"
70 T3

146 124 30 472 T4 25"
170 kips 590 310
4 24 124 25" T5 124

23
510 150"
103 340 310

118 273
T6 T7

67
122 122 165" 118 225 820
145 155
T8 T9

118 20"

340
20" 160" 113,5" 1045
145 kips

1099 kips

Figura 8-6: Modelo de bielas y tirantes para la Hipótesis de carga 5

203

<!-- p. 20 -->

Ejemplo 8: Muro de gran altura con dos aberturas

Para limitar la fisuración y satisfacer los requisitos sobre armadura mínima, se debería
incluir armadura ortogonal mínima (Secciones A.3.3.1 y A.3.3.2). Debido a que en los tres
modelos hay bielas con diferentes orientaciones, la manera más sencilla de satisfacer la
Ecuación A-4 es disponiendo una cantidad de armadura que satisfaga la expresión
A si ≥ 0,003
bs
en cada dirección ortogonal. Una malla de barras #5 con una separación de 12 in. (300
mm) en cada dirección en cada una de las caras del muro satisface esta expresión. Esta
disposición también satisface los requisitos sobre armadura mínima de las Secciones 11.8,
11.10 y 14.3 de ACI 318-02. Una vez dispuesta la armadura mínima que satisface A.3.3, al
calcular la resistencia efectiva del hormigón en las bielas (fcu) de manera conservadora se
puede asumir para βs un valor de 0,75 (A.3.2). Hay una excepción en los nodos que anclan
más de un tirante (nodos CTT). Para el extremo de una biela que ingresa a un nodo CTT,
fcu se debería calcular usando un valor de βn igual a 0,60 (A.3.1, A.5.2). El nodo ubicado
inmediatamente por encima del apoyo derecho en la Hipótesis de carga 3 es un ejemplo de
este tipo de nodo.

3 Cálculo de las armaduras de los tirantes

Como no hay armadura pretensada, la sección de acero requerida para cada tirante se
calcula usando la expresión
Fu
A st, req =
φf y
donde φ = 0,75. Por ejemplo, los tirantes más resistentes requeridos son T16 de la
Hipótesis de carga 2 y T12 de la Hipótesis de carga 4. La fuerza de tracción factoreada en
cada uno de estos tirantes es de 595 kips (2,65 MN); por lo tanto se requieren 13,2 in.2
(8520 mm2) de armadura. Colocando once barras #7 en cada cara del muro se obtiene una
armadura total en los tirantes de 13,2 in.2. Con una separación de 3,5 in. (89 mm) entre
barras la fuerza en los tirantes se distribuye en al menos 35 in. (890 mm). Todos los
tirantes se dimensionan de manera similar. La Figura (8-7) es un resumen gráfico de los
requerimientos en todos los tirantes, considerando todas las hipótesis de carga. En esta
figura todos los tirantes tienen tres números entre paréntesis. Estos tres números
representan la hipótesis de carga crítica, la carga factoreada (kips) y la sección de armadura
(in.2) requerida para cada tirante, respectivamente. Al establecer modelos de bielas y
tirantes para múltiples hipótesis de carga se debe hacer un esfuerzo por seleccionar para los
tirantes ubicaciones que sean consistentes para las diferentes hipótesis. Si esto se logra, a
menudo la armadura de los tirantes se puede utilizar eficientemente para más de una
hipótesis de carga. La Figura (8-8) ilustra una potencial configuración de las armaduras
que satisface los requisitos dados en la Figura (8-7). Las líneas discontinuas representan
armadura mínima no asignada a ningún tirante en particular.
204

<!-- p. 21 -->

Ejemplo 8: Muro de gran altura con dos aberturas

20" 100" 20" 40" 80" 40" 20"

20"
1.27) 1.11)
65"
57, 50,
(4, (4,
(5, 305, 6.78) (5, 292, 6.49) 20"

5.07) 2.24) 100"
228, 101, 1.53)
(4, (2, 69, (2, 170, 3.78)
(2,
5.96) 50" 5.40)
268, (5, 124, 2.76) 243, 25" (4, (2, 3.89)
(1, 232, 5.15) (2, 364, 8.09) 25"
175,
(3, 283, 6.29)
(2, 8.09)
6.56) 364, 75" (2, (2, 81,1.80) 9.98)
295, 449, (4, 6.38) (2,
75"
287,
(2,

(4, 291, 6.47) (4, 340, 7.56)

6.67) 13.2) 13.2)
300, 595, 179" 595,
(4, (2, (4,

(1, 135, 3.00)
6"

20" 160" 60" 60" 20"

Figura 8-7: Requisitos críticos en los tirantes (hipótesis de carga, Fu, Ast, req)

205

<!-- p. 22 -->

Ejemplo 8: Muro de gran altura con dos aberturas

Aº mínima:
\#5 @ 12" máx. c.c.
en ambas direcciones

\#5 @ 3,5"c.c.
8 #6 @ 3,5" c.c.
7 #5 @ 4" c.c.

5 #5 @ 6" c.c.

Aº mínima
más 2 #7 c.c.

Aº mínima
más 3 #7 c.c.

7 #7 @ 4" c.c.

7 #7 @ 5,5" c.c.
11 #5 @ 3,5" c.c.
7 #7 @ 4" c.c.

Aº mínima
más 1 #5 c.c.

11 #7 @ 3,5" c.c.

3 #7 @ 3" c.c.

Figura 8-8: Configuración de las armaduras del muro (c.c. = cada cara del muro)

206

<!-- p. 23 -->

Ejemplo 8: Muro de gran altura con dos aberturas

4 Zonas nodales y superficies de apoyo

Una inspección de los modelos de bielas y tirantes correspondientes a las cinco hipótesis
de carga revela que la región de apoyo crítica está en el apoyo comprimido cuando el muro
está sometido a las Hipótesis de carga 3 ó 5. Para la Hipótesis de carga 3 el apoyo
comprimido es el de la izquierda. En la Figura (8-9) se ilustra la zona nodal
correspondiente. Debido a que la zona nodal representa la intersección de cuatro fuerzas,
para facilitar su visualización se la ha subdividido en dos subnodos conectados mediante
una biela. Cada subnodo representa la intersección de tres fuerzas. De este modo se pude
construir la geometría de toda la zona nodal usando las relaciones fundamentales para
nodos con tres fuerzas [Schlaich y Anagnostou (1990)]. Toda la zona nodal consiste en dos
subnodos más la biela interna.

Fu = 558 kips

uF = 650 kips

Fu = 18,8 in.
Ac = 300 in.2 ws = 21,9 in.
φFns = 574 Ac = 350 in.2
kips φFns = 670
kips

wn = 37,9 in.
An = 607 in.2
φFnn = 1240
kips Fu= 1128 kips

Fu = 84 kips ht = 12 in.
Ast = 3,60 in.2
φFnt = 162 kips

al = 40,4 in > l d = 36,3 in

wn = 38,0 in.
An = 608 in.2
φFnn = 1240 kips

Fu = 1099 kips

Figura 8-9: Zona nodal en el apoyo comprimido (Hipótesis de carga 3)

La geometría del subnodo inferior está definida por el ancho de apoyo disponible igual a
40 in. y el espesor de 12 in. supuesto para el tirante horizontal, el cual consiste en tres

207

<!-- p. 24 -->

Ejemplo 8: Muro de gran altura con dos aberturas

barras #7 en cada cara. La magnitud (1128 kips [5,02 MN]) y ángulo de inclinación (67,9º
respecto de la horizontal) de la fuerza en la biela interna se obtienen a partir de la
condición de equilibrio. El ancho disponible de esta biela interna (37,9 in. [963 mm]) se
puede obtener considerando el ancho de la otra biela y tirante así como los ángulos
comprendidos entre las tres fuerzas. A continuación el subnodo superior se construye como
un nodo "hidrostático", asumiendo que las tensiones en las dos bielas exteriores son iguales
a la tensión en la biela interna. En consecuencia, las longitudes de cada lado de este
subnodo son proporcionales a la fuerza soportada por la biela correspondiente. De la
condición de equilibrio, las rectas de acción del tirante y de todas las bielas coinciden en el
punto nodal. En la Figura (8-9) se indican los valores obtenidos para el ancho, la
superficie, la carga factoreada y la resistencia factoreada de cada biela y cada tirante.
En el subnodo inferior hay que verificar la capacidad de apoyo del muro con respecto a la
reacción de apoyo. Debido a la inclinación de la reacción en el apoyo, el ancho disponible
de la zona nodal perpendicular a la reacción en la biela está dado por:
 1045 
w n = 40 in.   = 38,0 in. (966 mm)
 1099 
Luego la superficie disponible de la zona nodal con respecto a la reacción es:
An = (38,0 in.) (16 in.) = 608 in.2 (0,393 m2)
El nodo ancla un tirante (nodo CCT). Por lo tanto se selecciona un valor βn = 0,80. La
resistencia efectiva a la compresión del hormigón de la biela es:

fcu = 0,85 βn fc' = 0,85 (0,80) (4000 psi) = 2,72 ksi (18,8 MPa)
La resistencia nominal factoreada de la zona nodal con respecto a la fuerza de reacción es:
φ Fns = φ fcu Ac = 0,75 (2,72 ksi) (608 in.2) = 1240 kips ≥ Fu = 1099 kips
Aparentemente la superficie de apoyo es suficiente para proveer una resistencia adecuada.
Sin embargo, las caras del subnodo limitadas por la biela interna están sujetas a una fuerza
mayor (1128 kips [5,02 MN]) que la cara inferior de la zona nodal. Como se indica en la
figura, la capacidad de estas caras también es adecuada.
La componente horizontal de la reacción en este apoyo es transferida a la zapata mediante
fricción por corte. Cuando se diseña de acuerdo con los requisitos de la Sección 11.7.4 de
ACI 318-02 la cantidad de armadura de fricción por corte está dada por:
Vu 340 kips 2 2
A vf , req = = = 12,6 in. (8120 mm )
φ f y µ (0,75) (60 ksi) (0,6)
Para µ se adoptó un valor conservador de 0,6. Entonces al menos 12,6 in.2 (8120 mm2) de
armadura debe atravesar la junta y estar desarrollada adecuadamente tanto en la zapata
como en el muro. Este requisito quedará satisfecho por los 13,2 in.2 (8520 mm2) de
armadura de tracción dispuestos como armadura para los tirantes para las otras hipótesis de
carga.

208

<!-- p. 25 -->

Ejemplo 8: Muro de gran altura con dos aberturas

Dimensionar las placas de apoyo (o las superficies de apoyo) para las cargas aplicadas es
menos complicado. En este caso también se utilizó la totalidad del espesor del muro (16
in.). Debido a que la biela ingresa a un nodo solicitado exclusivamente a compresión y es
demasiado angosta para expandirse de manera significativa, para cada carga de 450 kips se
puede seleccionar un valor de 1,0 para βs y βn. El ancho requerido para la placa de apoyo
para cada una de estas cargas está dado por:
Fus 450 kips w ≥ = = 11,0 in. (280 mm)
φ b f cu 0,75 (16 in.) (3,4 ksi)

Por lo tanto seleccionamos placas de apoyo de 11 in. x 16 in. (280 mm x 406 mm). Para las
cargas laterales de 170 kips se puede efectuar un cálculo similar. Para una hipótesis de
carga cada una de las cargas laterales próximas a la parte superior del muro ingresa
inmediatamente a un nodo que ancla un tirante (nodo CCT), de manera que para calcular
fcu se debería seleccionar un valor βn = 0,80. Como resultado se obtiene un ancho requerido
de 5,21 in. (132 mm). Sin embargo, para las cargas de 170 kips inferiores se debería
seleccionar un valor βn = 0,60 porque para una hipótesis de carga cada carga ingresa a un
nodo CTT. Se requiere un ancho de placa de 6,94 in. (176 mm). Por motivos de
simplicidad, para todas las cargas laterales seleccionamos placas de apoyo de 7 in. x 16 in.
(178 x 406 mm).
Las zonas nodales y superficies de apoyo descriptas constituyen las áreas comprimidas más
críticas en los cinco modelos de bielas y tirantes. A pesar de la presencia de las dos
aberturas hay suficiente espacio para proveer anchos adecuados para todas las demás bielas
y nodos de los diferentes modelos.

5 Anclaje de las armaduras de los tirantes

La Figura (8-10) ilustra la geometría de la zona nodal inmediatamente por encima del
apoyo izquierdo bajo la influencia de la Hipótesis de carga 1. Esta hipótesis produce la
demanda crítica de tracción en el tirante horizontal. Para este tirante la armadura se
seleccionó de acuerdo con el procedimiento discutido en párrafos precedentes. La zona
nodal se dimensionó como se describe en la sección anterior. Debido a que la relación
entre la separación de las barras y el diámetro de las mismas es pequeña, la armadura para
este tirante requiere la mayor longitud de desarrollo de todas las barras del muro, a pesar
de que a la armadura horizontal ubicada a mayor altura le corresponde el factor de
ubicación de las armaduras (α) igual a 1,3 (Sección 12.2.4). Despreciando cualquier
potencial beneficio de la armadura transversal, la longitud de desarrollo (ld) para las barras
\#7 separadas 3 in. (76 mm) entre centros es:
3 f y αβγλ 3 60.000 1
l d = = (0,875 in.) = 36,3 in. (0,92 m)
\+ K tr  40 4000 1,71 40 f c'  c  
 d b 

209

<!-- p. 26 -->

Ejemplo 8: Muro de gran altura con dos aberturas

Como se ilustra en la Figura (8-10), este valor es menor que la longitud de anclaje
disponible (la) igual a 39,8 in. (1,01 m) (A.4.3(b)). Por lo tanto, para este tirante el
desarrollo de las barras es adecuado.
En general, en este diseño no es difícil asegurar el correcto anclaje de las armaduras. Los
tamaños de las barras y las separaciones son tales que las longitudes de desarrollo
requeridas son menores que las longitudes de anclaje disponibles. Todos los demás nodos
están ubicados a una distancia de al menos 15 in. de las superficies del muro, de manera
que hay suficiente espacio para el desarrollo de las barras #5, #6 y #7 dentro de las zonas
nodales y detrás de las mismas (A.4.3), que típicamente se extienden entre 30 y 40 in.
(0,76 - 1,02 m). Si hubiéramos seleccionado barras de mayor tamaño es posible que
hubiera sido necesario utilizar ganchos o anclajes mecánicos.
Cuando se terminan armaduras que ya no son requeridas, tales como las barras verticales
\#7 a lo largo de los límites del muro, hay que tener cuidado de extender estas barras a
través de la totalidad de la zona nodal en la cual ya no son requeridas. También se deben
prolongar al menos una distancia igual a la longitud de desarrollo más allá del punto en el
cual ingresan a la zona nodal extendida.
Fu = 290 kips

ws = 25,8 in. Fu = 209 kips
Ac = 412 in.2
φFns = 788 kips
ws = 18,6 in.
Ac = 297 in.2
φFns = 569 kips

ws = 41,76 in.
An = 668 in.2
φFnn = 1360 kips
Fu = 470 kips

ht = 12 in.
Fu = 135 kips Ast = 3,60 in.2
φFnt = 162 kips

l a = 39,8 in > l d = 36,3 in

wn = 40,0 in.
An = 640 in.2
φFnn = 1310 kips
Fu = 450 kips
Figura 8-10: Zona nodal en el apoyo (Hipótesis de carga 1)

210

<!-- p. 27 -->

Ejemplo 8: Muro de gran altura con dos aberturas

Resumen

Se presenta el diseño de un muro de hormigón armado con dos grandes aberturas. El muro
se diseña de acuerdo con los requisitos del nuevo Apéndice A − Modelos de Bielas y
Tirantes de ACI 318-02. Se discuten temas relacionados con el uso de modelos
indeterminados y la aplicación de modelos de bielas y tirantes para múltiples hipótesis de
carga. Luego de considerar modelos de bielas y tirantes para todas las hipótesis carga se
seleccionan las armaduras para los tirantes. Se ilustra la verificación de la capacidad de las
bielas y zonas nodales, y se incluye un ejemplo de la verificación del anclaje de los
tirantes. La longitud de anclaje es adecuada para todos los tirantes; no se requieren ganchos
ni dispositivos de anclaje especiales.

Notación

A menos que a continuación se especifique lo contrario, la notación corresponde a la
utilizada en ACI 318-02.
Ast, req = sección de armadura requerida en el tirante
Avf, req = sección de armadura de friccón por corte requerida
la = longitud de anclaje del tirante disponible en una zona nodal

Referencias

ACI 318-99: Building Code Requirements for Structural Concrete. ACI Committee 318,
American Concrete Institute, Farmington Hills, Michigan 1999
ACI 318-02: Building Code Requirements for Structural Concrete. ACI Committee 318,
American Concrete Institute, Farmington Hills, Michigan 2002
Schlaich, J.; Schäfer, K. y Jennewein, M. (1987): Toward a Consistent Design of Structural
Concrete. PCI Journal Vol. 32 (1987), No. 3, p. 74-150
Schlaich, M. y Anagnostou, G. (1990): Stress Fields for Nodes of Strut-and-Tie Models.
Journal of Structural Engineering Vol. 116 (1990), No. 1, p. 13-23.

211

<!-- p. 28 -->

Ejemplo 8: Muro de gran altura con dos aberturas

212

<!-- p. 29 -->

Ejemplo 9: Cabezal de pilotes

Gary J. Klein

Sinopsis

El siguiente ejemplo ilustra el uso de modelos de bielas y tirantes para el diseño de un
cabezal de pilotes. Se consideran dos hipótesis de carga: 1) carga axial exclusivamente, y
\2) carga axial y momento de vuelco. El diseño se basa en el Apéndice A de ACI 318-02.
Los resultados se comparan con los procedimientos de diseño seccional según ACI 318-99.
En comparación con los métodos de diseño seccionales, el diseño mediante modelos de
bielas y tirantes es más racional y conduce a estructuras más confiables. Debido a que las
barras de armadura están ubicadas encima de los pilotes, la profundidad total del cabezal es
mayor que en el caso del diseño tradicional en el cual las barras se colocan entre pilotes.

Gary J. Klein, FACI, es Vicepresidente Ejecutivo de Wiss, Janny, Elstner Associates Inc.,
Northbrook, IL, donde ha llevado a cabo investigaciones estructurales relacionadas con
edificios, puentes y estructuras para estacionamiento, entre otras. Es miembro de los
Comités ACI 318, Código de Construcción de Hormigón Estructural; ACI 342, Evaluación
de Puentes y Elementos de Puentes de Hormigón; ACI 345, Construcción, Mantenimiento
y Reparación de Puentes de Hormigón; ACI 445, Corte y Torsión; y ACI 546, Reparación
del Hormigón.

<!-- p. 30 -->

Ejemplo 9: Cabezal de pilotes

1 Geometría y cargas

3´6" 2´ 0" 3´6"
(1067 mm) (610) (1067 mm)
9´ (2744)
Mu

Pu
14´ (356 mm)

14"

9´

1´ 6" 3´ 6" 3´ 6" 1´ 6"
(457) (1067) (1067) (457)

a) Elevación b) Planta

Figura 9-1: Vista en elevación y planta

Datos generales
Cabezal fc' = 4000 psi
Columna fc' = 6000 psi
Armadura fy = 60.000 psi
Pilotes (14 in. x 14 in.) Tolerar = 70T (140k)

Hipótesis de carga 1:
PD = 445k MD = 0
PL = 222k ML = 0
Pu = 1,4PD + 1,7PL = 1000k

Hipótesis de carga 2:
PD = 445k MD = 0
PL = 104k ML = 282 ft-k
Pu = 800k Mu = 480 ft-k

Factores de carga y factores φ:
\- Según ACI 318-99, Capítulo 9.

214

<!-- p. 31 -->

Ejemplo 9: Cabezal de pilotes

\- Según ACI 318-02, Apéndice C.

Reacciones en los pilotes

P M
R = +
N SM
d 2 4 × 32 ∑SM pilotes = = = 12
d 3
Fila Hipótesis P/N M/SM Total Factoreada
1 133 0 133 200
Izquierda
2 110 24 134 200
1 133 0 133 200
Central
2 110 0 110 160
1 133 0 133 200
Derecha
2 110 -24 86 120
Tabla 9-1: Reacciones en los pilotes

2 Diseño seccional según ACI 318-99

Corte
Sección crítica en la cara de la columna: Vu = 2 x 200k = 400k

Vu ≤φ Vc = φ 2 f c' bd = 0,85 × 2 4000 × 108d ≥ 400.000 #

⇒ d ≥ 34,4" ∴ usar h = 39"; d = 39 − 3 − 1,5 = 34,5"

Flexión
Mu = 400k x 2 ft = 800 ft − k; Intentar 12 #7. As = 7,2 in.2
ρ = As / bd = 0,0019; ρmin = 0,0018 ⇒ Verifica

φ Mn = 0,9 x 7,2 x 60 x 34,5 (1 − 0,59 x 0,0019 x 60 / 4) = 13.200 in. − k = 1099 ft − k
⇒Verifica

Desarrollo de las armaduras

60.000
Barras #7 rectas: A d = × 0,875 = 41,5"
20 4000

Barras #7 con gancho: A db = 1200db / 4000 = 16,6"
215

<!-- p. 32 -->

Ejemplo 9: Cabezal de pilotes

Aunque las barras rectas se pueden desarrollar totalmente en la distancia hasta la cara de la
columna, usar barras con gancho siguiendo las prácticas habituales.

Fisuración
Verificar tensión por flexión bajo cargas de servicio en la cara de la columna:
SM = 9 x 3,252 / 6 = 15,8 ft4

Ms = 133k x 2 x 2' = 532 ft−k ft = 532 / 15,8 = 33,7 ksf = 233 psi ≈ 3,7 f c'

∴ Es poco probable que haya fisuración.

3 Modelo de bielas y tirantes según el Apéndice A de ACI 318-02
(Hipótesis 1)

200 200 200
200 200
14"

29" a

35,3°

200 200
b 200

200 200

Biela a: 346k Compresión
Tirante b: 200k Tracción

Figura 9-2: Modelo de bielas y tirantes

Biela a = 200/sin 35,3 = 346k Compresión
Tirante b = 346 cos 35,3/ 2 = 200k Tracción
Biela c = 200k Compresión

216

<!-- p. 33 -->

Ejemplo 9: Cabezal de pilotes

Armadura del tirante
φPnt = φ Ast fy ≥ Pu ⇒0,85 Ast 60 ≥ 200 ⇒ Ast ≥ 3,92 in.2
Usar 6 barras #8 (Ast = 4,32 in.2) ó 9 barras #6 (Ast = 3,96 in.2)

φ 0,85 β fc' Elemento Tipo β
(ksi)
Zona comp. 1,0 2,89
Bielas
En forma de botella 0,6 1,73
CCC 1,0 2,89
Nodos CCT 0,8 2,31
CTT 0,6 1,73

Tabla 9-2: Elementos

Biela:

346
A cs req = = 200 1,73

Acs = 14 h2 = 14 (14 sin 35,3 + h1 cos 3,5)
⇒h1 = 7,6" h2 = 14,3"

346k h2
35,3º

h1
Tu

14"

Figura 9-3: Nodo inferior

217

<!-- p. 34 -->

Ejemplo 9: Cabezal de pilotes

24"
A

A
1
a

A 2

PLANTA

h 3

1 h2 h

CORTE A

Figura 9-4: Nodo superior

Tirante traccionado:
200 2
Tu = 200k H c req = = 3,92 in. 0,85 × 60

Usar 6 barras #8 en dos capas a 2 in. y 6 in. sobre el cabezal.
Verificación de la longitud de desarrollo: A db = 1200 × 1,0/ 4000 = 19,0 in. ⇒ Verifica

Armadura mínima: ρmin = 0,0018
Separación máxima = 18 in.
A s 0,44Usar barras #6 separadas 6 in. entre pilotes ρ = = = 0,0019
bd 6 × 39

218

<!-- p. 35 -->

Ejemplo 9: Cabezal de pilotes

Nodo superior:
Pu 200 2
A1 = = = 116 in.
φ f cs 1,73
A2 = (242 − 116) / 4 = 115 in.2

Suponemos que las diagonales son cuadradas:

h 2 = 346/1,73 = 14,1"

h 3 = 115/14,1 = 8,2"

h 2 = h 3 sin35,3 + h 1 cos35,3
⇒ 1h = 11,5"

Verificación biela d:

346cos35,3
f cn =
14,1 × 11,5
\= 1,74 ksi \< 2,89

a = ( 116 / 2 + 8,2/ 2) / 2
\= 6,70" (7"supuesto)

Altura total del cabezal de pilotes = 29" + empotram. pilote + (h1/2)inf. + (h1/2)sup.
\= 29 + 9 + 7,6/2 + 11,5/2 = 47,5"
Usar 4' 0" = 48"

219

<!-- p. 36 -->

Ejemplo 9: Cabezal de pilotes

4 Modelo de bielas y tirantes según el Apéndice A de ACI 318-02
(Hipótesis 2)

366
160 (46)
366 (46)
j

d
f
e
a a 29,2º

35,3º
g
200 56º
120

b 160

200
120
Biela d: 246k Compresión
Tirante e: 46k Tracción
Biela f: 51k Compresión
Biela g: 31k Compresión
Tirante h: 200k Tracción
Biela j: 320k Compresión

Figura 9-5: Modelo de bielas y tirantes

Nodo inferior
Según el Caso 1

220

<!-- p. 37 -->

Ejemplo 9: Cabezal de pilotes

14" (supuesto para el modelo)
13,4" (real)

Baricentro
C
A

B

C

10,5" 5"

Figura 9-6: Nodo superior

Suponiendo que las bielas son cuadradas:

h 2 = Pu / φ f cs

φ f cs × h 2 × h 3 ≥ Pu sin θ
⇒ h 3 ≥ Pu sin θ /( φ f cs h 2 )

h 2 = h 3 sin θ + h 1 cos θ
⇒ h 1 = (h 2 − h 3 sin θ) / cos θ

Biela Nodo Pu φ fcs h2 θ φ fcn h3 h1 h2 x h3
Cent. B 160 1,73 9,6 90 2,89 9,6 0,0 92
a C 346 1,73 15,4 35,3 2,89 4,9 13,9 69
d C 246 1,73 13,0 29,2 2,89 3,5 11,7 42
f C 51 1,73 5,9 64,2 2,89 2,9 6,4 16
Total = A + B + 2C = 120 + 92 + 2 x 127 = 466

Tabla 9-3: Valores en los nodos

Sección total de columna disponible = 242 = 576 in.2 > 466 in.2
Altura total del cabezal de pilotes = 29" + empotram. pilote + (h1/2)inf. + (h1/2)sup.

221

<!-- p. 38 -->

Ejemplo 9: Cabezal de pilotes

\= 29 + 9 + 7,6/2 + 13,9/2 = 48,8"
Usar 4' 0" = 48"

5 Resumen

0"
4´

Figura 9-7: Diseño mediante modelos de bielas y tirantes de acuerdo con ACI 318-02

3"
3´

Figura 9-8: Diseño seccional de acuerdo con ACI 318-99

222

<!-- p. 39 -->

Ejemplo 9: Cabezal de pilotes

COMPARACIÓN
Modelo de bielas y tirantes de Diseño seccional de acuerdo
Método:
acuerdo con ACI 318-02 con ACI 318-99
Altura del cabezal 4' - 0" 3' - 3"
12 barras #8 concentradas sobre los 12 barras #7 en cada
Armadura pilotes y 9 barras #6 (temperatura) dirección entre pilotes
entre pilotes, en cada dirección

Tabla 9-4: Comparación

6 Conclusiones

\1. Los modelos de bielas y tirantes son aplicables al caso de cabezales de pilotes
sometidos a carga vertical y momento de vuelco.
\2. El diseño depende del criterio profesional.
\3. Se requieren cálculos detallados en los nodos a fin de determinar la altura de los
mismos y, consecuentemente, los detalles de las armaduras y altura del cabezal; sin
embargo, es necesario adoptar algunas hipótesis simplificadoras:

− Es necesario asumir tirantes cuadrados para simplificar la geometría donde se
intersecan bielas en tres dimensiones.

− Se deben despreciar las diferencias geométricas entre las bielas y los nodos (pero se
deben realizar verificaciones para asegurar que el baricentro está ubicado
correctamente y que el área del nodo es suficiente).
\4. En comparación con los diseños tradicionales en los cuales la armadura se ubica entre
los pilotes, el diseño mediante modelos de bielas y tirantes da por resultado mayor
altura del cabezal y cantidad de armadura.
\5. El diseño mediante modelos de bielas y tirantes es más racional y conduce a
comportamientos más confiables.

223
