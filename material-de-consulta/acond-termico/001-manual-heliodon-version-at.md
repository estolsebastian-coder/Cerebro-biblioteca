---
type: libro
title: "Manual final version 11.cdr"
author: "decca5"
categoria: "ACOND. TÉRMICO"
paginas: 17
extraccion: "texto"
fuente: "local:E:/MATERIAL DE CONSULTA/ACOND. TÉRMICO/001_Manual HELIODON_version AT.pdf"
convertido: 2026-10-16
---

# Manual final version 11.cdr

> Texto extraído de `ACOND. TÉRMICO\001_Manual HELIODON_version AT.pdf` (17 páginas, texto). El PDF original está en el disco E: (MATERIAL DE CONSULTA); `<!-- p. N -->` marca el inicio de cada página.

<!-- p. 1 -->

SetiembreSetiembre 20102010

CátedraCátedra dede AcondicionamientoAcondicionamiento TérmicoTérmico

ManualManual HeliodónHeliodón
AT 02

farqlfarql UruguayUruguay

<!-- p. 2 -->

TrabajoTrabajo realizadorealizado por:por:

BenoitBenoit BeckersBeckers

LucLuc MassetMasset

GoriGori MoyaMoya

LaLa presentepresente ediciónedición haha sidosido adaptadaadaptada por:por:

VerónicaVerónica CabreraCabrera

LucianaLuciana EspinosaEspinosa

AlejandraAlejandra SerraSerra

<!-- p. 3 -->

2
1 Introducción
Heliodón es un programa de diseño solar interactivo que permite estudiar los trayectos
solares desde cualquier punto del globo y analizar la incidencia de la luz solar directa en
cualquier edificio o zona urbana, teniendo en cuenta el enmascaramiento producido por
otros edificios u obstáculos naturales. Puede mostrarse en estudios sencillos,
permitiendo un vaivén constante entre la vista en planta de la configuración estudiada y
el diagrama solar correspondiente.

2 Las tres ventanas

En Heliodón, la pantalla está dividida en tres ventanas. A la izquierda, ocupando
aproximadamente los dos tercios de la pantalla está la vista en planta.
A su derecha encontramos el diagrama solar (arriba) y una pequeña vista en
perspectiva (abajo). Esta última se halla desactivada al iniciar el programa.

diagrama solar
vista en planta

Vista en perspectiva

Arriba de todo, a la izquierda, aparecen 5 botones.

Load image: permite importar imágenes en la vista en planta, para calcar su
geometría, tras indicar su escala. Podemos importar imágenes con formato
jpg,bmp,tif.

Load data: permite cargar un trabajo previamente guardado en el formato propio
del programa (helio)

Save data: permite guardar un trabajo, para recuperarlo luego con Load data

Print: permite conservar la vista completa del programa como imagen ej jpg

Refresh: permite refrescar la pantalla cuando el programa queda bloqueado,
generalmente si olvidamos desactivar la función de rotación en la vista de
perspectiva antes de cambiar de operación.

<!-- p. 4 -->

3
3 Diagrama Solar

En esta ventana se presenta un diagrama de los trayectos solares en proyección
estereográfica.
Arriba, se indica la latitud estudiada. Al iniciar el programa, estamos a 0 grados y 00
minutos de latitud norte. El sol, indicado por un pequeño disco amarillo, está en la
posición que corresponde a la fecha de los equinoccios (21 Mar, 21 Sep.)
Al mantener el botón izquierdo del ratón presionado sobre el sol, podemos desplazarlo
libremente sobre el diagrama.
Al mantener el botón izquierdo presionado sobre la letra N, podemos hacer rotar el
diagrama, cambiando la orientación del norte geográfico. Esta modificación repercutirá
en las otras vistas, ya que el diagrama solar les sirve de brújula.
Observamos que el sol sigue en la misma posición es decir, sin modificar las
coordenadas temporales.

Al pulsar con el botón derecho del ratón en cualquier parte del diagrama,
aparece un menú con las siguientes funciones :

“Select town” permite entrar la latitud de una de las ciudades de la lista propuesta,
cuyo nombre aparecerá luego en el encabezamiento del diagrama.
La lista de las ciudades disponibles se encuentra en el fichero c:\heliodon\towns.txt
y se puede modificar manualmente
“latitude” permite introducir manualmente cualquier latitud, en grados y minutos.
Por ejemplo si ponemos 34° 5´ S nos encontramos en Montevideo

