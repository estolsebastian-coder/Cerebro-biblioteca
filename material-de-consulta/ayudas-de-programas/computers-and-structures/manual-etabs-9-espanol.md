---
type: libro
title: "Computers and Structures, Inc"
author: "Morrison Ingenieros"
categoria: "AYUDAS DE PROGRAMAS"
paginas: 242
extraccion: "texto"
fuente: "local:E:/MATERIAL DE CONSULTA/AYUDAS DE PROGRAMAS/COMPUTERS AND STRUCTURES/Manual ETABS 9 Español.pdf"
convertido: 2026-10-16
---

# Computers and Structures, Inc

> Texto extraído de `AYUDAS DE PROGRAMAS\COMPUTERS AND STRUCTURES\Manual ETABS 9 Español.pdf` (242 páginas, texto). El PDF original está en el disco E: (MATERIAL DE CONSULTA); `<!-- p. N -->` marca el inicio de cada página.

<!-- p. 1 -->

ETABS®

Software de Diseño Integral para Edificaciones

Bienvenido a ETABS

Computers and Structures, Inc. Versión 9
Berkeley, California, USA November 2005

<!-- p. 2 -->

Derechos Reservados

El programa de computación ETABS y toda la documentación asociada a ella constituyen
propiedad y derechos reservados. A nivel mundial los derechos de propiedad recaen sobre la
persona moral denominada Computers and Structures, Inc. El uso de este programa o la
reproducción de su documentación en cualquiera de sus formas, requiere de autorización por
escrito de la empresa denominada Computers and Structures, Inc., queda estrictamente
prohibido cualquier uso sin dicha autorización.

Para mayor información y obtención de copias de esta documentación refiérase a:

Computers and Structures, Inc.
1995 University Avenue
Berkeley, California 94704 USA

Teléfono: (510) 845-2177
FAX: (510) 845-4096
e-mail: info@csiberkeley.com (para información general)
e-mail: support@csiberkeley.com (Soporte Técnico)
Pagina web: www.csiberkeley.com

\~ Copyright Computers and Structures, Inc., 1978-2005.
El logo CSI constituye una marca registrada de Computers and Structures, Inc.
ETABS es una marca registrada deComputers and Structures, Inc.
“Watch & Learn” es una marca registrada de Computers and Structures, Inc.
Windows es una arca registrada de Microsoft Corporation.
Adobe y Acrobat son marcas registradas de Adobe Systems Incorporated.

<!-- p. 3 -->

ADVERTENCIA

SE HAN INVERTIDO TIEMPO CONSIDERABLE, ESFUERZO Y GASTOS HACIA EL
DESARROLLO Y DOCUMENTACION DE ETABS. EL PROGRAMA HA SIDO
PROBADO Y USADO DETENIDAMENTE. DE CUALQUIER MODO, AL HACER
USO DEL PROGRAMA, EL USUARIO ACEPTA Y ENTIENDE QUE NO EXISTE
GARANTIA IMPLICITA DE LOS DESARROLLADORES O DISTRIBUIDORES EN
LA PRECISION O CONFABILIDAD DEL PROGRAMA.

EL USUARIO DEBE ENTENDER EXPLICITAMENTE LOS SUPUESTOS DEL
PROGRAMA Y DEBE VERIFICAR LOS RESULTADOS DE FORMA
INDEPENDIENTE.

<!-- p. 4 -->

Contenidos

Bienvenido a ETABS

1 Introduccion

Historia y Ventajas de ETABS 1-1

Lo que puede hacer ETABS! 1-3

Un acercamiento Integrado 1-4

Caracterisitcas De Modelado 1-5

Caracterisitcas del Analisis 1-6

2 Iniciando

Instalacion de ETABS 2-1

Si esta haciendo una Actualización (Upgrade) 2-1

Sobre los Manuales 2-2

Películas “Watch & Learn” (Ver y Aprender) 2-2

Soporte Tecnico 2-2

Ayudenos a Ayudarle 2-3

Soporte Telefónico o vía FAX 2-4

Soporte Online 2-4

3 El Sistema ETABS

Revisión del Proceso de Modelado 3-1

Terminología de Modelado Físico 3-2

i

<!-- p. 5 -->

Bienvenido a ETABS

Definición de Piso o nivel 3-3

Unidades 3-4

Coordenadas de Sistemas y Cuadriculas 3-4

Objects Estructurales 3-5

Grupos 3-7

Propiedades 3-7

Compartimientos de Cargas Estáticas 3-8

Cargas Verticales 3-8

Cargas de Temperatura 3-9

Carga Lateral Automatizada 3-9

Funcciones 3-10

Combinaciones deCarga 3-11

Ajustes del Diseño 3-12

Opciones de Salida y Exhibición 3-13

Más Información 3-14

4 Técnicas de Modelado de ETABS

Propiedades de Auto-Selección 4-1

Transferencia de Carga Vertical 4-2

Cargas Laterales de Viento y Sismos 4-3

Modelado del Panel de Zona 4-4

Reducción de Carga Viva 4-5

Modelado de Pisos Rígidos y Semi-Rígidos 4-5

Contraccion de Líneas 4-6

Modificadores 4-7

Construcción de la Secuencia de Carga 4-8

Optimización del Diseño y Precisión de la Barra de 4-8
Acero
Más Información 4-9

ii

<!-- p. 6 -->

Contenido

5 Técnicas de Análisis de ETABS
Análisis Estático y Lineal 5-1

Analisis Modal 5-2

Origen de la Masa 5-2

Análisis de los modos de vibrar 5-3
(Eigenvector)
Análisis del Vector Ritz o modo de vibrar 5-3
(Ritz-Vector)
Respuesta al Análisis de Espectros 5-4

Análisis del Calculo paso a paso(Time History) 5-5

Análisis Time History No-linear (Nonlinear 5-6
Time History)
Analisis Inicial P-Delta 5-6

Analisis No-linear Estatico (Nonlinear Static) 5-7

Más Información 5-8

iii

<!-- p. 7 -->

Capitulo 1

Introducción

ETABS es una propuesta especial de un Programa de diseño y análisis
sofisticado, pero fácil de usar, y desarrollado específicamente para los
sistemas de Edificación. La versión 9 de ETABS ofrece un interfaz gráfico
intuitivo y de gran alcance unido incomparables los procedimientos de
modelar, analíticos, y de diseño, que han sido integrados usando una base de
datos común. Aunque es rápido y sencillo para estructuras simples, ETABS
puede ser usado en los modelos de edificaciones mas grandes y complejas,
incluyendo un amplio rango de comportamientos no lineales, que lo hacen la
herramienta de opción para los ingenieros estructurales en el sector de la
industria de la construcción.

Historia y Ventajas de ETABS
Remontándonos a mas de 30 años atrás, nos topamos con el desarrollo
original de ETABS, el predecesor de ETABS, fue claramente reconocido
que los edificios constituyen un tipo de estructura muy especial. Se lanzaron
programas anteriores a ETABS, que proveyeron datos de entrada, de salida y
soluciones numéricas de técnicas que tomaron en consideración las
características únicas de las estructuras del tipo del edificio, proporcionando
una herramienta que ofreció ahorros significativos en tiempo y aumentó
exactitud sobre los programas para fines generales.

Historia y Ventajas de ETABS 1 - 1

<!-- p. 8 -->

Bienvenido a ETABS

Mientras las computadoras y los interfaces de las computadoras se fueron
desarrollando, ETABS añadió computacionalemente opciones analíticas
complejas tales como comportamiento no lineal dinámico, y poderosas
herramientas de dibujo CAD-like de una interfase grafica basada en el
objeto. Aunque la Versión 9 de ETABS parece radicalmente diferente a sus
predecesoras de hace 30 años, su misión sigue siendo la misma: proveer a la
profesión de uno de los programas mas eficientes y comprensivos para el
análisis y diseño de edificaciones. A tal efecto, el lanzamiento actual sigue
el mismo acercamiento filosófico propuesto por los programas originales, a
saber:

• La mayoría de los edificios se forman de geometría directa, con
vigas horizontales y columnas verticales. Aunque configurar
cualquier edificio es posible con ETABS, en muchos de los casos,
un simple sistema de cuadricula definido por pisos horizontales y
columnas verticales puede establecer la geometría del edificio con un
esfuerzo mínimo

• Muchos de los niveles del piso en los edificios son similares. Esta
concordancia se puede utilizar numéricamente para reducir
esfuerzo computacional.

• Las convenciones de entrada y de salida usadas corresponden a la
terminología común de edificaciones. Con ETABS, los modelos se
definen de forma lógica piso por piso, columna por columna,
tramo por tramo, muro por muro y no como corrientes de puntos
no descritos y elementos como lo hacen la mayoría de los
programas para fines generales. Así la definición estructural es
simple, sucinta y significativa.

• En muchos edificios, las dimensiones de sus miembros son grandes
en relación a los grosores de los tramos y alturas de los pisos. Esas
dimensiones tienen efectos significativos en la densidad de la
barra. ETABS corrige para tales efectos en la formulación de la
rigidez de la pieza, de forma diferente a la que lo hacen los
programas de uso general que trabajan en dimensiones de línea
central a línea central.

• Los resultados producidos por los programas deben ser usados de
forma directa por el ingeniero. Los programas de uso general
producen resultados en los que se requiere de procesos adicionales
antes de que sean usadas en el diseño estructural.

1 - 2 Historia y Ventajas de ETABS

<!-- p. 9 -->

Capitulo 1 - Introducción

Lo que ETABS Puede Hacer!
ETABS ofrece los surtidos más amplios de herramientas de análisis y de
diseño disponibles para el ingeniero estructural que trabaja en las estructuras
de edificios. La siguiente lista representa solo una porción de los tipos de
sistema y análisis que ETABS puede manejar fácilmente:

• Pisos múltiples con facilidades comerciales, gubernamentales y de salud.

• Garajes de Estacionamiento con rampas circulares y lineales

• Edificios escalonados “armadura”

• Edificios con barras de Acero, Concreto o piso compuesto o de viguetas.

• Edificios basados en sistemas de cuadricula o rejillas rectangulares o
cilíndricas.

• Edificios de concreto Plano o losa “aligerado” (waffle)

• Edificios sujetos a cualquier combinación de compartimientos verticales o
laterales, incluyendo cargas de viento y sísmicas automatizadas.

• Respuestas multiples a cargas de espectros, con curvas Multiple integradas.

• Transferencias de carga automatizadas en pisos y de vigas a muros.

• Analisis P-Delta con analisis estatico y dinamico

• Deformaciones explicitas de zona de panel

• Construcción del análisis de la secuencia de cargas.

• Time History Múltiple de compartimientos de carga lineales y no lineales
en cualquier dirección

• Establecimiento de la Cimentación/ Apoyo

• Analisis de Grandes Desplazamientos

• Pushover lineal y estatico

Lo que ETABS Puede Hacer ! 1 - 3

<!-- p. 10 -->

Bienvenido a ETABS

• Edificios con apagadores y aisladores base

• Moldeado de pisos con diafragmas rígidos o semi-rígidos

• Reducciones de carga vertical automatizadas

• Y mucho más!

Un acercamiento Integrado
ETABS es un sistema completamente integrado. Detrás de una interfase
intuitiva y simple, se encajan poderosos métodos numéricos, procedimientos
de diseño y códigos internacionales de diseño, que funcionan juntos desde
una base de datos comprensiva. Esta integración significa que usted crea
solo un sistema de modelo de piso y sistemas de barras verticales y laterales
para analizar y diseñar el edificio completo.

Todo lo que usted necesita se integra en un versátil paquete de
análisis y diseño basado con un utilizador de interfase grafica basada
en Windows. No se mantienen módulos externos y no se transfieren
datos entre programas o módulos. Los efectos producidos en una parte
de la estructura por los cambios realizados en otra son instantáneos y
automáticos. Los módulos integrados incluyen: Modulo de Guía para
generar el modelo (Drafting module for model generation)

• Modulo generador de cargas de viento y sismicas.

• Módulo Distribuidor de cargas de gravedad para la
distribución de cargas verticales a columnas y vigas cuando
los elementos de flexión de los pisos de la placa no se
proveen como parte del sistema del piso.

• Modulo de análisis lineal estático y dinámico basado en
elemento finito. Finite element-based linear static and dynamic
analysis module.

• Modulo de análisis no-lineal estático y dinámico basado en
elemento finito. Finite element-based nonlinear static and
dynamic analysis module (Solo disponible en la versión no-lineal de
ETABS).

• Exhibición de datos de salida y Reporte del modulo de Generación.

1 - 4 Un Acercamiento Integrado

<!-- p. 11 -->

• Módulo de diseño de barras de acero (columna, viga y Contraviento).

• Módulo de diseño de barra de Concreto (columna y viga).

<!-- p. 12 -->

Capitulo 1 - Introducción

• Módulo de diseño de barra compuesta.

• Módulo de diseño de la vigueta de acero

• Módulo de diseño de Muro Constante.

La versión 9 de ETABS esta disponible en dos versiones:

• ETABS Plus. Incluye todas las funciones y capacidades, excepto los
análisis estáticos y dinámicos no lineales. Se incluyen los módulos
de diseño de la barra de Acero, diseño de barra de concreto, diseño
de vigas compuestas, diseño de vigueta de acero, y de diseño de
muro constante.

• ETABS Nonlineal. Incluye todas las funciones de ETABS Plus,
más la capacidad de los análisis estático y dinámico no lineales.

Funciones de Modelado
El edificio ETABS es idealizado como un ensamblaje de puntos área, línea y
objeto. Esos objetos son usados para representar muros, pisos, columnas,
vigas, contrapesos, y piezas de conexión o resortes. Las geometría básica de
barras se define en una sistema de cuadricula tridimensional. Con técnicas de
Modelado relativamente simples, las situaciones de barras muy complejas
deben ser consideradas.

Los edificios deben ser asimétricos y n-rectangulares en el plano. El
comportamiento torsional de los pisos y la compatibilidad entre pisos se ve
reflejada de forma precisa en los resultados. La solución hace cumplir la
compatibilidad del completo desplazamiento tridimensional, haciendo
posible capturar de forma tabular los efectos asociados con el
comportamiento de estructuras muy altas que tienen columnas relativamente
con mucho espacio.

Los diafragmas de pisos Semi-rigidos pueden ser moldeados para capturar los
efectos de las deformaciones del piso dentro del plano. Los objetos del piso
pueden tener un tramo entre dos niveles adyacentes para crear pisos inclinados
(rampas), mismas que pueden ser útiles para moldear estructuras como los
estacionamientos.

El Modelado de diafragmas parciales, tales como en entresuelos, reveses y atrios, es
posible sin usar un (“dummy”) piso artificial y líneas de columnas. También es
posible moldear situaciones con diafragmas múltiples e independientes de cada
nivel, permitiendo el Modelado de edificaciones constituidas de varias torres que se
elevan de una base común.

Opciones de Modelado 1 -
5

<!-- p. 13 -->

Bienvenido a ETABS

Los elementos de columna, viga y contrapeso, pueden ser no-prismáticos, y
ellos pueden tener fijación parcial en sus conexiones finales. También
pueden tener patrones de carga uniformes, parcialmente uniformes, o
trapezoidales. Los efectos de dimensiones finitas de las vigas y columnas en la
rigidez del sistema de barra se incluyen usando offsets finales que se pueden
calcular de forma automática.

Los pisos y muros pueden moldearse solamente como elementos con
membrana firme y dura, los elementos de flexión en placa con rigidez fuera
de plano y solamente con elementos completos del tipo shell, mismos que
combinan con rigidez o dureza dentro-plano y fuera-de plano. Los objetos tipo
muro y piso pueden tener patrones de carga uniformes dentro y fuera de
plano, y deben tener cargas de temperatura. Los objetos columna, viga,
contrapeso, piso y muro son compatibles entre ellos.

Caracteristicas del Analisis
Son posibles los análisis estáticos para pisos laterales y cargas de niveles que
especifique el usuario. Si los elementos del piso con capacidad flexión en
placa son moldeados, las cargas laterales uniformes en el piso serán transferidas
de las vigas y columnas a través de la flexión de los elementos del piso. De otra
forma, las cargas laterales uniformes en el piso se convierten automáticamente
a cargas de tramos en vigas colindantes, o en cargas de puntos o columnas
adyacentes, de tal modo la tediosa transferencia tributaria de carga de las
vigas de pisos se hace automática sin hacer el Modelado explicito de las
barras secundarias
Note:
El programa puede generar de forma automática patrones de carga laterales El manual de
Verificación de viento y sísmicos para conocer los requerimientos de los diversos
del software de códigos de edificación. El modo tridimensional de figuras y frecuencias,
ETABS factores de participación modal, dirección de factores y porcentajes de
documenta el participación de masas son evaluados usando el análisis del vector propio o
análisis el vector-ritz. Los efectos P-Delta pueden ser incluidos con el análisis
usando estático o dinámico.
ETABS.
Son posibles las respuestas al análisis de espectros, análisis de cálculo paso
a paso o Time History lineal, análisis de Time History no lineal (pushover).

1 - 6 Características del Análisis

<!-- p. 14 -->

Capítulo 1 - Introducción

Las capacidades estáticas no lineales también le permiten ejecutar el análisis
de incremento de la construcción para que esas fuerzas que surgen como
resultado de la construcción de dicha secuencia sean incluidas.

Los resultados de diversas condiciones de carga estáticas deben ser
combinados con cada uno de los resultados de la respuesta dinámica del
espectro o con el análisis de Time History.

La salida puede ser vista de forma grafica, exhibida de forma tabular,
enviado a un impresora, exportada a un archivo de base de datos o guardado
en un archivo ASCII. Los tipos de salida incluyen reacciones y fuerzas de
las piezas, modos de figuras y factores de participación, desplazamientos
estáticos y dinámicos de niveles o pisos constantes, desplazamientos o
amontonamientos de nodos entre pisos, Time History de trazos, y mas.

Características del Análisis 1 - 7

<!-- p. 15 -->

Capítulo 2

Iniciando

ETABS es un programa con fines especiales, fácil de usar, y sin embargo
extremadamente poderoso, y el cual fue creado expresamente para sistemas
de edificaciones. Este capitulo le ayudara a iniciarse en el uso de este
programa.

Instalando ETABS
Por favor, siga las instrucciones de instalación que provee por separado su
paquete de ETAB, o pregunte a su administrador de sistema como instalar el
programa y tener acceso a el mismo.

Si usted esta realizando una Actualización
Si esta realizando una actualización de una versión previa de ETABS, debe
estar consiente de que el modelo actual se define en términos de Objetos, los
cuales son divididos automática e internamente en Elementos durante el
análisis.

Este cambio significativo, mejora drásticamente las capacidades del
programa, y le recomendamos leer el resto de este manual para
familiarizarse con esta y otras características del programa.

Instalando ETABS 2 - 1

<!-- p. 16 -->

Bienvenido a ETABS

Acerca de los Manuales
Este volumen esta diseñado para ayudarlo a ser productivo con ETABS. El
programa le provee de este manual de Bienvenido a ETABS, un manual de
Guía de Introducción para el Usuario y un Tutorial. El siguiente capitulo de
este manual le proporciona una sinopsis de la terminología usada en
ETABS, y los Capítulos 4 y 5 describen las técnicas de Modelado y análisis,
respectivamente. Los 13 Capítulos de la Guía de Introducción para el
usuario le dan una introducción de los pisos y elementos del menú que son
usados para crear, analizar y diseñar el modelo. El Tutorial describe los
procesos de creación del modelo, análisis y diseño para un ejemplo de
modelo. El Manual de Verificación de Software describe el análisis de los
sistemas del edificio usando ETABS.
Es muy recomendado que usted lea este manual y observe los videos del
tutorial ( “Watch & Learn~ Movies”) antes de que intente completar un
proyecto usando ETABS.

Información adicional puede ser encontrada en la opción de ayuda en línea (on-
line Help) que se encuentra disponible en la interfase grafica de ETABS,
incluyendo Notas Ténicas (Technical Notes) que describen códigos
específicos de algoritmos de diseño. Esos documentos están disponibles en
el formato de Adobe Acrobat PDF en el CD de ETABS, y puede accesarse a
ellos desde el programa usando el Menú de Ayuda (Help menú).

Videos “Observe y Aprenda” (“Watch & Learn”)
Uno de los mejores recursos disponibles para aprender acerca del programa
ETABS es la serie de videos “Watch & Learn”, mismos que pueden ser
vistos en el CD de ETABS o mediante la pagina web
http://www.csiberkeley.com. Esos videos contienen información abundante
para los dos tipos de usuario de ETABS, el que usa por primera vez el
programa y el experimentado, cubriendo un amplio rango de temas, que van
desde las operaciones básicas hasta el Modelado complejo. Los videos
tienen una duración que varia entre los 2 a 13 minutos aproximadamente.

2 - 2 Acerca de los Manuales

<!-- p. 17 -->

Capitulo 2 - Iniciando

Soporte Técnico
La empresa Computers and Structures, Inc. (CSI) ofrece soporte técnico
gratuito vía telefónica, fax, y e-mail por 90 días después de la compra del
programa. Después de dicho termino, el soporte técnico esta disponible
conforme a los términos del Acuerdo de Mantenimiento del Software
(Software Maintenance Agreement), mismo que puede ser adquirido mediante
la compra a CSI o su proveedor. Por favor contacte a la empresa CSI para
obtener información acerca del acuerdo antes mencionado (Software
Maintenance Agreement).

Si usted tiene alguna duda con respecto al uso del programa, le sugerimos:

• Consultar esta documentación y la demás información impresa
que incluye su producto.

• Revisar la opción de ayuda on-line (on-line Help) que ofrece el

programa.

• Revisar los videos “Watch and Learn” que proporciona el CD de
ETABS y también la pagina web de CSI
http://www.csiberkeley.com.

Si su duda no es resuelta de ese modo, contáctenos cose describe en la

siguiente sección.

Ayudenos a Ayudarle
En cualquier momento que usted nos contacte con el fin de obtener solución
a una pregunta de soporte técnico, recuerde proporcionar la siguiente
información:

• El nivel del programa (PLUS or Nonlinear) y el numero de
versión que usted esta usando. Estos datos pueden obtenerse desde
el programa usando el menú de ayuda Help menu > y después el
comando About ETABS.

• Una descripción de su modelo, incluyendo una imagen, de ser
posible.

• Una descripción de lo que ocurrió y lo que usted estaba haciendo
cuando ocurrió el problema.

Soporte Tecnico 2 - 3

<!-- p. 18 -->

• El mensaje literal del error que apareció en su pantalla.

• Una descripción de como trato usted de resolver el problema.

• La configuración de su computadora (marca y modelo,
procesador, sistema operativo, tamaño del disco duro, y tamaño de
la memoria RAM).

• Su nombre, nombre de su compañía, y como podemos contactarlo.

<!-- p. 19 -->

Bienvenido a ETABS

Soporte Telefonico o via FAX
El soporte telefónico o vía fax estándar esta disponible en los Estados
Unidos y esta a cargo de ingenieros de CSI, entre las 8:30 A.M. and 5:00
P.M., Hora del Pacifico, Lunes a Viernes, excepto los en los días festivos de
U.S.A.

Usted puede:

• Contactar a las oficinas de CSI vía telefónica (510) 845-2177, o

• Enviar un fax con sus preguntas y la información acerca de su
modelo, (incluyendo una imagen, de ser posible) a CSI al numero
(510) 845-4096.

Cuando realice la llamada, por favor, hágalo en su computadora y tenga a la
mano su manual.

Soporte Online
Esta disponible:

• Enviando un e-mail y el archivo de su modelo a
support@csiberkeley.com

• Visite la pagina web de CSI http://www.csiberkeley.com para leer
las preguntas mas frecuentes.

Si nos envía un e-mail, asegúrese de que ha incluido toda la información que se
l ha solicitado en la sección de Ayúdenos a Ayudarle “Help Us to Help You”.

2 - 4 Soporte Telefónico y vía FAX

<!-- p. 20 -->

Capitulo 3

El sistema ETABS

ETABS analiza y diseña la estructura de su edificio usado el modelo que
usted a creado usando la interfase grafica del usuario. La clave para
implementar exitosamente ETABS es entender que se debe tener un
acercamiento a través del Modelado de sistemas de edificios. Este capitulo le
proporcionara una vista rápida y descripción de algunos de los componentes
clave y su terminología.

Descripcion del Proceso de Modelado
El Modelado creado con este programa, es diferente a otros modelos que han
sido producidos con otros programas de análisis estructural, principalmente
por dos razones:

• Este programa ha sido optimizado para la creación de sistemas de
edificios. De esta forma, los procedimientos de Modelado y
capacidades de diseño son adaptados a los edificios.

• El Modelado de este programa se basa en objetos. Consistentes en
objetos puntos, líneas y área. Usted realiza tareas con dichos
objetos para definir piezas estructurales, tales como vigas,
columnas, contrapesos, pisos, muros, rampas y resortes. También
puede decir cargas con esos mismos objetos.

Dscripcion del Proceso de Modelado 3 - 1

<!-- p. 21 -->

Bienvenido a ETABS

De forma más simple, desarrollar un modelo requiere de tres pasos básicos:

• Dibujar series de objetos puntos, líneas y área que representen su
edificio usando las diversas herramientas de dibujo que se
encuentran disponibles en la interfase grafica.

• Asignar propiedades estructurales (secciones y materiales) y cargas
a objetos usando las opciones del menú Asignar (Assign menu
options). Note que el asignar propiedades estructurales puede ser
completado mediante el trazo del objeto usando la caja de
propiedades del Objeto (Properties of Object box), misma que
aparece cuando se utilizan los comandos de Dibujar (Draw).

• Asignar parámetros de división interna (meshing) a objetos area, si
estos no son membranas horizontales losa o secciones
tablero/tablón que el programa automáticamente divide hacia los
elementos necesarios para el análisis del modelo.

Cuando el modelo esta terminado, el análisis puede ser ejecutado. En ese
momento, el programa convierte de forma automática los modelos basados
en objetos en modelos basados en elementos, a esto se le conoce como
modelo del análisis usado en el análisis total. El modelo del análisis consiste
de nodos, elementos barra, elementos conexión y shell (membrana y placa)
elementos en contraste a los objetos punto, línea y área en el modelo basado
en objetos que especificó el usuario. La conversión del modelo del análisis es
interno en el programa y esencialmente transparente para el usuario.

Terminología del Modelado Físico
En ETABS, nos referimos frecuentemente a Objetos, Piezas o Miembros, y
Elementos. Los Objetos representan las piezas o miembros estructurales
físicos en el modelo. Los Elementos, por otro lado, se refieren a los
elementos finitos usados internamente por el programa para generar matices
rígidos. En muchos casos, los objetos y miembros físicos, tendrán
correspondencia de uno-a-uno, y son estos objetos los que “dibuja” el
usuario en la interfase de ETABS. Los Objetos se han pensado como una
representación exacta de los miembros o piezas físicas. Los usuarios
típicamente no requieren involucrase con el proceso de división interna de
esos objetos entre los elementos requeridos para el análisis matemático del
modelo.

3 - 2 Terminología del Modelo Físico

<!-- p. 22 -->

Capitulo 3 – El sistema ETABS

Por lo anterior, un simple objeto línea puede moldear una viga completa, sin
importar cuantos otros miembros tiene la barra, y sin importar la carga. Con
ETABS, la creación del modelo y el reporte de los resultados se alcanza en
el nivel del objeto.

Esto difiere del programa con análisis tradicional, donde el usuario necesita
definir un su-ensamblaje de elementos finitos que abarque los elementos
físicos más grandes. En ETABS, los objetos, o miembros físicos o piezas,
que dibuja el usuario, son típicamente subdivididos de forma interna entre un
gran número de elementos finitos necesarios para el modelo de análisis, sin
que el usuario los ingrese. En virtud, de que el usuario trabaja solo con los
miembros físicos basados en objetos, se requiere de menor tiempo para crear
un modelo y para interpretar los resultados, añadiendo a ello el beneficio de
que los resultados del análisis son generados de forma mas apropiada para el
trabajo de diseño que sigue.

El concepto de objetos en un modelo estructural puede ser nuevo para usted.
Es extremadamente importante que usted se aferre a este concepto porque es
la base para crear un modelo en ETABS. Después de que haya entendido el
concepto y haya trabajado con el por un rato, debe reconocer la simplicidad
del Modelado basado en el objeto, la facilidad con la que usted puede crear
modelos usando objetos, y el poder del concepto cuando se editan y se crean
modelos complejos.

Definicion del Piso
Una de las características mas importantes de que ofrece ETABS es el
reconocimiento de los niveles de pisos, permitiendo el ingreso de datos de
construcción de una forma conveniente y lógica. Los usuarios pueden definir
sus modelos bases de piso-piso, nivel-nivel, de forma análoga en la que un
diseñados trabaja cuando presenta los dibujos del edificio. Los niveles de
pisos ayudan a identificar, localizar y ver áreas y objetos específicos en su
modelo; objetos columnas y vigas son localizados fácilmente usando su
localización en el plano y su etiquetado o rotulado en el nivel y piso.

En la terminología de ETABS, un nivel de piso, representa un plano
horizontal que se ve a través de un corte del edificio a una elevación
especifica, y todos los objetos debajo de dicho plano hasta el siguiente nivel
de piso. Debido a que ETABS entiende de forma inherente la geometría de
los sistemas del edificio, el usuario puede especificar que el objeto que esta
siendo dibujado puede ser multiplicado en todos los pisos, o en pisos
similares que el mismo ha identificado. Esta opción funciona no solo en
repetición de barras de piso, si no también para columnas y barras. El

Story Definition 3 - 3

<!-- p. 23 -->

Welcome to ETABS

Rotulado o etiquetado del piso, la altura de cada nivel de piso, asi como la
habilidad para marcar los pisos similares, se encuentran bajo el control del
usuario.

Unidades

ETABS trabaja con cuatro unidades básicas; fuerza, longitud, temperatura
y tiempo (force, length, temperature, and time). El programa ofrece diferentes
sets de unidades compatibles de fuerza, longitud y temperatura para elegir,
tales como “Kip, in, F” o “N, mm, C.” El tiempo siempre se mide en
segundos.

Se hace una importante distinción entre masa y peso. Masa se usa para calcular
la inercia dinámica y para todas las cargas causadas por la aceleración del suelo.
El peso es la fuerza que se aplica como cualquier fuerza de carga. Asegúrese de
usar las unidades de fuerza cuando especifique valores de peso, unidades de
masa (fuerza-sec2/longitud) al especificar valores de masa.

Cuando usted inicia modelo, se le requiere para que ajuste un set de
unidades. Estas se convierten en las “unidades base”. Aunque después usted
puede proporcionar nuevos datos y ver los resultados en cualquier set de
unidades, esos valores son convertidos siempre y forman la base de las
unidades del modelo.

La medida angular siempre usa las siguientes unidades:

• Geometría: la orientación de cortes, siempre se mide en grados.

• Los desplazamientos rotatorios, se mide en radianes.

• La Frecuencia se mide en ciclos/segundo (Hz).

Sistemas de Coordenadas y Cuadriculas o rejillas.
Todas las ubicaciones del modelo se definen respecto a un sistema de
coordinas con un ángulo global. Es un sistema tridimensional de
coordenadas Cartesiano (rectangular), derecho (right-handed). Los tres
cortes denominados, X, Y, y Z, son mutuamente perpendiculares, y satisfacen
la regla derecha (right-hand rule).

3 - 4 Unidades

<!-- p. 24 -->

Capitulo 3 – El sistema de ETABS

ETABS siempre considera la dirección +Z como hacia arriba. Por valor
predeterminado, la gravedad actúa en la dirección –Z.

Los sistemas de coordenadas adicionales pueden definirse para ayudar al
desarrollo y vista del modelo. Para cada sistema de coordenadas, se deberá
definir un sistema de cuadricula tridimensional y ello consistirá en líneas de
“construcción” que serán usadas para localizar objetos en el modelo. Cada
sistema de rejillas coordenadas debe ser cartesiano (rectangular) o tener una
definición cilíndrica, y como se posiciona de forma relativa al sistema
global. Cuando usted mueve una línea de la cuadricula, debe especificar cual
es el objeto que se moverá con ella.

Las operaciones de dibujo tienden a adherirse “snap” a las líneas de
intersección de la cuadricula (de forma predeterminada) a menos, que esta
opción se desactive. Existen otras formas de “snap” disponibles, incluyendo
el adherir terminaciones de líneas a puntos medios (midpoint), adherir a
intersecciones, y así sucesivamente. Use estas herramientas poderosas
cuando le sea posible para asegurar la exactitud en la construcción de su
modelo. No usar la función de “snap” puede resultar en espacios “gaps”
entre objetos, que causarían errores en la conectividad del modelo.

