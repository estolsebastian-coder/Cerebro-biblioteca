---
type: libro
title: "03_GUÍA DE USUARIO IFC ARQ_V2.2"
author: "Sebastian Manriquez Fuentealba"
categoria: "BIM Y HBIM"
paginas: 53
extraccion: "texto"
fuente: "local:E:/MATERIAL DE CONSULTA/BIM Y HBIM/02. Planbim/documentación/03_GUÍA DE USUARIO IFC ARQ_V2.2.pdf"
convertido: 2026-10-16
---

# 03_GUÍA DE USUARIO IFC ARQ_V2.2

> Texto extraído de `BIM Y HBIM\02. Planbim\documentación\03_GUÍA DE USUARIO IFC ARQ_V2.2.pdf` (53 páginas, texto). El PDF original está en el disco E: (MATERIAL DE CONSULTA); `<!-- p. N -->` marca el inicio de cada página.

<!-- p. 1 -->

GUÍA DE ENTIDADES IFC ARQUITECTURA
Según ISO 16739-1:2018

VERSIÓN 2.2

ENERO 2021

1

<!-- p. 2 -->

CONTROL DE VERSIONES

Versión Fecha Observaciones
1.0 Septiembre 2020
2.0 Octubre 2020 Se corrige nombre de TABLA 11 a TIPOS DE PARTICIÓN VENTANA
Se agrega TABLA 12.- TIPO DE OPERACIÓN VENTANA y se actualiza la numeración de todas las tablas y
figuras en adelante.
Se agrega nombre de enumeración en inglés a cada tabla de tipos.
2.1 Enero 2021 Se corrige error en la norma ISO citada en páginas 3 y 4.
2.2 Enero 2021 Se agrega Nota 2, correspondiente al parámetro de Resistencia al Fuego

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

El presente documento tiene como objetivo apoyar la implementación del Estándar BIM para Proyectos Públicos y la Matriz de
Información de Entidades desarrollados por Planbim, en específico en la utilización del estándar abierto IFC (ISO 16739-1:2018)
para el intercambio de información de la industria de la construcción. En esta guía se describe cuáles entidades BIM deben ser
utilizadas en un modelo BIM de Arquitectura, - que puede ser desarrollado por especialistas de esta disciplina, paisajismo o
iluminación - y cuáles son los Tipos Predefinidos que existen dentro de estas entidades. Para cada Tipo Predefinido, Planbim ha
traducido su significado al español y elaborado una imagen referencial, para facilitar la identificación del elemento
constructivo al que cada uno de ellos representa.

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
documentos se encuentran disponibles en https://planbim.cl/biblioteca/documentos/ para su descarga. La ISO 16739-1:2018
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
un listado de tipos preestablecidos. Este listado está definido en la ISO 16739-1:2018. Por ejemplo, la entidad Muro (IfcWall) tiene
10 tipos predefinidos, entre ellos están: Pilastra (PILASTER) y Columna (COLUMN).

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

ENTIDADES DE UN MODELO DE ARQUITECTURA

A continuación, se listan las entidades que, en caso de ser parte de un proyecto, deben ser incluidas en el modelo BIM de
Arquitectura, según lo indicado en el Estándar BIM para Proyectos Públicos. Estas entidades se detallan en la presente Guía:

• Ejes (IfcGrid)
• Terreno (IfcSite)
• Elementos Civiles (IfcCivilElement)
• Elementos Geográficos (IfcGeographicElement)
• Fundaciones (IfcFooting)
• Zonas (IfcZone)
• Espacios (IfcSpace)
• Columnas (IfcColumn)
• Vigas (IfcBeam)
• Losas / Radier (IfcSlab)
• Muros (IfcWall)
• Muros Cortina (IfcCurtainWall)
• Ventanas (IfcWindow)
• Puertas (IfcDoor)
• Cubiertas / Techumbres (IfcRoof)
• Cielos Falsos / Acabados (IfcCovering)
• Sistemas de Circulación (IfcTransportElement)
• Escaleras (IfcStair)
• Rampas (IfcRamp)
• Equipos e Instalaciones Sanitarias (IfcSanitaryTerminal)
• Equipos e Instalaciones Médicas (IfcMedicalDevice)
• Muebles (IfcFurniture)
• Sistemas de Muebles (IfcSystemFurnitureElement)
• Estructuras Especiales (IfcElementAssembly)

Es importante indicar que las entidades abstractas Proyecto (IfcProject) y Edificio (IfcBuilding) se incluyen automáticamente en
todos los modelos BIM, y contienen información general del proyecto. Los parámetros específicos de estas entidades se detallan
en la Matriz de Información de Entidades, disponible en https://planbim.cl/biblioteca/documentos/.

6

<!-- p. 7 -->

Índice de Entidades de modelos BIM de Arquitectura

Entidad: Ejes (IfcGrid) ................................................................................................................................................................................... 8
Entidad: Terreno (IfcSite) .............................................................................................................................................................................. 9
Entidad: Elementos Civiles (IfcCivilElement) ............................................................................................................................................. 10
Entidad: Elementos Geográficos (IfcGeographicElement) ................................................................................................................... 11
Entidad: Fundaciones (IfcFooting) ............................................................................................................................................................ 12
Entidad: Zonas / Espacios (IfcZone-IfcSpace) ......................................................................................................................................... 14
Entidad: Columnas (IfcColumn) ................................................................................................................................................................ 17
Entidad: Vigas (IfcBeam) ........................................................................................................................................................................... 18
Entidad: Losas / Radier (IfcSlab) ................................................................................................................................................................ 19
Entidad: Muros (IfcWall).............................................................................................................................................................................. 20
Entidad: Muros Cortina (IfcCurtainWall) ................................................................................................................................................... 22
Entidad: Ventanas (IfcWindow) ................................................................................................................................................................ 23
Entidad: Puertas (IfcDoor) .......................................................................................................................................................................... 28
Entidad: Cubiertas / Techumbres (IfcRoof) .............................................................................................................................................. 33
Entidad: Cielos Falsos-Acabados (IfcCovering) ...................................................................................................................................... 35
Entidad: Sistemas de Circulación / Escaleras / Rampas (IfcTransportElement-IfcStair-IfcRamp) ...................................................... 37
Entidad: Equipos e instalaciones (IfcSanitayTerminal-IfcMedicalDevice-IfcLamp) ............................................................................. 41
Entidad: Muebles (IfcFurniture-IfcSystemFurnitureElement) .................................................................................................................... 46
Entidad: Estructuras Especiales (IfcElementAssembly) ............................................................................................................................ 48
Nota 1: Elementos compuestos ................................................................................................................................................................. 50
Nota 2: Resistencia al fuego en entidades .............................................................................................................................................. 52

7

<!-- p. 8 -->

Entidad: Ejes (IfcGrid)

Ejes (IfcGrid)

Un IfcGrid es una cuadrícula de diseño plano definida en el espacio 3D que se utiliza como apoyo para localizar elementos
estructurales y de diseño. La posición de la cuadrícula (ObjectPlacement) se define mediante un sistema de coordenadas 3D
(y por lo tanto, se puede usar en planta, sección o en cualquier posición relativa al sistema de coordenadas mundial). Esta
posición puede ser relativa a la de otras entidades o cuadrículas. El plano XY del sistema de coordenadas 3D se usa para
emplazar los ejes de la cuadrícula, que son curvas2 2D (por ejemplo, línea, círculo, arco, polilínea). En la siguiente tabla se
muestran los Tipos Predefinidos contenidos en IfcGrid:

TABLA 01.-TIPOS PREDEFINIDOS EJES (IfcGridTypeEnum)

NOMBRE TRADUCCIÓN DESCRIPCIÓN REPRESENTACIÓN GRÁFICA
Una IfcGrid con ejes en U y en V rectos, perpendiculares Fig.01
entre sí. Todos los ejes en U de la cuadrícula pueden
RECTANGULAR Rectangular describirse mediante una línea de eje y todos los demás
ejes son desplazamientos en 2D de esta línea de eje. Lo
mismo se aplica a todos los ejes en V de la cuadrícula.
Una IfcGrid con ejes en U rectos y ejes en V curvos. Fig.02
Todos los ejes en V de la cuadrícula tienen el mismo
RADIAL Radial punto central y son arcos circulares concéntricos. Todos
los ejes en U de la cuadrícula se cruzan en el mismo
punto central y giran en sentido antihorario.
Una IfcGrid con ejes U, ejes V y ejes W, siendo todos ejes Fig.03
co-lineales con un desplazamiento en 2D. Los ejes en V
TRIANGULAR Triangular están rotados a 60 grados en sentido antihorario desde
los ejes en U, y los ejes en W están rotados a 120 grados
en sentido antihorario desde los ejes en U.
Una IfcGrid con ejes U, ejes V y, opcionalmente, ejes W IRREGULAR Irregular que no pueden ser descritos a través de patrones.
Definido por Cualquier otra IfcGrid que no pertenezca a las USERDEFINED usuario categorías anteriores.

NOTDEFINED No definido Aún no se define el tipo de IfcGrid.

