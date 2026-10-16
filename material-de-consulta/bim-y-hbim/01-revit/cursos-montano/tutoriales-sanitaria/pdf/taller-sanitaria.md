---
type: libro
title: "3ds Max Design 2012 – para usuarios de AutoCAD"
author: "Fernando Montaño La Cruz"
categoria: "BIM Y HBIM"
paginas: 28
extraccion: "texto"
fuente: "local:E:/MATERIAL DE CONSULTA/BIM Y HBIM/01. Revit/CURSOS MONTAÑO/TUTORIALES SANITARIA/Pdf/Taller Sanitaria.pdf"
convertido: 2026-10-16
---

# 3ds Max Design 2012 – para usuarios de AutoCAD

> Texto extraído de `BIM Y HBIM\01. Revit\CURSOS MONTAÑO\TUTORIALES SANITARIA\Pdf\Taller Sanitaria.pdf` (28 páginas, texto). El PDF original está en el disco E: (MATERIAL DE CONSULTA); `<!-- p. N -->` marca el inicio de cada página.

<!-- p. 1 -->

Taller práctico de Revit:
Modelado de Instalación Sanitarias

Autor:

Fernando Montaño

<!-- p. 2 -->

Taller práctico de IS con REVIT autocadBIM.com

Lección 1Taller: Revit SANITARIA

Contenido de este taller:

 12 videos / duración: 2 hs. 54 min.

Lista de video-tutoriales:

Introducción a Instalaciones Sanitarias

\1. Introducción y configuración de la plantilla de proyecto (8:45)
\2. Conociendo la plantilla de proyecto (18:56)
\3. Modificando la plantilla de proyecto 7:43)
\4. Instalación ficticia de abastecimiento agua (21:58)
\5. Instalación ficticia de desagües (16:30)
\6. Artefactos sanitarios y sus conectores (16:51)
\7. Conexiones rápidas y por diseño de sistemas (11:55)

Proyecto de instalaciones Sanitarias

\8. Proyecto de instalaciones ¿Cómo iniciar? (15:00)
\9. Copiar y supervisar (12:34)
\10. Verificaciones y consejos previos (10:03)
\11. Tuberías de desagüe (18:42)
\12. Tuberías de abastecimiento (14:41)

arq Fernando Montaño 2

<!-- p. 3 -->

Taller práctico de IS con REVIT autocadBIM.com

Objetivos y metodología del taller

OBJETIVO:
El objetivo del taller es que el alumno desarrolle las capacidades necesarias para construir o modelar una
instalación sanitaria, básica, en Revit. Se da por hecho que toda persona que emprenda esta tarea, cuenta con
los conocimientos técnicos que la disciplina exige. Este taller aborda, únicamente, el uso de las herramientas de
Revit; todas las consultas sobre la disciplina «sanitaria» deberán ser realizadas al docente responsable de dicho
curso.

METODOLOGÍA:
La metodología a aplicar en el taller es la conocida con el nombre: Aprendizaje invertido con base en Proyectos.

¿En qué consiste?

El proceso de aprendizaje consta de tres etapas:

 El alumno aprende en su casa antes de participar en las clases, lo hace por medio de video-tutoriales y
realiza un ejemplo básico.
 El alumno participa de la clase, donde podrá evacuar dudas y ampliar conocimientos a través de
prácticas adicionales y el intercambio con sus compañeros de estudio.
 Aplica los conocimientos adquiridos en un proyecto más complejo, con apoyo docente.

PROTOTIPO DIGITAL vs representación simbólica 2D
Una pregunta que nos debemos formular antes de comenzar la instalación en Revit, es si deseamos dibujar los
planos de la instalación en base a «símbolos« o si deseamos modelar la instalación verdadera. Son tareas
diferentes y requieren de diferentes procedimientos.

El objetivo de este taller modelar la instalación verdadera y NO su representación simbólica. Hasta la actualidad
hemos dibujado «planos de sanitaria» que usan símbolos para representan a los objetos reales, pero en este
taller construiremos la instalación real; así que carece de sentido volver un paso atrás y representarlos
simbólicamente. En este taller construiremos un modelo 3D que podamos coordinar con las restantes disciplinas
del proyecto. Sí mostraremos como usar símbolos que representen a los objetos reales, pero será a modo
ilustrativo y NO con el objetivo de crear documentación completa.

