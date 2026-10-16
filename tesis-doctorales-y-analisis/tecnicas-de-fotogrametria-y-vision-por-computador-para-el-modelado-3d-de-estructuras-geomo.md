---
type: libro
title: "Técnicas de fotogrametría y visión por computador para el modelado 3D de estructuras geomorfológicas dinámicas"
author: "Javier de Matías Bejarano"
categoria: "Tesis doctorales y análisis"
paginas: 155
extraccion: "texto"
fuente: "local:E:/Biblioteca digital/Tesis doctorales y análisis/Técnicas de fotogrametría y visión por computador para el modelado 3D de estructuras geomorfológicas dinámicas.pdf"
convertido: 2026-10-13
---

# Técnicas de fotogrametría y visión por computador para el modelado 3D de estructuras geomorfológicas dinámicas

> Texto extraído de `Tesis doctorales y análisis/Técnicas de fotogrametría y visión por computador para el modelado 3D de estructuras geomorfológicas dinámicas.pdf` (155 páginas, texto). El PDF original está en el disco E: (Biblioteca digital); `<!-- p. N -->` marca el inicio de cada página.

<!-- p. 1 -->

TESIS DOCTORAL

TÍTULO: TÉCNICAS DE FOTOGRAMETRÍA Y VISIÓN POR
COMPUTADOR PARA EL MODELADO 3D DE ESTRUCTURAS
GEOMORFOLÓGICAS DINÁMICAS

AUTOR: JAVIER DE MATÍAS BEJARANO

DEPARTAMENTO DE INGENIERÍA DE SISTEMAS INFORMÁTICOS Y
TELEMÁTICOS

Conformidad de los directores:

Fdo: José Moreno del Pozo Fdo: José Jesús Guerrero Campo

2013

<!-- p. 2 -->

Técnicas de fotogrametría y visión por computador para el modelado 3D de
estructuras geomorfológicas dinámicas.

Códigos UNESCO: 2209.90, 2504.04, 2506.07.

Palabras clave: Fotogrametría, Visión por computador, Geomorfología, Glaciares
rocosos.

Resumen

Los diferentes enfoques que tienen la visión por computador y la fotogrametría de

acercarse al problema del modelado y medida tridimensionales (3D) aportan un

interesante punto de partida para esta tesis doctoral. Son disciplinas con objetivos

similares (la construcción de modelos 3D de objetos reales, entre otros), pero

provienen de mundos dispares y la forma de acercarse al problema es diferente y a la

vez complementaria.

En esta tesis se pretende combinar técnicas desarrolladas en el campo de la visión

por computador y de la fotogrametría para desarrollar métodos automáticos que nos

permitan generar productos cartográficos tridimensionales de estructuras dinámicas.

Aunque las técnicas que se desarrollen durante este trabajo pretenden ser

generales en cuanto a su campo de aplicación, nos centraremos principalmente en un

caso de especial relevancia. En concreto se trabajará con estructuras geomorfológicas

dinámicas (glaciares rocosos), que conllevan una serie de características especiales

que dificultan el uso de técnicas convencionales y son de gran interés actual en el

ámbito de la geomorfología, entre otras cosas por permitir analizar efectos del

“cambio climático”.

II

<!-- p. 3 -->

Abstract

Computer Vision and Photogrammetry try to solve the problem of 3D

reconstruction in a different way and that is the interesting beggining of this thesis

project. These disciplines have similar objective (3D reconstruction of real objects), but

come from different fields and have very different manners to approach the problem.

The goal of this project is to use known Computer Vision and Photogrammetry

techniques and develope new automatic methods to produce 3D cartography products

of dynamic structures.

Although it is very important get techniques with a general purpose, during thesis

development we work with dynamic geomorphologic structures (rock glaciers), which a

set of special features that make it interesting like field of application. Rock glacier

studies are very interesting because allow experts analyze climate change and his

effects.

III

<!-- p. 4 -->

IV

<!-- p. 5 -->

“Nulla estetica sine ética, ergo apaga y vámonos.”

J.M. Valverde

V

<!-- p. 6 -->

VI

<!-- p. 7 -->

Agradecimientos personales

A Sabela, por ser el pilar de mi vida.

A mi madre, por su apoyo incondicional

A José Juan, por llamarme aquel día a su despacho para iniciar todo este maravilloso
proyecto y ser un apoyo constante durante todos estos años.

A Pepe y Josechu, porque sin ellos aún estaría en la oscuridad más absoluta.

A todos los componentes de IGPU (Ingeniería Geomática y Patrimonio Urbano), José
Juan, Alan, Fernando, Lupe, Pérez,…, por iniciar éste y muchos otros proyectos y por
toda su ayuda en aquello que no es de los de mi gremio.

A todos los componentes de RoboLab, Pablo, Pilar,…, por todas sus aportaciones para
esta tesis.

A los equipos de Antonio Gómez y Enrique Serrano y a todos los que han acudido a
trabajar a pie de campo, Ferrán, Fernando, Ibai, Juanjo, Montse, María, Manu,…, por
lo que me enseñaron de los glaciares y por los buenos momentos que pasamos en las
montañas.

Agradecimientos institucionales

En primer lugar, a la Junta de Extremadura, que me concedió la beca predoctoral con
la que comenzó todo.

En segundo lugar, a las entidades que financiaron los proyectos necesarios para el
trabajo de campo de esta tesis doctoral:

\- “Procesos de ladera y cambios climáticos en montaña atlántica y de

transición: Cordillera Cantábrica y Pirineos” financiado por el Ministerio de

Educación y Ciencia (2007-2009). (Expediente nº: CGL2007 – 65295/BTE)

\- “Geoindicadores de alta montaña y cambio global: Análisis y control de

indicadores geomorfológicos en el parque nacional de Picos de Europa”

financiado por el Ministerio de Medio Ambiente (2008-2009). (Expediente nº:

007 – 2007).

\- “La criosfera como geoindicadora ambiental y del cambio climático: procesos

de ladera asociados al hielo y la nieve en las montañas del norte peninsular

VII

<!-- p. 8 -->

(Pirineos – Cantábrica)” financiado por el Ministerio de Ciencia e Innovación

(2010-2013). (Expediente nº: CGL2010 – 19729)

\- “Criosfera y cambio global en espacios naturales protegidos: control de

procesos geomorfológicos asociados a la nieve y el hielo como geoindicadores

de cambio ambiental en el Parque Nacional Picos de Europa” financiado por

el Ministerio de Medio Ambiente, Rural y Marino (2010-2013). (Expediente nº:

OAPN 053 – 2010).

Especialmente por el proyecto “Degradación de hielo fósil, permafrost y cambio

climático en Sierra Nevada” financiado por el Ministerio de Medio Ambiente (2008-

2009). (Expediente nº: 018 – 2007) y acogido por el grupo de investigación "Paisaje y

paleoambientas en la montaña mediterránea" (Ref. 2009SGR0868).

VIII

<!-- p. 9 -->

IX

<!-- p. 10 -->

X

<!-- p. 11 -->

Índice

\1. Introducción………………………………...…………………………………………3

1.2. Motivación del trabajo………………………………………………………5

1.3. Objetivos…………………………………………………………………….7

1.4. Organización de la tesis……………………………………………………..9

\2. Estado del arte……………………………………………………………………….13

2.1. Situación actual de la fotogrametría……………………………………….13

2.2. Visión por computador: Conceptos generales……………………………..25

2.3. Emparejamiento de imágenes……………………………………………...33

2.4. Métodos para el cálculo de modelos densos 3D…………………………...36

2.5. Medición y monitorización de la dinámica glaciar………………………...40

2.6. Monitorización de glaciares en distintos períodos…………………………45

\3. Metodología………………………………………………………………………….51

3.1. Bloque I: Modelado de las cámaras………………………………………..52

3.1.1. Fase 1: Calibración interna………………………………………52

3.1.2. Fase 2: SIFT como emparejador de puntos………………………54

3.1.3. Fase 3: Geometría epipolar………………………………………56

3.1.4. Fase 4: Orientación externa………………………………………57

3.2. Bloque II: Obtención de una superficie previa…………………………….59

3.2.1. Fase 5: Triangulación: Obtención de puntos 3D…………………59

3.2.2. Fase 6: Triangulación Delaunay: Obtención de una TIN………..60

3.3. Bloque III: Modelo 3D final……………………………………………….62

3.3.1. Fase 7: Mapas densos de profundidad…………………………...62

3.4. Bloque IV: Desplazamiento de bloques……………………………………68

3.4.1. Fase 8: Dense Flow Vectors……………………………………...69

XI

<!-- p. 12 -->

\4. Experimentos………………………………………………………………………...77

4.1. Materiales utilizados……………………………………………………….77

4.1.1. Cámaras utilizadas……………………………………………….78

4.1.2. Instrumental topográfico…………………………………………80

4.2. Escenarios de trabajo………………………………………………………81

4.2.1. Glaciar del Veleta en Sierra Nevada……………………………..82

4.2.2. Helero del Jou Negro (2007)……………………………………111

\5. Conclusiones………………………………………………………………………..119

A.I. Referencias bibliográficas………………………………………………………..127

A.II. Índice de figuras…………………………………………………………………137

A.III. Índice de tablas…………………………………………………………………143

XII

<!-- p. 13 -->

Capítulo 1: Introducción

<!-- p. 14 -->

\1. Introducción

2

<!-- p. 15 -->

\1. Introducción

\1. Introducción

El inicio de esta tesis doctoral se ha de buscar en la confluencia de dos disciplinas

provenientes de mundos distintos y complementarios: la parcela de conocimiento
denominada tratamiento digital de imágenes y visión por computador enmarcada en

el ámbito de las tecnologías informáticas y una segunda derivada de los entornos de la
cartografía y la expresión gráfica, esto es, la fotogrametría. Ambas disciplinas tienen

en común la obtención de modelos tridimensionales del mundo real a partir de datos

fotográficos. Por eso el primer objetivo global consiste en aunar criterios, conceptos,

metodologías, herramientas y técnicas comunes de estas dos parcelas del conocimiento.

Debemos preguntarnos: ¿qué proponen cada una de las dos disciplinas para solucionar

el problema del modelado 3D? y ¿qué ventajas tiene cada una de ellas?

La pretensión principal de este trabajo es el diseño y desarrollo de metodologías

mixtas conducentes a la obtención de productos cartográficos digitales, utilizando como

vía de adquisición de datos la fotografía (ya sea aérea o terrestre).

Se puede observar en el título de este trabajo que las técnicas desarrolladas tienen
un campo de aplicación que es el estudio de estructuras geomorfológicas dinámicas.

En concreto los glaciares rocosos son un tipo de estructura geomorfológica con unas

características especiales, complejo para su tratamiento con las técnicas usuales, y

además de gran interés actual en el ámbito de la geomorfología, entre otras cosas por ser

considerado un buen indicador para la realización de estudios que versen acerca del

llamado “cambio climático”.

Para solucionar el problema de la monitorización de glaciares existe una amplia

variedad de técnicas. Sin embargo, se pretende obtener una metodología que dé una

solución con un flujo de trabajo más sencillo, con similares o mejores precisiones de las

que actualmente se obtienen y con una mayor variedad de productos cartográficos, que

sean útiles en los estudios geomorfológicos de glaciares. En esta tesis doctoral por tanto,

se pretende desarrollar una metodología de trabajo capaz de resolver los problemas que

surgen en el uso del software fotogramétrico común, sobre todo en campos de

aplicación como éste. La complejidad de este tipo de problemas es sensiblemente mayor

al de otro tipo de prácticas.

3

<!-- p. 16 -->

\1. Introducción

La visión por computador y la fotogrametría actualmente consiguen resolver

muchos de los problemas que se plantean al proponer esta nueva metodología. Es

importante encontrar los conceptos, herramientas y técnicas comunes existentes entre

ambas. A partir de esta visión conjunta deberá surgir esta nueva metodología que
resuelva los problemas que en un principio se proponen, tanto en lo relativo al mayor
automatismo de las técnicas (simplificando los flujos de trabajo y por tanto reduciendo

la labor humana) como en la obtención de productos cartográficos más complejos.

Lo interesante de la tesis es llegar a conocer, a efectos prácticos, que puede aportar

la unión de las dos materias y que métodos y técnicas podemos conocer y proponer que
saquen el máximo rendimiento a esa unión. La aparición de nuevas técnicas de
matching robusto (Lowe 2004, Bay et al. 2006, Mikolajczyk y Schmid 2003 y 2005,
Mikolajczyk et al. 2005), la proliferación de técnicas de emparejamiento denso (Seitz

et al. 2006, Goesele et al. 2006) y todo el conocimiento que se tiene hoy día de la
geometría multivista (Trucco y Verri 1998, Faugeras y Luong 2001, Hartley y

Zisserman 2003), han hecho de la visión por computador evolucione hasta cotas no

previstas en los últimos años. Si observamos todo este conocimiento desde el interés

que todas estas mejoras pueden tener en el mundo de la fotogrametría, nos damos

cuenta del rendimiento que se puede lograr de esa unión.

Aunque esta tesis doctoral tiene interés en muchos campos de aplicación

(Ingeniería minera, ingeniería civil,…), como método de fotogrametría, se ha
pretendido centrar en un caso muy concreto. El estudio de estructuras
geomorfológicas dinámicas (más específicamente glaciares rocosos), es un campo de

aplicación con un alto interés científico y un buen campo de pruebas para la

metodología a desarrollar.

En primer lugar tiene un alto interés científico en el ámbito de la geomorfología.

Desde al menos el siglo XIX el estudio de glaciares rocosos ha sido una disciplina de

especial relevancia. Además su estudio y seguimiento se ha convertido en uno de los

factores más importantes a estudiar cuando lo que se pretende es observar las

variaciones del clima en las diversas áreas del mundo. La investigación de su

dinamismo, los cambios de volúmenes que sufre y su relación con la variación de

temperaturas convierten su estudio en un asunto prioritario respecto a otros fenómenos

geomorfológicos. Es por esto que entre los geomorfólogos surge la necesidad de obtener

mejores productos cartográficos, más complejos, más completos, con mayor

4

<!-- p. 17 -->

\1. Introducción

información y que puedan adaptarse a las necesidades de monitorización de un

fenómeno tan especial como el del fenómeno del glaciarismo. Hasta ahora los

geomorfólogos disponían de diversas metodologías para la obtención de cartografía o

información tridimensional (Sistemas de posicionamiento global, Métodos topográficos,

Fotogrametría convencional,…), sin embargo son necesarios métodos basados en las

nuevas tecnologías que proporcionen un mayor automatismo, capaces de generar mayor

cantidad de información 3D y que además nos permitan monitorizar la dinámica de los

glaciares a través del tiempo (normalmente años).

Como se decía anteriormente, se puede considerar el campo del glaciarismo como

un banco de pruebas desde el que partir para conseguir una metodología aplicable en

multitud de campos en los que haya una similitud con las características especiales de
este fenómeno geomorfológico. Los campos de aplicación pueden ir desde la ingeniería
de minas, en el estudio de canteras y explotaciones a cielo abierto, hasta la ingeniería
civil, como ayuda a las medidas topográficas realizadas en proyectos de vías de

comunicación como carreteras o ferrocarriles.

1.2. Motivación del trabajo

La motivación de este trabajo se puede dividir en dos importantes aspectos que

serán los que se desarrollen a lo largo de la tesis doctoral.

En primer lugar se trata del aspecto técnico y posicional del trabajo. La relación de
los grupos de la Universidad de Extremadura, IGPU (Ingeniería Geomática y

Patrimonio Urbano), integrado por investigadores del ámbito de la geomática, y
RoboLab (Laboratorio de Robótica y Visión), integrado por investigadores del ámbito

de la robótica y la visión por computador, estableció la primera piedra de este trabajo.

Ambos grupos de investigación desarrollaban y utilizaban métodos y técnicas en los que

el objetivo final no era otro que la obtención de información tridimensional (cualquier

tipo de escena a reconstruir) a partir de información bidimensional (en forma de

imágenes en cualquier soporte). Por tanto, si ambos grupos tenían ese objetivo común,

utilizando metodologías diferentes y complementarias, ¿por qué no aunar esfuerzos,

técnicas y metodologías de trabajo con ese fin?

De esta pregunta surge el proyecto de investigación “Desarrollo de un restituidor

digital para la realización de cartografía automática bajo Linex” financiado por la

5

<!-- p. 18 -->

\1. Introducción

Junta de Extremadura (2PR04B028) y donde los investigadores de ambos grupos

establecen los primeros puntos de unión que motivan esta idea. El autor de este trabajo

comienza su labor investigadora en este proyecto y ese momento se convierte en el

germen de esta tesis doctoral.

Un papel también importante lo ha jugado el profesor José Jesús Guerrero Campo
(miembro del grupo RoPeRT, “Robótica, percepción y tiempo real”, de la Universidad

de Zaragoza) que junto al profesor José Moreno del Pozo (miembro del grupo
RoboLab, de la Universidad de Extremadura) comienzan en 2005 a tutelar esta tesis

doctoral.

El segundo aspecto importante en cuanto a la motivación del trabajo es la

aplicación práctica de la metodología a desarrollar, como es el modelado de estructuras

geomorfológicas dinámicas. El autor de esta tesis doctoral ha participado en varios

proyectos multidisciplinares en los que se aúnan expertos del área de la geomática con

los del área de la geomorfología. La experiencia en estos proyectos ha traído dos

importantes avances para el trabajo. El primero tiene que ver con el conocimiento

adquirido acerca de lo que se pretende conseguir, saber que técnicas y productos

cartográficos se han utilizado anteriormente en este tipo de proyectos y sobre todo como

se pueden tratar de mejorar. El segundo es más práctico y tiene que ver con la obtención

de datos (normalmente imágenes e información topográfica) imprescindibles para

experimentar la metodología propuesta.

Los proyectos en los que el autor ha participado como investigador son los

siguientes:

\- “Escáner móvil autónomo robotizado” financiado por la Junta de Extremadura

(2009-2012). (Expediente nº: PDT09A044)

\- “Modelado tridimensional de precisión, estudio de patologías- estructural y

paseos virtuales por el patrimonio histórico y cultural de Extremadura”

financiado por la Junta de Extremadura (2009-2012). (Expediente nº:

PRI09A025)

\- “Procesos de ladera y cambios climáticos en montaña atlántica y de

transición: Cordillera Cantábrica y Pirineos” financiado por el Ministerio de

Educación y Ciencia (2007-2009). (Expediente nº: CGL2007 – 65295/BTE)

6

<!-- p. 19 -->

\1. Introducción

\- “Geoindicadores de alta montaña y cambio global: Análisis y control de

indicadores geomorfológicos en el parque nacional de Picos de Europa”

financiado por el Ministerio de Medio Ambiente (2008-2009). (Expediente nº:

007 – 2007)

\- “Degradación de hielo fósil, permafrost y cambio climático en Sierra Nevada”

financiado por el Ministerio de Medio Ambiente (2008-2009). (Expediente nº:

018 – 2007)

\- “La criosfera como geoindicadora ambiental y del cambio climático: procesos

de ladera asociados al hielo y la nieve en las montañas del norte peninsular

(Pirineos – Cantábrica)” financiado por el Ministerio de Ciencia e Innovación

(2010-2013). (Expediente nº: CGL2010 – 19729)

\- “Criosfera y cambio global en espacios naturales protegidos: control de

procesos geomorfológicos asociados a la nieve y el hielo como geoindicadores

de cambio ambiental en el Parque Nacional Picos de Europa” financiado por

el Ministerio de Medio Ambiente, Rural y Marino (2010-2013). (Expediente nº:

OAPN 053 – 2010)

Estas dos principales motivaciones están, implícita o explícitamente, reflejadas a lo

largo de todos los capítulos de esta tesis doctoral.

1.3. Objetivos

El objetivo general de este trabajo, tal y como se puede deducir de su título, es el de
establecer una metodología que permita obtener modelos tridimensionales de
estructuras geomorfológicas dinámicas, a través del uso de técnicas fotogramétricas y

de visión por computador.

Concretando ese objetivo general se pretende desarrollar una metodología de
trabajo en la que se aúnen técnicas provenientes de la fotogrametría y la visión por
computador. El fin que se persigue es simplificar el complejo flujo de trabajo que en la

actualidad se utiliza en la realización de un proyecto fotogramétrico. La pregunta que

cabe hacerse es que beneficios puede aportar a un proyecto de reconstrucción

tridimensional la unión de las dos disciplinas. En el capítulo 2, referente al estado del

arte, se exponen ambas. Por un lado se trata la forma que tiene la fotogrametría de

7

<!-- p. 20 -->

\1. Introducción

afrontar la reconstrucción tridimensional de una escena, de que fases consta el método

fotogramétrico y como se han automatizado a lo largo de los últimos años algunas de las

fases. Por otro lado se exponen los avances producidos en el ámbito de la visión por

computador y que técnicas pueden facilitar la propuesta que se realiza en este trabajo.

La metodología que se desarrolla ha de asociar ambas facetas. Lo que se busca es una

propuesta automática, o lo más automática posible, y que conlleve un flujo de trabajo

menos complejo y con un menor tiempo de trabajo frente a las propuestas clásicas.

En segundo lugar se encuentra un objetivo puramente técnico, la utilización de una
metodología que permita la obtención de reconstrucciones con una gran densidad de
puntos. Se precisa de una técnica que supere la densidad obtenida en propuestas

anteriores (López et al. 2006, Sanjosé y Lerma 2001 y 2004). En el apartado 2.4 se

detallan los aspectos más interesantes que caracterizan a los métodos de

emparejamiento denso, así como las diferentes propuestas aparecidas en la literatura en

los últimos años. Se necesitan obtener del orden del millón de puntos 3D con la

precisión suficiente como para ser útiles en posteriores aplicaciones.

El tercer gran objetivo es también de carácter técnico, aunque con una clara

vocación práctica. Es el derivado de su aplicación al ámbito de la reconstrucción de
estructuras geomorfológicas dinámicas (mayoritariamente glaciares rocosos). Se

pretende desarrollar técnicas que permitan relacionar los datos de la reconstrucción de

una campaña con los datos de otras campañas, es decir, establecer una secuencia

temporal predecible. Los productos cartográficos que se obtienen no se limitan a

reconstrucciones tridimensionales estáticas (de un solo instante en el tiempo), sino que

estos productos sean más completos y tengan en cuenta la dinámica de la estructura a

modelar. De esta forma, se puede estudiar con más detalle la evolución en el tiempo de

los distintos bloques de la estructura bajo estudio. Será interesante conocer que técnicas

se pueden desarrollar con este objetivo, que precisiones se pueden obtener y cuantas

campañas son necesarias para este tipo de relaciones.

Existe un interés creciente en el estudio de los fenómenos de glaciarismo (en este

caso glaciares rocosos y heleros) por su relación con los efectos del “cambio climático”.

En el apartado 2.5 del siguiente capítulo se hará un repaso por los trabajos existentes

que tienen un objetivo similar y cual ha sido la evolución producida en los últimos años.

Aunque se pretende desarrollar una metodología de propósito general, parte de la

motivación de este trabajo surge de su campo de aplicación. En el capítulo de

8

<!-- p. 21 -->

\1. Introducción

experimentos se muestran ejemplos de aplicación de esta metodología en proyectos

geomorfológicos. Además, se incluyen referencias bibliográficas de trabajos del ámbito

de la geomorfología, donde se ha aplicado la metodología de trabajo propuesta.

Los objetivos del trabajo se pueden resumir en:

\- Simplificar el flujo de trabajo del método fotogramétrico.

\- Conseguir una mayor automatización del proceso de reconstrucción de una

escena tridimensional.

\- Reducir el tiempo de trabajo necesario en un proyecto de reconstrucción

tridimensional.

\- Conseguir la densidad de información 3D suficiente para la producción de

cartografía de gran nivel de detalle.

\- Conseguir la precisión suficiente que exigen los proyectos geomorfológicos

donde se aplica la metodología de trabajo propuesta.

\- Obtener mejores productos cartográficos a utilizar en la monitorización de

glaciares. Sobre todo en lo relativo a la relación entre campañas.

1.4. Organización de la tesis.

La tesis doctoral está organizada en 5 capítulos:

\- Este primer capítulo, donde se realiza la introducción del trabajo, haciendo

hincapié en las motivaciones y objetivos del mismo.

\- El segundo capítulo, dedicado al estado del arte, donde se establecen las

técnicas, métodos y trabajos principales publicados en relación con los

objetivos de este trabajo.

\- El tercer capítulo, donde se especifica la metodología desarrollada en este

trabajo. Se establecen las fases en las que se divide ésta especificando los

resultados de cada una de ellas y su importancia en el resultado final.

9

<!-- p. 22 -->

\1. Introducción

\- El cuarto capítulo está dedicado a los experimentos, exponiendo los

resultados obtenidos en la aplicación práctica de la metodología propuesta.

Se especifican los materiales utilizados así como los escenarios donde se

realizaron los experimentos.

\- El quinto capítulo es el dedicado a las conclusiones, indicando hasta que

punto se han alcanzado los objetivos marcados en el inicio de la tesis.

10

<!-- p. 23 -->

Capítulo 2: Estado del arte

<!-- p. 24 -->

\2. Estado del arte

12

<!-- p. 25 -->

\2. Estado del arte

\2. Estado del arte.

Antes de hablar de la metodología que se propone en esta tesis doctoral, es

indispensable conocer el estado en que se encuentran los problemas que se plantean

para la consecución de los objetivos propuestos en el capítulo de introducción. En

primer lugar, en los apartados 2.1 y 2.2, se aborda la situación actual de las dos grandes

materias sobre las que se cimenta esta tesis doctoral, es decir, la fotogrametría y la

visión por computador. Tal y como se ha indicado en el anterior capítulo, son dos

materias provenientes de mundos diferentes, con fines muy similares y que aportan cada

una distintas mejoras a este trabajo. Posteriormente, en el apartado 2.3, se explica la

evolución y el estado actual en que se encuentra la medición de glaciares mediante

fotogrametría (en sus diferentes formas). Éstos serán las estructuras específicas en las

que se aplica la solución obtenida, tal y como se explica en el capítulo dedicado a los

resultados experimentales.

Una vez expuestos los tres mundos en que se mueve esta tesis doctoral

(Fotogrametría, visión por computador y geomorfología de glaciares rocosos) es el

momento de entrar en detalles más específicos. Los apartados 2.4, 2.5 y 2.6 explican el

estado de la cuestión en cuanto a los tres aspectos técnicos que marcan las diferencias

de este trabajo con trabajos anteriores. El apartado 2.4 trata el problema del

emparejamiento de imágenes, su evolución, y algunas comparativas que avalan la

utilización de algoritmos para este fin en la solución propuesta. En el apartado 2.5 se

expone el problema del emparejamiento denso. Partiendo de trabajos previos se

exponen los criterios a seguir para la elección de un método adecuado adaptándolo al

campo en que se quiere aplicar. Por último, el apartado 2.6 se centra en los trabajos

existentes para emparejar imágenes de distintas épocas en el problema específico de la

monitorización de glaciares.

2.1. Situación actual de la fotogrametría.

El concepto actual de fotogrametría es bastante amplio. Tradicionalmente la
fotogrametría se ha definido como el proceso de obtener información métrica de un

objeto a través de las medidas realizadas en fotografías. Muy relacionada con la

13

<!-- p. 26 -->

\2. Estado del arte

fotogrametría se encuentra la foto-interpretación, que se define como la extracción de

información cualitativa sobre los objetos fotografiados, mediante el análisis visual
humano y la evaluación de fotografías. Además, se puede añadir la teledetección. Se

define ésta como el conjunto de técnicas que nos permiten utilizar una mayor variedad

de ondas del espectro electromagnético que únicamente las que pueden impresionarse

en una fotografía. Todos estos conceptos están incorporados a los estudios que de la

fotogrametría se hacen actualmente (Wolf y Dewitt 2000, Mikhail et al. 2001 y

McGlone 2004).

La principal tarea de la fotogrametría es rigurosamente establecer las relaciones

geométricas entre la imagen y el objeto en el momento de la toma fotográfica. Una vez

se establece esta relación correctamente, se podrá obtener información del objeto a

partir de las imágenes. Esta relación se establece de dos formas:

\- Analógica: Mediante el uso de artificios ópticos y mecánicos (opción hoy

prácticamente en desuso).

\- Analítica: Donde el modelado es analítico y el proceso digital mediante el uso

de computadores.

La disponibilidad de imágenes en formato digital y el aumento de la capacidad de

proceso de los computadores digitales abrieron una gran variedad de posibilidad de
adaptación de técnicas de otras disciplinas. La primera de ellas es el procesamiento
digital de imágenes. Esta disciplina implica varios tipos de tareas: compresión,

restauración, segmentación o descripción de imágenes. La segunda de estas disciplinas
es el reconocimiento de patrones, el análisis de imágenes por computador consigue la

extracción automática de patrones característicos y su comparación con los de un
diccionario. La otra de las disciplinas implicadas es la inteligencia artificial. Esta

implica el estudio de técnicas que permiten a los computadores hacer aquellas cosas que

actualmente las personas hacen mejor. Cuando estas técnicas se aplican en el mundo de
la imagen se habla de visión por computador. Su principal objetivo es desarrollar

descripciones de objetos a partir de sus imágenes. Los métodos de visión por

computador se han ido incorporando cada vez más al método fotogramétrico, sobre todo

en la automatización de tareas. De esta forma se reduce el trabajo del operador

fotogramétrico.

14

<!-- p. 27 -->

\2. Estado del arte

