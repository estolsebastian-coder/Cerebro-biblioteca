---
type: libro
title: "Análisis constructivo y estructural de la catedral de Valencia ; Constructive and structural analysis of the cathedral of Valencia"
author: "V. Llopis Pulido"
categoria: "Técnicas Constructivas y materiales para la conservación"
paginas: 10
extraccion: "texto"
fuente: "local:D:/UPV/MCPA/Asignaturas/Técnicas Constructivas y materiales para la conservación/03. Otros documentos/Técnicas constructivas/Tesis doctorales/Resumen tesis doctoral Verónica Llopis.pdf"
convertido: 2026-10-16
---

# Análisis constructivo y estructural de la catedral de Valencia ; Constructive and structural analysis of the cathedral of Valencia

> Texto extraído de `Técnicas Constructivas y materiales para la conservación\03. Otros documentos\Técnicas constructivas\Tesis doctorales\Resumen tesis doctoral Verónica Llopis.pdf` (10 páginas, texto). El PDF original está en el disco D: (UPV\MCPA\Asignaturas); `<!-- p. N -->` marca el inicio de cada página.

<!-- p. 1 -->

Informes de la Construcción
Vol. 68, 543, e158
julio-septiembre 2016
ISSN-L: 0020-0883
doi: http://dx.doi.org/10.3989/ic.15.102

Análisis constructivo y estructural de la catedral de Valencia

Constructive and structural analysis of the cathedral of Valencia

V. Llopis Pulido (*), A. Alonso Durá (*), E. Fenollosa (*), A. Martínez Boquera (*)

RESUMEN

Las características constructivas de la catedral de Valencia la convierten en un ejemplo representativo del gótico mediterráneo: reducida esbeltez, escasa diferencia de altura entre las naves y limitadas dimensiones de huecos.

Estas características se explican a partir del presente trabajo donde se muestra un estudio constructivo y un análisis del
sistema estructural frente a cargas gravitatorias y efectos sísmicos. En el análisis se utiliza el método por empujes incrementales (pushover) y el método no-lineal de modelo de daño. La función de arbotantes y diafragmas quedará patente con
la modificación del modelo MEF que eliminará progresivamente cada uno de estos elementos constructivos.

Los resultados muestran una suficiente capacidad resistente frente a un sismo con un período de retorno de 475 años que
empeora si se considera de 950 años. Se evidenciará la necesidad de la continuidad muraria a través de los arbotantes que
se convierten en auténticos muros diafragmáticos.

Palabras clave: Gótico mediterráneo; análisis sísmico; pushover; modelo de daño; elementos finitos; período retorno.

ABSTRACT

The cathedral of Valencia constructive characteristics make it a representative example of the Mediterranean Gothic:
low slenderness, little height difference between the naves and limited voids dimension.

These differences are explained from the present work, where a constructive study and a structural system analysis
under gravity loads and seismic effects are shown. For the analysis a pushover method and a non-linear damage model
have been used. The buttresses and diaphragms function will be patent with the Finite Element structural model modification which will progressively remove each one of these constructive elements.

The results display a resistant capacity enough to face a seism of 450 years that gets worse if a return period of 950
years is considered. The need of the walls continuity trough the buttresses that turn into authentic diaphragm walls will
be demonstrated.

Keywords: Mediterranean Gothic; seismic analysis; pushover; damage model; finite element; return period.

(*) Departamento Mecánica de los Medios Continuos y Teoría de Estructuras. Universitat Politècnica de València. Camino
de Vera, s/n. 46022 Valencia, Spain.
Persona de contacto/Corresponding author: vllopis@mes.upv.es (V. Llopis Pulido)

Cómo citar este artículo/Citation: Llopis Pulido, V., Alonso Durá, A., Fenollosa, E., Martínez Boquera, A. (2016). Análisis constructivo
y estructural de la catedral de Valencia. Informes de la Construcción, 68(543): e158, doi: http://dx.doi.org/10.3989/ic.15.102.
Licencia / License: Salvo indicación contraria, todos los contenidos de la edición electrónica de Informes de la Construcción se
distribuyen bajo una licencia de uso y distribución Creative Commons Attribution License (CC BY) Spain 3.0.

Recibido/Received: 31/07/2015
Aceptado/Accepted: 26/06/2016
Publicado on-line/Published on-line: 19/09/2016

<!-- p. 2 -->

V. Llopis Pulido, A. Alonso Durá, E. Fenollosa, A. Martínez Boquera

\1.  INTRODUCCIÓN 2.  DESCRIPCIÓN

