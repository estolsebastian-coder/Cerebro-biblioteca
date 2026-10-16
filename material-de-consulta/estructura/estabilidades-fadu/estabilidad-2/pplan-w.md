---
type: libro
title: "PPLAN_W"
author: "Estabilidad"
categoria: "ESTRUCTURA"
paginas: 15
extraccion: "texto"
fuente: "local:E:/MATERIAL DE CONSULTA/ESTRUCTURA/ESTABILIDADES FADU/estabilidad 2/PPLAN_W.pdf"
convertido: 2026-10-16
---

# PPLAN_W

> Texto extraído de `ESTRUCTURA\ESTABILIDADES FADU\estabilidad 2\PPLAN_W.pdf` (15 páginas, texto). El PDF original está en el disco E: (MATERIAL DE CONSULTA); `<!-- p. N -->` marca el inicio de cada página.

<!-- p. 1 -->

GUIA PARA LA APLICACIÓN DEL PROGRAMA PPLAN WINDOWS
EN EL CURSO DE ESTABILIDAD II

ALCANCE DE SU UTILIZACIÓN EN EL CURSO

El PPlan es un programa que calcula estructuras esquematizables en el plano, tanto de
hormigón como de acero o madera, a partir del ingreso de los datos correspondientes a la
forma, dimensiones, vínculos, cargas y características de los materiales que las componen. En
el curso de Estabilidad 2 emplearemos este programa como herramienta en el ejercicio de
diseño para la obtención de reacciones, solicitaciones y deformada de una estructura
aporticada, preferentemente en hormigón armado. Si bien el programa permite también la
verificación y determinación de armaduras de las secciones propuestas, en el curso no
utilizaremos esta posibilidad. En el desarrollo del ejercicio de diseño se dejará a cargo del
alumno la determinación de la viabilidad de las formas proyectadas a partir de las solicitaciones
obtenidas con el programa y de acuerdo a los métodos y criterios planteados a lo largo del
curso.

PROGRAMA

Definir una estructura no es una tarea sencilla, los datos a ingresar son muchos y de
características muy diferentes, tales como la tipología de la estructura, las restricciones,
geometría, cargas etc.

En Argentina se ha desarrollado un programa de cálculo bidimensional de estructuras y de
dimensionamiento en Hormigón Armado, Acero y Madera, según normas CIRSOC 201,301 y
DIN 4114.

El P-plan se comercializa dentro del Pack Construction 2000, que incluye el E-Plan W para
Cálculo y Dimensionamiento de emparrillados de vigas, y el REM W para Cálculo y
Dimensionamiento de reticulados metálicos espaciales.

El programa que se utilizará en el curso es PPlan W (PPlan Windows).

Tanto el P-Plan como el E-Plan y el R.E.M. han adoptado, desde su versión D.O.S. hace más
de 10 años, el ingreso de datos a través de un lenguaje de definiciones. Esta metodología, si
bien inicialmente puede requerir de un tiempo mayor de entrenamiento, le confiere a los
programas la capacidad de trabajar con estructuras grandes y complejas, con miles de valores,
que de otra forma sería imposible administrar.
El ingreso del lenguaje se realiza a través de un procesador de textos en la ventana de Texto
del programa, con los comandos y operaciones clásicas.

El programa PPlan Windows que se instala es una Versión de Evaluación, es decir es una
versión de demostración del alcance que tiene el programa, que como tal no tiene costo, pero
que a su vez tiene una limitante en cuanto a la cantidad de cargas que considera al momento
de realizar el cálculo, ya que sólo considera las primeras diez cargas en barras y nodos que
fueron ingresadas. El programa deja ingresar todas las cargas que se quiera, pero al momento
de calcular la estructura sólo considera las primeras diez cargas que fueron ingresadas.
La versión de PPlan para DOS, no presenta esta limitante; llegado el momento se analizará
con el docente a cargo si se opta por:
§ realizar algunas simplificaciones en la cantidad de cargas que presente el pórtico para
poder utilizar la versión PPlan Windows,
§ en el caso que las simplificaciones no sean posibles porque implicaría un cambio
sustancial en la estructura adoptada, se utilizará la versión de PPlan de DOS.