El método de trabajo que sigue la fotogrametría clásica es el que se conoce como

restitución (Buill et al. 2003 y Lerma 2002). La restitución trata el problema de obtener

y almacenar las coordenadas de un determinado objeto a partir de las correspondientes

fotocoordenadas calculadas sobre el par estéreo (fotografías).

El proceso que se sigue hasta conseguir la intersección entre los rayos homólogos

se denomina orientación, y se puede dividir en los siguientes apartados:

\- Orientación interna: La orientación interna consiste en la reconstrucción

individual de los rayos que impresionaron la imagen fotográfica, eliminando las

deformaciones producidas en el proceso de medición de coordenadas imagen, y

su posterior refinamiento. Para realizar la orientación interna de la pareja de

fotogramas es necesario conocer los datos de calibración de la cámara con la que

se hicieron las fotografías. Estos datos incluyen la distancia focal calibrada, la

posición del punto principal respecto al centro fiducial y la función de distorsión

óptica.

\- Orientación relativa: Se llama orientación relativa al problema de lograr que

los haces, formados mediante la orientación interna, tomen idéntica posición,

con respecto al modelo, a la que tuvieron al ser tomadas las fotografías. Para ello

es necesario orientar las fotografías y el modelo en un sistema de coordenadas

común. Dicho de otro modo, se trata de relacionar el sistema de coordenadas

imagen, propio de la fotografía con el sistema de coordenadas del modelo.

\- Orientación absoluta: En la orientación absoluta lo que se hace es escalar, girar

y desplazar todo el conjunto hasta una posición conocida con respecto a un

sistema de coordenadas terreno. Como se dispone de un modelo semejante al

terreno, mediante un mínimo de 3 puntos de control, para los que se conocen las

coordenadas en ambos sistemas, modelo y terreno, se determinan los 7

parámetros (vector de traslación, ángulos de giro y factor de escala) de la

transformación tridimensional de semejanza que pasa del sistema modelo al

sistema terreno.

\- Restitución: Es la última fase del método y es en ella donde se determinan

finalmente las coordenadas del objeto a cartografiar. El operador fotogramétrico,

mediante el sistemas de coordenadas obtenido en la fase anterior, establece las

coordenadas que considera interesantes para obtener la cartografía final.

15

<!-- p. 28 -->

\2. Estado del arte

El que se ha expuesto es el método clásico. Aunque han surgido muchos avances

con la introducción de la fotogrametría digital, no se han cambiado en gran medida

ninguna de las fases del método expuesto. Más bien los avances se han encaminado a la

automatización de los diferentes procesos que forman el método (Wolf y Dewitt 2000,

Mikhail et al. 2001 y McGlone 2004).

Se ha expuesto el método clásico, con una explicación general de cada fase, pero a

continuación se explicará con más detalle en que consiste. El desarrollo de técnicas

fotogramétricas se basa en tres operaciones básicas:

\- Resection: Se trata de determinar la posición y orientación de una imagen en el

espacio.

\- Intersection: Consiste en calcular las coordenadas de un punto del objeto a

modelar a partir de las coordenadas de 2 o más imágenes.

\- Ambas operaciones se combinan en la tarea de triangulación o block adjustment,

en la que los parámetros de la orientación de la imagen y las coordenadas de los

puntos se calculan símultáneamente.

La combinación de estas tres operaciones básicas da como resultado el método

fotogramétrico. A continuación, se tratan un poco más en detalle el uso de estas

operaciones básicas en alguna de las fases del método fotogramétrico.

Refinado de coordenadas imagen

Los modelos utilizados en fotogrametría describen una geometría de la imagen

ideal para así simplificar las ecuaciones. Existen diversos factores que hacen que el rayo
de luz se desvíe de la línea recta ideal y se obtengan por tanto coordenadas
distorsionadas. Es por ello que se precisa un paso de preprocesado. Estas desviaciones

no aleatorias respecto del modelo matemático se llaman errores sistemáticos. Lo normal

es buscar las causas que producen estos errores sistemáticos para así poder eliminarlos

de las coordenadas imagen. Sin embargo, hay otros casos en los que se detectan estos

errores sistemáticos, como tendencias en los datos sin conocer de forma certera sus

causas. En estos casos, estos errores se tratan de eliminar durante la solución del block

adjustment, es decir, en un algoritmo que permite procesar la orientación y el cálculo de

16

<!-- p. 29 -->

\2. Estado del arte

coordenadas al mismo tiempo. Esta forma de resolver el problema es lo que se conoce

como un proceso de auto-calibración (self calibration).

El objetivo del refinado de las coordenadas imagen es asegurar que los errores en

éstas se ajustan al modelo matemático. Los errores sistemáticos son corregidos en el

orden contrario al que se produjeron. Los errores que se eliminan en esta fase son:

\- Los de los comparadores y los escáneres utilizados.

\- Las posibles deformaciones de las películas fotográficas.

\- El desplazamiento del punto principal.

\- Los errores de distorsión de las lentes.

\- La refracción atmosférica.

\- Los errores de curvatura de la tierra.

Resection

Esta operación consiste en la determinación de la posición y los parámetros de

orientación de la imagen respecto del sistema de coordenadas del objeto en el espacio.

En el caso estándar, se pretende averiguar las coordenadas del centro de proyección de

la cámara (X, Y, Z) y los 3 ángulos que describen la orientación de la cámara (α, φ, κ).

Existen muchas diferentes formulaciones del problema de la resection, optimizadas para

diferentes situaciones, requerimientos computacionales y especificación de precisión.

Aunque se puede encontrar soluciones rápidas y con pocos requerimientos

computacionales, en caso de necesitar soluciones más precisas se requiere de

mediciones redundantes y técnicas de ajuste por mínimos cuadrados. Normalmente esta

operación sólo se utiliza como cálculo de la solución inicial de una operación de block

triangulation.

Retroproyección de un solo rayo

A menudo es necesario calcular la posición en el espacio de un punto que aparece

en una sola imagen. En la proyección de un punto 3D al plano 2D de la imagen hay una

pérdida de la información de profundidad de la escena, por tanto es necesario tener

algún tipo de información adicional para recuperarla. El caso más simple es la

17

<!-- p. 30 -->

\2. Estado del arte

retroproyección a partir de un punto dada su elevación (o eje Z). Para ello se suelen

utilizar la condición de colinealidad. Existe algún caso más complejo como aquel en que

se cuenta con un DEM (Digital Elevation Model o, en español, Modelo Digital de

Elevación). En este caso hay que estudiar la intersección del rayo con la superficie que

describe el DEM.

Intersection

Esta fase se refiere al caso en el que se necesita calcular la posición en el espacio

de un punto que aparece en 2 o más imágenes. La solución estándar es la ecuación de

colinealidad, para así formar un sistema de ecuaciones lineales. También es posible

proponer una solución no lineal mediante la proyección de 2 o más rayos (en función de

las imágenes con las que contamos). Éstos determinan una zona donde buscar el punto

de intersección.

Orientación relativa

Dadas dos imágenes de una escena tomadas desde distintos puntos de vista, se

puede crear un modelo estéreo que permita la visión 3D de la escena. Este

procedimiento se conoce como orientación relativa. Ésta implica la determinación de 5

grados de libertad. Si se considera conocida la orientación interna de las imágenes, cada

imagen tendrá seis parámetros desconocidos (X, Y, Z, α, φ, κ). Aunque no se va a entrar

en detalles, se pueden seguir dos tipos de estrategias para su cálculo:

\- Una orientación relativa utilizando la condición de coplaneidad.

\- Una orientación relativa utilizando las ecuaciones de colinealidad.

Orientación absoluta

Antes de poder usar un par estéreo para fabricar un mapa, se ha de establecer la

relación entre el par y el sistema de coordenadas del objeto. Hay 7 parámetros

implicados en este proceso: una escala, 3 traslaciones y 3 rotaciones. La forma analítica

de la orientación absoluta consiste en una transformación 3D de similaridad:

Y = µ MX + T

18

<!-- p. 31 -->

\2. Estado del arte

donde µ representa la escala, M la matriz de rotación y T la traslación.

Block triangulation

Se ha dicho anteriormente como este proceso es el cálculo de los parámetros de

orientación y las coordenadas de los puntos simultáneamente. El desarrollo de este tipo

de soluciones ha evolucionado en la misma medida que la capacidad de los

computadores. Actualmente todas esas soluciones siguen el método llamado bundle

adjustment (Triggs et al. 2000).

Digital Photogrammetric Workstations (DPW)

Este paso a la era digital de la Fotogrametría ha supuesto la aparición de lo que en

inglés se llaman Digital Photogrammetric Workstations (DPW), que podríamos traducir

como Estación de trabajo para la Fotogrametría Digital, aunque en español también se

conocen por restituidores digitales. Realmente un DPW no es más que un computador

adaptado al trabajo de un operador de Fotogrametría. Consta de un computador al que

se añaden elementos que posibilitan tanto la visualización estereoscópica de la escena,

como dispositivos de entrada de datos especializados en el tipo de trabajos para el que

se ha diseñado el DPW. Por supuesto, además de todos los dispositivos hardware, el

sistema incluye el software necesario para desarrollar productos fotogramétricos

siguiendo las fases típicas del modelo fotogramétrico.

En la figura 2.1 se muestra en un diagrama el esquema que sigue una aplicación

típica de restitución fotogramétrica digital.

19

<!-- p. 32 -->

\2. Estado del arte

Figura 2.1: Esquema general de funcionamiento de un DPW.

Mientras que el flujo de trabajo de cualquier aplicación fotogramétrica es similar a

lo que se indica en la figura anterior, el desarrollo de nuevas técnicas revolucionó la

fotogrametría, automatizando gran parte de las tareas. Hoy día cualquier DPW provee al

usuario de soluciones listas para utilizarse, altamente modularizables, flexibles e

interoperables.

De entrada las tareas que los métodos de correspondencia de imágenes actualmente

han conseguido automatizar, total o parcialmente, podemos encontrar:

\- Orientación interna. La medida de las marcas fiduciales se automatiza a

menudo utilizando métodos de correspondencia basada en intensidades.

\- Orientación relativa. El emparejamiento entre puntos de dos imágenes está

también automatizado. El sistema más común de correspondencia que se emplea

es el de combinar un método basado en entidades con otro basado en

intensidades.

\- Orientación absoluta. Este es un caso similar al de la orientación interna, pero

en vez de buscar las marcas fiduciales, en este caso se buscan los puntos de

control de los que tenemos información.

20

<!-- p. 33 -->

\2. Estado del arte

\- Generación de MDE (Modelos digitales de elevación o Digital Elevation

Model, DEM, en inglés). Tanto los métodos de correspondencia basados en

intensidades como los basados en entidades se utilizan para derivar los MDE.

\- Extracción de elementos relevantes (por ejemplo, la extracción de carreteras).

Es una de los ejemplos de fotointerpretación más comunes en los que juega un

papel muy importante los métodos de correspondencia.

Ya se ha visto en que medida ha influido la automatización de procesos en el

método fotogramétrico con la utilización de técnicas de procesamiento de imagen. A

continuación a modo ilustrativo se incluyen dos ejemplos de este tipo de

automatizaciones que suelen estar implementados en la mayoría de aplicaciones de

fotogrametría digital.

Ejemplo de automatización de la orientación interna.

Aunque las cámaras digitales se están convirtiendo en las protagonistas en las

aplicaciones fotogramétricas de objeto cercano, cuando se habla de fotogrametría aérea

la utilización de sensores digitales de alta resolución no está lo suficientemente

extendida, o bien, se ha de contar con fotografías tomadas con sensores analógicos de

proyectos más antiguos. Es por ello, que muchas de las fotografías aéreas utilizadas para

realizar cartografía vendrán de cámaras de tipo analógico, precisando ser digitalizadas

para poder utilizarlas dentro de los programas de fotogrametría digital. Estos negativos

digitalizados serán por tanto la entrada del flujo de trabajo de una DPW. En este tipo de

configuración, la orientación interna precisa de dos trasformaciones:

\- Una transformación del sistema de coordenadas píxel de la imagen digital (filas

y columnas) al sistema de coordenadas de la imagen analógica, que será definido

por las marcas fiduciales (ver figura 2.2).

\- La definición del modelo de la cámara seleccionando los parámetros de la

calibración de la cámara, para soportar la transformación de fotocoordenadas al

espacio objeto.

La segunda de estas tareas vendrá durante la preparación del proyecto de la

selección de los datos de calibración de que dispondremos, generalmente información

21

<!-- p. 34 -->

\2. Estado del arte

relativa a los parámetros geométricos de la cámara, marcas fiduciales, etc. Esta

información será posteriormente de utilidad, por ejemplo en la aerotriangulación.

La aportación de las DPWs o de la Fotogrametría digital en la orientación interna

viene de la primera de las tareas. Ahora este proceso consigue automatizarse.

Básicamente lo que haremos es conocer de forma precisa y automática la posición de las

marcas fiduciales, para así conseguir la transformación de coordenadas píxel a

coordenadas de la imagen analógica. Esta tarea no es más que una tarea típica de

reconocimiento de patrones (en este caso las marcas fiduciales, ver figura 2.2) para la

que se utilizará alguno de los métodos de correspondencia que implemente la

aplicación.

Figura 2.2: Ejemplo de marcas fiduciales.

El esquema típico de esta fase en un DPW es el que se puede ver en la figura 2.3.

22

<!-- p. 35 -->

\2. Estado del arte

Figura 2.3: Esquema de la fase de orientación interna de un DPW

La forma más común de implementar el emparejamiento (matching) de las marcas

fiduciales con el patrón de búsqueda es utilizando métodos de correspondencia basados

en intensidades, siendo los más comunes la correlación cruzada y la correlación por

mínimos cuadrados. Aunque no es la única alternativa, también es posible utilizar

métodos basados en entidades, haciendo uso de métodos como Canny (Canny 1986),

Hough (Hough 1962) o SIFT (Lowe 2004) que permiten por ejemplo descomponer la

marca fiducial en sus primitivas estructurales para así identificarla más fácilmente en la

imagen (Remondino 2006).

Ejemplo de automatización de la orientación relativa.

La orientación interna permite, como se ha visto, la transformación de coordenadas

píxel a coordenadas de la fotografía. Junto con los datos de calibración de la cámara se

puede reconstruir la geometría para una sola imagen (aunque posteriormente la

reconstrucción se realizará para las dos imágenes). El siguiente paso en el método

fotogramétrico es la orientación relativa. Su objetivo es el de determinar la posición

relativa de las dos imágenes solapadas con respecto a la otra, consiguiendo así la

intersección de los rayos homólogos de ambas imágenes y formando por tanto el

23

<!-- p. 36 -->

\2. Estado del arte

modelo estéreo del área representada. Este paso requiere medir un adecuado número de

puntos homólogos en el área de solapamiento del par estéreo.

Un ejemplo de flujo de trabajo típico de una implementación de esta fase sería el

mostrado en la figura 2.4. En primer lugar se buscan zonas de interés (ventanas de

interés) que serán las candidatas a emparejarse con otras de estas zonas de la otra

imagen del par. Los puntos homólogos que se consiguen emparejar serán los que se

utilicen para calcular la orientación relativa.

Figura 2.4: Esquema de la fase de orientación externa en un DPW.

Una de las formas más comunes de implementación consiste en aplicar un operador

para obtener puntos de interés (Operadores de Foerstner, Moravec o Harris) (Foerstner

1986, Moravec 1981, Harris y Stephens 1988) que delimita las ventanas de interés, para

después aplicar alguna técnica de correlación que permita hacer un emparejamiento más

preciso sobre estas zonas. La combinación de técnicas de emparejamientos basadas en

entidades con las basadas en intensidades permite obtener tiempos de cómputo

razonables, ya que el uso exclusivo de técnicas basadas en intensidades sería demasiado

costoso computacionalmente.

24

<!-- p. 37 -->

\2. Estado del arte

Una vez se tiene reconstruida la relación entre las dos imágenes se remuestrean las

imágenes teniendo en cuenta que ya se conoce la relación que existió entre las mismas

en el momento en que se hicieron las fotografías. Cuando se habla de remuestreo, de lo

que se trata es de realizar una rectificación de las imágenes para así eliminar las

distorsiones geométricas que poseen.

2.2. Visión por computador: Conceptos generales.

La visión por computador fue una de las primeras aplicaciones de la inteligencia
artificial. En visión por computador, éste utiliza una imagen o imágenes de una escena

para hacer aquellas cosas que un humano podría hacer como reconocer un objeto

concreto o navegar a través de una escena. ¿Por qué la visión por computador no es un

problema resuelto? ¿Por qué un computador no puede observar una imagen aérea y

producir un mapa que representa carreteras y edificios? Un gran número de factores se

combinan para hacer la visión por computador un problema complejo. Una imagen es

una proyección del mundo 3D al plano 2D de la imagen. El tamaño y la forma de los

objetos tridimensionales se pierden en el proceso y efectos como la perspectiva y la

oclusión complican el proceso.

La visión por computador puede dividirse en subáreas:

\- Machine vision: Se refiere a la visión por computador utilizada en aplicaciones

industriales de objeto cercano. En este caso las condiciones ambiéntales como la

iluminación o la posición de la cámara pueden ser controladas y además son

pocos los objetos que se han de reconocer.

\- Image understanding: Se refiere a la construcción de modelos geométricos de

la escena utilizando primitivas para segmentar y reconocer objetos.

\- Visión activa: En este tipo de aplicaciones se hace menos énfasis en un modelo

explícito de la escena ya que se buscan otro tipo de objetivos, como pueden ser

la evasión de obstáculos o el seguimiento de dianas.

A continuación, en sucesivos subapartados se detallan algunos conceptos generales

relativos a la visión por computador necesarios para entender la metodología propuesta

por este trabajo.

25

<!-- p. 38 -->

\2. Estado del arte

Representación de imágenes

Un gran número de algoritmos de visión por computador hacen uso de estructuras

de datos que faciliten el procesado eficiente de imágenes. La estructura más común para

este efecto es la pirámide multi-resolución de imágenes. Ésta consiste en un conjunto de

sucesivas reducciones a partir de la imagen original. Esto permite a los algoritmos

trabajar sólo con la cantidad de información suficiente en cada caso, haciendo más

eficientes algunas de las operaciones de procesado de imágenes.

Representación de objetos

El objetivo más usual de un algoritmo de visión por computador es el

reconocimiento de un objeto en una escena. Por ello es necesario algún tipo de

estructura de datos que permita representar objetos 3D. Se pueden establecer 3 tipos

principales para la representación de objetos:

\- Representación a través de superficies.

\- Representaciones volumétricas.

\- Representaciones a partir de cilindros generalizados.

En el apartado 2.5 relativo al emparejamiento denso se detallan en mayor medida

estos tipos de representación, así como referencias de algunos trabajos interesantes.

Visión de bajo nivel: extracción de características

Se denomina visión de bajo nivel (en inglés, low-level vision) a la obtención de

características básicas de la imagen que son útiles para derivar a partir de ellas

propiedades de mayor nivel. Existe un gran número de características de este tipo:

contornos, regiones, texturas, puntos de interés, disparidad estéreo, color, … En el

apartado 2.3 relativo al emparejamiento de imágenes se explica la evolución y los

trabajos más interesantes para la obtención de puntos de interés. Tal y como se expone

en el capítulo siguiente, serán las características a partir de las que se obtendrá

información tridimensional de las escenas.

26

<!-- p. 39 -->

\2. Estado del arte

El modelo pinhole.

Cuando se tienen dos vistas de cámara de una misma escena 3D, hay un número

importante de hechos geométricos que dictan relaciones entre estas vistas. El tipo de

relaciones entre las dos imágenes dependerá del modelo de cámara utilizado.

El modelo de cámara más usual en visión por computador es el modelo pinhole

(Hartley y Zisserman 2003). Se considera la proyección central de puntos en el espacio

en un plano. Sea el centro de proyección el origen de un sistemas de coordenadas
euclidiano, y se considera el plano z = f , que se llamará plano imagen o plano focal.
Bajo el modelo de cámara pinhole, un punto X en el espacio con coordenadas X =
(x,y,z)T se proyecta en el punto en el plano imagen donde corta una línea que une el

punto X con el centro de proyección con el plano imagen, tal y como muestra la figura
2.5. De forma rápida podemos deducir que el punto 3D (x,y,z)T quedará como (f x/z, f
y/z, f )T en el plano imagen, expresado en coordenadas homogéneas.

Figura 2.5: Modelo de cámara pinhole.

El centro de proyección óptico también es conocido como centro óptico. La línea

desde el centro al plano de la imagen se la conoce como eje principal o rayo principal

de la cámara, y el punto donde el eje principal se corta con el plano de la imagen se le

conoce como punto principal. La distancia f referida anteriormente es la longitud focal.

La forma algebraica de definir una cámara como función geométrica es la de una
matriz 3x4 que se conoce como la matriz de proyección de la cámara. Dado un punto X
\= (x,y,z,1)T 3D y su correspondiente proyección en 2D x = (x,y,1)T su relación vendrá

de la expresión:

x = PX

27

<!-- p. 40 -->

\2. Estado del arte

La matriz de proyección P se puede descomponer en sus principales miembros:

P = K [ R | t]

donde K representa los parámetros internos de la cámara, R la matriz de rotación y
t el vector de traslación de la cámara.

En la mayoría de los casos cuando se habla de los parámetros internos de la cámara

se refiere principalmente a: la longitud focal y a las coordenadas del punto principal,

aunque pueden existir otros parámetros interesantes como el ratio de escalas en los ejes

X e Y (importantes en aquellas cámaras donde los pixeles no sean cuadrados) y el skew

que se tiene en cuenta en aquellos casos en los que el eje X y el Y no sean

perpendiculares (por ejemplo fotografías que han sufrido deformaciones al ser

escaneadas).

En lo que se lleva visto hasta ahora se considera que se trabaja con un modelo

lineal y que este modelo es suficientemente preciso. En la mayoría de los casos este

modelo será válido, sin embargo habrá que tener en cuenta en algunos tipos de cámaras

otro tipo de deformaciones, como por ejemplo la distorsión radial, que precisará de un

modelo no lineal (Gruen y Huang 2001).

Geometría epipolar.

La geometría epipolar es la geometría proyectiva intrínseca que existe entre dos

vistas. Es independiente de la estructura de la escena, y sólo dependerá de los

parámetros internos de las cámaras y de su posición relativa (Hartey y Zissermann 2003,

Faugeras y Luong 2001).

Dadas dos vistas de una misma escena 3D con sendas cámaras P y P', y sea un
punto 3D X y sus correspondientes puntos imagen x y x', los centros de las cámaras P y
P' el punto X y los puntos imagen x y x' formarán parte del mismo plano, al que

llamaremos plano epipolar. En base a esta relación estableceremos todos los principios

de la geometría epipolar.

28

<!-- p. 41 -->

\2. Estado del arte

Figura 2.6: Geometría epipolar de dos vistas de una escena.

Las principales entidades geométricas implicadas en la geometría epipolar son:

\- El epipolo es el punto de intersección de la línea que une los centros de

las cámaras (en inglés, baseline) con el plano de la imagen. De forma

equivalente, también se puede definir como la aparición en una de las imágenes

del centro de la cámara de la otra imagen.

\- El plano epipolar es el explicado ya anteriormente. Los planos epipolares

forman un haz de planos cuya recta común será la línea que uno los centros de

las cámaras (en inglés, baseline).

\- La línea epipolar es la intersección entre un plano epipolar con el plano

de la imagen. Todas las líneas epipolares intersecan en el epipolo. Un plano

epipolar interseca el plano de imagen de la izquierda y el de la derecha en sus

líneas epipolares, y define una correspondencia entre líneas.

Matriz fundamental

La matriz fundamental F encapsula la geometría intrínseca entre las dos imágenes.
F es una matriz 3x3 de rango 2. Si un punto 3D X es representado como x en la primera
imagen y como x' en la segunda, ambos puntos cumplen la relación x'T F x = 0. Por

tanto la matriz fundamental es la representación algebraica de la geometría epipolar.

Las propiedades principales (Hartley y Zissermann 2003) de la matriz fundamental

son:

\- Transposición: Si F es la matriz fundamental del par de cámaras P y P',
entonces FT es la matriz fundamental del par de cámaras en el orden opuesto, es
decir, P' y P.

29

<!-- p. 42 -->

\2. Estado del arte

\- Líneas epipolares: Para cualquier punto x en la primera imagen, su
correspondiente línea epipolar vendrá de la expresión l' = F x. De igual forma, l
\= FT x' representa la línea epipolar correspondiente a x' en la segunda imagen.

\- Epipolos: Para cualquier punto x (distinto del epipolo e) la línea epipolar
l' = Fx contiene al epipolo e'. Esto es, e' satisface la expresión e'T (Fx) = (e'T
F)x = 0 para todo x.

\- F tiene siete grados de libertad: una matriz homogénea 3x3 tiene 8

grados de libertad (aunque tiene 9 elementos la escala no es significable), sin
embargo F también cumple la restricción det F = 0, lo cual elimina un grado de

libertad.

\- F relaciona puntos con líneas. En el caso del punto x en la primera
imagen, define una línea en la segunda l' = Fx, que es la línea epipolar de x. Si l
y l' son líneas epipolares correspondientes entonces cualquier punto x en l es
relacionado con la misma línea l'. Esto quiere decir que no hay una relación

inversa.

Estratificación del espacio tridimensional

Existen varias formas de representar la estructura geométrica de un espacio

tridimensional (Hartey y Zissermann 2003, Faugeras y Luong 2001). Es importante

conocer las propiedades de los espacios (o estratos) proyectivo, afín, métrico y euclídeo,

así como la relación entre ellos. Lo usual es percibir el entorno como un espacio

tridimensional euclídeo. Sin embargo, hay ocasiones en que no es posible o deseable

fijar una estructura tridimensional euclídea. Un ejemplo podría ocurrir cuando se intenta

determinar dicha estructura desde las medidas y relaciones en una secuencia de

imágenes. En este caso es más conveniente tratar desde el principio con una estructura

tridimensional menos restrictiva, y más sencilla, como el espacio proyectivo.

Posteriormente, se puede pasar a una estructura intermedia como es el espacio afín y,

finalmente, alcanzar una estructura tridimensional métrica y euclídea más representativa

del entorno real.

Aunque se asume que el entorno real tiene propiedades de espacio euclídeo, se

pueden definir otros espacios geométricos que guarden cierta relación con la estructura

de este espacio original euclídeo. Se parte de que en el espacio original hay una esfera.

30

<!-- p. 43 -->

\2. Estado del arte

Si se realiza una transformación que no conserva la distancia entre puntos, se obtendrá

una estructura deformada del espacio original, por ejemplo un elipsoide. Si esta

transformación (que no es posible en el espacio euclídeo) está definida dentro de otro

espacio geométrico, por ejemplo el proyectivo, se dirá que se ha pasado de un espacio

euclídeo a un espacio proyectivo. Ahora bien, esta estructura deformada mantendrá

cierta relación con la estructura original debido a los invariantes asociados a la

transformación, como incidencia, tangencia y colinealidad. El proceso inverso será

bastante más complejo, ya que implicaría determinar una transformación inversa que

completara el resto de invariantes del espacio de partida. Con este proceso se

recuperaría la estructura original.

Este tipo de indeterminación es el que existe cuando la información proviene de

una secuencia de imágenes. Buscando relaciones entre las distintas imágenes (por

ejemplo emparejando puntos entre éstas) se puede fijar una estructura proyectiva que

estará relacionada con la original por medio de una transformación proyectiva

indeterminada.

Dentro de cada espacio o estrato habrá una serie de invariantes (propiedades que no

se perderán en las diferentes transformaciones) y de transformaciones.

Estrato proyectivo

El espacio proyectivo es el menos estructurado ya que contiene las

transformaciones más generales y con menor número de invariantes.

Las transformaciones en el espacio proyectivo se representan por matrices de

dimensión 4x4 en las que no existe ningún tipo de restricción sobre sus elementos.

 t 11 t 12 t 13 t 14 
 
t 21 t 22 t 23 t 24
T =  
t 31 t 32 t 33 t 34 
 
t 41 t 42 t 43 t 44 

Al estar definida hasta un factor de escala arbitrario, la matriz de transformación

proyectiva más general tiene hasta quince grados de libertad. Con estos grados de

31

<!-- p. 44 -->

\2. Estado del arte

libertad se mantienen los invariantes geométricos de colinealidad, incidencia, tangencia

y razón cruzada (en inglés, cross-ratio).

Estrato afín

Desde el punto de vista de la naturaleza de los puntos del espacio, el espacio afín

no incluye soporte ni representación de los puntos del infinito o puntos impropios. Sin

embargo, estos puntos juegan un papel importante en visión por computador aplicada al

modelado tridimensional del espacio. En la transformación proyectiva que realiza una

cámara, se suele dar el caso de que puntos infinitamente alejados del sistema de

referencia se proyectan en la imagen como puntos propios, es decir, puntos que están

acotados en relación con el sistema de referencia del plano imagen. Un ejemplo habitual

son los puntos del infinito de una superficie horizontal plana que se corresponde con el

suelo. En esta situación, dichos puntos se proyectan en la imagen en una línea de puntos

propios que representa el horizonte. Este fenómeno necesita de una “herramienta” capaz

de soportar dichos puntos y las transformaciones de los mismos.

Teniendo en cuenta las consideraciones anteriores, se puede entender el espacio

proyectivo como una extensión del espacio afín, al que se añade representación y

capacidad de transformar los puntos en el infinito. De esta manera, en el espacio y en las