<!-- p. 5 -->

4
“date” permite introducir la fecha del análisis, escogida en un calendario.
“time” permite introducir la hora del análisis con el formato ‘hh:mm’
“show time labels” nos permite visualizar las lineas horarias.
“rotate” nos permite orientar el diagrama (mover la orientacion del Norte).
Además de la lista propuesta “set angle”
podemos introducirle un valor numérico y “Flip North” invierte el Norte y el Sur

4 Vista en planta

Al iniciar el programa, la vista en planta muestra una malla de puntos.
Abajo a la derecha, aparece la indicación de escala : cuatro metros
corresponde a cuatro espacios de malla; por lo tanto, dos puntos de la malla
están separados por un metro.
En el centro vemos:
\- un cuadro negro (el indicador del zoom). La escala de representación (zoom)
podemos aumentarla pulsando el botón central del cuadro negro ,
mientras que si pulsamos con el derecho, disminuye. Si lo arrastramos a cualquier
punto de vista con el botón izquierdo del ratón, observamos que vuelve siempre al centro,
atrayendo consigo al dibujo: funciona como un mando “pan”.
\- un disco blanco (el observador ). Al mantener el botón izquierdo del ratón presionado
sobre el disco, podemos desplazarlo libremente. Pulsando con el botón derecho sobre el
observador, hacemos aparecer un menú que nos permite cambiar su altitud (”height”),
su posición en la vista en planta (”position”) o su color (”color”).
La altitud del observador determina la del plano de referencia para el estudio de
asoleamiento y el trazado de sombras.
Si elevamos el observador, vemos que sólo los objetos a alturas mayores siguen proyectando
sombra. Ya que las otras entidades quedan por debajo del plano de sombras.
En la vista en planta, aparecen entonces en lineas punteadas. Sus máscaras
desaparecen del diagrama solar.
En la vista en perspectiva, es como si una nube oscura tapara todo lo que está por
debajo de la posición del observador.

Es importante aclarar ciertos conceptos :
Al pulsar con el botón derecho del ratón en cualquier parte del diagrama, aparece el
menú de dibujo (Imag 4), donde tenemos herramientas para el control y modificación
de la malla.
En el menu dibujo encontramos:
“add prismatic building” define un edificio prismático recto ,con base poligonal,
la cual se introduce pulsando sucesivamente el botón izquierdo del
ratón en los futuros vértices. Si nos equivocamos, podemos retroceder con el botón
derecho del ratón. Al llegar al último, tras pulsar la tecla”e”, el polígono se cierra
automáticamente y aparece un menu donde se nos pregunta la altura del prisma.
Pulsando el botón central del ratón también podemos realizar el comando. (Imag 5)
Con add prismatic building podemos conformar el entorno del estudio (plaza,calle...).

<!-- p. 6 -->

5

Pulsando el botón derecho sobre la entidad dibujada, obtenemos un menú flotante que
nos informa de sus propiedades.
En este caso, nos dirá la altura, permite modificar el color o eliminarla.(imag 6)

imag 4 imag 5

imag 6

“add horizontal panel” define un panel horizontal de manera similar a
como hacemos un edificio prismático. Al finalizar de su definición obtenemos un plano
horizontal situado a la altura definida. Debemos notar que en la vista en planta
no se diferencia de un edificio prismático, ya que ambas proyecciones corresponden a polígonos.
“add vertical panel” , define un panel vertical, cuya proyección en planta se dibuja
pulsando el botón izquierdo del ratón dos veces, para ubicar el principio y el fin del segmento.
Podemos seguir pulsando el botón en otros lugares para corregir la posición.
Obteniendo el resultado deseado y pulsando la tecla”e” hacemos aparecer un menú doble
que nos pregunta la altura del panel.
Tras indicarla y pulsar ”OK”, el segmento cambia de color y se completa con la sombra que
arroja la pared.
“add room” permite introducir un edificio prismático al que sí le podemos poner ventanas
en diferentes paredes o en el techo, y dentro del cual podemos entrar.
Esta entidad nos permite analizar espacios interiores
se define exactamente como el prisma, pero le podemos especificar la altitud a la cual
se encuentra su base con respecto al nivel del suelo (”floor level”):

<!-- p. 7 -->

6

