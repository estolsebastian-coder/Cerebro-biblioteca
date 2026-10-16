---
type: libro
title: "Estrategias de modelado patrimonial en HBIM, aplicación a la lectura"
author: "Roque Angulo-Fornos"
categoria: "Tesis doctorales y análisis"
paginas: 11
extraccion: "texto"
fuente: "local:E:/DISCIPLINAS, TEXTOS Y MAPAS/Biblioteca digital/Tesis doctorales y análisis/Estrategias de modelado patrimonial en HBIM.pdf"
convertido: 2026-10-13
---

# Estrategias de modelado patrimonial en HBIM, aplicación a la lectura

> Texto extraído de `Tesis doctorales y análisis/Estrategias de modelado patrimonial en HBIM.pdf` (11 páginas, texto). El PDF original está en el disco E: (DISCIPLINAS, TEXTOS Y MAPAS\Biblioteca digital); `<!-- p. N -->` marca el inicio de cada página.

<!-- p. 1 -->

ARQUEOLOGÍA DE LA ARQUITECTURA, 18,
enero-diciembre 2021, e109
Madrid / Vitoria
ISSN-L: 1695-2731
https://doi.org/10.3989/arq.arqt.2021.001

MONOGRÁFICO: TECHNOHERITAGE 2019. 4TH INTERNATIONAL CONGRESS SCIENCE
AND TECHNOLOGY FOR THE CONSERVATION OF CULTURAL HERITAGE. SELECCIÓN
DE CONTRIBUCIONES / TECHNOHERITAGE 2019. A SELECTION OF CONTRIBUTIONS

Estrategias de modelado patrimonial en HBIM, aplicación a la lectura
estratigráfica del muro de fachada del cuadrante renacentista de la
catedral de Sevilla*
Heritage modelling strategies in HBIM, application to the stratigraphic reading of
the façade of the Renaissance quadrant of the Cathedral of Seville

Roque Angulo-Fornos1, Manuel Castellano-Román2, Francisco Pinto-Puerto3
Departamento de Expresión Gráfica Arquitectónica. Universidad de Sevilla

RESUMEN
Este artículo presenta diferentes estrategias de modelado digital del proceso constructivo de un elemento arquitectónico en un entorno HBIM, analizando los Niveles de Conocimiento –LOK– que permiten cada una de ellas.
Partiendo de la captura digital fotogramétrica de uno de los muros de la fachada de las dependencias capitulares
de la catedral de Sevilla, se ha generado un modelo conceptual inicial orientado a la definición genérica del bien
y a su encuadre dentro del conjunto catedralicio. Posteriormente, con objeto de experimentar la potencialidad
de aplicación de estas herramientas al análisis arqueológico y arquitectónico, se han transportado sus resultados
a este entorno HBIM, alcanzando la caracterización tridimensional de cada una de sus unidades constructivas
básicas de la fachada a diversos niveles, desde unidades estratigráficas formadas por regiones hasta las unidades materiales de cada sillar. Por lo tanto, la lectura estratigráfica no se limita al análisis de una superficie de un
paramento aislado, sino que se aborda desde su realidad tridimensional general, la catedral. El alto nivel de conocimiento alcanzado en este modelo más desarrollado ha permitido utilizarlo como base para el registro y gestión
de la información patrimonial, permitiendo visualizaciones temáticas gráficas y alfanuméricas.

Palabras clave: HBIM; análisis estratigráfico; patrimonio arquitectónico; catedral de Sevilla.

ABSTRACT
This paper discusses different heritage modelling strategies included in the HBIM model, analyzing the Levels of
Knowledge –LOK– allowed by each of them. Starting with the photogrammetric digital capture of the Renaissance
Quadrant façade of the Cathedral of Seville, an initial conceptual model has been generated, oriented towards the
generic definition of the asset and its location in the context of cathedral ensemble. The archaeological and architectonical analysis of the constructive process have enhanced the knowledge of the study case and, therefore,
the possibility to increase the level of development of the HBIM model, which have reached the three-dimensional
characterization of every single basic constructive unit of the façade. Therefore, the stratigraphic analysis is not
limited to the surface of the wall, but characterized as a three-dimensional reality, approaching thus the cathedral.
The high level of knowledge reached by this model has made it possible to take it as basis for registering and
managing heritage information, allowing themed graphic and alphanumeric views.

Key words: HBIM; stratigraphic analysis; architectural heritage; Cathedral of Seville.

Recibido: 03-02-2020. Aceptado: 19-03-2020. Publicado: 13-04-2021

