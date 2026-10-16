---
type: libro
title: "Manual"
author: "Prof. Suarez"
categoria: "AYUDAS DE PROGRAMAS"
paginas: 153
extraccion: "texto"
fuente: "local:E:/MATERIAL DE CONSULTA/AYUDAS DE PROGRAMAS/COMPUTERS AND STRUCTURES/introduccion_Visual_SAP2000__(excelente).pdf"
convertido: 2026-10-16
---

# Manual

> Texto extraído de `AYUDAS DE PROGRAMAS\COMPUTERS AND STRUCTURES\introduccion_Visual_SAP2000__(excelente).pdf` (153 páginas, texto). El PDF original está en el disco E: (MATERIAL DE CONSULTA); `<!-- p. N -->` marca el inicio de cada página.

<!-- p. 1 -->

Volumen
1

INTRODUCCIÓN VISUAL A SAP2000

Traducido por Luis E. Suárez y Drianfel Vázquez
Manual proporcionado en el seminario Internacional de CSI 2004 por:
www.construaprende.com / www.morrisoningenieros.com

<!-- p. 2 -->

Introducción Visual a SAP2000

© Luis E. Suárez y Drianfel Vázquez

Traducido por Luis E. Suárez y Drianfel Vázquez
Manual proporcionado en el seminario Internacional de CSI 2004 por:
www.construaprende.com / www.morrisoningenieros.com

<!-- p. 3 -->

I N T R O D U C C I Ó N A S A P 2 0 0 0 V I S U A L

Tabla de Contenido

I N T R O D U C C I Ó N 3

C A P Í T U L O 1 : V I G A S

Ejemplo de Viga 1 9

Ejemplo de Viga 2 31

C A P Í T U L O 2 : A R M A D U R A S

Ejemplo de Armaduras 1 42

Ejemplo de Armaduras 2 60

C A P Í T U L O 3 : M A R C O S

Ejemplo de MARCOS 1 70

Ejemplo de MARCOS 2 (Paredes de Cargas) 87

C A P Í T U L O 4 : A N Á L I S I S D I N Á M I C O

Ejemplo de Análisis Dinámico 1 100

Ejemplo de Análisis Dinámico 2 112

C A P Í T U L O 5 : E S P E C T R O D E R E S P U E S T A

Ejemplo de Análisis de Espectro de Respuesta 127

1
Traducido por Luis E. Suárez y Drianfel Vázquez
Manual proporcionado en el seminario Internacional de CSI 2004 por:
www.construaprende.com / www.morrisoningenieros.com

<!-- p. 4 -->

Nota Importante

ste texto tiene sólo una función didáctica como apoyo a los cursos
universitarios y seminarios de educación continuada de análisis
estructural. No pretende convertir al lector en un ingeniero estructural niEsuplir la experiencia práctica. Aunque los ejercicios y ejemplos han sido
verificados en diversas ocasiones, no se garantiza que estén totalmente libres de
errores. Los usuarios son totalmente responsables por el buen uso del programa
y los autores no asumen ninguna responsabilidad por el uso incorrecto del
mismo.

2
Traducido por Luis E. Suárez y Drianfel Vázquez
Manual proporcionado en el seminario Internacional de CSI 2004 por:
www.construaprende.com / www.morrisoningenieros.com

<!-- p. 5 -->

Introducción :

Sobre el uso de uso de
programas de análisis
estructural - SAP2000

l enfoque de la enseñanza del análisis estructural está cambiando en
forma acelerada debido a la profusión del uso y disponibilidad de la
computadora. Los costos cada vez más bajos y la capacidad de cálculoEsiempre creciente han tenido, como era de esperar, un efecto positivo en los
programas para el análisis de estructuras. El número y variedad de programas
para el análisis y diseño de estructuras ha crecido al mismo ritmo que se han
desarrollado las computadoras. Es muy probable que alguno o incluso varios de
los programas tales como SAP2000, ETABS, VisualAnalysis, STAAD/Pro,
RISA, GT-Strudl, WinStrudl, RAM, Robot, LARSA, 3D+, RSTAB y otros, se
encuentren hoy en día en todas las oficinas de cálculo y diseño.

A tono con los tiempos, el grupo de docentes del área de Estructuras del
Departamento de Ingeniería Civil y Agrimensura del Recinto Universitario de
Mayagüez de la Universidad de Puerto Rico, ha implementado y sigue
considerando cambios en el contenido de sus cursos de análisis y diseño. Se han
eliminado algunos de los llamados “métodos clásicos” del análisis estructural,
aptos para resolver “a mano” estructuras simples. Esto se hizo principalmente
para poder dar énfasis a los “métodos modernos”, que se basan en la resolución
de los problemas mediante una herramienta computacional. En particular, se está
poniendo más énfasis en los cursos de análisis de pregrado en el método de
rigidez matricial. Para que los estudiantes puedan resolver estructuras más
realistas que aquellas muy simples que se pueden resolver a mano, se decidió
adoptar un programa de computadora común para todos los cursos de
estructuras, tanto de nivel subgraduado como de nivel de postgrado. Los
cambios tecnológicos en la educación en general y en ingeniería estructural son
inevitables e irreversibles y no tiene sentido oponerse a ellos; por el contrario
deberíamos aceptarlos y adoptarlos en forma juiciosa e inteligente. Los
estudiantes actuales han nacido y crecido sumergidos en la era de la informática y
en general se sienten muy cómodos con el manejo de las computadoras. Es por

3
Traducido por Luis E. Suárez y Drianfel Vázquez
Manual proporcionado en el seminario Internacional de CSI 2004 por:
www.construaprende.com / www.morrisoningenieros.com

<!-- p. 6 -->

lo tanto lógico y razonable aprovechar esta coyuntura para mejorar su formación
técnica.

Luego de intercambiar opiniones y experiencias entre todos los docentes del área
de Estructuras, se decidió en forma unánime adoptar para uso en nuestros
cursos el programa dee análisis estructural SAP2000. Es importante destacar que
al adoptar este programa, de ninguna manera se le está restando importancia o
emitiendo juicio alguno sobre otros programas similares como ETABS. Los
programas antes citados son todos muy poderosos y confiables. En la decisión
de la adopción de un programa en particular influyen muchos factores, algunos
técnicos y otros no técnicos. Entre estos últimos se encuentran como la
familiaridad de los usuarios con algunos de los productos, la disponibilidad de
versiones estudiantiles, el precio para uso académico y privado, etcétera. En
nuestro caso, además de los factores citados, queríamos una herramienta que
fuera de uso relativamente sencillo, muy usada en la práctica, que tuviera la
posibilidad de ser aplicada para diseño, que tuviera la capacidad de analizar
estructuras distintas de las de barras (como placas y cáscaras), que fuese
reconocida por sus cualidades para el análisis dinámico, muy especialmente para
cargas sísmicas, que fuera puesto al día y mejorado en forma continua, y que
fuera producido por una compañía bien establecida y de excelente reputación. El
programa SAP2000, desarrollado y comercializado por la compañía Computers
& Structures, Inc. de Berkeley, California, reúne estas condiciones y por
consiguiente fue la opción favorecida.

Aunque no es el objetivo de esta introducción, es necesario hacer una aclaración
sobre el uso (y abuso) de los programas de análisis estructural. Como se tendrá
oportunidad de apreciar más adelante, es posible para un usuario crear un
modelo de una estructura relativamente complicada y analizarla para distintas
condiciones de carga con mucha facilidad y con conocimientos mínimos del
tema. Sin embargo, esto puede traer consecuencias muy negativas, e inclusive
catastróficas. Como todo profesional o docente con experiencia sabe, es
imposible (y peligroso) sustituir la experiencia y los años de estudio con una
computadora. Es harto conocido el adagio en inglés: “garbage-in, garbage-out”.
En otros palabras, los resultados que arroja un programa de computadora son
tan malos (o buenos...) como los datos que se le ingresan.

Definitivamente hay muchas ventajas en el uso de esta herramienta de cálculo en
ingeniería estructural. El uso de la computadora permite optimizar el diseño al
ser factible considerar diversos sistemas estructurales, geometrías o secciones
para una misma estructura en un tiempo razonable. También se puede aumentar
la confiabilidad estructural al poder considerarse con relativa facilidad diversos
escenarios o combinaciones de cargas más allá de las mínimas requeridas por un
código. El mismo objetivo se logra al acercar más el modelo analítico a la
estructura real haciéndolo más sofisticado y detallado (por ejemplo,
considerando efectos tridimensionales, etc.). Al reducirse el tiempo para el
4
Traducido por Luis E. Suárez y Drianfel Vázquez
Manual proporcionado en el seminario Internacional de CSI 2004 por:
www.construaprende.com / www.morrisoningenieros.com

<!-- p. 7 -->

análisis y diseño, la eficiencia y por ende la competitividad de una empresa de
ingeniería se ve beneficiada. En última instancia, el poder prestar menos tiempo
a estas tareas, en cierta forma mecánicas, permite dedicarle más tiempo a
actividades más creativas, o porqué no, a mejorar la calidad de vida aumentando
las horas de recreación y contacto familiar.

Todo esto es posible mediante el uso de programas profesionales para el análisis
estructural. Lo que no es posible sustituir mediante una computadora es el
esfuerzo detrás de años de estudio y el buen juicio ingenieril. Por lo tanto,
nuestra filosofía básica en la enseñanza del arte y la ciencia de la ingeniería
estructural no ha cambiado. Todo estudiante debe aprender en el salón de clase y
entender claramente las suposiciones y simplificaciones que se hacen al crear un
modelo, o en el método de cálculo. Debe ser capaz de reproducir a mano lo que
la computadora puede hacer para una estructura simple, incluyendo los famosos
diagramas de fuerzas y momentos internos. Debe ser capaz de determinar si los
resultados del análisis, ya sea a mano o automático, tienen sentido o no. Debe
conocer la metodología y ser capaz de calcular las cargas (muertas, vivas, viento
terremoto, etc.) para el análisis de la estructura. Debe conocer las diferencias
entre los distintos sistemas estructurales y cómo éstos trabajan. Sólo una vez que
domina estos aspectos (y tal vez uno que otro no citado), el estudiante o
profesional está capacitado para usar en forma exitosa y productiva una
herramienta tan poderosa como SAP2000.

Sobre las convenciones y
alcances de estas notas

AP2000 se basa en un programa escrito en FORTRAN inicialmente
desarrollado a comienzos de los años setenta por el Dr. Edward L. Wilson,
actualmente profesor emérito de ingeniería civil de la Universidad deSCalifornia en Berkeley. El programa se llamaba originalmente SAP IV por las
siglas en inglés de Structural Analysis Program (Programa de Análisis
Estructural).

Como el programa SAP2000 ha sido desarrollado en California, obviamente está
implementado en inglés. Al momento de desarrollar estas notas no había una
versión en español o castellano. Por lo tanto, una de las primeras decisiones que
debimos tomar es si se traducían todos los términos del inglés que aparecen al
5
Traducido por Luis E. Suárez y Drianfel Vázquez
Manual proporcionado en el seminario Internacional de CSI 2004 por:
www.construaprende.com / www.morrisoningenieros.com

<!-- p. 8 -->

explicar el uso del programa. Por ejemplo, un término frecuente es el de “toolbar”
para designar un conjunto de utilidades para la creación o modificación del
modelo estructural. ¿Es “caja de herramientas” un término más apropiado? La
decisión que se tomó es traducir todos los términos posibles, con algunas
excepciones. En cada caso, en el texto se usa la palabra o frase que consideramos
más práctica y que no genere confusión al usuario, en especial al leer los
manuales en inglés o al usar las ayudas que tiene incorporadas el programa.
Pedimos disculpas por adelantado a los usuarios que pueden sentirse molestos
por alguna que otra mezcla de inglés y español, o para quienes mantener la
pureza de un idioma es importante.

Existen en la actualidad tres versiones de SAP2000, conocidas como “Standard”,
“Plus” y “Nonlinear” en orden creciente de capacidad. Para correr los ejemplos
que se presentan en este manual basta con la versión “Standard”.

Al igual que la abrumadora mayoría de los programas de análisis estructural
disponibles en forma comercial, el programa SAP2000 está basado en el método
de rigidez matricial. No obstante, esto es transparente para el usuario. En ningún
momento durante el uso del programa se requiere conocer los detalles de este
método, aunque es muy recomendable conocerlo para apreciar mejor las
capacidades y limitaciones de SAP2000.

Los dos últimos capítulos de este manual cubren el análisis dinámico de
estructuras. El análisis de estructuras bajo cargas dinámicas requiere de
conocimientos más especializados que el caso de cargas estáticas. Por lo tanto,
en estos dos capítulos se supone que el lector tiene algunos conocimientos de
Dinámica de Estructuras; por ejemplo se asume que se tiene familiaridad con el
concepto de frecuencias y periodos naturales, modos de vibración,
amortiguamiento modal, espectros de respuesta.

SAP2000 tiene, por lo general, más de una manera de lograr un determinado
objetivo. Por ejemplo, hay tres maneras de seleccionar todas los elementos de
una estructura: usando el comando Ctrl+A de Windows, usando un menú y
submenú, o usando un icono o botón. Aunque a través de los distintos ejemplos
en los capítulos se le presentan al lector todas estas múltiples opciones, el uso de
una u otra es una cuestión de gusto personal.

Por último, es importante destacar que la mejor manera de aprender SAP2000 es
experimentando por sí mismo. Este texto no explora o considera todas las
numerosas opciones y herramientas del programa. Además es más que probable
que futuras versiones de SAP incorporen nuevas opciones. Es posible aprender a
usar el programa explorando por sí sólo. Este manual tiene por objetivo
disminuir el tiempo de aprendizaje y hacer más fácil y menos frustrante la tarea, a
través de compartir la experiencia de los autores con esta herramienta de cálculo.
6
Traducido por Luis E. Suárez y Drianfel Vázquez
Manual proporcionado en el seminario Internacional de CSI 2004 por:
www.construaprende.com / www.morrisoningenieros.com

<!-- p. 9 -->

En un futuro próximo se está planificando incorporar a este manual
herramientas de análisis de SAP200 más especializadas, como por ejemplo el
método del empuje lateral (“Pushover method”), análisis de placas y estructuras
en estado de esfuerzos o deformaciones planas, estructuras con elementos no
lineales localizados, etcétera.

7
Traducido por Luis E. Suárez y Drianfel Vázquez
Manual proporcionado en el seminario Internacional de CSI 2004 por:
www.construaprende.com / www.morrisoningenieros.com

<!-- p. 10 -->

La Pantalla Principal
Aumentar y Cambiar
disminuir la Punto de
imagen del Vista
modelo

Menú
“Toolbar”
Principal

“Toolbar”
para dibujar
y seleccionar
elementos

Cambiar Unidades

n la figura anterior se presenta la pantalla principal de SAP2000. En la
parte superior aparece el menú principal y por debajo del mismo el
“toolbar” principal (o la caja de herramientas). El “toolbar” principal
provee acceso rápido y directo a las operaciones más comúnmente utilizadas E

8
Traducido por Luis E. Suárez y Drianfel Vázquez
Manual proporcionado en el seminario Internacional de CSI 2004 por:
www.construaprende.com / www.morrisoningenieros.com

<!-- p. 11 -->

en el programa. Estas operaciones también pueden realizarse mediante el menú
principal. En el menú principal se hallan todas las operaciones que se encuentran
en el “toolbar” principal y otras que no se encuentran en el mismo. Algunas de las
opciones más utilizadas en este “toolbar” principal son las de aumentar y disminuir el
tamaño de los modelos (“Zoom”) y las opciones de cambio de puntos de vista de
bidimensional a tridimensional.

En la parte izquierda de la pantalla se encuentra el “toolbar” lateral. Éste se utiliza
mayormente para utilizar las operaciones de crear, seleccionar y modificar los
distintos tipos de elementos que utiliza el programa. En la parte inferior derecha se
presenta la caja de unidades. En esta caja se puede seleccionar y cambiar las
unidades que en determinado momento se están usando para la creación del modelo
o en las unidades que se están empleando para ver los resultados. Durante el
transcurso de este manual nos referiremos a estos estas herramientas con los
nombres mencionados en esta introducción y se describirán cada una de las
operaciones que hacen los mismos.

Usuarios

ste documento presume que los usuarios del programa SAP2000 están
familiarizados con el sistema operativo “Windows”. Además se presume
que las personas que lo van a utilizar tienen conocimientos básicos deE cursos tales como Estática, Mecánica (o Resistencia) de Materiales, y al
menos un curso básico de Análisis Estructural. Para enteder mejor los Capítulos 4 y 5
se requieren conocimientos de Dinámica Estructural o Vibraciones. Aspectos y
terminologías relacionadas a estas áreas son constantemente utilizados en el
transcurso del documento.

Abreviaciones

BD → Presionar el botón de la derecha del ratón (“mouse”)

BI → Presionar el botón de la izquierda del ratón (“mouse”)

9
Traducido por Luis E. Suárez y Drianfel Vázquez
Manual proporcionado en el seminario Internacional de CSI 2004 por:
www.construaprende.com / www.morrisoningenieros.com

<!-- p. 12 -->

Capítulo
1
Ejemplo de Vigas 1

Descripción del Problema: El ejemplo a resolver consiste de una viga de tres luces
con un extremo fijo, dos soportes internos tipo rodillo (“roller”) y el otro extremo
libre. Las propiedades de los materiales a utilizar son E = 3,120 ksi, I = 1,500 in4 y la
geometría que se muestra en la figura a continuación.

Solución:

Paso 1 [Definir Unidades]: Ejecute el programa SAP2000. Seleccione las unidades
iniciales en las que desea trabajar. Esta opción se encuentra en la parte inferior
derecha de la pantalla principal de SAP2000, como se muestra a continuación.
Seleccione de la caja de opciones (“combo box”).

10
Traducido por Luis E. Suárez y Drianfel Vázquez
Manual proporcionado en el seminario Internacional de CSI 2004 por:
www.construaprende.com / www.morrisoningenieros.com

<!-- p. 13 -->

Paso 2 [Selección del modelo]: Del menú principal (parte superior), abriendo la
opción de “File” seleccione “New Model from Template …”. Esta acción lo llevará
a la ventana de “Model Templates” que se muestra a continuación.

Nota:

Los “Templates”, en orden de izquierda a derecha y de arriba hacia abajo significan,
en inglés: Beams, Portal Frames, Braced Frames, Shear Walls, Cylinder, Eccentric
Frame, Space Frame, Perimeter Frame, Barrel, Dome, Sloped Truss, Vertical Truss,
Space Truss, Floor y Bridge. Estos son formatos que facilitan la definición de la
geometría de la estructura que queremos analizar.

Seleccione el primer “Template”: “beam”, con el BI. Esto lo conducirá a la siguiente
ventana o pantalla. Escriba 3 y 15 en las cajas de texto (“text box”) de “Number of
Spans” (número de tramos) y “Span Length” (longitud del tramo), respectivamente.
Seleccione OK. Esto lo conducirá a la pantalla principal de SAP2000, la cual tiene
por omisión (“default”) dos ventanas principales: una en 3-dimensiones y la otra en el
plano XZ. En general, si la estructura es plana, la imagen tri-dimensional que
11
Traducido por Luis E. Suárez y Drianfel Vázquez
Manual proporcionado en el seminario Internacional de CSI 2004 por:
www.construaprende.com / www.morrisoningenieros.com

<!-- p. 14 -->

muestra la ventana izquierda no es de mucha utilidad. Conviene en estos casos cerrar
esta ventana presionando .

Nota:

Asegúrese que las opciones de “Restraints” y de “Gridlines” están seleccionadas. De
otra manera, la estructura tendrá las juntas libres (sin apoyos) y no aparecerá una grilla
(“grid”) en la pantalla.

Paso 3 [Redefinición de Luces o Geometría]: Note que la viga creada por SAP2000
consiste en una viga de tres claros iguales de 15 ft. Por lo tanto, es necesario mover la
junta final de la derecha para llevarla a la posición deseada de 12 ft como se especifica
en la descripción del problema. Para esto seleccione la junta a moverse haciendo BI
sobre la misma. Al ser seleccionada la junta se marcará con una cruz entrecortada.
Del menú principal, abriendo “Edit” seleccione la opción “Move”, como se muestra
a continuación.

12
Traducido por Luis E. Suárez y Drianfel Vázquez
Manual proporcionado en el seminario Internacional de CSI 2004 por:
www.construaprende.com / www.morrisoningenieros.com

<!-- p. 15 -->

Esto lo conducirá a la siguiente ventana titulada “Move Selected Points”. Escriba -3
en la caja de texto (“text box”) correspondiente a “Delta X” para desplazar el nodo o
junta seleccionada 3 unidades (pies según se especificó en el Paso 1) hacia la
izquierda. Seleccione OK.

13
Traducido por Luis E. Suárez y Drianfel Vázquez
Manual proporcionado en el seminario Internacional de CSI 2004 por:
www.construaprende.com / www.morrisoningenieros.com

<!-- p. 16 -->

Paso 4 [Definición de las Condiciones de Borde]: Notar que no todas las
condiciones de borde de la viga desarrollada hasta ahora son las mismas que las
especificadas. Para cambiar las condiciones de borde, seleccione primero la junta a
cambiar (o sea, la del extremo derecho) para cambiar su condición. Luego de
seleccionar la junta seleccione en el menú principal “Assign” y la opción de “Joints” y
la sub-opción de “Restraints” o presione el icono del “toolbar” que se encuentra
en la parte superior de la pantalla principal. Ambas acciones lo conducirán a la
pantalla que se muestra a continuación.

Nota:

Por ahora se recomienda que utilice los botones que se encuentran en el recuadro de
“Fast Restraint”. Estos significan lo siguiente:

Apoyo o soporte fijo (“fixed”) que restringe desplazamientos y
rotaciones todas las direcciones.

14
Traducido por Luis E. Suárez y Drianfel Vázquez
Manual proporcionado en el seminario Internacional de CSI 2004 por:
www.construaprende.com / www.morrisoningenieros.com

<!-- p. 17 -->

Soporte articulado (“pin”) que restringe desplazamientos en dos
direcciones

Soporte de rodillo (“roller”) que restringe desplazamientos en una
dirección.

Junta libre de soporte

Seleccione de la ventana y seleccione OK. Repita el procedimiento con la junta

del extremo derecho, pero en esta ocasión seleccione para dejar ese extremo
libre. El modelo debe ahora aparecer como se muestra en la siguiente figura.

Paso 5 [Definición de propiedades de los materiales]: Notar que las unidades con
las que se especifican los materiales no coinciden con las utilizadas para crear el
modelo. Cambie las unidades a para facilitar la entrada de datos. Para
definir las propiedades de los materiales, seleccione “Define” del menú principal, de
la lista que se presenta escoja la opción de “Materials...” como se muestra en la figura
a continuación.

15
Traducido por Luis E. Suárez y Drianfel Vázquez
Manual proporcionado en el seminario Internacional de CSI 2004 por:
www.construaprende.com / www.morrisoningenieros.com

<!-- p. 18 -->

Esto lo conducirá a la pantalla que se muestra a continuación.

16
Traducido por Luis E. Suárez y Drianfel Vázquez
Manual proporcionado en el seminario Internacional de CSI 2004 por:
www.construaprende.com / www.morrisoningenieros.com

<!-- p. 19 -->

Seleccione el botón de “Add New Material” el cual lo conducirá a la pantalla de
“Material Property Data” siguiente.

