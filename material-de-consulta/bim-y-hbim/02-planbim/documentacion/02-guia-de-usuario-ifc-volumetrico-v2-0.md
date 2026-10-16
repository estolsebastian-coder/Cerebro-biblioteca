---
type: libro
title: "02_GUÍA DE USUARIO IFC VOLUMÉTRICO_V2.0"
author: "Sebastian Manriquez Fuentealba"
categoria: "BIM Y HBIM"
paginas: 15
extraccion: "texto"
fuente: "local:E:/MATERIAL DE CONSULTA/BIM Y HBIM/02. Planbim/documentación/02_GUÍA DE USUARIO IFC VOLUMÉTRICO_V2.0.pdf"
convertido: 2026-10-16
---

# 02_GUÍA DE USUARIO IFC VOLUMÉTRICO_V2.0

> Texto extraído de `BIM Y HBIM\02. Planbim\documentación\02_GUÍA DE USUARIO IFC VOLUMÉTRICO_V2.0.pdf` (15 páginas, texto). El PDF original está en el disco E: (MATERIAL DE CONSULTA); `<!-- p. N -->` marca el inicio de cada página.

<!-- p. 1 -->

GUÍA DE ENTIDADES IFC
MODELO VOLUMÉTRICO
Según ISO 16739-1:2018
VERSIÓN 2.0
OCTUBRE 2020

1

<!-- p. 2 -->

CONTROL DE VERSIONES

Versión Fecha Observaciones
1.0 Septiembre 2020
2.0 Octubre 2020 Se agrega nombre de enumeración en inglés a cada tabla de tipos

El contenido de esta guía es traducción directa de la ISO 16739-1:2018 publicada por buildingSMART International en la
página https://standards.buildingsmart.org/IFC/RELEASE/IFC4/ADD2_TC1/HTML/

2

<!-- p. 3 -->

La introducción, íconos de entidades e imágenes referenciales fueron desarrolladas por Planbim Chile.

Esta obra está licenciada bajo la Licencia Creative Commons
Atribución-NoComercial 4.0 Internacional.
Para ver una copia de esta licencia, visite http://creativecommons.org/licenses/by-nc/4.0/.

3

<!-- p. 4 -->

Introducción

OBJETIVO DE LA GUÍA

El presente documento tiene como objetivo apoyar la implementación del Estándar BIM para Proyectos Públicos desarrollado
por Planbim, en específico en la utilización del estándar abierto IFC para el intercambio de información de la industria de la
construcción. En él se describe cuáles entidades BIM deben ser utilizadas en un modelo BIM Volumétrico, y cuáles son los Tipo
Predefinidos que existen dentro de ellas. Para cada Tipo Predefinido, Planbim ha incluido su significado en español junto con
una imagen referencial, para facilitar la identificación del elemento constructivo al que cada uno de ellos representa.

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

4

<!-- p. 5 -->

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
https://planbim.cl/biblioteca/videos/.

5

<!-- p. 6 -->

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
6

<!-- p. 7 -->

ENTIDADES DE UN MODELO VOLUMÉTRICO

A continuación, se listan las entidades que, de ser parte de un proyecto, deben ser incluidas en el modelo BIM Volumétrico,
según lo indicado en el Estándar BIM para Proyectos Públicos. Estas entidades se detallan en la presente Guía:

• Terreno (IfcSite)
• Elementos Civiles (IfcCivilElement)*
• Elementos Geográficos (IfcGeographicElement)*
• Zonas (IfcZone)
• Espacios (IfcSpace)

Es importante recordar que las entidades abstractas Proyecto (IfcProject) y Edificio (IfcBuilding) se incluyen automáticamente
en todos los modelos BIM, y contienen información general del proyecto. Los parámetros específicos de estas entidades se
detallan en la Matriz de Información de Entidades, disponible en https://planbim.cl/biblioteca/documentos/.

\*Entidades sugeridas, según el tipo de modelo

7

<!-- p. 8 -->

Índice de Entidades de modelos BIM Volumétrico

Entidad: Terreno (IfcSite) .............................................................................................................................................................................. 9
Entidad: Elementos Civiles (IfcCivilElement)* ........................................................................................................................................... 10
Entidad: Elementos Geográficos (IfcGeographicElement)* .................................................................................................................. 11
Entidad: Zonas / Espacios (IfcZone-IfcSpace) ......................................................................................................................................... 12

8

<!-- p. 9 -->

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
una sección del sitio. Esto se define por el atributo de tipo de composición de la entidad IfcSpatialStructureElements7 que se
interpreta de la siguiente manera:

COMPLEJO = complejo de sitios

ELEMENTO = sitio

PARCIAL = sección del sitio

Para una georreferenciación exacta (o referencia a cualquier otro sistema de coordenadas geográficas que no sea
WSG84), las entidades IfcCoordinateReferenceSystem2 e IfcMapConversion3 deben usarse para definir una asignación
exacta del sistema de coordenadas de ingeniería del proyecto al sistema de coordenadas geográficas (o de mapas).

2 Entidad abstracta no indicada en el Estándar BIM para Proyectos Públicos ni en la Matriz de Información de Entidades, por lo que su
información se puede revisar en:
https://standards.buildingsmart.org/IFC/RELEASE/IFC4/ADD2_TC1/HTML/schema/ifcrepresentationresource/lexical/ifccoordinatereferencesyste
m.htm.
3 Entidad abstracta no indicada en el Estándar BIM para Proyectos Públicos ni en la Matriz de Información de Entidades, por lo que su
información se puede revisar en:
https://standards.buildingsmart.org/IFC/RELEASE/IFC4/ADD2_TC1/HTML/schema/ifcrepresentationresource/lexical/ifcmapconversion.htm.
9