\* Este trabajo forma parte de las acciones del proyecto HAR2016-78113-R del Plan Nacional de I+D+i del Ministerio de Economía y Competitividad.
1  roqueaf@us.es / ORCID iD: https://orcid.org/0000-0002-0401-8377
2  manuelcr@us.es / ORCID iD: https://orcid.org/0000-0003-4787-447X
3  fspp@us.es / ORCID iD: https://orcid.org/0000-0003-4608-6818

<!-- p. 2 -->

ESTRATEGIAS DE MODELADO PATRIMONIAL EN HBIM, APLICACIÓN A LA LECTURA ESTRATIGRÁFICA DEL MURO DE FACHADA
DEL CUADRANTE RENACENTISTA DE LA CATEDRAL DE SEVILLA 2

Cómo citar este artículo / Citation
Angulo-Fornos, R., Castellano-Román, M. y Pinto-Puerto, F. 2021: “Estrategias de modelado patrimonial en HBIM, aplicación a la lectura estratigráfica del muro de fachada del cuadrante renacentista de la catedral de Sevilla”, Arqueología de la Arquitectura, 18: e109. https://doi.
org/10.3989/arq.arqt.2021.001

Copyright: © CSIC, 2021. © UPV/EHU Press, 2021. Este es un artículo de acceso abierto distribuido bajo los términos de la licencia de uso y
distribución Creative Commons Reconocimiento 4.0 Internacional (CC BY 4.0).

\1. INTRODUCCIÓN tos del inmueble. Finalmente, el LOK500 se alcanza en
aquellos modelos HBIM que resulten operativos para la
En los últimos años se ha producido un amplio reperto- gestión eficiente e integral de la tutela patrimonial (Casrio de aportaciones en relación con el uso patrimonial de tellano-Román y Pinto-Puerto 2019).
la metodología BIM, agrupadas bajo la denominación Sin renunciar a la precisión geométrica que permite
HBIM pero muy diferentes en cuanto a su planteamiento la captura digital fotogramétrica, se ha generado un moconceptual, estrategias metodológicas y resultados espe- delo conceptual inicial orientado a la definición genérica
rados. A grandes rasgos, pueden reconocerse experien- del bien y a su encuadre dentro del conjunto arquitectócias orientadas al modelado de complejas geometrías pa- nico. El análisis arqueológico y arquitectónico desarroramétricas para la reconstrucción virtual de arquitecturas llado sobre el proceso constructivo (Pinto-Puerto 2013)
desaparecidas, experiencias centradas en la obtención ha permitido el avance en el conocimiento del caso de
automática o semiautomática de modelos de alta preci- estudio y, en consecuencia, la posibilidad de aumentar el
sión geométrica a partir de capturas digitales de edificios nivel de desarrollo del modelo HBIM, que ha alcanzado
patrimoniales existentes y, finalmente, otros casos donde la caracterización tridimensional de cada una de las uniel modelo HBIM forma parte de un proceso de levan- dades constructivas básicas, que se ha llevado al límite
tamiento y análisis arquitectónico cuyas características alcanzando en este caso la discretización en sillares. Por
evolucionan según el nivel de conocimiento del edificio lo tanto, la lectura estratigráfica no se limita al análisis
(Rua y Gil 2014). de la superficie del paramento, sino que se aborda desde
La investigación que se presenta se sitúa dentro de su realidad tridimensional.
este último grupo, poniendo el foco en la capacidad de El alto nivel de conocimiento alcanzado en el modelos modelos HBIM para el registro de las diferentes fa- lo ha permitido utilizarlo como base para el registro y
ses constructivas reconocibles en una lectura estratigrá- gestión de la información patrimonial, permitiendo vifica de los paramentos de una estructura arquitectónica sualizaciones temáticas gráficas y alfanuméricas que faemergente. Se presentan diferentes estrategias de mode- vorecen su conocimiento y dan soporte, además, a otras
lado patrimonial, integradas en el mismo modelo HBIM, acciones de la tutela patrimonial como la difusión o la
que permiten presentar diferentes Niveles de Conoci- conservación preventiva.
miento, LOK. Para mostrar de una manera sintética los resultados
Estos LOK son una traslación del concepto BIM del de este trabajo, ajustándonos a la extensión de la aporNivel de Desarrollo ‒LOD‒ al ámbito del patrimonio ar- tación, se ha concretado la experiencia a una parte del
quitectónico. El Nivel de Conocimiento LOK100 está edificio tratado, con suficiente autonomía formal y consasociado a la identificación del bien patrimonial y a la in- tructiva, el muro suroeste del cuadrante renacentista de
vestigación y generación de conocimiento sobre el mis- la catedral de Sevilla.
mo. El LOK200 permite una caracterización gráfica y de Este conjunto de construcciones y espacios, de diverinformación suficiente para el desarrollo de las acciones so origen y evolución, se encuentran adosados al ángurelacionadas con la protección jurídica del bien y su pla- lo suroriental del templo, confinados por un imponennificación estratégica o plan director. El LOK300 avanza te muro de fachada, desplegado entre la Puerta de San
en la caracterización de las entidades gráficas hasta el Cristóbal y la Puerta de Campanillas, que le confiere la
punto de poder mostrar los resultados de investigaciones apariencia de un todo unitario y continuo, solo alterado
especializadas realizadas con metodología arqueológica por la disposición de algunos huecos y por la variación
u otros estudios disciplinares específicos de auscultación del orden en su extremo oriental (Fig. 1).
y diagnóstico. El LOK400 contempla las acciones espe- La fachada del cuadrante renacentista encierra edificíficas de conservación e intervención sobre los elemen- caciones como la Sacristía de los Cálices, el Patio de los

