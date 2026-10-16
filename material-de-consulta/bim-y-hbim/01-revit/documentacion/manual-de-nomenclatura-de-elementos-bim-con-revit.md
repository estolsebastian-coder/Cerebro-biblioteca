---
type: libro
title: "Manual de nomenclatura de elementos bim con REVIT"
author: ""
categoria: "BIM Y HBIM"
paginas: 50
extraccion: "texto (OCR pendiente)"
fuente: "local:E:/MATERIAL DE CONSULTA/BIM Y HBIM/01. Revit/DOCUMENTACIÓN/Manual de nomenclatura de elementos bim con REVIT.pdf"
convertido: 2026-10-16
---

# Manual de nomenclatura de elementos bim con REVIT

> Texto extraído de `BIM Y HBIM\01. Revit\DOCUMENTACIÓN\Manual de nomenclatura de elementos bim con REVIT.pdf` (50 páginas, texto (OCR pendiente)). El PDF original está en el disco E: (MATERIAL DE CONSULTA); `<!-- p. N -->` marca el inicio de cada página.

<!-- p. 1 -->

documento

20©Todos

<!-- p. 2 -->

ÍNDICE

Índice
Presentación y contenido
Objetivos
Leyenda
Procedimiento
Abreviaturas de materiales
Identificador abreviado o Marca de tipo.
Parámetros de dimensión.
Nomenclatura de algunas categorías de modelo
Aparatos sanitarios
Aparcamiento
Armazón estructural
Cimentación estructural
Cubiertas
Equipos especializados
Equipos mecánicos
Luminarias
Mobiliario
Muros
Niveles
Pilares estructurales
Puertas
Rociadores
Suelos
Terminales de aire
Ventanas
Nomenclatura de planos, vistas y documentos
Planos
Vistas
Documentos
Bibliografía

Manual de nomenclatura de elementos y documentos BIM 2

<!-- p. 3 -->

PRESENTACIÓN Y CONTENIDO

Buscando la mejor forma de trabajar es inevitable
llegar a la necesidad de homogeneizar los
elementos con los que trabajamos.
Partiendo de esta premisa, básica en nuestro
trabajo, llegamos en algún momento a la necesidad
de encontrar una codificación para los elementos
que los haga reconocibles en el equipo en el que
trabajamos y que nos permita nombrarlos siempre
de la misma manera, proyecto tras proyecto y aumentando el diccionario de elementos a
medida que se vayan incorporando en los nuevos trabajos, pero manteniendo los materiales y
elementos habituales con un sistema de nomenclatura claro y conocido por todos los
participantes.

En aras a este objetivo hemos trabajado durante años en algo en lo que creemos y que
queremos compartir.

No se trata de crear un estándar o un sistema de clasificación, sino de aportar un punto de
partida que permita, a aquel que quiera utilizarlo libremente, disponer de unos criterios y unos
elementos básicos que puedan convertirse en comunes en su trabajo y que pueda adaptar a
sus necesidades específicas.

Podrás encontrar en este manual una propuesta de:

• Listado de materiales y abreviaturas.
• Criterios de renombrado de tipos y familias por categorías.
• Criterios de nomenclatura de planos, vistas y numeración de espacios.
• Parámetros de renombrado propuestos.
• Valores predeterminados para los parámetros definidos.

Este manual puede complementarse además con la aplicación Nomenclator y Nomenclator For
Revit que tambien hemos desarrollado y que automatiza los procesos de renombrado (en Revit)
aunque es posible realizar los nombrados de elementos en Revit y otras plataformas de forma
manual aprovechando los criterios de renombrado aquí propuestos o modificados según las
necesidades o preferencias del usuario o incluso emplear dichos criterios en cualquier otro
software o herramienta de modelado.

Jose Manuel Zaragoza Angulo y José Miguel Morea Nuñez.
BIMLEARNING

Manual de nomenclatura de elementos y documentos BIM 3

<!-- p. 4 -->

OBJETIVOS

Los objetivos del uso de este manual son:

• Permitir la homogenización de nomenclaturas de elementos en las principales
categorías de objetos BIM.
• Establecer un criterio de partida en la nomenclatura de elementos que el usuario pueda
personalizar según sus necesidades.
• Dotar de las herramientas a las empresas, por ejemplo, a una constructora, que recibe
proyectos de distintos autores u orígenes, realizados con distintos criterios de
renombrado de elementos para, sin perder las denominaciones originales, adaptar
fácilmente dichas denominaciones a su propio estándar o protocolo de renombrado de
elementos.
• Permitir que, en una sucesión de proyectos distintos, se trabaje con los mismos
elementos y se nombren siempre de la misma manera, de forma que los agentes
participantes conozcan e interioricen los nombres de los elementos en su trabajo diario.

Este manual no trata de tener un código de nomenclaturas para todas las categorías de un
modelo BIM, sino de desarrollar un criterio en las categorías principales del modelo que nos
sirvan como base de partida para modificar, personalizar y hacer extensible al resto de
categorías del mismo por parte del usuario que lo quiera utilizar para este fin.

Manual de nomenclatura de elementos y documentos BIM 4

<!-- p. 5 -->

LEYENDA

PARÁMETRO DE SISTEMA 1
PARÁMETRO COMPARTIDO1
PARÁMETRO GLOBAL1

Operación realizada con Nomenclator Manager by BIMLEARNING.es (NM)2

Operación realizada con Nomenclator For Revit by BIMLEARNING.es (NFR)2

Operación realizada con TagLegends for Revit by BIMLEARNING.es (TGLg)2

Los códigos QR te llevarán a videos explicativos para poder automatizar el renombrado
de elementos si usas aplicaciones de BIMLEARNING.

Los enlaces te llevan a los videos anteriores directamente.

Parámetro de texto con valores predefinidos y abreviaturas de los
mismos.

Los parámetros de texto pueden tener valores predefinidos. En las
tablas verás una serie de valores y abreviaturas propuestas para los
parámetros utilizados en el renombrado de elementos.

1 Tipología de parámetros en Revit. Los usuarios de otras plataformas de modelado usarán
atributos o parámetros propios.
2 Soluciones de software para automatización de procesos mencionados, que pueden ser
usadas para conseguir los objetivos propuestos.
Manual de nomenclatura de elementos y documentos BIM 5

<!-- p. 6 -->

Proponemos un procedimiento de renombrado de elementos en el modelo
BIM, que nos permita identificarlos inequívocamente para el usuario delPROCEDIMIENTO modelo, que no siempre es el modelador.
La premisa básica para utilizar este manual será la concatenación de
parámetros o propiedades como elemento definitorio del elemento, a imagen de lo que ocurre
con nuestros propios nombres como personas, donde se sucede el enlace de distintas
propiedades o atributos del individuo para hacernos únicos en una base de datos.
En este contexto el nombre de una persona podríamos definirlo cómo:

Nombre de pila + Primer apellido paterno + Primer apellido materno

Habida cuenta de que puede haber diversos individuos con coincidencias en el nombre y que
eso puede enturbiar la integridad de una base de datos, podemos añadir otros parámetros.
Tradicionalmente, si bien no se ha usado de forma administrativa, conocíamos nuestros
siguientes apellidos:

Nombre de pila + Primer apellido paterno + Primer apellido materno + Segundo
apellido paterno + Segundo apellido materno.

Al margen de este ejemplo y de las particularidades geopolíticas donde el orden de los apellidos
paternos/maternos pueden invertirse o solo considerar uno de ellos, el concepto de
concatenación de valores de propiedades es el que utilizaremos en esta guía para establecer
un criterio de homogeneización en los nombres de los elementos.

Para ello utilizaremos unos criterios que planteamos como propuesta y que pretenden ser una
invitación a que el nombre de un elemento no sea elegido sin una reflexión previa, que además
aporte información objetiva de este y que se establezca el criterio con anticipación, de forma
que cualquier agente implicado en el proceso lo conozca y aplique para obtener idénticos
resultados a cualquier otro agente.

