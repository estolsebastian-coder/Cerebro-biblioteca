---
type: libro
title: "Introducción a la ISO 19650_Mayo 2021"
author: ""
categoria: "BIM Y HBIM"
paginas: 33
extraccion: "mixto: 2 páginas por OCR (spa)"
fuente: "local:E:/MATERIAL DE CONSULTA/BIM Y HBIM/03. BuildingSmart Spain/Introducción a la ISO 19650_Mayo 2021.pdf"
convertido: 2026-10-16
---

# Introducción a la ISO 19650_Mayo 2021

> Texto extraído de `BIM Y HBIM\03. BuildingSmart Spain\Introducción a la ISO 19650_Mayo 2021.pdf` (33 páginas, mixto: 2 páginas por OCR (spa)). El PDF original está en el disco E: (MATERIAL DE CONSULTA); `<!-- p. N -->` marca el inicio de cada página.

<!-- p. 1 -->

?ºbuildingSMHRI

Spain

Af),
ff

INTRODUCCION A LA SERIE
EN ISO 19650

Revision Mayo 2021
VNN BET TI

a od A A
U g 7 w 4 5
: N

<!-- p. 2 -->

REDACTORES DE ESTE DOCUMENTO

El contenido de este documento y de las imágenes incluidas en él es propiedad de buildingSMART
Spain y ha sido elaborado de forma voluntaria por un conjunto de profesionales que representan a
los diferentes agentes de la cadena de valor.

Coordinadores:

Sergio Muñoz, buildingSMART Spain

Ferrán Bermejo, ITeC

Redactores:

Javier Calvo, Miller&CO José Emilio Nogués, ARQTEAM

Alejandro García, AVATAR Ignacio García Galdón, AQUALIA

Javier García Montesinos, CREA-SI Sergio de los Santos Carrión, AYESA

Luis Miguel Madruga, AYESA Alberto Cerdán, UPV

Inés Bolivar, FCC Francisco García, Logical Space

David Barco, BERRILAN BIM Verónica Mendo, AQUALIA

Fernando Blanco, ACCIONA

Han colaborado en las anteriores ediciones del documento:

Óscar Liébana (AELCA), Isaac Franco (ESBIMEX). Julián Chaur (think project!), Elisenda Serrano
(Italsan), Fidel San Emeterio (AYESA). Javier Vázquez (AYESA), Cristina Palmero (INECO), Eloi
Coloma (C+A), Jesús Perucho (BIM + Partners).

DERECHOS DE AUTOR

El contenido de este documento es sólo para fines de información general y orientativos.

Si se utiliza cualquier información de este documento, entendiendo por información a título
meramente enunciativo los textos, fotografías, gráficos, imágenes e iconos, de forma parcial o total,
se debe mencionar de forma explícita la fuente y la fecha de publicación.

Los derechos de autor de la información que contiene éste documento pertenecen a buildingSMART
Spanish Chapter.

© COPYRIGHT 2021 buildingSMART Spanish Chapter

<!-- p. 3 -->

1º

ÍNDICE

INTRODUCCIÓN

OBJETO DE ESTE DOCUMENTO Pág.1

OBJETO DE LA SERIE EN ISO 19650 Pág.2

BUILDING INFORMATION MODELLING (BIM) SEGÚN LA ISO 19650 Pág.3

PRINCIPIOS GENERALES DE LA SERIE EN ISO 19650

¿A QUIÉN AFECTA LAS NORMAS DE LA SERIE EN ISO 19650? Pág.4

PRINCIPIOS DE LA GESTIÓN DE LA INFORMACIÓN Pág.6

GESTIÓN DE LA INFORMACIÓN EN LA FASE DE DESARROLLO. EN ISO 19650-2 Pág. 14

GESTIÓN DE LA INFORMACIÓN EN LA FASE DE OPERACIÓN. EN ISO 19650-3 Pág. 17

ANEXOS

ANEXO I – GLOSARIO Pág.21

ANEXO II – DIAGRAMA DE SUBACTIVIDADES DE LA FASE DE DESARROLLO Pág.23

ANEXO III – DIAGRAMA DE SUBACTIVIDADES DE LA FASE DE OPERACIÓN Pág.24

ANEXO IV – PLANTILLA DEL PROGRAMA DE DESARROLLO DE LA INFORMACIÓN Pág.25

ANEXO V – EJEMPLOS DE RELACIÓN ENTRE AGENTES SEGÚN LA EN-ISO 19650 Pág.27

<!-- p. 4 -->

1

INTRODUCCIÓN

OBJETO DE ESTE DOCUMENTO

Ante la publicación de las normas EN-ISO 19650, buildingSMART Spain ha elaborado este
documento que facilita la comprensión de estas normas y de sus principios fundamentales, para su
aplicación en los proyectos BIM que se desarrollen en España.

En este documento, que amplía el alcance del publicado en 2019, se explican los principales
conceptos incluidos en las normas 1, 2, 3 y 5 de la serie EN- ISO 19650 y se realiza una propuesta
de adaptación al contexto del sector de la Construcción en España, así como a los agentes que
integran su cadena de valor.

Estandarizar los procesos de desarrollo y gestión de la información permitirá alcanzar el potencial
de BIM a través del trabajo colaborativo, por lo que desde buildingSMART Spain promovemos la
adopción de estas normas.

