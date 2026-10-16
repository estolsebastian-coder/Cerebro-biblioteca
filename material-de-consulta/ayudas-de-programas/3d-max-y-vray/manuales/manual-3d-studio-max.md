---
type: libro
title: "MANUAL 3D STUDIO MAX"
author: "vhfranco"
categoria: "AYUDAS DE PROGRAMAS"
paginas: 72
extraccion: "texto"
fuente: "local:E:/MATERIAL DE CONSULTA/AYUDAS DE PROGRAMAS/3D MAX Y VRAY/MANUALES/MANUAL 3D STUDIO MAX.pdf"
convertido: 2026-10-16
---

# MANUAL 3D STUDIO MAX

> Texto extraído de `AYUDAS DE PROGRAMAS\3D MAX Y VRAY\MANUALES\MANUAL 3D STUDIO MAX.pdf` (72 páginas, texto). El PDF original está en el disco E: (MATERIAL DE CONSULTA); `<!-- p. N -->` marca el inicio de cada página.

<!-- p. 1 -->

Modelación Curso 3D Studio Max

UNAM ‐ DGSCA / Victor Hugo Franco Serrano 1

<!-- p. 2 -->

Modelación Curso 3D Studio Max

Curso 3D Studio Max
D.C.V. Victor Hugo Franco Serrano
Dept. de Realidad Virtual, DGSCA UNAM
vhfranco@unam.mx

\1. INTRODUCCIÓN

1.1 Introducción sobre modelado de bajos polígonos usando MAX

3d Studio Max posibilita la creación de modelos y escenarios tridimensionales animables y
exportables para su render, visualización o simulación. Dependiendo de cuál sea su objetivo
final de los modelos estos pueden ser de altas cantidades de polígonos o de bajas cantidades
de polígonos.

El render emplea modelos de diferentes calidades pero no se preocupa en el peso, pues la
operación de renderizado puede tardar varios segundo e incluso horas en ser representada, a
diferencia de esto el tiempo real debe representar los elementos en pantalla de manera
inmediata para que el entorno sea creíble y manejable.

El objetivo de este curso es el aprendizaje de la herramienta 3D Studio Max orientada a la
creación de modelos y escenarios que sean factibles de uso dentro de entornos
tridimensionales interactivos para tiempo real.

Para lograr esto debemos tener en cuenta en todo momento que la cantidad de polígonos y el
uso de texturas pueden afectar el rendimiento del sistema alentándolo, nuestra responsabilidad
como modeladores para tiempo real es el realizar texturas y modelos ligeros que no afecten el
rendimiento del sistema pero que conserve la calidad gráfica necesaria.

A lo largo del curso aprenderá el manejo de materiales y texturas, técnicas de modelado, la
interfaz de max, técnicas de animación básica y algunas herramientas adicionales que
ayudaran durante el modelado.

UNAM ‐ DGSCA / Victor Hugo Franco Serrano 2

<!-- p. 3 -->

Modelación Curso 3D Studio Max

1.2 Aprendizaje de la Interfaz

\1. Menús desplegables (Pulldowns): este tipo de menús contienen en forma de listado muchos de los
comandos que también se encuentran de manera recurrente en forma de ícono en varias de las otras
secciones de la interfaz gráfica. Se puede citar entre estos menús: File, donde se pueden salvar,
importar y exportar archivos, además de manejar algunas opciones de configuración y preferencias.

UNAM ‐ DGSCA / Victor Hugo Franco Serrano 3

<!-- p. 4 -->

Modelación Curso 3D Studio Max

\2. Deshacer y rehacer (Undo/Redo): una de las mejores aportaciones en 3D Max, es
la posibilidad de tener un número ilimitado de deshacer y rehacer los pasos que se van
realizando durante la creación de una escena. Este procedimiento consta de dos botones;
el que tiene la flecha apuntando hacia la izquierda corresponde al comando “deshacer” y
el que apunta a la derecha es para “rehacer”.

\3. Controles de selección:
Muchos de los comandos de trabajo requieren del uso de parámetros de selección.

Este grupo de botones permite la selección y manipulación de los objetos y sus componentes de
variadas formas.

\4. Restricciones de eje y “array” (arreglo, matriz): estos botones
ayudan a limitar las transformaciones que se les hagan a los objetos,
para que éstas únicamente se puedan aplicar en una sola dirección o
plano de los ejes cartesianos X, Y o Z. Y "array" (arreglo, matriz), que
hace varias copias de un mismo objeto con distintos arreglos radiales o
lineales.

\5. Reflejar/Alinear (Mirror/Align): la única función de estos botones es tener un acceso
directo a los comandos: “mirror”, que reproduce objetos en una posición frente a frente y
“align”, alínea unos objetos con respecto a otros de la escena.

\6. Selección por Conjuntos Nombrados (Named Selection Sets): como las selecciones son
tan importantes para los modificadores y las transformaciones, 3D Max permite salvar cada
selección con un nombre y es en esta lista donde se puede acceder de manera rápida a
cualquiera de las selecciones nombradas previamente.

\7. Editor de materiales (Material Editor): este botón abre la ventana del editor de materiales,
donde se podrán crear materiales y aplicarlos a los objetos.

\8. Control de claves por pistas (Track View) y Vista Esquemática (Schematic
View): Track View abre la ventana del Controlador de claves que se utilizan para
manejar todos los parámetros de animación en la escena. Schematic View presenta de
manera gráfica todos los comandos con los que ha sido tratado, hasta el momento,
cada objeto durante su creación, utilizando un esquema de diagrama de flujo.

UNAM ‐ DGSCA / Victor Hugo Franco Serrano 4

<!-- p. 5 -->

Modelación Curso 3D Studio Max

\9. Controles de renderizado (Render Controls): este panel de botones da
acceso a todas las opciones de generación final de imágenes (Render) y sus
respectivas ventanas de diálogo. Una de las opciones más útiles es la
Ventana de Renderizado Activo (Active Shade Floater): esta ventana muestra
los objetos de la escena, y actualiza en tiempo real, mientras se conserve
abierta, todos los cambios que se les aplique a los materiales y texturas de
los objetos presentes en la escena.

\10. Panel de comandos (Command Panel):

El panel de comandos es la parte más importante del sistema de 3D Max en
su etapa de modelado. A través de este panel se puede acceder a la mayoría
de los comandos. El panel de comandos tiene una estructura descendente a
partir de seis etiquetas principales: Create, Modify, Hierarchy, Motion, Display
y Utility. Con cada etiqueta se llega a comandos correspondientes a cada tipo.

\11. Área de despliegue de comandos (Command Rollout Area): cada vez que se escoge un
comando en el panel de comandos, todos los parámetros referentes a él, aparecen en el área de
despliegue de comandos. Se le llama de despliegue porque las opciones de muchos de los
comandos necesitan un área más larga que las dimensiones de la pantalla. Cada uno de los
despliegues puede ser contraído o expandido para poder visualizar a los comandos y parámetros a los
que están asociados.

\12. / Controles de Vistas (Viewport Controls): estos botones
ofrecen todos los controles necesarios para manipular y cambiar
la configuración de todas las vistas presentes en la interfaz.

\13. Controles de Animación y Tiempo
(Animation Playback Controls): esta serie de
botones sirven para controlar el sistema interactivo
de reproducción de animaciones en 3D Max.

UNAM ‐ DGSCA / Victor Hugo Franco Serrano 5

<!-- p. 6 -->

Modelación Curso 3D Studio Max

\14. Botón para animar automáticamente
(Auto Key Button): este botón controla la creación de llaves de animación. Cuando esté
activo se pondrá rojo y aparecerá una línea roja alrededor de la vista activa en ese
momento, además, cada vez que se haga una transformación o una modificación a un
objeto, será creada una clave de animación.

\15. Anclas de Ajuste (Snap Locks): existen diferentes tipos de anclas
(desplazamiento, rotación, escala y graduación por unidades) que pueden ayudar
a dibujar de una manera más precisa. Este panel de botones permite activar y
desactivar los diferentes tipos de anclas a voluntad.

\16. Selección por cruce (Crossing Selection): este botón controla la forma en que van a
funcionar las selecciones por ventana. Si el botón está activado, cualquier objeto que se
encuentre parcial o totalmente dentro de la ventana de selección, será seleccionado. Si se
encuentra desactivado, sólo serán seleccionados los objetos que se encuentren totalmente
dentro de la ventana de selección.

\17. Interruptor de acceso por teclado (Plug-in Keyboard Shortcut Toggle): existen en 3D
Max accesos directos a ciertos comandos mediante combinaciones de teclas, pero algunos de
los programas externos (plug-ins) que se pueden instalar al sistema tienen sus propias
combinaciones de teclas. Este botón funciona como un interruptor, cuando está desactivado se
encuentran activas las combinaciones de teclado propias de 3D Studio Max, y cuando se
encuentra activado las combinaciones activas son las del programa suplementario que se
encuentre abierto en ese momento.

\18. Ancla de selección (Lock Selection): después de crear una selección, ésta puede ser
asegurada y entonces no se pueden añadir o remover objetos de dicha selección. Este botón
activa y desactiva este seguro.

\19. Barra de estado (Status Bar): la barra de estado está mostrando constantemente lo que sucede en
el programa, en cuanto a comandos, selecciones y otros eventos. Si el usuario requiere ubicarse, puede
consultar la barra de estado en cualquier momento.

UNAM ‐ DGSCA / Victor Hugo Franco Serrano 6

<!-- p. 7 -->

Modelación Curso 3D Studio Max

\20. Lector de coordenadas (Coordinate Readout): el
lector de coordenadas es muy útil cuando se quiere saber
la ubicación exacta del cursor en el espacio tridimensional.
Este lector muestra tanto lecturas de las coordenadas X, Y,
y Z del cursor, como de porcentajes de ciertas
operaciones, por ejemplo, de escalar.

\21. Desplazador de tiempo de animación (AnimationTime Slider): este botón de deslizamiento
permite navegar en los cuadros de una animación mostrando siempre el cuadro en el que se encuentra
posicionado el sistema. El botón se desliza ubicando el cursor sobre él y desplazando el ratón sin dejar
de oprimir el botón izquierdo, mientras la animación se reproduce de manera interactiva.

\22. Vistas o Cuadrantes (Viewports):
las vistas permiten visualizar la geometría, materiales, luces,
cámaras y escenas que el usuario ha creado en 3D Studio
Max. Las vistas pueden ser configuradas con muy diversos
parámetros. Una de las herramientas más útiles, que presenta
el control de vistas es la posibilidad de cambiar sus
dimensiones simplemente moviendo el cursor hasta alguna de
las barras que separa un cuadro de vista del otro, entonces el
propio cursor cambia la forma de su ícono, indicando que, al
apretar el botón izquierdo del ratón y moviéndolo, se puede
deslizar la barra completa, con lo cual se alterará el tamaño de
las ventanas a las que delimita la barra en cuestión.

\23. Regleta de control de funciones animadas Se trata de una barra de control situada en la parte
inferior de las vistas, graduada en 10 segmentos
que, a su vez, están divididos de tal manera que
cada división representa una posición de un
cuadro para cada imagen de la animación. En esta
regla graduada van a aparecer cada una de las
funciones animadas que se hayan aplicado al
objeto que esté seleccionado en ese momento,
representada por un rectángulo rojo sobre la línea
del cuadro presente.

UNAM ‐ DGSCA / Victor Hugo Franco Serrano 7

<!-- p. 8 -->

Modelación Curso 3D Studio Max

\24. Modo de Transformación Absoluta (Absolute Mode Transform Type In) y Modo de
Transformación Relativa (Offset Transform Type In): este interruptor se utiliza para
trabajar con el objeto seleccionado en ese momento, dando la posibilidad de cambiar el
sistema de unidades de las coordenadas que se deseé en el momento de la aplicación de
transformaciones de movimiento, rotación o escala; o sea, que las unidades sean absolutas,
relacionadas directamente con el punto de origen universal 0,0,0, o que las unidades sean
relativas, es decir, que las coordenadas base sean las del objeto origen, justo antes de
empezar a modificarlo.

\25. Clic derecho del cursor: esta opción aumenta el
número de posibilidades de edición, con sólo aplicar un clic
derecho sobre el objeto seleccionado o el eje de
coordenadas del mismo objeto.

Así, aplicando el clic derecho se puede acceder
directamente a todo el panel de opciones de presentación
(Display), todo el panel de propiedades de transformación
(Transform) movimiento, giro, y escala, y dependiendo del
tipo de objeto que se edite, se pueden usar también
paneles de herramientas propias de la elaboración del
objeto.

