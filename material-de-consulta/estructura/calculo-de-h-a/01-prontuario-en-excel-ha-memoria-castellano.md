---
type: libro
title: "PRONTUARIO EN EXCEL DE HORMIGÓN ARMADO"
author: "HP"
categoria: "ESTRUCTURA"
paginas: 83
extraccion: "texto (OCR pendiente)"
fuente: "local:E:/MATERIAL DE CONSULTA/ESTRUCTURA/CÁLCULO DE H.A/01. Prontuario_en_Excel_HA- Memoria (Castellano).pdf"
convertido: 2026-10-16
---

# PRONTUARIO EN EXCEL DE HORMIGÓN ARMADO

> Texto extraído de `ESTRUCTURA\CÁLCULO DE H.A\01. Prontuario_en_Excel_HA- Memoria (Castellano).pdf` (83 páginas, texto (OCR pendiente)). El PDF original está en el disco E: (MATERIAL DE CONSULTA); `<!-- p. N -->` marca el inicio de cada página.

<!-- p. 1 -->



<!-- p. 2 -->

Prontuario en Excel de Hormigón Armado (Adaptado a EHE-08)

ÍNDICE

RESUMEN ................................................................................................................................. 2

\1. INTRODUCCIÓN ................................................................................................................ 3

LA NECESIDAD DE CREAR ESTE PRONTUARIO .............................................................. 4

OBJETIVOS ................................................................................................................... 4

METODOLOGÍA ............................................................................................................ 5

EL MANUAL DE USO ..................................................................................................... 6

\2. ANÁLISIS DEL PRONTUARIO .............................................................................................. 7

PORQUÉ SE HA REALIZADO EN EXCEL .......................................................................... 8

PROBLEMAS HALLADOS Y SUS SOLUCIONES ................................................................ 8

VENTAJAS DE LA UTILIZACIÓN DE EXCEL ...................................................................... 9

\3. CÓMO UTILIZAR EXCEL ................................................................................................... 10

INTRODUCCIÓN.......................................................................................................... 11

FÓRMULAS UTILIZADAS ............................................................................................. 11

Formulación básica: ................................................................................................ 11

Condicionales: ........................................................................................................ 12

OTRAS HERRAMIENTAS.............................................................................................. 13

Listas desplegables: ................................................................................................ 13

Rastreo de fórmulas ................................................................................................ 14

Protección de las hojas. .......................................................................................... 14

\4. COMPARATIVA CON P.I.H.E. 3.1 ..................................................................................... 15

INTRODUCCIÓN DE DATOS (SECCIONES) ........................................................................ 16

Datos geométricos ...................................................................................................... 16

INTRODUCCIÓN DE DATOS (CARGAS) ............................................................................. 17

LAS ARMADURAS ........................................................................................................... 17

COMPARACIÓN ENTRE PIHE y Prontuario en Excel ......................................................... 17

FLEXIÓN ...................................................................................................................... 17

TORSIÓN ..................................................................................................................... 18

CORTANTE ................................................................................................................... 18

PUNZONAMIENTO ....................................................................................................... 19

RASANTE ..................................................................................................................... 20

ANCLAJE DE BARRAS .................................................................................................... 20

INESTABILIDAD DE SEGUNDO ORDEN (PANDEO) ......................................................... 20

DEFORMACIONES ........................................................................................................ 21

\5. FICHAS ............................................................................................................................ 25

\6. BIBLIOGRAFÍA ................................................................................................................. 80

CONCLUSIONES ...................................................................................................................... 82

Memoria 1

<!-- p. 3 -->

Prontuario en Excel de Hormigón Armado (Adaptado a EHE-08)

RESUMEN

El Prontuario en Excel de Hormigón Armado es una herramienta
de cálculo de fácil manejo (para uso profesional y docente), que
dimensiona y comprueba distintos tipos de secciones sometidas a
diversas solicitaciones; siempre siguiendo los criterios establecidos
por la normativa actual vigente (EHE-08).
Para ello se han creado 24 hojas de cálculo en formato Microsoft
Excel 2010, que se complementan con un Manual de Uso.

En esta Memoria se desarrollan: los objetivos que se pretendían
cumplir en este proyecto y cómo se han llevado a cabo, cuáles han
sido los procedimientos utilizados para los cálculos, las dificultades
encontradas en el desarrollo del trabajo y cómo se han afrontado,
también se realiza una comparativa con otro programa existente y
se muestran algunos ejemplos extraídos del Excel.

Memoria 2

<!-- p. 4 -->

Prontuario en Excel de Hormigón Armado (Adaptado a EHE-08)

\1. INTRODUCCIÓN

Memoria 3

<!-- p. 5 -->

Prontuario en Excel de Hormigón Armado (Adaptado a EHE-08)

LA NECESIDAD DE CREAR ESTE PRONTUARIO

Tal como se explica brevemente en el Resumen y como se deduce del título, el Prontuario en
Excel de Hormigón Armado (Adaptado a EHE-08) es un archivo en Excel creado para el cálculo y
comprobación de secciones de hormigón armado.

En el momento de plantear la solicitud de este proyecto no existía ningún programa de cálculo
de estructuras gratuito y que, además, sirviera para el uso académico, docente y profesional al
mismo tiempo.

La idea de este proyecto surgió de una herramienta preexistente: el Prontuario Informático
del Hormigón Estructural 3.0, desarrollado por el Instituto Español del Cemento y sus
Aplicaciones (IECA). Este prontuario era la cuarta edición de un aplicativo, que se empezó a
distribuir en el año 2000, y pretendía adaptar la versión anterior de 1994 a la normativa
vigente en la fecha (la EHE-98).

Como en el año 2012, pasados 4 años desde la entrada en vigor de la nueva normativa sobre
hormigón estructural (EHE-08), el IECA aún no había sacado a la luz ninguna actualización de su
prontuario y dado que el prontuario anterior ya era una actualización de un programa de 1994,
se consideró oportuno desarrollar uno partiendo desde cero.

Debido a las limitaciones derivadas de mi total desconocimiento sobre programación, y
conociendo el funcionamiento del prontuario preexistente, se consideró oportuno que este
nuevo “programa” no fuera un programa en sí mismo, sino que fuera un Excel que tuviera la
misma función y cubriera las mismas necesidades.

Es necesario mencionar que IECA ya ha creado y puesto a disposición de los usuarios una
nueva versión de su prontuario (la versión 3.1), pero esta vez no la ha distribuido
gratuitamente, sino por un precio de 10€/licencia. Sobre esta nueva versión se hablará más
adelante, dado que aprovechando su similitud con este proyecto se ha hecho una comparativa
de ambos “programas”.

OBJETIVOS

El objetivo de este proyecto era el de realizar y verificar el funcionamiento de todas las hojas
de cálculo que se planteaban inicialmente, siendo éstas las hojas de resultantes:

ESTADOS LÍMITE ÚLTIMOS
\1. FLEXIÓN SIMPLE
1.1. FLEXIÓN SIMPLE - EN SECCIONES RECTANGULARES
1.1.1. Dimensionado a Flexión Simple de Secciones Rectangulares
1.1.2. Comprobación a Flexión Simple de Secciones Rectangulares
1.2. FLEXIÓN SIMPLE - EN SECCIONES EN T
1.2.1. Dimensionado a Flexión Simple de Secciones en T
1.2.2. Comprobación a Flexión Simple de Secciones en T
\2. FLEXIÓN COMPUESTA
2.1. FLEXIÓN COMPUESTA - EN SECCIONES RECTANGULARES
2.1.1 Dimensionado a Flexión Compuesta de Secciones Rectangulares

Memoria 4

<!-- p. 6 -->

Prontuario en Excel de Hormigón Armado (Adaptado a EHE-08)

2.1.2. Comprobación a Flexión Compuesta de Secciones Rectangulares
2.2. FLEXIÓN COMPUESTA - EN SECCIONES EN T
2.2.1. Dimensionado a Flexión Compuesta de Secciones en T
2.2.2. Comprobación a Flexión Compuesta de Secciones en T
\3. COMPROBACIÓN A FLEXOCOMPRESIÓN SIMÉTRICA U OBLICUA
\4. CORTANTE
4.1. Dimensionado a Cortante de Secciones Rectangulares o en T
4.2. Comprobación a Cortante de Secciones Rectangulares o en T
\5. TORSIÓN
5.1. SECCIONES RECTANGULARES
5.1.1. Dimensionado a Torsión de Secciones Rectangulares
5.1.2. Comprobación a Torsión de Secciones Rectangulares
5.2. SECCIONES HUECAS
5.2.1. Dimensionado a Torsión de Secciones Huecas
5.2.2. Comprobación a Torsión de Secciones Huecas
\6. PUNZONAMIENTO
\7. RASANTE
\8. ANCLAJE DE ARMADURAS
\9. SOLAPO DE ARMADURAS
\10. INESTABLILIDAD DE SOPORTES
ESTADOS LÍMITE DE SERVICIO
\11. DEFORMACIONES
11.1. Comprobación de Secciones Rectangulares
11.2. Comprobación de Secciones en T
\12. FISURACIÓN
ANEJO
\13. Cálculo de armaduras y cuantías

En todas estas hojas se han alcanzado dos objetivos al mismo tiempo: desde un punto de vista
funcional, se trata de una herramienta útil y precisa, que cubre todas las necesidades de
dimensionado y comprobación que puede tener el usuario; por otro lado (desde una vertiente
más académica) es sencillo, de fácil manejo y proporciona algunos datos intermedios útiles
para el uso docente y que no suelen facilitar otros tipos de programas.

METODOLOGÍA

Considero importante explicarle al lector cuál ha sido el método que he utilizado para realizar
este Prontuario, dado que pese a que conocía de la existencia del Prontuario Informático del
Hormigón Estructural 3.0 (que menciono con anterioridad), no había tenido la oportunidad de
utilizarlo, y además no disponía de unas pautas de trabajo demasiado claras.

Al iniciar este proyecto desconocía las posibilidades reales del Excel y en consecuencia, en los
primeros cálculos no supe optimizar al máximo sus recursos; es por esto que durante todo el
proceso de realización de las distintas hojas de cálculo he tenido que ir consultando distintos
manuales y blogs sobre Microsoft Excel 2010.

Memoria 5

<!-- p. 7 -->

Prontuario en Excel de Hormigón Armado (Adaptado a EHE-08)

Para realizar todas las hojas he seguido siempre el mismo método:

\- Primero he realizado una lectura de la EHE-08 y de bibliografía complementaria.
\- En segundo lugar he redactado un resumen esquemático de los procedimientos y
fórmulas, para poder establecer todas las posibilidades de cálculo (esto resulta muy
útil a la hora de crear las fórmulas condicionales).
\- Seguidamente he extrapolado toda esa formulación a Excel, haciendo
comprobaciones a cada paso, con la ayuda de ejercicios resueltos.
\- Una vez se daba por acabada cada hoja de cálculo, se realizaba un tanteo con diversas
posibilidades numéricas para asegurar el funcionamiento de todos los condicionales y
evitar que algunos valores pudieran dar error.
\- Al verificar el funcionamiento correcto de todas estas posibilidades, se ha hecho una
comparación con el nuevo Prontuario Informático del Hormigón Estructural 3.1 , para
verificar todos los resultados.

EL MANUAL DE USO

Paralelamente a la realización de las hojas de cálculo he ido redactando un pequeño Manual
de Uso. Con él pretendo explicar brevemente cuales son los procedimientos y criterios de
cálculo seguidos en cada caso, qué datos requiere y cómo debe introducirlos el usuario, cuales
son los cálculos que realiza la hoja, de cuáles facilita algunos valores y, por último, ayuda a
interpretar los resultados.

No se pretende que el Manual sea una herramienta imprescindible para la correcta utilización
de las hojas de cálculo porque, tal y como he dicho, he intentado que todas las hojas sean lo
más sencillas posibles. Si bien, puede ayudar a la resolución de algunas posibles dudas que
puedan surgir, sobre todo gracias a que se ha creado un apartado de Simbología para cada una
de ellas.

Memoria 6

<!-- p. 8 -->

Prontuario en Excel de Hormigón Armado (Adaptado a EHE-08)

\2. ANÁLISIS DEL PRONTUARIO

Memoria 7

<!-- p. 9 -->

Prontuario en Excel de Hormigón Armado (Adaptado a EHE-08)

PORQUÉ SE HA REALIZADO EN EXCEL

Tal como se ha ido repitiendo en diversas ocasiones, el Prontuario en Excel de Hormigón
Armado se planteó para cubrir la ausencia de un programa de cálculo de estructuras gratuito y
sencillo, que pudiera ser utilizado por todo aquel que lo necesitara.

También se ha dicho que la elección de que el prontuario se realizara en Excel fue debido a dos
factores: el principal era mi desconocimiento de programación y por otro lado, porque se
consideró que Excel cubría todas las necesidades que el prontuario podría requerir.

En este apartado analizo, con la mayor brevedad posible, las ventajas y desventajas de la
utilización de Excel como herramienta principal, para introducir al lector en las dificultades que
me he encontrado durante su uso.

PROBLEMAS HALLADOS Y SUS SOLUCIONES

Parte de la dificultad del uso de un Excel, como base para realizar el prontuario, es su
simplicidad. Ésta a menudo comporta que los cálculos aparentemente más sencillos se
conviertan en fórmulas muy largas y difíciles de corregir.

Inicialmente, por la falta de práctica en el manejo de Excel, la complejidad y la longitud de las
fórmulas se convertía en mi problema más recurrente. Cuando encontraba algún resultado
erróneo me resultaba casi imposible hallar el lugar donde había errado, y a menudo no tenía
más remedio que rehacer todos los cálculos de nuevo.

Con el paso de las horas, de la práctica y de los numerosos errores y repeticiones, aprendí a
manejar con mayor soltura el programa y a realizar formulas cada vez más sencillas; pero esto
no siempre es posible.

Otro de los problemas que plantea el estar utilizando Excel es que, no se pueden hacer
“desaparecer” las casillas si en algún caso concreto no son necesarias. En un programa
podemos hacer que si no es necesario que el usuario facilite algún valor, se puede inutilizar esa
“casilla”.

Para solucionar esto se han planteado tres soluciones:

\- Por un lado se han duplicado algunas hojas de cálculo, pese a ser prácticamente
idénticas, para que el usuario, en lugar de seleccionar en qué caso se encuentra al
entrar en la hoja, directamente se dirija al apartado apropiado. Esto sucede en los
casos en que se calculan secciones rectangulares o en T.
\- Cuando en una misma hoja aparecen valores que pueden ser necesarios en unos casos
e innecesarios en otros, se solventa de dos modos:
o Se modifica la apariencia de la casilla, o incluso se la oculta totalmente.
o Se han creado fórmulas condicionales que “ignoran” los valores de esa casilla,
cuando no son necesarios.

Memoria 8

<!-- p. 10 -->

Prontuario en Excel de Hormigón Armado (Adaptado a EHE-08)

VENTAJAS DE LA UTILIZACIÓN DE EXCEL