Entre un nombre para identificar el material (por ejemplo: Hormigón, MAT1, etc) en
la caja de texto de “Material Name”. Deje la opción de “Isotropic” seleccionada en el
recuadro de “Type of Material” y cambie los valores en el recuadro de “Analysis
Property Data” a los valores especificados en la descripción del problema. En este
caso entre 3120 en el “Modulus of Elasticity”. Si conoce los otros valores y los va a
utilizar, escríbalos en las cajas de texto (“text box”) correspondientes. No cambie los
valores en los recuadros que dicen “Design” puesto que estos datos son para el
diseño y no para el análisis. Seleccione OK dosveces.
17
Traducido por Luis E. Suárez y Drianfel Vázquez
Manual proporcionado en el seminario Internacional de CSI 2004 por:
www.construaprende.com / www.morrisoningenieros.com

<!-- p. 20 -->

Nota:

Si se desea que el programa calcule automáticamente el peso propio de la estructura
para usarlo como carga muerta, el peso unitario del material (”Weight per unit
volume”) no debe ser cero. De la misma manera, para efectuar un análisis dinámico
de la estructura, la densidad (“Mass per unit volume” ) no debe ser cero (éste último
tema se explica en otro capítulo)..

Paso 6 [Definición de las secciones de los elementos]: Para definir las secciones
de los elementos, seleccione “Define” en el menú principal y luego la opción “Frame

Sections”. Una forma alternativa es presionar el icono de en el “toolbar”
ubicado en la parte superior. Cualquier opción lo conducirá a la siguiente pantalla.

Seleccione “Add General” como se muestra en figura, lo que hará abrir la siguiente
pantalla de “Property Data”. Entre 1500 en el “Moment of Inertia about 3 axis” y
seleccione OK. Esto lo llevará a una nueva pantalla llamada “General Section”

18
Traducido por Luis E. Suárez y Drianfel Vázquez
Manual proporcionado en el seminario Internacional de CSI 2004 por:
www.construaprende.com / www.morrisoningenieros.com

<!-- p. 21 -->

Nota:

Nótese que en la ventana de “Property Data” (Datos de las propiedades), además del
momento de inercia respecto al eje 3 que ingresamos, aparecen varias otras
propiedades de la sección geométrica. En este primer ejemplo, en que estamos
estudiando de una viga en flexión, estas otras propiedades no nos interesan. Sin
embargo, para otras estructuras como MARCOS tri-dimensionales es importante
ingresar los datos que aparecen en la ventana.

La primera propiedad que se requiere para el análisis es el área de la sección
transversal A (“Cross-section (axial) area”), la que no requiere de mayor explicación.

La segunda propiedad, que SAP2000 llama la constante torsional (‘Torsional constant”),
es importante para barras en torsión. Para una barra circular (maciza o hueca), esta
constante no es otra cosa que el momento polar de inercia Jp. Para secciones no
circulares, la constante torsional se puede definir como el producto del momento
polar de inercia por un factor de corrección. Por ejemplo, para una sección cuadrada
de lado “d” sería: 0.845 Jp, donde Jp = d4/6.

El área de corte o de cortante (“Shear area”) se requiere cuando se desea considerar el
efecto de las deformaciones angulares o por cortante en la deflexión de la estructura,
importante en vigas cortas y profundas. El área de corte se define como el área de la
sección transversal A dividida por un factor de forma. Por ejemplo, para una sección
rectangular el factor de forma es 6/5, y por lo tanto el área de corte es A/(6/5). Para
secciones con formas comunes SAP2000 calcula automáticamente el área de corte, y
por omisión, considera la contribución del cortante en la deflexión. Esta manera de
19
Traducido por Luis E. Suárez y Drianfel Vázquez
Manual proporcionado en el seminario Internacional de CSI 2004 por:
www.construaprende.com / www.morrisoningenieros.com

<!-- p. 22 -->

proceder es conveniente porque los resultados van a ser más precisos, si bien en
muchos casos la contribución del cortante es despreciable. Sin embargo, si se desea
comparar los resultados del programa con los de un problema resuelto “a mano”o
con otro programa, es necesario que no se consideren las deformaciones por
cortante. Básicamente hay dos maneras de hacer esto en el programa. La primera
forma es válida para secciones generales, donde el usuario entre las propiedades en la
ventana de “Property Data (como en este ejemplo). Simplemente se coloca un cero
en los encasillados del área de cortante (“Shear 2-2” y “Shear 3-3”). Si la sección es
estándar (circular, rectangular, etc.), como veremos en los próximos ejemplos, el
programa va a calcular todas las propiedades en la ventana “Property Data” y éstas
no se pueden modificar directamente. Sin embargo, es posible modificar las
propiedades en forma indirecta presionando el botón de “Modification Factors”
(factores de modificación) que se encuentra en la ventana que se muestra en la
siguiente página. Al presionar este botón se abrirá la ventana llamada “Analysis
Property Modification Factors” (factores de modificación de las propiedades del
análisis). Esta ventana permite aplicar un factor a las propiedades geométricas de las
secciones: asignar un valor de 0 en los encasillados de “Shear Area in 2 direction” y
“Shear Area in 3 direction” produce el mismo efecto que colocar en cero el área de
corte.

Los ejes locales 1, 2 y 3 a los que se refieren los momentos de inercia, etcétera, se
muestran en la Nota en la siguiente página.

20
Traducido por Luis E. Suárez y Drianfel Vázquez
Manual proporcionado en el seminario Internacional de CSI 2004 por:
www.construaprende.com / www.morrisoningenieros.com

<!-- p. 23 -->

Entre un nombre con el que se va identificar la sección transversal (por ejemplo,
VIGA1) en el espacio de “Section Name” y cambie el material al nombre del material
asignado (por ejemplo, MAT1) como se muestra. Seleccione OK dos veces para
volver a al pantalla principal.

Nota: La figura muestra las coordenadas locales de los elementos

21
Traducido por Luis E. Suárez y Drianfel Vázquez
Manual proporcionado en el seminario Internacional de CSI 2004 por:
www.construaprende.com / www.morrisoningenieros.com

<!-- p. 24 -->

Paso 7 [Asignar secciones de los elementos al modelo]: Luego de definir las
secciones y los materiales, el siguiente paso es asignar dichas propiedades a los
elementos. Seleccione cada uno de los tres elementos del modelo mediante un BI
encima de cada elemento o dibujando un cuadro que cubra la viga completa,
moviendo el “mouse” y manteniendo apretado el botón izquierdo. Del menú de
“Assign” seleccione “Frame” y luego “Sections”, lo que lo lleva a la siguiente ventana.

Seleccione del recuadro “Frame Sextions” el nombre de la sección previamente
definido (por ejemplo VIGA1). Al apretar OK, el nombre de la seccion va a
aparecer sobre cada elemento de la estructura.

22
Traducido por Luis E. Suárez y Drianfel Vázquez
Manual proporcionado en el seminario Internacional de CSI 2004 por:
www.construaprende.com / www.morrisoningenieros.com

<!-- p. 25 -->

Nota:

Se recomienda que grabe el archivo en el cual está trabajando frecuentemente puesto
que el programa no recupera archivos perdidos. Se recomienda que se utilize un
Cartapacio (“Folder”) distinto para cada modelo desarrollado. Grabe el programa

con un nombre (por ejemplo, EjVIGA1). Recuerde grabar presionando a
menudo en especial si la estructura es complicada.

Paso 8 [Definir sistemas de cargas]: Antes de aplicarle las cargas al modelo es
necesario definir los sistemas de cargas (por ejemplo Muerta, Viva, Viento
Terremoto). En este paso NO se aplican las cargas, solamente se definen cuales de
ellos van a ser utilizados. En este problema en particular solamente se van a aplicar
las cargas en el sistema de carga muerta y sin incluir el peso propio. Para esto,
seleccione “Define” del menú principal la opción de “Static Load Cases”. Esto lo
llevará a la siguiente ventana.

Inicialmente el programa tiene por omisión (“default”) un sistema llamado LOAD1.
Reemplace el nombre de LOAD1 por otro nombre (por ejemplo, MUERTA) en el
espacio de “Load” y deje el tipo (“Type”) como “DEAD”. Cambie el factor de “Self
Weight Multiplier” de 1 a 0. (1 significa que se va a incluir el peso propio de los
elementos y 0 significa que no se va a incluir). Presione el botón de “Change Load” y
OK.

Paso 9 [Definir carga concentrada]: Luego de definir los sistemas de carga, el
siguiente paso es asignar valores a las fuerzas del sistema de cargas correspondiente.
Como las cargas están definidas en “k-ft” y “ft”, cambie nuevamente las unidades a
en la parte inferior derecha del programa. La primera carga a ser
aplicada consiste en una fuerza concentrada de 10 kip ubicada a 10 ft del extremo
izquierdo del primer tramo (de longitud 15 ft). Para esto seleccione el primer
23
Traducido por Luis E. Suárez y Drianfel Vázquez
Manual proporcionado en el seminario Internacional de CSI 2004 por:
www.construaprende.com / www.morrisoningenieros.com

<!-- p. 26 -->

elemento donde se va a aplicar la carga concentrada. Luego seleccione del menú
principal de “Assign” la opción de “Frame Static Loads...” y a continuación la que
dice “Point and Uniform...”.

También puede presionar el icono de ubicado en el “toolbar” superior. Ambas
opciones lo conducirán a la siguiente ventana.

24
Traducido por Luis E. Suárez y Drianfel Vázquez
Manual proporcionado en el seminario Internacional de CSI 2004 por:
www.construaprende.com / www.morrisoningenieros.com

<!-- p. 27 -->

Verifique que en “Load Case Name” aparezca el nombre MUERTA (o el nombre
especificado en el sistema de carga). En el recuadro de “Load Type and Direction”
verifique que la opción de fuerzas (“Forces”) esté seleccionada y que la dirección
(“Direction”) sea “Gravity” (Gravity es una carga aplicada en dirección del eje Global
Z negativa). En el recuadro de “Point Loads” en los espacios debajo de 1 escriba 10
para “Distance” y 10 para “Load”. Verifique que la opción de “Absolute Distance
From End-I” esté seleccionada. Si desea usar la opción de “Relative Distance From
End-I” tiene que cambiar los 10 ft en “Distance” por 0.6666 = 10/15 que es la
distancia relativa al largo del tramo. Seleccione OK. La carga aparecerá en el modelo

como se muestra a continuación. Recuerde grabar el archivo actualizado de su
modelo.

25
Traducido por Luis E. Suárez y Drianfel Vázquez
Manual proporcionado en el seminario Internacional de CSI 2004 por:
www.construaprende.com / www.morrisoningenieros.com

<!-- p. 28 -->

Paso 10 [Definir la carga uniforme]: Para definir la carga uniformemente
distribuida, seleccione primero el elemento a ser cargado y luego del menú que se
abre con “Assign”, escoja la opción de “Frame Static Load...” y “Point and
Uniform...”. También puede presionar el icono de ubicado en el “toolbar”
superior. Esto lo lleva a la siguiente pantalla.

Note que la ventana contiene los valores de 10 en “Distance” y 10 en “Load”
especificados anteriormente. Cambie esos valores a 0 y en el recuadro de “Uniform
Load” escriba 2. Verifique que las unidades se encuentran en . Cierre
la ventana presionando OK. Ahora el modelo debe aparecer como se muestra a
continuación.

26
Traducido por Luis E. Suárez y Drianfel Vázquez
Manual proporcionado en el seminario Internacional de CSI 2004 por:
www.construaprende.com / www.morrisoningenieros.com

<!-- p. 29 -->

Paso 11 [Definir la carga lineal o trapezoidal]: Para definir la carga uniformemente
distribuida, seleccione primero el elemento a ser cargado y luego del menú que se
abre con “Assign”, escoja la opcion“Frame Load...” y “Distributed...”. Tambien
puede presionar el icono de ubicado en el “Toolbar” superior. Esto lo lleva a la
pantalla siguiente.

Verifique que el “Load Case Name” aparezca el caso MUERTA, que en “Load Type
and Direction” esté seleccionado la opción “Forces” y que en “Direction” aparezca
“Gravity”. En el recuadro de “Trapezoidal Loads”, en los cuadros o cajas de textos
de “Distance” escriba 0 y 12 para indicar que la carga va de 0 a 12 ft y en los de
“Load” coloque 4 y 0 para especificar que la fuerza varia linealmente de 4 k/ft a 0
como se muestra en la figura. Verifique que la opción de “Absolute Distance from
End-I” esté seleccionada. Seleccione OK. El modelo final debe ser el que se
muestra a continuación.

27
Traducido por Luis E. Suárez y Drianfel Vázquez
Manual proporcionado en el seminario Internacional de CSI 2004 por:
www.construaprende.com / www.morrisoningenieros.com

<!-- p. 30 -->

Paso 12 [Analizar la estructura]: El procedimiento seguido hasta el Paso 11
desarrolla lo que es la entrada de datos al programa o “Pre-Procesamiento”. Lo que
procede ahora es resolver el problema o sea continuar con la etapa de “Solución”.
Como la estructura en cuestión es de “dos” dimensiones, es recomendable que se le
especifique al programa los grados de libertad que se utilizarán para así reducir el
tamaño de la matriz de rigidez y a su vez disminuir el esfuerzo computacional y el
tiempo de análisis. Además, debe tenerse presente que en la definición de los
secciones de los elementos no se definieron la propiedades en las otras direcciones.
Debido a que el programa por omisión (“default”) analiza el sistema
tridimensionalmente, esto generaría problemas de cero rigidez en las direcciones
perpendiculares al plano. Para evitar estos problemas seleccione del menú principal
en “Analyze”, la opción de “Set Options”. Esto lo conducirá a la siguiente pantalla
titulada “Analysis Options”.

28
Traducido por Luis E. Suárez y Drianfel Vázquez
Manual proporcionado en el seminario Internacional de CSI 2004 por:
www.construaprende.com / www.morrisoningenieros.com

<!-- p. 31 -->

Presione el segundo botón que dice “Plane Frame” y luego presione OK. Para

obtener la solución del problema, presione el icono de o la tecla F5. También
puede seleccionar del menú de “Analyze” la opción de “Run”. Luego aparecerá una
ventana “Set Analisis Cases to Run” el cual deberá verificar.

El nombre del caso (DEAD) y el Type si el analisis es lineal estatico o dinamico en
nuestro caso es Linear Static. Para iniciar el analisis es necesario el boton “Run Now”.
Luego de esto aparecera una pantalla indicando la secuencia de pasos que el
programa esta llevando a cabo para la solución del problema, terminando con un
mensaje de “A N A L Y S I S C O M P L E T E” como se muestra a continuación.

29
Traducido por Luis E. Suárez y Drianfel Vázquez
Manual proporcionado en el seminario Internacional de CSI 2004 por:
www.construaprende.com / www.morrisoningenieros.com

<!-- p. 32 -->

Presione OK. El programa muestra ahora la estructura deformada (la deformación
está muy exagerada para mejor visualización).

Nota:

De haber algún error en la entrada de datos, el programa mostrará el mensaje
“A N A L Y S I S I N C O M P L E T E” indicando que hubo algún problema.
Utilize la barra lateral de movimiento (“Scroll Bar”) para ver los mensajes de errores e
identificar el problema. En este caso en particular, si no se hubiera especificado la
opción de “Plane Frame” en el Paso 12, el programa terminará con un mensaje de
error por lo antes explicado.

Paso 13 [Diagramas de Momento]: Una vez termindas las etapas de pre-procesamiento
y de solución del problema, lo único que falta es la revisión de resultados o “PostProcesamiento”. Usualmente en vigas lo que interesa verificar son los diagramas de
momento. Para esto seleccione el icono de en el “toolbar” de la parte superior
de la pantalla principal o seleccione del menú de “Display” la opción de “Show
Element Forces/Stresses” y escoja “Frame”. Ambas opciones lo conducirán a la
siguiente ventana.

30
Traducido por Luis E. Suárez y Drianfel Vázquez
Manual proporcionado en el seminario Internacional de CSI 2004 por:
www.construaprende.com / www.morrisoningenieros.com

<!-- p. 33 -->

Verifique que en el espacio de “Load” esté la opción de “MUERTA Load Case”.
Seleccione la opción de “Moment 3-3” en el recuadro de “Component”. Deje la
opción de “Auto” seleccionada en el recuadro de “Scaling”. Quite la opción del
cuadro de cotejo (“Check box”) de “Fill Diagram” y seleccione la opción de “Show
Values on Diagram”. El programa debe mostrar la pantalla que se muestra a
continuación. Para ver más detalladamente los valores de los momentos en cada
elemento, presione BD encima de cada elemento.

Paso 14 [Diagramas de cortante] : Repita el procedimiento del Paso 13 pero
seleccione ahora “Shear 2-2” en vez de “Moment 3-3”. El programa va a mostrar el
diagrama que se muestra a continuación.

Nota:

El momento y cortante que se escogieron para graficar (“Moment 3-3” y “Shear 22”0 corresponden a los sistemas de ejes locales que se muestran en la página 10. Si

31
Traducido por Luis E. Suárez y Drianfel Vázquez
Manual proporcionado en el seminario Internacional de CSI 2004 por:
www.construaprende.com / www.morrisoningenieros.com

<!-- p. 34 -->

por ejemplo se hubiese escojido “Shear 3-3”, el diagrama hubiese sido nulo en toda la
viga pues éste es el cortante en dirección perpendicular al plano de la Figura.

Paso 15 [Deformada y rotaciones en las juntas o nodos]: Para observar de nuevo
la deformada o curva elástica de la estructura presione el icono o seleccione del
menú de “Display” la opción de “Show Deformed Shape”. Ambas acciones lo
conducirán a la siguiente pantalla.

Seleccione “Cubic Curve” y luego presione OK. La deformada se muestra en la
próxima figura. Para obtener las rotaciones y desplazamientos en los nodos o juntas,
simplemente presione BD encima de la junta deseada. Se abrirá una ventana
indicando los desplazamientos y las rotaciones en las tres direcciones en coordenadas
globales. La figura subsiguiente muestra la ventana para la junta del extremo libre.
Las rotaciones se encuentran en radianes y los desplazamientos en las unidades que
se especifiquen en el “combo box” de unidades en la parte inferior derecha.

32
Traducido por Luis E. Suárez y Drianfel Vázquez
Manual proporcionado en el seminario Internacional de CSI 2004 por:
www.construaprende.com / www.morrisoningenieros.com

<!-- p. 35 -->

Paso 16 [Imprimir resultados] : Para obtener los resultados impresos, seleccione del
menú de “Display” la opción de “Show Analisis Results Tables” y seleccione en los
cuadros de verificaciones (“check box”) los resultados (por ejemplo, Displacements,
Reactions, Joint Forces, Frame Forces, Base Reactions) que desea que imprima el
programa como se muestra en la siguiente figura.

El programa también le permite imprimir los resultados en un archivo para verlos
posteriormente. Para esto seleccione la opción de “Print to File”, escriba el lugar y

33
Traducido por Luis E. Suárez y Drianfel Vázquez
Manual proporcionado en el seminario Internacional de CSI 2004 por:
www.construaprende.com / www.morrisoningenieros.com

<!-- p. 36 -->

dirección donde quiere guardar el archivo y el nombre presionando el botón de “File
Name” y oprima OK. Para ver estos resultados seleccione del menú de “File” la
opción de “Display Input/Output Text Files...” cambie el “File Type” a *.txt y
seleccione el archivo (por ejemplo, EjVIGA1.txt) y se mostrarán los resultados
mediante el programa WORDPAD.

Fin del Ejemplo de Vigas #1

34
Traducido por Luis E. Suárez y Drianfel Vázquez
Manual proporcionado en el seminario Internacional de CSI 2004 por:
www.construaprende.com / www.morrisoningenieros.com

<!-- p. 37 -->

Ejemplo de Vigas 2

Descripción del Problema: El ejemplo a resolver consiste de una viga de dos luces
con un extremo fijo y dos soportes internos tipo rodillo (“roller”). La viga consiste
de una sección W16X45 de acero estructural y la geometría que se muestra en la
figura a continuación. La viga tiene en el soporte interior un desplazamiento
prescripto de 4 in hacia arriba. Además se desea incluir en el análisis el peso propio
de la viga.

Solución:

Paso 1 [Definir Unidades]: Una vez que se ejecute el programa de SAP2000,
seleccione las unidades iniciales en las que desea trabajar. Verifique las unidades en la
parte inferior derecha de la pantalla principal de SAP2000. Se comenzará a trabajara
inicialmente en la unidades .

Paso 2 [Selección del modelo]: Del menú principal (parte superior), abriendo la
opción de “File” seleccione “New Model from Template …”. Seleccione el primer
“Template”: “beam”, con el BI. Esto abrirá la ventana de “Beams”. Escriba 2 y 10
en las cajas de texto (“text box”) de “Number of Spans” (número de tramos) y “Span
Length” (longitud del tramo), respectivamente. Seleccione OK. Esto lo conducirá a
la pantalla principal de SAP2000. Cierre la ventana de 3-dimensiones para visualizar
mejor el modelo.

Paso 3 [Definición de las Condiciones de Borde]: Para cambiar las condiciones de
borde, seleccione primero con un BI la junta a la cual se debe cambiar el apoyo (o
sea, la del extremo izquierdo). Luego de seleccionar la junta seleccione en el menú
principal “Assign” y la opción de “Joints” y la sub-opción de “Restraints” o presione

35
Traducido por Luis E. Suárez y Drianfel Vázquez
Manual proporcionado en el seminario Internacional de CSI 2004 por:
www.construaprende.com / www.morrisoningenieros.com

<!-- p. 38 -->

el icono del “toolbar” que se encuentra en la parte superior de la pantalla
principal. Ambas acciones lo conducirán a la siguiente pantalla.

Seleccione el apoyo fijo o empotramiento de la ventana. Note que
inmediatamente aparece un tilde en los seis posibles grados de libertad (en el espacio).
Presione OK. Observe que el apoyo izquierdo ha cambiado.

Paso 4 [Definición de propiedades de los materiales]: Para esta estructura se desea
utilizar problema utilizar una viga W16x45 de acero estructural. El programa tiene al
acero estructural (“STEEL”) y al hormigón (“CONC”) como materiales predefinidos
con módulos de elasticidad de 29,000 ksi y 3600 ksi (f’c=4,000 psi), respectivamente.
Por lo tanto el paso de definir el material (“Define Materials”) se puede omitir puesto
que el material de la viga (hacer) ya está predefinidos. No obstante, si desea ver qué
valores usa el programa para las propiedades del acero, siga la secuencia: “Define” →
“Materials…” → “Define Materials” → “Steel” → “Modif./Show Material”.

Paso 5 [Definición de las secciones de los elementos]: En este caso la viga a
analizar consiste de una sección prefabricada de tamaño W16X45. Es posible entrar
las propiedades geométricas de la viga de forma igual como se hizo en el Ejemplo de
Vigas 1, pero el programa posee la información de la mayoría de las secciones
prefabricadas.

Nota:

Las propiedades de las secciones prefabricadas se encuentran dentro del directorio
Computer and Structures\SAP2000\. Este directorio fue creado en la computadora
al instalar el programa. El mismo usualmente se encuentra en el disco duro, por
ejemplo en c:\. Verifique en las siguientes direcciones:
36
Traducido por Luis E. Suárez y Drianfel Vázquez
Manual proporcionado en el seminario Internacional de CSI 2004 por:
www.construaprende.com / www.morrisoningenieros.com

<!-- p. 39 -->

C:\Computer and Structures\SAP2000\

C:\Programs Files\Computer and Structures\SAP2000\

De no encontrar las direcciones, realice una busqueda (“Search”) en Windows
buscando *.pro que es la extensión de los archivos que trae el programa con las
pro-piedades de las secciones prefabricadas. Es importante que ubique la dirección
correcta, por que ésta es necesaria para la definición de las propiedades de la sección.

Para definir las secciones de los elementos, seleccione “Define” en el menú principal
y luego la opción “Frame Sections”. Una forma alternativa es presionar el icono de

en el “toolbar” ubicado en la parte superior.

Seleccione “Import I/Wide Flange” como se muestra en figura, lo que lo conducirá
al “Dialog Box” llamado “Section Property File”:

37
Traducido por Luis E. Suárez y Drianfel Vázquez
Manual proporcionado en el seminario Internacional de CSI 2004 por:
www.construaprende.com / www.morrisoningenieros.com

<!-- p. 40 -->

Ubique el directorio mencionado anteriormente y seleccione el archivo de
Sections.pro. Presione “Open”. Esto lo conducirá a la siguiente ventana. Seleccione
la sección W16X45 y presione el botón de OK.

Esto lo conducirá a la siguiente ventana de “I/Wide Flange Section”

38
Traducido por Luis E. Suárez y Drianfel Vázquez
Manual proporcionado en el seminario Internacional de CSI 2004 por:
www.construaprende.com / www.morrisoningenieros.com

<!-- p. 41 -->

Verifique que el “Section Name” o nombre de la sección importada sea W16X45.
Note que la dirección del archivo se especifica en el recuadro de “Extract Data from
Section Property File”. Note que la altura, anchos y espesores del alma y de las alas
se especifican en el recuadro de “Dimensions”. Si desea ver los momentos de inercia
y otras propiedades geométricas de la sección, presione el botón de “Section
Properties”. Verifique que en el recuadro de “Materials” se encuentre STEEL.
Presione OK dos veces para regresar a la ventana principal.

Grabe su archivo (por ejemplo EjViga2).

Paso 6 [Asignar secciones de los elementos al modelo]: Luego de definir la
sección y el material, el siguiente paso es asignar dichas propiedades a los elementos.
Seleccione los elementos del modelo mediante un BI encima de cada elemento o
dibujando un cuadro que cubra la viga completa, moviendo el “mouse” mientras
mantiene apretado el BI. Del menú de “Assign” seleccione “Frame” y luego
“Sections”. De la ventana que se muestre seleccione del recuadro “Frame Sections”
el nombre de la sección W16X45 y presione OK. Al apretar OK nuevamente, el
nombre de la sección va a aparecer sobre cada elemento de la estructura.
39
Traducido por Luis E. Suárez y Drianfel Vázquez
Manual proporcionado en el seminario Internacional de CSI 2004 por:
www.construaprende.com / www.morrisoningenieros.com

<!-- p. 42 -->

Paso 7 [Definir sistemas de cargas]: En este problema en particular sólo se va a
aplicar la carga debido al peso propio de la viga. Para esto, seleccionar “Define” del
menú principal la opción de “Static Load Cases”. Esto lo llevará a la siguiente
ventana.

Reemplace el nombre de LOAD1 por otro nombre (por ejemplo, MUERTA) en el
espacio de “Load” y deje el tipo (“Type”) como “DEAD”. Verifique que el factor de
“Self Weight Multiplier” se encuentre 1. Recuerde que 1 significa que se va a incluir
el peso propio de los elementos y 0 significa que no se va a incluir. Presione el botón
de “Change Load” y OK.

Nota:

A pesar de que nuestro modelo no tiene cargas externas, es necesario definir el
sistema de carga, puesto que se va a incluir el peso propio de la misma. Además los
desplazamientos prescriptos se aplican a la estructura de igual forma que las cargas
concentradas en las juntas bajo un sistema de carga en particular.

Paso 8 [Definir desplazamiento prescripto]: Luego de definir los sistemas de carga,
el siguiente paso es asignar el desplazamiento prescripto al soporte interno. Como el
desplazamiento está en pulgadas, cambie las unidades a en la parte
inferior derecha del programa. Seleccione la junta del medio. Luego seleccione del
menú principal de “Assign” la opción de “Joint Static Loads...” y a continuación la
que dice “Displacements...”. Esta acción lo conducirán a la siguiente ventana.

40
Traducido por Luis E. Suárez y Drianfel Vázquez
Manual proporcionado en el seminario Internacional de CSI 2004 por:
www.construaprende.com / www.morrisoningenieros.com

<!-- p. 43 -->

Verifique que en “Load Case Name” aparezca el nombre MUERTA (o el nombre
que ha especificado en el sistema de carga). En el recuadro de “Displacements” en la
caja de texto (“Text box”) de “Translation Z” escriba 4. Verifique que la opción de
“Add to existing loads” está escogida. Seleccione OK. Seleccione OK. El
desplazamiento aparecerá en el modelo como se muestra a continuación. El sentido

del desplazamiento se indica con una Flecha. Recuerde grabar el archivo
actualizado de su modelo. Con esto termina la etapa de pre-procesamiento de datos.

Nota:

Los desplazamientos prescriptos sólo pueden ser aplicados directamente a juntas o
nodos.

41
Traducido por Luis E. Suárez y Drianfel Vázquez
Manual proporcionado en el seminario Internacional de CSI 2004 por:
www.construaprende.com / www.morrisoningenieros.com

<!-- p. 44 -->

Paso 9 [Analizar la estructura]: Estamos ahora listos para la etapa de “Solución” o
sea para analizar la viga. Como la estructura que estamos analizando es plana, es
recomendable que se le especifique al programa los grados de libertad que se
utilizarán. Para esto seleccione del menú principal en “Analyze”, la opción de “Set
Options”. Esto lo conducirá a la pantalla titulada “Analysis Options”. Presione el
segundo botón que dice “Plane Frame” y luego presione OK. Si no sigue este
proceso, en este ejemplo el programa correrá sin problemas porque la estructura es
estable (o sea no hay movimientos de cuerpo rígido fuera del plano) y además las
propiedades de la viga estándar W16X45 están definidas en las dos direcciones de la
sección transversal.

Para obtener la solución del problema, presione el icono de o la tecla F5.
También puede seleccionar del menú de “Analyze” la opción de “Run”.

Presione OK. El programa muestra ahora la estructura deformada como se muesrta
a continuación. La deformación está muy exagerada para mejor visualización.

Paso 10 [Diagramas de Momento]: Ahora podemos ver los resultados del análisis:
fuerzas y momentos internos, desplazamientos, rotaciones y reacciones.
Comenzaremos con el diagrama de momentos. Para ver los diagramas de fuerzas

internas seleccione el icono de en el “toolbar” de la parte superior de la pantalla
principal o seleccione del menú de “Display” la opción de “Show Element
Forces/Stresses” y escoja “Frame”.

Verifique que en el espacio de “Load” esté la opción de “MUERTA Load Case”.
Seleccione la opción de “Moment 3-3” en el recuadro de “Component”. Deje la
opción de “Auto” seleccionada en el recuadro de “Scaling”. Quite la opción del
cuadro de cotejo (“Check box”) de “Fill Diagram” y seleccione la opción de “Show
Values on Diagram”. Los resultados del diagrama de momento en k-ft se muestran
a continuación.

42
Traducido por Luis E. Suárez y Drianfel Vázquez
Manual proporcionado en el seminario Internacional de CSI 2004 por:
www.construaprende.com / www.morrisoningenieros.com

<!-- p. 45 -->

Paso 11 [Diagramas de cortante] : Repita el procedimiento del Paso 10 pero
seleccione ahora “Shear 2-2” en vez de “Moment 3-3”. El programa va a mostrar el
diagrama que se muestra a continuación.

Paso 12 [Deformada y desplazamientos en las juntas]: Cambie las unidades a
. Para observar nuevamente la deformada o curva elástica de la
estructura presione el icono o seleccione del menú de “Display” la opción de
“Show Deformed Shape”. Seleccione “Wire Shadow” y “Cubic Curve” y luego
presione OK. Note que ahora, además de la curva elástica de la viga, aparece con
otro color más opaco el eje de la estructura sin deformar. Esto se logró usando la
opción de “Wire Shadow”

43
Traducido por Luis E. Suárez y Drianfel Vázquez
Manual proporcionado en el seminario Internacional de CSI 2004 por:
www.construaprende.com / www.morrisoningenieros.com

<!-- p. 46 -->

Para obtener los desplazamientos y rotaciones en los nodos o juntas, simplemente
presione BD encima de la junta deseada. Escojamos por ejemplo la junta interna. La
siguiente figura muestra las rotaciones y desplazamientos para esta junta. Note que el
desplazamiento o traslación (“Trans”) en la dirección 3 (Global Z) es de 4 pulgadas
positivo como se había especificado.

Paso 13 [Reacciones de Apoyo] : Si desea conocer las reacciones en los apoyos,

presione el icono en el menú principal. Alternativamente, puede usar la
secuencia “Display” → “Show Element” → “Joint…”→ “Forces/Stresses”.
Aparecerá la ventana “Joint Reaction Forces” como se muestra a continuación.

44
Traducido por Luis E. Suárez y Drianfel Vázquez
Manual proporcionado en el seminario Internacional de CSI 2004 por:
www.construaprende.com / www.morrisoningenieros.com

<!-- p. 47 -->

En el recuadro del tipo “Type” escoja “Reactions” y presione OK. Aparece entonces
la viga sin deformar con las reacciones indicadas con valor, dirección y sentido como
se muestra en la siguiente figura.

45
Traducido por Luis E. Suárez y Drianfel Vázquez
Manual proporcionado en el seminario Internacional de CSI 2004 por:
www.construaprende.com / www.morrisoningenieros.com

<!-- p. 48 -->

Los momentos NO aparecen en las figuras. Para conocer sus valores, por ejemplo
en el apoyo izquierdo, haga un BD sobre la junta. Se abrirá la ventana “Joint
Reaction”, en donde aparecen, las tres componentes de al reacción y del momento.
Notar que solo la componente 2 (eje Y Global) del momento es distinta de cero.
Esto se presenta en al siguiente figura.

Fin del Ejemplo de Vigas #2

46
Traducido por Luis E. Suárez y Drianfel Vázquez
Manual proporcionado en el seminario Internacional de CSI 2004 por:
www.construaprende.com / www.morrisoningenieros.com

<!-- p. 49 -->

Capítulo
2
Ejemplo de Armaduras 1

Descripción del problema: Obtenga las fuerzas axiales en las barras y las reacciones
debido a los siguientes estados de carga: a.) carga muerta, b.) carga viva y
c.)combinación Pu = 1.2 DL + 1.6 LL donde DL signfica carga muerta (“Dead
Load”) y LL significa carga viva (“Live Load”) para la armadura que se muestra en la
figura. Utilice como elementos, angulares L4X4 de acero estructural.

Nota

Verificar la estabilidad en todos los sistemas es imperativo puesto que la estabilidad
estructural es el requisito principal de cualquier estructura. En armaduras en
particular, el diseño de estos sistemas se basan simplemente en la capacidad axial del
elemento, teniendo como resultado unos sistemas con poca redundancia y poca
capacidad para redistribuir cargas si alguno de los elementos colapsa, teniendo como
resultados sistemas altamente dependientes de su configuracion geométrica inicial.
En armaduras esta verificación es sencilla y se recomienda que siempre se realize un
analisis preliminar de estabilidad.

47
Traducido por Luis E. Suárez y Drianfel Vázquez
Manual proporcionado en el seminario Internacional de CSI 2004 por:
www.construaprende.com / www.morrisoningenieros.com

<!-- p. 50 -->

El sistema es estable externamente puesto que las reacciones no son paralelas ni
concurrentes. La estabilidad interna se verifica primordialemente con la comparación
entre desconocidas y ecuaciones disponibles. El numero de desconocidas para este
problema es 14 (11 fuerzas axiales en las barras y 3 reacciones desconocidas). El
número de ecuaciones totales equivalen al 2 ecuaciones ( Fx y Fy) por cada
junta(en este caso 7) para un total de 2 x 7=14 ecuaciones. Dado que el numero de
desconocidas es igual al numero de ecuaciones de equilibrio podemos decir
preliminarmente que el sistema es internamente estable.

El último análisis de estabilidad interna es preliminar. En la mayoria de los casos este
criterio es un buen indicador de estabilidad interna pero hay casos en que se cumple
este criterio pero la configuracion geometrica de los elementos estructurales forman
un mecanismo inestable o de colapso. Otra forma de verificar es utilizando la regla
de Cramer basado en el determinante de las ecuaciones de equilibrio de las juntas. El
programa generara errores si éste último se cumple.

Paso 1 [Establecer unidades del sistema]: Active el programa SAP2000 y cambie
las unidades a .

Paso 2 [Definición de la Geometría de la Armadura]: Seleccione del menú
principal de “File” la opción de “New Model”. Esto lo conducirá a la siguiente
pantalla.

Nota

Entre las opciones de “Templates” de SAP se encuentran dos tipos de “Templates”
de armaduras comúnmente utilizados. Estos dos son el “Sloped Truss”

y el “Vertical Truss” . Se recomienda que si la geometría
de la armadura es similar a uno de estos “Templates” se utilizen los mismos, puesto
que facilitan considerablemente la etapa de Definicion de la Geometría.

En este problema en particular utilizaremos la forma “clásica” de hacer modelos con
las grillas o nodos, como se hace en la mayoría de los programas de elementos finitos.
Vamos a tomar ventaja de la simetría del modelo para modelar inicialmente la mitad
de la armadura. Luego utilizaremos la opción de “Replicate Mirror” para generar la
48
Traducido por Luis E. Suárez y Drianfel Vázquez
Manual proporcionado en el seminario Internacional de CSI 2004 por:
www.construaprende.com / www.morrisoningenieros.com

<!-- p. 51 -->

otra mitad de la armadura. La figura a continuación facilita la interpretación del
problema. Note que se han definido cuatro líneas de grilla (3 espacios) en la
dirección perpendicular a X y dos líneas (1 espacio) en la dirección perpendicular a Z.
El programa SAP2000 ubica los espacios de la grilla centralizando el eje global justo
en la mitad de ellos por lo que tenemos que establecer 6 espacios para tener los tres
que deseamos, teniendo a su ves el eje de coordenadas en el centro.

Los demás valores mostrados fueron obtenidos mediante trigonometría. Note que el
elemento perpendicular a la diagonal superior esta ubicado a la mitad de la misma.

49
Traducido por Luis E. Suárez y Drianfel Vázquez
Manual proporcionado en el seminario Internacional de CSI 2004 por:
www.construaprende.com / www.morrisoningenieros.com

<!-- p. 52 -->

Ingrese los valores de 6 y 1 en el marco de “Number of Grid Spaces” para X y Z,
respectivamente, y/o para la dirección Y. Además ingrese 1.5 y 2.5981 en el marco
de “Grid Spacing”. Presione OK. Esto lo conducira a la pantalla principal de
SAP200. Cierre la ventana de “3D View” para visualizar mejor el modelo.

Seleccione del “toolbar” pricipal para visualizar mejor este punto de vista. Del
menú principal, seleccione “Draw” y luego la opción de “Draw Frame Element”.
Alternativamente del “toolbar” ubicado en la parte izquierda de la pantalla, seleccione
el icono de .

Nota

Note que al completar el paso anterior, el cursor (“Pointer”) de SAP2000 cambia de

a indicando así que la opcion de “Draw Frame Element” está activada. El

cursor con la forma de una flecha inclinada es la opción por omisión de SAP
para seleccionar los componentes o elementos del modelo. Sólo cuando éste último
cursor está activado es posible el seleccionar los nodos, elementos de vigas, placas,
etc.

50
Traducido por Luis E. Suárez y Drianfel Vázquez
Manual proporcionado en el seminario Internacional de CSI 2004 por:
www.construaprende.com / www.morrisoningenieros.com

<!-- p. 53 -->

Con la opción de “Draw Frame Element” activada, se va a dibujar los elementos que
comprenden la mitad derecha de la armadura como se muestra en las cuatro figuras
siguientes.

Para dibujar los elementos presione BI en el punto donde quiere empezar a dibujar el
elemento y otra vez el BI en el punto donde termina el elemento. Notará que cuando
esté haciendo esto, una línea entrecortada seguirá el cursor hasta la posición o punto
final. Luego del punto final, la línea entrecortada seguirá siguiendo el cursor
buscando el siguiente punto final del próximo elemento. De esta manera complete el
triangulo en el recuadro 3 de la siguiente figura. Cuando necesite empezar una línea o
elemento desde otro punto inicial, presione el BD para indicar que terminó esa línea.
Utilice otra vez el BI para indicar los puntos de inicio y final de la siguiente línea o
elemento a dibujar (ver cuadro 4).

Luego de dibujar los cinco elementos de la par te derecha de la armadura, presione el

icono del “toolbar” ubicado en la parte izquierda de la pantalla, para volver así a
la condición de selección.

\1. 2.

\3. 4.

Paso 3 [Dividir el elemento diagonal con la opcion “Divide Frame”]: Note que en
la figura anterior falta un elemento para terminar la mitad de la figura. Como el
elemento que falta tiene un extremo coincidente con la mitad del elemento diagonal
de mayor longitud, vamos a utilizar una de las herramientas para la definición de
geometrías que posee el programa la opción de “Divide Selected Frames”.
Seleccione el elemento a dividir, haciendo BI sobre el elemento diagonal. Del menú
de “Edit” seleccione la opción de “Divide Frames...”. Esto lo conducirá a la pantalla
de “Divide Selected Frames” que se muestra a continuación.

51
Traducido por Luis E. Suárez y Drianfel Vázquez
Manual proporcionado en el seminario Internacional de CSI 2004 por:
www.construaprende.com / www.morrisoningenieros.com

<!-- p. 54 -->

Verifique la opción de “Divide into” esté seleccionada y que haya un número 2
en su caja de texto. Seleccione OK. Note que el elemento diagonal aparece
ahora dividido en dos, dado que hay un nodo intermedio, como se muestra en la
siguiente figura.

Dibuje un elemento entre la junta o nodo recién creado y aquella en la barra
inferior, usando el procedimiento descrito en el paso 3. El resultado debe ser el

que se encuentra en el paso 2 de la siguiente figura. Grabe su modelo .

\1. 2.

Paso 4 [Imagen de Reflejo con la opción de “Replicate Mirror”]: Note que
ahora la mitad de la estructura se encuentra completada. Para completar la parte
izquierda del modelo utilizaremos otra opción de SAP2000 que es útil para
geometrías simétricas o simplemente para facilitar el desarrollo de modelos.
Seleccione todos los elementos haciendo un recuadro que cubra la estructura con
el “mouse”, o haciendo BI en cada uno de los elementos. Del menú principal de
“Edit” seleccione la opción de “Replicate”. Habra la opción o el “tab” de
“Mirror” (espejo). Esto lo conducirá a la pantalla que se muestra a continuación.

52
Traducido por Luis E. Suárez y Drianfel Vázquez
Manual proporcionado en el seminario Internacional de CSI 2004 por:
www.construaprende.com / www.morrisoningenieros.com

<!-- p. 55 -->

Seleccione la opción de “YZ Plane” puesto que éste es el plano donde se debería
ubicar un espejo para formar la otra mitad de la imagen. Seleccione OK. El
modelo debe estar como se muestra a continuación.

Paso 5 [Unión de elementos con la opcion de “Join Frames”]: La geometría
del modelo esta prácticamente completada excepto que hay un nodo de más en
el elemento central. Para eliminar este nodo o convertir los dos elementos
adyacentes en uno, seleccione los dos elementos a unir. Del menú de “Edit”
seleccione la opción de “Join Frame”. Esto automáticamente convertirá los dos
elementos en uno. Note que si se dejan estos dos elementos sin unir, se crearía
inestabilidad interna en la armadura.

Paso 6 [Definición de las condiciones de borde]: Seleccione el nodo en el
extremo izquierdo haciendo BI sobre el mismo. Presione del “toolbar”
principal en la parte superior de la pantalla. De la ventana de “Joint Restraints”

que aparece, seleccione el apoyo del marco de “Fast Restraints”. Presione
OK. Repita el procedimiento anterior con el nodo en el extreme derecho, pero

53
Traducido por Luis E. Suárez y Drianfel Vázquez
Manual proporcionado en el seminario Internacional de CSI 2004 por:
www.construaprende.com / www.morrisoningenieros.com

<!-- p. 56 -->

seleccione ahora del marco de “Fast Restraints”. El modelo debe estar
como aparece en la figura a continuaci ón.

Paso 7 [Asignar las secciones de los porticos]: Seleccione todos los
elementos de la armadura haciendo un recuadro que cubra la armadura completa
o con Ctrl.+A, haciendo BI sobre cada uno de los elementos. El procedimiento
para asignar las secciones angulares a cada barra se resume a continuación y se
encuentra mejor detallado en el PASO 5 del Ejemplo 2 en el Capítulo de Vigas.

Assign → Frame → Sections... → Import Double Angle → Busque y
abra el archive Sections.Pro → Escoja 2L 4X4X1/2→ OK →Verifique
que el material sea acero (“STEEL”) →OK→OK

Paso 8 [Eliminar grados de libertad rotacionales de lo nodos o elementos]:
Note que la definición geométrica de la armadura se generó utilizando las
herramientas de “Draw Frame”. Como consecuencia de esto el programa
presume que los elementos dibujados son elementos de viga o MARCO, por lo
q ue hay que eliminar los grados de libertad rotacionales para que la estructura sea
una “armadura ideal”. Para esto seleccione todos los elementos del modelo. Del
menú principal de “Assign” seleccione “Frame” y luego “Releases…”. Esto lo
conducirá a la pantalla siguiente de “Frame Releases”.

Seleccione las dos opciones de “Moment 33 (Major)” para eliminar esto grados
de libertad en los extremos de los elementos. Seleccione OK. En el modelo
aparecerán unos nodos de color verde cerca de cada extremo Inicial (“Start”) y
Final (“End”) indicando que hay un grado de libertad liberado (“Released”).

54
Traducido por Luis E. Suárez y Drianfel Vázquez
Manual proporcionado en el seminario Internacional de CSI 2004 por:
www.construaprende.com / www.morrisoningenieros.com

<!-- p. 57 -->

Nota

En el caso de un análisis en tres dimensiones, si va a “liberar” estos grados de
libertad, es necesario que también seleccione los grados de “Moment 22 (Minor)” y el
“Torsion” puesto que dependiendo de la posición especial del elemento, el grado de
libertad de momento correspondería al grado de libertad torsional de otro elemento.

Paso 9 [Definir sistemas de cargas]: Los pasos se describen a continuación.

a. La secuencia “Define” →“Static Load Cases…” lo conducirá a la
siguiente ventana.

55
Traducido por Luis E. Suárez y Drianfel Vázquez
Manual proporcionado en el seminario Internacional de CSI 2004 por:
www.construaprende.com / www.morrisoningenieros.com

<!-- p. 58 -->

b. Cambie el nombre de LOAD1 a MUERTA y presione el botón de
“Change Load”

c. Escriba el nombre de VIVA en la caja de texto de “Load”, cambie el
tipo de carga en la caja de texto de “Type” a LIVE y escriba 0 en la
caja de texto de “Self Weight Multiplier”. Presione el botón de “Add
New Load”. Seleccione OK.