1.3 Manejo de vistas y modos de vistas

3D Studio Max posee 4 vistas que son intercambiables, además de varios modos de ver a los objetos, por ejemplo el
modo solido, modo wireframe, modo bounding box.

UNAM ‐ DGSCA / Victor Hugo Franco Serrano 8

<!-- p. 9 -->

Modelación Curso 3D Studio Max

Para cambiar vistas en max se debe:

Dar clic derecho sobre el área que
nombra a la vista, en la imagen
podemos observar el menú
emergente que sale al dar clic en el
viewport left.

Esto desplegara el menú emergente que contiene Views, se da clic en Views.

En la imagen se observan los
diferentes tipos de vistas dentro
del menú Views.

Para intercambiar las vistas
debemos dar clic en cualquiera
que queramos y se cambiara
automáticamente

Es posible tener repetidas varias
vistas iguales en max, aunque
no tendría mucho sentido ver al
mismo objeto repetido varias
veces en la misma vista.

UNAM ‐ DGSCA / Victor Hugo Franco Serrano 9

<!-- p. 10 -->

Modelación Curso 3D Studio Max

Es posible definir el cómo se van
a ver en tiempo real los objetos
de la escena, por ejemplo la
esfera se ve suavizada y
representa las luces de su
entorno.

Pero si damos clic en wireframe
el modo de visualizar la esfera
cambia. Existen varios modos de
visualizar los elementos de la
escena, estos son útiles al
momento de modelar los objetos.

UNAM ‐ DGSCA / Victor Hugo Franco Serrano 10

<!-- p. 11 -->

Modelación Curso 3D Studio Max

1.4 Uso y configuración de referencias para modelar

Por lo general es más fácil modelar a los objetos cuando hacemos uso de referencias, estas
pueden ser dibujos, fotografías, planos o diagramas esquemáticos del objeto a representar. Su
uso es recomendable aunque a veces es imposible tenerlos.

Referencia frontal Referencia lateral Referencia superior Referencia perspectiva

En la imagen podemos observar las referencias usables para el modelado de la casa.

1.5 Pensamiento del modelador para tiempo real

Antes de comenzar el aprendizaje de modelado es necesario reflexionar sobre el pensamiento que se
debe tener al momento de modelar.

Por ejemplo al modelar objetos orgánicos deberemos en todo momento tener el control del objeto y de su
cantidad de polígonos, de ser posible se emplearan técnicas adicionales que faciliten el modelado, pero
sin afectar al conteo de polígonos.

Pensando en la representación de la realidad, este tema es esencial puesto que en tiempo real no
podemos representar la realidad tal cual, lo que se realiza es una interpretación y síntesis de las formas
de los objetos para hacer un simil con baja cantidad de polígonos. Esto es fundamental a la hora de estar
modelando.

Pensar por ejemplo en representar a un árbol contextura y no con geometría son habilidades que el
modelador debe desarrollar.

Ya en el modelado para el proyecto IXTLI correspondiente se deberá evaluar la importancia de cada
objeto a modelar, si se va a animar y como sería más fácil resolver geométricamente el objeto y la
textura, por el momento no es algo que el curso incluya pero en cursos posteriores estos temas serán
mencionados y ejemplificados.

\2. GENERACIÓN DE OBJETOS 3D

Antes de comenzar a revisar las opciones de creación de volúmenes primitivos, es importante especificar
algunas características de los objetos en 3D Studio Max.

Primero es importante saber que cada objeto de 3D debe tener un nombre único, se pueden nombrar
varios objetos con el mismo nombre pero esto podría ocasionar problemas posteriores si se quiere
seleccionar alguno de ellos mediante su nombre. Para nombrar a los objetos se puede utilizar casi
cualquier caracter, además de que 3D Max es sensitivo a mayúsculas y minúsculas, así que dos objetos
podrían ser llamados: “casa” y “Casa”, por ejemplo.

Pero la mejor opción es asignar un nombre a los objetos que los relacione con su función en la escena,
como “entrada frontal” o “perno tapa 5”.

UNAM ‐ DGSCA / Victor Hugo Franco Serrano 11

<!-- p. 12 -->

Modelación Curso 3D Studio Max

Otra de las características propias de cada objeto dentro de la escena es el color, el color lo
asigna el programa de manera aleatoria a cada objeto, pero también puede ser escogido por el propio
usuario. 3D Max soporta 24 bits en color, es decir 16 millones de tonos diferentes, así que prácticamente
se puede asignar un color diferente a cada objeto.

Para cambiar el nombre y color de un objeto se hace a través del
comando de despliegue “Name and color” (nombre y color), éste es el
segundo comando de despliegue debajo de la etiqueta “Create” del panel
de comandos, el cual consiste en una caja de diálogo y una casilla de
color.
Nombre y color

Si se desea cambiar el nombre del objeto
simplemente se selecciona el campo y se sustituye el
nombre. Si se va a cambiar el color debe darse un
clic en la casilla de color para abrir la Ventana de
diálogo de color de objetos.

Para cambiar el color, simplemente se elige una
casilla en la paleta y se cambiará el color del objeto
que estuviera seleccionado.

2.1 Modelado usando primitivas

Los volúmenes básicos son objetos muy sencillos como cajas, esferas, etc. que quizá no presenten
mucha complejidad pero con la combinación de estos objetos es posible construir objetos más complejos
como automóviles o utensilios electrodomésticos.

Primitivas refiere al hecho de que estos objetos pueden modificarse mediante números o parámetros y
en todo momento es posible regresar a su estado original, por ello también son llamados paramétricos.

A continuación se analizan los parámetros de creación de los seis volúmenes básicos más comunes:

Caja Esfera Cilindro Cono Tubo Toroide

Cada volumen básico tiene su propia secuencia de construcción y sus propios parámetros. Se utilizará
“box” para explicar el proceso de creación de estos volúmenes.

UNAM ‐ DGSCA / Victor Hugo Franco Serrano 12

<!-- p. 13 -->

Modelación Curso 3D Studio Max

\1. Box: para construir un prisma rectangular hay que empezar
seleccionando la etiqueta “create” en el panel de comandos y escoger
“geometry” de entre las opciones que presenta su propio panel y por
último, dar un clic en el botón de “box”.

Si se quiere saber cuál es el siguiente paso, siempre hay que consultar
la barra de estado, en este caso indica que hay que hacer “clic and drag”
con el ratón, es decir, arrastrar el ratón abriendo una ventana para
definir la dimensión del ancho (width) y una para la dimensión del
largo (length) que forman la sección del prisma. Por último, se mueve el
ratón para definir una última dimensión de altura (height), quedando así
construido el prisma rectangular.

Cuando se construye moviendo el ratón es difícil lograr dimensiones
precisas, pero se puede llegar a medidas aproximadas y después llenar
los campos del área de comandos desplegables llamada “Parameters”
con cifras exactas.

Se presentan ahora los parámetros de los volúmenes primitivos más usuales, en secuencia de
construcción:

\2. Esfera: radio (radius) y número de segmentos (segments).

\3. Cilindro: radio, altura, segmentos en la altura, segmentos
en las tapas y número de lados (radius, height, height
segments, caps segments & sides).

\4. Toroide: radio externo, radio interno, rotación, giro,
segmentos y lados (radius1, radius2, rotation, twist, segments
and sides).

\5. Cono: radio de base, altura, radio de punta, segmentos en
la altura, segmentos en las tapas y lados.

\6. Tubo: radio 1, radio2, altura, segmentos de altura,
segmentos de las tapas y lados.

UNAM ‐ DGSCA / Victor Hugo Franco Serrano 13

<!-- p. 14 -->

Modelación Curso 3D Studio Max

2.2 Modelado usando polígonos

a.- Uso de elementos bidimensionales
Dentro de 3d studio max es posible emplear elementos bidimensionales para construir objetos
3d, como pueden ser puntos, líneas, formas básicas y texto, por ende es importante su
aprendizaje antes de pasar de lleno al modelado tridimensional.

Ejercicio: Aprendizaje del manejo de splines

Dentro de este ejercicio se deberá aprender a modificar splines por
medio del punto, la línea y el segmento que 3d max permite editar,
además de conocer algunas de las posibilidades de conversión de las
líneas y geometrías.

En la imagen podemos apreciar los tres niveles de edición de los
splines, en ellos es posible decidir entre la edición por puntos,
segmentos y líneas, en la parte inferior es posible encontrar los iconos
que representan a cada uno de estos, al dar clic en alguno de ellos es
posible entrar en su respectivo modo de edición.

Una vez seleccionado el modo de edición es posible editar en las vistas
a los splines.

Cuando empleamos splines prefabricadas como
el círculo, el rectángulo, la elipse, el arco, entre
otros, estamos usando splines paramétricos y
por ende no es posible su edición por medio de
puntos, líneas y splines, para ello se debe
convertir al spline en spline editable.

Para llevar esto a cabo debemos dar clic
derecho sobre el nombre círculo o en las vistas
sobre el círculo, en el menú emergente
debemos seleccionar la opción Editable Spline
para que la spline paramétrica sea convertida
en una spline con la que puedan editarse por
línea, punto o segmento.

UNAM ‐ DGSCA / Victor Hugo Franco Serrano 14

<!-- p. 15 -->

Modelación Curso 3D Studio Max

b.- Operaciones bidimensionales básicas

3D Studio Max permite realizar varias operaciones entre puntos, líneas y segmentos que
facilitaran la integración, extracción y adición de puntos, para ello los splines editables usan
operaciones como Attach, Weld, booleanos, espejo, corte, entre otras, que son accesibles
según el subnivel de selección en el que nos encontremos.

En la tabla podemos ver algunas de las relaciones de posibilidades de uso de operaciones
básicas según la selección de los tres niveles de edición, como vértice, segmento o línea.

Vertex Segment Spline
Attach * * *
Attach Multi * * *
Cross Section * * *
Weld *
Connect *
Fillet *
Chamfer *
Outline *
Booleano *
Trim *
Refine * *
Mirror *
Fuse *
Create line * * *

El significado de cada operación es:

Attach Esta operación permite hacer un solo objeto a diversos objetos, es aplicable
a splines, pero también es aplicable a geometrías tridimensionales.

Attach Multi Permite la integración en un solo objeto desde varias fuentes que pueden ser
seleccionadas de un lista de los objetos de la escena.

Cross Section Permite generar una sección cruzada que une a dos splines, esto lo realiza a
través de los puntos de interpolación más cercanos.

Weld Permite unir puntos, su traducción literal al español es soldar, por lo que de
esta forma suelda en uno solo los puntos de los splines e inclusive es
aplicable a geometrías tridimensionales.

Connect Solo conecta dos puntos, pero, a diferencia de soldar no elimina alguno de
ellos, más bien mantiene ambos pero unidos.

Fillet Genera una curvatura en los ángulos de los objetos, lo logra adicionando un
nuevo punto en las esquinas de los objetos y desplazando ambos puntos a
través de los lados del objeto, la interpolación entre estos puntos genera una
curvatura que se conoce como fillet.

Chamfer Es una operación en la cual se unen dos superficies a través de ejes
biselados, al igual que connect lo realiza al adicionar un punto al ángulo de
las superficies y trasladar a ambos sobre los lados del spline, esta operación

UNAM ‐ DGSCA / Victor Hugo Franco Serrano 15

<!-- p. 16 -->

Modelación Curso 3D Studio Max

a diferencia del fillet no produce un curvatura sino más bien un ángulo de 45
grados, en español es conocido como chaflán.

Outline Genera una copia interior del spline, si se usa más de una vez genera copias
concéntricas del spline.

Booleano Son una serie de operaciones que comparan dos splines (e inclusive dos
geometrías tridimensionales) para obtener un tercer resultado, las más
comunes son conectar, sustraer e intersectar. Cada operación requiere de
dos splines, geometrías o elementos de iguales condiciones.

Trim Permite la eliminación de segmentos de los splines, es útil cuando es
necesaria la eliminación de splines sobrantes.

Refine Permite agregar más puntos a un spline, esta opción es útil al dividir
segmentos.

Mirror Permite el espejeo de la posición de los splines de manera vertical,
horizontal o de ambas.

Fuse Con esta operación es posible colocar los vértices seleccionados en la misma posición en X,
Y y Z, por lo que todos los vértices se colocan en el mismo lugar.

Create line Esta operación permite crear una linea extra dentro del mismo spline.

Ejercicio: Manejo de operaciones con splines

Realización de un
ejercicio donde se
ejemplifican las
diferentes
operaciones de
edición de splines
que permite 3d
studio max.