Madrid/Vitoria. ISSN-L: 1695-2731. https://doi.org/10.3989/arq.arqt.2021.001 ARQUEOLOGÍA DE LA ARQUITECTURA, 18, enero-diciembre 2021, e109

<!-- p. 3 -->

3 Roque Angulo-Fornos, Manuel Castellano-Román y Francisco Pinto-Puerto

Figura 1. Situación en planta y fotografía de archivo del caso de estudio.

Óleos, la Sacristía Mayor, el Antecabildo, el Patio del importantes maestros mayores del arzobispado que proMariscal, la Sala Capitular, la escalera y el cuarto de las tagonizaron el tránsito a la Edad Moderna y el desarrotrazas. Cada una de ellas contiene elementos arquitectó- llo pleno de un lenguaje renacentista: Gil de Hontañón,
nicos, configuraciones espaciales y procesos constructi- Alonso Rodríguez, Diego de Riaño, Martín de Gainza,
vos bien diferenciados, trazados y dirigidos por los más Hernán Ruiz o Asencio de Maeda, entre otros. A su vez,

Madrid/Vitoria. ISSN-L: 1695-2731. https://doi.org/10.3989/arq.arqt.2021.001 ARQUEOLOGÍA DE LA ARQUITECTURA, 18, enero-diciembre 2021, e109

<!-- p. 4 -->

ESTRATEGIAS DE MODELADO PATRIMONIAL EN HBIM, APLICACIÓN A LA LECTURA ESTRATIGRÁFICA DEL MURO DE FACHADA
DEL CUADRANTE RENACENTISTA DE LA CATEDRAL DE SEVILLA 4