Esta guía describe algunas situaciones genéricas en la implementación de la norma EN-ISO 19650,
pero no entra en detalles específicos de la organización o del proyecto.

Con el fin de simplificar el uso de acrónimos, se ha adoptado el criterio de traducir el significado de
los términos manteniendo el acrónimo en inglés. Por ello, se verá como, por ejemplo, el Common
Data Environment se traduce por EntornoComúndeDatos, mientras se mantiene la sigla CDE.

En un anexo final consta un glosario con la traducción de los conceptos principales utilizados en las
normas objeto de este documento. Estas traducciones son una adaptación de la terminología
original inglesa a la realidad del sector en España, respetando los criterios de traducción
establecidos por UNE. Los conceptos que forman parte de esta traducción aparecen en el texto en
cursiva. Además, para facilitar la relación de este texto con la norma, a lo largo del documento se
indica el capítulo de la misma al cual se hace referencia.

buildingSMART Spain recogerá comentarios y sugerencias de mejoras que podrían incluirse en
posteriores ediciones de este documento. Estos comentarios y sugerencias pueden ser enviados a
comunicacion@buildingsmart.es.

Introducción a la serie EN ISO 19650
Revisión Mayo 2021

<!-- p. 5 -->

2

OBJETO DE LA SERIE EN ISO 19650

La metodología BIM establece que la colaboración entre los participantes involucrados en
proyectos de construcción y en la gestióndeactivoses esencial para llevar a cabo el desarrollo y
operación de los mismos de forma eficiente.

La serie EN ISO 19650 es un conjunto de normas internacionales que definen el marco, los
principios, y los requisitos, para la adquisición, uso y gestión de la información en proyectos y
activos, tanto de edificación como de ingeniería civil, a lo largo de todo el ciclo de vida de los
mismos, y está destinada principalmente a:

● Los agentes participantes en las fases de diseño, construcción y puesta en servicio de activos
construidos, que en este documento y de acuerdo con la ISO denominamos como fasede
desarrollo.

● Los agentes que desarrollan actividades relacionadas con la gestióndeactivos, incluidas
la operación y el mantenimiento, que en este documento y de acuerdo con la ISO
denominamos fasedeoperación.

La serie EN ISO 19650 está compuesta por un conjunto de normas:

● La norma EN ISO 19650-1 establece los conceptos y principios recomendados para los
procesos de desarrollo y gestión de la información a lo largo del ciclo de vida de cualquier
activo de construcción.

● La norma EN ISO 19650-2 define los procesos de desarrollo y gestión de la información
durante la fasededesarrollo.

● La norma EN ISO 19650-3 define los procesos de uso y gestión de la información durante
la fasedeoperación.

● La norma EN ISO 19650-4 define el intercambio de información en BIM durante las fases
de desarrollo y operación. Esta norma está actualmente en elaboración.

● La norma EN ISO 19650-5 establece los requisitos de seguridad de la información.

La serie EN ISO 19650 es de aplicación a proyectos y activos construidos de cualquier tamaño y
nivel de complejidad, pero en la misma ISO se recomienda que su uso se realice de manera
proporcional y adecuada. Esto debe ser tenido en cuenta especialmente en el caso de proyectos o
activos de pequeño tamaño y en el que los agentes involucrados en los mismos son PYMES.

Introducción a la serie EN ISO 19650
Revisión Mayo 2021

<!-- p. 6 -->

3

BUILDING INFORMATION MODELLING (BIM) SEGÚN LA ISO 19650

Building Information Modelling (BIM) es el uso de una representación digital compartida (modelo de
información) de un activo construido para facilitar los procesos de diseño, construcción y operación,
y proporcionar una base confiable para la toma de decisiones.

La aplicación adecuada de la serie EN ISO 19650 tiene como resultado:

● Una definición clara de la información que necesita el cliente del proyecto o el propietario
del activo, así como de los métodos, procesos, plazos y protocolos de desarrollo y
verificación de esta información;

● Que la cantidad y calidad de la información desarrollada es la suficiente para satisfacer
las necesidades definidas;

● Transferencias eficientes y efectivas de información entre los diferentes agentes que
participan en cada parte del ciclo de vida del activo, especialmente entre la fase de
desarrolloy la de operación.

Figura 1. Esquema general del desarrollo de la información según EN ISO 19650-1

Introducción a la serie EN ISO 19650
Revisión Mayo 2021

<!-- p. 7 -->

4

PRINCIPIOS GENERALES
DE LA SERIE EN-ISO 19650

¿A QUIÉN AFECTA LAS NORMAS DE LA SERIE EN ISO 19650?

La norma EN ISO 19650 es de aplicación por parte de todos los agentes que intervienen en los
diferentes procesos de gestión de la información a lo largo del ciclo de vida de un activo.

Esta gestión de la información se lleva a cabo durante las denominadas fasededesarrolloy fase
deoperación:

● Fasededesarrollo, es la parte del ciclo de vida durante la cual el activo se diseña, se
construye y se entrega a la propiedad.

● Fasedeoperación, es la parte del ciclo de vida durante la cual el activo se utiliza, se opera
y se mantiene.

Las fases de desarrollo y operación deben considerarse como un continuo dentro del ciclo de vida
del activo, estando la gestión de la información directamente vinculada a la gestión empresarial y
a la gestión del activo y el proyecto.

Figura 2. Relación de la gestión de la información con otros sistemas de gestión

