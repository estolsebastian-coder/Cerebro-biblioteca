---
type: libro
title: "Parte5"
author: "lauri"
categoria: "ESTRUCTURA"
paginas: 22
extraccion: "texto"
fuente: "local:E:/MATERIAL DE CONSULTA/ESTRUCTURA/BIELAS Y TIRANTES/Parte5.pdf"
convertido: 2026-10-16
---

# Parte5

> Texto extraído de `ESTRUCTURA\BIELAS Y TIRANTES\Parte5.pdf` (22 páginas, texto). El PDF original está en el disco E: (MATERIAL DE CONSULTA); `<!-- p. N -->` marca el inicio de cada página.

<!-- p. 1 -->

Parte 5:

Modelado del hormigón estructural mediante modelos de bielas y tirantes
− Discusión de los ejemplos según el Apéndice A de ACI 318-2002

Kart - Heinz Reineck

Sinopsis

Luego de un breve resumen de los contenidos de la Publicación Especial y los ejemplos, se
discuten varios puntos generales en base a observaciones surgidas de los ejemplos. La
elección de un modelo de bielas y tirantes es un punto fundamental, y es posible que
diferentes ingenieros propongan diferentes modelos para una misma estructura. Esto
conduce a una discusión de la unicidad de los modelos y si es o no aceptable que diferentes
ingenieros elijan diferentes modelos y, en consecuencia, diferentes cantidades y
disposiciones de armaduras para una misma región D. Otro punto identificado en algunos
de los ejemplos es la transición entre una región B y una región D; también se presenta el
procedimiento para modelarla. Finalmente se enfatiza el papel y la importancia del
detallado de las armadura y se incluyen algunos ejemplos. Además, se presentan algunas
observaciones que llevaron a recomendar la reconsideración de algunos requisitos del
Código.

Karl-Heinz Reineck recibió sus títulos de Ingeniero y Doctor en Ingeniería de la
Universidad de Stuttgart. Se dedica tanto a la investigación como a la docencia en el
Instituto de Diseño Conceptual y Estructural de Estructuras Livianas (ILEK), Universidad
de Stuttgart, donde se desempeña como director de dos grupos de investigación y director
ejecutivo del Instituto. Sus investigaciones abarcan el diseño de hormigón estructural, el
diseño con modelos de bielas y tirantes y detallado del hormigón estructural, y el diseño de
tanques de hormigón para agua caliente de rendimiento elevado. Es miembro del Comité
445 de ASCE-ACI, “Corte y Torsión”, donde preside dos subcomités, y también es
miembro del Grupo de Trabajo fib 1.1 “Diseño Práctico”.

<!-- p. 2 -->

Parte 5

1 Resumen

Los principales objetivos de esta Publicación Especial son brindar información y
antecedentes sobre el uso de modelos de bielas y tirantes de acuerdo con el Nuevo
Apéndice A de ACI 318-02 y presentar algunos ejemplos de diseño.
La Parte 2 describe el desarrollo del Apéndice A y proporciona información sobre el
propio Comentario de ACI 318. Justifica los valores de resistencia dados en el Apéndice A
por medio de comparaciones con otros códigos y con recomendaciones basadas en
resultados de ensayos.
La Parte 3 presenta resultados de ensayos importantes y bien conocidos que justifican el
empleo de modelos de bielas y tirantes para el diseño del hormigón estructural.
Los ejemplos presentados en la Parte 4 se pueden clasificar en diferentes grupos:

− Regiones D clásicas: Ejemplos 1, 2, 3 y 6. Estas regiones se diseñan usando modelos
de bielas y tirantes desde hace tiempo atrás; para ellas existe evidencia experimental,
según lo descrito en la Parte 3.

− Regiones D en vigas: Ejemplo 5 con apoyos indirectos. Hasta la fecha estas regiones
han sido tratadas en algunos códigos, a menudo mediante una regla adicional para el
detallado que indica la necesidad de disponer suspensores, aún no incorporadas en ACI
318-02.

− Regiones D en muros de edificios: Ejemplos 4, 7 y 8.

− Regiones D en estructuras tridimensionales: Ejemplos 9 y 10.
En las siguientes secciones se presentan algunas observaciones de carácter general y se
discuten algunos temas de relevancia general para el diseño mediante modelos de bielas y
tirantes.

2 Modelado y unicidad de los modelos

2.1 Encontrar un modelo
Encontrar un modelo para una geometría y un conjunto de cargas dadas para un miembro o
una región D es la primera y más importante tarea que debe emprender el ingeniero
calculista. Una vez seleccionado el modelo, el posterior análisis de las fuerzas y la
verificación de las tensiones son procesos relativamente sencillos. Schlaich, Schäfer y
Jennewein (1987) presentaron los diferentes métodos de modelado; estos métodos
consisten en:

− utilizar un ejemplo normalizado o adaptarlo a la geometría o fuerzas dadas, como por
ejemplo en el caso ya conocido de las ménsulas o vigas de gran altura;

− usar distribuciones de tensiones elásticas lineales en secciones críticas para determinar
la ubicación de las principales bielas o tirantes; y
226

<!-- p. 3 -->

Parte 5

