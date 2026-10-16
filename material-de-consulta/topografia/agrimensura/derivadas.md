---
type: libro
title: "derivadas"
author: "dblanco"
categoria: "TOPOGRAFÍA"
paginas: 3
extraccion: "texto"
fuente: "local:E:/MATERIAL DE CONSULTA/TOPOGRAFÍA/agrimensura/derivadas.pdf"
convertido: 2026-10-16
---

# derivadas

> Texto extraído de `TOPOGRAFÍA\agrimensura\derivadas.pdf` (3 páginas, texto). El PDF original está en el disco E: (MATERIAL DE CONSULTA); `<!-- p. N -->` marca el inicio de cada página.

<!-- p. 1 -->

FACULTAD DE INGENIERIA INSTITUTO DE AGRIMENSURA
DEPARTAMENTO DE GEODESIA

OBSERVABLES DERIVADAS

Las observaciones de las fases portadoras y las de código de las dos frecuencias proporcionan
las seudodistancias. Algunas combinaciones entre éstas son usadas pues los errores
existentes en las observaciones originales son eliminadas o reducidas.

Se detallan a continuación las distintas combinaciones:

Entre observaciones de diferentes estaciones.
Entre observaciones de satélites distintos.
Entre observaciones de diferentes épocas.
Entre observaciones del mismo tipo.
Entre observaciones de distinto tipo.

Son usuales las combinaciones entre estaciones y los satélites.
Consideremos:

En esta figura tenemos:
2 receptores i, j.
2 satélites p, q.
época t1: posición 1 de los satélites p, q.
época t2: posición 2 de los satélites p, q.
8 mediciones de seudodistancias.

Se pueden formar diferencias simples entre dos receptores, entre dos satélites o entre dos
épocas. Introduzcamos la siguiente notación:

Diferencias simples entre receptores ∆(•) = (•) receptor j - (•) receptor i

Diferencias simples entre satélites ∇ (•) = (•) satélite q - (•) satélite p

Diferencias simples entre épocas δ (•) = (•) época 2 - (•) época 1

Recordemos que al trabajar con diferencias simples en vectores cortos los errores
atmosféricos, los orbitales y los producidos por los relojes (en algunos casos) disminuyen
considerablemente.
Las diferencias simples entre dos receptores fueron presentadas junto a sus propiedades en el
método diferencial.

<!-- p. 2 -->

FACULTAD DE INGENIERIA INSTITUTO DE AGRIMENSURA
DEPARTAMENTO DE GEODESIA

Las diferencias simples entre satélites se forman diferenciando observaciones simultáneas a
dos satélites en una misma estación simple.
Trabajando con códigos:

∆R pq = ∆ ρ pq + c∆ δ pq + ∆Ι pq + ∆ T pq

Donde: ∆R pq diferencia de seudodistancias de código.
∆ ρ pq diferencia de distancias receptor – satélites.
∆δ pq diferencia de errores debido a los relojes de los satélites.
∆Ι pq diferencia de errores debido a la ionosfera.
∆T pq diferencia de errores debido a la troposfera.

Trabajando con fase:

∆Φ pq = ∆ρ pq + c∆δ pq + λ ∆N pq − ∆Ι pq + ∆T pq

Donde: ∆Φ pq diferencia de seudodistancias de fase.
∆ρ pq diferencia de distancias receptor – satélites.
∆δ pq diferencia de errores debido a los relojes de los satélites
∆N pq diferencia de ambigüedades.
∆Ι pq diferencia de errores debido a la ionosfera.
∆T pq diferencia de errores debido a la troposfera.

El término correspondiente al reloj del receptor se cancela.

Las diferencias simples entre dos épocas de un mismo satélite observado desde una estación
simple corresponden a la solución Doppler.

∆Φ p = ∆ρ p − ∆Ι p + ∆T p

Donde: ∆Φ p diferencia de seudodistancias de fase.
∆ρ p diferencia de distancias receptor – satélite.
∆Ι p diferencia de errores debido a la ionosfera.
∆T p diferencia de errores debido a la troposfera.

Los términos correspondientes a los errores de los relojes se cancelan.
El término correspondiente a la diferencia de ambigüedades desaparece debido a que la
ambigüedad de la fase inicial no varía con el tiempo (siempre y cuando no haya una pérdida de
señal, llamada cycle slips).

DIFERENCIAS DOBLES

Se forman usualmente entre receptores y satélites. Se las construye diferenciando diferencias
simples entre receptores a dos satélites p y q (en la misma época t).

Diferencia simple entre receptores con el satélite p:

<!-- p. 3 -->

FACULTAD DE INGENIERIA INSTITUTO DE AGRIMENSURA
DEPARTAMENTO DE GEODESIA

∆Φ pij = ∆ ρ pij + c ∆ δ pij + λ ∆N pij − ∆Ι pij + ∆Tijp + ∆ ε pij
Diferencia simple entre receptores con el satélite q:

∆Φ ijq = ∆ρ ijq + c∆ δ ijq + λ ∆N ijq − ∆Ι ijq + ∆Tijq + ∆ε ijq
La ecuación de observación de diferencias dobles para las fases de las portadoras queda:

∆Φ pij − ∆Φ ijq = ∆ ρ pij − ∆ρ ijq + λ (∆N pij − ∆N ijq ) − ∆Ι pij + ∆Ι ijq + ∆ Tijp − ∆Tijq + ∆ ε pij − ∆ ε ijq
En una notación simplificada:

∇ ∆Φ = ∇ ∆ρ + λ ∇ ∆N − ∇ ∆Ι + ∇ ∆T + ∇ ∆ ε

La ecuación equivalente para mediciones con código es:

∇ ∆R = ∇ ∆ρ + ∇ ∆Ι + ∇ ∆T + ∇ ∆ ε

Nótese que desaparece el término del reloj del receptor. Las observaciones de diferencia doble
no tiene ni errores de los relojes de los satélites ni de los receptores y solamente incluyen
reducidos errores de propagación y órbita. La observable de diferencias dobles es la
observación básica en muchos modelos de ajustamiento para observaciones GPS.

Las diferencias dobles entre receptores y tiempo se las construye diferenciando diferencias
simples entre receptores, al mismo satélite p, en dos épocas diferentes t1 y t2. Estas
observables están libres del término de ambigüedad N, y se usan frecuentemente para la
edición de “cycle slips”.

DIFERENCIAS TRIPLES

Se las construye entre receptores, satélites y tiempo. Se las forma diferenciando diferencias
dobles entre receptores y satélites en dos épocas t1 y t2 diferentes.

Diferencias dobles para las fases de las portadoras en la época t1:

∇ ∆Φ 1 = ∇ ∆ ρ 1 + λ ∇ ∆N1 − ∇ ∆Ι 1 + ∇ ∆T1 + ∇ ∆ε 1

Diferencias dobles para las fases de las portadoras en la época t2:

∇ ∆Φ 2 = ∇ ∆ ρ 2 + λ ∇ ∆ N 2 − ∇ ∆Ι 2 + ∇ ∆T2 + ∇ ∆ ε 2

Diferencias triples para la fase:

δ∇ ∆Φ = δ∇ ∆ρ − δ∇ ∆Ι + δ∇ ∆ T + δ∇ ∆ ε

La ambigüedad N del ciclo inicial desaparece de la ecuación. Se utilizan frecuentemente las
diferencias triples para obtener soluciones aproximadas. Son también de mucha utilidad
apoyando la extracción de cycle slips en un proceso de edición automática.