Figuras 01 a 03 basadas en las figuras elaboradas por buildingSMART International.
https://standards.buildingsmart.org/IFC/RELEASE/IFC4/ADD2_TC1/HTML/schema/ifcproductextension/lexical/ifcgrid.htm

Nota

Es importante indicar que esta entidad no cuenta con una ficha dentro de la Matriz de Información de Entidades, ya que solo
es necesario incluir la entidad entre los elementos exportados a IFC para que sus parámetros sean exportados de manera
automática.

En el caso de que se quiera dar más detalle, y si el software nativo lo permite, los parámetros (atributos heredados) Nombre
y Descripción se pueden usar para definir un nombre descriptivo de la cuadrícula e indicar el propósito de la cuadrícula.

Los tipos predefinidos indicados en la tabla anterior pueden ser utilizados si los equipos profesionales del proyecto cuentan
con los conocimientos y nivel de madurez BIM adecuado para su uso. Si no se cuenta con los conocimientos necesarios, estos
tipos predefinidos pueden ser omitidos, exportando las entidades sin esta información.

2 Definición de curva según ISO-10303-42: Una curva puede ser concebida como el recorrido de un punto moviéndose en su espacio
coordenado.
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
una sección del sitio. Esto se define por el atributo de tipo de composición de la entidad IfcSpatialStructureElements9 que se
interpreta de la siguiente manera:

COMPLEJO = complejo de sitios

ELEMENTO = sitio

PARCIAL = sección del sitio

Para una georreferenciación exacta (o referencia a cualquier otro sistema de coordenadas geográficas que no sea WSG84),
las entidades IfcCoordinateReferenceSystem3 e IfcMapConversion4 deben usarse para definir una asignación exacta del
sistema de coordenadas de ingeniería del proyecto al sistema de coordenadas geográficas (o de mapas).

3 Entidad abstracta no indicada en el Estándar BIM para Proyectos Públicos ni en la Matriz de Información de Entidades, por lo que su
información se puede revisar en:
https://standards.buildingsmart.org/IFC/RELEASE/IFC4/ADD2_TC1/HTML/schema/ifcrepresentationresource/lexical/ifccoordinatereferencesyste
m.htm.
4 Entidad abstracta no indicada en el Estándar BIM para Proyectos Públicos ni en la Matriz de Información de Entidades, por lo que su
información se puede revisar en:
https://standards.buildingsmart.org/IFC/RELEASE/IFC4/ADD2_TC1/HTML/schema/ifcrepresentationresource/lexical/ifcmapconversion.htm.
9

<!-- p. 10 -->

Entidad: Elementos Civiles (IfcCivilElement)

Elementos Civiles (IfcCivilElement)

Un IfcCivilElement es una generalización de todos los elementos dentro de una obra de ingeniería civil. Incluye, en particular,
todos los casos de obras de construcción lineales típicas, como segmentos de carreteras, segmentos de puentes, aceras, etc.
Dependiendo del contexto del proyecto de construcción, los trabajos de construcción incluidos, como edificios o fábricas, se
representan como una colección de elementos de IfcBuildingElement5, los sistemas de distribución, tales como tuberías o
drenaje, se representan como una colección de elementos de IfcDistributionElement6, y otros elementos geográficos, tales
como árboles, postes de luz, señales de tráfico, etc., se representan como elementos de elementos de IfcGeographicElement
(ver pág. 11).

NOTA: IfcCivilElement se ha introducido como un código auxiliar para futuras extensiones de esta especificación para incluir un
modelo de objeto para obras de ingeniería civil.

RECOMENDACIONES

Los elementos civiles generalmente se organizan horizontalmente utilizando una estructura espacial expresada por zonas, por
lo tanto, IfcCivilElement está contenido por defecto dentro de una IfcSpatialZone7.

5 Entidad abstracta no indicada en el Estándar BIM para Proyectos Públicos ni en la Matriz de Información de Entidades, por lo que su
información se puede revisar en:
https://standards.buildingsmart.org/IFC/RELEASE/IFC4/ADD2_TC1/HTML/schema/ifcproductextension/lexical/ifcbuildingelement.htm.
6 Entidad abstracta no indicada en el Estándar BIM para Proyectos Públicos ni en la Matriz de Información de Entidades, por lo que su
información se puede revisar en:
https://standards.buildingsmart.org/IFC/RELEASE/IFC4/ADD2_TC1/HTML/schema/ifcproductextension/lexical/ifcdistributionelement.htm.
7 Entidad abstracta no indicada en el Estándar BIM para Proyectos Públicos ni en la Matriz de Información de Entidades, por lo que su
información se puede revisar en:
https://standards.buildingsmart.org/IFC/RELEASE/IFC4/ADD2_TC1/HTML/schema/ifcproductextension/lexical/ifcspatialzone.htm.
10

<!-- p. 11 -->

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

Fig.04

11

<!-- p. 12 -->

Entidad: Fundaciones (IfcFooting)

Fundaciones (IfcFooting)

Un IfcFooting es una parte de los cimientos de una estructura que se extiende y transmite la carga al suelo. Un IfcFooting también
se caracteriza como un cimiento poco profundo, donde las cargas se transfieren al suelo cerca de la superficie.

TABLA 03.- TIPOS PREDEFINIDOS FUNDACIONES (IfcFootingTypeEnum)

REPRESENTACIÓN NOMBRE TRADUCCIÓN DESCRIPCIÓN GRÁFICA
Fig.05

Cajón de Un tipo de cimientos utilizado en la construcción CAISSON_FOUNDATION cimentación submarina.

Elementos de fundación que trabajan a flexión y se Fig.06
apoyan fuera del suelo. Normalmente se extienden
entre pilares, pilotes o dados de fundación. Se
distinguen de las vigas en la superestructura del
Viga de edificio, ya que normalmente requieren un menor FOOTING_BEAM fundación grado de acabado. Se distinguen de una fundación
corrida (STRIP_FOOTING) ya que están fuera de la
superficie del terreno y, por lo tanto, requieren soporte
en la cara inferior mientras el concreto se está
fraguando.

Fig.07

Fundación Un elemento que transfiere la carga de una o dos PAD_FOOTING aislada columnas al suelo.

Fig.08

Un elemento que transfiere la carga de una columna PILE_CAP Encepado o grupo de columnas a uno o varios pilares o pilotes.

Fig.09
Un elemento lineal que transfiere cargas al suelo desde Fundación STRIP_FOOTING un elemento continuo, como un muro, o desde una corrida serie de elementos, como columnas.

Definido por Cualquier tipo de fundación que no pertenezca a las USERDEFINED usuario categorías anteriores.

NOTDEFINED No definido Aún no se define el tipo de fundación.

12

<!-- p. 13 -->

Nota

Las losas de fundación no son representadas con la entidad IfcFooting, sino que utilizan la entidad IfcSlab (ver pág. 19) y su
tipo predefinido BASESLAB. Las fundaciones profundas que transfieren cargas a capas del subsuelo se representan con la
entidad IfcPile8.

8 Entidad indicada en la Ficha de Entidades IFC para Puentes. Su información se puede revisar en: https://planbim.cl/ficha-de-entidades-ifcpara-puentes/
13

<!-- p. 14 -->

Entidad: Zonas / Espacios (IfcZone-IfcSpace)

Zonas (IfcZone)

Una IfcZone es un grupo de espacios, espacios parciales u otras zonas. Las estructuras de zona pueden no ser jerárquicas (al
contrario de la estructura espacial de un proyecto), es decir, un IfcSpace (ver pág.15) individual puede estar asociado con
uno, varios o a ningún IfcZone.

Nota

Es importante indicar que esta entidad (IfcZone) es abstracta, por lo tanto, no tiene geometría en sí misma, sino que se
conforma a través de la asociación de entidades de Espacios (IfcSpace) a estas Zonas. A estas últimas se les puede asignar
nombres de puntos cardinales, tipos de recintos, sectores de la edificación o infraestructura. En la siguiente imagen se muestra
un ejemplo:

A (norte) B (norte) C (norte)
G (oeste) I (este) Espacios (IfcSpace) nombrados
con Letras (fig.10) D (sur) E (sur) F (sur)
Zonas (IfcZone) nombrados con
Puntos cardinales(fig.10)
Fig.10

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

14

<!-- p. 15 -->

Entidad: Zonas / Espacios (IfcZone-IfcSpace)

Espacios (IfcSpace)

Un IfcSpace representa un área o volumen acotado o teóricamente limitado. Los espacios son áreas o volúmenes que
proporcionan ciertas funciones dentro de un edificio. Los espacios están asociados a pisos o niveles (o, en el caso de espacios
exteriores, a un sitio).

Un IfcSpace puede abarcar varios espacios conectados. Por lo tanto, un grupo de espacios IfcSpace proporciona una
colección de espacios incluidos en un piso o nivel.

Un IfcSpace también se puede descomponer en partes, donde cada parte define una sección del espacio. Esto se define por
el atributo de tipo de composición de la entidad IfcSpatialStructureElements9 que se interpreta de la siguiente manera:

COMPLEJO = complejo de espacios

ELEMENTO = espacio

PARCIAL = sección del espacio

TABLA 04.- TIPOS PREDEFINIDOS ESPACIOS (IfcSpaceTypeEnum)

