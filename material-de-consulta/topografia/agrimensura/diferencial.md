---
type: libro
title: "diferencial"
author: "dblanco"
categoria: "TOPOGRAFÍA"
paginas: 3
extraccion: "texto"
fuente: "local:E:/MATERIAL DE CONSULTA/TOPOGRAFÍA/agrimensura/diferencial.pdf"
convertido: 2026-10-16
---

# diferencial

> Texto extraído de `TOPOGRAFÍA\agrimensura\diferencial.pdf` (3 páginas, texto). El PDF original está en el disco E: (MATERIAL DE CONSULTA); `<!-- p. N -->` marca el inicio de cada página.

<!-- p. 1 -->

FACULTAD DE INGENIERIA INSTITUTO DE AGRIMENSURA
DEPARTAMENTO DE GEODESIA

METODO DIFERENCIAL

Es claro, a partir del análisis del posicionamiento puntual, que para mejorar la calidad de los
resultados no se pueden considerar en los cálculos simplemente los términos que involucran a
la distancia entre satélite y receptor y al reloj local e ignorar todo lo demás. Los términos
restantes deben ser tratados adecuadamente.
Existen básicamente dos alternativas para hacer esto. Una de ellas es modelar de alguna
manera todos los fenómenos que afectan al posicionamiento.
La otra metodología posible y la más utilizada es el método diferencial. Este consiste en el
procesamiento de ya no las observaciones de un solo receptor, sino de diferencias de
observaciones simultáneas, realizadas por al menos dos estaciones a los mismos satélites. Se
calculan las coordenadas de puntos respecto de al menos una estación de referencia que debe
tener coordenadas conocidas a priori. La situación deseable es que el cálculo diferencial no se
encuentre afectado por errores sistemáticos apreciables. En este caso, la exactitud de las
coordenadas calculadas estará dada por la de las coordenadas a priori de la estación de
referencia. La precisión de las mismas en cambio estará determinada por el método diferencial
en sí y por las condiciones en las que se lo utiliza.

Esta técnica aprovecha los siguientes hechos:

Los errores orbitales de un satélite tienen efectos muy parecidos para dos receptores que lo
observan simultáneamente separados por una distancia pequeña respecto de la media
entre receptor y satélite, que es del orden de 20000 km.
Los errores del reloj de un satélite tienen el mismo efecto sobre receptores que lo observen
en forma simultánea.
Los efectos producidos por la ionosfera son casi idénticos para dos estaciones separadas
menos que 30 km y se hacen cada vez más diferentes a medida que la distancia entre ellas
aumente.
Los efectos de la troposfera para dos estaciones que observan simultáneamente códigos
pueden considerarse siempre como prácticamente iguales.

En cambio, los efectos del multicamino y el ruido de observación no están correlacionados para
mediciones simultáneas por lo que no serán disminuidos al utilizar el método diferencial.

A medida que el vector entre las estaciones se hace más corto, las señales son afectadas por
prácticamente los mismos errores. Esto es aprovechado por esta estrategia para obtener las
componentes del vector con precisión de algunos metros utilizando códigos y de pocos
milímetros usando fases.

<!-- p. 2 -->

FACULTAD DE INGENIERIA INSTITUTO DE AGRIMENSURA
DEPARTAMENTO DE GEODESIA

SIMPLES DIFERENCIAS DE CODIGO

Consideremos dos estaciones i y j, las cuales realizan observaciones de código en forma
simultánea al mismo satélite.
Las ecuaciones de observación correspondiente serán:

R i = ρ i + c δ i − c δ + Ι i + Ti + d mi + ε i
R j = ρ j + cδ j − cδ + Ι j + T j + d mj + ε j

Haciendo la diferencia R j − R i :

∆ R ij = ρ j − ρ i + c (δ j − δ i ) + Ι j − Ι i + T j − Ti + d mj − d mi + ε j − ε i
En notación simplificada:

∆ R ij = ∆ρ ij + c∆ δ ij + ∆Ι ij + ∆Tij + ∆d mij + ∆ ε ij

Donde: ∆R ij diferencia de seudodistancias de código.
∆ρ ij diferencia de distancias satélite – receptores.
∆δ ij diferencia de errores de los relojes de los receptores.
∆Ι ij diferencia de errores debido a la ionosfera.
∆Tij diferencia de errores debido a la troposfera.
∆d mij diferencia de errores debido a los multicaminos.
∆ ε ij diferencia de errores de medición de los receptores.

Resulta evidente que desaparece el error del reloj satelital δ.