.
Además de los comandos para introducir y editar entidades modelizadas, el menú
flotante de la ventana de dibujo ofrece las siguientes opciones:
“standard view” se usa para volver a la vista general cuando estamos en una vista
interior (dentro de room).
“hide/show image” muestra u oculta la imagen que hemos cargado como fondo.
“scale” permite modificar la escala de representación a través de la introducción de
factor de escala.
“grid spacing” modifica el espacio de los puntos de la malla con la única limitación de
que permanezca siempre por lo menos dos veces inferior al valor de “scale”.
“snap to grid” activa o desactiva la atracción de la malla.
“darken shadow” y “lighten shadow” permite aclarar u oscurecer sombras.

<!-- p. 8 -->

7
5 Vista en perspectiva

Esta vista nos mantiene en contacto con una visión espacial del problema estudiado.
Sólo dispone de un mando importante: la función “rotate” que se activa al pulsar con
el botón izquierdo del ratón en cualquier parte de la ventana. Un rótulo rojo aparece
arriba de la vista, indicando que la función está activada.
Si desplazamos el ratón manteniendo este botón pulsado,
aparecen las aristas de un cubo que indican la rotación que estamos efectuando.
Al soltar el botón, la rotación se realiza.

Al pulsar el botón central del ratón, la función se desactiva.
Si dejamos el “rotate” activado y vamos a trabajar en una de
las dos otras ventanas, nos resultará imposible realizar ciertas
operaciones, como la de desplazar el sol en el diagrama solar
o el observador en la vista en planta.
Además, comprobaremos que ya no podremos desactivar la
función de la vista en perspectiva.
Para salir de esta situación de bloqueo, podemos siempre
pulsar el botón “refresh” y “rotate” se desactivará.

Pulsando el botón derecho del ratón en cualquier parte de la vista en perspectiva, aparece
un menú adicional, donde podemos activar/desactivar la función “rotate” , cambiar el color
del fondo “ground color” , oscurecer o aclarar las sombras y activar/desactivar la función “light”.

6 Vista interior

La habitación “room” es un edificio prismático particular al cual podemos acceder a su
interior.
Pulsando el botón derecho del ratón sobre la habitación, hacemos aparecer un menú
donde esta la opción “add/modify roof windows”, que nos permite acceder a una
nueva ventana, que reproduce la vista en planta del techo.
Pulsando el botón derecho del ratón en cualquier parte de la ventana, hacemos aparecer
un menú con dos opciones.
“add rectangular window” nos permite crear una abertura cenital o ventanas.
“update” nos hará volver a la vista anterior.
Si elegimos la primera opción, aparecerá una ventana rectangular, que podremos desplazar
hacia cualquier parte del cerramiento (arrastrándola tras pulsar el botón izquierdo en su centro),
agrandar (arrastrando una de sus esquinas) o deformar (arrastrando el centro de uno de
sus lados). Su forma permanecerá siempre rectangular, y no se puede traspasar los
límites del techo. Pulsando el botón derecho sobre la ventana se nos ofrece la opción de
duplicarla o eliminarla.
Podemos añadir tantas ventanas como queramos pero nunca se pueden solapar entre sí.

<!-- p. 9 -->

8

Tras volver a la vista normal (con “update”), pulsando con el botón derecho del ratón
sobre cualquier pared de la habitación, hacemos aparecer un menú cuyas dos primeras
líneas nos informan de los datos geométricos de la pared. La opción “add/modify window”
nos permite perforar esta pared, del mismo modo que el techo . La opción “color”
nos permite modificar el color de la pared (y no de la habitación completa).
Al añadir ventanas, comprobamos en la vista en perspectiva las perforaciones de la habitación.
Tras abrir todas las ventanas deseadas, pulsamos con el botón derecho del ratón en el interior
de la habitación (pero fuera de las eventuales ventanas cenitales), y vuelve el menú de la
habitación, donde podemos elegir la opción “go inside”, que nos llevará dentro de la habitación,
en la vista interior.
Notamos que el observador se ha trasladado automáticamente dentro de la habitación.
En el diagrama solar vemos cómo y cuándo las ventanas dejan entrar la luz.
Para volver a la vista anterior, basta con pulsar “standard view” en el menú habitación.
Finalmente podemos añadir objetos al interior de la habitación, de modo que la atraviesen.
También es posible crear varias habitaciones, cada una con su interior.