De tal forma, un elemento tendrá como nombre una sucesión de los valores de una serie de
parámetros separados por un carácter que llamaremos separador.

La composición del nombre será definida para cada categoría o clase de elementos en función
de aquellos parámetros que lo definan, por ejemplo, para su tipo o familia (en el caso de Revit)
y que suelen coincidir con los elementos que influyen en su precio o que hacen que pertenezca
a una u otra partida presupuestaria.

Por ejemplo, en la definición del nombre de una puerta intervendrán:
• La apertura de la puerta (abatible, corredera, etc.)
• El número de hojas (1 hoja, 2 hojas, 1 hoja + 1 fijo, etc.)
• El material principal de la puerta (madera, aluminio, etc.)
• Si lleva cerradura o no y su tipo
• La clasificación de incendios según normativa
• El ancho de la hoja (82,5 cm)
• El alto de la hoja (212 cm)
Y cualquier otro que el usuario decida o considere conveniente. Lo importante es definir de
manera previa una concatenación o sucesión de atributos que definan todas las puertas del
proyecto y que todos los agentes conozcan dicho protocolo de denominación.

Manual de nomenclatura de elementos y documentos BIM 6

<!-- p. 7 -->

Valores vacíos En esta situación puede suceder que uno de los valores no tenga relevancia o simplemente no
tenga un valor definido, como es el caso de no disponer de cerradura o de clasificación de
incendios concreta. En estos casos el valor se escribirá como “XX”.

Ahora bien, un valor de tipo texto como puede ser la apertura de la puerta puede ser
Valores predefinidos y
interpretable o definirse de forma distinta por varios de los usuarios que participen de forma
abreviaturas
que podríamos tener para una misma puerta estas dos denominaciones:

• Abatible/2Hojas/Madera/C2/XX/825x212
• ABAT/2Hojas/Wood/C2/XX/825x212

y aun diciendo lo mismo nos puede conducir a error en filtros de tablas, exportaciones y otros
usos de las bases de datos el hecho de que un mismo valor de un atributo (Apertura), se exprese
por distintos agentes de formas diferentes (Abatible y ABAT).
Por ello surge la necesidad de que los valores de algunos parámetros puedan tener unos
valores predefinidos que sean homogéneos y conocidos, independientemente del agente que
realice la tarea de incluir el valor en la base de datos o en el modelo y dado que los nombres
pueden resultar demasiado largos e incómodos, podemos establecer además unas
abreviaturas para estos valores que estén en un listado previamente definido.

De esta forma podríamos definir:

Apertura
Valores Abreviaturas
Abatible ABAT
Corredera CORR
Vaivén VAIV
Oscilobatiente OSC
Fijo FIJ
Seccional SECC
Guillotina GUIL

como los valores y abreviaturas a utilizar para el atributo apertura de puertas y ventanas de
forma que ningún tipo de puerta pueda ser denominado con una abreviatura distinta a las
mencionadas, salvo que en un proyecto concreto tengamos una apertura nueva, no
considerada en el listado en cuyo caso se ampliará el listado de valores posibles añadiendo el
valor y la abreviatura correspondiente que harán crecer nuestro estándar actualizándolo.
En este manual podrás ver los parámetros en cada categoría tratada y una recopilación o
compendio de los mismos al final de este.

Abreviaturas de materiales Cuando nos encontramos con atributos o parámetros que definen el material del elemento
precisamos tambien definir los nombres de los materiales de acuerdo a un listado previo y
llegamos tambien a la necesidad de utilizar abreviaturas para los mismos, algo que el mercado
comercial o incluso el enfoque normativo ya ha realizado en numerosas ocasiones 3 creando
listados de nombres y abreviaturas para los materiales.

3 Véase el caso del hormigón (H-25/P/20/IIa) o de las telas impermeabilizantes (LBM-40/G-FV)
Manual de nomenclatura de elementos y documentos BIM 7

<!-- p. 8 -->

En el caso de este manual se plantea un listado de materiales y abreviaturas que no pretende
ser el listado de referencia, sino un punto de partida que el usuario pueda adaptar, modificar,
ampliar o reducir a voluntad según sus necesidades y que le permita tener una referencia de
utilidad.
Para ello planteamos los materiales como el resultado de :
• Un material genérico que define la familia principal del material o el uso de este.
• Un material específico, que define el material inequívoco dentro de la familia principal
o material genérico.
Como ejemplo podemos utilizar el mármol de Carrara, donde:
• Material genérico= Mármol.
• Material específico= Carrara

Y dado que esto, de nuevo, podría generar nomenclaturas demasiado largas para usarlas
dentro de un nombre que incluye más parámetros, utilizamos abreviaturas para ambos valores
de modo que :
Mármol de Carrara = MAR.CRR

En el caso de los elementos que tengan un atributo de tipo material implicado en la definición
del nombre, como ya vimos en las puertas, proponemos el uso de esta abreviatura como valor
del parámetro, de modo que el nombre de puerta que vimos anteriormente según el criterio
definido sería:

Ejemplo Abatible/2Hojas/Madera/C2/XX/825x212
ABAT/2Hojas/Wood/C2/XX/825x212
ABAT/2H/MAD.RBL/C2/XX/825x212

Siendo la definición de un tipo de puerta abatible de una hoja de madera de roble con cerradura
a dos caras y sin clasificación de incendio, de ancho 82,5 cm y alto de hoja 2,12 cm.

En el caso de los elementos compuestos de capas, donde aparecen diferentes materiales se
plantea la separación de los parámetros entre capas con un símbolo diferente, que en este
manual será de aquí en adelante el símbolo de la suma o adición (+), de modo que un muro de
una capa de ladrillo hueco doble con un yeso por sus dos caras podría ser :

RVS.YSVR + LD.TOSC + RVS.YSVR

Y si añadimos los espesores de las capas para incluir si el muro es de uno o de medio pie de
aparejo, sería:

1.RVS.YSVR +12.LD.TOSC + 1.RVS.YSVR

Es decir, medio pie de ladrillo tosco para revestir con una capa de yeso vertical de un cm por
cada cara.
O añadiendo algunos identificadores más para la función del muro o su espesor total:

Ejemplo elemento por capas T3 / TAB /14cm / 1.RVS.YSVR +12.LD.TOSC + 1.RVS.YSVR

Donde un NO modelador puede entender rápidamente, si conoce los listados de abreviaturas y
valores de manera previa, que nos referimos al muro identificado como T3 para tabiquería

Manual de nomenclatura de elementos y documentos BIM 8

<!-- p. 9 -->

interior de espesor total de 14 cm con una capa de medio pie de ladrillo tosco revestido con
yeso vertical en ambas caras, lo que nos deja, de un vistazo, en disposición de saber en qué
partidas presupuestarias ha de incluirse para presupuestar o en qué actividades de la
planificación técnica ha de desagregarse para poder definir la planificación temporal de la obra.

Separadores Como separador es posible utilizar cualquiera de los símbolos que el usuario desee. En este
manual se utilizará siempre:
• Cómo separador de parámetros la barra inclinada: /
• Cómo separador de abreviaturas de material el punto: .
• Cómo separador de distintas capas de un elemento (muros, suelos, techos, etc.) el
signo más: +

Marcas de tipo o A lo largo de este manual comprobarás que en muchos de los elementos hemos optado por
identificador de iniciar el nombre del tipo con el identificador simplificado del mismo o Marca de tipo para los
instancia/ejemplar usuarios de Revit. Esto nos permite relacionarlo más fácilmente en memorias o etiquetados de
planos de replanteo. Si bien esta cuestión es opcional para el usuario, hemos considerado
conveniente apoyar esta idea con el desarrollo de una herramienta dentro de Nomenclator for
Revit que permite la escritura masiva y automatizada de las marcas de tipo de cualquier
categoría y que está integrada en la versión gratuita (Type Mark).

Otro autores o usuarios optan por la nota clave de Revit o incluso otro parámetro personalizado,
si bien nosotros hemos preferido dejar libre este parámetro singular de Revit para usos que
pueden ser requeridos por otras addin como los programas de extracción de mediciones.

