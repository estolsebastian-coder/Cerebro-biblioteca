---
type: libro
title: "Plan de Trabajo Proyecto: “Fomento a la Implementación de metodologías BIM en PJUD”Año 2018-2019"
author: "Paulina Godoy Del Campo"
categoria: "BIM Y HBIM"
paginas: 24
extraccion: "texto"
fuente: "local:E:/MATERIAL DE CONSULTA/BIM Y HBIM/02. Planbim/documentación/Entidades Ifc para Elementos de Refuerzo_V1.0.pdf"
convertido: 2026-10-16
---

# Plan de Trabajo Proyecto: “Fomento a la Implementación de metodologías BIM en PJUD”Año 2018-2019

> Texto extraído de `BIM Y HBIM\02. Planbim\documentación\Entidades Ifc para Elementos de Refuerzo_V1.0.pdf` (24 páginas, texto). El PDF original está en el disco E: (MATERIAL DE CONSULTA); `<!-- p. N -->` marca el inicio de cada página.

<!-- p. 1 -->

FICHA DE ENTIDADES
IFC PARA ELEMENTOS DE
REFUERZO Y CONEXIÓN
ESTRUCTURAL

Según ISO 16739-1:2018
VERSIÓN 1.0

Agosto 2020

<!-- p. 2 -->

Esta obra está licenciada bajo la Licencia Creative Commons
Atribución-NoComercial 4.0 Internacional.
Para ver una copia de esta licencia, visite http://creativecommons.org/licenses/by-nc/4.0/.

1 Esta obra está licenciada bajo la Licencia Creative Commons. Atribución-NoComercial 4.0 Internacional.
Para ver una copia de esta licencia, visite http://creativecommons.org/licenses/by-nc/4.0/.
www.planbim.cl

<!-- p. 3 -->

1 ÍNDICE

1 ÍNDICE ............................................................................................................................................................................ 2

2 INTRODUCCIÓN ............................................................................................................................................................ 3

3 ELEMENTOS DE REFUERZO (IfcReinforcingElement) ................................................................................................... 6

IfcReinforcingBar (Barra de refuerzo) .................................................................................................................................... 11

IfcReinforcingMesh (Malla de refuerzo) ................................................................................................................................ 13

IfcTendon (Tensor) ................................................................................................................................................................... 15

IfcTendonAnchor (Anclaje de tensor) ................................................................................................................................... 17

4 FIJACIONES (IfcFastener) ........................................................................................................................................... 18

5 FIJACIONES MECÁNICAS (IfcMechanicalFastener) ................................................................................................ 20

2 Esta obra está licenciada bajo la Licencia Creative Commons. Atribución-NoComercial 4.0 Internacional.
Para ver una copia de esta licencia, visite http://creativecommons.org/licenses/by-nc/4.0/.
www.planbim.cl

<!-- p. 4 -->

2 INTRODUCCIÓN

El esquema de información Industry Foundation Classes (IFC, por sus siglas en inglés), es un
estándar abierto para la especificación e intercambio de información de la industria de la
construcción. Su utilización ha crecido de forma exponencial en los últimos años, y un gran número
de software BIM han incorporado en sus flujos de trabajo la importación y exportación de información
en este formato. El esquema está en un constante desarrollo, actualizando sus contenidos e
incorporando elementos y parámetros de tipologías no incluidas en un comienzo.

En sus esfuerzos por impulsar la implementación de la metodología BIM por parte de las
instituciones públicas, Planbim ha creado un Estándar que toma los principales elementos de los
documentos y normas más relevantes de la industria a nivel internacional, adaptándolos al contexto
nacional.

Para asegurar que la información intercambiada por los distintos participantes de un proyecto
sea interoperable y estandarizada, el Estándar BIM para Proyectos Públicos adopta el esquema IFC,
utilizándolo como base para:

• Especificar las entidades que componen los distintos modelos BIM,
• Especificar el Tipo de Información (TDI) que estos deben contener según los Usos BIM
seleccionados
• Especificar el Nivel de Información (NDI) necesario para los Estado de Avance de la
Información de los Modelos (EAIM) definidos para las etapas del proyecto.

La presente Ficha de Entidades IFC para Elementos de Refuerzo busca facilitar la aplicación del
esquema IFC en tipologías que utilizan elementos específicos, como es el caso de las disciplinas
estructurales. Este documento amplía la información ya incluida tanto en el Estándar BIM para
Proyectos Públicos, como en la Matriz de Información de Entidades, para incorporar entidades
específicas de la disciplina estructural. La entidad Elementos de Refuerzo (IfcReinforcingElement)
agrupa componentes utilizados para reforzar estructuras de hormigón. Las entidades Fijaciones
(IfcFastener) y Fijaciones Mecánicas (IfcMechanicalFastener) agrupan componentes que fijan o
conectan dos elementos estructurales, de forma adherente y mecánica respectivamente.

Para la versión 1.0 de este documento, se hace alusión a las entidades incluidas en la versión IFC
4.0.2.1 (IFC 4 ADD2 TC1), publicada en la ISO 16739-1:2018. Para utilizar esta ficha de forma correcta,
se debe tener en cuenta la estructura general de las entidades en el esquema IFC. En esta estructura,
una entidad representa una categoría de elementos, definidas por propiedades comunes. Dentro
del esquema existen entidades de carácter general, que sientan las bases para la creación de
entidades más específicas y que les heredan algunas de sus propiedades. A continuación, se muestra
un esquema simplificado de una entidad general y una específica:

ENTIDAD OBJETO
IfcObject

ENTIDAD PRODUCTO
IfcProduct

ENTIDAD ELEMENTO
IfcElement

Fig.1 – Esquema Entidades Generales

