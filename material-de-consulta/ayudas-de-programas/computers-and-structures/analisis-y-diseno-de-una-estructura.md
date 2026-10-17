---
type: libro
title: "Asignación de Secciones"
author: "Proyecto"
categoria: "AYUDAS DE PROGRAMAS"
paginas: 49
extraccion: "texto"
fuente: "local:E:/MATERIAL DE CONSULTA/AYUDAS DE PROGRAMAS/COMPUTERS AND STRUCTURES/Analisis y Diseño de una Estructura.pdf"
convertido: 2026-10-16
---

# Asignación de Secciones

> Texto extraído de `AYUDAS DE PROGRAMAS\COMPUTERS AND STRUCTURES\Analisis y Diseño de una Estructura.pdf` (49 páginas, texto). El PDF original está en el disco E: (MATERIAL DE CONSULTA); `<!-- p. N -->` marca el inicio de cada página.

<!-- p. 1 -->

1/1

Análisis y Diseño De Una Estructura

Usando el Programa SAP2000 V8.25

Curso SAP2000 V8
email: sap2000@cantv.net

<!-- p. 2 -->

2/2

Se procederá a modelar, analizar y diseñar la siguiente estructura:

La estructura consta de 2 niveles y será de perfiles estructurales HEA, la
losa entrepiso será de Concreto f’c = 280 Kgf/cm2. La losa del primer
nivel soportará una carga viva de 170 Kgf/m2 y el nivel superior de 100
Kgf/m2. A su vez cada losa soportará una sobre carga muerta de 50
Kgf/m2 debido a acabados e impermeabilización.

Curso SAP2000 V8
email: sap2000@cantv.net

<!-- p. 3 -->

3/3

Desde la pantalla principal del programa, inicie un nuevo modelo
haciendo clic en el menú File > New Model. Esto desplegará el menú
de plantillas del cual se indicará el sistema de unidades Kgf, m, C y
luego se escogerá Portal Frame.

A continuación indique las características geométricas del pórtico como
sigue:

Con esto obtendrá un pórtico plano, seleccione todos los elementos
entrando en el menú Select > Select > All. Ahora se procederá a
replicar dicho pórtico de acuerdo a la geometría del problema. Entre en
el menú Edit > Replicate e indique que la replica se hará de forma

Curso SAP2000 V8
email: sap2000@cantv.net

<!-- p. 4 -->

4/4

Lineal, El incremento será en el “eje y” con un valor de 3 metros, y la
cantidad de incrementos o replicas será igual a 1.

Ahora se creara un nuevo grillado para acceder a los elementos que se
han creado. Seleccione de nuevo todos los elementos como lo hizo
anteriormente y haga clic en el menú Edit > Add Grid At Selected
Points, indicando el “eje y“ para crear el grid. Luego en la ventana
derecha seleccione un plano XZ y ubíquese en Y=3 con los botones de
desplazamiento. En esta ventana dibuje una ventana para seleccionar
los elementos que forman la mitad del pórtico y repita el procedimiento
de replica cambiando el incremento a 3.5 metros. Obtendrá lo siguiente.

Curso SAP2000 V8
email: sap2000@cantv.net

<!-- p. 5 -->

5/5

Para dibujar los elementos restantes, haga clic en la herramienta de
dibujo de Frame / Cable de forma automática:

Y proceda a hacer clic en las líneas de grilla donde deberían ir las vigas
faltantes. Al finalizar esto, tendrá la geometría terminada y como sigue:

Curso SAP2000 V8
email: sap2000@cantv.net

<!-- p. 6 -->

6/6

Puede verificar la exactitud del modelo, haciendo clic en View > Set
Display Options y marcando la casilla Shade para mostrar los objetos
en tamaño real y con su sección asignada.

Ahora se procederá a asignar las condiciones de vinculación a tierra.
Haga clic en el botón XY para cambiar a dicho plano, y con los botones
de navegación vaya al plano Z=0. Seleccione todas las juntas y haga

Curso SAP2000 V8
email: sap2000@cantv.net

<!-- p. 7 -->

7/7

clic en el menú Assign > Joint > Restraints e indique el
Empotramiento.

Luego seleccione el Plano Z=3 y usando la herramienta de dibujo rápido
de Shells haga clic en los paños donde correspondan los shells.

Repita el mismo procedimiento para el nivel Z=6

Curso SAP2000 V8
email: sap2000@cantv.net

<!-- p. 8 -->

8/8