transformaciones proyectivas, tienen cabida todos los fenómenos relacionados con el

carácter proyectivo de la cámara. Esta característica conlleva una clasificación de los

puntos del espacio proyectivo en dos clases: los puntos propios o afines, y los puntos

impropios o del infinito.

Dentro de las transformaciones proyectivas existe un subgrupo que transforma

cualquier punto impropio en otro también impropio. Este tipo de transformaciones se

corresponde con todas las transformaciones afines posibles. Esto hace que se pueda

considerar el espacio afín como el espacio proyectivo con el grupo de transformaciones

proyectivas que mantiene los puntos del infinito en su lugar, es decir, en el infinito.

Estrato métrico y euclídeo

El espacio métrico y sus transformaciones mantienen también los ángulos de la

estructura geométrica, por lo que el ángulo entre líneas o curvas es un invariante

32

<!-- p. 45 -->

\2. Estado del arte

geométrico adicional. También lo son las distancias relativas. El resto de invariantes lo

constituyen todos los que mantienen el espacio afín. De esta forma, podemos decir que

las transformaciones del espacio métrico son el grupo formado por todas las

similaridades. Estas transformaciones se pueden descomponer en rotaciones y

translaciones, más un escalado.

Los espacios métrico y euclídeo están relacionados por un factor de escala. Así, el

espacio euclídeo mantiene también la escala de la estructura o las distancias absolutas.

Pasar del espacio métrico al euclídeo original consistirá, por tanto, en un escalado de

toda su estructura. Cuando la información proviene de una secuencia de imágenes, la

estructura métrica es el espacio más restrictivo que se puede alcanzar. Para relacionarlo

con el entorno euclídeo real es necesario fijar un factor de escala desconocido. Esta

arbitrariedad se puede resolver conociendo las coordenadas euclídeas de un solo punto

de la estructura métrica.

2.3. Emparejamiento de imágenes.

El desarrollo de métodos para el emparejamiento de imágenes, mediante la

utilización de puntos de interés local, comienza con los trabajos de Moravec (Moravec

1981). Éste propone un método para encontrar puntos homólogos en un par estéreo de

imágenes. El detector de Moravec servirá como base para los trabajos de Harris (Harris

y Stephens 1988), que propone un detector con más discriminabilidad bajo pequeñas

variaciones de luminosidad de la imagen y con contornos cercanos. El detector Harris se

ha convertido en uno de los más ampliamente utilizados durante años, para la gran

mayoría de tareas de emparejamiento. Aunque este tipo de métodos se los conoce como

detectores de esquinas, no sólo seleccionan esquinas de la imagen, más bien seleccionan

cualquier punto de la imagen con cambios fuertes de gradiente en varias direcciones

para una escala predeterminada.

Aunque las primeras aplicaciones en las que se usaba el método de Harris tenían

poco desplazamiento entre las dos posiciones de cámara del par estéreo, con el tiempo

su uso se ha ampliado a situaciones con mayores dificultades. Por ejemplo, en el trabajo

de Zhang (Zhang et al. 1995) se muestra la posibilidad de utilizar emparejamiento de

esquinas con Harris para después completarlo con el uso de ventanas de correlación

alrededor de la esquina. De esta forma podemos seguir utilizando Harris incluso cuando

33

<!-- p. 46 -->

\2. Estado del arte

la distancia entre cámaras aumente. Este método se completa con el cálculo de la matriz
fundamental con un método robusto (por ejemplo RANSAC, Fischler y Bolles 1981)

para así eliminar los posibles outliers, es decir, aquellos emparejamientos que no estén

acordes con la solución mayoritaria.

Un importante punto de inflexión en este tipo de métodos viene con el trabajo de

Schmid y Mohr (Schmid y Mohr 1997), donde se propone extender la utilización de

características invariantes usadas en emparejamiento a su uso en problemas de

reconocimiento de imágenes. Ellos también utilizan las esquinas de Harris para

seleccionar los puntos de interés, pero en vez de utilizar una ventana de correlación para

el emparejamiento, utilizan un descriptor invariante a la rotación de la región de la

imagen. Esto permite emparejar características bajo posibles cambios en la orientación

entre las dos imágenes.

El detector de Harris es muy sensible a los cambios de escala, por lo que no nos

provee de una buena base para el emparejamiento de imágenes de diferentes tamaños.

Esta es una de las razones por las que aparecen trabajos como el de Lowe (Lowe 1999 y

2004), en los que se pretende extender las características locales de forma que podamos

recuperarlas a pesar de tener variaciones en la escala. En este trabajo se describe un

nuevo descriptor local que provee características más “distinguibles” y con una

sensibilidad menor a las distorsiones locales de la imagen como las debidas a los

cambios en el punto de vista, y que es invariante ante cambios de escala y orientación.

El hecho de buscar descriptores con un mayor estabilidad en cuanto a cambios de

escala proviene de trabajos como los de Crowley (Crowley y Parker 1984) y

Shokoufandeh (Shokoufandeh et al. 1999), sin embargo, son los trabajos de Lindeberg

(Lindeberg 1993 y 1994) donde se estudia en profundidad este tipo de problemas. En

estos trabajos se establece el problema de selección de escala, que será utilizado por la

gran mayoría de los posteriores métodos. En los últimos años ha sido importante la

aparición de métodos invariantes a transformaciones afines (Baumberg 2000,

Tuytelaars y Van Gool 2000, Mikolajczyk y Schmid 2002, Schaffalitzky y Zisserman
2002, Brown y Lowe 2002). De todos ellos, se ha seleccionado el método SIFT (Lowe

\2004) para la metodología propuesta de reconstrucción, por conjugar todos los

elementos que se precisan de un método de emparejamiento y por ser una referencia en

la bibliografía de visión por computador.

34

<!-- p. 47 -->

\2. Estado del arte

SIFT combina el detector de regiones DoG (Difference of Gaussian) con el

descriptor SIFT para extraer un conjunto de puntos característicos. Cuando se habla de

descriptor en este caso, se refiere a la estructura de datos donde se almacena la

información obtenida por el detector de regiones. Las regiones extraídas con el detector

DoG se almacenan como un vector de 128 posiciones. El descriptor es un histograma

3D de localización y orientación de gradientes. Lo interesante de este descriptor es su

robustez frente a los cambios. De esta forma para cada imagen de un par estéreo se

obtiene un conjunto de puntos muy útiles para el emparejamiento.

Aunque, como se ha dicho, SIFT destaca sobre la gran mayoría de métodos de este

tipo, existen algunos otros que también podrían ser válidos en este cometido:

\- SUSAN (Smallest Univalue Segment Assimilating Nucleus) (Smith y Brady

1997): utiliza para la detección de esquinas una máscara circular sobre el píxel a

evaluar (el núcleo). La idea es medir el área de esta región circular, mediante

una función matemática, y que este valor sea el que determine si un punto es lo

suficientemente característico.

\- RIFT (Lazebnik et al. 2004): es una generalización invariante a la rotación de

SIFT. El descriptor RIFT se construye utilizando áreas normalizadas circulares

divididas en anillos concéntricos de idéntica anchura. Para cada anillo se calcula

un histograma de orientación de gradiente. Para mantener la invarianza a la

rotación, la orientación se mide en cada punto en la dirección que va del centro

hacia fuera.

\- SURF (Speeded Up Robust Feature): es un detector robusto de puntos

característicos. Fue presentado en 2006 (Bay et al. 2006), y se utiliza en visión

por computador en tareas como el reconocimiento de objetos o la reconstrucción

3D. Está parcialmente inspirado en el descriptor SIFT. La versión estándar de

SURF es varias veces más rápida que SIFT y con una respuesta parecida

respecto a las diferentes transformaciones de la imagen. Se basa en la suma de la

respuesta de la 2D Haar wavelet (similar a un análisis de Fourier), alrededor de

los puntos de interés. Además, se utiliza la técnica de integral image para que su

uso sea más eficiente.

Debido a la proliferación de los nuevos métodos de emparejamiento invariables a

la escala, se han publicado varios trabajos de Mikolajczyk (Mikolajczyk y Schmid

35

<!-- p. 48 -->

\2. Estado del arte

2003, Mikolajczyk y Schmid 2005a, Mikolajczyk et al. 2005b) que pretendían indagar

en las posibilidades que ofrece cada uno de estos métodos. La principal conclusión de

estos trabajos es que SIFT es el descriptor que mejor rendimiento da en la mayoría de

los aspectos en los que se le compara, no siendo determinante únicamente en el caso de

sufrir cambios de iluminación muy bruscos. En estos trabajos los descriptores han sido

evaluados con imágenes reales de diferentes tipos de escenas, a las que se ha sometido a

transformaciones geométricas y fotométricas: rotación, cambio de escala, cambio de

punto de vista, cambios en la definición de la imagen, compresión JPEG e iluminación.

Aunque los aspectos por los que se han comparado los descriptores son a priori

suficientes, los autores comentan que quizá sería necesario incluir una mayor variedad

en el tipo de escena utilizado en las imágenes. De esta forma se puede generalizar aún

más los resultados. Aunque consideran que lo incluido en los trabajos puede ser

suficiente para considerar los resultados concluyentes.

Aunque es poco frecuente encontrar en publicaciones relativas a Fotogrametría

trabajos en los que se utilice SIFT, es bastante interesante el publicado por Fabio

Remondino (Remondino 2006). En este trabajo se realiza una comparativa de detectores

y descriptores en su aplicación al campo de la Fotogrametría, entre los que se encuentra

SIFT. Aunque utiliza experimentos bastante sencillos (detección de esquinas con

diferentes transformaciones, precisión en la localización de elementos, análisis de una

orientación relativa), consigue una comparativa en el que los resultados obtenidos son

bastante interesantes para el proyecto que nos ocupa, ya que entre las conclusiones del

artículo destaca la utilidad de SIFT para trabajos fotogramétricos con buenos resultados

en la mayoría de los experimentos.

De estas comparativas se puede concluir por tanto, que estamos ante un método

que ha sido referencia en el mundo de la visión por computador y al que se intenta sacar

el máximo rendimiento (De Matías et al. 2007a, 2007b, 2009a).

2.4. Métodos para el cálculo de modelos densos 3D.

Otro de los objetivos principales de este trabajo es la obtención de modelos densos

tridimensionales a partir de un sistema de visión multivista. En la metodología que se

propone en esta tesis doctoral la consecución de este objetivo es un hecho primordial.

No sólo se necesita obtener un modelo tridimensional de los glaciares rocosos, sino que

36

<!-- p. 49 -->

\2. Estado del arte

además se quiere obtener una densidad importante de puntos que permita generar una

mayor variedad de productos cartográficos y de mejor precisión.

Ya que se necesita un algoritmo que solvente esta fase de la solución final, lo que

se expone en este apartado, es un estudio de las técnicas que resuelven este tipo de

problemas y que son referencia en la literatura actual (sobre todo desde el lado de la

visión por computador), para seleccionar la que mejor convenga al objeto seleccionado

y adaptarla a sus necesidades.

Hay una gran variedad de técnicas que nos permiten obtener reconstrucciones

densas a partir de un conjunto de imágenes. A lo largo de los últimos años se han

desarrollado algoritmos de gran calidad con este propósito. Uno de los trabajos más

completos es el desarrollado por Seitz et al. (Seitz et al. 2006). En él los autores

establecen un conjunto de propiedades sobre las que comparar y categorizar los más

importantes algoritmos existentes. El trabajo hace una revisión de lo que en inglés los

autores llaman “Multi-view stereo reconstruction algorithms”, es decir, algoritmos para

la reconstrucción estéreo y multivista. Existe un trabajo previo de los autores D.

Scharstein y R. Szeliski (Scharstein y Szeliski 2002), que se centra únicamente en el

caso de los algoritmos que utilizan sólo dos imágenes para la reconstrucción (Marr y

Poggio 1976 y 1979, Cox et al. 1996, Scharstein y Szeliski 1998, Bobick y Intille 1999).

En esta tesis doctoral se han descartado estas propuestas para centrarnos en los

algoritmos multivista, es decir, aquellos que utilizan más de dos imágenes, por ser más

apropiados en nuestro ámbito.

El trabajo de Seitz establece seis importantes propiedades:

\- Scene representation, en español representación de la escena.

\- Photoconsistency measure, en español índice de fotoconsistencia

\- Visibility model, en español modelo de visibilidad o modelo de

oclusiones.

\- Shape prior, en español forma prioritaria.

\- Reconstruction algorithm, en español algoritmo de reconstrucción.

\- Initialization requirements, en español requisitos o restricciones de

inicialización.

37

<!-- p. 50 -->

\2. Estado del arte

Se tiene un campo de aplicación específico que marca la búsqueda de la solución

más apropiada, y para ello se van a analizar los algoritmos multivista existentes

siguiendo las propiedades establecidas por Seitz. et al.. Tal y como indica en el citado

trabajo, se han de considerar las seis propiedades ya referidas, aunque no todas ellas

tienen la misma importancia. Normalmente la representación de la escena y el algoritmo

de reconstrucción, son las principales propiedades puesto que a menudo determinan a

las otras cuatro. Por ejemplo, el índice de fotoconsistencia se ve influido por la

representación de la escena y, en mayor medida, por el algoritmo de reconstrucción, tal

y como se observa en el método seleccionado. Además, existen otras dos propiedades

que pierden importancia en nuestro campo de aplicación: el modelo de visibilidad (o de

oclusiones) y la forma prioritaria. El modelo de visibilidad no es muy importante en

nuestra aplicación, ya que los problemas de oclusiones en el modelado 3D de glaciares

rocosos son muy poco frecuentes. Por otro lado, la forma prioritaria es una restricción

difícil de introducir en nuestros modelos objetivo, ya que los glaciares rocosos no se

asemejan a ningún tipo de estructura regular. Por consiguiente, las propiedades con una

mayor influencia en la elección del método a utilizar son el tipo de representación de la

escena, el algoritmo de reconstrucción y en menor medida las restricciones de

inicialización. Se busca una solución lo más simple posible (un tipo de representación

de la escena sencillo y una fácil implementación), con resultados suficientemente

precisos y un conjunto mínimo de restricciones de inicialización.

Respecto al tipo de representación de la escena se encuentran tres posibilidades:

\- Los modelos volumétricos (en inglés Volumetric Methods: Voxels (Seitz

y Dyer 1999, Vogiatzis et al. 2005), Levelsets (Pons et al. 2005),…). Son muy

populares por su simplicidad, uniformidad y capacidad para aproximarse a

cualquier tipo de superficie. En su contra tienen que precisan de un procesado

más complejo que los otros métodos.

\- Los métodos basados en mallas de polígonos (en inglés Polygon Meshes

(Yu et al. 2004)). Representan una superficie como un conjunto de caras planas

conectadas entre sí. Es una representación eficiente en cuanto a su

almacenamiento y renderización. En su contra, al igual que los métodos

volumétricos tiene el hecho de que su procesado sea también muy complejo.

38

<!-- p. 51 -->

\2. Estado del arte

\- Finalmente los métodos basados en mapas de profundidad (en inglés

Depth Maps (Goesele et al. 2006, Gargallo y Sturm 2006)). La representación en

varios mapas de profundidad (normalmente uno por cada imagen de partida),

simplifica la representación de la escena.

De acuerdo al algoritmo de reconstrucción se encuentra 4 tipos:

\- Métodos que minimizan una función de coste sobre un volumen 3D y

luego extraen una superficie a partir de este volumen.

\- Métodos que iterativamente intentan acercarse a una superficie

decrementando o minimizando una función de coste (Voxel, Levelset, Space

carving (Bonfort y Sturm 2003, Furukawa y Ponce 2006)).

\- Métodos que calculan un conjunto de mapas de profundidad. Estos

métodos refuerzan sus restricciones de consistencia entre los mapas de

profundidad (Goesele et al. 2006, Gargallo y Sturm 2006), o bien unen el

conjunto de mapas de profundidad en una escena 3D mediante un post-proceso

(Curless y Levoy 1996).

\- El último tipo serían algoritmos que primero extraen y emparejan una

serie de puntos característicos y después los encajan en una superficie común

(Taylor 2003).

Los dos primeros tipos de algoritmos necesitan implementaciones bastante

complejas y un gran coste computacional. El cuarto tipo podría producir

reconstrucciones incompletas si no tenemos suficientes puntos característicos. El tercer

tipo de algoritmos no requiere implementaciones tan complejas, y además obtiene

precisiones más que aceptables.

Teniendo en cuenta estas dos propiedades (representación de la escena y el

algoritmo de reconstrucción) de la taxonomía propuesta por Seitz (Seitz et al. 2006), se

ha considerado una buena opción el método propuesto por Goesele et al. (Goesele et al.

2006). Estos autores proponen una solución de reconstrucción densa adecuada en el

campo de los glaciares rocosos. Es una solución adecuada, puesto que los mapas de

profundidad son un tipo de representación de la escena más sencillo que los otros

propuestos, y además el algoritmo de reconstrucción obtiene una buena precisión

utilizando una implementación no demasiado compleja. Goesele propone un simple,

pero a la vez robusto, algoritmo estéro multivista para calcular mapas de profundidad,

39

<!-- p. 52 -->

\2. Estado del arte

utilizando una aproximación basada en ventanas de correlación con buenos resultados

en reconstrucciones densas.

Las ventajas de esta aproximación son:

\- El resultado del algoritmo son reconstrucciones precisas, de acuerdo con los

mejores métodos actuales.

\- Se calcula un valor de confianza para cada punto reconstruido. Este valor será

necesario, por ejemplo, para unir los diferentes mapas de profundidad en un

modelo mallado común.

\- La puesta en marcha es fácil de entender, analizar y predecir, además de ser un

algoritmo muy sencillo.

Además de estas ventajas se encuentran algunos inconvenientes:

\- Pueden aparecer agujeros en el modelo final en las áreas donde la textura sea

insuficiente.

\- Cada punto de la superficie debe ser visto en al menos tres vistas (o imágenes)

para ser reconstruido.

Por tanto, la solución elegida tiene inconvenientes poco importantes para su

aplicación en el caso de los glaciares rocosos, y por otro lado posee interesantes

ventajas (De Matías et al. 2009b, De Matías et al. 2010a). En el siguiente capítulo se

detalla en mayor medida esta solución y su adaptación a los objetivos de esta tesis.

2.5. Medición y monitorización de la dinámica glaciar.

Las posibilidades del uso de la fotogrametría en el estudio de los glaciares ya se

consideraron a finales del siglo XIX, sólo unas pocas décadas después de la invención

de la fotografía. Aunque la relación entre glaciares y fotogrametría ha continuado a

través de los años, en la última década existe un creciente interés por el estudio del

fenómeno de los glaciares. Tanto los glaciares de hielo como los glaciares rocosos se

han convertido en el objeto de muchos estudios geomorfológicos. Estos fenómenos se

tienen por una interesante referencia del llamado “cambio climático”.

Puesto que el interés por los glaciares ha ido creciendo, también ha crecido en igual

medida el número de técnicas y metodologías aplicadas en la monitorización de éstos.

40

<!-- p. 53 -->

\2. Estado del arte

El aspecto más relevante que permite discriminar entre las diferentes técnicas

utilizadas es la forma de capturar las imágenes. Este aspecto ha sufrido una importante
evolución. En el siglo XIX aparece el concepto de fotogrametría terrestre, es decir, un

método para la medición o la producción de cartografía a partir de fotografías tomadas

desde el nivel del suelo. La fotogrametría terrestre es en ese momento la única solución

posible en la toma y procesado de las imágenes (Finsterwalder 1896, Weiss 1913). Es la

técnica más sencilla y barata, aunque tenga algunos inconvenientes, como es la

necesidad de un acceso directo (o a poca distancia) del terreno que se quiere medir, lo

cual, no siempre es fácil cuando se trata de medir glaciares, normalmente situados en

zonas de alta montaña y muy difícil acceso. A principios del siglo XX se comienza a
utilizar la fotogrametría aérea. Ésta permite recuperar la información geométrica de

áreas a partir de las fotografías tomadas por un sensor montado en un medio aéreo:

aviones, helicópteros, globos aerostáticos, etc. Este tipo de fotogrametría permite

obtener información cuantitativa, espacialmente distribuida de amplias áreas sin la

necesidad de un acceso directo al terreno, aunque con un mayor coste que la terrestre.

Esto permitió una temprana aplicación a la investigación glaciológica (Pillewizer 1938).
Desde finales del siglo XX y comienzos del XXI, la fotogrametría a través de
imágenes de satélite ha tomado una mayor importancia en su uso fotogramétrico o de

producción de cartografía. La mejora en la resolución de las fotografías de satélite hace

de ésta una posible (aunque más cara) opción para la toma de imágenes en estudios

glaciológicos (Paul y Kääb 2005).

Aunque se puede inferir, a través de esta evolución, que la fotogrametría terrestre

ha quedado relegada a un segundo plano dentro de la glaciología, esta conclusión es

incompleta. Se ha de pensar que la fotogrametría aérea y la de satélite no han sustituido

a la fotogrametría terrestre. Antes de comenzar un nuevo proyecto fotogramétrico hay

que valorar que tipo de solución se adecua más a la solución cartográfica que se precisa.

Es cierto que el uso de la fotogrametría terrestre ha estado muy limitado durante varias

décadas, puesto que la fotogrametría aérea en primer lugar y el uso de imágenes

satélites posteriormente han ofrecido nuevas posibilidades que las soluciones terrestres

no satisfacían. Sin embargo, aún se encuentran un número de aplicaciones en las cuales

la fotogrametría terrestre sigue siendo la elección más adecuada (Theakstone 1997).

Hay que tener en cuenta diversos factores para tomar una decisión. Entre éstos se

encuentra los siguientes:

41

<!-- p. 54 -->

\2. Estado del arte

\- El coste es a menudo el factor que más influye en la decisión de utilizar

fotogrametría terrestre. El coste de un vuelo fotogramétrico, o de la adquisición

de imágenes de satélite, a menudo supera el presupuesto de buena parte de los

proyectos de monitorización de glaciares. Esto exige buscar soluciones más

sencillas y por tanto más baratas como son las terrestres.

\- Posibilidad de acceder a la zona. A veces no es posible acceder a algunas

zonas a cartografiar (por ejemplo, por la cercanía de un volcán, (Sanjosé

2006b)). En estas ocasiones sólo es posible utilizar soluciones de fotogrametría

aérea o de imágenes de satélite.

\- Posibilidad de hacer un vuelo fotogramétrico en la zona. En algunas

ocasiones la fotogrametría aérea puede no ser la solución adecuada. Es muy

común que en zonas de alta montaña de difícil acceso no sea posible hacer

vuelos fotogramétricos con poca altura (por los picos que pueden rodear la zona

a cartografiar). El aumento de la altura del vuelo conlleva una pérdida de

resolución de las imágenes que acarrea una pérdida de precisión.

\- Posibilidad de adquirir imágenes por satélite. No siempre es posible adquirir

imágenes por satélite de la zona que se busca, en la época que se necesita y con

la resolución que se precisa, aún cuando el coste de su adquisición no sea un

problema.

\- La precisión que es posible obtener. Este factor depende de otros, como es el

tipo de sensor utilizado o la distancia del sensor al terreno a cartografiar, además

de la metodología de trabajo que se utilice.

\- Superficie de la zona a cartografiar. También es interesante adecuar la

solución elegida a la cantidad de superficie de terreno que queremos

cartografiar. Normalmente la fotogrametría aérea y la de imágenes por satélite

suelen ser más adecuadas para superficies mayores de terreno que la

fotogrametría terrestre.

Un ejemplo donde la solución adecuada es la fotogrametría terrestre es el del
glaciar rocoso del Veleta en Sierra Nevada (incluido en el capítulo 4 de

experimentos) (Gómez et al. 2001). Es adecuado elegir una solución de fotogrametría

terrestre por varias razones: la zona a cartografiar está rodeada de picos altos que

dificultan la toma de fotografías aéreas, es una zona relativamente pequeña

42

<!-- p. 55 -->

\2. Estado del arte

(aproximadamente 2 Ha), es posible acceder a la zona (aunque el acceso no sea sencillo)

y además el coste de una solución que no sea la terrestre es sensiblemente mayor. Por
todas estas razones, la fotogrametría terrestre es la solución apropiada. No se ha de

olvidar que una solución de este tipo conlleva el inconveniente de tener que acceder

cada año a la zona para la toma de imágenes y la medición de puntos de control (De

Matías 2009a, Sanjosé y Lerma 2004, Sanjosé et al. 2006a).

Por tanto, la metodología que propone la fotogrametría terrestre parte de la toma de

una serie de fotografías, ya sea en tomas sencillas o con el uso de imágenes

panorámicas. La superficie del glaciar se ha de interpretar utilizando estas tomas y el
concepto de estereoscopía. A partir de esta idea se define y se mide un Modelo Digital
de Elevación.

La forma de almacenamiento de las imágenes también, evidentemente, ha sufrido

una notoria evolución. Hoy día, en la fotogrametría terrestre, lo más habitual es el uso

de cámaras equipadas con sensores digitales, sin embargo se siguen incorporando a

algunos de los proyectos actuales imágenes antiguas de cámaras analógicas para su

procesado con los flujos de trabajo actuales.

Hay algunos ejemplos de este tipo. Este es el caso del trabajo propuesto por

Haggrén et al. (Haggrén et al. 2007). Estos autores tratan de volver a medir glaciares

utilizando antiguas fotografías, mediciones en campo y técnicas actuales de procesado

de imagen digital. Para ello utilizan imágenes de Hochjochferner, Austria, de 1907. En

concreto escanearon 89 placas de cristal para ser analizadas. Además, remidieron una

serie de puntos en campo para conseguir modelos estereoscópicos debidamente

orientados. Se consiguió un modelo con una precisión del orden de 2 metros.

Del mismo modo Kaufmann y Ladstädter (Kaufmann y Ladstädter 2004a), han

cuantificado el retroceso del glaciar Goessnitzkees en Austria utilizando fotografías

terrestres (es decir, tomadas a pie de campo, sin ningún medio aéreo) de los años 1988,

1997 y 2003. Las fotografías (por ser de diferentes épocas) fueron tomadas utilizando

dispositivos de captura de imagen muy diversos. Para las tomadas en 1988 se utilizó un

Fototeodolito Zeiss TAL, para las tomadas en 1997 se probó la utilidad del uso de una

cámara digital Nikon D100 y por último para las que se tomaron en 2003 se aplicó la

cámara semi-métrica Rolleiflex 6006. Además, se tomaron mediante instrumental

topográfico unos 7 puntos de control (útiles en la orientación de las fotografías). La

43

<!-- p. 56 -->

\2. Estado del arte

distancia entre la cámara y el frente del glaciar fue de varios cientos de metros y se

obtuvo un Modelo Digital de Elevación (DEM) utilizando una restituidor

fotogramétrico digital. El DEM fue obtenido manualmente con una muestreo de

aproximadamente 5 metros. Un intento similar de utilización de la fotogrametría

terrestre para la monitorización de glaciares, fue el propuesto por Kaufmann et al.

(Kaufmann et al. 2006) en el glaciar Doesen, Austria. Se utilizaron fotografías de 1997

utilizando la cámara Rolleiflex y la Nikon D100, sin embargo no se pudo llevar a cabo

el trabajo, puesto que los autores no consideraron aceptables las precisiones obtenidas.

Otro trabajo interesante es el propuesto por Gruber y Slupetzky (Gruber y

Slupetzky 2002). Ellos querían comparar los cambios en la topografía del glaciar

Cathedral Massif en Alaska, a partir de los datos de 1976, 1985 y 1999. De los años

1976 y 1985 se contaba con mapas (en papel) sin ninguna información digital, y del año

1999 se contaba con 78 fotografías terrestres tomadas desde 13 puntos de vista

diferentes. Las fotografías fueron tomadas con una cámara calibrada de medio formato

(Mamiya RB 67). Además se tomaron varias fotografías desde un helicóptero y se tomó

una serie de puntos mediante GPS. Se obtuvieron más de 3000 puntos 3D, los antiguos

mapas fueron escaneados y manualmente digitalizados, y se produjo un DEM para

comparar con el DEM obtenido a partir de las fotografías terrestres. Gruber y Slupetzky

(Gruber y Slupetzky 2002) concluyeron que aunque es posible, pueden surgir

dificultades al digitalizar materiales analógicos (como es el caso de los mapas en papel),

así como combinar materiales de diferentes fuentes.

Otro interesante reto fue el propuesto en el glaciar Triglav, Eslovenia (Triglav et al.

2000, Triglav-Cekada 2006). Este pequeño glaciar ha sido fotografiado en numerosas

ocasiones desde 1976, por lo que hay una gran cantidad de material fotográfico sobre él.

No obstante, las fotografías fueron tomadas con una cámara compleja, en concreto una

cámara panorámica Horizon, y además, sin el consiguiente trabajo de campo. En 1999,

se comienza a utilizar la cámara métrica Rolleiflex 6006 y se miden puntos de control

comunes a todas las fotografías, lo que permite enlazar las fotografías de ambas

cámaras. La cámara Horizon se calibró y se llevó a cabo el trabajo de levantamiento con

GPS necesario. Aún así la obtención de un DEM lo suficientemente preciso fue muy

complicada. Por ello después de la campaña de 1999, las fotografías son tomadas desde

un helicóptero y por tanto los cambios del glaciar se han ido midiendo mediante

fotogrametría aérea.

44

<!-- p. 57 -->

\2. Estado del arte

Con el objetivo de unificar criterios y aunar esfuerzos en el desarrollo de nuevas