3 Esta obra está licenciada bajo la Licencia Creative Commons. Atribución-NoComercial 4.0 Internacional.
Para ver una copia de esta licencia, visite http://creativecommons.org/licenses/by-nc/4.0/.
www.planbim.cl

<!-- p. 5 -->

ENTIDAD ELEMENTO
IfcElement

ENTIDAD COMPONENTE DE ELEMENTO
IfcElementComponent

ENTIDAD ELEMENTOS DE REFUERZO ENTIDAD FIJACIONES ENTIDAD FIJACIONES MECÁNICAS
IfcReinforcingElement IfcFastener IfcMechanicalFastener

ENTIDAD BARRA DE REFUERZO
IfcReinforcingBar

Fig.2 – Esquema Entidades Específicas

Para lograr mayor especificidad, se utiliza la información disponible en el atributo tipo predefinido
(TypeEnum). Este atributo consiste en un listado de tipos de elementos derivados de una entidad, que
ya están definidos dentro del esquema, y que corresponden a los más comúnmente utilizados. Para
las entidades específicas que se describen en el presente documento, se incluye el listado de sus tipos
predefinidos si corresponde. Para las 21 entidades declaradas en el Estándar BIM, esta información
se encuentra en la Matriz de Información de Entidades que puede ser descargada en
https://planbim.cl/matriz-de-informacion/.

A diferencia de la estructura revisada anteriormente (Fig.2), el tipo predefinido (TypeEnum) no
modifica el nombre ni el tipo de la entidad, sino que utiliza un atributo específico para dar mayor
precisión a la definición del elemento.

• TIPO A
ENTIDAD TIPO PREDEFINIDO
• TIPO B
Entity TypeEnum
• TIPO C

Fig.3 – Esquema Tipo Predefinido (TypeEnum)

El listado de los tipos predefinidos de las entidades incluidas en la Matriz de Información de
Entidades y de las incluidas en este documento, están definidas en la ISO16739-1:2018 (IFC4). En la
siguiente figura se presentan los tipos predefinidos de la entidad Barra de Refuerzo (IfcReinforcingBar):

• ANCHORING (ANCLAJE)
• EDGE (BORDE)
• LIGATURE (AMARRE)
• MAIN (PRINCIPAL)
BARRA DE REFUERZO TIPO PREDEFINIDO • PUNCHING (PERFORANTE)
IfcReinforcingBar IfcReinforcingBarTypeEnum • RING (ANILLO)
• SHEAR (CORTE)
• STUD (PERNO)
• DEFINIDO POR USUARIO (USERDEFINED)
• NO DEFINIDO (NOTDEFINED)

Fig.4 – Tipos predefinidos de Barra de Refuerzo (IfcReinforcingBar)

4 Esta obra está licenciada bajo la Licencia Creative Commons. Atribución-NoComercial 4.0 Internacional.
Para ver una copia de esta licencia, visite http://creativecommons.org/licenses/by-nc/4.0/.
www.planbim.cl

<!-- p. 6 -->

En este listado de tipos predefinidos, también existe la opción de que el usuario ingrese un tipo
no especificado en la norma ISO, utilizando la opción USERDEFINED (DEFINIDO POR USUARIO), o dejarlo
sin definición (NOTDEFINED). De seleccionar la opción USERDEFINED, se utilizará el atributo ObjectType
(Tipo de Objeto) para ingresar la información correspondiente. Por ejemplo, para especificar que la
barra de refuerzo corresponde a un tipo especial, se debe utilizar esta última opción, ya que el
esquema no incluye este tipo predefinido.

• ANCHORING (ANCLAJE)
• EDGE (BORDE)
• LIGATURE (AMARRE)
• MAIN (PRINCIPAL)
BARRA DE REFUERZO • PUNCHING (PERFORANTE) TIPO DE OBJETO
IfcReinforcingBar • RING (ANILLO) ObjectType
• SHEAR (CORTE)
• STUD (PERNO)
• DEFINIDO POR USUARIO (USERDEFINED)
• NO DEFINIDO (NOTDEFINED)

Fig.5 – Esquema Barra de Refuerzo (IfcReinforcingBar)

El esquema IFC permite gestionar la información de las entidades a través de atributos,
propiedades y mediciones. Los atributos son los parámetros distintivos de cada entidad, es decir, la
información que nos permite identificar una entidad IFC. Las propiedades son parámetros agrupados
en los llamados Property Sets (Pset), y nos permiten ingresar información complementaria a una
entidad. Las mediciones son grupos de parámetros que nos permiten indicar las propiedades físicas
de una entidad, como largo, ancho, espesor, etc. Estas propiedades se agrupan en Quantity Sets
(Qto). Toda esta información puede ser específica para cada entidad, o puede ser heredada desde
una entidad superior.

Es importante destacar que los atributos y parámetros incluidos en este documento no son
obligatorios, sino que buscan complementar los incluidos en el Estándar BIM para Proyectos Públicos
y la Matriz de Información de Entidades. Su inclusión tiene como objetivo facilitar la comprensión del
esquema IFC y de los parámetros que ya existen y que están disponibles para ser utilizados por las
distintas especialidades involucradas en un proyecto. Además, la implementación de estos
parámetros y el esquema IFC en general depende de cada software, existiendo algunos que
permiten acceder a esta información de forma más directa que otros.

Para comprender cómo se ordena la información en el esquema IFC, revisar las distintas
versiones, las definiciones básicas de sus objetos y sus características, se recomienda revisar la página
oficial de buildingSmart https://technical.buildingsmart.org/standards/ifc/ifc-schema-specifications/ .

Todas las definiciones de entidades y parámetros utilizadas en este documento están basadas en la
ISO16739-1:2018 (IFC4).