En nuestro caso, recomendamos la inclusión como primer valor de la secuencia de un nombre
de tipo el valor de la Marca de tipo o identificador análogo de instancia o ejemplar, de forma
que por muy largo que pueda ser un nombre, sea perfectamente reconocible por sus primeros
caracteres.

Parámetros compuestos Existen algunos casos particulares donde un elemento es definido por su marca comercial y
modelo. Esto sucede con frecuencia con equipos mecánicos, luminarias y otros elementos
industrializados. En estos casos, además, es definitorio algún parámetro que puede tener
variaciones dentro del mismo modelo, tales como la potencia en vatios o el diámetro de un
elemento, por ejemplo una luminaria, un rociador, etc.
En estos casos puede utilizarse como norma general el uso del parámetro modelo, pero para
nuestro uso el modelo debería tener en su valor el tamaño, diámetro, color, material u otros
parámetros que puedan ser característicos.
Para ello podemos, a la hora de rellenar el valor de este atributo modelo, incluir en él dichos
parámetros o posteriormente combinar varios parámetros en este parámetro.
Si usas Nomenclator For Revit, puedes realizar esta tarea de forma automatizada con la utilidad
Combine Parameter, que permite unir varios parámetros en un parámetro de tipo texto, en este
caso el parámetro modelo.

Parámetros vacíos Existen casos donde un parámetro puede no tener un valor determinado, por ejemplo el
parámetro zona en planos o vistas donde existe una única zona. En estos casos se utilizará el
valor XX o simplemente no se considerará dicho valor en la composición de los nombres de
elementos del modelo.

Manual de nomenclatura de elementos y documentos BIM 9

<!-- p. 10 -->

Elementos no afectados No obstante, hay elementos en los modelos que pueden no responder a esta forma de
nombrarlos. Si pensamos en elementos cuya tipología no define un precio, sino que cada
instancia o ejemplar del elemento puede tener atributos que lo hagan pertenecer a otro conjunto
de elementos incluidos en una partida presupuestaria, nos daremos cuenta de que su nombre
de tipo no define el modo en que agruparlos, por lo que puede ser mucho más genérico.
Por ejemplo tuberías o conductos son elementos que se caracterizan de forma básica por su
diámetro que determina su uso o su precio aunque en Revit este atributo no es de tipo sino de
ejemplar, lo cual hace que no pueda usarse su diámetro en el nombrado del tipo.

Manual de nomenclatura de elementos y documentos BIM 10

<!-- p. 11 -->

Todo el contenido de este manual puede utilizarse para crear los
estándares de renombrado de una empresa u organización, sinSI UTILIZAS NOMENCLATOR
embargo puedes ahorrar tiempo y mejorar el rendimiento si
utilizas Nomenclator Manager, Nomenclator For Revit y BEP
Utilites, que conforman la solución NOMENCLATOR, para la
creación de estándares, automatización y comprobación de los
mismos.
,
Con la solución Nomenclator podrás: NOMENCLATOR

Crear plantillas de renombrado que te permitan aplicar desde DE Revit de forma automatizada los criterios definidos por el
VISTAS, coordinador o BIM Manager.
Gestionar los parámetros con valores predefinidos para
rellenar los valores de los mismos con valores correctos, así
como comprobar dispersiones o errores en los mismos.
Mapear los materiales de Revit para dotarlos de la abreviatura
correspondiente de tu listado de materiales a abreviaturas que
habrás definido previamente.
Renombrar tipos y familias de forma automatizada.
Renombrar muros, suelos, cubiertas y techos a partir de los
materiales que conforman sus capas de forma automatizada.
Crear tus protocolos BIM, definir el nivel LOIN de cada elemento, crear y mantener las
normas de modelado de tu organización, crear y mantener EIR, BEP y protocolos y/o
estándares de modelados BIM.

Además, Nomenclator For Revit incorpora herramientas accesorias gratuitas de gran utilidad
como:
From param to param, que permite pasar el valor de un parámetro a otro del mismo tipo
o cualquier parámetro de tipo texto de forma rápida y automatizada.
Type Mark para escribir el parámetro Marca de Tipo en Revit de forma masiva,
secuencial, para todos los elementos de una categoría o filtrando solo aquellos que
deseas.
Easy Write Parameter para escribir un parámetro de forma masiva en todos los tipos
que desees.
ID para “sacar a la luz” el valor del ID de cada ejemplar y tipo, que permitirá conocer
datos que no puedes ver en los elementos y usarlos en tablas.
Combine Parameters para unir varios parámetros de cualquier tipo en un parámetro de
tipo texto, que permita, por ejemplo, añadir al parámetro modelo de un elemento los
parámetros de material, tamaño, color u otros característicos que lo definen, o escribir
un parámetro en las habitaciones de un proyecto residencial que aune bloque o edificio,
portal, planta, letra y tipo de vivienda.

Manual de nomenclatura de elementos y documentos BIM 11

<!-- p. 12 -->

ABREVIATURAS DE MATERIALES

Se establece un Sistema de codificación de materiales mediante abreviaturas de modo que los
materiales utilizados se ordenan y clasifican según el siguiente sistema independientemente
del nombre que puedan tener en la aplicación de modelado:
• Material genérico. Abreviatura de Material genérico
o Material Específico 1 . Abreviatura de material específico 1 Link Link
o Material Específico 2 . Abreviatura de material específico 2
o Material Específico n . Abreviatura de material específico n

Steel, STL

Listado de abreviaturas de materiales propuesto

Mat genérico Abrevt Mat específico Abrevt

Aire AIR Aire AIR
Aislamientos AIS Espuma poliuretano PUR
Aislamientos AIS Lana de roca SW
Aislamientos AIS Lana mineral LNMR
Aislamientos AIS Poliestireno extruido XPS
Aislamientos AIS Poliestireno expandido EPS
Aislamientos AIS Lamina reflexiva LAMREFLX
Aislamientos AIS Lana de vidrio GW
AIS Espuma de polietileno POLRET Aislamientos
reticulado
Aluminio ALU Anodizado ANDZ
Aluminio ALU En su color NAT

Manual de nomenclatura de elementos y documentos BIM 12

<!-- p. 13 -->

Aluminio ALU Lacado LCD
Bloque BLQ Hormigón 15 HRG15
Bloque BLQ Hormigón 20 HRG20
Bronce BRN Natural NAT
Cauchos CAU Butadieno BDE
Cauchos CAU Butilo BUT
Cauchos CAU Celular CEL
Cauchos CAU Natural NAT
Cauchos CAU Etileno propileno dieno EPDM
monomero
Cauchos CAU Neopreno NEO
Cauchos CAU Polisobutileno PIB
Cauchos CAU Polilsulfuro PSU
Cerámica CER Esmaltada ESM
Cerámica CER Extrusionado EXTR
Cerámica CER Porcelanato PORC
Cerámica CER Esmaltada 60x30 ESM60x30
Cerámica CER Esmaltada 30x40 ESM30x40
Cerámica CER Vitrificada 20x20 VIT20x20
Cerámica CER Vitrificada 20x30 VIT20x30
Chapa CHP Chapa galvanizada GLVZ
Chapa CHP Chapa lacada LCD
Chapa CHP Chapa perforada PERF
Chapa CHP Chapa zincada ZNCV
Chapa CHP Grecada GRCD
Chapa CHP Ondulada microperforada ONDMICRO
Corcho COR Comprimido COMP
Corcho COR Expandido con resinas EXRS
COR Expandido EXPCorcho

ESCY Placas escayola lisa LISEscayola

ESCY Ladrillos de escayola LADREscayola

Formación de FPDTS Arcilla expandida ARL
pendientes
Formación de FPDTS Hormigón ligero con arcilla HARL
pendientes expandida
Formación de FPDTS Hormigón celular con HAIR
pendientes aireante
Formación de FPDTS Tablero cerámico TABCR
pendientes
Formación de FPDTS Panel sancwidch SANDW
pendientes
Formación de FPDTS Tablero de hormigón TABHR
pendientes

