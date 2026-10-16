---
type: libro
title: "Precisiones para el empleo del método del módulo de balasto en edificación"
author: "M. J. Freiré Tellado"
categoria: "Arquitectura"
paginas: 13
extraccion: "texto"
fuente: "local:E:/Biblioteca digital/Arquitectura/Método de Winkler.pdf"
convertido: 2026-10-15
---

# Precisiones para el empleo del método del módulo de balasto en edificación

> Texto extraído de `Arquitectura/Método de Winkler.pdf` (13 páginas, texto). El PDF original está en el disco E: (Biblioteca digital); `<!-- p. N -->` marca el inicio de cada página.

<!-- p. 1 -->

PRECISIONES PARA EL EMPLEO DEL MÉTODO DEL
MÓDULO DE BALASTO EN EDIFICACIÓN

(RECOMMENDATIONS FOR THE USE OF THE COEFFICIENT OF SUBGRADE REACTION)

Manuel J. Freiré Tellado, Arquitecto
Dpto. de Tecnología de la Construcción. Univ. de A Coruña
Fecha de recepción: 29-VII-99
ESPAÑA 480-4

RESUMEN SUMMARY

Actualmente las herramientas informáticas permiten el It has only been recently that computers were
cálculo conjunto de la estructura y cimentación, lo que available to analyze the combined of structure and
introduce un mayor grado de precisión en el dimensionado foundation, introducing more accuracy in structural
de ambas. Obviamente, esta técnica implica la modelización analysis. Obviously, this technique involves the soil
del terreno como requisito sine qua non, modelización que modelling as necessary. The model of the coefficient of
frecuentemente ha sido resuelta recurriendo al método del subgrade reaction has been often used for this task.
módulo de balasto.

En última instancia, la precisión del modelo de cálculo asi At last, the accuracy of the model depends on the
generado va a depender del ajuste entre el comportamiento agreement between predictions and soil behavior. The
del terreno real y el representado por el modelo. El empleo appropriate use of Winkler theory and the suitable
del modelo dentro de sus límites de aplicación, así como la determination ofk are essential conditions for a good
caracterización del suelo mediante un valor del módulo de analysis.
balasto apropiado, son condiciones prioritarias para un
cálculo correcto.

Desgraciadamente, pese a su trascendencia, el problema no Unfortunately, manuals are not sufficiently concerned
recibe un tratamiento adecuado en los manuales. Este texto with this problem. The limits of this theory, some
pasa revista a los condicionantes del método, recoge formulations for the determination of the k values and
diversas formulaciones para la determinación del módulo a a few improvements of the model are described in this
emplear en función del tipo de terreno y de cimiento y paper.
reseña varias correcciones que diversos autores han
propuesto para mejorar el modelo.

CONDICIONES DE BORDE DE LAS mucho tiempo se han aplicado unas simplificaciones de
ESTRUCTURAS DE EDIFICACIÓN. LOS las condiciones de contomo radicales y sólo recientemen-
CIMIENTOS Y EL TERRENO. te se ha empezado a recoger algunas modelizaciones del
terreno, si bien normalmente limitadas a ciertos tipos
Toda estructura está, en último término, soportada singulares de cimientos, como losas o vigas flotantes.
exclusivamente por el suelo. Este aserto, tan sencillo
como obvio, ha sido olvidado durante mucho tiempo en el Así,fi*entea métodos de análisis de la superestructura muy
campo del análisis de estructuras de edificación: durante sofisticados -matriciales 3D, elementos finitos, cálculos

(c) Consejo Superior de Investigaciones Científicas http://informesdelaconstruccion.revistas.csic.es
Licencia Creative Commons 3.0 España (by-nc)

<!-- p. 2 -->

24
Informes de la Construcción, Vol. 51 rf 463, septiembre/octubre 1999

en teoría de segundo orden- en los que se analizan -de una parte se continúan calculando los esfuerzos a que
numerosos efectos secundarios, se efectúa -en el ámbito éstas se encuentran sometidas como si se tratase de
de la edificación comercial- una simplificación sólidos rígidos, sólidos rígidos que provocan un reparto
sorprendente al suponer que la estructura e stá empotra- lineal de las tensiones de respuesta del terreno, sólo
da -o articulada- en su enlace con la cimentación. Ello posible si se considera la cimentación como infinitaequivale a despreciar tanto la deformabilidad de la mente rígida [1]. Es esto una carga heredada de épocas
cimentación como el efecto de la compresibilidad del pasadas, por cuanto las estructuras de cimentación son hoy
suelo y, por tanto, de los asientos de la edificación y a la mayormente flexibles, habiendo disminuido mucho
repercusión que este concepto tendrá en las leyes de asimismo la rigidez de la superestructura, consecuencia
esfuerzos resultantes. del incremento de luces y disminución de secciones de las
piezas [2].
El planteamiento anterior hunde sus raíces en tiem-
\-por otro lado, las estructuras de cimentaciónpos pasados, con limitados recursos de cálculo,
fundamentalmente manuales, en los que sólo un análisis superficiales -zapatas- se suelen estudiar como pie-
zas aisladas, ignorando que la mayoría de las veces sepor partes de la estructura hacía factible su tratamiento.
encuentran enlazadas con nervios con otras partes de laPese a la reconocida validez de esta técnica -con una
cimentación, formando verdaderas 'zapatas combinadassanción práctica evidente-, y dados los recursos de cálculo
de geometría varíable'.disponibles hoy en día, resulta defendible la tesis del
estudio conjunto de la estructura, cimentación y terreno,
\-el comportamiento no lineal y dependiente del tiempoque explicite las interacciones de las distintas partes: los
del terreno complica aún más el análisis de éstas -se hanlogros exponenciales de la informática hacen hoy facti-
hecho intentos de considerar la respuesta temporal a partirble abordar el tratamiento analítico global del conjunto
de la Teoría de Consolidación de Terzaghi [3] -.estructura-cimiento-suelo. Es más, la modelización de
parte del terreno de cimentación es norma usual en el Obviamente, la bondad del tratamiento de estos elementosestudio de presas y grandes obras de ingenieria. recae en una modelización del suelo adecuada,
convirtiéndose ésta en el primer problema a resolver.
El interés de tratamientos de este estilo va más allá del Los programas a los que se ha hecho referencia
campo meramente teórico: ya nos advirtieron algunos anteriormente resuelven la modelización mediante el
investigadores sobre la dificultad conceptual de admitir empleo del Método del Módulo de Balasto o de Winkler,
las condiciones de borde referidas cuando se cuantifican método que, además de su sencillez, cuenta con aval
los desplazamientos y giros que se producen en las piezas experimental referido al conjunto edificio-cimentacióncon las distintas condiciones de borde -empotramiento, terreno aunque, lamentablemente, aún bastante reducido.
articulación, apoyos deslizantes- de los apoyos y la Presenta, además, la ventaja fundamental de su fácil
dificultad de garantizar que las deformaciones que implementación informática: caracteriza el terreno
significarían el cambio de las condiciones de borde no se exclusivamente por el valor de un parámetro, el módulo de
produzcan en la cimentación construida, garantizando así balasto, dependiente del tipo de terreno, pero independiente
la validez de las hipótesis de cálculo supuestas. de la formulación que permite su obtención.