Una de las ventajas de la utilización de Excel es que, si el usuario dispone del pack de Office, no
tiene que pagar ningún gasto adicional, dado que no es un programa, y que, en consecuencia,
no requiere de licencias ni ha tenido ningún coste de producción.

También considero ventajosa la estética de las hojas de cálculo, dado que se pueden modificar
con facilidad a antojo de su creador, cosa que no habría sido posible si hubiera realizado un
programa, teniendo en cuenta que éste debería haber sido muy básico si quería alcanzar mis
objetivos. Además, a la hora de generar un archivo en PDF o de imprimir los documentos, el
resultado será el mismo que el que se le ha dado a las hojas de cálculo.

Desde el punto de vista del desarrollo de todo el conjunto del trabajo, el haber utilizado Excel
ha hecho posible que pueda dedicarle más tiempo a asegurar que el funcionamiento de los
cálculos es el correcto, más sencillo y más óptimo. Esto es así, porque pese a que he tenido
que profundizar en mis conocimientos de Excel, no he tenido que dedicar gran parte de mi
tiempo en aprender a crear un programa. Podríamos decir que el usar un programa ya
existente ha simplificado la tarea, y ha permitido dedicarle más tiempo a asegurar que todas
las hojas funcionan correctamente, que es el objetivo real que me había planteado desde el
principio.

Memoria 9

<!-- p. 11 -->

Prontuario en Excel de Hormigón Armado (Adaptado a EHE-08)

\3. CÓMO UTILIZAR EXCEL

Memoria 10

<!-- p. 12 -->

Prontuario en Excel de Hormigón Armado (Adaptado a EHE-08)

INTRODUCCIÓN

Pese a que lo habitual es que en el núcleo de la Memoria de un TFG sobre cálculo de
estructuras se faciliten las fórmulas utilizadas, en este proyecto no es viable porque no existe
una única fórmula con un resultado; sino que en algunas ocasiones podemos encontrar que en
una misma fórmula hay hasta 16 condicionales distintos, y transcribir cada una ellas sería
totalmente inútil. Del mismo modo, si pretendiera explicar los procedimientos con una
formulación más o menos detallada, estaría copiando casi literalmente la EHE-08, y no creo
que sea útil.

La explicación específica del procedimiento de cada hoja de cálculo se desarrolla en el Manual
de Uso adjunto, tal y como ya se explica en uno de los apartados de la Introducción de esta
Memoria.

FÓRMULAS UTILIZADAS

Considero que puede ser interesante, sobre todo para aquel que quiera profundizar más o
ampliar mi trabajo, el facilitar algunos criterios básicos de Excel que he ido utilizando
repetidamente durante el desarrollo del trabajo. Por lo que a continuación detallaré algunas
fórmulas y explicaré como se utilizan, para poder transmitir parte de lo que he aprendido al
lector.

Formulación básica:

En muchas fórmulas, para definir las casillas a las que queremos hacer referencias podemos
utilizar dos modos: el primero (y más habitual) es utilizar como método de separación el punto
y coma “;”, que sirve para dar valores de casillas separadas; por otro lado si queremos
referirnos a un rango de casillas (por ejemplo, si queremos sumar todos los valores de una
columna) deberemos utilizar los dos puntos “:” que indican que se tomarán todas las casillas
situadas entre las dos casillas que se mencionen en el rango. Lo explico a continuación con el
comando más básico, la suma:

\=SUMA(A1;A3;A7) En este caso estamos sumando los valores que se encuentran en las
casillas A1, A3 y A7.

\=SUMA(A1:A7) De este modo estamos sumando todos los valores situados entre las
casillas A1 y A7, es decir: A1, A2, A3, A4, A5, A6 y A7.

Sabido esto, podremos utilizar este criterio en muchos otros casos.

Otras formulas que pueden resultar de interés son las siguientes:

\=MAX(A1;A3) En esta fórmula podemos introducir el número de casillas o el rango
que queramos, y nos dará como resultado el mayor de todos esos
valores.

\=MIN(A1;A3) Se pueden introducir valores independientes o fórmulas en sus
distintos argumentos o un rango de valores, y su resultado será el
menor de todos ellos.

Memoria 11

<!-- p. 13 -->

Prontuario en Excel de Hormigón Armado (Adaptado a EHE-08)

\=ABS(A1) Facilita el resultado en valor absoluto (positivo) es muy útil si, por
ejemplo tenemos que introducir un valor en una raíz cuadrada para
obtener un ratio, pero sabiendo que este valor puede ser negativo en
algún caso.

\=RAIZ(A5) Esta es la fórmula de la raíz cuadrada, también podemos poner la raíz
de una fórmula o de un valor.

\=POTENCIA(A5;2) Esta es la fórmula de la potencia, si tienes una raíz un tanto extraña
(una raíz quinta, por ejemplo) puedes utilizarla del siguiente modo:
\=POTENCIA(A1;1/5).

\=PI() El valor de π=3,14 se representa siempre con la palabra PI() si no se
escriben los paréntesis aparecerá el error #NOMBRE

Condicionales:

El uso de los condicionales puede dar formulas muy complejas y con muchas variables
distintas, dado que las condicionales se pueden combinar entre si:

\=SI(prueba lógica;valor verdadero; valor falso) Con esta función podemos introducir
una condicional que, de cumplirse la condición establecida en el primer
argumento, su resultado será el valor verdadero, sino será el falso.

En caso de tener, por ejemplo, tres resultados distintos, podemos combinar dos condicionales
“si”:

\=SI(prueba lógica1;valor verdadero1;SI(prueba lógica 2;valor verdadero 2; valor falso)
\=SI(A1\<1;0;SI(A1=1;1;2)) explicación: Si A1 es menor a 1 siempre será
0, si es igual a 1, el resultado será 1, y para cualquier valor mayor a 1 el
resultado será 2)

Suele ser muy útil combinar las funciones lógicas anteriores con las funciones Y o O (and y or):

\=Y(prueba lógica 1;prueba lógica 2;…) La función Y permite que el resultado pueda darse si se
cumplen, a la vez, distintas condiciones. =SI(Y(A1=1;A2=2);1;2)

\=O(prueba lógica 1;prueba lógica 2;…) La función O permite que el resultado pueda darse si se
cumple al menos una de las pruebas lógicas que se muestran en
cualquiera de los argumentos.

Memoria 12

<!-- p. 14 -->

Prontuario en Excel de Hormigón Armado (Adaptado a EHE-08)

OTRAS HERRAMIENTAS

Listas desplegables:

Excel 2010 tiene un manejo relativamente sencillo, dado que es muy gráfico, y todas sus
herramientas están visibles en la barra superior del programa. Si bien hay algunas
herramientas que no están visibles por defecto y que puede ser útiles para la creación de una
hoja de Excel.

Este es el caso del menú Programador, que inicialmente aparece oculto, y deberá configurarse

a través del menú Archivo, en su botón de , deberemos clicar en “Personalizar
cinta de opciones” y añadir la correspondiente a la pestaña Programador.

De este menú he utilizado sobretodo la opción que permite añadir listas desplegables. Con
versiones más antiguas de Excel estas listas desplegables se añadían desde la pestaña de
“Validación de datos”; esto aún se puede llevar a cabo, pero en el caso de hacerlo desde esa
opción las listas desplegables no serán visibles como tales hasta que el usuario pinche en la
casilla.

En muchas ocasiones me ha interesado
mostrarle al usuario que en algunas hojas
debe escoger valores de algunas listas
desplegables, y por eso las he introducido de
este modo:

Desde el menú programador, clicando sobre la
pestaña “insertar” se pueden escoger
distintos tipos de cuadros, entre ellos el
Cuadro combinado, que corresponde a las
listas desplegables.

Tal como comentaba antes, también se pueden crear otro tipo de listas desplegables que no
son visibles para el usuario hasta el momento en que intenta modificar algún dato de la casilla,
como es en el caso de los valores de fck, fyk o los diámetros de las barras. Estos valores están
normalizados, y por lo tanto se pueden incluir en una lista, pero por motivos estéticos se
muestran como si fueran una casilla de datos normal:

Esto se realiza con la opción Validación de Datos desde la pestaña de Datos.

Memoria 13

<!-- p. 15 -->

Prontuario en Excel de Hormigón Armado (Adaptado a EHE-08)

Rastreo de fórmulas

En algunas ocasiones puede resultar muy útil encontrar qué casillas guardan relación entre sí,
por ejemplo cuando un resultado nos da algún tipo de error y tenemos que retroceder hasta
encontrar el origen de ese error.

Para ello hay dos opciones muy útiles, denominadas Rastrear precedentes y Rastrear
dependientes:

Ambas se encuentran en la pestaña de Fórmulas en el submenú Auditoria de fórmulas. Al
seleccionar en una casilla y seguidamente escoger una de estas opciones aparecerán unas
flechas azules que nos conducirán a las fórmulas dependientes o precedentes. En caso de que
una de las fórmulas anteriores o posteriores de un error relacionado con la casilla estudiada, la
flecha será de color rojo, cosa que facilitará la detección del error en los cálculos.

Protección de las hojas.

Este Excel ha sido bloqueado para evitar que el usuario pueda romper o modificar alguna de
las fórmulas que contiene. Pero no se han bloqueado todas las casillas, dado que se han
dejado editables todas aquellas que pertenezcan a la introducción de datos.

Además no se ha bloqueado el Excel entero para poderle permitir al usuario guardar los
cambios que realice en las hojas de cálculo, para que si tiene que cerrar sesión, pueda volver a
visualizar los mismos datos con posterioridad sin tener que volver a modificarlos.

El primer paso a realizar para proteger las hojas es seleccionar una a una las casillas que se
quieren bloquear y las que no. Como en el caso de este proyecto existen más casillas
bloqueadas que desbloqueadas, inicialmente se han bloqueado todas y posteriormente se han
desbloqueado las que se ha considerado oportunas. Para hacer esto, se debe entrar en el

menú que se encuentra en la lista desplegable que aparece al clicar
con el botón derecho del ratón sobre cualquier casilla, en el apartado Proteger podremos
escoger si Bloquear y/o Ocultar las fórmulas que contenga.

Una vez hecho esto, nos dirigimos a la pestaña Revisar de la barra de opciones superior, y
desde el apartado Proteger Hoja seleccionamos las opciones de bloqueo que consideremos
oportunas e introducimos la contraseña. Esto deberá repetirse hoja por hoja, si no se quiere
bloquear la totalidad del libro.

Memoria 14

<!-- p. 16 -->

Prontuario en Excel de Hormigón Armado (Adaptado a EHE-08)

\4. COMPARATIVA CON P.I.H.E. 3.1

Memoria 15

<!-- p. 17 -->

Prontuario en Excel de Hormigón Armado (Adaptado a EHE-08)

A finales del año 2012, el IECA sacó a la venta su nueva versión del Prontuario Informático de
Hormigón Estructural v.3.1 (a partir de ahora PIHE), en aquel momento mi proyecto ya había
tomado forma y se encontraba en un estado bastante avanzado. Tomé la decisión de que
debía aprovechar la existencia de esta herramienta para realizar comprobaciones de mis
cálculos, y me di cuenta de que el Prontuario en Excel de Hormigón Armado se asemejaba
mucho más de lo que esperaba al PIHE, y por eso consideré oportuno redactar algunas
comparaciones de algunas de las funciones de ambos aplicativos.

Estas comparaciones no pretenden exaltar ninguno de los dos programas, pero he de decir que
he intentado que el Excel mejorara algunos de los aspectos que consideraba que no eran del
todo óptimos en el PIHE.

Evidentemente, el hecho de que el PIHE sea un programa facilita que, en muchos casos,
plantee diversas alternativas para el cálculo (desarrollado y simplificado) o que use algunos
cálculos más exactos y, al mismo tiempo, mucho más complejos que el Excel; motivo por el
cual el aspecto que se ha intentado mejorar en el Prontuario en Excel ha sido sobretodo que
sea más fácil de utilizar.

En este apartado no se compararán todos y cada uno de los apartados que se han creado en el
Excel y que existen también en el PIHE, sino que tan solo se reseñan aquellos en que hayan
diferencias importantes o algunas divergencias justificadas de los resultados.

INTRODUCCIÓN DE DATOS (SECCIONES)

Para introducir los datos de las dimensiones de las secciones, en el PIHE han creado una
pestaña adicional donde introducir estos valores. En esta pestaña se deben facilitar tanto los
valores geométricos de la pieza como las características de sus materiales. Esto puede ser muy
ventajoso si el usuario pretende comprobar o dimensionar una misma pieza sometida a
esfuerzos distintos.

En cambio, en el Excel, pese a que se podría haber hecho lo mismo, se ha considerado
oportuno que en cada hoja el usuario tenga que introducir estos datos. La ventaja de esta otra
opción es que si el usuario quiere hacer el dimensionado de distintas piezas sometidas al
mismo esfuerzo, no tiene que salir de la hoja de cálculo para modificar los datos.

Además, de cara la impresión de los archivos, en el caso del Excel, es mejor que todos los datos
estén reflejados en cada hoja de cálculo, para que al pasar el documento a papel o a PDF el
usuario no deba realizar dos impresiones: la de la hoja de la sección y la de la hoja de cálculo
que esté utilizando en ese momento.

Datos geométricos

En el caso concreto de los recubrimientos, en IECA, en algunos casos, da por hecho que en
toda la pieza éstos son iguales. En el Excel he preferido distinguir entre recubrimientos
inferiores y superiores, porque puede darse el caso de que cada cara del elemento esté
sometida a un ambiente distinto, y que por lo tanto estos recubrimientos no sean iguales.

Memoria 16

<!-- p. 18 -->

Prontuario en Excel de Hormigón Armado (Adaptado a EHE-08)

INTRODUCCIÓN DE DATOS (CARGAS)

En ninguna de las pestañas de cálculo, el PIHE facilita esquemas de disposición de las cargas.
Esto significa que el usuario debe “deducir” si los valores positivos corresponden a la tracción o
la compresión, por ejemplo. En el caso de Excel se facilitan unos esquemas muy sencillos que
sirven tanto para facilitar la comprensión de la nomenclatura, como para esclarecer cuales son
los valores geométricos que se solicitan, como la dirección de las cargas.

LAS ARMADURAS

En el dimensionado de cualquier sección, podremos comprobar que PIHE suele limitar el
diámetro máximo de las armaduras a 25mm y en algunos casos a 20mm; además no utiliza las
armaduras que aparecen en la normativa, sino únicamente los diámetros comerciales.

Esto último tiene ventajas a la hora de aplicar los resultados a casos reales, pero no lo he
considerado útil para el uso docente, en el que no se suelen despreciar los valores de las
barras “no comerciales”. Además, en el caso del Excel he intentado que los cálculos se ajusten
a la normativa, y no a las condiciones del mercado existente, porque es más sencillo que
cambie el mercado que no los diámetros de las barras normalizadas.