Cada objeto en el modelo tiene su propio sistema local de coordenadas usado
para definir propiedades, cargas y respuestas. Se denotan los cortes de cada
sistema local de coordenadas 1 (rojo), 2 (blanco), y 3 (azul). Los sistemas
locales de coordenadas no tienen una cuadricula asociada a ella.

Objetos Estructurales
Como se ha asentado previamente, ETABS usa objetos para representar
miembros estructurales físicos. Al crear modelo, el usuario empieza
dibujando la geometría del objeto, y después asignándole propiedades y
cargas para definir completamente la estructura del edificio.

Los siguientes tipos de objetos están disponibles, y se enlistan de acuerdo a
su dimensión geométrica:

\~ Dos tipos de Objetos Punto (Point objects):

o Objetos nodo (Joint objects) se crean de forma automática
en las esquinas o en las terminaciones de todos los tipos de
objetos, y pueden ser adheridos explícitamente en cualquier
lugar del modelo.

Objetos Estructurales 3 - 5

<!-- p. 25 -->

Bienvenido a ETABS

• Objetos instalados en el suelo (de un nodo) y de
conexión “Grounded (one joint) link objects” se usan
para moldear conductas de soporte especial, tales como
aislantes, apagadores, huecos, resortes multilimeales y
mas.

• Dos tipos de Objetos línea (Line objects)

• Objetos Barra (Frame objects) son usados para moldear
barras, columnas, contrapesos y armaduras.

• Conectores (dos-nodos) objetos de conexión “Connecting
(two-joint) link objects” son usados para moldear el
comportamiento de un miembro en especial, tales como
aislantes, apagadores, huecos, resortes multilineales y mas.
Objetos barra desiguales, los objetos conectores pueden
tener una longitud de cero.

• Objetos área (Area objects) se usan para moldear muros, losas,
cubiertas, tablones y otros miembros de muros delgados. Los
objetos área serán divididos internamente de forma automática
entre los elementos requeridos para el análisis, si los objetos
horizontales con definición de membrana se incluyen en el
modelo; de otra forma, el usuario especifica la opción de división
que será usada.

Como regla general, la geometría del objeto corresponde a la de ese miembro
físico. Esto simplifica la visualización del modelo y ayuda en el proceso de
diseño.

Cuando usted ejecuta el análisis, ETABS automáticamente convierte su
modelo basado en objetos (excepto ciertos objetos Área) en un modelo
basado en elementos que es usado en el análisis. Este modelo basado en
elementos se llama modelo de análisis, y consiste en elementos finitos y
nodos. Después de ejecutar el análisis, su modelo basado en objetos aun tendrá el
mismo número de objetos en l, tal y como era antes de ejecutar el análisis.

Aunque la mayoría de la división interna los objetos se realiza de forma automática,
usted tiene control sobre la forma en que se completa dicha división interna, tal
como el refinamiento de los ángulos y como manejar las conexiones al intersecar
objetos. Existe la opción de subdividir el modelo de forma manual, divide al
elemento basado en el objeto en un miembro físico y a ese en objetos múltiples que
corresponden en tamaño y numero de elementos del análisis.

3 - 6 Objetos Estructurales

<!-- p. 26 -->

Capitulo 3 – El sistema de ETABS

Grupos
A un grupo se le denomina colección de objetos. Pueden contener cualquier
número de objetos de cualquier tipo. Los grupos tienen muchos usos:

• Selección rápida de objetos para editarlos o asignarlos

• Definir secciones de corte a través del modelo.

• Agrupar objetos que comparten el mismo diseño.

• Salida selectiva.

Defina todos los grupos que sean necesarios. El uso de los grupos es una
manera poderosa de manejar modelos grandes.

Propiedades
Las propiedades son “asignados” a cada objeto para definir el
comportamiento estructural de cada objeto en el modelo. Algunas
propiedades, como materiales y propiedades de sección, se denominan
entidades y deben ser especificadas antes de asignarles objetos. Por
ejemplo, un modelo debe tener:

• Un material propiamente llamado CONCRETO.

• Una sección rectangular de la barra denominado RECTANGULO,
y una sección circular de la barra llamada CIRCULAR, ambas se
forman del material llamado CONCRETO.

• Una sección muro/losa llamada propiamente SLAB O LOSA que
solo usa material llamado CONCRETO.

Si usted asigna la sección denominada RECTANGULO a un objeto línea,
cualquier cambio en la definición de la sección RECTANGULO o en el
material CONCRETO automáticamente se aplicara a dicho objeto. Una
propiedad denominada de cualquier forma no tiene efecto en el modelo a
menos que se le asigne a un objeto.

Otras propiedades, tales como los nudos de barra o el alojamiento de los
nodos son asignadas directamente a los objetos. Estas propiedades solo
pueden cambiarse ejecutando otra tarea de la misma propiedad al objeto; no
se denominan entidades y no pueden existir de forma independiente sin los
objetos.

Grupos 3 - 7

<!-- p. 27 -->

Bienvenido a ETABS

Cargas estaticas de los compartimientos
Las cargas estáticas representan acciones sobre la estructura, tales como
fuerza, presión, desplazamiento del soporte, efectos térmicos, y otros. A la
distribución especial de cargas sobre la estructura se le denomina
compartimiento de la carga.

Defina todos los compartimientos de carga que sean necesarios.
Típicamente, los compartimientos de carga separados serian usados para las
cargas muertas, cargas vivas, cargas estáticas terremoto, carga de viento,
cargas de nieve, cargas térmicas, y demás. Las cargas que necesiten variar
independientemente, para propósitos de diseño o por la forma en que son
aplicadas al edificio, deben ser definidas como compartimientos de carga
separados.

Después de definir el nombre del compartimiento estático de la carga, debe
asignar valores de carga específicos a los objetos que son parte del
compartimiento de la carga, o definir una carga lateral automatizada si dicha
carga es para viento o sismo. Los valores de carga que usted asigne a un
objeto especifican el tipo de carga (fuerza, desplazamiento, temperatura), su
magnitud, y dirección (si ella aplica). Diferentes cargas pueden ser asignadas
a un compartimiento individual, junto con la carga lateral automatizada, si as
lo desea. Cada objeto puede ser sujetado a múltiples compartimientos de
carga.

Cargas Verticales
Las cargas laterales, pueden aplicarse a objetos punto, línea y área. Las
cargas verticales son ingresadas típicamente con valores de gravedad, o en la
dirección –Z. Los objetos punto Los objetos punto pueden soportar fuerzas
o momentos concentrados. Los objetos barra pueden tener aplicadas
cualquier numero de cargas punto (fuerzas o momentos) o cargas
distribuidas (uniformes o trapezoidales). Las cargas uniformes pueden ser
aplicadas a los Objetos Área. Los compartimientos de carga laterales
también pueden incluir elementos de propio-peso.

Algunos compartimientos de carga verticales usados para los edificios deben incluir:

\~ Carga muerta

3 - 8 Compartimientos de Carga Estatica

<!-- p. 28 -->

Capitulo 3 – El sistema ETABS

• Carga muerta Súper impuesta

• Carga viva

• Carga Viva Reducida

• Carga de Nieve

Si las cargas verticales aplicadas son asignadas a un compartimiento de
carga viva reducida, ETABS le provee la opción de reducir las cargas vivas
usadas en la fase de diseño. Many different types of code-dependent load
reduction formulations are available.

Cargas de Temperatura.
Las cargas de temperatura en objetos línea y área pueden ser generados en
ETABS al especificar los cambios de temperatura. Esos cambios en la
temperatura pueden especificarse directamente como cambio de temperatura
uniforme en el objeto, o ellos deben estar basados en cambios de
temperatura previamente especificados de objetos punto, o en ambos.

Si se selecciona la opción del cambio de temperatura, el programa asume que el
cambio de la temperatura varía de forma lineal sobre la longitud de las líneas
del objeto, y linealmente sobre la superficie del objeto para las áreas. Although
you can specify a temperature change for a point object, temperature loads
act only on line and area objects.

Cargas Laterales Automatizadas
ETABS permite de forma automática la generación de cargas estáticas
laterales ya sea de terremotos (quake) o compartimientos de carga de viento
basados en numerosos especificaciones de códigos, incluyendo, pero no
limitando a, UBC, BOCA, ASCE, NBCC, BS, JGJ, Mexicana y IBC. Cada
carga lateral automatizada que usted defina debe hacerse en un
compartimiento de carga separado. Usted no puede tener dos cargas laterales
automatizadas en el mismo compartimiento de carga. Usted puede, agregar a
un compartimientos de cargas adicionales que incluya una carga automática
lateral.

Cargas de Temperatura 3 - 9

<!-- p. 29 -->

Bienvenido a ETABS

Si ha seleccionado una carga del tipo sismo, existen códigos de cargas
laterales disponibles. Con la selección del un código, la forma de la carga
sísmica se llena con valores y elementos predeterminados que pueden ser
revisados y editados por el usuario. El programa usa esos valores para
generar cargas laterales en la dirección que se especifique, basando esta
decisión en el peso definido por las masas asignadas o calculadas en las
propiedades de las definiciones. Después de que ETABS ha calculado la
fuerza de cada nivel para una carga sísmica automática, esa fuerza es
proporcionada a cada nodo de la elevación de cada nivel de piso en
proporción a su masa.

Si ha seleccionado la carga de tipo viento, existen varios códigos de cargas
laterales automáticas disponibles. A partir de la selección de un código, la
forma de Carga de viento se llena con valores y elementos predeterminados
que pueden ser revisados y editados el usuario. En ETABS, las cargas de
viento calculadas automáticamente, pueden ser aplicadas a diafragmas
rígidos o a muros, incluyendo muros no-estructurales tales como
revestimientos, que son creados usando objetos área. Si la opción de
diafragma rígido es seleccionada, se calculara una carga separada para cada
diafragma rígido presente en un nivel de piso. Las cargas de viento
calculadas en cualquier nivel de piso se basan en una elevación de dicho
nivel, la altura del piso sobre el nivel inferior, la asumida exposición de la
angostura del diafragma (s) rígido(s) en el nivel y los diversos códigos-
dependientes de los coeficientes de viento. La carga es aplicada a un
diafragma rígido a lo que ETABS calcula que será el centro geométrico.

Si usted ha seleccionad la opción en la que se calculan las cargas de viento
y se aplican mediante vía área los objetos que definen los muros, debe
asignar un coeficiente de presión den viento a cada objeto área que se ha
expuesto, y además indicar si éste es Barlovento/Sotaviento (windward or
leeward). Basándose en los diversos códigos factores y los coeficientes y
exposiciones definidos el usuario, ETABS calcula las cargas de viento para
cada objeto área (muro) y aplica las cargas a puntos fuerza en las esquinas de
dicho objeto.

Funciones
Usted define funciones para describir como varían las cargas como una
función de periodo tiempo. Las Funciones son solo necesarias para ciertos
tipos de análisis, no son usadas para análisis estáticos. Una función es una serie
de pares de datos digitados Absciso–Ordenado (abscissa-ordinate data
pairs).

3 - 10 Funciones

<!-- p. 30 -->

Capitulo 3 - El Sistema ETABS

Existen dos tipos de funciones:

• Funciones de Respuesta de Espectros (Response spectrum
functions) Son las funciones de aceleración pseudo-espectral
contra las funciones de periodo para usarlas en el análisis de
respuesta de espectros. En este programa, los valores de la
aceleración en la función son asumidos como normalizados; esto
es, las funciones por si mismas no tienen unidades. En lugar de ello,
las unidades se asocian con un factor escala que multiplica la función
y es especificada cuando usted define el compartimiento de la
respuesta del espectro.

• Funciones de Time History (Time history functions) Son la
magnitud de las cargas contra las funciones tiempo para usarse en
el análisis de Time History. Los valores de carga en una función de
Time History pueden ser valores de aceleración del suelo o pueden
ser múltiplos de compartimientos específicos (fuerza o
desplazamiento).

Usted puede definir todas las funciones con nombre que le sean necesarias.
Estas no se asignan a objetos, pero son usadas en los compartimientos de
definición de la Respuesta del Espectro y Historia del Tiempo.

Combinaciones de Carga
ETABS permite nombrar combinaciones de cualquier compartimiento de o
cualquier carga combinada y previamente definidas. Cuando una
combinación de carga es definida, se aplica a los resultados de cada objeto
en el modelo.

Los cuatro tipos de combinaciones son las siguientes:

• ADD (Additive) Aditivas: Son agregados los resultados desde los
compartimientos o paquetes de carga incluidos.

• ENVE (Envelope) Envolvente: Los resultados de los compartimientos o
paquetes de carga incluidos son envueltos para encontrar los valores mínimos
y máximos.

• ABS (Absolute) Absoluta: Son agregados los valores absolutos de los
resultados de los compartimientos o paquetes de carga incluidos.

• SRSS: Es computada la raíz cuadrada de la suma de los cuadrados
del resultado de los compartimientos y paquetes de carga.

Combinaciones de carga 3 - 11

<!-- p. 31 -->

Bienvenido a ETABS

Excepto por los de tipo envolvente, las combinaciones usualmente deben ser
aplicadas solo a los compartimientos de análisis lineal, porque los resultados
no lineales no son generados o sobrepuestos.

El diseño siempre se basa en combinaciones de carga, no directamente en
compartimientos de carga. Usted puede crear una combinación que contenga
solo un compartimiento de carga. Cada algoritmo de diseño crea su propia
combinación predefinida; compleméntelas con la combinación que usted
haya diseñado, en caso necesario.

Ajustes del Diseño

ETABS tiene integrados los siguientes post-procesadores de diseño:

• Diseño de Barra de Acero (Steel Frame Design)

• Diseño de Barra de Concreto (Concrete Frame Design)

• Diseño de Viga compuesta (Composite Beam Design)

• Diseño de Vigueta de Acero (Steel Joist Design)

• Diseño de Muro Constante (Shear Wall Design)

Los primero cuatro procesos de diseño son aplicables a objetos línea, y el
programa determina el proceso de diseño apropiado para el objeto línea
cuando se ejecuta el análisis. El procedimiento de diseño seleccionado se
basa en la orientación del objeto línea, propiedad de la sección, tipo del
material y conectividad.

El diseño del Muro Constante esta disponible para objetos que han sido
identificados previamente por el usuario como pilares (pier) o spandrels, y
dichos objetos serán considerados como objetos línea y área.

Para cada post-procesador de diseño, se pueden hacer diversos ajustes para
afectar el diseño del modelo:

• El código de diseño especifico que será usado en cada tipo de
objeto, por ejemplo, AISC-LRFD93 para barras de acero,
EUROCODE 2-1992 para barras de concreto, y BS8110 97 para
muros constantes.

• Preferencias determinadas de esos códigos deben aplicarse al modelo.

3 - 12 Ajustes del Diseño

<!-- p. 32 -->

Capitulo 3 – El sistema ETABS

• Las combinaciones de carga con las que se debe revisar el diseño.

• Los grupos de objetos que deben compartir el mismo diseño.

• Para cada objeto, preceden valores opcionales “overwrite”sobre los
coeficientes y parámetros usados en los códigos de las formulas
seleccionadas por el programa.

• Para barras acero, vigas compuestas, y viguetas de acero, ETABS
automáticamente puede seleccionar una sección optima desde una
lista que usted defina. Usted también puede cambiar manualmente
la sección durante el proceso de diseño. Como resultado, cada
objeto línea, puede tener dos propiedades de secciones diferentes
asociadas con:

• Una sección de análisis “analysis section” usada en el análisis previo.

• Una sección de diseño “design section” del diseño en uso.

La sección del diseño se convierte en la sección de análisis para el siguiente
análisis, y el análisis iterativo y el ciclo de diseño deben continuar hasta que
las dos secciones se conviertan en la misma.

Los resultados para la sección del diseño, cuando están disponibles, tal y como
los otros ajustes descritos en este punto, pueden ser considerados para ser parte
del modelo.

Opciones de salida y Exhibición
El modelo ETABS y los resultados del análisis y diseño pueden ser vistos y
guardados de diversas maneras, incluyendo:

• Vistas Bi-y-Tri-dimensionales del modelo

• Entrada /Salida de valores de datos en formato de texto, hoja de
cálculo, o formato de base de datos.

• Función de Localizador de coordenadas de los resultados del

análisis.

• Reportes de diseño.

• Exportar otros bosquejos y programas de diseño

Opciones de Salida y Exhibición 3 - 13

<!-- p. 33 -->

Bienvenido a ETABS

Usted puede guardar definiciones de la exhibición de las vistas, ajustes de
tablas, y funciones de bosquejos como parte de de su modelo. Combinado con
estos grupos, esto puede dar una velocidad significativa al proceso de
obtención de resultados mientras usted se encuentra desarrollando el modelo.

Más Información
Este capitulo presenta solo un adelanto de algunos de los componentes
básicos de del modelo ETABS. Información adicional puede encontrarse en la
ayuda on-line que se encuentra disponible, ya sea en la interfase grafica del
usuario de ETABS, incluyendo las notas técnicas que describen los códigos-
específicos de los algoritmos de diseño. Esos documentos están disponibles en
el formato de Adobe Acrobat PDF en el CD de ETABS, y puede accesarse a
ellos desde el programa usando el menú de ayuda (Help menú).

3 - 14 Más Información

<!-- p. 34 -->

Capítulo 4

Técnicas de Modelado de ETABS

ETABS ofrece una extensa y diversa rama de herramientas que le ayudaran
a moldear una amplio rango de sistemas y comportamientos del edificio.
Este capitulo ilustra algunas de las técnicas que usted puede usar con
ETABS para realizar cualquier tarea mundana o compleja de forma rápida y
sencilla.

Propiedades de Auto-Selección
Cuando se crea un modelo ETABS que contiene objetos línea de acero (barras,
vigas compuestas, y viguetas), no es necesario determinar el tamaño de los
miembros preliminares explícitos para el análisis. En lugar, de aplicar la una
propiedad de auto-selección a cualquiera o a todos los objetos línea hechos de
acero. Una propiedad de auto- selección es una lista de secciones en lugar que
de un solo tamaño. La lista contiene todos los tamaños de las secciones que
pueden considerarse como posibles candidatos para el miembro físico, y pueden
definirse listas múltiples. Por ejemplo, una lista de auto-selección puede ser
usada en columnas de acero, otra lista puede ser usada para pisos de viguetas, y
una tercera lista puede usarse en vigas de acero o viga maestra (girders).

Propiedades de Auto-Selección 4 - 1

<!-- p. 35 -->

Bienvendo a ETABS

Para el análisis inicial, el programa seleccionara la sección mediana en la
lista de auto-selección. Después de haber completado el análisis, ejecute el
proceso de optimización del diseño para un objeto particular, en el que solo
las medidas de las secciones sean consideradas en la lista de auto-selección,
y el programa automáticamente selecciona la sección mas económica, y
adecuada de la lista. Después de que la fase de optimización del diseño ha
seleccionado una sección, el análisis del modelo debe ser re-ejecutado si la
sección seleccionada difiere de la sección previamente analizada. Este ciclo
debe ser repetido hasta que la sección del análisis y la del diseño sean idénticas.

El uso efectivo de las propiedades de auto-selección puede ahorrarle muchas
horas, al asociarlas con el establecimiento preliminar de los tamaños de los
miembros.

Transferencia de Cargas Verticales
ETABS ofrece poderosos algoritmos para calcular la transferencia de cargas
verticales para tres de los sistemas de pisos mas populares en la construcción
de edificios: losa de concreto, tablero de acero con relleno de concreto, y
tarimas de concreto. Las cargas verticales pueden ser aplicadas como cargas
muertas, cargas vivas, cargas muertas súper impuestas, y cargas vivas
reducibles, con el propio-peso de los objetos incluidos en el compartimiento
de carga muerta, si se desea.

El problema principal de transferencia de las cargas verticales es la
distribución de las cargas punto, línea y área que descansan en el objeto
representando la placa del piso en el modelo del análisis. El análisis de
ETABS para transferencia de cargas verticales difiere para los tipos de piso
con comportamiento de membrana y para los pisos tipo objetos con
comportamiento de flexión en placa. Los siguientes puntos describen el
análisis de los objetos del tipo piso con comportamiento solo del tipo
membrana:

\~ Transformación de carga fuera de plano para objetos área del tipo piso
con propiedades de secciones tablero o tarima (Out-of-plane load
transformation for floor-type area objects with deck or tablón section
properties): En este caso, en el modelo del análisis, las cargas son
transformadas a vigas junto con los elementos de la membrana o los puntos
de las esquinas de los elementos de la membrana usando un numero
significativo de reglas y condiciones (ver notas técnicas Technical Notes
usando el menú de ayuda Help menu para una descripción detallada).
La transferencia de carga toma en cuenta que el tablero o la tarima se
encuadran solo en una dirección.

4 - 2 Transferencia de Cargas Verticales

<!-- p. 36 -->

Chapter 4 - ETABS Modeling Techniques

\~ Transformación de carga fuera de plano para objetos tipo-piso
con propiedades de secciones losa que tienen comportamiento
solo de membrana (Out-of-plane load transformation for floor-
type area objects with slab section properties that have
membrane behavior only): En este caso, en el modelo de análisis,
las cargas son transformadas ya sea, con las vigas junto con las
esquinas de los elementos de la membrana o a los puntos de la
esquina de los elementos de la membrana usando un numero
significativo de reglas y condiciones (ver las notas técnicas
Technical Notes usando el menú de ayuda Help menu para una
descripción detallada). La transformación de las cargas toma en
cuenta que la losa se encuadra en dos direcciones.

Para objetos área tipo-piso que tienen comportamiento tipo placa, ETABS
usa una función de interpolación bi-linear para transferir cargas aplicadas a
objetos área o a los puntos de las esquinas de elementos shell/placa en el
modelo del análisis.

Note que ETABS automáticamente divide internamente los objetos piso con
las propiedades de la membrana para su análisis. Típicamente, los pisos con
comportamiento de flexión en placa requieren la división interna asignada por el
usuario antes de ejecutar el análisis (con excepción de las losas aligeradas o
nervuradas que se generan al usar las plantillas, y las cuales son automáticamente
divididas aunque estas tengan comportamiento tipo flexión en placa).

Para las transferencias de carga descritas aquí, el programa automáticamente calcula
el área tributaria cargada a cada miembro para que esa reducción de los factores de
la transferencia de la carga viva pueda aplicarse. Diversas formulaciones
dependientes de los códigos están disponibles para esos cálculos; como sea, los
valores pueden ser sobre-escritos usando valores especificados por el usuario.

Cargas Laterales de viento y sísmicas
Las cargas laterales pueden ser en la forma de viento o sísmicas. Las cargas son
calculadas automáticamente por las dimensiones y propiedades de la estructura
basada en opciones built-in para una amplia variedad de códigos de construcción.

Para sistemas de diafragmas rígidos, las cargas de viento son aplicadas a los centros
geométricos de cada diafragma rígido de piso. Para moldear sistemas de multi-torres,
puede aplicarse uno o más diafragmas de piso rígido a un solo piso.

Las cargas sísmicas son calculadas desde la distribución de la masa del piso sobre la
estructura, usando coeficientes dependientes del código y periodos fundamentales de
vibración.

Cargas laterales de viento y Sísmicas 4 - 3

<!-- p. 37 -->

Welcome to ETABS

Para sistemas de pisos semi-rígidos existen numerosos puntos de masa, ETABS
tiene una carga especial dependiente del Ritz-vector un algoritmo para el
cálculo rápido de los periodos de tiempo predominantes. Las cargas sísmicas
son aplicadas a las ubicaciones donde son generadas las fuerzas de la inercia
y no tienen que estar en los niveles de piso solamente. De forma adicional,
para sistemas de pisos semi-rígidos, las cargas de la inercia son distribuidas
especialmente a través de la extensión horizontal de la proporción del piso a
la distribución de la masa, además de capturar de forma exacta las fuerzas
constantes generadas a través de los diafragmas del piso.

ETABS tiene también una amplia variedad de opciones de Análisis
Dinámico, que varían desde la respuesta básica del análisis del espectro
hasta una deformación no lineal del análisis de Time History. La respuesta
de las curvas del espectro que dependen del código se construyen dentro del
sistema, y son cambiadas a un análisis dinámico usualmente trivial después
de que se ha creado el modelo básico.

Modelado de Panel de Zona
Estudios han demostrado que no tomar en cuenta la deformación sin un
panel de zona barra-columna en el modelo puede causar una discrepancia
significante entre los resultados analíticos del comportamiento físico del
edificio. ETABS permite la explicita incorporación del comportamiento del
panel de zona constante que se cree que a cualquier hora tiene un
considerable impacto en la deformación de la conexión viga-a-columna.

Matemáticamente, la deformación del panel de zona es moldeado usando los
resortes agregados a los cuerpos rígidos geométricamente del tamaño del
panel de zona. ETABS permite la asignación del panel de zona “propiedad”
a un objeto punto a la intersección de la viga-columna. Las propiedades del
panel de zona pueden determinarse de alguna de las siguientes formas:

• Automáticamente por el programa desde las propiedades elásticas
de la columna.

• Automáticamente por el programa desde las propiedades elásticas
de la columna en combinación con cualquier placa doble que se
presenten..

• Valores de resortes especificados por el usuario

4 - 4 Modelado del Panel de Zona

<!-- p. 38 -->

Chapter 4 - ETABS Modeling Techniques

\~ Propiedades de conexión especificadas por el usuario (Users-specified
link properties), en cuyo compartimiento es posible tener un
comportamiento de panel del zona si se ejecuta un análisis no lineal
de Time History.

Reducción de la Carga Viva
Ciertos códigos de diseño permiten reducir las cargas vivas basadas en el área
que esta siendo soportada por un miembro en particular. ETABS permite que
sean reducidas las cargas vivas usadas en los post-procesadores del diseño
(no en el análisis) para los objetos línea (columnas, vigas, soportes, y así
sucesivamente) y para los objetos del tipo muro (objetos área con una
propiedad de definición de muro). El programa no permite la reducción de
las cargas vivas para los objetos del tipo piso.

ETABS ofrece un número de opciones para reducciones de carga viva, y
algunos métodos pueden tener sus factores de carga reducida (RLLF) sujetos
a dos mínimos. Un mínimo aplica a miembros recibiendo carga desde
múltiples niveles. El programa provee de valores predeterminados para esos
mínimos, pero el usuario puede hacerles correcciones. Es importante que
note que las cargas vivas son reducidas solo en los post-procesos de diseño;
las cargas vivas nunca son reducidas en la salida de datos del análisis básico.

Modelado de piso Rígido y Semi-rígido
ETABS ofrece tres opciones básicas para el Modelado de varios tipos de
sistemas de piso. Los diafragmas de piso pueden ser rígidos o semi-rígidos
(flexible), o el usuario puede optar por especificar que no hay diafragma
alguno.

En el compartimiento de los modelos de diafragma rígidos, cada placa del
piso se asume que se traduce en el plano y gira sobre una coordenada
vertical como un cuerpo rígido, se asume de forma básica que no hay
deformaciones dentro del plano en a placa del piso. El concepto de diafragmas
de piso rígido para edificios se ha venido usado a través de muchos años como
un medio para dar mayor eficacia de cómputo a la solución del proceso.
Debido al número reducido de grados de libertad asociados con el diafragma
rígido, esta técnica ha probado ser muy efectiva, especialmente para los
análisis que involucran estructuras dinámicas. Sin embargo, la desventaja de
tal avance es que la solución no produce ninguna información en las
tensiones constantes del diafragma, ni recobra ninguna fuerza de coordenada
horizontal en los miembros que descansan en el plano de los pisos.

Reducción de la Carga Viva 4 - 5

<!-- p. 39 -->

Welcome to ETABS

Esas limitaciones pueden tener un efecto significativo en los resultados que
reportan las estructuras soportadas por barras y en los edificios diafragmas
con problemas de flexibilidad, entre otros. Debajo de la influencia de cargas
laterales, tensiones constantes significativas pueden generarse en los
sistemas de pisos, y por ende, es importante que las placas del piso sean
moldeadas como diafragmas semi-rígidos para que las deformaciones del
diafragma se incluyan en el análisis, y las fuerzas de los ejes sean recobradas
en las vigas/puntal apoyando los pisos.

Por suerte, con ETABS es un proceso fácil el moldear el comportamiento
del diafragma semi-rígido, hacer el cambio entre comportamiento rígido y
semi-rígido para estudios paramétricos. De hecho, ETABS, con estas
eficientes técnicas de resolución numérica y acercamientos basados en
objetos miembros, hacen notar el uso de un diafragma rígido ya no sea
pertinente por las razones que originalmente justificaban su uso.

El acercamiento de ETABS basado en el objeto permite el Modelado
automático de diafragmas de pisos semi-rígidos, cada placa de piso siendo
esencialmente un objeto piso. Los objetos con propiedades de aperturas
pueden ponerse sobre objetos del piso para “hacer” hoyos en el sistema del
piso. La conversión de los objetos del piso y sus aberturas respectivas en los
elementos finitos para el modelo de análisis es automático para los tipos mas
comunes de sistemas de pisos, llámense losas de concreto, sistemas de
tableros metálicas y tarimas de concreto, las cuales se usan en
comportamientos de membranas en-plano (ver las cargas verticales
anteriores Vertical Load Transfer section). Para otros tipos de sistemas de
pisos, el usuario debe asignar los parámetros de división interna a los objetos
del piso, teniendo en mente que para los efectos de la deformación del
diafragma deben ser capturados con exactitud, la división interna “mesh” no
necesita se redefinida también.

Compulsión de Líneas
Parte de lo que hace que el Modelado tradicional de elementos finitos tome
tanto tiempo es el crear una división interna apropiada en la zona de
transición de objetos adyacentes cuyas divisiones internas no corresponden.
Esto es muy común, y casi siempre sucede en la interfase entre muros y
pisos. Los programas para fines generales históricamente han tenido
dificultades con las transiciones de divisiones internas entre muros
curveados y pisos, y entre muros y rampas inclinadas.

4 - 6 Compulsión de Líneas

<!-- p. 40 -->

Chapter 4 - ETABS Modeling Techniques

Sin embargo, en ETABS, la compatibilidad de la división interna de
elementos entre objetos adyacentes se refuerza automáticamente vía
compulsión de líneas que eliminan la necesidad de preocupación del usuario
sobre las transiciones de división interna. Estos desplazamientos que se
interpolan en la compulsión de las líneas son creadas automáticamente como
parte del elemento finito del modelo analítico. (De forma completamente
interna por el programa) en las intersecciones los objetos que contienen
geometrías que no corresponden son re-descubiertas. Así, de forma similar a
la creación de los elementos finitos como un todo, los usuarios de ETABS no
necesitan preocuparse sobre la compatibilidad de la división interna.

Modificadores
ETABS permite asignar los factores de modificación tanto a objetos línea
como a objetos área. Para objetos línea, los modificadores de las
propiedades de la barra son multiplicados para obtener las propiedades del
análisis final de la sección usada para los elementos de la barra. Para objetos
área, modificadores de rigidez de shell se multiplican las veces del análisis
de la rigidez del elemento shell calculado desde una propiedad de la sección
especificada. Ambos de esos modificadores afectan solo el análisis de
propiedades. Ellos no afectan ninguna de las propiedades del diseño.

Los modificadores pueden ser usados para limitar la forma en que se
comportan los elementos del análisis. Por ello, asuma que usted tiene una
losa de concreto apoyada en una armadura de acero, pero no quiere que la
losa actué como un reborde de la armadura; todas las fuerzas de los rebordes
deben ser cargadas por la parte superior de la armadura. Usando un
modificador de un objeto área, puede forzar la losa de concreto para actuar de
forma constante, de tal modo, remover el comportamiento de las
coordenadas en-plano del concreto para que no contribuya ninguna fuerza o
rigidez en la dirección vertical de la armadura. En otros ejemplos se usan
modificadores para beneficiar el Modelado de las secciones del concreto
donde es necesario reducir las propiedades de la sección debido al
rompimiento, o cuando se moldea el comportamiento del diafragma lateral,
entonces los objetos del piso son constantes, con las fuerzas de inclinación
subsecuentes que se cargan directamente a la cuerda del diafragma.

Modificadores 4 - 7

<!-- p. 41 -->

Welcome to ETABS