Agradecimientos a BIM Technology & Design, Spoerer Ingenieros Asociados, AEC Shift y René Lagos
Engineers por su colaboración en el proceso de revisión de la información incluida en esta ficha.

Todas las figuras presentes en este documento han sido elaboradas por Planbim, al igual que las
traducciones de los términos y descripciones de la ISO16739-1:2018 presentadas en las tablas.

5 Esta obra está licenciada bajo la Licencia Creative Commons. Atribución-NoComercial 4.0 Internacional.
Para ver una copia de esta licencia, visite http://creativecommons.org/licenses/by-nc/4.0/.
www.planbim.cl

<!-- p. 7 -->

3 ELEMENTOS DE REFUERZO (IfcReinforcingElement)

En el esquema IFC, la entidad IfcReinforcingElement representa barras, cables, hilos, mallas,
tensores y otros componentes insertos en hormigón, de tal manera que ambos elementos (el
elemento de refuerzo y el hormigón) actúan en conjunto resistiendo fuerzas. De esta entidad se
desprenden otras cuatro más específicas para representar este tipo de componentes. Estas son:

\1. IfcReinforcingBar
\2. IfcReinforcingMesh
\3. IfcTendon
\4. IfcTendonAnchor

Fig.6 – IfcReinforcingBar Fig.7 – IfcReinforcingMesh Fig.8 – IfcTendon Fig.8 – IfcTendonAnchor

El esquema IFC incluye propiedades para estos elementos, y otros que derivan de la entidad
IfcElementComponent, en el grupo de parámetros Pset_ElementComponentCommon. Estas
propiedades están disponibles para todas las entidades incluidas en este documento
(IfcReinforcingElement y sus subentidades, IfcFastener e IfcMechanicalFastener), pues todas derivan
de la entidad general IfcElementComponent (ver figura 2). Los parámetros incluidas en este Property
Set y que, por lo tanto, se encuentran disponibles en estas entidades son:

TABLA 01: Pset_ElementComponentCommon
NOMBRE
TRADUCCIÓN TIPO DE DATOS DESCRIPCIÓN
PARÁMETRO
Reference Referencia P_SINGLEVALUE/IfcIdentifier Identificador referencial para este tipo específico en
el proyecto, también conocido como “Tipo
Constructivo”. Se deberá utilizar como una
alternativa al denominador del “object type”, si el
software utilizado no soporta este parámetro.
Status Estatus P_ENUMERATEDVALUE / IfcLabel / Estado del elemento, utilizado generalmente en
PEnum_ElementStatus proyectos de renovación o reequipamiento.
Ver tabla 02 para los tipos predefinidos.
DeliveryType Tipo de P_ENUMERATEDVALUE / IfcLabel / Determina cómo el elemento será enviado a
Entrega PEnum_ElementComponentDeliver terreno.
yType Ver tabla 03 para los tipos predefinidos.
CorrosionTre Tratamiento P_ENUMERATEDVALUE / IfcLabel / Determina el tipo de tratamiento anticorrosivo del
atment anticorrosión PEnum_ElementComponenCorrosi elemento metálico. Esta propiedad se incluye
onTreatment independientemente de la especificación del
material, y sólo como declaración de requerimiento,
no una característica de diseño o procesamiento.
Ver tabla 04 para los tipos predefinidos.

6 Esta obra está licenciada bajo la Licencia Creative Commons. Atribución-NoComercial 4.0 Internacional.
Para ver una copia de esta licencia, visite http://creativecommons.org/licenses/by-nc/4.0/.
www.planbim.cl

<!-- p. 8 -->

TABLA 02: TIPOS PREDEFINIDOS DE ESTATUS (Status)
TIPO
TRADUCCIÓN DESCRIPCIÓN
PREDEFINIDO
NEW Nuevo
EXISTING Existente Elemento que existe y permanece
DEMOLISH Demolición Elemento que existe, pero que será demolido
TEMPORARY Temporal Elemento que existirá sólo de forma temporal (como una estructura de
soporte temporal)
OTHER Otro El valor no está en la lista
NOTKNOWN No conocido El valor es desconocido
UNSET No especificado El valor no ha sido especificado

TABLA 03: TIPOS PREDEFINIDOS DE TIPO DE ENTREGA (DeliveryType)

TIPO PREDEFINIDO TRADUCCIÓN DESCRIPCIÓN

CAST_IN_PLACE Ejecutado in-situ
WELDED_TO_STRUCTURE Soldado a la estructura
LOOSE Suelto
ATTACHED_FOR_DELIVERY Adjunto para la entrega
PRECAST Prefabricado
NOTDEFINED No definido El valor no ha sido definido

TABLA 04: TIPOS PREDEFINIDOS DE TRATAMIENTO ANTICORROSIÓN (CorrosionTreatment)

TIPO PREDEFINIDO TRADUCCIÓN DESCRIPCIÓN

PAINTED Pintado
EPOXYCOATED Recubrimiento epóxico
GALVANISED Galvanizado
STAINLESS Inoxidable
NONE Prefabricado
NOTDEFINED No definido El valor no ha sido definido

También se incluyen algunos grupos de propiedades heredados de la entidad IfcElement. Estos
grupos de propiedades o Pset son:

• Pset_EnvironmentalImpactIndicators
• Pset_EnvironmentalImpactValues
• Pset_Condition
• Pset_ManufacturerOcurrence
• Pset_ManufacturerTypeInformation
• Pset_ServiceLife
• Pset_Warranty

7 Esta obra está licenciada bajo la Licencia Creative Commons. Atribución-NoComercial 4.0 Internacional.
Para ver una copia de esta licencia, visite http://creativecommons.org/licenses/by-nc/4.0/.
www.planbim.cl

