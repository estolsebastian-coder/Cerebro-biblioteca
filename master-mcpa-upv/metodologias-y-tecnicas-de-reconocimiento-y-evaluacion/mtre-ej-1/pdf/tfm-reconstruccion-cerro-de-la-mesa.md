---
type: libro
title: "TFM-RECONSTRUCCION CERRO DE LA MESA"
author: ""
categoria: "Metodologías y técnicas de reconocimiento y evaluación"
paginas: 74
extraccion: "texto (OCR pendiente)"
fuente: "local:D:/UPV/MCPA/Asignaturas/Metodologías y técnicas de reconocimiento y evaluación/MTRE. Ej. 1/PDF/TFM-RECONSTRUCCION CERRO DE LA MESA.pdf"
convertido: 2026-10-16
---

# TFM-RECONSTRUCCION CERRO DE LA MESA

> Texto extraído de `Metodologías y técnicas de reconocimiento y evaluación\MTRE. Ej. 1\PDF\TFM-RECONSTRUCCION CERRO DE LA MESA.pdf` (74 páginas, texto (OCR pendiente)). El PDF original está en el disco D: (UPV\MCPA\Asignaturas); `<!-- p. N -->` marca el inicio de cada página.

<!-- p. 1 -->

UNIVERSIDAD COMPLUTENSE DE MADRID

FACULTAD DE GEOGRAFÍA E HISTORIA

MÁSTER UNIVERSITARIO EN
TECNOLOGÍAS DE LA INFORMACIÓN GEOGRÁFICA

TRABAJO FIN DE MÁSTER
CURSO 2019‐2020

LAS TIG AL SERVICIO DE LA ARQUEOLOGÍA NO INVASIVA:
RECONSTRUCCIÓN TOPOGRÁFICA Y ARQUEOLÓGICA DEL
CERRO DE LA MESA (ALCOLEA DE TAJO, TOLEDO)

GIT AT THE SERVICE OF NON-INVASIVE ARCHAEOLOGY: TOPOGRAPHIC AND
ARCHAEOLOGICAL RECONSTRUCTION OF CERRO DE LA MESA (ALCOLEA DE
TAJO, TOLEDO)

JULEN PÉREZ DE IRIARTE NAVARLAZ

CONVOCATORIA: OCTUBRE

TUTORES: IRENE ORTIZ NIETO-MÁRQUEZ
C.A.I. de Arqueometría y Análisis Arqueológico de la UCM
LUIS MIGUEL TANARRO GARCÍA
Departamento de Geografía. Facultad de Geografía e Historia de la UCM

<!-- p. 2 -->

AGRADECIMIENTOS

Sobre todo, quiero agradecer a todas aquellas personas que, de una manera u otra, me han ayudado
a llegar hasta aquí. En primer lugar, a mis tutores, Irene y Luis Miguel, por sus enseñanzas, consejos
y su predisposición en todo momento a colaborar, más meritorio si cabe en un año difícil como este,
en el que aun así han conseguido desinteresadamente que contara con toda la información necesaria
tanto del yacimiento como de los fotogramas históricos. A su vez, quiero agradecer a Teresa Chapa
y a Juan Pereira la posibilidad de realizar mi trabajo en el valioso yacimiento del Cerro de la Mesa,
a todo el Proyecto Arqueológico BHIT en general y al CAI de Arqueometría de la UCM. Por
supuesto, a mis padres y mi hermana por hacer posible esta aventura, a todas las grandes personas
que me llevo de Madrid, Grecia y Orcasitas, y a las que llevan conmigo toda mi vida.

<!-- p. 3 -->

RESUMEN

La Arqueología no invasiva encuentra en las TIG un soporte fundamental en su propósito de
minimizar el impacto material sobre el patrimonio arqueológico, pero también en el
beneficio que supone, para la investigación, la adquisición de información complementaria
que permiten las tecnologías geoespaciales. El presente trabajo parte con el objetivo de
profundizar en la aplicación de herramientas procedentes del ámbito de las TIG, como son
la técnica Structure From Motion (SfM), asociada a la fotogrametría digital, y el LiDAR,
que se combinan para integrar una metodología de estudio no invasivo sobre el yacimiento
arqueológico del Cerro de la Mesa (Alcolea de Tajo, Toledo). La utilización de ambas
técnicas forma parte de un proceso de reconstrucción que se plantea tanto en el plano
topográfico como arqueológico, donde el empleo de fotogramas aéreos históricos aporta la
información necesaria para restaurar la morfología del yacimiento, cuyas características
originales se han perdido, estableciendo la base desde la cual situar la interpretación
arqueológica. Esta reconstrucción se plasma en los productos cartográficos obtenidos tras la
aplicación, cuyo tratamiento, análisis y comparación permite no solo revalorizar estas
herramientas en el estudio del Cerro de la Mesa sino también proponer, y en base a sus
limitaciones, mejorar una metodología de implantación aplicable a otros casos de estudio
semejantes en Arqueología.

PALABRAS CLAVE: Tecnologías de la Información Geográfica (TIG), Arqueología no
invasiva, Fotogrametría digital, LiDAR, Edad del Hierro.

ABSTRACT

Non-invasive Archaeology finds in the group of GIT an essential support for the purpose of
minimizing physical impact over the Archaeological Heritage, but also for the profit of
acquiring supplementary information for the investigation allowed by geospatial tools. The
present work starts with the objective of delving into the application of GIT tools, like the
SfM technique, associated with digital photogrammetry, and LiDAR, that are combined to
integrate a non-invasive methodology related to the archaeological settlement of Cerro de
la Mesa (Alcolea de Tajo, Toledo). The application of both techniques takes part of a
reconstruction process that is raised in a topographical level, where the use of historical
aerial photographs provides the necessary information to restore the modified morphology
of the settlement, establishing the base from which the archaeological interpretation bust be
located. This reconstruction is embodied in the cartographic products obtained after the
application, where data processing, analysis and comparison allow the revaluation of these
tools but also, knowing their limits, the proposal and improvement of an applicable
methodology in other case studies related to Archaeology.

KEYWORDS: Geographical Information Technologies (GIT), Non-invasive Archaeology,
Digital Photogrammetry, LiDAR, Iron Age.

<!-- p. 4 -->

ÍNDICE

\1. INTRODUCCIÓN 8

\2. OBJETIVOS 8-9

\3. EL YACIMIENTO DEL CERRO DE LA MESA (ALCOLEA DE TAJO,
TOLEDO) 10-16

3.1. Situación geográfica 10-12
3.2. La ocupación del Cerro de la Mesa, apogeo y abandono 13-14
3.3. La presa de Azután: transformación completa del entorno 14-16

\4. ESTADO DE LA CUESTIÓN. LAS TIG Y SU APLICACIÓN EN
ARQUEOLOGÍA 16-18

4.1. Trayectoria y evolución 16-18
4.2. Posiciones teóricas 18

\5. METODOLOGÍA: RECONSTRUCCIÓN TOPOGRÁFICA
Y ARQUEOLÓGICA DEL CERRO DE LA MESA 19-37

5.1. Técnica fotogramétrica “Structure from Motion”
aplicada a fotografías áreas históricas del entorno del Cerro de la Mesa 19-30

5.1.1. Material de partida: fotografías aéreas históricas
5.1.2. Determinación de los parámetros de la cámara.
5.1.3. Establecimiento de los puntos de control (PC) para
georreferenciar la nube de puntos 3D
5.1.4. Aerotriangulación o alineación de las fotografías y obtención del modelo 3D

5.2. Aplicación de la tecnología LIDAR a la
prospección arqueológica del Cerro de la Mesa. 30-37

5.2.1. Planteamiento, material de partida y preparación de los datos.
5.2.2. Tratamiento visual del LIDAR: el programa Relief Visualization Toolbox

\6. RESULTADOS: PRESENTACIÓN, CARACTERÍSTICAS
Y TRATAMIENTO SIG DE LOS PRODUCTOS CARTOGRÁFICOS 37-56

6.1. Restitución paleotopográfica: productos derivados e interpretación 37-49

6.1.1. Precisión y calidad de los productos cartográficos.
6.1.2. Análisis arqueológico de la observación de las ortofotos y el modelo 3D
6.1.3. Tratamiento del Modelo Digital de Superficies (MDS) en un SIG.
Implicación en la investigación arqueológica

6.2. LIDAR: utilidad y complementación con los resultados del georradar (GPR) 50-55

6.2.1. Interpretación de las visualizaciones generadas con el programa RVT
6.2.2. Resultados del georradar e integración en la reconstrucción topográfica

<!-- p. 5 -->

\7. DISCUSIÓN 56-59

\8. CONCLUSIONES 59-60

\9. BIBLIOGRAFÍA 61-71

ANEXOS 72-73

LISTADO DE FIGURAS

Figura 3.1: Localización del área protegida del Cerro de la Mesa: regional en Castilla la Mancha-Toledo (AB), comarcal sobre el MTN 50 (C) y aérea (D) mediante la ortofoto del PNOA 2019.

Figura 3.2: Situación aproximada del vado histórico de Puente Pinos sobre el Mapa Topográfico Nacional
de 1950 (Fondo) y de 2007 (Abajo dcha.), ya sumergido bajo el embalse de Azután.

Figura 3.3 Límites geográficos de los vettones según las fuentes históricas y localización de los principales
yacimientos (Álvarez Sanchís, 2003). En triángulo rojo, situación del yacimiento del Cerro de la Mesa.

Figura 3.4: Evolución de la alteración morfológica del Cerro de la Mesa. Límite original del yacimiento
extraído de la ortofoto del Vuelo AMS B (izda.) en 1956, y en su situación posterior tras la construcción de la
presa en el Vuelo Nacional, en 1986 (centro) y el resto de infraestructura actual, en la ortofoto del PNOA
2019 (dcha.).

Figura 3.5.A: Panorámica del entorno del Cerro de la Mesa en la actualidad, después de todas las
transformaciones sufridas. Señalada, la zona protegida del yacimiento (Charro Lobato et al., 2009).

Figura 3.5.B: Vista general de la zona excavada del yacimiento arqueológico (Cabrera y Moreno, 2014).

Figura 5.1: Fundamentos de la estereoscopía artificial (izda.) y del solapamiento de los vuelos
fotogramétricos (dcha.) (Quirós Rosado, 2014).

Figura 5.2.A: Fases de realización del vuelo de la serie A a lo largo del territorio español, entre 1945 y 1946
(Quirós y Fernández, 1997).

Figura 5.2.B: Figura 5.2.B. Portada del informe final del Proyecto 54-AM-78 que realizó el vuelo
fotogramétrico de la Serie B entre 1955 y 1956 (AST 6 of 1372nd mapping and charting squadron, 1997).

Figura 5.3.A: Inscripción lateral de los fotogramas de la Serie B. En orden, de arriba abajo: reloj, distancia
focal calibrada, contador de exposiciones, número de serie del objetivo, número de serie de la cámara, marcas
fiduciales y altímetro.

Figura 5.3.B: Figura 5.3.B. Marco de trabajo en Bentley Context Capture, con el bloque de fotogramas
introducido, así como la información necesaria: tamaño del sensor y distancia focal.

<!-- p. 6 -->

Figura 5.4: Mosaico de fotogramas aéreos (Serie A, arriba, Serie B, debajo) compuesto en el programa de
diseño gráfico Corel Draw para el establecimiento de los solapes (coloreados).

Figura 5.5: Los puntos de control deben situarse sobre elementos inalterados y reconocibles en el terreno
desde la captura de la fotografía histórica, de 1945 (A) o 1956 (B) hasta la actualidad (C).

Figura 5.6: Figura 5.6 Puntos de control establecidos para los modelos de 1945 (A), sobre el fotograma
nº46, y 1956 (B), sobre el fotograma nº 1748.

Figura 5.7: Proceso gráfico de aerotriangulación: Estimación de la posición de cada fotograma (1),
establecimiento de puntos de control y puntos de enlace sobre los solapes (2); y generación de la malla
tridimensional (3-4).

Figura 5.8: Visualización en el programa ContextCapture Viewer de los modelos 3D generados en la FR-3D
correspondientes a las reconstrucciones de 1945 (A) y 1956 (B).

Figura 5.9: Distribución regional de las coberturas del PNOA realizadas hasta enero de 2020 (A) y en
detalle, la cuadrícula del fichero correspondiente al embalse de Azután (B) donde se localiza el yacimiento.
(Fuente: Instituto Geográfico Nacional).

Figura 5.10: Visualizaciones del archivo LIDAR: Nube de puntos sin clasificar, coloreados en RGB en
ArcScene (A-B) y como nube de puntos con la clasificación de todos los puntos por clases (C). Debajo, el MDE
generado, visualizado mediante Hillshade.

Figura 6.1: Aproximación al vado de Puente Pinos sobre las ortofotos generadas de las Series A y B, que
reflejan las diferencias de caudal del Tajo en dos momentos distintos del año: estiaje de septiembre, en 1945,
y gran caudal en abril, en 1956.

Figura 6.2: Visualización de la pérdida de referencia visual del Cerro de la Mesa. En 1956 (ortofoto y malla
3D), la plataforma sobre la que se asentaba el yacimiento presentaba un escarpe de más de 40 metros entre
la ribera del río y el punto más alto del cerro (A-C). En la actualidad, los productos del PNOA 2009 (D-E)
ilustran claramente la alteración morfológica del cerro y la situación escarpe, sumergido en el embalse.

Figura 6.3: Análisis del paisaje antiguo del Cerro de la Mesa a partir de la interpretación de los modelos
tridimensionales de 1945 (A) y 1956 (B-C) en BentleyContext Viewer. Transformación del entorno con la
construcción de las infraestructuras asociadas a la construcción el embalse y la subida de las aguas.

Figura 6.4: Análisis del vado de Puente Pinos a través de las ortofotos generadas. En verde, la isleta central
que facilitaría el paso, emergente sobre el agua en la ortofoto de 1956 (A) cuando el caudal está alto, pero
que se aprecia su dimensión real en 1945 con el caudal bajo (B), y que se encuentra sumergida en la actualidad
(C). En rojo, área en la que se encontraron los restos del puente antiguo que cruzaba el río bajo el cerro
(Charro Lobato, 2015).

Figura 6.5: Análisis del recorrido de la calzada romana que comunica Belvis de la Jara y Azután (Muñoz
Villarreal y Ruiz Carmona, 1993) sobre la ortofoto de 1956 (A), y en la actualidad (B). Debajo, ascenso de la
calzada desde la ribera del río, donde se encuentra en mejores condiciones, visualizado en 1956 (C) y 1945
(D).

Figura 6.6: Modelo Digital de Superficies generado mediante la restitución fotogramétrica SfM-MVS sobre
los fotogramas del Vuelo AMS (B) en torno al municipio de Alcolea de Tajo, tomadas en abril de 1956.
Clasificación con ayuda de Hillshade, y arriba a la derecha, detalle del área del Cerro de la Mesa.

Figura 6.7: Simbolización del MDS en base a la altimetría del Cerro de la Mesa y su perímetro, sobre la
ortofoto generada en la restitución. A la derecha, clasificaciones tridimensionales realizadas en ArcScene que
reflejan la posición original de dominio del cerro respecto al río.

<!-- p. 7 -->

Figura 6.8: Creación de perfiles topográficos para ilustrar la diferencia altimétrica entre la parte más alta
del Cerro de la Mesa y la ribera del río Tajo como reflejo de la predominancia visual del yacimiento. La
pérdida altimétrica en la actualidad (MDE PNOA 2009; B) respecto a 1956 (MDS logrado mediante
restitución, A) se expresa cuantitativamente en el gráfico (C).

Figura 6.9: Mapa de pendientes generado a partir del MDS de 1956 y visualizado sobre la ortofoto de 1956.

Figura 6.10: Diferencia de superficies entre el MDE generado mediante LiDAR del PNOA 2009 y el MDS
generado a partir de los fotogramas de 1956. Los valores positivos expresan procesos de sedimentación,
representados en tonos azules por los procesos de erosión, en rojo.

Figura 6.11: Mapas generados en el programa RVT para la completa visualización de los datos LiDAR en el
entorno del Cerro de la Mesa. En la figura se representan las ortofotos de 2019 (A) y 1956 (B), por un lado, y
los productos de las técnicas empleadas, por otro: MULTI-HS (C) PCA (D), SLRM (E), y SVF (F).

Figura 6.12: Presentación de los resultados obtenidos mediante el uso de georradar en el yacimiento del
Cerro de la Mesa, donde se visualiza el entramado urbanístico expuesto por el GPR junto a la estructura
arqueológica ya excavada y los restos de muralla (A). Además, localización de los restos en la ortofoto del
PNOA de 2019 (B) y en el MDT05 del PNOA, apoyado por la técnica de Hillshade (C). Información de GPR
procedente de la prospección geofísica dirigida por J. Vallés (Pereira Sieso et al., 2020), y facilitada por el
CAI Arqueometría UCM.

Figura 6.13: Comparación de los resultados del GPR (A) sobre el MDT05 del PNOA, con la técnica SVF para
el LiDAR en el cerro (B), donde no ha sido posible visualizar el conjunto de estructuras soterradas.
Información de GPR procedente de la prospección geofísica dirigida por J. Vallés (Pereira Sieso et al., 2020),
y facilitada por el CAI Arqueometría UCM.

Figura 6.14: Integración de la trama urbana descubierta por el georradar en la morfología original del Cerro
de la Mesa que se aprecia en la ortofoto generada para la restitución fotogramétrica de 1956. Información de
GPR procedente de la prospección geofísica dirigida por J. Vallés (Pereira Sieso et al., 2020), y facilitada por
el CAI Arqueometría UCM.

Figura 6.15: Perspectiva general de los resultados del georradar, con la aplicación de herramientas de
visualización en ArcScene, combinados con la ortofoto y el MDS de 1956. Información de GPR procedente de
la prospección geofísica dirigida por J. Vallés (Pereira Sieso et al., 2020), y facilitada por el CAI Arqueometría
UCM.

Figura 7.1: Distorsiones producidas por las limitaciones de los fotogramas históricos en la generación de los
MDS: Numerosas en el caso de la reconstrucción de 1945 (A-B), y que invalidan el modelo, pero también en
la de 1956, que afectan fundamentalmente a la zona noroeste del vado de Azután (C).

\11. LISTADO DE TABLAS

Tabla 1: Características básicas de los fotogramas usados para la restitución fotogramétrica mediante SfMMVS.

Tabla 2: Informe de calidad: datos generales de las reconstrucciones generadas mediante SfM-MVS.

Tabla 3: Informe de calidad: Detalle del RMSE de los Puntos de Control utilizados en cada reconstrucción.

<!-- p. 8 -->

\1. INTRODUCCIÓN

La aplicación en Arqueología de las Tecnologías de Información Geográfica lleva años
proporcionando grandes avances en la investigación de las sociedades del pasado (Connolly
y Lake, 2009; Mínguez García y Capdevilla Montes, 2016). En un mundo informatizado
como el actual, la digitalización del paisaje representa una más de las consecuencias lógicas
de un proceso que genera cantidades masivas de información en todos los aspectos de la
realidad. Al calor del fenómeno del Big Data, apoyados por la mejora técnica constante de
los ordenadores, la capacidad de almacenamiento y el software, emergen todos aquellos
datos de componente espacial con los cuales trabajan las TIG. No es de extrañar, pues, que
la utilización de estas herramientas suponga una ventaja tan importante en una disciplina
como la Arqueología, en la cual la dimensión espacial de los datos juega un papel dentro de
su método científico tan importante como lo es su condición de ciencia humana, que no
puede separar la estrecha relación que la humanidad ha vivido siempre con el paisaje que le
rodea (Chevallier, 1976; Orejas, 1991; Criado, 1993, Anchsuetz et al., 2001; etc.).

La eclosión de la tecnología digital y de la información ha encontrado en el contexto de la
Arqueología actual los condicionantes necesarios para el éxito, en un momento en el que
continúan las perspectivas positivistas (Ingold, 1993) a la vez que se desarrolla la
planificación territorial, los nuevos enfoques del paisaje y la apuesta por la conservación del
patrimonio arqueológico (Fábrega-Álvarez, 2017). Además, con la entrada del siglo XXI se
ha venido gestando y desarrollando la concepción de la Arqueología Preventiva, un cambio
de paradigma que, entre una serie de medidas dirigidas a la protección y gestión del
Patrimonio Arqueológico y apoyado por cambios en la legislación pública, pone el foco en
el carácter finito y único de los yacimientos arqueológicos. Esto es, considera la intervención
directa sobre el yacimiento, la excavación tradicional, que supone la destrucción del mismo,
como una actividad a limitar de forma que beneficie su estudio en el futuro, la conservación
a largo plazo y la difusión al público general (Querol, 2010: 216-219; Castillo, 2010).

Este principio implica necesariamente la utilización de métodos arqueológicos no invasivos,
que nos proporcionen toda la información y documentación posible acerca del yacimiento
arqueológico sin intervenir materialmente sobre él, de forma que pueda evitarse la
destrucción final, o al menos, llegados a este punto, contar con el conocimiento suficiente
para minimizar el impacto sobre él. Es indudable que este proceso no sería posible sin la
innovación tecnológica que ha supuesto el desarrollo de las técnicas de detección remota que
forman parte de las TIG, ya sean de reconocimiento de superficie como de prospección de
subsuelo, utilizando medios dispuestos en el espacio (satélites, radar), el aire (fotografía
aérea, LiDAR, etc.) o en el mismo suelo, como la prospección geofísica, SIG, DGPS
(acrónimo en inglés de Differential Global Positioning System), etc. En definitiva, una serie
de métodos tecnológicos innovados en otros ámbitos científicos que aplicados en
Arqueología permiten superar la idea de la excavación como único medio de obtención de
información (Dietz et al., 2011).

Este trabajo se plantea con la idea de avanzar en las capacidades que alberga el uso de las
TIG en los métodos de la arqueología no invasiva. Para esta tarea se han escogido dos medios
punteros como son la técnica fotogramétrica “Structure from Motion” (SfM) y la técnica
LíDAR, que, apoyados por los materiales cartográficos obtenidos de la prospección geofísica
mediante georradar (realizado por los técnicos Javier Vallés Iriso y Jorge Matesanz Vicente,
del CAI de Arqueometría de la UCM), se van a combinar para su aplicación en el yacimiento
arqueológico del Cerro de la Mesa (Alcolea de Tajo, Toledo). La elección de este lugar no
es aleatoria, pues la profunda alteración morfológica que ha sufrido el sitio en época

8

<!-- p. 9 -->

contemporánea supone un problema imposible de salvar sin la aplicación de estas
herramientas, que van a demostrar su virtud para la reconstrucción topográfica y
arqueológica de un paisaje antiguo desaparecido.

Definida la línea de trabajo, en primer lugar, se detallarán los objetivos, principales y
secundarios de esta investigación, junto a la problemática a la cual nos enfrentamos y qué se
pretende responder con la realización de este trabajo. A continuación, es necesario
contextualizar el estudio, tanto en el ámbito arqueológico con la descripción de las
características del yacimiento del Cerro de la Mesa como en la vertiente teórica, donde se
expone el estado de la cuestión de las TIG, su historia, evolución y aplicación en
Arqueología. Terminado el primer bloque se desarrolla el cuerpo de la investigación, donde
se describirá minuciosamente la metodología empleada para cada una de las aplicaciones,
así como las herramientas utilizadas, que culmina con la presentación de los resultados
obtenidos, la interpretación y discusión de estos. La estructura del estudio finaliza con la
exposición de las conclusiones, que incluyen la reflexión de las repercusiones que tiene el
presente trabajo en el futuro de la investigación.

