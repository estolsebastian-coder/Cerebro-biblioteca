---
type: libro
title: "Capítulo 3 - EJEMPLOS"
author: "Estudio de Ingeniería"
categoria: "ESTRUCTURA"
paginas: 50
extraccion: "texto"
fuente: "local:E:/MATERIAL DE CONSULTA/ESTRUCTURA/SUELOS/FUNDACIONES/CIRSOC 102/Guía/cap 3.pdf"
convertido: 2026-10-16
---

# Capítulo 3 - EJEMPLOS

> Texto extraído de `ESTRUCTURA\SUELOS\FUNDACIONES\CIRSOC 102\Guía\cap 3.pdf` (50 páginas, texto). El PDF original está en el disco E: (MATERIAL DE CONSULTA); `<!-- p. N -->` marca el inicio de cada página.

<!-- p. 1 -->

CAPÍTULO 3 - EJEMPLOS

Se desarrollan a continuación diversos ejemplos ilustrativos referidos a la determinación
de fuerzas de viento usando procedimientos analíticos, como una forma de servir de guía
a los proyectistas. Se presentan seis ejemplos asociados a configuraciones diferentes de
edificios, a saber:

1 Edificio en altura para oficinas, con lados de 30 x 60 m y 48 m de altura.
2 El mismo edificio anterior, pero ubicado sobre una escarpa.
3 Edificio de un piso para comercio o industria, con techo a dos aguas, con
lados de 60 x 75 m y altura de alero de 6 m.
4 Edificio del Ejemplo 3, usando disposiciones por baja altura para SPRFV.
5 Edificio con techo en una pendiente con lados de 12 x 24 m y altura 4.5 m.
6 Letrero con lados de 6 x 15 m, ubicado a 18 m sobre el terreno.

Estos ejemplos representan una variedad de situaciones en la determinación de las
fuerzas de viento, y se han desarrollado en detalle para asistir al proyectista en la
interpretación de las disposiciones normativas. Se ha puesto énfasis en el control de todas
las operaciones numéricas, aunque no puede garantizarse la ausencia de errores
involuntarios.

3.1. EJEMPLO 1

Parapeto (1.0 m)

48 m

60 m

30 m

Figura 3.1 Dimensiones del edificio para el Ejemplo 1

Reglamento CIRSOC 102, Guía Cap. 3 - 17

<!-- p. 2 -->

En este ejemplo se determinarán las presiones de viento para un edificio de oficinas
estándar, que se muestra en la Figura 3.1. Los datos disponibles son:

Ubicación: Ciudad de la Provincia de Buenos Aires.
Topografía : Plana.
Terreno : Suburbano.
Dimensiones: 30 x 60 m en planta.
Altura de la cubierta: 47 m, con 1,0 m de parapeto adicional.
Cubierta plana.
Estructuración: Pórticos de hormigón armado en ambas direcciones.
Las losas de entrepisos y de cubierta se comportan como
rígidas en su plano.
Frecuencia natural fundamental mayor que 1 Hz. (Así se
estima cuando la relación altura/menor dimensión horizontal
es menor que cuatro).
Revestimientos: Montantes para paneles vidriados de 3.3 m de luz entre losas,
y espaciados 1.50 m.
Los paneles de vidrio poseen 1.50 m de ancho y 1.65 m de
altura y son resistentes al impacto de proyectiles en los 18 m
más bajos.

Tipo de exposición y clasificación del edificio

El edificio se ubica en el área suburbana, por lo tanto le corresponde el tipo de exposición
B según el artículo 5.6. Se trata de un edificio de oficinas, y no se considera esencial
albergar a 300 personas en un área del mismo. En consecuencia, es apropiada la
Categoría II según la Tabla A-1.

Velocidad básica del viento

La elección de la velocidad básica del viento se extrae del artículo 5.4 del Reglamento, y
corresponde en el presente caso adoptar V = 46 m/s, según la Figura 1.

Presión dinámica

La ecuación para determinar la presión dinámica es:

qz = 0.613 Kz Kzt Kd V2 I

Para este ejemplo, Kz se obtiene de Tabla 5 (Caso 2, Exposición B), Kzt = 1.0 (terreno
plano), en tanto que I = 1.0 para edificios de Categoría II (Tabla 1). Kd solo se aplica para
los casos de combinaciones de carga. Sustituyendo en la ecuación resulta:

qz = 0.613 x 1.0 x 462 x 1.0 Kz = 1297 KZ N/m2

Los valores de Kz y las presiones dinámicas resultantes se llevaron a la tabla siguiente. La
presión dinámica a la altura media de cubierta qh es 1453 N/m2 .

Reglamento Argentino de Acción del Viento Guía Cap. 3 - 18

<!-- p. 3 -->

Presiones dinámicas Kz
Altura (m) Kz qz (N/m2)
0-5 0.59 (*) 765
10 0.72 934
15 0.81 1051
25 0.93 1206
35 1.03 1336
Cubierta 47 1.12 1453
Parapeto 48 1.13 1466
Nota: (*) Para C&R (caso 1), z ≤ 10 m, Kz = 0.72, qz = 934 N/m2

Presiones de viento de diseño para SPRFV

Las ecuaciones para determinar las presiones de diseño en edificios están dadas en el
artículo 5.12.2 del Reglamento. La ecuación para el SPRFV (el edificio no es flexible) es:

p = q GCp – qi (GCpi)

siendo

q = qz para paredes a barlovento, a la altura z sobre el terreno.
q = qh para paredes a sotavento, paredes laterales y cubierta, a la altura h.
qi = qh para paredes a barlovento, paredes laterales, paredes a sotavento y
cubierta de edificios cerrados y para la evaluación de la presión interna
negativa en edificios parcialmente cerrados .
qi = qz para la evaluación de la presión interna positiva en edificios parcialmente
cerrados donde la altura z está definida como el nivel de la abertura más
elevada del edificio que puede afectar la presión interna positiva. Para
edificios ubicados en regiones donde pueda darse el arrastre de partículas
por el viento, el vidriado en los 20 m inferiores que no sea resistente a
impacto o esté protegido con una cubierta resistente a impacto, se debe tratar
como una abertura de acuerdo con el artículo 5.9.3. Para la evaluación de la
presión interna positiva, qi se puede calcular conservativamente a la altura h
(qi = qh).
G factor de efecto de ráfaga del artículo 5.8.
Cp coeficiente de presión externa de la Figura 3 ó de la Tabla 8.
GCpi coeficiente de presión interna de la Tabla 7.

Factor de efecto de ráfaga G : Este factor se calcula según el artículo 5.8. Para terrenos
suburbanos, Exposición B, del artículo 5.8.1 se aplica G = 0.85.

Coeficientes de presión externa Cp para paredes: Los valores de este coeficiente para las
diversas superficies de paredes se obtienen de la Figura 3

El coeficiente de presión para paredes a barlovento es 0.8.
El coeficiente de presión para paredes laterales es -0.7.
El coeficiente de presión para paredes a sotavento es una función de la relación
L/B.
Para viento normal a la cara de 60 m de ancho es L/B = 30/60 = 0.5, y en
consecuencia, el coeficiente de presión a sotavento es -0.5.
Para viento paralelo a la misma cara, L/B = 60/30 = 2.0, por lo cual el coeficiente de
presión en la pared a sotavento es -0.3.

Reglamento CIRSOC 102, Guía Cap. 3 - 19

<!-- p. 4 -->

Coeficiente de presión en paredes : Cp
Superficie Dirección del viento L/B Cp
Pared a barlovento Todas Todas 0.80
⊥a la cara de 60 m 0.5 -0.50 Pared a sotavento
II a la cara de 60 m 2.0 -0.30
Paredes laterales Todas Todas -0.70

Coeficiente de presión externa Cp para cubierta (con el viento normal a la cara de 60 m):

Para h/L = 47/30 ≅ 1.6 > 1.0 , y θ \< 10º , se especifican dos zonas:
0 a h/2 , Cp = -1.3
\> h/2 , Cp = -0.7

El coeficiente Cp = -1.3 se puede reducir con el área sobre la cual se aplica:

Area = 60 x 23.5 = 1410 m2
Factor de reducción = 0.8
Cp reducido = 0.8 x (-1.3) = -1.04

Coeficientes Cp para la cubierta
Distancia desde el borde de referencia Cp
0 hasta h/2 -1.04
\> h/2 -0.70
Nota : h = 47 m

Coeficiente de presión externa Cp para cubierta ( con el viento paralelo a la cara de 60 m):

Para h/L = 47/60 ≅ 0.8 , es necesario interpolar en la Figura 3

Coeficientes Cp para la cubierta
Distancia desde el
h/L ≤ 0.5 h/L = 0.8 h/L ≥ 1.0 borde a barlovento
0 hasta h/2 -0.90 -0.98 -1.04
h/2 hasta h -0.90 -0.78 -0.70
h hasta 2h -0.50 -0.62 -0.70

Coeficientes de presión interna (GCpi) :

Los valores de GCpi para edificios se obtienen de la Tabla 7.

Se supone que las aberturas se distribuyen uniformemente en las paredes. En
consecuencia, de la Tabla 7:
GCpi = ± 0.18

Reglamento Argentino de Acción del Viento Guía Cap. 3 - 20

<!-- p. 5 -->

Presiones netas para el SPRFV

p = q GCp – qi (GCpi) (Artículo 5.12.2.1)

Cálculo para la pared a barlovento, a 10 m, viento normal a la cara de 60 m

p = 934 x 0.85 x 0.80 – 1453 x (± 0.18)
p = 374 N/m2 con presión interna positiva
p = 897 N/m2 con presión interna negativa

Cálculo para la cubierta, para 0-23.5 m desde el borde, viento normal a la cara de 60 m :

p = 1453 x 0.85 x (-1.04) – 1453 x (± 0.18)
p = -1546 N/m2 con presión interna positiva
p = -1023 N/m2 con presión interna negativa

Presiones netas para el SPRFV : Viento normal a la cara de 60 m
z q Presión Presión neta (N/m2) con:
Superficie Cp (m) (N/m2) externa (+ GCpi) (-GCpi)
0-5 765 0.80 520 259 782
10 934 0.80 635 374 897
Pared a 15 1051 0.80 715 453 976
barlovento 25 1206 0.80 820 559 1082
35 1336 0.80 908 647 1170
47 1453 0.80 988 727 1250
Pared a
Todas 1453 -0.50 -618 -879 -356
sotavento
Paredes
Todas 1453 -0.70 -865 -1126 -603
laterales
0-23.5 * 1453 -1.04 -1284 -1546 -1023
Cubierta
23.5-30.0 1453 -0.70 -865 -1126 -603
Notas: (*) Distancia al borde a barlovento
qh = 1453 N/m2, G = 0.85, (GCpi) = ± 0.18

