---
type: libro
title: "Sap2000-estruc.Acero2"
author: ""
categoria: "AYUDAS DE PROGRAMAS"
paginas: 11
extraccion: "texto"
fuente: "local:E:/MATERIAL DE CONSULTA/AYUDAS DE PROGRAMAS/COMPUTERS AND STRUCTURES/Sap2000-estruc.Acero2.pdf"
convertido: 2026-10-16
---

# Sap2000-estruc.Acero2

> Texto extraído de `AYUDAS DE PROGRAMAS\COMPUTERS AND STRUCTURES\Sap2000-estruc.Acero2.pdf` (11 páginas, texto). El PDF original está en el disco E: (MATERIAL DE CONSULTA); `<!-- p. N -->` marca el inicio de cada página.

<!-- p. 1 -->

ING. EDUARDO RIVERA REYES
CONSULTOR DE PUENTES Página Web: www.puentesrivera.es.fm

ANALISIS DE ESTRUCTURA DE CRUJIAS DE ACERO

Edificio de acero estructural A-36 de 3 pisos de 3 crujías con arriostres en cada piso.

Masas 1 er Techo 10.97 Ton-s2/m
2 do Techo 10.91 Ton-s2/m
3 er Techo 6.41 Ton-s2/m

Metrado de cargas

Espectro de Aceleraciones

T Sa
0.01 1.177
0.60 1.177
0.70 0.971
0.80 0.824
1.00 0.618
1.20 0.491
1.40 0.412
1.60 0.343
1.80 0.294
2.00 0.265
2.50 0.196
3.00 0.157

SOLUCION.-

1.- Modelación en el programa de computo SAP2000. Se verifican las unidades en que se
introducirá la estructura (dimensiones, cargas) Ton-m.

2.- Se busca un modelo predeterminado en el menú principal
FILE – NEW MODEL FROM TEMPLATE (Base de
datos del programa) se hace clic en Space Frame, tipear el
ingreso de datos, (a) número de pisos 3, (b) número de pórticos
en dirección en el eje X 2, (c) número de pórticos en
dirección en el eje Y 1, (d) altura de piso 3m., (e) separación
entre espacios de columnas en dirección X 7m., (f)

separación entre espacios de columnas en dirección Y 8m.

E-mail: erivera@terra.com.pe Telefax: 226-1435 - Lima Perú
www.puentesrivera.es.fm

<!-- p. 2 -->

ING. EDUARDO RIVERA REYES
CONSULTOR DE PUENTES Página Web: www.puentesrivera.es.fm

3.- Ingresar arriostres a la estructura seleccionar 2 puntos

como referencia. Luego seleccionar el elemento
En el menú principal Assign - Frame - Releases check
en los casilleros de Start y End Moment 22 (major)
y Moment 33 (major) luego click OK.

4.- Ingreso de propiedades de los materiales a usarse como: MASA (Si se quiere considerar la
masa del elemento para el análisis y diseño) DENSIDAD, MODULO DE ELASTICIDAD,

RADIO DE POISSON, en el menú principal se hará en menú principal

Define – Materials.

Mass = 0.00 kg/cm2
Weight = 7.83x10-3 kg/cm2

Modulo de elasticidad = 2038902 kg/cm2
Modulo poisson = 0.3

F´y = 2531 kg/cm2

5.- Selección de secciones se busca en el menú principal Define –
Frame Sections, Import / Wide Flange selección de
perfiles W, Add AutoSelection Sections en el recuadro

en blanco, tipear COL seleccionar perfiles de W14x120

para las columnas, click OK 2 veces.
Add AutoSelection Sections en el recuadro en blanco,

tipear VIGA seleccionar perfiles de W21 x 68 para las

vigas, click OK 2 veces.

E-mail: erivera@terra.com.pe Telefax: 226-1435 - Lima Perú
www.puentesrivera.es.fm

<!-- p. 3 -->

ING. EDUARDO RIVERA REYES
CONSULTOR DE PUENTES Página Web: www.puentesrivera.es.fm

Import Channel selección de perfiles de canales C, luego Add AutoSelection Sections en

el recuadro en blanco se tipea BRACE seleccionar perfiles de W10 x 20 para los

brace, click OK 2 veces.