arq Fernando Montaño 3

<!-- p. 4 -->

Taller práctico de IS con REVIT autocadBIM.com
\1. La mesa esta servida: Plantilla de proyecto

Sabido es que cada disciplina de Revit requiere del uso de herramientas especializadas, componentes específicos
y configuraciones correctas.

La terea de iniciar un proyecto de sanitaria es comparable a sentarnos a desayunar. Quizás no hay nada en la
heladera y primero debamos salir de compras, para después preparar el desayuno y por último poder sentarnos
a desayunar. Otra opción es contar con un desayuno buffet donde todo está a nuestro alcance y solo debamos
elegir y comenzar.

La opción «buffet» es la ideal para iniciar cualquier proyecto, o sea que todo lo que vayamos a necesitar esté
disponible.

La opción «buffet» nos la ofrecen las PLANTILLAS de PROYECTOS (o templates), archivos de extensión RTE con
componentes y características predefinidas, acordes al tipo de proyecto que realizaremos.

En este taller usaremos la plantilla: ORT_Sanitaria.RTE (Descargar plantilla)

Acceso rápido a la Plantilla de proyectos
Para optimizar el tiempo y acceder más rápido a nuestras plantillas de proyectos, debemos designarla en
Ubicación de archivos.

arq Fernando Montaño 4

<!-- p. 5 -->

Taller práctico de IS con REVIT autocadBIM.com

Este procedimiento reducirá los pasos de inicio a un nuevo proyecto y nos dará la tranquilidad de un comienzo
seguro.

Video 1: duración 8:45 minutos

Conociendo el «buffet» (Plantilla de proyecto)

Si bien una plantilla nos permite iniciar el proyecto sin demoras, debemos conocer su contenidos para poderlos
modificar y ampliar, cada vez que sea necesario. Antes de iniciar el proyecto analizaremos los aspectos
importantes que debe incluir una plantilla para instalaciones sanitarias y aprenderemos a guardarla para un uso
más rápido y sencillo.

Tuberías
Lo primero en lo que pensamos cuando debemos construir una instalación sanitaria o de plomería es en la
tubería que conducirá los fluidos, ya sean líquidos o gaseosos, ya sea en el abastecimiento como en el drenaje de
los mismos. Las instalaciones de tuberías son muchas más que para el abastecimiento y drenaje de agua, y para
su correspondiente ventilación; también son para el abastecimiento de gas, calefacción, riego, incendios y flujo
de un sinfín de líquidos y de gases en la industria.

Algunos materiales de tuberías son los siguientes:

 PVC (PoliCloruro de Vinilo) instalación hidráulica (fría) y sanitaria. Pegamento
 CPVC (PoliCloruro de Vinilo Clorado) instalación hidráulica (fría y caliente). Pegamento / Rosca
 PPR (Poli Propileno Random) instalación hidráulica (fría y caliente) Termofusión
 PPL (PoliPropiLeno) instalación hidráulica (fría y caliente). Rosca y Pegamento
 Polietileno reticulado Suelos radiantes y riegos. Muy flexibles
 Multicapa exterior polietileno (PE), aluminio (AL) e interior polietileno reticulado (PEX)
 Cobre instalación hidráulica (fría y caliente), instalaciones con vapor, gases, calefacción o aire
comprimido. Soldadura / Rosca

arq Fernando Montaño 5

<!-- p. 6 -->

Taller práctico de IS con REVIT autocadBIM.com

 Hierro galvanizado instalación hidráulica contra incendio, gas y climatización. Rosca / Soldadura
 Acero inoxidable instalación hidráulica vistas. Rosca / Soldadura / Presión

Sea cual sea la tubería que usaremos, está será de diferentes tamaños y es lo que se debe definir en Revit.