Manual de nomenclatura de elementos y documentos BIM 13

<!-- p. 14 -->

Formación de FPDTS Onduline ONDL
pendientes
Formación de FPDTS Tablero de madera TABMAD
pendientes
FRJ Bovedilla cerámica canto CER25+5Forjados
25
Forjados FRJ Bovedilla cerámica canto CER26+5
26
FRJ Bovedilla cerámica canto CER30+5Forjados
30
FRJ Bovedilla hormigón canto HR25+5Forjados
25
FRJ Bovedilla hormigón canto HR3+5Forjados
30
FRJ Bovedilla hormigón ligero HL25+5Forjados
25
Forjados FRJ Bovedilla hormigón ligero HL30+5
30
Grava GRV Rodada Lavada tam máx 40 LVD40
Grava GRV Rodada Lavada tam máx 80 LVD80
GRV Gravilla machaqueo negra MCHNEGGrava
jardinería
Grava GRV Árido reciclado RECICL
Gres GRES Calcáreo CAL
Gres GRES Cuarzoso CUA
Gres GRES Sílice SIL
Hormigón armado HA HA-25/P/20/IIa 25/P/20/IIA
Hormigón armado HA HA-25/P/20/IIb 25/P/20/IIB
Hormigón armado HA HA-30/P/20/IIa 30/P/20/IIA
Hormigón armado HA HA-30/P/20/IIb 30/P/20/IIB
Hormigón armado HA HA-35/P/20/IIb 35/P/20/IIB
Hormigón en masa HM HM-25/P/20/IIa 25/P/20/IIA
Hormigón en masa HM HM-25/P/20/IIB 25/P/20/IIB
Hormigón en masa HM Hormigón gunitado GUN
Hormigón HP Blanco BLC
prefabricado
Impermeabilizaciones IMP Caucho CAU
Impermeabilizaciones IMP Clorocaucho CLCAU
Impermeabilizaciones IMP Betún BET

Impermeabilizaciones IMP Lamina oxiasfalto 3 Kg/m2 OXASF3
Impermeabilizaciones IMP Lamina oxiasfalto 4 Kg/m2 OXASF4
IMP Betún modificado con SBS3Impermeabilizaciones
elastómero SBS 3 Kg/m2
IMP Betún modificado con SBS4Impermeabilizaciones
elastómero SBS 4 Kg/m2
IMP Betún modificado con APP3Impermeabilizaciones
plastómero SBS 3 Kg/m2

Manual de nomenclatura de elementos y documentos BIM 14

<!-- p. 15 -->

IMP Betún modificado con APP4Impermeabilizaciones
plastómero SBS 4 Kg/m2
IMP Mortero flexible MORTBIImpermeabilizaciones
bicomponente
Impermeabilizaciones IMP Lamina EPDM EPDM
Impermeabilizaciones IMP Masilla bituminosa MASBIT
IMP Revestimiento acrílico con ACRImpermeabilizaciones
fibra vidrio
Ladrillo LD Blanco BLN
LD Hormigón prefabricado PREFLadrillo
300
Ladrillo LD Hueco doble tabicón LHDT
Ladrillo LD Hueco doble LHD
Ladrillo LD Hueco sencillo LHS
Ladrillo LD Macizo Perforado MAZ
Ladrillo LD Macizo tosco para revestir TOSC
Ladrillo LD Termoarcilla 19 TRM
Ladrillo LD Visto VIST
Ladrillo LD Visto esmaltado blanco VISTESBL
Ladrillo LD Vitrificado visto azul VISTVITRAZ
Ladrillo LD Ladrillo cara vista CV
Ladrillo LD Ladrillo cara vista negro CVN
Madera MAD Pino Melis MELS
Madera MAD Pino segovia SEG
Madera MAD Roble RBL
Madera MAD Sapelly SPLY
Mármol MAR Blanco Macael MAC
Mármol MAR Blanco yugoslavo YGL
Mármol MAR Carrara CRR
Mármol MAR Crema marfil MARF
Mármol MAR RosaPorriño PRÑ
Metal MTL Estructura ACR
Mortero MOR Cemento CEM
Mortero MOR Cemento aligerado CEMLIG
Pantalla PANT Pantalla pilotes PILO
Pavés PAVS Traslucido TRSL
Pavimentos PAV Terrazo TRZ
Pavimentos PAV Terrazo continuo TRZC
Pavimentos PAV Laminado madera 25x120 LAM25X120
Pavimentos PAV Laminado madera 25x140 LAM25X140
Pavimentos PAV Laminado madera 35x150 LAM35X150
Pavimentos PAV Baldosas vinílicas BVINIL
Pavimentos PAV Baldosas linoleum BLINO
Pavimentos PAV Vinilo en rollo VIN
Pavimentos PAV Linoleum en rollo LIN

Manual de nomenclatura de elementos y documentos BIM 15

<!-- p. 16 -->

Pavimentos PAV Continuo industrial CINDUS
Pavimentos PAV Baldosa hidráulica BHIDR
Pavimentos PAV Moqueta en rollo MOQ
Pavimentos PAV Moqueta en baldosas BMOQ
Pavimentos PAV Microcemento MICRC
Pavimentos PAV Hormigón impreso HIMPR
Pavimentos PAV Hormigón lavado HLAVD
Pavimentos PAV Asfalto en caliente ASF
Piedra PDR Arenisca ARNS
Piedra PDR Artificial ARTF
Piedra PDR Caliza CALZ
Piedra PDR Silicocalcárea SLCA
Piedra PDR Pizarra PIZ
Piedra PDR Granito Gris GRNGR
Piedra PDR Granito rosa porriño GRNPRÑ
Pintura PINT Plástica PLST
Pintura PINT Temple TMPL
Placa de yeso PLD Lisa LS
laminado
Placa de yeso PLD Verde VRD
laminado
antihumedad
Placa de yeso PLD Rosa FOC
laminado incendios
Poliestireno PS Expandido EXP
Poliestireno PS Extruido EXTR
Policloruro de vinilo PVC Blanco BLC
Revestimientos RVS Cal CAL
Revestimientos RVS Monocapa china MONCH
Revestimientos RVS Monocapa liso MONLS
Revestimientos RVS Mortero cemento MORT_CEMT
Revestimientos RVS Yesos horizontales YSHZ
Revestimientos RVS Yesos verticales YSVR
Revestimientos RVS Yeso YES
Steel STL Galvanized GLVZ
Steel STL Stainless INOX
Steel STL Zinc-coated ZNC
Teja TEJ Cerámica mixta CERMIX
Teja TEJ Hormigón HOR
Teja TEJ Cerámica curva CER
Teja TEJ Asfáltica ASF
Teja TEJ Cerámica curva recuperada CERREC
Vidrio VID 3+3/6/6 3+3/6/6
Vidrio VID 4/6/4 4/6/4

Manual de nomenclatura de elementos y documentos BIM 16

<!-- p. 17 -->

IDENTIFICADOR ABREVIADO O MARCA DE TIPO /TYPE MARK

Vidrio VID 4/6/ Bajo emisivo 4 4/6/BE4
Vidrio VID 4/6/ Bajo emisivo 8 4/6/BE8
Vidrio VID 4/6/ Bajo emisivo 10 4/6/BE10
Vidrio VID 4/6/ Bajo emisivo 12 4/6/BE12
Vidrio VID Espejo ESPJ
Vidrio VID Luna LUN

Con frecuencia deberemos sustituir el nombre de tipo, que puede ser muy extenso, por un
identificador abreviado o utilizar una abreviatura que permita ordenar, clasificar e identificar
cada tipo de un elemento con un conjunto reducido de caracteres, por ejemplo, identificar un
tipo de ventana como V7 que nos permita a la vez saber que es una ventana (alusión a la
categoría del objeto) e identificar a qué ventana de entre las numerosas tipologías existentes
en cada proyecto estamos aludiendo.
Por ello se hace necesario utilizar (por ejemplo, en un plano de ubicación de carpinterías o
tabiquerías) estas abreviaturas o identificadores de tipo (en Revit el atributo Marca de tipo).
A tal efecto proponemos que se utilicen de manera común identificadores que se repitan en
cada proyecto, dando una abreviatura a cada categoría, seguida del número de orden que
podrá cambiar de un proyecto a otro, pero manteniendo la uniformidad del criterio en todos
ellos.