ESTABILIDAD DE LAS CONSTRUCCIONES II | FACULTAD DE ARQUITECTURA | UdelaR 1

<!-- p. 2 -->

GUÍA PARA SU APLICACIÓN

A continuación se darán una serie de indicaciones básicas relacionadas con el ingreso de
datos, el lenguaje utilizado y algunas definiciones.

En cuanto al manejo general del programa (Lenguaje PPlan, Unidades y Convención de
Signos), el alumno podrá obtener esta información en la opción “Ayuda General” del Menú
Principal del Programa, en los siguientes ítems:

Introducción
§ Para mayor información
§ Requerimientos
§ Alcances y Limitaciones
§ Conceptos Fundamentales. Lenguaje PPlan
§ Manejo General
§ Ejemplo Inicial

El Lenguaje PPlan
§ Ventana de Texto.
œ Títulos Valores y Comentarios
œ Corregir y Mensajes
§ Unidades
§ Convención de signos
§ Convención de Títulos

§ Comandos del Procesador de textos

Opciones del Programa
§ Proyectos
§ Imprimir
§ Gráfico
§ Tablas
§ Cálculo.
§ Animaciones

ESTABILIDAD DE LAS CONSTRUCCIONES II | FACULTAD DE ARQUITECTURA | UdelaR 2

<!-- p. 3 -->

EJEMPLO

Se desea calcular un pórtico de las siguientes características:

ESTABILIDAD DE LAS CONSTRUCCIONES II | FACULTAD DE ARQUITECTURA | UdelaR 3

<!-- p. 4 -->

Veremos a continuación cómo se ingresan los datos de la misma paso a paso, y las
consideraciones que tomaremos para el Curso de Estabilidad II.

NODOS

DESCRIPCIÓN:
El título Nodos puede ingresarse en cualquier parte del texto.
Los nodos deben ser definidos en orden creciente, aunque no es necesario que sean
correlativos.
No pueden definirse nodos coincidentes, es decir, dos nodos con las mismas coordenadas
X e Y.
Se ingresa un nodo por renglón.

Nodos
Nro. Cx Cy Art
e>0 r r 1/0
X X X -
L L

Nro. Es el número a asignar al Nodo.
Cx. Coordenada en X del nodo.
Cy. Coordenada en Y del nodo.
Art. Articulado Si o No (1 ó 0)

CONSIDERACIONES DEL CURSO:
Los nodos son puntos de la estructura que interesa definir o ubicar por algún motivo en
especial, ya sea porque se trata de vínculos (simples, dobles o triples), o porque existe una
carga puntual en una barra, o puede ser una barra que cambie de inercia en determinado
punto, o una barra que cambie de carga distribuida en determinado punto, etc.

Para nuestro caso ingresaremos:

Nodos
\* Nro Coord-X Coord-Y (Articulado 1/0)
1 0 0
2 4.5 6
3 13.5 0
4 13.5 6

BARRAS

DESCRIPCIÓN:
El título Barras puede ingresarse en cualquier parte del texto.
Las barras deben ser definidas en orden creciente, aunque no es necesario que sean
correlativas.
El Nodo inicial Ni y el Nodo final Nj deben haber sido definidos previamente.
El Nodo inicial Ni siempre debe ser de menor numeración que el final (Nj).
No puede definirse más de una barra con los mismos nodos Ni y Nj
Se ingresa una barra por renglón.

Barras
Nro. Ni Nj Art-i Art-j
e>0 r r 1/0 1/0
X X X A A

ESTABILIDAD DE LAS CONSTRUCCIONES II | FACULTAD DE ARQUITECTURA | UdelaR 4

<!-- p. 5 -->