Para facilitar el entendimiento la plantilla incluye, tan solo, tubería de PPR (termofusión) para abastecimiento de
agua potable y PVC para desagües; cualquier otro tipo de tubería necesaria, deberá ser creado o importado. Los
aspectos esenciales de una tubería son definir correctamente su DI (diámetro interior) y DE ((diámetro exterior).

Idea: Es muy fácil importas configuraciones de tuberías de otro proyecto.

Uniones de tuberías
Las uniones son las piezas que permiten conectar o cerrar los diferentes tramos de tuberías; como ser codos,
curvas, cuplas, ramales, etc.

arq Fernando Montaño 6

<!-- p. 7 -->

Taller práctico de IS con REVIT autocadBIM.com

Enrutamiento
A medida que se traza una instalación, las piezas de unión se añaden de forma automática, asegurando el
correcto trazado de la misma. Por ejemplo, si el trazado gira en ángulo recto se añadirá un codo de 90, pero si
gira 45º, se añadirá uno de 45. Si trazamos la tubería en una dirección distinta a 90 o 45 grados, Revit NO lo
permitirá, ya que no dispondrá de la pieza para hacerlo.

Para añadir nuevos tramos de tuberías se requiere de la unión correcta, pero no basta con que exista la pieza, la
misma debe estar asociada a la tubería; a esto se le llama Enrutamiento.

En las preferencias de enrutamiento se definen el/los segmentos de tuberías que se podrán usar en un Tipo de
tubería y las piezas de unión.

En la plantilla se ofrece un tipo de sistema para desagüe que utiliza solo segmentos de PVC (IS_PVC_Desagüe),
pero bien se podría crear un tipo que incluyera segmentos de PVC, de Hierro y de Hormigón.

El uso de diferentes segmentos de tuberías podría relacionarse a los diámetros disponibles y, por ejemplo, usar
PVC para tamaños de 40 a 110 y hormigón de 150 a 500.

arq Fernando Montaño 7

<!-- p. 8 -->

Taller práctico de IS con REVIT autocadBIM.com

Desde las Preferencias de enrutamiento es posible acceder a los segmentos y tamaños de tuberías
(Configuración mecánica), ya sea para crear nuevos tipos de segmentos o modificar los existentes.

En la Configuración mecánica controlamos los posibles ángulos del trazado de la instalación, además de 90º; que
está predeterminado

arq Fernando Montaño 8

<!-- p. 9 -->

Taller práctico de IS con REVIT autocadBIM.com

Sistemas
Un sistema es un tramo de instalación que transporta un fluido entre dos puntos o accesorios. Por ejemplo, en la
instalación de abastecimiento de agua, desde el calefón hasta la ducha tendremos un sistema de agua fría y un
sistema de agua caliente. En la instalación de desagüe, desde la ducha a la caja sifonada tendremos un sistema
de desagüe secundario, y desde el inodoro a la cámara de inspección un sistema de desagüe primario; pero en
una vivienda también tendremos sistema de ventilación y de sistema evacuación de pluviales.

Los Sistemas se pueden ver en las familias del Navegador de proyectos. No es posible crear nuevas
clasificaciones, pero si es posible duplicar los sistemas existentes para crear nuevos Tipos y modificar sus
propiedades (para esto basta seleccionar las opciones, haciendo clic derecho sobre el sistema).

Cómo crear un nuevo Sistema de tuberías
Duplicar uno existente, cambiar su nombre y cambiar sus propiedades; a todas las opciones se accede mediante
el menú contextual (clic derecho). Por ejemplo Instalación de Agua Caliente Solar…

NOTA: Los colores usados en los sistemas de tuberías de la Plantilla se corresponden con los definidos en las
normas UNIT 14-2019 Símbolos gráficos para instalaciones sanitarias.

arq Fernando Montaño 9

<!-- p. 10 -->

Taller práctico de IS con REVIT autocadBIM.com

Sistema  tuberías + uniones = Tipo de tubería
Los Sistemas pueden usar diferentes tipos y secciones de tuberías; por ejemplo: un sistema de agua potable fría
puede usar tuberías de materiales diferentes en tramos subterráneos, en la bajada del tanque de agua o en el
interior de una vivienda. Los Sistemas son independientes de las tuberías, pero seguramente no usaremos
hierro de 100 mm en un sistema de agua potable; por lo tanto, a pesar de dicha independencia, en la práctica
existirá una relación entre las tuberías y los sistemas. Cuando definimos un Tipo de tubería, lo hacemos
pensando en el Sistema específico.

Un sistema de desagüe primario puede incluir tuberías de PVC, de hierro y de hormigón, y en cada caso puede
incluir tuberías de diferentes secciones y uniones diferentes; nada puede quedar librado al azar, por lo tanto
debemos definir un Tipo de tubería que incluya los materiales, las secciones y las uniones que podremos usar en
dicho sistema de desagüe primario.

Tuberías
La plantilla incluye tuberías de Termofusión (20, 25, 32, 40 y 50) para instalaciones de abastecimiento de agua y
PVC (40, 50, 63, 100, 150 y 200) para instalaciones de desagüe y ventilación.

Accesorios para tuberías

Componentes que serán parte del sistema de tuberías y que, en general, se usan para controlar el pasaje de los
fluidos; por ejemplo llaves de paso.

arq Fernando Montaño 10

<!-- p. 11 -->

Taller práctico de IS con REVIT autocadBIM.com

Aparatos sanitarios

Son Familias de Revit que incluyen una o varias conexiones para tuberías. Los aparatos sanitarios pueden ser
piezas de la instalación misma (resumideros, cajas sifonada, graseras, cámaras de inspección…) o mobiliario que
se conectará a dicha instalación (inodoro, bidé, piletas, calefón, tanque de agua…)

Tuberías flexibles

Como su propio nombre lo indica, son tuberías flexibles que permiten seguir cualquier recorrido, por ejemplo de
una o varias curvas; un ejemplo de ello son las colillas que usamos para conectar los aparatos sanitarios con los
puntos fijos de las tuberías.

arq Fernando Montaño 11

<!-- p. 12 -->

Taller práctico de IS con REVIT autocadBIM.com

Video 2: duración 18:56 minutos / Video 3: duración 7:43 minutos

\2. Las bases para construir una instalacio n Sanitaria

Las instalaciones sanitarias son todo el conjunto de tuberías de agua fría, agua caliente, desagües, ventilaciones,
cajas de registro, aparatos sanitarios, entre otros, que sirven para abastecernos de agua potable y eliminarla a
través de los desagües.

El trazado de estas instalaciones se construirá de modo lineal, definiendo los extremos de cada tramo de tubería,
que unirá los puntos alimentación o evacuación de líquidos (conexiones). Las tuberías recorren un espacio
tridimensional, lo cual es un factor que deberá ser tenido en cuenta permanentemente. Lo más cómodo es
definir el recorrido en una vista de planta, pero las tuberías irán cambiando de altura, tendrán saltos y algunas
tendrán pendientes, por ello se requiere de una visualización completa permanentemente (alzados, secciones,
vistas 3D).

Idea: Antes de iniciar el trazado de las tuberías se debe definir la ubicación de los aparatos
sanitarios y la altura a la que se colocarán dichas tuberías; el mejor trazado será el de menor
recorrido, que por su parte será el que genere menor pérdida de presión, y el que tendrá
menor cantidad de insumos y de mano de obra.

Trazar una tubería de cero
Para trazar una tubería nueva desde cero, el procedimientos es ir al comando Sistema>Tubería (TI)…

\1. Seleccionar el Tipo de tubería
\2. Seleccionar el Tipo de sistema al que pertenecerá
\3. Designar el Segmento de tubería si corresponde (aplica solo a Tipos de tuberías que emplean diferentes
segmentos o materiales, por ejemplo tramos de termo fusión y de cobre)
\4. Designar el diámetro de tubería a colocar.
\5. Establecer la altura a la que trazaremos la tubería (esta opción solo está disponible cuando trazamos las
tuberías en una vista de planta)

arq Fernando Montaño 12

<!-- p. 13 -->

Taller práctico de IS con REVIT autocadBIM.com

Añadir tramos de tubería en una instalación existente
Para añadir nuevos tramos a tuberías existentes, tan solo se necesitan activar las opciones que permitan
heredar, automáticamente, la altura y tamaño existentes.

arq Fernando Montaño 13

<!-- p. 14 -->

Taller práctico de IS con REVIT autocadBIM.com

Añadir tuberías a partir de Aparatos sanitarios
Con solo seleccionar un aparato sanitario, se visualizarán sus conexiones, y bastará con tirar del extremo para
estar añadiendo una tubería.

Tuberías con pendiente
En el caso de tuberías con pendiente, se deberá indicar si hacia arriba o hacia abajo, y cuál es dicha pendiente.

Herramientas de edición útiles en tuberías
Todas las herramientas que usamos para editar otros objetos de Revit, como por ejemplo los muros, se pueden
usar de igual forma en tuberías, ya sea para moverlas, copiarlas, alinearlas, desfasarlas, incluso para crear una
esquina (en la que automáticamente se añadirá un codo) o para alargar un tramo hasta otro, donde
automáticamente se añadirá una Te).

