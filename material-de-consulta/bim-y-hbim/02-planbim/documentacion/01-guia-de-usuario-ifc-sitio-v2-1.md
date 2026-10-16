---
type: libro
title: "01_GUÍA DE USUARIO IFC SITIO_V2.1"
author: "Sebastian Manriquez Fuentealba"
categoria: "BIM Y HBIM"
paginas: 24
extraccion: "texto"
fuente: "local:E:/MATERIAL DE CONSULTA/BIM Y HBIM/02. Planbim/documentación/01_GUÍA DE USUARIO IFC SITIO_V2.1.pdf"
convertido: 2026-10-16
---

# 01_GUÍA DE USUARIO IFC SITIO_V2.1

> Texto extraído de `BIM Y HBIM\02. Planbim\documentación\01_GUÍA DE USUARIO IFC SITIO_V2.1.pdf` (24 páginas, texto). El PDF original está en el disco E: (MATERIAL DE CONSULTA); `<!-- p. N -->` marca el inicio de cada página.

<!-- p. 1 -->

GUÍA DE ENTIDADES IFC
MODELO DE SITIO
Según ISO 16739-1:2018

VERSIÓN 2.1

OCTUBRE 2020

1

<!-- p. 2 -->

CONTROL DE VERSIONES

Versión Fecha Observaciones

1.0 Septiembre 2020
2.0 Octubre 2020 Ajuste de color de portada
2.1 Octubre 2020 Se agrega nombre de enumeración en inglés a cada tabla de tipos.

El contenido de esta guía es traducción directa de la ISO 16739-1:2018 publicada por buildingSMART International en la
página https://standards.buildingsmart.org/IFC/RELEASE/IFC4/ADD2_TC1/HTML/
La introducción, íconos de entidades e imágenes referenciales fueron desarrolladas por Planbim Chile.

Esta obra está licenciada bajo la Licencia Creative Commons
Atribución-NoComercial 4.0 Internacional.
Para ver una copia de esta licencia, visite http://creativecommons.org/licenses/by-nc/4.0/.

2

<!-- p. 3 -->

Introducción

OBJETIVO DE LA GUÍA

El presente documento tiene como objetivo apoyar la implementación del Estándar BIM para Proyectos Públicos desarrollado
por Planbim, en específico en la utilización del estándar abierto IFC para el intercambio de información de la industria de la
construcción. En esta guía se describe cuáles entidades BIM deben ser utilizadas en un modelo BIM de Sitio, el cual puede ser
desarrollado por especialistas de la disciplina de topografía, y cuáles son los Tipo Predefinidos que existen dentro de ellas. Para
cada Tipo Predefinido, Planbim ha incluido su significado en español junto con una imagen referencial, para facilitar la
identificación del elemento constructivo al que cada uno de ellos representa.

Todas las definiciones indicadas en este documento son una traducción directa de la ISO 16739-1:2018 (IFC4 ADD2 TC1),
documento que detalla el esquema de datos IFC, las entidades que lo componen y los parámetros disponibles para cada una
de ellas. A través del Estándar BIM para Proyectos Públicos y la Matriz de Información de Entidades, Planbim adopta la estructura
de información del esquema IFC, utilizándola como base para especificar:

• las entidades que componen los distintos modelos BIM.

• el Tipo de Información (TDI) que estas deben contener según los Usos BIM seleccionados.

• el Nivel de Información (NDI) necesario para los Estado de Avance de la Información de los Modelos (EAIM)
definidos para las etapas del proyecto.

Las entidades referidas en esta guía están incluidas en la Tabla 03 - Entidades mínimas para cada tipo de modelo BIM - del
Estándar BIM para Proyectos Públicos y en la Matriz de Información de Entidades BIM, elaborados por Planbim. Estos
documentos se encuentran disponibles en https://planbim.cl/biblioteca/documentos/ para su descarga. La ISO 196739-1:2018
se encuentra disponible para consulta de forma gratuita en:

https://standards.buildingsmart.org/IFC/RELEASE/IFC4/ADD2_TC1/HTML/

ENTIDADES IFC

En el esquema IFC, una entidad representa una categoría de elementos, definidas por propiedades comunes. Existen distintos
tipos de entidades, que pueden ser clasificadas según el tipo de elemento al que representan, y también según su grado de
especificidad. A continuación, se definen estas clasificaciones:

• ENTIDADES ABSTRACTAS Y ENTIDADES FÍSICAS:
Las entidades físicas representan elementos tangibles utilizados en la industria de la construcción, como Muros,
Ventanas, Vigas y Mobiliario, entre otros. En cambio, las entidades abstractas permiten representar elementos
conceptuales, como Tareas, Proyectos o Edificios.