Categoría Abreviatura Marca de tipo
Accesorios de conductos ACC
Accesorios de tuberías ACCTB
Aparatos eléctricos ELC
Aparatos sanitarios SAN
Aparcamiento PARK
Armazón estructural VIG
Balaustres BA
Bandejas de cables B
Barandillas BR
Barridos de muro BAR
Cables CAB
Canalones CAN
Cimentación estructural ZAP
Conductos CND
Conductos flexibles CNDF
Cubiertas C

Manual de nomenclatura de elementos y documentos BIM 17

<!-- p. 18 -->

Entorno E
Equipos eléctricos EQELC
Equipos especializados EQ
Equipos mecánicos MEC
Escaleras ESC
Luminarias LU
Muros M
Mobiliario MB
Pilares estructurales PI
Puertas P
Rampas RA
Rociadores R
Suelos S
Techos TE
Terminales de aire TA
Timbres de enfermería TI
Tuberías TB
Tuberías flexibles TBF
Tubos TB
Uniones de bandeja de cables UB
Uniones de conducto UC
Uniones de tubería UTB
Uniones de tubo UTU
Vegetación VG
Ventanas V
Vigas de celosía estructurales VI
Topografía TO

Los usuarios de Nomenclator For Revit disponen de la utilidad TypeMark para el rellenado
rápido de todas las marcas de tipo de cualquier categoría, estableciendo para el usuario las
abreviaturas que decida para cada una de manera independiente.

PARÁMETROS DE DIMENSION

Existen la posibilidad de que distintos objetos utilicen distintos parámetros para establecer sus
dimensiones, bien porque no exista una homogeneidad de criterios previos a la hora de
establecer en qué parámetros se definirán, por ejemplo, sus tres magnitudes principales (ancho,
largo y alto) o bien porque la procedencia de las diferentes familias de objetos sea distinta,
incluso creadas en otros idiomas (habitual en las descargas de objetos de internet o de
fabricante) o incluso aún peor, que la dimensión establecida en los objetos no sea la que
buscamos, por ejemplo en una puerta bajada de internet con un ancho distinto al hueco libre de
paso de la misma.
Como medida para la homogeneización de las dimensiones y la parametrización de acuerdo
con un protocolo, se recomienda establecer tres parámetros de usuario que establezcan las
tres dimensiones del espacio, ancho, largo y alto y hacer que cada familia usada en el proyecto
tenga, independientemente de la procedencia, autor o criterios de creación de la misma,
mapeados a estos tres parámetros sus dimensiones, de modo que cualquier usuario de
nuestros proyectos, conocedor de los criterios tomados en estas magnitudes, tenga la garantía

Manual de nomenclatura de elementos y documentos BIM 18

<!-- p. 19 -->

de que los parámetros tengan siempre el mismo significado (el ancho de paso de una puerta o
el largo máximo de un elemento de mobiliario, por ejemplo).
Así, proponemos el uso de estos parámetros:

LARGO
ANCHO
ALTO
que tendrán que añadirse a todas las familias u objetos que los usen e igualar el valor de
aquellos parámetros homólogos de magnitud de modo que estos atributos reflejen el mismo
valor que los utilizados en cada familia.

Manual de nomenclatura de elementos y documentos BIM 19

<!-- p. 20 -->

APARATOS SANITARIOS/PLUMBING FIXTURES

• COMPOSICIÓN NOMBRE DEL TIPO

Marca de tipo / Tipo de sanitario / Fabricante / Modelo / Ancho x Alto
Link

• EJEMPLO

Link SAN3/LAVB/KROCA/MERIVIAN/ 50x70

• SIGNIFICADO

Marca de tipo o identificador: SAN3
Tipo de sanitario: Lavabo(LAVB)
Fabricante : KROCA
Modelo : Merivian
Ancho: 50 cm
Alto: 70 cm

Tipo de sanitario Valores Abreviaturas
Lavabo LAVB
Inodoro INOD
Ducha DUCH
Bañera BAÑR
Vertedero VERT
Fregadero FREG
Jacuzzi JCZZ
Urinario URIN
Fuente FUEN

Manual de nomenclatura de elementos y documentos BIM 20

<!-- p. 21 -->

APARCAMIENTO /PARKING

• COMPOSICIÓN NOMBRE DEL TIPO

Marca de tipo/Tipo de plaza / Largo x Ancho
Link

• EJEMPLO

Link
PARK4/NOR/240x450

• SIGNIFICADO

Marca de tipo o identificador: PARK4
Tipo de plaza: Normal (NOR)
Largo : 50 cm
Ancho: 70 cm

Tipo de plaza Valores Abreviaturas
(aparcamiento) Normal NORM
Discapacitado DISC

Manual de nomenclatura de elementos y documentos BIM 21

<!-- p. 22 -->

ARMAZÓN ESTRUCTURAL (Hormigón) / Structural Framing (Concrete)

• COMPOSICIÓN NOMBRE DEL TIPO

Marca de tipo/Material / Ancho x Alto
Link

• EJEMPLO

Link V8/HA-25/P/20/I/60x30

• SIGNIFICADO

Marca de tipo o identificador: V8
Material: Hormigón Armado HA-25/P/20/I
Ancho : 60 cm
Alto : 30 cm

Manual de nomenclatura de elementos y documentos BIM 22

<!-- p. 23 -->

CIMENTACION ESTRUCTURAL / STRUCTURAL FOUNDATIONS (aislada)

• COMPOSICIÓN NOMBRE DEL TIPO

Marca de tipo/Material /Largo x Ancho x Alto
Link

• EJEMPLO

Link Z6/HA-25/P/40/IIa/100x90x65

• SIGNIFICADO

Marca de tipo o identificador: Z6
Material: Hormigón Armado HA-25/P/40/IIa
Largo : 100 cm
Ancho : 90 cm
Alto : 65 cm

Manual de nomenclatura de elementos y documentos BIM 23

<!-- p. 24 -->

CUBIERTAS/ROOFS

• COMPOSICIÓN NOMBRE DEL TIPO

Marca de tipo / Clase de Cubierta / EspesorCapa1.MaterialCapa1
\+ EspesorCapa2.MaterialCapa2 + EspesorCapaN.MaterialCapaN
Link

• EJEMPLO

C6/NOTRAN/7.GRV.LVD40+0,5.IMP.GEO80+8.AIS.XPS+
Link (2)1.IMP.SBS4+0,5.IMP.IMPRASF+
3.MOR.CEM+15.FPDTS.HAIR

• SIGNIFICADO

Marca de tipo o identificador: C6
Clase de cubierta: No Transitable
Capa I : 7 cm grava lavada tamaño máx 40 mm.
Capa II: 0,5 cm Lámina geotextil 80 gr/m2.
Capa III : 7 cm Aislamiento térmico Poliestireno extruido XPS
Capa IV: 2 capas de impermeabilización de betún modificado con
elastómero SBS de 4 Kg/m2

Manual de nomenclatura de elementos y documentos BIM 24

<!-- p. 25 -->

Capa V: Imprimación asfáltica.
Capa VI: 3 cm Mortero de cemento.
Capa VII: Formación de pendientes con 15 cm de hormigón celular
con aireantes.

DetalledememoriarealizadaconTagLegends1 byBIMLEARNING

Clase de cubierta Valores Abreviaturas
Bóveda BOVD
Inclinada INCL
No transitable plana NOTRAN
Transitable plana TRAN

Manual de nomenclatura de elementos y documentos BIM 25

<!-- p. 26 -->

EQUIPOS ESPECIALIZADOS