Paso 10 [Definir Combinación de carga]: Para definir la combinación de carga
seleccione del menú de “Define” la opción de “Load Combinations…”. Esto lo
conducirá a la ventana de “Define Load Combinations” que se muestra a
continuación.

Seleccione el botón de “Add New Combo” lo que lo conducirá a la ventana de
“Load Combination Data” que se muestra a continuación.

56
Traducido por Luis E. Suárez y Drianfel Vázquez
Manual proporcionado en el seminario Internacional de CSI 2004 por:
www.construaprende.com / www.morrisoningenieros.com

<!-- p. 59 -->

En el marco de “Load Combination Name” escriba un nombre para la
combinación. En este caso vamos a dejar el nombre por omisión de COMB1.
Verifique que en el recuadro de “Load Combination Type” se halle la opción de
ADD (o sea suma de casos de cargas). En el recuadro de “Title” escriba un
título descriptivo de la combinación deseada (por ejemplo 1.2 Muerta + 1.6
Viva). Este título es útil para interpretar los archivos de resultados del programa.

Dentro del recuadro de “Define Combination” en la caja de texto de “Scale
Factor” escriba 1.2 y presione el botón de “Add”. Cambie la opción del la caja
d e combo de “Case Name” a Viva Load Case y el “Scale Factor” a 1.6. Presione
“Add”. Presione OK dos veces para volver a la pantalla principal.

Paso 11 [Definir las cargas del sistema]: Seleccione las juntas identificadas
como E, F y G en el dibujo de la armadura al comienzo del ejemplo. Presione el
icono de “Assign Joint Loading” . Esto lo conducirá a la siguiente ventana.

Verifique que en el recuadro de “Load Case Name” esté el sistema de cargas
MUERTA. Escriba -1 en la dirección “Force Global Z”. Presione OK.

S eleccione las juntas E y G. Presione . Cambie el “Load Case Name” de
MUERTA a VIVA y escriba -3 en la caja de texto de “Force Global Z” como se
muestra a continuación. Presione OK.

57
Traducido por Luis E. Suárez y Drianfel Vázquez
Manual proporcionado en el seminario Internacional de CSI 2004 por:
www.construaprende.com / www.morrisoningenieros.com

<!-- p. 60 -->

Seleccione la junta F y repita el procedimiento anterior pero escribiendo -2 en la
caja de la “Force Global Z”. Esto se muestra a continuación.

Nota

58
Traducido por Luis E. Suárez y Drianfel Vázquez
Manual proporcionado en el seminario Internacional de CSI 2004 por:
www.construaprende.com / www.morrisoningenieros.com

<!-- p. 61 -->

Note que en SAP2000 solo tienen que definir los “Static Load Cases” y el programa
se encarga de hacer las combinaciones.

Con esto concluimos la etapa de pre-procesamiento de datos.

Paso 12 [Analizar la estructura]: Recuerde grabar su modelo . Abriendo
el menú de “Analyze”, y dentro de la opción de “Set Options”, especifique la

opción “Plane Frame” del cuadro de “Fast DOFs”. Presione OK.

Efectúe el análisis presionado o con la opción de “Run” del menú de
“Analyze”. En el primer caso escoja “Run” de las tres opciones de “Run
Options”. Verifique que no haya un mensaje de error en la ventana “Analysis
Complete” que aparece.

Paso 13 [Resultados de Reacciones]: Para ver las reacciones presione el

icono de . Esto lo llevará a la siguiente ventana. Note que en recuadro de
“Load” se hallan los dos sistemas de carga (MUERTA y VIVA) y la
combinación COMB1 que se habían definido. Seleccione “MUERTA Load
Case” y presione OK. Repita el procedimiento seleccionando VIVA y luego
COMB1. Los resultados se muestran en las tres figuras subsiguientes.

59
Traducido por Luis E. Suárez y Drianfel Vázquez
Manual proporcionado en el seminario Internacional de CSI 2004 por:
www.construaprende.com / www.morrisoningenieros.com

<!-- p. 62 -->

MUERTA

VIVA

COMB1

60
Traducido por Luis E. Suárez y Drianfel Vázquez
Manual proporcionado en el seminario Internacional de CSI 2004 por:
www.construaprende.com / www.morrisoningenieros.com

<!-- p. 63 -->

Paso 14 [Resultados de fuerzas internas axiales]: Para ver las fuerzas axiales

presione el icono de . Esto lo llevará a la siguiente ventana de “Member
Force Diagram for Frames”. Note que al igual que en las reacciones, en el
recuadro de “Load” se hallan los sistemas de carga (MUERTA y VIVA) y la
combinación COMB1 que se habían definido.

Seleccione “MUERTA Load Case” del cuadro “Load”. Marque la opción de
“Show Values on Diagram” y presione OK. Repita el procedimiento
seleccionand o VIVA y luego COMB1. Los resultados se muestran a
continuación .

61
Traducido por Luis E. Suárez y Drianfel Vázquez
Manual proporcionado en el seminario Internacional de CSI 2004 por:
www.construaprende.com / www.morrisoningenieros.com

<!-- p. 64 -->

MUERTA

VIVA

62
Traducido por Luis E. Suárez y Drianfel Vázquez
Manual proporcionado en el seminario Internacional de CSI 2004 por:
www.construaprende.com / www.morrisoningenieros.com

<!-- p. 65 -->

COMB1

Paso 15 [Tablas con las fuerzas internas]: También es posible ver las fuerzas
internas en la forma de una tabla. Para esto se aprieta el icono “Display Output

Tables” . De la ventana “Select Output” se debe seleccionar el estado de
carga para el cual se quieren ver los resultados. Luego se selecciona una barra
(con BI) y presionando BD se habre la ventana “Frame Element Forces” donde
se listan en una tabla todas las seis posibles fuerzas internas. La tabla contiene el
número de la barra o elemento, el estado de carga o combinación, y la fuerza
axial (P), los dos cortantes (V2 y V3), el torque o momento torsor (T), y los dos
momentos flectores (M2 y M3). Estos valores se dan para varios puntos a lo
largo del elemento con la posición medida en un sistema de ejes locales. Notar
por último que el elemento en cuestión comienza a parpadear en la pantalla
cuando se habre la tabla

Nota

Si en la ventana que se abre con el icono se escoge “Moment 3-3” o “Shear 22” y la carga MUERTA o COMB1, el programa los diagramas de momento y
cortante, dado que se está incluyendo el peso propio de las barras en estos casos de
carga. Lo mismo puede observarse cuando se tabulan las fuerzas internas en las
tablas de resultados.

Fin del Ejemplo de Armaduras #1

63
Traducido por Luis E. Suárez y Drianfel Vázquez
Manual proporcionado en el seminario Internacional de CSI 2004 por:
www.construaprende.com / www.morrisoningenieros.com

<!-- p. 66 -->

Ejemplo de Armaduras 2

Descripción del problema: Para la armadura que se muestra en la figura, obtenga las
fuerzas axiales o normales para los siguientes casos de carga:

a.) carga muerta

b.) carga viva

c.) combinación Pu = 1.2 DL + 1.6 LL.

donde DL significa carga muerta (“Dead Load”) y LL significa carga viva (“Live
Load”). Utilice como elementos, angulares 2L 6 X 6 X 3/4 para los elementos en
compresión (arriba), 2L 4 X 4 X 1/2 para los elementos interiores y 2L 3 X 3 X 1/2
para los elementos en tensión (abajo). Los elementos que unen las dos armaduras
planas son tubos TS 6 X 4 X 1/2.

Las cargas muerta y viva son de 1.5k y 2.5k respectivamente, y están aplicadas en las
cuatros juntas inferiores.

Verificación de estabilidad interna:

64
Traducido por Luis E. Suárez y Drianfel Vázquez
Manual proporcionado en el seminario Internacional de CSI 2004 por:
www.construaprende.com / www.morrisoningenieros.com

<!-- p. 67 -->

Número de elementos = 11; Número de reacciones = 3; Número de juntas = 7. El
número de elementos y reacciones es 11+3 = 14 y el número de ecuaciones de
equilibrio es 2 x 7 = 14. Por lo tanto la armadura es internamente estable. También
es externamente estable puesto que las reacciones no son concurrentes ni paralelas.

Paso 1 [Escoger el sistema de unidades]: Inicie el programa SAP2000 y cambie
las unidades a .

Paso 2 [Definición de la geometría]: Del menú principal de “File” seleccione “New

Model from Template…” y escoja la opción de “Sloped Truss” . En la
ventana de “Sloped Truss” escriba 3 para el “Number of Bays”, 12 para la opción de
“Truss Height” y 12 para la opción de “”Truss Bay Length”. Presione OK. Esto
genera la armadura tal y como se muestra en la figura anterior.

Nota

En este problema NO cierre la ventana de 3-D ya que la misma se utilizará en pasos
posteriores. Aunque hasta ahora sólo se ha generado una cara de la armadura, más
adelante se verá cómo utilizando otras herramientas de SAP2000 es posible
“convertir” este problema bidimensional al tridimensional deseado.

Paso 3 [Crear la segunda armadura con la opción de “Copy”]: Como la segunda
armadura es idéntica a la armadura construida en el paso anterior, se va a utilizar la
opción de “Copy” para crear el modelo tridimensional. Seleccione todos los
elementos de la armadura haciendo un recuadro que cubra toda la estructura o
usando Ctrl + A. Del menú de “Edit” seleccione “Copy” y luego seleccione
“Paste…”. Esto lo conducirá a la pantalla de “Paste Coordinates” siguiente.

65
Traducido por Luis E. Suárez y Drianfel Vázquez
Manual proporcionado en el seminario Internacional de CSI 2004 por:
www.construaprende.com / www.morrisoningenieros.com

<!-- p. 68 -->

Escriba -12 (pies) en la caja de texto de “Delta Y” y presione OK. En la ventana “3D Views” aparece otra armadura plana por delante de la creada en el paso 2.

Paso 4 [Crear elementos de unión]: Haga BI sobre la ventana derecha para

activarla. Presione el icono de del “toolbar” principal para obtener una vista en
planta de la armadura. Note que en la parte superior de la ventana dice “X-Y Plane
@ Z=12” o sea que estamos ubicados en un plano que pasa por las juntas superiores
de las dos armaduras. Dibuje tres elementos para unir las armaduras con el icono de

. El uso de esta herramienta se explicó en el Paso 3 del Ejemplo de Armaduras

\1. Presione el botón de en el “toolbar” principal para bajar al nivel Z = 0. La
ventana debe decir ahora “X-Y Plane @ Z = 0”. Dibuje los cuatro elementos de
unión. Presione el botón de para volver a la vista original del modelo.

Asegúrese de presionar el icono para recuperar el puntero (“Pointer”) original.

Paso 5 [Crear grilla en la coordenada de la segunda armadura]: Del menú
principal de “Draw” seleccione la opción de “Edit Grid…”. Esto lo conducirá a la
ventana de “Modify Grid Lines” que se muestra a continuación.

66
Traducido por Luis E. Suárez y Drianfel Vázquez
Manual proporcionado en el seminario Internacional de CSI 2004 por:
www.construaprende.com / www.morrisoningenieros.com

<!-- p. 69 -->

Seleccione la opción Y en el recuadro de “Direction” y escriba -12 en la caja de texto
de “Y Location”, presione el botón de “Add Grid Line”. La pantalla debe aparecer
como se muestra arriba. Presione OK.

Paso 6 [Definición de grupos]: Haga BI (en cualquier lugar) en la ventana en dos
dimensiones X-Z para activar la misma. Del menú pricipal de “View” seleccione la
opción de “Set Elements…” o del “toolbar” principal seleccione el icono .
Cualquiera de estas opciónes lo conducirá a las siguiente pantalla de “Set Elements”.

67
Traducido por Luis E. Suárez y Drianfel Vázquez
Manual proporcionado en el seminario Internacional de CSI 2004 por:
www.construaprende.com / www.morrisoningenieros.com

<!-- p. 70 -->

En el recuadro de “Frames” seleccione la opción de “Labels” para ver la numeración
de los elementos. Presione OK. El programa muestra la numeración de las barras
como se muestra a continuación. Note que la ventana derecha tiene escrito en la
parte superior “X-Z Plane @ Y=0”. Para ver la segunda armadura presione el icono

. Note que los números cambiaron y ahora la ventana dice “XZ Plane @ Y= -
12”

Nota

Esta venta de “Set Elements” es una de las herramientas más usadas en SAP2000.
Como se puede ver, además de activar las numeraciones de los elementos (“Labels”),
con la misma también se puede activar la opción para presentar las secciones de los
elementos (“Sections”), los nodos liberados (“Releases”), el sistema de ejes (“Local
Axes”), etc. Todas estas opciones son muy útiles para facilitar la interpretación y
manejo de los modelos y se invita al lector a que active y desactive cada uno de ellas
para que observe su resultado. Estas opciones tienen solamente un efecto visual y no
afectan el modelo generado.

Del menú principal de “Define” seleccione la opción de “Groups…”. Esto lo
conducirá a la siguiente ventana de “Define Groups”. El programa tiene por
omisión un grupo llamado ALL, el cual incluye a todos los elementos. En la caja de
texto escriba un nombre descriptivo para los elementos superiores, por ejemplo
ARRIBA y presione el botón de “Add New Group Name”. Repita el procedimiento
para asignarle un nombre a los otros grupos, por ejemplo escribiendo ABAJO,

INTERMEDIO y UNION como se muestra en la figura. Presione para volver
a la pantalla inicial de “X-Z Plane @ Y=0”.

68
Traducido por Luis E. Suárez y Drianfel Vázquez
Manual proporcionado en el seminario Internacional de CSI 2004 por:
www.construaprende.com / www.morrisoningenieros.com

<!-- p. 71 -->

Paso 7 [Asignación de elementos a grupos]: Seleccione los elementos de arriba de
la cuerda superior (elementos 6, 4, 5 y 11), por ejemplo haciendo BI sobre cada uno

de ellos. Presione para pasar al plano “X-Z @ Y = 12” y seleccione los
elementos (17, 15, 16 y 22). Del menú principal de “Assign” seleccione la opción de
“Group Name…”. Esto lo conducirá a la siguiente ventana de “Assign Group”.

Seleccione la opción de ARRIBA y presione OK. Ahora seleccione los
elementos de la cuerda inferior de la armadura (elementos 12, 13 y 14), presione

y seleccione los elementos (1, 2 y 3). Otra vez seleccione del menú de
“Assign” la opción de “Group Names…”, seleccione ABAJO y presione OK.

Seleccione los elementos intermedios (elementos 9, 7,10 y 8), presione y

69
Traducido por Luis E. Suárez y Drianfel Vázquez
Manual proporcionado en el seminario Internacional de CSI 2004 por:
www.construaprende.com / www.morrisoningenieros.com

<!-- p. 72 -->

seleccione los elementos correspondientes de la otra armadura (20, 18, 21 y 19) y
repita el procedimiento anterior pero escogiendo INTERMEDIO en la ventana

de “Assign Group”. Seleccione el icono de y seleccione los elementos 23,

24 y 25, presione y seleccione los elementos 26, 27, 28 y 29 y repita el
procedimiento seleccionando UNION. Seleccione para volver a la vista
original.

Paso 8 [Definición de soportes en la segunda armadura]: Note que la opción de
“Copy” no copia las condiciones de borde o soportes de la armadura. Asigne a la
segunda armadura las mismas condiciones de borde que la de la armadura original
haciendo uso del icono . El procedimiento ha sido detallado en el Paso 3 del
Ejemplo de Vigas 2.

Paso 9 [Asignar secciones a los elementos]: Antes de asignar las secciones a los
elementos apague la opción de “Labels” presionando el icono de y quitando la
opción de “Labels” de las opciones que se presentan allí.

Luego del menú principal de “Select” seleccione “Select” y subseleccione
“Groups…”. Esto lo conducirá a la siguiente ventana de “Select Groups”.

Seleccione ARRIBA y presione OK. Note que automáticamente el programa ha
seleccionado todos los elementos del grupo correspondiente, o sea aquellos en la
cuerda superior.

Del menú de “Assign” seleccione “Frame” y luego “Sections”. Importe del
archivo correspondiente los angulares dobles 2L 6 X 6 X 3/4 y asigne es ta
sección a los elementos antes seleccionados. El procedimiento de asignar
70
Traducido por Luis E. Suárez y Drianfel Vázquez
Manual proporcionado en el seminario Internacional de CSI 2004 por:
www.construaprende.com / www.morrisoningenieros.com

<!-- p. 73 -->

secciones a los elementos fue explicado con detalles en el Ejemplo de Vigas 2 en
los Pasos 5 y 6. Repita nuevamente la secuencia “Select” → “Select” →
“Groups…” y seleccione esta vez el grupo llamado INTERMEDIO. Importe y
asigne los doble angulares 2L 4 X 4 X 1/2 a estos elementos. Repita el
procedimiento para los elementos de abajo y asigne a estos los doble angulares
2L 3 X 3 X 1/2. Por último, repita el procedimiento para los elementos de
UNION, usandotubos (Box/Tubes) TS 6 X 4 X 1/2.

Recuerde grabar el archivo actualizado de su modelo (por ejemplo Armadura2).

Paso 10 [Definir sistemas de carga]: Del menú de “Define” seleccione “Static
Load Cases…”. Defina dos sistemas de cargas, MUERTA y VIVA, sin incluir el
peso propio de los elementos (escriba 0 en el “Self Weight Multiplier”). El
procedimiento para definir los sistemas de cargas se explicó en detalle en el Paso
7 del Ejemplo de Vigas 2.

Paso 11 [Definir combinaciones de cargas]: Del menú de “Define” seleccione
“Loads Combinations…”. Defina la combinación de carga de Pu = 1.2 DL +
1.6 LL. El procedimiento para definir las combinaciones de cargas se discutió en
detalle en el Paso 11 del Ejemplo de Armaduras 1.

Paso 12 [Definir las cargas concentradas]: El procedimiento para asignar las
cargas es el mismo que se usó en todos los ejemplos anteriores (ver Paso 12 en
Ejemplo de Armadura 1). En este caso en particular las cargas se van a ubicar en
las cuatro juntas centrales de la parte inferior de la armadura. Como el modelo
es tridimensional se recomienda que se sigan los pasos que se describen a
continuación para seleccionar las juntas. Haga BI sobre la pantalla de la derecha

para activarla. Selccione el icono de para ver la armadura desde planta.

Utilice las herramientas de y para ubicar los cuatro nodos deseados.
Seleccione los nodos y aplique las cargas en las juntas en la dirección en la
dirección “GLOBAL Z” con valor negativo.

Luego de aplicar las cargas presione el icono de para volver a la vista lateral
del modelo.

Paso 13 [Elimina r grados de libertad rotacionales y torsionales de lo nodos
o elementos]: Al usar los “Templates” de SAP2000, por omisión la armadura
se genera con elementos de vigas o MARCOS (“Frame Elements”). Sabemos
que las armaduras ideales no se analizan de esta forma sino que sólo se
consideran los grados de libertad de translación y las cargas axiales. Por lo tanto,

71
Traducido por Luis E. Suárez y Drianfel Vázquez
Manual proporcionado en el seminario Internacional de CSI 2004 por:
www.construaprende.com / www.morrisoningenieros.com

<!-- p. 74 -->

si se desea usar este modelo tradicional se deben eliminar los grados de libertad
sobrantes. Para esto del menú de “Select” use la secuencia → Select →
Groups… → ALL para seleccionar todos los elementos del modelo. Del menú
principal de “Assign” seleccione “Frame” y luego “Releases…”. Esto lo
conducirá a la pantalla siguiente de “Frame Releases”.

Seleccione las fuerzas internas que se liberarán (o equivalentemente grados de
libertad que se eliminarán) como se muestran en la figura. Más información
sobre la liberación de fuerzas internas o eliminación de grados de libertad se
presentó en el Paso 9 del Ejemplo de Armaduras 1. Si quiere ver los grados de
libertad liberados seleccione “Releases” en la ventana que se abre con icono
de “Set Elements”.

Paso 14 [Analizar la estructura]: Recuerde que debe grabar su modelo
antes de ejecutar el análisis. Especifique en el menú de “Analyze”, dentro de la
opción de “Set Options…” la opción de “Fast DOFs” de armadura espacia l
(“Space Truss”):

Corra el análisis presionado o del menú de “Analyze” utilice la opción de
“Run”. Presione OK.

72
Traducido por Luis E. Suárez y Drianfel Vázquez
Manual proporcionado en el seminario Internacional de CSI 2004 por:
www.construaprende.com / www.morrisoningenieros.com

<!-- p. 75 -->

Paso 15 [Resultados]: En la siguiente figura se muestra la estructura deformada
en la parte izquierda y las fuerzas axiales para la combinación de carga en la parte
derecha. En la figura subsiguiente se muestran las reacciones para la misma
c ombinación.

DEFORMADA Y AXIALES (COMB1)

REACCIONES (COMB1)

Para ver cada una de las reacciones o l as fuerzas axiales individuales lea los Pasos
15 y 16 del Ejemplo de Armaduras 1.

Fin del Ejemplo de Armaduras #2

73
Traducido por Luis E. Suárez y Drianfel Vázquez
Manual proporcionado en el seminario Internacional de CSI 2004 por:
www.construaprende.com / www.morrisoningenieros.com

<!-- p. 76 -->

Capítulo
3
Ejemplo de MARCOS 1

Descripción del problema: Para la estructura de MARCO plano que se muestra,
obtenga las reacciones y los diagramas de momento para las siguientes
combinaciones de carga y para una envolvente que contenga todos los sistemas de
cargas y combinaciones que se describen a continuación. Utilice secciones de 12”x
24” para las columnas y de 12”x18” para las vigas. Utilice como material el hormigón
que tiene el programa por omisión.

Sistemas de Cargas

a.) carga muerta [DL] (1 k/ft en todas las vigas)

b.) carga viva [LL] (0.7 k/ft en todas las vigas)

74
Traducido por Luis E. Suárez y Drianfel Vázquez
Manual proporcionado en el seminario Internacional de CSI 2004 por:
www.construaprende.com / www.morrisoningenieros.com

<!-- p. 77 -->

c.) carga de terremoto [E] (5 k y 10 k en las juntas 2 y 3 respectivamente)

Combinaciones de Carga

d.) COMB1: 1.4 DL + 1.7 LL

e.) COMB2: 0.9 DL + 1.3 E

f.) COMB3: Envolvente

Paso 1 [Establecer unidades del sistema]: Active el programa SAP2000 y cambie
las unidades a .

Paso 2 [Definición de geometría]: Del menú principal de “File” seleccione “New

Model from Template…” y seleccione la opción de “Portal Frame” . En la
ventana del “Portal Frame” escriba 2 para el “Number of Stories” (número de pisos),
2 en el “Number of Bays” (número de tramos o vanos), 12 para la opción de “Story
Height” (altura de piso) y 24 en la opción de “”Bay Length” (largo del tramo o vano).
Presione OK. Cierre la ventana de 3-D. Esto le genera el marco tal y como se
muestra en la siguiente figura.

75
Traducido por Luis E. Suárez y Drianfel Vázquez
Manual proporcionado en el seminario Internacional de CSI 2004 por:
www.construaprende.com / www.morrisoningenieros.com

<!-- p. 78 -->

Paso 3 [Definir y asignar las secciones de los elementos]: Seleccione las

columnas del MARCO presionando el icono de del “toolbar” ubicado en la
parte izquierda de la pantalla principal de SAP2000. Esta opción también se puede
obtener mediante los siguientes pasos:

Menú principal de “Select”→ “Select” → “Intercepting Line”