\2. OBJETIVOS

El Cerro de la Mesa presenta un completo desafío a la hora de encarar la investigación
arqueológica del poblado fortificado que se asentó sobre él durante la Edad del Hierro, entre
los siglos VII a.C y II a.C (Ortega y Del Valle, 2004; Chapa et al, 2007; Charro y Cabrera,
2011; etc.). La construcción del embalse de Azután y la infraestructura derivada de éste ha
supuesto no solo la pérdida de buena parte del yacimiento sino la completa alteración de las
características de un paisaje que había permanecido prácticamente intacto. El objetivo
principal de este trabajo consiste en superar esta problemática realizando una reconstrucción
del yacimiento y su entorno, a través de la aplicación de técnicas no invasivas apoyadas en
las TIG. La reconstrucción se lleva a cabo tanto en el plano topográfico, mediante la
aplicación de novedosas técnicas de fotogrametría que permiten su restitución
tridimensional, como en el arqueológico, gracias al LiDAR y a la interpretación de los
resultados del georradar. Al final del proceso, la reconstrucción permite generar una serie de
productos cartográficos que con su debida interpretación cumplen su función en el avance
del estudio arqueológico del Cerro de la Mesa.

Si bien el trabajo tiene una clara vocación específica enfocada en el Cerro de la Mesa, esto
no excluye el planteamiento de otro tipo de objetivos secundarios que amplían las
competencias del estudio. En este sentido, pretende a nivel general demostrar con una nueva
aplicación la validez de las TIG en uno de sus múltiples campos de acción como es la
Arqueología, pero en un ámbito en clara expansión se busca aportar nuevas ideas en la
metodología de dos herramientas cada vez más utilizados como son el LiDAR y la
restitución fotogramétrica automatizada con técnicas SfM. En este proceso se van a
comparar dos medios de información histórica como son los vuelos fotogramétricos en
España de 1945-46 y 1955-46, con el doble objetivo de analizar la calidad de los resultados
de sus productos generados, y de utilizar ambas restituciones de la topografía como soporte
para la prospección visual. Respecto a la segunda aplicación, el objetivo de la reconstrucción
arqueológica se apoyará con el estudio de la viabilidad del LiDAR como complemento de

9

<!-- p. 10 -->

un instrumento de prospección más generalizado como es el georradar, cuyo uso se ve
restringido en las zonas cubiertas por vegetación donde sí llega a actuar el láser.

En definitiva, es necesario aclarar que nos encontramos ante un tipo de estudio muy
necesario en Arqueología. Este trabajo nace con el objetivo último de restaurar las
características perdidas de un espacio antiguamente habitado, y en el intento se aprovechan
y destacan técnicas constatadas ya por diferentes investigadores en trabajos anteriores
(Kokalj et al., 2011; Gómez, 2012; Gómez et al., 2016; Fernández-Lozano y GutiérrezAlonso, 2016), a la vez que se comparan y plantean otros métodos. Por lo tanto, es evidente
que el estudio se dirige al enriquecimiento de una vía de investigación aplicable a numerosos
yacimientos arqueológicos que, o han sufrido ya grandes transformaciones, o están en riesgo
de padecerlas.

\3. EL YACIMIENTO DEL CERRO DE LA MESA (ALCOLEA DE TAJO, TOLEDO)

3.1. Situación geográfica

El yacimiento arqueológico del Cerro de la Mesa se localiza a nivel regional en el valle
medio del Tajo, concretamente en la zona occidental de la provincia de Toledo (Castilla-La
Mancha). Situado al suroeste del término municipal de Alcolea de Tajo, al cual pertenece
administrativamente, el asentamiento se emplaza sobre un promontorio, constituido por
depósitos de terrazas asentadas en el zócalo granítico (Charro y Cabrera, 2011: 208) en la
margen derecha del Tajo, a la altura de la confluencia de este río con su afluente, el Huso.
Esta elevación, de unas dos hectáreas aproximadamente, se alza unos diez metros en sus
lados norte, sur y este sobre las tierras que la rodean, a la vez que desciende suavemente
hacia el río Tajo por el oeste (Ortega y Del Valle, 2004: 175).

Este es, ciertamente, el aspecto que presenta hoy en día, pues las características originales
del emplazamiento del Cerro de la Mesa cambiaron para siempre con la construcción de la
presa de Azután en la década de los años 60, derivando en una serie de transformaciones
físicas que expondremos más adelante. La preeminencia geográfica del Cerro de la Mesa
justifica, como sucede recurrentemente en la mayoría de los yacimientos arqueológicos de
este tipo en la Prehistoria Reciente, la elección de este lugar para el asentamiento humano.
El cerro constituye la última elevación del entorno (360m), al norte del Tajo, entre los cerros
de Puente Pinos (432m), al este, y la penillanura de la pedanía de El Bercial (338m). Al otro
lado del río, en cambio, en el dominio del Huso, el terreno se accidenta formando la Sierra
Ancha y más al sur, la Sierra Aguda, con altitudes ya de 920 y 813 metros, respectivamente
(Chapa y Pereira, 2006: 121). La combinación de estos factores otorga al Cerro de la Mesa
una notable visibilidad en el entorno (ver Figura 3.1).

10

<!-- p. 11 -->

A C

B

D

Figura 3.1. Localización del área protegida del Cerro de la Mesa: regional en Castilla la ManchaToledo (A-B), comarcal sobre el MTN 50 (C) y aérea (D) mediante la ortofoto del PNOA 2019.

Sin embargo, por encima de la posición que le otorga la altura en el entorno, el valor
estratégico más importante del emplazamiento del Cerro de la Mesa es su posición
privilegiada en el control del vado de Puente Pinos, hoy desaparecido bajo las aguas del
embalse de Azután (ver Figura 3.2). La importancia del vado fluvial como lugar de paso y
pilar básico en la red de comunicaciones interregional otorga a este espacio un papel
relevante en la historia del ser humano.

En el caso de Puente Pinos, se conjugan dos elementos que acrecientan su valor. El primero
es el régimen fluvial del río Tajo, que antes de ser regulado por los embalses en la segunda
mitad del siglo XX, presentaba un comportamiento bastante irregular, con varios episodios
de crecidas a lo largo del Holoceno (Benito et al., 2003) y un período de estiaje entre julio y
octubre, en el que las aguas se encontrarían especialmente bajas. El segundo elemento tiene
que ver con la singularidad del corredor. Son tres los vados principales para atravesar el Tajo
en la zona noroccidental de la Meseta Sur hacia los valles y pasos de la vertiente sur de
Gredos: de este a oeste, respectivamente, uno en las cercanías de Talavera de la Reina, en la
confluencia del río Alberche con el Tajo; el de Puente Pinos, en la confluencia del Huso y el

11

<!-- p. 12 -->

Tajo, y un tercero en las inmediaciones de la antigua población de Talavera la Vieja,
actualmente bajo las aguas del embalse de Valdecañas (Pereira, 2008).

Figura 3.2. Situación aproximada del vado histórico de Puente Pinos sobre el Mapa Topográfico
Nacional de 1950 (Fondo) y de 2007 (Abajo dcha.), ya sumergido bajo el embalse de Azután.

Con estas características, es innegable la integración del vado de Puente Pinos en la red de
caminos regional ya desde época prehistórica, o por lo menos, como lugar simbólico en el
entorno que va a favorecer durante la Edad del Hierro el asentamiento humano en el Cerro
de la Mesa y el dominio del territorio al abrigo del control del paso fluvial. No obstante, se
mantuvo su uso en época romana, atestiguado por la existencia de una calzada de la cual aún
quedan tramos visibles en sus inmediaciones (Blázquez y Delgado Aguilera, 1919-1920: 24)
y que comunicaría los municipios de Belvís de la Jara y Azután a lo largo de la Comarca de
la Jara. A su vez, el hallazgo en el año 1950 por parte de Fernando Díaz de Gregorio de
cuatro estribos de granito de lo que consideró el antiguo puente romano (1950: 111-112)
demuestra la existencia de un puente de esta época en el vado de Puente Pinos y refuerza la
teoría de la existencia de otros dos puentes más: uno también para el Tajo en las cercanías
del Salto de Azután, y otro para el río Huso en dirección noroeste, de manera que se pudieran
conectar las calzadas (Muñoz Villarreal y Ruiz Carmona, 1993). No sería hasta la Edad
Media cuando el tránsito a ambos lados del Tajo en esta zona se desplaza unos 10 kilómetros
al oeste con la construcción del Puente del Arzobispo. El vado de Puente Pinos pierde
entonces su influencia histórica, y desaparece finalmente bajo las aguas del embalse de
Azután a finales de la década de 1960. El control de la ruta de paso, como se ha visto, resultó
siempre fundamental, y no es de extrañar que el apogeo del asentamiento del Cerro de la
Mesa en la Protohistoria estuviera directamente relacionado con el control del vado de
Puente Pinos.

12

<!-- p. 13 -->

3.2. La ocupación del Cerro de la Mesa, apogeo y abandono

Las primeras evidencias de ocupación humana en el entorno del Cerro de la Mesa se
remontan al Bronce Final, cronología a la cual pertenece una espada de bronce hallada en el
propio vado del Cerro (Ruiz-Gálvez y Galán, 1991), y relacionada con otros hallazgos de
armas y objetos de bronce en el curso del Tajo, como un puñal en el de Carpio de Tajo
(Jiménez de Gregorio, 1966) o los ejemplares de fíbulas de codo localizados en Talavera la
Vieja, el siguiente vado aguas debajo de la ubicación del Cerro de la Mesa (Chapa y Pereira,
2006), con una cronología en torno al siglo IX a.C (Jiménez Ávila y González Cordero,
1999).

En los inicios de la Edad del Hierro, hacia los siglos IX-VIII a.C, el proceso de
territorialización y jerarquización de las sociedades lleva al sedentarismo y a la construcción
de asentamientos permanentes en puntos dominantes del paisaje, algunos de los cuales ya
estarían habitados con anterioridad (Parcero-Oubiña, 2000:86; Chapa y Pereira, 2006: 127;
Ruiz Zapatero y Álvarez Sanchís, 2012). En el valle Medio del Tajo, casos de ocupación
nombrados como los de El Carpio y Talavera la Vieja, junto a otros como el de Arroyo
Manzanas, todos ellos con claro control de los vados del Tajo, ofrecen continuidad con la
fase del Hierro Pleno, que comienza a mediados del siglo V a.C (Álvarez Sanchís, 1997:
160). Sin embargo, esto no impide observar importantes transformaciones en la transición a
este período, como son el abandono de numerosos asentamientos, la búsqueda de terrenos
más favorables a la actividad agrícola o la deposición de armas en puntos de paso del río, tal
y como hemos nombrado anteriormente, asociado a un proceso de territorialización ritual en
la cual se reclamaría derecho sobre el control de estos pasos clave (Rodríguez Hernández,
2018: 85-88).

En esta época se constata ya un asentamiento firme en el Cerro de la Mesa, cuyas fases más
antiguas de ocupación se han datado entre los siglos VII y V a.C relacionadas con la
construcción de la muralla, el santuario y las primeras etapas del poblado intramuros (Chapa
et al., 2013: 161-162). Las dataciones radiocarbónicas y el estudio de los materiales
cerámicos por parte del equipo investigador del yacimiento clarifican el origen del
asentamiento, que aumenta el grado de complejidad a la vez que se prolonga en el tiempo.
La Segunda Edad del Hierro (400-50 a.C) en el asentamiento viene determinada
directamente con la presencia de una etnia bien conocida por las fuentes clásicas, los
vettones, asentados en el territorio que se extiende desde el Duero hasta la sierra de
Guadalupe por el sur (aunque pudieron llegar hasta el Guadiana), a ambos lados del Sistema
Central (Almagro Gorbea 2008:54) en lo que hoy en día serían las provincias de Toledo,
Cáceres, Ávila y Salamanca (ver Figura 3.3). La localización del asentamiento en la zona
suroccidental del territorio vettón, en la frontera con oretanos y carpetanos, y especialmente
el control de un paso fronterizo como es el vado de Puente Pinos o Azután, que se fortalece
especialmente en este momento, otorgaron al poblado del Cerro de la Mesa una posición
estratégica para el intercambio comercial, y, por tanto, la supremacía en el entorno (Ortega
y Del Valle, 2004: 183). Consecuentemente, en este período el asentamiento desarrolla un
mayor grado de urbanismo y de actividad económica a nivel doméstico. Así mismo, se
suceden diferentes fases constructivas en las murallas que prueban el fortalecimiento del
cercado original, así como la incorporación de lienzos en talud y torres o contrafuertes de
planta rectangular (Chapa y Pereira, 2006: 132). En este recinto amurallado se van a
documentar restos de estructuras de habitación pertenecientes a la fase de ocupación final
del yacimiento, entre finales del siglo II y principios del I a.C (Cabrera y Moreno-García,
2014: 134), enmarcado en un proceso de abandono del asentamiento sobre el cual no
contamos todavía con suficiente información.

13

<!-- p. 14 -->

Figura 3.3. Límites geográficos de los vettones según las fuentes históricas y localización de los
principales yacimientos (Álvarez Sanchís, 2003). En triángulo rojo, situación del yacimiento del
Cerro de la Mesa.

3.3. La presa de Azután: transformación completa del entorno

El asentamiento abandonado del Cerro de la Mesa permaneció sepultado durante siglos,
inalterado, como el entorno más inmediato que le rodea hasta el año 1969, momento en el
que finaliza la construcción del embalse de Azután en la confluencia del Tajo con su afluente,
el Huso. La infraestructura requería de grandes movimientos de tierra y ubicación de
distintos tipos de estructuras fundamentales para los trabajos en la presa (Chapa et al., 2007),
unidos a la propia construcción del embalse y el salto de agua. En consecuencia, la
morfología del yacimiento y su paisaje sufrieron una transformación definitiva que hoy en
día dista mucho de parecerse a la original (ver Figura 3.4). De hecho, se calcula que
únicamente se ha conservado un tercio de la extensión real del asentamiento intramuros,
protegido hoy en día en terrenos de titularidad pública (Chapa et al., 2013: 141).

Esta radical modificación ha tenido enormes consecuencias en el entorno del Cerro de la
Mesa: la más importante, la pérdida de la referencia visual que suponía el Cerro de la Mesa
con la subida del nivel del agua y, por tanto, el dominio histórico sobre el vado de Puente
Pinos, desaparecido además bajo las aguas al igual que la mayor parte del territorio
extramuros del asentamiento. Se ha reducido a 25 metros la diferencia entre la cota de agua
y la parte más alta del yacimiento, que originariamente era de más de 40 metros (Charro et
al., 2009: 131).

14

<!-- p. 15 -->

Figura 3.4. Evolución de la alteración morfológica del Cerro de la Mesa. Límite original del
yacimiento extraído de la ortofoto del Vuelo AMS B (izda.) en 1956, y en su situación posterior tras
la construcción de la presa en el Vuelo Nacional, en 1986 (centro) y el resto de infraestructura
actual, en la ortofoto del PNOA 2019 (dcha.).

Como se ha comentado, únicamente el tercio norte, protegido por un vallado, ha conseguido
sobrevivir a las transformaciones. Ambos extremos del yacimiento han sido completamente
modificados: la zona oeste con la construcción de una subestación eléctrica sobre una
plataforma artificial que altera el desnivel original del promontorio en ese extremo, y la zona
oriental debido a los movimientos de tierra derivados de las obras de asfaltado de la vía que
conduce a la estación, que discurre además por la parte sur del yacimiento. Por último, una
repoblación de pinos en la zona norte y oeste hacia el área de la presa ha provocado la
afloración de elementos constructivos fuera de la superficie vallada (Chapa y Pereira, 2006:
\122) (ver Figura 3.5.A).

Curiosamente, las obras de construcción de la presa no motivaron el descubrimiento del
yacimiento arqueológico, que permanecería oculto hasta 1991. En ese año, la Confederación
Hidrográfica del Tajo comienza los trabajos de puesta en funcionamiento de un sistema de
regadío en el término municipal de Alcolea de Tajo (Ortega y Del Valle, 2004: 175). El
movimiento de tierras y la construcción de la central hidroeléctrica provocaron el hallazgo
de parte del lienzo sur de la muralla, tras lo cual se realizó una excavación arqueológica de
urgencia (Charro y Cabrera, 2011: 209). La excavación sistemática del Cerro de la Mesa no
comienza hasta el año 1996, en el cual se realizan trabajos dirigidos a conocer el potencial
arqueológico del yacimiento, a la vez que se procede a la protección del sitio, con el vallado
del perímetro mencionado anteriormente, y la implantación de una cubierta sobre las
estructuras defensivas para su protección frente a los factores climáticos (Ortega y Del Valle,
2004: 176). A partir de este momento, las campañas de excavación se han prolongado desde

15

<!-- p. 16 -->

comienzos de siglo, sacando a la luz diferentes estructuras del asentamiento, entre los que se
incluyen parte del entramado urbano, la arquitectura defensiva o una fosa vertedero (Chapa
et al., 2013), en un proceso de investigación que continúa hoy en día gracias a la labor de
los arqueólogos del Proyecto BHIT (ver Figura 3.5.B).

A B
Figura 3.5.A. Panorámica del entorno del Cerro de Figura 3.5.B. Vista general de la zona
la Mesa en la actualidad, después de todas las excavada del yacimiento arqueológico
transformaciones sufridas. Señalada, la zona (Cabrera y Moreno, 2014).
protegida del yacimiento (Charro Lobato et al.,
2009).

\4. ESTADO DE LA CUESTIÓN. LAS TIG Y SU APLICACIÓN EN ARQUEOLOGÍA

4.1. Trayectoria y evolución

El desarrollo de las nuevas Tecnologías de la Información Geográfica (TIG) ha
revolucionado por completo el análisis espacial del territorio convirtiéndose en herramientas
informáticas básicas para la investigación, planificación y gestión del mismo. No obstante,
la aparición y generalización de las TIG se enmarca en el fenómeno de la revolución
informática y digital, que desde los años 60 del siglo XX, ha transformado no solo el
tratamiento de la información, que ahora llega en cantidades masivas, sino también el mismo
funcionamiento de la sociedad. En este contexto, los grandes avances tecnológicos en el
ámbito de la informática provocan la expansión de un grupo de nuevas herramientas capaces
de solucionar multitud de problemas de componente espacial, estimuladas por los inicios de
la cartografía asistida por ordenador. Aunque se idea en los años 50, es a partir de la siguiente
década cuando comienzan a desarrollarse programas que permiten la creación de mapas
geográficos a partir de información digital (Wheatley y Gillings, 2002: 11-12).

La versatilidad de las TIG, con una capacidad de aplicación en diversos ámbitos de la
realidad, las convirtió pronto en poderosas herramientas en expansión. La gestión de la
información espacial territorial procedente de las nuevas tecnologías se apoyó en el
desarrollo los Sistemas de Información Geográfica (SIG), un amplio término que engloba,
en su definición más funcionalista según el Centro Nacional de Información Geográfica y

16

<!-- p. 17 -->

Análisis de los EEUU, un “sistema de hardware, software y procedimientos elaborados para
facilitar la obtención, gestión, manipulación, análisis, modelado, representación y salida de
datos espacialmente referenciados, para la resolución problemas complejos de planificación
y gestión” (NCGIA, 1990). Los SIG habían comenzado a desarrollarse en los años 60
vinculados a la incipiente cartografía digital, a partir de la base teórica sentada por J.K.
Wright una década antes, en la aplicación de proyectos pioneros destinados a la planificación
territorial como el Sistema de Información Geográfico de Canadá (CGIS) o la
implementación de software para la producción de información vectorial como el SYMAP
del Laboratorio Harvard (Olaya, 2014). A partir de los años 70, los SIG evolucionan ya como
una disciplina estable y asociada al ámbito científico, pero el principal avance se da en los
años posteriores con el nacimiento de empresas desarrolladoras de software SIG, con la
difusión consecuente y el carácter multidisciplinar que adopta desde entonces (Mínguez
García y Capdevilla Montes, 2016: 48).

En una ciencia tan ligada al territorio como es la Arqueología la simbiosis fue temprana y
ha sido fundamental en el recorrido y desarrollo de ambas. Este camino comenzó en los años
80 con la intervención de varios arqueólogos norteamericanos en el ámbito de la gestión
patrimonial y, sobre todo, en la identificación de patrones espaciales (Feder, 1979; Kvamme,
1983). Sin embargo, no es hasta los años 90 cuando la arqueología europea (y española) se
abre a la aplicación de los SIG, primero vinculado a la gestión patrimonial, como se realizó
en Andalucía (Amores et al, 1999) o Braga (Martins y Dantas, 2000). Ya en el siglo XXI,
impulsados por el avance tecnológico y especialmente, la disponibilidad de ordenadores de
gran capacidad (Scianna y Villa, 2011: 337), la aplicación de los SIG se amplía a la propia
investigación arqueológica mediante el almacenamiento y procesado de información
espacial derivada de los yacimientos, por ejemplo, en Segeda (López-Romero, 2006), Arucci
(Corrales-Álvarez et al., 2018) o Las Delicias (López Fraile et al., 2014), entre muchos otros,
la modelización digital del paisaje o el propio análisis territorial (García Sanjuán et al., 2009;
Verhagen, 2017), en un proceso de implantación beneficioso por el impulso de los SIG al
desarrollo de los estudios de la Arqueología del Paisaje (Baena et al., 1997; Grau, 2006).

Así pues, el verdadero éxito de los SIG en la Arqueología se produce a partir de la entrada
del nuevo siglo, especialmente en Europa, donde se convierten en pilar básico de estudios
territoriales frente a los modelos predictivos que imperaban en Norteamérica (Zamora y
Baena, 2010: 51-52). El alto número de trabajos que recurren a los SIG como herramienta
de trabajo es sintomático de la implantación de estas tecnologías en cualquier estudio
arqueológico desde la década de los 2000, con un fuerte predominio en estos años de los
análisis de visibilidad (Harris, 2000; Fairén, 2003, Fábrega-Álvarez, 2017; etc.) y de rutas
óptimas (López-Romero, 2005; Carrero-Pazos, 2018; etc.).

El establecimiento de los SIG como gestores de información espacial avanzó al mismo
tiempo que se desarrollaban tecnologías y herramientas, procedentes de campos ajenos a la
Arqueología, encargadas de proporcionar los datos necesarios para su tratamiento. De este
modo, se enmarcan en el concepto de las TIG, más integrador, en la cual los SIG se
complementan con la Teledetección, la Cartografía Digital, los GNSS (Global Navigation
Satellite System) y la Fotogrametría. La propia demanda en el campo laboral y académico
de este tipo de estudios, ya ligados permanentemente a cualquier proyecto arqueológico, y
el avance e incluso desarrollo de hardware con más capacidades, más accesibles, con
interfaces amables y una gran capacidad analítica, ha disparado las posibilidades de las TIG
en arqueología en la última década. Este proceso tiene un importante punto de inflexión en
España en el año 2015, cuando el Instituto Geográfico Nacional aprueba la política de
difusión que permite la liberación, de carácter libre y gratuita, de la información geográfica

17

<!-- p. 18 -->

digital generada por dicho organismo (Bases Topográficas y Cartográficas, tanto en formato
ráster como vectorial, fotogramas y ortofotos del Plan Nacional de Ortofotografía Aérea
(PNOA), LíDAR y Modelos Digitales del Terreno, coberturas y usos del suelo -SIOSE,
Corine Land Cover-, etc.), posibilitando la obtención de una gran cantidad de información
necesaria para la realización de buena parte de las aplicaciones de las TIG en Arqueología.