Nro. Número a asignar a la Barra.
Ni. Nodo inicial de la Barra.
Nj. Nodo final de la Barra.
Art-i. Articulada en su extremo inicial Si o No (1 ó 0)
Art-j. Articulada en su extremo final Si o No (1 ó 0)

Para nuestro caso ingresaremos:
Barras
\* Nro. Desde-i Hasta-j (Art-i 1/0) (Art-j 1/0)
1 1 2
2 2 4
3 3 4

RESTRICCIONES

DESCRIPCIÓN:

El título Restricciones puede ingresarse en cualquier parte del texto.
El Nodo a restringir debe haber sido previamente definido.
Los vínculos se expresan indicando el nodo, luego la restricción según x, según y y
finalmente la restricción al giro. El número 0 indica que no hay restricción mientras que el
número 1 indica que existe restricción, o sea el nudo está impedido de moverse en esa
dirección.

Restricciones
Nro. Rx Ry Rg Co-X Co-Y Co-G E-X E-Y E-G
e>0 1/0 1/0 1/0 r r R r r R
X X X X AB AB AB B B B
L L G F/L F/L F*L/G

Nro. Número del Nodo que se desea restringir.
Rx. Restringido en coordenada X Si o No (1 ó 0)
Ry. Restringido en coordenada Y Si o No (1 ó 0)
Rg. Restringido al giro Si o No (1 ó 0)
Co-X. Corrimiento del Nodo en la coordenada X
Co-Y. Corrimiento del Nodo en la coordenada Y
Co-G. Giro del Nodo.
E-X. Valor del resorte equivalente en la coordenada X
E-Y. Valor del resorte equivalente en la coordenada Y
E-G. Valor del resorte equivalente al giro

CONSIDERACIONES DEL CURSO: Los siguientes campos no se utilizan: “Co-X”, “Co-Y”,
“Co-G”, “E-X”, “E-Y” y “E-G”.

Restricciones posibles:
Movimiento Movimiento
Giros en sentido X en sentido Y
X Y Θ
Vínculo simple: 0 1 0
Apoyo deslizante (“carrito”) o Biela
Vínculo Doble: Articulación 1 1 0
Vínculo Triple: Empotramiento 1 1 1
Empotramiento deslizante (*) 1 0 1

(*) Empotramiento deslizante: es utilizado para estructuras simétricas (iguales cargas,
luces, secciones y apoyos); se ingresa la mitad de la estructura y en el eje de simetría se
ingresa ese punto como un empotramiento deslizante. Sólo se desliza verticalmente, no se
puede desplazar horizontalmente ni girar.

ESTABILIDAD DE LAS CONSTRUCCIONES II | FACULTAD DE ARQUITECTURA | UdelaR 5

<!-- p. 6 -->

Para nuestro caso ingresaremos:

Restricciones
\* Nodo R-X R-Y R-G (C-x) (C-y) (C-g) (K-x) (K-y) (K-g)
1 1 1 1
3 1 1 1

MATERIALES

DESCRIPCIÓN:
En el programa, el título Materiales puede ingresarse de tres formas diferentes en cualquier
parte del texto:
\1. Material Genérico (es la forma que se utilizará en el curso)
Cuando se define un material genérico se ingresan los valores mínimos para el
cálculo. Las barras a las que se asignó ese materiales NO podrán ser
dimensionadas.

Materiales
Nro E CT
e>0 r r
X X X
F/L^2

Nro. Número de Material a definir.
E. Módulo de elasticidad del Material
Ct. Coeficiente de dilatación térmica. Siempre en 1/Gc (grados centígrados)

\2. Material Hormigón
Para poder dimensionar en Hormigón Armado

\3. Material Acero
Para poder dimensionar en Acero

Se puede definir más de un tipo de material (Ej.: Hormigón y Acero):

Materiales
\* Nro E cT
1 200,000kg/cm^2 0.00001 ---- (Hormigón)
2 2,100,000kg/cm^2 0.00001 ---- (Acero)

