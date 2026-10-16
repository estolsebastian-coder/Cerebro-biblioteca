---
type: libro
title: "combinaciones"
author: "dblanco"
categoria: "TOPOGRAFÍA"
paginas: 3
extraccion: "texto"
fuente: "local:E:/MATERIAL DE CONSULTA/TOPOGRAFÍA/agrimensura/combinaciones.pdf"
convertido: 2026-10-16
---

# combinaciones

> Texto extraído de `TOPOGRAFÍA\agrimensura\combinaciones.pdf` (3 páginas, texto). El PDF original está en el disco E: (MATERIAL DE CONSULTA); `<!-- p. N -->` marca el inicio de cada página.

<!-- p. 1 -->

FACULTAD DE INGENIERIA INSTITUTO DE AGRIMENSURA
DEPARTAMENTO DE GEODESIA

COMBINACIONES LINEALES

Se puede combinar las distintas observaciones entre sí en una misma época para obtener
otras nuevas con características especialmente adecuadas para resolver problemas
específicos.
Una combinación arbitraria de las fases de las portadoras en L1 y L2 tiene la forma general:

k k k
Φ iΩ = α 1Φ 1i + α 2 Φ 2i

Donde Ω indica la combinación realizada, mientras que α1 y α2 son coeficientes
convenientemente elegidos para dar a la combinación resultante ciertas propiedades
deseadas.
Las características más buscadas en estas combinaciones son: ambigüedades enteras, valores
grandes de la longitud de onda, inmunidad al efecto ionosférico y bajo nivel de ruido. Esto hace
que de las infinitas posibilidades existentes, sólo unas pocas combinaciones de observaciones
de L1 y L2, o incluso con códigos, tengan utilidad práctica. Entre ellas, nos ocuparemos de las
combinaciones libre de ionosfera, widelane y narrowlane por su utilidad para resolver los dos
problemas centrales que se presentan en el posicionamiento con fases. La resolución de
ambigüedades como números enteros para períodos de observación tan cortos como sea
posible y la eliminación de los efectos de la ionosfera en vectores largos.

COMBINACIÓN LIBRE DE IONOSFERA

Las señales GPS sufren un retardo al atravesar la ionosfera que es directamente proporcional
al contenido de electrones del espacio atravesado por la señal y es inversamente proporcional
al cuadrado de la frecuencia de la onda portadora. El término del retardo ionosférico en las
señales GPS para una estación i que observa a un satélite k, puede escribirse como:

k kTEC ki k
Ι i = 2 donde k es una constante, TEC i es el contenido electrónico total encontrado por f
la señal en su paso por la ionosfera al ir desde el satélite k al receptor i, y f es la frecuencia de
la onda portadora.
Si se cuenta con receptores de doble frecuencia, se puede construir la combinación “libre de
ionosfera” (L0). Esta nueva observable elimina el problema del efecto ionosférico. Una forma de
obtener L0 es la siguiente:

k f12 k f 22 k
Φ 0i = 2 2 Φ 1i − 2 2 Φ 2i
f1 − f 2 f1 − f 2

Donde Φ k1i y Φ k2i son las observaciones de fase en L1 y L2 respectivamente de la estación i al
satélite k, siendo f1 y f2 las frecuencias de las portadoras.
Si desarrollamos esta expresión haciendo explícitos solamente los términos de la distancia,
ambigüedades, efecto ionosférico y errores de observación, nos queda:

c c
Φ 1 = ρ i − N1 − Ι 1 + + ε 1 Φ 2 = ρ i − N 2 − Ι 2 + + ε 2
f1 f 2

k  f12 kTEC ki f 22 kTEC ki   f1N1 − f 2 N 2   f12 f 22 
Φ 0i = ρ i +  2 2 2 − 2 2 2  − c 2 2  +  2 2 ε 1 − 2 2 ε 2 
 f1 − f 2 f1 f1 − f 2 f 2   f1 − f 2   f1 − f 2 f1 − f 2 

