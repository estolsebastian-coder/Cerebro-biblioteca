---
type: libro
title: "Plan de Trabajo Proyecto: “Fomento a la Implementación de metodologías BIM en PJUD”Año 2018-2019"
author: "Paulina Godoy Del Campo"
categoria: "BIM Y HBIM"
paginas: 22
extraccion: "mixto: 1 páginas por OCR (spa)"
fuente: "local:E:/MATERIAL DE CONSULTA/BIM Y HBIM/02. Planbim/documentación/entidades-ifc-para-equipamiento-hospitalario.pdf"
convertido: 2026-10-16
---

# Plan de Trabajo Proyecto: “Fomento a la Implementación de metodologías BIM en PJUD”Año 2018-2019

> Texto extraído de `BIM Y HBIM\02. Planbim\documentación\entidades-ifc-para-equipamiento-hospitalario.pdf` (22 páginas, mixto: 1 páginas por OCR (spa)). El PDF original está en el disco E: (MATERIAL DE CONSULTA); `<!-- p. N -->` marca el inicio de cada página.

<!-- p. 1 -->

FICHA DE
ENTIDADES IFC
PARA EQUIPAMIENTO
HOSPITALARIO Y CLÍNICO
Según ISO 16739-1:2018
VERSIÓN 1.0

Mayo 2020

<!-- p. 2 -->

Esta obra está licenciada bajo la Licencia Creative Commons
Atribución-NoComercial 4.0 Internacional.
Para ver una copia de esta licencia, visite http://creativecommons.org/licenses/by-nc/4.0/.

1

<!-- p. 3 -->

1 ÍNDICE

Contenido
• 1 ÍNDICE ................................................................................................................................................. 2
• 2 INTRODUCCIÓN .................................................................................................................................. 3
• 3 EQUIPOS E INSTALACIONES MÉDICAS (IfcMedicalDevice) ............................................................. 6
AIRSTATION (Estación de aire): ............................................................................................................. 7
FEEDAIRUNIT (Unidad de alimentación de aire): ............................................................................... 7
OXYGENGENERATOR (Generador de oxígeno): ............................................................................... 7
OXYGENPLANT (Planta de oxígeno): .................................................................................................. 7
VACUUMSTATION (Estación de vacío): ............................................................................................... 8
• 4 DISTRIBUCIÓN Y TUBERÍAS MEP (IfcDistributionFlowElement) .......................................................... 9
Válvulas (IfcValve) ................................................................................................................................. 9
Estanques (IfcTank) .............................................................................................................................. 10
• 5 EQUIPOS E INSTALACIONES SANITARIAS (IfcSanitaryTerminal) ..................................................... 11
• 6 MUEBLES (IfcFurniture) ...................................................................................................................... 12
• 7 PUERTAS (IfcDoor) ............................................................................................................................. 13
Tipo predefinido (IfcDoorTypeEnum) ................................................................................................ 13
Tipo de Operación (IfcDoorTypeOperationEnum) .......................................................................... 14
Propiedades de Panel de Puerta (IfcDoorPanelProperties) .......................................................... 17
Propiedades de Marco de Puerta (IfcDoorLiningProperties) ........................................................ 18

2

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
nacional. Para asegurar que la información intercambiada por los distintos participantes de un
proyecto sea interoperable y estandarizada, el Estándar BIM para Proyectos Públicos adopta el
esquema IFC, utilizándolo como base para:

• Especificar las entidades que componen los distintos modelos BIM,
• Especificar el tipo de Información (TDI) que estos deben contener según los Usos BIM
seleccionados
• Especificar el nivel de Información (NDI) necesario para los Estado de Avance de la
Información de los Modelos (EAIM) definidos para las etapas del proyecto.