Este icono activa una de las opciones para seleccionar elementos en SAP2000 la cual
se llama Modo de Selección de Intercepción de Línea (“Set Intercepting Line Select
Mode”). Como sugiere el título, ésta es una opción para seleccionar elementos
mediante el trazado de una línea que intercepta a todas las líneas o elementos que se
desean seleccionar.

Luego de activar esta opción, trace apretando el “mouse”, una línea “interceptadora”
de izquierda a derecha que cruce desde la columna izquierda hasta la última derecha
del primer piso. Esto seleccionará las tres columnas del primer piso. Note que este
método es más rápido que seleccionar las columnas una a una con el BI,
especialmente si hay muchos elementos. Repita el procedimiento para seleccionar
todas las columnas del segundo piso.

El procedimiento para definir y asignar las secciones de los elementos se explicó
detalladamente en el capítulo de vigas y en el capítulo de armaduras. Por lo tanto
aquí sólo se listarán los pasos mínimos para definir y asignar las secciones a las
columnas. Primero cambie las unidades a .

Presione el icono de o del menú principal use las secuencias: “Assign” →
“Frame” → Sections…” en la ventana que se abre, presione Modify/Show Section y
cambie el material a CONC, los tamaños a 24 (“depth”) y 12 (“width”) y el nombre
(“Sections Name”) a COLUMNAS. Vuelva a la pantalla principal ( → OK → OK)

Seleccione nuevamente el icono de , pero ahora arrastre el cursor de arriba hacia
abajo para seleccionar las vigas. Siga el procedimiento a continuación para definir y
asignar las secciones a las vigas.

Comenzando en el menú principal de “Assign”, use “Frame” → “Sections…” o el
icono equivalente, seleccione Add Rectangular y cambie el material a CONC, los
tamaños a 18 (“depth”) y 12 (“width”) y el nombre a VIGAS. Salga con OK →
OK.

Cambie las unidades a . El modelo debe verse como se muestra a
continuación.

76
Traducido por Luis E. Suárez y Drianfel Vázquez
Manual proporcionado en el seminario Internacional de CSI 2004 por:
www.construaprende.com / www.morrisoningenieros.com

<!-- p. 79 -->

Recuerde grabar el archivo actualizado de su modelo (por ejemplo Portico1).

Paso 4 [Definir condiciones de apoyo]: El procedimiento para definir las
condiciones de borde fue presentado en detalle en el Paso 4 del Ejemplo de
Vigas 1 y en los ejemplos anteriores. Para asignar las condiciones de borde,
seleccione los tres nodos inferiores y presione el icono de “Assign Joint
Restraints”. Cambie las condiciones de las columnas exteriores de articulado

a fijo . El modelo hasta esta etapa se muestra a continuación. Presione
OK.

77
Traducido por Luis E. Suárez y Drianfel Vázquez
Manual proporcionado en el seminario Internacional de CSI 2004 por:
www.construaprende.com / www.morrisoningenieros.com

<!-- p. 80 -->

Paso 5 [Definir sistemas de cargas]: Del menú de “Define” seleccione “Static
Load Cases…”. Defina tres sistemas de cargas (MUERTA, VIVA y TERRE).
Incluya el peso propio de los elementos solamente para el de sistema de carga
muerta (MUERTA) escribiendo 1 en el “Self Weight Multiplier” para este caso y
0 para los sistemas de carga viva (VIVA) y terremoto (TERRE). Note que,
como se muestra en la figura a continuación, se ha escogido QUAKE como
“Type” para el terremoto, LIVE para la carga viva y DEAD para la carga
muerta. El procedimiento para definir los sistemas de cargas han sido
pres entado en detalle en el Paso 7 del Ejemplo de Vigas 2.

Nota

Note que el peso muerto (“Self Weight Multiplier” = 1) sólo se incluye en la
definición del sistema de carga MUERTA puesto que si se incluyera en cualquiera de
los otros sistemas de cargas implicaría que al hacer cualquier combinación de esos
dos sistemas el peso propio de los elementos se estaría considerando más de una vez.

78
Traducido por Luis E. Suárez y Drianfel Vázquez
Manual proporcionado en el seminario Internacional de CSI 2004 por:
www.construaprende.com / www.morrisoningenieros.com

<!-- p. 81 -->

Paso 6 [Definir combinaciones de cargas]: El procedimiento para definir las
combinaciones de cargas ha sido presentado en detalle en el Paso 11 del Ejemplo
de Armaduras 1. A continuación se resumen los pasos esenciales a seguir para
desarrollar las combinaciones de carga y la envolvente.

Para definir la primera combinación de carga de 1.2 DL + 1.6 LL, siga los
siguientes pasos.

\1. Del menú de “Define” seleccione “Loads Combination…”.

\2. En la nueva ventana presione “Add New Combo”.

\3. En al ventana “Load Combination Data”, deje COMB1 en el recuadro

de “Load Combination Name”.

\4. Deje ADD en el recuadro “Load Combination Type”.

\5. Cambie lo que aparezca en el recuadro de “Title” a 1.4DL + 1.7 LL.

\6. En la caja de “Scale Factor” escriba 1.4 y verifique que a la izquierda en

el recuadro de “Case Name” esté el sistema de “MUERTA Load Case”.

Presione ADD.

\7. Cambie en el recuadro de “Case Name” el sistema de carga a “VIVA

Load Case” y escriba 1.7 en el cuadro de “Scale Factor”. Presiona ADD.

La ventana se debe ver como se muestra a continuación.
79
Traducido por Luis E. Suárez y Drianfel Vázquez
Manual proporcionado en el seminario Internacional de CSI 2004 por:
www.construaprende.com / www.morrisoningenieros.com

<!-- p. 82 -->

\8. Presione el botón de OK una sola vez.

Para la segunda combinación de carga de 0.9 DL + 1.3 E, siga los siguientes
pasos.

\1. De la ventana “Define Load Combinations” seleccione “Add New

Combo”.

\2. Deje COMB2 en el recuadro de “Load Combination Name”

\3. Deje ADD en el recuadro “Load Combination Type”.

\4. Escriba 0.9DL + 1.3 E en el recuadro de “Title”.

\5. En la caja de “Scale Factor” escriba 0.9 y verifique que en el recuadro de

“Case Name” esté el sistema de “MUERTA Load Case”. Presione

MODIFY.

80
Traducido por Luis E. Suárez y Drianfel Vázquez
Manual proporcionado en el seminario Internacional de CSI 2004 por:
www.construaprende.com / www.morrisoningenieros.com

<!-- p. 83 -->

\6. Haga un BI sobre el sistema de carga “VIVA Load Case” y presione

DELETE para borrarlo de esta combinación.

\7. En la caja de “Scale Factor” escriba 1.3 y escoja el sistema de “TERRE

Load Case” del recuadro de “Case Name”. Presione ADD. La ventana

debe verse como se muestra en la figura a continuación.

\8. Presione OK para regresar a la ventana de “Define Load Combinations”

Para la combinación de carga ENVOLVENTE de todos los sistemas y
combinaciones de carga siga los siguientes pasos.

\1. De la ventana que está activada, seleccione “Add new Combo”.

\2. Deje COMB3 en el recuadro de “Load Combination Name” (o escriba

este nombre si no aparece COMB3).

81
Traducido por Luis E. Suárez y Drianfel Vázquez
Manual proporcionado en el seminario Internacional de CSI 2004 por:
www.construaprende.com / www.morrisoningenieros.com

<!-- p. 84 -->

\3. Cambie de ADD a ENVE en el recuadro “Load Combination Type”.

\4. Cambie COMB3 (o lo que hubiera) en el recua dro de “Title” a

ENVOLVENTE.

\5. Seleccione los sistemas de carga haciendo BI sobre cada uno de ellos y

presione DELETE para borrarlos.

\6. Verifique que en el cuadro de “Case Name” aparezca MUERTA y que el

“Scale Factor” esté en 1. Presione ADD.

\7. Cambie el “Case Name” a “VIVA Load Case” y presione ADD.

\8. Cambie el “Case Name” a “TERRE Load Case” y presione ADD.

\9. Cambie el “Case Name” a “COMB1 Combo” y presione ADD.

\10. Cambie el “Case Name” a “COMB2 Combo” y presione ADD. La

ventana correspondiente a la envolvente se muestra en la figura a

continuación.

\11. Presione OK dos veces para terminar el proceso.

82
Traducido por Luis E. Suárez y Drianfel Vázquez
Manual proporcionado en el seminario Internacional de CSI 2004 por:
www.construaprende.com / www.morrisoningenieros.com

<!-- p. 85 -->

Paso 7 [Definir las cargas distribuidas]: El procedimiento para asignar las
cargas uniformes fue explicado en todos los ejemplos anteriores (por ejemplo, en
el Paso 12 de Ejemplo de Vigas 1).
Siga el procedimiento a continuación para definir la carga MUERTA distribuida
uniforme:

\1. Verifique que las unidades estén en

\2. Presionando el icono de seleccione las cuatro vigas, como se explicó

anteriormente (o use cualquier otro método).

\3. Presione el icono de “Assign Frame Span Loading” .

\4. Verifique que en el recuadro de “Load Case Name” diga MUERTA

\5. Verifique que en el recuadro de “Load Type and Direction” esté

seleccionada la opción de “Forces” y que en la caja de “Direction” la

dirección sea “Gravity”.

83
Traducido por Luis E. Suárez y Drianfel Vázquez
Manual proporcionado en el seminario Internacional de CSI 2004 por:
www.construaprende.com / www.morrisoningenieros.com

<!-- p. 86 -->

\6. En el recuadro de “Options” deje la opción de “Add to existing loads”.

\7. Verifique que el recuadro de “Point Loads” los valores de las cargas

(“Load”) sean todos ceros.

\8. En el recuadro de “Uniform Load” escriba 1. La ventana para esta carga

uniforme se muestra a continuación.

\9. Presione OK.

Siga el siguiente procedimiento para definir la carga VIVA distribuida uniforme:

\1. Seleccione nuevamente las cuatro vigas usando el icono de .

\2. Presione el icono de “Assign Frame Span Loading” .

\3. Escoja VIVA del recuadro de “Load Case Name”.

84
Traducido por Luis E. Suárez y Drianfel Vázquez
Manual proporcionado en el seminario Internacional de CSI 2004 por:
www.construaprende.com / www.morrisoningenieros.com

<!-- p. 87 -->

\4. Verifique que en el recuadro de “Load Type and Direction” esté

seleccionada la opción de “Forces” y que en la caja de “Direction” la

dirección sea “Gravity”

\5. En el recuadro de “Options” deje la opción de “Add to existing loads”

\6. Deje el recuadro de “Point Loads” como se encuentra (con carga cero).

\7. En el recuadro d e “Uniform Load” escriba 0.7. La ventana para esta

carga uniforme debe verse como se muestra a continuación.

\8. Presione OK.

Pas o 8 [Definir las cargas concentradas]: El procedimi ent o para asignar las
cargas fue descrito en todos los ejemplos anteriores (por ejemplo, en el Paso 9
del Ejemplo de Vigas 1). Siga el procedimiento a continu ación para definir las
cargas nodales de TERRE:

85
Traducido por Luis E. Suárez y Drianfel Vázquez
Manual proporcionado en el seminario Internacional de CSI 2004 por:
www.construaprende.com / www.morrisoningenieros.com

<!-- p. 88 -->

\1. Seleccione la junta 2 (a la izquierda en el primer nivel) haciendo BI sobre

la misma.

\2. Presione el icono de “As sign Joint Loading”.

\3. Cambie la carga en el recuadro de “Load Case Name” a TERRE.

\4. Escriba 5 en el recuadro de “Force Global X” debajo de “Loads”.

\5. Presione OK.

\6. Repita los pasos del 1 al 5 seleccionando ahora la junta 3 (a la izquierda

de la viga superior) y usando 10 para la fuerza en la dirección “Force

Global X”. Las dos ventanas para estos casos de cargas nodales se

muestran a continuación.

86
Traducido por Luis E. Suárez y Drianfel Vázquez
Manual proporcionado en el seminario Internacional de CSI 2004 por:
www.construaprende.com / www.morrisoningenieros.com

<!-- p. 89 -->

Paso 9 [Analizar la estructura]: Recuerde grabar su modelo . Especifique
en el menú de “Analyze”, dentro de la opción de “Set Options…”, la opción de
“Fast DOFs” que corresponde al siguiente caso:

Corra el análisis presionado o del menú de “Analyze” seleccionando la
opc ión de “Run”.

Paso 10 [Resultados]: Si el programa corrió sin problemas, aparecerá el
MARCO deformado debido al primer estado de cargas que se definió en este
caso (carga MUERTA). Las deformaciones para los otros casos pueden v erse
escogiéndo cada caso con el icono (“Display Static Deformed Shape”).
Aunque en este ejemplo nos interesan las reacciones y los momentos, siempre es
recomendable examinar la estructura deformada para verificar si tiene la forma
esperada para cada tipo de carga. En las siguientes figuras se muestran las
reacciones y los diagramas de momento de la estructura para las combinaciones
COMB1, COMB2 y para la COMB3 (Envolvente). Recordar que estas figuras se

activan con los iconos .

REACCIONES (COMB1)

87
Traducido por Luis E. Suárez y Drianfel Vázquez
Manual proporcionado en el seminario Internacional de CSI 2004 por:
www.construaprende.com / www.morrisoningenieros.com

<!-- p. 90 -->

REACCIONES (COMB2)

REACCIONES (COMB3 [ENVELOPE])

88
Traducido por Luis E. Suárez y Drianfel Vázquez
Manual proporcionado en el seminario Internacional de CSI 2004 por:
www.construaprende.com / www.morrisoningenieros.com

<!-- p. 91 -->

DIAGRAMA DE MOMENTOS (COMB1)

89
Traducido por Luis E. Suárez y Drianfel Vázquez
Manual proporcionado en el seminario Internacional de CSI 2004 por:
www.construaprende.com / www.morrisoningenieros.com

<!-- p. 92 -->

DIAGRAMA DE MOMENTOS (COMB2)

DIAGRAMA DE MOMENTOS
(COMB3 [ENVELOPE])

90
Traducido por Luis E. Suárez y Drianfel Vázquez
Manual proporcionado en el seminario Internacional de CSI 2004 por:
www.construaprende.com / www.morrisoningenieros.com

<!-- p. 93 -->

Fin del Ejemplo de MARCOS #1

91
Traducido por Luis E. Suárez y Drianfel Vázquez
Manual proporcionado en el seminario Internacional de CSI 2004 por:
www.construaprende.com / www.morrisoningenieros.com

<!-- p. 94 -->

Ejemplo de MARCOS 2

Descripción del problema: Para la estructura de MARCO que se muestra, obtenga
el momento equivalente y el cortante en la base de la pared estructural. Utilice para
las vigas y columnas, secciones de 12”x 18” y para la pared un espesor de 8”. Escoja
como material el hormigón que tiene el programa por omisión.

El sistema de cargas para el MARCO es el siguiente

\1. carga estática debida a un sismo de 15 k y 25 k en las juntas, 2 y 3
respectivamente.

Paso 1 [Establecer las unidades del sistema]: Ejecute el programa SAP2000 y
cambie las unidades a .

Paso 2 [Definición de la geometría]: Del menú principal de “File” seleccione “New

Model from Template…” y seleccione la opción de “Portal Frame” . En la
ventana del “Portal Frame” escriba 2 para el “Number of Stories”, 3 en el “Number
of Bays”, 12 para la opción de “Story Height” y 24 en la opción de “”Bay Length”.

92
Traducido por Luis E. Suárez y Drianfel Vázquez
Manual proporcionado en el seminario Internacional de CSI 2004 por:
www.construaprende.com / www.morrisoningenieros.com

<!-- p. 95 -->

Presione OK. Cierre la ventana de 3-D. Esto le genera el marco que se muestra en
la siguiente figura.

Paso 3 [Definir y asignar las secciones de los elementos]: Seleccione todas las

columnas y vigas del MARCO utilizando la herramienta de (“Select All”) del
“toolbar” ubicado en la parte izquierda de la pantalla principal de SAP2000. Esta
opción también puede obtenerse mediante los siguientes pasos:

Menú de “Select”→ “Select” → “All”

Siga los pasos a continuación para definir y asignar las secciones a las columnas.
Primero cambie las unidades a .

Presione el icono de o del menú de “Assign” → Frame → Sections… →
Modify/Show Section.

Cambie el material a CONC, los tamaños a 12 (“width”) y 18 (“depth”) y el nombre
a VIGASCOL. Retorne a la pantalla principal con OK → OK.

93
Traducido por Luis E. Suárez y Drianfel Vázquez
Manual proporcionado en el seminario Internacional de CSI 2004 por:
www.construaprende.com / www.morrisoningenieros.com

<!-- p. 96 -->

Recuerde grabar el archivo actualizado de su modelo (p. ej. Portico2).

Paso 4 [Definir la sección de los elementos de paredes de carga (“Shells”)]:
Usualmente las paredes estructurales se modelan con un tipo de elemento diferente a
los elementos de marcos o MARCOS (“Frame Elements”). Esto se debe a que el
comportamiento de las paredes es distinto al de, por ejemplo, una columna típica.
Además, algunas de las suposiciones usadas para el desarrollo de la matriz de rigidez
para un elemento de marco no aplican para un elemento de pared. Una de estas
simplificaciones es que en la derivación de un elemento de marco se desprecian las
deformaciones por cortante. Si bien en vigas y columnas esta deformación es
prácticamente despreciable, no ocurre lo mismo en las paredes: allí las deformaciones
por cortante son significativas. Para esto se utilizan ciertos elementos que se
denominan elementos de cáscaras o “Shell Elements” y que pertenecen a lo que se
conoce como “elementos finitos”. Estos elementos se utilizan para modelar no sólo
paredes estructurales sino también los de pisos y cáscaras. Por lo tanto, para modelar
las paredes del edificio se usarán estos nuevos elementos.

Del menú de “Define” seleccione “Shell Sections…” y presione “Modify/Show
Section”. Esto lo conducirá a la siguiente ventana.

94
Traducido por Luis E. Suárez y Drianfel Vázquez
Manual proporcionado en el seminario Internacional de CSI 2004 por:
www.construaprende.com / www.morrisoningenieros.com

<!-- p. 97 -->

Cambie el “Section Name” (nombre de la sección) a PARED y ambos espesores de
“Membrane” y de “Bending” en el recuadro de “Thickness” a 6. Por último,
verifique que las opciones de “Shell” y “Thick Plate” estén seleccionadas como se
muestra en la figura anterior. Presione OK dos veces.

Nota

Los elementos de cáscaras que utilizan la opción de “Thick Plate” incluyen la
deformación transversal por cortante utilizando la teoría de Mindlin/Reissner y sólo
afecta el efecto de placa y no el efecto membranal. Si no se escoge la opción de
“Thick Plate”, implicaría que se va a usar la teoría de placas delgadas o finas (“Thin
Plates”) para la cual SAP2000 utiliza la teoría de Kirchhoff. En el caso de paredes
este efecto no es muy importante puesto que las cargas en las paredes van paralelas al
plano. Como la pared no va a estar sometida a cargas transversales, esto implica que

95
Traducido por Luis E. Suárez y Drianfel Vázquez
Manual proporcionado en el seminario Internacional de CSI 2004 por:
www.construaprende.com / www.morrisoningenieros.com

<!-- p. 98 -->

las deformaciones generadas no son en la dirección transversal. De todas maneras,
SAP2000 recomienda que siempre se use el elemento de “Shell” con la opción de
“Thick Plate” para el análisis de losas o paredes, sean éstas delgadas o gruesas.