<!-- p. 9 -->

De los anteriores sólo detallaremos los parámetros definidos en Pset_ManufacturerOcurrence y
Pset_ManufacturerTypeInformation, por su relevancia especial en la información que se requiere de
los elementos de refuerzo. Los parámetros que incluye el Pset_ManufacturerOcurrence son:

TABLA 05: Pset_ManufacturerOcurrence

NOMBRE
TRADUCCIÓN TIPO DE DATOS DESCRIPCIÓN
PARÁMETRO
AcquisitionDate Fecha de adquisición P_SINGLEVALUE/IfcDate Fecha en la que se adquiere o compra el
elemento manufacturado.
BarCode Código de barra P_SINGLEVALUE/IfcIdentifier La identificación del código de barras
asignado a una instancia del producto.
SerialNumber Número de serie P_SINGLEVALUE/IfcIdentifier El número de serie asignado a una instancia
del producto.
BatchReference Referencia de lote P_SINGLEVALUE/IfcIdentifier La identidad de la referencia del lote del cual
proviene una instancia del producto.
AssemblyPlace Lugar de ensamblaje P_ENUMERATEDVALUE / Enumeración que define donde se debe
IfcLabel / realizar el ensamblaje, puede ser en una
PEnum_AssemblyPlace fábrica u otra locación externa al sitio de
construcción, o en el sitio de construcción.
Ver tabla 06 para los tipos predefinidos.

TABLA 06: TIPOS PREDEFINIDOS DE LUGAR DE ENSAMBLAJE (AssemblyPlace)
TIPO
TRADUCCIÓN DESCRIPCIÓN
PREDEFINIDO
FACTORY Fábrica
OFFSITE Fuera del sitio
SITE Sitio
OTHER Otro El valor no está en la lista
NOTKNOWN No conocido El valor es desconocido
UNSET Lugar de ensamblaje El valor no ha sido especificado

8 Esta obra está licenciada bajo la Licencia Creative Commons. Atribución-NoComercial 4.0 Internacional.
Para ver una copia de esta licencia, visite http://creativecommons.org/licenses/by-nc/4.0/.
www.planbim.cl

<!-- p. 10 -->

En cuanto a los parámetros incluidos en el Pset_ManufacturerTypeInformation, estos son:

TABLA 07: Pset_ManufacturerTypeInformation

NOMBRE PARÁMETRO TRADUCCIÓN TIPO DE DATOS DESCRIPCIÓN
GlobalTradeItemNumber Número global de ítem P_SINGLEVALUE/IfcIdentifier Este número (GTIN) es un
de comercio identificador para ítems de
comercio desarrollado por GS1
(www.gs1.org).

ArticleNumber Número de artículo P_SINGLEVALUE/IfcIdentifier Número de artículo o referencia
aplicada a un producto
configurado de acuerdo con un
esquema estandarizado, definido
por el fabricante. Usualmente
utilizado como número para la
compra.
ModelReference Referencia de modelo P_SINGLEVALUE/IfcLabel El número o identificador del
modelo del producto (o línea de
productos) asignado por el
fabricante del item.

ModelLabel Etiqueta de modelo P_SINGLEVALUE/IfcLabel El nombre descriptivo del modelo
de producto (o línea de producto)
asignado por el fabricante del ítem.

Manufacturer Fabricante P_SINGLEVALUE/IfcLabel La organización que fabricó o
ensambló el ítem.

ProductionYear Año de producción P_SINGLEVALUE/IfcLabel El año de producción del ítem
manufacturado.

AssemblyPlace Lugar de ensamblaje P_ENUMERATEDVALUE / IfcLabel / Enumeración que define donde se
PEnum_AssemblyPlace debe realizar el ensamblaje, puede
ser en una fábrica o en el sitio de
construcción.
Ver tabla 08 para los tipos
predefinidos.

TABLA 08: TIPOS PREDEFINIDOS DE LUGAR DE ENSAMBLAJE (AssemblyPlace)

TIPO
TRADUCCIÓN DESCRIPCIÓN
PREDEFINIDO
FACTORY Fábrica
OFFSITE Fuera del sitio
SITE Sitio
OTHER Otro El valor no está en la lista
NOTKNOWN No conocido El valor es desconocido
UNSET Lugar de ensamblaje El valor no ha sido especificado

9 Esta obra está licenciada bajo la Licencia Creative Commons. Atribución-NoComercial 4.0 Internacional.
Para ver una copia de esta licencia, visite http://creativecommons.org/licenses/by-nc/4.0/.
www.planbim.cl

<!-- p. 11 -->

Además, en el esquema IFC se incluyen mediciones generales para los elementos de refuerzo
agrupados en la entidad IfcReinforcingElement. Estas mediciones, contenidas en el
Qto_ReinforcingElementBaseQuantities, son heredadas por las entidades derivadas IfcReinforcingBar,
IfcReinforcinMesh, IfcTendon e IfcTendonAnchor, y por lo tanto están disponibles para todas ellas. Los
parámetros contenidos en Qto_ReinforcingElementBaseQuantities son:

TABLA 09: Qto_ReinforcingElementBaseQuantities

NOMBRE TRADUCCIÓN DEFINICIÓN
Count Cuenta Cantidad total de elementos de
refuerzo.
Length Longitud Longitud total del refuerzo.

Weight Peso Peso total del refuerzo

Figuras de ejemplo:

LENGTH: 254 mm
COUNT: 3 WEIGHT: 3.96 Kg

Fig.9 – Cantidad total de elementos Fig.10 – Longitud total del refuerzo y peso total
del refuerzo.

10 Esta obra está licenciada bajo la Licencia Creative Commons. Atribución-NoComercial 4.0 Internacional.
Para ver una copia de esta licencia, visite http://creativecommons.org/licenses/by-nc/4.0/.
www.planbim.cl