6.- Definir los casos de cargas propias, muertas y vivas, que se tendrán en la estructura, en el
menu principal se seleciona Define - Static Load Cases (a) se tipea la clase de carga que va

ha definir, (b) se define en el cuadro extendible la clase de carga que se aplicará, (c) se tipea
en Self Weight Multiplier 1 para considerar las cargas por peso propio en ésta selección, ó 0

para no tomar en cuenta en la carga definida el peso cuando se define en el peso propio. Se
adiciona la carga viva CV se tipea 0 en el casillero en blanco.

7.- Ingreso de Espectro de diseño de estructura con el Periodo Vs. Magnitud FUNC1.En el menú
principal se escoge Define – Response Spectrum Functions – Add New Function. En el
casillero de Time se tipea el periodo de la estructura, seguido de su magnitud.

E-mail: erivera@terra.com.pe Telefax: 226-1435 - Lima Perú
www.puentesrivera.es.fm

<!-- p. 4 -->

ING. EDUARDO RIVERA REYES
CONSULTOR DE PUENTES Página Web: www.puentesrivera.es.fm

8.- Definir casos de respuesta de espectro. Para escoger los casos de respuesta se selecciona del
menú principal Define – Response Spectrum Cases – Add New Spectra. Se introduce en
Damping para estructuras de concreto Armado es de 0.05 en la ventana de respuesta de
espectro se selecciona en la ventana de respuesta de espectro FUNC1 para la dirección U1 y

se repite para la dirección U2 e U3.

9.- Asignar propiedades a los elementos de la estructura Para asignar cualquier propiedad,

fuerza (puntual o distribuida), carga a los elementos o nudo de la estructura, previamente se

tiene que seleccionarlo o marcarlo cada elemento.

10.- Asignar las restricciones por traslación y rotación de los nudos de los elementos en la base,
en el menú principal Assign - Joint - Restraints o con el icono de la barra de herramientas

E-mail: erivera@terra.com.pe Telefax: 226-1435 - Lima Perú
www.puentesrivera.es.fm

<!-- p. 5 -->

ING. EDUARDO RIVERA REYES
CONSULTOR DE PUENTES Página Web: www.puentesrivera.es.fm

11.- Se crea un nudo maestro donde se concentrará las masas de los pisos en centro de gravedad
de la estructura. Menú principal Draw - Add Special Joint o con el icono de la barra de

herramientas

12.- Asignar la masa de cada piso en el menú principalASSIGN - JOINT - MASSES al nudo

maestro del piso superior de la estructura, ingresando en el sentido donde va ha actuar X

(Direction 1) 6.41 e Y (Direction 2) 6.41 y el momento de inercia rotacional de las masas
en la dirección Z (Rotation about 3) 138.88, y en los pisos inferiores en dirección 1 (10.97),

en dirección 2 (10.97) y el momento rotacional de la s masas en (Rotacion About 3) 237.69.

13.- Se restringir los nudos de los elementos por piso para que se desplacen juntos con la opción
en el menú principal Assign - Joint - Constraints – Diaphragm para cada piso se asigna
un diafragma diferente. Nos ubicamos en el último piso Add Diaphragm, en el casillero
en blanco se tipea DIAPH1 y se hace click 2 veces y repite para cada piso.

E-mail: erivera@terra.com.pe Telefax: 226-1435 - Lima Perú
www.puentesrivera.es.fm

<!-- p. 6 -->

ING. EDUARDO RIVERA REYES
CONSULTOR DE PUENTES Página Web: www.puentesrivera.es.fm

14.- Asignar secciones a los elementos estructurales, seleccionar los muros representados
por elementos frame. En el Menú principal ASSIGN – FRAME - SECTIONS, click name

seleccionar muro definido, repetir procedimiento para selecionar todos los muros.

15.- Asignar la cantidad de segmentos de salida que se tendrá en cuenta en el momento del
análisis. En el menu principal ASSIGN – FRAME – OUTPUT SEGMENTS

16.- Visualizar estructura con las propiedades de la secciones

VIEW – SET ELEMENTS – CHECK SHOW EXTRUSIONS

E-mail: erivera@terra.com.pe Telefax: 226-1435 - Lima Perú
www.puentesrivera.es.fm