Carga de parapeto sobre el SPRFV :

Para la contribución de la carga de parapeto al SPRFV, éste se puede considerar como
una estructura de cartel a nivel del terreno.

Coeficiente de fuerza para ν = 1.0/60.0 \< 3.0 , Cf = 1.2 (Tabla 11)

Para edificios abiertos y otras estructuras la ecuación se presenta en el artículo 5.13:

F = qz GCf Af

Si para Af se considera 1.0 m de ancho por 1.0 m de altura:

F = 1466 x (0.85) (1.2)(1.0) = 1495 N/m

Esta fuerza se debe aplicar sobre los parapetos a barlovento y a sotavento.

Reglamento CIRSOC 102, Guía Cap. 3 - 21

<!-- p. 6 -->

Para el diseño del parapeto se deben consultar las cargas sobre las componentes y
revestimientos.

23.50 m

1546 N/m 2

1126 N/m 2

1495 N/m 48 m 1495 N/m

Viento 47 m

727 N/m 2

35 m

647 N/m 2 30 m

879 N/m 2
25 m

559 N/m 2

15 m
453 N/m 2
10 m
374 N/m 2
5 m
259 N/m 2

Notas
1.- Se puede considerar una carga similar con presión interna negativa (succión) que producirá un
levantamiento reducido de la cubierta y no afectará el corte total horizontal.
2.- Los intervalos para la distribución de la carga sobre la pared a barlovento son idénticos a los de qz.

Figura 3.2 Presiones netas para SPRFV para viento normal a la cara de 60 m con
presión interna positiva

Presiones netas para el SPRFV: Viento paralelo a la cara de 60 m
z q Presión Presión neta (N/m2) con:
Superficie Cp (m) (N/m2) externa (+GCpi) (-GCpi)
0-5 765 0.80 520 259 782
10 934 0.80 635 374 897
Pared a 15 1051 0.80 715 453 976
barlovento 25 1206 0.80 820 559 1082
35 1336 0.80 908 647 1170
47 1453 0.80 988 727 1250
Pared a
Todas 1453 -0.30 -371 -632 -109
sotavento
Paredes
Todas 1453 -0.70 -865 -1126 -603
laterales
0-23.5 1453 -0.98 --1210 -1472 -949
Cubierta 23.5-47 1453 -0.78 -963 -1225 -702
47-60 1453 -0.62 -766 -1027 -504
Notas: qh = 1453 N/m2 , G = 0.85, (GCpi) = ± 0.18

Reglamento Argentino de Acción del Viento Guía Cap. 3 - 22

<!-- p. 7 -->

23.50 m 23.50 m

1472 N/m 2
1225 N/m 2
1027 N/m 2

1495 N/m 48 m 1495 N/m

47 m

727 N/m 2

Viento 35 m

647 N/m 2 60 m

632 N/m 2
25 m

559 N/m 2

15 m
453 N/m 2
10 m
374 N/m 2
5 m
259 N/m 2

Notas:
Ver Fig.3.2

Figura 3.3 Presiones netas para SPRFV para viento paralelo a la cara de 60 m con
presión interna positiva

Presiones de diseño para componentes y revestimientos

La ecuación para presiones de diseño en componentes y revestimientos de edificios con
altura mayor que 20 m está contenida en el artículo 5.12.4.2 y es:

p = q (GCp) – qi (GCpi)
siendo
q = qz para paredes a barlovento a la altura z
q = qh para paredes a sotavento, paredes laterales, y cubiertas
qi = qh para paredes a barlovento, paredes laterales, paredes a sotavento y
cubiertas de edificios cerrados
(GCp) coeficiente de presión externa según la Figura 8.

Presiones de diseño en paredes

Los coeficientes de presión (GCp) son función del área efectiva de viento. La definición de
esta última para un componente o un panel de revestimiento es la longitud multiplicada por
un ancho efectivo que no debe ser menor que un tercio de la longitud del tramo (según la
definición en Capítulo 2).

Reglamento CIRSOC 102, Guía Cap. 3 - 23

<!-- p. 8 -->

Las áreas efectivas de viento, A, para los componentes de la pared son:

Montantes: A = 3.30 x 1.50 ≅ 5.0 m2 (valor a adoptar)
ó A = 3.30 x 3.30/3 ≅ 3.60 m2
Panel vidriado: A = 1.50 x 1.65 ≅ 2.5 m2 (valor a adoptar)
ó A = 1.50 x 1.50/3 ≅ 0.75 m2
Ancho de zona 5: a = 0.10 x 30 = 3.0 m

(GCp) en paredes
GCp A
Componente zonas 4 y 5 zona 4 zona 5 (m2)
(+GCp) (-GCp) (-GCp)
Montante 5.0 0.81 -0.84 -1.55
Panel 2.5 0.87 -0.88 -1.72
Nota: El coeficiente de presión interna (GCpi) = ± 0.18

Cálculo típico de la presión de diseño

Montante en zona 4 (presión negativa)
p = 1453 [(-0.84) – (± 0.18)]
p = -1482 N/m2 con presión interna positiva (valor a adoptar)
p = -959 N/m2 con presión interna negativa

La presión negativa dominante se obtiene con la presión interna positiva y la presión
positiva dominante con la presión interna negativa.

Presiones de diseño en montantes, N/m2
Presiones de Diseño
z
Componente zona 4 zona 5 (m)
Positiva Negativa Positiva Negativa
0-5 1018 -1482 1018 -2514
5-10 1018 -1482 1018 -2514
10-15 1113 -1482 1113 -2514
Montante
15-25 1238 -1482 1238 -2514
25-35 1344 -1482 1344 -2514
35-47 1438 -1482 1438 -2514

Presiones de diseño en paneles, N/m2
Presiones de Diseño
z
Componente zona 4 zona 5 (m)
Positiva Negativa Positiva Negativa
0-5 1074 -1540 1074 -2761
5-10 1074 -1540 1074 -2761
10-15 1176 -1540 1176 -2761
Panel
15-25 1311 -1540 1311 -2761
25-35 1424 -1540 1424 -2761
35-47 1526 -1540 1526 -2761

Reglamento Argentino de Acción del Viento Guía Cap. 3 - 24

<!-- p. 9 -->

Presiones de diseño en parapetos

Aunque el Reglamento no provee presiones de diseño específicas para parapetos, los
valores de GCp dados en la Figura 8 posibilitan una estimación razonable de estas
presiones. Para un parapeto situado sobre la cara a barlovento del edificio, la presión neta
resulta de la suma algebraica de la presión positiva para paredes en zonas 4 y 5 y la
presión negativa para cubierta en zona 2. Si el parapeto se ubica sobre la cara a sotavento
del edificio o en la esquina de dicha cara. la presión neta surge de la suma algebraica de
las presiones positiva y negativa para paredes (zonas 4 y 5). El área efectiva de viento
depende de las dimensiones y detalles de estructuración del parapeto. En el presente
ejemplo, el área efectiva de viento se supone igual a 1.0 x 1.0 = 1.0 m2.

Parapeto a barlovento:

p = 1466 x (0.9) – 1453 x (-2.3) = 4661 N/m2 (Dirigida hacia adentro)

Parapeto a sotavento o de esquina:

Zona 4 : p = 1466 x (0.9) – 1453 x (-0.9) = 2627 N/m2 (dirigida hacia afuera)

Zona 5 : p = 1466 x (0.9) – 1453 x (-1.8) = 3935 N/m2 (dirigida hacia afuera)

Presiones de diseño en la cubierta

Los coeficientes de presión de cubierta para montantes y revestimientos están dados en la
Figura 8. Los coeficientes de presión son función del área efectiva de viento. Dado que los
componentes específicas de la cubierta no están identificados, las presiones de diseño se
presentan para varias áreas efectivas de viento A.

(GCp) en cubierta
Coeficiente de presión externa
A
zona 1 zonas 2 y 3 (m2)
(-GCp) (-GCp)*
≤ 1.0 -1.4 -2.30
2.0 -1.31 -2.18
10.0 -1.11 -1.89
25.0 -0.99 -1.72
40.0 -0.93 -1.64
≥50.0 -0.90 -1.60
Nota: * La nota 7 en la Figura 8 permite el tratamiento de la zona 3
como zona 2 si se dispone de un parapeto de altura ≥ 1.0 m.

Las presiones de diseño resultan de la suma de presiones externas e internas. Las
presiones internas positivas se suman a las presiones externas negativas que controlan el
diseño. Estas presiones de diseño actúan del interior al exterior de la superficie de la
cubierta.

Reglamento CIRSOC 102, Guía Cap. 3 - 25

<!-- p. 10 -->

Presiones de diseño en la cubierta, N/m2
Presiones negativas de
A diseño
(m2)
zona 1 zonas 2 y 3

≤ 1.0 -2296 -3603
2.0 -2165 -3429
10.0 -1874 -3008
25.0 -1700 -2761
40.0 -1613 -2644
50.0 -1569 -2586

Reglamento Argentino de Acción del Viento Guía Cap. 3 - 26

<!-- p. 11 -->

3.2. EJEMPLO 2

En este ejemplo, se determinarán las presiones dinámicas para el mismo edificio del
Ejemplo 1, pero ubicado ahora sobre una escarpa. Las presiones de diseño para el
SPRFV, y para los componentes y revestimientos se pueden determinar en forma análoga
al Ejemplo 1, una vez que las presiones dinámicas qz y qh son conocidas.

Los datos disponibles son:

Ubicación: Ciudad de la Provincia de Buenos Aires.
Topografía : Escarpa, como se muestra en Fig.3.4.
Terreno : Suburbano.
Dimensiones: 30 x 60 m en planta.
Altura de la cubierta : 47 m, con 1.0 m de parapeto adicional.
Cubierta plana.
Estructuración: Pórticos de hormigón armado en ambas direcciones.
Las losas de entrepisos y de cubierta se comportan
como rígidas en su plano.
Frecuencia natural fundamental mayor que 1 Hz.
Revestimientos: Montantes para paneles vidriados de 3.3 m de luz
entre losas, y espaciados 1.50 m.
Los paneles de vidrio poseen 1.50 m de ancho y
1.65 m de altura (típicos).

Exposición, clasificación del edificio y velocidad básica del viento:

Como en el Ejemplo 1: Exposición B
Categoría II
V = 46 m/s

Presiones dinámicas

La ecuación para la presión dinámica es:

qz = 0.613 Kz Kzt Kd V2 I (N/m2)

Para este ejemplo, Kz se obtiene de la Tabla 5 y Kzt se determina usando la Figura 2, Kd
se aplica solo para combinaciones de carga no consideradas en este ejemplo, I = 1.0 para
la categoría II y V = 46 m/s.

Reglamento CIRSOC 102, Guía Cap. 3 - 27

