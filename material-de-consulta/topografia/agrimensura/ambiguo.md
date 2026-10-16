---
type: libro
title: "ambiguo"
author: "dblanco"
categoria: "TOPOGRAFÍA"
paginas: 3
extraccion: "texto"
fuente: "local:E:/MATERIAL DE CONSULTA/TOPOGRAFÍA/agrimensura/ambiguo.pdf"
convertido: 2026-10-16
---

# ambiguo

> Texto extraído de `TOPOGRAFÍA\agrimensura\ambiguo.pdf` (3 páginas, texto). El PDF original está en el disco E: (MATERIAL DE CONSULTA); `<!-- p. N -->` marca el inicio de cada página.

<!-- p. 1 -->

FACULTAD DE INGENIERIA INSTITUTO DE AGRIMENSURA
DEPARTAMENTO DE GEODESIA

SOLUCION DE AMBIGUEDADES

Las mediciones de la fase de la portadora están influenciadas por el término de ambigüedad N,
siendo éste un múltiplo entero (número entero) de la longitud de onda entre el satélite y la
antena del receptor. Esta ambigüedad tiene que ser determinada con técnicas apropiadas para
aprovechar el potencial de alta precisión que encierran las mediciones de fase de las señales
GPS.
Los métodos principales son:

Método geométrico
Combinaciones de código y de portadora
Métodos de búsqueda de ambigüedades
Métodos combinados

METODO GEOMETRICO

Este hace uso de la variación dependiente del tiempo en la relación geométrica entre receptor y
satélites. Esta técnica funciona si el cambio de geometría es suficientemente grande, es decir
con un tiempo de observación bastante largo.
Las ambigüedades estimadas son números reales (solución flotante de ambigüedades). Se las
puede fijar como números enteros (solución fija de ambigüedades) en caso de que los valores
estimados se hallen muy cerca de un número entero. Esta exigencia da como resultado un
tiempo de observación muy largo en el método geométrico puro. Es posible disminuir el tiempo
de observación por medio de satélites adicionales, o bien haciendo uso de señales con una
longitud de onda más larga (por ejemplo “Widelane” L∆).

COMBINACIONES DE CODIGO Y DE PORTADORA

En estos se hace uso de las observaciones de código, las cuales no tienen ambigüedades.
Diferenciando las observaciones realizadas a un satélite de la portadora y de código para una
estación i, obtenemos:

R i − Φ i = λ N i + ∆Ι i + ∆Ti + ∆ ε i

La idea básica es hacer mediciones de código hasta que el nivel de ruido de la solución de
código sea menor que la mitad de la longitud de la onda portadora, esto requiere un receptor
con un nivel bajo de ruido para mediciones de código.
Sin embargo es difícil resolver las ambigüedades de las señales L1 y L2 debido a lo corta que
se su longitud de onda. En vez de ello se usa la banda ancha L∆.
Nótese que el método es completamente independiente de la geometría de observación y de
los relojes de los satélites y receptores. Se puede encontrar soluciones de las ambigüedades
después de un corto lapso de observación de unos minutos o menos todavía.

METODO DE BUSQUEDA DE AMBIGÜEDADES

Se han desarrollado métodos de rastreo de ambigüedades con el objetivo de reducir el tiempo
necesario de observación de una estación individual. A mayor número de satélites disponibles,
tanto mejor funciona este método.
Cuando se plantea el problema de resolver las ambigüedades como números enteros se parte
de la mejor aproximación disponible de las coordenadas del punto de interés. Por ejemplo se
puede obtener usando una medición diferencial con código.
A partir del error estimado para esa primera aproximación, se puede definir una esfera
alrededor de la solución a priori con un tamaño suficiente para asegurar que la solución
verdadera se encuentra dentro de ella.

<!-- p. 2 -->

FACULTAD DE INGENIERIA INSTITUTO DE AGRIMENSURA
DEPARTAMENTO DE GEODESIA

Existe en principio un conjunto de infinitas soluciones posibles para las coordenadas de la
estación que caerán dentro de la esfera. Sin embargo, si consideramos que las ambigüedades
de todos los satélites son números enteros sabemos que dentro de la esfera existe un número
finito de combinaciones de ambigüedades enteras para todos los satélites.

Este número de posibilidades dependerá de la calidad de nuestras coordenadas a priori
(tamaño de la esfera), la cantidad de satélites observados y la longitud de onda de la
observación de fase o combinación de ellas que estemos usando. Una vez identificado el
conjunto de soluciones “candidatas” se debe seleccionar la correcta.

Su éxito depende en primer lugar, de que se pueda reducir convenientemente el conjunto de
soluciones posibles o “candidatas” ya mencionado. Esto se debe a que en general se deben
ensayar tantas soluciones como candidatas haya.
Una vez reducido convenientemente el número de soluciones candidatas, resta discernir de
entre ellas cuál es la correcta. En este proceso el éxito depende en gran medida de que la
combinación del ruido de observación y el efecto del multicamino sea pequeña respecto de la
longitud de onda asociada a la combinación utilizada.

