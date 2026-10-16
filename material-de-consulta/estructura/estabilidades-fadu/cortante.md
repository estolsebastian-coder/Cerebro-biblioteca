---
type: libro
title: "cortante"
author: "atilio"
categoria: "ESTRUCTURA"
paginas: 9
extraccion: "texto"
fuente: "local:E:/MATERIAL DE CONSULTA/ESTRUCTURA/ESTABILIDADES FADU/cortante.pdf"
convertido: 2026-10-16
---

# cortante

> Texto extraído de `ESTRUCTURA\ESTABILIDADES FADU\cortante.pdf` (9 páginas, texto). El PDF original está en el disco E: (MATERIAL DE CONSULTA); `<!-- p. N -->` marca el inicio de cada página.

<!-- p. 1 -->

TENSIONES PRODUCIDAS POR CORTANTE Y TORSIÓN EN VIGAS DE
PARED DELGADA

Hasta ahora se ha analizado los efectos de la torsión asumiendo que no existía
cortante. De la misma manera cuando se estudió el efecto del cortante, se
admitió que no existía torsión.
Para que solo se produzcan tensiones por cortante sin que aparezcan
tensiones por torsión no se pueden aplicar cargas arbitrariamente. Para lograr
estas condiciones el cortante debe pasar por un punto específico que
llamaremos centro de cortante.

Inicialmente analizaremos una sección abierta (con un solo contorno exterior)
como la que se indica en la figura 12.
Para hallar el centro de cortante analizaremos las tensiones que se producen
en la sección asumiendo que no se produce un giro en la sección (ausencia de
torsión). Si el cortante actúa solamente en la dirección principal y (Vx = 0) y si
asumimos que no hay giro de la sección, las tensiones pueden ser calculadas
con la expresión de Jouravski o sea:
V yµx ( s )
τ( s ) = −
I x t ( s )
Donde s es una variable que permite ubicar el punto en el cual se esta
calculando la tensión, Vy es el cortante en la dirección y, Ix es el momento de
inercia en relación al eje x, t(s) es el espesor de la pared que puede depender
de la coordenada s y µx(s) es el momento de primer orden de la sección
comprendida entre el inicio de la sección (s = 0) y la sección que estamos
analizando en relación al eje x, o sea:
S
yt ( s ) ds µx ( s ) = ∫0

µ( s ) = ∫s0 yt (s )ds
Es claro que las tensiones rasantes que se producen en el borde de la sección
deben ser paralelas al mismo por las mismas consideraciones que se hicieron
en la torsión.
La formula de Jouravski supone que las tensiones son constantes en la zona
en la que se realiza el corte.
En definitiva en el caso que estamos estudiando de paredes delgadas es
razonable suponer que las tensiones rasantes producidas por un cortante puro
(sin torsión) en cualquier punto de una sección normal al borde son constantes
y paralelas al borde de la sección. El flujo de corte q en toda la sección
(definido considerándolo positivo cuando gira en sentido antihorario) queda
definido por:
V y µx ( s )
q ( s ) = τ( s )t ( s ) = −
I x
Análogamente si el cortante tiene la dirección según x (Vy = 0) el flujo de corte
queda definido por:
Vx µy ( s )
q ( s ) = τ( s )t ( s ) = −
I y
En el caso que exista cortante en ambas direcciones el flujo de corte puede
obtenerse por superposición.

<!-- p. 2 -->

La resultante del flujo de corte, integrando en s para recorrer toda la sección,
será igual al cortante. Además el momento de la resultante de integrar el flujo
de corte, en relación a cualquier punto genérico A, será también igual al que
produce el cortante.

El proceso mediante el cual se localiza el centro de cortante para una sección
abierta se ilustrará a continuación, considerando la sección de pared delgada
abierta de la figura 12.

Figura 12: Geometría de una sección abierta de pared delgada genérica.

