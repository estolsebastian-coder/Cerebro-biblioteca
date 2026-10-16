---
type: libro
title: "TIPS SAP2000"
author: "Traducido por Ing. Hossmar Guevara"
categoria: "AYUDAS DE PROGRAMAS"
paginas: 7
extraccion: "texto"
fuente: "local:E:/MATERIAL DE CONSULTA/AYUDAS DE PROGRAMAS/COMPUTERS AND STRUCTURES/Tips SAP2000 v8.pdf"
convertido: 2026-10-16
---

# TIPS SAP2000

> Texto extraído de `AYUDAS DE PROGRAMAS\COMPUTERS AND STRUCTURES\Tips SAP2000 v8.pdf` (7 páginas, texto). El PDF original está en el disco E: (MATERIAL DE CONSULTA); `<!-- p. N -->` marca el inicio de cada página.

<!-- p. 1 -->

TIPS SAP2000 V8
Ing. Hossmar Guevara, Ing. Oscar Bedoya, Ing. Eliud Hernández

• Un elemento de concreto es diseñado como viga o columna dependiendo de como fue
designada su propiedad de sección cuando fue definida usando el menú Define >
Frame Sections.

• Usted puede usar el menú File > Display Input/Output Text Files para ver los
archivos de texto de entrada y salida creados por SAP2000. Los archivos son abiertos
en el wordpad que viene con Windows.

• Puede animar las formas deformadas y las formas modales en perspectiva 3D
simplemente haciendo clic en el botón Start Animation ubicado en la barra de status.

• Usted puede automáticamente generar un elemento Shell haciendo un clic en la grilla
de trabajo y luego subdividirlo en elementos mas finos, si es necesario, con simples
parámetros disponibles en el menú Edit.

• Usted puede subdividir grandes Shells a lo largo de líneas definidas por el usuario.

• Puede mostrar información acerca de una junta o elemento apuntando a el y
haciendo clic con el botón derecho del mouse.

• La capacidad de Replica del SAP2000 permite replicar de manera lineal, cilíndrica y
de espejo porciones seleccionadas del modelo. La Replica copia las propiedades de
los elementos cuando los mismos son copiados.

• Las juntas pueden ser pegadas a las líneas de grilla usando el menú Draw > Edit
Grid. Mover las las líneas de grillas con las las juntas pegadas a las grillas modifica la
ubicación de todas las juntas en esa línea de grilla y acorta o alarga todos los
elementos conectados a esas juntas.

• Usted puede hacer doble clic en una línea de grilla para abrir un cuadro de dialogo
que le permitirá edita la ubicación de la línea de grilla.

• Mientras que las líneas de grillas estén desbloqueadas (Edit > Lock Grid) usted puede
ir al menú Draw > Reshape Element y arrastrar y soltar líneas de grilla en la pantalla
a nuevas ubicaciones.

• Usted puede agregar una nueva línea de grillas haciendo clic en Draw > Reshape
Element y luego sosteniendo la tecla CTRL de su teclado, haciendo clic en una línea
de grilla existente y arrastrando su duplicado.

• Haciendo clic en una vista mientras presiona la tecla CTRL de su teclado le da una
lista de los elementos dentro del rango de tolerancia de su clic.

<!-- p. 2 -->

• Usted puede producir extrusiones de perspectiva a escala de las secciones
estructurales simplemente activando la opción 'Show Extrusions' en el menú View >
Set Elements.

• Usted puede copiar una región tridimensional seleccionada de su modelo al
Portapapeles y luego pegarla en cualquier ubicación en el espacio 3D.

• Puede cambiar de unidades en cualquier momento durante la creación de su modelo
o cuando vea los resultados.

• Cuando dibuja elementos Shell en una elevación en particular los ejes del elemento
son alineados automáticamente para una interpretación conveniente de la salida.

• En SAP2000 usted solo dibuja / define elementos. Todas las juntas necesitadas por
los elementos son automáticamente generadas. No se necesita una predefinición de
las juntas.

