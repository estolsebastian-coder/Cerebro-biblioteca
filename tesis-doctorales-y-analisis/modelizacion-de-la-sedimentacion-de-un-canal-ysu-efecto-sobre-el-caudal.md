---
type: libro
title: "Modelización de la sedimentación de un canal ysu efecto sobre el caudal"
author: ""
categoria: "Tesis doctorales y análisis"
paginas: 11
extraccion: "texto"
fuente: "local:E:/Biblioteca digital/Tesis doctorales y análisis/Modelización de la sedimentación de un canal ysu efecto sobre el caudal.pdf"
convertido: 2026-10-16
---

# Modelización de la sedimentación de un canal ysu efecto sobre el caudal

> Texto extraído de `Tesis doctorales y análisis\Modelización de la sedimentación de un canal ysu efecto sobre el caudal.pdf` (11 páginas, texto). El PDF original está en el disco E: (Biblioteca digital); `<!-- p. N -->` marca el inicio de cada página.

<!-- p. 1 -->

Modelling in Science Education and Learning MSEL Volume 19 , 2026 doi: 10.4995/msel.2026.26712.
in Science Education and Learning
Instituto Universitario de Matemática Pura y Aplicada
Universitat Politècnica de València Modelling

Modelización de la sedimentación de un canal y
su efecto sobre el caudal
Modelling sedimentation in a channel

Denís Gómez-Taylor OliverLearning Universitat Politècnica de València
and dgomoli@cam.upv.es

Abstract

La modelización matemática constituye una herramienta fundamental tanto para el análisis de proble-
mas reales de ingeniería como para la formación de futuros ingenieros y matemáticos. En este trabajoEducation se desarrolla un modelo matemático que describe la evolución temporal de la sedimentación en un canal
abierto y su influencia sobre el caudal transportado. En primer lugar, se plantea un modelo simplificado
basado en una ecuación diferencial ordinaria con solución analítica, que permite estudiar el crecimiento
de los sedimentos a lo largo del tiempo. Posteriormente, se propone un modelo más realista medianteScience la incorporación de la ecuación de Manning, haciendo que el caudal dependa de la rugosidad, el área
in hidráulica y el radio hidráulico, todos ellos variables con el proceso de sedimentación. Debido a la ausen-
cia de una solución analítica cerrada, este segundo modelo se resuelve mediante el método numérico de
Runge-Kutta de cuarto orden. Además de su interés desde el punto de vista de la ingeniería hidráulica,
el trabajo pretende servir como recurso docente para introducir actividades de modelización en el aula,
integrando conceptos de ecuaciones diferenciales, hidráulica y métodos numéricos dentro de un problema http://polipapers.upv.es/index.php/MSEL real de ingeniería.Modelling
Mathematical modeling is an essential tool not only for analyzing real engineering problems but also for
educating future engineers and mathematicians. This work presents a mathematical model describing the
temporal evolution of sediment accumulation in an open channel and its effect on flow capacity. A sim-
plified model based on an ordinary differential equation with an analytical solution is first introduced to
describe sediment growth over time. A more realistic formulation is then developed by incorporating Man-
ning’s equation, allowing the flow rate to depend on hydraulic roughness, wetted area, and hydraulic radius,
all of which evolve as sediment accumulates. Since this model has no closed-form analytical solution, it is
solved numerically using the fourth-order Runge-Kutta method. Beyond its hydraulic engineering applica-
tions, the proposed model is intended as an educational resource for introducing mathematical modeling
activities in the classroom, integrating concepts from differential equations, hydraulics, and numerical
methods through the study of a realistic engineering problem.

Palabras clave: Modelización matemática, sedimentación, canales hidráulicos, ecuaciones diferenciales, ecuación
de Manning, método de Runge-Kutta, innovación docente.
Keywords: Mathematical modeling, channel sedimentation, hydraulic engineering, ordinary differential equations,
Manning’s equation, Runge-Kutta method, engineering education.

73

<!-- p. 2 -->

Modelización de la sedimentación de un canal
74 D. Gómez-Taylor Oliver

\1. Introducción