Construcción de la Secuencia de Carga
Se asume en la mayoría de los programas de análisis que la estructura no se
sujeta a ninguna carga hasta que esta totalmente construida. Esto es
probablemente razonable para cargas vivas, de viento y sísmicas, así como
para otras cargas súper impuestas. Sin embrago, en realidad la carga muerta
de la estructura esta siendo continuamente aplicada mientras se construye la
estructura. En otras palabras, los pisos inferiores de un edificio ya están siendo
tensados con la carga muerta de los pisos inferiores a ellos antes de que los
pisos superiores sean construidos. Los ingenieros ya han sido advertidos de la
inexactitud de los resultados analíticos de la forma de los momentos no
reales de la viga en los pisos superiores del edificio porque se asume la
apariencia de la carga muerta después de que la estructura ha sido
construida.

En muchos casos, especialmente en los edificios más altos debido al efecto
acumulativo, los resultados analíticos de la estructura final pueden ser
alterados por la secuencia de la construcción del edificio. Situaciones que
son sensibles a los efectos de la secuencia de la construcción incluida, entre
otros, los edificios con deformaciones de coordenadas diferenciales,
transferencia de vigas maestras que envuelven refuerzos temporales y
estructuras apuntaladas donde los segmentos del apoyo son construidos y
cargados mientras otros segmentos siguen siendo instalados.

ETABS tiene una opción con la que el usuario puede activar el incremento
automático de piso-a-piso la secuencia de la carga de construcción para una
compartimiento de carga particular. Este procedimiento debe cargar la
estructura mientras ésta es construida. Típicamente, usted puede hacer esto
para el compartimiento de la carga muerta y usar los resultados analíticos de la
carga de la secuencia de la construcción en combinación con otros
compartimientos de carga para la fase en diseño.

Optimización del Diseño y Precisión de la barra de
Acero
Los diversos códigos de algoritmos de diseño para la selección de la barra, revisión
de tensión y optimización de precisión involucra el calculo de la capacidad de
inclinación de la(s) coordenada(s) de un miembro, la definición de una combinación
de carga dependiente de un código, evaluar los factores K, longitudes sin apoyo y
efectos de segundo orden, magnificaciones de momento, y uso de factores para
determinar la aceptabilidad.

4 - 8 Construcción de la secuencia de carga

<!-- p. 42 -->

Chapter 4 - ETABS Modeling Techniques

Puede generar exhibiciones de diagramas de energía que demuestren la
distribución de energía por unidad de volumen para los miembros a través
de la estructura. Dichas exhibiciones ayudan a identificar los miembros que
contribuyen de mayor forma en precisión la resistencia bajo la influencia de
cargas laterales. Para el control de la precisión, crecen las medidas de los
miembros que producirán el uso más eficiente del material agregado.

Junto a las mismas líneas, ETABS ofrece un proceso automático de
optimización del tamaño del miembro para control lateral precisión basado en
los blancos laterales precisión que usted haya especificado para cualquier serie
de puntos en diversos pisos. La optimización precisión se basa en el método de
energía descrito aquí, por el que el programa incrementa el tamaño de los
miembros de forma proporcional a la cantidad de energía por unidad de
volumen calculado para un compartimiento de carga particular.

Más Información
Este capitulo pretendió ilustrar algunas de las técnicas que ETABS provee
para el eficiente Modelado de sistemas y comportamientos típicamente
asociados con la estructuras del edificio. Información adicional puede ser
encontrada en la Ayuda on-line disponible en la interfase grafica del usuario
de ETABS, incluyendo las notas técnicas (Technical Notes) que describen
algoritmos de diseño especificados por el código. Esos documentos están
disponibles en formato de Adobe Acrobat PDF en el CD de ETABS, y
puede tener acceso a ellos desde el programa usando el menú de ayuda Help
menu. Además, están disponibles las series de videos “Watch & Learn”
disponible en la pagina web de la empresa CSI’s www.csiberkeley.com.

Más Información 4 - 9

<!-- p. 43 -->

Capitulo 5

Técnicas de análisis de ETABS

Este capitulo provee una vista rápida de algunas de las técnicas de análisis disponibles
en ETABS. Los tipos de análisis descritos son análisis lineales estáticos, análisis modal,
análisis de respuesta del espectro, análisis de Time History, análisis P-Delta y no lineal.

En un análisis ejecutado, usted puede solicitar un análisis P-Delta inicial, un
El Manual del análisis modal, y múltiples compartimientos de linear estático, respuesta del
Software de espectro, y un análisis de Time History. Los múltiples compartimientos deverificación
análisis estáticos de no lineares pueden ser definidos; estos se ejecutan dede los
forma separada a los otros análisis de compartimientos.documentos y
análisis de
ETABS
Analisis estático Lineal
Un análisis estático lineal se ejecuta automáticamente para cada compartimiento de
carga estática que se define. Los resultados de los diferentes compartimientos de
carga pueden combinarse con los demás u cualquier otro análisis de
compartimiento de carga linear, tales como el análisis de respuesta de espectros.

Analisis Estático Linear 5 - 1

<!-- p. 44 -->

Welcome to ETABS

La geometría y no-linealidad del material no son consideradas en el análisis
linear estático, excepto que el efecto del análisis P-Delta inicial que se
incluye en cada compartimiento de carga estática. Por ejemplo, usted define
un análisis inicial P-Delta para carga de gravedad, las deflexiones y
momentos se incrementaran para los compartimientos de cargas laterales
estáticas.

Los compartimientos de carga lineares estáticos pueden ser combinados aun
cuando se ha ejecutado un análisis inicial P-Delta, porque la carga inicial P-
Delta es la misma para todas las cargas estáticas y compartimientos de
respuesta de espectros.

Analisis Modal
Este análisis calcula los modos de vibración para la estructura basado en la
rigidez de los elementos y masas presentes. Esos modos pueden usarse para
investigar el comportamiento de la estructura, y son requeridos como una
base para los análisis subsecuentes de respuesta del espectro y Time History.

Se encuentran disponibles dos tipos de análisis: análisis del vector propio y
análisis del vector Ritz. Only one type can be used in a single analysis run.

Fuente de Masa
Para calcular los modos de vibración, un modelo debe contener masa. La
Masa debe ser determinada y asignada en ETABS usando alguno de los
siguientes:

• ETABS determina la masa del edificio en las bases de la masa del
propio objeto (definido en la tarea de las propiedades) y cualquier
masa adicional que usted especifique. Esta es la funcion
predeterminada.

• ETABS determina la masa desde la combinación de carga que
usted especifique.

• ETABS determina la masa basándose en las propias masas,
cualquier masa adicional que haya asignado, y cualquier
combinación que especifique, que es una combinación de las
primeras dos opciones.

Típicamente, las masas se definen en todos los seis grados de libertad. Sin
embargo, ETABS tiene la opción de permitir solamente asignar la masa

5 - 2 Modal Analysis

<!-- p. 45 -->

Chapter 5 - ETABS Analysis Techniques

Transnacional global en las coordenadas de las direcciones X y Y y asignar
masa rotacional o momentos de inercia sobre la coordenada global Z para
que se considere en el análisis. Esta opción es útil cuando las cargas
verticales dinámicas no se consideran en el modelo. Además, existe la
opción de para todas las cargas laterales que no ocurren en un nivel de piso
para ser agrupados en el nivel de piso superior y en el piso debajo de la
ubicación de la masa. Ese acercamiento es usado primordialmente para
eliminar los comportamientos dinámicos fuera-de-plano que no hayan sido
intentados en muros que se conectan entre niveles de piso.

Análisis de Vector Propio
El análisis del modo de vibrar o valor vibratorio (Eigenvector/eigenvalue)
determina el modo de las figuras libres de vibraciones y no
amortiguamiento y las frecuencias del sistema. Esos modos naturales
permiten penetrar en el comportamiento de la estructura. Pueden también ser
usadas como bases en los análisis de respuesta del espectro o en el de
historia del tiempo, aunque los vectores son muy recomendados para dichos
propósitos

Los modos del vector propio se identifican por números del 1 a n en el orden
de modos que se encuentran en el programa Específicamente el numero de
modos, N, a ser encontrado, y el programa encontrara los modos de la
frecuencia menor para N (N-lowest frequency) (periodo mas largo).

El valor propio es el cuadrado de la frecuencia circular. El usuario especifica
una frecuencia cíclica (circular frequency/(2~)) rango en el cual se buscaran
los modos. Dichos modos se encuentran en el orden en el que se incrementa
la frecuencia, y aunque se empiece del valor cero es apropiado para la mayoría de
los análisis dinámicos, ETABS permite al usuario especificar una frecuencia de
inicio “shift frequency”; esta puede ser útil cuando su edificio esta sujeto a
frecuencias mayores de entrada, tales como maquinaria vibratoria.

ETABS también ofrece una opción para calcular la masa-residual o masa perdida
(missingmass) modos para análisis-propios. En este sentido, ETABS trata de
aproximar los comportamientos de alta-frecuencia cuando la participación de la
masa-radio para una carga a la que se le da un dirección de aceleración menor que el
100%.

Análisis del Vector Ritz
ETABS ofrece la habilitación del uso de la sofisticada técnica del Vector Ritz para
el análisis modal. Algunos estudios han indicado que el modo de las figuras libres
de vibración no es la mejor base para un análisis de super-posición de estructuras
sujetas a cargas dinámicas.

Modal Analysis 5 - 3

<!-- p. 46 -->

Welcome to ETABS

Se ha demostrado que los análisis dinámicos basados en cargas dependientes
de vectores Ritz generan resultados mas precisos que con el uso de números
con las figuras del vector propio o valores propios.

Los vectores Ritz dan excelentes resultados porque son generados tomando
en consideración la distribución espacial de las cargas dinámicas. El uso
directo de las figuras naturales niega su información importante.

Cada modo del Vector Ritz consiste en un modo de figura y una frecuencia.
Cuando un número suficiente de modos de vectores Ritz es encontrado,
algunos de ellos se aproximan a los modos de figuras naturales y a las
frecuencias. En general, sin embargo, los modos del vector Ritz no
representan características intrínsecas de la estructura en la misma forma en
que lo hacen los modos naturales, porque se basan en los vectores de inicio
de carga.

De forma similar a los modos naturales, especifique el número de modos
Ritz a encontrar. Además, especifique los vectores de carga de inicio, que
deben ser las cargas de aceleración, compartimientos de cargas estáticas, o
deformación de cargas no lineales.

Análisis de Respuesta de Espectros
Para este análisis, la aceleración del suelo por terremoto en cada dirección se
da como una respuesta curva del espectro, la respuesta de aceleración
espectral contra el periodo de la estructura. Este acercamiento busca
determinar la respuesta mas parecida en lugar de buscar la historia completa
del tiempo.

ETABS ejecuta la respuesta del análisis de espectros usando el modo de
súper-posición o se pueden usar también el vectores propio o el vector Ritz.
Los vectores Ritz son recomendados típicamente debido a que dan resultados
mas exactos para el mismo numero de modos.

Aunque la respuesta de las curvas del espectro se especifican en tres
direcciones, solo se produce un solo resultado positivo, por cada repuesta de
cantidad. Esta respuesta cuantifica lo que pueden ser desplazamientos,
fuerzas, o tensiones. Cada resultado computado representa una medida
estadística de la magnitud máxima más similar para esa respuesta de
cantidad. Los resultados se reportan como positivos, la respuesta actual
puede variar dentro de un rango que va desde su valor positivo hasta su valor
negativo correspondiente.

5 - 4 Análisis de la Respuesta del Espectro

<!-- p. 47 -->

Chapter 5 - ETABS Analysis Techniques

Análisis de Time History
Es usado para determinar la respuesta dinámica de una estructura a una
carga arbitraria. ETABS pueden completar cualquier número de
compartimientos de Time History en una ejecución sencilla del programa.
Cada compartimiento puede diferir en la carga que se le aplica y el tipo de
análisis que se le ejecuta. Hay tres tipos de análisis de Time History
disponibles:

• Linear Tansitorio (Linear transient): La estructura empieza con
cero condiciones iniciales o con las condiciones al final de un
compartimiento linear de Time History especificado por el usuario.
Se asume que todos los elementos se comportan de forma linear
para la duración del análisis.

• Periódico (Periodic): Las condiciones iniciales se ajustan para que
sean iguales a aquellas en el final del periodo de análisis. Se asume
que todos los elementos tienen un comportamiento linear para la
duración del análisis.

• No-linear transitorio (Nonlinear transient): La estructura
empieza de condiciones iniciales cero o con las condiciones que
tenía al final del compartimiento no linear de la historia del tiempo
especificada por el usuario. Los elementos de conexión pueden
exhibir comportamientos no lineares durante el análisis. Todos los
demás elementos se comportan de forma linear.

El modo estándar de súper posición del método de respuesta del análisis es
usado por el programa para resolver el equilibrio dinámico de las ecuaciones
del movimiento de la estructura completa. Los modos usados pueden ser el
vector propio o las cargas dependientes de los modos del vector Ritz, y el
amortiguamiento en la estructura se moldea usando el amortiguamiento
modal, también conocido como clásico o proporcional. Los vectores Ritz
deben usarse al ejecutar el análisis no linear de Time History con la
deformación de las cargas de conexión no-lineares como vectores de inicio.

Análisis de Time History 5 - 5

<!-- p. 48 -->

Welcome to ETABS

Análisis no-linear de Time History
El método del análisis no linear de Time History es usado en ETABS como
una extensión del método Análisis No-linear Veloz (Fast Nonlinear Análisis)
(FNA). Este método es extremadamente eficiente y es usado para sistemas
estructurales que son primariamente lineares y estáticos, pero los cuales
tienen un número limitado o predefinido de elementos no lineares, tales
como edificios con aislantes amortiguadores. En ETABS, la no-linealidad se
restringe a los elementos de conexión.

El método FNA es altamente exacto cuando se usa con los modos
apropiados de modo de vibrar en vectores Ritz, y tiene ventajas sobre los
métodos tradicionales de pasos-por tiempo, en términos de velocidad, y
control sobre amortiguamiento y modos de efectos más altos.

Analisis Inicial P-Delta
Esta opción enumera los efectos de grandes cargas compresoras o de tensión
sobre la rigidez transversal de los miembros de la estructura. La Compresión
reduce la rigidez lateral, y la tensión la incrementa. Este es un tipo de
geometría no lineal conocida como el efecto P-Delta. Esta opción es
particularmente útil para considerar el efecto de las cargas de gravedad sobre la
rigidez lateral de las estructuras del edificio, como se requiere con ciertos
códigos.

El análisis inicial P-Delta en ETABS considera el efecto P-Delta de un solo
estado de carga sobre la estructura. Especifica la carga usando alguno de los
siguientes métodos:

• Como una combinación especifica de compartimientos de carga; a
esto se le llama la combinación de carga P-Delta. Por ejemplo, esto
puede ser la suma del compartimiento de la carga muerta más la
fracción de un compartimiento de carga muerta. Este acercamiento
requiere de una solución iterativa para determinar el efecto P-Delta
sobre la estructura.

• Como una carga de piso-a piso sobre la estructura computada
automáticamente desde la masa de cada nivel. Este acercamiento
es aproximado, pero no requiere una solución iterativa.

Cuando usted solicita un análisis inicial P-Delta, se ejecuta antes de ejecutar
todos los análisis; lineal-estático, moda, de respuesta del espectro, y análisis
de Time History. El análisis P-Delta no tiene efecto en los análisis no
lineales.

5 - 6 Análisis Inicial P-Delta

<!-- p. 49 -->

Chapter 5 - ETABS Analysis Techniques

El análisis inicial P-Delta modifica esencialmente las características de la
estructura, afectando los resultados de todos los análisis subsecuentes que se
ejecuten. Porque la carga que causa el efecto P-Delta es siempre la misma que
genera los compartimientos de análisis lineales, sus resultados pueden súper
ponerse en las combinaciones de carga.

El análisis inicial P-Delta puede también ser usado par estimar cargas de
pandeo en el edificio al ejecutar una serie de análisis, cada vez
incrementando la magnitud de la combinación de la carga P-Delta, hasta que
se detecta el pandeo (si el programa detecta que ha ocurrido, el análisis
termina y no produce resultados). Las contribuciones relativas para cada
compartimiento de carga estático de la combinación P-Delta deben continuar
igual, incrementando todos los factores escala por el mismo porcentaje entre
ejecuciones.

En conclusión, los códigos del edifico reconocen típicamente, dos tipos de
efectos P-Delta: el primero causado por el sacudimiento total de la estructura
y el segundo que resulta de la deformación de un miembro entre sus bordes
finales. ETABS puede moldear ambos comportamientos. Se recomienda que
la opción del análisis inicial P-Delta se use en un análisis de sacudimiento
total de la estructura aplicable a los factores del código de magnificación
momentánea del edificio para que se usen en el análisis de la deformación
de un miembro entre sus bordes finales. El post proceso de diseño en
ETABS opera de este modo.

Analisis No-lineal Estático
Este análisis de ETABS ofrece una variedad de capacidades, incluyendo:

• No linealidad Material en vigas y columnas.

• Hueco, Gancho o unión no lineal y comportamiento de

plasticidad en conexiones.

• No linealidades geométricas, incluyendo deflexiones

grandes y efectos P-Delta.

• Análisis de Incremento de Construcción.

• Análisis de pushover estático.

Analisis no-lineal estatico 5 - 7

<!-- p. 50 -->

Welcome to ETABS

Pueden definirse análisis estáticos no lineales múltiples. Cada
compartimiento de análisis considera un patrón simple de
carga, especificada como una combinación lineal de
compartimientos de carga, las cargas de aceleración, y el modo
de vibración de figuras. Las cargas son aplicadas
incrementándolas dentro del análisis del compartimiento.

El patrón de carga puede ser aplicado debajo de una carga o
control de desplazamiento. El control de la carga es usado para
aplicar una magnitud de carga, tal como se requiere en la carga
de gravedad en un análisis de incremento de construcción. El
control del desplazamiento aplica la carga con una magnitud
variable para alcanzar el desplazamiento específico, como se
necesitaría en el análisis de pushover.

El análisis estático no lineal es independiente de todos los
demás compartimientos de análisis, excepto los modos de
figuras calculadas previamente para definir el patrón de carga.

Más Información
Este capitulo provee una introducción general de las técnicas
primarias analíticas que ETABS ofrece para análisis lineal y no
lineal de edificios. Información Adicional puede encontrarse en
el software denominado Software Verification Manual y en la
ayuda on-line disponible en la interfase grafica del usuario de
ETABS, incluyendo las notas técnicas Technical Notes que
describen los algoritmos de diseño de código-especifico. Esos
documentos están disponibles en el formato Adobe Acrobat
PDF en el CD de ETABS, y puede accesarse a ella desde el
menú de ayuda del programa Help menu. Además, las series de
videos “Watch & Learn” están disponibles en la pagina de la
empresa CSI’s www.csiberkeley.com.

5 - 8 More Information

<!-- p. 51 -->

ETABS®
Software de Diseño Integral para Edificaciones
Guía de Introducción para el usuario.

Computers and Structures, Inc. Version 9

Berkeley, California, USA November 2005

<!-- p. 52 -->

Derechos Reservados

El programa de computación ETABS y toda la documentación asociada con el mismo
constituyen propiedad intelectual y derechos reservados. Mundialmente, los derechos de
propiedad recaen a favor de Computers and Structures, Inc. Queda prohibido el uso o
reproducción, de éste documento en cualquiera de sus formas, sin la previa autorización por
escrito de Computers and Structures, Inc.
Por otra parte, la información y copias relativas a la presente documentación
deberán obtenerse de:
Computers and Structures, Inc.
1995 University Avenue
Berkeley, California 94704 USA

Teléfono: (510) 845-2177
FAX: (510) 845-4096
e-mail: info@csiberkeley.com (Información general)
e-mail: support@csiberkeley.com (Soporte técnico)
Página web: www.csiberkeley.com

\~ Copyright Computers and Structures, Inc., 1978-2005.
El Logo CSI es una marca registrada de Computers and Structures, Inc.
ETABS es u na marca registrada de Computers and Structures, Inc.
Windows es una marca registrada de Microsoft Corporation.
Adobe and Acrobat son marcas registradas de Adobe Systems Incorporated.

<!-- p. 53 -->

ADVERTENCIA

SE HAN INVERTIDO TIEMPO CONSIDERABLE, ESFUERZO Y GASTOS HACIA EL
DESARROLLO Y DOCUMENTACION DE ETABS. EL PROGRAMA HA SIDO
PROBADO Y USADO DETENIDAMENTE. DE CUALQUIER MODO, AL HACER
USO DEL PROGRAMA, EL USUARIO ACEPTA Y ENTIENDE QUE NO EXISTE
GARANTIA IMPLICITA DE LOS DESARROLLADORES O DISTRIBUIDORES EN
LA PRECISION O CONFABILIDAD DEL PROGRAMA.

EL USUARIO DEBE ENTENDER EXPLICITAMENTE LOS SUPUESTOS DEL PROGRAMA
Y DEBE VERIFICAR LOS RESULTADOS DE FORMA INDEPENDIENTE.

<!-- p. 54 -->

Contenido

Guía de de Introducción para el usuario.
1 Descripción del Programa.

2 ETABS “Screen”

3 Formas Básicas, Herramientas de Dibujo,
Apuntadores del Mouse.

4 Inicio del modelo.

5 Creación de un Modelo Estructural.

6 Selección de Objetos Estructurales.

7 Ingreso del Modelo Estructural.

8 Asignación/Cambio de Propiedades.

9 Edición del modelo Geométrico.

10 Análisis del Modelo.

11 Diseño.

12 Representación Gráfica

13 Generando Resultados

Guía de Introducción para el Usuario Contenido - 1

<!-- p. 55 -->

1

Capítulo 1

Descripción del Programa

Objetivo
Este capitulo describe brevemente el programa y algunos de los conceptos
involucrados en su uso.

Esto es ETABS

ETABS es un poderoso programa que engrandece el trabajo de análisis y diseño

que realiza el ingeniero sobre las aptitudes de las estructuras. Parte de dicho

poder radica en poder ordenar las opciones y figuras. La otra parte radica en

lo simple que es su uso.

La propuesta básica del uso del programa es muy directo. El usuario establece las

líneas de rejilla, y ubica objetos estructurales con respecto a las líneas de rejilla

usando puntos, líneas áreas, y asigna cargas y características estructurales a esos

objetos estructurales (por ejemplo, a un objeto de la línea se puede asignar

Objetivo 1 - 1

<!-- p. 56 -->

características de la sección; a un objeto del punto se le puede asignar

características del resorte; a un objeto del área se le pueden asignar

características de la losa o de la cubierta). El análisis y el diseño, entonces, son

realizados en base a los objetos estructurales y sus posiciones.

<!-- p. 57 -->

Guía de Introducción para el Usuario.

Los resultados se generan en forma gráfica o tabular y pueden ser enviados
1 a una impresora para ser impresos o almacenados en un archivo para ser
usados en otros programas.

Mediante el uso del programa, se puede manejar el Archivo (File),
Edición (Edit), el Modelo del Menú de ETABS, cambiar las vistas Ver
(View), Definir (Define) las opciones de Propiedades o Cargando,
Comandos:
Dibujar algo nuevo en el modelo, Seleccionar algo, -File (Archivo)
Asignar propiedades o cargas, Analizar el modelo, ~ Edit (Edicion)
Representar los resultados del análisis para revisarlos, ~ View (Ver)
Diseñar la estructura, aplicar varias Opciones para alcanzar ~ Define (Definir)
el resultado deseado con optimo esfuerzo, y buscar Ayuda ~ Draw (Dibujar)
cuando la necesite. Esas acciones son las bases para la ~ Select(Seleccionar)
estructura del Menú del programa. Es por ello, que la ~ Assign (Asignar)
familiaridad con los comandos del menú y sus funciones -Analyze (Analizar)
son la llave para la expandir su habilidad para usar ETABS.
• Display
(Exhibir)
Note: • Design
(Diseño) El manual
• Options de
(Opciones) verificación
del • Help
programa (Ayuda)
ETABS
documenta La información sobre los diversos artículos del Menú esta disponible usando el
los análisis Menú de Ayuda > en el comando Search for Help, así como usando la tecla F1
usando jugado en la pantalla de ETABS. La tecla F1 exhibirá ayuda sensible del
ETABS. contexto, incluyendo las descripciones de los tipos de entrada para las formas
usadas en el programa. La familiaridad con los comandos de menú permitirá al
usuario crear los modelos para los sistemas de división del piso compuesto
complejo con aberturas y sus proyecciones, los sistemas de acero de las vigas, los
marcos que resisten el momento, los sistemas complejos de la pared del carga, los
pisos rígidos y flexibles, las azoteas inclinadas, las rampas y las estructuras de
estacionamiento, los entrepisos, los sistemas de unión, los múltiples edificios de
torres y los sistemas de paso del diafragma, y muchos más.

Las notas técnicas en formato del pdf están disponibles en el Menú de Ayuda > y
en comando de Documentación y Clases particulares.

1 - 2 Esto es ETABS

<!-- p. 58 -->

Esas notas explican cómo el programa realiza el diseño del marco de
concreto, el diseño del marco de acero, el diseño compuesto del piso, el
diseño de la vigueta de acero, y el diseño concreto del esquileo de la pared
de acuerdo a los códigos aplicables de edificación.

<!-- p. 59 -->

Capítulo 1 - Descripción del Programa

Opciones para ahorro de tiempo 1
El programa incluye también opciones que le permiten reducir el tiempo
que se invierte en la creación de modelos. Entre esas opciones se incluyen
las siguientes:

• Pisos Similares (Similar Stories). Permite al usuario hacer cambios a
múltiples pisos de forma simultanea.

• Snap To (Adjuntar) Permite al usuario colocar elementos estructurales

con precisión.

• Seleccionar secciones Automáticamente (Auto Select Sections).
Permite al usuario definir una lista de secciones, por ejemplo W18X35,
W18X40, W21X44, W21X50 y W24X55, que pueden ser asignadas a
una pieza del armazón. El programa puede seleccionar automáticamente
la opción mas económica, adecuar la sección o miembro desde la opción
de la lista de seleccionado automático cuando esta siendo diseñada la
pieza.

• Transferencia de carga vertical. Vertical Load Transfer. Libera al
usuario de la tarea de calcular la carga en las secciones o miembros que
soportaran la placa del suelo, y determinar el área tributaria a cada
sección o miembro para una reducción real en la carga.

Plantillas y Predeterminados
ETABS proporciona un número de plantillas que permiten la generación
rápida de los modelos para una amplia gama de edificios comunes. Esas
plantillas sirven como buen punto de partida porque pueden ser modificadas
fácilmente.

El programa también incluye las plantillas para los marcos bidimensiones y
tridimensionales que se pueden añadir a un modelo existente. La opción
bidimensional se puede utilizar para localizar marcos planares a través de un
modelo. La opción tridimensional puede asistir al usuario en las condiciones
de modelado donde varias torres reposan sobre la misma estructura base.

El programa incluye parámetros predeterminados, muchos de los cuales son
específicos de códigos de construcción. Se puede accesar a esos parámetros

Opciones para el ahorro de tiempo 1 - 3

<!-- p. 60 -->

por defecto con las opciones de "Overwrites" y las "Preferences." Las
posibles opciones disponibles para sobreescribir (overwrites) y los valores
prefijados para las preferencias (preferences) se identifican en los manuales
del diseño.

Usando las plantillas y los defectos incorporados, el usuario puede crear un
modelo en cuestión de minutos.

<!-- p. 61 -->

Guía de Introducción para el usuario

1
Proceso Básico
A continuación se proporciona una amplia descripción de los procesos básicos
de modelo, análisis y diseño:

\1. Establecer unidades.

\2. Abrir un archivo.

\3. Establecer las líneas de la cuadricula.

\4. Definir los niveles de los pisos.

\5. Dibujar objetos estructurales.

\6. Definir las propiedades del armazón

(marcos).

\7. Definir las cargas.

\8. Editar el modelo geométrico.

\9. Asignar las propiedades.

\10. Ver el modelo.

\11. Análisis del modelo.

\12. Mostrar resultados para revisión.

\13. Diseño del modelo.

\14. Generar la salida del modelo.

\15. Guardar el modelo.

Formas

Diversas formas se utilizan en ETABS a través de los procesos de modelado,
análisis y diseño. Con una forma exhibida en la ventana de ETABS, presione
la tecla F1 en su teclado para tener acceso a la ayuda sensible al contexto para
la forma.

1 - 4 Proceso Básico

<!-- p. 62 -->

2

Capítulo 2

ETABS “Pantalla” (screen)

Objetivo
Este capítulo describe brevemente la “pantalla” de ETABS y de forma mas
precisa, la interfaz de uso grafico.

La ventana de ETABS
La interfase grafica del usuario de ETABS que se muestra en la Figura 2-1
incluye la ventana principal, barra principal, barra de exhibición de titulo,
barra de menú, barra de Herramientas, ventanas de exhibiciones, barra de
estado, coordinar la posición del apuntador del mouse y las unidades en uso.
Cada uno de estos elementos se describe en la lista enumerada que se presenta a
continuación.

\~ Ventana Principal (Main Window). Esta ventana se puede mover,
cambiar su tamaño, maximizar, minimizar, o cerrar usando las
operaciones estándares de Windows. Refiérase a la ayuda de Windows,
disponible en el menú de inicio, para la información adicional sobre esos
artículos.

Objetivo 2 - 1

<!-- p. 63 -->

Guía de Introducción para el usuario

2

Plan View Drawing and
Assignments Options

(Similar Stories Feature)

Figura 2-1: La interfase grafica de ETABS para el usuario

• Barra Principal (Main Title Bar). Esta barra incluye el
programa y los nombres de los modelos. La barra principal esta
resaltada cuando el programa esta en uso. La ventana principal
puede moverse dando click izquierdo al mouse en la barra
principal y sosteniendo el botón del mouse mientras se arrastra
la ventana por la pantalla.

• Barra del Menú. La barra del menú contiene todos los menús
del programa.

• Barras de herramientas y Botones (Toolbars and Buttons). La barra
de herramientas esta compuesta de botones. Estos botones proporcionan

2 - 2 La ventana de ETABS

<!-- p. 64 -->

acceso a los comandos mas usados a través de “un-click”. Manteniendo
el cursor del mouse posicionado sobre un botón de la barra de
herramientas por unos segundos sin dar click o presionar alguno de sus
botones dará como resultado la aparición de una pequeña caja de texto
que contiene una la descripción de la función que realiza dicho botón.

• Ventanas de exhibición (Display Windows) Una ventana de
exhibición muestra la geometría del modelo y puede también incluir
exhibiciones de características, carga y análisis o los resultados del
diseño. Se pueden exhibir hasta cuatro ventanas en cualquier momento.

<!-- p. 65 -->

Capítulo 2 - “Pantalla”ETABS

• Exhibición de la Barra de Título (Display Title Bar). La
exhibición de la barra del título está situada en la parte superior de
la ventana de exhibición. Se destaca la barra principal de la 2 exhibición cuando la ventana de exhibición asociada es activa. El
texto en la barra del título de la exhibición incluye típicamente el
tipo y la localización de la vista en la ventana de exhibición
asociada.

• Barra de estado (Status Bar). La barra de estado está situada en
la parte inferior de la ventana principal. El texto que describe el
estado actual del programa se exhibe en el lado izquierdo de la
barra de estado.

• Coordenadas de la posición del cursor del mouse (Mouse
Pointer Position Coordinates). Las coordenadas que refieran la
posición del cursor del mouse se exhiben en el lado derecho de la
barra de estado. Una ventana no necesita estar activa para que las
coordenadas de la posición del cursor del mouse ratón sean
exhibidas. Es solamente necesario que el cursor del mouse esté
sobre la ventana. En un plano bidimensional o en una vista de dos
dimensiones de la elevación, las coordenadas de la posición del
cursor del mouse son exhibidos siempre. En una visión
tridimensional, las coordenadas de la posición del cursor del mouse
se exhiben solamente cuando el cursor del mouse se encaja a
presión a un punto o a una intersección de la línea de una
cuadrícula.