<!-- p. 12 -->

Viento

48 m

L h = 30 m

H/2
x= 15 m 30 m
H = 24 m

Notas:
1.- Lh se mide desde media altura hasta el tope de la pendiente.
2.- La distancia x se toma hasta el frente del edificio como valor conservativo.

Figura 3.4 Edificio de oficinas sobre una escarpa

Determinación de Kzt

El efecto topográfico de escarpa se aplica solamente cuando el terreno a barlovento está
libre de obstáculos topográficos hasta una distancia igual a 100H ó 3000 m, la que sea
menor. Para este ejemplo, se admite que no existen tales obstáculos en una distancia de
2400 m.

Para entrar en la Figura 2 del Reglamento:

H = 24 m
Lh = 30 m
x = 15 m

Dado que H/Lh = 0.8 > 0.5 debe usarse, según Nota 2 de Figura 2: H/Lh = 0.5, con lo cual
resulta Lh = 2H = 48 m.

El edificio se ubica en una escarpa bidimensional.

Para H/Lh = 0.5 se obtiene de Figura 2 el valor K1 = 0.43

Para x/Lh = 0.31 se obtiene de Figura 2 el valor K2 = 0.92

(Nota: En la Figura 2, todos los otros casos para K2 se refieren a lomas y colinas)

K3 depende de z/Lh

Kzt = (1 + K1 K2 K3)2 (ecuación 2 del Reglamento)

qz = 0.613 Kz Kzt 462 x 1.0

Reglamento Argentino de Acción del Viento Guía Cap. 3 - 28

<!-- p. 13 -->

Presiones dinámicas (N/m2)
Altura (m) Kz z/Lh* K3 Kzt qz(N/m2)
0-5 0.59** 0.05 0.89 1.83 1401
10 0.72 0.16 0.68 1.61 1504
15 0.81 0.26 0.53 1.46 1534
25 0.93 0.42 0.35 1.31 1580
35 1.03 0.63 0.20 1.16 1550
h = 47 Kh = 1.13 0.85 0.13 1.11 1627
Notas: (*) z se toma en la mitad de cada rango de altura, por cuanto no es
conservativo adoptar la altura máxima de cada rango.
Se debe notar que Lh = 2H = 48 m.
(**) Kz = 0.59 para SPRFV, para C&R Kz = 0.72

Efecto de escarpa

Las presiones dinámicas qz son comparadas con los valores del Ejemplo 1 para verificar
el efecto de escarpa. El incremento de las presiones dinámicas no se traduce directamente
en un incremento de las presiones de diseño, este tema se aclara más adelante.

Presiones dinámicas qz (N/m2)
Terreno Homogéneo Escarpa
Altura (m) Incremento (%)
Ejemplo 1 Ejemplo 2
0-5 765* 1401 83
10 934 1504 67
15 1051 1534 46
25 1206 1580 31
35 1336 1550 16
47(cubierta) 1453 1627 12
Notas: (*) Válido solo para SPRFV, para C&R el valor es 934.

Para el SPRFV, las presiones en la pared a barlovento se aumentan en los porcentajes
que se muestran tabulados a las distintas alturas; sin embargo, las presiones en las
paredes a sotavento, laterales y cubierta, y la presión interna aumentarán un 12 %, por
cuanto éstas son controladas por la presión dinámica a la altura de cubierta qh .

Para componentes y revestimientos las presiones negativas de diseño (actuando hacia
afuera) también aumentarán solamente un 12 %.

Reglamento CIRSOC 102, Guía Cap. 3 - 29

<!-- p. 14 -->

3.3. EJEMPLO 3

En este ejemplo, las presiones de viento de diseño se determinarán para un edificio de un
piso de considerables dimensiones, destinado a comercio e industria. Los datos son:

Ubicación: Provincia de Tucumán.
Terreno: Rural, plano.
Dimensiones: 60 m x 75 m en planta.
Altura de alero 6 m.
Pendiente de la cubierta 1:3 (18° 26’).
Estructuración: Pórticos rígidos salvando la luz de 60 m.
Separación entre pórticos: 7.5 m.
Arriostramientos en dirección de los 75 m.
Correas de paredes y cubierta: luz = 7.5 m.
Separación entre correas de paredes: 2.0 m.
Separación entre correas de techo: 1.5 m.
Revestimientos: Dimensiones de paneles de cubierta: 0.6 m x 6.0 m.
Separación entre fijadores de cubierta: 0.3 m entre
ejes.
Dimensiones de paneles en paredes: 0.6 m x 6.0 m.
Separación entre fijadores en paredes: 0.3 m entre
ejes.
Aberturas distribuidas uniformemente.

Cumbrera
3

1

Pórtico Alero Arriostramiento
Correa
Correa de pared 6 m

30 m
7.5 m 75 m

60 m 30 m

Figura 3.5 Dimensiones y estructuración para el edificio del Ejemplo 3

Reglamento Argentino de Acción del Viento Guía Cap. 3 - 30

<!-- p. 15 -->

Exposición y clasificación del edificio

El edificio se localiza en un terreno rural plano, correspondiéndole la categoría de
exposición C. Su función es la actividad comercial-industrial, por lo cual no es factible que
lo ocupen 300 personas al mismo tiempo. Se considera apropiada la categoría II (Tabla 1).

Velocidad básica del viento

La velocidad básica del viento se elige según el artículo 5.4 del Reglamento. A la provincia
de Tucumán le corresponde el valor V = 40 m/s.

Presión dinámica

Las presiones dinámicas se computan con la ecuación:

qz = 0.613 Kz Kzt Kd V2 I (N/m2)

Para este ejemplo, Kz se obtiene de la Tabla 5. Kzt = 1 (no se presentan efectos
topográficos). Kd solo se considera para casos de combinaciones de carga. Para
categoría II es I = 1.0 . Sustituyendo valores resulta:

qz = 0.613x1.0x402x1.0 Kz = 981 Kz

En la tabla siguiente se muestran los valores de Kz y las presiones dinámicas asociadas
con las diferentes alturas. La altura media de la cubierta es igual a 11.0 m.

Presiones dinámicas en N/m2
Altura (m) Kz qz(N/m2)
0-5 0.87 853
Alero ht = 6 0.90 883
9 0.98 961
h =11 1.02 1001*
12 1.04 1020
15 1.09 1069
Cumbrera ht =16 1.10 1079
Nota: qh = 1001 N/m2

Presiones de viento de diseño para el SPRFV

Las ecuaciones para determinar las presiones y fuerzas de diseño para un edificio u otras
estructuras se dan en el artículo 5.12.2 del Reglamento. La ecuación para el SPRFV en
edificios de todas las alturas es:
p = q GCp – qi(GCpi)
siendo:

q = qz para pared a barlovento a la altura z sobre el terreno.
q = qh para pared a sotavento, paredes laterales y cubierta.
qi =qh para paredes a barlovento, paredes laterales, paredes a sotavento y
cubiertas de edificios cerrados y para la evaluación de la presión interna
negativa en edificios parcialmente cerrados.

Reglamento CIRSOC 102, Guía Cap. 3 - 31

<!-- p. 16 -->

qi = qz para la evaluación de la presión interna positiva en edificios
parcialmente cerrados, donde la altura z está definida como el nivel
de la abertura más elevada del edificio que puede afectar la presión
interna positiva. Para la evaluación de la presión interna positiva, qi
se puede calcular conservativamente a la altura h (qi = qh).
G = 0.85, factor de efecto de ráfaga según el artículo 5.8.1.
Cp valores obtenidos de la Figura 3.
(GCpi) valores obtenidos de Tabla 7.

Hay dos procedimientos alternativos para determinar las presiones de viento para SPRFV
en edificios de baja altura. Los coeficientes de presión que se muestran en la Figura 3 son
aplicables a edificios de todas las alturas, en tanto que los presentados en la Figura 4 se
refieren solamente a edificios de baja altura, en los cuales la altura media h es menor o
igual a 20 m. En este ejemplo se usarán los coeficientes de la Figura 3, y en el Ejemplo 4
se ilustrará el procedimiento usando los coeficientes de la Figura 4.

En este ejemplo, cuando el viento es normal a la cumbrera, la cubierta a barlovento recibe
presiones externas tanto positivas como negativas. Combinando estas presiones externas
con las presiones internas positivas y negativas resultan cuatro casos de carga cuando el
viento es normal a la cumbrera. Cuando el viento es paralelo a la cumbrera, las presiones
internas positivas y negativas dan lugar a dos casos de carga.

Valores Cp para paredes según la Figura 3

Los coeficientes de presión para la pared a barlovento y paredes laterales son 0.8 y (-0.7)
respectivamente, para todas las relaciones L/B.

El coeficiente de presión para la pared a sotavento es una función de L/B. Para viento
normal a la cumbrera, L/B = 60/75 = 0.8, siendo el coeficiente de presión (-0.5). Para el
flujo paralelo a la cumbrera, L/B = 75/60 = 1.25, se puede interpolar el valor de Cp . Todos
los valores del coeficiente Cp se resumen en la tabla que sigue.

Coeficiente de presión Cp para paredes
Superficie Dirección del viento Relación L/B Cp
Pared a barlovento Todas Todas 0.80
⊥a la cumbrera 0.80 -0.50 Pared a sotavento
II a la cumbrera 1.25 -0.45 (interpolación)
Paredes laterales Todas Todas -0.70

Coeficientes de presión Cp para la cubierta según la Figura 3 (Viento normal a la
cumbrera)

Estos coeficientes para el SPRFV se obtienen de la tabla continuación de la Figura 3. Para
el ángulo 18º26’ de la cubierta, se usa interpolación lineal para determinar Cp. Para viento
normal a la cumbrera, h/L = 11/60 = 0.18.

Coeficientes de presión Cp para la cubierta (Viento normal a la cumbrera)
Superficie 15º 18.4º 20º
\-0.5 -0.36 (interpolación) -0.3
Pared a barlovento
0.0 0.14 (interpolación) 0.2
Pared a sotavento -0.5 -0.57 (interpolación) -0.6

Reglamento Argentino de Acción del Viento Guía Cap. 3 - 32

<!-- p. 17 -->

Valores de GCpi internos

Los coeficientes de presión para edificios están contenidos en la Tabla 7 del Reglamento.
Las aberturas están distribuidas uniformemente en las paredes y en consecuencia
GCpi = ± 0.18.

Presiones netas sobre el SPRFV

p = q GCp – qi (GCpi)
p = q(0.85)Cp – 1001 (± 0.18)
donde:

q = qz para pared a barlovento.
q = qh para pared a sotavento, paredes laterales y cubierta.
qi = qh para paredes a barlovento, paredes laterales, paredes a sotavento y
cubiertas de edificios cerrados y para la evaluación de la presión interna
negativa en edificios parcialmente cerrados.
qi = qz para la evaluación de la presión interna positiva en edificios parcialmente
cerrados, donde la altura z está definida como el nivel de la abertura más
elevada del edificio que puede afectar la presión interna positiva. Para la
evaluación de la presión interna positiva, qi se puede calcular
conservativamente a la altura h (qi = qh).

Cálculo típico

Pared a barlovento, 0-5 m , viento normal a la cumbrera:
p = 853 (0.85) (0.8) – 1001 (± 0.18)
p = 400 N/m2 para presión interna positiva
p = 760 N/m2 para presión interna negativa

Las presiones netas para el SPRFV se incorporaron a las tablas siguientes:

Presiones sobre el SPRFV : Viento normal a la cumbrera
Presión neta en N/m2 con: Superficie z (m) q (N/m2) Cp
(+GCpi) (-GCpi)
Pared a 0-5 853 0.8 400 760
barlovento 6 883 0.8 420 781
Pared a
Todas 1001 -0.5 -606 -245
sotavento
Paredes
Todas 1001 -0.7 -776 -415
laterales
Cubierta a 1001 -0.36 -486 -126
\-
barlovento* 1001 0.14 -61 299
Cubierta a
\- 1001 -0.57 -665 -305
sotavento
Notas: qh = 1001 N/m2 ; G = 0.85 ; GCpi = ± 0.18
(*) Dos casos de carga sobre la cubierta a barlovento y dos presiones
internas dan un total de cuatro casos de carga (ver Figuras 3.6 y 3.7)

Reglamento CIRSOC 102, Guía Cap. 3 - 33

<!-- p. 18 -->

Coeficientes de presión Cp para cubierta, de la Figura 3 . (Viento paralelo a la cumbrera)

Para viento paralelo a la cumbrera h/L=11/75 = 0.147. Los valores de Cp para todos los
valores de θ se obtienen de la Figura 3, y se presentan en la tabla siguiente

Coeficientes Cp para la cubierta (Viento paralelo a la cumbrera)
Distancia desde el borde
Superficie h/L Cp a barlovento
0 a h -0.9
Cubierta ≤ 0.5 h a 2h -0.5
\> 2h -0.3

\-486 N/m2 -665 N/m2

(+ ) Presión interna de + 180 N/m 2 420 N/m2 5 m
\-606 N/m2
400 N/m2

60 m

\-126 N/m 2 -305 N/m 2

2 2 (-) Presión interna de - 180 N/m781 N/m
5 m 2 2 -245 N/m760 N/m

60 m

Figura 3.6 Presiones de diseño netas para el SPRFV para viento normal a la
cumbrera con coeficiente negativo de presión externa a barlovento en
cubierta

Reglamento Argentino de Acción del Viento Guía Cap. 3 - 34

<!-- p. 19 -->

2 -665 N/m2 -61 N/m

2 2 (+ ) Presión interna de + 180 N/m 420 N/m 5 m
\-606 N/m2
400 N/m2

60 m

299 N/m 2 -305 N/m2

2 2 (-) Presión interna de - 180 N/m781 N/m 5 m
2 -245 N/m2760 N/m

60 m

Figura 3.7 Presiones de diseño netas para el SPRFV para viento normal a la
cumbrera con coeficiente positivo de presión externa a barlovento en
cubierta

Reglamento CIRSOC 102, Guía Cap. 3 - 35

<!-- p. 20 -->

Presiones sobre el SPRFV : Viento paralelo a la cumbrera
Presiones netas (N/m2) con: Superficie z (m) q (N/m2) Cp
\+GCpi -GCpi
0-5 853 0.8 400 760
6 883 0.8 420 781
Pared a
9 961 0.8 473 834 barlovento
12 1020 0.8 513 874
16 1079 0.8 554 914
Pared a
Todas 1001 -0.45 -563 -203
sotavento
Paredes
Todas 1001 -0.7 -776 -415
laterales
0 a h* 1001 -0.9 -946 -586
Cubierta h a 2h* 1001 -0.5 -606 -245
\>2h* 1001 -0.3 -435 -75
Notas: qh = 1001 N/m2 ; G = 0.85 ; GCpi = ± 0.18 ; h = 11 m
\* Distancia desde el borde a barlovento.

11 m 11 m
\-946 N/m 2
\-606 N/m 2 2 -435 N/m

554 N/m 2
12 m
513 N/m 2
9 m -563 N/m 2
2 16 m 473 N/m
2 6 m 2 420 N/m (+ ) Presión interna de + 180 N/m 5 m
400 N/m 2

75 m

\-946 N/m 2
\-606 "
\-435 "

(+ ) Presión interna 2 -776 N/m2 -776 N/m

a) Con presión interna positiva

Reglamento Argentino de Acción del Viento Guía Cap. 3 - 36

<!-- p. 21 -->

11 m 11 m
\-586 N/m 2
\-245 N/m 2 2 -75 N/m

914 N/m 2
12 m 2 -203 N/m2 874 N/m
9 m
2 16 m 834 N/m
6 m (-) Presión interna 781 N/m 2 5 m
760 N/m 2

75 m

\-586 N/m 2
\-245 "
\-75 "

(-) Presión interna
\-415 N/m2 -415 N/m2

b) Con presión interna negativa

Figura 3.8 Presiones de viento netas de diseño para SPRFV con viento paralelo a
la cumbrera

Presiones de diseño para componentes y revestimientos (C & R)

Las ecuaciones para la presiones de diseño en componentes y revestimientos están dadas
en el artículo 5.12.4.1 del Reglamento. La ecuación para edificios con h ≤ 20 m es:

p = qh[(GCp) – (GCpi)]

siendo:

qh = 1001 N/m2
(GCp) = valores que se obtienen de la Figura 5
(GCpi) = ± 0.18

Reglamento CIRSOC 102, Guía Cap. 3 - 37

<!-- p. 22 -->

Presiones en componentes y revestimientos de paredes

Los coeficientes de presión (GCp) son función del área efectiva de viento. La definición de
área efectiva de viento para un componente o panel de revestimiento corresponde a la
longitud del tramo multiplicada por el ancho efectivo, que no debe ser menor que un tercio
de la longitud del tramo. Sin embargo, para el caso de un fijador, es el área tributaria
asociada con un fijador individual.

Correa de pared: A = 7.5 x 2 = 15 m2
ó 7.5(7.5/3) = 18.75 m2 (valor a adoptar)

Panel: A = 2 x 0.6 = 1.20 m2
ó 2 ( 2/3 ) = 1.33 m2 (valor a adoptar)

Fijador: A = 2 x 0.3 = 0.6 m2

Coeficientes para paredes (GCp) de la Figura 5A
(GCp) externos C & R A (m2)
Zonas 4 y 5 Zona 4 Zona 5
Correa de pared 18.75 0.77 -0.87 -0.95
Panel 1.33 0.98 -1.08 -1.36
Fijador 0.6 1.00 -1.10 -1.40
Otros* 1.0 1.00 -1.10 -1.40
Otros* 50.0 0.70 -0.80 -0.80
Nota: * Otros C & R pueden ser puertas, ventanas, etc.

Cálculos típicos para las presiones de diseño de una correa de pared en la Zona 4:

Para presión negativa máxima
p = 1001[(-0.87) – (± 0.18)]
p = - 1051 N/m2 con presión interna positiva (valor a adoptar)
p = - 691 N/m2 con presión interna negativa

Para presión positiva máxima
p = 1001[(0.77) – (± 0.18)]
p = 591 N/m2 con presión interna positiva
p = 951 N/m2 con presión interna negativa (valor a adoptar)

Presiones netas en componentes de paredes (N/m2)
Presión de diseño que controla, en N/m2
Componente Zona 4 Zona 5
Positiva Negativa positiva negativa
Correa de pared 951 -1051 951 -1131
Panel 1161 -1261 1161 -1542
Fijador 1181 -1281 1181 -1582
A ≤ 1.0 m2 1181 -1281 1181 -1582
A ≥ 50.0 m2 881 -981 881 -981

Reglamento Argentino de Acción del Viento Guía Cap. 3 - 38

<!-- p. 23 -->

Presiones en componentes y revestimientos de cubierta

Areas efectivas de viento para C & R de cubierta:

Correa: A = 7.5 (1.5) = 11.25 m2
ó 7.5 (7.5/3) = 18.75 m2 (valor a adoptar)
Panel: A = 1.5 (0.6) = 0.90 m2 (valor a adoptar)
ó 1.5 (1.5/3) = 0.75 m2

Fijador: A = 1.5 (0.3) = 0.45 m2

Coeficientes (GCp) para cubierta de la Figura 5B . 10 \< θ ≤30o
(GCp) externos Componente A (m2)
Zonas 1,2 y 3 Zona 1 Zonas 2 y 3
Correa 18.75 0.3 -0.8 -1.4
Panel 0.90 0.5 -0.9 -2.1
Fijador 0.45 0.5 -0.9 -2.1
Otros* ≤1.0 0.5 -0.9 -2.1
Otros* ≥ 10.0 0.3 -0.8 -1.4
Nota: * Otros C & R pueden ser lucernas, etc.

Cálculos típicos para las presiones de diseño para correa en Zona 1:

Para presión negativa máxima
p = 1001[(-0.8) – (± 0.18)]
p = - 981 N/m2 con presión interna positiva (valor a adoptar)
p = - 621 N/m2 con presión interna negativa

Para presión positiva máxima
p = 1001[(0.3) – (± 0.18)]
p = 120 N/m2 con presión interna positiva
p = 480 N/m2 con presión interna negativa (valor a adoptar)

Presiones netas en componentes de cubierta (N/m2)
Presiones de diseño que se adoptan, N/m2
Componente Positiva Negativa
Zonas 1,2 y 3 Zona 1 Zonas 2 y 3
Correa 480 -981 -1582
Panel 681 -1081 -2282
Fijador 681 -1081 -2282
A ≤ 1.0 m2 681 -1081 -2282
A ≥ 10.0 m2 480 -981 -1582

Reglamento CIRSOC 102, Guía Cap. 3 - 39

<!-- p. 24 -->

Caso particular de montante que atraviesa zonas 4 y 5

Ancho de Zona 5
a = 0.1 x 60 = 6 m
ó 0.4 x 11.0 = 4.40 m (valor a adoptar)
pero > 0.04 x 60 = 2.40 m
\> 1.0 m

Promedio ponderado de la presión de diseño =
\4. 40(− 1131) + (7. 50 − 4. 40 )(− 1051) = = − 1098 N/m2
7.50

Este procedimiento de promedios ponderados se puede usar para otros C&R.

Caso particular de correa-puntal

Las correas que actúan como puntales en el vano extremo experimentan:

a) presiones de levantamiento como parte integrante de la cubierta y
b) adicionalmente están sujetas a carga axial como parte del SPRFV.

Componente de presión

La correa está ubicada en Zona 1 y Zona 2.
Ancho de Zona 2 .............. a = 4.40 m

Promedio pesado de la presión de diseño =
4.40(− 1582 ) + (7.50 − 4.40 )(− 981) = = − 1334 N/m2
7.50

Componente axial correspondiente al SPRFV

La Figura 3.8(a) muestra las presiones de diseño sobre la pared extrema cuando el viento
es paralelo a la cumbrera con presión interna positiva (consistente con el levantamiento
mayor sobre la correa). Admitiendo que la pared extrema está apoyada en su borde
inferior y en la parte superior en la línea de cubierta, se puede determinar la fuerza axial
efectiva sobre la correa.

Carga combinada de diseño sobre la correa-puntal

1334 N/m2

Reacción sobre la
pared extrema en el
plano de la cubierta
(de la Figura 3.8 a)

Reglamento Argentino de Acción del Viento Guía Cap. 3 - 40

<!-- p. 25 -->

3.4. EJEMPLO 4

Este ejemplo ilustra el empleo de las disposiciones del Reglamento, para la determinación
de las presiones de diseño en los SPRFV de edificios de baja altura. Con este propósito, el
edificio a considerar presenta las mismas dimensiones que el edificio del Ejemplo 3. Las
presiones de diseño sobre componentes y revestimientos son las mismas que en el
Ejemplo 3. Los datos del edificio son:

Ubicación: Provincia de Tucumán.
Terreno: Rural, plano.
Dimensiones: 60 m x 75 m en planta.
Altura de alero 6 m.
Pendiente de la cubierta 1:3 (18º26’).
Estructuración: Pórticos rígidos salvando la luz de 60 m.
Separación entre pórticos: 7.5 m.
Arriostramientos en dirección de los 75 m.
Aberturas uniformemente distribuidas.

Edificios de baja altura

El Reglamento presenta dos condiciones para calificar a un edificio como de baja altura:

\1) La altura media de la cubierta debe ser menor que 20 m, y
\2) La altura media de la cubierta no debe exceder la mínima dimensión horizontal
(Capítulo 2). Un edificio que cumpla estas condiciones se considera de baja
altura y los coeficientes de presión externa se extraen de la Figura 4.

Exposición, clasificación del edificio y velocidad básica de viento

Las mismas del Ejemplo 3: Exposición C
Categoría II
V = 40 m/s

Cumbrera

3

1
Pórtico Alero
Arriostramiento
Esquina 2
Correa
6 m

Correa de pared

30 m
7.5 m 75 m

60 m 30 m

Esquina 1
Fig. 3.9: Dimensiones y estructuración del edificio de baja altura del Ejemplo 4

Reglamento CIRSOC 102, Guía Cap. 3 - 41

<!-- p. 26 -->

Presiones dinámicas

Las disposiciones del Reglamento para el SPRFV de edificios de baja altura establecen el
uso de la presión dinámica a la altura media de la cubierta en el cálculo de las presiones
internas y externas, incluyendo la pared a barlovento.

Altura media de la cubierta: h =11 m
Las presiones dinámicas se computan con:

qh = 0.613 Kh Kzt Kd V2 Ι (N/m2)

siendo:
qh presión dinámica a la altura media h de la cubierta.
Kh = 1.02 para Exposición C.
Kzt = 1.0 (factor topográfico).
Kd factor de direccionalidad, solo interviene en casos de combinaciones de
carga.
V = 40 m/s, velocidad básica.
Ι = 1.0 para Categoría II.

Presión dinámica a la altura media h de la cubierta.

qh = 0.613 x 1.02 x 1.0 x 1.0 x 402 = 1001 N/m2,

Presiones de diseño para el SPRFV

La ecuación para el SPRFV en edificios de baja altura es, según el artículo 5.12.2.2:

p = qh[(GCpf) – (GCpi)]
siendo:
qh presión dinámica para la altura media de la cubierta, en Exposición C.
(GCpf) coeficientes de presión externa, según la Figura 4.
(GCpi) coeficientes de presión interna, según laTabla 7.

Para obtener las acciones críticas de viento para el SPRFV, incluyendo la torsión, se
deben aplicar por separado los dos casos de carga, A y B, indicados en la Figura 4, en
cada esquina del edificio (ver Figura C-2). Para cada uno de ellos se deben considerar las
presiones internas tanto negativas como positivas, con lo cual se llega a un total de 16
condiciones de carga diferentes. Sin embargo, si el edificio es simétrico, tal número se
reduce a 8 (2 casos de carga, 2 esquinas a barlovento y 2 presiones internas).

Al aplicar las cargas de los casos A y B a la esquina 2 que se muestra en la Figura 3.9
(edificio rotado 90 grados), las zonas 2 y 3 se suponen separadas por una línea de
cumbrera imaginaria, orientada normalmente a la línea de cumbrera real y bisectando la
misma. Además, el ángulo de cubierta θ se admite nulo cuando se eligen los valores de
(GCpf) para el caso de carga A en la esquina 2 (ver la Figura C-2).

Reglamento Argentino de Acción del Viento Guía Cap. 3 - 42

<!-- p. 27 -->

Valores de los coeficientes (GCpf) externos

Los coeficientes de cubierta y pared son función de la pendiente θ de la cubierta. Se
destacan en el edificio 8 superficies definidas para el caso A: 4 superficies interiores con
respecto a los bordes del edificio y 4 superficies de zonas extremas. Para el caso B se
identifican 12 superficies: 6 superficies interiores y 6 superficies de zonas extremas.

Ancho de una superficie de zona extrema: 2a = 2(0.1)(60) = 12 m
ó 2(0.4)(11) = 8.8 m (valor a adoptar)
pero > 2(0.04)(60) = 4.8 m
\> 2(1.0) = 2 m

Esquina 1: Caso A, GCpf (θ= 18.43º)
Superficie θ (o)
1 2 3 4 1E 2E 3E 4E
0-5 0.40 -0.69 -0.37 -0.29 0.61 -1.07 -0.53 -0.43
18.4* 0.52 -0.69 -0.47 -0.42 0.78 -1.07 -0.67 -0.62
20 0.53 -0.69 -0.48 -0.43 0.80 -1.07 -0.69 -0.64
Nota: * Interpolado linealmente

Esquinas 1 y 2 : Caso B, GCpf
Superficie
Ubicación
1 2 3 4 5 6
Interior -0.45 -0.69 -0.37 -0.45 0.40 -0.29
Borde* -0.48 -1.07 -0.53 -0.48 0.61 -0.43
Nota: * Zonas 1E, 2E, 3E, 4E, 5E y 6E en la Figura 4

Esquina 2: Caso A, GCpf ( θ= 0o)
Superficie θ (o)
1 2 3 4 1E 2E 3E 4E
0-5 0.40 -0.69 -0.37 -0.29 0.61 -1.07 -0.53 -0.43

Valores de los coeficientes (GCpi) internos

Las aberturas se suponen uniformemente distribuidas en las paredes. El coeficiente de
presión interna dado en la Tabla 7 es:

(GCpi) = ± 0.18

Presiones de diseño (N/m2)

Cálculo típico para las presiones de diseño:

Esquina 1, Caso A: Superficie 1

p = 1001[(0.52) – (± 0.18)]
p = 701 N/m2 con presión interna negativa
p = 340 N/m2 con presión interna positiva

Reglamento CIRSOC 102, Guía Cap. 3 - 43

<!-- p. 28 -->

Esquina 1. Caso A: Superficie 2E

p = 1001[(-1.07) – (± 0.18)]
p = -891 N/m2 con presión interna negativa
p = -1251 N/m2 con presión interna positiva

Presiones de diseño, Esquina 1: Caso A
Presiones de diseño, N/m2
Superficie (GCpf)
(+GCpi) (-GCpi)
1 0.52 340 701
2 -0.69 -871 -511
3 -0.47 -651 -290
4 -0.42 -601 -240
1E 0.78 601 961
2E -1.07 -1251 -891
3E -0.67 -851 -490
4E -0.62 -801 -440

Presiones de diseño, Esquinas 1 y 2: Caso B
Presiones de diseño, N/m2
Superficie (GCpf)
(+GCpi) (-GCpi)
1 -0.45 -631 -270
2 -0.69 -871 -511
3 -0.37 -551 -190
4 -0.45 -631 -270
5 0.40 220 581
6 -0.29 -470 -110
1E -0.48 -661 -300
2E -1.07 -1251 -891
3E -0.53 -711 -350
4E -0.48 -661 -300
5E 0.61 430 791
6E -0.43 -611 -250

Presiones de diseño. Esquina 2: Caso A
Presiones de diseño, N/m2
Superficie (GCpf)
(+GCpi) (-GCpi)
1 0.40 220 581
2 -0.69 -871 -511
3 -0.37 -551 -190
4 -0.29 -470 -110
1E 0.61 430 791
2E -1.07 -1251 -891
3E -0.53 -711 -350
4E -0.43 -611 -250

Reglamento Argentino de Acción del Viento Guía Cap. 3 - 44

<!-- p. 29 -->

Aplicación de presiones en superficies 2 y 3 del edificio

La nota al pie 4(a) de la Figura 4 establece que el coeficiente de presión (GCpf) sobre la
cubierta, si es negativo en zona 2, se aplica en dicha zona en correspondencia con una
distancia desde el borde de la cubierta igual a 0.5 veces la dimensión horizontal del edificio
medida perpendicularmente a la línea del alero ó 2.5h , se debe adoptar el menor valor de
ambos; al resto de la zona 2, que se extiende hasta la línea de cumbrera, le corresponde
el coeficiente de presión GCpf para la zona 3.

0.5(60) = 30 m
2.5h = 2.5(11) = 27.5 m (valor a adoptar)

En consecuencia, la zona 3 se aplica sobre una distancia igual a 31.6 – 27.5 = 4.10 m, es
decir en lo que normalmente se considera zona 2 adyacente a la línea de cumbrera

Casos de carga

Debido a la simetría del edificio, los ocho casos muestran todas las combinaciones
necesarias, en tanto y en cuanto el diseño se ejecute aplicando las cargas para cada una
de las cuatro esquinas. Estas combinaciones de carga presentadas en las Figuras 3.10 a
3.17 se deben usar para diseñar el pórtico rígido y los arriostramientos.

Las presiones de diseño en componentes y revestimientos son las mismas que en el
Ejemplo 3.

Reglamento CIRSOC 102, Guía Cap. 3 - 45

<!-- p. 30 -->

651 N/m 2
601 N/m 2 651 N/m2

801 N/m2
851 N/m 2 871 N/m 2

1251 N/m 2 Esquina 2

340 N/m 2
27.5