− aplicar el método de la trayectoria de las cargas.
Los dos primeros métodos resultan bastante obvios y ya fueron descritos por Schlaich et al.
(1987). Por lo tanto, a continuación sólo explicaremos brevemente el método de la
trayectoria de las cargas y presentaremos un ejemplo tomado de las Recomendaciones FIP
(1999).
La región D ilustrada en la Figura 1 con una carga puntual aplicada en la dirección del eje
del miembro puede ocurrir en el extremo de una viga con un anclaje de pretensado o bien
puede representar una columna con carga excéntrica. En el extremo de la región D se
conoce la distribución de tensiones y ésta corresponde a la de la región B; en consecuencia,
se la puede calcular usando fórmulas conocidas de acuerdo con la teoría elástica lineal si el
miembro no está fisurado. Todos los diagramas de cuerpo libre ilustrados en la Figura 1
están en equilibrio. El modelo básico de la Figura 1a demuestra el equilibrio global para
una fuerza aplicada en el extremo con una pequeña excentricidad e. Sin embargo, este
modelo no es representativo para el flujo interno de fuerzas dentro de la región D. El
modelo refinado de la Figura 1b se obtiene dividiendo la fuerza aplicada F en dos fuerzas y
dividiendo el diagrama de tensiones del extremo derecho en dos partes con las fuerzas en
las bielas C1 y C2 como resultantes, cada una de ellas iguales a F/2. La ubicación de estas
dos fuerzas C1 y C2 es conocida, de manera que para completar el modelo de bielas y
tirantes y determinar la fuerza en el tirante T1 de la Figura 1b sólo es necesario suponer la
ubicación del nodo (N1) y el valor de d1.
Aplicando el método de la trayectoria de las cargas a una fuerza con gran excentricidad se
obtiene el modelo de bielas y tirantes indicado en la Figura 1c. En este caso la trayectoria
de la fuerza F sólo cubre la parte inferior del miembro y en el extremo derecho deja un par
de fuerzas iguales y opuestas en la parte superior de la sección. La magnitud y ubicación
de estas fuerzas también son conocidas, de manera que resulta relativamente sencillo
completar el modelo de bielas y tirantes.

l=h l=h l=h F e σ1 = (1 − 6 )
σ1 σ1 bh h
T3 T3h/2 N1 h/2
a C 2 N1 C 3= T 3
C=F T1 a T2 T1
e C 2= F/2 e F F
C1 F C 1= F/2
σ2 a/4 d1 σ2 a/4 d 1 F e σ 2 = (1 + 6 )
bh h
a) modelo básico b) modelo refinado c) modelo para grandes
excentricidades e
Figura 1: Método de la trayectoria de las cargas aplicado a una región D con una fuerza
concentrada en la dirección del eje del miembro −pequeña excentricidad y gran
excentricidad

227

<!-- p. 4 -->

Parte 5

De manera similar se puede aplicar el método de la trayectoria de las cargas al extremo de
una viga con un anclaje de pretensado como se ilustra en la Figura 2. En este caso en el
borde de la región B, además de las tensiones longitudinales, también ocurren tensiones de
corte. También aquí el modelo básico (Figura 2a) no es representativo del flujo interno de
las fuerzas. Se requiere un modelo refinado para hallar la fuerza en el tirante transversal T1
(Figura 2b). El modelo aún más refinado de la Figura 2c se obtiene desviando ligeramente
la biela superior inclinada C1, y así se evidencian las bajas fuerzas de tracción en la esquina
superior izquierda.

esquina no
solicitada
C 2 N2 T2 C12 C2 C1 N1 C11
C P T1
T1 C 3 2
P P2
σx τxz N2
V V V

a) modelo básico b) modelo refinado c) modelo más refinado

Figura 2: Método de la trayectoria de las cargas aplicado a la región D en el extremo
apoyado de una viga con un anclaje de pretensado

Tradicionalmente los códigos, como por ejemplo en el CEB-FIP MC 90, tratan todas estas
fuerzas y tensiones de tracción mediante reglas para las denominadas "tensiones de
descantillado" o "tensiones de aplastamiento". Con los modelos de bielas y tirantes estos
nombres artificiales se vuelven innecesarios y todas las fuerzas y tensiones de tracción se
pueden derivar a partir de la aplicación del método de la trayectoria de las cargas.
Finalmente, es importante señalar que aquí el método de la trayectoria de las cargas no
requirió un análisis por elementos finitos porque las tensiones requeridas en el borde de la
región B se pudieron hallar aplicando los principios básicos de la mecánica. Esta
orientación en base a las tensiones lineales elásticas fue un elemento determinante para la
selección del modelo. Por lo tanto, sólo fue necesario tomar algunas decisiones menores
respecto de la ubicación de nodos y tirantes, como por ejemplo la ubicación del nodo (N1)
en la Figura 2a o la ubicación del tirante T1 en la Figura 2b.

2.2 Unicidad de los modelos
Las técnicas de modelado presentadas implican que es necesario adoptar hipótesis con
respecto a la ubicación de nodos y bielas o tirantes, de manera que es posible que las
soluciones propuestas por diferentes ingenieros difieran entre sí. En los dos casos
anteriores estas diferencias son pequeñas y de escasa importancia porque los factores
determinante de la geometría del modelo fueron las distribuciones elásticas de las
tensiones. En otros casos las diferencias pueden ser más significativas y conducir a

228

<!-- p. 5 -->

Parte 5