estas construcciones fueron amortizando progresiva- una potente cornisa. El conjunto queda rematado por
mente las antiguas estructuras defensivas que separaban una balaustrada modulada entre pináculos entorchados
la mezquita, y posteriormente la catedral gótica, del al- situados sobre las pilastras, que se duplican en las escázar (Arévalo-Rodríguez 2011). quinas. Toda la fábrica es de sillares de piedra de dos
El proceso constructivo del cuadrante renacentista orígenes litológicos bien diferenciadas: las pilastras y
puede acotarse entre 1528 y 1596, año en que se levan- entablamento es de una piedra calcarenita más comtaron las contadurías. El autor de la traza inicial de este pacta procedente de las canteras de Utrera, que permite
conjunto fue el maestro Diego de Riaño, y su construc- una labra más fina y detallada, mientras los fondos lición se prolonga tras su muerte hasta los años centrales sos entre éstas se han fabricado con piedra más porosa
del siglo XVI en los que se terminan de los remates su- procedente de la Sierra de San Cristóbal (Rodríguez
periores. La fábrica se inició por el extremo oeste, justo Estévez 1998).
por el muro que tratamos, tras demoler las edificacio- El caso de estudio se limita al tramo de fachada que
nes previas, levantar las cimentaciones del conjunto y comienza a levantarse adosado al estribo sureste del
nivelar el recinto (Tabales-Rodríguez y Jiménez Sancho crucero de la catedral y continua, demoliendo parte del
\2002) aprovechando parte de los muros de la sacristía muro almohade de separación con el Alcázar, adosada a
que comenzó a levantar el maestro Alonso Rodríguez los muros de la principiada sacristía de los Cálices. El
tras cerrar el cimborrio en 1506, inconclusa tras la des- proceso puede observarse a nivel de volúmenes concepgraciada caída de esa estructura en 1511. tuales en la secuencia de la Figura 2.
Por lo tanto, este edificio se inicia de una forma Este muro, de 1,10 m de espesor medio, fue construpeculiar: levantando el muro de fachada que delimita yéndose en diversos impulsos constructivos irregulares
el cuadrante renacentista antes que las propias depen- entre 1528 y 1543 según se desprende de la lectura esdencias, dando así prioridad a la protección del recin- tratigráfica de sus paramentos (Pinto-Puerto 2013). Esta
to. Esta forma de proceder es recurrente en el proceso lectura revela un proceso constructivo sin grandes inteconstructivo de la propia catedral, en la que, tras elimi- rrupciones, pero sujeto a algunos cambios de criterio.
nar un elemento de protección perimetral, se construía Las diferentes unidades constructivas no responden a alinmediatamente otro nuevo dentro del cual se desarro- teraciones de épocas posteriores, sino a los condicionanllaban fases constructivas posteriores (Pinto-Puerto tes del propio proceso de ejecución de la obra de Riaño,
2006, 2019: 229). La fachada se compone con un orden sugiriendo cuestiones relacionadas con la permanencia
corintio apilastrado sobre un potente basamento conti- de la sacristía anterior, el adosamiento obligado a la fánuo que recorre toda la longitud de la fachada y sirve brica gótica previa, la introducción de nuevas canteras
para asumir el desnivel del terreno colindante. Sobre en el suministro de material pétreo, o los reajustes del
estas pilastras se desarrolla un entablamento completo proyecto renacentista para las estancias capitulares sobre
formado por arquitrabe, friso decorado con cartelas y el proyecto gótico anterior.

Figura 2. Tres etapas del proceso general. Dibujos de J. M. Guerrero 2013.

Madrid/Vitoria. ISSN-L: 1695-2731. https://doi.org/10.3989/arq.arqt.2021.001 ARQUEOLOGÍA DE LA ARQUITECTURA, 18, enero-diciembre 2021, e109

<!-- p. 5 -->

5 Roque Angulo-Fornos, Manuel Castellano-Román y Francisco Pinto-Puerto

\2. METODOLOGÍA

La generación del modelo HBIM de la fachada se ha
fundado sobre la base del conocimiento existente sobre
la misma, en particular sobre un modelo conceptual previo que atañe a toda la catedral, mucho menos definido
(Guerrero Vega 2010), y la lectura estratigráfica citada
en la introducción, de la que se han extraído las claves
para la caracterización de las unidades constructivas del
modelo del fragmento seleccionado desde un nivel de
detalle bajo a uno alto.
La lectura estratigráfica sobre la que se ha trabajado
estaba integrada en una lectura documental y arquitectónica del edificio tratado (Fig. 3) (Pinto-Puerto 2013).
Dado el carácter de este trabajo, se consideraron como
unidades estratigráficas las regiones formadas por cada
grupo de sillares que mantenían un aparejo semejante, y
las discontinuidades que se producían entre ellos como
fronteras. El cambio de material no se consideró como
elemento diferenciador entre unidades, pues documentalmente se constató que fue coetáneo. Estas diferenciaciones se realizaron tanto por el exterior como por el
interior del muro, verificando su relación con cada uno
de los espacios contenidos y los acontecimientos sucedidos. A pesar de plantearse la metodología estratigráfica
de forma simplificada, los resultados fueron suficientemente explícitos y útiles para plantear preguntas y obtener relaciones entre diversas fuentes documentales.
En paralelo a la revisión de la lectura estratigráfica, se realizó una captura digital fotogramétrica que ha
proporcionado la información métrica necesaria para la
generación del modelo tridimensional y ha permitido reconocer y delimitar cada unidad constructiva con mayor
precisión. La nube de puntos de la captura digital se ha
procesado en el software de ingeniería inversa Geomagic Design X®, para la obtención y segmentación de una
malla de triángulos a partir de la cual obtener las superficies simples y complejas que conforman el límite exterior del muro. Ese mismo entorno de trabajo ha servido
para la resolución de las uniones entre dichas superficies
y la obtención de una única superficie compuesta constituyente de la “cáscara” exterior del muro (Fig. 4). Esa
superficie de alta precisión (en términos de adaptación a
la captura digital fotogramétrica), combinada con otras
superficies de menor precisión (basadas en levantamientos gráficos preexistentes), procesadas ya en un entorno
de CAD, se constituye como el “molde” necesario para
generar las entidades volumétricas, de tipo sólido, que Figura 3. Sección y alzados con secuencia estratigráfica. Dibujos de F.
posteriormente han sido categorizadas en el entorno de Pinto-Puerto 2013.