arq Fernando Montaño 14

<!-- p. 15 -->

Taller práctico de IS con REVIT autocadBIM.com

Nota: Cuando estas herramientas no funcionan, puede ser porque los ejes de las tuberías se
ubican a alturas distintas; bastará con seleccionar los tramos para ver las alturas de sus
extremos, y bastará copiar los valores de un extremo a otro para solucionar el problema.

Marcador de posición de tuberías
Las marcas de posición son líneas que representan una tubería y que tienen asociados todas las características
de una tubería normal.

arq Fernando Montaño 15

<!-- p. 16 -->

Taller práctico de IS con REVIT autocadBIM.com

En cualquier momento se podrán transformar dichas líneas en las tuberías correspondientes, bastará seleccionar
los marcadores y hacer clic en

Video 4: duración 21:58 minutos / Video 5: duración 16:30 minutos

arq Fernando Montaño 16

<!-- p. 17 -->

Taller práctico de IS con REVIT autocadBIM.com

Añadir conexiones a las familias
Los Aparatos sanitarios podrían carecer de conexiones y será necesario incorporarlas, para lo que habrá que
editar las familias.

Ya dentro de la Familia hay que crear una Conector de tuberías y colocarlo en el plano que corresponda (quizás
haya que añadir un volumen para generar el plano); después se editan sus propiedades, como mínimo: el
Diámetro, la dirección del flujo (Entrante o Saliente) y la clasificación del sistema al que será conectado.