Se asume el origen de coordenadas O en el baricentro de la sección y que los
ejes x e y se encuentran ubicados en las direcciones principales de la sección.
V x y V y actúan en el centro de cortante E, que se supondrá que tiene
coordenadas en el sistema de ejes elegido ex y ey .
La fuerza desarrollada por el flujo de cortante en cualquier elemento ∆s de la
pared es q∆s y A es un punto arbitrario perteneciente al plano de la sección
transversal. A partir de la definición de centro de cortante, anulando los
momentos en A se obtiene:
St
q ( s ) r ( s ) ds Vx ( e y − a y ) − V y ( e x − a x ) = ∫0
donde ax y ay son las coordenadas de A, St es el largo total de la pared y r es la
distancia perpendicular desde A hasta la línea de acción de qds (que a su vez
es tangente a la pared de la sección).
El flujo cortante q es el producto de t (el espesor de la pared) y la tensión
rasante τ que viene dada por la ecuación de Jouravski, o sea:

V y µx ( s ) Vx µy ( s )
τ( s ) = − −
I x t ( s ) I y t ( s )
Y en consecuencia el flujo de corte será:
V y µx ( s ) Vx µy ( s )
q ( s ) = τ( s )t ( s ) = − −
I x I y

<!-- p. 3 -->

Sustituyendo q en la ecuación de equilibrio del momento en A queda:

St Vx St V y
µx ( s ) r ( s ) ds Vx ( e y − a y ) − V y ( e x − a x ) = − ∫0 µy ( s ) r ( s ) ds − ∫0 I y I x
Como hemos establecido que cualquiera que sea la fuerza que pasa por el
centro de corte no existe torsión la igualdad anterior debe cumplirse para todo
Vx y Vy y en consecuencia deberá ser:

1 St
µy ( s ) r ( s ) ds e y − a y = − ∫0 I y
1 St
µx ( s ) r ( s ) ds e x − a x = ∫0 I x
O teniendo en consideración que r(s) ds = 2dω donde dω es el diferencial del
área barrida se obtiene que:
2 St
µy ( s ) dω e y − a y = − ∫0 I y
2 St
µx ( s ) d ω e x − a x = ∫0 I x

En varios casos se puede hallar el centro de cortante de una sección
simplemente a partir de la estática.
Veamos el caso de la figura 13. Podemos elegir el punto A en el centro de la
pared vertical de la sección. Elegiremos un cortante solamente según y pues
en la otra dirección es claro que no se produce torsión cuando el cortante se
encuentra aplicado en el eje de simetría de la sección. O sea que el centro de
cortante se encuentra sobre el eje de simetría.
Debido a la simetría de la sección, se concluye que en ambas alas las fuerzas
son iguales y de sentido contrario, las llamaremos V1. Llamaremos V2 a la
resultante de las tensiones en el alma. Planteando las condiciones de equilibrio
de las tensiones rasantes y los cortantes obtenemos que:
Vy = −V2 eVy = − hV1
pero como se cumple también que:
h ts
µ ( s ) =
2
será:
V y 2 b V y ht b V y hb t
sds = − ( s ) ds = − V1 = − ∫µ0 ∫0 I x 2 I x 4 I x
y en consecuencia:
th 2 b 2
e =
4 I x

<!-- p. 4 -->

Figura 13: Una sección canal cargada de forma tal que la torsión sea nula. El
cortante resultante V pasa por el centro de cortante de la sección.

Cálculos similares con un gran número de secciones de uso común llevan a
ciertas observaciones útiles:

\1. El centro de cortante de secciones con 2 alas rectangulares que se
intersectan, es el punto de intersección de los ejes de dichas alas.
\2. El centro de cortante de una sección con un eje de simetría está en este
eje.
\3. El centro de cortante de una sección con dos ejes de simetría coincide
con el baricentro de la sección, que se encuentra en la intersección de los
dos ejes. Se pueden ver ejemplos de estos casos en la figura 14.

<!-- p. 5 -->

Figura 14: Ubicación del centro de cortante para algunas secciones usuales.
Los puntos E y O indican el centro de cortante y el baricentro respectivamente.

Otra conclusión muy interesante es que el centro de corte coincide con el
centro de torsión.
Ello se puede ver fácilmente observando que un momento torsor no produce
desplazamiento del centro de torsión en ninguna de las dos direcciones.
Aplicando el teorema de reciprocidad de Betti, se concluye que una fuerza
cualquiera aplicada en el centro de torsión no produce giro de la sección. Pero
al verificarse esta propiedad el centro de torsión cumple con la definición que
habíamos hecho del centro de cortante y en consecuencia ambos son el mismo
punto o sea coinciden.

