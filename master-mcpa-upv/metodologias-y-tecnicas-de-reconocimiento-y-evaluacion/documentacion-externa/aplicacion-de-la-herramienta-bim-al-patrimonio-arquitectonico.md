---
type: libro
title: "Aplicación de la herramienta BIM al patrimonio arquitectónico"
author: ""
categoria: "Metodologías y técnicas de reconocimiento y evaluación"
paginas: 132
extraccion: "texto"
fuente: "local:D:/UPV/MCPA/Asignaturas/Metodologías y técnicas de reconocimiento y evaluación/Documentación externa/Aplicación de la herramienta BIM al patrimonio arquitectónico.pdf"
convertido: 2026-10-16
---

# Aplicación de la herramienta BIM al patrimonio arquitectónico

> Texto extraído de `Metodologías y técnicas de reconocimiento y evaluación\Documentación externa\Aplicación de la herramienta BIM al patrimonio arquitectónico.pdf` (132 páginas, texto). El PDF original está en el disco D: (UPV\MCPA\Asignaturas); `<!-- p. N -->` marca el inicio de cada página.

<!-- p. 1 -->

Aplicación de la herramienta BIM al patrimonio arquitectónico.
El Convento de Santa Clara de la Columna en Belalcázar, Córdoba.
Parametrización de la habitabilidad.

Celia Chacón Carretón | Autora

Trabajo Fin de Grado | Tribunal G
Cristina Soriano Cuesta | Tutora

Curso 2020-2021
Escuela Técnica Superior de Arquitectura | Universidad de Sevilla

<!-- p. 2 -->

2 Celia Chacón Carretón

<!-- p. 3 -->

TFG | Aplicación de la herramienta BIM al patrimonio arquitectónico 3

<!-- p. 4 -->

4 Celia Chacón Carretón

<!-- p. 5 -->

Aplicación de la herramienta BIM al patrimonio arquitectónico.
El Convento de Santa Clara de la Columna en Belalcázar, Córdoba.
Parametrización de la habitabilidad.

Celia Chacón Carretón | Autora

Trabajo Fin de Grado | Tribunal G
Cristina Soriano Cuesta | Tutora

Curso 2020-2021
Escuela Técnica Superior de Arquitectura | Universidad de Sevilla

TFG | Aplicación de la herramienta BIM al patrimonio arquitectónico 5

<!-- p. 6 -->

6 Celia Chacón Carretón

<!-- p. 7 -->

“Actuemos como mediadores desvelando y construyendo soportes en los que la vida tenga lugar [...]”

José Ramón Moreno Pérez y Marta García de Casasola Gómez, 2017

TFG | Aplicación de la herramienta BIM al patrimonio arquitectónico 7

<!-- p. 8 -->

8 Celia Chacón Carretón

<!-- p. 9 -->

AGRADECIMIENTOS

Primero de todo, agradecer a mis padres por inculcarme el valor hacia las cosas hechas con cariño. Por su
apoyo constante y por extenderme su mano a lo largo de toda la carrera.

A Cristina Soriano Cuesta, por ser mi tutora y consejera en este camino.
A Pablo M. Millán Millán, especialmente por despertar en mí la curiosidad por el patrimonio e invitarme a
descubrir la compleja realidad del Convento de Santa Clara de la Columna.

Por último, dar las gracias a todos los amigos que me han acompañado. En especial a Marina, quien siempre
ha querido escuchar lo que tenía que decir.

TFG | Aplicación de la herramienta BIM al patrimonio arquitectónico 9

<!-- p. 10 -->

10 Celia Chacón Carretón

<!-- p. 11 -->

ACRÓNIMOS

AEC | Architecture, Engineering & Construction (Arquitectura, Ingeniería y Construcción)
BIC | Bien de Interés Cultural
BIM | Building Information Modelling (Modelado de Información de la Edificación)
CAD | Computer Aided System (Diseño Asistido por Ordenador)
CTE | Código Técnico de la Edificación
EGA | Expresión Gráfica Arquitectónica
HBIM | Heritage Building Information Modelling (Modelado de Información de la Edificación Patrimonial)
HBIR | Heritage Building Information Repository (Repositorio de Información de la Edificación Patrimonial)
HBOM | Heritage Building Object Model (Modelado de Objetos de la Edificación Patrimonial)
IAPH | Instituto Andaluz de Patrimonio Histórico
ICOMOS | Consejo Internacional de Monumentos y Sitios
IFC | Industry Foundation Classes
IPCE | Instituto del Patrimonio Cultural de España
LOD | Level of Development (Nivel de Desarrollo)
LOK | Level of Knowledge (Nivel de Conocimiento)
LPHA | Ley de Patrimonio Histórico Andaluz
LPHE | Ley de Patrimonio Histórico Español
MEP | Mechanical, Electrical and Plumbing (Mecánicas, Eléctricas e Hidrosanitarias)
MIP | Modelado de Información Patrimonial
NURBS | Non-Uniform Rational B-Splines (B-Splines Racionales No Uniformes)
ONU | Organización de las Naciones Unidas
SIG | Sistema de Información Geográfica
SIP | Sistema de Información Patrimonial
TLS | Terrestrial Laser Scanning (Escáner Láser Terrestre)
UNESCO | Organización de las Naciones Unidas para la Educación, la Ciencia y la Cultura
URL | Uniform Resource Locator (Localizador de Recursos Uniforme)

TFG | Aplicación de la herramienta BIM al patrimonio arquitectónico 11

<!-- p. 12 -->

CONTENIDOS

Abstract | Key words ..........................................................................................................................................14
Resumen | Palabras clave .................................................................................................................................15

Capítulo 0 | Introducción
0.1 Introducción........................................................................................................................................... 18
0.2 Motivación..............................................................................................................................................19
0.3 Objetivos................................................................................................................................................19
0.4 Método...................................................................................................................................................20

Capítulo 1 | Investigación
1.1 Estado de la cuestión | La herramienta BIM en levantamiento patrimonial ......................................... 24
1.2 Casos de estudio ................................................................................................................................. 30
1.2.1 Justificación de los casos de estudio .......................................................................................... 31
1.2.2 Casos .......................................................................................................................................... 36
01 | La Cartuja de Jerez .................................................................. 40
02 | Conjunto arqueológico Itálica ................................................... 42
03 | Casa de Hylas ......................................................................... 44
04 | Fachada del cuadrante renacentista ....................................... 46
05 | Iglesia San Juan del Hospital .................................................. 48
06 | Basilica di Santa Maria de Collegamaggio .............................. 50
07 | Chiesa di Santa Maria ............................................................. 52
08 | Real Colegiata de San Isidoro ................................................. 54
09 | Complejo medieval Sant’Apollinare ........................................ 56
10 | La Antigua Cárcel de la Real Fábrica de Tabacos .................. 58
1.3 Los factores tutela y resiliencia en el patrimonio arquitectónico.......................................................... 62
1.4 Parámetros ......................................................................................................................................... 66
1.4.1 La parametrización en el modelo BIM .................................................................................................... 66
1.4.2 La parametrización de la habitabilidad ....................................................................................... 70

12 Celia Chacón Carretón

<!-- p. 13 -->

Capítulo 2 | Experiencia
2.1 Caso de estudio | El Convento de Santa Clara de la Columna, Belalcázar ........................................ 80
2.2 Levantamiento ..................................................................................................................................... 86
2.2.1 | Recopilación y estudio de las fuentes planimétricas
2.2.2 | Criterios generales del modelado gráfico
2.2.3 | Creación del proyecto central y proyectos vinculados
2.2.4 | Ubicación y orientación del proyecto
2.2.5 | Creación de las fases históricas
2.2.6 | Modelado y definición de los sistemas constructivos
2.2.7 | Modelado y definición de los espacios
2.3 Parametrización .................................................................................................................................. 102
2.3.1 | Creación de parámetros
2.3.2 | Parámetros de habitabilidad
2.3.3 | Visualización de parámetros
2.3.4 | Tablas de planificación
2.3.5 | Relación de parámetros, elementos y espacios

Capítulo 3 | Conclusiones
3.1 Conclusiones..................................................................................................................................... 108
3.2 Futuras líneas de desarrollo................................................................................................................ 124

Bibliografía.................................................................................................................................................................. 128

TFG | Aplicación de la herramienta BIM al patrimonio arquitectónico 13

<!-- p. 14 -->

ABSTRACT

This research addresses the issue of architectural heritage survey through the use of new emerging graphic
technologies for information management, such as the BIM (Building Information Modelling) tool, with the aim of reflecting
on the usefulness that this type of technology can bring to the management of architectural heritage and help its possible
objectification in certain aspects.

To this end, based on the study of the state of the art as a fundamental part of this research, a selection of case
studies is made: 10 heritage assets on which some kind of research has been carried out based on a survey with BIM
tools. These cases are documented and critically analyzed, finally developing a catalog of summary cards for each case,
in order to facilitate the approach to the subject and its direct application to the heritage survey in the form of HBIM
(Heritage Building Information Modelling) model.

From the study carried out, as a direct application of the knowledge acquired in the previous research, the survey of
a BIC is carried out as an experience: the Convent of Santa Clara de la Columna in Belalcázar (Córdoba), using the BIM tool.
The survey is carried out reflecting and developing the entire process, with special emphasis on the parameterization involved.
In this sense, the creation and implementation of new parameters in relation to the habitability of the spaces, something that
can be essential when it comes to intervene, enhance, and provide use to the architectural heritage, is provided as a novelty.

KEY WORDS

BIM - heritage - parameters - convent - habitability

14 Celia Chacón Carretón

<!-- p. 15 -->

RESUMEN

Esta investigación aborda la cuestión del levantamiento del patrimonio arquitectónico mediante la utilización
de nuevas tecnologías gráficas emergentes para la gestión de información, como lo es la herramienta BIM (Building
Information Modelling), con el objeto de reflexionar sobre la utilidad que este tipo de tecnologías pueden aportar a la
gestión del patrimonio arquitectónico y ayudar a su posible objetivación en ciertos aspectos.

Para ello, a partir del estudio del estado de la cuestión como parte fundamental de esta investigación, se realiza
una selección de casos de estudio: 10 bienes patrimoniales sobre los cuales se ha realizado algún tipo de investigación
a partir de un levantamiento con herramientas BIM. Estos casos se documentan y analizan críticamente, desarrollando
finalmente un catálogo de fichas resumen de cada caso, con el fin de facilitar el acercamiento a la materia y su
aplicación directa al levantamiento patrimonial en forma de modelo HBIM (Heritage Building Information Modelling).

A partir del estudio realizado, como aplicación directa del conocimiento adquirido en la investigación previa , se
lleva a cabo como experiencia el levantamiento de un BIC: el Convento de Santa Clara de la Columna en Belalcázar
(Córdoba), utilizando la herramienta BIM. El levantamiento se lleva a cabo reflejando y desarrollando el proceso
completo, incidiendo especialmente en la parametrización que conlleva. En este sentido, se aporta como novedad la
creación e implementación de nuevos parámetros en relación con el factor de la habitabilidad de los espacios, algo que
puede resultar fundamental cuando se trata de intervenir, poner en valor, y dotar de uso al patrimonio arquitectónico.

PALABRAS CLAVE

BIM - patrimonio - parámetros - convento - habitabilidad

TFG | Aplicación de la herramienta BIM al patrimonio arquitectónico 15

<!-- p. 16 -->

16 Celia Chacón Carretón

<!-- p. 17 -->

Capítulo 0 | Introducción

TFG | Aplicación de la herramienta BIM al patrimonio arquitectónico 17

<!-- p. 18 -->

0.1 | Introducción

Fig. 1 | Grabado monja clarisa y utensilios de cocina (Anónimo, s. XVII)

El BIM, como propiamente indica, consiste en el Modelado de Información de la Edificación, es decir, un
proceso de representación gráfica de todos los elementos que componen una edificación, en los que la geometría unida
a la información no geométrica configuran un único documento de trabajo. Este proceso se complejiza cuando se trata
del patrimonio arquitectónico.

18 Celia Chacón Carretón

<!-- p. 19 -->

0.2 | Motivación

Esta investigación surge a partir de la inquietud personal por la gestión del patrimonio en relación con las
tecnologías actuales. El ámbito extensivo que se propone pretende poner en relación aspectos de expresión gráfica,
valoración cultural y cualidades habitacionales, buscando profundizar en la relación que existe entre todos los agentes
partícipes y la tutela del patrimonio arquitectónico.

El Patrimonio Histórico de España, siendo el tercer país del mundo con más sitios declarados como Patrimonio Cultural
de la Humanidad por la UNESCO, está integrado por bienes y objetos de interés artístico, histórico, paleontológico,
arqueológico, etnográfico, científico y técnico. También forman parte del Patrimonio Español los documentos
patrimoniales y la bibliografía de interés artístico o antropológico, así como el patrimonio inmaterial (Ministerio de la
Presidencia y del Territorio, 25 de junio de 1985). Al abordar el problema del rápido deterioro y la alta vulnerabilidad
de este amplio patrimonio, el Instituto del Patrimonio Cultural de España, lo achaca principalmente a la carencia de
documentación que trascienda más allá del tipo documental, y la falta de uso de muchos inmuebles, lo que incide tanto
en la conservación activa (respecto a intervenciones que favorezcan la reactivación del patrimonio más allá de su
mantenimiento), la desvinculación social y la difusión cultural.

Muchos casos de estudio revisados en esta investigación evidencian las aportaciones que introduce el modelo
BIM a la tutela integral patrimonial, no sólo por su resultado sino por la experiencia del proceso de levantamiento. La
complejidad en la realidad patrimonial en sí y su gestión conllevan la necesidad de nuevos métodos que incluyan una
visión más transversal, respecto a las disciplinas y a los temas afectados en el comportamiento y contexto del inmueble.

Es en el proceso de investigación durante la recopilación de los distintos casos de estudio cuando se despierta
en mí la incertidumbre de acuerdo al factor social. La tutela se define en su última instancia como difusión del valor
cultural. Es por esto que acaba siendo objeto fundamental ahondar en el conocimiento de la realidad de la escisión
entre la vivienda y el patrimonio teniendo presente ambos valores que a la vez son condicionantes recíprocos: la
protección y la habitabilidad. Según el Código de la Vivienda de Andalucía uno de los objetos de la rehabilitación urbana
es mejorar el conocimiento de la realidad de la vivienda y el fomento de la arquitectura en Andalucía manteniendo
la actividad investigadora sobre los temas anteriores y la rehabilitación del patrimonio arquitectónico, histórico y
antropológico andaluz, englobando desde su catalogación y conservación, hasta su puesta en valor y su reutilización.
Incide de igual manera en las nuevas perspectivas conceptuales que den respuesta arquitectónica a las necesidades
de transformación y crecimiento.

0.3 | Objetivos

General | El objetivo general de esta investigación es documentar y reflexionar sobre las ventajas del modelo BIM
en la representación del patrimonio arquitectónico, para su experiencia práctica en el caso de estudio el Convento de
Santa Clara de la Columna en Belalcázar, Córdoba, implementando parámetros en relación con la habitabilidad de los
espacios.

Especifico | Estudiar en profundidad la herramienta BIM
\| Analizar los métodos de aplicación de la herramienta BIM al patrimonio arquitectónico
\| Investigar casos de estudio de la implementación de la herramienta BIM aplicada al patrimonio
\| Documentar dichos casos de manera objetiva y concisa parara facilitar el acercamiento a esta materia

\| Realizar una valoración histórica y un análisis arquitectónico del caso de estudio
\| Aplicar un método de levantamiento que responda al conocimiento recogido en la investigación
\| Ejecutar el levantamiento del caso de estudio mediante la aplicación de la herramienta BIM
\| Analizar la respuesta de la herramienta BIM

TFG | Aplicación de la herramienta BIM al patrimonio arquitectónico 19

<!-- p. 20 -->

\| Definir y recoger parámetros patrimoniales que influyan en la tutela patrimonial del inmueble
\| Definir y recoger parámetros habitacionales que influyan en la habitabilidad del inmueble
\| Analizar la herramienta BIM en su capacidad de recoger dichos parámetros
\| Reconocer las relaciones provocadas por la coexistencia de dichos parámetros

\| Establecer un método para la aplicación de dichos parámetros en el modelado HBIM
\| Evaluar el resultado de recoger dichos parámetros de acuerdo a la tutela

\| Plantear estrategias de gestión para ambas realidades coexistentes
\| Poner en valor ambas realidades coexistentes que favorezca su difusión cultural de acuerdo a la tutela
\| Establecer una discusión basada en la objetivación realizada de la conviviencia de estas realidades

0.4 | Método

La investigación parte de una metodología analítico deductiva, cerrando el proceso investigador con un caso
práctico que contraste los resultados planteados. Se plantea como una aportación al problema de la tutela del patrimonio
arquitectónico.

Hito 1 | Investigación
Estudio/análisis de la herramienta BIM. Debido a la especificidad de la aplicación sobre intervenciones contemporáneas en
patrimonio, se requerirá un profundo análisis sobre la incorporación de datos al sistema BIM procedentes de áreas afines.

Estudio/análisis de intervenciones contemporáneas en patrimonio llevadas a cabo mediante la herramienta BIM. Esta
fase analítica cerrará este momento de la investigación con un directorio de proyectos contemporáneos en patrimonio
desarrollados en BIM definidos de manera pertinente.

Hito 2 | Experiencia
Acercamiento y documentación al caso de estudio del Convento de Santa Clara de la Columna en Belalcázar (España)
respecto a sus valores patrimoniales.

Aplicación directa de investigación, sobre un bien patrimonial concreto. Se desarrollará todo el soporte BIM sobre este
inmueble histórico, para desde ahí poder extraer conclusiones sobre la experiencia. La investigación partirá de un
levantamiento exhaustivo, para a partir de ahí comenzar a incorporar parñametros de los extraídos en las experiencias
anteriormente analizadas.

Implementación de los parámetros de habitabilidad desarrollados

Hito 3 | Conclusiones
Creación de la documentación que recoja la experiencia de manera gráfica incluyendo el modelo, planimetría
complementaria, imágenes, tablas de datos...

Reflexión y desarrollo de conclusiones para la valoración de la investigación y su aplicación en la tutela respecto al
conocimiento, conservación, intervención y difusión del inmueble patrimonial.

20 Celia Chacón Carretón

<!-- p. 21 -->

TFG | Aplicación de la herramienta BIM al patrimonio arquitectónico 21

<!-- p. 22 -->

22 Celia Chacón Carretón

<!-- p. 23 -->

Capítulo 1 | Investigación

TFG | Aplicación de la herramienta BIM al patrimonio arquitectónico 23

<!-- p. 24 -->

1.1 | Estado de la cuestión | La herramienta BIM en el levantamiento patrimonial

La tutela del patrimonio arquitectónico posee una dimensión técnica, ya que los edificios históricos deben
conservarse físicamente, y una dimensión social, ya que el patrimonio debe difundirse en la sociedad para garantizar
su protección (Naeyer et al., 2000). Según el World Heritage Committee e ICOMOS (1994), la responsabilidad tutelar
recae en la comunidad cultural generada y por tanto la que posteriormente lo cuida. El abordaje de este tema a día
de hoy trasciende el marco patrimonial más tradicional, perteneciendo a un foro de investigación muy reciente y en
constante evolución con repercusión diaria en ámbitos que trascienden la arquitectura, la era de la información y la
cultura visual (Català Domènech, 2005).

De acuerdo a la Carta del Rilievo (Jiménez Martín y Pinto Puerto, 2003) en la cual el levantamiento es
declarado fundamental en el año 2000, el conocimiento y digitalización de éste se aborda desde el proyecto de
protección patrimonial de mano del mundo de la expresión gráfica, donde el dibujo produce un proceso que no debe
únicamente valorarse por su resultado, sino como herramienta y método a la hora de registrar pensamientos que se
desarrollan en la transversalidad de hechos, en este caso arquitectónicos. La revisión realizada a consecuencia de
esto por Angulo Fornos (2020) desde el marco teórico conceptual y experimental del proceso de levantamiento del
patrimonio, busca canalizar la información de manera analítica para su filtración, ordenación y producción de nueva.
Los múltiples recursos que ha ofrecido y ofrece la representación gráfica permite múltiples traslaciones entre la obra,
en su arquitectura y materialización (mueble o inmueble) y el pensamiento a través de la intencionalidad del modelo, la

24 Celia Chacón Carretón

<!-- p. 25 -->

selección de la información y la diversa y nueva dimensión recogida de los elementos (González Pérez, 2018). Y esto
se aplica desde el dibujo a mano hasta las realidades más complejas.

La herramienta BIM (Building Information Modeling) se define como un sistema de representación gráfica digital
compartida de las características físicas y funcionales de cualquier objeto construido que constituye una base fiable
para la toma de decisiones (Norma I. S.O., 2010). Los procesos BIM ya están establecidos para los edificios nuevos,
sin embargo no ocurre de esta manera en la mayoría de los edificios existentes que aún no se mantienen, reforman
o deconstruyen con BIM (Volk et al., 2014), a pesar de que el uso principal de la herramienta se base en la cualidad
más extensiva de integrar y organizar todos los factores en un único archivo, cuyo uso eficaz permite la definición de
la evolución arquitectónica desde la fase de ideación, su desarrollo y su ejecución hasta el final de su ciclo de vida.
Superado el nivel 2D, el BIM destaca entre otros soportes por traspasar el 3D geométrico y constructivo asociando otras
dimensiones: 4D para incluir secuencias temporales, 5D en referencias a la incorporación de costes, 6D para indicar la
asociación a determinados comportamientos ambientales y 7D finalmente para recoger los programas de mantenimiento,
ver Fig.2. La adición de información técnica cualitativa y cuantitativa de los objetos que recoge en el modelo y sus
relaciones que se establecen dentro y fuera a través de enlaces a documentos externos, caracteriza la potencialidad
de su uso de acuerdo a los sistemas de información patrimonial que ya recogen documentos (Logothethis, 2015).

La complejidad que pueden llegar a alcanzar estos modelos supone la demanda de una denominación que
la recoja. Level of Detail, Level of Definition, Level of Development o Level of Information son los más comunes de
acuerdo al nivel de precisión y fiabilidad asociado a un archivo BIM, siendo esta definición interpretada de manera
múltiple, se subdivide en secuencias de nivel de desarrollo: LOD100, LOD200, LOD300, LOD400 Y LOD500 según el
American Institute of Architects (AIA, 2013).

BIM | DIMENSIONS & LOD/K | HBIM

Fig. 2 | Las dimensiones de la información BIM y su traslación a HBIM (Castellano Román, 2017)

TFG | Aplicación de la herramienta BIM al patrimonio arquitectónico 25

<!-- p. 26 -->

Esta jerarquía que permite clasificar rápidamente estas realidades gráficas se traduce al mundo patrimonial
como Level of Knowledge que sugiere desde la perspectiva contemporánea el nivel de conocimiento que se posee y se
recoge en el modelo. Este paralelismo se produce de manera indirecta, ya que la exactitud gráfica viene determinada
por la documentación y su discriminación en el proceso de levantamiento según valor significativo en la tutela. De
igual manera el LOK depende de la información disponible y posteriormente de su reflejo en el modelado, siempre
manteniendo la exactitud gráfica. La intencionalidad de los niveles propuestos LOK100, LOK200, LOK300, LOK400,
LOK500 siguen definiendo gradaciones que según su superación ascendente perpetúan la profundidad de la definición
y el conocimiento formal e histórico del inmueble (Castellano Román y Pinto Puerto, 2019).

A pesar de la rápida evolución y los estándares BIM, surgen oportunidades de investigación desafiantes de la
automatización de procesos y la adaptación de BIM a los requisitos de los edificios existentes (Volk et al., 2014). La
razón que sostiene que muchos edificios no se gestionen o mantengan correctamente son: falta de conocimientos,
experiencia y recursos,y dependencia de otras partes interesadas (Edwards, 2017). En recientes investigaciones
se ha incidido en la metodología de la herramienta más allá del resultado, de esta manera el objetivo se entiende
como el proceso de comprensión del levantamiento, y por tanto del bien patrimonial en sí incluyendo cualidades como
la potencialidad del sistema BIM como gestor de investigaciones, actividades de conservación y su difusión en el
sentido divulgativo. Por ejemplo en uno de los casos que se estudiarán a continuación, la comprensión y aclaración
de la compleja realidad patrimonial de espacios como la Cartuja de Jerez (Castellano Román, 2017) respecto a su
identificación paisajística, histórica y estructural ha permitido no solo el registro contemporáneo de este inmueble
sino también la obtención de información distintiva de aportación transversal. En este contexto, el propio investigador
realiza una valoración positiva del método, en relación a una caracterización general que no busca la perfección total
del modelo sino la posibilidad del enriquecimiento progresivo.

Murphy et al. (2009) definieron el HBIM, nomenclatura más extendida en publicaciones académicas que hace
referencia a la aplicación de softwares BIM en el patrimonio cultural (heritage), como un nuevo sistema de modelado
de estructuras históricas que crea modelos completos en 2D y 3D, que incluyen detalles detrás de la superficie de los
objetos relativos a sus métodos de construcción y composición de los materiales. Según Volk el al. (2014) HBIM es la
base de datos dinámica de un edificio histórico con una coordinación mejorada de los documentos de construcción,
en la que se estructuran y documentan la geometría, las relaciones espaciales, la información geográfica y otras
cantidades o propiedades de los componentes del edificio.

La transición entre la recogida de datos y su expresión gráfica, siendo consecuencia del proceso de captura
digital, diverge en diversos protocolos. La fotogrametría es uno de los métodos que más avances ha experimentado
gracias a la reciente aparición (derivados de otros sistema de captación) de obtención de datos dimensionales de
morfología superficial, como el escáner 3D o el propio software de fotogrametría avanzada que recoge colores y
texturas. Todos se fundamentan en la coordinación entre la toma de fotografías y la traducción a información
geométrica mediante restitución o rectificación (Tucci et al., 2017). Las aplicaciones informáticas traducen las nubes
de puntos generadas en superficies de gran fidelidad, pero Angulo Fornos (2020) indica su carencia de información
acerca de su masividad, aspecto fundamental en estructuras históricas. Es por ello que una postura recurrente es
realizar un tratamiento manual mediante clasificación, jerarquización y simplificación, que permitan centrar el modelo
en las referencias más intrínsecas y representativas, frente a acercamientos denominados semiautomáticos en los que
prevalece la generación íntegra a través de algoritmos que se aplican de manera global, siempre manteniendo la fase
de reflexión previa para la discretización y revisión de ciertos aspectos frente a los directamente automáticos.

26 Celia Chacón Carretón

<!-- p. 27 -->

Apollonio, Gaiani y Sun (2016) destacan que los aspectos que merece la pena investigar son la adaptación
de la metodología BIM a las características específicas de la arquitectura histórica, el nivel de conocimiento que es
posible incorporar en un HBIM y las estructuras semánticas disponibles para el patrimonio histórico. Algunos autores se
centran principalmente en el análisis del edificio histórico y en la generación de conocimiento que debe incorporar una
réplica digital, considerando la precisión geométrica como una característica del modelo que puede evolucionar según
su nivel de conocimiento y desarrollo (Castellano Román y Pinto Puerto, 2019). De igual forma otros autores abordan
el desarrollo de una biblioteca específica de elementos arquitectónicos históricos con la definición de Heritage Building
Object Model (HBOM) (Santagati y Lo Turco, 2016).