<!-- p. 10 -->

9
5 Trabajemos con un ejemplo

\1) Cargo la imagen de la planta del edificio a estudiar con el botón load image (imag 1 y 2)
\2) Tenemos que escalar la imagen para poder realizar un dibujo encima de ella.
La escala se dará a través de una medida patrón. Se pulsan dos puntos y
el programa pedirá la distancia de la que se trata. (imag 3)

imag 1

imag 2 imag 3

En primer lugar estudiaremos el dormitorio 1 cuyas dimensiones son de 4.3x3x2.40mts.
y que posee un cerramiento transparente (1.50x1.10m).(imag.4)

dormitorio 1

imag 4

<!-- p. 11 -->

10

Tecleando el botón derecho aparecerá una ventana de opciones,
pulsamos add room imag.2
Si el tamaño de la habitación a estudiar no es el apropiado,
dentro de la misma encontramos el comando escale
( cuanto más pequeño sea el valor algebraico mayor
zoom realizará). Imag.3

imag 2

imag 3
imag 4

Una vez pulsado el comando add room, trazamos la habitación por sus vértice .
Luego de cerrado el polígono, pulsamos la letra E. Imag 4

Aparecerá una ventana, ver imag. 5, “room height
and elevation , que permite definir la altura del local
(en nuestro caso 2.40m) y el nivel de piso
(que lo dejaremos en cero). Si la habitación a
estudiar hubiera estado en un segundo piso,
en floor level anotaríamos por ejemplo 2.50m
y luego el programa tomaría la altura height del imag 5
local desde este nivel de piso.
Una vez ingresado este valor el programa arrojará las sombras del objeto de estudio en
la vista en planta y sus obstrucciones correspondientes dentro del diagrama solar imag.6.
Para su fácil comprensión s e recomienda el cambio de color de
cada pared de la habitación y del techo, acción que se puede realizar
en su conjunto o por separado.

En conjunto:
Nos situamos encima de la habitación, pulsamos botón
derecho, se desplegará una ventana (cuyos primeros items
corresponden a características de la misma) y
teclamos el comando color, ver imag.1 siguiente pag.

imag 6

<!-- p. 12 -->

11

Por separado:

Se sitúa el cursor sobre la pared cuyo color queremos modificar,
pulsamos el botón derecho del mouse, se desplegará una
ventana, los primeros items son características de la pared, largo, imag. 1
inclinación. imagen 2

Apertura de cerramiento transparente:

Se sitúa el cursor sobre la pared que aloja el cerramiento
transparente, pulsamos el botón derecho del mouse y
pulsamos el comando add/modify windows, imagen 3
imag. 2

:

imag. 3

imag. 4

Aparecerá una nueva ventana donde se encuentra dibujada la fachada del cerramiento vertical
,imagen 4 , se teclea el botón derecho del mouse y accedemos al comando add rectangular
window. Imagen 5

:
:

1.50x1.10
antepecho a +0.9 de
N.P.T

imag. 6 imag. 5 imag. 7
Dibujamos el cerramiento transparente, tomando de referencia la grilla, para cambiar
el espacio de la misma pulsamos el comando grid spacing, también nos podemos imantar
a la misma, activando el snap to grid. Ver imagen 5 y 7.
Recordemos que para estas es necesario que el observador esté situado sobre
el antepecho de la ventana. Para salir de está ventana pulsamos update.
Para activar la abertura tenemos que entrar a la habitación,
se hace mediante el comando go inside room. Imagen 8
:
Dentro de la misma habitación nos
: podemos mover libremente.
Para salir de la misma pulsamos botón
derecho del mouse y dentro de la
ventana del menú presionamos
standard view. Imagen 9

imag. 8 imag. 9

:

<!-- p. 13 -->

12

La nueva habitación a estudiar es el sector living-comedor-cocina, que consta de tres
cerramientos vidriados en diferentes paredes. El procedimiento es similar al realizado
anteriormente, solo difiere en que dos de las aberturas tienen dispositivos de protección
horizontales, “aleros” ver imagen 1

alero 1
alero 2
2.00x1.50 1.50x1.10 0.75x1.10
antepecho a +1.00 de antepecho a +0.9 de antepecho a +0.9 de
N.P.T N.P.T N.P.T

imag. 1

