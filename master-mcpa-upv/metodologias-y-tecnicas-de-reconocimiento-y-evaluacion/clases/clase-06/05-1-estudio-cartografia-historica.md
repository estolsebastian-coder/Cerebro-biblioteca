---
type: libro
title: "Diapositiva 1"
author: "Miguel"
categoria: "Metodologías y técnicas de reconocimiento y evaluación"
paginas: 32
extraccion: "texto (OCR pendiente)"
fuente: "local:D:/UPV/MCPA/Asignaturas/Metodologías y técnicas de reconocimiento y evaluación/Clases/Clase 06/05.1__ESTUDIO CARTOGRAFIA HISTORICA.pdf"
convertido: 2026-10-16
---

# Diapositiva 1

> Texto extraído de `Metodologías y técnicas de reconocimiento y evaluación\Clases\Clase 06\05.1__ESTUDIO CARTOGRAFIA HISTORICA.pdf` (32 páginas, texto (OCR pendiente)). El PDF original está en el disco D: (UPV\MCPA\Asignaturas); `<!-- p. N -->` marca el inicio de cada página.

<!-- p. 1 -->

estudio cartografía histórica

Miguel Sancho Mir
Profesor del Área de Expresión Gráfica Arquitectónica
Universidad de Zaragoza

<!-- p. 2 -->

OBJETIVO

Saber analizar con rigor técnico documentación cartográfica para el estudio de la
imagen histórica de la ciudad o el territorio

2

<!-- p. 3 -->

ÍNDICE

\1. Análisis gráfico de cartográfica: conceptos y ejemplos

\2. Conceptos cartográficos básicos y GIS

\3. Introducción a Qgis

\4. Georrectificación + Restitución (Qgis + Cad): Práctica

3

<!-- p. 4 -->

\1. ANÁLISIS GRÁFICO DE CARTOGRÁFICA: CONCEPTOS Y EJEMPLOS

4

<!-- p. 5 -->

COORDINACIÓN CARTOGRÁFICA

¿qué es?
Trata de la verificación de relaciones
entre cartografías de distintas épocas,
tomando como puntos de apoyo las
permanencias o invariantes que
aseguran la comparación a lo largo de
la secuencia estudiada (Temes 2008)

5

<!-- p. 6 -->

COORDINACIÓN CARTOGRÁFICA

¿para que sirve?
La detección y medida de las
transformaciones en el territorio
constituyen una fuente de información
básica para en análisis de los
crecimientos, permanencia y
variaciones en los distintos recintos de
análisis.

6

<!-- p. 7 -->

COORDINACIÓN CARTOGRÁFICA

7

<!-- p. 8 -->

COORDINACIÓN CARTOGRÁFICA

Izq: Infografía sobre detalle de plano Teruel copiado en 1811. Elaboración propia. (CEME (España) [plano], 1811a ) Ctr: Detalle de plano de Teruel de 1869.
Elaboración propia. (CEME (España) [plano], 1869b ). Drch: Detalle de plano de Teruel editado en 1881. Elaboración propia. (CEME (España) [plano], 1881b).

8

<!-- p. 9 -->

COORDINACIÓN CARTOGRÁFICA

¿cómo se hace?
Se trata de un proceso inverso, en el
que se empieza a trabajar de la
cartografía más reciente, de mayor
precisión, y se avanza de forma gradual
a la más antigua, permitiendo así
evaluar y corregir gran parte de los
errores derivados de las inexactitudes
cartográficas

9

<!-- p. 10 -->

COORDINACIÓN CARTOGRÁFICA

Georreferenciación / Georrectificación
\+
Restitución

\=

Cartografía Historiográfica

10

<!-- p. 11 -->

GEORREFERENCIACIÓN

Dotar de coordenadas a ciertos puntos de un
plano en un sistema previamente establecido.

11

<!-- p. 12 -->

PUNTOS INVARIANTES O DE CONTROL

Puntos comunes del plano de referencia con
el plano a georreferenciar: convenientemente
distribuidos y fácilmente reconocibles en el
plano, pertenecientes a edificios construidos
que no hayan sufrido modificaciones en el
tiempo que afecten a su huella sobre el plano

12

<!-- p. 13 -->

GEORREFERENCIACIÓN

Si la asignación que se realiza en un Sistema
de Información Geográfica , que permite,
además, tener un control del error existente
en la cartografía

Valores residuales o error de cada punto de
control, gráfica y numéricamente

13

<!-- p. 14 -->

GEORRECTIFICACIÓN

Dotar de coordenadas a ciertos puntos de un
plano en un sistema previamente establecido
y una deformación del ráster para conseguir
un mejor ajuste al plano de referencia

14

<!-- p. 15 -->

GEORRECTIFICACIÓN

Dotar de coordenadas a ciertos puntos de un
plano en un sistema previamente establecido
y una deformación del ráster para conseguir
un mejor ajuste al plano de referencia

15

<!-- p. 16 -->

GEORRECTIFICACIÓN

Atlas of the Historical Geography of the United States (link)

16

<!-- p. 17 -->

GEORRECTIFICACIÓN

