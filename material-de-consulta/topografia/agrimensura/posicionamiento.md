---
type: libro
title: "posicionamiento"
author: "dblanco"
categoria: "TOPOGRAFÍA"
paginas: 2
extraccion: "texto"
fuente: "local:E:/MATERIAL DE CONSULTA/TOPOGRAFÍA/agrimensura/posicionamiento.pdf"
convertido: 2026-10-16
---

# posicionamiento

> Texto extraído de `TOPOGRAFÍA\agrimensura\posicionamiento.pdf` (2 páginas, texto). El PDF original está en el disco E: (MATERIAL DE CONSULTA); `<!-- p. N -->` marca el inicio de cada página.

<!-- p. 1 -->

FACULTAD DE INGENIERIA INSTITUTO DE AGRIMENSURA
DEPARTAMENTO DE GEODESIA

POSICIONAMIENTO PUNTUAL O ABSOLUTO

Este consiste en determinar la posición de un punto próximo a la superficie terrestre utilizando
un receptor y la medición de la seudodistancia usando el código que traen las ondas
portadoras de la señal GPS.
Como ya vimos para determinar la posición del receptor, basta con determinar las
seudodistancias a 4 satélites en el mismo instante t de tiempo.
El receptor mide la distancia satélite receptor a partir del tiempo de propagación de la señal
emitida desde el satélite. Los satélites y los receptores cuentan con relojes que controlan el
tiempo de emisión y recepción de la señal respectivamente. De esta manera:
t R − t S = ∆ t ⇒ c ∆t = dis tan cia

donde: tR = instante de recepción de la señal.
tS = instante de emisión de la señal.
∆t = tiempo de propagación de la señal.
c = velocidad de la luz.

Debido a que los relojes de los satélites y de los receptores no están sincronizados entre ellos,
ni con el tiempo patrón GPS, es que la distancia determinada satélite receptor se denomina
seudodistancia. Recordar que los errores en los relojes de los satélites se pueden corregir a
partir de los datos enviados en el mensaje para tal fin.
Si los relojes estuvieran sincronizados con el tiempo GPS:

t R (GPS ) − t S (GPS ) = ∆ t (GPS ) siendo t(GPS) tiempo en el sistema GPS

El tiempo de emisión lo controla el satélite ⇒ t S = t S (GPS ) + δ S
El tiempo de recepción lo controla el receptor ⇒ t R = t R (GPS ) + δ R

∆ t = t R − t S = (t R (GPS ) + δ R ) − (t S (GPS ) + δ S ) = t R (GPS ) − t S (GPS ) + δ R − δ S

⇒ ∆t = ∆t (GPS ) + ∆ δ . Multiplicando por c:

c∆ t = c ∆ t (GPS ) + c∆ δ ⇒ R = ρ + c ∆δ donde: R = seudodistancia medida.
ρ = distancia satélite receptor
∆δ = error de los relojes.

Introducimos la siguiente notación:

R i j (t ) = ρ ij (t ) + c δ i (t ) − cδ j ()t i indica el receptor.
j indica el satélite.
t indica el instante.
Recordar que: δ j (t ) = a 0 + a 1 (t − t oc ) + a 2 (t − t oc )2

j j 2 j 2 j 2 j j j
ρ X (t ) − X i ) + (Y (t ) − Yi ) + (Z (t ) − Z i ) donde: X (t ), Y (t ), Z ()t son las coordenadas i (t ) = (
del satélite j en el instante t y X i , Yi , Z i son las coordenadas del receptor i.
Las incógnitas en una sola época de observación serán X i , Yi , Z i y iδ ()t . Lo que implica la
necesidad de las mediciones a cuatro satélites como mínimo para su resolución, en cuyo caso
obtendremos:

<!-- p. 2 -->

FACULTAD DE INGENIERIA INSTITUTO DE AGRIMENSURA
DEPARTAMENTO DE GEODESIA

 2 2 2
 R1 (t ) = (X1 (t ) − XR ) + (Y 1(t ) − YR ) + (Z1 (t ) − Z R ) + c δR (t ) − c δ1(t )
 2 2 2
 R 2 (t ) = (X 2 (t ) − XR ) + (Y 2 (t ) − YR ) + (Z 2 (t ) − Z R ) + c δR (t ) − c δ 2 (t )

 3 3 2 3 2 3 2 3 R (t ) = (X (t ) − XR ) + (Y (t ) − YR ) + (Z (t ) − Z R ) + c δR (t ) − c δ (t ) 
 4 4 2 4 2 4 2 4 R (t ) = (X (t ) − XR ) + (Y (t ) − YR ) + (Z (t ) − Z R ) + c δR (t ) − c δ (t )

En caso de realizar la observación de n satélites en una época t, tendremos un sistema
indeterminado. La solución óptima la calculamos aplicando el método de ajuste por mínimos
cuadrados.

Observación:

Si llamamos: nJ = número de satélites.
nt = número de épocas de observación.
⇒ nJx nt = número de ecuaciones de observación.

R i j (t ) + c δ j (t ) = ρ ij (t ) + c δ i ()t
nJx n t ≥ 3 + nt condición para poder resolver las incógnitas.

Si nt = 1 ⇒ nJ ≥ 4 por lo menos es necesario 4 satélites.

Si nt = 2 ⇒ nJ ≥ 3 por lo menos es necesario 3 satélites.

Si nt = 3 ⇒ nJ ≥ 2 por lo menos es necesario 2 satélites.

En estos últimos casos, para que las ecuaciones de observación de cada satélite queden lo
suficientemente diferentes para la resolución del sistema, las épocas deben estar espaciadas
varias horas. Por lo que en la práctica no es aplicable.