técnicas para la monitorización de glaciares surgió en Abril de 2001 el proyecto
OMEGA (Development of Operational Monitoring System for European Glacial Areas

– sintesis of Earth observation data of the present, past and future). Es un proyecto

propuesto por la Comisión Europea entre los años 2001 y 2004, coordinado por el

profesor P. Pellikka de la Universidad de Helsinki. En el proyecto se han implicado

diferentes instituciones del ámbito europeo como las Universidades de Helsinki y Turku

en Finlandia, la Universidad de Innsbruck y el Instituto de Investigación Joanneum para

el Procesamiento de Imágenes Digitales en Austria, o el Directorio para la energía y los

recursos de agua del gobierno noruego, entre otros. Los objetivos que se trataron de

alcanzar fueron:

\- Evaluar y utilizar el potencial que supone la fotogrametría aérea y de fotografías

satélite para la monitorización de glaciares.

\- Diseñar un sistema de monitorización que pueda ser utilizado en los diferentes

tipos de datos para la observación de la tierra (Fotogrametría terrestre, aérea,

satélite, etc).

\- Construir una base de datos glaciológica.

Como último resultado del proyecto se publicó el libro “Remote Sensing of

Glaciers – Techniques por topographic, spatial and thematic mapping of glaciers”

coordinado por los autores Petri Pellikka y W. Gareth Rees (Pellikka y Gareth 2010).

En este libro se recoge un compendio de las diferentes técnicas utilizadas para la

monitorización de glaciares, así como los trabajos más interesantes en cada una de estas

técnicas.

2.6. Monitorización de glaciares en distintos períodos.

El último gran objetivo que se intenta alcanzar en el desarrollo de este trabajo es la

posibilidad de estudiar como evolucionan los glaciares rocosos a través de los años. Se

pretende desarrollar una técnica que nos permita monitorizar los movimientos de las

diferentes áreas o bloques del glaciar. Hoy día existen algunos autores trabajando en

este fin (Kääb et al. 1997, Kaufmann y Ploesch 2000, Kenyi y Kaufmann 2003,

Kaufmann y Landstädter 2002-2004a-2004b, Roer et al. 2005, Kääb y Kneisel 2006,

45

<!-- p. 58 -->

\2. Estado del arte

Kaufmann et al. 2006), con buenos resultados. Son trabajos propuestos desde la

perspectiva de la fotogrametría. En estos trabajos se proponen métodos para producir

ortofotos de diferentes años y compararlas mediante un proceso de emparejamiento de

imágenes. En este trabajo se pretende simplificar los flujos de trabajo ya propuestos en

la literatura actual, mejorar la resolución de los puntos calculados y conseguir una

mayor cantidad de puntos cuando se monitorice un glaciar rocoso.

En primer lugar hay que destacar el método que proponen los autores Kaufmann y

Ladstädter (Kaufmann y Ploesch 2000, Kaufmann y Landstädter 2004a-2004b,

Kaufmann et al. 2006, Kenyi y Kaufmann 2003). Se basa en el concepto de “pseudo-

ortofoto”. Partiendo de un MDT (Modelo digital del terreno) de poca precisión

consiguen obtener pares de “pseudo-ortofotos”. La rectificación de una sola fotografía

aérea produce una ortofoto, que podríamos llamar ortofoto “verdadera”, puesto que el

MDT utilizado para generarla representa de forma correcta la superficie del terreno. Por

otro lado, si contamos con un MDT no tan preciso (como ocurre en el caso de las

“pseudo-ortofotos”), que se aproxima mínimamente a la superficie del terreno, éste se

podría utilizar para la rectificación de un par estéreo. Las imágenes que se obtienen de

este par estéreo se denominarán “pseudo-ortofotos” (o POPs). Estas imágenes contienen

pequeñas desviaciones respecto de la que denominaríamos ortofoto “verdadera”. Estas

desviaciones provienen de las alturas erróneas del MDT que hemos utilizado para

generarlas. Sin embargo, estas imágenes si cuentan con el mismo factor de escala y la

misma orientación. Estas dos propiedades facilitan la utilización de algoritmos de

emparejamientos. A partir del MDT no tan preciso, las pseudo-ortofotos todavía

contienen la misma información estéreo que las fotografía original, lo que permite

obtener una reconstrucción tridimensional del terreno. El método propuesto por los

autores produce un MDT de alta calidad, emparejando puntos entre los pares de estas

pseudo-ortofotos. Una vez obtienen ortofotos verdaderas (utilizando ese MDT de gran
calidad) de varias campañas, utilizan el software de desarrollo propio ADVM

(Automatic Displacement Vector Measurement), para establecer relaciones entre estas

campañas mediante algoritmos de emparejamiento. Este software utiliza algoritmos de

correlación para la búsqueda de puntos homólogos entre las imágenes de diferentes

campañas.

Un trabajo similar es el que propone Kääb y otros autores (Kääb et al. 1997, Roer

et al. 2005, Kääb y Kneisel 2006). Ellos sugieren una idea más sencilla. A partir de

46

<!-- p. 59 -->

\2. Estado del arte

fotografías aéreas y un software comercial de fotogrametría producen un MDT y
ortofotos verdaderas del glaciar rocoso en varios años. Utilizando el software CIAS

(Correlation Image Analysis), calculan desplazamientos horizontales de puntos del

glaciar rocosos. El software CIAS es una solución similar a la que proponen Kaufmann

y Ladstädter.

Los trabajos de Kaufmann y Kääb tienen el mismo objetivo: Calcular

desplazamiento de puntos a través de varias campañas. En esta tesis doctoral se pretende

mantener el mismo objetivo, pero simplificando el flujo de trabajo (por ejemplo, que no

sea preciso producir ortofotos), e incluso utilizando imágenes tomadas con diferentes

cámaras, objetivos y resoluciones.

47

<!-- p. 60 -->

\2. Estado del arte

48

<!-- p. 61 -->

Capítulo 3: Metodología.

<!-- p. 62 -->

\3. Metodología

50

<!-- p. 63 -->

\3. Metodología

\3. Metodología.

Una vez presentados los métodos y algoritmos que la fotogrametría y la visión por

computador aportan, y una vez conocidas las técnicas que se utilizan en estudios

geomorfológicos, es el momento de proponer una metodología capaz de resolver los

objetivos del proyecto. En esta tesis doctoral se propone una metodología que permite el

modelado y medición de estructuras geomorfológicas dinámicas, concretamente los

glaciares rocosos. La precisión a obtener en las mediciones mediante esta metodología

debe ser suficiente para su uso en estudios geomorfológicos.

La metodología propuesta comprende una serie de técnicas, herramientas y

métodos. La integración de todos ellos da como resultado un software completo para

resolver el problema. Además, en este capítulo se explica qué tipo de cartografía es

posible producir siguiendo esta metodología. Tal y como se trata en la introducción, la

cartografía usual de anteriores propuestas resulta a veces incompleta, y por tanto hace

falta un esfuerzo importante para obtener una serie de productos cartográficos

innovadores y más complejos (dense flow vectors). La producción de cartografía más

compleja y con mayor cantidad de información puede ayudar a mejorar las técnicas de

control y seguimiento de glaciares rocosos utilizadas actualmente en geomorfología.

51

<!-- p. 64 -->

\3. Metodología

Figura 3.1: Esquema general de la metodología.

3.1. Bloque I: Modelado de las cámaras.

Como en toda metodología es primordial resolver dos aspectos importantes de las

imágenes con las que se cuentan. En primer lugar determinar cómo la óptica o la

electrónica de la cámara o cámaras deforman las imágenes en el proceso de la toma

fotográfica, y en segundo lugar obtener qué posiciones y orientaciones ocupaban esas

cámaras cuando fueron tomadas las imágenes. Estas dos tareas son las que se han de

resolver en este primer bloque de la metodología.

3.1.1. Fase 1: Calibración interna.

Como se ha indicado al inicio de este apartado 3.1, la calibración interna de una

cámara consiste en averiguar como ésta deforma las imágenes en el proceso de la toma

52

<!-- p. 65 -->

\3. Metodología

fotográfica, es decir, los cambios que sufren cada uno de los puntos tridimensionales

que fotografiamos hasta su proyección en la película o sensor de la cámara. Las cámaras

que se utilizan no poseen un sistema de lentes perfecto. Todas las lentes (incluso las de

alta calidad) sufren diferentes tipos de aberraciones. Se deben tomar las precauciones

necesarias para eliminarlas o al menos determinar su magnitud. La calibración interna

es el término utilizado para describir los parámetros que modelan el paso de los rayos a

través de la lente y su proyección sobre el plano imagen.

Figura 3.2: Mecanismo de proyección en una cámara fotográfica.

Antes de utilizar cualquier cámara en un proyecto fotogramétrico, estos parámetros

se deben conocer y compensar adecuadamente durante el proceso de calibrado. Existen

diferentes aproximaciones en la literatura que resuelven esta fase de la metodología, sin

embargo no forma parte de los objetivos de este trabajo la comparación o posible

mejora de las características de los diferentes métodos de calibración. Por ello se

considera la solución propuesta en (Pérez 2009), donde se realiza un estudio

comparativo de las técnicas actuales, tanto en el ámbito de la visión por computador

como en el de la fotogrametría, apostando por una solución más próxima a esta última.

El modelo matemático utilizado es el siguiente:

r
x − x0 + ∆xr + ∆xt = − c
q

s
y − y 0 + ∆y r + ∆yt = − c
q

r = m11 ( x − x0 ) + m12 ( y − y 0 ) + m13 ( z − z 0 )

s = m21 ( x − x0 ) + m22 ( y − y0 ) + m23 ( z − z 0 )

53

<!-- p. 66 -->

\3. Metodología

q = m31 ( x − x0 ) + m32 ( y − y 0 ) + m33 ( z − z 0 )

donde:

\- (x0, y0) es la posición del punto principal.

\- c es la distancia focal.

\- (∆xr, ∆yr) es la variación de x e y introducida por la distorsión radial. El modelo

de distorsión radial que se sigue es el método gaussiano:

∆r
∆xr = ( x − x0 )
r

∆r
∆yr = ( y − y0 )
r

r = ( x − x0 ) 2 + ( y − y 0 ) 2

∆r 2 4 6
\= k1r + k 2 r + k 3 r + ...
r

\- (∆xt, ∆yt) es la variación de x e y introducida por la distorsión tangencial:

c ][ ] ) ∆xt = 1( − [ p1 ( r 2 + 2 ( x − x0 ) 2 ) + 2 p 2 ( x − x0 )( y − y 0 ) 1 + p3 r 2 + p 4 r 4 + ...
s

c ][ ] ) ∆yt = 1( − [ p 2 ( r 2 + 2 ( y − y0 ) 2 ) + 2 p1 ( x − x0 )( y − y0 ) 1 + p3 r 2 + p 4 r 4 + ...
s

3.1.2. Fase 2: SIFT como emparejador de puntos.

En el apartado relativo a emparejamiento de imágenes del capítulo anterior, ya se

trató acerca de la potencialidad del uso de SIFT para la búsqueda de puntos homólogos

en pares estéreo de imágenes. Tal y como se explicó, su rendimiento es bueno, incluso

con condiciones poco favorables. Permite trabajar con importantes cambios en las

imágenes de los pares, como rotaciones, cambios de escala e incluso cambios de

iluminación de la escena. Estos cambios son muy comunes en algunas de las imágenes

utilizadas en esta tesis.

El primer paso a seguir en esta fase de la metodología, es utilizar SIFT para la

extracción de puntos característicos de cada una de las imágenes objetos del estudio.

54

<!-- p. 67 -->

\3. Metodología

SIFT combina el detector de regiones DoG (Difference of Gaussian) con el

descriptor SIFT para extraer un conjunto de puntos característicos. Cuando se habla de

descriptor, en este caso, se refiere a la estructura de datos donde se almacena la

información obtenida por el detector de regiones. Las regiones extraídas con el detector

DoG se almacenan como un vector de 128 posiciones. Este vector se divide por la raíz

cuadrada de la suma de cada uno de los componentes del vector al cuadrado. De esta

forma se consigue que sea invariante (o casi invariante) a los cambios de iluminación.

El descriptor es un histograma de localización y orientación de gradientes. Lo

interesante de este descriptor es su robustez frente a los cambios (orientación, escala,

iluminación…). De esta forma, para cada imagen de un par estéreo se obtiene un

conjunto de puntos muy útiles para el emparejamiento.

Por tanto, para cada una de las imágenes de que se dispone, se obtiene una lista de

descriptores SIFT así como la localización de esos puntos en las imágenes. De una

primera imagen se tendrá una lista de descriptores y de una segunda otra lista de ellos.

El mejor candidato para un emparejamiento será el punto vecino más cercano, es decir,

el punto con menor distancia de su descriptor respecto del descriptor del vecino. Sin

embargo, muchos de los puntos no tendrán un equivalente con el que emparejarlos. Por

tanto, es necesaria una forma de eliminar los puntos sin un buen emparejamiento en la

base de datos.

Experimentalmente se ha constatado que la solución más exitosa consiste en

establecer un umbral para la distancia al descriptor más cercano, e incluso, mejor aún,

comparar la distancia entre el más cercano y el segundo más cercano. Utilizando este

método se elimina un porcentaje bastante alto de emparejamientos erróneos. Por

ejemplo, en el trabajo donde se expone el método SIFT, se consigue eliminar un 90% de

emparejamientos erróneos y se pierden sólo un 5% de los correctos (Lowe 2004).

Variando el umbral se puede obtener o una mayor cantidad de emparejamientos, si

establecemos un umbral más amplio, o una mayor calidad en éstos aunque con una

cantidad menor, si establecemos un umbral más restrictivo.

55

<!-- p. 68 -->

\3. Metodología

Figura 3.3: Ejemplo emparejamiento SIFT.

3.1.3. Fase 3: Geometría epipolar.

En esta fase se propone utilizar la restricción epipolar para eliminar aquellos

emparejamientos que sean erróneos, y de esta forma robustecer el conjunto de ellos.

Para obtener la matriz fundamental de un par de imágenes, se debe partir de un

conjunto de correspondencias muy fiables. De cada correspondencia se obtendrá una

ecuación según la restricción epipolar. La matriz fundamental es una matriz 3 x 3 y por

tanto puede ser calculada resolviendo un sistema lineal de ecuaciones con un mínimo de

8 emparejamientos (Hartley 1997). Sin embargo, esta solución lineal puede no ser

acertada si en este conjunto de correspondencias hay alguna de ellas que no sea

correcta. Es por esta razón por la que se utilizan otro tipo de algoritmos (Luong et al.

1993, Rousseeuw y Leroy 1987) para el cálculo de la matriz fundamental. Uno de estos

métodos es el método RANSAC (Random sampling consensus) (Fischler y Bolles

1981), mucho más robusto con la presencia de estos emparejamientos erróneos,

conocidos como outliers. El resultado de este algoritmo es el cálculo de la matriz

fundamental, así como la selección de un conjunto de outliers, es decir, de

emparejamientos que se han descartado por no ser fiables para el ajuste realizado. Este

conjunto de outliers es muy útil para descartar algunos de los emparejamientos

obtenidos del conjunto de partida. Existen otras propuestas como LO-RANSAC (Chum

et al. 2003), PROSAC (Chum y Matas 2005) o BEEM (Goshen y Shimshoni 2006) con

mejores tiempos de computación, pero con resultados similares a RANSAC.

56

<!-- p. 69 -->

\3. Metodología

3.1.4. Fase 4: Orientación externa.

En esta cuarta fase se ha de establecer un método para obtener los parámetros

extrínsecos de las cámaras. Éstos vienen dados por:

\- La posición de la cámara: valores de X, Y, Z, que nos sitúan el centro de la

cámara en el sistema de coordenadas elegido.

\- La orientación de la cámara: valores de los tres ángulos (o de la matriz de

rotación) que definen la orientación de la cámara.

En los casos que se proponen en esta tesis (capítulo de experimentos) se utiliza una

serie de puntos de la escena de los que conocemos sus coordenadas 3D con precisión.

Normalmente junto a la toma de fotografías se sigue un proceso de medición de esos

puntos mediante técnicas topográficas (Estación total o GPS) que proporcionan un error

muy bajo (en torno a 1-2 cm).

Para la solución del problema se utiliza el método conocido como ajuste de rayos

(en inglés, bundle adjustment). Es un método muy conocido tanto en el mundo de la

visión por computador como en el de la fotogrametría (Triggs et al. 2000, Pollefeys et

al. 2004). Dado un conjunto de imágenes donde se observan puntos 3D a partir de

diferentes puntos de vista, el ajuste de rayos (bundle adjustment) puede definirse como

el problema de refinar simultáneamente la relación entre las coordenadas 3D que

describen la geometría de la escena, así como los parámetros del movimiento relativo y

de las características de la cámara (o cámaras) empleadas en la adquisición de imágenes,

de acuerdo con un criterio de optimización que implique las proyecciones de cada uno

de los puntos en las imágenes.

El ajuste de rayos puede ser utilizado como un último paso de un algoritmo de

reconstrucción 3D. Sin embargo, en este caso, es un paso previo para el cálculo de la

orientación relativa de las cámaras. Se trata de un problema de optimización en la que

participa la estructura 3D de la escena (puntos 3D conocidos) y los parámetros de

posición de la cámara. En algunas ocasiones se pueden optimizar también los datos de

calibración intrínseca de las cámaras y la información de distorsión radial de las

imágenes. No ocurre en este caso, puesto que consideramos que los datos de la

calibración intrínseca de la cámara poseen la suficiente calidad como para no tener que

ser refinados. Se trata de obtener una reconstrucción que sea óptima bajo ciertos

supuestos relativos al ruido de las características observadas en las imágenes. Si el error

57

<!-- p. 70 -->

\3. Metodología

e la imagen es gaussiano de media cero, el ajuste de rayos es el estimador de

máxima probabilidad (en inglés, Maximum Likelihood Estimator).

El ajuste de rayos minimiza el error de reproyección entre las coordenadas de

imagen de los puntos observados y los puntos predichos, que se expresa mediante la

suma de cuadrados de la distancia entre esos dos puntos. Lo que se asume es que n

puntos 3D son observados desde m vistas, xij representa la proyección del punto i en la

imagen j, vij denota una variable binaria que vale 1 si el punto i es visible en la imagen j

y 0 en caso contrario, y se representa cada cámara con el vector aj y cada punto 3D con

el vector bi. El ajuste de rayos minimiza el error de reproyección total con respecto a

todos los puntos 3D y todos los parámetros de las cámaras, esto es:

n m ( ( ) ) vij d Q a j , bi , xij min∑∑i =1 j =1 2

donde Q (aj, bi) es la proyección predicha del punto i en la imagen j y d representa la

distancia euclídea entre dos puntos. Por tanto, la minimización se alcanza utilizando

algoritmos de mínimos cuadrados no lineales. De todos ellos, el de Levenberg-

Marquardt (Levenberg 1944), ha demostrado ser uno de los más exitosos como técnica

estándar para los problemas de mínimos cuadrados no lineales. La implementación es

de propósito general, y su uso sigue una estrategia de amortiguamiento que permite la

habilidad de converger rápidamente desde un amplio rango de soluciones iniciales. En

cada iteración y tras la linearización de la función se busca la minimización entre los

vecinos de la estimación actual. El algoritmo Levenberg-Marquardt es una combinación

de dos métodos de aproximación, por un lado el algoritmo de descenso de gradiente y

por el otro el método Gauss-Newton. Cuando la estimación en ese momento está lejos

de la correcta, el algoritmo se comporta como el método de descenso de gradiente, es

decir, lento, pero garantizando que se converja a una solución. Mientras que si la

estimación en curso está cerca de la solución correcta, el algoritmo se comporta

siguiendo el método Gauss-Newton, que es más rápido en alcanzar una solución.

El principal defecto del algoritmo Levenberg-Marquardt proviene de su

concepción como algoritmo de propósito general, ya que esto implica un mayor coste

computacional, por ejemplo para el caso del ajuste de rayos. Afortunadamente, la falta

de interacción entre los puntos 3D y algunos parámetros de las cámaras da como

resultado en algunas de las matrices implicadas la aparición de grandes bloques de

ceros. Esto se puede explotar para mejorar los costes computacionales del algoritmo,

58

<!-- p. 71 -->

\3. Metodología

eliminando espacio de almacenamiento y reduciendo el tiempo de computación

necesario para su ejecución. Con este objetivo los autores Lourakis y Argyros proponen

la solución SBA (Sparse bundle adjustment) (Lourakis y Argyros 2004 y 2009).

Como se verá en el capítulo dedicado a los experimentos, los errores que se

obtienen al aplicar un ajuste de rayos para la obtención de los parámetros extrínsecos de

la cámara son del orden de tan sólo un píxel (aunque pueden llegar a alcanzarse en

algunas ocasiones valores menores de un píxel), lo que hace de esta técnica una de las

más adecuadas para esta tarea.

3.2. Bloque II: Obtención de una superficie previa.

Al finalizar el bloque I de la metodología propuesta se conoce toda la información

de las cámaras (calibración interna y orientación externa). En este bloque II se calcula

una primera solución discreta de la estructura 3D de la escena. Como se ha expuesto, en

esta tesis doctoral se pretende obtener una estructura 3D de la escena con gran densidad

de puntos 3D. Este objetivo ha de lograrse en dos fases. El bloque II representa el

primero de ellos, la obtención de una superficie previa. Aunque el cálculo de esta

superficie no es el objetivo final, se propone un método para obtener una superficie

previa a utilizar como estimación inicial de la superficie 3D final. Mediante el uso del

método SIFT se ha obtenido un primer conjunto de emparejamientos con los que poder

crear la primera superficie 3D de la escena. Ésta aún no tiene la densidad de puntos 3D

que se planteaba como objetivo, pero sirve para hacer una estimación de la profundidad,

muy útil en el último paso que se plantea en el bloque III. Lo que se implementa en este

bloque II es un método de reconstrucción 3D a partir del emparejamiento de

características utilizando los descriptores SIFT.

3.2.1. Fase 5: Triangulación: Obtención de puntos 3D.

En este punto de la metodología se cuenta por una parte con un conjunto de

emparejamientos robustos y de los datos de las cámaras obtenidos anteriormente

(calibración interna y orientación externa). Por tanto, conocida la información de las

cámaras es el momento de obtener una estructura 3D a partir del conjunto de

emparejamientos. Para ello, se utilizará un método de triangulación (Hartley y

Zisserman 2003 y Torr 1995 y 2002). La triangulación consiste en calcular los rayos de

59

<!-- p. 72 -->

\3. Metodología

retro-proyección de los dos puntos imagen que forman una correspondencia. El punto

3D donde coincidan estos dos rayos formará parte del modelo 3D que buscamos. Para
cada emparejamiento (x, x’) se puede calcular un punto 3D. Como se cuenta con las
matrices de proyección P y P’, el punto X de la escena debe cumplir las condiciones:

x = PX x’ = P’X

Lamentablemente no es sencillo hacer coincidir los rayos de retroproyección de un
emparejamiento en ese punto X. Cualquier emparejamiento (x, x’) lleva consigo un

error de medida. En esta metodología se propone un esquema sencillo de triangulación

lineal. Este esquema se basa en el hecho de que los puntos imagen emparejados pueden

tener ese cierto ruido (error), y por tanto los rayos retro-proyectados de estos puntos no

coinciden en el espacio. Existe un segmento que una la distancia más corta entre las dos

líneas rectas que representan los dos rayos de retroproyección. El esquema propuesto

soluciona este problema minimizando una función de coste que representa el error (o

ruido) en la imagen:

min 2 2 (d ( x , PX ) + d ( x ,' P ' X ) )
X

donde d es la distancia euclídea entre dos puntos. Una vez corregido este error se

obtiene la estructura 3D de la escena.

Figura 3.4: Ejemplo de triangulación.

3.2.2. Fase 6: Triangulación Delaunay: Obtención de una superficie TIN.

Como resultado de la Fase 5 de este bloque, se obtiene un conjunto de puntos 3D

que son la base de esa superficie previa necesaria para el cálculo de los mapas densos de

profundidad del Bloque III. Por tanto, a partir de este conjunto de puntos se obtiene una

superficie TIN (Triangular Irregular Network). Para solucionar esta tarea una de las

60

<!-- p. 73 -->

\3. Metodología

soluciones más sencillas es utilizar el algoritmo de triangulación de Delaunay (Bern y

Eppstein 1992).

Una triangulación de Delaunay es una red de triángulos que cumple la condición de

Delaunay. Esta condición dice que la circunferencia circunscrita de cada triángulo de la

red no debe contener ningún vértice de otro triángulo. Esa es la definición original para

espacios bidimensionales. Es posible ampliarla para espacios tridimensionales, usando

la esfera circunscrita en vez de la circunferencia circunscrita. Esa condición asegura que

los ángulos del interior de los triángulos son lo más grande posible. Es decir, maximiza

la extensión del ángulo más pequeño de la red.

Las triangulaciones de Delaunay tienen las propiedades siguientes:

\- La triangulación forma la envolvente convexa del conjunto de puntos.

\- El ángulo mínimo dentro de todos los triángulos está maximizado.

\- La triangulación es unívoca si en ningún borde de la circunferencia

circunscrita hay más que tres vértices.

La solución utilizada en esta tesis, es la de dos dimensiones. El resultado se puede

observar en la figura 3.4 (la línea roja representa el límite del glaciar rocoso). Tal y

como se apreciará en el siguiente bloque, la obtención de esta superficie previa mejora

la obtención de los mapas densos de profundidad, además de aligerar el tiempo de

cómputo necesario para su cálculo.

Figura 3.5: Ejemplo de superficie triangulada por Delaunay

61

<!-- p. 74 -->

\3. Metodología

3.3. Bloque III: Modelo 3D final.

3.3.1. Fase 7: Mapas densos de profundidad.

La principal entrada de datos que requiere el algoritmo es un conjunto de imágenes

o vistas de la escena y las matrices de proyección (parámetros internos y la orientación

externa) de cada cámara (posición de cámara). También será necesario conocer algunos

datos más sobre la escena que se quiere reconstruir (medidas aproximadas de la escena).

Por ejemplo se podrá establecer un margen de profundidades donde se buscará la

profundidad correcta.

El algoritmo implementado (De Matías et al. 2009b) en la solución seleccionada

consiste en dos pasos:

\- La generación de un mapa de profundidad por cada vista de entre las que

contamos como parámetro de entrada.

\- La unión de todos los mapas de profundidad en un solo modelo mallado global.

Generación de los mapas de profundidad (Depth map generation)

El primer paso consiste en elegir, de entre el conjunto de vistas de la escena
V = {V1 ,...,Vn } , una vista de referencia R ∈ V . Para esa imagen de referencia se elige

además k vistas vecinas C = {C1 ,..., C k }∈ V − R con las que se correla a R usando un

emparejamiento robusto de ventana. Para cada píxel p en R, se recorre su rayo de

retroproyección en el intervalo de profundidad que se haya establecido para la escena

que se quiere reconstruir. El rayo de retroproyección es la línea que parte del centro de

proyección de la cámara, corta el plano de la imagen en el píxel p, e incide en una

profundidad (que aún no se conoce) con alguno de los puntos de la escena. La

profundidad es la distancia entre plano de la imagen y el punto de la escena donde

incide el rayo de retroproyección. Se calcula el rayo de retroproyección (figura 3.5) del

píxel p para varios valores de d. Estos valores están comprendidos entre la profundidad

mínima y máxima que hayamos establecido en la escena. Además, también hay que

establecer un valor de incremento de la profundidad ∆ depth . Para cada valor de

profundidad se calcula el punto 3D de la escena donde incide el rayo de retroproyección

para ese valor. Ese punto 3D se reproyecta en las imágenes vecinas. Se computa una
correlación cruzada normalizada NCC (R , C j, d ) utilizando una ventana centrada en el

62

<!-- p. 75 -->

\3. Metodología

píxel p y las ventanas correspondientes centradas en las proyecciones en cada una de las

vistas vecinas C j ( j ∈ [1 ..k ] ) con una precisión subpíxel.

Figura 3.6: Esquema de retroproyección y reproyección

Cuando dos vistas muestran un área similar de un objeto con textura, se obtiene un

valor alto de NCC para el valor d. Si, en caso contrario, hay por ejemplo una oclusión,

reflejos, u otro factor, el valor NCC obtenido es bajo para todas las hipótesis de

profundidad. Se ha de confiar en un valor de profundidad sólo si la ventana en la vista

de referencia correla bien con la correspondiente ventana en las vistas vecinas. Se dice
que un valor de profundidad d es válido si NCC (R , C j, d ) es mayor que un umbral tresh

para al menos dos vistas de C. El conjunto de vistas con NCC mayor que tresh para una

profundidad dada d se denota como Cv (d) .

Para un valor de profundidad válido d, se calcula un valor de correlación corr(d)

como la media de los valores NCC de todas las vistas de Cv (d) :

NCC (R , C j , d ) ∑C j ∈Cv ( d ) corr ( d ) =
C v ( d )

Cv (d ) evalúa el número de elementos en Cv (d) . Para cada píxel p en R, la

profundidad que se elige es la que maximiza el valor de corr(d), o ninguno si no se

encuentra un valor válido de d. El algoritmo también calcula un valor de confianza

conf(d) para cada valor de profundidad recuperado mediante la siguiente ecuación:

NCC ( R , C j , d ) − thresh ∑C j ∈C v ( d ) conf ( d ) =
C 1( − thresh )

63

<!-- p. 76 -->

\3. Metodología

Esta función de confianza se incrementa con el número de vistas válidas y es una

información necesaria en el proceso de unión de los distintos mapas obtenidos. En las

figuras 3.6 y 3.7 se muestran los pseudo-códigos de los algoritmos del cálculo de los

mapas de profundidad y de cálculo de la correlación.

Pseudo-code of depth-map program

Objective: Calculate a depth map

Function:

for i from 1 to WITDH_IMAGE, and j from 1 to HEIGHT_IMAGE do

q_2d = [i, j];

for d from DEPTH_MIN to DEPTH_MAX do

Q_3d = back_project(q_2d, d);

corr = calculate_corr(q_2d, Q_3d, d);

we select the depth d with the best corr

endfor

endfor

Figura 3.7: Pseudo-código de calculate_depth_map.

Pseudo-code of calculate_corr

Objective: calculate corr for a pixel.

Function:

k: number of neighboring views

NCC_total = 0

NCC_number = 0

for j from 1 to k do

project Q_3d in j view;

calculate NCC;

if NCC > thresh then

NCC_total = (NCC_total + NCC)/2;

NCC_number = NCC_number

\+1;

endif

endfor

Figura 3.8: Pseudo-código de calculate_corr.

64

<!-- p. 77 -->

\3. Metodología

Otro aspecto importante de la solución elegida para el cálculo de modelo denso es

la definición de profundidad. En algunos casos, la profundidad puede entenderse como

la distancia en la dirección perpendicular al plano de la imagen (Mc Glone 2004), sin

embargo, en este caso se trabaja considerando la profundidad como la distancia

calculada a lo largo de la recta que une el centro de la cámara y el punto 3D que se

quiere reconstruir. De esta forma, es más sencillo establecer el intervalo prioritario

donde el algoritmo busca la profundidad correcta.

Primera estimación de profundidad utilizando una superficie previa.

Uno de los principales problemas, que se ha encontrado utilizando este método de

reconstrucción densa, es la estimación de un intervalo de profundidad inicial donde

realizar la búsqueda de la profundidad correcta. Normalmente se ha de establecer un

valor mínimo y otro máximo para cada punto de la imagen. El hecho de no tener una

buena estimación inicial de la profundidad obliga al uso de grandes intervalos que

pueden ser problemáticos. En primer lugar por la gran cantidad de tiempo de

computación necesaria, y además porque los resultados obtenidos podrían no ser

correctos (se pueden obtener altos valores de NCC en profundidades diferentes). Por

tanto, es necesario encontrar una forma de conseguir esa estimación inicial de la

profundidad de cara a obtener un buen resultado.

La solución propuesta en esta metodología para solventar el problema de la

estimación de la profundidad es el cálculo de una superficie previa del terreno. Esta

superficie no es tan densa y tan precisa como la que consigue al final de esta fase de la

metodología, sin embargo, sí permite utilizarla para la estimación del intervalo inicial

donde buscar la profundidad final. La intersección de los rayos de la cámara con esta

superficie del terreno será una razonable estimación inicial de la profundidad (Figura

3.8).

65

<!-- p. 78 -->

\3. Metodología

Figura 3.9: Estimación utilizando una superficie triangulada.

De esta forma se puede obtener una buena estimación inicial de profundidad a

partir de la cual se comienza la búsqueda de la profundidad correcta. El método de

reconstrucción consigue completar y mejorar la superficie inicial del terreno hasta

conseguir una reconstrucción tridimensional densa.

Estructura piramidal

Otro problema importante del método de emparejamiento denso viene de trabajar

con imágenes muy grandes (por ejemplo imágenes de 12 o más Megapíxeles), puesto

que el método original (Goesele et al. 2006) calcula un valor de profundidad para cada

píxel de la imagen de referencia. Esto supone un gran coste computacional, y por tanto

incrementa notablemente el tiempo necesario para conseguir una reconstrucción. En

este sentido lo que se propone es utilizar una estructura piramidal para procesar las

imágenes. La estructura piramidal es una mejora típica en el procesamiento de imágenes

(Bachiller et al. 2008) y es una forma adecuada para adaptar un algoritmo a unos

requerimientos menores de computación.

En este caso, el objetivo es trabajar con imágenes en varios niveles de tamaño

(normalmente dos, ver figura 3.9). Cada píxel en un nivel tiene su correspondiente en el

siguiente nivel. El nivel más alto de la pirámide (la del tamaño menor) es la imagen

sobre la que se calcula la profundidad en cada píxel. Cuando se encuentra el mejor valor

de correlación (mayor que el umbral impuesto) se prueba el proceso de correlación con

66

<!-- p. 79 -->

\3. Metodología

el correspondiente píxel en los otros niveles (por ejemplo el nivel más bajo en la figura

3.9). De esta forma, cada nivel tiene un propósito específico en el algoritmo:

\- El nivel más alto (con la imagen de menor tamaño) determina la cantidad de

píxeles donde calcula un valor de profundidad y por consiguiente la cantidad de

posibles puntos 3D de la reconstrucción final.

\- El nivel o niveles más bajos (con los tamaños de imágenes mayores) refuerzan

las profundidades obtenidas anteriormente.

Figura 3.10: Estructura piramidal.

Utilizando esta sencilla técnica se puede decidir la densidad de puntos de la

reconstrucción final, así como reducir el tiempo de ejecución o ajustarlo a los

requerimientos de cada caso.

Unión de los mapas de profundidad

En los pasos anteriores se ha producido un conjunto de mapas densos, a veces

incompletos (sobre todo si sufrimos el problema de las oclusiones), con unos valores de

confianza para cada profundidad calculada. El siguiente paso consiste en la unión de

todos ellos en una sola representación triangulada de la superficie. Para hacer esta

unión, se usa como en (Goesele et al. 2006), la aplicación del método volumétrico

propuesto por los autores Curless y Levoy (Curless y Levoy 1996). Esta aproximación

fue desarrollada en un principio para la unión de datos 3D obtenidos con un láser

67

<!-- p. 80 -->

\3. Metodología

scanner. La aplicación convierte cada mapa de profundidad en un volumen ponderado

(se establece un peso para cada vértice) por la distancia, forma una suma de estos

volúmenes (de los diferentes mapas de profundidad) y extrae una superficie (Goesele et

al. 2006, De Matías et al. 2009b, 2010a).

Este método de unión tiene un número importante de propiedades que hacen de él

una solución muy apropiada en la metodología que se propone. Particularmente habría

que destacar su robustez ante la presencia de outliers (aquellos puntos que no se adaptan

al ajuste general), y la representación de la incertidumbre direccional. El algoritmo de

unión comienza con la reconstrucción de una malla triangulada para cada vista y

reduciendo el peso de los puntos que se sitúan cerca de las discontinuidades y los puntos

vistos desde ángulos muy inclinados. Estas mallas se convierten, utilizando los pesos de

cada uno de los vértices, en un volumen listo para unir con otros. Los puntos o vértices

outliers serán los que se filtren tras uno o dos muestreos automáticamente, puesto que

no podrán formar triángulos en la primera fase del algoritmo. Algunos grupos de

outliers podrían formar pequeñas superficies desconectadas del resto. Estas superficies

tendrán pesos bajos, ya que todos sus puntos están cerca de las discontinuidades de

profundidad y probablemente no podrán ser confirmadas desde otras vistas. Pueden ser

eliminadas en un postproceso que prescinda de las partes con un bajo índice de

confianza o extrayendo el componente conectado de mayor tamaño. El resultado es una

malla triangulada que integra todas las superficies obtenidas a partir de los mapas de

profundidad.

3.4. Bloque IV: Desplazamiento de bloques.

El último paso es el que permite el estudio del desplazamiento de bloques en la

monitorización del glaciar. Lo que se busca es relacionar los modelos tridimensionales

obtenidos en una campaña con los obtenidos en otra posterior. El método

fotogramétrico estándar, así como gran parte de las técnicas de visión por computador,

contemplan sólo la posibilidad de reconstruir una escena en un instante en el tiempo

(reconstrucción estática). De una de estas reconstrucciones es difícil obtener

información dinámica, como la que nos hace falta para estudiar el movimiento de un

glaciar. Como ya se explicó en el capítulo de introducción, en gran parte de los estudios

68

<!-- p. 81 -->

\3. Metodología

geomorfológicos es muy interesante obtener información de la dinámica de los glaciares

rocosos.

Por tanto, es indispensable una técnica que permita enlazar puntos en imágenes

tomadas en diferentes campañas. De esta forma, se pueden obtener productos que

representen los movimientos de bloques del glaciar, para facilitar las tareas de

monitorización. Las informaciones a obtener van en dos direcciones, por un lado, se

obtiene información referente a desplazamientos en el plano horizontal X-Y, tanto en

dirección como en magnitud, y por el otro, desplazamientos en el eje vertical Z (en

magnitud), y todo ello a nivel local.

Tal y como se expone en el apartado de experimentos, en gran parte de los

proyectos de monitorización de glaciares, esta tarea se realiza utilizando métodos

geodésicos (por ejemplo GPS) para la medición de un conjunto reducido de puntos de

control (por ejemplo en el caso del Veleta, que se expone en los experimentos, se

controlan unos 35 puntos). Lo que se pretende en este bloque es desarrollar una técnica

automática para conseguir una mayor cantidad de relaciones entre los puntos

reconstruidos en diferentes campañas, fusionando métodos de la fotogrametría y de

visión por computador.

La técnica desarrollada en esta metodología se ha llamado dense flow vectors, que

traducido al español, es algo así como vectores densos de flujo. Son de flujo puesto que

representan los movimientos de un bloque, densos por la cantidad obtenida de ellos por

cada par de imágenes y vectores, puesto que representan la dirección, sentido y

magnitud del desplazamiento de una parte del glaciar.

3.4.1. Fase 8: Dense Flow Vectors.

La idea principal para conseguir los dense flow vectors es combinar dos de las

técnicas de las que ya se han tratado en el desarrollo de esta metodología:

\- Por un lado, se ha visto como los mapas de profundidad son una sencilla y a la

vez potente herramienta para la representación de reconstrucciones densas

tridimensionales. Como ya se indicó, permiten almacenar en una misma

estructura, información 3D (reconstrucción tridimensional de la escena en forma

de datos de profundidad) e información 2D (imágenes obtenidas de las tomas

realizadas en la escena).

69

<!-- p. 82 -->

\3. Metodología

\- Por otro lado, ya se trató en el capítulo anterior el conjunto de métodos para el

emparejamiento de imágenes que ha ido surgiendo en los últimos años y que ha

revolucionado esta parcela de la visión por computador. Entre otras cosas, se

indicó como el método SIFT es uno de los algoritmos más indicados de toda esta

nueva generación de métodos y descriptores, ya que consigue emparejamientos

correctos con cambios importantes entre las imágenes (escala, orientación,

iluminación,…). Estas características hacen de él una herramienta muy útil para,

por ejemplo, buscar puntos homólogos en imágenes tomadas con distintas

cámaras, con distintos objetivos, o incluso en diferentes épocas (hasta con varios

años de diferencia).

Por tanto, si se dispone de mapas de profundidad en los que a cada píxel de una

imagen digital se le asocia un valor de la profundidad tridimensional de la escena y

métodos que permiten emparejar puntos característicos entre imágenes de diferentes

épocas, se puede relacionar puntos 3D calculados en una campaña con sus homólogos

en otra anterior o posterior.

Cálculo de los dense flow vectors.

Cuando se le aplica a una imagen el método SIFT lo que se obtiene es un conjunto

de descriptores con las propiedades ya comentadas (invariabilidad a la escala, a las

rotaciones, a los cambios de iluminación,…). Como ya se ha explicado, si se quieren

buscar emparejamientos entre dos imágenes se comparan los conjuntos de descriptores

obtenidos de cada imagen para encontrar aquellos descriptores que coinciden entre los

dos conjuntos.

El objetivo es encontrar representaciones del mismo punto en dos imágenes

diferentes. Es poco probable encontrar descriptores completamente idénticos entre las

dos imágenes. Por ello se establece un índice de similaridad. Éste no es más que un ratio

mínimo entre la distancia del más próximo y del segundo más próximo. El valor de este

índice se ha de establecer de forma experimental. Como referencia se puede tomar el

valor de 0,8. Este valor es el que el autor de SIFT establece como el más adecuado para

la base de datos de descriptores con los que trabaja (Lowe 2004). Aunque 0,8 es la

referencia este valor puede variarse. Si se elige un valor inferior a 0,8, lo que se hace es

restringir las posibilidades para que dos descriptores se consideren similares. Por lo que

70

<!-- p. 83 -->

\3. Metodología

se obtendrán menos emparejamientos (si el valor es de cero para que dos descriptores se

consideren similares han de ser idénticos). En caso contrario, si se elige un valor

superior a 0,8, se amplia el abanico de posibles candidatos a puntos homólogos. En el

primer caso se obtienen menos emparejamientos con una mayor robustez y en el

segundo caso se obtienen más emparejamientos, pero con más posibilidades de obtener

puntos homólogos erróneos.

La forma de elegir este valor umbral es experimental y depende del tipo de

imágenes con las que se trabaje. En el capítulo de experimentos se discute cual es el

valor más adecuado.

El ajuste del valor umbral permite que se puedan encontrar descriptores SIFT

homólogos entre imágenes tomadas en diferentes años. Cada una de estas imágenes se

encuentra relacionada con un mapa de profundidad que permite establecer las relaciones

entre aquellos bloques aparecidos en las imágenes que no hayan sufrido excesivas

deformaciones (como es muy común en la monitorización de glaciares).

Este proceso se puede implementar mediante los siguientes pasos:

\1. Se selecciona una imagen de la campaña 1 y otra de la campaña 2 con sendos

mapas de profundidad asociados.

\2. Se extraen los descriptores SIFT de la imagen de la campaña 1 y de la misma

forma, los descriptores SIFT de la imagen de la campaña 2.

\3. Se comparan ambos conjuntos de descriptores SIFT para obtener aquellos que

son similares. Previamente, y de forma experimental, se debe haber elegido un

valor umbral de distancia entre primero y segundo que permita decidir que

descriptores se pueden considerar similares y cuales no.

\4. Se obtiene un conjunto de puntos homólogos en las imágenes de ambas

campañas. Un par de puntos homólogos será un par de puntos imagen de la

forma [xcampaña1, y campaña1, x campaña2, y campaña2], que representa las coordenadas

píxel del punto homólogo.

\5. Se relaciona esta información 2D (puntos en las imágenes) con información 3D

(puntos 3D obtenidos a partir de la información de profundidad). De esta forma

se obtienen pares de puntos 3D del tipo:

71

<!-- p. 84 -->

\3. Metodología

o [Xcampaña1, Y campaña1, Z campaña1, X campaña2, Y campaña2, Z campaña2]. Estos dos

puntos 3D determinan una dirección, un sentido y una distancia, es decir,

un vector que es a lo que se denomina dense flow vector.

\6. Estos vectores representan el desplazamiento de un punto característico de la

escena a través del tiempo. A partir de ellos se puede obtener de forma sencilla:

o Información de los desplazamientos en el plano XY.

o Información de los desplazamientos en el eje Z.

\7. Los pasos del 1 al 6 se repiten para cada par de imágenes de las campañas 1 y 2.

Es imprescindible contar con la información tridimensional de los mapas de

profundidad.

Este proceso permite obtener información dinámica de la escena, en forma de un

conjunto de vectores de desplazamiento, a partir de la información estática que suponen

los puntos 3D de la escena.

Este último bloque cierra la metodología que se propone en esta tesis doctoral.

Como se indica en el capítulo de introducción, el fin último es el de obtener

información cartográfica a partir de un conjunto de imágenes. Esta información

cartográfica, resultado de todo el proceso descrito en este capítulo, se puede resumir en

dos grupos:

\- Por un lado la información estática de la escena, que representa los resultados de

cualquier proyecto fotogramétrico. En este caso, esta información se produce en

forma de mapas de profundidad. No hay que olvidar que un mapa de

profundidad no es más que la situación de una cámara, el plano de la imagen de

esa cámara y de un conjunto de valores de profundidad, y que puede ser

traducido de forma sencilla a una nube de puntos 3D.

\- Por el otro se encontraría ese conjunto de vectores obtenidos en este bloque

(dense flow vectors) y que suponen la información dinámica de la escena. Estos

resultados no son comunes en cualquier proyecto fotogramétrico, y son los que

permiten establecer el comportamiento de los distintos bloques de la escena a lo

largo del tiempo.

72

<!-- p. 85 -->

\3. Metodología

En el capítulo siguiente se incluyen los resultados que con esta metodología se han

obtenido en los escenarios seleccionados para realizar los experimentos del trabajo.

73

<!-- p. 86 -->

\3. Metodología

74

<!-- p. 87 -->

Capítulo 4: Experimentos.

<!-- p. 88 -->

\4. Experimentos

76

<!-- p. 89 -->

\4. Experimentos

\4. Experimentos

En el capítulo anterior se han explicado los detalles la metodología propuesta en

este trabajo. Ya se ha visto como la metodología se ha divido en 4 bloques principales.

Un primer bloque dedicado al conocimiento de todo lo relativo a la cámara (calibración

interna y orientación externa), un segundo bloque, en el que se obtiene una primera

superficie previa, que es muy útil para el tercer bloque, en el que se calculan los mapas

densos de profundidad (dense depth maps). En el último bloque se trata la posibilidad

de enlazar los modelos de diferentes campañas mediante los dense flow vectors.

Como en toda tesis doctoral que propone una metodología eminentemente práctica,

es necesaria una validación de resultados con ejemplos reales (o lo más realistas

posibles). Esta validación debe ser la demostración de la idoneidad de lo propuesto.

Tal y como se indica en el título de esta tesis doctoral, la metodología que se ha

desarrollado pretende el modelado 3D de estructuras geomorfológicas dinámicas.

Aunque la metodología a desarrollar tenga un campo de aplicación lo más amplio

posible, desde un principio el objetivo ha sido su utilización en proyectos relacionados

con la geomorfología (principalmente glaciares rocosos).

Los ámbitos de experimentación y validación, uno principal y otro secundario, de

la propuesta básica de este trabajo han sido dos escenarios naturales en los cuales el

grupo de investigación “Ingeniería Geomática y Patrimonio Urbano” de la Universidad

de Extremadura ha desarrollado su labor investigadora en la última década: el glaciar
rocoso del Corral del Veleta de Sierra Nevada y el helero del Jou Negro en la

Cordillera Cantábrica.

El capítulo se ha dividido en dos apartados. Un primer apartado donde se detallan

los materiales utilizados (cámaras e instrumental topográfico) y un segundo apartado

donde se habla de los escenarios de cada uno de los experimentos, así como de los

resultados obtenidos en cada caso.

4.1. Materiales utilizados

Para el trabajo de campo se ha contado con un dispositivo que permita tomar

imágenes y otro que permita realizar medidas de algunos puntos de apoyo. En el primer

grupo de dispositivos se ha contado con una cámara analógica y otra digital, mientras

77

<!-- p. 90 -->

\4. Experimentos

que en el segundo grupo con dos tipos de tecnologías para la medición de los puntos de

apoyo, por un lado una estación total de tecnología láser y por otro un receptor GPS de

medición.

4.1.1. Cámaras utilizadas

La primera de las cámaras utilizadas es una del modelo Rollei 6008. Es un modelo

de cámara analógica, para película de medio formato (6x6), de las llamadas

semimétricas. Además se dispuso de tres lentes de focal fija, concretamente un 40 mm,

un 60mm y un 120 mm. Este tipo de modelo de cámara es muy común en la realización

de trabajos de fotogrametría analítica e incluso digital (mediante la digitalización de los

negativos).

Figura 4.1: Cámara Rollei 6008

Aunque se ha contado con una cámara de este modelo, no se ha utilizado en los

experimentos con los que se ha probado la metodología que propone esta tesis doctoral.

Únicamente se utilizaron algunas imágenes tomadas con esta cámara durante las

campañas de 2003 y 2005. El hecho de no utilizar esta cámara reside en el proceso de

digitalización necesario para su uso en los diferentes proyectos. Lo que aquí se propone

es una metodología totalmente digital, por lo que no parecía correcto partir de una

cámara analógica. Sí se tenía acceso a un escáner de negativos de gran calidad (Vexcel

Ultrascan 5000), con el que se digitalizaron por ejemplo las citadas campañas de 2003 y

\2005. Sin embargo, se intentó eliminar la tarea de digitalización, primero por ser un

trabajo extra, segundo por la consiguiente pérdida de calidad que supone un proceso de

escaneado. Esto supuso descartar este modelo de cámara y plantear desde un principio

el uso de un modelo digital completo con calidad suficiente.

78

<!-- p. 91 -->

\4. Experimentos

En la última década el avance en la tecnología y el abaratamiento del equipamiento

de fotografía digital han sido muy importantes. Resulta bastante económico adquirir una

cámara digital tipo réflex de calidad profesional y mucho más barato la adquisición de

modelos orientados al aficionado a la fotografía. Es por esto que la adquisición de una

cámara con calidad profesional (o semiprofesional) no es un problema en este tipo de

proyectos. Teniendo en cuenta estas razones se eligió para la realización de estos

experimentos una cámara Canon EOS 5D. Ésta mantiene ciertas características respecto

al resto de cámaras que la hacen diferente, y muy práctica en muchos trabajos. Su

principal ventaja en el momento de su aparición en el mercado respecto a sus
competidoras era el hecho de ser la primera cámara de formato completo1 a un precio

relativamente asequible. Esta característica implica olvidarse de los llamados factores

de multiplicación que conllevaban otros modelos anteriores. Es decir, aquellas cámaras

con un tamaño de sensor inferior al fotograma de 35 mm implicaban un factor de

multiplicación de las lentes que se utilizaran (a menudo factores de 1,4 o 1,6). Este

factor de multiplicación favorece el uso de teleobjetivos, pero castiga el uso de grandes

angulares. Por tanto, la cámara que se seleccionó para este trabajo es una cámara digital

y con un acabado casi profesional, muy adecuado para el objetivo por el que se

adquirió.

Figura 4.2: Cámara Canon EOS 5D

Para este modelo de cámara se contó con dos lentes de focal fija, una de 35 mm y

otra de 100 mm. El hecho de utilizar focales fijas se debe a la estabilidad de este tipo de

lentes. Esta característica es esencial para que los datos de calibración que se obtengan

de ella sean realmente fiables.

1 Se llama cámara de formato completo a aquella cuyo tamaño de sensor es el tamaño de un fotograma de
película de 35 mm.

79

<!-- p. 92 -->

\4. Experimentos

4.1.2. Instrumental topográfico

Ante la necesidad de establecer la posición de algunos puntos de control vitales

para determinar la orientación externa de las cámaras, durante el desarrollo de los

experimentos de esta tesis doctoral se han utilizado dos tipos de dispositivos:

\- Una estación total para la medición sin prisma, en concreto el modelo Topcon

GTS-502E.

\- Receptores GPS de medición, en este caso el modelo que se utilizó es el Leica

de la serie 1200 con tecnología GNSS (Global Navigation Satellite System) y

RTK (Real Time Kinematic). Permiten el uso de satélites GPS (sistema

americano) y GLONASS (sistema ruso).

Figura 4.3: Estación Topcon GTS-502E

Figura 4.4: Receptores GPS Leica 1200

80

<!-- p. 93 -->

\4. Experimentos

4.2. Escenarios de trabajo

Los experimentos de la tesis doctoral se centran en producción de cartografía en

zonas de alta montaña, para el estudio de algunos procesos geomorfológicos

(principalmente glaciares rocosos).

Este tipo de escenarios son un buen campo de pruebas de la metodología propuesta.

Por un lado, por ser un tipo de escenario sin “estructura creada por el hombre”, es decir,

son conjuntos de rocas donde no es posible ver la mano del hombre (no hay líneas

rectas, círculos, etc.). Esto impide que se puedan aplicar técnicas de, por ejemplo,

fotointerpretación, que si son útiles en otros escenarios.

Por otro lado, en la mayoría de los casos son zonas de muy difícil acceso que

dificultan, en muchas ocasiones, la utilización de técnicas válidas para la mayoría de

reconstrucciones tridimensionales. En casos como estos, no son aplicables, o su

aplicación resulta muy cara y de no tan buenos resultados (vuelos fotogramétricos, por

ejemplo). La mala accesibilidad de las zonas de alta montaña donde se ha trabajado

dificulta aún más este tipo de proyectos. En otros trabajos similares se observa como es

común otro tipo de aproximaciones a la obtención de este tipo de cartografía, tal y como

se pudo ver en el capítulo 2 (Fotogrametría aérea y Fotogrametría mediante fotografía

de satélite). Sin embargo, a menudo estas aproximaciones son muy caras o no se pueden

obtener las precisiones que se pretenden y que sí se obtienen si se reduce la distancia al

escenario a fotografiar, por ejemplo, con fotogrametría terrestre.

Además de las razones puramente técnicas, existen otras que tienen que ver con la

aplicabilidad de la tecnología. No debe olvidarse cómo los experimentos de esta tesis

doctoral pretenden observar, estudiar y cuantificar unos fenómenos geomorfológicos

(glaciares rocosos, heleros, etc.) esenciales en algunos proyectos de estudio de la

variación climática terrestre. En todos ellos, la metodología que se propone produce una

serie de productos cartográficos que facilita la tarea de los geomorfólogos que estudian

este tipo de fenómenos. Por tanto, lo que se propone tiene una validez científica

inmediata, aparte de las posibles futuras aplicaciones de las que se hablarán en el último

capítulo de conclusiones.

Además de usar esta metodología en los escenarios de trabajo comentados, se

utilizaron, y se siguen utilizando técnicas, como la topografía, la geodesia y la

fotogrametría clásica. No se pretende olvidar estas técnicas. Más bien se tiene como

81

<!-- p. 94 -->

\4. Experimentos

objetivo completarlas. Se puede decir que este trabajo sólo “competirá” con los

resultados de la fotogrametría clásica. Los resultados que se obtienen de la topografía y

la geodesia, siguen teniendo vigencia y resultan en muchos casos complementarios.

La principal forma de estudiar el movimiento de glaciares en anteriores trabajos

(De Sanjosé y Lerma 2001, 2004, De Sanjosé et al. 2006a, 2007) es la instalación de

una serie de varillas, fijadas a lo largo del escenario, y medidas utilizando, o bien

técnicas topográficas (estación total para medición con o sin prisma), o bien técnicas

geodésicas (dispositivos GPS). Las varillas se mantienen de año en año, lo que permite

que podamos realizar un seguimiento del desplazamiento del glaciar, tanto en

profundidad como longitudinalmente. Las precisiones de ambas técnicas son excelentes

(entre 2 y 3 cm para la estación total y entre 3 y 4 cm para los dispositivos GPS).

Acercarse a estas precisiones con otro tipo de técnicas como las propuestas es

francamente difícil. Sin embargo, es posible competir con ellas en cuanto a la cantidad

de puntos obtenidos y la facilidad de obtenerlos. Normalmente, no se instalan más de 20

o 25 varillas en cada escenario. La información que de ellas se obtiene es suficiente para

muchos de los estudios realizados, pero se puede quedar corta en otros, por la escasa

cantidad de datos obtenidos. En los dos escenarios que se incluyen a continuación se

especifican algunos de los datos obtenidos con estas técnicas. En algunos casos,

también son útiles para la comparación de los resultados obtenidos en estos

experimentos con la metodología propuesta.

4.2.1. Glaciar del Veleta en Sierra Nevada.

El Glaciar del Veleta en Sierra Nevada ha sido el principal escenario seleccionado

donde validar los métodos propuestos. Los datos allí obtenidos son la base más

importante de los experimentos de esta tesis doctoral. En primer lugar se incluye una

introducción geográfica y geomorfológica del escenario, realizada por el catedrático D.

Antonio Gómez Ortiz de la Universidad de Barcelona, para posteriormente describir qué

resultados se obtuvieron en la aplicación de la metodología.

82

<!-- p. 95 -->

\4. Experimentos

Introducción geográfica y geomorfológica (A. Gómez Ortiz).

El macizo de Sierra Nevada

Sierra Nevada forma parte de las cordilleras Béticas y conforma un robusto macizo

instalado en el SE de la Península Ibérica (37ºN/3ºW), cercano al Mediterráneo.

Regionalmente se distribuye en dirección oeste-este, entre las provincias de Granada y

Almería y morfoestructuralmente ofrece una nítida delimitación. Su fachada meridional

la fijan los surcos del Guadalfeo y Andarax, que la aíslan de las sierras de Lújar,

Contraviesa y Gádor. La fachada norte y extremo occidental la definen la Vega de

Granada y la Depresión de Guadix-Baza. En cuanto a su extremo oriental tiende a

diluirse hacia el surco del río Nacimiento debido a que los cordales cimeros de la Sierra,

a partir del Picón de Jéres (3094 m) declinan progresivamente en esta dirección

(Montenegro, 1710 m) (figura 4.5).

Figura 4.5: Macizo de Sierra Nevada (imagen Landsat)

Sierra Nevada se dispone a lo largo de más de 90 Km. y aglutina las mayores

altitudes peninsulares (Mulhacén, 3482 m; Veleta, 3398 m, Alcazaba, 3366 m; etc.). La

estructura básica de Sierra Nevada es una sucesión de mantos de corrimiento de origen

alpino construidos en rocas cristalinas paleozoicas y materiales triásicos. De su relieve

hay que destacar la predominancia de las formas evolucionadas, sobre todo en rellanos

de cumbres y laderas meridionales. También sobresale la compartimentación

generalizada que ofrece como respuesta a la organización de la red fluvial, tributaria del

83

<!-- p. 96 -->

\4. Experimentos

Mediterráneo y Atlántico. Las huellas glaciares en Sierra Nevada predominan por

encima de los 2500 m y hasta cotas bajas las de morfodinámica periglaciar.

La cubierta vegetal de Sierra Nevada destaca por su gran diversidad y riqueza de

especies. Lo explica la particular situación geográfica de la montaña y las adaptaciones

que la vegetación hace al clima, muy supeditado a la considerable altitud. Al respecto,

resalta que en los pisos más elevados, superados los 2900 m, reinen condiciones

climáticas propias de medios fríos periglaciares de montaña afectada por prolongada

aridez estival (precipitación anual superior a 710 mm a 2500 m y temperatura media

anual en torno a los 0ºC en los 3400 m de altitud) (Salvador et al. 2011).

Esta montaña, que pudiera parecer repulsiva a su antropización, pronto fue

humanizada en sus tramos bajos y medios. Así se desprende de la impronta secular que

el hombre fue dejando en el paisaje, reflejo de culturas milenarias y modos de vida

diversos, siempre subordinados al imperativo del medio natural.

Sierra Nevada, macizo afectado por glaciares

La variabilidad climática cuaternaria tuvo un significado geomorfológico

importante en los principales sistemas montañosos de las latitudes medias y el

desarrollo de glaciares fue una de sus manifestaciones más relevantes. En el caso de las

montañas europeas constituyó su foco más meridional. Sus principales sistemas

glaciares quedaron relegados en los tramos más elevados de la montaña, concentrándose

en las cabeceras de los barrancos (figura 4.6).

Figura 4.6: Cumbres de Sierra Nevada (ortofoto 2005, JA)

84

<!-- p. 97 -->

\4. Experimentos

Los sistemas glaciares de Sierra Nevada se extendieron desde el cerro de Trévelez

(2877 m) hasta el cerro del Caballo (3011 m), que es donde los cordales cimeros

sobrepasan los 3000 m (Mulhacén, 3482 m; Veleta, 3398 m; Alcazaba, 3366 m). Las

lenguas glaciares fueron de corto recorrido y no parece probable que sobrepasaran los

15 km. Los análisis realizados en diferentes registros glaciares (morfológicos y

sedimentológicos) tienden a mostrar la posibilidad de que la Sierra fuera afectada por

más de una glaciación (Gómez et al. 2002). Por lo que respecta a la desaparición

generalizada de los glaciares hay que señalar que se fijaría a partir de los 15000 BP

(Before present, antes del momento actual), que es cuando los hielos quedaron

encerrados en el seno de los circos. Los primeros estudios sobre el glaciarismo

cuaternario de Sierra Nevada debieron iniciarse a mediados del siglo XIX y se han

venido prolongando de manera sostenida hasta nuestros días (Gómez et al. 2002).

Históricamente Sierra Nevada, como otros núcleos de montañas de la península

Ibérica –Pirineos y Picos de Europa, por ejemplo- también fue afectada por la

denominada Pequeña Edad del Hielo (siglos XV/finales del XIX), lo que vendría a

confirmar que tal pulsación climática, con muy tenue repercusión en los modelados de

la Sierra, igualmente afectó al extremo suroeste de Europa. Siempre se trató de

pequeños focos glaciares encerrados en el seno de los antiguos circos. El espacio

glaciado incluyó los barrancos de la fachada norte de la Sierra y la sur. De entre los

focos más importantes el del Corral del Veleta fue el que perduró más tiempo.

El Corral del Veleta, último reducto glaciar

El Corral del Veleta forma parte de la cabecera del barranco del Guarnón. Está

situado en la cara norte de Sierra Nevada, al pie del picacho del Veleta (3392 m), entre

el cerro de los Machos (3374 m) y la cresta de los Lastrones. En su conjunto conforma

un cuenco ovalado abierto al noreste y labrado en bancos de micasquistos feldespáticos

de distinta naturaleza y resistencia (Sanz de Galdeano et al., 1998). Su base, inclinada

hacia el oeste, coincide con una repisa estructural (“vasar”) colmada de clastos que, en

dirección sur, entra en contacto con la pared vertical del picacho del Veleta y hacia el

norte, con un espeso cordón morrénico frontolateral que la aísla del valle. El Corral del

Veleta tiene una longitud (W-E) superior a los 600 m y una anchura (S-N) que oscila

entre los 175 y 250 m. Su desnivel es del orden de los 250-300 m, fijándose su cota más

baja en los 3050 m (figura 4.7).

85

<!-- p. 98 -->

\4. Experimentos

Figura 4.7: Corral del Veleta, agosto, 2009 (A. Gómez Ortiz)

La orientación y altitud del Corral del Veleta contribuyeron a que el foco glaciar

formado durante la Pequeña Edad del Hielo perdurara hasta fechas muy cercanas, pues a

finales del siglo XIX el cuenco aún permanecía colmado de masas de hielo y nieves, y

parcialmente, hasta bien sobrepasada la primera mitad del siglo XX (Quelle 1908 y

Messerlí 1965). En la actualidad no existe rastro visible del glaciar aunque si persisten

neveros o ventisqueros de fusión tardía en su base y pequeñas placas de hielo

permanente atrapadas en las paredes del tajo del Veleta. La presencia de estos cuerpos

helados, a los que hay que añadir el ya aludido hielo glaciar y permafrost enterrado bajo

escombro detrítico, se explican a partir del proceso de deglaciación que debió sufrir el

glaciar y que, una vez encerrado en su cuenco, se caracterizó por evolucionar

sucesivamente de glaciar blanco a glaciar negro y de éste a hielo glaciar fósil glaciar y

permafrost (Gómez et al. 2008).

La degradación de las masas heladas del Corral del Veleta

La existencia de hielos fósiles y permafrost alojado bajo manto detrítico en el seno

del Corral del Veleta fue detectada en el año 1998, a partir de los -120 cm, mediante

técnicas geofísicas y extracción de testigo. Desde el 2001 se viene analizando su estado

físico así como las repercusiones geomorfológicas que se operan en el manto detrítico

86

<!-- p. 99 -->

\4. Experimentos

de la base del circo (Gómez et al. 2008). Los análisis que se vienen haciendo se

traducen en el control de un incipiente glaciar rocoso (que actúa como muestra

significativa) cercano a la lagunilla del Corral en cuyo interior aún perduran bolsas de

hielo fósil glaciar y niveles de permafrost (figura 4.8). Las características de este glaciar

rocoso son:

Altitud media del cuerpo detrítico: 3106 m

Orientación: S-W (conforma una L)

Longitud: 129,6 m

Anchura media: 37,5 m

Espesor medio: 8 m

Superficie: 3815 m2

Material clástico: bloques heterométricos de micasquistos con abundante matriz

gruesa y fina interna.

Dimensiones de clastos: desde bloques de grueso calibre (varios m3) hasta cantos y

gravas de tamaño decimétrico-centimétrico.

En cuanto a los controles que se hacen para determinar su evolución son:

a) el régimen térmico del suelo.

b) el grado de recubrimiento nival en verano.