Problema relevante, por cuanto asientos y rotaciones de Lógicamente, este tratamiento del terreno puede plan-
la cimentación provocan serias variaciones en las leyes tear cierta discusión: es un método que no se ajusta a la
generales de esfuerzos de la estructura, significativamen- realidad, con problemas de todos conocidos -que luego
te en la redistribución de los esfuerzos flectores y axiles se revisarán-; pero es cierto también que, en el ámbito del
de pilares. Por fortuna, ciertos programas comerciales de estudio, métodos más precisos como el modelo
cálculo de estructuras muy sofisticados incluyen entre sus hiperbólico -elástico no lineal- no aportan mayor preci-
opciones la posibilidad de modelización del terreno y del sión en los resultados. Esto es así por cuanto que, en
cimiento, analizado como placa sobre apoyos elásticos, edificación convencional, las tensiones transmitidas al
solución que permite resolver con corrección, tanto el terreno no son altas: los coeficientes de seguridad
dimensionado de estos elementos, como las leyes de usualmente empleados en cimentaciones se traducen en
esfuerzos de la estructura, traduciéndose en un tensiones que rara vez superan el tercio de la carga de
significativo incremento de la precisión analítica y hundimiento del terreno -ya que la tensión admisible
conceptual del modelo. engloba ese doble factor de seguridad suficientefirentea
hundimiento yfirentea asientos excesivos- por lo que los
El segundo aspecto que justifica la modelización del cimientos se encuentran en la parte baja de la rama
cimiento y del terreno es, tal y como se ha avanzado en el tensión/deformación, que es en todos los modelos
párrafo anterior, el del dimensionado de las estructuras de propuestos bien una recta o bien sustituible por una rec-
cimentación: ta sin error apreciable. En palabras de Jiménez Salas [4].

(c) Consejo Superior de Investigaciones Científicas http://informesdelaconstruccion.revistas.csic.es
Licencia Creative Commons 3.0 España (by-nc)

<!-- p. 3 -->

25
Informes de la Construcción, Vol. 51 n° 463, septiembre/octubre 1999

\-Sin embargo, en muchos suelos, antes de llegar a este EVALUACIÓN DE LOS COEFICIENTES DE BALASTO
punto [rotura] existen estados en los que es muy Pu f?.
aproximado suponer que hay una correspondencia entre 13 2 Pu
las deformaciones y las fuerzas aplicadas. r^'^
N:^.
Abundando en esta idea, señala en otro punto -[5] pág. 3-, "->^^^
que si el coeficiente de seguridad al hundimiento es \ "^ \
del orden de 3, el estado tensional del suelo parece • • > ^--^
corresponder bastante bien con el deducido de la -^^ A
hipótesis del suelo perfectamente elástico -véase ">^
Gráfico 1 tomado de la referencia [6], pág. 323-. \
Terzaghi [6] señala que la hipótesis de que el valor del \
módulo de balasto es, en cada punto, independiente de la
presión de contacto, /?, es, de acuerdo con las relaciones \
mostradas por el diagrama anexo -Gráfico 1- es
aproximadamente válida solamente para valores de/? que \
no superen la mitad de la capacidad portante última p^. c

El Dr. John T. Christian [7] proporciona una recopilación REU\CION ENTRE LA REACCIÓN DEL SUELO. P. Y EL ASIENTO, y:
de resultados de estudios de campo de diferentes autores LÍNEA OA: RELACIÓN SUPUESTA. CURVA OC: RELACIÓN REAL
sobre la Interacción Suelo-Estructura, con un saldo positi- Gráfico 1
vo para el método, pero con grados de ajuste muy diferen-
tes, desde excelente -obtenido por Whitman et al. ([8],
1971)-hasta otros menos ajustados de De Simone y a formaciones rígidas y, por tanto, experimentan
Gould ([9], 1971), con movimientos reales dobles de los deformaciones muy pequeñas que no afectan
predichos -aunque correctos en forma- sobre un soporte significativamente a la estructura.
de arcilla azul de Boston -un descargo evidente-. Los
resultados de estos estudios se pueden consultar en la La discusión anterior pretende hacer patente la necesidad
referencia indicada. de que el técnico conozca mínimamente las condicio-
nes de uso del modelo que va a utilizar, para decidir sobre
Empero, la bibliografía sobre el tema apunta a que no si resulta o no aplicable al caso que analiza. Más aún, el
todos los terrenos admiten una modelización igualmente valor del coeficiente de balasto a emplear no resulta trivial
satisfactoria con el método del Coeficiente de Balasto. en absoluto, dependiendo de diversos factores -entre ellos
Dentro de los tipos de suelos excluidos de la aplicación de el tamaño del cimiento y la profundidad del plano de
métodos lineales se encuentran las arcillas normalmente apoyo-. Por desgracia, la información que se encuentra en
consolidadas. Labor fundamental del técnico será, por los manuales de los programas referidos no es muy
tanto, discernir en qué situación el modelo resulta aplica- abundante en ninguno de estos aspectos.
ble y cuándo no lo es.
EL MÉTODO DEL COEFICIENTE DE BALASTO
Parece también dudosa la aplicación del método para el
estudio de cimentaciones no superficiales -ya que las El Método del Módulo de Balasto es conocido por el
expresiones propuestas para la determinación de k se nombre de Método de Winkler -ya que fue en 1867 su
corresponden con condiciones superficiales o casi introductor [10]- y que sirvió de base para el estudio, hoy
superficiales, que minimicen el error de suponer un valor ya clásico, de Zimmermann sobre el análisis de rieles de
del Módulo de Young nulo en superficie del terreno- por ferrocarril sobre traviesas [11].
lo que existen dudas sobre la adecuación del método para
el estudio de cimentaciones de torres [7]. La hipótesis Es bien sabido que es un modelo que no se ajusta a la
\-se reseñará más adelante- de un valor de E= O en superfi- realidad experimental del terreno, si bien los resultados
cie parece excluir también la representación de terre- que históricamente ha proporcionado están avalados por
nos sometidos a un nivel previo de tensiones importante la experiencia -véase Dr. John T. Christian [7]-, factor de
\-preconsolidaciones-. considerable importancia en un análisis como el que se
aborda. Tal y como se ha señalado anteriormente, esto
De todas formas, el problema anterior de la interacción puede ser debido a que, en edificación convencional, las
con el terreno en el caso de cimentaciones profundas se ve tensiones transmitidas al terreno son de pequeña entidad
reducido, porque normalmente las cargas son transmitidas -limitadas tanto por el coeficiente de seguridad, suficiente

(c) Consejo Superior de Investigaciones Científicas http://informesdelaconstruccion.revistas.csic.es
Licencia Creative Commons 3.0 España (by-nc)

<!-- p. 4 -->

26
Informes de la Construcción, Vol. 51 n'* 463, septiembre/octubre 1999