<!-- p. 7 -->

ING. EDUARDO RIVERA REYES
CONSULTOR DE PUENTES Página Web: www.puentesrivera.es.fm

17.- Se ingresa las combinaciones de cargas que influyerán en el diseño en el menú principal . La
primera combinación DEFINE - LOAD COMBINATIONS - ADD NEW COMB se

ingresa la combinación de 1.4 CM, se tipea 1.4 en el casillero en blanco y se selecciona la
carga del cuadro extendible Case Number, check en Use for Steel Design.

18.- Ingresar opciones de análisis, estructura en el espacio o en el plano, número de modos de

vibración. En el menú principal ANALYZE – SET OPTIONS – SET DYNAMIC
PARAMETERS.

E-mail: erivera@terra.com.pe Telefax: 226-1435 - Lima Perú
www.puentesrivera.es.fm

<!-- p. 8 -->

ING. EDUARDO RIVERA REYES
CONSULTOR DE PUENTES Página Web: www.puentesrivera.es.fm

19.- Analizar Estructura Modelada Con Sus Repectivas Seciones (Analyze)

Ingresar opciones de analisis, estructura en el espacio o en el plano, número de modos de
vibración en el menú principal ANALYZE – SET OPTIONS – CHECK SET DYNAMIC
PARAMETERS colocar en el primer casillero Number of Modes 9.

20.- Revisar los resultados obtenidos del análisis, desplazamientos de la estructura.
En el menú principal DISPLAY – DEFORMED SHAPE o con la opción en la barra de

herramientas

21.- Visualizar las formas de modo de vibración de la estructura.
En el menú principal DISPLAY – SHOW MODE SHAPE o con la opción grafica de

E-mail: erivera@terra.com.pe Telefax: 226-1435 - Lima Perú
www.puentesrivera.es.fm

<!-- p. 9 -->

ING. EDUARDO RIVERA REYES
CONSULTOR DE PUENTES Página Web: www.puentesrivera.es.fm

22.- Visualizar fuerzas y esfuerzos en los elementos
En el menú principal DISPLAY – SHOW ELEMENT FORCES/STRESSES

23.- Revisar tablas de resultados para cada elemento
En el menú principal DISPLAY – SET OUTPUT TABLE MODE permite ver las

fuerzas cortantes en la estructura y los momentos actuantes.

24.- Para el Diseño de la estructura se selecciona en OPTIONS - PREFERENCES - STEEL en el
menú desplegable se elige el reglamento AISC.

E-mail: erivera@terra.com.pe Telefax: 226-1435 - Lima Perú
www.puentesrivera.es.fm

<!-- p. 10 -->

ING. EDUARDO RIVERA REYES
CONSULTOR DE PUENTES Página Web: www.puentesrivera.es.fm

25.- Se puede seleccionar los grupos de diseño DESIGN - SELECT DESIGN GROUPS con el

icono seleccionar los grupos de diseño después cliclk en ADD.

26.- Realizar el diseño en el menú principal DESIGN - START DESIGN / CHECK OF STRUCTURE
Se aprecia las secciones de color rojo que son las que no cumplen con las secciones

resistente. El valor apreciado en cada elemento es la relación de la resistencia de la sección

actuante entre la sección resistente.

27.- Para revisar un elemento que no cumple se hace Click derecho en cada barra de los elementos,
muestra las combinaciones de diseño a cada elemento y mediante la opción de Details

se revisa las propiedades de los elementos.

E-mail: erivera@terra.com.pe Telefax: 226-1435 - Lima Perú
www.puentesrivera.es.fm

<!-- p. 11 -->

ING. EDUARDO RIVERA REYES
CONSULTOR DE PUENTES Página Web: www.puentesrivera.es.fm

28.- Para rediseñar un elemento que no cumple se hace Click derecho en cada barra de los elementos,
muestra las combinaciones de diseño a cada elemento y mediante la opción de ReDesign se
puede optar por el cambio de otra sección.

Rediseñar sección cambiando los perfiles de los

elementos , click CHANGE escoger nueva

sección click OK 2 veces.

E-mail: erivera@terra.com.pe Telefax: 226-1435 - Lima Perú
www.puentesrivera.es.fm