El número de Material debe ser correlativo, comenzando desde el nro 1.

CONSIDERACIONES DEL CURSO: dado que en el curso se estudia el hormigón armado
como material estructural, sólo se trabajará con este tipo de material; salvo algunas
excepciones que justifiquen el diseño adoptado y que fueran acordadas con el docente.
Para el ingreso de los datos del material se utilizará la forma “Material Genérico” descrita.

Para nuestro caso ingresaremos:

Materiales
\* Nro E cT
1 200,000kg/cm^2 0.00001

Para ingresar la unidad del módulo de elasticidad de un material (kg/cm2), hay que tener
en cuenta que, cm2 se tomará como un error, deberá ingresar cm^2 para centímetros
cuadrados.
Desde cualquier teclado, la manera universal de ingresar el símbolo ^ es, manteniendo
pulsada la tecla [Alt], se oprime el número [94] desde el panel numérico ubicado
generalmente en la parte derecha del teclado.

ESTABILIDAD DE LAS CONSTRUCCIONES II | FACULTAD DE ARQUITECTURA | UdelaR 6

<!-- p. 7 -->

SECCIONES

DESCRIPCIÓN:

El título Secciones puede ingresarse en cualquier parte del texto, de cuatro maneras
diferentes:

\1. Ingreso de Secciones genéricas.
Permite definir secciones genéricas con los parámetros mínimos para el cálculo de la
estructura.

\2. y 3. Ingreso de Secciones de Hormigón.
Estos dos modos permiten ingresar secciones rectangulares y tipo "T". Al dimensionar
en Hormigón Armado se utilizarán estos valores para las barras asignadas a dicha
sección. El sistema determinará los valores de F y J para el cálculo basado en las
dimensiones ingresadas.

Secciones rectangulares:
Secciones
Nro Tipo b d h hp
e>0 [R] r r r r
X X X X X X
L L L L

Nro Número de la sección a definir
Tipo La letra [R] para secciones rectangulares
b,d,h,h” Dimensiones según la figura.

Secciones tipo "T":
Secciones
Nro Tipo b d b0 d0 h hp
e>0 [T] r r r r r r
X X X X X X X X
L L L L L L

Nro Número de la sección a definir
Tipo La letra [T] para secciones tipo “T”
b,d,b0,d0,h,h” Dimensiones según la figura.

4 . Ingreso de Perfiles de Acero.
Este último modo permite el ingreso de Perfiles de Acero previamente definidos en la
tabla de Perfiles, bajo la opción de Dimensionamiento del Menú.

Secciones
Nro F J Tipo Código Invertido
e>0 r r e>0 e “I”
X X X X X A
L^2 L^4

Nro. Número de la sección a definir.
F. Area de la sección
J. Momento de Inercia de la sección
Tipo Tipo de Perfil metálico.
Código Código del Perfil metálico.
Invertir Solamente cuando se desea utilizar el perfil invertido, deberá ingresarse
la letra "I" (i latina). En caso contrario deberá dejarse en blanco.

ESTABILIDAD DE LAS CONSTRUCCIONES II | FACULTAD DE ARQUITECTURA | UdelaR 7

<!-- p. 8 -->

Cuando se definen los valores de Tipo y Código deberá ingresarse 0(cero) para el valor
de F y el valor de J. Es decir, si se define el perfil de acero a utilizar NO deberán
ingresarse los valores F y J pues los mismos surgirán de los valores de la tabla de
perfiles.

Si NO se define el código de perfil (Código=0), deberán ingresarse valores para F y J
para ser utilizados en el cálculo. Esto permite que al dimensionar en Acero las barras
asignadas a esta sección sean predimensionadas para el tipo ingresado, buscando el
código de sección dentro de dicho tipo que verifique el dimensionamiento. Por el
contrario cuando se definen ambos valores de Tipo y Código el dimensionamiento en
acero se hará para dicho perfil informando si verifica o no.