Madrid/Vitoria. ISSN-L: 1695-2731. https://doi.org/10.3989/arq.arqt.2021.001 ARQUEOLOGÍA DE LA ARQUITECTURA, 18, enero-diciembre 2021, e109

<!-- p. 6 -->

ESTRATEGIAS DE MODELADO PATRIMONIAL EN HBIM, APLICACIÓN A LA LECTURA ESTRATIGRÁFICA DEL MURO DE FACHADA
DEL CUADRANTE RENACENTISTA DE LA CATEDRAL DE SEVILLA 6

Figura 4. Vista axonométrica de la superficie mallada obtenida a partir de la CMD (izquierda). Vistas exterior e interior del modelo vectorial CAD
una vez editado (centro y derecha).

Figura 5. Proceso de edición en CAD. Sólido despiezado en entidades sólidas tridimensionales.

modelado BIM. Este último proceso se ha realizado en En este punto, el volumen sólido obtenido es único.
un software CAD convencional, en concreto Autodesk® Para poder avanzar en la caracterización constructiva
AutoCAD®. Este proceso de modelado se puede cate- pormenorizada, ha sido necesario dividir el sólido en
gorizar como “no paramétrico semiautomático” según piezas que se correspondían con las unidades constructila clasificación definida en Angulo-Fornos y Castella- vas básicas. Dadas las características singulares del caso
no-Román (2020: 6). de estudio se ha llevado la situación al extremo, de for-

Madrid/Vitoria. ISSN-L: 1695-2731. https://doi.org/10.3989/arq.arqt.2021.001 ARQUEOLOGÍA DE LA ARQUITECTURA, 18, enero-diciembre 2021, e109

<!-- p. 7 -->

7 Roque Angulo-Fornos, Manuel Castellano-Román y Francisco Pinto-Puerto

ma que esta unidad básica ha sido el sillar. Utilizando
las ortofotografías derivadas de la fotogrametría se ha
realizado una división sistemática del volumen sólido,
obteniendo cada uno de los sillares de la fábrica (Fig. 5).
Posteriormente, se ha generado el modelo HBIM,
importando el modelo vectorial, georreferenciándolo
y poniéndolo en relación con el modelo genérico de la
catedral antes citado y estableciendo los sistemas de referencias y el repertorio terminológico propios del elemento modelado. En este caso, el software utilizado ha
sido Autodesk® Revit®.
Así, las entidades CAD se han ido importando a la
plataforma BIM, asignándoles la categoría correspondiente. En este caso, se han importado dentro de un
ejemplar de familia de categoría “muro”, modelado
como componente in situ. Este ejemplar de muro forma parte del proyecto de Revit® que, adecuadamente
georreferenciado, compondrá, junto con otros modelos
parciales, el modelo federado del templo.
No se disponía de registros o documentos suficientes
como para deducir con precisión el espesor de las distintas hojas que componen la estructura de la fachada y
la existencia de piezas dispuestas a modo de llaves que,
atravesando la supuesta hoja interior de calicastrado,
unen las hojas exteriores de piedra. La falta de certeza
en este tipo de cuestiones, tanto geométricas o formales como de información asociada, no ha impedido la
posibilidad de modelar las entidades en base a hipótesis
bien fundadas y asignarles valores relativos a diversos
niveles de conocimiento ‒LOK‒ a través de parámetros
creados ex profeso en el modelo HBIM, en espera de
tener información certera que permita su actualización.
Dichos parámetros permiten la generación de imágenes
gráficas tematizadas, en cualquier tipo de proyección,
basadas en el LOK pormenorizado a la unidad básica
de modelado. Con este mismo criterio, para entender de
forma adecuada la configuración de esta fachada, y facilitar su interpretación, se han considerado también los
espacios que encierra, básicamente los conjuntos conocidos como la sacristía de los Cálices y el Patio de los
Oleos, modelados de forma más simplificada, adaptados
a un nivel de conocimiento inferior.

\3. RESULTADOS

La composición del ejemplar resultante se basa en la superposición de los distintos sólidos importados por separado en Figura 6. a) Nivel de detalle bajo. b) Nivel de detalle medio. c) Nivel
función de su nivel de detalle geométrico o formal, lo que de detalle alto.