• ENTIDADES GENERALES Y ESPECÍFICAS:
Al ser IFC un esquema de información jerárquico, las entidades que contiene se ordenan desde las más generales a
las más específicas. Las entidades de carácter general sientan las bases para la creación de entidades más
específicas, permitiendo que estas últimas hereden algunas de sus propiedades de las primeras. Un ejemplo de esto es
la entidad IfcElement (Elemento), que representa una generalización de todos los componentes de un producto de la
industria de la construcción. De esta entidad general derivan las entidades específicas de los elementos constructivos
como muros, losas, vigas, equipos de climatización, electricidad o instalaciones sanitarias, y también entidades que
representan mobiliario, elementos de conexión estructural, entre otros.

3

<!-- p. 4 -->

ATRIBUTOS, PROPIEDADES Y CUANTÍAS

El esquema IFC permite gestionar la información de las entidades a través de atributos y propiedades. Los atributos son los datos
distintivos de cada entidad, es decir, la información que permite identificar una entidad IFC. Las propiedades se agrupan en
Property Sets (Pset), y permiten agregar información complementaria a una entidad.

Las cuantías son grupos de parámetros que permiten indicar las propiedades físicas de una entidad, como largo, ancho,
espesor, etc. Estas propiedades se agrupan en Quantity Sets (Qto). Toda esta información puede ser específica para cada
entidad, o puede ser heredada desde una entidad superior.

TIPOS PREDEFINIDOS

El Tipo Predefinido es un atributo que permite aumentar el grado de especificidad de una entidad, seleccionando un valor de
un listado de tipos preestablecidos. Este listado está definido en la ISO 196739-1:2018. Por ejemplo, la entidad Muro (IfcWall)
tiene 10 tipos predefinidos, entre ellos están: Pilastra (PILASTER) y Columna (COLUMN).

Los tipos predefinidos mínimos que contiene una entidad son:

• USERDEFINED (definido por usuario): Permite incorporar cualquier otro tipo que no esté indicado en el listado del
estándar IFC. Es importante indicar que, antes de utilizar esta opción, el equipo a cargo debe estar seguro de que
ninguno de los tipos predefinidos incluidos en el estándar IFC es apropiado para las necesidades del proyecto. En este
caso, el gestor BIM puede proponer un tipo definido por usuario, para ser validado por el Solicitante. Si el Solicitante
aprueba esta incorporación, el tipo definido por usuario debe ser comunicado todos los actores relevantes.

• NOTDEFINED (no definido): Permite clasificar una entidad BIM de la cual aún no se ha determinado su tipo, por ejemplo,
en las etapas tempranas de desarrollo de un proyecto.

Es importante indicar que la información del esquema IFC es la misma que se utiliza en cualquier proyecto de la industria de la
construcción, y por lo tanto muchas propiedades ya están incorporadas en los software de autoría BIM. Esto significa que en la
mayoría de los casos no será necesario crear cada uno de los parámetros incluidos en la Matriz de Información de Entidades,
sino que se pueden utilizar los existentes en el software con el que se trabaja, y sólo crear los que no se incluyan de forma nativa.
De esta forma se evita duplicar la información, manteniendo los archivos de proyecto con un peso acotado. Para entender
cuáles son los parámetros ya incluidos en cada software, se sugiere revisar la documentación que cada empresa desarrolladora
pone a disposición de sus usuarios.

INCORPORACIÓN DE LA INFORMACIÓN

Las formas en que cada software gestiona la información de un modelo y la traspasa al esquema IFC pueden ser muy diversas.
De forma general, se puede diferenciar tres maneras de incorporar la información del esquema IFC en las entidades de un
modelo BIM:

• Parámetros nativos: Son aquellos incorporados por defecto en la estructura de información de un software y por lo
tanto en sus entidades, y están ligados automáticamente al esquema IFC. Para estos parámetros, sólo se debe ingresar
el dato apropiado (p. ej. Parámetro Ancho: / Dato apropiado: 1,5 m) para que éste sea exportado sin requerir mayor
configuración.
• Parámetros configurados por el usuario: Son aquellos que están incorporados en la estructura de información de un
software, pero no están ligados automáticamente al esquema IFC. La exportación de esta información varía de un
software a otro, por lo que se sugiere revisar la documentación que cada empresa desarrolladora pone a disposición
de sus usuarios.
• Parámetros creados por el usuario: Estos son parámetros IFC que no están disponibles en los software de manera nativa
y que deben ser creados a partir de lo que indica la Matriz de Información de las Entidades en la columna IFC/COBie.

Para más detalle de este tema, se sugiere revisar el video tutorial N° 4 “Incluir información para la exportación IFC” de la lista
de reproducción “TUTORIALES ESTÁNDAR BIM PARA PROYECTOS PÚBLICOS”, que se encuentran disponibles en el siguiente link:
https://planbim.cl/biblioteca/videos/

4

<!-- p. 5 -->

¿CUALES SON LOS PARÁMETROS NATIVOS QUE SE EXPORTAN AUTOMATICAMENTE A IFC?