UNAM ‐ DGSCA / Victor Hugo Franco Serrano 16

<!-- p. 17 -->

Modelación Curso 3D Studio Max

c.- Modelado poligonal básico

Conversión de primitivas y splines a polígonos.

Para convertir de primitivas básicas y splines a polígono debemos
dar clic derecho sobre el objeto a convertir y elegir en que se va a
convertir, las dos posibilidades más usuales son Editable Poly y
Editable Mesh, aunque existen otras dos opciones, NURBS y
PATCH, pero por lo general no se emplean en tiempo real pues
producen demasiados polígonos.

En la imagen lateral izquierda se muestra la ventana emergente al
dar clic derecho sobre la primitiva o spline a convertir, en su parte
inferior se encuentra el menú desplegable Convert To, dentro de
la cual se encuentran las diferentes opciones de conversión a
polígonos y otras superficies.

La imagen inferior muestra de su lado izquierdo una
primitiva básica de una esfera y un spline de círculo, del
lado derecho se encuentran dos geometrías convertidas en
polígonos tipo Editable Poly.

Ejercicio: Comprobación del aprendizaje de modelado poligonal.

En esta práctica se deberá aprender el uso de los modelos poligonales tipo editable poly y editable mesh,
además de algunas de sus opciones y sus similitudes con la edición de geometrías 2d.

d.- Diferencias y uso de poly y de mesh

Dentro de la siguiente tabla comparativa entre Editable Mesh y Editable Poly es posible
identificar las capacidades de uno y otro, en lo general son muy similares, pero existen
opciones bastante útiles en el editable Poly.

UNAM ‐ DGSCA / Victor Hugo Franco Serrano 17

<!-- p. 18 -->

Modelación Curso 3D Studio Max

Editable Mesh Editable Poly
Permite la edición por * *
subobjetos
Id de Material * *
Conserva las coordenadas *
UV
Paint Deformation *
Edit Triangulation *
Extrude * *
Bevel * *
Attach / Detach * *
Slice / Cut * *
Weld * *
Tesselation * *
Flip * *
Auto smooth * *
Edición de la triangulación *

2.3 Modelado usando modificadores

Además de los volúmenes básicos existen otros dos procesos que comúnmente se utilizan para crear
geometrías elementales.

2.3.1 Extrusión

Consiste en dibujar una figura en dos dimensiones y después
asignarle propiedades de altura, formando un prisma cuya
sección sea la figura inicial.

En este caso se comienza dibujando una figura de dos
dimensiones para lo cual se selecciona en el panel de comandos:
“Create/Shapes/Line”, y se comienza a dibujar con el cursor del
ratón, preferentemente en la vista Top. Por cada clic del ratón
aparece un nuevo vértice, y cada uno de estos vértices puede ser
editado posteriormente. Es importante que el último clic se dé
sobre el punto inicial para cerrar la figura, pues sólo se pueden
extruir figuras cerradas.

Por último, se va a extruir esta figura con cierta altura,
seleccionando en el panel de comandos:

“Modify/Modifier list/ Extrude”. Extrude presenta dentro de sus
parámetros “Amount” que originalmente tiene una cifra 0.0, si se
aumenta la dimensión de este parámetro aumentará la altura de
la figura construyendo un nuevo prisma.

UNAM ‐ DGSCA / Victor Hugo Franco Serrano 18

<!-- p. 19 -->

Modelación Curso 3D Studio Max

2.3.2 Lathe

Consiste en dibujar una silueta o figura que al
ser girada sobre un eje forme un objeto, como
una botella o un jarrón. Al igual que en la
extrusión, se comienza a dibujar la silueta en
la vista “Top”con el comando
“Create/Shapes/Line”.

Una vez terminada se procede a aplicar el
comando “Modify/ Modifier list/Lathe”, la figura
se revoluciona automáticamente sobre su eje
central, pero la mayoría de las veces se busca
que se revolucione sobre un eje interno.

Para cambiar esto “Lathe” tiene los parametros de “Align” en el área de comandos desplegables que
ofrece tres opciones: Min, Center y Max. Si se quiere revolucionar sobre el eje interno hay que
seleccionar Min, pero la primera vez es bueno probar las tres opciones.

2.4 Modelado por objetos compuestos

Los objetos compuestos emplean dos o más objetos para realizar
operaciones de diversas índoles, así por ejemplo el compound object
terrain emplea líneas para generar terrenos, Boolean emplea
operaciones booleanicas de adición sustracción e intersección.

Estos objetos son bastante útiles al modelar, aunque tienden a generar
demasiados polígonos, lo recomendable es usarlos cuando sea
necesario o cuando realmente reduzca la carga de trabajo
considerablemente sin afectar el rendimiento del sistema.

UNAM ‐ DGSCA / Victor Hugo Franco Serrano 19

<!-- p. 20 -->

Modelación Curso 3D Studio Max

2.4.1 Loft

Este objeto compuesto emplea dos líneas
splines para poder generarse, se
selecciona una de ellas y luego se
selecciona Loft dentro de compound
objects.

Dentro de las opciones de Creation
Method está la de seleccionar por path o
seleccionar por Shape, según el objeto
que hayamos seleccionado al principio,
esta opción se selecciona a la inversa.

Por ejemplo si seleccionamos la directriz
ósea el Path debemos selecciona la
generatriz ósea el Shape.

Generatriz y directriz Objeto tipo loft

En la imagen podemos observar a la generatriz y Una vez seleccionado y creado el objeto loft se
la directriz, en donde la generatriz es el círculo y la puede visualizar en pantalla como polígonos.
directriz la línea curva. Loft es conocido en español como seguimiento.

UNAM ‐ DGSCA / Victor Hugo Franco Serrano 20

<!-- p. 21 -->

Modelación Curso 3D Studio Max

2.4.2 Booleanos

Otras herramientas básicas con que se cuenta para la
construcción de objetos 3D son las llamadas operaciones
Booleanas que consisten en sumar, restar o intersectar
las superficies de dos objetos tridimensionales.

Primero se deben construir dos objetos (como se explicó
en el punto 2.1), asegurándose de que los volúmenes de
los dos objetos se intersecten y que uno de los dos esté
seleccionado.

Después se selecciona en el panel de Comandos la opción “create”
pero en lugar de utilizar la etiqueta “Standard Primitives” se despliega
el menú, con la flecha que se encuentra a la derecha de dicho letrero,
y se escoge la opción “Compound Objects”.

Ahora se presenta otro panel llamado “Object Type” donde se
selecciona la opción “Boolean”.

Nota: Los compound objects emplean dos o más objetos para aplicar
operaciones diversas.

Es en este panel “Boolean” donde se aplican las operaciones booleanas, de la
manera siguiente:

a) Primero hay que elegir “move” debajo del comando “Pick Boolean”.

a) Después se selecciona la operación que se desee aplicar en el comando
“Parameters” ya sea union, intersection, substraction A-B o substraction B-A.

a) Por último se oprime “Pick operand B” en el comando “Pick Boolean” y se
procede a seleccionar, en una de las vistas, el objeto que no había sido
seleccionado en un principio.

UNAM ‐ DGSCA / Victor Hugo Franco Serrano 21

<!-- p. 22 -->

Modelación Curso 3D Studio Max

Unión Intersección Sustracción

Cada operación tiene un resultado diferente y conviene probarlos todos, como recomendación, no se
debe abusar de los booleanos ya que crean superficies irregulares de más de 3 o 4 puntos por cara lo
que no es recomendable para tiempo real.

Ejercicio: Comprobación del aprendizaje de modelado por modificadores y objetos compuestos

Hacer una figura extruida y una en lathe, además de dos ejemplos de objetos compuestos, incluyendo
booleanos y loft.

\3. EDICIÓN DE OBJETOS 3D

Los objetos tridimensionales pueden ser editados a través de las herramientas de selección y la
selección por subnivel, también es posible editarlos en relación a su posición, rotación y escala,

3.1 Tipos de Selección

En la imagen podemos observar los filtros de selección, estos nos
permiten discernir entre que elementos necesito seleccionar y bloquea la
posibilidad de selección de los demás elementos, se usa en conjunto con
la Selección por objeto.

Cuando se están editando objetos 3D normalmente son seleccionados antes de
hacerles cualquier cambio. Estos cambios pueden ser aplicados también a un
grupo de objetos o sus componentes, y muchas veces el éxito de lograr el efecto
en el modelo deseado depende de hacer bien la selección de objetos editados.
Por eso 3D Max cuenta con una variedad de tipos de selección, por lo que a
continuación sólo se muestran los más comunes:

\1. Selección por objeto (object): permite seleccionar uno o más objetos, siempre y cuando
la selección se haga considerando un objeto a la vez. Primero se elige el primer objeto y
después se aprieta la tecla “Control” y sin soltarla se van seleccionando los demás objetos
deseados.

UNAM ‐ DGSCA / Victor Hugo Franco Serrano 22

<!-- p. 23 -->

Modelación Curso 3D Studio Max

En la imagen se puede apreciar los
diferentes modos de selección, se
encuentran dentro del menú Edit, al dar
clic en selected by aparece una ventana
flotante que contiene modos adicionales
de selección, de igual forma al dar clic en
región es posible desplegar la ventana
emergente con opciones de selección
window y crossing.

\2. Selección por ventana (window): esta
herramienta se encuentra habilitada por
defecto. Si se abre una ventana en una de las
vistas, todos los objetos que estén total o
parcialmente dentro de la ventana quedarán
seleccionados.

Esta herramienta tiene más opciones que se pueden escoger en el ícono
representado por un cuadro de línea punteada en el área de controles de
selección. Al oprimir este botón presenta las opciones de “selección por área
circular” y “selección por área cercada” donde se va demarcando punto por punto
un área circundada por una línea quebrada que abarca todos los objetos a
seleccionar.

\3. Selección por nombre (By name): permite seleccionar
cualquiera de los objetos que se encuentren activos en la
escena, escogiéndolos en un listado que se presenta al
presionar el botón correspondiente que se encuentra en el área
de controles de selección y está representado por una flecha
que apunta a una lista.

\4. Selección por color (By color): selecciona todos los
objetos que tengan el mismo color del objeto seleccionado
inicialmente, a esta opción se puede entrar desde el menú
desplegable “Edit” o a través de la “Ventana de diálogo de color
de objetos” descrita en el capítulo 2.

UNAM ‐ DGSCA / Victor Hugo Franco Serrano 23

<!-- p. 24 -->

Modelación Curso 3D Studio Max

\5. Seleccionar todo (All): selecciona en un solo paso todos los
objetos de la escena, esta opción se escoge en el menú “Edit”.

\6. Seleccionar ninguno (None): el proceso inverso a seleccionar
todo, el objetivo es dejar de seleccionar cualquier objeto u elemento
que se encuentre seleccionado en la escena. Esta selección
también se encuentra en el menú “Edit” y es recomendable usarla
antes de hacer una nueva selección.

\7. Selección Invertida (Invert): selecciona todos aquellos objetos
que no se encuentren seleccionados en la escena en ese momento
y obviamente deja de seleccionar los que sí lo estén.

\8. Selecciones nombradas (Named Selection Sets): como las selecciones son
tan importantes para los modificadores y las transformaciones, 3D Max permite
salvar cada selección con un nombre, y es en esta lista donde se puede acceder
de manera rápida a cualquiera de las selecciones nombradas previamente. Esta
opción se maneja en el área de control de selecciones.

Para hacer uso de selection sets debemos dar click en Edit
Named Selection Sets dentro del menú Edit, posteriormente en
la ventana emergente se crean los selection sets al dar clic en
el primer icono.

Luego seleccionamos la lista de selección y dentro de ella
seleccionamos al objeto que deseemos agregar, ya
seleccionado damos clic en el icono que tiene un más.

Con esto habremos creado un selection set, es posible definir
más de un selection set para una escena y no importa si los
objetos se repiten en cada selection set.

\9. Selección por región (by Region): consiste en marcar cierta área, ya sea generando un
rectángulo o una circunferencia, o dibujando un perímetro cualquiera a partir de líneas rectas
alrededor de un área determinada.

Además, la selección por región ofrece otras dos opciones de trabajo, la selección por Ventana
(Window), donde todo objeto que se encuentre totalmente rodeado por el perímetro marcado
quedará seleccionado. Y la selección por Cruce (Crossing), donde basta con que alguno de los
segmentos que forman el perímetro marcado, pase por encima de alguno de los segmentos
que forman un objeto, para que dicho objeto quede seleccionado.

UNAM ‐ DGSCA / Victor Hugo Franco Serrano 24