El desarrollo de la ingeniería moderna está estrechamente ligado al empleo de modelos matemáticos capaces
de describir, predecir y analizar el comportamiento de sistemas físicos complejos. Desde el diseño de estructu-
ras hasta la simulación de flujos hidráulicos, el estudio del transporte de contaminantes o la planificación de
infraestructuras, las matemáticas constituyen una herramienta esencial para comprender fenómenos reales y
apoyar la toma de decisiones técnicas. En este contexto, disciplinas como las ecuaciones diferenciales, el análisis
numérico, la estadística o la optimización permiten representar procesos que, en muchas ocasiones, resultarían
imposibles o excesivamente costosos de estudiar únicamente mediante experimentación directa (White, F. M.
(2011); Chow, V. T., 1959).

En particular, la modelización matemática ocupa un lugar central dentro de la formación de los futuros
ingenieros y matemáticos, ya que constituye el puente entre el conocimiento teórico adquirido en las asignaturas
básicas y su aplicación práctica a problemas reales (Calabuig Rodríguez, J. M., et al., 2015, Blum, W., & Leiß,
D., 2007).
Sin embargo, a pesar de la importancia que posee la modelización dentro del mundo profesional, una parte
significativa del alumnado universitario continúa percibiendo las asignaturas matemáticas como excesivamente
teóricas, abstractas y alejadas de la realidad. Con frecuencia, los problemas planteados en materias como Ecua-
ciones Diferenciales, Análisis Numérico o Modelización Matemática se presentan mediante ejercicios idealizadosLearning cuyo objetivo principal consiste en aplicar una determinada técnica de resolución, sin mostrar claramente el
and fenómenoestudiantesfísicoadquierenque representandestreza enni lala utilidadresoluciónprácticade procedimientosde los resultadosmatemáticos,obtenidos. peroComoencuentranconsecuencia,dificultadesmuchos
para comprender cómo dichas herramientas se emplean posteriormente en el ámbito profesional de la ingeniería
real (Sánchez-Pérez, E. A., García-Raffi, L. M., & Sánchez-Pérez, J. V., 1999).

Diversos trabajos desarrollados durante las últimas décadas han puesto de manifiesto la necesidad de in-Education troducir actividades de modelización contextualizadas dentro de la enseñanza universitaria, especialmente en
titulaciones científico-técnicas. En este sentido, diferentes investigaciones en didáctica de las matemáticas han
mostrado que la resolución de problemas abiertos favorece simultáneamente el desarrollo del razonamiento ma-
temático, la interpretación física de los resultados, la capacidad de validación del modelo y la comunicaciónScience científica (Sánchez-Pérez, E. A., García-Raffi, L. M., & Sánchez-Pérez, J. V., 1999, Gallart Palau, C., Ferrando
Palomares, I., & García-Raffi, L. M. 2015a y 2015b, Blum, W., & Leiß, D., 2007).in

En este contexto se sitúa el presente documento. Se propone el desarrollo de un modelo matemático capaz
de describir la evolución temporal de la sedimentación en un canal y analizar cómo dicha acumulación de se-
dimentos afecta progresivamente al caudal transportado. La pérdida de capacidad hidráulica provocada por la http://polipapers.upv.es/index.php/MSEL deposición de limos, arenas y otros materiales constituye uno de los principales problemas de mantenimientoModelling
en canales de riego, conducciones abiertas y cauces naturales, ya que reduce la eficiencia hidráulica de la in-
fraestructura y puede incrementar significativamente el riesgo de desbordamientos durante episodios de lluvias
intensas (Chow, V. T. ,1959 White, F. M., 2011).

El interés por este problema ha adquirido una especial relevancia tras los efectos producidos por la DANA
que afectó a la Comunidad Valenciana en octubre de 2024. Aunque la acumulación de sedimentos representa
únicamente uno de los numerosos factores que intervienen en este tipo de fenómenos hidrológicos extremos,
los acontecimientos ocurridos pusieron de manifiesto la importancia del correcto mantenimiento de cauces y
canales, así como la necesidad de disponer de herramientas objetivas que permitan analizar su evolución y
anticipar posibles pérdidas de capacidad hidráulica. En este sentido, la modelización matemática constituye un
instrumento especialmente útil para estudiar la influencia de distintos parámetros sobre la evolución del sistema
sin necesidad de intervenir directamente sobre la infraestructura.