• Caja de Drop-Down de “Un piso” ("One Story" Drop-Down
Box). La caja drop-down está situada en el lado derecho de la barra
de estado. Las tres opciones en la caja drop-down son un piso,
todas los pisos, pisos similares. Con un piso, un objeto se aplica
solamente al nivel del piso en el cual se dibuja. Con todos los
pisos, un objeto dibujado en la vista del plano se aplica a todos los
niveles del piso en el modelo y en la misma localización del plano.
Una asignación hecha a los objetos seleccionados también se hace
a los otros objetos en la misma localización del plano en el resto de
los niveles del proyecto. Con pisos similares, un objeto dibujado
en la vista del plano se aplica a todos los niveles similares del
proyecto y en el modelo en la misma localización del plano. Una

La ventana de ETABS 2 - 3

<!-- p. 66 -->

asignación hecha a los objetos seleccionados se hace a los otros
objetos en la misma localización del plano en todos los niveles
similares del proyecto.

• Unidades en Curso (Current Units). Las unidades en uso se
exhiben en una caja drop-down que se localiza en la parte derecha
de la barra de estado. Las unidades pueden ser cambiadas en
cualquier momento de la creación del modelo.

<!-- p. 67 -->

Guía de Introducción para el Usuario

La Vista Aérea.
2 La figura 2-2 muestra un ejemplo de la ventana de la vista aérea. Esta ventana

exhibe completamente el dibujo para ayudar al usuario a moverse alrededor de

la ventana activa de un modelo mas grande y usar la función del zoom para

ver las áreas pequeñas mas fácilmente. También puede usarse la vista aérea

para tener una visión de qué parte del modelo se exhibe en la ventana activa.

Cada vez que se corrige el modelo, la visión aérea es actualizada.

2 - 4 La Vista Aérea.

<!-- p. 68 -->



<!-- p. 69 -->

3

Capítulo 3

Modos Básicos, Herramientas de
Dibujo, Punteros del mouse.

Objetivo
Este capitulo describe brevemente las dos modos de operación de ETABS,
identifica las herramientas de dibujo y describe como la apariencia del
cursor del mouse cambia para diversas aplicaciones.

Seleccionar o Dibujar.
Los dos modos en este programa son seleccionar (select) y dibujar (draw).

• El modo de seleccionar permite seleccionar objetos y es usado
para operaciones de edición, hacer asignaciones de objetos y
resultados de vista o impresión. De forma automática, el
programa se encuentra en modo de seleccionar. El capitulo 6
describe los varios métodos para seleccionar puntos, líneas y
áreas en el modelo.

• El modo de dibujar permite dibujar objetos.

Objetivo 3 - 1

<!-- p. 70 -->

Guía de Introducción para el usuario

El modo de dibujar automáticamente se desactiva cuando se selecciona una
de las siguientes opciones del submenú del menú de Dibujar o se da click a
los botones de la barra de herramientas. Nótese que las vistas en paréntesis
3 (Plan,esta activo;Elev, por3D)ejemplodespuéseldelcomandonombrededellascomandolíneas de indicadibujo cuandopuede usarseel botónen
las vistas de Plano, Elevación, o 3D, pero el comando para dibujar muros,
puede ser usado en la vista del Plano solamente. Los nombres de los
comandos se asumen de acuerdo a la explicación de las acciones que
realizan. La terminología “en regiones” significa sin ningún compartimiento
“at Clicks” significa a la posición del cursor del mouse en el modelo cuando
se da click izquierdo al mouse. Mas información sobre las herramientas de
dibujo están disponibles buscando “Menú de dibujo” o “Draw Menu” en el
menú de ayuda (Help menú)> o en el comando de Help on.

• Trazo de Objetos Punteados.

• Dibujo de Objectos lineales.

• Dibujo de
líneas (Plano, Elev, 3D)

• Creación de líneas en regiones o clicks (Plano, Elev, 3D)

• Crear Columnas en Regiones o en Clicks (Plano)

• Crear Vigas Secundarias en regiones o en Clicks (Plano)

• Crear apoyos en regiones o en Clicks (Plano)

• Dibujo de Objetos de Área.

• Dibujo de Áreas. (Plan, Elev, 3D)

• Dibujo de Áreas rectangulares (Plano,
Elev)

• Crear Áreas de un Click (Plan, Elev)

• Dibujo de Muros (Plano)

3 - 2 Select or Draw

<!-- p. 71 -->

• Crear muros en regiones o por Clicks
(Plano)

• Dibujar elevaciones desarrolladas

definidas.

<!-- p. 72 -->

Capítulo 3 – Modos Básicos, Herramientas de Dibujo y
Apuntadores del Mouse

3

Los modos de Dibujo permanecen activos hasta que el usuario realiza
alguna de las siguientes actividades para regresar al modo de seleccionar.

• Presionar el Cursor sobre la barra de

herramientas.

• Presionar la tecla Esc en el teclado.
• Seleccionar un comando del Menú de Seleccionar.

El apuntador del mouse indica cual de los modos esta activado. La
apariencia o propiedades del apuntador del mouse se definen en el Panel de
Control de Windows. Las propiedades del puntero del mouse son Selección
de Apuntador normal (Normal Select Pointer) y Selección de Apuntador
Alternativa (Alternate Select pointer).Nota:

Las
propiedades En el modo de seleccionar, el apuntador esta en normal (Normal Select
del mouse se Pointer). Si usted esta usando las funciones automáticas, el mouse se
asignan por exhibirá de esta forma.medio del
Menú de Inicio En el modo de Dibujo, el apuntador del mouse es el Alternativo (Alternate
de Windows, Select pointer). Si usted esta usando las funciones automáticas, el mouse se
entrando en exhibirá de la forma normal.Settings,
después en
Nótese que durante el modo de dibujar, si se mueve el apuntador del mouse sobre laControl panel
barra de herramientas o los menús, temporalmente cambia a la selección dely en las
propiedades apuntador. Si usted no da click sobre uno de los menús o la barra de herramientas,
del Mouse. el apuntador del mouse se revierte al modo apuntador cuando se mueve el cursor
hacia la ventana de exhibición.

Otras propiedades del mouse se utilizan para varias acciones en el programa,
incluyendo Ayuda, Seleccionar, Ocupado, Selección de texto, Edición de tamaño
vertical, Edición horizontal del tamaño, y Mover. La apariencia del apuntador del

Select or Draw 3 - 3

<!-- p. 73 -->

mouse para aquellas acciones depende de las propiedades que se le asignen al
cursor del mouse.

<!-- p. 74 -->

4

Capítulo 4

Comenzando un Modelo

Objetivo
Este capitulo describe como comenzar un modelo creando el sistema de
cuadricula básico. Los objetos estructurales se posicionan relativamente en
el sistema de cuadricula.

Creando el sistema básico de cuadricula.
Comience creando el sistema de cuadricula dando click en el Menú de
Archivo (File menú) > y con el comando o botón de Modelo Nuevo (New
Model). Aparecerá la forma que se muestra en la Figura 4-1.

F

i

g

u

Figura 4-1 La forma de Iniciación del Nuevo Modelo.
Objetivo 4 - 1

<!-- p. 75 -->

Guía de Introducción para el usuario.

Seleccione el botón de No que se ofrece como opción en la figura y
Nota: aparecerá el recuadro que se muestra en la Figura 4-2.
Mas infor-
mación
sobre las
plantilla se encuentra
disponible en
el Menú de
Ayuda.

Figura 4-2 Construcción del Sistema de Cuadricula y la forma de

Definición de información del piso.

El sistema de cuadrícula para construcción y el modo de historial de datos
son usados para especificar el espaciado horizontal de la cuadricula, guardar
datos, y en otros casos, modelos de plantillas. Los modelos de plantillas
proveen una forma rápida, y sencilla para empezar un modelo. Estas formas
automáticamente, añaden objetos estructurales con propiedades especiales a
su modelo. Se recomienda ampliamente que usted inicie su modelo usado las
plantillas lo más frecuentemente posible. De cualquier modo, en este ejemplo,
el modelo es construido desde la nada, en lugar de usar una plantilla.

La forma contiene los botones de OK y Cancel, los cuales son usados para aceptar o
cancelar las selecciones que se hacen en la forma. Al dar click al botón de OK se
acepta alguna de las selecciones o entradas. Dando clic al botón de Cancel se
cancela la selección hecha.

4 - 2 Creación del sistema de cuadricula básico.

<!-- p. 76 -->

Capítulo 4 – Comenzando un modelo

Dimensiones de la cuadricula (Planta) – Definiendo un sistema

de cuadricula. Use las dimensiones de la cuadricula (Plan)para definir el

sistema cuadricular de líneas. La forma para definir el sistema de cuadricula
ofrece dos opciones: 4

• Espaciado Uniforme en la cuadricula. (Uniform Grid spacing)
Especifique el numero de líneas de la cuadricula en las direcciones
X y Y y un espaciado uniforme para las mismas. Nótese que el
espaciado uniforme en las direcciones X y Y puede ser diferente.
Esta opción define el sistema de cuadricula para el sistema global
de coordenadas. Si subsecuentemente es necesario, editar la
información, se hará desde el menú de Edición (Edit menú) > y
el comando Edit Grid Data. Para mas información, busque “edit
grid data” usando el menú de ayuda (Help menu) > y el comando
Search for Help on. Nótese que la cuadricula de coordenadas
global predeterminada es plano cartesiano (rectangular). Use
Edición (Edit) > Edit Grid Data > y el comando Edit Grid para
modificar el sistema de cuadricula.

• Ajuste del espaciado de la cuadrícula. (Custom Grid Spacing).
Etiquete o marque las líneas de la cuadricula y defina los espacios
no uniformes de las líneas de la cuadricula en las direcciones X y
Y para el sistema global de coordenadas. Después de elegir esta
opción, de click en el botón de etiqueta de la cuadrícula (Grid
Label) para etiquetar las líneas de la cuadricula y después de clic
en el botón de Edición de cuadrícula (Edit Grid) para cambiar el
sistema de cuadrícula. Para mayor información, busque en “grid
labeling” usando Help menu > Search for Help on.

Las razones para definir el sistema de cuadricula para el diseño del modelo
incluyen:

• Vistas de los alzados predeterminada en el modelo ocurren en cada línea
de cuadricula primaria en el modelo.

• Los objetos estructurales adheridos al modelo desde una plantilla se
basan en las definiciones de las líneas de cuadricula del modelo.

• Los objetos se adhieren a las líneas de la cuadricula cuando se dibuja en el

Creación del sistema básico de cuadrícula 4 - 3

<!-- p. 77 -->

modelo.

• Acoplamiento de Objetos a sus intersecciones con las líneas de la

cuadricula.

• Las líneas de la cuadricula en el modelo pueden ser definidas con los
mismos nombres usados en los planos constructivos. Esto puede permitir
una identificación mas fácil de sitios en el modelo.

<!-- p. 78 -->

5

Capítulo 5

Creación del Modelo Estructural

Objetivo
Este capitulo describe como crear el modelo estructural. Se asume que se ha
leido el capitulo 4 y que ya ha quedado entendido como comenzar un modelo
con ETABS definiendo un sistema de cuadricula.

Definir los datos del piso.
Los datos de piso se definen usando el Sistema en planta de la
cuadrícula y la definición del piso. La figura 4-2 del capitulo 4
Nota: los muestra esta forma. Como se describe en el capitulo 4, utilice el
datos de Menú archivo File menu > y el comando New Model y seleccione
piso
pueden la forma de Iniciación de Nuevo Modelo “New Model Initialization
editarse
desde Edit form” para tener acceso al Plano del sistema de definición de
menu > Edit cuadricula y piso. Seleccione una de las dos opciones en las
Story Data> Edit Story dimensiones de las áreas del piso de la forma disponible para definir
los datos del piso.

Datos de piso simple (Simple Story Data): Inserte los valores en las cajas
de edición para definir el numero de pisos y la altura típica del piso que será
usado en todos los niveles de la construcción.

Objetivo 5 - 1

<!-- p. 79 -->

Guía de Introducción para el usuario