c) el desplazamiento de los bloques que recubren las masas heladas.

d) la caracterización geofísica de las masas heladas.

87

<!-- p. 100 -->

\4. Experimentos

Figura 4.8: Glaciar rocoso, agosto, 2009 (A. Gómez Ortiz)

La interpretación de los resultados obtenidos (hasta el año 2009) permite explicar

que los hielos glaciares relictos y el permafrost del glaciar rocoso se encuentran en

proceso continuado de degradación. Ello se justifica por las repetidas subsidencias que

sufre el paquete clástico y la disminución y desconexión de los cuerpos resistivos

congelados en profundidad. La interpretación que hacemos de estos acontecimientos es

resultado de la sucesión de procesos físicos en cascada, iniciados a partir de la radiación

externa que incide en el suelo, muy en particular desde que el glaciar rocoso queda

liberado del manto nival y las aguas de fusión recorren la capa activa. La degradación

de estas masas heladas sucede en verano, en pocas semanas, y de manera más notoria y

acelerada desde que la nieve tiende a permanecer menos tiempo en las cumbres de
Sierra Nevada, hace ya décadas (Gómez et al. 2011)2.

Monitorización del glaciar con técnicas geomáticas (2001 – 2009).

El dinamismo del glaciar rocoso del Corral del Veleta se controla a partir de

técnicas geomáticas que se iniciaron en el año 2001 (Sanjosé y Lerma 2001 y 2004).

Desde entonces los resultados obtenidos han mostrado diferentes tipos de movimientos

diferenciados en el tiempo y en los puntos de control (Sanjosé et al. 2006a y 2007).

Las diferentes técnicas geomáticas que se han aplicado a lo largo de este tiempo y

que han permitido determinar el dinamismo del glaciar rocoso han sido:

\- Empleo de estación total y geodesia con aplicación de GPS diferencial, que han

permitido el seguimiento de un total de 27 puntos fijos (varillas metálicas)

2 Aquí finaliza la introducción geográfica realizada por D. Antonio Gómez Ortiz.

88

<!-- p. 101 -->

\4. Experimentos

distribuidos por igual en su tramo frontal, medio y final. También con estación

total se controlaron varios perfiles transversales y longitudinales, así como el

contorno del glaciar rocoso.

\- Empleo de estación total sin prisma y apoyo de imágenes fotográficas para el

seguimiento del frente del glaciar rocoso, a partir del control de puntos fijos

relevantes en bloques (figura 4.9).

Figura 4.9: Fotografía superior, imagen general del frente del glaciar rocoso

captada con estación total. Fotografías inferiores, detalles del mismo punto durante

los años 2006, 2007 y 2008.

\- Uso combinado de distintos métodos de fotogrametría para la obtención de

cartografía de detalle (figura 4.10). En este apartado se encontrarían los

experimentos realizados en esta tesis doctoral.

89

<!-- p. 102 -->

\4. Experimentos

Figura 4.10: Punto de control utilizado en fotogrametría y toma de fotografías en el

pico del Veleta.

\- Utilización del láser escáner para el control preciso de sectores de interés y

cartografiado del conjunto del glaciar (figura 4.11).

Figura 4.11: Toma de datos con laser escáner.

El resultado de todas estas técnicas ha dado como resultado la obtención de

diversos tipos de cartografía, así como valiosa información acerca del desplazamiento

de los diferentes bloques del glaciar. A continuación, se incluye la tabla 4.1, con

información del desplazamiento del glaciar desde 2001, así como la figura 4.12, donde

se representa la evolución de dos perfiles topográficos del glaciar a lo largo de los años

en que se ha realizado la monitorización del mismo. Ambos resultados dan una idea

bastante precisa de su movimiento.

90

<!-- p. 103 -->

\4. Experimentos

PUNTOS 2001-2002 2002-2003 2003-2004 2004-2005 2005-2006 2006-2007 2007-2008

Frente (2,3,6) 8.0 / -17.3 13.9 / -35.5 3.7 / -11.0 24.9 / -63.9 18.6 / -46.6 19.5 / -47.00 11.7 / -43.5
Centro (10,11,12,13) 2.2 / -18.1 4.5 / -29.4 2.1 / -8.9 11.6 / -81.8 5.7 / -46.6 13.5 / -41.8 5.6 / -37.9
Cola (20,21) 40.7 / -63.2 39.4 / -63.6 21.5 / -35.6 60.8 / -97.3 40.2 / -71.8 46.2 / -57.6 36.0 / -64.8

Tabla 4.1: Desplazamiento medio (por sectores) planimétrico / altimétrico en cm

Figura 4.12: Evolución perfiles transversales (imagen superior) y longitudinal

(imagen inferior) del glaciar rocoso

Utilización de la metodología propuesta.

En este apartado se detalla cómo ha sido el uso de la metodología propuesta en el

glaciar del corral del Veleta. Se inicia con los datos de partida con los que se contó, para

después explicar cómo ha sido la aplicación de cada una de las fases de la metodología.

En cada fase se indican además los experimentos realizados para verificar la precisión

de los resultados obtenidos. Estos experimentos se indican con numeración romana.

Datos de partida

Tal y como se ha explicado, la toma de fotografías necesaria en estos experimentos

se realizó con el modelo de cámara Canon EOS 5D. Se han realizado tres campañas
para la obtención de datos, durante los años 2007, 2008 y 2009. No ha sido posible

obtener información ni en 2010, ni en 2011, por estar el glaciar cubierto de nieve

durante todo el verano. De manera que, las imágenes con las que se contó son las

siguientes:

\- En 2007 se obtuvieron 9 imágenes utilizando la única lente disponible en aquel

momento, la focal fija de 35 mm.

91

<!-- p. 104 -->

\4. Experimentos

\- En 2008, ya se contó con la otra lente de focal fija, la de 100 mm, por lo que se

obtuvieron dos baterías de imágenes. Un conjunto de 9 imágenes con la focal de

35 mm y otras 9 con la focal de 100 mm.

\- Por último en 2009, se contó de nuevo con ambas focales y se obtuvieron los

mismos dos conjuntos, de 9 imágenes con el 35 mm y de otras 9 con el 100 mm.

Además de estas imágenes obtenidas en el pico Veleta, se añadieron otras 6

imágenes tomadas desde una morrena situada en frente del pico, pero con una

distancia mucho menor al glaciar. Este punto de vista no nos permite hacer una

buena reconstrucción del glaciar. Sin embargo, estas imágenes se hicieron con el

objeto de rellenar las zonas de oclusiones que quedaban con el resto de

imágenes.

\- Ni en 2010, ni en 2011 se pudieron obtener fotografías, puesto que la nieve no

desapareció en todo el verano.

Además de estas imágenes de 2007 a 2009. Se contó con dos campañas anteriores,

concretamente del 2003 y del 2005, obtenidas utilizando la cámara analógica Rollei

6008, con su consecuente digitalización. Con estas imágenes no fue posible llevar a

cabo un proceso de reconstrucción, pero si fueron útiles en el apartado en el que se trata

el emparejamiento de imágenes históricas.

Por tanto, el primer conjunto de datos (y más importante en cualquier proyecto

fotogramétrico) es este conjunto de imágenes, que como se ha indicado se tomaron

desde el mejor punto de vista disponible, el pico del Veleta. En la figura 4.18 se incluye

un esquema donde se indican los puntos de vista desde donde se tomaron las fotografías

del objeto a cartografiar (en este caso el glaciar rocoso). En las figuras 4.13 y 4.14 se

muestran ejemplos de imágenes tomadas con el objetivo de 35mm y el de 100 mm

respectivamente.

92

<!-- p. 105 -->

\4. Experimentos

Figura 4.13: Ejemplo de imágenes realizadas con el objetivo de 35mm (2007)

Figura 4.14: Ejemplo de imágenes realizadas con el objetivo de 100mm (2008)

Además de las imágenes utilizadas, se contó con un conjunto de puntos de control,

necesarios para calcular la orientación externa de las cámaras. En la figura 4.15 se

muestra un ejemplo de los puntos de control utilizados. De estos puntos de control se

conocen las coordenadas 3D. Con estos datos se calcula los datos de orientación

externa, es decir, la rotación y traslación de las cámaras. Es importante indicar que el

sistema de coordenadas que se utiliza para medir los puntos de control (mediante el

93

<!-- p. 106 -->

\4. Experimentos

instrumental topográfico) es aquel respecto al que se tienen todos los puntos obtenidos

en la reconstrucción 3D.

Figura 4.15: Esquema de situación de los puntos de control (2008)

Por último, también se contó con otros datos, obtenidos con instrumental

topográfico, al igual que los puntos de control. En concreto, en las campañas de 2008 y

2009 se tomaron los perfiles marcados en la figura 4.20. Estos perfiles se han utilizado

para comprobar los resultados obtenidos en este capítulo de experimentos.

Con todos estos datos (imágenes, puntos de control, perfiles de comparación) se

calcularon las reconstrucciones tridimensionales de cada campaña siguiendo la

metodología propuesta.

Calibración interna

La metodología, por tanto, comienza con un primer bloque dedicado al cálculo de

los datos de las cámaras. En la primera fase de este bloque se realizaba una calibración

de los datos intrínsecos de la cámara. De esta fase se obtienen los datos de distancia

focal, punto principal y distorsiones radiales y tangenciales. En la tabla 4.2 se incluyen

un ejemplo de calibración de este tipo. En concreto son los datos que se obtuvieron de la

cámara Canon EOS 5D con el objetivo de 35 mm, y que se utilizaron durante los

experimentos.

94

<!-- p. 107 -->

\4. Experimentos

Cámara Canon EOS 5D con objetivo 35 mm

Formato teórico del CCD (x,y) 35.94x23.927 (mm)
Tamaño teórico del píxel (x,y) 8.228x8.217 (micras)
Formato real del CCD (x,y) 35.940x23.927 (mm)
Tamaño real del píxel (x,y) 8.228x8.217 (micras)
Distancia principal (mm) 102.390
xw (mm) 0.7698
yw (mm) -1.7387
Distorsión radial
K1 -2.21492881E-05
K2 -2.44968630E-08
K3 1.50604556E-11
Distorsión por descentramiento
P1 -1.91504749E-05
P2 0.00000000E+00

Tabla 4.2: Datos de calibración de la cámara Canon EOS 5D.

Figura 4.16: Gráfico de distorsión del objetivo 35 mm.

Orientación externa

Experimento I – Emparejamientos SIFT

Este primer experimento se realizó para comprobar que cantidad de

emparejamientos SIFT se obtienen en diferentes pares de imágenes. Se eligieron varios

pares de imágenes de forma aleatoria de entre las imágenes de la campaña de 2008. Para

cada imagen se obtuvieron sus descriptores SIFT y en cada par se buscaron los puntos

homólogos atendiendo a la similaridad de sus descriptores. De esta forma se obtuvieron

una serie de emparejamientos entre las imágenes del par. En la tabla 4.3 se incluyen los

resultados obtenidos.

95

<!-- p. 108 -->

\4. Experimentos

Par Descriptores SIFT en Descriptores SIFT en Emparejamientos
la imagen 1 la imagen 2 obtenidos
1-5 136.232 94.775 17.542
2-7 101.341 82.381 12.302
3-9 142.831 115.847 18.405
5-7 94.775 82.381 11.068

Tabla 4.3: Emparejamientos SIFT obtenidos en varios pares de imágenes de 2008

Además, en la figura 4.17 se representa una muestra de los emparejamientos para el

par 1-5. Entre las dos tomas había una separación de 31,96 metros. Se utilizó SIFT para

extraer los puntos clave con los que se trató de realizar los emparejamientos. Tal y como

se muestra en la tabla 4.3 se obtuvieron 136.232 puntos candidatos de la imagen 1 y

94.775 de la imagen 5. Se obtuvieron 17.542 puntos homólogos. Cada cruz azul de la

figura corresponde con un punto para el que se encontró otro homólogo en la otra

imagen del par. El contorno negro indica la zona donde se encuentra el glaciar rocoso.

Figura 4.17: Ejemplo de emparejamientos de SIFT (marcados con cruces azules) en un
par de imágenes del glaciar del Veleta (2008).

Se observa para cada par de imágenes un número de emparejamientos en torno a

los 15.000. Estos emparejamientos permiten calcular una primera superficie de la

escena, aunque de poca densidad de puntos 3D.

96

<!-- p. 109 -->

\4. Experimentos

Experimento II – Porcentaje de outliers con RANSAC

Del conjunto de emparejamientos obtenidos con SIFT hay que eliminar aquellos

que no cumplan la restricción epipolar. Para ello se calcula la matriz fundamental.

Aquellos emparejamientos que no cumplan esta restricción son eliminados. Para el

cálculo de la matriz fundamental se utilizó un método robusto como es RANSAC. Al

aplicarlo al conjunto de todos los emparejamientos éstos se dividen en inliers (aquellos

que están de acuerdo con el ajuste final) y outliers (aquellos que no lo están). En la tabla

4.4 se muestra el número de outliers y su porcentaje respecto al número total de

emparejamientos. El experimento se hizo para los mismos pares de imágenes que en el

experimento I.

Par Emparejamientos Nº de outliers Porcentaje de outliers
obtenidos
1-5 17.542 2 0,011 %
2-7 12.302 3 0,024 %
3-9 18.405 5 0,027 %
5-7 11.068 10 0,090 %

Tabla 4.4: Emparejamientos SIFT obtenidos en varios pares de imágenes de 2008

Se observa en la tabla como el porcentaje de outliers es muy bajo (siempre por

debajo del 1%). Esto lleva a dos conclusiones. Por un lado se puede considerar que

existe una homogeneidad en cuanto a los emparejamientos que nos proporciona el

método SIFT, ya que en un porcentaje muy alto los emparejamientos se ajustan

correctamente a la restricción epipolar (representada mediante la matriz fundamental).

Por otro lado se puede concluir que la utilización de este paso en la metodología no es

importante para este experimento.

Experimento III – Error de reproyección en la orientación externa

El cálculo de las cámaras se completa con la orientación externa. Esto es, una fase

donde se obtengan la traslación y rotación de las cámaras respecto del objeto a

cartografiar. Este proceso se realiza con un método de ajuste de rayos partiendo de un

conjunto de puntos 3D conocidos de la escena. Los puntos en este caso son los que se

han medido utilizando instrumental topográfico y geodésico. Son puntos que se pueden

97

<!-- p. 110 -->

\4. Experimentos

considerar de error casi despreciable (el error no es mayor de 3 cm), sobre los que

apoyar los cálculos. Además se pueden detectar de forma sencilla en las imágenes.

Por tanto, con las coordenadas 3D (X, Y, Z en metros) conocidas de estos puntos y

las coordenadas 2D (X, Y en píxel) de los mismos se realiza el proceso de ajuste. Lo

que se obtiene son los datos de traslación y rotación de cada una de las cámaras.

Figura 4.18: Orientación externa calculada. Posición de las cámaras respecto al
glaciar (2008).

Como prueba de la bondad de los datos obtenidos en el ajuste, se realizó un cálculo

del error de reproyección. Se proyectaron (utilizando las traslaciones y rotaciones

obtenidas) un conjunto de puntos 3D en las imágenes (distintos de los utilizados en el

ajuste), y se midió la distancia de estas proyecciones con sus coordenadas píxel reales.

La distancia que se obtiene nos da una buena idea de la calidad de la orientación externa

calculada. En la tabla 4.5, se incluye un ejemplo de este error de reproyección. En

concreto el que se obtuvo en la orientación externa con los datos de 2008.

98

<!-- p. 111 -->

\4. Experimentos

Medía (en pixels) respecto de los
puntos {E1, …, E9}
Cámara 1 0.687
Cámara 2 0.434
Cámara 3 0.535
Cámara 4 0.382
Cámara 5 0.529
Cámara 6 0.403
Cámara 7 0.449
Cámara 8 0.425
Cámara 9 0.631
Media de todas las cámaras (en 0.497
pixels)

Tabla 4.5: Error de reproyección (en píxels) tras la orientación externa (2008)

Obtención de una superficie previa

En el segundo bloque de la metodología se comienza a calcular información 3D de

la escena. Se obtiene una primera superficie 3D necesaria para el cálculo de los mapas

densos de profundidad. En este bloque juegan un papel esencial los emparejamientos

obtenidos con SIFT.

Con los datos conocidos en relación a las cámaras y mediante un proceso de

triangulación se obtiene un primer conjunto de puntos 3D, con poca densidad. Para cada

emparejamiento se obtiene un punto 3D. Por último, para que este conjunto de puntos

3D conformen una superficie tridimensional, se realiza una triangulación de Delaunay.

Experimento IV – Obtención de superficies TIN.

En este caso se ha utilizado la implementación que de este algoritmo se hace en el

software Matlab®. El resultado, por tanto, de este bloque en una superficie triangulada

o también denominada TIN (del inglés, triangular irregular network). En la figura 4.19

se incluye un ejemplo de las obtenidas para la campaña 2008.

99

<!-- p. 112 -->

\4. Experimentos

Figura 4.19: Ejemplo de TIN del glaciar del Veleta (2008)

Experimento V – Comparación del modelo con perfiles medidos con GPS

Para llegar a tener constancia de la precisión que tiene esta superficie triangulada se

utilizaron los perfiles tomados en campo con GPS. En concreto se contrastaron los datos

obtenidos a partir de las imágenes de 2008 (pares 1-5, 2-7, 3-9, 5-7) con los perfiles

medidos en GPS, que como ya se comentó tienen una precisión en torno a los 3 cm. En

la figura 4.20 se muestra un ejemplo de esta comparación. En el centro de la imagen

aparece el contorno del glaciar rocoso donde se indican los 5 perfiles utilizados, 4

transversales (A-B, C-D, E-F, G-H) y uno longitudinal en el frente del glaciar (I-J). En

cada representación de los perfiles se muestra el tomado con GPS (en color negro) y el

obtenido con la metodología propuesta (en color azul). Se pueden observar diferencias

en un intervalo de entre 10 y 15 cm.

100

<!-- p. 113 -->

\4. Experimentos

77.5

72.5
A 10 20 30 40 B
N
77.5 A
B

D
70.0 C 0 10 20 30 40
C 10 20 30 D F

75.0
E

67.5
H
E 10 20 30 F
I 70.5

70.0
G

62.5 J
G 10 20 30 H 57.5
I 10 J

Figura 4.20: Comparación con los 5 perfiles tomados con GPS (2008). En color negro
se representan los perfiles tomados con GPS y en azul los obtenidos con la metodología
propuesta

Se pueden observar diferencias en un intervalo de entre 10 y 15 cm. Por tanto, la

superficie obtenida tiene la suficiente precisión como para su uso como estimación de la

profundidad en la siguiente fase de la metodología

Mapas densos de profundidad

La reconstrucción final consiste en generar un conjunto de mapas densos de

profundidad. Las tomas con las que se cuentan en cada campaña se organizan en grupos

de 4 imágenes (una imagen de referencia y 3 imágenes vecinas). De cada grupo de 4

imágenes se obtiene un mapa denso de profundidad. En la figura 4.21 se muestran las

nueve tomas de 2008. La distancia máxima entre las tomas es de 150 m. En 2008 se

obtuvieron 4 mapas densos de profundidad (representados en rojo, azul, verde y

naranja). Se procuró elegir tomas contiguas (con una menor distancia entre ellas), por

sus mejores resultados en la correlación de imágenes. En la tabla 4.6 se indican que

tomas se utilizaron en cada mapa de profundidad.

101

<!-- p. 114 -->

\4. Experimentos

Figura 4.21: Partición de las nueve tomas en 4 mapas densos (2008)

Mapas Imágenes
Mapa 1 ● 1, 2, 3, 4
Mapa 2 ● 3, 4, 5, 6
Mapa 3 ● 5, 6, 7, 8
Mapa 4 ● 6, 7, 8, 9

Tabla 4.6: Imágenes utilizadas en cada uno de los mapas de profundidad calculados
(2008)

En el capítulo anterior se explicó el método para el cálculo de los mapas densos de

profundidad. A continuación se especifican algunos parámetros utilizados para la

reconstrucción 3D que se deben adaptar a esta escena donde se experimentó el método.

Entre estos parámetros están los siguientes:

\- ∆ depth : Incremento de profundidad. Es un parámetro muy importante puesto que

determina la resolución en la búsqueda de profundidad. Para este experimento se

utilizaron valores entre 10 cm y 1m (Goesele 2006).

\- thresh: Es el umbral que determina cuando un valor de NCC (Valor de

correlación cruzada normalizada), entre dos puntos, es válido o no. Los umbrales

que se utilizaron son los que se proponen en (Goesele 2006), entre 0,6 y 0,8.

\- k: Número de vecinos. Para el cálculo de un mapa denso de profundidad se ha de

elegir una imagen de referencia con un conjunto de imágenes vecinas con las

que calcular valores de correlación. Para los resultados que se han obtenido en el

glaciar del Veleta se utilizaron una imagen de referencia con 3 imágenes

vecinas.

102

<!-- p. 115 -->

\4. Experimentos

\- Superficie 3D previa. El método que se utiliza para calcular los mapas densos de

profundidad exige la elección de un intervalo donde buscar la profundidad

correcta para cada caso. Se entiende en este caso por profundidad a la distancia

entre la cámara y el objeto a cartografiar. En este experimento se partió de una

superficie 3D ya conocida. Se ha explicado en el apartado anterior su obtención.

Esta superficie 3D previa sirve de referencia en torno a la cual establecer el

intervalo para la búsqueda de los valores de profundidad. Se utilizó un rango de

20 metros alrededor de esta superficie. De esta forma se elige el intervalo de

búsqueda de profundidad relativo a esta superficie y no en términos absolutos.

De no utilizar esta superficie previa, se debería utilizar, según las pruebas

realizadas, un intervalo de entre 220 y 360 metros de profundidad. Estas cifras

tienen que ver con el rango de profundidades en las que podemos encontrar

puntos a reconstruir del glaciar. Al utilizar la superficie previa se reduce hasta

siete veces el coste computacional de la búsqueda de profundidad (se pasa de un

intervalo de 140 metros a tan sólo 20 metros).

\- 2 niveles de estructura piramidal. Para este ejemplo se eligieron dos niveles. El

primer nivel se eligió del doble de tamaño que el segundo. Como ya se explicó

en el capítulo anterior, el objeto de esta estructura piramidal es reducir también

el coste computacional del algoritmo. Se reduce a la mitad el número de píxeles

para los que se calcula un valor de profundidad.

Experimento VI – Puntos obtenidos para cada mapa de profundidad

Tras el uso del algoritmo con el conjunto de imágenes de una campaña se puede

obtener un mapa denso de profundidad por cada imagen. En principio si el proceso de

correlación fuera infalible, para cada píxel de la imagen se encontraría una profundidad