El objetivo principal de este trabajo consiste en desarrollar un modelo matemático de complejidad creciente
que permita describir la evolución de la sedimentación en un canal abierto a lo largo del tiempo. En una prime-
ra aproximación se plantea un modelo sencillo basado en una ecuación diferencial ordinaria resoluble mediante
separación de variables, lo que permite obtener una primera estimación analítica del fenómeno. Posteriormente,
el modelo se amplía incorporando conceptos propios de la hidráulica de canales abiertos mediante la ecuación
de Manning (Çengel, Y. A., & Cimbala, J. M., 2014) , relacionando la acumulación de sedimentos con la dismi-
nución progresiva del caudal transportado (Chow, V. T. ,1959). Dado que la formulación resultante no admite

ISSN 1988-3145 @MSEL

<!-- p. 3 -->

Volume 19 , doi: 10.4995/msel.2026.26712. 75

una solución analítica cerrada, su resolución se aborda mediante el método numérico de Runge-Kutta de cuarto
orden.

Con esta propuesta se pretende mostrar cómo un problema de ingeniería relativamente sencillo puede conver-
tirse en un contexto adecuado para integrar conocimientos de matemáticas, hidráulica y simulación numérica,
poniendo de manifiesto el papel de la modelización matemática como herramienta de conexión entre la formación
universitaria y la práctica profesional. De este modo, el trabajo no solo proporciona un modelo para estudiar un
fenómeno hidráulico concreto, sino que también ilustra el proceso mediante el cual las matemáticas permiten
analizar, comprender y predecir el comportamiento de sistemas reales de interés ingenieril.

\2. Planteamiento básico

Asumiremos que el canal transporta agua desde una fuente estable como un embalse o una estación de
bombeo, hasta un destino agrícola, industrial o natural. A lo largo del tiempo, el fondo del canal se eleva
progresivamente debido a la sedimentación de materiales arrastrados por el propio flujo (limos, arenas u otras
partículas), lo que se traduce en una pérdida funcional de su sección hidráulica.
Comenzaremos con un modelo sencillo, en el que el agua que pasa por el canal siempre está a un nivel,Learning independientemente de la cantidad de sedimento que haya en el fondo, por lo que cuanto más haya menos agua
and pasarásedimentaciónpor el canaldel canal.(White,ConformeF. M.,se2011).acumulaSe tratamás volumende describirde sedimentoel efecto queS(t) tiene(en m2)el pasoen eldelfondotiempodel canal,en la
Education de sección con área Amax, menos volumen tiene el agua para pasar y por ende menos caudal pasa.
Science
in http://polipapers.upv.es/index.php/MSELModelling

Figura 1: Sección del canal

@MSEL ISSN 1988-3145

<!-- p. 4 -->

Modelización de la sedimentación de un canal
76 D. Gómez-Taylor Oliver

Learning
and
Figura 2: Dibujo representativo del canal con agua y sedimento

El canal a modelizar es de sección cuadrada 10 × 10 m, con un área inicial A0 = 100 m2 y un perímetroEducation mojado P0 = 30 m, se puede obsevar en la Figura 1.
En forma discreta se podría describir esta relación como:

S(tn) = S(tn−1) + k · Vaguat,Science
in Siendo:
Vaguat = Amax −S(tn−1),

Entonces es: http://polipapers.upv.es/index.php/MSEL S(tn) = S(tn−1) + k · (Amax −S(tn−1)),Modelling
Que se podría describir como “la cantidad de sedimento en un instante tn es igual a la cantidad de sedimento
que había en el instante tn−1 más una concentración, k, de sedimentos del agua que pasa en ese momento t (que
es el nuevo sedimento). Esta ecuación se podría reordenar a:

S(tn) −S(tn−1) = k · (Amax −S(tn−1)),

Y se puede describir como:
S(t + ∆t) −S(t)
l´ım = k · Am´ax −S(t)
∆t→0 ∆t