4.2 Posiciones teóricas

Esta evolución tecnológica no ha seguido una tendencia lineal en los postulados teóricos de
la Arqueología, sino que fue variando del mismo modo que se enfrentaban las corrientes de
pensamiento contemporáneas a su aplicación. De hecho, la implantación de un nuevo marco
teórico como es la llamada Arqueología del Paisaje ha supuesto, junto a la definitiva
revalorización del entorno como sujeto arqueológico indispensable, una revisión y crítica de
los principios en base a los cuales se habían empezado a aplicar los SIG en Arqueología.
Hasta entonces, su raíz metodológica venía inspirada en los fundamentos de la Arqueología
Espacial, una corriente de la Nueva Arqueología británica que evidenciaba el interés del
procesualismo en superar la simple descripción subjetiva de los datos espaciales para
convertirlo en un medio de información cuantificable. De este modo, entendiendo el paisaje
como un recurso ecológico, económico y funcionalista por parte de los grupos humanos se
podían generar modelos predictivos de ocupación aplicables al estudio arqueológico
(Hodder y Orton, 1976; Clarke, 1977). Los SIG representaban, pues, una herramienta
fundamental para un giro analítico, positivista e informatizado de la Arqueología.

Paralelo a la generalización del uso de los SIG, en la década de los noventa, comienza a
brotar una postura crítica al significado determinista del paisaje que desprendían estos
principios, principalmente desde posiciones postprocesualistas. En su crítica se proponía
fundamentalmente la redefinición del paisaje como sujeto de estudio, de modo que se
incorporasen las dimensiones humana, social y cultural del espacio que habían excluido los
procesualistas en su visión empirista y funcionalista (Criado-Boado, 1993, 1999; Orejas,
1991, 1995). El intenso debate teórico que mantienen ambas corrientes ha cristalizado en
una Arqueología del Paisaje que sitúa el estudio de éste como una categoría de análisis por
encima de distintos enfoques y procedimientos (Sánchez Yustos, 2010; Parcero-Oubiña et
al., 2014). Es necesario introducir brevemente a los SIG en el debate, pues frecuentemente
se ha criticado el determinismo de estas herramientas y, por tanto, el enfoque metodológico
que implica su uso en la Arqueología del Paisaje, a pesar de que no han faltado autores e
investigaciones que experimentan y demuestran la capacidad de los SIG en planteamientos
no positivistas que otorgan al ser humano una interacción consciente e íntegra con el paisaje
(Fábrega Álvarez, 2017; Parcero-Oubiña, 2018)

Al margen de este debate, la aplicación de las TIG en Arqueología es desde hace unos años
un elemento fundamental en el estudio, protección, interpretación y difusión del Patrimonio
Histórico-Cultural donde se integra la investigación arqueológica. En este ámbito, al análisis
territorial se han unido una gestión predominantemente digital de los datos arqueológicos,
la detección remota de la superficie terrestre (Bucci, 2018), la fotogrametría digital para la
reconstrucción 3D (Pereira Uzal, 2013; Luis Rivas, 2013), la simulación virtual de los
yacimientos (Romero Serra et al., 2013) y el empleo de los drones (Fernández-Lozano y
Gutiérrez-Alonso, 2016), entre las tecnologías más punteras del panorama actual.

18

<!-- p. 19 -->

\5. METODOLOGÍA: RECONSTRUCCIÓN TOPOGRÁFICA Y ARQUEOLÓGICA
DEL CERRO DE LA MESA

Analizado el marco teórico en el que se desenvuelven las TIG y su desarrollo en la
Arqueología, se van a poner en práctica, siguiendo los objetivos del presente trabajo, dos
aplicaciones basadas en las TIG que, con una metodología novedosa, refuerzan la
investigación no invasiva del yacimiento del Cerro de la Mesa.

5.1. Técnica fotogramétrica “Structure from Motion” aplicada a fotografías aéreas
históricas del entorno del Cerro de la Mesa.

La relación entre el ser humano y el medio que habita es un hecho determinante dado el
impacto cultural, social y económico que esta conexión refleja en todos los ámbitos de la
vida humana. La Arqueología, en su intento de comprender el funcionamiento de las
sociedades del pasado, debe conocer las características propias del paisaje con el que
convivían estas personas como una herramienta más de la investigación científica entre todas
aquellas que componen el desarrollo de nuestra disciplina. El estudio del propio relieve
físico, que nos muestra las características que presenta la superficie terrestre, es
imprescindible para abordar posteriormente perspectivas simbólicas o económicas derivadas
del paisaje. Cuando se transforma por completo este contexto, ya sea provocado por agentes
naturales o por la mano humana, estamos perdiendo una fuente de información
imprescindible en la investigación del hábitat.

La restitución fotogramétrica, entendida como el conjunto de actuaciones que se realizan
sobre las fotografías para transformar su proyección cónica en una proyección ortogonal
para dibujar un mapa o plano (Sanjosé et al., 2004), permite solucionar el problema
acercándonos de manera fidedigna al relieve original. Se trata de una reconstrucción
paleotopográfica digital, que, en lugar de utilizar los mapas topográficos antiguos, ya
aplicado en otros yacimientos transformados como Tarraco (Orengo et al., 2011) o Caesar
Augusta (Longares et al., 2018), se vale de la fotografía aérea que proporciona la
información del paisaje antiguo. De este modo, con técnicas fotogramétricas se consigue una
Foto-Reconstrucción (FR-3D) de gran valor a nivel visual, con el modelado del relieve en
3D, y funcional, con la generación de diversos productos cartográficos que proporcionan a
la investigación una gran capacidad de análisis.

Es indispensable citar diversos trabajos recientes en la Península Ibérica que ya han
experimentado con esta técnica en otros yacimientos, demostrando su validez y capacidad
en entornos transformados, (Cerrillo, 2011; Pérez Álvarez et al., 2013) e incluso en el propio
Cerro de la Mesa (Charro, 2015). La novedad de este trabajo consiste en exponer la
metodología de una técnica reciente de fotogrametría digital como es el SfM-MVS
(Structure from Motion – MultiView Stereo), que agiliza y simplifica enormemente el
proceso de reconstrucción fotogramétrica digital, empleando un medio de información muy
útil para la Arqueología como es la fotografía aérea histórica.

Para este cometido es necesaria la combinación de dos medios esenciales: la información,
proporcionada por la fotografía aérea, y las herramientas para su tratamiento, que provienen
de la utilización del software de restitución fotogramétrica 3D. Estos dos elementos tienen
trayectorias diferentes en su aplicación en Arqueología. La fotografía aérea lleva ya varias
décadas proporcionando una fuente de datos fundamental para los estudios arqueológicos,
en tanto que amplía de manera sustancial el campo de visión.

19

<!-- p. 20 -->

La técnica de la fotointerpretación, cuyos antecedentes se remontan a finales del siglo XIX
(Orejas, 1992: 34), ha sido fundamental no solo para la identificación de evidencias
arqueológicas en las labores de prospección, sino también para enmarcar el estudio en la
visión global que representa el paisaje, cuyos elementos no se pueden estudiar en conjunto
de ninguna otra manera (Álvarez González, 1993: 268). Este concepto integrador y
determinante del medio como base de la Arqueología del Paisaje ha potenciado
enormemente la aplicación de estas técnicas desde los años 60, impulsado por los avances
tecnológicos que había experimentado la fotografía aérea como consecuencia de las
necesidades bélicas de la Segunda Guerra Mundial. La generalización de su uso en las
décadas posteriores es incontestable, también en la Península Ibérica donde su implantación
había sido mucho menor que en Reino Unido o Centroeuropa (Montufo Martín, 1991: 434435). El desarrollo ya comentado de las TIG ha ampliado el abanico de posibilidades que
nos ofrece la arqueología aérea. En este caso se utiliza como medio necesario para la
restitución fotogramétrica, una técnica ya conocida en el entorno de las TIG para la
producción cartográfica que con el avance técnico produce cada vez mejores resultados,
gracias a técnicas como la que se va a exponer a continuación, y con un campo de actuación
muy interesante en Arqueología, especialmente cuando tratamos paisajes que han perdido
su morfología antigua como el del Cerro de la Mesa.

La fotogrametría aporta las herramientas necesarias para el tratamiento de estas imágenes.
Esta disciplina se encarga de estudiar y definir con precisión la forma, dimensiones y
posición en el espacio de un objeto a través de medidas hechas sobre una o varias fotografías
(Bonneval, 1972), generando una visión estereoscópica que parte de los mismos principios
que permiten al cerebro humano generar visiones tridimensionales mediante varias imágenes
de un mismo punto. En esta ciencia ocupa un lugar muy importante la fotogrametría aérea,
que se vale de cámaras instaladas principalmente en aviones o satélites, y recientemente,
drones, para aplicar los fundamentos de estereoscopía (ver Figura 5.1) en la realización de
ortofotos, mapas topográficos y modelos tridimensionales (Sanjosé et al., 2004: 131-132).

Figura 5.1. Fundamentos de la estereoscopía artificial (izda.) y del solapamiento de los vuelos
fotogramétricos (dcha.) (Quirós Rosado, 2014).

20

<!-- p. 21 -->

La invención de la fotogrametría digital en los años 90 impulsa definitivamente esta técnica,
que a principios del siglo XXI abandona el espectro “hiper-especializado” en el que surge
para abrirse a todo tipo de ámbitos científicos que han aprovechado sus beneficios, como la
Arqueología. Este proceso de avance y accesibilidad viene necesariamente acompañado del
lanzamiento al mercado de software semiautomático de restitución fotogramétrica, que,
surgido en el marco de desarrollo de la fotogrametría terrestre de corto alcance, admite
usuarios sin conocimientos avanzados en fotogrametría a través de técnicas sencillas de usar
y dónde las fotografías se pueden obtener a bajo coste (Westoby et al., 2012) con cámaras
comerciales, smartphones o drones. Desde las primeras versiones de estos programas
pioneros como Photomodeler en 1999 y Photoscan en 2006, hasta la actualidad, el avance
ha sido constante, primando el procesamiento “inteligente” del programa en detrimento de
los procesos manuales, aumentando la velocidad, precisión y estabilidad (Charquero, 2016:
140-141).

Una de las técnicas que citábamos anteriormente, y que empiezan a incorporar estos
programas en sus versiones más recientes es el algoritmo Structure from Motion (SfM), que
complementado con el de Multi View Stereo conforma una tecnología (SfM-MVS)
destacadísima en el ámbito de la restitución fotogramétrica por la capacidad de generar fotoreconstrucciones 3D con nubes de puntos, ortofotos y Modelos Digitales de Elevaciones de
alta resolución, pero sobre todo por un marco de trabajo muy accesible y de bajo coste con
el uso de medios económicos (Tanarro y Gómez, 2014; Tomás et al., 2016). Con estas
virtudes, no es de extrañar que su uso empiece a expandirse en el ámbito de las Ciencias de
la Tierra donde también tiene su papel una ciencia multidisciplinar como la Arqueología.

La técnica SfM-MVS explota estos beneficios desmarcándose de la metodología de la
fotogrametría convencional, que en la actualidad recurre principalmente a las estaciones
digitales (DPWS, Digital Photogrammetric WorkStation) de gran precisión, pero costosas y
para cuyo manejo es necesario un elevado dominio práctico. En su lugar, el proceso se
simplifica: la geometría interna de la cámara, así como su posición y orientación se resuelven
automáticamente sin la necesidad de establecer una red de puntos de control con sus
posiciones tridimensionales conocidas. En vez de ello, esta operación se soluciona a partir
de la identificación simultánea de los puntos comunes correlacionados en las múltiples
fotografías superpuestas (Westoby et al., 2012; Fonstad et al., 2013; Micheletti et al., 2015).
La georreferenciación en coordenadas absolutas de la nube de puntos 3D obtenida,
intensificada gracias al algoritmo MVS, se consigue con el establecimiento de una serie de
puntos de control de coordenadas XYZ conocidas (Tomás et al., 2016). Con la nube de
puntos procesada, es posible generar los distintos productos cartográficos que se extraen
mediante el resto de los métodos procedentes de la fotogrametría digital, pero implicado en
un desarrollo mucho más accesible, barato y sin perder apenas calidad. La técnica SfM-MVS
está integrada en gran parte del software fotogramétrico semiautomático que comentábamos
anteriormente, pero para nuestra aplicación se utilizará la última versión del programa
ContextCapture, el software de modelado 3D realista de la empresa Bentley, en gran medida
gracias a la licencia de uso que se ha dispuesto, pero también por la aceptación general de
los buenos resultados que ofrece.

21

<!-- p. 22 -->

5.1.1. Material de partida: fotografías aéreas históricas

Aunque se trata de una técnica asociada a la fotogrametría de objeto cercano (menos de 300
metros del objeto fotografiado), la admisión de fotografías no calibradas amplía sobremanera
las capacidades de este método. Esta variabilidad incluye la capacidad de reconstruir escenas
mucho más amplias mediante fotografía aérea, y en base a nuestros intereses, histórica. El
empleo de la técnica SfM-MVS con la utilización de fotografía aérea histórica es una vía
incipiente aún en Arqueología (Gómez, 2012; Gómez et al., 2016), por lo que este trabajo
se enmarca en un intento de profundizar en esta vía de estudio y resaltar su utilidad en la
reconstrucción de paisajes históricos, como el de Azután y el Cerro de la Mesa, que tanto va
a poder ofrecer a la investigación de las sociedades del pasado.

Para la paleo-reconstrucción (SfM-MVS) en este TFM del paisaje del área de Azután, ha
sido necesario, por tanto, encontrar un vuelo fotogramétrico previo a la construcción del
embalse y todas las construcciones asociadas a él, cuyas obras terminaron en el año 1969.
Como es recurrente en la arqueología española, la mejor fuente de información de este tipo
para la época es el llamado “vuelo americano” de la USAF (United States Air Force),
realizado en dos tandas, la Serie A, entre 1945 y 1946 (ver Figura 5.2.A) y la Serie B, entre
1956 y 1957 (ver Figura 5.2.B), para toda la geografía española.

Figura 5.2.A. Fases de realización del vuelo de la Figura 5.2.B. Portada del informe final
serie A a lo largo del territorio español, entre 1945 y del Proyecto 54-AM-78 que realizó el
1946 (Quirós y Fernández, 1997). vuelo fotogramétrico de la Serie B entre
1955 y 1956 (AST 6 of 1372nd mapping
and charting squadron, 1997).

Los fotogramas del vuelo americano son documentos únicos del paisaje agrario preindustrial (prácticamente inalterado durante siglos) en el momento inmediatamente previo a
la profunda transformación social española en los años 60, que implicó grandes alteraciones
del entorno rural en el que se ubican gran parte de los yacimientos arqueológicos. Su uso,
por estos motivos, está ampliamente generalizado en la arqueología española como
herramienta básica de fotointerpretación y comparación con ortofotografía actual. En nuestro

22

<!-- p. 23 -->

caso, su función se basa en el empleo como soporte para la foto-reconstrucción 3D realista,
dado que sus características permiten la estereoscopía necesaria, frente a las fotografías
aéreas realizadas previamente en la zona con fines militares durante la Guerra Civil (19361939). Sin embargo, muchos autores han subrayado también los inconvenientes técnicos que
presenta el uso de los fotogramas del vuelo americano (Cerrillo, 2011: 152; Pérez Álvarez
et al., 2013; Pérez Álvarez et al., 2014), perfectamente enumerados en el trabajo de Cristina
Charro sobre el Cerro de la Mesa (Charro, 2015: 134). Proceden principalmente de la falta
de información sobre las peculiaridades de los fotogramas y su errónea interpretación, así
como el uso de distintas cámaras, incorrectas condiciones climáticas para la realización de
las fotografías, diferentes alturas de vuelo y, en general, la escasa calidad técnica,
radiométrica y de calibración.

En este TFM hemos trabajado con las dos series fotogramétricas, puesto que, aunque el
paisaje apenas varía en una década, las propiedades de los fotogramas en cada una de las
tandas sí son diferentes, permitiéndonos comparar sus resultados a la hora de realizar la
reconstrucción. Previamente, es imprescindible fijar un área de estudio correspondiente a las
necesidades del estudio que se realiza, no solo para acotar el espacio de trabajo sino también
para, entre otras razones, determinar cuántos fotogramas son necesarios adquirir. En nuestro
caso, se decidió establecer el área con un radio de al menos 1 kilómetro a partir del
yacimiento, de tal manera que incluye el entorno más inmediato del asentamiento donde el
entorno ha sido más transformado por la construcción de la presa. No obstante, las
posibilidades que ofrecen los fotogramas y el objetivo de generar cartografía como base para
estudios de tipo territorial, donde pueda analizarse el paisaje original del asentamiento como
conjunto nos ha llevado a ampliar el área varios kilómetros en dirección sur, este y oeste del
yacimiento, por lo que se van a alcanzar superficies mucho mayores en las reconstrucciones,
como se detallará posteriormente.

En definitiva, los fotogramas que se utilizan son: 4 fotografías de la Serie A,
correspondientes con los números 45, 46, 47 y 48, tomados el día 29 de septiembre de 1945
(SERIE A R-35 H-654 E 1-40800), y 5 fotogramas de la Serie B, que corresponden con los
números 1746, 1747, 1748, 1749 y 1750, tomados el día 7 de abril de 1956 (SERIE B R-24
H-654 E 1-32200). Los fotogramas, comprados en el Centro Cartográfico y Fotográfico
(CECAF) del Ejército del Aire, están digitalizados mediante Zeiss Photoscan TD a gran
resolución a 21 micras (un proceso de digitalización que terminó en 2011), que resulta en
una resolución de 1210 ppp, más alta incluso de la que se requiere en el equilibrio entre la
resolución del píxel y la de la propia fotografía (Charro, 2015: 135). Con una década de
diferencia, el avance tecnológico y las propias condiciones de ambos proyectos, es evidente
reseñar que los fotogramas resultantes de las series A y B presentan características
significativamente distintas (ver Tabla 1).

23

<!-- p. 24 -->

Tabla 1. Características básicas de los fotogramas usados para la restitución fotogramétrica
mediante SfM-MVS.

Distancia
Número de
Vuelo Año Altura (m) Escala Cámara Lente Focal
fotografías usadas
(mm)

Fairchild
Metrogon
SERIE A 1945 6000 1:40.000 K-17 y 154.40 4
Tipo I
K-18

Fairchild Metrogon
SERIE B 1956 4570-5550 1:33.000 153.78 5
T-11 Tipo II

La divergencia más importante es la escala, un factor determinante en cartografía. Esta
diferencia de escala se deriva de alturas de vuelo diferentes: para la serie A se decidió que
la escala de vuelo aproximada fuera 1:40.000 y las altitudes de 6000 metros, de ahí que las
alturas de vuelo varíen en función de la orografía (Pérez Álvarez et al., 2013: 3); para la serie
B las alturas de vuelo disminuyen y se sitúan entre 4570-5550 metros, con escalas
aproximadas de 1:30.000 (Pérez Álvarez et al., 2014: 3)

La menor escala de nuestros fotogramas de la serie A (1:40.800) presenta un problema a la
hora de realizar la restitución mediante SfM-MVS, frente a los beneficios de la empleada en
la serie B para el entorno del Cerro de la Mesa (1:33.000). La utilización de cámaras
diferentes (Fairchild K-17 y K-18 para la Series A, y Fairchild T-11 para la Serie B) con
parámetros específicos es también un factor diferenciador (Charro, 2015: 134). La distancia
focal, que representa la distancia existente entre el foco de la lente y el negativo de la película
(López Vergara, 1988) indica el ángulo de visión y varía en cada serie: 154.40mm para la
Serie A y 153.78mm para la Serie B. A su vez, elementos propios de la cámara como son el
obturador y el diafragma también generan productos fotográficos acordes a sus propias
especificaciones técnicas, sin olvidar los tipos de distorsión, como la distorsión radial,
fundamental en fotogrametría pues representa la deformación que sufre la imagen de un
objeto alejándola de su representación bidimensional “perfecta” (Cuadrado Méndez, 2001).
Las cámaras utilizadas en 1945 estaban equipadas con la lente Metrogon Tipo I, de distorsión
no controlada, que generarían una distorsión radial no superior a 240 micras. La
implantación de la lente de tipo II de uso fotogramétrico en la serie B permitió doblar la
calidad de los fotogramas, con una distorsión controlada que no superaría las 120 micras
(Pérez Álvarez et al., 2013; Pérez Álvarez et al., 2014). Estos y otros factores menos
significativos, unidos al propio deterioro en la conservación de los originales, que ha
afectado especialmente a la serie más antigua, influyen en el resultado final de la
reconstrucción que queremos realizar, como veremos más adelante.

Estos fotogramas constituyen la materia prima con la cual se realiza la foto-reconstrucción
3D. Sin entrar a explicar con detalle la base teórica que subyace en la metodología general
de cualquier técnica fotogramétrica, bien explicada en numerosos manuales (Sánchez
Sobrino, 2007; Santamaría Peña y Sanz Méndez, 2011; Quirós, 2014), en este proyecto nos
vamos a valer del software novedoso como es Bentley Context Capture, y la tecnología SfMMVS integrada en él, que simplifica enormemente al usuario la realización de los procesos
técnicos que se detallan a continuación.

24

<!-- p. 25 -->

5.1.2. Determinación de los parámetros de la cámara.

La restitución fotogramétrica se basa principalmente en la resolución de la orientación de las
cámaras, es decir, la reconstrucción exacta de los haces de rayos impresionados y su
colocación y posición respecto al terreno en el momento del vuelo fotogramétrico. En la
restitución fotogramétrica tradicional de fotografías aéreas, que usa estaciones de
fotogrametría digital (Digi3D, PhotoMOD, e-foto, entre otros programas), esta operación se
realiza en tres fases bien diferenciadas, durante las cuales el ajuste del par fotogramétrico se
produce al solucionar la orientación interna, externa y absoluta de los fotogramas. La
habilidad principal de la técnica SfM-MVS consiste en usar algoritmos de ajuste que estiman
la geometría 3D de la escena, las posiciones de la cámara y sus parámetros intrínsecos, es
decir, soluciona automáticamente la orientación interna de la cámara, y lo que es más
importante, sin la necesidad de disponer de los certificados de calibración (Smith et al.,
2016). Este factor es el que nos posibilita la utilización de vuelos antiguos, en los cuales esta
información (distancia focal, posición de las marcas fiduciales, distorsión de las lentes, etc.)
no siempre está disponible, ya que con frecuencia se han perdido los parámetros de
calibración de la cámara con la que se realizó el vuelo (ver Figura 5.3.A).

De este modo, se consigue combinar la automatización de un proceso costoso como es la
solución de la orientación interna con la utilización de vuelos fotogramétricos antiguos que
necesitamos para el estudio de paisajes históricos. Los sotfwares de fotogrametría que
utilizan la técnica SfM-MVS, empleados básicamente para fotogrametría terrestre de objeto
cercano, recogen de manera automática el modelo y las propiedades de la cámara, mediante
la identificación simultánea de los puntos comunes correlacionados en las múltiples
fotografías superpuestas, como se ha detallado en el apartado anterior.