diferentes fuerzas en los tirantes, posiblemente en diferentes ubicaciones, y en
consecuencia, diferentes cantidades de armadura requerida.
Esto plantea la cuestión relacionada con la unicidad de los modelos de bielas y tirantes
para un conjunto de cargas y una geometría determinada de una región D, lo cual nos
conduce nuevamente a las bases de la utilización de modelos de bielas y tirantes para el
diseño. Al aplicar modelos de bielas y tirantes se deben satisfacer las dos condiciones
siguientes: equilibrio y límites de resistencia para los elementos de los modelos de bielas y
tirantes. Estas dos condiciones cumplen con la solución estática de la teoría de la
plasticidad, es decir, satisfacen las condiciones de equilibrio y fluencia, y esto conduce a
un límite inferior de la carga de colapso como lo explican, por ejemplo, Muttoni, Schwartz
y Thürlimann (1996).
Por lo tanto no se satisface la compatibilidad; en otras palabras, no necesariamente es
posible hallar un mecanismo con solución estática. Las diferentes soluciones conducen a
diferentes cargas últimas, y sólo el valor máximo de las cargas de colapso corresponde a un
mecanismo. La solución exacta o correcta satisfará el límite inferior de todas las posibles
soluciones cinemáticas.
El hecho de que sea posible hallar diferentes modelos de bielas y tirantes es por lo tanto
una condición inminente de este método de diseño basado en la solución estática de la
teoría de la plasticidad. Sólo es dable anticipar una única solución si se satisface la
compatibilidad. Cualquier consideración de la compatibilidad requiere el cálculo de
tensiones y deformaciones, lo cual requiere hipótesis para las leyes constitutivas de los
elementos del modelo de bielas y tirantes, y esto nos lleva a un análisis no lineal del
modelo. A fin de evitar esta complicación, Schlaich et al. (1987) recomendaron orientar el
modelo de acuerdo con los campos de tensión de un análisis elástico lineal. En primer
lugar esto tiene la ventaja de que los cambios en el flujo de fuerzas dentro de la región D
son pequeños entre el estado de tensiones elásticas y el estado fisurado del miembro hasta
alcanzar la carga última en el modelo supuesto. Por lo tanto, no se produce una gran
redistribución de fuerzas internas, lo cual exigiría una gran ductilidad. En segundo lugar, el
modelo también se puede usar para verificar el estado límite de serviciabilidad, es decir,
los anchos de fisura y las deformaciones.
Con respecto a la ductilidad, que se asume está dada por la teoría de la plasticidad, y la
verificación de las condiciones de fluencia, se debe observar que normalmente un diseño
mediante modelos de bielas y tirantes conduce a la fluencia de las armaduras pero no a la
falla de las bielas. Esto se debe a que los anchos de las bielas a menudo quedan
determinadas por las dimensiones de las placas de carga o las condiciones estáticas, o bien
los anchos de las bielas se asumen de manera de no llegar a los límites de tensión de las
mismas. No siempre es aconsejable suponer valores mínimos para los anchos de las bielas
de manera que se llegue a los límites de tensión en todas las bielas, porque en ese caso los
tirantes conectados también están concentrados y esto provoca la congestión de las
armaduras. Por lo tanto, la conclusión práctica para asegurar un comportamiento dúctil

229

<!-- p. 6 -->

Parte 5

consiste en disponer armadura para todas las fuerzas de tracción principales y diseñar de
manera que las bielas y nodos no determinen la falla.
El hecho de que sea posible hallar diferentes modelos de bielas y tirantes para un problema
dado y que no se pueda anticipar una solución única confundió a muchos ingenieros
cuando los modelos de bielas y tirantes fueron propuestos como herramienta de diseño. Tal
vez esto se debe a que los ingenieros estructurales están entrenados para hallar la única
solución analítica posible. Esto es válido bajo ciertas condiciones y restricciones, por
ejemplo, al analizar una estructura para una geometría y cargas dadas de acuerdo con la
teoría elástica lineal.
Sin embargo, al contrario de lo que ocurre en un análisis, al diseñar los ingenieros pueden
elegir una variedad de soluciones, y para una misma tarea cuenta con numerosas opciones
que satisfacen las condiciones dadas y los requisitos sobre seguridad, economía y calidad.
Esto se demuestra en la Figura 3, que ilustra numerosos tipos de puentes que un diseñador
puede considerar durante el diseño conceptual o durante las primeras etapas de un
proyecto. La clasificación de los sistemas estructurales para puentes de la Figura 3a
(Schlaich y Bergermann, 1992) distinguen soluciones en las cuales los principales
componentes estructurales están ya sea en compresión o en tracción. Aún después de tomar
estas decisiones básicas y, por ejemplo, seleccionar las vigas y optar por el hormigón, aún
existe una gran variedad de sistemas posibles como lo indica la Figura 3b. Estos van desde
vigas cajón paralelas estáticamente determinadas o indeterminadas, pasando por vigas de
celosía con o sin articulación a mitad de tramo, vigas cuya forma concuerda con el
diagrama de momentos (como el de Schlaich), o puentes reticulados (como el de Menn).

compresión-tracción

a) clasificación de sistemas estructurales para b) variedad de vigas para puentes
puentes, según Schlaich y Bergerman (1992) de hormigón

Figura 3: Diferentes sistemas estáticos para puentes
230

<!-- p. 7 -->

Parte 5

En vista de esta enorme variedad que se presenta al diseñar una estructura, se debería
aceptar que también para el diseño de hormigón estructural existen numerosas soluciones
posibles, y que consecuentemente diferentes ingenieros pueden optar por diferentes
modelos de bielas y tirantes y llegar a diferentes disposiciones y cantidades de armaduras.
Todos los modelos proporcionarán la capacidad requerida para el miembro, siempre y
cuando se provea la ductilidad necesaria. Se puede anticipar que la ductilidad será
suficiente si el comportamiento estructural próximo a la carga última del miembro o la
región D es determinado por la fluencia del acero y si los nodos y particularmente los
anclajes están bien diseñados. Se puede anticipar menos ductilidad si las bielas y las
tensiones de compresión determinan el diseño; esto no debería ocurrir si el diseño ha sido
bien seleccionado.
Un buen ejemplo de modelos diferentes pero igualmente válidos es el extremo entallado de
una viga, analizado en la Parte 3 y en el Ejemplo 2. La Figura 4 muestra los modelos en
cuestión. El modelo de la Figura 4a requiere una concentración de estribos en la cara del
extremo de la viga, mientras que el modelo de la Figura 4b conduce a un segundo tirante
T2 para anclar el tirante T4 y en consecuencia promueve la distribución de los estribos en
una determinada longitud. En las Recomendaciones FIP (1999) se propone un tercer
modelo (Figura 4c), el cual se desarrolló de manera de minimizar las dimensiones de la
cartela.
Cada modelo tiene sus ventajas y sus desventajas, las cuales han sido identificadas por
diferentes investigadores. El modelo de la Figura 4a puede dar como resultado longitudes
muy cortas para el tirante horizontal (fuerza de 281), pero la biela inclinada entre el nodo
D y el nodo B (fuerza de 195) no parece concordar con el mecanismo de falla observado ya
que cruza la fisura inclinada que comienza en la esquina interior (ver Figura 9b, Parte 3).
El modelo de la Figura 4b evita este problema pero, al igual que el modelo de la Figura 4a,
este modelo se basa en armadura ortogonal, la cual no es favorable para limitar el ancho de
la fisura inclinada que comienza en la esquina interior. La armadura inclinada para el
tirante T5 ilustrada en la Figura 4c controla de manera más eficiente el ancho de la fisura
inclinada, la cual se abre bastante en el momento de la falla, pero este modelo no es capaz
de tratar las fuerzas horizontales en el apoyo que pueden ocurrir no intencionalmente
debido a la fricción en el apoyo. Por lo tanto, las Recomendaciones FIP (1999)
recomiendan una combinación de los dos últimos modelos.
Finalmente debemos señalar que los tres modelos pueden exhibir la totalidad de la
capacidad deseada siempre que sean bien diseñados y detallados como se demostró en la
Parte 3 para el modelo de la Figura 4a.