<!-- p. 25 -->

Modelación Curso 3D Studio Max

Es posible emplear el modo de selección por lista,
este modo de selección permite al usuario discernir
entre que objeto va a ser seleccionado, es posible
decidir entre 9 posibilidades de selección, entre
ellas se encuentran las geometrías, cámaras y
luces.

Para activar o desactivar el nivel que se desee se
debe dar clic en los botones de radio que se
encuentran del lado derecho, también es posible
seleccionar todos los botones de radio al dar clic en
el botón all y de manera inversa con el botón none
es posible deseleccionar todo.

Si se tiene seleccionado algún objeto de la lista
pero se desea seleccionar lo que no esta
seleccionado puede dar invert, que como su
nombre lo indica invierte la selección.

3.2 Selección de subniveles

Es posible editar subniveles de objetos tipo editable poly y editable mesh, en la
imagen lateral izquierda se muestran los iconos de selección de subnivel, para
seleccionar puntos seleccionamos el primer icono, en la imagen se encuentra
seleccionado el icono de eje, el que le sigue es el de borde, el cuarto es el de
polígono y el ultimo es el de elemento. Las imágenes superior e inferior
muestran dos modos de selección, por polígono y por eje.

Ejercicio: Comprobación del aprendizaje de selección de objetos 3d y sub-niveles

En esta práctica se deberán colocar varios objetos, primitivos y poligonales, en la escena para que
posteriormente se practique con los modos de selección directa, por medio de la lista de selección, por el
menú edit, se deberán crear selection sets de los objetos y lograr usarlos correctamente.

Como punto adicional, pero no menos importante, se deberá practicar el modo de selección de sub
niveles geométricos, punto, eje, borde, polígono y elemento.

UNAM ‐ DGSCA / Victor Hugo Franco Serrano 25

<!-- p. 26 -->

Modelación Curso 3D Studio Max

3.3 Edición por transformación

3D Studio Max tiene dos maneras básicas de editar objetos además de los propios parámetros
que pueden modificarse durante su creación: las transformaciones y los modificadores.

Una transformación es cualquier operación para cambiar las características de tamaño,
rotación o posición de un objeto, que prácticamente lo transforma. La manera más fácil de
aplicar la transformaciones es utilizando el botón de selección de objetos que se encuentra en
la sección de control de selecciones y cuyo ícono está representado por una flecha simple.

Una vez seleccionado un objeto se da un clic en el botón derecho del ratón para que aparezca
el menú de Transformación de objetos (Object Transform Menu), donde se pueden escoger las
siguientes transformaciones:

3.3.1 Mover

Simplemente desplaza el o los objetos seleccionados de un punto en el
espacio a otro.

3.3.2 Rotar

Gira los objetos seleccionados sobre cualquiera de los ejes cartesianos X, Y o
Z.

3.3.3 Escalar

Modifica las dimensiones de los objetos seleccionados ya sea aumentándolas
o disminuyéndolas.

Al dar click derecho sobre los iconos aparece la
opción “Transform”, que ayuda a restringir el plano o
eje de acción de cualquiera de las transformaciones y
colocar numéricamente los valores de transformación.

UNAM ‐ DGSCA / Victor Hugo Franco Serrano 26

<!-- p. 27 -->

Modelación Curso 3D Studio Max

3.4 Edición por modificadores

Un modificador es un método para cambiar la estructura interna
de la geometría de un objeto.

Torcer un cilindro, es un ejemplo de aplicación de un modificador
donde los vértices de un extremo del cilindro son rotados con
respecto a los del otro, produciendo un efecto de torcedura en el
objeto, es decir, en este caso la geometría original es modificada.

Cada vez que un modificador es aplicado a un objeto, este
cambio es archivado en la “Lista de Modificadores de Aplicados”
(Modifier List). Así que el usuario puede regresar en cualquier
momento a hacer cambios que vuelven a afectar la estructura del
objeto en el modificador.

Para acceder a cualquiera de los modificadores que se encuentran
en la etiqueta “Modify” del panel de comandos, primero se debe
seleccionar el objeto al cual se le quiere aplicar el modificador.
Después de seleccionado el objeto, todos los modificadores
presentes en el panel que puedan modificar a ese objeto
aparecerán en texto negro y aquéllos que no puedan afectar al
objeto seleccionado simplemente no aparecerán pues no sirven en
dicho caso.

La estructura de un modificador contiene al objeto, al envolvente y
al gizmo, este ultimo puede ser editado para cambiar la posición en
la cual se realiza la modificación a la geometría original.

Cada modificador posee una serie de parámetros que al ser
modificados cambian los valores e intensidad en pantalla de la
modificación de la geometría.

Permiten además definir sobre que eje se ejercerá la modificación
al objeto y define límites.

UNAM ‐ DGSCA / Victor Hugo Franco Serrano 27

<!-- p. 28 -->

Modelación Curso 3D Studio Max

Existen muchos modificadores, pero aquí sólo se enlistarán los más representativos:

3.4.1 Twist 3.4.2 Bend 3.4.3 Taper

Se utiliza para torcer un objeto Sirve para doblar el objeto Disminuye las dimensiones en
alrededor de cualquier eje. seleccionado alrededor de cierto uno de los extremos del objeto
eje. seleccionado.

3.4.4 Noise 3.4.5 Lathe

UNAM ‐ DGSCA / Victor Hugo Franco Serrano 28

<!-- p. 29 -->

Modelación Curso 3D Studio Max

Aplica variaciones aleatorias a la Se utiliza para generar superficies de revolución a partir de un
geometría para producir objetos perímetro cerrado marcado por un par de líneas paralelas que
con apariencia orgánica. guardan una distancia mínima entre ellas.

Así, a partir de una silueta elaborada en 2D, se pueden desarrollar
objetos que en la vida real se fabrican a partir de un torno.

Ejercicio: Comprobación del aprendizaje de edición de objetos 3d

En esta práctica se deberá editar con transformaciones y modificadores varias primitivas y primitivas
convertidas a polígono.

3.5 Clonación, alineación, arreglo y reflejo

Existen diferentes posibilidades de edición dentro de 3d studio max, una vez generadas las geometrías
es posible aplicarles diversas herramientas para su uso dentro de los entornos virtuales, la más común
es la clonación de objetos, aunque el reflejo es ampliamente usado al momento de modelar objetos
simétricos, pues con su uso se facilita de sobremanera el trabajo de duplicar en un eje axial la geometría
de un objeto.

Clonación El proceso de clonación se puede realizar de dos
maneras, la primera de ellas es dando clic derecho
sobre los objetos y elegir la opción clonar, al hacer
esto saldrá un dialogo que preguntará de que manera
queremos realizar la clonación, si se selecciona como
copia el objeto copiado conservara las propiedades
geométricas y de material del original, pero será un
objeto nuevo no vinculado

Por el contrario al seleccionar la opción instance lo
que habremos clonado conserva de igual forma las
propiedades geométricas y de materiales del objeto
pero en esta ocasión se encuentran vinculados, el
cambio realizado en uno será copiado en el otro.

También es posible acceder a esta clonación en el
menú edit clone o con el comando de teclas
Control + V.

Aunque la manera más común de uso de la clonación
es la de seleccionar el objeto, dar clic en mover, antes
de mover el objeto se debe oprimir sin soltar la tecla
shift, luego se arrastra el objeto y se suelta, esta
acción permitirá clonar al objeto al preguntarnos de
que forma será copiada la información.

UNAM ‐ DGSCA / Victor Hugo Franco Serrano 29

<!-- p. 30 -->

Modelación Curso 3D Studio Max

Arreglo

Es una disposición ordenada de objetos, que al igual que la clonación, permite la copia de
información geométrica y de materiales, pero agrega la posibilidad de modificación de la
rotación, la escala y la traslación de los objetos copiados.

Para acceder a la clonación de objetos por arreglo se puede dar clic en tools y buscar array,
o buscar el icono de array en la barra flotante de extras.

Nota adicional de uso: Para poder ver las
barras flotantes debemos dar clic en
customize, luego en Show UI, dentro de
esta opción se encuentra Show Floating
Toolbars, al dar clic aparecerán las
barras flotantes

UNAM ‐ DGSCA / Victor Hugo Franco Serrano 30

<!-- p. 31 -->

Modelación Curso 3D Studio Max

La imagen muestra la ventana flotante de Array, en ella podemos observar en un primer segmento
superior las diferentes transformaciones que posibilita Array, en cada una da las tres columnas de
valores de punto flotante de X, Y y Z se asigna un numero que en traslación es en unidades, en rotación
en ángulos y en escala en porcentaje, estas variaciones serán aplicadas al total de objetos que
definamos en la clonación.

El segmento de Type of Object nos brinda la oportunidad de decidir, al igual que con la clonación simple,
si los objetos copiados serán copia, instancia o referencia, a lado derecho de este segmento se
encuentra Array Dimensions, dentro de esta área es donde decidiremos el numero de copias, cuando
usamos una sola dimensión ósea en 1D es posible asignar un valor entero que representa al numero
total de objetos clonados incluyendo al original.

Al usar 2D y 3D usamos respectivamente dos y tres dimensiones, esto es útil al momento de copiar
elementos a través de un espacio tridimensional sobre XYZ.

Una de las opciones más útiles de esta ventana es la que posibilita
previsualizar en tiempo real dentro de los viewports lo que sucederá al
aplicarse el Array, por ende es muy importante tener activada la opción
Preview al momento de trabajar, un inconveniente surge al clonar de esta
forma objetos muy pesados, por ello preview esta por default desactivado

.

UNAM ‐ DGSCA / Victor Hugo Franco Serrano 31

<!-- p. 32 -->

Modelación Curso 3D Studio Max

Reflejo
Icono de reflejo

El reflejo dentro de max posibilita la
copia de elementos geometricos
sobre un eje axial, esta copia facilita
el trabajo de modelado pues si por
ejemplo se modela un objeto simetrico
es posible modelar solamente la mitad
de él y luego con la herramienta
mirror reflejarla para completar la
forma general.

Para realizar esta operación se debe
seleccionar el objeto a reflejar y dar
click en el icono mirror, al aparecer la
ventana emergente con las opciones
de eje de espejo y tipo de copia se
seleccionan sus valores y se da ok,
Ventana emrgente de Mirror En la imagen podemos offset permite definir una separación
en donde defines valores de observar un objeto reflejado que entre el objeto original y el reflejado.
reflejo y separación. en su conjunto crea un cilindro.

Spacing Tool

La herramienta spacing tool permite clonar
objetos a travez de una curva, para definir el
camino de clonación se debe seleccionar el
objeto a clonar y luego en el menu tools la
opción Spacing Tool… esta abre una ventana
emergente que permite seleccionar el path por
el cual se deplazara el objeto, se da clic en la
línea y con esto se podra generar la clonación
de los objetos en el espacio.

En la imagen
podemos
observar el
resultado de
la clonación
de objetos al
seguir una
curva que
permite la
herramienta
spacing tool.

UNAM ‐ DGSCA / Victor Hugo Franco Serrano 32

<!-- p. 33 -->

Modelación Curso 3D Studio Max

Alineación

La alineación a diferencia de las herramientas de
clonación, no produce copias, su función es la de
alinear a los objetos de la escena en uno o más ejes,
para llevar a cabo esta operación se debe seleccionar
de primera mano el objeto que se quiera alinear.

Luego dar click en el icono de alineación y luego dar
click en el objeto del que se tomaran los valores de
alineación, esta operación siempre se realiza con dos
objetos.Es posible decidir la posición relativa de la
transformación, las opciones que da son minimo que
significa la parte mas baja del objeto, center que es el
centro del objeto, e Punto Pivote que es el centro de
rotación de los objetos y el maximo que es la parte
más alta, profunda o extensa del objeto, esto claro
según el eje en el que se trabaje.
En la imagen izquierda podemos observar
las diferentes variedades de alineación, También brinda la posibilidad de uso de más de un eje,
por orden descendenteson align, quck lo que se debe hacer es marcar la cantidad de ejes align, normal align, place highlight, align
necesarios de X,Y o Z, con el uso de esta herramienta camera y por ultimo align to view.
podemos garantizar por ejemplo que todos los objetos
se encuentren sobre un plano sin atravezarlo, o que La imagen superior presenta los valores
los objetos se toquen exactamente en donde les de alineación usables dentro de 3d max.
decimos que deben tocarse.

Ejercicio: Aprendizaje de edición de objetos por medio de Transformaciones Básicas
Modificadores, Alineación y Clonación