REPRESENTACIÓN NOMBRE TRADUCCIÓN DESCRIPCIÓN GRÁFICA
Fig.11

SPACE Espacio Cualquier espacio que no corresponda a otra categoría. A02 A01

Fig.12
Un espacio dedicado para usar como un lugar de
PARKING Estacionamiento estacionamiento para vehículos, incluido el acceso a este,
ES01 como un pasillo de estacionamiento.

Área bruta de piso (GFA por sus siglas en inglés Gross Floor Fig.13
Area): es un tipo específico de espacio para cada piso del
edificio que incluye toda el área neta y el área de GFA Área bruta construcción (también la envoltura externa). La provisión de
un espacio tan específico a menudo es requerida por las
regulaciones.

INTERNAL Interno Sin definición por parte de IFC

EXTERNAL Externo Sin definición por parte de IFC

Definido por USERDEFINED Tipo definido por el usuario. usuario

NOTDEFINED No definido Tipo indefinido.

9 Entidad abstracta no indicada en el Estándar BIM para Proyectos Públicos ni en la Matriz de Información de Entidades. Su información se
puede revisar en:
https://standards.buildingsmart.org/IFC/RELEASE/IFC4/ADD2_TC1/HTML/schema/ifcproductextension/lexical/ifcspatialstructureelement.htm.
15

<!-- p. 16 -->

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

Fig.14 Figura basada en la figura 183, Space Elevations elaborada
por buildingSMART International.

https://standards.buildingsmart.org/IFC/RELEASE/IFC4/ADD2_TC1/
HTML/schema/ifcproductextension/lexical/ifcspace.htm.

16

<!-- p. 17 -->

Entidad: Columnas (IfcColumn)

Columnas (IfcColumn)

Un IfcColumn es un miembro estructural vertical o casi vertical que a menudo está alineado con una intersección de la
cuadrícula estructural. Es una representación de un miembro estructural que transmite, a través de la compresión, el peso de
la estructura superior a otros elementos estructurales que están por debajo de él. Dado que esta representación es generada
desde un punto de vista arquitectónico, no es necesario que sea un elemento de carga.

TABLA 05.- TIPOS PREDEFINIDOS COLUMNAS (IfcColumnTypeEnum)

REPRESENTACIÓN NOMBRE TRADUCCIÓN DESCRIPCIÓN GRÁFICA
Fig.15
Un miembro estándar, generalmente vertical, que resiste a
COLUMN Columna las fuerzas verticales por compresión, pero en ocasiones
también a las fuerzas laterales.

Fig.16

Un elemento de columna incrustado dentro de un muro. Se
PILASTER Pilastra puede requerir que este elemento soporte carga, pero
también se puede usar solo con fines decorativos.

Definido por Tipo definido por el usuario. Aplicable a categorías de USERDEFINED usuario columnas no listadas anteriormente.

Tipo indefinido. Aplicable cuando el tipo de columna no está NOTDEFINED No definido definido aún.

17

<!-- p. 18 -->

Entidad: Vigas (IfcBeam)

Vigas (IfcBeam)

Un IfcBeam es un miembro estructural horizontal o casi horizontal que es capaz de soportar la carga principalmente resistiendo
la flexión. Dado que esta representación es generada desde un punto de vista arquitectónico, no es necesario que sea un
elemento de carga.

TABLA 06.- TIPOS PREDEFINIDOS VIGAS (IfcBeamTypeEnum)

REPRESENTACIÓN NOMBRE TRADUCCIÓN DESCRIPCIÓN GRÁFICA
Fig.17

BEAM Viga Una viga estándar, usualmente utilizada horizontalmente.

Fig.18

JOIST Vigueta Una viga utilizada para soportar un piso o techo.

Fig.19

Una viga ancha a menudo pretensada con un perfil de
HOLLOWCORE Hueca núcleo hueco que generalmente sirve como componente
de una losa.

Fig.20

Una viga o elemento horizontal sobre una abertura (por LINTEL Dintel ejemplo, puerta, ventana).

Fig.21

Una viga alta en la fachada de un edificio. Puede usarse SPANDREL Coronación para apoyar viguetas o elementos de losa en su lado interior.

Fig.22 Una viga que forma parte de una construcción de losa y
actúa junto con la losa que soporta. Tales vigas a menudo
T_BEAM Viga T tienen forma de T (de aquí viene su nombre), pero también
pueden tener otras formas, por ejemplo, forma de L o de T
invertida.

Definido por Tipo definido por el usuario. Aplicable a categorías de vigas USERDEFINED usuario no listadas anteriormente.

Tipo indefinido. Aplicable cuando el tipo de viga no está NOTDEFINED No definido definido aún.

18

<!-- p. 19 -->

Entidad: Losas / Radier (IfcSlab)

Losas (IfcSlab)

Un IfcSlab es un componente de construcción que normalmente encierra un espacio verticalmente. La losa puede
proporcionar el soporte inferior (piso) o la construcción superior (losa del techo) en cualquier espacio de un edificio. Sólo la
parte central de este elemento es considerado una losa. Los acabados superior e inferior se representan a través de la entidad
IfcCovering (ver pág.33).

TABLA 07.- TIPOS PREDEFINIDOS LOSAS (IfcSlabTypeEnum)

REPRESENTACIÓN NOMBRE TRADUCCIÓN DESCRIPCIÓN GRÁFICA
Fig.23

FLOOR Piso Se utiliza para representar una losa de piso.

Fig.24

Se utiliza para representar una losa del techo (ya sea plana ROOF Techo o inclinada).

Fig.25

Se utiliza para representar un descanso dentro de una LANDING Descanso escalera o rampa.

Fig.26

Se utiliza para representar una losa de piso contra el suelo (y,
BASESLAB Radier por lo tanto, forma parte de la cimentación). Esta losa
también recibe el nombre de radier.

Definido por Tipo definido por el usuario. Aplicable a categorías de losas USERDEFINED usuario no listadas anteriormente.

Tipo indefinido. Aplicable cuando el tipo de losa no está NOTDEFINED No definido definido aún.

19

<!-- p. 20 -->

Entidad: Muros (IfcWall)

Muros (IfcWall)

Un IfcWall representa una construcción vertical que delimita o subdivide espacios. Los muros suelen ser elementos planos,
verticales o casi verticales, a menudo diseñados para soportar cargas estructurales. Sin embargo, también existen muros que
no cumplen una función estructural.

TABLA 08.- TIPOS PREDEFINIDOS MUROS (IfcWallTypeEnum)

REPRESENTACIÓN NOMBRE TRADUCCIÓN DESCRIPCIÓN GRÁFICA
Fig.27
Que se puede mover, como un muro plegable o deslizante,
o se puede quitar fácilmente como un tabique removible o
MOVABLE Móvil de montaje. Los muros móviles normalmente no definen los
límites del espacio y, a menudo, pertenecen al sistema de
mobiliario.

Fig.28
Una barrera similar a un muro para proteger a los ocupantes
humanos de la caída, o para evitar la propagación de PARAPET Antepecho incendios. A menudo son diseñados en el borde de
balcones, terrazas o techos.

Fig.29
Un muro diseñado para dividir espacios, que a menudo tiene
una construcción liviana, similar a un sándwich (por ejemplo, PARTITIONING División utilizando una placa de yeso). Estos muros normalmente no
soportan carga.

Fig.30

Muros de cierre, normalmente utilizado para contener
PLUMBINGWALL Muro sanitario tuberías en cuartos sanitarios. Estos a menudo no se
extienden hasta el techo.

Fig.31
Un muro diseñado para soportar cargas cortantes. Están
diseñados a menudo con una sección transversal no
rectangular a lo largo del recorrido del muro. También SHEAR Muro de Corte llamados muros de contención o muros de apoyo se usan
para proteger contra las capas de suelo que se encuentran
detrás.

Fig.32
Una construcción de muro macizo cuyo núcleo es de capa
única o tiene varias capas unidas. A menudo son de
SOLIDWALL Muro sólido mampostería o de concreto (ambos moldeados in situ o
prefabricados), soportan carga y protegen contra
incendios.

20

<!-- p. 21 -->

TABLA 08.- TIPOS PREDEFINIDOS MUROS (IfcWallTypeEnum)

REPRESENTACIÓNNOMBRE TRADUCCIÓN DESCRIPCIÓN GRÁFICA
Fig.33

Un muro estándar, extruido verticalmente con un espesorSTANDARD Estándar constante a lo largo de la trayectoria del muro.

Fig.34

Un muro enmarcado con montantes y revestido con láminas,ELEMENTEDWALL Muro compuesto revestimientos, paneles o yeserías.

Definido por Tipo definido por el usuario. Aplicable a categorías de murosUSERDEFINED usuario no listadas anteriormente.

Tipo indefinido. Aplicable cuando el tipo de muro no estáNOTDEFINED No definido definido aún.

21

<!-- p. 22 -->

Entidad: Muros Cortina (IfcCurtainWall)

Muros Cortina (IfcCurtainWall)

Un IfcCurtainWall es un muro exterior de un edificio, formado por un conjunto de componentes, que está colgado desde el
borde de la estructura de losa / techo en lugar de apoyarse en la losa. Los tipos predefinidos para esta entidad aún no se han
especificado en la norma ISO, pero sí se incluyó en esta un listado genérico para ser extendido en futuras versiones del esquema
IFC.