Según lo indicado anteriormente, cada software gestiona la información de sus entidades y modelos de formas distintas. Por
esto, la respuesta a esta pregunta varía según el software BIM que se utilice. Sin embargo, hay parámetros que son inherentes
a un modelo BIM desarrollado de forma correcta y que, por lo tanto, la gran mayoría de los software incluye sin requerir mayor
configuración. A continuación, se indican algunos de estos parámetros:

• PARÁMETROS DE TAMAÑO
(TDI1-B: Propiedades Físicas de Objetos y Elementos)

Cubicaciones Base
Ancho / Alto / Largo /
Área total / Volumen total

• PARÁMETROS DE POSICIONAMIENTO
(TDI-C: Propiedades Geográficas y de Localización Espacial de Objetos & Elementos)

Punto 0.00
Tipo de posición Coordenadas Número de Piso
Absoluto/Relativo/ X/Y/Z ZZ/01/E1/S1
Referencia de
cuadrícula

• PARÁMETROS DE ESPECIFICACIÓN
(TDI-D: Requerimientos Específicos de Información para el Fabricante)

ID:0298
\-Panel
\-Madera

Identificación
ID / Nombre / Material

1 Tipo de Información BIM (TDI): Grupo de datos que pueden estar contenidos en los modelos. Planbim, Estándar BIM para Proyectos Públicos,
junio de 2019, 28.
5

<!-- p. 6 -->

ENTIDADES DE UN MODELO DE SITIO

A continuación, se listan las entidades que, de ser parte de un proyecto, deben ser incluidas en el modelo BIM de Sitio, según
lo indicado en el Estándar BIM para Proyectos Públicos. Estas entidades se detallan en la presente Guía:

• Terreno (IfcSite)
• Elementos Civiles (IfcCivilElement)*
• Elementos Geográficos (IfcGeographicElement)*
• Fundaciones (IfcFooting)*
• Zonas (IfcZone)
• Espacios (IfcSpace)
• Columnas (IfcColumn)*
• Vigas (IfcBeam)*
• Losas / Radier (IfcSlab)*
• Muros (IfcWall)*
• Muros Cortina (IfcCurtainWall)*
• Cubiertas / Techumbres (IfcRoof)*

Es importante indicar que las entidades abstractas Proyecto (IfcProject) y Edificio (IfcBuilding) se incluyen automáticamente en
todos los modelos BIM, y contienen información general del proyecto. Los parámetros específicos de estas entidades se detallan
en la Matriz de Información de Entidades, disponible en https://planbim.cl/biblioteca/documentos/.

\*Entidades sugeridas, según el tipo de modelo.

6

<!-- p. 7 -->

Índice de Entidades de modelos BIM de Sitio

Introducción .................................................................................................................................................................................................. 3

Entidad: Terreno (IfcSite) .............................................................................................................................................................................. 8

Entidad: Elementos Civiles (IfcCivilElement) ............................................................................................................................................... 9

Entidad: Elementos Geográficos (IfcGeographicElement) ................................................................................................................... 10

Entidad: Fundaciones (IfcFooting)* .......................................................................................................................................................... 11

Entidad: Zonas / Espacios (IfcZone-IfcSpace) ......................................................................................................................................... 13

Entidad: Columnas (IfcColumn)* .............................................................................................................................................................. 16

Entidad: Vigas (IfcBeam)* .......................................................................................................................................................................... 17

Entidad: Losas / Radier (IfcSlab)* .............................................................................................................................................................. 18

Entidad: Muros (IfcWall)* ............................................................................................................................................................................ 19

Entidad: Muros Cortina (IfcCurtainWall)* ................................................................................................................................................. 21

Entidad: Cubiertas / Techumbres (IfcRoof)* ............................................................................................................................................ 22

7

<!-- p. 8 -->

Entidad: Terreno (IfcSite)

Terreno (IfcSite)

Un IfcSite es un área de terreno definida, que puede estar o no cubierta de agua, en la cual se debe desarrollar la construcción
del proyecto. Se puede usar un sitio para construir, modernizar o demoler edificios, o para otros desarrollos relacionados con la
construcción.

RECOMENDACIONES

Un sitio puede incluir una definición del punto de referencia geográfico único para este sitio (posición global usando WGS84
con longitud, latitud y elevación). La precisión se proporciona hasta una millonésima de segundo y provee una ubicación
absoluta en relación con el mundo real tal como se usa en intercambios con sistemas de información geoespacial. Si se
establece la longitud, la latitud y la elevación, estos fijan el punto en WGS84 donde se sitúa el punto 0., 0., 0. del
LocalPlacement de IfcSite.

Un proyecto puede abarcar varios sitios conectados o desconectados. Por lo tanto, el complejo de sitios proporciona una
colección de sitios incluidos en un proyecto. Un sitio también se puede descomponer en partes, donde cada parte define
una sección del sitio. Esto se define por el atributo de tipo de composición de la entidad IfcSpatialStructureElements8 que se
interpreta de la siguiente manera:

COMPLEJO = complejo de sitios