<!-- p. 12 -->

IfcReinforcingBar (Barra de refuerzo)

La entidad IfcReinforcingBar representa una barra generalmente de acero fabricada con
deformaciones en su superficie, y es utilizada en construcciones de hormigón y albañilería para
aportar resistencia adicional. Una instancia individual de esta entidad puede representar una o más
barras. Esta entidad tiene tipos predefinidos que permiten especificar los diferentes tipos de barras
estándar según su propósito o uso. Los tipos predefinidos para IfcReinforcingBar son:

TABLA 10: TIPOS PREDEFINIDOS DE LUGAR DE BARRA DE REFUERZO (IfcReinforcingBar)
TIPOS
PREDEFINIDOS TRADUCCIÓN DESCRIPCIÓN FIGURA

Fig.11

ANCHORING ANCLAJE Refuerzo de anclaje.

Fig.12

EDGE BORDE Refuerzo de borde.

Fig.13

Refuerzo de amarre (por ejemplo,
LIGATURE ESTRIBO
una liga o un estribo).

Fig.14

MAIN PRINCIPAL Barra de refuerzo principal.

Fig.15

PUNCHING PUNZONANTE Refuerzo de punzonamiento.

Fig.16

RING ANILLO Refuerzo de anillo.

Fig.17

SHEAR CORTE El refuerzo es una barra de corte.

11 Esta obra está licenciada bajo la Licencia Creative Commons. Atribución-NoComercial 4.0 Internacional.
Para ver una copia de esta licencia, visite http://creativecommons.org/licenses/by-nc/4.0/.
www.planbim.cl

<!-- p. 13 -->

TABLA 10: TIPOS PREDEFINIDOS DE LUGAR DE BARRA DE REFUERZO (IfcReinforcingBar)
TIPOS
PREDEFINIDOS TRADUCCIÓN DESCRIPCIÓN FIGURA

Fig.18

STUD PERNO La barra de refuerzo es un perno.

Cualquier otro refuerzo que no
USERDEFINED DEFINIDO POR USUARIO pertenezca a las categorías
anteriores.

NOTDEFINED NO DEFINIDO Aún no se define el tipo de refuerzo.

Además, el esquema incluye atributos específicos para esta entidad. Estos son:

TABLA 11: ATRIBUTOS DE BARRA DE REFUERZO (IfcReinforcingBar)

NOMBRE TRADUCCIÓN DESCRIPCIÓN

CrossSectionArea Área de sección transversal El área efectiva de la sección transversal de la barra.

NominalDiameter Diámetro nominal El diámetro nominal que define la sección transversal de la barra.

BarLength Longitud de barra La longitud total de la barra. Para las barras dobladas se calcula
según estándares locales, con corrección para los dobleces.
BarSurface Superficie de barra Indicador de si la superficie de la barra es lisa o texturizada.

BendingShapeCode Código de forma de doblado Código de la forma de la barra según estándar ACI315, ISO3766 u
otro seleccionado para el proyecto. Se asume que se utilizará un
único estándar a lo largo del proyecto, el que debe ser
referenciado en la entidad IfcProject a través de
IfcDocumentReference.
BendingParameters Parámetros de doblado Parámetros de doblado de forma. Sus significados son definidos en
el código de la forma de la barra y su respectivo estándar.

𝑨= 𝝅𝒓𝟐

Fig.19 – CrossSectionArea Fig.20 – NominalDiameter Fig.21 – BarLength Fig.22 – BarSurface

Se debe tener en cuenta que tanto los parámetros del Pset_ElementComponentCommon,
como las mediciones del Qto_ReinforcingElementBaseQuantities son heredados por la entidad
IfcReinforcingBar, y por lo tanto todos estos parámetros están disponibles para incluir la información
necesaria.

12 Esta obra está licenciada bajo la Licencia Creative Commons. Atribución-NoComercial 4.0 Internacional.
Para ver una copia de esta licencia, visite http://creativecommons.org/licenses/by-nc/4.0/.
www.planbim.cl

<!-- p. 14 -->

IfcReinforcingMesh (Malla de refuerzo)

La entidad IfcReinforcingMesh representa una serie de barras longitudinales y transversales de
distintos diámetros, organizadas en ángulos de 90° unas de otras y soldadas en todos los puntos de
intersección. Usualmente se utilizan para reforzar losas de hormigón. Se incluyen en esta entidad tanto
mallas planas como inclinadas. Esta entidad no tiene un listado de tipos predefinidos asociada, pero
si se definen atributos específicos para esta entidad. Estos son:

TABLA 12: ATRIBUTOS DE MALLA DE REFUERZO (IfcReinforcingMesh)
NOMBRE TRADUCCIÓN DESCRIPCIÓN
MeshLength Longitud de malla Longitud general de la malla medida en
dirección longitudinal.
MeshWidth Ancho de malla Ancho general de la malla medido en
dirección transversal.
LongitudinalBarNominalDiameter Diámetro nominal de barras Diámetro nominal que indica la sección
longitudinales transversal de las barras longitudinales.
TransverseBarNominalDiameter Diámetro nominal de barras Diámetro nominal que indica la sección
transversales transversal de las barras transversales.
LongitudinalBarCrossSectionArea Área de sección transversal Área efectiva de la sección transversal de las
de barras longitudinales barras longitudinales de la malla.
TransverseBarCrossSectionArea Áreas de sección transversal Área efectiva de la sección transversal de las
de barras transversales barras transversales de la malla.
LongitudinalBarSpacing Espaciamiento de barras Espaciamiento entre barras longitudinales. Se
longitudinales asume una distribución uniforme, otros casos
deben ser gestionados a través de
clasificaciones o property sets.
TransverseBarSpacing Espaciamiento de barras Espaciamiento entre barras transversales. Se
transversales asume una distribución uniforme, otros casos
deben ser gestionados a través de
clasificaciones o property sets.
BendingShapeCode Código de forma de doblado Si la malla es del tipo doblada y no plana, este
atributo provee un código de forma según
estándares como ACI315, ISO3766 o similar. Se
asume que se utilizará un único estándar a lo
largo del proyecto, el que debe ser
referenciado en la entidad IfcProject a través
de IfcDocumentReference.
BendingParameters Parámetros de doblado Si la malla es del tipo doblada y no plana, este
atributo provee los parámetros de doblado de
la forma. Sus significados son definidos en el
código de la forma de la barra y su respectivo
estándar.