Así, el programa combina esta estimación con la información asociada a cada fotografía
(ficheros Exif o EXchangeable Image File) y el cálculo de ajuste por haces que reconstruye
la red geométrica interna (Eltner y Sofia, 2020). El software reduce al usuario todo este
proceso en la especificación de un solo parámetro fundamental, la distancia focal, aunque
algunos softwares mejoran el procesamiento si se especifica el tamaño del sensor, como es
el caso de Bentley ContexCapture, un factor que se ha podido demostrar al analizar los
resultados obtenidos.

El proceso comienza con la introducción de los fotogramas en ContextCapture, en este caso
dividido en dos proyectos para 1945 y 1956, respectivamente. Cada bloque de fotogramas
debe ser caracterizado con los parámetros que necesita el programa para la reconstrucción.
Obligatoriamente, debe ser la distancia focal, que en los fotogramas de ambos vuelos
fotogramétricos es cónico, y por tanto es el valor que se especifica: 154.40mm para 1945 y
153.78 mm para 1956. Con el objetivo de mejorar el ajuste, se ha incluido también el tamaño
del sensor, utilizando un valor de 23 cm (230 mm), que representa el tamaño de los
fotogramas (ver Figura 5.3.B).

25

<!-- p. 26 -->

A B
Figura 5.3.A. Inscripción lateral de los fotogramas de la Serie B. En orden, de arriba abajo: reloj,
distancia focal calibrada, contador de exposiciones, número de serie del objetivo, número de serie
de la cámara, marcas fiduciales y altímetro.

Figura 5.3.B. Marco de trabajo en Bentley Context Capture, con el bloque de fotogramas
introducido, así como la información necesaria: tamaño del sensor y distancia focal.

5.1.3. Establecimiento de los puntos de control (PC) para georreferenciar la nube de puntos
3D

Estos algoritmos de correlación, descritos con más detalle en artículos técnicos (Westoby et
al., 2012; Remondino et al., 2012; Fonstad et al., 2013; Micheletti et al., 2013; etc.), resultan
en una nube de puntos en posición 3D lograda prácticamente para cada píxel de la imagen,
pero referida a un sistema de coordenadas arbitrario y sin escalar. La solución a este
problema de posicionamiento real se consigue al establecer una serie de puntos (conocidos
como puntos de control o puntos de apoyo) con coordenadas absolutas reconocibles en los
fotogramas, que nos permitan georreferenciar el producto y extraer posiciones absolutas y
tridimensionales en cualquier punto del mapa. De este modo se superan rápidamente las
orientaciones externa y absoluta de las restituciones fotogramétricas convencionales.

Esta tarea sí requiere un proceso manual riguroso que realiza el usuario en el software. Para
empezar, se prepara la cartografía aérea de manera que se determine correctamente la zona
de solapamiento, que debe ser en al menos 3 fotografías, ya que cada punto de control (PC)
ha de ser posicionado en cada uno de los fotogramas solapados. La determinación del solape
se puede realizar en cualquier programa de diseño gráfico, como Corel Draw en nuestro
caso: el ajuste de los fotogramas de los vuelos sobre el Cerro de la Mesa da lugar a dos zonas
de solapamiento para la Serie A, y tres zonas para la Serie B (ver Figura 5.4). Su delimitación
es imprescindible, pues es en estas áreas limitadas en las cuales se van a posicionar los
llamados puntos de control (PC), siendo las únicas zonas donde se produce el solapamiento
en tres fotogramas

26

<!-- p. 27 -->

Figura 5.4. Mosaico de fotogramas aéreos (Serie A, arriba, Serie B, debajo) compuesto en el
programa de diseño gráfico Corel Draw para el establecimiento de los solapes (coloreados).

El proceso de establecimiento de los PC se ha realizado mediante software SIG, en concreto
ArcGIS, donde se utiliza como soporte la ortofoto del PNOA de máxima actualidad que
corresponde al área del yacimiento, y las capas de líneas que se han creado para ilustrar las
áreas de solapamiento.

A partir de estos medios, se identifican una serie de elementos en el terreno sobre los cuales
se determinan los puntos de apoyo (cruces de caminos, esquinas de edificios, árboles, etc.)
y que cumplen unos requisitos: son claramente reconocibles tanto en la ortofoto actual como
en cada uno de los fotogramas históricos correspondientes (ver Figura 5.5), y se encuentra
en el área de solapamiento de los tres fotogramas (Sanjosé et al., 2004). La calibración es
correcta si se establece un número mínimo de puntos de control por cada zona de solape,
superado en nuestro caso con 11 en los fotogramas de 1955 y 8 en los de 1945.

27

<!-- p. 28 -->

Figura 5.5. Los puntos de control deben situarse sobre elementos inalterados y reconocibles en el
terreno desde la captura de la fotografía histórica, de 1945 (A) o 1956 (B) hasta la actualidad (C).

Para que la georreferenciación funcione, es imprescindible extraer las coordenadas absolutas
y los valores altimétricos de los puntos de control, recogidos y almacenados en una capa
shapefile. Las coordenadas X e Y, referidas en el sistema con el que trabajamos (ETRS89UTM: Zona 30N) se registran a partir de la ortofoto con una herramienta rápida (Data
Management Tools-Features→Add XY Cordinates), pero para extraer el valor altimétrico Z
debemos recurrir a un Modelo Digital del Terreno que contenga esta información. Para este
cometido se ha decidido partir de los datos proporcionados por la cobertura LIDAR del Plan
Nacional de Ortofotografía Aérea (PNOA). A pesar de que en este trabajo la utilización del
LiDAR se enfoca principalmente hacia la interpretación arqueológica, como se explicará en
la segunda aplicación, no debe olvidarse que esta tecnología se fundamenta en la adquisición
precisa de la información topográfica del terreno.

Por esta razón se ha decidido utilizar el MDT05 descargado directamente del Centro
Nacional de Información Geográfica. Este modelo digital del terreno se genera a partir de la
1ª Cobertura LIDAR del PNOA con paso de malla de 5 m, la más precisa posible en el Plan
Nacional LIDAR pues para la zona solo se dispone de los resultados de la primera cobertura
(año 2009). Con el MDT introducido en ArcGIS, los valores altimétricos se interpolan con
los PC de ambos vuelos mediante la herramienta Spatial Analyst Tools→Extraction-Extract
Values to Points. Al concluir esta tarea, los puntos de control registran las coordenadas XYZ
requeridas para la georreferenciación de la nube de puntos.

28

<!-- p. 29 -->

La dificultad que entraña este proceso se encuentra en la identificación de los sitios óptimos
para la correlación, dadas las características de los fotogramas antiguos y el propio
transcurso del tiempo (ver Figura 5.6). En este sentido, hay una gran diferencia cualitativa
entre ambas series, derivada de la escala, la calidad técnica de los fotogramas, la pequeña
área de solape en tres fotogramas y el estado de conservación de algunos de ellos, siempre
inferior en todos estos factores la serie más antigua. Ya en el programa de fotogrametría, se
introducen manualmente los puntos de control estableciendo la posición en cada uno de los
fotogramas en los que se identifican, con sus valores espaciales correspondientes.

A B

Figura 5.6. Puntos de control establecidos para los modelos de 1945 (A), sobre el fotograma nº46,
y 1956 (B), sobre el fotograma nº 1748.

5.1.4. Aerotriangulación o alineación de las fotografías y obtención del modelo 3D

Mediante los pasos descritos se ha especificado la información requerida por el programa
para proceder a la reconstrucción. A partir de aquí, Context Capture realiza la estimación de
las propiedades y la posición de cada fotograma en un proceso denominado
aerotriangulación (a veces abreviado como AT), apoyado para la georreferenciación con los
puntos de control, con el cual se produce un nuevo bloque de fotografías, esta vez
correlacionado y ajustado (ver Figura 5.7). La automatización del proceso de
aerotriangulación es la clave de la técnica SfM-MVS, pues se trata de un algoritmo
fotogramétrico técnico y costoso que se salva fácilmente y de manera mecánica, sin
necesidad de disponer de ordenadores actuales de máxima potencia, en un tiempo muy
reducido.

El resultado final es un modelo digital de superficies (MDS) o tridimensional (malla 3D o
mesh 3D), que incluye el entramado de polígonos y vértices ajustado a partir de los
fotogramas aéreos (ver Figura 5.8). Context Capture establece entonces el modelo
tridimensional en lo que denomina un marco de “reconstrucción”, el espacio de trabajo desde
el cual se produce la generación automática de los productos cartográficos resultantes de la
restitución fotogramétrica mediante la técnica SfM-MVS.

29

<!-- p. 30 -->

1 2

3 4

Figura 5.7. Proceso gráfico de aerotriangulación: Estimación de la posición de cada
fotograma (1), establecimiento de puntos de control y puntos de enlace sobre los solapes (2); y
generación de la malla tridimensional (3-4).

A

B

Figura 5.8. Visualización en el programa ContextCapture Viewer de los modelos 3D generados en
la FR-3D correspondientes a las reconstrucciones de 1945 (A) y 1956 (B).

30

<!-- p. 31 -->

5.2 Aplicación de la tecnología LiDAR a la prospección arqueológica del Cerro de la
Mesa.

El avance de las técnicas no invasivas en la investigación arqueológica se sustenta sobre un
desarrollo tecnológico que está permitiendo mejorar el estudio y puesta en valor de los
yacimientos sin la necesidad de intervenir en ellos (o al menos, mínimamente), a la vez que
proporciona nuevas herramientas para la prospección, documentación y análisis de los restos
arqueológicos con el objetivo de minimizar al máximo el impacto sobre el patrimonio (Dietz
et al., 2011). Ante esta realidad, la Arqueología debe servirse de nuevas tecnologías
procedentes de otros campos de investigación para su propio beneficio como son, tal y como
se está demostrando, las TIG.

Siguiendo esta línea, la segunda aplicación del trabajo se centra en una técnica de medición
remota que lleva una década popularizándose en el ámbito científico por la precisión y
espectacularidad de sus resultados, y cuyo uso se está expandiendo rápidamente en
Arqueología: el LiDAR (acrónimo del inglés, Light Detection and Ranging o Laser Imaging
Detection and Ranging). La tecnología LiDAR se basa en un escáner láser compuesto por
transmisor y receptor, que emite pulsos de luz, una Unidad de Medición Inercial (IMU), un
sistema de posicionamiento global (GPS) y un ordenador que controla el sistema y almacena
los datos registrados por el resto de los componentes. El sensor emite una cantidad masiva
de pulsos de luz sobre el terreno, cuya señal reflejada queda registrada en el receptor. La
medición del tiempo que tarda el láser reflejado en volver al sensor permite calcular la
distancia con el terreno, y constituye el principio básico de la tecnología LiDAR. Así, el
sistema utiliza la posición y la orientación del sensor proporcionadas por el GPS y el IMU
para calcular la coordenada precisa de cada punto realizado (Reutebuch et al., 2005).
Implantado sobre plataformas áreas (LIDAR aerotransportado: avión, dron, satélite, etc.) o
terrestres (TLS, Terrestrial Laser Scanner), este proceso permite generar masivas nubes de
puntos tridimensionales georreferenciados de gran precisión y resolución con los cuales se
generan MDT.

El LiDAR genera, de este modo, la representación topográfica del terreno más exacta que se
puede realizar hoy en día (Berrocal-Rangel et al., 2017: 196), pero sus virtudes no terminan
ahí. Una de sus cualidades específicas consiste en el almacenamiento de los múltiples
retornos por cada pulso emitido, de manera que registra una clasificación que va desde la
superficie o suelo, pasando por vegetación baja, media y las copas de los árboles, así como
estructuras y edificaciones (Rouco et al., 2020). La clasificación de estos retornos resulta en
una lista de clases que definen el tipo de objeto que reflejó el pulso láser en función de la
profundidad, y que se pueden filtrar y seleccionar en función de los intereses de tratamiento.
La utilización de un formato estándar (LAS) permite su tratamiento en los SIG para la
generación de Modelos Digitales de Superficies y Modelos Digitales del Terreno con una
precisión de en torno a 30-50 cm en planimetría y de entre 15-20 cm en altimetría,
comparativamente superiores a las de un mapa topográfico a escala 1:5.000 e incluso, en
altimetría, de 1:1.000 (Rosales y Rodrigo, 2012: 57). A su vez, aventaja a la ortofotografía
aérea, en su variante aerotransportada, que no depende de las condiciones atmosféricas a la
hora de la realización de los vuelos.

La importancia del LiDAR en el entorno de la metodología no invasiva es evidente, pues se
trata de un sistema de detección remota de la superficie del terreno al igual que el resto de
herramientas vinculadas a la teledetección, basadas en la adquisición de información sobre
un objeto a distancia, es decir, sin que haya contacto material entre el objeto o sistema
observado y el observador (López García y Caselles, 1991) y su proceso de tratamiento en

31

<!-- p. 32 -->

el contexto de una determinada aplicación sobre un elemento de la superficie terrestre
(Chuvieco, 1996: 25). La utilización del LiDAR (junto a la fotointerpretación que se lleva a
cabo durante todo el trabajo) en nuestro análisis no hace sino resaltar, además de la utilidad
arqueológica que se expondrá a continuación, el gran valor que constituye el extenso
conjunto de técnicas asociadas a la teledetección en la obtención de información geoespacial
que manejan las TIG.

Con todas estas virtudes, la tecnología LiDAR fue rápidamente adoptada para aplicaciones
arqueológicas. Se desarrolla a partir de antecedentes de escáneres láser con fines militares y
meteorológicos en los años 60, aunque no es hasta los años 80 cuando la NASA fabrica los
instrumentos que se convertirán en precursoras del LiDAR moderno. Con la entrada del
nuevo siglo su uso se expande hacia multitud de disciplinas, entre ellas la Arqueología. La
capacidad de producir modelos tridimensionales del terreno muy precisos y de explorar
grandes superficies cubiertas de vegetación tenía un impacto directo sobre la prospección
arqueológica (Opitz et al., 2015: 6), pues no solo complementaba a la fotografía aérea en sus
funciones, sino que, como hemos comentado, ampliaba sus posibilidades.

La representación realista del relieve topográfico, en 3D y apoyado por visualizaciones
realistas como el sombreado y otras no realistas (pendientes, sombreado multidireccional,
etc.), unido a la virtud de traspase de la vegetación superan los límites de la fotogrametría
clásica, a la vez que sirve de soporte para la creación de Modelos Digitales del Terreno
(MDT) con una mayor resolución espacial. Con esta perspectiva, el LiDAR lleva poco más
de una década aplicándose en el ámbito de la Arqueología del Paisaje europea con notable
popularidad en el estudio del entorno prehistórico inglés (Bewley et al., 2005; Crutchley,
2010), Escandinavia (Risbøl et al., 2013; Goodchild et al., 2017) o los más mediáticos en
las ciudades precolombinas de la selva centroamericana (Chase et al., 2014; Brewer et al.,
2017; Rosenswig y López-Torrijos, 2018), aunque cada vez más se implanta en el
postproceso de información arqueológica a menor escala: reconstrucciones estratigráficas,
aplicaciones en restos o estructuras, batimetría, etc. (Chase, 2017: 91).

En la arqueología española se conocen ampliamente los beneficios de esta técnica a la vez
que crece, si bien mucho más lento de lo que su implantación podría reflejar, su impacto en
las publicaciones académicas. La publicación de los datos del Plan Nacional de
Ortofotografía Aérea, que en dos fases (2009-2015 y 2015-2020) han realizado una cobertura
LIDAR de todo el territorio, ha espoleado en gran manera su uso con fines arqueológicos al
proporcionar una fuente de información fiable y precisa. Como señalan algunos autores
(Berrocal-Rangel et al., 2017: 195-196), su aplicación a casos concretos ha sido hasta hace
poco algo escasa pero se encuentra inmersa ya en una tendencia ascendente como
demuestran investigaciones muy especializadas a lo largo de la geografía española que han
proporcionado grandes resultados en la arqueología romana, con la detección de
campamentos militares (Costa-García y Casal, 2015; Cordero-Ruiz et al., 2017), estructuras
arquitectónicas (Monterroso-Checa, 2017) y evidencias de minería (Fernández-Lozano et
al., 2019), con igual éxito en el estudio del paisaje megalítico gallego (Carrero-Pazos et al.,
\2014) y extremeño (Cerrillo, 2017), donde se ha trabajado además con códigos informáticos
diseñados por el equipo investigador para agilizar el tratamiento de los datos LiDAR. La
notable difusión reciente de los beneficios de esta técnica no hace sino resaltar el importante
papel que el LiDAR va a protagonizar en la teledetección arqueológica durante los próximos
años.

32

<!-- p. 33 -->

5.2.1. Planteamiento, material de partida y preparación de los datos.

Esta aplicación nace con el objetivo de profundizar en el uso de esta técnica y su apoyo en
el estudio arqueológico del Cerro de la Mesa. La aplicación se basa en la generación de un
MDE a partir de los datos extraídos del LiDAR y su posterior tratamiento para la detección
de estructuras ocultas principalmente en las zonas cubiertas de vegetación, donde esta
técnica encuentra su mayor virtud. La interpretación de esta información se integra en un
proceso de prospección en el cual se va a cotejar con los resultados de la utilización del
georradar (GPR) en la zona protegida del yacimiento, cuyos detalles se expondrán más
adelante durante la presentación de los datos obtenidos en la presente aplicación.

La existencia de un catálogo abierto de cobertura LIDAR nacional ofrece una herramienta a
disposición de los investigadores que de otra manera sería difícil de alcanzar en ámbitos no
especializados, al hablar de una tecnología que necesita de medios técnicos costosos. Para
conseguir la nube de puntos perteneciente al entorno del yacimiento recurrimos al PNOA,
disponible en el Centro de Descargas del Centro Nacional de Información Geográfica
(CNIG), al igual que se ha realizado en la primera aplicación.

Llegados a este punto, surge un primer inconveniente al no disponer de los datos recientes
de la segunda cobertura (2ª fase del proyecto PNOA-LiDAR), realizada con sensores de
última generación y que supera ampliamente en resolución a la primera, planificada
originalmente para el año 2020 en la mitad meridional de la provincia de Toledo, pero que
hasta la fecha no han sido publicados.

En su lugar, debemos recurrir a la nube de puntos LIDAR proporcionada por la primera
cobertura y realizada en la región en el año 2009, con una densidad de 0,5 puntos/m2,
precisión altimétrica de ≤ 40 cm y planimétrica de ≤ 30 cm, referenciada en el datum
ETRS89 y distribuida en formato LAZ. El fichero digital adecuado para nuestro trabajo,
distribuido en una cuadrícula de 2x2 km 2, es el LOTE7-CLM-320-4406-ORT-CLA-CIR, en
su versión coloreada en RGB. Esta cuadrícula abarca el embalse de Azután en la confluencia
de los ríos Tajo y Huso, en la cual se encuentra el yacimiento y su entorno más inmediato
donde enfocamos este trabajo (ver Figura 5.9).

A B

Figura 5.9. Distribución regional de las coberturas del PNOA realizadas hasta enero de 2020 (A)
y en detalle, la cuadrícula del fichero correspondiente al embalse de Azután (B) donde se localiza
el yacimiento. (Fuente: Instituto Geográfico Regional).

33

<!-- p. 34 -->