Video 6: duración 16:51 minutos

Añadir tuberías desde los aparatos
Basta seleccionar un aparato para ver sus
conexiones y y los diámetros de tubos que
corresponderá colocar. Basta hacer clic en el icono
de la conexión para comenzar una tubería. Se
deberá respetar la línea punteada en el eje de la
tubería, de lo contrario no se podrá crear.

Este procedimiento condicionará la ubicación de la
tubería en la pared y colocará un tramo rígido, lo
cual no será lo habitual; por lo tanto no siempre
podremos usar este procedimiento. En todos los casos donde la conexión se realice por tubo flexible, este
procedimiento no será muy útil. Sí lo será en todos los casos donde la instalación lleve una conexión rígida, por
ejemplo en el desagüe del inodoro

arq Fernando Montaño 17

<!-- p. 18 -->

Taller práctico de IS con REVIT autocadBIM.com
Sistemas de tuberí as

Abriendo en Navegador de sistemas visualizaremos los diferentes sistemas MEP y los aparatos asignados a estos
o los NO asignados a ninguno.

Para crear un Sistema de tuberías bastará seleccionar los aparatos que vinculará, hacer clic en Tuberias,
designar el Tipo de tuberías correspondientes y asignarle un nombre; por ejemplo, para la instalación sanitaria
del baño 1, correspondiente al agua fría podría ser: IS-B01_AF

arq Fernando Montaño 18

<!-- p. 19 -->

Taller práctico de IS con REVIT autocadBIM.com

Una vez definidos todos los sistemas, tendremos una vista rápida y sencilla de todos sus componentes, del flujo y
de las secciones de las respectivas tuberías. Bastará la selección de un sistema o aparato en el navegador, para
que se lo identifique en el modelo.

En todo momento se podrá editar un sistema para añadir o eliminar aparatos sanitarios.