Cortante en tubos rectos de pared delgada

La evaluación de las tensiones normales desarrolladas en secciones cerradas
de una sola celda de pared delgada no presenta dificultades espaciales.
Asumiendo que las secciones planas permanecen planas, la distribución de
tensiones para un cortante determinado (asociado a la variación del momento
aplicado sobre la sección) puede ser analizada de manera similar a las
secciones abiertas.
Sin embargo en la evaluación de tensiones rasantes no es posible aplicar
Jouravski directamente ya que los momentos de primer orden solo tienen
significado para secciones abiertas.

FIGURA 15 Flujo de corte en secciones unicelulares

<!-- p. 6 -->

Consideraremos la sección cerrada de pared delgada de forma genérica de la
figura 15. La resultante de los esfuerzos de corte Vx y Vy actúan en E, el centro
de cortante, por lo que el momento torsor es nulo. El punto O es el baricentro
de la sección y m es un punto arbitrario de la periferia del tubo que sirve de
origen para la coordenada s. Si se aisla una parte de la sección, tal como se
indica en la figura se observa que la resultante de fuerzas en la dirección
∂Flongitudinal ( )∆z es equilibrada por las tensiones rasantes en m y en el ∂z
otro punto genérico elegido que llamaremos s. Si se considera que el flujo de
qcorte en s es la suma del flujo de corte en m que llamaremos y el incremento
0q entonces:
q = q + q0

y
∂F s ∂σz tds q0 = − = − ∫m ∂z ∂z
donde 0q es el flujo de corte que se desarrollaría si la sección fuera abierta en
qm, es decir si fuera cero. Como consecuencia 0q se obtiene a partir de la
ecuación de Jouravski (el signo negativo aparece debido a que se consideró el
flujo cortante total positivo si actúa en sentido antihorario, en la dirección de s).
Para su obtención nos podemos imaginar a al sección como si fuese abierta en
la sección m.
qSe puede obtener la magnitud de , teniendo en cuenta la propiedad II o sea:
→ →
II = τ. t ds = 2GθA ∫
e igualando a cero el giro total de la sección obteniendo que:
→ →
II = τ. t ds = 0 ∫
Teniendo en cuenta que la tensión rasante y la tangente son colineales y que:
_
q ( s ) q q0 τ( s ) = = +
t ( s ) t ( s ) t ( s )
qdonde t(s) es el espesor de la pared. Teniendo en cuenta también que no
depende de s resulta:
 _ 
 q q0 ( s )  _ ds qO ( s ) 0 = + ds = q + ds ∫ ∫ ∫  t ( s ) t ( s )  t ( s ) t ( s )
 
Si llamamos:
qO ds δO = ∫ ds y δ1 = ∫ t ( s ) t ( s )
Entonces
_ δO q = −
δ1

Si se supone que el tubo se transforma en una sección abierta por medio de un
corte longitudinal en m, el término δ0 de la ecuación es el alabeo relativo de las

<!-- p. 7 -->

caras opuestas del corte longitudinal en m para la sección abierta, debido al
flujo de corte 0q . De forma similar δ1 es el alabeo relativo de las caras opuestas
del corte longitudinal en m para la sección abierta, debido al flujo de corte
constante de valor unitario q = 1 , por lo tanto qδ1 es el alabeo relativo debido a
q . Los términos δ0 y δ1 se denominan coeficientes de influencia, o más
específicamente flexibilidades y la ecuación que los relaciona ecuación de
deformaciones consistentes, que físicamente expresa que el desplazamiento
relativo de las caras de un corte longitudinal hipotético es cero para un tubo
cerrado.
qConocidos qo y queda determinado el estado de tensiones que se produce
en la sección para una carga que pasa por el centro de cortante.
En función de estos resultados se puede hallar la resultante (modulo y recta
qde aplicación) de las tensiones rasantes producidas por el flujo qo .El flujo
produce solamente un par que en sentido antihorario tiene el valor:
_
Mt = 2q Ω