Para facilitar la aplicación del esquema IFC en tipologías que utilizan elementos particulares,
como es el caso de los establecimientos de salud, se elabora la presente Ficha de Entidades para
Equipamiento Hospitalario y Clínico. Este documento dará mayor detalle a la información que se
encuentra en la Matriz de Información de Entidades, sobre las entidades relevantes para
equipamiento hospitalario y que se pueden encontrar en la Tabla 03 del Estándar BIM para Proyectos
Públicos. En esta tabla, la entidad Equipos e Instalaciones es nombrada de forma genérica, para
luego especificar en la Matriz de Información de Entidades sus dos formas específicas. Una de ellas
representa equipamiento de uso exclusivo en infraestructura hospitalaria o clínica: la entidad Equipos
e Instalaciones Médicas (IfcMedicalDevice). Y la otra agrupa elementos utilizados de forma
transversal en varias tipologías, pero tiene especial importancia la sanitización personal y eliminación
de aguas sucias. Esta es la entidad Equipos e Instalaciones Sanitarias (IfcSanitaryTerminal). Ambas
entidades se incluyen en el presente documento. Además, se incluyen otras entidades relevantes
para la operación de un hospital o clínica, como el mobiliario hospitalario representado en la entidad
Muebles (IfcFurniture), y los distintos tipos de puertas según su utilidad y operación, en la entidad
Puertas (IfcDoor). Para mayor claridad, se incluyen esquemas conceptuales de los elementos. Estos
esquemas son referenciales, ya que cada elemento o equipo puede variar en su forma y aspecto.

Para la versión 1.0 de este documento, se hace alusión a las entidades incluidas en la versión IFC
4.0.2.1 (IFC 4 ADD2 TC1), publicada en la ISO 16739-1:2018. Para utilizar esta ficha de forma correcta,
se debe tener en cuenta la estructura general de las entidades en el esquema IFC. En esta estructura,
una entidad representa una categoría de elementos, definidas por propiedades comunes. Dentro
del esquema existen entidades de carácter general, que sientan las bases para la creación de
entidades más específicas y que les heredan algunas de sus propiedades. Las figuras 1 y 2 que se
encuentran a continuación, representan a través de un esquema simplificado una entidad general
y una específica respectivamente.

3

<!-- p. 5 -->

ENTIDAD OBJETO
IfcObject

ENTIDAD PRODUCTO
IfcProduct

ENTIDAD ELEMENTO
IfcElement

Fig.1 – Esquema Entidades Generales

ENTIDAD ELEMENTO
IfcElemento

ENTIDAD ELEMENTO DE DISTRIBUCIÓN
IfcDistributionElement

ENTIDAD ELEMENTO DE DISTRIBUCIÓN Y TUBERÍAS MEP
IfcDistributionFlowElement

ENTIDAD TERMINAL DE FLUJO
IfcFlowTerminal

ENTIDAD EQUIPOS E INSTALACIONES MÉDICAS ENTIDAD EQUIPOS E INSTALACIONES SANITARIAS
IfcMedicalDevice IfcSanitaryTerminal

Fig.2 – Esquema Entidades Específicas

Para lograr mayor especificidad, se utiliza la información en la propiedad tipo predefinido
(TypeEnum). Esta propiedad consiste en un listado de tipos de elementos derivados de una entidad,
que ya están definidos dentro del esquema, y que corresponden a los más comúnmente utilizados.
Los tipos predefinidos de las entidades incluidas en esta ficha se encuentra en la Matriz de
Información de Entidades, que puede ser descargada en https://planbim.cl/matriz-de-informacion/ .
A diferencia de la estructura revisada anteriormente, un tipo predefinido (TypeEnum) no modifica el
nombre ni el tipo de entidad, sino que utiliza un atributo específico para dar mayor precisión a la
definición del elemento.

• TIPO A ENTIDAD TIPO PREDEFINIDO • TIPO B Entity TypeEnum • TIPO C

Fig.3 – Esquema Tipo Predefinido (TypeEnum)

El listado de los tipos predefinidos de las entidades incluidas en la Matriz de Información de
Entidades, están definidas en la ISO16739-1:2018 (IFC4). En la siguiente figura se presentan los tipos
predefinidos de la entidad Equipos e Instalaciones Médicas (IfcMedicalDevice):

4

<!-- p. 6 -->