TABLA 09.- TIPOS PREDEFINIDOS MUROS CORTINA (IfcCurtainWallTypeEnum)

REPRESENTACIÓN NOMBRE TRADUCCIÓN DESCRIPCIÓN GRÁFICA

USERDEFINED Definido por usuario Tipo definido por el usuario.

NOTDEFINED No definido Tipo indefinido.

22

<!-- p. 23 -->

Entidad: Ventanas (IfcWindow)

Ventanas (IfcWindow)

Un IfcWindow es un elemento de construcción que se utiliza principalmente para proporcionar luz natural y aire fresco. Incluye
el vano vertical, pero también horizontal como tragaluces o cúpulas de luz. Incluye construcciones con paneles giratorios,
pivotantes, deslizantes o giratorios y paneles fijos. Un IfcWindow consta de un revestimiento y uno o varios paneles.

TABLA 10.- TIPOS PREDEFINIDOS VENTANAS (IfcWindowTypeEnum)

REPRESENTACIÓN NOMBRE TRADUCCIÓN DESCRIPCIÓN GRÁFICA
Fig.35

Una ventana estándar, generalmente dentro de la abertura
WINDOW Ventana de un muro, como un panel de ventana en un muro cortina,
o como una ventana independiente.

Fig.36

Una ventana dentro de un elemento de construcción SKYLIGHT Lucarna inclinado, generalmente una techumbre.

Fig.37

Una ventana especial que se encuentra en un vano LIGHTDOME Ventana cúpula horizontal de una techumbre.

Definido por Tipo definido por el usuario. Aplicable a categorías de USERDEFINED usuario ventanas no listadas anteriormente.

Tipo indefinido. Aplicable cuando el tipo de ventana no está NOTDEFINED No definido definido aún.

23

<!-- p. 24 -->

Además, la entidad IfcWindow define Tipos de Partición y Operación, que contienen la información de su configuración y la
manera en que la ventana tiene de operar o funcionar.

TABLA 11.- TIPOS DE PARTICIÓN VENTANAS (IfcWindowTypePartitioningEnum)

REPRESENTACIÓN NOMBRE TRADUCCIÓN DESCRIPCIÓN GRÁFICA
Fig. 38

SINGLE_PANEL Panel simple Ventana con un panel.

Fig.39

Doble panel Ventana con dos paneles. La configuración de los DOUBLE_PANEL_VERTICAL vertical paneles es vertical.

Fig.40

Doble panel Ventana con dos paneles. La configuración de los DOUBLE_PANEL_HORIZONTAL horizontal paneles es horizontal.

Fig. 41

Triple panel Ventana con tres paneles. La configuración de los TRIPLE_PANEL_VERTICAL vertical paneles es vertical.

Fig. 42

Triple panel Ventana con tres paneles. La configuración de los TRIPLE_PANEL_HORIZONTAL horizontal paneles es horizontal.

Fig.43

Ventana con tres paneles. La configuración de Triple panel TRIPLE_PANEL_BOTTOM dos paneles es vertical y el tercero es horizontal en abajo la parte inferior.

Fig.44

Ventana con tres paneles. La configuración de Triple panel TRIPLE_PANEL_TOP dos paneles es vertical y el tercero es horizontal en arriba la parte superior.

24

<!-- p. 25 -->

TABLA 11.- TIPOS DE PARTICIÓN VENTANAS (IfcWindowTypePartitioningEnum)

REPRESENTACIÓN NOMBRE TRADUCCIÓN DESCRIPCIÓN GRÁFICA
Fig.45

Ventana con tres paneles. La configuración de Triple panel TRIPLE_PANEL_LEFT dos paneles es horizontal y el tercero es vertical en izquierdo el lado izquierdo.

Fig. 46

Ventana con tres paneles. La configuración de Triple panel TRIPLE_PANEL_RIGHT dos paneles es horizontal y el tercero es vertical en derecho el lado derecho.

Tipo de operación definido por el usuario. Definido por USERDEFINED Aplicable a tipos de operación no listados usuario anteriormente.

Tipo de operación no definido. Aplicable cuando NOTDEFINED No definido el tipo de operación no está definido aún.

Figuras 38 a 47 basadas en las figuras elaboradas por buildingSMART International.
https://standards.buildingsmart.org/IFC/RELEASE/IFC4/ADD2_TC1/HTML/schema/ifcsharedbldgelements/lexical/ifcwindowtypepartitioningenu
m.htm

TABLA 12.- TIPOS DE OPERACIÓN VENTANAS (IfcWindowPanelOperationEnum)

REPRESENTACIÓN NOMBRE TRADUCCIÓN DESCRIPCIÓN GRÁFICA
Fig. 47
Practicable Panel que se abre hacia la derecha cuando es SideHungRightHand mano vista desde el exterior. derecha

Fig.48

Practicable Panel que se abre hacia la izquierda cuando es SideHungLeftHand mano vista desde el exterior. izquierda

25

<!-- p. 26 -->

TABLA 12.- TIPOS DE OPERACIÓN VENTANAS (IfcWindowPanelOperationEnum)

REPRESENTACIÓNNOMBRE TRADUCCIÓN DESCRIPCIÓN GRÁFICA
Fig.49
Oscilo
batiente Panel que se abre hacia la derecha girando sobreTiltAndTurnRightHand mano el marco inferior.
derecha

Fig. 50
Oscilo
batiente Panel que se abre hacia la izquierda girando sobreTiltAndTurnLeftHand mano el marco inferior.
izquierda

Fig. 51

OscilanteTopHung Panel con que gira sobre el marco superior. superior

Fig.52

OscilanteBottomHung Panel con que gira sobre el marco inferior. inferior

Fig.53

Pivotante Panel que pivota horizontalmente con bisagras enPivotHorizontal horizontal la mitad de los marcos laterales.

Fig.54

Pivotante Panel que pivota verticalmente con bisagras en laPivotVertical vertical mitad de los marcos superior e inferior.

Fig.55

CorrederaSlidingHorizontal Panel que se desliza horizontalmente. horizontal

26

<!-- p. 27 -->

TABLA 12.- TIPOS DE OPERACIÓN VENTANAS (IfcWindowPanelOperationEnum)

REPRESENTACIÓN NOMBRE TRADUCCIÓN DESCRIPCIÓN GRÁFICA
Fig. 56

SlidingVertical Guillotina Panel que se desliza verticalmente.

Fig.57

Panel RemovableCasement El panel se puede extraer. removible

Fig.58

FixedCasement Panel fijo El panel es fijo.

Tipo de operación definido por el usuario. Otro tipo de OtherOperation Aplicable a tipos de operación no listados operación anteriormente.

Tipo de operación no definido. Aplicable cuando NotDefined No definido el tipo de operación no está definido aún.

Figuras 47 a 58 basadas en las figuras elaboradas por buildingSMART International.
https://standards.buildingsmart.org/IFC/RELEASE/IFC4/ADD2_TC1/HTML/schema/ifcarchitecturedomain/lexical/ifcwindowpaneloperationenu
m.htm

27

<!-- p. 28 -->

Entidad: Puertas (IfcDoor)

Puertas (IfcDoor)

Un IfcDoor es un elemento de construcción que se utiliza principalmente para proporcionar acceso controlado para personas
y bienes. Incluye construcciones con operaciones articuladas, pivotadas, deslizantes y, además, giratorias y de plegado. Un
IfcDoor consiste en un revestimiento y uno o varios paneles.

TABLA 13.- TIPOS PREDEFINIDOS PUERTAS (IfcDoorTypeEnum)

REPRESENTACIÓN NOMBRE TRADUCCIÓN DESCRIPCIÓN GRÁFICA
Fig.59

Una puerta estándar, generalmente dentro de una abertura
DOOR Puerta de muro, como un panel de puerta en un muro cortina, o
como una puerta "independiente".

Fig.60
Punto de entrada a una propiedad, por lo general dentro de
GATE Portón una abertura en una cerca, o como un portón
"independiente".

Fig.61
Una puerta especial que se extiende horizontalmente en una
TRAPDOOR Escotilla abertura de losa. A menudo se utiliza para acceder a
bodegas o áticos.

Definido por Tipo definido por el usuario. Aplicable a tipos de puertas no USERDEFINED usuario listados anteriormente.

Tipo indefinido. Aplicable cuando el tipo de puerta no está NOTDEFINED No definido definido aún.

28

<!-- p. 29 -->

Además, la entidad IfcDoor define Tipos de Operación, que contienen la información de la forma que la puerta tiene de operar
o funcionar.

TABLA 14.- TIPOS DE OPERACIÓN PUERTAS (IfcDoorTypeOperationEnum)

REPRESENTACIÓN NOMBRE TRADUCCIÓN DESCRIPCIÓN GRÁFICA
Puerta con un panel que se Fig.62
abre (gira) hacia la izquierda.
Las bisagras están en el lado
Giro simple izquierdo. SINGLE_SWING_LEFT izquierda NOTA: La dirección de giro (ya
sea hacia adentro o afuera) se
determina en IfcDoor o
IfcDoorStandardCase.