Todos los agentes que intervienen en la cadena de suministro de este proceso (propietario,
promotor, cliente¹, arquitectos, ingenieros, constructores, instaladores, etc.) pueden clasificarse
como:

Introducción a la serie EN ISO 19650
Revisión Mayo 2021

1.LanormaENISO19650-1defineclientecomoelagenteresponsabledeiniciarunproyectoyaprobarelprogramadeconstrucción

<!-- p. 8 -->

5

● Adjudicador

● Adjudicatarioprincipal

● Adjudicatario

La versión original en inglés utiliza los términos Appointing, Appointed, que no tienen una traducción
sencilla que incluya las múltiples interpretaciones que pueden tener en nuestro entorno habitual. El
espíritu de la norma pretende identificar el rol de quien asigna un trabajo (adjudicador), y el de
quien recibe un encargo concreto (adjudicatario). Esto puede hacerse con un contrato de por medio
(por ejemplo, en el caso de una licitación) o sin contrato (como podría ser el reparto de tareas
relacionadas con el desarrollo de un proyecto dentro de un empresa, ingeniería o equipo en
general). Inicialmente en la primera versión traducida por UNE se utilizó la fórmula “parte
contratante” y “parte contratada”, aunque en una revisión posterior se flexibilizó con el uso de
“adjudicador” y “adjudicatario” para ser más fiel a la redacción original.

La siguiente figura muestra un ejemplo de las relaciones entre los distintos agentes, la cual se
establece a través de adjudicaciones (no siendo obligatorio que exista un contrato formal), así como
el detalle de qué agentes del mercado español pueden encuadrarse en cada uno de los tipos
definidos. Este esquema puede variar en función de la forma de adjudicación, tal y como se muestra
en el Anexo V.

Figura 3. Relación entre los diferentes agentes

Si bien la serie EN ISO 19650 define las actividades y responsabilidades para cada uno de los
agentes en cada una de las fases, cabe señalar que un agente puede, ocasionalmente, delegar
alguna/s de su/s actividad/es y responsabilidad/es a los agentes que tiene por debajo.

Introducción a la serie EN ISO 19650
Revisión Mayo 2021

<!-- p. 9 -->

6

PRINCIPIOS DE LA GESTIÓN DE LA INFORMACIÓN

Para poder llevar a cabo la gestión de la información conforme establece la serie EN ISO 19650,
es necesario conocer algunos conceptos.

Requisitos de información

Los requisitosdeinformación(verENISO19650-1,capítulo5)son un conjunto de especificaciones
sobre: la información que debe producirse, cuándo debe producirse, su método de producción y
su destinatario.

Estos requisitos de información son definidos inicialmente por el adjudicador pudiendo ser
ampliados por los propios requisitos de los diferentes adjudicatarios.

Por tanto, es importante resaltar que todos los agentes tienen una parte de responsabilidad en la
definición de estos requisitos.

Cabe señalar que los requisitos pueden clasificarse como:

● OIR: RequisitosdeInformacióndelaOrganizaciónrelativos a sus objetivos.

● PIR: RequisitosdeInformacióndelProyectorelativos a su desarrollo.

● AIR: RequisitosdeInformacióndelActivorelativos a su operación.

● EIR: RequisitosdeIntercambiodeInformaciónentre dos partes relativos a una adjudicación.

Es útil que el adjudicadorexplique las razones principales por las que se requiere la información y
así ofrecer una mayor comprensión del trabajo colaborativo a realizar.

Además, los requisitos de información están estrechamente relacionados con el concepto de Nivel
deInformaciónNecesario(verENISO19650-1,capítulo11.2), que se describe en el siguiente
apartado.

Cada posible adjudicatario (p. e. diseñador, contratista) debe responder a estos requisitos de
información en la presentación de ofertas (verEN ISO19650-2, capítulo5.3) con su plan de
ejecuciónBIM,BEP, previo a la adjudiación, indicando en el mismo quién, cuándo y cómo se va a
desarrollar la información que responde a los requisitos previos.

Introducción a la serie EN ISO 19650
Revisión Mayo 2021

<!-- p. 10 -->

7

Nivel de Información Necesario

Tal y como se define en la norma EN 17412-1, el NiveldeInformaciónNecesarioes el marco que
define el alcance y la granularidad de la información.

Uno de sus propósitos es optimizar la información generada, de tal forma que se satisfagan de
forma suficiente los requisitos de información.

El NiveldeInformaciónNecesario dependerá de los objetivos para el uso de la información, los
hitos de entrega, los agentes y los objetos.

El Nivelde InformaciónNecesario debe aplicarse a la información geométrica, la información
alfanumérica y la documentación, y se define para una serie de factores independientes, tal y como
se muestra en la siguiente figura.

Figura 4. Elementos del NiveldeInformaciónNecesario

Plan de ejecución BIM, BEP

El PlandeEjecuciónBIM(BEP) es necesario en distintas fases de un proyecto (desarrollo, operación)
y puede ser distinto para cada una de ellas ya que cubre aspectos distintos según las necesidades
de información de cada fase.

Este plan de ejecución es propuesto en primera instancia por el adjudicatarioprincipal, previa
adjudicacióndel trabajo, con la intención de dar su mejor respuesta a los requisitos de información
del adjudicador. Antes del inicio de la etapa de desarrollo, ambas partes establecerán de mutuo
acuerdo el BEP definitivo inicial, que podrá ser revisado a través de acuerdo entre las partes a
medida que avance el desarrollo. En algunas situaciones el adjudicador, en aras a una
homogeneidad de los trabajos que gestiona, puede proponer un determinado modelo de BEP tipo,
plantilla o similar.