Note: E programa provee nombres predeterminados para cada nivel de piso (por
ejemplo, Piso 1, Piso 2 y así sucesivamente, así como similitudes en los
niveles. Las
“similitudes” de
\~ Custom Story Data: Después de elegir esta opción, da click en el botón cada piso
pueden ser Edit Story Data para hacer aparecer la forma de Información. Coloca
5 significativas valoresnombres,ennombresla formadiferentesde informacióno Alturas delno uniformespiso para odefinerdatos similarestus propiosque Por ejemplo,
puedas ajustar. cuando el piso
2 es “Similar
La forma de Datos de piso también aparece cuando se utiliza el menú de al” Piso 1, un
objeto dibujado Editar, Edit menu > Edit Story Data > Edit Store. Para mayor
en el piso 1, información sobre la forma de Datos de piso, referirse a la sección llamada
aparece en el (Comando de datos de piso) "Edit Story Data Command" en el Menú de
Piso 2. Edición de los usuarios del manual de interfase grafico. Para mayor
información sobre las similitudes de un nivel de piso, busque en el menú de
caja de similitudes “similar stories drop-down box” usando el menú de
ayuda Help menu > Search for Help on. La similitud de niveles de piso
puede ser significativo para componer el diseño compuesto de la vigueta, de
la viga y del acero. Busque las similitudes “similarity” usando el menú de
ayuda de ETABS (ETABS Help menu) > y busque Help on.

Añada Objetos Estructurales usando plantillas.

Use la parte inferior del sistema reticular del plano y Piso como fue usada en
la sección anterior para añadir objetos estructurales a su modelo desde
plantillas predeterminadas. En muchos casos es la forma mas simple,
conveniente y rápida para iniciar el modelo.

Para añadir Objetos Estructurales la forma del plano del sistema de

5 - 2 Agregar Objetos Estructurales usando Plantillas

<!-- p. 80 -->

definición de cuadricula y piso se reproduce la siguiente referencia:

<!-- p. 81 -->

Capitulo 5 – Creación del Modelo Estructural.

Nótese que el número de planillas se compone de dos plantillas para
construcción en acero, cuatro para construcción en concreto y solamente una
para rejillas o cuadricula. Lo cual quiere decir que no se agregan objetos
estructurales al modelo desde la plantilla. Cuando una opción ha sido
seleccionada (botón) se ha seleccionado algo en el Área de Añadir Objetos
Estructurales, se resaltará el nombre de dicho objeto. Cuando la forma del
sistema de definición de cuadricula o piso se abre, se resaltara la selección 5de Solo Cuadricula “Grid Only”, indicando que a menos que se seleccione
otra plantilla, su modelo tendrá solo un sistema de cuadricula o rejillas.

Elija cualquiera de las plantillas dando click en el botón izquierdo del
mouse. Cuando uno de los botones de las plantillas es elegido, aparece una
forma para dicha plantilla. Use la forma para especificar diversos tipos de
datos en su modelo. Cuando haya terminado de especificar los datos en la
forma de la plantilla, de clic al botón de OK para regresar al sistema de
definición del Plano para construcción de cuadricula. Dando clic al botón
OK en dicha forma se completa la operación.

Nota: Cuando se utilicen las plantillas para construcción en concreto
en este programa, las vigas y las costillas de la losa (viguetas) están
normalmente modeladas a profundidades iguales a la dimensión de
la tapa de la losa (no fondo de la losa) y al fondo W de la viga o la
losa provista de costillas. También, las vigas se modelan como
elementos de línea en este programa de h. Así, losas con la
capacidad de flexión fuera-de-plano van del palmo del centro-deviga hacia el centro-de-viga en el modelo del programa.

Después de que se ha dado click al botón de OK en la forma de Definición
del sistema de construcción del Sistema de Plano de cuadricula y
Definición de Piso, el modelo aparece en la pantalla principal de ETABS
con dos ventanas embaldosadas verticalmente, una Vista de Plano en la
parte izquierda y una vista 3-D a la derecha, tal y como se muestra en la
Figura 5-1, el número de ventanas exhibidas puede ser cambiado usando el
menú de Opciones. (Options menu > Windows)

Nótese que la vista del Plano esta activa en la Figura 5-1. Cuando la ventana
esta activa, la exhibición de la barra principal se encuentra resaltada. Se
activa una ventana dando click a cualquier lugar en la vista de la ventana.

Añadir Objetos Estructurales usando Plantillas 5 - 3

<!-- p. 82 -->

Guía de Introducción para el usuario

5

Figura 5-1 La Ventana Principal de ETABS

Añadir Objetos Estructurales de Forma Manual
Objetos, tales como columnas, vigas, y pisos, también pueden ser dibujados
manualmente como se describe en las secciones siguientes.

Dibujar Columnas
Asegurese de que la Vista del Plano este activa. De click en el botón
de Create Columns in Region or at Clicks o uilice el comando
Draw menu > Draw Line Objects > Create Columns in Region
or at Clicks. Las propiedades de la caja de Objetos para la columnas
(Object pop-up box) se muestra en la Figura 5-2.

5 - 4 Añadir Objetos Estructurales de forma Manual

<!-- p. 83 -->

Capítulo 5 – Creación del Modelo Estructural

Nota:

La definición
de los
parámetros y
controles del
dibujo se 5
encuentra
disponible en
las Figura 5-2. Propiedades de la Caja del Objeto para Columnas
Propiedades
de la Caja del Las propiedades de la Caja del Objeto proveen de varias definiciones de
Objeto para parámetros y controles de dibujo. Revise los parámetros y controles que se
columnas
muestran en esta caja antes de dibujar en su columna para asegurar que sondifiere
dependiendo los que usted requiere. Cambie cualquier entrada de la caja dando click
del comando sobre ella y haciendo una nueva selección desde la caja drop-down o
de dibujo. tecleando nueva información en la caja de edición, como corresponda.
Siempre revise
que los Después de revisar los parámetros en las propiedades de la Caja del Objeto
parámetros y (Object box), de click en la parte izquierda de la Vista del Plano en la
controles son intersección de las líneas de la cuadricula donde usted quiera la columna.
los que
Una columna en forma de “I” deberá aparecer en un punto de la Vista delnecesita para
teclear el Plano. Continué con dicha operación para nuevas columnas.
objeto que se
Alternativamente, dibuje las columnas pendientes en una sola acción paseandoesta
dibujando. "windowing" alrededor de las intersecciones. Para ello (window), de click izquierdo
al mouse sobre y hacia la izquierda de la primera intersección de la cuadricula y
después, mientras sigue presionando el botón izquierdo del mouse, arrastre el
mouse hasta la parte inferior derecha de la ultima intersección de la cuadricula. Una
caja de selección similar a esa se muestra en la Figura 5-3 y deberá expandirse
alrededor de las líneas de las intersecciones de las cuadriculas conforme el mouse
se arrastra por el modelo. Suelte el botón del mouse y el programa dibujara los
objetos de la columna en las intersecciones de la cuadricula.

Es una buena idea guardar frecuentemente los cambios que se hacen al modelo. De
click en el menú de archivo (File menu > y el comando Save), o en el botón de
Save para guardar los cambios de su modelo.

Añadir Objetos estructurales de forma Manual
5 - 5

<!-- p. 84 -->

Guía de Introducción para el usuario

5

Figura 5-3 Dibujando Objetos de Columna en regiones seleccionadas.

Dibujo de Vigas
Asegúrese de que la Vista del Plano este activa. Dé Click en Create Lines in
Region (crear lineas en region) o en el botón de Clicks, o en el menú de
dibujar (Draw menu > Draw Line Objects> Create Lines in Region or
Clicks) . Aparecerán las propiedades de la caja de Objetos de pop-up box para
vigas que se muestra en la Figura 5-4.

5 - 6 Añadir Objetos Estructurales de forma Manual

<!-- p. 85 -->

Capítulo 5 – Creación del Modelo Estructural

Como se ha explicado previamente, la Caja de Objetos provee varias
definiciones de parámetros. Cambie cada entrada en la caja dando click en
ella, haciendo la selección desde la caja drop-down o tecleando nueva
información en la caja de edición, como corresponda.

Despues de haber revisado los parámetros en las propiedades de la Caja de
Objetos, de un click izquierdo en la Vista de Plano en una línea de la 5cuadricula (grid line) donde deba ser colocada una viga. Una viga se dibuja
junto con la línea de la cuadricula seleccionada. Repitiendo este proceso se
colocaran las demás vigas.

Alternativamente, dibuje las vigas que estén pendientes en un solo paso
pasando el mouse alrededor de las intersecciones de la cuadricula.
“Windowing” que ya ha sido explicado en la sección anterior.

De click frecuentemente en File menu > y el comando Save, o en el botón
de Save para guardar los cambios hechos al modelo.

Dibujar Vigas Secundarias (Infill)
Añada vigas secundarias o vigas "infill" dando click en Create Secondary
Beams in Region or at Clicks, o en el comando Draw menu > Draw
Lines Objects > Create Secondary Beams in Region or at Clicks. De
forma similar que en otras operaciones de dibujar, las propiedades de la caja de
Objeto pop-up aparecerá para dar la oportunidad de definir los parámetros
para las vigas secundarias.

Para insertar las vigas secundarias, de click izquierdo en la cuadricula de la
esquina (bay) limitada por líneas en las cuales serán colocadas las vigas. De
forma similar a las columnas y a las vigas primarias, las vigas secundarias
pueden dibujarse pasando el cursor sobre las esquinas. Nótese que se debe
fijar el parámetro de la Orientación aproximada para que quede fijada la
dirección del tramo. Recuerde Guardar los cambios hechos al modelo.
Con el comando de File menu > Save, o con el botón de Save.

Dibujar el Piso
Asegurese de que la Vista del Plano este activa. De click en el botón Draw
Areas, o seleccione el comando Draw menu > Draw Area Objects >
Draw Areas. Aparecerán las propiedades de la caja pop-up del Objeto
para las áreas que se muestra en la Figura 5-5.

Añadir Objetos Estructurales de Forma Manual 5 -
7

<!-- p. 86 -->

Guía de Introducción para el Usuario

5

Figura 5-5 Las Propiedades de las áreas de la Caja de Objeto.

De formar similar a las columnas y las vigas, estas propiedades de la Caja del
Objeto proveen de la oportunidad de revisar y cambiar los parámetros para el
área. Para cambiar cualquier entrada de la caja solo de clic sobre ella y haga
una nueva selección desde la caja drop-down o teclee la nueva información
en la caja de edición, como corresponda.

Después de revisar los parámetros en la caja de propiedades, revise que el
comando de Snap to Grid Intersections and Points esté activado. Estas
asistirán apropiadamente para dibujar un área del objeto. Este comando esta
activo cuando su botón asociado esta hundido. Alternativamente, use el
comando Draw menu > Snap To > Grid Intersections and Points para
asegurarse que el comando esta activo. Este comando esta activo de forma
predeterminada.

Dé click izquierdo en una columna para iniciar el área del piso en esa
columna. Después moviendo el cursor, alrededor del perímetro del objeto
del piso, de click en otra de las intersecciones de las columnas para dibujar
la línea exterior del edificio. Presione la tecla Enter en el teclado para
completar el piso.

Si ha cometido un error al dibujar este objeto, de click en el botón de Select
Object para cambiar el programa de Dibujar a Seleccionar (Draw mode to
Select mode). Después de clic en Edit menu > y después en el comando
de Undo Area Object Add.

Para poder tener una vista mejor de la adición del piso, de click en el botón
de Set Building View Options. Cuando aparezca la forma de Set Building
View Options, revise que se encuentren presionadas las opciones de la caja de
Object Fill check y la opcion Apply to All Windows, como se muestra en la
Figura 5-6. De Click al botón de OK.

5 - 8 Añadir Objetos Estructurales de Forma Manual

<!-- p. 87 -->

Capitulo 5- Creación del modelo Estructural

5

Recuerde GRABAR o SALVAR los cambios hechos a su modelo.

Añadir Objetos Estructurales de Forma Manual 5 - 9

<!-- p. 88 -->

6

Capítulo 6

Selección de Objetos Estructurales.

Objetivo

Este capitulo describe como seleccionar objetos en el modelo.

Opciones de Selección

El programa tiene tres métodos básicos para seleccionar objetos:
\~ Click Izquierdo: Se selecciona el objeto dando click izquierdo en un
objeto. Si hay objetos múltiples, uno sobre otro, sostenga la tecla de Ctrl en
el teclado mientras da click en los objetos. Aparecerá una forma que le
permitirá especificar cual es el objeto que desea seleccionar.

\~ Window o "Windowing": Dibuje un recuadro o ventana alrededor de
uno o más objetos para seleccionarlos. Para dibujar una ventana alrededor
de un objeto, primero posisione el cursor debajo de los límites del objeto;
por ejemplo: en la parte inferior izquierda del objeto. Después Presione y
mantenga así el botón izquierdo del mouse. Mientras realiza lo anterior jale
el cursor a la parte superior derecha del objeto que quiere seleccionar.

Objetivo 6 - 1

<!-- p. 89 -->

Introductory User's Guide

Suelte el botón del mouse para completar la selección. Durante la
selección con la ventana note lo siguiente:

\- Conforme se arrastra el mouse, aparece una ventana elástica "rubber
band window". Esta ventana elástica es un rectángulo que cambia de
forma conforme se arrastra el mouse. Una esquina de la ventana
elástica se encuentra en el punto en donde se oprimió el botón del
mouse por primera vez. La esquina diagonalmente opuesta de la
ventana elástica estará en la posición del cursor del mouse. Será6
seleccionado cualquier objeto visible dentro de la ventana elástica
cuando se suelte el botón del mouse.

\- Siempre y cuando usted se quede debajo de los límites del objeto que
quiere seleccionar, se puede comenzar desde cualquier punto, por
ejemplo: debajo del lado derecho, debajo del lado izquierdo, o debajo
del lado derecho del objeto que se quiere seleccionar. En todos los
casos, deberá arrastrar el cursor diagonalmente a través del objeto que
desea seleccionar.

\- Un objeto completo debe descansar entre la ventana elástica y el objeto a
seleccionar.

Nota sobre las selecciones de la Vista del Plano: Cuando se selecciona con
ventana “windowing” en la vista del plano (no en vista del plano en
perspectiva), solo los objetos visibles que descansan totalmente en el nivel
de la vista de plano serán seleccionados. En otras palabras, solo los objetos
de puntos visibles, objetos de área horizontal, y objetos de líneas
horizontales dentro de la ventana de selección serán seleccionados.

\~ Línea de Intersección: Dibuje una línea a través de uno o mas objetos
para seleccionarlos. Para usar este método de selección, de click en el
comando de Select menu > using Intersecting Line o en botón de
secting Line Select Model. Posisione su cursor en uno de los lados del
objeto (s) que desea seleccionar. Presione y mantenga así el botón
izquierdo del mouse. Mientras hace lo anterior, arrastre el mouse a través
del objeto que desea seleccionar. Suelte el botón del mouse para completar
la selección. Note lo siguiente sobre el método de línea de Intersección:

\- Mientras arrastra el mouse aparecerá la “línea elástica” (rubber band
line). Esta línea es punteada y cambia de orientación conforme usted
mueve el mouse. Se extiende desde el punto en el cual se presionó el
mouse por primera vez hasta la posición en que se encuentra. Cuando
se suelte el botón del mouse se seleccionara cualquier objeto visible
que se intersecte (o sea cruzado) con la línea elástica.

6 - 2 Optciones de Selección

<!-- p. 90 -->

Capitulo 6 – Selección de Objetos Estructurales

\- Después de usar este método para hacer selección, el programa regresa al
modo de seleccionar. Sin embargo, cada vez que se use el comando de
Select menu > using Intersecting Line debe usar el comando Set
Intersecting Line Select Mode.

.
\~ Control y Click Izquierdo: Mantenga presionada la tecla Ctrl y de click
izquierdo en algún punto, línea o área de objeto. Aparecerá una forma de
lista de selección como la que se muestra en la Figura 6-1, esto para 6
identificar los objetos existentes en esa ubicación. Seleccione el objeto
deseado al mover el puntero del Mouse sobre el y dando clic izquierdo en
el.

Métodos del Menú para seleccionar Objetos

La tabla 6-1 identifica los comandos del submenú que se encuentran
relacionados con el comando Select menu.

Métodos del Menú para Seleccionar Objetos 6 - 3

<!-- p. 91 -->

Guía de Introducción para el Usuario

Tabla 6-1 Sub-comandos del Menú de Selección (Select Menu)

Comando Acción que causa el Comando

De click en cualquier punto y en todos los objetos (punto,
en Plano XY línea y área) cuando son iguales en el plano XY mientas
los puntos sean seleccionados también. El objeto deberá
reposar totalmente en el plano asociado que ha sido
6 seleccionado
De Click en un punto yen todos los objetos (punto, línea y
en Plano XZ área) que se encuentren en el mismo plano global XZ
mientras el punto también es seleccionado. El objeto debe
reposar totalmente en el plano asociado que ha sido
seleccionado.

De Click en un punto y en todos los objetos (punto, línea
en Plano YZ y área) que se encuentren en el mismo plano global YZ
mientras el punto también es seleccionado. El objeto
debe reposar totalmente en el plano asociado que ha sido
seleccionado.

Seleccione el nombre de cualquier colección de objetos
por Grupos (groups) que hayan sido definidos como un grupo desde la Caja de
Selección de Grupos y el grupo será seleccionado.

Seleccione una pieza propiedad del armazón desde las
por secciones de Barras cajas de secciones de selección que han sido asignadas y
(marcos) esa sección propiedad del armazón será seleccionada.

Seleccione una sección del muro, losa o plataforma
por secciones de desde el nombre de la caja de sección de selecciones y
Muros/Losa/Plataforma todos los objetos del área que hayan sido propiamente
asignados a esas estructuras serán seleccionados.

por enlaces de Seleccione un enlace de propiedades nombrado en la caja
propiedades (link de Select Properties y todos los objetos de línea que
properties) hayan sido asignados a al enlace propiamente, serán
seleccionados.

6 - 4 Métodos del Menú para Seleccionar Objetos

<!-- p. 92 -->

Chapter 6 - Select Structural Objects

Seleccione un objeto de líneas. Las opciones para objetos
por Objetos tipo líneas tipo líneas son columnas, vigas, refuerzos o apoyos,
(Area Type Objets) líneas inútiles o dimensionales (cortas).

6
Seleccione un objeto tipo área desde la caja de selección
Por objetos tipo area de objeto y todos los objetos de ese tipo serán
(Line type Objetcs) seleccionados. Las opciones para los objetos del tipo área
son: pisos, muros, rampas o áreas nulas. Note que las
aberturas son un subset de objetos del tipo área nula.

Seleccione PIER desde la caja de selección y cualquier
por IDENTIFICACION área que tenga dicha forma y se le haya designado ese
DE PILA (PIER ID) nombre será seleccionada.

Por identificación de Seleccione el nombre de un arco desde la caja de
spandrel (Spandrel ID) Identificación de spandrel (Spandrel IDs) y cualquier
forma que haya sido asignada bajo ese nombre será
seleccionada.
Seleccione un nivel de piso desde la caja de Story Level,
Por nivel de piso (Story y todos lo objetos asociados con el serán seleccionados
level) (puntos, líneas y áreas).

Selecciona todos los objetos en el modelo ya sean
Todo (All) visibles o no. Sea cuidadoso al usar este comando.
Literalmente selecciona todos los objetos en su modelo.
También use el botón de Select All para ejecutar este
comando.

Cambie la selección que esta siendo seleccionada en ese
Invertir (Invert) momento, los objetos ya no serán seleccionados y los
objetos ya no estarán seleccionados y todos los objetos
que no estaban seleccionados se seleccionan.

Métodos del Menú para Seleccionar Objetos 6 - 5

<!-- p. 93 -->

Guía de Introducción para el Usuario

Comando de Deseleccionar
Deseleccione objetos uno a uno dando click izquierdo en los objetos
seleccionados. Alternativamente, use Select menu > y el comando
Deselect y sus sub-comandos para una rápida y especifica acción de
deseleccionar. Este comando provee acceso similar al descrito en la Tabla
6-1, excepto en el caso de ejecutar Select menu > y el comando Deselect y
los sub-comandos en lugar de seleccionar un objeto. Por ejemplo,
6 asumamos que usted quiere seleccionar todos los objetos en su modelo, excepto esos que se encuentran situados en el plano XZ. Haga esto de forma
rápida y sencilla usando Select menu > y el comando Select All y después
usando Select menu > Deselect > y el comando XZ Plane.

Comando de Obtención de Selección Previa (Get Previous
Selection)
En Select menu > y el comando Get Previous Selection seleccione el
objeto seleccionado anteriormente. Por ejemplo, asuma que ha seleccionado
algunos objetos tipo líneas dando click en ellos y asignándoles una parte de
las propiedades del armazón. Use el comando Get Previous Selection o el
botón Get Previous Selection para seleccionar la misma línea de objetos y
asignarles otra cosa.

Comando de Despejar Selección (Clear Selection)
La opción Select menu > y el comando Clear Selection se asocia con el
botón Clear Selection , limpia los objetos que se encuentran seleccionados.
Es un comando de todo o nada. Usted no puede limpiar una opción
selectivamente usando este comando.

6 - 6 Menú de Métodos de Selección de Objetos

<!-- p. 94 -->

7
Capítulo 7

Cargando el Modelo Estructural

Objetivo

Este capitulo describe como definir las cargas estructurales del modelo.

Cargas Estructurales
El programa permite al usuario que defina una variedad de cargas,
incluyendo cargas vivas y muertas, terremotos y cargas de viento. El usuario
asigna después las cargas a varios objetos estructurales en el modelo.
Note:
Se pueden Note que los manuales de diseño de barras de acero, concreto y piso
definir un compuesto, vigueta de acero y diseño de muro constante en concreto describen numero
las combinaciones de carga de acuerdo a los códigos de construcción. indeterminado
de
compartiment Definición del nombre de la Carga Estática
os de carga Para añadir una caja de carga estática, de click en Define menu > y el
estática en comando Static Load Cases de click en el botón Define Static Load Cases
ETABS. para que aparezca la forma del nombre del compartimiento de la carga
estática (Define Static Load Case Names form). Complete las siguientes
acciones usando dicha forma.

Objetivo 7 - 1

<!-- p. 95 -->

Introductory User's Guide

\1. Teclee el nombre del compartimiento de la carga en la caja de Load
edit. El programa no permite la duplicidad de nombres

\2. Seleccione un tipo de carga desde la caja Type drop-down.

\3. Teclee un multiplicador self-weight multiplier en la caja de edición de
Self-Weight Multiplier (ver la explicación que se presenta a
continuación)

\4. Si la carga especificada es de terremoto o viento (Quake or Wind),
seleccione una opción para la caja drop-down de carga auto lateral.7

\5. De click en el botón de Add New Load.

Nota: Si selecciona una carga lateral automática en la caja drop-down Auto
Lateral, de click en el botón de (modificar cargas laterales) Modify Lateral
Loads y revise o modifique los parámetros de la carga automática lateral en
la forma que resulte. Después de clic en OK para regresar a definir en la
forma de Define Static Load Case Names.

MULTIPLICADOR DE PESO PROPIO (SELF-WEIGHT
MULTIPLIER)

El peso propio de la estructura se determina multiplicando el peso por
volumen de unidad de cada objeto que tiene propiedades estructurales por el
volumen del objeto. El peso por volumen de unidad se especifica en las
propiedades del material (busque “material properties” usando Help menu
\> y el comando Search for Help on para mayor información o use el
comando Material Properties).

Una porción del peso propio de la estructura puede ser aplicado a cualquier
compartimiento de carga estática. El multiplicador de peso propio controla
que porción de peso propio contiene un compartimiento de carga. Un
multiplicador de peso propio de un valor de 1 incluye el peso propio
completo de la estructura y del compartimiento. Un multiplicador de peso
propio de 0.5 incluye una mitad del peso propio de la estructura en ese
compartimiento de carga.

7 - 2 Cargas estructurales

<!-- p. 96 -->

Chapter 7 - Load the Structural Model

Normalmente en un multiplicador de peso propio de 1 de un
compartimiento de carga estática solo puede especificar, usualmente el
compartimiento de carga muerta. Todos los casos de compartimientos de
otras cargas estáticas tienen multiplicadores de peso propio de cero. Note
que un multiplicador de peso propio de 1 esta incluido en dos diferentes
compartimientos de carga que se combinan en una carga, los resultados de
dicha combinación se basan en un análisis en el cual se ha aplicado a la
carga el doble propio peso de la construcción.
7Modificar un caso existente de Carga Estática.
Use el siguiente procedimiento y la forma Define Static Load Case Names
para modificar el compartimiento de carga estática. Se accesa a forma
Define Static Load Case Names usando Define menu > y el comando
Static Load Cases o el boton Define Static Load Cases :

\1. Resaltar el compartimiento de la carga existente en la forma. Note
que los datos asociados con el compartimiento de la carga aparecen
en las cajas de edición y drop-down en la parte superior de las áreas de
carga (Loads area).

\2. Modifique cualquier información en el area de los casilleros.

\3. De click en el botón de Modify Load. Si es necesario, de clic en el
botón Modify Lateral Loads para modificar los parámetros de
carga lateral.

Borrar un Compartimiento de Carga Existente
Use el siguiente procedimiento para borrar un compartimiento de carga
estática en la forma Define Static Load Case Names. Note que cuando
usted borra dicho compartimiento, todas las cargas que habían sido
asignadas al modelo como parte del compartimiento de carga estática serán
eliminadas también.

• Resaltar el compartimiento de la carga existente en la forma. Note
que los datos asociados con esa carga aparecen en las cajas de
Edición y drop-down en la parte superior del área de Cargas.

• De click en el botón (borrar carga) Delete Load.

Cargas estructurales 7 - 3

<!-- p. 97 -->

Guía de Introducción para el usuario

Asignar Cargas Estructurales
Los compartimientos de carga se han definido en la sección anterior y
pueden asignarse a puntos/nodos, líneas/barras y áreas/exteriores o
cascarones. El usuario debe seleccionar primero el elemento antes de
asignarlo a la carga. El capitulo 6 de esta guía describe como seleccionar los
objetos estructurales.

Después de haber seleccionado el objeto, de click en el comando Assign menu para
tener acceso al submenú aplicable y a las opciones de asignación. La tabla 7-1 identifica
7 las opciones u los submenús.

TABLA 7-1 Comandos de Carga en el Menú de Asignar (Assign Menu)
Cargas de Nodo/Puntos Cargas de Cargas de Area/Shell
(Joint/Point) Armazón/Línea (Shell/Area)
(Frame/Line)
Fuerza Punto Uniforme

Desplazamiento del Piso Distribuido Temperatura
Coeficiente de Presion del
Temperatura Temperatura Viento

Note que el tipo de elemento seleccionado determina que asignación se
puede hacer. Por ejemplo, el coeficiente de presión del viento no puede
hacerse a un nodo/punto o a un objeto armazón/línea. Sin embrago, si un
objeto nodo/punto (columna en plano) o un objeto armazón/línea (viga) ha
sido seleccionado antes de dar click al comando Assign menu el
Exterior/Área el submenú de la carga no estará disponible.

Aparecerá una forma después de dar click al comando Assign menu, el
submenú aplicable al tipo de objeto, y la asignación de la opción deseada. La
Tabla 7-2 identifica las formas que se generan cuando se usan diversos
comandos.

TABLA 7-2 Formas para comandos de carga en el Menú de Asignar.

Comando Nombre de la Forma*

Fuerza de la carga Nodo/Punto
Puntos fuerza (Point Force)
Desplazamiento del piso Desplazamiento de los Pisos
Temperatura Puntos de Temperatura

7 - 4 Asignar Cargas Estructurales

<!-- p. 98 -->

Capitulo 7 - Modelo Estructural de Cargas

Cargas Uniformes de Areas/Shell
Shell/Area Loads >Uniform Cargas de Superficies Uniformes

Uniform Surface Loads
Temperatura Temperatura de los Objetos Area
Coeficiente dePresion de Vientos Coeficiente de presión de vientos.

\* Nota: En la forma que se exhibe en la ventana de ETABS, de click en la
tecla F1 para acceder a la Ayuda sensible al contexto de la forma (context- 7
sensitive Help).

Aunque los nombres de las formas varían dependiendo de los comandos que
se usen, cada forma tiene un menú drop-down que permite al usuario
seleccionar el compartimiento de la carga que será asignado. Lógicamente,
los compartimientos de carga que se encuentren disponibles varían
dependiendo del tipo de tarea. Las formas también incluyen otras tareas de
objetos con campos específicos de que habilitan al usuario para refinar la
asignación de la carga.

Busque el comando de cargas estáticas “static loads” usando el menú Help
menu > y el comando Search for Help on para mayor información sobre las
cargas.

Asignar Cargas Estructurales 7 - 5

<!-- p. 99 -->

8
Capítulo 8

Asignar/Cambiar Propiedades

Objetivo
Este capitulo describe como asignar o cambiar las propiedades de los
elementos estructurales de su modelo.

Propiedades

Al crear el modelo, el usuario dibuja puntos, líneas, y áreas de objetos. Para

habilitar el diseño y el análisis deben asignársele propiedades a esos objetos,

tales como propiedades del material, secciones de barras, muros/losa o

bloques/plataformas (wall/slab/deck). Note que el menú de asignar enlista

varias propiedades que pueden ser asignadas. También note que la

asignación de las cargas ya ha quedado explicada en el capitulo 7 de esta

Objetivo 8 - 1

<!-- p. 100 -->

guía.

Como se muestra en la Tabla 8-1, los tipos de tareas disponibles, dependiendo del tipo

de objeto. Las tareas también dependen del tipo de diseño. ( acero contra

concreto y contra diseño compuesto).

<!-- p. 101 -->

TABLA 8-1 Posibles Tareas de los Objetos por Tipo de Ojbetos.
Objeto Opción de Tarea Nombre de la Forma*
Nodo/Punto Panel de Diafragma Rígido Asignar Diafragma
Panel de Diafragmas de Zonas Asignar Panel de Zona
Puntos de Limitación (Soporte) Asignar Límites
Puntos Resorte Propiedades de Asignar Resortes
Conexión Asignar NL Propiedades de conexión
Puntos Adicionales de Masas Asignar Masas

Lineas/Barra Secciones Barra Asignar Propiedades de Barras
Barras Liberadas Asignar Liberación de Barras
8 MomentoBarra TipoParcialViguetade(Longitud)Empotramiento MomentoMarcos deespecialvigas Longitud
Punto de colocación de Barra Extiende el punto de
Punto de salida de ejes locales inserción del marco
Modificadores de las Líneas Asigna el espaciado
Barras Orientación del eje
Líneas tipo Propiedades de Análisis y modificación de las
Conexión propiedades y factores
Barras de bisagras no lineales Asignar líneas a los marcos
Rótulos de pilares Asignar propiedades a los marcos
Rótulos de Spandrel
Líneas Resorte Spandrel Names
Líneas de Masas Adicionales Asignar flexiones
Subdivisión Automática de Barras Asignar masas
Uso de Líneas para División interna**Subdivide, Don't Subdivide, Cancel
de Pisos (Floor Meshing) **Yes, No, Cancel

Áreas/Shell Secciones Muro/Losa/Plataforma Asignar secciones a objetos
Aberturas Asignar aberturas Asignar
Diagrama Rígido de Cortes Diafragmas Asignar ejes locales
Locales
Densidad de Shell Analizar y modificar factores
Modificadores de etiquetas de Pilas Nombres pier
(Pier)
Áreas de Etiquetas Spandrel Nombres Spandrel
Springs
Áreas Adicionales de Áreas Masa Asignar flexiones
División Interna de Objetos Asignar masas
Opciones de Compulsión Automática Opciones de cuadrículas automáticas
de Líneas Auto Line Constraint Options

8 - 2 Propiedades

<!-- p. 102 -->

Capitulo 8 - Asignar/Cambiar Propiedades

Observe la tarea realizada para trazar puntos, líneas y objetos área dando click al

objeto. Aparecerán las formas de Información apropiadas de Punto (The

appropriate Point Information), Información de Línea (Line Information), o

información de Área (Area Information). De clic en Assignment tab.

En cada caso, seleccione un objeto antes de ejecutar el comando de la tarea
deseada ( seleccione un objeto línea antes de usar Assign menu > 8

Frame/Lines > y el comando Frame Sections). Como se ha explicado en

el capitulo 6 de esta guía, usando la tecla Ctrl y dando click en un punto del

modelo puede simplificar el proceso de seleccionar objetos cuando hay

varios objetos presentes en el mismo lugar o cuando seleccionar objetos es

nuevo para el usuario que esta aprendiendo.

La disponibilidad de los comandos depende del tipo de objeto que se selecciona.

Las formas predeterminadas incluyen los campos de objetos y las tareas que

inhabilitan el refinamiento de la tarea. Las modificaciones de las tareas se

pueden hacer fácilmente accesando a las formas mediante el uso del

comando apropiado del menú Assign menu.

Las formas incluyen los botones OK y Cancel y se usan para aceptar o
cancelar los cambios que se hicieron a las formas.

Note que la combinación del tipo de objeto, el nombre del comando y el nombre

de la forma provee una indicación de lo que puede ser alcanzado usando

dicho comando.

Lista de Auto selección 8 - 3

<!-- p. 103 -->

Lista de Auto Selección de Secciones
La lista de Auto selección de secciones de ETABS ayuda a controlar el
tiempo requerido para desarrollar el modelo, así como a mejorar el proceso
de diseño.

Una lista auto selección de secciones es una simple lista de secciones: por

ejemplo, W18X35, W18X40, W21X44, W21X50 y W24X55. Las listas de

Auto selección de secciones (Auto select section lists) puede ser asignada a

las piezas de la barra. Cuando se hace una lista de auto selección asignada a

una pieza de la barra, el programa automáticamente puede seleccionar la

sección mas económica, adecuada desde la lista.

El programa tiene diversas listas de auto selección. Además, el usuario
puede desarrollar una lista usando los siguientes pasos:

<!-- p. 104 -->

\1. De click en Define menu > y el comando Frame Sections, y esta
exhibirá la forma Define Frame Properties form, Figura 8-1.

8

Figura 8-1: Forma de Definición de Propiedades de la barra.

\2. De click en la caja drop-down que dice "Add I/Wide Flange" y despues
tendrá acceso a la forma n the Click To area of the Define Frame
Properties form. Observe todas las opciones de la lista de las posibles
secciones a localizar hasta llegar a Add Auto Select List. De doble click
en ella. Aparecerá la forma Auto Selection Sections que se muestra en la
Figura 8-2 .

\3. Teclee u nombre para la lista de Auto Section Name edit. Puede usarse
cualquier nombre. Para esta descripción y sus fines, la lista nueva de
Auto selección (Auto Select Section) será nombrada AUTOLATBM.

\4. Busque en la lista de secciones para encontrar las vigas (List of Sections
to find the beams) para incluirlas en la lista. De clic en ellas para
resaltarlas. Note pueden usarse las ventanas estándares para seleccionar
artículos en una lista ( dar click en una viga y después presionar la tecla
shift antes de seleccionar otra viga resaltara todas las vigas que se
encuentren situadas entre las dos vigas seleccionadas.)

8 - 4 Lista de auto selección de secciones

<!-- p. 105 -->

Capitulo 8 - Asignar/Cambiar
Propiedades

8

Figura 8-2: Forma de Auto Selección de Secciones

\5. De click en el botón de Add para agregar las vigas seleccionadas para la
lista de Auto selecciones del lado derecho de dicha forma.

\6. De click en el botón de OK y después en el botón OK de la forma para
definir las propiedades de la barra (Define Frame Properties form) para
aceptar la definición de una nueva lista de auto selección que se llamará
AUTOLATBM.

Asignar la Lista de Auto selección AUTOLATBM
La lista de Auto selección AUTOLATBM creada como se describió en la
sección anterior, consiste en varias secciones que pueden asignarse a un
elemento de la barra. Al hacer la asignación, el usuario no debe seleccionar
un punto u objeto área en el modelo, o de click en los comandos
Punto/Nodo o Shell/Area en el menú de Asignar (Assign menú).

En lugar, de que el usuario seleccione un objeto línea/barra (como una viga)
y después de clic en Assign menu > Frame/Line > en el comando Frame
Section o en el boton Assign Frame Section. De todo lo anterior resultará
la Forma de Propiedades. En el área de Propiedades de dicha forma, busque

Lista de Auto Selección 8 - 5

<!-- p. 106 -->

Guía de Introducción para el Usuario

la opción AUTOLATBM. Note que al resaltar un nombre en la lista, el
nombre aparece en la caja de edición y hasta la parte superior de la lista. De
click en el botón de OK y se completara la tarea de la (lista de auto
asignación)Auto Select Section List AUTOLATBM.

Realice una tarea al dibujar un objeto.
Una lista de Auto selección puede ser asignada cuando el objeto
barra/Línea es dibujado en el modelo. Usando este método,
seleccione la lista de Auto selección de secciones por el nombre de la
8 caja drop-down de la caja de propiedades del objeto (Properties of
Object Box) que aparece cuando se utiliza una herramienta de
dibujo. Utilice las herramientas de dibujo como se describe en el
capitulo 5 de esta guía junto con las figuras que muestran las cajas
de propiedades del objeto (Properties of Object boxes) para objetos
punto, línea y área.

Revise las secciones de la Lista de Auto selección de Secciones
Como se ha indicado previamente, en este programa se han construido
diversas Listas de Auto Selección de secciones. Para revisar las secciones
incluidas en cualquiera de dichas listas (Auto Select Section Lists), ya sea en
listas predeterminadas o en las creadas por el usuario, siga los siguientes pasos:

\1. De click en Define menu > en el comando Frame Sections o en el
botón Define Frame Sections. Aparecerá la Forma de Definición de
Propiedades de la Barra.

\2. Resalte el nombre de la Lista de Auto selección para revisarla en la lista
drop-down que se genera en la opción de Propiedades (Properties).

\3. De click al botón de Modify/Show Property (Propiedad de
Modificar/Mostrar). Aparecerá la forma de la lista de auto selección
de secciones; las secciones incluidas en dicha lista se enlistan también
en la forma principal de la forma de Área de Auto selecciones (Auto
Selections area) .

\4. De click en el botón de Cancel para cerrar la forma.

8 - 6 Lista de Auto Selección de sección

<!-- p. 107 -->

9
Capitulo 9

Edición de la Geometría del Modelo

Objetivo
Este capitulo describe como editar el modelo de forma rápida y sencilla
manteniendo su integridad.

Opciones de Edición

Durante la creación del modelo, requiere ser editado para perfeccionarlo. La

Tabla 9-1 identifica los diversos comandos de edición disponibles en

ETABS. Algunos son similares a los comandos de Windows.

En muchos de los casos, primero seleccione un objeto punto, línea o área, después

de click en el menú o botón apropiado. En algunos casos la acción será

inmediata (los comandos de deshacer “Undo” o rehacer “Redo”). En otros

Objetivo 9 - 1

<!-- p. 108 -->

casos, aparecerá una forma que permita al usuario especificar como se editará el

objeto (Edit menu > y el comando Align Points/Lines/Edges hace que

aparezca la forma (Alinear/Puntos/Lineas/Esquinas) Align

Points/Lines/Edges, misma que permite al usuario alinear puntos en las

coordenadas x, y, z o en el punto mas cercano, reducir o extender líneas).

<!-- p. 109 -->

Guía de Introducción para el Usuario

En otros casos, el comando que es un cierre que, al ser habilitado afectara las

acciones subsecuentes. Note que el tipo de comandos y opciones disponibles

depende del tipo de objeto que esta siendo editado.

9 TABLA9-1 Comandos de Edición en ETABS

Comando Acción Forma usada
Inmediatamente* o
cierre de la forma

Undo and Redo Inmediata
Undo Borra la ultima acción que se realizo.
(Deshacer y Rehacer)
Redo Restaura el ultimo paso que se deshizo.

Cut, Copy and Paste Generalmente tienen las mismas funciones que en Inmediata
(Cortar, Copiar, Pegar) Windows , con algunos comportamientos especiales
del programa ETABS. Solo se activa en el Plano o
en la Vista de Plano en Perspectiva.

Delete (Borrar) Delete Borra el objeto seleccionado (s) y todas las Inmediata
tareas que se relacionen con el (cargas, propiedades,
apoyos y otros)

Add to Model from Tem- Agrega al modelo barras bidimensionales y Formas en 2-D o
plate (Agregar a la plantilla tridimensionales. 3-D
del modelo) Que dan acceso a
otras formas

<!-- p. 110 -->

Capitulo 9 – Edición de la Geografía del

Replicate (Reproducir o Replicate reproduce uno o más objetos y la La Forma de
Duplicar) mayoría de sus tareas. Note que los objetos reproducir que
reproducidos no reemplazan a los objetos que hayan accesa a la forma de
sido colocados en ese punto. opciones

9
Edit Grid (Edición de
Cuadricula)
\> Edit Grid Data (Edición Edit Grid Data Edita el sistema de coordenadas. Forma de Sistemas
de los Datos de la Resulta una forma que permite al usuario seleccionar de Coordenadas
cuadricula) un sistema de cuadricula designado previamente; Coordinate
definir un sistema nuevo, agregar una copia de un Systems Form
sistema existente; mostrar/modificar un sistema Que accesa a las
existente; borrar un sistema existente. formas de definición
Agregar líneas en la cuadricula en puntos (definition forms)
seleccionados
La forma para
\> Add Grid at Selected "Pega" objetos punto que descansan directamente en Agregar rejillas en
Points (Agregar esas líneas de la cuadricula. Cuando un objeto punto puntos
cuadricula en puntos es pegado a una rejilla y la línea de la cuadricula se seleccionados
seleccionados) mueve, dicho objeto se mueve con ella. Los objetos se cierra.

TABLA 9-1 Comandos de Edición de ETABS
Forma que se usa
Inmediatamente/
Comando Acción
Cierre de la Forma

Opciones de Edición 9 - 3

<!-- p. 111 -->

Línea y área que se insertan en un objeto punto
cuando se mueve éste permanecen adheridos a dicho
objeto y se mueven o cambian su tamaño junto con el.
Permite al usuario mover líneas de la cuadricula
gráficamente en pantalla usando el comando Reshape
Object (Editar el Tamaño)

\> Lock OnScreen Grid Se cierra la ventana.
System Edit (Asegurar
Edición de la cuadricula
en pantalla)
Edit Story Data (Edición de Edit Story Permite cambiar los niveles del
datos de piso) piso, altura, Designación de Piso maestro (master
\> Edit Story (Editar piso) story designation). De forma similar a la designación,
empalmar puntos y altura. Permite al usuario cambiar Forma de Datos de
la elevación base del piso o nivel. Piso

\> Insert Story Inserta un nuevo piso al modelo. Permite al usuario Forma de insertar
(Insertar Piso) definir el nombre de dicho piso, su altura, el número piso
de pisos que se insertarán, la ubicación o lugar de los (Insert Story Form)
pisos y en su caso reproducir un piso de los ya
existentes para obtener un nuevo nivel en el modelo,
incluyendo sus propiedades.

\> Delete Story (Borrar Piso) Permite al usuario seleccionar y borrar un piso de su Seleccione el piso
modelo. para que aparezca la
forma para borrar
(Select Story to
Delete Form)

Edit Reference Planes Permite al usuario crear, modificar y borrar planos de Forma de Editar
(Edición de Planos de referencia. Estos planos son horizontales en Planos de Referencia
Referencia) coordenadas Z que el usuario especifica. Estos (Edit Reference
proveen un plano horizontal que puede ser usado al Planes Form)
dibujar un objeto en las vistas de elevación y para
insertar (snap) objetos (Información sobre la opción
snap esta disponible en el Menú de Ayuda)

<!-- p. 112 -->

Fusión de Puntos Forma Puntos
Merge Points Fusione los puntos dentro de una
(Merge Points) Fusionados Merge
distancia tolerante del punto que haya seleccionado.
Selected
El usuario especifica dicha tolerancia en la distancia
Points Form
en la forma correspondiente (Merge
Selected Points Form).
Alinear Align Points/Lines/Edges Esta opción permite Forma (Align
Puntos/Lineas/Esquinas alinear objetos en el modelo. Busque “edit points Selected
(Align Points/Lines/ Edges) lines edges” en el menu de Ayuda (Help menu) > y Points/Lines/
use el comando Search for Help on para localizar Edges Form)
notas importantes sobre el uso de dicho comando.

Mover Puntos/Lineas/Areas Move Points/Lines/Areas Le ayuda a mover objetos Forma Move
(Move Points/Lines/Areas) del modelo. Para mayor información, busque la Points/Lines/
opción “move points lines edges” en Help menu > Area Form
y el comando Search for Help on.

Expandir o Encojer Areas Expand/Shrink Areas Modifica el tamaño de un Forma
(Expand/Shrink Areas) objeto área usando un valor offset especificado por Expand/Shrink
el usuario. Areas Form
Fusión de Areas Merge Areas Une dos objetos área que tienen Se puede usar Undo
(Merge Areas ) una esquina común o coinciden al cubrir un objeto (deshacer)
área. Inmediatamente

<!-- p. 113 -->

Guía de Introducción para el Usuario

TABLA 9-1 Comandos de Edición de ETABS
Forma usada
inmediatamente /
Comando Accion Cierre de Ventana

Líneas de Unión (Join Lines) Join Lines Une dos o mas objetos líneas que Inmediatamente
son colineales y que tienen puntos con terminaciones puede usar Undo
comunes y la misma propiedad en un objeto línea
independiente.

Lineas de Division Divide Lines Dividen un objeto línea en objetos Forma Divide
(Divide Lines) múltiples. Selected Lines 9 Form

Sacar puntos de las líneas Crea objetos línea desde puntos. Existen opciones Forma Extrude
(Extrude Point to Lines) disponibles para extraer también objetos lineales y Point to
radiales. Esta opción es para crear vigas/columnas Lines Form
desde puntos/nodo.

Sacar lineas de las areas. Extrude Lines to Area Crea objetos área desde Forma Extrude
(Extrude Lines to Areas) líneas. Hay opciones disponibles para expulsiones Lines to
lineales y radiales. Esta opción permite crear objetos Areas Form
desde vigas.

Re-etiquetar todo Re-etiqueta todos los objetos en el modelo que esta Aviso:
Automáticamente siendo creado. Este comando no puede ser revertido Al usar este
(Auto Relabel All) después. Use este comando después de la creación del comando ya no
modelo se ha completado para obtener un puede revertirse el
re-etiquetado optimo. proceso.

Apartar de (Nudge) Funciona usando las teclas Ctrl y flecha para mover Inmediatamente
los objetos. Permite al usuario seleccionar objetos y
moverlos a una distancia pre-defnida. Para mayor
información, sobre el comando “nudge”use el menú
de Ayuda (Help menu).

\* Nota: En la forma exhibida en la ventana de ETABS window, de click a la tecla
F1 para tener acceso a la ayuda de la forma.

9 - 5

<!-- p. 114 -->

Capitulo 10

10

Análisis del Modelo

Objetivo

Este capitulo describe como analizar el modelo.

Análisis del Modelo

Para ejecutar el análisis, de click en el menú de análisis (Analyze menu > y en

el comando Run Analysis) o en el boton de Run Analysis (ejecutar

analisis), y de click en el boton de Run en la forma que aparece: Run

Options form.

El programa exhibirá una ventana con la frase (Analizando, por favor espere)

"Analyzing, Please Wait". Aparecerán datos en esta ventana mientras el

Objetivo 10 -1

<!-- p. 115 -->

programa corre el análisis. Después de que se completó el mismo, el programa

realiza otras pocas acciones “bookkeeping actions” que son evidentes en la

barra de estado que aparece en la parte inferior izquierda de la ventana de

ETABS.

<!-- p. 116 -->

Guía de Introducción para el Usuario

Cuando se ha completado el proceso de análisis, el modelo automáticamente
exhibirá una vista deformada del modelo, y el modelo será bloqueado. El
modelo se bloquea cuando el botón de Lock/Unlock Model, aparece
presionado. Bloquear el modelo previene que algunos cambios en el modelo
que podrían invalidar los resultados del análisis.

10

10 - 2 Análisis del Modelo

<!-- p. 117 -->

Capítulo 11

11

Diseño

Objetivo

Este capitulo describe el diseño usando los post-procesos de diseño de

ETABS.

Diseño de la Estructura

Los post procesos de diseño de ETABS incluyen los siguientes:

• Diseño de la barra de acero

• Diseño de la barra de concreto

• Diseño de la viga compuesta

• Diseño de la vigueta de Acero

• Diseño del Muro de carga (constantes)

Objetivo 11 - 1

<!-- p. 118 -->

Para elaborar el diseño, ejecute el análisis primero (como se describió en el

Capitulo 10), después de click en el menú Diseñar (Design menú) y

seleccionar el diseño apropiado desde menú que aparece como sub-selección.

Los tipos de diseño disponibles dependen de las piezas usadas en el modelo.

Esto es, que el usuario no puede completar un Diseño de Muro Constante si

no se han incluido Muros Constantes en el modelo.

De forma similar, los comandos usados para ejecutar un diseño
11 dependen del tipo de diseño que se realice. De cualquier modo, cada diseño tiene

comandos que llevan a lo siguiente:

• Revisar y/o seleccionar combinaciones de carga. (Review and/or
select design load combinations)

• Revisar y/o seleccionar sobre escrituras. (Review and/or select

overwrites).

• Empezar el diseño o revisar la estructura. (Start the design or check of the

structure)

• Realizar un diseño Interactivo (Perform interactive design)

• Exhibir información, datos de entrada y de salida en el modelo. (Display

input and output design information on the model)

Generalmente, la secuencia para usar los comandos se indica con su

disponibilidad. En otras palabras, algunos comandos deben ser usados antes

de que otros se conviertan en disponibles. Esto ayuda al usuario para

iniciarse en el proceso del diseño. (Busque “process” usando el menú de

ayuda Help menu para acceder a mas información sobre los procesos del

diseño “design processes” y el comando de secuencia “secuence”) La Tabla

<!-- p. 119 -->

11-1 identifica los comandos que se usan para iniciar el diseño dependiendo

del proceso deseado.

TABLA 11-1 Comandos de Inicio de Diseño
Proceso de Diseño Comando que Inicia el Diseño

Diseño de Barra de Acero Inicia Diseño/Revisión de la estructura

Diseño de barra de concreto Inicia Diseño/Revisión de la estructura
Inicia diseño usando semejanza o inicia diseño
Diseño de la Viga sin semejanza
Compuesta
Inicia diseño usando semejanza o inicia diseño
Diseño de la vigueta de sin semejanza
acero
Diseño de Muro Constante Inicia Diseño/Revisión de la estructura

11 - 2 Diseño de Estructura

<!-- p. 120 -->

Capitulo 11 - Diseño

Es importante entender que diseñar en ETABS es un proceso interactivo. Que
el usuario, es el que debe ejecutar el análisis y después realizar el diseño y
estar preparado para ejecutar el análisis nuevamente y diseñar de nuevo. Puede
ser necesario repetir el proceso varias ocasiones antes de que el diseño sea
completado. El objetivo es que el análisis de las secciones concuerden con las
secciones del diseño. El programa reportara cualquier diferencia. El usuario
debe repetir el análisis e iniciar el proceso del diseño hasta que el análisis y las
secciones diseñadas concuerden. (El programa no muestra ni exhibe un
mensaje de error).

Las Tablas 11-2 a la 11-6 resumen los comandos usados en cada tipo de proceso
de diseño.
11
Nota: Con la forma que se exhibe en la ventana de ETABS, de click a la
tecla F1 para tener acceso a la ayuda sensible al contexto de la forma.

TABLA 11-2
Comandos de Diseño de Barra de acero (Steel Frame Design Commands)
Comando Acción Forma

Selección de Grupo de Designa que un grupo es usado como un grupo de Marcos de Acero
Diseño diseño. Trabaja solamente cuando la auto selección de Forma de selección de
(Select Design Group) secciones ha sido asignada a objetos barra. A todos grupo de diseño
los objetos barra en el grupo se les dará la misma
sección de diseño.

Selección de Diseño de Permite revisar las combinaciones del diseño Designa
paquete predeterminado de la barra de acero definidas por el combinaciones de
(Select Design Combo) programa, o designación que el usuario especifique cargas de las
para diseñar esas combinaciones. Facilita la revisión o selecciones
modificaron de las cargas.

Ver/Revisar Sobre Permite revisar las sobre escrituras, que son Sobreescribe la forma
escritura parámetros que el usuario especifica para cambiar los
(View/Review valores predeterminados por el programa. Overwrites
Overwrites) se aplica a los elementos que han sido asignados
específicamente a la barra.

Definir Desplazamientos Especifica los desplazamientos de blancos u objetos Lateral
Laterales de blancos definidos, hacia cualquier dirección, para varios Displacement
(Set Lateral compartimientos de carga. Targets Form
Displacement Targets)

Diseño de Estructura 11 - 3

<!-- p. 121 -->

Guía de Introducción para el Usuario

TABLA 11-2 Comandos para el Diseño barras de Acero (de Steel Frame Design
Commands)
Comando Acción Forma

Definir objetivos de Especifica el periodo de tiempo que durara el análisis Forma Objetivos
periodos de tiempo sísmico. (sismic análisis) de períodos de
(Set Time Period Targets) tiempo

Comenzar Inicia el proceso de diseño. Si los elementos de la barra No hay forma
diseño/Revision de han sido seleccionados antes de dar clic a este comando, inmediata para
estrcutura solo se los elementos de la barra seleccionados serán ser usada.
(Start Design/Check of ingresados. Después del uso de este comando precede
Structure) un análisis de la edificación.

11
Diseño Interactivo de la Permite al usuario revisar los resultados del diseño Los resultados
barra de acero para cualquier elemento de la barra y después, deforma se muestran en
(Interactive Steel interactiva, cambiar las sobreescrituras del diseño y de pantalla.
Frame Design) forma inmediata ver los resultados.

Exhibir la Informacion Permite revisar algunos de los resultados del diseño de Forma Display
del diseno (Display barra y diseñar de forma directa en programa del Design
Design Info) modelo. Los ejemplos de los resultados pueden Results Form
exhibirse incluyendo las secciones del diseño, longitud
suelta, factores de longitud efectivos, tensiones
permisibles e información y cocientes.

Nulificar una Auto Remueve las listas de auto-selección hechas a AVISO:
selección elementos de la barra. De forma típica, se usa al final Al usar esta
(Make Auto Select del proceso interactivo del diseño, para que al final de función, no puede
Section Null) haber usado las secciones de la barra que fueron revertirse el
asignadas, no se de la auto selección de secciones. Solo proceso
funciona con una selección especifica del usuario.

Cambiar la sección del Permite al usuario cambiar la sección del diseño Forma
Diseño (Change Design asignando propiamente uno o mas elementos de la barra Select Sections
Section) y después volver a ejecutar el diseño sin antes re- Form
ejecutar el análisis. Solamente funciona con una
selección especificada por el usuario.

Reajuste de una sección Ajusta una sección del diseño para uno o varios Inmediata
del diseño para el ultimo elementos de la barra, remontándose al último análisis No es reversible.
análisis (Reset Design de dicha sección.
Section Solo funciona con una selección hecha por el usuario de
to Last Analysis) forma específica.

<!-- p. 122 -->

Verificación del análisis Verifica que el ultimo análisis realizado en la sección Inmediata
contra la sección del que se esta trabajando sea la misma para los elementos
diseño (Verify Analysis vs de la barra de acero de todo el modelo.
Design Section)

11 - 4 Diseño de la Estructura

<!-- p. 123 -->

Capítulo 11 - Diseño

TABLA 11-2 Comandos de Diseño de la Barra de Acero
Comando Acción Forma

Verificar todos las piezas Reporta si las piezas estructurales han pasado la Inmediata
Aprobadas (Verify All revisión de la capacidad de tensión. Un análisis y una
Members Passed) revisión del diseño de la estructura deben ser
completadas antes de usar este comando.

Reajuste de todas las Reajusta las sobre-escrituras de todas las secciones con AVISO: ESTA
Sobreescrituras de Acero diseño de barra de acero regresándolas a sus valores FUNCION NO PUEDE
(Reset All Steel predeterminados. SER REVERTIDA.
Overwrites)

11
Resultados de la Cancela todo el resultado del diseño de la barra de Inmediata
Cancelación del Diseño de acero pero no el diseño de la sección que se esta No se puede revertir.
Acero (Delete Steel realizando.
Design Results)

TABLA 11-3 Comandos de Diseño de Barra de Concreto.
Comando Acción Forma
Usada
Seleccionar un Paquete de Permite revisar las combinaciones de carga del diseño Design Load
Diseño (Select Design de la barra de concreto definidas por el programa, o Combinations
Combo) Designar un diseño especificado por el usuario de Selection Form
combinaciones de carga. Facilita la revisión o
modificación de cargas durante el diseño.

Ver/Revisar Sobre- Permite revisar las sobre-escrituras, mismas que son Overwrites Form
escrituras parámetros que el usuario especifica para cambiar los
(View/Review Overwrites) valores predeterminados del programa. Las sobre-
escrituras se aplican solo sobre los elementos de la
barra que han sido asignados específicamente.

Empezar diseno/Revisar Inicia el proceso del diseño. Si los elementos de la Es Inmediata,
Estructura (Start barra han sido seleccionados antes de usar este No hay forma que
Design/Check of comando, solo los elementos de la barra serán se use para ello.
Structure) designados. Este comando debe ser precedido por un
análisis de edificación.

Diseño de la Estructura 11 - 5

<!-- p. 124 -->

Diseño Interactivo de la Permite al usuario revisar los resultados del diseño No hay forma;
barra de Concreto para cualquier elemento de la barra y después cambiar Los resultados se
(Interactive Concrete de forma interactiva las sobre-escrituras del diseño, y exhibirán en la
Frame Design) ver los resultados inmediatamente. pantalla.

<!-- p. 125 -->

Guía de Introducción para el Usuario

TABLA 11-3 Comandos para el diseño de Barra de Concreto
Comando Acción Forma

Información de Revisión de algunos de los resultados del diseño de la Muestra la forma de
exhibición del diseño barra de concreto directamente en el modelo del los resultados de
(Display Design Info) programa. Los ejemplos resultantes pueden ser diseño
exhibidos incluyendo, diseño de secciones, longitudes
sueltas, y reforzamiento longitudinal.

11
Cambio de Diseño en una Permite al usuario cambiar la propiedad del diseño de Forma de selección de
sección (Change Design una o mas secciones y después volver a ejecutar el secciones
Section) diseño sin volver a ejecutar el análisis. Esta función Select Sections
solo sirve en una selección especificada por el Form
usuario.

Reajuste de Diseño de Ajusta el diseño de una sección para uno o mas Inmediata
Sección al ultimo análisis elementos de la barra regresando al ultimo análisis No se puede revertir el
(Reset Design Section usado en dicha sección. Esta función solo esa proceso.
to Last Analysis) disponible para selecciones que el usuario ha
especificado.

Verificación del análisis Verifica que el ultimo análisis de la sección diseño y Inmediata
VS Sección diseñada el diseño de la sección sean iguales para todos los
(Verify Analysis vs elementos del modelo.
Design Section)
Reajuste de todas las Reajusta las sobre-escrituras para todas las secciones de AVISO: ESTE
sobre-escrituras del la barra junto con el procedimiento del diseño de la Barra PROCESO NO
concreto (Reset All de Concreto, restituyendo los valores originales. PUEDE
Concrete Overwrites) REVERTIRSE

Cancelar los resultados Borra todos los resultados del diseño de concreto, Inmediato
del Diseño de Concreto pero no la sección de diseño en uso. (Por ejemplo, el No se puede deshacer
(Delete Concrete siguiente análisis de la sección). “Undo” la selección
Design Results) hecha.

11 - 6 Diseño de Estructura

<!-- p. 126 -->

TABLA 11-4 Comandos de Diseño de Vigas Compuestas (Composite Beam Design)
Comando Acción Forma

Selección de un Grupo de Señala que un grupo será usado como un grupo de Composite Design
Diseño (Select Design diseño (design group). Funciona solo cuando las
Group) secciones auto-seleccionadas han sido asignadas a Group Selection
objetos-barra. Cuando se agrupan, a todas las vigas en Form
el grupo se les dará el mismo tamaño, pero los
conectores y combinaciones constantes pueden ser
distintos.

<!-- p. 127 -->

Capitulo 11 - Diseño

TABLE 11-4 Comandos para Diseño de Vigas Compuestas
Comando Acción Forma Usada

Selección de Paquetes de Permite revisar los valores predeterminados de las Design Load
Diseño (Select Design combinaciones de carga para barras de concreto Combinations
Combo) definidas por el programa, o los diseños que hizo el Selection Form
usuario respecto de diseños para combinaciones de
carga. Facilita la revisión o modificación de las cargas
durante el diseño. Note que los diseños separados de
combinaciones de carga se especifican para cargas de
construcción y son especificadas considerando la
fuerza, y la carga final considerando la desviación.

11
Ver/Revisión de sobre- Permite revisar las sobre-escrituras, que son Overwrites Form
escrituras (View/Review parámetros que el usuario especifica para cambiar los
Overwrites) valores predeterminados del programa. Las sobre-
escrituras se aplican solo a las vigas que son
específicamente asignadas.

Empezar un diseño Asume que si una viga compuesta esta localizada en Inmediata
usando Simlitudes (Start un piso designado como “piso gobernador”, esa viga
Design using Similarity) compuesta tiene el mismo tamano que el de la viga
compuesta de los pisos gobernador .
(Para definir de un piso similar a un Piso Gobernador
en los datos del piso busque Edit menu > Edit Story
Data > y el comando Edit Story.)

Empezar un Piso sin Excluye la función de similitudes descrita en la Inmediata
similitudes (Start Design función anterior. Solo puede aplicarse a una selección
without Similarity) que especificó el usuario. SIEMPRE utilice este
comando para el diseño final.

Diseño Interactivo de Permite al usuario revisar los resultados del diseño No hay forma; los
Viga Compuesta para cualquier viga compuesta y después hacer el resultados se exhiben
(Interactive Composite cambio de forma interactiva, se hará una sobre- en la pantalla.
Beam Design) escritura en el diseño e inmediatamente se puede ver
el resultado.

Diseño de Estructura 11 - 7

<!-- p. 128 -->

Exhibir Información del Permite revisar algunos de los resultados de la viga Display Design
Diseño (Display Design compuesta designándolos directamente en el modelo Results Form
Info) del programa. Los ejemplos de los resultados que
pueden ser exhibidos incluyen etiquetas y los nombres
de los grupos de diseño; secciones diseñadas junto
con las disposiciones de las conexiones,
combinaciones y reacciones del final; e información
de cocientes y tensión.

<!-- p. 129 -->

Guía de Introducción para el Usuario

TABLA 11-4 Comandos para Diseño de Vigas Compuestas
Comando Acción Forma

Nulificar una Auto- Remueve las listas de auto selección de las vigas No se puede revertir
Selección de Sección seleccionadas. De forma típica, se usa cerca de el proceso
(Make Auto Select terminar el proceso interactivo de diseño, así que al
Section Null) final de que se realizo la interacción usando
secciones asignadas de la vigas, no auto seleccionar
secciones. Solo funciona en secciones especificadas
por el usuario.

11
Cambiar el Diseño de la Permite al usuario cambiar el diseño de una sección Select Sections
Sección (Change Design propiamente asignada a una o mas vigas y después Form
Section) volver a ejecutar el diseño sin antes re-ejecutar el
análisis. Solo funciona en selecciones especificadas
por el usuario.
Reajustar la sección del Ajusta el diseño de una o mas barras regresando al Inmediatamente
Diseño al ultimo análisis último análisis usado en dicha sección. Esta función No puede usarse
(Reset Design Section solo esa disponible para selecciones que el usuario ha Undo después, no
to Last Analysis) especificado. puede revertirse.
Verificación de análisis Verifica que el último análisis usado de esa sección y Inmediatamente
Vs Sección de Diseño el diseño que esta siendo usado sean los mismos para
(Verify Analysis vs todas las vigas compuestas del modelo.
Design Section)
Verificar todas las piezas Reporta si los miembros o piezas estructurales han Inmediatamente
pasadas (Verify All pasado la revisión de tensión/capacidad. Se debe
Members Passed) completar un análisis y un ingreso/revisión de la
estructura antes de usar este comando.

Reajustar todos las sobre- Reajusta las sobre-escrituras que se han hecho en el AVISO: AL USAR
escrituras de las Vigas proceso de diseño de las vigas compuestas ESTE COMANDO
compuestas (Reset All regresándolas a sus valores predeterminados. NO SE PUEDE
Composite USAR UNDO
Beam Overwrites)
Cancelar los resultados Borra todos los resultados del diseño de la viga Inmediata
de la Viga Compuesta compuesta pero no el diseño de la sección en curso No se puede utilizar
(Delete Composite (como el análisis de la sección siguiente) la tecla Undo
Beam Results)

<!-- p. 130 -->

TABLE 11-5 Comandos para el Diseño de la Vigueta de Acero (Steel Joist Design)
Comando Acción Forma

Selección de un Grupo de Señala que un grupo será usado como grupo de diseño Composite Design
Diseño (Select Design (design group). Funciona solamente cuando se ha
Group) auto-seleccionado una sección y se ha asignado a un Group Selection
nodo o nodos. Al agruparse se da a todos los objetos Form
del grupo el mismo tamaño del nodo.

11 - 8 Diseño de Estructura

<!-- p. 131 -->

Capitulo 11 - Diseño

TABLA 11-5 Comandos para el Diseño de Viguetas de Acero (steel joist)
Comando Acción Nombre de
la Forma
Selección de Paquetes de Permite revisar las combinaciones de las cargas del Forma de
Diseño (Select Design diseño de la vigueta de acero que han sido definidas selección de
Combo) en el programa, o los diseños de combinaciones de combinaciones de
carga que el usuario realizo de forma especifica. carga
Facilita la revisión o modificación de las cargas
durante el diseño.

Ver/Revisión de Sobre- Permite revisar las sobre-escrituras que especifican Sobreescribe la
escrituras (View/Review cuales son los parámetros que el usuario especifica forma
Overwrites) para cambiar los valores predeterminados del
programa. Las sobre-escrituras se aplican solo a las
viguetas de acero que han sido específicamente
asignadas.
11
Empezar un diseño Se asume que si una vigueta de acero se localiza en un Inmediatamente,
usando similitudes (Start piso designado como piso similar o piso maestro, esa no se utiliza
Design using vigueta tendrá la misma medida que las del piso forma alguna
Similarity) gobernador (para ajustar de un piso similar a un piso
gobernador “story Similar To a master Story” en los
datos de piso; busque Edit menu > Edit Story Data >
y despues el comando Edit Story).

Empezar un diseño sin Excluye las opciones de las similitudes descritas en la Inmediatamente,
similitudes (Start Design opción anterior. Se puede aplicar solamente a una no existe forma
Without Similarity) selección especificada por el usuario. SIEMPRE se para usarse con
usa este comando en el diseño final. esta función.

Diseño Interactivo de la Permite al usuario revisar los resultados del diseño No hay forma;
vigueta de Acero para cualquier vigueta de acero y después cambiar las los resultados se
(Interactive Steel Joist sobre-escrituras de ésta de forma interactiva, e exhiben en la
Design) inmediatamente ver los resultados. pantalla.

Diseño de Estructura 11 - 9

<!-- p. 132 -->

Exhibir la Información Permite revisar algunos de los resultados del diseño Aparece la forma
del Diseño (Display de la vigueta de acero directamente en el modelo del Display Design
Design Info) programa. Los ejemplos de los resultados que pueden Results Form
ser exhibidos incluyen los rótulos de las viguetas y
algunos nombres de grupos de diseño; designación de
secciones junto con sus reacciones y los cocientes de
información del diseño.

<!-- p. 133 -->

Guía de Introducción para el Usuario

TABLA 11-5 Comandos para el diseño de Viguetas de Acero
Comando Acción Forma

Nulificar la Auto Remueve las listas de Auto selección desde las AVISO: ESTE
Selección de Sección viguetas seleccionadas. Se usa típicamente casi al PROCESO NO SE
(Make Auto Select final de que se ejecuto la interacción del diseño PUEDE REVERTIR
Section Null) usando las secciones de las viguetas con las que se
esta trabajando, no con auto-selecciones. Solo
funciona con selecciones especificadas por el usuario.

11
Cambio del diseño de la Permite al usuario cambiar el diseño de una sección Select Sections
sección (Change Design propiamente asignada a una o mas viguetas y después Form
Section) volver a ejecutar el diseño sin antes re-ejecutar el
análisis. Solo funciona en selecciones especificadas
por el usuario.
Verificar análisis Vs Verifica que el último análisis de esa sección y el Inmediatamente
Diseño de Sección (Verify diseño de la sección en curso sea la misma para todas
Analysis vs las viguetas de acero del modelo.
Design Section)
Verificar todos los Reporta si una vigueta de acero ha pasado las Inmediatamente
miembros aprobados revisiones tensión/capacidad. Debe existir un análisis
(Verify All Members previo de Ingreso/Revisión de la estructura antes de
Passed) usar este comando.

Reajuste de Todas las Reajusta las sobre-escrituras en todas las viguetas de AVISO: ESTA
sobre-escrituras de acero, restituyendo los valores predeterminados en su FUNCION NO
Viguetas de Acero (Reset proceso de diseño. PUEDE
All Steel Joist REVERTIRSE
Overwrites) Cannot use Undo
Cancelar los resultados Borra todos los resultados del diseño de viguetas pero Inmediatamente
de Viguetas de Acero no el diseño en curso de la sección. (el análisis de la No se puede usar Undo
(Delete Steel Joist siguiente sección).
Results)

TABLA
Comando Acción Forma

11 - 10 Diseño de Estructura

<!-- p. 134 -->

Selección de Paquetes de Permite revisar los valores predeterminados de las Design Load
Diseno (Select Design combinaciones de carga de los diseños de muros
Combo) constantes y la designación que hace el usuario de las Combinations
combinaciones de carga que especifica. Facilita la Selection Form
revisión o modificación de las cargas durante el
diseño.

<!-- p. 135 -->

Capitulo 11 - Diseño

TABLA 11-6 Comandos para el diseño de Muro Constante (Shear Wall Design)
Comando Acción Nombre de la
Forma

Ver/Revisar Sobre- Permite revisar las sobre-escrituras de pilas, que son Overwrites Form
escrituras en Pila parámetros que el usuario especifica para cambiar los
(View/Review Pier valores predeterminados del programa. Esta función
Overwrites) se aplica solo a los pilares que hayan sido
específicamente asignados.

Ver/Revisar Sobre- Permite revisar las escrituras en spandrel, que son Overwrites Form
escrituras en Spandrel parámetros que el usuario especifica para cambiar los
(View/Review Spandrel valores predeterminados del programa. Esta función
Overwrites) se aplica solo a los spandrels que hayan sido
específicamente asignados.

11
Definir Secciones de Permite al usuario definir una sección del pilar usando Define General
Pilares Generales (Define una sección utilitaria de diseño. Pier Sections
General Pier Sections) Form

Asignar Secciones Tipo Permite al usuario asignar a una pila una de tres tipos Assign Pier
Pilar (Assign Pier de secciones. Sections Form
Sections Type)

Empezar diseno/Revision Inicia el proceso de diseño. Si la pila o spandrel ha Inmediata, no se usa
de Estructura sido seleccionado antes de usar este comando, solo las forma
(Start Design/Check of piezas seleccionadas serán designadas. Se requiere de
Structure) un análisis previo al usar este comando.

Diseño Interactivo de Permite al usuario revisar los resultados del diseño No hay forma; los
Muro (Interactive Wall para cualquier pilar o spandrel y después de forma resultados
Design) interactiva cambiar el diseño de la sobre-escritura y Aparecen en pantalla.
ver inmediatamente los resultados.

Exhibición de la Permite revisar algunos de los resultados del muro Display Design
Información del Diseño constante designando directamente en el modelo del Results Form
(Display Design Info) programa. Los ejemplos de los resultados pueden
exhibirse, incluyendo sus requerimientos de refuerzo,
requerimientos de cociente y limites de capacidad.

Diseño de Estructura 11 - 11

<!-- p. 136 -->

Reajustar Todas las Restaura las sobre-escrituras para todos los pilares o NO SE PUEDE
sobre-escrituras de Pilar spandrels a sus valores iniciales. REVERTIR
(Reset All Pier/
Spandrel Overwrites)

Cancelación de Muros Cancela todos los resultados de los muros constantes. Inmediata
Constantes (Delete Wall No se puede usar Undo
Design Results)

<!-- p. 137 -->

Capitulo 12

12
Exhibiciones Graficas

Objetivo

Este capitulo describe como exhibir gráficamente los resultados del análisis.

Obtención de Exhibiciones Graficas Básicas
Los resultados de los análisis pueden exhibirse gráficamente después de
ejecutarse el análisis. Para exhibirlos, de clic en el Display menu y seleccione
el tipo de exhibición que se desea. La Tabla 12-1 identifica las opciones de
exhibición.

Objetivo 12 - 1

<!-- p. 138 -->

Guía de Introducción para el Usuario

TABLA 12-1 Menú de Opciones de Exhibición
Comando Acción Nombre de la
Forma*
Mostrar Figura No existe forma para
Traza la figura indeformable en pantalla
indeformable (Show dicha acción; los
Undeformed Shape ) resultados
son exhibidos.

Mostrar Cargas (Show
Loads)
\> Nodo/ Punto Muestra las cargas asignadas a puntos Show Joint/Point
(Joint/Point) Loads Form
\> Frame/Line Show Frame/Line Muestra las cargas asignadas a Líneas.
(Barra/Linea) Loads Form
\> (Shell/Area) Show Shell/Area
Muestra las cargas asignadas a Áreas. Loads Form

12
Definir Tabla de Entrada Este modo provee al usuario la oportunidad de Data Tables Input
(Set Input Table Mode) completar una revisión en pantalla de los Form
parámetros de entrada usados en la edificación del
modelo.

Mostrar Figuras Exhibe la figura deforme de forma estática en Deformed Shape
deformadas pantalla y basada en cargas especificadas por el Form
(Show Deformed Shape) usuario. Esta muestra puede contener animación.

Mostrar el modo de la Muestra una figura deformada que se basa en los Mode Shape Form
Figura (Show Mode Shape) modos especificados por el usuario. También puede
contener animación.

12 - 2 Obtención de Exhibiciones Graficas Básicas

<!-- p. 139 -->

Mostrar las fuerzas de las
Piezas/ Diagrama de
Tension (Show Member
Forces/
Stress Diagram)

\> Reacciones de Exhibe las reacciones de soporte y resorte basadas Point Reaction
Soporte/Resorte en cargas especificadas por el usuario.
(Support/Spring Forces Form
Reactions)

\> Fuerza de Exhibe las fuerzas de columna, viga, apoyo, pila y Member Force
Barra/Pila/Spandrel spandrel basadas en las cargas que el usuario
(Frame/Pier/Spandrel especifica Diagram for
Forces) Frames Form
Element

\> Shell Stresses/ Muestra las fuerzas de los elementos internos del Force/Stress
Forces shell y sus tensiones, basados en las cargas que el Contours for
usuario especifica Shells Form

Muestra las fuerzas de conexión basadas en cargas Member Force
\> Link Forces especificadas por el usuarios Diagram Form

<!-- p. 140 -->

Capitulo 12 – Exhibiciones Graficas

TABLA 12-1 Menú de Opciones de Exhibición
Comando Acción Forma*

Mostrar Diagrama de Muestra el diagrama de trabajo energía/virtual que Energy/Virtual
Trabajo de Energia/Virtual puede ser usado como una ayuda para determinar Work Diagrams
(Show Energy/Virtual que elementos deben ser densificados para un
Work Diagram) control mas eficiente de desplazamientos laterales
de la estructura. El usuario define las fuerzas y
desplazamientos.

Mostrar la respuesta a las Muestra las diversas respuestas a espectros después Response
curvas del espectro (Show de que se ejecuto un análisis de historia de tiempo. Spectrum
Response Spectrum Curves) Generation Form

12
Mostrar Trazos de Historia Muestra varias curvas históricas basadas en los Time History
de Tiempo datos especificados por el usuario después de Display
(Show Time History Traces) ejecutar el análisis correspondiente Definition Form

Mostrar la curva pushover Muestra las curvas pushover basadas en datos Pushover Curve
Estática (Show Static especificados por el usuario después de ejecutar un Form
Pushover Curve) análisis no linear .

Ajustar Modo de Tabla de Permite al usuario seleccionar el tipo de Display Output
salida (Set Output Table información para ser incluida en la tabla de salida. Tables Form
Mode)

Obtención de Exhibiciones Graficas Básicas

12 - 3

<!-- p. 141 -->

\* Nota: Con la forma exhibida en la ventana de ETABS, de click en la tecla F1 para tener
acceso a la ayuda sensible al contexto de la forma.

<!-- p. 142 -->

Capitulo 13

Generar Resultados 13

Objetivo
Este capitulo describe como generar el análisis y diseño de los resultados
que pueden ser enviados a una impresora o a un archivo para compartir la
información con otros programas.

Análisis y Diseño de Resultados
Estos pueden ser enviados a una impresora o a un archivo usando los
comandos del menú de archivo (File menú). La Tabla 13-1 identifica los
comandos de impresión.

Objetivo 13 - 1

<!-- p. 143 -->

Guía de Introducción para el usuario

TABLA 13-1 Opciones del Menú de Archivo para Impresión
Comando Acción Forma*

Ajuste de Impresión (Print Permite al usuario especificar el tamaño de papel y la Print Page Setup
Setup) orientación de la página. Form

Vista Preliminar de Permite apreciar una vista preliminar de como será No disponible
Impresión de Graficos impreso el archivo en un formato grafico.
(Print Preview for
Graphics)

Impresion de Graficos Imprime cualquier grafico que se exhibe en la ventana activa deNo disponible
(Print Graphics) la impresora que se especifica como en uso.

13 Print Tables
\> Input (Datos entrada) Imprime los datos de entrada del análisis Print Input

O los envía a un archivo de texto. Tables Form

\> Analysis Output Imprime las tablas de los datos de salida Print Output
(Análisis de datos de
Salida)
O los envía a un archivo de Texto Table Form

\> Print Design ( Imprimir Imprime las tablas de diseño de los datos de salida o Print Design
Diseño) el archivo del texto según lo designe el usuario y
basado en la selección de Barras de Acero, Barras de
Concreto, Vigas Compuestas, Viguetas de Acero y
Muros Compuestos.
Table (Tablas) Tables Form

13 - 2 Resultados y exhibición de Análisis

<!-- p. 144 -->

ETABS®
Software Diseño Integral para Edificaciones

Tutorial

Computers and Structures, Inc.
Berkeley, California, USA
Version 9
November 2005

<!-- p. 145 -->

Derechos Reservados

El programa de computación ETABS y toda la documentación asociada a ella
constituyen propiedad y derechos reservados. A nivel mundial los derechos de propiedad
recaen sobre la persona moral denominada Computers and Structures, Inc. El uso de este
programa o la reproducción de su documentación en cualquiera de sus formas, requiere
de autorización por escrito de la empresa denominada Computers and Structures, Inc.,
queda estrictamente prohibido cualquier uso sin dicha autorización.

Para mayor información y obtención de copias de esta documentación refiérase a:

Computers and Structures, Inc.
1995 University Avenue
Berkeley, California 94704 USA

Teléfono: (510) 845-2177
FAX: (510) 845-4096
e-mail: info@csiberkeley.com (para información general)
e-mail: support@csiberkeley.com (Soporte Técnico)
Pagina web: www.csiberkeley.com

\~ Copyright Computers and Structures, Inc., 1978-2005.
El logo CSI constituye una marca registrada de Computers and Structures, Inc.
ETABS es una marca registrada deComputers and Structures, Inc.
“Watch & Learn” es una marca registrada de Computers and Structures, Inc.
Windows es una arca registrada de Microsoft Corporation.
Adobe y Acrobat son marcas registradas de Adobe Systems Incorporated.

<!-- p. 146 -->

ADVERTENCIA

SE HAN INVERTIDO TIEMPO CONSIDERABLE, ESFUERZO Y GASTOS HACIA
EL DESARROLLO Y DOCUMENTACION DE ETABS. EL PROGRAMA HA SIDO
PROBADO Y USADO DETENIDAMENTE. DE CUALQUIER MODO, AL HACER
USO DEL PROGRAMA, EL USUARIO ACEPTA Y ENTIENDE QUE NO EXISTE
GARANTIA IMPLICITA DE LOS DESARROLLADORES O DISTRIBUIDORES
EN LA PRECISION O CONFABILIDAD DEL PROGRAMA.

EL USUARIO DEBE ENTENDER EXPLICITAMENTE LOS SUPUESTOS DEL
PROGRAMA Y DEBE VERIFICAR LOS RESULTADOS DE FORMA
INDEPENDIENTE.

<!-- p. 147 -->

Tutorial

Un Ejemplo de Modelo
El Proyecto 4

Paso 1 Inicie un Nuevo Modelo 5
Definir una lista de secciones auto seleccionadas 8

Paso 2 Agregar Objetos Line 9
Configuración para agregar objetos a múltiples
Niveles simultaneamente 9
Dibujar objetos columna 11
Guadar el modelo 16
Dibujar los objetos vigas resistentes a las fuerzas laterales 16
Dibujar los objetos vigas secundarias (Infill) 18

<!-- p. 148 -->

Paso 3 Agregar Objetos Area 20
Dibujo de los objetos del area del piso 20
Agregar el area de objetos dummy usado para la
Aplicación de la carga de viento 23
Agregar objetos en la vista de elevación 24
Agregar objetos en la vista en planta 25

Paso 4 Definición de los casos de carga estática 26
Paso 5 Asignar cargas de gravedad 31
Paso 6 Definir una elevación desarrollada 35
Paso 7 Asignar cargas de viento 39
Paso 8 Revisión de la base de datos de ingreso en database display 43
Paso 9 Ejecutar el análisis 46
Paso 10 Revisión grafica de los resultados del análisis 46
Paso 11 Diseño de vigas compuestas 48
Paso 12 Diseño del elemento acero 54

Tutorial

<!-- p. 149 -->

Un Ejemplo de Modelo

Este manual proporciona instrucciones paso a paso para construir un modelo básico
de ETABS. Cada paso del proceso de creación del modelo es identificado, y varias
técnicas de construcción del modelo son introducidas. Al finalizar este capitulo, usted
habrá construido el modelo mostrado en la figura 1.

Figura 1
Un ejemplo
de un Modelo

<!-- p. 150 -->

El Proyecto

El ejemplo del proyecto es un edificio de cuatro pisos de forma irregular. El
primer piso es 15 pies de alto y los pisos 2,3 y 4 cada uno tienen 12 pies de
alto. Los vanos tienen 24 pies en las direcciones X e Y.

El sistema resistente de la fuerza lateral consiste en pórticos intersecados
entre si. Las losas de pisos consisten en concreto de 3 pulgadas sobre una
plancha metálica de 3 pulgadas de espesor. Las vigas secundarias son
diseñadas como vigas compuestas. Las vigas resistentes a la fuerza lateral que
conectan las columnas están diseñadas como vigas no compuestas.

El arquitecto para el edificio ha requerido que la altura máxima de la viga no
exceda el de una viga W18 para permitir la suficiente separación para la
c a n a l i z a c i ó n q u e f u n c i o n a d e b a j o d e l a s v i g a s .

Paso 1 Inicie un Nuevo Modelo

En este paso, se fijan las direcciones y alturas de los pisos. Luego, se define
una lista de secciones que se ajusten a los parámetros solicitados por el
arquitecto para el diseño.

A. Si las unidades mostradas en la caja de dialogo en la esquina inferior
derecha de la ventana de ETABS no están en Kip-in, seleccionar de
esta
caja de dialogo para fijar las unidades a Kip-in.

B. Hacer clic en el comando File Menu > New Model o en el botón New

<!-- p. 151 -->

Model . Se presentará el formulario mostrado en la figura 2.

Figura 2
Formulario
New Model
Initialization

<!-- p. 152 -->

C. Seleccionar el botón No en el cuadro anterior y aparecerá el cuadro
mostrado en la Figura 3. El Formulario Building Plan System and Story
Data es usado para especificar el espaciamiento de las líneas de la grilla
horizontal, los datos de los niveles y en algunos casos, modelos de plantillas.
Los modelos de plantillas proporcionan una rápida y fácil forma de iniciar su
Nota: modelo. Automáticamente, estos modelos agregan objetos estructurales con
Más propiedades apropiadas a su modelo. Se recomienda que usted inicie sus
informacio
n acerca de
las
plantillas
está
disponible
buscando
“template”
usando el
comando,
Help
Menu >
Search for
Help

<!-- p. 153 -->

modelos usando plantillas cada vez que sea posible. Sin embargo, en este
ejemplo, el modelo es creado desde la grilla, en vez de usar una plantilla.

D. Digitar 4 en la caja Number of Stories para fijar el número de pisos.

E. Digitar 15 ft dentro de la caja Bottom Story Height y presionar la
tecla Enter de su teclado. Note el programa automáticamente convierte los 15
ft a 180 porque las unidades configuradas son kips y inches (15 feet = 180
FiguraFigura 43 inches).
FormularioVentana
Buildingprincipal Plande F. Seleccionar el botón Grid Only.
GridETABSSystem
and Story
Data
Definition

<!-- p. 154 -->

G. Hacer clic en el botón Ok para aceptar sus cambios.

Cuando usted haga clic en el botón Ok, su modelo aparece en la ventana principal de
ETABS con dos sub ventanas verticales, en la ventana de la izquierda aparece una
vista en planta y en la ventana de la derecha una vista en 3D, como lo mostrado en la
Figura 4. El número de sub ventanas pueden ser cambiadas usando el comando
Options Menu > Windows.

<!-- p. 155 -->

Note que la vista en Planta esta activa en la figura 4. Cuando la ventana esta activa, la
barra de titulo esta resaltada. Fije una ventana activa clickeando en cualquier lugar de
la ventana a activar. Si usted cambia las vistas de las ventanas, regrese a las descritas
por defecto en el párrafo anterior con activar Plan View, antes de continuar con el
siguiente paso de este manual.

Definir una lista de Secciones Auto Seleccionadas

Una lista de secciones auto seleccionadas es simplemente una lista de secciones, por
ejemplo, W18X35, W18X40, W21X44, W21X50 y W24X55. Estas listas pueden ser
asignadas a elementos estructurales. Cuando una lista de secciones auto seleccionadas
esta asignada a un elemento estructural, el programa automáticamente puede
seleccionar el más económico, la sección más adecuada de la lista cuando esta
diseñando el elemento.

El programa tiene muchas listas de sección auto seleccionadas incorporadas. Algunas
de estas listas serán utilizadas as adelante en estas instrucciones. Debido a que el
arquitecto requiere que las vigas no sean más altas que W18, es útil crear una lista de
secciones auto seleccionadas que contengan vigas W16 y W18.

A. Hacer clic en el comando Define menú > Frame sections, aparecerá el
formato
Figura 5 Define Frame Properties mostrado en la figura 5.
Formulario
Define Frame
Properties

<!-- p. 156 -->

B. Hacer click en el caja de diálogo en la que se lee “Add I/Wide Flange” en el
área Click to del formulario Define Frame Properties. Seleccionar con un
doble
click Add Auto Select List entre la lista de resultado de secciones. El
formulario de secciones de auto selección aparece igual a lo mostrado en
Figura 6.

C. Digitar AUTOLATBM en la caja de edición Auto Section Name.
D. Hacer clic sobre la viga W16x26 una vez encontrada dentro de la lista de
secciones de vigas.

E. Mover la barra espaciadora en la lista de secciones de viga en List of Sections
para encontrar la viga W18x175. Presionar la techa Shift en su teclado y luego

<!-- p. 157 -->

hacer click una vez sobre la viga W18x175. Usted ahora deberá tener todas las
vigas entre la W16x26 y W18x175 resaltadas.

Figura 6
Formulario
Auto Select
Sections

Figura 6.- Formulario

F. Hacer click en el botón Add para agregar las vigas seleccionadas a la lista
Auto
Selection del lado derecho del formulario.

<!-- p. 158 -->

G. Hacer clic en el botón Ok y luego en el botón Ok del formulario Define
Frame
Properties para aceptar sus cambios.

Paso 2 Agregar Objectos Linea

En este paso, el programa esta configurado para agregar objetos a múltiples
niveles simultáneamente. Luego los objetos estructurales son agregados al
modelo.

Configuración para agregar objetos a múltiples niveles
simultáneamente

Asegúrese que la ventana Plan View este activa. Para hacer una ventana
activa, mover el cursor, o la flecha del mouse, sobre la lista y hacer click con
el botón izquierdo del mouse. Cuando la vista esta activa, la barra de titulo
esta resaltada. La localización de la barra de titulo esta indicada en la Figura
\4.

A. Hacer clic en la caja de dialogo en la que se lee “One Story” en la
parte
inferior derecha de la ventana principal, la cual es mostrada en la
igura 4.

B. Resaltar Similar Stories en la lista. Esto activa la opción Similar

<!-- p. 159 -->

Stories para dibujar y seleccionar objetos.

C. Para revisar las definiciones actuales del Similar Story, hacer clic en
comando Edit menú > Edit Story Data > Edit Story. El formulario
Story Data aparece mostrado en la Figura 7. Note el Master Story y
las columnas del Similar Story en el formulario.

Con la opción Similar Story activa, las adiciones o cambios son
hechos
a un nivel – por ejemplo, Nivel 4 – esas adiciones y cambios también
serán aplicadas a todos los niveles que han sido diseñados como
Similar To Story 4 en el formulario Story Data. Por defecto, el
programa ha definido Story 4 como un nivel maestro (Master Story)
como se muestra en la Figura 7, los niveles 1,2 y 3 son similares al
nivel 4. Esto significa que, con Similar Story activo, cualquier dibujo
o presentación seleccionada de cualquier nivel se aplicaran a todos los
otros niveles. Un nivel puede se configurado como Similar To NONE
de modo que las adiciones o cambios no lo afectaran.

D. No haremos ningún cambio al formulario, de modo que presione el
botón Cancel para cerrar el formulario.

<!-- p. 160 -->

Figura 7.- Formulario Story Data

<!-- p. 161 -->

Dibujar Objetos Columna

Asegúrese que la Vista del Plan es activa.

A. Hacer click en el botón Create Columns in Region or at Clicks o use el
comando Draw menu> Draw Line Objects> Create Columns in Region or at
Clicks. Aparecerá la caja de dialogo Properties of Objet para columnas como se
muestra en la Figura 8.

Figura 8.- Caja Properties of Objects (Propiedades del Objeto)

Si la caja Properties of Object está ocultando cualquier parte del modelo en cualquier
vista, presionarla y arrastrarla hacia otra posición. Para mover el formulario, hacer clic
en la barra del titulo Properties of Object de la caja, mantener presionado el botón
izquierdo del mouse y arrastrarlo fuera del formulario.

B. Asegúrese que el item Property del formulario Properties of Object esta
configurado como A-LatCol. Si no es así, hacer click una vez, en la caja de edición
opuesta al ítem Property para activar la caja de dialogo y luego seleccionar A-LatCol
de la lista resultante. A-LatCol es una lista de secciones auto seleccionadas
incorporadas con el propósito de ser usada para las columnas resistentes a la fuerza
lateral.

Si usted quiere revisar las secciones incluidas en A-LatCol, o cualquier otra lista de

<!-- p. 162 -->

sección auto seleccionada, (1) hacer clic una vez, en el comando Define menu>
Frame Sections o hacer click en el botón Define Frame Sections. Aparecerá el
formulario Define Frame Properties, (2) Resaltar A-LatCol en la lista de la caja
Properties. (3) Hacer click en el botón Modify / Show Property. Aparecerá el
formulario Auto Selection Sections; y en el área Auto Selección del formulario son
mostradas la secciones incluidas en la lista A-LatCol. (4) Hacer clic en el botón
Cancel para cerrar el formulario.

C. Hacer click en la caja de edición Angle del formulario Properties of Object y
configurar el ángulo de 90. Esto significa que por defecto las columnas rotaran 90
grados desde su posición.

D. Para dibujar la primera columna, hacer solo un click izquierdo dentro de la
Vista en Planta de la intersección de las líneas D y 1 de la grilla. Aparecerá en ese
punto una columna-I formada dentro de la Vista en Planta. También, en la vista 3D,
observe que la columna mostrada se extiende sobre todos los niveles a pesar de que la
columna fue dibujada en un solo nivel. Esto ocurre porque la propiedad de Similar
Stories esta activa. Obsérvese que la propiedad de Similar Stories solo se aplica
cuando las adiciones o cambios se realizan al modelo en la Vista en Planta. La
propiedad Similar Stories no se aplica cuando las adiciones o cambios se realizan en
las Vistas de Elevaciones o de 3D.

E. Hacer un solo click dentro de la Vista en Planta en la intersección de las líneas
D y 2 de la grilla para dibujar la segunda columna.

F. Ahora cambie el item Angulo dentro del formulario Propiedades del Objeto
(Properties of Object) de 90 a 0.

<!-- p. 163 -->

Figura 9- Dibujo de objetos columna dentro de una región seleccionada

G. Ahora dibujar las columnas restantes de una sola acción seleccionando un área
alrededor de la intersección de la grilla como se muestra en la Figura 9. Para hacer
esta selección, hacer click con el botón izquierdo del mouse sobre la parte superior
izquierda de la intersección de los ejes A-4 y luego, mientras sostiene el botón

<!-- p. 164 -->

izquierdo del mouse, arrástrelo hasta que se encuentre en la parte inferior derecha de
la intersección de los ejes C-1. Una caja de la selección similar a esa demostrada en el
cuadro 9 debe ampliarse alrededor de las líneas de intersección de la grilla mientras
que el mouse se arrastra a través del modelo. Suelte el botón izquierdo del mouse y el
programa dibujará los objetos de la columna en la intersección de los ejes.

Observe que estas columnas aparecerán giradas 90 grados con respecto a las dos
primeras.

H. Hacer click en el botón Select Object, para cambiar el programa del modo
Dibujo al modo Selección.

I. Mantener presionada la tecla Ctrl de su teclado y hacer un click
izquierdo en la Vista en Planta sobre la columna A-2. Una lista de la selección
similar a la presentada en la Figura 10 se mostrará debido a que múltiples
objetos existen en la ubicación que se selecciono. En este ejemplo, un objeto
punto y un objeto columna existen en la misma ubicación. Obsérvese que la
lista de selección solo aparecerá cuando la tecla Ctrl sea usada con el botón
izquierdo del mouse.

<!-- p. 165 -->

Figura 10- Formulario Selection List

J. Seleccionar la columna de la lista haciendo click sobre ella. Ahora la
columna en A-2 esta seleccionada. La columna estará seleccionada en su
totalidad debido a que la propiedad Similar Stories esta activa. Obsérvese que
la barra de estado en la esquina inferior derecha de la ventana principal de
ETABS indica que se han seleccionado 4 líneas.

K. Repetir el proceso de selección en B-2, A-3, C-3 y C-4. La barra de
estado debe indicar que se han seleccionado 20 líneas.

L. Hacer click en el comando Assign menu > Frame/Line > Local Axes
para presentar el formulario mostrado en la Figura 11.

<!-- p. 166 -->

Figura 11- Orientación de Ejes para columnas

Nota: Cuando son presentados los ejes locales, la codificación para el color
de las flechas es rojo, blanco y azul siempre, correspondientes a los ejes 1,
2 y3 respectivamente.

M. Hacer click en la opción Column Major Direction is Y en el formulario
y luego hacer click en el botón OK. Las columnas seleccionadas serán rotadas
90 grados.

Note las flechas de color asociadas a cada columna. Estas flechas indican las
direcciones de los ejes locales. La flecha roja esta siempre en la dirección del
eje local 1, la flecha blanca esta en la dirección del eje local 2 y la flecha azul
esta en la dirección del eje local 3. Por defecto, la flecha roja no es visible
porque esta (y por lo tanto el eje local 1 de la columna) es perpendicular a la
pantalla.

Una forma fácil de recordar la codificación para el color de los ejes es pensar

<!-- p. 167 -->

en la bandera Americana. La bandera Americana es roja, blanca y azul. La
codificación para el color de los ejes es rojo = 1, blanco = 2 y azul = 3.

Hacer click en el comando Assign menu > Clear Display of Assigns para
ocultar las flechas de la pantalla.

El modelo debe aparecer como se muestra en la Figura 12.

<!-- p. 168 -->

Nota: ¡Guarde su modelo con frecuencia!

Guardar el Modelo

Guardar el modelo con frecuencia durante el desarrollo. Aunque normalmente
se puede guardar con el mismo nombre, por lo tanto sobrescribiendo los
previos modelos, usted podrá de vez en cuando guardar sus modelos con un
nombre diferente. Esto le permite llevar un registro de su modelo en varias
etapas de su desarrollo.

A. Hacer click en el comando File menu > Save, o en el botón Save, ,
para guardar su modelo. Especifique el directorio en donde desea guardar su
modelo y, para este ejemplo, especifique el nombre del archivo como Steel
Frame.

Dibujar los objetos viga resistente a las fuerzas laterales

Asegúrese de que la vista en planta este activa. Dibujar las vigas entre las
columnas usando los siguientes pasos:

A. Hacer click en el botón Create Lines in Region o en el botón en
el comando Draw menu > Draw Line Objects > Create Lines in Regions or
at Clicks. La caja Properties of Object para objetos línea aparecerá como en la
Figura 13.

<!-- p. 169 -->

Figura 13- Caja Properties of Object

B. Hacer click una vez en la caja de edición opuesta al item Property para
activar la caja y luego seleccionar AUTOLATBM en la lista que aparece.
Recordar que AUTOLATBM es la lista de secciones auto seleccionadas
creadas en el Paso 1.

C. Hacer click con el botón izquierdo del mouse una vez en la vista en
planta sobre el eje D entre los ejes 1 y 2. Una viga será dibujada a lo largo del
eje seleccionado. Debido a que la opción Similar Stories esta activa, las vigas
serán creadas en todos los niveles.

D. De manera similar, hacer click una vez en el eje 1 entre los ejes C y D y
luego hacer click una vez sobre el eje 2 entre los ejes C y D para dibujar las
vigas en dos posiciones más.

<!-- p. 170 -->

Figura 14- Dibujando objetos viga resistentes a fuerza lateral en una región
seleccionada

E. Dibujar ahora las vigas resistentes a la fuerza lateral restantes en una
acción, seleccionando un área alrededor de los ejes para agregar vigas entre las
columnas dibujada en el Paso 1, como se muestra en la Figura 14. Para hacer
un área de selección, hacer click en el botón izquierdo del mouse sobre la parte
superior izquierda de la intersección de los ejes A-4 y luego, mientras mantiene
presionado el botón izquierdo del mouse, arrastrar el mouse hasta ubicarlo
sobre la parte inferior derecha de la intersección de los ejes C-1. Un área

<!-- p. 171 -->

seleccionada se creara alrededor de las intersecciones de los ejes conforme sea
arrastrado el mouse a través del modelo. Después de dejar de presionar el
botón izquierdo del mouse el programa dibujara los objetos vigas.

F. Hacer click en el botón Select Object, |, para cambiar del modo
Dibujo al modo Selección.

G. Hacer click una vez en la viga a lo largo del eje C entre los ejes 2 y 3
para seleccionarla. Presionar la tecla Delete en su teclado o hacer click en el
comando Edit menu > Delete para borrar la selección porque ninguna viga
deberá conectar los puntos C-3 y C-2 en el modelo.

H. Hacer click en el comando File menu > Save, o en el botón Save, ,
para guardar su modelo.

Dibujar los objetos Vigas Secundarias (Infill)

Asegúrese que la vista en planta esta activa. Ahora dibujar las vigas
secundarias que unen las vigas principales, usando los siguientes items:

A. Hacer click en el botón Create Secondary Beams in Region or at
Clicks, o en el comando Draw menu > Draw Lines Objects > Create
Secondary Beams in Region or at Clicks. La caja Properties of Object para
vigas aparecerá según lo mostrado en la Figura 15.

<!-- p. 172 -->

Figura 15- Caja Properties of Object

Asegúrese que el item Property en esta caja este en A-CompBm. Si no fuese
así, hacer click una vez en la caja opuesta al item Property para activar la caja y
luego de la lista resultante seleccionar A-CompBm es una lista de secciones
auto seleccionadas que puede ser usada para vigas secundarias compuestas.
Para revisar las secciones incluidas en la lista auto seleccionada A-CompBm,
(1) hacer click en el comando Define menu > Frame Sections. (2) Seleccionar
A-CompBm en la lista presentada. (3) Hacer click en el botón Modify/Show
Property. (4) Cuando finalice, hacer click en el botón Cancel para cerrar el
formulario.

Asegúrese que el item Approx. Orientation en la caja Properties of Object esta
en paralelo a Y o R.

B. Hacer click una vez en el vano delimitado por los ejes C, D, 1 y 2 para
dibujar el primer grupo de vigas secundarias.

<!-- p. 173 -->

Dibujar el resto de vigas secundarias en solo una acción, seleccionando un área
alrededor de los vanos donde las vigas secundarias serán adicionadas, Figura
16- Figura 16 Dibujando objetos viga secundaria en una región seleccionada

como se muestra en la Figura 16. Para seleccionar el área, hacer click con el
botón izquierdo del mouse en una posición superior izquierda de la
intersección de los ejes A-4 y luego, mientras mantiene presionado el botón
izquierdo del mouse, arrastrarlo hasta ponerlo en una posición inferior derecha
de la intersección C-1. Un área seleccionada como la que se muestra en la
Figura 16 se creara conforme el mouse sea arrastrado a través del modelo.
Dejar de presionar el botón del mouse para dibujar los objetos viga
secundarios.

<!-- p. 174 -->

C. Hacer click en el botón Select Object, , , para cambiar del modo
Dibujo al modo Selección.

D. Hacer click en el botón Select Using Intersecting Line, o hacer
click en el comando Select menu > Using Intersecting Line para cambiar al
modo selección de linear intersectante.

En esta modalidad, hacer click con el botón izquierdo del mouse una vez para
comenzar una línea. Luego, mientras mantiene presionado el botón izquierdo
del mouse, arrástrelo hacia otra posición, de modo de crear una línea de
selección. Cuando se deja de presionar el botón del mouse, todos los objetos
que son interceptados por la línea de selección están seleccionados.

E. Según la Figura 17. Hacer click con el botón izquierdo del mouse en la
vista en Planta entre los ejes 2 y 3 justo a la derecha del eje B en el punto
etiquetado como 1 en la figura. Manteniendo presionado el botón izquierdo del
mouse, arrastre el puntero al punto etiquetado como 2 en la figura. La línea
seleccionada debe cruzar las vigas secundarias indeseadas en el vano limitado
por las ejes 2, 3 B y C . Deje de presionar el botón izquierdo del mouse para
seleccionar las vigas

F. Presione la tecla Delete en su teclado o hacer click en el comando Edit
menu > Delete para borrar las vigas seleccionadas del modelo.

G. Hacer click en el comando File menú > Save, o en el botón Save, ,
para guardar su modelo.

<!-- p. 175 -->

2

Línea de Selección
1

Figura 17- Selección usando una línea intersecante

Paso 3 Agregar Objetos Area

En este paso, los pisos son agregados al modelo y se crea un área "dummy"

<!-- p. 176 -->

(simulada) en la cual la carga del viento puede ser asignada en el Paso 7.

Dibujo de los objetos del área del piso

Asegúrese que la Vista en Planta este activa. Ahora dibuje un objeto área para
representar el piso usando los siguientes ítems.

A. Hacer click en el botón Draw Areas, , o seleccionar el comando
Draw menu > Draw Area Objects > Draw Areas. Aparecerá el cuadro de
Properties of Object para áreas que aparece en la Figura 18.

Figura 18- Caja Properties of Object

Asegúrese que el ítem Property este configurado en Deck1. Si no se encuentra,
hacer un click en la caja de edición opuesta al ítem Property para activar la caja
de dialogo y luego, seleccionar Deck1 en la lista resultante. Deck1 es una
propiedad de sección de losa incorporada. Las propiedades de losa son
revisadas en el ítem de Acción subsiguiente de este paso.

B. Compruebe que el comando Snap to Grid Intersections and Points
este active. Este comando puede asistir con exactitud al dibujar el área objeto.
Este comando se activa cuando el botón asociado es presionado.
Alternativamente, usar el comando Draw menu >Snap To Grid Intersections
and Points para Asegúrese que este comando esta active. Este comando se
activa por defecto.

<!-- p. 177 -->

C. Hacer un click en la columna A-1. Luego, moviéndose en la dirección
de las agujas del reloj alrededor del modelo, hacer un click en los puntos de
intersección en este orden para dibujar el parámetro del edificio: A-4, C-4, C-3,
B-3, B-2, D-2, D-1 y regresar A-1. Presione la tecla Enter de su teclado para
completar el objeto losa.

Si se equivoco mientras dibujaba el objeto, haga click en el botón Select
Object, para cambiar el programa del modo Dibujo al modo Selección.
Luego hacer click en el comando Edit menu > Undo Area Object Add.
Repita los pasos desde A hasta D.

Observe en su modelo las dos flechas dirigidas justo sobre la columna B-2 que
indica la dirección del tramo de la losa. La losa esta atravesando en la dirección
global X, perpendicular a las vigas secundarias. Note el tramo de la losa en
dirección del eje local 1 del objeto del área asociada.

D. Hacer click en el botón Select Object, para cambiar el programa del
modo dibujo al modo selección.

E. Para una mejor vista de la adición de la losa, hacer click en el botón Set
Building View Options . Cuando este formulario aparezca, verificar que el
recuadro de Object Fill y Apply to All Windows estén activados con un check,
como se muestra en la Figura 19.

<!-- p. 178 -->

Figura 19- Formulario de Set Building View Options

<!-- p. 179 -->

F. Revisar la propiedad Deck1 que fue asignada a la sección de la losa. Hacer
clic en el comando Click the Define menu> Wall/Slab/Deck Sections para que
aparezca el formulario de Define Wall/Slab/Deck Sections.

<!-- p. 180 -->

Figura 20- Modelo después de que se han agregado los objetos área de piso
\1. Seleccionar la sección Deck1 y hacer click en el botón Modify/Show. El
formulario Deck Section aparecerá según como se muestra en la Figura 21.

\2. Configurar en el ítem Slab Depth (tc) el valor de 3 para indicar que el
espesor de la losa sobre la losa de metal es de 3 pulgadas.

\3. Hacer click en el botón OK y luego en el botón OK dentro del formulario
Define Wall/Slab/Deck Sections para aceptar los cambios.

G. Hacer click en el comando File menu > Save, o en el botón Save, , para
guardar su modelo.

<!-- p. 181 -->

Figura 21 Formulario Deck Section (Sección de Losa)

Agregar el área de Objetos Dummy usado para la aplicación de

<!-- p. 182 -->

la carga del viento

Algunas áreas de objetos Dummy que no tienen masa ni rigidez serán
agregados al modelo. Estas áreas serán usadas en el Paso 7 para aplicar la carga
del viento al edificio.

Agregar Objetos en la Vista de Elevación

A. Activar la vista 3D, haciendo click sobre cualquier punto de la vista. La vista
esta activa cuando su barra de titulo esta resaltada.

B. Hacer click en el botón Elevation View y seleccionar A (i.e., eje A) desde
el formulario set Elevation View; luego hacer click en el botón OK. La vista 3D
Gambia a la vista de elevación del eje A.

C. Hacer click en el botón Create Areas at Click, o en el comando Draw
menu > Draw Area Objects > Create Areas at Click. Aparecerá el cuadro
Properties of Object para objetos de área. Hacer click en la caja de edición Property y
seleccionar NONE del cuadro resultante.

D. Hacer un click en cada uno de los vanos mostrados en esta vista de elevación
para agregar los elementos de área simulados (dummy). La Figura 22 muestra el
modelo con la simulación del objeto tipo pared que no tiene masa ni rigidez que

<!-- p. 183 -->

agregar a lo largo de la línea A.

Figura 22 Modelo después de que se han agregado los objetos de área simulados en
la Vista de Elevación a lo largo de la línea A.

Agregar Objetos en la Vista en Planta

A. Asegúrese que la Vista de Elevación este activa. La vista esta activa cuando
su barra de titulo esta resaltada.

B. Hacer click en el botón Vista en Planta y seleccionar Story 4 del formulario
Select Plan Level.

C. Hacer click en e! botón Create Walls in Region or at Click, , o hacer click
en el comando Draw menu > Draw Area Objects > Create Walls in Region or at
Clicks. Aparecerá el cuadro Properties of Object para crear objetos área, Hacer click
en la caja de edición Property y seleccionar NONE de la caja resultante.

D. Hacer un click en la línea C entre los ejes 3 y 4; hacer un click sobre el eje B
entre los ejes 2 y 3; hacer un click sobre el eje D entre los ejes 1 y 2, como se muestra
en la Figura 23. Los tipos simulados de pared sin dureza ni masa serán agregados a
todos los niveles del modelo debido a que la propiedad Similar Stories esta activa y e!
comando fue ejecutado en la Vista en Planta.

<!-- p. 184 -->

Click
aquí

Click
aquí
Click
aquí

Figura 23 Agregando objetos simulados tipo pared en la Vista en Planta.

E. Hacer click en el botón Select Object, para cambiar el programa del
modo dibujo al modo de selección.

<!-- p. 185 -->

F. Asegúrese que la Vista en Planta de la derecha este activa. Hacer click en el
botón Set Default 3D View , para cambiar de la Vista en Planta a la Vista en 3D.

G. Hacer click en el comando File menu > Save, o en el botón Save, para
guardar su modelo. Su modelo aparecerá como se muestra en la Figura 24.

Figura 24 Modelo después que han sido agregados todos los objetos simulados tipo
pared

<!-- p. 186 -->

Paso 4 Definicion de los Casos de Carga Estática

Las cargas estáticas usadas en este ejemplo consisten en la carga muerta, viva,
de sismo y de viento actuando en el edificio.

Para este ejemplo se asume que la carga muerta del edificio consiste en su peso
propio, mas 35 psf (libras por pie cuadrado) como una carga muerta adicional
aplicada a las losas y 250 plf (libras por pie lineal) como una carga muerta
adicional aplicada a las vigas perimetrales del edificio, Los 35 psf de carga
muerta adicional aplicada a las losas, toma en cuenta los pesos de los tabiques,
cielorrasos. Ductos de ventilación, instalaciones eléctricas y sanitarias, etc. Los
250 plf adicionales alrededor del perímetro considera el revestimiento lateral
del edificio.

La carga viva esta tomada como 100 psf en cada nivel. Esta carga viva es
reducible para el diseño de los pórticos de acero y las vigas compuestas.

Observe que realmente las cargas varían probablemente en algunas losas de los
diferentes niveles. Sin embargo, para los propósitos de este ejemplo, hemos
elegido aplicar la misma carga a cada nivel.

Nota: No hay límite para el número de casos de carga estática que puedan
ser definidos en el ETABS.

Este ejemplo también aplica una carga sísmica estática UBC97 y una carga del
viento ASCE 7-98 para el edificio. Las fuerzas que se aplican a( edificio para
sismo y viento son automáticamente calculadas por el programa.

<!-- p. 187 -->

A. Hacer un click en el comando Define menu > Static Load Cases o click en el
botón Define Static Load Cases, para que aparezca el formulario Define Static
Load Cases como se muestra en la Figura 25. Observe que por defecto hay dos casos
de cargas definidos. Estas son DEAD, cuando es un caso de carga muerta, y LIVE,
cuando es un caso de carga viva.

Observe que el factor de multiplicidad de peso propio esta definido como 1
para el caso DEAD. Esto indica que este caso de carga incluirá
automáticamente 1.0 veces el peso propio de todos los elementos.

B. Hacer click en LIVE para resaltar la fila como se muestra en la Figura 25.
Seleccionar REDUCE LIVE desde el menu Type. Hacer click en el botón Modify
Load para cambiar el tipo de carga de viva a viva reducida. Aplicaremos la carga viva
a la estructura posteriormente.

Figura 25 Formulario Define Static Load Case Names

<!-- p. 188 -->

C. Hacer click en la caja de edición para la columna Load. Digite el nombre para
la nueva carga, en este caso, será SDEAD. Seleccionar el tipo de carga desde el menu
Type; en este caso, Seleccionar SUPERDEAD. Asegúrese que el factor de
multiplicidad del peso propio se encuentra en cero. El peso propio deberá ser incluido
en solo un caso de carga; de otro modo, podrá ser considerado dos veces en el análisis.
En este ejemplo, el peso propio ha sido asignado para el caso de carga DEAD. Hacer
clic en el botón Add New Load para agregar la carga SDEAD a la lista Load.

D. Repetir la acción del ítem C para agregar una carga tipo SUPERDEAD de
nombre
CLADDING. Aplicaremos carga muerta superimpuesta para la estructura
posteriormente.

E. Para definir la carga de sismo UBC97, nuevamente haga click en la caja de
edición para la columna Load y digite EQY. Seleccionar QUAKE para el tipo de
carga. Asegúrese que el factor de multiplicidad para el peso propio sea cero. Use el
menu carga lateral para seleccionar UBC97; con esta opción seleccionada, ETABS
automáticamente aplicara la carga sísmica estática conforme a los requerimientos del
código 1997 UBC. Hacer click en el botón Add New Load.

F. Con la carga EQY resaltada, hacer click en el botón Modify Lateral Load.
Esto presentara el formulario 1997 UBC Seismic Loading (El formulario UBC97
aparece porque el tipo Auto Lateral Load fue configurado en el ítem E). Dentro de
este formulario, hacer click en la opción Y Dir en la parte superior del formulario,
como se muestra en la Figura 26. Hacer click en el botón OK. El formulario Define
Static Load Case Names reaparecerá.

<!-- p. 189 -->

Figura 26 Formulario 1997 UBC Seismic Loading

<!-- p. 190 -->

G. Para definir la carga de viento ASCE7-98, hacer click nuevamente en la caja
de edición para la columna Load y digite WINDX. Seleccionar el tipo WIND en la
columna Type. Seleccionar ASCE7-98 del menú Lateral Load desplazado. Hacer click
en el botón Add New Load.

H. Con la carga WINDX resaltada, hacer click en el botón Modify Lateral
Load. Esto presentara e! formulario ASCE 7-98 Wind Loading mostrado en la figura
27 (el formulario ASCE 7-98 aparecerá porque el tipo Auto Lateral Load fue fijado en
el ítem G para ASCE 7- 98). Seleccione Exposure de la opción Área Objects- Note
que el formulario cambia de apariencia.

El Exposure de la opción Area Objects significa que la carga del viento se
define por los coeficientes de presión de viento especificado por el usuario
aplicados a los elementos verticales simulados que fueron dibujados
anteriormente en e! Paso

<!-- p. 191 -->

Figura 27 Formulario ASCE 7-98 Wind Loading (Cargas de Viento ASCE 7-98)

Digitar 100 dentro de la caja de edición para Wind Speed, como se muestra en
la Figura 27 y luego hacer click en el botón OK. Reaparecerá el formulario
Define Static Load Case Names.

El formulario Define Static Load Case Names aparecerá como se muestra en la
Figura 28. Hacer click en el botón OK en el formulario para aceptar todos los

<!-- p. 192 -->

nuevos cases de carga estática definidos.

Figura 28 El formulario Define Static Load Case Names después de que todos los
casos de las carga estática han sido definidas.

I. Hacer click en el comando File menu > Save, o en el botón Save, , para
guardar su modelo.

Paso 5 Asignar Cargas de Gravedad

En este paso, las cargas de gravedad muerta y viva super impuesta serán aplicadas en
este modelo. Asegúrese que la propiedad Similar Stories esta habilitada y que la Vista
en Planta esta activa.

A. Hacer click en cualquier lugar de la losa (pero no sobre una viga) para
seleccionar la losa. Una línea discontinua aparecerá alrededor del perímetro de la losa.

<!-- p. 193 -->

Esta línea discontinua indica que la losa ha sido seleccionada. Si usted se equivoca en
seleccionar, presione e! botón Clear Selection, , e intente de nuevo.

La barra de estado en la esquina inferior izquierda de la ventana principal de
ETABS deberá indicar que cuatro objetos área han sido seleccionados debido a
que la propiedad Similar Stories esta activa.

B. Hacer click en el comando Assign > Shell/Area Loads > Uniform o click en

el botón Assign Uniform Load, . Aparecerá el formulario Uniform Surface
Loads. Seleccionar SDEAD del cuadro Load Case Name, como se muestra en la
figura 29.

Figura29 Formulario Uniform Surface Loads

Note que la dirección especificada para la carga es Gravity. La dirección de la carga
de Gravedad es hacia abajo; eso es, en la dirección del eje Global 2 negativo.

<!-- p. 194 -->

\1. Mantenga presionada fa tecla Shift y haga doble click en el campo
Load para presentar el formulario Calculator, mostrado en la Figura 30. Esta
calculadora incorporada tiene un numero de funciones que son útiles para
asignar cargas. En este caso, será usada para convertir unidades y asignar la
carga muerta super impuesta en Ib-ft.

Figura 30 Formulario de la calculadora

Observe que en la calculadora mostrada tiene en la caja de texto las unidades Fuerza
sobre longitud al cuadrado (Fuerza/Longitud2).

Seleccionar Ib-ft de la lista que se presenta en el formulario Calculator y luego digite
35 dentro de la caja de edición Formula. Asegúrese que las unidades sean las
indicadas antes de digitar 35.

Hacer click en el botón OK del formulario Calculator; ETABS automáticamente
convierte el ingreso ib-ft en Kip-inch, apareciendo el resultado 2.43055555555556E04 kips/in2, en el formulario Uniform Surface Load.

<!-- p. 195 -->

\2. Hacer click en el botón OK del formulario Uniform Surface Load para
aceptar la carga muerta super impuesta.

C. Hacer click en cualquier lugar de la losa (pero no sobre la viga) para
seleccionar la losa.

D. Hacer click en el comando Assign > Shell/Area Loads > Uniform o click en
el botón Assign Uniform Load, . Aparecerá el formulario Uniform Surface
Loads. Seleccionar LIVE del cuadro Load Case Name.

\1. Configurar las unidades en el formulario en Ib-ft y luego ingresar 100
en la caja de edición Load. El formulario Uniform Surface Loads deberá
aparecer como se muestra en la Figura 31.

Figura 31 Formulario Uniform Surface Loads

<!-- p. 196 -->

\2. Hacer click en el botón OK del formulario Uniform Surface Load para
aceptar la carga viva.

E. Verificar que el comando Snap to Grid Intersections an Points no este
active. Esto hará más fácil seleccionar las vigas perimetrales. Este comando esta
active cuando su botón asociado esta presionado. Por lo tanto, Asegúrese que el
botón no este presionado. Usted puede accionarlo rápidamente usando el comando
Draw menu > Snap To > Grid Intersections and Points.

Nota: Se recomienda aplicar las cargas del revestimiento lateral del edificio (cladding)
a las vigas perimetrales y no a las losas

F. Seleccionar la viga perimetral a lo largo del eje A de la grilla entre los ejes 1 y
2 mediante un click izquierdo en la Vista en Planta. Observe que la barra de estado en
la esquina inferior izquierda de la ventana principal de ETABS indica que cuatro
líneas han sido seleccionadas debido a que la propiedad Similar Stories esta activa.
También note que las líneas seleccionadas aparecen discontinuas.

G. Seleccionar las otras trece vigas perimetrales en forma similar. Cuando usted
ha seleccionado todas las vigas perimetrales, la barra de estado deberá indicar que 56
líneas han sido seleccionadas (14 vigas por 4 pisos = 56 vigas).

H. Hacer click en el comando Assign > Frame/Line Loads > Distributed o en
el botón Assign Frame Distributed Load, .Se presentara el formulario Frame
Distributed Loads mostrado en la Figura 32. Seleccionar CLADDING de la caja Load
Case Name.

<!-- p. 197 -->

Figura 32 El formulario Frame Distributed Loads

\1. Configurar las unidades a Ib-ft y luego digitar 250 en la caja de edición
Load que esta ubicada en el área Uniform Load del formulario.

\2. Hacer click en el botón OK del formulario Frame Distributed Loads
para aceptar la carga muerta super impuesta que esta aplicada a las vigas
perimetrales para representar al revestimiento.

<!-- p. 198 -->

Observe que el formulario Frame Distributed Loads también tiene una caja de texto
Delete Existing Loads. Para borrar una Carga asignada, seleccionar la(s) viga(s) y usar
el comando Assign > Frame/Line Loads > Distributed o en el botón Assign Frame
Distributed Load, para acceder a este formulario. En !a caja Load Case Name,
ubicar la carga que será removida, verificar en la caja Delete Existing Loads y hacer
click en el botón OK.

I. Asegúrese que la Vista en Planta este activa. Hacer click en el botón Set
Default 3D View, , para cambiar de la vista en planta a la vista 3D. Usted debería
estar ahora habilitado para ver gráficamente la carga aplicada a las vigas perimetrales,
como se ilustra en la Figura 33.

<!-- p. 199 -->

Figura 33 Cargas distribuidas en los elementos Frame aplicadas a las vigas
perimetrales.

J. Hacer click en el comando Assign menu > Clear Display of Assigns para
ocultar las cargas asignadas.

<!-- p. 200 -->

K. Asegúrese que la vista 3D este activa. Hacer click en el botón Plan View
y seleccionar Story 4 del formulario Select Plan Level.

L. Hacer click en el comando File menu > Save, o en el botón Save, ,
para guardar su modelo.

Paso 6 Definir una Elevación Desarrollada

En este paso, una vista Developed Elevation del lado derecho del edificio será
definido de modo que la carga de viento puede ser originada en el Paso 7

A. Al hacer click en el comando Draw menu > Draw Developed Elevation
Definition para presentar el formulario Elevation Views mostrado en la Figura 34.

<!-- p. 201 -->

Figura 34 El Formulario Elevation Views.

\1. Digitar XXX en la caja de edición Developed Elevations, como se
muestra en la figura. Esta será el nombre de la elevación.

\2. Hacer click en el botón Add New Name y luego en el botón OK. Note
que ambas vistas son ahora Plan Views y que e! modo de dibujo Developed
Elevation esta activo. El modelo aparece como se muestra en la Figura 35.

B. Chequear que el comando Snap to grid Intersection and Points este activo.
Esto ayudara a dibujar con exactitud la definición de Developed Elevation. Este
comando esta activo cuando su botón asociado esta presionado. Alternativamente,

<!-- p. 202 -->

usar el comando Draw menu >Snap to > Grid Intersections and Points para
Asegúrese que este comando esta activo. Este comando esta activo por defecto.

Figura 35 ModoClickde Dibujo6 Developed Elevation

C. Trabajando en el Plan View de la izquierda (note que esto puede ser
completado de cualquier Plan View), hacer click en el botón izquierdo del mouse una
vez en D-2, B-2, B-3,C-3 y C-4 en ese orden. La secuencia de clicks es ilustrado en la
Figura 35.

Click 4
D. Cuando todos los puntos hallanClicksido5 seleccionados , presionar la tecla Enter en
su teclado para terminar con el dibujo de la definición del Developed Elevation, Click 3 Click 2

E. Presionar la tecla Esc de su teclado para salir del modo dibujo Developed
Elevation. Note que las vistas regresan a aquellas que existieron antes de habilitar el
modo de dibujo Developed Elevation.

F. Asegúrese que el Plan View este activa. Hacer click en el botón Elevation
Click 1
View y seleccionar XXX (al Developed Elevation definido) del formulario Set
Elevation View, hacer click en el botón OK. El Plan View cambia a Developed
Elevation View, como se muestra en la Figura 36.

<!-- p. 203 -->

Figura 36 Vista Developed Elevation

Developed Elevation es una vista separada de una elevación definida y es ilustrada por
líneas de color cyan en el 3D View.

Pueden definirse tantas elevaciones de este tipo como usted desee. Note sin embargo
que, un Developed Elevation no puede cruzarse y acercarse a si mismo. Estas dos

<!-- p. 204 -->

situaciones requerirán que el mismo punto ocurra en dos diferentes posiciones dentro
de estas elevaciones, lo cual no esta permitido.

Después de haber definido un Developed Elevation, este puede ser visualizado, los
objetos pueden ser dibujados en el, así también asignaciones a objetos y mucho mas,
similar a cualquier otra Elevation View. La Elevation View XXX será usada en el
siguiente paso.

G. Asegúrese que Developed Elevation View (i.e. Elevation View XXX) este
activa. Hacer clic en el botón Plan View y seleccionar Story 4 del formulario
Select Plan Level.

H. Hacer click en el comando File menu > Save o el botón , para guardar el
modelo.

Paso 7 Asignar Cargas De Viento

En este paso, las cargas de viento son asignadas a una vista Developed Elevation
definido en paso 6. Típicamente, los coeficientes de la presión del viento son
aplicados a la superficie vertical de un objeto área. En tales casos, y en este ejemplo
un coeficiente positivo de presión de viento es aplicado a una carga de viento en la
direcci6n posterior del eje local 3 de un objeto área. Un coeficiente negativo de
presión de área es aplicado a una carga de viento en la direcci6n negativa del eje local
local 3 de un objeto área.

A. Hacer Click en la ventana 3D View para volvería activa

<!-- p. 205 -->

B. Hacer Click en el comando view menu>SetBuilding View Options o en el
botón Set Building View Options para presentar el formulario Set Building View
Options mostrado en la figura 37.

Figura 37 Formulario Set Building View Options

\1. Chequear en la caja Area Local Axes para activar el eje local del área y
luego hacer clic en el botón OK para salir del formulario. Las rojas, blanca y
Azul aparecen definiendo los eje locales del objeto área. Recordar que Rojo =
e]e 1, Blanco = eje 2 y Azul= eje 3.

<!-- p. 206 -->

El edificio aparece como se muestra en la figura 38. Note que para los objetos área
dummy vertical a lo largo del eje A, las flechas azules representan el eje local 3 que
apuntan en la direcci6n positiva del eje Global X. Nota, que los ejes globales están
ubicados en el origen del modelo.

Figura 38 Ejes locales del Objeto área

<!-- p. 207 -->

C. Hacer click en el botón Rotate 3D View, y luego hacer click una vez en el
botón izquierdo en la vista 3D View, y mientras mantiene presionado el botón del
mouse, arrastre el mouse hacia la izquierda. Note que una caja con líneas discontinuas
muestra como la vista esta siendo rotada. Rotar la vista del modo que usted pueda ver
e! otro objeto área dummy vertical ubicado en los ejes B, C y D. Confirmar que el eje
local 3 de estos elementos están apuntando en la direcci6n positiva del eje global X.

D. Cuando usted haya confirmado que los objetos área vertical tienen sus ejes
locales apuntando en la dirección positiva del eje global X, hacer click en el comando
View menú > Set Building View Options en el botón Set Building View Options,
para presentar el formulario Set Building View Options. Quitar la selección de la

<!-- p. 208 -->

caja Area Local Axes para ocultar la visualización de los ejes locales y luego hacer
click en el botón OK para salir del formulario.

Figura 39 Seleccionando objetos área vertical en una vista de elevación

E. Asegúrese que la vista 3D View esta activa y luego hacer click en el botón Set
Default 3D View, para regresar a la vista 3D por defecto.

F. Con la vista 3D View activa, hacer click en el botón Elevation View,
para cambiar la vista a una elevación del eje A. y seleccionar A

G. Hacer click con el botón izquierdo del mouse y arrastrarlo para dibujar una
caja de selección alrededor de todos los paneles en esta vista en elevación, como se
muestra en la Figura 39.
H. Hacer click en el comando Assign menu > Shell / Area Loads > Wind
Pressure Coefficient, el cual presentara el formulario Wind Pressure Coefficient
mostrado en la Figura 40.

\1. Seleccionar WINDX de la caja Wind Load Case Name. Digitar 0.8 en
la caja Coeff, Cp y Seleccionar la opción Wind Ward.

Seleccionar la opción Wind Ward significa que la caja de viento aplicada a estos
paneles dummy variaran en toda la altura del edificio de acuerdo al código de
edificación especificado, cuando la carga de viento fue definida, en este caso, ASCE
7-98.

<!-- p. 209 -->

Figura 40 El formulario Wind Pressure Coefficients

\2. Hacer click en el botón OK para asignar esta caja. Note que con Cp
positivo, la carga actuara en la dirección positiva del eje Global X. Con la vista
Elevación View activa, hacer click en el botón Elevation View y seleccionar
XXX para visualizar la vista Developed Elevation View. Hacer click en el botón OK.
En la vista Developed Elevation View, hacer click con el botón

Caja de Selección

<!-- p. 210 -->

Figura 41 Seleccionando objetos de área vertical en una vista Deloped Elevation
View

izquierdo del mouse y arrastrarlo para dibujar una caja de selección alrededor de todos
los paneles, como se muestra en la Figura 41.

I. Hacer click en el comando Assign menu > Shell / Area Loads > Wind
Pressure Coefficient, para presentar el formulario Wind Pressure Coefficient- Digitar
0.5 en la caja Coeff, Cp y seleccionar la opción Leeward or Slides (Constant). Hacer
click en el botón OK para asignar esta carga. Nuevamente, note que con Cp positivo,
la carga actuara en la dirección Global X.

Seleccionar la opción Leeward or Slides significa que la caja de viento aplicada a
estos paneles dummy serán constantes sobre toda la altura del edificio de acuerdo al
código de edificación especificado, en este caso, ASCE 7-98. La magnitud de la carga
de viento esta basada en la altura total del edificio.

J. Hacer click en el comando Assign menu > Clear Display of Assigns para
ocultar la visualización de las asignaciones de los coeficientes de la presiónCaja dedeSelecciónviento.

<!-- p. 211 -->

K. Asegúrese que la vista Elevation View esta activa y luego hacer click en el
botón Set Default 3D View, para volver a la vista 3D por defecto.

L. Hacer click en el comando File menu > Save, o en el botón Save, , para
guardar su modelo.

Paso 8 REVISION DE LA BASE DE DATOS DE INGRESO EN
DATABASE DISPLAY

En este paso, una base de datos que muestra los coeficientes de presión debido a
viento que fueron ingresadas en el paso 7 serán revisadas.

A. Haga click en el comando Display menu > Set Input Table Mode para
mostrar el cuadro Database Input Tables. Hacer click en la etiqueta Assignments y
luego seleccione la cajita Wind Pressures como se muestra en la figura 42. Asegúrese
que la cajita Selection Only no este seleccionada.

\1. Hacer click en el botón OK para mostrar la tabla de base de datos
seleccionada, la tabla mostrada en la figura 43 es visualizada.

Cada columna en la tabla corresponde a un área de objetos. Note que las cinco
columnas en la tabla, etiquetadas con Cp, muestra los coeficientes Cp que fueron
ingresados para cada objeto área vertical. Las siguientes tres columnas muestran los
componentes globales X, Y y Z de este factor Cp. En este caso, todas las cargas están
en la dirección global positiva X, como se deseaba.

\2. Hacer click en e! botón OK para cerrar la ventana de base de datos.

\3. Repetir el proceso si deseara revisar otras tablas.

<!-- p. 212 -->

Figura 42 Formulario Database Imput Tables

<!-- p. 213 -->

Figura 43 Formulario Area Wind Pressures

Paso 9 EJECUTAR EL ANALISIS

En este paso, ejecutamos el análisis.

A. Hacer click en el comando Analize menu > Run Analysis o el botón Run
Analisis, y haga click en el botón Run en el cuadro Run Options.

El programa creara el modelo de análisis para los objetos basados en el modelo del
ETABS, y pronto presentara una ventana "Analyzing, Please Wait". Los datos se

<!-- p. 214 -->

desarrollan en esta ventana conforme el programa ejecuta el análisis. Después de
haber sido completado el análisis, el programa lleva algunas acciones de librería que
son mostradas en la barra de estado en la esquina inferior izquierda de la ventana del
ETABS.

Cuando e! proceso entero de análisis se haya completado, el modelo automáticamente
muestra una vista de la forma de !a deformada del modelo, y el modelo se bloquea, el
modelo es bloqueado cuando el botón Lock/Unlock Model, , aparece cerrado,
bloqueando el modelo prevenimos cualquier cambio en el modelo que invalidaría los
resultados del análisis.

Paso 10 REVISION GRAFICA DE LOS RESULTADOS DEL ANALISIS

En este paso, los resultados del análisis serán revisados usando la representación
grafica de los resultados.

A. Asegúrese que la 3D View este activa, luego haga click en el botón Elevation
View, y seleccione 1 para volver a iniciar la vista en Elevation View del Eje D.

B. Hacer click en el botón Show Frame/Pier/Spandrel Forces, , o los
comandos Display menu > Show Member Force/Stresses Diagram >
Frame/Pier/Spandrel Forces para presentar e! cuadro Member Force Diagram for
Frames mostrado en la figura 44.

\1. Seleccione en la cajita Load la carga
DEAD Static Load.

\2. Seleccione la opción Moment 3-3.

\3. Deseleccione Fill Diagram si estuviera
seleccionada.

<!-- p. 215 -->

\4. Seleccione en la cajita Show Values on Diagram.

\5. Haga click en el botón OK para generar fa salida del diagrama de momentos
mostrado
en la Figura 45.

Figura 44 Cuadro Member Force Diagram for Frames

<!-- p. 216 -->

Figura 45 Vista en elevación del Diagrama de Momentos

Note que estos diagramas de momentos son ploteados con el momento positivo en el
lado de tensión del elemento. Cambie esto, si deseara, usando el comando conmutador
Options menú > Moment Diagrams on Tension Side.

C. Hacer click con el botón derecho del mouse en el nivel superior de la viga
entre los ejes A y B para presentar el cuadro Diagram for Beam mostrada en la figura
\46.

<!-- p. 217 -->



<!-- p. 218 -->

Figura 46 Detalle de fuerzas obtenidas al hacer click con el botón derecho sobre
Beam Shown en la elevación vista en la Figura 45

Note que la carga aplicada, corte, momento y deflexión son mostradas para la viga, y
los máximos valores son identificados en el cuadro Diagram for Beam. Uniform Load
mostrada para la viga es la carga tributaria de la losa más el peso propio de la viga.
Las cargas tributarias concentradas no son mostradas.

\1. Hacer click en la opción Scroll for Values y una barra deslizable aparecerá en
la parte inferior del cuadro, arrastrar la barra deslizable con su mouse para ver los
valores en las diferentes ubicaciones a lo largo de la viga.

\2. Seleccione kip-ft en la cajita Units en la parte inferior del cuadro. Luego
digite 6.5 dentro de la cajita de edición Location. Los valores de carga, corte,
momento y deflexión son mostrados en la localización exacta en unidades kip y feet.

\3. Haga click en la caja tipo drop-down Static Load Case y seleccione el cuadro
CLADDING de la lista para mostrar las fuerzas actuantes en esta viga de la carga
muerta de superposición denominada CLADDING. Uniform Load (Down +) mostrana
un valor de 0.250 klf, la cual es la carga de revestimiento que fue aplicada en el paso
\5.

\4. Haga click en el botón Done para cerrar este cuadro.

D. Asegúrese que Elevation View este activa y luego haga click en el comando
Display menu >Show Undeformed Shape o el botón Show Undeformed Shape,
, para despejar la visualización de los diagramas de momento en Elevation View.

E. Asegúrese que Elevation View este activa y luego haga click en el botón Set
Default 3D View, , para volver a iniciar la vista por la vista por defecto 3D.

<!-- p. 219 -->

Paso 11 Diseño de Vigas Compuestas

En este paso, las vigas compuestas serán diseñadas. Note que el análisis deberá de
ejecutarse completando antes los siguientes Items.

A. En Plan View, haga click derecho en una de las vigas secundarias (relleno) en
el vano limitado por líneas tipo grilla 1,2, A y B. E! cuadro Line Información
mostrada en la figura 47 aparecerá.

<!-- p. 220 -->

Figura 47 Cuadro Line Información

Note que el cuadro reporta que Desing Procedure para este cuadro es Composite
Beam. El programa asigno este procedimiento de diseño por defecto a este objeto
línea debido a (1) aquella no esta en un piano horizontal, (2) los extremes de la viga
están con libertad de girar, y (3) es asignada a una sección de acero la cual es de tipo I
o tipo canal. Algún elemento de acero que no reuniese estos requerimientos esta
determinado por el procedimiento de diseño de Steel Frame.

<!-- p. 221 -->

B. Hacer click en el comando Options menu > Preferences > Composite Beam
Design. El cuadro Preferences que muestra en la figura 48 aparecerá.

<!-- p. 222 -->

Figura 48 Cuadro Preferences

<!-- p. 223 -->

\1. Hacer click en Design Code en la cajita tipo drop-down en la parte inferior de!
cuadro y vea los códigos disponibles. Seleccione el código AISC-LRFD93.

\2. Revise la información disponible en las cinco etiquetas del cuadro Preferences
y luego haga click en e! bot6n OK para aceptar el cambio en Design Code.

C. Hacer click en la barra de titulo del 3D View para activar la vista en 3D.

D. Hacer click el bot6n Set Building View Options . Cuando el cuadro Set
Building View Options aparece, deseleccione la cajita Object Fill como se muestra en
la figura 49. esta eliminara la presentación del relleno en los objetos área.

\1. En el área Object Present in View del cuadro, deseleccione la cajita All Null
Areas.

\2. Haga click en la cajita Apply to All Windows y luego haga click en el bot6n
OK para aceptar los cambios.

<!-- p. 224 -->

Figura 49 Cuadro Set Building View Options

E. Con 3D View activado, haga click en el comando Design menu > Composite
Beam Design > Start Design Without Similarity para iniciar los procesos de diseño.
El programa diseña las vigas compuestas, seleccionando el tamaño optimo de la viga
de la lista de selección de secciones A-CompBm que Ie fue asignada cuando aquellas
fueron dibujadas en el paso 2.

Cuando el diseño este completo, los tamaños seleccionados serán mostrados en el
modelo. El modelo aparecerá como se muestra en la Figura 50.

<!-- p. 225 -->

Figura 50 Model after the initial composite design

F. Haga click en el comando Design menu > Composite Beam Design > Verify
Analisis vs Design Section. Un mensaje similar ala mostrada en la figura 51
aparecerá. Haga Click en el botón No para cerrar e! cuadro.

<!-- p. 226 -->

Figura 51 Mensaje de advertencia por un diseño incompleto en el Análisis vs
Diseño de Sección

En el análisis inicial (Paso 9), el programa usa el peso de la sección media de la lista
de selección de secciones A-CompBm. Durante el diseño (este paso), el programa
selecciona una sección de diseño W12X19, el cual difiere para la sección de análisis
usada. El mensaje de la figura 51 indica que el análisis y la sección de diseño son
diferentes.

El objetivo es repetir los procesos del análisis (paso 9) y diseño (paso 11) hasta que el
análisis y diseño de la sección sean idénticos. Note que cuando el edificio es
reanalizado (Ej. Paso 9 es repetido), ETABS usara la sección de diseño actual (Ej.
Aquellos seleccionados en e! paso 11) como el nuevo análisis de la sección para la
próxima ejecución del análisis. Así, en el próximo análisis de este ejemplo, la viga
compuesta será analizada usando la sección de análisis W12X19.

G. Hacer click derecho en una de las vigas compuestas en 3D View mostrada en
la figura 50. el cuadro Interactive Composite Design and Review mostrada en la figura
52 aparecerá.

<!-- p. 227 -->

Figura 52 Formulario de Diseño y Revisión Interactiva de Vigas Compuestas
(Interactive Composite Beam Design an Review)

Note que la actual sección de diseño es reportada como W12X19 y el anterior análisis
es reportado como W 14X30.

Aceptable Sections List muestra todas las vigas en la lista de selección de secciones
A-CompBm que son adecuadas para las fuerzas de diseño.

<!-- p. 228 -->

\1. Hacer Click en el botón Details del cuadro Interactive Composite Beam
Design y Review. El cuadro Composite Beam Design mostrada en la figura 53
aparecerá. Este cuadro muestra la información detallada del diseño acerca de la viga.
Revise la información en cada uno de los cuatro etiquetas de este cuadro. Hacer click
en X en la esquina superior derecha del cuadro para cerrar esta.

<!-- p. 229 -->

Figura 53 Formulario de Diseño Compuesto de Viga (Composite Beam Design)

\2. Hacer click en el botón Cancel para cerrar el cuadro Interactive Composite
Beam Design y Review.

H. Para reejecutar el análisis con la nueva sección de análisis para la viga
compuesta, hacer click en los comandos Analyze menu > Run Analysis o en el botón
Run Análisis, y haga click en el botón Run en el cuadro Run Options-

I. Cuando el análisis se complete, haga click en el comando Design menu >
Composite Beam Design > Start Design Without Similarity para iniciar el proceso
de diseño de la viga compuesta.

J. Hacer click en el comando Design menu > Composite Beam Design >
Verify Analisis vs Design Section, El mensaje mostrado en la figura 54 se mostrará,
indicando que el análisis y la sección de diseño son los mismas para la viga
compuesta. Hacer click en e! botón OK.

Figura 54 Mensaje de advertencia por un diseño complete) en el Análisis vs. Diseño
de Sección