Diseño rápido del sistema
Si bien la herramienta de Diseño rápido NO dará una solución exacta, sí puede crear de manera simple y rápida
un acercamiento a la solución que necesitamos. Para esto basta seleccionar el sistema (1) y hacer clic en Generar
Diseño (2). Se deberá Configurar los Tipos de tubería para el ramal Principal y sus Ramificaciones (3), y después
experimentar con las diferentes soluciones que Revit nos ofrece de manera automática (punto 4 de la siguiente
imagen). En todo momento se podrá conmutar entre la solución automática y editar manualmente el diseño (5).

arq Fernando Montaño 19

<!-- p. 20 -->

Taller práctico de IS con REVIT autocadBIM.com

Una vez que alcancemos la mejor opción, se deberá Finalizar el diseño (6).

El resultado final será una tubería que habrá que modificar mucho, pero algunas veces servirá de punto de
partida. El mayor problema del diseño rápido es que conectará todos los puntos con tubería rígida, pero en la
realidad los tramos de conexión entre el sistema y el aparato, suele ser con tubería flexible (colillas).

Video 7: duración 11:55 minutos

arq Fernando Montaño 20

<!-- p. 21 -->

Taller práctico de IS con REVIT autocadBIM.com
Proyecto de Sanitaria

Al momento de iniciar un proyecto de sanitaria, lo habitual será contar con un modelo de arquitectura en fase de
diseño, o sea que podrá tener modificaciones en cualquier momento. Esto nos obliga a crear un vínculo
dinámico entre ambos modelos. A los efectos de aprender en un ejemplo concreto, utilizaremos el archivo
«ARQ_ Ejercicio.rvt» (descargar ahora).

La vivienda incluye baños en PB y PA, y una cocina en PB. El proyecto es tan solo la excusa para aprender a
construir una instalación sanitaria en un contexto real; para estudiar problemas frecuentes, analizar soluciones
posibles y conocer buenas prácticas de ejecución. Mostrar la construcción de toda la instalación demandaría de
muchos videos, en los que se repetirían los mismos procedimientos y no se aportaría nada nuevo; por lo tanto
en los videos mostraremos cómo construir los aspectos más relevantes.

arq Fernando Montaño 21

<!-- p. 22 -->

Taller práctico de IS con REVIT autocadBIM.com

Vincular el proyecto de ARQ
Procedimiento para vincular el Modelo de ARQ a la Plantilla de sanitaria:

\1. Iniciar un proyecto nuevo a partir de la Plantilla de sanitaria
\2. Vincular el archivo de Revit a nuestro nuevo proyecto, haciendo coincidir Centro a centro, para que el
proyecto quede dentro del área definida para trabajar.

Centro a centro es una opción que inserta el modelo en un punto casi al azar, y que impedirá toda referencia
rigurosa entre un modelo y el otro; pero esto no es problema, ya que el punto de relación entre ambos
(Coordenadas compartidas) lo tomaremos del vínculo mismo.

arq Fernando Montaño 22

<!-- p. 23 -->

Taller práctico de IS con REVIT autocadBIM.com

Después de realizar el procedimiento comprobaremos la nueva ubicación del Punto de reconocimiento - interno
que nos permitirá intercambiar geometría con total precisión.

Video 8: duración 15:01 minutos

Sentar base de igualdad entre las disciplinas: Copiar/Supervisar
Hay componentes del proyecto de ARQ que deberemos seleccionar o manipular en el modelo de sanitaria; como
por ejemplos los niveles y los aparatos sanitarios. Por otro lado, si modificamosr estos elementos, los
responsables de la arquitectura deberán saberlo, independientemente de que les avisemos o no. Para llevar
estos controles con rigurosidad Revit nos ofrece la herramienta Copiar/Supervisar

Debemos comenzar por los niveles en una vista apropiada; por ejemplo en un Alzado. El procedimiento de
Copiar/Supervisar creará copias de los elementos seleccionados en el archivo actual, pero vinculados al modelo
original, para supervisarlos en cualquier momento. La copia de elementos puede ser individual o Múltiple (4),
como así también por Lotes.

arq Fernando Montaño 23

<!-- p. 24 -->

Taller práctico de IS con REVIT autocadBIM.com

Nota: Después de copiar los niveles del proyecto, borrar el nivel existente en la plantilla
(+0.00 Nivel Plantilla).