ELEMENTO = sitio

PARCIAL = sección del sitio

Para una georreferenciación exacta (o referencia a cualquier otro sistema de coordenadas geográficas que no sea WSG84),
las entidades IfcCoordinateReferenceSystem2 e IfcMapConversion3 deben usarse para definir una asignación exacta del
sistema de coordenadas de ingeniería del proyecto al sistema de coordenadas geográficas (o de mapas).

2 Entidad abstracta no indicada en el Estándar BIM para Proyectos Públicos ni en la Matriz de Información de Entidades, por lo que su
información se puede revisar en:
https://standards.buildingsmart.org/IFC/RELEASE/IFC4/ADD2_TC1/HTML/schema/ifcrepresentationresource/lexical/ifccoordinatereferencesyste
m.htm.
3 Entidad abstracta no indicada en el Estándar BIM para Proyectos Públicos ni en la Matriz de Información de Entidades, por lo que su
información se puede revisar en:
https://standards.buildingsmart.org/IFC/RELEASE/IFC4/ADD2_TC1/HTML/schema/ifcrepresentationresource/lexical/ifcmapconversion.htm.
8

<!-- p. 9 -->

Entidad: Elementos Civiles (IfcCivilElement)

Elementos Civiles (IfcCivilElement)

Un IfcCivilElement es una generalización de todos los elementos dentro de una obra de ingeniería civil. Incluye, en particular,
todos los casos de obras de construcción lineales típicas, como segmentos de carreteras, segmentos de puentes, aceras, etc.
Dependiendo del contexto del proyecto de construcción, los trabajos de construcción incluidos, como edificios o fábricas, se
representan como una colección de elementos de IfcBuildingElement4, los sistemas de distribución, tales como tuberías o
drenaje, se representan como una colección de elementos de IfcDistributionElement5, y otros elementos geográficos, tales
como árboles, postes de luz, señales de tráfico, etc., se representan como elementos de elementos de IfcGeographicElement
(ver pág. 10).

NOTA: IfcCivilElement se ha introducido como un código auxiliar para futuras extensiones de esta especificación para incluir un
modelo de objeto para obras de ingeniería civil.

RECOMENDACIONES

Los elementos civiles generalmente se organizan horizontalmente utilizando una estructura espacial expresada por zonas, por
lo tanto, IfcCivilElement está contenido por defecto dentro de una IfcSpatialZone6.

\*Entidad sugerida, según el tipo de modelo

4 Entidad abstracta no indicada en el Estándar BIM para Proyectos Públicos ni en la Matriz de Información de Entidades, por lo que su
información se puede revisar en:
https://standards.buildingsmart.org/IFC/RELEASE/IFC4/ADD2_TC1/HTML/schema/ifcproductextension/lexical/ifcbuildingelement.htm.
5 Entidad abstracta no indicada en el Estándar BIM para Proyectos Públicos ni en la Matriz de Información de Entidades, por lo que su
información se puede revisar en:
https://standards.buildingsmart.org/IFC/RELEASE/IFC4/ADD2_TC1/HTML/schema/ifcproductextension/lexical/ifcdistributionelement.htm.
6 Entidad abstracta no indicada en el Estándar BIM para Proyectos Públicos ni en la Matriz de Información de Entidades, por lo que su
información se puede revisar en:
https://standards.buildingsmart.org/IFC/RELEASE/IFC4/ADD2_TC1/HTML/schema/ifcproductextension/lexical/ifcspatialzone.htm.
9

<!-- p. 10 -->

Entidad: Elementos Geográficos (IfcGeographicElement)

Elementos Geográficos (IfcGeographicElement)

Un IfcGeographicElement es una generalización de todos los elementos dentro de un paisaje geográfico. Incluye instancias de
elementos geográficos típicos, a menudo denominados características. Estas pueden ser características puntuales como
asientos, marquesinas de autobuses, señalización, árboles; características lineales como apartaderos (layby); y características
del área como estanques, lagos y bosques; drenaje como captación, embalse o emisario.

TABLA 02.-TIPOS PREDEFINIDOS ELEMENTOS GEOGRÁFICOS (IfcGeographicElementTypeEnum)

NOMBRE TRADUCCIÓN DESCRIPCIÓN

TERRAIN Terreno Sin definición por parte de IFC

USERDEFINED Definido por usuario Tipo definido por el usuario.

NOTDEFINED No definido Tipo indefinido.

Nota

Es importante indicar que la entidad IfcGeographicElement puede representar un terreno general y la entidad Terreno
(IfcSite) representa el sitio específico del proyecto, tal como se muestra en el ejemplo:

IfcSite

IfcGeographicElement

Fig.01

\*Entidad sugerida, según el tipo de modelo.

10

<!-- p. 11 -->

Entidad: Fundaciones (IfcFooting)*

Fundaciones (IfcFooting)