Para que el Excel sea útil tanto para el uso docente como para el uso profesional, he decidido
no facilitar únicamente el resultado más óptimo de dimensionado, sino que facilito tablas
donde se enseñan los resultados obtenidos de la utilización de cualquier diámetro. Es
necesario decir que esto no es exclusivo de éste proyecto, sino que también se realiza en el
PIHE, pese a que en el Prontuario en Excel se facilitan más resultados porque utiliza todos los
diámetros normalizados.

COMPARACIÓN ENTRE PIHE y Prontuario en Excel

FLEXIÓN

En todas las hojas de flexión simple o compuesta en el PIHE utilizan el método parábolarectángulo contemplado por la EHE-08. Este es un método más exacto que el que utilizo en el
Excel, pero también resulta mucho más complejo. Pese a que el método del diagrama
rectangular que se utiliza en el Excel es mucho más sencillo y menos preciso, las diferencias
finales son casi despreciables.

Otra diferencia que considero importante, es que el PIHE no facilita las armaduras mínimas
establecidas por la normativa. Es decir, si por cálculo la pieza no requeriría armadura superior,
el PIHE no le facilita al usuario los diámetros mínimos establecidos por la normativa, ni en
cuanto a cuantías ni para el cumplimiento del Artículo 42.3.2.

Dado que en el caso concreto de la flexión, podemos encontrarnos en flexión simple o
compuesta, el usuario se puede encontrar con un error al introducir los datos en el PIHE , este
error es debido a que la sección dimensionada para el cálculo de la flexión simple o de muchas
otras solicitaciones (por ejemplo torsión), no sirve para el dimensionado o la comprobación de
la flexión compuesta.

Memoria 17

<!-- p. 19 -->

Prontuario en Excel de Hormigón Armado (Adaptado a EHE-08)

En el PIHE facilitan 6 tipos de secciones, en función del caso en el que se encuentre el usuario,
entre ellas está el “EJEMPLO 2” que describe como “sección rectangular redondos”, y es la que
se requiere para el cálculo de elementos sometidos a flexión compuesta. Esto es así porque el
prontuario entiende que en caso de tratarse de una flexo-compresión la distribución de las
armaduras no es igual, y por lo tanto obliga al usuario a cambiarla.
En el Excel, como la hoja de Flexo-Compresión está realizada a parte, no da pie a error.

TORSIÓN

En este caso existen varias diferencias entre ambos aplicativos, la primera y más evidente es
que el PIHE solicita más datos al usuario, como son el valor de α y de he , en cambio estos dos
valores el Excel los da calculados. En el caso del PIHE da por hecho que el valor he no tiene
porqué ser igual en todas las caras de la pieza, por lo que permite escoger el valor con una
barra móvil, y lo representa al mismo tiempo con la ayuda de un gráfico que cambia según
modificamos el valor de la barra.

En el caso del Excel da por hecho que el valor de he es uniforme en todo el perímetro, y por lo
tanto lo puede calcular por si solo.

El valor de α, en cambio, es un valor marcado por la normativa, por lo que no veo útil que el
prontuario permita modificarlo a antojo.

Una ventaja que tiene el PIHE con respecto al Excel es que cuando el valor de Td>TU1, es decir,
cuando falla la resistencia de la sección de hormigón, no facilita ningún otro resultado. Esto es
positivo porque evita un exceso de información que el usuario no requiere.

CORTANTE

En este caso encontramos cuatro diferencias ente el PIHE y el Prontuario en Excel, y todas ellas
se encuentran en la introducción de datos.

La primera es que el PIHE solicita que el usuario le facilite la
cuantía geométrica de la armadura longitudinal, en cambio en
el Prontuario en Excel, se solicitan el diámetro y el número de
barras. He optado por facilitar las barras y no la cuantía
geométrica para evitar que el usuario tenga que hacer el
cálculo, si bien es cierto que complica la introducción de datos

Memoria 18

<!-- p. 20 -->

Prontuario en Excel de Hormigón Armado (Adaptado a EHE-08)

porque requiere del doble de información. Considero que en la mayoría de los casos, el usuario
será conocedor de la armadura y no directamente de la cuantía geométrica. Si se diera el caso
de que el usuario es estudiante y conoce únicamente la cuantía geométrica, puede hacer uso
de la hoja 13. Cálculo de armaduras y cuantías.

Una diferencia bastante importante es que en PIHE el usuario debe establecer si existe o no
armadura de cortante, tanto para el dimensionado como para la comprobación. En el
Prontuario en Excel, en el caso del dimensionado, es la hoja de cálculo la que determina si
requiere o no armadura, y su dimensionado.

PIHE solicita que el usuario calcule el brazo mecánico (z) de la sección, mientras que el Excel lo
da calculado.

Por último, PIHE no le permite al usuario establecer el momento flector que puede haber
aplicado en la pieza, en cambio en el Excel si se toma en consideración. Este valor sirve para
saber si la pieza fisura o no, dado que influye en el cálculo. Estimo que en el PIHE dan por
hecho que la pieza siempre fisura (dado que es lo más habitual).

PUNZONAMIENTO

En el caso del punzonamiento, el PIHE no permite que se realice el dimensionado de la
armadura si ésta se encuentra distribuida uniformemente, tan solo permite calcular armadura
en haz. Si el usuario introduce la opción de la armadura uniforme automáticamente salta un
error que dice \<\<En la actual versión del programa el esquema de armado para
dimensionamiento debe ser tipo 1>> (el tipo 1 corresponde a la distribución en haz).

Esta limitación está motivada por el hecho de que PIHE facilita los resultados en una tabla en la
que determina el número de redondos y el diámetro de cada capa, y esta tabla no se puede
utilizar en el caso de la armadura uniforme, dado que el número de barras varía en cada
perímetro concéntrico. En el caso del Excel se ha tomado la decisión de facilitarle al usuario el
número de capas y el área de acero necesaria en cada una de ellas.

Memoria 19

<!-- p. 21 -->

Prontuario en Excel de Hormigón Armado (Adaptado a EHE-08)

RASANTE

En este caso, de nuevo me vuelvo a encontrar con que PIHE, solicita datos distintos a los míos,
sus creadores han considerado oportuno solicitar menos cantidad de datos, pero que el
usuario sea el que debe calcularlos, en cambio, en el Prontuario en Excel, solicito más cantidad
de datos pero más sencillos; como es el caso del valor τr,d que en el PIHE es un dato solicitado y
en el Excel se calcula solo, dado que depende de b, de d y Nd.

Otra diferencia es que en el Prontuario Informático solicitan el valor de p (superficie de
contacto por metro lineal) mientras que yo solicito el valor b, b sirve para calcular p, y es un
valor más familiar para el usuario, además sirve para posteriormente calcular la Tensión
Rasante (τr,d), mencionada en el párrafo anterior.

ANCLAJE DE BARRAS

Ambas aplicaciones son muy parecidas, si bien el PIHE permite utilizar el método simplificado y
el “preciso”, y en el Prontuario en Excel solo he planteado el método simplificado.

Al comparar los resultados de las longitudes de anclaje de las armaduras se observa una
divergencia. Esto es debido a que el PIHE no solicita el recubrimiento nominal de las barras,
dato necesario para establecer el coeficiente β para obtener la lb,neta.

En la normativa (EHE-08, Tabla 69.5.1.2.b) establece que el valor de β en tracción para anclajes
con patilla, gancho o gancho en U, puede variar y ser de β=0,7 si el recubrimiento del
hormigón es superior a 3Ø o de β=1 si el recubrimiento es menor a 3Ø.

Si multiplicáramos los valores distintos de la tabla del Prontuario en Excel por 0,7 el resultado
sería idéntico al del PIHE.

INESTABILIDAD DE SEGUNDO ORDEN (PANDEO)

Me parece necesario mencionar un fallo que tiene el PIHE en la ficha de cálculo de pandeo.
Cuando el usuario está introduciendo los datos en la hoja de pandeo, en cuanto cambia de
pestaña para realizar dimensionado o si se dirige a la pestaña de “secciones” para cerciorarse
de que los datos están correctamente introducidos (recordemos que el dimensionado de la
sección no se introduce en cada pestaña de cálculo, sino que se guarda en una distinta), al
regresar a la hoja de pandeo, se encontrará con que todos los valores introducidos han sido
borrados automáticamente. También me ha sucedido que el ordenador se me ha “colgado” en
al menos dos ocasiones al intentar hacer que el programa hiciera los cálculos de pandeo, y que
en repetidas ocasiones he tenido que cerrar y volver a abrir el programa porque, sin motivo
aparente, no permitía la introducción de datos de la estructura. Si el usuario clica en algún
botón que modifique alguno de los encuentros superiores o inferiores de la estructura, todos
los datos introducidos se borran, y además vuelve a no permitir la introducción de datos sobre
la estructura.

En contraposición a los errores que he mencionado, la opción de pandeo en el PIHE es más
completa que la del Prontuario en Excel, dado que el prontuario tan solo se había planteado
como método de comprobación, y el PIHE también sirve para el dimensionado.

Memoria 20

<!-- p. 22 -->

Prontuario en Excel de Hormigón Armado (Adaptado a EHE-08)

DEFORMACIONES

El apartado de deformaciones es uno de los más complicados de utilizar por el usuario, tanto si
utiliza el PIHE como si utiliza el Prontuario en Excel. Si bien, ambos aplicativos no son
demasiado comparables, dado que el Prontuario Informático es mucho más completo y
complejo que el Prontuario en Excel.

Este apartado será más extenso y específico que el resto de apartados de esta memoria, dado
que pretendo demostrar lo complejo que es el procedimiento que utiliza PIHE, puesto que es
la justificación del porqué no se ha realizado una hoja de cálculo semejante en Excel.

A continuación explicaré los datos que solicita cada aplicativo y cómo funciona o muestra sus
resultados.

PIHE
En este programa, la introducción de datos es bastante compleja, pero es debido a que sus
cálculos también son más completos, motivo por el cual considero que esa dificultad añadida
está justificada.

Un punto que me ha llamado la atención es que admite seis tipos de secciones distintas, tanto
en función de la geometría como de la disposición de las armaduras, pero entre ellas no se
encuentran las secciones en T, justo al contrario de lo planteado en el Prontuario en Excel.

Dicho esto, empezaré a explicar paso por paso los datos que debe introducir el usuario:

\- Primero de todo el usuario debe escoger entre tres “Tipos de Elementos”, es decir, el
tipo de vano que quiere calcular en función de sus encuentros. Las opciones que se
muestran son: Bi-apoyado, Voladizo, Vano Interno y Vano extremo. Una vez escogido
esto, en la parte inferior de la pantalla se resaltarán algunas casillas, correspondientes
a la opción marcada, para que, en los casos en que ambos extremos no sean iguales,
pueda escoger entre 2 opciones según la disposición de los mismos (se muestra el
ejemplo del voladizo).

\- Después se selecciona el tipo de sección.
\- Una vez hecho esto, recomiendo que se introduzca el valor de las cuantías geométricas
de la armadura y la Luz (L) y se de al botón de calcular, incluso antes de introducir
ninguna carga. Digo esto porque es probable que la relación luz/canto del vano en
cuestión, sea inferior al marcado por la normativa, y por lo tanto tal vez no requiera
comprobación de deformaciones. Esto ahorraría un trabajo innecesario de
introducción de valores, dado que para obtener esta relación solo se necesitan los
datos previamente mencionados.

Memoria 21

<!-- p. 23 -->

Prontuario en Excel de Hormigón Armado (Adaptado a EHE-08)

\- Si PIHE establece que si es necesario comprobar las flechas, se procede a la
introducción de las cargas a las que está sometida la barra. Este es el punto más
complejo, dado que el usuario deberá introducir un número considerable de valores.
Esto es así, primero porque existen 3 tipos de cargas: actuantes en el descimbrado,
otras cargas permanentes y sobrecarga de uso; y luego porque puede introducir 3
tipos de acciones: Cargas puntuales, Momentos Flectores, Cargas uniformes y cargas
trapezoidales, y de cada una de ellas puede facilitar hasta 8 valores distintos. En
resumidas cuentas, el usuario puede introducir entre 2 y 96 cargas distintas, las cuales
requieren entre 2 y 4 datos para poder ser correctamente identificadas.

Una vez introducidos todos estos valores, se procede al cálculo. Con ellos el prontuario hace
diversas combinaciones y obtiene 3 tipos de inercias: una para el descimbrado, una teniendo
en cuenta solo cargas permanentes y la última que tiene en cuenta todas las cargas.

Con estas Inercias equivalentes, se calculan las deformaciones de las barras, y facilita una tabla
con las deformaciones instantáneas, diferidas, totales y activas, a cada 20 centímetros por
toda la barra. Además lo complementa con un gráfico en el que podemos obtener las
deformaciones en cualquier punto de la barra.

Memoria 22

<!-- p. 24 -->

Prontuario en Excel de Hormigón Armado (Adaptado a EHE-08)

Prontuario en Excel
El prontuario es mucho más sencillo tanto en la introducción de datos como en los resultados
que el PIHE, pero se ha considerado que era suficiente, dado que lo único que se pretende es
poder calcular la deformación máxima, total y activa de la barra.

La introducción de datos de esta hoja de cálculo se encuentra mucho más desarrollada en el
manual de uso, pero se hará una breve descripción para que se pueda comparar con el
programa anteriormente descrito.

Primero de todo, se debe escoger entre una de las 2 hojas de cálculo creadas: secciones
rectangulares o secciones en T. Una vez en la hoja apropiada lo primero que debe hacer es
escoger qué tipo de vano quiere calcular, y el sistema estructural:

Seguidamente se introducen las características geométricas y de materiales, que aparecen en
prácticamente todas las hojas de cálculo.

Una vez hecho esto el usuario puede, si así lo desea, dirigirse al apartado de Cálculos Previos,
donde se muestra el cálculo de la relación L/d. Se ha decidido dejarlo en ese apartado y no
mostrarlo desde un primer momento para anular todos los cálculos posteriores, dado que
considero que puede ser interesante para el usuario conocer las deformaciones, pese a que
estas cumplan normativa.

Independientemente de si se opta por comprobar la relación L/d o no, el siguiente paso es la
introducción de las cargas a las que está sometida la barra. Se han distinguido entre cuatro
tipos:

qd P q
qi + M

g
L a b c d e f

\- Repartida trapezoidal de extremo a extremo de la barra: esta carga sirve tanto para
calcular cargas repartidas uniformes como triangulares.
\- Puntual
\- Momento flector aplicado

Memoria 23

<!-- p. 25 -->

Prontuario en Excel de Hormigón Armado (Adaptado a EHE-08)

\- Repartida uniforme en un tramo de la barra.

De estas cargas se pueden introducir dos valores: el de las cargas en el momento del
descimbrado (se distinguen con el superíndice “i”) y las cargas actuantes a los n días. Dado que
se ha simplificado tanto el cálculo, si el usuario tiene, por ejemplo, una carga puntual debida a
cargas permanentes y una carga puntual debida a la sobrecarga de uso, deberá introducir el
resultado de la suma de ambas. No admite la introducción de varias cargas distintas del mismo
tipo.