Los términos que limitan la precisión de este método son el error de observación de código y el
efecto del multicamino, por lo cual en vectores cortos (menores a 30 km) los demás errores
( ∆Ι ij , ∆Tij ) se pueden considerar que se cancelan. El error de observación depende de la
calidad del receptor y el multicamino es dependiente del sitio de observación y del tipo de
antena. Debido a estos dos efectos se considera que las observaciones de código tienen
errores de unos pocos metros.

Para poder realizar un posicionamiento diferencial con códigos se necesitan dos receptores
midiendo código en forma simultánea a los mismos satélites. Estos deben ser como mínimo 4
si queremos resolver el problema en una época de observación.

SIMPLES DIFERENCIAS DE FASE

La observación de fase con GPS es muy precisa. Su inconveniente principal es que es
ambigua. La resolución de ambigüedades es el principal problema que condiciona la
productividad de los levantamientos GPS con fases.
Los errores de las mediciones de fase de los receptores son solamente de unos pocos
milímetros, por lo cual el éxito de las técnicas de medición con fase es mucho más dependiente
de la distancia entre estaciones que en el caso de los códigos.

Consideremos dos estaciones i y j, las cuales realizan observaciones de fase en forma
simultánea al mismo satélite.
Las ecuaciones de observación correspondiente serán:

<!-- p. 3 -->

FACULTAD DE INGENIERIA INSTITUTO DE AGRIMENSURA
DEPARTAMENTO DE GEODESIA

λ (ϕ + N) = ρ + c ∆δ + v ⇒ λϕ = ρ + c ∆δ − λ N + v ⇒ Φ = ρ + c ∆δ − λ N + v

Φ i = ρ i + c δ i − c δ − λ N i − Ι i + Ti + d mi + ε i
Φ j = ρ j + cδ j − cδ − λ N j − Ι j + T j + d mj + ε j

Haciendo la diferencia R j − R i :

∆Φ ij = ρ j − ρ i + c (δ j − δ i ) + λ (N i − N j ) − Ι j + Ι i + T j − Ti + d mj − d mi + ε j − ε i
En notación simplificada:

∆Φ ij = ∆ ρ ij + c∆ δ ij + λ ∆N ij − ∆Ι ij + ∆Tij + ∆ d mij + ∆ ε ij

Donde: ∆Φ ij diferencia de seudodistancias de fase.
∆ρ ij diferencia de distancias satélite – receptores.
∆δ ij diferencia de errores de los relojes de los receptores.
∆ N ij diferencia de ambigüedades.
∆Ι ij diferencia de errores debido a la ionosfera.
∆Tij diferencia de errores debido a la troposfera.
∆d mij diferencia de errores debido a los multicaminos.
∆ ε ij diferencia de errores de medición de los receptores.

Resulta evidente que desaparece el error del reloj satelital δ.
Cuando la longitud de los vectores aumenta a pocos kilómetros, los efectos de la ionosfera y la
troposfera dejan de cancelarse en las simples diferencias y sus efectos relativos superan
rápidamente el ruido de la observación. El efecto de la ionosfera es el más problemático por su
gran tamaño. Se sabe que ya es notable para vectores de más de 10 km y que no es prudente
ignorarlo para vectores de más de 30 km. El hecho de poder o no despreciar la influencia
ionosférica diferencial será el criterio para definir que un vector sea corto o largo. El límite que
se adopta para separar las dos categorías será la distancia de 30 km.
El efecto de la troposfera es más pequeño pero mucho más local. Es notable para vectores de
pocos kilómetros de longitud. Sin embargo, los modelos simples que poseen los programas de
procesamiento GPS comerciales permiten mantener sus consecuencias por debajo de las
tolerancias para la mayoría de las aplicaciones en el caso de vectores cortos.

En el caso de las simples diferencias de fase la resolución de las ecuaciones no es tan sencilla
como en el caso de los códigos. Se deben resolver las tres incógnitas de posición relativa, la
combinación de los errores de reloj de los receptores, y además una ambigüedad por cada
satélite. Si observamos 4 satélites, el total de incógnitas supera en 4 al número de ecuaciones,
por lo que el problema no puede resolverse con esta información ni tampoco aumentando el
número de satélites observados.
La solución inmediata sería usar información de la época siguiente, ya que si el receptor
mantiene el rastreo de los satélites, las incógnitas de ambigüedad son las mismas y tendríamos
entonces 6 ecuaciones y 6 incógnitas. Sin embargo el problema no puede resolverse de esa
manera. La razón es la lentitud con que varía la configuración geométrica de satélites y
receptores. Para que la configuración varíe lo suficiente como para resolver el problema
planteado, se necesitará incorporar observaciones separadas por un intervalo mayor que
media hora, trabajando con vectores cortos.