231

<!-- p. 8 -->

Parte 5

B E 56
\-112 -513 180 14 383 -195
A 281 D-478 -478 454 D' 260 356 274 -147
260
513 915
C F 90 100

318
95 702,5 mm

a) modelo para el ensayo de Cook y Mitchell (1988), ver Fig. 9c de la Parte 3

N1

T1 = F1 h1 N3 θ11 T4 T5 = F2 / sinθ
T3 = F1 T3 = F2 N4
T2 = F1
h2 F1 θ1 θ F2 α θ N2

l1 2l l3 = z cotθ

1 / l3 F1 /2l F
F1 / l1

b) modelo 1 propuesto por las c) modelo 2 propuesto por las
Recomendaciones FIP (1999) Recomendaciones FIP (1999)

Figura 4: Diferentes modelos para vigas con extremos entallados

Para el correcto diseño de un modelo para ménsulas se llevó a cabo una discusión similar,
y en la Figura 5 esto se demuestra para una ménsula cargada por su parte inferior. El
primer modelo de la Figura 5a sigue el requisito práctico de utilizar exclusivamente
armadura ortogonal, mientras que el modelo de la Figura 5b muestra un tirante inclinado
que sigue directamente las trayectorias según la teoría elástica lineal. Este tipo de armadura
inclinada es más eficiente, lo cual se puede visualizar por la menor longitud de los tirantes
en este modelo.

232

<!-- p. 9 -->

Parte 5

a) modelo para armadura ortogonal b) modelo para armadura inclinada

Figura 5: Modelos de bielas y tirantes para ménsulas cargadas por su parte inferior
[Schlaich y Schäfer (2001)]

Sin embargo, este tipo de discusión sobre el flujo de las fuerzas no es suficiente para
decidir cuál es el mejor modelo. Esta decisión requiere el detallado de los nodos y anclajes,
lo cual puede llegar a determinar todo el diseño de la región D.

2.3 Discusión de la unicidad de los modelos para diferentes ejemplos

2.3.1 Ejemplo 1

El Ejemplo 1 es un ejemplo básico de una viga de gran altura para el cual se pueden
discutir y estudiar ampliamente los principios de diseño y diferentes modelos, como se
hizo en el Ejemplo 1a. Además, en la Sección 3.6 de la Parte 3 se presenta un informe
exhaustivo de un ensayo de esta viga de gran altura que permitió conocer el
comportamiento estructural y la validez de los modelos ilustrados en la Figura 6.
Los tres modelos ilustrados en la Figura 6 difieren en la cantidad de armadura transversal
requerida y consecuentemente en la distribución de la fuerza del tirante en el cordón
inferior. El primer modelo (Figura 6a) es el que se seleccionó para el diseño del Ejemplo
1a, y ciertamente se encuentra del lado de la seguridad en relación con el diseño de la
armadura transversal ya que la fuerza del tirante vertical es igual a la carga aplicada. La
fuerza en el cordón inferior está desfasada y el anclaje en el apoyo se debe diseñar para una
fuerza mucho más pequeña (es decir, 50%) que en el centro del tramo.
El modelo de la Figura 6b parece ser un modelo más sencillo. No hay tirante vertical y la
fuerza en el tirante inferior es constante entre apoyos. En consecuencia, el anclaje en el
apoyo se debe diseñar para el 100% de la fuerza en el centro del tramo. El hecho de que no
haya tirantes verticales en el modelo no significa que no sea necesario disponer estribos,
sino que estos estribos se deberían agregar siguiendo las reglas para armadura mínima,
como se indica en la Sección 3.6 del Ejemplo 1b.

233

<!-- p. 10 -->

Parte 5

a) modelo supuesto para el Ejemplo 1a

b) modelo supuesto para el Ejemplo 1b

c) modelo según las Recomendaciones FIP (1999)

Figura 6: Diferentes modelos para el Ejemplo 1

El tercer modelo (Figura 6c) está comprendido entre los dos modelos anteriores y es
estáticamente indeterminado en su interior. Las Recomendaciones FIP (1999) dan una
regla empírica para determinar qué parte de la carga aplicada se debe asignar al tirante
vertical; esto depende de la distancia entre la carga y el eje del apoyo. Así se logra una
transición consistente entre el diseño de una viga de gran altura con cargas próximas a los
apoyos y una viga esbelta, en la cual la totalidad de la carga aplicada debe ser transferida
por medio de un reticulado sin transferencia de carga directa al apoyo por parte de una
biela inclinada.