Con estos valores la hoja calculará automáticamente los momentos flectores máximos a los
que están sometidas las barras, y con ellos establecerá si fisura para posteriormente
determinar cuál es el momento de inercia necesario para realizar los cálculos de las
deformaciones.

En el apartado de Resultados, el usuario deberá rellenar una casilla más. No es habitual que se
soliciten datos en este apartado, pero se ha considerado oportuno porque, tan solo afecta al
cálculo del resultado final.

Así pues, se simplifica la introducción de datos y se facilitan menos resultados, pero se han
realizado las combinaciones necesarias para obtener los más desfavorables, que son, en
definitiva, los que se suelen necesitar.

Memoria 24

<!-- p. 26 -->

Prontuario en Excel de Hormigón Armado (Adaptado a EHE-08)

\5. FICHAS

A continuación muestro ejemplos de todas las hojas de cálculo y sus homólogas del Prontuario
Informático de Hormigón Estructural 3.1.

Memoria 25

<!-- p. 27 -->

DIMENSIONADO A FLEXIÓN SIMPLE - SECCIONES RECTANGULARES

Volver al índice

DATOS

Dimensiones de la sección rs
As2
h 0,5 m
b 0,25 m
rMEC,INF 0,05 m d
h
rMEC,SUP 0,05 m
d 0,45 m
s
As1
Características de los materiales ri
fyk 500 N/mm² b
fck 25 N/mm²
T.M.A. 15 mm
As2
γs 1,15 u
γc 1,5 u
αcc 1 u d
h Md
fyd 434,8 N/mm²
fcd 16,67 N/mm²
As1
Esfuerzos de cálculo r i
Md 400 m·kN

CÁLCULOS

Diagrama rectangular Md>Mlim
xLIM 0,28 m y Yʟiм
yLIM 0,22 m FC Fc,ʟiм
FC,LIM 925,3 kN
MLIM 313,6 mkN

RESULTADOS: DIMENSIONADO DE LA ARMADURA

Armadura mínima de cálculo Armadura mínima de norma
AS1 26,25 cm² AS1 3,50 cm²
AS2 4,97 cm² AS2 1,05 cm²

AS1 Aumentar Sección AS2 Aumentar Sección

ØS1 #barras AREAL SREAL SMIN ØS2 #barras AREAL SREAL SMIN
(mm) (ud) (cm²) (cm) (cm) (mm) (ud) (cm²) (cm) (cm)

6 93 26,30 -0,44 2,00 6 18 5,09 0,25 2,00
8 53 26,64 -0,53 2,00 8 10 5,03 0,78 2,00
10 34 26,70 -0,58 2,00 10 7 5,50 1,33 2,00
12 24 27,14 -0,6 2,00 12 5 5,65 2,25 2,00
14 18 27,71 -0,6 2,00 14 4 6,16 3,13 2,00
16 14 28,15 -0,57 2,00 16 3 6,03 5,1 2,00
20 9 28,27 -0,38 2,00 20 2 6,28 11 2,00
25 6 29,45 0 2,50 25 2 9,82 10 2,50
32 4 32,17 0,73 3,20 32 1 8,04 ― 3,20
40 3 37,70 1,5 4,00 40 1 12,57 ― 4,00

<!-- p. 28 -->

PRONTUARIO INFORMÁTICO DEL HORMIGÓN ESTRUCTURAL 3.1 SEGÚN EHE-08

Cátedra de Hormigón Estructural ETSICCPM - IECA

Obra: 1
Fecha: 02/07/2013

Hora: 17:49:33

Dimensionamiento de secciones a flexión simple

1 Datos

\- Materiales

Tipo de hormigón : HA-25
Tipo de acero : B-500-S
fck [MPa] = 25.00
fyk [MPa] = 500.00
c = 1.50
s = 1.15

\- Sección

Sección : EJEMPLO1
b [m] = 0.25
h [m] = 0.50
ri [m] = 0.050
rs [m] = 0.050

2 Dimensionamiento

Md [kN·m] = 400

Plano de deformación de agotamiento

x [m] = 0.276
1/r [1/m]·1.E-3 = 12.7
s ·1.E-3 = 3.5
i ·1.E-3 = -2.8

Página 1 de 2

<!-- p. 29 -->

Deformación y tensión de armaduras

Profundidad Armadura Deformación Tensión
[m] [cm²] ·1.E-3 [MPa]
0.050 5.1 2.9 -434.8
0.450 26.6 -2.2 434.8

At_est [cm²] = 26.6

[mm] 12 14 16 20 25

nº ---- ---- ---- ---- 6

nº capas ---- ---- ---- ---- 2

At [cm²] ---- ---- ---- ---- 29.5

wk [mm] ---- ---- ---- ---- 0.24

Ac_est [cm²] = 5.1

[mm] 12 14 16 20 25

nº 5 4 3 2 2

nº capas 2 1 1 1 1

At [cm²] 5.7 6.2 6.0 6.3 9.8

Página 2 de 2

<!-- p. 30 -->

COMPROBACIÓN A FLEXIÓN SIMPLE - SECCIONES RECTANGULARES

Volver al índice
DATOS

Dimensiones de la sección
h 0,5 m rs
As2
b 0,3 m
rMEC,INF 0,05 m
rMEC,SUP 0,05 m
d
d 0,45 m h

Características de los materiales
s
fyk 500 N/mm² As1
fck 25 N/mm² ri
T.M.A. 15 mm b
γs 1,15 u
γc 1,5 u
αcc 1 u
As2
fyd 434,8 N/mm²
fcd 16,67 N/mm²

d MdDisposición de las armaduras h
\#bS1 4 ud.
ØS1 32 mm
As1
AS1 32,17 cm²
r i #bS2 2 ud.
ØS2 10 mm
AS2 1,57 cm²

Esfuerzos de cálculo
Md 500 m·kN

CÁLCULOS

Cálculos previos Valores límite (Diag. Rectangular)
US1 1398,7 kN xLIM 0,28 m
US2 68,29549 kN yLIM 0,22 m
FC,LIM 1110,3 kN
Mlim 376,37 mkN

RESULTADO

Resultados Interpretación de resultados:
DOMINIO 4 No cumple, insuficientes armaduras S1 y S2
yreal 0,23 m
Fc 1163,5 kN
Mu 415,53 m·kN

<!-- p. 31 -->

PRONTUARIO INFORMÁTICO DEL HORMIGÓN ESTRUCTURAL 3.1 SEGÚN EHE-08

Cátedra de Hormigón Estructural ETSICCPM - IECA

Obra: 1
Fecha: 02/07/2013

Hora: 18:12:55

Comprobación de secciones a flexión simple

1 Datos

\- Materiales

Tipo de hormigón : HA-25
Tipo de acero : B-500-S
fck [MPa] = 25.00
fyk [MPa] = 500.00
c = 1.50
s = 1.15

\- Sección

Sección : EJEMPLO1
b [m] = 0.30
h [m] = 0.50
ri [m] = 0.050
rs [m] = 0.050

2 Comprobación

At [cm²] = 32.2
Ac [cm²] = 1.6

Mu [kN·m] = 413.7

Plano de deformación de agotamiento

x [m] = 0.290
1/r [1/m]·1.E-3 = 12.1
s ·1.E-3 = 3.5

Página 1 de 2

<!-- p. 32 -->

i ·1.E-3 = -2.5

Deformación y tensión de armaduras

Profundidad Armadura Deformación Tensión
[m] [cm²] ·1.E-3 [MPa]
0.050 1.6 2.9 -434.8
0.450 32.2 -1.9 385.6

Página 2 de 2

<!-- p. 33 -->

DIMENSIONADO A FLEXIÓN SIMPLE - SECCIONES EN T

Volver al índice
DATOS

bala
Dimensiones de la sección
rs
hALA 0,30 m As2 h ala
hALMA 0,20 m s
bALA 0,50 m
bALMA 0,30 m d
rMEC,INF 0,05 m
h alma
rMEC,SUP 0,05 m s
d 0,45 m As1
ri
Características de los materiales balma
fyk 500 N/mm²
fck 25 N/mm²
As2
T.M.A. 15 mm hala
γs 1,15 u
γc 1,5 u d
h Md αcc 1 u
fyd 434,8 N/mm² halma
fcd 16,67 N/mm²
As1
r i
Esfuerzos de cálculo
Md 300 mkN

CÁLCULOS

Diagrama rectangular Md\<Mlim
xLIM 0,28 m x 0,111 m
yLIM=λ(x)h 0,22 m y 0,089 m 0,088752
MMAX,ALA 750,00 mkN FC 739,6 kN 739,6014
FC,LIM 1850,6 kN
MLIM 627,3 mkN

RESULTADOS: DIMENSIONADO DE LA ARMADURA

Armadura mecánica mínima Armadura geométrica mínima
AS1 17,01 cm² AS1 5,88 cm²
AS2 0,00 cm² AS2 1,76 cm²

AS1 AS2

ØS1 #barras AREAL SREAL SMIN ØS2 #barras AREAL SREAL SMIN
(mm) (ud) (cm²) (cm) (cm) (mm) (ud) (cm²) (cm) (cm)
6 61 17,25 -0,28 2,00 6 7 1,98 5,97 2,00
8 34 17,09 -0,22 2,00 8 4 2,01 12,27 2,00
10 22 17,28 -0,1 2,00 10 3 2,36 18,5 2,00
12 16 18,10 0,05 2,00 12 2 2,26 37,6 2,00
14 12 18,47 0,29 2,00 14 2 3,08 37,2 2,00
16 9 18,10 0,7 2,00 16 1 2,01 ― 2,00
20 6 18,85 1,6 2,00 20 1 3,14 ― 2,00
25 4 19,63 3,33 2,50 25 1 4,91 ― 2,50
32 3 24,13 5,2 3,20 32 1 8,04 ― 3,20
40 2 25,13 12 4,00 40 1 12,57 ― 4,00

<!-- p. 34 -->

PRONTUARIO INFORMÁTICO DEL HORMIGÓN ESTRUCTURAL 3.1 SEGÚN EHE-08

Cátedra de Hormigón Estructural ETSICCPM - IECA

Obra: 1
Fecha: 02/07/2013

Hora: 18:50:24

Dimensionamiento de secciones a flexión simple

1 Datos

\- Materiales

Tipo de hormigón : HA-25
Tipo de acero : B-500-S
fck [MPa] = 25.00
fyk [MPa] = 500.00
c = 1.50
s = 1.15

\- Sección

Sección : EJEMPLO3
b [m] = 0.50
b0 [m] = 0.30
h [m] = 0.50
h0 [m] = 0.30
ri [m] = 0.050
rs [m] = 0.050

2 Dimensionamiento

Md [kN·m] = 300

Plano de deformación de agotamiento

x [m] = 0.112
1/r [1/m]·1.E-3 = 29.2
s ·1.E-3 = 3.3

Página 1 de 2

<!-- p. 35 -->

i ·1.E-3 = -11.3

Deformación y tensión de armaduras

Profundidad Armadura Deformación Tensión
[m] [cm²] ·1.E-3 [MPa]
0.050 0.0 1.8 0.0
0.450 17.1 -9.9 434.8

At_est [cm²] = 17.1

[mm] 12 14 16 20 25

nº ---- ---- 9 6 4

nº capas ---- ---- 2 2 1

At [cm²] ---- ---- 18.1 18.8 19.6

wk [mm] ---- ---- 0.28 0.29 0.32

Página 2 de 2

<!-- p. 36 -->

COMPROBACIÓN A FLEXIÓN SIMPLE - SECCIONES EN T

Volver al índice
DATOS

Dimensiones de la sección bala
hALA 0,30 m rs
As2
hALMA 0,20 m h ala
s
bALA 0,50 m
bALMA 0,30 m d
rMEC,INF 0,05 m
rMEC,SUP 0,05 m h alma
d 0,45 m s
As1
ri
Características de los materiales
balma fyk 500 N/mm²
fck 25 N/mm²
T.M.A. 15 mm
γs 1,15 u As2
hala
γc 1,5 u
αcc 1 u
d fyd 434,78 N/mm² Md h
fcd 16,67 N/mm²
halma

Disposición de las armaduras
As1
\#bS1 5 ud. r i
ØS1 32 mm
AS1 40,21 cm²
\#bS2 7 ud.
ØS2 6 mm Esfuerzos de cálculo
AS2 1,98 cm² Md 450 mkN

CÁLCULOS

Cálculos previos Valores límite (Diag. Rectangular)
US1 1748,36 kN xLIM 0,28 m
US2 86,05 kN yLIM=λ(x)h 0,22 m
MMAX,ALA 750,00 mkN FC,LIM 1850,6 kN
MLIM 627,3 mkN

RESULTADO

Resultados Interpretación de resultados:
DOMINIO 2 o 3 Cumple, no es necesario aumentar la armadura
yreal 0,20 m
Fc 1662,3 kN
Mu 582,2 m·kN

<!-- p. 37 -->

PRONTUARIO INFORMÁTICO DEL HORMIGÓN ESTRUCTURAL 3.1 SEGÚN EHE-08

Cátedra de Hormigón Estructural ETSICCPM - IECA

Obra: 1
Fecha: 02/07/2013

Hora: 19:21:33

Comprobación de secciones a flexión simple

1 Datos

\- Materiales

Tipo de hormigón : HA-25
Tipo de acero : B-500-S
fck [MPa] = 25.00
fyk [MPa] = 500.00
c = 1.50
s = 1.15

\- Sección

Sección : EJEMPLO3
b [m] = 0.50
b0 [m] = 0.30
h [m] = 0.50
h0 [m] = 0.30
ri [m] = 0.050
rs [m] = 0.050

2 Comprobación

At [cm²] = 37.7
Ac [cm²] = 2.0

Mu [kN·m] = 584.5

Plano de deformación de agotamiento

x [m] = 0.230

Página 1 de 2

<!-- p. 38 -->

1/r [1/m]·1.E-3 = 15.2
s ·1.E-3 = 3.5
i ·1.E-3 = -4.1

Deformación y tensión de armaduras

Profundidad Armadura Deformación Tensión
[m] [cm²] ·1.E-3 [MPa]
0.050 2.0 2.7 -434.8
0.450 37.7 -3.3 434.8

Página 2 de 2

<!-- p. 39 -->

DIMENSIONADO A FLEXIÓN COMPUESTA - SECCIONES RECTANGULARES

Volver al índice
DATOS

Dimensiones de la sección
h 0,5 m As2 rs
b 0,25 m
rMEC,INF 0,05 m
rMEC,SUP 0,05 m d
h
d 0,45 m

Características de los materiales s
fyk 500 N/mm² As1
ri
fck 25 N/mm²
b
T.M.A. 15 mm
γs 1,15 u
γc 1,5 u As2
Md αcc 1 u
fyd 434,8 N/mm²
fcd 16,67 N/mm² d h Nd

Esfuerzos de cálculo
Md 200 m·kN As1
Tracción[-] Nd 50 kN r i
Md' 190 m·kN

CÁLCULOS