Si no Ie muestra este mensaje, repita las acciones de los items H, I y J hasta que esta
se muestre, antes de proceder al siguiente Item.

<!-- p. 230 -->

K. Hacer click en el comando Design menu > Composite Beam Design >
Verify All Menbers Passed. El mensaje mostrado en la figura 55 se mostrara.
Indicando que todas las vigas compuestas han aprobado el diseño. Hacer click en el
botón OK para cerrar el cuadro.

Figura 55 Mensaje de advertencia, verifique todos elementos anteriores

L. Hacer click en el botón Select All, o haga click en el comando Select
menu > All, o presione las teclas Ctrl. y A simultáneamente en su teclado para
seleccionar todos los objetos en el modelo.

M. Hacer click en el comando Design > Composite Beam Design > Make Auto
Select
Section Null y haga click en el botón OK para el mensaje resultante. Esta remueve las
secciones auto seleccionadas de las listas para los miembros de la viga compuesta y
reemplaza estos con otras secciones de diseño actuales.

N. Hacer click en el comando Assign menu > Clear Display of Assigns.
También haga clic en el botón Clear Section, , para borrar la selección.

<!-- p. 231 -->

O. Hacer click en el comando File menu > Save, o el botón Save, para salvar
el modelo. El diseño de la viga compuesta esta ahora completa.