Vemos que se cancela el término del efecto ionosférico. Otra consecuencia de la combinación
realizada es que las ambigüedades resultantes no son ya enteras por lo que su resolución será

<!-- p. 2 -->

FACULTAD DE INGENIERIA INSTITUTO DE AGRIMENSURA
DEPARTAMENTO DE GEODESIA

siempre de tipo “flotante” y además el error resultante de la medición aumenta. Si
consideramos a los errores en las dos frecuencias L1 y L2 iguales y no correlacionados, se
concluye que el error de la observación combinada es aproximadamente tres veces mayor que
el de cada una de las componentes. Por esta razón el uso de la combinación libre de ionosfera
para posicionamiento se reserva para el trabajo con vectores de longitud mayor que 30 km;
suficiente como para que el efecto ionosférico diferencial no sea despreciable.

COMBINACIÓN DE BANDA ANCHA (“Wide lane”)

Las longitudes de ondas de las portadoras L1 y L2 son 19 cm y 24 cm respectivamente. Si se
dispone de ambas frecuencias se puede construir la llamada widelane (L∆) cuya longitud de
onda es 86 cm.
Se forma de la siguiente manera:

k f1 k f 2 k
Φ i∆ = Φ 1i − Φ 2i
f1 − f 2 f1 − f 2

k kTEC ki c f1ε 1 − f 2 ε 2 Φ i∆ = ρ i + − (N1 − N 2 ) +
f1f 2 f1 − f 2 f1 − f 2

donde:
c
λ ∆ = ≈ 86 cm
f1 − f 2

La ventaja de la observable de banda ancha en comparación con la observable original, es que
la ambigüedad tiene que ser solucionada para una señal con una longitud de onda cuatro
veces mayor; mientras que el ruido de observación referente es seis veces mayor.

COMBINACIÓN DE BANDA CORTA (“Narrow lane”)

La longitud de onda de ésta combinación (LΣ) es de 11 cm y se forma de la siguiente manera:

k f1 k f 2 k
Φ iΣ = Φ 1i + Φ 2i
f1 + f 2 f1 + f 2

k kTEC ki c f1ε 1 + f 2 ε 2 Φ iΣ = ρ i − − (N1 + N 2 ) +
f1f 2 f1 + f 2 f1 + f 2

donde:
c
λΣ = ≈ 11 cm
f1 + f 2

La banda corta tiene el nivel más bajo de ruido de todas las combinaciones lineales y por eso
proporciona los mejores resultados. De todas formas su ambigüedad es difícil de resolver. Se
usa principalmente para distancias cortas entre las estaciones.

COMBINACIÓN DE BANDA EXTRA ANCHA (“Extra wide lane”)

Esta logra duplicar la longitud de onda efectiva de L∆ llevándola a 1.72 m y se forma de la
siguiente manera:

<!-- p. 3 -->

FACULTAD DE INGENIERIA INSTITUTO DE AGRIMENSURA
DEPARTAMENTO DE GEODESIA

 k k  k 1 Φ 2i Φ 1i
− f 2  Φ iX∆ =  f1 f1 − f 2  λ 2 λ 1 

La ambigüedad de la misma es entera.

Además de las combinaciones antes apuntadas se utilizan también otras que involucran
observaciones de códigos y de fases. Estas combinaciones son usadas por las estrategias
rápidas de resolución de ambigüedades aprovechando la ausencia de estas en las
observaciones de código.

CARACTERÍSTICAS RELEVANTES DE LAS COMBINACIONES MAS USADAS

Longitud de Error de observación Efecto ionosférico
Observable Ambigüedad
onda (cm) relativo a L1 relativo a L1
L1 Entera 19 1 1
L2 Entera 24 1 1.6
L0 No entera 5.4 3 0
L∆ Entera 86 5.7 1.3
LΣ Entera 11 0.7 -1.3
LX∆ Entera 172 5.7 1.3