El objetivo de este ejercicio es el de aprender el uso de las opciones que max brinda en la edición de
objetos tridimensionales y posibles aplicaciones.

UNAM ‐ DGSCA / Victor Hugo Franco Serrano 33

<!-- p. 34 -->

Modelación Curso 3D Studio Max

\4. EDITOR DE MATERIALES

Una de las partes más importantes en la creación de una escena, es asignar los
materiales requeridos a los objetos modelados.

3D Studio Max cuenta con el modulo de materiales que permite crear y asignar
materiales a objetos 3D, con el objetivo de emular materiales del mundo real como
mármol, vidrio, madera, metal y plástico, de esta manera se alcanza un grado de
fotorealismo en una escena tridimensional.

Un material es definido como una serie de parámetros que combinan la manera en
que se proyectará la luz, los reflejos o el sombreado en los objetos 3d que tengan
asignado el material.

Los materiales se pueden asignar a un objeto 3d o a un conjunto de objetos
seleccionados, inclusive se pueden asignar a los sub-objetos que los componen
como: vértices, caras o polígonos.

Se pueden encontrar tipos de materiales básicos y compuestos:

Material estándar y compuesto

Las propiedades de los materiales básicos permiten definir características
de superficie como el color, brillo y nivel de transparencia, con estos
controles podemos generar materiales realistas de un solo color (plástico,
vidrio, barro, etc.).

Pero también se pueden usar mapas para mejorar el realismo de los
materiales, estos mapas me permitirán definir propiedades de superficie
como textura, relieve, opacidad y reflexión.

Básicos: estándar, Raytrace, Mate/Sombra, material de sustitución de
iluminación avanzada, el material carcasa, material de Lighscape y el
material Ink´n Paint.

Los materiales compuestos o complejos, pueden combinar dos o más
submateriales de diversas formas y cada submeterial puede ser tan
complejo como un material estándar.

Compuestos: mezcla, compuesto, dos lados, Morfista, Multi/subobjeto,
Shellac y Superior/Inferior.

UNAM ‐ DGSCA / Victor Hugo Franco Serrano 34

<!-- p. 35 -->

Modelación Curso 3D Studio Max

4.1 Módulo de materiales

El módulo de materiales está formado por una excelente interfaz que permite crear y editar materiales y
mapas.

Para acceder a este módulo se da un clic en el ícono de edición de materiales en la barra de
herramientas o eligiendo el menú Rendering - Material Editor o presionando la tecla “M.”

Una vez elegida cualquiera de estas opciones
aparece la interfaz del Módulo de materiales.

El módulo de materiales ofrece funciones para crear
y editar materiales y mapas.

El Módulo de Materiales es un módulo dividido en
tres áreas: ventana de muestra, control del editor de
materiales y el área de parametros desplegables y
mapas.

El área de muestra brinda información de los
materiales y cómo lucirá el material cuando esté sea
asignado y renderizado en la escena (aunque el
resultado verdadero lo veremos cuando se
renderice). Dicha área de muestra está compuesta
por seis ventanas, la ventana activa tiene un borde
blanco alrededor, cuando un material es asignado en
la escena, cuatro triángulos blancos aparecen en la
ventana de muestra activa.

Estos triángulos indican que este
material es ahora caliente. Un
material caliente es un material
asignado en la escena, en otras
palabras cuando se modifica
cualquier parámetro de un material
caliente, estos cambios son
reflejados automáticamente en el
objeto, es decir no se tiene que
reasignar.

UNAM ‐ DGSCA / Victor Hugo Franco Serrano 35

<!-- p. 36 -->

Modelación Curso 3D Studio Max

4.2 Materiales estándar

Los materiales estándar usan mapas y no se combinan con otros materiales. Estos materiales son
usados para crear materiales del mundo real como pintura, plástico, metal y vidrio y permiten definir
valores de color, transparencia y reflexión.

Existen dos secciones en el Editor de materiales para editar los parámetros de control de los materiales
estándar: la barra de despliegue de los parámetros básicos y parámetros de extensión.

A la izquierda barra de despliegue de los
parámetros básicos: cuando se abre el
Módulo de materiales, la barra de
despliegue de los parámetros básicos se
abre automáticamente.

A la derecha, parámetros de extensión
afectan dos aspectos del material:
opacidad (transparencia) y la malla de
alambre (wireframe).

\- Parámetros Básicos

Un material estándar está compuesto por la combinación de varios parámetros básicos, cada uno de
estos está descrito a continuación:

\1. Shading: define el método que el programa utilizará para representar el comportamiento de la luz
sobre la superficie de un objeto.

\2. two – sided: precisa el modo de doble lado para las caras del objeto.

\3. Wire: esta opción forza el programa al renderizar el material en una malla de alambre.

\4. Face map: esta opción forza el programa al renderizar el material en cada una de las
caras del objeto.

\5. Ambient: define el color 7. Specular: esta opción
del material cuando está define el color del material
sombreado. El color definido en las zonas que están más
es el que se refleja en el iluminadas.
material cuando es
iluminado por luz de 8. Glosiness: esta opción
ambiente en lugar de la luz define la longitud del brillo
directa. en el material.

\6. Diffuse: determina el 9. Curva de espe_
color global del material. cularidad: muestra la curva
de valores especulares.

\10. Specular Level: determina la intensidad del brillo en el material.

UNAM ‐ DGSCA / Victor Hugo Franco Serrano 36

<!-- p. 37 -->

Modelación Curso 3D Studio Max

\11. Self-Illumination: brinda autoiluminación al material.

\12. Opacity: define el grado de transparencia del material.

\13. Soften: suaviza la intensidad del grado de brillantez en el material.

\- Parámetros de extensión:

Combinados con los parámetros básicos definirán el aspecto de los materiales estándar. Se puede
acceder a los parámetros de extensión dando un clic en la barra de Despliegue de parámetros
extendidos.

Los parámetros de extensión afectan dos aspectos del material: opacidad (transparencia) y la malla de
alambre (wireframe).

Debajo de las opciones de opacidad están tres opciones: Folloff, Type y Refraction IOR.

Los controles de Folloft definen cómo será aplicada la transparencia, se pueden elegir dos maneras, In y
Out.

Cuando el Folloft es definido con la opción In, la
transparencia decrece a partir del centro del
material. Por ejemplo: el vidrio.

Cuando el Folloft es definido con la opción Out, la
transparencia del material decrece a partir de los
bordes del material. Por ejemplo: las nubes, humo
y niebla.

La opción de Amount determina el grado de transparencia para cualquiera de las opciones.

Se puede elegir el color de la transparencia del material de tres maneras, escogiendo una de las tres
opciones que aparecen debajo de la opción Type. Como el material es transparente, los colores de los
objetos que se encuentran debajo se observan, afectando éstos el color del material transparente.

Al activar la opción Filter, se usan los colores definidos en los parámetros básicos.

La opción Subtractive substrae los filtros de color que se encuentran debajo del material transparente.

La opción Additive suma los filtros de color que se encuentran debajo del material transparente.

La opción Index of Refraction define el grado de refracción del material.

En los parámetros de la malla de alambre (Wireframe) se determina el tamaño y el grosor de los
alambres de la malla, estos valores se pueden definir en pixeles o unidades.

UNAM ‐ DGSCA / Victor Hugo Franco Serrano 37

<!-- p. 38 -->

Modelación Curso 3D Studio Max

4.3 Asignación de mapas

A los materiales estándar se les pueden asignar mapas
para generar materiales más reales como, cromo, oro,
metales, mármol, madera, ladrillos, etc.

Un material estándar utiliza bitmaps para aplicar infinidad
de efectos.

El bitmap es usualmente una fotografía de algún material
del mundo real, este bitmap es definido en la superficie
del material de diferentes maneras, dependiendo de la
geometría del objeto y del efecto deseado.

Por ejemplo, la imagen de un edificio para un entorno
arquitectónico.

Para acceder a los controles de los materiales
envolventes se da un clic en la barra de
despliegue Maps que se encuentra en el Módulo
de edición de materiales.

Para aplicar un bitmap a un material se da un
clic en el botón None en el nivel de Maps que se
desea trabajar.

UNAM ‐ DGSCA / Victor Hugo Franco Serrano 38

<!-- p. 39 -->

Modelación Curso 3D Studio Max

Cuando se elige algún nivel aparece una nueva ventana llamada
Material/Map Browser, en esta ventana se pueden elegir más de 26
diferentes tipos de bitmaps para su uso en los materiales envolventes.

Esta opción se elige dando un doble clic, despues de esto, regresa la
ventana de Edición de materiales pero con una serie de controles
nuevos que servirán para cargar y definir los valores del bitmap que se
utilizará en el material.

Nota adicional: es posible visualizar los materiales que se están
utilizando en la escena al dar clic sobre el botón de radio de Scene, de
igual forma es posible cargar librarías de materiales al dar clic en el
botón de radio Mtl Library.

Después de escoger el bitmap que será aplicado en el material, el Editor de materiales muestra cinco
barras de despliegue que se utilizarán para definir el bitmap en el material.

Estos controladores son: Coordinates, Noise, Bitmap Parameters, Output y Time.

\1. Barra de despliegue Coordinates (coordendas): esta opción se aplica para controlar la manera en
que el bitmap será aplicado a las coordenadas de mapeo.

Existen dos formas de aplicar las coordenadas de
mapeo: Texture y Environment.

Las coordenadas de Textura son aplicadas a todo tipo
de materiales y las coordenadas de Environment son
aplicadas solamente para crear efectos de ambiente.

La opción Offset define la posición horizontal y vertical
del bitmap en el material.

La opción Tiling define el número de veces que aparecerá el bitmap en el material e inclusive estas
opciones se pueden desactivar.

La opción Mirror invierte las coordenadas y el bitmap.

En el lado derecho de la barra de Despligue se pueden controlar el ángulo de rotación del bitmap y los
valores de Blur (nublado o borroso).

Las coordenadas de mapeo son aplicadas normalmente con la opción UV pero existen otros tipos de
mapeo para objetos como cubos o cilindros donde es mejor utilizar las coordenadas UVW.

UNAM ‐ DGSCA / Victor Hugo Franco Serrano 39

<!-- p. 40 -->

Modelación Curso 3D Studio Max

\2. Barra de despliegue Noise: esta opción es utilizada para aplicar distorsión o un grado de
imperfección al bitmap, para lograr un material más realista.

Esta opción tiene seis controles.

a) On: activa los controles de distorsión que serán
aplicados al bitmap.
b) Amount: define la intensidad de la distorsión, los
valores van del 0 al 1.
c) Levels: precisa el número de fractales que
serán usados para la distorsión.

d) Size: determina la longitud de la distorsión.
e) Animate: define un movimiento en la distorsión.
f) Phase: precisa la velocidad de movimiento en la distorsión.

\3. Barra de despliegue de los Parámetros del bitmap: esta es la opción más importante en el Editor
de materiales, ya que se elige el bitmap para su uso y aplicación de cualquier parámetro.

En la parte superior de la barra de Despliegue está un
campo titulado Bitmap con un largo botón del lado
derecho, el cual permite cargar al bitmap dentro del
programa, dando un clic en este botón aparece la
ventana de selección de materiales.

En esta ventana de diálogo se puede elegir
cualquier variedad de bitmaps (gif, jpg, tga, tif,
bmp, png, etc.) para su uso en cualquier tipo de
material, inclusive se pueden cargar bitmaps
animados para su uso en materiales animados
(flc, fli, cel, avi).

UNAM ‐ DGSCA / Victor Hugo Franco Serrano 40

<!-- p. 41 -->

Modelación Curso 3D Studio Max

Debajo del botón de Bitmap aparecen varios parámetros de control, los cuales se dividen en tres
categorías: Filtering, Mono channel Output y Alpha Source.

a. Filtering: en esta opción se define el método de Anti-
aliasing. Hay tres métodos, Pyramidal,Summed Area y
None. En general la opción Summed Area es lo mejor
pero aumenta el tiempo de proceso; para la mayoría de
los proyectos la opción Pyramidal es una buena elección,
pero se puede elegir la opción None si se desea que no
se aplique ningún proceso de Anti-Aliasing al Bitmap.

Vale la pena recordar que para tiempo real el antialising
de textura y geometría es demasiado costoso para el
sistema, por lo que en lo general no se usa, por ende esta
opción del programa se aplica primordialmente al render.

b. Mono chanel Output: en esta opción se define el canal de color
del Bitmap que será usado para ciertos tipos de mapping. Existen
dos tipos de fuentes para trabajar con los canales el modo RGB y el
Alpha Chanel.

Es bueno recordar esta parte pues más adelante se utilizara con
texturas con transparencia.