Diagrama rectangular Md'\<Mlim
xLIM 0,28 m x 0,15 m
yLIM 0,22 m y 0,12 m
FC,LIM 925,3 kN FC 484,9 kN
MLIM 313,6 mkN

RESULTADOS: DIMENSIONADO DE LA ARMADURA

Armadura mecánica mínima Armadura geométrica mínima
AS1 11,15 cm² AS1 3,50 cm²
AS2 0,00 cm² AS2 1,05 cm²

AS1 AS2

ØS1 #barras AREAL SREAL SMIN ØS2 #barras AREAL SREAL SMIN
(mm) (ud) (cm²) (cm) (cm) (mm) (ud) (cm²) (cm) (cm)

6 40 11,31 -0,23 2,00 6 4 1,13 4,2 2,00
8 23 11,56 -0,15 2,00 8 3 1,51 6,3 2,00
10 15 11,78 0 2,00 10 2 1,57 13 2,00
12 10 11,31 0,33 2,00 12 1 1,13 ― 2,00
14 8 12,32 0,54 2,00 14 1 1,54 ― 2,00
16 6 12,06 1,08 2,00 16 1 2,01 ― 2,00
20 4 12,57 2,33 2,00 20 1 3,14 ― 2,00
25 3 14,73 3,75 2,50 25 1 4,91 ― 2,50
32 2 16,08 8,6 3,20 32 1 8,04 ― 3,20
40 1 12,57 ― 4,00 40 1 12,57 ― 4,00

<!-- p. 40 -->

PRONTUARIO INFORMÁTICO DEL HORMIGÓN ESTRUCTURAL 3.1 SEGÚN EHE-08

Cátedra de Hormigón Estructural ETSICCPM - IECA

Obra: 1
Fecha: 26/09/2013

Hora: 23:09:14

Dimensionamiento de secciones a flexión simple

1 Datos

\- Materiales

Tipo de hormigón : HA-25
Tipo de acero : B-500-S
fck [MPa] = 25.00
fyk [MPa] = 500.00
c = 1.50
s = 1.15

\- Sección

Sección : EJEMPLO1
b [m] = 0.30
h [m] = 0.50
ri [m] = 0.050
rs [m] = 0.050

2 Dimensionamiento

Md [kN·m] = 190

Plano de deformación de agotamiento

x [m] = 0.117
1/r [1/m]·1.E-3 = 29.8
s ·1.E-3 = 3.5
i ·1.E-3 = -11.4

Página 1 de 2

<!-- p. 41 -->

Deformación y tensión de armaduras

Profundidad Armadura Deformación Tensión
[m] [cm²] ·1.E-3 [MPa]
0.050 0.0 2.0 0.0
0.450 10.9 -9.9 434.8

At_est [cm²] = 10.9

[mm] 12 14 16 20 25

nº 10 8 6 4 3

nº capas 2 2 2 1 1

At [cm²] 11.3 12.3 12.1 12.6 14.7

wk [mm] 0.28 0.26 0.28 0.31 0.30

Página 2 de 2

<!-- p. 42 -->

COMPROBACIÓN A FLEXOCOMPRESIÓN SIMÉTRICA O ESVIADA

DATOS

Dimensiones de la sección Armadura
b 0,5 m Ø 20 mm
h 0,5 m #barras(y) 3
rH 0,05 m #barras(x) 4
rV 0,05 m 300

Características de los materiales
200
fck 30 N/mm2
fyk 400 N/mm2
100
γc 1,50 ud
γs 1,15 ud
fy,cd 347,83 N/mm2 x 0
\-400 -200 0 200 400

Esfuerzos de cálculo -100
Nd 500 kN
My,d 300 m·kN -200
Mx,d 500 m·kN
EjeNeutro
\-300 y Barras

CÁLCULOS

Coordenadas de las barras Resultados acero
Coord. x Coord. Y Dist. e.n. εs Tracción[-] Fs · dx Fs · dy
Nº mm mm mm -- kN mkN mkN
1 200 200 38,29 -0,0005 -34,55 6,91 -6,91
2 67 200 32,74 0,0005 29,54 -1,97 5,91
3 -67 200 103,77 0,0015 93,62 6,24 18,72
4 -200 200 174,81 0,0025 109,27 21,85 21,85
5 -200 0 5,55 0,0001 5,01 1,00 0,00
6 -200 -200 163,70 -0,0024 -109,27 -21,85 21,85
7 -67 -200 234,73 -0,0034 -109,27 -7,28 21,85
8 67 -200 305,77 -0,0044 -109,27 7,28 21,85
9 200 -200 376,80 -0,0054 -109,27 21,85 21,85
10 200 0 207,55 -0,0030 -109,27 21,85 0,00
11 0 0 0,00 0,0000 0,00 0,00 0,00
12 0 0 0,00 0,0000 0,00 0,00 0,00
13 0 0 0,00 0,0000 0,00 0,00 0,00
14 0 0 0,00 0,0000 0,00 0,00 0,00
15 0 0 0,00 0,0000 0,00 0,00 0,00
16 0 0 0,00 0,0000 0,00 0,00 0,00
17 0 0 0,00 0,0000 0,00 0,00 0,00
18 0 0 0,00 0,0000 0,00 0,00 0,00
19 0 0 0,00 0,0000 0,00 0,00 0,00
20 0 0 0,00 0,0000 0,00 0,00 0,00
21 0 0 0,00 0,0000 0,00 0,00 0,00
22 0 0 0,00 0,0000 0,00 0,00 0,00
23 0 0 0,00 0,0000 0,00 0,00 0,00
24 0 0 0,00 0,0000 0,00 0,00 0,00
25 0 0 0,00 0,0000 0,00 0,00 0,00
26 0 0 0,00 0,0000 0,00 0,00 0,00
27 0 0 0,00 0,0000 0,00 0,00 0,00
28 0 0 0,00 0,0000 0,00 0,00 0,00
RESULTANTE -343,47 55,89 127,00

<!-- p. 43 -->

Resultados hormigón
Canto total h 689,51 mm
Canto útil total d 620,56 mm
Eje neutro x 243,76 mm
Bloque compresiones y 195,01 mm
A. zona comprimida Área 421,73 cm²
Coord. X c.d.g xcdg -127,99 mm
Coord. Y c.d.g ycdg 173,19 mm
Fc 843,47 kN
RESULTANTE Fc·dx 107,95 mkN
Fc·dx 146,08 mkN

RESULTADOS

Solver
Ángulo eje neutro φ 32,19 grados
Profundidad eje neut ξ 0,39 -
Nd / FTOT 1,00
( My,d / Fc·dx ) / ( Mx,d / Fc·dy 1,00
Error total 0,00
SOLVER: Que la resultante de fuerzas iguale al axil y que la excentricidad de resultante sea como la de servicio

Equilibrios
Acciones Esfuerzos Coef. Seg.
Equilibrio Fuerzas 500,00 500,00
Equilibrio Momentos 300,00 163,85 0,55
Equilibrio Momentos 500,00 273,08 0,55

Grafiado del eje neutro (coordenadas de sus vértices)

x y
A(x,y) -250,00 19,57 mm
B(x,y) 116,04 250,00 mm

<!-- p. 44 -->

PRONTUARIO INFORMÁTICO DEL HORMIGÓN ESTRUCTURAL 3.1 SEGÚN EHE-08

Cátedra de Hormigón Estructural ETSICCPM - IECA

Obra: 1
Fecha: 05/07/2013

Hora: 19:30:14

Cálculo de secciones a flexión compuesta esviada

1 Datos

\- Materiales

Tipo de hormigón : HA-30
Tipo de acero : B-400-S
fck [MPa] = 30.00
fyk [MPa] = 400.00
c = 1.50
s = 1.15

\- Sección

Sección : EJEMPLO2
b [m] = 0.50
h [m] = 0.50
r [m] = 0.050

nº barras horizontales = 4
nº barras verticales = 3

Página 1 de 2

<!-- p. 45 -->

2 Comprobación

Factor Arm. = 1.00
Nd [kN] = 500
Mxd [kN·m] = 300
Myd [kN·m] = 500

Nu [kN] = 500
Mxu [kN·m] = 158.8
Myu [kN·m] = 264.6
\= 0.53

Arm. nº Fija Tipo Diámetro [mm] Area [cm2] xi [m] yi [m] xf m] yf [m]
1 NO P 20.00 12.566 0.050 0.450 0.450 0.450
2 NO P 20.00 12.566 0.050 0.050 0.450 0.050
3 NO P 20.00 3.142 0.050 0.250 0.050 0.250
4 NO P 20.00 3.142 0.450 0.250 0.450 0.250

Plano de deformación de agotamiento

x [m] = 0.23
ß [º] = 62.9
1/r [1/m]·1.E-3 = 15.0
s ·1.E-3 = 3.5
i ·1.E-3 = -6.6

Deformación y tensión de armaduras superior e inferior

Profundidad Deformación Tensión
[m] ·1.E-3 [MPa]
0.07 2.5 348
0.61 -5.6 -348

Página 2 de 2

<!-- p. 46 -->

DIMENSIONADO A CORTANTE- SECCIONES RECTANCULARES O EN T

Volver al índice
DATOS

Dimensiones de la sección
h 0,5 m
rs
b0 0,3 m As2
rMEC,INF 0,05 m
rMEC,SUP 0,05 m
d
d 0,45 m h

Características de los materiales
fyk 500 N/mm² As1
fyα,k 500 N/mm² ri
fck 25 N/mm² b 0
Control del hormigón → 1
fcv 25,00 N/mm² cortanteArmadura
TMA 15 mm
γs 1,15 u As2
γc 1,5 u aα
αcc 1 u
fyd 434,78 N/mm² h d
fyα,d 434,78 N/mm²
fcd 16,67 N/mm²
Es 2,E+05 N/mm² As1 ?θ
r i
Disposición de las armaduras st Bielas de
\#bS' 3 ud. compresión
ØS' 25 mm
AS' 14,73 cm²
\#bS 5 ud.
ØS 25 mm d /4
AS 24,54 cm²
θt 45 ° d /4 b0
αt 90 ° d
d /4 b0
St,cercos 35 cm
\#RAMAS 4 ud b0 d /4

Esfuerzos de cálculo
Vrd 400 kN
Nd 0 kN
Md 0 m·kN

<!-- p. 47 -->

CÁLCULOS

Factores y coeficientes. Resultados

Relativos a los materiales Agotamiento por compresión oblicua del alma:
f1cd 10,00 N/mm² VU1 675,00 kN
fct,k 1,80 N/mm² Δb0xd 0,00 %
fct,d 1,20 N/mm² La sección cumple
fct,m 2,56 N/mm²
Relativos a los esfuerzos Agotamiento por tracción del alma:
K 1,00 ud. (39.1) Mfis 14,96 mkN
σ'cd 0,00 N/mm² No fisura pero requiere armadura
Relativos a la sección VU2,mec 427,80 kN
Iz 3E-03 m⁴ VCU 80,30 kN
S 0,01 m³ VSU,mec 347,50 kN
ξ 1,67 ud.
ρl 18,18 ‰
θe 45 °
β 1,00 ud.

RESULTADOS: DIMENSIONADO DE LA ARMADURA

Valores estrictos de norma: Otros datos geométricos de interés
st,cercos 27,00 cm Aα/grupo 5,12 cm²/grupo
Aα,mec 19,73 cm²/m st,trans MAX 45 cm
Aα,geom 0,03 cm²/m