El número de sección debe ser correlativo, comenzando desde el nro. 1.

CONSIDERACIONES DEL CURSO: como se mencionó en el punto anterior, dado que en
el curso se estudia el hormigón armado como material estructural, sólo se trabajará con
este tipo de material. Para el ingreso de los datos del material se utilizará la forma “Ingreso
de Secciones de Hormigón (secciones rectangulares y tipo "T")” descrita.
En caso que el ejemplo que desarrollemos tenga alguna sección en acero, para el ingreso
de los datos del material se utilizará la forma “Ingreso de Perfiles de Acero” descrita.

Para nuestro caso ingresaremos:

Secciones:
\* Nro
\* Nro Tipo (R) b d
\* Nro Tipo (R) b d h hp
\* Nro Tipo (T) b d b0 d0 h hp
1 R 0.20 0.30 0.27 0.03
2 R 0.20 0.35 0.32 0.03
3 R 0.20 0.40 0.37 0.03

Nota: Estos datos pueden ingresarse a través de un cuadro de diálogo que nos va guiando
en los pasos a seguir:

Secciones de Hormigón:
\1. Dentro del Editor de Texto, posicionamos el cursor en el renglón que queremos
insertar los tipos de secciones a definir,
\2. luego hacemos clik con el botón derecho del mouse y se despliega una ventana
que nos da una serie de opciones para elegir, debemos acceder a la opción de
“Secciones”,
\3. se despliega un cuadro de diálogo que nos brinda todos los tipos de secciones que
podemos ingresar, y en cada caso qué datos debemos ingresar.

Secciones de acero:
\1. Dentro del Editor de Texto, posicionamos el cursor en el renglón que queremos
insertar los tipos de secciones a definir,
\2. luego hacemos clik con el botón derecho del mouse y se despliega una ventana
que nos da una serie de opciones para elegir, debemos acceder a la opción de
“Secciones Perfiles”,
\3. se despliega un cuadro de diálogo que nos brinda todos los tipos de secciones de
perfiles que podemos ingresar, y en cada caso qué datos debemos ingresar.

ESTABILIDAD DE LAS CONSTRUCCIONES II | FACULTAD DE ARQUITECTURA | UdelaR 8

<!-- p. 9 -->

ASIGNA MATERIALES

DESCRIPCIÓN:

Asigna.M
Bd Bh M
e>0 e>0 e>0
X - X

Bd. Barra inicial a asignar.
Bh. Barra final a asignar
M. Nro. del Material a asignar al rango de Barras.

El título Asigna.M puede ingresarse en cualquier parte del texto.
La Barra Bd debe haber sido definida previamente.
Si se ingresa un rango (indicando el valor de Bh) la barra Bh debe haber sido definida
previamente.
El número de material debe haber sido definido previamente.
Cuando se define un rango Bd y Bh, solo deben existir las barras Bd y Bh, el material será
asignado a todas las barras intermedias que hayan sido definidas.

La asignación de materiales puede hacerse:
\- ingresando barra por barra (Ejemplo A)
\- o, en el caso que todas las barras o conjuntos de barras con su numeración
consecutiva, tengan el mismo material puede ingresarse a ese grupo como un rango.
(Ejemplo B)

Por ejemplo: Si una estructura que está conformada por 7 barras, de las cuales 2 de ellas
son de acero (barras nº 2 y 7) y el resto de hormigón (barras nº 1, 3, 4, 5, 6), la asignación
de materiales para estas barras puede ingresarse de la siguiente manera:

\* Barra (Barra_Hasta) Nro_de_Material Comentario:
1 1 ---- Ejemplo A (barra por barra)
2 2 ---- Ejemplo A (barra por barra)
3 6 1 ---- Ejemplo B (rango)
7 2 ---- Ejemplo A (barra por barra)