Ahora se deberán agregar dos diafragmas, uno por cada nivel,
seleccione todas las juntas del nivel Z=3 y haga clic en Assign > Joint
\> Constraints , como Constraint Type escoja Diaphragm y haga clic
en Add New Constraint y como nombre coloque D1.

Curso SAP2000 V8
email: sap2000@cantv.net

<!-- p. 9 -->

9/9

Repita el mismo procedimiento para el segundo nivel Z=6 y asigne un
diafragma D2.

Es necesario dividir los objetos de área (elementos finitos) para
discretizar correctamente las cargas., Para ello deben seleccionarse
todos los objetos de área (Shell) .

Los objetos de área pueden ser divididos en distintas partes según sea
necesario.

Para dividirlos debe realizarse el siguiente procedimiento: ir al menú
Select > Area Sections , de donde se observará la siguiente pantalla.

Curso SAP2000 V8
email: sap2000@cantv.net

<!-- p. 10 -->

10/10

Luego, se seleccionan las áreas a dividir. Una vez seleccionadas se debe
ir al menú Assign > Area > Automatic Area Mesh

Y elegir una de las dos formas posibles para esta opción, tal como se
muestra en la siguiente figura.

Curso SAP2000 V8
email: sap2000@cantv.net

<!-- p. 11 -->

11/11

Se selecciona una división uniforme de elementos finitos en 6 x 6 para
lograr buenos resultados…

Curso SAP2000 V8
email: sap2000@cantv.net

<!-- p. 12 -->

12/12

Definición de Materiales y Secciones.

Entre en el menú Define > Materiales, selección el material STEEL y
haga en clic en Modify/Show Material verifique las propiedades
siguientes correspondientes al acero ASTM A-36.

Ahora se importarán las secciones de los elementos del archivo
Euro.pro, haga clic en el menú Define > Frame/Cable Sections luego
haga clic en Import I/Wide Flange y luego en Modify/Show
Property.

Curso SAP2000 V8
email: sap2000@cantv.net

<!-- p. 13 -->

13/13

Se abrirá un cuadro de dialogo para que ubique el archivo Euro.pro que
debe estar en el mismo directorio en el que está instalado el programa.
Luego de ubicar el archivo seleccione los perfiles HEA de la lista que se
desplegará a continuación.

Curso SAP2000 V8
email: sap2000@cantv.net

<!-- p. 14 -->

14/14

Ahora se creará una Sección de Selección Automática para que
programa escoja la mejor opción de ese grupo de perfiles. Entrando en
el menú de definición de secciones, Haga clic en el menú desplegable
Add I/Wide Flange y seleccione de la lista Add Auto Select y haga
clic en Add New Property La lista de la izquierda indica todas las
secciones que se han cargado en el modelo hasta el momento, de dicha
lista seleccione los perfiles HEA que acaba de importar y haga clic en el
botón Add -> para agregarlas a la lista de auto selección.

Ahora se definirá la sección de la losa. Para esto haga clic en el menú
Define > Area Sections, luego en el botón Add New Section. Como
nombre coloque LOSA, en material CONC, como espesores de
Membrana y de Flexión indique 0,25 metros y como tipo de Losa
seleccione Shell.

Curso SAP2000 V8
email: sap2000@cantv.net

<!-- p. 15 -->

15/15

Asignación de Secciones

Para asignar la Sección de Selección Automática, seleccione todos los
elementos del modelo, y luego haga clic en el menú Assign >
Frame/Cable > Sections, seleccione la Sección AUTO1 y haga clic en
Ok.

Curso SAP2000 V8
email: sap2000@cantv.net

<!-- p. 16 -->

16/16

Vuelva a seleccionar todos los elementos, haga clic en Assign > Area >
Sections y asigne la sección LOSA.

Definición de Casos de Carga, Combinaciones y Asignación de
Cargas

Para definir los casos de Carga haga clic en el menú Define > Load
Cases, en esta ventana se indicaran los 3 casos de Carga, CP, CV y
SCM. Solo CP llevara el factor de peso propio igual a 1 ya que
corresponderá al peso propio de la estructura, CV corresponderá a
Carga Viva y SCM a la sobrecarga debido a impermeabilización,
acabados, etc.

Curso SAP2000 V8
email: sap2000@cantv.net

<!-- p. 17 -->

17/17

Para definir las combinaciones haga clic en Define > Combinations y
haga clic en Add New Combo. Luego se seleccionaran los casos de
carga, sus factores de amplificación y se agregaran al combo para
obtener lo siguiente:

Para asignar la carga, seleccione todos los Shells del nivel Z=3 y haga
clic en Assign > Area Loads > Uniform (Shell) y seleccione del
menú el caso de carga Viva y como valor coloque 170

Curso SAP2000 V8
email: sap2000@cantv.net

<!-- p. 18 -->

18/18

Repita el mismo procedimiento indicando como caso de carga SCM y un
valor de 50. Para los Shell del Nivel Z=6 indique un valor de CV de 100
y 50 para SCM.

Ahora se procederá a ejecutar el análisis de la estructura de la siguiente
manera. Haga clic en Analyze > Run Analysis.

Curso SAP2000 V8
email: sap2000@cantv.net

<!-- p. 19 -->

19/19

En este menú podrá escoger los casos de análisis que desee correr, para
el ejemplo se correrán todos haciendo clic en el botón Run Now. El
programa realizará el análisis y le mostrará el Primer Periodo de
Vibración. Seleccione la ventana derecha y haga clic en Display >
Show Deformed Shape ahí escoja el Caso de Carga DEAD y seleccione
la casilla Wire Shadow, (para mostrar la estructura antes de la
deformación)

Curso SAP2000 V8
email: sap2000@cantv.net

<!-- p. 20 -->

20/20

Se obtendrá lo siguiente:

Curso SAP2000 V8
email: sap2000@cantv.net

<!-- p. 21 -->

21/21

Para obtener el desplazamiento y la rotación de cualquier nodo de la
estructura haga clic con el botón derecho sobre el nodo en cuestión.

Curso SAP2000 V8
email: sap2000@cantv.net

<!-- p. 22 -->

22/22

Para mostrar los diagramas, seleccione un plano YZ o XZ de acuerdo al
pórtico que desee observar y haga clic en Display > Show
Forces/Stresses > Frames / Cables.

Curso SAP2000 V8
email: sap2000@cantv.net

<!-- p. 23 -->

23/23

Seleccione Shear 2-2 para observar el Corte 2-2 y como Case/Combo
seleccione COMB1.

Curso SAP2000 V8
email: sap2000@cantv.net

<!-- p. 24 -->

24/24

Para observar el diagrama de momentos 3-3 repita el mismo
procedimiento.

Curso SAP2000 V8
email: sap2000@cantv.net

<!-- p. 25 -->

25/25

Si desea saber los valores, haga clic sobre cualquier elemento con el
botón derecho y obtendrá los valores de Fuerza Axial, Corte, Momento y
Deflexión.

Curso SAP2000 V8
email: sap2000@cantv.net

<!-- p. 26 -->

26/26

Para obtener las reacciones haga clic en Display > Show
Foreces/Stresses > Joints y luego escoja la combinación
correspondiente y haga clic en OK

Curso SAP2000 V8
email: sap2000@cantv.net

<!-- p. 27 -->

27/27

Para observar los datos en forma de Tabla haga clic en Display > Show
Análisis Result Tables y seleccione los datos que desee obtener.

Curso SAP2000 V8
email: sap2000@cantv.net

<!-- p. 28 -->

28/28

Obtendrá las tablas con los valores:

Para exportar esta tabla de valores a Excel o Access haga clic en File >
Export Current Table > To Excel y le reportara los valores en Excel.

Curso SAP2000 V8
email: sap2000@cantv.net

<!-- p. 29 -->

29/29

Antes de proceder al diseño de los elemento haga clic en Options >
Preferences > Steel Frame Design y seleccione en Design Code
AISC-LRFD.

Curso SAP2000 V8
email: sap2000@cantv.net

<!-- p. 30 -->

30/30

Para proceder al diseño haga clic en Design > Steel Frame Design >
Start Design/Check of Structure. Una vez culminado el análisis
obtendrá los perfiles o los valores de iteración de acuerdo a como este
predefinido en su programa.

Curso SAP2000 V8
email: sap2000@cantv.net

<!-- p. 31 -->

31/31

Para observar los valores de iteración haga clic en Design > Steel
Frame Design > Display Design Info y seleccione en Design Input
el item Design Sections. Haga clic con el botón derecho sobre
cualquier elemento y obtendrá el resumen de reporte de diseño del
elemento:

Curso SAP2000 V8
email: sap2000@cantv.net

<!-- p. 32 -->

32/32

Para ver los detalles haga clic en Details.

Como se observa la sección de diseño no es igual a la sección de análisis
por lo que se deberá repetir el proceso de Análisis / Diseño hasta que
ambas sean igual, para verificar que ambas son iguales debe hacer clic
en Design > Steel Frame Design > Verify Analysis Vs. Design
Sections. Cuando obtenga el siguiente mensaje, su análisis y diseño
estarán completados.

