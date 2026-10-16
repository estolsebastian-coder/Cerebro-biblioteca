---
type: libro
title: "Guía Nº 2"
author: "Yo"
categoria: "AYUDAS DE PROGRAMAS"
paginas: 14
extraccion: "texto"
fuente: "local:E:/MATERIAL DE CONSULTA/AYUDAS DE PROGRAMAS/COMPUTERS AND STRUCTURES/Guía Nº 2.pdf"
convertido: 2026-10-16
---

# Guía Nº 2

> Texto extraído de `AYUDAS DE PROGRAMAS\COMPUTERS AND STRUCTURES\Guía Nº 2.pdf` (14 páginas, texto). El PDF original está en el disco E: (MATERIAL DE CONSULTA); `<!-- p. N -->` marca el inicio de cada página.

<!-- p. 1 -->

1

Guía Nº 2: SAFE 8

\1. Dibujo y Definiciones

Lo primero que tenemos que hacer es dibujar las losas en el programa, para esto tenemos dos
opciones. Exportando un piso y las cargas directamente desde ETABS o simplemente
dibujándolas de igual forma que lo hicimos con nuestro edificio.

1.1 Alternativa A:

Exportando las losas como sigue:

Luego elegimos el piso que vamos a exportar y las combinaciones que requeriremos. En la
elección de las cargas, tenemos que considerar las que incluyen el peso propio y las
sobrecargas, con sus respectivos factores de mayoración para los esfuerzos y las cargas bajo
criterio ASD para deformaciones. Sin embargo, el criterio para determinar las deformaciones
de las losas va a depender de cómo se construirán, pues como es sabido la rigidez del
hormigón aumenta con el tiempo y generalmente se realiza el descimbre de las losas, cuando
no se ha alcanzado la resistencia característica del hormigón; por lo tanto, determinar las
deformaciones con el mismo módulo de elasticidad con el que se determinan los esfuerzos no
es muy correcto, para esto se aconseja leer el capítulo 6 del código ACI 318.

Universidad de Santiago de Chile – Facultad de Ingeniería – Departamento Ingeniería en Obras Civiles
Taller de Estructuras 2do Semestre 2006
Profs.: Cristian Avendaño – Patricio Ugarte Ayud.: Jorge Arriagada

<!-- p. 2 -->

2

Para poder abrir las losas no es directamente desde el programa SAFE, se deben importar,
así:

Puede que tengan un error, pues se supone que la versión de SAFE trabaja con archivos de
ETABS v7 y nosotros realizamos el modelo en una versión superior, por esto a veces no se
cargan las losas correctamente y se borran las combinaciones de cargas. Por lo mismo, se
deben chequear las los losas y las cargas de cada una.

1.2 Alternativa B:

Se realizan las grillas de la misma forma que se hace en ETABS, la única diferencia es que
no nos muestra las coordenadas de los puntos de intersección del grillado, por lo tanto una
buena opción es realizar el grillado con varios colores, para no perderse en la grilla.

De igual forma que en otros programas de CSI, se deben definir cuales van a ser los
elementos que vamos a utilizar en la modelación. Sin embargo, aquí no se definen materiales,
sólo elementos; por ejemplo, definimos un muro de 20 cm con una resistencia característica de
250 kg/cm2. Además, existen los elementos áreas (losas) y para los elementos soportantes dos,
los muros y las vigas. En cuanto a estos últimos, más que muros el programa define elementos
soportantes y los elementos superiores se toman como vigas y/o muros, pues las condiciones
de apoyo de la losa varían si sobre la losa existe un muro o una viga.

Universidad de Santiago de Chile – Facultad de Ingeniería – Departamento Ingeniería en Obras Civiles
Taller de Estructuras 2do Semestre 2006
Profs.: Cristian Avendaño – Patricio Ugarte Ayud.: Jorge Arriagada

<!-- p. 3 -->

3

Define/Slab Properties…

Aquí estamos definiendo una losa de 15 cm, ojo que es con un 90% de fc’=250 kg/cm2, por
eso el valor del módulo de elasticidad, esto no se debe hacer en este taller.

Define/Beam Properties…

Se debe tener cuidado pues se deben definir los elementos que están sobre la losa, ya sean
vigas o muros:

Universidad de Santiago de Chile – Facultad de Ingeniería – Departamento Ingeniería en Obras Civiles
Taller de Estructuras 2do Semestre 2006
Profs.: Cristian Avendaño – Patricio Ugarte Ayud.: Jorge Arriagada

<!-- p. 4 -->

4

Definimos un muro que actuará como viga, pues se encuentra sobre el nivel de la losa:

También definimos las vigas propiamente tal:

Universidad de Santiago de Chile – Facultad de Ingeniería – Departamento Ingeniería en Obras Civiles
Taller de Estructuras 2do Semestre 2006
Profs.: Cristian Avendaño – Patricio Ugarte Ayud.: Jorge Arriagada