Introducción a la serie EN ISO 19650
Revisión Mayo 2021

<!-- p. 11 -->

8

En la redacción del BEP definitivo acordado entre las partes, es importante que se establezca una
relación entre el trabajo a realizar y los honorarios a percibir, ya que las exigencias contenidas en
el BEP tienen una incidencia directa con el tiempo y el coste de realización del encargo.

El plandeejecuciónBIM debe contener los siguientes elementos (ver EN ISO 19650-2, capítulo
5.3.2):

A. los nombres y reseñas profesionales de las personas que desempeñarán la función de
gestión de la información;

B. la estrategia de entrega de información;

C. la estrategia de federación de los modelos de información;

D. la matriz de responsabilidades, que describe la participación de varias funciones, en la
ejecución de tareas o en la provisión de entregables;

E. los métodos y procedimientos de producción de información del proyecto;

F. la norma de información del proyecto;

G. la infraestructura tecnológica (aplicaciones SW y HW) a adoptar.

Una vez movilizados (verENISO19650-2,capítulo5.5)los recursos necesarios tal y como se ha
definido en el Plan de Ejecución BIM, se inicia la actividad de producción colaborativa de
información(verENISO19650-2punto5.6).

Contenedores de información

Un contenedordeinformación es un conjunto de información persistente y recuperable desde un
archivo o sistema de almacenamiento.

En función del tipo de información los contenedores se clasifican como:

● De información estructurada: como por ejemplo modelos geométricos, propiedades y
atributos, programaciones, etc.

● De información no estructurada: como por ejemplo documentos, imágenes, videoclips, etc.

El almacenamiento de los contenedores de información puede realizarse a través de formatos
abiertos (cuyas especificaciones son de dominio público y sin restricciones legales) o formatos
propietarios.

El uso de formatos abiertos favorece la perdurabilidad y accesibilidad de la información a lo largo
del tiempo.

Introducción a la serie EN ISO 19650
Revisión Mayo 2021

<!-- p. 12 -->

9

Entorno Común de Datos, CDE

Para poder trabajar de forma colaborativa es necesario disponer de un EntornoComúndeDatos
(CDE). El CDE es la fuente acordada de información para cada activo o proyecto, para reunir,
gestionar y repartir cada contenedor de información a través de un procedimiento establecido (ver
ENISO19650-1,capítulo12). Según este procedimiento, la información contenida en el CDE podrá
tener diferentes estados (ver figura 5):

● Estado trabajoencurso(WIP). Aplica a la información que se está desarrollando por el
equipo de trabajo.

● Estado compartido(S). Aplica a la información que puede ser consultada por todas las
partes apropiadas.

● Estado publicado(P). Aplica a la información que ha sido autorizada para su uso.

● Estado archivo(ARC). Aplica a la información que se ha compartido y publicado y que
queda registrada.

Figura 5. Concepto de EntornoComúndeDatos(CDE)

Introducción a la serie EN ISO 19650
Revisión Mayo 2021

<!-- p. 13 -->

10

Los flujos de trabajo que deben tener lugar en el CDE pueden llevarse a cabo en una solución
tecnológica o herramienta que, al menos, permita:

● Gestión del estado de la información.

● Gestión y clasificación de los contendedores de información.

● Control de versiones.

● Control del acceso a la información.

El uso de una estructura fija de codificación y de metadatos para la identificación de los diferentes
contenedores de información genera una serie de beneficios:

● Aportar información a los agentes intervinientes.

● Disponer de un identificador único para cada documento.

● Búsquedas de información más eficientes.

● Mejora el intercambio de información entre agentes a lo largo de todo el ciclo de vida del
activo construido.

buildingSMART Spain ha elaborado un Manual de Nomenclatura de documentos al utilizar BIM,
alineado a la serie de normas ISO 19650, que sirve de punto de partida para su utilización por
parte del sector, y que puede ser adaptado conforme a las necesidades específicas de cada agente
o proyecto.

En la actualidad existe una gran variedad de herramientas que permiten desarrollar un proyecto
BIM de forma colaborativa. Algunas de estas soluciones integran funcionalidades adicionales que
facilitan las tareas de producción de la información:

● Gestión documental.

● Asignación de tareas y responsabilidades.

● Comunicación entre agentes.

● Visualización de los modelos de información.

Es el adjudicador el responsable de proporcionar la solución de EntornoComúndeDatos (CDE)
para cada proyecto, ya sea directamente o a través de un tercero, o incluso a través de alguno de
los adjudicatarios.

Una vez realizada la producción colaborativa de información, tiene lugar la actividad de entrega
del modelo de información (vercapítulo5.7delasnormasENISO19650-2yENISO19650-3).

Introducción a la serie EN ISO 19650
Revisión Mayo 2021

<!-- p. 14 -->

11

Modelo de información

El modelo de información es un conjunto de contenedores de información estructurada y no
estructurada que facilita la toma de decisiones.

Es recomendable que los elementos contenidos en el modelo estén clasificados según uno o más
sistemas de clasificación, de forma que facilite los procesos de búsqueda o filtrado de la información
(verENISO19650-1,capítulo11.3).