234

<!-- p. 11 -->

Parte 5

La ausencia de un tirante transversal explícito en el modelo de la Figura 6b puede parecer
crítica, ya que exige que el diseñador recuerde especificar la armadura mínima requerida.
Por otra parte, se podría argumentar que si se coloca armadura transversal mínima ésta
llevará parte de la carga, de manera que el modelo de la Figura 6c es en realidad efectivo.
La diferencia es sólo que la capacidad del tirante transversal que representa la armadura
mínima es siempre igual y no depende de la distancia entre la carga y el eje del apoyo.
Para concluir esta discusión, el modelo de la Figura 6c parece ser una solución adecuada y
práctica, que demuestra la necesidad de aumentar la cantidad de armadura transversal a
medida que a aumenta entre a = 0,5z y a = 2z (a = distancia entre la carga y el eje del
apoyo; z = brazo de palanca interno). Por lo tanto, en la Sección 8.3 de la Parte 2
MacGregor (2002) propone que el Subcomité ACI 318 E considere un requisito similar
como posible adición al Apéndice A.

2.3.2 Ejemplo 4

El Ejemplo 4 presenta un problema nuevo y desconocido, para el cual no es posible
encontrar soluciones en los libros de texto ni tampoco ensayos realizados. Por lo tanto no
resulta sorprendente que varios ingenieros a los cuales se les planteó este ejemplo hayan
propuesto modelos completamente diferentes, algunos de los cuales se ilustran en la Figura
\7.
En la Figura 7 a1 se ilustra el modelo seleccionado en el Ejemplo 2 (Figura 4-3). Este se
podría describir como una solución "viga sobre viga", lo cual significa que la parte
superior se considera como un miembro estáticamente determinado soportado por apoyos
inclinados. Debido a que las reacciones de apoyo de este miembro son iguales, es decir,
cada una de las bielas inclinadas lleva la mitad de la carga, la viga inferior debe transferir
parte de la carga debajo de la abertura al apoyo izquierdo de manera de satisfacer el
equilibrio global. Esto dio por resultado una reacción en el apoyo izquierdo mayor que la
mitad de la carga aplicada (ver la Sección 2.2 del Ejemplo 4). La parte superior se
considera como una viga de gran altura y el modelo seleccionado es igual al seleccionado
para el Ejemplo 1b ilustrado en la Figura 6b.
El modelo de la Figura 7 a2 es una variante de este primer modelo donde la biela inclinada
de la derecha se divide en una biela vertical y una biela inclinada. La biela vertical que
lleva la parte de la carga a transferir al apoyo izquierdo está más próxima al apoyo que en
el modelo anterior. En la Figura 6c se ilustra el modelo correspondiente a la viga de gran
altura superior.
Los modelos de la Figura 7b se basan en la hipótesis que los miembros verticales cortos al
lado de la abertura proveen una rigidez flexional que se puede evaluar mediante un análisis
de pórtico. Entonces la parte superior del modelo de la Figura 7 b1 refleja una viga de gran
altura abrazada a ambos lados por un cordón traccionado sobre la abertura. Por el
contrario, el modelo de la Figura 7 b2 se puede describir como dos ménsulas que salen de
los miembros verticales al lado de la abertura, llegan hasta el punto de carga y allí cada una

235

<!-- p. 12 -->

Parte 5

recoge la mitad de la carga. Las ménsulas apenas se tocan bajo las cargas, pero no están
conectadas; esto significa que sólo hay tracción en el cordón superior y no se requiere
armadura en el cordón inferior directamente sobre la abertura.
En todos los modelos discutidos hasta este momento la viga superior estaba apoyada de
manera simétrica, pero para el modelo presentado en la Figura 7c esta hipótesis se
abandona. La carga se divide entre las reacciones de apoyo en dos partes iguales y en
consecuencia la viga debajo de la abertura no transfiere ninguna carga. Por lo tanto no es
necesario proveer ninguna armadura transversal en la viga inferior. La parte superior
izquierda sobre la abertura exhibe predominantemente una acción tipo ménsula, mientras
que la parte derecha constituye una viga simple como la del modelo ilustrado en la Figura
7 a1.

1000 kN 1000 kN 1000 1000

1333 kN 667 kN 1333 667

a1) modelo del Ejemplo 4 a2) modelo refinado para el modelo de a1

1000 1000 1000 1000

1333 667 1333 667

b1) modelo en base a análisis de pórtico b2) modelo con dos ménsulas
en la viga superior
1333 kN 667 kN

1333 kN 667 kN

c) modelo en base a la trayectoria de las cargas sin transferencia de carga en la viga inferior

Figura 7: Diferentes modelos posibles para el Ejemplo 4
236

<!-- p. 13 -->

Parte 5

En vista de las importantes diferencias entre todos estos modelos, el diseñador puede
requerir algunos lineamientos para seleccionar un modelo entre todos los modelos posibles.
Para ello puede realizar un análisis elástico lineal del muro. Sin embargo, aún en ausencia
de este análisis, un buen criterio profesional proporcionará una perspectiva crítica:

− Los modelos de la Figura 7b son menos probables que los de la Figura 7a debido a que
son menos rígidos, lo cual se visualiza por los tirantes de mayor longitud requeridos.

− El modelo de la Figura 7 b2 obviamente viola la compatibilidad en la parte central de
la viga superior sobre la abertura porque no existe conexión alguna.

− En el modelo de la Figura 7c la viga inferior actúa exclusivamente como miembro
traccionado, pero con la tracción en la parte inferior; esto no es compatible con la
rigidez flexional de este miembro.
Por lo tanto, una solución sensata podría ser una combinación de los modelos de las Figura
7 a2 y 7 b1, con cierta preferencia por el primer modelo de manera que soporte más que el
segundo. Sin embargo hay otras soluciones posibles.