frente a hundimiento, como por la necesidad de limitar los La problemática del planteamiento del método queda así
asientos para que no resulten excesivos- y, en esta zona, de manifiesto: por una parte considera una relación
los valores responden con cierta aproximación a los que elástica lineal entre tensiones y deformaciones, regida
resultan de este modelo. por un módulo de Young con un valor nulo en superficie
y que varía linealmente en la profundidad, suponienEl método parte de la hipótesis de que el asiento producido do además que el terreno es incompresible.
en un punto es proporcional a la presión a la que está
sometido, transmitida por la cimentación. Analíticamente, Lo referente a la relación elástica lineal ha sido objeto de
un comentario anterior. El módulo de deformation en
terrenos homogéneos es, evidentemente, creciente con la
profiíndidad, pero que este crecimiento se produzca por
donde p representa la presión transmitida al terreno, correlación lineal es, cuanto menos, discutido entre los
y -ó s- el asiento experimentado yk^ el factor de proporción expertos.
entre ambos, conocido con el nombre de Módulo de
Reacción, Coeficiente de Reacción [12], Coeficiente de El valor nulo del módulo de Young en superficie es
Reacción de la Subrasante [6], Coeficiente o Módulo de incorrecto incluso para suelos muy flojos. No entremos
Balasto, con unidades de kg/cm^. en la consideración del efecto de la preconsolidación del
terreno, en el que para cargas inferiores a la de consolidación
La formulación se completa para los casos de carga lineal el asiento seria despreciable y por tanto, problemática la
q repartida sobre un ancho b y para carga concentrada P defensa del modelo.
actuando sobre una placa de área A como sigue:
Sin embargo, ensayos de laboratorio con placa de carga
q = k^'by = ky P = k'A'yOKy han demostrado que mientras las cargas no superen un
cierto límite, los asientos son proporcionales a las cargas
donde las unidades de ky K son variables para permitir la aplicadas-hipótesis general del método-. Se sabe empehomogeneidad de la fórmula. ro que el asiento de una gran cimentación es muy diferen-
te del encontrado para una pequeña superficie a la misma
Como demostró Gibson en sus estudios de 1967 y 1974 presión unitaria, razón que justifica una serie de
[13], el Método de Winkler es un caso particular de un correcciones introducidas al método y que incluso puede
Modelo de Suelo Elástico, Lineal, para un suelo Isótropo llegar a inhabilitarlo para ciertas soluciones y a partir de
y Heterogéneo, con Módulo de Young Linealmente ciertas dimensiones de los elementos.
Variable en Profundidad. Las particularidades del modelo
dentro de este grupo general se estriban en que considera De todas formas los rasgos que se acaban de señalar
un valor nulo en superficie para el Módulo E, y se supone no son más que particularidades de la hipótesis fiíndamenque el terreno es incompresible, ¡À =0,5, tal del método que considera el terreno como un fluido
'incompresible-, despreciando parámetros tales como el
Se puede representar la variación lineal del módulo de ángulo de rozamiento interno y la cohesión, y con el
Young en ñinción de la profiíndidad z como [14] agravante de que los terrenos no se comportan como
líquidos. Esto se remite a la hipótesis fimdamental del
E(z)=E(0)'^X'z método: solamente el terreno bajo el cimiento experimen-
ta deformaciones.
donde E(0) representa el valor del Módulo de Young en
superficie y A • z el incremento debido a la profiíndidad. De Se sabe que el asiento de los diferentes puntos del terreno
acuerdo con lo dicho anteriormente, el método considera depende del reparto de presiones en el suelo bajo las
que el módulo de Young varía con la profiíndidad de distintas cargas aplicadas. Sin embargo son conocidos
acuerdo con la ley desde los ensayos de Foppl de 1922 - citado en la referen-
cia [5], pág 4.-, gran variedad de terrenos para los que
E (z) = A • z resulta admisible la hipótesis de que el suelo se deforma
únicamente bajo la zona directamente cargada.
Y el Módulo de Balasto correspondiente, de acuerdo con
la expresión siguiente, responde a la relación Y esto, que es una falacia conceptual, tiene sin embargo la
importancia que permite ignorar la superposición de los
K = X./A, que si |j\< = 0,5 se convierte en K = 2/3 • X distintos bulbos de presiones de los cimientos del edificio
\-o de otros cimientos existentes- Jen/ro de ciertas
John T. Christian [7] indica que Masaal'skii (1964) [15] y magnitudes proporcionando unos resultados que,
Ward et al. (1968) [16] han encontrado referencias históricamente, han demostrado un grado de fiabilidad
experimentales que ratifican esta demostración. aceptable.

(c) Consejo Superior de Investigaciones Científicas http://informesdelaconstruccion.revistas.csic.es
Licencia Creative Commons 3.0 España (by-nc)

<!-- p. 5 -->

27
Informes de la Construcción, Vol. 51 n° 463, septiembre/octubre 1999

Fiabilidad que se explica -al menos parcialmente- porque, EXPRESIONES ANALÍTICAS DEL MÓDULO DE
como es sabido -si se llama è a la dimensión mayor del BALASTO
cimiento-, a una profundidad de 1,5 b -de forma más
precisa, a una profundidad variable entre b y 2b-, la De acuerdo con la hipótesis general del método, en
tensión transmitida al terreno es del orden de OJ-a, de pequeñas superficies y para placa circular se introduce,
forma tal que para las dimensiones de cimientos usuales siguiendo a Caquot [ 19], la hipótesis de que el coeficiente
en cimentación no suele haber problemas de superposi- de balasto es inversamente proporcional al diámetro de la
ción. Estudios recientes han mostrado que para placa empleada:
profundidades del orden de ^-6 no suele haber modificación tensional del terreno o bien ésta es insignificante. dK, = d'K,.
Otra razón que justifica el interés en el empleo del méto- donde d y d'son los diámetros de la placa de ensayo y K^
do es introducir coherencia con algunos de los métodos de y K^, son los módulos de balasto correspondientes a esos
Cálculo de Zapatas, que plantean implícitamente el cimientos determinados. Se admite igualmente que el
método del coeficiente de balasto -explícitamente en el valor correspondiente a unaplaca de carga cuadrada equivacaso del cálculo de zapatas de medianería y esquina-. Sin le al de una placa circular de igual área. Esta hipótesis
embargo, lo hacen aplicando la hipótesis de cimiento admite implícitamente que, para el rango de dimensiones
rígido, que conduce a una simplificación excesiva dados de las placas de carga -de 30 a 75 cm- el asiento producido
los métodos actuales disponibles. es proporcional al tamaño de la cimentación.