con un valor de correlación lo suficientemente alto, entonces con imágenes de

4368x2912 píxeles se deberían obtener 12.719.616 puntos 3D. Sin embargo, hay puntos

para los que no se puede encontrar la profundidad ya que el valor de correlación no es lo

suficientemente alto. En la tabla 4.7 se incluyen los resultados obtenidos sobre el área

de interés de la fotografía, no sobre todos los píxeles de la imagen. En este caso el área

de interés son los bloques que forman el glaciar rocoso.

103

<!-- p. 116 -->

\4. Experimentos

Mapas Puntos que forman el área Puntos para Porcentaje de puntos
de interés los que se válidos
calculó la
profundidad
Mapa 1 ● (2008 – 100mm) 5.760.000 5.225.472 90,72%
Mapa 2 ● (2008 – 100mm) 5.250.000 4.956.613 94,41%
Mapa 3 ● (2008 – 100mm) 5.400.000 5.068.121 93,85%
Mapa 4 ● (2008 – 100mm) 5.600.000 5.482.869 97,91%
Mapa 5 (2007 – 35mm) 980.000 780.000 79,59%

Tabla 4.7: Puntos obtenidos en cada mapa de profundidad.

Por tanto los mapas densos que se calcularon tenían una cantidad, por cada mapa

denso, de aproximadamente 800.000 puntos 3D para las imágenes tomadas con el

objetivo de 35 mm y 5.000.000 de puntos 3D para las imágenes tomadas con el objetivo

de 100 mm (por su mayor resolución). Además, la probabilidad de encontrar un valor

de profundidad en un determinado punto es muy alta, superior al 90% para los mapas de

profundidad calculados con imágenes del objetivo de 100mm y en torno al 80% para las

imágenes del objetivo de 35mm.

Experimento VII – Error de reproyección de los mapas de profundidad en los puntos de

control.

Por regla general es difícil hacer un cálculo cuantitativo del error de un modelo 3D

con esta densidad de puntos. Entre otras cosas porque no se dispone de un modelo real

con el mismo nivel de detalle con el que hacer la comparación. No obstante, sí que se

dispone de puntos medidos mediante instrumental topográfico, con los que es útil la

comprobación. Tomando 10 puntos que han sido medidos de esta forma (PT1, PT2,

PT3, …, PT10) y calculando el error de reproyección se obtiene una comprobación que

nos indica la calidad del modelo obtenido. Concretamente se tomó un mapa denso de

profundidad calculado con las imágenes y los datos de 2008. El error de reproyección se

obtuvo al aplicar el algoritmo de reconstrucción densa para cada uno de los 10 puntos.

Se midieron las distancias entre la situación real de los puntos (obtenidos proyectando

los puntos 3D en las imágenes mediante las matrices de las cámaras) y la situación de

los puntos mediante la situación de estos después de reproyectar, en las 4 imágenes con

las que se calcula el mapa denso. En la tabla 4.8 se incluyen los resultados de estas

medidas. Además se situó cada uno de esos 10 puntos (PT1, PT2,…, PT10) en el mapa

de profundidad, obteniendo su situación en coordenadas 3D. Calculando la distancia

104

<!-- p. 117 -->

\4. Experimentos

euclídea entre estas coordenadas 3D, calculadas en el mapa de profundidad y la

situación real de los puntos 3D, calculada mediante el instrumental topográfico, se

obtiene también un error de precisión en centímetros. En la tabla 4.9 se muestran estos

errores de precisión.

Img1 Img2 Img3 Img4 Media
(pixels)

PT 1 0,05 0,06 0,28 0,58
PT 2 0,05 0,03 0,10 0,22
PT 3 0,06 0,14 0,63 1,20
PT 4 0,01 0,01 0,03 0,07
PT 5 0,05 0,14 0,59 1,14
PT 6 0,08 0,26 1,08 1,20
PT 7 0,07 0,18 0,77 1,17
PT 8 0,08 0,09 0,42 0,85
PT 9 0,10 0,05 0,24 0,50
PT 10 0,02 0,01 0,05 0,10
Media 0,057 0,097 0,419 0,703 0.319

Tabla 4.8: Error de reproyección de puntos terreno en píxel (2008)

Puntos 3D Error (cm)
PT 1 27,23
PT 2 25,29
PT 3 24,68
PT 4 32,34
PT 5 35,82
PT 6 26,88
PT 7 39,02
PT 8 31,92
PT 9 32,65
PT 10 20,06
Media 29,59

Tabla 4.9: Error de reproyección de puntos terreno en cm (2008)

Se puede observar en la tabla 4.8 como el error máximo puede llegar a los 1,20

píxeles y el error medio se encuentra en torno a los 0,3 píxeles, un error bastante

aceptable. En la tabla 4.9 se puede analizar cómo este error en píxeles se traduce en

errores en torno a los 29,59 cm de media, con errores máximos de 39,02 cm.

Al finalizar esta fase final de la reconstrucción se cuenta con una serie de mapas

densos de profundidad, con gran cantidad de puntos. Con toda esta nube de puntos sólo

restan las tareas típicas de postproceso. En primer lugar, como ya se trató en el capítulo

de metodología, un proceso para unir todas las superficies 3D obtenidas, para que así el

105

<!-- p. 118 -->

\4. Experimentos

resultado sea un solo modelo de cada campaña. De este modelo final se podrán obtener

todo tipo de productos finales:

\- Perfiles.

\- Contornos.

\- Mapas de curva de nivel.

\- Ortofotos.

\- Etc.

Figura 4.22: Mapa de curvas de nivel del glaciar (2008)

Dense flow vectors (2007 – 2009)

La última fase de esta metodología es el cálculo del desplazamiento de bloques.

Como se dijo en el capítulo anterior, la técnica utilizada en esta propuesta son los dense

flow vectors. La técnica consta de dos fases. Una primera fase de emparejamiento de

imágenes de diferentes campañas (utilizando SIFT) y una segunda fase donde se asocian

esos emparejamientos a la información 3D de que se dispone. Ya se han calculado los

mapas densos de profundidad de este ejemplo (glaciar del Veleta), por tanto, si se

consiguen puntos homólogos entre imágenes de diferentes campañas y además,

imágenes de las que se ha calculado un mapa denso de profundidad, se pueden

conseguir los dense flow vectors, es decir, un conjunto de parejas de puntos 3D. Cada

106

<!-- p. 119 -->

\4. Experimentos

pareja representa la situación de un punto del glaciar en una primera campaña y su

situación en una campaña posterior.

Para el cálculo de los dense flow vectors se partió de las campañas de 2007 y 2009.

Como ya se ha indicado, en 2007 se contaba con imágenes tomadas con un objetivo de

35 mm y en 2009 con imágenes tomadas con objetivos de 35 y 100 mm (ambas

campañas con la cámara ya referida Canon EOS 5D).

Experimento VIII – Número de emparejamientos en pares 2007 – 2009

Como se explicó en el capítulo referente a la metodología, el primer paso consiste

en utilizar el método SIFT para obtener puntos homólogos entre la imagen seleccionada

del año 2007 y la imagen seleccionada del año 2009. Este experimento se realizó para

comprobar que cantidad de emparejamientos podemos encontrar entre las imágenes de

2007 y las de 2009 y que porcentaje de estos son correctos. La verificación de los

emparejamientos se realizó de forma visual con una muestra aleatoria de éstos (uno de

cada cuatro). Se comprobó si cada uno de ellos era correcto, es decir, si el punto

encontrado era el mismo en las dos imágenes del par. En la tabla 4.10 se muestran los

emparejamientos obtenidos, el número de elementos de la muestra aleatoria y el

porcentaje de resultados correctos para 4 pares de imágenes 2007-2009.

Pares 2007-2009 Nº emparejamientos Muestra Porcentaje emparejamientos correctos
[2-2007] – [6-2009] 413 103 90,80%
[1-2007] – [2-2009] 459 114 82,79%
[4-2007] – [2-2009] 352 88 90,91%
[6-2007] – [6-2009] 379 94 92,61%

Tabla 4.10: Emparejamientos obtenidos en pares de imágenes 2007-2009

En la figura 4.23 se puede observar un ejemplo de este tipo de emparejamientos.

Con cruces azules se representan los puntos homólogos encontrados y en color rojo se

indica el contorno del glaciar. En concreto para estas dos imágenes se encontraron 413

emparejamientos.

107

<!-- p. 120 -->

\4. Experimentos

Figura 4.23: Emparejamientos 2007-2009

A pesar del tiempo transcurrido entre las dos tomas y los cambios de iluminación y

escala producidos, se obtienen una buena cantidad de puntos homólogos. Además el

porcentaje de emparejamientos correctos es también suficientemente alto (entre el 80 y

el 90%). Por tanto, el emparejamiento con el método SIFT se puede considerar como

aceptable para la obtención de los vectores de flujo.

Una vez conseguidos los emparejamientos entre ambas campañas es el momento

de relacionar cada uno de ellos con la información 3D disponible (mapas densos de

profundidad de las dos imágenes). Por tanto se consiguieron parejas de puntos 3D. Cada

pareja consta de la situación de un punto del glaciar en 2007 y su situación en 2009.

Con estas parejas se pueden calcular, desplazamientos en altura (Z), es decir, cuanto ha

bajado un bloque del glaciar, o desplazamientos en el plano X-Y.

El problema es que entre las campañas 2007 y 2009 (las más extremas de que se

dispone) la información que se obtiene no es demasiado significativa. El

desplazamiento del glaciar medido entre 2007 y 2009 (mediante instrumental

topográfico) se sitúa en un intervalo de entre 15 y 20 cm (en el plano X-Y), y como ya

108

<!-- p. 121 -->

\4. Experimentos

se mencionó, el error de los modelos 3D obtenidos se sitúa en torno a los 30-40 cm. Por

tanto la información que se obtiene en este caso no es válida.

Sería necesario disponer de campañas posteriores a 2009 para que el

desplazamiento del glaciar sea superior al error registrado. Se ha explicado que desde

2009 no se ha podido medir en el glaciar del Veleta, ni en 2010 ni en 2011, puesto que

la nieve cubrió durante esos dos veranos toda su superficie. Es por esto que se adoptó la

decisión de simular esos mayores desplazamientos con la información de que se

dispone.

Lo que se ha hecho ha sido introducir en la campaña de 2009 un mayor

desplazamiento (ficticio) del que se obtuvo. Este desplazamiento añadido se estimó

teniendo en cuenta los desplazamientos observados en el glaciar en un período de 5 años

cualquiera. De esta forma se estima un posible modelo para 2012. En vez de calcular el

desplazamiento 2007-2009, se hizo para el posible desplazamiento 2007-2012. Para

comprobar los resultados para este posible desplazamiento se han realizado dos

experimentos. Por un lado se han estudiado las posibilidades de SIFT para el

emparejamiento entre campañas con una diferencia mayor de los 2 años, en concreto

entre imágenes de 2003 y 2009. Por el otro se ha calculado el modelo ficticio de 2012

con el fin de observar que resultados se obtienen con desplazamientos suficientes.

Emparejamiento entre campañas (2003 – 2009)

Experimento IX – Emparejamientos obtenidos en pares 2003 – 2009

Este experimento pretende averiguar qué resultados se obtienen al utilizar el

método SIFT con imágenes de un periodo mayor de 5 años. Se ha explicado que se

dispuso únicamente de las campañas 2007, 2008 y 2009, tomadas con la cámara Canon

EOS 5D, sin embargo también se dijo que se contaba con las campañas 2003 y 2005

tomadas con la cámara analógica Rollei. Las pruebas realizadas consisten en utilizar las

imágenes tomadas con cámara analógica en 2003 y las tomadas con la cámara digital en

\2009. El objetivo es comprobar como funciona el método SIFT cuando se emparejan

imágenes con una distancia mayor en el tiempo (en este caso seis años). Se han elegido

3 pares de imágenes 2003-2009. Para cada uno de ellos se han buscado sus puntos

homólogos con SIFT. Además, se ha elegido un muestreo de éstos para comprobar

109

<!-- p. 122 -->

\4. Experimentos

cuántos se pueden considerar correctos. En la tabla 4.11 se muestra toda esta

información.

Pares 2003-2009 Nº emparejamientos Muestra Porcentaje emparejamientos correctos
[2-2003] – [6-2009] 526 105 71,43%
[3-2003] – [6-2009] 613 122 77,86%
[5-2003] – [6-2009] 575 115 60,87%

Tabla 4.11: Emparejamientos obtenidos en pares de imágenes 2003-2009

En la figura 4.24 se muestra un ejemplo de estos emparejamientos. La primera

imagen es de la campaña de 2003 y la segunda de la de 2009. Las cruces azules

representan puntos homólogos entre las dos imágenes. En color rojo se resalta el

contorno del glaciar rocoso.

110

<!-- p. 123 -->

\4. Experimentos

Figura 4.24: Emparejamiento entre imágenes de 2003 y 2009.

Los resultados fueron bastante aceptables. Se han obtenido gran cantidad de

puntos homólogos y buenos porcentajes de acierto, evidentemente inferiores a los pares

de imágenes con tan sólo 2 años de diferencia (2007-2009).

Dense flow vectors (2007 – 2012)

Experimento X – Vectores de flujo utilizando un modelo ficticio de 2012

Con el experimento anterior se ha mostrado el resultado de emparejar puntos en

períodos de más de 5 años, en concreto entre 2003 y 2009. En este experimento la idea

es crear un modelo de una posible campaña de 2012, para así comprobar que resultados

se obtendrían cuando se tratan de medir desplazamientos mayores.

En primer lugar, lo que se obtuvo fue una estimación del desplazamiento del

glaciar en un período cualquiera de 5 años. Para ello se utilizaron los desplazamientos

medidos mediante técnicas topográficas. Se seleccionó un periodo cualquiera de 5 años

(2004-2009 por ejemplo) y se estableció un desplazamiento medio en cada una de las

coordenadas (X, Y, Z). Estos desplazamientos fueron los que se añadieron a los puntos

de control de 2007. De esta forma se obtienen los posibles puntos de control de 2012. Si

se parte de los puntos de control estimados para 2012, todo lo que se obtiene después

(orientación externa, obtención de la superficie previa y obtención de los mapas densos

de profundidad) forma esa posible campaña de 2012.

Por último se realizó el mismo proceso de cálculo de los vectores de flujo, tal y

como se explicó para 2007-2009. Sin embargo, en este caso el desplazamiento es mayor

111

<!-- p. 124 -->

\4. Experimentos

del posible error de la reconstrucción 3D y por tanto los desplazamientos se pueden

considerar fiables. En la figura 4.25 se ha representado una muestra aleatoria de los

vectores de flujo obtenidos (2007-2012). En color rojo se representa el contorno del

glaciar. Cada uno de los dense flow vectors se representa por un punto donde comenzó

el desplazamiento, y un segmento que indica cuanto se desplazó, con un factor 10 para

“exagerar” ese desplazamiento y observarlo mejor.

N 25 meters

Front of rock glacier

Figura 4.25: Posibles desplazamientos 2007-2012

El resultado es un conjunto de vectores de desplazamiento que nos indican de

forma gráfica cómo ha evolucionado la superficie del glaciar rocoso. Los vectores de Vectors of movement: Factor 10flujo obtenidos son consistentes con las medidas topográficas realizadas. 1 meter

4.2.2. Helero del Jou Negro (2007).

Aunque el principal escenario para los experimentos ha sido el glaciar del Veleta

en Sierra Nevada, también se ha incluido este segundo escenario del Jou Negro a modo

complementario. El Jou Negro es un circo glaciokárstico situado en el noroeste del
Macizo Central, en la cara norte de Torre Cerredo, la cumbre más alta de la Cordillera
Cantábrica. El circo de Jou Negro estuvo ocupado durante la PEH (Pequeña edad del

hielo) por un glaciar de 52 hectáreas (fácilmente reconstruido a partir de la morrena

terminal bien conservada) (González 2007 y González et al. 2008). Actualmente, el

antiguo glaciar se ha reducido a un resto de hielo glaciar o helero, parcialmente cubierto

112

<!-- p. 125 -->

\4. Experimentos

de clastos y sin movimiento por deformación de su masa. Este helero continúa en

regresión, después de haber perdido alrededor del 65% de la superficie del glaciar de la

PEH y haber disminuido de modo considerable su volumen (González 2006 y González

et al. 2008).

Desde el año 2007 hasta la actualidad, se han recabado los siguientes datos

geomáticos del helero del Jou Negro (figura 4.26):

\- Año 2007: Perímetro del helero, dos perfiles transversales, diez puntos de apoyo

para fotogrametría (once fotografías) y cuatro perfiles geofísicos.

\- Año 2008: Perímetro del helero, dos perfiles transversales, un perfil longitudinal

y cuatro perfiles geofísicos.

\- Año 2009: No hay datos (la nieve invernal no desapareció).

0 m 50 m 100 m 150 m
0 m 50 m 100 m 150 m
North North
8 9 3 Photography Front 2 410 Front FiguraPerimeter4.26: Datos geomáticos111 (2007-2008) en Perimeterel Jou Negro. Geophysical profiles 5 Geophysical profiles Los experimentos que se han6 realizadoPhotography en el helero del Jou NegroGeophysical(De Matíasprofiles et al. Topographic profile Topographic profile 72010b,Control2010c,point SanjoséGeophysicalet al.profiles2010) únicamente se centran en lasTopographicdos primeraslongitudinalfasesprofilede la Control pointmetodología de este Topographictrabajo. profileNo se han calculado mapas densos Topographicde profundidadprofile ni se Top Top Perimeter Perimeterhan estudiado los desplazamientos de bloques en las distintas campañas.

Para estos experimentos se cuenta con 11 fotografías tomadas durante la campaña

de 2007 desde distintos puntos de vista a lo largo de la morrena del helero, y con

ángulos convergente respecto a la zona a cartografiar. Las distancias entre las tomas se

encontraban en un intervalo de entre 10 m y 50 m. Se utilizó una cámara digital (el

modelo ya mencionado Canon EOS 5D con una focal fija de 35 mm) para la toma de

fotografías y una estación total (la también mencionada Topcon GTS-502E) para la

medición de 10 puntos de control y otra serie de puntos (perfiles) que fueron útiles para

comparar los modelos obtenidos.

113

<!-- p. 126 -->

\4. Experimentos

0 m 50 m 100 m 150 m Front
NorthNorth
Perimeter

10 meters 8 9 3 2 10 Top 4 1 11 5 Control point 6
Figura 4.27: Situación de las cámaras, puntos obtenidos y puntos de control en el 7
Jou Negro.

En este experimento sólo se realizó el primer bloque de cálculo de las cámaras, tal

y como se explicó para el glaciar del Veleta (calibración interna, orientación externa

mediante marcas instaladas en el terreno), y el segundo bloque de obtención de la

superficie previa. Utilizando SIFT se obtuvieron alrededor de 3000 emparejamientos

por cada par de imágenes, que tal y como se ha observado, supone prácticamente la

misma cantidad de puntos 3D (tras el proceso de triangulación). En la figura 4.27 se

muestra un ejemplo de la densidad de los puntos obtenidos para un par de imágenes, así

como el contorno del helero, y la situación de las tomas de las imágenes y los puntos de

control.

En este experimento, los modelos obtenidos se utilizaron para comparar el modelo

digital obtenido (2007) con perfiles tomados mediante instrumental topográfico un año

después (2008). En la figura 4.28 se muestran tres ejemplos de estas comparaciones. En

cada caso se muestra el contorno del helero, las curvas de nivel obtenidas a partir del

modelo 3D, los dos perfiles marcados a lo largo y ancho del helero, y de las tomas

fotográficas se indica cuales fueron utilizadas (en color verde las que se utilizaron y en

rosa el resto). Además en la esquina superior izquierda y en la inferior derecha se

muestran las comparaciones del modelo obtenido (verde) con el que se midió en campo

(azul) mediante instrumental topográfico un año después. Estas comparaciones se

utilizaron para observar la evolución del helero desde el verano de 2007 hasta el de

\2008.

114

<!-- p. 127 -->

\4. Experimentos

Front
Perimeter 2270.0 8 9 3 2255.0 2 10 4 2245.0 2008 0 50 57.91 1 Top 11 5 Control point 6 57.91 7
Front 2267.50 Perimeter 2262.50 2007 0 50 72.84 2270.0 8 9 3 2255.0 2 10 2245.0 2008 4 0 50 57.91 1 Top 11 5 Control point 6 7
Front 2267.50 Perimeter 2262.50 2007 0 50 72.84 2270.0 8 9 3 2255.0 2 10 2245.0 2008 4 0 50 57.91 1 Top 11 5 Control point 6 57.91Figura 4.28: Comparación modelo obtenido (2007) con7 perfil longitudinal y transversal
(2008) 2267.50 2262.500 50 72.842007 115

<!-- p. 128 -->

\4. Experimentos

Aunque las comparaciones de la figura 4.28 son para modelos de un solo par de

imágenes se puede obtener un modelo final. Éste se obtiene uniendo los diversos

modelos de cada par de imágenes, resultando un conjunto de alrededor de 45.000 puntos

en coordenadas tridimensionales.

116

<!-- p. 129 -->

Capítulo 5: Conclusiones.

<!-- p. 130 -->

\5. Conclusiones

118

<!-- p. 131 -->

\5. Conclusiones

\5. Conclusiones

El objetivo principal de esta tesis ha sido establecer una metodología automática

que permita obtener modelos tridimensionales precisos y con gran cantidad de

información de estructuras geomorfológicas dinámicas. Este objetivo general se puede

considerar alcanzado satisfactoriamente (De Matías et al. 2009a, De Matías et al. 2009b,

De Matías et al. 2010a, De Matías et al. 2010b, De Matías et al. 2010c). En el capítulo

anterior, se han revisado los experimentos realizados con la metodología propuesta y los

resultados obtenidos. Se ha explicado la utilización de la metodología en las diferentes

zonas de estudio y como los modelos obtenidos aportan suficiente cantidad de

información.

Aunque este objetivo general se puede considerar satisfactoriamente alcanzado, hay

que tener en cuenta que objetivos específicos de los que se establecieron en el capítulo

de introducción se han alcanzado y en que grado.

Habría que empezar por la necesidad de aunar técnicas fotogramétricas y de visión

por computador. Esta necesidad se traduce en tres objetivos concretos. El primero de

ellos consiste en la simplificación del flujo de trabajo que en la actualidad se utiliza en

proyectos fotogramétricos. En el capítulo 2 se ha expuesto la forma que tiene la

fotogrametría de afrontar la reconstrucción tridimensional de una escena y de qué fases

consta. Por otro lado, se expusieron los avances producidos en el ámbito de la visión por

computador y el conjunto de técnicas que facilitan la propuesta realizada en este trabajo

(geometría epipolar, nuevos métodos para el emparejamiento de imágenes, métodos de

emparejamiento denso). La metodología que se ha propuesto ha intentado aunar ambas

facetas consiguiendo un flujo de trabajo más sencillo para los usuarios de esta

tecnología, eliminando o aligerando algunas de las fases del método fotogramétrico

clásico. El segundo de estos objetivos consiste en aumentar la automatización del

proceso fotogramétrico. Debido al uso de técnicas del ámbito de la visión por

computador se ha conseguido una metodología totalmente automática, expandiendo su

uso a un mayor número de perfiles de usuario. Por último, en tercer lugar se encuentra

el objetivo de reducir el tiempo de trabajo en un proyecto fotogramétrico como los que

en esta tesis se exponen. Los dos anteriores objetivos conllevan la consecución de este

tercero. Gracias a la simplificación del flujo de trabajo y a la obtención de una

119

<!-- p. 132 -->

\5. Conclusiones

metodología automática el tiempo de trabajo dedicado a un proyecto se reduce en gran

medida.

En segundo lugar, se encontraba un objetivo puramente técnico, consistente en

proponer un método que permita obtener una reconstrucción con una gran densidad de

puntos y con datos de precisión aceptables. En el apartado 2.4 se han presentado los

aspectos principales que caracterizan a los métodos de emparejamiento denso, así como

las diferentes propuestas aparecidas en la literatura en los últimos años. Se seleccionó la

más idónea para su aplicación en la reconstrucción de estructuras geomorfológicas

dinámicas. Además, se indicaron en el capítulo 3 algunas adaptaciones que mejoraban

los resultados obtenidos. El resultado es la obtención de mapas densos de profundidad

con gran densidad de puntos (de hasta 5.000.000 de puntos 3D en algunos mapas, ver

experimento VI) y con suficiente precisión (ver experimento VII).

En tercer lugar, se encontraba el objetivo de relacionar los modelos

tridimensionales obtenidos en una campaña con los de otra para ver los desplazamientos

de los distintos bloques del modelo. Para ello se han propuesto los vectores densos de

flujo. Su misión en la metodología es el poder relacionar puntos 3D obtenidos en un año

con otro punto 3D obtenido en otro anterior, utilizando emparejamiento de imágenes

con SIFT. Las dudas que surgían al proponer esta técnica estaban en torno a dos

cuestiones. Primero si sería posible encontrar puntos comunes entre imágenes tomadas

en diferentes campañas (por ejemplo con 4 o 5 años de diferencia). En el capítulo

anterior se ha demostrado como SIFT da un buen rendimiento en esta tarea. Se han

emparejado imágenes con una diferencia de hasta 6 años (2003-2009), con un buen

número de emparejamientos y de porcentaje de resultados correctos (en torno a 500

emparejamientos y tasas de acierto del 70%, ver experimento IX). La otra cuestión era si

sería posible obtener información 3D de esos emparejamientos “entre campañas”. Se

mostró también como esto era posible. El problema con los vectores densos de flujo

proviene de los pocos datos con los que se contaba para evaluar su precisión. Se intentó

verificar obteniendo la relación de las campañas de 2007 y de 2009 (ver experimento

VIII). Sin embargo, el error que acumulan los mapas densos de profundidad es mayor

que el desplazamiento del glaciar rocoso en ese tiempo. En su lugar, se trató de

comparar el modelo de 2007 con un hipotético modelo de 2012, que tenía un

desplazamiento suficiente, mostrando cómo se puede obtener el desplazamiento de los

distintos bloques del glaciar rocoso (ver experimento X).

120

<!-- p. 133 -->

\5. Conclusiones

Por último, existía un objetivo relativo al campo de aplicación elegido para esta

tesis doctoral. Existe un interés creciente en el estudio de los fenómenos de glaciarismo

(en este caso glaciares rocosos y heleros) por su relación con los efectos del “cambio

climático”. En el apartado 2.5 se ha hecho un repaso por los trabajos que tienen un

objetivo similar a éste y cómo ha evolucionado su estudio con el desarrollo de nuevas

técnicas. En el capítulo de experimentos se muestran dos ejemplos de la aplicación de

esta metodología en proyectos geomorfológicos. Por un lado se habla del proyecto de

monitorización del glaciar rocoso del Veleta en Sierra Nevada. La utilización de esta

metodología va a permitir un avance en los resultados requeridos para este proyecto. La

obtención de cartografías de gran nivel de detalle (a partir de los mapas densos de

profundidad), así como las técnicas para el estudio del desplazamiento de bloques,

ayudarán a mejorar las técnicas habitualmente utilizadas en este tipo de proyectos. Por

otro lado se ha mostrado la aplicación de la metodología en el helero del Jou Negro en

la Cordillera Cantábrica. Dentro de este proyecto se midió el desplazamiento del helero

entre las campañas de 2007 y de 2008 combinando técnicas topográficas (en la campaña

de 2007) y la metodología propuesta (en la campaña de 2008) con buenos resultados.

Es evidente que la metodología propuesta tiene aún algunos aspectos de mejora.

Éstos se convierten, al finalizar esta tesis doctoral, en futuras posibles líneas de trabajo.

El primer aspecto con posibilidades de mejora es el de la precisión. Para ello se

pueden abrir dos frentes. Por un lado intentar reducir el error de las diferentes fases de

la metodología (orientación externa, cálculo de los mapas densos de profundidad,…) y

en segundo lugar aumentar la resolución de las imágenes. Una mayor resolución en las

imágenes permitirá reducir el error cometido en distancia, manteniendo el error relativo

al píxel en las mismas cifras.

Finalmente será interesante ampliar los experimentos realizados. Por ejemplo, en el

glaciar del Veleta sería interesante contar con más campañas. Como se explicó en el

capítulo de experimentos sólo se tuvieron las campañas de 2007 a 2009, puesto que no

fue posible tomar imágenes de la superficie del glaciar ni en 2010 ni en 2011. Cuando

se pueda contar con dos campañas con desplazamientos suficientemente grandes se

sacará un mejor partido a la técnica de los vectores densos de flujo para el seguimiento

de los distintos bloques del glaciar. En el otro escenario, el helero del Jou Negro,

también aportará mejores conclusiones, contando con alguna campaña más.

121

<!-- p. 134 -->

\5. Conclusiones

Otra futura línea de trabajo es la aplicación de esta metodología a nuevos proyectos

geomorfológicos. Entre las posibilidades que se han contemplado se encuentra la de

buscar nuevos escenarios de aplicación. Existe una estrecha relación entre el grupo de

investigación IGPU de la Universidad de Extremadura y el profesor Viktor Kaufmann

de la Universidad Técnica de Graz. El profesor Kaufmann, junto con otros

investigadores, ha desarrollado técnicas para la monitorización de glaciares rocosos en

los Alpes austríacos. Por ello, será interesante probar esta metodología con los datos

obtenidos en los glaciares que ya se han estudiado por los investigadores austríacos.

122

<!-- p. 135 -->

Anexos