Murphy et al. (2009) comenzaron a estudiar la forma de adaptar los objetos paramétricos a la nube de puntos.
Estudios posteriores mostraron la necesidad de combinar los modelos 3D en un archivo SIG 3D para mejorar la
orientación de la información semántica. Hay muchas investigaciones que se centran en la solución de este problema,
sin embargo, todavía no han podido encontrar una propuesta automática que resuelva la limitación que supone que
la mayoría de trabajos en SIG, más allá de recoger y ordenar contenidos, no dieran la posibilidad de actualizar sus
entidades hacia una dirección evolutiva arquitectónica que permitiera la integración de datos complementarios de
morfología, dimensiones, estructura… La concepción del BIM hereditaria del CAD si ofrece estas cualidades y no se
limita a posicionar datos y superficies, es por ello que actualmente se favorece la conexión entre distintas plataformas
SIG-BIM para importar datos para su modelo y visualización (Angulo Fornos, 2020).

En consecuencia, es esencial reflexionar sobre el nivel de detalle y la simplificación de los modelos útiles
para los proyectos de conservación (Garagnani y Manferdini, 2013), ambos aspectos relacionados con la posibilidad
real de modificar los parámetros de la forma de los elementos arquitectónicos, en particular de los objetos históricos
que a menudo son irregulares, de manera isotrópica. En lo relativo a HBIM se ilustra cómo se puede construir una
biblioteca de objetos paramétricos interactivos supeditados a la variabilidad de siempre un número relativamente bajo
de parámetros o no paramétricos, principalmente a partir de la dimensión histórica dada por los libros de patrones
arquitectónicos. Los modelos paramétricos están relacionados con los datos recogidos en una base de datos y cada
cambio de un parámetro provoca un cambio en la forma de los elementos (Boeykens, 2012); pero, por el momento, no
existe una biblioteca colaborativa para los elementos vinculados a arquitectura patrimonial. Las familias se modelan y
parametrizan desde el mismo entorno que el BIM no aplicado al patrimonio.

Fig. 3 | HBIM process (Santoni et al., 2021)

TFG | Aplicación de la herramienta BIM al patrimonio arquitectónico 27

<!-- p. 28 -->

Por consiguiente a los autores les parece que el alto potencial en la generación de bibliotecas BIM es el de
compartir, de una manera más fácil, herramientas y muestras de funcionalidades, con el fin de apoyar diferentes
análisis de otros casos específicos, evitando el riesgo de un uso acrítico de objetos sin relación con las formas reales.
La atención a la estricta conexión entre la geometría y las tecnologías constructivas es la única forma de garantizar
un modelo 3D real del patrimonio construido, es decir, el entendimiento del inmueble como un proceso que hay que
reproducir conceptualmente en su levantamiento (Carta del Rilievo, 2000). Debido a la complejidad en la generación
de objetos, por ejemplo una bóveda, comenzando por el levantamiento preciso con escáner láser hasta la texturización
3D, la generación de objetos basados en parámetros puede representar un apoyo válido en el modelado de objetos
similares. Además, una biblioteca de objetos espacialmente referidos puede apoyar, en el futuro, el ábaco de objetos y
una historia geográfica de las habilidades y técnicas a través de las regiones europeas, que ahora son sustancialmente
desconocidas para el público o para los especialistas, debido a la falta de relaciones entre ellos.

La literatura que se recoge de los casos desarrollados mediante la implementación contemporánea
del HBIM también advierten de la subdivisión interna que ya se está efectuando en el campo. La divergencia de
la procedencia y comportamiento formal de los inmuebles se entiende debido al campo cada vez más extenso
de la propia aplicación BIM. Los inmuebles acumulan alto número de casos motivados en cierta medida por la
complejidad de su comportamiento y su necesidad de planes directores que los ampare y describan en su tutela
integral como es el caso del Conjunto Arqueológico de Itálica cuyo objetivo investigador (Castellano Román y Pinto
Puerto, 2011) se justificaba en la necesidad de creación de un documento exhaustivo y flexible que codificara la
realidad patrimonial y a su vez permitiese la adición de inmuebles incluidos en la traza de la base cartográfica.

Otra de las vertientes de este foro de discusión es la gestión de la información ahora recogida y generada por
el modelo BIM. El modo de conocimiento que permite el acercamiento de múltiples agentes (arqueólogos, historiadores,
geógrafos…) a realidades patrimoniales está sujeto al fenómeno digital que trasciende todas las disciplinas (Castellano
Román, 2017). Jordán Palomar (2019) revisa la literatura de protocolos propuesto sobre el uso del BIM centrando
su objeto de estudio en el comportamiento del trabajo colaborativo. Las necesidades de las partes interesadas se
manifiestan más allá de los profesionales de la industria AEC (Architecture, Engineering & Construction) estando los
estudios del HBIM focalizados en el punto de vista gráfico conteniendo la participación fluida de otros profesionales
(Garagnani et al., 2016).

En el caso particular de la aplicación de los métodos y herramientas BIM en el contexto de la mejora de la
eficiencia energética de los edificios existentes, aunque es muy prometedora, tiene que superar una serie de problemas
críticos, como la identiﬁcación de la información necesaria para la retroalimentación, la recogida e interpretación
adecuada de los datos monitorizados, el manejo de la incertidumbre y el largo tiempo y los amplios recursos necesarios
para la creación del modelo de un edificio existente (Entziane y Scharmann, 2015). Por otro lado, el creciente uso de
sistemas de gestión de eficiencia energética que permiten la automatización del control en los edificios proporciona
una gran cantidad de datos sobre el consumo, las condiciones ambientales internas y externas y los perfiles de uso
que pueden ser de gran ayuda en los procedimientos de auditoría energética. Además, suele integrar los distintos
componentes del edificio de sensores que son capaces de recoger datos sobre las condiciones térmicas internas. Sin
embargo, la elección de un método adecuado para la visualización de los datos de los sensores es importante, ya
que puede ayudar a los usuarios a comprender y trabajar intuitivamente con los datos de forma más rápida y sencilla
(Desogus et al., 2021).

28 Celia Chacón Carretón

<!-- p. 29 -->

Es de esta manera cuando entran en escena plataformas donde la implementación del conocimiento entre
agentes busca ser sincronizada y accesible. Un ejemplo de esto es el programa comercial PetroBIM responde a
una aplicación web que debe su singularidad a su desvinculación del proceso de modelado funcionando como una
continuación a la exportación de un modelo a formato fbx para la interoperabilidad de aplicaciones 3D donde se convierte
en un elemento de visualización al que desde PetroBIM, se la califica a través de módulos respecto a parámetros
patrimoniales, Es decir, el modelo se desasocia y se visualiza para su posterior definición. O BIMLegacy (Jordán
Palomar, 2019), un protocolo consistente de un portal en la nube conectado a la base de datos intrínseca en forma de
plug in a un software BIM donde los implicados no técnicos puedan participar del proceso de modelado provocando
entradas de información sin tener que usar el software AEC, de manera que se eviten duplicidad, incoherencias,
dispersiones… dadas por la multiplicidad de espacios informativos dedicados al elemento.

Ciertamente, esta es una forma de estructurar la documentación en un proyecto HBIM, en el que la operatividad
del sistema permite a los especialistas recoger datos en las fases de mantenimiento y conservación. Estos archivos
de programa muestran datos especíﬁcos, pero su uso deja atrás información valiosa, como fotografías y documentos
gráficos que también pertenecen a la historia del edificio. Este trabajo desarrolla una metodología basada en un
intercambio de información en un proyecto activo incluido en una plataforma digital BIM. Los procedimientos utilizados,
en los que los operadores trabajan en tiempo real para implementar el proyecto HBIM, lo convierten en un proyecto
sostenible. La captura de datos para contribuir a la precisión y similitud de las características morfológicas del objeto
posee el mismo peso en la aportación del modelado que el vuelco de información que se desarrolla en su levantamiento
cuya variedad formal permitiendo la digitalización y la accesibilidad en línea del material cultural y la conservación
digital (Korro et al., 2021).

Existen directrices sobre las prácticas de intervención en el patrimonio. Por ejemplo, las Cartas Internacionales
de Restauración crearon diferentes documentos que describen las mejores prácticas y métodos de intervención.
Diferentes organizaciones patrimoniales como Heritage England o el Instituto del Patrimonio Cultural de España (IPCE)
han ido actualizando sus guías de intervención, creando guías patrimoniales específicas para determinados tipos de
bienes patrimoniales (por ejemplo, industrial, religioso, defensivo) y proponiendo leyes. Respecto a otras aportaciones
en el panorama nacional, en 2014 un equipo multidisciplinar español de expertos en la herramienta adaptaron la guía
al sector de la construcción española para garantizar el correcto uso de BIM (Building Smart Spanish Chapter, 2014).

La implementación de HBIM todavía requiere un debate metodológico y una experimentación práctica para
aplicar este tipo de documentación en un proceso más amplio de conservación y mantenimiento del patrimonio (López
et al., 2017). Se deben investigar más ampliamente en el futuro algunos límites y barreras con respecto a la ausencia
de conjuntos y objetos BIM de libre acceso para edificios patrimoniales (Brumana et al., 2013). Teniendo en cuenta
estos retos, las bibliotecas HBIM requieren una investigación amplia y compartida sobre los dibujos, la elaboración y las
actividades de interpretación del estudio de datos (Oreni et al., 2014). Finalmente existe una brecha de conocimiento
en la automatización y adaptación de la tecnología BIM a los edificios existentes, ya que los estudios no siempre tienen
en cuenta las necesidades sociales y culturales, que es un requisito fundamental en los proyectos de patrimonio (Volk
et al., 2014), es por ello que se vuelve a incidir en la fundamentalidad del factor entendimiento y revisión arquitectónica
e histórica en el momento de levantamiento.

TFG | Aplicación de la herramienta BIM al patrimonio arquitectónico 29

<!-- p. 30 -->

1.2 | Casos de estudio

La metodología y la tecnología asociadas al modelado de información de edificios (BIM) proporcionan a
arquitectos, ingenieros, arqueólogos e historiadores, entres otros agentes implicados, conceptos y herramientas que
apoyan el desarrollo de proyectos patrimoniales. Sin embargo, como se ha expuesto, esta forma específica de BIM
orientada a los edificios de valor patrimonial requiere una visión distinta y adicional, que tenga en cuenta aspectos que
normalmente no se atienden en los proyectos de edificios nuevos (Korro et al., 2021).

A pesar de la tendencia de la comunidad científica a adoptar la tecnología BIM para el diseño y la gestión del
ciclo de vida de las construcciones, se han realizado pocas investigaciones para explorar el valor de BIM en la gestión
y documentación de los monumentos del patrimonio cultural (Fai et al., 2011). Sin embargo, los investigadores han
desarrollado recientemente diferentes técnicas para la gestión fiable y coherente de la información relacionada con el
patrimonio cultural siendo el primer uso del BIM para edificios existentes la investigación de Arayici y Tah (2008) que
abogaba por la adopción del BIM para ir más allá de la visualización memorística en 3D de la geometría mediante la
incorporación de datos inteligentes, multifuncionales y multirrepresentacionales.

30 Celia Chacón Carretón

<!-- p. 31 -->

El método de documentación digital y registro de edificios históricos se basa en las normas internacionales para
el registro y la documentación del patrimonio cultural tangible e intangible y de los artefactos, han sido establecidas
por la Carta de Venecia (1964), que se refiere a la documentación digital y en papel del patrimonio cultural (ICOMOS
2012). Pero a pesar de la existencia de cada vez más publicaciones centradas en la normalización mediante directrices
y procedimientos internos de los organismos culturales, no se manifiesta a nivel nacional legislativo español ninguna
directriz sobre ello. Building Smart propone una recopilación de documentos en forma de guías con información
general y recomendaciones en el modelado, existiendo un último documento centrado en el BIM aplicado a inmuebles
patrimoniales (Armisén el al. 2018). En cuanto a las buenas prácticas y los criterios creados por las instituciones
culturales, deben examinarse tanto las organizaciones internacionales como las nacionales (ICOM, Getty, Historic
England, etc.), así como la experiencia acumulada mediante los planes para el patrimonio cultural en diferentes países
(Zhou et al., 2012).

1.1.2 | Justificación de los casos de estudio

Es por ello que como parte de esta investigación sobre el estado actual del conocimiento del levantamiento BIM
del patrimonio arquitectónico, se decide incluir el análisis exhaustivo de diez casos de estudio concretos que permitan
observar el acercamiento de diversos investigadores a realidades patrimoniales en el momento del levantamiento de
una manera directa y objetiva. Se desarrolla una colección de fichas y una tabla comparativa final de casos con lo que
se espera dar una visión de conjunto sobre la variedad de aspectos que se pueden abordar a la hora de estudiar bienes
patrimoniales, mediante su levantamiento BIM de acuerdo tanto a conceptos de modelado, como a las propios casos
arquitectónicos. El desarrollo de este trabajo se rige mediante un método sistemático de recogida de datos a través de
bibliografía publicada para su posterior estudio y sintetización; la literatura sobre el proceso en sí de levantamiento se
obtiene de mano de investigadores en forma de tesis y artículos publicados que recogen su experiencia empírica. De
esta manera se realizará un análisis crítico de factores tanto en relación con el inmueble como su levantamiento, y se
permitirá un abordaje de la información existente más concreta y discretizada. El resultado no solo será de aplicación
directa a la experiencia propia de levantamiento de la presente investigación, sino que se pretende adicionalmente
generar contenido de valor para posteriores investigaciones o acercamientos a la materia.

La selección consta de diez casos de estudio escogidos desde la búsqueda de su diversidad en su enfoque y
problemática según con los siguientes criterios:

1 | Actualidad del levantamiento
Los casos estudiados responden a experiencias realizadas en los últimos diez años desde la fecha de esta
investigación con el objetivo de observar prácticas que empleen métodos aplicables a la realidad actual.

2 | Fidelidad patrimonial
Los casos estudiados responden a la caracterización de levantamiento HBIM debido a la inclusión de
aspectos patrimoniales fidedignos que verifiquen su catalogación con información (confirmada o atribuida) en
forma de fuentes documentales, bibliográficas, planimétricas, iconográficas, fotografías, epigráficas… que
permitan un modelado preciso en su nivel de conocimiento (LOK).

TFG | Aplicación de la herramienta BIM al patrimonio arquitectónico 31

<!-- p. 32 -->

3 | Acceso a la información
Los casos estudiados se encontrarán publicados en forma de tesis, artículos de revistas, libros, capítulos de
libro o contribuciones a congresos de tal manera que su información sea accesible públicamente y de carácter
científico.

4 | Información sobre el método
Los casos estudiados exponen en su bibliografía el método empleado para el levantamiento de manera
directa, específica y técnica a través de literatura e imágenes significativas que permitan el desengranaje,
entendimiento y reproducción del proceso de razonamiento seguido a la hora del modelado e integración de la
información.

5 | Transversalidad del conocimiento
Los casos estudiados incluyen en su levantamiento información de carácter transversal de una a varias
aéreas que enriquezcan y complejicen el levantamiento produciendo relaciones entre la arquitectura y otras
realidades propias de los contextos patrimoniales como la estratigrafía histórica, la existencia de trazas
arqueológicas, la presencia de muebles históricos u otro tipo de elemento histórico-artístico…

6 | Incorporación de valoración tutelar e intervenciones
Los casos estudiados incluyen en su levantamiento información que permita el conocimiento del recorrido
tutelar de la edificación como lo son las intervenciones o planes que se hayan sucedido además de la
caracterización del estado del inmueble de acuerdo a sus patologías, estado de conservación, mantenimiento...

7 | Parámetros empleados
Los casos estudiados usan parámetros en la definición de su modelo en mayor o menor
medida, caracterizando de manera objetiva y técnica los elementos y/o espacios del
inmueble de acuerdo a su realidad patrimonial. La integración de parámetros singulares en forma
de aportación al campo de la investigación BIM será un incentivo para la selección del caso de estudio.

8 | Integración de aspectos arquitectónicos contemporáneos
Los casos estudiados integran aspectos arquitectónicos no tan ligados de manera histórica al ámbito
patrimonial como parte de su entendimiento y actuación como realidad arquitectónica contemporánea.
Reconocimiento de trazas geométricas, presencia de piezas artísticas, relaciones urbanas posteriores a la
construcción documental, lecturas constructivas actuales mediante sistemas innovadores, sistemas de
instalaciones en intervenciones...

9 | Morfología edificatoria
Los casos estudiados son de carácter edificatorio dejando al margen de esta selección aquellos levantamientos
realizados de muebles o elementos constructivos concretos que a pesar de formar parte de un inmueble no
supongan una relación arquitectónica espacial directa sino estudio paramental o constructivo de un sistema
singular de manera exenta.

32 Celia Chacón Carretón

<!-- p. 33 -->

10 | Contexto patrimonial
Los casos estudiados incorporan el contexto patrimonial en el que se insertan de manera directa siempre que
esta contribución sea de interés en el desarrollo de la investigación. De la misma manera y siguiendo la
lógica del criterio anterior, los casos de estudio de sistemas urbanos modelados desde una perspectiva
únicamente geográfica y/o arqueológica quedarán fuera de la selección.

11 | Similitud con el caso de estudio desarrollado en la experiencia de esta investigación
Los casos estudiados son de carácter edificatorio similar al caso de estudio de esta investigación, el
Convento de Santa Clara de la Columna, con el objetivo de maximizar el conocimiento empleado en esta
experiencia tras la investigación. Con ello se priorizan conjuntos edificatorios, edificios con varias alas u
espacios y construcciones de carácter religioso con técnicas constructivas similares a las expuestas en la
descripción del caso de estudio.

TFG | Aplicación de la herramienta BIM al patrimonio arquitectónico 33

<!-- p. 34 -->

Antes de proceder con la exposición de los aspectos analizados en los casos de estudio, se recogen aquellos
levantamientos que a pesar de formar parte del corpus de casos tenidos en cuenta en el proceso de investigación por
su valor en el conocimiento actual de la materia, no se seleccionan para las fichas debido a no incluirse en los requisitos
expuestos anteriormente; al efecto se indican las razones por las que se han descartado de esta investigación en el
caso de ser de interés para otros trabajos. En cada caso se recoge información general sobre el levantamiento, su
bibliografía principal y la numeración de los requisitos que no cumplen en relación al listado anterior, que han motivado
su no inclusion como caso de estudio en el presente trabajo:

Bien | El facistol de la Catedral de Sevilla, España s.XV (7,9,11)
Investigador | Roque Angulo Fornos
Bibliografía | Angulo Fornos, R. (2016). El modelo digital del facistol de la Catedral de Sevilla. Estudios y recuperación.
Editorial Universidad de Sevilla y Catedral de Sevilla, 2016, 227-242.

Bien | La portada del maestro Hernán Ruiz, Sevilla, España 1563 (9,11)
Investigador | Roque Angulo Fornos
Bibliografía | Angulo Fornos, R., Pinto Puerto, F., Rodríguez Medina, J. y Palomino Rodríguez, A. J. (2017). Digital
Anastylosis of the Remains of a Portal by Master Builder Hernán Ruiz: Knowledge Strategies, Methods and Modelling
Results. Estudios y recuperación. Digital Applications in Archaeology and Cultural Heritage, 7, 32-41.

Bien | La capilla de la Antigua de la Catedral de Sevilla, España s.XV (7,11)
Investigador | Roque Angulo Fornos
Bibliografía | Angulo Fornos, R. y Pinto Puerto, F. (2015). Decisiones constructivas en la ejecución de la capilla de la
Antigua de la catedral de Sevilla. Estudio a través de modelos gráficos. En: Instituto Juan de Herrera. Actas del Noveno
Congreso Nacional y Primer Congreso Internacional Hispanoamericano de Historia de la Construcción: Segovia, 13 a
17 de octubre de 2015 (p. 1337-1347).

Bien | La iglesia de la Merced Ciudad de Panamá, Panamá 1968 (11)
Investigador | José Martínez Rubio, Juna José Fernández Martín y Jesús Ignacio San José Alonso
Bibliografía | Martínez Rubio, J.,Fernández Martín, J. J. y San José Alonso, J. I. (2018). Implementación de escáner
3D y fotogrametría digital para la documentación de la iglesia de La Merced de Panamá. EGA Expresión Gráfica
Arquitectónica, 23(32), 208-219.

Bien | El castillo de Priego de Córdoba, Córdoba, España s. XIII-XIV (7,10,11)
Investigador | Diego Francisco García Molina, Ramón González Merino, Jesús Rodero Pérez y Bartolomé Carrasco
Hurtado
Bibliografía | García Molina, D. F., González Merino, R., Rodero Pérez, J. y Carrasco Hurtado, B. (2021). Documentación

34 Celia Chacón Carretón

<!-- p. 35 -->

3D para la conservación del patrimonio histórico: el Castillo de Priego de Córdoba. Virtual Archaeology Review, 12(24),
115-130.
Bien | El castillo de Piñar, Granada, España s.XIV (7,10,11)
Investigador | José Antonio Benavides López, José Mª Martín Civantos y Jorge Rouco Collazo
Bibliografía | Benavides López, J. A., Martín Civantos, J. M. y Rouco Collazo, J. (2019). Levantamiento arquitectónico
y análisis arqueológico del Castillo de Piñar como punto de partida para su conservación. Virtual Archaeology Review,
11(22), 95-115.

Bien | La galería de la Academia de Florencia, Florencia, Italia 1563 (7,9,11)
Investigador | Grazia Tucci, Alessandro Conti, Lidia Fiorini, Manuela Corongiu, Noemi Valdambrini y Carlotta Matta
Bibliografía | Tucci, G., Conti, A., Fiorini, L., Corongiu, M., Valdambrini, N y Matta, C. (2019). M-BIM: A new tool for the
Galleria dell’Accademia di Firenze. Virtual Archaeology Review, 10(21), 40-55.

Bien | La iglesia de San Pedro de Arcos de la Frontera, Cádiz, España s.XVi-XVII (11)
Investigador | Manuel Castellano Román
Bibliografía | Castellano Román, M. (2015). Generación de un modelo de información del patrimonio inmueble en el
momento de su protección jurídica. EGA Revista de Expresión Gráfica Arquitectónica, 20(26), 266-277.

Bien | La sinagoga de Vinohrady, Praga, República Checa 1896 (4,7,11)
Investigador | Stefan Boeykens, Caroline Himpe y Bob Martens
Bibliografía | Boeykens, S., Himpe, C. y Martens, B. (2010). A Case Study of Using BIM in Historical Reconstruction. The
Vinohrady synagogue in Prague. Physical Digitality, 30.

Bien | La puerta San Cristóbal de la Catedral de Sevilla, España 1887-1895 (9,11)
Investigador | Francisco Pinto Puerto y José María Guerrero Vega
Bibliografía | Pinto Puerto, F. y Guerrero Vega, J. M. (2015). Modelos digitales aplicados a la intervención del patrimonio
arquitectónico: La restauración del remate sureste de la puerta de San Cristóbal en la catedral de Sevilla. Virtual
Archaeology Review, 6(12), 103-108.

Bien | La iglesia de San Juan de los Caballeros de Jerez de la Frontera, Cádiz, España 1264 (11)
Investigador | Francisco Pinto Puerto, Gregorio Mora Vicente y José María Guerrero Vega
Bibliografía | Pinto Puerto, F., Mora Vicente, G. y Guerrero Vega, J. M. (2019). Trabajos previos y paralelos integrados
en el proyecto de restauración de la capilla de los Tocino (s. XV) en la iglesia de San Juan de los Caballeros de Jerez
de la Frontera. Arqueología de la Arquitectura, 16, e086.

Bien | Castillo Acrocorinto, Corinto, Grecia s.VII a.C. (7,10,11)
Investigador | Demetrios Athanasoulis, Xeni Simou y Theodora Zirogianni
Bibliografía | Athanasoulis, D., Siou, X. y Zirogianni, T. (2017). Historical Imprints and Virtual Representation Issues in
Mid-Byzantine Acrocorinth Castle. Virtual Archaeology Review, 8(17), 10-19.

Bien | El friso de barro dell’Ospedale del Ceppo en Pistoia, Toscana, Italia 1277 (7,9,11)
Investigador | Grazia Tucci, Valentina Bonora, Alessandro Conti y Lidia Fiorini
Bibliografía | Tucci, G., Bonora, V., Conti, A. and Fiorini, L. (2017). High-quality 3D Models and their Use in a Cultural

TFG | Aplicación de la herramienta BIM al patrimonio arquitectónico 35

<!-- p. 36 -->

1.2.2 | Casos

El estudio de los casos se expresa mediante un total de 10 fichas cuyo objetivo principal es la recopilación de la
información en vistas de obtener una documentación precisa y visual que facilite el conocimiento y la comparativa eficaz
entre casos a la hora de enfrentarse o la investigación y/o a la experiencia de levantamiento patrimonial BIM. Para ello
se ha optado por un modelo de díptico A4 en el cual se refleja a la izquierda del formato el proceso de levantamiento y
la derecha la descripción del caso patrimonial. De esta manera se busca la inmediata comprensión del proceso -objeto
y resultado-.

36 Celia Chacón Carretón

<!-- p. 37 -->

A continuación se recogen los casos de estudio seleccionados según los criterios del apartado 1.2.1:

01 | La Cartuja de Nuestra Señora Santa María de la Defensión de Jerez | Castellano Román, Manuel (2017)

02 | Conjunto arqueológico Itálica | Angulo Fornos, Roque (2011)

03 | Casa de Hylas | Angulo Fornos, Roque (2012)

04 | Fachada del cuadrante renacentista Catedral de Sevilla | Angulos Fornos, Roque (2019)

05 | Iglesia San Juan del Hospital | Jordán Palomar, Isabel (2015)

06 | Basilica di Collemaggio | Brumana, Raffaella et al. (2014)

07 | Chiesa di Santa María | Brumana, Raffaella et al. (2013)

08 | La Real Colegiata de San Isidoro | Santoni, Arianna et al. (2020)

09 | Complejo Medieval Sant ’Apollinare | Piselli, Cristina et al. (2020)

10 | La Antigua Cárcel de la Real Fábrica de Tabacos | Nieto Julián, Juan Enrique (2012)

Todas las fichas siguen esta relación nominal de caso en su identificación.

De igual manera se procede a describir más explicitamente el contenido de las fichas. Para ello se sigue el
mismo formato díptico A4 y el estilo de ficha, creando una ficha caso 00 para su comprensión y reproducción.

A la izquiera del formato se recoge información en cuanto al proceso de levantamiento, un resumen de las más
esenciales del levantamiento tras la realización de un análisis crítico del mismo.Los datos que se reunen muy concretos
y objetivos con la intención de caracterizar brevemente los aspectos principales y de potencial comparativos de cada
experiencia para su posterior indagación o reproducción:

A la derehca del formato serecoge información básica sobre el inmueble de acuerdo a un criterio
histórico-documental, valoración patrimonial y repercusión contemporánea y finalmente aseptos relacionados con el
ojetivo de esta investigación como es su uso y acceso:

En el caso de no obtener alguno de estos datos se opta por su omisión. Del mismo modo, se reitera el hecho de
que los datos recogidos en estas fichas responden al estudio de dichos casos consultados en criterio del entendimiento
del proceso investigador que han producido; de manera que dicha información es la concreción realizada en esta
investigación de la literatura en forma de tesis y artículos publicados por los investigadores citados para la difusión de
su trabajo y conocimiento científico.

TFG | Aplicación de la herramienta BIM al patrimonio arquitectónico 37

<!-- p. 38 -->

Denominación | Investigador (Año)

Investigador Persona individual o grupo de investigadores que han producido dicho levantamiento.
Año Año en el que se publicó la investigación que recauda dicha experiencia por vez primera a menos
de que se especifique en el documento su año de realización. En todo caso es coincidente o un año
anterior.

Justificación del uso del BIM Más allá de las virtudes y la potencialidad de la herramienta ya recogidas en la investigación, en
este apartado se propone concretar la justificación particular del uso BIM en cada caso singular en
respuesta a una oportunidad y/o problemática precisa.

Objetivo De nuevo se presenta este dato a partir del entendimiento de los objetivos de por sí integrados en el
levantamiento y el levantamiento BIM en cuestión, como oportunidad de señalar metas concretas de
estos casos de estudio.

Método Método empleado en el levantamiento. Este apartado responde a la catalogación ya realizada por
Angulo Fornos (2020) que define varios de los casos de estudio desarrollados por él en estas fichas
de información de acuerdo a su levantamiento paramétrico o no paramétrico de manera manual,
semiautomática o automática. El levantamiento mediante herramienta BIM incluye por definición la
utilización de parámetros pero estos siempre aparecen de manera indirecta debido al funcionamiento
de estos softwares. Con levantamiento paramétrico se busca indicar la creación y presencia intencional
y razonada de parámetros alternativos añadidos por el investigador/es a los propiciados por la
herramienta para la complejización y catalogación de la información de sus elementos y espacios.
Si es manual o automático dependerá de la toma de datos y su incorporación al modelo. En el primer
caso el modelado consiste en el levantamiento manual de las entidades constructivas mediante las
herramientas ofrecidas por el programa desestimando iregularidades, deformaciones... siendo el
segundo un proceso de generación totalmente automatizado a raíz de generalmente nubes de puntos.
El semiautomático se desarrolla por lo tanto combinando ambos métodos.

Parámetros Listado general de los parámetros o grupos de parámetros recogidos en el levantamiento para la
definición de elementos/espacios.

Resultados Resultados obtenidos de carácter metodológico y formal en el levantamiento y resultados aplicables
a la gestión del caso de estudio y su tutela.

Conclusiones Resumen y valoración de los puntos más relevantes y aportaciones alcanzadas en la experiencia.

Bibliografía Bibliografía existente hasta el momento de esta investigación al respecto.

imagen representativa del levantamiento

38 Fig. X | Nombre (Autor, Año)

<!-- p. 39 -->

CASO 00

Denominación Identificación histórica nominativa
Localización Situación geográfica
Data Año o siglo de su construcción
Autoría Autor del inmueble o responsable de su construcción
Tipo Catalogación edificatorio del inmueble
Estilo Denominación histórica que identifica la tendencia artística de una época, autor, emplazamiento… y
aporta información contextual

Estado de conservación Valoración contemporánea del conservador del inmueble
Intervenciones Relación de intervenciones (tipo y fecha) documentadas en el levantamiento de manera directa

Reconocimiento Valoración del patrimonio
Catalogación Figura jurídica de protección del patrimonio

Uso original Uso característico de su construcción
Uso contemporáneo Uso o usos actuales que se suceden en el inmueble
Visitabilidad Posibilidad de acceso al inmueble siendo: visitable cuando la mayoría de sus espacios se encuentran
abiertos al público y restringido cuando haya espacios de acceso limitado o clausuras.

Bibliografía Bibliografía consultada para la recopilación de los datos expuestos anteriormente

imagen representativa del inmueble patrimonial

Fig. X | Nombre (Fuente) 39

<!-- p. 40 -->

La Cartuja de Nuestra Señora Santa María de la Defensión de Jerez | Castellano Román, Manuel (2017)

Investigador Manuel Castellano Román, Universidad de Sevilla
Año 2017
Justificación del uso del BIM El levantamiento BIM permite estudiar y valorar la realidad patrimonial integral del bien en sus tres
escalas territorial, urbana y arquitectónica, integrando toda la documentación existente al respecto de
manera interdisciplinar. A su vez, su modelado incluye la posibilidad de cuantificar las lesiones.

Objetivo Desarrollar un modelo gráfico digital de información para la mejora en la gestión integral de la tutela
patrimonial (protección, conservación, investigación y difusión) dando cabida a todos los campos de
conocimiento que surgen de la interdisciplinaridad del hecho patrimonial. El proceso de levantamiento
incluirá la producción de una base de datos y visualizaciones formales que permitan una interpretación
contemporánea completa tanto de características materiales como espaciales.

Método Paramétrico | Manual
Parámetros Fases históricas
Identificación singular de elemento
Lesiones
Intervenciones
Grado de afección
Grado de urgencia
Links a documentos
Espacios (protección, vulnerabilidad, conservación, urgencia, visibilidad)

El levantamiento ha generado un modelo integral con una relación nominal de cada elemento y una
Resultados clasificación de éstos inéditos que describe su evolución histórica y constructiva con una caracterización
general de estado de conservación respecto a niveles de urgencia de intervención constatándose las
deficientes acciones de difusión de su valor patrimonial. A su vez se ha creado un HBIR que centraliza
la información disponible que propicia su conocimiento, conservación y difusión.

Conclusiones El levantamiento BIM permite valorar el conocimiento del patrimonio como proceso dinámico por sí
mismo que además de salvaguardar el conocimiento de manera eficaz provoca la generación de
nueva información desde una perspectiva contemporánea que no sólo incluye el inmueble como
edificación sino como espacio histórico complejo. Respecto a la gestión tutelar, el modelo mejora la
planificación estratégica de grandes conjuntos monumentales aportando bases para la generación de
Bibliografía un Plan Director.

Castellano Román, M. (2017). La Cartuja de Nuestra Señora de la Defensión en Jerez de la Frontera: un modelo digital de información
para la tutela de bienes inmuebles del patrimonio cultural. [Tesis de Doctorado, Universidad de Sevilla].
Castellano Román, M. & Pinto Puerto, F. (2019). Dimensions and Levels of Knowledge in Heritage Building Information Modelling, HBIM:
The model of the Charterhouse of Jerez (Cádiz, España). Digital Applications in Archeology and Cultural Heritage, 14 (e00110).
Castellano Román, M. & Pinto Puerto, F. (2019). HBIM Oriented towards the Master Plan of the Charterhouse of Jerez (Cádiz, España).
International Archives of the Photogrammetry, Remote Sensing and Spatial Information Sciences, XLII-2/W5, 285-290.

40 Fig. 4 | La Cartuja de Jerez, Axonométrica SO (Castellano Román, 2017)

<!-- p. 41 -->

CASO 01

Denominación La Cartuja de Nuestra Señora Santa María de la Defensión
Localización Jerez de la Frontera, Cádiz, España
Data s. XV d.C. - s.XVII d.C.
Autoría Álvaro Obertos de Valeto
Tipo Monasterio
Estilo Gótico - Renacimiento

Estado de conservación Bueno
Intervenciones

Reconocimiento Monumento Nacional 1856
Catalogación Bien de Interés Cultural BIC 31|07|1856

Uso original Monasterio
Uso contemporáneo Monasterio
Visitabilidad Restringido

Bibliografía https://www.juntadeandalucia.es/cultura/agendaculturaldeandalucia/evento/visita-la-cartuja-de-jerez
https://www.defension.com/02historia/la-cartuja/
http://cartujadejerez.es/generalidades/

Fig. 5 | Cartuja de Jerez (Miguel Ángel Pineda) 41

<!-- p. 42 -->

Conjunto arqueológico Itálica | Angulo Fornos, Roque (2011)

Investigador Roque Angulo Fornos, Universidad de Sevilla
Año 2011
Justificación del uso del BIM En el 2009 este inmueble se enfrentó a la redacción de su plan director y la necesidad de ordenar
la información, estudiar problemas y afecciones existentes (registradas o no) y redactar informes
al respecto. La herramienta BIM permite construir un instrumento gráfico con el cual mantener la
información accesible y flexible además de levantar espacios no documentados o parcialmente
documentados salvando las limitaciones arquitectónicas de un soporte SIG.

Objetivo Organizar la información en un modelo que permita su gestión a largo plazo en un Plan Director,
siendo el resultado una base cartográfica activa que incluya un inventario tridimensional y documental
exhaustivo de la información existente y de la incorporada tras el estudio y análisis.

Método Paramétrico | Manual
Parámetros Trazas generadoras
Lesiones
Grado de afección
Grado de urgencia
Links a documentos

Resultados La base cartográfica es un documento integral y multidisciplinar que recoge toda la información hasta
el momento del levantamiento además de todos los datos relativos a lesiones, grado de afección
y propuesta de intervención codificadas tras el análisis y estudio. Redacción del Plan Director del
Conjunto Arqueológico.

Conclusiones Mediante el levantamiento BIM se ha generado un modelo gráfico con información integral cuyos
elementos se hallan catalogados en diversas categorías vinculadas a bases de datos que permiten
su actualización a tiempo real. De igual manera se han generado planos, informes, mediciones y
valoraciones integrales.
La utilidad de esta interrelación de datos en el caso de una zona arqueológica radica en la posibilidad
de jerarquizar la entidad de los restos, más allá de su componente geográfica, para su gestión tutelar.

Bibliografía Pinto Puerto, F., Angulo Fornos R., Castellano Román, M., Guerrero Vega J. M. y Pastor Gil F. (2011). Construcción de una base cartográfica activa para el Conjunto Arqueológico de Itálica. PH: Boletín del Instituto Andaluz del Patrimonio Histórico, 20 (83), 116-119.

Angulo Fornos, R. (2020). Desarrollo de modelos digitales de información como base para el conocimiento, la intervención y la gestión
en el patrimonio arquitectónico. De la captura digital al modelo HBIM. [Tesis de Doctorado, Universidad de Sevilla].

42 FIg. 6 | Tablas asociadas a elementos (Angulo Fornos et al., 2011)

<!-- p. 43 -->

CASO 02

Denominación Conjunto Arqueológico Itálica
Localización Santiponce, Sevilla, España
Data s. II a.C. (206)
Autoría
Tipo Restos arqueológicos
Estilo Romano

Estado de conservación Bueno
Intervenciones

Reconocimiento Monumento Nacional 1912
Catalogación Bien de Interés Cultural BIC 13|12|1912

Candidatura Patrimonio de la Humanidad UNESCO

Uso original Ciudad romana
Uso contemporáneo Conjunto arqueológico
Visitabilidad Visitable

Bibliografía https://www.andalucia.org/es/santiponce-turismo-cultural-conjunto-arqueologico-de-italica
http://www.museosdeandalucia.es/web/conjuntoarqueologicodeitalica
http://www.museosdeandalucia.es/web/conjuntoarqueologicodeitalica

Fig. 7 | Conjunto arqueológico Itálica (Web Oficial de Turismo de Andalucía) 43

<!-- p. 44 -->

Casa de Hylas | Angulo Fornos, Roque (2012)

Investigador Roque Angulo Fornos, Universidad de Sevilla
Año 2012
Justificación del uso del BIM La problemática en la eficiencia de la gestión y divulgación del conocimiento transversal, y en las
labores de mantenimiento, conservación e intervención viene dada por el método de representación
gráfica. La herramienta BIM permite la consideración del objeto arquitectónico como documento en sí
mismo realizando un registro modelo racional e integral.

Objetivo A raíz de la base cartográfica de Itálica, establecer las bases para la construcción de una herramienta
que basada en un modelo infográfico sea capaz de contener y gestionar toda la información generada
sobre un inmueble arquitectónico concreto (salvando las carencias del SIG) facilitando la transversalidad
entre los análisis de diversas ramas de conocimiento. De esta manera se busca mejorar los recursos
gráficos mediante una lectura integral con información arquitectónica más allá de la vectorial.

Método Paramétrico | Semiautomático
Parámetros Trazas generadoras
Sistema constructivo
Intervenciones
Lesiones
Grado de afección

Resultados El modelo ha producido una lectura de las entidades geométricas generadoras con información más
allá de la implícita en la información geográfica e informes técnicos. Su comportamiento como base
de datos documental gráfica ha permitido un análisis sintético y fidedigno de su morfología, estado
de conservación y sus intervenciones. A su vez, se ha generado un vínculo con una base de datos
externas con la información que permite el trasvase en ambos sentidos.

Conclusiones El levantamiento de las trazas arqueológicas de estos restos ha permitido desarrollar una entidad
arquitectónica a raíz de la escasa información existente con el suficiente valor práctico al ejecutar el
modelo en un entorno BIM que está implícitamente relacionado con la construcción.
El método empleado se ha centrado en el análisis por lo que el modelo iconográfico ha sido resultado
de una abstracción que permite un enfoque de su gestión más transversal de acuerdo a criterios tanto
arquitectónicos, como arqueológicos e historiográficos.

Bibliografía Angulo Fornos, R. (2012). Construcción de la base gráfica para un sistema de información y gestión del patrimonio arquitectónico: Casa
de Hylas. Arqueología de la Arquitectura, 9, 11-25.

Angulo Fornos, R. (2020). Desarrollo de modelos digitales de información como base para el conocimiento, la intervención y la gestión
en el patrimonio arquitectónico. De la captura digital al modelo HBIM. [Tesis de Doctorado, Universidad de Sevilla].

44 Fig. 8 | Vista desde noreste del modelo texturado (Angulo Fornos, 2012)

<!-- p. 45 -->

CASO 03

Denominación Casa de Hylas
Localización Santiponce, Sevilla, España
Data s. II a.C. (206)
Autoría
Tipo Restos arqueológicos
Estilo Romano

Estado de conservación Bueno
Intervenciones

Reconocimiento Monumento Nacional 1912
Catalogación Bien de Interés Cultural BIC 13|12|1912

Candidatura Patrimonio de la Humanidad UNESCO

Uso original Vivenda
Uso contemporáneo Restos arqueológicos
Visitabilidad Visitable

Bibliografía https://www.hisour.com/es/roman-city-of-italica-seville-spain-51081/
http://www.spanisharts.com/arquitectura/imagenes/roma/italica_casa_hilas.html
http://www.tarraconensis.com/italica/casahylas.html

Fig. 9 | Casa de Hylas (Leyendas de Sevilla) 45

<!-- p. 46 -->

Fachada del cuadrante renacentista Catedral de Sevilla | Angulos Fornos, Roque (2019)

Investigador Roque Angulo Fornos, Universidad de Sevilla
Año 2019
Justificación del uso del BIM La implementación de este tipo de modelo digital en la obra expuesta lo valida como una opción de
solvencia, aportada desde el medio infográfico, ante la necesidad de contener, gestionar y visualizar
toda la información generada en las actuaciones de conservación preventiva sobre la arquitectura.

Objetivo Observar diferentes estrategias de modelado digital del proceso constructivo de un elemento
arquitectónico incorporando datos arquitectónicos y arqueológicos orientados a la conservación
preventiva del bien.

Método Paramétrico | Semiautomático
Parámetros Fases históricas
Unidades estratigráficas
Lesiones
Estado de conservación

Resultados El modelo se ha realizado de manera que la superposición de los distintos sólidos que componen la
fachada permiten la lectura del sistema constructivo desde el nivel pieza al nivel sistema constructivo
permitiendo un registro y análisis a ambas escalas de: materialidad, sistemas constructivos, acabados,
fases, lesiones, estado de conservación...

Conclusiones La lectura estratigráfica realizada mediante el levantamiento ha permitido la extracción de claves
para la caracterización de las unidades constructivas del modelo del fragmento seleccionado.El
LOK alcanzado en este modelo más desarrollado ha permitido utilizarlo como base para el registro y
gestión de la información patrimonial, permitiendo visualizaciones temáticas gráficas y alfanuméricas,
facilitando, a su vez, las relaciones transversales entre los diferentes análisis que redundan en un
conocimiento más profundo de este tipo de edificios.

Bibliografía Angulo Fornos, R. (2020). Desarrollo de modelos digitales de información como base para el conocimiento, la intervención y la gestión
en el patrimonio arquitectónico. De la captura digital al modelo HBIM. [Tesis de Doctorado, Universidad de Sevilla].
Angulo Fornos, R. and Castellano Román, M. (2020). HBIM as Support of Preventive Conservation Actions in Heritage Architecture.
Experience of the Renaissance Quadrant Facade of the Cathedral of Sevilla. Applied Sciences, 10, 2428.
Pinto Puerto, F., Angulo Fornos R. y Castellano Román, M. (2021). Estrategias de modelado patrimonial en HBIM, aplicación a la lectura
estratigráfica del muro de fachada del cuadrante renacentista de la catedral de Sevilla. Arqueología de la Arquitectura, 18, e109-e109.

46 Fig. 10 | Nivel de detalle y proceso de edición CAD (Angulo Fornos et al., 2021)

<!-- p. 47 -->

CASO 04

Denominación Fachada del cuadrante renacentista, Catedral de Sevilla
Localización Sevilla, Sevilla, España
Data s. XVI d.C. (1528-1596)
Autoría Diego de Riaño
Tipo Edificación religiosa
Estilo Renacentista

Estado de conservación Bueno
Intervenciones Restauración y limpieza de la fachada exterior, 2017

Reconocimiento Monumento
Catalogación Bien de Interés Cultural BIC 29|12|1928

Patrimonio de la Humanidad UNESCO 25|07|1987

Bien de Valor Universal Excepcional 25|07|2010

Uso original Iglesia
Uso contemporáneo Iglesia
Visitabilidad Visitable

Bibliografía https://www.catedraldesevilla.es/muestra-de-los-trabajos-sobre-las-fachadas-renacentistas/
http://historiartesevilla.blogspot.com/2013/04/puertas-de-la-catedral-22.html

Fig. 11 | Cuadrante renacentista Catedral de Sevilla (Conoce Spain) 47

<!-- p. 48 -->

Iglesia San Juan del Hospital | Jordán Palomar, Isabel (2015)

Investigador Isabel Jordán Palomar. Universitat Politècnica de València
Año 2015
Justificación del uso del BIM El potencial de la herramienta BIM en el contexto específico del patrimonio reside la capacidad de
representar las fases históricas, crear una base de datos intrínseca de las realidades constructivas
históricas y permitir la sincronización de la información en tiempo real de acceso multidisciplinar.

Objetivo El objetivo del levantamiento es deﬁnir un protocolo para generar una base de datos que recoja de
manera fidedigna la edificación con la metodología BIM para la gestión del patrimonio arquitectónico
incluyendo a las diversas partes interesadas que participan en este proceso.

Método Paramétrico | Manual
Parámetros Fases histórica
Unidades estratigráficas
Sistema constructivo
Lesiones

Resultados Se ha obtenido un modelado geométrico y estandarizado que permite la reflexión constructiva del
inmueble a través de la creación de una biblioteca histórica medieval de familias tipológicas teóricas,
las cuales son muy valiosas para el estudio y el análisis del patrimonio arquitectónico medieval. La
inclusión de las fases constructivas ha permitido la ordenación y verificación de la información hasta
entonces dispersa y no constatada de manera arquitectónica.

Conclusiones El modelo HBIM es más útil para la gestión de edificios históricos que los simples modelos de nubes de
puntos o la fotogrametría debido a la posibilidad de introducir fases históricas y al hecho de disponer
de bases de datos asociadas que permiten una construcción virtual requiriendo un proceso cognitivo
para lograr un conocimiento profundo del edificio del caso de estudio. Asimismo, se demuestra que
el modelo HBIM minimiza los errores debido a la sincronización de datos y la multidisciplinariedad
integrada.

Bibliografía JordánarquitectónicoPalomar,medievalI. (2015).aplicadoLa metodologíaal conjuntoHBIM:de SandiseñoJuandedelunHospitalmétododeparaValencia.la gestión[Tesisde dela informaciónMáster, Universitaty el conocimientoPolitècnicadeldepatrimonioValència].
García Valldecabres, J. L., López González, M. C. and Jordán Palomar, I. (2018). The Study of Architectural Heritage HBIM Methodology.
A Medieval Case Study. Springer International Publishing, AG2018, 945-955.
Jordán Palomar, I., Tzortzopoulos, P., García Valldecabres, J., y Pellicer, E. (2018). Protocol to manage heritage-building interventions
using heritage building information modelling (HBIM). Sustainability, 10, 908.
Jordán Palomar, I. (2019). Protocol to manage heritage-building interventions using Heritage Building Information Modelling (HBIM).
[Tesis de Doctorado, Universitat Politècnica de València y University of Huddersfield].

48 Fig. 12 | Vista Actualidad Patio Sur de San Juan del Hospital (Jordán Palomar, 2019)

<!-- p. 49 -->

CASO 05

Denominación Iglesia San Juan del Hospital
Localización Valencia, Valencia, España
Data s. XIII d.C. (1238)
Autoría
Tipo Edificación religiosa
Estilo Románico - Gótico

Estado de conservación Bueno
Intervenciones

Reconocimiento Monumento
Catalogación Bien de Interés Cultural BIC 05|04|1943

Uso original Iglesia
Uso contemporáneo Iglesia
Visitabilidad Visitable

Bibliografía https://sanjuandelhospital.es/iglesia-san-juan-del-hospital/
http://www.jdiezarnal.com/valenciaiglesiadesanjuandelhospital.html
https://es.wikipedia.org/wiki/Iglesia_de_San_Juan_del_Hospital_(Valencia)

Fig. 13 | Patio Sur de San Juan del Hospital (Visita Valencia) 49

<!-- p. 50 -->

Basilica di Collemaggio | Brumana, Raffaella et al. (2014)

Investigador Raffaella Brumana, Stefano Della Torre, Daniela Oreni, Mattia Previtali, Luigi Barazzetti y Fabrizio Banfi. Politecnico di Milano
Año 2014
Justificación del uso del BIM Tras el terremoto L’Aquila, la Basílica di Collemaggio resultó gravemente dañada en particular todo su
sistema estructural. Para realizar el proyecto de reconstrucción la herramienta BIM permite evaluar el
estado geométrico de las estructuras en su estado original y sus posibles reconstrucciones.

Objetivo Realizar una reconstrucción digital proponiendo distintas hipótesis de intervención estructural
incluyendo la información necesaria para la ejecución de esta (materialidad, comportamiento estructural
y lcostes) y potenciar el nivel de preservación del caso de estudio utilizando las herramientas BIM y la
interoperabilidad de acuerdo al análisis estructural del inmueble.

Método Paramétrico | Semiautomático
Parámetros Comportamiento estructural
Identificación singular de elementos
Fases histórica
Unidades estratigráficas
Lesiones
Resultados Tras diferentes experiencias, es posible argumentar que uno de los retos del modelado es el análisis
estructural y la toma de decisiones en relación con la conservación, lo que representa un paso
importante en el proceso que vincula la complejidad de la herramienta BIM con el análisis estructural.
El modelado, como herramienta de simulación y toma de decisión, ha permitido mejorar el nivel de
conservación y adoptar medidas teniendo en cuenta la tradición de sus tecnologías constructivas.

Conclusiones El uso de HBIM ha contribuido en gran medida a apoyar el proceso de restauración y conservación
del inmueble ya que el levantamiento ha sido capaz de encarnar diversas hipótesis de intervención
estructural para su estudio y comparación.
Durante el proyecto de restauración y la intervención in situ en la Basílica, se han realizado muchos
compromisos difíciles, entre cuestiones de conservación y de seguridad, lo que ha provocado también
decisiones difíciles cuando ha sido necesario mantener parcialmente la funcionalidad y la autenticidad
de los elementos estructurales que han podido ser valorados gracias al modelo.
Bibliografía Oreni,concerningD., Brumana,the BasilicaR., Delladi CollemaggioTorre, S., Banfi,after theF. andearthquakePrevitali,(L’Aquila).M. (2014).InternationalSurvey turnedArchivesinto HBIM:of thethePhotogrammetry,restoration and theRemotework involvedSensing
and Spatial Information Sciences, XLII-2/W5, 267-273.

Brumana, R., Della Torre, S., Oreni, D., Previtali, M., Cantini, L., Barazzettu, L., Franchi, A. & Banfi, F. (2017). HBIM Challenge among
the Paradigm of Complexity, Tools and Preservation: The Basilica di Collemaggio 8 Years after the Earthquake (L‘Aquila). International
Archives of the Photogrammetry, Remote Sensing and Spatial Information Sciences, XLII-2/W5, 97-104.

Brumana, R., Oreni, D., Barazzetti, L., Cuca, B., Previtali, M. and Banfi, F. (2020). Survey and Scan to BIM Model for the Knowledge
of Built Heritage and the Management of Conservation Activities. Digital Transformation of the Design, Construction and Management
Processes of the Built Environment, 391-400.

50 FIg. 14 | HBIM interoperability (Brumana et al., 2017)

<!-- p. 51 -->

CASO 06

Denominación Basilica di Santa Maria di Collemaggio
Localización L’Aquila, Abruzzo, Italia
Data s. XIII d.C. (1287-1294)
Autoría Pietro da Morrone
Tipo Edificación religiosa
Estilo Románico - Gótico

Estado de conservación Bueno
Intervenciones Restauración para devolver su aspecto románico, 1972
Restauración tras el terremoto del 2009, 2012

Reconocimiento Monumento
Catalogación

Uso original Iglesia
Uso contemporáneo Iglesia
Visitabilidad Visitable

Bibliografía http://www.santamariadicollemaggio.it/
https://it.wikipedia.org/wiki/Basilica_di_Santa_Maria_di_Collemaggio

Fig.15 | Interior de la basílica (Il Messaggero) 51

<!-- p. 52 -->

Chiesa di Santa María | Brumana, Raffaella et al. (2013)

Investigador Raffaella Brumana, Andreas Georgopoulos, Daniela Oreni, Anna Raimondi, Angeliki Bregianni y Luigi Barazzetti. Politecnico de Milano
Año 2013
Justificación del uso del BIM La lógica de la herramienta BIM se considera adecuada para cumplir con la exigencia de flexibilidad
de representación, con el fin de ser constantemente implementada y actualizada, satisfaciendo la
demanda de transformación continua y rigurosa del modelo de forma constructiva y estratigráfica.

Objetivo Generar un modelado digital como último paso después de los diversos análisis y la revisión e
investigación histórica que incluyan las consideraciones, especialmente centradas en la consecución
de un estudio estratigráfico, que contemplen los cambios sufridos por la iglesia a lo largo de los siglos
y analizar su comportamiento energético.

Método Paramétrico | Semiautomático
Parámetros Fases histórica
Unidades estratigráficas
Resistencia térmica