Puerta con un panel que se Fig.63
abre (gira) hacia la derecha.
Las bisagras están en el lado
Giro simple derecho. SINGLE_SWING_RIGHT derecha NOTA: La dirección de giro (ya
sea hacia adentro o afuera) se
determina en IfcDoor o
IfcDoorStandardCase.

Puerta con dos paneles, uno se Fig.64
abre hacia la izquierda y el otro
se abre hacia la derecha. Doble puerta DOUBLE_DOOR_SINGLE_SWING NOTA: La dirección de giro (ya abatimiento simple sea hacia adentro o afuera) se
determina en IfcDoor o
IfcDoorStandardCase.

Puerta con un panel que gira Fig.65
en ambas direcciones, con
bisagras en el lado izquierdo, en
la dirección de tráfico principal.
Doble giro a la También es llamada puerta de DOUBLE_SWING_LEFT izquierda doble efecto.
NOTA: La dirección de giro (ya
sea hacia adentro o afuera) se
determina en IfcDoor o
IfcDoorStandardCase.

Puerta con un panel que gira Fig.66
en ambas direcciones, con
bisagras en el lado derecho, en
la dirección del tráfico
Doble giro a la principal. También es llamada DOUBLE_SWING_RIGHT derecha puerta de doble efecto.
NOTA: La dirección de giro (ya
sea hacia adentro o afuera) se
determina en IfcDoor o
IfcDoorStandardCase.

29

<!-- p. 30 -->

TABLA 14.- TIPOS DE OPERACIÓN PUERTAS (IfcDoorTypeOperationEnum)

REPRESENTACIÓNNOMBRE TRADUCCIÓN DESCRIPCIÓN GRÁFICA

Puerta con dos paneles que Fig.67
oscilan en ambas direcciones,
un panel con bisagras a la
derecha y el otro a la izquierda
Doble puerta en la dirección de tráficoDOUBLE_DOOR_DOUBLE_SWING abatimiento doble principal.
NOTA: La dirección de giro (ya
sea hacia adentro o afuera) se
determina en IfcDoor o
IfcDoorStandardCase.

Puerta con dos paneles que se Fig.68
abren hacia la izquierda, un
panel gira en una dirección y el
Doble puerta otro panel gira en la dirección
DOUBLE_DOOR_ SINGLE_SWING_OPPOSITE_LEFT abatimiento simple opuesta.
y opuesta izquierda NOTA: La dirección de giro (ya
sea hacia adentro o afuera) se
determina en IfcDoor o
IfcDoorStandardCase.

Puerta con dos paneles que se Fig.69
abren hacia la derecha, un
panel gira en una dirección y el
Doble puerta otro panel gira en la dirección
DOUBLE_DOOR_SINGLE_SWING_OPPOSITE_RIGHT abatimiento simple opuesta.
y opuesta derecha NOTA: La dirección de giro (ya
sea hacia adentro o afuera) se
determina en IfcDoor o
IfcDoorStandardCase.

Fig.70

Corredera hacia la Puerta con un panel que seSLIDING_TO_LEFT izquierda desliza hacia la izquierda.

Fig.71

Corredera hacia la Puerta con un panel que seSLIDING_TO_RIGHT derecha desliza hacia la derecha.

Fig.72
Puerta con dos paneles, uno se
Doble puerta desliza hacia la izquierda y elDOUBLE_DOOR_SLIDING corredera otro se desliza hacia la
derecha.

30

<!-- p. 31 -->

TABLA 14.- TIPOS DE OPERACIÓN PUERTAS (IfcDoorTypeOperationEnum)

REPRESENTACIÓNNOMBRE TRADUCCIÓN DESCRIPCIÓN GRÁFICA
Fig.73

Plegable a la Puerta con un panel que seFOLDING_TO_LEFT izquierda pliega hacia la izquierda.

Fig.74

Plegable a la Puerta con un panel que seFOLDING_TO_RIGHT derecha pliega a la derecha.

Fig.75

Puerta con dos paneles, uno se Doble puertaDOUBLE_DOOR_FOLDING pliega a la izquierda y el otro se plegable pliega a la derecha.

Fig.76
Una puerta de entrada que
consta de cuatro hojas en
forma de cruz y que gira
REVOLVING Giratoria alrededor de un eje vertical
central (los cuatro paneles
están descritos por una sola
propiedad del panel IfcDoor).

Fig.77

Puerta que se abre enrollando.
NOTA: Si se enrolla haciaROLLINGUP De enrollar adentro o hacia afuera, se
determina en el IfcDoor.

Puerta con un panel que se Fig.78
abre (gira) hacia la izquierda y
un panel fijo. Las bisagras del
panel oscilante están en el lado Giro y panelSWING_FIXED_LEFT izquierdo. izquierdo fijo NOTA: La dirección de giro (ya
sea hacia adentro o afuera) se
determina en IfcDoor o
IfcDoorStandardCase.

31

<!-- p. 32 -->

TABLA 14.- TIPOS DE OPERACIÓN PUERTAS (IfcDoorTypeOperationEnum)

REPRESENTACIÓN NOMBRE TRADUCCIÓN DESCRIPCIÓN GRÁFICA
Puerta con un panel que se Fig.79
abre (gira) hacia la derecha y
un panel fijo. Las bisagras del
panel oscilante están en el lado Giro y panel SWING_FIXED_RIGHT derecho. derecho fijo NOTA: La dirección de giro (ya
sea hacia adentro o afuera) se
determina en IfcDoor o
IfcDoorStandardCase.

Tipo de operación definido por
Definido por el usuario. Aplicable a tipos de USERDEFINED usuario operación no listados
anteriormente.

Tipo de operación no definido.
NOTDEFINED No definido Aplicable cuando el tipo de
operación no está definido aún.

Figuras 62 a 79 basadas en las figuras elaboradas por buildingSMART International.
https://standards.buildingsmart.org/IFC/RELEASE/IFC4/ADD2_TC1/HTML/schema/ifcsharedbldgelements/lexical/ifcdoortypeoperationenum.ht
m

32

<!-- p. 33 -->

Entidad: Cubiertas / Techumbres (IfcRoof)

Cubiertas / Techumbres (IfcRoof)

Un IfcRoof es la cubierta de la parte superior de una edificación. Esta protege la edificación de los efectos del clima.

TABLA 15.- TIPOS PREDEFINIDOS CUBIERTAS/TECHUMBRES (IfcRoofTypeEnum)

REPRESENTACIÓN NOMBRE TRADUCCIÓN DESCRIPCIÓN GRÁFICA
Fig.80

Un techo sin pendiente, o con solo una leve FLAT_ROOF Techo plano inclinación para drenar el agua de lluvia.

Fig.81

Techo a un SHED_ROOF Un techo de una sola pendiente. agua

Fig.82

Un techo inclinado hacia abajo en dos partes desde Techo a dos GABLE_ROOF una arista central, para formar un alero en cada aguas extremo.

Fig.83

Techo a cuatro Un techo con extremos inclinados y lados que se unen HIP_ROOF aguas en un ángulo de proyección inclinado.

Fig.84

Tejado a cuatro Un techo a cuatro aguas que tiene un extremo HIPPED_GABLE_ROOF aguas aguilón truncando a un faldón.

Fig.85

Techo Un techo con aristas dividido en cada lado en una GAMBREL_ROOF abuhardillado pendiente más baja sobre una más empinada.

Fig.86

Un techo que tiene en cada lado una parte inferior
MANSARD_ROOF Techo Mansarda más empinada y una parte superior de menor
inclinación.

33

<!-- p. 34 -->

TABLA 15.- TIPOS PREDEFINIDOS CUBIERTAS/TECHUMBRES (IfcRoofTypeEnum)

REPRESENTACIÓN NOMBRE TRADUCCIÓN DESCRIPCIÓN GRÁFICA
Fig.87

Bóveda de BARREL_ROOF Un techo de forma semicilíndrica. cañón

Fig.88

Un techo a dos aguas en forma de un amplio arco Techo arco RAINBOW_ROOF gótico, con superficies convexas suavemente gótico inclinadas.

Fig.89

Un techo que tiene dos pendientes, cada una BUTTERFLY_ROOF Techo invertido descendiendo hacia adentro desde los aleros.

Fig.90

PAVILION_ROOF Techo piramidal Un techo piramidal.

Fig.91

DOME_ROOF Domo Un techo hemisférico.

FREEFORM Techo libre Techo de forma libre

Definido por Tipo definido por el usuario. Aplicable a tipos de USERDEFINED usuario techumbre no listados anteriormente.
Tipo indefinido. Aplicable cuando el tipo de NOTDEFINED No definido techumbre no está definido aún.

Figuras 80 a 91 basadas en las figuras elaboradas por buildingSMART International.
https://standards.buildingsmart.org/IFC/RELEASE/IFC4/ADD2_TC1/HTML/schema/ifcsharedbldgelements/lexical/ifcrooftypeenum.htm

34

<!-- p. 35 -->

Entidad: Cielos Falsos-Acabados (IfcCovering)

Cielos Falsos-Acabados (IfcCovering)

Un IfcCovering es un elemento que cubre alguna parte de otro elemento y que depende completamente de él.