3 Transición entre regiones D y regiones B de una viga

La transición entre regiones D y regiones B de una viga ya se discutió cuando se explicó el
método de la trayectoria de las cargas en las Figuras 1 y 2. Es evidente que es necesario
modelar una transición consistente, y que ésta se garantiza aplicando la distribución de
tensiones de la región B en la sección de borde de la región D. En las Figuras 1 y 2 estas
tensiones se calcularon mediante un análisis elástico lineal, pero también se podrían aplicar
las tensiones obtenidas de un diseño de sección fisurada, tal como un diseño flexional para
el momento y la fuerza de compresión axial en el caso de la Figura 1c, si las tensiones
demostraran que la sección está fisurada.
En caso que haya fuerzas de corte actuando en la sección de borde como en la Figura 2, el
modelo para una sección fisurada en la región B es el conocido modelo reticulado ilustrado
en la Figura 8 para una viga con voladizo [Reineck (1996)].

237

<!-- p. 14 -->

Parte 5

biela con campo de
nodo compresión paralelo

Z

θ θ θ

nodo
tirantes biela con campo de compresión
en forma de abanico

Figura 8: Modelo reticulado y campos de tensión para una viga con voladizo

En las regiones D la carga se transfiere mediante campos de tensiones en forma de abanico,
mientras que en las regiones B el modelo reticulado se caracteriza por un campo de
tensiones paralelas inclinadas un ángulo θ respecto del eje x. Una sección en la región B de
la viga contiene las fuerzas del reticulado como se ilustra en el extremo izquierdo de la
viga de la Figura 8, y de manera similar si el miembro está fisurado estas fuerzas se deben
aplicar en el borde de una región D.
Por lo tanto, para que haya una transición consistente entre las regiones B y las regiones D
de una estructura de hormigón, tal como una viga, es necesario conocer el brazo de palanca
interno z y el ángulo θ. Esto plantea el problema de derivar el ángulo θ para las bielas
inclinadas en el alma a partir del diseño al corte realizado de acuerdo con el Capítulo 11 de
ACI 318. Como se indica en el Ejemplo 5, es posible derivar el ángulo θ de las bielas
inclinadas en el alma del modelo reticulado ya que se conoce la cantidad de estribos. El
modelo de la Figura 8 (ver también la Figura 5-5 del Ejemplo 5) muestra que la fuerza de
corte en la región B debe ser tomada por las fuerzas en los estribos en la longitud (z cotθ):

Vn = (Av / sv) fy z cotθ

y a partir de esta expresión el ángulo θ se puede calcular de la siguiente manera:
Vn s v cot θ = ⋅
f y z A v

De este modo el diseño al corte de ACI 318 usando un término Vs y un término Vc se
interpreta mediante un modelo reticulado, a fin de modelar la transición de una región B a
una región D.

238

<!-- p. 15 -->

Parte 5

4 Detallado

Finalmente debemos tratar el tema del detallado, de importancia fundamental como lo
señalaran Leonhardt (1965, 1973) y Leonhardt y Mönning (1977). Esto continúa siendo
importante en los modelos de bielas y tirantes, ya que los modos se definen como un
elemento a verificar. El método de bielas y tirantes automáticamente obliga a los
ingenieros a prestar atención a los nodos y anclajes. Esto permite detectar muchos
problemas durante las primeras etapas del diseño e introducir los cambios necesarios para
evitar daños, detallando la estructura adecuadamente. Además de presentar el concepto del
diseño mediante modelos de bielas y tirantes, Schlaich y Schäfer (2001) presentan
numerosos ejemplos para el detallado en la continuación del artículo de Leonhardt (1973)
publicado en el Beton Kalender.
En esta sección se discuten algunos temas relacionados con el detallado, en base a la
experiencia y los ejemplos presentados en este informe. Éstos demuestran que el detallado
también significa dimensionar y modelar los campos de tensiones, sólo que a menor escala;
se debe refinar el equilibrio global de las bielas y tirantes en un nodo y posteriormente
revisar los campos de tensiones.
El primer punto es que en varios ejemplos se utilizan ganchos normales. Los ganchos
acortan la longitud de anclaje requerida en relación con una barra recta, pero no tanto como
se podría creer: los códigos europeos indican que el beneficio es de apenas 30 por ciento.
Además, debido a que existe el peligro de que la esquina sin armadura debajo del codo se
descantille como se ilustra en la Figura 9, el gancho resulta crítico en el caso de los apoyos
directos en el extremo de una viga como en el Ejemplo 1. Esto es particularmente cierto en
el caso de las barras de gran diámetro habitualmente utilizadas en Estados Unidos.

la esquina
se puede
descantillar

Figura 9: Gancho normal en un apoyo directo en el extremo de una viga

En estos casos es necesario proveer alguna longitud de anclaje detrás del apoyo como se
ilustra en la Figura 10. En principio estos detalles se deben considerar de manera
tridimensional (ver Figuras 10b y 10c), tanto para asegurar un buen anclaje como para que
no haya congestión de armaduras y se imposibilite la correcta colocación del hormigón.

239

<!-- p. 16 -->

Parte 5

db

c

„ 2c
„ 2c „ db/2 c

lb,neto

la, ver A.4.3.2
a) vista frontal b) corte c) planta

Figura 10: Detallado en un apoyo en el extremo de una viga con gancho normal