Combinaciones de armado Combinaciones de armado
ØS,t #RAMAS Aα,real st,cercos VSU,real ØS,t #RAMAS Aα,real st,cercos VSU,real
(mm) (ud) (cm²/m) (cm) (kN) (mm) (ud) (cm²/m) (cm) (kN)
6 4 22,62 5,00 425,68 6 25 20,20 35,00 380,07
8 4 20,11 10,00 378,38 8 14 20,11 35,00 378,38
10 4 20,94 15,00 394,14 10 9 20,20 35,00 380,07
12 4 22,62 20,00 425,68 12 7 22,62 35,00 425,68
14 4 22,81 27,00 429,18 14 5 21,99 35,00 413,85
16 4 29,79 27,00 560,56 16 4 22,98 35,00 432,43
20 4 46,54 27,00 875,88 20 3 26,93 35,00 506,76
(#RAMAS, fijo) (st,cercos, fijo)
NOTA: Los valores tachados no cumplen separación entre ramas.
El valor de St elegido es superior a la separación estricta máxima.

<!-- p. 48 -->

PRONTUARIO INFORMÁTICO DEL HORMIGÓN ESTRUCTURAL 3.1 SEGÚN EHE-08

Cátedra de Hormigón Estructural ETSICCPM - IECA

Obra: 1
Fecha: 09/07/2013

Hora: 19:45:13

Cálculo de secciones a cortante

1 Datos

\- Materiales

Tipo de hormigón : HA-25
Tipo de acero : B-500-S
fck [MPa] = 25.00
fyk [MPa] = 500.00
c = 1.50
s = 1.15

\- Control del hormigón

Control normal

\- Tipo de elemento estructural

Tipo : elemento con armadura a cortante

\- Sección

Sección : EJEMPLO1
b0 [m] = 0.30
h [m] = 0.50

Página 1 de 2

<!-- p. 49 -->

2 Dimensionamiento

Esfuerzo cortante de cálculo Vd [kN] = 400

Inclinación de las bielas [º] = 45
Inclinación de los cercos [º] = 90.0
l [·1.E-3] = 18.18
comprimida [·1.E-3] = 0.0
Nd [kN] = 0.0
xd [MPa] = 0.0
yd [MPa] = 0.0
e [º] = 45.0

Separación Area Vsu Vu2
nº ramas Tipo
[mm] [mm] [cm²/m] [kN] [kN]

ø 6 ---- ---- ---- ---- ---- ----
ø 8 0.10 4 20.1 2 325.7 406.02
ø 10 0.15 4 20.9 2 339.3 419.59
ø 12 0.10 2 22.6 1 366.4 446.73

Área estricta [cm²/m] = 19.7
Vu1 [kN] = 675.0
Vcu [kN] = 80.3

Página 2 de 2

<!-- p. 50 -->

COMPROBACIÓN A CORTANTE- SECCIONES RECTANCULARES O EN T

DATOS

Dimensiones de la sección cortanteArmadura
h 0,50 m rs
As2 As2 b0 0,30 m
rMEC,INF 0,05 m aα
rMEC,SUP 0,05 m
d d
d 0,45 m h h

Disposición de las armaduras
As1 ?θ
\#bS' 3 ud. As1
ri r i ØS' 25 mm
AS' 14,73 cm² b 0 st Bielas de
\#bS 5 ud. compresión
ØS 25 mm Características de los materiales
AS 24,54 cm² fyk 500 N/mm²
Armadura a cortante 1 fyα,k 500 N/mm²
θt 45 ° fck 25 N/mm²
αt 90 ° Control del hormigón → 1
ØS,t 8 mm fcv 25,00 N/mm²
\#RAMAS 2 ud. TMA 15 mm
St,cercos 30 cm γs 1,15 u
Aα 3,351 cm²/m γc 1,50 u
αcc 1,00 u
Esfuerzos de cálculo fyd 434,78 N/mm²
Vrd 100 kN fyα,d 434,78 N/mm²
Nd 0 kN fcd 16,67 N/mm²
Md 20 m·kN Es 2,E+05 N/mm²

CÁLCULOS

Coef. relativos a los materiales Coef. relativos a la sección
f1cd 10,00 N/mm² Iz 3E-03 m⁴
fct,k 1,80 N/mm² S 0,01 m³
fct,d 1,20 N/mm² ξ 1,67 ud.
fct,m 2,56 N/mm² ρl 18,18 ‰
Coef. relativos a los esfuerzos θe 45,00 °
K 1,00 ud. β 1,00 ud.
σ'cd 0,00 N/mm² z 0,405 m

RESULTADOS

Resultados previos Cortante que la sección puede resistir:
Mfis 14,96 mkN VU 134,58 kN
La sección fisura
VU1 675,00 kN Interpretación de resultados
La sección cumple a compresión oblicua Cumple, no es necesario aumentar ni armadura ni sección
VU2 134,58 kN
VCU 80,30 kN Δb0xd 0,00 %
VSU 54,29 kN ΔAα NO %
La armadura existente cumple

<!-- p. 51 -->

PRONTUARIO INFORMÁTICO DEL HORMIGÓN ESTRUCTURAL 3.1 SEGÚN EHE-08

Cátedra de Hormigón Estructural ETSICCPM - IECA

Obra: 1
Fecha: 11/07/2013

Hora: 18:19:52

Cálculo de secciones a cortante

1 Datos

\- Materiales

Tipo de hormigón : HA-25
Tipo de acero : B-500-S
fck [MPa] = 25.00
fyk [MPa] = 500.00
c = 1.50
s = 1.15

\- Control del hormigón

Control normal

\- Tipo de elemento estructural

Tipo : elemento con armadura a cortante

\- Sección

Sección : EJEMPLO1
b0 [m] = 0.30
h [m] = 0.50

Página 1 de 2

<!-- p. 52 -->

2 Comprobación

Tipo de armadura: cercos a 90.0º
separación st [m] = 0.30
[mm] = 8
nº ramas : 2
Area [cm²/m] = 3.4
l [·1.E-3] = 18.18

Inclinación de las bielas [º] = 45
Nd [kN] = 0.0
comprimida [·1.E-3] = 0.0
yd [MPa] = 0.0

Vu1 [kN] = 675.0
Vu2 [kN] = 134.6
Vcu [kN] = 80.3
Vsu [kN] = 54.3

\- Resistencia a cortante:
Vu [kN] = 134.6

Página 2 de 2

<!-- p. 53 -->

DIMENSIONADO A TORSIÓN - SECCIONES RECTANGULARES

Volver al índice
DATOS

Dimensiones de la sección
h 0,50 m rs c
b 0,30 m
perimetro ue
rMEC,INF 0,05 m Area Ae
rMEC,SUP 0,05 m d h
d 0,45 m perimetro u
Area A
Características de los materiales
fyk 500 N/mm² ri
fck 25 N/mm² he
TMA 15 mm b
γs 1,15 u
γc 1,50 u
αcc 1,00 u Armadura
fyd 434,8 N/mm²
As2
fcd 16,67 N/mm²
aα f1cd 10 N/mm²

d
Disposición de la armadura a torsión h
θt 45 °
αt 90 ° As1 ?θ
r i
Armadura longitudinal a compresión
st Bielas de #bS' 3 ud.
compresión
ØS' 25 mm
AS' 14,73 cm²

Esfuerzos de cálculo
Nd 0 kN
Td 40 m·kN
Vrd 0 kN

CÁLCULOS

Coeficientes: M. tors máximo que puede resistir
K 1,00 ud. TU1 48,0 m·kN Cumple
α 0,60 ud.
β 1,33 ud.

Características de la sección: Torsión combinada con cortante
he 0,10 m VU1 675,00 kN
Ae 0,08 m² Vrd,MAX 213,72 kN
ue 1,20 m

<!-- p. 54 -->

RESULTADOS: DIMENSIONADO DE LA ARMADURA

Armadura transversal a torsión estricta Armadura longitudinal mínima
At 6,63 cm²/m AL,MIN 7,50 cm²
At 0,38 cm² TU3 40,0 m·kN
St 6 cm

At Al Suponiendo AS1 y AS2 iguales
ØSt #cercos AREAL TU2 ØSl #barras AREAL SREAL SMIN TU3
6 1 0,57 60,32 6 27 7,634 0,3 2 40,72
8 1 1,01 107,23 8 15 7,540 1,1 2 40,21
10 1 1,57 167,55 10 10 7,854 2,2 2 41,89
12 1 2,26 241,27 12 7 7,917 3,9 2 42,22
14 1 3,08 328,40 14 5 7,697 6,5 2 41,05
16 1 4,02 428,93 16 4 8,042 9,1 2 42,89
20 1 6,28 670,21 20 3 9,425 no existe 2 50,27
25 1 9,82 1047,20 25 2 9,817 no existe 2,5 52,36
32 1 16,08 1715,73 32 1 8,042 no existe 3,2 42,89
40 1 25,13 2680,83 40 1 12,566 no existe 4 67,02

<!-- p. 55 -->

PRONTUARIO INFORMÁTICO DEL HORMIGÓN ESTRUCTURAL 3.1 SEGÚN EHE-08

Cátedra de Hormigón Estructural ETSICCPM - IECA

Obra: 1
Fecha: 11/07/2013

Hora: 18:46:10

Cálculo de secciones rectangulares a torsion

1 Datos

\- Materiales

Tipo de hormigón : HA-25
Tipo de acero : B-500-S
fck [MPa] = 25.00
fyk [MPa] = 500.00
c = 1.50
s = 1.15

\- Sección

Sección : EJEMPLO1
b0 [m] = 0.30
h [m] = 0.50

Página 1 de 2

<!-- p. 56 -->

2 Comprobación

he [m] = 0.100
Ae [m²] = 0.080
ue [m] = 1.200
[º] = 45.0
\= 0.60

Torsor de cálculo [kN·m] = 40

Agotamiento de las bielas Tu1 [kN·m] = 48.0

\- Armadura transversal

Area estricta [cm²] = 6.3

Separación Area Tu2
nº estribos
[mm] [mm] [cm²/m] [kN·m]

6 ------ ------ ------ ------
8 ------ ------ ------ ------
10 ------ ------ ------ ------
12 ------ ------ ------ ------

\- Armadura longitudinal

Area estricta [cm²] = 7.5

número de Area Tu3
[mm] redondos [cm²] [kN·m]

10 12 9.4 50.3
12 8 9.0 48.3
14 6 9.2 49.3
16 4 8.0 42.9
20 4 12.6 67.0

Página 2 de 2

<!-- p. 57 -->

COMPROBACIÓN A TORSIÓN - SECCIONES RECTANGULARES

Volver al índice
DATOS

Dimensiones de la sección
rs c h 0,5 m
b 0,3 m perimetro ue
rMEC,INF 0,05 m Area Ae
rMEC,SUP 0,05 m d h
d 0,45 m perimetro u
Area A

Disposición de las armaduras
\#bS,L 4 ud. ri
ØS,L 20 mm he
ASL 12,57 cm² AS' cm² b
ØSt 8 mm AL cm²
St 10 cm * El valor de st es mayor al establecido por art.45.2.3 coArmaduraa e
At 0,50 cm²
As2
θt 45 °
αt 90 ° aα

d
Características de los materiales h
fyk 500 N/mm²
fck 25 N/mm²
As1 ?θ
TMA 15 mm
r i γs 1,15 u
γc 1,50 u st Bielas de
αcc 1,00 u compresión
fyd 434,8 N/mm² Esfuerzos de cálculo
fcd 16,67 N/mm² Nd 0 kN
f1cd 10 N/mm² Td 45 m·kN
Vrd 3 kN

CÁLCULOS

Características relativas a la sección: Coeficientes
he 0,10 m K 1,00 ud.
Ae 0,08 m² α 0,60 ud.
ue 1,20 m β 1,33 ud.

Interacción con cortante
VU1 675,00 kN

RESULTADOS:

Momentos torsores máximos que puede resistir Cortante máximo que puede resistir
TU1 48,0 m·kN Cumple Vrd,MAX 103,86 kN
TU2 32,2 m·kN No cumple Cumple
TU3 67,0 m·kN Cumple

Torsor máximo que puede resistir:
TU,MAX 32,00 m·kN limitado por s t,MAX = 6,00 cm

Interpretación de resultados:
La armadura transversal no cumple las separaciones de norma, Tu,max=2/3·Tu

<!-- p. 58 -->

PRONTUARIO INFORMÁTICO DEL HORMIGÓN ESTRUCTURAL 3.1 SEGÚN EHE-08

Cátedra de Hormigón Estructural ETSICCPM - IECA

Obra: 1
Fecha: 12/07/2013

Hora: 19:46:01

Cálculo de secciones rectangulares a torsion

1 Datos

\- Materiales

Tipo de hormigón : HA-25
Tipo de acero : B-500-S
fck [MPa] = 25.00
fyk [MPa] = 500.00
c = 1.50
s = 1.15

\- Sección

Sección : EJEMPLO1
b0 [m] = 0.30
h [m] = 0.50

Página 1 de 2

<!-- p. 59 -->

2 Comprobación

he [m] = 0.100
Ae [m²] = 0.080
ue [m] = 1.200
[º] = 45.0
\= 0.60

\- Armadura longitudinal

[mm] = 20
Número de barras = 8
Área [cm²] = 25.13

\- Armadura transversal

[mm] = 10
Número de estribos = 1
Separación [m] = 0.10
SEPARACIÓN DE CERCOS SUPERIOR A LA PERMITIDA
Área [cm²/m] = 7.85
Inclinación de estribos [º] = 90

\- Axil de Cálculo (Compresión +)

Nd [kN] = 0.0
comp [·1.E-3] = 0.0
'cd [MPa] = 0.0

Esfuerzo de agotamiento de las bielas Tu1 [kN·m] = 48.0
Esfuerzo de agotamiento de la armadura transversal Tu2 [kN·m] = 50.2
Esfuerzo de agotamiento de la armadura longitudinal Tu3 [kN·m] = 134.0
Resistencia a torsión Tu [kN·m] = 32.0
(Tu limitado por la condición de máxima separación de cercos. Art. 45.2.3)

Página 2 de 2

<!-- p. 60 -->

E.L.U. a PUNZONAMIENTO

Volver al índice
DATOS

Datos geométricos del soporte 2 d c 2 lx c1 2d
c1 (x) 0,30 m u1
(y) y y
c2 0,30 m
Tipo de soporte 2
2 x by1 c 1 x by1 c
lx 0,00 m
u1 ly 2,00 m 2 d 2 d

Datos geométricos de la losa bx1 bx1
h 0,3 m lx c1 2 d
rmec,inf 0,03 m
d 0,27 m y
l y

2 xArmadura longitudinal de la losa: c by1
Diámetros y separaciones: 2
2 d u1
Ø Sx 8 mm
S Sx 0,1 m
bx1
Ø Sy 10 mm
S Sy 0,12 m S 2d S 2d
ρ l 1,39 ‰
un,ef ly y Cuantía geométrica
ρl 4,00 ‰ y cc x
by2
x by2Armadura de punzonamiento: S un,ef
2d
Armadura 2
S by2
α 90 ° 2d
smax 0,203 m bx2
s 0,20 m 0,200
S 2d
s1,min 0,081 m lx
s1,max 0,135 m ly y
s1 (user) 0,14 m 0,1
c x
by2
Características de los materiales
un,ef fck 25 N/mm² S
2d
fyα,k 400 N/mm²
bx2
γc 1,5 u
γs 1,15 u S 2d
S 2d
αcc 1,00 u
un,ef ly y fcd 16,67 N/mm²
f1cd 10,00 N/mm² y c x
Control del hormigón 1 by2
x by2
fcv 25 N/mm² S un,e
fyα,d 348 N/mm² 2d
S bx2
2d
Esfuerzos de cálculo
bx2
Fsd 350 kN
Nd,x 0 kN S 2d
lx Nd,y 0 kN
ly y Md 2
c x
by2
S un,ef
2d
bx2

<!-- p. 61 -->

DATOS GEOMÉTRICOS RELEVANTES

Datos de la superficie crítica Datos del área eficaz
u₁ 2,596 m bx,2 1,35 m
bx,1 1,11 m by,2 2,40 m
Ax,1 0,33 m² un,ef 4,14 m
by,1 1,92 m
Ay,1 0,58 m² Perímetro de comprobación
u₀ 0,90 m

OTROS VALORES DE INTERÉS

Coeficientes Tensiones axiales y tangenciales
β 1,40 u σ'cd 0,00 kN/m²
ξ 1,861 u τrd¹ 481,04 kN/m²
τrd²,min 634,51 kN/m²

CÁLCULOS

Comprobaciones para losas sin armadura de punzonamiento
τsd τrd
698,96 > 634,51 No cumple τsd≤τrd , requiere armadura de punzonamiento
kN/m² kN/m²

Dimensionado de armadura transversal de punzonamiento
Asw 2,25 cm²

Comprobación de la zona exterior a la armadura de punzonamiento
Fsd,ef Fext
490,00 \< 537,71 Cumple F sd,ef ≤F ext
kN kN

Comprobación de la limitación de la zona adyacente al soporte
Fsd,ef/(u₀d) 0,5*f1cd
2016,46 \< 5000,00 Cumple la limitación
kN/m² kN/m²

RESUMEN DE DATOS Y RESULTADOS

Interpretación de resultados
Requiere armadura

Resumen de resultados
Asw/CAPA 2,25 cm²
s 2,03 cm
capas 3

<!-- p. 62 -->

PRONTUARIO INFORMÁTICO DEL HORMIGÓN ESTRUCTURAL 3.1 SEGÚN EHE-08

Cátedra de Hormigón Estructural ETSICCPM - IECA

Obra: 1
Fecha: 18/07/2013

Hora: 18:13:04

Cálculo a punzonamiento

1 Datos

\- Materiales losa

Tipo de hormigón : HA-25
Tipo de acero : B-400-S
fck [MPa] = 25.00
fyk [MPa] = 400.00
c = 1.50
s = 1.15

\- Datos geométricos

Tipo de pilar : Pilar rectangular de borde
c1 [m] = 0.30
c2 [m] = 0.30
Canto útil de la losa d [m] = 0.27

\- Armado losa

l en zona critica de punzonamiento [·1.E-3] = 4
l en zona exterior a la armadura de punzonamiento [·1.E-3] = 4.0

Esquema de armado

\- Perímetros de cálculo

d [m] = 0.27
Perímetro de comprobación u0 [m] = 0.90
Perímetro crítico u1 [m] = 2.60
Perímetro exterior a la armadura de punzonamiento un,ef [m] = 3.95
\= 1.40

Página 1 de 2

<!-- p. 63 -->

\- Control del hormigón

Control normal

2 Dimensionamiento

Esfuerzo de cálculo en el perímetro crítico Fsd [kN] = 350
Esfuerzo de cálculo eficaz en el perímetro crítico Fsd,ef [kN] = 490.0
Esfuerzo de cálculo en el perímetro exterior a la armadura de
punzonamiento [kN] = 350.0
Ángulo de las ramas [º] = 90.0

Tensión media en el perímetro crítico sd [MPa] = 0.70
Tensión media en el perímetro exterior a la armadura de
dimensionamiento sd [MPa] = 0.63
'cd [MPa] = 0.00

En la zona exterior a la armadura propuesta
no se precisa disponer armadura.

Asw_estricta [cm²]= 2.2

número de capas por Asw Vsu Vsu+Vcu
[mm] ramas grupo [cm²] [kN] [kN]

12 6 3x2 4.7 327.7 661.7
14 6 3x2 6.8 471.7 805.7
16 6 3x2 12.1 839.4 1173.4
20 6 3x2 18.9 1311.4 1645.5

Página 2 de 2

<!-- p. 64 -->

DIMENSIONADO A RASANTE - SECCIONES RECTANGULARES

DATOS

s cp
As2Disposiciones relativas a la sección
b 0,40 m
t
d 0,27 m
p 0,40 m²/ml
L 1,00 m

Características de los materiales t s s
fck 25 N/mm² a
fyα,k 500 N/mm²
γc 1,50 s cp
γs 1,15
αcc 1,00 s As2 cp
fcd 16,67 N/mm²
fct,d 1,20 N/mm² t
fyα,d 400,00 N/mm² 400
Rugosidad 3
Solicitacion 1

Disposición de las armaduras
t
s 0,20 m s s
a
α 90 °

s cp
Esfuerzos de cálculo
ΔC o ΔT 400 kN
σcd 0 N/mm²

CÁLCULOS

Coeficientes
β1 0,20 Para cálculo sin armadura transversal
β2 0,20 Para cálculo con armadura transversal
μ 0,60

Cálculos previos
τr,d 3703,7 kN/m²

Comprobación en secciones sin armadura transversal
τr,u 167,58 kN/m² Requiere armadura

Comprobación en secciones con armadura transversal
2,5β(1,3-0,30fck/25)fctd = 299,2 kN/m²

RESULTADOS: DIMENSIONADO DE LA ARMADURA

Armadura transversal Dimensionado de la armadura (para 1ml)
Ast,min 0,80 cm² #b,TOTAL 10,00 ud
Ast 12,85 cm² Øst 14,00 mm

<!-- p. 65 -->

PRONTUARIO INFORMÁTICO DEL HORMIGÓN ESTRUCTURAL 3.1 SEGÚN EHE-08

Cátedra de Hormigón Estructural ETSICCPM - IECA

Obra: 1
Fecha: 17/09/2013

Hora: 20:35:05

Cálculo de juntas entre hormigones a rasante

1 Datos

\- Materiales

Tipo de hormigón: HA-25
Tipo de acero: B-500-S
fck [MPa] = 25.00
fyk [MPa] = 500.00

\- Tipo de Sección

Con armadura transversal

\- Rugosidad

\= 0.20
\= 0.60

\- Geometría

p [m] = .4
l [m] = 1.0

\- Resto datos
Ángulo de las armaduras = 90.0
Axil sobre la superficie de contacto Nd [kN] = 400
Tensión rasante de cálculo [MPa] = 3.8

2 Dimensionamiento

Sep. entre las barras que cosen la junta [cm] = 20

ru max [MPa] = 4.2
Ast,total [cm²] = 12.7

Página 1 de 1

<!-- p. 66 -->

ANCLAJE DE BARRAS O MALLAS

Volver al índice
DATOS

\= 5Ø
Características de los materiales
Ø
fck 25 N/mm² a= 5Ø Ø
γc 1,5
fct,d 1,20 N/mm² lb,neta
fyk 500 N/mm² Prolongación recta l b,neta
γs 1,15 u Gancho
fyd 434,8 N/mm² = 5Ø Ø
90º=a\<150
Ø
Características de las barras
Ø 25 mm
c 3 cm l b,neta lb,neta
As,mec. 11,85 cm² Patilla Gancho en U
As,real 12,57 cm²
Ø Ø = 0.6Øt
As,m/As,rea 0,94 ud.
Adherencia de las barras 2 = 5Ø
b,netal Tipologia de anclaje 2
Barra transversal soldada

FACTORES Y COEFICIENTES

m Coeficientes para lb no certificada
fyk η2 (1) 1,00 para Ø≤32
fck (2)
400 500 η2 0,92 para Ø=40
25 1,2 1,5
30 1,0 1,3 Coeficientes para lb certificada
35 0,9 1,2 m 1,50
40 0,8 1,1
45 0,7 1,0 Factores de reducción
50 0,7 1,0 βTRACC.(1) 0,70 para Ø≤8
βTRACC.(2) 1,00 para Ø>8
β βCOMP. 1,00
Tipo de anclaje Tracción Compr.
Prolongación recta -1,0 1,0
Patilla 1,0 1,0
Gancho 1,0 1,0
Gancho en U 1,0 1,0
Barra transversal soldada 0,7 0,7

RESULTADOS - barras aisladas

Certificada (cm)
lbnet
Ø TRACCION COMPRESIÓN
POS. I POS. II POS. I POS. II
6 15,98 22,83 24,22 34,59
8 21,31 30,44 32,29 46,12
10 26,63 38,05 40,36 57,66
12 45,66 65,22 48,43 69,19
14 53,27 76,09 56,50 80,72
16 60,88 86,97 64,57 92,25
20 76,09 108,71 80,72 115,31
25 95,12 135,88 100,90 144,14
32 121,75 173,93 129,15 184,50
40 165,42 236,32 175,47 250,68

<!-- p. 67 -->

PRONTUARIO INFORMÁTICO DEL HORMIGÓN ESTRUCTURAL 3.1 SEGÚN EHE-08

Cátedra de Hormigón Estructural ETSICCPM - IECA

Obra: 1
Fecha: 20/09/2013

Hora: 19:06:54

Cálculo de longitudes de anclaje y solapo

1 Datos

\- Materiales

Tipo de hormigón: HA-25
Tipo de acero: B-500-S
fck [MPa] = 25.00
fyk [MPa] = 500.00

2 Tabla de longitudes de anclaje de barras aisladas

Tipo de Análisis : Adherencia Simplificado
Adherencia barra : Certificada
Procedimiento de anclaje : Patilla
As/As,real : 0.94

Longitud [m]

Tracción Compresión

Posición I Posición II Posición I Posición II
[mm]

6 0.16 0.23 0.23 0.33
8 0.21 0.30 0.30 0.43
10 0.27 0.38 0.38 0.54
12 0.32 0.46 0.46 0.65
14 0.37 0.53 0.53 0.76
16 0.42 0.61 0.61 0.87
20 0.53 0.76 0.76 1.08
25 0.66 0.95 0.95 1.35
32 0.85 1.21 1.21 1.73
40 1.15 1.65 1.65 2.36

Página 1 de 1

<!-- p. 68 -->

EMPALME POR SOLAPO

Volver al índice
DATOS

Características de los materiales
fck 25 N/mm²
a
γc 1,5
fct,d 1,20 N/mm²
fyk 500 N/mm²
lb
γs 1,15 u
fyd 434,8 N/mm² Grupos de barras

Características de las barras
1,2 lb 1,2 lb 1,2 lb Ø 20 mm
a 15 cm
AS,mec.tot 12,9 cm²
AS1,real 12,57 cm²
AS2,real 1,05 cm²
1,3 lb 1,3 lb 1,3 lb 1,3 lb As,real 13,62 cm²
%As,tracc. 92,29 %
Tipología de barras 2
Adherencia de las barras 1
Posición de las armaduras 1
Tipo de adherencia 1
τbd ― N/mm²

FACTORES Y COEFICIENTES

m α
fyk % de As trabajando a tracción con respecto a As,total
fck a Compres.
400 500 20 25 33 50 >50
25 1,2 1,5 ≤ 10Ø 1,2 1,4 1,6 1,8 2 1
30 1,0 1,3 >10Ø 1 1,1 1,2 1,3 1,4 1
35 0,9 1,2
40 0,8 1,1
45 0,7 1,0
50 0,7 1,0

RESULTADOS

Longitud básica de anclaje Longitud de solapo
lb 60,00 cm ls ― cm
lsupl 216,0 cm
Longitud neta de anclaje Sempalmes 72,00 cm
lb,neta 56,83 cm

<!-- p. 69 -->

INESTABILIDAD DE SOPORTES

Volver al índice
DATOS

Pórtico Características de los materiales
Tipo de estructura 2 fck 25 N/mm²
γc 1,50 ud.
Pilar A-B fcd 16,67 N/mm²
bAB 0,30 m fyk 400 N/mm²
hAB 0,50 m γs 1,15
LAB 5,00 m fyd 347,83 N/mm²
dAB' 0,05 m εy 1,74E-03 ud.
d 0,45 E 3,20E+04 N/mm²
Ac 0,15 m²
IAB,z 312500 cm⁴ Esfuerzos de cálculo
Disposición de las armaduras: 3 Md,zA 108,4 m·kN
Viga D-A Md,zB 164,9 m·kN
bDA 0,3 m Nd 158,9 kN
hDA 0,5 m
x
LDA 5 m Md,zA
IDA,z 312500 cm⁴
Viga A-F
bAF 0,3 m h
hAF 0,5 m
LAF 5 m
b
IAF,z 312500 cm⁴
Pilar E-A
bEA 0,30 m
hEA 0,30 m
LEA 5,00 m
E
IEA,z 67500 cm⁴
Viga C-B
bCB 0,3 m
hCB 0,5 m D F
LCB 5 m
A ICB,z 312500 cm⁴
Viga B-G
bBG 0,3 m
hBG 0,5 m
LBG 5 m
IBG,z 312500 cm⁴ C B G
Pilar B-H
bBH 0,30 m
hBH 0,30 m
LBH 5,00 m x
IBH,z 67500 cm⁴ H

y z
CÁLCULOS Y RESULTADOS

Factores y coeficientes Esbelteces Excentricidades y esfuerzos
ψA 0,61 λinf 68,35 cm ee 0,90 m
ψB 0,61 λmec 24,80 cm ea 0,0214 m
e₁ 0,68 ud. No pandea etot 1,04 m
e₂ 1,04 ud. Nd 158,90 kN
υ 0,06 ud. Longitud de pandeo Md,z 164,90 m·kN
C 0,16 ud. α 0,72
β 1,50 ud. l₀ 3,58 m

<!-- p. 70 -->

PRONTUARIO INFORMÁTICO DEL HORMIGÓN ESTRUCTURAL 3.1 SEGÚN EHE-08

Cátedra de Hormigón Estructural ETSICCPM - IECA

Obra: 1
Fecha: 18/09/2013

Hora: 17:39:13

Cálculo de soportes a pandeo

1 Datos

\- Materiales

Tipo de hormigón : HA-25
Tipo de acero : B-400-S
fck [MPa] = 25.00
fyk [MPa] = 400.00
c = 1.50
s = 1.15

\- Sección

Sección : EJEMPLO2
b [m] = 0.30
h [m] = 0.50
r [m] = 0.050

nº barras horizontales = 4
nº barras verticales = 3

\- Disposición de armadura del pilar

Distribuida por todo el perímetro

\- Estructura

Tipo : Intraslacional
L [m] = 5

Vinculación de los extremos del soporte :

Elemento b h l
estructural [m] [m] [m]

Pilar superior 0.3 0.3 5
Viga superior izquierda 0.3 0.5 5
Viga superior derecha 0.3 0.5 5

Página 1 de 3

<!-- p. 71 -->

Elemento b h l
estructural [m] [m] [m]

Pilar inferior 0.3 0.3 5
Viga inferior izquierda 0.3 0.5 5
Viga inferior derecha 0.3 0.5 5

2 Comprobación

[mm] = 20
Nd [kN] = 158.9
Md,sup [kN·m] = 108.4
Md,inf [kN·m] = 158.9
inf = 75.11
etot [m] = 0.894
Mu* [kN·m] = 311.6
Nu [kN] = 311.6
\= 1.96

(*)Momento de 1er orden que produce la rotura (máximo momento en el soporte)

Plano de deformación de agotamiento

x [m] = 0.13
1/r [1/m]·1.E-3 = 26.7
s ·1.E-3 = 3.5
i ·1.E-3 = -9.8

Deformación y tensión de armaduras superior e inferior

Profundidad Deformación Tensión
[m] ·1.E-3 [MPa]
0.05 2.2 348
0.45 -8.5 -348

\- Parámetros de esbeltez

Longitud de pandeo l0 [m] = 3.58
Esbeltez mecánica = 25

A = 0.61
B = 0.61
\= 0.72

\- Parámetros de cálculo del método aproximado

ic [m] = 0.1443

Página 2 de 3

<!-- p. 72 -->

is [m] = 0.1789
y = 0.0017
\= 1.25

Página 3 de 3

<!-- p. 73 -->

E.L.S. DEFORMACIONES Y FLECHAS - SECCIONES RECTANGULARES

Volver al índice
DATOS

Tipo de vano: 3 Sistema estructural:
Biempotrado 1

Apoyado-

Biapoyado

Voladizo

CARACTERÍSTICAS GEOMÉTRICAS Y MATERIALES

Dimensionado de la sección Disposición de las armaduras
L 10 m #bS1 3 ud.
hc 0,5 m ØS1 25 mm
bc 0,3 m AS1 14,73 cm²
rinf 0,05 m #bS2 5 ud.
dc 0,45 m ØS2 12 mm
AS2 5,65 cm²
Características de los materiales: ρS,TOTAL 1,36 %
fck(i) 15 N/mm²
fctm,fl(i) 2,92 N/mm²
fck(n) 25 N/mm²
fctm,fl(n) 4,10 N/mm²
fyk 500 N/mm²
γs 1,15 u
fyd 434,8 N/mm²

ACCIONES DE CÁLCULO *NOTA: En vigas biapoyadas y biempotradas qd≥qi

qd P q
qi +M

g
L a b c d e f

Acciones iniciales (descimbrado) Acciones a los n días
qizq (i) 0 m·kN qizq (n) 0 m·kN
qder(i) 0 m·kN qder(n) 0 m·kN
P(i) 50 kN P(n) 60 kN
a 5 m a 5 m
b 5,00 m b 5,00 m
M(i) 0 m·kN M(n) 0 m·kN
c 0 m c 3 m
d 10,00 m d 7,00 m
q(i) 0 m·kN q(n) 0 m·kN
e 0 m e 2 m
f 10,00 m f 8,00 m
g 2 m g 2 m

<!-- p. 74 -->

CÁLCULOS PREVIOS

Comprobación previa: Cálculos previos: descimbrado y n días
L/d 22,22 ud. Es 200000 N/mm²
L/d * 20,00 ud. *Tabla 50.2.2.1.a Mf 36,48 m·kN
X/d 0,31
Ib 3,13E-03 m⁴
If 1,29E-03 m⁴

Inercias y módulos de def. en descimbrado Inercias y módulos de def. en n días
Ec (i) 28403,12 N/mm² Ec (n) 32035,25 N/mm²
Ie(i) 1,34E-03 m⁴ Ie(n) 1,32E-03 m⁴
I(i) 1,34E-03 m⁴ I(n) 1,32E-03 m⁴
E·I 3,80E+04 kN·m² E·I 3,74E+04 kN·m²

RESULTADOS

Esfuerzos y deformaciones máximos Factor λ (cálculo de fdif)
MMAX i 125,00 m·kN Duración de la/s carga/s 1
finsti 27,43 mm λ 1,65 ud
MMAX n 150,00 m·kN ξ 2,00 ud
finstn 33,40 mm ρ' 4,19 ‰

Cálculo de las flechas totales y activas
fdifi 45,36 mm
fdifn 55,23 mm
fTOTAL 155,45 mm
fACTIVA 110,09 mm

<!-- p. 75 -->

PRONTUARIO INFORMÁTICO DEL HORMIGÓN ESTRUCTURAL 3.1 SEGÚN EHE-08

Cátedra de Hormigón Estructural ETSICCPM - IECA

Obra: 1
Fecha: 26/09/2013

Hora: 22:48:02

Comprobación del Estado Límite de deformaciones en vigas

1 Datos

\- Materiales

Tipo de hormigón : HA-25
Tipo de acero : B-500-S
fck [MPa] = 25.00
fyk [MPa] = 500.00
c = 1.50
s = 1.15

\- Seccion centro de vano

Sección : EJEMPLO1
b [m] = 0.30
h [m] = 0.50
ri [m] = 0.100
rs [m] = 0.050
A_i [cm2] = 20.00
A_s [cm2] = 5.00

\- Estructura

Longitud [m] = 10.0

Vinculación de los extremos de la viga :
Extremo izquierdo : Apoyo
Extremo derecho : Apoyo

\- Cargas

CARGA ACTUANTE AL DESCIMBRAR

Edad de carga [dias] = 14

Cargas puntuales :

xp P
[m] [kN]

5 50

Página 1 de 3

<!-- p. 76 -->

RESTO DE CARGA PERMANENTE

Edad de carga [dias] = 28

Cargas puntuales :

xp P
[m] [kN]

5 60

SOBRECARGA DE USO

2 Resultados

\- Resumen resultados

Flecha total [mm] = 143.2
Flecha total/Longitud = 1 / 70
Flecha activa [mm] = 109.6
Flecha activa/Longitud = 1 / 91
\- Tabla deformaciones

Instantáneas Diferidas Total Activa

q1 q2 q3 d* dq1 dq2+d*

x
[m] [mm] [mm] [mm] [mm] [mm] [mm] [mm] [mm]

0.00 0.0 0.0 0.0 0.0 0.0 0.0 0.0 0.0
0.20 1.7 2.2 0.0 0.0 2.2 2.5 8.6 6.6
0.40 3.4 4.3 0.0 0.0 4.5 4.9 17.2 13.1
0.60 5.1 6.5 0.0 0.0 6.7 7.3 25.7 19.6
0.80 6.8 8.6 0.0 0.0 8.9 9.7 34.1 26.1
1.00 8.5 10.7 0.0 0.0 11.1 12.1 42.4 32.4
1.20 10.1 12.8 0.0 0.0 13.2 14.5 50.6 38.7
1.40 11.7 14.8 0.0 0.0 15.3 16.7 58.6 44.8
1.60 13.3 16.8 0.0 0.0 17.3 19.0 66.4 50.8
1.80 14.8 18.7 0.0 0.0 19.3 21.2 74.0 56.6
2.00 16.3 20.6 0.0 0.0 21.2 23.3 81.4 62.2
2.20 17.7 22.4 0.0 0.0 23.1 25.3 88.4 67.7
2.40 19.1 24.1 0.0 0.0 24.9 27.2 95.2 72.8
2.60 20.3 25.7 0.0 0.0 26.5 29.1 101.7 77.8

Página 2 de 3

<!-- p. 77 -->

2.80 21.6 27.2 0.0 0.0 28.1 30.8 107.8 82.4
3.00 22.7 28.7 0.0 0.0 29.6 32.4 113.5 86.8
3.20 23.8 30.0 0.0 0.0 31.0 33.9 118.7 90.8
3.40 24.7 31.3 0.0 0.0 32.3 35.3 123.6 94.6
3.60 25.6 32.4 0.0 0.0 33.4 36.6 128.0 97.9
3.80 26.4 33.3 0.0 0.0 34.4 37.7 131.9 100.9
4.00 27.1 34.2 0.0 0.0 35.3 38.7 135.2 103.5
4.20 27.6 34.9 0.0 0.0 36.0 39.5 138.0 105.6
4.40 28.1 35.5 0.0 0.0 36.6 40.1 140.3 107.3
4.60 28.4 35.9 0.0 0.0 37.1 40.6 141.9 108.6
4.80 28.6 36.1 0.0 0.0 37.3 40.9 142.9 109.3
5.00 28.7 36.2 0.0 0.0 37.4 41.0 143.2 109.6
5.20 28.6 36.1 0.0 0.0 37.3 40.9 142.9 109.3
5.40 28.4 35.9 0.0 0.0 37.1 40.6 141.9 108.6
5.60 28.1 35.5 0.0 0.0 36.6 40.1 140.3 107.3
5.80 27.6 34.9 0.0 0.0 36.0 39.5 138.0 105.6
6.00 27.1 34.2 0.0 0.0 35.3 38.7 135.2 103.5
6.20 26.4 33.3 0.0 0.0 34.4 37.7 131.9 100.9
6.40 25.6 32.4 0.0 0.0 33.4 36.6 128.0 97.9
6.60 24.7 31.3 0.0 0.0 32.3 35.3 123.6 94.6
6.80 23.8 30.0 0.0 0.0 31.0 33.9 118.7 90.8
7.00 22.7 28.7 0.0 0.0 29.6 32.4 113.5 86.8
7.20 21.6 27.2 0.0 0.0 28.1 30.8 107.8 82.4
7.40 20.3 25.7 0.0 0.0 26.5 29.1 101.7 77.8
7.60 19.1 24.1 0.0 0.0 24.9 27.2 95.2 72.8
7.80 17.7 22.4 0.0 0.0 23.1 25.3 88.4 67.7
8.00 16.3 20.6 0.0 0.0 21.2 23.3 81.4 62.2
8.20 14.8 18.7 0.0 0.0 19.3 21.2 74.0 56.6
8.40 13.3 16.8 0.0 0.0 17.3 19.0 66.4 50.8
8.60 11.7 14.8 0.0 0.0 15.3 16.7 58.6 44.8
8.80 10.1 12.8 0.0 0.0 13.2 14.5 50.6 38.7
9.00 8.5 10.7 0.0 0.0 11.1 12.1 42.4 32.4
9.20 6.8 8.6 0.0 0.0 8.9 9.7 34.1 26.1
9.40 5.1 6.5 0.0 0.0 6.7 7.3 25.7 19.6
9.60 3.4 4.3 0.0 0.0 4.5 4.9 17.2 13.1
9.80 1.7 2.2 0.0 0.0 2.2 2.5 8.6 6.6
10.00 0.0 0.0 0.0 0.0 0.0 0.0 0.0 0.0

Página 3 de 3

<!-- p. 78 -->

FISURACIÓN

Volver al índice
DATOS

Dimensiones de la sección Características de los materiales
hc 0,5 m fck,j 25 N/mm²
bc 0,3 m fctm,fl 4,10 N/mm²
c 0,1 m Acciones 1 *Art.49.2.4 (EHE-08), para obtención de β
d 0,40 m 0,6*fck,j 15,00 N/mm²
β 1,30 ud
Armadura principal a tracción
ØS 16 mm Area eficaz del hormigón
\#bS 3 ud Tipo de Ac,eficaz 1 *Figura 49.2.4.b (EHE-08)
S 10 cm Ac,eficaz 0,066 m²
As 6,03 cm²

Ac, ef
Ac, ef
Ac, ef Ac, ef

CASO 1a CASO 1b CASO 2 CASO 3
Figuras obtenidas de: Figura 49.2.4.b (EHE-08)
Esfuerzos de cálculo
Md 60 m·kN
Nd 0 kN * Tracción [+]
Tipo de carga 2

CÁLCULOS

Mf 32,06 m·kN
σs 310,85 N/mm²
σsr 166,11 N/mm²
sm 307,54 mm
εsm 1,33 ‰

RESULTADO

Abertura característica de la fisura
wk 0,53 mm

Abertura máxima de fisura
Clases de exposición wmáx [mm]
I 0,4
IIa, IIb, H 0,3

IIIa, IIIb,IV,F,Qa 0,2
IIIc, Qb, Qc 0,1

<!-- p. 79 -->

PRONTUARIO INFORMÁTICO DEL HORMIGÓN ESTRUCTURAL 3.1 SEGÚN EHE-08

Cátedra de Hormigón Estructural ETSICCPM - IECA

Obra: 1
Fecha: 26/09/2013

Hora: 22:27:26

Comprobación del Estado Límite de Servicio de fisuración debido a solicitaciones normales

1 Datos

\- Materiales

Tipo de hormigón: HA-25
Tipo de acero: B-500-S
fck [MPa] = 25,00
fyk [MPa] = 500,00

\- Ambiente

Clase general de exposición : I
Clases específicas de exposición : Qb

\- Geometría de la sección

Sección : EJEMPLO1
b [m] = 0,30
h [m] = 0,50

\- Armado de la sección

[mm] = 16

Separación
capa nº barras
[mm]

1 3 108.0

As [cm²] = 6.0
Ac,ef [cm²] = 684.0

2 Resultados

Mk [kN·m] = 60

Separación media entre fisuras sm [mm] = 301.0
Deformación media de las armaduras sm [·1.E-3] = 1.12

Página 1 de 2

<!-- p. 80 -->

Tensión en las armaduras en el instante de fisuración sr [MPa] = 169.3
Tensión en las armaduras en servicio s [MPa] = 275.7
Abertura característica de fisura wk [mm] = 0.57

wk max [mm]
Clase de exposición
Armado Pretensado

I 0.4 0.2

IIa, IIb, H 0.3 0.2

IIIa, IIIb, IV, F 0.2
Decompresión
IIIc, Qa, Qb, Qc 0.1

Página 2 de 2

<!-- p. 81 -->

Prontuario en Excel de Hormigón Armado (Adaptado a EHE-08)

\6. BIBLIOGRAFÍA

Memoria 80

<!-- p. 82 -->

Prontuario en Excel de Hormigón Armado (Adaptado a EHE-08)

LIBROS:

Navés Viñas, Francesc; Llorens Sulivera, Miquel. Cálcul d’estructures. Edicions UPC, 1995.
Número de ISBN: 84-8301-208-01

García Meseguer, A.; Morán Cabré, F.; Arroyo Portero, J.C. Jimenez Montoya Hormigón
Armado:15ª Edición basada en la EHE-2008 Ajustada al Código Modelo y al Eurocódigo EC-2.
Editorial Gustavo Gili, SL, Barcelona, 2009. Número de ISBN: 978-84-252-2307-5

Gómez Bernabé, Pepa; Gómez Serrano, José. Estructures de formigó armat:
Predimensionament i càlcul de seccions. Edicions UPC, 2002. Número de ISBN: 84-8301-586-2

Borlado, R.; Martínez, C.; Martínez, R. Prontuario de estructuras metálicas (6ª Edición). CEDEX
(Centro de Estudios y Experimentación de Obras públicas), Ministerio de Fomento, Edición
\2002. Número de ISBN: 84-7790-371-9

Empresa Nacional Siderúrgica, S.A. Prontuario ENSIDESA. Manual para el cálculo de
estructuras metálicas. Tomo 1: Valores estáticos. Resistencia de Materiales. Estructuras
elementales. Ed: Gráficas Reunidas, S.A., año 1975. Número de ISBN: 84-500-6777-4

NORMATIVAS:

Ministerio de Fomento. EHE-08. Instrucción de Hormigón Estructural. Madrid: Ministerio de
Fomento. Centro de publicaciones, 2008. ISBN: 978-84-498-0825-8

Ministerio de fomento. Código Técnico de la Edificación. Madrid: Ministerio de Fomento.
Centro de publicaciones, 2008. ISBN: 978-84-267-1434-3

WEBS:

Título: Mecánica de Sólidos y Sistemas Estructurales- Año 2007
Autor: Departamento de Estructuras de Edificación de Escuela Técnica Superior de
Arquitectura de Madrid 10-5-2007
http://www.aq.upm.es/Departamentos/Estructuras/e96-290/doc/hafs1.pdf

Título: Soporte técnico de Excel. Autor: Microsoft.
http://office.microsoft.com/es-es/support/?CTT=97

Título: ExcelTotal (Blog con tutoriales para la utilización de Excel); Autor: Moisés Ortiz; Última
actualización: 20 de Junio de 2013: http://exceltotal.com/

Título: Cálculo de Flechas por el Método de Branson. Autor: J.F. Bissio;
http://www.ing.unlp.edu.ar/construcciones/hormigon/ejercicios/TP5-Flechas.pdf

Título: Concret Online. Autor: PROIN S.L. http://www.concretonline.com/

Título: Tema 11. Estado límite de fisuración. Autores: Alfonso Cobo Escamilla y Luis Felipe
Rodríguez Martín; Universidad Nacional de Educación a Distancia http://www.uned.es/dptoicf/estructuras_varias/images/Pret-11_peq.pdf

Memoria 81

<!-- p. 83 -->

Prontuario en Excel de Hormigón Armado (Adaptado a EHE-08)

CONCLUSIONES

En este trabajo he calculado todas las situaciones de comprobación y
dimensionado de secciones, si bien no he tenido en cuenta el
pretensado en ninguna hoja.

He encontrado muchas limitaciones y dificultades por el hecho de
utilizar Excel, dado que resulta muy complejo corregir errores o
modificar algunos cálculos o procedimientos, por lo que he tenido que
invertir más horas de las deseadas en algunos apartados. Pero quiero
destacar lo práctico que resulta de cara al usuario el poder utilizar este
programa, y decir que se ha intentado que ninguna hoja de cálculo
ocupe más de dos folios, por lo que resulta muy sencilla su impresión
para poder trasladar los cálculos al papel.

Otra característica positiva del uso del Excel, es la posibilidad de ocular
y/o mostrar fórmulas a placer, y lo sencillo que resulta el bloqueo y
desbloqueo de las hojas, para su modificación si se diera el caso.

Me ha gustado mucho realizar este trabajo porque me ha servido para
profundizar ampliamente en la normativa y en la comprensión del
cálculo de estructuras

La guinda que pone el punto final a este trabajo es el esfuerzo de
realizar una comparativa con un aplicativo semejante, y el haber
modificado algunas de las hojas de cálculo para poder implementar
algunas mejoras derivadas de esa comparación.

Memoria 82