Paso 12 Diseño del Elemento Acero

En este paso, el diseño de la estructura de acero está completa. Note que en el análisis
(paso 9) seria ejecutada antes de llevar a cabo los siguientes Items.

A. En Plan View, haga click derecho en la viga a lo largo de las línea tipo grillas
1 y 2. el cuadro Line Información mostrada en la figura 56 aparecerá. Revise la
información. Note que Design Procedure para esta viga es Steel Frame. Haga click en
el botón OK para cerrar el cuadro.

<!-- p. 232 -->



<!-- p. 233 -->

Figura 56 Formulario de Informacion de la Línea

B. Haga click en la barra tipo titulo de la 3D View para activar la vista en 3D .
Esto permite que los resultados del diseño aparezca en la 3D View.

C. Haga click en el comando Design > Steel Frame Design > Start
Design/Check of
Structure o haga click en el botón Start Steel Design/Check of Structure, , para
iniciar el proceso de diseño de la estructura de acero. Las columnas y las vigas
laterales de aquellos tramos entre columnas serán diseñadas.

D. Cuando el diseño inicial este complete, un cuadro similar a lo que se muestra
en la figura 57 aparecerá.

Figura 57 Mensaje de advertencia por un diseño incompleto en el Análisis vs.
Diseño de Sección