A la barra 1 se le asigna el material 1 (hormigón). Ejemplo A (definición barra por barra)
A la barra 2 se le asigna el material 2 (acero). Ejemplo A (definición barra por barra)
A las barras 3, 4, 5, 6 se les asigna el material 1 (hormigón). En este caso se puede definir
un rango de la barra 3 a la 6. Ejemplo B (definición de un rango)
A la barra 7 se le asigna el material 2 (acero). Ejemplo A (definición barra por barra)

Para nuestro caso ingresaremos:

Asigna.M
\* Barra (Barra_Hasta) Nro_de_Material
1 3 1

ESTABILIDAD DE LAS CONSTRUCCIONES II | FACULTAD DE ARQUITECTURA | UdelaR 9

<!-- p. 10 -->

ASIGNA SECCIONES

DESCRIPCIÓN:

El título Asigna.S puede ingresarse en cualquier parte del texto.

Asigna.S
Bd Bh S
e>0 e>0 e>0
X - X

Bd. Barra inicial a asignar.
Bh. Barra final a asignar
S. Nro. de Sección a asignar al rango de Barras.

La Barra Bd debe haber sido definida previamente.
Si se ingresa un rango (indicando el valor de Bh) la barra Bh debe haber sido definida
previamente.
El número de sección debe haber sido definido previamente.

Cuando se define un rango Bd y Bh, solo deben existir las barras Bd y Bh, la sección será
asignada a todas las barras intermedias que hayan sido definidas.

Para nuestro caso ingresaremos:

Asigna.S
\* Barra (Barra_Hasta) Nro_de_Sección
1 1
2 2
3 3

CARGAS

DESCRIPCIÓN:

El título Cargas puede ingresarse en cualquier parte del texto.

Cargas
Nro. Tpo L1 L2 Q1 Q2 Ang
e>0 1/5 r r r r r
X X
Distribuidas 1 F/L G
Trapezoidales 2 L L F/L F/L G
Fuerzas Concentradas 3 L F G
Momentos Concentrados 4 L F*L
Temperatura 5 Gc Gc

Nro. El número de carga a definir. Debe ser correlativo y comenzar desde el Nro. 1.
Tpo. Tipo de carga. Puede ser 1,2,3,4 ó 5. (Ver la tabla anterior)
L1. De acuerdo al tipo de carga, la posición inicial de la misma.
L2. De acuerdo al tipo de carga, la posición final de la misma.
Q1. De acuerdo al tipo de carga, el valor inicial de la misma.
Q2. De acuerdo al tipo de carga, el valor final de la misma.
Ang. De acuerdo al tipo de carga su dirección y sentido

El Número de carga debe ser correlativo, comenzando desde el no 1.
El tipo de carga sólo puede tomar los valores 1,2,3,4 ó 5.
Al definir longitudes las mismas se ingresan en % de la longitud total de la barra.

ESTABILIDAD DE LAS CONSTRUCCIONES II | FACULTAD DE ARQUITECTURA | UdelaR 10

<!-- p. 11 -->

Campo Ang.:
Indica el mismo valor de dirección y sentido para Q1 y Q2.
Puede ser ingresado de varias formas diferentes:
\- Si se ingresa un valor numérico, este valor es el ángulo en coordenadas globales
que forma la carga con el eje +Y.

\- Para facilitar su ingreso puede definirse indicando la dirección y sentido en forma
explícita de acuerdo a la siguiente tabla:
0 +Y
90 -X
180 -Y
270 +X

\- Si desea ingresar cargas cuyo ángulo este en función de la barra a cargar, puede
expresar la dirección y sentido en coordenadas locales de la barra, agregando la
letra L a la dirección.

Ejemplo:

Cargas
\* Nro Tipo (l1) (l2) (q1) (q2) (ang)
1 1 1 -Y
2 1 1 180
3 3 50 2 -YL
4 2 0 100 1 2 +X

ü Las cargas nro. 1 y nro. 2 son idénticas. Se trata de cargas distribuidas (tipo 1) en toda
la barra, su dirección es el eje Y y su sentido es negativo. Por tratarse de coordenadas
globales siempre actuarán de arriba hacia abajo independientemente de las barras a
las que se le asigne la carga.