Una Copia por lotes requiere de una Configuración de coordinación previa en la que se podrán especificar las
categorías permitidas para copia por lote, si se copiará el elemento original o si se remplazará por uno de la
Plantilla de Sanitaria. Después de la configuración bastará un clic en Copiar por lotes para crear copias de todos
los componentes de instalaciones configurados.

Vistas de planta para sanitaria
Acto seguido habrá que crear las vistas de planta para la instalación sanitaria, basadas en la Plantilla de vista
correspondiente.

arq Fernando Montaño 24

<!-- p. 25 -->

Taller práctico de IS con REVIT autocadBIM.com

Video 9: duración 12:34 minutos / Video 10: duración 10:03 minutos

Instalacio n de desagu e

La instalación de desagüe presentas mayores desafíos que la de abastecimiento, en especial aquellas que
evacuarán por gravedad en base a pendiente. Estas instalaciones pueden presentarán puntos críticos que habrá
que respetar y que condicionarán el trazado; como por ejemplo profundidad mínima de salida, profundidad
máxima de una cámara o la profundidad de conexión a la red pública. Estas condicionantes pueden determinar si
debemos comenzar del punto más alto o del más bajo.

Para analizar una multiplicidad de factores que inciden en el trazado de la instalación de desagüe, en los videos
mostraremos cómo ejecutar las instalaciones correspondientes al baño principal y la cocina.

Baño principal

Idea:
\1. Partir del punto más comprometido, la conexión del inodoro al punto de bajada.
\2. Definir con líneas el recorrido de las tuberías, de acuerdo a las restricciones de ángulos.

Idea:
\3. Visualizar la instalación en múltiples vistas: planta, secciones y 3D.

arq Fernando Montaño 25

<!-- p. 26 -->

Taller práctico de IS con REVIT autocadBIM.com

Una posible instalación de desagüe para el baño principal es la siguiente, pero existen muchas; por ello la
importancia de concentraros en los procedimientos y NO en el ejemplo concreto o la resolución puntual.

arq Fernando Montaño 26

<!-- p. 27 -->

Taller práctico de IS con REVIT autocadBIM.com

Tuberías flexibles
Las tuberías flexibles se deben crear, preferentemente, donde sea posible visualizar claramente los puntos que
se conectarán; o sea en una vista.

Video 11: duración 18:42 minutos

Instalacio n de agua frí a y caliente

Los puntos de partida en las tuberías de agua potable (suministro de la red pública o del tanque de agua) no
suele condicionar el trazado de las mismas, con lo cual podemos comenzar por la instalación interna de cualquier
habitación. Solo se necesita saber por dónde ingresará la tubería (tanto de agua fría como de agua caliente) y la
ubicación de los aparatos sanitarios. Muchos de los aparatos sanitarios tampoco condicionarán una ubicación
exacta de los puntos de tuberías rígidas, ya que su conexión a dichas tuberías será por medio de un elemento
flexible (colilla). A los efectos de esta práctica, las condicionantes para el baño principal en Planta Alta serán las
siguientes:

\1. Tubería de agua fría de 32 mm
\2. Ubicación del termo-tanque

arq Fernando Montaño 27

<!-- p. 28 -->

Taller práctico de IS con REVIT autocadBIM.com

Otras definiciones:

 Las tuberías de agua fría y caliente en el interior del baño serán en termofusión de 20 mm.
 Se colocará una llave de corte en el ingreso del agua fría al baño.
 Las conexiones de agua caliente serán a la izquierda y de agua fría a la derecha.
 Las conexiones al inodoro, bidé y lavatorio serán por medio de tuberías flexibles (colillas), al igual que el
desagüe del lavatorio.
 En la bañera se colocará una monocomando empotrada con separación de 15 cm.
 Los puntos de conexión de agua estarán a las siguientes alturas:
o Cisterna del inodoro = 25 cm
o Bidé = 25 cm
o Termotanque = 150 cm
o Ducha bañera = 105 cm
o Lavabo = 60 cm

Nota: En el video se muestran todos los detalles de esta instalación.

Video 12: duración 14:41 minutos

arq Fernando Montaño 28