<!-- p. 5 -->

5

Define/Wall Support…

Los muros se tienen que definir como sigue:

Draw…

Luego tenemos que dibujar los objetos. Existen dos tipos de objetos para SAFE, uno son las
áreas y otros los elementos líneas.

Línea

Dibujamos una línea y luego la seleccionamos con el botón derecho y agregamos las
propiedades del muro que está bajo el fondo de la losa (Support Property) y del que está sobre
el NOG de ésta (Beam Property).

Universidad de Santiago de Chile – Facultad de Ingeniería – Departamento Ingeniería en Obras Civiles
Taller de Estructuras 2do Semestre 2006
Profs.: Cristian Avendaño – Patricio Ugarte Ayud.: Jorge Arriagada

<!-- p. 6 -->

6

Cuando se trata de una viga invertida, sólo se definen las propiedades de la viga:

Para definir pilares se dibuja un punto y se le asignan las propiedades del pilar previamente
definido.

Area

Este paso es similar a lo que se hace ETABS, se debe tener cuidado en cómo se van a
dibujar tratando de cortar en puntos adecuados las losas, para que se generen los puntos duros
que corresponden a los muros y dejando las losas de los pasillos o donde las luces son más
pequeñas con cortes convenientes. Los muros soportantes muestran unos símbolos en los
bordes de las losas, por lo que si no se ven en los lugares donde nosotros sabemos que existen
muros, tenemos que volver a definirlos, sobre todo en el caso de exportar directamente desde
ETABS.

Universidad de Santiago de Chile – Facultad de Ingeniería – Departamento Ingeniería en Obras Civiles
Taller de Estructuras 2do Semestre 2006
Profs.: Cristian Avendaño – Patricio Ugarte Ayud.: Jorge Arriagada

<!-- p. 7 -->

7

Cargas

Las cargas y combinaciones se definen igual que en todos los softwares de CSI, en el menú
define.

Para aplicarlas sobre las losas se debe seleccionar con el botón derecho la losa y aplicarlas
en la lengüeta Load Case y elegir de manera correcta las unidades.

Una vez definida las cargas tenemos listo nuestro modelo, hasta este paso es lo que se realiza
automáticamente al exportar las losas por piso; pero, es conveniente revisar que se hayan
cumplido estos pasos al exportar la losa.

\2. Definir Strips

Tenemos que definir los strip en los ejes X e Y, que equivalen a los spandrels y piers de
ETABS donde vamos a analizar los esfuerzos y diseñaremos nuestras losas. Estos deben ser de
un metro de ancho para que los esfuerzos y cuantías estén en unidades partidas por 1m o 100
cm.

Para ver los strip vamos View y activamos Set X-Strip Layer, vamos a trabajar sólo con el
eje X, pues el proceso es similar para ambos ejes.

Lo primero que hacemos es dibujar un strip a lo largo del eje X (Draw/ Draw Rectangular
Area Objects), no importa la forma que este tenga. Una vez dibujado lo seleccionamos con el
botón derecho y le damos las dimensiones que tiene nuestra planta para que la abarque
completamente.

Universidad de Santiago de Chile – Facultad de Ingeniería – Departamento Ingeniería en Obras Civiles
Taller de Estructuras 2do Semestre 2006
Profs.: Cristian Avendaño – Patricio Ugarte Ayud.: Jorge Arriagada

<!-- p. 8 -->

8

Luego lo pinchamos y posteriormente vamos a Edit/ Replicate o presionamos Control+R, y
le damos la separación:

Una vez que definimos los strips tenemos que cortarlos en los puntos donde existen muros,
que los cortan en el sentido del eje X (paralelos a X):

Universidad de Santiago de Chile – Facultad de Ingeniería – Departamento Ingeniería en Obras Civiles
Taller de Estructuras 2do Semestre 2006
Profs.: Cristian Avendaño – Patricio Ugarte Ayud.: Jorge Arriagada

<!-- p. 9 -->

9

En un círculo de color blanco los muros que se deben cortar:

Para realizar el proceso más rápido se recomienda utilizar Snap to Gris Intersections and
Point.

Universidad de Santiago de Chile – Facultad de Ingeniería – Departamento Ingeniería en Obras Civiles
Taller de Estructuras 2do Semestre 2006
Profs.: Cristian Avendaño – Patricio Ugarte Ayud.: Jorge Arriagada

<!-- p. 10 -->

10

\3. Análisis

Una vez que realizamos los strip en ambos sentidos estamos listos para poder realizar el
análisis de las losas.

Un primer paso es elegir el código de diseño que queremos usar y sus factores, esto lo
hacemos en Options/ Preferentes o tecleando Control+K. También elegimos como
queremos ver las cuantías en la opción Sq-cm/m.