TABLA 16.- TIPOS PREDEFINIDOS CIELOS FALSOS-ACABADOS (IfcCoveringTypeEnum)

REPRESENTACIÓN NOMBRE TRADUCCIÓN DESCRIPCIÓN GRÁFICA
Fig.92

CEILING Cielo Se utiliza para representar un cielo raso.

Fig.93

FLOORING Piso Se utiliza para representar un suelo.

Fig.94

CLADDING Revestimiento Se utiliza para representar un revestimiento de muro.

Fig.95

ROOFING Cubierta Se utiliza para representar un revestimiento de techo.

Fig.96
Se utiliza para representar una moldura que es una faja de
MOLDING Moldura material para cubrir la transición de superficies (a menudo
entre el revestimiento de muros y el techo).

Fig.97
Se utiliza para representar un zócalo que es una franja de
SKIRTINGBOARD Guardapolvo material para cubrir la transición entre el revestimiento del
muro y el suelo.

Fig.98

Se utiliza para aislar un elemento con fines térmicos o INSULATION Aislación acústicos.

35

<!-- p. 36 -->

Fig.99
Una capa impermeable que podría usarse para, por
MEMBRANE Membrana ejemplo, cubierta del techo o como una lámina a prueba
de humedad.

Fig.100

Se utiliza para aislar un elemento de distribución delSLEEVING Funda espacio en el que está contenido.

Fig.101

Se utiliza para envolver, particularmente elementos deWRAPPING Embalaje distribución, usando cinta.

Definido por Tipo definido por el usuario. Aplicable a tipos de acabadosUSERDEFINED usuario no listados anteriormente.

Tipo indefinido. Aplicable cuando el tipo de acabado noNOTDEFINED No definido está definido aún.

36

<!-- p. 37 -->

Entidad: Sistemas de Circulación / Escaleras / Rampas
(IfcTransportElement-IfcStair-IfcRamp)

Sistemas de Circulación (IfcTransportElement)

Un IfcTransportElement es una generalización de todos los objetos relacionados con el transporte que mueven personas,
animales o mercancías dentro de un edificio o complejo de edificios.

TABLA 17.- TIPOS PREDEFINIDOS SISTEMAS DE CIRCULACIÓN (IfcTransportElementTypeEnum)

REPRESENTACIÓN NOMBRE TRADUCCIÓN DESCRIPCIÓN GRÁFICA
Fig.102

Dispositivo de transporte para desplazar personas o ELEVATOR Ascensor productos verticalmente.

Fig.103
Dispositivo de transporte para mover personas. Consiste en
escalones individuales vinculados que se mueven hacia ESCALATOR Escala mecánica arriba y hacia abajo en rieles mientras se mantienen las
huellas en posición horizontal.

Fig.104

Dispositivo de transporte para desplazar personas MOVINGWALKWAY Pasarela móvil horizontalmente o en una pendiente.

Fig.105
Sistema que normalmente incluye la grúa, los rieles de esta,
y los sujetadores. Se utiliza principalmente para mover CRANEWAY Puente grúa mercancías pesadas en una fábrica u otros edificios de la
industria.

Fig.106
Un dispositivo utilizado para levantar o bajar mercancías Mecanismo de LIFTINGGEAR pesadas. Puede ser operado de forma manual, o a través elevación de un accionado eléctrico o neumático.

Definido por Tipo definido por el usuario. Aplicable a elementos de USERDEFINED usuario transporte no listados anteriormente.

Tipo indefinido. Aplicable cuando el elemento de NOTDEFINED No definido transporte no está definido aún.

37

<!-- p. 38 -->

Entidad: Sistemas de Circulación / Escaleras / Rampas (IfcTransportElement-IfcStair-IfcRamp)

Escaleras (IfcStair)

Un IfcStair es un pasaje vertical que permite a los ocupantes pasar de un nivel de piso a otro en una elevación diferente. Puede
incluir un descanso como una losa de piso intermedio.

TABLA 18.- TIPOS PREDEFINIDOS ESCALERAS (IfcStairTypeEnum)

REPRESENTACIÓN NOMBRE TRADUCCIÓN DESCRIPCIÓN GRÁFICA
Fig.107
Una escalera que se extiende de un nivel
STRAIGHT_RUN_STAIR Escalera de tramo recto a otro sin giros ni descansos. La escalera
consta de un tramo recto.

Fig.108
Una escalera recta que consta de dos Escalera de dos tramos TWO_STRAIGHT_RUN_STAIR tramos rectos sin giros, pero con un rectos descanso.

Fig.109
Una escalera que consta de un tramo
con un giro de 90°. La dirección del giro QUARTER_WINDING_STAIR Escalera con giro de 90° está determinada por la línea de
circulación.

Fig.110
Una escalera que realiza un giro de 90°,
Escalera con quiebre de con dos tramos rectos conectados por un QUARTER_TURN_STAIR 90° descanso. La dirección del quiebre está
determinada por la línea de circulación.

Fig.111
Una escalera que consta de un tramo,
que hace un giro de 180°. La orientación HALF_WINDING_STAIR Escalera con giro de 180° del giro está determinada por la línea de
circulación.

Fig.112
Una escalera que realiza un giro de 180°,
Escalera con quiebre de con dos tramos rectos conectados por un HALF_TURN_STAIR 180° descanso. La orientación del giro está
determinada por la línea de circulación.

Una escalera que consta de un tramo, Fig.113
que hace dos giros de 90°. La escalera en Escalera con dos giros de TWO_QUARTER_WINDING_STAIR total hace un giro de 180°. La dirección 90° de los giros está determinada por la línea
de circulación.

38

<!-- p. 39 -->

TABLA 18.- TIPOS PREDEFINIDOS ESCALERAS (IfcStairTypeEnum)

REPRESENTACIÓN NOMBRE TRADUCCIÓN DESCRIPCIÓN GRÁFICA
Una escalera que realiza un giro total de Fig.114
180°, con tres tramos rectos conectados Escalera con dos quiebres TWO_QUARTER_TURN_STAIR por dos descansos. La dirección de los de 90° giros está determinada por la línea de
circulación.

Una escalera que consta de un tramo, Fig.115
que hace tres giros de 90°. La escalera da Escalera con tres giros de THREE_QUARTER_WINDING_STAIR un giro total de 270°. La dirección de los 90° giros está determinada por la línea de
circulación.

Fig.116
Una escalera que realiza un giro total de
270°, que consiste en cuatro tramos rectos Escalera con tres quiebres THREE_QUARTER_TURN_STAIR conectados por descansos. La dirección de 90° de los giros está determinada por la línea
de circulación.

Una escalera construida alrededor de un Fig.117
pilar circular a menudo sin descansos.
Dependiendo del límite exterior, puede
SPIRAL_STAIR Escalera de caracol ser una escalera de caracol circular,
elíptica o rectangular. La orientación de
las escaleras de caracol está
determinada por la línea de circulación.

Una escalera que tiene un tramo recto Fig.118
que conecta con un amplio espacio de
descanso, y dos tramos laterales desde
DOUBLE_RETURN_STAIR Escalera de doble retorno ese descanso en direcciones opuestas. La
escalera realiza un giro de 90°. La
dirección del tráfico está determinada
por la línea de circulación.

Fig.119
Una escalera que se extiende de un nivel
CURVED_RUN_STAIR Escalera curva a otro sin giros. La escalera consta de un
tramo curvo.

Fig.120
Una escalera curva que consta de dos Escalera curva de dos TWO_CURVED_RUN_STAIR tramos curvados sin giros, pero con un tramos descanso.

Tipo definido por el usuario. Aplicable a USERDEFINED Definido por usuario escaleras no listadas anteriormente.

Tipo indefinido. Aplicable cuando la NOTDEFINED No definido escalera no está definida aún.

Figuras 107 a 120 basadas en las figuras elaboradas por buildingSMART International.
https://standards.buildingsmart.org/IFC/RELEASE/IFC4/ADD2_TC1/HTML/schema/ifcsharedbldgelements/lexical/ifcstairtypeenum.htm
39

<!-- p. 40 -->

Entidad: Sistemas de Circulación / Escaleras / Rampas (IfcTransportElement-IfcStair-IfcRamp)

Rampas (IfcRamp)

Un IfcRamp es un pasaje vertical que proporciona un enlace de circulación humana entre un nivel de piso y otro en una
elevación diferente. Puede incluir un descanso como una losa de piso intermedio. Una rampa normalmente no incluye
peldaños.

TABLA 19.- TIPOS PREDEFINIDOS RAMPAS (IfcRampTypeEnum)

REPRESENTACIÓN NOMBRE TRADUCCIÓN DESCRIPCIÓN GRÁFICA
Fig.121
Rampa recta de un tramo sin giros o STRAIGHT_RUN_RAMP Rampa de tramo recto curvas.

Una rampa recta que consta de dos Fig.122 Rampa de dos tramos TWO_STRAIGHT_RUN_RAMP tramos rectos sin giros, pero con un rectos descanso.

Una rampa que realiza un giro de Fig.123
90°, con dos tramos rectos
QUARTER_TURN_RAMP Rampa con giro de 90° conectados por un descanso. La
dirección del giro está determinada
por la línea de circulación.