• Típicamente, múltiples juntas que compartan la misma ubicación el espacio 3D son
automáticamente unidas.

• Restricciones internas de las juntas pueden usarse para definir diafragmas rígidos y
vínculos rígidos que conectan todos los tipos de elementos.

• Mientras dibuja una seria de elementos como vigas y columnas, un doble clic, clic
derecho o 'Enter' terminar la serie. 'Escape' terminara la modalidad de dibujo.

• Usted puede definir cortes de sección a través de elementos Shell como un grupo y
luego usar el menú Display > Show Group Joint Force Sums para obtener los
resultados de las fuerzas y momentos derivados de la esfuerzos integrados sobre el
shell

• Cuando trabaja en un modelo cilíndrico en un sistema de coordenadas cilíndrico una
vista T-Z muestra una elevación del cilindro.

• Usando el menú View > Set 2D View usted puede seleccionar una elevación en 2D
haciendo clic en una junta que este en el plano deseado 2D en el cuadro de diálogos
Set 2D View.

• Usted puede definir un nuevo sistema de coordenadas haciendo clic en Define >
Coordinate System/Grid.

• Usted puede importar la geometría de Elementos y Shells usando el menú File >
Import > .DXF

• Usted puede exportar la geometría de Elementos y Shells usando el menú File >
Export > .DXF

<!-- p. 3 -->

• Usted puede imprimir data de entrada, y resultados de análisis y diseño del menú
File y también de otras formas que reportan información.

• El menú Edit > Replicate es una poderosa manera de generar su modelo.

• Usando los comandos Set Limits, Set Elements y Show Selection Only del menú View
puede reducir el numero de elementos que son visibles en la pantalla.

• Usted puede automáticamente renumerar juntas seleccionadas, elementos y Shells
usando el menú Edit > Change Labels

• Usted puede comenzar un nuevo esquema de enumeración para los elementos que
falten por dibujar haciendo clic en Draw > New Labels.

• Usted puede seleccionar elementos por etiqueta usando el menú Select.

• Usar Grupos puedes hacer mas rápida la selección de elementos.

• Usar líneas de grilla puede hacer mas fácil editar y ver su modelo.

• Usar restricciones internas de juntas reduce el numero de grados de libertad en su
modelo lo que puede hacer que le análisis corra mas rápido.

• Para diseño en concreto usted no debe olvidar definir la sección del elemento como
viga o columna usando en menú Define > Frame Sections.

• Siempre debe intentar ubicar sus juntas en intersecciones de grillas. Colocando
grillas usted logra entradas, modificaciones y vistas de su modelo mucho mas fácil y
rápido.

• Usted puede siempre ver en la barra de status que tipos de elementos y cuantos de
ellos han sido seleccionados.

• Usted puede usar las lista de Auto selección de secciones para optimizar su diseño en
acero.

• Coloque el puntero del mouse sobre un botón de las barras de herramientas y en
unos segundos aparecerá una caja describiendo la función del botón.

• Usted puede hacer zoom rápidamente en un modelo muy grande y complejo usando
la vista aérea.

• En SAP2000 usted puede trabajar en de una a cuatro ventanas. Usualmente una
ventana o dos ubicadas verticalmente es la mejor manera. Usted puede decidir el
numero de ventanas en el menú Options > Windows.

• Los colores de la interfaz grafica pueden ser cambiados a su gusto usando el menú
Options > Colors.

<!-- p. 4 -->

• El tamaño mínimo y máximo de las letras en las ventanas de SAP2000 pueden ser
modificados usando el menú Options > Preferences (Dimmensions)

• SAP2000 ofrece la capacidad 'Undo' que trabaja con múltiples pasos hacia atrás
hasta la ultimas vez que usted salvó su modelo.

• Para ayudarse a dibujar objetos en su modelo de manera exacta use las opciones de
Referenciado que ofrece SAP2000.

• Cuando este creando su modelo, trabaje en vistas de plantas y elevaciones mientras
le sea posible. Es mucho mas fácil trabajar en esa vistas 2D que en una vista 3D.

