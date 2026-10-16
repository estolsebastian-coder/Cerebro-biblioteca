---
type: libro
title: "capitulo7"
author: "Nayeli Rodriguez"
categoria: "AYUDAS DE PROGRAMAS"
paginas: 14
extraccion: "texto"
fuente: "local:E:/MATERIAL DE CONSULTA/AYUDAS DE PROGRAMAS/COMPUTERS AND STRUCTURES/capitulo7.pdf"
convertido: 2026-10-16
---

# capitulo7

> Texto extraído de `AYUDAS DE PROGRAMAS\COMPUTERS AND STRUCTURES\capitulo7.pdf` (14 páginas, texto). El PDF original está en el disco E: (MATERIAL DE CONSULTA); `<!-- p. N -->` marca el inicio de cada página.

<!-- p. 1 -->

CAPÍTULO VII

LOSAS DE CIMENTACIÓN

7.1 INTRODUCCIÓN

Por último, se presentan las losas de cimentación que están clasificadas dentro de las

zapatas combinadas. Como en los capítulos anteriores, se hará énfasis en su definición,

empleo, clasificación y secuencia de cálculo para el análisis y diseño de las mismas.

Figura 7.1 Ejemplos de zapatas combinadas

7.1.1 DEFINICIÓN Y EMPLEO DE UNA LOSA DE CIMENTACIÓN

Una losa de cimentación se define como una estructura que puede soportar varias columnas

o muros al mismo tiempo. Se emplean cuando la capacidad de carga del suelo es muy baja

y las zapatas aisladas resultan demasiado grandes y juntas para ser una opción viable.

76

<!-- p. 2 -->

Figura 7.2 Losa de cimentación

7.1.2 CLASIFICACIÓN DE LAS LOSAS DE CIMENTACIÓN

Dentro de esta se encuentra una gran variedad, pero usualmente se emplean las siguientes:

Losa de cimentación con espesor uniforme: Se caracteriza por sólo tener los refuerzos de

acero y el espesor determinado por los cálculos sin ningún tipo de alteración.

77

<!-- p. 3 -->

Figura 7.3 Planta y corte de una losa de cimentación con espesor uniforme

Losa de cimentación aligerada: Este tipo de losa se caracteriza por disminuir el volumen

de concreto a utilizar, debido a que sólo se emplea el espesor determinado en las secciones

críticas determinadas en el diseño; el resto se disminuirá hasta donde permita el esfuerzo

cortante involucrado en el diseño.

78

<!-- p. 4 -->

Figura 7.4 Planta y corte de una losa de cimentación aligerada

Losa de cimentación nervurada: A diferencia de la losa aligerada aquí sólo se emplean

vigas, las cuales corren sobre los ejes eje X e Y generando así cajones entre columnas. Con

esta forma se disminuye mucho más el volumen de concreto a utilizar como se ve en la

figura siguiente.

79

<!-- p. 5 -->

Figura 7.5 Planta y corte de una losa nervurada

7.2 SECUELA DE CÁLCULO

En este caso es necesario calcular la presión que se ejerce en cada una de las columnas o

muros involucrados, para así determinar el peralte efectivo necesario (d) y seguir un

procedimiento muy similar al de una zapata combinada.

7.2.1 DETERMINACIÓN DE LOS VALORES CONSTANTES

Para poder comenzar el análisis y diseño de una losa de cimentación es necesario conocer:

\- Dimensiones de la losa: Largo (L) y ancho (B)

\- Distancia entre columnas o muros en ambos ejes (X e Y)

80

<!-- p. 6 -->

\- El valor de las cargas o pesos a soportar (P1, , Pn o W1, , Wn), usualmente se reportan

los valores correspondientes a cargas muertas (CM) y cargas vivas (CV).

Se determina la resultante y punto de aplicación de todas las cargas aplicadas en las

columnas y la losa de cimentación se considera una enorme zapata aislada para fines de

análisis.

7.2.2 ANÁLISIS DE LA LOSA

Debido a que se conocen las dimensiones de la losa, sólo queda determinar el peralte

efectivo a utilizar (d), y para esto, es necesario realizar lo siguiente:

a) Obtención de la carga o peso resultante (PR)

PR PCM PCV

b) Momentos de inercia (Ix, Iy)

BL3
I x 12

LB 3
I y 12

c) Excentricidades (ex y ey)

Debido a que se obtuvo una carga resultante, es necesario referenciarla con respecto al

centro geométrico de la losa; por tanto, se utilizará un nuevo eje de coordenadas. Con