Conocidas la resultante de ambos flujos de corte los mismos se superponen y
se obtiene la recta de aplicación del efecto conjunto. La adición del efecto
producido por el flujo constante produce un desplazamiento de la recta de
aplicación, que se traslada a una paralela. El centro de corte pertenece a esa
recta. La distancia entre la recta original y la recta final será:
_
M t ( q ) d =
R ( qo )
qDonde Mt es el momento producido por el flujo constante y R es la resultante
del flujo qo.

Si la sección tiene un eje de simetría la intersección de ese eje con la recta de
aplicación anteriormente obtenida será el centro de cortante.
En caso que la sección no tenga ningún eje de simetría deberá realizarse otro
proceso similar eligiendo otro punto m y obteniendo una nueva recta de
aplicación. La intersección de ambas rectas de aplicación será el centro de
cortante.
Conocido el centro de cortante la respuesta de la barra para una determinada
carga se resuelve descomponiendo la carga en una fuerza que pase por el
centro de cortante y en un momento. La primer componente causara una
flexión sin torsión y la segunda una torsión pura, lo que significa un giro en
relación al centro de torsión, que como ya hemos visto coincide con el centro
de cortante.

Flexión en tubos multicelulares de pared delgada

En el problema de flexión de secciones multicelulares, se introduce un flujo de
corte incógnita por cada celda cerrada. Como consecuencia un tubo de n
celdas sometido a flexión tiene n flujos de corte incógnitas.

<!-- p. 8 -->

El procedimiento que se utiliza para evaluar estas cantidades es similar al
utilizado para analizar la torsión de las secciones multicelulares y extiende las
ideas presentadas al analizar flexión en tubos de una celda.
Para ello se eligen n puntos m1, m2 ......mn donde se suponen cortes de las
paredes de las celdas. Los cortes se realizan uno en cada celda de manera
que la sección quede como si fuera una sección abierta.
En esta sección abierta se calcula el valor del flujo qo , llamaremos qoi al valor
del flujo que se produce en la celda i. Este flujo no es constante y depende de
una coordenada s que recorre la celda en sentido antihorario.
Si la carga aplicada pasa por el centro de cortante para cada celda deberá
verificarse que no presenta giro. Debera cumplirse que:

_ _ _
∂ 01 + ∂11 q1 + ∂12 q 2 + .......... ...........∂ 1n q n = 0

_ _ _
∂ 02 +∂ 21 q1 + ∂ 22 q 2 + .................... .∂ 2 n q n = 0
..........................................................
_ _ _
∂ 0 n + ∂ n1 q1 + ∂ n 2 q 2 + .......... ...........∂ nn q n = 0

ds ds qo ( s ) ds y ∂ 0 i = ∫Donde ∂ ii = ∫Ci , para i ≠ j ∂ ij = − ∫Cij t t Ci t ( s )

Donde Ci es el borde de la célula i , Cij es el borde de la celula i que limita con
la célula j . Si las células no tienen frontera común el coeficiente
correspondiente será cero.

Con este sistema de n ecuaciones con n incógnitas se obtienen los n flujos de
_ _ _ _
corte correspondientes o sea : q1 , q 2 , q 3 .......... q n .
El flujo de la sección abierta producido por qo genera una resultante R(qo) y una
_ _ _ _
recta de aplicación. Los flujos q1 , q 2 , q 3 .......... q n no producen resultante y si
producen un momento torsor de valor:
n _
M t = 2 qi ∑Ω i
i =1

La adición del efecto producido por los flujos constantes produce un
desplazamiento de la recta de aplicación, que se traslada a una paralela. El
centro de corte pertenece a esa recta. La distancia entre la recta original y la
recta final será:
M t d =
R ( qo )

Si la sección tiene un eje de simetría la intersección de ese eje con la recta de
aplicación anteriormente obtenida será el centro de cortante.
En caso que la sección no tenga ningún eje de simetría deberá realizarse otro
proceso similar eligiendo otros puntos mi y obteniendo una nueva recta de

<!-- p. 9 -->

aplicación. La intersección de ambas rectas de aplicación será el centro de
cortante.
Conocido el centro de cortante la respuesta de la barra para una determinada
carga se resuelve descomponiendo la carga en una fuerza que pase por el
centro de cortante y en un momento. La primer componente causara una
flexión sin torsión y la segunda una torsión pura, lo que significa un giro en
relación al centro de torsión, que como ya hemos visto coincide con el centro
de cortante.