Paso 5 [Generar las paredes de carga con los elementos de cáscaras (“Shells”]:

Presione el icono de (“Quick Draw Rectangular Shell Element”) o del menú de
“Draw” seleccione “Quick Draw Shell Elements”.

Nota

Hay tres diferentes formas de generar los elementos de cáscaras. Éstas son las
siguientes:

“Quick Draw Rectangular Shell Element” → Con esta opción se pueden
generar los elementos de cáscaras con sólo presionar un BI en el centro del
rectángulo donde se desea ubicar el elemento.

“Draw Rectangular Shell Element” → Con esta opción se especifican los
puntos diagonalmente opuestos que generarían un rectángulo, es decir la
esquina inferior izquierda y la esquina superior derecha.

“Draw Quadrilateral Shell Element” → Con esta opción se genera un elemento
de cáscara especificando las cuatro esquinas o bordes que componen el
cuadrilátero. A diferencia de las opciones anteriores, el elemento desarrollado
con esta opción NO necesariamente tiene que ser rectangular como con las
dos opciones anteriores. Además con esta opción se pueden generar
elementos de tres lados ubicando los últimos dos nodos en el mismo punto.

Nota: Estas opciones también se encuentran en el menú de “Draw”.

96
Traducido por Luis E. Suárez y Drianfel Vázquez
Manual proporcionado en el seminario Internacional de CSI 2004 por:
www.construaprende.com / www.morrisoningenieros.com

<!-- p. 99 -->

Como mencionamos anteriormente, en este caso en particular vamos a utilizar la

opción de (“Quick Draw Rectangular Shell Elements”) para crear los elementos
de cáscaras del modelo.

Presione y luego presione el BI en cualquier lugar dentro del rectángulo que
formaría la pared del primer piso. A continuación presione otro BI en el interior del
rectángulo que formaría la pared del segundo piso.

Nota

Note que al completar el paso anterior, el cursor (“Pointer”) de SAP2000 cambia

de a indicando así que la opción de “Quick Draw Rectangular Shell
Element” está activada. Recordar que este cursor también se activaba al utilizar la
opción de “Draw Frame Element”, como se mostró en el Ejemplo de Armaduras
\1.

El modelo generará unos rectángulos (en color rojo) que corresponden a los
elementos de cáscaras, como se muestra en la figura a continuación.

97
Traducido por Luis E. Suárez y Drianfel Vázquez
Manual proporcionado en el seminario Internacional de CSI 2004 por:
www.construaprende.com / www.morrisoningenieros.com

<!-- p. 100 -->

Paso 6 [Eliminación de elementos solapados]: Es importante hacer notar
que al definir los elementos de cáscaras, los bordes de éstos se sobrepusieron
sobre las columnas y vigas que lo rodean. Por lo tanto es necesario que se
eliminen o se borren estos elementos para así tener un modelo más cercano a la
realidad.

Nota

Hay MARCOS de edificios, en especial de más de 4 pisos, en los cuales las paredes
estructurales tienen lo que se conoce como “elementos de borde o de contorno”, que
básicamente consisten en unas columnas en los extremos. Si éste es el caso, se puede
dejar las columnas junto con la pared, pero aún así se tienen que eliminar las vigas.

Note que estos elementos de vigas y columnas, aunque están en el modelo, no se
pueden ver. Una forma de ver estos elementos es ocultando los elementos de
cáscaras. Esto es necesario porque para borrar los elementos hay que
seleccionarlos y para ello es imprescindible verlos. Para hacer que el programa
muestre estos elementos, seleccione el icono de (“Set Elements”) o del menú
de “View” seleccione “Set Elements”. Esto lo conducirá a la siguiente ventana:

Como se muestra en la ventana, seleccione la opción de “Hide” (ocultar) dentro
del recuadro de “Shells” para así poder esconder los elementos de cáscara.
Presione OK. Ahora el programa muestra todas las vigas y columnas del
MARCO. Los elementos de paredes están donde se habían creado; simplemente
ahora están ocultos.

Nota

98
Traducido por Luis E. Suárez y Drianfel Vázquez
Manual proporcionado en el seminario Internacional de CSI 2004 por:
www.construaprende.com / www.morrisoningenieros.com

<!-- p. 101 -->

Esta ventana de “Set Elements” le permite al usuario mostrar o esconder varias
opciones asociadas a los elementos. Entre ellas se encuentran opciones tales como
la identificación de los números de elementos (“Element ID”), tipos de elementos
(“Element Types”), secciones (“Sections”) y otras. Se invita al usuario a que
prenda y apague estas opciones para que vea el efecto del mismo en la pantalla.
Una de las más usadas es la de “Show Extrusions”, mediante la cual el programa
muestra el modelo con literalmente la forma y tamaño de la sección definida.

Seleccione las vigas y las columnas que rodean a la pared haciendo BI sobre cada
una de ellas y presione la tecla “Delete” para borrarlas. Presione nuevamente el
icono y quite la opción de “Hide” en el recuadro de “Shells” para volver a
ver los elementos de cáscaras. Presione OK.

Paso 7 [Asignar la sección del elemento de cáscara a las paredes]: Al igual
que en los otros ejemplos se asignaban las secciones a los elementos de marcos o
vigas, a las paredes definidas en el paso anterio r también hay que asignarles la
sección de cáscara que se desea. El procedimiento es el mismo que se utiliza
para los elementos de marcos y se explica a continuación.

Primero seleccione las paredes haciendo BI sobre cada una de ellas. Note que
aparecen rectángulos con líneas entrecortadas interiores a los elementos. Luego

presione el icono de (“Assign Shell Sections…”) o del menú de “Assign”,
seleccione “Shell” y “Section…”. De la pantalla de “Define Shell Sections” que
se presenta, seleccione la sección de PARED y presione OK.

Paso 8 [Refinar las paredes o elementos de cáscaras]: Como se desea
obtener información precisa acerca de las fuerzas internas en las paredes, es
necesario que éstas se subdividan en muchos elementos de paredes pequeños
que, en conjunto, forman la pared total. De esta manera podemos conocer en
cada elemento los momentos y fuerzas internas como así también los esfuerzos y
deformaciones. A este proceso de subdivisión se le llama refinamiento de los
elementos o también como generar lo que se conoce como una malla o “Mesh”.
En este caso en particular vamos a dividir las paredes en seis (6) elementos en la
dirección horizontal y cuatro (4) en la dirección vertical como se muestra en la
figura inicial de este ejemplo. Para subdividir las paredes o generar la malla se
deben seguir los siguientes pasos:

99
Traducido por Luis E. Suárez y Drianfel Vázquez
Manual proporcionado en el seminario Internacional de CSI 2004 por:
www.construaprende.com / www.morrisoningenieros.com

<!-- p. 102 -->

\1. Seleccione los elementos de paredes haciendo BI dentro de cada

elemento

\2. De “Edit” en el menú principal, seleccione “Mesh Shells…” Esto lo

conducirá a la pantalla de “Mesh Selected Shells”que se muestra a

continuación.

\3. En la caja de “Mesh into” escriba 6 y en la caja de “by” escriba 4.

Presione OK.

El modelo hasta esta etapa se muestra a continuación. Recuerde grabar su
modelo.

100
Traducido por Luis E. Suárez y Drianfel Vázquez
Manual proporcionado en el seminario Internacional de CSI 2004 por:
www.construaprende.com / www.morrisoningenieros.com

<!-- p. 103 -->

Paso 9 [Asignar condiciones de borde]: Note que los elementos “nuevos” en
la franja inferior no tienen los apoyos por lo que es necesario asignarles la
condición de borde requerida. Para asignar las condiciones de borde, seleccione
los nodos “nuevos” (los cinco nodos libres inferiores) y presione el icono de

“Assign Joint Restraints”. Seleccione el icono de del recuadro de “Fast
Restraints”. Presione OK. El procedimiento para definir las condiciones de
borde fue presentado en detalle en el Paso 4 del Ejemplo de Vigas 1.

Cambie también las condiciones de las columnas exteriores de articulado a

fijo . El modelo hasta esta etapa se muestra a continuación:

101
Traducido por Luis E. Suárez y Drianfel Vázquez
Manual proporcionado en el seminario Internacional de CSI 2004 por:
www.construaprende.com / www.morrisoningenieros.com

<!-- p. 104 -->

Paso 10 [Definir las cargas concentradas]: El procedimiento para asignar las
cargas nodales fue explicado en todos los ejemplos anteriores (por ejemplo, en el
Paso 9 del Ejemplo de Vigas 1). Para simplificar el proceso, en este caso vamos
a utilizar el sistema de carga que tiene el programa por omisión (LOAD1). En la
práctica, se deben definir los sistemas de carga y combinaciones de carga como
en los ejemplos anteriores.

\1. Seleccione la junta 2 (primer nivel) haciendo BI sobre la misma.

\2. Presione el icono de “Assign Joint Loading” .

\3. V erifique que en el recuadro de “Load Case Name” diga L OAD1

\4. En el recuadro de “Loads”, escriba 15 en el cuadro de “Force Global X”.

\5. Presione OK.

\6. Repita los pasos del 1 al 5 ahora seleccionando la junta 3 y escribiendo

25 en el cuadro “Force Global X”.

102
Traducido por Luis E. Suárez y Drianfel Vázquez
Manual proporcionado en el seminario Internacional de CSI 2004 por:
www.construaprende.com / www.morrisoningenieros.com

<!-- p. 105 -->

Nota

Además de las fuerzas de 15 y 25 kips, por omisión el programa le va a sumar a
este estado de carga (“LOAD1”) el peso propio de todos los elementos (vigas,
columnas y paredes).

Paso 11 [Analizar la estructura]: Recuerde grabar su modelo .
Especifique en el menú de “Analyze”, dentro de la opción “Set Options”, la
siguiente opción de “Fast DOFs” de “Plane Frame”:

Efectúe el a nálisis presionando , o del menú de “Analyze” escoja la opción
“Run”. Presione OK. El programa debería mostrar la estructura deformada si el
análisis terminó sin inconvenientes. Obser ve que las vigas tienen una
deformación debida a su propio peso, debido a que, como se explico, por
omisión, SAP2000 considera el peso propio en el estado de carga (LOAD1 en
este caso).

Paso 12 [Resultados de Momentos y Cortante en la Base de la Pared]:

Seleccione el icono de para ver las reacciones de la estructura. Note que
las reacciones sólo tienen los componentes verticales y horizontales y no tienen
los momentos en las bases de las columnas exteriores. Para observar estos

momentos puede observar el marco en una vista tridimensional . Los
momentos alrededor del eje Y aparecen como vectores en una doble flecha.
Para poder ver los valores de los momentos debe agrandar la imagen con un
“Zoom”. Para hacer el acercamiento presione el icono de (“Rubber Band
Zoom”) y haga un recuadro que cubra todas las reacciones de la pared
manteniendo el BI presionado mientr as hace el recuadro.

Haga otro acercamiento (“Zoom”) a las reacciones de la pared para ver mejor los
resu ltados como se muestra en la figura a continuación.

103
Traducido por Luis E. Suárez y Drianfel Vázquez
Manual proporcionado en el seminario Internacional de CSI 2004 por:
www.construaprende.com / www.morrisoningenieros.com

<!-- p. 106 -->

Nota

Como se usaron elementos de cáscaras para representar la pared, es posible
calcular los esfuerzos normales y cortantes promedio en cada uno de los elementos
y aún en cada punto de un elemento individual. No obstante, para verificar ciertas
condiciones en los códigos puede ser necesario calcular un “momento” flector en
la base de la pared (alrededor del eje Y perpendicular al plano de la figura). Debe
tenerse presente que, rigurosamente, sólo tendría sentido hablar de momento en
un apoyo fijo o empotrado de un elemento de MARCO (como en la base de las
columnas del edificio). Sin embargo, bajo condiciones de carga apropiadas, una
placa como nuestra pared puede tener momentos alrededor de los ejes X y Z. En
este ejemplo, debido a que la pared no tiene deflexión fuera de su plano, estos
momentos son cero. Esto es fácil de verificar comenzando en el menú principal y
siguiendo la secuencia: Display -> Show Element Forces/Stresses -> Shells... En la
ventana que se abre, si se escogen los momentos debido a la flexión M11 o M22, o
el momento M12 debido a la torsión de la placa (“twist”), el programa va a mostrar
que todos ellos son cero.

Para obtener el momento equivalente en la base, sólo tiene que sumar los
momentos de las reacciones verticales respecto a cualquier punto de la pared.
Recuerde que el largo o claro de esta pared es 24 pies, y como fue dividida en 6
s ub-elementos, cada elemento tiene un ancho de 4 pies. Tomando momento
respecto al centro tenemos que:

M = 16 . 64 × 4 + 26 .64 × 8 + 21 .77 × 12 − .190 × 4 + .9 70 × 8 + 12 .66 × 12 = 762 .84 k ⋅ ft ∑
Centro

Para calcular el cortante en la base de la pared sumamos las fuerzas en la
dirección horizontal en los apoyos articulados. Tenemos así:

F = .3 28 + .5 49 + .5 84 + .6 66 + .6 77 + .6 00 + .5 45 = 39 . 49 kip ∑
Horizontal

REACCIONES EN PARED (LOAD1)

104
Traducido por Luis E. Suárez y Drianfel Vázquez
Manual proporcionado en el seminario Internacional de CSI 2004 por:
www.construaprende.com / www.morrisoningenieros.com

<!-- p. 107 -->

Fin del Ejemplo de MARCOS #2

105
Traducido por Luis E. Suárez y Drianfel Vázquez
Manual proporcionado en el seminario Internacional de CSI 2004 por:
www.construaprende.com / www.morrisoningenieros.com

<!-- p. 108 -->

Capítulo
4
Ejemplo de Análisis
Dinámico 1

Descripción del problema: Obtenga los primeros cuatro periodos naturales con sus
correspondientes modos de vibración para el MARCO que se muestra en la figura de
la izquierda. Luego subdivida el MARCO como se muestra en la figura de la derecha
y calcule sus primeros doce periodos naturales y modos de vibración. Para definir la
masa de la estructura para estos casos considere únicamente el peso propio de los
elementos. Utilice el material de hormigón (CONC) que tiene el programa por
omisión y una sección transversal cuadrada de 0.4m X 0.4 metros.

Nota:

Para el análisis dinámico SAP2000 usa lo que se conoce como un modelo de masas
concentradas (“lumped mass model”). En este modelo se ignora la inercia asociada a la
rotación de una junta o nodo de estructuras de barras. Esto hace que el número de

106
Traducido por Luis E. Suárez y Drianfel Vázquez
Manual proporcionado en el seminario Internacional de CSI 2004 por:
www.construaprende.com / www.morrisoningenieros.com

<!-- p. 109 -->

grados de libertad estático (el que usamos hasta ahora) no coincida con el número de
grados de libertad dinámico (el que vamos a usar a continuación). Por ejemplo, en el
caso del MARCO plano de la izquierda en la figura anterior, el número de grados de
libertad estático es 8 (4 traslaciones más 4 rotaciones). Para el mismo MARCO, el
número de grados de libertad dinámico es sólo 4 (las traslaciones de las dos masas
superiores). El máximo número de periodos y modos de vibración que se puede
calcular para un modelo dado coincide con los grados de libertad dinámicos.

Paso 1 [Establecer unidades del sistema]: Inicie el programa SAP2000 y cambie
las unidades a .

Paso 2 [Definición de geometría]: Del menú principal de “File” seleccione “New

Model from Template…” y seleccione la opción de “Portal Frame” . En la
ventana del “Portal Frame” escriba 1 para el “Number of Stories”, 1 en el “Number
of Bays”, 3 para la opción de “Story Height” y 6 en la opción de “Bay Width”.
Presione OK. Cierre la ventana de 3-D. Esto le genera el marco que se muestra en
la siguiente figura.

107
Traducido por Luis E. Suárez y Drianfel Vázquez
Manual proporcionado en el seminario Internacional de CSI 2004 por:
www.construaprende.com / www.morrisoningenieros.com

<!-- p. 110 -->

Paso 3 [Definir el caso de Análisis]: Abra el menú de “Define” y la opcion de
“Analisis Cases…”. Note que el seleccionar esta opcion se activa una ventana
“Analisis Cases” y seleccione el boton “modify Show/Case..” se activará una ventana
“Anlisis Case Data-Modal” escriba en la caja de texto de analisis Case name
MODAL1, en Analisis Case Type seleccione la opcion “Modal” luego para definir el
numero de odods en el recuadro Maximun Number of Modes escriba 4 (o de
periodo o frecuencias naturales) y dejar los demas parámetros como los tiene el
programa en el Type of Modes seleccionar “Eigen Vectors” Presione OK dos veces.

Paso 4 [Definir y asignar las secciones de los elementos]: Seleccione todas las

columnas y vigas del MARCO utilizando la herramienta de (“Select All”) del
“toolbar” ubicado en la parte izquierda de la pantalla principal de SAP2000. Esto
también puede hacerse con Ctrl+A o con la secuencia: menú “Select” → Select →
All.

Presione el icono de (o use el menú de “Assign” → Frame→ Sections…).
Presione Modify/Show Section.

Deje el nombre de FSEC1 (Frame Section 1) que tiene SAP2000 por omisión,
cambie el material a CONC y las dimensiones a 0.4 para la profundidad o altura y
para el ancho. Presione OK dos veces.

Recuerde grabar el archivo actualizado de su modelo (por ejemplo Frec 1a).

Paso 5 [Analizar la estructura y obtener las frecuencias naturales]: Abra el
menú de “Analyze” y la opción de “Set Options…”. Escoja la siguiente opción
de “Fast DOFs”:

Abajo en la misma pantalla seleccione la opción de “Dynamic Analysis”. Note
que al seleccionar esta opción se activa el botón que está a la derecha y que tiene
como descripción “Set Dynamic Parameters”. Presione este botón, lo que lo
conducirá a la pantalla que se muestra a continuación. Escriba 4 en el número
de modos (o de periodos o frecuencias naturales) y deje los demás parámetros
como los tiene el programa por omisión. Presione OK dos veces para llegar a la
pantalla principal.

108
Traducido por Luis E. Suárez y Drianfel Vázquez
Manual proporcionado en el seminario Internacional de CSI 2004 por:
www.construaprende.com / www.morrisoningenieros.com

<!-- p. 111 -->

Nota:

Recuerde que cuando se especificaba la opción de (“Plane Frame” o “XZ
Plane”) los únicos grados de libertad utilizados eran el desplazamiento horizontal
UX, el desplazamiento vertical UZ y la rotación RY de cada junta. Esto implica que
para un análisis estático, como la estructura tiene 4 nodos y hay tres grados de
libertad por nodo habría 12 grados de libertad en total y 6 al aplicar las condiciones
de apoyo. Sin embargo, como se mencionó antes, al analizar marcos dinámicamente,
SAP2000 sólo computa las frecuencias naturales y modos de vibración teniendo en
cuenta los grados de libertad translacionales (UX y UZ). Por lo tanto los grados de
libertad disponibles son 12 menos 4 grados de libertad rotacionales menos 4
restringidos por los soportes para un total de sólo 4 grados de libertad. Por ende,
éste es máximo número de modos (“Number of Modes”) o periodos naturales que
se le puede pedir a SAP2000 para este modelo.

109
Traducido por Luis E. Suárez y Drianfel Vázquez
Manual proporcionado en el seminario Internacional de CSI 2004 por:
www.construaprende.com / www.morrisoningenieros.com

<!-- p. 112 -->

Corra el análisis presionado o mediante la opción de “Run” en el menú de
“Analyze”.
Paso 6 [Resultados y Animación]: Si el programa completó el análisis sin
inconvenientes, debe mostrar el mensaje “ANALYSIS COMPLETE” en la
pantalla con fondo oscuro. Al presionar el botón de OK, el programa muestra el
primer modo de vibración (o sea el que corresponde al periodo más alto). Para
apreciar mejor el modo se sugiere que abra la ventana “Mode Shape” con el
icono (“Display Mode Shape”). En el recuadro de “Options”, escoja “Wire
Shadow” y “Cubic Curve”. La primera opción va a mostrar la estructura sin
deformar con líneas más finas. La segunda va a utilizar una curva suave (un
polinomio cúbico) para representar las barras deformadas. El modo de vibración
que se está mostrando y el periodo natural correspondiente se identifican en el
extremo superior izquierdo de la pantalla. Observe los cuatro modos de
vibración pasando de uno a otro con los iconos , o escogiendo el modo
deseado con el icono .

Es posible ver los cuatro modos en una misma pantalla usando la opción
“Windows” dentro del menú de “Options”. Escogiendo “Four”del submenú de
“ Windows”, la pantalla de visualización se divide en cuatro. Notar que una sola
de ellas contiene el modo. Para que aparezcan los otros modos, debe activar
primero la subpantalla que desee mediante un BI en cualquier lugar de la misma.
Luego abra el icono y escoja el modo que quiere que se muestre. Si no lo
hizo antes, recuerde que conviene activar las opciones “Wire Shadow” y “Cubic
Curve” para mejor visualización de los modos. A continuación se muestra la
pantalla con los cuatro modos de vibración a la vez.

110
Traducido por Luis E. Suárez y Drianfel Vázquez
Manual proporcionado en el seminario Internacional de CSI 2004 por:
www.construaprende.com / www.morrisoningenieros.com

<!-- p. 113 -->

Para volver a una sola pantalla, cierre las restantes pantallas o repita el
procedimiento anterior (Windows → Options, etc.) pero seleccionando “One”
en vez de “Four”.

Es posible ver los valores numéricos de los desplazamientos modales del modo
de vibración que se muestra en la pantalla. Para esto debe seleccionar la junta
con un BI, y luego con un BD se activa una pequeña ventana donde aparecen los
valores de los desplazamientos y las rotaciones. Para observar los valores del
modo para otra junta debe cerrar la ventana y repetir el proceso.

Note que al terminar el análisis, se encendieron unos botones al lado de la caja
de las unidades en la parte inferior derecha como se muestra en la siguiente
figura:

El botón de “Start Animation” (iniciar la animación) activa una animación
gráfica del modo de vibración que se muestra en la parte superior de la pantalla.
Para adelantar al siguiente modo de vibración o volver hacia atrás, presione los
iconos de y , respectivamente. Note que al presionar “Start Animation”
y se inicia la animación, el botón cambia a “Stop Animation”, el que se debe usar
para detener la animación.

111
Traducido por Luis E. Suárez y Drianfel Vázquez
Manual proporcionado en el seminario Internacional de CSI 2004 por:
www.construaprende.com / www.morrisoningenieros.com

<!-- p. 114 -->

Para ver un listado detallado de los resultados generados por SAP2000 siga los
siguientes pasos:

Menú “File” → “Display Input/Output Text Files”→ Seleccione el archivo
llamado Frec 1a.out (o use el nombre con el cual guardó el presente modelo).
Este proceso se explicó en el Ejemplo de Vigas 1.

Busque en este archivo la parte donde dice “M O D A L P E R I O D
S A N D F R E Q U E N C I E S”. Allí aparecen los
resultados que se muestran en la siguiente tabla.

MODE PERIOD FREQUENCY FREQUENCY EIGENVALUE
(TIME) (CYC/TIME) (RAD/TIME) (RAD/TIME)**2

1 0.164758 6.069506 38.135833 1454.342
2 0.007709 129.717474 815.038928 664288.453
3 0.007705 129.78929 815.490158 665024.197
4 0.007701 129.860017 815.934551 665749.191

Paso 7 [Dividir los elementos]: Grabe el archivo con otro nombre para no

perder el archivo anterior. (por ejemplo Frec 1b). Presione el icono de
(“Lock/Unlock Model”) para poder editar el nuevo modelo. Presione OK para
reconocer el mensaje que aparece previniéndole que los resultados del análisis
anterior se van a borrar.

Seleccione las columnas haciendo BI sobre cada una o utilice la herramienta de
(“Set Intercepting Line Select Mode”) explicada en el Ejemplo de MARCOS 1. Del
menú de "Edit" seleccione “Divide Frames” y en la pantalla que aparece de “Divide
Selected Frames” verifique que diga 2 en la caja de “Divide into” y 1 en la caja de
“Last/First Ratio”. Presione OK.

Seleccione ahora la viga y repita el procedimiento anterior pero escriba 3 en la caja de
“Divide into”. Presione OK. Note que con esto el segundo modelo está
completamente definido, dado que las propiedades (materiales, etc.) son las mismas
que las del primer MARCO.

Nota:

112
Traducido por Luis E. Suárez y Drianfel Vázquez
Manual proporcionado en el seminario Internacional de CSI 2004 por:
www.construaprende.com / www.morrisoningenieros.com

<!-- p. 115 -->

La opción de “Last/First Ratio” permite subdividir un elemento en segmentos
desiguales, en donde el último segmento es “X” veces el primero, siendo “X” el
número que entramos como dato.

Paso 8 [Analizar la estructura y obtener las frecuencias naturales]:
Especifique en el menú de “Analyze”, dentro de la opción de “Set Options” la
opción de “Fast DOFs” de

Seleccione la opción de “Set Dynamic Parameters”. Escriba 12 para el número
de modos o frecuencias naturales y deje los demás parámetros como los tiene el
programa por omisión. Presione OK

Nota:

Note que el máximo número de frecuencias naturales para la estructura modificada es
ahora 12. El total de grados de libertad estáticos es (8 juntas) x (3 grados de libertad)
\= 24. Si se resta 8 (los grados de libertad rotacionales en cada junta) y 4 (los grados
de libertad restringidos por los soportes) se obtienen los 12 grados de libertad
dinámicos.

Efectúe el análisis presionado o del menú de “Analyze” use la opción de
“Run”. Presione OK.

Paso 9 [Resultados]: Puede observar todos los modos de vibración con las
flechas y . También puede obtener un listado de los periodos y
frecuencias naturales del nuevo MARCO abriendo el archivo Frec1b.out (o el
nombre que le asignó al archivo) mediante la opción “Display Input/Output
Text Files...” del menú de “File”. En la siguiente tabla se muestran los resultados.

113
Traducido por Luis E. Suárez y Drianfel Vázquez
Manual proporcionado en el seminario Internacional de CSI 2004 por:
www.construaprende.com / www.morrisoningenieros.com

<!-- p. 116 -->

MODE PERIOD FREQUENCY FREQUENCY EIGENVALUE
(TIME) (CYC/TIME) (RAD/TIME) (RAD/TIME)**2

1 0.16091 6.214657 39.04784 1524.734
2 0.043709 22.878805 143.751769 20664.571
3 0.017223 58.060844 364.807043 133084.178
4 0.014151 70.664505 443.998177 197134.382
5 0.012104 82.620005 519.116803 269482.255
6 0.005351 186.875248 1174.172 1.38E+06
7 0.005318 188.052828 1181.571 1.40E+06
8 0.005064 197.485843 1240.84 1.54E+06
9 0.002855 350.28939 2200.933 4.84E+06
10 0.002245 445.381452 2798.414 7.83E+06
11 0.001983 504.245765 3168.27 1.00E+07
12 0.001983 504.316378 3168.713 1.00E+07

A continuación se muestran los doce primeros modos del nuevo modelo
agrupados de a cuatro. Notar que sólo el primero se parece al modo
correspondiente del modelo con 4 grados de libertad anterior. Como se sabe de
la teoría de Dinámica de Estructuras, generalmente este primer modo es el que
más contribuye a la respuesta (en especial para estructuras con cargas sísmicas).
Esto significa que si se calcula la respuesta sísmica con el modelo de 4 y de 12
grados de libertad los resultados deben ser similares. No obstante, para otro tipo
de carga dinámica, por ejemplo para una fuerza vertical armónica aplicada a la
viga, los resultados pueden ser muy distintos. La conclusión a la que se llega es
que el modelo de 4 grados de libertad dinámico no es el más conveniente para
representar el comportamiento dinámico de este MARCO ante cualquier
excitación. Puede surgir la pregunta: ¿y no ocurrirá lo mismo con el modelo de
12 grados de libertad? ¿Si volvemos a dividir en dos cada tramo del segundo
MARCO (o sea si usamos 26 grados de libertad), es posible que los resultados
del nuevo modelo no se asemejen al anterior? Aunque la duda es válida, no
debemos preocuparnos: una vez que se usa un número suficiente de grados de
libertad, los resultados comienzan a converger rápidamente. Se sugiere al lector
que compruebe esto subdividiendo las columnas y la viga por dos y comparando
los resultados. Por supuesto, en un modelo más detallado siempre aparecerán
nuevos modos que no están en uno más simple. Sin embargo, estos modos altos
prácticamente casi no contribuyen a la respuesta.

114
Traducido por Luis E. Suárez y Drianfel Vázquez
Manual proporcionado en el seminario Internacional de CSI 2004 por:
www.construaprende.com / www.morrisoningenieros.com

<!-- p. 117 -->

MODOS 1 AL 4

MODOS 5 AL 8

115
Traducido por Luis E. Suárez y Drianfel Vázquez
Manual proporcionado en el seminario Internacional de CSI 2004 por:
www.construaprende.com / www.morrisoningenieros.com

<!-- p. 118 -->

MODOS 9 AL 12

116
Traducido por Luis E. Suárez y Drianfel Vázquez
Manual proporcionado en el seminario Internacional de CSI 2004 por:
www.construaprende.com / www.morrisoningenieros.com

<!-- p. 119 -->

Nota:

En algunas ocasiones se puede necesitar un listado de los desplazamientos modales,
por ejemplo para ser procesados con otro programa. Por omisión, SAP2000 no los
entrega porque para una estructura complicada de un caso real, la cantidad de
información sería abrumadora. No obstante, es posible agregar los modos al archivo
de texto que se mencionó en el Paso 8 (Frec1b.out). Para esto, cuando en el Paso 4 o
7 abre el menú de “Analyze” seguido por “Set Options...”, debe marcar el casillero
“Generate Output”. Esto activará el botón “Select Output Options”. Apriete este
botón para abrir la ventana “Select Output Results”. Allí debe escoger
“Displacements”, lo que automáticamente activará el botón de “Select/Show Loads”
en el lado derecho. Apriete este botón para abrir la ventana “Select Output”. Allí
debería haber dos casos: “LOAD1 load case” y “MODES”. Selección este último
caso y apriete OK tres veces para cerrar todas las ventanas. Una vez que corra el
programa, cuando abra el archivo de resultados (el que tiene la extensión .out), éste va
a contener un listado como el que se muestra parcialmente a continuación..

J O I N T D I S P L A C E M E N T S

TRANSLATIONS AND ROTAT IONS, IN GLOBAL COORDINATES

MODE 1 ------------------

JOINT UX UY UZ RX RY RZ
1 .000000 .000000 .000000 .000000 0.222305 .000000
2 0.537837 .000000 0.001180 .000000 0.089836 .000000
3 .000000 .000000 .000000 .000000 0.222305 .000000
4 0.537837 .000000 -0.001180 .000000 0.089836 .000000

Note que el programa presenta para cada junta (y para cada modo), los tres
desplazamientos (UX, UY y UZ) y las tres rotaciones (RX, RY y RZ) alrededor
de los tres ejes coordenados. Por supuesto, como en este ejemplo la estructura es
plana, sólo los grados de libertad UX, UZ y RY tienen valores distintos de cero.

Fin del Ejemplo de Análisis Dinámico #1

117
Traducido por Luis E. Suárez y Drianfel Vázquez
Manual proporcionado en el seminario Internacional de CSI 2004 por:
www.construaprende.com / www.morrisoningenieros.com

<!-- p. 120 -->

Ejemplo de Análisis Dinámico 2

Descripción del problema: Obtenga la respuesta del MARCO creado en el Ejemplo
de Análisis Dinámico 1 debido a un terremoto determinado. Use un análisis
dinámico en el tiempo transitorio (“Time History Analysis”) y el registro del
terremoto de El Centro. Añada una masa de 250 Kg a cada una de las cuatro masas
ubicadas en la viga. Grafique el historial de desplazamientos horizontales de la junta
superior izquierda del modelo, el cortante total en la base y el cortante en la columna
izquierda.

Paso 1 [Abrir el archivo]: Inicie el programa SAP2000 y abra el archivo Freq1b.sdb
generado en el caso anterior de Ejemplo de Análisis Dinámico 1. Grabe el modelo
con otro nombre para no perder el ejemplo anterior (por ejemplo, THistory).
Cambie las unidades a

Paso 2 [Añadir Masas Concentradas]: Note que en el ejemplo de Análisis
Dinámico 1 sólo se utilizó el peso propio de los elementos para definir la masa. En la
mayoría de los casos reales, la masa que contribuye a los efectos dinámicos, además
del peso propio de los elementos, incluye el peso muerto de los componentes de la
estructura y parte de la carga viva que se encuentra en la estructura. En este ejemplo
vamos a añadir unas masas de 250 Kg en cada una de las juntas de la viga superior.
Éstas representan el peso muerto de la parte de la estructura asignada al MARCO.
Para agregar las masas siga el procedimiento indicado a continuación:

\1. Seleccione las cuatro juntas o nodos ubicados en la viga.

\2. Use la secuencia: “Assign” (en menú principal) → “Joints” → “Masses…”.
En la ventana de “Joint Masses” que se abre escriba 250 en el casillero
“Direction 1” y en la “Direction 3”, como se muestra a continuación.
Asegúrese que la opción “Add to existing masses” esté seleccionada
118
Traducido por Luis E. Suárez y Drianfel Vázquez
Manual proporcionado en el seminario Internacional de CSI 2004 por:
www.construaprende.com / www.morrisoningenieros.com

<!-- p. 121 -->

\3. Presione OK para regresar a la pantalla principal.

Nota:

Si el programa no muestra las masas agregadas a la estructura, use el icono (‘Set
Elements”) que aparece en la fila superior de iconos. En la ventana que se abre, en la
columna de “Joints”, active la opción “Masses”. Al presionar OK van a aparecer las
masas en las juntas representadas por flechas con sus valores numéricos.

Nota:

Como se puede observar en la ventana de “Joint Masses”, el programa permite
agregar masas en las direcciones de los tres ejes coordenados. Aunque en la ventana
estos ejes se identifican como 1, 2 y 3, en realidad éstos corresponden,
respectivamente, a los ejes X, Y, y Z globales. Las masas en las juntas se consideran
como partículas (o sea elementos con dimensiones despreciables) concentradas en un

119
Traducido por Luis E. Suárez y Drianfel Vázquez
Manual proporcionado en el seminario Internacional de CSI 2004 por:
www.construaprende.com / www.morrisoningenieros.com

<!-- p. 122 -->

punto. Evidentemente, una masa concentrada puede tener tres traslaciones, en las
direcciones de los ejes coordenados. Como la estructura de este ejemplo se considera
como plana, los desplazamientos en la dirección Y global (eje 2, normal a la pantalla)
están restringidos y por lo tanto no es necesario agregar masa en esta dirección. Por
otro lado, como queremos calcular la respuesta de una estructura debido a un sismo
actuando en la dirección horizontal, debemos asignar las masas adicionales en la
dirección X global (o eje 1 en la ventana de “Joint Masses”). Generalmente para
obtener la respuesta a un sismo en la dirección horizontal, no es necesario asignar
también las masas en la dirección vertical (eje Z global, o 3). Esto se debe a que los
modos asociados a la vibración vertical y horizontal de la estructura están casi todos
“desacoplados” (o sea, la deformación modal es puramente vertical o transversal). En
este caso, la respuesta sísmica no cambia mucho si no se agrega la masa en la
dirección Z o 3. La situación sería distinta si se estuviera analizando un MARCO
plano con barras inclinadas: en este caso los modos están “acoplados” y
necesariamente se debe asignar la masa en la dirección horizontal (1) y vertical (3).
No obstante lo mencionado, se recomienda agregar las masas adicionales en ambas
direcciones para evitar sorpresas y porque el esfuerzo computacional es exactamente
el mismo.

Paso 3 [Definir la Función para el Análisis en el Tiempo]: Para definir la función
que describe la variación en el tiempo del terremoto siga los siguientes pasos.

\1. Desde Windows Explorer o My Computer en su computadora ubique el
Directorio (“Folder”) de SAP2000. Dentro de este directorio debe haber un
sub-directorio llamado “Examples”. Entre a este directorio y copie el
archivo del “Elcentro” al directorio en que usted se encuentra trabajando en
este ejemplo. Este archivo tiene un total de 222 valores de aceleración del
terremoto de El Centro. Las primera, tercera y quinta columnas contienen
los tiempos en intervalos no uniformes hasta el tiempo t = 12.133 seg. Las
restantes columnas contienen los valores de la aceleración del suelo como
fracción de la aceleración de la gravedad g, o sea en porciento de g. Por
ejemplo, el valor máximo del acelerograma es 0.3194. En las unidades que
estamos usando, la máxima aceleración sería 0.3194 x 9.81 = 3.133 m/s2

\2. Abra el menú de “Define” y escoja “Time History Functions…”. Esto abre
la ventana de “Define Time History Functions” que se muestra en la
siguiente figura. Apriete el botón de “Add Function From File” para abrir la
ventana “Time History Function Definition”. Esto abre la ventana “Time
History Function Definition” que se muestra abajo. En la caja de “Function
Name” de la nueva ventana escriba ELCENTRO. Presione a continuación
el botón de “Open File”. Al hacer esto se abrirá una ventana donde se

120
Traducido por Luis E. Suárez y Drianfel Vázquez
Manual proporcionado en el seminario Internacional de CSI 2004 por:
www.construaprende.com / www.morrisoningenieros.com

<!-- p. 123 -->

muestran todos los archivos con datos de SAP2000 del subdirectorio de
trabajo. Seleccione “All files (*.*)” en el recuadro inferior de tipos de archivo
(“Files of type:”). Busque allí el archivo Elcentro que grabó anteriormente y
selecciónelo (con un doble BI).

\3. El nombre del archivo debe haber aparecido en el recuadro de “Function
File” como se muestra en la siguiente figura. Escriba 6 en la caja de
“Number of Points per Line” (Número de Puntos por Fila).

\4. Seleccione la opción “Time and Function Values” (Valores del Tiempo y de
la Función) porque, como se mencionó anteriormente, el registro de El
Centro que tiene SAP2000 está definido por los tiempos junto con las
aceleraciones en esos instantes. Presione OK.

\5. Observe que en la ventana “Define Time History Functions” apareció el
nombre de la nueva función que se definió (ELCENTRO). Presione OK
para retornar a la pantalla principal.

\6. Para convertir el Archivo como función de usuario presione el botón
“convert to User Defined” luego se puede apreciar de la siguiente figura.

121
Traducido por Luis E. Suárez y Drianfel Vázquez
Manual proporcionado en el seminario Internacional de CSI 2004 por:
www.construaprende.com / www.morrisoningenieros.com

<!-- p. 124 -->

Recuerde grabar el archivo actualizado de su modelo.

Paso 4 [Definir el Caso de Análisis en el Tiempo]: Para definir el caso de análisis
en el tiempo siga los siguientes pasos.

\1. Comience en el menú principal con “Define”. Abra la opción de “Analisis
Cases…” (Casos de Análisis). Esto abre la ventana “Analisis Cases” (Agregue
im Nuevo Caso). Esta acción abre la ventana “Analisis Case Data” (Datos
del Caso de Análisis) luego en la Opción Analisis Cases Type escoja el tipo de
análisis que se realizará “Time History” que se muestra a continuación. En
esta ventana se deben entrar varios datos.

122
Traducido por Luis E. Suárez y Drianfel Vázquez
Manual proporcionado en el seminario Internacional de CSI 2004 por:
www.construaprende.com / www.morrisoningenieros.com

<!-- p. 125 -->

\2. En la caja de “History Case Name” deje el nombre de HIST1.

\3. En el recuadro de Options deje el “Analysis Type” (Tipo de Análisis) como
“Linear” dado que queremos efectuar un análisis lineal.

\4. En el primero de los cuatro recuadros de “Loads Applied” se especifica la
direccion en la que actua el acelerograma que se va a usar. Como en nuestro
ejemplo la componente del sismo actua en la local U1 de eje global X
(horizontal), escoja la opcion de “accel” de la caja de “Load Type” y en
“Load Name escoja U1.”

\5. Cambie a ELCENTRO la opción en la caja de “Function”.

\6. En la caja de “Scale Factor” se debe ingresa el factor de escala por el cual se
va a multiplicar al acelerograma para tener los valores en unidades
consistentes con las usadas para la definición de la estructura (en la esquina
inferior derecha de la pantalla). Escriba 9.81 que es el factor para convertir el
acelerograma a metros/seg2. Recuerde que el registro del terremoto de El

123
Traducido por Luis E. Suárez y Drianfel Vázquez
Manual proporcionado en el seminario Internacional de CSI 2004 por:
www.construaprende.com / www.morrisoningenieros.com

<!-- p. 126 -->

Centro que trae SAP2000 está en fracciones o % de g. Luego presione ADD
para añadir como dato.

\7. Escriba 1200 en la caja de “Number of Output Steps” (éste es el número de
pasos de tiempo para calcular los resultados).

\8. Escriba 0.01 en la caja de “Output Time Step Size”. Ésta es la duración en
segundos de los pasos de tiempo con los cuales se desea obtener la respuesta
de la estructura.

\9. En el cuadro de “Others Parameters” y “Modal Damping”
(Amortiguamiento Modal) presione el botón de “Modify/Show”. Esta
acción lo llevará a la venta de “Modal Damping” que se muestra a
continuación. En esta ventana se puede asignar una misma razón de
amortiguamiento a todos los modos de vibración o asignarle razones de
amortiguamiento individuales a cada modo. En este caso se va a asignar una
razón de amortiguamiento de 0.05 a todos los modos de vibración. Ingrese
entonces 0.05 en “Damping for all Modes”. Presione OK para regresar a la
ventana “Time History Case Data”.

\10. La ventana debe tener ahora los datos finales que se muestran en la figura
“Time History Case Data” anterior. Presione OK dos veces.

124
Traducido por Luis E. Suárez y Drianfel Vázquez
Manual proporcionado en el seminario Internacional de CSI 2004 por:
www.construaprende.com / www.morrisoningenieros.com

<!-- p. 127 -->

Paso 5 [Analizar la estructura]: Recuerde que en la segunda parte del ejemplo
de Análisis Dinámico 1 se había requerido que el programa calculara los
primeros 12 modos de vibración y periodos naturales. En la práctica, por lo
general, no es necesario emplear todos los modos de vibración.
La cantidad de modos conviene utilizar dependen de la estructura y del tipo de
excitación dinámica (terremoto, fuerza armónica, etc.). En este caso es suficiente
utilizar, por ejemplo, los 5 primeros modos. Se sugiere al lector que
posteriormente vuelva a analizar la estructura con los doce modos y compare los
resultados.

Especifique en el menú de “Analyze”, dentro de la opción de “Set Options”, la

opción de “Fast DOFs” de y verifique que la opción de “Dynamic
Analysis” esté seleccionada. Presione el botón de “Set Dynamic Parameters” y
cambie el 12 en la caja de “Number of Modes” por 5. Presione OK dos veces.

Corra e l análisis presionado o del menú de “Analyze” utilice la opción de
“Run”. Note que ahora el programa se toma más tiempo para producir los
resultados, debido a que está haciendo un análisis paso a paso en el tiempo.
Presione OK si el proceso terminó sin problemas.

Paso 6 [Deslazamientos en la Junta]: Como en todo análisis dinámico lineal,
ya sea de vibraciones libres o forzadas como en este ejemplo, el programa
muestra los modos de vibración. Sin embargo ahora hay mucha más
información disponible.

Vamos a ver, por ejemplo, los desplazamientos en una junta. Comience
presionando el botón de (“Show Undeformed Shape”) para ver la estructura
sin deformar. Seleccione la junta superior izquierda para la cual se desea ver el
historial de desplazamientos en el tiempo (debería ser la junta 2 de acuerdo a la
numeración interna que usa el programa).

Del menú de “Display” seleccione “Show Time History Traces…(Muestre las
Trazas del Historial) ”. Esto lo conducirá a la ventana de “Time History Display
Definition” que se muestra a continuación.

125
Traducido por Luis E. Suárez y Drianfel Vázquez
Manual proporcionado en el seminario Internacional de CSI 2004 por:
www.construaprende.com / www.morrisoningenieros.com

<!-- p. 128 -->

Seleccione la junta (Joint2) del cuadro de “List of Functions” y presione el botón
que dice “Define Functions”. Esto lo conducirá a la siguiente ventana de “Time
History Functions”

126
Traducido por Luis E. Suárez y Drianfel Vázquez
Manual proporcionado en el seminario Internacional de CSI 2004 por:
www.construaprende.com / www.morrisoningenieros.com

<!-- p. 129 -->

Seleccione “Joint2” y presione el botón de “Modify/Show TH Function”. Esto
lo conducirá a la ventana de “Time History Joint Function” que se muestra a
continuación.

Note que por omisión SAP2000 grafica los desplazamientos (la opción “Disp”
está pre-seleccionada). Usted puede escoger la respuesta que desea graficar en el
recuadro de “Vector Type”. En el recuadro de “Component” debe seleccionar la
componente de la respuesta que escogió en “Vector Type”.

Como queríamos obtener el historial de desplazamientos horizontales de la junta
2, dejamos las opciones originales.

Presione OK dos veces para volver a la pantalla de “Time History Display
Definition”.

Seleccione “Joint2” en el recuadro “List of Functions” y presione el botón que
dice “Add->”. Observe que “Joint2” pasó ahora al cuadro de la derecha de
“Plot Functions” y está seleccionado. El resultado se muestra en la figura
correspondiente anterior. Presione el botón de “Display” en la parte inferior
para ver el historial de desplazamientos en función del tiempo. Este último se
muestra a continuación. Presione OK si desea salir de esta ventana.

127
Traducido por Luis E. Suárez y Drianfel Vázquez
Manual proporcionado en el seminario Internacional de CSI 2004 por:
www.construaprende.com / www.morrisoningenieros.com

<!-- p. 130 -->

En el cuadro de “Legend” a la derecha el programa muestra los mínimos y
máximos valores de la respuesta graficada, y los instantes de tiempo en que
ocurren. Además, si posiciona el cursor en un punto sobre la curva, las
coordenadas del mismo (desplazamiento en metros y tiempo en segundos)
aparecen en el recuadro inferior derecho. El gráfico en la pantalla se puede
imprimir simplemente abriendo el menú “File” en esta ventana. Escoja “Print
Graphics” si desea obtener una copia en papel de la figura, o si lo desea, puede
obtener los valores numéricos en una tabla. Para esto us e la opción “Print
Tables to File…”. En la nueva ventana que se abre escoja un nombre para el
archivo con el historial de la respuesta. Por omisión la extensión del archivo es
“.txt”. Luego puede abrir con un procesador de texto el archivo creado. En este
ejemplo el archivo contendrá dos columnas, una con los tiempos y otra con los
desplazamientos correspondientes, además de otros datos necesarios para
identificar la información guardada (unidades, etc.)

Nota:

Si presiona OK y vuelve a la ventana “Time History Display Definition”, observe
que es posible modificar el gráfico anterior. Por ejemplo puede cambiar el color de la
curva con el botón de “Color”, el que abre una paleta. Puede seleccionar el lapso de
tiempo de la función que desea graficar, cambiando los valores estándar de cero hasta
el final del intervalo. Para esto simplemente entre los instantes inicial y final de

128
Traducido por Luis E. Suárez y Drianfel Vázquez
Manual proporcionado en el seminario Internacional de CSI 2004 por:
www.construaprende.com / www.morrisoningenieros.com

<!-- p. 131 -->

tiempo en los casilleros “From” y “To”, respectivamente en el recuadro de “Time
Range”. Por último, puede agregarle un texto identificatorio a los ejes horizontal y
vertical escribiendo esta información en el recuadro “Axis Labels”, en las cajas
“Horizontal” y “Vertical”.

Paso 7 [Cortante total en la base]: Para obtener un gráfico de la variación del
cortante total en la base (la suma del cortante en las dos columnas), seleccione
nuevamente “Define Function” de la ventana de “Time History Display Definition”.
En la ventana que se abre de “Time History Functions” seleccione la opción de “Add
Base Function” como se muestra en la siguiente figura.

Se abre una nueva pantalla de “Base Function” (ver figura). Seleccione allí “Base
Shear X” (Cortante Basal X) como se muestra a continuación.

129
Traducido por Luis E. Suárez y Drianfel Vázquez
Manual proporcionado en el seminario Internacional de CSI 2004 por:
www.construaprende.com / www.morrisoningenieros.com

<!-- p. 132 -->

Presione OK dos veces para volver a la pantalla de “Time History Display
Definition”, presione “ADD->” sobre la función de “Base Shear X” en el recuadro
de “List of Functions”. Seleccione “Joint 2” del recuadro de “Plot Functions” y
presione el botón de “\<-Remove” para remover esa función de la figura a graficar.
Presione el botón de “Display” para ver el historial del cortante total en la base, el
que se muestra en la figura a continuación.

Presione OK para cerrar esta ventana y volver a la pantalla de “Time History

130
Traducido por Luis E. Suárez y Drianfel Vázquez
Manual proporcionado en el seminario Internacional de CSI 2004 por:
www.construaprende.com / www.morrisoningenieros.com

<!-- p. 133 -->

Paso 8 [Cortante en la columna izquierda (Elemento 4)]: Para obtener un gráfico
de la variación del cortante en la columna de la izquierda, seleccione nuevamente
“Define Function” en la ventana de “Time History Display Definition”. En la
ventana que se abre de “Time History Functions” seleccione la opción de “Add
Element Frame Forces” como se muestra en la siguiente figura.

Aparece la ventana de “Time History Frame Function” que se muestra en la próxima
figura. Escriba 4 en el cuadro de “Element ID” (Identificación del Elemento).
Seleccione la opción de “Shear 2-2” en el recuadro de “Component”. Deje la opción
de “Include all” seleccionada en el recuadro de “Mode Number” y en el recuadro de
“Location” deje la estación (“Station”) 1 que corresponde al extremo inicial del
elemento. Si desea el historial del cortante en un punto intermedio del elemento
seleccione la estación (“Station”) 2 y si desea el cortante en el otro extremo del
elemento, seleccione la estación 3.

131
Traducido por Luis E. Suárez y Drianfel Vázquez
Manual proporcionado en el seminario Internacional de CSI 2004 por:
www.construaprende.com / www.morrisoningenieros.com

<!-- p. 134 -->

Presione OK dos veces para volver a la pantalla de “Time History Display
Definition”, presione “ADD->” sobre la función de “Frame4” en el recuadro de
“List of Functions”. Seleccione “Base Shear X” del recuadro de “Plot Functions” y
presione el botón de “\<-Remove” para remover esa función. Presione el botón de
“Display” para ver el historial del cortante en el elemento 4, estación 1, que se
muestra en la siguiente figura.

132
Traducido por Luis E. Suárez y Drianfel Vázquez
Manual proporcionado en el seminario Internacional de CSI 2004 por:
www.construaprende.com / www.morrisoningenieros.com

<!-- p. 135 -->

Fin del Ejemplo de Análisis Dinámico #2

133
Traducido por Luis E. Suárez y Drianfel Vázquez
Manual proporcionado en el seminario Internacional de CSI 2004 por:
www.construaprende.com / www.morrisoningenieros.com

<!-- p. 136 -->

Capítulo
5
Ejemplo de Análisis usando un
Espectro de Respuesta

Descripción del problema: Vamos a usar como ejemplo el MARCO de hormigón
de un piso y un tramo que se muestra en la figura. Por simplicidad vamos a utilizar
vigas y columnas de sección cuadrada de 16 pulgadas.

Paso 1 [Establecer unidades del sistema]: Inicie el programa SAP2000 y cambie
las unidades a .

Paso 2 [Definición de la Geometría]: Del menú principal de “File” seleccione

“New Model from Template…” y seleccione la opción de “Portal Frame” .
En la ventana del “Portal Frame” escriba 1 para el “Number of Stories”, 1 en el
“Number of Bays”, 15 para la opción de “Story Height” y 40 en la opción de “Bay
Width”. Presione OK. Cierre la ventana de 3-D. Esto le genera el marco que se
muestra en la siguiente figura.

134
Traducido por Luis E. Suárez y Drianfel Vázquez
Manual proporcionado en el seminario Internacional de CSI 2004 por:
www.construaprende.com / www.morrisoningenieros.com

<!-- p. 137 -->

Paso 3 [Definición de las condiciones de borde]: Seleccione los apoyos

haciendo BI sobre ellos. Presione del “toolbar” principal en la parte
superior de la pantalla. De la ventana d e “Joint Restraint” que aparece,

seleccione del marco de “Fast Restraint”. Presione OK.

Paso 4 [Aumentar los grados de libertad]: Habiamos visto en el Ejemplo de
Análisis Dinámico 1 que a diferencia del análisis estático de estructuras, el
análisis dinámico con modelos discretos nunca es exacto aunque tiende a la
solución exacta a medida que el número de grados de libertad crece. Por lo
tanto vamos a representar las columnas y vigas con cuatro elementos para
aumentar el número de grados de libertad y la precisión de los resultados. Para
esto seleccionamos la estructura completa con Ctrl + A. Luego seleccione del

135
Traducido por Luis E. Suárez y Drianfel Vázquez
Manual proporcionado en el seminario Internacional de CSI 2004 por:
www.construaprende.com / www.morrisoningenieros.com

<!-- p. 138 -->

menú principal de “Edit” la opción de “Divide Frames...”. Para dividir cada
elemento en cuatro subelementos escriba 4 en la opción de “Divide into” y 1 en
la opción de “Last/First ratio” en la ventana de “Divide Selected Frames” como
se muestra a continuación. Esta opción de “Divide Frames” fue detallada en el
Ejemplo de Armaduras 1. Presione OK

Paso 5 [Definir y asignar las secciones de los MARCOS]: Cambie las unidades a
. Seleccione todas las columnas y vigas del MARCO utilizando la

herramienta de (“Select All”) del “toolbar” ubicado en la parte izquierda de la
pantalla principal de SAP2000. Esto también puede hacerse con Ctrl.+A o con la
secuencia menú “Select” → Select → All.

Presione el icono de (o use el menú de “Assign” → Frame→ Sections…).
Presione Modify/Show Section.

Deje el nombre de FSEC1 (Frame Section 1) que tiene SAP2000 por omisión,
cambie el material a CONC y las dimensiones a 16 para la profundidad o altura y
para el ancho. Presione OK dos veces.

Recuerde grabar el archivo actualizado de su modelo (por ejemplo, con el
nombre Esp ectro).

Paso 6 [Definición de la carga sísmica]: Vamos ahora a escojer el espectro de
respuesta o de diseño que queremos usar. La versión 7.4 de SAP2000, tiene una
serie de espectros predefinidos tomados del código UBC-94 (Uniform Building
Code, edición 1994). Estos pueden verse de la siguiente manera:

Comience en el menú principal “Define” → “Response Sepctrum
Function”. Esto lo conduce a la siguiente ventana.

136
Traducido por Luis E. Suárez y Drianfel Vázquez
Manual proporcionado en el seminario Internacional de CSI 2004 por:
www.construaprende.com / www.morrisoningenieros.com

<!-- p. 139 -->

Nota:

En la ventana se muestra a la izquierda los espectros predefinidos. Los botones de la
derecha permiten entrar un espectro nuevo (directamente en el programa o leyéndolo
de un archivo). También se pueden usar para graficar los valores de las funciones
que están a la izquierda.

Vamos a seleccionar el UBC94Spectrum. Al presionar el boton “Add New
Function..” nos muestra una ventana “Response Spectrum UBC 94 Function
Definition”. El nombre de la funcion por defecto muestra “FUNC1” en el
cuadro de “parameters” en la opcion “Seismic Zone Factor, Z” (0.4) “Soil Type”
(2) identifican al tipo de suelo (suelo rigido o denso con profundidad mayor de
200 pies o 61 metros). En la ventana tambien podemos observar la función del
espectro de la UBC 94 definidos para los paraetros indicados como se muestra
en la ventana “Define Function” y en el cuadro “Function Graph” muestra el
grafico del espectro. Presione OK kis veces para volver a la pantalla principal.

137
Traducido por Luis E. Suárez y Drianfel Vázquez
Manual proporcionado en el seminario Internacional de CSI 2004 por:
www.construaprende.com / www.morrisoningenieros.com

<!-- p. 140 -->

Paso 7 [Definición de casos de espectros]: Vamos ahora a escojer el espectro
de respuesta que queremos usar. Para esto, del menú principal de “Define”
seleccione la opción de “Response Spectrum Cases” (Casos de Espectros de
Respuesta). Dijimos que el programa tiene una serie de espectros predefinido s
tomados del código UBC-94. Estos pueden verse haciendo lo siguiente:

Comience en el menú principal “Define” y selecione la opción
“Response Spectrum Function” (Función de Espectro de Respuesta). Esto lo
conduce a la siguiente ventana de “Define Response Spectra” (Defina los
Espectros de Respuesta).

138
Traducido por Luis E. Suárez y Drianfel Vázquez
Manual proporcionado en el seminario Internacional de CSI 2004 por:
www.construaprende.com / www.morrisoningenieros.com

<!-- p. 141 -->

(Agregue Nuevos Casos) lo que lo conduce a la siguiente ventana.

En el recuadro de Análisis Case Type seleccione “Response Spectrum” y luego
en el recuadro de “Análisis Case Name” (Nombre del Caso de Análisis) deje el
nombre de SPEC1 que es el nombre por defecto.

139
Traducido por Luis E. Suárez y Drianfel Vázquez
Manual proporcionado en el seminario Internacional de CSI 2004 por:
www.construaprende.com / www.morrisoningenieros.com

<!-- p. 142 -->

En el recuadro de “Modal Combination” (Combinación Modal) seleccione la
opción de SRSS (o “Square Root of Sum of the Squares”). Note que la opción
por omisión es CQC (“Complete Quadratic Combination”). No obstante, vamos
a aplicar la combinación de la raíz cuadrada de la suma de los cuadrados (o sea la
SRSS) porque todavía es la más usada en la práctica.

En el recuadro de “Directional Combination” (Combinación Direccional) deje la
opción de SRSS. Como no estamos haciendo un análisis tridimensional con
sismos en más de una dirección, esta opción es irrelevante para nuestro ejemplo.
En el recuadro de “Input Response Spectra” (Espectros de Respuesta de
Entrada) debemos escoger la dirección en la cual queremos que se aplique el
terremoto. Hay tres opciones: U1, U2 y U3. Éstas se refieren a los ejes locales
1, 2 y 3. Si el ángulo de la excitación que se definió antes es cero, entonces: U1
\= X, U2 = Y y U3 = Z, donde X, Y y Z son los ejes globales. En nuestro caso
queremos considerar la componente horizontal del sismo, por lo tanto vamos a
escoger la función de UBC94S2 en la dirección U1.

Por último vamos a ingresar el valor de 139.1 en la caja de “Scale Factor” (Factor
de Escala). Este factor se explica en la siguiente nota. Presione OK cuando haya
terminado.

Nota:

Note que el espectro que vimos en el paso anterior está en %g (o en otrras palabras,
como fracción de la aceleración de la gravedad) y tiene una máxima aceleración del
suelo igual a 1 (o sea para periodo cero el valor es 1-g). Por lo tanto, debemos
escalarlo para que tenga la máxima aceleración del suelo correspondiente al sitio
donde se va a construir la estructura. Por ejemplo, en el caso de Puerto Rico,
ubicado en Zona 3 en la clasificación del código UBC-97, y para un tipo de suelo Sd,
según el mismo código, esta aceleración máxima deber ser 0.36g. Además debemos
asignarles unidades a espectro, en este caso pulg/s2 para lo cual lo multiplicamos
también por el valor de g correspondiente (386.4 pulg/s2). En resumen el factor de
escala (“Scale Factor”) es igual a 0.36 * 386.4 = 139.1 pulg/s2.

Paso 8 [Analizar la estructura y obtener las frecuencias naturales]: Abra el
menú de “Analyze” y la opción de “Set Options…”. Escoja la siguiente opción
d e “Fast DOFs”:

140
Traducido por Luis E. Suárez y Drianfel Vázquez
Manual proporcionado en el seminario Internacional de CSI 2004 por:
www.construaprende.com / www.morrisoningenieros.com

<!-- p. 143 -->

Abajo en la misma pantalla seleccione la opción de “Dynamic Analysis”. Note
que al seleccionar esta opción se activa el botón que está a la derecha y que tiene
como descripción “Set Dynamic Parameters”. Presione este botón, lo que lo
conducirá a la siguiente pantalla que se muestra. Escriba 8 en número de modos
(o de frecuencias naturales) y deje los demás parámetros como los tiene el
programa por omisión. Presione OK dos veces para llegar a la pantalla principal.

Corra el análisis presionado o mediante la opción de “Run” en el menú de
“Analyze”.

Al terminar de analizar el modelo, el programa nos muestra el primer modo de
vibración. Para ver todos los modos de vibración siga el Paso 5 del Ejemplo de
Análisis Dinámico 1. Se recomienda examinar los modos para asegurarse que el
modelo produce los resultados que uno espera.

Paso 9 [Resultados]: Para ver la deformación máxima de la estructura presione

el icono de . De la ventana que aparece de “Deformed Shape”, seleccione en
el recuadro de “Load” la opción de “SPEC1 Spectra”, deje el recuadro de
“Scaling” con los valores por omisión y en el recuadro de “Options” seleccione
la opción de “Wire Shadow” como se muestra a continuación.

141
Traducido por Luis E. Suárez y Drianfel Vázquez
Manual proporcionado en el seminario Internacional de CSI 2004 por:
www.construaprende.com / www.morrisoningenieros.com

<!-- p. 144 -->

Presione OK. El programa muestra la estructura deformada superpuesta con la
no deformada como se muestra a continuación.

142
Traducido por Luis E. Suárez y Drianfel Vázquez
Manual proporcionado en el seminario Internacional de CSI 2004 por:
www.construaprende.com / www.morrisoningenieros.com

<!-- p. 145 -->

Si deseamos conocer los desplazamientos o la rotación de una junta en
particular, vamos a esta junta y la seleccionamos haciendo BD sobre la misma.
Se abrirá una ventana donde aparece la información deseada. Esto se había
m ostrado en el Paso 15 del Ejemplo de Vigas 1.

Para ver las reacciones presione el icono de y seleccione la opción de
“SPEC1 Spectra” en el recuadro de “Load” de la ventana de “Joint Reaction
Forces” que se abre. Además asegúrese que la opción de “Reactions” esté
seleccionada. El resultado se muestra a continuación. Recuerde que para ver los
momentos en la base de la columnas debe cambiar la vista de la estructura del
pnao X-Z a una 3-Dim. Por supuesto, siempre se puede observar los valores
numéricos de las reacciones haciendo un BD sobre el apoyo que nos interesa.

143
Traducido por Luis E. Suárez y Drianfel Vázquez
Manual proporcionado en el seminario Internacional de CSI 2004 por:
www.construaprende.com / www.morrisoningenieros.com

<!-- p. 146 -->

Para observar los cortantes presione el icono de y seleccione la opción de
“SPEC1 Spectra” en el recuadro de “Load” de la ventana de “Member Force
Diagram for Frames” (Diagramas de Fuerza en los Miembros para MARCOS)
que se abre. En el recuadro de “Component” escoja la opción “Shear 2-2”
(Cortante en la dirección del eje 2). Además seleccione la opción de “Show
Values on Diagram” (Muestre los Valores en el Diagrama) y deje la opción
“Scaling” (Escala) en “Auto” (automático). El diagrama de cortante del
MARCO se muestra a continuación.

Para escoger la fuerza cortante que se desea que el programa grafique, tenga en
cuenta que para una barra horizontal el eje 2 coincide con el eje Z global y para
una barra vertical, el eje 2 está en la dirección del eje X global.

144
Traducido por Luis E. Suárez y Drianfel Vázquez
Manual proporcionado en el seminario Internacional de CSI 2004 por:
www.construaprende.com / www.morrisoningenieros.com

<!-- p. 147 -->

Para ver los momentos flectores presione el icono de y seleccione la
opción de “SPEC1 Spectra” en el recuadro de “Load” de la ventana de
“Member Force Diagram for Frames” que se activa. Asegúrese de seleccionar la
opción “Moment 3-3” (momento alrededor del eje 3) en el recuadro de
“Component”. Seleccione la opción de “Show Values on Diagram” y deje
“Scaling”en “Auto”. Al presionar OK aparece el diagrama que se muestra a
continuación.

Para seleccionar el momento que se desea graficar, recuerde que para una
estructura plana como la nuestra el eje 3 tiene siempre la dirección del eje global
X (o sea normal a la pantalla).

145
Traducido por Luis E. Suárez y Drianfel Vázquez
Manual proporcionado en el seminario Internacional de CSI 2004 por:
www.construaprende.com / www.morrisoningenieros.com

<!-- p. 148 -->

Nota:

Cuando se usa el método del espectro de respuesta nuestro objetivo es calcular
aproximadamente la máxima respuesta en valor absoluto de una estructura a un
terremoto específico representado por su espectro de aceleraciones, o a los posibles
sismos de diseño representados por un espectro de diseño. En el caso de un
MARCO plano, las máximas respuestas pueden ser, por ejemplo, los dos
desplazamientos y el giro de las juntas, o la fuerza axial, cortante y momento en los
extremos de cada barra. Como se explica en los cursos o textos de Dinámica de
Estructuras, el método predice la máxima respuesta en cada modo de la estructura, y
luego las combina de acuerdo a una regla. Cuando se usa la regla SRSS (el caso de
este ejemplo) , las respuestas modales se elevan al cuadrado, se suman y al resultado
se le saca la raiz cuadrada. Por lo tanto el método NO nos da los signos de estas
cantidades, o en otras palabras los resultados son todos positivos. En la realidad, una
respuesta puede ser positiva o negativa. Si calculásemos la verdadera respuesta
máxima en el tiempo, el resultado sería un valor cercano a una de las dos cantidades
positiva o negativa. Esto tiene implicaciones importantes para el diseño. Por
ejemplo, para diseñar la viga y las columnas del MARCO debemos considerar los dos
posibles diagramas de momentos con signos contrarios como los se muestran en las
dos figuras a continuación.

146
Traducido por Luis E. Suárez y Drianfel Vázquez
Manual proporcionado en el seminario Internacional de CSI 2004 por:
www.construaprende.com / www.morrisoningenieros.com

<!-- p. 149 -->

Las dos figuras siguientes fueron obtenidas aplicando cargas nodales horizontales con
de 56.51 k en la junta superior izquierda en los dos sentidos del eje de X. Para el
lector con curiosidad, el valor de 11.78 k fue obtenido usando la fórmula que se
muestra a continuación. Esta fórmula permite calcular los momentos en la junta entre
viga y columna de un MARCO de un claro y un piso, como el que se utilizó en este
ejemplo, cuando se le aplica una carga horizontal en un extremo de la viga. En este
caso, del análisis espectral anterior se obtiene que el momento en las juntas de la viga
es 30.54 k-ft. Usando este valor en la fórmula se puede despejar la carga lateral
“equivalente” P que generaría este momento. Al sustituir los valores de M = 30.54 kft, h = 15 ft, l = 40 ft, J1/J2 = 1 y εa =0.5 en la ecuación y despejar la carga lateral se
obtiene P = 11.78 k. Nóte que los momentos obtenidos con esta carga concentrada
son bastante parecidos a los obtenidos con el análisis espectral.

⎛ 1 + 1 ⎞
Ph ⎜ εa ⎟ M = v k a 2 ⎜ N ⎟ ⎜ ⎟
⎝ ⎠

donde:

P = Carga concentrada en la junta para un MARCO de un claro y un piso

εa = Factor de acarreo entre viga y columna

v ⎛ 1 ⎞
N = ⎜⎜ + 4 ⎟⎟ k a + 1
⎝ εa ⎠

J 1 h ka = ⋅
J 2 l

J1, J2 = Momentos de inercia de la viga y las columnas, respectivamente

h, l = altura y largo o claro del MARCO

147
Traducido por Luis E. Suárez y Drianfel Vázquez
Manual proporcionado en el seminario Internacional de CSI 2004 por:
www.construaprende.com / www.morrisoningenieros.com

<!-- p. 150 -->

Fin del Ejemplo de Análisis de Espectro de Respuesta
148
Traducido por Luis E. Suárez y Drianfel Vázquez
Manual proporcionado en el seminario Internacional de CSI 2004 por:
www.construaprende.com / www.morrisoningenieros.com

<!-- p. 151 -->

149
Traducido por Luis E. Suárez y Drianfel Vázquez
Manual proporcionado en el seminario Internacional de CSI 2004 por:
www.construaprende.com / www.morrisoningenieros.com

<!-- p. 152 -->

Sobre los autores

El Dr. Luis Edgardo Suárez se desempeña actualmente como profesor titular
(catedrático) en el Departamento de Ingeniería Civil y Agrimensura de la Universidad de
Puerto Rico, Recinto Universitario de Mayagüez (UPR-RUM). En este departamento
dicta cursos de pregrado, maestría y doctorado en el área de Análisis Estructural,
Mecánica Aplicada, Dinámica de Estructuras y Dinámica de Suelos. Además de las
actividades docentes, el Dr. Suárez trabaja en investigación en las áreas de dinámica
estructural, ingeniería de terremotos, métodos computacionales y vibraciones aleatorias.
Como resultado de su trabajo, ha publicado más de 40 artículos en revistas técnicas
internacionales con arbitraje y en más de 50 congresos técnicos, además de varios
reportes técnicos. El Prof. Suárez se graduó como el mejor de su clase en la Universidad
Nacional de Córdoba, Argentina, en 1981 con un diploma en Ingeniería Mecánica en un
programa de 6 años. Luego de trabajar como instructor por dos años en la misma
universidad, recibió su grado de maestría en 1984 y su grado doctoral en 1986, ambos en
Mecánica Aplicada del Departamento de Ciencias de la Ingeniería y Mecánica Aplicada
(Engineering Science & Mechanics, ESM) en Virginia Polytechnic Institute and State
University (Virginia Tech, VPI). Su disertación doctoral consistió en el análisis sísmico
de equipos mecánicos y componentes no estructurales de edificios. El Dr. Suárez se
unió a la Universidad de Puerto Rico en 1989 como profesor asistente (catedrático
auxiliar) en el Departamento de Ingeniería General. Anteriormente trabajó como
profesor asistente en el Departamento ESM en Virginia Tech y como profesor de
postgrado en el Departamento de Estructuras de la Universidad de Córdoba. El Dr.
Suárez se ha distinguido como profesor e investigador. Fue seleccionado entre los 20
mejores profesores en enseñanza del Colegio de Ingeniería en VPI. Recibió el “Ph. D.
Research Award” del Capítulo de VPI de Sigma Xi, una “Cunningham Fellowship” de
VPI, el “PR-EPSCoR Productivity Award” por dos años consecutivos, y dos “Tau Beta
Award” por excelencia en la enseñanza. El Dr. Suárez aparece listado en varias
publicaciones de referencia como por ejemplo: “Who's Who in Science & Engineering”,
“Who's Who in American Education”, “Who's Who in American Education”, “Who's
Who Among America's Teachers”, y “Who's Who Among Hispanic Engineers”. Fue
seleccionado como uno de los seis “Profesores Destacados” del Colegio de Ingeniería
de la UPR-M en los años 1994, 1996 y 1999. El Prof. Suárez ha supervisado proyectos
de investigación para el “US Army Research Office”, la “National Science Foundation”,
el “US Corps of Engineers”, NASA, y el “National Center for Earthquake Engineering
Research”. En la actualidad dirige dos proyectos de la “Federal Emergency Management
Agency”. Además es Editor de la Revista Internacional de Infraestructura Civil,
Accidentes y Desastres, miembro de la Junta Editorial de la revista “Engineering
Structures” y Editor para el Caribe y Centroamérica de la revista “Mechanics”. Es revisor
de artículos técnicos para trece revistas técnicas internacionales y es miembros de once
sociedades científicas y profesionales, entre ellas la ASCE, ASME, AIAA, ASEE, EERI,
y Sigma Xi.

Drianfel E. Vázquez Torres es estudiante doctoral en el Departamento de Ingeniería
Civil y Agrimensura del Recinto Universitario de Mayagüez de la Universidad de Puerto

150
Traducido por Luis E. Suárez y Drianfel Vázquez
Manual proporcionado en el seminario Internacional de CSI 2004 por:
www.construaprende.com / www.morrisoningenieros.com

<!-- p. 153 -->

Rico (UPRM). Su tesis se titula “Seismic behavior and Retrofitting of Hillside and Hilly
Terrain R/C Houses Raised on Gravity Columns” (comportamiento sísmico y
rehabilitación de casas de hormigón sobre columnas gravitatorias en laderas y colinas).
Completó su bachillerato con honores en ingeniería civil en esa misma institución en el
año 1998. Posteriormente, obtuvo una Maestría en Ciencias en la misma institución con
su tesis titulada “Detection and location of damage in experimental and analytical R/C
beams using modal methodologies” (detección y localización de daño en vigas
experimentales y analíticas de hormigón armado usando metodologías modales).
Además en la actualidad se desempeña como Instructor en el Departamento de
Ingeniería del Recinto de Ponce de la UPR. También ha enseñado como instructor en
la Pontificia Universidad Católica de Puerto Rico y en el Departamento de Ingeniería
General de la UPRM. Es miembro, en calidad de especialista estructural, del “Urban
Search and Rescue Team” de Puerto Rico (Equipo Urbano de Rescate y Búsqueda).
Además de la ingeniería estructural, otra de sus especialidades es el desarrollo de
interfases gráficas para programas de ingeniería civil.

151
Traducido por Luis E. Suárez y Drianfel Vázquez
Manual proporcionado en el seminario Internacional de CSI 2004 por:
www.construaprende.com / www.morrisoningenieros.com