<!-- p. 10 -->

Entidad: Elementos Civiles (IfcCivilElement)*

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

Los elementos civiles generalmente se organizan horizontalmente utilizando una estructura espacial expresada por zonas,
por lo tanto, IfcCivilElement está contenido por defecto dentro de una IfcSpatialZone6.

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
10

<!-- p. 11 -->

Entidad: Elementos Geográficos (IfcGeographicElement)*

Elementos Geográficos (IfcGeographicElement)

Un IfcGeographicElement es una generalización de todos los elementos dentro de un paisaje geográfico. Incluye instancias de
elementos geográficos típicos, a menudo denominados características. Estas pueden ser características puntuales como
asientos, marquesinas de autobuses, señalización, árboles; características lineales como apartaderos (layby); y características
del área como estanques, lagos y bosques; drenaje como captación, embalse o emisario.

TABLA 01.- TIPOS PREDEFINIDOS ELEMENTOS GEOGRÁFICOS (IfcGeographicElementTypeEnum)

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

\*Entidad sugerida, según el tipo de modelo

11

<!-- p. 12 -->

Entidad: Zonas / Espacios (IfcZone-IfcSpace)

Zonas (IfcZone)

Una IfcZone es un grupo de espacios, espacios parciales u otras zonas. Las estructuras de zona pueden no ser jerárquicas (al
contrario de la estructura espacial de un proyecto), es decir, un IfcSpace (ver pág.12) individual puede estar asociado con
uno, varios o a ningún IfcZone.

Nota

Es importante indicar que esta entidad (IfcZone) es abstracta, por lo tanto, no tiene geometría en sí misma, sino que se
conforma a través de la asociación de entidades de Espacios (IfcSpace) a estas Zonas. A estas últimas se les puede asignar
nombres de puntos cardinales, tipos de recintos, sectores de la edificación o infraestructura. En la siguiente imagen se muestra
un ejemplo:

A (norte) B (norte) C (norte)
G (oeste) I (este) Espacios (IfcSpace) nombrados
con Letras (fig.2) D (sur) E (sur) F (sur)
Zonas (IfcZone) nombrados con
Puntos cardinales(fig.2)
Fig.2

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

12

<!-- p. 13 -->

Entidad: Zonas / Espacios (IfcZone-IfcSpace)

Espacios (IfcSpace)

Un IfcSpace representa un área o volumen acotado o teóricamente limitado. Los espacios son áreas o volúmenes que
proporcionan ciertas funciones dentro de un edificio. Los espacios están asociados a pisos o niveles (o, en el caso de espacios
exteriores, a un sitio).

Un IfcSpace puede abarcar varios espacios conectados. Por lo tanto, un grupo de espacios IfcSpace proporciona una
colección de espacios incluidos en un piso o nivel.

Un IfcSpace también se puede descomponer en partes, donde cada parte define una sección del espacio. Esto se define por
el atributo de tipo de composición de la entidad IfcSpatialStructureElements7 que se interpreta de la siguiente manera:

COMPLEJO = complejo de espacios

ELEMENTO = espacio

PARCIAL = sección del espacio

TABLA 02.- TIPOS PREDEFINIDOS ESPACIOS (IfcSpaceTypeEnum)
REPRESENTACIÓN
NOMBRE TRADUCCIÓN DESCRIPCIÓN GRÁFICA

Fig.03
A02 A01 SPACE Espacio Cualquier espacio que no corresponda a otra categoría.

Fig.04
Un espacio dedicado para usar como un lugar de
PARKING Estacionamiento estacionamiento para vehículos, incluido el acceso a este, ES01
como un pasillo de estacionamiento.

Fig.05
Área bruta de piso (GFA por sus siglas en inglés Gross Floor
Area): es un tipo específico de espacio para cada piso del
edificio que incluye toda el área neta y el área de GFA Área bruta construcción (también la envoltura externa). La provisión de
un espacio tan específico a menudo es requerida por las
regulaciones.

INTERNAL Interno Sin definición por parte de IFC

7 Entidad abstracta no indicada en el Estándar BIM para Proyectos Públicos ni en la Matriz de Información de Entidades. Su información se
puede revisar en:
https://standards.buildingsmart.org/IFC/RELEASE/IFC4/ADD2_TC1/HTML/schema/ifcproductextension/lexical/ifcspatialstructureelement.htm.
13

<!-- p. 14 -->

TABLA 02.- TIPOS PREDEFINIDOS ESPACIOS (IfcSpaceTypeEnum)
REPRESENTACIÓN
NOMBRE TRADUCCIÓN DESCRIPCIÓN GRÁFICA

EXTERNAL Externo Sin definición por parte de IFC

Definido por USERDEFINED Tipo definido por el usuario. usuario

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

Fig.6 Figura basada en la figura 183, Space Elevations elaborada
por buildingSMART International.

https://standards.buildingsmart.org/IFC/RELEASE/IFC4/ADD2_TC1/
HTML/schema/ifcproductextension/lexical/ifcspace.htm.

14

<!-- p. 15 -->

www.planbim.cl

in

15