Resultados El proceso de levantamiento ha permitido documentar, verificar e introducir nuevas fases estratigráficas
del caso de estudio. A su vez se ha podido estudiar su comportamiento energético y observar hipótesis
de coste y consumo de acuerdo a la incorporación de instalaciones.

Conclusiones La herramienta ofrece la incorporación al modelo de una biblioteca interoperable de objetos y datos
espaciales de enfoque multidisciplinario cuyas transformaciones involucran desde la estructura
arquitectónica hasta las capas de acabado. Su análisis resulta de utilidad arquitectónica desde la
perspectiva patrimonial, arqueológica y energética estando sus estudios aún abiertos y susceptibles
de ser profundizados.

Bibliografía Brumana, R., Georgopoulos, A., Oreni, D., Raimondi, A. and Bregianni, A. (2013). HBIM for Documentation, Dissemination and
Management of Built Heritage. The Case Study of St. Maria in Scaria d’Intelvi. International Journal of Heritage in the Digital Era, 2(3),
433-451.

52 Fig. 16 | “Box system” representation of the constructive phases (Brumana et al., 2013)

<!-- p. 53 -->

CASO 07

Denominación Chiesa di Santa Maria
Localización Scaria, Lombardia, Italia
Data s. XV d.C.
Autoría Diego y Carlo Carloni
Tipo Edificación religiosa
Estilo Románico - Barroco

Estado de conservación Bueno
Intervenciones Reconversión al estilo barroco, 1708

Reconocimiento Monumento
Catalogación

Uso original Iglesia
Uso contemporáneo Iglesia
Visitabilidad Visitable

Bibliografía http://www.lombardiabeniculturali.it/architetture/schede/CO160-00031/
https://www.flickr.com/photos/achilleballerini/50862582213

Fig. 17 | Exterior de la iglesia (Lombardia Beniculturali) 53

<!-- p. 54 -->

La Real Colegiata de San Isidoro | Santoni, Arianna et al. (2020)

Investigador Arianna Santoni, Ramona Quattrini, Rafael Martín Talaverano y José Ignacio Murillo Fragero. Università Politecnica delle Marche, Universidad Politécnica de Madrid y Urbe pro Orbe Patrimonio Cultural.
Año 2020
Justificación del uso del BIM La herramienta BIM permite un flujo de trabajo más racional y eficiente a la hora de manejar información
patrimonial del tipo arquitectónico, arqueológico e histórico, creando un único espacio de información
riguroso y completo en forma de modelo 3D interoperable por todos los agentes partícipes de la tutela.

Objetivo Proponer un nuevo método de trabajo que permita reflejar la secuencia de transformación históricas
que se han sucedido en el inmueble a lo largo de su evolución, así como su construcción de acuerdo
a técnicas y materiales incluyendo las diferentes lesiones que forman parte de la integridad actual de
la edificación. Este método permitirá un balance positivo entre los costes adicionales de desarrollar un
modelo BIM de un edificio histórico y los beneficios obtenidos de manera eficaz y viable.

Método Paramétrico | Semiautomático
Parámetros Fases históricas
Sistemas constructivos
Unidades estratigráficas
Links a documentos

Resultados Se ha obtenido un método que permite un modelado eficaz y viable de acuerdo al factor tiempo
incorporando información referente a la evolución histórica y los sistemas constructivos. Para ello se
han creado tablas comparativas del tiempo dedicado a cada elemento del modelo en relación con sus
características y método de modelado. Además se ha creado un sistema de consultas personalizadas
con Dynamo que permite la búsqueda basada en los criterios de identificación y parámetros.

Conclusiones El tiempo dedicado al levantamiento e implementación de información del modelo ha sido comparado
según el empleo de: NURBS o modelado de familias con Dynamo. En el caso de estudio desarrollado
el método NURBS ha dado mejores resultados de acuerdo a tiempo y fidelidad del modelo pero no se
aporta información absoluta ya que depende de varias condiciones como el número de parámetros a
incorporar o el caso de estudio.

Bibliografía Santoni, A., Quattrini, R., Martín Talaverano, R. y Murillo Fragero. J. I. (2021). HBIM approach to implement the historical and
constructive knowledge. The case of the Real Colegiata of San Isidoro (León, Spain). Virtual Archaeology Review, 12(24), 49-65.

54 FIg. 18 | Properties panel of a generic wall with new parameters (Santoni et al., 2020)

<!-- p. 55 -->

CASO 08

Denominación Real Colegiata de San Isidoro
Localización León, Castilla y León, España
Data s. X d.C. - XII d.C.
Autoría
Tipo Edificación religiosa
Estilo Románico

Estado de conservación Bueno
Intervenciones Excavación arqueológica, 2011
Excavación arqueológica, 2014

Reconocimiento Monumento
Catalogación Bien de Interés Cultural BIC 09|02|1910

Uso original Iglesia
Uso contemporáneo Iglesia y museo
Visitabilidad Visitable

Bibliografía http://urbsregia.eu/real-colegiata-de-san-isidoro/
https://www.bimportale.com/hbim-la-real-colegiata-san-isidoro-leon/
http://www.urbeproorbe.com/basilica-de-la-real-colegiata-san-isidoro-leon

Fig. 19 | Exterior de la colegiata (Viajes y rutas) 55

<!-- p. 56 -->

Complejo Medieval Sant ’Apollinare | Piselli, Cristina et al. (2020)

Investigador Cristina Piselli, Jessica Romanelli, Matteo Di Grazia, Augusto Gavagni, Elisa Moretti, Andrea Nicolini, Franco Cotana, Francesco
Strangis, Henk J. L. Witt y Anna Laura Pisello. Università degli Studi di Perugia
Año 2020
Justificación del uso del BIM El levantamiento BIM permite la incorporación de dimensiones técnicas del tipo instalación MEP más
allá de la representación gráfica tridimensional de su geometría y composición. Su potencia permite
generar multitud de hipótesis y su comparación de manera cuantitativa y cualitativa.

Objetivo Evaluar el comportamiento del sistema de climatización en su incorporación a un contexto patrimonial.
El análisis se realiza de acuerdo a la relación espacial entre el inmueble y la instalación, la
retroalimentación de la instalación con las prestaciones constructivas de la edificación y eficiencia
energética del sistema.

Método Paramétrico | Manual
Parámetros Sistema constructivo
Resistencia térmica
Conductividad térmica
Emisividad térmica
Reflectancia solar

Resultados Mediante el modelado del sistema de climatización se han realizado cálculo riguroso del comportamiento
y eficiencia energética de la instalación dentro de su contexto patrimonial real en el levantamiento BIM.
Gracias a los datos y gráficos obtenidos del análisis de distintos sistemas e hipótesis, se han podido
realizar ajustes que mejoran la operabilidad y funcionamiento del sistema de acuerdo al edificó, su
entorno y clima.

Conclusiones La integración de la instalación de climatización ha permitido una lectura contemporánea del modelo
de acuerdo a su multidimensionalidad del centro de información para el mantenimiento, la gestión y el
funcionamiento del edificio, y por lo tanto es una herramienta clave para la gestión de las instalaciones
y del propio patrimonio.

Bibliografía Piselli, C., Guastaveglia, A., Romanelli, J., Cotana, F. and Pisello, A. L. (2020). Facility Energy Management Application of HBIM for Historical Low-Carbon Communities: Design, Modelling and Operation Control of Geothermal Energy Retrofit in a Real Italian Case
Study. Energies, 13(23), 1-18.

Piselli, C., Romanelli, J., Cotana, F., Di Grazia, M., Gavagni, A., Moretti, E., Nicolini, A., Strangis, F., Witte, H. J. L. and Pisello, A. L. (2020).
An Integrated HBIM Simulation Approach for Energy Retroﬁt of Historical Buildings Implemented in a Case Study of a Medieval Fortress
in Italy. Energies, 13(10), 1-21.

56 Fig. 20 | HBIM Back rendered view and front 3D view (Piselli et al., 2020)

<!-- p. 57 -->

CASO 09

Denominación Complejo Medieval Sant ’Apollinare
Localización Sant‘Apollinare, Perugia, Italia
Data s. X d.C. - XI d.C.
Autoría
Tipo Complejo medieval
Estilo Románico

Estado de conservación Bueno
Intervenciones Renovado con introducción de instalaciones y climatización, 2018

Reconocimiento
Catalogación

Uso original Complejo rural de viviendas y talleres
Uso contemporáneo Oficinas y laboratorios, Universidad de Perugia
Visitabilidad Restringida

Bibliografía https://geofit-project.eu/pilots/perugia/
https://www.gbcitalia.org/-/primo-edificio-certificato-gbc-historic-building-le-scuderie-della-rocca-di-sant-apollinare

Fig. 20 | Within the complex of Sant’Apollinare fortress (Piselli et al., 2020) 57

<!-- p. 58 -->

La Antigua Cárcel de la Real Fábrica de Tabacos | Nieto Julián, Juan Enrique (2012)

Investigador Juan Enrique Nieto Julián, Universidad de Sevilla
Año 2012
Justificación del uso del BIM La herramienta permite la participación de grupos multidisciplinares de manera eficiente en todo
el proceso de estudio y análisis. El flujo de información se facilita en su coordinación mejorando la
gestión tutelar y evitando inexactitud o duplicidad de la información.

Objetivo Mejorar el conocimiento de este inmueble recuperando su integridad respecto al proceso de
construcción, rehabilitación y reconstrucción.
Realizar una hipotética rehabilitación donde se aborden procedimientos que permitan la observación
del comportamiento de la herramienta en el modelado del estado actual del inmueble y en un supuesto
de intervención de acuerdo a sus capacidades de levantamiento y gestión multidisciplinar.

Método Paramétrico | Manual
Parámetros Identificación singular de elementos
Fases históricas
Lesiones
Intervenciones

Resultados Mediante el proceso de modelado se ha configurado una metodología que sirve para gestionar de
forma eficaz y productiva la información desde una visión multidisciplinar, permitiendo no solo la
incoorporación de información al modelo sino su análisis. Durante el levantamiento se pudo verificar
información acerca de los sistemas constructivos y sus lesiones, así como corregir datos de tipo
geométrico sobre espesores de elementos.

Conclusiones La herramienta BIM permite el levantamiento del patrimonio desde el análisis interdisciplinar. El trabajo
realizado permite ser continuado y perfeccionado mediante la inclusión de nuevos aspectos de estudio
y potenciales intervenciones.

Bibliografía Nieto Julián, J. E. (2012). Generación de modelos de información para la gestión de una intervención: La cárcel de la Real Fábrica de
Tabacos de Sevilla. Virtual Archaeology Review, 3(5), 63-67.

Nieto Julián, J. E. (2014) Generación de modelos de información para la gestión de una intervención en el patrimonio arquitectónico.
[Tesis de Doctorado, Universidad de Sevilla].

58 Fig. 22 | Sección del modelo de información con ID identificativos (Nieto Julián, 2012)

<!-- p. 59 -->

CASO 10

Denominación La Antigua Cárcel de la Real Fábrica de Tabacos
Localización Sevilla, Sevilla, España
Data 1728-1770
Autoría Ignacio Sala y Garrido, Diego Bordick Deverez y Sebastián Van der Borcht
Tipo Cárcel
Estilo Barroco - Neoclásico

Estado de conservación Bueno
Intervenciones Adecuación como sede de la Universidad de Sevilla, 1956

Reconocimiento Monumento
Catalogación BIC 1959

Uso original Cárcel
Uso contemporáneo Sede del Departamento de Historia Moderna, Universidad de Sevilla
Visitabilidad Restringida

Bibliografía https://institucional.us.es/vrelinstitu/antigua-carcel
http://esasevilla.blogspot.com/2011/09/fabrica-real-de-tabacos-iii-la-carcel.html

Fig. 23 | Fachada principal de la antigua cárcel (Sevilla Daily Foto) 59

<!-- p. 60 -->

Como conclusión de este apartado, además de las fichas se aporta esta tabla final para favorecer el análisis y la
comparativa entre los casos de estudio. Para su realización se han tomado aquellos datos que han resultado de especial
interés durante el proceso de ejecución de las fichas como son especialmente el objetivo específico del levantamiento
y la justificación del uso de la herramienta BIM para lograrlo, o los parámetros empleados en el levantamiento.

Respecto a esto último y gracias a la trazabilidad de la información de la bibliografía, se puede observar una
correspondencia. Los parámetros empleados en el modelo están directamente vinculados al objetivo que se espera de los
levantamientos. En casos como el Conjunto arqueológico de Itálica 1.1.b, la información que se vuelca a la herramienta
es de carácter principalmente arqueológico y arquitectónico ya que su propósito es generar documentación que recoja
el análisis de aspectos como la traza generadora de la antigua ciudad romana, sus elementos de infraestructura,
verificación de niveles, hipótesis de urbanización... en vistas de la creación de un Plan Director. Otro caso en contraste
sería la Basilica di Collemaggio, cuyo objetivo de generar y probar opciones de intervención mediante la producción de
diversos escenarios se obtuvo mediante la aplicación de diversos datos estructurales asociados a parámetros, al igual
que el Complejo Medieval Sant’Apollinare pero en temática de efectividad de sistemas de climatización.

CONJUNTO ARQUEOLÓGICO FACHADA CUADRANTE
CASOS DE ESTUDIO CARTUJA DE JEREZ CASA DE HYLAS
ITÁLICA RENACENTISTA

Localización Jerez, Cádiz, España Santiponce, Sevilla, España Santiponce, Sevilla, España Sevilla, Sevilla, España

Investigador, año Castellano Román, M., 2017 Angulo Fornos, R., 2011 Angulo Fornos, R., 2012 Angulo Fornos, R., 2019

Tipo Monasterio Restos arqueológicos Restos arqueológicos Edificación religiosa

Estado de conservación Bueno Bueno Bueno Bueno

Restauración y limpieza de
Intervenciones - - -
fachada, 2017

Reconocimiento | Catalogación Monumento | BIC 1856 Monumento | BIC 1912 Monumento | BIC 1912 Monumento | BIC 1928

Uso original | Uso contemporáneo Monasterio | Monasterio Ciudad | Zona arqueológica Vivienda | Zona arqueológica Catedral | Catedral

Visitabilidad Restringida Visitable Visitable Visitable

Necesidad de una herramienta Modelo digital capaz de
Estudiar y valorar la
accesible y flexible sin las Gestión problemática y poco contener, gestionar y visualizar
Justificación del uso del BIM complejidad del inmuble en
limitaciones arquitectónicas eficiente de la información información construcitva y de
sus tres escalas
del SIG conservación preventiva

Construir un modelo
Desarrollar un modelo Organización de la información capaz de gestionar la Observar estrategias de
Objetivo gráfico para la gestión interal para la creación de una base información generada en la modelado digital e hipótesis de
interdisciplinar cartográfica, Plan Director. base cartográfica e incluir conservación preventiva
información arquitectónica

Manual x x

Método Semiautomático x x

Automático
Traza generadoras
Fases históricas
Unidades estratigráficas
Identificación singular
Sistema constructivo
Lesiones
Elementos Estado de conservación
Parámetros Intervenciones
Grado de afección
Grado de urgencia
Comportamiento estructural
Cualidades térmicas
Links a documentos
Espacios

Modelo de capas superpuestas
Modelo con relación nominal
Modelo capaz de realizar de acuerdo a las realidades:
de los elementos y espacios e Base cartográfica
Resultados lectura de las trazas materiales, sistemas
información inédita volcada en multidisciplinar y Plan Director
arquitectónicas constructivos, lesiones,
HBIM y HBIR
intervenciones...

El modelo BIM permite la El levantamiento ofrece incluir
BIM como sistema de lectura
BIM como herramienta para el catalogación y vinculación de entidades arquitectónicas a
estratigráfica y de gestión
Conclusiones conocimiento y salvaguarda datos generando todos los un entorno multidisciplinar
pormenorizada de sistemas
del patrimonio documentos para la gestión de carácter principalmente
constructivos
tutelar arqueológico

60 Celia Chacón Carretón

<!-- p. 61 -->

IGLESIA SAN JUAN DEL REAL COLEGIATA COMPLEJO MEDIEVAL ANTIGUA CÁRCEL
BASILICA DI COLLEMAGGIO CHIESA DI SANTA MARIA
HOSPITAL SAN ISIDORO SAN’T APOLLINARE REAL FÁBRICA TABACOS

Valencia, Valencia, España L’Aquila, Abruzzo, Italia Scaria, Lombardia, Itali León, Castilla y León, España Sant‘Apollinare, Perugia, Italia Sevilla, Sevilla, España

Jordán Palomar, I., 2015 Brumana, Raffaella et al., 2014 Brumana, Raffaella et al., 2013 Santoni, A., et al., 2020 Piselli, Cristina et al., 2020 Nieto Julián, J. R., 2012

Edificación religiosa Edificación religiosa Edificación religiosa Edificación religiosa Complejo medieval Cárcel

Bueno Bueno Bueno Bueno Bueno Bueno

Restauración románica, 1972 Excavación arqueológica, 2011 Introducción de instalaciones, Adecuación a la Universidad,
\- Reconversión barroca, 1706
Restauración terremoto, 2012 Excavación arqueológica, 2014 2018 1956

Monumento | BIC 1943 Monumento Monumento Monumento | BIC 1910 - Monumento | BIC 1956

Iglesia | Iglesia Iglesia | Iglesia Iglesia | Iglesia Iglesia | Iglesia y museo Complejo rural | Oficinas Cárcel | Sede Universidad

Visitable Visitable Visitable Visitable Restringida Restringida

Potencialidad de la La lógica de la herramienta Necesidad de una herramienta Necesidad de mejorar el fujo
Necesidad de estudio de Búsqueda de la incorporación
herramienta para representar BIM permite la flexibilidad en de trabajo racional y eficiente de información multidisciplinar
hipótesis de intervención de dimensiones técnicas MEP
fases históricas y trabajar de la representación constructiva para el manejo transversal del para evitar errores en la
urgente tras terremoto en el patrimonio arquitectónico
manera multidisciplinar y estratigráfica patrimonio arquitectónico información

Lograr un método de trabajo Mejorar y unificar el
Definir un protocolo para Generar un modelo que recoja Evaluar el comportamiento de
Realizar construcción digital y que permita reflejar la conocimiento del inmueble
generar una base de datos los análisis de la investigación sistemas de climatización en
probar las hipótesis evolución histórica de manera y realizar un hipotética
multidisciplinar histórica de la estratigrafía el caso patrimonial
eficiente rehabilitación

x x x

x x x

Se ha configurado una
Toma de decisión Método eficaz y viable para Se ha realizado un cálculo
Modelo documentado y metodología de gestión eficaz
Modelo geométrico y biblioteca argumentada tras el estudio incorporar el factor tiempo y riguroso que ha permitido la
verificado contenedor de toda de la información y se ha
histórica medieval del comportamiento de las su construcción. Sistema de decisión por un sistema de
la información del análisis verificado la información del
hipótesis consultas paramétrico acuerdo al inmuble
inmueble

La herramienta BIM permite El método NURBS dentro El modelado del inmuble y el La herramienta BIM permite el
El modelo BIM ha permitido El uso de la herramienta
la incorporación de una de las posebilidades de la sistema de climatización ha levantamiento interdisciplinar
la gestión con información BIM apoya el proceso de
biblioteca interoperable con herramienta BIM es más permitido una lectura técnica y el perfeccionamiento del
histórica minimizando errores y restauración y conservación
condicionantes históricos y eficiente para la tarea de reflejo contemporánea de acuerdo a conocimiento del patrimonio
favoreciendo la transversalidad de los inmubles patrimoniales
estratigráficos histórico la intervención arquitectónico

TFG | Aplicación de la herramienta BIM al patrimonio arquitectónico 61

<!-- p. 62 -->

1.3 | Los factores tutela y resiliencia en el patrimonio arquitectónico

Los inventarios para la protección de los bienes existen desde los
años 30 del siglo pasado, cuando, con la publicación de la Carta de Atenas
(1941), se empezó a crear conciencia de la necesidad de la conservación
del patrimonio. Sin embargo, estos registros se limitaban a recoger sólo los
llamados Monumentos Nacionales, es decir, las edificaciones y obras más
interesantes de cada país por su valor artístico. Será la UNESCO, a partir de
los años 70, el organismo que promoverá el registro y legislación por parte de
cada nación de sus bienes de interés, ampliando el concepto de patrimonio a
todos los aspectos culturales.
Fig. 24 | Diagrama resultado de la gestión del patrimonio como práctica de custodio y vigilacia (Gestión del Patrimonio Mundial Cultural ONU, 2014)

62 Celia Chacón Carretón

<!-- p. 63 -->

La ley de Patrimonio Histórico Español (LPHE) de 16/1985 de 25 de junio, recoge que el patrimonio ha de
protegerse. Es por ello que aquellos bienes que por su relevancia social e histórica y su singularidad necesiten de
protección son declarados Bienes de Interés Cultural, siendo ésta una denominación jurídica de distinción máxima que
se le otorga a un bien a nivel nacional. Los BIC de carácter inmueble recogidos por el Estado son los siguientes:

\| Monumento Histórico: esculturas, obras arquitectónicas o de ingeniería
\| Conjunto Histórico: grupo de bienes inmuebles de carácter histórico que forman un conjunto
\| Jardines Históricos: espacios de elementos naturales elaborados por el ser humano con gran valor estético, o botánico
\| Sitios Históricos: lugares o parajes naturales vinculados a sucesos históricos, tradiciones populares u obra humana
\| Zonas arqueológicas: lugares naturales con presencia de bien mueble o inmueble de interés arqueológico

Según el último informe publicado de 2017, con cifras correspondientes al año anterior, España cuenta con 17.450 BIC
inmuebles y 22.114 bienes muebles.

La ley de Patrimonio Histórico Español (LPHE) se complementa con leyes elaboradas por cada comunidad
autónoma que añaden o modifican ligeramente algunas categorías pero siempre manteniendo la dirección fundamental
marcada por la ley del Estado: protección y difusión. En Andalucía, es la Ley 14/2007 del Patrimonio Histórico de
Andalucía (LPHA) la encargada de regular todo lo relativo al Patrimonio Cultural de nuestra comunidad. Esta ley
supone un avance con respecto a la LHPE, ya que en ella se adopta una visión más amplia del concepto de patrimonio,
se introduce la idea de patrimonio industrial y se crean nuevas figuras de protección como la Zona Patrimonial o el Bien
de Catalogación General. De la misma manera, dispone que la administración pública municipal a la que pertenezca
un BIC está obligada a establecer una estrategia de protección y conservación.