y tenemos esta ecuación diferencial, continua:

dS
\= k · (Am´ax −S(t)),
dt

donde k es un coeficiente de sedimentación. Representa la fracción de sedimento transportado por el agua que
acaba depositándose en el canal en cada unidad de tiempo. Es un valor empírico que depende de la pendiente,
la velocidad del agua, el tipo de partículas y el mantenimiento del cauce. Si k es grande, el canal se colmata
muy rápido porque la mayor parte de los sedimentos en suspensión se depositan. Si k es pequeño, el canal se
colmata lentamente, ya que la mayor parte de las partículas siguen en movimiento y no llegan a asentarse.

ISSN 1988-3145 @MSEL

<!-- p. 5 -->

Volume 19 , doi: 10.4995/msel.2026.26712. 77

Valor típico de k Descripción

0.001 Río de montaña. Gran velocidad y poco sedimento
0.01 Río medio. Como el Ebro.
0.02 Poca velocidad y mucho sedimento.
0.05 Gran río turbulento. Como el Ganges.

Tabla 1: Distintos contextos con distintas ks

\3. Resolución básica

Para resolver la ecuación diferencial se usará el método de separación de variables:

dS
\= k dt
Am´ax −S(t)

Se integra:
Z dS Z
\= k dt
Am´ax −S(t)Learning Que es:
Am´ax −S(t) = k t + Cand −ln
Despejando:
S(t) = Am´ax −Ce−kt

Asumiendo que Amax = 100m2 y que k = 0, 01 (un 1 % del canal se acumula de sedimento tras el paso temporal)
y por ende C = 100, se tendría la gráfica en la Figura 3, con el periodo de tiempo siendo 30 años, con pasoEducation temporal de un año. La solución es:
Science S(t) = Am´ax −Am´axe−kt.
in http://polipapers.upv.es/index.php/MSELModelling

Figura 3: Sedimento acumulado.

@MSEL ISSN 1988-3145

<!-- p. 6 -->

Modelización de la sedimentación de un canal
78 D. Gómez-Taylor Oliver

Después de 30 años, según este modelo, en S(30), se tendría un 25′9182 % del canal lleno de sedimentos. Es
decir, pasaría un 74′0818 % del caudal que pasaba al principio.
Usando otras ks de otros casos, se obtienen la gráfica de la Figura 6 con todos los casos mencionados.

Learning
and
Education

Figura 4: Sedimento acumulado con distintas ks.Science
in
\4. Planteamiento complejo

En este ejemplo más complejo se asumirá que mientras se van acumulando sedimentos en el canal, su eficiencia http://polipapers.upv.es/index.php/MSEL hidráulica se reduce debido a una disminución en área, un aumento de rugosidad, un aumento de perímetroModelling mojado y por ende una disminución de radio hidráulico. Y como menos caudal pasa, menos sedimentos se
depositan, decelerando su colmatación.
Se introduce ahora la fórmula de Manning:

1
Q = nAR2/3S1/2,

Donde:
Q = caudal (m3/s), es decir, el volumen de agua que pasa por la sección en un segundo.
n = coeficiente de rugosidad de Manning (s/m1/3), un valor empírico que mide cuán rugosas son las paredes
del canal (a mayor rugosidad, más resistencia al paso del agua).
A = área hidráulica mojada (m2), la parte de la sección del canal realmente ocupada por agua.
R = A/P = radio hidráulico (m), una forma de medir la “eficiencia” de la sección para conducir agua, donde P
\= perímetro mojado (m), es decir, la longitud del contorno de la sección que está en contacto con el agua.
S = pendiente de la línea de energía (pendiente del canal)

Diremos que n(S) = n0(1 + µS), es decir, la rugosidad del canal depende de la cantidad de sedimento
acumulado ya que cuanto más sedimento se acumula más rugoso se vuelve linealmente. Siendo n0 la rugosidad
base del canal cuando está limpio y µ el coeficiente de aumento de rugosidad por unidad de sedimento acumulado.
Diremos también que A(S) = A0 −S, el área hidráulica mojada también dependerá de la cantidad de sedimento
acumulado, siendo A0 es área hidráulica inicial y S el área de la sección cubierta por sedimentos.