601 N/m 2

Esquina 1

8.80

NOTA: Las presiones de 871 y
1251N/m 2 actúan hasta 27.50
m; los 4.10 m restantes hasta
la línea de cumbrera tendrán
2 DIRECCIÓN DEL presiones de 651 y 851 N/m.
VIENTO

Figura 3.10 Presiones de diseño para Caso A en Esquina 1 con presión interna
positiva

290 N/m 2

240 N/m 2

440 N/m 2
490 N/m 2 511 N/m 2

891 N/m 2 Esquina 2

701 N/m2
27.5

961 N/m 2

Esquina 1

8.80

NOTA: Las presiones de 511 y
891N/m 2 actúan hasta 27.50
m; los 4.10 m restantes hasta
la línea de cumbrera tendrán
2 DIRECCIÓN DEL presiones de 290 y 490 N/m.
VIENTO

Figura 3.11 Presiones de diseño para Caso A en Esquina 1 con presión interna
negativa

Reglamento Argentino de Acción del Viento Guía Cap. 3 - 46

<!-- p. 31 -->

551 N/m2

631 N/m 2

470 N/m 2

661 N/m2
711 N/m 2 2 871 N/m
611 N/m 2

1251 N/m2 Esquina 2

631 N/m 2

220 N/m 2

661 N/m 2
430 N/m 2
4.40 Esquina 1
8.80

DIRECCIÓN DEL
VIENTO

Figura 3.12 Presiones de diseño para Caso B en Esquina 1 con presión interna
positiva

190 N/m2

270 N/m 2

110 N/m 2
300 N/m 2
350 N/m 2 2 511 N/m
250 N/m 2

891 N/m 2 Esquina 2

270 N/m2

581 N/m 2

300 N/m 2
791 N/m 2
4.40 Esquina 1
8.80

DIRECCIÓN DEL
VIENTO

Figura 3.13 Presiones de diseño para Caso B en Esquina 1 con presión interna
negativa

Reglamento CIRSOC 102, Guía Cap. 3 - 47

<!-- p. 32 -->

Línea de cumbrera imaginaria
551 N/m 2

2 2 551 N/m 470 N/m 2 871 N/m

2 2 870 N/m 711 N/m 27.5

1251 N/m2
611 N/m2

Esquina 1

220 N/m 2

430 N/m 2
Esquina 2

8.80

DIRECCIÓN DEL
VIENTO
Figura 3.14 Presiones de diseño para Caso A en Esquina 2 con presión interna
positiva

Línea de cumbrera imaginaria
190 N/m 2

2 2 190 N/m 110 N/m 2 511 N/m

250 N/m 2 350 N/m 2 511 N/m 2 27.5

891 N/m 2

Esquina 1

581 N/m 2

791 N/m 2

Esquina 2

8.80

DIRECCIÓN DEL
VIENTO

Figura 3.15 Presiones de diseño para Caso A en Esquina 2 con presión interna
negativa

Reglamento Argentino de Acción del Viento Guía Cap. 3 - 48

<!-- p. 33 -->

551 N/m 2
Línea de cumbrera imaginaria

551 N/m 2
631 N/m 2 470 N/m2

2 871 N/m 2 711 N/m
2 611 N/m2 871 N/m

2 2 1251 N/m 661 N/m

Esquina 1

220 N/m2 631 N/m 2

661 N/m 2
430 N/m2

Esquina 2 8.80 4.40

DIRECCIÓN DEL
VIENTO

Figura 3.16 Presiones de diseño para Caso B en Esquina 2 con presión interna
positiva

190 N/m 2
Línea de cumbrera imaginaria

190 N/m2
270 N/m 2 110 N/m2

2 511 N/m 2 350 N/m
2 250 N/m2 511 N/m

2 2 891 N/m 300 N/m

Esquina 1

581 N/m2 270 N/m 2

2 300 N/m 2 791 N/m

Esquina 2
8.80 4.40

DIRECCIÓN DEL
VIENTO

Figura 3.17 Presiones de diseño para Caso B en Esquina 2 con presión Interna
negativa

Reglamento CIRSOC 102, Guía Cap. 3 - 49

<!-- p. 34 -->

3.5. EJEMPLO 5

En este ejemplo se determinan las presiones de diseño para un depósito de ventas por
menor. Los datos del edificio son:

Ubicación: Ciudad de Necochea, Pcia. de Buenos Aires.
Topografía: Homogénea.
Terreno: Suburbano.
Dimensiones: 12 m x 24 m en planta.
Cubierta en monopendiente de 14º, con alero de
2.10m en planta.
Altura de paredes: 4.50 m en el frente y 7.50 m atrás.
Estructuración: Paneles de hormigón liviano en todos los costados
apoyados en sus bordes inferior y superior. Entramado
de acero en el frente para alojar ventanas vidriadas y
puertas.
Las vigas de cubierta salvan una luz de 12.36 m, más
2.16 m de volado. Su separación es de 1.50 m entre
ejes.
Revestimientos: Las medidas de puertas y vidrios varían. Estos últimos
no se consideran resistentes a impactos de proyectiles
generados por el viento.
Los paneles de cubierta son de 0.60 m de ancho y 6.0
m de largo.

7.5 m
12.0 m
4.5 m

2.1 12.0 m

2.1 m CORTE

24.0 m

PLANTA

Figura 3.18 Dimensiones del depósito para ventas por menor

Exposición y clasificación del edificio

El edificio se ubica en un terreno suburbano, por lo que se debe usar Exposición B.

Se considera que en el depósito no entrarán 300 personas simultáneamente, y le
corresponde por lo tanto la Categoría II.

Reglamento Argentino de Acción del Viento Guía Cap. 3 - 50

<!-- p. 35 -->

Velocidad básica del viento

Para Necochea se usa la velocidad básica 50 m/s.

Presiones dinámicas

Se computan con la ecuación: qz = 0.613 Kz Kzt Kd V2 Ι (N/m2)

donde:

Kz se obtiene de la Tabla 3,
Kzt = 1.0 (terreno homogéneo),
Kd sólo se considera en casos de combinaciones de carga,
Ι = 1.0 para edificios de categoría II,
V = 50 m/s, velocidad básica de viento.

Las presiones dinámicas q se basan en Exposición B para el SPRFV. Para el diseño de
los componentes y revestimientos de edificios con altura media h \< 20 m se emplean las
presiones dinámicas qh usando la exposición definida en el artículo 5.6.3.1. La altura
media en el presente caso es de 6.0 m.

Presiones dinámicas qz y qh , (N/m2)
Kz qz,qh
Altura h (m) Exposición B Exposición B
Caso 1* Caso 2* Caso 1* Caso 2*
0-5 0.72 0.59 1103 904
6 0.72 0.62 1103 950
7.5 0.72 0.66 1103 1011
Nota: (*) Ver Notas de Tabla 5

Presiones de diseño para el SPRFV

La ecuación para edificios de todas las alturas es, según el artículo 5.12.2.1:

p = q GCp – qi(GCpi)
donde:

q = qz para pared a barlovento y qh para pared a sotavento, paredes laterales y
cubierta.
qi = qh para la evaluación de la presión interna negativa en edificios parcialmente
cerrados.
qi = qz para evaluar la presión interna positiva, que en forma conservativa se puede
calcular a la altura h (qi = qh).
G se determina según artículo 5.8.1, en tanto que los valores de Cp se obtienen
de la Figura 3 y (GCpi) de la Tabla 7.

Las especificaciones del Reglamento permiten el uso de los coeficientes de presión
externa (GCpf) dados en la Figura 4. Sin embargo, los valores de esta figura fueron
obtenidos mediante estudios en túnel de viento de edificios con cubierta a dos aguas. Su
empleo en el caso de cubiertas en monopendiente requiere por lo tanto una cuidadosa
interpretación. El Ejemplo 4 con un pórtico a dos aguas ilustra el uso de los coeficientes de

Reglamento CIRSOC 102, Guía Cap. 3 - 51

<!-- p. 36 -->

presión de la Figura 4, y los comentarios del Reglamento sirven para fundamentar los
valores de (GCpf).

Factor de efecto de ráfaga, G

El factor de efecto de ráfaga para edificios no flexibles, según el artículo 5.8.1 es: G = 0.85.

Coeficientes de presión externa en paredes, Cp

Los valores para la pared a sotavento dependen de L/B, y son diferentes para las dos
direcciones siguientes:

\1) viento paralelo a la pendiente de cubierta, y
\2) viento normal a la pendiente de cubierta.

Coeficientes de presión en paredes, Cp
Superficie Dirección del viento L/B Cp
Pared a sotavento II a la pendiente de cubierta 0.5 - 0.5
Pared a sotavento ⊥ a la pendiente de cubierta 2.0 - 0.3
Pared a barlovento - - 0.8
Paredes laterales - - - 0.7

Coeficientes de presión externa en cubierta, Cp

Dado que el edificio tiene una cubierta monopendiente, la superficie de cubierta para
viento dirigido paralelamente a la pendiente puede ser una superficie a barlovento o a
sotavento. En este caso el valor de h/L es 0.5.

Cuando el viento es normal a la pendiente de cubierta, el ángulo θ = 0 y h/L = 0.25.

Coeficientes de presión en cubierta, Cp
Dirección del viento h/L θo Cp
II a la pendiente de cubierta 0.5 14 -0.74 como pendiente a barlovento
II a la pendiente de cubierta 0.5 14 -0.50 como pendiente a sotavento
\-0.90 (0-6 m)*
⊥ a la pendiente de cubierta 0.25 0 -0.50 (6-12 m)
\-0.30 (12-24 m)
Nota: * Distancia desde el borde a barlovento de la cubierta.

Para el voladizo, el artículo 5.11.4.1 especifica: Cp = 0.8 .

Coeficientes de presión interna (GCpi)

La velocidad básica del viento es 50 m/s y el vidriado no es capaz de resistir impactos de
proyectiles. El edificio satisface las condiciones de la Tabla 7. Independientemente de las
aberturas en paredes y cubierta, los coeficientes de presión interna son:

(GCpi) = ± 0.55

Reglamento Argentino de Acción del Viento Guía Cap. 3 - 52

<!-- p. 37 -->

Cálculo típico para las presiones de diseño en SPRFV (viento paralelo a la pendiente
con la pared de 4.50 m a barlovento)

Presión sobre la pared a sotavento:
p = qh GCp – qh (±GCpi)
\= 950 (0.85) (-0.5) – 950 (0.55)
\= -926 N/m2 para presión interna positiva

y p = 950 (0.85) (-0.5) – 950 (-0.55)
\= 119 N/m2 para presión interna negativa

Presión sobre la superficie superior del alero:
p = qh GCp
\= 950 (0.85) (-0.74)
\= -598 N/m2