Una experiencia de tipo más general que se puede obtener a partir de los ejemplos es que
los requisitos sobre longitud de desarrollo de ACI 318 deben ser discutidos en mayor
profundidad. Las reglas contenidas en el Apéndice A no cumplen con las reglas del cuerpo
principal de la norma, y existen numerosas discrepancias entre ACI 318 y los códigos
europeos.
Por ejemplo, ni ACI 318 ni el Apéndice A de ACI 318 tratan claramente la influencia de la
presión transversal o las tensiones de tracción sobre la longitud de anclaje. Como lo
demuestra el Ejemplo 5, no se diferencia entre un nodo TCC, como por ejemplo un apoyo
directo en un extremo, y un nodo TTC, tal como un apoyo indirecto en un extremo.
Ensayos realizados han demostrado que el anclaje en los apoyos indirectos constituye un
punto crítico [Leonhardt, Koch y Rostasy (1971); Leonhardt, Walther y Dilger (1968);
Baumann y Rüsch (1970)]. Además, se debería revisar la longitud de anclaje del Apéndice
A como se ilustra en la Figura 10a, ya que en los códigos europeos la longitud de anclaje
comienza a partir de la cara interna del apoyo.
También se debería reconsiderar la relación entre los ganchos normales y los ganchos a
180º. Ningún código indica una diferencia respecto de acortar la longitud de anclaje con
relación a las barras rectas; por ejemplo, los códigos europeos asignan el mismo beneficio
del 30% a ambos elementos de anclaje. Sin embargo, cualquier gancho a 180º que confina
el hormigón dentro de su codo constituye un mejor anclaje en el estado límite último que
un gancho normal. El motivo de esta discrepancia es que actualmente las reglas para el
desarrollo de las longitudes de anclaje se basan en consideraciones de serviciabilidad,
como por ejemplo que sólo debe producirse un resbalamiento de 0,10 mm. Si se
consideraran las condiciones en el estado límite último, se evidenciaría el obvio beneficio
de utilizar ganchos a 180º.
Es verdad que el uso de ganchos de 190º significa que posiblemente sea necesario
seleccionar barras de menor tamaño a fin de tomar en cuenta el diámetro de doblado. Sin
240

<!-- p. 17 -->

Parte 5

embargo, hay una clara ventaja si hay anclajes cortos como en el caso de la ménsula
ilustrada en la Figura 11. En este caso Schlaich y Schäfer (2001) demostraron que se
requieren consideraciones exhaustivas para diseñar y detallar un detalle tan crítico.
En general, al determinar la longitud de desarrollo en el estado límite último resulta
indispensable definir valores realistas para la resistencia de adherencia y factores realistas
para los diferentes elementos de anclaje. Sólo así el diseñador puede considerar las
diferentes condiciones para nodos TCC o TTC que anclan barras de armadura. Se deberían
realizar más investigaciones sobre el dimensionamiento de los nodos y el desarrollo de las
armaduras como los realizados por Bergmeister, Breen y Jirsa (1991).

Cortes:
variante: variante: variante:
N A B C
F(H) Pos 3

Pos 1

Pos 3

Pos 2
Pos 2

Plantas: Posición del plato de carga: ≥ c
\> 3ds ≥ 2ds
variante: A ds

dbr 2ds
2
d > br+ 3ds 2

variante: B 3 dbr Pos 1
15ds
2 >lb

variante: C dbr >15d s

Figura 11: Detallado de una ménsula en una columna con longitud de anclaje corta,
según Schlaich y Schäfer (2001)

241

<!-- p. 18 -->

Parte 5

5 Conclusiones

El Apéndice A de ACI 318 constituye un importante paso hacia un diseño consistente del
hormigón estructural. Debería posibilitar un mejor diseño y detallado de las regiones D de
las estructuras de hormigón. En este informe se presentan los antecedentes de este
importante logro; su intención es alentar a los ingenieros para que adopten el diseño
mediante modelos de bielas y tirantes. Los nueve ejemplos presentados en esta Publicación
Especial de ACI deberían ayudar a los ingenieros a aplicar el Apéndice A en su trabajo
diario.

6 Referencias

ACI 318 (1999): Building Code Requirements for Structural Concrete (ACI 318-02) and
Commentary (ACI 318R-02). Reported by ACI Committee 318. American
Concrete Institute, Farmington Hills, MI. 445 pp.
Baumann, Th.; Rusch, H. (1970): Schubversuche mit indirekter Krafteinleitung (Ensayo
de corte con aplicación de carga indirecta). Deutscher Ausschuss für
Stahlbeton, Report 210, 1-42, W. Ernst u. Sohn, Berlin, 1970.
Bergmeister, K.; Breen, J.E.; Jirsa, J.O. (1991): Dimensioning of the nodes and devel-
opment of reinforcement. p. 551 - 556 en: IABSE Rep. V.62 (1991).
FIP Recommendations (1999): "Practical Design of Structural Concrete". FIP-
Commission 3 "Practical Design", Sept. 1996.
Publ.: SETO, Londres, Sept. 1999. (Distribuido por: fib, Lausanne)

Leonhardt, F. (1965): Über die Kunst des Bewehrens von Stahlbetontragwerken (Sobre
el arte de armar estructuras de hormigón).
Beton- und Stahlbetonbau 60 (1965), H.8, pp. 181; H.9, pp. 212.

Leonhardt, F.; Walther, R.; Dilger, W. (1968): Schubversuche an indirekt gelagerten,
einfeldrigen and durchlaufenden Stahlbetonbalken (Ensayos de corte en
vigas de hormigón armado apoyadas indirectamente − vigas de un tramo y
vigas continuas). Deutscher Ausschuss für Stahlbeton Report 201. 1968.
Leonhardt, F.; Koch, R.; Rostásy, F.S. (1971): Aufhängebewehrung bei indirekter
Lasteintragung von Spannbetonträgern, Versuchsbericht und
Empfehlungen (Uso de suspensores en la transferencia indirecta de cargas
en vigas de hormigón pretensado, informe de ensayos y recomendaciones).
Beton- and Stahlbetonbau 66 (1971), H.10, 233-241.
Discusión de: Baumann, Th.. Beton- und Stahlbetonbau 67 (1972), H.10,

242

<!-- p. 19 -->

Parte 5