Madrid/Vitoria. ISSN-L: 1695-2731. https://doi.org/10.3989/arq.arqt.2021.001 ARQUEOLOGÍA DE LA ARQUITECTURA, 18, enero-diciembre 2021, e109

<!-- p. 8 -->

ESTRATEGIAS DE MODELADO PATRIMONIAL EN HBIM, APLICACIÓN A LA LECTURA ESTRATIGRÁFICA DEL MURO DE FACHADA
DEL CUADRANTE RENACENTISTA DE LA CATEDRAL DE SEVILLA 8

permite, utilizando un solo objeto, generar distintas visuali- niveles de desarrollo contenidos en el modelo HBIM,
zaciones dirigidas a volcados gráficos de distinta escala de dos basados en la entidad sólida completa en dos niveles
representación, lo que implica además distintas posibilida- de detalle ‒diferenciados de cara a variaciones de escala
des en cuanto a la cantidad o profundidad de la informa- en representaciones gráficas‒ y otro a partir de las entición introducida. De esta manera, cada sólido importado se dades despiezadas. Estos niveles de desarrollo pueden
convierte en una pieza asociada a uno de los tres niveles de considerarse, a los efectos del uso patrimonial del BIM,
detalle: bajo, medio y alto. como Niveles de Conocimiento LOK.
El Nivel de Detalle Bajo presenta el sólido completo De esta forma, a la entidad constituida por modelos
del fragmento de muro sin elementos figurativos. Per- volumétricos completos ‒ejemplar de categoría muro‒
mite la producción de documentación gráfica a escala se han asociado parámetros que se refieren al elemento
de representación asimilable a un anteproyecto de arqui- como conjunto: identificación, información patrimonial
tectura de nueva planta —1/200 a 1/100—. Reproduce básica sobre la adscripción estilística y autoría principal,
fielmente la configuración geométrica y formal del ele- figuras de protección jurídica que le afectan, registro de
mento, resultado del proceso exhaustivo de modelado intervenciones y acciones de difusión relacionadas. Indescrito con anterioridad. Una vista en sección de este dependientemente de su detalle gráfico ‒que ha llegado
elemento se presenta como una única entidad masiva, a ser de nivel alto por necesidades de representación‒,
sin discriminación de sus capas materiales y despieces podemos considerar que se adscribe a un nivel de conoreales (Fig. 6a). cimiento LOK300.
El Nivel de Detalle Medio presenta el sólido com- En el caso del modelo despiezado de la fachada, cada
pleto del fragmento con inclusión de elementos figura- pieza es un objeto de registro y, por lo tanto, pueden asotivos. Responde a las mismas características del nivel ciarse parámetros relacionados con un mayor nivel de
anterior, con aportación de mayor información a nivel conocimiento, el requerido en este caso para gestionar la
gráfico. Permite obtener documentación gráfica a escala conservación preventiva del elemento. Así, a cada pieza
de representación asimilable a un proyecto básico de ar- se le asigna un identificador único y es caracterizada con
quitectura de nueva planta (Fig. 6b). parámetros de identificación, cronología, características
El Nivel de Detalle Alto presenta el conjunto de só- litológicas, lesiones, tratamientos y acciones como la
lidos resultado del despiece final desarrollado en el pro- sustitución, que genera una cronología específica. Podeceso de modelado. Permite la obtención de documenta- mos considerar, por tanto, que se adscribe a un nivel de
ción gráfica a escala de representación asimilable a un conocimiento LOK500.
proyecto de ejecución de arquitectura de nueva planta Si los valores definidos en los párrafos anteriores se
alcanzando desde proyecciones generales del objeto refieren a un LOK por elemento, siguiendo el criterio
hasta detalles constructivos. Además de reproducir fiel- adoptado por el grupo de trabajo, es preceptivo asignar
mente la configuración geométrica y formal del elemen- un LOK global tanto a los modelos parciales como al
to, incluye la representación de los despieces reales co- modelo federado. En este caso, el nivel de conocimiento
rrespondientes a los distintos estratos que conforman el asignado al modelo parcial que contiene el fragmento
muro (Fig. 6c). de fachada es LOK200 en base al estado de desarrollo
A cada una de las piezas del modelo se le han asocia- actual. En el caso del modelo federado del templo, dado
do campos de información que las identifican y sitúan en que el nivel actual de desarrollo consiste en un modelo
el tiempo en relación con las demás. Entre estos campos volumétrico básico con la única inserción de un modelo
de información se encuentran los datos relacionados con parcial, podemos adscribirlo a un LOK100.
la secuencia estratigráfica. La introducción efectiva de Las propiedades de gestión conferidas de forma aulos distintos conceptos de la estructura de información tomática a cada elemento, así como la asignación de los
en el modelo se ha llevado a cabo mediante la creación parámetros a las distintas entidades que conforman el
de parámetros personalizados ligados a los mismos den- modelo en función de su categoría y del sistema de relatro del software BIM. Dichos parámetros se han incluido ciones implementado, supone el salto cualitativo desde
dentro de una lista llamada de “parámetros compartidos” un simple modelo gráfico tridimensional ‒desarrollado
registrada en un archivo de texto susceptible de ser vin- en cualquier software de dibujo digital o CAD‒ a un verculable a cualquier otro proyecto parcial o federado. Se dadero modelo de información ‒BIM o HBIM en este
han asignado los parámetros requeridos en base a tres caso‒ capaz de ofrecer todas las ventajas de una base de