Presión sobre la superficie inferior del alero (idem a la presión externa en pared a
barlovento):
p = qz GCp
\= 904 (0.85) (0.8)
\= 615 N/m2

Presiones de diseño para el SPRFV: Viento paralelo a la pendiente de la cubierta
Dirección Presión de
qz, qh Cp* del viento Superficie z (m) diseño(N/m2) (N/m2) externa
(+GCpi) (-GCpi)
Pared a Pared a barlovento 0-5 904 0.80 92 1137
barlovento Pared a sotavento 0-7.5 950 -0.50 -926 119
4.5 m Pared lateral todas 950 -0.70 -1088 -43
Cubierta -- 950 -0.74 -1120 -75
Volado(superior) -- 950 -0.74 -598** -598**
Volado(inferior) -- 904 0.80 615** 615**
Pared a 0-5 904 0.80 92 1137
barlovento Pared a barlovento 5-6 950 0.80 124 1169
7.5 m 6-7.5 1011 0.80 165 1210
Pared a sotavento todas 950 -0.50 -926 119
Pared lateral todas 950 -0.70 -1088 -43
Cubierta -- 950 -0.50 -926 119
Volado(superior) -- 950 -0.50 404** -404**
Volado(inferior) -- -- -- 0** 0**
Notas: *El cálculo de las presiones externas incluye G = 0.85
\** Las presiones sobre el voladizo no están afectadas por las presiones internas.
Conservativamente se toma qi = qh

Reglamento CIRSOC 102, Guía Cap. 3 - 53

<!-- p. 38 -->

Presiones de diseño para el SPRFV: Viento normal a la pendiente de la cubierta
z ó Distancia*** Presión de diseño
Superficie (m) qz , qh (N/m2)* Cp (N/m2)
(+GCpi)** (-GCpi)**
0-5 904 0.8 92 1137
Pared a
5-6 950 0.8 124 1169 barlovento
6-7.5 1011 0.8 165 1210
Pared a sotavento todas 950 -0.3 -765 280
Pared lateral todas 950 -0.7 -1088 -43
0-6 950 -0.9 -1249 -204
Cubierta**** 6-12 950 -0.5 -926 119
12-24 950 -0.3 -765 280
Notas: * El cálculo de las presiones externas incluye G = 0.85
\** La presión interna está asociada con conservativamente qh = 950 N/m2.
\*** La distancia a lo largo de la cubierta se mide desde el borde a barlovento
dominante.
\**** Sobre el voladizo actúa solamente la presión externa.

1120 N/m2

598 N/m 2

Viento 926 N/m
615 N/m 2 Presión interna positiva
2 (+ GC pi ) 92 N/m

12.0 m

75 N/m 2

598 N/m 2

Viento 119 N/m 2
615 N/m 2 Presión interna negativa
(- GC pi )
1137 N/m2

12.0 m

Figura 3.19 Presiones de diseño para el SPRFV, viento paralelo a la pendiente de
cubierta

Reglamento Argentino de Acción del Viento Guía Cap. 3 - 54

<!-- p. 39 -->

926 N/m 2

165 N/m 2
6 m 2 404 N/m2 124 N/m
5 m
Viento
Presión interna positiva
2 92 N/m 2 (+ GC pi ) 926 N/m

12.0 m

119 N/m 2
1210 N/m2 2 404 N/m
6 m
1169 N/m2
5 m
Viento
Presión interna negativa
1137 N/m 2 (- GC pi ) 119 N/m2

12.0 m

Figura 3.20 Presiones de diseño para el SPRFV, viento paralelo a la pendiente de
cubierta

Reglamento CIRSOC 102, Guía Cap. 3 - 55

<!-- p. 40 -->

6.0 m 6.0 m
1249 N/m 2 2 926 N/m 2 765 N/m

165 N/m 2 7.5 m
6 m
Viento 124 N/m 2 5 m
765 N/m 2 Presión interna positiva
(+ GC pi )
92 N/m 2

24.0 m

6.0 m 6.0 m
2 280 N/m2 204 N/m 2 119 N/m

1210 N/m 2 7.5 m
6 m
Viento 1169 N/m 2 5 m
280 N/m2
Presión interna negativa
(-GCpi )
1137 N/m 2

24.0 m

Figura 3.21 Presiones de diseño para el SPRFV, viento normal a la pendiente de
cubierta

Presiones de diseño para componentes y revestimientos

La ecuación para las presiones de diseño sobre componentes y revestimientos en el caso
de edificios con altura media h ≤ 20 m está dada en el artículo 5.12.4.1 y es la siguiente:

qh[(GCp) – (GCpi)]
siendo:
qh la presión dinámica correspondiente a la altura media de la cubierta,
usando la exposición definida en el artículo 5.6.3.1.
GCp los coeficientes de presión externa extraídos de Figuras 5A y 7A.
GCpi = ± 0.55 , previamente determinados de la Tabla 7.

Presiones de diseño en paredes

En razón de que los paneles de paredes están apoyados en sus bordes superior e inferior,
el área efectiva de viento depende de la longitud de los mismos.

Area efectiva de viento:
para tramos de 4.5 m A = 4.5 (4.5/3) = 6.75 m2
para tramos de 6 m A = 6 (6/3) = 12 m2
para tramos de 7.5 m A = 7.5 (7.5/3) = 18.75 m2

Reglamento Argentino de Acción del Viento Guía Cap. 3 - 56

<!-- p. 41 -->

Coeficientes de presión externa en paredes (GCp)
Coeficientes de presión
Area (m2) Zonas 4 y 5 Zona 4 Zona 5
(GCp) (-GCp) (-GCp)
6.75 0.85 -0.95 -1.11
12 0.81 -0.91 -1.02
18.75 0.77 -0.87 -0.95

Ancho de zona 5 (Figura 5A)

a = 0.1 (12) = 1.20 m (valor a adoptar)
ó 0.4 (6) = 2.40 m
pero > 0.04 (12) = 0.48 m
\> 1.00 m

Las presiones de diseño son críticas cuando la suma algebraica de las presiones externas
e internas es un máximo. A continuación se calculan las presiones de diseño en paredes.

Cálculo típico para las presiones de diseño en paredes de 4.50 m, Zona 4

p = 1103 [(0.85)-(-0.55)] = 1544 N/m2
p = 1103 [(-0.95)-(0.55)] = -1655 N/m2

Presiones de diseño en paredes, N/m2
Presiones de diseño, N/m2
Altura de pared
Zonas 4 y 5 Zona 4 Zona 5
(m)
positiva negativa negativa
4.5 1544 -1655 -1831
6.0 1500 -1610 -1732
7.5 1456 -1566 -1655
Notas : qh = 1103 N/m2.
Las presiones corresponden al caso 1 para terrenos en
exposición B de la Tabla 5.

Los paneles de pared se deben calcular para presiones determinadas para zonas 4 y 5
usando las áreas tributarias correspondientes.

Las presiones de diseño para puertas y vidriados se pueden estimar usando coeficientes
de presión apropiados, asociados con sus áreas efectivas de viento.

Presiones de diseño en cubierta

Area efectiva de viento:
Vigas de cubierta, A = (12.36 + 2.16) x 1.50 = 21.78 m2
ó = (14.52)(14.52)/3 = 70.28 m2 (valor a adoptar)
Panel de cubierta, A = (1.5)(0.60) = 0.90 m2 (valor a adoptar)
ó = (1.5)(1.5)/3 = 0.75 m2

Reglamento CIRSOC 102, Guía Cap. 3 - 57

<!-- p. 42 -->

Aún cuando el área efectiva de las vigas de cubierta sea mayor que 70 m2, sus
coeficientes de presión externa (GCp) se determinan sobre la base de componentes y
revestimientos. El artículo 5.12.1.3, según el cual se pueden usar para un componente
principal especificaciones para el SPRFV, es válido solamente si el área tributaria es
mayor que 70 m2. El área tributaria para una viga de cubierta es 21.78 m2.

El artículo 5.11.4.2 dispone que los coeficientes de presión para los voladizos de cubierta
se obtengan de la Figura 5B. Las zonas para ménsulas de cubierta en la Figura 5B son
diferentes de las zonas para cubiertas de pendiente única de Figura 7A

Coeficientes de presión externa en cubierta (GCp), θ= 14º
Coeficientes de presión, Figura 7A
Componente Area (m2) Zonas 1,2 y 3 Zona 1 Zona 2 Zona 3
(GCp) (-GCp) (-GCp) (-GCp)
Viga 70.28 0.3 -1.1 -1.2 -2.0
Panel 0.90 0.4 -1.3 -1.6 -2.9
Coeficientes de presión, Figura 5B
Zonas 1,2,y 3 Zona 1 Zona 2 Zona 3
(GCp) (-GCp) (-GCp) (-GCp)
Viga 70.28 0.3 -0.8 -2.2 -2.5
Panel 0.90 0.5 -0.9 -2.2 -3.7

Ancho de zona (distancia a)

a = 0.1(12) = 1.2 m (valor a adoptar)
ó = 0.4(6) = 2.40 m
\> 0.04(12) = 0.48 m
\> 1.0 m

Los anchos y longitudes de zonas 2 y 3 para una cubierta de pendiente única se muestran
en la Figura 7A (varían entre a y 4a), y para los volados en la Figura 5B.

En forma similar a la determinación de las presiones de diseño sobre paredes, las
presiones críticas de diseño sobre cubiertas resultan de la suma algebraica de las
presiones externas e internas. Las presiones de diseño en las áreas en voladizos se basan
en coeficientes de presión obtenidos de la Figura 5B.

Cálculo típico para presiones en vigas

Zona 2:
p = 1103 [0.3-(-0.55)] = 938 N/m2
p = 1103[(-1.2)-(0.55)] = -1930 N/m2

Reglamento Argentino de Acción del Viento Guía Cap. 3 - 58

<!-- p. 43 -->

Presiones de diseño en cubierta, N/m2
Presiones de diseño, N/m2
Componente Zonas 1,2 y 3* Zona 1 Zona 2 Zona 3
positiva negativa negativa negativa
Viga 938 -1820 -1930 -2813
Viga en voladizo 500** -882 -2427 -2758
Panel 1048 -2041 -2371 -3805
Panel en voladiz 552 -993 -2427 -4081
Notas: qh = 1103 N/m2. Las presiones de diseño corresponden al caso 1 para
exposición B de la Tabla 5.
\* Zonas en voladizo según la Figura 5B.
\** El artículo 1.4 especifica un mínimo de 500 N/m2.

Las zonas para la cubierta con pendiente única y su voladizo se muestran en la Figura
3.22. Los paneles se deben calcular para las presiones indicadas.

24.00 m

Viento para
Viento para 4.80 m carga 3 4.80 m
carga 1
Zona 3 para
cubierta Zona 2 para
2.40 m
cubierta