METODOS COMBINADOS

En zonas de trabajo pequeñas existen técnicas que incorporan información adicional a la fase
de L1. Las más robustas son las que incorporan las observaciones de la fase de L2 y del
código P. Con una buena solución de código P, que no tiene ambigüedad y posee además bajo
ruido, se puede limitar drásticamente el número de soluciones posibles de ambigüedades
enteras de las combinaciones L∆ y/o LX∆ con solamente unas pocas épocas de observación,
necesarias para obtener una solución de códigos con la precisión necesaria. Una vez resueltas
las ambigüedades de L∆ se puede resolver las de LΣ para finalmente obtener las ambigüedades
de L1 y calcular una solución final con este observable que aportará, por sus bajos ruido y
efecto ionosférico, la solución más precisa y exacta.

En zonas de trabajo extensas las alternativas para resolver las ambigüedades son más
limitadas. La presencia del efecto ionosférico hace difícil cuando no imposible la resolución de
las ambigüedades de L∆ en vectores de longitudes mayores que unas pocas decenas de km.

<!-- p. 3 -->

FACULTAD DE INGENIERIA INSTITUTO DE AGRIMENSURA
DEPARTAMENTO DE GEODESIA

La solución a partir de L0 es confiable si se ha medido el tiempo suficiente como para resolver
las ambigüedades flotantes. Una estrategia utilizada por muchos programas es la siguiente:

Se obtiene primero una solución con L0 (ambigüedades flotantes). Luego se calcula una
solución con L∆ estimando solamente las ambigüedades y dejando las coordenadas
provenientes del cálculo anterior (L0) fijas. Este paso es muy delicado ya que L∆ sufre 1.3 el
efecto de la ionosfera respecto al que sufre L1. Esto, combinado con el alto ruido que presenta
L∆ hace que para las distancias consideradas aquí pueda producirse una solución errónea.
Si se ha logrado resolver las ambigüedades L∆, se reescribe entonces el término de la
ambigüedad en la ecuación de la combinación libre de ionosfera L0 de la siguiente manera:

k  f 2 N ∆ c   f12 f 22 
Φ 0i = ρ i − c 2 2 + N1  + ∆T +  2 2 ε 1 − 2 2 ε 2   f1 − f 2 f1 + f 2   f1 − f 2 f1 − f 2 

Donde vemos que la ambigüedad desconocida restante N1 es entera. Su longitud de onda es
c
que como ya vimos es la asociada a la combinación narrowlane (LΣ) y vale 11 cm.
f1 + f 2
El paso siguiente con esta estrategia es entonces resolver las ambigüedades Narrowlane como
números enteros en la combinación L0 junto con las componentes del vector medido. Ahora el
efecto ionosférico no nos perturba, pero si otros como el efecto troposférico residual, cuyo
efecto relativo deja de ser despreciable en simples diferencias, el efecto del multicamino, y el
ruido de la observación L0, que es tres veces el de L1. Como vimos, la perturbación ionosférica
hace que esta estrategia implique siempre cierto riesgo. Esto hace que resulte conveniente,
antes de adoptarla como final, compararla con una solución de ambigüedades flotantes y
controlar que las diferencias estén bien por debajo del tamaño del ciclo de la portadora.

La resolución de ambigüedades enteras se facilita si se mide durante mucho tiempo ya que
esto permite producir mejor estimaciones a priori de las mismas y por ende menor cantidad de
candidatos posibles para la solución. Sin embargo, cuando se miden vectores durante más de
4 horas, la diferencia entre fijar o no las ambigüedades se hace despreciable. Por esto, en
casos en que se buscan muy altas precisiones en vectores largos, suele ser más económico y
seguro medir durante varias horas y calcular luego el vector mediante una solución libre de
ionosfera con ambigüedades flotantes.

PERDIDA DE SEÑAL (Cycle Slips)

Se produce una pérdida de señal cuando el receptor pierde la relación de fase de la señal
satelital. Las razones pueden ser, entre otras: obstrucciones, ruido de la señal, baja elevación
del satélite.
La fase portadora muestra un salto súbito de un número entero de ciclos; la parte fraccionaria
de la observación de fase no sufre ningún cambio. La pérdida de señal puede ser pequeña, de
uno o varios ciclos, o de millones de ciclos. La pérdida de señal cycle slips tiene que ser
extraída de los datos a nivel de procesamiento previo o bien una ambigüedad nueva tiene que
ser determinada para la seudodistancia particular.
La mayoría de los receptores tienen algoritmos instalados que identifican todos o la mayoría de
los cycle slips y los marcan en el conjunto de datos.
Los cycle slips no pueden ser identificados y corregidos solamente de una serie simple de
mediciones de fase. Una pérdida de señal puede ser detectada fácilmente si se forman
diferencias dobles y triples.