238-239.
Leonhardt, F. (1973): Das Bewehren von Stahlbetontragwerken.
Beton Kalender 1973, W. Ernst & Sohn, Berlin. (Armado de estructuras de
hormigón. Reimpresión traducida al Inglés por B. Maisel, C&Ca,
Londres).
Leonhardt, F.; Mönnig, E. (1977): Vorlesungen über Massivbau - Teil 3: Grundlagen
zum Bewehren im Stahlbetonbau. Springer Verlag, Berlin, 1977.
MacGregor, J. G. (2002): Derivation of strut-and-tie models for the 2002 ACI Code. p. 7-
40 en: Examples for the design of structural concrete with strut-and-tie
models, Special Publication of ACI. American Concrete Institute,
Farmington Hills, 2002.
Muttoni, A.; Schwartz, J.; Thürlimann, B. (1996): Design of concrete structures with
stress fields. Birkhäuser, Basel, 1996.
Reineck, K.-H. (1996): Rational Models for Detailing and Design. p. 101-134 en: Large
Concrete Buildings. Rangan, B.V.; Warner, R.F. (Ed.). Large Concrete
Buildings. Longman Group Ltd., Burnt Mill, Harlow, Inglaterra, 1996.

Schlaich, J.; Bergermann, R. (1992): Fuβgangerbrücken. Katalog zur Ausstel lung an der
ETH Zurich, 1992 (Puentes peatonales. Catálogo de una exposición).
Schlaich, J.; Schäfer, K; Jennewein, M. (1987): Toward a consistent design for structural
concrete. PCI-Journal Vol. 32 (1987), No.3, 75-150.
Schlaich, J.; Schäfer, K. (2001): Konstruieren im Stahlbetonbau (Detallado del hormigón
armado). Betonkalender 90 (2001), Teil 11, 311 - 492.
Ernst & Sohn Verlag, Berlin 2001

7 Agradecimientos

Los autores desean agradecer la contribución de Arndt Goldack y Uwe Burkhardt de la
Universidad de Stuttgart, así como la de Robert Zechmann de la Universidad de Kansas,
quienes propusieron y ensayaron algunos de los modelos para el Ejemplo 4 presentado en
la Figura 7.
Los autores agradecen la edición de los gráficos realizada por Elfriede Schnee y Ali
Daghighi. También agradecen profundamente el trabajo de Angela Siller en la edición de
la versión final, considerando los comentarios aportados por los encargados de la revisión
del trabajo.

243

<!-- p. 20 -->

244

<!-- p. 21 -->

FACTORES DE CONVERSIÓN − LIBRA-PIE a SI (MÉTRICO)*

Para convertir de a multiplicar por
Longitud
pulgada milímetro (mm) 25,4E†
pie metro (m) 0,3048E
yarda metro (m) 0,9144E
milla (estatutaria) kilómetro (km) 1,609
Superficie
pulgada cuadrada centímetro cuadrado (cm2) 6,451
pie cuadrado metro cuadrado (m2) 0,0929
yarda cuadrada metro cuadrado (m2) 0,8361

Volumen (Capacidad)
onza centímetro cúbico (cm3) 29,57
galón metro cúbico (m3) ‡ 0,003785
pulgada cúbica centímetro cúbico (cm3) 16,4
pie cúbico metro cúbico (m3) 0,02832
yarda cúbica cúbico metro (m3) ‡ 0,7646
Fuerza

kilogramo-fuerza newton (N) 9,807
kip-fuerza newton (N) 4448
libra-fuerza newton (N) 4,448

Presión o Tensión
(fuerza por unidad de superficie)

kilogramo-fuerza /metro cuadrado pascal (Pa) 9,807
kip-fuerza/pulgada cuadrada (ksi) megapascal (MPa) 6,895
newton/metro cuadrado (N/m2) pascal (Pa) 1,000E
libra-fuerza/pie cuadrado pascal (Pa) 47,88
libra-fuerza/pulgada cuadrada (psi) kilopascal (kPa) 6,895

Momento Flector o Torque

libra-fuerza-pulgada newton-metro (Nm) 0,1130
libra-fuerza-pie newton-metro (Nm) 1,356
kilogramo-fuerza-metro newton-metro (Nm) 9,807

245

<!-- p. 22 -->

Para convertir de a multiplicar por
Masa
onza-masa (avoirdupois) gramo (g) 28,34
libra-masa (avoirdupois) kilogramo (kg) 0,4536
tonelada (métrica) megagramo (Mg) 1,000E
tonelada (corta, 2000 1bm) megagramo (Mg) 0,9072

Masa por unidad de volumen
libra-masa/pie cúbico kilogramo/metro cúbico (kg/m3) 16,02
libra-masa/yarda cúbica kilogramo/metro cúbico (kg/m3) 0,5933
libra-masa/galón kilogramo/metro cúbico (kg/m3) 119,8

Temperatura

grado Fahrenheit (F) grado Celsius (C) tC = (tF - 32)/1,8
grado Celsius (C) grado Fahrenheit (F) tF = 1,8tC + 32

\* Esta lista presenta los factores de conversión para las unidades utilizadas más
frecuentemente en la tecnología del hormigón. La fuente donde se puede obtener mayor
información sobre las unidades SI y factores de conversión más exactos es la publicación
ASTM E "Standard for Metric Practice".
† Indica que el factor dado es exacto.
‡ Un litro (decímetro cúbico) es igual a 0,001 m3 ó 1000 cm3.
§ Estas ecuaciones se usan para convertir una temperatura de una escala a otra e incluyen
las correcciones de escala correspondientes. Para convertir una diferencia de temperatura
de grados Fahrenheit a grados Celsius, sólo dividir por 1,8 − es decir, una variación entre
70 y 88 F representa una variación de 18 F ó 18/1,8 C = 10 C.

246