• Cuando use listas de auto selección de sección para sus elementos trate de no
colocar todas las posibles secciones de acero en la lista. Mantener la lista corta, de
20 a 30 secciones, aumentara significativamente la velocidad de diseño.

• Revise cuidadosamente los resultados de salida para asegurarse que su modelo se
esta comportando como lo esperaba. Si no lo hace, investigue porque.

• Cuando exporta una vista plana a un archivo .DXF todos los items que van a ser
exportados deben ser visibles en la ventana de vista plana activa.

• Usted puede crear videos de las respuestas en función del tiempo (como archivos
.AVI) y luego reproducirlos usando el media player que viene con Windows.

• Usted puede editar la geometría del modelo en una hoja de cálculo y luego copiarla y
pegarla en SAP2000

• En SAP2000 usted puede tener sistemas de grillas / coordenadas Cartesiano y/o
cilíndricos.

• Usted puede seleccionar mas de una sección de elementos a la vez en la lista Section
Selection, cuando este agregando Secciones de Elementos, sosteniendo la tecla CTRL
o SHIFT mientras hace la selección.

• Cuando este asignando cargas a un elemento, debe estar seguro que esta agregando
cargas al caso de cargas que usted quiere.

• Una vez que el análisis de su modelo haya terminado, usted debe revisar todos los
resultados en pantalla antes de presionar OK. Este es el primer chequeo para
asegurarse de que no hubo problemas con su modelo.

• Las listas de Auto Selección de secciones solo funcionan para secciones de elementos
de acero/aluminio/formados en frió.

• Usted no puede borrar una propiedad de sección que este asignada a un elemento.
Esto es una manera de asegurar que todos los miembros se diseñen con secciones
existentes.

<!-- p. 5 -->

• Si usted quiere chequear el diseño para un numero limitado de elementos, puede
seleccionar esos elementos y luego escoger Start Design/Check of Structure.

• Usted puede cambiar el numero de locaciones en las cuales se reportaran las fuerzas
en los miembros. Para hacer esto seleccione el elemento, y haga clic en el menú
Assign > Frame > Output Segments.

• Cuando use desplazamientos de extremos, los valores de corte y momento serán
ligeramente diferentes que con desplazamientos de extremos no rígidos. Esto es
debido a que la asignación de desplazamientos de extremos rígido reduce la longitud
flexible del miembro.

• Las especificaciones hechas usando el menú View > Set Elements solo afecta la
ventana actualmente activa.

• Mostrar las secciones en su tamaño real (Extrusion) es una manera conveniente de
chequear la orientación de los ejes locales de los elementos.

• Usted puede especificar propiedades de materiales isotrópicos u ortotrópicos en
SAP2000

• Varias bases de datos de secciones de acero son incluidas en SAP2000. Usted
también puede crear sus propias bases de datos de secciones.

• Usted puede usar el menú Assign > Frame > Sections para simultáneamente definir
secciones de elementos y asignarlas al elemento seleccionado.

• Usted puede especificar información de refuerzo para vigas rectangulares, "Te", "Ele"
y para columnas rectangulares y circulares de concreto.

• Usted puede usar el menú Assign > Shell > Sections para simultáneamente definir
secciones de Shells y asignarlas al Shell seleccionado.

• En SAP2000 los valores de aceleración en una función de espectros de respuesta se
asumen como normalizadas, es decir, se asume que la función no tiene unidades.

• Use el método de línea de intersección en una vista de perspectiva para seleccionar
todas las columnas en un mismo piso.

• Cuando este listo para crear un nuevo modelo, lo primero que debe hacer es escoger
las unidades en la lista ubicada a su mano derecha en la barra de status.

• Desplazamientos de extremos rígidos a lo largo de la longitud del elemento son
contados para el tamaño finito de las intersecciones de vigas y columnas.

• SAP2000 muestra las fuerzas en la cara interna de los desplazamientos de extremos
de los miembros.