Con el material adquirido, es necesario un paso previo de preparación para que el tratamiento
de los datos, que se realiza en un entorno SIG (ArcGIS 10.4), sea el adecuado. En este
proceso es imprescindible descomprimir el fichero LAZ en el que viene distribuida la nube
de puntos. Existen diversas fórmulas para realizar esta acción, pero en este caso recurrimos
al uso de las LASTools, herramientas de código abierto programadas por los creadores de
Rapidlasso GmbH (https://rapidlasso.com/). Estas herramientas, integradas en ArcGIS,
permiten una rápida descompresión en archivos con extensión .LAS (LASTools Production
→ LasZip Pro), un formato que sí permite la visualización y tratamiento de las nubes de
puntos en un SIG. El archivo debe ir almacenado en un Dataset LAS, donde se puede calcular
sus estadísticas, ajustar y examinar la clasificación y retorno de los puntos, características
clave del LIDAR.

En este punto es posible realizar el siguiente paso en la preparación de los datos: la
generación de un MDE (Modelo Digital de Elevaciones) a partir de la nube de puntos. No
olvidemos que la mayor virtud del LIDAR es la capacidad de clasificación de los distintos
objetos que reflejaron los pulsos láser en cada uno de los retornos, y que, por tanto, es capaz
de registrar los valores altimétricos del suelo tras superar las distintas capas de vegetación o
la estructura de los edificios.

De este modo, se desechan del LAS Dataset todos los puntos excepto aquellos pertenecientes
a la segunda clase, que representan los valores del suelo (Ground) y se consigue generar
rápidamente un MDE utilizando la herramienta LAS Dataset to Raster (Conversion Tools →
To Raster), seleccionando una interpolación de tipo “Binning” y un método de asignación
de celdas por media (Average). La resolución del MDE es un factor determinante,
condicionado siempre por la densidad de puntos con la cual se realiza la cobertura LiDAR,
en nuestro caso de 0,5 puntos/m2. Conocido este dato, es posible asignar el tamaño de celda
del ráster, que, según el método general, es recomendable que sea cuatro veces mayor que
la densidad de puntos. A pesar de que, según la norma, la resolución adecuada sería de 2
metros, se ha optado en nuestro caso por un lado de celda de 1 m, con el fin de mejorar la
visualización de los modelos que se obtienen con Relief Visualization Toolbox (ver Figura
5.10).

34

<!-- p. 35 -->

A C

B

D

Figura 5.10. Visualizaciones del archivo LIDAR: Nube de puntos sin clasificar, coloreados en RGB
en ArcScene (A-B) y como nube de puntos con la clasificación de todos los puntos por clases (C).
Debajo, el MDE generado, visualizado mediante Hillshade (D).

35

<!-- p. 36 -->

5.2.2. Tratamiento visual del LIDAR: el programa Relief Visualization Toolbox

Es preciso dejar claro que el LIDAR no refleja una imagen íntegra de las estructuras
soterradas como hace el georradar, sino que genera una representación topográfica muy
exacta de la superficie a distintos niveles, que con su debido tratamiento visual puede ayudar
a la identificación de restos arqueológicos ocultos bajo la vegetación o el propio suelo. Este
tratamiento se basa principalmente en el sombreado analítico del relieve, al cual se han ido
incorporando técnicas de visualización alternativas que enriquecen la metodología de
representación de Modelos Digitales del Terreno en 2D (Hesse, 2010; Cordero-Ruiz et al.,
2017; Dübel y Schumann, 2017).

El sombreado analítico del relieve parte del popular método de representación digital del
terreno en el cual se utiliza la iluminación del paisaje para la generación de un contraste de
luz y sombras, revelando la topografía, que se conoce como Hill-Shading. Sin embargo, el
estudio sobre LIDAR necesita de una sofisticación de esta técnica que se consigue con el
sombreado múltiple desde distintas direcciones, y, sobre todo, de métodos recientes que
superan las limitaciones del Hill-Shading para representar estructuras paralelas al eje de
iluminación (Štular et al., 2012). Así, recientemente, y en relación con la disponibilidad de
datos LiDAR, se han desarrollado técnicas y algoritmos para representar, modelar y
visualizar el relieve, en especial para diferenciar y detectar los detalles de la superficie del
suelo, entre las cuales cabe destacar las siguientes:

▪ Sky View Factor (SVF): los algoritmos de la técnica SVF se valen de luz difusa que
ilumina el relieve desde el hemisferio celestial, creando contrastes entre crestas y
terraplenes planos (muros, túmulos), más iluminados, frente a las depresiones
(trincheras, fosos, surcos arados, etc.) más oscuras (Zakšek et al., 2011; Kokalj et
al., 2011).

▪ Simple Local Relief Modeling (SLRM): la técnica SLRM procesa datos de modelos
digitales de elevación (MDE) de alta resolución derivados de LiDAR para crear
modelos de relieve local, es decir representa las diferencias de elevación locales a
pequeña escala después de eliminar las formas del paisaje a gran escala de los datos.
De esta forma se consigue mejorar la visibilidad de características topográficas
superficiales a pequeña escala, independientemente del ángulo de iluminación
(Hesse, 2010; Novák, 2014). Así, en estudios arqueológicos, este tipo de modelo se
utiliza para la prospección y cartografía arqueológica de elementos tales como
túmulos, terraplenes lineales y circulares, caminos hundidos, terrazas agrícolas, etc.
(Hesse, 2010).

▪ Principal Component Analysis (PCA): algoritmo que maximiza el contraste de la
combinación de sombreados múltiples en distintas direcciones para reducir el ruido
y simplificar el análisis (Bennett et al., 2012).

36

<!-- p. 37 -->

En conjunto, todas estas técnicas forman parte de un amplio método de visualización realista
que pretende explotar al máximo las capacidades de interpretación del MDE generados a
partir de las nubes de puntos del LiDAR. Para la aplicación práctica de estos métodos en
nuestro estudio se ha elegido Relief Visualization ToolBox (RVT), uno de los mejores
programas, de código abierto, desarrollados en este ámbito gracias al Instituto de Estudios
Antropológicos y Espaciales (IAPŠ) del Centro de Investigación de la Academia Eslovena
de las Artes y las Ciencias (ZRC SAZU). El programa RVT trabaja a partir del archivo (en
formato GeoTIFF) del MDE generado previamente, al cual aplica las técnicas de sombreado
analítico del relieve, desde la más sencilla (sombreado analítico) a otras más elaboradas
como el sombreado desde múltiples direcciones (Orengo y Petrie, 2018) y alternativas
perfeccionadas como el SVF y el PCA, junto a visualizaciones especializadas como el mapa
de pendientes, el SLRM o la dominancia local, entre otros. La virtud del programa reside
tanto en la agilidad y facilidad con la cual se producen los resultados como por la variedad
de fórmulas utilizadas, que hacen uso de las técnicas más avanzadas hasta el momento en
este estudio. El resultado aborda, desde distintas perspectivas, la información más efectiva
para la detección de pequeñas estructuras que se puede extraer del MDE generado a partir
del LiDAR.

\6. RESULTADOS: PRESENTACIÓN, CARACTERÍSTICAS Y TRATAMIENTO
SIG DE LOS PRODUCTOS CARTOGRÁFICOS

6.1. Restitución paleotopográfica: productos derivados e interpretación

Los productos cartográficos que se han generado mediante la aplicación de la técnica de
fotogrametría “Structure from Motion-Multiview-Stereo (SfM-MVS) a las fotografías
aéreas históricas son una malla 3D, una ortofoto, un Modelo Digital de Superficies (MDS)
y una nube de puntos. Se trata de un conjunto de información destinada para su tratamiento
en el ámbito de los SIG o CAD, y se presenta como base topográfica para futuros análisis
que se quieran realizar en el entorno del Cerro de la Mesa desde la perspectiva del relieve
primigenio.

6.1.1. Precisión y calidad de los productos cartográficos.

Uno de los objetivos principales de esta aplicación era la de comparar la precisión entre la
utilización de los fotogramas de la Series A y B del llamado vuelo americano a la hora de
aplicar la técnica SfM-MVS. En esta cuestión, es necesario mostrar los resultados
cuantitativos que mejor reflejan la comparativa entre ambos modelos. La confrontación se
respalda en el informe de calidad que genera el programa resultado de la aereotriangulación,
a partir del cual se pueden extraer datos muy significativos. En este informe se detallan
valores generales del modelo como la escala obtenida, la dimensión de la reconstrucción, la
resolución espacial media, la calibración de la cámara, y el RMSE (Error Cuadrático Medio)
junto al error de los puntos de control, entre los más importantes (ver Tabla 2 y ANEXOS).

37

<!-- p. 38 -->

Tabla 2. Informe de calidad: datos generales de las reconstrucciones generadas mediante SfM-MVS.

RMSE Puntos clave Puntos de Resolución Extensión
Reconstrucción Escala General detectados en enlace (GSD) total (m2) (píxeles) cada foto generados

43049
1945 1:2652 0,88 m/píxel 35,3 1,15 39
(mediana)

44963
1956 1:1868 0,62 m/píxel 41,08 0,82 270
(mediana)

En un análisis más específico de estos valores, es posible afirmar que la principal diferencia
radica en la escala a la que se han conseguido realizar ambas reconstrucciones, resultado de
las propias alturas de ambos vuelos fotogramétricos. Como ya se ha señalado en la
metodología, las características de la serie B admiten resultados significativamente mejores,
tal y como refleja las escalas conseguidas por defecto: 1:1868 en la de 1956 frente al 1:2652
generado para la reconstrucción de 1945. En consecuencia, la resolución espacial de los
rásteres (Ortofoto y MDS) se ve condicionada por este factor: el GSD (Ground Sampling
Distance), que mide la distancia entre dos centros de píxeles consecutivos, es de 0,62 m para
la serie B y de 0,88m para la serie A. Otros dos elementos clave, como los puntos clave
(Keypoints) y de enlace (Tie Points) que el programa detecta automáticamente en cada
fotograma, condicionan la calidad de los resultados y reflejan eficazmente las diferencias
entre ambas reconstrucciones.

Ante todo, la suma de la escala y la resolución unido a la propia calidad radiométrica y a las
condiciones de conservación de los fotogramas puede ser medida con el Error Cuadrático
Medio (RMSE). El RMSE representa el error entre un valor predicho por un modelo
(reconstrucción) y el valor observado (real) a través de la desviación típica respecto a los
Puntos de Control, por lo que resulta imprescindible a la hora de valorar la precisión.

El informe de calidad expone los resultados desglosados del error que supone cada PC (11
en 1956, 7 en 1945 por la exclusión final de uno de sus puntos) en el modelo. En la tabla se
detallan, en metros, el error global horizontal, vertical y error 3D (la suma del cuadrado de
las dos anteriores) de cada PC, así como su RMSE en píxeles y el RMS de distancia a rayos
(línea 3D entre la posición de la fotografía y los puntos de control observados en ella), como
parte de un conjunto de información que se ha simplificado para su visualización en este
trabajo (ver Tabla 6.2).

38

<!-- p. 39 -->

Tabla 3. Informe de calidad: Detalle del RMSE de los Puntos de Control utilizados en cada reconstrucción.

RMSE RMSE RMSE
RMSE Error RMSE Error
Modelo Nº PC Reproyección Distancia a Error
vertical 3D
(píxeles) rayos (metros) horizontal

X=0,14
1945 7 1,03 44,23 0,74 0,81
Y=0,31

X=0,16
1956 11 0,53 3,07 0,18 0,29
Y=0,16

La reconstrucción de 1956 arroja un RMSE Global de los puntos 3D de 0,29 metros, así
como un RMSE de reproyección de 0,53 píxeles. Dadas las características de los fotogramas
y los objetivos de nuestro trabajo se trata de una precisión realmente adecuada para el estudio
topográfico del área de estudio. La reconstrucción de 1945, por su parte, presenta un RMSE
Global de los puntos 3D de 0,81 metros y de reproyección de 1,03 píxeles, pero está
condicionado por un factor negativo como es el RMS de distancia a rayos que aparece muy
elevado, de 44m (frente a los 3m de 1956), un indicador de una precisión bastante más
irregular. Es necesario incluir un agente principal que condiciona la validez de la restitución:
la escasa calidad radiométrica que afecta a ambos vuelos fotogramétricos, pero
especialmente al de 1945, y cuyas consecuencias son evidentes en la generación del producto
geográfico final.

Con estos valores se componen los diversos productos cartográficos resultantes de las
restituciones en ambas fechas: por un lado, los modelos 3D y las ortofotos que cumplen su
función en el análisis visual, por otro, el MDS (Modelo Digital de Superficies) y la nube de
puntos como herramientas en virtud de la información altimétrica que aportan. La
comparación entre la ortofoto y el modelo 3D para cada fecha no arroja grandes diferencias,
especialmente para la zona del Cerro de la Mesa, pero sí es destacable la aparición de
distorsiones que presenta la reconstrucción de 1945 fruto de la deficiencia radiométrica
señalada con anterioridad. Esto provoca que, a nivel técnico, la reconstrucción de 1956, más
constante y regular, sea la más válida a la hora de estudiar el paisaje global previo a la
construcción del embalse de Azután. Además, a la hora de utilizar los Modelos Digitales de
Superficies sí se puede considerar una divergencia reseñable entre ambos modelos en cuanto
a su precisión, que tiene consecuencias más o menos determinantes en el resultado de los
análisis. Por este motivo, es posible afirmar que la serie B es el modelo más adecuado para
nuestros objetivos, teniendo en cuenta las cualidades particulares de un medio de
información antiguo como es este, y con la posibilidad aún de comprobar los resultados en
campo y su corrección en postproceso.

El espectro de aplicaciones que se abre con la generación de estos resultados es amplio y
dependerá siempre de los objetivos que se marquen los investigadores. Este trabajo se ha
concebido para demostrar y analizar la capacidad que tienen los SIG en la recuperación de
un paisaje transformado que afecta al estudio arqueológico, por lo que se van a exponer
algunas consideraciones generales a partir de su aplicación en lugar del análisis específico
de alguna de ellas.

39

<!-- p. 40 -->

6.1.2. Análisis arqueológico de la observación de las ortofotos y el modelo 3D

Es posible constatar, desde el básico reconocimiento visual, cómo la restitución
fotogramétrica de un vuelo histórico se convierte en un medio de información privilegiado.
La combinación de las ortofotos y el modelo 3D nos ayudan a visualizar algunos de los
elementos más significativos que se desprenden de esta interpretación visual, que se realiza
en ArcGIS para las ortofotos y en ContextCapture Viewer para el modelo 3D. Aunque, como
hemos comentado anteriormente, hemos considerado la reconstrucción de 1956 como la más
adecuada tras el control de calidad, se puede recurrir a la reconstrucción más antigua en una
buena parte de su extensión, donde no se producen errores de magnitud que imposibilitan su
utilización como herramienta.

1945 1956

Figura 6.1. Aproximación al vado de Puente Pinos sobre las ortofotos generadas de las Series A y
B, que reflejan las diferencias de caudal del Tajo en dos momentos distintos del año: estiaje de
septiembre, en 1945, y gran caudal en abril, en 1956.

A nivel visual, en la reconstrucción 3D del entorno del Cerro de la Mesa no hay apenas
diferencias en lo que al relieve físico respecta dado el escaso periodo de tiempo transcurrido
y el contexto histórico “inmovilista” en el que nos encontramos. No obstante, es necesario
mencionar el apreciable cambio de caudal del río en ambos momentos, que refleja las épocas
de estiaje (septiembre de 1945) con las de mayor caudal (abril de 1956) (ver Figura 6.1). No
se trata de un asunto banal, pues en realidad constituye un punto fuerte de la interpretación
arqueológica del entorno. En este sentido, puede servirnos como reflejo de la viabilidad de
vados como el de Azután a lo largo del año, con sus fluctuaciones del nivel del agua, a pesar
de que ya desde época moderna se habría regulado parcialmente el caudal del Tajo con la
presencia de numeroso molinos, aceñas y batanes (Cerrillo, 2011: 153; Vela Santamaría,
2009). Al igual que se aprecia en la figura anterior, ambos modelos de 1956 y 1945 ilustran
a la perfección la morfología prácticamente original del Cerro de la Mesa apenas reconocible
hoy en día. No obstante, la plataforma elevada sobre la cual se asentó la población ha sufrido
la modificación más representativa del paisaje tras la construcción del embalse. El resultado
nos muestra una elevación de silueta trapezoidal claramente visible, con el escarpe oeste

40

<!-- p. 41 -->

muy pronunciado hacia el río en una clara posición de dominio sobre éste. La comparación
con la actualidad muestra el enmascaramiento de su situación preminente y la pérdida de su
extensión real, de la cual solo permanece conservado el tercio norte que hoy día se encuentra
vallado y protegido (ver Figura 6.2).

A B

C

D

E

Figura 6.2. Visualización de la pérdida de referencia visual del Cerro de la Mesa. En 1956 (ortofoto
y malla 3D), la plataforma sobre la que se asentaba el yacimiento presentaba un escarpe de más de
40 metros entre la ribera del río y el punto más alto del cerro (A-C). En la actualidad, los productos
del PNOA 2009 (D-E) ilustran claramente la alteración morfológica del cerro y la situación del
escarpe, sumergido en el embalse.

La configuración de la zona oeste, más próxima al río, está completamente alterada, debido
a los movimientos de tierra derivados de la construcción de la plataforma artificial edificada
para la subestación eléctrica, y la carretera de acceso a ella. La reconstrucción 3D hace
justicia al gran desnivel original entre la parte más alta del cerro en esta zona y el río (más
de 40 metros), cuyo escarpe se encuentra hoy en día parcialmente sumergido en el embalse,
como muestra la nube de puntos LiDAR del PNOA 2009. La mitad de la plataforma se
encuentra hoy día, asimismo, cubierta por la reforestación de pinos que se plantaron sobre

41

<!-- p. 42 -->

el relleno de tierra, ocultando la silueta que se aprecia desde el aire en las fotografías aéreas
de 1956 y 1945 sobre un cerro sin apenas vegetación, y dificultando a su vez la prospección
arqueológica como veremos después.

Zona aproximada de alteración por el Arroyo desaparecido en la misma zona
relleno de tierra y replantación en la (Modelo 1956)
vertiente norte (Modelo 1945)

A B

C

Modificación
por central
hidroeléctrica

Caminos antiguos de acceso al vado por Nudo principal de
la vertiente sur caminos, posible
entrada al
yacimiento

Figura 6.3. Análisis del paisaje antiguo del Cerro de la Mesa a partir de la interpretación de los
modelos tridimensionales de 1945 (A) y 1956 (B-C) en ContextCapture Viewer. Transformación del
entorno con la construcción de las infraestructuras asociadas a la construcción el embalse y la subida
de las aguas.

42

<!-- p. 43 -->

Junto al perímetro del cerro es posible rescatar más piezas del paisaje antiguo que tenían su
propio papel en la configuración del hábitat del asentamiento humano. Una gran virtud de la
restitución es la de poder reconstruir las características topográficas del área de captación de
recursos de un asentamiento, un concepto clave si se pretende contextualizar la
interpretación arqueológica. En la parte norte, el relleno de tierra y la posterior plantación
de pinos hicieron desaparecer un arroyo que se distingue claramente en los modelos antiguos
(ver Figura 6.3.A y B) al borde del cerro fortificado, aunque probablemente no fuera el único
en los alrededores.

Tampoco se puede descartar la existencia de algún tipo de prolongación del asentamiento en
la parte sur, pues como ya se ha comentado este sector está totalmente alterado por la
estación de bombeo y las carreteras que acceden a él. En la vertiente este, donde el escarpe
que baja del cerro es más leve, nos encontramos con las carreteras y vías modernas que
conectan las diferentes instalaciones del embalse. La importancia de este sector radica en
que, tal y como demuestran las reconstrucciones, parece constituir la vertiente por la cual
circulan los caminos que se dirigen hacia el vado, así como hacia una de las hipotéticas
entradas al poblado amurallado (ver Figura 6.3.C).

El curso fluvial es probablemente el elemento más determinante en el entorno del Cerro de
la Mesa, específicamente la confluencia de los ríos Tajo y Huso, y su vado sobre el cual se
sitúa el yacimiento arqueológico. El modelo de 1956 refleja un escenario que podría ser muy
parecido al que presentaba el lugar en época protohistórica. A orillas del escarpe que
flanquea el promontorio en su lado oeste, el río presenta un tramo de estrechamiento que
acerca sobremanera el espacio entre ambos bordes. Es en ese preciso lugar en el que se
documenta la existencia de puentes a lo largo de la historia, por lo que es de suponer que
cualquier edificación de este tipo habría ocupado esa posición idónea, como bien ha indicado
Cristina Charro (Charro Lobato, 2015: 131) (ver Figura 6.4.A).

A B

C

Figura 6.4. Análisis del vado de Puente Pinos a través de las ortofotos generadas. En verde, la isleta
central que facilitaría el paso, emergente sobre el agua en la ortofoto de 1956 (A) cuando el caudal
está alto, pero que se aprecia su dimensión real en 1945 con el caudal bajo (B), y que se encuentra
sumergida en la actualidad (C). En rojo, área en la que se encontraron los restos del puente antiguo
que cruzaba el río bajo el cerro (Charro Lobato, 2015).

43

<!-- p. 44 -->

Confirmada su existencia en época medieval (la documentación histórica informa de ruinas
en este lugar en informes de los siglos XVI y XIX) y seguramente romana gracias a los
hallazgos anteriores a la construcción del embalse (Jiménez de Gregorio, 1950: 111-112),
queda por conocer su situación durante la Edad del Hierro, período en el que se desarrolla
fundamentalmente la actividad del asentamiento del Cerro de la Mesa. El histórico vado se
prolongaría más allá del estrechamiento, extendiéndose aguas arriba donde el río se ensancha
y se produce la desembocadura del Huso. En ese punto se formaba una isleta central de
arenas y gravas que facilitaría el paso a pesar de su probable inestabilidad (Chapa y Pereira,
2006:122) y que es perfectamente distinguible en la ortofoto de 1956 y se intuye en la de
1945 (ver Figura 6.4.A y B). La subida del nivel de agua del embalse sumergió no solo la
isla sino el vado entero (ver Figura 6.4.C), por lo que es necesario recurrir a la reconstrucción
para reconstruir las características originales del cerro en su posición de dominio sobre el río
y su ruta de paso.

A pesar de que los objetivos del trabajo se enfocan principalmente sobre el propio cerro y el
entorno inmediato que lo circunda, las dimensiones de las reconstrucciones realizadas nos
permiten ampliar la vista fuera del área de modificación del embalse. En esta área de
influencia y en clara relación con el vado destaca la calzada romana que comunica los
municipios de Azután y Belvís de la Jara, constatada y estudiada arqueológicamente (Coello,
1889; Jiménez de Gregorio, 1950; Muñoz Villarreal y Ruiz Carmona, 1993). La vía, que
pertenece probablemente a la red de comunicaciones que conectaría las ciudades de Toletum
y Emerita Augusta, se descubre con claridad en el tramo que discurre tras cruzar el río Huso
en dirección a Aldeanueva de Barbarroya, manteniéndose el empedrado original, bloques de
granito pertenecientes al bordillo y los cercados de las piedras en los tramos en los que se
interrumpe el empedrado (Muñoz Villarreal y Ruiz Carmona, 1993). A la altura en la que la
calzada se acerca a la carretera CM-4014 se pierde el rastro, permaneciendo intermitente
hasta su llegada a las proximidades de Aldeanueva de Barbarroya, donde desaparece
fundiéndose en la pista de tierra.

Como es lógico, las ortofotos generadas de 1956 y 1945 nos ofrecen una visión de la silueta
de la calzada mucho más evidente que en las fotografías actuales, por lo que es posible
realizar una interpretación general apoyada por los modelos en 3D (ver Figura 6.5). La
posibilidad de visualizar la vía antigua es especialmente clara en la primera parte tras el cruce
del Huso, donde la calzada sube desde la ribera del río y el empedrado está más completo.
Se trata, además, de la zona más transformada en la actualidad para el tramo que estamos
observando, ya que la infraestructura moderna ha conllevado el asfaltado de la antigua
carretera local 44 que sustituía por el sur a la antigua calzada en su camino hacia Aldeanueva
de Barbarroya, junto a la construcción del puente sobre la desembocadura del Huso, donde
también ha desaparecido bajo las aguas el tramo de la vía que cruzaba el río por esta parte.

Más recientemente, las obras de remodelación y ampliación de la carretera comarcal CM4104 modifican aún más el terreno en esta primera parte del sector, con el movimiento de
tierras y alteración topográfica que ello implica. Todos estos factores consolidan la técnica
Structure from Motion como la alternativa más adecuada no solo para el seguimiento de la
ruta de la calzada sino también para poder realizar análisis de rutas óptimas o de visibilidad
mediante el modelo digital del terreno más cercano a su estatus antiguo. A pesar de una
cronología posterior con respecto al asentamiento del Cerro de la Mesa, no debe tomarse la
calzada como un elemento ajeno al propio yacimiento, si se considera la red de caminos
tradicional que probablemente se aprovechó para la construcción de la calzada, y sin obviar
las ramificaciones que se han planteado para esta vía principal y que por supuesto implicarían
el cruce del Tajo por el vado de Puente Pinos.

44

<!-- p. 45 -->

A

B

C

D

Figura 6.5. Análisis del recorrido de la calzada romana que comunica Belvis de la Jara y Azután
(Muñoz Villarreal y Ruiz Carmona, 1993) sobre la ortofoto de 1956 (A), y en la actualidad (B).
Debajo, ascenso de la calzada desde la ribera del río, donde se encuentra en mejores condiciones,
visualizado en 1956 (C) y 1945 (D).

45

<!-- p. 46 -->

6.1.3. Tratamiento del Modelo Digital de Superficies (MDS) en un SIG y análisis
arqueológico.

Es importante resaltar previamente que el MDS (Modelo Digital de Superficies) es el
producto necesariamente derivado de la restitución, ya que no deja de ser un modelo digital
donde se toman las elevaciones naturales y construidas en la superficie de la Tierra que se
sustraen a partir de las fotografías aéreas en el preciso momento en el que se toman. Este
factor lo hace diferenciarse del MDE (Modelo Digital de Elevaciones), un modelo de
elevación de tierra desnuda que representa la superficie de la Tierra y filtra los elementos
sobre la superficie (vegetación, edificios, etc.) que sí incluye el MDS. Por este motivo, el
último paso en el control de producción sería el de corregir anomalías derivadas del MDS,
como construcciones modernas o vegetación alta, para convertirlo en un MDE. Las
características de nuestro trabajo no hacen imprescindible este paso, pero es interesante
mencionar la posibilidad de una primera interpretación cultural en la valoración de los
elementos, como los caminos, que podían tener un peso relevante en el paisaje rural
tradicional.

La generación de un MDS supone contar con un ráster preciso sobre las características
topográficas del entorno del Cerro de la Mesa anterior a la construcción del embalse. La
disponibilidad de esta información constituye por sí misma un factor determinante para la
reconstrucción topográfica, pero, al mismo tiempo, su tratamiento permite la obtención de
manera rápida de otros productos derivados que son de gran utilidad en un estudio
arqueológico como el que se acomete en este trabajo.

El tratamiento de los Modelos de Superficie (MDS) se realiza en ArcGIS, donde en primer
lugar se procede a la combinación de los diferentes tiles o “baldosas” en los cuales se divide
el modelo durante su generación (Raster→ Raster Dataset → Mosaic to new Raster). El
MDS cubre una extensión considerable del terreno gracias a la altura y escala con la cual se
realizó el vuelo fotogramétrico que ha permitido la restitución, por lo que consigue abarcar
un gran espacio alrededor del yacimiento, muy importante si queremos abarcar un estudio
amplio del territorio (ver Figura 6.6). Sin embargo, para centrar el análisis en una zona
específica se deben acotar los límites en busca de una mayor precisión. En este caso, para
ejemplificar el potencial tratamiento nos centraremos en el cerro, estableciendo un perímetro
de 400 metros alrededor de él y extrayendo la información del recuadro (Spatial Analyst
Tools →Extraction →Extract by Mask). Las herramientas que nos proporciona el programa
SIG (al igual que en CAD) son muy útiles para crear nuevos productos derivados del MDS
(pendientes, orientaciones, sombreados, etc.) y representaciones realistas que explotan las
características topográficas del cerro en su estatus original. Por ejemplo, para generar una
visualización realista de la altimetría, de manera que refleja la posición prominente del cerro,
fundamentalmente en sus vertientes norte, sur y oeste, y su situación de dominio frente al río
(ver Figura 6.7).

46

<!-- p. 47 -->

Figura 6.6. Modelo Digital de Superficies generado mediante la restitución fotogramétrica SfM-MVS
sobre los fotogramas del Vuelo AMS (B) en torno al municipio de Alcolea de Tajo, tomadas en abril de
\1956. Clasificación con ayuda de Hillshade, y arriba a la derecha, detalle del área del Cerro de la
Mesa.

Figura 6.7. Simbolización del MDS en base a la altimetría del Cerro de la Mesa y su perímetro,
sobre la ortofoto generada en la restitución. A la derecha, clasificaciones tridimensionales
realizadas en ArcScene que reflejan la posición original de dominio del cerro respecto al río.

47

<!-- p. 48 -->

De igual manera se puede cuantificar y visualizar la pérdida de la posición del cerro como
referencia visual con relación al río y al propio vado, debido a la construcción del embalse
y las alteraciones derivadas que ya hemos comentado. En este sentido, la creación de un
perfil topográfico tanto en el MDS de 1956 como en el MDT actual del PNOA, con el cual
se ha trabajado anteriormente, desde la posición más alta del cerro hasta la ribera del río
refleja perfectamente esta modificación, aunque las características de ambos modelos sean
diferentes (ver Figura 6.8).

A

A C

B
B

Perfil topográfico de 1956

Perfil topográfico actual

X: Longitud del perfil (m)/ Y: Altitud (m)

Figura 6.8. Creación de perfiles topográficos para ilustrar la diferencia altimétrica entre la parte más
alta del Cerro de la Mesa y la ribera del río Tajo como reflejo de la predominancia visual del yacimiento.
La pérdida altimétrica en la actualidad (MDE PNOA 2009; B) respecto a 1956 (MDS logrado mediante
restitución, A) se expresa cuantitativamente en el gráfico (C).

Una línea que atraviesa la zona a estudiar y su interpolación (Interpolate Shape) con los
rásteres que contienen los datos nos permiten fácilmente realizar esta tarea en ArcGIS gracias
a las herramientas de 3D Analyst. Los resultados ilustran la pérdida de referencia, donde
antiguamente se superaban los 40 metros de diferencia entre la zona más alta del yacimiento
y la ribera del río, actualmente se queda alrededor de los 20-25 metros. Misma valoración
ofrece el mapa de pendientes (Slope), que representa los grandes desniveles originales del
cerro en el escarpe oeste en relación con el río, donde se aprecian las pendientes más fuertes
(ver Figura 6.9).

También, la disposición de los dos MDS nos posibilita comparar y obtener la diferencia de
superficies con la herramienta Raster Calculator (Spatial Analyst Tools→Map Algebra). Si
combinamos esta información con el MDE del LiDAR de 2009, el mapa resultante refleja la
diferencia de los valores de elevación (ver Figura 6.10), en la que se ha optado por establecer
una zona de incertidumbre de 1 metro derivado del RMSE, pero también al considerar la
comparación entre productos de distinta naturaleza (MDS y MDE) y las propias limitaciones

48

<!-- p. 49 -->

metodológicas. Así pues, tras descartar el MDS de 1945 por su inexactitud, el cálculo sobre
el MDS de 1956 refleja con claridad los principales aumentos de altitud alrededor del río,
tras la inundación provocada por la construcción del embalse, y en las zonas norte, debido
al relleno de grandes volúmenes de tierra para la replantación, y sur, con el emplazamiento
de la plataforma para la estación hidroeléctrica. Destaca, a su vez, como una gran parte del
promontorio original del cerro se ha visto afectado por una pérdida altimétrica producto de
las grandes alteraciones geomorfológicas sufridas en el entorno durante la época reciente.

Figura 6.9. Mapa de pendientes generado a partir del MDS de 1956 y visualizado sobre la ortofoto de 1956.

Sedimentación
(embalse)

RMSE

Erosión

Figura 6.10. Diferencia de superficies entre el MDE generado mediante LiDAR del PNOA 2009 y el MDS
generado a partir de los fotogramas de 1956. Los valores positivos expresan procesos de sedimentación,
representados en tonos azules por los procesos de erosión, en rojo.

49

<!-- p. 50 -->

6.2 LIDAR: Utilidad y complementación con los resultados del georradar (GPR)

6.2.1. Interpretación de las visualizaciones generadas con el programa RVT

Mediante el programa RVT se ha intentado sacar el máximo partido a la información que
los datos LIDAR de los que disponemos pueden aportar a la reconstrucción arqueológica del
Cerro de la Mesa. La utilización del programa no supone dificultad alguna, por lo que se han
aplicado todas las técnicas disponibles en su haber, entre las que se encuentran todas aquellas
que se mencionaban en la metodología. El producto de este proceso es un conjunto de
rásteres, o imágenes digitales, para cada una de las técnicas planteadas, que combinados
conforman una fuente de información única del potencial arqueológico en el terreno.

La virtud arqueológica de esta tecnología se basa directamente en la interpretación de estas
visualizaciones del terreno. Esta interpretación se lleva a cabo, al igual que el resto del
proceso, en software SIG como es ArcGIS, donde la confrontación y/o comparación de los
resultados se consigue superponiendo las distintas capas obtenidas en el programa RVT
junto a ortofotos actuales descargados del PNOA que nos muestran la visión real del cerro.
(ver Figura 6.11). Entre la variedad de productos que genera el programa RVT destacan las
técnicas principales a la hora de proceder a la interpretación.

El sombreado desde múltiples direcciones (MULTI-HS) ofrece un mapa de sombras (ver
Figura 6.11.C) del cerro en el cual se consigue anular el efecto por el cual se invisibilizan
los elementos que se encuentran en el mismo sentido de la iluminación. Con estas
características se observan de manera eficaz las siluetas del relieve tanto del propio cerro
como de la zona inmediatamente al norte de éste, donde se encuentra la mayor parte de la
repoblación de pinos, pero sin éxito alguno a la hora de localizar estructuras ocultas bajo
esta masa arbórea, a pesar de que sí reconoce de manera precisa las formas geométricas
asociadas a la infraestructura de la estación hidroeléctrica. Es interesante subrayar que la
“eliminación” de la vegetación que realiza el LiDAR permite constatar cómo se ha llevado
a cabo el relleno de tierra en la zona de la repoblación, pues ha desaparecido completamente
el desnivel que había en la plataforma original del cerro en su vertiente norte. La aplicación
de PCA (ver Figura 6.11.D), que maximiza los contrastes de sombra realizado sobre
múltiples direcciones, tampoco ofrece mucha más información que la que proporciona el
MULTI-HS, pues su eficacia depende en gran manera de las técnicas de sombreado como
esta.

Al pasar a interpretar técnicas complejas más específicas, los resultados son igualmente
escasos. El mapa de SLRM (ver Figura 6.11.E) incide sobre la microtopografía al eliminar
los elementos morfológicos a gran escala, pero esta técnica trabaja eficientemente sobre
entornos donde se pueden individualizar elementos arqueológicos como terrazas de cultivo,
túmulos funerarios o líneas de arado independientemente de su situación topográfica a gran
escala. Las cualidades del área que prospectamos no benefician la eficacia de esta técnica,
pues nos centramos en una zona de menor escala donde los contrastes topográficos son
pequeños debido a su transformación. Por último, el mapa generado por SVF (ver Figura
6.11.F) destaca al ofrecer los mejores resultados en cuanto a la visualización topográfica del
relieve, pero no ha podido ayudar a la detección de estructuras arqueológicas. El mapa de
SVF resalta en color oscuro las depresiones frente al claro de los terraplenes, y por lo que

50

<!-- p. 51 -->

refleja bien las variaciones de altura que afectan al paisaje del cerro, pero no logra detectar
fosos, trincheras o muros que pueden llegar a salir a luz con la aplicación de esta herramienta.

A B

C D

E F
±
Figura 6.11. Mapas generados en el programa RVT para la completa visualización de los datos
LiDAR en el entorno del Cerro de la Mesa. En la figura se representan las ortofotos de 2019 (A) y
1956 (B), por un lado, y los productos de las técnicas empleadas, por otro: MULTI-HS (C) PCA (D),
SLRM (E), y SVF (F).

51

<!-- p. 52 -->

6.2.2. Resultados del georradar e integración en la reconstrucción topográfica

Afortunadamente, la aplicación de otro método de prospección, en este caso proveniente de
la geofísica, como es el georradar, sí ha ofrecido importantes resultados en la interpretación
arqueológica de la trama urbanística del yacimiento. Al contrario que las técnicas descritas
anteriormente en este trabajo, se trata de una tecnología muy contrastada y de uso
generalizado en la investigación arqueológica. Sin extenderse en su descripción, el georradar
es una herramienta asociada a la prospección geofísica, que consta de un radar de subsuelo
(GPR, por sus siglas en inglés, Ground Penetrating Radar) que emplea ondas
electromagnéticas de alta frecuencia transmitidas bajo la superficie. El efecto de la presencia
de discontinuidades en el subsuelo (muros, pozos, etc.) es reflejado y registrado, por lo que
se convierte en el método de más elevada resolución para la búsqueda y el registro de
estructuras arqueológicas enterradas (Conyers, 2004; Dietz et al., 2011). La inclusión de los
resultados del georradar en nuestro trabajo parte de la idea, ya expuesta anteriormente, de
utilizarse en la comparación con el LiDAR como técnicas no invasivas de prospección
visual, pues, aunque no se puede considerar el GPR como una tecnología específica del
ámbito de las TIG, debe combinarse necesariamente con éstas para su análisis. Además, nos
ofrece la posibilidad de difundir sus interesantes resultados, así como de integrar y
contextualizar la trama urbana que se refleja en la foto-reconstrucción 3D que hemos
realizado en este proyecto.

La prospección geofísica fue llevada a cabo en el yacimiento del Cerro de la Mesa por parte
del CAI (Centro de Asistencia a la Investigación) de Arqueometría y Análisis Arqueológico
de la Universidad Complutense de Madrid, cuyos resultados ha cedido para la realización de
este trabajo, con Javier Vallés Iriso como responsable técnico y Jorge Matesanz Vicente de
apoyo topográfico, todo ello con la colaboración de Ana Cabrera Díaz (Pereira Sieso et al.,
2020). Para la prospección, que se integra en una aplicación combinada de técnicas no
destructivas, se aplicó la metodología de georradar multicanal 3D equipado con una antena
de 600 MHz y con el apoyo para la georreferenciación topográfica de un GPS diferencial
TopCon GR5. Con estas herramientas se consiguió cubrir una superficie de 2,1 ha (16000
m²) abarcando gran parte del yacimiento arqueológico conservado hoy en día.

El procesado de los datos del georradar siempre culmina con la generación de una capa de
información geoespacial que sitúa correctamente los resultados obtenidos en su contexto,
para facilitar la interpretación, una labor que se realiza, tanto en SIG como en CAD. Al
introducir esta información en ArcGIS, podemos observar el entramado urbano que ha
sacado a la luz el GPR, en los cuales se han diferenciado las estructuras ya excavadas, las
estructuras identificadas por el georradar y la muralla (ver Figura 6.12). Al margen de la
interpretación arqueológica, que escapa a los objetivos de este trabajo y que está muy bien
representada en el artículo que han realizado los autores de esta aplicación no invasiva en el
Cerro de la Mesa (Pereira Sieso et al., 2020), es interesante apreciar cómo el entramado
urbano se ajusta perfectamente al relieve topográfico en la zona protegida del yacimiento
que se ha salvado de las grandes alteraciones morfológicas que afectan al resto del cerro, tal
y como se aprecia cuando superponemos la capa del georradar al MDT del PNOA.

52

<!-- p. 53 -->

A B

C

Figura 6.12. Presentación de los resultados obtenidos mediante el uso de georradar en el yacimiento
del Cerro de la Mesa, donde se visualiza el entramado urbanístico expuesto por el GPR junto a la
estructura arqueológica ya excavada y los restos de la muralla (A). Además, localización de los
restos en la ortofoto del PNOA de 2019 (B) y en el MDT05 del PNOA, apoyado por la técnica de
Hillshade (C). Información de GPR procedente de la prospección geofísica dirigida por J. Vallés
(Pereira Sieso et al., 2020), y facilitada por el CAI Arqueometría UCM.

Además, la superposición de capas facilita el cotejo de los datos con el resto de información
obtenida en ambas reconstrucciones. En primer lugar, la comparación con los resultados del
LiDAR, en los cuales es apenas perceptible la sucesión de elementos detectados con el GPR
(ver Figura 6.13), pues únicamente se identifican las estructuras ya excavadas en el
yacimiento. En segundo lugar, la integración de la trama urbana en la ortofoto de 1956,
donde sí se aprecia la plataforma completa del cerro (ver Figura 6.14). Esta última
visualización tiene gran impacto para la interpretación, pues sitúa el yacimiento conservado
actual en su posición original, cuando el cerro ocupaba toda su extensión, a la vez que
muestra con claridad las dimensiones de la pérdida arqueológica derivada de la construcción
del embalse. Para potenciar la representación se utilizan las herramientas que disponemos
en el entorno de visualización 3D de ArcGIS como es ArcScene, donde se ha decidido elevar
la ortofoto generada con los valores del MDS, y aplicar la extrusión para tener una visión
más completa de los resultados del georradar, reflejando de este modo, de manera
simplificada, los alzados de las estructuras que compondrían el asentamiento (ver Figura
6.15).

53

<!-- p. 54 -->

A B

Figura 6.13. Comparación de los resultados del GPR (A) sobre el MDT05 del PNOA, con la técnica
SVF para el LiDAR en el cerro (B), donde no ha sido posible visualizar el conjunto de estructuras
soterradas. Información de GPR procedente de la prospección geofísica dirigida por J. Vallés
(Pereira Sieso et al., 2020), y facilitada por el CAI Arqueometría UCM.

Figura 6.14. Integración de la trama urbana descubierta por el georradar en la morfología original
del Cerro de la Mesa que se aprecia en la ortofoto generada para la restitución fotogramétrica de
\1956. Información de GPR procedente de la prospección geofísica dirigida por J. Vallés (Pereira
Sieso et al., 2020), y facilitada por el CAI Arqueometría UCM.

54

<!-- p. 55 -->

1

2

3

Figura 6.15. Perspectiva general de los resultados del georradar, con la aplicación de herramientas
de visualización en ArcScene, combinados con la ortofoto y el MDS de 1956. Información de GPR
procedente de la prospección geofísica dirigida por J. Vallés (Pereira Sieso et al., 2020), y facilitada
por el CAI Arqueometría UCM.

55

<!-- p. 56 -->

\7. DISCUSIÓN

El resultado directo de la aplicación de estas técnicas no invasivas es la obtención de un
conjunto de productos cartográficos que, con mayor o menos grado de detalle, se han
expuesto en este trabajo. La exploración de estas técnicas novedosas y métodos asociados,
contrastados ya en el ámbito de las TIG, ha supuesto grandes beneficios tanto por la
incorporación de información única en la reconstrucción topográfica y arqueológica del
Cerro de la Mesa como por la constatación de algunas limitaciones que, lejos de obstaculizar,
ayudan a mejorar la implantación de estas herramientas en Arqueología.

La reconstrucción paleotopográfica del Cerro de la Mesa es una vía de estudio que se ha
podido abordar en la primera aplicación gracias a la fotogrametría digital, y en especial
mediante la técnica SfM-MVS. La Foto-Reconstrucción 3D (FR-3D) de su situación en 1945
y 1956 ratifica la capacidad de esta técnica para generar un modelo tridimensional de
componente realista en base a fotogramas de vuelos históricos en el que destaca la rapidez y
automatización de un proceso costoso y, sobre todo, la disponibilidad de herramientas como
la ortofoto y el MDS, de gran precisión. Es este último factor uno de los principales puntos
fuertes que se extrae de la metodología expuesta, a pesar de considerar necesario un paso
posterior para la comprobación de los resultados en postproceso. La precisión indicada de
los modelos, concretamente el de 1956 que ha dado mejores resultados, presenta errores
(RMSE) planimétricos y altimétricos menores a 1 metro, perfectamente asumibles para
aplicaciones como las que se han detallado en este trabajo, y que son comparables con los
datos obtenidos en otras aplicaciones de fotogrametría digital sobre fotografías aéreas
históricas, ya sea por medio de la propia Serie B de 1956 (Cerrillo, 2011; Pérez Álvarez et
al., 2013; Charro, 2015) o en vuelos antiguos de otros países (Mölg y Bolch, 2017; Feurer y
Vinatier, 2018).

La disponibilidad de un MDS de alta resolución abre un abanico de posibilidades que
incluyen análisis cuantitativos mediante mapas de coste, orientaciones, pendientes o de
intervisibilidad muy útiles en Arqueología para los estudios de visibilidad y movilidad, que
pueden aportar valiosísima información en una ruta de paso como es el vado del Cerro de la
Mesa. Dados los objetivos de este trabajo, nos remitimos únicamente a subrayar la utilidad
que podrían aportar estos estudios a la investigación arqueológica del Cerro de la Mesa,
exponiendo las herramientas necesarias para llevarlas a cabo. Además, es justo citar el
reciente trabajo de Cristina Charro, que aporta también las bondades de la restitución
fotogramétrica a partir de vuelos históricos para generar el modelo digital del terreno del
Cerro de la Mesa y ejemplifica el valor que hemos mencionado realizando un análisis
comparativo con mayor grado de detalle para medir las variaciones topográficas registradas
en el entorno próximo del Cerro con la construcción del embalse (Charro, 2015: 129-139).

En este aspecto, la potencialidad de sus resultados no exime a esta aplicación de presentar
ciertas dificultades, debido a la presencia de distorsiones (ver Figura 7.1), la altura del vuelo
que dificulta el reconocimiento de PC comunes en tres fotogramas donde la franja de solape
es pequeña, y la disminución de precisión topográfica a pequeña escala, entre los más
importantes. Estos factores provocan evidentemente ciertas limitaciones que condicionan los
resultados obtenidos, especialmente para la restitución de 1945 en la cual el MDS generado
no cumple con los requisitos de precisión necesarios para validar cualquier análisis
cuantitativo. Se trata de un error de magnitud que no ocurre, por el contrario, en el modelo
de 1956, donde se han obtenido, al menos metodológicamente, resultados muy satisfactorios

56

<!-- p. 57 -->

que clarifican la comparativa entre ambos medios de información como uno de los objetivos
que se planteaban para este trabajo.

A B

C

Figura 7.1: Distorsiones producidas por las limitaciones de los fotograma históricos en la
generación de los MDS: Numerosas en el caso de la reconstrucción de 1945 (A-B), y que invalidan
el modelo, pero también en la de 1956, que afectan fundamentalmente a la zona noroeste del vado
de Azután (C).

Ante todo, la mayor parte de estas dificultadas se encuentran condicionadas por las propias
características del medio utilizado por encima de las capacidades de la metodología, que ya
ha demostrado precisión centimétrica en el ámbito de los estudios geomorfológicos
utilizando medios actuales de bajo coste (Tanarro y Gómez, 2014; Rodríguez Moreno,
2016), como también, en relación con la Arqueología, para el propio registro 3D de la
excavación (De Reu et al., 2014), la documentación de grabados rupestres (Maximiliano y
Barcia, 2017) o de edificios históricos (Medina, 2014), entre una gran variedad de
aplicaciones. No en vano, la habilidad de esta herramienta para trabajar con fotografía aérea
histórica de baja calidad se convierte precisamente en su mayor virtud para nuestros
intereses, a pesar de que la precisión dependerá siempre de la calidad de los fotogramas, tal
y como se ha visto reflejada en la comparación de las dos reconstrucciones. En este sentido,
no hay duda de que este tipo de aplicación va a evolucionar eficazmente en base a las
necesidades de campos de nuestra disciplina como la geoarqueología, la conservación del
patrimonio arqueológico y la prospección del terreno (Gómez, 2012). Así pues, la obtención

57

<!-- p. 58 -->

de grandes resultados en la combinación de fotogrametría digital y fotografía aérea histórica
amplía las posibilidades de la investigación como refleja, para la arqueología española, la
capacidad de utilizar una información única, procedente de los vuelos americanos de 194546 y 1956-57, tan fundamentales en el estudio de la evolución del paisaje de España en el
siglo XX.

El LiDAR es la otra herramienta utilizada examinada en este trabajo para su aplicación en
la reconstrucción arqueológica del Cerro de la Mesa. Al respecto, ha demostrado su eficacia
como medio topográfico y en la generación de imágenes de representación del relieve, a
partir de distintos algoritmos y escalas, interesantes para la interpretación. Sin embargo, es
necesario reconocer que el análisis visual no ha proporcionado los resultados deseados en la
detección de estructuras arqueológicas ocultas, aún consideradas las limitaciones existentes.
La implantación del LiDAR en esta aplicación pretendía examinar su capacidad de actuación
en la propia área del cerro actual pero especialmente en su entorno más inmediato. Esto es,
se consideraba su utilidad para la prospección de la zona protegida y vallada del Cerro de la
Mesa, de modo que se pudiera comparar con el georradar, que sí se pudo pasar en esa zona
y ha proporcionado muy buenos resultados.

Sin embargo, el objetivo fundamental del LiDAR en este trabajo era el de aportar
información en el resto de los sectores del yacimiento arqueológico y zonas colindantes en
los cuales la vegetación no admite la utilización del GPR, y donde el LiDAR encuentra su
mayor virtud en la detección e identificación de evidencias arqueológicas, tanto en forma de
estructuras o muros como en fosos, trincheras, etc. Esta prospección es muy interesante en
las zonas arboladas de la vertiente norte y, sobre todo, oeste, de la que gracias a la
reconstrucción topográfica conocemos sus características morfológicas antiguas que
incluían la prolongación del cerro.

Ya se ha mencionado anteriormente que existían limitaciones previas que podían dificultar
la capacidad del LiDAR para reflejar alteraciones arqueológicas en el terreno. La más
evidente, fuera del ámbito de estudio específico del Cerro de la Mesa, es que el LiDAR no
supone la herramienta definitiva, como a veces se presenta, para hacer frente a problemáticas
de la investigación desde la perspectiva de la Arqueología del Paisaje, sino que se trata de
una vía auxiliar para el estudio y análisis del paisaje arqueológico desde la topografía, con
sus correspondientes limitaciones (Costa-García y Fonte, 2017). Una de las más importantes
es su naturaleza temporal específica, ya que registra las condiciones del terreno en un
momento dado, en el cual ya se han podido desencadenar alteraciones geomorfológicas sean
de carácter antrópico o natural. Este es el caso que afecta a nuestro estudio en el Cerro de la
Mesa. En el contexto actual, en el cual se realiza la toma de los datos LiDAR, la
transformación es inmensa: el relleno de toneladas de tierra en la vertiente norte y este, donde
se encuentra la reforestación de pinos, oculta cualquier anomalía que pueda llegarse a
considerar indicio arqueológico; al sur, el paisaje es irreconocible con la construcción de la
plataforma y la estación hidroeléctrica, por lo que el LiDAR difícilmente puede aportar
información válida.

La segunda limitación, si bien menos relevante, es la calidad del medio de información. A
pesar de que ya ha sido demostrada la utilidad del LIDAR del PNOA para el estudio
arqueológico (Monterroso-Checa, 2017; Berrocal-Rangel et al., 2017; Cerrillo, 2017), no es
irrelevante admitir que podrían mejorar las prestaciones del LiDAR incorporando la
tecnología que ya se usa para la segunda cobertura y que permite doblar la densidad de
puntos obtenidos, y por tanto, la precisión, permaneciendo en un medio abierto y gratuito
como es el PNOA al margen de medios mucho más costosos. La escasa respuesta mostrada
aquí no invalida la aplicación del LiDAR para la investigación arqueológica del Cerro de la

58

<!-- p. 59 -->

Mesa, cuya aportación es realmente valiosa en el TFM. Por el contrario, la finalidad de este
trabajo reside en mostrar metodologías, aplicaciones y utilidades de las TIG en la
arqueología no invasiva por encima de conseguir resultados definitorios en la investigación
del Cerro, en el cual, además, se anima a solventar estas limitaciones descritas con la mejora
de los medios técnicos de adquisición de las nubes de puntos LiDAR.

Al margen de las dos herramientas aplicadas, la inclusión de los productos cartográficos
generados a partir del georradar cumple una función específica para la reconstrucción
arqueológica, en la que se compara a su vez con el LiDAR, pero, sobre todo, global, en base
a los objetivos del trabajo. Con relación a la primera, el GPR proporciona una “fotografía”
muy cercana a la realidad urbanística del antiguo asentamiento, presentando unos resultados
que necesitan ser debidamente interpretados por el equipo arqueológico del yacimiento. Sin
embargo, es más importante para este trabajo constatar como su utilización permite la
combinación de todas las técnicas mostradas cuando se superpone con los productos
cartográficos generados para la reconstrucción topográfica, donde también se han aplicado
la fotogrametría digital en base a la técnica SfM-MVS y el LiDAR.

En definitiva, es esta capacidad de superposición e integración de la información geoespacial
el principal aporte de las TIG a la interpretación arqueológica. Al abordar este tema, siempre
se deben considerar los condicionantes que incluyen estas herramientas, y que incluso en un
estudio más dirigido al análisis metodológico como este, se proyectan sobre el discurso que
se ofrece (Mínguez García y Capdevilla Montes, 2016). En este sentido, ya se ha señalado
cómo la temporalidad y la calidad de los datos han influenciado enormemente la obtención
de resultados adecuados, y, en consecuencia, la interpretación. Sin embargo, no podemos
obviar tampoco el componente relativo que se impregna al considerar elementos asociados
a las decisiones del propio investigador para seleccionar uno u otro parámetro, una
determinada área de estudio en el que se fijan límites preestablecidos en el paisaje (Orejas,
\1991) o el propio punto de partida desde el presente, del cual se reflejan las ideas
preconcebidas (Canosa, 2015). La discusión de estos condicionantes forma parte de un
debate mucho más amplio que en el estudio de las sociedades del pasado se aborda desde la
Arqueología del Paisaje. En un marco teórico tan complejo, remitiéndonos a los
planteamientos de un investigador prolífico en este ámbito como es Marcos Llobera, se debe
considerar el uso de estas herramientas como parte de un marco analítico de procesos,
conceptos, etc., que parte de un espacio de trabajo en el cual el paisaje se debe representar
tal y como es percibido por el ser humano (Llobera, 1996).

\8. CONCLUSIONES

El potencial de las TIG en la investigación arqueológica es una evidencia demostrada ya
tiempo atrás. No obstante, la aplicación de nuevas técnicas y metodologías, como se ha
expuesto en este trabajo, no hace sino reforzar la capacidad de estas herramientas para
explorar límites a los cuales la Arqueología puede llegar a aproximarse en el estudio del
paisaje antiguo. En este contexto se ha enmarcado la realización de este proyecto, con el
doble objetivo de arrojar luz tanto en la implantación de técnicas novedosas para la
investigación arqueológica no invasiva y de bajo coste, como en el avance particular del
estudio de un yacimiento como es el Cerro de la Mesa.

59

<!-- p. 60 -->

Los resultados obtenidos mantienen la línea argumentativa que destaca la importancia de las
TIG en nuestra disciplina. Fundamentalmente, porque estas técnicas se han revelado
imprescindibles en un entorno que ha perdido las características morfológicas primigenias
sobre las cuales debe enfocarse obligatoriamente la interpretación arqueológica. En esta
aproximación, es imprescindible partir de una reconstrucción topográfica que ha sido posible
reproducir mediante la técnica de Foto-Reconstrucción 3D (FR-3D), integrada en una
tecnología SfM-MVS que consigue aunar la precisión y gran resolución de las técnicas
fotogramétricas con la utilización de un medio de información, la fotografía histórica, que
posibilita la recreación del paisaje antiguo. A su vez, porque la disponibilidad de una base
topográfica original permite contextualizar espacialmente cualquier interpretación
arqueológica posterior, ya sea basada sobre información recogida por vías convencionales
como a partir de la utilización de tecnologías recientes integradas en las TIG como son los
SIG o el LiDAR, cuyas capacidades se han mostrado en este trabajo. Por este motivo, la
obtención de resultados poco determinantes durante la aplicación de la tecnología LiDAR
en nuestro caso no modifica el discurso en el cual se defienden y exponen las virtudes de
esta herramienta para la reconstrucción arqueológica, pues más allá de este planteamiento,
la pretensión de este trabajo es la de presentar metodologías que aprovechen las capacidades
del LiDAR como medio de prospección (a la vez que topográfico) en Arqueología, en
consideración, a su vez, de sus limitaciones.

La implementación de estas técnicas aporta conclusiones desde otra perspectiva. No cabe
duda de que, tal y como se pretendía exhibir, estas herramientas juegan un papel fundamental
en la práctica de la Arqueología no invasiva. En este sentido, se revelan no solo como medios
de investigación que implican la nula intervención material sobre el Patrimonio
Arqueológico, sino que, además, se convierten en métodos de obtención de información
única para el estudio arqueológico del yacimiento en general. Por este motivo, es evidente
que la Arqueología debe seguir sirviéndose de la incorporación de nuevas tecnologías que
amplíen el conjunto de técnicas no invasivas (donde ya llevan años implantados medios
como el GPR, tomografía eléctrica, análisis de imágenes multiespectrales e hiperespectrales,
térmicas…) sin olvidar que el ámbito de las TIG es un campo prolífico para ello. En
definitiva, la apuesta por una Arqueología Preventiva necesita obligatoriamente seguir la
estela de la innovación tecnológica que facilita el registro, conservación y difusión del
Patrimonio Arqueológico frente al riesgo de destrucción que, hoy en día y a pesar de los
esfuerzos de concienciación y protección legal del mismo, continúa muy presente.

Por último, no pueden dejar de considerarse las vías futuras de investigación que se abren
tras la realización de este trabajo. Fundamentalmente, en torno al propio estudio del Cerro
de la Mesa, sobre el cual se ha pretendido proporcionar información en la reconstrucción
topográfica y arqueológica del yacimiento. La metodología propuesta se plantea así con la
virtud de ser ampliada y, sobre todo, perfeccionada, con el empleo de medios más precisos
que se puedan disponer o se desarrollen en el futuro, especialmente a la hora de aplicar la
tecnología LiDAR, aunque esto pudiera implicar un factor de coste que se ha pretendido
evitar en el trabajo. A mayor escala, este proyecto presenta una vocación clara por facilitar
la aplicación de metodologías de trabajo sobre yacimientos arqueológicos con características
semejantes al Cerro de la Mesa, donde las TIG son esenciales en la recuperación del paisaje
perdido.

60

<!-- p. 61 -->

\9. BIBLIOGRAFÍA

ALMAGRO GORBEA, M. (2008): “Celtas y Vettones”. Zona Arqueológica, nº12, pp. 44-61.

ÁLVAREZ GONZÁLEZ, Y. (1993): “Arqueología del paisaje: modelos de ocupación y
explotación de los castros del Valle de Noceda (León)”. Complutum, Vol.4, pp. 265-
\278.

ÁLVAREZ SANCHÍS, J. (1997): Los vettones: Arqueología de un pueblo protohistórico. Tesis
Doctoral de la Universidad Complutense de Madrid.

\- (2003): Los señores del ganado. Arqueología de los pueblos pre- rromanos en
el occidente de Iberia. Akal, Madrid.

AMORES, F., GARCÍA, L., HURTADO, V. y RODRÍGUEZ-BOBADA, M. (1999):
“Geographic Information Systems and Archaeological Resource Management in
Andalusia (Spain)”. En BARCELÓ, J.A, BRIZ, I. y VILA, A. (Eds.): New
Techniques for Old Times, Computer Applications and Quantitative Methods in
Archaeology. Proceedings of the 26th Conference, Barcelona, Marzo de 1998 (BAR
International Series 757). Archaeopress, Oxford, pp. 351-358.

ANSCHUETZ, K., WILSHUSEN, R. y SCHEICK, C. (2001): “An Archæology of Landscapes:
Perspectives and Directions”. Journal of Archæological Research, Vol. 9, nº 2, pp.
152-197.

AST 6 OF 1372nd MAPPING & CHARTING SQUADRON (1997): “Final Report of Field
Operations, Project 54-AM-78. The Photomapper, Portada. Recurso electrónico
[Consulta en 12-10-2020], recuperado de:
http://www.1370th.org/ASTs/ast6ms/ast6ms.htm.

BAENA, J. BLASCO, X. y QUESADA, F. (Eds.) (1997): Los S.I.G. y el análisis espacial en
Arqueología. Universidad Autónoma de Madrid, Madrid.

BENITO, G., SOPEÑA, A., SÁNCHEZ-MOYA, Y., MACHADO, Mª. J. y PÉREZ-
GONZÁLEZ, A. (2003): “Palaeoflood record of the Tagus River (Central Spain)
during the Late Pleistocene and Holocene”. Quaternary Science Reviews, Vol. 22,
pp. 1737–1756.

BENNETT, R., WELHAM, K., HILL, R.A. y FORD, A. (2012): “A Comparison of Visualization
Techniques for Models Created from Airborne Laser Scanned Data”.
Archaeological Prospection, Vol.19, pp. 41–48.

BERROCAL-RANGEL, L., PANIEGO DÍAZ, P., RUANO, L, MANGLANO VALCÁRCEL,
G.R. (2017): “Aplicaciones LiDAR a la topografía arqueológica: El Castro de Irueña
(Fuenteguinaldo, Salamanca)”. Cuadernos de Prehistoria y Arqueología, nº 43, pp.
195-215.

BEWLEY, R. H., CRUTCHLEY, S. P. y SHELL, C. A. (2005): “New light on an ancient
landscape: LiDAR survey in the Stonehenge World Heritage site. Antiquity, Vol. 79,
pp. 636-647.

61

<!-- p. 62 -->

BLÁZQUEZ JIMÉNEZ, A. y BLÁZQUEZ y DELGADO AGUILERA, A. (1919-1920): Vías
romanas de Carrión a Astorga y de Mérida a Toledo. Excavaciones en Lancia.
Memoria de los resultados obtenidos en los viajes y excavaciones practicadas en
1919 y 1920. Memorias de la Junta Superior de Excavaciones 29. Ministerio de
Educación y Cultura. Madrid.

BONNEVAL, H. (1972): Photogrammétrie Générale. Ed. Eyrolles, Paris.

BREWER, J.L., CARR, C., DUNNING, N.P., WALKER, D.S., ANAYA HERNÁNDEZ, A.,
PEURAMAKI-BROWN, M. y REESE-TAYLOR, K. (2017): “Employing airborne
lidar and archaeological testing to determine the role of small depressions in water
management at the ancient Maya site of Yaxnohcah, Campeche, Mexico”. Journal
of Archaeological Science: Reports, Vol. 13, pp. 291-302.

BUCCI, G. (2018): “Remote Sensing and Geo-Archaeological Data: Inland Water Studies for the
Conservation of Underwater Cultural Heritage in the Ferrara District, Italy”. Remote
Sensing, Vol. 10(3), 380.

CABRERA DÍEZ, A. y MORENO-GARCÍA, M. (2014): “Prácticas de sacrificio en el Cerro de
la Mesa (Alcolea de Tajo, Toledo): El depósito ritual de la Casa 1”. Zephyrus:
Revista de prehistoria y arqueología, nº 73, pp. 133-147.

CANOSA BETÉS, J. (2015): “La población medieval de Kabbāl (Capilla,Badajoz): estudio
histórico-arqueológico de su territorio y la red defensiva andalusí a partir de
Tecnologías de Información Geográfica”. Trabajo de Fin de Máster de la
Universidad Complutense de Madrid.

CARRERO-PAZOS, M. (2018): “Modelando dinámicas de movilidad y visibilidad en los
paisajes megalíticos gallegos. El caso del Monte de Santa Mariña y su entorno
(Comarca de Sarria, Lugo)”. Trabajos de Prehistoria, Vol. 75, nº 2, pp. 287-306.

CARRERO-PAZOS, M., VILAS ESTÉVEZ, B., ROMANÍ FARIÑA, E. y RODRÍGUEZ
CASAL, A.A. (2014): “La necrópolis del Monte de Santa Mariña revisitada:
aportaciones del LIDAR aéreo para la cartografía megalítica de Galicia”. Gallaecia:
revista de arqueoloxía e antigüidade, nº 33, pp. 39-57.

CASTILLO MENA, A. (2010): “Archaeological Heritage Management in the World Heritage: A
Preventive Archaeology Proposal” en JANSSON, B.G. (Ed.): The Significance of
World Heritage: Origins, Management, Consequences. The Future of the World
Heritage Convention in a Nordic Perspective. Universidad de Dalarna, pp. 179-195.

CERRILLO CUENCA, E. (2011): “Recorriendo un territorio desaparecido: restitución
fotogramétrica y análisis del paisaje de la necrópolis prehistórica del vado de
Alconétar”. En MAYORAL HERRERA, V. y CELESTINO PÉREZ, S. (eds.)
Tecnologías de Información Geográfica y análisis arqueológico del territorio,
Anejos de AEspA, LIX, pp.145–159. Actas del V Simposio Internacional de
Arqueología de Mérida. Mérida: Instituto de Arqueología de Mérida, CSIC.

\- (2017): “An approach to the automatic surveying of prehistoric barrows
through LiDAR”. Quaternary International, Vol. 435, Parte B, pp. 135-145.

CHAPA BRUNET, T. y PEREIRA SIESO, J. (2006): “Un Vado Perdido: El Cerro de la Mesa
(Alcolea del Tajo, Toledo)”. Zona Arqueológica, nº7, Vol.2, pp. 121-132.

62

<!-- p. 63 -->

CHAPA BRUNET, T., PEREIRA SIESO, J., CABRERA DÍEZ, A., CHARRO LOBATO, C. y
MORENO GARCÍA, M. (2013): “Una fosa-vertedero de época vettona en el Cerro
de la Mesa (Alcolea de Tajo, Toledo)”. Trabajos de Prehistoria, Vol.70, nº 1, pp.
140-165.

CHAPA BRUNET, T., PEREIRA SIESO, J., MADRIGAL BELINCHÓN, A., PERLINES
BENITO, M.ª R., FERNÁNDEZ DEL CERRO, J.; DE ARCOS LAMARCA, L. y
CHARRO LOBATO, C. (2007): “El asentamiento protohistórico del Cerro de la
Mesa (Alcolea de Tajo, Toledo)”. En MILLÁN, J. M. y RODRÍGUEZ RUZA, C.
(eds.): Arqueología de Castilla-La Mancha. I Jornadas (Cuenca 2005). Cuenca:
UCL-Junta de Comunidades de CLM, pp. 797-809.

CHARQUERO BALLESTER, A. Mª. (2016): “Práctica y usos de la fotogrametría digital en
Arqueología”, DAMA. Documentos de Arqueología y Patrimonio Histórico, nº1, pp.
139-157.

CHARRO LOBATO, Mª C. (2015): “Historical aerial photographs to recover a lost landscape
using digital photogrammetry: a case study of the Iron Age site of Cerro de la Mesa
(Alcolea de Tajo, Toledo, central Spain)”. En COWLEY, D., IVANISEVIC, V.,
VELJANOVSKI, T., KIARSZYS, G. y BUGARSKI, I. (eds): Recovering Lost
Landscapes. Instituto de Arqueología de Belgrado, Monographs Vol. 58, pp. 129-
\139.

CHARRO LOBATO, C. y CABRERA DÍEZ, A. (2011): “El yacimiento arqueológico del Cerro
de la Mesa y su entorno (Alcolea de Tajo, Toledo)”. En LÓPEZ GARCÍA, J. P.;
HERNÁNDEZ SÁNCHEZ, D. y GARCÍA SÁNCHEZ, J. (eds.): Los vínculos entre
el hábitat y el paisaje. (Actas I Congreso de Arqueología de Chamartín (Ávila),
2010). Madrid: La Ergástula, pp. 209-218.

CHARRO LOBATO, C., CHAPA BRUNET, T. y PEREIRA SIESO, J. (2009): “Intervenciones
arqueológicas en el Cerro de la Mesa (Alcolea de Tajo, Toledo). Campañas 2005-
2007” En SANABRIA MARCOS, P.J. (ed.): Los pueblos prerromanos en la actual
demarcación Beira Baixa – Alto Alentejo – Cáceres. Memorias, nº9, Publicaciones
del Museo de Cáceres, Cáceres, pp. 131-139.

CHASE, A.F., CHASE, D.Z., AWE, J.J., WEISHAMPEL, J.F., IANNONE, G., MOYES, H.,
YAEGER, J., BROWN, M.K., SHRESTHA, R.L., CARTER, W.E., y
FERNÁNDEZ DÍAZ, J. (2014): “Ancient Maya regional settlement and inter-site
analysis: the 2013 west-central Belize LiDAR survey”. Remote Sensing, 6(9), pp.
8671–8695.

CHEVALLIER, R. (1976): “Le paysage palimpseste de l'histoire: pour une archéologie du
paysage”. Mélanges de la Casa de Velázquez, nº 12, pp. 503-510.

CHUVIECO SALINERO, E. (1996): Fundamentos de la Teledetección Espacial. Ed. Rialp,
Madrid.

CLARKE, D.L. (1977): Spatial Archaeology. Boston Academic Press.

COELLO, F. (1889): "Las vías romanas entre Toledo y Mérida". Boletín de la Real Academia de
la Historia, tomo XV, Madrid.

CONNOLLY, J. y LAKE, M. (2009): Sistemas de Información geográfica aplicados a la
Arqueología. Bellaterra, Barcelona.

63

<!-- p. 64 -->

CONYERS, L. B. (2004): Ground Penetrating Radar for Archaeology, Alta Mira Press, Walnut
Creek, (CA, USA).

CORDERO RUIZ, T., CERRILLO CUENCA, E. y PEREIRA, C. (2017): “Detección de un
nuevo campamento romano en las inmediaciones de Mérida mediante tecnología
LiDAR”. Saguntum: Papeles del Laboratorio de Arqueología de Valencia, nº 49,
pp. 197-201.

CORRALES ÁLVAREZ, Á., BERMEJO MELÉNDEZ, J. y CAMPOS CARRASCO, JM.
(2018): “Aplicaciones SIG e infográficas en la Casa Norte del yacimiento
arqueológico de Arucci (Aroche, Huelva)”. Virtual Archaeology Review. Vol. 9(18),
pp. 77-86.

COSTA-GARCÍA, J. M.; CASAL, R. (2015): “Fotografía aérea histórica, satelital moderna y
LiDAR aéreo en algunos recintos militares romanos de Castilla y León”. Portugalía,
nº 36, pp. 143-145.

COSTA GARCÍA, J.M. y FONTE, J. (2017): “Scope and limitations of airborne LiDAR
technology for the detection and analysis of Roman military sites in Northwest
Iberia”. En MAYORAL HERRERA, V., PARCERO-OUBIÑA, C. y FÁBREGA-
ÁLVAREZ, P. (Eds.): Archaeology and Geomatics. Harvesting the benefits of 10
years of training in the Iberian Peninsula (2006-2015), Sidestone Press, pp. 57-73.

CRIADO BOADO, F. (1993): “Límites y posibilidades de la Arqueología del Paisaje”. SPAL,
Revista de Prehistoria y Arqueología., Vol. 2, pp. 9-55.

\- (1999): “Del terreno al espacio: Planteamientos y Perspectivas para la
Arqueología del Paisaje”. CAPA: Cadernos de Arqueoloxía e Patrimonio, nº 6,
pp. 1-82.

CRUTCHLEY, S. (2010): The Light Fantastic. Using Airborne LiDAR in Archaeology Survey.
English Heritage, Swindon.

CUADRADO MÉNDEZ, O. (2001): “La distorsión radial y su representación gráfica”, III
Jornadas de Fotogrametría Arquitectónica, Universidad de Valladolid, Valladolid.

DE REU, J., DE SMEDT, P., HERREMANS, D., VAN MEIRVENNE, M., LALOO, P., y DE
CLERCQ, W. (2014): “On introducing an image-based 3D reconstruction method
in archaeological excavation practice”. Journal of Archaeological Science, Vol.41,
pp. 251-262.

DIETZ, C., CATANZARITI, G., DE LA PRESA, P. y JIMENO, A. (2011): “Técnicas no
invasivas para el registro del patrimonio arqueológico”. Monografías del Instituto
del Patrimonio Cultural de España, Ministerio de Cultura de España, ed. Secretaría
General Técnica, Subdirección General de Publicaciones, Información y
Documentación, pp. 118-129.

DÜBEL, S. y SCHUMANN, H. (2017): “Visualization of features in 3D Terrain”. ISPRS
International Journal of Geo-Information, Vol. 6(11), 357.

ELTNER, A. y SOFIA G. (2020): “Structure from motion: photogrammetric technique”.
Developments in Earth Surface Processes, Vol. 23, pp. 1-24.

64

<!-- p. 65 -->

FÁBREGA ÁLVAREZ, P. (2017): Recorriendo y observando paisajes digitales, una
aproximación al análisis arqueológico con tecnologías de la información
geográfica (TIG). Tesis Doctoral de la Universidad de Jaén.

FAIRÉN JIMÉNEZ, S. (2003): “Visibilidad y percepción del entorno. Análisis de la distribución
del arte rupestre esquemático mediante sistemas de información geográfica”.
Lucentum, nº XXI-XXII, pp. 27-43.

FEDER, K. L. (1979): “Geographic patterning of tool types as elicited by trend surface analysis”.
En UPHAM, S. (ed.): Computer Graphics in Archaeology, Anthropological
Research Papers, nº. 15, Arizona State University, Tempe, pp. 95–102.

FERNÁNDEZ-LOZANO, J., BLANCO-SÁNCHEZ, J.A., CARRASCO, R.M., PEDRAZA,
REMONDO, J., BONAECHEA, J., GONZÁLEZ DÍEZ, A.; BERNARDO-
SÁNCHEZ, A., MÉNDEZ-CECILIA, A.J., GUTIÉRREZ-ALONSO, G. (2019):
“Nuevas evidencias del impacto de la minería aurífera romana mediante el estudio
de marcadores geomorfológicos, drones y LiDAR en los piedemontes zamoranos”.
XV Reunión Nacional de Cuaternario (Bilbao 1-5 julio 2019), pp 114-117.

FERNÁNDEZ-LOZANO, J. y GUTIÉRREZ-ALONSO, G. (2016): “Improving archaeological
prospection using localized UAVs assisted photogrammetry: An example from the
Roman Gold District of the Eria River Valley (NW Spain). Journal of
Archaeological Science: Reports, Vol. 5, pp. 509–520.

FEURER, D. y VINATIER, F. (2018): “Joining multi-epoch archival aerial images in a single
SfM block allows 3-D change detection with almost exclusively image information”.
ISPRS Journal of Photogrammetry and Remote Sensing, Vol.146, pp. 495-506.

FONSTAD, M.A., DIETRICH, J.T., COURVILLE, B.C., JENSEN, J.L., CARBONNEAU, P.E.
(2013): “Topographic structure from motion: a new development in
photogrammetric measurement”. Earth Surface Processes and Landforms, Vol. 38,
pp. 421-430.

GARCÍA SANJUÁN, L., WHEATLEY, D.W., MURRIETA FLORES, P. y MÁRQUEZ PÉREZ,
J. (2009): “Los SIG y el análisis espacial en arqueología: aplicaciones en la
prehistoria reciente del sur de España”. En ONTIVEROS CAU, M.A. y NIETO
PRIETO, F.X: Arqueología náutica mediterránea. Museu d'Arqueologia de
Catalunya, pp. 163-178.

GOODCHILD, H., HOLM, N., y SINDBÆK, S. (2017): “Borgring: The discovery of a Viking
Age ring fortress”. Antiquity, Vol. 91(358), pp. 1027-1042.

GÓMEZ, C. (2012): Historical 3D Topographic Reconstruction of the Iwaki Volcano using
Structure from Motion from Uncalibrated Aerial Photographs, HAL [Consulta: 02-
10-2020], recuperado de: https://hal.archives-ouvertes.fr/hal-00765723.

GÓMEZ, C., HAYAKAWA, Y. y OBANAWA, H. (2016): “A study of Japanese landscapes
using structure from motion derived DSMs and DEMs based on historical aerial
photographs: New opportunities for vegetation monitoring and diachronic
geomorphology”. Geomorphology, Vol. 242, pp. 11-20.

GRAU MIRA, I. (2006): La aplicación de los S.I.G. en la Arqueología del Paisaje, Servicio de
Publicaciones de la Universidad de Alicante.

65

<!-- p. 66 -->

HARRIS, T.M. (2000): “Moving GIS: exploring movement in prehistoric cultural landscapes
using GIS. En LOCK, G. (ed): Beyond the Map: archaeology and Spatial
Technologies. NATO Science Series: Life Sciences, Vol. 321, pp. 116-123.

HESSE, R. (2010): “LIDAR-derived Local Relief Models (LRM), a new tool for archaeological
prospection”. Archaeological Prospection, nº 17, pp. 67–72.

HODDER, I. y ORTON, C. (1976): Spatial Analysis in Archaeology. Cambridge University
Press.

IAPS (Institute of Anthropological and Spatial Studies): Relief Visualization Toolbox (RVT)
applied project. Recuperado de https://iaps.zrc-sazu.si/en/rvt#v.

INGOLD, T. (1992): “Culture and the perception of the environment”. en Croll, E. y PARKIN,
D. (Eds.): Bush base, forest farm. Routledge, Londres, pp. 39-56.

JIMÉNEZ ÁVILA, J. y GÓNZALEZ CORDERO, A. (1999): “Referencias culturales en la
definición del Bronce Final y la Primera Edad del Hierro de la Cuenca del Tajo: el
yacimiento de Talavera la Vieja, Cáceres”. II Congreso de Arqueología Peninsular.
Primer Milenio y Metodología. Tomo III. Universidad de Alcalá. Fundación Rei
Afonso Henriques, pp. 181-190.

JIMÉNEZ DE GREGORIO, F. (1950): “Hallazgos arqueológicos en la Jara (II)”. Archivo
Español de Arqueología, Vol. XXIV: 105-117.

\- (1966): “Hallazgos arqueológicos en la provincia de Toledo”. Archivo Español
de Arqueología, Vol. XXXVIII, pp. 185-187.

KOKALJ, Ž., ZAKŠEK, K. y OŠTIR, K. (2011): “Application of Sky-View Factor for the
Visualization of Historic Landscape Features in Lidar-Derived Relief Models”.
Antiquity, Vol. 85 (327), pp. 263–273.

KVAMME, K.L. (1983): “Computer Processing Techniques for Regional Modeling of
Archaeological Site Locations”. Advances in Computer Archaeology, Vol. 1, pp. 26-
\52.

LLOBERA, M. (1996): “Exploring the topography of mind: GIS, social space and archaeology”.
Antiquity, Vol. 70, nº 269, pp. 612-622.

LONGARES ALADRÉN, L.A., PEÑA-MONNÉ, J.L., ESCUDERO ESCUDERO, F. y PÉREZ-
LAMBÁN, F. (2018): “Cartografía histórica y reconstrucción paleotopográfica y
geoarqueológica de la ciudad romana de Caesar Augusta (Zaragoza, España)”.
Boletín Geológico y Minero, nº129 (1/2), pp. 421-435.

LÓPEZ-FRAILE, F.J, ALCARAZ-CASTAÑO, M., LÓPEZ-RECIO, M., BAENA, J. MORÍN,
J., ROCA, M., RODRÍGUEZ-AVELLO, L., TAPIAS, F. PÉREZ-GONZÁLEZ, A.
y SANTONJA, M. (2014): “Aplicaciones SIG en la caracterización
geoarqueológica del yacimiento paleolítico de Las Delicias (Madrid, España) y
visualización en 3D de los resultados”. Virtual Archaeology Review, Vol. 5 (10),
pp. 32-44.

LÓPEZ GARCÍA, M.J. y CASELLES, V. (1991): “Introducción a la Teledetección” en
GANDÍA, S. Y MELIÁ, J. (coords.): La Teledetección en el Seguimiento de los
Fenómenos Naturales. Recursos Renovables: Agricultura. Universidad de
Valencia, pp. 19-50.

66

<!-- p. 67 -->

LÓPEZ-ROMERO, R. (2005): “Cálculo de rutas óptimas mediante SIG en el territorio de la
ciudad celtibérica de Segeda. Propuesta metodológica”. Saldvie: Estudios de
prehistoria y arqueología, nº 5, pp. 95-111.

\- (2006): “Aplicación de los SIG al estudio del territorio de Segeda”. Studium:
Revista de humanidades, nº 12, pp. 57-84.

LÓPEZ VERGARA, J.L. (1988): Manual de Fotogeología. (3ª ed.). Junta de Energía Nuclear,
Madrid.

LUIS RIVAS, I. (2013): Toma de datos fotogramétricos, reconstrucción virtual, realidad
aumentada y difusión en la red de la Iglesia Nuestra Señora de la Asunción,
Mombuey (Zamora). Trabajo de Fin de Máster de la Universidad de Salamanca.

MARTINS, M. M. y DANTAS GIESTAL, C. (2000): “O Projecto SIABRA: um Sistema de
Informação Geográfica para a Arqueologia Urbana em Braga”. En OLIVEIRA, J.
(ed): Actas do 3º Congresso de Arqueologia Peninsular Sistema de Informação
Arqueológica. (SIG’s aplicados à Arqueologia da Península Ibérica). Porto,
ADECAP, pp. 43-61.

MAXIMILIANO CASTILLEJO, A. y BARCIA GARCÍA, C. (2017). “Viabilidad y operativa en
la digitalización de casos rupestres prehistórico del "Arte sureño"”: Recetas digitales
desde técnicas SFM y plataformas open source”. En Actas del Primer Congreso en
Ingeniería Geomática, Editorial Universitat Politècnica de València, pp. 20-26.

MEDINA CARRILLO, F. (2014): “La fotogrametría digital como herramienta de trabajo para
la toma de datos y catalogación de las iglesias románicas en la comarca de Las
Merindades (Burgos)”. Trabajo de Fin de Grado de la Universidad de Alicante

MICHELETTI, N., CHANDLER, J.H. y LANE, S.N. (2015): Structure from Motion (SfM)
Photogrammetry. En CLARKE, L.E. y NIELD, J.M. (Eds.): Geomorphological
Techniques (Online Edition). London: British Society for Geomorphology, Chap. 2,
Sec. 2.2.

MÍNGUEZ GARCÍA, Mª C. y CAPDEVILLA MONTES, E. (Eds.) (2016): Manual de
Tecnologías de la Información Geográfica aplicadas a la Arqueología. Alcalá de
Henares: Museo Arqueológico Regional. Madrid: Colegio Oficial de Doctores y
Licenciados en Filosofía y Letras y en Ciencias de la Comunidad de Madrid.

MÖLG, N. y BOLCH, T. (2017): “Structure-from-Motion Using Historical Aerial Images to
Analyse Changes in Glacier Surface Elevation”. Remote Sensing. Vol.9(10), 1021.

MONTERROSO CHECA, A. (2017): “Remote Sensing and Archaeology from Spanish LiDAR-
PNOA: Identifying the Amphitheatre of the Roman City of Torreparedones
(Córdoba-Andalucía-Spain)”. Mediterranean Archaeology and Archaeometry, Vol.
17, nº 1, pp. 15-22.

MONTUFO MARTÍN, A.M. (1991). “Aplicaciones de la Teledetección en Arqueología: una
revisión crítica”. Cuadernos de prehistoria y arqueología de la Universidad de
Granada, nº16-17, pp. 425-451.

67

<!-- p. 68 -->

MUÑOZ VILLARREAL, J.J. y RUIZ CARMONA, S. (1993): “Estudio arqueológico de la
calzada romana que comunica los municipios de Belvis de la Jara y Azután
(Toledo)”. Actas del I Congreso Internacional de Caminería Hispánica, Madrid.
Tomo I, pp. 79-88.

NCGIA (1990): NCGIA Core Curriculum. Santa Barbara. Universidad de California.

NOVÁK, D. (2014): Local Relief Model (LRM) Toolbox for ArcGIS. Instituto de Arqueología,
Academia checa de Ciencias, Praga, República Checa. Recurso electrónico,
[Consulta:12-10-2020], recuperado de:
/www.academia.edu/5618967/Local_Relief_Model_LRM_Toolbox_for_ArcGIS_
UPDATE_2014-10-7.

OLAYA, V. (2014): Sistemas de Información Geográfica. Madrid, Bubok.

OPITZ, R.S, RYZEWSKI, K., CHERRY, J.F. y MOLONEY, B. (2015): “Using Airborne LiDAR
Survey to explore Historic-era archaeological landscapes of Montserrat in the
Eastern Caribbean”. Journal of Field Archaeology, Vol.40, pp. 523-541.

OREJAS SACO DEL VALLE, A. (1991): “Arqueología del paisaje. Historia, problemas y
perspectivas”. Archivo Español de Arqueología, nº 64, pp. 191-230.

\- (1992): Estructura social y territorio: el impacto romano en la cuenca
noroccidental del Duero. Tesis doctoral de la Universidad Complutense de
Madrid.

\- (1995): “Territorio, análisis territorial y Arqueología del Paisaje”. Studia
histórica, Historia antigua, nº 13-14, pp. 61-68.

ORENGO, H.A., FIZ FERNÁNDEZ, J.I. y MACÍAS SOLÉ, J.M. (2011): “Restitución 3d de la
topografía de la antigua ciudad de Tarraco en un entorno SIG: Propuestas
metodológicas y primeros resultados”, Tecnologías de Información Geográfica y
análisis arqueológico del Territorio, Anejos del Archivo Español de Arqueología,
LIX, vol. 0, pp. 713-722.

ORENGO, H.A. y PETRIE, C.A. (2018): “Multi-scale relief model (MSRM): a new algorithm
for the visualization of subtle topographic change of variable size in digital elevation
models”. Earth Surface Processes and Landforms, Vol. 43, pp. 1361-1369.

ORTEGA BLANCO, J. y DEL VALLE GUTIÉRREZ, M. (2004): “El poblado de la Edad del
Hierro del Cerro de la Mesa (Alcolea de Tajo, Toledo): Primeros resultados”.
Trabajos de Prehistoria, Vol.61, nº1, pp. 175-185.

PARCERO-OUBIÑA, C. (2000): “Tres para dos. Las formas de poblamiento en la Edad del
Hierro del noroeste ibérico”. Trabajos de Prehistoria, Vol.57(1): pp. 75-95.

\- (2018): “Mapeando experiencias: SIG y arqueología en el paisaje”. en:
FLORES BLANCO, L. (Ed.): Lugares, Monumentos, Ancestros. Arqueologías
de paisajes andinos y lejanos. Avqi Ediciones, Lima, pp. 55–70.

PARCERO-OUBIÑA, C., BARREIRO, D., y CRIADO-BOADO, F. (2014): “Landscape
Archaeology”. En Claire Smith & Jo Smith (Eds.): Encyclopedia of Global
Archaeology, Springer, Nueva York, pp. 4379-4388.

68

<!-- p. 69 -->

PEREIRA SIESO, J. (2008): “Nuevos escenarios en el circuito de intercambios de época colonial:
los vados del Tajo”. En GARCIA I RUBERT, D.; MORENO MARTÍNEZ, I.;
GRACIA ALONSO, F. (coords.): Contactes. Indígenes i fenicis a la Mediterrània
occidental entre els segles VIII i VI ane. Simposio de Arqueología de Alcanar, 24-
26 de noviembre de 2006, pp. 191-209.

PEREIRA SIESO, J., CHAPA BRUNET, T., CHARRO LOBATO, C., VALLÉS IRISO, J. y
MAYORAL HERRERA, V. (2020): "Nuevas perspectivas en el estudio del
urbanismo del asentamiento fortificado del Cerro de la Mesa (Alcolea de Tajo,
Toledo) mediante métodos no destructivos". En CARRETERO PÉREZ, A. y PAPÍ
RODES, C. (Coord.): Actualidad de la investigación arqueológica en España I
(2018-2019). Conferencias impartidas en el Museo Arqueológico Nacional.
Ministerio de Cultura. Madrid, pp. 367-383.

PEREIRA UZAL, J.M. (2013): “Modelado 3D en patrimonio cultural por técnicas de Structure
From Motion”. PH Investigación: revista del IAPH para la investigación del
patrimonio cultural, nº. 1, pp. 77-87.

PÉREZ ÁLVAREZ, J.A., BASCÓN ARROYO, F.M. y CHARRO LOBATO, M.C. (2014):
“Photogrammetric usage of 1956–57 USAF aerial photography of Spain”. The
Photogrammetric Record, Vol. 29/145, pp. 108–124.

PÉREZ ÁLVAREZ, J.A., BASCÓN ARROYO, F.M, CRESPO PÉREZ, F.C. y CHARRO
LOBATO, Mª C. (2013): “Project Casey Jones, 1945-46: el vuelo histórico
"fotogramétrico" de la serie A en España y sus aplicaciones cartográficas”. Mapping,
nº159, pp. 14–24.

PÉREZ ÁLVAREZ, J.A., MAYORAL HERRERA, V., MARTÍNEZ DEL POZO, J.A. y DE
TENA REY, Mª T. (2013): “Multi-temporal archaeological analyses of alluvial
landscapes using the photogrammetric restitution of historical flights: a case study
of Medellin (Badajoz, Spain)”. Journal of Archaeological Science, Vol. 40/1, pp.
349–364.

QUEROL FERNÁNDEZ, Mª.Q. (2010): Manual de gestión del patrimonio cultural. Ed. Akal,
Madrid.

QUIRÓS LINARES., F. y FERNÁNDEZ GARCÍA, F. (1997): “El vuelo fotográfico de la “Serie
A”. Ería: Revista cuatrimestral de geografía, nº 43, pp. 190-198.

QUIRÓS ROSADO, E. (2014): Introducción a la Fotogrametría y Cartografía aplicadas a la
Ingeniería Civil. Universidad de Extremadura, Cáceres.

ROMERO SIERRA, M., ROJO ARIZA, M.C. y MARTINEZ GIL, T. (2013): “Modelos virtuales
entorno al Territorio Vetón; hacia una visualización del pasado accesible para todos
los públicos”. Virtual Archaeology Review, Vol. 4, nº 8, pp. 15-19.

REMONDINO, F., DEL PIZZO, S., KERSTEN, T.P. y TROISI, S. (2012): “Low-cost and open-
source solutions for automated image orientation—a critical overview”.
EuroMed'12: Proceedings of the 4th international conference on Progress in
Cultural Heritage Preservation, Octubre de 2012, pp. 40–54.

REUTEBUCH, S.E., MCGAUGHEY, R.J. y ANDERSEN, H.E. (2005): “Light Detection and
Ranging (LIDAR): An Emerging Tool for Multiple Resource Inventory”. Journal
of Forestry, Vol. 103(6), pp.286-292.

69

<!-- p. 70 -->

RISBØL, O., BOLLANDSÅS, O.M., NESBAKKEN, A., ØRKA, O.H., NÆSSET, E. y
GOBAKKEN, T. (2013): “Interpreting cultural remains in airborne laser scanning
generated digital terrain models: effects of size and shape on detection success
rates”. Journal of Archaeological Science, Vol. 40, Issue 12, pp.4688-4700.

RODRÍGUEZ HERNÁNDEZ, J. (2018): Las comunidades de la Edad del Hierro en el occidente
de la Meseta: cultura material, poder y sociedad. Tesis Doctoral de la Universidad
Complutense de Madrid.

RODRÍGUEZ MORENO, L. (2016): Aplicación de la técnica de Foto-Reconstrucción 3D para
monitorizar la erosión de un escarpe natural en la ladera acarcavada del valle del
río Duratón (Segovia). Trabajo Fin de Máster de la Universidad Complutense de
Madrid.

ROSALES LEÓN, J.J. y RODRIGO BELLO, J.J. (2012): “Tecnología LiDAR aplicada a la
gestión del territorio.” Tierra y tecnología, nº41, pp. 57-59.

ROSENSWIG, R. y LÓPEZ-TORRIJOS, R. (2018): “Lidar reveals the entire kingdom of Izapa
during the first millennium BC”. Antiquity, Vol.92(365), pp. 1292-1309.

ROUCO COLLAZO, J., BENAVIDES LÓPEZ, J.A. y MARTÍN CIVANTOS, J.M. (2020):
“Falling from the sky. Aerial photogrammetry and LiDAR applied to the
Archaeology of Architecture and Landscape: two fortifications from the Alpujarra
(Granada, Spain)”. En RAMÍREZ GALÁN, M. y SANDIFER BARD, R. (Eds):
Studies in archaeometry Proceedings of the archaeometry symposium at NORM
2019, 16-19 de junio, Portland, Oregon, Portland State University, pp. 87-174.

RUIZ-GÁLVEZ, M. y GALÁN, E. (1991): “Las estelas del Suroeste como hitos de rutas
ganaderas y vías comerciales”. Trabajos de Prehistoria, Vol.48, pp. 257-273.

RUIZ ZAPATERO, G. y ÁLVAREZ-SANCHÍS, J.R. (2012): “¿Centros de poder? Sociedad y
poblamiento en la Meseta Norte española (ca. 800 - 400 a.C.)”. Vegueta: Anuario
de la Facultad de Geografía e Historia, nº. 15, pp. 211-233.

SÁNCHEZ SOBRINO, J.A. (2007): Introducción a la Fotogrametría. Universidad Politécnica
de Madrid, Madrid.

SÁNCHEZ YUSTOS, P. (2010): “Las dimensiones del paisaje en Arqueología”. Munibe,
(Antropologia-Arkeologia), nº 61, pp. 139-151.

SANJOSÉ, J.J., MARTÍNEZ GARCÍA, M. y LÓPEZ GONZÁLEZ, M. (2004): Topografía para
estudios de Grado. Editorial Bellisco, Ediciones Técnicas y Científicas.

SANTAMARÍA PEÑA, J. y SANZ MÉNDEZ, T. (2011): Fundamentos de Fotogrametría.
Universidad de La Rioja.

SCIANNA, A. y VILLA, B. (2011): “GIS Applications in Archaeology”, Archeologia e
Calcolatori, nº 22, pp. 337-363.

SMITH, M.W., CARRIVICK, J.L. y QUINCEY, D.J. (2016): Structure from motion
photogrammetry in physical geography. Progress in Physical Geography: Earth and
Environment, Vol. 40 (2), pp. 247–275.

70

<!-- p. 71 -->

ŠTULAR, B., KOKALJ, Ž., OŠTIR, K. y NUNINGER, L. (2012): “Visualization of lidar-derived
relief models for detection of archaeological features”. Journal of Archaeological
Science, Vol. 39, pp. 3354–3360.

TANARRO GARCÍA, L.M. y GÓMEZ GUTIÉRREZ, A. (2014): “"La aplicación de técnicas de
foto-reconstrucción 3D al estudio de la dinámica erosiva en las laderas acarcavadas
de Valle del Caslilla (Segovia y de una cárcava permanente en Monroy (Cáceres)".
En SCHNABEL, S. y GÓMEZ GUTIÉRREZ, A. (Ed.). Avances de la
Geomorfología en España 2012-2014, XIII Reunión Nacional de Geomorfología,
Cáceres, pp. 347-350.

TOMÁS, R., CANO, M., RIQUELME, A., ABELLÁN, A. y JORDÁ, L. (2016): “Structure from
Motion (SfM): una técnica fotogramétrica de bajo coste para la caracterización y
monitoreo de macizos rocosos”, Reconocimiento, tratamiento y mejora del terreno,
10º Simposio Nacional de Ingeniería Geotécnica. La Coruña, pp. 209-216.

VELA SANTAMARÍA, F.J. (2009): “Agua e industria en la segunda mitad del siglo XVI: los
molinos harineros de la Meseta Sur”. Investigaciones Históricas, Época Moderna y
Contemporánea, nº 29, pp. 11-40.

VERHAGEN, F. (2017): “Spatial Analysis in Archaeology: Moving into New Territories”. En
SIART, C., FORBRIGER, M. y BUBENZER, O. (eds.): Digital Geoarchaeology,
New Techniques for Interdisciplinary Human-Environmental Research. Cham,
Springer, pp. 11-25.

WHEATLEY, D.W. y GILLINGS, M. (2002): Spatial Technology and Archaeology. The
Archaeological Applications of GIS. Londres y Nueva York, Taylor & Francis.

WESTOBY, M.J., BRASINGTON, J., GLASSER, N.F., HAMBREY, M.J., REYNOLDS, J.M.
(2012): “‘Structure from-Motion’ photogrammetry: a low-cost, effective tool for
geosciences applications”. Geomorphology, Vol. 179, pp. 300–314.

ZAKŠEK, K., OŠTIR, K. y KOKALJ, Z. (2011): “Sky-View Factor as a Relief Visualization
Technique”. Remote Sensing, Vol. 3, pp. 398–415.

ZAMORA MERCHÁN, M. y BAENA PREYSLER, J. (2010): “Los SIG en la arqueología
española: una valoración " CAA" del contexto actual”. Cuadernos de prehistoria y
arqueología de la Universidad de Granada, nº 20, pp. 49-64.

71

<!-- p. 72 -->

ANEXOS

\1. Quality Report (Informe de Calidad) de la reconstrucción de 1945

Características principales

72

<!-- p. 73 -->

\2. Quality Report (Informe de Calidad) de la reconstrucción de 1956

Características principales

73

<!-- p. 74 -->

74