13 Esta obra está licenciada bajo la Licencia Creative Commons. Atribución-NoComercial 4.0 Internacional.
Para ver una copia de esta licencia, visite http://creativecommons.org/licenses/by-nc/4.0/.
www.planbim.cl

<!-- p. 15 -->

MeshWidth

MeshLength

TransverseBarSpacing

LongitudinalBarSpacing

Fig.23 – Entidad IfcReinforcingMesh

Se debe tener en cuenta que tanto los parámetros del Pset_ElementComponentCommon,
como las mediciones del Qto_ReinforcingElementBaseQuantities son heredados por la entidad
IfcReinforcingMesh, y por lo tanto todos sus parámetros están disponibles para incluir la información
necesaria.

14 Esta obra está licenciada bajo la Licencia Creative Commons. Atribución-NoComercial 4.0 Internacional.
Para ver una copia de esta licencia, visite http://creativecommons.org/licenses/by-nc/4.0/.
www.planbim.cl

<!-- p. 16 -->

IfcTendon (Tensor)

La entidad IfcTendon representa un elemento tipo cable, tensor, barra, varilla o hilo de acero,
utilizado para pretensar concreto.

Fig.24 – Entidad IfcTendon

Esta entidad tiene tipos predefinidos que permiten especificar el tipo de tensor dependiendo
de sus características. Los tipos predefinidos de la entidad IfcTendon son:

TABLA 13: TIPOS PREDEFINIDOS DE TENSOR (IfcTendon)
TIPOS PREDEFINIDOS TRADUCCIÓN DESCRIPCIÓN FIGURA

El tensor está configurado como una Fig.25
BAR BARRA
barra.
Fig.26
COATED RECUBIERTO El tensor tiene recubrimiento.

Fig.27
STRAND HILO El tensor es un hilo.

Fig.28
WIRE CABLE El tensor es un cable.

Cualquier otro tensor que no pertenezca a
USERDEFINED DEFINIDO POR USUARIO
las categorías anteriores.

NOTDEFINED NO DEFINIDO Aún no se define el tipo de tensor.

Además, el esquema incluye atributos específicos para esta entidad. Estos son:

TABLA 14: ATRIBUTOS DE TENSOR (IfcTendon)

NOMBRE TRADUCCIÓN DESCRIPCIÓN

NominalDiameter Diámetro nominal Diámetro nominal que define el tamaño de la sección
transversal de la parte pretensada del tensor.
CrossSectionArea Área de sección transversal Área efectiva de la sección transversal de la parte
pretensada del tensor.
SheathDiameter Diámetro de vaina Diámetro de la vaina o ducto que envuelve el tensor,
de incluirla.
TensionForce Fuerza de tensión Tensión máxima permitida que puede ser aplicada al
tensor.
PreStress Pretensado Pretensado que será aplicado al tensor.

FrictionCoefficient Coeficiente de fricción Coeficiente de fricción entre el tensor y su vaina
mientras este está sin ligar.
AnchorageSlip Deslizamiento de anclaje Deformación de un anclaje o deslizamiento de
tendones cuando el dispositivo pretensor es liberado.
MinCurvatureRadius Radio mínimo de curvatura Menor radio de curvatura calculado en toda la longitud
efectiva del tensor, donde las propiedades de tensión
son aún válidas.

15 Esta obra está licenciada bajo la Licencia Creative Commons. Atribución-NoComercial 4.0 Internacional.
Para ver una copia de esta licencia, visite http://creativecommons.org/licenses/by-nc/4.0/.
www.planbim.cl

<!-- p. 17 -->

Se debe tener en cuenta que tanto los parámetros del Pset_ElementComponentCommon,
como las mediciones del Qto_ReinforcingElementBaseQuantities son heredadas por la entidad
IfcTendon, y por lo tanto todos sus parámetros están disponibles para incluir la información necesaria.

16 Esta obra está licenciada bajo la Licencia Creative Commons. Atribución-NoComercial 4.0 Internacional.
Para ver una copia de esta licencia, visite http://creativecommons.org/licenses/by-nc/4.0/.
www.planbim.cl

<!-- p. 18 -->

IfcTendonAnchor (Anclaje de tensor)

La entidad IfcTendonAnchor representa la conexión en el extremo de un tensor para hormigón
pretensado y postensado.

Fig.29 – Entidad IfcTendonAnchor

Esta entidad tiene tipos predefinidos que permiten especificar el tipo de anclaje dependiendo
de sus características. Los tipos predefinidos de la entidad IfcTendonAnchor son:

TABLA 15: TIPOS PREDEFINIDOS DE ANCLAJE DE TENSOR (IfcTendonAnchor)

TIPOS
PREDEFINIDOS TRADUCCIÓN DESCRIPCIÓN FIGURA

Fig.30
El anclaje es un dispositivo intermedio que
COUPLER ACOPLADOR
conecta dos tendones.

Fig.31