Esto significa que los profesionales del patrimonio no pueden actuar con independencia y sin tomar en
consideración a los demás grupos de interés y pertenencia. Es esencial que los organismos encargados del patrimonio
colaboren en la medida de lo posible con otros interesados para estructurar y aplicar una visión y unas políticas convenidas
a fin de gestionar cada lugar del patrimonio en su contexto físico y social más amplio (UNESCO, 2014). El Consejo
Internacional de Monumentos y Sitios, también conocido como ICOMOS es una asociación civil no gubernamental
ligada a la ONU (Organización de las Naciones Unidas), a través de la UNESCO (Organización de las Naciones
Unidas para la Educación, la Ciencia y la Cultura). Fundada en 1965, como resultado de la Carta de Venecia de 1964,
adoptó su principal objetivo en vistas de promover la teoría, la metodología y la tecnología aplicada a la conservación,
a la protección y a la valorización de monumentos y de sitios de interés cultural. Ello remarca la importancia de las
actividades colaborativas y la participación plena y transparente de los interesados. Cualquier sistema de gestión,
incluyendo la preparación y ejecución de los planes de gestión, debe tomar en consideración estos aspectos. Para
abordar estos objetivos múltiples es necesaria una mayor participación: el aumento de la complejidad requiere avances
en la práctica de la gestión multidisciplinar como se ha recogido en los beneficios del uso del BIM ((Building Smart
Spanish Chapter, 2014). No debe suponerse, sin embargo, que el enfoque vertical, o de arriba a abajo, sea el único
medio de gestionar cuestiones múltiples. Los enfoques de la gestión deben adaptarse a la contemporaneidad y a un
enfoque más amplio e incluyente de la gestión del patrimonio y a la mayor importancia atribuida a la intervención de la
comunidad desde el análisis transversal. El “nuevo paradigma para las áreas protegidas”, elaborado por Adrian Phillips
(2002), destaca con extremada eficacia la mayor importancia atribuída en los últimos años a un enfoque más amplio
e incluyente de la gestión del patrimonio y a la participación de la comunidad (que en algunas partes del mundo ya es
una realidad).

TFG | Aplicación de la herramienta BIM al patrimonio arquitectónico 63

<!-- p. 64 -->

El ejercicio de tutela de un inmueble es el escenario en el cual un arquitecto se enfrenta a una intervención
y mantenimiento de un edificio. La reflexión que se caracteriza por la inversión de tiempo, permite desgranar las
decisiones de proyecto que dieron como resultado dicho inmueble y las que produjeron los cambios que se identifican
en él, y de esta forma extraer aquellos aspectos que lo diferencian. La conservación y transformación debe permitir que
se mantengan vigentes dichos aspectos en convivencia con las operaciones de adaptación, rehabilitación y ampliación
que se propongan en el nuevo proyecto (Boissier Domínguez, 2016). Los edificios son realidades sincrónicas a su
materialidad y espacialidad, y como testigos de actos pasados y detonantes de sucesos presentes no deben ser
tratados como muebles cuya práctica tutela se convierta únicamente en un ejercicio de custodia y vigilancia propio
de realidades de carácter museístico (UNESCO, 2014). Como señaló Sennett (2019), es distinto el medio construido
del cómo vive la gente en él. Lo físico, organizativo, planificado; de lo vivido, lo sentido, lo experienciado; los espacios
son sobre todos las personas que lo habitan y no un espacio habitado por personas. Además, estas personas no
son personas aisladas sino personas que establecen vínculos y redes que conforman la sociedad. Cuando mejora la
capacidad de resiliencia de un sistema, agentes y comunidad, está mejor preparado para tolerar las perturbaciones
(Xu, Marinova y Gou, 2015).

Por otra parte, la sociedad evoluciona muy rápido; los avances tecnológicos y concretamente el mundo AEC
han cambiado la apreciación de las realidades construidas, y por tanto la sociedad, los sistemas de comunicación, el
acceso a la información y la capacidad de relación de los agentes patrimoniales (Romero Moragas, 2017). El mayor
alcance actual del patrimonio ha hecho que en su gestión intervengan muchos más agentes o grupos de interés en vistas
de la determinación de descifrar los sistemas de significados que de los valores patrimoniales (Pinto Puerto, 2018).
Cuando los lugares del patrimonio eran principalmente monumentos o edificios bajo control público, el administrador
podía gozar de una relativa autonomía dentro de los límites del Bien. Actualmente esto ha cambiado, aunque un bien
patrimonial sea de propiedad y administración públicas, el administrador del Bien deberá colaborar con los grupos de
interés y las autoridades competentes en el área circundante. En los bienes más extensos del patrimonio la propiedad
estará mucho más dispersa. Las comunidades locales pueden depender para su subsistencia de estos usos lucrativos
de los lugares del patrimonio (Martin y Piatti, 2009).

En una actualización de la metodología en lo referente al patrimonio cultural, el desarrollo sostenible puede
enfocarse desde dos ángulos: como el interés en sostener el patrimonio, considerado como un fin en sí y como parte de
los recursos ambientales/culturales que deben protegerse y transmitirse a las generaciones futuras para garantizar su
desarrollo; y como la contribución que el patrimonio y su conservación pueden aportar a las dimensiones ambientales,
sociales y económicas del desarrollo sostenible (UNESCO, 2014). Este enfoque parte de la premisa de que los
miembros de la sociedad atribuyen valores diversos al patrimonio, entre los que cobrarán valor en el futuro estarán
los patrimonios que favorezcan la resiliencia, entendida como la capacidad que tiene un sistema social para absorber
o resistir alteraciones y otros factores de estrés, de tal modo que el sistema permanezca en las mismas condiciones,
manteniendo en esencia su estructura y funciones, es decir la capacidad para auto-organizarse, aprender y adaptarse.
Conocer, recuperar e incorporar estos saberes y usos locales, probadamente sostenibles al ser fruto de una larga
interacción histórica de las comunidades con sus territorios, unido a los nuevos conocimientos que ofrecen prácticas
como la permacultura, va a ir cobrando un interés creciente, que a su vez abundará en garantizar el conocimiento y
conservación de una parte importante del patrimonio cultural inmaterial (Carrera Díaz, 2016).

Este acercamiento permite la adaptación a nuevos usos, que les confieren una función que garantiza su
continuo mantenimiento y su relevancia para la sociedad siendo los miembros de la sociedad los que atribuyen valores

64 Celia Chacón Carretón

<!-- p. 65 -->

diversos al patrimonio y salvaguardan su realidad de uso y domesticidad en casos habitables. Este concepto se explicó
en más detalle en los trabajos de James Kerr (2013) sobre los planes de conservación. y, lo que es más importante,
de la significación cultural para la sociedad de un lugar del patrimonio. Por tanto, y en lo que a la tutela respecta, las
agendas urbanas no se centrarán en los espacios, sino en las personas que los habitan; en la ciudad como espacio
donde tienen lugar estas relaciones diversas como foco de interés principal y en la convivencia de todos para un mayor
bienestar (Lledó, 2018). El patrimonio arquitectónico es por tanto una de las cristalizaciones o materializaciones más
relevantes. Domínguez Pérez (2019) lo recoge en forma de dicotomía espacial explicando que el patrimonio sería
un elemento que cuenta con dos funcionalidades, una hacia fuera y otra hacia dentro. Hacia fuera, como elemento
de atractivo cultural. Y hacia adentro, para consolidar y materializar los lazos entre los residentes, que a través del
patrimonio construyen y recrean su identidad. Así el patrimonio refleja todo el cúmulo de saberes, cultura, historia, etc
de las comunidades, de manera simbólica. Con ello, puede conocerse la comunidad a través de sus símbolos, sus
cristalizaciones, su patrimonio.

En la otra dirección, del investigador hacia el conocimiento, se plantea una revisión del concepto de tutela a
raíz de la tecnología digital y su relación con la información. Implica superar la percepción instrumental de la tecnología
digital en el desarrollo de los procesos que siguen siendo tradicionales. La tecnología digital y la ciencia que la acompaña
implica una nueva manera de posicionarse ante la complejidad de la realidad patrimonial permitiendo afrontarla evitando
soluciones reduccionistas. Desde el enfoque del levantamiento digital como parte de la acción tutelar Pinto Puerto
recalca la articulación en grupos activos de investigadores y técnicos como es el caso de la IAPH, de los requerimientos
en el uso e instrumentalización de la información, la permanencia y sostenibilidad de esta información en el tiempo, su
accesibilidad o los modos de conocimiento (2018).

A este respecto y como conclusión parcial, se recoge que el proceso que entorna la realidad del patrimonio
arquitectónico concretamente se polariza en su cristalización o resiliencia (Domínguez Pérez, 2019; Romero Morgas,
\2017) en consecuencia de su gestión multidisciplinar herencia de los agentes poseedores de su tutela. Su desarrollo como
realidades inmuebles complejas reconocidas y catalogadas, argumenta su protección, pero no es sino entendimiento
como la complejidad de su sistema de espacios y de los escenarios que provoca su entendimiento integral y su auto
salvaguarda.

TUTELA

cristalizado resiliente

Fig. 25 | Diagrama graduación de la tutela entre la resiliencia y la cristalización del patrimonio arquitectónico (Elaboración propia)

TFG | Aplicación de la herramienta BIM al patrimonio arquitectónico 65

<!-- p. 66 -->

1.4 | Parámetros

1.4.1 | La parametrización en el modelo BIM

Como se ha puesto de manifiesto en el apartado 1.1 y 1.2, uno de los aspectos que más interesan en el
desarrollo de esta investigación es el empleo de parámetros a la hora de definir la arquitectura patrimonial. Su cualidad
como estructura informacional (Murphy et al., 2009) permite asociar información de manera directa a los elementos,
espacios y proyectos y a su vez generar tablas o repositorios de información externa, como el HBIR (Heritage Building
Information Repository); todo ello con inclusiones no únicamente del tipo dato asociado a las localizaciones que la
herramienta BIM admite, sino además de tipo planimetría histórica, archivos documentales, imágenes, información URL
(Uniform Resource Locator, Localizadora Uniforme de Recursos)… En revisiones del estado actual del conocimiento
como la de Hichri et al. (2013) se incluye implícitamente la categorización de los modelos en paramétricos o no
paramétricos debido a la consideración del uso de parámetros como método ya definido por la experimentación. El
modelo BIM con gestión activa de parámetros implica la simplificación, al menos inicial, de la geometría mediante
análisis previo (Angulo Fornos, 2020), pero aporta la potencialidad de la la variabilidad prácticamente infinita que
presenta esta herramienta permitiendo ordenar la información de manera objetiva y racional de acuerdo a aspectos
concretos que permiten focalizar el resultado del levantamiento según el caso como se ha podido comprobar en los
casos de estudios reflejados en el apartado 1.2.2.

66 Celia Chacón Carretón

<!-- p. 67 -->

Dentro del proceso de levantamiento se diseña una estructura de parámetros asociados a los diferentes
elementos del modelo gráfico, que permite registrar información patrimonial sobre los mismos. En el despliegue del
grupo de parámetros este se subdivide en elemento y espacios, ya que una de las primeras conclusiones que se han
efectuado tras el análisis de los casos de estudio, es la posibilidad de definir ambas realidades de manera paralela
permitiendo valorar la obra patrimonial de manera integral desde el punto de vista no sólo constructivo sino también
arquitectónico, incluyendo aspectos intrínsecos con el comportamiento del inmueble y por tanto su valoración integral
objetivo de la reflexión sobre la contemporaneidad de la gestión. Como se puede observar en el levantamiento de la
Cartuja de Jerez por Castellano Román (2017), esa pormenorización ha sido posible tras un análisis de sus elementos
,desde su materialidad a sus sistemas constructivos, lo que ha llevado a la objetivación de la definición de los espacios,
caso de estudio 01 del apartado 1.2.2.

La definición de parámetros dentro de la herramienta BIM permite modelar estructuras básicas de la edificación:
muros, suelos, cubiertas, elementos estructurales, etc., estando estos elementos programados con opciones de edición
avanzadas que permiten caracterizar un número ilimitado de contenidos, así como un repertorio igualmente ilimitado de
soluciones gráficas para su visualización. Su utilización progresiva en el tiempo, a base de adiciones y actualizaciones,
permite un incremento directamente progresivo del LOD. Algo habitual sucede al diseño conceptual mediante masas
genéricas, permitiendo en un primer momento su definición únicamente volumétrica y a posteriori añadir información
sobre su posición, dimensión exacta, materialidad… En cualquier caso, la estructura de parámetros ya intrínseca en el
software no impide o contradice la inclusión de nuevos parámetros para la caracterización de los diferentes elementos
del modelo. Las diferentes familias con las que se modela en el programa ofrecen una serie de parámetros que pueden
ser perfectamente compatibles con la información patrimonial (Castellano Román, 2017). Sería el caso del parámetro
material, que puede utilizarse para registrar la naturaleza constructiva de los elementos sin más consideración,
definiendo dicho parámetro de acuerdo al material del elemento. De igual manera, la herramienta permite la duplicación
y modificación de una parámetros existente en su biblioteca para el cambio o adición de información del tipo: resistencia
a compresión, resistencia térmica, textura…

Fig. 26 | Esquema de caracterización de los Niveles de Conocimiento en un modelo HBIM (Castellano Román, 2017)

TFG | Aplicación de la herramienta BIM al patrimonio arquitectónico 67

<!-- p. 68 -->

En la relación LOD con la secuencia LOK asociada al HBIM, expuesta en la Fig. 26, este desarrollo de nuevo
responde al conocimiento que se tenga del inmueble (Castellano Román y Pinto Puerto, 2019) relativa al nivel de
complejidad que se requiera alcanzar con el levantamiento, ya que si no se conoce la información de algún parámetro se
puede o atribuir o no completar, ocasionando que por tanto en los casos de edificios patrimoniales el nivel que alcance
la representación refleje directamente el nivel de conocimiento que se posea sobre ella incluyendo la información
multidisciplinar completa.

En relación específica con el programa Revit ®, la opción de parámetros compartidos consiste en un formato
.txt, y como tal puede ser abierto con cualquier editor de texto, si bien el entorno de cuadros de diálogo y tablas de
planificación que incorpora el programa es el más aconsejable (Jordán Palomar et al., 2018). Los parámetros creados
pueden configurarse de tipo longitud, superficie, texto, si/no... según la naturaleza de la información que se desee
que contengan, al igual que su denominación y sistema de ordenación es totalmente codificable. Dado que estos
parámetros están contenidos en un archivo externo, pueden ser usados en tantos archivos de proyectos y familias
como sean requeridos produciendo su carga en ese archivo.

Por último, respecto a la potencialidad de usos, existen estudios sobre la gestión del rendimiento de los entornos
de los edificios mediante esta metodología. A través del análisis mediante parámetros se pueden proponer diversas
hipótesis para apoyar la toma de decisiones necesaria para la gestión del rendimiento energético de los edificios en
proyecto o construidos en entorno BIM. La propuesta de un marco digital para la gestión inteligente de activos miden
el efecto de la herramienta en la gestión de la energía de los edificios. También mediante el uso de parámetros en
relación con sistemas MEP se mejora el método de monitorización del rendimiento energético mediante una simulación
paramétrica como parte del movimiento (Manfren et al., 2020).

En el caso de una edificaciónpatrimonial, los parámetros de los objetos del modelo HBIM se suelen organizar
facilitando su ordenación basada en disciplinas que establecería conjuntos de propiedades históricas, arqueológicas…
más convencionales, o según las áreas de tutela convencionalmente reconocidas: identificación, investigación,
protección, conservación, difusión, y dentro de cada una de ellas mediante subgrupos que facilitan la ordenación de los
parámetros con objetivo de mejorar la gestión de la información puramente multidisciplinar. En todas las estructuras el
sistema de información logra crear un mapeo de datos semántico que se puede aplicar activamente y es extraíble en
forma de documentación planimétrica, informes, tablas… usando un único sistema de entrada de información (Santoni
et al., 2021).

En conclusión a este apartado y como razón fundamental del desarrollo del levantamiento, la parametrización
permite el avance del modelado gráfico tridimensional básico mediante elementos genéricos y una estructura de
información orientada hacia su análisis multidisciplinar y de sus realidades de manera integral, al establecer las
directrices generales de su planificación representacional. Su precisión depende del propósito del creador de ese
modelo (González Pérez, 2018) siendo el resultado un modelo interactivo basado en lenguajes comunes de recursos y
mecanismos mentales actuales adscritos no solo a la representación gráfica más tradicional.

68 Celia Chacón Carretón

<!-- p. 69 -->

TFG | Aplicación de la herramienta BIM al patrimonio arquitectónico 69

<!-- p. 70 -->

1.4.2 | La parametrización de la habitabilidad

La arquitectura -material, sistema, elemento, espacio, complejo, imagen…- establece relaciones entre técnica
y sociedad para la creación de una co-habitabilidad humana (Moreno Pérez y García de Casasola Gómez, 2017). En el
caso específico del patrimonio, su valoración y protección resulta un añadido a su realidad arquitectónica, y por tanto el
interés que despierta su mantenimiento resultaría insatisfactorio si no se ratifica su condición de enriquecimiento de la
vida humana (Rueda, 1996). De esta manera, la Unión Mundial de la Conservación (Programa de Medio Ambiente de
las Naciones Unidas y del Fondo Mundial para la Conservación de la Naturaleza), indicaba en 1991 que “el desarrollo
sostenible implica la mejora de la calidad de vida dentro de los límites de los ecosistemas” siendo el concepto tradicional
de habitabilidad entendido en relación al confort ambiental aceptado por parte de los usuarios en las condiciones en las
que efectúan actividades. Hoy en día la habitabilidad se entiende con un alcance más amplio de espectro cuantitativo
y cualitativo determinada por la adecuación de cada una de las escalas territoriales. En la misma línea, el concepto
de “vivienda saludable”, desarrollado por la Organización Mundial de la Salud, abarca la prestación funcional y el
adecuado desarrollo físico, social y mental de las condiciones de salud, la seguridad, higiene, comodidad y privacidad
(2000).

70 Celia Chacón Carretón

<!-- p. 71 -->

Como se evidencia en estos acercamientos, la definición de habitabilidad incluye un trabajo de determinación
de los factores y variables que permiten establecer unos estándares de bienestar habitacional con un criterio transversal
de lectura en relación con el ambiente y la comunidad (D´Alençon et al. 2009). El enfoque determinante a la habitabilidad
de los espacios se abandona en los casos patrimoniales pasando a un segundo plano en favor de la tutela, de manera
que las cualidades relativas al confort y la salud quedan subordinadas a la conservación y protección del inmueble
provocando divergencias y contradicciones de acuerdo a las exigencias aplicadas a otras construcciones.

Dentro de este movimiento las razones responden a la habitabilidad de los espacios de igual manera; en un
momento del desarrollo funcional del Convento, las clarisas deciden mudar su espacio vividero nocturno al ala de
celdas suroeste de menor calidad patrimonial pero más receptiva conforme a prestaciones como la accesibilidad de
las habitaciones, la posibilidad de disponer de sistemas de calefacción, la presencia de ventanas de mayor tamaño
que favorecen la iluminación y la ventilación… prestaciones que no solo no se permitirían en las celdas originales del
claustro sino que supondrían cambios ambientales como por ejemplo la temperatura interior que no serían compatibles
con el mantenimiento previsto para la protección de revestimientos como frescos o trabajos artesanales históricos de
la madera del artesonado… De igual manera, existen otros aspectos de las celdas originales que a pesar de no estar
en relación con aspectos concretos de su patrimonialidad arquitectónico-artística como lo son sus acabados, dependen
directamente de su formalidad y que por tanto tampoco permiten su modificación de nuevo por el nivel máximo de
protección que se le ha conferido.

En los casos de estudio recogidos en esta investigación se elaboraron levantamientos de espacios habitables,
en menor medida de acuerdo a su uso temporal ya que ninguno de dichos casos son de tipo residencial, como la
Iglesia San Juan del Hospital siendo un espacio de culto de uso actual y reiterado, otros como el complejo medieval
Sant’Apollinare cuya modelo HBIM se efectuó desde una visión de análisis de una hipótesis de intervención más
permisiva de acuerdo a los cambios que se efectuaron en los espacios a base de la adición de sistema de climatización…
y finalmente el caso más similar al desarrollado en esta investigación, la Cartuja de Jerez.

Fig. 27 | Galería Claustro principal (Pablo M. Millán Millán) 71

<!-- p. 72 -->

El levantamiento se realizó incorporando parámetros que permitieron medir el comportamiento de la tutela en
sus cuatros bases: identificación, protección, conservación y difusión (Castellano Román, 2017), llegando a conclusiones
que permitieron no solo salvaguardar el conocimiento que se posee de dicho patrimonio mas incorporar nuevas visiones
dadas del análisis contemporáneo a través del uso de la herramienta BIM. Respecto a su comportamiento habitacional,
se desarrolló un extenso estudio previo que recoge todas las fuentes y por tanto crea un mapa de lo que fue el devenir
hasta la actualidad del inmueble culminando con el estado actual; las hermanas de Belén son las actuales residentes
de este espacio y por tanto permiten su salvaguardia diaria. La domesticidad de un espacio está ligada directamente a
la presencia de sus habitantes (Boissier Domínguez, 2016), y sus exigencias se revierten o no en el espacio; en este
caso este aspecto se tiene en consideración únicamente desde una visión de presencia y funcionamiento de acuerdo
a la visitabilidad del complejo, otros de los factores que Catellano Román tiene en cuenta y refleja en su levantamiento,
pero no se valora la habitabilidad de ellos más allá del estado de la edificación totalmente en relación con exigencias
patrimoniales.

En la aproximación a la potencial medición de la habitabilidad de un inmueble se produce un primer
acercamiento a lo que supone la características y prestaciones de los elementos de la construcción que permiten su
cumplimiento para después concretar estas cualidades asociadas a espacios. El interés en estos conceptos radica en
que amplían el ámbito de la evaluación de la calidad de las prestaciones de las edificaciones, tanto en la variedad de los
problemas considerados como en las escalas de análisis e intervención, permitiendo además la objetivación y por tanto
el tratamiento absolutamente técnico y contemporáneo de su estudio con fines como la investigación y la potencial
intervención o mejora en la gestión de su tutela. Para fijar los estándares de confort en virtud del concepto habitabilidad,
se han determinado los siguientes parámetros respondiendo a la bibliografía recogida en este capítulo, entre ellas las
indicaciones sobre cómo mejorar el desempeño de los sistema de salud de la OMS (2000) y a la normativa vigente
respecto a exigencias de los espacios habitables del Código Técnico de la Edificación de España. Una técnica útil para
los bienes complejos o los bienes, en particular culturales, que presentan múltiples atributos organizados en niveles
complejos, consiste en situar en un mapa los atributos importantes y los valores que estos confieren al bien. Ello
puede ayudar a entender la relación existente entre los atributos, y también dar a conocer los conflictos o problemas
de gestión, y es esencial para trazar los límites según el Manual de referencia del Patrimonio Mundial: Elaboración de
propuestas de inscripción en la Lista del Patrimonio Mundial (2010).

Según el Real Decreto 235/2013, de 5 de abril, por el que se aprueba el procedimiento básico para la
certificación de edificios existentes, en la situación de un espacio de vivienda existente, para poder considerarse
como tal debe tener y cumplir unas condiciones, de lo contrario se supone que la vivienda no es habitable y por lo
tanto no se podría considerar como tal. El cumplimiento con estos mínimos se acredita con un certificado técnico
que se denomina certificado de habitabilidad, y si este certificado que debe ser redactado por un técnico cualificado
(arquitecto, arquitecto técnico o Ingeniero de la edificación) es favorable, entonces la Administración correspondiente
otorga lo que se denomina la cédula de habitabilidad, la cual respalda y acredita la habitabilidad de la vivienda. Las
características de habitabilidad de las viviendas están reguladas por cada comunidad autónoma a través de normas
o decretos municipales o autonómicos, las cuales pueden variar en cuanto a valores de referencia sin perjudicar o
menospreciar en ningún caso a las garantías mínimas de habitabilidad exigidas en el Código Técnico de la Edificación
(CTE), por lo que para la creación de los parámetros espaciales se tendrá en cuenta esto último, ya que permite mayor
transversalidad y concreción en la medición.

72 Celia Chacón Carretón

<!-- p. 73 -->

Como último a este respecto recalcar que tal y como se recoge en CTE, en las intervenciones en los edificios
existentes no se podrán reducir las condiciones preexistentes relacionadas con las exigencias básicas, cuando
dichas condiciones sean menos exigentes que las establecidas en los documentos básicos del CTE, salvo que en
éstos se establezca un criterio distinto. Las que sean más exigentes, únicamente podrán reducirse hasta los niveles
de exigencia que establecen los documentos básicos. El CTE se aplicará también a intervenciones en los edificios
existentes teniendo en cuenta que dicha acción sea incompatible con la naturaleza de la intervención o con el grado de
protección del edificio, se podrán aplicar, bajo el criterio y responsabilidad del proyectista o, en su caso, del técnico que
suscriba la memoria, aquellas soluciones que permitan el mayor grado posible de adecuación efectiva.

El nivel de habitabilidad resultado de todos los procesos de evaluación pormenorizados expuesto, será una
herramienta para informar a las instituciones vinculadas y agentes, sobre la realidad de las condiciones de habitabilidad
en relación con la tutela. El uso de esta herramienta permitiría conducir los recursos de manera más eﬁciente por
encima de las circunstancias de cada programa, al tener una perspectiva más completa y objetiva de los problemas
que se abordan.

Los principales ámbitos de aplicación, dentro de los programas relevantes son:

\| Como herramienta de evaluación preliminar, para la focalización de los proyectos de intervención y
mantenimiento.
\| Como herramienta para establecer requerimientos especíﬁcos asociados a los objetivos de cada programa,
exigiendo ciertos cumplimientos en los niveles de desempeño.
\| Como herramienta de estudio y reflexión sobre la domesticidad siendo un factor sincrónico en el desarrollo
histórico de los inmuebles patrimoniales.

Este último punto responde a la primera instancia de esta investigación, que de nuevo incide en el análisis
contemporáneo del patrimonio desde la adición de el factor habitabilidad a su visión global con el fin de fomentar la
transversalidad e integridad del conocimiento.

Es por ello que en esta investigación uno de los objetivos se focaliza en determinar dichos factores y variables
para su traducción paramétrica a la hora de representar gráficamente esta convivencia en la herramienta BIM con
la finalidad de poder objetivar la práctica de estas dos realidades: la patrimonial y la habitabilidad. Para ello y como
conclusión de este apartado se proponen los siguientes parámetros para el control y medición de la habitabilidad en
casos patrimoniales. Con ellos se pretende implementar lo recogido en la investigación aportando una nueva perspectiva
al conocimiento del campo del BIM aplicado al patrimonio arquitectónico. Su utilización se recoge de manera directa en
el apartado 2.3.2, por lo que los diagramas explicativos que se exponen a continuación responden al caso de estudio
el Convento de Santa Clara de la Columna, aunque los datos que traducen gráficamente responden a la definición
paramétrica pormenorizada de la consecuencia habitable de los elementos y espacios de los inmubles patrimoniales.
Consecuentemente, esta elaboración de parámetros puede ser aplicada en otros bienes patrimoniales arquitectónicos.

TFG | Aplicación de la herramienta BIM al patrimonio arquitectónico 73

<!-- p. 74 -->

A continuación se indican los parámetros a los que se han llegado tras la investigación y reflexión hasta este
capítulo: junto con los mencionados diagramas que pretenden la conceptualizaicón de los mismos:

IDENTIFICACIÓN
\| Número
\| Nombre
\| Imagen
\| Comentarios
\| Fase histórica

GEOMETRÍA
\| Área
\| Perímetro
\| Altura sin límites
\| Volumen
\| Orientación

TEMPERATURA
\| Transmitancia térmica de los materiales y sistemas
\| Estanqueidad de los sistemas

ACÚSTICA
\| Absorción acústica de los materiales y sistemas

VENTILACIÓN
\| Dimensión de los huecos
\| Caudal de ventilación

INSTALACIONES
\| Eléctrica
\| Fontería
\| Saneamiento
\| Ventilación
\| Climatización
\| Telecomunicación

ILUMINACIÓN NATURAL

\| Situación del espacio
\| Dimensión de los huecos
\| Orientación de los huecos

ILUMINACIÓN ARTIFICIAL

\| Lúmenes

ACCESIBILIDAD
\| Dimensiones de pasos
\| Presencia de escaleras
\| Discontinuidades en el pavimento

PRIVACIDAD
\| Altura de los huecos
\| Sistemas de compartimentación
\| Sistemas de cierre de huecos

74 Celia Chacón Carretón

<!-- p. 75 -->

identificación geometría

temperatura acústica

ventilación instalaciones

iluminación iluminación
natural artifical

accesibilidad privacidad

Fig. 28 | Diagrama conceptualización parámetros habitabilidad (Elaboración propia)

TFG | Aplicación de la herramienta BIM al patrimonio arquitectónico 75

<!-- p. 76 -->

76 Celia Chacón Carretón

<!-- p. 77 -->

Capítulo 2 | Experiencia

TFG | Aplicación de la herramienta BIM al patrimonio arquitectónico 77

<!-- p. 78 -->

78 Celia Chacón Carretón

<!-- p. 79 -->

Fig. 29 | Camino SO (Jesús Mayora) 79

<!-- p. 80 -->

2.1 | Caso de estudio | El Convento de Santa Clara de la Columna, Belalcázar

El Convento de Santa Clara de la Columna es el resultado de unas circunstancias históricas en un tiempo
y espacio determinado. Todos los valores que recoge están estrechamente ligados a variables políticas, sociales,
económicas y culturales como detonante a la hora de surgir esta institución y su devenir en el tiempo, por ello es
oportuno realizar una breve reseña que favorezca la comprensión del cenobio en toda su dimensión.

Situado en el municipio cordobés de Belalcázar, el Convento de Santa Clara de la Columna constituye uno
de los pilares fundamentales del patrimonio histórico, artístico y arquitectónico de los Pedroches. Siendo el mayor
convento de la provincia, forma parte de las fábricas conventuales de la Córdoba Medieval y su ámbito territorial es
seña de los primeros brotes del Renacimiento. Por su extensión, sus artesonados policromados y arquitectura, está
considerado el segundo monumento histórico-religioso, en importancia, de la provincia de Córdoba, después de la
Mezquita Catedral de la capital. Su localización sureste a aproximadamente 1km del Ayuntamiento lo carcateriza por su
singularidad en medio del entorno rural con escasas edificaciones circundantes y una topografía relativamente plana.
Otros focos de interés de este emplazamiento son el Castillo de los Sotomayor y Zúñiga de estrecha relación familiar y
constructiva, la iglesia parroquial de Santiago el Mayor, el puente romano...

80 Celia Chacón Carretón

<!-- p. 81 -->

Toda la documentación consultada para el desarrollo de este apartado se ha recogido en la bibliografía
queriendo destacar de manera especial el libro El Convento de Santa Clara de la Columna de Belalcázar de Juan
Andrés Molinero Merchán (2007) quien como historiador del arte realiza un profundo análisis historiográfico de esta
obra siendo una de las obras cumbre del primer Renacimiento cordobés. Su trabajo recoge todas las fuentes escritas:
documentales, bibliográficas, iconográficas, fotográficas, epigráficas y gliptográficas que existen hasta el momento de
la publicación de este compendio. Este trabajo de documentación ha permitido el entendimiento del funcionamiento del
inmueble, ya que entre sus aportaciones genera la hipótesis de crecimiento del Convento empleada en el apartado del
levantamiento 2.2.5.

A continuación se recoge de manera resumida y sistemática aquellos hitos más importantes sucedidos en
el transcurso de los siglos de la historia del Convento de Santa Clara de la Columna de acuerdo principalmente a
su construcción y desarrollo arquitectónico. Para ello, se ha dispuesto el momento del acontecimiento en formato
año|mes|día si se conocen los tres datos y un pequeño epígrafe del asunto. De no especificarse o tener conocimiento
del momento temporal exacto se señalará únicamente la fase y el siglo.

Destacar en primer lugar que la fundación del Convento se debe a la primera condesa de Belalcázar, Elvira de
Zúñiga, quien junto a sus hijas, acudía con gran asiduidad a este monasterio para rezar y retirarse a la meditación, por
lo que construyeron unas casas colindantes para ellas y sus criados, formando de esta forma la mencionada Villeta de
Santa Clara. En un principio, fue construido para albergar a los frailes Franciscanos por lo que se le puso el nombre de
monasterio de San Francisco.

Ayuntamiento

0,5km

Fig. 30 | Mapa Belalcázar (Fototeca del Centro Nacional de Información Geográfica, Ministerio Transportes Movilidad y Agenda Urbana de España) 81

<!-- p. 82 -->

\| Fase 1: Convento primitivo s.XV

1464 Inicio de la construcción tras la viudedad de D.ª Elvira de Zúñiga

1474 Primeras referencias documentales de la finalización de la construcción

1476 Fundación por D.ª Elvira de Zúñiga

1483 Muerte de D.ª Elvira de Zúñiga. Sus hijas, Leonor e Isabel lo convierten en cenobio femenino para profesar
la religión católica en clausura

\| Fase 2: Ampliación época de los frailes s.XV

1486 Los frailes son autorizados por Inocencio VIII para la posesión del nuevo convento

1490 Los frailes abandonan el recinto tomando posesión de otro edificio más cercano al pueblo

1493 La congregación se desliga de la Custodia de Santoyo y pasa a ser acogida por Santa Maria de los
Ángeles fundada por por Fray Juan de la Puebla, hijo de Doña Elvira de Zúñiga

1494|02|21 Llegada de las monjas procedentes del Convento de Nuestra Señora de la Consolación de Calabazanos
(Burgos). Traen consigo un trozo de la Columna en la que ataron a Jesucristo para azotarle, razón de la
denominación desde este momento del convento: Santa Clara de la Columna.

Añadido de una nueva dependencia paralela a la iglesia como panteón familiar. Esta nueva dependencia
se bautizó con el nombre de capilla de San Benito. Actualmente se le conoce como Capilla o Auditorio.

\| Fase 3: Reforma época de las monjas s.XVI

1500 Ampliaciones y modificaciones para su adaptación a las necesidades de los condes y de las nuevas
inquilinas. Las reglas de una orden masculina son diferentes a las femeninas.

1544|11|01 En su última voluntad y testamento firmado, Francisco de Zúñiga y Guzmán Sotomayor, tercer duque
de Béjar, pide su entierro en el monasterio de San Francisco en Belalcázar. Hasta que este fuera terminado,
su cuerpo debía reposar en la capilla de San Benito del convento de Santa Clara.

\| Fase 4: Ampliación época de las monjas s.XVII

Debido al aumento de clarisas se culmina la ejecución del segundo Claustro, conocido como Claustro
Nuevo con la adición del nuevo Ala de Celdas. Esta construcción es de menor valor arquitectónico debido a
la labor apresurada de su creación.

Del mismo modo aparece la Casa de Oración y los Locutorios en relación con el espacio de la fuente Samaritana.

82 Celia Chacón Carretón

<!-- p. 83 -->

Fig. 31 | Evolución morfológica (Elaboración propia a ráiz de ortofoto Google Earth)

Fig. 32 | Evolución morfológica del contexto 1945 | 1973 | 1998 | 2019 (Fototeca Centro Nacional De Información Geográfica)

Fig. 33 | Planta baja de las Gradas (Pablo M. Millán Millán) 83

<!-- p. 84 -->

1982|08|27 El Convento es declarado Bien de Interés Cultural

1990|04|01 Inicio de las obras de restauración por el arquitecto Arturo Ramírez. Consejería de Cultura Junta de Andalucía.

2000|10|01 Terminación de las obras de restauración.

2015|03|01 Intervención por el arquitecto Pablo M. Millán Millán.

El municipio se nutre igualmente de este complejo inmuble realizando cines de verano, representaciones
teatrales y muchos otros tipos de actividades con el Convento como telón de fondo. Es muy habitual en las noches de
verano encontrar el patio trasero de las Gradas colmatado de belalcazareños disfrutando de algún hito cultural al frescor
de la noche. En ocasiones también se han realizado exposiciones, cursos y talleres siempre en contacto con el exterior
sureste de la finca con vistas a la vegetación. La visita al Convento permite el acceso a las dependencias que no son
de clausura o de trabajo de labor de las clarisas, como es el Templo, la Capilla, el Claustro, la Enfermería, la Casa de
Oración y las Gradas. Sumado a esto, su realidad diaria se caracteriza por el trasiego de la comunidad de monjas que lo
habita quienes desempeñan labores de preparación de actos litúrgicos, tareas de mantenimiento y limpieza doméstica
de los espacios, elaboración de dulces tradicionales... La visita es posible mediante guías dispuestas semanalmente.

La domesticidad del Convento es la razón principal de su funcionamiento y uso, este tipo de construcciones
desarrolladas a raíz del propio movimiento orgánico de la necesidad de crecimiento produce piezas que se van
adhiriendo a un corazón central, el claustro, según las nuevas competencias que se le requiera a esta “ciudad dentro
de ciudad” (Hidalgo Prieto, 2010).

Otros aspectos descubiertos en la investigación que podrían continuar profundizando la definición de la
habitabilidad del Convento es la estacionalidad de los espacios. Las costumbres, celebraciones, labores y eventos
que se suceden dentro de este complejo inmueble suponen un valor identitario y de conservación de la forma de
vivir de una comunidad totalmente partícipe del lugar que habita. La monumentalidad de este conjunto transgrede los
límites materiales de carácter histórico-artístico en favor de la arquitectura y la sociología, una dimensión que no solo
enriquece su patrimonialidad sino su longevidad y adaptación en el tiempo, ya que siendo una estructura fundada
en el siglo XV se ha conseguido adaptar a las múltiples menesteres y como resultado, nunca final, se presenta en
la contemporaneidad como el espacio patrimonial cuya configuración jamás podrá ser determinada únicamente por
su formalización en cartas, constituciones, boletines… pues su realidad y comportamiento es un flujo colaborativo
perteneciente a la complicidad de la comunidad que lo habita, actores que ejercitan y codifican el pasado y el devenir
de un sistema que no solo se define por su valor patrimonial sino por sus éticas, responsabilidades y resiliencia hacia
el espacio.

84 Celia Chacón Carretón

<!-- p. 85 -->

Finalmente, la elección del Convento de Santa Clara de la Columna como caso de estudio tiene otro motivo: la
propia complejidad de su tutela. Su declaración y su automática asimilación a la figura de Bien de Interés Cultural (BIC)
incorporan, tanto en el proceso administrativo como en sus consecuencias jurídicas, una consideración de los valores
patrimoniales mucho más amplia que la que se deriva una declaración de otro código o registro.

Otras de las razones para la selección de este inmueble es la facilitación al acceso a la información sobre el
mismo gracias al arquitecto Pablo M. Milllán Millán; con quien de manera paralela a esta investigación se realizan otros
estudios en la materia del patrimonio arquitectónico en su entendimiento contemporáneo con este mismo caso de
estudio.

\|
2
Imagen

Fig. 34 | Claustro (Mira Los Pedroches https://miralospedroches.es/) 85

<!-- p. 86 -->

2.2 | Levantamiento

2.2.1 | Recopilación y estudio de las fuentes planimétricas

En primer lugar y como nexo conector del apartado anterior 2.1, se procede a recopilar aquellas fuentes que a
continuación del proceso de entendimiento y conocimiento del inmueble permitan su modelado.
Para comenzar con la creación del levantamiento se basa el trazado y construcción del Convento en los documentos
gráficos disponibles pertenecientes a:

\| Proyecto: Obras de restauración en el Monasterio de Santa Clara de las Columnas de Belalcázar
Arquitecto: Arturo Ramírez
Promotor: Consejería de Cultura Junta de Andalucía
Fecha: Abril de 1990

\| Proyecto: Terminación de obras en el Monasterio de Santa Clara de las Columnas de Belalcázar
Arquitecto: Arturo Ramírez
Promotor: Consejería de Cultura Junta de Andalucía
Fecha: Octubre de 2000

\| Planimetría
Estudio de arquitectura: Pablo M. Millán Millán
Fecha: Marzo de 2015

86 Celia Chacón Carretón

<!-- p. 87 -->

Fig. 35 | Planimetría de análisis (Arturo Ramírez) 87

<!-- p. 88 -->

El último de ellos cuenta con levantamientos CAD en 2D basados en la anterior planimetría, cuya relevancia en
el modelo ha sido esencial gracias a su fiabilidad que se ha visto comprobada a lo largo del proceso del modelado BIM.
De esta manera se ha procedido a un estudio de las trazas fundacionales, las geometrías generadoras, la composición
de los alzados y el entendimiento del crecimiento del Convento a raíz de la aparición de volúmenes a lo largo de su
recorrido histórico basado asimismo en las fuentes documentales recogidas por Juan Andrés Molinero Merchán en su
libro referenciado en el estudio del caso en el apartado 2.1. Todo esto ha permitido el control formal del levantamiento,
el entendimiento del proceso constructivo y la generación de un modelo coherente con el funcionamiento del inmueble.
En la Fig.36, se muestra una selección de este trabajo, concretamente las plantas grafiadas en su análisis geométrico y
con su programa de usos.

Una vez generada esta planimetría y su estudio, se ha traducido en un CAD vinculado al modelo facilitando la
utilización de recursos de control formal del programa: rejillas, planos de referencia y niveles horizontales. La importancia
de esta información redunda nuevamente en la comprensión arquitectónica del inmueble para su representación gráfica.
En este momento se requiere incidir en el hecho de que con anterioridad de esta investigación no existe ningún modelo
del inmueble o formalización gráfica de carácter no bidimensional, ya que la planimetría existente generada por el
arquitecto Arturo Ramírez consiste en plantas, alzados, secciones y detalles del estado anterior a su reforma y posterior
a ella de con calidad de informe de intervención planimétrica. La documentación aportada por el arquitecto Pablo M.
Millán Millán consiste en una revisión de esta planimetría anterior y digitalización de parte de ella con la inclusión de
sus intervenciones en el inmueble. De esta manera esta experiencia se convierte en un documento totalmente inédito
que además de representar geométricamente en tres dimensiones el Convento logra la integración de su materialidad,
construcción e intervenciones gracias al uso de la herramienta BIM. A partir del alcance de este nivel de levantamiento
se procederá al modelado de espacios 2.2.7 y al proceso de parametrización 2.3.

2.2.2 | Criterios generales del modelado

Para proceder con la fase de levantamiento se ha optado por la aplicación Revit © de Autodesk © por cuestiones
de accesibilidad de licencia educacional, versatilidad en la representación gráfica, compatibilidad con Autocad © entre
otros programas dentro de la interoperabilidad mediante IFC, un formato de datos que tiene como finalidad permitir el
intercambio de un modelo informativo sin la pérdida o la distorsión de datos o informaciones (Building Smart, 2014)
y generalidad de uso en el ámbito del levantamiento BIM en general y de los casos de estudios recogidos en la
investigación en particular.

Para alcanzar los objetivos de esta investigación, una de las finalidades del modelo es su nivel LOK200. En
conocimiento de que el LOK en HBIM no tiene por qué desarrollarse de forma sincronizada para todos los elementos
del modelo, esto constituye una de las principales ventajas de su aplicación patrimonial . El avance en el conocimiento
de las partes de un bien puede no ser homogéneo y estará sujeto a la oportunidad de determinadas intervenciones
o investigaciones (Castellano Román, 2017). En el caso de esta investigación y del inmueble del Convento, cuya
extensión y complejidad son considerables para este trabajo, se establece el LOK200 de forma general aunque en el
Claustro y el Ala de Celdas se han realizado avances hacia el nivel LOK300 con la finalidad de aplicar las aportaciones
de esta investigación.

Todos los archivos empleados para abarcar la complejidad morfológica del inmueble, que se desarrollaran a
continuación, se acogen a los mismos criterios de modelado y su concepción individual se ha enfocado de manera que se

88 Celia Chacón Carretón

<!-- p. 89 -->

12

11

4

9

1 Claustro
2 Templo
3 Samaritana
4 Capilla
5 Claustro Nuevo
6 Biblioteca
Aseos 7 Enfermería
8 Las Gradas
9 Locutorios
10 Ala de Celdas
10 1112 ObradorCasa de Oración

1 Coro

4 8

5 2
6

Celda
Sor Felipa
Aseos

PLANTA PRIMERA
Ropería Aula CuadradaSala Cocina

7 N
0 5 10 20m

N
PLANTA PR I MERA 0 5 10 20m

12

11

4

9

1 Claustro
Torno 23 TemploSamaritana
4 Capilla
5 Claustro Nuevo
6 Biblioteca
Cocinas Portería 7 Enfermería
8 Las Gradas
9 Locutorios
10 Ala de Celdas
10 1112 ObradorCasa de Oración

Refectorio
1

4 8

5 2
6

Despacho Sala Antesacristía
Enfermería Capitular

Comedor LaborSala Provisoría Sacristía

Callejón de las palomas

Almacén huerta
Patio de San Francisco 7

Cocina N
PLANTA BAJA 0 5 10 20m

Cementerio

Fig. 36 | Estudio y análisis de la planimetría (Elaboración propia sobre planimetría del estudio Pablo M. Millán Millán)

TFG | Aplicación de la herramienta BIM al patrimonio arquitectónico 89

<!-- p. 90 -->

comparten las familias empleadas, el estilo de visualización conforme a las vistas principales escogidas para la definición
del inmueble (planos de cada planta, 4 alzados, 2 secciones y vista 3D) y los criterios de levantamiento generales.
Así mismo, todos los parámetros desarrollados son igualmente creados de manera que se pueda compartir e incluso
aplicar a futuros levantamientos mediante su trazabilidad. Todas las familias empleadas, sistemas generadores de todos
los elementos volumétricos y espaciales levantados, seguirán su misma morfología de acuerdo a su denominación,
definición de materiales y capas, y asociación de parámetros. En el caso de que un sistema constructivo o espacio
se repita, se reproducirá el uso de esa misma familia variando únicamente su posición y definición dimensional. Cabe
destacar que un mismo tipo de sistema constructivo puede ser empleado en fases históricas distintas, quedando
definido esto y por tanto siendo distinguible de otros de su familia.

Este levantamiento no pretende ser un levantamiento de cualidades artístico-escultóricas por lo que los
elementos ornamentales no influyentes en la constitución o el comportamiento de sistemas y espacios han sido
simplificados. De igual manera, el método aplicado en este trabajo responde a la conclusión del apartado 1.1.2 tras el
estudio de los casos; el modelo HBIM no tiene como propósito el proyecto y producción de nueva arquitectura o de una
imagen duplicada y estática de la realidad, sino que se funda como instrumento para la tutela patrimonial sostenible,
entre sus focos las acciones de investigación de nuevas formas de valoración y análisis contemporáneo.

A lo largo de todo este capítulo se utilizará el estilo tipográfico cursiva, cuando se recojan comandos de la
herramienta de manera directa según su denominación en el software.

2.2.3 | Creación del proyecto central y proyectos vinculados

La creación del archivo digital comenzó con la creación de un archivo central, denominado por la herramienta
proyecto para la producción de arquitectura, al cual se vincularon el resto de archivos, también de tipo proyecto,
donde se desarrollarían los espacios del Convento. En esta investigación, esta es una de las primeras decisiones
que se toman de acuerdo al modelado y responde a la intención de valorar el inmueble como un proyecto único, por
su reconocimiento como un bien inmueble complejo compuesto por diferentes estructuras con diferentes grados de
complejidad, tipo constructivo y fase de creación, pero a su vez como un conjunto de proyectos vinculados para facilitar
su manejo informático en la configuración HBIM y a su vez mantener la entidad integral del levantamiento. A su vez,
esto permite alcanzar LOK distintos entre los archivos dados por el nivel de conocimiento de cada espacio y establecer
prioridades a la hora de la definición y el perfeccionamiento del modelo.

La diferenciación del proyecto también proporciona la facultad de establecer intervenciones más pormenorizadas
pero siempre vinculadas al proyecto central como modelo HBIM del conjunto monumental completo. Esta división se
realizó de acuerdos a criterios morfológicos respecto a la construcción e historia del inmueble derivadas de zonificaciones
ya existentes en las fuentes consultadas (apartado 2.1) y el análisis e interpretación del conjunto en esta investigación
2.2.1. Reflejo de esto Fig.37.

90 Celia Chacón Carretón

<!-- p. 91 -->

Fig. 37 | Vinculación de archivos

Fig. 38 | Ubicación del modelo

Fig. 39 | Creación de fases

TFG | Aplicación de la herramienta BIM al patrimonio arquitectónico 91

<!-- p. 92 -->

2.2.4 | Ubicación y orientación del proyecto

Con el fin de reproducir el contexto del complejo se procede a ubicar el proyecto central y sus vinculaciones
a la ubicación real del Convento. Para ello se inserta la dirección de Belalcázar en el diálogo de ubicación, clima y
emplazamiento del sistema situando el proyecto en la localización general para después especificar sus coordenadas,
Fig. 38. El sistema a raíz de esta información procede a adjuntar al modelo información de tipo climática ofrecida por
la estación meteorológica más cercana al emplazamiento que permite el estudio fidedigno del soleamiento y ofrece
valores de comparación sobre posibles análisis de eficiencia energética o de sistemas MEP (mechanical, electrical and
plumbing) si se requiere. De igual modo, el proyecto se orienta respecto al norte real de la edificación; la herramienta
permite mantener la ortogonalidad deseada para facilitar la construcción del modelo, en el caso de este levantamiento
adscrita a la geometría del Claustro como entidad generadora.

Para completar la contextualización del archivo y por tanto del modelo, se modela la topografía del emplazamiento
a partir de la inserción de un archivo CAD con las líneas de nivel ya situadas en su cota. De esta manera esta realidad
se integra en el modelo BIM como un sólido de terreno sobre el cual se modelan los elementos constructivos mediante
plataformas de construcción. El contexto en el que se encuentra el inmueble, recogido en el apartado 2.1, no implica el
modelado de multitud de construcciones cercanas. Por lo que sumado a los objetivos del levantamiento más focalizados
en la definición de la construcción y los espacios consecuentes, se procede a modelar únicamente las edificaciones de
baja altura como hilera perpendicular a las Gradas con su consecuente camino de acceso al Convento.

2.2.5 | Creación de las fases históricas

La herramienta permite a su vez reconocer el factor tiempo en sus modelos, aunque esta utilidad está orientada
en la definición de un proceso constructivo o en la simplificación del estado inicial y reformado de una edificación,
incluyendo si se requiere fase de demolición. Teniendo esta posibilidad de recoger la evolución del inmueble totalmente
pertinente en la valoración de su gestión tutelar, se decide documentar y reflejar dicha información que igualmente
resulta coherente y útil en el trabajo del modelo y la agilidad en el control de la información y su catalogación.

Se acaban determinando un total de cuatro fases reconocidas por las fuentes documentales y bibliográficas
recogidas en el apartado 2.1, que se traducen de igual manera en 4 entidades fase en la herramienta:

\| Fase 0: Preexistencias
\| Fase 1: Convento primitivo s.XV
\| Fase 2: Ampliación época de los frailes s.XV
\| Fase 3: Reforma época de las monjas s.XVI
\| Fase 4: Ampliación época de las monjas s.XVII

Sumado a lo anterior, este sistema de fases muestra una imagen diacrónica que simplifica su realidad sincrónica
actual, pero que mejora la interacción con el modelo ya que favorece el entendimiento visual e introduce un método de
representación más contemporáneo que también sería idóneo para la difusión y divulgación del Convento. Ver Fig.40.

92 Celia Chacón Carretón

<!-- p. 93 -->

Fig. 40 | Evolución histórica de la construcción del Convento (Elaboración propia)

TFG | Aplicación de la herramienta BIM al patrimonio arquitectónico 93

<!-- p. 94 -->

2.2.6 | Modelado y definición de los sitemas constructivos

Al proceder con el levantamiento en sí, el proceso se adentra en la situación y definición de los sistemas
constructivos, y para ello nuevamente es fundamental ubicar la edificación en el tiempo de su construcción. El nacimiento
de este convento surgió a mediados del siglo XV. En este periodo de tiempo destacaban varios métodos de construcción
que son los que de manera general se repiten en los distintos espacios del complejo; en su construcción se emplean
diferentes materiales y técnicas edilicias fruto de las distintas fases constructivas, reformas y ampliaciones en relación
con el acceso a los bienes materiales y el estado económico histórico del inmueble y su gestión. Especialmente los
materiales que fueron adoptados son de proximidad y responden a otras construcciones de Belalcázar y alrededores
como es el trabajo de cantería de granito empleado en el monumento más destacado, el Castillo de los Sotomayor y
Zúñiga, y otros aspectos aludidos en el apartado 2.1.

Se recogen aquí la generalidad de ellos en una valoración de su tipo constructivo, siendo en el modelo donde
se desarrollan en profundidad en relación estrecha y estricta tanto con sus edificaciones y su fase histórica.

\| Muros

En este tipo de construcciones ubicadas en este periodo y en esta situación geográfica suelen ejecutarse mediante
grandes muros de carga de espesores entre los 80 cm y los 200 cm. El material propio de la cantería de esta zona y
que se extiende por otras construcciones a lo largo de la provincia es el granito. Los tipos constructivos que por tanto
se presentan para este sistema y material divergen fundamentalmente de acuerdo a su fase histórica. La sillería en
granito responde a la primera fase y por tanto la construcción de carácter más original; la piedra labrada por varias de
sus caras, generalmente en forma de paralelepípedo aparejándose a soga, o sea, mostrando la cara mayor.

En cuanto se suceden las primeras adiciones al Convento original formado por el Claustro y el Templo, el tipo se
establece como duplicidad del sistema combinado con trabajos de mamposterías de granito más desorganizadas con
argamasa. La Capilla emplea este sistema y en zonas dedicadas a trabajos como es la Enfermería y su comunicación
con la Gradas aparecen materiales adicionales como la pizarra y el ladrillo para la resolución de esquinas.
Todos los espacios se caracterizan por la presencia de alguno de estos muros ya que presentan la totalidad de las
fachadas del Convento. Esta distinción se puede comprobar en las Fig. 43 y 44.

94 Fig. 41 | Gradas planta baja (Pablo M. Millán Millán)

<!-- p. 95 -->

\| Estructura

Cabe destacar algunos elementos estructurales, más allá de los muros de carga, como los que se encuentran en
el Claustro. En él se encuentra una rica combinación de elementos estructurales, como son los arcos carpaneles
en trabajo de granito sobre pilares de la misma materialidad. Los arcos y pilares con pilastras son una constante de
este inmueble, su materialidad de nuevo va variando según la fase y la posibilidad de acceso a los materiales de
cada momento en el tiempo. Por ejemplo, una de las composiciones que varía de la original ejemplar del Claustro, es
los arcos de ladrillo sobre pilares de esta piedra en la planta baja de las Gradas. Igualmente, la formalización de los
sistemas de arcos va variando según el espacio, manteniendo la constante de los arcos carpaneles comentados con
la excepción de la planta baja de la Enfermería con arcos de medio punto en su planta baja. En la planta primera, y
última, de todos estos espacios de galería porticadas existe un sistema de balaustrada también de sillar o mampostería
de granito; en el Claustro se adorna con un motivo labrado que lo caracteriza.

Como sustentación de espacios de mayor valor tipológico como es el Templo se optó por una solución de bóvedas en
estrella, una práctica habitual en este tipo de espacios religiosos. Estas bóvedas se realizan en ladrillo y sus nervios
en piedra. En casos como la Capilla, su comportamiento estructural viene dado por la presencia del Templo al que se
adhiere; su sistema de bóvedas descansan sobre pilares incluidos en sus muros y en el muro que comparte con el
Templo al igual que la cubierta.

\| Cimentación

Al no tener documentación al respecto, se trabaja con la siguiente hipótesis: la cimentación de todo este sistema
estructural, protagonizado por muros de cargas principalmente, consiste en ensanchamiento del muro en contacto con
el terreno formando una zapata corrida de mampostería.

\| Cubiertas y forjados

En este caso encontramos distintas soluciones adoptadas para cada espacio del Convento. El sistema general se
resuelve mediante vigas durmientes sobre los muros de carga, en la que sobre ella se colocan las viguetas o rollizos,
para finalmente superponer un tablazón y como terminación teja cerámica. La de las zonas vivideras como las celdas
del Claustro juntos con todas las dependencias interiores de las galerías y el Ala de Celdas, se componen de un trabajo

Fig. 42 | Pozo del Claustro desde la galería de planta primera (Pablo M. Millán Millán) 95

<!-- p. 96 -->

de viguerías horizontales conformando un falso techo que en ocasiones se trata como una artesanía de carpintería
dando lugar a motivos mudéjares o artesonados de casetones o motivos geométricos más elementales. La estructura
de este primer forjado está compuesto por estribos de madera (vigas de madera de gran escuadría sobre los muros
exteriores) en los que se apoyan los tirantes y a su vez sobre este, los pares y nudillos del propio artesonado.

El resto de forjados mantienen la misma composición que las cubiertas mediante durmientes en los muros exteriores
y viguetas de rollizo. Esto sucede en los dos espacios litúrgicos principales, el Templo y la Capilla, sobre el sistema de
bóvedas.

\| Solerías

En este apartado cabe destacar la utilización de guijos y guijarros como la pavimentación de espacios exteriores como
las explanadas de acceso y los patios traseros de las Gradas, la Enfermería y el Claustro Nuevo, creando tramas
cuadriculadas de piedra que se sitúan en diagonal a los paramentos de la edificación. Esta solución es la misma que
predomina en otros espacios de la localidad, por tanto otorga un carácter de calle o espacio público dentro del cenobio.
En los espacios interiores se optó por un pavimento de losas de cerámica cocida; aunque esta solería que se repite en
todos los espacios, en el Claustro se dispone en espiga tanto en el patio como en las galería en contraste con el resto
de espacio interiores.

Debido a las condiciones térmicas que supone este tipo de construcción, en el Ala de Celdas, como actual espacio
vividero de las monjas con mayor margen de intervención debido a su valoración respecto a la protección, se dispone
de una tablazón de madera en forma de estrado individual en cada una de las dependencias, para mejorar el confort
de este espacio respecto al aislamiento y la temperatura superficial del pavimento.

\| Carpinterías

Las carpinterías se caracterizan por su trabajo ornamental. En el caso de puertas de acceso a grandes dependencias
más singularess en su composición como es el Templo, que podía considerarse centro de la fachada principal distintiva,
la madera se trata con motivos escultóricos y añadidos de herraje metálicos. En el resto de casos, las puertas tienen
un tratamiento artístico pero de escala doméstica con pequeños recercados tallados o paneles. Para su modelo se ha
atendido principalmente a sus dimensiones y número de hojas.

Las ventanas nuevamente varían principalmente en forma y tamaño, siendo circulares en espacios como las portadas
del Templo y la Capilla. En la Capilla existen ventanas saeteras largas y estrechas, abocinadas en su interior. El
abocinado es una práctica recurrente también en las ventanas de las celdas del Claustro, son cuadradas y de pequeña
dimensión, factor que dificulta la ventilación e iluminación de dicho espacio, achacando su posición en galería a esto
último.

\| Portada

La portada del Templo forma parte de la construcción de la fase original y por tanto tiene un sentido emblemático desde
el momento de su concepción. Ejecutada en granito, conviven en su composición multitud de detalles en forma de
molduras y recercados, destacando el trabajo escultórico de la puerta bajo el hueco que queda enmarcado por el arco
conopial, tan típico del gótico tardío.

\| Acabados y trabajos decorativos

Los acabados de los sistemas estructurales y de particiones se revisten de yeso bastardo en zonas de menor valor
monumental, como los espacios de comedor, cocina… y de estucos con molduras en el resto con terminaciones de
frescos y trabajos murales con pintura al aceite como es el caso del Refectorio y todos los muros en su cara exterior

96 Celia Chacón Carretón

<!-- p. 97 -->

Fig. 43 | Propiedades y parámetros | Muro sillar granito 80cm

Fig. 44 | Propiedades y parámetros | Muro mampostería granito 100cm

TFG | Aplicación de la herramienta BIM al patrimonio arquitectónico 97

<!-- p. 98 -->

a la galería del Claustro conocidas como panda norte, sur, este y oeste, donde se encuentran a su vez escudos
ornamentales en granito.

Es por esto que el conjunto del Claustro principal y todas sus dependencias, entre ellas las celdas originales, es el
más protegido respecto a posibles modificaciones. Las intervenciones son múltiples y siempre orientadas a dichos
acabados y revestidos para el mantenimiento de sus cualidades artísticas frente a lesiones del tipo: humedad por
condensación, fisuras, pérdidas de revestimiento… Por su condición en galería, la policromía del trabajo de viguerías
y artesonado de los forjados, otro de los emblemas de este inmueble, se encuentra nuevamente acogida a diversas
labores de mantenimiento de su estética y a estrictos criterios de uso de todo el Claustro en general a consecuencia.

Los frescos del Claustro, con motivos religiosos, destacan por su valor artístico, convirtiéndose en uno de los principales
hitos de este inmueble. Del mismo modo el Templo, siendo el espacio litúrgico principal, contiene el corpus principal de
trabajos murales y esculturas además de multitud de bienes muebles que conforman la entidad histórico-artística del
Convento.

Mediante la creación y modificación de familias, ha sido posible la creación de todas estas realidades formales
en la herramienta, atendiendo a sus materiales, capas y acabados. Todo ello ha quedado recogido en las propiedades
de los elementos además de la información no directamente constructiva como se expondrá en el apartado de relación
de parámetros 2.3.5.

El uso de masa conceptual ha permitido realizar un modelado geométrica general y sintético de realidades
complejas o de carácter ornamental que se han estimado necesarias para la reproducción arquitectónica del inmueble.
Este sistema de modelado permite caracterizar volúmenes de geometrías no recogidas en las familias, y a partir de ellos
realizar definiciones cuantitativas y a su vez cualitativas, ya que permiten la incorporación de materiales y por tanto de
parámetros de definición. Estos elementos permiten modificaciones una vez ejecutados de manera que, nuevamente,
el modelo es suceptible de ser mejorado continuamente. Muchas realidades ornamentales, como la portada del Templo
ya comentada o los encuentros de los pilares con el forjado de diversos espacios, se han modelado sujetas al criterio
de análisis geométrico y simplificación del mismo para facilitar su compresión en el proceso de modelado.

Mediante la creación y modificación de familias, ha sido posible la creación de todas estas realidades formales
en la herramienta, atendiendo a sus materiales, capas y acabados. Todo ello ha quedado recogido en las propiedades de
los elementos además de la información no directamente constructiva como se expondrá en el apartado de parámetros

2.2.7 | Modelado y definición de los espacios

Ya expuesto el levantamiento y definición de los sistema constructivos resultando realidades llenas construidas,
el vacío que resulta de esto queda por ser modelado. falta por modelar el vacío resultantate.

Es aquí cuando Revit© introduce las categorías del modelo espacio y habitación como las dos opciones
posibles para definir estos estratos inmateriales. El conflicto viene dado por la asociación que hace este software para
definir estas dos opciones; desde el entendimiento y manejo de los conceptos arquitectónicos espacio sería la opción
empleada pero en Revit©, los “espacios”, es una categoría cuya utilidad y desarrollo solo se emplea en MEP (xxx) para
el sector de las instalaciones, por lo que habitación es la categoría que se utiliza. Cabe apuntar que en general esta
categoría, denominada de familia de tipo inserción, necesita estar inscrita dentro de otra como sucede en, por ejemplo,
un ejemplar de la categoría ventana dependiente de su anfitrión muro. Esto se traduce en que al crear una habitación
es necesario la existencia de un espacio delimitado por muros con anterioridad, aunque existe la opción de delimitación
de habitación en espacios no cerrados mediante la creación de separación de habitación que admite la creación de

98 Celia Chacón Carretón

<!-- p. 99 -->

Fig. 45 | Propiedades y parámetros | Espacio Celda 1 Claustro

Fig. 46 | Propiedades y parámetros | Espacio Celda 11 Ala Celdas

TFG | Aplicación de la herramienta BIM al patrimonio arquitectónico 99

<!-- p. 100 -->

Fig. 47 | Isometría NO del Convento (Elaboración propia)

100 Celia Chacón Carretón

<!-- p. 101 -->

Fig. 48 | Isometría SO del Convento (Elaboración propia)

TFG | Aplicación de la herramienta BIM al patrimonio arquitectónico 101

<!-- p. 102 -->

2.3 | Parametrización

2.3.1 | Creación de parámetros

En primer lugar, se incide en la potencialidad de los parámetros; tal y como se expuso en el apartado de
investigación 1.4, los parámetros permiten completar la definición del modelo y sus partes. En el caso del Convento,
existen sistemas constructivos que se repiten, apartado 2.2.6, y por tanto su definición de propiedades formales es
idéntica incluyendo su fase histórica. Los parámetros creados permiten la distinción de un mismo sistema constructivo,
ya que a una misma cubierta como sucede en la zona del Claustro construida en el s.XV, se presentan singularidades del
tipo lesión e intervención entre sus faldones. De esta manera el modelo identifica sus partes no solo por su construcción
sino por su desarrollo histórico y estado actual en forma de informe integrado de cada uno de sus elementos.

Para la creación de todos los parámetros incorporados al modelo y por tanto para la obtención de una
estructura de la información como la recogida de manera teórica en el apartado 1.4.1 y 1.4.2, se ha seguido el siguiente
procedimiento de acuerdo al objetivo de su rápida y eficaz clasificación y su visualización:

La creación de parámetros dentro de la herramienta se realizó mediante la opción que se ofrece de parámetros
compartidos, de manera que los parámetros creados se pueden aplicar a todos los proyectos vinculados y a otros
potenciales archivos. Su funcionamiento es similar a la opción básica de parámetros pero con la ventaja descrita.
Dentro de este diálogo se procede facilitando información del tipo: nombrar el parámetro de manera reconocible y
racional empleando términos recogidos en literatura existente y conceptos arquitectónicos reconocidos y además
empleados en la bibliografía y legislación de consulta; disciplina en la que se agrupa dentro de las categorías que
ofrece Revit ©, se elige común ya que permite su acceso desde todas las plantillas, tipos de archivo y visualizaciones;
tipología del parámetro, es en este momento donde los parámetros definidos para este levantamiento comienzan a
divergir ya que se decide por cuatro tipos: de tipo sí/no, de tipo texto, de tipo URL y de tipo imagen; por último el listado
en el que se agrupa dicho parámetro en las propiedades del elemento, decidiéndose la asociación de dicho parámetros
a ejemplar y no a tipo, para poder definir cada elemento dentro de una categoría general de tipo dentro de familia. Es
decir, una misma cubierta, en relación a su definición constructiva, puede tener distintas definiciones de acuerdo a sus
parámetros asociados dependiendo de la cubierta o paño que se represente, lo que es necesario para poder señalar
lesiones, grados de afección de distintos paños etc; y por último en lugar de agrupación del parámetro donde se opta
por el grupo otros, ya que el resto de opciones suponen categorías de conceptos demasiado concretos o en relación
con otras disciplinas como las estructuras, instalaciones, etc., que podrían llevar a la confusión.

Finalmente se filtra a qué elementos se les va a poder asociar el parámetro creado de manera que el resultado
desde el diálogo de propiedades es un listado de datos a rellenar que van variando según la familia y los parámetros
que se le hayan asociado a dicho tipo de elemento. En este caso sí se filtra por familia de categorías del modelo
siendo las opciones todas las familias que, o presenta Revit©, o se han creado dentro del software. En el caso de este
levantamiento, los parámetros se asocian a elementos (familias de sistemas constructivos presentes en el Convento:
cubiertas, muros, particiones….) o espacios.

El resultado de todo este procedimiento de parametrización, que se ha de ejecutar por cada parámetro en su
definición, es una lista de campos a rellenar para completar la definición de los elementos y espacios que se han
modelado en la herramienta dentro de su diálogo propiedades.

102 Celia Chacón Carretón

<!-- p. 103 -->

Fig. 49 | Parámetros del proyecto

Fig. 50 | Creación parámetro tipo sí/no

Fig. 51 | Creación parámetro tipo texto

TFG | Aplicación de la herramienta BIM al patrimonio arquitectónico 103

<!-- p. 104 -->

2.3.2 | Parámetros de habitabilidad

Tal y como se recogió en el apartado 1.4.2., los parámetros de habitabilidad han sido una reflexión constante
en esta investigación, y su desarrollo ha permitido tanto su conceptualización, ver Fig. 52 y Fig. 53, como su aplicación
directa en este levantamiento del Convento de Santa Clara de la Columna, del cual se basan los diagramas que tratan
de simplificar el comportamiento elementos-espacio, concretamente la celda que se repite en el Claustro.

HABITABILIDAD

elementos espacio

Fig. 52 | Diagrama relación elementos y espacio (Elaboración propia)

104 Celia Chacón Carretón

<!-- p. 105 -->

identificación geometría

temperatura acústica

ventilación instalaciones

iluminación iluminación
natural artifical

accesibilidad privacidad

Fig. 53 | Diagrama conceptualización parámetros habitabilidad (Elaboración propia)

TFG | Aplicación de la herramienta BIM al patrimonio arquitectónico 105

<!-- p. 106 -->

2.3.3 | Visualización de parámetros

La creación de parámetros no contrae de manera directa su visualización. La asociación y definición de
parámetros a elementos y espacios queda reflejada en estas realidades dentro de sus propiedades pero no en su
representación en ninguna de las visualizaciones. Es por ello que se ha de modelar a su vez un sistema de configuración
de estilo de visualización.

Lo primero a destacar de este procedimiento es que las visualizaciones, y por tanto su modelado y configuración,
responden a vistas concretas. Entre las posibilidades que permite Revit© de: planos de planta, planos de techo, vistas
3D, alzados y secciones, en este levantamiento se decide que el desarrollo visual de los parámetros se realice en
planta, alzado y sección, siendo estos por tanto las vistas que se configuran. Es preciso señalar una determinación
que posee la herramienta, los espacios (habitaciones y espacios) y por tanto su definición en forma de parámetros o
etiquetas de identificación y superficie tan solo puede ser visualizadas en planta y sección, no se permite esta opción en
ninguna de las otras visualizaciones que confiere el programa; este es uno de los criterios que esencialmente colaboran
en la decisión anterior.

Por lo tanto, en cada vista que se requiere se configura su visualización correspondiente entrando en el cuadro
de diálogo visibilidad/gráficos. Al igual que en las pestañas de categorías se define qué elementos se visualizan en
la vista, inclusive los archivos linkeados como era el caso de CAD 2D para la base del modelo, en la pestaña filtro se
procede a añadir nuevos filtros. Dichos filtros se crean de acuerdo a la relación que se ha establecido entre un parámetro
y su definición, de tal forma que el estilo gráfico de visualización puede crearse de acuerdo no solo al parámetro sino a
sus distintas definiciones facilitando la comparativa y el análisis. Las opciones empleadas son de patrón de superficie
sólido para los espacios capacitando el entendimiento de su superficie y de patrón de corte para señalar elementos.

Los ejemplos que se recogen de visualización de parámetros en elementos y espacios en las figuras de la derecha
responden a:

\| Lesiones Fig. 54
\| Nivel de Urgencia Fig. 55
\| Nivel de Habitabilidad Fig. 56

Como resultado final de este proceso, se crean distintos planos de planta que responden a las visualizaciones
creadas según los criterios de parámetros. Su comportamiento es similar a lo que se conocería como planos temáticos
donde aparece la representación gráfica de la arquitectura modelada de los edificios y se señala con una leyenda de
color aquella información volcada y filtrada para su visualización. Dichos planos se encuentran acogidos a cada archivo
de proyecto en su navegador de proyecto siendo común en todos, según uno de los criterios del apartado 2.2.2.

\| Nivel de Protección Fig. 57
\| Nivel de Conservación Fig. 58
\| Nivel de Urgencia Fig. 59
\| Nivel de Visitabilidad Fig. 60
\| Nivel de Habitabilidad Fig. 61

106 Celia Chacón Carretón

<!-- p. 107 -->

Fig. 54 | Visualización de lesiones asociada a vista

Fig. 55 | Visualización de Nivel de Urgencia asociada a vista

Fig. 56 | Visualización de Nivel de Habitabilidad asociada a vista

TFG | Aplicación de la herramienta BIM al patrimonio arquitectónico 107

<!-- p. 108 -->

Máximo
Alto
Medio
Bajo
Fig. 57 | Visualización de Nivel de Protección | Planimetría +5.00m

Máximo
Alto
Medio
Bajo
Fig. 58 | Visualización de Nivel de Conservación | Planimetría +5.00m

108 Celia Chacón Carretón

<!-- p. 109 -->

Máximo
Alto
Medio
Bajo
Fig. 59 | Visualización de Nivel de Urgencia | Planimetría +5.00m

Visitable
Restringido
Clausura
Fig. 60 | Visualización de Nivel de Visitabilidad | Planimetría +5.00m

TFG | Aplicación de la herramienta BIM al patrimonio arquitectónico 109

<!-- p. 110 -->

Alto
Medio
Bajo
Fig. 61 | Visualización de Nivel de Habitabilidad | Planimetría +5.00m

110 Celia Chacón Carretón

<!-- p. 111 -->

TFG | Aplicación de la herramienta BIM al patrimonio arquitectónico 111

<!-- p. 112 -->

2.3.4 | Tablas de planificación

Las tablas de planificación son una de las herramientas más útiles que presenta el programa, siendo fundamental
para la realización de mediciones en el uso general de la herramienta BIM para edificaciones de nueva construcción,
o para efectuar cómputos de superficies en el proyecto. Estas tablas son concebidas como otra vista del modelo y
se pueden crear tantas como se requieran, siguiendo un procedimiento que interpela a qué elemento o espacio se
requiere contabilizar y cuáles propiedades o parámetros asociados se quieren ver reflejados en la tabla. Se pueden
efectuar por familias incluyendo dentro de la planificación los distintos ejemplares de esa misma familia.

En este levantamiento el uso de estas tablas se ha individualizado únicamente para el cómputo de los espacios
y su comparativa, aunque debido al conocimiento volcado durante el levantamiento sobre intervenciones, lesiones…
esta información podría quedar igualmente expresada en dichas tablas directamente extraídas del modelo de
información, de manera que, aunque quedando fuera del objeto de esta investigación, se podría estudiar la tutela desde
el punto de vista de la cuantificación de otros aspectos como los mencionado y proponer una valoración económica
de intervención a partir del diagnóstico general aportando un coste genérico que se podría asociar a la medición que
realiza la herramienta en forma de dicho coste por superficie, volumen, nivel de urgencia…

En las tablas de espacios se han recogido los datos principales que caracterizan nominativa y geométricamente
dicha habitación, y todos los parámetros que han permitido la definición pormenorizada del cumplimiento de las
exigencias de habitabilidad y por tanto el análisis y reflexión de los distintos niveles patrimoniales y de habitabilidad de
dichos espacios.

112 Celia Chacón Carretón

<!-- p. 113 -->

Fig. 62 | Tabla de planificación | Parámetros de habitabilidad Celdas Claustro

Fig. 63 | Tabla de planificación | Parámetros de habitabilidad Celdas Ala Celdas

TFG | Aplicación de la herramienta BIM al patrimonio arquitectónico 113

<!-- p. 114 -->

2.3.5 | Relación de parámetros, elementos y espacios

A continuación se recoge de manera esquemática, para favorecer su entendimiento fuera de la herramenta y
su trazabilidad, aquellos parámetros desarrollados en la investigación y volcados en la experiencia:

ELEMENTOS
Información Identificación Familia | Elemento constructivo
Tipología Ejemplar | Tipo de elemento
Dimensiones
Materialidad
Estructural Sí | No
Uso estructural Carga | Arriostramiento | Combinado estructural

Patrimonial Información Atribuida | Confirmada
Data
Autor
Estilo
Descripción
Imagen

Fase histórica 00_ConventoPrimitivo s.XV
01_AmpliaciónFrailes s.XV
02_ReformaMonjas s.XVI
03_AmpliaciónMonjas s.XVII

Lesiones Depósitos
Manchas de óxido
Eflorescencias
Musgos, líquenes frescos o secos
Disgregaciones del mortero
Disgregaciones de la roca
Degradación superficial por lavado
Degradación volumétrica por coqueras
Pérdida de revestimiento
Restos de revestimiento a eliminar
Fisuras
Grietas
Humedad por condensación
Humedad por capilaridad

Grado de afección Bajo | Medio | Alto
Intervención Intervención
Data
Autor
Imagen

Estado de conservación
Mantenimiento

Habitabilidad Características Transmitancia térmica
Impermeabilidad
Absorción acústica
Caudal de ventilación
Lúmenes

Existencia de instalación Iluminación artifical
Eléctrica
Fontanería
Saneamiento
Ventilación
Climatización
Telecomunicaciones

114 Celia Chacón Carretón

<!-- p. 115 -->

ESPACIOS
Información Identificación
Superficie
Volumen
Altura libre

Habitabilidad Dimensión Sí | No
Temperatura Sí | No
Ventilación Sí | No
Iluminación natural Sí | No
Iluminación artificial Sí | No
Instalaciones Sí | No
Accesibilidad Sí | No
Privacidad Sí | No
Acústica Sí | No

Niveles Patrimonial Nivel de Protección Bajo | Medio | Alto | Máximo
Nivel de Conservación Bajo | Medio | Alto | Máximo
Nivel de Urgencia Bajo | Medio | Alto | Máximo
Nivel de Visitabilidad Visitable | Restringido | Clausura

Habitabilidad Nivel de Habitabilidad Bajo | Medio | Alto

Fig. 64 | Galería planta primera del Claustro (Mira Los Pedroches https://miralospedroches.es/) 115

<!-- p. 116 -->

116 Celia Chacón Carretón

<!-- p. 117 -->

Capítulo 3 | Conclusiones

TFG | Aplicación de la herramienta BIM al patrimonio arquitectónico 117

<!-- p. 118 -->

3.1 | Conclusiones

Esta investigación ha permitido el desarrollo de un largo proceso de exploración del estado actual del conocimiento
de varias facetas que atañen el comportamiento de la arquitectura contemporánea en su vertiente patrimonial. En el
planteamiento de utilización de una herramienta que permitiese crear un sistema de información patrimonial se ha
abarcado el acercamiento a varios campos fundamentales de las realidades patrimoniales: el tipo de bien cultural que
tiene como objeto, el complejo sistema de agentes que lo rodean, la tecnología que le da soporte y como eje generador
de la hipótesis de esta investigación: las personas que lo habitan. De esta manera, a su vez se ha dado la necesidad de
provocar un entendimiento de la edificación desde la transversalidad intrínseca del estudio arquitectónico, generando
análisis históricos, artísticos, geométricos, tipológicos, constructivos, estratigráficos, sociológicos y de representación
gráfica.

Como se recogió en el capítulo de investigación, el uso de la herramienta BIM y su información asociada
se considera actualmente el modo de trabajo útil en la conservación de edificios patrimoniales, ya que favorece la
colaboración y la fácil gestión de la información relevante. El reconocimiento de los procesos constructivos y de los
materiales históricos aplicados en cada caso, archivados en formato digital y en una adecuada organización jerárquica de
los datos, sirve de apoyo útil para el análisis requerido en los proyectos de recuperación o reconversión. La perspectiva

118 Celia Chacón Carretón

<!-- p. 119 -->

HBIM es un aspecto de permanente descubrimiento e innovación, que contribuye positivamente a la preservación de la
historia de los edificios (Zita Sampaio et al., 2021). La construcción del modelo gráfico es directamente dependiente del
proceso de conocimiento del bien que se modela, y por tanto ambas realidades se nutren la una de la otra, provocando
una reciprocidad que en este caso ha incentivado la ampliación de la investigación, en el momento de la inclusión de
nuevos parámetros relacionado con la habitabilidad no visitados por los casos de estudio recogidos en el estado de la
cuestión.

En el caso de estudio que se ha presentado y expresado de la forma más sintética posible dentro de la
complejidad del inmueble, se ha buscado su racionalidad a la hora del levantamiento basado en los análisis
anteriormente comentados y en una visión crítica focalizada en la tarea del modelado en BIM. Una vez más, se
quiere hacer referencia a Castellano Román y Pinto Puerto que reflexionan sobre la representación y por tanto el
procedimiento de conocimiento y creación de ideas como estrategia de modelización de activos mucho más decisivos
en la construcción de un modelo HBIM que la precisión geométrica de una nube de puntos de alta resolución, o un
modelo de alta precisión métrica, pueden ofrecer (2019). La imagen real o “calco” (Angulo Fornos, 2020) generado por
un levantamiento puramente basado en la automaticidad de procesos con NURBS o fotogrametría no filtrados pueden
ofrecer un producto fidedigno de la realidad, pero no necesariamente un alto nivel de conocimiento del inmueble.
Además el modelado manual empleado, al igual que el semiautomático, permite la adición progresiva de información
durante su ejecución y perfeccionamiento del modelo, concretamente de un modelo BIM generado con un método
basado en el criterio de levantamiento arquitectónico.

Hasta el momento de la investigación no existía ningún levantamiento tridimensional del complejo pero sí
numerosa información sobre su trazado arquitectónico y sus intervenciones. Con el modelo HBIM generado se ha
alcanzado en LOK2OO general en el cual la situación y geometría de los elementos y sistemas constructivos han sido
definidos de acuerdo a su posición y estado actual basado en el conocimiento previo del inmueble. En los espacios
de celdas, tanto el original del Claustro como las del Ala de Celdas, se han realizado avances y aportaciones hacia el
LOK300 como forma de sondear las posibilidades de las aportaciones de esta investigación respecto a la recogida de
datos patrimoniales y habitacionales.

Fig. 65 | Las Gradas desde el patio trasero (Presente Continuo http://presente-continuo.org/) 119

<!-- p. 120 -->

Parte de la experiencia se ha centrado no solo en la creación de un modelo, sino de una estructura de información
vinculada intrínsecamente al mismo permite la transversalidad de la tutela. En el sentido de la organización del
modelado, este ha evolucionado cada vez que se ha añadido información con el objeto de abarcar el ámbito patrimonial
más allá de la conservación y protección, siendo una de las barreras que se preveían. El modelo la información no
puede limitarse a una serie de parámetros vinculados a determinados objetos geométricos, sino que requiere integrar
documentos de naturaleza diversa; la diversidad y complejidad de la información patrimonial, tanto por la naturaleza
de sus soportes como por las diversas procedencias disciplinares de los contenidos posibilita la extrapolación de la
realidad a aspectos intrínsecos a ella como la domesticidad de sus espacios. Para su ordenación se ha diseñado una
estructura de información capaz de registrarla de forma eficaz.

Para ello, desde la perspectiva más amplia y a la vez científica posible, y con la vocación de exhaustividad
que permiten las nuevas tecnologías de la información, se han registrado parámetros en relación con la habitabilidad
del Convento. La parametrización como método de objetivación de las realidades arquitectónicas y herramienta de
identificación, catalogación, medición, visualización y comparativa de aspectos ha logrado aplicarse en aspectos
como la luz de los espacios, su privacidad, sus condiciones térmicas o su accesibilidad entre otros. Se ha logrado
mediante el dibujo la representación de la convergencia de la realidad patrimonial y habitacional y como interactúa en
los espacios permitiendo reflexionar a raíz de aspectos convergentes y divergentes. Se puede cumplir el principio de
interdisciplinariedad ya que los nuevos avances y desarrollos llevados a cabo por la herramienta BIM enfatizan una
colaboración eficaz entre el diseño del arquitecto y las demás disciplinas, una colaboración que requiere de métodos
fiables para compartir y almacenar información sobre modelos construidos, además de las soluciones y propuestas
de diseño. Y permite gestionar todos los cambios realizados al modelo por parte de cualquiera de los participantes,
minimizando a la vez la posibilidad de que se produzcan errores humanos.

El proceso de definición de estos parámetros ha tratado de recoger la complejidad del factor habitabilidad
desde aspectos técnicos asociados a materiales y dimensiones, como a factores directamente en relación con el
confort asociado a decisiones arquitectónicas como la orientación y disposición de los huecos, la superficie de los
espacios, su privacidad… todo esto recogido en el apartado 1.1.5. Esta reflexión, aunque incipiente, ha intentado añadir
al estado del conocimiento del HBIM una pequeña aportación a su perspectiva de estudio contemporáneo sobre el
aspecto intrínseco de los espacios arquitectónicos patrimoniales o no, su identidad como lugares donde se desarrolla
la vida.

Una de las reflexiones que ha permitido aclarar un factor determinante en la convivencia de la tutela y la
habitabilidad es el hecho de que un elemento puede encontrarse perfectamente conservado, sin necesidad de
intervención a corto plazo, y ser a su vez altamente vulnerable por cuenta de su falta de protección o su sobreprotección,
siendo el ambiente en el que se desarrolla un factor de daño o un factor al que daña. De esta manera, un aspecto
que se entiende como parte fundamental de la gestión del patrimonio arquitectónico y patrimonio en general como
es la protección, puede llegar a aumentar la vulnerabilidad de su estructura elemental y especial. Esta determinación
ha podido ser medida y valorada según el método de creación de parámetros patrimoniales y habitables aplicados a
elementos y espacios pudiendo observar la interacción entre ellos.

Del mismo modo existe el otro lado de este espectro, y es la convergencia de factores patrimoniales y
habitables suponiendo el enriquecimiento y salvaguarda de ambos; esto ha podido ser observado gracias a los niveles
parametrizados y visualizados tras la pormenorización de la definición y parametrización de los elementos y espacios.

120 Celia Chacón Carretón

<!-- p. 121 -->

En el Ala de Celdas, donde la protección que se le aplica al inmueble es menor a pesar de la catalogación general como
BIC, se generan condiciones de vida más propias de espacios habitables. Esto se debe a que la caracterización formal
y artística de los espacios lo hacen menos vulnerable a lo que respecta la tutela. La ausencia de frescos, policromía,
artesonados o trabajos ornamentales en madera, entre otros, confieren de menos exigencias a las condiciones de
mantenimiento de este espacio. Es por ello que se permite el uso de aparatos de calefacción (sistemas de climatización
no integrados), integración de elementos como la tarima de madera que se coloca sobre el pavimento original, la
presencia de sistemas de iluminación artificial ejecutadas para las prestaciones como espacio habitable en lugar de
como elemento de valorización de los espacios en forma de focos… Existen a su vez aspectos formales arquitectónicos
como la continuidad del pavimento, en lugar de la presencia de escalones para acceder a cada celda en el caso de la
zona vividera del Claustro, la dimensión mayor de ventanas al exterior practicables de dos hojas…

Todo esto analizado y volcado en forma de parámetros en el modelo incidiendo en la habitabilidad, ha permitido
una evaluación objetiva de las condiciones de vida, llegando a poder afirmar que el Ala de Celdas tiene un nivel de
habitabilidad mayor que el las celdas del Claustro en relación directa a aspectos de la tutela: protección, conservación
e intervención, de manera que la aplicación práctica se verifica.

De manera adicional, todo este conocimiento queda recogido en tablas registrables y modificables para
personas no conocedoras de la herramienta Revit ® lo que favorece la transversalidad y la discusión multidisciplinar
fundamentada en datos cuantificables de la realidad patrimonial y habitacional.

Hoy en día el patrimonio cultural está intrínsecamente ligado a los desafíos que conlleva su mantenimiento.
Una gestión correcta del potencial de desarrollo del patrimonio cultural exige un enfoque que haga hincapié en la
sostenibilidad, un concepto recientemente incorporado a la noción de patrimonio. A su vez, la sostenibilidad requiere
encontrar el justo equilibrio entre sacar provecho del patrimonio cultural hoy y preservar su “riqueza frágil”, como lo
denomina la UNESCO (2017) para las generaciones futuras; nuevas perspectivas en la investigación contemporánea,
acciones innovadoras que capitalicen las lecciones aprendidas, aquellas que la cooperación puede recuperar con el fin
de potenciar el desarrollo de las capacidades resilientes intrínsecas de los sistemas de patrimonio territorial.

Fig. 66 | Fotografía histórica (https://belalcazar-cordoba.blogspot.com/2018/11/santa-clara.html) 121

<!-- p. 122 -->

Estas resiliencias no solo serían capaces de otorgar nuevas posibilidades a la hora de sobreponerse a estos
desafíos, sino que además pondrían en valor, no solo a todos los agentes partícipes del proceso, pero también a las
personas intrínsecas a la realidad, como son los habitantes históricos de muchos contextos patrimoniales, salvaguardas
constantes de estos bienes y protagonistas de su existencia.

La difusión se considera por la LPHA 14/2017 del 26 de noviembre, uno de los objetivos básicos de la gestión
tutelar constituyendo uno de los principales factores, junto con la investigación y conservación, de la identidad, e
historia y riqueza que caracteriza el presente. Potenciar la difusión no sólo del bien sino de su forma de vida basada
en las costumbres, tradiciones, festividades, maneras de hacer… Estos pilares de la acción pública proporcionan la
base para la sostenibilidad del patrimonio de hoy y su capacidad de contribuir a formas más sostenibles del desarrollo
humano en el futuro de manera inclusiva y equitativa. Esta noción completa del patrimonio contribuye a la revalorización
continua de las culturas y de las identidades, y es un vehículo importante para la transmisión de experiencias, aptitudes
y conocimientos entre las generaciones. Además es fuente de inspiración para la creatividad y la innovación, que
generan los productos culturales contemporáneos y futuros. El patrimonio cultural encierra el potencial de promover
el acceso a la diversidad cultural y su disfrute. Puede también enriquecer el capital social conformando un sentido de
pertenencia, individual y colectivo.

La combinación acertada de patrimonio cultural y desarrollo sostenible requiere no sólo protección frente
a las condiciones ambientales adversas y el daño intencionado, sino también atención constante a los factores
multidisciplinares y la renovación permanente de la perspectiva de actuación. Todo enfoque que mire sólo al pasado
correrá el riesgo de convertir el patrimonio en una entidad rígida y congelada, que perderá su pertenencia para el
presente y para el futuro (UNESCO, 2014).

Por último y retomando el inicio de la investigación se valora el detonante de la misma. El trabajo realizado
nació en gran parte de la necesidad de estudiar de manera objetiva y analítica la documentación abundante, aunque
dispersa, de la materia. La casuística de levantamientos y aproximaciones resultaba imponente, y la sistematización
que se comenzó a producir en aras de entender el estado del arte de la materia pasó a formar parte fundamental
de la investigación expuesta. Por ello su resolución final en dos capítulos centrales: 1 y 2, en los cuales de manera
continuada se procedió a conocer para después aplicar.

De la misma manera, y por la incipiente necesidad de ser diestro en la materia BIM a día de hoy, se realiza una
valoración positiva del trabajo de recopilación de casos de estudio con el interés de continuar en su desarrollo por esta
investigación u otras en favor del conocimiento, o al menos el inicio a él, del levantamiento del patrimonio arquitectónico
mediante tecnologías de modelado digital.

122 Celia Chacón Carretón

<!-- p. 123 -->

TFG | Aplicación de la herramienta BIM al patrimonio arquitectónico 123

<!-- p. 124 -->

3.1 | Futuras líneas de desarrollo

El conocimiento de un edificio complejo como lo es el Convento de Santa Clara de la Columna en Belalcázar,
puede no ser homogéneo, así como puede a su vez ampliarse durante las diferentes fases de la investigación. Algunas
partes pueden presentar un análisis más preciso que otras, pero el estudio evolutivo y multidisciplinar nos permite
rellenar las lagunas continuamente. Por esta razón, algunas partes del Convento se han desarrollado y aplicado de
forma más precisa que otras como se ha indicado a lo largo del levantamiento. La investigación ha tratado de poner
de manifiesto las posibilidades del método en relación con una parte significativa del edificio, las celdas como espacios
vivideros, lo que permitirá aplicar estas ideas en otros espacios u otros edificios.

Del mismo modo, como deseo final de esta investigación se exponen a continuación diferentes posibilidades de
futuras líneas de desarrollo. De manera intrínseca se quiere invitar a la indagación en nuevos aspectos que conforman
el complejo y a veces secreto mundo de la arquitectura patrimonial, en ocasiones oculto en quienes lo habitan por
ejemplo.

\| Continuar el trabajo de documentación y análisis de casos de estudio

\| Continuar con el progresivo enriquecimiento del levantamiento del Convento de Santa Clara de la Columna
\| Continuar con la parametrización de los espacios del Convento de Santa Clara de la Columna

\| Investigar en la inclusión de nuevos parámetros para profundizar en la definición del patrimonio arquitectónico

\| Reproducir esta experiencia en otros casos donde se produzca también esta convergencia de realidades

\| Estudiar la compatibilidad de la tutela y la habitabilidad a raíz de la objetivación paramétrica de estas realidades
\| Proponer reformas en la tutela para la convergencia de realidades de manera respetuosa y contemporánea

124 Celia Chacón Carretón

<!-- p. 125 -->

Fig.TFG67| | AplicaciónPuerta haciade unala herramientade las dependenciasBIM al patrimoniodel Claustroarquitectónico(Santiago de la Flor) 125

<!-- p. 126 -->

126 Celia Chacón Carretón

<!-- p. 127 -->

Bibliografía

TFG | Aplicación de la herramienta BIM al patrimonio arquitectónico 127

<!-- p. 128 -->

American Institute of Architects. (2013). AIA Document E-203.

Angulo Fornos, R. (2016). El modelo digital del facistol de la Catedral de Sevilla. Estudios y recuperación. Editorial Universidad de Sevilla y Catedral
de Sevilla, 227-242.

Angulo Fornos, R., Pinto Puerto, F., Rodríguez Medina, J. & Palomino Rodríguez, A. J. (2017). Digital Anastylosis of the Remains of a Portal by Master
Builder Hernán Ruiz: Knowledge Strategies, Methods and Modelling Results. Estudios y recuperación. Digital Applications in Archaeology
and Cultural Heritage, 7, 32-41. https://doi.org/10.3390/app10072428

Angulo Fornos, R. y Pinto Puerto, F. (2015). Decisiones constructivas en la ejecución de la capilla de la Antigua de la catedral de Sevilla. Estudio
a través de modelos gráficos. En: Instituto Juan de Herrera. Actas del Noveno Congreso Nacional y Primer Congreso Internacional
Hispanoamericano de Historia de la Construcción: Segovia, 13 a 17 de octubre de 2015, 1337-1347. https://dialnet.unirioja.es/servlet/
libro?codigo=580318

Angulo Fornos, R. (2020). Desarrollo de modelos digitales de información como base para el conocimiento, la intervención y la gestión en el patrimonio
arquitectónico. De la captura digital al modelo HBIM [Tesis doctoral, Universidad de Sevilla]. https://idus.us.es/handle/11441/98088

Angulo Fornos, R. (2016). El modelo digital del facistol de la Catedral de Sevilla. Estudios y recuperación. Editorial Universidad de Sevilla y Catedral
de Sevilla, 227-242.

Apollonio, F. I., Gaiani, M., & Sun, Z. (2016). A reality integrated BIM for architectural heritage conservation. Handbook of Research on Emerging
Technologies for Architectural and Archaeological Heritage, 1(5), 31–65. https://doi.org/10.4018/978-1-5225-0675-1.ch002

Armisén, A., Agustín, L., Benitez, Y., Coronel A., Pérez de Prada, L., Alonso, J. A., Salvador, E. et al. (2018). BIM aplicado al Patrimonio Cultural. Guía
Usuarios BIM, 46. https://www.buildingsmart.es/bim/gu%C3%ADas-ubim/

Athanasoulis, D., Siou, X. & Zirogianni, T. (2017). Historical Imprints and Virtual Representation Issues in Mid-Byzantine Acrocorinth Castle. Virtual
Archaeology Review, 8(17), 10-19. https://doi.org/10.4995/var.2017.5959

Benavides López, J. A., Martín Civantos, J. M. y Rouco Collazo, J. (2019). Levantamiento arquitectónico y análisis arqueológico del Castillo de Piñar
como punto de partida para su conservación. Virtual Archaeology Review, 11(22), 95-115. https://doi.org/10251/138328

Boeykens, S., Himpe, C. & Martens, B. (2012). A case study of using BIM in Historical Reconstruction. The Vinohrady synagogue in Prague. eCAADe
and CVUT, Faculty of Architecture. https://doi.org/10.13140/2.1.2997.0721

Boissier Domínguez, V. (2016). Habitar el patrimonio. ANALES de la Real Academia Canaria de Bellas Artes, 9, 211-214. https://doi.org/10.1016/j.
scs.2020.102296

Brumana, R., Della Torre, S., Oreni, D., Previtali, M., Cantini, L., Barazzettu, L., Franchi, A. & Banfi, F. (2017). HBIM Challenge among the Paradigm
of Complexity, Tools and Preservation: The Basilica di Collemaggio 8 Years after the Earthquake (L‘Aquila). International Archives of the
Photogrammetry, Remote Sensing and Spatial Information Sciences, XLII-2/W5, 97-104. e. https://doi.org/10.5194/isprs-archives-XLII-2-
W5-97-2017

Brumana, R., Oreni, D., Raimondi, A., Georgopoulos, A. and Bregianni, A. (2013). From survey to HBIM for documentation, dissemination and
management of built heritage. Digital Heritage International Congress (Digital Heritage) 2013, 497-504. https://doi.org/10.1109/
DigitalHeritage.2013.6743789

Carrera Díaz, G. (2016). Propuesta metodológica para la documentación y gestión del patrimonio cultural inmaterial como estrategia de desarrollo
social y territorial [Tesis doctoral, Universidad de Sevilla]. https://idus.us.es/handle/11441/34477

Carta de Venecia. (1964). Carta internacional sobre la conservación y la restauración de monumentos y sitios. Segundo Congreso Internacional de
Arquitectos y Técnicos de Monumentos Históricos, Venecia 1964.http://www.icomos.org.mx/ venecia.ph

Carta de Atenas (1941). Carta internacional sobre la conservación y la restauración de monumentos y sitios. Cuarto Congreso Internacional de
Arquitectura Moderna (CIAM) .http://www.icomos.org.mx/ atenas.ph

Castellano Román, M. & Pinto Puerto, F. (2019). Dimensions and Levels of Knowledge in Heritage Building Information Modelling, HBIM: The model
of the Charterhouse of Jerez (Cádiz, España). Digital Applications in Archeology and Cultural Heritage, 14, 1-11. https://doi.org/10.1016/j.
daach.2019.e001

Castellano Román, M. (2015). Generación de un modelo de información del patrimonio inmueble en el momento de su protección jurídica. EGA

128 Celia Chacón Carretón

<!-- p. 129 -->

Revista de Expresión Gráfica Arquitectónica, 20(26), 266-277. https://doi.org/10.4995/ega.2015.4060

Castellano Román, M. (2017). La Cartuja de Nuestra Señora de la Defensión en Jerez de la Frontera: un modelo digital de información para la tutela
de bienes inmuebles del patrimonio cultural [Tesis doctoral, Universidad de Sevilla]. https://idus.us.es/handle/11441/65027

Català Domènech, J. M. (2005). La imagen compleja. La fenomenología de las imágenes en la era de la cultural visual. Servei de Publicacions de la
Universitat Autònoma de Barcelona.

D’Alençon, R., Justiniano, C., Márquez, F. y Valderrama C. (2009). Parámetros y estándares de habitabilidad: calidad en la vivienda, el entorno
inmediato y el conjunto habitacional. Universidad Católica de Chile, 9, 271-304. https://doi.org/10.33349/2018.0.4125

Desogus, G., Quaquero, E., Rubiu, G., Gatto, G. & Perra, C. (2021). BIM and IoT Sensors Integration: A Framework for Consumption and Indoor
Conditions Data Monitoring of Existing Buildings. Sustainability, 13(8), 1-22. https://doi.org/10.3390/su13084496

Domínguez Pérez, M. (2019). Del patrimonio como la cristalización de la historia de la comunidad urbana y su identidad. PH Instituto Andaluz del
Patrimonio Histórico, 97, 126-128. https://doi.org/10.33349/2019.97.4371

Edwards, J. (2017). “It’s BIM–but not as we know it!”, in Heritage Building Information Modelling. Routledge.

Entziane, K. & Scharmann, R. (2015). BIM for Existing Buildings, in Building Information Modeling. Springer Fachmedien Wiesbaden: Wiesbaden,
Germany, 8, 371–383. https://doi.org/10.3390/su13084496

Garagnani, S. (2013). Building Information Modeling and real world knowledge: A methodological approach to accurate semantic documentation
for the built environment. Digital Heritage International Congress (Digital Heritage) 2013, 489-96. https://doi.org/10.1109/
DigitalHeritage.2013.6743788

García Molina, D. F., González Merino, R., Rodero Pérez, J. y Carrasco Hurtado, B. (2021). Documentación 3D para la conservación del patrimonio
histórico: el Castillo de Priego de Córdoba. Virtual Archaeology Review, 12(24), 115-130. https://doi.org/10251/161456

González Pérez, C. (2018). Modelado de información para arqueología y antropología: principios de ingeniería de software para patrimonio cultural.
Createspace Independent Publishing Platform.

Hichri, N., Stefani, C., Luca, L., Véron, P. & Hamon, G. (2013). From point cloud to BIM: a survey of existing approaches. International Archives of
the Photogrammetry, Remote Sensing and Spatial Information Sciences. XL-5/W2, 343-348. https://doi.org/10.5194/isprsarchives-XL-5-
W2-343-2013

Hidalgo Prieto, R. (2010). La ciudad dentro de la ciudad: reflexiones sobre la gestión y conservación del patrimonio arqueológico en ámbito urbano
en Andalucía. Seminario de Arqueología, Universidad Pablo de Olavide, Sevilla.

Jiménez Martín, A y Pinto Puerto, F. (2003). Levantamiento y análisis de edificios. Tradición y futuro. Universidad de Sevilla. Secretariado de
Publicaciones. Instituto Universitario de Ciencias de la Construcción.

Jordán Palomar, I., Tzortzopoulos, P., García Valldecabres, J., & Pellicer, E. (2018). Protocol to manage heritage-building interventions using heritage
building information modelling (HBIM). Sustainability, 10(908), 1-19. https://doi.org/doi:10.3390/su10030908

Jordán Palomar, I. (2019). Protocol to manage heritage-building interventions using Heritage Building Information Modelling (BIM) [Tesis doctoral,
Universitat Politècnica de València y University of Huddersfield]. https://riunet.upv.es/handle/10251/321

Kerr, J. (2013). The Seventh Edition. Conservation Plan. A Guide to the Preparation of Conservation Plans for Places of European Cultural Significance.
ICOMOS Australia.

Korro Bañuelos, J., Rodríguez Miranda, Á., Valle Melón, J. M., ZornozaIndart, A., Castellano Román, M., Angulo Fornos, R., Pinto Puerto, F., Acosta
Ibáñez, P. &, Ferreira Lopes, P. (2021). The Role of Information Management for the Sustainable Conservation of Cultural Heritage.
Sustainability, 13(8), 1-21. https://doi.org/10.3390/su13084325

Ley 14/2007, de 26 de noviembre, del Patrimonio Histórico de Andalucía. Presidencia de la Junta de Andalucía. Boletín Oficial de la Junta de
Andalucía, 248, de 19 de diciembre de 2007 y Boletín Oficial del Estado, 38, de 13 de febrero de 2008, 2008-2494. https://www.google.
com/url?sa=t&rct=j&q=&esrc=s&source=web&cd=&ved=2ahUKEwih--SY167xAhVQQUEAHcf2AUIQFjAAegQIBBAD&url=https%3A%
2F%2Fwww.boe.es%2Fbuscar%2Fpdf%2F2008%2FBOE-A-2008-2494-consolidado.pdf&usg=AOvVaw0VJISEp5DT3YQ0B8MPRNCh

Lledó, E. (2018). Sobre la educación: la necesidad de la literatura y la vigencia de la filosofía. Barcelona Taurus.

TFG | Aplicación de la herramienta BIM al patrimonio arquitectónico 129

<!-- p. 130 -->

Logothetis, S., Delinasiou, A. & Stylianidis, E. (2015). Building Information Modelling for Cultural Heritage: a Review. International Archives of the
Photogrammetry, Remote Sensing and Spatial Information Sciences, II-5/W3, 177– 183. https://doi.org/10.5194/isprsannals-II-5-W3-177-
2015

López, F. J., Lerones, P .M., Llamas, J., Gómez García-Bermejo, J. & Zalama, E. (2017). A Framework for Using Point Cloud Data of Heritage
Buildings Toward Geometry Modeling in A BIM Context: A Case Study on Santa Maria La Real De Mave Church. International Journal of
Architectural Heritage, 11(7), 965–986. https://doi.org/10.1080/15583058.2017.1325541

Martínez Rubio, J., Fernández Martín, J. J. y San José Alonso, J. I. (2018). Implementación de escáner 3D y fotogrametría digital para la documentación
de la iglesia de La Merced de Panamá. EGA Expresión Gráfica Arquitectónica, 23(32), 208-219. https://doi.org/10.4995/ega.2018.9811

Manfren, M., Aste, N., Leonforte, F., Del Pero, C., Buzzetti, M., Adhikari, R. S. & Zhixing, L. (2020). Parametric energy performance analysis
and monitoring of buildings: Heart Project Platform case study. Sustainable Cities and Society, 61, 22-43. https://doi.org/10.1016/j.
scs.2020.102296

Martin, O. y Piatti, G. (2009). World Heritage and Buffer Zones, International Expert Meeting on World Heritage and Buffer Zones. World Heritage
Papers, 25, 154-86. https://doi.org/10.30827/cuadgeo.v53i2.2360

Moreno Pérez, J. R. y García de Casasola Gómez, M. (2017). Patrimonio y habitabilidad contemporánea. PH Instituto Andaluz del Patrimonio
Histórico, 9, 120-123. https://doi.org/10.33349/2017.0.3913

Molinero Merchán, J. A. (2007). El convento de Santa Clara de la Columna de Belalcázar. Diputación provincial de Córdoba. Delegación de Cultura.

Murphy, M., Corns, A., Cahill, J., Eliashvili, K., Chenau, A., Pybus, C., Shaw, R., Devli, G., Deevy, A. & Truong-Hong, L. (2017). Developing Historic
Building Information Modelling Guidelines and Procedures for Architecture Heritage in Ireland. International Archives of the Photogrammetry,
Remote Sensing and Spatial Information Sciences, XLII-2/W5, 539-546. https://doi.org/10.5194/isprs-archives-XLII-2-W5-539-2017

Murphy, M., McGovern, E. & Pavia, S. (2009). Historic building information modelling (HBIM). Structural Survey, 27(4), 311–327. https://doi.
org/10.1108/02630800910985108

Naeyer, A. de, Arroyo, S. and Blanco, J. (2000). Krakow Charter 2000: principles for conservation and restoration of built heritage. Department of
Architecture and urban planning. Bureau Krakow.

Nieto Julián, J. E. (2014). Generación de modelos de información para la gestión de una intervención en el patrimonio arquitectónico [Tesis doctoral,
Universidad de Sevilla]. https://idus.us.es/handle/11441/70873

Oreni, D., Brumana, R., Della Torre, S., Banfi, F. and Previtali, M. (2014). Survey turned into HBIM: the restoration and the work involved concerning
the Basilica di Collemaggio after the earthquake (L’Aquila). International Archives of the Photogrammetry, Remote Sensing and Spatial
Information Sciences, XLII-2/W5, 267-273. https://doi.org/doi:10.3390/su10030908

Organización Mundial de la Salud. (2000). Informe sobre la salud en el mundo 2000. Mejorar el desempeño de los sistemas de salud. Ginebra, Suiza:
World Health Report OMS. https://apps.who.int/iris/handle/10665/42357

PetroBIM (2014). PetroBIM. http://petrobim.com/

Phillips, A. (2002). Directrices de manejo para las áreas protegidas de la categoría V de la UICN: Paisajes terrestres y marinos protegidos. UICN
Gland, Suiza y Cambridge, Reino Unido.

Pinto Puerto, F. (2018). La tutela sostenible del patrimonio cultural a través de modelos digitales BIM y SIG como contribución al conocimiento e
innovación social. PH Instituto Andaluz del Patrimonio Histórico, 93, 27-29. https://doi.org/10.33349/2018.0.4125

Pinto Puerto, F., Angulo Fornos, R., Castellano Román, M., Guerrero Vega, J. M. y Pastor Gil, F. (2012). Construcción de una base cartográfica activa
para el conjunto arqueológico de Itálica. Boletín del Instituto Andaluz del Patrimonio Histórico, 20(83), 116-119. https://doi.org/10.33349/2
011.77.3115

Pinto Puerto, F. y Guerrero Vega, J. M. (2015). Modelos digitales aplicados a la intervención del patrimonio arquitectónico: La restauración del remate
sureste de la puerta de San Cristóbal en la catedral de Sevilla. Virtual Archaeology Review, 6(12), 103-108. https://doi.org/10251/98143

Pinto Puerto, F., Mora Vicente, G. y Guerrero Vega, J. M. (2019). Trabajos previos y paralelos integrados en el proyecto de restauración de la capilla
de los Tocino (s. XV) en la iglesia de San Juan de los Caballeros de Jerez de la Frontera. Arqueología de la Arquitectura, 16, 55-68. https://
doi.org/10.3989/arq.arqt.2019.008

130 Celia Chacón Carretón

<!-- p. 131 -->

Real Decreto 235/2013, de 5 de abril, por el que se aprueba el procedimiento básico para la certificación de la eficiencia energética de los edificios.
Boletín Oficial del Estado, 89, de 14 de abril de 2013, 2013-3904. https://www.boe.es/buscar/act.php?id=BOE-A-2013-3904

Romero Moragas, C. (2017). Patrimonio y resiliencia. PH Instituto Andaluz del Patrimonio Histórico, 91, 132-133. https://doi.org/10.33349/2017.0.3
870

Rueda, S. (1996). Habitabilidad y calidad de vida. Cuadernos de Investigación Urbanística, 42, 29-33. https://doi.org/10.1007/s11625-014-0274-4

Sennett, R. (2019). Construir y habitar. Ética para la ciudad. Barcelona Anagrama.

Tucci, G., Bonora, V., Conti, A. & Fiorini, L. (2017). High-quality 3D Models and their Use in a Cultural Heritage Conservation Project. International
Archives of the Photogrammetry, Remote Sensing and Spatial Information Sciences, XLII-2/W5, 687-693. https://doi.org/10.5194/isprs-
archives-XLII-2-W5-687-2017

Tucci, G., Conti, A., Fiorini, L., Corongiu, M., Valdambrini, N y Matta, C. (2019). M-BIM: A new tool for the Galleria dell’Accademia di Firenze. Virtual
Archaeology Review, 10(21), 40-55. https://doi.org/10.4995/var.2019.11943

UNESCO. (2014). Manual de referencia. Gestión del Patrimonio Mundial cultural. https://www.google.com/url?sa=t&rct=j&q=&esrc=s&source=we
b&cd=&cad=rja&uact=8&ved=2ahUKEwj_qJbqnLLxAhVSzRoKHXvTBecQFjABegQIBRAD&url=https%3A%2F%2Fwhc.unesco.org%2F
document%2F130488&usg=AOvVaw0VITh7Exhp2pg9JFDL7hRA

Volk, R., Stengel, J. & Schultmann F. (2014). Building Information Modelling (BIM) for existing buildings. Literature review and future needs. Automation
in Construction, 38, 109-127. https://doi.org/10.1016/j.autcon.2013.10.023

Xu, L., Marinova, D. & Guo, X. (2015). Resilience thinking: a renewed system approach for sustainability science. Sustainability Science, 10(1),
123-138. https://doi.org/10.1007/s11625-014-0274-4

Zhou, M., Geng, G. & Wu, Z. (2012). Digital Preservation Technology for Cultural Heritage. Springer Berlin/Heidelberg, Germany.

Zita Sampaio, A., Gomes, A. M., Sánchez Lite, A., Zulueta, P. & González Gaya, C. (2021). Analysis of BIM Methodology Applied to Practical Cases
in the Preservation of Heritage Buildings. Sustainability, 13(6), 1-21. https://doi.org/10.3390/su13063129

TFG | Aplicación de la herramienta BIM al patrimonio arquitectónico 131

<!-- p. 132 -->