ü La carga nro. 3 es una fuerza concentrada (tipo 3) en la mitad de la barra (50%) y su
dirección y sentido fueron definidos en coordenadas locales, como perpendiculares a la
barra de arriba hacia abajo (-YL)

ü La carga nro. 4 es una carga distribuida trapezoidal (tipo 2) que ocupa la totalidad de la
longitud de la barra (0% a 100%) y su dirección y sentido coinciden con el eje +X en
coordenadas globales independientemente de las barras a las que se le asigne la
carga.
En coordenadas locales solamente pueden definirse las direcciones y sentidos principales,
\+XL, +YL, -XL y –YL. Si desea ingresar una carga en coordenadas locales con un ángulo
diferente, deberá ingresar las proyecciones en las direcciones principales.

ESTABILIDAD DE LAS CONSTRUCCIONES II | FACULTAD DE ARQUITECTURA | UdelaR 11

<!-- p. 12 -->

Para nuestro caso ingresaremos:

\* Nro Tipo (l1) (l2) (q1) (q2) (ang)
1 1 0.15 -Y
2 3 60 0.135 -Y
3 1 0.535 -Y
4 1 0.2 -Y

Nota: Estos datos pueden ingresarse a través de un cuadro de diálogo que nos va guiando
en los pasos a seguir:
\1. Dentro del Editor de Texto, posicionamos el cursor en el renglón que queremos
insertar los tipos de cargas a definir,
\2. luego hacemos clik con el botón derecho del mouse y se despliega una ventana
que nos da una serie de opciones para elegir, debemos acceder a la opción de
“Cargas”,
\3. se despliega un cuadro de diálogo que nos brinda todos los tipos de cargas que
podemos ingresar, y en cada caso qué datos debemos ingresar.

ESTADO

DESCRIPCIÓN:

Estado
Nro.
e>0
X

Nro. Número de Estado.

El título Estado indica qué estado se definirá desde su ingreso en el texto en adelante. Las
cargas y barras que se ingresen a continuación se asignarán al estado definido.
Solo pueden definirse estados correlativos comenzando desde el nro. 1.

CONSIDERACIONES DEL CURSO:
El programa permite ingresar varios estados de carga posibles, por ejemplo:
\- La estructura sometida solamente a la acción de cargas permanentes (peso propio de
los elementos constitutivos de la estructura), o
\- La estructura sometida a la acción de cargas permanentes + cargas eventuales
(producidas por el viento o por el propio uso del edificio)

Estudiando los distintos estados de carga, se obtiene la totalidad de las máximas
exigencias a que está sometida la estructura.

En el curso se considerarán las cargas actuando todas a la vez (peso propio + cargas
producidas por propio uso del edificio), no se consideran estados de carga distintos.

Para nuestro caso ingresaremos:

Estado
\* Nro.
1

ESTABILIDAD DE LAS CONSTRUCCIONES II | FACULTAD DE ARQUITECTURA | UdelaR 12

<!-- p. 13 -->

CARGAS EN BARRAS

DESCRIPCIÓN:

Cargas.B
Bd Bh C
e>0 e>0 e>0
X - X

Bd. Barra inicial a cargar.
Bh. Barra final a cargar
C. Nro. de Carga a cargar al rango de Barras.

El título Cargas.B puede ingresarse en cualquier parte del texto, de haberse asignado
previamente una carga a la barra, se agrega la nueva carga.

La Barra Bd debe haber sido definida previamente.
Si se ingresa un rango (indicando el valor de Bh) la barra Bh debe haber sido definida
previamente.
El número de carga debe haber sido definido previamente.
Cuando se define un rango Bd y Bh, solo deben existir las barras Bd y Bh, la carga será
asignada a todas las barras intermedias que hayan sido definidas.