Una rampa que realiza un giro de Fig.124
180°, con tres tramos rectos
TWO_QUARTER_TURN_RAMP Rampa con dos giros de 90° conectados por descansos. La
dirección del giro está determinada
por la línea de circulación.

Una rampa que realiza un giro de Fig.125
180°, con dos tramos rectos
conectados por un descanso. La HALF_TURN_RAMP Rampa con giro de 180° orientación del giro está
determinada por la línea de
circulación.

Fig.126
Una rampa construida alrededor de
SPIRAL_RAMP Rampa espiral un vacío circular o elíptico sin pilar ni
descansos.

Tipo definido por el usuario. Aplicable USERDEFINED Definido por usuario a rampas no listadas anteriormente.

Tipo indefinido. Aplicable cuando la NOTDEFINED No definido rampa no está definida aún.

Figuras 121 a 126 basadas en las figuras elaboradas por buildingSMART International.
https://standards.buildingsmart.org/IFC/RELEASE/IFC4/ADD2_TC1/HTML/schema/ifcsharedbldgelements/lexical/ifcramptypeenum.htm

40

<!-- p. 41 -->

Entidad: Equipos e instalaciones
(IfcSanitayTerminal-IfcMedicalDevice-IfcLamp)

Equipos e instalaciones sanitarias (IfcSanitayTerminal)

Un IfcSanitayTerminal es un aparato fijo o terminal que generalmente recibe un suministro de agua, que se utiliza para beber,
limpiar o desechar agua sucia. También se incluyen en esta entidad algunos equipos que funcionan en conjunto con uno de
estos aparatos.

TABLA 20.- TIPOS PREDEFINIDOS EQUIPOS E INSTALACIONES SANITARIAS (IfcSanitaryTerminalTypeEnum)

NOMBRE TRADUCCIÓN DESCRIPCIÓN REPRESENTACIÓN GRÁFICA
Fig.127

Aparato sanitario para inmersión BATH Tina del cuerpo humano o partes de él.

Fig.128
Aparato de aguas residuales para
lavar los órganos excretores BIDET Bidet mientras está sentado en el
recipiente.

Una unidad de almacenamiento Fig.129
de agua conectada a un terminal
sanitario equipado con un
dispositivo, operado CISTERN Cisterna automáticamente o por el usuario,
que descarga agua para limpiar
una bandeja de inodoro, urinario o
tolva.

Fig.130
Instalación o dispositivo de aguas
residuales que emite un chorro de SHOWER Ducha agua para lavar el cuerpo
humano.

Fig.131
Aparato de aguas residuales para
recibir, retener o desechar líquidos SINK Lavabo de procesos domésticos, culinarios,
de laboratorio o industriales.

Fig.132
Un terminal sanitario que
proporciona un chorro de agua a SANITARYFOUNTAIN Fuente de agua baja presión para un propósito
específico.

41

<!-- p. 42 -->

TABLA 20.- TIPOS PREDEFINIDOS EQUIPOS E INSTALACIONES SANITARIAS (IfcSanitaryTerminalTypeEnum)

NOMBRE TRADUCCIÓN DESCRIPCIÓN REPRESENTACIÓN GRÁFICA
Fig.133

Aparato de suelo para laTOILETPAN Inodoro eliminación de excrementos.

Fig.134
Aparato del suelo que recibe orina
URINAL Urinario y lo dirige a una salida de
desechos.

Fig.135
Aparato de aguas residuales para
WASHHANDBASIN Lavamanos el lavado de las partes superiores
del cuerpo.

Tipo definido por el usuario.
USERDEFINED Definido por usuario Aplicable a terminales sanitarios no
listados anteriormente.

Tipo indefinido. Aplicable cuando
NOTDEFINED No definido el terminal sanitario no está
definido aún.

42

<!-- p. 43 -->

Entidad: Equipos e instalaciones (IfcSanitayTerminal-IfcMedicalDevice-IfcLamp)

Equipos e instalaciones médicas (IfcMedicalDevice)

Un IfcMedicalDevice está conectado a un sistema de tuberías médicas y funciona con gases clínicos para realizar una función
específica. Los gases clínicos incluyen aire clínico, vacío clínico, oxígeno, dióxido de carbono, nitrógeno y óxido nitroso.

Las salidas para gases clínicos deben usar IfcValve con PredefinedType igual a GASTAP, que contiene un IfcDistributionPort con
FlowDirection = SINK y PredefinedType igual a COMPRESSEDAIR, VACUUM o CHEMICAL, y tener conjuntos de propiedades en el
puerto que indiquen el tipo de gas y la presión. Los tanques para gases médicos deben usar IfcTank con PredefinedType igual
a PRESSUREVESSEL, que contiene un IfcDistributionPort con FlowDirection = SOURCE y PredefinedType = CHEMICAL, e incluir
conjuntos de propiedades en el puerto que indiquen el tipo de gas y el rango de presión. Para más información, se recomienda
revisar la Ficha de Entidades IFC para Equipamiento Hospitalario y Clínico, disponible en https://planbim.cl/ficha-equipamientohospitalario/.

TABLA 21.- TIPOS PREDEFINIDOS EQUIPOS E INSTALACIONES MÉDICAS (IfcMedicalDeviceTypeEnum)

REPRESENTACIÓN NOMBRE TRADUCCIÓN DESCRIPCIÓN GRÁFICA
Fig.136
Dispositivo que proporciona aire médico purificado,
AIRSTATION Estación de aire compuesto por un compresor de aire y una línea de
tratamiento de aire.

Fig.137
Dispositivo que alimenta aire a un generador de Unidad de aire FEEDAIRUNIT oxígeno, compuesto por un compresor de aire, una de alimentación línea de tratamiento de aire y un receptor de aire.

Fig.138

Generador de OXYGENGENERATOR Dispositivo que genera oxígeno del aire. oxígeno

Fig.139
Dispositivo que combina una unidad de aire de Planta de OXYGENPLANT alimentación, un generador de oxígeno y cilindros de oxígeno oxígeno de respaldo.

Fig.140
Dispositivo que proporciona succión, compuesto por Estación de VACUUMSTATION una bomba de vacío y una línea de filtración vacío bacteriana.

Definido por Tipo definido por el usuario. Aplicable a equipos no USERDEFINED usuario listados anteriormente.

Tipo indefinido. Aplicable cuando el equipo no está NOTDEFINED No definido definido aún.

43

<!-- p. 44 -->

Entidad: Equipos e instalaciones (IfcSanitayTerminal-IfcMedicalDevice-IfcLamp)

Equipos de iluminación (IfcLamp)

Una IfcLamp es una fuente de luz artificial, como una bombilla o un tubo.

TABLA 22.- TIPOS PREDEFINIDOS EQUIPOS DE ILUMINACIÓN (IfcLampTypeEnum)

REPRESENTACIÓN NOMBRE TRADUCCIÓN DESCRIPCIÓN GRÁFICA
Fig.141

Compacto Una lámpara fluorescente que tiene un diseño COMPACTFLUORESCENT fluorescente compacto, producido al dar forma al tubo.

Fig.142
Una lámpara típicamente tubular en la que la mayor
parte de la luz es emitida por una o varias capas de FLUORESCENT Fluorescente fósforos excitadas por la radiación ultravioleta de la
descarga.

Fig.143
Una lámpara incandescente en la que se sella un
filamento de tungsteno en una envoltura de transporte HALOGEN Halógeno compacta llena de un gas inerte y una pequeña
cantidad de halógeno, como el yodo o el bromo.

Fig.144

Mercurio alta Una lámpara de descarga en la que la mayoría de la HIGHPRESSUREMERCURY presión luz es emitida por mercurio a alta presión.

Fig.145

Sodio alta Una lámpara de descarga en la que la mayor parte de HIGHPRESSURESODIUM presión la luz se emite al excitar sodio a alta presión.

Fig.146

Una lámpara que utiliza diodos de estado sólido, LED Led emisores de luz.

Fig.147

Una lámpara de descarga en la que la mayor parte de METALHALIDE Haluro metálico la luz se emite al excitar haluro metálico.

44

<!-- p. 45 -->

TABLA 22.- TIPOS PREDEFINIDOS EQUIPOS DE ILUMINACIÓN (IfcLampTypeEnum)

REPRESENTACIÓNNOMBRE TRADUCCIÓN DESCRIPCIÓN GRÁFICA
Fig.148
Una lámpara que utiliza diodos de estado sólido
emisores de luz, cuya capa electroluminiscente emisivaOLED Oled está compuesta por una película de compuestos
orgánicos.

Fig.149
Una lámpara que emite luz al pasar una corriente
TUNGSTENFILAMENT Tungsteno eléctrica a través de un filamento de alambre de
tungsteno en vacío.

Definido por Tipo definido por el usuario. Aplicable a equipos deUSERDEFINED usuario iluminación no listados anteriormente.

Tipo indefinido. Aplicable cuando el equipo no estáNOTDEFINED No definido definido aún.

45

<!-- p. 46 -->

Entidad: Muebles (IfcFurniture-IfcSystemFurnitureElement)

Muebles (IfcFurniture)

Un IfcFurniture define los muebles completos, como una mesa, escritorio, silla o gabinete, que pueden estar o no unidos a
componentes de un edificio de forma permanente.