Se debe recordar que el método, tal y como se propuso Las relaciones anteriores son especialmente útiles para
inicialniente, descuida el efecto de factores tan importan- correlacionar resultados experimentales, normalmente
tes como: derivados de ensayos realizados con las placas de
diámetros normalizados 34 y 75 cm o conplaca cuadrada
\- Naturaleza del Terreno en Superficie y sobrecarga de 30 cm de lado, de tal forma que la expresión anterior se
aplicada. convierte en 34K^^ = 75'Kj^ para las placas circulares,
\- Profundidad del Plano de Cimentación. admitiéndose además que K^^ = K^^,, siendo este último el
\- Relación de Profundidad Plano Cimentación/Ancho de valor para lá placa cuadrada de lado 30.
Zapata.
\- Posición Relativa del Nivel Freático. La expresión anterior se admite para todo tipo de terrenos
\- Presencia de Capas Compresibles a Profundidad que y para pequeñas dimensiones de la faja de carga. Cuando
puedan ser afectadas. las dimensiones son las usuales en cimientos de
\- Forma y Dimensiones de la Cimentación. edifícación precisa de ciertas correcciones, algunas de
\- Nivel de Cargas Aplicado. ellas ya establecidas por Terzaghi en 1955 [6], para
\- Nivel de Tensiones en el Terreno. desterrar la errónea concepción, ampliamente extendida
entre los ingenieros, de que el Módulo de Balasto
Hoy, el Coeficiente de Balasto se hace depender de: depende exclusivamente de la naturaleza del subsue-
lo -[6], pág. 300-.
\1. Módulo de Compresibilidad E^ bajo el cimiento.
En la referencia anterior, Terzaghi fundamenta la
formulación en una reflexión sobre el tamaño de los2. Forma y dimensiones de la cimentación -rectangular,
bulbos de presiones y los asientos producidos.cuadrada, circular...-
Posteriormente [3] justifica las expresiones que evalúan
los valores del Módulo de Balasto a partir del estudio de 3. Proporción entre las dimensiones del cimiento y cargas
los asientos de zapatas corridas de diferentes dimensiones aplicadas.
trabajando a presión constante sobre arenas y arcillas
homogéneas. Terzaghi aproximó la variación del asiento 4. Rigidez Relativa del cmiiento.
ocurrido en las zapatas a partir del experimentado por una
placa de carga cuadrada de 30 cm -si bien las dimensiones 5. Nivel de Cargas: Cargas Vivas/ Cargas Muertas.
fueron expresadas en pies en la formulación original, se
han reescrito adaptadas al Sistema Intemacional- como:En el planteamiento del método se han llegado a introducir
correcciones-como, por ejemplo, la referencia [17]-que
garantizan cierta continuidad en la deformación del soporte 5^= S.30 (arcillas duras) 30 -suelo-, de tal forma que se garantiza en el modelo alguna
continuidad del soporte. La referencia [18] puede ser l'b c \2 Y (arenas)
valiosa en este tema. ^^^""^"^ft+SO

(c) Consejo Superior de Investigaciones Científicas http://informesdelaconstruccion.revistas.csic.es
Licencia Creative Commons 3.0 España (by-nc)

<!-- p. 6 -->

28
Informes de la Construcción, Vol. 51 n'* 463, septiembre/octubre 1999

donde s^^ es el asiento experimentado por la placa de Winkler depende fuertemente de la geometría de la
30 cm, s^ es el asiento del cimiento y b^ es el ancho del carga.
cimiento. De acuerdo con la ecuación inicial, y dado que
la presión transmitida es constante, es inmediato obtener: Terzaghi, empero, recomienda el método de Winklerpara
el cálculo de momentos, pero no para asientos, debido a 30
K~ ^30*— (arcillas duras) las simplificaciones que el método contiene. El propio
K Terzaghi, en su exposición de 1955 -[6] pág 301- ha
b +30 ^ / V señalado dos simplificaciones apriorísticas:
' ^° i'b^
que son las ecuaciones clásicas propuestas por Terzaghi 1. El Módulo de Balasto es, en cada punto, independiente
en 1955 [6], y que se recogen en [3] para zapatas o de la presión de contacto.
cimentaciones corridas^ donde k^^ es el valor del balasto
para placa de 30 cm y A:^ es el correspondiente al cimiento. 2. El Módulo de Balasto tiene el mismo valor en todos los
Sobre ellas John T. Christian-[7] pág. 151-indica que puntos de la superficie de contacto.
estas ecuaciones son aplicables exclusivamente a
cimentaciones superficiales y casi superficiales, por lo La primera hipótesis se ha analizado al principio del
que su aplicación a cimentaciones de edificios altos es capítulo, demostrándose su aproximada validez dentro de
dudosa. un rango de valores de presión sobre el terreno, siempre
inferior a la mitad de la presión de hundimiento.
Terzaghi en referencia [6], pág. 315, añade además:
La segunda de ellas se ha comprobado relevante en anáh- , (placas cuadradas
sis sobre base perfectamente elástica, en los que se
^^30 siendo a= — sobre arcillas 1,5-a ^c precomprimidas) ha demostrado que el Módulo de Balasto depende,
en cierta proporción, de la rigidez a flexión de la viga. A
expresión válida para una placa cuadrada de 1 pie(30cm), ambas simplificaciones, estudios posteriores, han asigna-
siendo /^ la longitud del cimiento. El propio autor aclara do factores de corrección.
que, para zapatas aisladas, zapatas continuas y vigas
flotantes, las expresiones anteriores son válidas siempre Estudios e investigaciones sucesivas han generalizado y
que la presión de contacto no supere la mitad de la capaci- reescrito parcialmente estas expresiones en la forma que
dad portante última del subsuelo; mientras que para losas sigue, donde 6^ representa el lado de la placa de carga [20].
sometidas a cargas concentradas lo son mientras que
ninguna de las cargas concentradas supere la mitad de la (arenas sueltas o muy sueltas,
capacidad portante última de la zapata equivalente de limos, arcillas) radio R -la zapata circular equivalente es un concepto que v^
acuña Terzaghi para el cálculo del módulo de balasto en
losas con cuyo diámetro se entraria en las fórmulas
Suelo Poco o No Coherente: anteriores-.