The British Library (link)

17

<!-- p. 18 -->

\2. CONCEPTOS CARTOGRÁFICOS BÁSICOS Y GIS

18

<!-- p. 19 -->

CONCEPTOS CARTOGRÁFICOS

Cartografía_ Arte de trazar mapas geográficos / Ciencia que los estudia.
Mapa_ representación plana de la superficie terrestre, que tiene en cuenta la forma de la
tierra, para lo que precisa usar dela Geodesia y de la Cartografía.

Plano_ representación plana de la superficie terrestre en la que se prescinde de la forma real
de la tierra

Sistema de Referencia de Coordenadas (SRC)
Básicamente la localización geográfica de un punto se puede
realizar detallando uno de estos parámetros:

\-Sistema de Coordenadas Geográficas en formato
Longitud-Latitud

\-Sistema de Coordenadas proyectadas (x,y) el más
utilizado es el UTM Universal Transversa Mercator.

19

<!-- p. 20 -->

CONCEPTOS CARTOGRÁFICOS

SISTEMA DE COORDENADAS GEOGRÁFICAS

Longitud (λ o L)_ es el arco de Ecuador contado desde el meridiano de Greenwich hasta el
meridiano del lugar. Puede ser Oeste (W) o Este (E)
Latitud (ω o l)_ es el arco de meridiano contado desde el ecuador hasta el punto a localizar.
Puede ser Norte (N) o Sur (S) y siempre es ≤ 90°

λ = 71°03’27’’ E
ω = 42°21’30’’ N

20

<!-- p. 21 -->

CONCEPTOS CARTOGRÁFICOS

SISTEMA DE COORDENADAS PROYECTADAS

Un sistema de coordenadas proyectadas es plano,
una representación en dos dimensiones de la
tierra. Usa un Sistema de Coordenadas
Cartesianas con unidades lineales de medida que Se
basa en un modelo esférico o esferoidal de la tierra y
que por lo tanto, requiere de una proyección
cartográfica para trasformar la superficie curva en
plana.

21

<!-- p. 22 -->

CONCEPTOS CARTOGRÁFICOS

UNIVERSAL TRANSVERSAL MERCATOR (UTM)

El sistema de proyección UTM emplea un cilindro de proyección de eje mayor
transversal al eje de la tierra, “tangente” al meridiano central de cada huso de proyección,
de ahí su universalidad.

No consiste en una única proyección para todo el globo, sino que se realizan múltiples
proyecciones, 60 en total, y se aprovecha de cada una de ellas solamente la superficie en
que la distorsión es nula o muy pequeña. Esta porción, que abarca 6 grados de longitud, se
denomina huso.

22

<!-- p. 23 -->

CONCEPTOS CARTOGRÁFICOS

UNIVERSAL TRANSVERSAL MERCATOR (UTM)

Una posición en la tierra es definida en el Sistema UTM por su Huso, y un par de
coordenadas (x,y) que indica la distancia en dirección este y norte desde el origen de cada
huso, situado en el encuentro del Ecuador con el meridiano situado más al oeste del huso.

Husos cuadricula UTM.

23

<!-- p. 24 -->

CONCEPTOS CARTOGRÁFICOS

ELIPSOIDE DE REFERENCIA

En geodesia, un elipsoide de referencia es una superficie matemáticamente definida que
se aproxima al geoide, que representa la Superficie teórica de la Tierra en la que todos sus
puntos tienen igual gravedad.

24

<!-- p. 25 -->

CONCEPTOS CARTOGRÁFICOS
DATUM

Los datums mas usados en las diferentes zonas geográficas son :
\- North America: NAD27, NAD83 y WGS84
\- Brazil: SAD 69/IBGE
\- Spain : ED50, since 2007: ETRS89 in all Europe

25

<!-- p. 26 -->

CONCEPTOS CARTOGRÁFICOS
CÓDIGO EPSG

26

<!-- p. 27 -->

GIS

SISTEMAS DE INFORMACIÓN GEOGRÁFICA

Es un sistema, formado por datos, tecnología, análisis, visualización y factor
organizativo, que nos permiten integrar y relacionar datos georreferenciados, facilitando
así la toma de decisiones de una manera más eficaz.

27

<!-- p. 28 -->

\3. INTRODUCCIÓN A QGIS

28

<!-- p. 29 -->

\4. GEORECTIFICACIÓN + RESTITUCIÓN (QGIS + CAD)

29

<!-- p. 30 -->

1880_Plano de Zaragoza

Fuente: Servicio de Documentación
Geográfica y Biblioteca Instituto Geográfico
nacional. Signatura: 31-G-9

30

<!-- p. 31 -->

1880_Plano topográfico de la Ciudad de Valencia del Cid

Fuente: Servicio de Documentación Geográfica y Biblioteca Instituto Geográfico nacional. Signatura: 31-F-10

31

<!-- p. 32 -->

1910_Plano de Valencia facilitado y
revisado por el Ayuntamiento

Fuente: Servicio de Documentación
Geográfica y Biblioteca Instituto Geográfico
nacional. Signatura: 92-89(V03-0100MAPA)

32