El modelo de información podrá componerse de un conjunto de contenedores de información de
diferentes disciplinas (arquitectura, estructura, instalaciones, etc.) organizados para que puedan ser
federadosde forma apropiada para facilitar la colaboración durante el desarrollo del proyecto (ver
ENISO19650-1,capítulo10.4).

Figura 6. Modelo federado en las disciplinas de arquitectura, estructura e instalaciones

Por otro lado, los modelos de información que pueden ser considerados como entregables pueden
clasificarse (verENISO19650-1,capítulo4)como:

● PIM: ModelodeInformacióndelProyectorelacionado con la fasededesarrollo.

● AIM: ModelodeInformacióndelActivorelacionado con la fasedeoperación.

Introducción a la serie EN ISO 19650
Revisión Mayo 2021

<!-- p. 15 -->

12

La siguiente figura define la jerarquía de los requisitos de información en relación a la Organización,
la Adjudicación, y el Modelo entregable.

Figura 7. Jerarquía de los requisitos de información según EN ISO 19650-1

A la finalización de la fasededesarrollo, y con la entrega del modelo de información se debe
garantizar que se han cumplido los requisitos de información. La información relevante de los activos
recopilada durante esta fase se debe unificar para su entrega y ser de utilidad para la operación y
mantenimiento.

Seguridad de la Información

La aplicación de la metodología BIM conlleva el uso y dependencia de las tecnologías de la
información y las comunicaciones, más si cabe cuando dicha información puede estar accesible
para diferentes organizaciones en un EntornoComúndeDatos(CDE). Es por tanto necesario tener
en cuenta los problemas de vulnerabilidad y los riesgos de seguridad, así como la existencia de
informaciónsensibleen el modelo de información o documentación relacionada.

Hay una serie de activos que, por su naturaleza, contienen informaciónsensible, como es el caso
de infraestructuras críticas o los considerados como espacios multitudinarios, tales como estadios,
pabellones deportivos, hoteles, calles comerciales, mercados, plazas, parques, estaciones de
transporte, hospitales, etc.

Introducción a la serie EN ISO 19650
Revisión Mayo 2021

<!-- p. 16 -->

13

La pérdida, alteración, uso indebido o acceso no autorizado a esta informaciónsensible puede
tener una serie de repercusiones graves que hay que tener en cuenta:

● Afectar a la privacidad, protección o seguridad de personas.

● Comprometer la propiedad intelectual o secretos comerciales de una organización.

● Causar daños comerciales o económicos a una organización.

Para poder responder de forma adecuada a los riesgos de seguridad, puede ser necesario definir
una estrategia de gestión de dichos riesgos, tal y como se detalla en la norma ISO 19650-5.

Dicha estrategia debe tener en cuenta que BIM es una metodología colaborativa, en la que existe
intercambio de información entre organizaciones, por lo que será necesario tener en cuenta los
requisitos de seguridad de cada una de ellas para establecer los riesgos y tolerancias a lo largo del
ciclo de vida.

La aplicación de las medidas establecidas en la estrategiadeseguridadse llevará a cabo mediante
un plan de gestión de la seguridad, cuyo principal objetivo es garantizar la fiabilidad, integridad,
confidencialidad y autenticidad de la información.

Figura 8. Proceso de gestión de la seguridad simplificado conforme a la norma UNE EN ISO 19650-5

Introducción a la serie EN ISO 19650
Revisión Mayo 2021

<!-- p. 17 -->

14

GESTIÓN DE LA INFORMACIÓN EN LA FASE DE DESARROLLO.
EN ISO 19650-2

El proceso de gestión de la información (que incluye su producción y entrega) en la fase de
desarrollo(parte del ciclo de vida en la que el activo se diseña, construye y entrega a la propiedad)
se aplicará para cada adjudicaciónhasta la finalización de dicha fase.

Este proceso está compuesto por una serie de actividades según se muestra en la siguiente figura
(verENISO19650-2,capítulo4):

Figura 9. Esquema de la gestión de la información durante la fasededesarrollosegún EN ISO 19650-2

Cada una de estas actividades puede a su vez estar dividida en subactividades, tal y como se
muestra en la figura del Anexo II. En dicha figura, se indica el agente responsable (adjudicador,
adjudicatario, etc.) de cada subactividad, así como el tipo de resultado esperado (un documento,
una evaluación, etc.). Además, se puede apreciar el flujo de dichas subactividades y los procesos
de aprobación a los que están sometidos los resultados de las mismas.

En función de la complejidad y tamaño del proyecto, algunas de estas subactividades podrían
simplificarse.

Aunque en la norma EN ISO 19650-2 se describe de forma detallada el alcance de cada una de
estas subactividades, en este documento queremos destacar algunos aspectos que consideramos
relevantes a lo largo de este proceso.

Introducción a la serie EN ISO 19650
Revisión Mayo 2021

<!-- p. 18 -->

15

Inicio de la gestión de la información

El adjudicadorcomienza realizando una evaluación de necesidades (verENISO19650-2,capítulo
5.1), asegurando que los requisitos de información estén claramente definidos al inicio del proyecto,
junto con la forma en que se deben implementar los conceptos y principios de la gestión de la
información y los beneficios esperados de ello.

Es recomendable que en esta fase se definan, entre otros:

● Los responsables de la función de gestión de la información.

● Los requisitosdeinformacióndelproyecto(PIR).

● Los hitos de entrega de información del proyecto.