<!-- p. 136 -->

124

<!-- p. 137 -->

Anexo I: Referencias bibliográficas.

<!-- p. 138 -->

Anexo I: Referencias bibliográficas

126

<!-- p. 139 -->

Anexo I: Referencias bibliográficas

Bibliografía

P. Bachiller, P. Bustos y L.J. Manso. Attentional Selection for Action in Mobile Robots.
Advances in Robotics, Automation and Control, ISBN 978-953-7619-16-9, 2008.

E.P. Baltsavias. Multi-Photo geometrically constrained matching. PhD Thesis, Institute
of Geodesy and Photogrammetry, ETH Zurich, Switzerland, 1991.

A. Baumberg. Reliable feature matching accross widely separate views. International
Conference on Computer Vision and Pattern Recognition, Hilton Head, South Carolina,
pp 774-781, 2000.

H. Bay, T. Tuytelaars y L. Van Gool. SURF: Speeded Up Robust Features. European
Conference on Computer Vision (ECCV06), 2006.

M. Bern y D. Eppstein. Mesh generation and optimal triangulation. Computing in
Euclidean Geomeetry, pp 23-90, 1992.

A.F. Bobick y S.S. Intille. Large Occlusion Stereo. International Journal of Computer
Vision, 33(3), pp 181-200, 1999.

T. Bonfort y P. Sturm. Voxel carving for specular surfaces. International Conference on
Computer Vision, pp. 591-596, 2003.

M. Brown y D.G. Lowe. Invariant features from interest point groups. International
British Machine Vision Conference, Cardiff, Wales, pp 656-665, 2002.

F. Buill, M.A. Núñez y J.J. Rodríguez. Fotogrametría analítica. Ediciones UPC, 2003.

J.F. Canny. A computational approach to edge detection. IEEE Transaction on Pattern
Analysis and Machine Intelligence, 8(6), pp 34-43, 1986.

O. Chum, J. Matas y J. Kittler. Locally optimized RANSAC. German Pattern
Recognition Symposium, pp 236-242, 2003.

O. Chum y J. Matas. Matching with PROSAC: Progressive sample consensus.
Computer Vision and Pattern Recognition, pp 220-226, 2005.

I.J. Cox, S.L. Hingorani, S.B. Rao, B.M. Maggs. A maximum likelihood stereo
algorithm. Computer Vision and Image Understanding, 63(3), pp 542-567, 1996.

J.L. Crowley y A.C. Parker. A representation for shape based on peaks and ridges in
the difference of low-pass transform. IEEE Transaction on Pattern Analysis and
Machine Intelligence, 6(2), pp 156-170, 1984.

B. Curless y M. Levoy. A volumetric method for building complex models from range
images. Int. SIGGRAPH, pp 303-312, 1996.

O. Faugeras y Q.T. Luong. The geometry of Multiple Images. MIT Press, 2001.

127

<!-- p. 140 -->

Anexo I: Referencias bibliográficas

S. Finsterwalder. Zur photogrammetrischen Praxis. Zeitschrift für Vermessungswesen
25(8), 225-240, 1986.

M. Fischler y R. Bolles. RANdom Sampling Consensus: a paradigm for model fitting
with application to image analysis and automated cartography. Commun. Assoc.
Comp. Mach., 24(6), pp 381-95, 1981.

W. Foerstner. A feature based correspondence algorithm for image matching.
International Archives of Photogrammetry, 26(3), 1986.

Y. Furukawa y J. Ponce. High-fidelity image-based modeling. Technical Report 200602, UIUC, 2006.

P. Gargallo y P. Sturm. Bayesian 3D Modeling from Images using Multiple Depth
Maps. IEEE Computer Vision and Pattern Recognition, 2, pp. 885-891, 2006.

M. Goesele, B. Curless y S. Seitz. Multi-view stereo revisited. IEEE Computer Vision
and Pattern Recognition, 2, pp. 2402-2409, 2006.

A. Gómez, D. Palacios, M. Ramos y L. Schulte. Location of Permafrost in Marginal
Regions: Corral del Veleta, Sierra Nevada, Spain. Permafrost and Periglacial Processes,
12, pp 93-110, 2001.

A. Gómez Ortiz (Coordinador). Geomorphological Map of Sierra nevada. Glacial and
periglacial Geomorphology. Granada: Junta de Andalucia, Consejería de Medio
Ambiente, 2002.

A. Gómez Ortiz, F. Salvador Franch, J.J Sanjosé Blasco, D. Palacios Estremera, L.
Schulte, A. Atkinson Gordo. Evolución morfodinámica de un enclave montañoso recién
deglaciado: el caso del Corral del Veleta (Sierra Nevada), ¿consecuencia del Cambio
Climático?. Scripta Nova. Revista Electrónica de Geografía y Ciencias Sociales.
Barcelona: Universidad de Barcelona, XII 270 (26), 2008.

A. Gómez Ortiz, D. Palacios Estremera, F. Salvador Franch, JJ. Sanjosé Blasco, M.
Oliva Franganillo, M. Salvà Catarineu, A. Atkinson Gordo, J. Galindo Zaldivar, C. Sanz
de Galdeano, LM. Tanarro, LM. & L. González Castillo. Respuesta de una montaña
mediterránea al Cambio Global (Sierra Nevada, España): el proceso degradativo de
masas heladas glaciares relictas y permafrost. Regional Geographic Conference UGI.
Santiago de Chile. Chile (en prensa), 2011.

J.J. González Trueba. Topoclimatical factors and very small glaciers in Atlantic
Mountain of SW Europe: The Little Ice Age glacier advance in Picos de Europa (NW
Spain). Zeitschrift für Gletscherkunde und Glazialgeologie, 39, 115-125, 2006.

J.J. González Trueba. Pequeña Edad del Hielo en los Picos de Europa. Universidad de
Cantabria, Santander, 2007.

J.J. González Trueba, R. Martín Moreno, E. Martínez de Pisón, E. Serrano. Little Ice
Age glacier advance and current glaciers in the Iberian Peninsula. The Holocene, 18,
551-568, 2008.

128

<!-- p. 141 -->

Anexo I: Referencias bibliográficas

L. Goshen y I. Shimshoni. Balanced Exploration and Exploitation Model Search for
Efficient Epipolar Geometry Estimation. European Conference on Computer Vision
(ECCV06), 2006.

W. Gruber y H. Slupetzky (2002). Remapping of the Cathedral Massif Glacier (B.C.,
Canada) – from tradicional mapping to digital techniques. 2nd ICA Mountain
Cartography Workshop, Mt. Hood, Oreon, USA, 2002.

A. Gruen y T.S. Huang. Calibration and Orientation for Cameras in Computer Vision.
(Eds.). Springer, 2001.

H. Haggrén, C. Mayer, M. Nuikka, L. Braun, H. Rentsch y J. Peipe. Processing of old
terrestrial photography for verifying the 1907 digital elevation model of Hochjockferner
glacier. Zeitschrift für Gletsckerkunde und Glazialgeologie, 41, pp 29-53, 2007.

C. Harris y M. Stephens. A combined corner and edge detector. Fourth Alvey Vision
Conference, pp 147-151, 1988.

R. Hartley. In defense of the eight-point algorithm. IEEE Transaction on Pattern
Analysis and Machine Intelligence, 19(6), pp 580-593, 1997.

R. Hartley y A. Zisserman. Multiple View Geometry in Computer Vision, 2nd Edition.
Cambridge University Press, 2003.

P. Hough. Method and Means for Recognizing Complex Pattern. U.S. Patent 3.069.654,
\1962.

A. Kääb, W. Haeberli y G.H. Gudmundsson. Analysing the creep of mountain
permafrost using high precision aerial photogrammetry. 25 years of monitoring Gruben
rock glacier. Swiss Alps. Permafrost and Periglacial Processes, 8, pp 409-426, 1997.

A. Kääb y C. Kneisel. Permafrost creep within a recently deglaciated glacier forefield:
Muragl, Swiss Alps. Permafrost and Periglacial Processes, 17, pp 79-85, 2006.

V. Kaufmann y H. Ploesch. Mapping and visualization of the retreat of two cirque
glaciers in the Austrian Hohe Tauern National Park. XIX ISPRS Congress
International Archives of Photogrammetry and Remote Sensing, Amsterdam, The
Nederlands, Vol. XXXIII, Part B4, pp 446-453, 2000.

V. Kaufmann y R. Ladstädter. Monitoring of active rock glaciers by means of digital
photogrammetry. Proceedings of the ISPRS Commission III Symposium
"Photogrammetric Computer Vision" Graz, Austria, IAPRS, 34, Part 3B, pp 108-111,
\2002.

V. Kaufmann y R. Landstädter. Documentation of the retreat of small debris-covered
cirque glacier (Goessnitzkees, Austrian Alps) by means of terrestrial photogrammetry.
4th ICA Mountain Cartography Workshop, Vall de Nuria, Spain, 2004a.

V. Kaufmann y R. Ladstädter. Change detection of a mountain slope by means of
ground-based photogrammetry: A case study in the Austrian Alps. 4th ICA Mountain
Cartography Workshop, Vall de Nuria, Spain, 2004b.

129

<!-- p. 142 -->

Anexo I: Referencias bibliográficas

V. Kaufmann, R. Ladstädter y G. Kienast. 10 Years of monitoring of the Doesen rock
glacier (Ankogel group, Austria) – A review of the research activities for the time
period 1995-2005. 5th ICA Mountain Cartography Workshop, Bohinj, Slovenia, 2006.

L.W. Kenyi y V. Kaufmann. Estimation of rock glacier surface deformation using SAR
interferometry data. IEEE Transactions on Geoscience and Remote Sensing, 41, 15121515, 2003.

S. Lazebnik, C. Smith y J. Ponce. Semi-local affine parts for object recognition.
Proceedings of the British Machine Vision, 2004.

J.L. Lerma. Fotogrametría moderna: analítica y digital. Editorial UPV, 2002.

K. Levenberg. A Method for the Solution of Certain Non-Linear Problems in Least
Squares. Quarterly of Applied Mathematics 2, 164–168, 1944

T. Lindeberg. Detecting salient blob-like image structures and their sacles with a scalespace primal sketch: a method for focus – of – attention. International Journal of
Computer Vision, 11(3), pp 283-318, 1993.

T. Lindeberg. Scale-space theory: A Basic tool for analysing structures ad different
scales. Journal of Applied Statistics, 21(2), pp 224-270, 1994.

G. López, J.J. Guerrero y J.J. de Sanjosé. Automatic photogrammetry for the production
of geomorphologic cartography. 6th International Conference on Geomorphology,
Zaragoza, 2006.

M. Lourakis y A. Argyros. The Design and Implementation of a Generic Sparse Bundle
Adjustment Software Package Based on the Levenberg-Marquardt Algorithm. Institute
of Computer Science – FORTH, Technical Report FORTH-ICS TR-340-2004, 2004.

M. Lourakis y A. Argyors. Is Levenberg-Marquardt the most efficient optimization
algorithm for implementing Bundle Adjustment. IEEE International Conference on
Computer Vision, 2, pp 1526-1531, 2005.

M. Lourakis y A. Argyros. SBA: A Software Package for Generic Sparse Bundle
Adjustment. ACM Transactions on Mathematical Software, 36 (1), pp 1–30, 2009.

D. Lowe. Object recognition from local scale-invariant features. International
Conference on Computer Vision, pp 1150-1157, 1999.

D. Lowe. Distinctive Image Features from Scale-Invariant Features. International
Journal of Computer Vision, 60(2), pp 91-110, 2004.

Q.T. Luong, R. Deriche, O. Faugeras y T. Papadopoulo. On determining the
fundamental matrix: analysis of different methods and experimental results. Technical
Report 1894, INRIA, 1993.

D. Marr, T. Poggio. Cooperative Computation of Stereo Disparity. Science, 194, pp
209-236, 1976.

130

<!-- p. 143 -->

Anexo I: Referencias bibliográficas

D. Marr y T. Poggio. A computational theory of human stereo vision. Proc. Royal Soc.
London B, 204, pp 301-328, 1979.

J. de Matías, J. Moreno y J.J. Guerrero. Automatización de trabajos fotogramétricos
mediante técnicas de Visión Artificial. Congreso Internacional de Matemáticas en la
Arquitectura y la Ingeniería, 2007a.

J. de Matías Bejarano, J. Moreno del Pozo y JJ. Guerrero Campo. Automatización de
trabajos fotogramétricos mediante técnicas de visión artificial. Topografía y
Cartografía, XXIV nº173, 10-15, 2007b.

J. de Matías, JJ. de Sanjosé, G. López-Nicolás, C. Sagües y JJ. Guerrero
Photogrammetric Methodology for the Production of Geomorphologic Maps:
Application to the Veleta Rock Glacier (Sierra Nevada, Granada, Spain). Remote
Sensing, 1, 829-841, 2009a.

J. de Matías Bejarano, J. Moreno del Pozo y JJ. Guerrero Campo. A multi-view dense
reconstruction for rock glacier modelling. 15th International Conference on Virtual
Systems and Multimedia, 2009b.

J. de Matías, J. J. Guerrero, J. Moreno y J.J. de Sanjosé. Image measurement techniques
in rock glaciar modelling. International Archives of Photogrammetry, Remote Sensing
and Spatial Information Sciences, 2010a.

J. de Matías Bejarano, F. Berenguer Sempere, JJ. de Sanjosé Blasco. Automatic close–
range photogrammetry to Digital Terrain Model in ice patch Jou Negro (Picos de
Europa-Spain). 7th ICA Mountain Cartography Workshop on “Mountain mapping and
geospatial information retrieval”, 2010b.

J. de Matías Bejarano, F. Berenguer Sempere, JJ. de Sanjosé Blasco. Automatic closerange photogrammetry to Digital Terrain Model in Ice Patch Jou Negro (Picos de
Europa – Spain). Geographia Technica. Special issue, 6-11, 2010c.

J.C. McGlone. Manual of photogrammetry 5th edition. American Society for
Photogrammetry and Remote Sensing, 2004.

B. Messerli. Beiträge zur Geomorphologie der Sierra Nevad (Andalusien). Juris Verlag.
Zürich, 1965.

E.M. Mikhail, J.S. Bethel y J.C. McGlone. Introduction to Modern Photogrammetry.
Ed. John Wiley: New York, NY, USA, 2001.

K. Mikolajczyk y C. Schmid. An affine invariant interest point detector. Europena
Conference on Computer Vision (ECCV), Copenaghe, Denmark, pp 128-142, 2002.

K, Mikolajczyk y C. Schmid. A Performance Evaluation of Local Descriptors.
Proceedings of the IEEE Computer Vision and Pattern Recognition, 2, pp. II/257-II/263,
\2003.

K, Mikolajczyk y C. Schmid. A Performance Evaluation of Local Descriptors. IEEE
Transactions on Pattern Analysis and Machine Intelligence Vol. 27 No. 10, 2005.

131

<!-- p. 144 -->

Anexo I: Referencias bibliográficas

K. Mikolajczyk, T. Tuytelaars, C. Schmid, A. Zisserman, J. Matas, F. Schaffalitzky, T.
Kadir y L. Van Gool. A comparison of affine region detectors. International Journal of
Computer Vision, 65 (1-2), pp 43-72, 2005.

H. Moravec. Rover visual obstacle avoidance. Int. Joint Conference on Artificial
Intelligence, Vancouver, Canada, pp 785-790, 1981.

F. Paul y A. Kääb. Perspectives on the production of a glacier inventory from
multispectral satellite data in the Canadian Arctic: Cumberland Peninsula, Baffin
Island. Annals of Glaciology, 42, 59-66, 2005.

P. Pellikka y W.Gareth Rees. Remote Sensing of Glaciers – Techniques for topographic,
spatial and thematic mapping of glaciers. CRC Press, 2010.

J.A. Pérez. Tesis doctoral: “Estimación de los parámetros internos de sensores
utilizados en cámaras digitales de resolución media y alta mediante modelización de
técnicas fotogramétricas”, Universidad de Extremadura, 2009.

W. Pillewizer. Photogrammetrische Gletscherforchung. Bildmessung und
Luftbildwesen, 2, 66 – 73, 1938.

M. Pollefeys, L. Van Gool, M. Vergauwen, F. Verbiest, K. Cornelis, J. Tops y R. Koch.
Visual modeling with a hand-held camera. International Journal of Computer Vision, 59
(3), pp 207-232, 2004.

J.P. Pons, R. Keriven y O. Faugeras. Modelling dynamic scenes by registering multiview image sequences. IEEE Computer Vision and Pattern Recognition vol. II, pp 822827, 2005.

O. Qelle. Beitragë zur Kenntnis der Spanischen Sierra Nevada . Tesis doctoral. Berlin.
Universidad Friedrich-Wilhelm, 1908.

F. Remondino. Detectors and descriptors for photogrammetric applications,
Photogrammetry and Computer Vision, Bonn, Germany, 2006.

I. Roer, A. Kääb y R. Dikau. Rock glacier acceleration in the Turtmann valley (Swiss
Alps): Probable controls. Norwegian Journal of Geography, 50, 157-163, 2005.

P. Rousseeuw y A. Leroy. Robust regression and outlier detection. Ed. John Wiley:
New York, NY, USA, 1987.

F. Salvador Franch, A. Gómez Ortiz, M. Salvà Catarineu. & D. Palacios Estremera.
Caracterización térmica de la capa activa de un glaciar rocoso en medio periglaciar de
alta montaña mediterránea. El ejemplo del Corral del Veleta (Sierra Nevada, España).
Periodo de observación: 1998-99/2008-09. Cuadernos de Investigación Geográfica (en
prensa), 2011.

J.J. Sanjosé y J.L Lerma. La fotogrametría digital: Una herramienta idónea para el
cartografiado y modelado de zonas de alta montaña. In Congreso de periglaciarismo en
montaña, Potes, Spain, pp 185-203, 2001.

132

<!-- p. 145 -->

Anexo I: Referencias bibliográficas

J.J. Sanjosé y J.L. Lerma. Estimation of the rocks glaciers dynamics by environmental
modeling and automatic photogrammetric technique. XX Congress International
Society for Photogrammetry and Remote Sensing, Istanbul, Turkey, Vol. XXXV,
Commission VII, WG VII/3, 2004.

J.J. de Sanjosé, A.D.J. Atkinson, F.S. Franch, A. Gómez y J. de Matías. Geodesic and
photogrammetric techniques for the cartographic production and the observation of the
geomorphic dynamic of the Corral del Veleta active rock glacier (Sierra Nevada,
España). International Symposium on High Mountain Remote Sensing Cartography,
2006a.

J.J. de Sanjosé, A.D.J. Atkinson, N.A. De Pablo, J.J. Zamorano, D. Palacios y J. de
Matías. Cartographic production (1997-2003) of the Popocatépetl (México) and the
Ventorrillo glacier for the analysis of hydro volcanic risks. International Symposium on
High Mountain Remote Sensing Cartography, 2006b.

J.J. Sanjosé, A.D.J. Atkinson, F. Salvador y A. Gómez. Application of geomatic
techniques to monitoring of the dynamics and to mapping of the Veleta rock glacier
(Sierra Nevada, Spain). Zeitschift für Geomorphologie, 51, 79-89, 2007.

J.J. de Sanjosé Blasco, F. Berenguer Sempere, J. de Matías Bejarano, E. Serrano
Cañadas. Técnicas fotogramétricas aplicadas al Estudio del Helero del Jou Negro
(Picos de Europa). XI Reunión Nacional de Geomorfología, 2010.

C. Sanz de Galdeano, AC. López. Nature and impact of the neotectonic deformation in
the western Sierra Nevada (Spain). Geomorphology, 30 (3): 259-273, 1998.

F. Schaffalitzky y A. Zisserman. Multi-view matching for unordered image sets, of
‘How do I organize my holiday snaps’. European Conference on Computer Vision,
Copenhagen, Denmark, pp 414-431, 2002.

D. Scharstein, R. Szeliski. Stereo matching with nonlinear diffusion. International
Conference of Computer Vision, 28(2), pp 155-174, 1998.

D. Scharstein y R. Szeliski. A taxonomy and evaluation of dense two-frame stereo
correspondence algorithms. International Journal of Computer Vision, 47(1/2/3), pp 742, 2002.

C. Schmid y R. Mohr. Local grayvalue invariants for image retrieval. IEEE Transaction
on Pattern Analysis and Machine Intelligence, 19(5), pp 530-534, 1997.

S. Seitz, C.M. Dyer. Photorealistic scene reconstruction by voxel coloring. International
Journal of Computer Vision, 35(2), pp 1-23, 1999.

S. Seitz, B. Curless, J. Diebel, D. Scharstein y R. Szeliski. A Comparison and
Evaluation of Multi-View Stereo Reconstruction Algorithms. IEEE Computer Vision
and Pattern Recognition, 1, pp 519-526, 2006.

A. Shokoufandeh, I. Marsic y S.J. Dickinson. View-based object recognition using
salicency maps. Image and Vision Computing, 17, pp 445-460, 1999.

133

<!-- p. 146 -->

Anexo I: Referencias bibliográficas

S. Smith, J. Brady. SUSAN: a new approach to low level image processing.
International Journal of Computer Vision, 23, 45-78, 1997.

P. Sturm. On Focal Length Calibration from Two Views. IEEE Computer Vision and
Pattern Recognition, 2, pp 145-150, 2001.

C. J. Taylor. Surface reconstruction from feature based stereo. International Conference
of Computer Vision, pp 184-190, 2003.

W.H. Theakstone. Maping changing glaciers. Aarbus Geoscience, 7, 101-111, 1997.

P. Torr. Motion segmentation and outlier detection. PhD Thesis, Dept. of Engineering
Science, University of Oxford, 1995.

Torr, P.H.S. A structure and motion toolkit in matlab. Technical Report MSR-TR-200256; Microsoft Research: Cambridge, UK, 2002.

B. Triggs, P. McLauchlan, R. Hartley y A. Fitzgibbon. Bundle Adjustment – A Modern
Synthesis. Vision Algorithms’99, LNCS 1883, pp 298-372, 2000.

M. Triglav, M.K. Fras y T. Gvozdfanovic. Monitoring of glacier surfaces with
photogrammetry, a case study of the Triglav Glacier. Acta Geographica, 40(1), 7-30,
\2000.

M. Triglav-Cedaka. Photogrammetrical monitoring of the Triglav Glacier in Slovenia.
5th ICA Mountain Cartography Workshop, Bohinj, Slovenia, 2006.

E. Trucco y A. Verri. Introductory Techniques for 3-D Computer Vision. Prentice Hall,
\1998.

T. Tuytelaars y L.Van Gool. Wide baseline stereo based on local, affinely invariant
regions. Int. British Machine Vision Conference, Bristol, UK, pp 412-422, 2000.

G. Vogiatzis, P. Torr y R. Cipolla. Multi-view stereo via volumetric graph-cuts. IEEE
Computer Vision and Pattern Recognition, pp 391-398, 2005.

M. Weiss. Die geschichtliche Entwicklung der Photogrammetrie und die Begründung
ihrer Verwendbarkeit für MeB- und Konstruktionszwecke. Strecker & Schröder,
Stuttgart, 94 p, 1913.

P.R. Wolf y B.A. Dewitt. Elements of Photogrammetry with aplications in GIS, 3rd ed.
Ed. Mc Graw Hill: Boston, MA, USA, 2000.

T. Yu, N. Xu y N. Ahuja. Shape and view independent reflectance map from multiple
views. European Conference on Computer Vision, pp 602-616, 2004.

Z. Zhang, R. Deriche, O. Faugeras y Q.T. Luong. A robust technique for matching two
uncalibrated images through the recovery of the unknown epipolar geometry. Artificial
Intelligence, 78 (1-2), 87-119, 1995.

134

<!-- p. 147 -->

Anexo II: Índice de figuras

<!-- p. 148 -->

Anexo II: Índice de figuras

136

<!-- p. 149 -->

Anexo II: Índice de figuras

Índice de figuras

Figura 2.1: Esquema general de funcionamiento de un DPW……………………...20

Figura 2.2: Ejemplo de marcas fiduciales………………………………………….22

Figura 2.3: Esquema de la fase de orientación interna de un DPW………………..23

Figura 2.4: Esquema de la fase de orientación externa en un DPW………………..24

Figura 2.5: Modelo de cámara pinhole……………………………………………..27

Figura 2.6: Geometría epipolar de dos vistas de una escena……………………….29

Figura 3.1: Esquema general de la metodología……………………………………52

Figura 3.2: Mecanismo de proyección en una cámara fotográfica…………………53

Figura 3.3: Ejemplo emparejamiento SIFT………………………………………...56

Figura 3.4: Ejemplo de triangulación………………………………………………60

Figura 3.5: Ejemplo de superficie triangulada por Delaunay………………………61

Figura 3.6: Esquema de retroproyección y reproyección…………………………..63

Figura 3.7: Pseudo-código de calculate_depth_map……………………………….64

Figura 3.8: Pseudo-código de calculate_corr………………………………………64

Figura 3.9: Estimación utilizando una superficie triangulada……………………...66

Figura 3.10: Estructura piramidal…………………………………………………..67

Figura 4.1: Cámara Rollei 6008……………………………………………………78

Figura 4.2: Cámara Canon EOS 5D………………………………………………..79

Figura 4.3: Estación Topcon GTS-502E…………………………………………...80

137

<!-- p. 150 -->

Anexo II: Índice de figuras

Figura 4.4: Receptores GPS Leica 1200……………………………………………80

Figura 4.5: Macizo de Sierra Nevada (imagen Landsat)…………………………...83

Figura 4.6: Cumbres de Sierra Nevada (ortofoto 2005, JA)………………………..84

Figura 4.7: Corral del Veleta, agosto, 2009 (A. Gómez Ortiz)…………………….86

Figura 4.8: Glaciar rocoso, agosto, 2009 (A. Gmez Ortiz)………………………...88

Figura 4.9: Fotografía superior, imagen general del frente del glaciar rocoso captada

con estación total. Fotografías inferiores, detalles del mismo punto durante los años

2006, 2007 y 2008………………………………………………………………….89

Figura 4.10: Punto de control utilizado en fotogrametría y toma de fotografías en el

pico del Veleta……………………………………………………………………..90

Figura 4.11: Toma de datos con laser escáner……………………………………..90

Figura 4.12: Evolución perfiles transversales (imagen superior) y longitudinal

(imagen inferior) del glaciar rocoso………………………………………………..91

Figura 4.13: Ejemplo de imágenes realizadas con el objetivo de 35mm (2007)…...92

Figura 4.14: Ejemplo de imágenes realizadas con el objetivo de 100mm (2008)….93

Figura 4.15: Esquema de situación de los puntos de control (2008)……………….93

Figura 4.16: Gráfico de distorsión del objetivo 35 mm…………………………….95

Figura 4.17: Ejemplo de emparejamientos de SIFT (marcados con cruces azules) en

un par de imágenes del glaciar del Veleta (2008)………………………………….96

Figura 4.18: Orientación externa calculada. Posición de las cámaras respecto al

glaciar (2008)……………………………………………………………………….98

Figura 4.19: Ejemplo de TIN del glaciar del Veleta (2008)………………………..99

138

<!-- p. 151 -->

Anexo II: Índice de figuras

Figura 4.20: Comparación con los 5 perfiles tomados con GPS (2008). En color

negro se representan los perfiles tomados con GPS y en azul los obtenidos con la

metodología propuesta…………………………………………………………….100

Figura 4.21: Partición de las nueve tomas en 4 mapas densos (2008)……………101

Figura 4.22: Mapa de curvas de nivel del glaciar

(2008)……………………………………………………………………………...105

Figura 4.23: Emparejamientos 2007-2009………………………………………..107

Figura 4.24: Emparejamiento entre imágenes de 2003 y 2009…………………...110

Figura 4.25: Posibles desplazamientos 2007-2012……………………………….111

Figura 4.26: Datos geomáticos (2007-2008) en el Jou Negro……………………112

Figura 4.27: Situación de las cámaras, puntos obtenidos y puntos de control en el

Jou Negro…………………………………………………………………………113

Figura 4.28: Comparación modelo obtenido (2007) con perfil longitudinal y

transversal (2008)…………………………………………………………………114

139

<!-- p. 152 -->

Anexo II: Índice de figuras

140

<!-- p. 153 -->

Anexo III: Índice de tablas

<!-- p. 154 -->

Anexo III: Índice de tablas

142

<!-- p. 155 -->

Anexo III: Índice de tablas

Índice de tablas

Tabla 4.1: Desplazamiento medio (por sectores) planimétrico / altimétrico en cm……91

Tabla 4.2: Datos de calibración de la cámara Canon EOS 5D…………………………94

Tabla 4.3: Emparejamientos SIFT obtenidos en varios pares de imágenes de 2008…...95

Tabla 4.4: Emparejamientos SIFT obtenidos en varios pares de imágenes de 2008…...97

Tabla 4.5: Error de reproyección (en píxels) tras la orientación externa (2008)……….98

Tabla 4.6: Imágenes utilizadas en cada uno de los mapas de profundidad calculados
(2008)………………………………………………………………………………….101

Tabla 4.7: Puntos obtenidos en cada mapa de profundidad…………………………..103

Tabla 4.8: Error de reproyección de puntos terreno en píxel (2008)…………………104

Tabla 4.9: Error de reproyección de puntos terreno en cm (2008)……………………104

Tabla 4.10: Emparejamientos obtenidos en pares de imágenes 2007-2009…………..107

Tabla 4.11: Emparejamientos obtenidos en pares de imágenes 2003-2009…………..109

143