FIXED_END EXTREMO FIJO El anclaje fija el extremo de un tensor.

Fig.32
El anclaje es o puede ser utilizado para
TENSIONING_END EXTREMO TENSIONANTE
pretensar el tensor.

Cualquier otro tensor que no pertenezca a las
USERDEFINED DEFINIDO POR USUARIO
categorías anteriores.

NOTDEFINED NO DEFINIDO Aún no se define el tipo de tensor.

Se debe tener en cuenta que tanto los parámetros del Pset_ElementComponentCommon, como
las mediciones del Qto_ReinforcingElementBaseQuantities son heredadas por la entidad
IfcTendonAnchor, y por lo tanto todos sus parámetros están disponibles para incluir la información
necesaria.

17 Esta obra está licenciada bajo la Licencia Creative Commons. Atribución-NoComercial 4.0 Internacional.
Para ver una copia de esta licencia, visite http://creativecommons.org/licenses/by-nc/4.0/.
www.planbim.cl

<!-- p. 19 -->

4 FIJACIONES (IfcFastener)

La entidad Fijaciones (IfcFastener) representa los componentes utilizados para conectar o unir
un elemento a otro. De esta entidad se excluyen las fijaciones mecánicas, que son representadas por
la entidad IfcMechanicalFastener.

Fig.33 – Entidad IfcFastener

Esta entidad tiene tipos predefinidos que permiten especificar el tipo de fijación dependiendo de sus
características. Los tipos predefinidos de la entidad IfcFastener son:

TABLA 16: TIPOS PREDEFINIDOS DE FIJACIONES (IfcFastener)

TIPOS
PREDEFINIDOS TRADUCCIÓN DESCRIPCIÓN FIGURA

Fig.34

Una conexión que utiliza adhesivos para
GLUE ADHESIVO
unir dos elementos.

Fig.35
Mezcla de minerales u otros materiales
utilizados para rellenar juntas y
MORTAR MORTERO
posiblemente cumplir la función de
soporte de cargas.

Fig.36

Cordón de soldadura entre partes
WELD SOLDADURA metálicas o de otros materiales
apropiados.

Cualquier otra fijación que no
USERDEFINED DEFINIDO POR USUARIO
pertenezca a las categorías anteriores.

NOTDEFINED NO DEFINIDO Aún no se define el tipo de fijación.

18 Esta obra está licenciada bajo la Licencia Creative Commons. Atribución-NoComercial 4.0 Internacional.
Para ver una copia de esta licencia, visite http://creativecommons.org/licenses/by-nc/4.0/.
www.planbim.cl

<!-- p. 20 -->

Entre las propiedades que se incluyen en esta entidad, está un grupo de parámetros
específico para las soldaduras. Este grupo de parámetros se denomina dentro del esquema como
Pset_FastenerWeld, y las propiedades que incluye son:

TABLA 17: Pset_FastenerWeld

NOMBRE TRADUCCIÓN DESCRIPCIÓN
Type1 Tipo 1 Tipo de cordón de soldadura según la ISO 2553. Las soldaduras combinadas
reciben los dos símbolos correspondientes en la dirección del eje normal del
sistema de coordenadas. Por ejemplo, una soldadura X se especifica como:
Type1 = ‘V’ y Type2 = ‘V’.
Type2 Tipo 2 Tipo de cordón de soldadura según la ISO 2553. Las soldaduras combinadas
reciben los dos símbolos correspondientes en la dirección del eje normal del
sistema de coordenadas. Por ejemplo, una soldadura X se especifica como:
Type1 = ‘V’ y Type2 = ‘V’.
Surface1 Superficie 1 Rasgo de la superficie del cordón de soldadura, que puede ser plano, curvo o
convexo. Las soldaduras combinadas reciben los dos símbolos
correspondientes, tal como para Type1 y Type2.
Surface2 Superficie 2 Rasgo de la superficie del cordón de soldadura, que puede ser plano, curvo o
convexo. Las soldaduras combinadas reciben los dos símbolos
correspondientes, tal como para Type1 y Type2.
Process Proceso Número de referencia al proceso de soldado de acuerdo con la ISO 4063,
código de hasta tres dígitos de longitud.
ProcessName Nombre del Proceso Nombre del proceso de soldado. Este parámetro es una alternativa a la
propiedad numérica ‘Process’.
a Cota ‘a’ de acuerdo con la ISO 2553.

c Cota ‘b’ de acuerdo con la ISO 2553.

d Cota ‘d’ de acuerdo con la ISO 2553.

e Cota ‘e’ de acuerdo con la ISO 2553.

l Cota ‘l’ de acuerdo con la ISO 2553.

n Cuantía ‘n’ de acuerdo con la ISO 2553.

s Cota ‘s’ de acuerdo con la ISO 2553.

z Cota ‘z’ de acuerdo con la ISO 2553.

Intermittent Intermitente Si se trata de una soldadura tipo filete, señala si esta es intermitente o no.

Staggered Alternada Si se trata de una soldadura intermitente, señala si esta es alternada o no.

Se debe tener en cuenta que los parámetros del Pset_ElementComponentCommon son
heredados por la entidad IfcFastener, y por lo tanto están disponibles para incluir la información
necesaria.

19 Esta obra está licenciada bajo la Licencia Creative Commons. Atribución-NoComercial 4.0 Internacional.
Para ver una copia de esta licencia, visite http://creativecommons.org/licenses/by-nc/4.0/.
www.planbim.cl

<!-- p. 21 -->

5 FIJACIONES MECÁNICAS (IfcMechanicalFastener)

La entidad Fijación Mecánica (IfcMechanicalFastener) representa los componentes que
conecta elementos de una construcción de forma mecánica. Una instancia de esta entidad puede
representar una fijación individual o un grupo de fijaciones, por ejemplo, una fila de pernos o clavos.