● Los procedimientos para la producción e intercambio de información.

● Los recursos compartidos.

● El CDE del proyecto.

Etapa de licitación

En esta etapa (ver EN ISO 19650-2 capítulos 5.2 y 5.3), el adjudicador debe establecer los
requisitos para la petición y presentación de ofertas por parte de los adjudicatarios, así como los
criterios de evaluación de dichas ofertas.

Estos criterios de evaluación deben tener en cuenta, principalmente, los siguientes elementos:

● El PlandeEjecuciónBIM(BEP) propuesto por el adjudicatario.

● Las habilidades y capacidades del equipo de trabajo propuesto por el adjudicatario.

● El plan de movilización de los recursos humanos y tecnológicos necesarios.

● La evaluación de los riesgos asociados a la entrega de información.

Etapa de planificación

En esta etapa (verENISO19650-2capítulos5.4y5.5) tiene lugar la adjudicación, en la que se
designa al adjudicatarioprincipaly se deberá confirmar el PlandeEjecuciónBIM, vinculante entre
las partes, de acuerdo con el resto de adjudicatariosy conforme a los requisitos y necesidades del
adjudicador.

A continuación, el adjudicatarioprincipal, deberá movilizar los recursos humanos y tecnológicos
necesarios (definidos en el plan de movilización) para poder llevar a cabo el trabajo.

Introducción a la serie EN ISO 19650
Revisión Mayo 2021

<!-- p. 19 -->

16

Etapa de producción

En esta etapa (ver EN ISO 19650-2 capítulos 5.6 y 5.7) tiene lugar la producción colaborativa de
la información y la entrega del modelo de información.

La producción colaborativa de la información se llevará a cabo dentro del EntornoComúndeDatos,
(CDE), donde se crean los contenedores de información que conforman el modelo de información.
La entrega del modelo de información por parte del adjudicatarioprincipalal adjudicadorpodrá
llevar asociados procesos de control de calidad y revisión teniendo en cuenta los entregables de
información definidos, sus requisitos de información y el NiveldeInformaciónNecesariode cada
uno de ellos.

Si la revisión tiene éxito, el adjudicadordebe aceptar el modelo de información como entregable
dentro del EntornoComúndeDatos(CDE).

Fin de la fase de desarrollo

En esta etapa (ver EN ISO 19650-2 capítulo 5.8), el adjudicadordeberá verificar que se archiva el
modelo de información en el EntornoComúndeDatos(CDE), teniendo en cuenta qué información
es necesaria como parte del ModelodeInformacióndelActivo(AIM) y los requisitos de acceso a la
información en el futuro, en la fasedeoperación.

Además, es recomendable que el adjudicador, en colaboración con los adjudicatariosprincipales,
recoja las lecciones aprendidas durante la fasededesarrolloy las registre en una base de datos de
conocimiento, para poder consultarla en futuros proyectos.

Introducción a la serie EN ISO 19650
Revisión Mayo 2021

<!-- p. 20 -->

17

GESTIÓN DE LA INFORMACIÓN EN LA FASE DE OPERACIÓN.
EN ISO 19650-3

El ModelodeInformacióndelActivo(AIM), necesita ser mantenido durante la fasedeoperacióndel
activo, reflejando de este modo el estado y condición del mismo.

Si bien, hay que tener en cuenta que la fasedeoperacióndel activo tiene una duración muy superior
a la fasededesarrollo, y el proceso de gestión de la información en esta fase se debe aplicar por
cada evento desencadenante que suponga llevar a cabo una actualización del Modelo de
InformacióndelActivo.

Los eventos desencadenantes pueden clasificarse en:

● Los previsibles y que pueden ser planificados con antelación, como por ejemplo las tareas
anuales de mantenimiento o las solicitudes de reparaciones rutinarias. Para este tipo de
eventos desencadenantes es posible seleccionar el adjudicatarioprincipalde forma previa.

● Los imprevisibles y por tanto no pueden ser planificados, como por ejemplo averías
inesperadas de los equipos o accidentes. Para este tipo de eventos desencadenantes la
selección del adjudicatarioprincipalsuele hacerse con posterioridad a que tengan lugar.

Además, cabe tener en cuenta que puede darse el caso en que se haya utilizado BIM en la fasede
desarrolloconforme a lo indicado en la EN ISO 19650-2, o que la aplicación de la EN ISO 196503 tenga lugar a partir de la adquisición de un activo existente.

El proceso de gestión de la información en la fasedeoperaciónestá compuesto por una serie de
actividades que pueden variar en función de la casuística descrita anteriormente (ver figura 4 EN
ISO 19650-3).

Cada una de estas actividades puede a su vez estar dividida en subactividades, tal y como se
muestra en la figura del Anexo III. En dicha figura, se indica el agente responsable (adjudicador,
adjudicatario, etc.) de cada subactividad, así como el tipo de resultado esperado. Además, se
puede apreciar el flujo de dichas subactividades y los procesos de aprobación a los que están
sometidos los resultados de las mismas.

Aunque en la norma EN ISO 19650-3 se describe de forma detallada el alcance de cada una de
estas subactividades, en este documento queremos destacar algunos aspectos que consideramos
relevantes a lo largo de este proceso.

Introducción a la serie EN ISO 19650
Revisión Mayo 2021

<!-- p. 21 -->

18

Inicio de la gestión de la información