Zona 2 para
cubierta
Viga 1 (ancho: 1.2 m) Zona 2 para 9.60 m
Viga 2 cubierta
(ancho: 1.2 m)

Zona 2
para alero
2.10 m
Zona 3 Zona 2 Zona 1
Viento para para alero para alero para alero
carga 2 (1.2 x 1.2 m) (ancho:1.2 m) (ancho: 0.90 m)
Viento para
carga 4

CARGA SOBRE VIGA 1 CARGA SOBRE VIGA 2

2813 N/m 2 1930 N/m 2

1930 N/m 2 1820 N/m 2
CARGA 1 2427 N/m 2 CARGA 3
882 N/m 2

2.4 9.6 2.1 2.4 9.6 2.1

1930 N/m 2 1820 N/m 2
CARGA 2 2758 N/m 2 CARGA 4 2427 N/m 2

12.0 2.1 12.0 2.1

Figura 3.22 Presiones de diseño para vigas típicas y zonas de presión para las
componentes y revestimientos de cubierta

Reglamento CIRSOC 102, Guía Cap. 3 - 59

<!-- p. 44 -->

Las presiones de diseño para las vigas de cubierta exigen una cuidadosa interpretación.
Las altas presiones en las esquinas o áreas de alero no se presentan simultáneamente en
ambos extremos. Los casos de carga sobre dos vigas son los siguientes y se muestran en
la Figura 3.22:

• Viga 1, carga 1 : zonas 2 y 3 para cubierta y zona 2 para voladizo
• Viga 1, carga 2 : zona 2 para cubierta y zonas 2 y 3 para voladizo
• Viga 2, carga 3 : zonas 1 y 2 para cubierta y zona 1 para voladizo
• Viga 2, carga 4 : Zona 1 para cubierta y zonas 1 y 2 para voladizo

Por simplicidad, en la Figura 3.22 se usó solamente una zona para las presiones sobre el
voladizo.

Reglamento Argentino de Acción del Viento Guía Cap. 3 - 60

<!-- p. 45 -->

3.6. EJEMPLO 6

En este ejemplo se determinan las fuerzas de viento de diseño para un cartel de
señalización elevado sobre el terreno. El ejemplo se presta para ilustrar la aplicación de
dos items:

(1) el factor de efecto de ráfaga para estructuras flexibles, y
(2) el uso de coeficientes de fuerza para otras estructuras.

Los datos del cartel son:

Ubicación: Autopista en la provincia de Mendoza.
Terreno: Plano y abierto.
Dimensiones: 15.0 m de ancho por 6.0 m de altura. El cartel se montó sobre
dos columnas circulares de acero de 400 mm de diámetro. El
borde inferior del mismo se encuentra a 18 m sobre el terreno.
Estructuración: Estructura alta y flexible. La frecuencia fundamental estimada
es de 0.7 Hz y la relación de amortiguamiento crítico es 0.01.
(La frecuencia natural de una estructura se puede calcular de
diferentes maneras, y ha sido predeterminada en este ejemplo).

RECUERDE:
\+ = 6.0 m

3.0 m 9.0 m 3.0 m

18.0 m

Figura 3.23 Dimensiones de un cartel de señalización en una ruta interprovincial

Reglamento CIRSOC 102, Guía Cap. 3 - 61

<!-- p. 46 -->

Exposición y características de la construcción

El cartel se ubica en un área abierta, en consecuencia se trata de Exposición C.

El colapso del cartel implica un escaso riesgo para la vida humana puesto que se emplaza
lejos de la carretera y no se localiza en un área populosa. La estructura se clasifica por lo
tanto como de Categoría I de la Tabla A-1.

Velocidad básica de viento

Se determina en base al mapa de la Figura 1. La velocidad básica se fija en 40 m/s.

Presiones dinámicas

Las presiones dinámicas se computan mediante:

qz = 0.613 Kz Kzt Kd V2 Ι (N/m2)
donde:

V = 40 m/s
Kd debe usarse cuando se calculan otras combinaciones de carga.
Ι = 0.87 para Categoría I (Tabla 2).
Kzt = 1.0 por ser el terreno plano.
Kz = valores de la Tabla 5 para z igual a 9,18 y 24 m. Más divisiones de z no se
justifican debido a que las cargas sobre las columnas circulares son
pequeñas comparadas con las que actúan sobre el cartel elevado.

Presiones dinámicas , N/m2
Altura (m) Kz qz (N/m2)
9.0 0.98 836
18.0 1.13 964
24.0 1.21 1032

Fuerzas de diseño para el SPRFV

La ecuación dada en Tabla 1 es:

F = qz Gf Cf Af
donde:

qz es el valor determinado en la tabla anterior.
Gf es el factor de efecto de ráfaga, se calcula según el artículo 5.8.2 o mediante
un análisis racional que cumpla con las disposiciones del artículo 5.8.3, debido a
que f \< 1 Hz.
Cf son los valores de los coeficientes de fuerza de Tablas 10 y 11.
Af = 6 x 15 = 90 m2. Para viento normal y oblicuo ver Nota 4 de la Tabla 11.

Reglamento Argentino de Acción del Viento Guía Cap. 3 - 62

<!-- p. 47 -->

Coeficiente de fuerza Cf

Este cartel califica como un cartel sobre el nivel del suelo con M / N = 15 / 6 = 2.5; Cf = 1.2
(Tabla 11).

Los soportes son redondos.

De la Tabla 10:
h 18
D q z = 0 . 40 836 = 11 . 57 > 5 . 3 y = = 45
D 0 . 40
Para una superficie moderadamente suave, Cf = 0.7

Factor de efecto de ráfaga Gf

El factor de efecto de ráfaga Gf se determina con la ecuación 6 del artículo 5.8.2:

2 2 2 2  1 + 7.1 I z g Q Q + g R R   G f = .0925
 1 + 7.1 g v I z   
donde:
zI se obtiene de la ecuación 3.
gQ y gv se toman igual a 3.4 según el artículo 5.8.2.
gR se obtiene de la ecuación 7.
Q se determina con la ecuación 4.
R se determina con la ecuación 8.
z es la altura equivalente de la estructura, que se usa para determinar el valor
nominal de zI ; para edificios el valor recomendado es 0.6 h, pero para el cartel se
debe tomar a la mitad del área del mismo o sea 21 m.
c, l , α, α , ε , etc., se obtienen de la Tabla 4.

1 / 6 1 / 6
 10   10 
I = c   = 0 . 2   = 0 . 176 (ecuación 3) z
 z   21 

ε 1 / 5
 z   21 
Lz = l   = 152   = 176 m (ecuación 5)
 10   10 

.0 577 gR = 2 ln (3600 n1 ) + 2 ln (3600 n1 )

.0 577 = 2 ln (3600 × 7.0 ) + = .4 1035 (ecuación 7)
2 ln (3600 × 7.0 )

2 1 1 Q = = = 0 . 858 (ecuación 4)
0 . 63 0 . 63
 B + h   15 + 6 
1 + 0 . 63   1 + 0 . 63  176  L  z 
Nota: En la ecuación 4, B y h son las dimensiones del cartel.

Reglamento CIRSOC 102, Guía Cap. 3 - 63

<!-- p. 48 -->

α 1 / 6 . 5
 z   21 
V z = b   V = 0 . 65   40 = 29 . 14 m/s (ecuación 12)  10   10 
Nota: V es la velocidad básica de viento.

n1 Lz 0 . 7 × 176 N1 = = = 4 . 23 (ecuación 10)
V z 29 . 14
Nota: n1 es la frecuencia natural de la estructura.

7 . 47 N 1
R n = 5 / 3 = 0 . 056 (ecuación 9) (1 + 10 .3 N 1 )

4 . 6 n1 h 4 . 6 × 0 . 7 × 24 Para Rh: η = = = 2 . 652 (ecuación 11)
V z 29 . 14

Nota: h se toma igual a 24 m por cuanto la respuesta resonante depende de
la altura total.

1 1 − 2 η Rh = − (1 − e ) = 0 . 3063 (ecuación 11a)
η 2 η 2

4 . 6 × 0 . 7 × 15
Para RB: η = = 1 .657 (siendo B = 15 m)
29 . 14

RB = 0.4280

15 . 4 × 0 . 7 × 0 . 60
Para RL : η = = 0 . 222 (suponiendo la profundidad L = 0.60 m)
29 . 14

RL = 0.8671

2 1 R = R n R h R B (.053 + .047 R L ) =
β
1 = × .0056 × .03063 × .04280 × (.053 + .047 × .08671) = .0688
.001
(ecuación 8)
 2 2  1 + 1 . 7 x 0 . 176 3 . 4 x 0 . 858 + 4 . 104 x 0 . 688
Gf = 0 . 925   =1.095 (ecuación 6)  1 + 1 . 7 x 3 . 4 x 0 . 176   

Fuerza de diseño

Fuerza, F = qz Gf Cf Af

Para cada soporte:

Para 0 a 9 m F = 836×1.095×0.7×0.40 = 256 N/m
Para 9 a 18 m F = 964×1.095×0.7×0.40 = 296 N/m

Reglamento Argentino de Acción del Viento Guía Cap. 3 - 64

<!-- p. 49 -->

Para los dos soportes: 0 a 9 m: 512 N/m ; 9 a 18 m: 592 N/m

Para el cartel:
F = 1032×1.095×1.2×15 = 20341 N/m

La fuerza sobre el cartel sigue dos casos:

\1. fuerza en el centro geométrico.
\2. fuerza a 0.2×15 = 3 m hacia cualquier lado del centro geométrico (ver nota 4
de la Tabla 11).

Limitación

En ciertas circunstancias para elementos circulares, la respuesta transversal al viento
debida a desprendimiento de vórtices puede ser crítica. El Reglamento no brinda un
procedimiento para encarar la respuesta transversal al viento, pero sugiere obtener una
guía a partir de bibliografía reconocida.

Fuerza sobre componentes y revestimientos

La ecuación dada en el artículo 5.13 es:

F = qz G Cf Af

Los valores de qz son iguales que para SPRFV. Las fuerzas de diseño se pueden
determinar usando los Cf y Af apropiados para cada componente o panel de revestimiento.

Caso 1
24 m

20341 N/m Línea de
21994 N/m Fuerza

18 m

592 N/m 7.5 m 7.5 m
640 N/m

9 m Caso 2

512 N/m (*) Línea de
(*) Fuerza 554 N/m

(*) Combinada para dos soportes 4.5 m 10.5 m

Figura 3.24 Fuerzas de diseño para el cartel de señalización

Reglamento CIRSOC 102, Guía Cap. 3 - 65

<!-- p. 50 -->

Reglamento Argentino de Acción del Viento Guía Cap. 3 - 66