El sistema estructural de las grandes catedrales góticas cen- La iglesia catedral basílica metropolitana de Valencia (1262)
troeuropeas está formado por bóvedas de crucería que per- se sitúa sobre la antigua mezquita mayor musulmana. Es un
miten concentrar las cargas gravitatorias sobre cuatro co- edificio de planta de cruz latina con marcado crucero, formalumnas. El muro pierde su función portante y se convierte en da en su origen por tres naves y tres crujías transversales.
grandes vitrales que permiten la entrada de luz en el edificio
(1). La nave central es de tramos cuadrados mientras que las late-
rales son de tramos rectangulares con el eje mayor según el eje
La estructura de la catedral de Valencia se aparta de los cá- longitudinal del templo, delimitadas por una serie de capillas
nones constructivos del gótico centroeuropeo, se trata de un que configuran el espacio central. Su construcción se inició por
ejemplo representativo de la denominada arquitectura gótica la girola, de tramos pentagonales delimitados por un tramo de
mediterránea (2), (3). Arquitectura que se caracteriza por su la capilla mayor y por dos capillas absidiales. Estas capillas se
escasa esbeltez y por una disminución de la superficie des- configuran radialmente, con una disposición poco común al
tinada a vidriera, debido a la pequeña diferencia de altura considerar a eje de simetría un pilar y no una capilla.
entre la nave principal y las laterales (4). Distintas hipótesis
han intentado justificar el porqué de estas diferencias, desde En 1458 se realiza la ampliación de la catedral: se añade una
motivos relacionados con el clima, cuestiones compositivas, cuarta crujía y se unen al templo los volúmenes de la capilla
el carácter defensivo de este tipo de edificación, etc. del Santo Cáliz y el campanario conocido como El Miguelete.
Al final del siglo xvii se amplían capillas con cúpulas barrocas
Recientes estudios relacionan estas peculiaridades del góti- que configuran el estado actual (Figura 1a).
co mediterráneo con la geografía en que se ubican. En concreto al superponer su localización con el mapa sísmico de El cimborrio es de planta octogonal, se sitúa en el tramo cenEuropa se observa que se sitúan en zonas de mayor riesgo tral del crucero, articulado en dos cuerpos muy esbeltos y sin
sísmico (5). estribos, estas características lo han convertido en una obra
que ha generado gran admiración (Figura 1b).
El presente trabajo mostrará el estudio constructivo de la
catedral de Valencia y su análisis estructural, a partir de un La sección transversal (Figura 2a) refleja las características
modelo informático con E.F. (6). La manipulación de este que alejan a la catedral de Valencia de los ideales de propormodelo mediante la eliminación selectiva de arbotantes, dia- ción del gótico centroeuropeo. Por un lado la escasa diferenfragmas y/o refuerzos, genera cinco variaciones, cuyo análisis cia de altura entre la nave principal y las naves laterales lo
mostrará la función de cada uno de estos elementos estruc- que supone una reducción de la superficie de las vidrieras.
turales. Por otro lado destacar la posición de los arbotantes por enci-
ma del empuje de la bóveda, situación que pone en duda su
El análisis estructural de la catedral, que contempla las accio- función estructural.
nes sísmicas además de las cargas gravitatorias, se realizará
mediante el programa de E.F. en régimen no lineal ANGLE El sistema primario lo constituyen dos conjuntos de muros-
(7). Los efectos sísmicos se evaluarán mediante el método de diafragma, los muros longitudinales de la nave central y los
análisis por empujes incrementales (pushover) (8) y el com- transversales de cada tramo (Figura 2b), el conjunto confiportamiento de los materiales mediante el denominado «mo- gura una caja rígida de muros de gran potencia. El muro diadelo de daño» (9). fragmático transversal es perforado por los arcos de la nave
central y las laterales, y por un arco de medio punto que perLos resultados obtenidos proporcionarán un excelente cono- mite el recorrido por la cubierta. El arbotante forma parte del
cimiento del comportamiento estructural y de los sistemas diafragma, en realidad es el resultado de su perforación por
constructivos utilizados en el gótico mediterráneo. el mencionado arco.

(a) (b)

Figura 1.  Catedral de Valencia: a) planta; b) sección longitudinal. (Planos autor Ramiro Moya).

2 Informes de la Construcción, Vol. 68, 543, e158, julio-septiembre 2016. ISSN-L: 0020-0883. doi: http://dx.doi.org/10.3989/ic.15.102

<!-- p. 3 -->

Análisis constructivo y estructural de la catedral de Valencia

Constructive and structural analysis of the cathedral of Valencia

(a) (b)

Figura 2.  Catedral de Valencia: a) sección transversal (Plano autor Ramiro Moya); b) esquema estructural.