c. Alpha Source: esta opción es utilizada para definir la
transparencia del bitmap. Se tienen tres opciones para definir
este valor, Image Alpha, RGB Intensity y None.

i) None: produce un bitmap opaco o sólido sin ningún
valor de transparencia.

ii) Image Alpha: usa el pixel superior izquierdo del
bitmap como el color transparente.

iii) RGB Intensity: toma el negativo del bitmap y asigna el
valor de transparencia basado en esta
información, el color negro es
completamente transparente y el
blanco completamente opaco.

UNAM ‐ DGSCA / Victor Hugo Franco Serrano 41

<!-- p. 42 -->

Modelación Curso 3D Studio Max

\4. Barra de despliegue de las opciones de Salida
(Output): en esta opción se determina la intensidad del
bitmap en el material y se pueden modificar los valores de
saturación, brillantez y contraste.

\5. Barra de despliegue de las opciones de Tiempo (Time):
en esta opción se define cómo y cuándo el Bimap animado
será desplegado.

4.4 Tipos de Mapas

3D Studio Max soporta una gran variedad de tipos de mapeo, los cuales son descritos a continuación.

Ambient Para asignar un bitmap al color de ambiente del material.

Diffuse Para asignar un bitmap al color difuso. Se debe recordar
que el color difuso es el que predomina en el material.

Specular El bitmap se aplica solamente en las regiones más brillantes
del material.

Glosiness El bitmap se aplica en las regiones brillantes del material.

Specular Esta opción proyecta solamente los valores más brillantes
level del Bitmap en el material.

Self- El bitmap se aplica solamente en las regiones del self-
Illumination: ilumination.

Opacity: Para controlar el grado de transparencia del bitmap.

Filter Color: Para modificar los colores de los objetos que se encuentran
detrás del material transparente, estos colores se suman a
los colores del bitmap.

Bump: Para obtener un efecto de tercera dimensión en la superficie
del material.

Reflection: En esta opción se utiliza un para ser usado como reflejo en
la superficie del material.

Refraction: En esta opción el bitmap es usado para controlar la
refracción de la luz en un material transparente.

UNAM ‐ DGSCA / Victor Hugo Franco Serrano 42

<!-- p. 43 -->

Modelación Curso 3D Studio Max

Todas estas opciones de mapeo cuentan con una caja para activarlas o desactivarlas, un campo para
definir su intensidad y se pueden combinar.

Manejo de mapas con transparencia

Las transparencias en texturas se obtienen a través del canal alfa, este canal permite definir las zonas de
total transparencia de color negro y las zonas carentes de transparencia de blanco, entre estas existe
una diversidad de escalas de grises, en donde el gris medio es una transparencia de 50%.

Mapa de difusión Alfa con diferentes valores de Visualización en tiempo real de
grises transparencia por textura

También es posible obtener la transparencia de textura, cuando la textura posee en si misma los valores
de transparencia como en el caso de png, que puede ser integrado en osg como textura con
transparencia.

Para hacer uso de estos mapas dentro de 3d studio max debemos:

1.- Asignar un material estándar a la geometría que deba llevar
la transparencia.

2.- Dentro del material estándar buscar la opción de Maps.

3.- En Maps buscar el canal que dice Opacity y dar clic en el
gran botón que dice NONE.

UNAM ‐ DGSCA / Victor Hugo Franco Serrano 43

<!-- p. 44 -->

Modelación Curso 3D Studio Max

4.- Se selecciona el mapa de bits que contenga al
canal alfa.

5.- Una vez cargada la textura se debe seleccionar en Mono Chanel
Output como Alpha.

6.- Al hacer esto el alfa de la textura será tomado en cuenta al momento
de hacer render o exportarlo para tiempo real.

4.5 Material multisubobjeto e Id de polígonos

Un material multisubobjeto es aquel que permite la integración de más de un material, ya sea estándar o
no, dentro de un solo elemento, al integrarse estos materiales no son mezclados, sino que conservan
todas sus propiedades de material estándar, la diferencia de uso de este material es que permite la
integración de varios segmentos geométricos que posean diferentes texturas.

Esto se logra al asignarle un numero identificador al objeto, por ejemplo en la esfera mostrada cada color
representa una región geométrica y cada una de estas regiones esta definida por un número, al
momento de configurar el material multisubobjeto (imagen central) se definen estos números ID y se
asigna para cada uno un material diferente, por ende al ser aplicado a al esfera es posible ver más de
una textura en el objeto.

UNAM ‐ DGSCA / Victor Hugo Franco Serrano 44

<!-- p. 45 -->

Modelación Curso 3D Studio Max

Existen diferentes materiales dentro de 3d studio max, en particular el material multi/subobjeto permite
congregar a muchos materiales juntos, que se identifican con un número, por ejemplo:

Identificador Materiales Zona del objeto que Aplicaciones de las
contiene al material texturas al material
multi/subobjeto
1 Madera
2 Ladrillos

3 Metal

4 Fruta

5 Yeso

2 ‐ Material ID

Para establecer el material ID o identificador debemos seleccionar los polígonos de cada zona
independientemente, luego darle a cada uno un número y asignar la textura multi/subobjeto.

Paso1: Seleccionamos los polígonos que integraran a cada una de las zonas del objeto

Paso2: Se estable el número ID

Paso3: Se asigna el material multi/subobjeto que tiene asignadas cada textura

Polígonos seleccionados Número ID Asignación de textura en el
material multi/subobjeto

UNAM ‐ DGSCA / Victor Hugo Franco Serrano 45

<!-- p. 46 -->

Modelación Curso 3D Studio Max

Para configurar la textura multisubobjeto debemos:

1.‐ Sustituir un material estándar por un 2.‐ Aparecerá la ventana emergente Material/Map
multisubobjeto dando clic en el botón Standar. Browser, en la lista de materiales deberemos
ubicar multi/sub‐objeto y dar doble clic.

UNAM ‐ DGSCA / Victor Hugo Franco Serrano 46

<!-- p. 47 -->

Modelación Curso 3D Studio Max

3.‐ Una vez cargado el material multisubobjeto debemos decidir
cuantos materiales se van a usar, para lograr esto, debemos dar clic
en el botón set number, en donde nos preguntara el numero de sub‐
materiales, debemos ingresar el numero necesario de materiales, por
ejemplo una caja de seis lados deberá tener seis sub‐materiales
dentro de la lista del material multisubobjeto.

4.‐ Es recomendable darle un nombre a cada material, tanto en el
material multisubobjeto como en el nombre del sub‐material
estándar.

Ejercicio: Aprendizaje del editor de materiales y manejo de materiales básicos,
con transparencia y de multisubobjeto

El objetivo de esta práctica es el de generar varias esferas y en cada una de ellas aplicar materiales con
diferentes valores, crear una esfera, editar sus IDs, configurar y aplicar un material multisubobjeto.

UNAM ‐ DGSCA / Victor Hugo Franco Serrano 47

<!-- p. 48 -->

Modelación Curso 3D Studio Max

4.6 Capacidad de exportación de materiales para tiempo real y materiales adicionales.

Uno de los más grandes conflictos a la hora de prepara contenido visual para ambientes virtuales radica
en lo que puede o no ser visible en tiempo real, como modeladores para tiempo real debemos tomar en
cuenta que no todos los materiales y efectos que max genera pueden ser visualizados en tiempo real,
aunque existen técnicas adicionales que ayudan a la conversión de materiales no exportables, lo realizan
convirtiendo un material o efecto complejo en texturas simples, y, empleando las coordenadas de textura
les es posible convertir, por ejemplo, texturas tridimensionales en bidimensionales o imprimir sombras y
brillos sobre las texturas bidimensionales1.

El reflejo simulado es uno de los ejemplos más comunes dentro de entornos
virtuales, para realizarlo se emplean texturas que representan al entorno de
los objetos.

El color por vértice es otra de las opciones adicionales que podemos usar en
3d studio max, en este proceso se pintan colores directamente sobre el
objeto, en la mayoría de los casos esta opción si puede visualizarse en
tiempo real.

Los procesos de baking de textura emplean la proyección y render
sobre texturas bidimensionales adicionándoles información de
iluminación, brillos y sombras, además es posible precalcular
reflejos y desarrollar objetos para su texturización.

Las texturas procedurales o texturas tridimensionales son
imágenes generadas a través de la computadora que emplea un
algoritmo para crear representaciones realistas de elementos
naturales como la madera, mármol, granito, metal, piedra entre
otros y son comúnmente referidas como shaders.

También son el proceso de dar color a las geometrías a través de fórmulas matemáticas. Para poder ver
un material procedural este debe ser convertido a una textura bidimensional basada en pixeles y en rgb,
esto se logra a través del proceso de texture baking.

1 Curso de iluminación global para ambientes virtuales (Franco Serrano, 2007)

UNAM ‐ DGSCA / Victor Hugo Franco Serrano 48

<!-- p. 49 -->

Modelación Curso 3D Studio Max

4.7 Edición de coordenadas UVW

Coordenadas UVW se refiere a la forma en como
las texturas son usadas en los programas
tridimensionales, en donde XYZ son
intercambiadas por UVW en donde U es el ancho
de la textura, V es el alto y W la profundidad, la
coordenada W solo es usable por texturas
tridimensionales o procedurales.

Los valores asignados a U, V y W individualmente
van del cero al uno, en donde cero es el origen de
la textura y uno es el final, si se asignan valores
mayores a uno entonces la textura será repetida el
numero de veces que el valor contenga, sea esto
el numero 3 en U repetirá 3 veces la textura en el
ancho del objeto.

Las coordenadas de textura pueden ser editadas dentro de 3d studio max, para llevar esto a cabo
debemos hacer uso de los modificadores UVW Map y Unwrap UVW de la lista de modificadores.

Por un lado UVW Map permite la edición de las coordenadas de
textura, al aplicarle el modificador es posible decidir si el mapeo será
planar, cilíndrico, esférico, como envoltura, como caja, por cara,
convirtiendo XYZ a UVW.

Permite también hacer tiling al posibilitar cambiar el número de
repeticiones en cada una de las direcciones de textura U, V y W,
existe la posibilidad de espejear la textura al dar clic en Flip, aunque
siempre es recomendable que la textura sea preparada en un editor
de imágenes antes de ser colocada en el objeto.

UNAM ‐ DGSCA / Victor Hugo Franco Serrano 49

<!-- p. 50 -->

Modelación Curso 3D Studio Max

Por otro lado Unwrap
UVW permite seleccionar
individualmente cada nivel
geométrico para hacer
una edición de
coordenadas UVW de
manera precisa, para
hacer uso de esta se debe
decidir a que nivel
geométrico se va a
trabajar, para
posteriormente
seleccionar el polígono y
aplicarle alguna de las
proyecciones que tiene,
planar cilíndrica, pelt,
esférica o de caja.

Para realizar la edición de
manera visual se debe dar
clic en el botón edit,
aparecerá la ventana
emergente Edit UVWs, en
ella es posible realizar
una edición de todos los

elementos geométricos de manera aislada y en conjunto con una buena distribución de los elementos
de una textura podrá servir para optimizar el uso de materiales y texturas.

La ventana complementaria de
Edit UVW permite la selección por
sub niveles geométricos, así es
posible decidir si se va a hacer la

edición por puntos, por líneas, por polígonos o por elemento, estas opciones son bastante útiles al
momento de editar las coordenadas de textura, existe la posibilidad de expandir o contraer la selección al
dar clic en el más y menos respectivamente, también es posible seleccionar puntos, líneas y polígono
pintando directamente sobre el editor de UVW, para ello es necesario seleccionar el pincel y definir que
tan grande queremos que sea dando clic en el más y menos que se encuentran a su derecha.

Ejercicio: Haciendo la caja del playmobil

El objetivo de esta práctica es la de modelar y texturizar por varios métodos la caja de playmobil, usando
primitivas, polígonos, material multi/sub-objeto y material estándar con edición de coordenadas UVW.

UNAM ‐ DGSCA / Victor Hugo Franco Serrano 50

<!-- p. 51 -->

Modelación Curso 3D Studio Max

4.8 Texturas Seamless

Seamless Sin Seamless

Las texturas seamless son texturas
que al ser repetidas no muestran
patrones evidentes de repetición.

Por lo general las texturas no
preparadas para ser repetidas tienden
a demostrar sus límites y a crear
líneas visuales desagradables, por
ende el uso de texturas preparadas
para su repetición favorecerá la
calidad visual del entorno
tridimensional.

\5. CREACIÓN DE LUCES Y CÁMARAS