<!-- p. 6 -->

• Las cargas distribuidas asignadas a un elemento pueden ser uniformes, no uniformes
(trapezoidales) y pueden ser de la longitud completa del elemento o de una longitud
parcial.

• La dirección gravitacional para las cargas es hacia abajo en la dirección global
negativa Z.

• Las asignaciones hechas a un grupo existente remplazan lo que esta en el grupo. No
se agregan. Si usted quiere agregar a un grupo existente, primero seleccione el
grupo, luego el objeto que quiere asignar al grupo y finalmente haga la asignación.

• Si usted esta corriendo un análisis de espectro de respuesta o de dominio del tiempo,
se recomienda que use vectores Ritz. Es especialmente importante que use vectores
Ritz cuando haga un análisis no lineal de dominio del tiempo.

• Cuando se muestran las fuerzas en los elementos del modelo usted puede hacer clic
con el botón derecho de cualquier elemento para obtener una ventana donde puede
mover el puntero del mouse sobre el elemento y ver los valores de fuerza en
cualquier ubicación.

• Cuando se muestran las fuerzas en los Shells del modelo usted puede hacer clic con
el botón derecho de cualquier Shell para obtener una ventana donde puede mover el
puntero del mouse sobre el elemento y ver los valores de fuerza en cualquier
ubicación.

• Las fuerzas internas de los Shells son reportadas en la superficie media del elemento
en unidades de fuerza por longitud. Los esfuerzos internos de los shells son
reportados tanto en la parte superior como inferior del elemento en unidades de
fuerza por área.

• El menú Display > Show Energy Diagram sirve como ayuda para que determine
cuales elementos deben ser rigidizados para controlar mas eficientemente los
desplazamientos laterales de su estructura.

• La tolerancia de auto unión (menú Options > Preferences) es usado internamente por
SAP2000 para determinar cuando dos juntas están en la misma ubicación.
• No haga su margen de paneo muy grande. Consumirá toda la memoria de su
computador. El valor por definición de 50% es normalmente adecuado.

• En SAP2000 en eje Z es siempre vertical, con +Z siendo hacia arriba.

• La regla de la mano derecha aplica a todos los sistemas de coordenadas en SAP2000

• Todos los sistemas de coordenadas adicionales y los sistema de coordenadas locales
de los elementos son definidos con respecto al sistema de coordenadas global.

• Use el menú Options > Set Coordinate System para definir un nuevo sistema de
coordenadas.

<!-- p. 7 -->

• Si usted quiere ver una rampa o un techo inclinado en una vista plana use el menú
Options > Set Coordinate System para definir un nuevo sistema de coordenadas tal
que la rampa o el techo quede en el plano 'XY" del nuevo sistema de coordenadas.

• Para hacer una asignación a un objeto primero seleccione el objeto y luego haga clic
en el comando apropiado del menú Assign.

• Los tipos de diseño son especificados para cada caso de carga usando el menú Define
\> Static Load Cases. Ellos son usados por el postprocesador de diseño de SAP2000
para crear la combinación de cargas apropiada para el diseño.

• No hay limite para el numero de casos o combinaciones de cargas que usted pueda
crear en SAP2000.

• Típicamente para obtener un buen comportamiento de flexión de placas usted debe
tener cuatro o mas elementos entre cada junta de soporte.

• Existen dos tipos de análisis modal en SAP2000, análisis por autovectores y análisis
por vectores Ritz.

• En SAP2000 usted puede considerar modos de masas residuales en sus análisis
modales.

• La opción de P-Delta en SAP2000 es útil para considerar el efecto de cargas
gravitacionales sobre la rigidez lateral de estructuras aporticadas, como es requerido
por ciertos códigos.

• Las fuerzas internas de los miembros son reportadas en las estaciones de salida a lo
largo de la longitud del elemento.

• Usted puede imprimir tablas de datos de salidas para objetos seleccionados si así lo
desea. Usted puede imprimir la data en la impresora o a un archivo de texto.