La definición de las “cargas en barras” puede hacerse:
\- ingresando barra por barra, y a cada una asignarle el tipo de carga en barra que le
corresponde, o;
\- en el caso que todas las barras o conjuntos de barras con su numeración consecutiva,
tengan la misma “carga en barra” puede ingresarse a ese grupo como un rango.

Para nuestro caso ingresaremos:

\* Barra (Barra_Hasta) Nro_de_Carga
1 1
1 2
2 3
3 4

CARGAS EN NODOS

DESCRIPCIÓN:

Cargas.N
Nd Nh C-X C-Y C-M
e>0 e>0 r r R
X - X X X
F F F*L

Nd. Nodo inicial a cargar.
Nh. Nodo final a cargar
C-X. Fuerza en X a cargar en el Nodo
C-Y. Fuerza en Y a cargar en el Nodo
C-M. Momento a cargar en el Nodo

El título Cargas.N puede ingresarse en cualquier parte del texto, de haberse asignado
cargas previamente a un nodo, se agregan los nuevos valores de carga.

ESTABILIDAD DE LAS CONSTRUCCIONES II | FACULTAD DE ARQUITECTURA | UdelaR 13

<!-- p. 14 -->

El nodo Nd debe haber sido definido previamente.
Si se ingresa un rango (indicando el valor de Nh) el nodo Nh debe haber sido definido
previamente.
Cuando se define un rango Nd y Nh, solo deben existir los nodos Nd y Nh, las cargas serán
asignadas a todos los nodos intermedios que hayan sido definidos.

Las direcciones y sentidos de las cargas son siempre en coordenadas globales.

Para nuestro caso:

El ejemplo que tomamos no tiene fuerzas o momentos aplicados en nodos, por lo cual no
se ingresa nada, queda en blanco.

\* Nodo (Nodo_Hasta) F-X F-Y M

HIPÓTESIS

DESCRIPCIÓN:

Hipótesis
Nro. F1 F2 F3 F4 F5 F6 F7 F8 F9
e>0 r r R r r r r r R
X X - - - - - - - -

Nro. Número de hipótesis a definir. Debe ser correlativo y comenzar desde el nro. 1.
F1 a F9. Factores que multiplican cada estado que interviene en la hipótesis definida.

El título Hipótesis solo puede ingresarse una única vez.
Los factores pueden ser negativos, indicando un cambio en el sentido de la definición de la
carga.
No es necesario completar con factores 0(cero) los estados no definidos.

Como ya se dijo anteriormente, el programa permite ingresar varios estados de carga
posibles (peso propio, viento, cargas de uso, etc.), ello posibilita el calcular la estructura en
uno de esos estados de carga, en combinaciones de ellos o en todos a la vez. A cada una
de estas posibilidades, el programa las identifica como “Hipótesis”; y ello permite
determinar la totalidad de las máximas exigencias a que está sometida la estructura.

CONSIDERACIONES DEL CURSO:
Dado que como en el curso se considerarán las cargas actuando todas a la vez, es decir
que no se consideran estados de carga distintos, la hipótesis de cálculo es solo una.

Para nuestro caso ingresaremos:

Hipótesis
\* Nro. F1 F2 F3 F4 F5 F6 F7 F8 F9
1 1

SISMO

CONSIDERACIONES DEL CURSO: No se considerará

ESTABILIDAD DE LAS CONSTRUCCIONES II | FACULTAD DE ARQUITECTURA | UdelaR 14

<!-- p. 15 -->

CÁLCULO (ORDEN)

DESCRIPCIÓN:

El título Cálculo define el tipo de cálculo a realizar sobre la estructura. El programa puede
realizar el cálculo en Primer Orden, o en Segundo Orden.

CONSIDERACIONES DEL CURSO:
El cálculo se realizará en Primer Orden.

Para nuestro caso ingresaremos:

Cálculo
\* Orden (Tolerancia)
1

ESTABILIDAD DE LAS CONSTRUCCIONES II | FACULTAD DE ARQUITECTURA | UdelaR 15