ISSN 1988-3145 @MSEL

<!-- p. 7 -->

Volume 19 , doi: 10.4995/msel.2026.26712. 79

Diremos también que P(S) = P0−βS, el perímetro mojado depende la cantidad de sedimento acumulado. Siendo
P0 el perímetro mojado inicial del canal y β es el coeficiente de pérdida de perímetro mojado dependiendo de
los sedimentos acumulados. Esto hace que la ecuación general sea la siguiente:

2
1 A0 −αS 3
Q(S) = · (A0 −αS) · · S1/2
n0 (1 + µS) P0 + βS

La ecuación de evolución es:
dS
\= k(Am´ax −S)Q(S).
dt

Al no existir solución analítica cerrada, se resuelve con Runge-Kutta de cuarto orden (RK4) con paso mensual
durante 30 años.

\5. Resolución compleja

Usando los siguientes parámetros:
Rugosidad inicial n0 = 0.015 (canal relativamente liso de hormigón), Coeficiente de aumento de la rugosidad
µ = 0, 08 y pérdida de perímetro β = 0.2 simulando un aumento progresivo de la resistencia hidráulica,Learning
Dimensiones antes usadas A0 = 100m2, P0 = 30m y pendiente suave S = 0, 002. Se obtiene la gráfica en la
Figura 5 representando el caudal conforme se acumula el sedimento.and
Education
Science
in http://polipapers.upv.es/index.php/MSELModelling

Figura 5: Caudal.

Lo que representa que conforme se va acumulando sedimento en el canal el caudal cae, y conforme se acumula
más el caudal cae a menor ritmo.
El objetivo ahora es resolver una ecuación diferencial dS/dt que incluya esta caída en caudal como influencia en
la deposición de nuevos sedimentos, es decir, cuanto menos caudal pasa menos sedimentos se depositan, pero
esta vez teniendo en cuenta rugosidad, área hidráulica, perímetro mojado y pendiente (que será constante).

dS
\= k Am´ax −S(t) Q(S)
dt

@MSEL ISSN 1988-3145

<!-- p. 8 -->

Modelización de la sedimentación de un canal
80 D. Gómez-Taylor Oliver

Esta ecuación diferencial es separable, así que se puede obtener la solución implícita.

dS
\= k dt
Am´ax −S(t) Q(S)

Y se integra desde t = 0 hasta t, y desde S0 hasta S(t).

Z S(t) dξ Z t
\= k dt
S0 Am´ax −ξ Q(ξ) 0

Que es la solución implícita de S(t). dS/dt = f(t, S) indica la pendiente instantánea de la curva S(t). Al no
existir una fórmula exacta para S(t) se aproximarán sus valores paso a paso mediante Runge-Kutta (RK4). En
cada intervalo de tiempo calcula varias pendientes intermedias de S(t) mediante la fórmula de su derivada y las
combina para estimar con precisión el siguiente valor de S. Repitiendo se construye la trayectoria de S(t).
Usando paso de h = 1/12 (mensual) durante t = 30 años, se parte de t0 = 0 y S0 = S(0), y se usan los datos
antes expuestos junto con el coeficiente de sedimentación global k = 0, 001 (valor apreciable para observar el
cambio en varias décadas, modificable al tomar mediciones) y Amax = 100, y se define

f(t, S) = k Am´ax −S(t) Q(S)Learning Siguiendo Runge Kutta se calculan
and k1 = f(t0, S0),

k2 = f t0 + h2 , S0 + h2 k1 = f t0 + 24,1 S0 + k124 ,

k3 = f t0 + h2 , S0 + h2 k2 = f t0 + 24,1 S0 + k224 ,Education 1 k3
k4 = f(t0 + h, S0 + h k3) = f t0 + 12, S0 + 12 .

Entonces
S1 = S0 + h6 k1 + 2k2 + 2k3 + k4 = S0 + 721 k1 + 2k2 + 2k3 + k4Science
Usando el paso mencionado hasta 30 años se consigue una serie de valores que formarán la Cuadro de Valores
in
2 y gráfica en la Figura 6.