Cuando se crea una escena, la manera en que se ve, es de suma importancia para expresar el
volumen de ésta al observador.

La escena se puede observar desde una vista ortogonal o una vista con perspectiva,
obviamente una vista ortogonal no es tan real como una vista con perspectiva o cámara. Así
mismo una mala iluminación decrece una escena, probablemente la iluminación es el aspecto
del realismo más importante en el proceso de renderización de una escena.

La combinación de estos dos aspectos es fundamental para un obtener buen resultado.

En los siguientes temas se abordarán las diferentes técnicas de iluminación así como la
definición de vistas con perspectiva y cámara.

5.1 Tipos de iluminación

Cuando se genera una escena, 3d Studio Max proporciona una iluminación artificial que
muestra un aproximado de cómo quedará ésta cuando sea renderizada. Siempre se debe de
renderizar la escena para saber exactamente cómo quedará la misma, la iluminación artificial
se pierde en el momento que se define cualquier tipo de luz.

Se debe tomar en cuenta que no todos los tipos de luces, sombras y brillos son susceptibles a
ser exportados para tiempo real, por ende aunque sea posible su renderización si se requieren
sombras en el entorno virtual se puede proceder al proceso de baking de texturas2.

5.1.1 Luz General

La luz general es la luz de ambiente que ilumina la escena entera.

Tiene una intensidad uniforme y es uniformemente difusa y no tiene ninguna fuente discernible
y ninguna dirección discernible.

2 Más información sobre Baking de textura en los tutoriales de la página del IXTLI curso iluminación global.

UNAM ‐ DGSCA / Victor Hugo Franco Serrano 51

<!-- p. 52 -->

Modelación Curso 3D Studio Max

Para modificar sus atributos se elige el menu Rendering- Environment.

5.1.2 Luz Omnidireccional

Las luces omnidireccionales iluminan desde un solo punto en todas direcciones y no se
puede restringir el rango de iluminación, pero permite excluir objetos.

Una luz omnidireccional proyecta sombras y es usada para proveer de iluminación
general a la escena.

Para generar una luz omnidireccional, se escoge el botón de Luces en el panel de
Creación, después se selecciona el botón Omni.

Después se definen los parámetros de la luz omnidireccional.

UNAM ‐ DGSCA / Victor Hugo Franco Serrano 52

<!-- p. 53 -->

Modelación Curso 3D Studio Max

5.1.3 Luz Dirigida

Este tipo de luz es usado comúnmente en las escenas y particularmente en escenas
de interiores. Estas luces son dirigidas a un punto específico, primero se define el
punto de iluminación y después se arrastra para definir el objetivo. Estas luces
proyectan sombras y pueden hacer uso de la atenuación.

Para generar este tipo de luz se elige el botón de Luces en el panel de Creación y se
selecciona el botón Target Spot.

Posteriormente se definen los parámetros de la luz dirigida.

5.2 Cámaras dirigidas

3D Studio Max proporciona dos formas de observar la escena. Con perspectiva y cámara
existen grandes diferencias entre estas dos opciones. La opción de la cámara muestra un ícono
que aparece en la escena y tiene parámetos de control, se puede modificar el campo de visión
y el tipo de lente.
La vista de perspectiva trabaja como cualquier vista ortogonal, excepto por que se puede
modificar el campo de visión. Esta vista de perspectiva funciona muy bien, sin embargo la vista
de la cámara es mucho más eficiente ya que se puede tener un control más amplio que en la
vista de perspectiva.

El uso de las cámaras en 3D Studio Max está basado en los principios de la fotografía. Por
ejemplo: una cámara de 35mm usa diferentes lentes para capturar imágenes de diferentes
tamaños, inclusive dos puntos están asociados siempre con una cámara de 35mm, el punto
donde está colocada (llamado punto de cámara) y el punto donde se está apuntando (llamado
punto del objetivo o target). Aplicando estas connotaciones se pueden crear vistas de cámara
con unas coordenadas precisas.

UNAM ‐ DGSCA / Victor Hugo Franco Serrano 53

<!-- p. 54 -->

Modelación Curso 3D Studio Max

El programa proporciona dos tipos de cámaras: Target y Free.

Para crear una cámara se activa el botón de Creación de cámaras
en el menú de Creación.

Una cámara dirigida tiene dos puntos, el de la cámara y el objetivo,
cada uno de estos puntos puede tener su propio nombre para
facilitar el trabajo, si no están ocultos estos puntos aparece un ícono
de la cámara en todos los cuadrantes.

Este ícono está compuesto de
tres partes: la cámara, el target
u objetivo y el cono.

El ícono representa el campo
de visión de la cámara, los
puntos de la cámara y el Target
del ícono pueden ser
transformados usando cualquier
método de transformación
estándar como son selección y
mover.

Para crear una cámara dirigida se elige el botón Target en el panel de
Creación de cámaras.

Una barra desplegable aparece y una vez elegido el botón se define la
posición de la cámara dando un clic en cualquier lugar de las vistas
ortogonales y dando un segundo clic para definir el Target.

Después de esto se activa la vista de la cámara eligiendo cualquier vista
ortogonal y presionando la tecla C.

Cuando es creada una cámara se pueden controlar cualquiera de los
parámetros mostrados en la barra de despliegue.

UNAM ‐ DGSCA / Victor Hugo Franco Serrano 54

<!-- p. 55 -->

Modelación Curso 3D Studio Max

\6. ANIMACIÓN

La animación está basada en el principio de la visión humana. Si se observa una serie de imágenes en
sucesión rápida, el cerebro percibe un movimiento continuo. 3D Studio MAX se refiere a cada imagen
como un cuadro.

Históricamente, la mayor dificultad en la creación de animaciones ha sido que los animadores deben
producir un gran número de cuadros, depende de la calidad que se requiera, por ejemplo un minuto de
animación podría requerir entre 720 y 1800 imágenes separadas. Crear estas imágenes cuadro a
cuadro, representa muchísimo trabajo. Es aquí donde el keyframing entra.

La mayoría de los cuadros en una animación implica cambios rutinarios, como incrementar cambios del
cuadro anterior y dirigirlo hacia alguna meta predefinida. Los estudios tempranos de la animación que se
realizaron permitieron comprender que se podía reducir el tiempo de producción haciendo que los
artistas dibujaran sólo los cuadros más importantes, llamados keyframes. De esta forma los ayudantes
podrían deducir los cuadros que se requirieran entre cada keyframe. Los cuadros fueron (y todavía son)
llamados tweens.

3DS Studio MAX es el ayudante de animación, el usuario es el maestro animador, éste crea los
keyframes que contienen el inicio y final de cada transformación. Los valores de estos keyframes son
llamados llaves. 3DS Studio MAX calcula los valores interpolados entre cada llave realizando el proceso
de tweens.

3DS Studio MAX no se limita a animar transformaciones básicas (como posición, rotación, y escala).
Puede animar cualquier parámetro al que se pueda acceder. De esta forma se pueden modificar
parámetros, como curvatura o un ángulo afilado, los parámetros de los materiales, como el color o
transparencia de un objeto, y mucho más.

UNAM ‐ DGSCA / Victor Hugo Franco Serrano 55

<!-- p. 56 -->

Modelación Curso 3D Studio Max

Aunque la limitante siempre se encuentra a la hora de visualizar estas animaciones en tiempo real, ya
que animaciones como los parámetros de los materiales no son posibles de exportar ni visualizar en
tiempo real.

6.1 Animación estándar

Cuando se crea cualquier objeto, 3DS Studio MAX graba su posición, rotación e información de la escala
en una tabla interior llamada matriz de transformación. A la subsecuente posición, rotación y escala se
les llama modificadores.

Un objeto puede contener cualquier número de modificadores, pero sólo un paso de transformación.
Aunque se pueden cambiar los valores de transformación cuadro por cuadro, cada objeto, en todo
momento, sólo tiene una posición, una rotación, y una escala de transformación.

Se pueden animar las transformaciones encendiendo el botón de Animación y realizando entonces la
transformación en cualquier cuadro que no sea el 0. Esto creará una llave para esa modificación en el
cuadro actual.

Para empezar la animación de un objeto:

a) Se enciende el botón de Animación.

b) Se arrastra el deslizador de tiempo a un cuadro que no sea el 0.

c) Se Definen los valores de modificación, rotación, posición, escala.

Por ejemplo: si se tiene un cilindro que no ha sido animado, este no tiene ninguna llave. Si se enciende el
botón de Animación, y en el cuadro 20 se rota el cilindro 90 grados sobre su eje de Y, las llaves de
rotación crean los cuadros 0 y 20. La llave del cuadro 0 contiene la orientación original del cilindro,
mientras la llave del cuadro 20 tiene la rotación animada de 90 grados.

Cuando se despliega la animación, el cilindro rota 90 grados sobre su eje de Y en 20 cuadros.

UNAM ‐ DGSCA / Victor Hugo Franco Serrano 56

<!-- p. 57 -->

Modelación Curso 3D Studio Max

6.2 Módulo de control de llaves

El control de llaves (Keyframes)
graba el inicio y el final de cada
transformación de un objeto o
elemento en la escena. Los
valores de estos keyframes son
llamados llaves.

Por ejemplo, si se tiene una
esfera que no ha sido animada,
ningún keyframe (o llave) existe
para ella. Si se enciende el botón
de Animación, se mueve al
cuadro 20, y si se rota la esfera
90 grados, se crean llaves de La llave del cuadro 0 representa la orientación de la esfera antes de
rotación entre el cuadro 0 y 20. que fuera rotada, mientras la llave del cuadro 20 representa la
orientación de la esfera después de que se rotó 90 grados.

Cuando usted despliega la animación, la esfera rota de 0 a 90
grados en 20 cuadros.

\7. Herramientas Adicionales

7.1 Conteo de polígonos y propiedades de objeto

El conteo de polígonos dentro de 3d studio max se obtiene de varias formas, la primera de ellas es
dando clic en el menú edit y luego en propiedades, la segunda es dando botón derecho sobre el objeto y
clic en propiedades, ambas opciones despliegan la ventana emergente Object Properties, en ella es
posible ver la cantidad de vértices y polígonos que nuestro objeto contiene.

Como aclaración, en max al contabilizar los polígonos de un objeto Editable Poly estos se contabilizan
como cuadrados, por lo que se debe contemplar que en la mayoría de los casos los engines tomaran en
cuenta una cantidad del doble del valor pues ellos toman en cuenta triángulos por lo que los polígonos
son divididos y por ende el conteo sube al doble.

UNAM ‐ DGSCA / Victor Hugo Franco Serrano 57

<!-- p. 58 -->

Modelación Curso 3D Studio Max

Menu Edit Y Object Clic derecho sobre el objeto y Ventana emergente de Object
Properties… Properties… Properties

Existe otra posibilidad para ver en tiempo real el conteo de polígonos, para ello
debe darse clic derecho sobre el nombre del viewport, como por ejemplo sobre
perspectiva y seleccionar la opción Show Statistics, esta opción desplegara en
pantalla la cantidad de polígonos y vértices que contiene la escena, además de
mostrar la cantidad de cuadros que son representados en el programa.

7.3 Ayudantes

Los ayudantes de max son objetos no visibles que ayudan a mejorar las capacidades del programa o a
servir de apoyo a procesos más complejos como la animación de personajes.

En este curso nos enfocaremos a los ayudantes que ocuparemos a lo largo del desarrollo de contenido
grafico para tiempo real.

UNAM ‐ DGSCA / Victor Hugo Franco Serrano 58

<!-- p. 59 -->

Modelación Curso 3D Studio Max

OSG VRML Reactor

7.4 Sistemas

Los sistemas dentro de max son configuraciones de elementos
preestablecidos que permiten acelerar y auxiliar algunos procesos, es el
caso de la animación, iluminación y arreglo.

La mayoría de estos sistemas al crearse necesitan de configuración en
diferentes paneles, pues por ejemplo con el de la iluminación necesita
ser definida en los valores de su fuente de luz, además de necesitar la
configuración de su orientación relativa a una rosa de los vientos en la
escena que representa la orientación de la luz.

UNAM ‐ DGSCA / Victor Hugo Franco Serrano 59

<!-- p. 60 -->

Modelación Curso 3D Studio Max

Biped

Es un sistema prefabricado de ayudantes en el
que previamente se encuentran establecidas las
relaciones jerárquicas de los elementos que lo
integran, el nombre biped refiere a la disposición
bípeda que el sistema posee y es posible usarlo
en la animación de personajes bípedos.