Curso SAP2000 V8
email: sap2000@cantv.net

<!-- p. 33 -->

33/33

Y las secciones resultantes:

Curso SAP2000 V8
email: sap2000@cantv.net

<!-- p. 34 -->

34/34

ANALISIS DINAMICO

Para realizar el análisis dinámico es necesario definir el espectro de
diseño.

Para introducir un espectro de diseño se debe accesar al menú Define
\> funtion > Response spectrum , tal como se muestra en la figura.

Al entrar se desplegará una pantalla donde se podrá elegir el espectro a
utilizar para el análisis…

Curso SAP2000 V8
email: sap2000@cantv.net

<!-- p. 35 -->

35/35

Es posible elegir cualquiera de los espectros de las normas aquí
preestablecidas, o bién, se puede importar un espectro.txt previamente
configurado por el usuario (Covenin)

Elegimos el espectro de la UBC97 y se selecciona la etiqueta Add New
Function, luego, se deplegará la siguiente forma…

Curso SAP2000 V8
email: sap2000@cantv.net

<!-- p. 36 -->

36/36

En la ventana superior se puede colocar un nombre para identificarlo en
el modelo.

Luego de identificado el espectro, se selecciona OK para volver a la
pantalla anterior, y una vez allí, se selecciona otra vez Ok para retornar
a la pantalla principal.

Ya definido el espectro se procede a realizar los casos de análisis, para
lo cual se debe ir al menú Define > Analisis Cases , tal como se
muestra a continuación …

Curso SAP2000 V8
email: sap2000@cantv.net

<!-- p. 37 -->

37/37

luego de seleccionar la opción Analisis cases, se obtiene la siguiente
pantalla …

Curso SAP2000 V8
email: sap2000@cantv.net

<!-- p. 38 -->

38/38

En ella se observan cada uno de los casos definidos anteriormente. Para
definir los casos sísmicos debe realizarse el siguiente procedimiento
descrito a continuación.

Curso SAP2000 V8
email: sap2000@cantv.net

<!-- p. 39 -->

39/39

Curso SAP2000 V8
email: sap2000@cantv.net

<!-- p. 40 -->

40/40

Es necesario indicar el factor de escala a utilizar para el espectro. En
algunos casos la aceleración viene expresada en función de la gravedad,
por lo que debe multiplicarse por la misma a fin de obtener resultados
correctos.

Curso SAP2000 V8
email: sap2000@cantv.net

<!-- p. 41 -->

41/41

Una vez definidos los casos sísmicos , se puede establecer el número de
modos a considerar para el análisis de la estructura, siguiendo el
procedimiento descrito a continuación.

Curso SAP2000 V8
email: sap2000@cantv.net

<!-- p. 42 -->

42/42

Curso SAP2000 V8
email: sap2000@cantv.net

<!-- p. 43 -->

43/43

En esta pantalla se puede editar el número mínimo y máximo de modos
a considerar en el análisis (Number of modes)

Una vez definidos cada uno de los casos sísmicos y los modos de
vibración a considerar , es necesario definir la masa de la estructura en
los distintos niveles, para ello debe realizarse el siguiente
procedimiento…

Curso SAP2000 V8
email: sap2000@cantv.net

<!-- p. 44 -->

44/44

Curso SAP2000 V8
email: sap2000@cantv.net

<!-- p. 45 -->

45/45

Es necesario colocar un factor de multiplicación para cada uno de los
casos de cargas definidos anteriormente. Esta función lo que hace es
transformar las cargas a masa incluyendo su peso propio.

Curso SAP2000 V8
email: sap2000@cantv.net

<!-- p. 46 -->

46/46

Al correr la estructura se pueden observar cada uno de los modos de
vibración de la misma uilizando el menú Display > Show deformed
shape

Los resultados también pueden obtenerse en tablas siguiendo el
procedimiento descrito a continuación.

Curso SAP2000 V8
email: sap2000@cantv.net

<!-- p. 47 -->

47/47

Curso SAP2000 V8
email: sap2000@cantv.net

<!-- p. 48 -->

48/48

En esta pantalla se eligen cada uno de los resultados del análisis para
ser revisados en tablas, considerando la carga sísmica.

Curso SAP2000 V8
email: sap2000@cantv.net

<!-- p. 49 -->

49/49

Curso SAP2000 V8
email: sap2000@cantv.net