Año Sedimento ( %) Caudal ( %)

0 0.0 100.0 http://polipapers.upv.es/index.php/MSELModelling 5 47.20 52.80
10 58.39 41.61
20 68.72 31.28
30 74.06 25.94

Tabla 2: Evolución del sedimento y caudal a lo largo del tiempo.

Donde se puede observar que a los 10 años el nivel de sedimento llega casi al 60 %. Evidentemente esto es
un modelo idealizado de sedimentación, sin contar las partículas en suspensión, calidad del agua o procesos de
lavado. Además, en el inicio el caudal es inmenso ya que no existe casi impedimento por lo que el crecimiento
de sedimentos en los primeros 2 años es muy rápido.

Usando, como antes, distintas ks se obtienen los resultados de la Figura 7.

\6. Conclusiones

Este proyecto presentado surge de una experiencia en la que el autor formaba parte de un grupo de estu-
diantes de dobles titulaciones de matemáticas y diversas ingenierías cuyo objetivo era introducir la modelización
matemática como una competencia transversal dentro de la formación universitaria, bajo la dirección del pro-
fesor Luis Miguel García-Raffi. El trabajo desarrollado por los estudiantes en este grupo ha sido de carácter

ISSN 1988-3145 @MSEL

<!-- p. 9 -->

Volume 19 , doi: 10.4995/msel.2026.26712. 81

Learning
and

Figura 6: Sedimentos con RK.Education
Science
in http://polipapers.upv.es/index.php/MSELModelling

Figura 7: Sedimentos con RK con distintas ks.

altruista y motivado por el interés de profundizar en la conexión entre las Matemáticas y la realidad mediante
el estudio de problemas de ingeniería susceptibles de ser modelizados. El presente documento constituye uno

@MSEL ISSN 1988-3145

<!-- p. 10 -->

Modelización de la sedimentación de un canal
82 D. Gómez-Taylor Oliver