Además de su creación de colocar y arrastrar en la
escena, este debe ser configurado en sus
parámetros generales de altura y configuración de
los huesos del cuerpo.

Además de estas configuraciones es necesaria la
configuración de la animación automática o el
desarrollo de una animación simple por elemento
del biped.

Con el biped es posible usar configuraciones y
animaciones realizadas con anterioridad o de
colecciones.

UNAM ‐ DGSCA / Victor Hugo Franco Serrano 60

<!-- p. 61 -->

Modelación Curso 3D Studio Max

Sunlight y daylight

Es una configuración
previa de una luz que
asemejaría a la luz del
sol, pues está regida por
un sistema de orientación
tipo rosa de los vientos y
un mapa de localización
geográfica que define la
posición del norte de la
escena.

Otra de las opciones que
se pueden configurar en
este sistema es la de la
fecha y hora del día, esto
influirá en la intensidad,
color y posición de la luz
en la escena.

7.5 Menú jerarquía

Dentro de este menú es posible editar por separado elementos del objeto que
pueden ayudarnos en el proceso de modelado o animación, puesto que el
modelo puede ser separado en su pivote, en su geometría o en su jerarquía y
actuar individualmente en cada uno de ellos sin afectarse entre sí.

Es posible también restablecer la posición del pivote del objeto, también es
posible por medio de botones centrar el pivote al objeto o alinear el pivote al
mundo o al objeto.

También es posible editar la cinemática inversa de los objetos de la escena y
mostrar la información de sus vínculos.

Edición del Pivote o centro de rotación

UNAM ‐ DGSCA / Victor Hugo Franco Serrano 61

<!-- p. 62 -->

Modelación Curso 3D Studio Max

El pivote es el lugar o centro de rotación de
los objetos, este puede ser modificado en 3D
Studio Max dentro del menú jerarquía, para
ello debemos dar clic en Afect Pivot Only con
lo cual solo será afectado el pivote del objeto,
más no la geometría, una vez hecho esto
debemos editar el pivote con las
transformaciones básicas mover y rotar.

Uno de los porques de la importancia del pivote
radica en su uso en animación y modelado, pues
el pivote al servir como centro de rotación permite
al objeto no solo rotar o trasladarse desde su
centro sino desde cualquier punto del espacio
tridimensional.

En la imagen podemos observar a una esfera con
el pivote, su pivote fue modificado para
posicionarlo fuera del centro del objeto, y al girar
este girara desde el punto de referencia del pivote

7.6 Menú despliegue

El menú de despliegue permite editar la forma en cómo se seleccionan y ven
los objetos en pantalla, lo realiza a través del modo de aislamiento,
congelamiento, ocultar y de ver a través.

Las opciones que esta sección despliega son individuales para cada objeto
por lo que para hacer uso de estas opciones debemos tener seleccionado el
objeto y dar clic en el menú despliegue, posteriormente se debe buscar las
opciones que da el sistema, esconder, congelar y propiedades de despliegue
son mostradas en esta sección, dentro de estas existen, mostrar gris al
congelar, Ver a través, desplegar como caja, esconder, esconder selección,
congelar, descongelar, entre muchos otros.

UNAM ‐ DGSCA / Victor Hugo Franco Serrano 62

<!-- p. 63 -->

Modelación Curso 3D Studio Max

Modo aislamiento

El modo de aislamiento permite extraer temporalmente a algunos de
los elementos de un escena para su edición individual.

Para realizar el aislamiento de uno o varios objetos debemos
seleccionarlos, para luego dar clic derecho sobre de ellos y en la
ventana emergente seleccionar isolate selection, como se muestra en
la imagen de la izquierda.

Al entrar en modo de aislamiento aparecerá la ventana Warning:
Isolated Selection, que es un gran botón amarillo que dice Exit
Isolation Mode, al dar clic en el saldremos del modo de aislamiento.

Esconder

Dentro de 3D Studio Max es posible esconder los objetos
de la escena dando, para llevar esto a cabo se debe
seleccionar el objeto a esconder y dar clic derecho, al
aparecer la ventana emergente se debe seleccionar la
opción Hide Selection, adémas de esta opción es posible
esconder a los objetos de la escena de forma inversa al
seleccionar el objeto a conservar y dando clic en Hide
Unselected.

Si ya se tienen escondidos objetos en la escena, la forma
de que aparezcan es dando clic en Unhide All, aunque
las opciones permiten seleccionar a los objetos que
queramos que aparezcan por medio de una lista.

También es posible acceder a las opciones dentro del
menú despliegue.

UNAM ‐ DGSCA / Victor Hugo Franco Serrano 63

<!-- p. 64 -->

Modelación Curso 3D Studio Max

Congelar

La opción de congelamiento o freeze permite al usuario, ,
con esto se protegen de cualquier modificación a los objetos
que se hayan congelado.

Esta opción es bastante útil pues en ocasiones necesitamos
modificar solo a algunos elementos y dejar como están a los
elementos que los rodean.

Para congelar a algún objeto en la escena debemos
seleccionar el objeto a congelar y dar clic derecho sobre él,
al aparecer la ventana emergente debemos seleccionar
Freeze selection, con esto se habrá congelado el objeto.

Para descongelar a los objetos que congelamos debemos
dar clic en cualquier zona de los viewports y seleccionar la
opción Unfreeze all.

Nota: Al dar clic en Unfreeze all se descongelaran todos los
objetos de la escena.

UNAM ‐ DGSCA / Victor Hugo Franco Serrano 64

<!-- p. 65 -->

Modelación Curso 3D Studio Max

7.7 Menú Utilities

La ventana del menú utilities permite
acceder a complementos para 3d studio
max, es posible al instalar algunos
plugins adicionales acceder a estos
mediante el botón More… que se
encuentra en este menú, al oprimir este
botón se despliega la ventana Utilities
en donde se encuentra una lista con las
opciones adicionales y los plugins de
max.

Cuando se establecen operaciones
adicionales en max a veces es
necesario configurar parámetros y para
ello el menú utilities los despliega en su
parte inferior, en la imagen podemos
observar al plugin Reactor y debajo
podemos observar algunos parámetros
de configuración del mismo.

Es posible agregar botones al menú
utilites, para lograr esto se debe dar clic
en el icono Configura Button Sets, al dar
clic en el es posible configurar en su
ventana el numero de botones en
pantalla, pues existe el numero de Total
Buttons, al agregar uno se debe
arrastrar sobre el nuevo botón desde la
lista del lado izquierdo.

UNAM ‐ DGSCA / Victor Hugo Franco Serrano 65

<!-- p. 66 -->

Modelación Curso 3D Studio Max

7.8 Vista esquemática y vínculos jerarquicos

La vista esquemática muestra las relaciones de parentesco jerárquico entre los objetos del entorno
virtual, es posible modificar estas relaciones y definir nuevas, en la imagen podemos observar un sistema
bípedo con diferentes jerarquías, la jerarquía se lee de arriba abajo y en forma de árbol invertido, tienen
la posibilidad de visualizar una ventana flotante donde muestra una paleta de identificación o Display de
los elementos jerárquicos.

UNAM ‐ DGSCA / Victor Hugo Franco Serrano 66

<!-- p. 67 -->

Modelación Curso 3D Studio Max

Para establecer jerarquías manualmente
se debe dar clic en el icono Select and
Link.

Posteriormente dar clic en la geometría hijo y
arrastrar hasta la geometría padre, al realizar esto
se establece una relación jerárquica.

Para romper un vínculo jerárquico se debe seleccionar al objeto vinculado, y dar clic en el botón
Unlink Selection, con esto se habrá roto el vínculo entre ellos y puede establecerse una relación
jerárquica diferente.

Es posible visualizar esta relación jerárquica entre todos
los elementos además de modificarlos directamente en la
pantalla esquemática. Es posible usar el editor
esquemático para seleccionar a los niveles jerárquicos,
estos pueden servir al momento de realizar animaciones
básicas, pues pueden realizarse menos pasos para
mover todos los objetos de una escena.

7.9 Manejo de grupos

Agrupar Desagrupar

Para realizar grupos en max se deben seleccionar los objetos a
agrupar e ir al menú Group, dentro de este se encuentra la opción
agrupar.

Al dar click aparecera una ventana emergente que nos pedira darle
nombre al grupo, una vez concretado el grupo este integrara sin
combinar a las geometrias.

Para desagrupar se debe seleccionar el grupo y oprimir Ungroup
dentro del menu Group.

UNAM ‐ DGSCA / Victor Hugo Franco Serrano 67

<!-- p. 68 -->

Modelación Curso 3D Studio Max

Abrir Cerrar

Los grupos en max pueden ser editados sin necesidad de ser
desagrupados, para ello existe en el menú Group la opción Open
que abrirá temporalmente el grupo y podrá ser editado.

Al finalizar la edición se debe cerrar el grupo con la opción Close.

7.10 Attach y Detach

Attach sirve para la integración de varios objetos
o elementos en un mismo objeto, o a la inversa,
en el caso de detach, para lograr un Attach de
varios objetos se debe dar clic en el botón Attach
que se encuentra en el panel de comandos al
seleccionar alguna geometría en modo Editable
Mesh o Editable Poly, después se da clic en el

objeto u objetos que se quieran integrar, es muy
importante dar clic en el botón activo de attach
al finalizar la integración, pues si no se hace
esto cada clic integrara otras geometrías.

.

Para realizar un Detach o extracción de un
elemento geométrico se debe seleccionar
el elemento o polígonos que se decida
extraer, para luego dar clic en detach, al
realizar esto aparecerá una ventana
emergente que nos preguntara del cómo
queremos realizar la extracción del
elemento geométrico o de los polígonos.

UNAM ‐ DGSCA / Victor Hugo Franco Serrano 68

<!-- p. 69 -->

Modelación Curso 3D Studio Max

Es posible extraer la seleccion para generar un nuevo elemento o
una copia de este como clonación, al oprimir clonación el elemento
seleccionado no se separa sino más bien genera uno nuevo que
puede ser usado de forma separada, otra de las opciones que
brinda la ventana es la de decidir el nombre del objeto al
preguntarnos Detach as:.

7.14 Manejo de configuraciones

Para configurar opciones de
max se debe dar clic en
Customize, en este menú se
despliegan varias opciones de
configuración dentro de las
cuales se encuentra Units
Setup, aquí es posible cambiar
las unidades en la que son
creados los objetos de la
escena.

Las opciones que aparecen en
la ventana Units Setup permite
decidir el sistema métrico que
se quiera usar, por lo regular en
México elegimos el sistema
métrico decimal basado en
metros, centímetros o
kilómetros.

UNAM ‐ DGSCA / Victor Hugo Franco Serrano 69

<!-- p. 70 -->

Modelación Curso 3D Studio Max

La ventana Preference Settings permite
editar muchos de los aspectos y
configuraciones de 3d studio max, para
desplegarla se debe dar clic en el menú
Cuztomize, para posteriormente dar clic
en preferences.

UNAM ‐ DGSCA / Victor Hugo Franco Serrano 70

<!-- p. 71 -->

Modelación Curso 3D Studio Max

8 Proyectos de Evaluación

Los proyectos de evaluación son formas en las que puedes autoevaluar tus conocimientos sobre 3D
Studio Max y el modelado para tiempo real. La idea de estos proyectos es realizarlos en conjunto con el
aprendizaje teórico de 3d studio max y poder en última instancia tener modelos que puedan ser usados
durante otros curos de modelación, exportación y visualización.

Realización de una casa

Reafirmación del conocimiento de uso de referencias, modelado poligonal, uso de texturas y materiales,
iluminación, cámaras y render, aprendizaje de las limitantes de exportación, recursos adicionales,
configuración y uso de las coordenadas de textura UVW,

Realización de una calle.

Reafirmación de conocimiento de modelado poligonal, uso de clonación y espejeo de objetos
tridimensionales, Texturización y manejo de materiales, uso de texturas seamless y edición de
coordenadas de textura, uso de materiales con transparencia, visualización del espacio virtual para
tiempo real.

UNAM ‐ DGSCA / Victor Hugo Franco Serrano 71

<!-- p. 72 -->

Modelación Curso 3D Studio Max

La caja de Playmobil

Dentro de este proyecto el alumno reforzara sus conocimientos de modelado, asignación de
coordenadas de textura, materiales multisubobjeto, id para texturización y selección, iluminación,
cámaras y render, animación básica y animación por medio de modificadores, clonación, espejeo y
alineación de objetos tridimensionales, uso y conversión de primitivas básicas, modos de selección,
grupos y attach y detach.

UNAM ‐ DGSCA / Victor Hugo Franco Serrano 72