El adjudicadorcomienza realizando una evaluación de necesidades (ver EN ISO 19650-3, capítulo
5.1), asegurando que los requisitos de información estén claramente definidos, junto con la forma
en que se deben implementar los conceptos y principios de la gestión de la información y los
beneficios esperados de ello.

Es recomendable que en esta fase se definan, entre otros:

● Los requisitos de información de la organización (OIR) y del activo (AIR).

● Los eventos desencadenantes previsibles.

● Los procedimientos para la producción de información y de mantenimiento del Modelode
InformacióndelActivo(AIM).

● El EntornoComúndeDatos(CDE) y su conexión con el sistema empresarial.

Etapa de licitación

En esta etapa (ver EN ISO 19650-3 capítulos 5.2 y 5.3), el adjudicadordebe establecer, para cada
tipo de eventodesencadenante, los requisitos para la petición y presentación de ofertas por parte
de los adjudicatarios, así como los criterios de evaluación de dichas ofertas.

Estos criterios de evaluación deben tener en cuenta, principalmente, los siguientes elementos:

● El PlandeEjecuciónBIM(BEP) propuesto por el adjudicatario.

● Las habilidades y capacidades del equipo de trabajo propuesto por el adjudicatario.

● El plan de movilización de los recursos humanos y tecnológicos necesarios.

● La evaluación de los riesgos asociados a la entrega de información.

Introducción a la serie EN ISO 19650
Revisión Mayo 2021

<!-- p. 22 -->

19

Etapa de planificación

En esta etapa (ver EN ISO 19650-3 capítulos 5.4 y 5.5) tiene lugar la adjudicación, en la que se
designa al adjudicatarioprincipaly se deberá confirmar el PlandeEjecuciónBIM, vinculante entre
las partes de acuerdo con el resto de adjudicatariosy conforme a los requisitos y necesidades del
adjudicador.

A continuación, el adjudicatarioprincipal deberá movilizar los recursos humanos y tecnológicos
necesarios para poder llevar a cabo el trabajo, de modo que estén preparados en caso de que se
produzca un eventodesencadenantecontemplado previamente.

Etapa de producción

En esta etapa (ver EN ISO 19650-3 capítulos 5.6 y 5.7) tiene lugar la producción colaborativa de
la información y la entrega del modelo de información.

La producción colaborativa de la información se llevará a cabo dentro del EntornoComúndeDatos
(CDE), donde se crean los contenedores de información que conforman el modelo de información.
La entrega del modelo de información por parte del adjudicatarioprincipalal adjudicadorpodrá
llevar asociados procesos de control de calidad y revisión teniendo en cuenta los entregables de
información definidos, sus requisitos de información y el nivel de información necesario de cada uno
de ellos.

Si la revisión tiene éxito, el adjudicadordebe aceptar el modelo de información como entregable
dentro del EntornoComúndeDatos(CDE).

Agregación al Modelo de Información del Activo

En esta etapa (ver EN ISO 19650-3 capítulo 5.8), el adjudicadores responsable del proceso de
integración de un modelo de información aceptado al AIM, conciliando esta información con el
contenido existente del AIM.

Introducción a la serie EN ISO 19650
Revisión Mayo 2021

<!-- p. 23 -->

20

ANEXOS

Introducción a la serie EN ISO 19650
Revisión Mayo 2021

<!-- p. 24 -->

21

ANEXO I - GLOSARIO

Glosario de los conceptos principales utilizados en las normas objeto de este documento y que han
sido traducidos como una adaptación de la terminología original inglesa a la realidad del sector en
España.

TÉRMINO CONCEPTO ORIGINAL EN-ISO 19650

Adjudicación Appointment

Entorno común de datos, CDE Common Data Environment

Equipo de desarrollo Delivery Team

Fase de desarrollo Delivery Phase

Fase de operación Operational Phase

Hito de entrega de información Information Delivery Milestone

Modelo de información del activo, AIM Asset Information Model, AIM

Modelo de información del proyecto, PIM Project Information Model, PIM

Nivel de información necesario Level of Information Need

Adjudicatario / Adjudicatario principal Appointed party / lead appointed party

Adjudicador Appointing party

Plan de ejecución BIM, BEP BIM Execution Plan, BEP

Programa de desarrollo de información de una tarea Task Information Delivery Plan

Programa general de desarrollo de la información Master Information Delivery Plan

Introducción a la serie EN ISO 19650
Revisión Mayo 2021

<!-- p. 25 -->

22

Requisito de información Information Requirement

Requisitos de información relativos a la organización, Organizational Information
OIR Requirements, OIR

Requisitos de información relativos al activo, AIR Asset Information Requirements, AIR

Requisitos de información relativos al proyecto, PIR Project Information Requirements, PIR

Requisitos de intercambio de información, EIR Exchange Information Requirements, EIR

Gestión de activos Asset management

Gestión de inmuebles y servicios de soporte Facility management

Evento desencadenante Trigger event

Protección Safety

Seguridad Security

Información sensible Sensitive information

Estrategia de seguridad Security-minded

Introducción a la serie EN ISO 19650
Revisión Mayo 2021

<!-- p. 26 -->

19650 DESARROLLO ISO 2021
EN DE Mayo serie
la FASE a Revisión
LA
DE Introducción
SUBACTIVIDADES
DE
DIAGRAMA

–

II
23 ANEXO

<!-- p. 27 -->

24

ANEXO III – SUBDIAGRAMA DE ACTIVIDADES DE LA FASE DE OPERACIÓN