imag. 2
Luego de trazar la habitación con sus aberturas, se colocan los aleros.
Como ejemplo realizaremos un alero.
\1. Tecleamos el botón derecho del mouse,
se despliega una ventana y pulsamos el comando
add horizontal panel, imagen 2.
Trazamos el alero por sus vértices como lo
haríamos con add room.
Cuando cerremos el polígono puslaremos la letra e,
y nos pedirá la altura. imagen 4.
Se deberá activar el alero, entrando a la
habitación como lo haríamos en el caso anterior.

imag. 3

imag. 4

<!-- p. 14 -->

13

Para realizar Parasoles horizontales ,
se selecciona el comando add horizontal panel, se
establece la dimensión del parasol y luego con el comando
Height, se establece la altura a nivel de piso que deben
estar colocados y con el mismo procedimiento que los
anteriores ejemplos se realiza el estudio del asoleamiento.

imag. 1

De la misma manera se podrán realizar parasoles
verticales , en este caso se deberá utilizar el comando add
vertical panel.

imag. 2

imag. 3

<!-- p. 15 -->

14

Estudio de asoleamiento en el exterior

\1) Cargo la imagen del espacio a estudiar con el botón load image (imag 1 y 2)
\2) Tenemos que escalar la imagen para poder realizar un dibujo encima de ella.
La: escala se dará a través de una medida patrón. Se pulsan dos puntos y el programa
pedirá la distancia de la que se trata. (imag 3)

imag 1

imag 2 imag 1 imag 3

Para el estudio del asoleamiento de un espacio exterior lo
realizaremos mediante el comando add prismatic building.
Imag.4
Dibujamos el contorno de las dos viviendas linderas,
excepto sus aleros, que lo analizaremos posteriormente.
Al terminar de dibujar la primera vivienda, pulsamos
la letra E,

imag 5 imag 4
El programa nos pedirá la altura de la vivienda, le indicaremos 2.90mts. Y nos arrojará la
Sombra. imagen 5.

Procedemos de la misma manera con la
Segunda vivienda. imagen 1, de la
Siguiente Página.
A continuación dibujaremos los pilares que
Soportan los aleros, que también se realiza
Con el comando add prismatic building.
Imagen 2, de la siguiente Página

<!-- p. 16 -->

15

Hemos modificado el color de la
segunda vivienda para su mejor
compresión, que se realiza tecleando
el botón derecho del mouse encima
de la misma, seleccionando colorPara realización de los aleros se
procede de la misma forma que lo
visto anteriormente solo difiere que
pulsaremos el comando
add horizontal panel. Imagen 3

imag 1

imag 3 imag 2

Al terminar el trazado del mismo
pulsamos la letra E, el programa
nos preguntará a que altura esta el
parasol horizontal, imagen 4.

Cabe acotar que para el trazado del
alero activamos el comando wireframe
que lo que realiza es darnos la sombra
de la vivienda 1 en lineas, para facilitarnos
el dibujo del mismo, luego de trazado el
alero accionamos nuevamente el
comando darken shadow o imag 4
lighten shadow

Si deseamos también estudiar las sombras de imag 5
arboles, equipamiento urbano, etc, se puede realizar
semejando los mismos a una figura geómetrica,
nosotros realizaremos las de los arboles de la
vereda y del automovíl como ejemplo.

<!-- p. 17 -->

16

Arboles.

Se realizará su tronco, con el comando add prismatic building,
como lo hiciéramos anteriormente, imagen 1
Su follaje con el comando add room, dibujamos el contorno imag 1
que deseamos del mismo, al finalizar pulsamos la letra E y el
programa nos pedirá la nivel en el cual se sitúa el piso y su
altura imagen 2.

imag 2
Una vez accionado estos datos
nos arrojará la sombra. imagen3.
Los arbustos como empiezan en
el suelo lo realizaremos con el
comando add prismatic building.
Imagen 4

imag 3

imag 4
Automóvil:

Lo estudiaremos como algo anecdótico, para demostrar que se puede analizar cualquier
elemento, asemejando el mismo a volúmenes sencillos, para poder dibujarlo.

2
1 1 El automóvil se dibujará en dos partes.
1- la base, con el comando add prismatic building.
2
2-el remate, con el comando add room.

1

Estudio de sombras en Estudio de asoleamiento
el patio el 27sep/15mar del punto P en todo el año
a las 11:00 hrs
P