\3.  ANÁLISIS CONSTRUCTIVO determinante para la estructura. Como hemos comentado en
la catedral de Valencia se disponen potentes muro-diafragPara conocer en profundidad el sistema estructural de la ca- mas, por tanto, si estos muros no son fundamentales frente a
tedral resulta fundamental hacer referencia al sistema cons- cargas gravitatorias, las preguntas a plantearse son: ¿por qué
tructivo de las iglesias denominadas «iglesias de reconquista» razón se construyen?, ¿qué función desempeñan?
(10). Se trata de un sistema heredado de la tradición romana,
en el que las iglesias están construidas con arcos diafragma Las investigaciones realizadas por la profesora Cassinello
transversalmente a la nave y que soportan la cubierta a dos plantean otras preguntas que desde un punto de vista difevertientes, generalmente de madera y vista desde el interior. rente convergen en las mismas conclusiones. Según CassiEl origen del sistema se halla en las abadías cistercienses de nello la respuesta se obtiene al superponer el mapa sísmico
los países mediterráneos, utilizado para cubrir las dependen- de Europa y el mapa de localización de las catedrales góticias monásticas. Posteriormente este sistema se traslada a cas españolas (11). Se observa que aquellas iglesias con una
la construcción de iglesias donde se realizan modificaciones geometría y unas proporciones que se alejan del modelo gócomo la introducción del ábside y las capillas abovedadas. tico tradicional se sitúan en zonas donde hay mayor riesgo
sísmico. Por tanto el sismo justifica las diferencias entre las
En el caso de la catedral de Valencia y de muchas otras situa- proporciones características del estilo gótico centroeuropeo
das en la franja del Mediterráneo, el sistema diafragmático y las del mediterráneo. Las particularidades de la catedral de
queda enmascarado por las bóvedas que, para garantizar la Valencia, en relación a sus proporciones y a la ineficacia esdurabilidad sustituyen a la cubierta de madera. En definitiva tructural de los arbotantes frente a cargas gravitatorias, quelos arcos diafragmáticos proporcionan la estabilidad tramo a dan justificadas en la estructura pétrea oculta bajo su terraza.
tramo, mientras que las bóvedas garantizan la durabilidad y
solidez de la cubierta, además de conseguir un espacio bajo Otro ejemplo que reproduce el sistema del gótico mediterráun mismo estilo. neo es la catedral de Tortosa, donde los potentes diafragmas
presentan huecos para circulación pero de proporciones más
La forma más elemental de bóveda de crucería es la que resul- reducidas que los de la catedral de Valencia. También se pota de la intersección de dos bóvedas de cañón (en este caso de drían citar la catedral de Sevilla, con diafragmas vistos desde
sección apuntada Figura 3). En sus aristas se concentran las el exterior, o la iglesia de Santa María del Mar de Barcelona.
tensiones como consecuencia de la pérdida de continuidad de
su curvatura, estas discontinuidades tienen que ser reforza- 3.1.  Toma de datos, interpretación constructiva
das por medio de los nervios. Como las cargas gravitatorias se
transmiten directamente a los nervios, el arco fajón aparen- Para llevar a cabo el análisis estructural de la catedral ha
temente está exento de carga, por lo que se podría suponer sido fundamental realizar una toma de datos exhaustiva que
que no son necesarios, ya que no desempeñan una función permita conocer el estado actual, para lo que se han anali-

Figura 3.  Esquema estructural de las bóvedas de la nave central de la catedral de Valencia.

Informes de la Construcción, Vol. 68, 543, e158, julio-septiembre 2016. ISSN-L: 0020-0883. doi: http://dx.doi.org/10.3989/ic.15.102 3

<!-- p. 4 -->

V. Llopis Pulido, A. Alonso Durá, E. Fenollosa, A. Martínez Boquera

zado aquellas intervenciones de carácter estructural y cons- 10 cm de espesor. Los ladrillos originales que pertenecían a
tructivo. De todas estas actuaciones la más relevante fue la la cubierta plana fueron recuperados y colocados posteriorrealizada por Ramiro Moya en 1976. En ella se eliminan las mente como remate final sobre la losa. En coronación de los
cubiertas inclinadas (Gilabert, 1773) y se recuperan las pri- muros se realizó un zunchado perimetral con un nervio de
mitivas terrazas planas que cubren la nave principal y las la- hormigón armado, y otros zunchos perpendiculares sobre los
terales (Figura 4). Estas cubiertas originales están formadas diafragmas de mampostería, en continuidad con los arcos fapor tabiques de ladrillo de 15 cm de espesor, separados 40 jones, además se consolidaron las grietas de los arbotantes.
cm, apoyadas directamente sobre las bóvedas. El espesor de
la bóveda central es de pie y medio (29 + 15 cm), y las latera- Con la información recopilada y con el levantamiento geoméles de un pie (29 cm). Sobre los tabiques apoyan baldosas de trico a partir del escáner láser (12) se ha elaborado un modelo
40 cm de longitud sujetas por una mezcla de cal, yeso y arena. 3d que reproduce el sistema constructivo de la cubierta de la
catedral. En la figura 5a se observa el entramado murario con
Para solucionar los daños provocados por las continuas fil- los diafragmas, la continuidad con los arbotantes, la dispositraciones se aisló la cubierta por medio de una lámina imper- ción y tipo de bóvedas, en la figura 5b se muestra la distribumeabilizante y se construyó una losa de hormigón armado de ción de los tabiquillos sobre las bóvedas.

(a) (b)

Figura 4.  Intervención: a) cubierta original; central: losa de hormigón armado; b) zuncho hormigón armado sobre muros. (Fotos cedidas
por Tirso de Ávila).

(a) (b)

Figura 5.  Interpretación cubierta: a) entramado murario, bóvedas y tabiques sobre nervios; b) disposición y orientación de
los tabiquillos.

4 Informes de la Construcción, Vol. 68, 543, e158, julio-septiembre 2016. ISSN-L: 0020-0883. doi: http://dx.doi.org/10.3989/ic.15.102

<!-- p. 5 -->

Análisis constructivo y estructural de la catedral de Valencia

Constructive and structural analysis of the cathedral of Valencia