Fig.37 – Entidad IfcMechanicalFastener

Esta entidad tiene tipos predefinidos que permiten especificar el tipo de fijación mecánica
dependiendo de sus características. Los tipos predefinidos de la entidad IfcMechanicalFastener son:

TABLA 18: TIPOS PREDEFINIDOS DE FIJACIONES MECÁNICAS (IfcMechanicalFastener)

TIPOS PREDEFINIDOS TRADUCCIÓN DESCRIPCIÓN FIGURA

Fig.38

Perno de anclaje en hormigón, roca o
ANCHORBOLT PERNO DE ANCLAJE
albañilería.

Varilla cilíndrica con hilo que se acopla con Fig.39
una perforación con hilo similar para formar
BOLT PERNO una fijación. Este tipo de fijación mecánica
usualmente involucra una o más tuercas y
golillas.
Fig.40

Varilla cilíndrica que se introduce en
DOWEL ESPIGA
perforaciones de las piezas conectadas.

Fig.41

Pieza metálica fina y con punta que se
NAIL CLAVO
clava en materiales como fijación.

Fig.42
Placa metálica con puntos perforados que
NAILPLATE PLACA DE CLAVOS se sobrepone a piezas conectadas y es
presionada sobre el material.

20 Esta obra está licenciada bajo la Licencia Creative Commons. Atribución-NoComercial 4.0 Internacional.
Para ver una copia de esta licencia, visite http://creativecommons.org/licenses/by-nc/4.0/.
www.planbim.cl

<!-- p. 22 -->

TABLA 18: TIPOS PREDEFINIDOS DE FIJACIONES MECÁNICAS (IfcMechanicalFastener)

TIPOS PREDEFINIDOS TRADUCCIÓN DESCRIPCIÓN FIGURA

Fig.43
Una fijación con una cabeza en un extremo
mientras que el otro extremo es martillado
RIVET REMACHE
luego de pasar por las perforaciones de las
piezas que se unen.

Fig.44

SCREW TORNILLO Fijación con hilo cónico y cabeza ranurada.

Fig.45
Conector con forma de anillo que calza en
anillos chaveteados en las piezas
SHEARCONNECTOR CONECTOR DE CORTE conectadas, o un conector circular o
cuadrado con dientes que es presionado
sobre las piezas conectadas.

Fig.46

Pieza metálica con doble punta que se
STAPLE GRAPA
martilla en materiales como fijación.

Fig.47

Fijación cilíndrica con una cabeza en un
PERNO CONECTOR DE extremo y el otro extremo es soldado a
STUDSHEARCONNECTOR
CORTE partes metálicas, utilizado en estructuras
compuestas de acero y hormigón.

DEFINIDO POR Cualquier otra fijación mecánica que no
USERDEFINED
USUARIO pertenezca a las categorías anteriores.

Aún no se define el tipo de fijación
NOTDEFINED NO DEFINIDO
mecánica.

21 Esta obra está licenciada bajo la Licencia Creative Commons. Atribución-NoComercial 4.0 Internacional.
Para ver una copia de esta licencia, visite http://creativecommons.org/licenses/by-nc/4.0/.
www.planbim.cl

<!-- p. 23 -->

Entre las propiedades que se incluyen en esta entidad, existen dos grupos de parámetros
específicos para anclajes y pernos. Estos grupos de parámetros se denominan en el esquema:
Pset_MechanicalFastenerAnchorBolt y Pset_MechanicalFastenerBolt. Las propiedades que incluye
cada uno de ellos son:

TABLA 19: Pset_MechanicalFastenerAnchorBolt

NOMBRE TRADUCCIÓN DESCRIPCIÓN
AnchorBoltLength Longitud de perno de anclaje Longitud del perno de anclaje.

AnchorBoltDiameter Diámetro de perno de anclaje Diámetro nominal de los pernos de anclaje.

AnchorBoltThreadLength Longitud de hilo del perno de Longitud del hilo del perno de anclaje.
anclaje
AnchorBoltProtrusionLength Profusión de perno de anclaje Longitud de la parte saliente del perno de anclaje.

TABLA 20: Pset_MechanicalFastenerBolt
NOMBRE TRADUCCIÓN DESCRIPCIÓN
ThreadDiameter Diámetro de hilo Diámetro nominal del hilo, si es diferente al diámetro nominal general del perno.

ThreadLength Longitud de hilo Longitud nominal del hilo.

NutsCount Cuenta de tuercas Cantidad de tuercas que serán montadas en un perno.

WashersCount Cuenta de golillas Cantidad de Golillas que serán montadas en un perno.

HeadShape Forma de cabeza Forma de la cabeza del perno.

KeyShape Forma de ranura Si aplica, forma de la ranura de la cabeza del perno.

NutShape Forma de tuerca Forma de la tuerca.

WasherShape Forma de golilla Forma de la golilla.

Se debe tener en cuenta que el grupo de propiedades Pset_ElementComponentCommon es
heredado por la entidad IfcMechanicalFastener, y por lo tanto todos sus parámetros están disponibles
para incluir la información necesaria.

22 Esta obra está licenciada bajo la Licencia Creative Commons. Atribución-NoComercial 4.0 Internacional.
Para ver una copia de esta licencia, visite http://creativecommons.org/licenses/by-nc/4.0/.
www.planbim.cl

<!-- p. 24 -->

www.planbim.cl

in

23 Esta obra está licenciada bajo la Licencia Creative Commons. Atribución-NoComercial 4.0 Internacional.
Para ver una copia de esta licencia, visite http://creativecommons.org/licenses/by-nc/4.0/.
www.planbim.cl