respecto al eje inicial, se seguirá utilizando, pero ahora se considerará como un eje

secundario y será denotado como el eje X e Y , como se ve en la siguiente figura.

81

<!-- p. 7 -->

Figura 7.6 Referencia del nuevo eje de coordenadas (X, Y)

Para poder saber el punto geométrico de la carga resultante (PR) es necesario

calcular momentos con respecto al eje, inicial ahora el eje (X , Y ).

M 'x 0 ; PR x ' P1 x1' P2 x 2' P3 x 3' ... Pn x n' 0

M 'y 0 ; PR y ' P1 y1' P2 y 2' P3 y 3' ... Pn y n' 0

La forma de obtener las excentricidades con respecto al centro geométrico de la losa

es la siguiente:

B
ex x ' 2

L
ey y ' 2

82

<!-- p. 8 -->

d) Momentos (Mx, My)

Para poder calcular los momentos, es necesario factorizar la carga resultante y esto se

obtiene de la siguiente manera:

PRF 4.1 PCM 7.1 PCV

Ya factorizada la carga, se procede a calcular los momentos en X e Y.

M x PRF * e y

M y PRF * e x

e) Obtención de la presiones en cada uno de los puntos (qn)

Para poder determinar la presión en cada uno de los puntos, se tendrá que ser muy

cuidadoso en tomar el signo de los momentos involucrados ya que, dependiendo del punto

que se vaya analizar, las fibras de éste pudieran estar en tensión o compresión. Siendo así, a

continuación se muestran imágenes que pueden servir de guía para tomar en cuenta los

signos del momento.

83

<!-- p. 9 -->

Figura 7.7 Comportamiento de las fibras con respecto a un momento positivo en X

Figura 7.8 Comportamiento de las fibras con respecto a un momento positivo en Y

84

<!-- p. 10 -->

Con esta guía sólo es necesario aplicar los signos correspondientes en la siguiente

fórmula.

PRF M y x M x y q n
A I y I x

Donde:

A = área de la losa B*L

x = Distancia que hay del centro geométrico al punto en la dirección X

y = Distancia que hay del centro geométrico al punto en la dirección Y

PRF = Carga resultante factorizada

Mx = Momento con respecto al eje X

My = Momento con respecto al eje Y

Ix = Inercia con respecto al eje X

Iy = Inercia con respecto al eje Y

f) Dividir la losa

Un criterio aproximado de análisis consiste en dividir la losa en franjas, lo que consiste en

colocar líneas paralelas a los ejes (X, Y) entre las mitades de la distancias que hay entre las

columnas o muros como se ve en la figura. El ancho de cada bloque será identificado como

B1, B2, , Bn.

85

<!-- p. 11 -->

Figura 7.9 Subdivisiones en la losa

g) Determinación de la presión promedio (qav)

Este cálculo se hará para todos los bloques que se han generado tanto en el eje X como en

el eje Y a partir de la división de la losa. Ya que se eligió un bloque, la presión promedio

qav se obtiene de la siguiente manera:

q inicial q final
q av 2

86

<!-- p. 12 -->

Figura 7.10 Presión promedio (qav)

h) Determinación de la presión total en el bloque (qT)

Aquí existen dos criterios para obtener la presión total y son:

\1) carga promedio * ancho de la sección * ancho de la losa

q T q av B1 B

\2) La suma de todas las cargas involucradas en la sección. Tomando como ejemplo la

sección JKPQ B1, sería la siguiente:

qT P1 P2 P3 P4

i) Factor de compensación (F)

Sí existiera una diferencia entre estos dos casos, será necesario calcular un factor de

compensación (F).

qav B1 B P1 P2 P3 P

87

<!-- p. 13 -->

q av B1 B P1 P2 P3 P F
2

j) Compensación de cargas y presiones

\1) Para presiones

F
q av (mod ificada )
q av B1 B

\2) Para cargas

Pn (mod ificada ) F * Pn

k) Diagrama de cortante y momentos

l) Obtención del peralte efectivo (d)

Considerando la losa como una viga ancha se tiene:

VCR FR bd 2.0 20 p f c *

7.2.3 REVISIÓN POR PUNZONAMIENTO

Será igual al mencionado en el capítulo anterior correspondiente a la sección 6.4.5.

7.2.4 ÁREA DE ACERO (As)

As p * b * d

88

<!-- p. 14 -->

This document was created with Win2PDF available at http://www.daneprairie.com.
The unregistered version of Win2PDF is for evaluation or non-commercial use only.