\4.  ANÁLISIS NUMÉRICO degradación de su rigidez por el nivel tensional y en el efecto
en la respuesta en función del tamaño de la malla empleada.
Por medio del análisis estructural es posible demostrar la
capacidad estructural de los diafragmas para recibir los es- La degradación de una zona del material que tiene un nivel de
fuerzos horizontales y estudiar su influencia en la mejora del deterioro se representa mediante «huecos». El índice d [1] indica
comportamiento sísmico de la catedral. Además de analizar y el grado de deterioro del material (0 ≤ d ≤ 1), siendo el valor 0 el
comparar la efectividad del resto de elementos constructivos estado no dañado y la unidad el deterioro total del área resistente.
por medio de diferentes modelos de cálculo.
S – S'
d = [1]El análisis de elementos finitos se realiza por medio del soft- S
ware ANGLE, a partir de la geometría real y en base a su con-
S representa la superficie total y S′ el área resistente efectiva.figuración constructiva se generan los modelos de cálculo con
La diferencia S – S′ expresa la superficie de huecos que se hanherramientas CAD. Para evaluar el comportamiento sísmico de
producido en el material. La relación entre la tensión de Cau-la catedral se utiliza el análisis no lineal pushover (13). El mé-
chy σ′ y la tensión efectiva que actúa sobre la sección resis-todo empleado para simular el comportamiento de la piedra y
tente efectiva (σ), es calculada por la condición de equilibrioel ladrillo es el «modelo de daño», uno de los métodos más rigurosos para reproducir la respuesta de los materiales frágiles.
1 – d 1 – d σ = ( )σ´= ( )Eε [2]
4.1.  Propiedades mecánicas de los materiales
Este índice escalar es suficiente para representar correctamenSe han considerado dos tipos de materiales, la sillería para te el comportamiento de materiales como las fábricas de ladripilares y muros y el ladrillo para las bóvedas y para el relle- llo y de piedra. Siendo D la matriz de elasticidad para un mano del núcleo central de pilares (14), (15). Para establecer las terial isótropo, la matriz constitutiva D′ es calculada como [3]:
propiedades mecánicas se han considerado los ensayos rea-
1– dlizados en los sillares del puente de la Trinidad de Valencia D' = ( )D [3]
(16), ya que la procedencia de esta piedra es la misma que la
de la catedral. Los resultados de estos ensayos se han corre- Siendo r máx {r0,rn}, A el parámetro que depende de la energido ligeramente al alza para tener en cuenta que las probe- gía disipada por unidad de volumen para un proceso de tractas se tomaron de sillares situados en el exterior, sometidos ción uniaxial, el índice de daño es [4]:
durante siglos a la degradación medioambiental y perdiendo
densidad. En el análisis estructural realizado se han utilizado r0 ⎧ ⎛ rn ⎞ ⎫valores conservadores del lado de la seguridad, distinguiendo d = 1– exp ⎨⎪ A 1– ⎬⎪ [4] r ⎩⎪ ⎝⎜ r0 ⎠⎟ ⎭⎪entre cuatro materiales (17), (18) (Tabla 1).

4.2.  Modelo constitutivo: modelo de daño 4.3.  Acción sísmica

La mecánica de daño introduce cambios a nivel microestruc- Para analizar el comportamiento sísmico de la estructura se
tural del material a través de variables internas. Estas varia- utiliza el método de análisis estático no lineal pushover o por
bles modifican la influencia de la historia del comportamien- empujes incrementales según el Eurocódigo 8 (21). Se trata
to del material en la evolución de las tensiones. La aparición de una técnica eficiente que permite estudiar la capacidad y
de fisuras y la evolución de las mismas en el tiempo se descri- la resistencia-deformación de la estructura bajo los efectos
ben como las trayectorias de los puntos que están dañados. de un terremoto. La acción sísmica se introduce en la direc-
ción de la estructura a analizar, sometiéndola a un patrón
La fractura queda representada como un efecto de daño local de cargas horizontales que se incrementan hasta alcanzar
que se puede caracterizar en función de la resistencia a com- su capacidad máxima. En su aplicación se utiliza el espectro
presión y a tracción del material, de los parámetros conocidos de aceleraciones para la ciudad de Valencia propuesto por la
del material y de las funciones que controlan la evolución de norma española NCSE-02 (20). La intersección entre la curva
la fisuración según el estado sucesivo de las tensiones en cada de demanda y la de capacidad define el punto de desempeño
uno de los puntos. o Performance Point. Este punto señala el movimiento que se
puede esperar en el punto más elevado de la estructura para
El análisis estructural se ha realizado mediante el programa las acciones sísmicas de cálculo definido por el espectro.
de Elementos Finitos en régimen no lineal ANGLE, mediante
una aplicación del modelo de daño isótropo (19). El modelo A partir de la posición del punto de desempeño respecto a los
de daño empleado se basa en la diferencia de comportamien- puntos de cedencia y capacidad última se definen los umbrato en compresión y tracción de este tipo de materiales, en la les de los estados de daño (Sd) (Figura 6).

Tabla 1.  Clasificación de los materiales.

D E fc ft Gf + Material (t/m3) (N/mm2) (N/mm2) (N/mm2) (Nmm/mm2)

Sillería 2,2 7.500 12 0,35 0,3

Relleno sillería 2,0 2.500 8 0,25 0,2

Ladrillo 1,8 3.500 3,5 0,15 0,1

Relleno bóveda 1,5 1.000 3 0,2 0,15

Informes de la Construcción, Vol. 68, 543, e158, julio-septiembre 2016. ISSN-L: 0020-0883. doi: http://dx.doi.org/10.3989/ic.15.102 5

<!-- p. 6 -->

V. Llopis Pulido, A. Alonso Durá, E. Fenollosa, A. Martínez Boquera