Madrid/Vitoria. ISSN-L: 1695-2731. https://doi.org/10.3989/arq.arqt.2021.001 ARQUEOLOGÍA DE LA ARQUITECTURA, 18, enero-diciembre 2021, e109

<!-- p. 9 -->

9 Roque Angulo-Fornos, Manuel Castellano-Román y Francisco Pinto-Puerto

Figura 7. Vista en alzado del modelo filtrado por el parámetro “material”.

Madrid/Vitoria. ISSN-L: 1695-2731. https://doi.org/10.3989/arq.arqt.2021.001 ARQUEOLOGÍA DE LA ARQUITECTURA, 18, enero-diciembre 2021, e109

<!-- p. 10 -->

ESTRATEGIAS DE MODELADO PATRIMONIAL EN HBIM, APLICACIÓN A LA LECTURA ESTRATIGRÁFICA DEL MURO DE FACHADA
DEL CUADRANTE RENACENTISTA DE LA CATEDRAL DE SEVILLA 10

Figura 8. Perspectivas del modelo filtradas por el parámetro “ID Fase” que gestiona la información relativa a la estratigrafía del objeto de estudio.

datos gráfica. Así, una vez asignados los valores corres- las relaciones entre elementos y su información asociada
pondientes dentro de cada parámetro a cada entidad, a desde nuevos enfoques difíciles de alcanzar sin contar
partir de la información previamente sistematizada, esta- con esta herramienta. En ese sentido, la implementación
mos en disposición de poder solicitar al sistema consul- en el modelo del parámetro “ID Fase” ha permitido la intas, filtrados de información o búsquedas condicionadas, corporación de la información relativa a la estratigrafía,
en forma de gráficos tematizados o listados alfanumé- de manera que a cada unidad básica de modelado se le ha
ricos, que nos ofrezcan nuevos puntos de partida a la asignado el valor correspondiente a la unidad estratigráhora de afrontar diversos tipos de análisis; o información fica a la que pertenece (Fig. 8). De esta forma, es posible
actualizada en tiempo real sobre determinados aspectos generar imágenes gráficas capaces de mostrar de forma
de la realidad patrimonial del bien (Fig. 7). paralela la evolución del fragmento estudiado y la confi-
Por otro lado, en el entorno BIM, los filtrados grá- guración espacial del interior del cuadrante renacentista.
ficos de información o consultas gráficas tematizadas
pueden ser personalizados en combinación con herramientas de configuración de las vistas en las cuales son 4.CONCLUSIONES
representadas. De esta manera, la visualización intencionada desde determinados puntos de vista ‒si considera- Se ha elaborado un modelo de información patrimonial
mos perspectivas axonométricas o cónicas‒ o utilizando HBIM de la fachada del cuadrante renacentista de la
proyecciones diédricas, permiten la contemplación de catedral de Sevilla con la capacidad de caracterizar la

Madrid/Vitoria. ISSN-L: 1695-2731. https://doi.org/10.3989/arq.arqt.2021.001 ARQUEOLOGÍA DE LA ARQUITECTURA, 18, enero-diciembre 2021, e109

<!-- p. 11 -->

11 Roque Angulo-Fornos, Manuel Castellano-Román y Francisco Pinto-Puerto