Empero la expresión anterior, en las referencias [3] y [6] ¿+¿.
el autor señala que no hay mayor diferencia entre el K^ kQ ( ^ , f (arenas densas)
2'b asentamiento de zapatas continuas y cuadradas de
igual ancho B, por lo que las expresiones anteriores
resultan también de aplicación para este último caso -idea
Suelo Muy Coherente: que ha sido rebatida por la bibliografia posterior, como se
ve seguidamente-.
h 4-h
k^= k^ (——-)^ (arenas compactas)
Autores posteriores [21 ] [ 12] han adaptado esta expresión
generalizándola para cualquier ancho de cimiento y
expresándola en el sistema internacional de unidades Para algunos autores-[12] pág. 310-, cuando el ancho
6 = 7m, se acepta:
/ (arcillas 2.a-Hl ^30
K~ ^30 siendo ^-^ preconsolidadas) k^= k^ (0.25+-2^) 3.a
Nótese asimismo que se está diferenciando la expre- con B en metros-.
sión del Módulo de acuerdo con el tipo de terreno e
introduciendo una corrección en razón al tamaño del Otros autores -[21], pág. 207; [12], pág. 310- recogen,
cimiento, ya que, además, la constante de muelle de además, la última de las expresiones de Terzaghi citadas,

(c) Consejo Superior de Investigaciones Científicas http://informesdelaconstruccion.revistas.csic.es
Licencia Creative Commons 3.0 España (by-nc)

<!-- p. 7 -->

29
Informes de la Construcción, Vol. 51 n" 463, septiembre/octubre 1999

generalizándola para cualquier ancho de cimiento y Esta expresión es aplicable a depósitos de arena natural y
expresándola en el sistema internacional de unidades compacidad relativamente uniforme. La corrección pare-
ce provenir de diferencias en la carga última encontrada.
. . 2.a+1 ^0 . . h (^''^^'^^ Ha sido probada con placas de carga de hasta 1,20 m.
K= K(\ 3.a siendo a=—¿ preconsolidadas) Evidentemente, para minimizar los efectos de alteración
del Módulo de Balasto debido a las dimensiones del
Resulta preocupante, por su falta de rigor, la propuesta de cimiento, interesan placas de carga grandes. Además, si el
algunos conocidos programas comerciales de cálculo de estrato compresible es de espesor menor que 4B se deben
estructuras de extender el empleo de la expresión anterior emplear valores de n menores. El autor indica como
al campo de las arcillas. corrección experimental que, en cimientos rectangulares,
es más exacto emplear el lado del cimiento cuadrado de
La modelización del terreno se vuelve, con las correcciones igual área.
anteriores, un poco más específica.
\3. Estimación por ensayo de laboratorio o in situ
El método ha ido modificando las expresiones que
correlacionan los valores de los Módulos de Balas- [ll]ACI'336.2R-88:Qn el apartado 3.3.2 indica que
to para distintos tipos de suelo y distintas situaciones -traducción del autor-:
y dimensiones de cimiento, corrigiendo aquellas
discordancias observadas entre su aplicación teórica Para obtener el asiento AH21 se procederá por integración
y las comprobaciones de carácter experimental numérica de la deformación unitaria a lo largo de la
(infi-avaloración de asientos, exceso esfuerzos). profundidad de influencia, calculando posteriormente K^
como q/ÁH.
Dentro de este planteamiento se han desarrollado estudios
tendentes a la determinación del Módulo en los casos de Se deben usar varios valores de deformación en la
Zapatas Unidas por Vigas de Atado -recogidos en la profundidad de influencia, aproximadamente 4B, donde
referencia [22]-. B es la mayor dimensión de la base del cimiento.

Se exponen a continuación diferentes métodos de Los valores de los parámetros elásticos determinados
estimación del Módulo de Balasto propuestas por en laboratorio son fuertemente dependientes de las
diferentes autores, indicando el año de su proposición y la perturbaciones de la muestra y del tipo y calidad de los
referencia. resultados del análisis triaxil

MÉTODOS DE ESTIMACIÓN DEL MÓDULO DE A continuación se señalan una serie de correcciones
BALASTO propuestas por distintos autores. Se ha mantenido la
diferenciaciónrecogida en las publicaciones entre Módulo
\1. A partir de Tabulaciones Publicadas: Edométrico, E^, y el Módulo de Compresibilidad, E^.
Ambos dependen del valor de tensión que se escoja como
[17] ACI-336.2R-88: señala las siguientes: valor inicial en el ensayo. Se definen como [31]

Terzaghi, 1955 [6]. Bowles, 1974,1982,1984 [23][24][25]. A.a^
Dept. of Navy, 1982 [26]. Kramrish, 1984 [27]. AV

REFERENCIASESPAÑOLAS:
3.a. A partir de Módulo de Compresibilidad del Suelo:
[28] Calavera, Cálculo de Estructuras de Cimentación.
Tablas GT-8 y GT-9 Según DE BEER [32]:
[29] Jiménez Salas, Geotecniay Cimientos III Capítulo 1.
Tabla 1.1 1. Cimentación Circular de área^ y rigidez suficiente para
distribución uniforme de presiones:
\2. A partir de Ensayos en Placa de Carga: E^
K= 1,392--^
[17] ACI-336.2R-88: cita, entre otros:
\2. Cimentación Circular de área A y rigidez infinitamente
Terzaghi, 1955 [6] -señalados anteriormente-. grande:
Sowers, 1977 [30]:
K= 1,50-^- k^ k, A " 0,5^n^0,7

(c) Consejo Superior de Investigaciones Científicas http://informesdelaconstruccion.revistas.csic.es
Licencia Creative Commons 3.0 España (by-nc)

<!-- p. 8 -->

30
Informes de la Construcción, Vol. 51 n" 463, septiembre/octubre 1999

\3. Cimentación Rectangular ¿z > 6 y rigidez suficiente para
K=distribución uniforme de presiones: H
2.Carga en faja de ancho 5, con capa compresible de
A:= 1,330 — — espesor H:
ab^ 1 K=2^
\4. Cimentación Rectangular a> b con rigidez propia tan B , ,B+2H. B Ln(-^)exigua que se produce levantamiento:
3.Para superficies circulares o cuadradas, de diámetro o
K= 1,330 — lado d:

d^H
si el levantamiento a.a> ;r, se denota por a'=;r/a, siendo K= E, d'H
4 í
relaciones que se han obtenido a partir de un reparto de
\ 4El tensiones por ensanche lineal a 45**.

DIMITROV[32]: VESIC (1971) [34] : Para una gran viga sobre profimdidad
infinita de suelo con módulo de elasticidad o de
K= p deformación constantes, el valor de k resulta ser
b (l-^l')
12 E,b* £,donde p es un Coeficiente de Forma de la Cimentación jfc = 0,65
Rectangular, según la tabla 1. ^
Y \i depende del tipo de terreno de forma tal que: ACI-336.2R-88 [17]:
0,125^1^^ 0,50 Arenosos y guijarrosos 1. Bowles (1982) [24]:
0,200\< ^^\<0,40 Arcillosos
E^
DIN 4019: [32] K= '— ,
donde la función/depende de las relaciones a/b y z/b, 2. Corrección de Comentarios,
donde z es el espesor de la capa de terreno efectivo,
tomándose un valor z= 2'b si el espesor efectivo supera ,._ ^s
2'b. (tomado de la referencia [32]) (tabla 2). b (1-ix^) IJp
3.b. A partir de Módulo de Deformación o del Módulo donde I^ representa el Factor de forma de la base,
Edométrico Equivalente, E^ del Suelo: dependiente de la forma y flexibilidad de la cimentación,
e Ip denota el factor de empotramiento por la profundidad.
VOGT[33]:
\1. Cimentación Circular de área^ y rigidez suficiente para 4. Uso mixto:
distribución uniforme de presiones:
ACI-336.2R'88 [17]:
K= l,392--5-
Úsese uno de los métodos anteriores para estimar el
\2. Cimentación Rectangular a > 6y rigidez suficiente para Módulo de Balasto, pero, además, considérese la respuesta
distribución uniforme de presiones: del subsuelo a las condiciones de carga dependiente del
En tiempo.
K= 1,330 Y7=
\-Nótese la coincidencia con dos de las expresiones Propuestas de Métodos Iterativos -recogidos por la
propuestas por De Beer-. norma-:

KOGLER YSCHEIDING [33]: tnrich (1988) [35].
Banavalkary Ubich(1984) [36].
1 .Superficie infinita, con capa compresible de espesor i/: Fochtetal.(1978)[37]
(c) Consejo Superior de Investigaciones Científicas http://informesdelaconstruccion.revistas.csic.es
Licencia Creative Commons 3.0 España (by-nc)

<!-- p. 9 -->

31
Informes de la Construcción, Vol. 51 n* 463, septiembre/octubre 1999

TABLAI

a:b i^.OO 1,50 2,00 3,00 5,00 10 20 30 50
P 1,05 0,87 0,78 0,66 0,54 0,45 0,39 0,33 0,30

TABLA2

z:b\l:b 1,00 1,50 2,00 3,00 5,00 10,00 20,00

0,20 0,18 0,18 0,18 0,19 0,19 0,19 0,19

0,40 0,29 0,31 0,32 0,33 0,33 0,34 0,34

0,60 0,37 0,40 0,42 0,44 0,45 0,46 0,46

0.80 0,44 0,47 0,50 0,53 0,56 0,57 0,57

1,00 0,49 0,53 0,57 0,61 0,64 0,67 0,67

1,50 0,58 0,65 0,70 0,75 0,81 0,86 0,87

2,00 0,64 0,72 0,78 0,85 0,93 1,00 1,03

3,00 0,70 0,82 0,89 0,99 1,09 1,20 1,25

5,00 0,76 0,90 1,00 1,13 1,27 1,43 1,54

7,00 0,79 0,94 1,05 1,20 1,37 1,55 1,68

10,00 0,81 0,97 1,09 1,26 1,45 1,68 1,85

20,00 0,82 0,98 1,12 1,32 1,57 1,89 2,12

CORRECCIONES ALMÓDULODEBALASTO la carga está aplicada en un extremo, debe tomarse
para K el doble del valor medio de dicho coeficiente.
\- J. Hann [32], señala
Este autor, en la referencia citada, propone unos valores
\- Problemas de infravaloración de asientos: calcúlense de longitudes elásticas virtuales de las vigas flotantes
con los valores límite función de las distintas posiciones de la carga sobre ella.
A partir de ellos se han obtenido las correcciones al
\- El valor menor de Â'para el cálculo de presiones sobre el Módulo de Balasto que considera este autor, en función
terreno. de la posición relativa de la carga. Estos valores se
reflejan en el Gráfico 2
\- El valor mayor de -^para el cálculo de esfuerzos sobre la
cimentación.

\- Consolidación en los Bordes de una Viga Flotante:
implica aumento del Módulo de Balasto.

Experiencias señaladas por Borowika y De Beer
demostraron teóricamente que la presión sobre una zapa- ^ ^1.00
ta circular con carga uniformemente repartida (Borowüca) 1.31 1,104 1,00 0.961 0,9225 0.904 0.885 0.885 0,885
y rectangular con carga puntual en el centro ejercen un
reparto de presiones que no es en absoluto lineal. ^,874

La teoría del semiespacio elástico conduce a la 0.00 0.10 0.20 0.30 0.40
determinación de un coeficiente de balasto variable
PORCENTAJE DE DISTANCIA AL EXTREMO, a.L/L
dentro de la superficie de la cimentación, cualquiera
que sea el tipo de ésta.f...] Según Dimitrov [...] cuando Gráfico 2

(c) Consejo Superior de Investigaciones Científicas http://informesdelaconstruccion.revistas.csic.es
Licencia Creative Commons 3.0 España (by-nc)

<!-- p. 10 -->

32
Informes de la Construcción, Vol. 51 n" 463, septiembre/octubre 1999

Bowles -[24] [25]- plantea también correcciones por tabulaciones del Módulo de Balasto. La razón estriba en
consolidación del terreno. La propia ACI-336 [17], en su que los efectos de escala resultan demasiado severos. En
apartado 6.9 recomienda: se debe prestar especial este sentido, ACI-336 [17], en su apartado 2.2.8, Modulus
atención a los muelles exteriores porque estudios con of Subgrade Reaction, indica que:
modelos de gran tamaño han mostrado que se precisa
duplicar los muelles finales para conseguir Para losas de cimentación, esta propiedad del suelo no
aproximación entre los resultados del cálculo y los puede ser convenientemente estimada con ensayos de
experimentales. Esta duplicación produce un mínimo campo de placa de carga, porque los efectos de escala
efecto de emparejamiento. son demasiado severos.

ACI-336.2R-88 [ 17] -se refiere fiíndamentalmente al caso Se pueden obtener resultados suficientemente precide losas de cimentación-: sos usando la teoría del Módulo de Balasto, pero
modificada, para considerar individualmente cargas
El uso de un solo Coeficiente de Balasto constante para muertas, cargas vivas, efectos del tamaño, respuestas
toda la cimentación puede conducir a errores por del terreno asociado...
infravaloración de los resultados, ya que éste depende de:
Se deben considerar zonas de Módulo de Balasto
\- Tamaño del cimiento. constante de diferente valor para conseguir una
\- Área tributaria del nodo. estimación más aproximada que la predicha por un
\- Proñindidad efectiva. único módulo constante. Se puede encontrar una
\- Módulo de Balasto elegido. exposición del método en Ball y Notch (1984) y Bowles
\- Variación del Módulo con la profundidad. (1982), así como análisis en Banalvakary Ulrich (1984)
\- Características dependendientes del tiempo: yFochtetal. (1978). [38] [24] [36] [37]
. Asientos por consolidación.
. Asientos por consolidación parcial. [...] Se debe tener precaución cuando se use el análisis
por Elementos Finitos para suelos. Sin unos buenos
resultados experimentales, los muelles de terrenoAdemás la interacción suelo-estructura puede continuar
derivados de los valores del Módulo de Balasto puedendurante largo tiempo hasta que se establezca el equilibrio
ser exclusivamente una grosera aproximación a lafinal entre las cargas sobreimpuestas y las reacciones del
respuesta actual del suelo. Algunos proyectistas llevanterreno soportante.
a cabo varios análisis con muelles de terreno, calcula-
dos dentro de un rango de Módulos de Balasto paraFactores Detallados (Interacción Suelo-Estructura):
obtener un diseño adecuado.
\- Tipo del suelo bajo la cimentación.
\2. Correcciones a Adoptar en la Modelización:- Tipo del suelo a grandes profundidades.
\- Tamaño de la cimentación.
En orden de complejidad decreciente se plantean los - Forma de la cimentación.
siguientes sistemas de modelizaciones: - Excentricidad de la carga.
\- Rigidez de la cimentación.
\-Empleo de Coupled Springs - Rigidez de la superestructura.
\-Sistemas de Emparejamiento Indirecto de Boussinesq,
vinculado a estimaciones del asiento por Boussinesq ([ 17] 1. Corrección en el Método de Determinación del
Sección 6.7).Módulo:
\-Usar en combinación los métodos anterior y siguiente.
\-Doblar los muelles extremos -Bowles (1974) [23]- - Cimientos pequeños B\<1,50 m. Se puede estimar el
\-Contribución del muelle estimada en proporción lineal aMódulo de Balasto sobre la base de ensayos de Placa de
la superficie -práctica común, pero incorrecta-.Carga o sobre la base de las caracteristicas de los suelos
conocidos.
Las correcciones a adoptar en la modelización propues-
tas tratan de conseguir la corrección del comportamientoEl comportamiento del suelo es generalmente más
de muelles aislados que se deforman sin continuidad, complicado de lo que se asume en el cálculo de tensiones
estableciendo una deformación continua del modelo depor medio de la teoría del Módulo de Balasto. Sin
terreno. embargo, cumpliendo ciertos requisitos y limitaciones,
se pueden obtener resultados suficientemente precisos
mediante el empleo de estas teorías. FASES DE LA APLICACIÓN DEL MÉTODO[39]

\- Cimientos grandes -referido a losas-: estimación por 1. Modelización [de la Estructura,] de la Cimentación y del

(c) Consejo Superior de Investigaciones Científicas http://informesdelaconstruccion.revistas.csic.es
Licencia Creative Commons 3.0 España (by-nc)

<!-- p. 11 -->

33
Informes de la Construcción, Vol. 51 n** 463, septiembre/octubre 1999

Terreno, de acuerdo con las consideraciones señaladas y las vigas flotantes, donde se expresa que se considera el
las que se realizan en el capítulo especíñco. cimiento comoflotandosobre un líquido. Es sabido que en
el caso de los líquidos, el empuje que recibe el cuerpo
\2. Determinación de las Constantes de Muelle que son de sumergido es proporcional al peso del volumen de líquido
aplicación. Implica: desplazado. En este sentido se justifica la introducción del
concepto de Area Equivalente.
\- Cálculo del Módulo de Balasto del Suelo, k^
\- Cálculo del Módulo de Balasto Corregido del Cimien- CONCLUSIONES
to, *,
\- Cálculo del Valor de Muelle teniendo en cuenta las áreas El avance en los recursos informáticos ha puesto al alcantributarias y las correcciones por consolidación. ce del técnico el tratamiento conjunto de suelo-cimiento-
estructura para casos cotidianos, introduciendo un mayor
\2. Cálculo del Modelo. nivel de precisión. El mayor grado de precisión obtenido
se refleja principalmente en una serie de aspectos como
\3. Cálculo de las Fuerzas Nodales del Terreno, calculadas son
como
\-Leyes de esfuerzos más ajustadas a la realidad.
Fuerza= Muelle de Nodo x Desplazamiento del Nodo -Dimensionado de los elementos de cimentación tenien-
do en cuenta su deformabilidad y una respuesta del terreno
Deben calcularse y totalizarse para compararlas con la más ajustada.
suma de las fuerzas verticales de la entrada de datos -Estimación afinada de las presiones realmente
\-cargas axiles y peso de la losa- y verificar la validez del transmitidas al terreno.
cálculo. Debe realizarse como un chequeo de rutina. - Posibilidades de estudio de asientos.

\4. Presiones sobre el Terreno en los Nodos, calculadas Empero, el prímer condicionante que surge es conseguir
como: una modelización del suelo adecuada. En numerosos ca-
sos, este problema se ha resuelto recurríendo al método
q.= k^ X Desplazamiento del módulo de balasto, bien conocido y único del que se
posee contraste práctico.
Evidentemente, los valores así calculados deben ser
aceptables para el terreno. Desgraciadamente, las referencias que los manuales de
los programas informáticos ofrecen sobre este aspecto
De todas formas, como la rigidez axil de la barra ficticia son muy escasas, siendo sin embargo un problema
que emula el terreno se expresa como trascendente para la consecución de un modelo afinado.
Las referencias que se incluyen en el artículo permiten
EA decidir sobre la validez del modelo para cada caso particular, = Kb'X
I así como también la elección de valores adecuados para el
módulo, de acuerdo con el tipo de terreno y de cimientos
donde x es el paso de la discretización. Evidentemente, -así como de sus dimensiones- que se encuentren
según lo expuesto anteriormente, siendo x constante, involucrados en el problema.
resulta que la capacidad de carga del cimiento es muy poco
dependiente de su ancho b. Se puede corregir este efecto Por último, se recogen una serie de refinamientos que
definiendo un ancho equivalente, b que sería el ancho diversos autores han ido proponiendo para la mejora del
de un cimiento cuadrado de igual área, de forma similar al modelo y que pueden ser fácilmente implementados en
coeficiente corrector que propone Calavera -[21] pág. sistemas informáticos, obteniendo unos grados de precisión
342 y 343- para el caso de arcillas. La importancia del de nivel superior.
problema se plantea en la capacidad portante de la zapata de
medianería, ya que de considerarla funcionando
principalmente en un sentido u otro -esto es, planteando BIBLIOGRAFÍA
qué lado se designa por a y cuál por 6-, habría una noto-
ría diferencia de la capacidad de carga del cimiento. La [1] Véase, por ejemplo, CALAVERA, J., Cálculo de
consideración anteríomente señalada permite obtener un Estructuras de Cimentación, Capítulo 3. INTEMAC,
valor medio para el caso. Madrid (2" Ed.)

Una justificación de esta corrección se puede plantear [2] Véase, por ejemplo, CALAVERA, J., Cálculo de Flechas
desde el principiofísicodel empuje de cuerpos sumergidos. en Estructuras de Hormigón Armado, Capítulo 1.
Este método es conocido, como es bien sabido, como de INTEMAC, Madrid, 1992.

(c) Consejo Superior de Investigaciones Científicas http://informesdelaconstruccion.revistas.csic.es
Licencia Creative Commons 3.0 España (by-nc)

<!-- p. 12 -->

34
Informes de la Construcción, Vol. 51 n** 463, septiembre/octubre 1999

[3] TERZAGHI, KARL Y PECK, RALPH B., Soil Mechanics [18] HORVATH, J. S., A Study of analytical methods for
in Engineering Practice. Whiley, New York, 1967. Version determining the response of mat foundations to static
Española Mecánica de Suelos en la Ingeniería Práctica. loads. Tesis Doctoral del Instituto Politécnico de Nueva
Editorial El Ateneo S.A. l^Ed: 1955.2^ Ed.: 1973.págs. 279 York, 1979.
y ss. / 484 y ss.
[19] Referencia tomada de [12], pág. 309. Si bien no aparece
[4] JIMÉNEZ SALAS, Geotecniay Cimientos. Editorial Rueda. referida en ésta, parece corresponder a Caquot y Kerisel,
Madrid, 1980 (2'» Ed.) Traité de mécanique des sois. París, 1956.

[5] JIMÉNEZ SALAS, Geotecnia y Cimientos^ Tomo III, [20] Sopeña, L., Jornadas sobre Problemática Geotécnica
Capítulo 1. Editorial Rueda. Madrid, 1980 {T Ed.) en la Edificación. Cimentaciones, pag. 64 y ss. Lugo,
junio 1994.
[6] TERZAGHI, KARL, Evaluation of Coefficients of
Subgrade Reaction. Geotecnique, 1955, Vol. 5, nl 4, pp. [21] CALAVERA, J., Estructuras de Cimentación.
297-326. INTEMAC, Madrid (20 Ed.).

[7] Dr. CHRISTIAN, JOHN T., SoiUFoundation-Structure [22] L'HERMINIER, Étude des fondations de surface.
Interaction. Proceedings, Short Course-Seminar on Analysis Annales del I.T.B.T.P. Enero, 1957. Sois et Fondations
and Design of Buildings Foundations. Lehigh University. nl24
Envo Press, Lehigh Valley, 1976, pp. 149-179.
[23] BOWLES, J.E., Analytical and Computer Methods in
[8] Whitman, R. ; Casagrande, D. ; Karstrud, Kjell y Simon, R., Foundation Engineering. McGraw-Hill Book Co., New
Performance of Foundation for Altair Radar. ASCE, York, 1974, pp. 154-170.
journal of Soil Mechanics and Foundation Division, Vol. 97,
enero, 1971,pp 1-18. [24] BOWLES, J.E., Foundation Analysis and Design.
McGraw-Hill Book Co., New York, 1982, 800 pp. (3^*
[9] De SIMONE, S.V. Y GOULD, J.P., Performance of two Ed.)
mat foundations on Boston blue clay. Presentada a ASCE
Annual and National Environmental Engineering Meeting. [25] BOWLES, J.E.,Physical and Geotechnical Properties
St. Louis, octubre 1971. of Soil. McGraw-Hill Book Co., New York, 1984 (2*
Ed.)
[10] WINKLER, E., Die Lehre von Elastizitat und Festigkeit
(Sobre Elasticidad y Resistencia). Praga, 1867, pp. 182. [26] Dept. of Navy. Soil Mechanics. Design Manual
NAVFAC DM-7.1. Naval Facilities Engineering
[11] ZIMMERMANN, H., Die Berechnung des Eisenbahn Command, Alexandriapp. 7.2-129 a7.2-175.
Oberbaues. (Cálculo de superestructuras de vías de
ferrocarril) Berlín, 88 [27] KRAMRISH, F., Footings. Handbook of Concrete
Engineering. MarkFintel, Editor, VanNostrandReinhold
[12] D. GRAUX, Fundamentos de Mecánica del Suelo. Co. New York, 1984. pp. 139-168(2'^ Ed.)
Proyecto de Muros y Cimentaciones.
Editores Técnicos Asociados, Barcelona, 1975 (2^ Ed.) [28] CALAVERA, J., Estructuras de Cimentación, Tabla
GT-9. INTEMAC, Madrid (2" Ed.)
[13] GIBSON, R. E., Some Results Concerning Displacements
in a Non-Homogenous Elastic Half-Space. Geotechnique, [29] JIMÉNEZ SALAS, Geotecniay CimientosIlI.Capitülo
Vol. 17, pp., 58-67, 1967 y The analytical method in soil 1. Tabla 1.1. Editorial Rueda. Madrid, 1980 (2" Ed.)
mechanics. Geotechnique, Vol. 21, pp., 115-140, 1974
(Referencias tomadas de Jiménez Salas, Geotecnia y [30] SOWERS, G.F., Foundation Modulus for a Mat on
Cimientos, Tomo III, Cap. 1. pág. 4 -Editorial Rueda, Sand. Preprint nl 2937. American Society of Civil
Madrid, 1980 (2^ Ed.)- que se refiere a Vol.2, Pág. 265 y ss.) Engineers, oct 17-21. New York, 1977.

[14] JIMÉNEZ SALAS., Geotecniay Cimientos, Vol. II. Cap., [31] JIMÉNEZ SALAS. Geotecnia y Cimientos, Vol. I,
pág. 265. Editorial Rueda. Madrid, 1980 (2^ Ed.) págs. 181 y 320. Editorial Rueda. Madrid, 1980 (2" Ed.)

[15] MASAAL'SKII, E.K., Experimental Study of a Flexible [32] Tomado DE J. HANN, Vigas Continuas, Pórticos,
Beam on a Sand Foundation. Soil Mechanics and Foundation Placas y Vigas Flotantes sobre Terreno Elástico.
Engineering, Santiago de Chile, 1964, Vol II, pp 71 -86. Editorial Gustavo Gili, 3** Ed. págs. 334 y ss.

[16] WARD, W.H.; BURLAND, J.B. Y GALLOIS, R.W., [33] Tomado de JIMENEZ SALAS,Geotecnicay Cimientos
Geotechnical Assessment of a Site at Mundford, Norfolk in. Capítulo 1. Editorial Rueda. Madrid, 1980(2*Ed.)
for a Large Proton Accelerator. Geotechnique, 1968, Vol
18 pp. 399-431. [34] VESIC, ALEKSANDER, Beams on Elastic Subgrade
and the Winkler's Hypothesis. 5* International
[17| ACI 336 2R-88. Suggested Analysis Design Procedures ConferenceofSoilMechanicsandFoundationEngineering.
for Combined Footings and Mats. Paris, 1971, Vol. I. pp. 845-850.
(c) Consejo Superior de Investigaciones Científicas http://informesdelaconstruccion.revistas.csic.es
Licencia Creative Commons 3.0 España (by-nc)

<!-- p. 13 -->

35
Informes de la Construcción, Vol. 51 n° 463, septiembre/octubre 1999

[35] ULRICH, E.J., Geotechnical Considerations in Mat [38] BALL, S.C. Y NOTCH, J.S., Computer Analysis/Design
Foundations Design. Structural and Geotechnical Lecture of Large Mat Foundations. Journal of Structural
Series. ASCÇ, Sección Illinois. Chicago, 1988 Engineering ASCE, Vol. 1 10ni 5.mayo, 1984.pp. 1180-
\1196.
[36] BANAVAKAR P.V. Y ULRICH, E.J., Republic Bank
Center: Structural and Geotechnical Features. [39] Se puede consultar la exposición realizada en PÉREZ
International Conference on Tall Buildings. Singapur, VALCÁRCEL et alii Estructuras de Hormigón Armado.
Octubre, 1984. Tórculo Artes Gráficas, Santiago de Compostela, 1994.

[37] FOCHT J.A.; KHAN, F.R. Y GEMEINHARDT, J.P.,
Performance of One Shell Plaza Deep Mat Foundation.
Proceedings ASCE,V. 104, Mayo, 1978. pp. 593-608.

Publicaciones del Instituto Eduardo Torroja-CSIC

; SUMARIO:
Prólogo Prof. G. Ciribini.

Introducción
Capítulo 1. —La industrialización en las proclamas y ma-
nifiestos de arquitectura.
Capítulo 2.—¿Réquiem por la construcción industriali-
zada?
^:;k..>V4;|fUv^4 i Capítulo 3.—Algunos conceptos básicos.
;s5: Síl:.l¡r/Q;í;; Capítulo 4.—¿Proyecto tradicional, construcción indus-
.í trializada?
Vi, Capítulo 5. —Componentes.
? Capítulo 6. — La coordinación dimensional hoy.
•' Capítulo 7. —Flexibilidad, intercambiabilidad y catálogos.
ALOJAMIENTO Y TECNOLOGÍA: Capítulo 8. —Industrialización, normativa y calidad.
¿INDUSTRIALIZACIÓN ABIERTA? Capítulo 9. — Reflexiones finales.
JULIAN SALAS, ING. IND. (LE.T.c.c.)
Un volumen de 160 páginas, 109 figuras y 16 tablas, Ta-
publicación del maño 240 X 168 mm. Encuademado en rústica.
INSTITUTO EDUARDO TORROJA

(c) Consejo Superior de Investigaciones Científicas http://informesdelaconstruccion.revistas.csic.es
Licencia Creative Commons 3.0 España (by-nc)