Dy Du El análisis pushover permite evaluar la vulnerabilidad de la
estructura y por tanto el modelo se aplica a la dirección trans- Au
versal de la nave, por ser la más débil frente a sismo, por ello
se modelan tres pórticos y se toman como valores de referen-
cia los correspondientes al central. Sd1 = 0,7 Dy
Sd2 = Dy
A partir del estudio constructivo elaborado se plantean dife-
Sd3 = Dy + 0,25 (Du – Dy)
rentes variaciones del modelo según los elementos constructi-
Sd4 = Du vos considerados. El primer modelo reproduce la situación ac- Sd1 Sd2 Sd3 Sd4
tual, incluyendo la losa de hormigón armado (construida en la
Figura 6.  Umbrales de los estados de daño. intervención de 1976), además de los diafragmas y de los arbo-
tantes, garantizando la continuidad de la estructura muraria.
Para definir la acción sísmica se recurre a métodos de proba- El segundo modelo de cálculo mantiene la losa de hormigón
bilidad. En este estudio se han utilizado dos eventos sísmicos, pero prescinde de los arbotantes manteniendo sólo los diafragel espectro de diseño que corresponde a un período de retor- mas, lo que nos permitirá comprobar su función estructural.
no de 475 años y el sismo máximo con un período de retor- En la tercera, cuarta y quinta simulación se elimina la losa de
no de 950 años. El período de retorno es una expresión que hormigón armado para analizar la estructura original de la caindica el promedio de tiempo en años que transcurre entre la tedral y se combina con y sin los arbotantes y diafragmas.
ocurrencia de un seísmo que produce daños de una severidad
igual o superior a una determinada. 5.  RESULTADOS

4.4.  Modelo estructural Con carácter general al tratarse de una estructura rígida, las
propiedades dinámicas del modelo se sitúan en las zonas
El análisis se centra en el tramo central de la catedral, forma- donde el espectro es más elevado y por tanto las aceleraciones
do por las tres naves y dos crujías correspondientes al trazado efectivas son mayores. Para cargas gravitatorias las tensiones
primitivo. Éste es el tramo más vulnerable frente a acciones máximas se producen en la base de los pilares centrales alsísmicas, ya que en la dirección longitudinal del templo los canzando valores máximos de 3 N/mm2 muy por debajo de la
empujes son absorbidos tramo a tramo y resistidos por la ca- resistencia a compresión considerada en el cálculo del orden
becera y los pies. El cálculo contempla cargas gravitatorias de 12 N/mm2. El índice de daño se concentra en el intradós de
y acciones sísmicas transversales al edificio, actuando sobre las claves de los arcos advirtiéndose que los arbotantes supeeste tramo central (22), (23). riores no colaboran al equilibrio de la estructura.

Se elabora un modelo por medio de elementos finitos tipo 5.1.  Situación actual: modelo con losa, arbotantes
«sólido» de unos 50 cm de tamaño medio, siguiendo los cri- y diafragmas
terios de la denominada «macro-modelización», modelo más
utilizado en el análisis de estructuras complejas (24). La es- En las gráficas se compara la capacidad de la estructura con la
tructura muraria y los pilares están formados por sillares ca- demanda provocada por el movimiento del terreno. La máxima
reados por el exterior y con relleno de argamasa en su núcleo, deformación horizontal obtenida se corresponde con el punto
por tanto los elementos utilizados modelizan la fábrica como de desempeño, situado en la intersección del espectro de caun continuo, con las propiedades mecánicas homogeneizadas pacidad de la estructura con la curva de demanda. Teniendo
piedra-argamasa. Ello permite una menor exigencia de cálcu- en cuenta un sismo con un período de retorno de 475 años, el
lo dada la enorme envergadura del objeto de estudio que con- punto de desempeño se sitúa previo a la fase elástica por lo tantiene más de 16.500 elementos. Se ha considerado un terreno to lejano al colapso (Figura 7a). En el sismo de 950 el punto de
de tipo medio según especificaciones de la Norma Sismorre- desempeño indica un nivel de daño medio-severo (Sd3) según
sitente NCSE-02, que se ajusta al tipo del suelo de la catedral. la tabla de clasificación de los umbrales de daño (Figura 7b).

a/g Performance Point (SDOF) = 0,79 (MDOF) = 1,00 cm. Ductil (mu) = 1,00 a/g Performance Point (SDOF) = 1,09 (MDOF) = 1,34 cm. Ductil (mu) = 1,26
0,200 0,250

0,180 0,225

0,160 0,200

0,140 0,175

0,120 0,150

0,100 0,125

0,080 0,100

0,060 0,075
Curva de capacidad y Curva de capacidad y
0,040 simplificada bilineal 0,050 simplificada bilineal
Curva de demanda elástica Curva de demanda elástica
0,020 Curva de ductilidad 0,025 Curva de ductilidad
D.Y cm (a) D.Y cm (b)

0,50 1,00 1,50 2,00 2,50 3,00 3,50 4,00 4,50 5,00 0,40 0,80 1,20 1,60 2,00 2,40 2,80 3,20 3,60 4,00
Figura 7.  Determinación del punto de desempeño: a) sismo con tiempo de retorno de 475 años;
b) sismo con tiempo de retorno de 950 años.

6 Informes de la Construcción, Vol. 68, 543, e158, julio-septiembre 2016. ISSN-L: 0020-0883. doi: http://dx.doi.org/10.3989/ic.15.102

<!-- p. 7 -->

Análisis constructivo y estructural de la catedral de Valencia

Constructive and structural analysis of the cathedral of Valencia