Luego en Analisis/ Set Options, elegimos el tipo de análisis que queremos, hacer en este se
elije normal; pues, los demás corresponden a análisis a la fisuración y por fluencia lenta,
además elegimos el mesh de las losas.

Universidad de Santiago de Chile – Facultad de Ingeniería – Departamento Ingeniería en Obras Civiles
Taller de Estructuras 2do Semestre 2006
Profs.: Cristian Avendaño – Patricio Ugarte Ayud.: Jorge Arriagada

<!-- p. 11 -->

11

Una vez definido estos parámetros, que son los más básicos previo a hacer correr el
programa, pues se pueden configurar como obtener los planos de las losas y el tipo de barras a
utilizar en el diseño, etc; se puede hacer correr SAFE 8.

Para hacer el análisis presionamos F5 o Analyse/ Run Analysis. Una vez realizado el
análisis chequeamos que las deformaciones de las losas sean las correctas, eso lo podemos
hacer desde el menú Display:

Para conocer los valores de la cuantía de acero de cada losa realizamos el diseño, esto se
hace en Desig/ Start Design, luego mostramos en pantalla los strip con Display/ Show Strip
Forces…:

Universidad de Santiago de Chile – Facultad de Ingeniería – Departamento Ingeniería en Obras Civiles
Taller de Estructuras 2do Semestre 2006
Profs.: Cristian Avendaño – Patricio Ugarte Ayud.: Jorge Arriagada

<!-- p. 12 -->

12

4 Diseño

El siguiente paso es exportar los resultados de la misma forma en que lo hacíamos en
ETABS. Para esto vamos a File/ Export/ Data File Access, lo guardamos en una carpeta
determinada y luego lo abrimos, se debe poner atención en que unidades pedimos que
exportara los datos. Una vez abierta la base de datos, tenemos la opción de ver los momentos y
las cuantías para las losas.

Diseñaremos la losa Nº 3 del sistema:

En primer lugar desplegamos los strip que llegan en esa losa para poder identificarlos en la
base de datos, vemos cual es el que tiene el momento mayor, en este caso es el strip 58 y la
losa en cuestión va desde las coordenadas 985.5 a 1597.5 en el sentido de X.

Universidad de Santiago de Chile – Facultad de Ingeniería – Departamento Ingeniería en Obras Civiles
Taller de Estructuras 2do Semestre 2006
Profs.: Cristian Avendaño – Patricio Ugarte Ayud.: Jorge Arriagada

<!-- p. 13 -->

13

Una vez detectado el strip nos vamos a la base de datos que contiene el strip con sus
momentos, X Strips moments, obviamente esta la exportamos a Excel y le aplicamos los
filtros correspondientes:

En este caso tenemos los momentos en Kg*cm por metro de ancho y como vemos en ancho
(width), nuestro strip justamente es de un metro de ancho, así que no tenemos que hacer
ninguna corrección al momento para diseñar. Como se pueden dar cuenta tenemos dos
momentos; pues, el programa como definió un strip, que transversalmente es un rectángulo,
entrega datos de los cuatro vértices de aquel rectángulo, obviamente para diseño tomamos los
mayores. De igual forma se detectan los momentos negativos para la armadura superior.

Una vez detectado el momento procedemos a diseñar la armadura, para ello obviamente lo
hacemos como una viga de 1 m de ancho y ocupamos el código ACI 318-2002, y en especial
los ejemplos que aparecen en “Notas Sobre el ACI-318”, del CIRSOC, de Argentina que es
una traducción del libro del ACI.

En este caso cumplimos los requerimientos de las combinaciones de carga con una armadura
φ 10 @ 25 cm.

Nótese que se puede ahorrar el proceso de diseño de la enfierradura, buscando
específicamente el strip en el punto indicado, este nos dará directamente la cuantía de acero
requerida. La diferencia de 2.527 a 2.957 cm2, se debe a que la cuantía de la tabla anterior esta
determinada por el método aproximado descrito en el libro ya mencionado.

Universidad de Santiago de Chile – Facultad de Ingeniería – Departamento Ingeniería en Obras Civiles
Taller de Estructuras 2do Semestre 2006
Profs.: Cristian Avendaño – Patricio Ugarte Ayud.: Jorge Arriagada

<!-- p. 14 -->

14

Este mismo proceso se repite para cada una de las losas en los niveles superiores e
inferiores, y cuando determinamos las cuantías correspondientes nos disponemos a diseñar la
ubicación de la enfierradura. Esto está especificado en el Código ACI. Sin embargo se incluye
una tabla para tener una mayor claridad de cómo diseñar la armadura:

Universidad de Santiago de Chile – Facultad de Ingeniería – Departamento Ingeniería en Obras Civiles
Taller de Estructuras 2do Semestre 2006
Profs.: Cristian Avendaño – Patricio Ugarte Ayud.: Jorge Arriagada