Introducción a la serie EN ISO 19650
Revisión Mayo 2021

<!-- p. 28 -->

Etc.

4
Hito
Entrega
3 tareas de
las Hito
de Fechas

2 una
Hito cada

1
Para
Hito TIDP)
Plan, de INFORMACIÓN 19650 LA Título
ISO modelo/Dibujo DE Delivery 2021 EN
Mayo serie
la Número a Revisión DESARROLLO Information (Task tarea Disciplina Introducción DE
tarea una de una información Tipo
de de información PROGRAMA de Nivel contenedor DEL información del de desarrollo de Sistema Identificador PLANTILLAS desarrollo Programa – Creador
IV de
Proyecto25 ANEXO Programa

<!-- p. 29 -->

Mantenimiento
y Operación - 7

marcha
en Puesta - 6

Construcción - 5

Constructivo
/ Ejecución P. - 4 Edificación
en

Básico Proy. - 3
disciplinas Etapas
las Anteproyecto 2-
de
una MIDP) previos
cada Estudios 1-
Plan, 19650 para
Estrategia - 0 ISO
2021
EN Delivery de Mayo información serie Dibujo la la Título modelo/
a Revisión de Information Número
desarrollo Introducción
Disciplina (Master de información general de Tipo información
Nivel de Programa contenedor
del
Sistema
desarrollo Identificador Creador de

Proyecto general

de de
Estructura Modelo escaneado26 Programa Arquitectura Instalaciones Modelos Obra/Subcont.

<!-- p. 30 -->

27

ANEXO V – EJEMPLOS DE RELACIÓN ENTRE AGENTES SEGÚN LA
EN-ISO 19650

Adjudicador
(Promotor y
Propietario)

Adjudicatario Adjudicatario Adjudicatario
Principal Principal Principal (Operación
(Arquitectura) (Constructora) y Mantenimiento)

Adjudicatario Adjudicatario Adjudicatario
(Geotecnia) (Subcontrata) (Facility Manager)

Adjudicatario Adjudicatario Adjudicatario (Mantenimiento (Estructuras) (Instalador) Climatización)

Adjudicatario
(Instalaciones)

Figura V-A. Esquema de agentes en un proyecto de edificación tradicional

Adjudicador
(Promotor y
Propietario)

Adjudicatario Adjudicatario
Principal Principal (Empresa
(Constructora) de servicios de FM )

Adjudicatario Adjudicatario Adjudicatario Adjudicatario (Subcontrata (Lider Arquitectura) (Instalador) (Facility Manager) Construcción)

Adjudicatario Adjudicatario (Mantenimiento (Estructuras) Climatización)

Adjudicatario
(Instalaciones)

Figura V-B. Esquema de agentes en un proyecto de edificación tipo diseño y construcción

Introducción a la serie EN ISO 19650
Revisión Mayo 2021

<!-- p. 31 -->

28

Adjudicador (Cliente)

Adjudicatario Adjudicatario Principal
Principal (Certificador (Consorcio PPP)
Indep.)

Adjudicatario* Adjudicatario* Adjudicatario* (Financiación PPP y (Diseño y Construcción) (Servicios de O&M) gestión comercial)

Adjudicatario Adjudicatario* (Sistemas Adjudicatario* (Mantenimiento de Ferroviario y Material (Constructora) sistemas ferroviarios y Rodante) Material rodante)

Adjudicatario* Adjudicatario Adjudicatario (Sistemas (Ingeniería (Ingeniería sistemas ) Ferroviario) Coordinadora)

Adjudicatario Adjudicatario Adjudicatario (Material
(Arquitectura) (Diseñador Ferroviario) Rodante)

Adjudicatario Adjudicatario
(Subncontratista) (Instalador)

Figura V-C. Esquema de agentes en un proyecto PPP ferroviario (Financiación, Diseño, Construcción y O&M)

\*UnAdjudicatario(principalono)puededelegaralguna/sdesusactividad/esaunoovariosdesus
Adjudicatarios

Introducción a la serie EN ISO 19650
Revisión Mayo 2021

<!-- p. 32 -->

29

Adjudicador(Cliente)

Adjudicatario
(Ing. Cliente)

Adjudicatario Principal
(SPV)

Adjudicatario Adjudicatario
(EPC) (O&M)

Adjudicatario Adjudicatario Adjudicatario
(Ingeniería) (Constructora) (Mantenimiento)

Adjudicatario Adjudicatario Adjudicatario
(Estudios: geotecnia, (Conducciones
topografía…) exteriores) (Gestión de Residuos)

Adjudicatario Adjudicatario Adjudicatario
(Ingeniería Procesos:
EM, EE, I&C…) (Obra Civil) (Energía Eléctrica)

Adjudicatario ( Otros: Adjudicatario Adjudicatario suministro reactivos, (Ingeniería No (Edificación) membranas, material Procesos: HVAC, FF…) laboratorio…)

Adjudicatario
(Instalaciones
Procesos: EM, EE,
I&C…)

Adjudicatario
(Instalaciones No
Procesos: HVAC, FF…)

Figura V-D. Esquema de agentes en un proyecto de aguas (Financiación, Diseño, Construcción y O&M)

Introducción a la serie EN ISO 19650
Revisión Mayo 2021

<!-- p. 33 -->

(º)SbUHdlngSMHRT

buildingsmart.es