lo que supone daños leves. En el caso de un sismo con un
período de retorno de 950 años el performance point se sitúa
cercano al punto de rotura (Figura 9b) y por tanto los daños
son graves.

Puede observarse que el daño se concentra en el intradós de
los arcos de la nave central y trasdós de los arcos de las naves
laterales (Figura 10). Aunque los daños son graves en estas
zonas no se llega a alzanzar el colapso global.

5.3.  Situación original de la catedral: modelo sin
losa, con diafragmas y con arbotantes

En este caso, como muestra la Figura 11, la situación del pun-
to de desempeño indica un nivel de daño medio severo (Sd3)
para un sismo con tiempo de retorno de 475 años. Al eliminar
la losa del modelo el punto de rotura desciende, por tanto la
Figura 8.  Índice de daño para el desplazamiento máximo. estructura es más vulnerable. Los daños obtenidos se sitúan
entre daños moderados y daños graves.
En la Figura 8 el índice de daño se concentra en el intradós
de los arcos y se observa como los contrafuertes entran en El cálculo realizado explica los daños históricos sufridos por
carga, aumenta el daño en el trasdós del arco justo donde se la catedral. Como puede observarse en la Figura 12a el daño
produce la disminución de su sección. Se alcanza la fisuración en arbotantes se concentra en zonas que han tenido que ser
en las zonas indicadas, pero se trata de daños leves sin llegar intervenidas y en arcos de las naves laterales (Figura 12b).
al colapso global de la estructura.
5.4.  Modelo sin losa, sin arbotantes y con
5.2.  Función de los arbotantes: modelo con losa, diafragmas
diafragmas y sin arbotantes
En la simulación en la que se elimina losa y no se consideDe nuevo para un sismo de 475 años el punto de desempeño ran los arbotantes el punto de desempeño indica un nivel
se sitúa en el primer tramo de la fase inelástica (Figura 9a) de daño completo (Sd4) (Figura 13a). Éstos se concentran

a/g Performance Point (SDOF) = 0,77 (MDOF) = 0,97 cm. Ductil (mu) = 1,06 a/g Performance Point (SDOF) = 1,07 (MDOF) = 1,34 cm. Ductil (mu) = 1,36
0,200 0,250
0,180 0,225
0,160 0,200
0,140 0,175
0,120 0,150
0,100 0,125
0,080 0,100
0,060 Curva de capacidad y 0,075 Curva de capacidad y
simplificada bilineal simplificada bilineal0,040 0,050 Curva de demanda elástica Curva de demanda elástica
Curva de ductilidad Curva de ductilidad0,020 (a) 0,025 (b) D.Y cm D.Y cm

0,40 0,80 1,20 1,60 2,00 2,40 2,80 3,20 3,60 4,00 0,40 0,80 1,20 1,60 2,00 2,40 2,80 3,20 3,60 4,00

Figura 9.  Determinación del punto de desempeño: a) sismo con tiempo de retorno de 475 años; b) sismo con tiempo de retorno de 950 años.

Figura 10.  Índice de daño para el desplazamiento máximo para un sismo con tiempo
de retorno de 950: a) alzado; b) perspectiva.

Informes de la Construcción, Vol. 68, 543, e158, julio-septiembre 2016. ISSN-L: 0020-0883. doi: http://dx.doi.org/10.3989/ic.15.102 7

<!-- p. 8 -->

V. Llopis Pulido, A. Alonso Durá, E. Fenollosa, A. Martínez Boquera

a/g Performance Point (SDOF) = 0,74 (MDOF) = 0,93 cm. Ductil (mu) = 1,15 a/g Performance Point (SDOF) = 1,03 (MDOF) = 1,29 cm. Ductil (mu) = 1,49
0,200 0,250
0,180 0,225
0,160 0,200
0,140 0,175
0,120 0,150
0,100 0,125
0,080 0,100

0,060 0,075 Curva de capacidad y Curva de capacidad y
simplificada bilineal simplificada bilineal0,040 0,050 Curva de demanda elástica Curva de demanda elástica
0,020 Curva de ductilidad (b) D.Y cm (a) 0,025 Curva de ductilidad D.Y cm

0,40 0,80 1,20 1,60 2,00 2,40 2,80 3,20 3,60 4,00 0,40 0,80 1,20 1,60 2,00 2,40 2,80 3,20 3,60 4,00

Figura 11. Determinación del punto de desempeño: a) sismo con tiempo de retorno de 475 años;
b) sismo con tiempo de retorno de 950 años.

Figura 12. Índice de daño del desplazamiento máximo para un sismo con tiempo de retorno de 950 años: a) resultados sobre el modelo; b)
daños observados en arcos fajones de las naves laterales y arbotantes.

en diafragmas extendiéndose en intradós de arcos y en los lo que conduce a unos daños clasificados como graves que
huecos de los cerramientos laterales de la nave principal llegarían a producir el colapso. Al no considerar los diafrag-
(Figura 13b). Se producen daños graves llegando al colapso mas ni la losa, se pierde el concepto de caja, por lo que la
global para el escenario de sismo con tiempo de retorno de capacidad sísmica transversal de la estructura comienza
950 años. a ser insuficiente. Los desplazamientos son mayores como
consecuencia de la pérdida de unidad del conjunto. El daño
5.5.  Modelo sin losa, con arbotantes se concentra en arcos fajones y en la parte superior e inferior
y sin diafragmas de los huecos de los muros formeros, alcanzándose el colap-
so de los arbotantes en la zona donde la sección del arco se
En este análisis se obtiene el valor más alto del punto de des- reduce, por ser el punto más vulnerable frente a la rotura
empeño de todas las simulaciones realizadas (Figura 14a) (Figura 14b).