evolución constructiva de un elemento arquitectónico 6. BIBLIOGRAFÍA
complejo, incorporando la lectura estratigráfica tridimensional de los paramentos. Angulo-Fornos, R. y Castellano-Román, M. 2020: “HBIM as Support of Pre-
El modelo gráfico se basa en una captura métrica di- ventive Conservation Actions in Heritage Architecture. Experience of the Renaissance Quadrant Façade of the Cathedral of Seville”, Applied Sciencgital fotogramétrica que es analizada e interpretada con es, 10 (7), 2428. https://doi.org/10.3390/app10072428
las claves metodológicas del levantamiento arquitectó- Arévalo-Rodríguez, F. 2011: “El amurallamiento externo en la mezquita alja-
ma de la Sevilla almohade: una hipótesis a partir de una muralla fosilizada,
nico. El modelo surge, en consecuencia, de una propues- de las excavaciones arqueológicas y del análisis gráfico del parcelario”,
ta de interpretación de los datos métricos fundada sobre en La catedral sin la catedral, pp. 7-56. Aula Hernán Ruiz, Catedral de
el conocimiento arqueológico y arquitectónico del ele- Sevilla, Sevilla.
Castellano-Román, M. y Pinto-Puerto, F. 2019: “Dimensions and Levels of
mento estudiado, diferenciando aquellos elementos cuya Knowledge in Heritage Building Information Modelling, HBIM: The moddefinición surge de un conocimiento cierto, de aquellos el of the Charterhouse of Jerez (Cádiz, Spain)”, Digital Applications in
modelados según hipótesis pendientes de confirmación. Archaeology and Cultural Heritage, 14, e00110. https://doi.org/10.1016/j. daach.2019.e00110
Se establecen tres niveles de desarrollo del modelo Guerrero Vega, J. M. 2010: “El informe de 1513 de Alonso Rodríguez”, en
del elemento muro, como evolución de un primer nivel A. Jiménez Martín (ed.), La catedral después de Carlín, pp. 31-74. Aula
conceptual de la catedral, con el que estaría federado: Hernán Ruiz, Catedral de Sevilla, Sevilla. Pinto-Puerto, F. 2006: “Fábrica y forma del templo gótico”, en A. Jimé-
dos que, diferenciados en dos niveles de detalle a nivel nez-Martín (coord.), La catedral gótica de Sevilla: Fundación y fábrica de
formal, abarcan todo el elemento estudiado en una úni- la obra nueva, pp. 211-295. Universidad de Sevilla, Sevilla.
Pinto-Puerto, F. 2013: “La Sacristía de los Cálices. Aportaciones desde el anáca entidad y otro, derivado de un análisis arquitectónico lisis de sus fábricas y los sistemas de control formal”, en F. Guerra-Librero
y arqueológico existente, donde se ha delimitado cada Fernández y A. Jiménez Martín (eds.), La Catedral entre 1434 y 1517 hisunidad constructiva del conjunto. Los modelos de en- toria y conservación, pp. 163-235. Aula Hernán Ruiz, Catedral de Sevilla,
Sevilla.
tidad única incorporan los parámetros de información Rodríguez Estévez, J. C. 1998: Los canteros de la Catedral de Sevilla: del
relativos al conjunto del elemento. Esta información se Gótico al Renacimiento. Diputación de Sevilla, Sevilla.
completa con los parámetros de cada pieza del modelo Rua, H. y Gil, A. 2014: “Automation in heritage – Parametric and associa- tive design strategies to model inaccessible monuments: The case-study
despiezado, donde se incorporan los parámetros asocia- of eighteenth-century Lisbon Águas Livres Aqueduct”, Digital Applicados a las acciones de conservación preventiva, permi- tions in Archaeology and Cultural Heritage, 1 (3), pp. 82-91. https://doi.
tiendo numerosas visualizaciones que mejoran la com- org/10.1016/j.daach.2014.06.002 Tabales-Rodríguez, M. Á. y Jiménez Sancho, Á. 2002: “La cilla de la catedral
prensión de la complejidad espacial y constructiva, y, y el sector meridional de la mezquita aljama de Sevilla”, en Magna Hispapor otro lado, quedan registrada la información asociada lensis (I): Recuperación de la Aljama Almohade, pp. 229-296. Aula Hernán
al modelo. Ruiz, Cabildo Metropolitano, Sevilla

\5. AGRADECIMIENTOS

Los autores agradecen la colaboración del cabildo de la
catedral de Sevilla y de la empresa Artyco S.L. por los
medios puestos para el registro pormenorizado de la fachada durante las últimas obras de intervención.

Madrid/Vitoria. ISSN-L: 1695-2731. https://doi.org/10.3989/arq.arqt.2021.001 ARQUEOLOGÍA DE LA ARQUITECTURA, 18, enero-diciembre 2021, e109