Un IfcFooting es una parte de los cimientos de una estructura que se extiende y transmite la carga al suelo. Un IfcFooting también
se caracteriza como un cimiento poco profundo, donde las cargas se transfieren al suelo cerca de la superficie.

TABLA 03.- TIPOS PREDEFINIDOS FUNDACIONES (IfcFootingTypeEnum)

REPRESENTACIÓN
NOMBRE TRADUCCIÓN DESCRIPCIÓN GRÁFICA

Fig.02

Cajón de Un tipo de cimientos utilizado en la construcción
CAISSON_FOUNDATION
cimentación submarina.

Elementos de fundación que trabajan a flexión y se Fig.03
apoyan fuera del suelo. Normalmente se extienden
entre pilares, pilotes o dados de fundación. Se
distinguen de las vigas en la superestructura del
Viga de edificio, ya que normalmente requieren un menor
FOOTING_BEAM
fundación grado de acabado. Se distinguen de una fundación
corrida (STRIP_FOOTING) ya que están fuera de la
superficie del terreno y, por lo tanto, requieren soporte
en la cara inferior mientras el concreto se está
fraguando.

Fig.04

Fundación Un elemento que transfiere la carga de una o dos
PAD_FOOTING
aislada columnas al suelo.

Fig.05

Un elemento que transfiere la carga de una columna
PILE_CAP Encepado
o grupo de columnas a uno o varios pilares o pilotes.

Fig.06
Un elemento lineal que transfiere cargas al suelo desde
Fundación
STRIP_FOOTING un elemento continuo, como un muro, o desde una
corrida
serie de elementos, como columnas.

Definido por Cualquier tipo de fundación que no pertenezca a las
USERDEFINED
usuario categorías anteriores.

NOTDEFINED No definido Aún no se define el tipo de fundación.

\*Entidad sugerida, según el tipo de modelo.

11

<!-- p. 12 -->

Nota

Las losas de fundación no son representadas con la entidad IfcFooting, sino que utilizan la entidad IfcSlab (ver pág. 18) y su
tipo predefinido BASESLAB. Las fundaciones profundas que transfieren cargas a capas del subsuelo se representan con la
entidad IfcPile7.

7 Entidad indicada en la Ficha de Entidades IFC para Puentes. Su información se puede revisar en: https://planbim.cl/ficha-de-entidades-ifcpara-puentes/
12

<!-- p. 13 -->

Entidad: Zonas / Espacios (IfcZone-IfcSpace)

Zonas (IfcZone)

Una IfcZone es un grupo de espacios, espacios parciales u otras zonas. Las estructuras de zona pueden no ser jerárquicas (al
contrario de la estructura espacial de un proyecto), es decir, un IfcSpace (ver pág.14) individual puede estar asociado con
uno, varios o a ningún IfcZone.

Nota

Es importante indicar que esta entidad (IfcZone) es abstracta, por lo tanto, no tiene geometría en sí misma, sino que se
conforma a través de la asociación de entidades de Espacios (IfcSpace) a estas Zonas. A estas últimas se les puede asignar
nombres de puntos cardinales, tipos de recintos, sectores de la edificación o infraestructura. En la siguiente imagen se muestra
un ejemplo:

A (norte) B (norte) C (norte)
G (oeste) I (este) Espacios (IfcSpace) nombrados
con Letras (fig.7) D (sur) E (sur) F (sur)
Zonas (IfcZone) nombrados con
Puntos cardinales(fig.7)
Fig.7

Uno de los propósitos de la entidad IfcZone es definir la compartimentación contra incendios. En este caso, define la
información geométrica de esta compartimentación a través de los espacios contenidos, y la información sobre ventilación
o protección con aspersores. Si se utiliza esta entidad para representar compartimentación contra incendio, se debe utilizar
uno de los siguientes tipos como valores en el atributo ObjectType:

• FireCompartment (Compartimiento contra incendio): Una zona de espacios agrupados para representar una
compartimentación contra incendio.

• ElevatorShaft (Caja de ascensor): Un grupo de espacios dentro de una caja de ascensor, que pueden atravesar
varios pisos.

• RisingDuct (Ducto vertical): Una colección de espacios verticales para la circulación de aire.

• RunningDuct (Ducto horizontal): Una colección de espacios horizontales para la circulación de aire.

13

<!-- p. 14 -->

Entidad: Zonas / Espacios (IfcZone-IfcSpace)

Espacios (IfcSpace)

Un IfcSpace representa un área o volumen acotado o teóricamente limitado. Los espacios son áreas o volúmenes que
proporcionan ciertas funciones dentro de un edificio. Los espacios están asociados a pisos o niveles (o, en el caso de espacios
exteriores, a un sitio).

Un IfcSpace puede abarcar varios espacios conectados. Por lo tanto, un grupo de espacios IfcSpace proporciona una
colección de espacios incluidos en un piso o nivel.

Un IfcSpace también se puede descomponer en partes, donde cada parte define una sección del espacio. Esto se define por
el atributo de tipo de composición de la entidad IfcSpatialStructureElements8 que se interpreta de la siguiente manera:

COMPLEJO = complejo de espacios

ELEMENTO = espacio

PARCIAL = sección del espacio

TABLA 04.- TIPOS PREDEFINIDOS ESPACIOS (IfcSpaceTypeEnum)

REPRESENTACIÓN
NOMBRE TRADUCCIÓN DESCRIPCIÓN GRÁFICA

Fig.08

A02 A01 SPACE Espacio Cualquier espacio que no corresponda a otra categoría.

Fig.09
Un espacio dedicado para usar como un lugar de
PARKING Estacionamiento estacionamiento para vehículos, incluido el acceso a este, ES01
como un pasillo de estacionamiento.

Fig.10
Área bruta de piso (GFA por sus siglas en inglés Gross Floor
Area): es un tipo específico de espacio para cada piso del
edificio que incluye toda el área neta y el área de
GFA Área bruta
construcción (también la envoltura externa). La provisión de
un espacio tan específico a menudo es requerida por las
regulaciones.

INTERNAL Interno Sin definición por parte de IFC

8 Entidad abstracta no indicada en el Estándar BIM para Proyectos Públicos ni en la Matriz de Información de Entidades. Su información se
puede revisar en:
https://standards.buildingsmart.org/IFC/RELEASE/IFC4/ADD2_TC1/HTML/schema/ifcproductextension/lexical/ifcspatialstructureelement.htm.
14

<!-- p. 15 -->

TABLA 04.- TIPOS PREDEFINIDOS ESPACIOS (IfcSpaceTypeEnum)

REPRESENTACIÓN
NOMBRE TRADUCCIÓN DESCRIPCIÓN GRÁFICA

EXTERNAL Externo Sin definición por parte de IFC

Definido por
USERDEFINED Tipo definido por el usuario.
usuario

NOTDEFINED No definido Tipo indefinido.

El siguiente esquema describe las alturas y elevaciones de un IfcSpace:

a) Elevación del espacio sobre el nivel tope de losa,
especificado por IfcBuildingStorey.Elevation relativo a
IfcBuilding.ElevationOfRefHeight.
b) Elevación del piso terminado (NPT) del espacio,
especificado por IfcSpace.ElevationWithFlooring relativo
a IfcBuilding.ElevationOfRefHeight.
c) Espesor del piso del espacio (desde el nivel superior de la
losa inferior al nivel de piso terminado), especificado por
BaseQuantity de nombre FinishFloorHeight.
d) Altura neta del espacio (desde nivel de piso terminado a
nivel inferior de cielo), especificado por BaseQuantity de
nombre FinishCeilingHeight
e) Altura del espacio (desde nivel superior de losa inferior al
nivel inferior de losa superior), especificado por
BaseQuantity de nombre Height.

Fig.11 Figura basada en la figura 183, Space Elevations elaborada
por buildingSMART International.

https://standards.buildingsmart.org/IFC/RELEASE/IFC4/ADD2_TC1/
HTML/schema/ifcproductextension/lexical/ifcspace.htm.

15

<!-- p. 16 -->

Entidad: Columnas (IfcColumn)*

Columnas (IfcColumn)

Un IfcColumn es un miembro estructural vertical o casi vertical que a menudo está alineado con una intersección de la
cuadrícula estructural. Es una representación de un miembro estructural que transmite, a través de la compresión, el peso de
la estructura superior a otros elementos estructurales que están por debajo de él. Dado que esta representación es generada
desde un punto de vista arquitectónico, no es necesario que sea un elemento de carga.

TABLA 05.- TIPOS PREDEFINIDOS COLUMNAS (IfcColumnTypeEnum)

REPRESENTACIÓN
NOMBRE TRADUCCIÓN DESCRIPCIÓN GRÁFICA

Fig.12
Un miembro estándar, generalmente vertical, que resiste a
COLUMN Columna las fuerzas verticales por compresión, pero en ocasiones
también a las fuerzas laterales.

Fig.13
Un elemento de columna incrustado dentro de un muro. Se
PILASTER Pilastra puede requerir que este elemento soporte carga, pero
también se puede usar solo con fines decorativos.

Definido por Tipo definido por el usuario. Aplicable a categorías de
USERDEFINED
usuario columnas no listadas anteriormente.

Tipo indefinido. Aplicable cuando el tipo de columna no está
NOTDEFINED No definido
definido aún.

\*Entidad sugerida, según el tipo de modelo.

16

<!-- p. 17 -->

Entidad: Vigas (IfcBeam)*

Vigas (IfcBeam)

Un IfcBeam es un miembro estructural horizontal o casi horizontal que es capaz de soportar la carga principalmente resistiendo
la flexión. Dado que esta representación es generada desde un punto de vista arquitectónico, no es necesario que sea un
elemento de carga.

TABLA 06.- TIPOS PREDEFINIDOS VIGAS (IfcBeamTypeEnum)