a/g Performance Point (SDOF) = 1,06 (MDOF) = 1,31 cm. Ductil (mu) = 1,52
0,250
0,225
0,200
0,175
0,150
0,125
0,100
0,075 Curva de capacidad y
simplificada bilineal0,050 Curva de demanda elástica
0,025 Curva de ductilidad (a) (b) D.Y cm

0,40 0,80 1,20 1,60 2,00 2,40 2,80 3,20 3,60 4,00

Figura 13. Sismo con un tiempo de retorno de 950 años: a) punto de desempeño; b) índice de daño.

8 Informes de la Construcción, Vol. 68, 543, e158, julio-septiembre 2016. ISSN-L: 0020-0883. doi: http://dx.doi.org/10.3989/ic.15.102

<!-- p. 9 -->

Análisis constructivo y estructural de la catedral de Valencia

Constructive and structural analysis of the cathedral of Valencia

a/g Performance Point (SDOF) = 1,61 (MDOF) = 2,00 cm. Ductil (mu) = 1,70
0,250
0,225
0,200
0,175
0,150
0,125
0,100
0,075 Curva de capacidad y
0,050 simplificada bilineal
Curva de demanda elástica
0,025 Curva de ductilidad (a) (b) D.Y cm

0,40 0,80 1,20 1,60 2,00 2,40 2,80 3,20 3,60 4,00
Figura 14.  Sismo con un tiempo de retorno de 950 años: a) punto de desempeño; b) índice de daño.

\6.  CONCLUSIONES puesto que se pierde el sentido de la estructura muraria, pro-
duciéndose el colapso.
Al tratarse de una estructura de gran rigidez los períodos de
oscilación obtenidos son bajos por lo que se sitúan en el es- A la vista de los distintos resultados, es evidente que tanto
pectro de demanda donde las aceleraciones son más elevadas. el diafragma como los arbotantes son necesarios para el co-
rrecto comportamiento de la estructura de la catedral frente
Se ha comprobado que la capacidad sísmica de la catedral de a un movimiento sísmico. No obstante hay que resaltar que la
Valencia, en su situación actual, es suficiente para soportar el pérdida del diafragma resulta más determinante en el comterremoto con un período de retorno de 475 años. Los daños portamiento del conjunto.
esperados, de producirse, serían leves. La situación empeora
cuando se considera un terremoto con tiempo de retorno de En aquellos modelos en los que se ha considerado la losa de
950 años. En este caso los daños principales se sitúan en el hormigón armado de la cubierta se ha comprobado un auintradós de los arcos y se extiende en los diafragmas y arbo- mento de la rigidez del conjunto. Frente a la opinión extentantes. dida de que un aumento de peso en altura supone una modi-
ficación negativa del comportamiento dinámico del edificio,
La eliminación de los arbotantes impide la continuidad en el en este caso supone un incremento de peso que es bajo en
sistema murario, perdiéndose la conexión entre los diafrag- relación al peso total por tanto no modifica las propiedades
mas y los contrafuertes. Los daños obtenidos son más gra- dinámicas. Sin embargo sí que hay un aumento de la rigidez,
ves, aunque no se llega al colapso global de la estructura. La atando los muros longitudinales y los diafragmas, favoreciensimulación en la que se elimina la losa, pero se mantienen do el comportamiento frente a sismo.
los diafragmas y los arbotantes que coincide con la situación
primitiva de la catedral, reproduce los daños históricos su- Gracias a la forma y posición de los arbotantes, estos arcos
fridos y las deformaciones actuales en los arbotantes y arcos se convierten en diafragmas que garantizan la continuidad
fajones. Cuando no se consideran ni los arbotantes ni la losa, con los contrafuertes y generan una estructura muraria que
el nivel de daños comienza a ser severo tanto en los diafrag- arriostra transversalmente, funcionando como «muros de
mas como en la parte superior e inferior de los huecos de los cortante». Este entramado de muros ortogonales caractecerramientos de la nave central. En esta simulación se produ- rístico del «Gótico mediterráneo» dota a la estructura de la
cen daños graves que conducirían al colapso. El modelo sin la catedral de la rigidez y resistencia necesaria configurando la
losa ni los diafragmas representa la situación más vulnerable forma que mejor responde frente a movimientos sísmicos.

REFERENCIAS

(1) Heyman, J. (2004). Análisis de estructuras: un estudio histórico. Madrid: Reverte.
(2) Mira, E., Zaragozá, A. (2003). Una arquitectura gótica mediterránea. Valencia: Conselleria de Cultura i Educació.
(3) Cassinello, M. (2004). Trazado y estabilidad de la arquitectura gótica. Cuadernos Intemac, 53
(4) Medina, J.M. (2014). Clasificación inédita de catedrales góticas españolas en función de su iluminación. Informes de la
Construcción, 66(535): e028, doi: http://dx.doi.org/10.3989/ic.12.132.
(5) Cassinello, P. (2005). Influencia de los terremotos históricos en la construcción de las catedrales góticas españolas. An-
nali Di Architettura: Rivista del centro Internazionale di Studi di Architettura “Andrea Palladio” (17): 9-20.
(6) Roca, P., Cervera, M., Pelà, L., Clemente, R., Chiumenti, M. (2013). Continuum FE Models for the Analysis of Mallorca
Cathedral. Engineering Structures, 46: 653-670, doi: http://dx.doi.org/10.1016/j.engstruct.2012.08.005.
(7) ANGLE. (2014). Structural Analysis Software for Finite Element. Developed by A. Alonso. Department of Mechanics of
the Continuous Medium and Theory of Structures. Universitat Politècnica de València, Spain.
(8) Marques, R., Lourenço, P.B. (2013). A model for pushover analysis of confined masonry structures: Implementation and
validation. Bulletin of Earthquake Engineering, 11(6): 2133-2150, doi: http://dx.doi.org/10.1007/s10518-013-9497-5.