de los materiales elaborados en dicho contexto, con la intención de que pueda servir como recurso para otras
personas interesados en incorporar actividades de modelización en el aula.
Este trabajo pone de manifiesto el potencial didáctico de las actividades de modelización matemática contex-
tualizadas en problemas reales de ingeniería para la formación de estudiantes de dobles grados en matemáticas
e ingeniería. En este caso, el estudio de la sedimentación en un canal abierto constituye un ejemplo especial-
mente adecuado, ya que integra de manera natural contenidos de ecuaciones diferenciales, hidráulica y análisis
numérico que habitualmente aparecen distribuidos entre distintas asignaturas del currículo.
Desde el punto de vista matemático, el proyecto permite recorrer de forma completa el ciclo de modelización:
a partir de un fenómeno físico real se identifican las variables relevantes, se establecen hipótesis simplificado-
ras, se formulan las ecuaciones que describen el proceso y se analizan las limitaciones del modelo obtenido.
La evolución desde un modelo analítico sencillo hasta otro más completo, basado en la ecuación de Manning
y resuelto mediante el método de Runge-Kutta de cuarto orden, muestra cómo la incorporación progresiva de
nuevos fenómenos físicos permite obtener representaciones más realistas del comportamiento del sistema.
Este aspecto resulta especialmente relevante en el contexto de los dobles grados, donde con frecuencia el alum-
nado percibe las matemáticas avanzadas como excesivamente abstractas o alejadas de las aplicaciones ingenie-
riles. Actividades como la presentada permiten mostrar que herramientas como las ecuaciones diferenciales, los
métodos numéricos o la simulación no constituyen únicamente procedimientos matemáticos aislados, sino ins-
trumentos fundamentales para analizar, comprender y predecir el comportamiento de sistemas físicos complejos
cuya resolución analítica exacta resulta, en muchas ocasiones, imposible o excesivamente costosa.Learning Asimismo, el carácter abierto del problema obliga al estudiante a adoptar un papel activo durante todo el proand cesoanalizarde modelización.críticamente lasLa limitacionesnecesidad dedelseleccionarmodelo favorecehipótesis,el interpretardesarrollo deparámetroscompetenciasfísicos,comovalidarel razonamientoresultados y
matemático, el pensamiento crítico y la capacidad para integrar conocimientos procedentes de distintas disci-
plinas. Al mismo tiempo, la naturaleza modular del modelo facilita su ampliación mediante la incorporación de
nuevos procesos físicos, como fenómenos de erosión, episodios de limpieza del cauce, transporte de sedimentos
o datos hidrológicos reales.Education Estos resultados muestran que el modelo básico predice un colmatación del canal suave y progresiva, llegando
al 25 % en 30 años, mientras que el modelo complejo, usando efectos hidráulicos más avanzados refleja una
dinámica más realista y veloz, con una acumulación de sedimentos fuerte en los primeros años, debido al gran
caudal, y una ralentización progresiva, lo que muestra la importancia de considerar factores hidráulicos másScience realistas. No obstante, se tiene que subrayar las limitaciones que hay en estos modelos, como transporte de
in partículas en suspensión o episodios de crecida que puedan limpiar o colmatar aún más el canal. Se asume una
pendiente constante y no se consideran tareas de dragado o limpieza artificial periódicas. Por ello, los resultados
obtenidos han de entenderse como una aproximación idealizada que representa tendencias generales, pero no
exactas en un canal real, donde los parámetros se medirían antes de modelizar.
En conjunto, los resultados obtenidos refuerzan la idea de que la modelización matemática constituye una me- http://polipapers.upv.es/index.php/MSEL todología especialmente adecuada para la formación de estudiantes de Matemáticas e Ingeniería. No solo facilitaModelling
la integración de conocimientos procedentes de distintas disciplinas, sino que también aproxima al estudiantado
a la forma en que los modelos matemáticos se desarrollan y utilizan en la práctica profesional para comprender,
simular y apoyar la toma de decisiones en problemas reales de ingeniería hidráulica. Esto formará a los ingenie-
rios del futuro, interesados por su entorno y como explicarlo. La cualidad más importante de un ingeniero es el
saber tomar decisiones y este tipo de ejercicios fomentan esa actividad.

ISSN 1988-3145 @MSEL

<!-- p. 11 -->

Volume 19 , doi: 10.4995/msel.2026.26712. 83

Referencias

Blum, W., & Leiß, D. (2007).
How do students and teachers deal with modelling problems?
En C. Haines, P. Galbraith, W. Blum, & S. Khan (Eds.),
Mathematical Modelling: Education, Engineering and Economics, pp. 222–231.
Horwood Publishing
doi:10.1533/9780857099419.5.222

Calabuig Rodríguez, J. M., Ferrando Palomares, I., Gallart Palau, C.,
García Raffi, L. M., Hurtado Soler, A., & Sierra Galdón, L. (2015).
La modelización como competencia transversal en el sistema educativo español.
UNO. Revista de Didáctica de las Matemáticas, 69, 44–51.

Çengel, Y. A., & Cimbala, J. M. (2014).
Mecánica de fluidos: Fundamentos y aplicaciones.
McGraw-Hill (3.ª edición)

Gallart Palau, C., Ferrando, I., & García-Raffi, L. M. (2015a).
Análisis competencial de una tarea de modelización abierta.Learning
Números. Revista de Didáctica de las Matemáticas, 88, 93–103.
and
Gallart Palau, C., Ferrando Palomares, I., & García-Raffi, L. M. (2015b).
El profesor ante la actividad modelizadora en el aula de secundaria.
SUMA, 79, 9–16.

Sánchez-Pérez, E. A., García-Raffi, L. M., & Sánchez-Pérez, J. V. (1999).Education Introducción de las técnicas de modelización para el estudio de la física
y de las matemáticas en los primeros cursos de las carreras técnicas.
Enseñanza de las Ciencias, 17(1), 119–129.Science White, F. M. (2011).
in Mecánica de fluidos.
McGraw-Hill/Interamericana (7.ª edición) http://polipapers.upv.es/index.php/MSELModelling

@MSEL ISSN 1988-3145
