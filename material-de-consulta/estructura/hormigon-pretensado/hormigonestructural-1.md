---
type: libro
title: "HormigonEstructural[1]"
author: "usuario"
categoria: "ESTRUCTURA"
paginas: 402
extraccion: "texto"
fuente: "local:E:/MATERIAL DE CONSULTA/ESTRUCTURA/HORMIGON PRETENSADO/HormigonEstructural[1].pdf"
convertido: 2026-10-16
---

# HormigonEstructural[1]

> Texto extraído de `ESTRUCTURA\HORMIGON PRETENSADO\HormigonEstructural[1].pdf` (402 páginas, texto). El PDF original está en el disco E: (MATERIAL DE CONSULTA); `<!-- p. N -->` marca el inicio de cada página.

<!-- p. 1 -->



<!-- p. 2 -->



<!-- p. 3 -->

HORMIGÓN ARMADO Y PRETENSADO

CONCRETO REFORZADO Y PREESFORZADO

<!-- p. 4 -->



<!-- p. 5 -->

ENRIQUE HERNÁNDEZ MONTES
LUISA MARÍA GIL MARTÍN

HORMIGÓN ARMADO Y PRETENSADO

CONCRETO REFORZADO Y PREESFORZADO

GRANADA
2007

<!-- p. 6 -->

Reservados todos los derechos. Los autores permiten la reproducción total o parcial
siempre que se mencione explícitamente la fuente. Está prohibido reproducir o
transmitir esta publicación, total o parcialmente, por cualquier medio si no se menciona
la fuente, bajo las sanciones establecidas por la ley.

© ENRIQUE HERNÁNDEZ MONTES
© LUISA MARÍA GIL MARTÍN
HORMIGÓN ARMADO Y PRETENSADO
\-CONCRETO REFORZADO Y PREESFORZADO-
Depósito Legal: GR-2974/2007. Edición en papel
Depósito Legal: GR-2975/2007. Edición electrónica
Edita: Grupo de Investigación TEP-190 Ingeniería e infraestructuras
Maquetación: Luis Pardo
Imprime: Gráficas Alhambra

Printed in Spain Impreso en España

<!-- p. 7 -->

A Nuestra Señora de las Angustias

A Enrique, Andrés y Luisa María

Violenti Rapiunt

<!-- p. 8 -->



<!-- p. 9 -->

Estimado amigo:

El libro que te presentamos, con el título “Hormigón Armado y
Pretensado –Concreto Reforzado y Preesforzado-“ corresponde al libro de texto
de la asignatura del mismo nombre en la Escuela de Ingenieros de Caminos,
Canales y Puertos de la Universidad de Granada, España. Si bien ha sido
enriquecido tratando de responder a las dudas que nos han surgido durante
nuestros años docentes. Este libro pretende ser un tratado general de cálculo de
estructuras de hormigón armado y pretensado, por eso se han obviado temas
como soluciones constructivas y detalles, que se pueden consultar en otros
volúmenes existentes en el mercado y en proyectos constructivos.

Hoy día, debido a la facilidad de cálculo asociada con el desarrollo de la
informática, el uso de tablas y reglas simplificadas está en desuso. De hecho,
actualmente es inconcebible abordar el cálculo de una estructura sin la ayuda de
un programa de ordenador adecuado. En este contexto, este libro pretende
aumentar el conocimiento teórico del ingeniero y del alumno de ingenieríateniendo como base una importante carga teórica y conceptual.

Aunque generalmente se utiliza la normativa española (EHE) y la
europea (Eurocódigo-2), en general el texto no se ciñe a una norma específica,
haciéndose mención, por su interés práctico en casos concretos, a otras normas
como la americana ACI-318 o la suiza SIA-165 -entre otras-.

Nuestro agradecimiento a los profesores que en mayor o menor medida
han colaborado en la edición de este libro, especialmente a: Mark Aschheim de
la Universidad de Santa Clara (California), Luis Albajar Molera de la UPM,
Rafael Gallego Sevilla y Miguel Losada Rodríguez, ambos de la UGR, a
Stravoula Pantazopoulous de la Universidad de Tracia y a Daniel Kuchma de la
Universidad de Illinois U-C.

Especial agradecimiento a las empresas y asociaciones que han
colaborado y sin cuya financiación no hubiésemos extendido este trabajo a
todas la Escuelas de Ingenieros de Caminos de España, para cuyos alumnos de
la signatura de hormigón armado, este volumen será gratuito los próximos dos
años. Además está disponible en red para cualquier persona que lo desee. Estas
empresas son:

SACYR, JOCA, AZVI, PROINTEC, HOLCIM, DETECSA, ORTIZ
Construcciones, BRUES Y FERNÁNDEZ, GARASA, IECA y CHM.

Los autores.
Granada, Diciembre de 2007

<!-- p. 10 -->



<!-- p. 11 -->

HORMIGÓN ESTRUCTURAL
Hernández-Gil

ÍNDICE

\1. PRINCIPIOS FUNDAMENTALES

1.1. Introducción 15
1.2. El hormigón armado y pretensado como material
de construcción 16
1.3. Normativa 23

Ejercicios propuestos
Referencias

\2. PROCEDIMIENTOS GENERALES DE CÁLCULO

2.1. Métodos probabilistas y métodos deterministas 27
2.2. El método de los estados límite 28
2.3. Durabilidad 36

Referencias

\3. DESCRIPCIÓN Y CARACTERÍSTICAS DEL HORMIGÓN Y DEL ACERO

3.1. El Hormigón o Concreto 45
3.2. Propiedades mecánicas del hormigón 49
3.3. Diagramas tensión-deformación 51
3.3.1. Diagramas para el cálculo estructural
3.3.2. Resistencia de cálculo del hormigón
3.3.3. Diagramas para el diseño en rotura de secciones
3.4. Fluencia 60
3.5. Retracción 64
3.6. Otras propiedades del hormigón 69
3.7. Armadura pasiva 72
3.8. Anclaje 75
3.9. Armadura activa 78
3.10. Relajación 83
3.11. Fatiga 85

Ejercicios propuestos
Referencias

Anejo: Modelo de arcos de descarga de hormigón confinado 89

Referencias
Ejemplo

<!-- p. 12 -->

HORMIGÓN ESTRUCTURAL
Hernández-Gil

\4. LA FUERZA DE PRETENSADO (20)

4.1. Las pérdidas de pretensado 103
4.2. Pérdidas por rozamiento 103
4.3. Geometría del postesado 106
4.4. Pérdidas por penetración en cuña 110
4.5. Pérdidas por acortamiento elástico 116
4.6. Pérdidas diferidas 120

Ejercicios propuestos
Referencias

\5. MÉTODO DE LAS BIELAS Y TIRANTES
5.1. Regiones B y D 125
5.2. Modelos de Bielas y Tirantes 128
5.3. Bielas y Tirantes 131
5.4. Unicidad de los Modelos de Bielas y Tirantes 132
5.5. Proceso de diseño 133

Ejemplo en hormigón armado
Ejemplo en hormigón pretensado
Referencias

\6. ANÁLISIS DE LA SECCIÓN EN FLEXIÓN

6.1. Introducción 151
6.2. Hipótesis fundamentales a nivel sección 154
6.3. Comportamiento del hormigón a tracción 157
6.4. Ejemplo de respuesta a corto y largo plazo 159
6.5. Aproximación lineal para la fase de prefisuración 165
6.6. Agotamiento frente a solicitaciones normales 172
6.7. Flexión simple y flexión compuesta uniaxial 187
6.7.1. Comprobación
6.7.2. Dimensionamiento
6.8. Flexión biaxial 200
6.8.1. Comprobación
6.8.2. Dimensionamiento
6.9. Disposiciones geométricas y cuantías mínimas en armaduras
longitudinales 207

Ejercicios propuestos
Referencias

\7. CORTANTE

7.1. Introducción 219
7.2. Esfuerzo cortante efectivo 223
7.3. Distribución de tensiones en el hormigón 225

<!-- p. 13 -->

HORMIGÓN ESTRUCTURAL
Hernández-Gil

7.4. Grietas de cortante 227
7.5. Planteamiento en la normativa actual 229
7.6. Comportamiento del hormigón agrietado.
Analogía de la celosía. 231
7.7. Interacción flexión-cortante 247
7.8. Punzonamiento 252

Ejercicios propuestos

Anejo. Teorías del campo de compresiones 255

Ejercicios propuestos
Referencias

\8. TORSIÓN

8.1. Introducción 275
8.2. Torsión en pre-fisuración 276
8.3. Torsión en post-fisuración y rotura 280
8.4. Interacción entre torsión y otros esfuerzos 284

Ejercicios propuestos
Referencias

\9. ANÁLISIS ESTRUCTURAL

9.1. Introducción 293
9.2. Tipos de análisis estructural 295
9.3. Análisis en segundo orden 302
9.4. Métodos aproximados de cálculo en segundo orden 311
9.4.1. Método basado en la rigidez nominal
9.4.2. Método basado en la curvatura nominal
9.5. Flexión compuesta esviada 323
9.6. Pilares zunchados 326

Ejercicios propuestos
Referencias

\10. ESTADOS LÍMITE DE SERVICIO

10.1. Introducción 331
10.2. Limitaciones a la deformación 332
10.3. Deformación. Método general 332
10.4. Método simplificado de cálculo de deformaciones
de la EHE 344
10.5. Estado límite de fisuración 351
10.6. Estado límite de vibraciones 357

<!-- p. 14 -->

HORMIGÓN ESTRUCTURAL
Hernández-Gil

Ejercicios propuestos
Referencias

\11. DISEÑO DE ELEMENTOS

11.1. Introducción 359
11.2. El proceso de diseño 362
11.3. Secciones compuestas 368

Ejercicios propuestos
Referencias

\12. ESTRUCTURAS HIPERESTÁTICAS

12.1. Introducción 379
12.2. Redistribución de esfuerzos 380
12.3. Momentos primarios y momentos secundarios 381
12.4. Diseño del trazado del tendón 393

Referencias
Tablas 399

<!-- p. 15 -->

HORMIGÓN ESTRUCTURAL 15
Hernández-Gil

CAPÍTULO I

PRINCIPIOS FUNDAMENTALES

Viaducto Arroyo del Valle. España.
Cortesía de Grupo AZVI. www.azvi.es

1.1. INTRODUCCIÓN

El objetivo de este libro es lograr que el estudiante alcance un conocimiento de los
principios básicos del hormigón armado y pretensado. Dado que actualmente el hormigón es
el material de construcción más extendido, estos principios básicos han de ser conocidos por
arquitectos e ingenieros.

Se entiende por hormigón estructural, también denominado hormigón armado y/o
pretensado, a la disciplina que estudia el empleo del hormigón en elementos estructurales.
Para este fin, como veremos más adelante, será necesario el uso del hormigón combinado
con barras de acero.

<!-- p. 16 -->

PRINCIPIOS FUNDAMENTALES 16

El conocimiento de la forma de trabajar del hormigón estructural hace que el
ingeniero o arquitecto pueda emplear el hormigón, un material frágil cuya resistencia a
tracción es muy pequeña, para construir elementos estructurales resistentes y dúctiles.

Debido al avance que han experimentado las posibilidades de cálculo, las tablas y
manuales han sido sustituidos por programas informáticos. Estos medios han permitido al
ingeniero mayor capacidad y libertad en el diseño estructural. Por otra parte, los tipos de
hipótesis en el análisis se han visto incrementados: análisis no lineal, análisis dinámico,
etc… Esta mayor capacidad hace que los técnicos tengan necesidad de un conocimiento
más profundo de las hipótesis y los modelos empleados en el hormigón estructural y una
menor preocupación en relación a los métodos de cálculo numérico.

El hormigón es un material heterogéneo que además retrae, fluye y se agrieta, de tal
forma que sus tensiones no pueden ser conocidas con exactitud. En general, como veremos a
lo largo de este libro, las ecuaciones de diseño están basadas en conceptos básicos de la
ingeniería mecánica y de la estática junto con términos deducidos empíricamente.

1.2. EL HORMIGÓN ARMADO Y PRETENSADO COMO MATERIAL DE
CONSTRUCCIÓN

El hormigón por si solo es un material que resiste bien a compresión (en torno a 30
N/mm2 o MPa) aunque menos que el acero (que su resistencia a compresión está en torno a
400 N/mm2) e incluso menos que la madera. Una característica del hormigón es su baja
resistencia a tracción, del orden de 10 veces menor que la resistencia a compresión,
hablando en términos poco precisos.

Consideremos la viga fabricada exclusivamente con hormigón (sin acero) de la
figura 1.1). El valor máximo de la carga (q) que puede resistir la viga será aquella que
origine una tensión de tracción igual a la resistencia a tracción del hormigón. Cuando esta
carga se alcance la viga colapsará sin previo aviso.

<!-- p. 17 -->

HORMIGÓN ESTRUCTURAL 17
Hernández-Gil

q
Sección
transversal

h

b

L

Diagrama de tensiones
normales en la sección
transversal a centro de luz

Figura 1.1. Viga de hormigón

En la viga de la figura 1.1 la rotura se producirá en las fibras inferiores, pues es en
ellas donde se experimentan las máximas tracciones. Podemos fácilmente intuir que, en
general, el empleo de hormigón sin armadura (hormigón en masa) no es adecuado. En el
elemento estructural de la figura 1.1 se está desaprovechando la capacidad de trabajo del
hormigón a compresión ya que éste podría resistir tensiones mucho mayores. Además se
está confiando en la capacidad de trabajo del hormigón a tracción que, dado que no se puede
garantizar que el hormigón no tenga grietas que lo incapaciten para resistir esta solicitación,
es muy poco fiable.

Para mejorar los inconvenientes antes descritos se plantea la necesidad de
introducir un material que resista a tracción lo que el hormigón no puede: el acero. Este
material añadido debe colocarse en las zonas donde es más necesario (figura 1.2) o sea,
donde se desarrollan las tracciones. Al conjunto de ambos materiales trabajando de esta
forma se le denomina hormigón armado.

<!-- p. 18 -->

PRINCIPIOS FUNDAMENTALES 18

q

Diagrama de tensiones
normales en la sección
transversal a centro de luz

Figura 1.2. Viga de hormigón con acero en la zona de tracción

Como se verá más adelante, salvo excepciones, no se considera la colaboración del
hormigón a tracción, tal y como se aprecia en el diagrama de tensiones normales de la figura
1.2.

Puesto que sobre la viga de la figura 1.2 no actúa ningún esfuerzo axil (flexión
simple), en toda sección transversal se debe cumplir que la resultante de las compresiones
iguale a la resultante de las tracciones:

s dAs ∫ σ c dAc = ∫ σ
Zona Zona
Comprimida Traccionad a

donde σc es la tensión en el hormigón (el subíndice c proviene de la palabra inglesa
concrete), σs es la tensión del acero (el subíndice s proviene de la palabra inglesa steel), y
dAc y dAs son las diferenciales de área de hormigón y de acero respectivamente.

Con la aparición en el mercado aceros de alto límite elástico, aceros cuya
resistencia a tracción es muy elevada (en torno a 2000 N/mm2), se plantea la posibilidad de
su empleo junto con el hormigón. Para ambos aceros, el de alto y bajo límite elástico, el
módulo de elasticidad es siempre aproximadamente el mismo, Es =200000 N/mm2, lo que
implica que pasar de una tensión inicial de 0 a una tensión igual a su resistencia máxima
requiere una deformación grande en el acero de alto límite elástico. Por tanto, si se pretende
emplear este tipo de acero para armar una viga, tal como se indica en la figura 1.2, el
hormigón se agrietará exageradamente y aparecerán grandes deformaciones antes de
alcanzar tensiones próximas a su máxima capacidad. Trabajar a resistencias máximas con
acero de alto límite elástico sólo es posible si éste es introducido en el hormigón con una
predeformación (o tensión inicial, denominada pretensado). Con esta técnica es posible que,
para deformaciones pequeñas o nulas, el acero trabaje a tensiones cercanas a su tensión

<!-- p. 19 -->

HORMIGÓN ESTRUCTURAL 19
Hernández-Gil
máxima. En la figura 1.3 se representan los diagramas de tensiones normales debidas al
efecto del pretensado, suponiendo en la sección transversal situada en el centro de luz el
acero (cable de pretensado) está sometido a una carga axil de valor N.

q

e

N

Diagrama de tensiones normales en la
sección transversal a centro de luz,
debidas al axil N y al momento N·e

Figura 1.3. Viga de hormigón con acero pretensado

Si al estado de tensiones inicial, debido al pretensado -fuerza del axil N y momento
N·e - , se le suman las tensiones correspondientes al momento flector generado por la carga
q, tenemos:

Estado final

Figura 1.4. Estado de tensiones en la viga pretensada

Se puede observar que el estado de tensiones final (o en carga) , representado en la
figura 1.4, presenta tensiones menores que el estado de tensiones inicial (o descargado) de
la figura 1.3.

Este nuevo tipo de hormigón estructural se denomina hormigón pretensado. Es
interesante señalar que cuando un hormigón armado se desencofra (el enconfrado es el
sustento necesario hasta que endurezca) las barras de acero quedan traccionadas mientras
que, en la zona de compresiones, el hormigón queda comprimido. Así pues, tanto en el
hormigón armado como en el pretensado, el acero quedará finalmente tensado.

A la armadura propia del hormigón armado se le denomina armadura pasiva y a la
propia del hormigón pretensado se le denomina armadura activa.

<!-- p. 20 -->

PRINCIPIOS FUNDAMENTALES 20

Particularidades del material compuesto

El material compuesto hormigón-acero posee algunas características especiales
debido a su relación sinérgica que van más allá de la introducción que acabamos de hacer,
puramente mecanicista.

La primera gran ventaja es que el hormigón genera cal libre durante su fraguado y
endurecimiento, Ca(OH)2, lo que hace que tenga un pH muy elevado (≅12). Este ambiente
alcalino protege al acero de un posible proceso de corrosión.

El acero, que de por sí es muy vulnerable frente a la acción del fuego, está
recubierto por una capa de hormigón que le confiere un gran aislamiento. El efecto es que el
conjunto puede permanecer expuesto a grandes temperaturas durante horas sin que su
capacidad mecánica se vea alterada.

Con el paso del tiempo, y debido a que el hormigón es poroso, el CO2 del aire
penetra por los poros del hormigón reaccionando con la cal libre y despasivizando el medio
(proceso de carbonatación). Este fenómeno es el principal causante de la degradación del
hormigón pues deja expuesto al acero frente a la corrosión. Durante este proceso el
hormigón se carbonata. La superficie que separa la masa de hormigón carbonatado de la que
no lo está se denomina frente de carbonatación.

Las contaminaciones del hormigón por sales de cloro (Cl-) crean un efecto parecido
al descrito anteriormente; estas sales pueden provenir del agua, de los áridos, o aparecer con
posterioridad a la fabricación del hormigón ( p.ej. uso de sales de deshielo en carreteras).

La tracción absorbida por las barras de acero será trasmitida al hormigón mediante
tensión cortante (fricción) a lo largo del perímetro de las barras de acero. Para asegurar la
transmisión de estas tensiones de cortante se necesita garantizar una buena adherencia entre
hormigón y acero. Esta adherencia queda garantizada por varios mecanismos. El primero de
estos mecanismos es de naturaleza físico-química, su origen está en la interfase hormigónacero que se produce en el contacto de ambos. El segundo mecanismo se debe al hecho de
que el hormigón retrae al endurecer, lo que provoca un mejor agarre de las armaduras. El
tercer mecanismo es un mecanismo forzado: las barras de las armaduras pasivas, que son las
empleadas en hormigón armado, están fabricadas con corrugas que mejoran la adherencia.

En relación con el hormigón pretensado, existen dos grandes diferencias técnicas
dependiendo de si la tensión en el acero se introduce antes o después del endurecimiento del
hormigón (hormigón preteso y posteso, respectivamente). En elementos pretesos, el acero se
tensa dentro del molde del elemento, posteriormente se hormigona y una vez endurecido se
liberan los extremos de los cables. En estas estructuras el trazado del cable debe de ser
rectilíneo. En el caso de estructuras postesas, en el interior de la masa de hormigón se

<!-- p. 21 -->

HORMIGÓN ESTRUCTURAL 21
Hernández-Gil
colocan unos conductos o vainas por los que,, una vez endurecido el hormigón, se procede a
introducir los cables de pretensado para su posterior tesado. El trazado de los cables en estas
últimas estructuras puede ser curvo.

De lo anteriormente expuesto se puede intuir que la transmisión de las tracciones
del acero al hormigón en elementos de hormigón pretensado es más compleja que en el caso
del hormigón armado. Como ya comentamos, el acero de pretensar alcanza tracciones
mucho mayores que el acero de armar. La solución a este problema ha generado grandes
diferencias entre distintos sistemas ideados para realizar dicha transmisión existiendo
numerosos sistemas de pretensado (tanto posteso como preteso) y múltiples patentes.

Con la técnica del hormigón armado las luces que se pueden salvar en una viga
horizontal son muy limitadas. Las grandes luces en hormigón armado se consiguen
mediante estructuras cuya geometría obliga a que las secciones trabajen fundamentalmente a
compresión, siendo los esfuerzos de flexión muy limitados, tal es el caso de los arcos. Un
gran maestro en el arte de sacar al hormigón armado su máximo partido fue D. Eduardo
Torroja. Las figuras 1.5 y 1.6 corresponden a dos de sus obras: El Frontón de Recoletos
(figura 1.5) - destruido durante la Guerra Civil Española - y El Viaducto Martín Gil (figura
1.6), obra muy singular debido a que la armadura pasiva hizo de sustento del encofrado.

<!-- p. 22 -->

PRINCIPIOS FUNDAMENTALES 22

Figura 1.5. Frontón de Recoletos. Cortesía de la familia Torroja.

Figura 1.6. Viaducto Martín Gil. Cortesía de la familia Torroja.

La técnica del hormigón pretensado permite salvar mayores luces y, de hecho, en la
mayoría de los puentes de grandes vanos construidos hoy día se emplea hormigón

<!-- p. 23 -->

HORMIGÓN ESTRUCTURAL 23
Hernández-Gil
pretensado. En la figura 1.7 podemos ver un puente fabricado con hormigón pretensado
posteso.

Figura 1.7. Puente de Huétor-Santillán.

1.3. NORMATIVA

El uso del hormigón en la sociedad es de tal importancia que los modelos de
comportamiento del hormigón y del acero, las hipótesis de cálculo y su rango de aplicación
están normalizados.

En Europa es de aplicación el Eurocódigo 2 para hormigón estructural y el Eurocódigo
1 para el estudio de las cargas sobre las estructuras. En España la norma vigente es la
Instrucción de Hormigón Estructural (EHE). En la parte dedicada a hormigón estructural la
EHE y el Eurocódigo 2 son similares aunque en algunos casos existen diferencias
apreciables, debido sobre todo a la tradición tecnológica de nuestro país.

Una obra interesante desde el punto de vista técnico es el Código Modelo CEB-FIP
(Comité Euro-Internacional del Hormigón - Federación Internacional del Pretensado. Esta
obra, cuya última versión es de 1990, es un compendio de la tecnología del hormigón
estructural y constituye una fuente para las normativas nacionales.

<!-- p. 24 -->

PRINCIPIOS FUNDAMENTALES 24

En el caso arquitectos e ingenieros especialistas en estructuras es interesante y
recomendable el conocimiento de las normativas de otros países, en especial la norma
americana ACI-318, editada por el American Concrete Institute en inglés y en español.

Denominación básica

En la norma española si el hormigón no contiene armadura se le denomina hormigón
en masa (HM), si su armadura está constituida exclusivamente por armadura pasiva se
denomina hormigón armado (HA) y si existe armadura activa se llama hormigón pretensado
(HP). En la nomenclatura del Eurocódigo 2 no existe esa diferencia y al hormigón
estructural se le nombra con la letra C.

<!-- p. 25 -->

HORMIGÓN ESTRUCTURAL 25
Hernández-Gil
Ejercicios propuestos

\1. ¿Dónde rompería una viga pretensada como la de la figura 1.3 si la fuerza de
pretensado fuese excesivamente grande y no estuviera sometida más que a la
acción de su peso propio?.

\2. En las vigas como la de la figura 1.2 las barras de armadura que se colocan en
la parte inferior se denominan positivos. Si las barras se colocan en la parte
superior de la viga se denominan negativos. ¿Tiene esto algo que ver con el
signo de los momentos flectores?.

\3. Considérese una viga continua de tres vanos ¿en qué partes se necesitaría
armadura y en cuales no?, dicho de otra forma ¿dónde se colocarían los
positivos y dónde los negativos?.

Referencias

Jiménez Montoya P., García Meseguer A. y Morán Cabré F. (1994). Hormigón Armado.
Editorial Gustavo Gili. Barcelona.

Páez, Alfredo (1986). Hormigón Armado, tomo 1. Editorial Reberté. Barcelona

Torroja Miret E., (1991). Razón y ser de los tipos estructurales. Consejo Superior de
Investigaciones Científicas. Instituto de Ciencias de la Construcción “Eduardo Torroja”.

<!-- p. 26 -->

PRINCIPIOS FUNDAMENTALES 26

<!-- p. 27 -->

HORMIGÓN ESTRUCTURAL 27
Hernández-Gil

CAPÍTULO II

PROCEDIMIENTOS GENERALES DE CÁLCULO

Carga móvil de ferrocarril sobre una estructura.
Cortesía de PROINTEC S.A. www.prointec.es

2.1. DESCRIPCIONES PROBABILISTAS Y DETERMINISTAS

Cuando se acomete el cálculo de una estructura con objeto de dimensionarla
existen algunos datos que es necesario conocer: acciones, propiedades de los materiales,
condiciones ambientales y geometría. En relación al valor de cada uno de estos datos
caben dos posibilidades:

\- suponer que sus valores son conocidos y únicos, o bien
\- suponer que el valor de cada uno o conjunto de ellos tiene asociada una
cierta distribución estadística.

El primero de los planteamientos se conoce como determinista. Los
planteamientos deterministas fueron adoptados por las primeras normas de hormigón,
de manera que partiendo de unos valores determinados en los datos de entrada se

<!-- p. 28 -->

PROCEDIMIENTOS GENERALES DE CÁLCULO 28

realizaba todo el cálculo estructural. Al final del proceso de cálculo se comparaba el
resultado de algunos valores obtenidos con los que se consideraban valores admisibles
de estos resultados. P.ej. las tensiones obtenidas en el cálculo se comparaban con lo que
se denominaban tensiones admisibles, siendo en éstas donde se introducía el coeficiente
de seguridad, asociado a la incertidumbre inherente al proceso.

σmax σadmisible =
γ

El segundo de los planteamientos es mucho más realista y consiste en asignar a
cada una de las variables del proceso una función de densidad y obtener la garantía de
funcionamiento de la estructura en términos de probabilidad.

Un planteamiento intermedio a los anteriores es el método de los estados
límites. En este método se fijan una serie de estados que la estructura, durante un
tiempo determinado, no debe sobrepasar para garantizar una determinada funcionalidad.
A ese intervalo de tiempo se le conoce como vida útil de la estructura.

2.2. EL MÉTODO DE LOS ESTADOS LÍMITES

Cuando se proyecta y construye una estructura se debe hacer de forma que
durante la vida útil estimada se mantenga en las condiciones de uso requeridas, tanto
durante su construcción como durante su uso, sin que ello requiera operaciones más
complicadas que un simple mantenimiento. A lo largo de esta vida útil pueden aparecer
distintas situaciones en función de su duración en el tiempo denominadas situaciones de
proyecto:

\- situaciones persistentes o definitivas
\- situaciones transitorias o provisionales
\- situaciones accidentales
\- situaciones sísmicas

Durante todas estas situaciones hemos de garantizar que no se alcanzará ningún
ESTADO LÍMITE, definidos como aquellos a partir de los cuales la estructura no
satisface los requerimientos de seguridad y de funcionalidad para los que había sido
proyectada.

Los estados límite se agrupan en los dos siguientes:

\1. Estados límite últimos (ELU): Asociados al colapso o a otra forma de
fallo similar de la estructura, parte de ella, o a la seguridad de personas.
Los estados límites últimos, según la norma española de hormigón EHE,
se producen cuando el fallo se presenta por:

\- Pérdida de estabilidad
\- Solicitaciones normales
\- Cortante

<!-- p. 29 -->

HORMIGÓN ESTRUCTURAL 29
Hernández-Gil
\- Torsión
\- Punzonamiento
\- Deformaciones estructurales (pandeo)
\- Fatiga

\2. Estados límite de servicio (ELS): Asociados a la falta de servicio en
funcionalidad, comodidad o apariencia estética de la estructura. Los
estados límite de servicio pueden ser reversibles o irreversibles. Los
estados límites de servicio en hormigón son:

\- de limitación de tensiones bajo condiciones de servicio
\- de fisuración
\- de deformación

El método de los estados límites centra su estudio sobre las acciones y sobre las
características de los materiales. La durabilidad de la estructura es un supuesto de
proyecto, lo que quiere decir que se supone que los materiales de la estructura
permanecerán en perfecto estado durante su vida útil. Para garantizar esto último, se
tomarán medidas paliativas en función del tipo de ambiente en el que se encuentre y se
asegurará la calidad durante todo el proceso constructivo.

Se supone que las hipótesis de cálculo establecidas para el análisis estructural
son apropiadas para predecir el comportamiento estructural y los estados límites
considerados. El método de los estados límites está basado en el principio de
superposición y, por tanto, todo análisis estructural cuyas hipótesis no verifiquen el
principio de superposición (como puede ser el caso del estudio de estabilidad de pilares)
no es compatible, en principio, con el método de los estados límites.

Las acciones sobre una estructura se pueden clasificar atendiendo a varios
criterios:

\- Por su forma de aplicación: directas (cargas) o indirectas (deformaciones
impuestas, acciones térmicas, ..).
\- Según su variación en el tiempo:
\- G permanentes: como el peso propio o los elementos
permanentes.
\- Q variables: como la sobrecarga de uso, el viento o la
nieve.
\- A accidentales: como explosiones o impactos de
vehículos
\- Por su variación espacial: fijas o libres.
\- Por su naturaleza o respuesta estructural: estáticas o dinámicas.

Valores característicos, valores representativos y valores de cálculo

Un concepto muy importante en el método de los estados límites es el de valor
característico, tanto para las acciones como para los materiales. El concepto de valor

<!-- p. 30 -->

PROCEDIMIENTOS GENERALES DE CÁLCULO 30

característico está ligado a la distribución estadística que presenta el valor en cuestión,
denominándose valor característico aquel que más interese destacar dentro de la
distribución estadística. Algunas veces el valor característico corresponderá al valor
medio y en otras ocasiones será el asociado a un percentil determinado de la
distribución estadística.

Materiales

En relación a los materiales, desde el punto de vista del método de los estados
límites, caben dos posibilidades: referirse a situaciones de resistencia última
(relacionadas con los ELU) o bien referirse a situaciones de limitación de
deformaciones (relacionadas con los ELS). Según se trate de un caso u otro, el valor
característico de los materiales será conceptualmente diferente y el nivel de seguridad
requerido en el cálculo también será diferente.

Consideremos un ejemplo: si se pretende estudiar la deformación de una viga
de hormigón lo que interesa es considerar el valor medio del módulo de deformación ya
que en el cálculo de la deformación de ésta interviene todo el hormigón que la
compone. Por el contrario, si lo que se pretende es estudiar la resistencia a rotura de la
viga será conveniente tener en cuenta el valor de la resistencia del hormigón
correspondiente a un percentil determinado ya que la rotura se producirá por el punto
más débil.

En el caso de las resistencias últimas de los materiales, se supone que sus
valores siguen una distribución normal. El valor característico de la resistencia última
será el que presente una garantía del 95% (sólo el 5% de las probetas ensayadas tendrán
una resistencia menor a la característica):

f k = f m − 1 . 65σ

donde fm es el valor medio y σ es la desviación estándar.

En cuanto a parámetros relativos a la rigidez de los materiales, necesarios para
medir deformaciones, el valor característico será su valor medio, ya que la deformación
vendrá dada con mayor exactitud por el valor medio que por el del cuantil del 0.95.

Como ya hemos dicho, el valor característico de la propiedad de un material es
aquel valor que es más interesante resaltar (Xk). No obstante, cuando se introduce en el
cálculo es necesario aplicarle un coeficiente de seguridad con objeto de garantizar que
no se va a sobrepasar en los ELU y que los ELS van a ser calculados con exactitud. Con
este objeto se introduce el coeficiente parcial de la propiedad del material: γM.

Se denomina valor de cálculo de la propiedad de un material al valor Xd:

X k X d =
γM

<!-- p. 31 -->

HORMIGÓN ESTRUCTURAL 31
Hernández-Gil
Los coeficientes parciales de seguridad para ELU de las propiedades de los
materiales según la EHE y el EC2 se recogen en la tabla 2.1.

Tabla 2.1. Coeficientes parciales de seguridad de materiales

Situación de proyecto Hormigón Acero pasivo y activo
γc γs
Persistente o transitoria 1.5 1.15
Accidental 1.3 1.0

Obviamente el valor del coeficiente parcial de seguridad en hormigón es mayor
que en acero puesto existe mayor desviación de la media en su valor característico. Si
los valores característicos de resistencia son de 30 MPa para un hormigón y de 500
MPa para un acero, sus correspondientes valores de cálculo -en situaciones persistentesserán de 20 y 435 MPa, respectivamente. Esto significa que, debido al proceso de
fabricación, se tiene la misma garantía de que el acero de 500 MPa no supere el valor
de 435 MPa como de que un hormigón de 30 MPa no supere 20 MPa.

Para los ELS se tomará γM=1.

Acciones

En el caso de las acciones el valor característico depende del tipo de acción
considerada, pudiendo ser el valor medio, un valor superior, un valor inferior o un valor
nominal.

En el caso de acciones permanentes:

\- si su variación es pequeña se suele usar un único valor Gk
\- si su variabilidad es grande se suelen usar dos valores característicos
Gk,inf y Gk,sup, asociados al cuantil del 5% y del 95% respectivamente.

En el caso de acciones variables, en la definición de su valor característico se
usan niveles de confianza del 2% y del 98% para Qk,inf y Qk,sup respectivamente, o bien
su valor medio.

Se denomina valor representativo de una acción al valor adoptado como carga
sobre la estructura, en general este valor será el valor característico y, de hecho, para las
cargas permanentes el valor característico y el representativo coinciden. Cuando se
consideran numerosas cargas o combinaciones de cargas sobre una estructura la
probabilidad de que aparezcan todas simultáneamente disminuye. Por ejemplo: sobre un
puente actúan varias cargas variables: el tráfico, la nieve, el viento, las cargas térmicas,
... pero la probabilidad de que todas actúen a la vez es menor que la de que actúen sólo
algunas de ellas y, por tanto, es lógico considerar sólo fracciones de las cargas variables
cuando actúen a la vez. Considerar combinación de acciones implica tener en cuenta
que es poco probable la actuación simultánea de todas ellas, lo que se realiza mediante

<!-- p. 32 -->

PROCEDIMIENTOS GENERALES DE CÁLCULO 32

los coeficientes de compatibilidad Ψ. Así pues, aparecen tres valores representativos de
las acciones variables:

Ψ0Qk el valor de combinación
Ψ1Qk el valor frecuente (ligado a una parte de tiempo del 5%)
Ψ2Qk el valor cuasipermanente (ligado a una parte del tiempo del 50%)

Los valores de Ψ dependerán de cada normativa. En la tabla 2.2 se indican los
valores establecidos por el EC-1 para estructuras de edificación.

Tabla 2.2. Coeficientes Ψ para edificación, según EC-1

Acción Ψ0 Ψ1 Ψ2
Carga exterior en:
A.- Edificios domésticos 0.7 0.5 0.3
B.- Oficinas 0.7 0.5 0.3
C.- Áreas de reunión 0.7 0.7 0.6
D.- Comercios 0.7 0.7 0.6
E.- Almacenes 1.0 0.9 0.8
Carga de tráfico:
\- vehículo ≤ 30kN 0.7 0.7 0.6
\- vehículo entre 30 y 160 kN 0.7 0.5 0.3
\- cubiertas 0 0 0
Nieve 0.6 0.2 0
Viento 0.6 0.5 0
Térmicas (no fuego) 0.6 0.5 0

Hasta ahora se ha hablado de valor característico: el más idóneo, y de valor
representativo: para tener en cuenta el carácter de ocurrencia simultánea. El siguiente
paso es establecer el nivel de seguridad o coeficiente de seguridad que, en el caso de las
acciones, se lleva a cabo mediante el coeficiente parcial de la acción: γF.

Se denomina valor de cálculo (también denominado valor de diseño) de una
acción al valor Fd:

Fd = γF Ψi FK

El valor de γF además tiene en cuenta si el efecto de la acción sobre la
estructura es favorable o desfavorable, según sea este efecto γF tomará diferentes
valores. El valor de γF establecido por la EHE viene recogido en la tabla 2.3. Estos
valores pueden ser modificados en función del nivel de control en la ejecución de la
obra, ver tabla 2.4.

<!-- p. 33 -->

HORMIGÓN ESTRUCTURAL 33
Hernández-Gil
Tabla 2.3. Coeficientes parciales de seguridad para las acciones

TIPO DE ACCIÓN Situación persistente o Situación accidental
transitoria
Efecto Efecto Efecto Efecto
favorable desfavorable favorable desfavorable
Permanente γG=1.00 γG=1.35 γG=1.00 γG=1.00
Pretensado γP=1.00 γP=1.00 γP=1.00 γP=1.00
Permanente de γG*=1.00 γG*=1.50 γG*=1.00 γG*=1.00
valor no constante
Variable γQ=0.00 γQ=1.50 γQ=0.00 γQ=0.00
Accidental - - γA=1.00 γA=1.00

Tabla 2.4. Correcciones según el nivel de control de ejecución

TIPO DE ACCIÓN Nivel de control de ejecución
Intenso Normal Reducido
Permanente γG=1.35 γG=1.50 γG=1.65
Pretensado γP=1.00 γP=1.00 -
Permanente de γG*=1.50 γG*=1.60 γG*=1.80
valor no constante
Variable γQ=1.50 γQ=1.60 γQ=1.80

Combinación de acciones para verificar los Estados Límites

Una vez conocidas todas las acciones a las que está sometida la estructura y sus
valores de cálculo, los valores de cálculo de las propiedades de los materiales, los datos
geométricos y decidido el tipo de análisis estructural se pueden comprobar cada uno de
los Estados Límites. Este nuevo paso consiste en verificar que no se sobrepasa ninguno
de los estados límites durante la vida útil de la estructura. Para ello hay que considerar
todas las formas posibles en que las acciones pueden actuar sobre la estructura
(combinaciones) durante la vida de la estructura (situaciones de proyecto).

El método de los estados límites plantea una serie de combinaciones de
acciones que tienen en cuenta la probabilidad de que se presente una determinada
situación de proyecto junto con la probabilidad de que las acciones actúen
simultáneamente. Se establecen así unas determinadas combinaciones de acciones para
cada situación de proyecto.

Sean E los efectos de las acciones (p.ej. esfuerzos en barras, tensiones,
deformaciones y desplazamientos) y R la resistencia de la estructura, cuyos valores de
cálculo son:

<!-- p. 34 -->

PROCEDIMIENTOS GENERALES DE CÁLCULO 34

Ed = E ( Fd 1 , Fd 2 , ... ad 1 , ad 2 , ... X d 1 , X d 2 , ... )
1442443 1442443 1442443
acciones geometría materiales
Rd = R ( ad 1 , ad 2 , ... X d 1 , X d 2 , ... )

donde:

Fdi son las acciones
adi los datos geométricos de la estructura
Xdi las acciones sobre la estructura

Para verificar los estados límites últimos se debe de cumplir:

\- Equilibrio estático:

Ed , dst ≤ Ed , stb

Ed,dst es el valor de cálculo de los efectos desestabilizadores de las acciones
Ed,stb es el valor de cálculo de los efectos estabilizadores de las acciones

Un ejemplo de esto puede verse en el muro de contención de tierras de la figura
2.1. No sólo hay que garantizar que el muro no rompe sino que éste tampoco puede
deslizar o volcar si se quiere asegurar la funcionalidad de la estructura.

Figura 2.1. Pérdida de estabilidad en un muro de contención de tierras.

\- Estado límite de rotura o deformación excesiva

E d ≤ Rd

Para cada estado límite último (excepto para fatiga) el valor de Ed debe de ser
calculado para las siguientes situaciones de proyecto:

Para situaciones persistentes y transitorias de proyecto:

Qki ∑γGj Gkj + γP Pk + γQ1Qk 1 + ∑γQi Ψ 0 i
j ≥1 i >1

<!-- p. 35 -->

HORMIGÓN ESTRUCTURAL 35
Hernández-Gil
Para situaciones accidentales de proyecto:

Qki ∑γGAj Gkj + γPA Pk + Ad + Ψ 11Qk 1 + ∑ Ψ 2 i
j ≥1 i >1

Para la situación sísmica de proyecto:

G ki ∑ G kj + Pk + γI AEd + ∑ Ψ 2 i
j ≥1 i ≥1

donde:

\+ significa “se combina con”
Σ significa “efecto combinado de”
Gkj valor característico de las acciones permanentes
Pk valor característico de las acciones de pretensado, que se consideran
permanentes
Qk1 valor característico de la acción variable 1
Qki valor característico de la acción variable i
Ad valor de cálculo de la acción accidental
AEd valor de cálculo de la acción sísmica
γGj coeficiente parcial de la acción permanente j
γGAj igual al anterior pero para situaciones accidentales de proyecto
γP coeficiente parcial para la acción de pretensado
γPA igual al anterior pero para situaciones accidentales de proyecto
γQi coeficiente parcial para la acción variable i
γI coeficiente de importancia. Este coeficiente diferencia las estructuras
según su importancia.

Para verificar los estados límites de servicio se debe de cumplir:

Ed ≤ C d

Donde Cd es el valor nominal o una función de la propiedad de cálculo del
material relacionada con los efectos de cálculo de las acciones consideradas, o sea, una
limitación impuesta a la estructura (por ejemplo: unas deformaciones).

Para cada estado límite de servicio, el valor de Ed debe de ser calculado para
las siguientes combinaciones:

\- Combinación característica o rara

Qki ∑ Gkj + Pk + Qk 1 + ∑ Ψ 0 i
j ≥1 i >1

<!-- p. 36 -->

PROCEDIMIENTOS GENERALES DE CÁLCULO 36

\- Combinación frecuente

Qki ∑ Gkj + Pk + Ψ 11Qk 1 + ∑ Ψ 2 i
j ≥1 i >1

\- Combinación cuasipermanente

Qki ∑ Gkj + Pk + ∑ Ψ 2 i
j ≥1 i ≥1

Algunas normas pueden presentar comprobaciones simplificadas, el EC1 y la
EHE presentan comprobaciones simplificadas para estructuras de edificación.

2.3. DURABILIDAD

Las estructuras pueden colapsar por sobrepasar uno de los Estados Límites
debido a causas tales como el deterioro de los materiales y, en especial, a problemas de
corrosión. El problema de la durabilidad de la estructura se enfoca fuera del método de
los estados límites y con carácter paliativo. La norma EHE plantea 4 clases generales de
ambientes relativos a corrosión de armaduras y 4 clases de ambientes específicos para
procesos de deterioro distintos de la corrosión, éstos se especifican en las tablas 2.5 y
2.6.

Tabla 2.5. Clases generales de exposiciones relativas a corrosión de las armaduras

Clase de ambiente Ejemplos
I –no agresivo-. Interior de edificios
IIa –normal de humedad alta- Sótanos no ventilados, cimentaciones
IIb –normal de humedad media- Tableros y pilas de puentes
IIIa –ambiente marino aéreo- Edificaciones a menos de 5 km de la
costa
IIIb –ambiente marino sumergido- Diques, pantalanes
IIIc –ambiente marino en zona de mareas- Pilas de puentes sobre el mar
IV –corrosión por cloruros- Piscinas

Tabla 2.6. Clases específicas de exposición relativas a otros procesos de deterioro
distintos de la corrosión

Clase específica de exposición Ejemplos
Qa –ataque químico débil- Instalaciones industriales con ataque débil
Qb –ataque químico medio- Estructuras marinas en general
Qc –ataque químico fuerte- Conducciones de aguas residuales
H –heladas sin sales fundentes- Construcciones en alta montaña
F –heladas con sales fundentes- Tableros de puentes en alta montaña
E –erosión por cavitación o abrasión- Pilas en cauces muy torrenciales

<!-- p. 37 -->

HORMIGÓN ESTRUCTURAL 37
Hernández-Gil

La durabilidad se garantiza clasificando la estructura dentro de una o varias
clases de exposición e imponiendo condiciones relativas a:

\- Máxima relación agua/cemento y mínimo contenido de cemento (tabla
37.3.2.a de la EHE-98) para garantizar la mínima porosidad.
\- Resistencias mínimas (tabla 37.3.2. de la EHE-98) para garantizar máxima
compacidad.
\- Formas estructurales adecuadas que proporcionen el máximo aislamiento
del agua.
\- Adopción del adecuado espesor de recubrimiento (apdo. 37.2.4 de la EHE-
\98)
\- Control de sustancias perjudiciales (apdos. 37.3.4 al 37.3.5)
\- Cantidad mínima de aire ocluido para resistencia a heladas (apdo. 37.3.3)
\- Limitación de fisura (apdo. 49.2.4)
\- Calidad adecuada del hormigón, tanto en dosificación como en ejecución.

Con todas estas limitaciones se pretende que el hormigón no presente deterioro
durante su vida útil con objeto de garantizar las resistencias del acero y del hormigón
durante este periodo.

<!-- p. 38 -->

PROCEDIMIENTOS GENERALES DE CÁLCULO 38

Ejemplo

La azotea de un edificio está compuesta por vigas continuas de tres vanos
separadas 5 m entre sí. Todos los vanos tienen una luz de 6 m. La sección transversal de
la viga tiene unas dimensiones de 0.5×0.3 m. Las cargas que actúan sobre ella son:
\- Una carga permanente compuesta de su peso propio más 2 kN/m2.
\- Una carga variable de nieve de 0.6 kN/m2.
\- Una carga variable de uso de 1.5 kN/m2.
El nivel de ejecución de la obra es intenso.

Se pide: hallar el momento flector de cálculo en ELU para un apoyo intermedio
en la situación persistente o transitoria.

A B

6 m 6 m 6 m

0.5 m

0.3 m

Solución:

La fórmula correspondiente para la situación de proyecto persistente y
transitoria es:

Qki ∑γGj Gkj + γP Pk + γQ1Qk 1 + ∑γQi Ψ 0 i
j ≥1 i >1

En primer lugar hay que estudiar las acciones que actúan sobre la estructura y
clasificarlas. Si la densidad del hormigón armado es de 2500 kg/m3, los valores
característicos de las acciones serán:

G = 2500 kg/m2 · 9.81 m/s2 · 0.5 m · 0.3 m + 2000 N/m2 · 5 m =
\= 13.7 kN/m
Qnieve = 0.6 kN/m2 · 5 m = 3.0 kN/m

<!-- p. 39 -->

HORMIGÓN ESTRUCTURAL 39
Hernández-Gil
Quso = 1.5 kN/m2 · 5m = 7.5 kN/m

Para conocer los valores representativos de las acciones variables es necesario
conocer los valores de los coeficientes ψ, que vienen dados en la tabla 2.4. ψ0 para la
nieve toma el valor de 0.6 y para la carga variable de uso 0.7.

Para obtener los valores de cálculo necesitamos multiplicar los valores
representativos por los coeficientes parciales de seguridad de las acciones γF, que son:

G 1.35 si la acción es desfavorable, 1.0 si la acción es favorable
Qnieve y Quso 1.50 si la acción es desfavorable, 0 si la acción es favorable

Como se puede observar el carácter favorable o desfavorable de la carga, en
este problema, dependerá de dónde se sitúe ésta. Una carga distribuida en el primer o
segundo vano será desfavorable en cuanto al momento en B mientras que una carga
distribuida situada en el tercer vano será favorable para el momento en B. Esto se puede
apreciar en los tres casos siguientes:

q

1
A B

deformada
q

2
A B

q

3
A B

<!-- p. 40 -->

PROCEDIMIENTOS GENERALES DE CÁLCULO 40

El momento en B tendrá los siguientes valores:

Caso 1 Caso 2 Caso 3 Caso 1+2+3
Momento en B -0.0667 q l2 -0.0500 q l2 0.0167 q l2 -0.1000 q l2

donde l es la longitud del vano y q la carga por unidad de longitud.

En vista de lo anterior, caben dos posibilidades:

\1. Plantear directamente la hipótesis más desfavorable
\2. Realizar todas la combinaciones posibles

La hipótesis más desfavorable, en este sencillo ejemplo es fácil de ver y
consiste en:

Considerar como Q1 a la carga variable de uso (puesto que es la mayor) y
considerar los valores desfavorables de γF en los vanos primero y segundo y el
valor favorable para el tercer vano. Procediendo de esta manera el momento en
B será:

MB = 1.35 · 13.7 · 62 · ( -0.0667 -0.0500 ) + 1.00 ·13.7 · 62 · ( 0.0167) +
1.5 ·7.5 · 62 · ( -0.0667 -0.0500 ) + 1.5 · 0.6 · 3.0 · 62 · ( -0.0667 -0.0500)
\= -128.07 kN·m

En este sencillo ejemplo es fácil saber cúal es la combinación más
desfavorable. No obstante, en la mayoría de los casos la deducción de la combinación
más desfavorable no es inmediata siendo necesario plantear las distintas combinaciones
posibles, tal y como se resume en la tabla siguiente.

<!-- p. 41 -->

HORMIGÓN ESTRUCTURAL 41
Hernández-Gil

Combinación Q1 Primer vano Segundo vano Tercer vano MB (kN·m)
1 Uso Desfavorable Desfavorable Desfavorable -116,8
2 Uso Desfavorable Desfavorable Favorable -128,1
3 Uso Desfavorable Favorable Desfavorable -83,1
4 Uso Desfavorable Favorable Favorable -94,3
5 Uso Favorable Desfavorable Desfavorable -71,8
6 Uso Favorable Desfavorable Favorable -83,1
7 Uso Favorable Favorable Desfavorable -38,1
8 Uso Favorable Favorable Favorable -49,3
9 Nieve Desfavorable Desfavorable Desfavorable -111,1
10 Nieve Desfavorable Desfavorable Favorable -121,5
11 Nieve Desfavorable Favorable Desfavorable -80,2
12 Nieve Desfavorable Favorable Favorable -90,5
13 Nieve Favorable Desfavorable Desfavorable -69,9
14 Nieve Favorable Desfavorable Favorable -80,2
15 Nieve Favorable Favorable Desfavorable -39,0
16 Nieve Favorable Favorable Favorable -49,3

Como se puede observar la hipótesis inicial era cierta.

Referencias

EN 1991-1-1:2002 Eurocode 1. Actions on structures. General actions. Densities, selfweight, imposed loads for buildings.

EHE. Instrucción de Hormigón Estructural (borrador 2007). Secretaría General
Técnica. Ministerio de Fomento. Madrid.

Jiménez Montoya P., García Meseguer A. y Morán Cabré F. (1994). Hormigón Armado.
Editorial Gustavo Gili. Barcelona.

<!-- p. 42 -->

PROCEDIMIENTOS GENERALES DE CÁLCULO 42

Ejercicios propuestos

\1. Para el ejemplo anterior: estudiar cuál sería la posición más desfavorable de
una carga móvil puntual de 100 kN para los siguientes casos:

a. máximo momento flector positivo
b. máximo momento flector negativo
c. cortante.

\2. En ELS los valores de los coeficiente parciales de mayoración de las cargas y
de minoración de los materiales son 1, ¿tiene esto algo que ver con las
consecuencias que tiene para la estructura el hecho de que deje de verificarse
puntualmente un ELS?

<!-- p. 43 -->

HORMIGÓN ESTRUCTURAL 43
Hernández-Gil

<!-- p. 44 -->

PROPIEDADES DE LOS MATERIALES 44

<!-- p. 45 -->

HORMIGÓN ESTRUCTURAL 45
Hernández-Gil
CAPÍTULO III

DESCRIPCIÓN Y CARACTERÍSTICAS DEL HORMIGÓN Y
DEL ACERO

Bombeando hormigón.
Cortesía de HOLCIM (España) S.A. www.holcim.es

En este capítulo se estudian las características mecánicas de cada uno de los
componentes del hormigón estructural: hormigón, armadura pasiva y armadura activa.
El planteamiento de este capítulo es fundamentalmente mecanicista, no tratándose los
aspectos químicos ni del hormigón ni del acero.

3.1. EL HORMIGÓN O CONCRETO

El hormigón (concreto en varios países de Ibero-América) es una mezcla de:
cemento, agua y áridos como componentes principales. Además pueden añadírsele
adiciones (hasta un 35% del peso de cemento, dependiendo del tipo de adición) y
aditivos (\<5% del peso de cemento). El objetivo de las adiciones y de los aditivos es

<!-- p. 46 -->

PROPIEDADES DE LOS MATERIALES 46

mejorar alguna de las propiedades del hormigón aunque en la práctica las adiciones se
emplean sobre todo para abaratar el precio final del hormigón. Las adiciones son:
puzolanas naturales, cenizas volantes, escoria de alto horno y polvo de sílice. Los
aditivos, como los superplastificantes, se utilizan fundamentalmente para mejorar la
trabajabilidad temporal del hormigón y permitir relaciones bajas de agua/cemento. En
peso, las proporciones aproximadas de cada uno de los componentes de un hormigón
típico vienen reflejadas en la figura 3.1:

1200

1000

800

600 Kg/m3
400

200

0
árido grueso árido fino cemento agua

Componentes del hormigón

Figura 3.1. Componentes del hormigón en peso

En el instante en que el agua entra en contacto con el cemento se produce una
reacción química exotérmica de hidratación y en poco tiempo (unos días) el hormigón
se endurece tomando el aspecto de una piedra, ver figura 3.2. Cuando se agrega agua al
cemento y a los áridos se forma una pasta gelatinosa que puede tomar cualquier forma.
El agua es necesaria para que el hormigón fresco sea manejable y moldeable y por este
motivo la cantidad de agua añadida será superior a la estrictamente necesaria para el
proceso de hidratación y endurecimiento del hormigón. El agua en exceso no llega a
formar parte de la estructura química del hormigón endurecido sino que se evapora con
el tiempo y hace que el hormigón adquiera una naturaleza porosa.

Figura 3.2. Aspecto del hormigón endurecido

La propiedad más importante del hormigón es su resistencia a compresión. La
relación agua/cemento de la mezcla es la variable que más afecta a la resistencia a

<!-- p. 47 -->

HORMIGÓN ESTRUCTURAL 47
Hernández-Gil
compresión del hormigón. Un hormigón con gran cantidad de agua será muy poroso,
retraerá en exceso y tendrá una resistencia baja.

Para medir la docilidad del hormigón (trabajabilidad) se emplea el ensayo de
asiento en el cono de Abrams (figura 3.3). Este ensayo consiste en un molde de acero
troncocónico en el que se vierte hormigón y una vez lleno se retira el molde y se mide
lo que ha descendido la masa, atribuyéndole su consistencia en función de este
descenso: seca de 0 a 2 cm, plástica de 3 a 5 cm, blanda de 6 a 9 cm y fluida de 10 a 15
cm. Este ensayo es un referente de la calidad del hormigón: cuanto más dócil es un
hormigón, más agua contiene y, por tanto, menor será su resistencia.

Consistencia

Figura 3.3. Ensayo de consistencia

El ensayo más importante para medir la resistencia a compresión es el de rotura
de probetas cilíndricas1 de 15×30 cm, medidas en hormigón de 28 días y curado a 20ºC
con el 90% de humedad (EN 206-1). La norma española EHE define como resistencia
del hormigón a compresión al resultado obtenido mediante el ensayo en rotura de la
probeta cilíndrica en las condiciones anteriormente expuestas. Además hay otros
ensayos no destructivos que miden la resistencia a compresión, aunque de forma menos
precisa, como son los ensayos de ultrasonidos o los métodos esclerométricos. Antes de
usar estos ensayos no destructivos conviene conocer sus limitaciones, que están
suficientemente explicadas en la literatura especializada2.

La rapidez con la que el hormigón adquiere resistencia depende, entre otros
factores, de la temperatura exterior: cuanto mayor es la temperatura más rápido es el
proceso de hidratación. Esto provoca que a temperaturas en torno a 0ºC sea necesario
tomar medidas especiales como calentar los áridos o cubrir el hormigón, en este último
caso se trata de aprovechar el calor generado por el proceso exotérmico. Por otro lado,
en fábricas de productos prefabricados de hormigón es habitual utilizar técnicas de
curado con vapor para acelerar el proceso de endurecimiento.

1 En otros países se utilizan otro tipo de probetas como probetas prismáticas.
2 Por ejemplo: en hormigones viejos no es riguroso emplear métodos esclerométricos.
Los métodos esclerométricos están basados en un índice de rebote de una masa contra la
superficie del hormigón con objeto de medir su módulo de elasticidad y, a partir de éste
estimar su resistencia. Puesto que el proceso de carbonatación (comentado en el primer
capítulo) lleva asociado un fenómeno de endurecimiento, los hormigones viejos serán
más duros en su exterior que en su interior (no carbonatado).

<!-- p. 48 -->

PROPIEDADES DE LOS MATERIALES 48

La resistencia del hormigón aumenta con el tiempo. De manera aproximada, se
puede decir que la resistencia de un hormigón de un año es un 10% superior a la
resistencia que el mismo hormigón tenía a los 28 días.

<!-- p. 49 -->

HORMIGÓN ESTRUCTURAL 49
Hernández-Gil

3.2. PROPIEDADES MECÁNICAS DEL HORMIGÓN

Por separado, el árido y la pasta de cemento tienen un comportamiento que se
puede aproximar al lineal, esto no sucede con el hormigón, como se puede observar en
la figura 3.4. Esta no linealidad es debida fundamentalmente a microgrietas que
aparecen en la interfase roca-pasta de cemento.

σc

árido

hormigón

pasta de cemento

\=c

Figura 3.4. Diagrama tensión-deformación del hormigón y de sus componentes

La principal característica mecánica de un hormigón es su resistencia a
compresión (fc), que es obtenida a partir del ensayo de rotura en probeta cilíndrica.
Siguiendo la nomenclatura de la norma EHE y del Eurocódigo 2, se definen:

σc tensión normal a la que está sometido el hormigón en un instante
determinado.
fc resistencia media obtenida de ensayar al menos dos probetas a
compresión.
fck resistencia característica a compresión del hormigón en probeta
cilíndrica a 28 días. Es el valor que se adopta en el proyecto para la
resistencia a compresión del hormigón (fck siempre será mayor o igual
que la resistencia característica real: cuantil del 5% de la resistencia
del hormigón colocado en obra).
fci resistencia a rotura por tracción indirecta (ensayo brasileño).
fct resistencia a tracción. Se puede determinar como 0.9fci.
fcm resistencia media a compresión a 28 días, puede calcularse como
fcm=fck+8 MPa si las condiciones de ejecución son buenas.
fctm resistencia media a tracción a los 28 días.
fct,k resistencia característica inferior a tracción (correspondiente al cuantil
del 5%), también se denomina fct,k,0.05. Se puede estimar como 0.7fctm.
fctk,0.95 resistencia característica superior a tracción. Según el EC2 se puede
estimar como 1.3fctm.

<!-- p. 50 -->

PROPIEDADES DE LOS MATERIALES 50

fct,fl resistencia a flexo-tracción. Ésta puede obtenerse a partir de la
resistencia a tracción mediante la expresión 3.1.
⎛ h ⎞ 0 .7 1 + 1 . 5⎜ ⎟
⎝ 100 ⎠
(3.1) f ct ,fl = f ct 0 . 7
⎛ h ⎞
1 . 5⎜ ⎟
⎝ 100 ⎠

siendo h el canto del elemento en milímetros.

A falta de resultados experimentales, el valor de la de la resistencia media a
tracción se puede estimar mediante la siguiente expresión propuesta por el EC2
(Eurocódigo 2)

2
f ct ,m = 0 . 30f ck 3 para f ck ≤ 50 MPa
f cm ⎞ (3.2) f ct ,m = 2 . 12 ln⎛+⎜ 1 ⎟ para f ck > 50 MPa
⎝ 10 ⎠

Como hemos dicho antes, la resistencia del hormigón depende de su edad. El
EC2 y la norma española plantean las siguientes expresiones:

f cm ( t ) = βcc ( t ) f cm
f ct ,m ( t ) = (βcc ( t ) ) α f ct , m (3.3)
⎡ 28 ⎞ ⎤ donde βcc ( t ) = exp ⎢s ⎛−1 ⎥ ⎜⎜ ⎟⎟ ⎢⎣ ⎝ t ⎠ ⎥⎦

donde t es la edad del hormigón en días, tomando como origen (t=0) el instante en el
que se vierte el hormigón en el encofrado, βcc es un coeficiente que depende de la edad
del hormigón, s es un factor que depende del tipo de cemento y toma el valor: 0.2 para
cementos de alta resistencia y rápido endurecimiento, 0.25 para cementos de
endurecimiento normal y rápido y 0.38 para cementos de endurecimiento lento. Por
último α es un coeficiente que depende de la edad del hormigón y de su resistencia
características a los 28 días y cuyo valor es:

1 si t \< 28 días
2/3 si t ≥ 28 días y fck ≤ 50 MPa
1/2 si t ≥ 28 días y fck >50 MPa

La denominación de un hormigón está basada en su resistencia a compresión.
De hecho el EC2 los denomina con la letra C (inicial de la palabra inglesa Concrete)
seguida de la resistencia característica en probeta cilíndrica y seguida de la resistencia
característica en probeta cúbica. Así: C25/30, significa hormigón de 25 MPa en probeta

<!-- p. 51 -->

HORMIGÓN ESTRUCTURAL 51
Hernández-Gil
cilíndrica y 30 en cúbica. La EHE define HM, HA o HP según se trate de hormigón en
masa, armado o pretensado, seguidos de su resistencia característica en MPa, la primera
letra de su consistencia, el tamaño máximo del árido y el ambiente. Así: un hormigón
HA-25/P/25/IIIa, corresponde a un hormigón para armar de resistencia característica 25
MPa, con una consistencia plástica, de 25 mm de tamaño máximo de árido y en un
ambiente marino aéreo.

3.3. DIAGRAMAS TENSIÓN-DEFORMACIÓN

Cuando se realiza un ensayo de rotura a compresión se observa que el resultado
obtenido depende de la velocidad con la que se lleva a cabo, tal y como se aprecia en la
figura 3.5. Podemos concluir que el diagrama tensión-deformación depende del tiempo
de aplicación de la carga. La diferencia entre los diagramas tensión-deformación
obtenidos para distintos tiempos de aplicación de la carga es menor si la edad del
hormigón es mayor, o sea, el fenómeno observado disminuye a medida que aumenta la
edad del hormigón. Existen además otras variables que influyen en la forma del
diagrama tensión-deformación, como son la forma de la sección, la humedad, el tipo de
árido, …

Si un hormigón con una edad determinada (por ejemplo: el de la figura 3.5) lo
sometemos de forma rápida a una tensión de compresión σ1 inicialmente se produce una
deformación =1 pero pasados varios días, en los que se mantiene la carga constante, se
observa que la deformación ha pasado a ser =’1. De la misma forma, si se carga el
mismo hormigón con una tensión de compresión σ2 la deformación inicial es =2 pero
pasados unos minutos el hormigón rompe, tal y como se aprecia en la figura 3.5. Al
fenómeno por el cual el hormigón rompe con una resistencia inferior a fc se le conoce
como cansancio del hormigón.

σc

Unos segundos

σ2 Unos minutos Envolvente de rotura

Varios días
σ1

\=1 =2 =’1 =c

Figura 3.5.Diagramas tensión-deformación en función del tiempo de aplicación
de la carga

<!-- p. 52 -->

PROPIEDADES DE LOS MATERIALES 52

Evidentemente no se puede obtener a priori un diagrama tensión-deformación
específico para cada estructura concreta. Tampoco tendría sentido obtener el diagrama
tensión-deformación a posteriori, puesto que esto implicaría desconocer el nivel de
seguridad hasta después de ejecutada la estructura. Por este motivo, las normas
proponen diferentes tipos de diagramas. Estos diagramas se dividen en dos grupos en
función de su rango de aplicación: diagramas para el cálculo estructural y diagramas
para el diseño de secciones en el ELU de agotamiento por tensiones normales.

El origen de esta división está en el hecho de que los diagramas empleados en
el cálculo estructural deben de proporcionar valores fiables en el rango de deformación
que se pretenda analizar. Por el contrario, para comprobar una sección en ELU, lo que
interesa son los valores últimos de las tensiones y de las deformaciones. En el caso del
ELU por agotamiento frente a tensiones normales se opta, como veremos después, por
diagramas más sencillos, reduciendo su rango de aplicación en aras de conseguir mayor
simplicidad. En la figura 3.6 se han esquematizado los distintos modelos tensióndeformación para el hormigón, que se desarrollarán a continuación.

Diagramas tensión-deformación
para el hormigón

Modelos Modelos bidimensionales
unidimensionales y tridimensionales

Definidos a corto plazo Definidos en rotura

Aproximaciones Diagramas - Rectangular
lineales parabólicos - Parábola-rectángulo
\- Bilineal
\- otros

Figura 3.6. Distintos diagramas tensión-deformación para el hormigón.

3.3.1 Diagramas para el cálculo estructural

Modelo tensión-deformación lineal: deformación elástica

Siguiendo la clasificación de la Figura 3.6, este modelo corresponde a una
aproximación lineal del comportamiento unidimensional. Este comportamiento
corresponde a probetas cilíndricas de 15×30 ensayadas a compresión en un corto plazo
de tiempo: pocos minutos.

<!-- p. 53 -->

HORMIGÓN ESTRUCTURAL 53
Hernández-Gil
Siempre que las tensiones no superen un determinado nivel se puede considerar
que el hormigón deforma linealmente. La hipótesis más empleada en el cálculo de
estructuras de hormigón es la de comportamiento lineal del material, esto es, se
considera que el módulo de deformación longitudinal del hormigón es constante.

Según el EC2, el módulo de deformación longitudinal o módulo de elasticidad
para un hormigón de 28 días se puede aproximar por Ecm (pendiente de la secante entre
σc=0 y σc=0.4 fcm). Para áridos de cuarcita el EC2 propone la siguiente expresión:

⎛ f cm ⎞ 0 . 3 E cm = 22000 ⎜ ⎟ MPa (3.4)
⎝ 10 ⎠

donde fcm se introduce en MPa. Esta formulación es, como ya hemos dicho, para áridos
cuarcíticos; para árido calizo y arenisco el valor debe de reducirse en un 10% y 30%
respectivamente. En el caso de basalto el valor debe de incrementarse en un 20%.

Además el EC2 propone que la variación en el tiempo de Ecm puede ser
estimada como:
⎛ fcm ( t ) ⎞ 0 . 3 (3.5) E cm ( t ) = ⎜⎜ ⎟⎟ E cm ⎝ fcm ⎠

donde t es la edad del hormigón, tomando como origen el instante en que el hormigón
se vierte en el encofrado.

La norma española EHE propone dos valores del módulo de deformación
longitudinal: Ecm y Ec.

Ecm es el módulo de deformación longitudinal secante a 28 días. Este módulo
corresponde a la pendiente de la recta secante a la curva real tensión-deformación. Su
valor es:

E cm = 8500 3 f cm MPa (3.6)

La expresión anterior sólo es válida siempre y cuando las tensiones, en condiciones de
servicio, no sobrepasen 0,40fcm.

La EHE define además un módulo para cargas instantáneas o rápidamente
variables, Ec o módulo de deformación longitudinal inicial del hormigón a los 28 días
(pendiente de la tangente en origen de la curva real tensión-deformación). Su valor
viene dado por:

E c = 10000 3 f cm MPa (3.7)

<!-- p. 54 -->

PROPIEDADES DE LOS MATERIALES 54

Como ya se ha comentado, el valor de fcm a 28 días se puede aproximar por
fck+8 MPa. La norma EHE propone además un factor de corrección a aplicar a Ecm y Ec
en función del tipo de árido usado: α. La EHE también considera el hecho de que el
hormigón pueda tener una edad distinta de 28 días, para ello utiliza la misma expresión
del EC2: ecuación 3.5.

Ambos módulos Ecm y Ec son para cargas de corta duración y no tienen en
cuenta que cuando las cargas son de larga duración se produce una variación en el valor
del módulo de elasticidad (fluencia), tal y como se estudiará más adelante.

Modelo tensión-deformación no lineal

Para cálculos no lineales, el EC2 y la EHE proponen un modelo tensióndeformación parabólico definido a corto plazo (ver esquema de la figura 3.6). Este
modelo se representa en la figura 3.7.3

σc

fcm

0.4 fc tan α = Ecm

α

\=c1 =cu1 =c

Figura 3.7. Diagrama tensión-deformación propuesto por el EC2 y la EHE para
cálculo estructural no lineal con cargas instantáneas

El diagrama de la figura 3.7, que sólo se puede emplear para cargas de corta
duración, corresponde a la siguiente formulación:

3 Se utiliza nomenclatura del EC2, que varía ligeramente respecto de la EHE.

<!-- p. 55 -->

HORMIGÓN ESTRUCTURAL 55
Hernández-Gil
kη− η2
σc = f cm para εc ≤ εcu 1
1 + ( k − 2 )η

εc η= (3.8)
εc 1
εc 1
k = 1 . 05E cm
f cm
0 . 31 \< 0 . 0028 εc 1 = 0 . 0007 (f cm )

siendo:
σc tensión del hormigón para un valor dado de =c
\=c deformación del hormigón
\=c1 deformación del hormigón para la tensión máxima
\=cu1 deformación máxima del hormigón

⎧ 0 . 0035 si f ck \< 50 MPa
4 εcu 1 = ⎪⎨ ⎛ 98 − f cm ⎞ 0 . 0028 + 0 . 027 ⎜ ⎟ si f ck ≥ 50 MPa ⎪⎩ ⎝ 100 ⎠

El diagrama tensión-deformación de la figura 3.7 se emplea poco en la práctica
debido a la dificultad que conlleva el hecho de que el módulo de deformación
longitudinal (pendiente de la curva) dependa del nivel de tensión.

El modelo correspondiente a la figura 3.7 (ecuación 3.8) considera la
existencia de tensión sólo en una dirección, lo que corresponde al ensayo en probeta
cilíndrica. En el caso de que existan tensiones en dos o en tres direcciones existen
modelos más sofisticados para representar el comportamiento del hormigón, alguno de
ellos queda recogido en el Código Modelo CEB-FIP (1990). Ésta consideración viene
recogida en el esquema de la figura 3.6 en lo que se han denominado modelos
bidimensionales y tridimensionales.

3.3.2. Resistencia de cálculo en el hormigón

Cuando se procede a diseñar y armar una sección de hormigón es necesario
aplicar un coeficiente de seguridad a la resistencia del hormigón. Puesto que la
resistencia característica se define para hormigones bajo cargas instantáneas, se hace
necesario adoptar coeficientes que aseguren que el hormigón no experimentará
fenómenos de cansancio. Por este motivo, en el diseño se emplea la resistencia de
cálculo (o diseño) del hormigón a compresión, fcd, que el Eurocódigo 2 define como:

<!-- p. 56 -->

PROPIEDADES DE LOS MATERIALES 56

fck fcd = αcc (3.9)
γc
donde:
γc coeficiente parcial de seguridad del hormigón (tabla 2.1)
αcc coeficiente que considera los efectos negativos de la duración de la
carga (cansancio) y de la forma de aplicar la carga. Tradicionalmente
se ha adoptado un valor de de 0.85.

La norma española EHE desarrolla el caso de que αcc=1, aunque permite
valores entre 0,85 y 1.00 4 .

La resistencia de cálculo (o diseño) del hormigón a tracción, fctd, el EC2 la
define como:

fctk ,0 .05
fctd = αct (3.10)
γc

donde αct es un coeficiente que tiene en cuenta los efectos negativos de la duración de la
carga y de la forma de aplicar ésta sobre la resistencia a tracción del hormigón.

3.3.3. Diagramas para el diseño en rotura de secciones

Como se puede deducir de la figura 3.7, la obtención de un modelo tensióndeformación es complejo y las normas actuales sólo lo proponen para cargas
instantáneas. Estos modelos no son suficientes dado que es necesario dimensionar las
estructuras para combinaciones de cargas de corta y larga duración. La dilatada
investigación sobre el tema ha demostrado que se pueden emplear modelos tensióndeformación sencillos que predigan, con un aceptable margen de error, la resistencia
última del hormigón. Los modelos más empleados son: el rectangular y el parábolarectángulo. El rango de aplicación de estos modelos se reduce al cálculo de la
resistencia última (rotura) de secciones de hormigón. Estos modelos corresponden a los
modelos unidimensionales “definidos en rotura” del esquema de la figura 3.6. Conviene
señalar aquí que estos modelos suponen nula la resistencia del hormigón a tracción.

El diagrama parábola rectángulo, representado en la figura 3.8, consiste en una
parábola que nace en el origen y llega con pendiente horizontal al punto de deformación
εc2 con tensión fcd (o bien fck si se trata de resistencia característica). En el EC2 εc2 toma
el valor constante de 2‰ siempre que la calidad del hormigón verifique que fck es
menor de 50 MPa (ecuación 3.12). El resto del diagrama es una línea horizontal que une
el punto de deformación de εc2 con el punto de deformación máxima (εcu2). El diagrama
parábola-rectángulo para valores de cálculo viene dado por la expresión:

4 Los autores de este libro, por coherencia con la tradición y con lo establecido en otras
normas como la ACI-318-05 recomendamos utilizar αcc =0.85.

<!-- p. 57 -->

HORMIGÓN ESTRUCTURAL 57
Hernández-Gil
⎧ ⎡ n ⎤ ⎛ εc ⎞ 1 − ⎟ ⎪fcd ⎢1 − ⎜ ⎥ para 0 ≤ εc ≤ εc 2 ⎪
σc = ⎨ ⎢ ⎝ εc 2 ⎠ ⎥ (3.11) ⎣ ⎦ ⎪
⎪⎩ fcd para εc 2 ≤ εc ≤ εcu 2

donde

⎧ 2 si fck \< 50 MPa
⎪ 4
n = ⎨ ⎛ 90 − fck ⎞
⎪1.4 + 23.4 ⎜ ⎟ si fck ≥ 50 MPa
⎩ ⎝ 100 ⎠
ck \< 50 MPa 0 ⎧⎪ 2.0 si f εc 2 ( 00 ) = ⎨ 0.53 (3.12)
fck − 50 ) si fck ≥ 50 MPa ⎪⎩ 2.0 + 0.085 (
⎧ 3.5 si fck \< 50 MPa
⎪ 4 0 εcu 2 ( 00 ) = ⎨ ⎛ 90 − fck ⎞
⎪ 2.6 + 35 ⎜ ⎟ si fck ≥ 50 MPa
⎩ ⎝ 100 ⎠

εc2 y εcu2 se representan en la figura 3.8.

En el caso de una sección transversal sometida a compresión simple (momento
flector nulo) la deformación máxima del hormigón se limita a εc2 (tanto por la EHE
como por el EC2). Si en la sección hay alguna fibra traccionada el límite de la
deformación es εcu2. El origen de esta diferenciación está en el hecho de que en flexión
unas fibras están más deformadas que otras y se produce una colaboración entre ellas
que permite mayores deformaciones de rotura. Varios autores han obtenido
experimentalmente deformaciones superiores al 4‰ en flexión.

Otras normas como la americana ACI-318 o la suiza SIA-162 plantean una
deformación máxima del hormigón a compresión única del 3‰, no estableciendo
diferencias entre compresión simple y flexión.

<!-- p. 58 -->

PROPIEDADES DE LOS MATERIALES 58

σc

fck

fcd

\=c
\=c2 =cu2
Figura 3.8. Diagrama Parábola-rectángulo del EC-2.

El diagrama rectangular es el diagrama más extendido en rotura. En el EC2, el
diagrama rectangular corresponde a un valor constante de la tensión de valor ηfcd
(resistencia efectiva) en una profundidad efectiva comprimida de valor λx (siempre que
λx ≤ h, si λx > h la profundidad efectiva vale h, ver figura 3.10) donde x es la distancia
de la fibra más comprimida a la fibra neutra (profundidad de la fibra neutra) y h es el
canto de la sección. Los valores de λy ηnecesarios para definir el diagrama rectangular
propuesto por EC2 son:

⎧ 1 . 0 si f ck ≤ 50 MPa
η = ⎪⎨ f ck − 50 1 . 0 − si 50 \< f ck ≤ 90 MPa (3.13) ⎪⎩ 200

⎧ 0 . 8 si f ck ≤ 50 MPa
λ= ⎪⎨ f ck − 50 (3.14) 0 . 8 − si 50 \< f ck ≤ 90 MPa ⎪⎩ 400

En el caso de que el ancho de la sección transversal disminuya en la dirección
de la fibra más comprimida (lo contrario de lo que sucede en la figura 3.10) el valor de
ηfcd debe de reducirse en un 10%.

De la ecuación 3.14 se desprende que el EC2 hace depender la profundidad
efectiva (λx) de la resistencia del hormigón (fck), tal y como se puede ver en la figura
3.9. Esta variación del parámetro λ se debe a que el comportamiento del hormigón es
más lineal (menos parabólico) cuanto mayor es su resistencia. La resultante de la zona
comprimida en una distribución de tensiones lineal es menor que en una distribución
parabólica por lo que el valor de λdel diagrama rectangular equivalente debe disminuir.

<!-- p. 59 -->

HORMIGÓN ESTRUCTURAL 59
Hernández-Gil

Diagrama rectangular equivalente
Distribución de tensiones real
λ

0.80

0.70

fck (MPa)
50 90

Figura 3.9 Valores de λsegún el Eurocódigo 2.

En la figura 3.10 se ha representado la distribución de tensiones en la zona
comprimida del hormigón obtenida a partir del diagrama parábola-rectángulo y del
diagrama rectangular.

\=cu2 ó =cu3 fcd η fcd

λx x Zona =c2 ó =c3 comprimida
h

Tensiones Tensiones Deformaciones
Diagrama Diagrama
parábola-rectángulo rectangular

Figura 3.10. Diagramas de tensiones normales en la zona comprimida según
los diagramas parábola-rectángulo y rectangular.

La deformación máxima del hormigón en flexo-compresión si se emplea el
diagrama rectangular es εcu3 y la deformación máxima en compresión pura es εc3. Estos
valores se definen a continuación:

⎧ 1 . 75 si f ck ≤ 50 MPa
εc 3 ( 0 00 ) = ⎪⎨ ⎛ f ck − 50 ⎞ 1 . 75 + 0 . 55⎜ ⎟ si 50 \< f ck ≤ 90 MPa
⎪⎩ ⎝ 40 ⎠ (3.15)
⎧ 3 .5 si f ck ≤ 50 MPa
0 εcu 3 ( 4 00 ) = ⎪⎨ ⎛ 90 − f ck ⎞ 2 . 6 + 35⎜ ⎟ si 50 \< f ck ≤ 90 MPa ⎪⎩ ⎝ 100 ⎠

El diagrama bilineal consiste en una línea recta que une el origen con el punto
de deformación εc3, y a partir de ese instante es una línea recta horizontal hasta el punto
de deformación εcu3.

<!-- p. 60 -->

PROPIEDADES DE LOS MATERIALES 60

3.4. FLUENCIA

En la figura 3.5 se puede observar que la deformación obtenida al aplicar una
tensión σ1 es diferente según cual sea el tiempo de aplicación de la carga. La
deformación en el instante inicial es =1 pero basta con dejar pasar varios días
(manteniendo la tensión σ1) para obtener otra deformación diferente: =’1. Consideremos
la figura 3.11 extraída de la figura 3.5. Una vez en el punto (σ1, =1) se puede: bien
mantener la tensión σ1 o bien mantener la deformación =1. Si mantenemos la tensión σ1
pasados unos días la deformación habrá aumentado hasta =’1, a ese proceso se le conoce
como fluencia. Si se mantiene la deformación =1 pasados unos días la tensión
disminuirá hasta un valor σ’1, a este proceso se le conoce como relajación.

σc

Unos segundos

Varios días

σ1

Fluencia
σ’1
Relajación

\=1 =’1 =c

Figura 3.11. Fluencia y relajación

La fluencia se define como la deformación adicional obtenida como
consecuencia de aplicar una carga y mantenerla en el tiempo. Estudiemos con detalle la
figura 3.12: cuando se aplica una carga constante a una probeta de hormigón de 28 días
de edad (punto A) se obtiene una deformación instantánea: AB. Según avanza el
tiempo, si se mantiene la carga, se observa que la deformación sigue creciendo. Esa
deformación adicional es la fluencia. En un instante cualquiera C (p.ej. a los 7 meses)
se puede optar por continuar con la carga (línea de trazo continuo) o por retirarla (línea
de trazo discontinuo). Si se elige la segunda opción y se retira la carga en el punto C se
produce una recuperación instantánea: CD y, con el tiempo, se produce una
recuperación diferida: DE. Al final podemos ver que hay una deformación que no se
recupera: EF.

<!-- p. 61 -->

HORMIGÓN ESTRUCTURAL 61
Hernández-Gil

Deformación (bajo carga constante)

periodo sin carga

C

Recuperación
instantánea Fin de carga

D
Fluencia Recuperación
diferida
B
E

Deformación no
recuperada Deformación instantánea

F
A
0 2 4 6 8 10 12 14 16 (meses)
Figura 3.12. Ensayo de fluencia. Tipos de deformaciones

A la diferencia entre la deformación instantánea y la recuperación instantánea
(AB-CD) se le denomina deformación remanente. La deformación remanente aparece
sólo cuando se carga por primera vez el hormigón (carga noval) y depende del valor de
la tensión aplicada. Para nuevas, cargas por debajo de la carga noval, el diagrama
tensión-deformación es más lineal, tal y como se representa en la figura 3.13.

σc

Deformación
remanente

fc

descarga

\=cu =c
Figura 3.13. Deformación remanente y carga noval

La fluencia del hormigón depende de varios factores, siendo los más
importantes: la humedad del ambiente, las dimensiones del elemento y la composición
del hormigón. En la fluencia también influye la edad del hormigón a la que se aplica la
carga por primera vez y la duración de ésta. Las normas EHE y el EC2 plantean

<!-- p. 62 -->

PROPIEDADES DE LOS MATERIALES 62

formulaciones similares para calcular la fluencia. La formulación adoptada por el EC2
es válida siempre que la tensión aplicada sea menor de 0.45fck(t0). La deformación se
mide en el instante t y la carga se aplica en el instante t0, todo en valores absolutos del
tiempo5, tomando como origen el momento en que el hormigón ha sido puesto en obra.
Así pues, la deformación dependiente de la tensión: deformación instantánea más
deformación diferida se puede calcular como:

σ( t 0 ) σ( t 0 ) εcσ ( t , t 0 ) = + ϕ(t , t 0 ) (3.15)
E cm ( t 0 ) 1 . 05E cm

donde el primer sumando es la deformación instantánea y el segundo la fluencia. El
coeficiente ϕ es el coeficiente de fluencia. Ecm y Ecm(t0) han sido definidos en las
ecuaciones 3.4 y 3.5.

El coeficiente de fluencia ϕ(t,t0) se calcula a partir de la expresión:

ϕ( t , t 0 ) = ϕ0βc ( t , t 0 ) (3.16)

donde:

ϕ0 = ϕHR β( f cm )β( t 0 )
⎧ 1 − HR / 100 1 + si f cm ≤ 35 MPa ⎪ 3 ⎪ 0 . 1 h0
ϕHR = ⎨ ⎡ 1 − HR / 100 ⎤ ⎪ ⎢1 + α1 ⎥α2 si f cm > 35 MPa ⎪ ⎢⎣ 0 . 13 h0 ⎥⎦ ⎩
16 . 8 β(f cm ) = ; f cm en MPa
f cm
1 β(t 0 ) = 0 . 20
0 . 1 + t 0

HR es la humedad relativa del ambiente en %, φ0 es el coeficiente básico de fluencia,
φHR es el coeficiente de influencia de la humedad relativa, β(fcm) es el factor que tiene en
cuenta el efecto de la resistencia del hormigón y β(t0) es el coeficiente que tiene en
cuenta la edad del hormigón cuando se aplica la carga. El valor h0 es el tamaño teórico

5 En todas las expresiones de la normativa, el factor tiempo se mide en días y el origen
de tiempos corresponde al momento en el que se coloca el hormigón en el encofrado.
Por tanto, no se pueden considerar intervalos de tiempo. En la formulación t son los
días transcurridos desde que se vierte el hormigón hasta el instante de la evaluación y t0
son los días que transcurren desde que se vierte el hormigón hasta que se aplica la carga.

<!-- p. 63 -->

HORMIGÓN ESTRUCTURAL 63
Hernández-Gil
en milímetros (h0=2Ac /u) donde Ac es el área de la sección transversal del elemento y u
el perímetro en contacto con la atmósfera.

βc(t,t0) es el coeficiente que describe la evolución de la fluencia en el tiempo
después de la carga:

⎡ t − t 0 ⎤ 0 . 3 βc ( t , t 0 ) = ⎢⎣ βH + t − t 0 ⎥⎦

βH es un coeficiente que depende de la humedad relativa y del tamaño teórico:

18 βH = 5.1 [1 + ( .0 012 HR ) ] h 0 + 250 ≤ 1500 para f cm ≤ 35 MPa
18 βH = 5.1 [1 + ( .0 012 HR ) ] h 0 + 250 α3 ≤ 1500 α3 para f cm ≥ 35 MPa

α1,2,3 son coeficientes para tener en cuenta la influencia de la resistencia del hormigón:

7.0 2.0 5.0
⎡ 35 ⎤ ⎡ 35 ⎤ ⎡ 35 ⎤
α1 = ⎢ ⎥ α2 = ⎢ ⎥ α3 = ⎢ ⎥
⎣ f cm ⎦ ⎣ f cm ⎦ ⎣ f cm ⎦

El EC2 propone además dos factores adicionales de corrección de la fluencia:
uno por el efecto del curado a una temperatura distinta de 20ºC y otro por el efecto del
tipo de cemento. Ambas correcciones se realizan variando el tiempo. Por efecto de la
temperatura se varía la edad del hormigón cuando se mide la deformación: t. Por efecto
del tipo de cemento se varía la edad en el momento de aplicación de la carga: t0.

\1. Por efecto de las temperaturas:

4000
n 13.65 −
e ⋅∆t i (3.17) tT = ∑ 273 +T ( ∆t i )
i =1

donde:
tT edad del hormigón ajustada por efecto de las temperaturas, esta edad
reemplaza a t en las ecuaciones correspondientes.
T(∆ti) temperatura en ºC durante el periodo de tiempo ∆ti
∆ti número de días en los que se mantiene la temperatura T

\2. Según el tipo de cemento se tomará t0 como:

α
⎡ 9 ⎤
(3.18) t 0 = t 0 ,T ⎢1 + 1 . 2 ⎥ ≥ 0 . 5
⎣ 2 + t 0,T ⎦

<!-- p. 64 -->

PROPIEDADES DE LOS MATERIALES 64

donde:
t0,T edad del hormigón en días, cuando la carga es aplicada, ajustada por el
efecto de las temperaturas
α exponente del tipo de cemento (-1 para cementos de fraguado lento, 0
para cementos de fraguado normal o rápido y 1 para cementos de
fraguado rápido y de alta resistencia)

En el caso de que la tensión supere 0.45fck(t0) el EC2 propone una expresión
exponencial para la fluencia a tiempo infinito:

⎡ ⎛ σc ⎞ ⎤ (3.19) ϕk ( ∞, t 0 ) = ϕ( ∞, t 0 ) exp ⎢1 . 5⎜⎜ − 0 . 45 ⎟⎟ ⎥ ⎣ ⎝ f cm ( t 0 ) ⎠ ⎦

Si se puede admitir que las tensiones en el hormigón varían poco y que se
aplican a los 28 días, se puede deducir un módulo de deformación longitudinal efectivo,
Ec,ef, deducible de la ecuación 3.15, a partir del cual es posible calcular las
deformaciones para cargas de largas duración.

E cm E c , ef ( t , t 0 ) = (3.20)
1 + ϕ( t , t 0 )

3.5. RETRACCIÓN

Como veíamos al comienzo del capítulo, es necesario amasar el hormigón con
exceso de agua. Este exceso de agua, que se añade a la masa de hormigón para que sea
manejable durante el hormigonado, no formará parte de la estructura cristalina del
hormigón endurecido y saldrá al exterior, a menos que se mantenga el ambiente en un
100% de humedad. Durante ese proceso, denominado retracción, el hormigón pierde
humedad y retrae.

Si el hormigón esté sumergido en agua experimentará lo que se denomina
entumecimiento e incrementará de volumen.

La deformación por retracción se puede descomponer en dos: deformación por
retracción de secado y deformación por retracción autogenerada. La retracción de
secado se desarrolla lentamente, puesto que es debido a la migración del agua a través
del hormigón endurecido. La retracción autogenerada se produce durante el
endurecimiento del hormigón y por ello se desarrolla en su mayor parte en los días
posteriores al hormigonado. La retracción autogenerada es una función lineal de la
resistencia del hormigón y tiene una importancia especial cuando un hormigón nuevo se
vierte sobre un hormigón endurecido. Los valores de la retracción total (retracción de
secado más retracción autogenerada) se pueden tomar como:

εcs = εcd + εca (3.21)

<!-- p. 65 -->

HORMIGÓN ESTRUCTURAL 65
Hernández-Gil
donde:

εcs es la deformación unitaria total por retracción
(s del inglés shrinkage: retracción)
εcd es la deformación unitaria por retracción de secado (d de dry)
εca es la deformación unitaria por retracción autogenerada
(a de autogenous)

El valor final de la deformación unitaria de secado es εcd,∞=kh· εcd,0. El valor de εcd,0 se
obtiene de la tabla 3.1 (que corresponde a valores medios, pudiéndose presentar una
variación del orden de un 30%) 6.

Tabla 3.1. Valor nominal de la retracción de secado libre εcd,0 (en ‰). Para
hormigones de fraguado normal o rápido.

fck Humedad relativa (en %)
(MPa) 20 40 60 80 90 100
20 0.62 0.58 0.49 0.30 0.17 0
40 0.48 0.46 0.38 0.24 0.13 0
60 0.38 0.36 0.30 0.19 0.10 0
80 0.30 0.28 0.24 0.15 0.08 0
90 0.27 0.25 0.21 0.13 0.07 0

El valor de la deformación unitaria de secado en función del tiempo viene dado
por la expresión:

εcd ( t ) = βds ( t , t s )·k h ·εcd , 0

6 El EC2 plantea también una formulación para el cálculo de εcd,0, que considera
distintos tipos de cemento.
⎡ f cm ⎞ ⎤ − 6 εcd ,0 = 0 . 85 (220 + 110·αds 1 ) exp⎛−⎜ αds 2 ⎟ 10 ·βRH ⎢⎣ ⎝ 10 ⎠ ⎥⎦
⎡ ⎛ HR ⎞ 3 ⎤
βRH = 1 . 55 ⎢1 − ⎜ ⎟ ⎥
⎢⎣ ⎝ 100 ⎠ ⎥⎦
donde HR es la humedad relativa en %, αds1 y αds2 son coeficientes que dependen del
tipo de cemento:

Tipos de cemento αds1 αds2
Fraguado lento 3 0.13
Fraguado normal o rápido 4 0.12
Fraguado rápido y alta resistencia 6 0.11

<!-- p. 66 -->

PROPIEDADES DE LOS MATERIALES 66

donde:

kh es un coeficiente que depende del tamaño teórico (h0) y que se recoge
en la tabla 3.2.

Tabla 3.2. Valores de kh

h0 kh
100 1.0
200 0.85
300 0.75
≥500 0.70

t − t s βds ( t , t s ) =
t − t s + 0 . 04 h03

donde

t edad del hormigón en el instante de evaluación, en días,
tomando como origen cuando el hormigón ha sido colocado
en el encofrado o molde.
ts edad del hormigón en el comienzo del entumecimiento o de
la retracción, en días, tomando el mismo origen que antes. La
fase de retracción comienza al final de la fase de curado.
h0 es el tamaño teórico en milímetros de la sección transversal
(h0=2Ac/u), donde Ac es el área de la sección transversal del
elemento y u el perímetro en contacto con la atmósfera.

La deformación unitaria de retracción autogenerada se calcula a partir de la
expresión:

εca ( t ) = βas ( t )·εca ( ∞ )
εca ( ∞ ) = 2 . 5( f ck − 10 )10 − 6
βas ( t ) = 1 − exp( −0 . 2 t )

donde t está expresado en días.

<!-- p. 67 -->

HORMIGÓN ESTRUCTURAL 67
Hernández-Gil
Ejemplo de fluencia y retracción

Consideremos una probeta de 20×20×40 cm fabricada con hormigón HA-35
sobre la que actúa una carga de 500 kN colocada a los 28 días. El valor de la carga pasa
de 500 kN a 300 kN, a los 100 días. La humedad ambiental es del 70%. La probeta ha
sido curada al vapor durante un día. Calcular la retracción, la deformación inicial y la
deformación a los 100 días y a los 2 años.

20 cm

40 cm

20 cm

Figura 3.14. Probeta sometida a compresión

El diagrama de acciones en función del tiempo es:

kN

500

300

días
28 50 100 730

Para el cálculo de la retracción basta con aplicar la expresión 3.21 extraída del
EC2:
εcs = εcd + εca

El tamaño teórico h0 toma el valor de 100 mm, los valores de t que vamos a
considerar son t=50, 100 y 730 días y ts vale 1.

<!-- p. 68 -->

PROPIEDADES DE LOS MATERIALES 68

El resultando de la retracción se resume en la tabla inferior, en la que se ha
diferenciado entre retracción seca y autogenerada:

Tiempo t (días) 50 100 730
εcd (‰) 0.19 0.24 0.32
εca (‰) 0.047 0.054 0.062
εcs (‰) 0.24 0.30 0.38

La deformación instantánea se calcula a partir del módulo de deformación
longitudinal mediante aproximación lineal. Puesto que la carga se aplica a los 28 días:
Ecm(t0)=Ecm=34077 N/mm2 y σc(28 días)=12.5 N/mm2 (menor que 0.45fcm). Por tanto, la
deformación instantánea es σc /Ecm=-0.0003668 y la probeta encogerá 0.15 mm.

σc 12 . 5 ∆ L = L = 400 = 0 . 15 mm
E cm 34077

A los 100 días hay que considerar dos situaciones: antes y después de reducir la
carga. Antes de reducir la carga, tenemos la deformación inicial a los 28 días más la
fluencia que ésta haya producido. La carga comenzó a actuar a los 28 días: t0=28 días.
Aplicando las fórmulas correspondientes (ecuaciones 3.15 y 3.16) se obtiene el valor
del coeficiente de fluencia ϕ =1.08.

σ( t 0 ) σ( t 0 ) 12 . 5εcσ ( t , t 0 ) = + ϕ(t , t 0 ) = − 0 . 000368 − 1 . 08 = − 0 . 00074
E cm ( t 0 ) 1 . 05E cm 1 . 05 ⋅ 34077

Lo que provoca una disminución de longitud en la probeta de 0.30 mm.

A partir de este momento se reduce la carga, pasando de 500 a 300 kN. Puesto
que hay una disminución de tensión de 5 N/mm2 se produce un alargamiento que se
puede obtener a partir del módulo de deformación longitudinal para el hormigón con
100 días Ecm(100), calculado a partir de las ecuaciones 3.3 y 3.5: Ecm(100)=35302 MPa.
Para este caso la deformación instantánea es σc /Ecm(100)=0.00014 y la probeta alargará
0.056 mm.
σc 5 ∆ L = L = 400 = 0 . 056 mm
E cm (100 ) 35302

¿Qué pasará a los dos años?. Aplicaremos el principio de superposición de la
siguiente forma: la fluencia de la carga de 500 kN se considera hasta los 2 años y la
fluencia de la carga de 200 kN de tracción se considera desde los 100 días hasta los 2
años. El efecto total será la suma de ambos.

<!-- p. 69 -->

HORMIGÓN ESTRUCTURAL 69
Hernández-Gil
Para la carga de 500 kN el coeficiente de fluencia vale ϕ=1.64;. Para la
segunda carga el coeficiente de fluencia es ϕ=1.27. Las correspondientes deformaciones
son las siguientes:

σ( t 0 ) σ( t 0 ) 12 . 5 12 . 5εcσ ( 730;28 ) = + ϕ(t , t 0 ) = − − 1 . 64 = − 0 . 00094
E cm ( t 0 ) 1 . 05E cm 34077 1 . 05 ⋅ 34077
σ( t 0 ) σ( t 0 ) 5 5εcσ ( 730;100 ) = + ϕ(t , t 0 ) = + 1 . 27 = 0 .00032
E cm ( t 0 ) 1 . 05E cm 35302 1 .05 ⋅ 34077

La deformación total a los 730 días será de -0.00062, o sea, la probeta habrá
encogido 0.248 mm, que sumados a la retracción, supone un acortamiento total de 0.4
mm a los 730 días.

La deformación tensional (instantánea + fluencia) se ha representado en la
figura 3.15.

mm
0.4

0.3

0.2

0.1
días

50 100 700

Figura 3.15. Deformación tensional

3.6. OTRAS PROPIEDADES DEL HORMIGÓN

El hormigón presenta otras características mecánicas que es necesario resaltar.

Densidad

La densidad aproximada del hormigón es de 2300 kg/m3 para hormigón en
masa y de 2500 kg/m3 para hormigón armado y pretensado.

Existen hormigones ligeros fabricados con productos como la piedra pómez o
la escoria expandida de alto horno. Sus densidades van desde 1300 a 2000 kg/m3. La
resistencia característica de estos hormigones es muy variable dependiendo del producto
empleado y oscila entre 1 y 50 N/mm2. Su módulo de elasticidad está comprendido entre
un 50 a un 70% de los hormigones normales y la fluencia y retracción son mayores que
en los hormigones normales.

El coeficiente de Poisson del hormigón no fisurado es de 0.2 y 0 para el
hormigón fisurado.

<!-- p. 70 -->

PROPIEDADES DE LOS MATERIALES 70

El coeficiente lineal de dilatación térmica, que mide el aumento de volumen
experimentado por el hormigón cuando incrementa su temperatura, es igual a 10-5 ºC-1.
Por tanto, la deformación por dilatación térmica del hormigón es:

ε∆T = 10 −5 ⋅ ∆T (3.22)

donde ∆T viene expresado en grados centígrados.

Para tener en cuenta el comportamiento del hormigón a grandes temperaturas,
se puede suponer que hasta los 400ºC el módulo de deformación longitudinal disminuye
pero no pierde resistencia última fc. A 600 ºC ha perdido un tercio de su resistencia
última y a 800ºC sólo le queda un sexto de la resistencia inicial.

Confinamiento del hormigón

Una aplicación muy interesante en construcción, que permite entender el
comportamiento del hormigón estructural, es el efecto del confinamiento del hormigón.
El hormigón tiene la capacidad de incrementar su carga a compresión si se le somete a
una presión lateral de confinamiento, ver figura 3.16. La resistencia última a
compresión del hormigón confinado responde a la conocida expresión experimental
obtenida en Illinois en los años 20 del siglo XX:

fck ,conf = fck + 4.1σconf (3.23)

σc

fck,conf fck,conf

σconf

Confinado, σconf,2 σconf,2>σconf,1

Confinado, σconf,1

No confinado
\=c

Figura 3.16. Efectos del confinamiento sobre el diagrama tensión-deformación

<!-- p. 71 -->

HORMIGÓN ESTRUCTURAL 71
Hernández-Gil
La formula anterior no es de aplicación inmediata puesto que el confinamiento
en hormigón generalmente lo produce la armadura y ésta se encuentra en posiciones
localizadas y no en un continuo. En las piezas de hormigón la armadura transversal,
compuesta por cercos o espirales, es la que proporciona el confinamiento ayudada por la
armadura longitudinal. Por tanto, la tensión de confinamiento dependerá de: la cuantía
de armadura, la posición del hormigón y de la carga axial.

En la figura 3.17 se representa la sección transversal de un pilar circular con
cercos separados una distancia s. En esta figura se aprecia la zona del centro de la
sección que está eficazmente confinada así como la zona exterior y la zona de
confinamiento no eficaz.

Se han desarrollado varios modelos para el hormigón confinado con resultados
cercanos a la experimentación. Entre ellos cabe citar los modelos de hormigón de KentPark (Park et al. 1982) de San Diego, válidos tanto para hormigón confinado como para
hormigón no confinado. Como se puede apreciar en la figura 3.17 estos modelos
suponen la existencia de una serie de arcos internos apoyados en la armadura transversal
(arcos de descarga) que permiten el confinamiento. Se ha incluido un anejo a este
capítulo donde se desarrolla uno de los modelos más extendidos de hormigón
confinado: el modelo de Mander-Richart.

ds

Centro eficazmente Hormigón exterior
confinado
A A

s'/4

SECCIÓN B-B

B B

s' s Hormigón
confinado
no ineficaz Hormigón exterior

ds-s'/2

ds

SECCIÓN A-A

Figura 3.17. Modelo de hormigón confinado para pilares circulares

<!-- p. 72 -->

PROPIEDADES DE LOS MATERIALES 72

3.7. ARMADURA PASIVA

En la mayoría de elementos estructurales como vigas, láminas, etc. hay zonas
que se encuentran a tracción. El hormigón por si solo es un material que tiene una baja
resistencia a tracción. Para solucionar este problema se introducen en la masa de
hormigón barras de acero que resisten la tracción que el hormigón no puede soportar. Si
las barras son colocadas sin tensión se les denomina armadura pasiva. También se
puede introducir armadura pasiva en zonas comprimidas, en este caso la armadura
trabaja junto con el hormigón a compresión.

Existe la posibilidad de colocar armadura tensada, que transmite su tensión a la
masa de hormigón, denominándose en ese caso armadura activa. La armadura activa
altera las zonas de tracción o compresión que se presentarían si dicha armadura no
existiese, ver figuras 1.3 y 1.4. Otros materiales como fibras de vidrio, lañas de acero,
fibras de carbono, etc. pueden emplearse para mejorar la resistencia a tracción del
hormigón, si bien su empleo es poco común.

Como ya hemos comentado, la función de la armadura pasiva es la de absorber
las tracciones que el hormigón no puede. Para garantizar su funcionalidad, la barra que
trabaja en tracción debe de estar anclada en zonas en las que no se requiera su
colaboración, a ser posible en zonas comprimidas.

Con objeto de mejorar la adherencia entre el acero y el hormigón, la armadura
pasiva se presenta generalmente corrugada (figura 3.18). La armadura pasiva se puede
presentar como: barras corrugadas, mallas electrosoldadas o armaduras básicas
electrosoldadas en celosía.

Los diámetros nominales7 bajo los que se presentan las barras corrugadas son:
6 – 8 – 10 – 12 – 14 – 16 – 20 – 25 – 32 y 40 mm.

Las mallas electrosoldadas tienen los siguientes diámetros nominales: 5 - 5.5 –
6 - 6.5 – 7 - 7.5 – 8 - 8.5 – 9 - 9.5 – 10 - 10.5 – 11 - 11.5 - 12 y 14 mm

Las armaduras básicas electrosoldadas en celosía, tanto lisas como corrugadas,
tienen los siguientes diámetros nominales: 5 – 6 – 7 – 8 – 9 – 10 y 12 mm.

7 Se denomina área nominal a la obtenida mediante el diámetro nominal. Y se denomina
área equivalente a la obtenida de considerar una barra lisa ideal con el mismo peso por
unidad de longitud que la barra corrugada correspondiente. Según la EHE el área
equivalente no será inferior al 95.5% del área nominal.

<!-- p. 73 -->

HORMIGÓN ESTRUCTURAL 73
Hernández-Gil

Figura 3.18. Armaduras según la EHE.
Tipo B 400 S:
Todas las corrugas tienen la misma inclinación, pero presentan separaciones diferentes
en cada uno de los sectores de la barra.
Tipo B 500 S:
Las corrugas de uno de los sectores tienen la misma inclinación y están uniformemente
separadas. Las del otro sector están agrupadas en dos series de la misma separación pero
distinta inclinación.
Tipo B 400 SD:
Todas las corrugas tienen la misma separación y la misma inclinación
Tipo B 500 SD:
Las corrugas están agrupadas en dos series de la misma separación pero distinta
inclinación, igual en ambos sectores.

El acero de las barras corrugadas se designa con la letra B seguido de su límite
elástico fy (correspondiente a una deformación remanente del 0.2%) y de la letra S si es
soldable o de las letras SD si tiene especiales características de ductilidad. Éstos últimos
aceros, los terminados en SD, son para zonas sísmicas. En la figura 3.17 y en la Tabla
3.3 podemos ver los distintos tipos de aceros de barras corrugadas considerados por la
EHE.

Tabla 3.3. Tipos de acero
Designación Clase de Límite Carga unitaria Alargamiento Relación
acero elástico fy de rotura fs en en rotura en fs/fy en
en N/mm 2 N/mm 2 % sobre base ensayo εmáx
de 5
≥ ≥ diámetros
≥
B 400 S Soldable 400 440 14 ≥ 1.05
B 500 S Soldable 500 550 12 ≥ 1.05
B 400 SD Soldable con 400 480 20 ≥ 1.20 9%
características
de ductilidad
B 500 SD Soldable con 500 600 ≤ 1.35
características
especiales de
ductilidad

<!-- p. 74 -->

PROPIEDADES DE LOS MATERIALES 74

El acero de las mallas electrosoldadas se designa por B500T. Estas mallas
están constituidas por barras corrugadas soldadas formando cuadriculas Este tipo de
armadura es muy interesante por su fácil colocación en obra.

Para el cálculo de elementos de hormigón se puede emplear el diagrama
tensión-deformación del acero de armaduras pasivas obtenido a partir de datos
experimentales (siempre que los ensayos cumplan con las características exigidas por la
normativa vigente) o bien el diagrama representado en la figura 3.19 (extraído del EC2).
El diagrama representado en la figura 3.19 es válido en compresión y en tracción. En
dicho diagrama fyk es el límite elástico o tensión de cedencia, k es la relación entre la
tensión máxima y el límite elástico (su valor está comprendido entre 1.05 y 1.35, según
el EC2), εuk es la deformación correspondiente a la tensión máxima y para εud la EHE
adopta el valor de 0.01 permitiendo llegar a 0.02 para aceros del tipo SD. En el caso de
adoptar como diagrama de diseño el correspondiente a la línea superior horizontal el
EC2 (al igual que la ACI-318) no limita la deformación del acero.

σs
Diagrama característico
kfyk kfyk

fyk kfyk/γs
fyd = fyk/γs

Diagrama de diseño

Es = 200000 N/mm2

εs
fyd/Es εud εuk

Figura 3.19. Diagrama característico y de cálculo tensión-deformación para
acero de armar

El valor fyk es el límite elástico o límite elástico característico y fyd es la
resistencia de cálculo del acero (fyd= fyk/γs).

El acero de la armadura pasiva (EHE y EC2) tiene un módulo de elasticidad o
módulo de deformación longitudinal de valor Es=200000 MPa, la densidad es de 7850
kg/m3 y el coeficiente lineal de dilatación térmica es de 10-5 ºC-1 . 8

8 El hecho de que el hormigón y el acero tengan el mismo coeficiente de dilatación
térmica es una condición sin la cual no serían compatibles.

<!-- p. 75 -->

HORMIGÓN ESTRUCTURAL 75
Hernández-Gil
3.8. ANCLAJE

Como se ha adelantado anteriormente, las barras de armadura pasiva deben
estar ancladas en el hormigón en zonas alejadas de donde se requiera su colaboración a
tracción, permitiendo así transmitir las tensiones a la masa de hormigón. Al menos estas
barras deberán estar ancladas en los extremos para llevar hasta ellos las tracciones. Una
parte esencial en el funcionamiento del anclaje es la adherencia entre la armadura pasiva
y el hormigón.

Como ya vimos en capítulo I, la adherencia barra-hormigón se consigue por
tres mecanismos: reacción química en la interfase hormigón-acero, retracción del
hormigón y corrugas. Años atrás bastaba sólo con los dos primeros procesos para
asegurar la adherencia y por eso se empleaban barras lisas. Debido a la mejor calidad de
los aceros (que pueden resistir mayores tracciones) fue necesario mejorar la adherencia
introduciendo las corrugas.

Si se introduce una barra de acero en un bloque de hormigón y se intenta
extraerla una vez que el hormigón ha endurecido se puede observar que el esfuerzo de
extracción (P) es tanto mayor cuanto más se haya introducido la barra en el hormigón
(figura 3.20a). Ese esfuerzo P tiene un valor límite correspondiente a la resistencia a
tracción de la barra (Pmax=Asfy). A la longitud mínima necesaria para que el esfuerzo P
sea igual a Asfy se le denomina longitud de anclaje (figura 3.20).

P P Longitud de anclaje

Longitud introducida
Pmax
Pmax
fbd

Longitud de anclaje

Longitud introducida

Figura 3.20a. Longitud de anclaje Figura 3.20b. Tensión última de adherencia

En la longitud de anclaje influyen varios factores: las calidades del acero y del
hormigón, el tipo de anclaje utilizado y la zona del hormigón que se esté considerando.

La influencia de las calidades del hormigón y del acero en la longitud de
anclaje es fácil de entender: cuanto mejor sea el hormigón menor longitud de anclaje
será necesaria, mientras que cuanto mejor sea el acero mayor habrá de ser la longitud de
anclaje.

<!-- p. 76 -->

PROPIEDADES DE LOS MATERIALES 76

Respecto a la influencia de la zona del hormigón donde se efectúa el anclaje es
necesario diferenciar entre zonas de buena adherencia y zonas de adherencia deficiente.
El origen de esta diferenciación está en la posibilidad de segregación durante el proceso
de hormigonado, con la consiguiente influencia en el mecanismo de adherencia. Se
consideran condiciones de buena adherencia si:

\- La barra tiene una inclinación de 45º a 90º con la horizontal. Horizontal
establecida durante el hormigonado.
\- En caso de que la barra tenga una inclinación de 0 a 45º se considera de
buena adherencia si: la pieza tiene menos de 250 mm de espesor en la
dirección del hormigonado, la barra está en la mitad inferior de la pieza o a
más de 300 mm de la superficie superior.

Si la barra no se encuentra en posición de presentar buena adherencia, entonces
se considera que tiene adherencia deficiente.

Los tipos de anclaje son: por prolongación recta, por patilla, por gancho, por
gancho en U y mediante barra transversal soldada (figura 3.21). Estos tipos de anclaje
están ideados para trabajar a tracción. Los diámetros interiores de los ganchos y patillas
deben de cumplir unos valores mínimos para evitar la degradación del hormigón y del
acero durante su funcionamiento: 4Ø para barras con Ø≤16 mm y 7 Ø para Ø>16 mm,
según el EC2 (para mayor detalle ver EC2).

a) Longitud básica de anclaje, lb, para b) Longitud equivalente para anclaje
cualquier forma medida a lo largo de la tipo patilla
línea media

c) Longitud equivalente para d) Longitud equivalente para e) barra transversal
anclaje tipo gancho anclaje tipo gancho en U soldada

Figura 3.21. Tipos de anclajes

La norma EHE plantea dos formas diferentes de calcular la longitud de anclaje.
La primera es idéntica a la del EC2. La segunda forma es un proceso simplificado
donde la longitud básica de anclaje lb vale: mØ2 centímetros para zonas de buena
adherencia y 1.4mØ2 para zonas de adherencia deficiente. El parámetro m depende de la

<!-- p. 77 -->

HORMIGÓN ESTRUCTURAL 77
Hernández-Gil
resistencia característica fck del hormigón y del tipo de acero (artículo 69 de la EHE2007) y Ø es el diámetro de la barra en centímetros.

El primer enfoque de la EHE en relación al cálculo de la longitud de anclaje es
más amplio. Cuando se intenta extraer la barra de la masa de hormigón (figura 3.20b) se
produce una tensión tangencial en la zona de contacto hormigón-acero. Para P=Pmax y si
la longitud introducida coincide con la longitud de anclaje, al valor de la tensión
tangencial se le denomina tensión última de adherencia fbd. Para barras corrugadas el
valor de la tensión última de adherencia es:

f bd = .2 25η1η2 f ctd (3.24)

donde:

fctd viene dado por la expresión 3.10
η1 es un coeficiente que depende de la zona de adherencia (1.0 si el barra
está en zona de buena adherencia y 0.7 si es de adherencia deficiente)
η1 1.0 si el diámetro de la barra Ø≤32 mm y (132- Ø)/100 si Ø>32 mm.

A partir de la ecuación anterior se obtiene lo que se denomina longitud básica
de anclaje lb.

φ2 φ f yd
πφl b f bd = f yd π → l b = (3.25)
4 4 f bd

La longitud de anclaje necesaria ( lb,net ) se calcula a partir de la expresión:

As , req
lb , net = aa lb ≥ lb , min (3.26)
As , prov

donde:

As,req y As,prov son las armaduras necesaria por cálculo y la dispuesta
lb,min es la longitud mínima de anclaje, para anclajes en tracción es
el mayor de los valores (0.3 lb,net, 0.3 lb y 10 Ø) y para
anclajes en compresión es el valor mayor de (0.6 lb,net, 0.6 lb y
100 mm).
aa es un coeficiente que depende del tipo de anclaje. En tracción
vale: 1 para prolongación recta, 0.7 para barras en tracción
ancladas dobladas (si el recubrimiento de hormigón
perpendicular al plano de doblado es al menos 3Ø en la zona
del gancho, patilla o anclaje en U). En compresión toma el
valor 1.

<!-- p. 78 -->

PROPIEDADES DE LOS MATERIALES 78

3.9. ARMADURA ACTIVA

Como veíamos al principio del texto, el hormigón resiste poco a tracción. Para
paliar este problema se colocan barras de acero en las zonas traccionadas del elemento
(armadura pasiva). Otra forma de solucionar el inconveniente de la baja resistencia a
tracción del hormigón consiste en forzar a que todo el hormigón trabaje a compresión,
lo que se logra introduciendo fuerzas de pretensado (figura 1.3). Las fuerzas de
pretensado se introducen mediante armaduras activas. Estas armaduras se presentan
bajo 3 tipos:

Alambre: Producto de sección maciza, procedente de un estirado en frío
o trefilado de alambrón que normalmente se suministra en
rollo. Los alambres se suministran en bobinas.
Barra: Producto de sección maciza, se suministra en elementos
rectilíneos.
Cordón: Formado por varios alambres arrollados helicoidalmente.

Se denomina tendón al conjunto de varias armaduras de pretensado paralelas
alojadas dentro de un mismo conducto.

Los alambres se presentan bajo los siguientes diámetros: 3-4-5-6-7-7.5-8-9.410 mm y están constituidos por acero de alto porcentaje de carbono (0.7 a 0.85%). La
materia prima del cable es un alambrón obtenido mediante laminado. Antes de procesar
el alambrón éste es calentado hasta unos 900ºC y enfriado lentamente para que el acero
sea más homogéneo. Posteriormente el alambrón es sometido a un proceso de trefilado
en frío. El trefilado se realiza en varias fases reduciendo paulatinamente el diámetro del
alambre y mejorando así su resistencia. La EHE designa los alambres en relación a su
carga unitaria máxima fmáx, ver tabla 3.4.

Tabla 3.4. Tipos de alambres
Designación Serie de diámetros Carga unitaria máxima fmáx
nominales, en N/mm2 ≥
en mm
Y 1570 C 9.4 – 10.0 1570
Y 1670 C 7.0 – 7.5 – 8.0 1670
Y 1770 C 3.0 – 4.0 – 5.0 – 6.0 1770
Y 1860 C 4.0 – 5.0 1860

El límite elástico fy (aquel que produce una deformación remanente del 0,2 %)
estará comprendido entre el 0.85 y el 0.95 de la carga unitaria máxima fmáx.

En elementos pretesos los alambres transmiten la fuerza de pretensado al
hormigón a través de la superficie de contacto. Los alambres (al no fabricarse mediante
procesos de laminado, como la armadura pasiva) son lisos y no presentan corrugas. Si
fuese necesario se le pueden practicar muescas, estando este uso reservado para
alambres y cordones en elementos pretesos de corta longitud tales como traviesas de
ferrocarril. Para mejorar aún más la adherencia el alambre se suele presentar rizado.

<!-- p. 79 -->

HORMIGÓN ESTRUCTURAL 79
Hernández-Gil
Muescas y rizado junto con el efecto Poisson (incremento de volumen a menor tensión)
y los demás mecanismos descritos anteriormente (retracción del hormigón y reacción
química en la interfase acero-hormigón) aseguran la adherencia de los alambres en los
elementos pretesos.

Los cordones están compuestos por varios alambres arrollados
helicoidalmente. Los más empleados son los cordones de 7 alambres. Una vez
arrollados se puede optar por dos procesos: calentar hasta unos 350ºC y luego enfriar
lentamente, produciendo cordones de relajación normal, o bien calentar hasta 350ºC
estando el cordón en tensión, dando lugar a cordones de baja relajación. La norma
EHE designa los cordones por su carga unitaria máxima fmáx, ver tabla 3.5.

Tabla 3.5. Tipos de cordones
Designación Serie de diámetros Carga unitaria máxima fmáx
Cordones de nominales en mm (área mm2) en
2 o 3 N/mm2 ≥
alambres
Y 1770 S2 5.6 – 6.0 1770
Y 1860 S3 6.5 – 6.8 – 7.5 1860
Y 1960 S3 5.2 1960
Y 2060 S3 5.2 2060
Y 1770 S7 16.0 1770
Y 1860 S7 9.3 – 13.0(99) – 15.2(140) – 1860
16.0(150)

Las barras se fabrican mediante estirado en frío. Su diámetro varía entre 20 y
40 mm. La carga unitaria máxima no será inferior a 980 MPa. Las barras pueden ser
roscadas o lisas, pero las barras lisas deben de tener los extremos roscados ya que su
sistema de pretensado es mediante rosca: se tensa la barra y se aprieta la tuerca. En la
figura 3.22 se representa una barra de pretensado.

Figura 3.22. Barras de pretensado

<!-- p. 80 -->

PROPIEDADES DE LOS MATERIALES 80

Alambres y cordones se suministran en bobinas, mientras que las barras lo
hacen en tramos rectos igual que la armadura pasiva; figura 3.23.

Figura 3.23. Bobina de cable S7.

El diagrama característico tensión-deformación para la armadura activa
(alambres, barras y cordones) puede ser suministrado por el fabricante (con las debidas
garantías) o , en su defecto, el representado en la figura 3.24 (artículo 38 de la EHE).
Este diagrama consta de un primer tramo recto de pendiente Ep y un segundo tramo que
responde a la ecuación 3.27 a partir del punto 0.7fpk de tensión.

σp ⎛ σp ⎞ 5
0 . 7 para σp ≥ 0 . 7f pk (3.27) εp = + 0 . 823 ⎜⎜ − ⎟⎟ E p ⎝ f pk ⎠

σp Diagrama característico
fpk
Diagrama de cálculo
fpd

Ep

0.002 =p

Figura 3.24. Diagrama tensión-deformación para armaduras activas

Como módulo de elasticidad o de deformación longitudinal se pueden adoptar
los valores de Ep=200000 MPa para alambres y barras y de Ep=190000 MPa para
cordones.

<!-- p. 81 -->

HORMIGÓN ESTRUCTURAL 81
Hernández-Gil
El término fpk tiene significados distintos en la EHE y en el EC2. En la norma
europea fpk corresponde a la resistencia a tracción y fp0.1k es la tensión que produce una
deformación remanente del 0.1 %, como se puede ver en la figura 3.25. Se denomina εuk
a la elongación unitaria para la carga máxima. Los tendones de pretensado deben
presentar una ductilidad adecuada, para lo cual se ha de verificar que; fpk /fp0,1k ≥ 1.1.

σp

fpk

fp0,1k

\=p
0,1%
εuk

Figura 3.25 Diagrama tensión-deformación típico del acero pretensado (valores
de tracción)

El EC2 propone como diagramas característico y de diseño los representados
en la figura 3.26 y recomienda como valor de la deformación unitaria límite εud =0.9 εuk.

σs
Diagrama característico
fpk

fp0,1k fpk/γs
fpd = fp0,1k/γs

Diagrama de diseño

Ep

εs
fpd/Ep εud εuk

Figura 3.26 Diagramas tensión-deformación característico y de diseño del
acero pretensado (valores de tracción)

<!-- p. 82 -->

PROPIEDADES DE LOS MATERIALES 82

En el apartado 3.8 se ha definido el concepto de longitud de anclaje en relación
con la armadura pasiva. En el caso de la armadura activa el anclaje se puede concentrar
en una longitud muy reducida (mediante cuñas o tuercas) o bien extenderse a lo largo de
una longitud mayor, como en el caso de la armadura pasiva. El anclaje localizado suele
ser típico de la armadura activa postesa mientras que el anclaje en longitud lo es de la
armadura activa pretesa.

El efecto Poisson es el mecanismo más importante para que se produzca el
anclaje a lo largo de una determinada longitud sin que exista ningún elemento mecánico
adicional (la corruga). Esto es debido a que la armadura bajo tensión experimenta una
reducción de su sección transversal. Cuando el alambre o cordón de pretensado se corta
(proceso de destesado en bancada) la tensión en los extremos se anula lo que implica
un aumento de su sección transversal, que ayuda a mejorar el anclaje (ver figura 3.27).

Longitud de transmisión
Figura 3.27. Longitud de transmisión

En el proceso de destesado, descrito en el párrafo anterior, el alambre o cordón
pasa de una tensión 0, en el extremo del elemento, a la tensión inicial de pretensado
P0/Ap, a una determinada distancia del extremos. La longitud necesaria para alcanzar el
valor P0 se conoce como longitud de transmisión. La longitud de transmisión se puede
calcular a partir de la EHE (artículo 70) o del EC2 o bien suponer que es 50 veces el
diámetro nominal para cordones ó 100 diámetros para alambres (método ACI).

Tanto la EHE como el EC2 suponen una tensión constante (fbpt) a lo largo de la
longitud de transmisión (lpt).

Cuando hay que pretensar una pieza de corta longitud, como una traviesa de
ferrocarril, la longitud de transmisión puede resultar excesiva. En esos casos se
practican unas muescas en frío en la zona de anclaje, reduciéndose así la longitud de
transmisión.

<!-- p. 83 -->

HORMIGÓN ESTRUCTURAL 83
Hernández-Gil
3.10. RELAJACIÓN

En la figura 3.11 se representaban los fenómenos de fluencia y relajación.
Como ya vimos, la relajación es la pérdida de tensión bajo deformación constante
(figura 3.28) siendo este fenómeno especialmente importante en el acero de pretensado.
La relajación depende del tiempo, de la temperatura y del nivel de tensión. Para valores
de tensión inferiores a 0.5fpk la relajación se puede considerar despreciable.

σp

σpi

σpi-∆σp

Ep,ef

Ep

\=p

Figura 3.28. Relajación del acero de las armaduras activas

Por efecto de la relajación el valor del módulo de deformación longitudinal Ep
varía. El nuevo valor Ep,ef (figura 3.28) se puede deducir a partir de los valores de la
relajación.

La relajación ρ(ρ=∆σp/σpi) para una tensión inicial σpi comprendida entre 0.5 y
0.8 de fmáx y para un tiempo t se puede estimar a partir de la ecuación 3.28:

⎛∆σp ⎞
K 1 + K 2 log( t ) (3.28) log( ρ) = log⎜⎜ ⎟⎟ =
⎝ σpi ⎠

donde ∆σp es la pérdida de tensión por relajación y K1 y K2 son coeficientes que
dependen del tipo de acero y de la tensión inicial. La ecuación anterior es una recta si
los ejes de referencia se presentan en escala logarítmica:

Log ρ

Log t

120 horas 1000 horas

Figura 3.29. Relajación en función del tiempo

<!-- p. 84 -->

PROPIEDADES DE LOS MATERIALES 84

Bastará con que el fabricante suministre datos de la relajación a 120 y 1000
horas para obtener los valores de K1 y K2 en cada nivel de tensión.

Se denomina valor final de la relajación ρf al correspondiente a la vida
estimada de la obra en horas o a 106 de horas.

A falta de datos experimentales la norma EHE propone valores de la relajación
a 1000 horas (ρ1000) para tensiones iniciales de 0.6, 0.7 y 0.8 de fmáx.

Tabla 3.6. Valores de relajación a 1000 horas. En %
0.6 fmáx 0.7 fmáx 0.8 fmáx
Alambres y cordones 1.0 2.0 5.5
Barras 2.0 3.0 7.0

La EHE proporciona además la variación en la relajación desde tiempo 0 hasta
las 1000 horas en porcentajes:

Tabla 3.7. Variación porcentual de la relajación de 0 a 1000 horas
1 5 20 100 200 500 1000
% de pérdidas hasta 1000 horas 25 45 55 70 80 90 100

Asimismo para estimar la relajación a partir de las 1000 horas la EHE propone
la siguiente fórmula:

⎛ t ⎞ k
ρ( t ) = ρ1000 ⎜ ⎟ (3.29)
⎝ 1000 ⎠

⎛ ρ1000 ⎞
donde: k = log⎜⎝ ρ100 ⎟⎠

<!-- p. 85 -->

HORMIGÓN ESTRUCTURAL 85
Hernández-Gil
3.10. FATIGA

Se define como fatiga a la relación entre la diferencia de tensiones máxima y
mínima (σs,máx – σs,mín) y el número de ciclos que dicha carga es repetida hasta causar el
agotamiento del material. En hormigón armado y pretensado la fatiga del acero es
anterior a la de hormigón. En la figura 3.30 se ha representado la relación entre rango de
tensiones y ciclos de carga necesarios hasta la rotura:

σmáx -σmín (N/mm2)
500

400

300

200

100

105 106 107 Nº de ciclos hasta rotura

Figura 3.30. Curva de fatiga

La norma EHE propone límites a la diferencia de tensiones (σs,máx –σs,mín) tanto para
armadura pasiva como activa por debajo de los cuales no se presentan problemas de
fatiga.

<!-- p. 86 -->

PROPIEDADES DE LOS MATERIALES 86

Ejercicios propuestos

3.1. Para estimar las flechas en hormigón es necesario obtener con gran
precisión el valor del módulo de deformación longitudinal Ecm. El rango de
deformaciones (ε) a considerar va desde 0 hasta 0.001. ¿Se pueden
emplear los valores de Ecm obtenidos a partir del gráfico de la figura 3.8?.
¿Qué inconvenientes tendría el usarlo?.

3.2. La norma EHE propone dos factores de corrección, αy β, en función del
tipo de árido y en función de la edad del hormigón. Explica brevemente en
qué consisten.

3.3. En el problema de fluencia y retracción, calcular el efecto de deformación
por temperatura si a los 50 días pasa de 20ºC a 40ºC. Rehacer la figura
3.15.

3.4. Explica brevemente el efecto beneficioso del confinamiento del hormigón.
Intenta explicar por qué las distintas normativas son reticentes al empleo
de la mejora de resistencia en el dimensionamiento de pilares de
hormigón, y que tiene que ver esto con la deformación del pilar.

3.5. Busca en la norma EHE la solución al siguiente problema: se ha dejado a
la intemperie la armadura pasiva y ha aparecido gran cantidad de óxido,
que se ha eliminado mediante cepillado con cerdas de acero. ¿Se puede
colocar o es preciso realizar algún tipo de comprobación?.

3.6. Normas antiguas daban un valor mínimo a la resistencia del hormigón fck
en función de la resistencia del acero (B-400-S o B-500-S). ¿Qué sentido
puede tener esto en relación con el anclaje?

3.7. La relajación depende del tiempo y del nivel de tensión, sin embargo en la
ecuación 3.29 sólo aparece como variable el tiempo. ¿Dónde interviene el
nivel de tensión?.

<!-- p. 87 -->

HORMIGÓN ESTRUCTURAL 87
Hernández-Gil
Referencias

ACI 318-05 (2005). Building Code Requirements for Structural Concrete, American
Concrete Institute, Farmington Hills, Michigan.

EHE. Instrucción de Hormigón Estructural (borrador 2007). Secretaría General Técnica.
Ministerio de Fomento. Madrid.

Eurocode 2 (2002): Design of concrete structures- Part 1: General rules and rules for
buildings prEN 1992-1-1. European Committee for Standardization. Brussels.

Nawy (2003). Reinforced Concrete. A Fundamental Approach. 5th edition. PrenticeHall. New Jersey.

Park, R., and Paulay, T. Reinforced Concrete Structures, John Wiley & Sons, New
York. (1975).

SIA 162 (1989), Norme SIA 162: Ouvrages en bétón, Société suisse des ingénieurs et
des architectes, Zurich, Suiza.

Walther, R, and Miehlbradt, M. (1990), Dimensionnement des Structures en Béton,
Presses Polytechniques et Universitaires Romandes, Lausanne, Suiza.

<!-- p. 88 -->

PROPIEDADES DE LOS MATERIALES 88

Pilar confinado mediante empresillado metálico
Cortesía de DETECSA www.detecsa.es

<!-- p. 89 -->

HORMIGÓN ESTRUCTURAL 89
Hernández-Gil
ANEJO. Modelo de arcos de descarga de hormigón confinado
(o de Mander-Richart)

Como hemos visto, la resistencia máxima del hormigón aumenta si éste se
encuentra confinado. Los valores de resistencia máxima (fcc) y la deformación
unitaria correspondiente (εcc) en función de la tensión de confinamiento (σconf) se
pueden tomar como:

fcc = fc + k1σconf
σconf ⎞ A3.1
1 k 2 ⎟⎟ εcc = εc 0 ⎛+⎜⎜ ⎝ fc ⎠

Las expresiones A3.1 fueron fruto de las primeras investigaciones sobre
hormigón confinado.

Tensión (σc) Hormigón confinado Rotura del
confinamiento
fcc

Hormigón no confinado

fc Prolongación para la zona no confinada

εct εsp
εc0 2εc0 εcc εcu
fct
Deformación unitaria εc
Figura A3.1 Modelo tensión – deformación de hormigón confinado y no confinado
para carga monótona.

En la figura A3.1, la resistencia (o tensión máxima) y la deformación
correspondiente, para el caso de hormigón no confinado, son fc y εc0,
respectivamente. Los coeficientes k1 y k2 de las expresiones A3.1 dependen de la
presión lateral y del tipo de hormigón. Richart (1928) obtuvo experimentalmente
k1=4.1 y k2=5k1. En investigaciones recientes (Pantazopoulou S.J.) se han

<!-- p. 90 -->

PROPIEDADES DE LOS MATERIALES 90

obtenido valores similares aunque se ha encontrando alguna variación para
hormigones de alta resistencia.

El Eurocódigo 2 propone también valores de las tensiones máximas para
hormigones confinados. No obstante, estas expresiones no son aplicables
directamente puesto que es necesario conocer el valor de la tensión de
confinamiento. Hay que tener en cuenta que el confinamiento se logra
principalmente por la armadura transversal y por la manera en la que ésta está
colocada y que, por tanto, interesa que los modelos tensión-deformación sean
función tanto de la armadura existente como de su disposición.

El modelo básico tensión-deformación (σc-εc) propuesto por Popovics (1973)
para hormigón confinado bajo carga cuasi-estática y monótona es:

fcc xr σc = r r − 1 + x
εc x =
εcc
⎡ ⎛ fcc ⎞ ⎤ A3.2 εcc = εc 0 ⎢1 + 5⎜⎜ − 1⎟⎟ ⎥ ⎣ ⎝ fc ⎠ ⎦
E c r =
E c − E sec
fcc E sec =
εcc

donde Ec es el módulo tangente de deformación longitudinal (los autores de este
modelo emplearon Ec =5000 cf MPa).

Para definir el comportamiento del hormigón en la zona no confinada este
modelo supone que a partir de una deformación 2εc0 (εc >2εc0) existe una
prolongación recta de la curva hasta la intersección con el eje de abscisas (εc =εsp),
como se puede ver en la figura A3.1.

Modelo de arcos de descarga

En la práctica, el confinamiento lo ejercen las armaduras transversal y
longitudinal sobre el núcleo de la sección. Por efecto Poisson el hormigón
comprimido longitudinalmente tiende a dilatar transversalmente pero la armadura
transversal se lo impide, formándose unos arcos de descarga internos apoyados en
los puntos de la armadura más inmovilizada. Se entiende así que en la figura A3.2,

<!-- p. 91 -->

HORMIGÓN ESTRUCTURAL 91
Hernández-Gil
para un mismo diámetro de armaduras y una misma separación de la armadura
transversal, la sección a presente un confinado menos eficaz que las secciones b y
c.

Zona confinada no eficaz Zona eficazmente confinada

a b Zona no confinada c

Figura A3.2 Arcos de descarga y zona no confinada, confinada no eficaz y confinada
eficaz.

Se define núcleo de la sección (Ac) al área situada entre la línea media de la
armadura transversal (cercos o espiras). Esta definición es necesaria para poder
operar cómodamente con el modelo de hormigón confinado (σc-εc) dada la
dificultad que tendría operar con el área eficazmente confinada (Ae) debido a que ésta
varía tanto a lo largo de la pieza como en la propia sección transversal.
ds

Núcleo Hormigón exterior
eficazmente
confinado
A A

s'/4

SECCIÓN B-B

B B

s' s Hormigón
ineficazmente 45º
confinado Hormigón exterior

ds-s'/2 s'/4

ds

SECCIÓN A-A

Figura A3.3 Núcleo de hormigón eficazmente confinado para armadura transversal
circular.

<!-- p. 92 -->

PROPIEDADES DE LOS MATERIALES 92

En la figura A3.3 se observa la variación (en dirección longitudinal) del núcleo
eficazmente confinado para una columna circular con cercos circulares separados a
una distancia s.

Sea σconf la presión lateral ejercida por la armadura uniformemente repartida
sobre la superficie del núcleo de la sección, Ac. En realidad, esta presión se ejerce
sobre el exterior de Ae (zona eficazmente confinada) que, como ya se ha
comentado, no tiene un valor constante y que es menor que Ac (núcleo de la
sección). Para poder operar con el núcleo de la sección se define una presión lateral
eficaz (σe,conf) que actúa en el exterior del núcleo de la sección (Ac) y produce el
mismo efecto. Lógicamente, al aumentar el área de actuación, la presión lateral
eficaz será menor que la presión lateral de confinamiento (σe,conf \< σconf ):

σe , conf = σconf k e
Ae k e = A3.3
Acc
Acc = Ac (1 − ρcc )

Acc es el área de hormigón dentro del núcleo de la sección, ρcc es la relación de la
armadura longitudinal respecto al área del núcleo de la sección (As/Ac). El
parámetro ke se denomina coeficiente de confinamiento eficaz.

Confinamiento eficaz en pilares circulares

Consideremos la columna circular de la figura A3.3 con cercos circulares
de área As,90 separados una distancia s (distancia libre s’ ). El diámetro de la línea
media de los cercos es ds. Se supone que el arco de descarga forma una parábola
con una inclinación de salida de 45 grados. El área confinada eficaz (a media
distancia entre los cercos) y el área de hormigón dentro del núcleo de la sección
son, respectivamente:
π⎛ s ' ⎞ 2 π 2 s ' ⎞ 2 Ae = ⎜ d s − ⎟ = d s ⎛−⎜⎜ 1 ⎟⎟
4 ⎝ 2 ⎠ 4 ⎝ 2d s ⎠ A3.4
π 2 Acc = Ac (1 − ρcc ) = d s (1 − ρcc )
4

y, en este caso, el coeficiente de confinamiento eficaz, ke es:

<!-- p. 93 -->

HORMIGÓN ESTRUCTURAL 93
Hernández-Gil
⎛−1 s ' ⎞ 2 ⎜⎜ ⎟⎟ ⎝ 2d s ⎠ k e = A3.5
1 − ρcc

Para deducir la expresión de la presión lateral de confinamiento se plantea
el equilibrio de medio cerco circular, figura A3.4:

2 As ,90 f y ,90 = σconf sd s A3.6

siendo fy,90 la tensión máxima de la armadura del cerco. Si se define ρs como la
cuantía geométrica de la armadura transversal respecto del núcleo de la sección:

As ,90πd s 4 As ,90
ρs = = A3.7
π 2 d s s d s s
4

fy,90As,90

σconf ds

fy,90As,90

Figura A3.4 Presión de confinamiento.

los valores de la presión lateral de confinamiento y de la presión lateral eficaz de
confinamiento se pueden obtener a partir de las expresiones A3.3, A3.6 y A3.7:

1
σconf = ρs f y ,90
2
A3.8
1
σe , conf = k e ρs f y ,90
2

Una vez conocida la tensión eficaz de confinamiento se pueden calcular
los valores de resistencia máxima del hormigón confinado (fcc) y la deformación

<!-- p. 94 -->

PROPIEDADES DE LOS MATERIALES 94

unitaria correspondiente (εcc) empleando la expresión A3.11. Estos valores de fcc y
εcc se pueden introducir en la expresión A3.2 y obtener el modelo tensióndeformación para hormigón confinado.

Confinamiento eficaz en secciones rectangulares

En secciones rectangulares, como en el caso anterior, se supone que las
parábolas (arcos de descarga) forman una tangente inicial de 45º. En este tipo de
secciones las parábolas serán tanto verticales como horizontales.
Geométricamente, se puede determinar que la altura de una parábola con una
cuerda de valor w’ (ver figura A3.5) y tangente inicial de 45º es de w’/4 y que su
área es igual a (w’)2/6. Teniendo en cuenta lo anterior, el área ineficazmente
confinada a nivel del cerco para n parábolas formadas entre n barras longitudinales
inmovilizadas es:
2 n (w i ' ) A3.9 Ai = ∑ i = 1 6

donde wi es el arco de cada una de las parábolas de descarga. Si se tiene en cuenta
además la existencia de parábolas verticales entre los distintos niveles de cercos, se
puede calcular el área eficazmente confinada a media distancia entre los cercos
como:
2 ⎞ s ' ⎞ s ' ⎞ ⎛ n (w i ' ) ⎛− ⎛− A3.10 ⎜⎜ 1 ⎟⎟ ⎜⎜ 1 ⎟⎟ c d c − ∑ ⎟⎟ Ae = ⎜⎜ b i =1 6 ⎠⎝ 2bc ⎠⎝ 2d c ⎠ ⎝

donde bc y dc son las dimensiones del núcleo de la sección, o sea, el área encerrada
por la línea media de los cercos exteriores siendo además bc ≥ dc.

A partir de las definiciones dadas en las expresiones A3.3 se puede
formular la siguiente expresión del coeficiente de confinamiento ke.

n (w i ' ) ⎛−1 2 ⎞⎛−1 s ' ⎞⎛−1 s ' ⎞ ⎜⎜ ∑ ⎟⎟⎜⎜ ⎟⎟⎜⎜ ⎟⎟ i =1 6 bc d c ⎠⎝ 2bc ⎠⎝ 2d c ⎠ ⎝ k e = A3.11
1 − ρcc

Imponiendo el equilibrio de fuerzas en las direcciones x e y
respectivamente, se obtiene que:

1 Se pueden emplear modelos más sofisticados para este mismo fin.

<!-- p. 95 -->

HORMIGÓN ESTRUCTURAL 95
Hernández-Gil
Asx ,90 f y , 90 = σconf , x s d c
A3.12
Asy ,90 f y ,90 = σconf , y s bc

donde:

Asx,90 y Asy,90 son las áreas de las armaduras transversales según las direcciones
x e y respectivamente
σconf,x y σconf,y son las presiones laterales de confinamiento según x e y,
respectivamente.

Núcleo
eficazmente y
confinado w’

dc-s’/2
dc

A A
x
bc

SECCIÓN B-B

B B

s' s Hormigón
ineficazmente 45º
confinado Hormigón exterior
\-recubrimiento-
bc-s'/2

bc

SECCIÓN A-A

Figura A3.5 Núcleo de hormigón eficazmente confinado para armadura
transversal rectangular.

De la expresión anterior se pueden deducir la presión lateral de
confinamiento y la presión lateral eficaz de confinamiento en las direcciones x e y:

<!-- p. 96 -->

PROPIEDADES DE LOS MATERIALES 96

Asx , 90 f y ,90
σconf , x = = ρx f y ,90
sd c
σe , conf , x = k e ρx f y ,90
A3.13
Asy , 90 f y ,90
σconf , y = = ρy f y , 90
sd c
σe , conf , y = k e ρy f y , 90

donde ke viene dado por la expresión A3.11.

Conocidos los valores de las tensiones eficaces de confinamiento en ambas
direcciones se puede recurrir a un modelo tridimensional de rotura y obtener una
expresión para fcc. Mander (1988) propuso el gráfico de la figura A3.6 para el
cálculo de fcc. Con este valor de fcc se puede emplear el modelo tensión-deformación
para hormigón confinado dado por la expresión A.3.2.

Para el caso de confinamiento circular o rectangular igual en las
direcciones x e y , se puede emplear la siguiente expresión (Mander 1988):

⎛ 7 . 94σe , conf σe , conf ⎞ 1 . 254 + 2 . 254 1 + − 2 A3.14 ⎟⎟ fcc = fc ⎜⎜ − f c fc ⎝ ⎠

<!-- p. 97 -->

HORMIGÓN ESTRUCTURAL 97
Hernández-Gil

Relación de resistencias fcc/fc
σe,conf,2/fc
mayor

σe,conf,1= σe,conf,2
confinamiento
de
Relación
Relación de confinamiento menor σe,conf,1/fc

Figura A3.6 Incremento de la resistencia a compresión en secciones
rectangulares confinadas por tensiones ortogonales.

La deformación unitaria última del hormigón (εcu), ver figura A3.1, se debe
a la rotura del confinamiento y puede aproximarse por (Paulay 1992):
f y ,90 εsm
εcu = 0 . 004 + 1 . 4ρs A3.15
fcc

donde εsm es la deformación del acero correspondiente a la máxima tensión de
tracción y ρs es la cuantía volumétrica de la armadura transversal. Para secciones
rectangulares ρs= ρx+ρy, donde ρx y ρy vienen definidos en la expresión A3.13. Los
valores de εcu están comprendidos entre 0.012 y 0.05.

<!-- p. 98 -->

PROPIEDADES DE LOS MATERIALES 98

Referencias

Blume, J. A., Newmark, N. M., and Corning, L. H. (1961). Design of Multistory Reinforced
Concrete Buildings for Earthquake Motions, Portland Cement Association, Skokie, Illinois.

Hernández-Montes, E., Aschheim, M and Gil-Martín, L.M. (2004). “The impact of optimal
longitudinal reinforcement on the curvature ductility capacity of reinforced concrete
column sections”. Magazine of Concrete Research, 56, No. 9, Noviembre, 499-512.

Mander J. B., M.J.N. Priestley and R. Park (1988). "Theoretical Stress-Strain Model for
Confined Concrete". Journal of Structural Engineering. Vol 114, Nº 8, Agosto 1988. ASCE.

Paulay T., Priestley M.J.N. Seismic Design of Reinforced Concrete and Masonry Buildings. John
Wiley & Sons. 1992.

Sheikh S.S., Yeh C.C. (1992). "Analytical Moment-Curvature Relations for Tied Concrete
Columns". Journal of Structural Engineering. Vol. 118, No.2, Febrero, 1992. ASCE.

<!-- p. 99 -->

HORMIGÓN ESTRUCTURAL 99
Hernández-Gil
Ejemplo2

En la figura A3.7a se representa una sección cuadrada de 0.5 m de lado. El
hormigón es HA-25 y el acero B-400-S. La armadura longitudinal está compuesta
por 5 Ø20 en cada cara con un total de 16 Ø20. Se han dispuesto cercos y cruces
de Ø12 cada 8 centímetros (confinamiento propuesto para esta sección por la
ACI-318-05 para zonas de alto riesgo sísmico). En la figura A3.7b se ha
representado el diagrama momento-curvatura correspondiente a esta sección
solicitada por un axil de compresión constante de 1500 kN. Para el núcleo de la
sección se ha considerado el modelo de arcos de descarga y para el exterior de la
sección un modelo de hormigón no confinado. El punto 1 corresponde a la rotura
de la zona exterior: desprendimiento del recubrimiento. El punto 2 corresponde a
la rotura del confinamiento.

0.5 m

Cercos y cruces
∅12 a 80mm
a

0.05 m
recubrimiento

600 1 2
(kN·m)

400 b Momento

200

100 200 300 400
Curvatura (x1000 m -1)

Figura A3.7. Análisis momento-curvatura mediante modelo de arcos de
descarga.

2 Para poder entender este ejercicio es necesario haber estudiado el capítulo de flexión.

<!-- p. 100 -->

LA FUERZA DE PRETENSADO 100

<!-- p. 101 -->

HORMIGÓN ESTRUCTURAL 101
Hernández-Gil

CAPÍTULO IV

LA FUERZA DE PRETENSADO

Viga pretensada tipo artesa, antes de destesar.

La fuerza de pretensado es de tal importancia en hormigón estructural que
requiere un capítulo especial en el que se estudiará cómo se introduce y cómo varía su
valor a lo largo del trazado del tendón de pretensado. Dependiendo de que el pretensado
sea posteso o preteso, la fuerza de pretensado tendrá características muy diferentes,
tanto en la forma de ser introducida como en el valor que tenga a lo largo de la viga del
elemento estructural. En la figura 4.1.a podemos ver una bancada de fabricación de dos
vigas mediante pretensado preteso: primero se tesa el tendón y posteriormente se
hormigona. Este proceso se puede ver en la figura 4.2. La figura 4.1.b corresponde a
una viga simplemente apoyada fabricada mediante pretensado posteso, en este caso la
viga se ha hormigonado con la vaina y cuando el hormigón ha endurecido se procede a
tesar la armadura activa.

<!-- p. 102 -->

LA FUERZA DE PRETENSADO 102

Gato L = Longitud inicial

a

Tendón
Vaina

b

Figura 4.1. Vigas pretesas y postesas, a y b respectivamente.

Inicialmente, el gato introduce una fuerza de tesado P0 (tanto en pretesado
como en postesado) que proporcionará una tensión σP0 a la armadura activa. Esta
tensión, según la EHE, deberá ser menor de 0.75 de la carga unitaria máxima
característica (fpmax,k) y menor de 0.90 del límite elástico característico (fpk) aunque
momentáneamente puede alcanzar el 0.85 y 0.95 respectivamente.

Figura 4.2. Viga pretesa con la armadura activa tesada antes de hormigonar

<!-- p. 103 -->

HORMIGÓN ESTRUCTURAL 103
Hernández-Gil

4.1. LAS PÉRDIDAS DE PRETENSADO

El valor de P0, transmitido por el gato a los tendones, disminuye desde el
primer instante debido a varios factores (pérdidas). Estas pérdidas se pueden dividir en
pérdidas instantáneas y pérdidas diferidas, tabla 4.1.

Tabla 4.1. Pérdidas en la fuerza de pretensado, según la EHE
Pérdidas instantáneas Nombre EHE Pérdidas diferidas Nombre EHE
Rozamiento ∆P1 Retracción del hormigón
Penetración de cuñas ∆P2 Fluencia del hormigón ∆Pdif
Acortamiento elástico ∆P3 Relajación del acero

4.2. PÉRDIDAS POR ROZAMIENTO

Las pérdidas por rozamiento a lo largo del tendón sólo afectan a las armaduras
postesas. Como podemos intuir de la figura 4.1.a la fuerza P0 introducida antes de
hormigonar tiene el mismo valor a lo largo de todo el tendón. En la figura 4.1.b se tensa
desde el extremo izquierdo y, como consecuencia del rozamiento a lo largo de la vaina,
la fuerza de pretensado en el extremo derecho será menor.

En la figura 4.4. se representa un trozo de tendón de longitud dx cuyo trazado,
en esa longitud, varía un ángulo dα. El tendón está sometido en sus extremos a unas
fuerzas de pretensado P y P-dP lo que produce una acción normal de valor
2·P·sen(dα/2). A su vez la vaina ejerce sobre el tendón una fuerza vertical igual y de
sentido contrario, N. Si el coeficiente de rozamiento entre el tendón y la vaina que lo
aloja es µ, la pérdida por rozamiento será µN. Si el ángulo αes pequeño se puede tomar
la aproximación sen(dα/2)≈dα/2 y la pérdida por rozamiento debido a la variación de
ángulo será µPdα, siendo µ el coeficiente de rozamiento en ángulo.

<!-- p. 104 -->

LA FUERZA DE PRETENSADO 104

Trompeta

Vaina

Figura 4.3. Viga postesa. Se aprecia la vaina y la trompeta colocadas antes de
hormigonar. En el croquis ya está hormigonada.

dα
P-dP
P
N
n dα/2

t

dx

Figura 4.4. Pérdidas de rozamiento en ángulo.

<!-- p. 105 -->

HORMIGÓN ESTRUCTURAL 105
Hernández-Gil

Además del rozamiento en ángulo existe otro rozamiento a lo largo del tendón
que es independiente del ángulo del trazado y que depende del diámetro del conducto o
vaina que aloje al tendón, del tipo de tendón y de la forma en que se aloje en el interior
del conducto. Las pérdidas asociadas este tipo de rozamiento en un dx de longitud serán
K·P·dx, donde K es el coeficiente de rozamiento en recta o parásito y P la fuerza de
pretensado. El origen de este rozamiento parásito está en la ondulación relativa existente
entre la vaina y el tendón, figura 4.5.

Rozamiento

Tendón
Vaina

Figura 4.5. Efecto parásito en tramos rectos

Sumando los dos tipos de rozamiento:

dP = µP dα + K P dx

e integrando:

P0 dP α x resolviend o − (µα+ Kx ) x = P0 e ∫ = µ∫ dα+ K ∫ dx ⎯⎯ ⎯ ⎯⎯→ P P 0 0 (4.1)Px
⎯⎯o bien⎯→ ∆ P1 = P0 [ 1 − e − (µα + Kx ) ]

donde P0 es la fuerza de tesado, Px es la fuerza de pretensado a una distancia en
horizontal igual a x y α es la variación acumulada del ángulo del trazado en la longitud
x.

El valor del coeficiente µ depende de las características del tendón y de la
vaina y varía de 0.05 a 0.5. El coeficiente de rozamiento parásito K, depende de µ y de
la sinuosidad de la vaina y varía de 0.0003 a 0.0066 por metro. La EHE da los valores
para ambos coeficientes de rozamiento para tendones cuyos elementos se tesen
simultáneamente y para pérdidas concentradas en desviadores.

<!-- p. 106 -->

LA FUERZA DE PRETENSADO 106

4.3. GEOMETRÍA DEL POSTESADO

En estructuras postesadas el trazado habitual es el parabólico. Para vigas
simplemente apoyadas el trazado corresponde a una parábola simple, tal y como
podemos ver en la figura 4.1.b. En el caso de vigas continuas se disponen parábolas
encadenadas que serán convexas en los apoyos y cóncavas lejos de ellos, figura 4.6.

Excentricidad máxima en vano Excentricidad máxima en apoyo

Figura 4.6. Viga continua de tres vanos

Antes de evaluar las pérdidas por rozamiento vamos a recapitular sobre la
geometría de la parábola.

y

2
e0 ⎛ x ⎞
y = e0 ⎜⎜ ⎟⎟ ⎝ L0 ⎠

α (x)

x
L0

Figura 4.7. Parábola simple

Sea la parábola de la figura 4.7, que pasa por el origen y tiene pendiente
horizontal en éste. Las ecuaciones del radio de curvatura R y de la variación del ángulo
α, ambas en función de x, son:

1 y ′′ L20 = k = 3 ⇒ R ( x = 0 ) =
2 R 2 2e0 ( 1 + y ′ ) (4.2)
2e0 2e0 tg(α( x ) ) = 2 x ⇒ α( x = L0 ) ≈
L0 L0

<!-- p. 107 -->

HORMIGÓN ESTRUCTURAL 107
Hernández-Gil

En el caso de parábolas encadenadas, como las de la figura 4.8, el
planteamiento es similar. Denominemos L1, L2 y L3 a las longitudes (en horizontal) de
cada parábola dentro del primer vano.

Parábola 2 Parábola 3 Parábola 4

h2
Punto de inflexión e2
h=e1+e2
e1

Parábola 1

Punto inferior

L1 L2 L3

Figura 4.8. Parábolas encadenadas

En el punto inferior las parábolas 1 y 2 ambas parábolas tienen pendiente
horizontal. Conocidos L1 y e1 es posible determinar, a partir de las fórmulas de la
parábola (ecuaciones 4.2), el radio de curvatura en el punto inferior y la variación de
ángulo.

Siguiendo con la notación empleada en la ecuación 4.2 y en la figura 4.8, para
la parábola 2 se tiene que: e0=h-h2 y L0=L2. Conocidos estos datos se pueden calcular el
radio de curvatura en el punto inferior y la variación de ángulo (ecuaciones 4.2).
Análogamente se procede con la parábola 3, para la que L0=L3 y e0=h2.

Es interesante observar que en el punto de inflexión se unen las parábolas 2 y 3
y, por tanto, en este punto ambas parábolas tendrán la misma pendiente:
2 (h − h2 ) 2 h2 = (4.3)
L2 L3

despejando h2:

L3 o bien h2 h h2 = h ⎯⎯ ⎯→ =
L2 + L3 L3 L2 + L3

en la ecuación anterior, el primer miembro corresponde a la pendiente de la recta que
une el punto de inflexión con el punto superior de la parábola 3 mientras que el segundo
miembro es la pendiente de la recta que une el punto superior de la parábola 3 con el
punto inferior de la parábola 2. De lo anterior se deduce que los siguientes puntos están
alineados: inferior de la parábola 2, punto de inflexión y superior de la parábola 3. Por
tanto, conocido el punto inferior de la parábola 2, el punto superior de la parábola 3 y L3
queda determinado el punto de inflexión.

El punto superior de la parábola 3 tiene pendiente horizontal y coincide con el
punto superior de la parábola 4. Con una construcción similar a la efectuada entre las

<!-- p. 108 -->

LA FUERZA DE PRETENSADO 108

parábolas 2 y 3 podemos hallar la variación de ángulo a lo largo de todo el trazado del
tendón de pretensado.

Las parábolas encadenadas convexas (parábolas 3 y 4), cuya misión
fundamental es dar continuidad al trazado, suelen ser ajustadas con radios mínimos. En
la tabla 4.2 se recogen los radios mínimos recomendados en función del diámetro
interior de la vaina.

Tabla 4.2. Valores mínimos de radios de curvatura
Diámetro de la vaina (mm) 45-55 65-80 85-95 100-110
Radio mínimo de curvatura (m) 3.5 4.5 5.0 7.0

Otro factor a tener en cuenta es la excentricidad existente entre el c.d.g. del
tendón y el centro de la vaina (figura 4.9). En la tabla 4.3 se indican valores
aproximados de esta excentricidad, que han sido extraídos de catálogos técnicos.

Excentricidad en el punto
inferior

Excentricidad del
punto superior

Figura 4.9. Excentricidades en los puntos extremos

<!-- p. 109 -->

HORMIGÓN ESTRUCTURAL 109
Hernández-Gil

Tabla 4.3. Valores de excentricidades. Extraidos de varios catálogos comerciales.
Nº de cordones S7 de 13.0 Diámetro de la vaina Excentricidad
mm (mm) (mm)
3 32 7
4 41 7
7 51 8
12 64 11
19 80 13
22 86 12
31 102 14
55 140 23
Nº de cordones S7 de 15.2
mm
3 38 5
4 51 5
7 57 10
12 76 13
19 100 19
31 125 22
55 165 30

Figura 4.10. Gato empleado en armadura pretesa para tesar un solo cordón.

<!-- p. 110 -->

LA FUERZA DE PRETENSADO 110

4.4. PÉRDIDAS POR PENETRACIÓN EN CUÑA

En armadura postesa se suele emplear anclaje medianted cuñas1 (figura 4.12).
En este tipo de armaduras, una vez que el gato ha aplicado la fuerza de tesado al tendón,
hay que proceder a anclar el tendón y extraer el gato. Éste proceso conlleva una nueva
pérdida en la fuerza de pretensado.

La pérdida en la fuerza de pretensado por penetración en cuña (∆P2) afecta sólo
a una longitud del tendón denominada longitud de influencia (X), ver figuras 4.11.a y
4.11.b. El valor de X depende del rozamiento (p) entre el tendón y la vaina, que se
supone de valor constante por unidad de longitud2. El valor de p no depende de hacia
donde se mueva el cable en la vaina (hacia dentro o hacia afuera) de ahí que la línea
continua AB y la discontinua CB tengan pendientes iguales y opuestas (figura 4.11.a).
En la figura 4.11.b se aprecia que el valor inicial de la fuerza en el anclaje es P0,
pasando a P0-∆P2 cuando se produce una penetración de cuña de valor a. A una
distancia X la fuerza de pretensado tendrá un valor P’ que, por definición de X, será el
mismo antes y después de producirse la pérdida por penetración de la cuña, ∆P2.

Fuerza de tesado
X, Longitud de influencia
Antes de la penetración de cuña
P0-∆P1 P’=P0 -∆P2/2 A Después de la penetración de P0 P0
p cuña
1 B p
1 p P’=P0 -∆P2/2 p
C P0 -∆P2
X, Longitud de influencia

a, penetración de cuña

x, Distancia desde el anclaje

a b

Figura 4.11. (a) Distribución de la fuerza de pretensado.
(b) Equilibrio en la longitud de influencia.

Estableciendo el equilibrio en las dos situaciones representadas en la figura
4.11.b (antes y después de la penetración de cuña) se obtiene:

1 Para lograr que éstas queden encajadas se necesitan del orden de 5 mm de penetración.
2 Si el tendón está engrasado la longitud de influencia será mucho mayor.

<!-- p. 111 -->

HORMIGÓN ESTRUCTURAL 111
Hernández-Gil
∆P2 0 − P0 = P ′ + p ⋅ X ⎫ P ' = P 2 ⎬ → (4.4)
P0 − ∆P2 + p ⋅ X = P ′ ⎭ ∆P 2 = p ⋅ X
2

El rozamiento que se desarrolla en la longitud de influencia X cambia de signo
al pasar del estado inicial (sin penetración de cuña) al estado final (penetración de
cuña), tal y como se aprecia en la figura 4.11.b.

Al final de la fase de penetración de cuña, la variación del valor de la fuerza de
pretensado será máxima en el extremo izquierdo, donde valdrá ∆P2, siendo nula a una
distancia X. Así pues, la variación media de la fuerza de pretensado a lo largo de X será
∆P2/2. La pérdida de tensión se puede obtener dividiendo la pérdida de fuerza de
pretensado entre el área, por lo que la pérdida de tensión media será ∆σmed=∆P2/2Ap,
donde Ap es el área del tendón.

Puesto que la variación de la tensión en el cable a lo largo de X pasa de un
valor máximo a 0 (con un variación que se supone lineal), la deformación
correspondiente a la penetración de la cuña (a) es la misma que si se considera que toda
la longitud X está sometida a una pérdida de tensión media y, por tanto:

∆σmed X a = (4.5)
E p
donde Ep es el módulo de deformación longitudinal del tendón.

Sustituyendo ∆σmed=∆P2/2Ap y la segunda ecuación 4.4. en la ecuación
anterior se puede despejar el valor de X.

a E p Ap X = (4.6)
p

<!-- p. 112 -->

LA FUERZA DE PRETENSADO 112

Cuña

Trompeta

Bloque de anclaje

Figura 4.12. Detalle de anclaje de armadura activa. Cabeza de viga postesa

Ejemplo de pérdidas de rozamiento

Sea una viga postesada de 4 vanos, de 25 m de luz cada uno, representada en la
figura 4.13. La excentricidad del trazado del tendón respecto a la línea media de la viga
es de 0.6 m en la mitad del vano y de 0.5 m en los apoyos. La armadura postesa está
compuesta por un tendón de 19 cordones Y-1860-S7 de 15.2 mm de diámetro nominal.
Todo el tendón se tesa simultáneamente. El tendón está anclado en el eje de simetría y
su tesado se lleva a cabo desde cada uno de los extremos.

0.5 m
0.6 m

11.25 m 11.25 m 2.5 m 2.5 m 10 m 10 m 2.5 m

1 2 3 4 5 6 7 8

Figura 4.13. Viga de 4 vanos de 25 m cada uno

A partir de la norma EHE, y teniendo en cuenta que se tesa simultáneamente,
adoptamos como coeficiente de rozamiento en curva el valor µ=0.213. La vaina para
incluir los 19 cordones ( según catálogos técnicos) está en torno a 100 mm de diámetro.
Para el caso de diámetro interior de conducto mayor de 60 mm la EHE establece que la

3 Alambres o cordones trefilados sin lubricar y tendón formado por varios elementos
agrupados en una misma vaina de acero sin tratamiento superficial.

<!-- p. 113 -->

HORMIGÓN ESTRUCTURAL 113
Hernández-Gil
relación (k/µ) toma el valor de 0.006 y, por tanto, el coeficiente de rozamiento parásito
por metro lineal (k) es: k= 0.006·0.21= 0.00126.

Ap = 140·19 = 2660 mm2
Ep = 190000 N/mm2
Penetración de cuña (a) = 5 mm

Al existir penetración en cuña se va a optar por tesar hasta un 85% de fpmax,k, lo
que supone P0=0.85·1860·2660/1000 = 4205 kN.

Las pérdidas por rozamiento se calculan aplicando la formulación 4.1 y 4.2.
Para la sección 2:

2 ⋅ 0 . 6
α2 = = 0 . 107 rad
11 . 25
µα + kx = 0 .21 ⋅ 0 . 107 + 0 . 00126 ⋅ 11 .25 = 0 . 03658

−µα( + kx ) ] = 151 .02 kN ∆P1 = P0 [1 − e

Para localizar las siguientes secciones se tiene en cuenta que los puntos de
inflexión (secciones 3, 5 y 7) están alineados con los puntos de las secciones adyacentes
(ecuación 4.3). Para las 8 secciones señaladas en la figura 4.13 se puede confeccionar la
siguiente tabla:

Tabla 4.4. Pérdidas de rozamiento. Valores acumulados.
SECCIONES 1 2 3 4 5 6 7 8
Α 0.0 0.107 0.267 0.667 0.843 1.019 1.195 1.371
µα+kx 0 0.03658 0.08435 0.17150 0.21161 0.26117 0.31073 0.35084
∆P1 0 151.02 340.14 662.71 801.98 966.52 1123.11 1244.27

El valor de P0-∆P1 se ha representado en la figura 4.14.

<!-- p. 114 -->

LA FUERZA DE PRETENSADO 114

1 2 3 4 5 6 7 8

P
4205 kN

4000 kN 4010 kN

3865 kN

3814 kN

3542 kN
3500 kN
3403 kN
3238 kN

3082 kN

3000 kN 2961 kN

2500 kN x
12.93 m

Figura 4.14. Variación de la fuerza de pretensado

Para determinar la longitud de influencia de la pérdida por penetración de cuña
(a partir de la ecuación 4.6) es necesario conocer el valor de p (rozamiento por unidad
de longitud), que se puede obtener entre las secciones 1 y 3 como:

340140
p = = 15 .12 N / mm
2 ⋅ 11250

y, por lo tanto, el valor de X será:

a E p Ap 5 ⋅ 190000 ⋅ 2660 X = = = 12928 mm = 12 .93 m
p 15 .12

A partir de la segunda ecuación 4.4 se puede determinar el valor de la pérdida por
penetración de cuña:

∆P2 = 2 ⋅ p ⋅ X = 2 ⋅ 15 . 12 ⋅ 12928 = 390943 N = 390 . 94 kN

<!-- p. 115 -->

HORMIGÓN ESTRUCTURAL 115
Hernández-Gil
Calcular el alargamiento que va a experimentar el tendón durante la fase de
tesado es una buena manera de comprobar si el proceso de tesado ha sido tal y como
había sido planteado. Suponiendo que la fuerza de pretensado varía linealmente entre
los extremos de cada parábola y que se mide después de la penetración en cuña, el valor
de la fuerza media de pretensado será:

1 ⎡ 4010 + 3814 4010 + 3865Pmedia = ⋅ 12 .93 + ⋅ (2 ⋅ 11 .25 − 12 . 93 ) + 50 ⎢⎣ 2 2
3865 + 3542 3542 + 3403 3403 + 3238 3238 + 3082
⋅ 2 . 5 + ⋅ 2 .5 + ⋅ 10 + ⋅ 10 +
2 2 2 2
3082 + 2961 ⎤ ⋅ 2 . 5 = 3571 . 3 kN
2 ⎥⎦

y, por tanto, el alargamiento experimentado por el tendón durante el tesado debe de ser
de:

50000 ⋅ 3571300
∆L = = 353 . 3 mm
190000 ⋅ 2660

<!-- p. 116 -->

LA FUERZA DE PRETENSADO 116

4.5. PÉRDIDAS POR ACORTAMIENTO ELÁSTICO

En elementos pretesos se procede a la fase de destesado cuando el cable está
tesado y el hormigón endurecido y carente de tensiones. En esta fase se transmiten las
tensiones al hormigón. Estas tensiones provocan un acortamiento del elemento
estructural debido a que la fuerza de tesado comprime el hormigón (figuras 4.15 y 4.16).
A su vez, el acortamiento de la viga de hormigón afecta al tendón ya que éste
experimenta una disminución de su longitud, lo que produce una nueva pérdida en la
fuerza de tesado, ∆P3, denominada pérdida por acortamiento elástico.

Gato L = Longitud inicial

L -∆L = Longitud final

e

Figura 4.15. Pérdida por acortamiento elástico

Figura 4.16. Proceso de destesado de la armadura activa en vigas pretesas

Como hipótesis se admite que la deformación a la altura del tendón es la misma
en el hormigón que en el acero ya que ambos se encuentran en la misma fibra y, por la
hipótesis de las secciones planas, ambos tienen la misma deformación. Si la tensión en

<!-- p. 117 -->

HORMIGÓN ESTRUCTURAL 117
Hernández-Gil
el hormigón a la altura del c.d.g. de la armadura activa es σcp, para que ambas
deformaciones sean iguales se ha de verificar que:

σcp ∆σp E p
\= ⇒ ∆σp = m σcp con m = (4.7)
E cm E p E cm

En el caso de pretensado posteso, si la tensión se transmite a la vez en todos los
tendones no se produce pérdida por acortamiento elástico. En este tipo de pretensado la
pérdida por acortamiento elástico aparece en el caso de que se tensen los tendones
sucesivamente. Si hubiera n tesadas de n tendones de la misma sección, en la última
tesada (que introduce una tensión en el hormigón de valor σcp/n) la pérdida en el tendón
tesado sería nula pero en las otras (n-1) tesadas anteriores provocaría una pérdida de
valor
σcp Ap
m
n n

en cada uno de los tendones, donde Ap es el área de toda la armadura activa.

Sumadas las pérdidas acumuladas en cada tesada sobre los tendones anteriores,
tenemos que la pérdida total es:

Ap
∆P3 = mσcp ( n − )1 (4.8)
2 n

Cuando se procede a la fase de destesado de la armadura activa la viga se ve
sometida a un momento de valor P·e, siendo P la fuerza de pretensado y e la
excentricidad. Este momento es negativo y tiende a provocar una contraflecha que se ve
compensada por el peso propio de la viga.

La ecuación 4.7 relaciona la pérdida de la tensión de pretensado con la tensión
en el hormigón, ésta última será distinta según el valor del momento compensado del
peso propio. En la práctica se considera como pérdida de acortamiento elástico al valor
medio entre los valores máximos y mínimos, si bien puede haber casos en que esto no
sea aceptable.

Ejemplo de acortamiento elástico en una viga simplemente apoyada pretesa

Consideremos la viga pretensada pretesa de la figura 4.17 de 20 m de longitud,
fabricada con hormigón HP-45 y acero Y-1860-S7. En bancada se le ha transmitido una
tensión inicial de pretensado del 75% de fmáx. Las características mecánicas son: Ac=
4.5×105 mm2; Ap=2850 mm2; Ic=9.4×1010 mm4. El peso propio por unidad de longitud
es de 10 kN/m.

<!-- p. 118 -->

LA FUERZA DE PRETENSADO 118

20 m

Sección transversal

e = 560 mm

Figura 4.17. Viga pretesa de 20 m de luz

Para calcular su acortamiento elástico se va a tener en cuenta que:

\- Lo que acorta el acero es igual que lo que acorta el hormigón en la misma
fibra. Debido a ese acortamiento la fuerza de pretensado, que inicialmente
era P0, pasa a ser Pe=Ap(σp0-∆σp).
\- Cuando se liberan los cables y la viga se sometide a la fuerza de
pretensado, ésta tiende a levantarse y a vencer su peso propio.

Vamos a suponemos que todos los tendones están situados a e=560 mm (en el caso que
éstos estuvieran muy separados entre sí esta hipótesis no sería válida).

El valor del momento máximo debido al peso propio es M0

10 ⋅ 20 2 8
M 0 = = 500 kN ⋅ m = 5 × 10 Nmm
8

y la tensión del hormigón a la altura del c.d.g. de la armadura activa, en la sección
situada en el centro de luz es4:

4 En la expresión de la tensión σcp se ha considerado el momento del peso propio sobre
la sección bruta. Esto no sería real puesto que el peso propio que actúa al descimbrar lo
hace sobre la sección homogeneizada, no obstante la diferencia es pequeña.

<!-- p. 119 -->

HORMIGÓN ESTRUCTURAL 119
Hernández-Gil
Pe Pe ⋅ e ⋅ e M 0 ⋅ e σcp = + −
Ac I c I c

Introduciendo la ecuación 4.7 en la ecuación anterior y teniendo en cuenta que
Pe=Ap(σp0-∆σp), se obtiene el siguiente sistema de dos ecuaciones con dos incógnitas:

⎧ ∆σp Pe Pe ⋅ e ⋅ e M 0 ⋅ e = + −
⎪⎨ m Ac I c I c
Pe = Ap ⋅ (σpo − ∆σp ) ⎪⎩

190000
donde m = = 5 . 058 y σp0=0.75·1860=1395 N/mm2.
10000 3 45 + 8

Resolviendo el sistema anterior, se obtiene que ∆σp=89.54 N/mm2 y
Pe=3.72×106 N.

En los extremos el momento debido al peso propio es cero y el valor de ∆σp es
103.49 N/mm2. Por tanto, la pérdida media en la armadura activa será:

89 . 54 + 103 . 49 2
∆σp = = 96 . 52 N / mm
2

lo que supone una pérdida del 6.92%.

Consideremos ahora que el trazado en lugar de ser recto es parabólico. Se ha
empleado la técnica de postesado y la viga ha sido tesada en 3 veces.

20 m

Figura 4.18. Viga postesa

La expresión de la tensión del hormigón a la altura del c.d.g. de la armadura
activa, junto con la ecuación 4.8 forman el siguiente sistema de ecuaciones:

<!-- p. 120 -->

LA FUERZA DE PRETENSADO 120

⎧ P0 − ∆ P3 ( P0 − ∆ P3 ) ⋅ e ⋅ e M 0 ⋅ e σcp = + − ⎪⎪ Ac I c I c
⎨
⎪ n − 1 ∆ P3 = m ⋅ σcp ⋅ ⋅ Ap ⎪ ⎩ 2n

Puesto que n=3, del sistema de ecuaciones anteriores se obtiene que σcp=18.62
N/mm2 . Si M0=0 y e=0 (extremo de la viga) la tensión correspondiente sería: σcp=21.52
N/mm2.

La pérdida de tensión media en la armadura de pretensado se puede obtener
como:

n − 1 18 .62 + 21 . 52 2 2
∆σp = mσcp = 5 . 058 ⋅ ⋅ = 33 . 83 N / mm
2 n 2 6

lo que representa una pérdida del 2.42%.

4.6. PÉRDIDAS DIFERIDAS

Una vez anclada la armadura activa y después de haberse producido las
pérdidas instantáneas, aparecen unas nuevas pérdidas a lo largo del tiempo. Estas
pérdidas se deben esencialmente al acortamiento de hormigón (retracción y fluencia) y a
la relajación del acero de las armaduras activas.

Los fenómenos de fluencia y de relajación dependen a su vez del valor de las
pérdidas diferidas, por lo que sería necesario realizar un proceso iterativo. De forma
aproximada, las pérdidas diferidas se pueden calcular mediante la expresión5:

mϕ( t , t 0 )σcp + E pεcs ( t , t 0 ) + 0 . 80 ∆σpr
∆ Pdif = 2 Ap Ap ⎛ Ac y p ⎞
(1 + χϕ( t , t 0 )) 1 + m ⎜⎜ 1 + ⎟⎟ Ac ⎝ I c ⎠
donde:

yp Distancia del centro de gravedad de las armaduras activas al centro de
gravedad de la sección.
m Coeficiente de equivalencia = Ep/Ec.
ϕ(t,t0) Coeficiente de fluencia para t0 como edad de puesta en carga.
εcs Retracción tras la operación de tesado.
σcp Tensión en el hormigón en la fibra correspondiente al c.d.g. de las
armaduras activas debida a la acción de pretensado, al peso propio y a
la carga muerta.

5 Propuesta por la EHE.

<!-- p. 121 -->

HORMIGÓN ESTRUCTURAL 121
Hernández-Gil
∆σpr Pérdida por relajación a longitud constante = ρf Pki/Ap.
χ Coeficiente de envejecimiento. Para evaluaciones a tiempo infinito se
puede tomar 0.8.
Ac , Ic Área y momento de inercia de la sección de hormigón,
respectivamente

<!-- p. 122 -->

LA FUERZA DE PRETENSADO 122

Ejercicios propuestos

4.1. Justificar razonadamente (sin recurrir a extender al límite ningún tipo de
formulación) que la pérdida de tensión por acortamiento elástico puede
considerarse como mσcp/2.

4.2. Explicar qué ventajas tiene el planteamiento seguido en este capítulo para
desarrollar las parábolas encadenadas frente al expuesto por la EHE. ¿Cuál
crees que es más general?

4.3. Calcula las pérdidas diferidas en el problema de pérdidas por rozamiento.
Elabora un gráfico similar al de la figura 4.14 considerando ambos tipos de
pérdidas.

Referencias

EHE. Instrucción de Hormigón Estructural (borrador 2007). Secretaría General Técnica.
Ministerio de Fomento. Madrid.

Eurocode 2 (2002): Design of concrete structures- Part 1: General rules and rules for
buildings prEN 1992-1-1. European Committee for Standardization. Brussels.

Collins M.P. y Mitchell D. (1991). Prestressed Concrete Structures. Prentice-Hall. New
Jersey.

Hurst M.K. (1998). Prestressed Concrete Design. 2ª edición. E & FN Spon. Londres y
Nueva York.

Leet K. y Bernal D. (1997). Reinforced Concrete Design. McGraw-Hill.

<!-- p. 123 -->

HORMIGÓN ESTRUCTURAL 123
Hernández-Gil

<!-- p. 124 -->

MÉTODO DE BIELAS Y TIRANTES 124

<!-- p. 125 -->

HORMIGÓN ESTRUCTURAL 125
Hernández-Gil

CAPÍTULO V

MÉTODO DE LAS BIELAS Y TIRANTES

Centro de vano
P

C y 3
C y 5 B

y 4

A D E
y 1

F 700 mm 700 mm
2

Modelo de bielas y tirantes.

5.1. REGIONES B Y D

La hipótesis de las secciones planas, o hipótesis de Bernoulli, establece que las
secciones planas antes de la deformación permanecen planas después de ésta. Esta hipótesis
es fundamental en el estudio de los elementos de una estructura ya que conocida la
deformación en dos puntos de la sección transversal se puede calcular la deformación en
todos los puntos de ésta –en el caso de trabajar en tres dimensiones sería necesario conocer
la deformación en tres puntos-. Estos dos puntos de la sección transversal pueden ser los
correspondientes a las deformaciones máxima y mínima, respectivamente. Ver Figura 5.1.

<!-- p. 126 -->

MÉTODO DE BIELAS Y TIRANTES 126

A’s
εsup
εcg
φ
Fibra neutra
Centro de gravedad
de la sección bruta Ap

εinf
As
Deformaciones unitarias debidas a
las acciones exteriores

Figura 5.1. Deformaciones unitarias en la sección trasversal según la hipótesis de
las secciones planas

Sin embargo, no siempre es posible aplicar la hipótesis de las secciones planas. ya
que existen zonas en las que, bien por cambios bruscos de geometría o bien por la existencia
de cargas concentradas, ninguna sección plana permanece plana después de la deformación.

En estructuras de hormigón es necesario distinguir entre regiones B (de Bernoulli)
y regiones D (de discontinuidad). Las regiones B son partes de la estructura en las que se
puede aplicar la hipótesis de las secciones planas. Las regiones D son aquellas en las que no
es válida dicha hipótesis debido a la existencia de una distribución de deformaciones
compleja y claramente no lineal.

Las figuras 5.2 y 5.3 son ejemplos de la división entre regiones B y D en
estructuras de edificación y civiles, respectivamente. Las regiones D aparecen dibujadas en
tono oscuro y las regiones B en tono claro. Los valores h1, h2, …corresponden a los cantos
de los elementos estructurales y b1 y b2 a los anchos de alas.

<!-- p. 127 -->

HORMIGÓN ESTRUCTURAL 127
Hernández-Gil

h1 D B D B D h3
h 4 h2 h2 h2 h 2 h2
B B
D B D B D B D
h1 D h3 D h4 h4 h4 D
h5 h5
h 1 h1 h3 h3
B B B h3
h 1 h5
D
D D

Figura 5.2. División entre zonas B y D en una estructura de edificación

b1 b1>h1 b2 b2>h4
h1 h4

Sección -1-1 Sección -2-2 b1 b1 1 2

D B D D B D D B D B D
D h1 D 1 b1 D b2 h4 b2 b2 2 b2

h2 h2 h3 h3 D B
h2 B
D h3

D

Figura 5.3. División entre zonas B y D en una estructura de puente

<!-- p. 128 -->

MÉTODO DE BIELAS Y TIRANTES 128

El diseño de las regiones B se fundamenta en la analogía de la viga para el cálculo
de la armadura longitudinal y en la analogía de la celosía para el diseño a cortante. Estas
teorías se tratarán en capítulos siguientes. Las regiones D, que se presentan en elementos
tales como las vigas de gran canto, apoyos, uniones viga-columna, encepados, zapatas, etc.,
se diseñan mediante los métodos de bielas y tirantes.

5.2. MODELOS DE BIELAS Y TIRANTES

El método de bielas y tirantes consiste en la modelización de la región D mediante
una estructura de barras articuladas –plana o espacial-. Esta estructura articulada estará
compuesta por nudos, barras a compresión o bielas y barras a tracción o tirantes. Las bielas
están constituidas por el hormigón existente en la región D y los tirantes por la armadura de
aportación.

Las zonas discontinuas se pueden estudiar también mediante métodos de análisis
elásticos, especialmente mediante técnicas con elementos finitos, a partir de los cuales se
puede calcular la distribución de tensiones generada por las cargas concentradas. Estos
modelos tratan al hormigón como un medio continuo y, a partir del estado de tensiones, se
decide la posición de la armadura. El objeto de la armadura es absorber las tensiones de
tracción –que no pueden ser resistidas por el hormigón-. Son numerosos los estudios
existentes en relación a la distribución de tensiones bajo cargas concentradas. Hay que
tener en cuenta que esta forma de proceder es precisa siempre que nos mantengamos en la
fase de pre-fisuración. Por el contrario, en las fases de post-fisuración y cedencia los
modelos de bielas y tirantes son más fiables. De hecho, cuando la fisuración es importante
las direcciones principales de compresión tienden a convertirse en líneas rectas, lo que hace
que el modelo de bielas y tirantes sea el más adecuado.

En la figura 5.4 se muestran algunos modelos de bielas y tirantes para regiones D
en dos dimensiones. La figura 5.5 corresponde a un modelo espacial. Las líneas
discontinuas constituyen los elementos a compresión (bielas) y las líneas continuas
representan los elementos a tracción (tirantes).

<!-- p. 129 -->

HORMIGÓN ESTRUCTURAL 129
Hernández-Gil

Biela
Tirante
Nodo

Figura 5.4. Modelos planos de bielas y tirantes

<!-- p. 130 -->

MÉTODO DE BIELAS Y TIRANTES 130

(a)

(b)

(c)

Figura 5.5. Ejemplo de modelo espacial de bielas y tirantes. a) perspectiva de la
viga b) modelo de bielas y tirantes en el alma de la viga c) modelo de bielas y
tirantes en el ala de la viga.

<!-- p. 131 -->

HORMIGÓN ESTRUCTURAL 131
Hernández-Gil
5.3. BIELAS Y TIRANTES

Las bielas son elementos a compresión y representan campos de tensiones en el
hormigón de la región D. La tensión principal de compresión está situada en la biela del
modelo. La forma del campo de compresiones en la biela, siguiendo un modelo en dos
dimensiones, puede ser prismático, en forma de uso o en forma de abanico tal y como se
puede ver en las figuras 5.6a, 5.6b y 5.6c respectivamente. Las bielas también pueden ser
reforzadas mediante armadura, denominándose en este caso bielas armadas. En la figura 5.7
se representan distintos tipos de bielas en una región D típica.

σc1\< σc

σc σc

σc wc wc σc wc

(a) (b) (c)

Figura 5.6. Tipos básicos de bielas en dos dimensiones. a) Prismático, b) En forma
de uso, c) En abanico.

(f)

(d) (e) (c) (a) (b)

Figura 5.7. Tipos de biela en una región D: a) Biela prismática en zona no fisurada
b) Biela prismática en zona fisurada y paralela a las fisuras c) Biela prismática en
zona fisurada y no paralela a las fisuras d) Bielas en forma de uso con armadura
para control de fisuración e) Biela en forma de uso sin armadura de fisuración f)
Biela de hormigón confinado.

<!-- p. 132 -->

MÉTODO DE BIELAS Y TIRANTES 132

Los tirantes son los elementos traccionados del modelo de bielas y tirantes. Los
tirantes representan generalmente a barras de armadura pasiva aunque ocasionalmente
pueden estar compuestos de armadura activa o campos de compresiones de hormigón cuya
dirección principal de tracción vaya en la dirección del tirante.

Los nodos representan las zonas de la región D donde las fuerzas entre bielas y
tirantes se equilibran y, por tanto, los nodos están sometidos a fuerzas multidirectionales.
Los nodos se clasifican atendiendo a los tipos de fuerzas que conectan. En la figura 5.8 se
representan los tipos de nodos más comunes en dos dimensiones, C representa compresión y
T tracción.

Figura 5.8. Nodos básicos. a) CCC, b) CCT, c) CTT y d) TTT

5.4. UNICIDAD DE LOS MODELOS DE BIELAS Y TIRANTES

El modelo de bielas y tirantes debe de estar en equilibrio tanto externo (fuerzas
aplicadas y reacciones) como interno (en cada uno de los nodos de la celosía que compone
el modelo). Para conseguir este equilibrio los tirantes se dimensionarán mediante armadura
pasiva o activa, también se dimensionará el ancho efectivo de cada biela y el nudo deberá
dimensionarse para garantizar una resistencia suficiente. Es interesante que el modelo
interno de barras del método de bielas corresponda a una estructura isostática, de tal forma
que sólo sea necesario verificar el equilibrio entre los elementos de la celosía y criterios de
resistencia última, no siendo necesario el cálculo de deformaciones.

El método de las bielas permite resolver la región D mediante distintos modelos,
todos ellos admisibles, un ejemplo de esto se puede ver en la figura 5.9. En el ejemplo de la
figura 5.9 se observa que existe una solución preferente: debido a la carga aplicada, la parte
superior de la viga es probable que desarrolle tensiones de tracción y, por ello, el modelo
con un tirante horizontal (figura 5.9a) es preferible al modelo de la figura 5.9b ya que éste
último sólo resiste la tracción mediante barras inclinadas y, por tanto, desarrollará mayores
deformaciones.

<!-- p. 133 -->

HORMIGÓN ESTRUCTURAL 133
Hernández-Gil
Es aconsejable optar por modelos que tengan tirantes de mínima longitud ya que en
éstos las deformaciones serán menores. Además, con objeto de evitar grandes
deformaciones, cuando se emplee el modelo de bielas y tirantes la deformación de éstos
últimos se limitará al 2‰, lo que para el acero supone una fyd máxima de 400 MPa. Una
forma de obtener un modelo consiste en encajar las bielas y tirantes una vez conocida la
distribución de tensiones a partir de un análisis lineal. No obstante es bueno darse cuenta
que al poner nosotros los tirantes obligamos a la pieza a trabajar de una forma determinada,
y posiblemente no coincidente con la distribución de tensiones obtenida mediante un
análisis lineal.

Es conveniente que el ángulo que forman las bielas y los tirantes que confluyen en
un nudo sea lo suficientemente grande como para que no se produzca incompatibilidad de
deformaciones. Por tanto, se evitarán los ángulos pequeños.

Figura 5.9. Dos modelos biela-tirante estáticamente admisibles para una viga de
gran cango en voladizo bajo una carga vertical. a) modelo con menor deformación,
b) modelo con mayor deformación.

5.5. PROCESO DE DISEÑO

El proceso de diseño para aplicar el método de bielas y tirantes conlleva cinco pasos,
que se describen a continuación. Estos pasos se muestran en la figura 5.10, que corresponde
a un ejemplo de diseño de una viga con apoyo a media madera.

PASO 1. Definir las fronteras de la región D y determinar las fuerzas del contorno
(fuerzas de diseño) que provienen de las acciones exteriores y de las
fuerzas internas que actúan en las secciones del contorno de la región D.

<!-- p. 134 -->

MÉTODO DE BIELAS Y TIRANTES 134

PASO 2. Insertar un modelo de celosía para la región D, determinando las fuerzas
equivalentes del contorno y resolviendo la celosía.

PASO 3. Seleccionar la armadura activa o pasiva necesaria en los tirantes y
comprobar que esta armadura está convenientemente anclada en los nodos.

PASO 4. Evaluar las dimensiones de las bielas y de los nodos de tal forma que la
capacidad de todos ellos (tanto bielas como nodos) sea suficiente para
soportar la fuerzas de la celosía.

PASO 5. Proporcionar suficiente armadura para asegurar el comportamiento dúctil
de la región D.

PASO 1 PASO 2

h D B

h

PASO 5
PASOS 3 Y 4

.

Figura 5.10. Pasos a seguir en el proceso de diseño.

<!-- p. 135 -->

HORMIGÓN ESTRUCTURAL 135
Hernández-Gil
Ejemplo en hormigón armado

La figura 5.11 corresponde a un apoyo a “media madera” de una viga de 0.75×0.40
m. Este apoyo debe de transmitir una reacción vertical de 250 kN y reacción horizontal de
50 kN, ambas mayoradas. La reacción se supone que actúa a 50 mm del final de la viga. El
hormigón de la viga es del tipo HA-35 y el acero B-400-S. Para la resolución se aplicará la
norma española EHE.

L 100×100×15

0.40 m
0.75 m 213.75 kN·m

50 kN

50 kN
250 kN

0.35 m 250 kN

5 cm 10 cm 0.75 m

Figura 5.11. Apoyo a media madera.

\1. Definir la región D y calcular los esfuerzos de continuidad

La región D se extiende un canto a partir de la discontinuidad así que tendrá
(15+75)=90 cm. Las fuerzas de la derecha corresponden a un momento de 250(0.90-
0.05)+50(0.40-0.75/2)=213.75 kN·m, a una fuerza horizontal de tracción de 50 kN y a un
cortante de 250 kN. Todos ellos representados en la figura 5.11.

\2. Dimensiones del apoyo

Se ha elegido para el apoyo un angular de 100×100×15. La superficie del apoyo
será de 400×100=40000 mm2 y, por tanto, la tensión transmitida al hormigón es de:

<!-- p. 136 -->

MÉTODO DE BIELAS Y TIRANTES 136

Vd 250000 2 = = 6.25 N / mm
Ac 40000
menor que 0.85·fcd=0.85·35/1.5=19.83 N/mm2, luego la elección de las dimensiones del
apoyo han sido adecuadas.

\3. Elección del modelo

La geometría del modelo ha sido representada en la figura 5.12. La altura a la que
han de colocarse las barras BE y CF está relacionada con la situación del centro de gravedad
de la zona de compresiones, en el caso de la barra BE, y con el centro de gravedad de la
armadura de tracción, en el caso de la barra CF. Tomaremos 8 cm a partir de la parte
superior de la viga para la barra BE y 8 cm a partir de la parte inferior de la viga para la
barra CF. Se ha tomado 45º como el ángulo de las barras CD y DE con la horizontal. La
barra BC se ha separado 15 cm respecto a la media madera.

B E 8 cm
G

A 47.2º 40.2º
59 cm
5 cm D

50 kN

35 cm F
250 kN C H
8 cm

10 cm
59 cm

5 cm 15 cm

Figura 5.12. Modelo de bielas y tirantes

<!-- p. 137 -->

HORMIGÓN ESTRUCTURAL 137
Hernández-Gil
\4. Cálculo de la estructura de barras articuladas

En la tabla siguiente se muestran los resultados de la resolución de la estructura
articulada. Positivo corresponde a compresión y negativo a tracción.

Barra AB AD BC BD BE CD CF DE EF
Axil (kN) 340.7 -281.5 -378.9 199.8 78.9 535.8 -378.9 353.4 -250

\5. Comprobación de las bielas

Para comprobar las bielas se calculará el ancho de éstas y se comprobará si caben
en el espacio disponible. En el caso de almas de vigas sometidas a cortante, las bielas tienen
una resistencia de f1cd=0.60fcd= 0.6·35/1.5=14 N/mm2. Si el ancho de la viga es de 400 mm,
el ancho de cada biela viene dado en la tabla siguiente:

Barra AB BD BE CD DE
Axil (kN) 340.7 199.8 78.9 535.8 353.4
Anchura (mm) 61 36 14 96 63

Representadas las bielas y sus anchos correspondientes en la viga (figura 5.13) se
puede concluir que éstos son aceptables.

B E
G

A
D

F
C H

Figura. 5.13. Dimensión de las bielas

<!-- p. 138 -->

MÉTODO DE BIELAS Y TIRANTES 138

\6. Diseño de los tirantes

La armadura necesaria en los tirantes se dimensiona a tracción As,necesaria=Nd/fyd.
Los resultados se resumen en la siguiente tabla.

Barra AD BC CF EF
Axil (kN) -281.5 -378.9 -378.9 -250
Armadura (mm2) 810 1089 1089 719
Armadura 3Ø20 5cØ12 4Ø20 4cØ12
(mm2) (942) (1130) (1257) (905)

\7. Capacidad resistente de los nudos y anclajes

Todos los nudos tienen tirantes anclados y, por tanto, realizada la comprobación de
bielas sólo es necesario dimensionar el anclado de los tirantes. El tirante soldado al angular,
nudo A, requerirá un ancho efectivo de:

N AD 281500 = = 35 mm
\0. 85f cd b 0 . 85·35 / 1 . ·5400

y puesto que el ancho de placa disponible es de 100 mm, resulta suficiente. Para el nudo D
será necesario disponer de una longitud de anclaje de 32 cm.

As 2 As 2 810 Lb ,neta = Lb ·β· = m·φ · = 2·9 = 31 . 4 cm.
As ,real As ,real 942

En el tirante CF, el nudo C necesita una longitud de anclaje de

As 2 As 2 1089 Lb ,neta = Lb ·β· = m·φ · = 2·9 = 31 .19 cm
As ,real As ,real 1257

9 . 6
Puesto que sólo hay disponible 15 + 2 = 21 .79 cm será necesario añadir barras
2
que absorban la diferencia y la transmitan a la armadura del tirante CF. La diferencia es de
21 . 79
378 .9 kN − 378 . 9 = 114 . 2 kN por lo que el área necesaria será de
31 . 19
114200 /( 400 / 1 . 15 ) = 328 mm 2 que habrá de ser suministrada en armaduras cuya

<!-- p. 139 -->

HORMIGÓN ESTRUCTURAL 139
Hernández-Gil
longitud de anclaje sea menor de los 21.79 cm disponibles. Se dispondrán 2Ø16 en forma
de U (cuya longitud de anclaje en U es de 13 cm).

Los nudos B y D del tirante BD necesitan una longitud de anclaje de

As 2 As 2 1089Lb ,neta = Lb ·β· = m·φ · = 1·9 . 2 = 8 . 74 cm , de la que ya se
As ,real As ,real 1130
dispone.

\8. Otras consideraciones

Si el apoyo es tratado como ménsula corta, la EHE establece que además habrá que
disponer armadura Ase con objeto de mejorar la fisuración y la ductilidad. Esta armadura
estará compuesta por cercos horizontales que verifiquen:

0 . 20·Fvd 0 . ·2250000 2 Ase = = = 143 . 73 mm
f yd 400 / 1 .15
Se puede disponer 1cØ10 ó 2Ø10 en forma de U.

5 cercos Ø12 4 cercos Ø12
de dos ramas cada 5 cm de dos ramas cada 10 cm

2 Ø16 de montaje
2 cercos Ø 10 2 Ø 10 en U
3 Ø20 Soldados al angular

2 Ø16 en U

4 Ø20

Figura 5.14. Armadura

<!-- p. 140 -->

MÉTODO DE BIELAS Y TIRANTES 140

Ejemplo en hormigón pretensado

1000 mm

200 mm
200 mm

2000 mm
4 placas de anclaje
200×200 mm
agujero Ø50 mm

200 mm

Figura 5.15. Zona de anclaje de una viga postesada.

En la figura 5.15 se ha representado la zona de anclaje de una viga postesada en
doble T. Cada tendón contiene 4 cordones de 13mm de diámetro (área de 99 mm2 cada uno)
del tipo Y1860-S7 cuya tensión máxima es de 1860 MPa. Durante el tesado se ha alcanzado
el 75% de su tensión máxima. La resistencia del hormigón durante el tesado es de 34 MPa.
En este ejemplo se va a diseñar la armadura de la zona discontinua.

Calcularemos el armado de la zona como si pudiera desarrollarse toda la fuerza de
los tendones. Pd=4·1860·99/1000=737 kN.

\1. Definir la región D y calcular los esfuerzos de continuidad

Al final de la zona de discontinuidad la tensión en toda la viga será constante siendo el
valor de la resultante sobre las alas y el alma de la viga:

·4737000
R alas = 200·1000 = 819 kN
·2200·1000 + 200·1600
·4737000
R alma = 200·1600 = ·2655 kN = 1310 kN
·2200·1000 + 200·1600

<!-- p. 141 -->

HORMIGÓN ESTRUCTURAL 141
Hernández-Gil

La resultante correspondiente a la acción de los tirantes en el lado izquierdo de la
viga se puede representar mediante diversos sistemas de fuerzas, siempre que se verifique
que son estáticamente equivalentes. De entre todos los posibles sistemas de fuerzas
conviene adoptar el representado en la figura 5.16, para el cual las distancias al eje de las
fuerzas son 200 mm y 89 mm, como se puede ver en la figura 5.16.

819 kN

900 mm
819 kN 655 kN 200 mm
400 mm
655 kN

655 kN 89 mm

819 kN 655 kN

819 kN

2000 mm

Figura 5.16. Equilibrio externo.

El apoyo es de neopreno y no forma parte de la viga por lo que no se calculará en
este problema (en la práctica habría que calcularlo).

<!-- p. 142 -->

MÉTODO DE BIELAS Y TIRANTES 142

\2. Elección del modelo y cálculo de esfuerzos en bielas y tirantes

Para la división de fuerzas efectuada es fácil plantear un modelo de bielas y
tirantes espacial.

h/2=1000 mm

ALZADO
E 819 kN

F M
819 kN A 655 kN

B
655 kN
C 655 kN
G N D
819 kN 655 kN

H
819 kN

2000 mm

b/2= 500 mm
PLANTA

Q S
409.5 kN
E

250 mm
409.5 kN
R T

Figura 5.17. Modelo de bielas y tirantes

Los nudos A, B, C y D constituyen un único nudo y, por tanto, no se consideran
las barras que los unen entre sí.

<!-- p. 143 -->

HORMIGÓN ESTRUCTURAL 143
Hernández-Gil
En la tabla siguiente se resumen los resultados de la resolución de la estructura
articulada. Positivo es compresión y negativo tracción.

Barra AE BF EF FG FM EQ QR QS
Axil (kN) 960 686 -500 -704 655 458 -205 409.5

\3. Comprobación de las bielas

La comprobación de las bielas consiste en el cálculo del ancho y verificar si caben
en el espacio disponible. En el caso de almas de vigas sometidas a cortante, las bielas tienen
una resistencia de f1cd=0.60fcd= 0.6·34/1.5=13.6 N/mm2. Si los anchos del alma y del ala son
de 200 mm,los valores del ancho de cada biela se resumen en la tabla siguiente:

Barra AE BF FM EQ QS
Axil (kN) 960 686 655 458 409.5
Anchura (mm) 353 252 241 168 151

Representadas las bielas y sus anchos en la viga se puede concluir que son
aceptables, ver figura 5.18.

\4. Diseño de los tirantes

La armadura necesaria en los tirantes se dimensiona a tracción As,necesaria=Nd/fyd. En
este caso armamos con acero B-500-S pero como se está aplicando la teoría de bielas y
tirantes la tensión máxima será de 400 MPa.

Las bielas EF y FG se armarán igual ( no tendría sentido utilizar distinta armadura).

Barra EF FG QR
Axil (kN) -500 -704 -205
Armadura (mm2) 1250 1760 512.5
Armadura 8cØ12 8cØ12 3cØ12
(mm2) (1808) (1808) (679)

\5. Capacidad resistente de los nudos y anclajes

El nudo bajo el anclaje es un nudo multicomprimido con un estado biaxial y su
tensión máxima admisible será fcd=34/1.5=22.7 MPa. En este ejemplo la tensión existente
en el plano más desfavorable del nudo es:

·4Pd = 18 . 43 MPa \< f cd = 22 . 70 MPa
·4200·200

<!-- p. 144 -->

MÉTODO DE BIELAS Y TIRANTES 144

El resto de los nudos son nudos con tirantes anclados y, por tanto, realizada la
comprobación de bielas sólo es necesario dimensionar el anclado de los tirantes. Para el
nudo E será necesario disponer de una longitud de anclaje de 8.4cm, que en la configuración
existente ya está disponible.

As 2 As 2 1250 Lb ,neta = Lb ·β· = m·φ 0· . ·7 = 121· . 2 0· . 7 = 8 . 36 cm.
As ,real As ,real 1808

En los anclajes de piezas postesadas se suele tener en cuenta el efecto del
confinamiento del hormigón (el hormigón resiste tensiones mayores que si no estuviera
confinado). El confinamiento se puede proporcionar mediante armadura transversal o por el
hormigón circundante no cargado. Una manera de evaluar el efecto del confinamiento del
hormigón circundante es aplicando la EHE, según la cual la resistencia del hormigón en
estado triaxial es:

Ac f3 cd = fcd ≤ 3 . 3fcd
Ac 1

donde Ac1 es el área neta donde actúa la carga puntual y Ac es el área máxima no cargada,
concéntrica y homotética donde puede situarse Ac1. En este caso esto no es aplicable puesto
que Ac1 coincide con Ac.

La mayor parte de los sistemas de postesado utilizan espirales debajo de la carga
para conseguir el efecto del confinamiento, logrando mayor capacidad que con el sistema
anterior. En nuestro caso se pueden colocar espirales.

<!-- p. 145 -->

HORMIGÓN ESTRUCTURAL 145
Hernández-Gil

ALZADO
E

F M
A

B

C
G N D

H

PLANTA
Q S

E

R T

Figura 5.18. Ancho de bielas.

<!-- p. 146 -->

MÉTODO DE BIELAS Y TIRANTES 146

8 cercos Ø12 cerrados ALZADO
a 25 cm

PLANTA

1200 mm

3 cercos Ø12 cerrados
a 30 cm

Figura 5.19. Armadura.

<!-- p. 147 -->

HORMIGÓN ESTRUCTURAL 147
Hernández-Gil
Ejemplo

La norma española EHE diferencia entre zapatas rígidas y flexibles. Zapatas
flexibles son aquellas en las que se puede aplicar la teoría de flexión de la viga (hipótesis de
las secciones planas) y zapatas rígidas son aquellas que constituyen una región D y donde se
puede aplicar la teoría de las bielas. Calculemos la zapata cuadrada de la figura 5.20. En
primer lugar se calculan las dimensiones de la zapata para un Nd=500 kN y un Md=50 kN·m,
considerando que la tensión máxima que admite el terreno es de 0.2 N/mm2, que la densidad
del hormigón armado es de 2400 kg/m3 y que el espesor de zapata elegido ha sido de 1 m. Se
va a armar con acero B-400-S.

Nd

a) Md b)

1.00 m 0.09
0.16

a

Figura 5.20. Zapata cuadrada a) Tensiones sobre el terreno. b) Tensiones para el
cálculo de armaduras

Imponiendo que la tensión máxima sea inferior a 0.2 N/mm2 se obtendrá el valor de
a. Hay que hacer notar que en esta ecuación hay que añadir el peso de la zapata, dado que
este peso carga sobre el terreno. Sin embargo, cuando se procede a armar la zapata no hay
que considerar el peso ésta. Esto es así puesto que al colocar el hormigón fresco el suelo
soporta su peso pero dicho hormigón no genera esfuerzos en las barras de la armadura, La
ecuación para obtener el valor de a es:

6 a 2 − 9 50 ⋅ 10 ⋅
500000 + 1000 ⋅ a ⋅ 24 ⋅ 10 2σmáx = 0 . 2 = 2 + → a ≈ 1823 mm a 1 4 a
12

Se adoptará a=2000 mm. Las tensiones máximas y mínimas de compresión serán
0.16 y 0.09 N/mm2, respectivamente. Como hemos dicho antes, estas tensiones no son las
que se emplearán para el cálculo de la armadura ya que para esto no se considerará el peso

<!-- p. 148 -->

MÉTODO DE BIELAS Y TIRANTES 148

de la zapata. Sin embargo, en este caso ambas tensiones son prácticamente iguales: 0.16 y
0.09 N/mm2.

Antes de proceder al cálculo de la armadura por el método de las bielas, veamos
qué ocurriría si las acciones sobre la zapata fuesen Nd=200 kN y un Md=120 kN·m.
Planteando la ecuación de la flexión compuesta tenemos:

6 a 2 − 9 120 ⋅ 10 ⋅
200000 + 1000 ⋅ a ⋅ 24 ⋅ 10 2σmáx = 0 . 2 = 2 + → a ≈ 1750 mm a 1 4 a
12

lo que da una tensiones máximas y mínimas de 0.200 y -0.069 N/mm2. Puesto que la zapata
no transmite tensiones de tracción al terreno, el planteamiento de la ecuación anterior no es
válido siendo necesario plantear el siguiente sistema, en el que las incógnitas son x y a.
(Figura 5.21)

⎧0 . 2 ⋅ a ⋅ x / 2 = 200000 + a 2 ⋅ 1000 ⋅ 24 ⋅ 10 −9 x = 1052 mm
⎨ 6 →
⎩ 0 . 2 ⋅ a ⋅ x / 2 ⋅ ( a / 2 − x / 3 ) = 120 ⋅ 10 a = 1901mm

0.2
x

Figura 5.21. Incógnita x

Volvamos al caso inicial correspondiente a la la zapata sometidas a unas acciones
exteriores de Nd=500 kN y Md=50 kN·m. En la figura 5.20b se representan las tensiones
existentes cuando no se tiene en cuenta el peso de la zapata.. La norma EHE considera
zapata rígida siempre que el vuelo de la zapata sea menor de dos veces el canto de la zapata,
lo que en nuestro caso se cumple (se supone un pilar de 30×30 cm). El modelo biela-tirante
considerado es el siguiente:

<!-- p. 149 -->

HORMIGÓN ESTRUCTURAL 149
Hernández-Gil

A 0.85 d

0.16 0.09
R1d x1

Figura 5.22. Esquema de bielas y tirantes sobre una zapata

Los valores de R1d y x1 se obtienen planteando equivalencia de fuerzas y de
momentos de la mitad izquierda de la zapata. Con esos valores se plantea el equilibrio en el
nudo A para obtener la armadura necesaria de tracción.

0 .16 + 0 .09 a 1 0 . 16 + 0 . 09 a
R1d = ⋅ a ⋅ + ⋅ ( 0 . 16 − ) ⋅ ⋅ a → R 1d = 285 kN
2 2 2 2 2
0 .16 + 0 . 09 a a 1 0 . 16 + 0 . 09 a 2a
R1d ⋅ x 1 = ⋅ a ⋅ ⋅ + ⋅ ( 0 . 16 − ) ⋅ ⋅ a ⋅ → x 1 = 520 mm
2 2 4 2 2 2 2·3

As ⋅ f yd ⋅ 0 . 85d = R 1d ⋅ x 1 → As = 557 mm 2

Se colocarán 8∅10.

Referencias

Collins M.P. y Mitchell D. (1991). Prestressed Concrete Structures. Prentice-Hall. New
Jersey.

Página Personal del Prof. Daniel Kuchma (Universidad de Illinois en Urbana-Champaign)

<!-- p. 150 -->

ANÁLISIS DE LA SECCIÓN EN FLEXIÓN 150

<!-- p. 151 -->

HORMIGÓN ESTRUCTURAL 151
Hernández-Gil

CAPÍTULO VI

ANÁLISIS DE LA SECCIÓN EN FLEXIÓN

Autopista EX - A2. Badajoz.
Cortesía de JOCA. www.joca.es

6.1. INTRODUCCIÓN

Hasta ahora se han estudiado las propiedades de los materiales que forman el
hormigón armado y pretensado: hormigón y acero. En los primeros capítulos se han
estudiado los materiales, hormigón y acero, desde el punto de vista de sus propiedades
mecánicas. En este capítulo se estudiará el comportamiento conjunto hormigón-acero a
nivel sección transversal.

El primer paso en el cálculo de una estructura es modelizarla, para lo cual se
establece un sistema de referencia en el que la estructura queda definida
geométricamente por nodos y elementos. Algunos de esos nodos serán el vínculo de la
estructura al exterior. Cada elemento debe de estar definido por sus propiedades
mecánicas: áreas, inercias, momentos estáticos, cantos, anchos... Además es necesario
fijar las propiedades mecánicas de cada material (acero y hormigón): módulo de
deformación, módulo de Poisson, coeficiente de dilatación térmica, fluencia,
relajación....

<!-- p. 152 -->

ANÁLISIS DE LA SECCIÓN EN FLEXIÓN 152

Con el modelo de la estructura y con las cargas exteriores se puede realizar el
cálculo de la misma. A partir del cálculo estructural se obtendrán los desplazamientos
en todos los nodos de la estructura y, a partir de éstos, las deformaciones, tensiones y
esfuerzos en todas las secciones transversales de cada elemento.

Con los resultados obtenidos del cálculo de la estructura (esfuerzos y
deformaciones) se procederá a dimensionar1 los elementos de hormigón armado y
pretensado de tal forma que resistan los esfuerzos flectores, axiles, cortantes y de
torsión que haya en cada una de las secciones y que cumplan las limitaciones de
deformaciones (flechas y fisuras).

Como ejemplo del comportamiento de un elemento estructural se analiza la
viga de la figura 6.1 en la que el momento flector es el esfuerzo predominante. A
continuación se estudiarán las distintas fases por las que pasa esta viga hasta alcanzar la
rotura.

p
Diagrama de momentos flectores

pL 2/8

L

Figura 6.1. Viga sometida a flexión

Para una viga simplemente apoyada y sometida a una carga de valor constante por
unidad de longitud p (figura 6.1), el máximo momento se produce en el centro de luz
(pL2/8). A medida que aumenta la carga p la viga pasará por varias fases hasta su rotura
(figura 6.2):

\- Fase de pre-fisuración: comprende desde que p vale 0 hasta el valor de p para el
cual la fibra más traccionada alcanza el valor de la resistencia a tracción del
hormigón fct,m. Al momento flector que provoca esta tracción se le conoce como
momento de fisuración.

M fis = fct , m ⋅ W
(6.1)
fct , m = 0 . 30 3 fck2

1 Para iniciar el cálculo es necesario suponer unos valores iniciales en las dimensiones
de los elementos, es lo que se denomina predimensionado. La práctica es la mejor
herramienta para predimensionar. El cálculo de una estructura suele hacerse con las
propiedades mecánicas de las secciones brutas. El apartado 9.2 de este libro está
dedicado al análisis estructural.

<!-- p. 153 -->

HORMIGÓN ESTRUCTURAL 153
Hernández-Gil
donde W es el módulo resistente a tracción de la sección (W = momento de
inercia/distancia máxima a la fibra neutra en la zona de tracción). En este estado las
tensiones son tan pequeñas que se puede considerar que se está en régimen lineal.
El módulo de deformación longitudinal del hormigón en esta fase es Ecm
(ecuaciones 3.4 y 3.5). El momento de inercia, en esta fase, será el de la sección
compuesta por hormigón y acero (aunque en algunos casos basta con emplear el
momento de inercia de la sección bruta).

\- Fase de fisuración lineal: en esta fase el hormigón a tracción se ha fisurado. El
momento de inercia en las secciones fisuradas ha cambiado respecto al de la fase
anterior. El hormigón fisurado no trabaja a tracción en las secciones fisuradas y hay
que ignorarlo en el cálculo de la inercia. Si la máxima tensión de compresión en el
hormigón es suficientemente pequeña, menor de 0.45fcj, la ley de distribución de
tensiones se puede considerar lineal, esto es, se cumplirá la ley de Navier (σ=My/I).
El módulo de deformación longitudinal del hormigón en esta fase coincide con el
de la fase anterior.

\- Fase de prerrotura: se produce cuando las tensiones del hormigón se aproximan a
0.85fcj. La distribución de tensiones ya no es lineal sino que el diagrama de
tensiones se curva (ver figura 6.2).

\- Fase de rotura: este estado se produce cuando la sección de hormigón se ha
agotado completamente y se produce la rotura a compresión del hormigón y/o a la
rotura a tracción del acero. En esta fase, como en la fase anterior, se pueden
emplear diagramas simplificados para el comportamiento del hormigón como el
diagrama parábola-rectángulo o el diagrama rectangular del hormigón.

Puede que la viga no pase por todas estas fases. En una viga poco armada el acero
puede romper antes de que el hormigón alcance tensiones elevadas, en este caso la
rotura se produciría entre las fases de fisuración lineal y de prerrotura. Si la cantidad de
acero fuese muy reducida, la viga podría romper entre las fases de prefisuración y
fisuración lineal lo que significa que el acero no sería capaz de resistir ni siquiera la
resultante de las tracciones que el hormigón deja de resistir cuando fisura. Esta última
posibilidad viene limitada por todas las normas debido al peligro que esta situación
conlleva por ser una rotura sin aviso previo (limitación de cuantía mínima mecánica).
En el caso de una viga excesivamente armada, se produciría una rotura frágil del
hormigón, sin ningún tipo de aviso previo, presentándose sólo las fases de prefisuración y de rotura. Por tanto, para que se presenten todas las fases descritas
anteriormente debe de existir un armado determinado.

Para calcular una viga se ha de comprobar que no se rebasarán los Estados Límite
Últimos ni los Estados Límite de Servicio, vistos en el capítulo 2. En la viga de la figura
6.1 se debe comprobar el ELU de agotamiento frente a esfuerzos normales y cortantes,
y los ELS de fisuración y de deformación.

El agotamiento frente a esfuerzos normales se debe de comprobar en todas y cada
una de las secciones transversales de cada elemento, de forma independiente. Cada
sección deberá resistir los esfuerzos a los que se encuentra solicitada, siendo necesario
comprobar que no se llega a agotar en rotura. Por el contrario, el estudio de

<!-- p. 154 -->

ANÁLISIS DE LA SECCIÓN EN FLEXIÓN 154

deformaciones y de fisuración se realiza a nivel de todo el elemento, siendo necesario
comprobar que no se superan unas determinadas flechas o un determinado ancho de
fisura. Un ejemplo de la diferencia entre estudio a nivel seccional (agotamiento) y
estudio a nivel global (deformación) se puede ver en una cadena: una cadena romperá
por el eslabón más débil (habrá que comprobar aisladamente eslabón por eslabón) pero
para estudiar su deformación hay que sumar lo que deforman todos los eslabones.

En este capítulo nos centraremos en el estudio de secciones sometidas a tensiones
normales, o sea, dados unos esfuerzos normales (axil y momento) se comprobará cómo
se comporta una sección transversal: su deformación unitaria, su resistencia y
dimensionamiento.

6.2. HIPÓTESIS FUNDAMENTALES A NIVEL SECCIÓN

Las hipótesis fundamentales para el estudio del hormigón a nivel sección son:

\1. Distribución lineal de deformaciones. Para regiones B (definidas en el capítulo
anterior) esta hipótesis, también conocida como hipótesis de las secciones planas
o de Bernoulli, está suficientemente contrastada incluso hasta la fase de rotura.
La deformación del acero pasivo y del activo adherente (preteso y posteso) se
considera que es la misma que la del hormigón situado en su misma fibra. Si
bien, como veremos, el acero de pretensado tiene una predeformación.
\2. Curvas de comportamiento de los materiales, ya estudiadas en el capítulo 3.
\3. Para cualquier sección, tanto en elementos de hormigón armado como de
hormigón pretensado, debe de haber equilibrio entre las resultantes de las
tensiones de hormigón y acero y los esfuerzos exteriores. Este tercer punto no es
una hipótesis; no obstante, junto con los dos puntos anteriores, constituyen las
herramientas básicas para el estudio de la sección.

Distribución lineal de deformaciones

Esta hipótesis es conocida como hipótesis de las “secciones planas” o de
Bernoulli. Como ya hemos dicho, conocidas las deformaciones de dos puntos2 queda
definida la distribución de deformaciones en toda la sección. Las dos deformaciones de
referencia pueden ser o bien las deformaciones en las caras superior e inferior (εsup y εinf
respectivamente) o bien la deformación en el centro de gravedad εcdg y la curvatura φ,
ver figura 6.3.

La curvatura es la rotación experimentada por la sección por unidad de
longitud. Si se representa la deformación en términos de deformación por unidad de
longitud (ε), el gradiente de ε en una sección será la curvatura (φ), como se puede
apreciar en la figura 6.3.

2 Dos puntos en modelos en 2D y tres puntos para modelos en 3D.

<!-- p. 155 -->

HORMIGÓN ESTRUCTURAL 155
Hernández-Gil

DEFORMACIONES

Pre-fisuración Fisuración Fase de
elástica elástica rotura

TENSIONES

Figura 6.2. Hipótesis de las secciones planas

εsup
y

εcdg c.d.g.

φ
εinf

Figura 6.3. Distribución de deformaciones

La deformación del hormigón en una fibra situada a una distancia y del c.d.g.
es (ver figura 6.3):

εc = εcdg + φy (6.2)

la deformación del acero pasivo es:

<!-- p. 156 -->

ANÁLISIS DE LA SECCIÓN EN FLEXIÓN 156

εs = εcdg + φy (6.3)

y la del acero activo:

εp = εcdg + φy − ∆εp (6.4)

donde ∆εp es la diferencia de deformación del acero de pretensado, que debe de ser
determinada en función del proceso de pretensado que se realice. En la formulación
anterior se ha considerado deformación positiva la de compresión y curvatura positiva
la que produce tracciones en la parte inferior de la sección transversal.

Ecuaciones de equilibrio

El estado de tensiones existente en cualquier sección debe de generar los
esfuerzos que la solicitan, ya sean de diseño (en ELU) o característicos (en ELS). En el
caso de flexión compuesta se ha de verificar que:

p dAp N = ΣN = ∫ σ c dAc + ∫ σ s′ d As′ − ∫ σ s dAs − ∫ σ
Ac A ' s As Ap
(6.5)
p y dAp M = ΣM = ∫ σ c y dAc + ∫ σ s′ y d As′ + ∫ σ s y dAs + ∫ σ
Ac A ' s As Ap

En las ecuaciones anteriores se ha considerado positivo el esfuerzo axil de
compresión y el momento que introduce compresiones en la parte superior (ver figura
6.4).

σc
y
M

N
c.d.g.
Ap
σp
σs As

Distribución tensional generada por las
fuerzas exteriores

Figura 6.4. Distribución de tensiones

<!-- p. 157 -->

HORMIGÓN ESTRUCTURAL 157
Hernández-Gil

6.3. COMPORTAMIENTO DEL HORMIGÓN A TRACCIÓN

Como se ha comentado anteriormente, el hormigón es un material que resiste
muy poco a tracción y que, por tanto, rompe bajo tensiones de tracción pequeñas (fct).
Sin embargo, para deformaciones de tracción superiores a la correspondiente a la
tensión de tracción fct la contribución del hormigón no es despreciable: veamos lo que
esto último significa.

Consideremos la barra de la figura 6.5 cuya sección transversal está constituida
por un cuadrado de hormigón con una barra de acero situada en el centro de la sección.
Si sometemos al conjunto a una solicitación de tracción se obtiene la gráfica axildeformación longitudinal unitaria de la figura 6.5.a. En línea discontinua se ha
representado la contribución del acero en la deformación media experimentada por la
barra (conjunto hormigón-acero).

Carga de primera
N grieta

N2
N1 N1

N
Nc
N1
Ns
N1
Nc
N2 N2
N
Ns

N2
ε

a b
Figura 6.5. Contribución del hormigón a tracción

Una vez que aparece la primera grieta el hormigón deja de contribuir en la zona
de la grieta pero continúa contribuyendo en las zonas entre grietas. La figura 6.5.a
representa la contribución media del acero (línea discontinua) y del conjunto hormigónacero (línea continua). La figura 6.5.b representa el reparto de la acción exterior, pero a
lo largo de toda la barra, para los valores del esfuerzo axil de tracción N1 y N2 indicados
en la figura 6.5.a. La deformación total experimentada por la barra, aún cuando existan
numerosas grietas, es menor que la que experimentaría la barra de acero aislada.

Justo antes de que se forme la primera grieta, la tensión del hormigón era de fct
y la deformación εct. Cuando se forma la primera grieta la tensión media de tracción en
el hormigón disminuye y decrecerá tanto más cuanto más grietas haya, o sea cuando εc

<!-- p. 158 -->

ANÁLISIS DE LA SECCIÓN EN FLEXIÓN 158

aumente (εc calculada como valor medio en toda la barra). Se puede adoptar la siguiente
expresión como valor de la resistencia media del hormigón a tracción3:

α1α2 f ctm σct = (6.6)
1 + 500εct

α1 Coeficiente en función de la adherencia acero-hormigón

1 para barras corrugadas
0.7 para barras lisas, cables y cordones con muescas
0 para barras sin adherencia

α2 Coeficiente en función del tipo de carga

1.0 para carga no cíclica rápida
0.7 para carga de duración o repetitivas

al fenómeno de la contribución a tracción del hormigón se le denomina tensorrigidez.

La tensorrigidez no afecta a toda el área de la sección transversal sometida a
tracción sino sólo a una parte situada en el entorno de la barra de acero. Al área afectada
se le denomina área eficaz. Se considera que el área eficaz (Ac,eficaz) es la zona
rectangular en torno a la barra a una distancia no superior a 7.5∅.

Para cargas de corta duración el modelo planteado por el EC2 (ecuación 3.8) o
por la norma EHE puede ser complementando por la ecuación 6.6. Veamos un ejemplo.

3 El Código Modelo CEB-FIP (1990) propone una expresión distinta para el mismo
fenómeno. Por simplicidad, hemos optado por adoptar el modelo de Vechhio y Collins
(1986).

En el anejo al capítulo 7 de este libro se han presentado otras expresiones de la
tensorrigidez más actuales.

<!-- p. 159 -->

HORMIGÓN ESTRUCTURAL 159
Hernández-Gil
6.4. EJEMPLO DE RESPUESTA A CORTO Y LARGO PLAZO

La figura 6.6 corresponde a una viga pretensada pretesa de sección rectangular
de 200×100 mm, fabricada con hormigón HP-45 y con dos alambres de acero Y1670C
de ∅7.

100 mm

Deformaciones
HP-45
fcm=45+8= 53 N/mm 2 2 φ fctm=0.3fck 2/3=3.8 N/mm
200 mm Ap=77 mm 2 y 7.5∅
\+

7.5∅

Zona de
influencia
εc

Figura 6.6. Viga pretesa. Deformaciones

Optamos por una tensión de pretensado de 1200 N/mm2, lo que provoca una
deformación ∆εp de 0.006. Como diagrama tensión-deformación para el hormigón se
empleará el siguiente modelo combinado:

\- ecuación 3.8 para cargas instantáneas que generen tensiones de compresión, o
bien que generen tensiones de tracción cuya deformación sea menor de fctm /Ec.
\- y ecuación 6.6 para cargas instantáneas que generen deformaciones en tracción
mayores que la de rotura (fctm /Ec):

Así pues, el diagrama tensión-deformación del hormigón para este ejemplo
queda de la siguiente forma:

50 σ(N/mm2)

40

30

HP-45 20

10
ε

\-0.001 0.001 0.002 0.003

Figura 6.7. Diagrama tensión-deformación del HP-45 para cargas de corta
duración

<!-- p. 160 -->

ANÁLISIS DE LA SECCIÓN EN FLEXIÓN 160

El diagrama de cálculo correpondiente al acero de pretensado es el propuesto
por el Eurocódigo 2 (figura 3.26 del capítulo 3).

Las deformaciones unitarias en la sección se plantean como ε=εcdg+φy, siendo
ε la deformación a una altura y, εcdg la deformación en el c.d.g. de la sección y φ la
curvatura. Las ecuaciones de equilibrio para este ejemplo son muy sencillas: Nc+Np=0
y Mc=M. Siendo Nc el esfuerzo axil existente en el hormigón, Np el esfuerzo axil
provocado por los alambres de pretensado y Mc el momento producido por las tensiones
existentes en el hormigón. M es el momento exterior que solicita la sección.

La resolución del problema se ha efectuado con ayuda del programa
Mathematica® y se ha operado de la siguiente forma: se fija un valor de εcdg inicial y
vamos variando φhasta hacer verificar la primera ecuación de equilibrio (equilibrio de
axiles), de la segunda ecuación de equilibrio obtenemos el momento exterior M, y así
con varios εcdg4. Los resultados se recogen en la tabla 6.1 y el diagrama Momentocurvatura es el representado en la figura 6.8.

En la tabla 6.1 se indican los valores de la deformación unitaria en el centro de
gravedad de la sección (εcdg), las tensiones en las fibras superior e inferior, la curvatura
y el momento resultante.

Tabla 6.1. Valores de deformación y momentos
εcdg σsup σinf φ×103 M
×103 MPa MPa (rad/m) kN·m
0.10 15.50 -2.00 3.15 6.75
0 21.50 -1.70 5.95 8.30
\-1 39.90 -1.17 22.68 10.29
\-2 47.10 -0.99 36.52 10.51
\-3 51.07 -0.89 49.77 10.60
\-3.4 52.02 -0.85 55.00 10.63
\-4.0 52.84 -0.81 62.79 10.65
\-4.4 53.00 -0.79 67.98 10.67
\-4.8 52.83 -0.77 73.16 10.68
\-5.0 52.62 -0.76 75.76 10.68
\-5.4 51.93 -0.74 80.97 10.69
\-6.0 50.13 -0.71 88.85 10.69
\-6.4 48.81 -0.70 94.16 10.68
\-6.8 45.84 -0.68 99.56 10.67

4 Se podría haber empleado otro método (Newton-Rapson, bisección, ….)

<!-- p. 161 -->

HORMIGÓN ESTRUCTURAL 161
Hernández-Gil
Momento (kN·m)
12

10

8

6

4

2

0
0 20 40 60 80 100 120

Curvatura (rad/m)x1000

Figura 6.8. Diagrama Momento-curvatura

<!-- p. 162 -->

ANÁLISIS DE LA SECCIÓN EN FLEXIÓN 162

Listado de entrada para Mathematica®

H∗MODELIZACIÓN DE LOS MATERIALES∗L
fck= 45;
è!!!!!!!!!3
fctm = 0.3 fck2 ;
fcm = fck+ 8;
εc1= IfA0.0007fcm0.31 \< 0.0028, 0.0007fcm0.31, 0.0028E;
εcu= 0.0035;
η@ε_D := εêεc1;
fcm 0.3
Ecm = 22000 J N ;
10
εc1
κ = 1.1 Ecm ;
fcm
fpk= 1670;
εud= 0.02;
εuk= εudê0.9;
γs= 1.15;
fpd= 0.9fpkêγs;
Ep= 200000;
∆εp= 0.006;
κ η@xD −η@xD2
Interseccion= FlattenAFindRootA fcm m −fctm, 8x, 0, −0.001\<EE;
1+ Hκ −2L η@xD
Interseccion= 8xê. Interseccion@@1DD\<;
εct= Interseccion@@1DD;
0.7fctm κ η@xD −η@xD2
σc@x_D := PiecewiseA99− , x\< εct=, 9 fcm, εct\< x≤εcu=, 80, x > εcu\<=E
1+è!!!!!!!!!!!!−500 x 1+Hκ −2L η@xD
0.1 fpk Jx−fpd N
σp@x_D := PiecewiseA98Epx, 0≤x≤fpdê Ep\<, 9fpd+ γs Ep , fpdê Ep\< x≤εud=, 80, x> εud\<=E
εuk−fpd Ep

Plot@σc@xD, 8x, −0.001, 0.004\<D;
Plot@σp@xD, 8x, 0, 0.02\<, PlotRange →80, fpk\<D;
H∗EQUILIBRIO∗L
εcdg= −0.0068
φ = 0.00009956
εp= ∆εp−εcdg
Np= 77σp@εpD
‡ 100100σc@εcdg+ φ yD Åy−Np
−100
‡ 100100yσc@εcdg+ φ yD Åy
−100

<!-- p. 163 -->

HORMIGÓN ESTRUCTURAL 163
Hernández-Gil
El interés que pueda suscitar el hecho de resolver este mismo problema para
esfuerzos de carácter permanente es relativo debido a que los esfuerzos máximos
aparecen sólo en espacios de tiempo muy reducidos.

Para cargas de larga duración los fenómenos de fluencia y retracción en el
hormigón (y de relajación en el acero) hacen que las gráficas momento-curvatura sean
diferentes de las obtenidas para cargas instantáneas (figura 6.8). Continuemos con el
ejemplo para entender esto último.

Se supone que el hormigón se carga a los 28 días y que la evaluación de la
tensión se realiza a los 10000 días. Durante todo el proceso (desde los 28 días hasta los
10000 días) la carga se ha mantenido constante, con una humedad relativa del 60%.
Aplicando la fórmula de la fluencia (apartado 3.4) se deduce que el coeficiente de
fluencia (ϕ) es de 2.52. Para este caso el módulo de deformación longitudinal inicial del
hormigón es de 37500 N/mm2, valor que se ve afectado a largo plazo por el efecto de la
fluencia. Aplicando la fórmula de la fluencia se obtiene el valor del módulo de
deformación longitudinal inicial del hormigón a 10000 días.

E c 37500 2 E c ,ef = = = 10653 N / mm
1 + ϕ 1 + 2. 52

Las fórmulas de la fluencia de la EHE pueden ser empleadas sólo cuando la
tensión del hormigón es menor de 0.45fcm (en nuestro caso 0.45fcm =23.85 MPa).
Teniendo en cuenta esta limitación, sólo se podrá utilizar el módulo de deformación
longitudinal inicial antes deducido (10653 N/mm2) cuando las tensiones sean inferiores
a 0.45fcm. Para el cálculo del diagrama tensión-deformación a largo plazo se necesita
conocer el valor de la resistencia media afectada por el cansancio del hormigón:
0.85fcm=45.05 MPa y 0.85fctm=3.23 MPa. Con estos datos se puede calcular el diagrama
tensión-deformación del hormigón hasta una tensión de 0.45fcm: línea continua de trazo
grueso en la figura 6.9. Para el cálculo de la fluencia con valores de tensión de
compresión superiores a 0.45fcm se puede emplear la expresión exponencial del
Eurocódigo 2 (ecuación 3.19): línea punteada en la figura 6.9.

50 σ (N/mm2) HP-45

40
Corto plazo
30
Largo plazo

20

10

ε
\-0.001 0.001 0.002 0.003 0.004

Figura 6.9. Diagramas para el hormigón HP-45 a corto y largo plazo

<!-- p. 164 -->

ANÁLISIS DE LA SECCIÓN EN FLEXIÓN 164

Otro factor a considerar para evaluaciones a largo plazo del hormigón es la
retracción. Aplicando el apartado 3.5, el valor de la retracción (εcs ) en este problema es
0.42×10-3. La retracción se tiene en cuenta en la ecuación de compatibilidad de
deformaciones. Si suponemos que la retracción es constante en toda la sección se
obtiene la siguiente ecuación de compatibilidad de deformaciones:

εc = εcdg + εcs + φy

Se admite que la pérdida por relajación para el acero de pretensado es del 3%,
(que es la obtenida de aplicar la formulación del apartado 3.10 para 10000 días). El
nuevo módulo de deformación longitudinal del acero, Ep,ef, será 0.97·200000=194000
hasta 0.7·fpk (según el modelo de la EHE). Para tensiones mayores que 0.7·fpk se emplea
la ecuación 3.27, sustituyendo el valor de Ep por Ep,ef (modelo de la EHE para el acero
de pretensado).

Como en la resolución a corto plazo, el problema se puede resolver por
iteraciones. La respuesta a largo plazo se puede ver en la figura 6.10, en la que tambien
se ha representado el resultado obtenido a corto plazo (en este caso se ha resuelto
empleando el modelo de acero de la EHE). En esta figura se observa que el diagrama a
largo plazo no presenta valores para curvaturas mayores de 0.02 rad/m debido a que
estas curvaturas corresponden a tensiones en la sección superiores a 0.45fcm (límite de
validez de las fórmulas de la fluencia empleadas por la normativa española).

12

10

(kN·m) 8
6

4 Momento Corto plazo

2 Largo plazo

0
0 10 20 30 40 50

Curvatura (rad/m) x 1000
Figura 6.10. Diagramas momento curvatura a corto y largo plazo
Figura 6.10. Diagramas Momento-curvatura a corto y a largo plazo.

<!-- p. 165 -->

HORMIGÓN ESTRUCTURAL 165
Hernández-Gil
Conocido el diagrama momento-curvatura puede obtenerse el giro entre dos
secciones cualesquiera:

x B B
θA = ∫x A φ dx

Aplicando el segundo teorema de Mohr, o integrando la ecuación de la elástica,
se puede deducir la deformación en cualquier punto de la viga tal y como se verá más
adelante en el capítulo X.

6.5. APROXIMACIÓN LINEAL EN FASE DE PREFISURACIÓN

En fase de prefisuración (antes de que el hormigón fisure) la relación tensióndeformación se puede considerar lineal y, por tanto, las ecuaciones resultan mucho más
simples que las del apartado anterior.

Las deformaciones, como hasta ahora, tienen una distribución lineal tal y como
se deduce de la figura 6.3 y de las ecuaciones 6.2, 6.3 y 6.4, que volvemos a plasmar
aquí:
εc = εcdg + φy
εs = εcdg + φy (6.7)
εp = εcdg + φy − ∆εp

La deformación puede ser tensional o atensional. La deformación de retracción
(εcs) y la deformación térmica son atensionales. En el caso de que sólo consideremos
estas deformaciones atensionales se tiene que:

σc εc = εcs + εc∆T +
E c
σs εs = εs∆T + (6.8)
E s
σp
εp = εp ∆T +
E p

La relaciones tensión-deformación de los materiales (hormigón, acero pasivo y
acero de la armadura activa) se representan gráficamente en la figura 6.11.

<!-- p. 166 -->

ANÁLISIS DE LA SECCIÓN EN FLEXIÓN 166

σc σs σp

Ec Es Ep
εc εs εp
εcs+εc∆T εs∆T εp∆T

Figura 6.11. Relaciones tensión-deformación

La ecuación de equilibrio de axiles, tal y como se hizo en las ecuaciones 6.5,
se plantea integrando sobre la sección transversal,. Si se emplean las aproximaciones
lineales de la figura 6.11 y se tienen en cuenta las ecuaciones 6.7 y 6.8, la ecuación de
equilibrio de axiles será:

s (εcdg + φy − εs ∆T )dAs +N = Σ N = ∫ E c (εcdg + φy − εcs − εc ∆T )dAc + ∫ E
Ac As
p (εcdg + φy − ∆εp − εp∆T )dAp =+ ∫ E
Ap
⎤ ⎡ ⎡ E s E p ⎤ E s E p p ⎥ −= E cεcdg Ac + As + Ap + E cφ⎢ ∫ y dA c + ∫ y dA s + ∫ y dA ⎢⎣ E c E c ⎥⎦ ⎢ E c As E c Ap ⎥⎦ ⎣ Ac
⎡ ⎤
p ( ∆εp + εp∆T )dAp ⎥− ⎢ ∫ E c (εcs + εc ∆T )dAc + ∫ E s (εs∆T )dAs + ∫ E ⎢ ⎥ ⎣ Ac As Ap ⎦

El primer corchete de la última igualdad de la ecuación anterior es el valor del
área homogeneizada de la sección (homogeneizada en hormigón). Si se toma el origen
de la variable y en el c.d.g. de la sección homogeneizada el segundo corchete se anula,
puesto que es el valor del momento estático de toda la sección. Teniendo esto en cuenta,
la ecuación anterior queda:

N − N 0 εcdg = (6.9)
E c Ahom
siendo:
⎡ ⎤
p ( ∆εp + εp ∆T )dAp ⎥N 0 = − ⎢ ∫ E c (εcs + εc∆T )dAc + ∫ E s (εs ∆T )dAs + ∫ E ⎢ ⎥ ⎣ Ac As Ap ⎦

La ecuación de equilibrio de momentos toma la forma:

<!-- p. 167 -->

HORMIGÓN ESTRUCTURAL 167
Hernández-Gil
s y (εcdg + φy − εs∆T )dAs +M = ΣM = ∫ E c y (εcdg + φy − εcs − εc∆T )dAc + ∫ E
Ac As
p y (εcdg + φy − ∆εp − εp ∆T )dAp+ ∫ E
Ap

que se puede expresar como:

M − M 0 φ = (6.10)
E c I hom

donde M0 es:

⎡ ⎤
p y ( ∆εp + εp∆T )dAp ⎥M 0 = − ⎢ ∫ E c y (εcs + εc∆T )dAc + ∫ E s y (εs∆T )dAs + ∫ E ⎥ ⎢ ⎦ ⎣ Ac As Ap

De las ecuaciones 6.9 y 6.10 deducimos que los valores N0 y M0 son los valores
de axil y momento al que debe someterse la sección para que la deformación y la
curvatura sean nulas. Ambas ecuaciones dan lugar a gráficas momento-curvatura y axildeformación lineales, como se puede ver en la figura 6.12:

M
N
EcAhom EcIhom

M0
N0 εcdg φ

Figura 6.12. Gráficas axil-deformación del cdg y momento-curvatura

<!-- p. 168 -->

ANÁLISIS DE LA SECCIÓN EN FLEXIÓN 168

Ejemplo –respuesta a corto plazo-

Consideremos la sección transversal de una viga de hormigón pretensado
representada en la figura 6.13.

HP-45
200 mm Ap = 6 cordones Y 1860 S7 de
120 mm 15.2 de diámetro
300 mm Pérdidas a corto + largo plazo = 20%

300 mm

200 mm

400 mm

Figura 6.13. Sección transversal del ejemplo

El área de la armadura pretesa es Ap= 6·140=840 mm2. La viga está
inicialmente tesada al 70% de fpk: P0=0.7·1860·840=1093680 N. La viga está sometida
inicialmente a su peso propio más el hormigón fresco de una losa de 25 cm de espesor.
Ambas cargas producen un momento en la mitad del vano de 245 kN·m. Inicialmente
vamos a suponer que no hay deformaciones atensionales (esto es, ni fluencia, ni
relajación, ni retracción, ni cargas térmicas).

En primer lugar procedemos a calcular las características de la sección
homogeneizada:

E p 190000
n = = = 5 .06 → n − 1 = 4 .06
E c 10000 3 45 + 8

Ahom = 2 ⋅ 400 ⋅ 200 + 120 ⋅ 300 + 4 . 06 ⋅ 840 = 199410 mm 2

400 ⋅ 200 ⋅ 600 + 120 ⋅ 300 ⋅ 350 + 400 ⋅ 200 ⋅ 100 + 4 .06 ⋅ 840 ⋅ 50
y cdg = = 345 mm
199410

1 3 1 3 2 2 7 4
I hom = 400 ⋅ 700 − 280 ⋅ 300 + 4 . 06 ⋅ 840 ⋅ 300 − 199410 ⋅ ( 350 − 345 ) = 1111 × 10 mm
12 12

El siguiente paso consiste en calcular los valores de N0 y M0. En el cálculo de
N0, puesto que todas las deformaciones atensionales son nulas, la única deformación que
interviene es ∆εp. El valor de N0 queda:

0 . 7 ⋅ 1860
p ∆εp dA p = − E p ∆εp A p = − 190000 ⋅ ⋅ 840 = −1093 . 7 kNN 0 = − ∫ E 190000 Ap

<!-- p. 169 -->

HORMIGÓN ESTRUCTURAL 169
Hernández-Gil

Como era de esperar, dado que no existen deformaciones atensionales, -N0 coincide con
la fuerza de pretensado.

El valor de M0 es:

0 . 7 ⋅ 1860 ⋅ 840 ⋅ (345 − 50 ) = 322 . 6 kN ⋅ mM 0 = − E p y ∆εp dA p = E p ∆εp A p ( y cdg − y p ) = 190000 ⋅ ∫ 190000 A p

El siguiente paso consiste en calcular, para las acciones exteriores
consideradas, el valor de las deformaciones y de las tensiones:

N − N 0 1093680 − 4
εcdg = = 3 = 1 . 46 ⋅ 10 E c Ahom 10000 45 + 8 ⋅ 199410
M − M 0 ( 245 − 322 . 6 ) ⋅ 10 6 − 7φ = = = −1 . 86 ⋅ 10 rad / mm
E c I hom 10000 3 45 + 8 ⋅ 1111 ⋅ 10 7

Los diagramas de deformaciones y de tensiones en la sección de momento
máximo son los siguientes:

3.0 N/mm2 8.00×10-5

21.02×10-5 7.9 N/mm2

Figura 6.14. Deformaciones y tensiones en el hormigón

El momento máximo a corto plazo (Mcr) que origina la tensión de tracción que
agota el hormigón (fctm=3.80 N/mm2) se deduce de la siguiente expresión:

f ctm − 7 εcdg + φy inf = → φ = 7 . 165 ⋅ 10 rad / mm →
E c
→ M cr = M 0 + φE c I hom = 621 . 6 kN ⋅ m

Por último, veamos cómo queda la armadura de pretensado en el proceso a
corto plazo cuando el momento máximo es de 245 kN·m.

− 4 − 7 0 . 7 ⋅ 1860 − 3
εp = εcdg + φy − ∆εp = 1 . 46 ⋅ 10 − 295 ⋅ ( −1 . 86 ⋅ 10 ) − = − 6 . 65 ⋅ 10
190000

<!-- p. 170 -->

ANÁLISIS DE LA SECCIÓN EN FLEXIÓN 170

La tensión correspondiente es de 1264 N/mm2, lo que supone una pérdida
respecto a la tensión inicial de pretensado de un 3%..

Ejemplo –respuesta a largo plazo-

A continuación procedemos a calcular la respuesta lineal a largo plazo, para lo
cual se considerarán los fenómenos de retracción (εcs=0.42×10-3) y fluencia (ϕ=2.5) en
el hormigón y el fenómeno de relajación en el acero (3%). El momento exterior es 245
kN·m.

En primer lugar se han de calcular las nuevas propiedades de la sección
homogeneizada. Como veíamos en el apartado anterior el módulo de deformación
longitudinal del hormigón varía debido al fenómeno de fluencia y el nuevo módulo Ec,ef
tiene un valor de:

E c 2 E c ,ef = = 10732 N / mm
1 + ϕ

Debido a la relajación se produce una variación en el módulo de deformación
longitudinal del acero (apartado 3.10) cuyo valor es Ep,ef = 0.97·190000 = 184300
N/mm2. Con estos datos procedemos a calcular las características de la sección
homogeneizada:

E p ,ef 184300
n = = = 17 .17 → n − 1 = 16 . 17
E c ,ef 10732

Ahom = 2 ⋅ 400 ⋅ 200 + 120 ⋅ 300 + 16 . 17 ⋅ 840 = 209583 mm 2

400 ⋅ 200 ⋅ 600 + 120 ⋅ 300 ⋅ 350 + 400 ⋅ 200 ⋅ 100 + 16 . 17 ⋅ 840 ⋅ 50
y cdg = = 331mm
209583

1 3 1 3 2 2 7 4
I hom = 400 ⋅ 700 − 280 ⋅ 300 + 16 .17 ⋅ 840 ⋅ 300 − 209583 ⋅ ( 350 − 331) = 1195 × 10 mm
12 12

El siguiente paso consiste en calcular los valores de N0 y M0. Si no se
consideran las deformaciones por temperatura (las deformaciones que intervienen son la
de retracción y ∆εp) el valor de N0 queda:

<!-- p. 171 -->

HORMIGÓN ESTRUCTURAL 171
Hernández-Gil
p , ef ∆εp dAp = −E c , ef εcs Ac − E p , ef ∆εp Ap = −1940 . 5 kNN 0 = − ∫ E c , ef εcs dAc − ∫ E
Ac Ap
p ,ef y ∆εp dA p = − E c ,ef εcs Ac ( 350 − 331) +M 0 = − ∫ E c ,ef yεcs dAc − ∫ E
Ac Ap
\+ E p ,ef ∆εp Ap ( y cdg − y p ) = 281 . 2 kN ⋅ m

El siguiente paso consiste en calcular, para la acción exterior considerada,
momento de 245 kN·m, el valor de las deformaciones y de las tensiones:

N − N 0 1940500 − 4εcdg = = = 8 . 63 ⋅ 10
E c ,ef Ahom 10732 ⋅ 209583
M − M 0 ( 245 − 281 . 2 ) ⋅ 10 6 − 7
φ = = 7 = −2 . 82 ⋅ 10 rad / mm
E c ,ef I hom 10732 ⋅ 1195 ⋅ 10

Los diagramas de deformaciones y de tensiones correspondientes a la sección
de momento máximo son los indicados en la figura 6.15:

8.14 N/mm2 7.60×10-4

9.56×10-4 10.26 N/mm2

Figura 6.15. Deformaciones y tensiones en el hormigón a largo plazo

La deformación a largo plazo en el tendón es:

− 4 − 7 0 . 7 ⋅ 1860 − 3
εp = εcdg + φy − ∆εp = 8 . 63 ⋅ 10 − 281 ⋅ ( −2 . 82 ⋅ 10 ) − = −5 . 91 ⋅ 10
190000

Esta deformación ocasiona una tensión en el tendón de 1089 N/mm2, lo que
representa una pérdida del 11.4% respecto al pretensado inicial.

<!-- p. 172 -->

ANÁLISIS DE LA SECCIÓN EN FLEXIÓN 172

6.6. AGOTAMIENTO FRENTE A SOLICITACIONES NORMALES

Comprobar una viga o un pilar a E.L.U. de agotamiento frente a solicitaciones
normales mediante el planteamiento del apartado anterior no es práctico ya que, como
se ha visto, la obtención de la respuesta a largo plazo ha resultado excesivamente
compleja.

Tal y como se ha apuntado al principio del capítulo, el estudio del agotamiento
frente a esfuerzos normales y flectores se realiza a nivel de la sección. Las hipótesis
adoptadas para el estudio del comportamiento a nivel sección han sido: linealidad de
deformaciones, comportamiento del material según modelos de agotamiento (capítulo
\3) y equilibrio en la sección.

En agotamiento existe la posibilidad de emplear diagramas de cálculo tensióndeformación para el hormigón diferentes al empleado en el apartado anterior. En el
capítulo 3 se presentaron el diagrama rectangular, parábola-rectángulo y bilineal como
diagramas apropiados para el estudio de la sección en agotamiento. Estos diagramas
tienen la ventaja fundamental de la facilidad de uso y de que consideran el fenómeno
del cansancio del hormigón, si bien sólo se pueden aplicar en estados de rotura.

Para el acero se emplearán los diagramas especificados en el capítulo 3. Estos
diagramas tensión-deformación son los mismos que los considerados en el apartado
anterior.

A

A

Figura 6.16. Sección transversal

Para el estudio de la sección transversal A-A de las figuras 6.16 y 6.17 se
empleará la siguiente nomenclatura: d es el canto útil o distancia de la fibra superior al
centro de gravedad de la armadura traccionada, d’ es la distancia de la fibra superior al
centro de gravedad de la armadura comprimida, h es la altura de la sección y b es el
ancho.

La sección A-A de la figura 6.16 puede agotar por solicitaciones normales
siguiendo distintos planos de deformación que van desde la tracción pura a la
compresión pura, ver figura 6.17. La norma española y el Eurocódigo 2 describen toda
una serie continua de planos de deformación que producen el agotamiento de la sección,
divididos en lo que se denominan dominios de rotura, que a su vez se encuentran
limitados por los siguientes planos de deformación:

<!-- p. 173 -->

HORMIGÓN ESTRUCTURAL 173
Hernández-Gil

Sección A-A Tracción pura
B

As' (1-εc2/εcu2)/h
d' xlim ó
(1-εc3/εcu3)/h
C
h d

Compresión pura
A
As

b
εud εy 0
Diagrama parábola-rectángulo: εc2 εcu2
Diagrama rectangular: εc3 εcu3

A Deformación última del acero en tracción
B Deformación última del hormigón en compresión con flexión
C Deformación última del hormigón en compresión pura

Figura 6.17. Dominios de rotura

Plano 1: toda la sección a tracción con una deformación de εud (10‰ según la EHE) lo
que agota el acero a tracción. El hormigón obviamente ya se ha agotado antes a
tracción. Este plano corresponde a la “tracción pura”, ver figura 6.17.

Plano 2: el acero inferior está traccionado con una deformación εud (10‰ según la
EHE) y la zona superior de la viga no presenta deformación. En este plano también
agota al acero a tracción. Este plano no está representado en la Figura 6.175.

Plano 3: el acero inferior está traccionado con una deformación εud (10‰ según la
EHE) y la zona superior de la viga está a compresión con una deformación de εcu2 ó εcu36
(ambas iguales al 3.5‰ según la EHE para hormigones con resistencia inferior a 50
MPa). En este plano de deformación el acero agota a tracción y el hormigón agota a
compresión.

5 El lector puede dibujarlo e ir numerando sobre el dibujo los distintos planos y
dominios de rotura.

6 La deformación máxima del hormigón a compresión se tomará εcu2 ó εcu3 según se
emplee el diagrama parábola-rectángulo o el diagrama rectangular respectivamente.

<!-- p. 174 -->

ANÁLISIS DE LA SECCIÓN EN FLEXIÓN 174

Los planos 1, 2 y 3 pasan por el punto A de la figura 6.17. Todos los infinitos
planos de rotura comprendidos entre el plano 1 y 3 pivotan en torno al punto A y tienen
en común que en ellos el acero inferior agota a tracción.

Plano 4: el acero inferior está a tracción, con una deformación εy= fyd/Es y la fibra
superior de la viga está a compresión con una deformación de εcu2 ó εcu3 (ambas iguales
al 3.5‰ según la EHE para hormigones de resistencia inferior a 50 MPa). El hormigón
agota a compresión. En este plano de rotura la profundidad de la fibra neutra se
denomina profundidad límite (xlím). Es muy interesante observar que este plano de
deformación produce mayor momento flector que el plano anterior. Esto se debe a que
el acero inferior tanto en el plano 3 como en éste trabaja a fyd, no obstante, en este plano
la zona comprimida del hormigón es mayor que la correspondiente al plano 3. Este
plano está representado en la figura 6.17 por una línea discontinua de trazo grueso.

Plano 5: el acero inferior tiene tensión nula y la zona superior de la viga está a
compresión con una deformación de εcu2 ó εcu3. La fibra neutra en este plano se sitúa al
nivel del acero inferior. Este plano no está representado en la Figura 6.17.

Plano 6: la fibra inferior tiene tensión nula y la zona superior de la viga está a
compresión con una deformación de εcu2 ó εcu3. La fibra neutra en este plano se sitúa en
la fibra inferior de la viga.

Los planos 3, 4, 5 y 6 pasan por el punto B de la figura 6.17. Todos los
infinitos planos de rotura comprendidos entre el plano 3 y el plano 6 pivotan en torno al
punto B y agotan el hormigón a compresión.

Plano 7: agota la viga a compresión pura, con una deformación de εc2 ó εc37 (ambas
iguales al 2.0‰ según la EHE para hormigones de resistencia inferior a 50 MPa).

El dominio 1 está comprendido entre los planos 1 y 2; el dominio 2 entre los
planos 2 y 3; el dominio 3 está comprendido entre los planos 3 y 4; El dominio 4 entre
los planos 4 y 6; y el dominio 5 entre los planos 6 y 7.

Como hemos dicho antes, del plano 1 al plano 3 se puede pasar de forma
continua pivotando entorno al punto A; del plano 3 al plano 6 se puede pasar pivotando
en torno al punto B; y del plano 6 al 7 entorno al punto C. En el caso de utilizar el
modelo bilineal del acero sin endurecimiento8, el EC2 no limita la deformación en
tracción y como consecuencia el pivote A desaparece y los planos de rotura se
configuran exclusivamente con dos pivotes B y C9.

7 La deformación máxima del hormigón a compresión pura se tomará εc2 ó εc3 según se
emplee el diagrama parábola-rectángulo o el diagrama rectangular, respectivamente.

8 Se denomina endurecimiento nulo cuando no se producen aumento de tensiones para
deformaciones superiores a la correspondiente al límite elástico fy/Es (ver figura 3.19).

9 Estos dominios de rotura además pueden variar dependiendo de la normativa
empleada. La norma suiza SIA-165 o la americana ACI-318 no emplean el punto C y no

<!-- p. 175 -->

HORMIGÓN ESTRUCTURAL 175
Hernández-Gil

Cada uno de estos planos de deformación son planos de agotamiento por rotura
y para producir la deformación asociada a cada plano se necesitarán unos esfuerzos
exteriores (axil y momento flector) que, obviamente, serán distintos para cada plano de
deformación.

Como se veía en el apartado 6.2 en 2-D un plano de deformación queda
definido sólo con dos variables, generalmente la deformación en el centro de gravedad
(εcdg) y la curvatura (φ), ver figura 6.3. Es interesante observar que un plano de rotura
queda definido exclusivamente con una variable, que puede ser la profundidad de la
fibra neutra, x. O sea, a cada valor de la profundidad de la fibra neutra le corresponde un
único valor de plano de rotura y viceversa. Como hemos dicho anteriormente, para el
modelo bilineal del acero sin endurecimiento el EC2 no limita la deformación en
tracción y como consecuencia el pivote A desaparece, no existiendo en este caso valores
negativos de la profundidad de la fibra neutra: x variará de 0 a +∞.

La figura 6.17 representa los dominios de rotura o dominios de deformación
para flexión positiva, esto es, la zona comprimida está en la parte superior y la zona
traccionada en la parte inferior de la sección transversal. Se pueden obtener dominios de
deformación, similares a los de la figura 6.17, para flexión negativa (ver figura 6.28).
Esto se verá al final del ejemplo siguiente.

Se denomina diagrama de interacción10 a un gráfico M-N donde están
representados todos los pares (M,N) que producen planos de rotura. El diagrama de
interacción es un grafo cerrado donde los pares (M,N) que quedan fuera de él no podrán
ser resistidos por la sección considerada (cada sección tiene un diagrama de interacción
propio) mientras que los pares del interior sí podrán ser resistidos por la sección.

plantean diferencia entre agotamiento a compresión con flexión y agotamiento a
compresión pura. La norma Americana ACI-318 tampoco limita la deformación del
acero a tracción y todos sus dominios de rotura se pueden deducir pivotando en un solo
punto (equivalente al punto B de la figura 6.17).

10 Los diagramas de interacción axil-flector fueron introducidos por Whitney en 1956.

<!-- p. 176 -->

ANÁLISIS DE LA SECCIÓN EN FLEXIÓN 176

Ejemplo resuelto

La figura 6.18 corresponde a la sección transversal de una viga de hormigón
armado. Se pretende calcular el diagrama de interacción de la sección aplicando el
diagrama rectangular del hormigón y el parábola-rectángulo. Se aplicará la norma
española EHE. El hormigón es del tipo HA-30 y el acero es B-500-S. La armadura
superior está compuesta por 6 redondos ∅12 y la armadura inferior por 6 redondos
∅20. El ambiente considerado es del tipo IIb, por lo que el recubrimiento mínimo será:
30 mm (recubrimiento nominal) + 10 mm de margen = 40mm, que es mayor que el
diámetro de las armaduras principales y mayor de 1.25 el tamaño máximo de árido. Si al
recubrimiento de 40 mm le sumamos 10 mm por el cerco + 10 mm correspondientes al
radio de un redondo de ∅20, se obtiene 60 mm. A estos 60 mm se les suele denominar
recubrimiento mecánico. La distancia del c.d.g. de las armaduras inferiores hasta el
paramento inferior es de 60 mm. Tomaremos también 60 mm como recubrimiento
mecánico en el paramento superior (con esta hipótesis estamos del lado de la
seguridad).

A’ s=6φ12

0.5 m

As=6φ20
1.0 m

Figura 6.18. Sección transversal

Las resistencias de cálculo del hormigón y del acero son, respectivamente:

30 2
f cd = = 20 . 0 N / mm
1 . 5
500 2
f yd = = 434 . 78 N / mm
1 . 15

Los valores de las áreas de acero son A’s=6∅12=679 mm2 y As=6∅20=1884
mm2.

Plano 1

Todos los pares M, N que se van a calcular están referenciados a c.d.g. de la
sección bruta. Vamos a calcular el valor de M y N necesario para inducir a la sección de
la figura 6.18 una deformación como la representada en el plano 1 de la figura 6.17. La
resistencia a tracción del hormigón es nula puesto que estamos en rotura y planteando
equilibrio de axiles y momentos en el c.d.g. de la sección bruta (figura 6.19) se tiene:

<!-- p. 177 -->

HORMIGÓN ESTRUCTURAL 177
Hernández-Gil

60
A’s·fyd
250

As·fyd

εs=10‰

Figura 6.19. Plano 1

N = −f yd ( As + As′ ) = −1114 . 34 kN N d = ∑
M = f yd ( As − As′ ) ⋅ (250 − 60 ) = 99 . 54 kN ⋅ m M d = ∑

El par (N,M) para el plano 1 es (-1114.34;99.54).

Plano 2

Antes de calcular el par (N,M) para el plano de rotura número 2 es preciso
calcular la deformación a nivel de la armadura superior (ε’s). Para ello tendremos en
cuenta la hipótesis de linealidad de la deformación:

0 . 01 εs′ = ⇒ εs′ = 0 . 00136
500 − 60 60

60
A’s·σ’s
250

As·fyd

εs=10‰

Figura 6.20. Plano 2

<!-- p. 178 -->

ANÁLISIS DE LA SECCIÓN EN FLEXIÓN 178

fyd

Es

εy 10‰
Figura 6.21. Diagrama de cálculo del acero

Puesto que la deformación ε’s es menor que εy = fyd/Es=0.00217 el valor de la
tensión en la armadura se puede obtener a partir del diagrama de la figura 6.21 como:

σs′ = 200000 ⋅ 0 . 00136 = 272 N / mm 2 ≤ f yd

Estableciendo el equilibrio de axiles y de momentos en el c.d.g. de la sección
bruta, se obtiene que:

N = − f yd ⋅ As − σs′ ⋅ As′ = − 1003 . 81 kN N d = ∑
M = f yd ⋅ As ⋅ 190 − σs′ ⋅ As′ ⋅ 190 = 120 . 54 kN ⋅ m M d = ∑

y, por tanto, el par (N,M), para el plano 2 es (-1003.81;120.54).

<!-- p. 179 -->

HORMIGÓN ESTRUCTURAL 179
Hernández-Gil
Plano 3

El plano 3 queda definido por una deformación del 3.5‰ en la fibra extrema
superior (a compresión) y una deformación del 10% en el acero de la zona inferior (a
tracción).

εc=3.5‰ 0.85 fcd 0.85 fcd
60
A’s·σ’s 0.8x
d=440 250 x

As·fyd

Tensiones Tensiones Diagrama
εs=10‰ Diagrama rectangular Parábola-rectángulo

Figura 6.22. Plano de rotura nº3. Diagrama de tensiones

El cálculo de las fuerzas generadas en las armaduras superior e inferior se
realiza de la misma forma que en los planos anteriores. En el caso de la armadura
superior habrá que calcular la deformación para comprobar si es superior o inferior a εy.

En este caso la fibra neutra está situada a una distancia x respecto al extremo
superior (profundidad de la fibra neutra):

d x
\= ⇒ x = 114 mm
10 + 3 . 5 3 . 5

Conocida la profundidad de la fibra neutra se procede a calcular la deformación
de la armadura superior:

.0035 εs′ 2 = ⇒ εs′ = .0001658 \< εy ⇒ σs′ = E s ⋅ εy = 331.6 N / mm
114 114 − 60

Para calcular la contribución de la zona de compresión del hormigón se van a
considerar dos hipótesis distintas respecto al comportamiento mecánico del hormigón:
el diagrama rectangular y el diagrama parábola-rectángulo.

Aplicando el diagrama rectangular la resultante de las compresiones sobre el
hormigón toma el valor Nc=0.85·fcd·0.8x·b=0.85·20·0.8·114·1000=1550 kN.

Para aplicar el diagrama parábola-rectángulo hemos de tener en cuenta que el
valor de la tensión σc varía en función de y, o sea, según la fibra que se esté
considerando, tal y como podemos ver en las figuras 3.8 y 6.22. Se toman los valores:

<!-- p. 180 -->

ANÁLISIS DE LA SECCIÓN EN FLEXIÓN 180

σc = 1000 ⋅ εc ⋅ f c ⋅ ( 1 − 250εc ) para εc ≤ 0 . 002
σc = f c = 0 . 85 ⋅ f cd para 0 . 002 ≤ εc ≤ 0 . 0035

y

114 mm

εc=3.070×10-5y

εc
0.0035
Figura 6.23. Ley de deformaciones del hormigón

Si se adopta un sistema de referencia con origen en la fibra neutra (figura 6.23)
la deformación del hormigón εc obedece a la expresión εc=3.071·10-5·y. La deformación
de 0.002 corresponde a un y =65 mm y el valor de Nc es:

114 114
N c = ∫0 σc ⋅ dA = ∫0 σc ⋅ b ⋅ dy =
\= ∫065 1000 ⋅ εc ⋅ 0 . 85f cd ⋅ (1 − 250 ⋅ εc ) ⋅ b ⋅ dy + ∫ 65114 0 . 85f cd ⋅ b ⋅ dy = 1569 kN

De la misma forma, el momento producido por las compresiones en el
hormigón respecto al c.d.g. de la sección bruta, según el método del diagrama
rectangular es:
M c = N c ⋅ (250 − 0 . 4 ⋅ x ) = 1550000 (250 − 0 . 4 ⋅ 114 ) = 316 . 82 kN ⋅ m

y según el diagrama parábola-rectángulo:

114
M c = ∫0 (y + (250 − 113 .96 )) ⋅ σc ⋅ b ⋅ dy =

65
\= ∫0 (y + (250 − 113 .96 )) ⋅ 1000 ⋅ εc ⋅ f c ⋅ ( 1 − 250εc ) ⋅ b ⋅ dy +

114
\+ ∫65 (y + (250 − 113 .96 )) ⋅ 0 .85f cd ⋅ b ⋅ dy = 317 . 88 kN ⋅ m

Planteando la resultante de axiles y de momentos en el c.d.g. de la sección
bruta según el diagrama rectangular:

<!-- p. 181 -->

HORMIGÓN ESTRUCTURAL 181
Hernández-Gil
N = − f yd ⋅ As + σs′ ⋅ As′ + N c = 956 kNN d = ∑
M = f yd ⋅ As ⋅ 190 + σs′ ⋅ As′ ⋅ 190 + 316 . 84 = 515 . 23 kN ⋅ mM d = ∑

y mediante el diagrama parábola-rectángulo:

N = − f yd ⋅ As + σs′ ⋅ As′ + N c = 975 . 03 kNN d = ∑
M = f yd ⋅ As ⋅ 190 + σs′ ⋅ As′ ⋅ 190 + 317 . 71 = 516 . 29 kN ⋅ mM d = ∑

Los pares (N,M) para el plano 3 son: para el diagrama rectangular
(956.00;515.23) y para el diagrama parábola rectángulo (975.03;516.29).

Plano 4
εc=3.5‰

60
A’s·σ’s
d=440 250
xlim

As·fyd

εy=fyd/Es

Figura 6.24. Plano de rotura nº4

Establecemos la compatibilidad de deformaciones para calcular el valor de xlím:

f yd0 . 0035 +
E s 0 . 0035 d = ⇒ x lím = = 271 mm
d x lím f yd 1 +
0 . 0035 ⋅ E s

La deformación por unidad de longitud de la armadura superior (ε’s) es:

0 .0035 εs′ = ⇒ εs′ = 0 . 00273
x lím x lím − 60

Esta deformación es mayor que εy= fyd/Es=0.00217 y, por tanto, el acero de la
armadura superior trabaja a fyd.

<!-- p. 182 -->

ANÁLISIS DE LA SECCIÓN EN FLEXIÓN 182

Estableciendo el equilibrio de axiles y momentos en el c.d.g. de la sección
bruta tenemos:

\- Según el diagrama rectangular del hormigón:

N = −f yd ⋅ As + f yd ⋅ As′ + 0 . 85 ⋅ f cd ⋅ b ⋅ 0 . 8 x lím = 3161 .69 kNN d = ∑
M = f yd ⋅ As ⋅ 190 + f yd ⋅ As′ ⋅ 190 + 0 .85 ⋅ f cd ⋅ b ⋅ 0 . 8 x lím ⋅ ( h / 2 − 0 . 4 x lím ) =M d = ∑
\= 733 . 61 kN ⋅ m

\- Según el diagrama parábola-rectángulo del hormigón:

La deformación del hormigón responde a la ley que εc=1.29·10-5·y, luego la
deformación de 0.002 corresponde a y =155 mm, y los valores de Nd y Md son:

1000 ⋅ εc ⋅ 0 . 85f cd ⋅ (1 − 250 ⋅ εc ) ⋅ b ⋅ dyN d = ∑ N = −f yd ⋅ As + f yd ⋅ As′ + ∫0155

271
\+ ∫155 0 . 85 ⋅ fcd ⋅ b ⋅ dy = 3204 . 54 kN

σc ⋅ b ⋅ ( y − ( x − h / 2 )) ⋅ dy =M d = ∑ M = f yd ⋅ As ⋅ 190 + f yd ⋅ As′ ⋅ 190 + ∫0271
\= f yd ⋅ As ⋅ 190 + f yd ⋅ As′ ⋅ 190 +

155
\+ ∫0 1000 ⋅ εc ⋅ 0 . 85f cd ⋅ (1 − 250 ⋅ εc ) ⋅ b ⋅ ( y − ( x − h / 2 )) ⋅ dy +

271
\+ ∫155 0 .85 ⋅ f cd ⋅ b ⋅ ( y − ( x − h / 2 )) ⋅ dy =722 . 06 kN ⋅ m

Los pares (N,M) para el plano 4 son: (3161.69;,733.61) para el diagrama
rectangular y (3204.54;722.06) para el parábola-rectángulo.

<!-- p. 183 -->

HORMIGÓN ESTRUCTURAL 183
Hernández-Gil
Plano 5

En este plano, la armadura superior trabaja a fyd (dado que en el plano anterior
ya trabajaba a esa tensión) y la deformación ahora será ligeramente superior. La
armadura inferior no trabaja puesto que la fibra neutra coincide con el canto útil.

εc=3.5‰
60
A’s·fyd
d=440 250
x=d

εy=0

Figura 6.25. Plano de rotura nº5

Las ecuaciones de equilibrio según el diagrama rectangular del hormigón son:

N = f yd ⋅ As′ + 0 . 85 ⋅ f cd ⋅ b ⋅ 0 . 8 ⋅ d = 6279 . 20 kNN d = ∑
M = f yd ⋅ As′ ⋅ 190 + 0 . 85 ⋅ f cd ⋅ b ⋅ 0 . 8 ⋅ d ⋅ (h / 2 − 0 . 4 ⋅ d ) = 498 . 91 kN ⋅ mM d = ∑

Plano 6

En este plano la armadura superior trabaja a fyd, la inferior trabaja a la tensión
correspondiente a su deformación y la fibra neutra coincide con la fibra inferior.

εc=3.5‰
60
A’s·fyd
d=440 250 εy=fyd/Es
x=h

As·σs

Figura 6.26. Plano de rotura nº6

Establecemos compatibilidad de deformaciones:

<!-- p. 184 -->

ANÁLISIS DE LA SECCIÓN EN FLEXIÓN 184

εs 0 . 0035 2 = ⇒ εs = 0 . 00042 ⇒ σs = 84 N / mm
60 500

Las ecuaciones de equilibrio para el diagrama rectangular del hormigón dan los
siguientes resultados:

N = f yd ⋅ As′ + σs ⋅ As + 0 . 85 ⋅ f cd ⋅ b ⋅ 0 . 8 ⋅ h = 7253 . 50 kNN d = ∑
M = f yd ⋅ As′ ⋅ 190 − σs ⋅ As ⋅ 190 + 0 . 85 ⋅ f cd ⋅ b ⋅ 0 . 8 ⋅ h ⋅ (h / 2 − 0 . 4 ⋅ h ) =M d = ∑
\= 366 . 02 kN ⋅ m

Plano 7

En este plano la deformación es constante a compresión y de valor 0.002.

εc=εs=2‰
60
A’s·σs
d=440 250

As·σs

Figura 6.27. Plano de rotura nº7

Estableciendo el equilibrio, tenemos:

N = 400 ⋅ As′ + 400 ⋅ As + 0 . 85 ⋅ f cd ⋅ b ⋅ h = 9525 . 20 kNN d = ∑
M = 400 ⋅ As′ ⋅ 190 − 400 ⋅ As ⋅ 190 = − 91 . 58 kN ⋅ mM d = ∑

Hasta aquí hemos analizado la sección cuando la parte superior de la sección
transversal está comprimida, lo que se conoce como flexión positiva. En el caso de que
la compresión esté situada en la parte inferior aparecen otros 7 planos de deformación,
que corresponderían a la flexión negativa. El primero y el último de estos planos
coinciden con los de la flexión positiva. El esquema de estos nuevos 7 planos esta
representado en la figura 6.28.

<!-- p. 185 -->

HORMIGÓN ESTRUCTURAL 185
Hernández-Gil

Tracción Compresión
ε ε

10 ‰ εy 2 ‰

6 7 A 4
5

3
1

2 C
xlím

B

3.5 ‰

Figura 6.28. Planos de deformación en flexión negativa

Los resultados, tanto para flexión positiva como negativa, de los pares Nd y Md
vienen reflejados en la tabla 6.2 y se representan en la figura 6.29.

Para la confección del diagrama de interacción N-M se deberían tomar los
infinitos planos de rotura que pivotan entorno a los puntos A, B y C de las figuras 6.17
y 6.28. La figura 6.29 está confeccionada con planos de rotura espaciados entre sí 1 mm,
variando x desde –h hasta 2h, tanto para flexión positiva como para flexión negativa.

Tabla 6.2. Planos de deformación en rotura
Plano Nd (kN) Md (kN·m)
Flexión positiva
1 -1114.34 99.54
2 -1003.81 120.54
3 956.00 515.23
4 3161.69 733.61
5 6279.20 498.91
6 7253.50 366.02
7 9525.20 -91.58
Flexión negativa
2 -808.00 41.27
3 1879.22 -491.69
4 4209.51 -733.61
5 6803.13 -598.45
6 7676.16 -484.80

<!-- p. 186 -->

ANÁLISIS DE LA SECCIÓN EN FLEXIÓN 186

M (kN·m) MRmax

R 600 Q (Nd,R;Md,R)
400

200
N (kN)
2000 4000 6000 8000
\-200

\-400

\-600

Figura 6.29. Diagrama de interacción

Los diagramas de interacción Axil-Flector permiten comprobar de manera
inmediata si una determinada sección transversal (definidas geométricamente la parte de
hormigón y la de acero) resiste o no una solicitación dada por el par (N-M). Un ejemplo
de esto se ha indicado en la figura 6.29: el par que define el punto R (Nd,R;Md,R) es
resistido por la sección (no provoca la rotura de la misma) mientras que el par definido
por el punto Q (Nd,Q;Md,Q) agota a la sección.

<!-- p. 187 -->

HORMIGÓN ESTRUCTURAL 187
Hernández-Gil
6.7. FLEXIÓN SIMPLE Y FLEXIÓN COMPUESTA UNIAXIAL

Se dice que una sección está sometida a flexión pura cuando la única
solicitación a la que está sometida es un momento flector aplicado en un eje principal de
inercia. Se define flexión simple cuando la sección está solicitada por un momento
flector en un eje principal de inercia más un cortante. Flexión compuesta o flexión
compuesta uniaxial se presenta cuando la sección está solicitada a flexión pura o simple
más un esfuerzo axil. En el caso de que el momento flector no actúe sobre un eje
principal de inercia, o bien, si actuan dos momentos flectores sobre la sección, se habla
de flexión esviada o flexión biaxial.

El estudio del agotamiento de una sección sometida a flexión simple o
compuesta uniaxial se puede plantear desde dos puntos de vista: el problema de
comprobación y el problema de dimensionamiento, esquematizados de la siguiente
forma:

PROBLEMA PROBLEMA
DE DE
COMPROBACIÓN DIMENSIONAMIENTO

DATOS: DATOS:
Sección*, As, A’s, Md y Nd Sección*, Md y Nd

INCÓGNITAS: INCÓGNITAS:
x y Nmax
ó x, As y A’s
x y Mmax

\*Por sección nos referimos a la geometría del hormigón de la sección
transversal.

Figura 6.30. Los problemas de comprobación y dimensionamiento en flexión
uniaxial

El equilibrio a nivel sección se plantea en las ecuaciones 6.5, que por
comodidad se vuelven a escribir a continuación1 :

1 No se considera el acero de prentensado.

<!-- p. 188 -->

ANÁLISIS DE LA SECCIÓN EN FLEXIÓN 188

s dAs N d = Σ N = ∫ σ c dAc + ∫ σ s′ d As′ − ∫ σ
Ac A 's As
(6.11)
s y dAs M d = Σ M = ∫ σ c y dAc + ∫ σ s′ y d As′ + ∫ σ
Ac A 's As

Si se disponen dos niveles de armadura, situados a una distancia d’ y d de la
fibra superior (ver Figura 6.17), las ecuaciones de equilibrio anteriores se pueden
expresar de la siguiente forma:

N = −σs ⋅ As + σs⋅′ As′ + N c N d = ∑
(6.12) h h
M = σs ⋅ As ( d − ) + σs⋅′ As′ ( − d ′ ) + N c ⋅ y Nc M d = ∑ 2 2

donde Nc es la resultante de las compresiones en el hormigón, que depende de x
(profundidad de la fibra neutra); yNc es la distancia al centro de gravedad de la sección
bruta de la fuerza resultante de las compresiones en el hormigón, que también depende
de x.

6.7.1. El problema de comprobación

El problema de comprobación consiste en determinar si una sección totalmente
definida es capaz de resistir un determinado par axil-flector que la solicita Nd-Md.

En un problema de comprobación, en las ecuaciones 6.11 y 6.12 se conocen los
siguientes parámetros: la sección (su forma geométrica), el área de la armadura (As y
A’s) y también las acciones que actúan sobre la sección (Nd y Md). Las incógnitas en el
problema de comprobación son x y Mmax (o bien x y Nmax), tal y como se ha indicado en
el esquema de la figura 6.30. Para entender lo que esto significa, volvamos al ejemplo
resuelto del apartado 6.6, en el que la sección y las armaduras eran conocidas y, por
tanto, era posible realizar el correspondiente diagrama de interacción N-M: figura 6.29.
Basta con comprobar que un determinado par (Nd,Md) queda dentro del diagrama para
asegurar que la sección no agota. Este planteamiento, obviamente, es demasiado
costoso no siendo necesario realizar el diagrama de interacción N-M para comprobar si
una determinada sección resiste un par de esfuerzos (Nd,Md). Un planteamiento más
directo y menos costoso es el siguiente: sea el punto R (Nd,R;Md,R) representado en la
figura 6.29, de la primera de las ecuaciones 6.12 imponemos Nd=Nd,R y despejamos el
valor de x 2; de la segunda de las ecuaciones 6.12 imponiendo el valor de x anterior
obtenemos un momento que denominamos MRmax (figura 6.29). Si Md,R>MRmax la
sección no soportará el par (Nd,R;Md,R) mientras que si, por el contrario, es menor la
sección podrá soportar este par.

2 Obsérvese que el valor de la tensión de las armaduras no es incógnita sino que se
puede expresar en función de la profundidad de la fibra neutra (x). Téngase en cuenta
que a cada valor de x le corresponde un único plano de deformación de agotamiento.

<!-- p. 189 -->

HORMIGÓN ESTRUCTURAL 189
Hernández-Gil
De la misma forma se podía haber optado por imponer en la segunda de las
ecuaciones de equilibrio 6.12 que Md=Md,R y despejar x, introducir x en la primera de
las ecuaciones de equilibrio y obtener un NRmax 3.

6.7.2 El problema de dimensionamiento

Dimensionar (o armar) una sección transversal consiste en calcular la armadura
(As y A’s) necesaria para que la sección resista un determinado par (Nd,Md) 4. En este
caso en las ecuaciones 6.12 el número de incógnitas es 3: x, As y A’s siendo sólo dos las
ecuaciones de equilibrio. Luego el problema tiene infinitas soluciones.

A lo largo de la historia del cálculo de hormigón (más de un siglo) la obtención
de una solución de As y A’s se ha enfocado de distintas formas, no exentas de polémicas
en cuanto a su rango de aplicación (Páez 1986). Debido a que la capacidad de cálculo
era muy reducida, en comparación con la actual, tradicionalmente el problema se
planteaba reduciendo el número de incógnitas mediante hipótesis adicionales, las más
habituales son:

\- As=A’s, hipótesis típica para pilares
\- A’s=0 hipótesis típica en vigas descolgadas, en las que no sea necesario
disponer armadura de compresión.
\- Imponer x=xlím.

Estas hipótesis simplificatorias se siguen utilizando hoy día y, de hecho, es
habitual en los programas de cálculo proporcionar directamente la solución de armadura
simétrica si el axil es distinto de cero (Nd≠0).

El problema de dimensionamiento en el caso de dos niveles distintos de
armadura tiene infinitas soluciones. Puesto que este infinito es de grado 1 (o sea el
número de incógnitas – número de ecuaciones =1) las infinitas soluciones se pueden
representar gráficamente. Los diagramas de armado a flexión o RSD5 (del inglés
Reinforcement Sizing Diagrams) son una representación de las infinitas soluciones del
problema de armado en función de la profundidad de la fibra neutra. En el eje de
abscisas se representa la profundidad de la fibra neutra y en el eje de ordenadas se
representa área de armadura. Los RSD tienen generalmente tres gráficas (As, A’s y
As+A’s). Veamos un ejemplo de su aplicación.

3 ¿Podría el lector situar NRmax en la figura 6.29 y deducir la inecuación de resistencia?

4 Nos centramos en una sección transversal rectangular con armadura sólo en dos capas.
En el caso de que hubiera más de dos capas de armadura el problema sería más
complejo, pero en síntesis el planteamiento es idéntico.

5 Introducidos en Hdz-Montes et al. en 2003.

<!-- p. 190 -->

ANÁLISIS DE LA SECCIÓN EN FLEXIÓN 190

Ejemplo

La figura 6.31 corresponde a un ejemplo de la publicación de la ACI SP17(97). Para una sección transversal de (508×406 mm) solicitada por un par axilmomento de 3560 kN – 754 kN·m sólo se proporciona la solución simétrica. En nuestro
caso se han representado todas las posibles soluciones mediante un diagrama RSD de
armado a flexión. El hormigón tiene una resistencia de 27,6 MPa (4 ksi) y el acero de
414 MPa (60 ksi).

En el diagrama RSD de armado a flexión se pueden observar todas las
soluciones posibles. En nuestro caso se puede ver como la solución asimétrica puede
suponer un ahorro hasta del 40% sobre la solución simétrica. El ejemplo está totalmente
desarrollado en Hernández-Montes et al. (2005).

h=20 in (508 mm)

0.75h
As A’s

b=16 in (406 mm)

e Pn=800 kips (3560 kN)

Área de acero (mm2)
10000

Área total (As + A’s)
As
8000

6000

4000
A’s

2000

225 250 275 300 325 350 375 400

Profundidad de la fibra neutra, x (mm)

Figura 6.31. Ejemplo tomado de la publicación ACI- SP-17(97)

<!-- p. 191 -->

HORMIGÓN ESTRUCTURAL 191
Hernández-Gil
● Teorema de armado a flexión

En el caso de secciones transversales rectangulares con dos niveles de
armadura se verifica que, de entre las infinitas posibilidades de armar la sección de
hormigón en rotura, el mínimo de armadura (As + A’s) es una de las siguientes
soluciones6:

\- As=0 y/o A’s=0
\- x igual o ligeramente superior a xlim
\- deformación constante en toda la sección transversal igual a εud (ver figura
6.17)
\- deformación constante en toda la sección transversal igual a εc2 -ó εc3- (ver
figura 6.17).

Como corolario del teorema anterior concluimos que el problema de
dimensionamento puede abordarse de varias formas:

\1. Armadura simétrica (As=A’s). Esto es muy común cuando el elemento
estructural debe resistir distintos tipos de cargas (pares N-M) y el conjunto
de todos los pares es relativamente simétrico. Un ejemplo de esto son las
columnas de edificación, en las que, debido al viento o al sismo, el
máximo momento positivo y el mínimo negativo tienen valores absolutos
muy parecidos.
\2. Obligar a que A’s=0. Esto es típico de vigas, siempre que el momento no
sea superior a un momento denominado Mlim7.
\3. Suponer el valor de una de las dos armaduras As o A’s, o bien suponer una
relación entre ambas (i.e. As/A’s=cte).
\4. Obligar x=xlim.
\5. Calcular las soluciones en los 5 supuestos del teorema y adoptar la
solución de mínima armadura. Puede ser interesante comparar la mínima
con la solución simétrica.
\6. Realizar un diagrama RSD de armado a flexión y elegir la combinación de
armaduras que más interese.

6 Este teorema está demostrado en Hernández-Montes et al. (2007).

7 Profundidad límite de la fibra neutra:
Como ya se vió anteriormente (plano de deformación Nº 4 del Apdo. 6.6):
d
x lím = . Si observamos la figura 6.17, el momento que generan las
1+ f yd 0 . 0035 E s
tensiones en el hormigón comprimido respecto a la armadura traccionada crece según
aumenta la profundidad de la fibra neutra. No obstante, si x>xlim aunque este momento
crezca no resulta interesante puesto que el acero en tracción abandona la zona plástica y
comienza a trabajar a una tensión inferior a fyd. Por tanto, que si x>xlim el acero está
“desaprovechado”. Al momento engendrado por las tensiones internas para el valor
x=xlim se denomina Mlim.

<!-- p. 192 -->

ANÁLISIS DE LA SECCIÓN EN FLEXIÓN 192

Ejemplo de comprobación

d’=60 mm
A’ s=6φ12
HA-30
d 0.5 m B-500-S

As=6φ20
1.0 m 60 mm

Figura 6.32. Sección transversal

Vamos a calcular la capacidad a flexión simple de la sección de la figura 6.18,
reproducida nuevamente en la figura superior. Para el acero vamos a emplear el
diagrama bilineal sin endurecimiento del EC28 (Figura 6.17 y 6.33). Para el hormigón
adoptaremos las hipótesis del diagrama rectangular del EC2 con αcc=0.85 (coeficiente
de duración de carga, apartado 3.3.2).

B
xlim
C

εy 0 0.002 0.0035

Figura 6.33. Pivotes B y C para modelo del acero bilineal sin endurecimiento

De x=0 hasta x=h9 el pivote es el punto B y desde x=h hasta x=+∞ el pivote es
el punto C. En nuestro caso el valor de x en C es 3h/7 (ver Figura 6.17). Las tensiones
en el acero superior e inferior se pueden expresar en función de la profundidad de la
fibra neutra x mediante una función definida a trozos. Para formular dicha función es
necesario conocer los valores de la profundidad de la fibra neutra cuando el acero pasa
por los puntos de cedencia, tanto en compresión como en tracción (Figura 6.34).

8 Para este caso el pivote A desaparece

9 Siendo h el canto total de la sección.

<!-- p. 193 -->

HORMIGÓN ESTRUCTURAL 193
Hernández-Gil

Armadura superior

x1 x2

\-εy 0 εy 0.0035 -εy 0 εy 0.0035

(i) x1 (ii) x2

Armadura inferior
B Pivote

x3

(iv) Para acero B-500 no se produce
cedencia en compresión de la armadura
inferior, puesto que εy es mayor de 0.002

\-εy 0 εy 0.0035

(iii) x3

Figura 6.34. Profundidades de la fibra neutra para los puntos de cedencia de la armadura
superior e inferior.

Para el acero B-500 y γs=1.15 se tiene que εy=0.00217. Los valores de x1, x2 y
x3 indicados en la figura 6.34 y particularizados para la sección de la figura 6.32 son:

0 . 0035 d '
x 1 = = 37 .01 mm
0 .0035 + εy
0 .0035 d '
x 2 = = 158 . 36 mm (6.13)
0 . 0035 − εy
0 . 0035 d
x 3 = = 271 .42 mm
0 . 0035 + εy

<!-- p. 194 -->

ANÁLISIS DE LA SECCIÓN EN FLEXIÓN 194

La tensión en la armadura superior viene dada por:

⎧ − f y si x \< x 1
⎪⎪ d − x
σ' s ( x ) = ⎨ − 0 . 0035 E s si x 1 ≤ x ≤ x 2 (6.14)
x
⎪⎪ f y si x > x 2 ⎩

y, para la armadura inferior:

⎧
⎪ − f y si x \< x 3
⎪⎪ d − x
σs ( x ) = ⎨ − 0 . 0035 E s si x 3 ≤ x ≤ h (6.15)
x ⎪ d − x ⎪ − 0 . 002E s si x > h ⎪ ⎩ x − 3 h 7

Debido a que estamos empleando el diagrama rectangular del hormigón del
EC2, Nc se puede expresar de la siguiente forma:

⎧0 .85f cd b 0 . 8 x si 0 ≤ x \< 1 . 25 h
N c ( x ) = ⎨ (6.16)
⎩ 0 . 85f cd bh si x ≥ 1 . 25 h

En la expresión anterior no se han descontado las áreas ocupadas por las barras
de acero. Esto se puede tener en cuenta mediante una modificación de las expresiones
en la tensión del acero:

⎧σ' s ( x ) − 0 . 85f cd si 0 . 8 x ≥ d '
σs′ * ( x ) = ⎨
σ' s ( x ) en otro caso ⎩ (6.17)
⎧σs ( x ) − 0 . 85f cd si 0 . 8 x ≥ d
σs * ( x ) = ⎨
σs ( x ) en otro caso ⎩

Las ecuaciones de equilibrio toman la forma:

<!-- p. 195 -->

HORMIGÓN ESTRUCTURAL 195
Hernández-Gil
N = N ( x ) + σ' ( x ) A' + σ ( x ) A
d c s * s s * s

⎧ ⎛ h ⎞ ⎛ h ⎞ ⎛ h ⎞
⎪⎪N c ( x )⎜⎝ 2 − 0 . 4 x ⎟⎠ + σ' ( x ) A' ⎜ − d ' ⎟ − σ ( x ) A ⎜ d − ⎟ si 0 . 8 x ≤ h s * s ⎝ 2 ⎠ s * s ⎝ 2 ⎠M = ⎨ d ⎛ h ⎞ ⎛ h ⎞ ⎪ σ' ( x ) A' ⎜ − d ' ⎟ − σ ( x ) A ⎜ d − ⎟ en otro caso
⎪⎩ s * s ⎝ 2 ⎠ s * s ⎝ 2 ⎠
(6.18)

Con la ayuda del programa Mathematica® se resuelve el problema de la
siguiente forma: imponiendo Nd=0 se obtiene x de la primera de las ecuaciones 6.18:
x=137.78 mm. De la segunda de las ecuaciones 6.18 se obtiene el momento Md que,
debido a que estamos en rotura, será el máximo momento que la sección puede resistir
en flexión simple: Md=320.44 kN·m.

Se podría haber obtenido la misma solución de una forma más intuitiva, tal y
como se indica a continuación (se empleará la EHE).

Se supone inicialmente que As y A’s trabajan a fyd. Planteando únicamente el
equilibrio de axiles:

N = 0 .85 ⋅ fcd ⋅ b ⋅ 0 .8 ⋅ x + As′ f yd − As f yd = 0 kN N d = ∑

se obtiene un valor de x = 38.5 mm. Para este valor de x ambos aceros no trabajan a fyd
por lo que hay que replantear el sistema y ver en qué dominio de rotura estamos. El
plano de rotura 3 (figura 6.17) queda determinado por un valor de la profundidad de la
fibra neutra x=0.259d=114 mm, luego la x obtenida de ecuación anterior hace que el
plano de rotura pase por el punto A (figura 6.17) y, por tanto, se está en el dominio de
rotura 2. Planteando nuevamente el equilibrio junto con una ecuación de compatibilidad
de deformaciones:

N = 0 . 85 ⋅ f cd ⋅ b ⋅ 0 . 8 ⋅ x + As′σs − As f yd = 0 kN N d = ∑
d − x x − 60 0 . 01( x − 60 )
\= ⇒ σs = E sεs = E s
0 . 01 εs d − x

Resolviendo este sistema obtenemos: x=60.18 mm. Con este valor de x
planteamos la ecuación de equilibrio de momentos. El equilibrio de momentos se realiza
en el c.d.g. de la armadura inferior10, obteniendo:

10 En el caso de flexión simple se puede plantear el equilibrio de momentos en cualquier
punto de la sección no alterándose el valor del momento, puesto que no hay fuerza axil.
En el caso de flexión compuesta si planteamos el equilibrio en un punto diferente al que
está referenciado el momento flector, necesariamente se altera el valor de dicho
momento debido a la presencia del esfuerzo axil, y hay que tenerlo en cuenta.

<!-- p. 196 -->

ANÁLISIS DE LA SECCIÓN EN FLEXIÓN 196

M = 0 .85 ⋅ f cd ⋅ b ⋅ 0.8 ⋅ x ⋅ ( d − 0.4 x ) + σs ⋅ As′ ⋅ ( d − d )' M d = ∑

el valor de Md es 340.68 kN·m, valor que podíamos haber obtenido en el diagrama de
interacción de la figura 6.29 (intersección con la línea de N=0).

Consideremos la misma viga de la figura 6.32 pero sin armadura superior
(figura 6.35). Si la viga de la figura 6.32 estuviese dimensionada exclusivamente para
trabajar a flexión simple, el armado descrito en la figura 6.32 no sería el más adecuado
puesto que la armadura superior apenas trabaja.

¿Cuál sería el mayor momento en flexión simple que la viga de la figura 6.35
podría resistir sólo con armadura de tracción?. A este momento se le denomina
momento límite dado que se produce para una profundidad de la fibra neutra igual xlím.
Planteando la ecuación de compatibilidad de deformaciones, tenemos:

d
x lím = = 271 mm
f yd 1 +
0 . 0035 ⋅ E s
M lím = 0 . 85f cd b 0 . 8 x lim (d − 0 . 4 x lim ) = 1223 kN ·m

0.5 m d

1.0 m

Figura 6.35. Sección transversal, sólo con armadura inferior de tracción.

¿Podríamos obtener un momento superior a éste (1223 kN·m) sólo con
armadura de tracción?. La respuesta es que sí, pero esto nos obligaría a bajar la fibra
neutra por debajo de xlím, lo que nos introduciría en el dominio de rotura 4 y, por tanto,
las tensiones en el acero serían inferiores a fyd. Por tanto, la respuesta a la pregunta
anterior es que sí aunque sería muy poco práctico. Concluimos que el mayor momento
de flexión simple resistido por la sección de la figura 6.35, de una forma
económicamente satisfactoria, sería el momento límite ( cuyo valor es 1223 kN·m). A la
armadura de tracción correspondiente se le denomina cuantía límite (deducible a partir
del equilibrio de axiles). Si necesitáramos resistir un momento superior al momento

En flexión simple es útil considerar el equilibrio de momentos en la armadura
inferior porque simplifica las ecuaciones. As no entra en la ecuación de equilibrio de
momentos y el sistema queda desacoplado.

<!-- p. 197 -->

HORMIGÓN ESTRUCTURAL 197
Hernández-Gil
límite sólo tenemos dos opciones: aumentar el canto de la sección de tal forma que el
nuevo momento límite sea superior o introducir armadura de compresión. En este
último caso existirán infinitas soluciones y, en el caso particular de flexión simple y
secciones rectangulares, el Teorema de armado a flexión, anteriormente enunciado,
garantiza que x=xlím proporciona el mínimo de la armadura total.

Supongamos ahora que se pretende dimensionar la sección de la figura 6.35
para un momento -en flexión simple- igual a 1600 kN·m. Las ecuaciones de equilibrio
de axiles y de momentos son:

N = f yd ⋅ As′ + 0 . 85 ⋅ fcd ⋅ b ⋅ 0 . 8 ⋅ x lím − f yd ⋅ As = 0N d = ∑
M = f yd ⋅ As⋅′ ( d − d )' + 0 . 85 ⋅ fcd ⋅ b ⋅ 0 . 8 ⋅ x lím ⋅ (d − 0 . 4 ⋅ x lím ) =M d = ∑
\= 1600 kN ⋅ m

Si en las ecuaciones anteriores no se hubiera impuesto11 que x=xlím existirían
tres incógnitas As, A’s y x y, por tanto, el sistema tendría infinitas soluciones. En las
ecuaciones anteriores hemos supuesto que ambas armaduras trabajan a fyd. La armadura
de tracción sí trabaja a fyd puesto que estamos en x=xlím (ver figura 6.17) y la armadura
de compresión también, puesto que xlím=271 mm es mayor que la mitad de h (250 mm)
y, por tanto, la deformación de la armadura de compresión, ε’s , será mayor que la de
tracción. De la resolución del sistema tenemos: As=10764 mm2 (14∅32) y A’s=2287
mm2 (5∅25).

Imponiendo x=xlim en las ecuaciones 6.18 se obtiene un sistema de 2
ecuaciones con 2 incógnitas de cuya resolución se obtiene que: As=10769 mm2 (14∅32)
y A’s=2372 mm2 (5∅25). La pequeña diferencia entre este resultado y el del párrafo
anterior está en el hecho de que en las ecuaciones 6.18 se ha descontado al hormigón el
volumen ocupado por las barras a compresión mediante las expresiones 6.17.

11 Como se ha visto, considerar x=xlím para flexión simple es la mejor opción.

<!-- p. 198 -->

ANÁLISIS DE LA SECCIÓN EN FLEXIÓN 198

Ejemplo en hormigón pretensado

Consideremos la siguiente viga de hormigón pretensado posteso.

200 mm
HP-45
120 mm Ap = 6 cordones Y 1860 S7 de 15.2
300 mm de diámetro
Pérdidas a corto + largo plazo = 20 %
300 mm

200 mm

400 mm

Figura 6.36. Sección transversal de una viga de hormigón pretensado

El área de la armadura activa es Ap=6·140=840 mm2. La viga está inicialmente
tesada al 70% de fmax, P0=0.7·1860·840=1093680 N, y la fuerza de tesado después de
las pérdidas es P=0.8·P0=874944 N. Utilizando para el acero el modelo bilineal sin
endurecimiento propuesto por el EC2 (figura 3.26):

f p 0 1,k f pk
f pd = = = 1127 . 27 MPa
γs 1 . 1 ⋅ 1 . 5

Planteando equilibrio de axiles (figura 6.17):

0 . 85·f cd 0· . 8 ⋅ x ⋅ b = A p ⋅ 1127 . 27 → x = 116 mm

Puesto que x=116 mm \< 200 mm (espesor del ala), la compresión afecta sólo a
una porción de ala y, por tanto, el valor de b en la ecuación anterior es el ancho del ala
(valor único).

De la ecuación de equilibrio de momentos se obtiene el valor del momento
máximo:

M d = 0. 85·fcd 0·.8 ⋅ x ⋅ b ⋅ ( d − 0 .4 x ) = 571. 3 kN ⋅ m

<!-- p. 199 -->

HORMIGÓN ESTRUCTURAL 199
Hernández-Gil
Planteamiento tradicional.

Tradicionalmente se ha diferenciado entre flexión simple y flexión compuesta
aún cuando las ecuaciones de equilibrio, planteadas de forma genérica (ecuaciones
6.18), no hacen tal diferenciación.

Los problemas de dimensionamiento se han acometido tradicionalmente
diferenciando entre pequeña y gran excentricidad. Sea e la excentricidad de la carga axil
Nd tal que e=Md/Nd. Hablamos de gran excentricidad cuando e se sitúa fuera del núcleo
central de la sección y de pequeña excentricidad cuando está dentro de éste. Dicho de
otra forma, la gran excentricidad se presenta para los dominios de rotura 2,3 y 4 y la
pequeña excentricidad para el resto.

Dentro del dominio 5 conviene operar de la siguiente forma: calcular una
nueva excentricidad e2 respecto de la armadura superior y diferenciar entre los dos
siguientes casos:

εc=3.5‰
d’ A1
e2
d Nd
e0

A2

Figura 6.37. Pequeñas excentricidades

\1. Que el momento de Nd respecto a la armadura superior sea inferior que el
que el engendrado por toda la sección comprimida de hormigón respecto a
la armadura superior:

N d ⋅ e2 \< 0.85 ⋅ fcd ⋅ b ⋅ h ⋅ ( h / 2 − d 2 )

En este caso se puede prescindir de la armadura inferior y las ecuaciones
de equilibrio son:

N d = 0 . 85 ⋅ f cd ⋅ b ⋅ 0 . 8 ⋅ x + A1 ⋅ f yd
N d ⋅ e 2 = 0 . 85 ⋅ f cd ⋅ b ⋅ 0 . 8 ⋅ x ⋅ ( 0 . 4 ⋅ x − d )'

\2. En el supuesto de que no se cumpla la inecuación del caso 1, se obliga a
que toda la armadura de la sección trabaje a fyd, siendo en este caso
ecuaciones de equilibrio:

<!-- p. 200 -->

ANÁLISIS DE LA SECCIÓN EN FLEXIÓN 200

N d = 0 . 85 ⋅ f cd ⋅ b ⋅ h + A1 ⋅ f yd + A2 f yd
N d ⋅ e 2 = 0 . 85 ⋅ f cd ⋅ b ⋅ h ⋅ ( 0 . 5 ⋅ h − d )' + A2 ( d − d )'f yd

En ambos casos fyd debe de ser inferior a 400 N/mm2 puesto que el acero
agotará a compresión junto con el hormigón.

Una práctica habitual es colocar armadura simétrica cuando se producen
pequeñas excentricidades.

Hasta ahora se ha acometido el problema de comprobación y
dimensionamiento de secciones en flexión uniaxial, trantando fundamentalmente
secciones rectangulares con dos niveles de armadura As y A’s situadas a una distancia
desde la fibra superior d y d’, respectivamente. Bastaría con considerar el ancho b como
variable en función de x -en la función Nc(x) de la expresión 6.16- para extender el
problema a secciones no rectangulares. De la misma manera se pueden considerar
posiciones de la armadura distintas de d y d’ (definidas en la figura 6.17).

6.8. FLEXIÓN COMPUESTA BIAXIAL

En el apartado anterior se ha definido flexión compuesta o flexión compuesta
uniaxial cuando la sección estaba solicitada por un momento flector en un eje principal
de inercia y un esfuerzo axil. En el caso de que el momento flector no actúe sobre un eje
principal de inercia, o bien, si se presentan dos momentos flectores en dos ejes
principales de inercia se habla de flexión esviada o flexión compuesta biaxial, ver la
figura 6.38.

Las diferencias fundamentales entre flexión uniaxial y biaxial son:

\- En el caso biaxial aparece una nueva ecuación de equilibrio, siendo ahora tres las
ecuaciones de equilibrio: 1 de esfuerzos axiles y 2 de equilibrio de momentos:

p dAp N = Σ N = ∫ σ c dAc + ∫ σ s dAs + ∫ σ
Ac As Ap
p y dAp (6.19) M x = Σ M = − ∫ σ c y dAc − ∫ σ s y dAs − ∫ σ
Ac As Ap
p x dAp M y = Σ M = ∫ σ c x dAc + ∫ σ s x dAs + ∫ σ
Ac As Ap

donde As es la armadura pasiva (localizada en distintos posiciones, (ver figura 6.39) y Ap
es la armadura activa (localizada también en distintas posiciones).

<!-- p. 201 -->

HORMIGÓN ESTRUCTURAL 201
Hernández-Gil
Tracción

Fibra neutra

Compresión

b

y
Fibra neutra
Zona traccionada
φ
h
ξ M My

N Mx x

Zona comprimida

Figura 6.38. Flexión compuesta biaxial en una sección rectangular

\- La posición de la fibra neutra en flexión uniaxial se define a partir de una sola
variable (x) mientras que en flexión biaxial se requieren dos variables para
posicionar la fibra neutra: ξ y φ (figuras 6.38 y 6.39).

\- Generalmente no bastará con disponer dos niveles de armadura y, de hecho, en
secciones rectangulares es común dotar de armadura a las 4 caras.

Las demás diferencias están derivadas de la resolución numérica del problema,
puesto que los modelos de acero y hormigón no dependen del tipo de flexión (uniaxial o
biaxial) que se considere. En la figura 6.39 se representan las distribuciones de
deformaciones y tensiones en una sección no rectangular sometida a flexión biaxial. En
esta figura se aprecia cómo la fibra neutra puede no ser paralela al momento flector
aplicado.

<!-- p. 202 -->

ANÁLISIS DE LA SECCIÓN EN FLEXIÓN 202

fcu
As1·σs1
εc,max
σc
y εs
As2·σs2

As3·σs3 Fibra neutra

φ
εs 1
M
ξ My εs
x
N Mx

3
2

Centro de gravedad de la
sección bruta

Figura 6.39. Distribución de deformaciones y tensiones en una sección
sometida a flexión compuesta biaxial

6.8.1. El problema de comprobación

Paralelamente al caso uniaxial, el problema de comprobación en flexión biaxial
consiste en determinar si una sección totalmente definida resiste o no una determinada
terna axil-flector-flector que la solicita Nd-Mdx-Mdy..

En las ecuaciones 6.19, en el caso de un problema de comprobación, se
encuentran definidos los siguientes parámetros: la sección (su forma geométrica), el
área y la posición de la armadura (As) y las acciones que actúan sobre la sección (Nd,
Mxd y Myd). El valor de las tensiones en el acero y en el hormigón se pueden deducir en
función de la posición de la fibra neutra (ξ y φ, figura 6.39). Así pues, una forma de
abordar el problema de comprobación es la siguiente: tomar dos de los valores de la
terna (p.ej. Nd y Mxd) e introducirlos en sus ecuaciones de equilibrio correspondientes (2
de las 3 ecuaciones 6.19) y determinar los valores de ξ y φ. Estos valores de ξ y φ se
introducen en la tercera ecuación de equilibrio (en nuestro caso en el equilibrio de
momentos en el eje y) y de ahí se obtiene un valor de momento que denominaremos

<!-- p. 203 -->

HORMIGÓN ESTRUCTURAL 203
Hernández-Gil
Mymax. Si Myd ≥ Mymax la sección no resistirá la terna (Nd, Mxd y Myd) y sí lo hará en caso
contrario.

Igual que en el caso uniaxial, existen diagramas de interacción N-Mx-My de tal
forma que bastará comprobar que la terna (Nd, Mxd y Myd) queda dentro del diagrama
para asegurar que la sección no agota. Obviamente este planteamiento es demasiado
costoso, no siendo necesario realizar el diagrama de interacción N-Mx-My para
comprobar si una sección determinada resiste.

Ejemplo

En la figura 6.40 se representa el diagrama de interacción N-Mx-My de una
sección rectangular de 75×50 cm, de hormigón HA-25 y acero B-500-S. El
recubrimiento mecánico es de 6 cm y está armada con 16Ø20 tal y como queda
reflejado en la Figura adjunta. Para la confección del diagrama se han empleado las
hipótesis de la EHE y el programa informático del Prontuario informático del Hormigón
3.0 de Corres et al. (2001).

y N DiagramaInteracciónde
0.50 m
0.06 m
0.06 m b

0.75 m
a x

Mx
HA-25
B-500-S My

Diagrama de interacción N-Mx-My c

600
2000 kN

4000 kN
1000 kN
400

0 kN

6000 kN
200

(kN·m) 0 7000 kN
Mx -1200 -700 -200 300 800

\-200

\-400

\-600

My (kN·m)

Figura 6.40. Diagrama de Interacción N-Mx-My.

<!-- p. 204 -->

ANÁLISIS DE LA SECCIÓN EN FLEXIÓN 204

6.8.2. El problema de dimensionamiento

En flexión biaxial el problema de dimensionar (o armar) una sección
transversal implica muchas variables, fundamentalmente relacionadas con la posición y
la sección de las armaduras.

Una forma de obtener el mismo número de variables que de ecuaciones
consiste en fijar la posición de las armaduras y emplear un solo diámetro Ø. En ese
caso las variables son ξ, φ y Ø. El Prontuario informático del Hormigón 3.0 de Corres
et al. (2001) utiliza este procedimiento.

Una forma alternativa, aplicable a secciones rectangulares, y que puede llevar a
ahorros importantes de armadura es la de considerar dos separaciones distintas e iguales
en las caras paralelas (sv y sh, ver figura 6.41) conservando la simetría de la armadura.
Este procedimiento aumenta el número de incógnitas a 4: ξ, φ , Ø y sh/sv. Las ecuaciones
de equilibrio son tres:

N = N (ξ,ϕ,φ, s h s v ) ∑
M x (ξ,ϕ,φ, s h s v ) (6.20) M x = ∑
M y (ξ,ϕ,φ, s h s v ) M y = ∑

La solución óptima se puede obtener mediante diagramas RSD-biaxial como se
aprecia en el siguiente ejemplo.

<!-- p. 205 -->

HORMIGÓN ESTRUCTURAL 205
Hernández-Gil
Ejemplo

Sea una sección rectangular de 70×40 cm fabricada con hormigón HA-30 y
acero B-500-S. Se van a calcular los diagramas RSD-biaxiales para los dos casos de
carga indicados en la figura 6.41.

400 mm

y
Fibra neutra

φ
700 mm

ξ fck= 30 MPa; fyk=500 MPa
recubrimiento mecánico= 7 mm

x Caso 1 Caso 2
Nd = 200 kN 200 kN
Mxd = 300 kN·m 400 kN·m
sv Myd = 250 kN·m 100 kN·m

sh

Figura 6.41. Ejemplo de Diagrama RSD-Biaxial.

<!-- p. 206 -->

ANÁLISIS DE LA SECCIÓN EN FLEXIÓN 206

Diagrama RSD-biaxial –Caso 1-

5000

4900

4800
(mm2) 4700
total 4600

4500 Armadura 4400

4300

4200
0 1000 2000 3000 4000 5000 6000
Área de la armadura inferior + superior (mm2)

Diagrama RSD-biaxial –Caso 2-

3900

3700

(mm2) 3500
total 3300

3100
Armadura 2900

2700

2500
0 500 1000 1500 2000 2500 3000 3500
Área de la armadura inferior + superior (mm2)

Figura 6.42. Diagramas RSD-biaxiales

<!-- p. 207 -->

HORMIGÓN ESTRUCTURAL 207
Hernández-Gil
6.9. DISPOSICIONES GEOMÉTRICAS Y CUANTÍAS MÍNIMAS EN
ARMADURAS LONGITUDINALES

El objetivo fundamental de las disposiciones geométricas y las cuantías
mínimas es lograr un mejor funcionamiento estructural de los elementos así como
dotarlos de buena durabilidad. En este apartado hemos seguido fundamentalmente las
especificaciones de la norma española EHE12.

Recubrimiento

Uno de los factores más importante en la durabilidad13 del hormigón armado es
el recubrimiento de hormigón que tienen las armaduras. Se denomina recubrimiento a la
distancia mínima entre la superficie exterior del elemento y la armadura (incluyendo
cercos y estribos). Según la EHE, en el caso de armaduras pasivas y activas pretesas se
denomina ( r ) y en el caso de armadura postesa se denomina Cv al recubrimiento en
vertical y Ch al recubrimiento en horizontal, ver figura 6.42.

Cv

Armadura pasiva

\>a
Cerco o estribo >b
\>50 mm

b

\>a
\>b
\>40 mm a Ch

\>0.8 D
\>∅
\>10 mm
Separación vertical

\>1.25 D
\>∅
\>20 mm

r

Malla de reparto, si r>50 mm
r Separación horizontal

Figura 6.42. Disposiciones geométricas.

12 Otras normas tienen cuantías y disposiciones geométricas ligeramente distintas.

13 Otro factor muy importante en la durabilidad es la permeabilidad del hormigón –que
está directamente relacionada con la resistencia de éste-.

<!-- p. 208 -->

ANÁLISIS DE LA SECCIÓN EN FLEXIÓN 208

En armaduras pasivas o activas adherentes el recubrimiento cumplirá:

\1. Para armaduras principales: será mayor o igual al diámetro de la barra (ó diámetro
equivalente si se trata de un grupo de barras14) y a 0.8 veces el tamaño máximo de
árido, salvo que la disposición de armaduras respecto a los paramentos dificulte el
paso del hormigón, en cuyo caso se tomará 1.25 veces el tamaño máximo de árido.

\2. Será igual al recubrimiento nominal rnom (rnom=rmín+∆r), donde ∆r valdrá 0 mm en
elementos prefabricados con control intenso de ejecución, 5 mm en caso de
elementos in situ con control intenso de ejecución y 10 mm en el resto de los casos.
El valor de rmín viene fijado por la norma EHE en función del ambiente, del tipo de
elemento y de la resistencia característica del hormigón, estos valores oscilan entre
15 mm y 40 mm. En la siguiente tabla se muestran algunos de los rmín establecidos
por la EHE.

Tabla 6.3. Recubrimientos mínimos
Resistencia Tipo de Recubrimiento mínimo (mm) según la clase de
característica elemento exposición
del hormigón I IIa IIb IIIa IIIb IIIc IV Qa
(N/mm2)
25 ≤ fck \< 40 General 20 25 30 35 35 40 35 40
Elementos 15 20 25 30 30 35 30 35
prefabricados
y láminas

\3. En barras dobladas será siempre mayor de dos diámetros, medidos en dirección
perpendicular a la curva.

\4. Si el recubrimiento total es mayor de 50 mm se dispondrá de una malla de reparto
en medio del espesor.

\5. rmín será de 70 mm en piezas hormigonadas contra el terreno, salvo que se haya
previsto hormigón de limpieza.

Para armaduras postesas el recubrimiento cumplirá:

\1. Cv será mayor de 4 cm y mayor que la dimensión horizontal de la vaina o grupos de
vainas en contacto (a), ver figura 6.42.

14 Se pueden colocar varias barras juntas en contacto (hasta 3 en horizontal y 4 en
vertical) formando lo que se denomina grupo de barras. Se considera como diámetro
del grupo de barras al diámetro de la sección circular equivalente. Este diámetro no será
mayor de 50 mm, salvo en piezas comprimidas hormigonadas en vertical, en las que
puede ser de 70 mm.

<!-- p. 209 -->

HORMIGÓN ESTRUCTURAL 209
Hernández-Gil
\2. Ch será mayor de: 4 cm, la mitad de la dimensión vertical de la vaina o grupo de
vainas en contacto (b/2) y la dimensión horizontal de la vaina o grupo de vainas (a),
ver figura 6.42.

Distancia entre barras

El origen de esta limitación está en que todas las barras deben quedar bien
envueltas en hormigón, permitiendo un vibrado adecuado. Las distintas normas
proponen unos valores mínimos para la distancia entre barras.

La EHE establece que la distancia libre para armadura pasiva, horizontal y
vertical, entre dos barras aisladas consecutivas, salvo que formen grupos de barras, será
igual o superior a:

\- 20 mm
\- ∅máx (el diámetro de la mayor)
\- 1.25 veces el tamaño máximo de árido (D).

En armadura pretesa, la separación libre mínima de los tendones individuales
(figura 6.42) debe de ser mayor de:

\- 20 mm para la separación horizontal y 10 mm para la vertical
\- el diámetro de la mayor: ∅
\- 1.25 el tamaño máximo del árido D para la separación horizontal y 0.8
para la vertical.

Para armadura postesa, “se admite colocar en contacto diversas vainas
formando grupo, limitándose a dos en horizontal y a no más de cuatro en conjunto. Para
ello, las vainas deben ser corrugadas”. Las distancias libres (figura 6.42) son como
mínimo:

En vertical: - el diámetro de la vaina
\- la dimensión vertical de la vaina o grupo de vainas
\- 5 centímetros.

En horizontal: - el diámetro de la vaina
\- la dimensión horizontal de la vaina
\- 4 centímetros
\- 1.6 veces la mayor de las dimensiones de las vainas individuales
que formen un grupo de vainas.

<!-- p. 210 -->

ANÁLISIS DE LA SECCIÓN EN FLEXIÓN 210

Cuantía mínima de los estribos para que la armadura pasiva trabaje a compresión

Con objeto de tener en cuenta la contribución de la armadura pasiva a
compresión es necesario asegurar que ésta no pandee, tal y como indica la línea
punteada de la figura 6.43. Es función de los cercos y estribos mantener la armadura
pasiva en su lugar para que ésta colabore a compresión.

st

Figura 6.43. Separación de estribos

La separación entre cercos st deberá cumplir:

⎧ s t \< 15φmin ⎧s t = 15φmin
(6.21) ⎪⎨ φmax o bien ⎪⎨ s 2t = 152 φmin φt = ⎪⎩ 4 ⎪φt φmax ⎩ 16

donde st y ∅t son, respectivamente, la separación y el diámetro de los estribos y ∅máx y
∅mín los diámetros máximo y mínimo de la armadura longitudinal comprimida.

Con objeto de garantizar el buen funcionamiento de la armadura a compresión
la norma EHE recomienda que, al menos, estén sujetas las barras de las esquinas y una
de cada dos de las situadas en las caras, siempre que la distancia entre ellas sea menor
de 15 cm. Si la distancia es mayor de 15 cm deben de estar sujetas todas.

<!-- p. 211 -->

HORMIGÓN ESTRUCTURAL 211
Hernández-Gil

Figura 6.43. Atado de la armadura longitudinal mediante cercos

Cuantía mínima en flexión simple o compuesta

En flexión simple o compuesta se dispondrá una armadura mínima de origen
mecánico. En el instante en que el hormigón se fisura, la tracción que hasta ese
momento estaba resistiendo el hormigón pasa al acero. El acero tiene que tener, como
mínimo, la capacidad de absorber el esfuerzo que estaba soportando el hormigón a
tracción antes de fisurar. A esa cuantía mínima se le denomina cuantía mínima
mecánica y se formula a partir de la siguiente expresión:

W1 Ap f pd + As f yd ≥ 0 . 25 fcd (6.22)
h

donde W1 es el módulo resistente de la sección bruta relativo a la fibra más traccionada
y h el canto total de la sección.

Además la EHE obliga a llevar hasta los apoyos 1/3 de la armadura máxima
necesaria a flexión.

Cuantía mínima en compresión simple o compuesta

La normativa actual impone límites superior e inferior a la cuantía de armadura
para elementos a compresión. El límite superior está relacionado con la dificultad que
puede presentarse durante el hormigonado si existe demasiada armadura. El límite
inferior de armadura está relacionado con la necesidad de que las columnas tengan
resistencia a flexión así como para reducir los efectos de fluencia y retracción en el
hormigón.

En este caso, las armaduras superior e inferior en compresión A’s1 y A’s2
deberán cumplir:

As′ 1f yc , d ≥ 0 . 05N d As′ 1f yc , d ≤ 0 . 5fcd Ac
(6.23)
As′ 2 f yc , d ≥ 0 . 05N d As′ 2 f yc , d ≤ 0 .5fcd Ac

<!-- p. 212 -->

ANÁLISIS DE LA SECCIÓN EN FLEXIÓN 212

donde fyc,d es la resistencia de cálculo del acero a compresión fyc,d=fyd ≤400 N/mm2.

Cuantía mínima en tracción simple o compuesta

En este caso se deberá cumplir que:

A p f pd + A s f yd ≥ 2.0 Ac f cd (6.24)

Cuantías geométricas mínimas

El origen de las cuantías geométricas mínimas está en controlar de forma
simplificada los efectos térmicos y de retracción. Los valores de estas cuantías se
establecen en ‰ de la sección total de hormigón.

Tabla 5.5. Cuantía mínima geométrica
Tipo de elemento estructural Tipo de acero
B 400 S B 500 S
Pilares 4.0 4.0
Losas (*) 2.0 1.8
Vigas (**) 3.3 2.8
Muros Armadura horizontal 4.0 3.2
(***) Armadura vertical 1.2 0.9

(*) Cuantía mínima de cada una de las armaduras, longitudinal y transversal, repartida
en las dos caras. Las losas apoyadas sobre el terreno requieren un estudio especial.
(**) Cuantía mínima correspondiente a la cara de tracción. Se recomienda disponer en
la cara opuesta una armadura mínima igual al 30% de la consignada.
(***) La cuantía mínima vertical es la correspondiente a la cara de tracción. Se
recomienda disponer en la cara opuesta una armadura mínima igual al 30% de la
consignada.
La armadura mínima horizontal deberá repartirse en ambas caras. Para muros vistos por
ambas caras debe disponerse el 50% en cada cara. Para muros vistos por una sola cara
podrán disponerse hasta 2/3 de la armadura total en la cara vista. En el caso en que se
dispongan juntas verticales de contracción a distancias no superiores a 7.5 m, con la
armadura horizontal interrumpida, las cuantías geométricas horizontales mínimas
pueden reducirse a la mitad.

<!-- p. 213 -->

HORMIGÓN ESTRUCTURAL 213
Hernández-Gil
Empalme de las armaduras pasivas

Puesto que las barras de armadura pasiva se suministran en longitudes
máximas de 12 m, a veces es necesario empalmar las barras en obra.

Los tipos de empalme que se pueden realizar son:

\- Empalme por solapo: colocando una barra junto a la otra a una distancia menor de
4∅. La longitud de solapo viene establecida en la EHE en función de la longitud de
anclaje.
\- Empalme por soldadura: soldando una barra a la otra, bien en ángulo o a tope.
\- Empalmes mecánicos: mediante dispositivos mecánicos.

<!-- p. 214 -->

ANÁLISIS DE LA SECCIÓN EN FLEXIÓN 214

Ejercicios propuestos

\1. La figura inferior corresponde a una viga de 60×100 cm, fabricada con hormigón HA25 y con acero B-400-S. Las armaduras superior e inferior están compuestas por 5∅20.
Se pide: 1. Realizar el diagrama de interacción y deducir a partir de él el momento
máximo en flexión simple que puede soportar la sección, 2. ¿Qué armadura de
pretensado centrado habría que introducirle para que resistiera en flexión simple un
momento máximo del doble del anterior?

→ ∅20
0.6 m Ap

1.0 m

\2. La figura inferior corresponde a una viga de 60×100 cm, fabricada con hormigón HA25 y con acero B-400-S. Plantear las ecuaciones de la flexión compuesta para que resista
las acciones exteriores de Nd=300 kN y Md=500 kN·m. Una vez planteadas resolverlas
aceptando las siguientes hipótesis: a) x=xlím y b) As=A’s.

0.6 m

1.0 m

\3. En la figura inferior se presenta una viga en T de un puente. Las armaduras, tanto las
de tracción como las de compresión, se colocan de manera que el recubrimiento mínimo
al paramento exterior más próximo sea de 25 mm. Las distintas barras están separadas
entre sí al menos un diámetro. La calidad del hormigón es HA-35 y el acero es B-500SD. Los coeficientes de seguridad de minoración de materiales son 1.5 para el hormigón
y 1.15 para el acero. Las vigas son de hormigón armado, dado que la luz es de 10 m, y
se colocan simplemente apoyadas.

<!-- p. 215 -->

HORMIGÓN ESTRUCTURAL 215
Hernández-Gil

1300

250

650

250

Se pide:
a. Aplicando la EHE calcular el ancho eficaz de la viga en T.
b. Deducir los valores límite: xlím, momento límite y cuantía límite.
c. Fijar x=250 mm y calcular el momento de agotamiento en flexión simple sin
armadura de compresión.
d. Razona el motivo por el que una viga en T resulta económica desde el punto de
vista del ahorro de hormigón.

\4. Para el problema de la viga en doble T (ejemplo de hormigón pretensado) plantear
todo el sistema como si agotara en el dominio de rotura 3 y establecer las conclusiones
correspondientes.

\5. En el problema de la zapata del capítulo anterior, bajar el canto hasta que sea una
zapata flexible y calcular la armadura resultante. ¿Qué armadura habría que disponer si
las acciones sobre la zapata fueran Nd=200 kN y Md=120 kN·m y ésta tuviese 1 m de
canto?

<!-- p. 216 -->

ANÁLISIS DE LA SECCIÓN EN FLEXIÓN 216

Referencias:

ACI Committee 340 (1997), ACI Design Handbook: Design of Structural Reinforced
Concrete Elements in Accordance with the Strength Design Method of ACI 318-95, ACI
Special Publication SP-17(97), American Concrete Institute, Detroit, Michigan.

ACI 318 (2005), Building Code Requirements for Structural Concrete, American
Concrete Institute, Detroit, Michigan.

Collins M.P. y Mitchell D. Prestressed Concrete Structures. Prentice Hall. 1991. New
Jersey.

Corres Peiretti H., Martínez Martínez J.L., Pérez Caldentey A. y López Agüí J.C.
Prontuario Informático del Hormigón Estructural 3.0. IECA. (www.ieca.es).

Hernández-Montes E., Gil-Martín L.M. y López-Aragón J.A. “Diagramas de
dimensionamiento en flexión para hormigón”. Hormigón y Acero, Nº 227.Primer
trimestre 2003. Pág. 67-74.

Hernández-Montes E., Gil-Martín L.M. y Aschheim M.A. (2005) “The Design of
Concrete Members Subjected to Uniaxial Bending and Compression Using
Reinforcement Sizing Diagrams”. Structural Journal. ACI. Volumen 102, Nº1, EneroFebrero 2005. Pág. 150-159.

Hernández-Montes, E., Aschheim, M and Gil-Martín, L.M. (2004). “The impact of
optimal longitudinal reinforcement on the curvature ductility capacity of reinforced
concrete column sections”. Magazine of Concrete Research, 56, No. 9, Noviembre,
499-512.

Páez, Alfredo (1986). Hormigón Armado, tomo 1. Editorial Reberté. Barcelona.

Priestley, M.J.N., Park, R., y Lu,F., “Moment Curvature Relationships for Prestressed
Concrete in Constant Moment Zones”. Magazine of Concrete Research, Vol.23, N0.7576, Junio-Septiembre. 1971. pp. 69-78.

Vecchio, F.J., y Collins, M.P., "The Modified Compression Field Theory for Reinforced
Concrete Elements Subjected to Shear", ACI Journal, Vol. 83. Nº2, Marzo-Abril. 1986.
pág. 219-231

<!-- p. 217 -->

HORMIGÓN ESTRUCTURAL 217
Hernández-Gil

<!-- p. 218 -->

CORTANTE 218

<!-- p. 219 -->

HORMIGÓN ESTRUCTURAL 219
Hernández-Gil

CAPÍTULO VII

CORTANTE

Agotamiento por cortante.
Cortesía del Instituto Eduardo Torroja. CSIC

7.1. INTRODUCCIÓN

Vamos a iniciar el capítulo de cortante con un ejemplo. En la figura 7.1 se
representan los diagramas de momentos flectores y de esfuerzos cortantes de una viga
simplemente apoyada de sección rectangular y fabricada con hormigón armado.

<!-- p. 220 -->

CORTANTE 220

ESTADO DE TENSIONES
Tensiones normales Tensiones tangenciales
B A
SECCIÓN A-A

B A

SECCIÓN B-B

Figura 7.1. Viga simplemente apoyada

En la sección A-A las tensiones normales son máximas y las tensiones
tangenciales son nulas. La rotura de tracción que se puede presentar en la sección AA
será del tipo grietas verticales dado que las tracciones existentes son horizontales1. En la
sección BB se presentan tanto tensiones normales como tangenciales: en la parte
inferior de la sección BB las tensiones normales son de tracción y las tensiones
tangenciales son nulas y, por tanto, el comportamiento en esa zona es similar al de la
sección AA, apareciendo grietas de tracción verticales. En la figura 7.2 se ha aislado un
diferencial de área de la zona de la fibra neutra de la sección BB2 y se ha representando
el estado de tensiones mediante el círculo de Mohr3.

1 Téngase en cuenta que las grietas son siempre perpendiculares a las direcciones
principales de tracción.
2 Donde las tensiones normales son nulas y máximas las tensiones tangenciales.
3 En la representación en el círculo de Mohr hemos considerado tracciones positivas y
tensiones tangenciales positivas si van en sentido horario. Este criterio es diferente al
que estamos usando y sólo lo emplearemos en el círculo de Mohr.

<!-- p. 221 -->

HORMIGÓN ESTRUCTURAL 221
Hernández-Gil

τ

P

P σ

Dirección principal de tracción

Figura 7.2. Estado de tensiones en el c.d.g. de la sección BB y círculo de Mohr
correspondiente.

Como se puede observar, las grietas que aparecen en la zona de la fibra neutra
de la sección BB forman 45º con la horizontal, de tal forma que el agotamiento por
cortante de la viga de la figura 7.1 se puede producir por extensión de las grietas a 45º
en la forma que aparece en la figura 7.3. La manera de impedir el agotamiento por
cortante, es decir, que la zona central de la viga descienda, es coser la grieta mediante
barras verticales (cercos y estribos) y/o mediante barras horizontales levantadas. El EC2
recomienda que al menos el 50% de la armadura transversal de cortante sea del tipo
cerco.

V V
Armadura longitudinal

Barras levantadas
Armadura transversal

Viga agotada por cortante

Cerco Estribos

Figura 7.3. Armadura de cortante

Sea una viga de sección rectangular como la representada en la figura 7.3 y V,
el valor del cortante que origina el agotamiento de la sección. La grieta de cortante se
supone comprendida entre la armadura longitudinal y el centro de gravedad de la zona
de compresiones, ver figura 7.4. En este caso particular la armadura de cortante está
compuesta exclusivamente por cercos o estribos a 90º separados una distancia s.
Cosiendo la grieta hay z/s estribos, que son los encargados de resistir el cortante
(además de lo que contribuya el hormigón en la zona de compresión). Tal y como se
indica en la figura 7.4, z es el brazo mecánico: distancia entre los cc.dd.gg. de la zona
comprimida y de la zona traccionada -éste último estará centrado en la armadura de
tracción-. El valor de z se puede calcular o bien tomar z=0.90d, siendo d el canto útil.

<!-- p. 222 -->

CORTANTE 222

Zona de compresiones

c.d.g. de la zona de d
compresiones
Asfyd z

s

z

Figura 7.4. Colaboración de los cercos en la resistencia a cortante

La contribución de la armadura en la resistencia a cortante (Vsu) es:

0 . 9 d
Vsu = As f y 90 , d o bien Vsu = A90 f y 90 , d 0 . 90 d (7.1)
s

donde As es el área de la armadura que cada cerco o estribo aporta para la resistencia a
cortante y A90 es el área de la armadura de cortante por unidad de longitud. Para
entender esto volvamos sobre la figura 7.3, en la que se ha representado un cerco, en el
que hay dos ramas que impiden que la parte central de la viga descienda. En la misma
figura se representan dos estribos: uno de dos ramas y otro de cuatro ramas. Obviamente
el estribo de cuatro ramas tiene el doble de capacidad para resistir el esfuerzo cortante
que el estribo de dos ramas. Las fórmulas de este ejemplo son válidas sólo para
hormigón armado cuando los cercos están a 90º y con bielas de hormigón a 45º (i.e.
grietas a 45º).

De lo expuesto en esta introducción podemos sacar varias conclusiones:
1ª. Para resistir el esfuerzo cortante la armadura debe ser del tipo cercos, estribos o
barras levantadas. Puesto que el hormigón en la zona de compresiones también
colaborará a resistir el cortante, si este esfuerzo es pequeño podría no ser necesaria
armadura de cortante.
2ª. El cortante no afecta a una sección transversal determinada sino a una zona de la
viga. Esta consideración nos permite desestimar, en cuanto al cálculo de la armadura de
cortante se refiere, la zona de la viga situada a menos de d (canto útil) del apoyo (ver
figura 7.7). Esto es debido a que el cortante comprendido entre la cara del pilar y la
sección situada a la distancia d no produce grietas en la viga ya que la biela de
compresión generada por el cortante continúa hacia el interior del pilar, sin afectar a la
viga.

En la figura 7.5 se aprecia una rotura por cortante típica en las proximidades
de un apoyo.

<!-- p. 223 -->

HORMIGÓN ESTRUCTURAL 223
Hernández-Gil

Figura 7.5. Rotura de cortante

7.2. ESFUERZO CORTANTE EFECTIVO

El esfuerzo cortante efectivo Vrd es el valor del esfuerzo cortante que debe de
considerarse para efectuar la comprobación relativa al Estado Límite de Agotamiento
por esfuerzo cortante, o sea, el cortante que “realmente” debe de resistir la sección.

El cortante producido por las acciones exteriores Vd puede no ser el único
cortante que deba de resistir la sección. Se pueden presentar dos cortantes adicionales:
el cortante producido por la fuerza de pretensado4 (Vpd) y el cortante producido por la
variación del canto de la sección transversal (Vcd). La formulación que propone la EHE
es:

Vrd = Vd + V pd + Vcd (7.2)

El pretensado produce dos efectos sobre la resistencia a cortante, que se
contabilizan por separado:

4 Componente de la fuerza de pretensado paralela a la sección transversal. Esta
componente tiene la misma dirección que Vd , tal y como se aprecia en la figura 7.6.

<!-- p. 224 -->

CORTANTE 224

\- El primer efecto se debe al axil que el pretensado introduce sobre el elemento
(proyección de la fuerza de pretensado sobre la línea media del elemento).
Este axil mejora la resistencia a cortante del hormigón, tal y como se verá
más adelante.
\- El segundo efecto se debe a la proyección vertical de la fuerza de pretensado
y que se resta directamente al esfuerzo cortante. Éste efecto es el que se
tratará en este apartado. En el elemento de la figura 7.6, la sección señalada
debe de resistir un esfuerzo cortante de valor: Vrd = Vd - P0 senα.

P0
P0senα
α

Vd

Figura 7.6. Contribución del pretensado para resistir el esfuerzo cortante

Si el elemento es de canto variable los ccddgg de compresiones y de tracciones
no son paralelos a la línea media de la sección, lo que hace que las resultantes de las
compresiones y de las tracciones tengan componentes paralelas a la sección transversal
(Vcd), tal y como se aprecia en la figura 7.7. El esquema de la derecha, correspondiente a
la sección AA, permite apreciar cómo la acción vertical Vd es suma de tres términos:
Tsenα, Csenβy el término que deberá resistir la sección transversal, Vrd.

d A
Sección AA

α T
Armadura Vrd Vd z
cdg de β
compresiones C

A
Vd=Vrd+Tsenα+Csenβ

Vd
Vcd

Figura 7.7. Cortante en piezas de canto variable

<!-- p. 225 -->

HORMIGÓN ESTRUCTURAL 225
Hernández-Gil
En el ejemplo de la figura 7.7 ambas componentes son favorables5 y, por tanto:
Vrd= Vd -(T senα+ C senβ). Se dice que las componentes son “favorables” cuando el
cortante que realmente debe de resistir la sección (Vrd) es menor que el que actúa sobre
ella (Vd). En el caso de flexión simple (axil nulo) se cumple que:

T cos α = C cos β ⇒ M = T cos α·z = C cos β·z ⇒
M M
Vrd = Vd − tanα− tan β (7.3)
z z 144424443
Vcd

7.3. DISTRIBUCIÓN DE TENSIONES TANGENCIALES EN EL HORMIGÓN

La distribución de tensiones tangenciales que aparece en la figura 7.1 obedece
a la ley de Colignon6:

V ⋅ S z τ = (7.4)
bw ⋅ I z

Esta ley podría ser aceptable en prefisuración pero no es aplicable cuando el
hormigón está fisurado, como sucede en el caso de que existan tracciones. De hecho, en
ELU se desprecia la colaboración del hormigón a tracción, lo que equivale a suponer
que éste se encuentra totalmente fisurado.

Existen otras particularidades que llevan a no poder considerar de forma
general la distribución de Colignon como es el hecho de que el hormigón estructural es
un material compuesto donde uno de los materiales presenta fluencia, con la
consiguiente alteración de la distribución de tensiones en función del tiempo.

Por lo anteriormente expuesto se hace necesario considerar una distribución de
tensiones tangenciales distinta. Para ello se va a calcular el valor de τen la fibra neutra,
siguiendo la notación indicada en la figura 7.8, que representa una rebanada de viga de
dx de longitud. En esta figura cualquier plano a-b comprendido entre la fibra neutra y la
armadura de tracción debe verificar la siguiente ecuación para equilibrar la diferencia de
tracciones existentes en la armadura de tracción (dT):

dT = τ⋅ bw ⋅ dx

5 Respecto a Vcd se puede decir que la contribución a cortante es siempre favorable si la
sección crece en la misma dirección que crece el momento.
6 Se ha empleado bw para designar el ancho del alma (del inglés web =alma). El valor bw
puede ser variable a lo largo del canto de la viga..La EHE emplea un valor de bw
denominado b0, definido como ancho del alma, que corresponde al menor valor de bw
en los ¾d contados en vertical a partir de la armadura de tracción.

<!-- p. 226 -->

CORTANTE 226

σ σ+dσ

C
C+dC

τ Fibra neutra
z
V τ V
a b T
T+dT
τ
dx

Figura 7.8. Tensiones de cortante en la fibra neutra

El valor de τbw permanece constante en todos los planos horizontales del tipo
a-b, situados entre la fibra neutra y la armadura de tracción, puesto que no hay esfuerzo
exterior que pueda modificarlo, basta con observar las leyes de tensiones normales de la
figura 7.8. Estableciendo equilibrio de momentos de las acciones exteriores sobre la
rebanada en el punto donde se aplica la resultante de compresiones, tenemos:

dT ⋅ z = V ⋅ dx

Combinando las dos ecuaciones anteriores nos queda que:
V
τ = (7.5)
z ⋅ bw

El valor de la tensión cortante (τ) dado por la ecuación 7.5 es el valor máximo
de la tensión tangencial, en contraposición a la fórmula de Colignon, en la que el valor
de la tensión tangencial es función de la posición de la fibra considerada. Para bw
constante, el valor de τ entre la fibra neutra y la armadura de tracción se mantiene
constante, ya que se ha supuesto que la resistencia a tracción del hormigón es nula. La
expresión anterior ha sido muy cuestionada7 ya que implica que la tensión de cortante se
transmite a través de las grietas de flexión. Sin embargo, tanto la ecuación 7.5 como la
figura 7.8 están hoy día suficientemente contrastadas.

7 Tanto la figura 7.8 como la ecuación 7.5 se han trascrito del libro “Reinforced
Concrete Design” de Sutherland y Clifford de 1926.

<!-- p. 227 -->

HORMIGÓN ESTRUCTURAL 227
Hernández-Gil
7.4. GRIETAS DE CORTANTE

En las vigas de hormigón se presentan dos tipos de grietas de cortante: grietas
de cortante y grietas de flexión-cortante. Las primeras son las producidas en el alma de
las vigas y se deben a la tensión de cortante. Las segundas son las que, iniciadas por la
tensión normal, son continuadas por la tensión cortante. Figura 7.9.

Figura 7.9. Grietas de cortante y grietas de flexión-cortante

Las primeras son típicas de vigas en doble T y se producen porque la tensión
principal de tracción supera la resistencia a tracción del hormigón (fct). Estudiemos el
estado de tensiones de un punto situado en el cdg de la sección transversal de la viga en
doble T de la figura 7.10.

τ σx
A

A τ

2θ
τ θ
A σx fct σ
σx

Direcciones principales

Figura 7.10. Grietas de cortante

Si se estudia el problema aplicando la Teoría de la Elasticidad se puede
establecer que la rotura por cortante se producirá cuando la tensión principal de tracción
sea igual a la resistencia máxima a tracción del hormigón (fct). Es interesante observar
que sólo hasta ese instante se puede aplicar Teoría de Elasticidad puesto a partir de ese
momento el hormigón se agrieta y ya no se comporta como un medio continuo.
Imponiendo que la tensión principal de tracción sea igual a fct, del círculo de Mohr de la
figura 7.10 se deduce que:

<!-- p. 228 -->

CORTANTE 228

σx 2 2 σx ctf = ( ) + τ − (7.6)
2 2

De la ecuación 7.6 se puede deducir el valor de τ que produce fisuración y, por
ende, el valor del esfuerzo cortante.

En el momento en que se produce la fisuración, la inclinación de las grietas de
cortante (θ) se puede deducir del círculo de Mohr (figura 7.10):

2 ⋅τ
tg ( 2θ) =
σx

Figura 7.11. Inclinación de fisuras cerca de los apoyos

Como se puede observar en la figura 7.11, cerca de los apoyos -donde τ es
máximo- las grietas de tracción están más inclinadas, tendiendo a formar 45º en la fibra
neutra de la viga.

Cuando entre dos grietas verticales contiguas, producidas por tensiones
normales, aparece un voladizo empotrado en la zona de compresiones, ver figura 7.12,
aparece otro tipo de grietas. La carga sobre el voladizo es la diferencia de tracciones en
la armadura inferior entre las dos grietas verticales (dT). Esta diferencia de tracciones
produce un momento en el empotramiento que puede generar las tracciones necesarias
para que evolucione este nuevo tipo de grieta.

<!-- p. 229 -->

HORMIGÓN ESTRUCTURAL 229
Hernández-Gil

Zona de compresiones

M
V

T T+dT

Figura 7.12. Grietas de flexión-cortante

7.5. PLANTEAMIENTO EN LA NORMATIVA ACTUAL

El siguiente diagrama de flujo tiene por objeto situar al lector en relación al
tratamiento que la normativa actual hace de la resistencia a cortante de piezas de
hormigón estructural.

Resistencia a cortante

Piezas sin armadura de Piezas con armadura de
cortante cortante

Resistencia Resistencia
en regiones en regiones Contribución Contribución
no fisuradas fisuradas del acero del hormigón

Figura 7.13. Planteamiento general de la resistencia a cortante

La resistencia a cortante en vigas sin armadura de cortante se puede plantear de
dos maneras distintas en función de si aparecen o no zonas fisuradas. En el caso de que
no aparezcan zonas fisuradas se puede emplear la mecánica del continuo para el
hormigón, siendo posible aplicar la teoría de Colignon siempre que las tensiones de
compresión no sean muy elevadas y se pueda considerar un módulo de deformación

<!-- p. 230 -->

CORTANTE 230

longitudinal constante (Ec). En este caso la resistencia a cortante se puede deducir de la
expresión 7.4. El Eurocódigo 2 plantea de la siguiente fórmula para regiones no
fisuradas sin armadura de cortante:

I ·bw 2 VRd , c = (fctd ) + αlσcp fctd (7.7)
S

donde I es el momento de inercia, S es el momento estático respecto al cdg,
fctd=fctk,0.05/γc, αl=lx/lpt2≤1 para tendones de pretensado y αl=1 para otro tipo de
pretensado, σcp es la tensión en el hormigón generada por el esfuerzo de pretensado, lx es
la distancia de la sección considerada al inicio de la longitud de transmisión y lpt2 es el
límite superior de la longitud de transmisión8.

Se puede observar que en el caso de no existir pretensado la expresión 7.7 se
puede deducir directamente a partir de la ecuación 7.49,

En el caso de vigas fisuradas no es aplicable la teoría de elasticidad. Este
problema requiere de un tratamiento experimental que trasciende al planteamiento de
este texto. El EC2 formula que la resistencia a cortante de piezas sin armadura de
cortante en regiones fisuradas es:
VRd , c = (C Rd , c k (100ρl fck ) 1 / 3 + k 1 σcp ) bw d ≥ (v min + k 1 σcp ) bw d (7.8)

donde:

fck en MPa
200
k = 1 + ≤ 0.2 , d en mm
d
Asl lρ = ≤ .002
bw d
Asl es el área de la armadura traccionada, que se extiende a una distancia
≥ (lbd + d) más allá de la sección considerada.
bw es el ancho menor de la sección transversal en la zona de tracción
(mm).
σcp =NEd / Ac \< 0.2 fcd (MPa)
NEd es la fuerza axil sobre la sección transversal debida a carga o al
pretensado (expresado en N y positiva en compresión). Se puede
ignorar la influencia de las deformaciones impuestas sobre NEd.

8 Según el EC2, lpt2=1.2lpt donde lpt es el valor básico de la longitud de transmisión. Ver
Eurocódigo 2 apartado 8.10.2.2.
9 Basta con considerar que en el caso del círculo de Mohr centrado en el origen del
sistema de referencia σ-τ el valor de la tracción máxima es el mismo que el del
cortante máximo (círculo de Mohr de la figura 7.2).

<!-- p. 231 -->

HORMIGÓN ESTRUCTURAL 231
Hernández-Gil
Ac El área de hormigón de la sección transversal.
VRd,c expresado en N.

El EC2 recomienda CRd,c= 0.18 /γc, vmin= 0.035 k3/2 fck 1/2 y k1=0.15.

La norma española EHE establece una serie de limitaciones para la separación
entre estribos, que de cumplirse permite suponer que la fisuración debida a esfuerzo
cortante se controla adecuadamente.

Si el elemento estructural tiene armadura de cortante su resistencia a cortante
viene dada como suma de dos: la resistencia aportada por la armadura de cortante más
la resistencia aportada por el hormigón. La resistencia aportada por la armadura se
deduce mediante la analogía de la celosía, que será tratada en el apartado siguiente.

7.6. COMPORTAMIENTO DEL HORMIGÓN AGRIETADO. ANALOGÍA DE LA
CELOSÍA

Dada la poca resistencia a tracción del hormigón, bajo pequeñas cargas éste
presenta grietas orientadas la dirección perpendicular a la dirección principal de
tracción. Una vez que aparecen estas grietas la resistencia del hormigón en la dirección
principal de tracción es nula (aunque cese la carga) y dejan de ser aplicables los
principios de la Mecánica de los Medios Continuos. Una hipótesis, presentada por Ritter
en 1899, consiste en considerar que la viga se comporta internamente como una celosía
en la que los elementos a compresión (cordón superior y diagonales) están constituidos
por el hormigón presente en la viga, y los elementos a tracción están constituidos por la
armadura longitudinal inferior actuando como tirante y la armadura transversal
actuando como montante. Figura 7.14.a

a b

Figura 7.14. Analogía de la celosía

Los montantes están concentrados en la armadura vertical. Por el contrario, las
diagonales comprimidas de hormigón no están concentradas sino que forman un
continuo a lo largo de toda la masa de hormigón, como se aprecia en la figura 7.14b.

La idea inicial de Ritter fue posteriormente mejorada ya que la aplicación
estricta del método de la celosía conducía a valores de tensiones en las armaduras de
cortante claramente superiores a los obtenidos en los ensayos. Esto es debido a que
existen otros mecanismos, además del mecanismo de celosía, que colaboran en la
resistencia a cortante: en el caso de una viga sin armadura de cortante el modelo de
Ritter supone que la resistencia a cortante es nula y sin embargo la experiencia ha
demostrado que no es así. Por otro lado, si sólo se considera el mecanismo de la celosía

<!-- p. 232 -->

CORTANTE 232

el acero quedará tensado en exceso. Se concluye que el cortante que resiste una viga
según el modelo de la celosía es inferior al que en realidad resiste dicha viga. Otro
inconveniente era que las bielas comprimidas en el modelo de Ritter formaban 45º con
la horizontal y, en general, se comprobó que en hormigón armado este ángulo es
ligeramente menor.

A continuación se plantea la analogía de la celosía con una orientación
genérica de las bielas de hormigón y de la armadura de cortante. Sea θel ángulo que
forman las bielas de hormigón con la horizontal y sea αes el ángulo de la armadura de
cortante con la horizontal. En la figura 7.15 se ha aislado un elemento unidad de
longitud de la viga (Figura 7.15). Sea A-A una sección en la que el valor de la tensión de
cortante venga dado por la ecuación 7.5.

Las líneas discontinuas de la figura 7.15 representan los ccddgg de las bielas de
hormigón y las líneas continuas, que forman un ángulo αcon la horizontal, representan
la armadura de cortante. Estableciendo el equilibrio de fuerzas sobre la cara inferior del
plano A-A de forma vectorial se obtiene el triángulo de fuerzas de la figura 7.15b, donde
C es la resultante de las compresiones de las bielas de hormigón y T es la resultante de
las tracciones de la armadura de cortante. Ambas resultantes (C y T) generan una
resultante horizontal R que origina unas tensiones tangenciales (τ), verificándose que:
R=1·τ·bw. Planteando el equilibrio, según las direcciones horizontal y vertical, en la
figura 7.15 se obtiene:

C ⋅ cosθ + T ⋅ cos α = R = τ⋅ bw (7.9)
C ⋅ senθ = T ⋅ senα

1

a b

V V
A A C T

θ α θ α
R
st

Figura 7.15. Analogía de la Celosía

En las ecuaciones 7.9 se despeja C de la segunda y se sustituye en la primera.
Imponiendo que la tensión del acero sea fyα,d, o sea, llevando el acero hasta el
agotamiento: T= Aα· fyα,d, donde Aα es el área de armadura de cortante por unidad de
longitud. Se obtiene así que:

<!-- p. 233 -->

HORMIGÓN ESTRUCTURAL 233
Hernández-Gil
V
Aα ⋅ f yα,d ⋅ senα⋅ (cot θ+ cot α) = τ⋅ bw = (7.10)
z

Multiplicando por z -brazo mecánico- a ambos lados de la ecuación 7.10 y
teniendo en cuenta la ecuación 7.5, se obtiene la fórmula propuesta por las normas EHE
y EC2:

Aα ⋅ f yα,d ⋅ senα⋅ (cot θ + cot α) ⋅ z = Vsu (7.11) ∑

En el estudio de cortante de piezas de hormigón armado, no sometidas a axiles,
se puede utilizar z= 0.9d.

La interpretación de la ecuación 7.11 es la siguiente: empleando la analogía de
la celosía y obligando a que la armadura de cortante Aα (armadura de cortante por
unidad de longitud) trabaje a una tensión10 fyα,d, el cortante que resiste la viga es Vsu. El
valor Vsu es inferior al cortante que solicita a la viga Vrd, puesto que, como ya se ha
apuntado anteriormente, el modelo de Ritter no tiene en cuenta que la viga tiene una
capacidad resistente asociada a mecanismos diferentes al del modelo de la celosía. El
símbolo Σ contempla la posibilidad de la existencia de distintos grupos de armadura de
cortante, con diferentes orientaciones.

Cambiemos el punto de vista: despejemos T de la segunda de las ecuaciones
7.9 y sustituyamos su valor en la primera. Teniendo en cuenta que: C=σc·bw·senθ,
donde senθes la zona sobre la que actúa la tensión de hormigón cuya proyección es el
lado unidad, tal y como se aprecia en la figura 7.16, se obtiene que:

2 V
σc ⋅ sen θ⋅ (cotθ+ cot α) = τ = (7.12)
bw ⋅ z

De la ecuación anterior se puede determinar el valor de la tensión en las bielas
de hormigón cuando la tensión cortante sobre el plano A-A es τ. Si en la ecuación 7.12
se impone que σc sea la resistencia del hormigón en biela y se aplica un coeficiente de
reducción, para tener en cuenta la existencia de axiles adicionales, se obtiene la fórmula
propuesta por la norma EHE (que coincide con la del EC2):

cot θ+ cot α
(7.13) Vu 1 = K ⋅ f1cd ⋅ b0 ⋅ d ⋅ 2 1 + cot θ

El valor de Vu1 dado por la ecuación 7.13 es el cortante que habría que aplicar a
la sección para agotar el hormigón a compresión. Obviamente Vrd no puede superar este
valor.

10 La norma EHE recomienda que la tensión de la armadura de cortante sea inferior a
400 N/mm2 por razones de deformación. Al emplear mecanismos de bielas y tirantes
para la demostración es conveniente que no se produzcan excesivas deformaciones.

<!-- p. 234 -->

CORTANTE 234

La resistencia del hormigón comprimido en biela es igual a f1cd, teniéndose así
en cuenta que el hormigón puede presentar fisuración oblicua o paralela a las bielas de
compresión, con la consiguiente disminución de la capacidad resistente a compresión.

f1cd = 0.60 fcd para fck ≤ 60MPa
\= (0.90 –fck/200) fcd ≥ 0.5fcd para fck>60 MPa

K es un coeficiente que depende del esfuerzo axil y toma los valores:

K=1.00 para estructuras sin pretensado o sin esfuerzo axil de compresión.
σcd′ K = 1 + para 0 \< σcd′ ≤ 0 . 25fcd
fcd
K = 1 . 25 para 0 . 25fcd \< σcd′ ≤ 0 . 50fcd
⎛ σcd′ ⎞
K = 2 . 5⎜⎜ 1 − ⎟⎟ para 0 . 50 \< σcd′ ≤ fcd ⎝ fcd ⎠

donde σ’cd es la tensión de compresión media (medida positiva) en el hormigón debido
a la fuerza axil de diseño, que se debe de calcular teniendo en cuenta la compresión
absorbida por las armaduras comprimidas. El valor de σ’cd no necesita ser calculado en
una distancia menor de 0.5 d cotθ, medida desde el borde del apoyo.

1
σc

θ
sen θ

θ θ

Figura 7.16. Campo de compresiones

Contribución del hormigón en la resistencia a cortante

Como se ha comentado anteriormente, la ecuación 7.11 corresponde al cortante
resistido por la armadura de cortante empleando la analogía de la celosía. Como ya
habíamos adelantado, se ha comprobado que el cortante resistido por una viga es mayor
que el resistido exclusivamente por el modelo de la celosía. Esto se debe a diversas
causas, entre ellas: al fenómeno arco, al efecto pasador de la armadura longitudinal y al
efecto de rozamiento en la grieta. En la viga de la figura 7.12, sin armadura de cortante,
se forma un arco interno que resiste un cortante adicional al expresado por la ecuación
7.11, aún cuando la viga esté agrietada en la zona de tracción.

<!-- p. 235 -->

HORMIGÓN ESTRUCTURAL 235
Hernández-Gil
Antes de calcular la contribución del hormigón en la resistencia a cortante11
cuando hay armadura de cortante consideremos algunos ejemplos relativos a la
naturaleza del hormigón.

El hormigón es parecido a una piedra y como tal muy deteriorable frente a
deformaciones internas. Una estructura de hormigón que haya sufrido un fuerte
movimiento (sismo, impacto de guerra, atentado, …) quedará, por lo general,
desmoronada mientras que la estructura metálica (parte del edificio como ascensores,
estructuras auxiliares o estructura completa de acero) sólo se deformará. Dicho de otro
modo, el hormigón puede resistir grandes cargas pero en cuanto deforma su resistencia
se ve tremendamente menguada. En ingeniería estructural se define ductilidad de la
estructura o de un elemento estructural (µ) a la relación entre deformación máxima
(δmax) y deformación de cedencia (δy).

La mayoría de las normas no consideran que la contribución del hormigón a
cortante depende de la ductilidad de la estructura. La resistencia a cortante de un
elemento de hormigón estructural varía en función de la ductilidad del elemento
estructural tal y como se indica en la figura 7.17.
Vrd

µ

Figura 7.17. Resistencia a cortante del hormigón en función de la ductilidad (µ)
del elemento estructural

En la figura 7.17 se aprecia que en el primer tramo (baja ductilidad) la
resistencia es mayor puesto que el hormigón no se ha deformado mientras que en el
último tramo la resistencia es atribuible sólo a la ayuda de la armadura de cortante
puesto que el hormigón ha perdido toda su capacidad resistente frente al cortante. El
tramo intermedio corresponde a una degradación progresiva del hormigón.

Los grandes movimientos que puede sufrir una estructura de hormigón son
generalmente el sismo y los impactos. Los impactos tales como aviones, bombas, …
son muy difíciles de cuantificar, sin embargo el riesgo sísmico sí está bastante
determinado. Alguna norma (recomendaciones para pilas de puente de la Federal
Highway Administration, EEUU) vincula la resistencia del hormigón a cortante con el
riesgo sísmico.

La normativa actual, entre ella la EHE, establece que el agotamiento a cortante
puede venir dado por dos causas: agotamiento a compresión de las bielas, si Vrd supera a

11 Existen grandes discrepancias entre los valores de la contribución del hormigón que
proponen las distintas normas (incluso el EC2 considera nula la contribución del
hormigón si existe armadura de cortante).

<!-- p. 236 -->

CORTANTE 236

Vu1 (ecuación 7.13) y agotamiento a tracción en el alma, si Vrd supera a Vu2, siendo Vu2
el cortante resistido por la viga, teniendo en cuenta todos los mecanismos posibles:
modelo de la celosía y otros.

Los valores de Vu2 son distintos para piezas con y sin armadura de cortante, tal
y como se puede ver a continuación:

Para piezas con armadura de cortante, según la EHE tenemos:

V rd ≤ V u 1 ( ecuación 7 . 13 )
V rd ≤ V u 2 V u 2 = V cu + V su
⎡ 0 . 15 1 / 3 ⎤ V cu = ⋅ ξ ⋅ (100 ⋅ ρl f cv ) − 0 . 15 ⋅ αl ⋅ σcd′ b 0 ⋅ d ⋅ β ⎢⎣ γc ⎥⎦
V su = z ⋅ sen α ⋅ (cot α + cot θ) ∑ Aαf y α,d ( ecuación 7 . 11 )
(7.14)

donde:

Aα área por unidad de longitud de cada grupo de armaduras que forman un ángulo
α con la directriz de la pieza.
fyα,d resistencia de cálculo de la armadura Aα, con la limitación de 400 MPa.
z brazo mecánico. En flexión simple, y a falta de datos más precisos, puede
adoptarse como valor aproximado z= 0.9d.
θ ángulo entre las bielas de compresión de hormigón y el eje de la pieza. Se
adopta el mismo valor que en la ecuación 7.13 y debe cumplir 0.5 ≤ cotθ≤ 2.0.
α ángulo de las armaduras con el eje de la pieza.
σ’cd tensión de compresión media en el alma de la sección, medida positiva
200
ξ = 1+ , d en mm.
d
fcv resistencia efectiva del hormigón a cortante en MPa de valor fcv=fck, con fcv no
mayor de 15 MPa en el caso de control reducido del hormigón.
ρl cuantía geométrica de la armadura longitudinal principal de tracción, pasiva y
activa adherente, anclada a una distancia igual o mayor de d a partir de la
sección de estudio.
As + A p ρ= ≤ .0 02
b0 d
αl factor que tiene en cuenta la introducción progresiva de las tensiones
transmitidas por el pretensado al hormigón en el caso de piezas pretensadas con
anclaje por adherencia (EHE).

<!-- p. 237 -->

HORMIGÓN ESTRUCTURAL 237
Hernández-Gil
⎧ 2 ⋅ cot θ− 1
si 0 . 5 ≤ cot θ \< cot θe ⎪ 2 ⋅ cot θe − 1
⎪⎪
β = ⎨
⎪ cot θ− 2
⎪ si cot θe ≤ cot θ \< 2
⎪ ⎩ cot θe − 2
θe ángulo de referencia de inclinación de fisuras. Este valor puede calcularse
mediante dos criterios: en pre-fisuración ó en post-fisuración. El primero es
deducido de la Teoría de Elasticidad y corresponde al ángulo de inclinación de
las fisuras en el alma de la pieza en el instante de fisuración, esto es, cuando la
tensión principal de tracción alcanza fct,m. El segundo criterio está deducido a
partir de teorías de campos de compresiones, desarrolladas en el anejo de este
capítulo.

Criterio de pre-fisuración:

fct2, m − fct , m (σxd + σyd ) + σxd ⋅ σyd ⎧≥ 0 . 5
cotθe = ⎨ (7.15)
fct , m − σyd ⎩≤ 0 . 2

fct,m es la resistencia media a tracción del hormigón
σxd , σyd son las tensiones normales de cálculo, a nivel del centro de gravedad
de la sección, paralelas a la directriz de la pieza y al esfuerzo cortante
Vd, respectivamente. Estas tensiones se obtendrán a partir de las
acciones de cálculo, incluido el pretensado, de acuerdo con la Teoría
de la Elasticidad y en el supuesto de hormigón no fisurado y
considerando positivas las tensiones de tracción12.

Criterio de campo de compresiones:

Adoptando este criterio se puede tomar θe=29+7εx (θe en grados y εx en
‰), donde εx es la deformación longitudinal en el alma, obtenida mediante la
ecuación:

M d + Vrd − 0 . 5N d − Apσp 0
z εx ≈ 1000 ≥ 0 (7.16) 2(E s As + E p Ap )

donde σp0 es la tensión de los tendones de pretensado cuando la deformación
que la envuelve es igual a 0.

12 Tal y como se hizo en la ecuación 7.6.

<!-- p. 238 -->

CORTANTE 238

Para piezas sin armadura de cortante la norma española EHE propone la
siguiente formulación, similar a la propuesta por el EC2 (ecuaciones 7.7 y 7.8):

V rd ≤ V u 1
V rd ≤ V u 2 Para zonas fisuradas :
⎡ 0 . 18 1 / 3 ⎤ V u 2 = ⋅ ξ ⋅ (100 ⋅ ρl f cv ) + 0 . 15 ⋅ αl ⋅ σcd′ ⋅ b 0 ⋅ d ⎢⎣ γc ⎥⎦
⎡ 0 . 075 3 2 1 / 2 ⎤ ≥ ⋅ ξ ⋅ f cv + 0 . 15 ⋅ αl ⋅ σcd′ ⋅ b 0 ⋅ d ⎢⎣ γc ⎥⎦
Para zonas no fisuradas :
I ⋅ b 0 2 V u 2 = (f ct ,d ) + αl ⋅ σ' cd ⋅f ct ,d
S
(7.17)

donde las variables tienen el mismo significado que en las expresiones 7.14.

Ángulo de inclinación de las bielas de hormigón.

El ángulo de inclinación de las bielas no tiene un valor determinado, siendo
válido cualquier valor que verifique: 0.5 ≤ cotθ≤ 2.0. Lo habitual es imponer que θ=
θe, para ello se puede aplicar el criterio de pre-fisuración (que por lo general
proporciona ángulos excesivos) o bien el método basado en teorías de campos de
compresiones.

Los criterios de pre-fisuración o elásticos consisten en aplicar la teoría de la
Elasticidad a la zona del alma, tal y como se hizo en el apartado 7.1 en el que se obtenía
θ=45º cuando sólo existe tensión de cortante. En la Figura 7.10 la inclinación viene
dada por tan(2θ)=2τ/σx, cuando existe tensión cortante y una tensión normal en la
sección transversal paralela al eje de la pieza. En el caso de que el diferencial de área
esté sometido a tensión tangencial τy dos tensiones normales en caras perpendiculares
σxd y σyd, el ángulo de inclinación de las bielas se obtiene de la ecuación 7.15, en la que
se ha supuesto que la tensión en la dirección principal de tracción es fct,m.

Existen otros criterios plásticos para determinar el ángulo de inclinación de las
bielas. Estos criterios se fundamentan en las ecuaciones 7.10 y 7.12, que plasmamos
conjuntamente aquí:

V
Aα ⋅ f yα, d ⋅ senα⋅ (cot θ+ cot α) = τ⋅ bw =
z
(7.18)
2 V
σc ⋅ sen θ⋅ (cot θ+ cot α) = τ =
bw ⋅ z

<!-- p. 239 -->

HORMIGÓN ESTRUCTURAL 239
Hernández-Gil
Como ya vimos, estas ecuaciones se obtuvieron resolviendo el sistema vectorial de la
figura 7.15b, suponiendo que el acero llegaba hasta el agotamiento mientras que al
hormigón se le suponía una tensión σc (i.e. T=Aα·fyα,d y C=σc·bw·senθ ). Uno de los
criterios plásticos consiste en suponer σc =f1cd, σs =fyd y obtener V y θ de estas dos
ecuaciones. Otro criterio posible es suponer conocidos V y σc, imponer que σc=f1cd, y
de la segunda de las ecuaciones anteriores deducir el valor de θ.

Por primera vez el Código modelo CEB-FIP de 1978 (y actualmente algunas
normas, como la EHE) deja al ingeniero calculista el “privilegio” de poder elegir el
ángulo θ (siempre comprendido entre 27º y 65º).

<!-- p. 240 -->

CORTANTE 240

Ejemplo en hormigón armado

Consideremos la sección de una viga de 50×30 cm de hormigón HA30/P/20/IIb con armadura del tipo B-500-S y ejecutada con control intenso. El esfuerzo
cortante efectivo (Vrd) al que está sometida la sección es de 186 kN y el momento de
diseño (Md) es de 200 kN·m. Las comprobaciones que se deben hacer (según EHE) son
las correspondientes a las ecuaciones 7.14. Optamos por armar mediante cercos a 90º:
α=90º. Al tratarse de hormigón armado, el ángulo de inclinación de las bielas de
hormigón es de 45º (θ=45º), tal y como se comentó en el apartado 7.4. Si aplicamos
criterios de las teorías de campos de compresiones, a partir de la ecuación 7.16 se
obtiene como ángulo de referencia un valor de θe=36.6º. Optamos por operar con dos
ángulos (θ=45º y θ=40º ). Los datos correspondientes a θ=40º aparecerán entre
paréntesis.

2∅12

5∅20

Figura 7.18. Sección transversal de una viga

Aplicando la ecuación 7.13 se obtiene que Vu1=801 kN (Vu1=789 kN para
θ=40º). Este valor no supera Vrd y no se produce agotamiento a compresión en el alma.
La contribución del hormigón para resistir el cortante (Vcu), para d=445 mm (ξ=1.67,
ρL=0.0118, σ’cd=0, β=1 para σxd=σyd=0 y θe=θ=45º), es: Vcu=73.15 kN (en el caso de
θe=36.6 y θ=40º: β=0.82 y Vcu=60.00 kN). La parte que tiene que resistir el acero es la
diferencia entre la solicitación y el cortante resistido por el hormigón: Vsu=Vrd -
Vcu=112.85 kN (126.00 kN para θ=40º). Aplicando la ecuación 7.14 para dimensionar la
armadura de cortante por unidad de longitud, se obtiene que se necesitan Aα=0.704
mm2/mm (Aα=0.591 mm2/mm para θ=40º). Si tomamos como unidad de longitud el
valor st (separación de los cercos) el valor obtenido anteriormente será la armadura
necesaria para resistir el cortante cada st.

<!-- p. 241 -->

HORMIGÓN ESTRUCTURAL 241
Hernández-Gil

st

st

Figura 7.19. Separación entre estribos

⎧s t = 2 . 23 ⋅ φ2 para θ = 45 º 2 π⋅ φs t ⋅ Aα = n ramas ⋅ Aredondo = n ramas ⋅ → ⎪⎨
s t = 2 . 65 ⋅ φ para θ = 40 º 4 ⎪⎩ 2

donde nramas es el número de ramas del cerco o estribo y Aφ es el área del redondo del
mismo. En este ejemplo se considera un cerco de dos ramas.

La norma EHE establece algunas limitaciones para la disposición de la
armadura de cortante13:

\- Un valor máximo de st en función de la relación Vu1/Vrd, en nuestro caso
obliga a que st≤267 mm.
\- La separación transversal entre ramas debe cumplir:
st,tran s≤ 0.75d= 334 mm ≤ 500 mm
en nuestro caso se cumple puesto que tendrá un valor ligeramente menor de
200 mm.
\- En el caso de que la armadura superior a compresión esté considerada en el
cálculo se debe de cumplir la limitación que ya se estudió en el tema anterior
(ecuación 6.21) y que obliga a que st ≤180 mm en el caso de que los 2Ø12
hayan sido considerados en el cálculo.
\- Se prolongarán los cercos o estribos calculados en una longitud igual a medio
canto de la pieza.
\- Además la norma española establece un valor mínimo para ΣAα :
Aαf yα, d fct , m 2
Σ ≥ ⋅ b0 ⇒ Aα ≥ 0 . 29 mm mm
senα 7 . 5
condición que se verifica puesto que este valor es menor que el necesario por
resistencia.

Operando con varios diámetros de cercos para los dos valores del ángulo de
bielas de hormigón que se están considerando se obtiene la siguiente tabla:

13 El objeto de esta limitación es la de asegurar un adecuado confinamiento del
hormigón

<!-- p. 242 -->

CORTANTE 242

θ=45º θ=40º
∅ st st
8 143 169
10 223 265
12 321 381

Optamos por disponer cercos de ∅8 cada 16 cm. La tabla inferior resume los
resultados obtenidos:

θ=45º θ=40º
Vu1 (kN) 801 789
Vcu (kN) 73.15 60
Vsu (kN) 112.85 126.00
Aα (mm2/mm) 0.704 0.591
Armadura transversal cØ8 a 14 cm cØ8 a 16 cm

<!-- p. 243 -->

HORMIGÓN ESTRUCTURAL 243
Hernández-Gil
Ejemplo de hormigón pretensado

200 mm
A

150 mm
425 mm
600 mm

A
15 m
50 mm
200 mm

500

Figura 7.20. Viga pretensada de 15 m de luz

Sea la viga pretensada de la figura 7.20, fabricada con hormigón HP-35 y
sometida a una carga ya mayorada de 90 kN/m. La armadura de pretensado está
compuesta por 14 cordones tipo S7 de ∅16 (150 mm2) de acero Y·1860·S7. La fuerza de
pretensado se supone de valor constante igual a 2100 kN.

Los diagramas de momentos flectores y de cortantes debidos a la acción
exterior son los representados en la figura 7.21.:

675 kN

Ley de cortantes

675 kN

Ley de flectores

2531.25 kN·m

Figura 7.21. Leyes de cortantes y flectores sobre la viga. Valores de cálculo.

Lo primero que debemos calcular es el valor del cortante efectivo, que en
nuestro caso dependerá del valor de cálculo Vd y de la fuerza de pretensado,
Vrd=Vd+Vpd, dado que, al ser la sección de canto constante, Vcd es cero. Teniendo en
cuenta la aproximación senα ≈ tanα ≈ α y la ecuación 4.2, tenemos:

675 2e 0 675 2 ⋅ 0 . 475
Vrd = Vd + V pd = x − P ⋅ 2 x = x − 2100 ⋅ 2 x (7.19)
7 . 5 L0 7 . 5 7 . 5

<!-- p. 244 -->

CORTANTE 244

La representación gráfica de la ecuación 7.19 se puede ver en la figura 7.22, en
la que el cortante efectivo se ha dibujado en trazo continuo y el cortante de cálculo en
trazo discontinuo. Sólo se ha representado una parte de la viga: la otra sería igual y de
signo contrario. El origen del eje de las x está situado en el centro de luz de la viga, tal y
como se indica en la figura 7.22.

x

Vcu=233 kN
Vrd=409 kN

Vd=675 kN
Figura 7.22. Cortante efectivo y cortante de cálculo

Ahora hay que decidir el ángulo que las bielas de compresión de hormigón
forman con el eje de la pieza (θ). Por comodidad vamos a emplear el criterio elástico y
además consideramos θ≡θe (ángulo de referencia obtenido aplicando la teoría de la
elasticidad, dado por la ecuación 7.15). Como σyd=0, tenemos:

σxd ⎫ cotθe = 1 − ⎪
f ct ,m ⎪
N d 2100000 2 ⎪
σxd = = − 5 = − 7 . 24 N / mm ⎬ → cotθe = 1 . 8 ⇒ θ = θe = 29 º
Ac 2 . 9 ⋅ 10 ⎪
f ct ,m = 0 . 3 ⋅ 3 f ck2 = 3 . 21N / mm 2 ⎪ ⎪
⎭

El primer paso es comprobar que el esfuerzo cortante efectivo no supera al
esfuerzo cortante de agotamiento por compresión oblicua en el alma (ecuación 7.13). La
armadura de cortante estará compuesta por cercos a 90º, siendo K=1.25 (0.25fcd \< σ’cd
\= 7.24 ≤ 0.5fcd).

35 cot 29 + cot 90
V rd ≤ Vu 1 = 1 . 25 ⋅ 0 . 6 ⋅ ⋅ 150 ⋅ 950 ⋅ 2 = 1057410 N = 1057 kN 1 . 5 1 + cot 29

Como se puede ver en la figura 7.22, este valor no se supera en ningún punto.
Si este valor se superase la única solución sería cambiar la geometría de la sección
transversal de la viga.

<!-- p. 245 -->

HORMIGÓN ESTRUCTURAL 245
Hernández-Gil
El siguiente paso consiste en comprobar que no se produce el agotamiento a
tracción en el alma (Vu2). Una parte de la tracción en el alma es resistida por el
hormigón y otra parte por la armadura de cortante (Vu2=Vcu+Vsu).

⎡ 0 . 15 1 / 3 ⎤
V cu = ⋅ ξ⋅ (100 ⋅ ρl ⋅ 35 ) + 0 . 15 ⋅ αl ⋅ 7 . 24 ⋅ 150 ⋅ 950 ⋅ 1 = 232 . 7 kN ⎢⎣ 1 . 5 ⎥⎦
200 14·150
ξ = 1 + = 1 . 46; ρl = = 0 . 015; αl = 1 . 0
950 150·950

Se ha supuesto que αl es igual a 1.0, lo que equivale a no considerar la
influencia de la zona de transmisión.

El valor de Vcu está representado en la figura 7.22 por una línea punteada. La
armadura de cortante deberá resistir la diferencia entre Vrd y Vcu. En el apoyo
necesitamos:

Vsu = V rd − Vcu = 409 − 232 . 7 = 176 . 3 kN = z ⋅ senα⋅ (cot α+ cot θ) ⋅ Σ Aαf yα,d
Aα = 0 . 286 mm 2 / mm

Aplicando las limitaciones de la norma EHE, la separación entre cercos, st,
debe ser como máximo de 450 mm (Vu1/Vrd=2.6): optamos por 300 mm. Esto supone
que 2·A∅=0.286·300=85.8 mm2, siendo suficiente con colocar un cerco ∅8 cada 30 cm.
La cuantía mínima de armadura de cortante es de Aα=0.145 mm2/mm, que se cumple
con cercos ∅6 cada 30 cm. La forma de proceder es la siguiente: colocamos cercos ∅6
a 30 cm, hasta que Vrd-Vcu sea justo la armadura que resisten los cercos del tipo cercos
∅6 a 30 cm, a partir de ahí colocamos cercos ∅8 cada 30 cm hasta el final – ampliado
en una cantidad h/2 -.

Vsu para φ6 = z ⋅ senα⋅ (cot α+ cot θ) ⋅ Aα ⋅ f yα,d = 58 kN

Sustituyendo en la ecuación 7.19, tenemos:

675 2 ⋅ 0 . 475
Vrd = x − 2100 ⋅ 2 x = 58 + 232 . 7 ⇒ x = 5 . 33 m 7 . 5 7 . 5

Luego la disposición (5.33-1/2=4.83, que se redondea a 4.5 m) es:

<!-- p. 246 -->

CORTANTE 246

4.5 m 4.5 m

c∅6 a 30 c∅8 a 30

Figura 7.23. Distribución de cercos

Si se opta por un criterio plástico, como puede ser imponer que el hormigón
trabaje a fcd y el acero a fyd. Las incógnitas en las ecuaciones 7.18 son Vsu y θ.
Resolviendo el sistema se obtiene: Vsu= 574 kN y θ=11.28º (el valor de θes inferior al
permitido por la norma, por lo que adoptamos el límite inferior θ=27º). Fijando θ=27º
el valor de Vsu es 228.8 kN para cercos ∅8 cada 30 cm.

<!-- p. 247 -->

HORMIGÓN ESTRUCTURAL 247
Hernández-Gil
7.7. INTERACCIÓN FLEXIÓN CORTANTE

Consideremos una viga como la de la figura 7.24. Las ecuaciones de equilibrio,
en una sección transversal cualquiera, se pueden plantear a partir de dos modelos: la
analogía de la celosía (figura 7.24 izq.) o la teoría clásica de la viga (figura 7.24 dcha.).
Según la teoría clásica de la viga, si la sección está sometida a flexión simple se
cumplirá: M= T·z= C·z, según se tomen momentos respecto del punto O ó respecto del
c.d.g. de las compresiones, respectivamente.

s

A C C
Vc
z V z
V
Vs Vs cot α
α O θ α O
T Vs T
z cotθ

Figura 7.24. Modelos según la analogía de la celosía y según la teoría clásica
de la viga.

El planteamiento del equilibrio de la viga a partir de la analogía de la celosía es
un poco más complejo. Damos un corte a la viga por una sección siguiendo la
inclinación de las bielas de hormigón (figura 7.24 izq.). Las ecuaciones de equilibrio
tendrán la forma:

FV → V = Vc + Vs∑
FH → C = T + Vs ⋅ cot α (7.20)∑
z z cot θ
M o → M = C ⋅ z − Vc ⋅ z ⋅ cot θ − Vs ⋅ cot α⋅ − Vs ⋅∑ 2 2

En las ecuaciones anteriores se ha supuesto que el cortante V es resistido por el
hormigón en la zona de compresiones (Vc) y por la armadura de cortante (Vs). Se supone
que la resultante de la armadura de cortante (de valor Vs/senα) está aplicada en la mitad
de la línea AO, siendo su proyección vertical Vs y su proyección horizontal Vs·cotα, tal
y como se indica en el esquema de la figura 7.24. En las ecuaciones anteriores
sustituimos Vc de la primera en la tercera y C de la segunda en la tercera, obteniendo:

⎡ V s V s ⎤ M V s (7.21)M = z ⋅ T − (V − ) cot θ + cot α → T = + V cot θ − (cot θ + cot α)
⎢⎣ 2 2 ⎥⎦ z 2 1444442444443
∆T

<!-- p. 248 -->

CORTANTE 248

Como podemos observar en la ecuación anterior, el valor de T no es M/z como
predecía la teoría clásica de la viga, sino que aparece un ∆T adicional, como
consecuencia de haber considerado un comportamiento diferente al clásico. Este nuevo
comportamiento lo denominamos analogía de la celosía modificada (modificación del
modelo de la figura 7.14a , considerando Vc).

El momento M, para una sección determinada, es el obtenido del diagrama de
momentos flectores para una sección determinada. Con la teoría clásica se cumplía que
T=M/z, sin embargo esto no se cumple con la analogía de la celosía modificada. ¿Qué
momento M’ tendremos que tomar para que introducido en la igualdad T=M’/z se
obtenga el valor de T dado por la ecuación 7.21?, esto es:

M ′ M + ∆ M
T = = (7.22)
z z

o dicho de otro modo: ¿en qué punto de la ley de flectores de la viga el
momento es M’=M+∆M?. Si este punto está relativamente cerca de la sección
considerada se puede realizar la aproximación de la figura 7.25, que consiste en
imponer M+∆M=M’=M+V·sd. Sustituyendo este valor de M’ en la ecuación 7.22 y
teniendo en cuenta la ecuación 7.21 se obtiene que:

M + V ⋅ s d M V s T = = + V cot θ− (cot θ+ cot α) (7.23)
z z 2

sd

V

M’ M ≈ M’ - V·sd

M

Figura 7.25. Decalaje

despejando sd de la expresión anterior – y empleando la notación de la EHE-:

⎛ 1 V su ⎞
(7.24) s d = z ⋅ ⎜⎜ cot θ − (cot θ + cot α) ⎟⎟ ⎝ 2 V rd ⎠

Por tanto, la armadura longitudinal deberá de ser capaz de soportar un
incremento de tracción ∆T, cuyo valor se puede deducir de la ecuación 7.21 ó 7.23:

<!-- p. 249 -->

HORMIGÓN ESTRUCTURAL 249
Hernández-Gil
Vsu ∆ T = Vrd cot θ − (cot θ + cot α) (7.25)
2
En la práctica, este incremento de tracción ∆T se introduce “decalando” la ley
de momentos de cálculo Md una magnitud sd (dada por la expresión 7.24) en el sentido
más desfavorable, lo que equivale a considerar el momento existente a una distancia sd
de la sección considerada, tal y como se indica en la figura 7.26. A sd se le denomina
decalaje de la ley de momentos flectores.

sd
Ley de flectores
clásica Ley de flectores
decalada

sd

Figura 7.26. Ley de momentos flectores y ley de momentos flectores decalada

Para elementos sin armadura de cortante el decalaje debe de ser igual al canto
útil, d (9.2.1.3 (2) del EC2). La norma EHE permite tomar sd=d para θ=45º.

<!-- p. 250 -->

CORTANTE 250

Ejemplo de decalaje

En la figura 7.27 se representa una viga biapoyada, de 10 m de luz y de sección
transversal constante de 30×50 cm. Sobre ella actúa una carga de diseño14 puntual
aplicada en el centro de luz de 100 kN. Ésta es la única carga que se va a considerar. Se
procederá a armar la viga con armadura pasiva. La viga está fabricada con HA-25 y B500-S: fcd=25/1.5=16.7 N/mm2, fyd=500/1.15 =434.8 N/mm2.

100 kN

A

500 mm

10 m A

300 mm

50 kN

Ley de cortantes

50 kN

Leyes de flectores

114 kN·m 250 kN·m
211 kN·m

253 kN·m 0.45 m Ley de flectores decalada
Ley de flectores clásica 1.23 m
3.17 m
1∅20 L=366 cm
2∅20 L=754 cm
2∅20 L=1024 cm

Figura 7.27. Viga biapoyada de 10m de luz

Para armar la viga se emplea cálculo en rotura y se plantean las ecuaciones de
equilibrio a nivel sección para el valor del momento máximo Md=250 kN·m. Se
consideran 50 mm de recubrimiento mecánico, esto es, distancia entre el paramento
inferior y el c.d.g. de la armadura de tracción (i.e.: d=450 mm). Los valores límite son:
xlím=278 mm y Mlím=0.85·fcd·0.8·xlím·300·(450-0.4·xlím)=320.87 kN·m. Como Md\<Mlim no
se necesita armadura de compresión para resistir el momento de diseño de 250 kN·m.
Las ecuaciones de equilibrio de axiles y momentos son:

14 Carga de diseño equivale a decir carga mayorada.

<!-- p. 251 -->

HORMIGÓN ESTRUCTURAL 251
Hernández-Gil
N = 0 . 85 ⋅ f cd ⋅ b ⋅ 0 . 8 ⋅ x − As f yd = 0 N d = ∑
M = 0 . 85 ⋅ f cd ⋅ b ⋅ 0 . 8 ⋅ x ⋅ ( d − 0 . 4 x ) = 250 kN ·m M d = ∑

del sistema anterior se obtiene: x= 198 mm y As=1551 mm2, que se resiste con 5∅20
(1571 mm2). La EHE obliga a continuar hasta los apoyos al menos 1/3 de las armaduras
necesarias, en este caso 2∅20. Optamos por realizar 3 escalones de armado (no tendría
sentido utilizar 5∅20 en toda la viga): uno con 5∅20, otro con 4∅20 y otro con 2∅20.
El siguiente paso es plantearse qué momento resisten dichos armados puesto que a partir
de ahí dejan de ser necesarias las barras, luego a partir de ese punto se añade la longitud
de anclaje. Así pues, en el sistema de ecuaciones anteriores introducimos As (=1571
mm2 para 5∅20, 1257 mm2 para 4∅20 y 628 mm2 para 2∅20) y obtenemos el valor de x
(profundidad de la fibra neutra) y Md. Los valores de Md obtenidos son, 252.8 kN·m para
5∅20, 210.8 kN·m para 4∅20 y 114.1 kN·m para 2∅20, representados en la figura 7.26
en línea discontinua.

Se toma como sd (magnitud del decalaje) la cantidad d. En este caso la ley de
momentos flectores decalada responde a la ecuación siguiente, en la que se ha tomando
como origen de x el punto de centro de luz15:

⎧ M = 250 para 0 \< x \< 0 . 450 m
⎪⎨ 250 M = 250 − ( x − 0 . 45 ) ⋅ para 0 . 450 m \< x \< 5 m
⎪⎩ 5

Introduciendo M=210.8 kN·m obtenemos que x=1.23 m, e igualando M=114.1
kN·m se obtiene x=3.168 m. Luego entre los puntos 0 y x=1.23 son necesarias las 5
barras ∅20. A partir de x=1.23 podemos prescindir de una de las barras. Como hemos
optado por realizar tres escalones (5 barras, 4 barras y 2 barras), el punto a partir del
cual sólo son necesarias dos barras corresponde a x=3.168 m. Cuando las barras dejan
de ser necesarias hay que prolongar una longitud de anclaje, que según la EHE es lb=60
cm –posición I-. Las longitudes finales de las barras se indican en la figura 7.27.

15 En general se utilizan listados de datos (hojas de cálculo o similares) para operar con
las leyes de flectores y sus correspondientes leyes decaladas. En este ejemplo, por
pedagogía, hemos optado por una ley sencilla en la que es fácil operar y seguir el
procedimiento.

<!-- p. 252 -->

CORTANTE 252

7.8. PUNZONAMIENTO

La actuación de una carga concentrada en losas se denomina punzonamiento.
La figura 7.28.izq representa una viga sobre la que actúa una carga concentrada. En este
caso para realizar la comprobación de agotamiento se calcula la resistencia al esfuerzo
cortante en la sección en la que está aplicada la carga puntual. Cuando la carga actúa
sobre una losa (figura 7.28.drcha) el planteamiento es similar pero ahora en lugar del
ancho de la viga bw se considera el perímetro de un cilindro concéntrico al punto de
aplicación de la carga (u1), tal y como se indica en la figura 7.28. Al perímetro de la
sección transversal del cilindro se denomina u1 (perímetro crítico) y a la superficie de
ese cilindro se le denomina área crítica.

P

h

L

bw

P/2
u1

Superficie crítica resistente
P/2 de punzonamiento

Ley de cortantes en viga 2d

Figura 7.28. Superficie crítica de punzonamiento.

La norma EHE define como área crítica a la superficie de un cilindro de altura
la de la placa y de perímetro el correspondiente a una distancia igual a 2d (d = canto
útil) desde el perímetro del área cargada o del soporte. Si la tensión tangencial en la
superficie crítica, τsd (denominada tensión tangencial nominal de cálculo en el perímetro
crítico), es menor que un valor establecido por la normativa, τrd (denominado tensión
máxima resistente en el perímetro crítico), no será necesario disponer armadura de
punzonamiento, puesto que el hormigón absorbe toda la tensión de cortante generada
por la carga puntual.

En el caso que no se cumpla la condición anterior, i.e. τsd > τrd, habrá que
disponer armadura de punzonamiento. En este caso, para dimensionar la armadura se
aplica la teoría de cortante desarrollada en este capítulo aunque es frecuente
redimensionar la sección para que se verifique τsd ≤τrd.

<!-- p. 253 -->

HORMIGÓN ESTRUCTURAL 253
Hernández-Gil

Ejercicios propuestos

\1. Completar el ejemplo de la figura 7.27 calculando la armadura de cortante a 90º y a
60º.
\2. Leer los artículos de punzonamiento de la EHE o del EC2 y descubrir las
similitudes con los artículos de cortante.
\3. Comentar los artículos de la normativa referentes a rasante (o cortante) entre alas y
alma de vigas en T.

<!-- p. 254 -->

HORMIGÓN ESTRUCTURAL 254
Hernández-Gil

Edificio Viapol

Cortesía de ORTIZ Construcciones y Proyectos S.A.

www.ortiz-construcciones.com

<!-- p. 255 -->

HORMIGÓN ESTRUCTURAL 255
Hernández-Gil
ANEJO. Teorías del campo de compresiones
Es muy interesante, desde el punto de vista de la aplicación técnica, que la
normativa relativa al cálculo a cortante esté basada en modelos conceptualmente
sencillos, con sentido físico, en lugar de en complejas ecuaciones empíricas. Si
estos modelos de cálculo a cortante son fáciles de entender, el ingeniero podrá
abordar nuevos problemas de diseño de forma racional. Se puede afirmar que
todavía se está buscando una teoría que explique el comportamiento del hormigón
sometido a esfuerzos cortantes. Dentro de las teorías de cortante existe un grupo,
conocido como “teorías del campo de compresiones”, que resultan muy útiles para
el estudio del hormigón estructural y que serán tratadas en este anejo. El índice de
este anejo es el siguiente:

\- Introducción
\- Campo de deformaciones
\- Ecuaciones de equilibrio
\- Ecuaciones de comportamiento de los materiales

Introducción

El alma agrietada de una viga de hormigón armado transmite el cortante
de forma compleja. Inicialmente aparece una familia de grietas y según se
incrementa la carga aparecen nuevas grietas mientras que las iniciales se propagan y
cambian de inclinación. Debido a que la sección transversal está solicitada por un
momento y un cortante, las deformaciones longitudinales y la inclinación de las
grietas variarán con la profundidad de la viga (figura A7.1)

Barra

Anchura de grietas en mm

Cercos de 10 a 440 mm

al apoyo Sección A Sección B
\= 75 MPa fc
Tensiones de cortante Deformaciones = 0.0026 εc1
en B Longitudinales en B

Figura A7.1. Ejemplo de alma agrietada de una viga con rotura por
cortante.

Los modelos de Ritter (1899) y de Mörsch (1920 y 1922) explicaron el
comportamiento frente a cortante suponiendo la existencia de bielas a compresión
en el hormigón, inclinadas a 45º. En la dirección perpendicular a estas bielas el

<!-- p. 256 -->

HORMIGÓN ESTRUCTURAL 256
Hernández-Gil
hormigón se encuentra agrietado y como consecuencia de ello deja de resistir a
tracción. Según el modelo de bielas a 45º (figura A7.2a), el cortante máximo se
alcanzará cuando los cercos alcancen la tensión de cedencia, lo que corresponde a
una determinada tensión de cortante cuyo valor se puede deducir a partir de la
ecuación de equilibrio de las fuerzas verticales de la figura A7.2a.

h Av ·f y
Av ·f y · = τ·bw ·h ⇒ τ = = ρv ·f y (A7.1)
s bw ·s

donde Av es el área de los cercos, fy la tensión de cedencia, bw el ancho del alma, h el
canto y s la separación entre estribos. El cociente h/s es el número de cercos en la
figura A7.2a.

h h·cotθ

h h

θ

s s

a b

Figura A7.2. a) Estribos a 90º y bielas a 45º b) Estribos a 90º y bielas a θ.

Aplicando el criterio anterior a la viga de la figura A7.1 le corresponde
una tensión máxima de cortante de 0.80 MPa. Sin embargo, la viga resistió 2.38
MPa en el laboratorio y, por tanto, la ecuación anterior -basada en la teoría de
bielas a 45º - resulta excesivamente conservadora.

Una de las razones por las cuales el método de la analogía de la celosía es
muy conservador es porque la inclinación de las bielas medidas respecto a las fibras
longitudinales (θ) suele ser menor de 45º. Para una inclinación genérica θ del ángulo
de las bielas (figura A7.2b) la ecuación anterior tiene la forma:

τ = ρv ·f y ·cot θ (A7.2)

Teniendo en cuenta la ecuación anterior, para que la resistencia a cortante
de la viga de la figura A7.1 fuese igual a 2.38 MPa las grietas deberían estar

<!-- p. 257 -->

HORMIGÓN ESTRUCTURAL 257
Hernández-Gil
inclinadas 18.6º. Como se puede apreciar en la figura A7.1, la mayor parte de las
grietas tienen inclinaciones mayores a ésta.

Campo de deformaciones

Antes de formular una ecuación basada en los mecanismos de bielas para
determinar la resistencia a cortante de una viga o para diseñar los estribos, es
necesario conocer el ángulo de inclinación de las bielas, θ. Con relación a este
problema, Mörsch en 1922 comentó “es absolutamente imposible determinar
matemáticamente la pendiente de las grietas secundarias con las que poder diseñar
los estribos”. Sin embargo, un problema parecido se resolvió con éxito en perfiles
metálicos de alma débil, mediante las teorías denominadas de los campos
diagonales de tracción. Un ejemplo de esto lo podemos ver en la figura A7.3, que
muestra el alma de una viga metálica, que ha generado un campo diagonal de
tracciones. Este campo está apoyado principalmente en la parte superior e inferior
–alas de la viga-, puesto que la parte lateral no ofrece resistencia suficiente y ha
cedido.

Figura A7.3. Campo diagonal de tracciones apoyado en la parte superior e
inferior.

En el campo diagonal de tracciones un mismo material –el acero- se
comporta de manera muy diferente según esté solicitado por compresiones o por
tracciones. Algo parecido se iba a aplicar en el estudio del hormigón estructural.

Basándose en el planteamiento anterior y trasladándolo al estudio del
hormigón se han formulado aproximaciones conocidas como teorías del campo de
compresiones. Éstas determinan el ángulo de inclinación de las bielas (θ)
considerando las deformaciones de la armadura transversal, de la armadura
longitudinal y del hormigón. A partir de las teorías del campo de compresiones se
puede estudiar la respuesta carga-deformación de una sección sometida a cortante,
para ello se plantean las condiciones de equilibrio, las condiciones de
compatibilidad y las relaciones tensión-deformación tanto para la armadura como
para el hormigón agrietado.

<!-- p. 258 -->

HORMIGÓN ESTRUCTURAL 258
Hernández-Gil
Las teorías de los campos de deformaciones están formuladas en la
mecánica del continuo, considerando deformaciones medias1, tal y como se indica
en la figura A7.4a. Si la armadura longitudinal sufre un alargamiento medio εx , la
armadura transversal un alargamiento medio εt y el hormigón en la dirección
principal de compresión un acortamiento medio ε2 se puede deducir la dirección
principal de deformación de compresión, a partir del círculo de deformaciones2
(figura A7.4b).

2 εx − ε2 tan θ = (A7.3)
εt − ε2

y
0.5 Distorsión angular
\-ε2 ε1
εt ε1
εt y
εx 0.5 γm
x 2 1

ε2 2θ Deformación normal
θ x
εx

a) Deformaciones medias b) Círculo de deformaciones medias
en un elemento agrietado

Figura A7.4. Condiciones de compatibilidad para el alma agrietada.

A partir del círculo representado en la figura A7.4b se puede deducir la
deformación media principal de tracción (ε1) en función de otras deformaciones,
mediante cualquiera de estas igualdades:

ε1 = εx + εt − ε2 = εx + (εx − ε2 ) cot 2 θ (A7.4)

Si hay armadura activa, se cumplirá además que εp=εx+∆εp, donde εp es la
deformación unitaria de la armadura activa y ∆εp la deformación impuesta por el
sistema de pretensado.

1 Comunes a acero y a hormigón.
2 Al hacerse el planteamiento en deformaciones medias este razonamiento es
válido aunque el hormigón esté agrietado,

<!-- p. 259 -->

HORMIGÓN ESTRUCTURAL 259
Hernández-Gil

Ecuaciones de equilibrio

La primera de las denominadas teorías de campos de compresiones se
conoce como Teoría del Campo de Compresiones (en adelante TCC). La TCC fue
posteriormente modificada y surgió la que se conoce como Teoría Modificada del
Campo de Compresiones (en adelante TMCC). La diferencia entra ambas se puede
ver en la figura A7.5.

La figura A7.5 muestra el alma de una viga de hormigón armado antes y
después de la fisuración. Antes de producirse la fisuración el cortante es resistido
por tracciones y compresiones diagonales en el hormigón, donde σ1 y σ2 son las
tensiones principales de tracción y compresión, respectivamente. Una vez que se
produce la fisuración el hormigón pierde su capacidad resistente a tracción y la
TCC considera que, a partir de ese instante, σ1=0. Sin embargo, debido al
fenómeno de la tensorrigidez, el hormigón sí contribuye -en lo que a la
deformación del elemento se refiere- después de fisurado y, en base a ésto, la
TMCC considera una resistencia media del hormigón a tracción.

σ2 σ2 σ2

σ1 σ1

a) Antes de fisurar b) Teoría del Campo de c) Teoría Modificada del
Compresiones, σ1=0 Campo de Compresiones, σ1≠0

Figura A7.5. Diferencia entre la TCC y la TMCC

El planteamiento de las ecuaciones de equilibrio es distinto según se
emplee la TCC o la TMCC. Las ecuaciones de equilibrio se plantean para una viga
simétrica de hormigón con armadura pasiva y activa, supuesto que la tensión de
cortante viene dada por la siguiente expresión (ecuación 7.5, §7.3):

V
τ = (A7.5)
bw ⋅ z

Aplicando la TCC e imponiendo el equilibrio de fuerzas verticales se
obtiene:

V 1 V
σ2 = = (tanθ+ cot θ) (A7.6)
bw ⋅ z senθcosθ bw ⋅ z

La componente longitudinal de la fuerza de compresión vale:

<!-- p. 260 -->

HORMIGÓN ESTRUCTURAL 260
Hernández-Gil
2 V
σ2 z b w cos θ = (A7.7.a)
tanθ

Esta fuerza debe de ser contrarrestada por una fuerza axil de tracción, Nv ,
en la armadura longitudinal:
V
Nv = Asxσsx + Apσp = (A7.7.b)
tanθ

Planteando equilibrio de fuerzas verticales en el detalle de la figura A7.6 se
obtiene que la fuerza de compresión diagonal del hormigón (σ2 s senθ bw) introduce
una componente vertical (σ2 s sen2θ bw) que debe de ser contrarrestada por la
armadura transversal Asv σsv :

Avsσvs = σ2 sen 2θbw s (A7.8)

Las tres ecuaciones A7.6, A7.7.b y A7.8 constituyen las ecuaciones de
equilibrio para la Teoría del Campo de Compresiones.

z cos θ

0.5 Nv
σ2 bw
z
V
θ
0.5 Nv

s

s sen θ
σ2

s
Detalle

Figura A7.6. Estudio del equilibrio para la Teoría del Campo de
Compresiones (TCC).

La figura A7.7 representa el equilibrio para la Teoría Modificada del
Campo de Compresiones. Como se aprecia en la figura A7.7, el valor de la tensión
del hormigón perpendicular a las grietas σ1 es tenido en cuenta (este valor era cero
en la TCC, como ya vimos). De hecho, las ecuaciones de equilibrio en el caso de la
TMCC difieren de las ecuaciones de equilibrio de la TCC en el término σ1.

<!-- p. 261 -->

HORMIGÓN ESTRUCTURAL 261
Hernández-Gil

z cos θ

σ1 0.5 Nv σ2 bw
z
V
θ
0.5 Nv Tensiones de
cortante
s σcx

σ1 τ Tensiones
σ2 2θ θ normales

s σcy
Detalle
σ2 σ1
Círculo de tensiones medias del hormigón

Figura A7.7. Estudio del equilibrio para la Teoría Modificada del Campo
de Compresiones (TMCC).

Analicemos la viga en doble T simétrica de la figura A7.7 sometida a
cortante. Sea Apx el área total de la armadura longitudinal activa y Asx el área total
de la armadura longitudinal pasiva. El cortante en la sección produce compresiones
diagonales, σ2, y tracciones diagonales, σ1. Cuando el hormigón se agrieta las
tensiones de tracción varían desde 0 en la grieta hasta valores máximos en la zona
entre grietas. Para formular el equilibrio, y haciendo uso de la Mecánica del
Continuo, es necesario operar con una tensión de tracción media, σ1. En este caso,
el círculo de Mohr de tensiones medias es el representado en la figura A7.7. Del
círculo de tensiones medias en el hormigón se puede deducir la primera de las
ecuaciones A7.9.
V
σ2 = (tanθ + cot θ) − σ1
zbw
Asvσsv = (σ2 sen 2θ − σ1 cos 2 θ)bw s (A7.9)
2 2 V
Asxσsx + Apσp = (σ2 cos θ − σ1sen θ)bw z = − σ1bw z
tanθ

De la descompensación de la proyección vertical de resultantes de las
tensiones principales σ2 y σ1 se deduce la fuerza absorbida por la armadura
transversal, que corresponde a la segunda de las ecuaciones A7.9, en la que σsv es la
tensión media de la armadura transversal.

<!-- p. 262 -->

HORMIGÓN ESTRUCTURAL 262
Hernández-Gil

Introduciendo el valor de σ2 de la primera de las ecuaciones A7.9 en la
segunda se obtiene el valor del cortante como suma de dos componentes: la
absorbida por el hormigón a tracción más la absorbida por los estribos
respectivamente:

Asvσsv V = σ1bw z cot θ+ z cot θ (A7.10)
s

Si el esfuerzo axil que solicita la sección es nulo, las tensiones diagonales
en el hormigón generan una componente longitudinal no compensada que, como
ya vimos en el apartado §7.7, es la responsable del “decalaje de la ley de flectores”.
En el caso de elementos con armadura activa esta componente da lugar a la tercera
de las ecuaciones A7.9, en la que σsx y σp son las tensiones medias en la armadura
longitudinal pasiva y activa respectivamente.

Ecuaciones de comportamiento de los materiales

Las tensiones y las deformaciones están relacionadas mediante las
ecuaciones de comportamiento del material. Las relaciones tensión-deformación se
aplican al acero en las direcciones de la armadura y al hormigón en las direcciones
principales. Las deformaciones consideradas son deformaciones medias, ya que
están medidas en distancias superiores a la separación entre grietas.

Ecuaciones de comportamiento de los materiales: hormigón

Las deformaciones y las tensiones están relacionadas mediante los
modelos tensión-deformación de los materiales. Para el hormigón a compresión
los modelos habituales son los presentados en el capítulo 3, figura 3.7 (ver figura
3.6). Como ya vimos, el modelo representado en la figura 3.7 reproduce el
comportamiento del hormigón en el ensayo a compresión en probeta cilíndrica. El
caso que nos ocupa es bien distinto dado que ahora el hormigón está solicitado a
compresión en una dirección principal al mismo tiempo que traccionado según la
otra dirección principal y además está agrietado. Como ecuación de
comportamiento del hormigón en este caso Vecchio y Collins3 (1982) proponen:

3 Existen en la literatura numerosos modelos de comportamiento para el hormigón
agrietado, aquí se ha optado por uno de ellos.

<!-- p. 263 -->

HORMIGÓN ESTRUCTURAL 263
Hernández-Gil
⎡ 2 ⎤ ⎛ ε2 ⎞ ⎛ εc ⎞
σ2 = f2,max ⎢ 2⎜⎜ ⎟⎟ − ⎜⎜ ⎟⎟ ⎥ ⎢ ⎝ εc 1 ⎠ ⎝ εc 1 ⎠ ⎥ ⎣ ⎦ (A7.11)
fc donde f2,max = ≤ fc
0 . 8 + 170ε1

La representación gráfica de esta expresión se puede ver en la figura A7.8.

σ2
σ2
f2max/fc ε2
fc 1
σ2

f2max
ε2 ε1

ε1 ε2 0
εc1 0 10-2
a) Tensión-deformación del hormigón agrietado b) Tensión máxima del hormigón agrietado

Figura A7.8. Relaciones tensión-deformación para el hormigón agrietado
en compresión.

La TMCC considera la relación tensión-deformación del hormigón a
tracción que se estudió en el apartado §6.3 y que se transcribe nuevamente aquí4:

4 Esta ecuación puede verse en Collins y Mitchell (1991). Otros autores proponen
ecuaciones alternativas existiendo entre ellas diferencias sustanciales.
Recientemente Bentz (2005) propone una nueva ecuación para el comportamiento
a tracción del hormigón en función del área de hormigón que afecta a la barra (7.5
diámetros en torno a la barra):

f ctm Acf1 = donde M = todo en mm (A7.12bis)
d bπ 1 + 3 . 6Mε1 ∑

donde db es el diámetro de la barra y Ac es el área de hormigón perpendicular a la
barra que la afecta. Esta nueva ecuación se ajusta mejor a los datos experimentales
existentes.

<!-- p. 264 -->

HORMIGÓN ESTRUCTURAL 264
Hernández-Gil
σ1 = E cε1 para ε1 ≤ εctm
(A7.12)
α1α2 fctm σ1 = para ε1 > εctm
1 + 500ε1

donde εctm es la deformación unitaria correspondiente a fctm. El resto de parámetros
ya se vieron en el apartado 6.3. La representación gráfica de la ecuación anterior se
muestra en la figura A7.9.

σ1
fctm σ2

ε1

σ1
0 ε1
0 εctm

Figura A7.9. Relación tensión-deformación media para el hormigón en
tracción.

Ecuaciones de comportamiento de los materiales: acero

Ambas teorías, la TCC y la TMCC (Collins y Mitchell 1991) adoptan
relaciones bilineales para el acero (figura A7.10 a y b, línea continua)

σsx σsv

fy fy

Es Es
1 1
εx εv

a) Armadura longitudinal b) Armadura transversal

Figura A7.10. Relaciones tensión-deformación del acero

<!-- p. 265 -->

HORMIGÓN ESTRUCTURAL 265
Hernández-Gil
Otras teorías proponen relaciones bilineales con valores inferiores a los
anteriores en base a que el comportamiento medio de las barras embebidas debe de
ser menor que el de la barra aislada (Belardi y Hsu 1994). Estas relaciones se han
representado cualitativamente con línea discontinua en la figura A7.10.

Otras teorías (Hdz-Montes y Gil-Martín 2005) proponen que los modelos
de acero y de tensorrigidez de hormigón deben de estar relacionados sin ninguna
formulación adicional. Siempre que el acero no entre en cedencia en la grieta (i.e.
σs≤fy) el módulo de deformación del acero será Es. Cuando, en una grieta, el acero
alcance su límite elástico el módulo de deformación medio del acero se verá
alterado, ver figura A7.11. Si se establece el equilibrio entre la sección de la grieta
(cuando se ha producido cedencia en el acero) y una sección que represente el
estado medio de tensiones (figura A7.11) se verificará que:

σs,med fy

σct,med

Sección Sección en
genérica grieta

Figura A7.11. Barra sometida a tracción. El acero ha alcanzado la tensión
de cedencia fy.

As f y = Asσs , med + Ac , efσct , med (A7.13)
{ 144424443
grieta sec ción media

de donde se puede deducir el valor medio de la tensión en la armadura:

Ac , ef α1α2 fctm σs , med = f y − si εctm ≥ εmax, l
As 1 + 500ε1 (A7.14)
σs , med = E sεct si εctm \< εmax, l

El valor de εmax,l corresponde a la deformación de la primera cedencia en la grieta
y se calcula a partir de la ecuación A7.13.

<!-- p. 266 -->

HORMIGÓN ESTRUCTURAL 266
Hernández-Gil
α1α2 fctm As εy E s = As εmax, l E s + Ac , ef
1 + 500 εmax, l

Ejemplo

Si estudiamos el ejemplo de la figura A7.1 aplicando la TCC se obtiene un
sistema de 8 ecuaciones no lineales: 3 ecuaciones de equilibrio (A7.6, A7.7.b y
A7.8), 2 ecuaciones de compatibilidad (A7.3 y la primera igual de A7.4) y 3
ecuaciones de comportamiento de los materiales: ecuación A7.11 para el hormigón
a compresión y las relaciones bilineales para la armadura con Es=200000 N/mm2.
Las incógnitas son: θ, εx, ε1, εv, ε2, σ2, σsx, y σsv. Se puede comprobar que la tensión de
cedencia en la armadura transversal (522 MPa) se alcanza para V=458 kN (θ=25.5º
y τ=1.69MPa). Para posteriores incrementos de V la tensión en los cercos
permanece constante y el agotamiento del hormigón a compresión se produce para
un valor del cortante V=736 kN (θ=16.5º y τ=2.71MPa).

Estudio a nivel grieta en la TMCC.

Los resultados obtenidos a partir de la TCC están más cercanos al
comportamiento de agotamiento en la grieta que los de la TMCC. Esto es debido a
que la TCC considera que la resistencia del hormigón a tracción es nula, lo que es
cierto a nivel grieta.

Puesto que el fallo de un elemento de hormigón armado no está
gobernado por las tensiones medias sino por las tensiones locales a nivel de las
grietas, es preciso adaptar la TMCC para el estudio del agotamiento. Belardi y Hsu
(1994) demostraron que las teorías que utilizan modelos de acero embebido
(Figura A7.8 línea discontinua o el método de la ecuación A7.14) no necesitan
comprobación del estado de tensiones en grieta.

Por ahora sólo se han tratado tensiones y deformaciones medias, teniendo
en cuenta que éstas varían de un punto a otro, especialmente entre las grietas y las
zonas entre grietas (ver figura A7.12). Obviamente, en grieta la tracción en el
hormigón es nula mientras que la tensión en la armadura es máxima.

Para valores pequeños del esfuerzo cortante, la tracción se trasmite a
través de las grietas mediante aumentos locales en la tensión de las barras de acero.
A ciertos niveles de cortante la tensión de la armadura del alma puede alcanzar el
valor de fluencia, figura A7.12c. Si el esfuerzo cortante aumenta, para transmitir
tracciones a través de la grieta será necesaria la aparición de tensiones de cortante
locales, τci, que actúan tal y como indica la figura A7.12b.

<!-- p. 267 -->

HORMIGÓN ESTRUCTURAL 267
Hernández-Gil
La capacidad de la interfase de la grieta para transmitir estas tensiones
tangenciales dependerá del ancho de la grieta (w) y del tamaño máximo de árido (a).
El valor máximo de τci viene dado por la expresión (Bhide y Collins, 1989):

0 . 18 fc
τci ≤ (MPa, mm) (A7.15)
0 . 3 + 24w a + 16

En la expresión anterior no se tienen en cuenta los efectos favorables
producidos por compresiones locales en la interfase de la grieta.

1

2

τci

τci
θ

1
a) Viga sometida a cortante b) Detalle de la grieta
2 1 2

τci σ1
Asvfvy Asvσsv

1 2

c) Tensiones locales en la grieta d) Tensiones medias calculadas

Figura A7.12. Fuerzas a través de la grieta.

Las dos familias de tensiones de las figuras A7.12c y A7.12d deben de ser
estáticamente equivalentes. Por eso ambas componentes verticales han de ser
iguales:
⎛ z ⎞ bw z ⎛ z ⎞ Asvσsv ⎜ ⎟ + σ1 = Asv fvy ⎜ ⎟ + τci bw z (A7.16)
⎝ s tanθ⎠ tanθ ⎝ s tanθ⎠

de donde se puede deducir el valor de la tracción transmitida por el hormigón
entre grietas, σ1 :

<!-- p. 268 -->

HORMIGÓN ESTRUCTURAL 268
Hernández-Gil

Asv σ1 = τci tanθ+ (fvy − σsv ) (A7.17)
sbw

El ancho de fisura, w, se puede obtener a partir de la siguiente ecuación:

w = ε1 ⋅ s mθ
1
siendo : s mθ = (A7.18) senθ cosθ
\+
s mx s mv

En la expresión anterior smθ es la separación media de las grietas
diagonales, smx y smv son las separaciones entre grietas en las direcciones de la
armadura longitudinal y transversal respectivamente, ε1 es la deformación
longitudinal unitaria en la dirección principal de tracción y θ el ángulo de
inclinación de las bielas, tal y como se indica en la figura A.7.13.

El código modelo CEB-FIP propone una formulación para estimar las
separaciones entre grietas. Esta formulación fue deducida para el ancho de fisura
en superficie. Para adaptar esta fórmula, en lugar de c (recubrimiento) se emplean
cx y cv, que son las distancias del cdg de la sección bruta a la armadura longitudinal y
vertical, respectivamente. Ver figura A.7.14.

⎛ s x ⎞ d bx s mx = 2⎜ c x + ⎟ + k1k 2
⎝ 10 ⎠ ρx
(A7.19)
⎛ s ⎞ d bv
s mv = 2⎜⎜ c v + ⎟⎟ + k1k 2 ⎝ 10 ⎠ ρv

donde:

ρv=Asv/(bws)
ρx=(Asx+Apx)/Ac,
k2=0.25 y
⎧ = 0 . 4 para barras corrugadas
k1 ⎨
⎩ = 0 . 8 para barras lisas o tendones

Otro límite del valor de la resistencia a cortante viene dado por la cedencia
de la armadura longitudinal. Las componentes horizontales que aparecen en los
modelos de las figuras A7.12c y A7.12d deben verificar la siguiente inecuación:

<!-- p. 269 -->

HORMIGÓN ESTRUCTURAL 269
Hernández-Gil
⎡ Asv ⎤ 2Asx ·f y + Ap ·f p ≥ Asx ·σsx + Apx ·σp + σ1·bw ·z + σ1 − (fvy − σsv ) bw ·z·cot θ ⎢⎣ bw ·s ⎥⎦
(A7.20)

donde fy es el límite elástico de la armadura longitudinal pasiva y fp el límite elástico
del acero de pretensado, que se alcanzan a nivel grieta.

smθ

bw

θ

a) Sección Transversal b) Grietas inclinadas θ, y separadas smθ

smv

smx

c) Grietas verticales, separadas smx d) Grietas horizontales, separadas smv

Figura A7.13. Separación entre grietas.

cv

s

cx
sx

Figura A7.14. Parámetros sx, s, cx y cv.

<!-- p. 270 -->

HORMIGÓN ESTRUCTURAL 270
Hernández-Gil
Ejemplo

Un ejemplo clásico en el estudio del cortante es un ensayo realizado por Abersman
y Conte (Collins y Mitchell 1991). La figura A7.15 resume la geometría del ensayo y
la sección transversal es la representada en la Figura A7.16.

Geometría de la viga

Zona de ensayo
P 2 P A

1219 mm 1829 mm 1829 mm

Diagrama de cortantes

P 2P/3

4P/3
Diagrama de flectores

\- 1.22 P kN·m

1.22 P kN·m
Figura A7.15. Geometría del ensayo.

<!-- p. 271 -->

HORMIGÓN ESTRUCTURAL 271
Hernández-Gil

51 mm 610 mm Características de la sección transversal
Recubrimiento lateral = 13 mm
Recubrimiento superior e inferior= 25 mm
fc=38.6 MPa
Hueco fctm=2 MPa
εc1=0.003
152×406 mm Cercos de Ø9.5 mm cada 152 mm
fy=367 MPa
Barras longitudinales pasivas 6 de Ø9.5 mm
fy=367 MPa
76.5 mm Barras longitudinales activas
Alambres 6×4 de Ø7 mm
fpu=1680 MPa
fpy=1450 MPa
∆εp=0.0054
Ep=197000 MPa
51 mm

305 mm

Figura A7.15. Sección transversal A del ejemplo

El problema se ha resuelto para la sección transversal A aplicando la
TMCC. Las ecuaciones implicadas son las siguientes:
\- 3 ecuaciones de equilibrio, A7.9.
\- 2 ecuaciones de compatibilidad, A7.3 y A7.4.
\- ecuación de compatibilidad en la deformación del pretensado
(εp=εx+∆εp)
\- comportamiento del hormigón a tracción (σ1), ecuación A7.12.
\- comportamiento del hormigón a compresión (σ2), ecuación A7.11.
\- 2 relaciones tensión-deformación del acero, una para la armadura
longitudinal y otra para la armadura transversal, figura A7.10.
\- relación tensión-deformación del acero de pretensado, que se ha
tomado bilineal.

Además se ha efectuado la comprobación en grieta (Ecuaciones A7.15 a
A7.20). Estas ecuaciones sólo modifican el comportamiento a tracción del
hormigón, introduciendo tantas incógnitas nuevas como ecuaciones.

En el sistema de 11 ecuaciones no lineales anterior hay 11 incógnitas: θ, εx,
εp, V, εv, ε2, σ1, σ2, σsx, σsv y σp si se resuelve para un determinado valor de ε1. Para la
resolución de este sistema se ha empleado el programa Mathematica®.

Se han considerado dos alteraciones a la TMCC. La primera ha consistido
en adoptar la expresión A7.12bis para el comportamiento del hormigón a tracción
(tensorrigidez). Los resultados así obtenidos se han denominado TCC2.

<!-- p. 272 -->

HORMIGÓN ESTRUCTURAL 272
Hernández-Gil

La segunda modificación consiste en, además de la ecuación A7.12bis,
considerar como ecuación del acero a tracción la expresión A7.14. Esta nueva
teoría la hemos denominado TCC3. Hay que hacer notar que en la expresión
A7.12bis el área de hormigón Ac es el área rectangular en torno a la barra a una
distancia no mayor de 7.5Ø –siendo Ø el diámetro de la barra- (figura A7.16), área
generalmente adoptada en fenómenos de tracción. Para aplicar la ecuación A7.14
se ha considerado un Ac,ef de 0.3 y 0.5 de Ac. Los resultados obtenidos se han
representado en la forma Cortante-deformación vertical en la figura A7.17.

7.5Φ 7.5Φ

≤ 7.5Φ

Ac

Figura A7.16. Área Ac.

500

450

400

(KN) 350 Zona de ensayo
V

300

250

200
0 0,001 0,002 0,003 0,004 0,005 0,006 0,007

epsilon v

TMCC TCC2 Resultado experimental
Resultado experimental TCC3-0.3 TCC3-0.5

Figura A7.17. Resultados comparativos.

<!-- p. 273 -->

HORMIGÓN ESTRUCTURAL 273
Hernández-Gil

Ejercicios propuestos

\1. Resolver el ejercicio de la figura A7.1 aplicando la TMCC, la TCC2 y la TCC3.

<!-- p. 274 -->

HORMIGÓN ESTRUCTURAL 274
Hernández-Gil
Referencias:

ASCE-ACI Committe 445 on Shear and Torsion. "Recent Approaches to Shear Design
of Structural Concrete". Journal of Structural Engineering. December 1998. Páginas
1375- 1417.

Belardi, A., y Hsu, T.T.C. (1994). "Constitutive laws of concrete in tension and
reinforcing bars stiffened by concrete". ACI Struct. J., 91(4), 465-474.

Bentz E. (2005). “Explaining the Riddle of Tension Stiffening Models for Shear Panel
Experiments”. ASCE Journal of Structural Engineering. September 2005. Vol.131. Nº9,
1422-1425.

Building Code Requirements for Structural Concrete (ACI 318-05) and Comentary
(ACI 318R-02). American Concrete Institute. Michigan. (Enero 2005).

Collins, M.P. (1978). "Toward a rational theory for RC members in shear". J. Structural
Division., ASCE 104(4), 649-666.

Collins M.P., Mitchell D., (1991). Prestressed Concrete Structures. Prentice Hall,
Nueva Jersey.

Hernández Montes, E., y Gil Martín, L.M. (2005). “Hacia una Teoría Unificada del
Campo de Compresiones”. Hormigón y Acero. Nº 236. Segundo trimestre 2005. Pág.
109-118.

Kupfer, H., Hilsdorf, H.K. and Rusch, H. (1969). “Behavior of concrete under biaxial
stresses”. J. ACI. 66(8), 656-666.

Sutherland H. y Clifford W.W. (1926). Introduction to Reinforced Concrete Design.
Editorial John Wiley & Sons Inc. Nueva York.

Vecchio, F., y Collins, M.P. "The response of reinforced concrete to in-plane shear and
normal stresses". Publication No. 82-03, Department of Civil Engineering, Universidad
de Toronto, Mazo 1982, 332 pág.

Vecchio, F.J., y Collins, M.P. (1986). "The modified compression field theory for
reinforced concrete elements subjected to shear". J. Am. Concrete Inst., 83(2), 219-231.

<!-- p. 275 -->

HORMIGÓN ESTRUCTURAL 275
Hernández-Gil

CAPÍTULO VIII

TORSIÓN

Puente del Dragón sobre el Zacatín. Alcalá de Guadaira. Sevilla.
Cortesía de Brues y Fernández Construcciones S.A. www.bruesa.com

8.1. INTRODUCCIÓN

El momento torsor o simplemente torsor (T) es un momento cuyo eje de
aplicación es paralelo a la directriz de la pieza, ver figura 8.2.

La torsión se presenta en elementos estructurales tales como: puentes curvos,
vigas embrochaladas, vigas de puente cargadas excéntricamente, etc. El momento torsor
puede ser una solicitación principal o una solicitación secundaria. Si la solicitación es
principal (figura 8.1.a) la pieza debe de resistir todo el torsor, dado que en caso
contrario se originaría la ruina de la pieza. Esto se produce en estructuras isostáticas
donde si no se resiste el torsor la estructura se convierte en mecanismo y se produce su
ruina. En la figura 8.1.a el voladizo está resistido isostáticamente por la viga principal,
la cual debe de resistir todo el momento torsor inducido por el voladizo.

<!-- p. 276 -->

TORSIÓN 276

Se habla de solicitación secundaria (figura 8.1.b), cuando el momento torsor no
tiene por qué ser resistido en su totalidad, dándose dos posibilidades:

\- si la viga principal de la figura 8.1.b no tiene capacidad para resistir el
momento torsor, ésta gira en torno a su eje, y las vigas secundarias se
comportan como biapoyadas, con una ley de flectores como la representada en
la figura 8.1.c.
\- si la viga principal presenta resistencia frente al torsor, a todo o a una parte de
éste, las vigas secundarias estarán sometidas a un momento flector en el apoyo,
con una ley de flectores como la de la figura 8.1.d.

Viga principal

Vigas secundarias
Viga principal a b

Vigas secundarias

c

d

Figura 8.1. Torsor como solicitación principal y como solicitación secundaria

8.2. TORSIÓN EN PRE-FISURACIÓN

La torsión en elementos de hormigón en pre-fisuración se puede estudiar tal y
como se explica en cualquier libro de Resistencia de Materiales: a partir de las teorías
de Saint-Venant o de Vlasov. En este capítulo, sin embargo, sólo se tratará la torsión en
perfiles delgados cerrados.

La hipótesis fundamental en la teoría de perfiles delgados cerrados consiste en
suponer que el torsor origina una tensión cortante constante en cada sección del espesor
del tubo delgado (figura 8.2b): en la sección B-B1 el espesor del perfil delgado es tB y la
tensión es constante de valor τB. Para la sección A-A1 el espesor del perfil y la tensión
serán tA y τA, respectivamente.

<!-- p. 277 -->

HORMIGÓN ESTRUCTURAL 277
Hernández-Gil

T

dA/2
x

A1 B1 B dΓ Γ tB B
A
A’1 B’1 rO B1
O τB
A’ B’ A1
tA
τA A
a b

Figura 8.2. Torsión en perfiles delgados cerrados

Aplicando el teorema de reciprocidad de las tensiones tangenciales a la figura
8.2a se deduce que en la cara A-A1-A’1-A’ aparece una tensión tangencial de valor τA,
mientras que en la cara opuesta la tensión tangencial es τB. Estableciendo el equilibrio
de fuerzas verticales en las caras A-A1-A’1-A’ y B-B1-B’1-B’ se obtiene que:

τA t A = τB t B = τ t = q

A q se le denomina flujo de cortantes y su valor se mantiene constante a lo
largo de la sección transversal.

Sea Γ la línea formada por los puntos medios en cada sección del tipo AA1
(figura 8.2b). El momento que engendra el flujo de cortantes respecto al eje x es el
momento torsor, que se puede obtener integrando a lo largo de Γ:

O d Γ = q 2 AO T = ∫ q r O d Γ = q ∫ r
Γ
además rO d Γ = 2 ⋅ dA

donde rO es el brazo respecto al punto O (intersección de la sección transversal con el
eje x) y AO es el área que queda dentro de Γ. De la ecuación anterior se puede despejar
el valor de la tensión de cortante τdebida al momento torsor T, sabiendo que q=τ·t.

T
τ = (8.1)
2 AO t

<!-- p. 278 -->

TORSIÓN 278

Para obtener la rigidez de torsión1 ( relación entre el momento torsor T y el
ángulo de giro por unidad de longitud θ) se aplica el principio de los trabajos virtuales.
El trabajo exterior desarrollado por T en una unidad de longitud tiene que ser igual al
trabajo interno desarrollado por las tensiones tangenciales:

T
T θ = ∫τγdVol = 1 ⋅ ∫τγdA = ∫ γt d Γ Vol Area Γ 2 AO t

Si t permanece constante a lo largo de Γ el valor de τ será también constante y
puesto que τ= Gγ, también γpermanecerá constante. Por tanto, se puede sacar γfuera
de la integral y se obtiene el siguiente valor para el ángulo girado por unidad de
longitud:
γΓ T Γ T 4 AO2 t θ = → θ = → G IT = = G 2 2 AO 4 AO tG θ Γ

Momento torsor en piezas de hormigón:

Las normas EHE y el EC2 admiten que el momento torsor es resistido por la
parte exterior de la sección transversal de hormigón, en un espesor he -espesor eficaz-2,
tal y como se indica en la figura 8.3. El valor de he será tal que:

A ⎧ \< h0
he ≤ ⎨
u ⎩ > 2c

donde:
A Área de la sección inscrita en el perímetro exterior
incluyendo las áreas huecas interiores
u Perímetro exterior de la sección transversal
h0 Espesor real de la pared en caso de secciones huecas
c Recubrimiento de las armaduras longitudinales

Así pues, el momento torsor será resistido por una pieza ideal cerrada de pared
delgada con un espesor de pared he y un perímetro exterior u. La línea media del espesor
he se denomina ue, y Ae es el área encerrada por ésta3.

1 Por analogía con la flexión, donde la rigidez es EI, se define la rigidez a torsión como
GIT, siendo IT la rigidez de torsión de la pieza.
2 Esta hipótesis está suficientemente contrastada con la experimentación (Mitchell y
Collins 1978).
3 Los valores he , ue y Ae han sido denominados anteriormente t, Γ y AO respectivamente,
siguiendo la nomenclatura clásica de Resistencia de Materiales.

<!-- p. 279 -->

HORMIGÓN ESTRUCTURAL 279
Hernández-Gil

u
Ae ue
A

he

Figura 8.3. Espesor eficaz

El momento torsor sólo origina tensiones tangenciales, contenidas en el plano
perpendicular al eje del torsor. El valor de T que produce fisuración en la pieza de
hormigón se denomina torsor de fisuración, Tfis, y se alcanza cuando la tensión principal
de tracción es igual a fct. El estado de tensiones existente en una de las caras de la pieza
torsionada, punto A, cuando alcanza Tfis se deduce de la figura 8.4.

A

A τ
τ
τ
2θ A σx θ fct σ
σx

Direcciones principales

Figura 8.4. Grietas de torsión

En la figura 8.4 σx es la tensión debida a un axil exterior de compresión y/o a
la fuerza de pretensado.

Imponiendo en el círculo de Mohr que la tensión máxima de tracción sea igual
a fct, se puede obtener el valor correspondiente de la tensión tangencial τ :

σx 2 2 σx σx fct = ( ) + τ − → τ = fct 1 +
2 2 fct

<!-- p. 280 -->

TORSIÓN 280

Si en la ecuación anterior se sustituye τ por su valor dado por la ecuación 8.1, t
por he (nomenclatura de la EHE) y fct=0.3fck 2/3, se obtiene el siguiente valor del torsor de
figuración, Tfis:

3 2 σx Tfis = 2 he Ae 0 . 30 fck 1 + en N ·mm
0 . 30 3 fck2

8.3. TORSIÓN EN POST-FISURACIÓN Y ROTURA

Como se aprecia en la figura 8.4, cuando se aplica el momento torsor de
fisuración se producen grietas que forman un ángulo θ con la directriz de la pieza. Al
producirse estas grietas en las cuatro caras se forman espirales de bielas comprimidas,
figura 8.4.

Pre-fisuración
q

Opcióndearmado1 Opcióndearmado2

q q

1
Post-fisuración
q/senθ q
θ cosθ
qcotθ

Figura 8.5. Equilibrio en pre-fisuración y rotura

En la figura 8.5 se observa como el flujo de cortantes (q=t·τ), en pre-fisuración
éste genera internamente compresiones y tracciones en el hormigón. Si se pretende que
la pieza fisurada resista la solicitación de torsión será necesario, para equilibrar el flujo
de cortantes, que las tracciones que el hormigón deja de resistir sean resistidas por una

<!-- p. 281 -->

HORMIGÓN ESTRUCTURAL 281
Hernández-Gil
armadura. Como ya vimos, en post-fisuración el hormigón no puede resistir las
tracciones y sólo resistirá a compresión siguiendo la dirección que forman las bielas
formadas en rotura.

Se puede optar por colocar la armadura paralela a la dirección principal de
tracción, o sea siguiendo las tracciones inducidas por el flujo de cortante q: opción de
armado 1 en la figura 8.5.

Otra posibilidad es colocar la armadura paralela al eje de la pieza, opción de
armado 2 en la figura 8.5. En este caso, cuando el hormigón fisura se produce un
cambio brusco en la forma de equilibrar el flujo de cortante (q) debido a que las
tracciones sólo pueden ser absorbidas en paralelo al eje de la pieza, viéndose las
compresiones incrementadas.

En la opción de armado 1, si el flujo de cortante cambia de signo la pieza no
resistirá mientras que, por el contrario, la opción de armado 2 no se ve afectada por el
cambio de signo. Por tanto, la opción de armado 2 es la más interesante.

Así pues, q se va a descomponer de tal forma que las tracciones sean paralelas
al eje de la pieza (figura 8.5 post-fisuración). Si ya se han formado bielas de
compresión4 con una inclinación θ, el valor de las tracciones por unidad de longitud5 es
q·cotθ. Ver figura 8.3.

La resultante de la tracción generada tiene un valor de q·cotθ ·ue, que será
resistida por una armadura longitudinal distribuida de forma homogénea a lo largo de
ue. El valor del área de esta armadura ,Al, se determina a partir de la ecuación de
equilibrio:

q cot θu e = Al f yl ,d

Si se introduce el valor de q=τ⋅t dado por la ecuación 8.1 en la expresión
anterior se obtiene el siguiente valor del momento torsor:

2 Ae T = Al f yl ,d tgθ = Tu 3
u e

La Norma EHE denomina Tu3 al máximo momento torsor que pueden resistir
las armaduras longitudinales Al. En la ecuación anterior fyl,d es la resistencia
característica de la armadura longitudinal. Puesto que para el estudio de la torsión se ha
empleado la teoría de las bielas, la deformación del acero no puede ser excesiva y por
este motivo fyl,d no será mayor de 400 N/mm2.

En la figura 8.5 se observa además que las tensiones de compresión se
modifican en post-fisuración, respecto al estado de pre-fisuración. En post-fisuración el

4 En rotura.
5 Unidad de longitud medida en la dirección de q, o sea según ue.

<!-- p. 282 -->

TORSIÓN 282

flujo de cortantes q produce un flujo de compresiones q/senθ por unidad de longitud en
ue. Así pues, q origina unas tensiones en biela cuyo valor viene dado por:

q 1
σc = ≤ f1cd
senθ he cosθ

Sustituyendo en la expresión anterior el valor de q obtenido de la ecuación 8.1
e imponiendo el agotamiento del hormigón a compresión se puede obtener el valor de T:

Según la EHE cotθ
T = 2f1cd Ae he senθcosθ ⎯⎯ ⎯ ⎯ ⎯→ Tu 1 = αf1cd Ae he 2 1 + cot θ

donde f1cd es la resistencia a compresión del hormigón en biela (la EHE toma
f1cd=0.6fcd), el parámetro αtoma el valor de 1.2 si hay estribos únicamente a lo largo del
perímetro exterior de la pieza y 1.5 si se colocan estribos cerrados en ambas caras de la
pared de la sección hueca equivalente o de la sección hueca real. El valor de Tu1
corresponde al máximo momento torsor que pueden resistir las bielas comprimidas de
hormigón.

Atσt

qst tanθ
qst /cosθ
q
θ

q qst

st

Figura 8.6. Equilibrio para determinar la armadura transversal

Si se aísla la esquina inferior derecha del elemento de la figura 8.4 en una
longitud st (figura 8.6) y se establece el equilibrio de esfuerzos sobre la cara superior, se
observa que es necesario disponer una armadura transversal para absorber las
tracciones. Si esta armadura está constituida por barras de área At separadas st, se habrá
de verificar que:

Atσt = q s t tanθ

<!-- p. 283 -->

HORMIGÓN ESTRUCTURAL 283
Hernández-Gil
Es interesante señalar que, a diferencia con el cortante, en la expresión anterior At es el
área del redondo. Sustituyendo q por su valor (ecuación 8.1) e imponiendo que la
tensión de la armadura transversal alcance su tensión límite σt=fyt,d, obtenemos:

2 Ae At T = f yt ,d cotθ = Tu 2
s t

La EHE denomina Tu2 al máximo momento torsor que pueden resistir las armaduras
transversales.

Ejemplo

Considermos la viga ABC como de la figura 8.7, solicitada por una carga
puntual de diseño en C de 30 kN. Toda la viga tiene unas dimensiones de 0.6×0.6 m . El
hormigón es del tipo HA-25 y el acero B-500-S. Se pide: Calcular la armadura necesaria
para resistir el momento torsor generado por la carga puntual.

A 30 kN
8 m Td=150 kN·m

B C
A B
5 m Diagrama de momentos torsores

Figura 8.7. Ejemplo de dimensionamiento a momento torsor

Según el artículo 45.2 de la EHE, el torsor de diseño Td tiene que ser menor
que Tu1, Tu2 y Tu3. O sea, tiene que no agotar a compresión las bielas de hormigón y no
superar la resistencia de la armadura transversal ni longitudinal, respectivamente.

En primer lugar se calcularán los parámetros del área efectiva:

A 0 . 6 ⋅ 0 . 6
he = = = 0 . 15 m = 150 mm
u 4 ⋅ 0 . 6
Ae = ( 0 . 6 − 0 . 15 ) 2 = 0 . 2025 m 2 = 202500 mm 2
u e = 4 ⋅ ( 0 . 6 − 0 . 15 ) = 1 . 8 m = 1800 mm

El torsor que pueden resistir las bielas a compresión, Tu1, será:

<!-- p. 284 -->

TORSIÓN 284

cot θ 25 1
Tu 1 = αf1cd Ae he 2 = 1 . 2 ⋅ 0 . 6 ⋅ 202500 ⋅ 150 ⋅ = 182 . 25 kN ⋅ m 1 + cot θ 1 . 5 1 + 1

Puesto que no existen tensiones de compresión se ha adoptado θ=45º y , al ser
la sección maciza, α=1.2. Dado que Tu1>Td el torsor de diseño no provoca rotura a
compresión en las bielas.

Antes de calcular Tu2, torsor que resisten las armaduras transversales, vamos a
considerar la disposición que establece la norma para estas armaduras transversales
(artíc. 45.2.3 de la EHE). La separación st deberá ser ≤ue/8=22.5 cm. Ya que Td >2Tu1/3
st deberá de ser ≤0.30·lado=13.5 cm. Un valor válido de st es 12 cm.

2 Ae At 2 ⋅ 202500 ⋅ A t Tu 2 = f yt ,d cotθ = ⋅ 400 ⋅ 1 > Td
s t s t

De la expresión anterior se puede deducir el valor de At. Dispondremos cercos
∅12 cada 12 cm.

Por último nos queda dimensionar la armadura longitudinal a partir del torsor
Tu3:

2 Ae 2 ⋅ 202500 6Tu 3 = Al f yl , d tgθ = ⋅ Al ⋅ 400 ⋅ 1 ≥ Td = 150 ⋅ 10 N ⋅ mm ⇒
u e 1800
⇒ Al ≥ 1667 mm 2

La armadura longitudinal necesaria para resistir el momento torsor se puede
dotar con 16∅12 ( 5∅12 por cara).

8.4. INTERACCIÓN ENTRE TORSIÓN Y OTROS ESFUERZOS

El estudio de la interacción de la torsión con otros esfuerzos es bastante
complejo. La flexión hace que la tensión normal varíe en la sección transversal de un
elemento lo que provoca una variación en el ángulo de inclinación de las bielas de
compresión, θ. Así pues, el ángulo θ no permanece constante en la sección, debido a
que la variación de la tensión normal hace cambiar la dirección principal de compresión.

La existencia de flexión, cortante y torsor hace que la inclinación de las bielas
de compresión sea diferente en cada cara del elemento, (Rabat y Collins 1977), puesto
que las tensiones normales y cortantes que aparecen son distintas.

La normativa actual emplea métodos simplificados para tratar la interacción
entre la torsión y otros esfuerzos. A continuación se transcribe el artículo 45.3.2 de la
EHE.

<!-- p. 285 -->

HORMIGÓN ESTRUCTURAL 285
Hernández-Gil

Torsión combinada con flexión y axil

Las armaduras longitudinales necesarias para torsión y flexocompresión o
flexotracción se deben calcular por separado suponiendo la actuación de ambos tipos de
esfuerzos de forma independiente. Las armaduras así calculadas se combinarán de
acuerdo con las siguientes reglas:

\1. En la zona traccionada debida a la flexión compuesta, las armaduras
longitudinales por torsión se sumarán a las necesarias por los esfuerzos de
flexión y axil.

\2. En la zona comprimida debido a la flexión compuesta, si la capacidad
mecánica de las armaduras de torsión a disponer es inferior al esfuerzo de
compresión del hormigón debido a la flexión compuesta, no será necesario
añadir armadura por torsión. En caso contrario se añadirá la diferencia
entre ambos valores.

Respecto a las compresiones en el hormigón, deberá comprobarse que la
tensión principal de compresión σcd en el punto crítico de la sección verificará:
σcd≤α·f1cd donde αy f1cd son los valores empleados en la deducción de Tu1. Para calcular
σcd se empleará la tensión normal debida a la flexión compuesta σmd y la tensión
tangencial τtd (td significa torsor de diseño) debida al esfuerzo torsor calculada según la
ecuación 8.1. Una vez obtenidos σmd y τtd , mediante el círculo de Morh se calcula el
valor de σcd, tensión principal de compresión.

Es interesante observar que el planteamiento superior es válido siempre que
Td\<Tfis, en el caso que Td≥Tfis habría que hacer la comprobación basándose en teoría de
bielas y tirantes (Hernández-Montes et al. 2004).

Torsión combinada con cortante.

Los esfuerzos torsores y cortantes de cálculo concomitantes deberán satisfacer
la siguiente condición para asegurar que no se producen compresiones excesivas en el
hormigón:
β β
⎛ Td ⎞ ⎛ Vrd ⎞
⎜⎜ ⎟⎟ + ⎜⎜ ⎟⎟ ≤ 1 ⎝ Tu 1 ⎠ ⎝ Vu 1 ⎠
he ⎞ donde β = 2 ⋅ ⎛−⎜ 1 ⎟
⎝ b ⎠

b es el ancho del elemento, igual al ancho total para sección maciza y a la suma de los
anchos de las almas para sección cajón.

El dimensionamiento de los estribos se realizarán de forma independiente, para
la torsión y para el cortante y se sumarán ambos. Se tendrá en cuenta que las armaduras

<!-- p. 286 -->

TORSIÓN 286

de la torsión deberán disponerse en el perímetro exterior de la sección, sin embargo en
el cortante no es necesario. En ambos dimensionados, de cortante y torsor, se empleará
el mismo ángulo de inclinación de las bielas de compresión, θ.

Ejemplo

Consideremos la viga ABC de la figura 8.8, ya estudiada en el ejemplo
anterior. La solicitación consiste en una carga puntual de diseño en C de 30 kN. Las
dimensiones de la sección transversal son de 0.6×0.6 m. El hormigón es del tipo HA-25
y el acero B-500-S. Se pide: calcular la armadura necesaria en el punto A.

Md=240 kN·m Ley decalada

A B
Ley de momentos flectores

A 30 kN

8 m
Vd=30 kN
B C
A B
5 m Ley de cortantes

Td=150 kN·m
A B
Diagrama de momentos torsores

Figura 8.8. Ejemplo de dimensionamiento frente a momento torsor combinado

Del planteamiento del problema de flexión simple empleando el diagrama
rectangular del hormigón y con un canto útil de d=530 mm, se obtiene rotura en el
dominio 2 y los resultados son: x=70.3 mm (profundidad de la fibra neutra), As=1100
mm2. Esta cuantía es superior al mínimo mecánico (Apdo. 42.3.2 de la EHE) y al
mínimo geométrico (Artíc. 42.3.5 de la EHE). La armadura mínima geométrica a
compresión, en la cara inferior es:

2 . 8 2 As′ = 0 . 3 ⋅ 600 ⋅ 600 = 302 . 4 mm → 3φ12
1000

Para el cortante se obtiene un valor de Vcu = 105 kN superior a Vd. La armadura mínima
de cortante es (Artíc. 44.2.3.4.1 de la EHE):

fcd 16 . 67 2 Amín = 0 . 02 b0 = 0 . 02 ⋅ ⋅ 600 = 0 . 5 mm / mm
f yα, d 400

<!-- p. 287 -->

HORMIGÓN ESTRUCTURAL 287
Hernández-Gil
Los cercos deben disponerse a una distancia: ≤30 cm, ≤0.8·d=424 mm por ser
Vrd≤0.2·Vu1. Colocando estribos a 30 cm tenemos:

Aα = n ramas · Aredondo → 300 ⋅ 0 . 5 = 2 ⋅ Aredondo → cφ10 a 30 cms t ⋅∑

Interacción torsor-flector

En la cara traccionada se coloca la suma de la armadura necesaria a torsión más
la necesaria a flexión:

1664 2
As ,torsión + As ,tracción = + 1100 = 1516 . 75 mm → 5φ20
4

En la cara comprimida la capacidad mecánica de la armadura de torsión es
inferior al esfuerzo de compresión inducido en el hormigón por la flexión6, no siendo
necesario añadir ninguna armadura de torsión.

En las caras laterales se añadirá la de torsión, o sea 5∅12 en cada cara.

Interacción torsor-cortante

Las armaduras calculadas en este caso se sumarán, teniendo en cuenta que los
cercos de torsión deben disponerse en el perímetro exterior mientras que los de cortante
no es necesario que cumplan esta prescripción.

A su vez la limitación en bielas de compresión obliga a cumplir:
β β
⎛ Td ⎞ ⎛ Vrd ⎞
⎜⎜ ⎟⎟ + ⎜⎜ ⎟⎟ ≤ 1 ⎝ Tu 1 ⎠ ⎝ Vu 1 ⎠
he ⎞ donde β = 2 ⋅ ⎛−⎜ 1 ⎟ = 1 . 5
⎝ b ⎠

que en nuestro caso se cumple sobradamente.

La disposición definitiva de armadura será la indicada en la figura 8.8.

6 En este caso, por tratarse de flexión simple, equivale a la capacidad mecánica de la
armadura de tracción calculada.

<!-- p. 288 -->

TORSIÓN 288

4φ12
cφ12 a 12

5φ12
0.6 m

5φ12 cφ10 a 30

0.6 m

5φ20

Figura 8.8. Armado final

<!-- p. 289 -->

HORMIGÓN ESTRUCTURAL 289
Hernández-Gil

Ejercicios propuestos

\1. Consideremos una sección cuadrada de 0.6×0.6 m, maciza, fabricada con HA-25.
Dicha sección está solicitada por un momento flector aplicado de 28.8 kN·m que actúa
junto con un torsor de 180 kN·m.

\- Calcular la tensión normal máxima de compresión y de tracción generada por
el momento flector, suponiendo distribución lineal.
\- Calcular el torsor de fisuración en las caras perpendiculares al eje de aplicación
del momento flector, sin tener en cuenta la tensión normal.
\- Calcular el torsor de fisuración en las caras paralelas al eje de aplicación del
momento flector.
\- Aplicar criterios de mecánica del medio continuo o de teoría de bielas, según
proceda para estimar la tensión máxima en el hormigón.

<!-- p. 290 -->

TORSIÓN 290

Referencias:

ASCE-ACI Committe 445 on Shear and Torsion. "Recent Approaches to Shear Design
of Structural Concrete". Journal of Structural Engineering. December 1998. Páginas
1375- 1417.

Building Code Requirements for Structural Concrete (ACI 318-05) and Comentary
(ACI 318R-02). American Concrete Institute. Michigan. (Enero 2005).

Collins M.P., Mitchell D., (1991). Prestressed Concrete Structures. Prentice Hall,
Nueva Jersey.

Hernández Montes, E. Gil Martín, L.M. y Albajar Molera L. (2004). “Límites de la
teoría de rotura y prerrotura para solicitaciones combinación de momentos torsores y
flectores en piezas de hormigón”. Hormigón y Acero. Nº 231. Primer trimestre 2004.
Pág. 97-100.

Mitchell, D., and Collins, M.P., “Influence of Prestressing on Torsional Response of
Concrete Beams”. PCI Journal, Vol.23, Nº3. Mayo-Junio 1978. págs. 54-73.

Rabbat, B., y Collins, M.P. “A Varible Angle Space Truss Model for Structural
Members Subjected to Complex Loading”. Douglas McHenry International Symposium
on Concrete and Concrete Structures. SP-55, American Concrete Institute, Detroit,
1977, pp.229-236.

<!-- p. 291 -->

HORMIGÓN ESTRUCTURAL 291
Hernández-Gil

<!-- p. 292 -->

ANÁLISIS ESTRUCTURAL 292

<!-- p. 293 -->

HORMIGÓN ESTRUCTURAL 293
Hernández-Gil

CAPÍTULO IX

ANÁLISIS ESTRUCTURAL

Edificio Diputación de Granada
Cortesía de GARASA-ESÑECO
www.garasa.com

9.1. INTRODUCCIÓN

El propósito del cálculo de estructuras es determinar la distribución de fuerzas
internas (diagramas de axiles, cortantes y momentos) o tensiones, deformaciones y
desplazamientos de todos los elementos que componen una estructura.

Para calcular una estructura se deben de dar los siguientes pasos:

\1. Realizar un modelo de la estructura mediante nudos y barras.
\2. Asignar propiedades a cada barra: áreas, inercias y módulos de rigidez.
\3. Optar por un tipo de análisis estructural.

<!-- p. 294 -->

ANÁLISIS ESTRUCTURAL 294

\4. Calcular la estructura: obtener los desplazamientos de cada grado de libertad
considerado, a partir de los cuales se obtendrán las deformaciones y los
esfuerzos existentes en cada sección.
\5. Dimensionar la estructura (dotarla de armadura).

Realizar un modelo de nudos y barras es un proceso sencillo donde la práctica
juega un papel fundamental. Este proceso se ha abordado en problemas de resistencia de
materiales y de cálculo de estructuras.

El siguiente paso consiste en definir las barras de la estructura, esto es, decidir el
área, las inercias y el material de las mismas. Este primer paso se denomina
tradicionalmente predimensionamiento. Existen numerosos procedimientos para
predimensionar una estructura de hormigón. Por ejemplo,, para dimensionar un pilar es
frecuente optar por una sección bruta rectangular que cumpliera la siguiente condición:
N d Ac = 0 . 1
f cd

Otra manera de predimensionar consiste en adoptar las secciones de una estructura
parecida y modificarlas (aumentándolas o reduciéndolas) analizando el coste total de la
estructura y verificando que las modificaciones efectuadas abaratan la estructura final.

Determinados el modelo y las secciones de las barras, es necesario decidir el tipo
de análisis estructural a utilizar. En el apartado siguiente se examinan las peculiaridades
de cada tipo de análisis estructural. Elegido el tipo de análisis se determinarán los
esfuerzos flectores, axiles, cortantes y de torsión que solicitan a los elementos de la
estructura así como sus deformaciones. El último paso consiste en dimensionar los
elementos de hormigón armado y pretensado de tal forma que resistan los esfuerzos y
que cumplan las limitaciones de deformaciones (flechas y fisuras).

Para definir las propiedades mecánicas de cada elemento se pueden considerar
los siguientes tipos de secciones:

\- Sección bruta: la sección que resulta de tomar las dimensiones reales de la pieza,
sin deducir los huecos de las armaduras.
\- Sección neta: la obtenida a partir de la sección bruta deduciendo los huecos
longitudinales practicados en el hormigón, tales como entubaciones o entalladuras,
para el paso de las armaduras activas o sus anclajes.
\- Sección homogeneizada: la obtenida a partir de la sección neta considerando la
presencia de armadura longitudinal adherente. Esta última se multiplica por el
correspondiente coeficiente de equivalencia1 (n).
\- Sección fisurada: es la sección formada por la zona comprimida del hormigón y las
áreas de las armaduras longitudinales, tanto activas adherentes como pasivas,
multiplicadas por el correspondiente coeficiente de equivalencia.

El empleo de una sección u otra va a depender del tipo de análisis estructural por
el que se opte, como se verá más adelante.

1 Coeficiente de equivalencia n=Es/Ec.

<!-- p. 295 -->

HORMIGÓN ESTRUCTURAL 295
Hernández-Gil

En estructuras de hormigón la forma más usual de sección transversal para
pilares es rectangular o circular, manteniéndose ésta constante en toda la longitud del
elemento. Sin embargo, son posibles otras formas de y la sección transversal puede
variar a lo largo de la pieza.

Es interesante señalar que en estructuras de hormigón los nudos generalmente
transmiten momentos y, por tanto, los pilares trabajarán como vigas-columnas, estando
sometidos a todo tipo de solicitaciones: axiles, flectores, cortantes y torsores.

Figura 9.1. Secciones de pilares, cuadrada y circular

9.2 TIPOS DE ANÁLISIS ESTRUCTURAL

El EC2 (Eurocódigo 2) considera las siguientes idealizaciones del comportamiento
estructural:

\- Comportamiento elástico lineal
\- Comportamiento elástico lineal con redistribución limitada (o elasto-plástico)
\- Comportamiento plástico
\- Comportamiento no-lineal

Estas idealizaciones dan lugar a distintos tipos de análisis, cuyas características
generales se pueden ver en la tabla 9.1.

<!-- p. 296 -->

ANÁLISIS ESTRUCTURAL 296

Tabla 9.1. Tipos de Análisis Estructural
Hipótesis
Material Pequeños Pequeñas
desplazamientos (1) deformaciones (2)
Elástico Lineal Elástico-lineal Sí Sí
Elástico Lineal con Elástico-plástico Sí o No Sí
redistribución
limitada
Plástico Elasto-plástico ó Sí o No Sí
Rígido-plástico
No lineal No lineal Sí o No Sí o No
(1) Pequeños desplazamientos equivale a considerar el equilibrio sobre la
estructura no deformada. Esto se conoce como cálculo en primer orden ( o
no considerar los efectos P∆). Por el contrario tener en cuenta los
desplazamientos equivale a considerar los efectos P∆, también se
denomina cálculo en segundo orden, o que se considera la no-linealidad
geométrica.
(2) La hipótesis de pequeñas deformaciones permite aproximar, en flexión, la
curvatura por la derivada segunda (d2y/dx2).

Análisis elástico lineal

El análisis elástico lineal (o análisis en primer orden) está basado en la teoría
de elasticidad y se puede aplicar tanto para las comprobaciones de ELU como de ELS.
En este tipo de análisis se suele considerar:

\- Propiedades de las secciones transversales brutas. O bien unas reducciones de
éstas como veremos más adelante.
\- Relación tensión-deformación lineal en la curva de comportamiento del
material.
\- Valores medios de los módulos de elasticidad.

La ventaja principal de este tipo de análisis es que se puede aplicar una
formulación matricial lineal. Recordamos de los cursos de cálculo de estructuras que
una barra en dos dimensiones tiene 6 grados de libertad (g.d.l.2). Por tanto, los
desplazamientos en los nodos (figura 9.2 izq), agrupados en el vector δ, están
relacionados con las fuerzas que actúan sobre los nodos (figura 9.2. derecha), vector f.
La relación entre ambos vectores, δ y f, es la matriz de rigidez de la barra k. Las
componentes de k son kij, donde kij es el valor de la componente i del vector de fuerzas f
cuando se impone un valor unidad al gdl j en el vector δ, permaneciendo el resto de los
desplazamientos iguales a cero.

2 Un gdl (grado de libertad) es cada uno de los componentes ortogonales que caracterizan el
movimiento de cada nodo de la estructura. En general -salvo restricciones- una barra (que une dos
nodos) en el plano tiene 6 gdl y en el espacio 12 gdl.

<!-- p. 297 -->

HORMIGÓN ESTRUCTURAL 297
Hernández-Gil
vi θi E;I;A:L vj θ Vi Mi E;I;A;L Vj Mj

ui uj
i j i Hi j Hj

Figura 9.2. Movimientos y esfuerzos en una barra con 6 gdl

En la barra de la figura 9.2 se han considerado 6 gdl y la expresión matricial de
relación existente entre f y δ es f=kδ, desarrollada a continuación:

⎡ A 0 0 − A 0 0 ⎤
12 12 I 6I I 6I ⎥⎡ H i ⎤ ⎢ ⎡ u i ⎤ 0 0 − 2 2 ⎢ ⎥⎢ ⎥ L L L L ⎢ ⎥ Vi ⎢ ⎥ v i⎢ ⎥ 6I 6I ⎢ ⎥
⎢ M i ⎥ E ⎢ 0 4I 0 − 2I ⎥ ⎢θi ⎥⎢ ⎥ = ⎢ L L ⎥ ⋅ ⎢ ⎥ (9.1)
⎢ H j ⎥ L ⎢ − A 0 0 A 0 0 ⎥ ⎢u j ⎥
⎢v j ⎥⎢ V j ⎥ ⎢ 0 − 122I − 6I 0 122I − 6I ⎥⎢ ⎥ ⎢ L L L L ⎥ ⎢ ⎥
⎢⎣M j ⎥⎦ ⎢ 6I 6I ⎥ ⎢⎣θj ⎥⎦ ⎢ 0 2I 0 − 4I ⎥
⎣ L L ⎦
1444444442444444443
k

Ensamblando todas las barras de una estructura y realizando los cambios de
base necesarios se llega a la expresión típica de cálculo de estructuras

F = KD (9.2)

donde F es el vector de fuerzas exteriores sobre los gdl considerados en la estructura, D
es el vector desplazamientos de los gdl de la estructura y K es la matriz de rigidez de la
estructura.

Puesto que este análisis es lineal, si un vector F da lugar a unos
desplazamientos D, un vector αF dará lugar a unos desplazamientos αD. En este tipo de
análisis el equilibrio se establece sobre la estructura no deformada, siendo posible que la
estructura deformada no esté en equilibrio. Consideremos el siguiente ejemplo.

Ejemplo

En la figura 9.3 se ha representado una columna de altura h sometida a un axil
P y a una fuerza horizontal V. Si aplicamos análisis elástico lineal el momento en el
punto A es MA=V·h, dado que la carga P no produce ningún momento en la estructura
no deformada. Si la columna se deforma tal y como se indica en la figura (debido a V y
a P) se producirá un desplazamiento ∆ y, como consecuencia de éste, aparecerá un

<!-- p. 298 -->

ANÁLISIS ESTRUCTURAL 298

momento adicional (P∆) que será necesario considerar. Puesto que en el análisis elástico
lineal se considera el equilibrio sobre la estructura no deformada se desprecian los
desplazamientos y los esfuerzos adicionales asociados a éstos. A esto se le conoce como
hipótesis de pequeños desplazamientos, que equivale a no considerar los efectos P∆,
también se dice que no se ha considerado la no linealidad geométrica, ver tabla 9.1.

P
V

h
∆

A

Figura 9.3.

Está bastante extendido y la norma EHE así lo permite realizar un cálculo en
primer orden (análisis elástico lineal, EHE artículo 19.2.1) empleando las características
de la sección bruta, lo que tiene la ventaja de que no se necesita conocer la armadura de
los elementos para realizar el cálculo estructural.

<!-- p. 299 -->

HORMIGÓN ESTRUCTURAL 299
Hernández-Gil
Análisis elástico lineal con redistribución limitada

En algunas ocasiones se permite una redistribución de momentos en vigas. Esto
se debe a que la hipótesis de relación lineal tensión-deformación en el material resulta
excesiva siendo necesario considerar la plastificación del material. Veamos un ejemplo.

Ley de momentos elástica lineal

q
qL2/12
a
qL2/24

L

Ley de momentos elástica lineal
con redistribución limitada

Momento

Mpl
b

giro

Figura 9.4. Viga biempotrada.

Ejemplo

La figura 9.4 corresponde a una viga biempotrada de sección transversal
constante sometida a una carga uniforme q. Si se realiza un análisis elástico-lineal el
momento en el empotramiento es qL2/12 mientras que el momento en el centro de vano
es de qL2/24. Si la sección tiene suficiente capacidad de rotación con momento
constante (Figura 9.4.b) se puede permitir la plastificación en los puntos de momento
máximo con la consiguiente redistribución de la ley de momentos, tal y como se indica
en la figura 9.4a en línea discontinua. Si el momento plástico (Mpl de la figura 9.4b) de
la sección transversal de la viga es mayor que qL2/12 la ley de flectores será la obtenida
mediante análisis elástico lineal sin redistribución (línea continua en la figura 9.4a)
mientras que en caso contrario –por ejemplo una sección cuyo momento plástico sea
qL2/16- la viga plastificará en las secciones de apoyo y la ley se desplazará tal y como
muestra la línea discontinua en la misma figura.

<!-- p. 300 -->

ANÁLISIS ESTRUCTURAL 300

Análisis plástico

El análisis plástico está basado fundamentalmente en la formación de rótulas3 o
zonas plásticas que permiten el giro manteniendo el momento (relación bilineal
momento-giro), o bien estableciendo otro tipo de relaciones (empíricas, poli-lineales,
etc), Código Modelo CEB-FIP (1990). Un caso límite es el análisis rígido-plástico en el
que la deformación estructural se concentra en las rótulas, como es el caso del análisis
de líneas de rotura en placas (Jiménez Montoya (1994)).

Existen distintos tipos de análisis plástico. El más extendido en hormigón es el
tipo biela-tirante al que se le ha dedicado el capítulo 5 de este libro.

Análisis no lineal

Se dice que el análisis es no lineal cuando la relación tensión-deformación del
material es no lineal, independientemente de que se considere el equilibrio en primer o
en segundo orden, Chen y Sohal (1995). Este tipo de análisis puede ser empleado en
ELS y en ELU, ver tabla 9.1.

\* * *

Además de la clasificación general que aparece en la tabla 9.1 existen diversas
hipótesis y simplificaciones que necesitan ser consideradas para delimitar
completamente el tipo de análisis estructural.

Deformación de cortante: en la expresión matricial 9.1, los coeficientes kij de la matriz k
sólo consideran deformaciones axiles y de flexión. Se podría también considerar
deformación por cortante (lo que se ha llamado tradicionalmente “viga de
Timoshenko”). Añadir el término de deformación de cortante a los coeficientes kij de la
expresión 9.1 no altera la linealidad del planteamiento, de tal forma que la deformación
por cortante se puede considerar también en análisis elástico-lineal. No obstante, en
estructuras de hormigón no se suele considerars la deformación de cortante.

Pequeñas deformaciones: tal y como se ha comentado en la tabla 9.1 pequeñas
deformaciones equivale a considerar, en flexión, la curvatura como d2y/dx2. En la
expresión 9.1 ya se ha considerado la hipótesis de pequeñas deformaciones, puesto que
en las regiones B4 de estructuras de hormigón siempre se adopta esta hipótesis.

Grandes desplazamientos o cálculo en segundo orden (no-linealidad geométrica): Esta
hipótesis consiste en plantear el equilibrio sobre la estructura deformada. Adoptando
esta hipótesis, en el ejemplo de la figura 9.3 el momento en el punto A es MA=V·h+P∆.
Evidentemente se trata de un problema mucho más complejo puesto que ∆ no es
conocido a priori y el problema ya no es lineal. El apartado siguiente está dedicado al
cálculo en segundo orden.

3 El EC2 admite que una rótula tiene una longitud de 1.2 veces el canto de la sección y
propone valores de la rotación admisible para secciones de hormigón.
4 Región B, de Bernouilli, ya estudiado en el capítulo 5.

<!-- p. 301 -->

HORMIGÓN ESTRUCTURAL 301
Hernández-Gil

Fluencia: En la expresión 9.1 el valor de E corresponde al módulo de deformación
longitudinal del hormigón Ec (ecuación 3.4). Si se consideran los efectos de la fluencia
el valor de Ec variará en función del tiempo y del nivel de carga. En este caso se emplea
el módulo efectivo del hormigón, definido como:

E cm E c , ef ( t , t 0 ) = (9.3)
1 + ϕ( t , t 0 )

donde φ(t,t0) es el coeficiente de fluencia, ya estudiado en el apartado 3.4.

El efecto de la duración de la carga se puede tener en cuenta de forma
simplificada introduciendo el denominado coeficiente efectivo de fluencia (φef). Este
coeficiente puede ser empleado para la carga de diseño proporcionaron objeto de
obtener la deformación por fluencia correspondiente a la carga cuasi-permanente.

M 0 Eqp
ϕef = ϕ∞ , t 0 (9.4)
M 0 Ed

donde: φ∞,t0 es el coeficiente final de fluencia, según el apartado 3.4
M0Eqp es el momento de primer orden obtenido para la combinación de carga
cuasi-permanente.
M0Ed es el momento de primer orden obtenido para la combinación de
diseño

Variación de la sección transversal: la sección transversal y sus propiedades mecánicas
pueden también cambiar. Esta variación se produce sobre todo debido a los esfuerzos,
ya que, la sección transversal y sus propiedades varían en función de la fisuración de la
sección. El Eurocódigo 2 y la EHE española permiten el empleo de las características de
la sección bruta para análisis elástico lineal (apartado 5.4(2) del EC2). El EC2 también
aborda la posibilidad de realizar el cálculo empleando secciones fisuradas (apartado
5.8.7.2(4)). La norma americana ACI-318 especifica que los desplazamientos
horizontales se pueden calcular en primer orden empleando las siguientes propiedades
en los elementos:

a) Módulo de elasticidad: Ec
b) Momentos de inercia
\- En vigas I=0.35Ibruta
\- En vigas en T: I=2Ibruta del alma
\- En columnas I=0.7Ibruta
\- En muros: - No fisurados I=0.70 Ibruta
\- Fisurados I=0.35 Ibruta
\- En láminas planas I=0.25 Ibruta
c) Área =1.0 Abruta

<!-- p. 302 -->

ANÁLISIS ESTRUCTURAL 302

Rigidez tensional o tensorrigidez. La influencia del hormigón a tracción en la fase de
post-fisuración se realiza mediante modelos de tensorrigidez, tal y como se ha descrito
en los capítulos 6 y 7.

9.3. ANÁLISIS EN SEGUNDO ORDEN

El análisis en segundo orden tiene especial relevancia cuando los esfuerzos axiles son
elevados, como es el caso de los pilares. Un pilar de un edifico o la pila de un puente se
diferencian de otros elementos estructurales en que la carga axil es la solicitación
principal. En elementos como vigas, no sometidos a ninguna carga axial, determinar el
diagrama de momentos flectores es, en general, un proceso sencillo. Sin embargo en
elementos sometidos a cargas axiles este proceso puede resultar más complejo ya que la
determinación del momento máximo de segundo orden en una pila esbelta como la de la
figura 9.3 requiere conocer cuánto se va a desplazar ésta en horizontal. Una estructura
se define como traslacional cuando su desplazamiento horizontal no puede ser
despreciado, apareciendo entonces unos efectos adicionales denominados efectos de
segundo orden o efectos P∆5. En el ejemplo de la figura 9.3 el momento en A, obtenido
a partir de un análisis elástico lineal (o de primer orden), es MA=V·h. En el caso de que
se considere el equilibrio en la estructura deformada, si ∆ es el desplazamiento
máximo, el momento en el punto A será MA=V·h+P·∆.

Según el EC2, los efectos de segundo orden pueden ignorarse cuando éstos
constituyan menos del 10% de los correspondientes en primer orden.

Además, según el EC2, en edificios se puede despreciar la influencia de los
efectos de segundo orden cuando se cumple:

E cd I c ns ∑ (9.5) FV , Ed ≤ k1 2
ns + 1 . 6 L

donde:
FV,Ed es la carga vertical total
ns es el número de plantas
L es la altura total del edificio por encima del nivel con momentos
restringidos
Ed es el valor de diseño del módulo elástico del hormigón
Ic es el segundo momento de área (sección no fisurada) de los elementos
que contribuyen a la estabilidad del edificio.

siendo la expresión 9.5 válida siempre que se verifique que:

\- la inestabilidad por torsión no sea predominante, o sea: estructura
razonablemente simétrica,

5 Tener en cuenta la no-linealidad geométrica es equivalente a considerar el equilibrio
en la estructura deformada.

<!-- p. 303 -->

HORMIGÓN ESTRUCTURAL 303
Hernández-Gil
\- las deformaciones globales de cortante sean despreciables
\- las rotaciones en base sean despreciables
\- la rigidez del sistema de rigidización sea razonablemente constante en
altura y
\- la carga vertical aportada por cada planta sea aproximadamente constante.

Formulación matricial de la no-linealidad geométrica

Para formular matricialmente el cálculo en segundo orden (no-linealidad
geométrica) vamos a introducir unas fuerzas denominadas fuerzas de segundo orden6.
Volvamos al ejemplo de la figura 9.3, representado nuevamente en la figura 9.5. Como
se observa en la figura 9.5.derecha junto a la fuerza V se ha introducido una fuerza
F2,orden de tal forma que operando en primer orden se obtienen los desplazamientos y
esfuerzos que se obtendrían en segundo orden7:

M 2, orden = (V + F2, orden ) ⋅ h = V ⋅ h + P ⋅ ∆
P ⋅ ∆
⇒ F2, orden = (9.6)
h
⎛ P ⋅ ∆ ⎞
además M 2, orden = V ⋅ h ⋅ ⎜ 1 + ⎟
⎝ V ⋅ h ⎠

6 Existen otras aproximaciones más exactas para abordar este apartado (Clogh y Penzien
1993 o Cook et al. 1989 ) pero los autores hemos decidido utilizar ésta por su claridad
conceptual.
7 Tradicionalmente al axil se le ha designado con la letra P, de ahí que los efectos de
segundo orden de naturaleza geométrica se les haya denominado efectos P∆. Las
normativas más recientes están utilizando la letra N para designar a la carga axil. En este
volumen emplearemos ambas letras N o P indistintamente para designar la carga axil.

<!-- p. 304 -->

ANÁLISIS ESTRUCTURAL 304

P P
V+F2,orden V

h

Equivale a
∆

A

Figura 9.5. Planteamiento del cálculo en segundo orden

Así pues, los principales responsables de los efectos de segundo orden son los
axiles. Aunque el desplazamiento de la estructura hará que cortantes y flectores también
influyan en los efectos de segundo orden, su influencia será menor que la de los
esfuerzos axiles.

Analicemos a continuación la influencia de los esfuerzos axiles sobre una barra
perteneciente a una estructura de nudos articulados, figura 9.6. Los desplazamientos de
los extremos (i y j), medidos respecto de la posición inicial, en la dirección
perpendicular al esfuerzo axil se han denominado vi y vj en la figura 9.6:

j N

i fGj
N vj

vi fGi E;I;A;L

Figura 9.6. Fuerzas de segundo orden

<!-- p. 305 -->

HORMIGÓN ESTRUCTURAL 305
Hernández-Gil
El equilibrio de la barra deformada se logra mediante la introducción de las
fuerzas de segundo orden (fg), deducidas de aplicar equilibrio de momentos en los nodos
i y j –supuestos articulados-:

v i − v j
N fGi = matricial ⎡fGi ⎤ N ⎡ 1 − 1⎤ ⎡ v i ⎤ L (9.7) ⎯⎯ ⎯⎯→ ⎢ ⎥ = ⋅ ⎢ ⎥ v j − v i ⎣ fGj ⎦ L ⎢⎣ − 1 1 ⎥⎦ ⎣ v j ⎦ fGj = N
L

Es necesario expandir la expresión matricial de las fuerzas de segundo orden
para hacerla compatible con la ecuación 9.1:

⎡ 0 ⎤ ⎡0 0 0 0 0 0 ⎤ ⎡ 0 ⎤
⎢ ⎥ ⎢ ⎥ ⎢ ⎥ fGi 0 1 0 0 − 1 0 v i ⎢ ⎥ ⎢ ⎥ ⎢ ⎥
⎢ 0 ⎥ N ⎢0 0 0 0 0 0 ⎥ ⎢ 0 ⎥
⎢ ⎥ = ⎢ ⎥ ⋅ ⎢ ⎥ (9.8)
0 L 0 0 0 0 0 0 0 ⎢ ⎥ ⎢ ⎥ ⎢ ⎥
⎢fGj ⎥ ⎢0 − 1 0 0 1 0 ⎥ ⎢v j ⎥
⎢⎢⎣ 0 ⎥⎥⎦ ⎢⎢⎣0 0 0 0 0 0 ⎥⎥⎦ ⎢⎢⎣ 0 ⎥⎥⎦
1444442444443
k g

Simbólicamente la ecuación anterior se expresa como fG=kGδ. Esta expresión
se puede sumar a la correspondiente al cálculo en primer orden f=kδ para obtener la
siguiente formulación matricial para el cálculo en segundo orden de la barra aislada:
f = [k − k G ]δ (9.9)

En la ecuación 9.9 k es la matriz de rigidez de la barra y kg se denomina matriz
de rigidez geométrica de la barra. Al igual que ocurría con el cálculo en primer orden, se
pueden ensamblar las matrices de rigidez y rigidez geométrica de todas las barras, con
sus correspondientes cambios de base, obteniéndose la formulación matricial del cálculo
en segundo orden:
F = [K − K G ] ⋅ D (9.10)

donde K es la matriz de rigidez de la estructura, KG es la matriz de rigidez geométrica
de la estructura, , F es el vector de fuerzas exteriores sobre los gdl considerados y D el
vector desplazamientos según esos gdl.

<!-- p. 306 -->

ANÁLISIS ESTRUCTURAL 306

Pandeo global

El planteamiento del problema de la no-linealidad geométrica o cálculo en
segundo orden puede enfocarse desde dos puntos de vista. El primero consiste en
considerar unos desplazamientos adicionales y emplear la formulación matricial dada
por la expresión 9.10. El segundo enfoque consiste en deducir la carga crítica elástica8 o
de pandeo para la cual existan infinitas soluciones del vector D, i.e. infinitos
desplazamientos.

De la ecuación 9.8 se deduce que kg (y por consiguiente también KG) depende
linealmente de los esfuerzos, o sea que si a un vector F0 le corresponde una matriz de
rigidez geométrica KG0, a un vector κF0 le corresponderá κKG0, de tal forma que:
F0 = [K − K G 0 ] ⋅ D
κF0 = [K − κK G 0 ] ⋅ D'

siendo D’ un vector desplazamientos distinto del vector D. Se producirán infinitas
soluciones del vector D’ cuando el problema sea indeterminado. O sea, el problema,
pues, consiste en determinar un escalar κ tal que:
det [K − κK G 0 ] = 0 (9.11)

Esta expresión es conocida como el problema de autovalores de pandeo. A
partir de la ecuación 9.11 se obtendrán los valores de vectores de carga κF0 que
provocan la inestabilidad global de la estructura.

Por definición, κF0 es la carga límite que no se puede superar. Aunque el
cálculo en segundo orden sí tiene un interés práctico, la determinación de los
autovalores (y autovectores asociados) tiene un interés práctico reducido ya que han
sido deducidos admitiendo que el material es lineal y elástico mientras que lo normal es
que se produzcan plastificaciones antes de alcanzar el pandeo. No obstante, son
numerosos los trabajos existentes en relación a la optimización estructural a partir del
problema de autovalores de pandeo (Hjelmstad 1991, Hernández-Montes 2004 y GilMartín 2006).

Pandeo de barras aisladas

De cursos anteriores se sabe que la máxima carga que una barra biarticulada,
como la de la figura 9.7, sometida a una carga de compresión centrada puede soportar es
el valor correspondiente a la carga crítica elástica de pandeo o carga de Euler (PE):

π2 E I mín (9.12) PE = 2 L

8 Se habla de inestabilidad elástica puesto que se supone que el material no abandona el
dominio lineal elástico.

<!-- p. 307 -->

HORMIGÓN ESTRUCTURAL 307
Hernández-Gil

PE

PE

Figura 9.7. Barra aislada biapoyada

Longitud de pandeo

Se define longitud de pandeo o longitud efectiva l0 como: “la mayor distancia
entre dos puntos de inflexión consecutivos, reales o ficticios, de la deformada de pandeo
de la pieza”.

El término longitud de pandeo aparece para extender la expresión de la carga
de Euler a una barra con una sustentación cualquiera en sus extremos, en este caso9:

π2 E I mín (9.13) N b = 2
l 0

Siendo l0=αL, donde αse denomina factor de longitud de pandeo. En el caso
de una barra biarticulada como la de la figura 9.7 tenemos que α=1. Para otros casos
simples el valor de α es el indicado en la figura 9.8:

9 El subíndice B viene de la palabra inglesa “buckling” (pandeo)

<!-- p. 308 -->

ANÁLISIS ESTRUCTURAL 308

α=1 α=2 α=0.7 α=0.5 α=1 α=2

Figura 9.8. Factores de longitud de pandeo

Los casos arriba representados son casos muy simples, se puede decir que son
casos extremos. Consideremos una estructura que no experimente traslaciones
horizontales, una columna intermedia estará unida en su parte superior e inferior a vigas
u a otras columnas. Ninguno de los extremos de la columna en cuestión será ni una
articulación (caso 1 de la figura 9.8) ni un empotramiento perfecto (caso 4) estando,
por tanto, el factor de longitud de pandeo la columna comprendido entre los valores 0.5
y 1.

En edificios donde se desprecia la traslación horizontal (intraslacionales) es
una práctica común considerar α=1, lo que estará del lado de la seguridad y evita el
cálculo de α, que puede ser un tanto tedioso e impreciso, como vamos a ver en el
siguiente subapartado. Esta aproximación es adoptada por la norma ACI-318.

La expresión de PE de la ecuación 9.13 se puede formular en términos de
tensión:
π2 E
(9.14) σE = 2 λ

donde λes la esbeltez mecánica, (λ=l0/imín), siendo imín el radio de giro (imín=(Imín/A)1/2 ),
Imín el momento principal de inercia mínimo y A el área de la sección considerada.

Si representamos la ecuación anterior (hipérbola de Euler) colocando la tensión
en el eje de ordenadas y la esbeltez mecánica en el eje de abcisas, se obtiene la
denominada hipérbola de Euler (figura 9.9).

<!-- p. 309 -->

HORMIGÓN ESTRUCTURAL 309
Hernández-Gil

σc
Curva aproximada de pandeo
Fallo por para hormigón estructural
aplastamiento A
fc
Fallo por
pandeo

λ
λlím

Figura 9.9. Curva de pandeo

El punto A de la figura 9.9 es el punto de intersección de la línea horizontal
(límite de resistencia a compresión del hormigón, σc=fc ) con la hipérbola de Euler. El
punto A es el punto teórico que fija un valor de λdenominado λlím, si λ\< λlím el fallo de
la columna se producirá por agotamiento a resistencia mientras que si λ> λlím el fallo se
producirá por pandeo –estado límite de inestabilidad-.

La EHE fija el valor de λlim=35 y aconseja no superar el límite de λ=200.

Longitud de pandeo de una barra perteneciente a una estructura

Para estudiar la longitud de pandeo de una barra perteneciente a una estructura
es necesario extraerla y plantear las ecuaciones de equilibrio de forma aislada con
objeto de determinar el valor de la carga crítica de pandeo y a partir de la ecuación 9.13
determinar el valor de la longitud de pandeo. Como antes hemos visto, teóricamente los
extremos de la barra pueden ser: articulados, empotrados, libres y permitir o no la
traslación, figura 9.8. En la práctica estos extremos tendrán una rigidez10 determinada y
estarán en una situación intermedia. La figura 9.10 modeliza una barra con unas
condiciones genéricas de apoyo, donde k1 es la rigidez al giro en el apoyo inferior, k2 es
la rigidez al giro en el apoyo superior y k3 es la rigidez al desplazamiento transversal
relativo entre ambos extremos.

La deducción de la longitud de pandeo de una barra perteneciente a una
estructura tradicionalmente se ha llevado a cabo para los dos casos siguientes:

\1. Considerando k3=0, o bien
\2. Considerando k3=∞

10 Rigidez es la relación entre esfuerzo y desplazamiento, o sea: momento/giro o
fuerza/desplazamiento.

<!-- p. 310 -->

ANÁLISIS ESTRUCTURAL 310

Cuando k3=∞ se dice que la estructura es intraslacional y su intraslacionalidad
se garantiza mediante elementos externos a la estructura inicial: rigidizadores centrados
(o cruces de San Andrés), rigidizados excéntricos, muros pantalla, estructuras contiguas,
etc.

k2
k3

k1

Figura 9.10. Estudio de una barra perteneciente a una estructura

Cuando k3=0 la estructura se clasifica como traslacional, y debe de ser la
propia estructura la que garantice que los desplazamientos horizontales son
suficientemente pequeños. Cada norma fija unos límites, la EHE propone L/250 como
flecha máxima genérica. Para estructuras traslacionales el factor de longitud de pandeo
será siempre mayor que 1 (α>1 (caso 5 de la figura 9.8)).

Un estudio teórico sobre este tema se puede ver en (Hernández-Montes 1996).

Así pues, el valor de α para una barra perteneciente a una estructura vendrá
dado en función de la rigidez de cada una de las barras que confluyen en los extremos
del elemento considerado y en función de que la estructura se considere traslacional o
intraslacional (o sea, suponiendo k3=0 ó k3=∞).

Como simplificación la norma EHE propone las siguientes expresiones
aproximadas del coeficiente α para pilares pertenecientes a estructuras porticadas.

Para pórticos intraslacionales:

0 . 64 + 1 . 4( ΨA + ΨB ) + 3 ΨA ΨB α = (9.15)
1 . 28 + 2( ΨA + ΨB ) + 3 ΨA ΨB

Para pórticos traslacionales:

7 . 5 + 4( ΨA + ΨB ) + 1 . 6 ΨA ΨB α = (9.16)
7 . 5 + ( ΨA + ΨB )

<!-- p. 311 -->

HORMIGÓN ESTRUCTURAL 311
Hernández-Gil
donde Ψ es la relación entre las rigideces Σ(EI/L) de los soportes y las rigideces
Σ(EI/L) de las vigas, en cada extremo A y B del pilar considerado. Como valor de I la
norma EHE toma la inercia bruta de la sección.

En general se considera que una estructura es traslacional si los esfuerzos en
los extremos de las columnas obtenidos mediante cálculo en segundo orden varían en
más de un 5% respecto de los obtenidos en primer orden.

Además de la inestabilidad de columnas, en hormigón puede darse el fenómeno
del pandeo lateral (EC2 -artículo 5.9-), aunque este fenómeno es más común en vigas
metálicas.

9.4. MÉTODOS APROXIMADOS DE CÁLCULO EN SEGUNDO ORDEN

El Eurocódigo 2 plantea un método general y dos métodos simplificados para
cálculo en segundo orden.

El método general está basado en el cálculo matricial no lineal (expresión
9.10). Se pueden emplear curvas tensión-deformación no-lineales de los materiales, se
tendrán en cuenta los efectos de la fluencia (ecuaciones 9.3 ó 9.4) y el efecto de la
tensorrigidez, (tratado en los capítulos 6 y 7).

Además del método general el Eurocódigo 2 plantea dos métodos
simplificados: el primero es un método basado en la rigidez nominal (también conocido
como método de los momentos mayorados) y el segundo método está basado en la
curvatura nominal (también conocido como método de la columna modelo). La figura
9.11 sintetiza ambos métodos. Para tener en cuenta la no-linealidad geométrica, el
método de los momentos mayorados mayora los momentos de primer orden mientras
que el método de la columna modelo introduce una excentricidad en relación al axil.

<!-- p. 312 -->

ANÁLISIS ESTRUCTURAL 312

NEd
M0Ed
V

h
∆

⎡ β ⎤
M 0 Ed ⎢⎣1 + ( N B / N Ed ) − 1⎥⎦ NEd
NEd
V
A
etot
V
Método general

M0Ed/NEd
e2

Método de los Método de la columna
momentos mayorados modelo

Figura 9.11. Métodos de análisis en segundo orden propuestos por el
Eurocódigo 2

<!-- p. 313 -->

HORMIGÓN ESTRUCTURAL 313
Hernández-Gil

9.4.1 Método basado en la rigidez nominal (o Método de los Momentos Mayorados
MMM)

En este método los momentos de diseño se obtienen mayorando los momentos
calculados en primer orden11:

⎡ β ⎤
M Ed = M 0 Ed 1 + (9.17) ⎢⎣ ( N b / N Ed ) − 1⎥⎦

donde M0Ed es el momento de primer orden
β factor que depende de la distribución de las leyes de momentos, tanto
de primer como de segundo orden, ver EC2 5.8.7.3. Una
aproximación razonable es considerar β=1
NEd valor de diseño de la carga axil
Nb es la carga crítica elástica de pandeo (ecuación 9.13), basada en la
rigidez nominal.

En este tipo de método se emplean valores nominales de la rigidez en todos los
elementos de la estructura, teniendo en cuenta los efectos de la fisuración, la no-

11 El MMM que propone el EC2 difiere del planteado por la ACI-318. Mientras que el
EC2 mayora los momentos de primer orden, la ACI-318 requiere dividir la estructura en
la parte traslacional y la parte no traslacional asociando a éstas momentos traslacionales
Ms y momentos no traslacionales Mns, con coeficientes de mayoración distintos.

P1 P1
V1 R1 V1+R1

P2 P2
V2 R2 V2+R2

P3 P3
V3 R3 V3+R3

Pórtico original Pórtico intraslacional Pórtico traslacional
para calcular Mns para calcular Ms

Aunque el MMM del EC2 es más fácil de emplear, el planteamiento de la ACI318 es más consecuente dado que en la simplificación adoptada para el cálculo de
longitudes de pandeo de elementos pertenecientes a estructuras porticadas éstas se han
clasificado como translacionales e intranslacionales.

<!-- p. 314 -->

ANÁLISIS ESTRUCTURAL 314

linealidad del material y la fluencia. Además se tendrá en cuenta la interacción sueloestructura cuando ésta sea relevante.

El valor de la rigidez nominal de elementos comprimidos se puede estimar a
partir de la expresión:

EI = K c E cd I c + K s E s I s (9.18)

donde Ecd es el valor de diseño del módulo de elasticidad del hormigón, que se
puede tomar como Ecm/1.2
Ic es el momento de inercia de la sección de hormigón
Es es el valor de diseño del módulo de elasticidad de la armadura
Is es el momento de inercia de la armadura respecto del cdg de la
sección de hormigón
Kc factor que tiene en cuenta los efectos de la fisuración, fluencia, etc.
Ks factor que tiene en cuenta la contribución de la armadura

Una simplificación posible, siempre que As/Ac≥0.01 es considerar Ks=0 y
Kc=0.3/(1+0.5φef).

El valor de la rigidez nominal de los elementos adyacentes a los elementos
comprimidos puede estimarse, de manera simplificada, considerando la inercia fisurada
de las secciones y el módulo efectivo del hormigón (expresión 9.3). Si no se recurre a
esta simplificación sería necesario tener en cuenta la fisuración parcial de los elementos
y el efecto de la tensorrigidez (EC2 (7.4.3)).

9.4.2 Método basado en la curvatura nominal (o Método de la columna modelo)

El método de la columna modelo es el adoptado por la EHE para el estado
límite de inestabilidad o pandeo. Como ya se ha comentado, para esbelteces mecánicas
(λ=l0/imín) menores de 35 no es necesario verificar el estado límite de inestabilidad.

En compresión simple (axil sin momento flector), la EHE obliga a que el
soporte deba resistir un momento flector mínimo, provocado por una excentricidad
mínima asociada a la incertidumbre del punto de aplicación del axil. Esta excentricidad
mínima será mayor a 2 cm y mayor a h/20, siendo h la altura del soporte. La
excentricidad estará medida en la dirección principal más desfavorable.

Como ya se vió, el hormigón a compresión (fck≤55 MPa) agota para una
deformación del 2‰. Para este nivel de deformación la tensión del acero será de
σs=fyd=0.002·Es=400 MPa. Por este motivo, la EHE obliga a que la tensión máxima de
cálculo fyd en los aceros de pilares sea de 400 MPa12.

12 Debido a esta premisa los aceros del tipo B-500 son menos rentables en pilares, ya
que se aprovecha menos su capacidad mecánica.

<!-- p. 315 -->

HORMIGÓN ESTRUCTURAL 315
Hernández-Gil
Los métodos aproximados basados en la curvatura nominal, tanto el propuesto
por el EC2 como el que propone la EHE, calculan una excentricidad total, etot.
Multiplicando esta excentricidad total por el axil se obtiene un momento de diseño MEd
que incluye: el momento de primer orden (con el efecto de las imperfecciones) y el
efecto de segundo orden (figura 9.11). Éste método está basado en la longitud efectiva
(o de pandeo) y en una estimación de la curvatura máxima. El EC2 establece:

etot = e0 + e2

multiplicando por la carga axil NEd:

M Ed = N Ed etot = N Ed e0 + N Ed e 2 ⇒ M Ed = M 0 Ed + N Ed e 2 (9.19)

donde:
e0 es la excentricidad de primer orden incluidas las imperfecciones
e2 la excentricidad debida a los efectos de segundo orden, como veremos
a continuación e2=(1/r)l02/c
NEd es el valor del esfuerzo axil de diseño
MEd es el momento de diseño teniendo en cuenta los efectos de segundo
orden
M0Ed es el momento de diseño de primer orden incluidas las imperfecciones
(M0Ed=NEde0)
1/r es la curvatura
l0 es la longitud efectiva o longitud de pandeo del elemento
c factor que depende de la distribución de la curvatura

Excentricidad de primer orden

Cuando la excentricidad en ambos extremos del pilar es la misma, entonces
e0=M0Ed/NEd. (Figura 9.12, a)

<!-- p. 316 -->

ANÁLISIS ESTRUCTURAL 316

NEd NEd NEd

e02 e02

e0

e01 e01

NEd NEd NEd

a b c

Figura 9.12. Excentricidad de primer orden

Cuando las excentricidades de primer orden son distintas en ambos extremos
(figura 9.12 b y c) el EC2 propone emplear un único momento de primer orden, M0e,
cuyo valor es:

M 0 e = 0 . 6M 02 + 0 . 4M 01 ≥ 0 . 4M 02 (9.20)

Los momentos M02 y M01 tienen el mismo signo si introducen el mismo tipo de
tensión (tracción o compresión) en la misma cara del pilar, en caso contrario los signos
serán distintos. Además se verificará que |M02| ≥ |M01|, con: M02=NEd·e02 y M01=NEd·e01
donde e01 y e02 representan las excentricidades de primer orden en los dos extremos, |e02|
≥ |e01| (figura 9.12 b y c).

<!-- p. 317 -->

HORMIGÓN ESTRUCTURAL 317
Hernández-Gil

Excentricidad debida a los efectos de segundo orden

Una columna modelo es una columna empotrada en su base y libre en cabeza.

etot
e2 NEd

y

x

L

Figura 9.13. Método de la columna modelo

Si se admite que la deformada tiene una forma senoidal, colocando los ejes x e
y tal y como se indica en la figura 9.13, la ley de la deformada de la pieza será:

⎛ πx ⎞
y ( x ) = y máx sen ⎜⎜ ⎟⎟ ⎝ l 0 ⎠

donde se cumple que para x=0 ⇒ y=0 y que para x=l0/2 ⇒ y=ymáx, siendo l0 la longitud
de pandeo (l0=2L). Derivando dos veces se tiene:

1 π2 ⎛ πx ⎞ π2
y ′′( x ) = φ( x ) = = − y máx 2 sen ⎜⎜ ⎟⎟ = − 2 y ( x ) r ( x ) l 0 ⎝ l 0 ⎠ l 0

Para x=l0/2=L, se tiene que y(L)=e2, siendo en este punto (x=L) máximos el
momento y la curvatura. Aproximando π2≈10 se obtiene:

l 02 e 2 = − φmáx
10

<!-- p. 318 -->

ANÁLISIS ESTRUCTURAL 318

El EC2 propone el siguiente valor de e2:

1 l 02 e2 = (9.21)
r c

donde: l0 es la longitud efectiva (o longitud de pandeo)
1/r es la curvatura
c es un factor que depende de la distribución de la curvatura. Para
secciones constantes c=10 (≈π2), siendo 8 un límite inferior.

Para elementos con sección transversal constante y simétrica (incluida la
armadura) se puede emplear:

1 = K r Kϕ 1 r r0
nu − n
K r = ≤ 1 (9.22)
nu − nbal
Kϕ = 1 + βϕef ≥ 1

donde Kr es un factor de corrección dependiente de la carga axil
Kφ es un factor que tiene en cuenta la fluencia
1/r0 =εyd/0.45d
εyd =fyd/Es
d es el canto útil
n =NEd /(Acfcd), fuerza axil relativa
NEd es la fuerza axil de diseño
nu =1+ω
nbal es el valor de n en el punto de máximo momento (generalmente se
produce para xlim (ver capítulo 6, figura 6.17)). Se pueden tomar
nbal=0.4.
ω =Asfyd/(Acfcd)
As es el área total de la armadura
Ac es el área de hormigón de la sección transversal
φef es el coeficiente de fluencia efectivo, dado por la expresión 9.4
β =0.35+fck/200-λ/150
λ es la esbeltez mecánica

Si la armadura no está concentrada en lados opuestos, sino que parte de ella
está colocada paralela al plano de flexión, d se define como

h
d = + si
2

donde is es el radio de giro de toda la armadura

<!-- p. 319 -->

HORMIGÓN ESTRUCTURAL 319
Hernández-Gil

Ejemplo

Consideremos la pila de un puente de sección anular representada en la figura
9.14, fabricada con hormigón C35. Las cargas de diseño a las que está sometida
consisten en una carga axil centrada de 4500 kN, una carga horizontal en cabeza de 275
kN y una carga en fuste de 9.0 kN/m. Se pide: calcular el momento máximo en segundo
orden aplicando los dos métodos propuestos por el EC2 (MMM y el método de la
columna modelo). La armadura estará formada por acero del tipo B-400-S y el
momento cuasipermanente supone el 20% del momento máximo. Se supone que la
carga actúa a los 28 días y que la humedad relativa es del 70%.

4500 kN
275 kN
Momentos de primer orden
675 kN·m
9.0 kN/m
30 m Sección A-A

A A

2.4 m
3.0 m

12975 kN·m

Figura 9.14. Pilar anular para puente

El factor de longitud de pandeo en este caso es de 2, y la longitud de pandeo es
l0=α·l=60 m. Las características mecánicas de la sección bruta y la esbeltez mecánica
de la pila son:

2 Ac = π⋅ ( rext 2 − rint 2 ) = 2 . 54 m
π 4 4 4 I c = ⋅ ( rext − rint ) = 2 . 347 m
4
l 0 l 0 λ= = = 62 . 42
i c I c
Ac

<!-- p. 320 -->

ANÁLISIS ESTRUCTURAL 320

La imperfección geométrica propuesta por el EC2 se puede tomar como
excentricidad inicial:

l 0 ei = = 150 mm
400

Con esta excentricidad inicial y para las cargas indicadas en el enunciado se
puede calcular la ley de momentos de primer orden, representada en la figura 9.14, cuyo
valor máximo, en el empotramiento, toma el valor M0Ed=12975 kN·m.

Método de los Momentos Mayorados (MMM)

Aplicando la expresión 9.17 se obtiene el momento de diseño:

⎡ β ⎤
M Ed = M 0 Ed 1 + ⎢⎣ ( N b / N Ed ) − 1⎥⎦

El coeficiente β puede tomar de manera aproximada igual a 1.0 o adoptar el
valor propuesto por el EC2 (β =π2/c0=1.03, donde c0 depende de la distribución de la
ley de momentos de primer orden y para distribución parabólica c0=9.6). Nb es la carga
de pandeo basada en la rigidez nominal. Se ha supuesto la expresión simplificada de la
rigidez nominal EI (Ks=0 y Kc=0.3/(1+0.5φef)) aplicable a cuantías geométricas
superiores a 0.01 (ρ=As/Ac≥0.01). Para el cálculo del coeficiente efectivo de fluencia
(φef) se ha empleado la expresión 9.4 y el Anejo B del EC2 (esta formulación también se
ha recogido en el capítulo 3 de este texto).

π2 EI π2 EI
N b = 2 = 2 = 45685 kN
l 0 60
EI = K c E cd I c + K s E s I s = 0 . 25E cd I c = 1 . 67·10 7 kN ·m 2
0 .3
K c = = 0 . 25 K s = 0
1 + 0 . 5ϕef
M 0 Eqp
ϕef = ϕ( ∞, t 0 ) = 1 . 780· . 20 = 0 .36
M 0 Ed
1 1 ⎛ f cm ⎞ 0. 3 1 6 kN 6 kN
E cd = E cm = 22000 ⎜ ⎟ = 34·10 2 = 28 .·410 2
1 . 2 1 . 2 ⎝ 10 ⎠ 1 . 2 m m

Conocida la carga de pandeo Nb se puede calcular el momento total de diseño en el
empotramiento (basados en cálculo aproximado de segundo orden según el MMM):

⎡ β ⎤ ⎡ 1 . 03 ⎤
M Ed = M 0 Ed ⎢⎣1 + ( N b / N Ed ) − 1⎥⎦ = 12975 ⎢⎣1 + 45685 4500 − 1⎥⎦ = 14435 kN ·m

<!-- p. 321 -->

HORMIGÓN ESTRUCTURAL 321
Hernández-Gil

Método basado en la curvatura nominal o Método de la columna modelo

Como se ha comentado en la parte teórica, este método consiste en añadir una
excentricidad para tener en cuenta los efectos de segundo orden:

M Ed = M 0 Ed + N Ed e2 = 12975 + 4500·e2 = 15334 kN·m
1 l 02 60 2 e2 = = 0.001456 = 0. 524
r c 10
1 1
\= K r Kϕ = 1.1·0.040·. 0014 = 0. 001456
r r0
Kϕ = 1 + βϕef = 1 + 0.110·.36 = 1.04 K r = 1.0
fck λ 35 62.42 β = 0. 35 + − = 0. 35 + − = 0.11
200 150 200 150
f yd
1 εyd E s 400 / 1.15 / 200000 = = = = 0.0014
r0 0. 45d 0. 45d 0. 452·.7
c = 10

\* * *

Los métodos de cálculo aproximado de segundo orden propuestos por el EC2
exigen el cálculo de la longitud de pandeo. Una ventaja muy interesante de la ACI-318
es que no requiere el cálculo de las longitudes de pandeo de tal forma que

1
M 2 orden = M1orden , no traslacion al + ⋅ M1orden , traslacion al
N Ed ⋅ ∆ ∑ 1 −
V ⋅ h

donde V es el cortante en el pilar o el cortante total por planta, ∆ es el desplazamiento
relativo del pilar o de la planta y h es la altura del pilar.

Si se tiene en cuenta que para valores pequeños de N∆/Vh se verifica que13
1/(1-N∆/Vh) ≈ 1+ N∆/Vh , la expresión anterior se puede reescribir como:

N ⋅ ∆
M 2 orden = M1orden , no traslacion al + (1 + ) ⋅ M1orden , traslacion al
V ⋅ h

13 Si a es pequeño frente a la unidad: 1/(1-a)=(1+a)/((1+a)(1-a)=(1+a)/(1-a2)≈1+a

<!-- p. 322 -->

ANÁLISIS ESTRUCTURAL 322

Como podemos ver el segundo sumando de la parte derecha de la igualdad
coincide con la última igualdad de la expresión 9.6. Los trabajos de Lai (1983)
demostraron que se puede aproximar Nb/NEd por NEd∆/Vh siempre que el factor que
mayora los momentos traslacionales sea menor de 1.5 :

Σ N b Σ N Ed ∆ ≈ ≤ 1 . 5
Σ N Ed V ·h

Para el ejemplo anterior nos queda:

⎛ N ·∆ ⎞ 45000· . 2 ⎞ M 2 orden = ⎜ 1 + ⎟M 0 Ed = ⎛+⎜ 1 ⎟12975 = 13689 kN ·m
⎝ V ·h ⎠ ⎝ 545·30 ⎠
275 ⋅ h 3 9 . 0 ⋅ h 4
∆ = + = 0 . 20 m
3EI 8EI
V = 9 . ·030 + 275 = 545 kN

La ventaja de la norma ACI-318-05 es que emplea exclusivamente datos
obtenidos del análisis de primer orden y además no es necesario el cálculo de las
longitudes de pandeo de los elementos.

<!-- p. 323 -->

HORMIGÓN ESTRUCTURAL 323
Hernández-Gil

9.5. FLEXIÓN COMPUESTA ESVIADA

Diseñar una pila a flexión compuesta esviada es complicado dado que situar la
posición de la fibra neutra en la sección transversal es una tarea difícil, como ya vimos
en el capítulo 6, figura 9.15. Además en hormigón se dimensiona generalmente en
rotura, lo que contribuye a aumentar la dificultad.

Tracciones

Fibra neutra

Compresiones

Figura 9.15. Tensiones producidas en una sección transversal debido a una
flexión compuesta esviada

Como vimos en el capítulo 6, en flexión compuesta esviada para posicionar la
fibra neutra son necesarias dos coordenadas (en lugar de una como ocurría en flexión
simple).Estas dos coordenadas son ξ y φ como se indica en la sección transversal de la
figura 9.16. Es interesante señalar que la inclinación de la fibra neutra no tiene porqué
coincidir con la inclinación del momento flector (Md).

b
Fibra neutra
y

zona traccionada
φ
h
ξ
Md Myd

Nd Mxd x

Figura 9.16. Posicionamiento de la fibra neutra en flexión compuesta esviada

<!-- p. 324 -->

ANÁLISIS ESTRUCTURAL 324

Todo el tema de dimensionamiento en flexión esviada se vio en el apartado 6.8.
Una práctica común en el caso de secciones con geometría no habitual sometidas a
flexión compuesta esviada, consiste en sustituir la sección inicial por otra inscrita en la
misma y simétrica14.

En cuanto al cálculo en segundo orden se refiere, si éste se ha realizado
mediante el método general, no será necesario realizar ninguna comprobación adicional.
En el caso de haber empleado los métodos simplificados será necesario tener en cuenta
algunas consideraciones adicionales.

La imperfección inicial sólo se tendrá en cuenta en la dirección más
desfavorable, no siendo necesario realizar ninguna comprobación adicional si se
verifican las dos condiciones siguientes (según EC2):

λy λz 1. ≤ 2 y ≤ 2
λz λy
\2. Las excentricidades relativas ey/h y ez/b satisfacen:

e y heq ez beq ≤ 0 . 2 o ≤ 0 . 2
ez beq e y heq
Donde:
b, h son el ancho y el canto de la sección
beq = i y 12 y heq = i z 12 son el ancho y el canto de una sección
rectangular equivalente
λy, λz son la esbeltez geométrica lo/i respecto a los ejes y y z respectivamente
iy, iz son los radios de giro respecto a los ejes y y z respectivamente
ez =MEdy/NEd; excentricidad según el eje z (ver figura 9.17)
ey =MEdz/NEd; excentricidad según el eje y (ver figura 9.17)
MEdy es el momento de diseño en el eje y, incluido segundo orden
MEdz es el momento de diseño en el eje z, incluido segundo orden
NEd es la fuerza axil de diseño en la combinación de carga considerada

14 De esta forma se queda del lado de la seguridad.

<!-- p. 325 -->

HORMIGÓN ESTRUCTURAL 325
Hernández-Gil

z
ey

y
b NEd

iy ez
y
iy

Nd

iz iz
h

Figura 9.17. Definición de excentricidades ey y ez.

En el caso de que las dos condiciones anteriores no se cumplieran, se puede
emplear la siguiente relación de interpolación, siempre que no se tenga ninguna
expresión más precisa:

M Edy ⎞ a ⎛ M Edz ⎞ a ⎛ 1 . 0 ⎜⎜ ⎟⎟ + ⎜⎜ ⎟⎟ ≤ ⎝ M Rdz ⎠ ⎝ M Rdy ⎠

donde:

MEdz/y es el momento de diseño en sus respectivos ejes, incluyendo efectos
de segundo orden.
MRdz/y es el momento último de la sección en su respectivo eje
a es un coeficiente de interpolación (la norma EHE toma a=1) y el EC2
toma a=2 para secciones circulares o elípticas. Para secciones
rectangulares el coeficiente a se obtiene de la siguiente tabla, en la que
se puede interpolar linealmente:

NEd/NRd 0.1 0.7 1.0
a 1.0 1.5 2.0

NEd es el valor del axil de diseño
NRd =Acfcd+Asfyd

<!-- p. 326 -->

ANÁLISIS ESTRUCTURAL 326

9.6. PILARES ZUNCHADOS

En el capítulo 3 se vio que una de las propiedades del hormigón es el efecto del
confinamiento (ver anejo del capítulo 3). Este efecto permite aumentar la resistencia a
compresión del hormigón de una pieza de hormigón armado.

Para confinar el hormigón se dispone de una hélice o una serie de cercos muy
próximos de tal forma que coarten las deformaciones transversales del hormigón que se
producen por el efecto Poisson. Al coartar la deformación aparecen tensiones radiales
de confinamiento.

En este tipo de piezas la compresión máxima permitida es mayor que en las
piezas en las que el hormigón no esté confinado. Por este motivo en las piezas de
hormigón confinado las deformaciones obtenidas en la dirección de la compresión
serán mayores.

Como regla general, los pilares zunchados no se deben usar salvo en piezas
muy cortas, sin excentricidades y sin posibilidad de pandeo. En determinadas zonas
sísmicas se recomienda zunchar los pilares, dado que proporciona un grado de
confianza adicional y representa una seguridad frente al sismo vertical. No obstante en
éste último caso el efecto del zuncho no sería tenido en cuenta en el cálculo para
acciones distintas del sismo vertical.

<!-- p. 327 -->

HORMIGÓN ESTRUCTURAL 327
Hernández-Gil

Ejercicios propuestos

\1. El pórtico de la figura inferior soporta una carga mayorada de 45 kN/m y una

45 kN/m
35×50 cm
35 kN f e

d

30×35 cm 35×35 cm 30×35 cm
3.0 m
0.30 m 0.30 m
b
a c

7.0 m 7.0 m

carga de viento colocada en el nudo f de 35 kN. Aplicando la EHE, determinar
el axil y el momento flector para los que debe de ser dimensionada la columna
a-f, considerando sólo la flexión en el plano. Para este ejercicio es necesario
emplear un programa de cálculo estructural.

\2. Aplicar el método de los momentos mayorados del EC2 y el de la ACI-318-05
para resolver el problema anterior. Hacer el cálculo aplicando el método
general (utilizar para ello un programa) y comparar los resultados.

<!-- p. 328 -->

ANÁLISIS ESTRUCTURAL 328

Referencias

Building Code Requirements for Structural Concrete (ACI 318-05) and Comentary
(ACI 318R-02). American Concrete Institute. Michigan. (Enero 2005).

Chen W.F., Sohal I. (1995). Plastic Design and Second-Order Analysis of Steel Frames.
Springer-Verlag. Nueva York.

Código modelo CEB-FIP 1990 para hormigón estructural. Colegio de Ingenieros de
Caminos, Canales y Puertos. Grupo Español del Hormigón y Asociación Técnica
Española del Pretensado.

Clough R.W. y Penzien J. (1993). Dynamics of Structures. McGraw-Hill.

Cook R.D., Malkus D.S. y Plesha M.e. (1989). Concepts and Applications of Finite
Elements Analysis. John Wiley & Sons. Nueva York.

Gil-Martín, L.M. Hernández-Montes, E. y Aschheim M. (2006). Optimal design of
planar frames based on stability criterion using first-order analysis. Engineering
Structures, 28 (13), 1780-1786.

Hernández-Montes E., Gil-Martín L.M.(1996). Análisis comparativo del cálculo de las
longitudes de pandeo según el Eurocódigo 3 y la NBE-EA-95. Hormigón y Acero.
Nº201. Septiembre 1996. Páginas 13-26.

Hernández-Montes, E., Gil-Martín, L.M. and Aschheim M. (2004). Optimal Design of
Planar Frames Based on approximate second-order analysis. Engineering Optimization,
36 (3), 281-290.

Hjelmstad, K.D. y Pezeshk, S. (1991). Optimal design of frames to resist buckling under
multiple load cases. J.Struct.Engrg., ASCE, 117(3), 914-935.

Jiménez Montoya P., García Meseguer A. y Morán Cabré F. (1994). Hormigón Armado.
Editorial Gustavo Gili. Barcelona.

Lai, S.M. y MacGregor J.G (1983). Geometric Nonlinearities in Unbraced Multistory
Frames. ASCE Structural Engineering. V.109. Nº11. Nov. 1993. 2528-2545.

Priestley, M.J.N., Park, R., and Lu, F., “Moment Curvature Relationships for
Prestressed Concrete in Constant Moment Zones”. Magazine of Concrete Research,
Vol.23, No. 75-76, June-Sept. 1971, pp. 69-78.

<!-- p. 329 -->

HORMIGÓN ESTRUCTURAL 329
Hernández-Gil

<!-- p. 330 -->

ESTADOS LÍMITE DE SERVICIO 330

Viga flectada y fisurada. Instituto Eduardo Torroja. CSIC.

<!-- p. 331 -->

HORMIGÓN ESTRUCTURAL 331
Hernández-Gil

CAPÍTULO X

ESTADOS LÍMITE DE SERVICIO

Ensayo de hormigón autocompactante. ETSICCP UGR.
Cortesía de IECA. www.ieca.es

10.1. INTRODUCCIÓN

Hasta ahora se han tratado los ELU (estados límite últimos), que son aquellos que
llevan a la ruina total o parcial de la estructura. Los Estados Límite de Servicio (ELS) son
los que originan la pérdida de funcionalidad, comodidad, durabilidad o aspecto de la
estructura. Los estados límites de servicio comprenden:

\- Deformaciones, que pueden resultar excesivas a corto o a largo plazo.

<!-- p. 332 -->

ESTADOS LÍMITE DE SERVICIO 332

\- Fisuración, producida por grietas que, además de resultar estéticamente
inadmisibles, pueden provocar la corrosión prematura de la armadura por
dejarla a la intemperie.
\- Vibraciones, que pueden causar incomodidad a los usuarios o afectar al
funcionamiento de máquinas.

Dentro del estado límite de deformaciones se contempla la posibilidad de que
flechas excesivas puedan provocar la aparición de zonas de acumulación de agua en puentes
y tejados, lo que supondría por un lado un peligro para el tráfico y por otro la introducción
de cargas adicionales no consideradas inicialmente en el cálculo. En edificios, las flechas
pueden provocar el agrietamiento de tabiquerías, azulejos y desencaje de puertas y ventanas.
Por todo lo anteriormente expuesto es necesario realizar un control de las deformaciones.

En la actualidad, el empleo de materiales con valores de tensión de rotura muy
altos, tanto en el caso de hormigones como en el de acero, hace que el estudio de los Estados
Límite de Servicio sea fundamental. Los nuevos materiales son susceptibles de presentar
grandes deformaciones o fisuraciones sin llegar a la rotura. Para entender esto consideremos
el caso concreto del acero: los aceros de alto límite elástico tienen una tensión de rotura muy
alta pero su módulo de deformación longitudinal es el mismo que el del acero de bajo límite
elástico, por lo que las deformaciones que pueden experimentar antes de presentar rotura
son mayores.

10.2. LIMITACIONES A LA DEFORMACIÓN

La forma de controlar este ELS es imponer unos límites a la deformación del
elemento estructural.

La EHE, en los comentarios al artículo 50.1, define dos tipos de flechas:

\- flecha total a tiempo infinito: aquella debida a la totalidad de las cargas desde
que comienzan a actuar, y
\- flecha activa respecto a un elemento dañable: flecha que se produce en un
elemento a partir del instante en que se construye dicho elemento.

En general se puede tomar como límite L/250 para la flecha total, donde L es la
longitud del elemento que se comprueba, y L/400 para la flecha activa. Además, para evitar
flechas en tabiquería, la flecha activa debe de ser menor de 1 cm.

10.3. DEFORMACIÓN. MÉTODO GENERAL

Generalmente, el estudio de las deformaciones se lleva a cabo a partir de la teoría
elástica lineal, o sea, se considera que la tensión es proporcional a la deformación tanto en el

<!-- p. 333 -->

HORMIGÓN ESTRUCTURAL 333
Hernández-Gil
acero como en el hormigón. La parte traccionada en el hormigón estará fisurada si sobrepasa
el momento de fisuración y no lo estará en caso contrario. Debido a que para los ELS los
coeficientes de seguridad son menores que para los ELU, es lógico emplear teoría elástica
lineal en ELS mientras que se empleará teoría de rotura en ELU.

Un elemento estructural fabricado en hormigón pretensado está sometido a dos
tipos de tensiones: unas provocadas por las cargas exteriores y otras por las acciones de
pretensado. Si el mismo elemento se fabrica en hormigón armado, las únicas tensiones a las
que estará sometido serán las correspondientes a las cargas exteriores. De hecho, la
existencia de pretensado hace que el estudio de deformaciones sea uno de los puntos en los
que existe mayor diferencia entre el hormigón armado y el hormigón pretensado.

Debido a la excentricidad del pretensado (figura 10.1) las vigas pretensadas
presentan una deformación en contraflecha cuando la carga exterior es pequeña. Esta flecha
inicial variará dependiendo del valor de la solicitación exterior y del tiempo. Cuando la
carga exterior sea suficientemente grande, la flecha será hacia abajo.

P
P

e
Deformada de la línea
media cuando se aplica P

Pe

Figura 10.1.Tendón de pretensado y diagrama de momentos flectores del
pretensado

En el diseño y dimensionamiento de elementos de hormigón es necesario calcular
las flechas finales para comprobar que éstas no exceden los límites admisibles. El
procedimiento más general para el cálculo de flechas es a partir de un análisis estructural en
segundo orden plástico mediante procedimientos paso a paso en el tiempo. Esto se lleva a
cabo integrando los diagramas momento curvatura a lo largo de la pieza. Conocida la ley de
momentos flectores es fácil obtener la ley de curvaturas e integrando esta obtener las flechas
en el elemento, en la figura 10.2 se ha esquematizado todo el proceso. Si se denomina φ0 a
la curvatura producida por el pretensado, en el diagrama M-φde la figura 10.2 el momento
M corresponde al momento exterior, supuesto aplicado el pretensado.

<!-- p. 334 -->

ESTADOS LÍMITE DE SERVICIO 334

El gran inconveniente del método general es que el módulo de deformación
longitudinal del hormigón Ecm varía con el tiempo y que el momento de inercia de la sección
I varía con la deformación. Por esto la forma más usual de proceder es determinar Ecm e I y
emplearlos en los diagramas M-φ, dado que φ=M/Ecm·I. Conocido el diagrama M-φ1 para
una sección determinada es inmediato pasar de la ley de momentos flectores a la ley de
curvaturas.

Siguiendo el proceso indicado en la figura 10.2, el cambio de ángulo entre dos
puntos de la viga se obtiene integrando la curvatura:

D dθ D x
(10.1) φ = ⎯⎯→ θC = ∫ φ dx dx xC

En el caso de la figura 10.2, donde la carga es uniforme en toda la viga, la flecha
máxima (δmáx) se produce en el centro de luz: CL. El cálculo de δmáx se puede obtener como
la distancia del punto B a la tangente trazada desde el CL de la deformada. Este
procedimiento es el mismo que el seguido en el planteamiento del segundo teorema de
Mohr (Ortiz Berrocal, 1991).

x B
B − x ) dx (10.2) δmáx = ∫ φ( x
xCL

1 Como se vio en el capítulo 5, los diagramas M-φpueden ser definidos a corto o a largo
plazo.

<!-- p. 335 -->

HORMIGÓN ESTRUCTURAL 335
Hernández-Gil

q

M

Mmax
Mcr
A B Diagrama M-Φ

Φ0
Φcr Φ
Mcr Mmax Mcr
Ley de Momentos flectores exteriores

Φ0 Φcr Ley de curvaturas

∆CL
Deformada
δmáx

Figura 10.2. Método general de cálculo de deformaciones

Para pequeñas deformaciones θ≈tan θ= dy/dx y, por tanto, integrando dos veces
la curvatura se obtiene el desplazamiento relativo entre dos puntos.

Deformaciones a corto plazo en prefisuración

En la situación de prefisuración el método general se puede aplicar directamente,
sin tener que realizar mayores simplificaciones. En prefisuración el comportamiento de los
materiales está más próximo a la teoría elástica lineal y la relación entre la curvatura y el
momento es lineal. Veamos con un ejemplo cómo tratar las deformaciones a corto plazo en
situación de prefisuración.

<!-- p. 336 -->

ESTADOS LÍMITE DE SERVICIO 336

Ejemplo

Consideremos la viga biapoyada de la figura 10.3. Se van a determinar las
deformaciones en el centro de luz en las siguientes situaciones:

\- En bancada, cuando se sueltan los cables de pretensado. La fuerza de
pretensado tiene un valor inicial de P=6800 kN.
\- Bajo una carga cuasipermanente de 31 kN/m. La fuerza de pretensado tiene un
valor de 4500 kN.

El peso propio de la viga es de 15.0 kN/m.

La ley de momentos flectores correspondiente a la carga uniformemente distribuida
q es:
q 2 M ( x ) = ( L ⋅ x − x )
2

En bancada actúan el peso propio y la fuerza de pretensado de 6800 kN. En esta
situación las leyes de momentos flectores, en kN⋅m, son las siguientes:

15 2
M pp ( x ) = ( 24 ⋅ x − x )
2
⎧ x 1700 ⋅ para 0 \< x ≤ 8 M P ( x ) = ⎪⎨ 8
⎪⎩ 1700 para 8 \< x ≤ 12

<!-- p. 337 -->

HORMIGÓN ESTRUCTURAL 337
Hernández-Gil

q 925 mm

200 mm
1000 mm

250 mm
8 m 8 m 8 m

24 m
Sección transversal
x

960 kN·m 1080 kN·m
Ley de Momentos flectores
del peso propio

Ley de Momentos flectores
\-0.25·P kN·m de la fuerza de pretensado

1984 kN·m 2232 kN·m
Ley de Momentos flectores
de la carga cuasipermanente

Figura 10.3. Viga pretensada

En todo el tramo la relación entre la curvatura y el momento es lineal: Φ=M/Ecm·I.
Tomamos Eci=28×103 N/mm2; I=0.0676 m4; A=0.61 m2. Aplicando la ecuación 10.2
tenemos:

1 8 ⎡ 15 2 x ⎤ 1 12 ⎡ 15 2 ⎤
δ = ∫ ( 24 x − x ) − 1700 x dx + ∫ ( 24 x − x ) − 1700 x dx = EI 0 ⎢⎣ 2 8 ⎥⎦ EI 8 ⎢⎣ 2 ⎥⎦
\= −0 . 02085 m

Bajo carga cuasipermanente, las ecuaciones correspondientes a las leyes de
momentos flectores de la carga y de la fuerza de pretensado, en kN⋅m, son las siguientes:

<!-- p. 338 -->

ESTADOS LÍMITE DE SERVICIO 338

31 2
M qp ( x ) = ( 24 ⋅ x − x )
2
⎧ x 1125 ⋅ para 0 \< x ≤ 8 M P ( x ) = ⎪⎨ 8
⎪⎩ 1125 para 8 \< x ≤ 12

Aplicando la ecuación 10.2, se obtiene que la deformación consiste en una flecha
hacia abajo de valor δ=0.0343 m. Este valor de la flecha supone 1/700 de luz, cumpliendo
todas las limitaciones que establece la EHE en relación a flechas.

Si se hubiese calculado la flecha a partir de la formulación correspondiente a una
viga simplemente apoyada, se habría obtenido:

5 ⋅ q ⋅ L4
δ = = 0 .071 m
384 ⋅ E ⋅ I

que supone 1/339 de la luz, valor que no cumple la limitación de flecha activa de la EHE.

Deformaciones a largo plazo en prefisuración

A largo plazo los fenónemos de fluencia y relajación hacen variar los valores de la
deformada.

Como ya vimos, los efectos de la fluencia se pueden considerar a partir del módulo
de deformación longitudinal efectivo, Ec,eff :

E c E c ,eff =
1 + ϕ

donde Ec es el módulo de deformación longitudinal instantáneo para la edad considerada, y
ϕes el coeficiente de fluencia.

Además de la fluencia también actúa la retracción. Una práctica habitual en
hormigón pretensado para tener en cuenta la retracción es de aumentar en un 20% el término
de la flecha debida a la fluencia.

<!-- p. 339 -->

HORMIGÓN ESTRUCTURAL 339
Hernández-Gil
Deformaciones a largo plazo en fisuración

Una vez que la sección ha fisurado las propiedades mecánicas cambian -momento
de inercia, área, etc.- y la sección pierde rigidez.

La deformación se calcula integrando dos veces la ecuación de la elástica:

1 d 2 y
φ= = 2 r dx

Para integrar esta ecuación es necesario establecer el valor del radio de curvatura.
En la parte no fisurada de la viga el radio de curvatura corresponde al de la sección no
fisurada. Sin embargo, en la zona fisurada el valor del radio de curvatura no corresponde al
de la sección fisurada, dado que dentro de la zona fisurada existen secciones no fisuradas
(zona entre grietas en la figura 10.10). Por este motivo el radio de curvatura en la zona
fisurada es un valor medio entre el correspondiente a la sección fisurada y al de la sección
no fisurada. El EC2 proporciona una expresión de interpolación para el cálculo del radio de
curvatura medio en la zona fisurada del elemento (ecuación 10.3).

1 1 1
\= (1 − ς) ⋅ ( ) + ς⋅ ( ) (10.3)
rm r1 r2

donde r1 y r2 son los radios de curvatura de las secciones no fisurada y fisurada,
respectivamente. El factor ζindica la proporción de sección fisurada, teniendo en cuenta las
propiedades adherentes del acero y el efecto de la duración de las cargas, siendo su valor:

⎛ σsr ⎞ 2 (10.4) ς = 1 − β1β2 ⎜⎜ ⎟⎟
⎝ σs ⎠

donde β1 vale 0.5 para barras lisas y 1 para barras de alta adherencia; β2 vale 1 para cargas
de corta duración y 0.5 para cargas de larga duración o cíclicas; σsr es la tensión del acero en
la sección fisurada para el momento crítico de fisuración y σs es la tensión del acero para la
carga cuasipermanente.

<!-- p. 340 -->

ESTADOS LÍMITE DE SERVICIO 340

Ejemplo

Sea la viga biapoyada de 10 m de luz de la figura 10.4, fabricada con hormigón HP35 y acero Y-1870-S7. La fuerza de pretensado -incluidas las pérdidas- es de 200 kN y la
carga cuasipermanente (qqp) tiene un valor de 40 kN/m -incluido el peso propio-. Las
características mecánicas de la sección bruta son las siguientes: Ac=5.00×105 mm2,
Ic=4.167×1010 mm4, Wc=8.333×107 mm3, Ap=200 mm2 y As=982 mm2. El coeficiente de
fluencia toma el valor de 2.2. Se pide: determinar la deformación a largo plazo.

500 mm
450 mm

1000 mm

10 m

Mmax =500 kNm

Figura 10.4. Viga biapoyada de 10 m de luz

El diagrama de momentos flectores correspondiente a la carga cuasipermanente,
figura 10.4, responde a la siguiente expresión – en kN⋅m- :

x 2
Mqp ( x ) = 200 ⋅ x − 40
2

A nivel sección, las deformaciones son las representadas en la figura 10.5. En esta
figura x es la profundidad de la fibra neutra, εc es la deformación en la fibra superior debido
a la flexión, εpe es la deformación en el tendón de pretensado debido a la fuerza de
pretensado y εpb es la deformación en el tendón de pretensado debido a la flexión.

<!-- p. 341 -->

HORMIGÓN ESTRUCTURAL 341
Hernández-Gil

εc

x

950 mm

εpe εpb

Figura 10.5. Deformación a nivel sección

Antes de abordar el problema es necesario calcular los siguientes datos iniciales:

200000 2
σpe = = 1000 N / mm
200
1000
εpe = = 0 . 005
200000
fctm = 0 .30 3 fck2 , j = 3 . 21 N / mm 2
E ci 8500 3 35 + 8 2 E c ,eff = = = 9306 N / mm
1 + ϕ 1 + 2 . 2

Como ya vimos, el momento de fisuración, Mfis, es aquel que produce una tracción
máxima igual a la resistencia del hormigón a tracción (fct,m). Así pues, Mfis se puede calcular
igualando la tensión en la fibra más traccionada a fct,m.

200 ⋅ 10 3 200 ⋅ 10 3 ⋅ 450 M fis ⋅ 10 6− 3 .21 = 5 + 7 − 7 → M fis = 390 .71 kN ⋅ m 5 ⋅ 10 8 .33 ⋅ 10 8 . 33 ⋅ 10

Se comprueba que el momento máximo de flexión (500 kN·m) es superior al
momento de fisuración. Del diagrama de momentos de la figura 10.4 se deduce que el
momento de fisuración se alcanza en los valores x=2.66m y x=7.34m. Para x comprendida
entre 2.66 y 7.34 el momento flector de la carga cuasipermanente es superior a Mfis. Por
tanto, para valores de x, menores de 2.66m y mayores de 7.34m la sección no está fisurada.
Para los valores intermedios, existirán secciones fisuradas y secciones no fisuradas y para el
cálculo del radio de curvatura en esta zona influirá tanto la parte fisurada como no fisurada

<!-- p. 342 -->

ESTADOS LÍMITE DE SERVICIO 342

(ecuación 10.3). En la ecuación 10.3 intervienen los radios de curvatura de la sección
fisurada y no fisurada, así como el nivel de tensión en el acero.

Para determinar el radio de curvatura de la sección fisurada es necesario conocer la
deformación a nivel sección en varios puntos y para ello hay que resolver las ecuaciones de
equilibrio de axiles y de momentos. Estas dos ecuaciones junto con la ecuación de
compatibilidad de deformaciones proporcionan un sistema no lineal de tres ecuaciones con
tres incógnitas, resoluble numéricamente. Las incógnitas son εc, εpb y x, para valores dados
de Mqp:

x
Σ N = N c + N s = 0 ⇒ − E c ,eff ⋅ εc ⋅ ⋅ 500 + 200 ⋅ E p ⋅ ( 0 .005 + εpb ) +
2
\+ 982 ⋅ E s ⋅ εpb = 0
x x
Σ M = 0 ⇒ E c ,eff ⋅ εc ⋅ ⋅ 500 ⋅ ( 950 − ) − M qp = 0
2 3
εc εpb Compatibil idad → =
x 950 − x

Posteriormente se procede a seleccionar varios puntos de la viga, cada uno de ellos
con un Mqp asociado, en los que obtener el radio de curvatura e integrando la curvatura
hallar la deformada. Con objeto de calcular el radio de curvatura medio en cada uno de estos
puntos se ha confeccionado la tabla 10.1. La fila de abscisas y la de Mqp son datos, las filas
x, εpb y εc se obtienen del sistema de ecuaciones anterior, que será necesario plantear para
cada una de las secciones consideradas. El valor de ζ se obtiene de la ecuación 10.4. Para
calcular el radio de curvatura r1, basta con tener en cuenta que:

1 M qp + M P =
r1 E c ,eff ⋅ I

siendo MP el momento de la fuerza de pretensado.

El radio de curvatura de la sección fisurada (r2), se obtiene geométricamente
analizando la sección deformada, tal y como se puede observar en la figura 10.6.

Desarrollada la tabla 10.1 se obtienen valores de rm para cada sección, a partir de
los cuales se puede integrar la ecuación diferencial de la deformada 1/rm=d2y/dx2. Como
sólo interesan los valores de la deformada en las secciones transversales elegidas, el método
más apropiado para resolver la ecuación diferencial es el método de diferencias finitas cuyo
planteamiento teórico es el siguiente:

<!-- p. 343 -->

HORMIGÓN ESTRUCTURAL 343
Hernández-Gil
y i +1 − y i y i − y i −1 −
hi +1 hi y ′′( x i ) ≈ = y i′′ para i = 2,1,.., n − 1 hi + hi +1
2
hi = x i − x i −1

Tabla 10.1. Valores y resultados en varios puntos de la viga
ZONA NO ZONA FISURADA ZONA NO
FISURADA FISURADA
Abscisas (m) 0.00 1.33 2.66 3.83 5.00 6.17 7.34 8.67 10.00
Mqp (kN·m) 0.0 230.6 390.5 472.6 500 472.6 390.5 230.6 0.0
x (m) - 407 326 312 309 312 326 407 -
εpb (×10-3) - 0.40 1.17 1.57 1.71 1.57 1.17 0.40 -
εc (×10-3) - 0.30 0.61 0.77 0.82 0.77 0.61 0.30 -
σ - 80 234 314 342 314 234 80 -
ζ - 0 0 0.44 0.53 0.44 0 0 -
1/r1(1/mm×10-7) - 0.80 3.98 6.80 7.73 6.80 3.98 0.80 -
1/r2(1/mm×10-7) - - 18.71 24.68 26.54 24.68 18.71 - -
1/rm(1/mm×10-7) - 0.80 3.98 14.67 17.70 14.67 3.98 0.80 -

r2

εc

1 εc
x = r2 x

1

Figura 10.6. Deformación a nivel sección, radio de curvatura de la sección fisurada

<!-- p. 344 -->

ESTADOS LÍMITE DE SERVICIO 344

Este método conduce a un sistema de 7 ecuaciones donde son conocidos los valores
de y’’i y los valores de y0=0 y de y8=0. Al final se obtiene un sistema lineal de 7 ecuaciones
con 7 incógnitas que, en este caso y debido a la simetría del problema, se puede transformar
en un sistema lineal de 4 ecuaciones con 4 incógnitas -bien condicionado-. Los resultados se
indican en la tabla 10.2.

Tabla 10.2. Tabla de resultados
i 0 1 2 3 4 5 6 7 8
xi (m) 0.00 1.33 2.66 3.83 5.00 6.17 7.34 8.67 10.00
hi (m) - 1.33 1.33 1.17 1.17 1.17 1.17 1.33 1.33
yi (mm) 0 4 9 12 13 12 9 4 0

Lo que supone una flecha máxima de L/769, cumpliéndose las limitaciones
impuestas por la EHE.

10.4. MÉTODO SIMPLIFICADO DE CÁLCULO DE DEFORMACIONES DE LA EHE

La EHE en el artículo 50.2.2 propone un método simplificado aplicable a vigas y a
losas de hormigón armado en flexión simple. El método simplificado establece que no será
necesaria la comprobación de las flechas cuando la relación canto/luz útil del elemento
estudiado sea igual o inferior a los valores de la tabla 10.3, que corresponden a situaciones
normales de uso en edificación y para elementos armados con acero B-500.

Tabla 10.3. Relaciones L/d en elementos estructurales de hormigón armado
sometidos a flexión simple
Elementos fuertemente Elementos débilmente
Sistema estructural armados armados
(ρ=As/b0d=0.012) (ρ=As/b0d=0.004)
Viga simplemente apoyada. Losa uni o
14 20
bidireccional simplemente apoyada
Viga continua1 en un extremo. Losa unidireccional
18 24continua1,2 en un solo lado
Viga continua1 en ambos extremos. Losa
20 30unidireccional continua1,2
Recuadros exteriores y de esquina en losa sobre
16 22apoyos aislados3
Recuadros interiores en losa sobre apoyos
17 25aislados3
Voladizo 6 9

\1. Un extremo se considera continuo si el momento correspondiente es igual o superior al 85%
del momento de empotramiento perfecto

<!-- p. 345 -->

HORMIGÓN ESTRUCTURAL 345
Hernández-Gil
\2. En losas unidireccionales, las esbelteces de la tabla 10.3 se refieren a la luz menor
\3. En losas sobre apoyos aislados (pilares) las esbelteces de la tabla 10.3 se refieren siempre a
la luz mayor

Por otro lado el método simplificado de la EHE propone que en el caso de que
fuera necesario el cálculo de la flecha, ésta se considerará compuesta por la suma de una
flecha instantánea y de una flecha diferida, esta última debida a la fluencia y retracción bajo
cargas permanentes.

Cálculo de la flecha instantánea

Para el cálculo de las flechas instantáneas en elementos de sección constante se
propone el empleo del momento de inercia equivalente (Ie), que consiste en una
interpolación entre los momentos de inercia de las secciones fisuradas y no fisuradas en
función del momento flector máximo y del momento nominal de fisuración:

3 ⎡ 3 ⎤ ⎛ M f ⎞ ⎛ M f ⎞ (10.5) I e = ⎜⎜ ⎟⎟ I b + ⎢1 − ⎜⎜ ⎟⎟ ⎥ I f ≤ I b ⎝ M a ⎠ ⎢ ⎝ M a ⎠ ⎥ ⎣ ⎦

donde:

Ma Momento flector máximo aplicado a la sección hasta el instante en que se
evalúa la flecha.
Mf Momento nominal de fisuración de la sección, obtenido como: Mf=fct,flWb.
fct,fl Resistencia a flexotracción del hormigón, que puede suponerse igual a
0.37fck,j2/3, para fct,fl y fck,j en N/mm2.
Wb Módulo resistente de la sección bruta respecto a la fibra extrema en
tracción.
Ib Momento de inercia de la sección bruta.
If Momento de inercia de la sección fisurada en flexión simple, que se
obtiene despreciando la zona de hormigón en tracción y homogeneizando
las áreas de las armaduras activas adherentes y pasivas multiplicándolas
por el coeficiente de equivalencia.

La flecha máxima de cada elemento puede obtenerse aplicando las teorías de
Resistencia de Materiales o de Análisis de Estructuras, adoptando como módulo de
deformación longitudinal del hormigón el definido por la EHE (ecuaciones 3.6 y 3.7) y
como momento de inercia -constante para toda la pieza- el valor equivalente
correspondiente a la sección de referencia, que se define como:

a) En elementos simplemente apoyados o tramos continuos: la sección central.

<!-- p. 346 -->

ESTADOS LÍMITE DE SERVICIO 346

b) En elementos en voladizo: la sección de arranque.

Cálculo de la flecha diferida

Las flechas adicionales diferidas, asociadas a cargas de larga duración, son las
producidas por las deformaciones de fluencia y retracción. La EHE propone obtener la
flecha diferida como el producto de la flecha instantánea por un factor λ, definido como:

ξ
λ=
1 + 50ρ′

donde:

ρ’ es la cuantía geométrica de la armadura a compresión A’s, referida al área
de la sección útil b0d, en la sección de referencia.

As′ ρ′ =
b0 d

ξ es un coeficiente que depende de la duración de la carga y cuyos valores
son los siguientes:

Tabla 10.4. Valores de ξ
5 o más años 2.0
1 año 1.4
6 meses 1.2
3 meses 1.0
1 mes 0.7
2 semanas 0.5

Es evidente que λestará influido por la armadura de compresión dado que cuanto
mayor sea la armadura de compresión existente en la sección menor será la fluencia de la
zona de compresiones y, por tanto, menor será la flecha diferida.

En la formulación anterior el parámetro tiempo siempre es absoluto y se mide
desde el momento de colocación del hormigón. Por tanto, para una edad j de carga y t de
cálculo de la flecha, el valor de ξpara el cálculo de λserá ξ(t)-ξ(j).

<!-- p. 347 -->

HORMIGÓN ESTRUCTURAL 347
Hernández-Gil
Ejemplo

La figura 10.7 representa el alzado y la sección transversal de una viga biapoyada.
La luz de la viga es de 16 m y la sección transversal es del tipo Π con las dimensiones
indicadas en el croquis. La armadura de la sección transversal corresponde a la sección
central.

SECCIÓN A-A
17∅16

16 m 0.22
A

0.46
A 8∅32

0.20 0.22 0.36 0.22 0.20

Figura 10.7. Viga biapoyada

Las cargas que soporta la viga son (en servicio):

• El peso propio (2500 kg/m3, artículo 10.2 de la EHE), que comienza a actuar
cuando se descimbra la estructura a los 28 días de su hormigonado.
• Carga permanente repartida de 5 kN/m, actuando sobre toda la viga. Esta carga
entra en acción pasados 3 meses desde el hormigonado de la viga.

El hormigón es del tipo HA-25/P/25/IIIa y el acero es B400S.

Se pide: estudiar la evolución de la estructura desde que se descimbra hasta la edad de un
año.

Para ello se calculará:

a) La flecha de la viga cuando se descimbra, es decir, a los 28 días del hormigonado.
b) La flecha de la viga a los tres meses, en el instante inmediatamente anterior a la
actuación de la carga permanente.
c) La flecha instantánea que produce la carga permanente.
d) La flecha de la viga al cabo de un año.

<!-- p. 348 -->

ESTADOS LÍMITE DE SERVICIO 348

Las propiedades de la sección bruta son: I= 1.79×1010 mm4, Ab= 4.66×105 mm2,
ycdg= 275.5 mm. Otras propiedades mecánicas son As= 12864 mm2, A’s= 3417 mm2,
n=Es/Ec= 7.34. El valor de la resistencia a flexotracción del hormigón es de fct,fl= 3.16
N/mm2 y, por tanto, el momento nominal de fisuración es de Mf=140 kN·m. Nada más
descimbrar la viga ésta se ve sometida a su peso propio, cuyo momento máximo es:

q ⋅ L2 2500 ⋅ 9 . 81 ⋅ 0 . 466 ⋅ 16 2
Mpp = = = 365717 N ·m = 366 kN ·m
8 8

El momento nominal de fisuración es menor que el momento máximo, por lo que
habrá zonas de la viga que estén fisuradas. Para calcular el momento de inercia equivalente
hay que aplicar la ecuación 10.5, siendo necesario determinar el momento de inercia de la
sección fisurada. Planteando equilibrio de axiles en la sección se obtiene la profundidad de
la fibra neutra (x) y, a partir de ella, el momento de inercia de la sección fisurada en flexión
simple.

Si se admite la hipótesis de distribución lineal de tensiones en el hormigón y en el
acero, la ecuación de equilibrio de axiles (con axil nulo) es equivalente a la ecuación del
momento estático, ver figura 10.8, siendo posible obtener la profundidad de la fibra neutra
de cualquiera de ambas ecuaciones. Se observa que sacando factor común la curvatura de la
ecuación del equilibrio de axiles y dividiendo por Ec ambas ecuaciones son idénticas.

De cualquiera de las ecuaciones de la figura 10.8 se obtiene x=211 mm, valor que
es menor de 220 mm, siendo válida la hipótesis de que la fibra neutra no baja de la cabeza de
la viga. Para este valor de x se calcula If, If=1.28×1010 mm4. Aplicando la ecuación 10.5 se
obtiene el valor del momento de inercia equivalente Ie=1.30×1010 mm4.

De Resistencia de Materiales se sabe que la deformación máxima de una viga
simplemente apoyada sometida a una carga uniforme es:

5 ⋅ q pp ⋅ L4
v max = = 28 mm
384 ⋅ E 28 ⋅ I e

en la ecuación anterior se ha introducido el módulo instantáneo de deformación longitudinal
secante del hormigón a los 28 días.

La flecha a los tres meses, en el instante inmediatamente anterior a la colocación de
la carga permanente, es:

<!-- p. 349 -->

HORMIGÓN ESTRUCTURAL 349
Hernández-Gil
∆ t = λ⋅ ∆ i = λ⋅ 28 .0 = 0 . 19 ⋅ 28 = 5 mm
∆ 3 meses = ∆ i + ∆ t = 28 + 5 = 33 mm
ξ( 90 ) − ξ( 28 ) 1 − 0 .7
λ= = − 2 = 0 .19 1 + 50ρ′ 1 + 50 ⋅ 1 .15 × 10
As′ 3417 − 2 ρ′ = = = 1 . 15 × 10
b0 ⋅ d 440 ⋅ 513

Para determinar la flecha instantánea que produce la carga permanente, colocada a
los tres meses, hay que calcular la flecha instantánea suma del peso propio y de la carga
permanente, y luego restar la flecha instantánea debida al peso propio (28 mm). Se calcula
así el incremento de flecha instantánea provocado por la carga permanente. Obsérvese que
al depender el momento de inercia equivalente del momento flector el problema es no lineal,
siendo necesario operar siguiendo el proceso indicado.

5 ⋅ L2
M pp + cp = 366 kN ·m + = 526 kN ·m
8

Para este valor del momento flector el valor del momento de inercia equivalente es
Ie=1.29×1010 mm4. Aplicando nociones de Resistencia de Materiales se puede obtener la
deformación máxima en una viga simplemente apoyada sometida a una carga uniforme:

5 ⋅ ( q pp + q cp ) ⋅ L4
v max = 10 = 36 mm
384 ⋅ 1 . 09 ⋅ E 28 ⋅ 1 . 29 × 10

en la expresión anterior se ha introducido el módulo instantáneo de deformación
longitudinal secante del hormigón a los 3 meses, que según el artículo 39.6 de la EHE puede
suponerse igual a 1.09·E28.

Cuando actúa la carga permanente la viga experimenta una flecha máxima de
33+(36-28)=41mm.

<!-- p. 350 -->

ESTADOS LÍMITE DE SERVICIO 350

1200 mm

70 mm
A’s x

513 mm

As

Deformaciones Tensiones
Ec·φ·x
70 mm
x Es·φ·(x-70)

513 mm

φ
Es·φ·(513-x)

Momento estático

x21200 − 3417 ⋅ (x − 70 ) + 3417 ⋅ 7 .34 ⋅ (x − 70 ) − 12864 ⋅ 7 .34 ⋅ (513 − x) = 0
2

Equilibrio de axiles
xEc ⋅ φ⋅ x ⋅ ⋅ 1200 − 3417 ⋅ Ec ⋅ φ⋅ (x − 70 ) + 3417 ⋅ Es ⋅ φ⋅ (x − 70 ) − 2
− 12864 ⋅ Es ⋅ φ⋅ (513 − x) = 0

Figura 10.8. Equivalencia entre momento estático y equilibrio de axiles

<!-- p. 351 -->

HORMIGÓN ESTRUCTURAL 351
Hernández-Gil
Al cabo de un año habrá una flecha diferida, que será distinta para cada una de las
cargas:

para el peso propio:

ξ(1año ) − ξ(1mes ) 1 .4 − 0 . 7
λ= = − 2 = 0 .44 1 + 50ρ′ 1 + 50 ⋅ 1 .15 × 10

para la carga permanente:

ξ(1año ) − ξ( 3 meses ) 1 .4 − 1
λ= = − 2 = 0 .25 1 + 50ρ′ 1 + 50 ⋅ 1 . 15 × 10

La flecha total al año será 28+0.44·28+8+0.25·8= 50 mm. La evolución de la
flecha se representa en la figura 10.9.

mm
50

40

30

20

10
meses

1 2 4 10 12

Figura 10.9. Evolución en el tiempo de la flecha máxima de la viga

La flecha en un año equivale a L/320, admisible como flecha total.

10.5. ESTADO LÍMITE DE FISURACIÓN

Las fisuras aparecen de forma inevitable en las zonas traccionadas de elementos
estructurales de hormigón. Estas fisuras deben de ser suficientemente finas como para no
provocar la corrosión del acero ni resultar estéticamente inadmisibles.

Todas las vigas de hormigón armado están fisuradas, inicialmente por retracción y
después por la flexión. La fisuración de flexión en hormigón armado es consecuencia de que

<!-- p. 352 -->

ESTADOS LÍMITE DE SERVICIO 352

el acero traccionado a fy (tensión máxima) experimentará una deformación que el hormigón
no puede desarrollar en tracción.

La anchura de fisura aceptada dependerá del ambiente donde esté situada la
estructura. La EHE (artíc. 49) propone la siguiente tabla para limitar la abertura máxima de
fisura:

Tabla 10.5. Valores máximos de abertura de fisura
Wmáx (mm) Clase de exposición
Hormigón armado Hormigón pretensado
I 0.4 0.2
IIa, IIb, H 0.3 0.21
IIIa, IIIb, IV, F 0.2
Descompresión
IIIc, Qa, Qb, Qc 0.1
1 Adicionalemente deberá comprobarse que las armaduras activas se encuentran en la zona
comprimida de la sección, bajo la combinación de acciones cuasipermanentes.

Las principales variables que afectan a la abertura de fisura son:

\- Tensión en el acero. Tal y como se acaba de ver, esta variable afectará directamente.
\- La adherencia hormigón-acero, que influirá tanto en la abertura de fisura como en la
homogeneidad en el reparto de las fisuras.
\- El recubrimiento y el diámetro de la barra. Para controlar la fisuración es preferible
disponer mayor número de barras de menor diámetro ,que menos barras y de mayor
diámetro.

Si se desprecia la deformación del hormigón en tracción la anchura de grieta dependerá
exclusivamente del alargamiento del acero, siendo la abertura de la grieta la deformación del
acero por la separación entre dos grietas (figura 10.10).

<!-- p. 353 -->

HORMIGÓN ESTRUCTURAL 353
Hernández-Gil

w
sm w = sm· εsm

σs Tensiones en el acero

Tensiones en el hormigón
a nivel del acero

Figura 10.10. Abertura de fisura y separación entre fisuras. Tensiones de tracción
en acero y hormigón

Para el cálculo de la abertura característica de fisura, la EHE propone la siguiente
expresión:

w k = β⋅ s m ⋅ εsm (10.6)

donde:

β Es el coeficiente que relaciona la abertura media de fisura con el valor
característico y cuyo valor es 1.3 para fisuración producida sólo por
acciones indirectas y 1.7 para el resto de los casos.

sm Separación media de fisuras, expresada en mm.

φ Ac ,eficaz
s m = 2c + 0 .2s + 0 . 4 k 1
As
εsm Alargamiento medio de las armaduras, teniendo en cuenta la colaboración
del hormigón entre fisuras. Como se aprecia en el diagrama de tensiones
en el acero de la figura 10.10 el alargamiento medio del acero es

<!-- p. 354 -->

ESTADOS LÍMITE DE SERVICIO 354

ligeramente menor de σs/Es. La EHE propone determinar el alargamiento
medio a partir de la expresión:

⎡ 2 ⎤ σs ⎛ σsr ⎞ σs
εsm = ⎢1 − k 2 ⎜⎜ ⎟⎟ ⎥ ≥ 0 . 4 E s ⎢ ⎝ σs ⎠ ⎥ E s ⎣ ⎦

c Recubrimiento de hormigón.
s Distancia entre barras longitudinales. Si s>15Ø se tomará s=15 Ø.
En caso de vigas armadas con n barras, se tomará s=b/n siendo b el ancho
de la viga.
k1 Coeficiente que representa la influencia del diagrama de tracciones en la
sección, de valor

ε1 + ε2 k 1 =
8ε1

donde ε1 y ε2 son las deformaciones máxima y mínima respectivamente
en la sección fisurada, en los límites de la zona traccionada (ver figura
10.11).
ε2 ε2=ε1

ε2=0

ε1 ε1 ε1

Figura 10.11. Flexión simple k1=0.125. Tracción compuesta 0.125\<k1\<0.250.
Tracción simple k1=0.250.

Ø Diámetro de la barra traccionada más gruesa o diámetro equivalente en el
caso de grupo de barras.
Ac,eficaz Área de hormigón de la zona de recubrimiento en donde las barras a
tracción influyen de forma efectiva en la abertura de las fisuras. Se define
como la zona rectangular limitada a no más de 7.5Ø al lado de cada barra,
sin superar la mitad del canto en vigas de canto, ni la cuarta parte en vigas
planas o losas. (Ver figuras 49.2.5 de la EHE).
As Sección total de las armaduras situadas en el área Ac,eficaz.

<!-- p. 355 -->

HORMIGÓN ESTRUCTURAL 355
Hernández-Gil
σs Tensión de servicio de la armadura pasiva en la hipótesis de sección
fisurada.
Es Módulo de deformación longitudinal del acero.
k2 coeficiente de valor 1.0 para los casos de carga instantánea no repetida y
0.5 para los restantes casos.
σsr Tensión de la armadura en la sección fisurada en el instante en que se
fisura el hormigón, lo cual supone que ocurre cuando la tensión de
tracción en la fibra más traccionada de hormigón alcanza el valor fct,m.

Para secciones pretensadas con armadura activa adherente y armadura pasiva el
cálculo de la abertura de fisura se realiza como si se tratase de una sección de hormigón
armado teniendo en cuenta la acción del pretensado como una acción exterior y la armadura
pasiva existente en la sección.

Como se ha comentado en capítulos anteriores, en el caso de fisuración provocada
por esfuerzo cortante y por torsión, la EHE establece unas limitaciones para la separación
entre estribos que de cumplirse se puede suponer que la fisuración está controlada.

Ejemplo

Supongamos que en el ejemplo anterior la viga está situada en un ambiente IIIa.
Para comprobar el ELS de fisuración hay que calcular la abertura característica de fisura
(ecuación 10.6) y comprobar que no es superior a la abertura máxima admisible (wmax), que
en el caso de un ambiente IIIa en hormigón armado es wmáx=0.2 mm.

En la figura 10.12 aparece un detalle de una de las almas de la viga, del que se
pueden extraer los siguientes valores:

<!-- p. 356 -->

ESTADOS LÍMITE DE SERVICIO 356

17∅16

0.22 m

7.5·∅
0.46 m

96 mm
8∅32

h/2=340 mm

263 mm
0.20 0.22 0.36 0.22 0.20

220 mm

Figura 10.12. Sección transversal y detalle del alma

c = 45 mm
s = 46 mm \< 15φ
k 1 = 0 . 125
φ= 32mm
h 2
Ac ,eficaz = ⋅ 220 = 74800 mm
2
φ Ac ,eficaz
s m = 2c + 0 .2s + 0 . 4 k1 = 118 mm
As

Una vez calculada la separación media entre fisuras se puede determinar el
alargamiento medio entre fisuras. De la figura 10.12 se deduce que h=680 mm y d=513 mm,
el valor medio de la resistencia a tracción del hormigón es fct.m=2.56 N/mm2 y el valor de
Mfis se puede despejar de la ecuación de la tensión:

M fis ⋅ ( h − y cdg ) M fis ⋅ ( 680 − 275 .5 ) 2 .56 = = 10 =→ M fis = 113 kN ⋅ m I 1 . 79 × 10

<!-- p. 357 -->

HORMIGÓN ESTRUCTURAL 357
Hernández-Gil

Los valores de σsr y de σs así como el valor de εsm , para k2=0.5, son:

113 × 10 6 ⋅ ( d − 211) 2
σsr = ⋅ n = 19 .57 N / mm
I f
526 × 10 6 ⋅ ( d − 211) 2
σs = ⋅ n = 91 . 09 N / mm
I f
⎡ 2 ⎤ σs ⎛ σsr ⎞ − 4 σs − 4
εsm = ⎢1 − k 2 ⎜⎜ ⎟⎟ ⎥ = 4 .45 × 10 ≥ 0 .4 = 1. 8 × 10 E s ⎢ ⎝ σs ⎠ ⎥ E s ⎣ ⎦

Con los datos anteriores se puede determinar la abertura de fisura a partir de la
ecuación 10.6, cuyo valor es wk=0.1 mm, menor de 0.2 mm.

10.6. ESTADO LÍMITE DE VIBRACIONES

Las vibraciones y movimentos rítmicos debidos al movimiento de las personas o al
tráfico, maquinaria, viento u oleaje, etc. pueden afectar al comportamiento en servicio de
las estructuras. Para evitar tales vibraciones habrá que proyectar las estructuras de forma que
sus frecuencias naturales de vibración estén suficientemente alejadas de las frecuencias de
las acciones. Las recomendaciones que a este respecto hace la EHE se recigen en la tabla
10.6.

Tabla 10.6. Frecuencias naturales recomendadas
Estructura Frecuencia natural (Hz)
Gimnasios o palacios de deporte > 8.0
Salas de fiesta o conciertos sin asientos > 7.0
Salas de fiesta o conciertos con asientos > 3.4
Pasarelas peatonales Quedará fuera de los
intervalos
(1.6-2.4) y (3.5-4.5)

<!-- p. 358 -->

ESTADOS LÍMITE DE SERVICIO 358

Ejercicios propuestos

\1. Calcular wk para el segundo ejemplo del apartado 10.3, que corresponde a la viga
de la figura 10.4. El cálculo de la abertura característica de fisura se realizará sin
considerar la existencia de la armadura pasiva.

\2. Rehacer el ejercicio anterior considerando la armadura pasiva que se indica en el
enunciado del ejemplo.

Referencias:

Código modelo CEB-FIP 1990 para hormigón estructural. Colegio de Ingenieros de
Caminos, Canales y Puertos. Grupo Español del Hormigón y Asociación Técnica Española
del Pretensado.

Collins M.P., Mitchell D., (1991). Prestressed Concrete Structures. Prentice Hall, Nueva
Jersey.

Hurst M.K. (1998). Prestressed Concrete Design. E & FN Spon. Nueva York.

<!-- p. 359 -->

HORMIGÓN ESTRUCTURAL 359
Hernández-Gil

CAPÍTULO XI

DISEÑO DE ELEMENTOS

Pilas de puente. N-340. Almería. España.
Cortesía de Constructora Hormigones Martínez S.A.
www.chm. es

11.1. INTRODUCCIÓN

El primer problema que se plantea a la hora de resolver una estructura, con
luces y cargas determinadas, es determinar el tipo de sección más adecuada y qué tipo
de armadura hay que emplear. Además, es necesario saber cuándo usar pretensado y
cuales deben de ser el valor de la fuerza de tesado y el trazado del cable.

<!-- p. 360 -->

DISEÑO DE ELEMENTOS 360

En hormigón armado el número de parámetros de diseño es menor que en
hormigón pretensado y, en general, la elección de los elementos es más simple.

Para vigas rectangulares de hormigón armado y, en general, para elementos de
sección rectangular sometidos a flexión simple resulta muy útil el concepto de momento
límite (§6.7, máximo momento en flexión simple que puede resistir una viga sin
armadura de compresión y con mejor aprovechamiento del acero). En base al momento
límite se pueden dimensionar el canto y ancho de estos elementos.

En otro tipo de secciones sometidas a flexión simple, como son las vigas en T y
los forjados reticulares, la limitación principal en el dimensionamiento es la cantidad de
armadura traccionada que desde el punto de vista constructivo es posible colocar..

En pilares es común disponer el área necesaria para resistir todo el axil
centrado contando exclusivamente con la resistencia de hormigón, reservando así la
flexión a la armadura.

Una vez elegida una primera sección habrá que comprobar todos los estados
límite y modificarla si es necesario.

Como ya se ha comentado, en hormigón pretensado el diseño de elementos
suele ser más complejo que en hormigón armado debido al mayor número de variables
que intervienen en el proceso.

<!-- p. 361 -->

HORMIGÓN ESTRUCTURAL 361
Hernández-Gil
Ejemplo

Determinar las dimensiones de la sección transversal –canto y ancho- de una
viga continua de 4 vanos de 13 m de luz cada uno, para una carga de diseño continua
de 4 kN/m incluido peso propio. El hormigón es del tipo HA-25 y el acero B-500-S.

Diagrama de momentos
flectores

A

13 m 13 m 13 m 13 m

h

b

Figura 11.1. Viga continua de 4 vanos

Los momentos flectores determinados a partir de un análisis lineal a 0.4, 0.5,
1.0 y 1.5 de la luz (siendo la luz de 13 metros) son:

Tabla 11.1. Momentos de la viga continua
Momento Valor
M0.4 0.0771·q·L2
M0.5 0.0714·q·L2
M1 -0.1071·q·L2
M1.5 0.0357·q·L2

Aprovechando la redistribución plástica se decide bajar el momento máximo
negativo en un 10%. Así pues el máximo momento de diseño será:

Md =- 0.9·0.1071·4·132 = - 65 kN·m.

En vigas de hormigón armado el criterio óptimo es trabajar en el plano de
rotura nº4 (§6.6) puesto que en este plano de deformación el hormigón y acero están
aprovechados al máximo. Además el Teorema de Armado a Flexión (§6.7.2) nos

<!-- p. 362 -->

DISEÑO DE ELEMENTOS 362

garantiza que dicho plano es un plano de armadura mínima. Este plano de rotura
corresponde a la profundidad de la fibra neutra xlím.

0 . 0035 ⋅ d
x lím = = 0 . 617 ⋅ d
εlím + 0 . 0035

Suponiendo que no existe armadura de compresión, el momento que resiste la
sección en el plano nº 4 (x= xlím) es:

M lím = 0 . 85 ⋅ fcd ⋅ 0 . 8 ⋅ x lím ⋅ b ⋅ ( d − 0 . 4 ⋅ x lím ) = 5 . 27 ⋅ b ⋅ d 2

Igualando el momento límite al momento máximo de diseño (65 kN·m) se
obtiene la relación que tienen que verificar b y d. Esta relación se ha representado
gráficamente en la figura 11.2.

d (mm)
500

400

300

200

100

200 250 300 350 400 450 b (mm)

Figura 11.2. Relación canto-ancho

Siguiendo este criterio iniciamos el dimensionamiento de la viga con una
sección transversal de 20×35 cm, donde se ha adoptado 5 cm como la diferencia entre
canto total (h) y canto últil (d).

11.2. EL PROCESO DE DISEÑO

Como se ha comentado en la introducción de este capítulo, el proceso de
diseño en hormigón pretensado es más complejo, debido al mayor número de variables
que intervienen: tipo de sección, dimensiones, tipo de pretensado, valor de la fuerza de
pretensado, trazado del cable, tipo de materiales, etc. El diseño del elemento estructural
tiene que garantizar que, tanto los límites de tensión como los límites de deformación no
son superados.

Tipo de sección

El primer paso es optar por un tipo u otro de sección. La figura 11.3 - adaptada
de Collins (1991) - puede resultar útil para elegir el tipo de sección más adecuado. En

<!-- p. 363 -->

HORMIGÓN ESTRUCTURAL 363
Hernández-Gil
esta figura se indica el tipo de sección aconsejado para vigas simplemente apoyadas en
función de la carga soportada y de la luz libre.

kN/m2

Cables Y 1860 S7 ∅13
1.2 m D - cable posteso existente
14 en el centro de luz
200 mm S – cable preteso
3.0 m
12 de 5S a 7S 2.4 m Hormigón HP-35
800 mm

10 de 10D a 20D 900 mm

de 10D a 18D
8
3.0 m
6
1200 mm
4 de 5S a 8S de 2S a 6D
1.2 m de 14D a 24D
2.4 m
2 300 mm
300 mm

0
5 10 15 20 25 30 35 luz (m)

Figura 11.3. Distintos tipos de secciones en función de la luz y de la carga

Una vez elegido el tipo de sección es usual seleccionar el canto de la sección a
partir de relaciones luz/canto como las indicadas en la tabla 11.2.

<!-- p. 364 -->

DISEÑO DE ELEMENTOS 364

Tabla 11.2. Relaciones luz/canto más usuales para vigas pretensadas
simplemente apoyadas
Tipo de Sobrecarga (kN/m2) Relación luz/canto
elemento

\< carga permanente 40

2.4 40-50
4.8 32-42

2.4 20-30
4.8 18-28

2.4 23-32
4.8 19-24

\< carga permanente 20

\< carga permanente 30

Vigas de carretera 18

Además de la información obtenida a partir de la figura 11.3 y de la tabla 11.2
es frecuente recurrir a catálogos de empresas de prefabricados en los que se especifica el
tipo de perfil y el rango de aplicación. En general, entre perfiles de distintas empresas
sólo existen pequeñas variaciones. Estos catálogos y manuales resultan elementos muy
útiles para la elección del tipo de sección.

Límites de tensión

La estructura pretensada pasa por diversas fases críticas a lo largo de su vida
que es preciso comprobar. El límite de tensión se clasifica como ELS, siendo
obligatorio verificar los límites de tensión en las distintas situaciones de proyecto. Las
situaciones más críticas suelen ser:

\- El instante de transferir la fuerza de tesado al hormigón ó instante inicial.
En este estado la fuerza de tesado es máxima, puesto que las pérdidas
diferidas aún no se han producido, y el hormigón es joven por lo que tiene
una resistencia mínima. En esta fase, el momento exterior es mínimo y
debido exclusivamente al peso propio.

<!-- p. 365 -->

HORMIGÓN ESTRUCTURAL 365
Hernández-Gil
\- A largo plazo se considera la actuación de las combinaciones cuasi-
permanente y rara. Para estas combinaciones la fuerza de pretensado será
mínima puesto que ya se han producido todas las pérdidas. En esta etapa la
resistencia del hormigón es máxima y las acciones exteriores son máximas
también.

En las dos situaciones críticas descritas anteriormente, el condicionante más
importante suele ser la resistencia a tracción del hormigón. La fibra más traccionada es
la fibra superior a corto plazo y la fibra inferior a largo plazo (ver figura 11.4).

Diferenciando a corto y a largo plazo aparecen las siguientes inecuaciones,
relativas a las limitaciones de tracción (ver estados de tensiones en la figura 11.4):

M mín αP0 αP0 ⋅ e + − ≥ −fct′
Z sup A Z sup
(11.1)
M máx βP0 βP0 ⋅ e − + + ≥ −fct
Z inf A Z inf

donde:
Mmín momento flector mínimo –que se presenta a corto plazoMmax momento flector máximo –que se presenta a largo plazo-
Zsup y Zinf módulos resistentes de la sección referidos a la fibra superior e
inferior, respectivamente.
αP0 y βP0 valores de la fuerza de pretensado a corto y a largo plazo (siendo α y β
los coeficientes de pérdida a corto y a largo plazo)
f’ct resistencia del hormigón a tracción a corto plazo
fct resistencia del hormigón a tracción a largo plazo

f’ct

c.d.g.

fct

Estado de Estado de
tensiones tensiones
a corto plazo a largo plazo

Figura 11.4. Estado de tensiones a corto y largo plazo.

<!-- p. 366 -->

DISEÑO DE ELEMENTOS 366

Generalmente, lo más restrictivo en vigas simplemente apoyadas suele ser la
limitación de tensión en la fibra inferior a largo plazo para la sección situada en el
centro de luz. Desde el punto de vista económico, lo más interesante es disponer la
máxima excentricidad permitida en la sección en cuestión (ver limitaciones geométricas
en §6.9) y determinar la fuerza de pretensado a partir de la segunda de las ecuaciones
11.1.

Alternativamente, para un valor determinado de la fuerza de pretensado P0 se
puede establecer una zona de cableado despejando de las inecuaciones 11.1 (ver figura
11.5).

Zona de
cableado

Zsup Mmín + Zsup ⋅ fct′
e ≤ +
A αP0
Zinf Mmáx − fct ⋅ Zinf e ≥ − +
A βP0

Figura 11.5. Zona de cableado.

Para ELS es frecuente recurrir al estado de descompresión, obligando a que
fct=f’ct= 0.

En vigas simplemente apoyadas con pretensado lineal puede darse el caso de
que los extremos estén sometidos a un momento de pretensado excesivo y a un
momento exterior muy pequeño. Con objeto de controlar la fisuración en esta situación
se coloca armadura pasiva. Además, se puede optar por una de estas dos soluciones
(figura 11.6a):

\- Eliminar la adherencia hormigón-armadura de parte de la armadura activa
en los primeros y últimos metros de la viga (figura 11.6a), reduciendo de
este modo el valor de la fuerza de pretensado, o bien
\- Reducir la excentricidad del pretensado para que produzca menor
momento de pretensado (ver figura 11.6b).

<!-- p. 367 -->

HORMIGÓN ESTRUCTURAL 367
Hernández-Gil

a. Entubado parcial b. Reducción de excentricidad

Figura 11.6. Formas de reducir la tensión en los extremos

Límites a la deflexión

En vigas, el pretensado tiende a producir una contraflecha mientras que las
cargas permanentes y las sobrecargas tienden a producir una flecha en sentido contrario.
Una práctica muy extendida es de introducir un pretensado que equilibre la flecha
generada por la combinación cuasi-permanente de cargas, lo que se consigue ajustando
apropiadamente la fuerza de pretensado y la excentricidad. Como consecuencia de esta
compensación, para la combinación cuasi-permanente, se produce una tensión uniforme
de compresión en toda la sección.

A veces el criterio de compensar las cargas cuasi-permanentes puede llevar a
unas contra-flechas excesivas en el instante de transferir la fuerza de pretensado siendo
necesario establecer otros criterios.

Las contraflechas producidas por un pretensado lineal y por un pretensado
parabólico se especifican en la figura 11.7.

1 P ⋅ e⋅ L2
∆ ∆ =
e 8 E ⋅ I
L

∆ 5 P ⋅ e⋅ L2
e ∆ = 48 E ⋅ I

Figura 11.7. Contra-flechas proporcionadas por el pretensado

<!-- p. 368 -->

DISEÑO DE ELEMENTOS 368

Cálculo en rotura

El cálculo en rotura de una sección se realiza tal y como se comentó en el
capítulo VI. Para el caso de flexión simple una forma de verificar la condición de rotura
es la de realizar equilibrio de momentos en el punto de aplicación de la resultante de
compresiones. Aproximando el brazo mecánico z por 0.9·d , queda:
M d ≤ 0 . 9 ⋅ d ⋅ ( 0 . 9 ⋅ Ap ⋅ f pd + As ⋅ f yd )

Es usual, en vigas postesas y en trazados con un punto bajo en el centro, que
las secciones críticas correspondan a las situadas a 0.4L - en vez de a 0.5L-.

11.3. SECCIONES COMPUESTAS

Gran parte de las construcciones en las que se usan técnicas de pretensado,
como los tableros de puentes, están constituidos por composición de elementos
pretensados junto a una losa de hormigón colocado in situ. En estos casos las vigas
pretensadas se diseñan para resistir su peso propio más el peso del hormigón que se
debe colocar in situ. Este hormigón in situ se coloca fresco y no tiene ninguna
capacidad resistente hasta que endurece. La sección compuesta trabaja como tal cuando
endurece el hormigón in situ, o sea, para el resto de cargas permanentes y para las
sobrecargas. Un ejemplo típico de este tipo de construcción son los puentes de vigas
pretensadas.

En elementos compuestos es necesario diferenciar entre los diferentes tipos de
situaciones por las que éste pasa.

Situación inicial (al transferir la fuerza de pretensado)

Esta situación inicial es la misma para todos los elementos pretensados: valor
máximo de la fuerza de pretensado, valor mínimo de la resistencia del hormigón y la
única acción exterior es la debida al peso propio.

La tensión en la fibra superior de la sección transversal es:

αP0 M 0 αP0 ⋅ ev σ0 ,sup = + −
Av Z v ,sup Z v ,sup

y en la fibra inferior:

αP0 M 0 αP0 ⋅ ev σ0 ,inf = − +
Av Zv ,inf Z v ,inf

<!-- p. 369 -->

HORMIGÓN ESTRUCTURAL 369
Hernández-Gil

donde Av es el área neta de la viga, M0 es el momento del peso propio, α es el
coeficiente de pérdidas a corto plazo de la fuerza de pretensado, ev es la excentricidad
de la fuerza de pretensado en la viga, y Zv,sup y Zv,inf son los módulos resistentes de la
sección referidos a la fibra superior y a la fibra inferior, respectivamente. Ver figura
11.8.

σ0,sup

yv,sup

cdgv

ev
yv,inf

σ0,inf

Figura 11.8. Situación inicial

Los valores de σ0.inf y σ0.sup deben de cumplir las limitaciones correspondientes
al hormigón, teniendo en cuenta la edad de éste.

Colocación del hormigón in situ

Generalmente la viga pretensada sirve de cimbra para la losa de hormigón
aunque esto no siempre es así. A veces se colocan cimbras para colaborar en la
resistencia en esta situación. Cuando se coloca la losa de hormigón la situación es la
siguiente: el hormigón de las vigas tendrá una resistencia mayor que la que tenía en la
situación inicial, la fuerza de pretensado tendrá mayores pérdidas estando su valor
comprendido entre αP0 y βP0 (valores a corto y largo plazo) y la acción exterior se
habrá incrementado debido al peso propio de la losa. Como simplificación se suele
emplear el valor a largo plazo de la fuerza de pretensado (βP0). En esta situación las
tensiones máximas y mínimas son:

<!-- p. 370 -->

DISEÑO DE ELEMENTOS 370

βP0 M1 βP0 ⋅ ev σ,1sup = + −
Av Zv ,sup Zv ,sup
βP0 M1 βP0 ⋅ ev σ,1inf = − +
Av Z v ,inf Zv ,inf

donde el subíndice 1 indica que corresponde al estado de colocación del hormigón in
situ.

El nuevo estado de tensiones se puede ver en la figura 11.9

Hormigón fresco

σ0,sup

yv,sup

ev
yv,inf

σ0,inf

Figura 11.9 Estado de tensiones al colocar el hormigón in situ

Situación Final

La sección compuesta quedará operativa una vez que el hormigón colocado in
situ endurezca. Las cargas aplicadas a partir de este momento serán resistidas
conjuntamente por la viga y la losa. Sin embargo, las tensiones a las que estaba
sometida la viga aislada – etapa anterior- seguirán estando presentes y por ello siempre
existirá una discontinuidad de tensiones entre ambos hormigones.

Además de lo anteriormente comentado, las secciones compuestas están
sometidas a una redistribución de tensiones debido a la fluencia y a la retracción.

En las secciones compuestas, una vez que el hormigón ha endurecido, la
discontinuidad de deformaciones en la interfase permanece constante a lo largo de la
vida del elemento. En la fase de colocación del hormigón in situ se han producido unas

<!-- p. 371 -->

HORMIGÓN ESTRUCTURAL 371
Hernández-Gil
deformaciones iniciales en el hormigón, εci (ver figura 11.10). Cuando el hormigón de la
losa ha endurecido y se carga la sección compuesta se producen deformaciones
adicionales en el hormigón, ∆εc (ver figura 11.10). Como hipótesis de trabajo se supone
que ambas deformaciones son lineales y las deformaciones totales en el hormigón se
obtienen sumando ambas:

εc = εci + ∆εc

Hormigón endurecido

εci ∆εc εc
Deformaciones Deformaciones Deformaciones
iniciales en el adicionales en el totales en el
hormigón hormigón hormigón

Figura 11.10. Estado de deformaciones

Para el diseño se suele recurrir a una simplificación en relación al
razonamiento anterior que consiste en suponer que el estado de tensiones que aparece
cuando se coloca el hormigón fresco no cambia, siendo resistidas el resto de cargas
permanentes y las sobrecargas adicionales por la sección compuesta. La distribución de
tensiones final es la suma de estos dos estados (figura 11.11).

<!-- p. 372 -->

DISEÑO DE ELEMENTOS 372

Hormigón endurecido

σci ∆σc σc
Tensiones Tensiones Tensiones
iniciales en el adicionales en totales en el
hormigón el hormigón hormigón

Figura 11.11. Estado de tensiones

Resistencia a rasante

En las secciones compuestas, la existencia de tensiones horizontales de
cortante en la interfase entre el hormigón de la viga y el de la losa juega un papel muy
importante. Para resistir este cortante suele ser necesario disponer de conectadores en
las vigas. Estos conectadores suelen formarse con la misma armadura de cortante que se
alarga hasta introducirla en la losa. La EHE (artíc. 44.2.3.5) propone el uso de métodos
plásticos para dimensionar la armadura necesaria aunque también se pueden emplear
criterios elásticos.

<!-- p. 373 -->

HORMIGÓN ESTRUCTURAL 373
Hernández-Gil
Ejemplo

Consideremos la viga biapoyada de la figura 11.12 que salva 15 m de luz. Esta
viga pertenece a una estructura de un aparcamiento, lo que supone una sobrecarga de 4
kN/m2. Además, la carga permanente se compone del peso propio más 1 cm de espesor
de aglomerado. El hormigón que se va a emplear es del tipo HP-35, que al destesar en
bancada presenta una resistencia a corto plazo de 25 N/mm2. Se pretende resolver con
una sección en Π, como la que aparece en la figura 11.12, con armadura activa del tipo
Y-1860-S7 de Ø13. En bancada la armadura activa se tesará hasta 0.75 fmáx.

2500 mm

50 mm

15 m
850 mm 1250 mm

Figura 11.12. Viga en Π

Elección del canto

El primer paso es la elección del canto, según la tabla 11.2, se puede ir a una
relación de 18, lo que supone un canto de 0.83. Optamos por un canto de 850 mm.

2500 mm

50 mm
200 mm
850 mm

100 mm

1250 mm

Figura 11.13. Características geométricas de la sección transversal

A la sección transversal de la figura 11.13 le corresponden las siguientes
propiedades mecánicas -asociadas a su sección bruta-:

Área 365000 mm2
I 2.426×1010 mm4
ycdg 275 mm
Zsup 8.813×107 mm3
Zinf 4.220×107 mm3

<!-- p. 374 -->

DISEÑO DE ELEMENTOS 374

Las cargas de servicio (no mayoradas) que actúan sobre la viga son dos cargas
permanentes y una sobrecarga, cuyos valores son:

qpp= (carga del peso propio) = 2500·0.365·9.81/1000 = 8.95 kN/m
qaglomerado = 0.01·2300·9.81/1000·2.5 = 0.56 kN/m
qsc= (sobrecarga) = 4·2.5 = 10.00 kN/m

Elección del pretensado

Tal y como se ha comentado en el apartado 11.2, lo más restrictivo en vigas
biapoyadas suele ser la limitación de tensión en la fibra inferior en el centro de luz a
largo plazo. Por este motivo se dispondrá la máxima excentricidad permitida.

El momento máximo en el centro de luz es:

q ⋅ L2 15 2 M máx = = (8 . 95 + 0 . 56 + 10 ) = 548 . 72 kN ⋅ m
8 8
15 2 M máx ,d = [1 . 35 ⋅ (8 . 95 + 0 . 56 ) + 1 . 5 ⋅ 10 ] = 782 . 96 kN ⋅ m
8

Las resistencias del hormigón a compresión y a tracción, en bancada al destesar
y a largo plazo, son:

\- A largo plazo fck = 35 N/mm2 fct = 0.21·fck 2/3 = 2.24 N/mm2
\- En bancada f’ck = 25 N/mm2 f’ct = 0.21·f’ck 2/3 = 1.80 N/mm2

Los coeficientes de pérdidas a corto y largo plazo de la fuerza de pretensado,
en vigas pretesas, se pueden tomar de la siguiente tabla:

Tabla 11.3. Valores aproximados de las pérdidas de la fuerza de pretensado
Acero Y-1860 Valor de P0 Pérdidas a corto plazo (%) Pérdidas a largo plazo (%)
Relajación normal 0.70 fmáx 10 28
Baja relajación 0.75 fmáx 8 22

La limitación de tensión a largo plazo en la fibra inferior viene dada por la
expresión:

548 . 7 × 10 6 β⋅ P0 β⋅ P0 ⋅ e − 7 + + 7 ≥ − 2 . 24 4 . 220 × 10 365000 4 . 220 × 10

<!-- p. 375 -->

HORMIGÓN ESTRUCTURAL 375
Hernández-Gil

rm=30+3.5·13=75.5 mm

Figura 11.14. Recubrimiento mecánico

Teniendo en cuenta que βP0=0.72·0.75·1860·Ap y que e=h-ycd-rm, de la fórmula
anterior se obtiene que:

e = 500 mm
Ap ≥734.5 mm2 que se consigue con 8 cordones Y-1860-S7 de 13 mm.

rm es el recubrimiento mecánico, figura 11.14.

Rotura

Para la verificación en rotura, d = 850-75.5 = 775 mm, se puede recurrir a la
aproximación comentada en el apartado 11.2:

782 . 96 × 10 6 2M d ≤ 0 . 9 ⋅ d ⋅ ( 0 . 9 ⋅ Ap ⋅ f pd ) ⇒ Ap ≥ = 771 mm
0 . 9 ⋅ 775 ⋅ 0 . 9 ⋅ 1860 / 1 . 15

que se satisface con los 8 cordones (792 mm2).

Limitación de tensión a corto plazo

A corto plazo el momento en el centro de luz es Mmín = 8.95·152/8 = 251.7
kN·m. La limitación de tensión en la fibra superior corresponde a la siguiente expresión:

251 . 7 × 10 6 α⋅ P0 α⋅ P0 ⋅ 500 7 + − 7 ≥ − 1 . 8 8 . 813 × 10 365000 8 . 813 × 10

de la que se deduce que: Ap ≤1264 mm2, que obviamente se verifica.

<!-- p. 376 -->

DISEÑO DE ELEMENTOS 376

Elección del trazado

Hasta ahora se ha fijado la excentricidad en el centro. Si este valor de la
excentricidad se continuara hasta los extremos en éstos aparecería un momento de
pretensado negativo y un momento del peso propio muy pequeño. Esto puede llevar a
que las fibras superiores agrieten por tracción. En esta viga se opta por un trazado
poligonal con objeto de logar una tensión nula.

La longitud de transmisión – calculada a partir del artículo 67.4 de la EHE- es
de 707 mm≈ 700 mm, y el momento mínimo a 700 mm del apoyo debido
exclusivamente al peso propio es Mmín = 45.28 kN·m. El límite de tensión viene dado
por:

45 . 28 × 10 6 0 . 9 ⋅ 0 . 75 ⋅ 1860 ⋅ 792 0 . 9 ⋅ 0 . 75 ⋅ 1860 ⋅ 792 ⋅ e
7 + − 7 ≥ 0 8 . 813 × 10 365000 8 . 813 × 10

de donde se deduce que e ≤287 mm.

287 mm

75.5 mm

700 mm
15 m

Figura 11.15. Elección del trazado

<!-- p. 377 -->

HORMIGÓN ESTRUCTURAL 377
Hernández-Gil

Estudio de tensiones

La última parte del problema de diseño consiste en el estudio de las tensiones
existentes a 700 mm del apoyo, a 0.4L y a 0.5L, tanto para la condición inicial como
para la condición final. Para ello se han empleado las propiedades brutas de la sección y
se ha supuesto que la fuerza de pretensado concentrada en un punto. Las tensiones, en
MPa, se resumen en la tabla inferior.

a 700 mm a 0.4 L a 0.5 L

Mmin Mmax Mmin Mmax Mmin Mmax

44.80 kN⋅m 97.67 kN⋅m 241.69 kN⋅m 526.88 kN⋅m 251.76 kN⋅m 548.8 kN⋅m

Cond. Fibra sup. -0,0056 0,5943 0,3555 3,5916 -0,0605 3,3104
Inicial
Fibra inf. 8,4252 7,1724 7,6710 0,9129 8,5398 1,5002
Cond. Fibra sup. 0,0972 0,6971 0,8329 4,0690 0,5230 3,8939
Final
Fibra inf. 6,5278 5,2751 4,9913 -1,7667 5,6386 -1,4010

Se puede observar que en la sección situada a 0.4L, las tensiones a largo plazo
en las fibras superior e inferior -para el momento máximo- son mayores que para la
sección a 0.5L

<!-- p. 378 -->

DISEÑO DE ELEMENTOS 378

Ejercicios propuestos

\1. Para el segundo ejemplo de este capítulo, correspondiente a la figura 11.12,
resolver el problema mediante un trazado horizontal.

Nota: será necesario eliminar parte de los cordones mediante la colocación de
un entubado que impida la adherencia. Se disminuye así la fuerza de
pretensado manteniendo la excentricidad.

\2. En el mismo ejemplo estudiar el Estado Último de agotamiento a flexión.

\3. En el mismo ejemplo obtener las deformaciones a corto y largo plazo.

Referencias

Código modelo CEB-FIP 1990 para hormigón estructural. Colegio de Ingenieros de
Caminos, Canales y Puertos. Grupo Español del Hormigón y Asociación Técnica
Española del Pretensado.

Collins M.P., Mitchell D., (1991). Prestressed Concrete Structures. Prentice Hall,
Nueva Jersey.

Hurst M.K. (1998). Prestressed Concrete Design. E & FN Spon. Nueva York.

Leet K. y Bernal D. (1997). Reinforced Concrete Design. McGraw-Hill.

Favre R., Jaccoud JP., Burdet O., y Charif H. (1997). Dimensionnement des Structures
en Béton. Presses Polytechniques et Universitaires Romandes.

<!-- p. 379 -->

HORMIGÓN ESTRUCTURAL 379
Hernández-Gil

CAPÍTULO XII

ESTRUCTURAS HIPERESTÁTICAS

Los Vilos-La Serena (Chile).
Cortesía de SACYR S.A. www.gruposyv.com

12.1. INTRODUCCIÓN

Calcular una estructura hiperestática resulta más complicado que calcular una
estructura isostática. En éstas últimas basta con plantear las ecuaciones de equilibrio
para obtener los diagramas de esfuerzos (axiles, cortantes, momentos flectores y
torsores). Sin embargo, la estructura hiperestática requiere además el planteamiento de
las ecuaciones de compatibilidad y de las ecuaciones de comportamiento del material.

<!-- p. 380 -->

ESTRUCTURAS HIPERESTÁTICAS 380

De ahí que en el cálculo de estructuras hiperestáticas influyan las rigideces de los
elementos y, por ende, las deformaciones que estos experimentan.

En capítulos anteriores se han tratado ampliamente estructuras isostáticas, tales
como vigas simplemente apoyadas. Sin embargo, en las estructuras hiperestáticas
aparecen dos fenómenos propios de este tipo de estructuras que es necesario considerar:

\1. La redistribución de esfuerzos
\2. La aparición de momentos secundarios

12.2. REDISTRIBUCIÓN DE ESFUERZOS

En la figura 12.1 se han representado una viga simplemente apoyada
(isostática) y una viga continua de dos vanos (hiperestática). La sección transversal de
ambas vigas es constante y tiene el mismo diagrama momento-curvatura (M-φ). Cuando
la viga simplemente apoyada alcanza el Mmáx -en el centro de la luz- se convierte en un
mecanismo y rompe. Sin embargo, cuando la viga continua de la figura 12.1 alcanza el
Mmáx -en el apoyo central-, punto 1 del diagrama M-φ, no colapsa teniendo la capacidad
de absorber incrementos adicionales de giro para Mmáx=cte –punto 2 del diagrama M-φ.
.Este fenómeno se traduce en que la viga hiperestática no sólo no se arruina cuando
alcanza el Mmáx sino que puede soportar un aumento de carga (línea discontinua del
diagrama de momentos flectores). Cuando esto ocurre se dice que se ha formado una
rótula1 en el apoyo central de la viga hiperestática.

El fenómeno por el cual se absorben incrementos de carga mediante la
formación de rótulas en estructuras hiperestáticas se denomina redistribución de
esfuerzos. Este fenómeno se presenta tanto de estructuras de hormigón armado como
pretensado (por supuesto en estructuras metálicas y mixtas).

Para la comprobación de los ELU, la EHE (artículo 21.4) permite una
redistribución de la ley de flectores de hasta un 15% del máximo momento negativo2.

1 Unos textos hablan de rótula plástica y otros de zona plástica. Ambos conceptos son
diferentes (Chen 1995).
2 Siempre que se trate de dinteles de estructuras sensiblemente intraslacionales, y
además la profundidad de la fibra neutra de la sección sobre el soporte, sometida al
momento redistribuido, sea inferior a 0.45d.

<!-- p. 381 -->

HORMIGÓN ESTRUCTURAL 381
Hernández-Gil

12.3. MOMENTOS PRIMARIOS Y MOMENTOS SECUNDARIOS

Las deformaciones que experimentan las estructuras isostáticas debido a las
acciones exteriores no influyen en la distribución de esfuerzos, tal y como se aprecia en
la viga isostática de la figura 12.1. Si esta viga isostática estuviera pretensaza, los
momentos flectores sobre la viga serían los debidos a la carga exterior más los debidos a
la fuerza de pretensado. En este caso, a los momentos flectores asociados a la fuerza de
prentensado se les denomina momentos flectores primarios de pretensado (ver figura
12.2).

q M
Mmax 1 2

A B

Mmax
Φ
Diagrama M-Φ

Ley de Momentos flectores exteriores

q

A B C

Mmax

Ley de Momentos flectores para
aumentos de carga a partir de la Ley de Momentos flectores exteriores
plastificación en B.

Figura 12.1 Isostatismo e Hiperestatismo

<!-- p. 382 -->

ESTRUCTURAS HIPERESTÁTICAS 382

q

e

P·e Ley de Momentos flectores
primarios de pretensado

Figura 12.2 Momentos flectores primarios de pretensado

Sin embargo si la estructura es hiperestática el pretensado producirá
deformaciones que pueden influir en las leyes de esfuerzos de la estructura. La fuerza de
pretensado, con excentricidad constante e, tenderá a producir una contraflecha en el
apoyo central de la viga pretensada de la figura 12.3. Para que la viga no se levante del
apoyo intermedio será necesaria la aparición de unas reacciones adicionales en los
apoyos, que modificarán las leyes de flectores y de cortantes sobre la viga. Los
momentos provocados por estas reacciones adicionales se conocen como momentos
secundarios de pretensado. Las leyes de momentos flectores secundarios tienen una
distribución lineal entre apoyos ya que están asociadas a unas reacciones localizadas en
los apoyos, ver figura 12.3.

<!-- p. 383 -->

HORMIGÓN ESTRUCTURAL 383
Hernández-Gil
deformada
e

Reacciones
adicionales R

L L

\-Pe

Ley momentos flectores
Primarios de pretensado

Ley de momentos flectores
secundarios de pretensado
RL/4

\-Pe

RL/4 - Pe Ley de momentos flectores
totales de pretensado

Figura 12.3. Momentos flectores de pretensado

Como consecuencia de la aparición de los esfuerzos secundarios la ley de
momentos flectores de pretensado será la suma de los momentos flectores primarios y
de los secundarios, tal y como se puede ver en la figura 12.3. La suma de las leyes de
momentos primarios y secundarios da lugar a la denominada ley de momentos flectores
totales de pretensado.

Se puede definir una nueva variable y de tal forma que el producto P·y sea
igual al momento flector total de pretensado (primario + secundario). La nueva variable
y define un punto de aplicación de la resultante de compresiones del tendón de
pretensado. La nueva excentricidad y (figura 12.4) se conoce como excentricidad
efectiva y, una vez conocida, es posible operar tal y como se ha hecho en vigas
isostáticas en capítulos anteriores.

<!-- p. 384 -->

ESTRUCTURAS HIPERESTÁTICAS 384

y

e

Trazado efectivo Trazado real

Figura 12.4 Trazado real y trazado efectivo

Ejemplo

Consideremos la viga continua de dos vanos pretensada de la figura 12.5. La
fuerza de pretensado es constante de valor P. La excentricidad máxima es e en el vano
de luz L y de 2e en el vano de luz 2L. Los momentos flectores primarios de pretensado
son los representados en la figura 12.5.

y

e x 2e

L 2L

Pe 2Pe

Figura 12.5. Viga pretensada y ley de momentos primarios de pretensado

En primer lugar vamos a deducir qué cargas aplicadas sobre la estructura
darían lugar a la misma ley de momentos flectores que la dibujada en la figura 12.5.
Para ello se puede operar de la siguiente forma: se libera el apoyo central y se aplican
tres cargas puntuales P1, P2 y P3, a 0.5L, L y 2L respectivamente, tal y como se indica
en la figura 12.6.

<!-- p. 385 -->

HORMIGÓN ESTRUCTURAL 385
Hernández-Gil

y
2Pe
Pe

x
P1 P2 P3

L 2L

P1
5/6 P1 1/6 P1

P2
2/3 P2 1/3 P2

P3
1/3 P3 2/3 P3

Figura 12.6. Sistema de cargas equivalentes

Para obtener el valor de las fuerzas puntuales aplicadas se impone la condición
de igualdad de momentos flectores:

M= P·e para x = 0.5L
M= 0 para x = L
M= 2Pe para x = 2L

Estas tres condiciones dan lugar a un sistema lineal de 3 ecuaciones con tres
incógnitas, de cuya resolución se obtiene:

P1 = 4Pe/L,
P2 = - 4Pe/L
P3 = 4Pe/L

A continuación se procede de la siguiente manera: se considera la viga
solicitada por las cargas P1 y P3, cuyos valores son P1 = P3 = 4Pe/L, y se calcula el
valor de la reacción ( R ) en el punto de x = L para que el desplazamiento vertical de la
viga en el apoyo central sea nulo. El valor de R distinto a P2 (-4Pe/L) debido a que la
viga de la figura 12.5 –liberado el apoyo intermedio- experimentará un desplazamiento

<!-- p. 386 -->

ESTRUCTURAS HIPERESTÁTICAS 386

provocado por la fuerza de pretensado. La reacción adicional que da lugar a los
esfuerzos secundarios será la diferencia entre R y P2.

v1

4Pe/L
R

v2

v3

4Pe/L

Figura 12.7. Desplazamientos en el apoyo central

En la figura 12.7 se representan los desplazamientos v1, v2 y v3 del punto
situado a x=L producidos por las fuerzas P1, P3 y la reacción R. Este punto corresponde
a la situación del apoyo intermedio -que se ha liberado-. Para este problema podemos
utilizar cualquier prontuario de Resistencia de Materiales y deducir los valores de los
desplazamientos:

Pe L
4 ⋅ ⋅ (3L − L ) 2 19 Pe 2 ⎤ L 2 L L2 = ⎡ (3L ) − (3L − L ) v 1 = 2 − ( ) 6 ⋅ EI ⋅ 3L ⎢⎣ 2 ⎥⎦ 18 EI
Pe
4 ⋅ L ⋅ L 14 Pe 2 L 2 2 2 v 2 = [(3L ) − (L ) − (L ) ] = L 6 ⋅ EI ⋅ 3L 9 EI
R ⋅ 2L ⋅ L 2 2 2 4 RL 2 v 3 = [(3L ) − (2L ) − (L ) ] = L 6 ⋅ EI ⋅ 3L 9 EI

Imponiendo que el desplazamiento en el apoyo sea nulo, (i.e. v1+v3=v2), se
puede deducir el valor de R :

47 Pe
R =
8 L

<!-- p. 387 -->

HORMIGÓN ESTRUCTURAL 387
Hernández-Gil

La diferencia entre el valor de R y P2 corresponde a la reacción adicional que
aparecerá en el apoyo central y que, a su vez, dará lugar a los esfuerzos secundarios de
pretensado.

47 Pe Pe 15 Pe
R secundaria = − 4 =
8 L L 8 L

Las leyes correspondientes a los esfuerzos secundarios de pretensado se
representan en la figura 12.8.

y

e x 2e

L 2L

5/4 Pe/L

5/8 Pe/L

5/4 Pe

Figura 12.8. Ley de cortantes y momentos flectores secundarios de pretensado

El proceso seguido en este ejemplo ha sido el siguiente:

\1. Cálculo de la deformación producida en una viga isostática por la fuerza de
pretensado
\2. Imposición de las limitaciones de los apoyos y determinación de las reacciones
adicionales que generan los esfuerzos secundarios de pretensado.

• • •

Otra forma de calcular P1, P2 y P3 es a partir de la proyección vertical de la
fuerza de pretensado en los puntos de variación de la pendiente, ver figura 12.9. Los

<!-- p. 388 -->

ESTRUCTURAS HIPERESTÁTICAS 388

valores de la proyección vertical de la fuerza de pretensado en el trazado de la viga son
los indicados en la figura 12.93:

L

α α

P’ P
P P

2Pe/L 2Pe/L 4Pe/L

4Pe/L
4Pe/L
L 2 L

Figura 12.9. Fuerzas verticales producidas por el pretensado poligonal

Por trigonometría se pueden obtener los valores de las cargas indicadas en la
figura 12.9:

e 2 e
tgα = = ≈ senα
L / 2 L
2Pe
P1 = P senα =
L
4Pe
P2 = 2P senα =
L

Resolviendo la estructura supuesta sometida a estas fuerzas verticales –que
introduce la fuerza de pretensado- se pueden obtener los momentos totales de
pretensado. Una vez obtenidos los momentos totales se pueden obtener los momentos
secundarios restando de los totales los momentos primarios. Éste será el razonamiento
que seguiremos en el caso de trazado parabólico, que se tratará a continuación.

Es interesante señalar que una viga con un trazado de tendón horizontal estará
sometida únicamente a un par de momentos en los extremos y un axil, tal y como se
indica en la figura 12.10.

3 En el primer apoyo: P´ y en el primer cambio de pendiente : P1 .

<!-- p. 389 -->

HORMIGÓN ESTRUCTURAL 389
Hernández-Gil

Figura 12.10. Momentos flectores ejercidos por el trazado horizontal

Cuando el trazado es parabólico la fuerza vertical que introduce el tendón de
pretensado se deduce de la figura 12.11.

ρ P dα
dα/2

dx

Figura 12.11. Equilibrio de fuerzas verticales sobre el tendón

Estableciendo el equilibrio de fuerzas verticales se tiene que:

dα dα⎫ wdx = 2Psen ≈ 2P P 2 2 ⎪⎬ ⇒ w ρ dα = P dα ⇒ w = ρ dx = ρ dα ⎪⎭
(12.1)

donde w es la proyección vertical de la fuerza distribuida, ρ es el radio de curvatura del
trazado y P es la fuerza de pretensado.

La relación entre el radio de curvatura con la geometría del trazado de
pretensado ya se vio en el apartado 4.3.

Para la viga continua de dos vanos cuyo trazado es el indicado en la figura
12.12a, el pretensado dará lugar a las fuerzas verticales que aparecen en la figura
12.12b.

<!-- p. 390 -->

ESTRUCTURAS HIPERESTÁTICAS 390

L1/10 L2/10

a

L1 L2

b

12.12. a) Viga continua de dos vanos. b) Fuerzas verticales producidas por el
pretensado

El considerar las fuerzas verticales producidas por el pretensado se debe a que
son éstas las que producen la flexión del elemento y las responsables, por tanto, de la
deformación de la viga. El efecto de los axiles se ha despreciado en el cálculo de las
deformaciones estructurales, siendo a nivel sección -como se ha visto en el capítulo VIdonde la influencia del axil de pretensado es muy importante.

<!-- p. 391 -->

HORMIGÓN ESTRUCTURAL 391
Hernández-Gil

Ejercicio

En la viga de la figura 12.13 se va a determinar la distribución de momentos de
pretensado, diferenciando entre momentos primarios y secundarios. La fuerza de
pretensado considerada es de 1500 kN. Además se determinarán las reacciones en los
apoyos producidas por el pretensado.

2.0 2.0
10.0 8.0 8.0 10.0

3
0.350

0.350 0.350
1 2

20.0 20.0

α

0.7
α

Figura 12.13. Viga continua de dos vanos

En cada vano hay tres parábolas. Mediante semejanza de triángulos se puede
calcular la ordenada máxima de cada una de las parábolas (e1, e2 y e3). Conocida la
ordenada se calcula el radio de curvatura de cada parábola y la carga uniforme que
introduce sobre la viga:

0 . 7 e 2 e 3 tgα = = =
10 8 2
L21 10 2 P 1500ρ1 = = = 142 . 86 m → w 1 = = = 10 . 50 kN / m
2 ⋅ e1 2 ⋅ 0 . 35 ρ1 142 . 86

L22 8 2ρ2 = = = 57 . 14 m → w 2 = 26 . 25 kN / m
2 ⋅ e 2 4 2 ⋅ 0 . 7
5
L23 2 2ρ2 = = = 14 . 29 m → w 3 = 104 . 97 kN / m
2 ⋅ e 3 1 2 ⋅ 0 . 7
5

<!-- p. 392 -->

ESTRUCTURAS HIPERESTÁTICAS 392

Del cálculo de la viga continua sometida a las cargas w1, w2 y w3 anteriormente
calculadas se obtienen los momentos totales de pretensado. Ver figura 12.14.

El momento primario en el apoyo central es:

M=0.35·1500=525 kN·m

y, por tanto, el momento secundario en el apoyo será 206.06 kN·m (731.06525=206.06). El trazado efectivo tendrá en el apoyo una excentricidad y, cuyo valor
viene dado por:

y = 731.06/1500 = 0.487 m

lo que constituye un incremento de 137 mm sobre el trazado real.

104.97 kN/m

26.25 kN/m 26.25 kN/m
10.50 kN/m
10.50 kN/m

\-422.00 kN·m
\-422.00 kN·m

Momentos
totales de
pretensado

731.06 kN·m

20.60 kN Momentos
secundarios
de pretensado

10.30 kN
10.30 kN 206.06 kN·m

Figura 12.14. Momentos totales y secundarios de pretensado

<!-- p. 393 -->

HORMIGÓN ESTRUCTURAL 393
Hernández-Gil

12.4. DISEÑO DEL TRAZADO DEL TENDÓN

En el capítulo anterior se trató el diseño enfocado especialmente a vigas
isostáticas. En vigas hiperestáticas el trazado más empleado es el parabólico, cuyas
características geométricas fueron tratadas en el capítulo 4.

En general se suele colocar el punto de inflexión entre parábolas a 1/10 de la
luz, como en la viga de la figura 12.12, procurando que la excentricidad sea máxima en
el punto de máximo momento.

Compensación de momentos

Consideremos el trazado parabólico de la viga isostática de la figura 12.15. La
viga está sometida a una carga exterior q uniformemente distribuida siendo la ley de
momentos flectores la que aparece en la figura 12.15. Si se resuelve el trazado mediante
una parábola se procurará que el momento de pretensado contrarreste a la ley de
momentos exteriores. Por tanto, si P es la fuerza de pretensado, la excentricidad e del
trazado será e = M/P; o lo que es lo mismo, la fuerza vertical que introduce el tendón
será igual a la carga q cambiada de signo4. Téngase en cuenta que, desde el punto de
vista de deformación vertical, es lo mismo emplear el diagrama de momentos de
pretensado que el correspondiente a las cargas verticales introducidas por éste ya que
ambos son iguales.

q

e

Trazado de pretensado

M

Momentos exteriores

Figura 12.15. Trazado parabólico en una viga isostática

4 El momento máximo en centro de vano es qL2/8, luego la excentricidad máxima es
emáx=qL2/8P, y el radio de curvatura (4.2) es:
2 L20 (L / 2 ) ρ= = 2
2e0 2qL / 8P
Se puede comprobar que aplicando la expresión 12.1 se obtiene w=P/ρ=q.

<!-- p. 394 -->

ESTRUCTURAS HIPERESTÁTICAS 394

Así pues, el trazado parabólico introduce una fuerza continua opuesta a la
acción exterior q, puesto que no se producen esfuerzos secundarios. La ley de
momentos flectores de la carga vertical de pretensado será igual a la ley de momentos
primarios P·e. Ver figura 12.16. A este trazado, obtenido de compensar directamente la
ley de flectores, se le denomina trazado concordante.

Diagrama de
Momentos flectores

Trazado
concordante

Figura 12.16. Trazado concordante de pretensado.

Obviamente, cuando no existen esfuerzos secundarios, los trazados real y
efectivo de pretensado coinciden.

El trazado que se indica en la figura 12.16 no se puede materializar en vigas
hiperestáticas dado que los trazados parabólicos tienen que ser del tipo de los que
aparecen en las figuras 12.12 y 12.13. Sin embargo, suele ser habitual comenzar el
primer tanteo partiendo del diagrama de momentos de las acciones exteriores,
procurando que en los puntos de apoyo el radio sea mínimo.

Transformación lineal

Anteriormente se ha visto que el trazado efectivo se obtenía a partir del trazado
real modificándolo en función de los valores de los momentos secundarios. En general,
se mantenía la forma del trazado ajustándola en los apoyos de manera que el resto del
trazado experimentaba una variación lineal en función de la distancia al apoyo en el que
realiza el ajuste y del valor de éste.

<!-- p. 395 -->

HORMIGÓN ESTRUCTURAL 395
Hernández-Gil
Consideremos una aproximación rectilínea del trazado para el problema
correspondiente a la figura 12.13, (figura 12.17a) y una transformación lineal del
trazado ajustada al apoyo central, figura 12.17b.

0.350 m

a

0.350 m 0.350 m

52.5 kN 210.0 kN 52.5 kN

157.5 kN 157.5 kN

0.550 m

b

0.250 m 0.250 m

37.5 kN 240.0 kN 37.5 kN

157.5 kN 157.5 kN

Figura 12.17. Transformación lineal

En las figuras 12.17a y b se han representado, además de los trazados, las
cargas verticales equivalentes. Se aprecia que estas cargas equivalentes son distintas en
los apoyos de las vigas 12.17a y b e iguales en el interior de los vanos. Puesto que las
cargas en el interior de los vanos son las mismas en las dos vigas los momentos totales
de pretensado serán idénticos aunque aisladamente no coincidan los momentos
primarios y secundarios. Sin embargo, tal y como se ha visto en el apartado 12.3, los
momentos totales son los únicos que intervienen en la definición del trazado efectivo5.

5 ó línea de presiones en el hormigón.

<!-- p. 396 -->

ESTRUCTURAS HIPERESTÁTICAS 396

Si no se aproxima el curvo por uno rectilíneo esto no sería totalmente cierto
puesto que el punto de inflexión habría variado ligeramente. Si embargo, este hecho no
se suele tener en cuenta. Así pues, se puede concluir que las transformaciones lineales
del trazado de pretensado no modifican los momentos totales de pretensado. Esta
propiedad es muy útil para la modificación de trazados con objeto de verificar las
limitaciones de tensiones, ya tratadas en el capítulo anterior.

<!-- p. 397 -->

HORMIGÓN ESTRUCTURAL 397
Hernández-Gil
Referencias

Building Code Requirements for Structural Concrete (ACI 318-05) and Comentary
(ACI 318R-02). American Concrete Institute. Michigan. (Enero 2005).

Chen W.F., Sohal I. (1995). Plastic Design and Second-Order Analysis of Steel Frames.
Springer-Verlag. Nueva York.

Código modelo CEB-FIP 1990 para hormigón estructural. Colegio de Ingenieros de
Caminos, Canales y Puertos. Grupo Español del Hormigón y Asociación Técnica
Española del Pretensado.

Clough R.W. y Penzien J. (1993). Dynamics of Structures. McGraw-Hill.

Cook R.D., Malkus D.S. y Plesha M.e. (1989). Concepts and Applications of Finite
Elements Analysis. John Wiley & Sons. Nueva York.

<!-- p. 398 -->

ESTRUCTURAS HIPERESTÁTICAS 398

<!-- p. 399 -->

HORMIGÓN ESTRUCTURAL 399
Hernández-Gil

Tabla de secciones en cm2 y pesos (cualquier tipo de acero)

Diámetro Peso Número de barras
Ø (mm) (kg/m) 1 2 3 4 5 6 7 8 9
5 0,15 0,20 0,39 0,59 0,79 0,98 1,18 1,37 1,57 1,77
6 0,22 0,28 0,57 0,85 1,13 1,41 1,70 1,98 2,26 2,54
8 0,4 0,50 1,01 1,51 2,01 2,51 3,02 3,52 4,02 4,52
10 0,62 0,79 1,57 2,36 3,14 3,93 4,71 5,50 6,28 7,07
12 0,89 1,13 2,26 3,39 4,52 5,65 6,79 7,92 9,05 10,18
14 1,21 1,54 3,08 4,62 6,16 7,70 9,24 10,78 12,32 13,85
16 1,58 2,01 4,02 6,03 8,04 10,05 12,06 14,07 16,08 18,10
20 2,47 3,14 6,28 9,42 12,57 15,71 18,85 21,99 25,13 28,27
25 3,85 4,91 9,82 14,73 19,63 24,54 29,45 34,36 39,27 44,18
32 6,31 8,04 16,08 24,13 32,17 40,21 48,25 56,30 64,34 72,38
40 9,87 12,57 25,13 37,70 50,27 62,83 75,40 87,96 100,53 113,10

<!-- p. 400 -->



<!-- p. 401 -->



<!-- p. 402 -->