• ESTACIÓN DE AIRE
• UNIDAD DE ALIMENTACIÓN DE AIRE
EQUIPOS E • GENERACIÓN DE OXIGENO TIPO PREDEFINIDO
INSTALACIONES MÉDICAS • PLANTA DE OXIGENO IfcMedicalDeviceTypeEnum
IfcMedicalDevice • ESTACIÓN DE VACÍO
• DEFINIDO POR USUARIO (USERDEFINED)
• NO DEFINIDO (NOTDEFINED

Fig.4 – Tipos predefinidos de Equipos e Instalaciones Médicas

En este listado de tipos predefinidos, también existe la opción de que el usuario ingrese un tipo
no especificado en la norma ISO, utilizando la opción USERDEFINED (DEFINIDO POR USUARIO), o
dejarlo sin definición (NOTDEFINED). De seleccionar la opción USERDEFINED, se utilizará el atributo
ObjectType (Tipo de Objeto) para ingresar la información correspondiente. Por ejemplo, para
especificar que el equipos o instalación médica corresponde a un equipo especial, se debe utilizar
esta última opción, ya que el esquema no incluye este tipo predefinido.

• ESTACIÓN DE AIRE
• UNIDAD DE ALIMENTACIÓN DE AIRE
EQUIPOS E • GENERACIÓN DE OXIGENO TIPO DE OBJETO INSTALACIONES MÉDICAS • PLANTA DE OXIGENO ObjectType IfcMedicalDevice • ESTACIÓN DE VACÍO
• DEFINIDO POR USUARIO (USERDEFINED)
• NO DEFINIDO (NOTDEFINED

Fig.5 – Esquema Equipos e Instalaciones Médicas

En la Matriz de Información de Entidades, se puede encontrar el listado de Tipos Predefinidos en
la ficha individual de cada entidad, si corresponde.

Para comprender cómo se ordena la información en el esquema IFC, revisar las distintas
versiones, y las definiciones básicas de sus miembros y características, se recomienda revisar la página
oficial de buildingSMART:

https://technical.buildingsmart.org/standards/ifc/ifc-schema-specifications/

5

<!-- p. 7 -->

3 EQUIPOS E INSTALACIONES MÉDICAS (IfcMedicalDevice)
La entidad IfcMedicalDevice1 agrupa el equipamiento hospitalario que maneja el flujo de los
distintos gases clínicos. El equipo debe ir entonces conectado a un sistema de tuberías que servirán
para distribuir estos gases clínicos. Dependiendo de la acción que el equipo ejecute sobre estos
gases, y del tipo de gas clínico sobre el cual actúa, se le asignará uno de los siguientes tipos
predefinidos existentes en el esquema IFC:

\1. AIRSTATION
\2. FEEDAIRUNIT
\3. OXYGENGENERATOR
\4. OXYGENPLANT
\5. VACUUMSTATION

5 2

3
1

4

Fig. 6 – Simplificación de los distintos dispositivos existentes en una instalación hospitalaria

La información referida a los parámetros y atributos que es posible ingresar para esta entidad
según cada Nivel y Tipo de Información (NDI y TDI), se encuentra en la Matriz de Información de
Entidades. A continuación, se detalla la definición de cada uno de los tipos predefinidos de la entidad
Equipos e Instalaciones Médicas:

1 – Según buildingSMART, “Un IfcMedicalDevice está conectado a un sistema de tuberías médicas y funciona con gases
médicos para realizar una función específica. Los gases médicos incluyen aire médico, vacío médico, oxígeno, dióxido de
carbono, nitrógeno y óxido nitroso.”

6

<!-- p. 8 -->

AIRSTATION (Estación de aire):
Dispositivo que proporciona aire médico purificado, compuesto por un compresor de aire y una línea
de tratamiento de aire.*

FEEDAIRUNIT (Unidad de alimentación de aire):
Dispositivo que alimenta aire a un generador de oxígeno, compuesto por un compresor de aire, una
línea de tratamiento de aire y un receptor de aire.*

OXYGENGENERATOR (Generador de oxígeno):
Una unidad de almacenamiento de agua conectada a un terminal sanitario equipado con un
dispositivo, operado automáticamente o por el usuario, que descarga agua para limpiar una
bandeja de inodoro, urinario o tolva.*

OXYGENPLANT (Planta de oxígeno):
Dispositivo que combina una unidad de aire de alimentación, un generador de oxígeno y cilindros
de oxígeno de respaldo.*

\* Definiciones según ISO16739-1:2018. Los equipos representados son sólo referenciales. La forma real de cada equipo
dependerá del modelo y fabricante de este.

7

<!-- p. 9 -->

VACUUMSTATION (Estación de vacío):
Aparato de aguas residuales para recibir, retener o desechar líquidos de procesos domésticos,
culinarios, de laboratorio o industriales.*

\* Definiciones según ISO16739-1:2018. Los equipos representados son sólo referenciales. La forma real de cada equipo
dependerá del modelo y fabricante de este.

8

<!-- p. 10 -->

4 DISTRIBUCIÓN Y TUBERÍAS MEP (IfcDistributionFlowElement)
Los accesorios necesarios para conectar y alimentar los equipos e instalaciones revisados en el
apartado anterior se pueden encontrar en la entidad Distribución y Tuberías MEP
(IfcDistributionFlowElement). En específico, se utilizan las subentidades Válvulas (IfcValve) y Estanques
(IfcTank). Tanto la entidad general como las subentidades mencionadas se encuentran en el
Estándar BIM para Proyectos Públicos y en la Matriz de Información de Entidades. A continuación, se
incluyen indicaciones de cómo utilizar estas subentidades en el contexto del equipamiento
hospitalario y clínico.

Válvulas (IfcValve)
Las salidas para gases médicos deben usar IfcValve con PredefinedType = GASTAP, que
contiene un IfcDistributionPort con FlowDirection = SINK y PredefinedType = COMPRESSEDAIR, VACUUM
o CHEMICAL.*

4.1

\* Definiciones según ISO16739-1:2018. Los equipos representados son sólo referenciales. La forma real de cada equipo
dependerá del modelo y fabricante de este.

9

<!-- p. 11 -->

Entidad: IfcValve
Tipo Predefinido: GASTAP

Entidad: IfcDistributionPort
Tipo Predefinido: COMPRESSEDAIR/VACUUM/
CHEMICAL
Dirección del flujo (FlowDirection): SINK

Estanques (IfcTank)
Los tanques para gases médicos deben usar IfcTank con PredefinedType = PRESSUREVESSEL, que
contiene un IfcDistributionPort con FlowDirection = SOURCE y PredefinedType = CHEMICAL, y tener
conjuntos de propiedades en el puerto que indiquen el tipo de gas y el rango de presión.*

Entidad: IfcTank
Tipo Predefinido: PRESSUREVESSEL

Entidad: IfcDsitributionPort
Tipo Predefinido: CHEMICAL
Dirección del flujo (FlowDirection): SOURCE

\* Definiciones según ISO16739-1:2018. Los equipos representados son sólo referenciales. La forma real de cada equipo
dependerá del modelo y fabricante de este.
10

<!-- p. 12 -->

5 EQUIPOS E INSTALACIONES SANITARIAS (IfcSanitaryTerminal)
Los Equipos e Instalaciones Sanitarias clasificadas en el esquema IFC como IfcSanitaryTerminal,
son aquellos aparatos fijos que usualmente reciben un suministro de agua para beber, lavar o eliminar
aguas sucias. También se incluyen en esta entidad algunos equipos que funcionan en conjunto a uno
de estos aparatos. Los tipos predefinidos de esta entidad son:
\1. BATH: Aparato sanitario para inmersión del cuerpo humano o partes de él.
\2. BIDET: Aparato de aguas residuales para lavar los órganos excretores mientras está sentado
en el recipiente.
\3. CISTERN: Una unidad de almacenamiento de agua conectada a un terminal sanitario
equipado con un dispositivo, operado automáticamente o por el usuario, que descarga agua
para limpiar una bandeja de inodoro, urinario o tolva.
\4. SHOWER: Instalación o dispositivo de aguas residuales que emite un chorro de agua para lavar
el cuerpo humano.
\5. SINK: Aparato de aguas residuales para recibir, retener o desechar líquidos de procesos
domésticos, culinarios, de laboratorio o industriales.
\6. SANITARYFOUNTAIN: Un terminal sanitario que proporciona un chorro de agua a baja presión
para un propósito específico.
\7. TOILETPAN: Aparato de suelo para la eliminación de excrementos.
\8. URINAL: Aparato del suelo que recibe orina y lo dirige a una salida de desechos.
\9. WASHHANDBASIN: Aparato de aguas residuales para el lavado de las partes superiores del
cuerpo.
En la figura 7 se muestran algunos de los tipos predefinidos de la entidad IfcSanitaryTerminal. Tanto la
entidad como sus tipos predefinidos se encuentran en la Matriz de Información de Entidades.

8

4

5

3

7

Fig.7 Representación de algunos tipos predefinidos de la entidad IfcSanitaryTerminal

11

<!-- p. 13 -->

6 MUEBLES (IfcFurniture)
Para el mobiliario clínico se debe utilizar la entidad Muebles (IfcFurniture), aplicando el tipo
predefinido que corresponda. Además, para especificar si el mobiliario es adosado o no, se debe
utilizar el parámetro incluido en el conjunto de propiedades Pset_FurnitureTypeCommon, IsBuiltIn. Este
parámetro almacena información de tipo booleano, por lo que se debe definir como verdadero
(True) si el mueble es adosado, y falso (False) si no lo es.

Los tipos predefinidos para esta entidad son:
\1. CHAIR: Mueble que sirve de asiento para una sola persona.
\2. TABLE: Mueble con una superficie encimera para múltiples personas.
\3. DESK: Mueble con una superficie encimera y opcionalmente cajones, para una sola persona
\4. BED: Mueble utilizado para dormir.
\5. FILECABINET: Mueble con cajones deslizantes, utilizado para almacenar documentos.
\6. SHELF: Mueble para almacenar libros u otros objetos.
\7. SOFA: Mueble que sirve de asiento para múltiples personas.

En la figura 8 se muestran algunos de estos tipos predefinidos, además de ejemplos de tipos definidos
por usuario. Tanto la entidad Muebles como sus tipos predefinidos se pueden encontrar en la Matriz
de Información de Entidades.

TIPO PREDEFINIDO: USERDEFINED
OBJECT TYPE: CLOSET
PSET_FURNITURETYPECOMMON:
• ISBUILTIN: TRUE
TIPO PREDEFINIDO: USERDEFINED
OBJECT TYPE: BEDSIDECABINET
PSET_FURNITURETYPECOMMON:
• ISBUILTIN: FALSE

4

1

Fig. 8 Representación de algunos de los tipos predefinidos de la entidad IfcFurniture

12

<!-- p. 14 -->

7 PUERTAS (IfcDoor)
Las puertas son elementos que se encuentran en toda clase de edificaciones, pero que son
especialmente importantes en la construcción de un edificio hospitalario, por lo que se especifican
más a fondo sus atributos y parámetros en esta ficha. La entidad Puertas (IfcDoor) tiene algunas
particularidades dentro del esquema IFC. Además de tener un Tipo Predefinido (IfcDoorTypeEnum),
las puertas tienen un Tipo de Operación (IfcDoorTypeOperationEnum), que contiene la información
de la forma que tiene de operar o funcionar. Aquí se encuentran, por ejemplo, la puerta giratoria,
enrollable, deslizante, plegable, de vaivén, entre otras. Tanto la entidad Puertas como sus tipos
predefinidos y de operación se encuentran especificadas en la Matriz de Información de Entidades.
Otras propiedades que pueden ser especificadas en la entidad puerta son la información del panel
de la puerta (IfcDoorPanelProperties), y la información de su marco (IfcDoorLiningProperties). El
presente documento complementa la información del Estándar BIM para Proyectos Públicos y la
Matriz de Información de Entidades, incluyendo la descripción de estas últimas propiedades.

Tipo predefinido (IfcDoorTypeEnum)
• DOOR: Puerta estándar usualmente ubicada en una apertura de muro, como un panel de
puerta en muros cortinas, o como puerta independiente.

• GATE: Punto de entrada a una propiedad, usualmente ubicada en una cerca. También puede
ser un portón independiente.

• TRAPDOOR: Puerta especial que se ubica horizontalmente en la apertura de una losa. Se utiliza
generalmente para acceder a un ático o bodega.

13

<!-- p. 15 -->

Tipo de Operación (IfcDoorTypeOperationEnum)
• SINGLE_SWING_LEFT: Puerta con un panel que se abre (se balancea) hacia la izquierda. Las
bisagras están en el lado izquierdo según se ve en la dirección del eje y positivo.

• SINGLE_SWING_RIGHT: Puerta con un panel que se abre (se balancea) hacia la derecha. Las
bisagras están en el lado derecho según se ve en la dirección del eje y positivo.

• DOUBLE_DOOR_SINGLE_SWING: Puerta con dos paneles, uno se abre (se balancea) hacia la
izquierda y el otro se abre (se balancea) hacia la derecha.

• DOUBLE_SWING_LEFT: Puerta con un panel que gira en ambas direcciones y hacia la izquierda en
la dirección de tráfico principal. También llamada puerta de doble efecto.

• DOUBLE_SWING_RIGHT: Puerta con un panel que gira en ambas direcciones y hacia la derecha
en la dirección del tráfico principal. También llamada puerta de doble efecto.

14

<!-- p. 16 -->

• DOUBLE_DOOR_DOUBLE_SWING: Puerta con dos paneles, uno oscila en ambas direcciones y
hacia la derecha en la dirección de tráfico principal, la otra también en ambas direcciones y
hacia la izquierda en la dirección de tráfico principal.

• DOUBLE_DOOR_ SINGLE_SWING_OPPOSITE_LEFT: Puerta con dos paneles que se abren hacia la
izquierda, un panel gira en una dirección y el otro panel gira en la dirección opuesta.

• DOUBLE_DOOR_SINGLE_SWING_OPPOSITE_RIGHT: Puerta con dos paneles que se abren hacia la
derecha, un panel gira en una dirección y el otro panel gira en la dirección.

• SLIDING_TO_LEFT: Puerta con un panel que se desliza hacia la izquierda.

• SLIDING_TO_RIGHT: Puerta con un panel que se desliza hacia la derecha.

• DOUBLE_DOOR_SLIDING: Puerta con dos paneles, uno se desliza hacia la izquierda y el otro se
desliza hacia la derecha.

• FOLDING_TO_LEFT: Puerta con un panel que se dobla hacia la izquierda.

• FOLDING_TO_RIGHT: Puerta con un panel que se dobla hacia la izquierda.

15

<!-- p. 17 -->

• DOUBLE_DOOR_FOLDING: Puerta con dos paneles, uno se pliega a la izquierda y el otro se pliega a la
derecha.

• REVOLVING: Una puerta de entrada que consta de cuatro hojas en forma de cruz y que gira
alrededor de un eje vertical central (los cuatro paneles están descritos por una sola propiedad
del panel IfcDoor).

• ROLLINGUP: Puerta que se abre enrollando.

• SWING_FIXED_LEFT: Puerta con un panel que se abre (se balancea) hacia la izquierda y un panel
fijo. Las bisagras del panel oscilante están en el lado izquierdo según se ve en la dirección del
eje y positivo.

• SWING_FIXED_RIGHT: Puerta con un panel que se abre (se balancea) hacia la derecha y un
panel fijo. Las bisagras del panel oscilante están en el lado derecho según se ve en la dirección
del eje y positivo.

16

<!-- p. 18 -->

Propiedades de Panel de Puerta (IfcDoorPanelProperties)
El panel de una puerta es cada una de las hojas de esta, que se abren para permitir el paso de
individuos o bienes. Los atributos definidos en IfcDoorPanelProperties se utilizan para describir de forma
paramétrica la forma y operación de los paneles de una puerta. A continuación, se describen estos
atributos, complementando la información ya incluida en la Matriz de Información de Entidades. Para
asegurar la claridad de estos conceptos, las figuras 9 y 10 representan algunas de las propiedades
del panel de una puerta.
• PanelDepth (Profundidad de panel): Profundidad del panel de la puerta medido
perpendicularmente al plano de la hoja de esta.

• PanelOperation (Operación de panel): Define la forma de operar de dicho panel. Este atributo
debe coincidir con el Tipo de Operación de la puerta.

• PanelWidth (Ancho de panel): Ancho del panel expresado con relación a la apertura total de
la puerta. Este valor debe estar definido para todas las puertas cuyo Tipo de Operación defina
estar compuesta por más de un panel.

• PanelPosition (Posición de panel): Posición del panel en la puerta. Esta posición debe coincidir
con lo especificado en el Tipo de Operación de la puerta.

Fig.9 Representación de las propiedades de una puerta de un panel

Fig.10 Representación de las propiedades de una puerta de dos paneles
17

<!-- p. 19 -->

Propiedades de Marco de Puerta (IfcDoorLiningProperties)
El marco de puerta es el elemento que sujeta sus hojas y les permite tener una posición fija. La
subentidad que agrupa sus propiedades, IfcDoorLiningProperties no contiene una representación
geométrica. Sin embargo, incluye los datos necesarios para crear la forma de la puerta. A
continuación, se describen estas propiedades, complementando la información ya incluida en la
Matriz de Información de Entidades. Además, las figuras 11 a 15 permiten visualizar los atributos
descritos.

• LiningDepth (Profundidad de Marco): Profundidad del marco de una puerta, medido de forma
perpendicular al plano de este marco.

• LiningThickness (Espesor de Marco): Espesor del marco del marco de la puerta, según muestra
la figura 11.

• ThresholdDepth (Profundidad de umbral): Profundidad (dimensión perpendicular al plano de
la hoja de la puerta) del umbral de una puerta.

• ThresholdThickness (Espesor de umbral): Espesor del umbral de una puerta, según muestra la
figura 14.

• TransomThickness (Espesor de travesaño): Espesor (ancho en paralelo a la hoja de la puerta)
del travesaño que divide la hoja de la puerta de un cristal o ventana superior.

• TransomOffest (Distancia de travesaño): Distancia a la que se encuentra el travesaño que
divide la hoja de la puerta de un cristal o ventana superior. Esta distancia se mide desde la
cara inferior de la apertura de la puerta.

• LiningOffset (Separación Marco): Distancia (perpendicular al plano de la hoja de la puerta)
del marco de la puerta.

• ThresholdOffset (Distancia de umbral): Distancia (perpendicular al plano de la hoja de la
puerta) del umbral de la puerta.

• CasingThickness (Espesor Cubierta): Espesor de la cubierta (en el plano de la hoja de la
puerta), según se muestra en la figura 13.

• CasingDepth (Profundidad Cubierta): Profundidad de la cubierta (en el plano de la hoja de
la puerta, según muestra la figura 13.

• LiningToPanelOffsetX (Distancia entre Marco y Panel en eje X): Distancia entre el marco y el
panel de la puerta, medido en el eje x de la ubicación local de esta (ver Fig. 11 y 12).

• LiningToPanelOffsetY (Distancia entre Marco y Panel en eje Y): Distancia entre el marco y el
panel de la puerta, medido en el eje y de la ubicación local de esta (ver Fig.11 y 12).

18

<!-- p. 20 -->

Fig.11 Propiedades de marco de puerta, sin cubierta

Fig.12 Propiedades de marco que cubre sólo parte de la apertura de muro

Fig.13 Propiedades de marco de puerta, con cubierta

19

<!-- p. 21 -->

Fig.14 Propiedades de umbral de puerta

Fig.15 Propiedades de travesaño

20

<!-- p. 22 -->

21

www.planbim.cl

m E -y