REPRESENTACIÓN
NOMBRE TRADUCCIÓN DESCRIPCIÓN GRÁFICA

Fig.14

BEAM Viga Una viga estándar, usualmente utilizada horizontalmente.

Fig.15

JOIST Vigueta Una viga utilizada para soportar un piso o techo.

Fig.16
Una viga ancha a menudo pretensada con un perfil de
HOLLOWCORE Hueca núcleo hueco que generalmente sirve como componente
de una losa.

Fig.17

Una viga o elemento horizontal sobre una abertura (por
LINTEL Dintel
ejemplo, puerta, ventana).

Fig.18

Una viga alta en la fachada de un edificio. Puede usarse
SPANDREL Coronación
para apoyar viguetas o elementos de losa en su lado interior.

Una viga que forma parte de una construcción de losa y Fig.19
actúa junto con la losa que soporta. Tales vigas a menudo
T_BEAM Viga T tienen forma de T (de aquí viene su nombre), pero también
pueden tener otras formas, por ejemplo, forma de L o de T
invertida.

Definido por Tipo definido por el usuario. Aplicable a categorías de vigas
USERDEFINED
usuario no listadas anteriormente.

Tipo indefinido. Aplicable cuando el tipo de viga no está
NOTDEFINED No definido
definido aún.

\*Entidad sugerida, según el tipo de modelo.

17

<!-- p. 18 -->

Entidad: Losas / Radier (IfcSlab)*

Losas (IfcSlab)

Un IfcSlab es un componente de construcción que normalmente encierra un espacio verticalmente. La losa puede
proporcionar el soporte inferior (piso) o la construcción superior (losa del techo) en cualquier espacio de un edificio. Sólo la
parte central de este elemento es considerado una losa. Los acabados superior e inferior se representan a través de la entidad
IfcCovering. Para más información sobre la entidad IfcCovering y sus tipos predefinidos, se sugiere revisar la Guía de Entidades
IFC Arquiectura, disponible en https://planbim.cl/biblioteca/documentos/.

TABLA 07.- TIPOS PREDEFINIDOS LOSAS (IfcSlabTypeEnum)

REPRESENTACIÓN
NOMBRE TRADUCCIÓN DESCRIPCIÓN GRÁFICA

Fig.20

FLOOR Piso Se utiliza para representar una losa de piso.

Fig.21

Se utiliza para representar una losa del techo (ya sea plana
ROOF Techo
o inclinada).

Fig.22

Se utiliza para representar un descanso dentro de una
LANDING Descanso
escalera o rampa.

Fig.23

Se utiliza para representar una losa de piso contra el suelo (y,
BASESLAB Radier por lo tanto, forma parte de la cimentación). Esta losa
también recibe el nombre de radier.

Definido por Tipo definido por el usuario. Aplicable a categorías de losas
USERDEFINED
usuario no listadas anteriormente.

Tipo indefinido. Aplicable cuando el tipo de losa no está
NOTDEFINED No definido
definido aún.

\*Entidad sugerida, según el tipo de modelo.

18

<!-- p. 19 -->

Entidad: Muros (IfcWall)*

Muros (IfcWall)

Un IfcWall representa una construcción vertical que delimita o subdivide espacios. Los muros suelen ser elementos planos,
verticales o casi verticales, a menudo diseñados para soportar cargas estructurales. Sin embargo, también existen muros que
no cumplen una función estructural.

TABLA 08.- TIPOS PREDEFINIDOS MUROS (IfcWallTypeEnum)

REPRESENTACIÓN
NOMBRE TRADUCCIÓN DESCRIPCIÓN GRÁFICA

Que se puede mover, como un muro plegable o deslizante, Fig.24
o se puede quitar fácilmente como un tabique removible o
MOVABLE Móvil de montaje. Los muros móviles normalmente no definen los
límites del espacio y, a menudo, pertenecen al sistema de
mobiliario.

Fig.25
Una barrera similar a un muro para proteger a los ocupantes
humanos de la caída, o para evitar la propagación de
PARAPET Antepecho
incendios. A menudo son diseñados en el borde de
balcones, terrazas o techos.

Fig.26
Un muro diseñado para dividir espacios, que a menudo tiene
una construcción liviana, similar a un sándwich (por ejemplo,
PARTITIONING División
utilizando una placa de yeso). Estos muros normalmente no
soportan carga.

Fig.27

Muros de cierre, normalmente utilizado para contener
PLUMBINGWALL Muro sanitario tuberías en cuartos sanitarios. Estos a menudo no se
extienden hasta el techo.

Un muro diseñado para soportar cargas cortantes. Están Fig.28
diseñados a menudo con una sección transversal no
rectangular a lo largo del recorrido del muro. También
SHEAR Muro de Corte
llamados muros de contención o muros de apoyo se usan
para proteger contra las capas de suelo que se encuentran
detrás.