Similar al diseño compuesto (descrito en el paso 11), en el análisis inicial, el programa
usara la sección media para el peso de las secciones seleccionadas de las listas
AUTOLATBM y A-Latcol para el análisis. Las secciones diseñadas escogidas difieren
para la secciones de análisis usadas. El mensaje en la figura 57 indica que el análisis y
e! diseño de la sección son diferentes.

<!-- p. 234 -->

\1. Haga click en el botón No para cerrar el cuadro.

E. Haga click en la barra de titulo de Plan View para activar la vista.

F. Haga click en el comando Design > Steel Frame Design > Display Design
Info. El cuadro Display Design Results aparecerá.

\1. Asegúrese que la opción Design Output este seleccionada y que P-M Ratio
Colors & Values este seleccionada en la cajita tipo drop-down de Design Output.
Luego haga clic en el botón OK.

Los resultados serán mostradas en la Plan View y el modelo aparece como se muestra
en la figura 58.

<!-- p. 235 -->

Figura 58 Modelo después del diseño inicial del Pórtico de Acero

G. En Plan View, haga click derecho en la viga a lo largo de la línea tipo grilla C
entre las líneas grilla 3 y 4 como se indica en la figura 58. El cuadro Steel Stress
Check Información mostrada en la figura 59 aparecerá. Note que el reporte del análisis
y la sección de diseño son Diferentes.

El cuerpo principal del cuadro lista la relación de esfuerzos obtenidas en varias

<!-- p. 236 -->

estaciones a lo largo de la viga para cada combinación de cargas de diseño. Note que
el programa automáticamente crea códigos específicos de diseño de combinación de
cargas para el diseño de estos elementos de acero.

Haga click en el botón Details en el cuadro Steel Stress Check Información. El cuadro
Steel stress Check Información AISC-LRFD93 mostrada en la figura 60 aparecerá.
Note que usted puede imprimir esta información usando el cuadro File Menu.

Figura 59 Formulario informativo para verificar el Esfuerzo del Acero

Haga click en X en la esquina superior derecha del cuadro Steel Stress Check
Información AISC-ASD89 para cerrar esta.

<!-- p. 237 -->

Haga click en el botón Cancel para cerrar el cuadro Steel Stress Check Información.

Figura 60 Formulario para verificación de información AISC-LRFD93 del
esfuerzo
del acero

<!-- p. 238 -->

H. Haga click en el comando Design > Steel Frame Design > Select Design
Combo. El
cuadro Design Load Combinations Selection mostrada en la figura 61 aparecerá.

Figura 61 Formulario de Selección de la Combinación del Diseño de Carga

En la lista de combinaciones de diseño identificamos las diez combinaciones de carga
de diseño por defecto para elementos de acero creados por el programa. Haga click en
DSTL6 para resaltar esta y luego haga click en el botón Show. El cuadro Load
Combinación Data mostrada en la figura 62 aparecerá, mostrando la combinación de
carga de diseño DSTL6 definidas por el programa.

<!-- p. 239 -->

\1. Haga click en el botón OK en el cuadro Load Combinación Data para cerrar
esta. Si
decidiera, revisar otras definiciones de combinaciones de carga entonces haga click en
el
bot6n OK para cerrar el cuadro de datos,

\2. Haga click en el botón Cancel en el cuadro Design Load Combinations
Selection para
cerrar esta sin aceptar algún cambio que pudiera haber hecho involuntariamente.

I. Hacer click en la barra tipo titulo de la Plan View para activar la vista.

J. Hacer click en el comando Display menu > Show Undeformed Shape o en
el botón Show Undeformed Shape, , para despejar !a pantalla de relación de
esfuerzos.

<!-- p. 240 -->

Figura 62 Formulario de Combinación de Datos de la Carga

K. Hacer click en la barra tipo titulo 3D View para activar la vista en 3D.

L. Para volver a ejecutar el análisis con las nuevas secciones de análisis para las
vigas de acero, haga click en el comando Analyze menu > Run Análisis o el botón
Run Analysis, y haga click en el botón Run en el cuadro Run Options.

M. Cuando el análisis este completo, la forma de la deformada se mostrara. Hacer
click en el comando Design > Steel Frame Design > Start Design/Check of

<!-- p. 241 -->

Structure o haga click en el botón Start Steel Design/Check of Structure, , para
iniciar el proceso del diseño de la estructura de acero.

Cuando el diseño este completo, un mensaje aparecerá indicando cuantas secciones de
diseño son diferentes de las secciones de análisis. Hacer click en el botón No para
cerrar la cajita que apareció.

Repetir las acciones de los Items L y M hasta que el análisis y diseño de las secciones
sean iguales, lo cual es indicado cuando no aparece el mensaje al final del diseño (y
"wait tour glass" tendrá que desaparecer). Esto podría tomar cinco o más iteraciones
para este ejemplo.

N. Cuando el análisis y diseño de las secciones son iguales, hacer click en el
botón Select All, , o hacer click en el comando Select menu > All, o presione
simultáneamente Ctrl. y A en su teclado para seleccionar todos los objetos en este
modelo.

O. Hacer click en el comando Design > Steel Frame Design > Make Auto
Select Section Null y haga click en OK para el mensaje resultante. Esto elimina las
secciones auto seleccionadas de las listas asignadas para los elementos de acero y
reemplaza estos con sus secciones actuales de diseño.

P. Hacer click en el comando Design > Steel Frame Design > Verify All
Members Passed. Un cuadro similar al mostrado en la figura 63 debiera aparecer
indicando que todos los miembros pasan.

<!-- p. 242 -->

Figura 63 Mensaje de alerta para verificar todos los elementos anteriores para un
diseño completo

Note que los miembros que no estén pasando en este estado es una indicación que las
secciones de la lista de auto selección son inadecuadas. El programa tendrá que usar
las secciones en la lista auto select para ambos análisis y diseño, buscando el resultado
inadecuado, en este caso, cualquiera de las secciones añadidas a la lista auto
seleccionadas o asignada a las secciones largas para los miembros que no pasaron y
continué con el proceso de diseño.

Q. Hacer click en el comando File menu > Save, o el botón Save, , para
guardar su modelo. El diseño de la estructura de acero y esta introducción del ETABS
Versión 8 esta ahora completa.