• COMPOSICIÓN NOMBRE DEL TIPO

Marca de tipo / Tipo de equipo / Fabricante / Modelo / Potencia o
Link
Voltaje4

• EJEMPLO

Link EQ7/VENT/ADLER/LUXE/10w

• SIGNIFICADO

Marca de tipo o identificador: EQ7
Tipo de aparato: Ventilador
Fabricante : Adler
Modelo : Luxe10
Potencia: 10w

Tipo de equipo 5
Valores Abreviaturas
Ventilador VENT
Sirena emergencia SIRN
Desfribilador de pared DESF

4 Parámetro opcional, puede haber elementos que no lo necesiten, por ejemplo detectores.
5 Solo se incluyen unos valores a título enunciativo y de ejemplo. El usuario deberá crear su
propia lista de tipos de equipos y las correspondientes abreviaturas.
Manual de nomenclatura de elementos y documentos BIM 26

<!-- p. 27 -->

EQUIPOS MECANICOS

• COMPOSICIÓN NOMBRE DEL TIPO

Marca de tipo /Tipo de equipo / Fabricante / Modelo / Potencia o
Link
voltaje6

• EJEMPLO

Link EM10/ENF/MORRIS/FREECOOL1000/2500W

• SIGNIFICADO

Marca de tipo o identificador: EM10
Tipo de aparato: Enfriadora
Fabricante : Morris
Modelo : FREECOOL 1000
Potencia: 2500w

Tipo de equipo 7
Valores Abreviaturas
Enfriadora ENF
Fancoil FANC
Compuerta COMP

6 Parámetro opcional, puede haber elementos que no lo necesiten, por ejemplo detectores.
7 Solo se incluyen unos valores a título enunciativo y de ejemplo. El usuario deberá crear su
propia lista de tipos de equipos y las correspondientes abreviaturas.
Manual de nomenclatura de elementos y documentos BIM 27

<!-- p. 28 -->

LUMINARIAS

• COMPOSICIÓN NOMBRE DEL TIPO

Marca de tipo / Tipo de luminaria / Fabricante / Modelo /Potencia
Link

• EJEMPLO

LU5/DOWL/PHILIPS/ALU20/28W

Link

• SIGNIFICADO

Marca de tipo o identificador: LU5
Tipo de luminaria: Downlight(DOWL)
Fabricante : PHILIPS
Modelo : Aluminio 20 cm8
Potencia: 28w

9
Valores Abreviaturas
Tipo de aparato Carril luminaria CARR
Downlight DOWL
Farola FARL
Lámpara colgada COLG
Lámpara de pared PARD
Lineal LIN
Proyector PROT
Tira de leds LEDLIN

8 En los elementos con modelo comercial definido puede integrarse el material, el diámetro, el
tamaño, el color u otro parámetro dentro del valor del modelo usando la utilidad Combine
Parameters de Nomenclator For Revit.

9 Solo se incluyen unos valores a título enunciativo y de ejemplo. El usuario deberá crear su
propia lista de tipos de equipos y las correspondientes abreviaturas.

Manual de nomenclatura de elementos y documentos BIM 28

<!-- p. 29 -->

MOBILIARIO

• COMPOSICIÓN NOMBRE DEL TIPO

Marca de tipo / Tipo de mueble / Fabricante / Modelo /Ancho x Largo
Link

• EJEMPLO

Link MB4/SOF/IKEA/KAHLÜG/1280x950

• SIGNIFICADO

Marca de tipo o identificador: MB4
Tipo de mueble: Sofá
Fabricante : Ikea
Modelo : Kahlüg
Ancho: 1280 mm
Largo : 950 mm

10
Tipo de mueble Valores Abreviaturas
Alacena ALAC
Cama CAM
Estantería ESTN
Mesa MES
Silla SILL
Sillón SILN
Sofá SOF

10 Solo se incluyen unos valores a título enunciativo y de ejemplo. El usuario deberá crear su
propia lista de tipos de equipos y las correspondientes abreviaturas.
Manual de nomenclatura de elementos y documentos BIM 29

<!-- p. 30 -->

MUROS/WALLS

• COMPOSICIÓN NOMBRE DEL TIPO

Marca de tipo / Clase de Muro / Grosor /
EspesorCapa1.MaterialCapa1 + EspesorCapa2.MaterialCapa2 +
Link
EspesorCapaN.MaterialCapaN

• EJEMPLO

M1/FCH/19cm/11.LD.MAZ+1.MOR. CEM+7.AIS.LNMR
Link

• SIGNIFICADO

Marca de tipo o identificador: M1
Clase de muro: Fachada
Grosor total: 19 cm.
Capa I : 11cm Ladrillo macizo.
Capa II: 1cm Mortero cemento.
Capa III : 7 cm Aislamiento térmico Lana mineral

Manual de nomenclatura de elementos y documentos BIM 30

<!-- p. 31 -->

Clase de muro Valores Abreviaturas
Fachada FCH
Trasdosado TRS
Urbanización exterior URB
Peto de cubierta PET
Tabiquería interior TAB

Manual de nomenclatura de elementos y documentos BIM 31

<!-- p. 32 -->

NIVELES / LEVELS

Pisos:

Los pisos se numeran utilizando un estándar de 2 dígitos que comienza con '01' para la primera
planta y continúan hacia arriba para cada piso siguiente (por ejemplo, 02-segundo piso, 03-
tercer piso
01,02,03,…n

Nivel de entrada

La planta de entrada, se denominará PB.
PB

Sótanos:

Los pisos situados debajo de la planta baja se designarán como sótano, designándose como
S1 al primer sótano, S2 al segundo sótano, etc.
De más alto a más profundo: S1,S2,S3,…Sn

Entreplantas:

A las entreplantas se les asigna un valor de código de planta de dos caracteres de EP.
utilizando una EP anterior seguida del número del piso de abajo (por ejemplo, "EP2" donde '2'
es el piso de abajo).
EPB, EP1, EP2,…EPn
Cubierta:

El último nivel, donde se apoye la cubierta más alta, a partir de la cual ya no se generan volumen,
ni habitaciones, se denominará "C", y se utilizará como referencia para medir salidas de
ventilaciones y chimeneas.

C

Manual de nomenclatura de elementos y documentos BIM 32

<!-- p. 33 -->

PILARES ESTRUCTURALES (Hormigón) / Structural Columns (Concrete)

• COMPOSICIÓN NOMBRE DEL TIPO

Marca de tipo/Material / Largo x Ancho
Link

• EJEMPLO

Link
Pi4/HA-25/P/20/I/45x50

• SIGNIFICADO

Marca de tipo o identificador: Pi8
Material: Hormigón Armado HA-25/P/20/I
Largo : 45 cm
Ancho : 50 cm

Manual de nomenclatura de elementos y documentos BIM 33

<!-- p. 34 -->

PUERTAS/DOORS

• COMPOSICIÓN NOMBRE DEL TIPO

Marca de tipo / Apertura / Número de Hojas / Material / Cerradura /
Link
Clasificación de incendios / Ancho x Alto

• EJEMPLO

Link P4/ABAT/1H /MAD.CSTÑ / C2 / EI-90 /72x212

• SIGNIFICADO

Marca de tipo o identificador: P4
Apertura: ABATIBLE (ABAT)
Número de hojas: 1 Hojas (1H)
Material: Madera de castaño (MAD.CSTÑ)
Cerradura: 2 caras (C2)
Clasificación incendios = EI-90 según CTE-DB-SI
Ancho: 72,5 cm
Alto: 212 cm

Manual de nomenclatura de elementos y documentos BIM 34

<!-- p. 35 -->

MemoriarealizadaconTagLegends3byBIMLEARNING

Apertura (puertas y Valores Abreviaturas
ventanas) Abatible ABAT
Corredera CORR
Vaivén VAIV
Oscilobatiente OSC
Fijo FIJ
Seccional SECC
Guillotina GUIL

Número de hojas Valores Abreviaturas
(puertas y ventanas) 1 Hoja 1H
1Hoja+1Fijo Lateral 1H+1FjLt
2 Hojas 2H
2Hojas+1Fijo inferior 2H+1FjInf
2Hojas+1Fijo Superior 2H+1FjSup

Cerradura (puertas y Valores Abreviaturas
ventanas) 1 Cara C1
2 Caras C2

Manual de nomenclatura de elementos y documentos BIM 35

<!-- p. 36 -->

Persiana Valores Abreviaturas
No tiene persiana PER_NO
Persiana perfiles mini PER_MIN
Persiana perfiles PER_INY
inyectados

Manual de nomenclatura de elementos y documentos BIM 36

<!-- p. 37 -->

ROCIADORES

• COMPOSICIÓN NOMBRE DEL TIPO

Marca de tipo /Fabricante/Modelo/Diámetro
Link

• EJEMPLO

Link RC8/SCHOOF/RAPIDWATER100/100

• SIGNIFICADO

Marca de tipo o identificador: RC8
Fabricante : SCHOOF
Modelo : RAPIDWATER 100
Diámetro: 100 MM

Manual de nomenclatura de elementos y documentos BIM 37

<!-- p. 38 -->

SUELOS/FLOORS

• COMPOSICIÓN NOMBRE DEL TIPO

Marca de tipo / Clase de suelo / Grosor /

Link EspesorCapa1.MaterialCapa1 + EspesorCapa2.MaterialCapa2
\+….+ EspesorCapaN.MaterialCapaN

• EJEMPLO

Link
S1/INT/10cm/8.MOR.CEM+8.PAV.LAM25x120

• SIGNIFICADO

Marca de tipo o identificador: S1
Clase de suelo : Acabado interior
Grosor total: 10 cm.
Capa I : 8cm Mortero de cemento.
Capa II: 2cm Pavimento laminado madera 25x120

Clase de suelo Valores Abreviaturas
Estructura STR
Acabado interior INT
Acabado exterior EXT

Manual de nomenclatura de elementos y documentos BIM 38

<!-- p. 39 -->

TERMINALES DE AIRE

• COMPOSICIÓN NOMBRE DEL TIPO

Marca de tipo /Tipo de Terminal de aire /
Link
Fabricante/Modelo/Ancho/Largo

• EJEMPLO

Link TA8/RJFJ/ ALG/K27/150x300

• SIGNIFICADO

Marca de tipo o identificador: TA8
Tipo de terminal de aire : Rejilla Fija (RJFJ)
Fabricante : ALG
Modelo : K27
Ancho: 150 mm
Largo: 300 mm

11
Tipo de terminal de Valores Abreviaturas
aire Cortina de aire CORTAI
Difusor circular DIF
Difusor lineal DIFLIN
Rejilla Fija RJFJ
Rejilla orientable RJOR

11 Solo se incluyen unos valores a título enunciativo y de ejemplo. El usuario deberá crear su
propia lista de tipos de equipos y las correspondientes abreviaturas.
Manual de nomenclatura de elementos y documentos BIM 39

<!-- p. 40 -->

VENTANAS/WINDOWS

• COMPOSICIÓN NOMBRE DEL TIPO

Marca de tipo / Apertura / Número de Hojas / Material / Persiana /
Link
Ancho x Alto

• EJEMPLO

Link V3/OSC/2H /ALU.LCD / Sí / 200x200

• SIGNIFICADO

Marca de tipo o identificador: V3
Apertura: OSCILOBATIENTE (OSC)
Número de hojas: 2 Hojas (2H)
Material: Aluminio lacado (ALU.LCD)
Persiana : Sí
Ancho: 200 cm
Alto: 200 cm

Manual de nomenclatura de elementos y documentos BIM 40

<!-- p. 41 -->

MemoriarealizadaconTagLegends4byBIMLEARNING

Apertura (puertas y Valores Abreviaturas
ventanas) Abatible ABAT
Corredera CORR
Vaivén VAIV
Oscilobatiente OSC
Fijo FIJ
Seccional SECC
Guillotina GUIL

Número de hojas Valores Abreviaturas
(puertas y ventanas) 1 Hoja 1H
1Hoja+1Fijo Lateral 1H+1FjLt
2 Hojas 2H
2Hojas+1Fijo inferior 2H+1FjInf
2Hojas+1Fijo Superior 2H+1FjSup

Manual de nomenclatura de elementos y documentos BIM 41

<!-- p. 42 -->

Cerradura (puertas y Valores Abreviaturas
ventanas) 1 Cara C1
2 Caras C2

Persiana Valores Abreviaturas
No tiene persiana PER_NO
Persiana perfiles mini PER_MIN
Persiana perfiles PER_INY
inyectados

Manual de nomenclatura de elementos y documentos BIM 42

<!-- p. 43 -->

PLANOS/SHEETS

• COMPOSICIÓN NOMBRE DEL PLANO 12

Link Project_Code_ISO / Originator / Volume or system / Level /
Discipline / Numero de plano / Description / Status / Revision actual

• EJEMPLO

Link
PR202001/BL/Z1/P1/A/A101/Distribución y cotas/S0/V1

• SIGNIFICADO

Project_Code_ISO : Código alfanumérico del proyecto. En el ejemplo el proyecto
identificado con el código PR202001
Originator: Código o abreviaturas del autor del plano. En el ejemplo BL es
BIMLEARNNG.
Volume or system: Zona, edificio, portal o identificador de la parte geográfica del proyecto. Si
no procede se coloca XX. En el ejemplo Z1 es zona 1.
Level: Nivel o planta. En el ejemplo P1 es planta primera.
Discipline: Disciplina (parámetro con valores predefinidos). En el ejemplo A es Arquitectura
Numero de plano: Código alfanumérico de orden del plano.
Description: Texto con la descripción del contenido del plano.En el ejemplo: Distribución y
cotas.
Status: Situación o estado.Parámetros con valores predefinidos. S0 Por ejemplo es Work in
progress
Revision actual: Revisión o edición del plano. En el ejemplo V1 versión 1

12 Basado en la norma BS 1192:2007+ a1:2015 Collaborative production of architectural,
engineering and construction information. Code of practice.
Manual de nomenclatura de elementos y documentos BIM 43

<!-- p. 44 -->

Parámetro añadido automáticamente con Nomenclator13
Status (planos) Valores Abreviaturas
Estado inicial de la información S0
generada antes de revisar por el
coordinador. WIP para aprobar.
Adecuado para coordinación en WIP S1
general aprobado para coordinación
pero no compartido con otros
agentes.
Compartido con otros. Apto para S3
revisión y comentario externo
Compartido con otros. Apto para S5
fabricación
Compartido con otros. Apto para S6
autorización PIM (proyecto de
ejecución)
Compartido con otros. Apto para S7
autorización AIM
Publicado. Apto para licitación o D2
solicitud de precio
Publicado. Apto para contratación, D4
fabricación, adquisición de equipos,
encargo de manufacturación,
prefabricados o petición de licencia.
Archivado. Información para el AIM o CR
“As Built”

Opción extendida.
Opción reducida.

Proponemos el uso en proyectos que no lo requieran más división de status, únicamente de los
valores de la opción reducida.

13 Collaborative production of architectural, engineering and construction information – Code of practice
BS 1192:2007+A1:2015 Table 5 Standard codes for suitability models and documents

Manual de nomenclatura de elementos y documentos BIM 44

<!-- p. 45 -->

VISTAS/VIEWS

• COMPOSICIÓN NOMBRE DE VISTA DE PLANTA 14

Link Disciplina (3)15 /Subdisciplina (3)/ Edificio / Zona / Nivel asociado
/Tipo vista16

• EJEMPLO

Link
ARQ/MOB/Edif A/Zona III/Nivel 1/Pta distribución

• SIGNIFICADO

Disciplina : Disciplina de la vista abreviada a los tres primeros caracteres.
Subdisciplina : Subdisciplina abreviada a los tres primeros caracteres.
Edificio: Edificio o volumen. Si no procede XX (algunos autores usan ZZ). En el ejemplo Edificio
A.
Zona: Zona o sector. Si no procede XX (algunos autores usan ZZ). En en ejemplo Zona III.
Nivel asociado: Nivel 1
Tipo vista: Planta de distribución (se usan los tipos de vista de Revit).

Puede utilizarse el mismo sistema en alzados o secciones.

14 Basado en la norma BS 1192:2007+ a1:2015 Collaborative production of architectural,
engineering and construction information. Code of practice.
15 Abreviado a los tres primeros caracteres.
16 En vistas de detalle, imágenes, etc, se sustituye el tipo de vista por descripción.
Manual de nomenclatura de elementos y documentos BIM 45

<!-- p. 46 -->

DOCUMENTOS/DOCS

Propuesta de concatenación de atributos en el nombre de los documentos de un proceso BIM.

• COMPOSICIÓN NOMBRE DE DOCUMENTO (ISO-19650)

Project_Code_ISO /Originator/ Volume or system / Level / Discipline
Link / Type Document / Descripción / Status / Version

• EJEMPLO

PR2001/BL/Z1/XX/A/PR/PRESUPUESTO EJECUCIÓN
MATERIAL/S0/V.B1

• SIGNIFICADO

Project Code ISO: Código alfanumérico del proyecto. Se trata de un atributo interno de la
organización originadora del proyecto.
Enel ejemplo, el proyecto identificado con el código PR2001. Cada usuario
determinará la composición de sus propios códigos de proyectos. En este caso:
Prefijo (PR) Año (20) Número de Orden (01).

Originator:: Código o abreviaturas del autor del documento o equipo de desarrollo (ISO-
19650). En el ejemplo BL es BIMLEARNING.

Volume or system: Zona, edificio, portal o identificador de la parte geográfica del proyecto.
Si no procede se coloca XX. En el ejemplo Z1 es zona 1. Se definirá de manera
previa en cada proyecto la nomenclatura de las distintas partes zonificadas.

Level: Nivel o planta. Si el documento no alude a una sola planta en concreto el valor será
XX. Algunos autores utilizan ZZ

Discipline: Disciplina (parámetro con valores predefinidos). En el ejemplo A es Arquitectura.
Indica el equipo de trabajo específico dentro del equipo de desarrollo.
Type Document: Tipo de documento
Descripción: Descripción del documento (Presupuesto)

Manual de nomenclatura de elementos y documentos BIM 46

<!-- p. 47 -->

Status: Situación o estado. Parámetros con valores predefinidos. S0 Por ejemplo es Workin
progresso documento en proceso de trabajo. Este atributo indica los usos
permitidos del documento y la fiabilidad de sus datos o su estado de aprobación.
Version: Versión 1 del proyecto básico. v.B1

Discipline El atributo o parámetro disciplina hace alusión a la especialidad del proyecto relacionada con
el documento reflejado en el equipo de trabajo que produce el documento.

Si bien existen distintas posibilidades para tomar una taxonomía o una clasificación universal
de disciplinas, ninguna puede ocupar todas las variantes necesarias. Es por ello que tomamos
la clasificación que recoge la BS 1192 con una interpretación propia de la traducción (en azul)
que se intenta adaptar a las distintas figuras habituales en el trabajo proyectual en España.

Dicha clasificación indexa por orden alfabético distintas disciplinas.

Obviamente esta propuesta no recoge la totalidad de las posibilidades, sino que, una vez
más, plantea un punto de partida que el usuario puede modificar, adaptar, recortar o ampliar
según sus necesidades.

Valores Abreviaturas
Architect /Arquitectura A
Civil engineer / Obra civil C
Electrical engineer /Instalaciones E
eléctricas.
Facilities Manager F
Geographical and land surveyor G
/Topografía
Interior Designer /Decoración I
Client K
Landscape architect /Paisajismo L
Mechanical engineer /Instalaciones M
mecánicas
Quantity surveyor /Costes Q
Structural Engineer /Estructura S
Seguridad y salud SS
Town and country planner / T
Urbanismo
Contractor /Contratista W
Sub-Contractor /Subcontratista X
Specialist designer /Especialista en Y
diseño

El campo Tipo de documento indica el tipo de contenido del mismo.Tipo de documento
Si bien hay interpretaciones y la propia BS 1192 refleja tipos de archivos para dibujos o modelos,
/ Type document
entendemos que en ese caso la extensión del archivo ya da la información necesaria, sin
embargo, sí es preciso una aclaración del tio contenido del mismo aunque tambien puede
integrarse este dentro del campo descripción.

En el caso de realizarse así, integrando el tipo de documento en la descripción, por ejemplo
podríamos considerar una descripción como:

Manual de nomenclatura de elementos y documentos BIM 47

<!-- p. 48 -->

PRESUPUESTO DE EJECUCIÓN MATERIAL
Donde no sería necesario añadir un campo más para describir el tipo de documento,
quedando el nombre de la siguiente forma:

PR2001/BL/Z1/XX/A/PRESUPUESTO DE EJECUCIÓN
MATERIAL/S0/V.B1

Y en caso de incluirlo como un campo independiente para describir el tipo de documento:

PR2001/BL/Z1/XX/A/PR/EJECUCIÓN MATERIAL/S0/V.B1

El usuario deberá determinar en su caso si opta por una opción u otra.
A modo de ejemplo no exhaustivo, indicamos aquí los valores de abreviaturas de tipo de
documento propuestos como más usuales:

Valores Abreviaturas
Modelo M
Planos PL
Memoria MR
Pliego de condiciones PC
Presupuesto PR
Presupuesto ciego PRC
Mediciones MD
Ficha técnica FT
Instrucciones de uso y UM
mantenimiento
Estudio de seguridad y salud ESS
Plan de seguridad y salud PSS
Estudio geotécnico EG
Plan de gestión de residuos PGR
Solicitud de aclaración SA
Acta de reunión AC
Fotos o imágenes PH
Renderizados RD

Atributo que indica el estado de disponibilidad y/o aprobación del documento.Status (documentos)

Valores Abreviaturas
Estado inicial de la información S0
generada antes de revisar por el
coordinador. WIP para aprobar.
Adecuado para coordinación en WIP S1
general aprobado para coordinación,
pero no compartido con otros
agentes.
Compartido con otros. Apto para S3
revisión y comentario externo

Manual de nomenclatura de elementos y documentos BIM 48

<!-- p. 49 -->

Compartido con otros. Apto para S5
fabricación
Compartido con otros. Apto para S6
autorización PIM (proyecto de
ejecución)
Compartido con otros. Apto para S7
autorización AIM
Publicado. Apto para licitación o D2
solicitud de precio
Publicado. Apto para contratación, D4
fabricación, adquisición de equipos,
encargo de manufacturación,
prefabricados o petición de licencia.
Archivado. Información para el AIM o CR
“As Built”

Versión Refleja la versión del documento. Se establece un código de abreviaturas que además refleja
la fase del proyecto y la versión del documento, hasta la entrega del activo.
A modo de ejemplo:
Valores Abreviaturas
Anteproyecto (A) v.A0, vA.1,v.A2,...v.An
Básico (B) v.B0,v.B1,v.B2,…v.Bn
Ejecución (E) v.E0,vE1,vE2,…v.En
Licitación (L) v.L0,vL1,vL2,…v.Ln
Obra (Ob) v.Ob0,v.Ob1,vOb2,…v.Obn
As Built (AB) v.AB0,v.AB1,vAB2,…v.ABn

BIBLIOGRAFÍA

BS 1192:2007 + A1:20115 . Collaborative proeuction of architectural engineering and
construction information-Code of practice. BRITISH STANDARD.

Morris,Siân. BIM FUNDAMENTALS. BS 1192:2007 Information naming & suitability codes.

uBIM: Guía en español para usuarios. BIMbuildingSMART Spanish Chapter. 2012

Manual de nomenclatura de elementos y documentos BIM 49

<!-- p. 50 -->

Manual de nomenclatura de elementos y documentos BIM 50