Informes de la Construcción, Vol. 68, 543, e158, julio-septiembre 2016. ISSN-L: 0020-0883. doi: http://dx.doi.org/10.3989/ic.15.102 9

<!-- p. 10 -->

V. Llopis Pulido, A. Alonso Durá, E. Fenollosa, A. Martínez Boquera

(9) Oñate, E., Hanganu, A., Barbat, A. (1996). Structural Analysis and Durability Assessment of Historical Constructions
using a Finite Damage Model. Barcelona: CIMNE.
(10) Zaragozá Catalán, A. (1990). Iglesias de arcos diafragma y armadura de madera en la arquitectura medieval valencia-
na. Valencia: Universidad Politécnica de Valencia.
(11) Cassinello, P. (2005, 27 de enero). Racionalidad sísmica en la arquitectura ojival: tipos estructurales y constructivos. En
Cuarto Congreso Nacional de Historia de la Construcción, pp. 249-258. Cádiz: Instituto Juan de Herrera.
(12) Casinello, P., Álvarez, M., Rodríguez, R., Miranda, M., Ramos, L.A., Azorín, V. (2014). Levantamiento del comedor del
IETcc: una crónica de la innovación en la representación de edificios. Informes de la Construcción, 66(536): e039, doi:
http://dx.doi.org/10.3989/ic.14.023.
(13) Vargas, Y.F., Pujades, L.G., Barbat, A.H., Hurtado, J.E. (2013). Incremental Dynamic Analysis and Pushover Analysis. A
Probabilistic Comparison. Computational Methods in Applied Sciences, 26: 293-308, doi: http://dx.doi.org/10.1007/978-
94-007-5134-7_17.
(14) Ramos, A., León, J. (2013). Classification of backfill at the extrados of masonry vaults. Informes de la Construccion,
65(532): 471-480, doi: http://dx.doi.org/10.3989/ic.12.062.
(15) Orduña, A., Roeder, G., Peña, F. (2007). Evaluación sísmica de construcciones históricas de mampostería: comparación
de tres modelos de análisis. Revista de Ingeniería Sísmica, 77: 71-88.
(16) Navarro, A., Lizondo, L., Martínez, A., Alonso, A. (2009, 21 de octubre). Origen, influencias y realidad en la construcción
del puente de Trinidad de Valencia. En Congreso Nacional de Historia de la Construcción, pp. 989-1002. Valencia.
(17) Alonso, A., Martínez, A., Llopis, V., Moreno, J. (2012) Structural Behaviour Analysis of the Cathedral of Valencia. Struc-
tural Analysis of Historical Constructions. En SAHC 2012 8th International Conference on Structural Analysis of His-
torical Constructions, pp. 185-192. Poland.
(18) Lluis i Ginovart, J., Costa A., Fortuny, G., Solà-Morales, P., Toldrà, J.M. (2013). Proceso de rotura de una cúpula oval en
la catedral de Tortosa. Análisis del mecanismo de colapso. Informes de la Construcción, 65(532): 509-517, doi: http://
dx.doi.org/10.3989/ic.12.069.
(19) Oller, S. (2001). Fractura mecánica. Un enfoque global. Barcelona: CIMNE.
(20) NCSE-02. (2002). Real Decreto 997/2002, de 27 de septiembre, por el que se aprueba la Norma de Construcción Sismo-
resistente (NCSE-02). Boletín Oficial del Estado (244): 35898-35967. España: Ministerio de Fomento.
(21) EC-8 (2004). ENV 1998-4:2004 Eurocode 8: Design of structures for earthquake resistence. Part1: General rules,
seismic actions and rules for buildings.
(22) Irizarry, J., Podestà, S., Resemini, S. (2003, 1-4 de abril). Curvas de capacidad para edificios monumentales: la iglesia
Santa María del Mar de Barcelona. En Segundo Congreso Nacional de Ingeniería Sísmica, pp. 541-555. Málaga.
(23) Vacas, A. (2009). Análisis sísmico de las catedrales góticas mediante el método del espectro de capacidad. Universidad
Politécnica de Cataluña.
(24) Roca, P., Cervera, M., Gariup, G., Pela, L. (2010). Structural Analysis of Masonry Historical Constructions. Classi-
cal and Advanced Approaches. Archives of Computational Methods in Engineering, 17: 299-325, doi: http://dx.doi.
org/10.1007/s11831-010-9046-1.

\* * *

10 Informes de la Construcción, Vol. 68, 543, e158, julio-septiembre 2016. ISSN-L: 0020-0883. doi: http://dx.doi.org/10.3989/ic.15.102