TABLA 23.- TIPOS PREDEFINIDOS MUEBLES (IfcFurnitureTypeEnum)

REPRESENTACIÓN NOMBRE TRADUCCIÓN DESCRIPCIÓN GRÁFICA
Fig.150

CHAIR Silla Mueble que sirve de asiento para una sola persona.

Fig.151
Mueble con una superficie encimera para múltiples TABLE Mesa personas.

Fig.152
Mueble con encimera y opcionalmente cajones, para DESK Escritorio una sola persona.

Fig.153

BED Cama Mueble utilizado para dormir.

Fig.154
Mueble con cajones deslizantes utilizado para guardar FILECABINET Cajonera documentos.

Fig.155

SHELF Repisa Mueble para almacenar libros u otros artículos.

Fig.156

SOFA Sofá Mueble que sirve de asiento para varias personas.

Definido por Tipo definido por el usuario. Aplicable a muebles no USERDEFINED usuario listados anteriormente.

Tipo indefinido. Aplicable cuando el mueble no está NOTDEFINED No definido definido aún.

46

<!-- p. 47 -->

Entidad: Muebles (IfcFurniture-IfcSystemFurnitureElement)

Sistema de muebles (IfcSystemFurnitureElement)

Un IfcSystemFurnitureElement define componentes de muebles modulares que no se adosan directamente a un edificio, sino
que se agregan dentro de otros muebles.

TABLA 24.- TIPOS PREDEFINIDOS SISTEMA DE MUEBLES (IfcSystemFurnitureElementTypeEnum)

REPRESENTACIÓN NOMBRE TRADUCCIÓN DESCRIPCIÓN GRÁFICA
Fig.157

PANEL Panel Panel vertical utilizado para dividir espacios de trabajo.

Fig.158

Superficie de WORKSURFACE Superficie de una estación de trabajo. trabajo

Definido por Tipo definido por el usuario. Aplicable a sistemas de USERDEFINED usuario muebles no listados anteriormente.

Tipo indefinido. Aplicable cuando el sistema de NOTDEFINED No definido muebles no está definido aún.

47

<!-- p. 48 -->

Entidad: Estructuras Especiales (IfcElementAssembly)

Estructuras Especiales (IfcElementAssembly)

Un IfcElementAssembly representa conjuntos complejos, formados por varios elementos, de construcción o de otros tipos.

TABLA 25.- LUGAR DE ENSAMBLAJE ESTRUCTURAS ESPECIALES (IfcAssemblyPlaceEnum)

REPRESENTACIÓN NOMBRE TRADUCCIÓN DESCRIPCIÓN GRÁFICA
N/A
SITE Sitio Se ensambla en el sitio.

N/A
FACTORY Fábrica Se ensambla en una fábrica.

NOTDEFINED No definido Su ensamblaje no está definido aún.

Esta entidad, además de tener una enumeración de tipos predefinidos, ofrece una enumeración de lugar de ensamblaje
(IfcAssemblyPlaceEnum). Los lugares listados son los siguientes:

TABLA 26.- TIPOS PREDEFINIDOSESTRUCTURAS ESPECIALES (IfcElementAssemblyTypeEnum)

REPRESENTACIÓN NOMBRE TRADUCCIÓN DESCRIPCIÓN GRÁFICA
Fig.159

Accesorio ACCESSORY_ASSEMBLY Accesorios o componentes ensamblados. ensamblado

Fig.160

ARCH Arco Una estructura curva

Fig.161

Vigas interconectadas, ubicadas en un plano BEAM_GRID Grilla de vigas (típicamente horizontal).

48

<!-- p. 49 -->

TABLA 26.- TIPOS PREDEFINIDOSESTRUCTURAS ESPECIALES (IfcElementAssemblyTypeEnum)

REPRESENTACIÓNNOMBRE TRADUCCIÓN DESCRIPCIÓN GRÁFICA
Fig.162

MarcoBRACED_FRAME Un marco rígido con miembros de refuerzo adicionales. arriostrado

Fig.163

Una gran viga, generalmente utilizada en superGIRDER Jácena estructuras.

Fig.164

Unidades deREINFORCEMENT_UNIT Elementos de refuerzo ensamblados. refuerzo

Fig.165

Una estructura construida por vigas, columnas, etc. conRIGID_FRAME Marco rígido uniones resistentes al momento.

Fig.166

SLAB_FIELD Losas Losas dispuestas en un plano.

Fig.167

TRUSS Entramado Una estructura formada por miembros con unión fija.

Definido por Tipo definido por el usuario. Aplicable a estructurasUSERDEFINED usuario especiales no listadas anteriormente.

Tipo indefinido. Aplicable cuando la estructura especialNOTDEFINED No definido no está definida aún.

49

<!-- p. 50 -->

Nota 1: Elementos compuestos

La forma en que se representan los elementos compuestos por distintas capas, como Muros (IfcWall), Losas (IfcSlab) y
Cubiertas (IfcRoof), puede variar según el objetivo del modelo, y la versión del esquema IFC que se utilice. La recomendación
general es evitar complejizar la geometría de los elementos, y preferir el traspaso de estas características a través de
información no geométrica.

En específico, en la versión IFC 4 del esquema no es posible exportar los componentes de un muro como geometrías
separadas. Esta información se representa sólo como información no gráfica, traspasando la información de las capas de
materialidad, sus espesores y ubicación.

Elemento: Entidad: IfcWall
MURO_TIPO_A
Material1: H.A.
Capa estructural
Material2: Lana mineral
Capa aislación
Material3: Volcanita
Capa terminación

Fig.168 Muro compuesto en software nativo Fig.169 Muro compuesto en IFC4

Por otro lado, existe la posibilidad de modelar el recubrimiento de un elemento utilizando la entidad IfcCovering y sus
tipos predefinidos (ver pag.33 Entidad: Cielos Falsos – Acabados). De esta forma, el elemento principal y su recubrimiento
quedan como entidades separadas. Es importante que esto sólo sea ejecutado si es necesario para cumplir un objetivo
específico en el modelo. Esto aplica para las entidades IfcWall, IfcSlab e IfcRoof.

Entidad: IfcWall Elemento: Muro
Entidad: IfcCovering Elemento: Recubrimiento
Tipo Predefinido: CLADDING

Fig.170 Muro y recubrimiento modelado en software nativo Fig.171 Entidades IfcWall e IfcCovering en IFC4

La versión del esquema IFC 2x3 permite exportar un elemento y sus componentes como entidades separadas, pero
manteniendo su jerarquía, mostrando como elemento principal la entidad IfcWall, IfcSlab o IfcRoof y sus componentes como
elementos subordinados utilizando la entidad IfcBuildingElementPart.

50

<!-- p. 51 -->

Elemento:
Entidad: IfcWall MURO_TIPO_A
Entidad: IfcBuildingElementPart Capa estructural
Entidad: IfcBuildingElementPart Capa aislación
Capa terminación Entidad:JfcBuildingElementPar

Fig.172 Muro compuesto en software nativo Fig.173 Entidad IfcWall y sus entidades subordinadas
IfcBuildingElementPart en IFC 2x3

Algunos software de autoría BIM permiten explotar las distintas capas de un elemento y luego traspasar estas capas como
entidades separadas, pero sin una jerarquía clara y asignándole a cada capa la entidad IfcWall, IfcSlab o IfcRoof. Esta opción
no se recomienda, ya que se pierde la relación entre elementos y la información de su función específica.

Elemento:
MURO_TIPO_A

Parte estructural
Entidad: IfcWall
Parte aislación
Entidad: IfcWall
Parte terminación
Entidad: IfcWall

Fig.174 Muro compuesto explotado en software nativo Fig.175 Cada parte del muro explotado como una entidad
IfcWall independiente en IFC

51

<!-- p. 52 -->

Nota 2: Resistencia al fuego en entidades

Entre los parámetros incluidos en el Manual de Entrega de Información Básica BIM (MEI), se solicita incluir la resistencia
al fuego de las entidades de un modelo. Los valores posibles para este parámetro, según la normativa nacional (O.G.U.C), son
los siguientes:

TABLA 27.- VALORES POSIBLES PARÁMETRO RESISTENCIA AL FUEGO (FireRating)

VALOR DESCRIPCIÓN

F-15 El elemento constructivo puede estar 15 minutos expuesto al fuego antes de colapsar.

F-30 El elemento constructivo puede estar 30 minutos expuesto al fuego antes de colapsar.

F-60 El elemento constructivo puede estar 60 minutos expuesto al fuego antes de colapsar.

F-90 El elemento constructivo puede estar 90 minutos expuesto al fuego antes de colapsar.

F-120 El elemento constructivo puede estar 120 minutos expuesto al fuego antes de colapsar.

F-150 El elemento constructivo puede estar 150 minutos expuesto al fuego antes de colapsar.

F-180 El elemento constructivo puede estar 180 minutos expuesto al fuego antes de colapsar.

NOTAPPLICABLE El parámetro no aplica para esta entidad.

NOTDEFINED El valor de resistencia al fuego no está definido aún.

52

<!-- p. 53 -->

www.planbim.cl

in

53