Una construcción de muro macizo cuyo núcleo es de capa Fig.29
única o tiene varias capas unidas. A menudo son de
SOLIDWALL Muro sólido mampostería o de concreto (ambos moldeados in situ o
prefabricados), soportan carga y protegen contra
incendios.

19

<!-- p. 20 -->

TABLA 08.- TIPOS PREDEFINIDOS MUROS (IfcWallTypeEnum)

REPRESENTACIÓN
NOMBRE TRADUCCIÓN DESCRIPCIÓN GRÁFICA

Fig.30

Un muro estándar, extruido verticalmente con un espesor
STANDARD Estándar
constante a lo largo de la trayectoria del muro.

Fig.31

Un muro enmarcado con montantes y revestido con láminas,
ELEMENTEDWALL Muro compuesto
revestimientos, paneles o yeserías.

Definido por Tipo definido por el usuario. Aplicable a categorías de muros
USERDEFINED
usuario no listadas anteriormente.

Tipo indefinido. Aplicable cuando el tipo de muro no está
NOTDEFINED No definido
definido aún.

\*Entidad sugerida, según el tipo de modelo.

20

<!-- p. 21 -->

Entidad: Muros Cortina (IfcCurtainWall)*

Muros Cortina (IfcCurtainWall)

Un IfcCurtainWall es un muro exterior de un edificio, formado por un conjunto de componentes, que está colgado desde el
borde de la estructura de losa / techo en lugar de apoyarse en la losa. Los tipos predefinidos para esta entidad aún no se han
especificado en la norma ISO, pero sí se incluyó en esta un listado genérico para ser extendido en futuras versiones del esquema
IFC.

TABLA 09.- TIPOS PREDEFINIDOS MUROS CORTINA (IfcCurtainWallTypeEnum)

REPRESENTACIÓN
NOMBRE TRADUCCIÓN DESCRIPCIÓN GRÁFICA

USERDEFINED Definido por usuario Tipo definido por el usuario.

NOTDEFINED No definido Tipo indefinido.

\*Entidad sugerida, según el tipo de modelo.

21

<!-- p. 22 -->

Entidad: Cubiertas / Techumbres (IfcRoof)*

Cubiertas / Techumbres (IfcRoof)

Un IfcRoof es la cubierta de la parte superior de una edificación. Esta protege la edificación de los efectos del clima.

TABLA 10.- TIPOS PREDEFINIDOS CUBIERTAS/TECHUMBRES (IfcRoofTypeEnum)

REPRESENTACIÓN
NOMBRE TRADUCCIÓN DESCRIPCIÓN GRÁFICA

Fig.32

Un techo sin pendiente, o con solo una leve
FLAT_ROOF Techo plano
inclinación para drenar el agua de lluvia.

Fig.33

Techo a un
SHED_ROOF Un techo de una sola pendiente.
agua

Fig.34

Un techo inclinado hacia abajo en dos partes desde
Techo a dos
GABLE_ROOF una arista central, para formar un alero en cada
aguas
extremo.

Fig.35

Techo a cuatro Un techo con extremos inclinados y lados que se unen
HIP_ROOF
aguas en un ángulo de proyección inclinado.

Fig.36

Tejado a cuatro Un techo a cuatro aguas que tiene un extremo
HIPPED_GABLE_ROOF
aguas aguilón truncando a un faldón.

Fig.37

Techo Un techo con aristas dividido en cada lado en una
GAMBREL_ROOF
abuhardillado pendiente más baja sobre una más empinada.

Fig.38

Un techo que tiene en cada lado una parte inferior
MANSARD_ROOF Techo Mansarda más empinada y una parte superior de menor
inclinación.

22

<!-- p. 23 -->

TABLA 10.- TIPOS PREDEFINIDOS CUBIERTAS/TECHUMBRES (IfcRoofTypeEnum)

REPRESENTACIÓN
NOMBRE TRADUCCIÓN DESCRIPCIÓN GRÁFICA

Fig.39

Bóveda de
BARREL_ROOF Un techo de forma semicilíndrica.
cañón

Fig.40

Un techo a dos aguas en forma de un amplio arco
Techo arco
RAINBOW_ROOF gótico, con superficies convexas suavemente
gótico
inclinadas.

Fig.41

Un techo que tiene dos pendientes, cada una
BUTTERFLY_ROOF Techo invertido
descendiendo hacia adentro desde los aleros.

Fig.42

PAVILION_ROOF Techo piramidal Un techo piramidal.

Fig.43

DOME_ROOF Domo Un techo hemisférico.

FREEFORM Techo libre Techo de forma libre

Definido por Tipo definido por el usuario. Aplicable a tipos de
USERDEFINED
usuario techumbre no listados anteriormente.

Tipo indefinido. Aplicable cuando el tipo de
NOTDEFINED No definido
techumbre no está definido aún.

\*Entidad sugerida, según el tipo de modelo.

23

<!-- p. 24 -->

www.planbim.cl

in

24
