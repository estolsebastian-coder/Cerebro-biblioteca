---
type: libro
title: "Limusa - Diseño de Acero Estructural"
author: ""
categoria: "LIBROS, REVISTAS Y FOTOS"
paginas: 621
extraccion: "texto"
fuente: "local:E:/MATERIAL DE CONSULTA/LIBROS, REVISTAS Y FOTOS/ESTRUCTURA/ACERO/Limusa - Diseño de Acero Estructural.pdf"
convertido: 2026-10-16
---

# Limusa - Diseño de Acero Estructural

> Texto extraído de `LIBROS, REVISTAS Y FOTOS\ESTRUCTURA\ACERO\Limusa - Diseño de Acero Estructural.pdf` (621 páginas, texto). El PDF original está en el disco E: (MATERIAL DE CONSULTA); `<!-- p. N -->` marca el inicio de cada página.

<!-- p. 1 -->

La presente obra aborda los siguientes
temas:

\- Consideraciones generales de diseño

\- Elementos de diseño de marcos, armaduras y ,
puentes.

\- Comportamiento elástico, plástico y por pandeo
del acero estructural

\- Diseño de vigas a flexión -

\- Diseño de miembros a tensión

\- Columnas y puntales axialmente cargados

\- Diseño de vigas-columnas

\- Conexiones atornilladas y remachadas

\- Conexiones soldadas

• Trabes armadas

\- Apéndice. Selección de programas de
computadoras

<!-- p. 2 -->



<!-- p. 3 -->

DISEÑO DE ACERO
ESTRUCTURAL

JOSEPH E. BOWLES
Catedrático de Ingeniería Civil
en Bradley University

\~ LlMUSA
GR~~~ E~~~~~~~'a. Argentina •
Colombia. Puerto Rico lB

<!-- p. 4 -->

Versión autorizada en español
de la obra publicada en inglés
por McGraw-Hill Book Company, con el titulo:
STRUCTURAL STEEL DESIGN,
© 1980 by McGraw-Hill, Inc.
ISBN 0-07-006765-1
Versión española:
CARLOS ALBERTO GARCIA FERRER
Ingeniero Quimico e Ingeniero Civil
de la Universidad de La Habana, Cuba.

Revisión:
JOSE DE LA CERA ALONSO
Ingeniero Civil de la Facultad de Ingeniería
de la Universidad Nacional Autónoma de México, UNAM.
Diplom-Ingenieur de la Universidad Técnica de
Munich, Alemania Federal. Profesor de Tiempo
Completo e Investigador del Departamento de Materiales de la Universidad Autónoma Metropolitana.

Con la colaboración de:
ENRIQu'E MARTINEZ ROMERO
Ingeniero Civil de la Facultad de Ingeniería
de la Universidad Nacional Autónoma de México, UNAM.
Maestría en Ciencias de la Universidad de
Comel!, Estados Unidos. Profesor del Area de
Estructuras de la Facultad de Ingeniería de la
UNAM y Profesor de Estructuras Metálicas en la
Escuela de Ingeniería de la Universidad Anáhuac.
Consultor en Ingeniería Estructural.

Lap"'sentaci6n y disposici6nen conjuntode
OIsERoDE ACERO ESTRUCTURAL
son propiedaddel editor.Ningunaparte de esta obta
puede ser reproch.¡cif,M optmsmiticla.medianteningtJn sistema
o método.electrónico 'o mecánico(INCLUYENDO EL FOTOCOPIADO.
la gtabacióno cualquiersistemade fflCUp9ff1Ci6n y almacenamiento
de información). sin consentimiento por escritodel editor.

Derechosreservados:

© 1993,EDITORIALL1MUSA, S.A. de C.V.
GRUPONORIEGAEDITORES
Balderas95, C.P. 06040, México.Q.F.
Teléfono 521-21-05
Fax 512·29-03

Miembrode la Cámara Nacionalde la IncJustña
EditoñalMexicana.Registronúmero 121

Primera edición: 1984
Pñmerareimpresión:1989
Segundareimpresión: 1991
Tercerareimpresión:1992
Cuarta reimpresión: 1993
Impresoen México
(11996)

ISBN 968-18-1623-4'

<!-- p. 5 -->

PROLOGO

El propósito principal de este libro de texto es exponer los temas básicos para un
primer curso en diseño de acero estructural. El texto contiene elementos de diseño
tanto de edificios como de puentes, para usarlo en la secuencia de ingeniería
estructural de los programas de ingenieria civil. Si el instructor quisiera hacer énfasis eh las estructuras de edificios, el texto también es apropiado como introducción al diseño de acero estructural en los programas de arquitectura.
Se le da aproximadamente igual importancia a las unidades pie-lb-s y SI. Se
utilizan en la exposición de los temas ambos sistemas de unidades; los problemas
presentados como ejemplo y los que se dan para que los resuelva el alumno están
10mismo en un sistema de unidades que en el otro. Se adoptó este formato después de entrevistar y consultar a algunos miembros de la facultad y especialistas
de distintas industrias afines, que se interesan en este tema. Se acordó que en el
texto se debían seguir usando ambos sistemas de unidades, ya que la transición a
las unidades métricas no ocurre en la industria de la construcción con la misma
rapidez que en otras áreas de la ingeniería. Parece que es necesario este uso dual
para proporcionar tanto al estudiante como al instructor con la comprensión nece-
saria de 10que representan tanto para el estudiante como para el profesor, el ta-
maño razonable de un miembro (número), deflexión, o cualquier otro parámetro
de diseño, en ambas sistemas de unidades.
La instrucción práctica en el uso de las unidades SI requiere utilizar datos de
diseño, y corno ninguno de ellos era de fácil obtención, se ha reunido un juego de

5

<!-- p. 6 -->

ti PROLOGO

tablas con datos de secciones de acero laminado, como suplemento del texto; estos datos se calcularon usando computadoras. Estas tablas por lo general se ajustan a las especificaciones de la AISC y la A-6 de la ASTM. Este grupo de datos
también incluye material elaborado con base en las especificaciones de la AISC,
AASHTO, y AREA. Se espera que este texto, junto con el manual suplementario
Structura/Stee/Design Data(SSDD), sean los instrumentos necesarios para un curso de diseño de acero, sin necesidad de ninguna otra obra de consulta. El material
presentado en el curso debe ser suficiente para permitir a los estudiantes diseñar
miembros estructurales de rutina (y algunos no tan de rutina), ya sea en las unidades p, lb, s o SI, y usando cualesquiera de las tres especificaciones de diseño de
acero que es más probable que controlen el diseño -al menos en la práctica en los
E.V.A.- Los problemas especializados por lo general no se presentan en el aula, y
para estos casos (así como la práctica de diseño en las oficinas de ingeniería y para
otros trabajos no académicos), el lector debe obtener, de la agencia correspondiente, una copia de las últimas especificaciones.
Se ha usado la computadora digital como auxiliar en el diseño, de modo algo
interactivo (por medio del procesamiento en lotes) para la parte de diseño del curso de diseño de acero. Se ha visto que el uso de la computadora en los cursos de
diseño de acero es una de las mejores experiencias académicas para el estudiante,
porque los ayuda a adquirir rápidamente experiencia en el área del comportamiento estructural. Esto puede ser por accidente (al perforar de manera equivocada los
datos sobre el módulo de elasticidad, área transversal de la sección, o el momento
de inercia de un miembro) o por la repetición de un problema de diseño en el que
se cambian las dimensiones de los miembros según lo indiquen los resultados de la
computadora. En cualesquiera de los casos, los estudiantes perciben con facilidad
los efectos de la sección del miembro sobre el comportamiento estructural. El uso
de los programas de computadora permite obtener este resultado con sólo una pequeña cantidad de trabajo por parte del estudiante, y sin necesidad de escribir
programas.
En el Apéndice del texto se da una lista de algunos programas de computadora, para el uso de quienes no usen ya la computadora como auxiliar del diseño.
Estos programas son relativamente simples, pero eficaces, y se pueden perforar
fácilmente en tarjetas para ser usadas en un sistema local de computadoras. Se
usa el método de reducción del ancho de banda a fin de que sean mínimos los requerimientos de capacidad de la computadora. El autor puede suministrar estos
programas en cintas, al costo de la misma, la reproducción y los gastos de envío,
para cualquier persona que use actualmente este texto en las aulas.
No se ha tratado de citar, o promover el uso de calculadoras programables de
mesa, para simples tareas, como son el diseño de vigas o columnas, debido a la diversidad de dispositivos disponibles (por ejemplo, HP, TI, Sharp, Casio, etc.),
cada uno de los cuales requiere un método diferente de programación y además a
causa de los continuos y rápidos cambios en las técnicas. Para dar una lista de los
múltiples programas necesarios para el empleo de las diversas calculadoras, se hubiese necesitado demasiado espacio de esta obra, en detrimento del estudio de temas más importantes.

<!-- p. 7 -->

PROLOGO 7

El texto trata de establecer un equilibrio entre la teoría y la "manera de proceder". El tratamiento de los temas no es lo suficientemente complejo como para
oscurecer las bases, pero tiene la suficiente profundidad para que el lector conozca el origen de las ecuaciones de diseño que aparecen en las varias ecuaciones. Algunas de estas ecuaciones se deducen total o parcialmente, de modo que el lector
se dé cuenta de sus limitaciones. También se da una explicación razonablemente
detallada de los problemas básicos del diseño y los ejemplos ilustrativos se efectúan por lo general paso por paso. Con este formato, los estudiantes deben ser capaces de resolver los problemas de diseño más complejos a nivel profesional, y
obtener soluciones de diseño para los problemas asignados para resolverlos por
su cuenta.
Se cita directamente en el texto la bibliografía apropiada para aquellos temas cuyo tratamiento sea limitado pero que sean lo suficientemente importantes
como para que el lector desee estudiar el asunto con mayor profundidad. Por lo
general, la inclusión de referencias se acostumbra más en la práctica profesional
que a nivel escolar. La experiencia adquirida por el autor durante la enseñanza de
varios años de diseño de acero, indica que la mayoría de los estudiantes del primer curso de diseño se interesa principalmente en aprender cómo diseñar los diversos tipos de miembros estructurales que se les asignarán para su trabajo en
casa o en el laboratorio. En este punto de su desarrollo profesional no están demasiado interesados en las consideraciones teóricas ni en los extensos trabajos de laboratorio de los investigadores y teóricos, que han producido las ecuaciones
actuales de diseño.
La complejidad de las ecuaciones de diseño semiteóricas y empíricas, además
de la naturaleza del diseño estructural y su íntima relación con las especificaciones y códigos de diseño, hace necesario adoptar una actitud definida sobre el
enfoque que se debe utilizar al enseñar el diseño de acero. Es esencial presentar al
que los va a usar un juego de datos hipotéticos (o reales) y realizar un diseño como ilustración. Se presume que los estudiantes tienen preparación suficiente en
las secuencias básicas de ingeniería y matemáticas, para poder apreciar lo que se
ha ilustrado, y luego se les enseña a aplicar los pasos en un problema semejante
para así adquirir confianza y, basándose en los problemas ilustrativos extrapolar,
con un mínimo de supervisión, a un problema donde los parámetros de diseño
sean considerablemente diferentes.
En los problemas de ejemplo se introducen como apropiados, factores prácticos y de fabricación. Se consideran, en varias secciones, la separación de los sujetadores, la distancia al borde, los espacios libres para el montaje, distancias
normales de paso, paso de rosca, y mantenimiento. Esto da al usuario un panorama de los problemas de fabricación y otras consideraciones prácticas. Además de
todo esto, el texto tiene numerosas fotografías, complementadas con croquis
de los elementos y conexiones estructurales, lo que debe ser de ayuda particular al
principiante. El lector debe complementar dichas ilustraciones con la observación
de armaduras de acero en proceso de construcción. Las fotografías se tomaron
especialmente para este libro, para mostrar las características individuales de las
estructuras según se vayan estudiando a lo largo de la obra.

<!-- p. 8 -->

8 PROLOGO

En el capítulo 3 se describe brevemente el diseño plástico, junto con los con-
ceptos básicos de la teoría de placas. Se procede de este modo a fin de referir efi-
cazmente al capítulo 3 las ecuaciones que tienen su origen en el diseño plástico o
la teoría de placas, lo que representa un ahorro de espacio en el texto. No se hace
hincapié en los métodos de diseño plástico por dos razones básicas: no hay sufi-
ciente tiempo en un primer curso para cubrir apropiadamente el tema, y además
parece ser que, en la práctica profesional se prefiere el diseño elástico.
El autor se ha apartado de la tendencia actual en estos libros para reflejar el
formato que se incorporó en algunos de los textos sobre acero publicados en los
años cincuenta. Este formato incluye el uso de simples ejemplos ilustrativos, don-
de se enuncian sencillamente los datos de diseño, así como ejemplos de diseño
más realistas. Estos ejemplos se analizan en el capítulo 2 usando la computadora,
y se dejan algunos miembros para ser diseñados en capítulos posteriores. El uso
de ejemplos sencillos le da al lector una rápida comprensión de los objetivos gene-
rales de la exposición. Se usan ejemplos de diseño más detallados para dar un sen-
tido de realismo e indicar claramente que el diseño del acero no es sólo asunto de
manipular números. En cada ejemplo se comenta razonablemente el análisis utili-
zado.
Considerando las restricciones de tiempo en las clases, un diseño de-acero de-
be ser tan realista como sea posible. Por esta razón se alienta al alumno a proce-
sar cualesquiera de los problemas de diseño estructural, asignados en el capítulo 2,
en los capítulos posteriores, rediseñando los miembros según fuere necesario y re-
calculando una y otra vez el problema para determinar el tamaño de los
miembros antes de llegar a diseñar las conexiones, en los capítulos 8 y 9. Se puede
crear un falso sentido de seguridad en lo que respecta a la complejidad real del di-
seño estructural, y hasta de la manera como se llega a las cargas de diseño, si se le
dan simplemente al alumno las cargas para cada problema de diseño. Se debe re-
conocer que los problemas de diseño más realistas requieren mayor esfuerzo
físico y mental de parte del alumno y un mayor esfuerzo de clasificación de parte
del instructor. Se puede compensar un poco este esfuerzo asignando menos
problemas totales, pero incluyendo algunos en que se suministran las cargas, para
aumentar la confianza, y algunos con problemas de diseño, para aumentar la pe-
ricia en el diseño.
El siguiente programa podría ser apropiado para el sistema de semestres:

3 horas semestre. Tratamiento rápido de los capítulos 1 y 3, con el capítulo 3
asignado como lectura. Un tratamiento razonable de los capítulos 4 a 10. Tal vez
dos semanas en cada uno de los capítulos 4, 7, y 10.
4 horas semestre. Tratamiento rápido dé los capítulos 1 y 3. Dos semanas
para loscapítulos 2, 4, 7, y 10,seguidos por eldiseño real de la estructurade un edifi-
. cio y un puente de armadura para carreteras, o un edificio industrial, basándose en
los análisis del-capítulo 2. Una de las estructuras se debe calcular en unidades p,lb, s
y la otra en unidades SI. Se debe llevar una libreta de notas del diseño, donde se
muestren los cálculos y las entradas y salidas de la computadora. También se acon-
seja que se labore en grupos, con un máximo de cuatro estudiantes en cada grupo.

<!-- p. 9 -->

AGRADECIMIENTOS

Muchas personas y organizaciones proporcionaron considerable apoyo y ayuda
en la preparación de este libro. Primeramente quisiera expresar mi más sincera
gratitud al Dr. Peter Z. Bulkeley, Decano de Ingeniería y Tecnología de la Universidad de Bradley, que me concedió la licencia necesaria en mis labores docentes.
También quisiera dar gracias a Mr. Andrew Lally y Mr. Franck Stockwell,
Jr., de la AISC, quienes me suministraron una copia preliminar de las nuevas especificaciones de la AISC y quienes me dedicaron el tiempo necesario para revisar
junto conmigo las modificaciones más importantes. Mr. Lally también suministró provechosa información sobre cómo realizar las conversiones a unidades
SI. Mr. Robert Lorenz, de la Oficina Regional de la AISC en Chicago, tuvo la
gentileza de proporcionarme las correcciones más recientes para loscambios preliminares en las especificaciones.
Las corporaciones Bethlehem y la US Steel fueron muy amables al suministrar copias de los nuevos perfiles de sus seccionesde acero, casi un año antes de
que tuvieran carácter oficial; esto permitió adelantar el trabajo de cálculo por
computadora de las tablas del Structura/ Stee/ Design. Doy particularmente las
gracias a Mr. Roland Graham de la US Steel, quién revisó cuidadosamente secciones escogidas del manuscrito y todo el manual de datos de acero, e hizo muy
útiles sugerencias e indicaciones.
Doy mis más expresivas gracias al Dr. Eugen Chesson, del Departamento de
Ingeniería Civil de la Universidad de Delaware, por su gran ayuda al revisar con
gran cuidado los manuscritos tanto preliminares como finales del libro. Gracias
también al Dr. T. V. Galambos, del Departamento de Ingeniería Civil de la Universidad de Washington, San Luis, quien revisó el material de diseño para el factor de resistencia de carga.
El autor también desea expresar su agradecimiento a Mr. Gary Zika, ingeniero de construcción de la Pittsburg-Des Moines Steel Company, un antiguo
alumno en Bradley, quien ayudó a conseguir muchas de las fotografías usadas en
el texto.
Finalmente, doy gracias a mi esposa Faye, que ayudó a mecanografiar el manuscrito, verificó las cifras y las ordenó y, lo que es más importante, fue paciente
conmigo durante esos difíciles momentos.

Joseph E. Bow/es

9

<!-- p. 10 -->



<!-- p. 11 -->

CONTENIDO

Prólogo 5
Capítulo 1 Consideraciones generales de diseño 17
17 1-1 Tipos de estructuras
1-2 Procedimientos de diseño 18
1-3 El acero como material estructural 19
1-4 Productos de·acero 22
1-5 Resistencia del acero 25
1-6 Efectos de la temperatura en el acero 27
1-7 Códigos de diseño estructural 31
1-8 Cargas de construcción 33
1-9 Cargas sobre los puentes de carretera y ferrocarril 42
1-10 Cargas de impacto 48
1-11 Cargas sísmicas 50
1-12 Fatiga 56
1-13 Estructuras de acero 59
1-14 Exactitud de los cálculos y de las computadoras
electrónicas 65
1-15 Cálculos de ingeniería estructural en unidades SI 65

Capítulo 2 Elementos de diseño de marcos, armaduras y
puentes 71
2-1 Métodos de análisis 71
2-2 Análisis de vigas 75

11

<!-- p. 12 -->

12 CONTENIDO

2-3 Estructuras determinadas 78
2-4 Análisis de armaduras 78
2-5 Análisis de marcos rígidos 81
2-6 Análisis de puentes 83
2-7 El programa de computadora que se presenta en el
Apéndice 85
2-8 La matriz P 86
2-9 Condiciones de carga 90
2-10 Revisión de la salida de la computadora 91
2-11 Ejemplos de diseño 92

Capítulo 3 Comportamiento elástico, plástico y por
pandeo del acero estructural 135
3-1 Introducción 135
3-2 Teoría elástica y teoría plástica de diseño 136
3-3 Factores de seguridad en los diseños elásticos y
plásticos 146
3-4 Deflexionesde diseño plástico vsdeflexionesde diseño elástico 148
3-5 Longitud de la articulación plástica 149
3-6 Diseño elástico y diseño plástico 150
3-7 Diseño por factor de resistencia de carga 157
3-8 Pandeo local de placas 158
3-9 Resistencia posterior al pandeo de placas 164

Capítulo 4 Diseño de vigas a flexión 169
4-1 Consideraciones generales 169
4-2 Diseño de vigas por el método elástico 173
4-3 Diseño de vigas continuas 181
4-4 Pandeo y aplastamiento del alma 183
4-5 Criterios de cortante 187
4-6 Flexión según el eje fuerte y flexión según el eje débil 188
4-7 Deflexiones 189
4-8 Flexión biaxial y flexión en secciones asimétricas 192
4-9 Centro de cortante de secciones abiertas 200
4-10 Diseño de vigas sin soporte lateral 203
4-11 Vigas con patines no paralelos 212
4-12 Diseño de largueros de puente y vigas de piso 214
4-13 Vigas compuestas . 220
4-14 Diseño de vigas usando el factor de resistencia de
carga (DFRC) 241

Capítulo 5 Diseño de miembros a tensión 249
5-1 Tipos de miembros a tensión 249
5-2 Esfuerzos permisibles a tensión 251

<!-- p. 13 -->

CONTENIDO 13

5-3 Consideraciones generales de diseño 254
5-4 Esfuerzos debidos a la carga axial sobre la sección
neta 261
5-5 Diseño de las barras a tensión 263
5-6 Secciones netas 265
5-7 Diseño de miembros a tensión según el AISC 271
5-8 Diseño de miembros a tensión en los puentes 275
5-9 Diseño de cables 278
5-10 Diseño de miembros a tensión usando el DFRC 284

Capítulo 6 Columnas y puntales axialmente cargados 293
6-1 Introducción 293
6-2 La fórmula de Euler para columnas 294
6-3 Columnas con condiciones de extremo 297
6-4 Esfuerzos permisibles en las columnas de acero 298
6-5 Diseño de miembros armados a compresión 312
6-6 Placas de base de columnas 326
6-7 Soporte lateral de las columnas 333
6-8 Diseño de columnas y puntales usando el DFRC 334

Capítulo. 7 Diseño de vigas-columnas 341
7-1 Introducción 341
7-2 Consideraciones generales sobre la carga axial
combinada con la flexión 344
7-3 Longitudes efectivas de columnas en marcos de
edificios 348
7-4 Deducción de las fórmulas de diseño para vigas-
columnas 359
7-5 Determinación del coeficiente Cm de reducción por
interacción 366
7-6 Fórmulas de diseño de la AASHTO y el AREA, para
vigas-columnas 367
7-7 Diseñ.o de vigas-columnas usando las ecuaciones de 368 interacción
7-8 Columnas escalonadas y columnas con carga axial
intermedia 377
7-9 Control del desplazamiento lateral 384
7-10 Diseño de vigas-columnas usando el DFRC 386

Capítulo 8 Conexiones atornilladas y remachadas 395
8-1 Introducción 395
8-2 Remaches y conexiones remachadas 399
8-3 Tornillos de alta resistencia 403
8-4 Factores que afectan el diseñ.o de las juntas 409

<!-- p. 14 -->

14 CONTENIDO

8-5 Remaches y tornillos sometidos a cargas excéntricas 425
8-6 Conexiones de las vigas a los marcos 435
8-7 Sujetadores sometidos a tensión 439
8-8 Conexiones sometidas a cortante y tensión
combinados 447
8-9 Conexiones por momento (Tipo 1) 451
8-10 Factor de resistencia de carga (DFRC) para diseño de
conexiones 457

Capítulo 9 Conexiones soldadas 465
9-1 Consideraciones generales 465
9-2 Electrodos para soldar 468
9-3 Tipos de juntas y soldaduras 469
9-4 Desgarramiento laminar 475
9-5 Orientación de las soldaduras 476
9-6 Conexiones soldadas 477
9-7 Conexiones soldadas sometidas a cargas excéntricas 486
9-8 Placas soldadas para bases de columnas 496
9-9 Conexiones soldadas para placas de extremo 499
9-10 Conexiones soldadas en las esquinas 502
9-11 Diseño de soldaduras de filetes, usando el DFRC 508

Capítulo 10 Trabes armadas 513
10-1 Generalidades 513
10-2 Cargas 519
10-3 Proporcionamiento del patín y el alma de las trabes y
secciones armadas 522
10-4 Cubreplacas de longitud parcial 527
10-5 Proporciones generales de las trabes armadas 530
10-6 Teoría del diseño de las trabes armadas - AISC 532
10-7 Teoría del diseño de las trabes armadas ~ AASHTO
yAREA 553

Apéndice Selección de programas de computadoras 575
A-l Programa para el análisis de un marco 575
A-2 Generador de la matriz de cargas para el caso de
camiones, según la AASHTO, en un puente de
armadura 588
A-3 Generador de la matriz de carga, según el AREA,
para la carga COOPER E-80 en un puente de armadura 592

Indice 597

<!-- p. 15 -->

DISEÑO DE ACERO ESTRUCTURAL

<!-- p. 16 -->

Figura 1·1 El puente Eads a través del Mississippi en St. Louis, Missouri. Este puente de ferrocarril y
carretera, terminado en 1874, representa uno de los primeros usos del acero de alta resistencia (Fy =
50a 55 kip/pulg2) en los Estados Unidos, para una estructura importante. Al fondo se puede ver el arco de Sto Louís, con 192 m (630 pies) de altura, cubierto con una película de acero inoxidable.

<!-- p. 17 -->

CAPITULOUNO
CONSIDERACIONES GENERALES DE DISEÑO

1-1 TIPOS DE ESTRUCTURAS

El ingeniero estructural se ocupa del diseño de una variedad de estructuras que
incluyen, pero que no necesariamente se limitan, a las siguientes:

Puentes: Para ferrocarriles, carreteros, y de peatones.
Edificios: Que incluyen estructuras dé marco rígido, marcos simplemente conec-
tados, muros de carga, soportados por cables, y en voladizo. Se pueden con-
siderar o usar numerosos esquemas de' soporte lateral, como armaduras,
simples y alternadas, y un núcleo c~ntral rígido. Además, se pueden clasifi-
car los edificios según su empleo o altura como edificios de oficinas, in-
dustriales, fábricas, rascacielos, etc.
Otras estructuras: Incluyen torres para transmisión de potencia, torres para ins-
talaciones de radar y TV, torres de transmisión telefónica, servicios de sumi-
nistro de agua, y servicios de terminales de transporte, que incluyen ferro-
carriles, camiones, aviación y marina.

Además de las estructuras anteriores, el ingeniero estructural también se ocupa del diseño de navíos, aeroplanos, partes de diversas máquinas y otros equipos
mecánicos, automóviles, presas y otras estructuras hidráulicas, incluyendo el suministro de agua y la eliminación de desperdicios.

17

<!-- p. 18 -->

18 CONSIDERACIONES GENERALES DE DISEÑO

En este libro se trata en primer término del diseño estructural usando metales, y en particular, perfiles estructurales estándar como los que producen directamente los diversos fabricantes de acero, o en algunos casos con el uso de
miembros que se componen de placas y perfiles de acero y que se fabrican en las
fábricas productoras de acero o en talleres locales de elaboración de acero.

1-2 PROCEDIMIENTOS DE DISEÑO

El diseño estructural requiere la aplicación del criterio del ingeniero para producir
un sistema estructural que satisfaga de manera adecuada las necesidades del cliente o el propietario. A continuación, este sistema se incorpora a un modelo matemático para obtener las fuerzas en los miembros. Como el modelo matemático
nunca representa con exactitud la estructura real, otra vez es necesaria la habilidad del ingeniero para evaluar la validez del análisis a fin de poder aplicar las tolerancias apropiadas a la incertidumbre tanto en la deformación como en la estática.
Con base en las propiedades de los materiales, la función estructural, las
consideraciones ambientales y estéticas, se efectúan modificaciones geométricas
en el análisis del modelo, y se repiten los procesos de resolución hasta obtener una
solución que produce un equilibrio satisfactorio entre la selección del material, la
economía, las necesidades del cliente, sus posibilidades económicas, y diversas
consideraciones arquitectónicas. Rara vez, excepto quizás en las estructuras más
elementales, se obtiene una única solución; única en el sentido de que dos
compañías de ingeniería estructural obtendrían exactamente la misma solución.
\~ En la práctica de la ingeniería estructural, el diseñador dispone, para su posible uso, de numerosos materiales estructurales, que incluyen acero, concreto,
madera, y posiblemente plásticos y/o algunos otros metales, como aluminio y
hierro colado. A menudo, el empleo o el uso, el tipo de estructura, la situación u
otro parámetro de diseño impone el material estructural. En este texto se supone
que el diseño ha llegado al punto en que se ha decidido la forma estructural (es decir, como armadura, trabe, marco, domo, etc.) y que se han eliminado todos los
diversos materiales estructurales alternativos posibles, en favor del uso del acero.
Se procede entonces a efectuar cualquier análisis estructural requerido, y se hace
la selección del miembro y el diseño de la conexión, que sea apropiada al asunto
en estudio.
Las limitaciones de espacio y tiempo en el texto y en las aulas, limitan necesariamente al minimo esencial la complejidad de la presentación del diseño. El lector debe-estar consciente de que el diseño real es considerablemente mucho más
complejo, aún con experiencia, que las simplificaciones presentadas en los siguientes capítulos.
La seguridad, como preocupación de diseño tiene precedencia sobre todas
las otras consideraciones de diseño. La "seguridad" de cualquier estructura depende, naturalmente, de las cargas subsiguientes. Como la estructura, después de
su construcción, siempre estará sometida a cargas, y no siempre del modo o ma-

<!-- p. 19 -->

EL ACERO COMO MATERIAL ESTRUCTURAL 19

nera con que fue diseñada, la selección de las cargas de diseño constituye un
problema de estadística y probabilidad. Esta parte del problema resultaría bastante subjetiva, y produciría diseños extremadamente dispares, si no fuese por los
códigos de construcción que se han desarrollado (y que en una forma u otra se
usan casi universalmente); estos códigos establecen límites mínimos requeridos o
sugeridos en aquellos casos en que la seguridad pública constituye un factor
importante.

1-3 EL ACERO COMO MATERIAL ESTRUCTURAL

El acero es uno de los más importantes materiales estructurales. Entre sus propiedades de particular importancia en los usos estructurales, están la alta resistencia, comparada con cualquier otro material disponible, y la ductilidad. Q:?uctilidad es la capacidad que tiene el material de deformarse sustancialmente ya sea a
tensión o compresión antes de fallar)Otras ventajas importantes en el uso del acero son su amplia disponibilidad y durabilidad, particularmente con una modesta
cantidad de protección contra el intemperismo.
El acero se produce por la refinación del mineral de hierro y metales de desecho, junto con agentes fundentes apropiados, coke (para el carbono) y oxígeno,
en hornos a alta temperatura, para producir grandes masas de hierro llamadas
arrabio de primera fusión. El arrabio se refma aún más para remover el exceso
de carbono y otras impurezas y/o se alea con otros metales como cobre, níquel,
cromo, manganeso, molibdeno, fósforo, sílice, azufre, titanio, columbio, y vanadio, para producir las características deseadas de resistencia, ductilidad, soldadura y resistencia a la corrosión.
Los lingotes de acero obtenidos de este proceso pasan entre dos rodillos que
giran a la misma velocidad y en direcciones opuestas para producir un producto
semiterminado, largo y de forma rectangular que se llama plancha o lingote, dependiendo de su sección transversal. Desde aquí, seenvía el producto a otros molinos laminadores para producir el perfil geométrico final de la sección, incluyendo perfiles
estructurales así como barras, alambres, tiras, placas y tubos. El proceso de laminado, además de producir el perfil deseado, tiende a mejorar las propiedades materiales de tenacidad, resistencia y maleabilidad. Desde estos molinos laminadores, los
perfiles estructurales se embarcan a los fabricantes de acero o a los depósitos, según
se soliciten.
El fabricante de estructuras de acero trabaja con los planos de ingeniería o
arquitectura para producir dibujos detallados de taller, de los que se obtienen las
dimensiones requeridas para cortar, aserrar, o cortar con antorcha, los perfiles al
tamaño pedido y localizar con exactitud los agujeros para barrenar o punzonar.
Los dibujos originales también indican el acabado necesario de la superficie de las
piezas cortadas. Muchas veces se arman las piezas en el taller para determinar si
se tiene el ajuste apropiado. Las piezas se marcan para facilitar su identificación
en el campo y se embarcan las piezas sueltas o armadas parcialmente hasta el sitio
de la obra para su montaje. El montaje en el sitio la ejecuta a menudo el propio
fabricante, pero la puede hacer el contratista general.

<!-- p. 20 -->

20 CONSIDERACIONES GENERALES DE DISEÑO

Entre las más importantes propiedades estructurales del acero se tienen las siguientes:

\1. Módulo de elasticidad, E. El rango típico para todos los aceros (relativamente
independiente de la resistencia de fluencia) es de 28 000 a 30 000 k/pulg- ó
193 000 a 207 000 MPa.1\< El valor de diseño se toma por lo general como
29 000 k/pulg- ó 200 000 MPa.
\2. Módulo de cortante, G. El módulo de cortante de cualquier material elástico
se calcula como

G = E
2(1 + ¡.t)
donde ¡.t = coeficiente de Poisson que se toma como 0.3 para el acero. Usando
JI- = 0.3 se obtiene un valor de G = 11 000 k/pulg- ó 77000 MPa.
\3. Coeficiente de expansión térmica, a. El coeficiente de expansión térmica
puede tomarse como
a = 11.25 X 10-6 por "C
fJ.L = a(1J - T¡)L (pies o metros, dependiendo de la longitud L)
En estas ecuaciones, la temperatura está en grados Celsius. Para convertir de
Fahrenheit a Celcius, se usa
C =t(F - 32)

\4. Punto de fluencia y resistencia última. En la tabla 1-1 se dan los puntos de
fluencia de los varios grados de acero que interesan al ingeniero estructural, y
que se producen en las fábricas de acero.
\5. Otraspropiedades de interés. Estas propiedades incluyen la densidad de masa
del acero que es 4.2{Llbs/pie3 ó 7.850 ton/m! (l ton = 1 000 kg); o en términos
del peso unitario, el valor para el acero es 490 lbs/pie' ó 76.975 kN/m3• Por lo
general, se acepta la gravedad específica del acero como 7.85. La conversión de
las unidades fps de lb/pie a unidades SI de kN/IÍl y kg/m se obtiene como si-
gue.
Dados: lb/pie y se requiere convertirlas a:

lb . kg pie lb kg/rn: -:- x 0.4535924- x 3.2808- = 1.488164"""";" = kgy m pie lb m pie

kN/m: lb x 0.4535924 kg x 3.2808pie x 0.009806650 kN pie lb m kg
lb
0.0145939~ = = kN /m pie
• MPa, megapascal = I x l\<f N/m2.

<!-- p. 21 -->

Tabla 1·1 Datosde los perfiles de acero estructural

F'y Fultim. Espesor de placas y barras
Denominación
Tipo de la ASTM kip/ MPa kip/ MPa pulg mm Grupo' pulg2 pulg2
Carbono A-36 36 250 58-80 400-550 8 203 1 hasta 5 inclusive
Alta resistencia, A-242 40 275 60 415 ·4 a 8 102 a 203
aleación bajab A-440 42 290 63 435 1.5 a 4 38 a 102 4y5
A-441 46 315 67 460 0.75 a 1.5 19 a 38 3
50 345 70 485 0.75 19 1 Y2
e-tr1Alta resistencia, A-572 grado 42 42 290 60 415 hasta 6 hasta 152.4 1 hasta 5 inclusive
aleación baja grado 45 45 310 60 415 hasta 2 hasta 50.8 1 hasta 5 inclusive >o
\- Columbio-vanadio grado 50 50 345 65 450 hasta 2 hasta 50.8 1 hasta 4 inclusive tr1::o grado 55 55 380 70 4is hasta 1.5 hasta 38.1 1, 2, 3, y 4 hasta O
426 lb/pie (639 kg/m) oO
grado 60 60 415 75 520 hasta 1.25 hasta 31.8 1 Y2 ~
grado 65 65 450 80 550 hasta 1.25 hasta 31.8 1 O
\~
Alta resistencia, A-588 grado 42 42 290 63 435 5 a 8 127 a 203 - >--l baja aleación grado 46 46 315 67 460 4a5 102 a 127 - tr1
grado 50 50 345 70 485 hasta 4 hasta 102 1 hasta 5 inclusive ::o;;r-
tr1
'Véanse las tablas de datos de las secciones de acero (por ejemplo, tabla 1-1 ó V-l del Structura/ Stee/ Design Data de l.E Cf.l --lBowles). ::o
bPuede que sea difícil obtener el acero A-440, porque no es soldable,
c:o--le::o>r-
N...

<!-- p. 22 -->

22 CONSIDERACIONES GENERALES DE DISEÑO

Nótese que se han usado indistintamente en el sistema fps, la lb ma-
sa y la libra fuera debido a que la fuerza que produce la aceleración
es la fuerza de la gravedad. Esto no se puede hacer en el sistema SI,
puesto que el newton es una unidad derivada que define la fuerza
necesaria para acelerar l-kg masa 1 m/s-. La aceleración debida a
la gravedad es aproximadamente 9.807 m/s-,
Ejemplo: Dado un perfil estructural laminado que pesa 300 lb/pie (el
mayor de todos, W36).
Se requiere: masa/m y peso/m.
Solución: masa/m = kg/m = 1.488164(300) = 446.4 kg/m
peso/m = kN/m = 0.0145939(300) = 4.38 kN/m
El valor de la masa se usaría para hacer estimaciones de costos de
material y para solicitar las cantidades necesarias de la fábrica de acero. El
valor de peso se usa para calcular cargas, momentos flectores y esfuerzos.

1-4 PRODUCTOS DE ACERO

Los lingotes de acero de la refinación del arrabio se laminan para formar placas
de anchos y espesores .variables; diversos perfiles estructurales; barras redondas,
cuadradas y rectangulares; y tubos. La mayor parte del laminado se efectúa sobre
el acero en caliente, y el producto se llama "acero laminado en caliente". Algunas de las placas más delgadas se laminan o doblan aún más, después de
enfríadas, para hacer productos de acero laminados en frío o "formados en
frío" . En las siguientes secciones se describen varios de los perfiles más comunes.

1-4.1 Perfiles W

El perfil estructural que se usa con mayor frecuencia es el perfil de patín ancho.o
W. Este perfil es doblemente simétrico (tanto con respecto al eje de las x como para el eje de las y), que consiste en dos patines de forma rectangular conectados
por una placa de alma también rectangular. Las caras del patín son esencialmente
paralelas con la distancia interior entre patines para la mayoría de los grupos, con
una dimensión constante" .** Hay alguna variación debido al desgaste del rodillo
laminador y otros factores, pero la distancia se mantiene constante dentro de las
tolerancias de la ASTM. El perfil se produce como se ilustra en la figura 1-1.

La designación: W16 x 40 significa un peralte nominal total de 16 pulg y con un
peso de 40 lb/pie.
La designación: W410 x 59.5 es la misma W16 anterior con un peralte nominal
en mm (basado en elpromedio aproximado de los peraltes de todas las secciones
y redondeado hasta los más cercanos 5 mm) y con una masa de 59.5 kg/m.
\* Las varias secciones con peralte nominal constante. Cuando un grupo consiste en un gran número de secciones. se puede usar una segunda distancia interior al patín.
\** Puede haber diferencias considerables entre los peraltes nommares y los reales (N. del R.).

<!-- p. 23 -->

PRODUCTOS DE ACERO 23

\~----..¡.¡.-- Se varia esta distancia para controlar el espesor del alma

Figura 1-1 Método de laminación de un lingote de acero para producir un perfil W. Se ha de notar
Quela variación de los rodillos y la configuración de los mismos produce perfiles S. C. y de angulares.

Antes de 1978, cuando menos una sección W en la designación de un grupo tenía
"exactamente" el peralte nominal indicado ( o sea una W16 tenía un peralte de
16.00 pulg; una W18 tenía un peralte de 18.00 pulg). Ahora, la W16 más cercana
es la W16 x 40, con un peralte indicado de 16.01 (por ejemplo, la W21 varia de
20.66 a 22.06 pulg). Para la W14, el equivalente SI es W360, pero el intervalo real
es de 349 a 570 mm (en este caso, el "promedio" estaba muy lejos del valor nominal y la designación W360 se usó algo arbitrariamente).
Se debe notar que el producto laminado secontrae al enfriarse y con una tasa
variable que depende del espesor en cualquier punto de la sección transversal. Los
rodillos laminadores que se usan para producir los perfiles están sujetos a desgaste, lo que unido a las enormes fuerzas implicadas en el proceso de laminado, solamente dará lugar a la producción de perfiles nominales (que varían de los valores
teóricos o de diseño). La especificación A-6 de la American Society for Testing
and Materials (ASTM) da, en su Parte 4, tolerancias permisibles de laminado,
incluyendo la cantidad de alabeo en el patín y el alma y la desviación permisible
en el peralte del alma para que la sección sea satisfactoria. En general, la máxima variación permisible en el peralte, medida en el plano del alma es ± i pulg
ó 3 mm. Sin embargo, nótese que la diferencia permisible en el peralte de dos vigas laminadas con un peralte teórico de 16.01 puede producir peraltes extremos
de 15.8885 a 16.135 pulg o sea una diferencia de ¡ pulg ó 6 mm. Estas variaciones deben tenerse en cuenta, en particular al convertir a dimensiones SI para
el detallado, los espacios libres y el acoplamiento de las piezas.

1-4.2 Peñlles S

Son perfiles doblemente simétricos producidos de acuerdo con las dimensiones
adoptadas en 1896 y que se conocían anteriormente como vigas I o vigas American Standard. Hay tres diferencias esenciales entre los perfiles S y W:

<!-- p. 24 -->

24 CONSIDERACIONES GENERALES DE DISEÑO
[ L Perfil L Perfiles W Perfiles1S Perfiles CI
Sección de Viga American Canal Angular de
patín ancho Standard (Viga 1) lados iguales

c:::=::::J Rectangulares

\~ Cuadrados l T Perfil L Perfil T O Redondos
Angular de Te estructural,
lados desiguales cortado de un Barras
perfil W

Placa
Figura 1-2 Perfiles estructurales tal como son producidos directamente por los fabricantes de acero.

\1. El ancho del patín del perfil S es menor.
\2. La cara interna del patín tiene una pendiente de aproximadamente 16.70 •
\3. El peralte teórico es el mismo que el peralte nominal. Una viga S510 x 111.6
es un perfil con peralte nominal 510 mm x 111.6 kg/rn (S20 x 75).

1-4.3 Perfiles M

Son perfiles doblemente simétricos que no se clasifican como perfiles W o S. Existen unos 20 perfiles ligeros, clasificados como perfiles M. Un perfil M360 x 25.6
es el mayor de la clasificación M, y es una sección de peralte nominal de 360 mm y
una masa de 25.6 kg/m (M14 x 17.2).
1-4.4 Perfiles e

Son perfiles de carial, producidos de acuerdo con estándares dimensionales adoptados en 1896. La pendiente interna del patín es la misma que la de los perfiles S.
Estos canales se llamaban anteriormente canales Standard o American Standard.
Los peraltes teóricos y nominales son idénticos (lo mismo que para los perfiles
MC que se describen a continuación).
Un C150 x 19.3 es un perfil estándar de canal con un peralte nominal de 150
mm y una masa de 19.3 kg/m (C6 x 13).

1-4.5 Perfiles Me

Estos son perfiles en canal que no se clasifican como perfiles C. Se conocían como canales diversos o para construcción de barcos.

<!-- p. 25 -->

RESISTENCIA DEL ACERO 25

1-4.6 Perfiles L

Estos perfiles pueden ser angulares de lados iguales o desiguales. Todos los angu-
lares tienen paralelas las caras de los lados. Las dimensiones de los lados del angular pueden tener una variación de ± 1 mm en el ancho.
Un perfil L6 x 6 x ! es un angular de lados iguales con dimensión nominal de 6 pulg y un ,espesor 4 de ¡3 pulg.
Un perfil L89 x 76 x 12.7 es un angular de lados desiguales con dimensiones en sus lados de 89 y 76 mm respectivamente, y un espesor de 12.7 mm en
sus lados (L3 ~ x 3t).

1-4.7 Perfiles T

Las tes estructurales son miembros estructurales que se obtienen cortando perfiles
W (para WT), S (para ST), o M (para MT). Por lo general se hace el corte de tal
modo que se produce un perfil con área equivalente a la mitad del área de la sección original, pero a menudo se puede desplazar el corte cuando se requiere una
sección con mayor peralte. Las tablas publicadas con perfiles T se basan en cortes
simétricos. No se tiene en cuenta la pérdida de material debido al corte de la sección original, por aserrarniento o corte con soplete.
Un perfil WT205 x 29.8 es una te estructural con un peralte nominal de 205
mm y una masa de 29.8,kg/m, y se obtiene dividiendo la sección W410 x 59.5 (de
una sección W16 x 40).
En la figura 1-2 se muestran varios perfiles laminados estructurales.

1-~_M~~TENCIA DEL ACERO

En todo diseño de acero se tiene en consideración la resistencia de fluencia del
material. La resistencia de fluencia de diversos grados de acero que están disponibles para el diseño, se pueden ver en la Tabla 1-1. La resistencia defluencia es el
mínimo valor garantizado por el productor de acero y que se basa en el promedio
estadístico y la consideración del valor mínimo de fluencia obtenido mediante
gran número de pruebas. Así, para el acero A-36, el valor garantizado es F; = 36·
k/pulg- ó 250 MPa, pero el valor más probable será del orden de 43 a 48 k/pulg-
(300 a 330 MPa; véase las figuras 1-3a y 1-3b. De modo similar, un acero A-441,
con un punto de fluencia de 345 MPa, tendrá una resistencia de fluencia del orden
de 400 MPa. Conforme la fluencia garantizada aumenta hasta aproximadamente
450 MPa (65 k/pulg-) los valores real y garantizado, convergen.
Desde cerca de 1 900 a 1 960, el grado principal de acero disponible era elllamado A-7 con Fy = 33 k/pulg-. En 1954 se introdujo un grado A-373 para usar
con soldadura y Fy = 32 k/pulg-; esto fue la consecuencia de la mayor popularidad de la soldadura debido a las actividades en la construcción de buques en la
Segunda Guerra Mundial. Cuando se renueven edificios más antiguos, el inge-

<!-- p. 26 -->

26 CONSIDERACIONES GENERALES DE DISEÑO

550 5 50
500 Y1N 50 O Resist~cia (J1tim~ \<, 1-441 ~ V
450 4 50 ~ Niveldel ~f~~ esfuerzo ele
400 O tluencia--r-:-:-
\~6 Rango plástico _ I
Est ./- V~·esistencíal. u"1tima ..... A-36 'tt--y 350 50 m~ "- Pendiente d' I =
len-EII _ dee eíastícíelastí id a d , E teen= I - '" 300 ./ O :lE~ Nivel del I r \..Resistenciade tluencia
\~ 250 50 esfuerzo de tluencia
.E Est Rango inelástico
¡rJ 200 O
_ Rango elástico
150 15 :o
100 10O

50 5 O €y

O 00 0.04 0.08 0.12 0.16 0.20 0.24 0.28 0.32 O 4 8 12 16 20 24 28 32
Deformación, mm/mm o m/m Deformación. m/m x 10-3

Figura 1·30 Curvas típicas de esfuerzo-deforma- Figura 1·3b Ampliación de la parte inícial de la
ción para el acero estructural. curva de esfuerzo deformación para dos grados
de acero estructural. Nótese que el rango plástico
es del orden de 1O€y-

niero estructural puede ocuparse de incorporar los nuevos aceros a los antiguos
grados.
A partir de 1960 se han sustituido los grados de acero A-373 y A-7 por el acero A-36, que representa un 10 por ciento de aumento en la resistencia de fluencia
sobre el grado A-7. En los años treinta, se inició la producción de acero de alta resistencia y también resistente a la corrosión, yal que se designó como A-272 (está
descrito en la especificación A-272 de la ASTM). En 1959se escribió la especificación ASTM A-440, para otro acero de alta resistencia, aplicable a la construcción
con remaches y tornillos; en 1960se introdujo el acero A-441, aplicable a la construcción soldada. Todos estos tres aceros tienen un punto de fluencia que depende del espesor del metal, como se muestra en la tabla 1-1.
Desde cerca de 1964se han incorporado a las normas de la ASTM las especificaciones para varios otros aceros de alta resistencia (baja aleación); estos aceros
aparecen como A-572 y A-588. En la tabla 1-1se muestra que el acero descrito en
la especificación A-572 cubre varias resistencias de fluencia, llamadas grados, tales como los grados 42, 45, 50, 55, 60, Y 65 para el correspondiente esfuerzo
mínimo garantízado de fluencia en k/pulg-, En general, la resistencia de fluencia
de estos nuevos aceros también dependen del espesor, como se muestra en la tabla
bajo el encabezamiento "espesor de placas y barras". Los productores de acero
han clasificado los diversos perfiles W en cinco grupos, dependientes del espesor

<!-- p. 27 -->

EFECTOS DE LA TEMPERATURA EN EL ACERO 27

del patín (y como se muestran en las tablas 1-1, 1-2. V-I, y V-2)*, compatibles
con el grado del acero. El diseñador simplemente tiene que buscar en dichas
tablas para ver si está disponible el perfil en el grado que se requiere o se desea.
Por ejemplo, en el grado 450-MPa, sólo los perfiles del grupo 1, califican para el
espesor del patín. En el grupo 1, solamente se dispone de perfiles WI8 con valores
entre 35 y 60 lb/pie, inclusive (son las cinco secciones más pequeñas y con un máximo espesor de la pieza de 0.695 pulg).
La especificación ASTM A-588 permite Fy = 345 MPa para un acero de alta
resistencia y baja aleación cuyo espesor puede llegar hasta lOO mm (4 pulg). El
acero descrito en dicha especificación se usa principalmente para trabajos de soldadura y es resistente a la corrosión.
En términos de costo/unidad de masa, el acero A-36 es el más económico.
Los aceros de alta resistencia tienen su aplicación principal en aquellos casos donde los esfuerzos son principalmente de tensión. Las vigas de acero de alta resistencia pueden tener una deflexión excesiva, debido al módulo de sección reducido.
Las columnas de acero de alta resistencia pueden resultar menos económicas que
el acero A-36 si la relación de esbeltez (KL/r) es grande. Las trabes híbridas en
que se usa acero de alta resistencia en los patines, o las columnas armadas en que
se usa acero de alta resistencia puede que suministren mejores soluciones en los
casos en que se restrinjan las dimensiones de los miembros. En un caso determinado, es necesario efectuar un análisis económico y de disponibilidad para determinar si es apropiado usar acero de alta resistencia.

1-6 EF_ECTOSPE LAJ'EMIlERATURA EN EL ACERO

1-6.1 Efectos de las altas temperaturas

El acero no es un material inflamable; sin embargo, la resistencia depende en alto
grado de la temperatura, como se ilustra en la figura 1-4. A 1 Ooo°F,la resistencia
tanto de fluencia comode tensión es alrededor del 60 a 70 por ciento de la obtenida a la temperatura ambiente (alrededor de 70°F). La pérdida de resistencia es
bastante notable a altas temperaturas, como se muestra en la figura, donde se ve
que la resistencia a 1 600°F es sólo el15 por ciento de la resistencia a la temperatura ambiente. Las estructuras de acero que encierren materiales inflamables requerirán protección contra incendios para controlar la temperatura del metal el
tiempo suficiente para que los ocupantes lleguen a un lugar seguro o para que
el fuego consuma los materiales combustibles o que se pueda apagar antes de que el
edificio se desplome. En muchos casos, el edificio no llega a desplomarse, aun a
altas temperaturas; más bien, la deformación de los miembros sobrecalentados es
demasiado grande para ser aceptable y dichos miembros deben ser removidos.

\* Véase la nota a al pie de la tabla 1-1, en J. E. Bowles, Structural Steel Design Data Manual,
McGraw-HiII, Nueva York, 1980.

<!-- p. 28 -->

28 CONSIDERACIONES GENERALES DE DISEÑO

Oc X 100
1.2 O 2 3 4 5 6 7 8 9 10 11 12
I I I
¡..-- Rango de valores ,;,; --..... 1', ,;
1.0 , ,"""~ ~ .....
\~y ,, "" ~\.\
\

FUII \ 0.2 J\r, ...........
\~~r-s-
2 4 6 8 lO 12 14 16 18 20 22
Temperatura. °F X lOO

Figura 1-4 Efecto de las temperaturas elevadas ya sea sobre la fiuencia o la resistencia última a ten-
sión, expresado como una relación de la resistencia a la temperatura ambiente de aproximadamente
70°F.

Se han establecido clasificaciones de protección contra incendios para los diversos materiales y espesores que se pueden aplicar a un miembro estructural para
controlar la temperatura. Se incluyen productos a base de yeso, o concreto ligero
que se puede rociar sobre el miembro (véase la figura 1-5) o tableros aislantes de
fibra para proteger el acero. Cuando el miembro de acero sea hueco, se puede
proveer un líquido con un agente anticongelante, para el control de las altas temperaturas. La clasificación de incendios se basa en el número de horas que le toma
al acero alcanzar una temperatura promedio de 540 a 650°C para el espesor dado
de material de protección contra incendios, utilizando un procedimiento estándar de prueba según viene dado por la ASTM E-119 (en la Parte 18). Una clasificación de incendio de 2 horas, que se usa comúnmente, indica que tarda 2 horas
que la temperatura del acero alcance el nivel indicado por la prueba estándar. Las
primas de seguros se basan en la clasificación en horas del incendio y son menores
para las clasificaciones más altas del íncendio.idebido a la reducida probabilidad
de que el incendio pueda producir daños críticos.

1-6.2 Efectos de las bajas temperaturas

La fractura frágil a menudo se asocia con las bajas temperaturas. Básicamente, la
fractura frágil ocurre sin que haya fluencia del materíal. Las curvas de esfuerzodeformación de la figura 1-3 indican que en la falla usual de un espécimen a tensión, tiene lugar una considerable elongación. De hecho, en la prueba estándar a

<!-- p. 29 -->

EFECTOS DE LA TEMPERATURA EN EL ACERO 29

a) b) el

Materiales de protección Peso unitario
contra el fuego pcf Ib/pie3
Concreto de cenizas 110 17.3
Tableros de yeso 30-40 4.7-6.3
Mortero, cemento y arena 100 15.7
Concreto de pizarra expandida
Vermiculita 80-105 12.6-16;5
Perlita 30-35 4.7-5.5

Por lo general se debe usar 35 mm de protección contra el fuego para un
fuego de 2 hr; obténganse los valores especificos de espesor ya sea me-
d) diante pruebas o de los productores del yeso, perlita, etc.

Figura 1-5 Métodos para obtener la resistencia a los incendios de los miembros estructurales de acero.
a) Fibras rociadas. b) Listones y yeso. e) Concreto ligero (colado). el) Tableros de yeso -se usan
los tableros para aumentar el espesor. e) Detalle del material aislante, rociado en una esquina. El espesor aumenta mediante varias rociadas. j) Detalle del material aislante rociado sobre la viga.

tensión de la ASTM, se especifica un por ciento mínimo de elongación para el
acero. En el diseño del acero está implícita la deformación resultante (fluencia)
del material bajo un alto esfuerzo local. Cuando el material sufre elongación, las
dimensiones laterales se contraen, debido al efecto de Poisson. Si las dimensiones

<!-- p. 30 -->

30 CONSIDERACIONES GENERALES DE DISEÑO

Temperatura, Oc
\-275 -250 -225 -200 -175 -150 -125 -100 -50 O
1 1 I I J ISO 30
\~--.--: /
F: /
".......::!.!............"" ~ / '3 ~---- ¡~ -....., e-c -e- / -'" \00 20 .~
¿ ~ ·0.¡;; ..- ),(, ~

'O El ........, " ......... ~ '".s )\<; o
.~u u5 /' l / \<, 1;; 50 O \<,! ,/ ~
'bt\ 1--'/
\~\Ot\~'''''
........ --r-1---I 1 1 I I 1 I
_300 0 200 0
Temperatura. °F

Figura 1-6 Efecto de la baja temperatura en la fluencia y resistencia última a tensión y en la elongación de un espécimen.

laterales están total, o hasta parcialmente restringidas, el acero se separará sin de-
sarrollar totalmente su potencial de fluencia. Este tipo de falla constituye lo que se
conoce como "fractura frágil". En la figura 1-6 se muestra que la elongación disminuye en todo caso con la baja temperatura. En la figura 1-7 se ilustra el efecto de
concentración de esfuerzos que ocurre en una muesca -siendo una muesca cual-

T

Fresando para obtener una transición suave hasta las
dimensiones de la muesca, elimina la zona rayada y
\ Contracción durante I permite que el área de muesca se "estreche" a tensión
\ el estrechanúento I
\ I
\ I

T
Figura 1·7 Una barra muescada a tensión. La sección muescada tiende a contraerse bajo tensión, como se muestra por los semicírculos punteados, yes resistida por las zonas sombreadas, lo que equivale
a la aplicación de una fuerza lateral.

<!-- p. 31 -->

CODIGOS DE DISEÑO ESTRUCTURAL 31

quier cambio abrupto en el área de la sección transversal- para inhibir la
contracción lateral en una situación de tensión.
Una combinación de baja temperatura, un cambio en las dimensiones de la
sección (efecto de muesca) o alguna imperfección, junto con la presencia de esfuerzos de tensión, pueden iniciar una fractura frágil. Esto puede empezar como
una grieta que se desarrolla hasta constituir la falla de un miembro. No todos los
miembros que presentan muescas en un ambiente de baja temperatura y sometido
a una alta tasa de deformación por tensión fallan; tiene que haber exactamente la
combinación apropiada de deformación y tasa de deformación, temperatura y
efecto de muesca. Sin embargo, si ocurriese una falla catastrófica, el hecho de
que haya muy poca probabilidad de que ocurra la combinación para la falla, ayudará bien poco para ajustar las demandas por daños que resultan de la falla y que
es más que de seguro que se presentarán. La fractura frágil se puede controlar de
varias maneras:

l. Detállense los miembros y sus conexiones a fin de hacer mínimas las con-
centraciones de esfuerzos.
\2. Especifiquese la secuencia de fabricación y montaje para minimizar los efec-
tos residuales de tensión.
\3. Usense aceros que tengan aleaciones especiales para emplearlos en ambientes
de baja temperatura (véase ASTM A-633).
\4. Aplíquese un esfuerzo de pretensión preferiblemente a una temperatura eleva-
da, o si no a temperatura normal a la zona de la muesca para generar una
fluencia local antes de que se presenten las cargas de servicioy por temperatura.
\5. Si fuera posible, rebáiese (o púlase) la muesca para obtener una transición
suave.
\6. Redúzcase la tasa de aplicación de la deformación a tensión.

1-7 CODIGOS DE DISEÑO ESTRUCTURAL

Las oficinas loceles de construcción casi siempre requieren que los diseños estructurales que pertenecen a su jurisdicción se diseñen de acuerdo con algún código.
Las ciudades principales -Nueva York, Atlanta, Chicago, San Francisco y
otras- tienen sus propios códigos (por ejemplo, Chicago Building Code, New
York BuildingCode, etc.). Las ciudades más pequeñas usan por lo general uno de
los varios códigos nacionales o regionales cuya lista se dará más adelante. Las diversas dependencias estatales de transporte (oficinas de carreteras) usan por lo regular las especificaciones presentadas por la AASHTO, que también están en la
lista. Los diversos ferrocarriles usan generalmente las especificaciones establecidas por la AREA, también en la lista.
El diseñador estructural que prepare diseños para obras en carreteras o
ferrocarriles debe seguir estrictamente las especificaciones de diseño de estas
publicaciones, en particular si el gobierno federal interviene en parte del financiamiento.

<!-- p. 32 -->

32 CONSIDERACIONES GENERALES DE DISENO

De modo similar, el diseñador que se ocupe de la ingeniería estructural tiene
que apegarse estrictamente a los requerimientos mínimos de diseño del código
apropiado de construcción y las especificaciones del cuerpo local de control. Los
requisitos especiales del propietario o el cliente puede que requieran un diseño
más estricto que el que establecerían los criterios del código de construcción. Sólo
en casos contados podrá el diseñador obtener permiso del organismo local de
control para desviarse del código de manera menos conservativa. Estas variaciones por lo general requieren mucha documentación y la presentación de
consultores adicionales para obtener la aprobación. Hay cosas buenas y malas,
asociadas con este aspecto del diseño estructural. Por una parte, a veces lleva
tiempo considerable obtener la aprobación de nuevos métodos y materiales; por
otra parte, tiene sus ventajas "el no ir demasiado rápido". Si se sigue cuidadosamente el código local de construcción y se cumple con los requerimientos
mínimos de diseño, o se sobrepasan, y resultase a pesar de todo una catástrofe,
hay siempre la prueba de que se han seguido las buenas prácticas de la ingeniería.
Finalmente, se supone que los códigos de construcción reflejan aquella parte de
las prácticas estructurales que resultan ser únicas para dicha localidad, como son
las temperaturas, sismos, la cantidad de nieve y lluvia, profundidad a que llegan
las heladas, y las velocidades promedio del viento.
En la siguiente lista hay varios códigos de díseño y/o especificaciones, que
puede que los diseñadores se vean en la necesidad .de usar:
National Building Code, publicado por la American Insurance Association, 85
John Street, Nueva York, N.Y. 10038; ellos mismos pueden proporcionarlo.
Uniform Building Code, del International Conference of Building Officials y
5360 South Workman Mill Road, Whittier, California 90601.
Basic Building Code, Building Officials and Code Administrators International
1313 East 60th Street, Chicago, Illinois 60637 (anteriormente BOCA). Ame-
rican National Standards Institute (ANSI), Minimun Design Loads in Buil-
dings and Other Structures, ANSI 58-1, 1430 Broadway, Nueva York, N.Y.
\10018.
American Institute of Steel Construction (Especificaciones, Steel Construction
Manual, 8a. ed. (1979), 101 Park Avenue, Nueva York, N.Y. 10017. Ameri-
can Welding Society (AWS), Structural Welding Code, 2501 N.W., 7th;
Street, Miami, Florida 33125.
American Iron and Steel Institute (AISI), 1 000 Sixteenth Street, Washington,
D. C. 20036. Publica varias especificaciones para el uso de los productos de
hierro y acero.
American Association of State Highway and Transportation Officials (AASHTO),
Specificationsfor Highway Bridges, 341 National Press Building, Washing-
ton, D. C. 20004.
American Railway Engineering Association (AREA), Specificaüons jor Steel
Railways Bridges, 59 East Van Buren Street, Chicago, Illinois 60605.
En todos los códigos nacionales y urbanos se usan normas de especificaciones como aplicables por las organizaciones que las redactan, como son la

<!-- p. 33 -->

CARGAS DE CONSTRUCCION 33

AWS, AISC, y AISI, para los metales, y otras agencias apropiadas para los otros
materiales de construcción.
Organizaciones como la AISI y la AISC, así como los productores de acero,
proporcionan tablas de datos de diseño para perfiles estructurales, así como datos
de otros productos de acero, como placas, barras, alambre, y tornillos. Algunos de estos datos, junto con especificaciones extractadas de la AISC, AASHTO y
AREA, han sido incluídas por el autor en su manual Structura/ Stee/ Design Data
(SSDD), publicado por McGraw-Hill Company, y que usa como suplemento de
este texto. Este manual se desarrolló de manera tal que el lector dispone de ambos
tipos de unidades, pfs y SI.

1-8 CARGAS DE CONSTRUCCION

En el diseño de un edificio es necesario determinar las cargas que ha de soportar
el esqueleto o estructura del edificio. Estas cargas se dividen en cargas muertas y
cargas vivas. Se hace esta distinción ya que la estructura y la cimentación deben
siempre soportar las cargas muertas, las cargas debidas al peso propio de las varias componentes del edificio y que incluyen el peso de la estructura. Entre las
cargas muertas típicas se incluyen:

Materiales de piso y techo, incluyendo las viguetas de piso y techo (vigas).
Materiales del plafón, que incluyen la red de conductos para el control ambien- .. tal y el suministro de fuerza.
Muros exteriores soportados por la estructura, incluyendo ventanas, puertas, y
balcones.
Muros interiores que están permanentemente colocados.
Equipos mecánicos (calefacción, aire acondicionado, ventilación, y eléctricos
(tales como elevadores, con su jaula, cables y motores).
Protección contra incendios.
Vigas, trabes y columnas, incluyendo las cimentaciones que constituyen la estruc-
tura del edificio.

Es evidente de esta lista que cualquier parte del edificio que esté permanentemente instalada contribuye a la carga muerta total. Las cargas muertas se pueden
establecer de manera bastante razonable después de que se hayan fijado los elementos del edificio, usando los perfiles geométricos y las tablas de pesos unitarios
de los materiales de construcción; como ejemplo se tiene la tabla IV-3.* .
Las cargas vivas son cualesquiera cargas que ha de soportar la componente
del edificio y que se considere como algo transitoria. Esto es, la carga se puede
aplicar por varias horas hasta varios años, pero su magnitud es variable. Los có-

• En el Structural Steel Design Manual Data (SSDD). Cualesquiera tablas a las que se haga referencia de ahora en adelante, serán de este manual, a menos que sea evidente de que están contenidas
en el texto.

<!-- p. 34 -->

34 CONSIDERACIONES GENERALES DE DISEÑO

digos de construcción acostumbran prescribir las cargas vivas basándose en
quiénes ocupan los edificios y su situación, y entre las que incluyen las cargas de
viento, nieve y sísmicas. Además de estas últimas, las cargas vivas incluyen:

Las personas como en los auditorios, salas de reunión y aulas.
Canceles movibles en las habitaciones.
Equipos de oficina y máquinas de producción, si es que se mueven ocasionalmente.
Productos de los almacenes.
Muebles.

Los valores de las cargas vivas que dan los códigos deconstrucción, por lo general se basan en valores estadísticamente conservativos, y aunque el diseñador
puede pedir a la oficina local de construcción que se le permita variar el código,
esto se debe hacer sólo después de haber evaluado cuidadosamente los valores
propuestos. En la tabla IV-4 se proporcionan valores típicos de la carga viva, basándose en el uso de la estructura, como se hallan en diversos códigos de construcción. Las cargas se dan como fuerza/área como una conveniencia para el cálculo y el diseño, y también debido a que se desconoce la geometría actual del plan
del edificio.
La mayoría de los códigos permiten una reducción de los valores tabulados
de las cargas vivas, cuando el área que contribuye es muy grande, debido a la probabilidad estadística que toda el área no esté cargada al máximo. Por lo común,*
la reducción será el menor de los siguientes factores:
pie lb s. R= 0.0008 X área (cuando el área > 150 pies-)
SI: R = 0.0086 x área (área> 11.2 m2)
D+L
R = 4.33L (1-1)
R \< O60 (algunos códigos limitan R ::; 0.40 para miembros horizontales, co-
\-' mo son las vigas y trabes, y R ::; 0.60 para miembros verticales).

donde R factor de reducción, usado como (1 - R) X Ltabla
D carga muerta, lb/piel ó kPa (kilonewtons/m)
L carga viva, lb/piel, kPa, pero L se limita a un valor menor de 100
lb/pie- ó 5 kPa; por lo general, los valores más altos que este límite
no se reducen

No se permiten reducciones en la carga viva para los usos siguientes: salones de
reuniones públicas (como auditorios), cocheras y techos.
Es preciso determinar la estructura de tal modo que se pueda efectuar el flujo
de carga, para obtener el área tributaria de carga a cualquier miembro.

\* Según viene dada en los varios códigos nacionales de construcción, citados antes.

<!-- p. 35 -->

CARGAS DE CONSTRUCCION 35

Ejemplo 1-1 En la figura. El-l se muestra una porción de la planta de piso
de un edificio de oficinas (de muchos pisos). El piso es de 4 pulg de concreto
sobre un tablero metálico colocado encima de viguetas de acero, de celosía.
¿Cuál será 'la carga viva reducida para las vigas de piso y para una columna
exterior situada tres pisos más abajo del piso más alto?

\~ A 1 D 1- _?Exterior
T t==-==-t~_t_ ± -±__+ :f==~=--:.1=- E I - =1-=-" - r= F-=-t
\~~~~ior~f"··~-=l=*=É~íI- 18
18 ./-Vigas del PisO--'¡ H t GT - ,--1 1
\- l--L-l~I-
f---22' 'l' 22' 'l' 22-----1
Figura EI-I

SOLUCION Estímese la carga muerta sobre el área tributaria del piso
(centrada sobre el miembro), como:

Piso de concreto y su terminación: 4 X 144/12=48Ib/pie2
Plafón, tablero metálico, viguetas de celosía = 12 lb/pie?
de acero: Total =60Ib/pie2

La carga viva para oficinas, obtenida de la tabla IV-4 (SSDD) = 80Ib/pie2.
Calcúlese R para la viga de piso; el área tributaria es, como se muestra en la
figura El-l, 18 x 22 (área ABCD):
R = 0.0008(18 X 22) = 0.32 \< 0.60
D+L 60+80
R = 4.33L = 4.33(80) = 0.40 \< 0.60

Se usará el menor de los valores calculados de R, 0.32. La carga viva reducida L' será
L' = (l - 0.32)80 = 54.4, o sea 55 lb/pie-

Calcúlese R para la columna; el área tributaria de 9 x 22 (AEFD) está
centrada en la columna; pero se tiene que, para la acumulación de tres pisos
R = 0.0008(3 X 9 x 22) = 0.475 \< 0.60 Correcto
60 + 80
R = 4.33(80) = 0.40 \< 0.60

<!-- p. 36 -->

36 CONSIDERACIONES GENERALES DE DISEÑO

Usando el valor menor de R, 0.40, la carga viva reducida, sobre la columna es

L' = (1 - 0.4) x 80 = 48 lb/pulg-

Se notará que 0.40 es el R máximo para la columna y que es mucho menor en
el más alto nivel de piso.

Ejemplo 1-2. Un salón de reuniones y banquetes de un hotel tiene una planta
de piso de 22 x 27m. El piso está compuesto de 125mm de concreto colado
sobre un tablero metálico y con un recubrimiento de mosaicos (refiérase a la
figura El-2). ¿Cuál será la carga viva reducida sobre la viga de piso C2,
usando una reducción que no sea mayor de 40O¡o?

_:¡;A B :¡;e :¡;D
Viguetas 1I I IT -I I II 1-tD 2 A2 tv~ -I 1'-I 31 9r+7 I I I -I I I :r-L f-7 12 8--.1 .,- .,-
Figura El-2

SOLUCION Nótese que un salón de uso público no es lo mismo que un
auditorio, donde la carga descansa principalmente sobre asientos fijos o mo-
vibles. Se puede usar con esta definición un factor de reducción de carga viva.
Estímese primero la carga muerta usando la tabla IV-3 del SSDD para
obtener el peso unitario del concreto = 23.5 kN/m3•

Peso del concreto: 0.25 x 23.5 2.940 kPa
Mosaico de 10 mm 0.188 kPa
Tablero de acero, plafón, viguetas (presión estimada) 0.575 kPa

Total 3.703 kPa
De la tabla IV-4, la carga viva = 5.00 kPa. El factor de reducción para
una trabe basada en el área tributaria mostrada es
R = 0.0086[(12 + 8)/2 x 9] = 0.774 > 0.40 (y además 0.60)
R = D + L = 3.703 + 5.00 = 0.402 \< 0.60
4.33L 4.33(5.00)

<!-- p. 37 -->

CARGAS DE CONSTRUCCION 37

Como el planteamiento del problema limita la reducción de la carga viva
a no más de 0.40, la carga viva reducida es
L' = (1 - OA) x 5.00 = 3.00 kPa III

1-8.1 Cargas de viento

Las cargas de viento se han estudiado ampliamente en años recientes, particularmente para las grandes estructuras de muchos pisos. Por lo general, para estructuras elevadas, se deben efectuar estudios en los túneles de viento, para determinar las fuerzas del viento sobre la estructura. Para estructuras más pequeñas de
forma regular con alturas del orden de los 100 pies o unos 30 m, resulta satisfactorio usar la presión del viento estipulada en el código apropiado de construcción.
El National Building Code (NBC) para el viento es como sigue:

Altura Presión del viento

pies m pie lb s, lb/pie- SI, lePll

\< 30 \<9 15 0.75
30 a 49 9.1 a 14.9 20 1.0
50 a 99 15 a 30 25 1.25
100 a 499 30.1 a 150 30 1.50

Los tanques, chimeneas, y estructuras similares deben resistir esta presión multiplicada por los siguientes factores:

Forma de la estructura Factor

Rectangular o cuadrada 1.00
Hexagonal u octagonal 0.80
Redonda o elíptica 0.60

Comúnmente no se tiene en cuenta el efecto de protección de las estructuras
adyacentes o del terreno.
Para obtener la presión de viento según el NBC, se mide la altura del edificio, desde la base del mismo y por encima del nivel promedio del terreno.
En general, la presión del viento se calcula entre los niveles de piso y se
prorratea a los pisos adyacentes usando la teoría simple de las vigas si la distancia
vertical, comparada con la distancia lateral a las columnas adyacentes, es lo suficientemente pequeña para poder suponer una acción flectora en "una sola dirección". Esta suposición no produce un momentoflector debido a la presión del
viento a lo largo de la columna. Cuando el espaciamiento entre columnas es pequeño comparado con la altura, se puede aplicar la presión del viento como una

<!-- p. 38 -->

38 CONSIDERACIONES GENERALES DE DISEÑO

carga uniforme sobre la columna y que produce un momento de viento de WL2/8
(si se la considera como una viga simple).
Se considerarán los efectos aerodinámicos cuando el viento se aplique contra
edificios con techos en pendiente. Para pendientes de techo menores de 30° (que
incluyen los techos planos) la presión del viento sobre el techo que indica el NBC,
es una succión que actúa hacia afuera, normal a la superficie del techo, con un valor de 1.25 x la presión previamente recomendada.
La carga de viento sobre techos con pendientes mayores de 30° se obtiene de
la presión del viento que actúa normalmente a la superficie del techo, y donde el
valor básico previamente indicado dependerá de la altura. La altura para determinar la presión sobre el techo se mide como la diferencia entre las elevaciones promedio del terreno y el techo.
Se hace notar que debido a que el viento puede soplar desde cualquiera de los
lados de un edificio, la estructura es simétrica, aunque el análisis del viento se
efectúa desde una sola dirección.

Ejemplo 1-3. Dado el techo de dos aguas que se muestra en la figura El-3a,
y usando la presión de viento del NBC, ¿cuáles serán las fuerzas laterales y
sobre el techo debido al viento que sopla de la izquierda?

't>
\~~ T LJS
sl~t 10
bN
Marco
\~ bN c~t .oE
::J
U Marco
o ~ II ::J bN ::J
\~ 00ál
...l ...l

l- ~ ~I"
Planta Figura EI·3a

<!-- p. 39 -->

CARGAS DE CONSTRUCCION 39

SOLUCIONo Con una columna de 22 pies, se supondrá flexión en la misma,
pero aun así se tendrán esfuerzos cortantes en el alero y la cimentación, como se muestra en la figura El-3b.
Altura promedio = 22 + 7.5 = 29.5 pies.
Presión del viento para esta altura = 15 lb/piel = 0.015 k/pie-

Viento en la columna de barlovento = P = (2J )(20)(0.015)
\= 3.3 kips en la línea de techo yen la cimentación

El viento sobre el techo se aplica en las puntas de los largueros, como se indica en la figura. La distancia en pendiente se calcula fácilmente y es igual a
33.54 pies. Dividiéndola en seis partes, se obtienen 5.59 pies.

Figura El-3b
En el punto 1, el viento es 5.59(20)(0.015 x 1.25) = 2.097 kips (pendiente del techo \< 30°). Esta fuerza se descompone en componentes horizontales y verticales:

_1_ (2.097) = 0.94 kip
V5

<!-- p. 40 -->

40 CONSIDERACIONES GENERALES DE DISEÑO

_2_ (2.097) = 1.88 kips
v'5
En los puntos 2 y 3 el área de viento tributaria es 2(5.59) = 11.18 pies.
Las componentes de viento son 3.75 Y 1.88 kips.
En el punto 4 la carga de viento es también 3.75 pero las componentes
horizontales se cancelan.
Los varios valores del viento se muestran en la figura EI-3b. La exposi-
ción de los datos es conveniente para la programación por computadora de
los esfuerzos del marco, usando el programa de computadora descrito en el
capítulo 2.
Las presiones del viento se pueden calcular aproximadamente como

q = 0.00256 V 2 (lb/piel) (1-2)
q = 0.0000473 V 2 (kPa) (l-2a)

donde V está en milh o km/h. Esta ecuación se puede deducir fácilmente como
q =1mo",donde la densidad de masa del aire es aproximadamente 0.00238 lb o
s2/pie4.
Como el viento es una carga transitoria, los códigos de construcción por lo
general permiten un aumento de un tercio en los esfuerzos permisibles de diseño
con el viento incluido como parte de las condiciones de carga, siempre que la sección requerida no se menor que la que se requeriría para la condición de carga
de carga muerta + carga viva solamente. Por ejemplo, si se permite un esfuerzo de
20 k/pulg-, entonces, con las condiciones de carga de viento, se podría usar un esfuerzo de 20 x 1.33 = 26.6 k/pulg-.

1-8.2 Cargas de nieve

Las cargas de nieve son cargas vivas que actúan sobre los techos. La carga de
nieve y cualesquiera otras cargas vivas se toman con respecto a la proyección ho-

Carga de nieve y otras cargas vivas

Se muestra una mitad del techo t

Figura 1-8 Carga de nieve y otras cargas de lecho, vivas y muertas.

<!-- p. 41 -->

CARGAS DE CONSTRUCCION 41

Las cargas de nieve sobre el terreno que aquí se muestran,provienen de datos reportados por la "Distribution of E22:3 Se le debe dar especial consideración a aquellas regiones
Maximum Annnal Water Equivalent of Snow 00 the donde no se muestran cargas de diseño. y donde pudiesen
Ground", aparecida en la Monthly Wearher Review, Vol. 94, ocurrir acumulaciones de nieve extremadamente altas.
No. 4, 1966, publicada por el U.S. Weather Bureau. Todavía no se conoce en su totalidad la variación de las
cargas de nieve sobre el terreno, con la elevación y la
Se pueden tomar las cargas básicas de techo como el SOpor exposición, y las diferencias locales en las regiones
ciento de la carga de nieve sobre el terreno. montañosas son por lo general muy significativas.
Las cargas de nieve sobre el terreno. que se muestran en este
mapa. se han de usar en lugares donde no haya un código de
construcción que establezca los requerimientos de la carga de
nieve, y no han de sustituir a los requerimientos de los códigos
estatales o locales.

Figura 1-9 Carga de nieve sobre el terreno, en lb/pie/, para un intervalo de recurrencia de 50 años.
(Según el Uniform Building Code, 1976).

rizontal del techo, como se ilustra en la figura 1-8. En la figura 1-9se presenta un
mapa donde se muestran las cargas de nieve que se pueden usar en ausencia de requerimientos específicos de carga en los códigos de construcción. Aun en áreas
donde las cargas de nieve sean mínimas, se debe usar una carga viva de techo
mínima. El NBC estipula que se use la mayor de las cargas de nieveo 20 Ib/pie2 ó
1.0 kPa. Como 10 pulg de nieve son aproximadamente iguales a 1 pulg de agua,
una carga de nieve de 20 lb/pie- corresponde a una profundidad de nieve sobre el
techo de casi 40 pulg -valor que es fácil obtener donde ocurran ventiscas. Sin
embargo, cuando la lluvia caiga más tarde sobre la nieve, la nieve saturada pesa
considerablemente más y el peso unitario puede aproximarse al del agua.

1-8.3 Otras cargas de construcción

Además de los tipos indicados de cargas de presión o área, los códigos de construcción pueden estipular la investigación de cualquier carga concentrada de algu-

<!-- p. 42 -->

42 CONSIDERACIONES GENERALES DE DISEÑO

na magnitud que se puede colocar en cualquier lugar del piso o del techo. Donde
se usen los techos como áreas de recreo o terrazas para tomar el sol, las cargas vivas se deben ajustar a valores basados en la ocupación, además de considerar la
nieve y/o el viento.
El encharcamiento es una carga especial de techo que puede que requiera in-
vestigación. Es una condición en la que el agua se acumula en un techo plano que
tiene una deflexión local (tal vez debido a una sobrecarga, mala construcción,
asentamiento de las cimentaciones, o un drenaje de techo tapiado), que es causa
de una concentración de agua, la que a su vez aumenta la carga y la deflexión, con
una concentración adicional de agua. Si se toma nota de que una profundidad de
agua de 1 pulg produce una presión por carga viva de 5.21b/pie2, se pueden de-
sarrollar cargas que hacen que fallen localmente algunos miembros del techo. A
través de fallas sucesivas, todo el techo se podrá desplomar. Los diseños por
encharcamiento han sido considerados con algún detalle por Marino en el AISC
Engineering Journa/ de julio de 1966.
Las cargas de montaje no se consideran directamente en los códigos de cons-
trucción. Dichas cargas pueden controlar el diseño de algunos miembros, particularmente en edificios de mucha altura, puentes en voladizo, o estructuras sostenidas por cables. El ingeniero responsable de cualquier fase del montaje puede ser
considerado legalmente responsable de una falla estructural durante la erección.
La mayoría de las fallas estructurales (cuando menos las que se reportan) tienden
a ocurrir durante la erección más bien que posteriormente. Los métodos de erección así como el equipo varían según el proyecto; por consiguiente, en los libros
de texto no resulta práctico hacer otra cosa que poner de relieve esta muy impor-
tante sección del diseño. El ingeniero debe determinar qué equipo se usará, dónde
se ha de colocar, las cargas que se han de levantar, las cantidades de materiales, y
los lugares donde se depositarán, a fin de que se pueda revisar la resistencia de los
miembros estructurales individuales afectados, usando los principios de la estáti-
ca y los procedimientos de diseño contenidos en los últimos capítulos sobre diseño.

1-9 CARGAS SOBRE LOS PUENTES DE CARRETERA Y
FERROCARRIL

La American Association of Highway and Transportation Officials (AASHTO)
ha diseñado cargas estándar para puentes, como se muestra en la figura 1-10. En ge-
neral, la carga estándar de camión produce los valores mayores de momento flector para claros de puente hasta cerca de 60 pies para los camiones H y hasta 145
pies para los HS. El momento flector se puede calcular fácilmente refiriéndose a
la figura 1-10. El cortante máximo se obtiene ya sea con una carga de rueda o con la
carga concentrada de carril en una reacción. Para los camiones HS y las .longitudes de claros, los cortantes son como sigue:

<!-- p. 43 -->

CARGAS SOBRE LOS PUENTES DE CARRETERA Y FERROCARRIL 43

Claro del puente Efecto debido al camión HS·

33.8 a 145.6 pies M . = [(0.9L + 4.206)(0.5L + 2.33) - 11.2Ll pie- kips max WL
W 10.3 a 44.38 m M máx= T[(0.9L + 1.282)(0.5L + 0.71) - 3.4ILl kN . m
28 a 127.5 pies Vmáx = w( L - L16.8 + 0.8) kips (carga de camión)
8.53 a 38.86 m Vmáx= w( L ~5.I + 0.8) kN (carga de camión)
Más de 127.5 pies Vmáj¡= V + ~L kips (carga por carril de tráfico)
Más de 38.86 pies Vmáx= V + ~L kN (carga por carril de tráfico)

aW = 40, 30, Y20 kips o su equivalente en kN (y es la carga básica del camión, no
la total).

Se diseñan los puentes de ferrocarril basándose en las cargas vivas discurridas por Theodore Cooper (aproximadamente en el afio 1890), un ingeniero de
ferrocarriles, y que se conocen como las "cargas de Cooper". La carga consiste
en dos locomotoras "típicas" de ferrocarril que tiran de una hilera de carros.

Tabla 1-2 Momentos, cortantes, y reacciones de las vigas de piso para la
carga Cooper E-SO"

Rueda no 3 4 6 8 9 10 11 12 13 14 15 16 17 18

Espaciamiento en
las ruedas, pies 9 6 8 8 9 6
Carga total en los
ejes del tren:
Pies:
Ft:

Momento Momento en Cortante, Reacción en la pila Claro, máximo, punto cuarto, kips o en la viga de pies
pies-kips pies-kips En el ex- cuarto Centro piso, kips
tremo
5 50.0 37.5 40.0 30.0 20.0 40.0
6 60.0 45.0 46.9 30.0 20.0 53.3
7 70.0 55.0 51.4 31.4 20.0 62,9
8 80.0 70.0 55.0 35.0 20.0 70.0
9 90.0 85.0 57.6 37.8 20.0 75.6
10 112.5 100.0 60.0 40.0 20.0 80.0
11 131.8 115.0 65.5 41.8 21.8 87.3
12 160.0 130.0 70.0 43.3 23.3 93.3
13 190.0 145.0 73.8 44.6 24.6 98.5
14 220.0 165.0 77.1 47.1 25.7 104.3

<!-- p. 44 -->

44 CONSIDERACIONES GENERALES DE DISEÑO

Tabla 1·2 (Continuación)
Momento Momento Cortante, Reacción en la pila Claro, máximo en punto kips o en la viga de piso, pies pies· kips cuarto, En el Punto Centro kips
pies' kips extremo cuarto
15 250.0 188.0 80.0 49.8 26.6 109.2
16 280.0 210.0 85.0 52.5 27.5 113.7
18 340.0 255.0 93.3 56.7 28.9 121.3
20 412.5 300.0 100.0 60.0 28.7 131.1
24 570.4 420.0 110.8 70.0 31.8 147.9
28 731.0 555.0 120.9 77.1 34.3 164.6
30 820.8 623.0 126.0 80.1 35.8 172.4
32 910.9 692.5 131.4 83.1 37.5 181.9
36 1097.3 851.5 141.1 88.9 41.4 199.1
40 1311.3 1010.5 150.8 93.6 44.0 215.9
45 1601.2 1233.6 163.4 100.3 46.9 237.2
50 1901.8 1473.0 174.4 106.9 49.7 257.5
52 2030.4 1602.7 180.0 110.2 51.2 266.8
55 2233.1 1732.3 185.3 113.6 52.7 280.7
60 2597.8 2010.0 196.0 120.2 55.7 306.4
70 3415.0 2608.2 221.0 131.9 61.4 354.1
80 4318.9 3298.0 248.4 143.4 67.4 397.7
90 5339.1 4158.0 274.5 157.5 73.5 437.2
92 5553.2 4338.5 279.6 160.6 74.4 444.8
94 5768.0 4519.0 2'84.8 163.7 75.6 452.4
96 5989.2 4699.5 289.6 166.9 76.6 460.0
98 6210.9 4880.0 294.8 170.0 77.7. 467.2
100 6446.3 5060.5 300.0 173.1 78.7 474.2
120 9225.4 7098.0 347.4 202.2 88.9 544.1
140 U 406.0 9400.0 392.6 230.2 101.6 614.9
160 15 9OS.ot' 11 932.0 436.5 256.5 115.2 687.5
180 19672,(1' 14820.0 479.6 282.0 128.1 762.2
200 23 712.ot' 17 990.0 522.0 306.8 140.8 838.0
250 35 118.ot' 27 154.0 626.4 367.3 170.0 1030.4
300 48 SOO.ot' 38246.0 729.3 426.4 197.9 1225.3

aTodos los valores mostrados son para un riel (una mitad de la carga de vía). Las cargas por eje se
muestran en el diagrama. Los otros valores de las cargas E se obtienen por proporción.
bEn el centro del claro; los otros valores del momento están comúnmente cerca del centro del claro, de modo que se puede obtener el momento total como la suma de wL2/8 para la carga muerta
\+ el valor de la carga viva que se muestra en la tabla.

Con base en el peso de la locomotora, la carga Cooper se designa como E-40,
E-50, E-60, E-7S, E-SO, Ó E-ll0, y es directamente proporcional (esto es, E-60
\=6/S x E-SO). Los criterios ordinarios de diseño del AREA se basan en la carga
E-SO (a veces en la E-1l0) que se muestra en la figura 1-11. Con la tabla 1-2 se
pueden obtener los momentos flectores y las fuerzas cortantes en lugares determinados previamente de los puentes de trabes, con los valores dados para la carga

<!-- p. 45 -->

CARGAS SOBRE LOS PUENTES DE CARRETERA Y FERROCARRIL 45

HS 20 8 kips 36 kN 32 kips 144 kN 32 kips 144 kN
HSI5 6 kips 27 kN 24 kips 108 kN 24 kips 108 kN
\~I ~I ~I
0' 14~'~ V ~ --e:S=3}~-~------~W
\~-- O.IW-b--0.1W ~ ¿ ----r::.rr
W = peso combinado sobre los dos primeros ejes, que es el
mismo que el del correspondiente camión H (4.27 a
9.14 m) .
V = espaciamiento variable -se usará el espaciamiento de R = 72k (HS 20)
14 a 30 pies inclusive, que sea el que produzca los
máximos esfuerzos.

Momento máximo
La localización general del momento máximo . debido a las cargas de camión es como se
muestra (con valores del HS 20)

I I
HS 20 8 kips 36 kN 32 kips 144 kN
HS 15 6 kips 27 kN 24 kips 108 kN
HS 10 4 kips 18 kN 16 kips 72 kN
E I 14 pies: I V
W/longitud Momento Cortante Ñ ~ ,~i;".:-.:;~~:'::,Rjo"j~f- Camión kip/pie kN/m kip kN kip kN
E E O.IW I
HS 20 0.640 9.3 18 80 26 ! 16b - I I H 20 0.640 9.3 18 80 26 116
\- . .....: I HS 15 0.480 7.0 \3.5 60 19.5 87 ok H 15 0.480 7.0 13.5 60 19.5 87
Ñ E O.IW ~ H 10 0.320 4.7 9 40 13 58fl

Se coloca V en cualquier lugar del claro donde produzca el máximo efecto

W/longitud y cubre todo el ancho del carril de tráfico

Figura 1-10 Cargas estándar de camiones en puentes, según la AASHTO.

<!-- p. 46 -->

\~

N N o o V)e-r NV) '"V) V) V)r. '"o'1" 00 00 00o 00o V) '"o'1" o00 00o 00o 00o V)r. r,." r.
L 8k

'z. z;
O O O "" O ""O00 'O 00 O-c
r~ N r, N O""r' O O O"" "" ""O O O"" O ""Or' ""O". O"" - ""'O ""'O "" ""'O - O"" ""-c ""'O ""'O I I I I I I I I I I 1 1 1 1 I I N
L

Figura 1-1I Carga estándar Cooper E·SO,según del AREA. Se obtienen las otras cargas por proporción directa (esto es, E-60 = 0.75 x E-SO).

<!-- p. 47 -->

CARGAS SOBRE LOS PUENTES DE CARRETERA Y FERROCARRIL 47

de un solo riel (basada en la mitad de la carga por eje que se muestra en la figura
1-11)
Donde el puente soporte vías múltiples de tráfico para ferrocarril o carreteras la carga viva será como sigue:

Porcentaje de la carga viva

Carril o via AASHTO AREA

1 100 100
2 100 100
3 90 2 x 100 + 1 x 50
4 75 2 x 100 + 1 x 50 + 1 x 25
Más de 4 75 Según lo especifique el diseñador

Otras cargas de puente que se deben considerar incluyen fuerzas de impacto,
viento y longitudinales. Las fuerzas de impacto y longitudinales tienen en cuenta
los efectos dinámicos del equipo rodante que atraviesa el puente, así como los
arranques y paradas efectuadas sobre el mismo. El impacto se considerará en la
siguiente sección. La carga del viento se explica por sí misma y en el caso de un
puente cargado de ferrocarril, el viento que sopla contra un tren puede constituir
una carga sustancial.

1-9.1 Viento

\1. Los requerimientos para el viento de la AASHTO, para el viento en ángulo recto con el eje longitudinal:

Presión, fuerza/áreaTipo de puente o miembro
(en el área expuesta) pie lb s, Ib/pie2 SI, kPa

Armaduras 75 3.6
Trabes y vigas 50 2.4

Sin embargo, la carga total uniforme no debe ser menor que la siguiente:

Armaduras, 300 lb/pie ó 4.38 kN/m.
Trabes y vigas, 150 lb/pie ó 2.9 kN/m.
Para el viento sobre la carga viva a 6 pies ó 1.83 m por encima del tablero, 100
lb/pie ó 1.46 kN/m.

\2. Requerimientos del AREA, para el viento:

<!-- p. 48 -->

48 CONSIDERACIONES GENERALES DE DISEÑO

Presión, fuerza/área
Claro sin carga Claro con carga
Miembro del puente pie.Ib.s, Ib/pie 2 SI, kPa pie.lb.s, Ib/pie2 SI, kPa

Armaduras 50 2.5 30 1.5
Trabes y vigas 75 3.75 45 2.25

La carga total uniforme sobre el claro cargado no debe ser menor que la siguiente:

Cuerda o patín cargados, 200 lb/pie ó 2.92 kN/m.
Cuerda o patín sin carga, 150 lb/pie ó 2.19 kN/m.
Viento sobre la carga viva, a 8 pies ó 2.4 m sobre el riel superior, 300 lb/pie, ó
4.38 kN/m.

1-9.2 Fuerza longitudinal

La fuerza longitudinal (paralela al eje del puente) es como se ve a continuación:

AASHTO: 0.05 x carga viva (sin impacto).
AREA: 0.15 x carga viva (sin impacto).

Otras cargas que pudiesen requerir consideración incluyen las temperaturas
diferenciales entre los patines o cuerdas superiores e inferiores, cargas de hielo y
nieve, posibles sobrecargas y, para los puentes continuos, asentamiento de los
apoyos (pilas).
En los puentes de ferrocarril se establece una distinción entre los puentes que
consisten en trabes y durmientes (tablero abierto) y aquellos que tienen un sistema
de piso que contiene 6 pulg o más de agregado triturado (balasto). Estas últimas
estructuras se llaman puentes con tablero de balasto. Como se supone que el balasto pesa 120lb/pie' 018.86 kN/m3, una estructura con balasto tiene una inercia
y una relación de carga muerta a viva muy grande, lo que deberá reducir los efectos tanto de fatiga como de impacto. Esta ventaja se contrarresta algo por la mayor posibilidad de corrosión en las placas del tablero, debajo del balasto.

1-10 CARGAS DE IMPACTO

Todas las especificaciones de diseño hacen referencia a las cargas de impacto. El
factor de impacto se calcula basándose en una combinación de experiencia y
teoría a fin de obtener la carga de impacto como
L¡mpacto = L(1 + /1) (1-3)
Los factores para edificios de la AISC yel National BuildingCode son como sigue:

<!-- p. 49 -->

CARGAS DE IMPACTO 49

Tipo de carga J¡

Cargas de elevadores 1.00
Maquinaria y otras cargas móviles ;;.0.25

Se considera que las vigas carril de las grúas están sometidas a una carga lateral, y
con un valor de 0.25 x el peso de capacidad de la grúa x el peso de la grúa, y con
una mitad de este valor aplicado al tope de cada riel. Una fuerza longitudinal horizontal de 0.125 x la carga total de la rueda se aplica también al tope del riel de
la viga carril.
El requerimiento de impacto de la AASHTü es

pie lb s SI

50 15
J¡ - L + 125 S; 0.30 J¡ = L + 38 S; 0.30

donde L es la longitud del claro o porción de él que está cargado, en pies o en
metros. Las especificaciones de impacto del AREA dependen del equipo rodante.
Para las locomotoras diesel y eléctricas y ténders:

pie lb s SI

2
3L L \< 80 pies L \< 24m T¡ = 30.5 + 40 _ S 150
30.5 185 L > 80 pie L> 24m J¡ = S + 16 + L - 9.0

donde J¡ = factor de impacto expresado como porciento; se ha de dividir entre
100 para usarlo en los cálculos de diseño.
S = distancia entre centros de largueros longitudinales, solos o en gru-
pos, que se conectan a las vigas transversales de piso o a las trabes, o .
entre las armaduras principales o trabes, pies o m.
L = longitud entre las vigas transversales de piso o entre los apoyos, se-
gún se aplique, pies o m.

Se usará el 90 por ciento del J¡ calculado antes para los puentes de tablero con balasto.

Ejemplo 1-4 Se tiene un puente de carretera de armadura con carga HS 20.
Los paneles de la armadura son de 7.5 m, y la distancia entre reacciones es de
37.5 m. La distancia entre armaduras es de 14.1 m (ancho). ¿Cuál es el factor
de impacto, J¡?

<!-- p. 50 -->

50 CONSIDERACIONES GENERALES DE DISEÑO

SOLUCION El factor de impacto variará para las vigas de piso, largueros y
la armadura, dependiendo de sus respectivas longitudes. Para los largueros,
el factor de impacto es

li = 7.5 ~ 38 = 0.330 > 0.30 Se usará por consiguiente I¡ = 0.30 / / /

Ejemplo 1·5 Un puente de ferrocarril de tablero abierto consiste en dos ar-
maduras espaciadas a 17.00 pies. Las armaduras consisten de siete paneles a
27.6 pies/panel. ¿Cuál será el factor de impacto?
SOLUCION Como L > 80 pies,
L = 7(27.60) = 193.2
100 600 .
li = 17 + 16 + 193.2 _ 30 = 25.6 por Ciento III

Ejemplo 1·6 ¿Cuál es el impacto para las vigas de piso de la armadura según
el AREA del ejemplo 1-5? Las vigas de piso son miembros transversales que
conectan las dos armaduras en los puntos de panel.

SOLUCION S = 27.6 pies L = 17 pies \< 80.

100 3(17)2 .
li = 27.6 + 40 - 1600 = 43.1 por Ciento III

1-11 CARGAS SISMICAS

Los análisis sísmicos siguen dos tendencias generales. Una de ellas es tratar de
modelar la estructura como un conjunto de masas y resortes y usar una computadora digital para desarrollar espectros de respuesta para diversas aceleraciones
sísmicas supuestas. El otro método consiste en obtener las aceleraciones sísmicas
con base en la probabilidad sísmica, un periodo de excitación basado en la
geometría del edificio, y aplicar la ecuación de fuerza F = ma, para obtener una
fuerza de aceleración que se prorratea de alguna manera en los diferentes pisos,
de modo que ~ F, = F. En los siguientes párrafos se da el procedimiento
semiempírico para el análisis sísmico según el Uniform Building Code (el del NBC
es casi idéntico); véase la ecuación que sigue, (1-7), para la identificación de los
términos que no se han identificado inmediatamente después de las ecuaciones:
La fuerza sísmica lateral que actúa sobre el edificio, en cualquier dirección,
se puede calcular usando una modificación de F = ma:
F= ZIKCSW (1.4)

Los códigos (UBC y NBC) permiten que el producto de los factores C y S sea

<!-- p. 51 -->

CARGAS SISMICAS 51
es .-; 0.14
El factor e se basa en el periodo fundamental del edificio, T:
e = l .-; 0.12 (1-5)
15vT

El periodo fundamental del edificio se obtiene como el periodo de un resorte
vibratorio que tiene la ecuación general

T= 27r{f

donde m = masa (del edificio)
k = constante del resorte (y que se obtiene para los edificios como la su-
ma de las contribuciones de los elementos de la estructura).

Como las constantes de resorte son difíciles de determinar, es más común calcular
el periodo del edificio usando un factor basado en la experiencia, para obtener

T= JH (segundos) (1-6)
Vi5

donde J 0.05 cuando H (altura) y D (dirección lateral del edificio en la dirección
que interesa) están en pies, y J = 0.91 cuando H y D están en metros. Cuando la
estructura está hecha de material dúctil como el acero, se permite aproximar el
periodo del edificio a

T = 0.10 x número de pisos por encima de la base

La fuerza lateral de la ecuación (1-4) se distribuye como sigue:

\~ 0.25F Fl ope = 0.07TF

T~ 0.7s. La fuerza a cualquier nivel de piso sepero Fl ope puede ser cero cuando
prorratea como

(1-7)

Los términos no identificados previamente en las ecuaciones anteriores son:

D = Ancho del edificio en la dirección que interesa, pies o m
H = Altura del edificio sobre el nivel del terreno, pies o m
h n =Altura hasta cualquier piso desde el nivel del terreno

<!-- p. 52 -->

52 CONSIDERACIONES GENERALES DE DISEÑO

1 = Factor de importancia de ocupación: 1 1.5 para facilidades esenciales
1.25 para salones de reunión
I para otra ocupación
K Coeficiente de fuerza lateral basado en el tipo de edificio como en la tabla
1-3
S Coeficiente numérico para la resonancia del sitio; se usará S = 1.5 a me-
nos de que se disponga de datos geotécnicos más exactos del sitio
W Carga muerta total o carga muerta + 25 por ciento de la carga viva en al-
macenes
Wn Carga en el piso enésimo
Z Coeficiente sismico zonal, según se obtiene de la figura 1-12, basado en la
situación geográfica del edificio:

Para la zona: Z

1 0.187
2 0.375
3 0.75
4 1.00

Tabla 1-3 Factor K de fuerza horizontal para edificios y otras estructurasa
Tipo de estructura K
\1. Todos los edificios con sistemas de marcos torales, excepto como se indica a conti-
nuación 1.00
\2. Edificios con un sistema de cajón, esto es, sin un marco espacial completo para so-
portar la carga vertical; parte de la carga de gravedad soportada por los muros de
carga 1.33

\3. Edificios con un sistema doble de contravenreo, que consiste en un marco dúctil que
resiste al momento y de muros de cortante o marcos contraventeados como sigue:
a. Los marcos y los muros de cortante resisten la fuerza lateral total de acuerdo con
las rigideces relativas y con interacción entre el muro y el marco. 0.80
b. Los muros de cortante actúan independientemente de la capacidad resistente al
momento del marco dúctil, y resisten la fuerza lateral total
c. El marco rígido debe ser capaz de resistir cuando menos el 25 por ciento de la
fuerza lateral total

\4. Edificios con un marco dúctil, resistente al momento, y que puede resistir el total de
la fuerza lateral 0.67

\5. Tanques elevados más el contenido, soportados por cuatro o más patas contraven-
teadas y que no están soportados por un edificio 2.5h

6 Otras estructuras distintas de los edificios 2.00
a Cuando la carga de viento produzca mayores esfuerzos, se usará la carga del viento en lugar de
la carga sísmica
b El valor mínimo de "K x C' = 0.12, Yel máximo no excederá 0.25. La torre de soporte del
tanque se diseña para una carga de torsión basada en la fuerza lateral, con una excentricidad del 5 por
ciento de la dimensión de la estructura en el punto de aplicación de la fuerza.

<!-- p. 53 -->

CARGAS SISMICAS S3

30'

ZONA O- Sin daños
.2 5° ZONA 1 - Daños menores; los sismos distantes
pueden causar daños en estructuras con
periodos fundamentales mayores de 1.0
\~et~nt~¡aC~~~~\<;I~o~~~~.la5intensidades V -+ .L, +----¡
ZONA 2 • Daños de importancia; corresponde a la ZONA 4 ~ Corresponde a aquellas áreas dentro de la
intensidad VII de la Escala M.M.· Zona No. 3, determinada!'; por la
ZONA 3 - Daños de importancia; corresponde a las proximidad a algunos importantes sistemas
intensidades VIII o más airas de la Escala de fallas.
M.M,· *Escala de intensidad de Mercalli, modificada. 1931
1100 100 0 90 0
Figura 1-12 Mapadelaszonas sísmicas en losEstados Unidos. (Según el UniformBuilding Code, 1976).

Ejemplo 1·7 En la figura EI-7a se muestra un edificio de apartamentos de 10
pisos y sótano. El exterior está formado por muros aislantes y ventanas tér-
micas (doble hoja) con un peso estimado de 15lb/piel. Las paredes interiores
están generalmente constituídas por canceles dobles enyesados por ambos la-
dos y con aislamiento entre las hojas individuales. Se usan pisos de concreto
de 4 pulg (son mosaicos o alfombras) colocados sobre soportes metálicos de
acero corrugado, y sostenidos por viguetas de acero de celosía. El edificio es-
tá situado en Memphis, Tennessee. Estímese la fuerza sísmica y la correspon-
diente carga por piso.

SOLUCION Estímense de la manera siguiente las cargas muertas de techo y
piso:
Techo:
Entablado de madera 3 lb/piel
Fieltro de techo de 5 capas 7 lb/piel
Plafón y viguetas de celosía 11 lb/piel
Total 21 lb/piel
Peso total del techo 0.021(40 x 90) 75.6 kips

<!-- p. 54 -->

54 CONSIDERACIONES GENERALES DE DISEÑO

Elevación

40'

1-----------

\- - - - - - - - ---

Plan Figura EI-70.

<!-- p. 55 -->

CARGAS SISMICAS SS

Para cualquier piso:
Canceles para un apartamento de 40 x 30 y 8 pies de altura y en i perímetro
\+ 2 muros transversales a 20 lb/pie-
da: (40 x 2 + 30 x 2)(8)(20)/(40 x 30) = 18.71b/pie2
Piso: _4_ (144) (concreto) = 48.0 lb/pie-
12
Plafón (estimado) 10.0 lb/pie-
Viguetas de celosía y plancha metálica ó.ü lb/pie-
Muro exterior a 10 pies de altura
(2 x 40 + 2 x 90)(15)(10)/(40 x 90) 10.8 lb/pie-
Total = 93.5 lb/pie-
Peso total del piso = 0.0935(40 x 90) = 336.6 kips

Estos pesos se ilustran en la figura EI-7a. Para facilitar los cálculos, se usarán
pesos de 76 y 337 kips, respectivamente para el resto del problema. Para la
zona 3 de la figura 1-12, el factor Z es 0.75; tómese 1 = 1.00; tómese K =
0.80, obtenido de la tabla 1-3. El peso total del edificio = 76 + 10(337) =
3446 kips.
La fuerza sísmica en la dirección E-W, se calcula como sigue:

D = 40 pies
T = 0.05(100) = 0.7906 s
V40
Como la estructura es de acero, el cálculo alternativo del periodo es
T = 0.1 x número de pisos = 0.1(1O) = 1.0 s.

El autor promedia los dos valores de T para obtener T = 0.895 s.
c=---1 ----1 = 0.0705
15VT 15VO.895

La sustitución de esta acumulación de factores/peso en la ecuación (1-4) da
F = 0.75(1.0)(0.80)(0.0705)(1.5)(3446) = 218.6 kips

El valor para el techo es
Ftope = 0.07TF = 0.07(0.895)(218.6) = 13.7 kips (T > 0.7 s)

Las cargas por piso se hallan usando h; = distancia desde el terreno
hasta el piso n, de la manera siguiente: L Wnhn = 337(90) + 337(80) +
337(60) + .. , +337(10) = 151 650 pie· kips

<!-- p. 56 -->

56 CONSIDERACIONES GENERALES DE DISEÑO

13.7k

10'
tO.98

36.42

31.87

27.32

22.77

18.21

13.66

9.11

\0'
4.SS k

\0'

Figura EI-7b

W h Wnhn (2186 13 F = ( F - Ftope ) ~ . - . Wn hn = 7)-:-::-:~C7151 650 n n
Para el décimo piso
F IO = 0.001351(337 x 90) = 40.98 kips (que se muestran en la figura EI-7b)
F9 = 0.001351(337 X 80) = 36.42 kips
Fa = 0.001351(337 X 70) = 31.87 kips
F2 = 0.001351(337 X 10) = 4.55 kips
Sumando las cargas horizontales de piso e incluyendo el valor del techo de
13.7, se obtiene como verificación 218.59 versus 218.6. Estas cargas laterales
de piso se tienen todavía que prorratear entre los diversos claros en la direc-
ción E-W para la condición (o condiciones) de carga del análisis de la estruc-
tura, el que incluye las fuerzas sísmicas. ///

1-12 FATIGA

Se han registrado numerosas fallas estructurales que se han atribuido a la fatiga.
La falla por fatiga es una fractura del material causada por un número suficiente-

<!-- p. 57 -->

FATIGA 57

I I I!I I 1 1I I i 1I ! i 11
I I I I I I1
\<; I I!' , I I' I i I
I -:ffi4' I - "'- I i [ i I i I I I i i 1 i ----- ~lllilil I I ¡ L I I i I I i i I ! I 1I
001 01 3 10

Figura 1-13 Trazado cualitativo del rango del esfuerzo Fsr versus el número de ciclos necesarios para
la falla.

mente grande de repeticiones de esfuerzos, esfuerzos cíclicos o pulsantes o inversiones de esfuerzo. La aplicación de esfuerzos tiende a producir una fractura del
material en un lugar donde exista una pequeña imperfección (que puede tener un
tamaño microscópico). Se forma una grieta y, dependiendo del nivel de esfuerzos, progresa rápida o lentamente (a veces con tanta lentitud que se puede detectar visualmente la grieta antes de que ocurra la falla) hasta la ruptura del
miembro.
La mayoría de los metales que se prueban bajo cargas repetidas o cíclicas
muestran un rango de esfuerzos versus el número de ciclos para llegar a la falla,
como se ilustra cualitativamente en la figura 1-13.En otro tiempo, estas curvas se
presentaban comúnmente como niveles de esfuerzo versus ciclos. En la actualidad, el parámetro de interés lo constituye el rango de esfuerzos. El rango de esfuerzos Fsr se puede definir como

(l-8)

donde Fmáx es el esfuerzo máximo yfmío el esfuerzo mínimo a los que está sometido el miembro mientras da servicio. El límite de fatiga (rango de esfuerzos) a menudo se define como el rango de esfuerzos que requiere cuando menos 2 x 106
ciclos de esfuerzo para causar la falla.
Las especificaciones del AISC, AASHTO, y el AREA son casi idénticas al
especificar el rango de esfuerzos y el número de ciclos de esfuerzo (cuando la falla
del miembro no sea catastrófica). Dichas especificaciones se basan en la ejecución
de gran número de pruebas (véase Fisher, "Fatigue Strength of Steel Members
with Welded Details", AISC Engineering Journal, No. 4, 1977). En la tabla 1-4
se dan valores típicos de rangos de esfuerzos que se pueden usar con las tres espe-

<!-- p. 58 -->

58 CONSIDERACIONES GENERALES DE DISENO

Tabla 1-4 Rango del esfuerzo permisible Fsn para diversos materiales y
tipos de esfuerzo
Rango de esfuerzos, kip/pulg?
Ciclos =
20 a 100 100 a 500 500 a 2000Más de 2000
Material Esfuerzo x loJ xloJ x loJ x loJ

Metal de base con superficies laminadas To Inv" 60 (415) 36 (250) 24 (165) 24 (165)
Miembros armados
Metal base y metal de aportación,
construidos de placas y perfiles con
soldaduras de ranura con penetra-
ción total o parcial T o Inv" 45 (310) 27.5 (190) 18 (124) 16 (110)
Esfuerzo calculado de flexión en el ta-
lón (toe) del alma o del patín adya-
cente a atiesadores transversales
soldados To Inv" 32 (221) 19(131) 13 (90) IOb (69)
Metal base al final de las cubreplacas
parciales de recubrimiento (rectas o
ahusadas) To lnv" 21 (145) 12.5(86) 8 (55) 5 (34.5)
Conexiones mecánicamente fijas
Metal base en la sección, que usaco-
nexiones de fricción con tornillos
de alta resistencia -pero sin fle-
xión fuera del plano en la junta To Inv" 45 (310) 27.5 (190) 18(124) 16 (\lO)
Metal base en la sección neta de las
juntas remachadas o con otra suje-
ción mecánica To Inv" 27 (186) 16(110) 10 (69) 7 (48.3)
Soldaduras de ranura
Metal base y metal de aportación con
penetración total, rebajado a ras, e
inspeccionada To Inv" 45 (310) 27.5 (190) 18(124) 16 (110)
Metal base y metal de aportación en
empalmes con penetración total To Inv" 45 (310) 27.5 (190) 18 (124) 16 (110)
Conexiones soldadas a filete
Metal base con filetes intermitentes de
soldadura To Inv" 21 (145) 12.5(86) 8 (55) 5 (34.5)
Metal base en la unión de un miembro
sometido a carga axial con cone-
xiones en sus extremos soldadas a
filete y con las soldaduras balan-
ceadas respecto al eje del miembro To lnv" 21 (145) 12.5(86) 8 (55) 5 (24.5)
Soldaduras de filete, continuas o in-
termitentes, longitudinales o trans-
versales Cortante 15(103) 12(83) 9 (62) 8 (55)

a T, Tensión; Inv, inversión de esfuerzos (tanto a tensión como a compresión).
b Se usará 12 k/pulg2 u 83 MPa para el alma de las trabes.

<!-- p. 59 -->

ESTRUCTURAS DE ACERO 59

cificaciones. El lector debe consultar el Structural Welding Code, sección 9-14,
que es donde se origina el material usado en las tres especificaciones, o la especificación apropiada de diseño para una más completa presentación de los casos de
fatiga y el Fsr•
El mayor valor en cada categoría de ciclos que aparece en la tabla 1-4 es por
lo general aplicable a edificios. Valores más bajos que los mostrados son necesarios para secciones reducidas, ciertos tipos de juntas, tipo del material de las mismas, y para algunos miembros en los edificios industriales. Se deben consultar el
manual AISC (Apéndice B), el A WS Structura/ We/ding Code, las especificaciones de la AASHTO (sección 1-7.2 o del AREA, para aquellos casos donde sea
preciso considerar la fatiga. Nótese que no es común considerar la fatiga junto
con las fuerzas de viento o sísmicas sobre los edificios. La fatiga no se considera
por lo general en el diseño de rutina de edificios, ya que 10 ciclos de carga/día durante un periodo de 20 años sólo representa

N = 10 x 365 x 20 = 73000 ciclos

Estos casi nunca son suficientes ciclos de cualquier rango de esfuerzos, para requerir una reducción en los esfuerzos permisibles, para tener en cuenta la fatiga.

Ejemplo 1-8 Se supone que una sección laminada estará sometida a 1 x 106
ciclos de esfuerzo durante el periodo de diseño de la estructura. El análisis de
los esfuerzos da Fmáx = Pmáx/A = 16 k/pulg-; fmín = - Pmín/A = - 12
pulg-. El esfuerzo básico para este miembro es fa = 22 k/pulg- (tensión) y
16.5 k/pulg- (compresión). La configuración estructural limita a Fsr = 24 k/
pulg- en el metal base. ¿Será satisfactoria esta sección?

SOLUCIONo
isr = 16 - (- 12) = 28 k/pulg- \< 24 k/pulg- No sirve

Esta sección no es adecuada para este número de ciclos; se debe aumentar la
sección de manera que Fsr \< 24 k/pulg-, Nótese que la sección es adecuada
para los esfuerzos estáticos "permisibles". / / /

1-13 ESTRUCTURAS DE ACERO

Las estructuras de acero incluyen puentes, edificios, torres de transmisión, tanques de almacenamiento, soportes para anuncios, y hasta objetos artísticos. En
este libro se da atención principalmente a puentes y edificios, ya que éstos son los
proyectos.más comunes de los que se ocupan los ingenieros.
De acuerdo con su uso, los edificios se clasifican por lo general en edificios
industriales o de muchos pisos. En la actualidad se usa muy poco el acero en la
construcción residencial, excepto en los apartamentos de muchos pisos.

<!-- p. 60 -->

60 CONSIDERACIONES GENERALES DE DISEÑO

Cabezal Cabezal

\ Rígido o
articulado

Marco de un solo claro Marco de un solo claro Marco de múltiples claros

( Parapeto Techo '\

Columna y cabezal acartelados
en un marco rigido

Puntal
Armadura sobre columna de rodilla

L

Figura 1-14 Diversos marcos usados en las estructuras de acero para edificios.

Largueros

\<
0\<1t:°x 0qro I
\~
0\<1t:o~
Figura 1·15 Términos adicionales usados para identificar los miembros estructurales de los edificios
industriales.

<!-- p. 61 -->

ESTRUCTURAS DE ACERO 61

1-13.1 Edificios industriales

En general, los edificios industriales son estructuras de uno o dos pisos que se
usan principalmente con fines industriales (como son las fábricas, almacenes, u
operaciones de menudeo/mayoreo), e institucionales (que incluyen escuelas, hos-
pitales, hoteles, apartamentos). Entre otras estructuras se pueden incluir los gim-
nasios, arenas, iglesias, restoranes, y terminales de transporte (tierra, mar, aire).
Estos edificios pueden estar compuestos de marcos de acero, como los de la figura
1-14, o tener un techo soportado por miembros de acero que descansan sobre mu-
ros de carga (véase figura 2-4). El esqueleto de acero del edificio puede ser rígido o
articulado; puede ser un arco con dos o tres articulaciones, o puede ser un sistema
de armaduras sobre columnas. La armadura puede ser rígida o articulada. En la
figura 4-1, se muestran varias estructuras de edificios durante la construcción.
La estructura de un edificio es un esqueleto tridimensional, pero por lo gene-
ral se considera como rígida en un plano solamente. Algunos edificios son rígidos
tanto en el plano XY como en el plano XZ, pero este tipo de estructura no se tratará en este libro. La estructura plana que se obtiene de considerar solamente los
elementos principales de la misma y/o la rigidez se llama marco y puede tener una
altura de uno o más pisos (las figuras 1-14y 1-15 ilustran términos que se definen en
este caso y más tarde). El término "marco" se usa en todas las estructuras ya sean
rígidas, armadura sobre columnas, cabios sobre columnas, u otros miembros, y
que se utilizan para salvar el espacio entre columnas en el plano principal. La se-

Vigas
exteriores

Figura 1-16 Vigas exteriores en un edificio de oficinas de cinco pisos. Nótese que las vigas exteriores
soportan trabes más pequeftas y a las que se fijarán los muros de la fachada.

<!-- p. 62 -->

62 CONSIDERACIONES GENERALES DE DISEÑO

paración entre marcos según la tercera dimensión constituye las crujías. Las vigas
de borde y de piso se usan para salvar las crujías en edificios de muchos pisos (véanse las figuras 1-16 y 4-1c) con trabes (que por lo general son miembros más pesados que las vigas de piso) tendidas entre las columnas de los marcos. En la figura
1-15 se ilustran términos adicionales para edificios industriales de un solo piso,
donde se hace notar que el contraventeo lateral (véase figura 4-1d) se usa en determinados claros.
El sistema de techo ge todos los edificios consiste en una estructura, algún
sistema de piso y una cubierta impermeabilizante. La estructura principal del
techo consiste de los cabios o de la armadura en cualquier marco. Los largueros
se tienden a través de las crujías y se espacían de 0.6 a 2 m (2 a 6 pies), o más, medidos centro a centro, dependiendo del tipo de tablero de techo que se use. Se proveen tensores como un apoyo adicional para los largueros que se usan en los
techos en pendiente. El diseño de los largueros en los techos inclinados resulta
bastante complejo debido a la flexión asimétrica (véase ejemplo 4-10). El tablero
de techo descansa sobre los largueros y puede ser un tablero metálico, losas de
concreto prefabricadas, entarimados de madera, o planchas de asbestos o yeso.
Las paredes pueden ser de chapa metálica, chapas metálicas "sandwichs"
(muros de cortina) que consisten en dos hojas metálicas con algún tipo de relleno
aislante, tablones de asbesto, ladrillos, bloques de concreto, mosaicos o concreto
precolado o colado en el lugar. Las paredes ligeras se soportan con vigas de

Figura 1·17 Largueros de la pared exterior conectados a las columnas usando segmentos cortos de an-
gular atornillados con pernos de alta resistencia. Refiérase a la figura 4-lb para largueros parcialmente
instalados en un edificio industrial usando columnas acarteladas y secciones de cabios. Nótese los largueros que descansan sobre los cabios.

<!-- p. 63 -->

ESTRUCTURAS DE ACERO 63

Figura 1-18 Estructuración del piso. Las trabes son las secciones de mayor peralte a las que se conectan las vigas de piso. Se usa un tablero metálico sobre las vigas y donde se colará el concreto para producir un piso compuesto. Los miembros diagonales que se muestran constituyen el contraventeo de la
armadura. La dirección de las vigas de piso con respecto a las trabes determina la dirección del flujo
de carga, desde cualquier piso hasta la cimentación.

fachada suplementadas con largueros de pared en los edificios de muchos pisos.
En los edificios industriales el recubrimiento ligero de las paredes lo soportan los
puntales del alero y los largueros de pared.

Figura 1-19 Uso de una armadura del tipo de tablero superior para el claro de aproche y de una armadura de tablero inferior para la luz principal. Nótese el contraventeo lateral aproximadamente a la mitad de la altura de la armadura principal para reducir la longitud no soportada de los miembros verticales de la armadura. La geometría particular de las diagonales se usa para reducir la longitud sin apoyo de los miembros diagonales.

<!-- p. 64 -->

64 CONSIDERACIONES GENERALES DE DISEÑO

La viga de borde o fachada, ya mencionada, es similar a un larguero y se coloca en la línea de piso como la viga de piso más externa, y soporta cierta proporción de la carga de piso. Soporta también parte de la pared lateral. Sr el recubrimiento lateral es pesado (ladrillos, bloques de concreto, mosaicos, etc.) se puede
"reforzar" el larguero usando un canal o un angular, dependiendo de la carga
que haya que soportar. Las vigas de-borde se muestran en las figuras 1-5j,I-16, y
4-1h. Las trabes se muestran en la figura 1-17.
El sistema general de entramado del piso de un edificio de muchos pisos, se
puede ver en las figuras 1-18, 4-1e y 4-lf. Es necesario establecer el entramado del
piso desde el mismo principio del diseño de modo que se pueda realizar el flujo de
carga y dimensionar a los diversos miembros.

1-13.2 Puentes

Los puentes se pueden clasificar en dos tipos: de armadura, trabes armadas (que
incluyen las vigas laminadas); y de arco, o de suspensión (que usan cables o
barras en los miembros principales para soportar la carga). Los puentes de armaduras y trabes armadas son los de uso más común y los únicos considerados en el
texto. Los puentes del tipo de armadura abarcan los puentes de tablero superior en
los que el tráfico pasa por encima de la armadura, y los de tablero inferior, donde
el tráfico pasa entre las armaduras. Se prefiere en general el tipo de tablero superior cuando el espacio libre debajo de la armadura no sea un factor determinante,
porque es posible hacer más cortas las pilas. Muchos puentes de armadura combinan los dos tipos de armaduras (véasefigura 1-19). Es práctica común usar combinaciones de armaduras para las luces más largas y trabes para los claros más cortos
(o los aproches). Este último esquema se ilustra en la figura 4-140. En la figura 1-20
se muestran los términos usados en las armaduras de puente (véase también la figura 4-13). Actualmente se usan estructuras de trabes en el diseño de los puentes, las
que requieren menos trabajo de fabricación que las armaduras. En todo caso se
usa lo más posible la soldadura, y con las conexiones de campo soldadas o
construídas usando tornillos de alta resistencia.

,_ panel ..,. Panel _1

4-
\~o~
Vertical ~

l, Claro
Figura 1-20 Términos usados en las armaduras. Se muestra una armadura continua. No es necesario
que todos los paneles tengan la misma longitud. Cuando la altura de la armadura aumenta en la región de altos momentos (sobre el apoyo), se debe reducir la longitud de los paneles para hacer más
cortos los miembros.

<!-- p. 65 -->

CALCULOS DE INGENIERIA ESTRUCTURAL EN UNIDADES SI 6S

1-14 EXACTITUD DE LOS CALCULOS y DE
LAS COMPUTADORAS ELECTRONICAS

En los tiempos en que la regla de cálculo de 10pulg era e! principal auxiliar de los
cálculos en la oficina del diseñador estructural, los cálculos rara vez sobrepasaban las tres cifras significativas. Esto era (y es) satisfactorio, por las razones aducidas al principio de este capítulo tanto de manera directa o como se implicaba en
los cálculos de los ejemplos.
En la actualidad, la calculadora electrónica y/o la calculadora digital se usan
casi universalmente en los cálculos estructurales, tanto por la mayor complejidad
de las configuraciones estructurales como por la mayor velocidad al efectuar los
cálculos y fijar automáticamente e! punto decimal. En la actualidad, es casi obligatorio (tanto por razones éticas como económicas) efectuar varias iteraciones en
e! cálculo de una estructura para la mayor optimización de! diseño. Este paso casi
siempre requiere e! uso de una computadora digital.
Estos dispositivos de cálculo pueden proporcionar un número bastante grande de dígitos para cualquier resultado de los cálculos; el problema consiste en la
manera como se ha de considerar este aumento en la capacidad de cálculo. Es evidente que la entrada no es mejor que la salida, pero con un gran número de
dígitos aparentemente significativos, luce muy impresionante. En casi todas las
oficinas de diseño, los cálculos de diseño los verifica una segunda persona, como
precaución. Si el diseñador original efectúa gran número de cálculos en serie
usando una calculadora electrónica, los resultados diferirán de los obtenidos
cuando el revisor elimina los pasos intermedios, y luego los vuelve a utilizar para
continuar los cálculos. Cuando las discrepancias no son grandes, se origina la duda de que si el problema ha sido "verificado" o si una de las personas (o ambas)
ha incurrido en una omisión en el diseño.
Por estas razones se aconseja que, no importa cuál sea la exactitud de los datos
iniciales, los cálculos se deben llevar a tantos lugares decimales como sea práctico
(quizá 0.001) para obtener una buena convergencia en la verificación. El esfuerzo
adicional en los cálculos es mínimo. Cualesquiera pasos intermedios se deben
escribir con la misma precisión con que se han de usar en los cálculos subsiguientes (esto es, no se escriba 106.1 y luego se use 106.153 en los cálculos subsiguientes).

1-15 CALCULOS DE INGENIERIA ESTRUCTURAL
EN UNIDADES SI
1-15.1 Unidades principales

Las unidades SI que revisten mayor interés para el ingeniero estructural son las siguientes:

Peso unitario, kN/m3•

<!-- p. 66 -->

66 CONSIDERACIONES GENERALES DE DISEÑO

Masa unitaria (también densidad de masa o simplemente "densidad"), kg/rn" o
ton/m- (la tonelada métrica = 1 000 kg; 1 ton/m? = 1 g/cm-),
Presión (mayor de 1 000 lb/pulg- en unidades pie lb s), MPa (MPa = megapascal
\= 106 N/m2) .
Presión (menor de 1 000 lb/pulg- en unidades pie lb s), kPa (kPa = kilopascal =
103 N/m2) .
Peso lineal (como el peso de las vigas para los momentos flectores), kN/m.
Masa lineal (como cuando se ponen las órdenes a la fábrica), kg/m.
Momentos flectores, kN·m.

Las tablas del SSDD usan mm en las unidades SI para las dimensiones de las
secciones y m" para los módulos de inercia x 10-6, y el de sección por 10- 3• Estos exponentes son múltiplos de 3, como se acostumbra. Además el usuario debe
tomar nota de que

}; M M, kN . m = MPa
3 X 10- 3 X 103 b = S = S, m
M = fbS = MPa X m3 X 10-3 X loJ = kN . m

donde no es necesario escribir el valor 10- 3 después de haber efectuado los cálculos varias veces para adquirir confianza.

Ejemplo 1-9 Dados los datos:
Módulo de sección, S = 6.33 rrr' (x 10- 3)
Fb = 0.6F;, = 0.6(250) = 150 MPa
M = 12ookN· m

¿Es adecuada la sección? Si no lo fuera, ¿qué S se requerirá?

SOLUCION

M 1200
fb = S = 6.33 = 189.6 MPa > 150 La sección no es adecuada

El S requerido es

M 1200 3 ( -3) S=-=--=8oom x ro Fb 150 .

Nótese que no es necesario incluir el 103 junto con el valor de 150 MPa para
producir 150000 kPa por división (después de haber adquirido alguna prác-
tica), ya que las unidades se obtendrán corriendo simplemente el punto deci-
m~. ///

<!-- p. 67 -->

CALCULOS DE INGENIERIA ESTRUCTURAL EN UNIDADES SI 67

1-15.2 Tipos y precisión general de las unidades SI

Las unidades SI indicadas tienen la suficiente precisión para los cálculos:

Concepto Aproximación al siguiente
Peralte de las vigas, ancho de los patines, lados de
los angulares 1.0 mm
Espesor de cualquier miembro como placas, etc. 0.1 mm
Momento de inercia (m" x 10- 6) , pero depende del
tamaño 0.01
Módulo de sección (m! x 10- 3), pero depende del
tamaño 0.01
Radio de giro 0.1 mm
Usese para los pesos: 0.01 kN/m
(La especificación A-6 de la ASTM usa por lo
general el kg/m más cercano para una selec-
Masa: 0.1 kg/m ción de perfiles laminados -queda por vez
cómo se comprará el material, ya que no es
probable que los fabricantes regalen grandes
masas al comprador que exige un excesivo
números de cortes).
Presión: 0.01 kPa
Presión: 0.1 MPa
Peso unitario: 0.01 kN/m3

El lector debe observar que en las tablas SSDD, algunas de las dimensiones y
presiones difieren ligeramente de la precisión de la lista anterior, debido a que se
calcularon en la computadora. Los valores de las tablas son aceptables, pero
cualesquiera otros valores adicionales calculados, deben estar de acuerdo con los
anteriores.

1-15.3 Selección de factores de conversión a unidades SI

A continuación se dan algunos de Jos más útiles factores de conversión. Nótese
que cualesquiera unidades derivadas de fuerza, se pueden deducir usando

1 pie' de agua pesa 62.4 lb/pie1 m3 de agua pesa 9.807 kN/m3
1 m! de agua tiene una densidad de masa de 1 000 kg/m! 1 g/cm'
1 pie = 0.3048 m
1 m = 3.2808 pie
g = 32.17 pie/s- = 9.8054 m/s- (se usará 9.807)

Ejemplo 1-10 Conviértanse 120 lb/pie' a unidades SI

Peso unitario = ~~~ (9.807) = 18.86 kN/m3

<!-- p. 68 -->

68 CONSIDERACIONES GENERALES DE DISEÑO

¿Cuánto es 23.5 kN/m3 en pie lb s?

Peso unitario = :.~g7 (62.4) = 149.5pcf III

El lector debe observar que no se muestran los varios pasos intermedios que
producen los resultados finales de 62.4 y 9.807.
A continuación se indican algunos otros factores de conversión que pueden
ser de utilidad:

Para convertir a Multiplíquese por

kilogramo (kg) kilonewton (kN) 0.009806650
libra (lb) kg 0.4535924
libra kN 0.004448222
kips (1000 lb) kN 4.448222
lb/pie kNjm 0.014593727
kips/pie kNjm 14.593727
lb/pie kgjm 1.48816404
lb/pulg' MPa 0.006894757
lb/pulg? kPa 6.8947577
kip/pulg-' MPa 6.8947577
kip/pulg? kPa 6894.7577
Ib/pie 2 kPa 0.04788026
kip/pie' kPa 47.88026
kip . pie (momento) kN·m 1.35584
kip . pulg kN·m 0.1l29862

PROBLEMAS

1-1 ¿Cuál es la €y para un acero con Fy = 40 kips/pulg/?
1-2 ¿Cuál es la €y para un acero con Fy = 365 MPa?
Respuesta: 0.00182.
1-3 ¿Cuál es el aumento en peso/pie de una viga WI6 x 40, como aparece en la figura PI-3, después
de la aplicación de 2 pulg. de perlita? (véase figura 1-5); el método de aplicación es probable que no
produzca una sección geométrica exacta; por consiguiente, el cálculo no debe ser sumamente preciso.
Respuesta: 30 lb/pie.

r----=,.",....----,

Protección contra
el fuego

Figura Pl-3

1-4 ¿Cuál es el aumento en peso de una sección laminada W410 x 46.1, con 55 mm de vermiculita
aplicada como protección contra incendios, como se ve en la figura PI-3? (Antes de resolver el problema, léase el comentario del problema 1-3).

<!-- p. 69 -->

PROBLEMAS 69

1·5 ¿Cuál es el factor R para la columna interior en el piso más alto y tres pisos más abajo, como se ve
en el ejemplo I-I?
t~6 ¿Cuál es el factor R de la viga BI y la columna B2 del ejemplo 1-2?
1-7 ¿Cuáles son las fuerzas de viento en los puntos 1 a 9 inclusive y que se muestran en la figura PI-77
Respuesta: P(5) = - 18.07 kips.

5

8 (u 3.05 = 24.4 m

Separación entre los marcos = 6.32 m

Figura Pl-7

)-8 ¿Cuál es la carga de nieve para el edificio de la figura PI-', si el lugar está cerca de Chicago, 11Iinois,
donde el Chicago Building Code requiere 1.25 kPa?
)-9 ¿Cuál es el cortante y momento f1ector máximos en el claro de 92 pies de un puente para un camión HS 15? ¿Cuál es el factor de impacto?
Respuesta: V = 48.5 kips, 1 = 0.23.
)-10 ¿Cuál es el cortante y momento f1ector máximos en el claro de 52.5 m para un camión HS-20?
¿Cuál es el factor de impacto?
I-H ¿Cuál es el momento máximo en la trabe de un puente de ferrocarril (una de dos) que soporta
una sola vía. El claro es de 30.5 m y el espaciamiento entre las trabes es de LIZO. Usese una carga
E-n. ¿Cuál es el factor de impacto si la via usa locomotoras diesel y el puente es de tablero inferior
con balasto?
Respuesta: M = '865 kN . m; 1 = 40. l OJo
1-12 ¿Cuáles son los cortantes de piso en la dirección N/S del edificio del ejemplo 1-77
)·13 Un elemento estructural está sometido a 1 x 106 ciclos de esfuerzos de carga. La fuerza axial
máxima es 640 kN Yla mínima 320 kN. Si los esfuerzos axiales permisibles son 150 y 99 MPa para tensión y compresión respectivamente, ¿qué área en m2 se requiere para satisfacer tanto los esfuerzos permisibles como los requerimientos de fatiga? Supóngase que la tercera columna de la tabla 1-4es aplicable a este miembro.

<!-- p. 70 -->

o) b)

Figura n-} Dos de los edificios más altos del mundo, se usan estructuras de acero. (o) El edificio
Sears Tower en Chicago, IIIinois, con una altura de 1450pies (442 m), es actualmente el edificio más
alto del mundo. (b) El edificio John Hancock Center, también en Chicago, IIlinois y con una altura de
337 m. Vista desde la Sears Tower.

<!-- p. 71 -->

CAPITULO
DOS
ELEMENTOS DE DISEÑO DE MARCOS,
ARMADURAS Y PUENTES

2-1 METOnOS DE ANALISIS

Para diseñar cualquier estructura se necesita determinar las fuerzas en los marcos
(esfuerzos axiales, cortantes y flectores) basados en las cargas muertas y en las
combinaciones críticas de carga muerta y viva.
El método de análisis depende de la complejidad de la estructura y de que ésta sea estáticamente determinada o indeterminada. Al efectuar el análisis, se
puede considerar la estructura como bi o tridimensional. Las estructuras simples
son por lo general determinadas; esto es, son suficientes las tres ecuaciones de la
estática C'I:,Ph, 'I:,Pv, 'I:,M= O) para obtener las fuerzas internas de los miembros. En
las estructuras simples, se supone que los extremos de los miembros no transfieren la resistencia a momento a los miembros adyacentes. Las fuerzas internas
de los miembros en las estructuras determinadas se obtienen fácilmente mediante
el cálculo manual y con considerable eficiencia usando calculadoras de bolsillo.
Las estructuras rígidas son por lo general indeterminadas, puesto que los
extremos de los miembros transfieren fuerzas cortantes y momentos a los miembros adyacentes. Las estructuras indeterminadas requieren la compatibilidad
de deformación para suplementar las ecuaciones de la estática para determinar
las fuerzas internas de los miembros. Se usan las computadoras digitales para
obtener soluciones para todas las estructuras indeterminadas, con excepción de
las más sencillas. Para las vigas continuas y algunas estructuras simples de marco

71

<!-- p. 72 -->

72 ELEMENTOS DE DISEÑO UE MARCOS, ARMADURAS Y PUENTES

rígido se tienen soluciones que se pueden hallar en los manuales (o deducirse con
facilidad usando métodos de la resistencia de materiales). Se presentan algunas
soluciones para vigas, en la Parte IV del SSDD, en el manual de la AISC, yen la
mayoría de los manuales de ingeniería.
Una parte fundamental del diseño estructural es establecer si la estructura ha
de ser rígida o simple. Un marco rígido proporciona por lo general menores momentos de diseño, pero casi nunca resulta en un diseño más económico. Esto se
debe a:

l. Consideraciones prácticas de control de calidad y diseño de conexiones rígidas
contra simples.
\2. La tendencia a utilizar vigas del mismo peralte a través de varios claros, aun-
que algunos de éstos sean más cortos o soporten menos carga.
\3. El uso de un tamaño constante de columna a través de cuando menos dos pisos
ya menudo tres o más, para reducir los empalmes. Como la columna es la que
resiste la mayor carga, resulta sobrediseñada en el piso superior (o en los pisos
superiores).

El método de análisis por rigidez (anteriormente conocido como método de
deflexión y pendiente) es el que se usa más comúnmente para el análisis estructural indeterminado, usando la computadora digital. Este método se adapta particularmente al uso de la computadora, ya que la matriz es siempre poco densa y simétrica. Se puede aprovechar la simetría para reducir el esfuerzo de inversión, de
modo que se puedan obtener económicamente rápidas soluciones de problemas
de muy grandes dimensiones.
Todas las soluciones de las estructuras indeterminadas son repetitivas y generalmente no son únicas a causa de que la salida depende de la entrada de datos o
dicho de manera diferente, es necesario conocer las propiedades de los miembros
(área, A; momento de inercia, J) a fin de obtener compatibilidad de desplazamiento. Como se puede obtener la salida de una computadora digital en forma
rápida, se puede iniciar el problema usando valores relativos de A e J, y usar
luego esta salida para seleccionar miembros preliminares y repetir el proceso según se requiera. Cuando la entrada es considerable, y donde los marcos contengan gran número de miembros, puede que sea mejor usar métodos aproximados
de análisis para obtener dimensiones preliminares de los miembros. Uno de los métodos aproximados es simplemente suponer tamaños relativos de las columnas y
vigas (por ejemplo, A = constante, Jb = 1.2Jc u otros valores relativos). Se puede
usar la distribución de momentos junto con los valores relativos de A y de J, para
obtener dimensiones preliminares de los miembros (pero limitando su uso a no
más de dos o tres ciclos). Los métodos del portal y del voladizo para el análisis
aproximado de los marcos se puede usar para marcos dé edificios de uno o más
pisos. Estos dos últimos métodos se usan principalmente para obtener los efectos
de las fuerzas laterales (de viento) sobre un marco.
En el método del portal (ver figura 2-1) se hacen las siguientes suposiciones:

<!-- p. 73 -->

METODOS DE ANALlSIS 73

PI
4m 6 3

E
p(~) ~ l PI (2:) I 2A (3)'" p/~) =O.154PI A PI 2A
A=4+6+3=13

2 2 3 3 1.5 1.5 P2

M=O

11(PI + P2)

\~ (PI + P2) y
o
\~----+---------IJ

EMy = O(suponiendo que las cargas laterales no introducen fuerzas axiales en las columnas interiores)
VI = 1.2P2 + 3.6P I
13
'LF,,=O :.V2=J'1

Figura 2-1 Método del portal para el análisis estructural aproximado de un marco tipico de tres
claros.

\1. El punto de inflexión ocurre a la mitad de la altura de todas las columnas.
\2. La suma de las cargas de viento (lateral) se distribuye como fuerzas cortantes
en proporción al ancho del claro correspondiente.
\3. El momento de la viga o trabe es cero a la mitad del claro.
\4. Las columnas interiores no soportan cargas axiales.

Con estas cuatro suposiciones y la aplicación de la estática, se pueden obtener los momentos en las juntas.
El método del voladizo (figura 2-2) es un método alternativo de análisis aproximado para edificios altos con H/W :::; 4 ó 5, con las siguientes suposiciones:

\1. Los puntos de inflexión son los mismos que los del método del portal -punto
medio de vigas y columnas.
\2. Hay cargas axiales en todas las columnas y son proporcionales a la distancia
del eje neutro del marco considerado como una viga vertical en voladizo. La

<!-- p. 74 -->

74 ELEMENTOS DE DISEÑO DE MARCOS, ARMADURAS Y PUENTES

4m 6m 3m
f,v;

O
NA. r,'\<l: '\<l:r\<
VI 6.75 I
2.75 3.25 I
3 ¡ 3
¡f V; Ví =l- r~ O L/' y

V¡ V2 V)

r,

\~Mo = AX (se supone que las áreas de las columnas son constantes)
X=4A+IOA+13A =6.75
A+A+A+A m
1 = 6.75 2 + 2.75 2 + 3.25 2 + 6.25 2 = 102.75
My =3.6P¡ + 1.2P2
V¡=MyX
1
My(6.75)
VI = 102.75 = 0.0657 My V2 = 0.0268My V) = 0.031611.1'
) = O 1'4 = 0.0608M,.~( VI + V2 - V) _ V4

Figura 2·2 Método del voladizo para el análisis estructural aproximado del marco típico de una
estructura.

situación del eje neutro se basa en las áreas de columnas (como por lo general
estas áreas no se conocen, se usa comúnmente un valor de A = 1de área unita-
ria). El momento de inercia equivalente se calcula como

Las cargas de la columna se calculan como

Me
V;=¡

<!-- p. 75 -->

ANALISIS DE VIGAS 75

donde M = suma de los momentos de volcamiento por encima del punto de
inflexión.
e = distancia del eje neutro del marco a la columna i
1 = momento de inercia del marco considerado como I:Ad2

Las estructuras que son asimétricas en planta pueden estar sometidas a
efectos de torsión a causa de las fuerzas laterales. Se puede realizar un análisis
de torsión similar al método del voladizo, usando una constante de torsión, J
\= AI:(x2 + y2), en lugar de 1, donde se obtendrá la fuerza de torsión como

F = Te
1 J
donde T = Momento de torsión con respecto al eje neutro (vista en planta).
e = Distancia radial desde el eje neutro a la columna i,

2-2 ANALISIS DE VIGAS

Las vigas son miembros generalmente colocados en posición horizontal y que soportan una carga vertical. Esta carga vertical se puede distribuir en todo el claro o
aplicarla sólo en un segmento del mismo. Si la carga se distribuye sobre un segmento muy corto del claro, se considera como carga en un punto.:Para producir
la acción de la viga, la relación lid (véase figura 2-3H) debe ser mayor de 4 ó 5,
de otro modo las cargas se transfieren a las reacciones más bien por arqueamiento
que por cortante. La relación w/d debe también ser suficientemente grande para
desarrollar flexión más bien que torsión en la sección. La estructuración del piso
y la dirección en que se usarán las viguetas de piso afectarán a las trabes y vigas
que constituyen la estructura principal. Las viguetas de piso llevan las reacciones
extremas concentradas a las vigas de piso, pero es común, donde hay más de tres
viguetas en un claro, suponer una carga uniforme. La diferencia en los momentos
flectores para una supuesta carga uniforme, w, en lugar de tres cargas iguales, P,
se obtiene como sigue:

3P w=-
L
M _ wL 2 _ 3P L 2 _ 3PL
w-g-LS--S-

Las cargas concentradas producen un momento de

3P L PL PL M -----=- e 2 2 4 2

<!-- p. 76 -->

76 ELEMENTOS DE DISEÑO DE MARCOS, ARMADURAS Y PUENTES

A /fh
(a) (b)

/797 d-f7 /797 /797 /fh
(c) (d)

/797 /797
(e)

/fha 3
(j) (g)

\1'

(11) 1 1Ud
Figura 2-3 Vigas. (a) Viga simple en voladizo. (b) Viga simplemente apoyada. (e) Viga simplemente
apoyada con voladizo. (d) Viga continua de tres claros. (e) Viga continua con voladizo. (j) Viga apun-
talada en voladizo. (g) Viga con extremos fijos o empotrada. (h) Tanto Lid como wld deben ser cantidades razonables para que se pueda desarrollar la acción de la viga y para evitar la torsión de las secciones de vigas delgadas y con un gran peralte.

El error es [(0.5 - 0.375)/0.5](100) = 25 por ciento (demasiado pequeño). El error
disminuye y cambia de signo rápidamente según aumenta el número de cargas
concentradas (nótese que la situación es tal que la carga total de la viga es una
constante y que no aumenta con el número de cargas). Por ejemplo, si la carga total es constante, 3P, y se coloca en cinco espacios iguales, el valor de M; seguirá
siendo 3PL/8; el valor de Me será 9PL125.
Las vigas pueden ser simplemente apoyadas, voladas, en voladizo, fijas, o
continuas, como se ilustra en la figura 2-3. El diseñador tiene siempre que hacer
suposiciones que involucran las cargas concentradas en puntos fijos, así como
con respecto a cuán realistas serán los modelos de las vigas fijas, en voladizo o
continuas respecto a la geometría real del miembro. Casi nunca es posible y nunca
deseable tener realmente puntos de aplicación de cargas ó reacciones, aunque es
común hacer esta suposición en todos los métodos de análisis.
El proporcionamiento de las vigas se puede efectuar tan pronto como se obtengan los diagramas de cortante y momento. La ecuación diferencial general para una viga es
Elyiv = - W

<!-- p. 77 -->

ANA LISIS DE VIGAS 77

y sucesivamente:

E/y'" = V = cortante = - wx + CI
\-wx 2 E/y" = M =momento= -2- + Clx + C2

\- wx 3 C I X 2 E/y' = pendiente = -6- + -2- + C2x + C3
\- wx 4 C I X 3 C2X 2 Ely = deflexión = M- + -6- + -2- + C3x + C4

La ecuación general de la curva elástica de una viga produce cuatro constantes de
integración. Las constantes C2y C4 = O, para vigas simples, y el término w es cero
para las vigas cargadas con cargas concentradas.
La ecuación general de la viga a menudo resulta útil en cuanto se puede obtener de manera aproximada la información apropiada sobre la viga, al sustituir
una serie de cargas concentradas por el valor equivalente de carga uniforme.
Es frecuente limitar las deflexiones de las vigas, tanto en edificios como en
puentes. En los códigos de construcción se pueden hallar valores desde L/360
hasta valores tan bajos como L/l 000, dependiendo del uso y/o el acabado interior. Donde se suministran criterios de deflexión las deflexiones aproximadas se
deben calcular antes de que avance mucho el diseño. El lector se debe dar cuenta
de que no son posibles los cálculos de deflexión con un alto grado de exactitud,
debido a la incertidumbre en lo que respecta a las cargas. También se debe notar
que la deflexión depende en grado sumo del momento de inercia -y que E es casi
constante en el acero. Por consiguiente, donde se estipule un criterio rígido de
deflexión, puede que no sea económico el uso de acero de alta resistencia, puesto
que el tamaño de la sección puede quedar determinado por el momento de inercia
más bien que por el esfuerzo de flexión.

Techo
,f;Techo
\-SZ\? S:7ZSZ ...J:--VigaW

Vigueta de celosía '

Columna tubular
Muro de carga
Muro de bloques

Figura 2-4 Sistemas de muros de carga para edificios de un solo piso.

<!-- p. 78 -->

78 ELEMENTOS DE DISEÑO DE MARCOS, ARMADURAS Y PUENTES

2-3 ESTRUCTURAS DETERMINADAS

Las estructuras del tipo de muro de carga son muy usadas en almacenes, edificios
industriales, talleres, y otras estructuras con bajas relaciones H/ W. En una
estructura de muro de carga, gran parte de la carga de techo la soportan los muros del perímetro (y a veces los muros interiores). Las viguetas del techo pueden
salvar todo el espacio cubierto y descansar sobre los muros exteriores, o apoyarse
en el muro exterior y en un sistema interior de viga de techo y columna, como se
ilustra en la figura 2-4. En cualesquiera de los casos, las viguetas son vigas simplemente apoyadas. La viga interior de techo puede apoyarse simplemente en las columnas, o constituir un sistema continuo sobre las mismas.
Las conexiones de viga a columna no pueden transmitir momento alguno en
los marcos simples. En la práctica, casi todas las conexiones de vigas y columnas
pueden, y lo hacen, transmitir tanto cortantes como momentos. Si la conexión
fuese flexible, se hará la suposición común de que sólo se transmite el cortante.
En el capítulo 8 se tratarán las conexiones con mayor detalle.

2-4 ANALISIS DE ARMADURAS

Las estructuras pueden ser determinadas o indeterminadas, dependiendo de que
se suministren más barras de las necesarias para completar exactamente una serie
de triángulos. Expresado en forma de ecuación, el número de barras para producir una armadura determinada es
n = 2) - R

dondej = Número de juntas
n = Número de barras
R =Número de reacciones
Si n' >n, la armadura es indeterminada; si n' \<n la armadura es inestable.
Las armaduras determinadas se optimizan con facilidad para el peso mínimo
ya que las fuerzas en los miembros dependen sólo de la geometría de la armadura.
Las armaduras indeterminadas no son tan fáciles de optimizar, puesto que las
fuerzas en los miembros dependerán tanto de la geometría como del tamaño de
los miembros. Las armaduras indeterminadas se usan comúnmente en donde
ocurren inversiones de esfuerzos, donde se encuentran condiciones asimétricas de
carga, y cuando se usan miembros extra para reducir la relación L/r de los
miembros principales que conducen la carga. Al controlar la relación L/r es po-
sible dictar la geometría de muchas clases de estructuras. En los casos en que la
relación L/r controla el diseño, es muy dificil obtener la optimización para el peso mínimo. Sin embargo, el lector debe tener presente que la armadura óptima (o
cualquier estructura), será aquélla que equilibra el peso, la fabricación, y la segu-
ridad total contra el costo total que pagará el cliente. El peso mínimo por sí solo
no satisface los criterios de "optimización".

<!-- p. 79 -->

ANALISIS DE ARMADURAS 79

Las armaduras determinadas se resuelven con facilidad en forma manual
usando el método de equilibrio de las juntas, o el alternativo del equilibrio de la
porción a la derecha o a la izquierda de un corte en la sección. Tanto las armaduras determinadas como las indeterminadas se resuelven fácilmente con cualquier programa de computadora del gran número de que se dispone actualmente.
El programa de computadora que se encuentra en el Apéndice de esta obra puede
ser usado lo mismo para resolver armaduras determinadas o indeterminadas. En
este programa seutiliza elmétodo matricial de análisis de la rigidez, como seindica
más adelante. Se supone que el alumno ha tomado o tomará pronto un curso
avanzado de análisis estructural, por lo que sólo se incluye un estudio breve del
método de la rigidez que se usa en el programa de computadora que aparece en el
Apéndice.
Haciendo referencia a la figura 2-5, la codificación de un elemento típico de la
armadura será como se indica, en donde el código P-X se refiere a los efectos nodales en un sistema de armadura en el que solamente las fuerzas PI hasta P4 inclusive son las que aparecen afectando al miembro designado con la letra i. La fuerza interna en el miembro i es F I , Yexiste para esta fuerza un correspondiente
desplazamiento axial el' Se define la pendiente del miembro como: cos a=HIL;
sen a= VIL; y L =(H2 + V2) -} . El equilibrio nodal en la notación matricial es
P=AF (a)

P2 I
L I v
H I
Xl------ J

Miembro de la armadura que conecta 2 nudos

Miembro de la armadura P2
\~p,
'J:.FH =0
PI + F¡ cos c s O
'J:.Fv =0
P2 +Flsena= O

Figura 2·5 Codificación de un elemento tipico de una armadura.

<!-- p. 80 -->

80 ELEMENTOS DE DISEÑO DE MARCOS, ARMADURAS Y PUENTES

Además, las deformaciones del miembro (e) se relacionan con los desplazamientos nodales en la forma siguiente

(b)

Las fuerzas en los miembros se pueden escribir como

F= Se = SATX (e)

Ahora bien, al combinar las ecuaciones (e) y (o), se obtiene

P = ASATX (d)

La ecuación (d) se puede invertir para obtener

(e)

La matriz P se basa en las cargas reales aplicadas a la estructura en los puntos nodales. Estos puntos nodales pueden ser juntas de la armadura o puntos a lo largo
de una viga o de un marco. La matriz S es una matriz de propiedades de los
miembros, y la matriz A es el puente entre las fuerzas nodales y las de los miembros y considera la geometría de la armadura (o del marco). La inversión de la
ecuación (d) suministra los desplazamientos nodales, ecuación (e), y se puede entonces usar la ecuación (e) para calcular las fuerzas en los miembros:

F = SATX

Los elementos generales de la matriz A, para cualquier miembro de una armadura son los cosenos directores:

\- cos a ] -sena
A j = cos a [ sen (l

La matriz S, para cualquier miembro; con área transversal A, longitud L, y E es

S = AE
1 L

Efectuando la multiplicación de la matriz, se puede obtener el SAT como

T AE SA j = T( -cos a - sena + cos a + sen a)

El producto de A x SA Tda la matriz de rigidez del elemento en la forma siguiente:

<!-- p. 81 -->

ANALISIS DE MARCOS RIGIDOS 81

EASA T = AE 1 L
\~ 1 2 3 4
1 cos2a +senacosa - cos2 a - sena cos a
2 +sena cos a +sen2 a -sena cos a -sen2a
3 -oos2 a -sena cos a cos2 a sena cos a

4 -sena cos a -ser?- a sena cos a ser?- a

Como se ve, esta matriz es siempre simétrica. Los elementos P-X se sitúan en el
lugar correcto al considerar las coordenadas X y P, mostradas en este caso como
1, 2, 3, Y4 en la matriz total (o global) de la armadura, y esto se realiza a su vez
para cada miembro de la armadura. Cuando se hayan incluído en la matriz todos
los miembros de la armadura, esta matriz se puede invertir para obtener los
desplazamientos nodales.
Las fuerzas nodales en las reacciones no originan fuerzas en los miembros o
desplazamientos nodales. Para tener esto en cuenta, la codificación de una armadura se hace de tal modo que todas las reacciones se codifiquen hasta el final,
usando el valor NP + 1 = NPPI, donde NP = número de valores P que se incluyen (dos por junta, siendo horizontal el primero de estos valores) hasta llegar al
valor de la reacción. Los otros nudos que se sabe tienen cero desplazamiento o rotación se deben codificar NPPl para reducir el trabajo de cálculo.
El alumno se dará cuenta que las reacciones se pueden calcular insertando un
miembro ficticio en cada reacción de rodillo y dos miembros ficticios en una articulación. Usando una longitud unitaria y una área A de una magnitud suficiente,
dará ~-o y la fuerza axial en el miembro será la reacción. Se puede evaluar el
efecto de los asentamientos en los apoyos usando un valor de AE/L y una fuerza
axial en el nudo, cuyo efecto sobre los miembros ficticios de:
e = ~~ = asentamiento del apoyo dado

La rotación en un apoyo requiere alimentar manualmente los momentos de empotramiento y los cortantes correspondientes como si fueran elementos de la
matriz P, basados en la rotación conocida. Los momentos calculados de los
miembros se deben corregir manualmente según se requiera para los momentos
finales en el extremo del miembro, de manera que el nudo esté en equilibrio estático.

2-5 ANALISIS DE MARCOS RIGIDOS

El análisis de un marco rígido es similar al de una armadura. Se tiene, como diferencias esenciales, que cada nudo tiene tres grados de libertad y el miembro tiene
un momento en cada extremo así como una fuerza axial.

<!-- p. 82 -->

82 ELEMENTOS DE DISEÑO DE MARCOS, ARMADURAS Y PUENTES

\~--1-.. Ps .. Xs

Nudo:
codificación P-X
PI

Figura 2-6 Elemento de un marco rígído para generar las matrices A. S, YEASAT de un elemento general.

El elemento resultante ASAT tiene una dimensión 6 x 6 en lugar de la 4 x 4 obtenida con el elemento de la armadura. Refiriéndose a la figura 2-6, las matrices A
y S para un miembro típico en un marco rígido son las siguientes:

l 2 3 ~
1 o 1 o
sen a sen ex 2 -cos a rt: L
cos a cos a 3 - sena --- --- L L
A=
4 O O 1

sen a sen a 5 cos a --- --- L L

cos a cos a 6 sen a -- rt: L

1 2 3 ~
1 EA/L O O
s- 2 O 4EljL 2EljL

3 O 2EljL 4EljL

<!-- p. 83 -->

ANALISIS DE PUENTES 83

La computadora genera las matrices de los elementos intermedios de SA T y
EASA T. La matriz total o global se construye por superposición a partir del elemento EA SA T. La codificación P-X sitúa los elementos ASA T en la matriz global.
En la figura 2-7 se muestra la codificación de juntas que contienen discontinuidades o simultáneamente miembros de armaduras y de marcos rígidos.

2-6 ANALISIS DE PUENTES

El análisis de los puentes es similar al de las armaduras o vigas de edificios, excepto que la carga viva es un valor móvil. Con una carga móvil es necesario emplear
líneas de influencia o desarrollar, alternativamente, la matriz de carga con esta última colocada en numerosos puntos a lo largo de la luz. Es igualmente conveniente, con las computadoras digitales, desarrollar la matriz de carga para varias posi-

\~IO ~~3 ~0=.~PP1
\~~ .......L:.~ -\<o)---"';'__---l..:o.l.-__~"""';--Y6 l
En la articulación: la misma translación, l7A777
para la rotación es diferente en cada lado
NPE(i) de la viga
Miembro no. NPEU) _
I 10 10 3 4
2 346 7 la

Miembro no. ,VPEU)
26 26 26 l 2 3
2 2 3 4 5 6 L2
3 3 7 8
4 5 6 7 8

26
Figura 2-7 Codificación de estructuras con discontinuidades o que contienen simultáneamente vigas y
miembros de armaduras.

<!-- p. 84 -->

84 ELEMENTOS DE DISEÑO DE MARCOS. ARMADURAS Y PUENTES

ciones de los vehículos y obtener directamente las fuerzas en los miembros. Se diseña entonces el miembro para la fuerza crítica del miembro, obtenida por inspección de la matriz de fuerzas en la salida de la computadora. Sin embargo, se debe
tener muy en cuenta que la carga de impacto, así como la carga muerta se ha de
usar como parte del diseño. Queda a juicio del diseñador el decidir si el impacto
y/o la carga muerta se incorporan directamente a la matriz de cargas vivas para
producir de manera directa las fuerzas de diseño en la matriz de salida, o si se
combinan manualmente los diversos efectos. Obsérvese también de que el factor
de impacto puede depender del miembro que esté en proceso de diseño.

2-7 EL PROGRAMA DE COMPUTADORA QUE SE PRESENTA
EN EL APENDICE

El programa de computadora que aparece en el Apéndice se puede utilizar para el
análisis de cualquier marco rígido, o armadura o combinación de armadura y
marco rígido bidimensionales. Se puede usar para estructuras de vigas y columnas
yes particularmente eficaz para vigas continuas. Es necesario dibujar la estructura a escala aproximada y codificarla de manera apropiada (teniendo en cuenta al
codificar el tipo de elemento estructural de que se trate) a fin de determinar el número de entradas P-X (NP) y las que definen las reacciones (NP + I = NPPI),
donde los valores de X (o desplazamientos) son cero. En esta etapa también se determina el número de miembros (NM). Las distancias horizontales y verticales de
un extremo al otro de cada miembro se obtienen de la geometría del edificio. El
programa calcula la longitud real del miembro, usando como datos de entrada los
valores H y V, obtenidos de esta etapa.
Si se dan como entrada los valores correctos del área de la sección del
miembro, A, y el momento de inercia, 1, los desplazamientos (matriz X) resultan
ser valores reales. Si se usan valores relativos (o incorrectos), los desplazamientos
no serán valores verdaderos (en muchos casos hasta las fuerzas de los miembros
pueden ser incorrectas). Las fuerzas de los miembros de una armadura isostática
se pueden obtener usando cualquier área (úsese una área = 1.0 para que el
programa no vaya a dividir por cero), pero ahora también, los desplazamientos
sólo serán correctos si se usó el área correcta del miembro. El momento de inercia
no se usa en los cálculos de armaduras articuladas, determinadas o indeterminadas. Las fuerzas de los miembros en las armaduras indeterminadas dependen de
las áreas de sección de los miembros. Las fuerzas de los miembros en marcos
rígidos dependen, tanto del área de la sección como del momento de inercia; por
consiguiente, siempre será este un problema iterativo, ya que habrá que usar valores iniciales estimados, obtener un resultado, revisar la estimación inicial si fuera
necesario, y efectuar los ajustes que se requieran.
Si se desea obtener las deflexiones de las vigas de piso (o las deflexiones a lo
largo de un puente de carretera), sólo es necesario añadir nudos en esos lugares,
como se indica en la figura 2-8. Aunque el añadir nudos aumenta el tamaño de la
matriz que se ha de invertir, en la rutina usada en este programa de computadora

<!-- p. 85 -->

EL PROGRAMA DE COMPUTADORA QUE SE PRESENTA EN EL APENDICE 85

JI 8 t}-
3 PIO ·XIO

4 7
\P= 3'6
20 23 ,VPPI =39 t;.
10 " /VM= 21 ,\'BA,'\'D = 15 I + I = 15
11 14 Miembro 4
Para el miembro 14
¡\'EA.\'D =36 - 22 + I = 15 32 -t}. 35
28 31 17 34

18 19 20 21
\~ 39 39 39 39 t;: t; 37 39 38 r;.39

(a)

P2 - X 2 6 10

L5 L9 NP= 13 LI 6 NPPI = 14
NM= 13
7 9 12
3 11
14 14
2 4 10 13 G L 13

11 7 3 t. L L
Calcúlese NBAND: Miembro 5: 8 - I + I = 8
(b)

NP= 10 NPPl = 11 NM=5 NBAND = 5 - 2 + I = 4 (miembro 2)
\~ ~II ~II ~II ~11 ~ 11
1 4 , 2 , 4 I 5 ::I!L!0 3//iJ 1I1
l, Claro = L ·1
(e)

Figura2-8 Codificación de diversas estructuras. (o) Codificación de un marco rigido con bases de columnas tanto articuladas como fijas. (b) Codificación de una armadura. (e) Codificación de una viga
a través de un solo claro. Nótese que es convencional despreciar los cambios en la longitud de la viga,
por tanto estos valores P- X se convierten en NPPI. Esta codificación proveerá momentos f1ectores
en cada nudo, así como la pendiente y deflexión vertical de la viga. Se puede usar esta configuración
para las cuerdas inferiores de las armaduras de puente o las vigas de puente con los nudos situados en
el lugar donde las vigas transversales de piso se conectan con la cuerda o con la trabe.

<!-- p. 86 -->

86 ELEMJ;:NTOS DE DISEÑO DE MARCOS, ARMADURAS Y PUENTES

(un método de reducción de banda), se usa solamente una parte de la matriz global, de modo que problemas de muy grandes dimensiones se pueden resolver con
gran eficiencia. Para aprovechar hasta el máximo este método de reducción, la
codificación debe ser la apropiada para que la diferencia entre el valor PI en el
extremo más cercano y P4 (para armaduras) ó P6 en el extremo más lejano sea la
más pequefía posible, ya que esta diferencia [NBAND = NPE (4 ó 6) - NPE (1)
\+ 1]establece el tamaño de la matriz que se ha de reducir. Nótese que NBAND es
sólo 4 en la codificación de la viga ilustrada en la figura 2-8. Esto significa que
es posible usar un gran número de segmentos de viga, o alternativamente, un puente continuo con cinco o seisclaros y 15a 20 nudos/luz se puede resolver fácilmente
usando una cantidad muy pequefía del núcleo de la computadora, puesto que el
valor de STIFF (1) es NBAND x NP = 4 x NP; con NP = 100 hay sólo 400
entradas STIFF (1) versus 100 x 100 = 10 000 entradas para la inversión de una
matriz estándar. El tiempo de resolución se reduce a aproximadamente 1/10 del
de la matriz 100 x 100.

2·8 LA MATRIZ P

La matriz P se desarrolla a partir de las cargas de la estructura, considerando cada elemento finito ya sea como elemento de la armadura que sólo tiene fuerzas en
los nudos (sin flexión) o como un elemento de viga basado en la estática y de las
fuerzas externas aplicadas al miembro, como son las cargas de viento, del techo y
de las ruedas. Se debe observar que las cargas de las ruedas entre los paneles de
la armadura se prorratean a los nudos adyacentes usando un sencillo análisis de la
viga, como si este miembro de la armadura fuese una viga con las reacciones en
los nudos.
Los elementos finitos que componen una viga se consideran como una serie
de vigas con extremos fijos; de este modo, las entradas de la matriz P incluirán la
suma de los momentos de extremos fijo (MEF) de los diversos elementos de las vigas que se encuentran en una junta, además de los esfuerzos cortantes, como se
muestra en la figura 2-2.
En los análisis, tanto de vigas como de armaduras, las fuerzas en los nudos
(iguales y opuestas a las que actúan sobre los elementos conectados) se convierten
en componentes paralelas a las traslaciones Pi'
Cuando se analicen vigas y vigas-columnas (fuerza axial y flexión), es conveniente hacer que el programa de la computadora calcule los MEF y los cortantes de
los varios elementos de la viga usando la carga de la viga, y efectuar el proceso
de suma según se vaya encontrando la contribución que cada elemento hace a un
nudo, y a continuación construir la matriz P. El programa debe aceptar también
la lectura de entradas adicionales de la matriz P, las que se pueden usar y/o afíadir a los valores que ya están dentro de la matriz P. El programa de computadora
del Apéndice permite utilizar este procedimiento.
El alumno debe tener en cuenta, al usar el programa de la computadora para
desarrollar las entradas de la matriz P, que todas las cargas muertas y vivas se

<!-- p. 87 -->

LA MATRIZ P 87

aplican a lo largo de la longitud del elemento viga en la dirección de la gravedad
usando un signo (+). Esto permite al programa calcular correctamente las entradas (y signos) de la matriz P para vigas inclinadas.
Las cargas de viento para las vigas inclinadas, horizontales y verticales, se
aplican siempre a lo largo y normales al eje del miembro. Si la pendiente es O
\~ O~ 30°, el signo por lo general será (-) debido al efecto aerodinámico (succión).
Esto permite al programa desarrollar la matriz P para la NLC del viento. Como
las cargas de viento y gravedad a lo largo de un miembro no se pueden combinar
debido a la existencia de una componente horizontal del viento en un miembro
inclinado, conviene almacenar el análisis de D + L (o D solamente) y tratar el caso del viento totalmente por separado, para luego combinar el viento con el análisis de D + L para obtener el caso de diseño para D + L + W. Las especificaciones permiten aumentar el esfuerzo permisible del acero en un tercio, para cualquiera condición de esfuerzo, incluyendo el viento (siempre que el miembro resultante no sea menor que el adecuado para el caso de D + L separadamente). Este
aumento del esfuerzo equivale a reducir las fuerzas del miembro, incluyendo el
viento en un 25 por ciento (fuerzas axiales y momentos). El programa de la computadora también lo puede hacer, de modo que el diseñador obtiene meramente
la fuerza axial máxima y/o el momento a partir de cualesquiera de las NLC de diseño de dicho elemento. Para aprovechar la capacidad del programa para efectuar esta operación, es necesario poner la NLC del viento (usando la NLW) después de la NLC de la carga D + L. Este procedimiento se ilustra en los varios
ejemplos que muestran los resultados de la computadora. El lector debe inspeccionar en particular la entrada y salida del Ejemplo 2-7, que usa la presión del
viento sobre un elemento inclinado de viga.
La codificación de NP y notando que NP + 1 = NPPI para especificar cero
desplazamientos (incluídos pero no limitados) para las reacciones excluye de la
consideración a esas entradas de la matriz global. Esas entradas de la matriz P desarrolladas por la computadora para P (NPPl) no se usan en el análisis. El estudiante debe observar que estos valores se incorporan directamente a la reacción y,
por consiguiente, no producen fuerzas internas en los miembros (véasela verificación de la salida de figura E2-4d).
Una de las primeras decisiones que debe tomar el diseñador estructural es determinar si la superestructura (las columnas en particular) será articulada (lo que
permite la rotación) o rígidamente fija a la cimentación (no permite rotación) y
determinar si el miembro de dicha cimentación puede restringir la rotación. No
hay reglas fijas que permitan tomar esta decisión de diseño -cada estructura se
considera según sus propias características. Si la estructura es articulada, el método de conexión del miembro es por lo general diferente de cuando se trata de una
estructura rígida, lo que hace que se requiera suficiente diseño y análisis para desarrollar el momento calculado. Podría parecer razonable y apropiado, en el caso
de los edificios de oficina de los ejemplos 2-3 y 2-4, utilizar una conexión articulada al muro del sótano (es posible que este muro esté reforzado con pilastras en
dichos lugares). La utilización de conexiones articuladas en las columnas del sótano se puede dejar al criterio del diseñador, ya que la restricción de la rotación se

<!-- p. 88 -->

88 ELEMENTOS DE DISEÑO DE MARCOS, ARMADURAS Y PUENTES

puede obtener más fácilmente en esos lugares aplicando la geometría indicada para las cimentaciones.
Ejemplo 2-1. Muéstrense las entradas de la matriz P para las 2 NLC (carga
móvil) para la armadura mostrada parcialmente en la figura E2-la.

4 l. 4m >l' S .1 FiguraE2-la
SOLUCION Considérese la viga fija que se muestra en la figura E2-lb: Para
el nudo 4:
Nótese que RR es opuesta en dirección a PIS' que se ha definido como ( +).
Por consiguiente, la matriz P (y también para las otras condiciones de carga)
será:

NLC
p 2

10 o O
11 -10 O

14 O O
IS -8 -18 10t

Figura E2-lb III
Ejemplo 2-2. Muéstrense las entradas de la matriz P para el marco de dos
miembros de la figura E2-2a.

72 kN

(2)

NP=6
NM = 2
NPPI = 7

6m

Figura E2-2a

<!-- p. 89 -->

LA MATRIZ P 89

SüLUClüN Es necesario deducir las ecuaciones necesarias para los MEF de
los miembros inclinados. Refiérase, para esta deducción, a la figura E2-2b y
obsérvese que las cargas normales al miembro producen MEF. Volviendo
ahora al problema inicial, para () = 45° en el miembro inclinado:

FEM = 12(0.70711)( 6 )2 = 5091 kN .
12 0.70711 . m

6
RL = RR =(12) 0.70711 (0.5) = 50.91 kN

p

50.91 kN( .....------..l
601
Figura E2-2b 50.91 kN Figura E2-2c

Para el miembro horizontal:

R{ = 4(~2) = 48.0 kN RR = 2(~2) = 24.Q kN

FEMi = Pab 2 = 72(2)(4)2 = 64 kN. m
L 2 62

FEM~ = Pba 2 = 72(4)(2i = 32 kN· m
L 2 62

Considérese ahora el dibujo siguiente para los nudos 1, 2, Y3:

P3 = O
P2 = 64 - 50.91 = 13.09(nótese +)
P4 = - (50.91 + 48.0) = -98.91 kN

<!-- p. 90 -->

90 ELEMENTOS DE DISEÑO DE MARCOS, ARMADURAS Y PUENTES

P4
50.91 64 ~ 64 32
(f-t~ :1\ (f)64
50.91 50.91 48 k L8
50.91

p NLC=I

1 +SO.91
2 +13.09
3 O
4 -98.91
S -32.00
6 O
7 (NPPI) -(no tiene importancia)

III

2-9 CONDICIONES DE CARGA

En la mayoría de los análisis estructurales se encontrarán diversas combinaciones
de cargas que deben investigarse para hallar aquella combinación que produzca
las mayores fuerzas internas en los miembros. A cada combinación de cargas,
muertas o de otro tipo, se le llama condición de carga (NLC en el programa de
computadora). Las condicionesde carga producen las cargas en los nudos que forman la matriz P en la ecuación

Las diversas condiciones de carga para un marco rígido o una armadura en un
edificio industrial podrían incluir:

Combinación de cargas NLC

Muerta + viva 1
Muerta + viva en crujías alternas 2
Muerta + viva + nieve 3
. l. 4 M uerta + viva + "2meve
Muerta + viva + nieve en un lado + vientoS
Muerta + viva + viento 6

<!-- p. 91 -->

REVISION DE LA SALIDA DE LA COMPUTADORA 91

Las varias condiciones de carga para un puente incluirian

Carga muerta
Carga muerta + carga viva, incluyendo impacto
Carga muerta + carga viva + carga de viento

La carga viva constituye en realidad un problema de lineas de influencia, debido a que los esfuerzos en los diversos elementos del puente dependen de la posición de la carga. Un método muy práctico consiste en construir una matriz P para
carga viva, poniendo en posición a lo largo del claro del puente las cargas H o HS
de camiones o las Cooper de ferrocarriles, a intervalos de aproximadamente 2 ó 5
pies. Se puede usar para esto un programa de computadora, con la salida en tarjetas perforadas de un formato apropiado para usarlas en el programa de computadora de la sección anterior.
El impacto y la combinación de cargas muertas y cargas vivas se puede automatizar por medio de una programación por computadora; sin embargo, puede
que el impacto no sea constante para todos los elementos de un puente, y como el
impacto se aplica sólo a las cargas vivas, el diseñador deberá usar su criterio para
determinar la manera más eficaz de combinar las cargas muertas y vivas además
de los efectos de impacto para obtener la fuerza de diseño para el elemento dado
del puente. Esta es una consideración que justifica un análisis inicial muy cuidadoso, ya que puede haber de 40 a 60 condiciones en puentes de gran longitud debido a la carga viva, y será preciso escrutar la salida de la computadora a fin de
obtener la fuerza máxima en cualquier elemento entre todas las condiciones de
carga.
En el Apéndice se incluyen programas de computadora para desarrollar la
matriz por medio de tarjetas perforadas, para efectuar el análisis de una armadura de puente, carretera o de ferrocarril.

2-10 REVISION DE LA SALIDA DE LA COMPUTADORA

Es esencial verificar la exactitud de la salida de la computadora.
En esta verificación hay dos etapas básicas:

l. Se revisan siempre los datos de entrada de los miembros y cargas, por errores
en el punto decimal. Si se comete un error al perforar la codificación P- X, el
programa podrá o no operar, dependiendo de que NP sea tan grande que
sobrepase la DIMENSlüN de la matriz de rigidez o de que el efecto de super-
posición contribuya a la colocación incorrecta de la matriz global. Nótese que
es posible efectuar un análisis correcto con datos incorrectos de un miembro,
como A o l. Se puede efectuar un análisis "correcto" con datos incorrectos de
la longitud de un miembro. Este tipo de análisis correcto por lo general satis-
fará las verificaciones estáticas.
\2. Se efectúa siempre una verificación estática en puntos determinados y/o
EFh y EFv = Opara toda la estructura. Por lo general, sise verifica un nudo cer-

<!-- p. 92 -->

92 ELEMENTOS DE DISEÑO DE MARCOS. ARMADURAS Y PUENTES

ca del comienzo y otro cerca del final de la secuencia de codificación y ambos
satisfacen las condiciones estáticas, se habrá resuelto correctamente el proble-
ma para esos datos de entrada.

Se pueden verificar los problemas de diversas maneras, como se ilustra en los
ejemplos que presentan la salida de las computadoras. En general, se debe revisar
primero una esquina, donde los momentos extremos de los dos miembros concurrentes deben ser iguales y opuestos (dentro del error de aproximación de la
computadora), ya que dicha revisión se puede efectuar con un mínimo de esfuerzos de cálculo -a menudo por inspección. Las fuerzas acumuladas por encima
de un piso resultan a menudo convenientes, ya que se suministran directamente las
fuerzas axiales sobre las columnas. A veces se puede aprovechar la simetría de la
estructura y de las cargas, como sucede en los ejemplos de edificios de oficinas
que aparecen a continuación (sin carga de viento). A veces se puede usar provechosamente la matriz X, como se ilustra en la revisión de las columnas del edificio de oficinas.
La revisión de las armaduras es similar a la de los marcos rígidos. Siempre se
debe aprovechar la geometría de la armadura, al verificar los miembros en los que
se sabe que la fuerza interna es cero. Si la salida de la computadora no resulta
igual a cero y la matriz de carga es correcta, seguramente que algo andará mal con
los datos de entrada, como la perforación equivocada de un NP, o una falta de
concordancia entre H y V (ya sea en la longitud o en los signos). Efectúense verificaciones de estática cerca de cada uno de los extremos de la armadura donde se
conecta un mínimo de barras. Si estas juntas no satisfacen el equilibrio estático
tampoco lo harán las juntas más complicadas y es necesario reprogramar el
problema.

2-11 EJEMPLOS DE DISEÑO

Los varios ejemplos de diseño que aparecen a continuación ilustrarán aún más la
codificación de los marcos y la entrada y la salida de la computadora para el
programa de análisis por computadora que aparece en el Apéndice. Los resultados de la computadora obtenidos para esos ejemplos se usarán en muchos de los
ejemplos de diseño de los capítulos subsiguientes, para ilustrar los problemas en
el diseño estructural de acero de manera algo parecida a la que tendría lugar en el
diseño actual. A fin de ahorrar espacio en el texto y mantener el interés del lector,
los ejemplos están considerablemente condensados, comparados con los problemas reales de diseño.

Ejemplo 2-3. En la figura E2-3a se muestra la planta y elevación de un pe-
queño edificio de tres plantas para uso de oficinas. Se usarán contravientos
en la dirección E-W (en las crujías y en los lugares marcados cv) junto con
un simple esquema estructural. Se usará un marco rígido en la dirección N-S
(con los consiguientes momentos en los extremos). El acabado exterior de
ladrillos estará soportado por vigas de dintel que conducirán la carga a las

<!-- p. 93 -->

EJEMPLOS DE DISENO 93

columnas exteriores y a cada piso. El tipo de estructuración permite un
corredor entre las columnas interiores con espacio libre para las áreas de
oficina. El espacio rentable será en bloques: a, b, e, etc. Este espacio con-
tendrá muebles diversos de oficina, canceles, etc., basados en las necesidades
y deseos del que renta. Las condiciones de entrada y salida para los tres pi-

21'·4" 7'·6" 21'·4"
1- ,,1" ,,~ -1 I I 2 3 2 3 4
(2) (3) N.:::;e (1)
No
(4) (5) (6) (7)
N \<U
'o.\<,
:!2 13,14,15 8
\~ 5 (8) 6 (9) 7 (10)
Ual
Z (11 ) (12) (13) (14) -¡¡
t:"O.... ,;;;)
00 ~ 25,26,27
12
e;: 9 (15) 10 (16) 11 (17)
';;\<U

"O \<U (18) (19) (20) (21 )
00¡¡¡'"
U 37,47,47 44,47,47
13 (22) 14 (23) 15 (24) 16 ~.
','
_NM '. Muro de concreto .' (25) (26) i¡...-- del sótano 46-NP=46
(47 NPPI=47 : .' . 17 45,47,47 18 47 " .
, [:;.'-'J lSJ ' '. '.
Elevación de un marco interior típico

5 Ca 18'·6" ,.
wb wb N ,. .-N

\~
1-- +
1-:..
N

wb wb

Vista en planta
Figura E2-30

<!-- p. 94 -->

94 ELEMENTOS DE DISEÑO DE MARCOS, ARMADURAS Y PUENTES

sos consistirán en una escalera en cada extremo además de un elevador de
servicio para equipos pesados que estará situado en el lado oeste del edifi-
cio. Para el aire acondicionado y la calefacción se utilizará una bomba si-
tuada en un cobertizo auxiliar que no se muestra en la figura. El sótano con-
tendrá el resto del equipo ambiental y proporcionará espacio extra para al-
macenaje. Se usará el NBC para el díseño'general.
Se usará un techo plano, que podrá utilizarse para que los empleados ha-
gan ejercicio durante el día. Considerando esta actividad adicional se diseñará
el techo para una carga viva de 80 lb/piel (en contraste con las 20 a 30 lb/piel
que se acostumbra para carga viva y/o nieve). El lector debe tener en cuenta
que los códigos de construcción y las especificaciones de materiales estipu-
lan requerimientos mínimos, de modo que el diseñador puede siempre usar
valores mayores.

SOLUCION La codificación general de la computadora se muestra par-
cialmente en la figura E2-3a y también en la figura E2-3d (hoja de salida de
la computadora). Esta codificación da la siguiente información sobre los
datos de control del programa de la computadora:
NM = (26 miembros) NP = 46 NBAND = 11
El paso siguiente es obtener las cargas de vigas y columnas para este marco
interior típico (refiérase a la figura E2-3b en que se muestran las cargas des-
pués de efectuados los cálculos).
Techo:
Carga muerta: se estiman 5 pulg de concreto sobre un tablero metálico
soportado por viguetas de celosía de acero.

Concreto: (5/12) 144 601b/pie2
Tablero metálico y viguetas (estimado) = 51b/pie2
Plafón, conductos, electricidad, etc. 5 lb/piel
Total = 70 lb/piel

Carga viva: revísese la reducción en los espacios de 21.3 x 18.5. Nor-
malmente, la carga viva del techo no se reduce; sin embargo no se está usan-
do una carga viva normal en el techo.

R = 21.3(18.5)(0.08) = 31.5 por ciento
D + L 70 + 80 . . o R = 433L (100) = () (100) = 43.3 por ciento . 4.33 80
Nótese que el valor L = 80 lb/piel se tomó de la tabla IV-4. Se usará una re-
ducción del 30 por ciento.

2 Carga viva = 80(1.00 - 0.30) = 56 lb/pie
En un claro de 7.5 pies, R = 7.5(18.5) = 138.8 piel> 150 (no hay reduc-
ción).

<!-- p. 95 -->

EJEMPLOS DE DISEÑO 95

Las cargas equivalentes de viga para el techo son:
Carga muerta = 0.070(18.5) = 1.295 kips/pie
Carga viva en el claro de 18.5 pies = 0.056(18.5) = 1.036 kips/pie
Carga viva en el claro de 7.5 pies = 0.080(18.5) = 1.48 kips/pie

Otros pisos:

Estímese la carga muerta con el aumento por el terminado
del piso yel acabado del plafón = 80Ib/pie2
Corredores (tabla IV y uso conservativo) = 100lb/pie-
Espacio de oficina = 80Ib/pie2

El espacio de oficina tendrá un 30 por ciento de reducción en la carga viva
pero no habrá reducción de carga viva en el corredor. Esto da las siguientes
cargas de viga:

Carga muerta = 0.080 (18.5) = 1.48 kips/pie
Carga viva en la oficina = 0.080(0.70)(18.5) = 1.036 kips/pie
Carga viva en el corredor = 0.10 (18.5) = 1.85 kips/pie

Estas cargas se muestran en la figura E2-3b.

El muro de ladrillos para el acabado exterior contribuirá con cargas de
columnas para los dos pisos superiores, como se indica en la figura. Los valores obtenidos son:
Obténgase el peso de un forro de ladrillos de 4 pulg (tabla IV-3) =
80/2 = 40 lb/pie- más el acabado interior del muro, accesorios, etc., de 5
lb/pie", que da un total de 45 lb/píe'.

Carga de columna = 12(18.5)(0.045) = 9.99 kips

Los muros longitudinales que definen el corredor y la viga longitudinal
contribuyen cargas a las columnas interiores:

Muro de azulejos, de 8 pulg = 35 lb/pie-
Viga de 50 lb/pie (estimada) = 50 lb/pie lineal
Cortante en la columna = 12 (18.5) (0.035) + 18.5 (0.050) = 8.695
kips
Para el techo = 0.050 (18.5) = 0.925 kips (columnas interiores).

Se desprecia cualquier peso de la viga que contribuya cortante a la línea
de techo de las columnas exteriores, puesto que ros valores son demasiado
pequeños para que sean confiables o que afecten el diseño.

<!-- p. 96 -->

96 ELEMENTOS DE DISEÑO DE MARCOS, ARMADURAS Y PUENTES

0.925
_. 775 _., 331 k'ips /nipie0.02(6)185 : 1 ips pre ~ l 1111.295 111 1.036 + 1.2950 p¡~~
\+ 1.48 :e:l 12frll10 :el
01 N
"'t..,-
o.015X12X 19.99 8.695kl 3.330 kiPS!pjel8.695k
18.5 : 3.33 k 2.516
111 1.48 + 1.036 L 111 11I 11I 1111 11I P14---t

,~:
·-1
\~I
:el '"- "'1 -1 ~9.99 8.695l 3.330 l8.695k 2.516 I
:PI4"-..L. 111 111 111 ,111
I
1
1 N 1
1
lS.695 ~9.99k 8.695 ~ 1 3.330 1 2.516 2.516 kips!pie
I 11 1 111 !1i 11I1 1I1 W~

(26) 1;-47 '"
37 47

21.3' 45 7.5' 21.3' ,.j\< >r .1 l.
Figura E2-3b Carga general sobre el marco.

Ahora se harán algunas estimaciones preliminares de las dimensiones
de los miembros, con las siguientes consideraciones prácticas:

\1. Se usarán columnas continuas (sin empalmes) en los 36 pies de altura to-
tal. (Se'podrían empalmar las columnas interiores a nivel del primer pi-
so).
\2. Usense vigas de peralte constante a través del marco.

Paralas vigas
Si la viga de techo está simplemente apoyada, el momento es M =
wL2/8, y si está empotrada, el momento es M = wL2/l2. El valor real es un
valor intermedio, y tomando promedio:
(1.036 + 1.48)(21.3)2 1427' ki M s = 8 =. pie- ps

<!-- p. 97 -->

EJEMPLOS DE DISEÑO 97

82
Mf = (142.7) 1 = 95.Ipie· kips
M av = 118.9, o sea 120pie' kips

El módulo de sección requerido, basado en un esfuerzo permisible de
flexión de 24 k/pulg- (capítulo 7), es

s = 120(12) - 60 I 3 x 24 - pu g
Usese WI6 X 40:
S, = 64.7 A = 11.80pulg- L; = 518.0 pulg"

Para las columnas:
Estímese un coeficiente de longitud K = 1.2 - KL = 12 x 1.2 = 14.4
pies. Estímese Fa = 16 k/pulg? (algo menor que 22 k/pulg-),

P aprox. = 0.925 + (8.695)(3) + 12.5(3) + (2.775) 7:} + (2.331) 2~.3
\+26.79(3) = 180.1 kips

En este cálculo se acumulan los cortantes de las vigas procedentes de las
contribuciones longitudinales + más las cargas uniformes de las vigas desde
el techo hasta el primer piso de una columna interior.

P 180.1 I 2 A 1 = - = -- = II 2 pu g co Fa 16 .
Usese W8 X 40:
A = 11.70 pulg- I, = 146 pulg"

Inspecciónese al azar para ver si está bien: Kl.rr, = 14.4(12)/3.53 = 49.
El esfuerzo permisible en las columnas = 18.5 k/pulg-; tomado de la tabla
11-5.
Se probará este valor para la primera repetición del diseño, ya que
habrá en las columnas momentos extremos de valor desconocido que
aumentarán P de manera efectiva. Se usará una sección menor para las columnas exteriores. Sea W8 x 31:
A = 9.13 pulg 2 Ix= 110 pulg 4
Para las dos columnas del sótano, se usará W8 x 48:

A = 14.10 pulg ' Ix = 184.0 pulg"

<!-- p. 98 -->

98 ELEMENTOS DE DISEÑO DE MARCOS, ARMADURAS Y PUENTES

J, J, Ir x ¡VI

0000 0000 0000 00
0000 ~~~c; 0000 ~c;
0000 0000 ooó~ 00
Rt>X j.¡,lj
\--..., .g -

Ot- X S.ti

00000000000000000000000000
00000000000000000000000000
00000000000000000000000000
0000000000000000000 0000000
\~c;c;~c;~~~c;c;c;c;c;c;c;c;~c;~c;c;~~c;~c;o o o ~ ~ ~ _ o o o__ ~ _ o o o ooo __
z 0000000000000000000000000000000000000000000000000000 ~ gggggggggggggggggggggggggg
c;c;c;c;c;~~~c;c;c;c;c;c;c;c;c;c;c;c;c;c;c;~c;c;___ O O O O ~__ O O O O ~ _ ~ C O O O Oo

00000000000000000000000 0 00
\~c;~c;c;c;c;~c;~c;c;c;c;~c;~c;c;c;c;~c;~c;c;
\~ N~o~.~·.~o~.~••~~~N •• ~.~v~••••N N ~o~~N~~~N ••••••• ~o~oo~~~e~N N __

_ ~~~O~~O~~~O~~~~~«O~~O~q~..........................••
\---- •• ----- •• ----- •• -~~~«~
\~~~----~~~----~~~----~~~--

ocoo~~cooo~~oooo~~oooo~~
OOOONN~aOOaaa~OoaaaaOOaa
\~~~~~~~~~~~~~~~~~~~~~~~~ ~~~:~~:~~~:~~~~~~:~~~~~~~~
; OOOoooaaoo~~aaoo~~aaoo~~ .. ---~--~---~--q---~--~-------- ._- ._-- -._-- ._- . oz
000000000000000000000000
000000000000000000000000
\~~~~~~~~~~~~~~~~~~~~~~~~
\~ 000000000000000000000000

00000000000000000000000000
000000000000000000000000 ~c;~c;c;c;c;~c;~~c;c;c;~c;~c;c;c;c;~c;~c;c;
000000000000000000000000
\~o~oooo~o~oooo~o~oooo~o~oo
\~~~ ~q~ ~q~ ~q~ ~~~~~~~~~~~~~~~~~~~~~~~~ 1
\~ 000000000000000000000000 N N N N N N N N
OOOO~OOOOOoOOOOOOOOOOOOO000000000000000000000000 ..Z~ ~qN~~q~~_.~~_.o~~~o~~o~~o~.~ __ NN __ NN~'~~N~~~•••••
\~~~~~~~~~~~~~~~~~~~~~~~~
\~ 000000000000000000000000

v"
000000000000000000000000 ~z .~o_.~O~qN~~aN~_.~«_.~_.~__ _ __ N NN~~NN~~~ •• ~ . . ~zo 000000000000000000000000 + ~~~~~~~~~~~~~~~~~~~~~~~~oo..""ce
\~ ooooooooooooooooooooo~oo
;~:~ ir vU N~2 N~~.~O"·4~0~UN~~qN~aN~~gN~~__ NN __ N~N~mNN~4~4•• ~44. z~"~ _ v ~~~~~~~~~~~~~~~~~~~~~~~~

\~ _.~~~UN~~U~~_.~«_~~_.~~_~~N NN~,~NN~r\~.4~~4 •• ~t~ z ~~~~~~~~~~~~~~~~~~~~~~~~NN~~N~NN~~NNNN~~N~NN~~N~ Z
De'CJzzz
C'I __ NN~~««q~~~~:~~::~~~::: .

<!-- p. 99 -->

\~o STIFFttt fNTPIE~ ~ 6"0 6ANO WIOTH • 15 P1 x)
T"'f P-MATPIX, K ANO K-IN "'Hf X-MaTA IX. IN OP RAOIANS

10~7.55 0.00~02 ~X 1057.55 ",o I = O. 003"~ I x, =
\~o 0.0~A7 0.~0556 = 0.00 7 NX 1.22 irP¡I 4. S. 6 1.8.9 P'O -2~. = ,2 0"5~1 -0.0"3~~ -210,. 83 8~ "4)( 3 = ~o = -O.
NI) = 4 -"Ol.~b -"Ol.~b I\IX = 4 -0.0016" -0.00IS7 11I
\~ 0.00 0.00 5 0.00033 NI' = = 0.3"96A l"
\-0.1"3~3 Nt) NI( -36.16 -36.16 6 -0.16673 = b ~t)( =
NO = 7 "01.~6 "01.~6 "-!)( = 7 0.0016" O.OOIAO
NO = P 0.00 0.00 /\IX e A -0.00033 0.39872 (4)
\~o = -36.16 -36.16 1\1)( = o -0.1"3~3 -0.1"8H ~o lO" -10~7.55 -1057.55 !\IX = lO -0.00394 -0.00386
NO :: 11 0.00 0.00 "IX = 11 -0.0~87 0.3"386
\-24."~ 12 -O.O""~I -0.0"738 -24.e:! NX " = 12 "'O 13.14.15 .23.24
ll~I.~A No NX :: 13 0.00272 0.00303 D lI~I.~A
\~o 14 0.00 3.33 N)( = 14 -0.00081 0.33816 (8) !IOI
\~o :: 15 -36.7'1 -~6.1q NX = 1" -0.OA302 -0.OAI22 11,10 = 16 -"5~.17 -OH.17 "J)( = lb -0.00121 -0.00101
\~o = 17 0.00 0.00 NX • 17 -0.00006 0.33683
\-0.172~" NO :: -~7."8 "JX :: lA -47.CJR l. -0.17721 !(1) 4)
"5~.17 95~.17 0.001~0 11,10 lO 0.00121 NX = 1" =
NO :: 20 0.00 0.00 NI( = 20 0.00006 0.33652
NO :: 21 -~7.Q8 -41.IQe N\< • 21 -0.17721 -0.181"~
\-11~1.4A -U~I.~8 -0.002~0 NO 22 N\< -0.00272 = .35.30 0.00 23 0.00 No 0.000A2 0.33687 NX = e= 2322
\-~6.1Q 2~ 2~ -0.08~83 NO • NX -36.7" = -0.08302 (11)
NO = 25 1I41.~A U~I.~P N)( = 25 0.00275 0.00335
NO = 26 0.00 3.~~ N)( = 26 0.00061 0.19A4~
\~p = 27 -36.7'1 -36.79 NX • 77 -0.05121 -0.04"'17
e 11,10 -"5~.I7 2A -'154" 7 NX :- 2. -0.00125 -0.00097 0.195'1~ 1) 20 NO 0.00 0.00 NX • = 0.00007 2"
\-~7 -~7."e -O.l~018 = NO 30 .'1. NX • 30 -0.13600
NO = 31 '15~.17 954.11 NX • 31 0.00125 0.00153
NI) :: 32 0.00 0.00 NX • 32 -0.00007 0.1"537
"JO = 33 -41.q~ -41.98 NX e 3' -0.140IA -0.14437
;\ID :: 34 -1"'1.~e -1141.4. 1\Il( = 3. -0.00275 -0.00216
11,10 = 35 0.00 0.00 I\IX :- 3' -0.00061 0.1"'33
\-0.052~5 -16.7'1 -36.7'1 ~I)( 36 = tTl'- 36 -0.05121 = 17 41 NONO :: 37 U41.48 1141.4A NX • 37 0.00353 0.003.7 ~ NO = 17 -'15~.17 38 -95•• NX • 3A -0.00136 -0.00123
.~ .... :: 30 0.00 0.00 NX 0.00023 • 3" 0.00194 1 '1:1
NO = '0 -47.'1e -47.ge NX • 40 -0.08232 -0.079"9 41 L.j--41
'15~.17 NO "54.17 NX • = '1 .1 0.00136 0.001'" 5r.n ~2 0.00 0.00 NX • NO = .2 -0.00023 0.00149 1--11 ,..0 = 4:-' -47.9~ -47."8 NX • 43 -0.08232 -0.08~75 CI
NO = '4 -U41.48 -U41.4. "Ix :: ~. -0.00353 -0.0031" tTl
NO :: 0.00 0.00 NX • 0.0006A '5 'S 0.00063 CI NO :: .6 0.00 0.00 NX • ~6 -0.0006e -o.ooon
\~z· Dibujo para identificar codificación P - X O
Figura E2·3d ~

<!-- p. 100 -->

lOAnp'm CONDITlON NO =
Des ICN eNO "OJl4ENTS CORRECTEO g "IEMRER: AXIAL ~OFlCEt K FIJR FE'" ,6NO WIND f NE,6R ENQ 1="~$T. t I(-FT Verificación estática de la salida NCL = I
\-6.07 -38.7J 82.1t2 Nótese la simetría de las cargas y salida al verificar 1
\-"iQ.9; 1)9.9) -2.52
\-6.07 38.11 O.925k O.Q2Sk rnr- -62.'2
\-22.11 ~4.1 Q 3Et.10 l:M' O kM = O
\-'3fl.21 -20.14 -22.49 2.331klpsJpie 2.775 2.331 +38.71
22.4q -3~. 21 20.14 tr1zrn
\-22.77 -34.1Q -3A.l0 (1) (Z) (3)
\-64.52 A7.21 1.01 38.71 "f3870 -4q.l q 0.46 49.19 Ñ Ñ ~l 2-lO +31:UO 61t.52 -87.21 lO 1.01 ~ VJ ~ (51 ;:~ (4) ~ (61 (71
\~) q 30.45 30. -s e... 11
12 -137.26 -18.14 -11.q4 Orn
13l' -81.26-·H~.4q -30.45lq.14 -~O.'3'311.94 2,516 2,510 hTI1Tm -0.12 -63.13 15 A1.36 21,3' 7.5' 21.3' S2 -50.34 50.34 16 -0.!i4 11 -0.12 -e7.36 63.13 (J)rn 2'
""JI (1\) (14) 1r~ O 1"l· -136.)4-94.1 7 -19.1t236.16 -18.A833.2A
lq.42 20 -136.34 18.8'" O -33.21\ 21 -94.11 -36.16
22 O. lA -36.16 q3.l9
\~3 -2.14 -61.6Q e3.69 tr1z ? 2\< -un0.38.00 -q3.10.00q -lO.OA36.16 :J>
?6 -un.oo -0.00 10.0"
( 181 1(20) (21) lDAOINf; CCND1TION NO 1(19: :>::1oO DeSlCN END M014ENTS CORRECTED Y'
FE'" AND wl"'O ME""I\ER AXIAL FOPCE. k Ft:'R :J> (NEU ENO F JRsr), K-FT .rrr2.516 -5.90 64.33 1 -Z6.18~4tj.64 (221 -2.1"? 2 :>::1z -""4.76 -4. Al" 3 ~1.31> :J> -'SQ.2Q 26.7A 4 -16. fl6 20\.05 -20.09 -2~. 10 -t a.ot Oe -7R.61 1'3.61) 8~1(25) ""\9.42'"+93.1963,69VS. ·93.19+ 10.08e.k 5, :>::1 12.1" -31.31 1 -11.31 -27.27 70.Q2 :J> R -1.34 VJ -42.06 42.66 -O.ClO -3l.l~ 54.16 ID O. l6 -'iq.~H 18.01 -\<
II -41.09
12 -64.50 -21.63lf'.A8 -21.195.1? 10 -66.3fl "Oem
l' -44.6"i -2b.Al5.5ft -27.""914.21 Verifíquese '::.Fv = Opara el piso superior:
15 -2.51 -36.6q 49.37 Salidas de la computadora 22_77\1(~1+38_21el= l21,%klpS
Cargas: ~331 1213) {21'" _,775(7,5)'" -2b.l'i 5A.8l -1.011) O,Q25 \21 2-lrn(J) -')6.~' 94.30+ 20.81 + 1.85klps= 121.96klPStO.K.) l1.Al eH 11"IR -b8.-1.64
\1. -9°.15 -21.431"25\<~26'"1.86 20 -10'i.'H
21 -12.33 -34.871.73 -32.007';.82
?2 2.43 -lQ.2'i 'i4.04
\>3 -1.61 -41.51 34.A7 Verifíquese F == - 187,00 kips en el miembro 26 usando la matriz
2' -1.86 -64.02 -6.88 X: X43 = - 0.08232 pulg = acortamiento axial del miembro 26 25 -136.1?
26 -144.39 0.000,00 8.24 P» TL'(431=141l290001(O,08:3~L'(15X1::)= 187 00 kLps
Figura E2-3e

<!-- p. 101 -->

EJEMPLOS DE DISEÑO 101

2.nk
75' 3
\~o. o;e oo; o
o r-, r-. ,..: r-. N "

(4) (5 ) (6) O)

Verifiquese Fv para el piso superior
í:¡'~(cargast 2.331( 21.3)( 2) + 2.51'6(5) + 0.925( 2) = 12002 kips
Tomados de la salida de la computadora, para los valores mostrados que se han reducido un 25 por ciento por
viento, de modo que esta salida se compara directamente con la salida D + L:
'iF" = (17.09 + 27.92 + 27.90
\+ 17.10)/0.75
V2=8.965 -;:., 10155
í:F, = 120.01 kips O.K. 1354k e- o 0.75' ¡-":_ActudIF=--'-=
\- 25.57 +70.90 4669 kips/pie . 48.91
\~ _J 516 k'IPS/ pie ) ( 3.330 klps!pie ) ~ (23) N2"
(2 ~ 3 ) + (70~90__ 25J1) = 29.63k R2 R 3 33 (U)+I~i§..2.!) • .1.3(.75) 3 2 7 5( 75)
\~ R3 = l2.09k (
;;; Se han reducido
\~ ~ los momentos por viento

,- Compresión = (-) = 135.4k V2=8.965!!F19
R, = 29'63 kJ
\= 1209 ~.r3

\= í:Fnodo= 186 05 k fF25
. 139.36 _ , k
vs. 075 - 18..81 O.K.

Verificación de la salida de la computadora para la columna (miembro 25) usando la salida de la computadora
y los valores estáticos del nudo 14)

Figura E2-31 Verificación de la salida para NLC 2 (con viento).

Estos datos se usarán para preparar un juego de tarjetas de datos de los
miembros, tarjetas de cargas de vigas (entremezcladas, según sea convenien-
te entre los datos de los miembros), y un juego de datos para la matriz P.
Nótese que las entradas de la matriz P que se leen (PR(i, j)) son cero para
NCL = 1Ytoman los valores mostrados en la figura E2-3b para NCL = 2. El

<!-- p. 102 -->

102 ELEMENTOS DE DISEÑO DE MARCOS, ARMADURAS Y PUENTES

resto de la matriz P lo construye el programa de la computadora usando los
datos de carga de las vigas y los cortantes de las columnas, calculados por
separado y que aparecen también en la figura E2-3b. La entrada se reescribe
como parte de la salida para la verificación por parte del diseñador (figura.
E2-3c). El resto de la salida se muestra en las figuras E2-2d y E2-3e junto con
algunas verificaciones de la salida. En la figura E2-3fpresenta una ilustración
adicional de la verificación de la salida para NLC = 2.

El lector debe notar que en los casos en que se considera el viento, el esfuerzo
permisible se puede aumentar en un tercio de su valor. Para que todo el diseño
tenga la misma base, el programa multiplica todas las fuerzas de los miembros
por 0.75 para los NLC que tienen fuerzas de viento como entrada. Con este ajuste, el diseñador no tiene más que escudriñar la totalidad de la salida para el momento o fuerza axial máximos. El mayor valor para cualquier condición de carga
se usa entonces con el esfuerzo permisible para determinar si el miembro resulta
adecuado. Nótese que.al verificar la salida (como se ilustra en la figura E2-1f) es
preciso considerar el uso de este factor de 0.75 para que se satisfagan las condiciones estáticas.

Ejemplo 2·4. Se pasará ahora a diseñar el pequeño edificio de oficinas del
ejemplo 2-3, pero usando unidades SI. Nótese que las dimensiones son lige-
ramente diferentes que en el caso que se usa una conversión suave. Se apli-
carán las mismas consideraciones generales de diseño y parámetros que en
los del ejemplo anterior, con la excepción de que el acabado de ladrillos
del muro se tomará como 200 mm (aproximadamente el doble del espesor
del ejemplo 2-3). En la figura E2-4a se presenta la distribución general del
edificio y las dimensiones expresadas en unidades SI.

SOLUCION Los programas de computadora resolverán problemas expre-
sados en unidades SI o en unidades pie.lb.s. Será necesario incluir una tarje-
ta "UNITS" con la identificación pie.lb.s. o SI para usarla en la informa-
ción de FORMAT e identificar las unidades de la salida.
Como se utilizan los mismos criterios de diseño de construcción, se
puede proceder directamente a la codificación de las juntas (hágase referen-
cia a la figura E2-3d, puesto que la estructura es familiar) y obtener las cargas
en la estructura.

Cargas de techo:
Carga muerta: supónganse 130mm de concreto sobre un tablero metá-
lico apoyado en viguetas de celosía de acero.
Concreto: 0.13(23.5 kN/m3) = 3.055 kPa
Tablero metálico y viguetas (estimados) = 0.263 kPa
Plafón, acabado, electricidad, etc. = 0.263 kPa
Total 3.581 KPa

<!-- p. 103 -->

EJEMPLOS DE DISEÑO 163

65 2.3 6.5 m
, -.
(1) (2) (3)
\-z-
o
(4) (5) (6) (7) "1
13,14,15
11 (8) (9) (10)
\~ U ~ --f- (11) () 2) (13) (14) e- e-lrv e- e ,:;l e-
bll ::!5.26.27 e- ~ e-
o 1- (15 ) ( 16) (17)
;: e-e-
e .;;:" e-f--. (1 XI (19) (20) (21) -c e- ro') " e- ro f- ""
f- 37,47,47 44,47,47 ro~ f- U
\~V/Í>;; (23) ; % "- (24) '.:: , .~ lO" .\'p= 46 , :.: Supóngase articulada la '.
, base del muro del sótano (251 (261 .\'M = 26 Q' -c,: .\'BA.\'D = 15 "

45,47,47 46.47,47 :
";':~ ' •. '. . 0 I:..:.:.-J ..

Elevación de un marco típico ínterior

\- 5.9 59 5.9 5.9 5.9 .\

wb wb I
\ wb = Contraventeo N+

\\'b wb

Vista en planta

Figura E2-4a

<!-- p. 104 -->

104 ELEMENTOS DE DISEÑO DE MARCOS, ARMADURAS Y PUENTES

Carga viva: se puede usar una reducción en la carga viva en el área de
6.5 x 5.9 m.
Carga viva básica = 4.0 kPa (tabla IV-4).

R = 6.5(5.9)(0.0086) = 0.329 \< 0.60

R = D + L = 3.581 + 4.0 = 0.438 0.329
4.33 L 4.33(4) >

Se usará una reducción de 30 por ciento en la carga viva. Carga viva reduci-
da = 4.0(1.0 - 0.30) = 2.8 kPa. No se use ninguna reducción de la carga
viva a través del claro de 2.3 m.
Las cargas de las vigas de techo son:

Carga muerta = 3.581(5.9) = 21.1 kN/m
Carga viva en el claro de 6.5 m: 2.8(5.9) = 16.5 kN/m
Carga viva en el claro de 2.3 m: 4(5.9) = 23.6 kN/m

Cargas en los marcos para los otros pisos
Se usará un 30 por ciento de reducción para las cargas vivas en el área de
oficinas, pero ninguna en el corredor.
Carga muerta, incluyendo piso, acabado,
plafón, duetos, etc. = 3.9 kPa
Carga viva en el corredor (tabla IV-4) = 5.0 kPa
Area de oficinas = 4.0 kPa
Estas intensidades de carga dan las siguientes cargas de vigas:

Carga muerta: 3.0(5.9) 23.01 kN/m
Carga viva en las oficinas: 4.0 (0.70) (5.9) = 16.5 kN/m·
Carga viva en el corredor: 5.0(5.9) 29.5 kN/m

El recubrimiento exterior de ladrillos de 200 mm de espesor contribuirá car-
gas a las columnas (úsese la tabla IV-3):
3.77 kPo. (ladrillo) + acabado: úsese 4.0 kPa
P = 4.0 (5.9) (3.6) = 85.0 kN
Paredes longitudinales que definen el corredor + viga longitudinal:
Tableros del muro + el estimado de la estructuración = 1.08 kPa
Viga a 0.75 kN/m

Cortante en la columna interior:
P = 1.08(5.9)(3.6) + 5.9(0.75) = 27.2 kN

<!-- p. 105 -->

EJEMPLOS DE DISEÑO 105

Para las columnas interiores del techo: úsese sólo el cortante de la viga lon-
gitudinal (omítase para las columnas exteriores como un excesivo refina-
miento):
P = 5.9(0.75) = 4.4 kN

Usando el ejemplo 2-3 como guía, hágase la siguiente selección preliminar
de vigas y columnas:

Todas las vigas: W410 x 59.9 A = 7.61 X 10- 3 t, = 215.6 X 10-6
Columnas exteriores: W200 x 46.1 A = 5.89 X 10-3 I; = 45.8 X 10-3
Columnas interiores: W200 X 59.5 A = 7.55 X 10- 3 L; = 60.8 X 10-3
Columnas del sótano: W200 X 71.4 A = 9.10 X 10-3 I; = 76.6 X 10-3

En las figuras E2-4b hasta E2-4d inclusive se ilustran la entrada y salida
de la computadora. En la figura E2-4d se muestra una selección de compro-
baciones estáticas que se pueden efectuar por la inspección de la matriz de
fuerzas, para NLC = 2. Se hará una comprobación estática para el nudo 1 y
para 'E.Fv en toda la estructura para NLC = 1 Y 2. Nótese que la matriz de
fuerzas se ha reducido por el factor 0.75 (NLC = 2 con carga de viento),
de modo tal que se pueda comparar fácilmente la salida de los varios NLC,
para determinar la fuerza máxima que se usará en el diseño y utilizando los
esfuerzos básicos persibles, en las columnas y en flexión. Habrá que conside-
rar esta reducción de 0.75 en los valores de las fuerzas para poder efectuar
cualesquiera comprobaciones estáticas, como se muestra en la parte supe-
rior de la figura sin número de la página 106.
Verifíquese ahora 'E.Fvy 'E.Fh = O, para toda la estructura. Calcúlese el
peso total para ambas comprobaciones de la fuerza vertical:
37.6(6.5)(2) + 44.7(2.3) + 39.5(6.5)(6) + 52.5(2.3)(3) + 4.4(2)
\+ 27.2(6) + 85(4)t = 3006.36 kN
Para NLC = 1 (véase el diagrama en la parte inferior de la página 106):
Fuerzas resistentes verticales: R) + Rz + las fuerzas en las columnas del só-
tano.
F, = 642.28 + 642.28 + 861.35 + 861.35 = 3007.28 kN (vs. 3006.36 kN)

La diferencia se debe al error de redondeo de la computadora. Por inspec-
ción, Fh = O, puesto que las cargas son simétricas.

Nota: dos fuerzas de 85 kN pasan directamente a las reacciones y no se consideran.

<!-- p. 106 -->

106 ELEMENTOS DE DISEÑO DE MARCOS, ARMADURAS Y PUENTES

En el nudo I
Para NLC ~ 1: No se muestra en la viga la carga distribuida pero sí se usa para calcular.
como se indica. el cortante en el extremo. Nótese la dirección de las
flechas en los miembros para indicar esfuerzos axiales a compresión.

111.48 -56.93 + I ~6.64

0_.J....;219 )
" 56.93)/6.5 = 111.48 ("'m('f)':(:::~ 53T111.48 EFundo ~ OH & V
5650 ~9.53
(29.39)

Para NLC ~ 2: No se muestra la carga distribuida de la viga.

110.07 kN ·39.33 n.45
I 10.~kN !~ ~8 ~5 kN , - ) ~~ (f ·
\~ 110.07 "\<.~ 376 (65)"2
49.80 kN'm ~0.6 = '747 0.75 _. 98.45 39.33) = I 10.07 kN ( 0.75(6.5)

v-.
E v-. ~8.~5 = 37 67 el -o
...., 00I 0.75 .
8~55= 11007
0.75 .
\+34.83x.> 'i.Ff¡ = 'i.F¡ = O

Miembro 21 ~ 526.24

526.53 kN (miembro 18) +140.64 - 140.64 ¡ -57'86( ! 39.5 )
)57.85 ( " (~4)" " " ,'i,S"6.5 m " " "1 :W' f"""'"""
R 1 = 64~.~8 kN Rí = 64~.~8

<!-- p. 107 -->

EJEMPLOS DE DISEÑO 107

'"~1----"""'I---=----'-t-"""::'---+""":::"""'_---"-\<:4i
i
\~ ~ ...... 9"9L '" XI
\~ ;SOlo6;Y
\~'6) X ooZ'"

00000000000000000000000000
8 S"'" xI 0000000000000000000000000000000000000000000000000000
68 S '" Y ~~~~~~~~~~~~~~~~~~~~~~~~~~000 000 000 000 __ X QOVIf ::f 1'9..

gggggggggggggggggggggggggg
\~ gg8g8g8g888gg88gg8ggggg8g8~~~~~~~~~~~~~~~~~~~~~~~~~~
\~N~~~~~~N~~~~~~N~~~~~~N~~~

\~~~~.~

1 I I I I 1111~~~...I 11 I ~~~~~..1 1 I I I I 1 I I I 1 1 1 00000000000000000000000000~~~.~..w~~wwwwwwwwwwwwwwwwwwwwwww
\~oo~ ~oo~ ~oo~ ~~
\~~~~~~c~~~e«c~~~~.ce~~~~~~ 00000000 00000000 ~
\~~~~ ~~~~ ~~~~~~~~~~~~~~~~~~~~~~~~~~ ~~OO ~~oo
00000000000000000000000000
00000000000000000000000000NNNNNN~NNNNNNNNNNNNNNNNNNN
wwwwwwwwwwwwwwwWwW~WWwWWWW___II I ~~~~I III I 1 I ~~~~I I I 1 I I I ~~~~I III I I I ooI I
\~~~c~~e~~~c~~e~~~e~~e~~~__
\~~~~~~~~~~~~~~~~~~~~~~~~~~
00000000000000000000000000
00000000000000000000000000
000000000000000000000000 ~~~~~~~~~~~~~~~~~~~~~~~~~~ 000000000000000000000000
00000000000000000000000000 ~~~~~~~~~~~~~~~~~~~~~~~~
\~ 0000~~~~ 0000~~~~ 0000~~~~ 00.~ 000000000000000000000000
\~~~~ ~~~~ ~~~~ ~~

000000000000000000000000000000000000000000000000 ~~~~~~~~~~~~~~~~~~~~~~~~~~ooooooocooooooooooooo~oooo
1 00000000000000000000000000 ~~~~~~~~~~~~~~~~~~~~~~~~ 000~~~ ~~~OUO 000~~~ 000~~r ; 000000000000000000000000
\~N~ ~N~ ~N~ ~N~

000000000000000000000000 ~~N~~~Ne-.~e_.o~~~O~~O~~O~ : 000000000000000000000000 Z _ __NN __ NN~~~NM~~.~•••o v ~~~~~~~~~~~~~~~~~~~~~~~~
e o ~N oo«' o ~ 000000000000000000000000
\~ ~C_N~C_~O~.~O~~N~~VN~~N~ONU Z __NN __ NNN~~NN~~~•• ~. _ "Z

.~O_.~O~~NM~~NC_.~~_.e_.e__ _ __ N NN~~NN~M~ •• ~.
000000000000000000000000 000000000000000000000000 :.Z
\~~~~~~~~~~~~~~~~~~~~~~~~
\~ ~~~~c-.~e_~O~~~O~~OM~~O~~~__ NN __ NN~~~NM~••••••••• ~ 000000000000000000000000 '"Z
N~Z N~e.~O~'.~O~VNr~VN~~N~~vN~~__ NN __ ~~~~MNN~.~••• ~ •••

\~Z _.~~~~N~~~~e_.~e_~e_.~c_r~__ ~N NN~MNNM~~'•• ~M •••
c.'OC'Z"Z _N~.~~~«OO~N~.~~~~~e~N~.~~___ ~~ ~~NNNNN~N

<!-- p. 108 -->

...
Qll NQ STIOFIII ENTRIES = 6'10 8ANO WIOTH • 15 o 4.4 kN 4.4 kN o C>

THE R-MATRIX. KN ANO K-MM THE X-HATRIX. MM OR RAOIANS 1+ 16.5 = 37.6 kNI 44.7 37.6 m L ! 1111111 ! ! NP = 1 132383.30 132383.30 IIIX • 1 0.004n 0.00430 P, = 10.2 kN "IR = 2 0.00 10.20 NX = 2 0.13429 10.25240 (sóloNL e = 2) r-m3: "IR = , -1Z2.20 -ln.20 NX = 3 -2.'17310 -2.81463 m
"IR = 4 -112618.00 -112618.00 ~x '=' 4 -0.00192 -0.00181
5 0.00 0.00 5 0.00811 10.0'1155 NX "IP = =
\= 6 -118.00 -118.00 NO -4.6414'1 -4.52804 NX 6 (/J2-lO =
"IR = 1 112618.00 112618.00 NX = 1 0.001'12 0.00203
NR = 8 0.00 0.00 IIIX = -0.001'13 10.06111
\~o Om o 85l -118.00 -118.00 -4.641'14 -4.15541 l27.2 11I X = = '1" l85 27.2l 52.5 '-!X -132383.30 -132383.10 "IR 10 -0.00422 -0.00413 O 23.01 + 16.5 = 39.5 10 39.5 =
[j; 0.00 0.00 '1.'13314 P, , - 15.3 NO -0.11351 -= 11 NX 11 :== 111 " I -122.20 -2.'11336 12 -122.20 NX 12 -2.92418 NR = =
13'1012.80 NO :: 13 139012.80 0.00280 0.00n2 NX ILC= 2 m2' = 13
NO = 14 0.00 15.10 NX = 14 -0.02431 8.55236 O NR = 15 -213.38 -213.38 NX = l' -2.58330 -2.'3825 NO = 16 -115'129.10 -115'12'1.10 NX = 1~ -0.00133 -0.00114 . Om NR = 11 0.00 0.00 NX = 11 -0.00056 8.52131 NO = 18 -215.'15 -215.'1' NX -= 18 -4.1'112'1 -4.0111'1 3:
\= NI' 10 116105.10 116105.10 10 0.00133 0.00153 27.2 ~ "IX !27.2 = l85 85l ;¡:. ~o :: 20 0.00 0.00 0.0028'1 8.51323 20 NX 52.5 = 39.5 39.5 NO :: -216.11 -216.11 -4.30535 21 -4.1'1181 NX = 21
\-13'1248.'10 -13'1248.'10 -= ?Z -0.00248 P" = 15.3 1111II ;AloO(/J -0.00281 ,.,.0 Z2 "IX = No :: 23 0.00 0.00 NX = 23 0.02611 8.52660 .vLC= 2 "IR = 24 -213.54 -213.54 "IX :: 24 -2.58318 -2.62890 ;¡:. NR = 2' 139248.90 139248.'10 MX :: 25 0.0021'l 0.0033'1 ;Al
No -= 26 0.00 15.30 IIIX = 26 0.03041 5.016'16 3:
NO :: 21 -213.54 -21'.54 IIIX = 21 -1.60'109 -1.51808 ;¡:.
"IR = 28 -116105.10 -116105.10 "IX = 28 -0.00135 -0.00101 :: No 20 0.00 0.00 29 0.00412 4.99844 "IX = 27.2! !85 85! Oe ;Al -216.11 -216.11 NO 30 -3.21213 -3.11330 = 30 IIIX = 52.5 !27.2 ;¡:. 39.5 e 39.5 115'12'1.10 31 11592'1.10 "IX = 0.00135 0.00163 31 ""O
NP = 32 0.00 0.00 NX = 32 -0.00206 4.'18083 III1111I (/J NO :: 33 -215.95 -215.'15 IIIX = ,. -1.211'1'1 -3.31004 -\<
No dm m. ~o == '435 -13'1012.800.00 -13'1012.800.00 "IX"IX == ?;!>34 -0.00218-0.02834 -0.002184.'141'16 NR = 36 -213.38 -213.38 IIIX = 16 -1.60011 -1.64010 '"em
13'1012.80 13'1012.80 31 NP 31 0.00414 0.00430 = IIIX =
\~ 18 -115'12'1.10 -115'12'1.10 No = 38 -0.00110 -0.00155 NX = ,., NR '0 0.00 0.00 = 10 NX = 0.00116 0.06411 ,.,,.,~ (/J2-lm
"IR 40 -215.'15 -215.'15 ;2 = 40 -1.10311 -1.65161 NX =
00 41 115'12 0.10 115'12'1.10 NR 41 0.00110 = 0.00185 NX = " NO :: 42 0.00 0.00 IIIX = 42 -0.0011 O 0.05042 NP = 43 -215.'15 -215.'15 NX :: 43 -1.10313 -1.155'14
NO :: 44 -11'1012.80 -13'1012.80 NX = 44 -0.00430 -0.00388
"IR e 45 0.00 0.00 ~'X :: 45 0.00085 0.00080
"IR = 46 0.00 0.00 NX -= 46 -0.00085 -0.00000
d tT7 mftT7
FiguraE2·4c

<!-- p. 109 -->

lQAOTNG CONDITtON NO '" ·39.33 +4$.49
CO~RECTEO DESIGN END JIlIO'4ENTS
FI')~ FE" ANO WINO INEAR ENO F IPST l. I(N-M P2'" io.i 6.$ m :?3 m 6,5 m "4E·"4~ER AXUl ~ORCE. I(N
(ll (3'
\-2CJ. '3CJ -'56. '50 126.81 1
\-Ql.QO -11.05 2
56.'52 -2CJ.41 -126. AO , ql.16 +39,)3 kN . m ·-4$.49
\~O 4Q. '56.'50 (4) },6 m (7) 4 -111.3R
5 -lM.64 -:\1.02 -~'5.0 1
\-lM.~O 31.0'5 3'5.04 • 1 -111.3CJ PI. '" 15,3 -92. , 5.56 -4Q.3":n -0;6.'52131.0A
\2. ,l(~ -71.00 73.1'5 o
10 ~.~A -131.2P Q2.30
11 -318.7e 42.8e- "2.en
12 -410.70 -27.18 -27.06
(1:?) 27 .06 21.11 -410.°6 13 109,88-.11.45 -.19_8.1 -3950'" O SLe '" ~ -42.96 14 -31 R. q, -42.113
\-6.11 -\<:3.00 130.63
73.60 -4.0Q -7~.16 l. '\ a2.1:,3 -6.11) -130.43 11" P¡;:ISJkN,1 ) I r.n I -~26.'53 '50.14 '51.A6
10 -632.61 -32.06 -29.68 " 'O -632.63 3'.04 2q.6~
21 -526.'54 -'51.R4 -'50.10
22 1. MI -")1. A6 140.64
\-Cl.44 -86. el: A6.88
'4 1.66 -140.64 51.80; 25" -861.3!í -0.00 -21.12 ,. -Ml.33 -0.00 21.12
LOADING CC'NDl TI0N NO oss IGN ENO MOMENT S CQPQEC TEO
"'~fl4eE~ AXIAL FOflCE. I(N FOR FE'" ANO WINO (NEAQ: ENO FIfl:'iTl. KN-M

\-2A.25 -3q.33·~6'1.9498.45
\-12.13 4'5.It~:> -23. 39.3~ '53 -91.73-61.13 4 -A2.55 'IIt.A? -30.1' -141.64 5 -27.31 21.71:,
\-141.~8 •7 -fl4.'54 -3G.20¡CJ.23 -4'5.4Q- , -5.45 -60.'55 105.70
Q -4.01 -46.60 63.01 lTl
i o 2.35 -'11.0'5 17 .90 Se muestran salidas seleccionadas para la condición de la carga del viento (NLC = 2) '- 2'5.72 26.16 -235.604 11
113.07 97.96 53.64 79 -J~.98 12 -~03.41 -11.lt5 - -~1.
\9. '32 8.61 39.5 ) lTls: 39.5 'N/m ') ( -3\2.'1:'
\-37.")'5 -31'.70 11 11 -'42.61 14 ( " 10q.fH! • -54.60 111"'116.$ m f"lll"lllllll"lllllt6.$ m (22) 1" -13.7CJ 15
11.59 -8.74 -38.'13- 111"1(14) '"Or-O(J) 16
\-A~.97 1'4.13 -6.83 11
R~ :?1.8lt -387.29 - ~f: : ; ' -39.50- -459. RO lo " ~O 6.1'1 -4R9.1R '5.06 Rí. = (3~,980.7~ 13.07)/6.5 + 39.5 (6/) RR '" (53.640~-7~7.96)/6.$ + 39.5 ~ -41.11\ -402. '51 -53.604 R~ lTlo" ?l
.. 113.07 22 11.36 \<-32.9f! Vi l1t.l1 --;6.1 '5 -1.0\<1 23 '" 111.9$ kN· = 119.28 kN- lTl
'53.64 -8.85 -97.q6 24 aumenta un 25"70 debido al factor de viento - 'Se 25 -626.26 -0.00 - -14.99 de 0.75. Z'O 0.00 -665.79 26 17.60 = Parte de los cálculos para verificar O r:.Fv
...Figura E2-4d ~

<!-- p. 110 -->

110 ELEMENTOS DE DISEÑO DE MARCOS, ARMADURAS Y PUENTES
Para NLC = 2: No se muestran las cargas distribuídas en las vigas.
Se efectúa la comprobación estática vertical, haciendo referencia a la figura
E2-4d, donde se calcula parte de las reacciones en el muro del sótano:

F¿ = R{ + carga axial18+ R~ -í-carga axialj¡ + carga axíal-, + carga axial-¿
402.510~5626.26 + 665.79 = 111.95 + 119.28 + 387.29 +

2081.85 = 231.23 + 0.75 = 3007.03 (vs. 3006.36 kN) Correcto.
Consíderese ~ Fh = O:

27.84 53.64 14.92 17.60 ~ «\<: ,...... ~

E
"\< (18) (21)
\<"') (25) E -o (26)
'i'

16.89/0.75 = 22.52 28/0.75= 37.33

3.24/0.75 = 4.32 3.83/0.75 = 5.11 '-"32.98 '-.J47.18
\...:0 \...:0

Fuerzas en los miembros

22.52 kN 37.33
\~11.36=1515 ~ 8.85 = 11.80kN
\~ /0.75 . l77i777 (0.75
( (Miembros 22) (24)

Fuerzas de las dos reacciones del sótano, incluyendo los efectos de las vigas
que constituyen los miembros horizontales 22 y 24:
EFh(aplicado exteriormente) 10.2 + 15.3(2) = 40.8 kN
EFh(nodos) = -22.52 + 15.15 + 37.33 + 11.80 + 4.32 - 5.11
\= 40.93 kN Correcto. / / /

Ejemplo 2-5. Se trata de un diseño parcial de un edificio industrial (para un
proceso de fabricación); en la figura E2-50 se muestra la vista general en ele-
vación, junto con una vista reducida de la planta. Debido a las grandes di-

<!-- p. 111 -->

r-,
r-.

;,. "Or, ;9, -
r-,

74 22 crujías su 25' = 550' r-. I~ .I -,..J~
,...,
",1 -o .,f

,...,E
r--

3 00 ~.,;
\~ 2 _~HS~ll~"'-J.·~ '\J. '\J
y;.~

E ;,. (1) (24) (70) (93) '" '"0,
07 107~107 1~107 107:tt-I07 107~7
\~ ~107 107 107 107/'
6 (a' 12' 10 (a 12' 6 Ca 12' I I =:=J 72'603.6m : 72'·6(a3.6m:==J 120' 10(á3.6m ::
21.6 m 36 m 21.6 m

El·5a= Figura...

<!-- p. 112 -->

112 ELEMENTOS DE DISEÑO DE MARCOS, ARMADURAS Y PUENTES

mensiones del tramo libre y a la altura requerida, no se consideran prácticas
las vigas de techo, por lo que se usarán armaduras de techo y largueros. Estas
armaduras reducirán la deflexión del techo y aumentarán la rigidez total del
marco, en particular si se hacen constantes las columnas hasta la parte más
alta de la armadura principal de techo. Al hacer continua la columna se redu-
cirán la rotación y traslación de la columna en la línea del techo. Es posible
espaciar los largueros aproximadamente 6 pies c.a.c., por lo que uno de ellos
caerá dentro de un panel. Esto producirá flexión en los miembros del cordón
superior, además de la fuerza axial obtenida del análisis de la armadura.
Será necesario hacer una estimación preliminar de las dimensiones de
los miembros, programar estos datos, inspeccionar la salida de la computa-
dora e iterar según se requiera. Para una primera iteración se usaron colum-
nas Wl4 x 68; (esta repetición no se muestra en el texto). La condición más
severa de carga (con viento) produjo desplazamientos laterales del orden de
36 pulg, los que nunca podrían ser aceptables. Se probó una nueva dimen-
sión para las columnas, usando una sección de W27 x 178 para la segunda
iteración, que se muestra aquí.
La planta del edificio muestra 22 crujías espaciadas a 25 pies. Se pon-
drán contravientos en determinadas crujías que ni se muestran ni se diseñan
en este ejemplo. Se proveerán vigas longitudinales entre las columnas, con
espaciamientos verticales de aproximadamente 8 pies, para soportar los mu-
ros exteriores. Estos miembros aportarán cargas adicionales a la columna y
proveerán soporte lateral a la columna en su eje débil. Las cargas sobre los
muros no se consideran en el análisis en este momento. La contribución del
muro se puede tener en cuenta fácilmente añadiendo directamente los cor-
tantes de la viga del muro a la fuerza axial a la salida de la computadora, al
determinar el tipo de cubierta exterior que se ha de usar (hojas metálicas,
madera y metal, etc.).
Los parámetros generales de diseño para un marco interior típico (o ar-
madura) incluyen:
Techo + largueros, estimados como 151b/pie2
Detalles diversos adicionales 5Ib/pie2
Total 20Ib/pie2
Carga/pie de techo = 25(0.02) 0.50 kip/pie
SOLUCION La carga muerta de la armadura se obtiene después de haber re-
alizado un análisis aproximado de la armadura (que no sea indeterminada),
para estimar las posibles fuerzas en los miembros. Este análisis esmuy aproxi-
mado y no se muestra en este lugar, ya que se han hecho suposiciones muy
aproximadas y hay además un gran número de las mismas que permiten a
cada individuo obtener con ellas resultados similares. Con esta estimación ini-
cial se procede a seleccionar las dimensiones de los miembros de la armadura:
Cordones superiores e inferiores del cobertizo y la armadura principal
del techo: dos L6 x 4 x 5/16:
peso/pie = 20.6 lb/pie A = 6.06 pulg?

<!-- p. 113 -->

EJEMPLOS DE DISEÑO 113

Miembros verticales y diagonales: dos L4 x 3 x +
peso = 11.6 lb/pie A = 3.38 pulg-

El peso aproximado de la armadura se calcula de la manera siguiente:

Longitud (aprox.) de la cuerda superior + cuerda inferior de
la armadura principal = 2 x 120 =240 pies
Verticales: peso prom. x 11 = (15 + 27)(11)/2 = 231 pies
Diagonales: longitud prom. x 10 = (27.3 + 19.2)(10)/2 =232 pies

Peso promedio de la armadura:
W(I20) = 240(0.0206) + 0.0116(231 + 232) = 1031 kips
W = 1~2~1 = 0.09 kipjpie se usa O.10kipjpie

El peso de la armadura de los cobertizos es como sigue:

Longitud aprox. de las cuerdas superior e inferior = 2 x 72 = 144pies
Verticales: (3 + 15)5/2 45 pies
Diagonales: (12.4 + 19.2)(5)/2 = 80pies

Peso promedio de la armadura:
W(72) = 144(0.0206) + 0.0116(80 + 45) = 4.42 kips
W = 47~2 = 0.06 kipjpie se usaO.O? kipjpie

Los pesos de las armaduras se han redondeado para tener en cuenta las cone-
xiones.
La armadura se analizará para dos condiciones de carga.

NLC = 1: carga muerta + nieve
NLC = 2: viento + nieve + carga muerta en el cobertizo de la izquierda +
viento (succión) + carga muerta en la armadura principal + 1.5
de nieve + carga muerta en el cobertizo de la derecha.

La armadura se diseña simétricamente, puesto que el viento puede
soplar de cualquiera de las dos direcciones. El fundamento de esta combina-
ción de cargas es el siguiente:

\1. El viento que sopla de la derecha no arrastrará la nieve acumulada en elco-
bertizo de la izquierda. Además, el muro vertical producirá un cierto estan-
camiento, de modo que la dirección es normal y dirigida hacia abajo.

<!-- p. 114 -->

......~

P34 .. \.J--'-"" P34 = omo(7.5)(25) = 5.63
1.13- Fig. E2-5e
4.50
P31 • I P31 = 0.025(12)(25) + 0.025(4)(25) + (7.5 - 4)(25)(0.030) I
\= 12.63k

\- P28 =0.025( 12)(25) = 7.5k
\+0.94
8.44k

Pi = 0.015(3)(25) + 0.020(20)(25)
\+ 0.025(4)(25) = 13.63 k
\+0.94~ Fig. E2-5e
14.57

Figura E2·5b

<!-- p. 115 -->

EJEMPLOS DE DISEÑO 115

11.48 11.26
11.48/2 = 5.74 L e
31 0 5.63 e=tan:' 12=II60 .
sene = 0.19612
cos e= 0.98058
L = J.L = 12.24' cos e
N w = 0.030 X 1.25 X 12.24 X 25 = 11.48k
Pv = 11.48 X cos o= 11.26
Ph = 11.48 X sen s = 2.25

Armadura principal del techo

e=tan-I~=1404° e 72 .
LI ~ = 12.37' cos O
PN = 0.025(25)(12.37) = 7.73k
Pv = 7.73 cos e= 7.50k
Ph = 7.73 sene = 1.88k Armadura del cobertizo

11.48k
11.26 11.48k
11.26

Lado derecho de la armadura
principal del techo

Figura E2·5e

\2. En la armadura principal, la pendiente es tal que la acción aerodinámica
resultará en un efecto de succión, además de llevarse la nieve.
\3. El cobertizo de la derecha debe quedar protegido del viento, pero la nieve
puede acumularse en el techo: para tener en cuenta esta condición, se
aumenta la carga de nieve a 1.5 x S.

<!-- p. 116 -->

1I6 ELEMENTOS DE DISEÑO DE MARCOS, ARMADURAS Y PUENTES

Ahora se puede empezar el cálculo de las fuerzas en los nudos.
Para la carga muerta: Aplíquese el peso de la armadura (calculado en
kips/pie de claro) al nudo superior junto con la carga muerta del techo, ya
que el aumento en el peso total es pequeño y es causa de demasiado trabajo
adicional para justificar el aumento en la precisión de los cálculos.
Carga muerta sobre los cobertizos: nótese que tanto el cobertizo como
la armadura principal tienen paneles de 12 pies.
Nudos interiores: (0.07 + 0.50)(12) = 6.84 kips
Nudos exteriores: 6.84/2 = 3.42 kips
Armadura principal:
Nudos interiores: (0.10 + 0.50)(12) =7.20 kips
Nudos exteriores: 7.20/2 = 3.60 kips
Carga de nieve de 25 lb/pie- para la proyección horizontal del claro:
Nudos interiores: 0.025(25)(12) = 7.50 kips
Nudos exteriores: 7.50/2 = 3.75 kips
La D + S resultante para NLC = 1.es:
Cobertizos: nudos exteriores: D + S = 3.42 + 3.75 = 7.17 kips (en la
matriz P)
nudos interiores: 6.84 + 7.50 = 14.34 kips
Armadura principal: nudos interiores: 7.2 + 7.50 = 14.70 kips
nudos exteriores: 14.70/2 = 7.35 kips
Estos valores aparecen en las hojas de salida de la computadora, para la
matriz P, con un signo (-), de acuerdo con la convención de signos; para
la situación de los nudos, se hará referencia a la figura E2-5a.
Será necesario hacer referencia a las figuras E2-5b y E2-5e para la obten-
ción de las fuerzas en los nudos en el caso de NLC = 2. En la figura E2-5b se
muestra el perfil recomendado por el NBC para el viento contra la armadura.
Se muestra en este diagrama una selección de entradas de la matriz P, como
una conveniencia para el lector. Es necesario prestar la más estricta atención a
fin de aplicar los signos correctos a las fuerzas en los nudos. Nótese que las
fuerzas que tienen la misma dirección que las de la figura 2-6 son ( +), y cuan-
do se invierte la dirección, el signo es ( - ).
En las figuras E2-5d a E2-5finclusive, se muestran las salidas de la com-
putadora para las dos condiciones de carga. En la figura E2-5g semuestra una
selección de la salida de la computadora para su uso en diseño (usando el ma-
yor valor de cualesquiera de los 2 NLC). Estos datos se usarán en capítulos
subsiguientes para diseñar, o rediseñar, los miembros. Nótese que el máximo
desplazamiento lateral es ahora del orden de 4.7 pulg en la base de la armadu-
ra del cobertizo y sólo 4.0 pulg en la parte superior de la armadura principal,
lo que indica cierta flexión adicional en las columnas interiores. Nótese que
este desplazamiento tiene lugar con el NLC donde se considera el viento, co-
mo se podía razonablemente esperar. / / /

<!-- p. 117 -->

EJEMPLOS DE DISEÑO 117

Ejemplo 2-6 Diséñese el edificio para un almacén industrial usando unidades
SI, y cuyas dimensiones generales se muestran en la figura E2-6a. Se harán las
mismas suposiciones y se usarán los mismos parámetros que en el ejemplo 2-5.

SOLUCION Se seleccionan como sigue, las dimensiones iniciales de los
miembros (y guiándose en todo lo posible por los resultados de la computa-
dora para el caso del ejemplo 2-5, lo que se conoce en la terminología profe-
sional como "uso de la experiencia"):
Miembros de las cuerdas superior e inferior de las armaduras principal y
de los cobertizos: dos Ll52 x 102 x 7.9 mm:

peso = 0.301 kN/m A =3.91 x 10-3 m2
Ix: no se necesita para miembros de armaduras

Miembros intermedios de las armaduras (verticales y diagonales): dos
L102 x 76 x 6.3 mm:
peso = 0.169 kN/m A 2.18 x 10- 3 m2

qtHNf-SS "'HHOO QF RICID F••ME aNO n.us!. ANAlYSI S

.,~ NO NP lOO NOOF
N':' Nle NO NON-lHD. ., P .. Te W{NO "le '" NO OFz "OlAeRS .- l CADIIlEnte;rOMO JT el.. .. MET9I;tc12 . o I(:Tt~F ~ NO 7EJlDEO 29000.0 "'00 ElA5T1CITY .. •••
Nle FOA. o • l '" NlC FQA: wtNC ON eH'" .. o •
/Ile'U~Fll: NPI NP2 NP3 NP4 NPO} NP6 COS SIN F':Ml HfIlI2

648.00 0.00000 1.00000 0.00 0.00 t o 'o, , 2 ,
1.00000 0.00000 0.00 0.00 'o' s o o 144.000.00 648.00O.CO 6.0641.7 O.'511E0.000 •• 1...,..00 , , 2 , o• 7 o o 144.00 !6.00 6.06 0.000 148.43 0.97014 0.242'54 0.00 0.00 , o , o o 0.00 16.00 3.38 0.000 36.00 0.00000 1.00000 0.00 0.00 , o o 144.00 0.00 0.06 0.000 144.00 1.00000 0.00000 0.00 0.00 • • 7 •o o o · • 7 10• 11 o o o H4.00144.00 -lb.e'J~6.00 1.386.06 0.0000.000 14f1.43148.4~ O.91014-0.24;?54o. Q70H 0.24254 0.000.00 0.000.00
0.00000 1.00000 3.38 0.000 12.00 0.00 0.00 io 0.00 "2.00 o 11 o
0.00 0.000 144.00 1.00000 0.00000 n.no 13 144.00 0.00 6.06 • • 12 o o io 1. 1t. 12 13 O o 144.00 -11.00 ~. 3" 0.000 161.00 o. iJlI:I443-0.44"21 0.00 0.00
0.24215'" 1...8 .... 3 0.1:17014 0.00 0.00 0.000 11 14 1"'4.00 3"'.00 6.06 o o '1 'O
10~~00 3.38 0.000 0.00000 1.00000 0.00 0.00 0.00 108.00 12 12· o o \. t..s
144.00 1.00000 0.00000 0.00 0.00 ¡; 144.nO 0.00 6.06 0.000 lO 17 o l' o " 3.3iJ1 180.00 0.80000-0.60000 0.00 144.00 0.00 -10!.00 0.000 17 re e ,.
0.24254 0.'nOI4 0.00 6.06 0.00 0.000 148.43 le i 144.00 14 "6.00 s o lO •o
1~.00 0.00 0.00000 1.00000 144.00 3.38 0.000 0.00 le 0.00 e t o o l' "'O 17"13 " 0.000 144.00 0.00 0.00 1.00000 0.00000 0.00 6.06 144.00 ,. tO 17 21 o o
203.615 0.70111-0.70711 0.00 -144.00 3.3iJ1 0.000 0.00 21 o 2' l. ,.
0.97014 0.2420;4 0.000 148.43 0.00 0.00 1R 144.00 16.00 6.06 2Z o l'
0.00000 1.00000 0.00 '1.3iJ1 0.000 180.00 73 180.00 0.00 0.00 2. "l'" 2. 21 ZZ o •oo 144.00 21 2. 21 "'O o o 144.00 0.00 0.06 0.000 1".00 1.00000 O.{)OOOO 0.00 0.00
0.000 230.'51 0.62470-0.7f11081 -180.00 0.00 0.00 Z2 ZS 20 3.3" o
148.43 0.0:,7014 0.242'54 0.000 0.00 0.00 "7A 144.00 36.00 0.06 2Z o 2' " ~2.3 0.699f 04 648.00 0.00000 1.00000 0.00 64iJ1.00 0.00 1.7 24 0.00 20 o• H4.00
0.6QQE 04 216.00 0.00000 216.00 '52.3 1.00000 0.00 0.00 lO "24 "724 27 0.00 20 2. 107""r
0.61:11:1f 04 2811.00 288.00 0.00000 1.00000 0.00 0.00 ?7 52.3 20 lO 0.00 "3\ so ze " 0.60:,QE 0.00000 1.00000 0.00 04 ."0.00 0.00 SZ.' JO 0.00 1"0.00 " 144.00 6.06 0.000 1.00000 0.00000 0.00 0.00 0.00 144.00 37 o o 2. 'O .. " " " 0.000 2'30.151 0.62470-0.1"0IP 0.00 0.00 H '3.'38 144.00 -r so.ne o o Z7,a 'O '1" 0.~l\058 146.111'5 0.IQ612 6.06 0.000 0.00 0.00 ze.AO 144.00 ,." so o o " " .. 20f'l.P;0 0.000 208.110 o.nooee 1.00000 0.00 0.00 3.'38 0.00 o o ,... 0.00 144.00 1.00000 0.00000 0.00 0.000 0.00 0.06 O 144.00 30 37 o '0 ., " " " 0.51830 0.85520 0.00 0.00 2H.60 0.000 ZT7.'lJ 144.00 4Z o 'O J. ~" '. " e 0.0:,80158 0.IQ612 6.06 146.85 0.00 • 22.9 144.00 28.80 ", O ., e ,.'O .. ~B " 237.60 0.00 '5.'54 0.00000 1.00000 0.00 .\ 2'H.60 3. 0.00 o o '0 '2 ..
22.8 144.00 1.000no 0.00000 0.00 0.00 6.06 144.00 0.00 o o '1 .'.. " C.Oo 277.(113 O. 51 iJI'30-0.1II~5 20 0.0(; 0.00 '3.38 5.54 H4.00 -237.60 o ••'2 o .. 0.Q8()f)80.IQb12 lf0.6.At; 6.06 0.00 0.00 ..•• .7 22." O O 144.00 Z"."O 43 '0 4Z .. .. ",.]O'O 5.54 266.40 O. 00000 1.00000 0.00 266.40 0.00 3.38 ovee o o '0
2Z.1lt 0.00 6.06 144.00 1 • 00000 0.00000 0.00 0.00 .e 144.00 O '0 o .. .. ..
Zq~.20 0.438lt2 0.8Qen •• 15.'54 32'8.4'5 0.00 0.00 144.00 '.3A so o '1 o '1•• .. lo1t6.8'5 0.QiJlO58 0.IQ612 0.00 22.8 144.00 l8.80 6.06 o.no 42 50 o o '0 .. ..
'i.54 21:1'1.20 0.00000 0.00 '3.38 1.00000 0.00 0.00 2°5.20 o 'O .. " 22.(11 6.01, 144.00 1.00000 0.00000 0.00 0.00 0.00 ." 144.00 o o .. ., .. .a
\-29~. " 5.'54 328.45 0.43"42-0. ftq811 20 0.00 0.00 144.00 3.38 50 e o '1 .. " 146.80; 0.1:1"058 2,..fItO 6.06 22.8 0.lQ612 0.00 0.00 144.00 o o .. " 0 ..00 •• .' 324.00 0.00000 1.00000 0.00 324.00 '3.38 5.54 "54•• 0.00 O • .. .." • "'1 "50
Figura E2-Sd

<!-- p. 118 -->

118 ELEMENTOS DE DISEÑO DE MARCOS, ARMADURAS Y PUENTES

'1'1 STIFF" 1 ENTRIES '154 RANO WIOTH '1

THF P-~ATRIX. K ANO IN-K THE X-"ATRIX. IN OP RADIANS
'1P 1 0.00 0.00 'IX 1 -0.00023 0.01043
"lP 2 0.00 14.57 'IX 2 -0.0'1800 4.50431
NP 3 -7.17 -10.'12 'IX 3 -0.01613 -0.01'1'1'1
'1P 'IX 4 -0.00880 4.60253 . 4 0.00 Q.OO NP 5 0.00 0.00 'IX 5 -1.42'1"2 -1.625'18
'1P 6 0.00 1.88 "X 6 0.15761 4.7'1l84
'1P 7 -14.34 -21.84 'IX 7 -1.42°'12 -1.625'18
NP 8 0.00 0.00 'IX 8 0.08040 4.70075
'1P NP 10" 0.000.00 0.001.88 'IX'IX 10" -1.554150.11525 -1.703214.n34q
'1P 11 -14.34 -21.84 'IX 11 -1.54888 -1.6'1502
"lO 12 0.00 0.00 'IX 12 0.14610 4.76242
'1P 13 0.00 0.00 'IX 13 -1.36'13" -1.453'16
'1P 14 0.00 1.88 'IX 14 0.02006 4.62Cl83
'1P 15 -14.34 -21.84 'IX 15 -1.35359 -1. 42Cl38
'lo 16 0.00 0.00 'IX 16 0.18630 4.78753
NO 17 0.00 0.00 'IX 17 -1.01\<>55 -1.04842
'lo 18 0.00 1.8P 'IX 18 -0.091"7 4.52340
N° 1" -14.34 -21.84 'IX 1'1 -0.'187'15 -0.'1'1'126
No 20 0.00 0.00 NX 20 0.20700 4.77608
'ID 21 0.00 0.00 NX 21 -0.56'180 -0.56118
'lo 27 0.00 1.88 'IX 22 -0.20456 4.4:'1285
'1P 23 -14.34 -21.84 'IX 23 -0.51713 -0.47'125
'10 74 0.00 0.00 'IX 24 -0.00180 0.001'13
'lo 25 0.00 0.00 'IX 25 0.20220 4. 72807*En la armadura
No 26 0.00 0.00 'IX 26 -0.05346 -0.027'18del cobertizo y en
'lo 27 0.00 0.00 'IX 27 -0.00167 -0.00243\a col. int.
NO 2A 0.00 8.44 'IX 28 -0.28645 4. ~qe 1q ·Parte superior
'lo 2" -7.17 -10.'12 "lX 2'1 -0.06617 -0.02'136de \a armadura
NP 30 0.00 0.00 'IX 30 0.00133 -0.00044 .
No 31 0.00 12.63 NX 31 -0.266'10 4.10000 del cobertizo
'lo 32 0.00 0.00 NX 32 -0.08013 -0.02502
No 33 0.00 0.00 NX 33 0.00183 -0.00057
No 34 0.00 4.50 'IX 34 0.03280 4. OO5 Aq*Líneadel techo
'lo 35 -7.35 2.03 'IX 35 -0.08885 -0.02230
No 3", 0.00 0.00 "lX 3b -0.26637 4.10056
NP 37 0.00 0.00 'IX 37 -0.55227 0.12MO
No 38 0.00 -2.25 NX 38 0.0'1677 3.98208
NP 3° -14.70 4.06 'IX 3" -0.5835\<> 0.13641
'1P 40 0.00 0.00 'IX 40 -0.20621 4.08144
'10 41 0.00 0.00 'IX 41 -0.'16568 0.26435
'1P 47 0.00 -2.25 "'!X 42 0.13821 3.q6b3'1
NP 43 -14.70 4.06 'IX 43 -0.'16568 0.26435
NO 44 0.00 0.00 'IX 44 -0.14604 4.06233
'1P 45 0.00 0.00 NX 45 -1.218'18 0.350'17
'10 46 0.00 -2.25 'IX 46 0.12801 3.'169'18
'lo 47 -14.70 4.06 NX 47 -1.258'13 0.36323
'1P 48, 0.00 0.00 'IX 48 -0.07301 4.03843
'10 49 0.00 0.00 NX 4" -1.35411 0.3'1891
0.0781'1 'O NP 50 'IX 50 0.00 -2.25
NP 51 -1.35411 .~e 3.'188160.3'18'11 'IX 51 -14.70 4.06
No 52 0.00 0.00 'IX 52 0.00001 ~ 4.01453
No 53 0.00 0.00 NX 53 -1.35785 ;: 0.4043'1
No 54 0.00 ,1>.00 'IX 54 0.00001 j 4.02054
'10 55 -14.70 4.06 'IX 55 -1.30304· 0.37563 'Cumbrera con
'lo 56 0.00 0.00 'IX 56 0.01304 3.'18858 viento
No 5V 0.00 0.00 NX 57 -1.35411 0.41300
NO 58 0.00 2.25

Figura E2-Se

<!-- p. 119 -->

EJEMPLOS DE DISEÑO 119

ll)AOING CC'NOlTtON NO L')"01 "IG (('NOI T I OH NO
OeSIGN eNO "O"'ENTS DES IGN eNO _O"ENTS
"INO ANO AXIAL FOR WINO "'f"'l~ER. cORRecreo FO" 'e. ANO CORRECreo AXIALJIIEfIIl8!:R
FT-I( K FT-K FORCE. INfU ENOFIRSTt. INfU ENO K FORCE. F JASO....
1 -34.43 8.15 0.00 -32.00 -301.56 -0.00
2 108.136 11\<;.81 , -112.38 -i so.vo
0.00 0.00 4
llq.~7 5 lO8.fIJ6
6 -2Q.S6 -45. qq
7 -R2.82 -86.S5
O 1.17 11.15 eO.18 • 75.26 • -"O.IlA In 10. -32.07 -42. lQ 11 -53.2'5 11

i '2s 51.~O14,34 12 30.6422.31
\-1)'5,71 14 -35.e'5 14
\-2'3.6\<:1 1.27 15" 15
16 21.51 16 33.46
17 22.82 17 -lJ.'H
l. -40.'56 .lt:l: -63.10
'5.(118 1t"".32 l' ,. 70 44.62 20 28.68 21 -5.136 ,. -5fl.o;9
22 -45.01 -11.42
23 80.31 35.44 23
\-180.46 -704.~A 24" -40.12 -125.12 -142.fIIJ -236.8'5 24 ,. -8Q ..21 236.R5 Zo;t1t. '35 -7.20 704 •.98 103.2'5
\7. -13.50 -2'511'.3'5 93.45 2. 17.16 -len.Z5 -17.f'3 77 -73.'50 -Q3.4'5 -0.00 "2' 11.16 11.A~ 0.00 2"- 0.64 ,. O.MI
lO 74.41 lO -24.3t>
30 -41.05 q.32 '0 4.51 -1'1·.70 31
'73.4~ -23.33 37 " -50.7'5 16.\<n " -41.o~ 34 H.l.l 14 " " 0.00 0.00 35
36 -23 ..33 13 36
Q • 4 3 ",7 -{Il.'5 24.45 31 0 3R -80.10 ,. 27.42 3' -14.70 ,. 4.'51
40 8'9.12 40 -ZQ.16
\-6.'91 41 3.16
42 -80.79 47 2°.11 "4' 0.00 4' 0.00

1.'98 -9.22 .-
46 32.53 .-4.44 -7'9.1f>8'9.12 44 -2'9.17
47 1b.5A 41 -1'1.10
40 8'9.12 4R -31.67
4' -9.22 4' 7.70
50 -7'9.76 40 32.53
41 0.00 51 0.00
52 1'19.12 52 -31.67

\-80.79 44 54 35. '8
4.')1 54 -lit.70 "54 -6.'90 43 -3.1lI1
\5. 73.43 -32.6\<> 2It.4'5 ..57 -1.21
\5. 33.09 -80.1\<1
0.00 "5.50 0.00 .0 13.43 60.. -'2.6°
.1 -"0.75 61 7.62
62 --U.OS .? 26.10
4.0f> ., -11t.70 .,64 -22.53 .4 0.64
74.41 64 -13.'54
26.10 -41 ..05 .7•• 13.29 180.00 ...7•• -7).50 I'n.\<tt6 0.00
.0 13.7.'9 6Z.4~ -180.01 -73.'50 2'51.35 -'9'3.46 •• -89.27 -236.8'5 -2"'.35 6.28 -42.31 -h7.4A-0.01 10•• -125.12 t42."~ 236.85 ••70 -21.64 -H''¡.'!'9 42.32
35.44 7, 1.27
\-'51. 0 ?
\~o.\<n 12" -45.'91-5.A'" 7, 1. 28.68 14" )6.1 A " 11."8 15 -)6.02
\7. -40.116 7, -1I1.J7 11" 22.'t2 77 61.15
21.14 1.
70 -13.6'9 2l.'n ,.,. -13. "2
00 -)5.85 00 -4".23
\~1.~0 01 Vt 103.
02 1R.OC! .,O~ 14.)4
\-53.25 O, -110.62
\-32.01 R4 -40.46 ••" 80.1c! 139. ~Z
1.11 '6 •• ..
R1 -!41.\<ClIZ'.04 •• 01 -82.82
\-29.56 00 -31.10 •• 1011.81 ••'0 0.00
.,O, -112.)ft108.81 ., -)4.43 -fIl. 75 -0.00

Figura E2-Sj

<!-- p. 120 -->

\~ -
rnr- tr1
2::
NT -cE tr1Z
,..; dV'J
'V-. I -c O
"" tr1g
E V'J rn
"'",-..: Z· O
O
tn ~
\-r.r: 2::;¡. ~3
\~r-- ::o8 ""ci !fl "" ;¡. E ::o ;,. or. V> (1) ~iI(24) ( 70 ) (93) -D 2::;¡.

\~I V> '" V> ~ Oe::o .=- ;¡. o·Sox"'"";'~ V'J -c f'i""-'",;:: I
\~ -gi ::::: -\<-ee 10(0 12' _ ~ 6(al~)'72'
120' 6 (a 3.6 m tr1z I -21.6 m LI'~---72'6!a 12' -l· 10(a3.6m ~rn I 6!a3.6m I
• 21.6111 -. 36m V'J

Figura E2-5g

<!-- p. 121 -->

22 bays Cú 7.6 m

,,,do, lE·'"' m
0'= PLAN ..:.:
'\<t
"": ,.., E -o
'"
v, ~-o
30 'd 2'J.L ~..... ~ ~ .,..., .- '" .- , , ....
E
(68) \<tr' '"r-.
No

",,1 '\<t ~~~

15
\-o
o-o E tTl
'-rn V)'\<t V) '\<59m~.25I(l) 1(24) (70) (93) 3:
\~ 'ti
..:.:
CIl5 Nr-o O
0- tTl
O
6 @ 12' 10 Ca: 12' I 6 Ca: 12' Vi I tTl : 72' 6 @ 3.6 ~:d 120' io s 3.6 m --:¡:--72' 6 @ 3.6 md Z' 21.6 m 36 m 21.6 m O
...Figura E2-6a N...

<!-- p. 122 -->

122 ELEMENTOS DE DISEÑO DE MARCOS, ARMADURAS Y PUENTES

Columnas de los cobertizos (miembros 1 y 93): W610 x 241.1:

peso = 0.72 kN/m A = 30.77 X 10-3 m2 I, = 2151.9 X 10-6 rrr'

Dos columnas interiores (miembros 24, 25, 27,28,67,68,69, 70): W690
x 264.9:

peso = 0.99 kN/m A = 33.74 x 10-3 m2 I, = 2 909.5 X 10-6 nr'

Sigue ahora el cálculo de las cargas de la armadura:

Techo =O.72kPa
Varios elementos, incluyendo largueros = 0.24 kPa
Total = 0.96 kPa
Carga/m sobre el marco = 0.96(7.6)= 7.3 kN/m

Carga muerta de la armadura: nótese que ésta se calcula directamente
como una proyección horizontal.
. Armadura principal:

Longitud de la cuerda superior e inferior = 2(36) =72m
Longitud aprox. de las diagonales = 10(5.84 + 8.3)/2 =70.7m
Longitud aprox. de las verticales = 11(4.6 + 8.2)/2 =70.4m
36W = 72(0.301) + 0.169(70.4 + 70.7) = 45.52 kN
W = 4~.~2 = 1.26kN/m

Peso muerto de la armadura del cobertizo:

Longitud de la cuerda superior + la cuerda inferior = 2(21.6) =43.2m
Longitud aproximada de las verticales = 5(0.9 + 4.5)/2 = 13.5m
Longitud aproximada de las diagonales = 5(3.71 + 5.26)/2 =22.4m
21.6W = 43.2(0.301) + 0.169(13.5 + 22.4) = 19.1 kN
W = ~~:~ = 0.88 kN/m se usaO.90 kN/m

La carga de nieve se toma como 1.2 kPa (proyección horizontal):
s- = 1.2(7.6) = 9.12 kN/m • m

Tómese como proyección horizontal, ya que la pendiente de la armadura es muy pequeila y los váÍo-
res son estimados.

<!-- p. 123 -->

EJEMPLOS DE DISENO 123

En la figura E2-6b se muestran fuerzas típicas en los nudos de los cobertizos y
de la armadura principal para las cargas muertas combinadas con las de
nieve, que se acaban de calcular.
Se calculan como sigue las cargas de viento. Supóngase que los efectos
del viento son como los que se muestran en la figura E2-6c y úsese el perfil de
viento del NBC en el lado de barlovento de la estruc5JIratal como aparece en
la figura E2-6a. Se tomarán las cargas de viento, normales y hacia abajo en el
cobertizo de barlovento, normales hacia afuera en la armadura principal de
techo, más la carga muerta, y 1.55 vecesla carga de nieve, más la carga muer-
ta en la armadura del cobertizo de sotavento para tener en cuenta los efectos
aerodinámicos sobre la armadura principal y la acumulación de la nieve adi-
cional, procedente de la armadura principal de techo, sobre el cobertizo de so-
tavento.
Partiendo de estos datos, se muestra en las figuras E2-6d a E2-6finclusi-
ve, la entrada y la salida editada de la computadora. Nótese que los efectos
más críticos del viento se producen en la porción mostrada de la salida, excep-
to para la columna de barlovento, que aparece en la lista siguiente:

Miembros F 1 (axial), kN F2,kN F3,kN·m

24 -206.2 -941.98 -873.24
25 -23.86 873.24 296.57
26 78.75 -296.56 -53.11
27 78.75 53.11 0.01

D= 0.9 + 7.3 = 8.20kN/m 5= 9.12 kN/m lit-tan-. I ~-21.6-14. 040 I111111111111111111111111111111111111111111111
P23 = 62.35
P29 = 31.18 14.04° ~ ~
PII = 62.35 P7=3.6W+5J
P7 = 62.35 I E "': = 3.6(8.20 + 9.12) = 62.35 kNP3 = 31.18 kN ~ t V)
P3 = P29 = P7/2 = 31.18 kN ~
21.6 m

D= 8.56 kN/m 5 = 9.12 kN/m •
1IIIIIIIIIIIIIlIIIIIIIIIIIIIIIIIIIIIIIII
P = 63.65 P43 = 63.65
39

P 35 =('82 ~ ~
P39 = 3.6 (D +5)
\= 3.6(8.56 + 9.12) = 63.65 kN 11 =tan··1 3.6
P 35 = P74 = P39/2 = 31.82 kN 18
\=11.31°

Figura E2-6b

<!-- p. 124 -->

124 ELEMENTOS DE DISEÑO DEMARCOS, ARMADURAS Y PUENTES

P3= 16.42+D = 164'.• +-(36)8.22 . + T(3.6)9.12

\= -.47.6 kN
Pn=9.12 ~cos é = 33.84 k r.4~ 4.10 kN

P7 = 32.83 + 3.6(8 7
\- ·-95.19 kN

Tómese nota del . + 9.12).s.:\:lirQQ=rr~g1~~~LJ.i~~~$~">---l-matriz P signo.- ( - ) para la
r.
• Pi = 4.10 + Pí.
PÍrp¡ == 41[12(1. ..5)+0.96(6)+0'O + 61 56 _ .7.(0.75»)76. = 61 56 kN
. - 65.66 kN .

PJ5 = 24.62 D = 24.62 . 8 .56 -3.6 9
39 = 49 '4 2 = .21 kN
P .• ···8.56(3.6)
P39 = 18.42 kN

\~9.24 25.11 r, = 13.68 (.li..\-cos Or 50.22 kN 49 O 4924 .24 24.62 49.24 t49~:85 t 9.85 9.85 ¡.;'85 ~ ~ • "" 9.85 \,44(\.1.S)n.6)" \3.63 k~lll\ d~

•

Pj4p' _-- r:h + Pw =1.44 (2.3)7.6 = 25
Ph - _,1.44(2.3)(76)-. -25.17
34 4 . 92 = 20.25 kN
\- _5.17[1.44(~- P31 = 2 - 0.8) + 1.2(30 - 29. 2 ) + 1.2"":""723 ]7.6=57.0kN.

Figura E2-6c

<!-- p. 125 -->

EJEMPLOS DE DISEÑO 125

STtH~I:SS foIIETHOO OF R:tGID FRAME "NO Ttl:USS ANU,SIS

NO OF le,t,Q CONDIT ,. ,. NO OF ,",p hO OF fIIlEfillftERS 106 ,
• METRtO NO NC'N-l~RO. ., P • N'1 NLe TD wttofO "lC 11 ""Elote ., , . 1
NO tHIFF lFllClEO " foIIOD HASTtCtT'I' ,. 200000.0 ••• Nle FOIl o • l . o NlC FOA. WIND Ofll 8E'•• o
""E~AEo NPI NP2 NP3 N04 NP'5 NP6 (05 SIN ffllll Fe"'?
1 101 101 101 1 , , 0.00 16'500.00 0.308E-Ol 0.215E-02 164~.qq 0.00000 1.00000 0.00 0.00 , , , • 1 , , , • 51 ooo ooo '600.00)600.000.00 900.00"00.000.00 0.21AE-02O.'3nE-D2D. 'Q1E-02 0.0000.000C.ODa 3600.00~710.900.007q 0.00000O.'HOH1.00000 0.242540.000001.00000 0.000.000.00 0.000.000.00 •5 • 5 • o o 3600.00 0.00 O.391E-02 0.000 '3600.00 1.00000 0.00000 0.00 0.00 • 1 • . o o 3600.00 -seo.oe O.ZlRCl-02 0.000 3110.79 0.'97014-0.24254 0.00 0.00 1 • 1 10• 11. o o '60Ó.OO qOO.OO O.391E-02 0.000 3110.7'9 D. "7014 0.242'4 0.00 0.00 • 0.218e'-02 0.000 1800.00 0.00 10 O O 0.00 1800.00 0.00000 1.00000 0.00 11 ·, • 0.00 O.3cne'-02 0.000 0.00 0.00 0.00000 l> 13 O 3600.00 1.00000 O 3600.00 , . 10 10 11• l> 13 O O 3600.00 -1800.00 0.218E-02 0.000 4024.Ql 0.8944"-0.44721 0.00 u.eo
11 10 11 14 15 O O 3600.00 CJao.oo 0.3qlE-02 0.000 3710.1q 0.ql014 0.242'4 0.00 0.00 1>· 13 14 15 O O 0.00 2100.00 o. 218E -02 0.000 2100.00 0.00000 1.00000 0.00 0.00
13 l. ,1 O O 3600.00 0.00 O. 3QlE -02 0.000 3600.00 1.00000 0.00000 0.00 0.00 " 0.00 3600.00 -2700.00 0.1l8f-02 0.000 0.00 ,4 O O 4'00.00 0.1!I0000-0.60000 l. 11 14" qOO.OO 0.3qlE-OZ O 0.00 0.00 0.000 O ~600.00 l5" 15 l. 3710.7q 0.97014 0.242'4 14
O 0.ZI8f-0? 0.000 3600.00 0.00 "17 0.00 3600.00 0.00000 1.00000 0.00 O l. ,.
¡7 O 0.000 0.00 0.3QU:-02 3600.00 0.00 0.00 1.00000 0.00000 O 3600.00 ">l l. 11 "zo l' 15 '0 >l O O 3600.00 -3600.00 0.218E-02 c.eoc 'iOCJ1.17 0.1071 1-0.70711 0.00 0.00
0.00 900.00 0.3qlE-02 0.000 3710.n 0.00 >3 O O 3600.00 o. Q7014 0.242'4 az l. .. l'"
0~00000 O 0.00 0.00 0.000 O 1.00000 0.00 4500.00 0.'-18E-02 4'00.00 >3 >l '0 '0
0.00 O 'QlE-OZ 0.000 0.00 o. 3600.00 0.00 >5 O 3600.00 1.00000 0.00000 >l ze ">l '0
\~? 5762.81 0.00 0.00 3600.00 -4500.00 0.ZllIE-02 0.000 O O D. 62470-0.78087 >3 ,.zz ,. 900.00 o. ]QlE-02 0.000 3710.79 0.00 0.00 O O 24Z54 3600.00 0.97014 O. ,. lO >3
\>4 107 " 107 107 0.00 16500.00 0.337E-Ol O.2Q¡e-02 164'99.99 0.00 0.00 0.00000 1.00000 lO ,. ,." 0.2Q1E-02 539"f.QQ lO 5400.00 0.3371:-01 0.00 0.00 0.00000 1.00000 >5 '1 ze ,."
o.zq lE-02 ,. 7300.00 0.3"lTE-Ol 7300.00 0.00 11 0.00 0.00 0.00000 1.00000 ,. ,. ",. 0.00 O.zqlE-OZ 0.00 4600.00 0.3371:-01 4600.00 0.00 31 0.00 0.00000 1.00000 as 'o
0.00 0.3Q1E-OZ 0.00 0.000 3600.00 0.00 .-"O "O 3600.00 1 • 00000 0.00000 31 3> ,7'O
71111~1 0.00 0.00 O ae?1 ,. -4600.00 0.ZUE-02 0.000 0.61631-0. ,."3. " 31 O 3600.00 lO '841.23
3671.1Q 120.00 0.3QlE-02 0.000 0.00 0.00 39 O O 34 3600.00 0.Q80'!'i80.1Q612 ,. .- " 531q.Qq O 5'!ZO.00 0.000 0.218E-02 0.00 0.00 39 0.00000 1.00000 O 0.00 '1 ,. ,. 0.000 0.00 0.3Q1E-OZ 0.00 0.00 O 3600.00 3600.00 1.00000 0.00000 3. 31 41 O '0
o.~ljOOO 30" 0.00 O O O.'llql) 0.00 6040.00 O.Z1RE-oZ 0.000 1031.4t6 43 3600.00 3. 31 .,
0.00 43 O 0.1 120.00 0.1'91E-OZ 0.000 3611.20 O. Q80,e Cl612 0.00 O "34 3600.00 39 ., " 6040.00 0.218E-02 0.000 0.00 0.00 O 0.00 603'9."Q 0.00000 1.0000n 41 43 O ., '0
0.00 0.1911:-02 0.000 0.00 45 3600.00 1.00000 0.0001)0 0.00 40" O 3600.00 41 4' o ,. ~11"8-0.85QOO " 3600.00 -6040.00 0.21U-02 0.000 0.00 0.00 45 7031.46 O. 43 O O H ., ., 43 •• '1 O O 3600.00 720.00 0.3Q1E-OZ 0.000 3671.2Q 0.98058 0.1'961Z 0.00 0.00
44 45 •• 3' •• 40" 45 '4 .1 oO OO 3600.000.00 6760.000.00 0.2HtE-020.3Q1E-OZ 0.000e.eco 6760.003600.00 0.000001.00000 0.000001.00000 0.000.00 0.000.00
0.00 0.00 0.000 8301.Z2 7480.00 0.218E-02 0.43367 0.90101 O 51 O 3600.00 41 4' 45 •• 50 ..
0.1l~6t2 3600.00 720.00 0.391lE-02 0.000 0.00 0.00 50 O 3671.29 0.Q8058 51 O ., 43 •• .. 50 51 O O 0.00 7480.00 0.2181:-02 0.000 1479.Qq 0.00000 1.00000 0.00 0.00 4' •• •• 5> 53 O O 3600.00 0.00 0.3Q1E-02 0.000 3600.00 1.00000 0.00000 0.00 0.00 45 ••50 ••51 5> 53 o O 3600.00 -7480.00 0.218e-02 0.000 8301.22 0.43367-0. "0107 0.00 0.00
50 51 55 O O 3600.00 720.00 O. 3"IE-02·0.00'0 1671.2" 0.'980'8 0.1'1612 0.00 0.00 ••41 ., 43 •• 55 o o 0.00 8200.00 0.218E-OZ 0.000 81..... 0.00000 1.00000 0.00 0.00 ••

Figura E2-6d

Los miembros del edificio se han de diseñar para la fuerza máxima en el
miembro bajo cualesquiera de las condiciones de carga, y el que será, natural-
mente, simétrico. Las máximas deflexiones horizontales presentes son:

101.7 mm X 25 = 105.1 mm
X 6 = 106.4 mm X 31 = 90.4 mm
X 16 = 106.4 mm X 34 = 88.5 mm

La diferencia

90.4 - 85.8 = 4.6 mm

es el acortamiento axial neto de la cueraa mferior. En los próximos capítulos
se diseñará una selección de miembros de esta estructura, para ilustrar el mé-
todo de diseño de los miembros a tensión y compresión, y sus conexiones. / / /

<!-- p. 126 -->

126 ELEMENTOS DE DISEÑO DE MARCOS, ARMADURAS Y PUENTES

THE P-~ATQ:t)(t KN 'NO K-14M TH': X-flIIATPIX. 14M !lR R'OIANS

"R 1 0.00 0.00 NX 1 -0.0001'1 0.00'101
NR = 2 0.00 65.66 NX 2 -2.11252 '1'1.lJMO
NR 3 -31.lP -H.60 3 -0.400~7 -0.51275 4 0.00 0.00 "'xNX 4 0.06161 101.61240 ...
5 0.00 0.00 "X 5 -34.86252 -41.0802'1 ".N· 6 0.00 A.21 .. X 6 4.118AO 106.38340
"R 7 -62.36 -'15.1" "X 7 -34.86252 -41.0802'1
8 0.00 0.00 "X = 8 2.23574 104.08630 ".N. '1 0.00 0.00 NX -37.88237 -43.2321'1
0.00 8.21 = 10 104."1360 10 3.086'8 "
\-'15.1'1 -43.03146 11 -62.36 "'x.. X -37.75365 11 "."R
"R 12 0.00 0.00 NX 12 3.83557 10~.66430
0.00 -37.040'17 13 0.00 -33.37656 13 "X ... 14 0.00 102.24680 14 0.76"25 A.21 "X ... "R -'15.1'1 -36.43817 15 -62.36 -32.'1'103'1 15 "X
"R 16 0.00 0.00 "X 16 4.86116 lM.34650
0.00 0.00 -26.7'1018 17 -24.85272 "X
,·X ... 17lA 0.00 A.21 lA '1".453'12 -1."5573 "."R e 1" -62.36 -'15.1" "X 1" -24.0RO'?R -25.5856'1
5.312~" ZO 0.00 0.00 ZO 106.13320 "X ". 21 0.00 21 -1 '.A"'13" -14.36411 0.00 "X ... n 0.00 A.21 "X 22 -4.6'1145 '17.00620 ".N. 23 -62.36 -'15.1'1 "X 23 -12.61215 -12.35670
24 0.00 0.00 'IX ?4 -0.00175 0.00130 ". 2~ 0.00 0.00 "X 25 5.18"86 105.02440 ". 26 0.00 0.00 "'X 76 -1.32775 -0.67222 "."R = 27 0.00 0.00 77 -0.00163 -0.00227 "x '1~.8'1003 2A 0.00 4.10 28 -6.674"5 "X
\-31.1A -47.60 -0.6'l767 NX -1.63753 2' 2° ...
0.0012~ 30 0.00 -0.00023 0.00 NX 30 ...N.". 31 0.00 57.00 NX 31 -6.41213 "0.318'14
H 0.00 0.00 -0.58411 "R 32 -1."8181 "X
'3~ 0.00 0.00 -0.00051 33 0.00173 "X ... 0.00 20.25 = 34 NX 34 0.7'14"3 ...
3~ 35 -31.82 '1.21 -0.51255 NX -2.1'1875 "."R 36 0.00 0.00 NX 36 -6.3'1507 '10.4213088.3'1206
N. H 0.00 0.00 NX 37 -13.27372 2.'1"750
\= 38 0.00 -'1.85 NX 2.32"60 87.8 0621 N·". lA.42 3" -63.65 NX 3"
40 0.00 40 '" -14.05036-4.QCj20Q "0.01476 0.00 "X ". 41 0.00 0.00 "X 41 -23.18555 6.2"02"3.2462'1
42 0.00 -'1.85 87.41147 3.320'18 "..... 43 -63.65 18.42 43 -23.18555 ... 44 0.00 44 0.00 "'x"XNX 42 -3.50'110 8".60822 ".N· 45 0.00 0.00 .. X 45 -2".2564A 6.2'102"8.3R120
46 0.00 -".85 "X 46 3.081.1 87.4"551 ". 47 -63.65 18.42 8.6'1736 47 -30.24336 "X · ... 48 0.00 0.00 loA -1.75330 8".06'126 "X ...
\-32.50~23 4. 0.00 '1.54463 0.00 4. "X
\~O ..."l. = 0.00 -'1.85 NX 50 I.A8365 87••3.67
51 -63.65 lA.47 NX 51 -32.50523 '1.54463 ". 52 0.00 0.00 NX 52 0.00250 88.53032 ... N. • 53 0.00 0.00 NX '1.68'1"3 53 -32.58763
55 -63.65 18.42 NX 55 8.'182'13 -31.26768 ". 54 0.00 0.00 .. X 54 0.00251 88.7356'1 56 0.00 0.00 NX ••3411 ,56 1.75830 87 ...". 57 0.00 Q.Q14QZ 0.00 NX 57 -37.50520 ... . 58 0.00 '1.85 NX 58 60577 -1.87863 8s, .... 5. -63.65 lA.42 NX 5· -32.50520 '1.'114'12 ". 60 0.00 0.00 NX 60 3.5140. 87.337.1 ". 61 0.00 0.00 NX 61 -2•• 25644 ".1"504 .... 62 0.00 '1.85 'IX 62 -3.07688 "0.27214
\-63.65 18.42 63 -30.24335 "X ".... 6'64 0.00 0.00 4.'15706 86.71817 "X 64 ". 65 0.00 0.00 "X 65 -23.18552 '1.511147.20518 .... 66 0.00 '1.85 NX 66 -3.315'14 .0.50"'1'1 ". 67 -6).65 lR.42 .. X 67 -23.18552 7.2051A ".·". 6"68 -63.650.00 18.42•• 85 "X"X 6'168 -14.05033-2.32453 .0.461034.1.31'1 ".. 70 0.00 0.00 "X 70 6.40001 86.0'1"64 ". 72 0.00 0.00 72 -0.00173 0.00058 ...". 71 0.00 0.00 "X 71 -13.2n6q 3.'14440 73 0.00 4.'12 73 .0.08044 ..x"X -0.78"86 ... 74 -31.82 '1.21 'IX -2.1 '1817 -0.23628 74 · ... 75 0.00 0.00 75 NX -0.00125
76 0.00 0.00 76 6.41703 85.73734 "X ....... 77 0.00 0.00 77 -0.2'102'1 -1."8183 "X ... · 78 0.00 0.00 "X 78 0.00163 0.004270.00167 ". 7'1 0.00 7'1 6.67801 0.00 "X ... 80 -31.18 -3'1.3'1 -1.63755 -0.375"'1 "X 80 ". 62.'1'1757
Figura E2-6e

<!-- p. 127 -->

EJEMPLOS DE DISEÑO 127

lO"OIMG tDJrtDt"tON 'fa • LOADING CONOtTION Ne . OESte .. eNO NOflllENTS OIEStGN ENO 1lI0MeNTS
FE" ANO ..,INO ME"'6€~ AXIAL COA:REC TEDfO. AX'Al COtt«ECTED FOA:"f-,e..
FORce. FO"CE. t CNfU ~"" FIRST , ,,"-M CfrIEAI EtIlO FI.S'" FE" ANO1("'""INO
\ -14'.40 10.02 0.00 -1"3.43 -:!~2.62 -0.00 ~'3'T.fl.O". 41Z.Z7". 2
3 -4~7.4? -5~2.2'5
0.00 0.00 •S 472.27 •, 537.. 31:'
\-12ft.50 o -200.'i2 •1 -31J8. A4 1 -400.24
o 31.18 o 48.62
347.52 342.11 \0 -13Q.46 \0. -2l7.4'?
\-20e.z~ -230.21 11 11 · \2 12 en.'.4
13 2t~:~: 13 148.20
\-l~l5.qo \. \. -243.13
\-101.71 \, -16.28
\0 Q3.'54 \. H5.flft "11 98.0b \1 -46.34
\0 -176. 'lA \0 '"'275.06
\. 26.85 \. 115.72
zo 124.12 20 1~.50
'\ -26.66 2\ -240..86
22 -IQ9.65 n -"311.1.-
?1 155.41 '67.71
\>4 -543.01 -190.09 -313.62 l' -206.1 -IUZ.91 , ·'U.52 ,. -3(117.11 -23.8~ >5 'HR." 296.55 >\< 1!172.9' -~3R.qq313.62 -311'.24 -Z96.~" I20.5e 2. 1ft. 73 -53.01
21 -'lA.l4 ,T -120.';13 0.00 7R. 1~ ~3.08 -0.00 " 3.11 22.23 ,. 2. 320.24 -lU.cH ,. " -114.54 '0 30 34.66 ,\ -63.M 3\ 20.3'1'
31'3.45 12 -88.~1
\-21'1'.49 33 33 7'1'.83 " 34 -114.54 ,. ".10
0.00 0.00
\-88.31 " 31'3.45106.~3 3631" -41.63 ,O -344.76 llA.12 'O '." 3· -63.65 20.3C1 ,. '0 -111.01 3''l.40 '0 .\ -30.92 .\ 17.06
.2 -344.16 '2 128.16
381.ltO -111.01 43•• -'38.950.00 43 0.00 •• 6.5ft
.-341.21 .. llt2.80 ••'T 70.18 ...1•• -'37.lIjq
.0 381.40 .0 -129.'il
\-38.95 35.H ..'0 -341.Z1 ••,O 142.1'10
.\ 0.00 .\ 0.00
52 381.40 52 -129.51
\-30.CJ2 -17.5\<)
\-344.76 54 ,. 15".Ollj " " -63.65 20.39
313.44 56 ..56 -134.49
S1 lGb.53 " -5.28
\-344.76 146.01 0.00 ••54 "..54 \<o 313.44 .0 -134.490.00
.\ -21\<).49 ,\ :!3.61
.2 -114.54 '2 115.59
03 -63.65 63 20.39
O. 3.70 -18.10 320.2,. •• -62.62
\-174.51t 105.54 " .. -31".24 •• 6T 120.61 0.00 -0.00 '\9.42 ..6T 206.8'
\-31~.24 338.'~ -120.61 lD4.U -206.'0 'i9.41 'O -~fn.ll •• -31'3.63 -338." -90.00 -104.U 24.40
\-~43. 'O 02 10 1'-'0.09 313.63 .a.OO .. •• -123.31 -140.66
11 155.41 1\ ~O.08
T' -lqq.66 T2 -2'\2.22
"14 -26.66124.26.85 13 113.70 73 T4,. -132.34
10 -116.34; 1. -222. "3 " 151.56 T1 98.0'7 71 211.24
TO q3.55 10 lU.18
10 -ltH.12 T. -2".79
00 -155.92 00 -lq6.96
lIH 22l. 428.7q '1 .\O, 62.31 78. '19
3D O' -2~0. O,02 -451.23

586.36 ••O. -139.41 -116.20 31.1A ...,O, 3Q.40 ••91 -358.IHI347.11)6 .1 -61\<).71 O. -128.61 -162.48
472.33 .,O, 143.96 .0•• .0 0.00 0.00 .\ -487.49 .\ -182.21
.2 4'12.33 .2 143.95
\-149.41 -10.03 -0.00 .3 -111.83 -184.61 -0.00 .'
Figura E2-6f.

<!-- p. 128 -->

128 ELEMENTOS DE DISENO DE MARCOS, ARMADURAS Y PUENTES

PROBLEMAS

Los problemas que aparecen a continuación son de dos tipos. Los cuatro primeros problemas tienen
como fin que el estudiante aprenda a usar el programa de computadora que aparece en el Apéndice
para resolver los problemas estructurales. (Se pueden usar también otros programas de computadora
tales como el STRESS o el STRUDL, pero es probable que ~ogramadel Apéndice sea más rápido
de manejar). Úsese E = 200 000 MPa o 29000 kips/pulg/, Se obtendrán los resultados en unidades pie
lb s o SI, según lo solicite el profesor.
Se debe elegir uno de los tres últimos problemas para ser usado en el diseño de los proyectos que se
deben resolver junto con otros problemas de los capítulos subsiguientes.
2-1 En la viga siguiente: Obténgase una sección W que limite la deflexión en el punto A a 1 pulg ó
'l5 mm. Nótese que todos los NPE(2) se pueden volver NPPI.
Respuesta: M A = 171.6 pie-kips, 6236.2 kN·m.

..1

Figura P2-1

2-2 Se presenta la siguiente estructura académica. Hállese una sección W que limj~fieXi6nen el
punto A a 0.5 pulg Ó 12.5 mm. //

E.T NV
\<i-
1 1_

Figura P2-2

2-3 Para la armadura dada y las cargas muertas mostradas aplicaldas a la cuerda superior, y donde se
utiliza un par de angulares de tamaño constante, con los lados largos espalda con espalda para las
cuerdas tanto superior como inferior. hállese un angular de tamaño tal que o bien se use el mayor par
obtenible, o la deflexión en el punto e se limite a 2 pulg 6 50 mm, para la carga viva m6vil mostrada.

<!-- p. 129 -->

PROBLEMAS 129

Se aplicará la carga viva solamente en los puntos B, e, y D Yno en puntos intermedios. Usese E =
29000 kips/pulg- ó 200 000 MPa. La carga viva es de 20 kips o 90 kN, Yse aplicará a un solo nudo cada vez, junto con la carga muerta.

3 3
14 kN 14 kN

e
tI 4 paneles @,20' = 80'
1.. (4 panelesw 7 m = 28 m) .1

Figura P2-3

2-4 Itérense los cálculos para elmarco mostrado en la figura, hasta obtener que la deflexión lateral y la
deflexión vertical en el punto e no sean mayores de 0.5 pulg. o 12.7 mm. No será aceptable el uso de
la más pesada sección W, hasta que se pueda demostrar que es el único camino viable. Otros datos:
Carga muerta de techo =22Ib/pie2 (o el equivalente métrico de la tabla)
Nieve = 30 lb/piel
Viento = Valor del NBC (considérese una altura de 9 m en los puntos B yE, para el
viento en cualquier dirección).
Carga vertical colgada de un malacate en el punto D = 20 kips o 90 kN
Espaciamiento de las armaduras = 25 pies u 8 m
Se debe tratar de que las iteraciones no pasen de cinco.

e

Nota: Las juntas B, E, YF están "fijas"
Las juntas A, e, y D están "articuladas"

Figura P2-4

<!-- p. 130 -->

130 ELEMENTOS DE DISEÑO DE MARCOS, ARMADURAS Y PUENTES

Problemas de diseño

Comentarios generales. Se sugiere resolver uno o más de los siguientes problemas usando algunas estimaciones preliminares de A e 1, que sean apropiados al problema. Las soluciones se deben dibujar con
cuidado a fin de que muestren claramente las dimensiones generales, codificación y las dimensiones de
cualquier miembro usado, o alguna otra suposición. Los cálculos de disefio para las cargas vivas,
muertas, de viento, y de nieve, o las cargas de camión se deben tabular cuidadosamente de tal modo
que sea posible identificar fácilmente los errores gruesos. Se deben enunciar todas las suposiciones e
indicar el lugar donde se obtuvieron las cargas de diseño, tales como cargas vivas de piso, cargas de
nieve, etc. (National Building Code, Uniform Building Code, etc.),
Estas soluciones y datos de diseilo se deben conservar en una libreta de notas para que los diversos elementos se diseilen en capítulos subsiguientes, según se considere conveniente. Al final, o cerca
del final del curso, el problema se volverá a programar usando los valores de diseño para un nuevo
cálculo. Se deben inspeccionar los elementos para asegurarse que son apropiados y, en el caso que se
disponga de tiempo suficiente, se debe repetir el problema varias veces para llegar a una mejor solución.
Este es un plan académico de trabajo; por consiguiente, es preciso omitir un número considerable
de detalles de trabajo en el interés del tiempo disponible. El estudiante debe limitar las condiciones de
carga investigadas en las estructuras de los edificios a
Carga muerta + carga viva
Carga muerta + carga viva + carga de nieve
Carga muerta + carga viva en crujias alternas + carga de nieve (opcional)
Carga muerta + carga viva + carga de viento (el último NLC = 4)

Seco A-A
b e d

e

e

e

e

f

///~ V~""
g Sótano

Elevación

a a a a a b

e fE

d

Planta

Figura P2-S

<!-- p. 131 -->

EJEMPLOS DE DISEÑO 131

Este número de NLC para las estructuras de edificios se pueden resolver en una sola corrida de la
computadora (si se introducen correctamente los datos). Es preciso fijarse que habrá cuatro tarjetas
(una para cada NLC) a continuación de cada tarjeta de datos de los miembros de vigas, y con NPE(7)
\= Opara esta tarjeta (todas son vigas).
2-5 En la figura P2-5 se muestra un marco para un edificio de oficinas. Se supone que todas las escaleras y elevadores están situadas en el lado oeste. Trácese una razonable distribución en la planta de piso
(que será la misma en todos los pisos) para los corredores y espacio de oficina, y, utilizando los datos
apropiados de los códigos de construcción, calcúlense las cargas de piso, la reducción en las cargas vivas, etc., y estimando las relaciones entre A e / del orden de 1.2 a 1.5 (o sea, / de la viga = 1.2/co1y limitando las columnas a las secciones WI2 ó W31O).Obténganse y establézcanse las dimensiones bao
sándose en la siguiente tabla. La tabla de datos está dispuesta de tal modo que se pueden desarrollar un
grupo de diferentes problemas. Los resultados de la computadora serán algo diferentes, dependiendo
de los datos de entrada (aunque algunos miembros llegarán a tener las mismas dimensiones según
avance el diseño),

Dimensiones pie lb s SI, m

Parte a 26 pies ± 2 pies 8.0 ± 0.6
b 13 pies 8 pulg ± 16 pulg 4.20 ± 0.40
e 30 pies ± 2 pies 9.1 ± 0.60
d Igual que b Igual que b
e 12 pies 2 pies 3.75 ± 0.15
f 14 pies I pie 4.20 ± 0.30

rd

h
Puntal de g .2SI----+
rodilla

Columna e
de la grúa

f---------a-------"'i
Elev, A-A

N
\-tE Ta
\~
1-------7 crujías (~ b-------l.1
Planta
Figura PU

<!-- p. 132 -->

132 ELEMENTOS DE DISEÑO DE MARCOS, ARMADURAS Y PUENTES

2-6 Dado el marco de la figura P2-6, que muestra un edificio para usos industriales, supóngase al comienzo que la carga de la grúa produce un empuje lateral en la columna de un valor de 5 kips ó 22 kN.
Nótese que este análisis no incluirá todos los NLC de la estructura del edificio del problema 2-5.
Usense las dimensiones siguientes para analizar el problema que se considera.

Dimensiones pie lb s pie SI,m

Parte aa 60 ± 1.5 18.4 ± 0.40
b 30 ± 3.0 9.1 ± 1.0
e 29 ± 0.5 8.8 ± 0.20
d 13.75 ± 0.5 4.20 ± 0.15
e 7.5 ± 0.5 2.3 ± 0.2
f 20.0 ± 2.0 6.1 ± 0.6
g 3.25 I
h 6.0 ± 1.5 2.0 ± 0.5

a Esta dimensión debe ser consistente con la dimensión e

Notas:

l. El puntal de rodilla se articula a la columna, pero esta última es continua hasta llegar a la arma-
dura.
\2. La carga lateral de impacto de la grúa se aplicará en el punto de unión de la trabe carril con la co-
lumna, como se muestra en la figura.
\3. Se puede usar un miembro vertical opcional para reducir el valor KL/r de la cuerda inferior. En el
caso de que se use este miembro, debe estar articulado a la cuerda inferior, pero esta última será
continua a través de la conexión (por lo que experimentará flexión).
\4. Hágase un dibujo indicando donde se podrían colocar los contravientos, pero no se haga el diseño.

2·7 Dada la armadura para un puente de carretera, la que se muestra en la figura P2-7, efectúese un
análisis por computadora para la carga estándar de camión que asigne el instructor. Usense las siguientes dimensiones y datos iniciales:

Dimensiones/sección, pie lb s: SI:
25 ± 3 pies 7.5 ± l m

Miembros
Cuerda mrenorfl, 4, . ,. , 21, 25) W8 x 48 W200 x 71.4
Cuerda superior (6, 10, 15, 19,23) 2CI2 x 30 2C305 x 44.6
Verticales (3, 7, ... , 20, 24) W8 x 40 W200 x 59.5
Diagonales excepto 2, 13, 14,26 W8 x40 W200 x 50.5
Diagonales 2, 26 2CI2 x 30 2e305 x 44.6
Diagonales 13, 14 2 L3i x 3 x T. 2 L89 x 76 x 11.1

• Usense incrementos de 0.5 pies ó 0.15 m para obtener s = 25, 25.5-28 pies.

2·8 Dada una armadura de tablero inferior para el puente de ferrocarril que aparece en la figura P2-7,
efectúese un análisis por computadora para cargas Cooper E-80 ó E-llO, según indique el instructor.
Tómese un espaciamiento de 17 pies ó 5.2 m e.a.e. Se aconseja que las áreas tentativas de las secciones

<!-- p. 133 -->

15 19

26 "\.
\~rf---=----I._'---....>L..---"------>"--,.-"':"::""'-----"t:-----.:-,--.JL--=-=---'----=-='---~1 4 8
\~1 .14L....13

1--------------7 paneles@s-------------...

Figura P2·7

que se muestran en el problema 2-7, para la armadura de un puente de carretera se dupliquen aproximadamente para la primera operación de cálculo de la computadora.

Notas (para los problemas 2-7 y 2-S):
l. Los datos para la sección dada pueden ser aplicables a las dimensiones básicas y la carga HS 20.
\2. Al aumentar o disminuir la longitud de los paneles puede que sea necesario cambiar las dimen-
siones preliminares de la sección (un paso de aumento o uno de disminución).
\3. Es necesario obtener lineas de influencia (o su equivalente) para determinar las fuerzas máximas y
mínimas en los miembros. También se deben considerar el impacto y la carga muerta.
\4. Se puede usar el programa para las lineas de influencia que se presenta en el Apéndice, para perfo-
rar un juego de tarjetas de la matriz de cargas, para el programa de análisis de las cargas de las
ruedas en puntos previamente seleccionados a lo largo del claro. Se aconseja usar incrementos de 5
pies o 1.S m para la distancia entre ruedas.
\5. No se diseñe ningún tipo de contraventeo o soporte lateral, ya que no se dispondrá del tiempo sufi-
ciente.

<!-- p. 134 -->

Figura111-1 El "Picasso" de Chicago. Una enorme escultura a base de acero resistente a la corrosión, diseñada por Picasso, Nótese el edificio del fondo en que se utiliza una estructura de marco
de acero.

<!-- p. 135 -->

CAPITULO
TRES
COMPORTAMIENTO ELASTICO, PLASTICO y
POR PANDEO DEL ACERO ESTRUCTURAL

3-1 INTRODUCCION

Hay dos modos en el comportamiento estructural bajo esfuerzo que revisten particular importancia y que tienen considerable influencia en el diseño de los
miembros de acero. Uno de estos modos es el comportamiento del acero en la región plástica de la curva de esfuerzo-deformación (véase figura 1-3b). Antes de la
década de los setenta, este comportamiento particular por lo general se conocía
como "comportamiento plástico". Actualmente, se usa con bastante frecuencia
el término comportamiento inelástico; sin embargo, el lector debe proceder con
cautela al usar el término "comportamiento inelástico", ya que muchas personas
todavía restringen el término comportamiento inelástico a la región de deformación posterior al inicio del endurecimiento por deformación.
La tendencia de los miembros estructurales a pandearse bajo el efecto de esfuerzos de compresión constituye una segunda caraterística de comportamiento
de particular interés. Se puede definir el "pandeo" como la súbita flexión, alabeo
o arrugamiento del elemento bajo esfuerzos de compresión. Las placas, así como
las columnas, se diseñan usando ecuaciones que se han deducido como una combinación de la teoría y las pruebas de laboratorio y del reconocimiento de la existencia del pandeo en presencia de los esfuerzos de compresión. Estos dos modos
de comportamiento se consideran con brevedad en este capítulo, para proporcionar la teoria necesaria para los capítulos posteriores de diseño,

135

<!-- p. 136 -->

136 COMpORTAMIENTO ELASTICO, PLASTICO y POR PANDEO

En el diagrama de esfuerzo-deformación del acero se muestra en la figura
1-3b se indica que el comportamiento del material es casi lineal hasta el límite proporcional (E = o/e), es elástico hasta el límite elástico (Ey) , (las deformaciones
son recuperables) y se muestra un comportamiento plástico (del tipo inelástico)
hasta el inicio del endurecimiento por deformación Est. El comportamiento plástico se puede describir como la deformación debida a la ductibilidad del acero y
que Ocurre bajo esfuerzo constante por encima del límite elástico. Después de
cierta cantidad de deformación plástica, el acero tiende a endurecerse por deformación, y es posible un aumento en la carga, acompañado por deformaciones
adicionales. Esta región de la curva de esfuerzo-deformación representa una capacidad adicional de reserva de resistencia del acero, más allá del límite elástico.
La pendiente de la curva después del inicio del endurecimiento por deformación
proporciona el m6dulo de endurecimiento por deformacián (llamado a veces módulo tangente; sin embargo, se puede definir un módulo tangente desde el inicio
de la deformación más allá del límite proporcional).
Los ingenieros estructuristas diseñan comúnmente los miembros de acero para que funcionen en la parte elástica de la curva de esfuerzo-deformación. Algunos ingenieros utilizan la región plástica de la curva como base del diseño, aunque
las cargas reales producen esfuerzos que están en la región elástica de la: curva de
esfuerzo-deformación. Muchas de las ecuaciones usadas en el diseño elástico, especialmente las que se utilizan con columnas cortas y vigas armadas, se basan en
el comportamiento del acero en la región inelástica.

3-2 TEORIA ELASTICA y TEORIA PLASTICA DE DISEÑO

A mediados de la década de los cincuenta y a comienzos de la década de los sesenta se hicieron considerables investigaciones, en varios de los laboratorios estructurales de las principales universidades para desarrollar un método de diseño de
acero basado en el comportamiento del material dentro de la región plástica de la
curva de esfuerzo-deformación. Estas investigaciones tuvieron gran éxito como
nuevo auxiliar de trabajo hasta la general disponibilidad y uso de las computadoras digitales. El uso generalizado de las computadoras digitales con su gran facilidad para resolver estructuras, usando los métodos elásticos (clásicos), y en particular el método de la rigidez en la formulación de los problemas, puso de moda
dichos métodos, de modo que, actualmente se hace poco uso del concepto plástico de diseño. Sin embargo, como se ve a continuación, el diseño plástico es un
método muy rápido para muchas vigas y marcos rígidos de un solo piso, y a menudo da por resultado miembros algo más económicos (de peso más ligero). No
tiene ventaja alguna en especial, la utilización de la computadora digital en el diseño de esas diversas estructuras.
El diseño elástico se basa en la premisa de que el esfuerzo es proporcional a
la deformación, de modo que las secciones planas antes de aplicar el esfuerzo lo
i Aquí se utílizará el término "diseño plástico" para referirse a un método de diseño en que se
aprovecha el hecho de que la curva de esfuerzo-deformación es casi plana desde Ey a Est'

<!-- p. 137 -->

TEORIA ELASTICA y TEORIA PLASTICA DE DISEÑO 137

siguen siendo después de su aplicación, por lo que para una carga axial el esfuerzo
se calcula directamente como

y la correspondiente deformación es e = PLIAE = faLlE = €L. Se usa la conocida ecuación de la mecánica de los materiales para los esfuerzos de flexión.

No se debe olvidar que mientras los esfuerzos estén en la región elástica, será válido el principio de la superposición de efectos y que tampoco es importante el orden de aplicación de las cargas. Por lo común, el principio de superposición no es
válido, para deformaciones más allá de €y- Las deflexiones no se pueden calcular
de manera tan directa para las cargas de flexión como para las cargas axiales;
sin embargo, es posible usar las ecuaciones diferenciales de una viga que se dan en
la sección 2-2, para calcular la pendiente y deflexión de la viga. Se pueden obtener
soluciones de forma cerrada utilizando dichas ecuaciones, pero serán válidas sólo
para la viga dada, su geometría, y cargas.
Con el siguiente ejemplo se ilustra el concepto de "análisis elástico" .

Ejemplo 3-1 Una estructura está formada por tres barras de acero A-36 con
F; = 36 k/pulg-, conectadas por una barra rígida ABC, de tal modo que
existe traslación vertical pero no rotación en ésta (figura E3-1). Se pide en-
contrar la fuerza axial en cada miembro.

P3

Pi t
P2 t
t ~5
;O"". V) "ir, C> "'t o r- -Il Il M o Il '-.: '-.:
'-.:
A B e
2.5'

30k Figura EJ·1

SOLUCION Se debe tener en cuenta que para que el miembro ABC no ten-
ga rotación, debe haber compatibilidad de desplazamientos entre la longitud
de los miembros y las áreas de las secciones transversales.

<!-- p. 138 -->

138 COMPORTAMIENTO ELASTICO, PLASTICO y POR PANDEO

(a)

Como el miembro ABe es rígido y no rota,

(b)

De la mecánica de los materiales,

P¡(48) P2(36) P3(60) e = --....:....:...--=---- e =--..::..----- e3 = --;;"":""--'--- ¡ 0.64 X 29 X loJ 2 0.75 X 29 X loJ 1.0 X 29 X 103
(e)

La ecuación adicional que se necesita para resolver las fuerzas en las
barras (tres ecuaciones con tres incógnitas), se obtiene tomando momentos
en un lugar conveniente (sea el punto B), para obtener

2.5P¡ - 2P3 = O
2 P, = 2.5 P3 = 0.8P3

De las ecuaciones (e) y (b),

0.8P3(48)
e¡ = e3 = 0.64(29 (00) 1.0(29 (00)

de donde se obtiene
6OP3 = 6OP3 que comprueba que los desplazamientos son constantes

Además, de la ecuación (e):

48P¡ 36P2
0.64(29 (00) 0.75(29 (00)
P2 = 1.5635P¡
P2 = 1.5625(0.8P3) = 1.25P3

Al sustituir ahora en la ecuación (a), se obtiene
0.8P3 + 1.25P3 + P3 - 30 kips
P3 = 30/3.05 =9.836 kips
P2 = 1.25(9.836)= 12.295 kips
P, = 0.8(9.836) = 7.869 kips
Total =30.000 kips comprueba

<!-- p. 139 -->

TEORIA ELASTICA y TEORIA PLASTICA DE DISEÑO 139

Sustituyendo estos valores en cada una de las ecuaciones (e) se obtiene (e) =
0.02035 pulg (lo que debe verificar el alumno), / / /

Ahora se pasa a reconsiderar el ejemplo 3-1 usando el "análisis plástico" en
el siguiente ejemplo.

E3~2 (el mismo que el del ejemplo 3-1),Ejemplo 3-2 En el dibujo de la figura
¿cuáles serán las fuerzas en las barras, cuando las tres hayan fluído plásticamente?

p¡t

Figura EJ-2

SOLUCION Es preciso aplicar una carga factorizada de magnitud suficiente para que fa = Fyen las tres barras. En este caso, las fuerzas en las barras
son sencillamente

Además,
PI + P2 + P3 = P última O simplemente Pu
P; = 36(0.64) + 36(0.75) + 36(1.0) = 84.04 kips
Como la carga real es de sólo 30 kips, el factor de carga es Pu/P:

LF = = 8;: 2.87

Son pertinentes algunos comentarios:

\1. El análisis plástico es mucho más sencillo.
\2. La barra rígida ABe rotará bajo la carga aplicada Pu = 84.04 kips, lo
que no era el caso en el análisis elástico. ¿Por qué?

<!-- p. 140 -->

140 COMPORTAMIENTO ELASTICO, PLASTICO y POR PANDEO

\3. El análisis elástico (ejemplo 3-1) indica que la barra 2 cede primero. ¿Por
qué? Cuando Fy = 36 kips/pulg- en la barra 2, ésta no soporta carga adi-
cional sino que meramente se alarga con cualquiera carga adicional que
soporte cualesquiera de las barras adyacentes, hasta que lleguen a su vez a
Fyo Cuando se alcanza Fy en la barra 2, la carga en dicha barra es P2
0.75(36) = 27 kips.

Estableciendo una proporción con el ejemplo 3-1, la carga en este punto.será

p = 1~~i~5 (30) = 65.88 kips III

El comportamiento de las vigas basado en el análisis plástico es similar al problema de las barras. Considérese la viga de la figura 3-1. Si se aplica un momento
flector a la sección, la curva de momento-rotación (M-e/» será lineal t hasta M';
Desde el momento en que la fibra más esforzada de la viga está sometida al esfuerzo Fy (el que produce el momento de fluencia M y ) hasta el punto en que todas
las fibras de la viga estén sometidas a ese mismo esfuerzo Fy (que puede ser a tensión y compresión dependiendo del lado del eje neutro que se investiga) y que
produce el momento plástico M p , la curva no será lineal. Cuando se llega a M p , la
viga gira sencillamente en este punto, sin aumento adicional de la capacidad de
momento (o de esfuerzo) y se dice que se ha formado una "articulación" plástica.
Habrá un pequeño aumento adicional en la capacidad de momento cuando algunas' de las fibras de la viga que estén más distantes del eje neutro alcancen deformaciones dentro de la región de endurecimiento por deformación. Este efecto dependerá de la geometría de la sección transversal de la viga en los patines y en el
alma y, naturalmente, del claro de la viga y de las condiciones de borde. Si la viga
está cargada con un momento mayor que M, (pero no M p ) , y a continuación se
descarga, la rama BE de la curva se obtiene con una cantidad residual permanente
de rotación OE.
[Los perfiles estructurales laminados (W, M, C, etc.) contienen casi siempre
esfuerzos residuales causados por el enfriamiento diferencial.ll.as puntas de los
patines y las partes interiores del alma, al ser más delgadas y estar más expuestas,
siempre se enfrían más rápidamente que las otras partes del patín. La unión entre
el patín y el alma esla más gruesa y la más protegida de la sección y es siempre la
última en enfriarse. Los esfuerzos residuales de tensión se desarrollan en aquellas
partes que se enfrían a¡'último, ya que el metal tiende a contraerse pero se ve retenido por el metal más frío. Estos esfuerzos residuales de tensión producen esfuerzos residuales de compresión en el metal adyacente, que se enfrió primero. La soldadura también produce esfuerzos residuales, ya que el metal caliente y la llama
de corte en sus cercanías se ve restringido en su contracción por el metal más frío
que lo rodea. Los esfuerzos residuales se pueden producir por el enderezamiento

Dentro de la homogeneidad del material y las tolerancias del laminado, así como las limitaciones prácticas en las medidas.

<!-- p. 141 -->

TEORIA ELASTICA y TEORIA PLASTICA DE DISEÑO 141

e D Mp r----------::;;;"'O----::--,l:r------------,-

\-I---

R
M = My en el punto A de la curva M - q,

F\<F" M(

M \< My en cualquier punto entre Oy las cercanías de A,

Rotación de la viga, q, ----.

Figura 3-1 Momento vs. Rotación para un perfil W.

de los miembros doblados y durante el proceso de formado en frío de los perfiles
estructurales, doblando en frío placas de metal hasta obtener la forma geométrica
deseada para la sección. En cualquier caso, casi todos los miembros de acero contienen esfuerzos residuales tanto de tensión como de compresión, lo que tiende a
producir una excentricidad neta en la sección transversal.éfin la figura 3-2 se
ilustra de manera cualitativa (y algo cuantitativa) la distribución de los esfuerzos
residuales debidos a causas térmicas en diversos perfiles laminados.
Los esfuerzos residuales debidos al enfriamiento diferencial tienden a depender en grado sumo de la geometría de la sección, donde las secciones más gruesas
tienen esfuerzos menores. Por ejemplo, una sección Wl2 x 65 puede tener esfuerzos de compresión en el alma y en las puntas de los patines del orden de 15
kips/pulg-, y esfuerzos de tensión en la unión entre el patín y el alma de unos 12

<!-- p. 142 -->

142 COMPORTAMIENTO ELASTICO, PLASTICO y POR PANDEO

\- Comp. + Tensión
20 10 10 20 kips/pulg2
\-t--+-+--+--+---+--+-f-t-- Escala de esfuerzos

W4Xl3 I

Esfuerzos en el patín Esfuerzos en el alma

Figura 3-2 Esfuerzos residuales en los perfiles W (según Johnston Guide to Stability Design Criterio for Metal Structures, 3a. ed. (Nueva York: John Wiley & Sons, Ine.)

kips/pulg-. Para una sección W14 x 426, los esfuerzos correspondientes en las
puntas de los patines son de aproximadamente 20 kips/pulg-, pero en la unión
entre el patín y el alma, los esfuerzos de tensión son de sólo unos 4 ó 5 kips/pulg-.
Es interesante que, para una sección W8 x 31, todo el patín parece estar en
compresión, con valores máximos de aproximadamente 8 kips/pulg-, mientras
que el esfuerzo máximo en el alma es de aproximadamente 12 kips/pulg- ( en tensión).
El momento plástico de una sección laminada es apenas afectado por la presencia de esfuerzos residuales (evidenciado en pruebas de laboratorio a escala
natural), como lo indica la línea de puntos FD de la figura 3-1. Esto es cierto sólo
si las proporciones de la sección son tales que ésta puede volverse totalmente plástica antes del inicio del endurecimiento por deformación (o sea, si la relación
entre el peralte y el espesor del alma y la relación entre el ancho y el espesor del
patín no son demasiado grandes).
Ahora se pasará a investigar en detalle el concepto de momento plástico, en
los párrafos que vienen a continuación. Refiriéndose a la figura 3-1, el momento
en la fluencia inicial es

<!-- p. 143 -->

TEORIA ELASTICA y TEORIA PLASTICA DE DISEÑO 143

donde S; es el módulo de sección, l/c. El momento de inercia l, y la distancia e
entre el eje neutro y la fibra extrema se puede encontrar en cualquier texto de mecánica de materiales. El momento plástico, por inspección de los esfuerzos
mostrados en la sección transversal de la figura 3-1, para una sección totalmente
plástica, M = M¿ Yfijándose que el eje neutro en este lugar divide el área en dos
partes, con la distancia y desde el centroide del área al eje neutro, es

El valor de Ay se llama módulo plástico, Z, de modo que se puede reescribir el
momento como

La relación z/s se llama factor de forma, f.

Ejemplo 3-3 ¿Cuál será el módulo de sección Sx' el módulo plástico Z, yel
factor de forma del perfil rectangular mostrado en la figura E3-3?

y

b =200 mm
EE
oo
'1"
"...,
x x +

.1' Figura E3-3

SOLUCIONES El módulo elástico de la sección se calcula usando las ecua-
ciones de la mecánica de materiales:

l bh3 bh2
S = ~ = 12(h/2) = 6

S =Q.200~.4)2 = 5.333 X 10-3 m3

<!-- p. 144 -->

144 COMPORTAMIENTO ELASTICO, PLASTICO y POR PANDEO

El módulo plástico de la sección se obtiene como el momento estático
del área con respecto al eje neutro, el que divide al área en dos partes iguales.
Nótese que esto se hace necesario a fin de satisfacer los requerimientos estáti-
cos de Y:.Fh = Oen la sección.
A = bh 2y = h _ !!:. _ !!:. = !!:.
2 2 4 4 2
Z _ Ay _ bh h _ bh2
\-2-22-4

3 m3 = 2oo~.4)2 = 8.00 X 10-

El factor de forma se calcula como

Z 8
f = S = 5.333 = 1.50 III

El módulo plástico y el factor de forma de un perfil W se pueden calcular de
manera similar a la del perfil rectangular del ejemplo 3-3. En estos casos se hace
uso conveniente de las tablas para los perfiles T, como se ilustra en el siguiente
ejemplo.

Ejemplo 3-4 Calcúlese el módulo plástico de sección y el factor de forma de
un perfil laminado W610 x 241.1

SOLUCION El valor de AI2 se obtiene fácilmente de la tabla WT (WT305
x 120.5), ya que este perfil T se obtiene dividiendo un perfil W61O. El valor
de ji en la tabla permite localizar el centro de área de la T, pero es con respec-
to al patín.
De la tabla V-18 del SSDD, se obtiene
\~ = 15.39 X 10- 3 m2 y = 68.6 mm

De la tabla V-3, se tiene que el peralte de una sección W610 x 241.1 es 635
mm. El área total = 30.77 x lO-3 m2.

f;;-= d - 2fT = 635 - 2(68.6) = 497.8 mm = 0.498 m
X 10-3 X 0.498 = 7.664 X 10-3 m3 Z = A{ = 15.39

3 y la discrepan- El valor que se da en la tabla V-3 para Z; = 7.659x 10-
cia se debe a los dígitos extra que usa la computadora al calcular Z; de mane-
ra directa contrariamente al redondeo de la tabla V-18 y el uso de 0.4978 vs.
0.498 del cálculo anterior.

<!-- p. 145 -->

TEORIA ELASTICA y TEORIA PLASTICA DE DISEÑO 145

De la tabla V-3, el módulo de sección de un perfil W610 x 241.1 es
S; = 6.78 X 10- 3 m '

y el factor de forma, J, se puede calcular directamente como

f = 76~~: = 1.13 III

El factor de forma es una medida del aumento de la capacidad del momento
plástico M p sobre el valor del momento de fluencia M y , y se tiene

El valor típico deJpara los perfiles W es aproximadamente 1.12, con un intervalo
aproximado de 1.10 a 1.18 cuando se consideran todas las secciones laminadas.

\-
I--b--l

z = b/¡1/6 Z = t(b/¡l - b¡hT) Z = b/¡1/3
J =1.50 (b/¡2_ b¡lzr) J = 2.00
J= 1.5/¡---'---,-
(bf¡)- b¡/¡t)

Perfiles W

L = 4r 3/3 Z =1(r~ -- r1) Z = valores tornados de las tablas
J = 1.70 J= Z/S= 1.10 a 1.18
J=31.~ Promedio = 1.14
6 r¿ + r[ Vmor modal = 1.12

Figura 3-3 Módulo plástico de sección y factor para algunas secciones transversales escogidas.

<!-- p. 146 -->

146 COMPORTAMIENTO ELASTICO, PLASTICO y POR PANDEO

El módulo plástico y el factor de forma para diversas secciones transversales
se muestran en la figura 3-3.

3-3 FACTORES DE SEGURIDAD EN LOS DISEÑOS ELASTICOS
y PLASTICOS
El diseño del acero se puede basar en la resistencia a la fluencia (en este caso se denomina diseño de estados plásticos o de límite) o en el diseño elástico. En el diseño por estados límite el análisis se efectúa con base en suposiciones plásticas de
comportamiento -el miembro se sigue deformando desde Ey a Est sin ningún
aumento en la carga (véase figura 1-3b). El diseño elástico tiene en cuenta esta
característica única del acero pero limita los esfuerzos de trabajo a la región elástica de la curva de esfuerzo-deformación, donde el esfuerzo es proporcional a la
deformación, lo que queda definido por el hecho de que el módulo de elasticidad
sea una constante.
El método presente de diseño de las estructuras de acero se basa en el método
de diseño elástico. Los procedimientos comunes de diseño elástico, como se
hallan en las varias especificaciones de diseño, se basan en la relación lineal
esfuerzo-deformación hasta el límite elástico, pero se reconoce implícitamente el
comportamiento del acero más allá del límite elástico. El diseño elástico, como se
usa comunmente, coloca el esfuerzo límite del acero en el esfuerzo de fluencia Fr
Un esfuerzo de diseño que usará el esfuerzo límite de F; en el procedimiento de diseño elástico tendría un factor de seguridad F = 1. Un factor de seguridad de 1es
inaceptable, ya que no tiene en cuenta cambios futuros en el uso estructural o en
los ocupantes, ni los efectos por la fatiga o la corrosión. Un valor de F = 1 no
tendría en cuenta cambio alguno en la posición de las cargas. Por estas razones y
por una cierta incertidumbre en las propiedades de los materiales (defectos, dimensiones menores de las debidas en las secciones, y pequeñas diferencias metalúrgicas en los tipos de acero), incertidumbre en las cargas, y diferencias en los esfuerzos que resultan del uso de un modelo matemático ideal para la estructura real, se requiere un valor de F> 1.
Idealmente, todos los elementos de una estructura de acero deberían tener el
mismo factor de seguridad. No es éste el caso en la práctica. La respuesta por flexión de los miembros parece ser la que se puede predecir con mayor confianza, y
dichos miembros tendrán un valor mínimo de F. Las columnas son más sensibles
a la geometría de la estructura y de la sección y tienen una F con un límite inferior
como sucede con los miembros a flexión. Las conexiones, cuya falla tenga por resultado un colapso estructural, tienen justamente los mayores valores de F.
El factor básico de seguridad para los miembros de acero en la construcción
se obtiene de la siguiente manera. Se define como S la resistencia calculada del
miembro y la carga calculada de servicio como R. El factor de seguridad se puede
definir como

resistencia calculada del miembro S F= = carga calculada de servicio R

<!-- p. 147 -->

FACTORES DE SEGURIDAD EN LOS DISEÑOS ELASTICOS y PLASTICOS 147

Hay incertidumbre tanto en las cargas de servicio como en la resistencia real del
miembro, y se puede considerar la combinación que dé por resultado la más baja
relación SIR. Esta combinación se puede tomar como S - ~S, y para la carga de
servicio como R + M.
Para F = 1, esta nueva relación se cónvierte en
1 = S - áS = §.. 1 - áSjS
R + s« R 1 + áR j R
Ahora bien, si se toma MIS = MIR = 0.25 y fijándose en que SIR = F, se obtiene

O.75 1 = F
1.25

Resolviendo para F, se obtiene

1 F = 0.6 = 1.667 [o H

Este valor de F se toma como el valor básico de F para su uso en el método de
diseño elástico del acero en estructuras que no sean puentes de carreteras y ferrocarriles. Los puentes de carreteras y ferrocarriles por lo general están sometidos a
un ambiente más severo y a una mayor posibilidad de sobrecarga, de modo que se
toma el factor de incertidumbre M = M como 0.29, lo que da F = 110.55 =
1.82.
El valor de F = 110.6se modifica a 110.66cuando la geometría de la sección
transversal sea de un tipo tal que se pueda desarrollar totalmente una articulación
plástica en el punto de mayor esfuerzo. Los perfiles laminados, cuya geometría de
sección sea del tipo donde se pueda desarrollar en su totalidad una articulación
plástica, de modo que se pueda usar el valor básico de F = 110.66, se conocen como perfiles compactos. Los criterios geométricos para estos perfiles se considerarán en el capítulo 4.
Para el acero, A-36, y usando el factor de seguridad previamente definido,
los esfuerzos básicos permisibles se convierten en
Fa = 0.6Fy = 0.6(36) kíps/pulg-

(la especificación AISC permite en este caso el uso de 22 kips/pulg-)
Fa = 0.6(250) = 150MPa (en unidades SI)

Para las especificaciones AREA y AASHTO, se tiene
Fa = 0.55(36) = 19.8 kips/pulg-

<!-- p. 148 -->

148 COMPORTAMIENTO ELASTICO, PLASTICO y POR PANDEO

(estas especificaciones permiten usar 20 kips/pulg- en este solo caso)
Fa = 0.55 (250) = 137.5 MPa
Es preciso fijarse en que el redondeo opcional de 21.6 kips/pulg- a 22 kips/pulg-
(como se debe hacer en el caso de cálculos manuales) puede crear una pequeña
discrepancia en los cálculos si se usase una computadora digital, a menos que se
introduzca en el programa de la computadora un procedimiento de redondeo para este tipo de acero. El autor sugiere que se redondee a 22 kips/pulg-, ya que es
permisible y el acero A-36 es el de uso más común. No se recomienda (en este momento) redondear 137.5 MPa a 140 MPa, puesto que ya se ha redondeado algo
para obtener 250 MPa a partir de 36 kips/pulg-,

3-3.1 Factor de seguridad para el diseño plástico ordinario
El factor de seguridad usado (llamado factor de carga) para el diseño plástico, de
acuerdo con los procedimientos actuales del AISC, se obtienen usando el factor
promedio de forma, f, definido en la sección 3-2, e ilustrado en los cálculos para
una forma rectangular típica en el ejemplo 3-3. En el diseño elástico con secciones
compactas, el valor de F = 110.66 = 1.52. El valor del momento plástico es, M p
\= fMy, donde el factor de forma = 1.12 como valor típico para todos los perfiles
laminados W. Usando ahora el mismo valor de esfuerzo de trabajo,fb para cualquiera de los dos métodos de diseño, se tiene

Cancelando el módulo de sección, S, se obtiene

FI = 1.52f = 1.52(1.12) = 1.70
(como se usa en la Parte 2 de las especificaciones del AISC)

Este valor de F se usa en el diseño plástico (o de estados límites), como un factor
de carga por el que se multiplican las cargas de trabajo o de diseño para obtener
las cargas "últimas". Los esfuerzos que se obtienen de estas cargas últimas y con
base en las propiedades de la sección se comparan con el esfuerzo de fluencia, Fy ,
y se efectúan los ajustes hasta que el valor calculado /; :5 Fy •

3-4 DEFLEXIONES DE DISEÑO PLASTICO VS. DEFLEXIONES
DE DISEÑO ELASTICO
Si se desarrolla una articulación plástica en un punto a lo largo de una viga o de
una columna, resultará una deflexión muy grande. Sin embargo, esta deflexión
carecería de sentido pues produciría un colapso de la estructura. Ninguna estruc-

<!-- p. 149 -->

LONGITUD DE LA ARTICULACION PLASTICA 149

tura se diseña para que esto ocurra, de modo que la deflexión que ocurre bajo la
carga real de trabajo es la que interesa. La carga de trabajo para el diseño plástico
se obtiene aplicando el factor de carga de 1.7 a las cargas últimas, en wu' Pu, Mu'
etc. Este factor asegura que.las deflexiones bajos las condiciones reales de carga
de trabajo tendrán valores elásticos.
Como las deflexiones plásticas producen colapso de la estructura, son las
deflexiones elásticas las que tendrán alguna significación, y es por esta razón que
siempre se calculan las deflexiones usando procedimientos analíticos elásticos pa
ra ambos métodos generales de diseño.

3-5 LONGITUD DE LA ARTICULACION PLASTICA

La longitud de la articulación plástica se puede derivar como sigue para una viga
uniformementecargada y con extremos fijos (refiérase a la figura 3-4). Siendo horizontalla pendiente de la curva de momentos en el centro del claro, la ordenada de
la curva parabólica de momentos es

L Yo = M¿ - ( - Mp) = 2 M¿ para x = "2

La ecuación de una parábola con el origen de las equis como se muestra es
Y = kx2

Insertando Yo Yx = L/2, se obtiene

(3-1)
Como y =M¿Ahora es necesario encontrar un valor de x tal que M; =M; = SxFr
\- My , se tiene

\V.
I I
L ~ x
y
\+Mp
My yo=T2Mp
l:p -Mp
L/2

Figura 3-4 Longitud de la articulación plástica para una viga uniformemente cargada y con
extremos fijos.

<!-- p. 150 -->

150 COMPORTAMIENTO ELASTICO, PLASTICO y POR PANDEO

Sustituyendo y y M p en la ecuación (3-1), se obtiene

Cancelando S, y Fy y reordenando, se obtiene para la longitud de la articulación
el valor x que la define (y el que es la longitud de la articulación en la mitad del
claro),

(3-2) x=~..W2.83 VI -7
Cuandof = 1.12, la longitud 2x de la articulación plástica en el centro de la vigaes

L
Larticulación = 2 8.64 (casi el 20 porciento del claro)

La longitud de la articulación para otras cargas sobre la viga, tales como las
vigas en voladizo, vigas con cargas concentradas, y para combinaciones de cargas, se puede obtener de manera similar a la que se acaba de presentar, y teniendo
en cuenta el gradiente de momento (pendiente de la curva de momentos).

3-6 DISEÑO ELASTICO y DISEÑO PLASTICO

El uso del diseño plástico en vigascontinuas y estructuras pequeñas de uno o dos
pisos, tiene sus ventajas:

\1. La rapidez en la obtención de los momentos de diseño.
\2. Se economiza algo en el acero (a menudo es posible usar secciones más
ligeras).
\3. Da alguna idea sobre el modo de colapso y la resistencia de la estructura.

No obstante, si se compensan estas ventajas se tienen algunas desventajas:

\1. La amplia disponibilidad de programas de computadora, que pueden resolver
rápidamente tanto estructuras simples como complicadas, usando métodos
elásticos.
\2. La mayoría de los diseñadores están más familiarizados con los métodos elás-
ticos de diseño.
\3. La dificultad de obtener el modo de colapso si la estructura es razonablemente
complicada.

<!-- p. 151 -->

DISEÑO ELASTICO y DISEÑO PLASTICO 151

PII PII

a b ~ 111111111"(1 1111~ ~r----!---....,~mfm/l!'""---l-----,.,

Articulación ~ Articulación
\~\~ ~ ~Ol~
1----k.JI+02 ~+02 ~~+02

(iJ) (b) (e)
Figura 3·5 Formación de articulación plástica para diversas vigas cargadas como se muestra. (a)
Viga simplemente apoyada, una articulación para la falla. (b) Viga en voladizo apuntalada, dos
articulaciones para la falla. (e) Viga con extremos fijos, tres articulaciones para la falla.

\4. No hay mucha economía en el diseño de las columnas (y a veces en otros
miembros, dependiendo de los métodos de fabricación).
\5. La dificultad en el diseño por fatiga.
\6. Los requerimientos de soporte lateral son más exigentes que los del diseño·
elástico.

En el diseño plástico, es necesario determinar la posición de las articulaciones plásticas que se forman en aquellos lugares donde se desarrolla el M p • Para
que se desarrolle un mecanismo de colapso (donde la estructura es incipientemente inestable), es necesario que se forme un número suficiente de articulaciones.
Así, una viga simple requiere una articulación, una viga en voladizo apuntalada
dos articulaciones, una viga fija en los dos extremos tres articulaciones. y así sucesivamente. En la figura 3-5 se ilustran las vigas y los mecanismos de colapso para las tres vigas consideradas. El alumno debe fijarse que una viga continua es similar a una viga con extremos fijos, y que el claro exterior de una viga continua es
similar a una viga en voladizo apuntalada.
Hay dos métodos de análisis que se usan comúnmente para determinar el valor de M¿ cuando se ha determinado el mecanismo de colapso. Estos dos métodos
son, el método de equilibrio (conocido también como método estático) y el método del trabajo virtual. Sólo se considerará en adelante el método de equilibrio.
Este método se ilustrará con los ejemplos siguientes. El lector debe observar el
hecho de que las vigas consideradas en los siguientes ejemplos producirán articulaciones (y M p) en lugares claramente definidos. Un marco rígido que consiste en
varios claros (y pisos) debe desarrollar las suficientes articulaciones para producir
un mecanismo de colapso y poder efectuar un análisis plástico. La posición de estas articulaciones se debe determinar por pruebas (o sea se supone la posición de
las articulaciones y se calcula M p ) . El juego de articulaciones que produzca el
mínimo Mp se considerará como crítico y se usará en el diseño. Este proceso iterativo no es necesario para las vigas de los ejemplos que vienen a continuación.
Ejemplo 3-5 Dedúzcase una expresión paraM p ' para la viga con extremos fi-
jos que se muestra en la figura, y selecciónese un perfil W con un valor ade-
cuado de Z para Pw = 120 kN.

<!-- p. 152 -->

152 COMPORTAMIENTO ELASTICO, PLASTICO y POR PANDEO

r; = 120 kN

3m 3m ~~!~~ L-6m

Figura EJ-5

SOLUCION Son necesarias tres articulaciones para producir un mecanismo
de colapso. Nótese que se trata de una viga indeterminada de segundo grado
(no hay carga horizontal, por lo que Fh = Ose satisface automáticamente.
Por simetría, las tres articulaciones necesarias para formar el mecanismo de-
ben ser como se muestran en la figura E3-S. El efecto de los momentos en los
extremos fijos es reducir el diagrama de momentos de la viga simple, como se
muestra por las líneas punteadas. Para que se formen las articulaciones es
necesario que el valor del momento sea igual a Mp ' y es evidente que Mp se
formará primero en los extremos fijos, ya que el momento elástico es mayor
en dichos puntos. Los incrementos en los momentos empujan los momentos
elásticos hacia el intervalo plástico. También es evidente que el único otro
punto donde se puede generar el momento M p será debajo de la carga con-
centrada, puesto que el momento en este punto será el próximo lugar donde
el momento elástico es lo suficientemente grande para que el aumento de Pw
hasta P¿ forzará al momento dentro del rango plástico. Cuando se forma es-
ta articulación, la estructura se desploma (en teoría) y no es posible ningún
aumento adicional de la carga.

Con esta consideración, se tiene (haciendo nuevamente referencia a la
figura E3-S)

donde

Para acero A-36, F'y = 250 MPa.
Pu = P; x factor de carga = 120(1.7) = 204 kN
M = M = PuL = 204(6) = 153 kN . m
u p 8 8

<!-- p. 153 -->

DISEÑO ELASTICO y DISEÑO PLASTICO 153

El módulo plástico de sección requerido es

153 Z = 250 = 0.612 x 10-3 m3

De la tabla VI-2 del SSDD, se selecciona
W360 x 38.7 z, = 0.6566 X 10-3 m3
La viga tiene que soportar su propio peso, así que, por peso propio de la
viga, el momento será M = wL2/8. Para el análisis plástico se usa el mismo
concepto que para la carga concentrada, lo que da

Para el perfil W360 x 38.7, el peso/m = 0.38 kN/m (tabla V-3).

Estableciendo una proporción,

sz, = 153(0.612)1.454 = 0.0058

El valor total de Z; requerido es
Zx = 0.612 + 0.0058 = 0.6178 \< 0.6566 x 10-3 m3 suministrado correcto.

Se usará una viga W360 x 38.7.

Es aún necesario comprobar los requerimientos de soporte lateral. Para
un diseño elástico en que se use Fa = 0.6 Fy (el esfuerzo permisible de uso
corriente), la viga sería

M = PL = 120(6) = 9OkN. m
8 8

El módulo de sección requerido, S, es

90 _ 3 S = 0.6(250) = 0.60 x 10 3 m

<!-- p. 154 -->

154 COMPORTAMIENTO ELASTICO, PLASTICO y POR PANDEO

Usese una sección W410 x 38.7.
f:1S = 0.38(6i = 0.0076
x 12(150)
Sx(req) = 0.60 + 0.0076 = 0.6076 \< 0.629 x 10-3 suministrado Correcto

Por coincidencia se ha encontrado una sección que tiene exactamente la
misma masa por metro: en la mayoría de los casos, las seccionesobtenidas por
métodos de diseño plástico son algo más ligeras que las obtenidas por diseño
elástico, por lo menos cuando la viga es indeterminada. / / /

Ejemplo 3-6 Dada la viga en voladizo apuntalada que se muestra en la figura
E3-6, se requiere obtener una expresión general para M¿ y luego diseñar la vi-
ga si Ww = 5 kN/m y Fy = 250 MPa. Dedúzcase también una expresión ge-
neral para la posición del Mp en el claro.

\~ ",.'5 kN/m
A 1IIIIIIIIIIInllllll ~ 1111111111111-

M = máximo en estelugar Re

A B

M'qllllll'~'~

v= O Re
Figura E3-6

SOLUCION El mecanismo de colapso consistirá en dos articulaciones COlO-
cadas como se indican. Por estática, el momento Mp en B es un máximo. De
la mecánica de materiales, V = O. cuando M = máximo. Esto da

(a)
Además, por estática, M B = Opara el segmento Be, lo que da

W x2 M +_u--Rx=O (b) p 2 e

<!-- p. 155 -->

DISEÑO ELASTICO y DISEÑO PLASTICO 155
Tomando momentos del segmento AC de la viga con respecto a A (EMA =
O), se obtiene

W L2 M +RL-_u-=O p e 2 (e)

Sustituyendo el valor de Re de la ecuación (a) en la ecuación (e), y luego susti-
tuyendo el valor de M p de la ecuación (e) en la ecuación (b) se obtiene

x2 + 2xL - L2 = 0

Al resolver esta ecuación, completando cuadrados, se obtiene
x = 1.414L - L = 0.414L (3-3)

Se puede ahora obtener una expresión general para M p a partir de las
ecuaciones (a) y (b):

(3-4)

Usando la ecuación (3-4) con la longitud y carga dadas para la viga, el valor
deMp es

Mp = 0.08579(45 X 1.7)(6f = 236.26 kN . m

3 z, = 2;~~6 = 0.9451 X 10-3 m

Pruébese una sección W460 X 52.1. Z; = 1.0861 X 10-3 m", El aumento
de Z; por el peso de la viga es

°4~1 (0.9451) = 0.0107 AZx =
Zx(req) = 0.9451 + 0.0107 = 0.9558 \< 1.0861 X 10-3 1-'3

Se usará una sección W460 X 52.1 (nótese que no se comprobó la sección
para los requerimientos de soporte lateral).

Ejemplo 3-7 Para la viga continua de dos claros que se muestra en la figura
E3-7, selecciónese una sección W económica usando el diseño plástico yacero A-36.

SOLUCION Son necesarias dos articulaciones para el colapso de cuando
menos un claro. Los valores de M p para alcanzar este resultado son:
Claro de la izquierda:

<!-- p. 156 -->

156 COMPORTAMIENTO ELASTICO, PLAST¡CO y POR PANDEO

/77977

Á 450 =PL'
/" 4
/ / ""- / / "-,
/ / " "
\--

Figura EJ-7

Mp _ 2(90)L
Mp + 3 - 9
Mp = 15L

Claro de la derecha:

M' 120L' M' + --!!.. = -- p 2 4

M; = 20L'

Se usa el valor máximo de Mp obtenido de cualesquiera de los dos claros para
el diseño (ya que la viga salva ambos claros usando una sección constante).

Mp = 15(1.7)(18) = 459 pie- kips
M; = 20(1.7)(15) = 510 pie . kips úsese este valor
Z = 510(12) = 170 pulg!
36
Selecciónese de la tabla 11-2 una sección W24 x 68, con Z; = 176.4 pulg",
Compruébese aproximadamente el efecto del peso de la viga (si se encontrase
un caso extremo, se podría justificar el trabajo adicional de realizar un análi-
sis exacto):

L 2 ss«:p _ Wu ~AM' p +-----2 8
152 =.217'pie > ki ps ~AM'p = "32 0.068 x 81.7 x

<!-- p. 157 -->

DISEÑO POR FACTOR DE RESISTENCIA DE CARGA 157

y el valor requerido de AZx es

!!lZ = 2.17(12) = 0.72 pulg?
x 36

Zxtotal(req) = 170.0 + 0.72 = 170.72 \< 176.4 suministrado Correcto
Se usará una sección W24 x 68, con Z; = 176.4 pulg! III

3-7 DISEÑO POR FACTOR DE RESISTENCIA DE CARGA

El diseño por factor de resistencia de carga (DFRC) constituye una proposición
reciente que todavía está en proceso de desarrollo como un enfoque alternativo
del método de diseño elástico en uso actual. Se espera que el DFRC sea completamente aceptado por el AISC dentro de la vida útil de este texto. Este pronóstico se
basa en el hecho de que este procedimiento (al menos en los detalles esenciales,
conocido como diseño de estados límites) ya ha sido aceptado en el Canadá y
otros países fuera de los Estados Unidos. Las especificaciones para puentes de la
AASHTO que están actualmente en vigor (l2a. edición) proporcionan un método
alternativo de diseño en acero, llamado diseño por factor de carga, para vigas
simples y continuas, y trabes de moderada longitud, que usan secciones compactas. Todos los diseños DFRC son muy semejantes entre sí y al procedimiento de

Tabla 3-1 Recomendaciones actuales para los ti> factores
Condición de esfuerzo Sugerido" Canada AASHTO

Miembros a tensión
Fluencia (Fy ) 0.88 0.90 1.0
Fractura (Fu) 0.74 0.90 1.0
Flexión
Secciones laminadas y trabes armadas 0.86 0.90 1.0
Columnas? 0.90 1.0
1'/ s 0.16 0.86
0.16 \<1'/ s 1.0 0.90-0.251'/
1'/ > 1.0 0.65
Cortante
Almas de vigas y trabes 0.86 0.90 1.0
Conexiones
Tomillos? 0.70-1.00 0.90
Soldaduras 0.80 0.90

a Véase Journa/ 01 Structural Division, ASeE ST9, septiembre, 1978 (contiene ocho articulos sobre
el DFRC).
b 1'/ = (KLhrr) .JFy/E (K = factor de longitud, dado en el capitulo 6).
C Véase sección 8-10.

<!-- p. 158 -->

158 COMPORTAMIENTO ELASTICO, PLASTICO y POR PANDEO

diseño por resistencia que se usa para el diseño de concreto reforzado. En el
DFRC, como en el concreto reforzado, se usan factores cj> para reflejar las incertidumbres del material (en este caso, la resistencia especificada del acero, Fy) . Estos
factores actualmente están en estudio junto con las sugerencias indicadas en la
tabla 3-1.
En el DFRC se usa una ecuación de la forma general

donde 1/; = factor de análisis (también llamado factor de importancia; valor ac-
tualmente sugerido, 1.1
Fd = Factor de incertidumbre para la carga muerta con un valor su-
gerido de 1.1
FL = Factor de incertidumbre para la carga viva con un valor sugerido
de 1.4 según el uso a que se destine el edificio; se usan también otros
valores (por ejemplo, 1.5 para máxima nieve, 1.6 para máximo vien-
to, etc).

Las ecuaciones para las diversas cargas, incluyendo el viento y la nieve podrian
ser como sigue:

cj>R ~ 1.1(l.1D + l.4L + 1.6WmIDJ
cj>R ~ 1.1(l.1D + 1.58 mIDJ
cj>R ~ 1.1(l.1D + l.4L)
El valor de la resistencia será por lo general, R = Fy (el esfuerzo de fluencia del
acero).
El objetivo general cuando se usa el DFRC es evaluar por separado cada
renglón que influya sobre el diseño de una estructura más bien que "amontonar"
algunos efectos en conjunto, como, por ejemplo, sencillamente añadir las cargas
vivas y muertas para obtener la carga compuesta. Se usan factores mayores con
aquellos aspectos que presentan mayor incertidumbre, como son las cargas de
viento y de nieve (factores de carga viva de 1.5 y 1.6 contra el factor de carga
muerta de 1.4) y factores menores para las propiedades de los materiales (factor
cj» y las cargas muertas, estas últimas se pueden identificar razonablemente bien,
cuando menos después de que se ha diseñado la estructura. Los factores cj>, Fs,
Fu Y1/; se basan en amplios estudios de probabilidad (que se siguen realizando) y
que se pueden redondear positiva o negativamente con base en consideraciones
conservadoras y/o prácticas.

3·8 PANDEO LOCAL DE PLACAS
Es fácil darse cuenta de que la mayoría de los miembros estructurales son conjuntos de placas planas. Las seccionesW consisten de tres placas planas, dos placas

<!-- p. 159 -->

PANDEO LOCAL DE PLACAS 159

Bordes articulados (simplemente Bordes fijos (empotrados)
apoyados)
(a) 1
b1

(b)

Figura 3-6 Pandeo de placas delgadas bajo esfuerzos de compresión en los bordes. (o) Pandeo de
una placa rectangular. (b) Pandeo de una placa larga, rectangular.

planas forman un ángulo, y así sucesivamente. Cuando se somete una placa a esfuerzos de compresión, flexión, o cortantes, o a una combinación de los mismos
esfuerzos, puede que la placa se pandee localmente antes de que falle todo el
miembro.
Considérese una placa rectangular con dimensiones a x b (véase figura 3-6)
libre de esfuezos residuales, perfectamente plana, homogénea, e isotrópica que
está sometida a una carga uniforme de compresión a lo largo de bordes opuestos.
Bajo este esfuerzo, la placa se comprimirá uniformemente hasta llegar al esfuerzo
de pandeo. Cuando se alcanza dicho esfuerzo, la placa se deflexionará en una o
una serie de ondas, dependiendo de las condiciones en los bordes (condiciones de

<!-- p. 160 -->

160 COMPORTAMIENTO ELASTICO, PLASTICO y POR PANDEO

frontera) y de la relación largo a ancho (a/b) con una redistribución resultante
de los esfuerzos de compresión hasta que, con la adición de carga, toda la placa se
pandee.
Según la teoría de las placas, como la proponen varias autoridades, t el esfuerzo elástico crítico de pandeo, Fcr es

(3-5)

También es posible el pandeo inelástico, definido aquí como el esfuerzo
crítico, Fcr> por encima del límite proporcional; este pandeo se puede describir
con el uso de un término Aen la ecuación (3-5):

(3-6)

Donde E = Módulo de elasticidad, 29 000 kips/pulg- ó 200 000 MPa.
fJ- = Coeficiente de Poisson (se puede usar 0.33 ó 0.3 para el acero).
a, b = Largo y ancho de la placa, respectivamente; nótese que Fcr se apli-
ca a través del ancho b.
t = Espesor de la placa.
k¿ = Coeficiente no dimensional que depende de los apoyos en los bor-
des, de la relación a/b y viene dada en la forma general

Cuando a/b = m y n = 1 y los bordes paralelos al esfuerzo de
compresión están simplemente apoyados, k = 4.00. Los términos
m y n provienen del uso de una solución por serie para deducir la
ecuación de la placa. Otros valores de k no se obtienen tan directa-
mente, pero han sido calculados y tabulados para diversas condi-
ciones de frontera, y aparecen en la tabla 3-2.
A = factor que se usa para obtener un módulo tangente en la forma E(
\= AE. Cuando A = 1, se tiene E( = E. En general, Aes

(3-7)

t Por ejemplo: Timoshenko y Goodíer, Theory 01 Etasticity, o Bleich, Buckling Strengtb 01 Metal
Structures (Nueva York: McGraw-Hill Book Company), o Johnston, Guide to Stability Design Criterialor Metal Structures, 3a ed. (Nueva York: John Wiley & Sons, Inc.).

<!-- p. 161 -->

PANDEO LOCAL DE PLACAS 161

Tabla 3-2 Valores de los coeficientes de pandeo para varias condiciones de los
bordes de las placas

1-

k~ ks
\~ 0.38 Para ks• los cuatro bordes de la - placa tienen el mismo tipo de ---- soporte
1.15 a v alb 3 =------ ...--- - 4.00 + 5.34/a2 a\<l - -~ 3.615 y 5.34 + 4.00/a2 a>l
\------>q; 4.90 g--

\~ '""____-:::a ~ 6.30 5.60 + 8.98/a2 a\<l
8.98 + 5.60/a2 a>l

donde Fpl = Esfuerzo del acero en el límite proporcional (se puede
usar un valor de F p/ = 0.70 a 0.75).
Fy = Esfuerzo de fluencia del acero.
Fer Esfuerzo crítico de pandeo, de la ecuación (3-6).

Si se trata de resolver la ecuación (3-6) para determinar el esfuerzo crítico de
pandeo, se presentarán diversos problemas, en particular si A \< l. Se debe determinar primeramente k.: Aunque se ha proporcionado la expresión general para
k, es necesario ajustar dicha expresión para las varias condiciones de frontera que
son posibles. Diversos autores han realizado estos cálculos, pero, como una conveniencia el autor ha combinado además el efecto de 1r2/ [12(l - p,2)] para que den
los valores de k~ que se muestran en la tabla 3-2 [ésto es, 4.00(0.9038) = 3.615].
Si el término Aes menor que 1 es necesario repetir el cálculo hasta llegar a Fer• Esto se ilustra como sigue:
Se reescribe la ecuación (3-6) en términos de k' e' para obtener

<!-- p. 162 -->

162 COMPORTAMIENTO ELASTICO. PLASTICO y POR PANDEO

(3-8)

Se divide la ecuación entre
F cr = Ek,(!-)2 (3-8a) A e b

Por el momento no se usará esta ecuación. Utilizando entonces la ecuación (3-7)
para Acon Fpl = 0.75Fy , se puede, reordenando un poco, obtener
s; 0.1875F;.2
T= F;.-Fcr (3-9)

Como Fcr se encuentra en ambos lados de la ecuación (3-9), hay que hallar el valor
de Fc/A por ensayos sucesivos. Una vez que se obtenga este valor, se puede usar
en la ecuación (3-8a) para determinar la razón bit, que por lo general es lo que interesa. De la ecuación (3-80), se encuentra que la razón bit es

Para k¿ = 3.615, A = 1, YFcr = 0.75Fy , el valor límite de la razón bit, para el
acero A-36 es

b (29 000)(3.615) = 62.3
t 0.75 x 36

Al usar la ecuación (3-9), a menudo conviene construir una tabla de Avs. Pero con
valores desde Fcr = 0.75Fy hasta Fy- Para el acero A-36, los valores típicos son los
siguientes:

Fer• kips/pulg2 A El' kíps/pulg/'

27.0 1.00 29000
28.0 0.922 26 738
30.0 0.741 21 489
33.0 0.407 11 803
36 0.0 O

En la figura 3-7 se muestran las características de compresión (k; Yel ancho b
a compresión) de tres perfiles laminados. Los valores mostrados de k; concuerdan razonablemente con las pruebas. Es necesario hacer ajustes en los valores de
k., porque son muy pocas las placas que están libres de imperfecciones y esfuerzos residuales.

<!-- p. 163 -->

PANDEO LOCAL DE PLACAS 163

b¡
\-»¡ o dw·/fw·
k~ = 0.38 ~br--i k~ = 1.15 para el alma de la viga T
dw/fw bJ/fcp El patín igual que pata el perfil W
bJ/2fJ b¡/fcp
bl/fcp
k~ = 0.63 para los patines
k~ = 4.5 para el alma

Figura 3-7 Características de compresión de los perfiles laminados que se muestran en la figura.
Nótese que por lo' general es necesario investigar la relación bit crítica, que puede ser como se
muestra para un perfil W con una cubreplaca, soldada o atornillada.

Si se usa el valor de k' e = 0.63 que se muestra en la figura 3-7, para el patín
de una sección W y un FS = 2.00 YFer = Fy , se obtiene

11.3 sea II

o, en general

b- = 0.5 (29 000)(0.63) =--67.5 sea --65 t F;, y¡;; y¡;;

La especificación en vigencia del AISC permite una relación bit de 651-/Py (usa
b¡l2t¡). Obsérvese también que si se considera el alma, k' = 4.9, se obtiene

d-=0.5 (29 000)(4.9) =--188.5 sea --190 tw F;, y¡;; y¡;

que se encuentra también en la especificación del AISC.
En la tabla 3-2 también se muestran valores de k, = Ksv para el esfuerzo
crítico que produce el pandeo por cortante. El esfuerzo crítico de pandeo por cortante se puede deducir de manera similar al de compresión, con la sustitución de
un coeficiente apropiado de pandeo, ks' para obtener, de la ecuación (3-6),
k '(T2AE; F = s
en 12(1 _ p.2)(b/t)2

<!-- p. 164 -->

164 COMPORTAMIENTO ELASTICO, PLASTICO y POR PANDEO

Es común suponer que los cuatro bordes de la placa están simplemente apoyados
en él caso del cortante, y que el esfuerzo cortante, Fcfs = FyI$Este valor se ha
de combinar con el factor de seguridad de 1/0.6, de modo que el esfuerzo cortante de diseño, resulta ser

SF xv'3

La mayoría de los problemas prácticos de diseño consideran, o bien pandeo
a compresión, o bien pandeo por cortante. Cuando ambos esfuerzos actúan simultáneamente, el alumno debe consultar otros libros, como los de Bleich, John-
ston, y Timoshenko y Goodier, citados en una nota anterior.

3-9 RESISTENCIA POSTERIOR AL PANDEO DE LAS PLACAS

Los resultados experimentales demuestran que una placa pandeada no da por resultado una falla inmediata. Hay, más bien, una considerable reserva de resistencia que se atribuye al efecto del material adyacente de la placa, el que restringe el
pandeo y permite la transferencia de cualquier aumento en la carga después
del pandeo a las zonas sin pandeo. Esta situación se idealiza en la figura 3-8, que
ilustra la zona central pandeada en el ancho cargado b. A cada lado se encuentran
fajas que confinan el pandeo y que están cargadas con una carga efectiva menor,
le. El concepto de ancho efectivo se aplica como la suma de los dos anchos de faja a cada lado de la zona de pandeo. Cuando el esfuerzo efectivo sobre estas dos
fajas de borde (esfuerzo sobre el ancho be) alcanza un valor tal que la deformación es constante sin aumento adicional de la carga, se ha llegado a la capacidad
total de carga de la placa. La diferencia entre la carga inicial de pandeo y este
nuevo valor constituye la resistencia de la placa después del pandeo.

Figura 3·8 Ancho efectivo para la capacidad de la placa después del pandeo.

<!-- p. 165 -->

PROBLEMAS 165

El esfuerzo fc se puede evaluar usando la ecuación (3-8), para obtener

donde se han identificado previamente todos los términos, excepto be' que aparece
en la figura 3-8. Para una placa simplemente apoyada, muy larga y delgada, parece ser que el valor teórico de k' es 3.615 para usar con esta ecuación. A menudo el
uso de la resistencia de las placas después del pandeo no se evalúa directamente.
Por lo general, se usa de manera más indirecta; por ejemplo, el AISC permite
usarla indirectamente, por medio del apéndice C3 que establece que: "Cuando la
relación de ancho a espesor de un miembro atiesado uniformemente comprimido
excede el límite aplicable dado por la sección 1-9.2., se usará un ancho efectivo reducido, bc' al calcular el. .."

PROBLEMAS

3-1 ¿Cuál es el bfl21f permisible para cualquier sección W de acero con Fy = 50 kips/pulgj?
Respuesta: 9.2
3-2 ¿Cuál es el b¡l2tf permisible para cualquier sección W con Fy = 250 MPa?
3-3 ¿Cuál es el momento plástico (kN. m) de una sección WE920 x 200.9, con un Fy = 345 MPa?
Respuesta: 2865.2 kN • m.
3-4 Verífiquese Z¿ en la tabla V-3 para un perfil laminado W610 x 241.1.
3·5 ¿Cuál será el valor de Z, para el perfil geométrico de la figura P3·5, si se una como viga?

1-- 450 mm--l
FOT650
. 120 l Figura P3-S{E

3-6 Selecciónese la sección W más ligera que satisfaga la flexión para el claro y carga mostrados en la
figura P3-6. Usese Fy = 36 kips/pulg/ y diseño plástico.

\~ 4 k,,,¡n I! I I! I I I I I! I!!!!!! I I I Irrrrr~
20'
Figura P3·6

3·7 Selecciónese la sección W más ligera que satisfaga la flexión para el claro y carga mostrados en la
figura P3-7. Usese Fv = 250 MPa y diseño plástico.
Respuesta: W610 x 101.2

<!-- p. 166 -->

166 COMPORTAMIENTO ELASnCO, PLASnCO, y POR PANDEO

340 kN

50 kN/m 1,J;;II!! 11111111!J%m ------r--

Figura P3-7
3-S Selecciónese la sección W más ligera para la flexión de la viga que se muestra en la figura P3-S.
Usese Fy = 345 MPa y diseño plástico.

420 kN

\~ 60 kN/m

1---4 m
¡....-----8m Figura P3-S

3-9 ¿Cuál es el factor de incertidumbre tanto para S como R para producir Fa = 0.5 Fy?¿Cuáles son
los dos valores alternativos, razonables y distintos para producir el mismo efecto?
Respuesta: S = R = l/3.

<!-- p. 167 -->



<!-- p. 168 -->

(o)

(b)
Figura IV·1 Vigas de acero. (a) Un par de trabes masivas usadas para una grúa y trabe carril. Se
puede ver el equipo de la grúa entre las dos trabes. Nótese que las columnas de la trabe carril están escalonadas, con una menor sección de columna por encima de la base de la trabe carril. (b) Vigas en
proceso de montaje para un complejo de oficinas de dimensiones medias. Nótense los tomillos de montaje que se usan temporalmente para soportar las piezas. La viga que aparece en primer término es una
viga de borde, formada por un canal y un angular.

<!-- p. 169 -->

CAPITULO
CUATRO

DISEÑO DE VIGAS A FLEXION

4-1 CONSIDERACIONES GENERALES

Las vigas son miembros estructurales que soportan cargas transversales que producen momentos flectores y fuerzas cortantes, siendo la resistencia a la flexión el
parámetro de diseño de particular significación. Las vigas pueden ser horizontales(las más comunes), inclinadas (como las vigas de techo), o verticales. Las vigas
inclinadas y las verticales pueden soportar cargas axiales y transversales. Los
miembros verticales, llamados vigas-columnas, se estudiarán en el capitulo 7. Es
preciso considerarlas por separado, ya que en el comportamiento a flexión y por
pandeo influye en grado considerable una combinación de esfuerzos de flexión y
axiales de compresión.
Las vigas se denominan vigassimplescuando las conexiones extremas no soportan, o se supone que no soportan ningún momento originado por cualquier
continuidad desarrollada en la conexión. Una viga es continua cuando se extiende
sin interrupción a través de uno o más apoyos; es viga fija si los extremos se conectan rígidamente a otros miembros, de tal modo que se puede transmitir el momento a través de la conexión. En un marco de acero, el término "extremo fijo"
resulta algo inapropiado, ya que los extremos de las conexiones rígidas no están
filos en el sentido en que se analiza una viga de extremos fijos en los textos de mecánica de materiales. Por lo general, hay alguna rotación en las juntas, de tal manera que el momentoextremo real no se obtiene directamente de las ecuaciones de

169

<!-- p. 170 -->

170 DISEÑO DE VIGAS A FLEXION

momentos para extremos fijos, sino que se calcula considerando la rigidez general
del marco. Se verá más adelante que en circunstancias especiales se puede diseñar
la conexión en el extremo para una parte de la capacidad de momento del
miembro. Se centrará la mayor atención sobre los casos en los que la viga:

\1. No tiene momentos extremos (viga simple), o bien
\2. Tiene momentos en los extremos de cada claro (continua o de extremos fijos).

'Las cargas sobre la viga consistirán de cargas muertas y vivas. Los efectos de
dichas cargas, en términos de si se manifiestan éstas como una serie de cargas
concentradas o como cargas uniformes, dependerá del plan general de la estructura y la posición de la viga. El peso propio de la viga es parte de la carga muerta de
la misma. Cuando se usan miembros largos y pesados, el peso propio puede constituir una parte significativa de la carga total de la viga. Cuando el claro sea pequeñ.oy/o las cargas externas sean también pequeñas, el peso de la viga puede ser
bastante pequeñ.o, yen este caso, la relación resistencia/peso del acero es una particular ventaja. De cualquier modo, se debe comprobar siempre la sección para
ver si tiene la resistencia adecuada para las cargas aplicadas, incluyendo el peso de
la viga.
Las vigas se clasifican en:
\1. Trabes: miembros principales de carga en los cuales seconectan las vigas de pi-
so, como se muestra en la figura 4-1. En el capítulo lOse consideran los
miembros armados que se usan como trabes en los puentes.
\2. J[iguetas: miembros que se usan para soportar el techo y los pisos de los edifi-
cios.
\3. Dinteles: vigas que se usan para soportar las cargas del muro sobre las abertu-
ras de los mismos.
\4. Yigas de borde o fachada: vigas exteriores a nivel de piso, usadas en la cons-
trucción de edificios para soportar parte de la carga de piso y del muro exte-
rior. Cuando el revestimiento del muro sea de ladrillos o losetas, la viga de
fachada puede soportar la carga del revestimiento de un piso para reducir los
esfuerzos de compresión en la mamposteria.
\5. Largueros: miembros usados en los puentes, paralelos al tráfico para soportar
la losa dé" cubierta, y que se conecta por lo general a los miembros transversa-
les (vigas de piso).
\6. Vigas de piso: miembros secundarios en un sistema de piso (figura 4-1), y
miembros principales en la construcción de puentes a las que se conectan los
largueros (véanse las figuras 4-13 y 4-14).
En la mayoria de los casos, en particular para maximizar la economía, se cargan los perfiles de acero laminado, de tal modo que la flexión sea con respecto al
eje fuerte (eje X-X, como se muestra en las tablas de propiedades de las secciones
del SSDD). A veces, la flexión tiene lugar con respecto al eje débil (Y- Y), yen algunos casos hay flexión simultánea con respecto a ambos ejes, X e Y.En casi todas las aplicaciones que implican un solo eje de flexión, se considera aplicada la

<!-- p. 171 -->

CONSIDERACIONES GENERALES 171

carga a través del centro de cortante de los perfiles W o S. El centro de cortante de
dichos perfiles está en el centro de área, y esta posición de la carga produce flexión simple con respecto a alguno de los dos ejes.
Cuando la carga no pasa por el centro de cortante, como puede suceder con
los canales, angulares, y algunas secciones armadas, a menos que se use un dispositivo especial de carga, se produce un momento de torsión junto con el momento
de flexión el que debe tenerse en cuenta para evitar el sobresfuerzo del miembro.
¡El diseño de vigas requiere un análisis analitico iterativo para determinar los
diagramas de cortante y momento basados en las varias combinaciones de cargas
(D + L, D + L + S, D + L + W, etc). Este proceso es relativamente sencillo
cuando se trata de vigas simples, aun ouando esté involucrada una carga viva móvil. Cuando estén implicadas vigas continuas y cargas vivas móviles, puede que
sea necesario usar líneas de influencia. Eluso de un programa de computadora,
como el que se da en el Apéndice (utilizado en el capítulo 2) presenta considerables ventajas, ya que es posible mover una carga viva a lo largo de la viga, yel
resultado estará directamente representado por las ordenadas de las líneas de
influencia.' La inspección de los resultados da directamente el momento crítico
de diseño. Si se requiere el cortante, se puede usar el momento junto con las cargas
para calcular retrospectivamente el cortante crítico.
Los esfuerzos /; producidos por el cortante y el momento se comparan con
los esfuerzos permisibles Fi, y se selecciona una sección (se usarán letras minúsculas para los valores calculados y mayúsculas para los valorespermisibles). Cuando el diseño se basa en el comportamiento del material por debajo dellímitepr~
I?orcionij~ sele llama al nrocedíiiilento diseño elástico o diseño por esfuerzos de
trabajo, y las ecuaciones que se usan se encuentran en cualquier texto sobre mecánica de materiales:
'Para flexión:

• _ My
Jb - 1

Para esfuerzos en la fibra extrema:

(4-1)

Para cortante:

(4-2) 1.v = VQIt \<- Fv
en que M = Momento de flexión, tomado del diagrama de momentos o por cál-
culo directo
y Distancia del eje neutro de la sección de la viga al punto donde se
desea conocer el esfuerzo (véase figura 4-2)

<!-- p. 172 -->

(b)

(e)

(f)

(e)

(g) (h)
Figura4-1 Se ilustran diversos tipos de vigas en el proceso de construcción de edificios. (a) Uso de vigas en un edificio industrial. La trabe carril es una viga armada. Se ven en la parte superior los largueros que descansan sobre las armaduras de techo. (b) Edificio de marcos rigidos que usa columnas y
trabes acarteladas para mantener un gran espacio interior libre de columnas. (e) Uso de viguetas armadas, tanto para las trabes como para los largueros de techo. (d) Sencillo edificio de unsolo piso con las
vigas de techo simplemente apoyadas en las columnas. Se resiste el viento en ambas direcciones usando contravientos en las cuatro esquinas. (e) Trabe (de izquierda a derecha) y sistema de vigas de piso
en un edificio de oficinas. (f) Vista de cerca, que muestra la armazón de vigas de piso y largueros. (g)
Vigas de techo y de borde-para un edificio de techo plano. (h) Viguetas de techo (parcialmente colocadas); también vigas de piso, trabes, y vigas de borde exteriores.

<!-- p. 173 -->

DISEÑO DE VIGAS POR EL METOOO ELASTICO 173

x-- --x ___ n.a.

v )
Tensión
A = área sombreada

\~ l Centroide de A
\~ x--- X = eje neutro

VAl'
Iv = h __==:tz===__
Figura 4-2 Esfuerzos a flexión y cortantes en las vigas.

e Distancia del eje neutro a la fibra extrema
I Momento de inercia de la sección transversal
S JIe = módulo de sección (tanto I como S están tabulados en las
tablas de propiedades de las secciones, como las tablas 1-4 y V-4 del
SSDD)
Q Momento estático del área por encima del punto en el que se deter-
mina el esfuerzo cortante = Ay (refiérase también a la figura 4-2)
t = Espesor de la viga en el punto de investigación del esfuerzo cortan-
te
V Fuerza cortante critica, tomada del diagrama de cortante o por
cálculo directo.

Se revisa la sección para asegurarse que es adecuada para soportar su propio
peso, y por último se verifican las deflexiones causadas por la carga de trabajo.A
veces son las deflexiones más bien que los esfuerzos las que controlan el tamaño
de la sección, especialmente cuando las deflexiones están rígidamente limitadas.
Los valores de las deflexiones varían comúnmente desde L/360 hasta un valor tan
pequeño como L/lOOO..

4-2 DISEÑO DE VIGAS POR EL METODO ELASTICO

Se usarán por lo general los perfiles W como vigas. A veces, se utilizan perfiles S,
M Yhasta canales, dependiendo del lugar, modo de conexión al resto de la armadura, y las cargas a soportar. Los perfiles W, que tienen patines relativamente
anchos, son por lo general más estables en relación con el pandeo lateral y casi

<!-- p. 174 -->

174 DISEÑO DE VlGAS A FLEXION

siempre son más económicos en términos de peso que cualesquiera otros perfiles
producidos.
Al examinar la ecuación (4-1) se ve que, siendo iguales todos los factores, la
sección preferida tendrá un módulo grande de sección, S. Nótese también que un
mayor módulo de sección por lo general está acompañado por un aumento en el
peralte de la viga. Como varias de las secciones laminadas tienen casi el mismo
valor de S, es necesario hallar al mismo tiempo la sección más ligera y una que
tenga un valor adecuado de S. Las tablas II~l y VI-l en el SSDD (yen el AISC)
tienen las secciones que se usan comúnmente para las vigas arregladas en orden
descendente de S y con respecto al eje Xs X (eje fuerte). Esta ordenación es también con respecto al peso, de modo que considerando un grupo definido por los
dobles espaciamientos. se tiene que:

l. El mayor valor de s en cualquier grupo está en la parte superior de dicho gru-
po.
\2. La sección más ligera del grupo está en la parte superior y la más pesada en la
inferior.

(o)

(e)
Figura~3 Fotografías de fallas en vigas, producidos por cargas aplicadas en el laboratorio. (a) Pandeo lateral de una sección W. (b) Pandeo del alma de una viga corta, con una carga concentrada a la
mitad del claro. (e) Pandeo del patin, acompañado del pandeo del alma del caso (b).

<!-- p. 175 -->

DISEÑO DE VIGAS POR EL METODO ELASTICO 175

Este ordenamiento permite determinar rápidamente la sección laminada más
económica, que se ha de usar como viga, basados en las consideraciones de esfuerzo y peso. A veces puede ser necesario usar una sección con menor peralte
(con el correspondiente aumento en el peso). Esto puede tener particular importancia en los marcos de los edificios, ya que el uso de una sección W16 contra una
W2l, puede resultar en un ahorro de 5 pulg/piso. En un edificio de 20 pisos, esto
equivale a 100pulg, lo que puede representar un piso adicional para la misma longitud de columnas, el techo, y área de terreno, con sólo el costo extra de las armaduras de piso y ventanas más algunos costos extra por servicios. Cuando se especifique el peralte de la viga, es necesario investigar la tabla 1-4, o la VI-4 (SSDD)
hasta que se encuentre la sección más económica dentro del peralte nominal
dado.
Dos factores influyen de modo considerable en el esfuerzo máximo permisible a flexión, Fb, en el diseño de las secciones laminadas. Estos son:

l. Geometría de la sección (basada en la relación ancho del patín/espesor y la re-
lación peralte/espesor del alma).
\2. Apoyo lateral (o espaciamiento del soporte lateral).

Estos dos factores son consecuencia directa del problema del pandeo de placas planteado en el capítulo 3. Si las relaciones ancho/espesor del patín (b¡I2!¡) y
peralte/espesor del alma (d/!w) no fuesen adecuadas, los elementos de la sección
tenderán a pandearse con bajos esfuerzos de compresión (esta compresión sedebe
a la flexión + algunos esfuerzos debidos a las cargas axiales). Si el patín de
compresión no está soportado en algunos intervalos a lo largo de la zona de
compresión, se pandeará en el plano o fuera del plano acompañado de torsión.
Estos tipos de falla se ilustran en la figura 4-3 (prueba de laboratorio) y la figura
4-4 (dibujo esquemático).

Posición cargada Posición origina!
'-~~I
\--L
f
Al'(f--~-~-1t- \-,-1
(al
Figura 4-4 Esquemas detallados de la consideración de la estabilidad de la viga, producida por esfuer-
zos en el patín a compresión, debidos a la flexión. (o) Pandeo del patín, cuando la compresión es muy
grande y está lateralmente apoyado de modo que no ocurre pandeo lateral (ilustrado en la figura
4-3c). Nótese que este tipo de falla puede estar acompañado por el pandeo vertical del alma. (b) Pan-
deo lateral o torsión. Nótese que la sección se ha desplazado lateral y verticalmente, y además se ha
torcido. El ángulo () se refiere a la posición original de la viga. Este tipo de falla se ilustra en la figura
4-30.

<!-- p. 176 -->

176 DISEÑO DE VIGAS A FLEXION

El diseñador tiene poco control sobre la geometría de la sección; sin embargo,
los productores de acero, por medio de un análisis refinado y el espaciamiento
de los rodillos, producen secciones con relaciones bf I2tf Yd/t; tales que este factor
ya no es tan importante como los requerimientos de soporte lateral, los que si
puede controlar el diseñador.
La geometría de un perfil laminado puede ser tal que produzca una sección
compacta o no compacta, según las especificaciones del AISC. Las especificaciones de la AASHTO y el AREA no hacen esta distinción cuando usan métodos
de diseño elástico. Hoy día la última especificación de la AASHTO utiliza los criterios de sección compacta cuando se usa el método alternativo de diseño por factor de carga (AASHTO, sección 1-7.52). Tiene cierta ventaja contar con una sección compacta cuando se usen las especificaciones de diseño del AISC (para la
mayoría de los edificios), puesto que el esfuerzo básico de flexión es:
Fb = 0.6 Fy (para secciones no compactas)
Fb = 0.66 Fy (para secciones compactas) ....----..:..
Una sección compacta es aquella que cumple con los requerimientos siguientes:
(véase también la sección 1-5.1.4 en la Parte III del SSDD).

\1. El patín de compresión debe estar conectado de manera continua al alma
de la viga.
\2. Tiene las siguientes relaciones de ancho/espesor del patín:

bJ 65 pie • lb • seg: - \< -- u, VE;
Usese Fy = k/pulg- o MPa en éstas y todas las otras ecuaciones que sigan. Obsérvese también de que las relaciones bfl2tfY d/t; no tienen dimensión, por lo que
hay que usar unidades consistentes de pulg o mm.
Se pueden resolver las expresiones anteriores haciendo Fy = Fy, Yasí obtener
el límite superior del esfuerzo de fluencia para cualquier relación de bfl2t de una
sección, como se ve en las tablas 11-1 y VI-1. Estos valores se presentan de tal modo que, cuando se selecciona la sección, se comprueba para ver si el Fy del acero
que se usa es menor o igual al valor tabulado. Es fácil ver que no hay perfilesque
no cumplan con esta parte de los criterios "compactos" para el acero A-36, y que
el W610 x 154.8 no será "compacto", sólo cuando Fy > 403 MPa (W24 x 104
para Fy > 58 k/pulg2). .
\3. La relación d/t¿ está parcialmente controlada por la presencia de una carga axial. Sólo se considera en este lugar una viga cuya carga axial sea cero: por
consiguiente la relación d/t; (haciendo referencia al SSDD ya citado), será:

'lb d 640 pIe • • seg: - \<-- tw VF;

<!-- p. 177 -->

DISEI'l'O DE VIGAS POR EL METOOO ELASTICO 177

Se pueden resolver estas ecuaciones haciendo F"; = F; para obtener el d/t; límite
de cualquier perfil laminado. Este valor de F", se da en las tablas 11-1 y VI-l, donde se verá que todos los perfiles que se producen corrientemente para vigas, para
todos los valores de F, (hasta 65 k/pulg- ó 450 MPa) son compactos (como lo indica el signo ---).
\4. El patín a compresión se debe soportar adecuadamente para satisfacer los
últimos criterios "compactos". La distancia entre soportes laterales será la menor de las siguientes distancias (1os puntos de inflexión se pueden considerar como soportes laterales):

76bj 0.20bj L¡ = (ft) L¡ =-- (m)
12..¡F; ..¡F;

ó

20000 L2 = 139 000 (m) F'y X diAj

donde b¡ Ancho del patín a compresión, pulg o mm, tomados de la tabla 1-4
ó la V-4
.;d Peralte de la sección, pulg o mm
A j =Area del patín a compresión = bj x t¡;nótese que diAj está calcu-
lado en las tablas 1-4 y V-4
\=Esfuerzo de fluencia en kips/pulg- o MPa

El menor de los valores anteriores de L¡ y L2 se denomina Le (longitud soportada
lateralmente para una sección "compacta") y el mayor valor es L u• Ambos valo-
res se dan en las tablas 41-1 y VI-l.
(Cuando la longitud no soportada del patín a compresión, Lb S Le/Y la
geometría de la sección sea "compacta" se puede usar

Cuando la longitud sin soportar Lb ~ Lu, el mayor valor posible de Fb será

Cuando se tenga una u otra de las condiciones:

65 bj 95
ó --\<-\<;-- ..¡F; 21j ..¡F;

se puede usar una transición lineal entre 0-66!,y y 0.6Fb , tal como

<!-- p. 178 -->

178 DISEÑO DE VIGAS A FLEXION

(4-3) b = F ~[0.79 - A( ;~)~ ]

donde A 0.002 en el sistema pie.lb.seg y Fy en kips/pulg-
0.00076 en el sistema SI y Fy en MPa

El autor no recomienda el uso de la ecuación (4-3) para la mayoria de las situaciones ya que requiere un esfuerzo considerable de cálculo, para obtener cuando más un aumento del 1Opor ciento en el esfuerzo permisible. Sobre elbásico deF;
\= 0.6Fy (la mayoría de los valores mostrarán un aumento de solamente dez a 3
por ciento).
El esfuerzo básico de flexión del AASHTO y el AREA para vigas lateralmente soportadas es

(4-4)

Para. un acero A-36, esta ecuación de un valor ligeramente redondeado de
20 kips/pulg-, ó 138 MPa.

Ejemplo 4·1 Para una viga con el claro y las cargas que se muestran en la fi-
gura E4-1, selecciónese la sección más ligera usando acero A-36, si se puede
usar cualquier peralte en la viga.

SOLUCION trácense los momentos de cortante y momento, como se
muestra en la figura E4-1. A continuación, obténgase M máx = 276 pie-kip.
Con una carga uniforme sobre la viga, el patín superior está en contacto
con algo; así que se supondrá que hay soporte lateral total, de modo que

6 6 6 6'
IIIIII~ ~ 111111111111113r 1k/pie I !111 r!!
14 L = ~4' -1
43k

v-....---......--_I-__.....,. .....,

\~76 pie. kips

\~04 ft-kips ~04 pie • kips

M-"'----L--_--l .....L. ~ Figura E4-1

<!-- p. 179 -->

DISEÑO DE VIGAS POR EL METODO ELASTICO 179
y se usará Fb = 0.66 Fy =t x 36 = 24 kips/pulg-.
Al reordenar la ecuación (4-1), se tiene que el módulo de sección re-
querido es
s = M(l2) = 276(12) = 138 pulg '
x Fb 24

Es preciso encontrar una sección que tenga un valor de S un poco mayor que
el requerido, a fin de poder soportar el peso de la viga. Se selecciona en la
tabla 11-1,
W21 x 68: S; = 140 pulg!

Comprobando el peso de la viga, se tiene el valor adicional de S requerido

, 2
\~S = wL2(12) = 0.068(24) (12) = 245 1 3
x ) 8(24) . pu g 8(Fb
Sreq = 138 + 2.45 == 140.45 > 140 suministrado
Si se usa esta viga se tiene que el valor real defb = 24(140.5)/140 = 24.077
k/pulg-, o sea que la viga tendrá un sobresfuerzo de 77 lb/pulg- basado en
las condiciones dadas de carga. Se puede:

l. Aplicar un criterio de ingeniería y considerar aceptable este pequeño sobresfuer-
zo, o si no
\2. 'Se usará la siguiente sección, que es en este caso una viga
W24 x 68: s, = 154.0 > 140.45

Con un valor tan alto de Sx y siendo el peso el mismo que el de la sección anterior, no es necesario verificar de nuevo el peso de la viga.
El lector debe fijarse en que, desde el punto de vista de la deflexión, conviene
más elegir la sección W24. / / /

Ejemplo 4-2 ¿Cuál será la dimensión de la viga a usar en el ejemplo 4-1, si el
peralte de la viga está limitado a 16 pulg?

SOLUCION El Sreq será aproximadamente 145 pulg", ya que el peso tendrá
que ser mayor que las 68 lb/pie de la sección más económica seleccionada en
el ejemplo. Cuando la viga esté lateralmente apoyada se debe usar siempre el
máximo peralte posible. Por tanto, por la inspección de las secciones W16 de
la tabla 1-3, se selecciona
WI6 x 89: S = 155.0 pulg' d = 16.75 pulg > 16 no sirve

<!-- p. 180 -->

180 PISEÑO DE VIGAS A FLEXION
Pruébese W14 X 90: S = 143.0pulg? d = 14.02pulg (pJi\Íébese otra)
W12 X 106: S = 145.0 pulg! d = 12.89 pulg

Al comprobar el peso de la viga, se obtiene

6.S = 0.090(24i(12) = 3.24 ul 3
8(24) p g
Sreqd = 138 + 3.24 = 141.2 \< 143pulg-' suministrado

Se usará una viga W14 x 90 1//

Ejemplo 4-3 En la figura E4-3 se muestra el claro y cargas de una viga que es
aproximadamente igual al sistema de la viga del ejemplo 4-1. La mayoria de
los problemas en unidades SI serán aproximadamente iguales a los de las uni-
dades pie lb seg (pero nunca una conversión directa de unidades), de modo
que el lector tendrá una ayuda para familiarizarse con las unidades SI y la se-
lección de los tamaños. Se usará Fy = 250 MPa.

24
18 18 kN

206

v

206 kN

lIf

Figura E4-3

SOLUCION Primero, se trazan los diagramas de cortante y momento. Des-
pués, se obtiene M máx = 436A KN.m. Suponiendo soporte lateral total, se
obtiene
Fb = 0.67 x 250 = 167 MPa

El módulo de sección requerido es

<!-- p. 181 -->

DISEÑO DE VIGAS CONTINUAS 181

_ M _ 436 _ _3 3'/ .
S, - Ji: - 167 - 2.611 X 10 m
b
Nótese que 167 MPa x 103 = 167 X 103 kPa, que es consistente con 436
kN-m. Verifíquese un valor de S, en la tabla VI-I algo mayor. Hállese:
W610 x 113:1 S, = 2.8841 X 10-3 m!
Verifíquese el/1Sx causado por el peso de la viga = 1.11 kN/m:
'\S = 1.11(8l = 0.0532 x 10-3 m3
¡.;¿ x 8(167)
Sreq = S, + /1Sx = 2.611 + 0.0532 = 2.6642 \< 2.8841 x 10-3 m3 correcto

Se usará una sección W610 x 113.1 / / /

4-3 DISEÑO DE VIGAS CONTINUAS

Las vigas continuas se disefian de manera semilar a la de las vigas simples. La
principal diferencia consiste en que cuando se usan las especificaciones del AISC,
si la sección es compacta y no se trata de una viga voladizo, se puede diseñar la
sección usando uno de los dos modos siguientes:

l. 0.9 x el mayor momento negativo en el claro, o
\2. Momento positivo, basado en el momento máximo positivo del diagrama de
momentos + 0.1 x el promedio de los momentos negativos en el claro,

el que sea mayor. Estos momentos se basan en los momentos debidos a las cargas
por gravedad (D + L, D + L + S, etc., sin viento). Cuando la viga esté
rígidamente conectada a una columna, también se puede reducir el valor del momento de diseño de la columna, en dicho lugar. Este procedimiento se basa en la
aceptación del método de la formación de una articulación plástica y la resultante
transferencia de momento de la zona negativa a la positiva, hasta que se forme finalmente una articulación en dicho punto. Ahora se ilustrará dicho procedimiento.

Ejemplo 4·4 Usese el resultado de la computadora en el ejemplo 2-2 y
compruébese y/o rediséñense los miembros 22, 23 y 24 (refiérase a la figura
E4-4 para el momento por la carga de gravedad) (la inspección de la figura
E2-4d indicará los valores críticos del diseño). Se usará Fy = 250 MPa.

SOLUCION De los resultados de la computadora se obtienen los valores de
los momentos extremos

\- 57.86 + 140.64 -86.86 +86.88 -140.64 +57.86 kN . m

<!-- p. 182 -->

182 DISEÑO DE VIGAS A FLEXION

Col Col. Col.- Col.
52.5 kNrm
39.5 kN!m 39.5 k Nnn
® t23\ f24\
\1. 6.5 m 2.3 6.5 .1

141.1
115.6

357 2.93
2.93 - 1.15 3.57

115.()

2.37 - 2.37

57.ilú

86.86 140.64

Figura E4-4

Se necesitan estos valores para completar los diagramas de cortante y mo-
mento que aparecen en la figura E4-4.
Como se usa la misma sección para todos los claros, el mayor momento
de diseño se hallará por inspección en los claros 1 ó 3. Nótese que el momen-
to en el claro 2 es totalmente negativo, y quizás requiera soporte lateral en el
patín inferior (de compresión), si Lb = 2.3 > Le' Se debe investigar esta po-
sibilidad al seleccionar la sección.
El M - para el diseño es

M -= -140.6(0.9) -126.5 kN·m
El M + para el diseño es

M + = 111.3 + 57.86; 140.6(0.1) = 121.2 \< 126.5kN' m

Como el momento mayor es -126.5 kN·m, se usará este valor para selec-
cionar la sección. Nótese que el patín a compresión está parte por arriba y
parte por debajo, con puntos de inflexión como se muestran en el diagrama
de momentos de la figura E4-4. Se supone tentativamente que Le será mayor

<!-- p. 183 -->

PANDEO Y APLASTAMIENTO DEL ALMA 183

que los valores para el patín inferior; si así fuere, no se requerirá ningún so-
porte lateral y se puede usar r, = 0.66 F1
126.5 -3 3 Sreq > 167/= 0.7575 x 10 m

De la tabla VI-l, se selecciona una sección
W410 x 46.1: S = 0.7735 X 10- 3 m3
Le = 1.78 m > 1.20 correcto sin soporte lateral
Lu=2.16m
El punto de inflexión en cualquiera de los claros exteriores produce 0.87
m de patín de compresión sin soporte, en la parte inferior de la-viga. Esto se
considerará suficiente soporte para el patín a compresión, ya que el resto del
patín a compresión (arriba) está soportado por el piso. Se tendrá que usar un
soporte lateral a la mitad del claro para el patín inferior en el claro central,
para producir

2.3 78 Lb = T = 1.13 m \< 1.

Verifiquese por peso propio de la viga (peso = 0.45 kN/m). Por propor-
ciones (puesto que la carga de la viga es uniforme):

A _ 0.45 ( ) _ -3 3 uS - 39.5 0.7575 - 0.0086 x 10 m
Sreq = S + AS = 0.7575 + 0.0086 = 0.7611 x 10-3 m3 \< 0.7735 suministrado

Se usará una viga W410 x 46.1
El lector debe verificar que el método usado para obtener el AS sea la
manera correcta y más práctica disponible. Como se usó una viga W410 x
59.5 para el análisis inicial por computadora, parece que habrá que reprogra-
mar el problema después de que se haya hecho el diseño y revisión de la co-
lumna en un capítulo posterior. / / /

4-4 PANDEO Y APLASTAMIENTO DEL ALMA

El pandeo del alma es una distorsión fuera del plano del alma que resulta de la
combinación de una alta relación d/t.; y esfuerzos de flexión. La parte sin soporte
lateral del patín a compresión puede también contribuir al pandeo del alma. Este
pandeo se controla limitando ya sea la razón d/t.; o el esfuerzo que se puede usar
con la razón d/r; dada. Esto se tiene en cuenta en las varias especificaciones. El
pandeo del alma se ilustra en la figura 4-5b.

<!-- p. 184 -->

184 DISEÑO DE VIGAS A FLEXION
I

a) b)

Figura 4-S Fallas del alma que se deben evitar al hacer el diseño. (o) Aplastamiento del alma. (b) Pandeo del alma.

El aplastamiento del alma puede ocurrir si los esfuerzos a compresión en el
plano del alma son suficientemente grandes. Esto puede ocurrir si las distancias
de la reacción o las placas de asiento de carga que se usan para transmitir cargas
de columnas al patín de la viga son demasiado estrechas. El aplastamiento de la
viga también puede ocurrir si la carga uniforme sobre el patín es demasiado grande para el espesor del alma. Se obtendrá el control del aplastamiento del alma determinando la distancia requerida para la reacción o el ancho de la placa de base
de la columna de la siguiente manera. Se obtiene la distancia de reacción que se
necesita considerando un área a compresión en el alma definida por la longitud de
la reacción + una distancia adicional que utiliza una pendientel: 1 (45°) en la
distancia k de la sección. En las tablas de propiedades de las secciones se tabula k
para las varias seccioneslaminadas. La distancia k se mide desde la cara exterior
del patín hasta el extremo del filete que forma la transición entre el alma y el
patín. En este lugar el área resultante a compresión del alma se acerca a un
mínimo (aunque no llega al mismo). En una reacción, el área a compresión en el
alma es

El esfuerzo permisible en este lugar, según el AISC (véase SSDD sección
1-10.10.1), será

Fa = 0.75F;,
En una reacción, con f = R/A e, es

( Rk) s 0.75F;, (4-5) N + tw

Bajo una carga concentrada en el claro se puede desarrollar la distancia k a
ambos lados de la carga, como se ilustra en la figura 4-6. Para esta condición se
obtiene

<!-- p. 185 -->

PANDEO Y APLASTAMIENTO DEL ALMA 185

\~ r RI~=-=:s-- L_ ~__ ---- --
1-- o,,: + 2k---l
1", Lf~#####dl
L
1",
1---IV+ k ---.¡ k T .-.-¿-/
I 45°
I
R I
I
Figura 4-6. Longitud del apoyo para cargas concentradas en las vigas, según las especificaciones del
AISC.

R
(4-6) (N + 2k)t s O.75F;, w
donde N = Ancho de la reacción: se supone a menudo un valor básico de 34
pulg ó 89 mm (ancho de un ladrillo normal); N = ancho de la co-
lumna o el elemento transmisor de carga para las cargas interiores
R = Reacción u otra carga concentrada, kips, o kN
t w =espesor del alma en la sección, pulg o mm
k = Distancia desde la cara exterior del patín a la base del filete, pulg o
mm

Cuando se transmiten grandes cargas uniformes del patín al alma, puede que
sea necesario comprobar el esfuerzo de compresión fe, y limitar el valor a
t; s O.75F;,

Ejemplo 4-5 ¿Cuál es la reacción permisible para una WI6 x 40, usando el
valor básico de N = 3Yz pulg, con acero A-36? ¿Qué carga de columna
puede transmitirse usando una W8 x 31?

SOLUCION De la tabla 1-3, se obtiene para una WI6 x 40

k = 1.03pulg
tw = 0.305 pulg
R "'" (N + k)tw(0.75F;,) = (3.5 + 1.03)(0.305)(0.75 x 36) = 37.3 kips

<!-- p. 186 -->

186 DISEÑO DE VIGAS A FLEXION

La carga de la columa se limita a (suponiendo que la base de la columna
tiene exactamente el mismo tamaño que el peralte de la columna, como se in-
dica en la figura 4-6): para una W8 x 31: d = 8.00 pulg = N.
P = (N + 2k)t(0.75F;.)
\= [8.00 + 2(1.03) ](0.305)(0.75 x 36) = 82.8 kips / / /
Ejemplo 4-6 ¿Cuál es la reacción permisible para una sección W460 x 74.4,
usando el valor básico de N = 89 mm y Fy = 345 MPa? ¿Qué carga de co-
lumna se puede transmitir usando una W200 x 46.1?

SOLUCION De la tabla V-3 para una W460 x 74.4:

k = 27.8 mm
tw = 9.0 mm
R = (N + k)tw(0.75F;.) = (89 + 27.8)(0.009)(0.75 x 345) = 272 kN
Nótese que MPa x mm- x 10-3 = kN(no se muestra el factor 10-3) . La carga
de la columna es (suponiendo que la placa de base tiene las mismas dimen-
siones que el peralte de la columna): para una W200 x 46.1, el peralte d = N
\= 203 mm
P = [203 + 2(27.8) ](0.009)(0.75 x 345) = 602.2 kN / / /

Las reacciones en los puentes están por lo general suministradas por apoyos
especialmente fabricados, y las especificaciones. de la AASHTO requieren el uso
de atiesadores en el alma cuando-el Cortante en ella en el apoyo seafc > 0.75. En
general, las vigas de puente no soportan las cargas de las columnas. Las especificaciones del AREA son más estrictas que las de la AASHTO y requieren pares de
atiesadores del alma en los apoyos extremos y en los puntos de carga concentradas de trabes y vigas. El diseño de trabes armadas se considerará en el capitulo 10.

4-5 CRITERIOS DE CORTANTE

La distribución del esfuerzo cortante en cualquier sección sujeta a flexión puede
calcularse usando la ecuación presentada con anterioridad:

En la figura 4-7 se muestra un diagrama de esfuerzo cortante usando dicha
ecuación. Nótese que el esfuerzo cortante promedio basado en

(4-7)

<!-- p. 187 -->

CRITERIOS DE CORTANTE 187

50

490(6.71 X 0.2021)
fUe = 487 X 0.0127 . = 107.4 MPa
WI8 X 71 W460 X 105.7 Usese la tabla T para obtener !, A
d = 18.47 d = 469 111m
b¡ = 7.635 b¡ = 194.0 l' = at: Yrcc
I¡ = 0.810 I¡ = 20.6
I w = 0.495 1.. = 12.6 f."",. = dIV.. = 0.469 X4900.0126 -_ 0_."")"IP'" a
1= 1170 pul 4 I = 487 X 10 6 m"
V=IIOKips V=490kN

4.7
I I 716

Figura 4-7 Distribución del esfuerzo cortante teórica y promedio, en una sección según las condiciones indicadas.

difiere algo del valor máximo mostrado en la figura 4-7 (en este caso alrededor de
23 por ciento) pero es considerablemente más fácil de calcular. El AISC permite
el uso de la ecuación (4-7) ya sea para secciones laminadas o fabricadas (trabes armadas).
Las especificaciones del AASHTO y el AREA permiten el cálculo de fv basándose en el área de la sección "bruta". Esto puede interpretarse como en las especificaciones del AISC (o seef; = V/tw) '
El esfuerzo cortante permisible F; para las secciones laminadas se calcula
como

Ff) = O,AOF;. (AISC)
F; = O.33F;. (AASHTO)
Ff) = O.35F;. (AREA)

Los esfuerzos cortantes raras veces dominan la construcción de edificios, a
menos que la sección sea al mismo tiempo muy corta y esté fuertemente cargada,
como se ilustra en el siguiente ejemplo.

Ejemplo 4-7 ¿Cuál es la longitud del claro y la carga/pie de la viga de acero
A-36, que se muestra en la Fíg. E4-7, tal que controlen F; Ó Fb el diseño?
¿Qué longitud de N se requiere para la reacción?

11', kipsipie
\~ W24 X 94 1» 1- L -1 Figura E4-7

SOLUCION Datos para una W24 x 94:

<!-- p. 188 -->

188 DISEÑO DE VIGAS A FLEXION
d = 24.31 pulg k = 1.53pulg
t; = 0.515pulg S¿ = 222.0pulg3
wL
l; = 2t = 0.4..fy (a)
wd
wL 2
j¡, = 8S = 0.66F;. (b)
x'
De la ecuación (o)

0.4(36)(2)(24.31)(0.515) 360.6 w= =--
L L

Sustituyendo este valor de w en la ecuación (b) se obtiene

3~S6L = 0.66(36)
x
L = 24(8)(222) = 9 85 .
360.6 x 12 . pie
Sustituyendo de nuevo en la primera ecuación, se tiene que w = 360.6/9.85
\= 36.61 kips/pie. Comprobando se tiene

36.61(9.85)2(12) fb = . = 24.0 k/pulg- Correcto , 8(222.0)
\- 36.61(9.85) - 144 k/ l 2 C 1.v - 2(24.31)(0.515) - . pu g orrecto

La longitud de la reacción N basada en R = wLI2 = 180.4 kips y Fa =
0.75 Fy = 27 kip/pulg- es
(N + k)twFa = R
R N=--k
twFa

180.3
\= 0.515(27) - 1.53 = 11.44pulg III

4-6 FJ.EXION SEGUN EL EJE FUERTE Y FLEXION
SEGUN EL EJE DEDIL

Siempre que sea posible, se deben orientar las secciones de tal modo que se desarrolle la fexión con respecto al eje fuerte (X-X). Esto debe producir tanto el peso
mínimo de la sección como la menor deflexión debido a la carga.

<!-- p. 189 -->

DEFLEXIONES 189

Las limitaciones del peralte u otras consideraciones pueden requerir una
orientación tal que la flexión se produzca con respecto al eje Y- Y. El esfuerzo permisible de flexión de las especificaciones del AISC para secciones laminadas compactas con flexión con respecto al eje Y-Y Y para barras sólidas, redondas,
cuadradas o rectangulares se puede tomar como

(4-8)

donde B = 0.005 para unidades pie lb seg
\= 0.0019 para unidades SI
Para la mayoría de las secciones laminadas esto da aproximadamente Fb =
0.75Fy , que se puede usar en lugar de la ecuación (4-8). Cuando se usa ul}a barra
sólida, b/Lt¡ se convierte en ancho/peralte, y para una barra redonda se toma
b/Lt¡ = 1. El uso de la ecuación (4-8) se ilustra más adelante en el diseño de vigas
sin apoyo lateral, donde ocurre simultáneamente flexión con respecto a los ejes X
y Y.

4-7 DEFLEXIONES

A menudo se requieren estimaciones de las deflexiones bajo las cargas de trabajo
para asegurarse que los pisos son razonablemente planos y a nivel, y que la deformación de los marcos no haga que las puertas y ventanas no funcionen de manera
apropiada. Se pueden producir grietas en la mampostería y en los muros enlucidos o azulejeados si la subsiguiente aplicación de la carga viva produce excesivas
deflexiones.
Las deflexiones de gran magnitud por lo general indican falta de rigidez estructural y la posible vibración por el movimiento de las cargas vivas (incluyendo el movimiento de la gente) o los arranques o paradas de los elevadores, y los movimientos laterales producidos por fuerzas de vientos menores que las de diseño.
Las deflexiones de los techos planos producen la acumulación local del agua
(ya sea por lluvia o nieve), lo que a su vez aumenta la deflexión y la mayor acumulación de agua, terminando posiblemente con el colapso del techo. Puede notarse
también que este tipo de falla se produce por la combinación del agua acumulada
por las deflexiones locales junto con la falla del sistema de drenaje del techo
causado por su obstrucción debido a la basura acumulada por el viento o la congelación del agua retenida por la basura.
Las deflexiones de las vigas simples se pueden calcular usando la superposición de los efectos de la carga de las vigas y las ecuaciones tabuladas para la selección de cargas que se dan en los manuales (también en la tabla IV-5 del SSDD) y
en algunas más que aparecen en el párrafo siguiente. Para los otros casos de cargas, que incluyen vigas continuas, se puede calcular la deflexión usando la
ecuación diferencial general

<!-- p. 190 -->

190 DISEÑO DE VIGAS A FLEXION

Ely'" = -w

e integrando e incorporando las condiciones conocidas de borde para evaluar las
constantes de integración. Este método ya ha sido esbozado en la sección 2-2 y se
ilustrará en el ejemplo 4-9.
En general no es necesario hallar el valor "exacto" de la deflexión (particularmente para cartas vivas), puesto que no se conocen dichas cargas con mucha
precisión. En la figura 4-8 se tabulan varias ecuaciones de deflexión para cargas
uniformes y concentradas de las vigas.
Al examinar estas ecuaciones se ve que la deflexión es inversamente proporcional al momento de inercia l. El uso de secciones de menores dimensiones, como las provenientes del uso de aceros de alta resistencia, tenderá a aumentar las
deflexiones y pueden llegar a limitar el uso del acero de alta resistencia.

P

b XI' ~.x I \:--ad' II~ ~""-'-'-IrTl!"IT1II~IIII! III!!! I IIIIIIIIIII!

1" L .,

\~x Acarga ¿leen

2 PI 3 Pb2a Carga concentrada Pbx
48EI 6EIL (L 2 - b 2 - X 2 ) cuando a =b 3EIL

Pax¡ 2 2 2
6EIL(L-a -XI)

Carga uniforme wx 3 - 2Lx2 + x 3 ) 5wL4 24EI (L 384EI

Figura ....8 Cargas simples sobre las vigas, y las deflexiones resultantes.

Ejemplo 4-8 ¿Cual es la deflexión aproximada de la viga seleccionada en el
ejemplo 4-1?
SOLUCION La viga seleccionada fue una W21 x 68, con Ix = 1480 pulg".
La máxima ~ es en el centro y será causada por

Nótese que se necesita un factor de conversión de unidades de 1728 tanto pa-
ra w como para P expresados en unidades pie.lb.seg, cuando el claro está
expresado en pies y ~ en pulgadas. De las ecuaciones tabuladas se tiene que:

<!-- p. 191 -->

DEFLEXIONES 191

5wL4 5(3)(24)4(1728)
w =0.522 pulg a = 384EI = 384(29 000)(1480)
PL3 6(24)3(1728)
\=0.070 pulg ap2 = 48EI = 48(29 000)(1480)
A _ _ 2Pax (2 2 2) ~p2 - ap3~ 2ap2 - 6EIL L - a - XI

\= 2(4)(6)(1728) (242 _ 62 _ 122) =0.005pulg
6(29 000)( 1480)(24)
af =0.597 pulg
La máxima deflexión basada en L1360 es

L 24(12) 360 = 360 = 0.80 > 0.597 pulg

Por consiguiente, esta viga satisfará el criterio de deflexión menor de LI360.
III

Ejemplo 4-9 ¿Cuál es la deflexión estimada de la viga continua (miembro
\22) del ejemplo 4-4? Se dan los datos en la figura E4-9.
Datos de la sección: W410 x 46.1

1 = 156.1 X 10-6 m"
E = 200 000 MPa

r,57.86
" ~ 39.5 kN/m
f-.---6.5m---
115.6kN 141.1 kN Figura E4-9

SOLUCION Para la deflexión será necesario usar la ecuación diferencial
Elyiv = - W = -39.5
Ely'" = - 39.5x + CI pero e1 = reacción para x = O
Ely'" = - 39.5x + 115.6
2
Ely" = - 39.gx + 115.6x + C2 pero C2 = Mparax = O
2
Ely" = - 39.gx + 115.6x - 57.86
r - 39.5x3 115;6x2 57 86 C Ely - --6- + 2 - . X + 3 C3 = pendiente para x = O

<!-- p. 192 -->

192 DISEÑO DE VIGAS A FLEXION

El 39.5x4 115.6x3 58.86x2 C C y = - -2-4- + --:-6- 2 + 3X + 4
Deflexión = Opara x = OYes también Opara x = L, de lo que se obtiene C4
\= O. Al sustituir x = L, se obtiene
_ 39.5L3 _ 115.6L2 57.86L
C 3- 24 6 + 2
Para L = 6.5 m, se obtiene C3 = -173.98 (resultado de la computadora =
0.0043 rad) y.
_ 1 ( 39.5x 4 115.6x 3 57.~6x2 _ 173.98X)
Y-EI-~+ 6
resulta aparente que .:1x ocurre con +M = M máx, para x = 0.87 + 2.37 =
3.24 m, a partir del extremo izquierdo. Para este valor de x en la ecuación
precedente se calcula / / /
.:1 = -393.5 X 10- 3 MN . m = 0.0126 m
x (200 000)(0.0001561 m'')
\= 12.6 mm (aproximadamente t pulg] III

4-8 FLEXION BIAXIAL y FLEXION EN SECCIONES
ASIMETRICAS

En las secciones precedentes se ha considerado la flexión con respecto al eje X o al
eje y de los perfiles W, M, o S. En todos estos casos, el momento producido por
la carga se aplicaba perpendicularmente al eje X o el eje Y, con una linea de acción pasando por el origen de los ejes. Esto producia el esfuerzo de flexión que se
puede calcular usando la ecuación (4-1). Las secciones W, M y S son simetricas
con respecto al plano X- Y que contiene los ejes X e Y y son por consiguiente ejes
principales. Los ejes principales son tales que
Ix = fAy2dA
Iy = fAX2dA
Ixy = fAxy dA = O

La última ecuación, para Ixy es un término de producto de inercia que se origina
cuando al menos uno de los ejes X e Y no es eje de simetría. Los ejes principales
se producen como ejes mutuamente perpendiculares que pasan por el centroide
del área de tal manera que los momentos de inercia son un máximo con respecto a
uno de los ejes y un minimo con respecto al otro. Los ejes principales son ejes de
simetría para las secciones simétricas pero se pueden determinar para secciones

<!-- p. 193 -->

FLEXION BIAXIAL y FLEXION EN SECCIONES ASIMET\UCAS 193

asimétricas. Si el producto de inercia I xy no es cero, los ejes que interesan no son
ejes principales.

4-8.1 Secciones simétricas con flexión biaxial

Cuando los ejes X y Y son ejes principales pero la carga no se aplica perpendicularmente a los ejes principales (pero la resultante pasa por el origen de los ejes), se
produce la flexión biaxial. Para esta condición de carga, es necesario determinar
las componentes de la carga, perpendiculares a cada eje y utilizar la superposición
para hallar los esfuerzos en los lugares críticos, usando,

(4-9)

y para el cortante

(4-9a)

La ecuación (4-9) se usa comúnmente para las vigas de fachada y los largueros de techo, donde hay componentes de fuerza tanto verticales como horizontales. Cuando la carga se aplica al patín superior del miembro (lo que es común para los largueros en los techos con pendiente) y se separa en componentes
perpendiculares y paralelos a los ejes X e Y, la fuerza paralela al eje Y no pasa por
el origen de los ejes. Esto constituye un estado de esfuerzos muy complejo que
implica flexión biaxial y torsión. Se obtiene como solución aproximada

esto es, usando la mitad del módulo de sección de la sección para la componente
tangencial de flexión y el signo (+) se usa para obtener el esfuerzo.
Se usa ampliamente una forma alternativa de la ecuación (4-9) para la flexión biaxial y en una forma similar para combinar los esfuerzos de flexión y
axiales. Para obtener esta forma se hace lb = Fb Yluego se dividen ambos lados
de la ecuación entre el esfuerzo permisible Fb (fijándose en que esto se hará, aun
, se borra el (-) y se reordena para obtenercuando Fbx "* Fby)
M x My --+--= 1.0
FbxSx FbySy
Cuando se haga esto, una sección con cualquier combinación de momentos y módulos de sección que produzca 1.0, o menos, resultará satisfactoria; se debe tratar
de obtener un valor tan cerca de 1.0 como sea posible. Cualquier valor mayor de
1.0 implica un sobresfuerzo.

<!-- p. 194 -->

194 DISEÑO DE VIGAS A FLEXION

Figura E4·10

Ejemplo 4-10 Diséñese un larguero de techo usando una sección en canal pa-
ra los cobertizos laterales y para la más crítica condición de carga del
ejemplo 2-5. Colóquense los largueros a cada 6 pies medidos horizontalmen-
te, como se muestra en la figura E4-1O y úsense tirantes a 1""mitad del claro,
lo que dará una longitud sin apoyo de 12.5 pies para los momentos de flexión
con respecto al eje Y del larguero.

SOLUCION Datos adicionales tomados del ejemplo 2-5
Carga muerta = 20.0 lb/pie-
Carga viva = carga de nieve 25 cos ()
25 cos 14.04 24.25 lb/pie2
Total = 44.25 lb/pie-
Carga vertical/pie 6.18(0.04425)
0.273kip/pie
Carga normal debida al viento a 25 lb/pie- = 6.18(0.025) = 0.1545
kip/pie
Con viento, se puede aumentar en un tercio el esfuerzo permisible por lo
que es preciso verificar que la componente normal de D + S -+- W > 1.33(D
\+ 8):
D + S + W = 0.273 cos 14.04 + 0.1545
\= Q.4195 kipypie
1.33(D + S) = 1.33(0.273 cos 14.04)
\= 0.352 \< 0.4195 kipj'pie

<!-- p. 195 -->

FLEXION BIAXIAL y FLEXION EN SECCIONES ASIMETRICAS 195

Rige el caso del viento.
Con los tirantes como se muestran y las cargas aplicadas a la canal de la
manera indicada:

u, = W~2 = 0.4195(~5)2(12) = 393 pulg' . kips

2
) d on d e L = 12 . 5'pie (ta bl a IV-5 y am bIdos e eros carga os ) My -_. - 2( WIL6
(0.066)(12.5)2(12) 155 1 k' = ~ 2 16 =. pu g. ips

El esfuerzo permisible de flexión es Fb = 0.6 Fy para una sección asimétrica;
se aumenta en un tercio: F b = 0.6(36)(1.33) = 28.7 kip/pulg-, El esfuerzo
crítico será a tensión, en el patín inferior, ya que M; produce compresión en
el lado del alma debido al momento negativo en el tirante. Nótese que el Sy
de una canal se basa en la mayor distancia e (del centroide a la punta del
patín).

Se probarán varias secciones para encontrar una que satisfaga esta igualdad.
Primera prueba, C12 x 30:
S¿ = 27.00pulg ' Sy = 2.06 pulg '
393 31 _ 2 27.00 + 2.06 - 29.6 > 28.7 k/pulg N.S.
Segunda prueba, C15 x 33.9:
S, = 42.00 pulg ' S, = 3.11 pulg'
393 31.0 _ 9 42.00 - 1 . 3 ~ 28 .7 k /pulg 2 Correcto + 3.11
Se usará una sección C15 x 33.9, puesto que no hay otra sección más ligera
(puede que sea preferible una sección W).

<!-- p. 196 -->

196 DISEÑO DE VIGAS A FLEXION

4-8.2 Flexión con respecto a ejes no principales

Ahora se considerará el caso donde los ejes X e Y no sean ejes principales y la carga tiene alguna otra orientación. Esta orientación puede ser paralela y perpendicular a los ejes principales o tener cualquier otra dirección, pero pasando siempre
por el origen de los ejes. Si alguno de los ejes dados, X o Y, es un eje de simetría,
se usará el caso A o el concepto de centro de cortante que se presenta en la sección
siguiente. En este caso, las soluciones normales vienen dadas por

\-
Se requiere prestar mucha atención a los signos cuando se use esta ecuación, y se
obtendrá un signo + para la compresión cuando se use la convención de signos
de la figura 4-9. El término I xy es el producto de inercia, definido junto con I, e I,
como

Los momentos de inercia Ix e ly son siempre positivos; sin embargo, Ixy puede ser
ó (+) o (-). La orientación de los ejes principales con respecto a los ejes donde X e
Yes (véase también la figura 4-9):

(4-11)

Los momentos de inercia con respecto a los ejes principales, I xp e I yp , se pueden
calcular una vez que se conozca 8, y se puede usar la ecuación (4-9) en lugar de la

x

bh 3
Ix = 12
hb 3
x - 1"=12
Ixy =o

Figura 4-9 Signos convencionales e identificación de los
y términos para la ecuación (4-10) y la (4-11).

<!-- p. 197 -->

FLEXION BIAXIAL y FLEXION EN SECCIONES ASIMETRICAS 197

ecuación (4-10), si se usan los momentos principales. Los momentos principales
de inercia son:
Ixp = I; cos2 () + Iy sen- (J - 2Ixy sen (J cos ()
Iyp = Iy cos2 () + I; sen- (J + 2Ixy sen 9 cos () (4-12)

Nótese que si se suman las ecuaciones (4-12) se obtiene la siguiente igualdad útil:

Ejemplo 4-11 Se usa un angular 203 x 152 x 25.4 como dintel por encima
de una puerta corrediza. Investíguense los esfuerzos a flexión y estímese la
deflexión producida en este angular de lados desiguales para la carga que se
muestra en la figura E4-11.

SOLUCION Supóngase que:

\1. La mamposteria no puede resistir ningún esfuerzo apreciable de tensión,
de modo que cualquier deflexión produce el diagrama triangular de carga
que muestran las grietas.
\2. La mamposteria + el lado vertical del angular resiste cualquier deflexión
fuera del plano.
\3. La flexión asimétrica ocurre debido a que los ladrillos no están colocados
de tal manera que la resultante coincida con el centro del área.

Usando los pesos dados en la tabla IV-3 del SSDD y utilizando un revestimiento con un espesor igual a un ladrillo se tiene que:
Peso/m- = peso de un muro de ladrillo de 200 mm x la altura del muro so-
2 bre el dintel

Puntal del alero

Figura E4-11

<!-- p. 198 -->

198 DISEÑO PE VIGAS A FLEXION

w = 3.;7 x 2.3 m= 1.89kN/m (véase tabla IV-3, SSDD)

Peso del angular = 0.645 kN/ m
Total =2.535 kN/m

M = WL/6 tomada de la tabla IV-5, donde W = wL/2.
u, = 10.39;(8.2) = 14.21 kN . m

Nótese que se desprecia cualquier torsión debido a que no se coloquen los
ladrillos de tal manera que su peso actúa a través del centro de área del angu-
lar.
Las propiedades de la sección L203 x 512 x 25.4 son:

6 Ix = 33.63 X 10- m" Iy = 16.1 X 10-6 m" A = 8.387 X 10-3 m2
rz = 32.5 mm tan a = tan O= 0.543
O= tan - I 0.543 = 28.5o
De la ecuación (411),
Ixy = (t, - 1) tan 20
\= (16.1 - 33.63) tan 2(28.5) = -27.0 x 10-6 m"
El eje\<Z-Zde la tabla V-8 es el I xp usado en este caso
Ixp = Ar; = 8.387 X 10- 3 m(0.0325 m)2 = 8.859 X 10-6 m"
Como I xp + Iyp = t, + Iy'
Iyp = 33.63 + 16.1 - 8.859 = 40.87 x 10-6 m"
Usando la ecuación (4-1) y fijándose en que M y = O, se obtiene

donde (Ix1y - F xy) x 103 (se usa 103 para convertir kN a MN). Sustituyen-
do valores se obtiene
lb = - 2046x - 1220y (si se hace igual a cero, da la situación del eje
neutro)
En el punto A, x = - 0.0419,Y = + 0.1357 m.
lb = -2046(-0.0419) - 1220(0.1357)
\= -79.8 MPa (compresión)

<!-- p. 199 -->

FLEXION BIAXIAL y FLEXION EN SECCIONES ASIMETRICAS 199

En el punto B, x = - 0.0419,Y = - 0.0673.
/b = 167.8MPa (+ = tensión)
y

A

\---------x
M
r-.
\-o1-_--+-----_ e
41.9 8 110.111101--1
En el punto C, x = 0.110,Y = - 0.0673.
/b = -142.9 MPa (- = compresión)

Si se usafb = Mc/I se tiene que:
En el punto A:

1;, = 14.2~~~6~357) (leP) = 57.3 MPa (compresión)

En los puntos B y c:

/b = 14.2~~~6~73) (leP) = 28.4MPa (tensión)

Estos valores difieren en modo considerable de los calculados usando flexión
asimétrica.
Verifiquese de manera aproximada las deflexiones usando la tabla IV-S
para una viga simplemente apoyada:
A = wL 3 = 10.394(8.2)3 = 0.0142m
60EI 60(200 000)(33.63 x 10-6)
Esta deflexión tiene un valor calculado de 14.2 mm (más de Y2 pulg), que
podría hacer que se rajara el recubrimiento de ladrillo, en el caso de que
ocurriera en realidad. Sería preciso aplicar buen juicio ingenieril para decidir
si este angular resultaria satisfactorio teniendo una posible deflexión de 14
mm, pero que quizá fuese mucho menor que dicho valor. / / /

<!-- p. 200 -->

200 DISEÑO DE VIGAS A FLEXION

4-9 CENTRO DE CORTANTE DE SECCIONES ABIERTAS

El centro de cortante sitúa el punto con respecto a una sección transversal en don-
de se debe aplicar la carga de flexión de modo que no ocurra ningún retorcimien-
to (O torsión) cuando los esfuerzos cortantes debidos a la flexión actúan en el pla-
no que pasa por el punto. Por tanto, si la carga pasa por el centro de cortante, se
puede analizar la sección para flexión y cortante simples, usando las ecuaciones
(4-9) y (4-90). Si la carga de la viga no pasa por el centro de cortante, se desarrolla
un momento de torsión que produce esfuerzos cortantes torsionales con un valor
de

Ve't
fs=¡ (4-13)

donde Ve r = Cortante y excentricidad del cortante con respecto al centro de
cortante
t = Espesor del elemento donde se desea hallar el esfuerzo cortante
J = Constante torsional de la sección, para un rectángulo delgado
bt 3 ~ 10 (alma y algunos patines de las secciones) J = ""3 b/ t
bt 3
\~ 4 (patines gruesos, como en los canales) J = ""3 - 0.21t4 b/ t

El cálculo del centro de cortante resulta complicado excepto para los perfiles
más simples. Por fortuna, la mayoría de las secciones tiene situado el centro de
cortante en un lugar conveniente (véase figura 4-10), por ejemplo:

l. Si una sección contiene un eje de simetría, el centro de cortante se halla sobre
dicho eje.
\2. Se infiere, de (1) que el centro de cortante de todas las secciones con simetría
respecto a ambos ejes se halla en la intersección de los dos ejes (todos los perfiles
W, M, y S).
\3. En todas las secciones que consisten de elementos formados por placas que se
intersecan (angulares, tes, etc), el centro de cortante se encuentra en la inter-
sección de las placas.

Es más fácil demostrar que el centro de cortante Eo(usando los símbolos de
la tabla 1-6) para canales es

(4-14)

donde b, = b¡ - tw/ 2
h' = d - tI = peralte promedio de la sección
tp tw = espesor del patín y del alma, respectivamente

<!-- p. 201 -->

CENTRO DE CORTANTE DE SECCIONES ABIERTAS 201

)' .. y .. \'
t"1-"+'~-"~':E' , ' ~ , , • • Localización del centro
de cortante

.l'
Figura 4-10 Localización del centro de cortante para varios perfiles laminados.

Usando estosvalores para una ClO x 30, con d = 10.00 pulg, b¡ = 3.033 pulg,
ti = 0.436 pulg, y t; = 0.673 pulg, se obtiene Eo = 0.705 pulg, como en las tablas
del AISC y la tabla 1-6del SSDD.
El lector debe fijarse en que hay varias ecuaciones que se usan en las diversas
tablas de diseño y que suministran valores de Eoligeramente diferentes de las de la
ecuación (4-14), dependiendo de las suposiciones que se hagan para el flujo de
cortante en los patines. El cálculo del centro de cortante de los perfiles más
complicados está fuera del alcance de este texto; el lector puede consultar cualesquiera de los textos sobre mecánica de materiales avanzada.
El esfuerzo de flexión para las condiciones en las que se desarrolla torsión,
debido a que la carga aplicada no pasa por el centro de cortante es, aproximadamente

(4-15)

donde Me!1 = Cálculo común del esfuerzo de flexión
V = Cortante a una distancia x a lo largo de la viga, a partir del origen
bI = Ancho del patín sometido a esfuerzo
x Distancia desde el origen del eje hasta V, y donde se desealb
II = Momento de inercia del patín sometido a esfuerzo; aproximada-
mente 1/2 para un canal

Ejemplo 4-12 ¿Cuál es el esfuerzo aproximado de flexión y torsión en una
canal CI0 x 30, con la carga que se muestra en la figura E4-12?

Revestimiento de ladrillo

0.35 kip/pie incluyendo el peso del canal

f--------12.5'--------+l Figura E4-12

<!-- p. 202 -->

202 DISEÑO DE VIGAS A FLEXION

SOLUCION De la tabla 1-6, las propiedades de la sección de una CI0 x 30
son:
Sx = 20.70 pulg! Eo = 0.705 pulg
Iy = 3.94 ;;¡; Uf b¡ = 3.033 pulg
En la mitad del claro:
L
x=- V=O 2
M = w~2 = = 82.0pulg' kips 0.35(1285f(12)
lb = 2~~7 = 3.96 ksi « 0.6.F;,(22 k/pulg-)
Para x = L/4 = 3.13 pies:
w(L - x 2) 0.35(12.5 - 3.132)(12) 57 1 k' Mx = 2 = 2 = . pu g : rps

Vx = ~L - wx = 0.35( 1;5 - 3.13) = 1.092 kips
f _ 5.7 1.092(3.13)(3.03)(12)
Jb - 20.7 + 3.94
\= 0.3 + 31.6 = 31.9 k/pulg- » 0.6.F;,
Nótese que si la canal se diseñara sin considerar la torsión y la posición del
centro del cortante, el esfuerzo de flexión aparente a la mitad del claro indica
que la sección está considerablemente sobrediseñada. Cuando se consideran
los efectos del centro de cortante, la sección no resultará adecuada a menos
que se suponga que el análisis es demasiado aproximado y que las conexiones
extremas son tales que restringen la rotación de manera que no se desarrollan
grandes esfuerzos de flexión. El autor supondría, por su parte, que la sección
está considerablemente subdiseñada y usaría una sección distinta, ya que se
incurriría en un gran riesgo de diseño en comparación con la poca economía
al usar una sección más ligera.
El esfuerzo cortante de torsión se puede evaluar como

Ve'tf fs =-J-

J = Contribución del alma + los dos patines
3
bt? ( bt 4 ) J = 3 + 2 3 - 0.21t

\= 10 _ 2(0.436~(0.673)3 + 2(3.033~(0.436)3 _ 0.21(0.436)4
\= 0.927 + 0.152 = 1.08 pulg" (vs. 1.22 pulg en el SSDD)

<!-- p. 203 -->

DISEÑO DE VIGAS SIN SOPORTE LATERAL 203

La discrepancia entre el valor de J calculado anteriormente y el de las tablas
SSDD se debe al uso de un cálculo más refinado en las tablas, que tiene en
cuenta el aumento de la rigidez en la intersección del patín y el alma. Se usará
el valor de J = 1.22 que se halla en la tabla.
\= 0.751 + 0.649 = 1.40 pulg e' = Eo + x
fs = 1.092(\~~~(0.436) = 0.546 kips/pulg- que parece satisfactorio / / /

4-10 DISEÑO DE VIGAS SIN SOPORTE LATERAL

En muchos casos, los miembros a flexión tienen el patín de compresión con
restricción adecuada para satisfacer el apoyo lateral, o los requerimientos de soporte lateral. Esto es cierto en particular en las vigas que soportan pisos y techos,
donde la viga está en contacto directo continuo con el piso o el techo o si no algo
empotrada en los mismos. En los casos en que el sistema de piso consiste en una
cubierta metálica colocada sobre las vigas, puede que no se provea adecuado apoyo lateral si la resistencia se debe sólo a la fricción. En dichas situaciones, soldaduras cuidadosamente situadas para tomar por ejemplo del 2 al 3 por ciento de la
fuerza sobre el patín (0.02 a 0.03 A¡fb) proveerán soporte lateral adecuado. No se
requiere una restricción lateral muy grande, como se evidencia en la aplicación de
fuerza meramente manual para restringir vigas de dimensiones relativamente
grandes contra el pandeo lateral en las pruebas de laboratorio.
La flexión y alabeo laterales en las vigas sin apoyo lateral se ha ilustrado ya
en las figuras 4-2 y 4-3. Hay situaciones diversas, que abarcan especialmente
miembros verticales a flexión y vigas que se usan para soportar las cargas de columnas en grandes áreas abiertas, trabes carriles, y vigas continuas de grandes
claros, donde el patín a compresión no está en contacto con la cubierta u otros
elementos; en estos casos no es práctico proveer soporte lateral, excepto en los
extremos y/o en unos pocos puntos interiores dentro del claro. En aquellas condiciones donde el patín a compresión no está apoyado cierta distancia, la acción tipo columna resultante, puede producir pandeo del patín, alabeo (rotación parcial
o total de la sección), y flexión lateral. Sólo el efecto de superposición de los esfuerzos verticales de compresión, debidos a la flexión sumados a los esfuerzos de
compresión debidos a la flexión lateral, al deflexionarse la sección fuera del plano, puede producir esfuerzos de fluencia o pandeo en un lado del patín sujeto a
compresión. En cualquier caso, donde sea posible esta situación, se reducen los
esfuerzos permisibles de compresión. Esta reducción es crítica cuando la sección
es ligera y con un peralte grande, puesto que con la flexión lateral la resistencia al
alabeo de los patines y el alma es pequeña. Esto también resulta cierto para vigas
largas sin apoyo en casi toda su longitud, puesto que, como sucede con el pandeo
de una columna de gran longitud, se necesita sólo una carga pequeña (o esfuerzo)
para hacer que el patín a compresión se flexione lateralmente fuera del plano y
exista la tendencia al alabeo.

<!-- p. 204 -->

204 DISEÑO DE VIGAS A FLEXION

Se puede efectuar una combinación teórica de la resistencia lateral por flexión y torsión para obtener el esfuerzo crítico de pandeo en el patín a compresión:

(4-16)

o, alternativamente,

(4-17)

donde J = Constante de torsión, definida previamente y que se da en la tabla
de propiedades de las secciones del SSDD
\~-kl¡bl(d - 1¡)2 Cw = Constante de alabeo
E
G = Módulo de cortante = 2(1 + Jt} = 11.150 k/pulg- para Jt = 0.3
Iy = Momento de inercia con respecto al eje Y
S; = Módulo de sección con respecto al eje X
L = Longitud no soportada. lateralmente

Si se realizan las siguientes aproximaciones:

Iy = Ar; rx = O.4ld
S = __2Ar x2 h = 0.95d x d

y se sustituyen en la ecuación (4-16), se obtiene
F = 14E L/ry )2 1 + 0.0476 ( d/t¡ (4-18) cr {L/r)2

Sustituyendo de manera similar en la ecuación (4-17), se obtiene

F = 3E d/t¡)2 (4-19) cr Ldfr.tyj 1+21 ( L/ry

Para vigas con baja rigidez torsional, la ecuación (4-18) es casi

(4-20)

y para vigas con alta rigidez torsional, la ecuación (4-19) es aproximadamente

<!-- p. 205 -->

DISEÑO DE VIGAS SIN SOPORTE LATERAL 205

Fer = ~~ t (4-21)
yJ

Uno de los métodos para obtener Fer consiste en calcular valores tanto de la
ecuación (4-20) como la (4-21), y usar el mayor valor. Sin embargo, nótese que la
expresión original de la ecuación (4-17) toma la forma siguiente, cuando se usan
los valores aproximados de las ecuaciones (4-20) y (4-21):

(4-22)

Esta ecuacion se puede interpretar de la manera mostrada en la figura 4-11. Si no
se usa la resultante para Fer, la solución más apropiada después de esta última
consiste en usar la rama más larga del triángulo recto, lo que produce un error
máximo de ($- 1.0)100 = 41 por ciento. La mayoría de los casos no serán tan
extremos.

Ec. (4-2') é (4-21)

Figura 4-11 Interpretación gráfica de la
ecuación (4-22)

Se pueden ahora desarrollar las especificaciones del Alse usando las diversas
ecuaciones precedentes, junto con algunas simplificaciones adicionales y redondeando números. Más o menos desde 1946, las especificaciones del AISe han
usado la siguiente fórmula basada en la sustitución de Ty = 0.22b, aplicando un
factor de seguridad de 1.67 y un factor Cb para tener en cuenta el gradiente de
momento (que es la última modificación) a la ecuación (4-21), y obtener

12 OOOCb Fb = LdfAl s 0.6r;, [AISC, ecuación (1.5-7)] (4-23)

82 700Cb s, = LdfAl (Unidades SI) (4-23m)

donde A¡ = Area del patín a compresión = bJ¡
d = Peralte de la sección; nótese que la razón diA¡está calculada y tabu-
lada ea las tablas de propiedades de las secciones
\~ 2.3. En esta ecuación, MI es Cb = 1.75 + 1.05(MIIM2) + 0.3(MIIM2f
siempre el menory M 2 el mayor momento en el extremo de la longi-

<!-- p. 206 -->

206 DISEÑO DE VIGAS A FLEXION

tud sin soporte lateral M/M 2 = (+) cuando los momentos son del
mismo signo (lo que produce curvatura doble) y M 1/M2 = (-)
cuando son de signos opuestos. Se usará Cb = 1.0 cuando el mo-
mento en el interior de la longitud no soportada es mayor que cual-
quiera de los momentos extremos sin importar el signo.

El Column Research Council ha propuesto como alternativa a la ecuación
(4-20), la fórmula básica de columnas

j F (L r)2 ]F (4-24)
y cr =[1.0 - 2C2C
e b
Haciendo FS = 1.67, esta ecuación se convierte en

F r)2 ]0.60F (4-25) =[1.0 _(Lj y b 2C 2C e D
donde el término Ce = relación de esbeltez para la que los esfuerzos residuales
producen pandeo inelástico, o la transición Llr de pandeo inelástico a pandeo de
Euler:

Sustituyendo este valor y usando 0.667 en lugar de 0.6 en el primer término (l.0) y
aproximadamente 0.75 para el segundo término en la ecuación (4-24), se obtiene

2 ~(LjrT)2 ]
\~ [AISC, ecuación (1.5-60)] (4-26) r, = "3 - 1530 X I\<>3C [ b

(Unidades SI) (4-26m)

donde rT = radio de giro del patín a compresión + 1/3 del área a compresión del
alma, tomada con respecto al eje Y; estos valores se dan también en las tablas del
AISC y el SSDD.
En la ecuación (4-26) se tiene en cuenta la posibilidad del pandeo inelástico;
sin embargo, el pandeo elástico es también una posibilidad, dependiendo de las
proporciones de la sección y de la longitud sin soporte lateral. En este caso se
puede usar la ecuación (4-18) con r, = 0.38d en lugar de 0.41d, para obtener

<!-- p. 207 -->

DISEÑO DE VIGAS SIN SOPORTE LATERAL 207

Dividiendo entonces entre FS = 1.92 Ytomando rr == 1.2ry, se obtiene un esfuerzo permisible de flexión de .
170 x loJCb Fb=----~ (Unidades [AISe, ecuación (l.5-6b)] (4-27)
pie lb seg) (L/rTi
l.l7 X 106C6 Fb =----:-..::. (Unidades SI) (4-27m)
(L/rTi
La relación mínima LlrT para usar la ecuación (4-26) se halla haciendo Fb =
0.6Fy para obtener (con un ligero redondeo):

L 102 x loJCb -= (Unidades pie lb seg)
rT ~

L 706 x loJCb -= (SI)
rT ~

Por criterios diferentes del LlrT (como el de la sección compacta o la
ecuación AISC 1.5-7) se determinará Fb , cuando LIrT es menor que el obtenido
de la ecuación anterior. La relación mínima de LlrT para la que se aplica la
ecuación (4-27) se halla igualando las ecuaciones (4-26) y (4-27) (redondeando ligeramente otra vez): .
L 510 x loJCb (pie lb seg)
rT ~

L 3.54 X I\<>6Cb (SI)
rT ~

En todos estos casos se necesita calcular el esfuerzo permisible de flexión por las
ecuaciones del AISC (1.5-60) o (1.5-6b) dependiendo del L/rT y por la ecuación
AISC (l.5-7). El valor mayor que se obtenga de las dos ecuaciones es el que se
emplea para el diseño. Se puede usar un análisis más refinado", según el AISC.
Lo que significa que se puede usar

2
Eq. (1.5-60)
or + [Eq. (1.5-7)]2
[ Eq. (1.5-6b) ]

según la ecuación (4-22) y como se ilustra en la figura 4-11 .
fSe puede resumir de la siguiente manera el diseño de vigas sin apoyo lateral:

<!-- p. 208 -->

208 DISEÑO DE VIGAS A FLEXION

F~~ ~e selecciona tentativamente una1. Se supone en primer lugar que F» = 0.6
sección, usando una tabla como la tabla-Il-f del SSDD que da también Le Y
L u. Si la longitud real sin soporte lateral Lb ::5 Le O L u' se podrá obtener una
solución directa puesto que la longitud no soportada no será un factor por
considerar.
\2. Si la sección tentativa indica que L; \< Lb puede que la longitud sin soporte sea
un factor de diseño. Usando la sección tentativa, o una algo mayor, calcúlese
Fb usando la ecuación (4-23). Si esta ecuación da un valor de Fb que satisfaga
la flexión, se obtendrá una solución (que tal vez no será la mejor).
\3. Si la ecuación (4-23) no da una solución satisfactoria, eldiseñador tendrá que
usar la ecuación (4-26) o la (4-27), dependiendo de la relación L/rT. Usese el
valor mayor de Fb que se obtenga, ya sea de la ecuación (4-23) o de las
ecuaciones de control (4-26) ó (4-27) según lo determina L/rT'

Se puede usar una tabla de longitudes no soportadas lateralmente versus momentos permisibles de flexión, como las tablas 11-3 ó VI-3, para obtener un diseño directo o para dar una indicación de las secciones que posiblemente puedan resultar adecuadas'!
Los siguientes ejemplos ilustran el uso de las ecuaciones para vigas no soportadas lateralmente.

Ejemplo 4-13 Dada una trabe que utiliza una W36 x 300 y que soporta dos
columnas, como se muestra en la figura E4-13, ¿cuál será la carga máxima de
las columnas usando las especificaciones ASCI y acero A-36? Supóngase que
la trabe está restringida contra rotación solamente en los extremos. Las co-
lumnas pueden proveer alguna restricción lateral, pero no se la-.tendra en
cuenta.

FiguraE4-13

SOLUCION Complétese la figura E4-l3 trazando los diagramas de cortante
y momento, como se muestra. A continuación, obténgase de la tabla 11-1 del
SSDD, para una W36 x 300, Le = 17.6 pies y L; = 35.3 pies. Como Lb >
t.; (46 > 35.3), se ve inmediatamente que Fb \< 0.6 Fr

<!-- p. 209 -->

DISEÑO DE VIGAS SIN SOPORTE LATERAL 209

M = 17P( 12) + 0.30(46)2(12)
8
M = 204P + 952.2 pulg . kips
übténganse de la tabla 1-3 las propiedades de sección para una W36 X 300:
s; = 111O¡pulg3 d- = 1.31 pulg-l 'r = 4.422.pulg A¡ •

Cálculo alternativo de diA¡:
d = 36.74 pulg b¡ = 16.655pulg t¡ = 1.680pulg
d d 36.74 _ 131 1-)
A¡ = b¡t¡ = 16.655(1.680) - . pu g

Cálculo alternativo de rr:

. t¡bJ 1.690(16.655)3 __ 6468 1 4 I¡ = 12 = 12 . pu g

A¡ + ~w ~ 16.655(1.680) + 36.74 - 2~.680)O.945

\= 33.24.pulg 2
.. (i; .. ¡¡;;¡¡;s 'T = VA = V3I24 = 4.411 pulg

La ligera discrepancia se debe a los cálculos algo aproximados que se han
usado; sin embargo, este método es satisfactorio cuando hay que calcular rr.
eb = 1.0, ya que en el diagrama de momentos se muestra que los momentos extremos son O y queel momento en el claro interior es mayor.
l:.- = 46(12) = 124.89
'r 4.42
Compruébese si la ecuación I.S-6b del AISC [ecuación (4-27)] se puede aplicar:
\~ =' fslO 000(1) = 119 \< 124.9 'T V' 36
Usese la ecuación I.S-6b del AISC [ecuación (4-27)];
170 000(1) .
Fb = 2 = 10.9 kíps/pulg?
124.9
Usese también la ecuación 1.5-7 [ecuación (4-23)] del AISC:

<!-- p. 210 -->

210 DISEÑO DE VIGAS A FLEXION

12 000(1) _ 12 000 _ . 2
Fb = LdlA¡ - 46(12)(1.31) - 16.6 kips/pulg

Usese Fb = 16.6 kips/pulg- (valor mayor):

M
\~ M = SFb lb = S = Fb
204P + 952.2 = 16.6(1110)
P = 172~3.8 = 85.6 kips III

Es fácil comprobar el ejemplo anterior, ya que se había seleccionado el tamaño de la viga y sólo es necesario determinar el esfuerzo permisible de flexión. En
la mayoría de los casos de diseño es más bien un proceso iterativo, pues aunque
se dan las cargas, no se sabe cuál será la sección más económica. A veces se pueden
usar cartillas como las del AISC, que dan el momento permisible para varias longitudes no soportadas, o si no, en forma alternativa, tablas obtenidas de computadoras, como la tabla 11-3 o la VI-3 del SSDD, que dan el momento permisible
para perfiles seleccionados con diversas longitudes sin soporte, Lb' También se
debe observar que si la ecuación (4-23) rige el diseño, el uso de acero A-36 resulta
la solución más económica (el lector debe verificar la veracidad de esta observación).

Ejemplo 4·14 En la figura E4-14 se muestra una trabe carril sin apoyo lateral
en un almacén industrial. Selecciónese la sección W más ligera que limite
también la deflexión a L/360. Se usará acero A-36. Nótese que el trole de la
grúa viaja sobre un riel de ferrocarril de 90 lb sujeto en la parte superior del
patín (90 lb = 90lb/yd = 30 lb/pie).

15k, incl. impacto

Riel de 90 lb

1+--------±--35'--------I-1
Figura E4-14

SOLUCION Hállese el momento máximo. Escríbase una ecuación para M
en términos de x y hágase dM/dx = O.
M = (l5x + 15(x + 6)][L - (x + 6)]
L

<!-- p. 211 -->

DISEÑO DE VIGAS SIN SOPORTE LATERAL 21J

dM - = O = -60x - 270 + 30L x = 13pies del lado izquierdo dx
M = (30 x 13 + ~5(35 - 13 - 6) = 219.4 ft . kips

Estimese aproximadamente el peso de la viga como el 100/0 de la carga:

(0.03 x 35 + 30)(0.1) _ O09 k' / . 35 -. IpS pie

2
bid la vi M d e loa a viga = -8-wL = (0.09 + 0.03)(35f8 =.184'pie : kips

Mtotal = 237 pie· kips

Con una gran longitud sin apoyo del patin a compresión, Lb' se tiene
que estimar de alguna manera la dimensión de la viga. Nótese que de la tabla
JI-3 del SSDD, se han seleccionado secciones con los momentos dados hasta
longitudes de 34 pies de longitud sin apoyo. Como 35 pies es ligeramente mayor, se usará esta tabla como guia para seleccionar las siguientes secciones
tentativas:
wrz x 96: Sx = 131.0 Lu = 39.9 (tabla 11-4para W12)
d WI4 x 90: s; = 143.0 L; = 34 A = 1.36 (tabla 1-3)
f
Wl6 x 100: Sx = 175.0 Lu = 28 dA = 1.65
f
d . W18 x 97: s, = 188.0 t; = 24.1 A = 1.92
f
Pruébese una W14 x 90 y compruébese con la ecuación (1.5-7) del AISC. Se
toma eb = 1.0.

_ 12 000 _ 21 k' / 1 2
Fb · - (35)(12)(1.36) - ip pu g

Correcto

Revisense las deflexiones:

1" = 999.0 pulg-'
Obténganse, de la figura 4-8, las deflexiones que se necesitan para la carga
delantera:

<!-- p. 212 -->

212 DISEÑO DE VIGAS A FLEXION

d = 15(19i(16)2 15(13)(16) (L2 _ 132 _ 162)
carga 3EIL + 6EIL

1 '
\= 3IL (47.80 + 43.03)(1728) = 1.5pulg

L 35(12)
360 = 360 = 1.2 \< 1.5 pulg

Se usará una sección mayor; un cálculo auxiliar indica que una W18 x 97 no
sirve. Pruébese una W16 x 100:
1 = 1490pulg'
R - 12 000 - 7 3 k' / 1 2 b - (35)(12)(1.65) - l. ip pu g
Ma = l7.3\~5.0) = 252pie . kips Correcto
A = 15( 999.0) 5(0.10 + 0.03)(35)41728 = 1 10 12 1 C '-l • 1490.0 + 384E(1490) . \<. pu g orrecto

Se usará una sección W16 x 100 / / /

En estos dos ejemplos se ilustra el método de aplicación de esfuerzos permisibles reducidos a flexión, usando las especificaciones del AISC cuando el patín a
compresión está sin apoyo lateral. El lector debe observar (véase también la Parte
III del SSDD para el AASHTO y el AREA) que las especificaciones de la AASHTO son algo más fáciles de aplicar, porque el esfuerzo de flexión se reduce a partir del valor básico, en función de la relación Lb/bj •

4-11 VIGAS CON PATINES NO PARALELOS

La economía estructural o la apariencia pueden dictar el uso de vigas acarteladas,
como se muestra en la figura 4-12. Según aumenta el peralte de la viga, es evidente que la capacidad de momento aumenta rápidamente. El análisis teórico de este
tipo de vigas es algo complicado y como por lo general no se conocen con precisión las cargas, se usan comúnmente métodos simplificados de análisis. En la figura 4-120 se ilustra un método de análisis para una viga acartelada. Se toma el
eje neutro de tal manera que el ángulo 4>12 sea como se muestra. Examinando con
cuidado la figura, es evidente que el patín inferior (en este caso particular) es menos efectivo, o inversamente el patín sometido a mayores esfuerzos, ya que EPH
\= Oda
e = T cos!.2

<!-- p. 213 -->

VIGAS CON PATINES NO PARALELOS 213

4> 4> 4> Aje = A¡J; cos"2 = A¡ cos"21, cos"2

ó 1, =.fc para áreas iguales de patín (elcaso común)
I cos24>/2
Como un valor de el> = 20° produce un aumento en el esfuerzo de
1, = {c = 1.03.fc cos 100

por lo general no es necesario considerar la pendiente al calcular I, S, etc, ya que
hay mayor incertidumbre en las cargas que en esta discrepancia de aproximadamente 3 por ciento. Es preferible usar una pequeña cantidad de sobrediseño (lb algo menor que Fb) . Los esfuerzos permisibles de flexión del AISC para vigas acarteladas se dan en el Apéndice D del manual del AISC, y no se presentarán en este
lugar.
Se debe tener en cuenta la fuerza vertical que se desarrolla cuando el patín
cambia de dirección, como se ilustra en la figura 4-12b. Esta fuerza aumenta el
cortante del alma, y es común colocar un atiesador en este punto, para tomar la
fuerza vertical (compresión). La fuerza en el atiesador se calcula directamente por
estática como
T¿ = TI sen 4>'

(~Fh = O) TI cos 4>' = To

El atiesador se puede diseñar fácilmente como una columna, tomando en
consideración la relación mínima bit. El AISC no tiene criterios específicos de diseño para estos miembros; por tanto, el diseñador tiene considerable libertad.

\~(AJCOSrf>12
\~'-rf>12

(a) (b)

FIgura 4-12 Análisis de vigas acarteladas.

<!-- p. 214 -->

214 DISEÑO DE VIGAS A FLEXION

4-12 DISEÑO DE LARGUEROS DE PUENTE Y VIGAS DE PISO

En las figuras 4-13 y 4-14 se ilustran los detalles de la colocación de los largueros
de puente y las vigas de piso (también llamadas vigas "transversales"). La carga
muerta que dichos miembros soportan se determina considerándolas como vigas
simples y por la geometría de las cargas muertas. La distribución de las cargas vivas está determinada por las especificaciones de la AASHTü y el AREA.

4-12.1 Criterios de la AASHTO

La distribución de las cargas de las ruedas en puentes de varios carriles está dada
por la AASHTü y se basa en la carga de un camión estándar o carga equivalente
que ocupe un carril de 10 pies de ancho (3.05 m). El ancho de la calzada se toma
como la distancia entre guarniciones. Se supone que los anchos de calzada desde
20 a 24 pies (6.1 a 7.3 m) inclusive tienen dos carriles cargados. Para anchos mayores de la calzada, el número de carriles cargados se puede obtener como

donde L; = 10 pies o 3.05 m
W = Ancho de la calzada (incluyendo cualquier margen para los acota-
mientos)

El número de carriles N es un número entero; por tanto, una fracción de carril se
lleva al siguiente entero. Cuando el número de carriles, N > 2, se permite una reducción en la intensidad de la carga, como se indica a continuación:

N Por ciento de la carga viva

2 100
3 90
4 o más 75

La distribución de las cargas de las ruedas a los largueros (O vigas longitudinales) así como a las vigas transversales de piso, se basa en un articulo de Newmark ("Design of I-Beam Bridges", Transactions, ASeE, Vol. 114, 1949)y viene
dado en términos del valor S del claro dividido entre un coeficiente que aparece
en la tabla 4-1.
El cálculo del cortante y los momentos flectores para los largueros del piso se
basa en un simple análisis de las vigas para determinar la carga crítica (ya sea de
camión o carril). Después de calculados estos valores se han ajustado por impacto, se usan los factores de distribución de la tabla 4-1 para obtener el efecto del diseño sobre cualesquiera de los largueros interiores.
Estos factores tienen en cuenta la continuidad de la cubierta a través de varios
largueros por acción de placa, lo que hace que la carga se distribuya según tienda a

<!-- p. 215 -->

DISEÑO DE LARGUEROS DE PUENTE Y VIGAS DE PISO 215

Puntal lateral superior

Lateral superior

Cuerda superior

Viga de piso

Cuerda inferior

Viga de piso
Viga extrema
de piso

Figura 4·13 Ensamblaje de la armadura de un puente carretero de varios carriles de tablero inferior.
S610 se muestran los miembros principales. Véase también la figura VI·I de una armadura de un
puente de carretera.

(a) (b)

Figura 4-14 Componentes de un puente en servicio. (o) Vista de un puente de carretera de tablero in-
ferior, que muestra los largueros, vigas de piso y otros detalles de contraventeo y estructurales. (b)
Largueros de vigas laminadas para un puente de ferrocarril de tablero superior abierto.

<!-- p. 216 -->

Z16 DISEÑO DE VIGAS A FLEXION

Tabla 4-1 Coeficientes de distribución de las cargas de las ruedas para diseño de
puentes según la AASHTO, los que se usan como S/coeficiente donde S = se-
paración entre largueros (o vigas) ,

Momento flector y cortante (distribución lateral en las I carril 2 o más carriles
vigas interiores de acero") ( ) = Valores SI
Para: piso de concreto 7.0(2.134) 5.5(1.676)
tablero de rejilla de acero \< 4 pulg (102 mm) 4.5(1.372) 4.0(1.219)
tablero de rejilla de acero> 4 pulg (102 mm) 6.0(1.828) 5.0(1.524)
Nota: Para largueros exteriores úsense los principios de
la estática para hallar las cargas efectivas de las ruedas,
que producen la flexión y el cortante (refiérase a la figu-
ra 4-15).
Momento flector en las vigas transversales de piso, sin
largueros:
Con tablero de concreto 6.0(1.828)
Con rejilla de acero =:; 4 pulg (102 mm) 4.5(1.372)
Con rejilla de acero =:; pulg (102 mm) 6.0(1.828)
Flexión en vigas transversales de piso, con largueros:
véase la figura 4-I5.
Momentos flectores en la losa de los tableros de concre-
to (el refuerzo principal es transversal):
S = longitud efectiva del claro = distancia libre de borde de patines + brl2
P¡ = carga de la rueda trasera para H 20, H 15, H 10, etc. (H 20 ó HS 20 = 3212 = 16 kips = 72 kN)
Se debe usar M" = 0.8 M si hay tres o más largueros.
a Los largueros exteriores deben ser cuando menos tan grandes como los largueros interiores, para permi-
tir la futura ampliación del puente.

flexionarse la cubierta. Los cálculos de los cortantes y los momentos flectores de
los largueros exteriores se basan enteramente en la estática y en el análisis simple
de vigas; sin embargo, la AASHTü requiere por lo regular que los largueros exte-
riores sean cuando menos tan grandes como los interiores, previendo una futura
ampliación del puente.
El cálculo del momento flector en la losa del piso es empírico y depende de la
dirección del refuerzo principal (por lo general, transversal), donde las ecuaciones
aplicables de la AASHTü se dan en la tabla 4-1.
El cálculo del cortante y los momentos flectores en las vigas transversales o
del piso a las cuales conectan los largueros (actualmente usan por lo general en los
puentes de armadura) se basa en la figura 4-15, con un camión en cada carril, colocado de tal manera que produzcan ya sea el cortante máximo en un extremo del
carril o elmomento máximo. El análisis se basa en la estática y no se aplica ningún factor de distribución.

4-12.2 Criterios del AREA

La distribución que especifica el AREA para la distribución de la carga de las
ruedas a las vigas transversales en puentes abiertos de tablero superior (véanse

<!-- p. 217 -->

DISEÑO DE LARGUEROS DE PUENTE Y VIGAS DE PISO 217

I~ I~
3.05 -m--+l-o\<..¡.-- 3.05 Camión

,--__ (a)

ro' " T T c C=3.05===r- anuon

(b)
Q-----=Ü_1
l!L6'--!LJ0.61 1.83 0.61
0.8w 0.8w (si HS)

Larguero de piso
Viga'de piso
Figura 4-15 Colocación de las ruedas de un camión para cortante y momentos máximos en las vigas
de piso. Nótese que la carga por carril rara vez rige (si acaso) el diseño de dichos miembros.

las figuras lO-le y 10-4) se basa en el valor total de la carga crítica de eje aplicada.
En el diseño de los durmientes se considera una igual distribución en tres de ellos
pero en no más de 4 pies (1.22 m) para la carga de una rueda.
La porción de la carga de la vía férrea sobre las vigas transversales de los
puentes de tablero con balasto (véanse figuras 1O-4d y 10-5) se puede tomar como
1.15PwD P=--- (4-28)
s
donde Pw = Carga crítica del eje
D = Espaciamiento efectivo de las vigas (D \< s), y que se puede reducir
s = Espaciamiento del eje para la carga crítica, Pw

Se coloca sobre cada riel una mitad de la carga efectiva P, separada la distancia
entre vías. Esta distancia se puede tomar como 4.71 pies (1.346 m). Las especificaciones del AREA proporcionan una complicada expresión para D, que permite
el uso de un valor menor que el espaciamiento real de las vigas. Sin embargo, el
diseñador puede usar D = espaciamiento real para producir un momento de diseño. conservador. Se requiere el espaciamiento real para calcular el cortante de la
viga de piso. Si el espaciamiento de las vigas es D > s, se debe usar directamente
P = PW'

<!-- p. 218 -->

218 DISEÑO DE VIGAS A FLEXION

5.79 m 1:= =:j 2.177----T-I.436T'. 2.177

Balasto.1251.. I Ib/pie3 I Durmiente Via. 1 E
'"r-:N
11
\-...¡

Placa de cubierta
Viga de piso j Vigas de piso
Trabes. véase Ej. 10.5
Figura E4-15

Ejemplo 4·15 Diséñense las vigas de piso para el puente de tablero inferior,
con balasto y trabes armadas del ejemplo 10-5. Se usará acero A-36 y las es-
pecificaciones del AREA. Usese la carga Cooper E-IlO. La geometría gene-
ral del puente se muestra en la figura E4-15. Refiérase a la figura 10-4para la
situación e ilustración de las vigas de piso, en servicio en un puente de ferro-
carril.

SOLUCION

Paso No 1. Determínese la carga muerta sobre la viga de piso.
Para los rieles: 0.200 kip/pie x 14.59 x 0.76 x 2 (Tolerancia del
AREA) = 4.44 kN. Balasto y durmientes: los durmientes son de 8 pies 6 pulg
x 6 pulg, u 8 pulg (ó 7 pulg x 9 pulg) y están embebidos en 6 ó 7 pulg de ba-
lasto con otras 7 pulg de balasto entre el durmiente y la placa inferior. Su-
póngase que no hay desplazamiento y que el balasto tiene un peso unitario de
125 lb/pie', incluyendo hielo, agua, etc. En unidades SI:
125(9.807/62.4)[(7 + 7)/12J(0.3048)(0.76) =5.31 kN/m
Placa de balasto: se incluye un 10 por ciento para proteger
contra la corrosión
0.015(77kN/m3)(0.76)(1.10) = 0.97kN/m
Peso estimado de la viga transversal = 1.50kN/m
Mantenimiento diverso, almacenaje de los durmientes,
materiales = 1.23 kN/m
Total = 9.01 kN/m
El momento por carga muerta es
wL i Md = -S- + la viga
\= 9.0H;.79)2 + 4.44/2(5.~9 - 1.44) = 37.S + 4.S = 42.6 kN . ro

<!-- p. 219 -->

DISEÑO DE LARGUEROS DE PUENTE Y VIGAS DE PISO 219

El cortante por carga muerta es

Vd = 9.01~.79) + 4.~ = 28.3 kN

Paso No 2. Hállese la carga viva sobre la viga. (D = 0.76 m, s = 5 pies
1.524 m)

1.15PwD P = ----:~
S
\= 1.15(110/80)(80 X 4.448)(0.76) = 2806 kN
L524 .
con P/2 colocado sobre cada riel. El cortante por carga viva es

\~w = 28~.6 = 140.5kN

El factor de impacto es
1 = 30.5 + 40 _ 3L 2 donde S = espaciamiento de la
S 150 viga, L = longitud
30.5 40 3(5.79)2 795 . = 0.76 + - 150 = . por Ciento

El cortante de diseño por carga viva es
140.5 x L795 = 252.2 kN
El momento de diseño por carga viva es

M = 280.6(2.177 x L795) = 548 kN . m
L 2

El momento total de diseño es
M diserto= Md + M L = 42.6 + 548 = 591 kN· m

El cortante total de diseño es:
Vdiseño = Vd + VL
\= 28.3 + 252.2 = 280.5 kN
Paso No 3. Hállese la sección de la viga.
El módulo de sección requerido se basa en Fb = 0.55 Fy , ya que el patín
a compresión está lateralmente apoyado.

<!-- p. 220 -->

220 DISEÑO DE VIGAS A FLEXION

_ M _ 591 _ -3 3
S¿ - F - 137.5 - 4.30 x 10 m
b

Se podria usar una sección W760 x 147.3; sin embargo, se escogerá arbitra-
riamente la siguiente sección más económica, W760 x 160.7/1.58:
Sx = 4.8997 X 10- 3 m3 tw = 13.8 > 8.50 mm
t¡ = 19.3mm d = 758 mm

Se notará que el peso es 0.08 kN/m mayor de lo supuesto, pero el módulo de
sección es más que adecuado para tomar esta pequeña diferencia.
Compruébese el cortante:

V 280.5
t: = dt = 0.758(13.8) = 26.8 «0.35Fy Correcto w

(Las conexiones terminales a la viga armada se diseñarán en el ejemplo 8-9).
Se usará una sección laminada W760 x 160.7/1.58 III

4-13 VIGAS COMPUESTAS

Una vigacompuesta es aquella cuya resistencia depende de la interacción mecánica
entre dos o más materiales. Las vigas de concreto reforzado son en realidad vigas
compuestas, pero por lo general no se les considera como tales. Con mucha fre-
cuencia, en la construcción de edificios y puentes, se aplica el término''viga com-
puesta" a una sección de acero sobre la que se ha colado un piso de concreto o
un tablero de puente. El concreto se adhiere con firmeza a la sección de acero por
medio de conectores de cortante cuidadosamente diseñados, de manera que el
concreto y el acero actúen en conjunto como un viga te. En las figuras 4-16 y4-17
se muestran conectores de cortante colocados en posición para unir el concreto a
las vigas a fin de obtener una acción compuesta. Los conectores de cortante
mostrados se llaman pernos de cortante y se sueldan a la viga (y a través del table-
ro en la figura 4-16). Se pueden usar otros tipos de conectores de cortante, pero
los pernos de cortante son los más comunes.
Cuando no exista unión entre la viga de acero y el piso o tablero de concreto,
ocurrirá un deslizamiento relativo en la superficie de contacto entre los dos mate-
riales, y resultará una sección que no es compuesta. En realidad, siempre habrá
un pequeño deslizamiento debido a las deformaciones desiguales en los pernos de
cortante, el concreto y la viga de acero, pero para fines prácticos se puede despre-
ciar este deslizamiento en el diseño compuesto. En la breve introducción al diseño
compuesto que se ha hecho en este lugar se considerará sólo una acción compues-
ta total.
El método de construcción y los códigos de especificaciones constituyen pa-
rámetros de diseño significativos cuando se han de diseñar secciones compuestas.

<!-- p. 221 -->

VIGAS COMPUESTAS 221

\~a) (b)

(e)
Figura 4-16 Construcción compuesta en un edificio. (o) Pernos de cortante colocados en su lugar,
usando la construcción sin apuntalar, y un tablero metálico como cimbra. (b) Vista del tablero metálico con los conductos eléctricos que se empotrarán en el concreto. (e) Vista inferior del tablero metálico
que descansa sobre las vigas y trabes. El tablero metálico se suelda a las vigas de piso por medio de
conectores de cortante.

En la figura 4.18 se ilustra al ancho efectivo b" del concreto que se ha de usar en
una sección transformada usando la relación modular n = EJEc como se encuentra en los varios textos de mecánica de materiales.
La relación modular depende de la resistencia de diseño f~, del concreto a los
28 días, como se muestra en la tabla 4-2.
Los métodos básicos de construcción para producir vigas compuestas son los
dos siguientes:

l. Construcción apunta/oda. Se colocan las vigas de acero en su lugar y se añaden
las cimbras para la losa de concreto. A continuación se apuntala el conjunto
(con contravientos o puntales) de modo que no pueda ocurrir ninguna defle-
xión (o cuando menos en cantidad relativamente pequeña), y se cuela el
concreto. Después que el concreto haya fraguado unos 7 días (obteniéndose
del 70 al 75 por ciento del!:) se quita el apuntalamiento. En este momento, los
esfuerzos en la viga compuesta se deben al peso muerto de la viga de acero más
una parte proporcional del tablero de concreto.
\2. Construcción sin apunta/aro Se colocan las vigas de acero y se proveen las
cimbras (que pueden ser metálicas) para el tablero de concreto (véase la figura
4-17). Se cuela el concreto y en este momento la viga de acero soporta la carga

<!-- p. 222 -->

222 DISEÑO DE VIGAS A FLEXION

tal (b)

te)
Figura 4-17 Tablero compuesto de puente (dos carriles de una carretera interestatal con seis lar-
gueros. (a) El tablero compuesto del puente casi listo para el concreto, con el refuerzo y los pernos de
cortante colocados en su lugar. El acero vertical en los lados es para el refuerzo del parapeto. (b) Vista
de cerca de los pernos de cortante. (e) Vista inferior mostrando los largueros y las cimbras sin apunta-
lar del tablero.
¡--bilf+·--b--__ b' =bln b' =bln '1
t--1 t------I

(al

L = Claro
Usese el menor valor de b:
b=L/I~ b =L/4
b=bf+5/~ b = bf+ 5
AASHTO: b = (5 + bf)l~
b = b¡ + 6t b = bf + 16t AASHTO: b = I ~t

Figura 4-18 Ancho efectivo del patín de secciones compuestas según las especificaciones del AISC y
de la AASHTO, indicando diferencias. (a) Borde. (b) Interior.

<!-- p. 223 -->

VIGAS COMPUESTAS 223

Tabla 4-2 Relación modular para el diseño compuesto según el AISC y la AASHTO, _para diversas resistencias del concreto.

\= wJ.s33(f;)~ Relación modular, n s: Ec
lb/pulg'' MPa - 57(1;)2I ACla AASHTO

2000 13.8 2550 (lb/pulg-) 11 11
2500 17.2 2850 10 10
3000 20.7 3100 9 9
3500 24.1 3400 9 9
4000 27.6 3600 8 8
5000 34.5 4000 7 7
6000 41.4 4400 7 6

a ACI, American Concrete Institute.

muerta del acero, las cimbras (si se usaron), y el concreto. Después que el
concreto fragüe por completo, se quita cualquier tipo de cimbra que se haya
usado. Es evidente, en esta etapa de la construcción, que la viga de acero ha si-
do permanentemente esforzada con el peso de la propia viga más una parte
proporcional del peso del tablero de concreto.

En la figura 4-19 se ilustra el estado cualitativo de los esfuerzos obtenidos al
final de los métodos de construcción apuntalada y sin apuntalar.
Se ha encontrado que la carga última de una viga compuesta apuntalada es
de 2.2 a 2.5 veces la carga de trabajo (véase Progress Report of the Joint ASCEACI Committee on Composite Construction, Journal ofStructural Division ASCE, ST12, diciembre-de 1960)y mayor aún para vigas compuestas sin apuntalar.
Como esto se compara con una relación de carga de aproximadamente 1.7 a 1.8

1- -,

!>ID/S, M¡)S" lb :s;F¡,
Figura 4-19 Diagramas cualitativos de esfuerzos para las vigas compuestas, en que se indica el procedimiento de construcción.

<!-- p. 224 -->

224 DISEÑO DE VIGAS A FLEXION

para las vigas de acero laminado, parece práctico tener un método modificado de
análisis, el que se usa por el AISC. Se define:

Ss = Módulo de sección de la viga de acero referido al patín a tensión
Sfr = Módulo de sección de la viga compuesta referida al patín a tensión

Si se usa un factor de sobresfuerzo de 135 por ciento (1.35 para tener en cuenta el
alto valor de la capacidad última), el esfuerzo en el patín inferior de una viga de
acero compuesta, bajo las condiciones últimas de carga, en términos de los momentos es

Multiplicando toda la ecuación por Sfr y resolviendo, se obtiene la ecuación del
AISC, la que limita al módulo de sección del patín inferior a no más del valor siguiente:

0.35ML ) ·M s, (4-29) Sir = ( 1.35 + D

Cuando el valor calculado de Sfr basado en la sección real sea mayor que el dado
por esta ecuación, se debe usar el valor obtenido de la ecuación (4-29) para calcu-
lar el esfuerzo real de flexión en el patín a tensión de la sección compuesta.
Los esfuerzos a flexión reales en una viga compuesta quedan limitados por el
material. Por lo general, el esfuerzo del acero se limita a Fb = O.66Fy para las sec-
0~6Fy para otras secciones. El esfuerzo del concreto seciones compactas y a Fb =
limita a 0.45/; usando los métodos de esfuerzos de trabajo y a 0.85/; usando los
métodos de diseño por resistencia.
Considerando la figura 4-20, se ve que el cortante desarrollado en el eje
neutro será de compresión o tensión, despreciando al concreto en la zona de tensión. Como es difícil hallar el eje neutro y tener en cuenta los esfuerzos de trabajo, el Alse y la AASHTO permiten calcular el cortante horizontal que ha de ser

1- -1 O.1l5J;
\---- e = O.1l5J: bt

t----., ---... T = .·I,F,

F,.
Figu... 4-20 Distribución de esfuerzos bajo carga última para una viga compuesta.

<!-- p. 225 -->

VIGAS COMPUESTAS 225

resistido en la superficie de contacto del acero y el concreto, como el menor de los
dos valores:

0.85f:(bt)
\-~2-'--';'" (4-30) o Vh =

donde se usa el factor 2 para reducir el cortante último a un valor de trabajo.
Cuando el refuerzo de acero esté en el patín de concreto, usando f~ para el concreto, se debe ajustar la ecuación (4-30), pero se refiere el lector al manual de AISC o
a las especificaciones de la AASHTO.
El número de pernos de cortante depende de la capacidad del perno que según las especificaciones del AISC es como sigue;

Resistencia horizontal del conector ó perno, q, kips (kN)
Tamaño del concepto o perno f~' kip/pulg'' (Mpa)
(diámetro x longitud), pulg (mm) 3.0 (20.7) 4.0(27.6)
! x 2 (12 x SO) S.1 (22.7) S.9(26.2)
\~ x 24 (16 x 6S) 8.0 (3S.6) 9.2 (40.9)
\~ x 3 (20 x 7S) Ii.s (S1.2) 13.3(S9.2)
i x 34 (22 x 90) IS.6(69.4) 18.0 (80.1)

El número de conectores de cortante, según las especificaciones del AISC, no se
basa en VQ/l, como en la soldadura o el atornillado, sino que se basa en

(4-31)

donde Vh = Valor minimo de la fuerza cortante horizontal, de la ecuación (4-30)
q = Capacidad de cortante del perno, tomado de la tabla anterior.

Este cálculo del número de pernos de cortante requeridos supone un espaciamiento uniforme de ellos (en general por pares) desde el punto de cero a máximo momento. Cuando una carga concentrada cae dentro del claro, el número de pernos
de cortante entre la carga y el punto de momento nulo más cercano se calcula de
la manera siguiente:

(4-32)

donde M = Momento en la carga concentrada (Mmáx = momento máximo en el
claro)

<!-- p. 226 -->

226 DISEÑO DE VIGAS A FLEXION
NI = Número de conectores de cortante, obtenido previamente por la
ecuación (4-31)

Se deben consultar las especificaciones apropiadas (AASHTO o AISC) para
el diseño de conectores de cortante en las vigas continuas.
El manual de AISC contiene unas cuantas secciones compuestas para las que
ha proporcionado las propiedades de las mismas, con secciones de acero y espesor
del concreto. El lector puede preparar tablas similares para una selección de secciones de acero, espesor de la losa, y f~, usando una computadora digital.

4-13.1 Requerimientos de la AASHTO para conectores de cortante

Los requerimientos de la AASHTO son muy similares a las especificaciones del
AISC; en los párrafos siguientes se muestran las diferencias. La tolerancia a la fatiga es la principal diferencia y depende del número de ciclos de fatiga que se
pueden esperar. La AASHTO requiere el cálculo del rango del cortante horizontal, basándose en el rango del cortante Vrdebido a las cargas vivas de la envolvente de cortante por cargas vivas, donde

V,=Vmáx-Vrnln
para obtener
s=-, V,Q1

donde Q e 1 son como se usaron en la ecuación (4-2) e 1 es el momento de inercia
basado en la sección compuesta.
La fuerza cortante horizontal permisible F, desarrollada por un conector de
cortante depende del diámetro del conector y del número de ciclos de fatiga que se
pueden esperar (y para una relación Bid del conector ~ 4); es:

Z, = G(d)2 (kips o kN) (4-33)

donde
Número de ciclos = 0.1 x 1()6 0.5 x 106 2 X 106 más de 2 x 1()6

pie-lb-seg: G::::; 13.0 10.6 7.85 5.5
SI: G= 0.0895 0.0731 0.0541 0.0379

Se usará el diámetro del conector den pulg o mm, como en la ecuación (4-33).
El espaciamiento requerido de los conectores, basado en el número n usados
a través del patin (de acero) de la viga será

<!-- p. 227 -->

VIGAS COMPUESTAS 227

n~ ( S· = - 4-34) I Sr

El número total de conectores, NI, debe ser cuando menos igual al que indican las
ecuaciones del AISC ecuaciones [(4-30) y (4-31)].

I
\-,-- 1 I1 I1- 00
1---
00
1---
00
\- 1--
00
,.---
00--1 1 r- 1-t----30'---+t----30·--....¡-1 Figura E4-16a

Ejemplo 4-16 Diséñese la sección de una viga compuesta interior para un
claro de 30 pies en un edificio de oficinas (figura E4-16a) usando una losa de
concreto de 4 pulg y un tablero metálico como cimbra, con vigas de acero es-
paciadas a 10 pies centro a centro. Se supone que no hay restricciones en el
peralte total de la sección. No se requerirá apuntalamiento. Se usará!: = 3
kips/pulg-, acero A-36, y las especificaciones del AISC. Se limita la defle-
xión por carga muerta a 1.5 pulg y la deflexión por carga viva a L/360. Otros
datos:
carga viva = 100 Ib/pie2
Peso de los canceles = 20 lb/pie-
Peso del plafón = 10 lb/pie-

SOLUCION

Paso No. 1. Hállense los momento flectores.

a) Carga muerta soportada por la viga de acero:

Acero, incluyendo el refuerzo, conectores,
tablero metálico = 0.080 kip/pie-
Concreto: 4(1/12)(0.144) = 0.048 kip/pie-
Total = 0.128 kip/pie2

<!-- p. 228 -->

228 DISEÑO DE VIGAS A FLEXION

M = wL2 = 0.128(30)2(8) = 1152 pie- kips
D 8 8 .

b) Cargas vivas soportadas por la sección compuesta:
Carga viva = 0.100 k/pie-
Canceles = 0.020 k/pie-
Plafón = 0.010 k/pie2
Total = 0.130 k/píe-

2
M = wL = 0.130(30f(8) = 117.0pie . kips
L 8 8
V máx = (0.128 + 0.~30)(8 x 30) = 30.96 kips

Paso No. 2. Hállese el módulo de sección requerido, Ss, de la viga de
acero (Fb = 0.66Fy) .

S = M D = 115.2(12) = 576 pulg!
s Fb 24 .
Mínimo S = M D + M L = (115.2 + 117.0)12 = 116 l l 3 Ir F. 24 . pu g
b
Para una deflexión por carga muerta menor de 1.5 pulg, el momento de iner-
cia será cuando menos

4 3
1 = 5wL = 5(0.128 X 8)3\<f12 = 429 l 3
384(E)a 384(29 (00)(1.5) pu g

Después de varios cálculos preliminares (que no se incluyen para ahorrar es-
pacio), se prueba:

88.9pulg~ W18 x 50: I; = 800 pulg'' S; =
d = 17.99(18.0) pulg A = 14.70pulg2
bJ = 7.495(7.5)pulg tw = 0.355 pulg
Paso No. 3. Hállese el ancho del patín de la viga compuesta, b,

L 30(12) b = - = --- = 90 pulg 4 4
S = 8(12) - 7.5 = 88.5 pulg
b = 7.5 + 88.5 = 96 pulg
b = 7.5 + 16(4) = 71.5 pulg controla

<!-- p. 229 -->

VIGAS COMPUESTAS 229

Paso No 4. Calcúlense las propiedades de la sección compuesta (refiérase a
la figura E4-16b).

n = 9 b' = ~ = 7~.5 = 7.9 pulg Mxx = Ay
(7.9 x 4 + 14.70)y = ( ~ + 2)(7.9 x 4)
347.6 Y = 46.3 = 7.51 pulg

Calculada y, se sitúa el eje neutro, como se muestra en la figura E4-16b. Se puede
entonces calcular l, Ssup, y Sinf = s;

2 7.9(4)3 [ 2 lxx = 800 + 14.7(7.51) + -1-2- + 7.9 x 4 2 + (9 - 7.51)]
\= 800 + 829.1 + 42.1 + 384.9
\= 2056.1 pulg"
\= 2056.1 = 3475 l 3 Ssup 5.49 . pu g
2056.1 l 3 Sinf = Str = 16.51 = 124.5pug > 116.1 Correcto

Verifíque el Sfr máximo por la ecuación del AISC:

s; = [ 1.35 + 0.35( z:)]s,
1.35 + 0.35"""li7( 115.2 ) ] 88.9 s; = [
\= 150.6 > 124.5 Se usará 124.5 pulg! Correcto

7.51
x x~

Figura E4-16b

<!-- p. 230 -->

230 DISEÑO DE VIGAS A FLEXION

Paso No. 5. Compruébense los esfuerzos finales.

, _ M D _ 115.2(12) _ 156k' / ul 2 Inicial: lb - - - -. IpS P g s, 88.9

Final: Superior:

fb = 11;4~~2) = 4.04 kips/pulg- (transformada)
I; = 4~ = 0.45 kips/pulg- « 0.45f; Correcto

Inferior:

117.0(12) 113k' / . 2 fb = 124.5 = . IpS puíg

Basado en el AISC

(117+ 115.2)(12) =224k' / / 24 1 Correcto lb'= 124.5 . IpS pu g 2 \<,

El perfil de esfuerzos de la sección, basado en las consideraciones de la mecánica
está trazado en la figura E4-16c, para compararlo con el esfuerzo de 22.4 k/pulgde la sección compuesta según el AISC.

4.04 4.04
15.6
_1_15.6 11.3 --2-6.9 kips/pulg2 > 22.4
Carga muerta Carga viva Total
Figura E4-16c

Paso No. 6. Hállese el número requerido de conectores de cortante:
_ 0.85f;bt _ 0.85(3)(71.5)(4) _ 3646 ki Vh - - - • ps 2 2
AsF.v - 14.7(36) ó V.h----- -.- 264 6 ki ps rige 2 2
Usense conectores de 5/8 con una capacidad de 8 kips/conector; el número
requerido es

<!-- p. 231 -->

VIGAS COMPUESTAS 231

NI = = 26:.6 = 33.07 se usarán 34 conectores :h

Se usarán dos conectores en cada sección, con un espaciamiento de w ='4d
\= 4(5/8) = 2.5 pulg centro a centro. El espaciamiento longitudinal de los
conectores es

30(12) 106 1 6 ( ., ) s = 2(34)/2 = . pu g > D rmrnmo

\<81 (máximo)
Paso No. 7. Compruébese el cortante, actuando simultáneamente las
cargas vivas y muertas.
v = 30.96 kips
• - V _ 30.96 _ 4 9' 1 2 O4F )1) - dl - 18(0.355) - . kip/pu g « . y Correcto
w

Paso No. 8. Verifíquese la deflexión bajo la carga viva. Nótese que la
deflexión causada por la carga muerta se ha eliminado del piso por el flujo
del concreto húmedo durante el colado.
5wL4 5(0.13 X 8)(3\<>4)(123) L
\~ = 384EI = 384(29 (00)(2059.1) = 0.32 pulg \< 360Correcto/ / /

Ejemplo 4-17 Diséñeseuna sección compuesta para un puente de dos carri-
les (dos carriles de 12pies + dos acotamientos de 8 pies y banquetas para los
peatones), como se muestra en la figura E4-17a. Otros datos: carga HS 20;f~
\= 27.6 MPa (concreto clase A de 4 k/pulg2);fy = 415 MPa (acero de refuer-'
zo); acero A-36 para los largueros; especificaciones de la AASHTO; 2 x 1()6
ciclos de carga.

SOLUCION Los dos parapetos y los dos barandales se colocarán después
que se haya colado la loza de tablero. Se supondrá que esta carga la soportan los dos largueros exteriores, que no se diseñan aquí (tampoco se verifica
el larguero interior para ver si es tan adecuado como un larguero exterior, ya
que estos últimos deben ser cuando menos tan grandes como los largueros interiores). Se supone también que se añadirá una superficie de desgaste de
40 mm, cuando se deteriore la superficie inicial.

Paso No. 1. Diseñ.o de la losa de concreto del tablero.
Se elige para las vigas de acero una separación de 2033 mm, como se
muestra en la figura E4-17a. Se estima el ancho del patín del larguero, b¡ =
420 mm (una sección W920), y se calcula el espaciamiento efectivo de los largueros (AASHTO Seco 1-3.2) de las vigas interiores como

<!-- p. 232 -->

232 DISEÑO DE VIGAS A FLEXION

b¡
S = S act - b'J + -2 = 2033 - 210 = 1823mm

La carga muerta de la losa, incluyendo la futura superficie de desgaste, y ba-
sada en D = 230 mm de concreto es
(0.230 + 0.040)(23.6 kN/m3) = 6.37 kPa

Se aumenta un 10 por ciento para basuras en la calzada, nieve, etc.:

6.37 x 1.10 = 7.0 kPa

El momento debido a la carga muerta se calcula como

2 M = wL = 7.0{1.823)2 = 233 kN . m
D 10 10 .

915 915

Parapeto

Cartela de 40 mm
\-------6 (a 2033-------.1 l.

I
I-I----r------ll----+------l--
I I
I I
1 ~ .c:1 -'~----~,'.::::~~... ......-------''---....v~'---.......------
1._~.- ".,:- trarisversales'~J.irW4....
4(" 5550----------

Figura U17a

<!-- p. 233 -->

VIGAS COMPUESTAS 233

El factor de impacto para la losa es (usando L == s == 2.033 m)

15 1 = L + 38 = 0.375 > 0.30 se usa 1 = 0.30

Como siL == 2.033/22.4 == 0.091 es tan pequeño se usará en el diseño de la
losa refuerzo principal en una sola dirección, perpendicular al flujo del tráfico. En este caso y en los cinco claros que aseguran la continuidad de la losa,
el momento por carga viva es

M L = 0.8( s ;.~461 )(P)(l + 1)
\= 0.8( 1.82~.;40.61 )(72)(1.30) = 18.7kN . m

El momento de diseño de la losa de tablero, usando el diseño por resistencia
es
5ML 5(18.7) Mdiseño = MD + -3- = 2.33 + 3 = 33.5 kN . m

Tómese d == D - 40 (permitiendo 25 mm de recubrimiento libre para el refuerzo inferior en los tableros de puente, según el arto 1.6.16 de la
AASHTO):

d = 230 - 40 = 190 mm

El factor de mano de obras, \<1> == 0.90.
Mu = f/>Asfy(d - Í)

AJ~ 415A s
a = 0.85f;b = 0.85(27.6)(1) = 17.69As
A 190 _ 17.69As ) = __3_3_.50__ (o
s • 2 0.9(415)(1&)
A; - 0.02148As = -1.0140 X lO-s

Se resuelve para As completando cuadrados:
As = ±0.0102576 + 0.0107405 - 0.0004829 m2/m
La relación máxima de AsIA c == 0.0214. basada en f~ y /y y tomando el 75
por ciento del valor, para asegurar la fluencia inicial del acero. El porcentaje
real del acero es

<!-- p. 234 -->

234 DISEÑO DE VIGAS A FLEXION

0.0004829
P = 0.19(1) = 0.0025« 0.0214 Correcto

El porcentaje mínimo es
1.383 PJrÚn = = 0.0033 > 0.0025 -r
Se usará As = 0.0033(0.19 x 1.0) = 0.000627 m-zm.

Paso No. 2. Diseño de los largueros de acero.
Nótese que ha sido necesario diseñar la losa de tal modo que se pudiese
calcular la carga muerta soportada por los largueros. Supóngase construc-
ción sin apuntalar -los largueros deben soportar la carga muerta de la losa
de tablero hasta que el concreto fragüe y se endurezca.
Carga muerta de la losa: (0.230 + 0.040)(23.6)(2.032) = 13.00kN/m
Cartela: 0.040(0.42)(23.6) 0.40 kN/m
Vigalaminada supuesta 3.60kN/m
Diversos, incluyendo basura, cimbras, etc. l.ookN/m
TOTAL = 18.00 kN/m

El momento máximo por carga muerta en el centro del claro es

2
M = wL = 18(22.4)2 = 1129kN . m
D 8 8
VD = ~L = 18(~2.4) = 201.6 kN

El momento máximo por carga viva, incluyendo el impacto se basa en la car-
ga de camión de la AASHTO y el espaciamiento de los largueros.

15
1 = 22.4 + 38 = 0.25

• De la sección 1-9, el momento por carga viva debido a la carga total de ca-
mión sobre un claro de esta longitud es

ML == ~ [(0.9L + 1.282)(0.5L + 0.71) - 3.41L](1 + I)
180 .. 22.4 [(0.9(22.4) + 1.282)(0.5(22.4) + 0.71) - 3.41(22.4)](1.25)
\== 1798kN· m
El factor de distribución por carga viva sobre el larguero de un puente con
dos o más carriles se obtiene de la tabla 4-1 como

<!-- p. 235 -->

VIGAS COMPUESTAS 235

S 2.033 Factor =-- =-- = 1 213 ruedas 1.676 1.676 .

Como 1.213 ruedas = 1.21312 = 0.6065 ejes, el momento flector ajustado
del larguero (para la acción de la losa de tablero) es
ML(disello) = 1798(0.6065) = 1090.5 kN . m

El cortante máximo tiene lugar cuando la carga de una de las ruedas traseras
[144 kN (32 kips) por eje] está sobre el extremo de la viga:

L ~5.1 + 0.8) = 180( 22·~2~/·1 + 0.8) = 283 kN v = w(

Este valor debe también ajustarse por acción de placa e impacto:
VL(disello) = 283.0(0.6065)(1.25) = 214.6 kN

Se notará que M D está en el centro del claro del larguero, mientras que M L
está ligeramente fuera de centro. El error de sumar M D + M L es insignificante y conservativo, de manera que se pueden comprobar los esfuerzos en el
centro del claro bajo M D y añadir el efecto combinado de ML (secuencia de
construcción sin apuntalar).

230 - 15 = 215 mm

\~s= 1.613--1 Figura E4-17b

Paso No. 3 Hállense las propiedades de la sección compuesta (refiérase
a la figura E4-17b).
Supóngase que 15 mm del concreto no tienen utilidad para la sección
compuesta debido al desgaste y el deterioro de la superficie. Ignórese el área
de concreto de la cartela.
t' = 230 - 15 = 215 mm
S = 2.033 - bJ = 2.033 - 0.42
\= 1.613 m
b = 2¡4 = 5.6 m

<!-- p. 236 -->

236 DISEÑO DE VIGAS A FLEXION

b = 0.42 + 1.613 = 2.033 m
b = 0.42 + 16t = 3.86 m
Se usará b = 2.033 m: para F; = 27.6 MPa, n = 8.
b' = 2.~33 = 0.254 m

En general, es suficiente seleccionar una viga de acero de un tamaño una
o dos vecesmenor que la requerida para acción no compuesta. La sección re-
querida para la acción no compuesta (soportada lateralmente en el patín) es
aproximadamente
s - M T _ 1129 + 1090.5 _ -3 3
x - 0.55.F;, - 0.55(250) - 16.14 x 10 m

Pruébese tentativamente una W920 x 364.6/3.58:
I; = 6701.3 X 10-6 m" S; = 14.67 X 10-3 m3
d = 916 mm lw = 20.3 mm
tI = 34.3 mm bl = 419 mm
A = 46.52 X 10-3 m2
Compruébese el cortante:

\1. = VT = 201.6 + 283
v dt; 0.916(20.3)
F
\= 26.1 MPa«; Correcto

Compruébese la deflexión por carga muerta

t>. = 5wL4 = 5(0.018 MN/m)(22.4)4
384EI 384(200 (00)(0.0067013)
\= 0.04402 m (44.02 mm)
Tanta deflexión en un claro de 22.4 m se agravarla durante el colado del
concreto para obtener una superficie superior a nivel (necesita 44 mm adi-
cionales de concreto en el centro del claro. Esto requerirá un puntal temporal
a la mitad del claro, o de preferencia hacer que en la fábrica le den al lar-
guero una contraflecha de 44 mm (y asegurarse de que se coloca el lado con
contraflecha hacia arriba al montarlo en la obra, de 10contrario ocurriría un
verdadero desastre). El resto de las propiedades de la viga (peso, b¡, etc.)
caen dentro de las suposiciones, por lo que se puede seguir adelante.
Calcúlese 1 de la sección compuesta (refiérase a la figura E4-17c)

<!-- p. 237 -->

VIGAS COMPUESTAS 237

Ay = ~Mn.a.
A = 46.52 + b'd'
\= 46.52 + 0.254(215) = 101.13 x 10-3m2
916 215) 101.13y = 54.61 ( T + 40 + """2
33 066
y = 101.13 = 327 mm

Figura E4-17c

que da las dimensiones que se muestran en la figura E4-17c.

\~Ad2 Ixx = lo +
\= 6701.3 + 46.52(0.327)2 x loJ + 0.254(0.2;g)3 X 106

\+54.61(0.131 + 0.040 + loJ 0.~15rX
\= 6701.3 + 4974.3 + 210.4 + 4235.7
\= 16 121.7 X 10-6 m"
Los valores de los módulos de sección son como sigue

16 121.7 _ -3 3
Ssup = 131 + 40 + 215 - 41.77 X 10 ro
_ 16 121.7 _ -3 3
Sinf - 458 + 327 - 20.54 X 10 m

Los esfuerzos son:

Inicial:

MD 1129 1, = ft, = S· 14.67 = 77.0 MPa
x

<!-- p. 238 -->

238 DISEÑO DE VIGAS A FLEXION

Final:
M L 1091
1sup= Ssup= 41.77 = 26.1 MPa

fc = 2~.1 = 3.26 MPa « 0.41: Correcto

1091
finf = 20.54 = 53.1 MPa

Los diagramas de esfuerzo de la sección se muestran en la figura E4-17d
Veriñquense los esfuerzos de sobrecarga de lOO por ciento contra los esfuer-
zos permisibles del 150 por ciento:

fc = 2(~~/) = 52.24 MPa
6.5 MPa \< 1.5(0.4)1: Correcto 1conc = 52824 =
2(1091)
1, = 20.54 = 106.2 MPa
También es 1r(total) = 77.0 + 106.2 = 183.2 MPa \< 1.5(O.55F;.) correcto

26.1 MPa 26.1 MPa
r.n-~-r.:-~~-- ---------- ----
'-'-O.~_'_Ys:.:.c~-===----- 77.0 MPa J-L--~85.9

77.0 53.1 1301 \< 0.55 F,.
Figura E4-17d Carga muerta Carga viva

Paso No. 4. Diseño de los conectores de cortante.
Se usarán tres pernos de 20 mm como se muestra en la figura E4-17e,
con L = 150 mm. Por tanto, Lid = 150/20 > 4 es correcto. Los pernos
tienen que resistir el menor de los dos valores siguientes:

0.851:bd'
Vhc = 2 (se desprecia la ménsula)

\= 0.85(27.6)(~033)(0.215) = 5.13 MN

\= 5130 kN controla (después de calcular Vhs)
V = AsF;. = 46.52(250) = 5815 kN
IIs 2 2

<!-- p. 239 -->

VIGAS COMPUESTAS 239

Figura E4-17e

La resistencia última del conector de cortante es
Su = 0.4d2Y f;E E = 4740Vi
\= 0.4(0.020)2(27.6 x 24 9oo)t (ajustes w/SI)
\= 132.6 kN pernos

El número mínimo de pernos requeridos desde el extremo hasta la mitad del
claro (distancia de L = 22.412 = 11.2 m) es

5130
NI = 132.6 = 38.7 se usan 39 (múltiplos de 3)

Con los pernos en grupos de tres, habrá 13grupos. Se establecerá ahora el espaciamiento basándose en la fatiga.
El intervalo máximo del cortante por carga viva es de Oa 214.6 kN.

2 Z, = Gd = 0.0541(20)2 = 21.6 kN
V,Q
S, = "T'
214.6(0.0541)(0.131 + 0.040 + 0.215/2)
\= 0.0161217
\= 200.6 kN/m
«z, 3(21.6)
peso p = Sr = 200.6 = 0.323 m
Para X = 3.5 a partir de los apoyos, el cortante por carga viva más impacto
es (refiérase a la figura E4-17j)
22.4Ra = 10.4(36) + 14.7(144) + 18.9(144) = 5212.8
R = 5212.8 = 2327 kN
a 22.4 .
V = 232.7(0.6065)(1.25) = 176.4kN

<!-- p. 240 -->

240 DISEÑO DE VIGAS A FLEXION

144 144 36 kN
¡.-X -+oo----L- X - 8.5

"Ro Figura E4-17f
Por proporción, ya que Q/I = constante,

214.6 )
p = 0.323( 176.4 = 0.3929 m

Para X = 7 m a partir de los apoyos, el cortante por carga viva más impacto
es
22.4Ra = 4078.8
s; = 182kN
V = 182(0.6065)(1.25) = 138kN
214.6 ) p = 0.323( 138" = 0.5022 mm
\< 0.61, max, espaciamiento permisible. Correcto

Usando el espaciamiento anterior, los primeros 3.44 m requieren 11 grupos
de pernos, los siguientes 3.43 m requieren 9 grupos, y los siguientes 4.33 re-
quieren 9 grupos, con un total de 29 grupos con 3 pernos cada uno, lo que da
un total de 87 pernos vs. los 39 requeridos por consideraciones de cortante
último.
Paso No. 5. Diseño de los diafragmas.
Carga lateral:

Viento a 24 kPa x el área de la superficie expuesta y, refiriéndose a
la figura E4-17a: H = 460 + 225 + 270 + 916 mm = 1.871 m
Carga de la guarnición a 500 lb/pie para el lado opuesto=7.3 kN/m
Viento = 24(1.871) = 44.9kN/m
Total = 52.2 kN/m

Nota: No hay carga de viento del camión debido a que el tablero actúa como diafragma.

Con los diafragmas espaciados a 5.55 m.
Pdiafrag= 52.2(5.55) = 289.7 kN (diafragma interior)
\= 28:.7 = 144.9kN (diafragma exterior)

<!-- p. 241 -->

DISEÑO DE VIGAS USANDO EL FACTOR DE RESISTENCIA DE CARGA (DFRC) 241

Usense diafragmas del mismo tamaño; además, los diafragmas deben ser
cuando menos un tercio y preferiblemente la mitad del peralte de la viga. Se-
lecciónese arbitrariamente
916 W530 x 65.5/0.64: d = 525 mm > 2 Correcto
tw = 8.9 mm > 8.0 mm Correcto
A = 8.39 X 10-3 m2
ry = 32 mm L = 2.033 m
Una verificación como columna (que no se muestra) indica que P = 994 kN
\~ 289.7 kN, de modo que la sección es ampliamente adecuada. Usese la mis-
ma sección para ambos extremos y puntos interiores.
Paso No. 6. Compruébese la deflexión por carga viva.
Conviértase el momento por carga viva en una carga uniforme equiva-
lente como una primera aproximación.

wL 2
\-8- = 1090.5 kN . m

w' = 1090.5~8} = 17.4 kN/m = 0.0174 MN/m
22.4
L\ = 5(0.0174)(22.4t = 0.01769 m
384(200 000)(0.0161217)

Tomando la máxima deflexión permisible como

L 22 400 Correcto 1000 = 1000 = 22.4 mm> 17.6 mm

Si el diseñador supone que el diagrama real de momentos que resulte de la
carga de tres ruedas, se aproxima lo suficiente a un diagrama de carga uni-
forme, la deflexión calculada es adecuada; de otro modo, se debe hacer un
análisis más exacto.
III

4-14 DISEÑO DE VIGAS USANDO EL FACTOR DE
RESISTENCIA DE CARGA (DFRC)

El diseño de una viga sometida a flexión usando el DFRC es relativamente sencillo. Es necesario tener valores separados para las cargas muertas y vivas. El esfuerzo permisible de flexión se toma como

\<p = 0.86

<!-- p. 242 -->

242 .. DISEÑO DE VIGAS A FLEXION

v. = 4>( ~ ) dt " v'3 w
y M; se calcula usando cargas vivas y muertas factorizadas. Esto se ilustra con el
ejemplo siguiente.

Ejemplo 4-18 Se da el sistema de piso mostrado en la figura E4-1S, para un
edificio de oficinas que usa una estructuración simple. Las cargas serán: car-
ga muerta = 75 lb/piel Ycarga viva = SO lb/pie': se usará el diseño DFRC y
el acero A-36.
/1-0-0__ 00' __-1"1 00'__"·1
I I I-r Vigueta
Vigueta ..,'" '" e-tV) e ~ E-

1---1---1- Figura E4-18l Hágase un diseño preliminar con base en un perfil W donde el peralte no
sea un factor restrictivo.

SOLUCION Como la trabe es simétrica en planta y las viguetas se colocan
muy juntas entre si, supóngase que las cargas producirán una carga uniforme
sobre la trabe.

Usando los factores de carga de la sección 3-7 (y la tabla 3-1) y considerando
que no hay reducción por carga viva para el área de piso, puesto que los fac-
tores de carga son de por si términos estadisticos, se obtiene
W" = 1.1[ 1.1(22 X 0.075) + 1.4(22 X O.OSO)]
\= 1.1(1.S15 + 2.464) = 4.71 kips /pie
El momento de diseño es

W"L2 4.71(25)2 36797' ki M u = -S- = S = . pIe· ps
M" = 4>FyZ (4) = 0.S6 de la tabla 3-1)
Z = M" = 367.97(12) = 1426 1 3
4>~ 0.S6 X 36 . pu g

<!-- p. 243 -->

PROBLEMAS 243
Obténgase, de la tabla 11-2 del SSDD, una W21 x 62 con Z = 144.4 pulg-,
d = 20.99 pulg, y t w = 0.400 pulg.
Verifiquese el peso de la viga:
Ilwu = 1.l(1.l)(0.062) = 0.075 kipy pie

Por proporción,

IlZ = IlwuZ = 0.075(142.6) = 2.27 pulg' Correcto
Wu 4.71

Verifiquese el cortante:

\- w.L: - 4.71(25) - 589 k' Vu - -2- - 2 - . lpS
\=$-~ dt = 0.86-(20.99)(0.40% ) = 180.3» 58.9 kips. Correcto V3 w V3
Se usará una sección W21 x 62. III

PROBLEMAS

4-1 Selecciónese la sección W más económica para la viga que se muestra en la figura P4-1. Supóngase apoyo lateral total. Usense las especificaciones del AISC y acero A-36.
Respuesta: W24 x 76

25'

8' 3 5 k pie !

4-2 Selecciónese la sección W más económica para la viga que se muestra en la figura P4-2. Supóngase apoyo lateral total. Usense las especificaciones del AISC y acero A-36.
Respuesta: W610 x 113.1

115 kN

Figura P4-2
4-3 Selecciónese la sección W más económica para la viga que se muestra en la figura P4-3. Usense las
especificaciones del AlSC y supóngase que la viga tiene apoyo lateral adecuado entre A y B, pero entre
B y e tiene apoyo solamente en los extremos. Usense F; = 50 k/pulg",
Respuesta: WI2 x 26. .

<!-- p. 244 -->

244 DISEÑO DE VIGAS A FLEXION

3.2 kips/pie
\~IIIIIIII~

A 1---15' '1- Figura P4-3

4-4 Selecciónese la sección W más económica para la viga de la figura P4-4. Usense las especificaciones del AISC y supóngase que la viga tiene apoyo lateral adecuado entre A y B, pero desde B a e está apoyada sólo en los extremos. Usense Fy = 345 MPa.

50 kN

55 kN/m
\~ I I , I I , ,lEE',,,,I/!#L L
1---6111 .1- 5 '1' 2-1 Figura P4-4

4-5 Una grua de monorriel + trole (figura P4-5) pesa 2050 lb con S = 2.5 pies y tiene una capacidad
de levantamiento de P = 12 kips, Está diseñada para correr a lo largo del patin inferior de un perfil S
estándar. Diséñese la sección si el claro tiene 20 pies, empleando las especificaciones de la AISC. Nótese que se debe empezar con acero A-36 y sólo usar un valor mayor de Fv' si fuese necesario.
Respuesta: S18 x 54.7. .
¡..- Claro = 20' ..
m) ,. d = 2.5' (6.2
0.8111

PerfilS

Figura P4-5 p
4-6 Refiriéndose a la figura P4-5, efectúese el diseño en unidades SI si d = 0.8 m, el trole y la grúa pesen 9.12 kN, la capacidad de levantamiento P = 50 kN, y el claro es de 6.2 m. Usense las especificaciones del AISC y Fy = 250 MPa.
Para los problemas 4-7 a 4-18, refiérase a la figura P4-7.
4-7 Hágase un diseño tentativo para las trabes Al y BI, usando acero A-36. Usense los momentos de
extremos fijos wL2/12 para el extremo interior y wL 2/14 para el extremo exterior. Considérese que Al
soporta el muro con una carga de 0.4 kip/pie (véase problema 4-9).
Respuesta: Wl8 x 65 para BI
4-8 Diséñense las viguetas de piso (vigas) suponiéndolas simplemente apoyadas y usando acero A-36.
4-9 Diséñese la viga de borde AB, suponiendo un recubrimiento de ladrillos con un espesor equivalente al grueso de un ladrillo y un muro que ha de ser soportado por la viga de borde de 8.5 pies. Supóngase que el tablero metálico está soldado al patin de la viga de borde de manera que haya torsión
debido a la excentricidad del ladrillo. Se usará acero A-36.
4-10 Diséñense las vigas de piso que salvan el espacio entre columnas suponiendo apoyos simples y
acero A-36.
4-11 Diséñense las trabes Al y BI usando unidades SI y Fy = 345 MPa. Tómese la carga del muro soportada por Al como 5.90 kN/m. Usese wL2/14 para el momento exterior en el extremo y wL2/12 para el momento interior.
Respuesta: W410 x 59.8 para Al.

<!-- p. 245 -->

PROBLEMAS 145

A B CViga de bordej) E
rI---I---I I---I
Piso
Vigueta
\-0-OJ)
;:M~ - -v Vigueta @; '"
'"
Vi de p iso
':1---1---1 ga I--- I
Vigueta
Detalle de piso N e-tv Vigueta ~ ~... '" ~ ~ 2

\---------4 (", 20 --------~
6.1 m
Otros datos: Piso + acabado + cubierta metálica = 80 lb/pié 3.77 kPa
Col Plafón = 10 Ib/pie2 0.19 kPa
Viguetas (est.) = 3 Ib/pie2 0.07 kPa
Carga viva = 80 Ib/pie2 4.0 kPa

Se pueden usar las reducciones de carga viva que sean apropiadas
Detalle de viga de borde Usense los momentos de empotramiento = wL2/IO, exterior; wL2/12, interior
Limitense las def1exiones aproximadas a L/360
Figura P4-7 Limítese d a 18 pulg a 460 mm (peralte nominal)

4-12 Diséñense las viguetas de piso (vigas) suponiéndolas simplemente apoyadas y con un valor de F y
\= 345 Mpa.
4-13 Diséñese la viga de borde AB, suponiendo un recubrimiento de ladrillos con un espesor equivalente a un ladrillo y un muro que ha de ser soportado por la viga de 2.60 m. Supóngase que el tablero
metálico está soldado al patín de la viga de borde de modo que no haya torsión debido a la excentricidad del ladrillo. Se usará Fy = 345 MPa.
Respuesta: W410 x 46-1.
4-14 Diséñense las vigas de piso que salvan el espacio entre columnas suponiendo apoyos simples y Fy
\= 345 MPa.
Respuesta: W410 x 46.1
4-15 Resuélvase el problema 4-8 suponiendo construcción compuesta sin apuntalar. Usense f~
3000 lb/pulg/.
4·16 Resuélvase el problema 4-12 usando construcción compuesta sin apuntalar, pero usando Fy =
250 MPa (en lugar de Fy = 345 MPa para el acero; ¿por qué?) Usesefc' = 21 MPa.
4-17 Rehágase el ejemplo 4-16 usando construcción apuntalada en lugar de la construcción "sin
apuntalar" que se usa en el ejemplo.
4-18 Rehágase el ejemplo 4-16 usando una sección WI8 x 46 y véase si es posible obtener una solución práctica.

<!-- p. 246 -->

246 DISEÑO DE VIGAS A FLEXION

28'
f---------- 8536 "'n:-::IO=-1-------

·1

36-46'
11000 14000 mm

Figura P4·19

Para los problemas 4-19 a 4-22 consúltese la sección transversal mostrada en la figura P4-19. El
instructor fijará el claro del puente (36 a 46 pies u 11 a 14 m). En el caso que no la fijara, se usarán 40
pies o 12.5 m para el claro. Para las vigas exteriores, la máxima carga posible debido al camión será la
mitad de la carga de camión. La carga muerta está constituida por la parte en voladizo más la parte
prorrateada de la losa de tablero hasta el larguero interior adyacente. Usese un camión HS 20 y acero
A-36 ó I; = 250.
4-19 Diséñense los largueros de piso considerando que se tiene apoyo lateral total para los patines a
compresión, y usando acero A-36. Usense las especificaciones de la AASHTO.
Respuesta: W33 x 130.
4·20 Diséñense los largueros de piso, teniendo en cuenta que se tiene apoyo lateral total para los patines a compresión, y usando acero con Fy = 250 MPa. Usense las especificaciones de la AASHTO.

160k
\-----....... l, 6.70111 r> 790 kN
.:
39.5' ----------tJ~
13.3 m

Figura P4-23

<!-- p. 247 -->

PROBLEMAS 247

4·21 Diséñense los largueros interiores de piso de la figura P4-19, usando diseño compuesto y cons-
trucción sin apuntalar. Limítese la deflexión bajo carga viva a L/800. Usese j'; = 4 kip/pulgé,
4-22. Diséñense los largueros interiores de piso de la figura P4-19 usando diseño compuesto y cons-
trucción sin apuntalar. Limítense las deñexiones por carga viva a L/800. Usesef/ = 28 MPa.
A continuación se presentan diversos problemas de vigas para claros sin apoyo lateral y para con-
sideraciones de cortante.
4-23 Una carga de columna de 160 kips está soportada sobre un área abierta de trabajo como la de la
figura P4-23. La longitud lateral no soportada es de 39.5 pies. Elijase el perfil W más ligero, con la
deflexión limitada a L/360. Se usará cualquier grado de acero si el A-36 no fuese adecuado. Nótese
que es necesario asumir las condiciones de fijación.
Respuesta: W36 x 300 (Simplemente apoyada).
4-24 Rehágase el problema 4-23, con P = 790 kN y las dimensiones métricas mostradas en la figura
P4-23.
4-25 Si la carga de columna del problema 4-23 está soportada por una sección W8 x 48, ¿qué longi-
tud de la distancia N de apoyo de la figura 4-6 se requerirá para la viga seleccionada en el problema
4-23?
Respuesta: N = 8. 50 pulg .
4-26 Si la viga seleccionada en el problema 4-24 soporta la carga de columna de 790 kN transmitida
por una sección de columna de W200 x 86.3, ¿qué longitud de N de la figura 4-6 se requerirá?
Respuesta: N = 222 mm
4·27 Una sección W se ha de usar en un claro de 10 pies para transmitir una carga concentrada de
650 kips que actúa a la mitad del claro. Selecciónese la sección, verifíquese el esfuerzo cortante, y calcúlense los valores N, tanto para la reacción como para la carga concentrada, usando acero A-36 y las
especificaciones del AISC.
4-28 Una sección W se ha de usar en un claro de 3.5 m para soportar una carga concentrada de
2100 kN que actúa a la mitad del claro. Selecciónese la sección, verifíquese el esfuerzo cortante, y calcúlense los valores N, tanto para la reacción como para la carga concentrada, usando para el acero Fy
\= 250 MPa y las especificaciones del AISC.
Respuesta: W840 x 299.1, N = 260 mm para la reacción.
4·29 Rehágase el ejemplo 4-18, si \<f> = 0.90 YFL e = 1.5.
4-30 Rehágase el ejemplo 4-18, si Fy = 50 kip/pulgé
Respuesta: W21 x 50.
4·31 Rehágase el Ejemplo 4-18, si D = 3.75 kPa, L = 4.0 kPa, L = 7.75 m (claro), y la longitud de la
vigueta = 6.75 m. Usese Fy = 250 MPa y el LRFD con los factores sugeridos en la sección 3-7.
Respuesta: W530 x 92.3.
4-32 Rehágase el ejemplo 4-10 para la sección más ligera, W o M.
Respuesta: WIO x 22 o MIO x 22.9.
4-33 Diséñense los largueros de techo del problema 5-20 (en el capítulo siguiente) usando la sección laminada más ligera, W o e, con un tirante a la mitad del claro. Se usarán las especificaciones del AISC
y acero A-36.
Respuesta: WI4 x 43
4-34 Obténgase la sección W más ligera para una viga con 45 pies de claro con dos cargas concentradas de 20 kips cada una, actuando a 15 pies de cada extremo. Se tiene apoyo lateral sólo en los extremos y en las cargas concentradas. Se usará acero A-36 y las especificaciones del AISC.
Respuesta: W27 x 84
4-35 Obténgase la sección W más ligera para una carga uniforme de 30 kips/pie que actúa sobre un
claro de 15 pies. Hállese también la distancia N de la reacción. Se usará acero A-36 y las especificaciones del AISC.

<!-- p. 248 -->

b)
Figura V-l. Miembros a tensión. (a) Miembro a tensión en un edificio industrial usando tornillos de
alta resistencia. (b) Miembro a tensión en un pequeño edificio industrial, para contraviento. Se puede
ver un tornillo de montaje en el miembro inferior. La junta es soldada.

<!-- p. 249 -->

CAPITULO
CINCO
DISEÑO DE ,MIEMBROS A TENSION

5-1 TIPOS DE MIEMBROS A TENSION

Los elementos de una estructura que soportan cargas a tensión se llaman
miembros a tensión. Ejemplos clásicos de miembros a tensión son las cuerdas inferiores de las armaduras de techos y puentes. Algunos de los miembros del alma
de las armaduras pueden soportar tensión o pueden ser miembros a tensión para
ciertas condiciones de carga, y miembros a compresión para otras condiciones de
carga.
Los cables de acero usados en los puentes colgantes y en los techos soportados por cables son ejemplos de miembros de acero sometidos a tensión. Se usan
también los cables para atirantar las altas torres de acero en las comunicaciones,
así como los postes de las líneas de fuerza, en los lugares en donde ocurran cambios de alineación.
Se usan con frecuencia los contraventeos de configuración X, en los lugares
donde los miembros son tan flexibles que tiene lugar "el pandeo" bajo esfuerzos
de compresión desarrollados por el viento que sopla en una dirección, pero que
funciona como un miembro a tensión para el viento que sopla en dirección opuesta. Otros casos en que se usan los miembros a tensión incluyen miembros especiales del alma de las torres de fuerza y comunicaciones, suspensores en los pozos
de las escaleras, los cables de los elevadores, suspensores para los muros de cortina, y partes de los equipos de izado.

249

<!-- p. 250 -->

250 DISEÑO DE MIEMBROS A TENSION

Barra redonda

Barra cuadrada

\~ Barra plana o placa

00: Un solo angular l I I I 1---
Conexión de placa ci2.-Q Conexión con angular auxiliar

I Perfil S 1 :=1t:=:=:==========Conexión de placa
Perfil W X
o O Canal O O [ I
(a)

tb¡

\~~ () C=e
\~~:_~.~=.~iI==.t¡g(~
(e)

Figura S·) Miembros a tensión. Véase la figura 5-2 para cables usados como miembros a tensión. (al
Perfiles estructurales usados como miembros a tensión. (bl Barra con rosca sobrepuesta. (el Barra
roscada y uso de un templador para ajustar la longitud de la barra. Aplicable a barras cuadradas y redondas.

<!-- p. 251 -->

ESFUERZOS PERMISIBLES A TENSION 251

Se usan los tensores de acero de alta resistencia para reforzar las estructuras
existentes, fijando dichos tirantes al patín o cuerda inferior de la estructura y aplicando pretensión para inducir un esfuerzo de compresión en el miembro, esfuerzo que debe ser superado cuando se aplique una carga. A vecesse usan los tirantes
entre las reacciones de un arco o de un marco rígido para ayudar a resistir el coceo
en la base.
Los cables se utilizan ampliamente en la construcción de techos soportados
por cables, a fin de producir un techo estéticamente agradable, sobre un área
grande de piso que esté libre de obstáculos, y con una cantidad mínima de acero y
de cualquier otro material estructural que se requiera.
Para todos estos usos se utiliza la resistencia a tensión del acero. En esta configuración del esfuerzo no se considera el pandeo o el alabeo de las placas. Sin
embargo, en algunos casos, las especificaciones requerirán una cantidad mínima
de rigidez en el miembro, por razones estéticas y de seguridad.
En general, los miembros a tensión se pueden clasificar como varillas y
barras, perfiles estructurales, miembros armados, y alambres o cables. Varios de
estos miembros se ilustran en las figuras 5-1 y siguientes.

5-2 ESFUERZOS PERMISIBLES A TENSION

Según el AISC, el esfuerzo permisible a tensión, excepto para las barras de ojo, se
limita a

F, = 0.6F;, i (área de la sección bruta)
F, = 0.5Fu (área de la sección neta) (5-1)

El esfuerzo permisible a tensión, según la AASHTü y el A~EA, es algo más conservador, con

F, = 0.55Fy (5-2)

La especificación de la AASHTü limita aún más este esfuerzo básico al valor menor de la ecuación (5-2), o si no

pero se usa la sección neta para ambas ecuaciones. Para el acero con Fy no mayor
de 80 kip/pulg-, el esfuerzo básico de tensión está regido por la ecuación 5-2, para
el diseño según la AASHTü.
Para la sección neta a través del agujero del pasador de una barra de ojo (véase figura 5-3), el esfuerzo permisible según el AISC es

F, = 0.45Fy (5-3)

<!-- p. 252 -->

252 DISEÑO DE MIEMBROS A TENSION

Templador con
horquilla terminal Casquillocerrado

11 11111 111111

Cable Varillade anclaje (alambreo torón)
(a) ( h)

Casquilloabierto

Barra de ojo extremo Cable
Inserto roscado (alambreo torón)

(e) (d)

Cable Concreto
(alambreo torón) estructural

Casquillode anclaje

. Anclajeestructural Casquillode anclaje

Cable Cable
(alambreo torón) (alambreo torón)

Casquilloabierto

Miembros
estructurales

Casquillode anclaje

(e)

Figura5~2 Cables como miembros a tensión y sus accesorios para fijación. Nótese que en muchas de
estas situaciones se puede usar una barra cuadrada o redonda. (a) Horquilla roscada con pasador. (b)
Casquillo para cable con templador. (e) Método para usar un casquillo para cables con el anclaje
estructural. (d) Detalles de un casquillo. (e) Tres situaciones en las que se usan cables para un miembro
a tensión.

<!-- p. 253 -->

ESFUERZOS PERMISIBLES A TENSION 253

Tabla 5·1 Esfuerzos permisibles de tensión para las especificaciones y
ecuaciones que se muestran

AISC AASHTO y AREA
No en los agujeros
de los pasadores' En los agujeros
Sección neta de los
pasadores b Sección neta
F y Fu 0.6Fy 0.45 r, O. 5F u 0.55Fy O. 46Fu
Ksi Mpa Ksi MPa Ksi MPa Ksi MPa Ksi MPa Ksi MPa Ksi MPa
36 250 58 400 22.0 150 16.2 112 29 200 20 138 26.7 184
42 290 63c 435 25.2 174 18.9 130 31.5 218 23.1 160 29.0 200
46 315 67c 460 27.6 189 20.7 142 33.5 230 25.3 173 30.8 212
50 345 70c 485 30.0 207 22.5 155 35.0 242 27.5 190 32.2 223
60 415 75d 520 36.0 216 27.0 187 37.5 260 33.0 198 34.5 239
65 450 80d 550 39.0 270 29.3 202 40.0 275 35.8 248 36.8 253
a En la sección bruta, no en los agujeros de los pasadores.
b En la sección bruta, en los agujeros de los pasadores.
e Fu varía con la designación de la ASTM; los valores mostrados son para el Acero A-588.
d Para el acero A-572.

En la tabla 5-1 se muestran los esfuerzos permisibles a tensión para varios
grados de acero; el lector debe observar que la práctica establecida permite redondear los valores para el acero A-36 a los valores que se muestran tanto para el
AISC como para el AASHTO/AREA.
En todos los casos, excepto en las barras de ojo, los esfuerzos a tensión se deben calcular con base en las áreas de sección transversal, brutas y netas, cuando se
usen las especificaciones del AISC. Sólo se requiere el área neta para las especificaciones de la AASHTO y el AREA. El área neta es igual al área bruta (total)
cuando se usen conexiones soldadas. El área neta será el área transversal menos
efectiva para todos los otros casos, como cuando se usan agujeros para tornillos o
remaches como sujetadores mecánicos en los extremos, o cuando ocurren huecos
y/o reducciones en el área, a lo largo del miembro.
El área neta efectiva aproximadamente en el fondo de la rosca de los
miembros roscados a tensión, usando la especificación del AISC es.

(5-4)

donde D = Diámetro nominal externo de los filetes
n = número de filetes/pulg (o el equivalente SI de nI25.4)

La raíz de la rosca será el área crítica para las barras normales roscadas y que produce efectivamente un considerable desperdicio de material. Esto se puede evitar
con el uso de las roscas sobrepuestas (figura 5-lb), donde los extremos roscados
se forjan a un diámetro mayor antes de hacer la rosca, de tal modo que la aplica-

<!-- p. 254 -->

254 OISEJ'lO DE MIEMBROS A TENSION

UJA"~A." 15~. , .~

I 1"
r::::05"(12.5mml D;Dpln + j2
'------:------'--~

Figura 5-3 Dimensiones de una barra de ojo, según el AlSC.

\~ Abarra• Sin embargo, no es total el ahorro,ción de la ecuación (5-4) produce A e
ya que hay un cargo extra de fabricación por producir una rosca sobrepuesta.

S-3 CONSIDERACIONES GENERALES DE DISEÑO

Para diseñar miembros a tensión se deben considerar varios factores, que incluyen conexiones, tipos de perfiles disponibles o que se requieren, yel flujo del cortante. Estos factores se tratan en las siguientes secciones.

S-3.1 Conexiones

Entre los factores principales está la manera como afectará una conexión del
miembro a tensión al resto del sistema estructural (esto es, a otros miembros o a
la cimentación). En las figuras 5-1,5-2, y 5-4, se presentan varios tipos de conexiones
de los miembros a tensión. La conexión más simple es la de la barra de ojo conectada por un pasador, pero ya se ha comprobado que este tipo presta servicios poco satisfactorios, y requiere especial cuidado en su dimensionamiento; se muestra
en la figura 5-3. El siguiente tipo más simple sería algún tipo de barra roscada o
cable. Aquí se originan varios problemas, que incluyen el área a tensión de la
barra, ecuación (5-4) y ajustar el miembro a la estructura. El problema por lo general se resuelve con el uso de un templador, o teniendo una distancia roscada

<!-- p. 255 -->

CONSIDERACIONES GENERALES DE DISEÑO 255

extra en un extremo para tomar la flojedad. Las barras y cables que se usan como
miembros a tensión reciben por lo regular una pequeña tensión inicial al instalarlos, para eliminar cualquier colgamiento y para evitar el traqueteo cuando la
estructura vibra bajo las cargas de servicio. La tensión inicial a menudo resulta
provechosa para "ajustar" el resto de la estructura.
Los cables pueden estar formados por hilos de alambre, con los términos
"alambre de puente", o "cable de puente" para especificar la calidad estructural
de los cables. No se usan alambres sencillos en las aplicaciones estructurales; más
bien, se envuelven cables individuales alrededor de un núcleo central de alambre,
para producir una sección simétrica. Estos cables son conjuntos de 7 a 61 o más
torones individuales. El cable se produce enrollando varios cables individuales en
forma helicoidal alrededor de un núcleo de alambre. Comúnmente los cables consisten de 6 a 37 torones; en la tabla 5-2 se dan los datos de diseño para una selección de cables para puentes y cables para otros usos.
Las conexiones de los cables toman por lo común la forma de una de las configuraciones que se ilustran en la figura 5-2. En dichas conexiones, se limpia con
cuidado el extremo del cable y luego se pasa por la abertura del conector. Los
extremos del cable, algo separados, se limpian cuidadosamente, y se vierte luego
r---- Roldanas
o placas de ----]
relleno 1L' H-~~MW~ I Celosia
I I
Placa de Remaches L' conexión en de punto -t
el extremo
Placa de Placa de conexión J relleno

Placas de
conexión conexión -~1lJ

(al (bl (el (d)

Figura 5-4 Conexiones de los miembros a tensión. (o) Las dimensiones del alma del miembro contro-
lan el espaciamiento de los canales en las cuerdas. (b) Uso de las placas de relleno para hacer cone-
xiones. (e) Conexiones entre dos miembros armados usando placas de conexión. (el) Par de angulares
con placa de conexión. Se requieren por lo general remaches (o tornillos) para mantener la L' /r, entre
los tornillos :S LIrm del miembro completo. Nótese la necesidad de usar el rz del elemento para calcu-
lar la L' / r entre tornillos.

<!-- p. 256 -->

256 DISEÑO DE MIEMBROS A TENSION

Tabla 5-2 Selección de datos para el diseño de cables
Diámetro Peso Area Pu
pulg mm libra/pie kN/m pulg1 m1 (x 10-3) kips kN

Cables para puentes (un solo cable con múltiples alambres)

112 13 0.52 0.008 0.15 0.0968 29.0 129
5/8 16 0.82 0.012 0.234 0.1510 46.6 207
11116 18 0.99 0.014 0.284 0.1832 56.2 250
3/4 19 1.18 0.017 0.338 0.2181 66.0 294
7/8 22 1.61 0.023 0.459 0.2961 89.2 397
I 25 2.10 0.031 0.600 0.3871 1I8.4 527
I 1/8 28 2.66 0.039 0.759 0.4897 151.4 673
I 114 32 3.28 0.048 0.938 0.6052 188.2 837
I 3/8 35 3.97 0.058 1.130 0.7290 228.0 1014
I 112 38 4.73 0.069 1.350 0.8710 270.0 1201
I 5/8 41 5.55 0.081 1.59 1.0258 318.0 1414
I 3/4 44 6.43 0.094 1.84 1.1871 368.0 1637
I 7/8 48 7.39 0.108 2.1I 1.3613 424.0 1886
2 50 8.40 0.123 2.40 1.5484 482.0 2144
2112 64 12.8 0.187 3.75 2.4194 740.0 3292
4 100 33.6 0.490 9.60 6.1935 1822.0 8105

Torones para puentes [6 x 7 (cables de 7 alambres/cable)]

3/8 10 0.24 0.004 0.065 0.0419 13.0 58
112 13 0.42 0.006 0.1I9 0.0768 23.0 102 .
5/8 16 0.65 0.009 0.182 0.1l74 36.0 160
3/4 19 0.95 0.014 0.268 0.1729 52.0 231
7/8 22 1.28 0.019 0.361 0.2329 70.0 31I
I 25 1.67 0.024 0.471 0.3039 91.4 407

Torones para puentes [6 x 19 (6 cables de 19 alambres/cable)]

13/4 44 5.24 0.076 1.47 0.9484 286.0 1272
2 50 6.85 0.100 1.92 1.2387 372.0 1655
2112 64 10.60 0.155 2.97 1.9161 576.0 2562

Torones para puentes [6 x 37 (6 cables de 19 alambres/cable)]

3 75 15.1 0.220 4.25 2.7419 824.0 3665
3 1/2 90 21.0 0.306 5.83 3.7613 1110.0 4938
4 100 27.0 0.394 7.56 4.8774 1460.0 6494

cinc fundido a aproximadamente 8500 F dentro de la matriz de alambres. Después que se enfría el cinc, y se haya vuelto a limpiar la conexión y montar, el
miembro está listo para su instalación. Este método de fijar los conectores extremos produce una junta que es, cuando menos, tan resistente como el cable. A veces (pero no se muestra en este lugar), se puede insertar el cable en un conector
más largo, el que se aprieta para producir una conexión a fricción.

<!-- p. 257 -->

CONSIDERACIONES GENERALES DE DISEÑO 257

Se necesita conocer el módulo de elasticidad de los alambres y torones, para
el cálculo de la elongación bajo el esfuerzo. El módulo de elasticidad de los torones de alambre no es el mismo que el del acero básico de alta resistencia usado en
la manufactura de los hilos individuales. El módulo 'de elasticidad se determina
después de formar los hilos o torones y estirarlo a fin de que las partes componentes se ajusten entre sí.
El módulo de elasticidad de los hilos y torones de puentes, se pueden tomar
como sigue:

Diámetro o clase
Cable de puente (diámetro) E
Pie.Ib.seg, pulg SI, mm pie > lb • seg SI, MPa
kip/pulg2
Y2 a 2 9/16 12.5 a 65 24000 165000
2 5/8 67 (y mayor) 23000 158000
Torón para puentes (clase)
6 x 7 (6 cables con 7 alambres/cable) 20000 138000
6 x 19 (6 cables con 19 alambres/cable) 20000 138000
6 x 37 (6 cables con 37 alambres/cable) 20000 138000

Se usa acero estructural de alta resistencia (Fy del orden de 160 kip/pulg-) en la
fabricación de hilos y torones para puentes. El fabricante garantiza la resistencia
de ruptura (Pu dada en la tabla 5-2), pero es el diseñador el que ha de especificar
el factor de seguridad. El FS no debe ser menor de 1.7, y puede ser tan alto como
3.0, dependiendo de las incertidumbres del proyecto y del diseño.

5-3.2 Flujo del cortante y áreas efectivas máximas de sección transversal

En la figura 5-5 se ilustra cualitativamente el problema del flujo de cortante o el
rezago del mismo según se transfiere la carga a las placas de conexión partiendo
del miembro principal. El problema resulta aún más crítico cuando se usan angulares individuales y sólo uno está conectado para transferir la carga. En este caso
a veces se utilizan angulares de conexión (figura 5-10). Las especificaciones del
AISC (sección 1-14.2) consideran este problema de la manera siguiente.
En cualesquiera de los casos donde los miembros a tensión tengan un perfil
en que no todos los segmentos estén en un plano común (como el lado saliente de
un angular, el alma de las vigas con conexiones en los patines, los patines de los
canales cuando se conectan al alma, y de manera similar para miembros compuestos) se calculará el área efectiva A e de la manera siguiente:

\1. Angulares de lados iguales o desi~uales conectados por un lado a una placa
(solos o por pares). A e = 0.9ºA"..·
\~ O.67d, o tes estructurales cortadas de estos2. Para perfiles W, M, o S, con bJ
perfiles, y conectados sólo por el patín, A e = O.90An•

<!-- p. 258 -->

258 DISEÑO DE MIEMBROS A TENSION

4 3 2
P I I I I Miembro a tensión..~ "2Placas de co ne~ón,\< ~ . P ~
P
2 P/A
o=f(P') 0= f(P")
L' -1

En el punto 1: Se supone distribución uniforme del esfuerzo en el análisis.
2: Parte de la carga se transfiere a las placas de empalme, dejando
P'. La transferencia de carga es en patines, lo que resulta en
esfuerzos cualitativos en la sección mostrada. Los esfuerzos
interiores del alma serán mas bajos que P/ A, debido al retardo
del cortante. Así, en las juntas largas, el alma se puede rasgar
debido a grandes deformaciones diferenciales en un fallo
progresivo a tensión en el extremo delantero de la junta.
3: Carga adicional transferida a las placas de empalme, dejando P .
4: Toda la carga se transfiere a las placas. de asiento. y los esfuerzos
en el miembro a tensión son cero.

Fi2ura 5-5 Flujo del cortante en la junta de un miembro a tensión durante la
transferencia de carga a las placas de conexión.

\3. Para todos los otros perfiles, incluyendo los perfiles armados, con cuando me-
nos tres sujetadores en una línea (la figura 5-5 tiene cinco sujetadores en
línea), A e = 0.85A n•
\4. Cualesquiera miembros a tensión con solamente dos sujetadores en una línea,
A e = 0.75An•

Se nota que el área efectiva A e es siempre menor que el área neta cuando se ha de
considerar el rezago del cortante.
Pruebas efectuadas en gran número de conexiones a tensión han demostrado
que las conexiones soldadas pueden estar cerca de un 100 por ciento de eficiencia
(A e - A n). No se encontró ninguna conexión que usara sujetadores mecánicos y
que estuviera muy por encima del 90 por ciento de eficiencia, así que, para suministrar un tratamiento estadístico adecuado de las pruebas, las especificaciones
del AISC limitan la eficiencia de cualquier conexión que use sujetadores mecánicos a un área neta máxima para una sección transversal de

(5-5)

Con conexiones soldadas sin agujeros, el área neta A n es igual a la sección totalo bruta Ago El autor sugiere que se use

para los miembros a tensión que sean continuos en la junta, para calcular el área
efectiva a tensión de angulares dobles, canales y tes estructurales usados como
cuerdas inferiores de las armaduras, y que sean continuos a lo largo de varios paneles. .

<!-- p. 259 -->

CONSIDERACIONEC GENERALES DE DISEÑO 259

5·3.3 Uso de perfiles estructurales como miembros a tensión

El uso de un perfil en particular, laminado o armado, estará dictado por el resto
de la estructura y, por supuesto, la carga axial que se ha de resistir. Cuando el
miembro se conecta a una junta que tenga suficiente ancho, puede que sea deseable el uso de los perfiles W, M, o C, como se ilustra en la figura 5-4. La longitud
de la junta, L' debe ser suficiente de tal modo que el esfuerzo a tensión en la sección transversal total se pueda transferir a la junta vía el "flujo de cortante", como se ilustra cualitativamente en la figura 5-5.
Más generalmente, los miembros a tensión son o bien angulares solos o, preferiblemente, dobles, como se muestra en la figura 5-6. Se prefiere por lo regular
el uso de angulares dobles, porque la junta será más simétrica tanto en el plano
como fuera de él, en oposición al uso de un solo angular, que siempre tendrá excentricidad fuera del plano. El lector debe notar la relativa facilidad en la fabricación de juntas usando angulares sobre el alma de la viga WT, que se muestra en la
figura 5-6a, y el uso de una sola placa de conexión en oposición a la conexión de
la figura 5-4. Para obviar en parte esta situación se recomienda el uso de placas

n--l
1\ I
1I 1
11 1
11 I
l' I
11 I
\ 1
I 1
u__J1 1

(e)

Placade conexión

Id) ( e)

Figura 5-6 Juntas para miembros a tensión (y compresión), cuando las cargas axiales son pequeñas,
como en las armaduras de techo de los edificios industriales o torres de transmisión. (a) Angulares
sencillos o dobles con tornillos o remaches. (b) Angular sencillo soldado. (e) Canal soldado o atornillado. (d) Sección T con angulares sencillos o dobles. (e) Cuerda con doble angular con placa de conexión y miembros verticales y diagonales a base de angulares sencillos o dobles.

<!-- p. 260 -->

260 DISEÑO DE MIEMBROS A TENSION

Celosía Celosíar--,I I [Jp~
L_~

(a) (b) (e)

Celosía

(d) (e) 1__1 D

(f)

Figura 5-7 Sección transversal de varias secciones armadas. La configuración general de la sección
transversal está limitada solamente por las necesidades e inventiva del diseñador, y puede incluir perfiles W y S con celosia y/o placas. Cuando se necesite mayor área, se pueden añadir más placas a las
arriba mostradas. (o) Cuatro angulares con celosia. (b) Cuatro angulares con placas y celosía. (e) Dos
angulares y una o dos placas. (el) Dos canales con celosía. (e) Dos canales con los patines invertidos
con respecto a (el) y con placas y celosia. (j) Cuatro placas soldadas para formar una sección en cajón.

espaciadoras con tornillos o soldaduras a intervalos de 1.5 a 2m, a lo largo del par
de angulares, para reducir el ruido debido a la vibración.
La decisión de usar un perfil S en lugar de un W o M, requiere considerar el
hecho de que los perfiles W están mejor balanceados con respecto a la rigidez (rx y
ry)con respecto a ambos ejes, que los perfiles S. Los peraltes real y nominal de los
perfiles S es el mismo, mientras que para los perfiles W y M, el peralte nominal y
el real, difieren, lo que requiere por lo general el uso de placas de relleno en las conexiones-rnostradas en la figura 5-4, a fin de ampliar el ancho y poder construir la
conexión.

5-3.4 Uso de miembros armados a tensión

Se requirirá usar miembros armados, cuando un angular solo o un par, de los
mismos, o cualesquiera de los perfiles laminados normales, o tiene suficiente sección transversal o rigidez (medida por L/r), o no resultará práctico construir la

<!-- p. 261 -->

ESFUERZOS DEBIDOS A LA CARGA AXIAL SOBRE LA SECCION NETA 261

junta. No se considera miembro armado el que está constituido por un par de angulares puestos de espalda.
En la figura 5-7 se muestran algunas posibles secciones armadas. Estos
miembros están formados de dos o más perfiles laminados, suficientemente unidos para que la sección resultante actúe como un solo miembro. La rigidez de un
miembro armado, según la determina el radio de giro r. Puede ser controlada por
el diseñador, lo que constituye una de sus principales ventajas, al usarlas en lugares donde hay inversión de esfuerzos (el miembro soporta tanto cargas de tensión
como de compresión); esta ventaja equilibra un tanto los considerables costos de
fabricación, a menos que se use cierto número de miembros con la misma sección
(por ejemplo, en puentes de armadura con claros muy grandes).
Existen, además de los requerimientos de carga, rigidez, y conexiones, otras
consideraciones en el uso de los miembros armados, a saber, peso mínimo, facilidad de fabricación, y donde se usen en un ambiente hostil, como en los puentes,
protección contra la corrosión, mantenimiento y reparaciones. Los puentes y
otros miembros expuestos a severas condiciones ambientales, que incluyen tanto
los efectos de la intemperie como los de los pájaros, se han de construir de tal modo
que la acumulación de los excrementos de los pájaros y el agua (en particular si
ésta se halla contaminada por óxidos de carbono y azufre, que crean una débil y
rápida corrosión ácida) no se presente. También es necesario que el miembro, o
miembros, se puedan pintar en su totalidad. Este requerimiento imposibilita, por
lo general, el uso de secciones en forma de cajón totalmente cerrado u otras secciones armadas con cavidades cerradas. En su lugar, las secciones armadas deben
estar abiertas en uno o más lados, y se obtendrá la continuidad en esa cara con el
uso de barras de celosía o usando cubreplacas perforadas, como se muestra en la
figura 5-8.

5-4 ESFUERZOS DEBIDOS A LA CARGA AXIAL SOBRE LA
SECCION NETA

La presencia de un hueco en una sección obviamente crea un efecto de "muesca",
como se comentó brevemente en la sección 1-6. Esto será cierto aun cuando el
hueco esté ocupado por un remache o un tornillo. Podrá haber una excepción si el
sujetador engrapa las dos o más partes, haciendo la sección lo suficientemente resistente para que no pueda haber ningún movimiento relativo a través del hueco.
Las pruebas de tensión que utilizan técnicas plásticas y fotoelásticas indican concentraciones de esfuerzos en los bordes del hueco del tornillo, las que pueden tener un valor máximo del orden del doble o el triple del esfuerzo promedio en la
sección. Como los esfuerzos del acero se redistribuyen a través de la sección cuandoft = Fy , es razonable suponer una distribución uniforme del esfuerzo a través
de cualquier sección transversal, al menos para condiciones de esfuerzo estático.
Esto significa que para esfuerzos de trabajo, la distribución actual del esfuerzo en
las cercanías de la conexión con huecos es indeterminada, pero si no se tuviese
precisión al estimar la carga de trabajo, de manera que se produjeran esfuerzos de

<!-- p. 262 -->

262 DISEÑO DE MIEMBROS A TENSION

(al

wssssss~
I I
I I~- -- -- -- -- -- -- -
(bl W
Sección transversal típica
Nota: Se usa actualmente la
soldadura en lugar de losH----Q----bd--U---~ remaches. ---- ---- ---- ----

(el

(dl
Figura 5-8 Celosía y otras formas de producir un miembro armado con acceso al interior. Las prácticas actuales de fabricación en los talleres dan preferencia al uso de listones o cubreplacas perforadas,
que se sueldan. (al Celosia sencilla. (bl Celosía doble. (el Listones. (el Cubreplacas perforadas.

fluencia, se redistribuyen los esfuerzos hasta que la carga sea suficiente para producir ft = Fy en la sección neta.
Cuando un miembro esté sometido ya sea a gran número de inversiones de
esfuerzos o a esfuerzos cíclicos, el resultado es la aplicación de un rango de esfuerzos al miembro. Será necesario reducir los esfuerzos permisibles para evitar la
falla por fatiga si el número de ciclos de esfuerzo y/o el rango de esfuerzos es
grande.
Es común suponer que la fatiga se puede ignorar en la construcción normal
de edificios. Sin embargo, se debe notar que con 20 ciclos de carga/día, el total de
ciclos durante un periodo de 20 años es de sólo
Nciclos = 20(365)(20) = 146000

Por supuesto que hay situaciones donde será necesario considerar los esfuerzos de
fatiga (por ejemplo, trabes para grúas viajeras y sus conexiones), pero el diseñador debe estar alerta a la ocurrencia de estas situaciones en el curso del diseño. En
las especificaciones del AISC se considera el problema de la fatiga en el Apéndice
B del manual de acero.

<!-- p. 263 -->

DISEÑO DE LAS BARRAS A TENSION 263
s-s DISEÑO DE LAS BARRAS A TENSION

El diseño de una barra a tensión procede directamente de la determinación de la
selección carga/área, basada en el esfuerzo permisible de tensión de 0.6Fy- Por lo
común se usan barras roscadas como tensores para soporte de largueros en edificios industriales con techos inclinados, así como para soportar largueros de pared y para soportar balcones y descansos de escaleras. Las barras tendrán roscas
normales, como se muestra en la selección de diámetros de barras de la tabla 5-3.
En el próximo ejemplo se ilustra el diseño de un tensor.

Tabla 5-3 Datos de diseño para las roscas de los diámetros estándar
de barras que aparecen a continuación

Diámetro de la Diámetro en la Número de roscas por
barra raíz pulgada o por 25 mm
pulg mm pulg mm

112 12.7 0.400 10.2 13
5/8 15.9· 0.507 12.9 11
3/4- 19..0 0.620 15.7 10
7/8 22.2 0.731 18.6 9
1 25.4 0.838 21.3 8
11/4 31.8 1.064 27.0 7
11/2 38.1 1.283 32.6 6
13/4 44.4 1.490 37.8 5
2 50.8 1.711 43.5 41/2
21/4 57.2 1.961 49.8 4
21/2 63.5 2.175 55.2 4
23/4 69.9 2.425 61.6 4
3 76.2 2.675 67.9 4

Ejemplo 5·1 Diséñense los tensores de los largueros del ejemplo 4-10 (el
techo de los cobertizos laterales del edificio industrial del ejemplo 2-5) (véase
figura E5.1a); úsese acero A-36.

SOLUCION Seobtuvieron, del ejemplo 4-10, las siguientes cargas parael lar-
guero, siendo la condición D + S + Wla condición más crítica de carga. Sin
embargo nótese, que la carga de 0.066 kip/pie se debe sólo a D + S. Tenien-
do esto en cuenta, se usará F¡ = 0.6Fy y no FI = 0.6Fy (1.33). Obténgase, de
la tabla IV-S, la fuerza sobre el tensor como la reacción central de una viga
simétrica continua de dos claros (figura ES-lb):

5wL 25.
P = 2-8- = 1.25(0.066)T = 1.03kips
Para 12 largueros (figura E2-5a y ejemplo 4-10) el valor superior = 12 x
1.03 = 12.36 kips.

<!-- p. 264 -->

264 DISEÑO DE MIEMBROS A TENSION

I ¡ o 1 ~ I o
I ¿'" I ¿~ I I
I Larguero I
12.5' 12.5' 12.5' I 12.5' I 1
I I
I I
I I
I Larguero 1 I
Ji i
I I I I I
!I !I

\--25·---- l·----25·--...·1-...
Figura ES-la

12.36- 0562 l 2 pu g A req = n-- =.

Las especificaciones del AISC requieren un máximo L/r para contra-
venteos y miembros secundarios a tensión de 300 (sección 1-8.4) pero no para
barras y varillas. No obstante, se usará esto como guía, de modo que el
miembro no sea demasiado pequeño. La fuerza mínima de 6 kips en la sec-
ción 1-15.1 del AISC no se aplica a los tensores.

d r para barra redonda = Vl/A = =-4

L-= 300 d = 4(6.1:~ 12) = 0.988 pulg
r

Verifíquese la varilla de 1 pulg de diámetro (véase tabla 5-3), usando n = 8
filetes de rosca/pulg:

0.9743)2 Ae = 0.7854( 1.00 - -8- = 0.605 > 0.562 pulg Correcto

<!-- p. 265 -->

SECCIONES NETAS 265

0.4195 kips/pie

,J-....,..._- 0.066 kip/pie

F===-----'- p= 1.03 k

Figura ES-lb

Notas:

l. Se puede reducir el tamaño de los tensores en la mitad inferior del grupo
de largueros, para una fuerza en el tensor de 6 x 1.03·= 6.18 kips,
\2. Se requerirá una viga de buen tamaño para salvar los claros de 25 pies, y
soportar la carga concentrada de 12.18 kips en la mitad del claro, sin una
excesivadeflexión hacia afuera. Es indudable que el techo reduce conside-
rablemente este efecto, pero el diseñador tiene que decidir en qué medida.
\3. Los cálculos no le dan importancia a los beneficios derivados del techo en
contacto con el patín superior de los largueros, lo que puede reducir en un
50 por ciento o más la fuerza sobre los tensores. / / /

5-6 SECCIONES NETAS

Cuando la sección transversal contiene una fila de agujeros, la sección crítica
ocurrirá a través de uno de los huecos, como se muestra en la figura 5-9. Cuando
haya más de una fila de huecos, el diseñador debe determinar una sección de falla
que suministre el área mínima. El camino a través de la sección que produzca el
área mínima será la sección neta crítica.
En la figura 5-9b, que es una porción de un patrón que se repite, el que
podría obtenerse en un gran conjunto de placas (tanque de agua, caldera de va-

p = s s s 1 l· - l· ·1· s-l· -lA
\
\ 2
\~ Q O 1 O O x " '- 3 g
):> T I T 11 / / g I O O ..co 4 / I O g I . O O -ee" a: " -, 5
I / 'P
/
6 F F'
(a) (b)

Figura 5·9 Sección neta critica para miembros a tensión con agujeros. (o) Una hilera de agujeros o
más, donde resulta obvia la sección neta. (b) Patrón de agujeros donde se han de hacer pruebas para
hallar la sección neta.

<!-- p. 266 -->

266 DISEÑO DE MIEMBROS A TENSION

por, u otra estructura similar), la sección crítica no resulta directamente obvia, ya
que la placa se puede rajar a lo largo de líneas diagonales como la línea de puntos
1-2-3-4-S-6. Se han desarrollado soluciones teóricas para la falla a lo largo de algún recorrido posible, como el que se acaba de citar, que tiene en cuenta el comportamiento del material a tensión diagonal, a lo largo de las líneas irregulares de
falla. Las soluciones teóricas son demasiado complicadas para c:\<l diseño, y se permite usar una aproximación. Dicha aproximación se basa en un procedimiento de
Cochrane (Engineering News-Record, Vol. 89, 1922, págs. 847-848) y su uso es
casi universal. El método es como sigue:

\1. Tómese cualquier camino razonable, y posible, a través de una cadena de agu-
jeros, y dedúzease un ancho de agujero por cada agujero que se encuentre.
\2. Por cada cambio en la dirección de un agujero al otro, añádase la cantidad

donde s = Paso, o distancia longitudinal entre agujeros adyacentes
g = Gramil entre los agujeros adyacentes a través del ancho de la sec-
ción

Este método de predecir la capacidad de una conexión (basado en el área neta) a
tensión está razonablemente de acuerdo con las pruebas, por lo que no hay ningún motivo para que no se siga usando, ya que su empleo es simple y directo.
Es evidente que si s o g tienen el valor apropiado, se puede reañadir efectivamente un agujero a la diagonal, con lo que se cancela la reducción de dicho agujero en el ancho neto.
El diámetro efectivo del agujero (excepto en los agujeros oblongos) se toma
como

D + 118 pulg (ó 3 mm) Especificaciones del AISC
D + 118 pulg (ó 3 mm) Especificaciones de la AASHTO y el
AREA

El agujero es siempre mayor que el conector, cuando menos en 1116pulg (ó
1.S mm) para absorber un pequeño desajuste (que incluye rebabas tanto en el
agujero como en el sujetador y/o grandes cambios de temperatura entre el punzonado y el montaje) de manera que esta última pueda proceder rápidamente.
Cuando el agujero sea punzonado, se debe deducir 1116 pulg adicional para tener
en cuenta el posible daño del material alrededor del agujero, con lo que se produ-
ce un diámetro efectivo del agujero, D + 118 pulg ó D + 3 mm.

Ejemplo 5-2 ¿Cuál sera la sección neta crítica'del patrón de agujeros que se
muestra en la figura ES-2? Considérense agujeros para tornillos de 7/8 pulg.
Nótese que este paltón es más académico que práctico, pero se usa para

<!-- p. 267 -->

SECCIONES NETAS 267

,! n
2

2"

2"

3"

F' Figura E5-2 F

ilustrar el método de usar s2/4g; úsense las especificaciones del AISC para el
diámetro del agujero.

SOLUCION
Ancho total w = 2(1.5) + 3 + 2(2)
\= 10 pulg
7 r D = i + i == 1.00 pulg

Ancho neto a,lo largo del camino ABDF':
W = 10 - 2(1.00) = 8.00 pulg
Ancho neto a lo largo del camino ABCDEF: wneto = W - 4 agujeros +
s2/4g términos de B a C, CaD, y D a E.

32 32 32
wneto = 10 - 4(1.0) + 4(2) + 4(2) + 4(3) =:= 9.00 pulg

Camino ABDEF:
32 ,
wneto = 10 - 3(1.0) + 4(3) = 7.75 pulg controla

WO.85 = 0.85(10) = 8.50 pulg
Area neta crítica = 7.75(t) pulg-,
Pregunta: ¿Qué valor del paso s producirá una sección neta equivalente
aABDF'?
SOLUCION El camino crítico es a lo largo de ABDEF, y se tiene

S2
wneto = 10 - 3(1.0) + (4)(3) = 10 - 2.00 = 8.00 pulg

<!-- p. 268 -->

268 DISENO DE MIEMBROS A TENSION

S212 = 8.000 - 7.000
S2 = V(12)(1.0)
s = 3.46 pulg
(digamos 3.5 pulg, puesto que cualquier valor superior a 3.46 es correcto)

Sustituyendo de nuevo este valor de s se verifica rápidamente que la nueva
sección crítica será de 8.00 pulg (dentro de los ajustes de las tolerancias).

5-6.1 Sección neta de las secciones laminadas

El método para obtener la sección neta crítica de las secciones laminadas difiere
ligeramente de la solución para la placa, que se acaba de mencionar, puesto que
se debe considerar directamente el área (w X t). Esto se efectúa deduciendo el
área a través de cada agujero (D x t) y añadiendo nuevamente el área parcial del
agujero (s2/4g x t) para cada cambio de dirección en el camino". Nótese que en
este ejemplo se sitúan los agujeros usando las distancias de gramil g¡ que aparecen
en las tablas 1-3y V-3. Estas distancias son estándar para tener la facilidad de tener listas las plantillas en el taller de fabricación para hacer los agujeros, de modo
que produzcan la mínima interferencia con los patines al instalar tornillos o remaches. No será fácil instalar todos los tamaños de tornillos y/o remaches, cuando se usen estas distancias de gramil, pero el espaciamiento es tal que se pueden
acomodar casi todos los tamaños.

Ejemplo 5-3 ¿Cuál será el área crítica a tensión para la canalC250 x 37.2,
que se muestra en la figura E5-3? Los tornillos son de 22 mm (tabla VI-7).
Tómese nota de la distancia g¡ usada para situar los agujeros B y D con res-
pecto a los patines, y que viene dada por la tabla V-6. Se usarán las especifi-
caciones del AISC,

A

V) .. B '"-o O V)
N1- V)'"""
'"V) O -o J:6 '"-c
Figura ES-3

SOLUCION De la tabla V-6 se obtiene
A, = 4.74 X 10-3 m2
k_

• Esto se ejemplificará con una sección en canal usada como miembro a tensión.

<!-- p. 269 -->

SECCIONES, NETAS 269

tw = 13.4nun
D = 22 + 3.0 = 25.0nun

Area neta a lo largo del camino ABDE:

An = 4.74 - 2(0.025)(13.4) = 4.07 x 10-3 m2

Area neta a lo largo del camino ABCDE [área - 3 agujeros + 2(sl/4g)]

An = 4.74 - [3(0.025) + 2( 4(~~~5) ] x 0.0134 x loJ
\= 4.74 - 0.740 = 4.000 x 10-3 m2 se halla que es critica
A O.85 = (4.74)(0.85) = 4.029 x 10-3 m2

Para una canal con los patines fuera del plano y sin conexiones, y haciendo
referencia a la sección 5-3.2, el área defectiva A e (w/3 lineas de conectores)
será
Ae = 0.85An = 0.85(4.00) = 3.40 x 10- 3 m2 III

5-6.2 Secciones netas de angulares con agujeros defasados

La sección critica de los angulares con agujeros defasados es similar a la de las
placas, como se ilustra en la figura 5-10. La localización de los agujeros se hace de
manera estándar, como se ve en la tabla 1-13o V-13. La sección critica se basa en
el ancho neto menos los agujeros + sl/4g, como antes. Nótese que el ancho neto
de la placa equivalente sin punzonar = b, + b2 - 1, como se obtendria cortando

I
I o
OI O b¡ + b: - t f? ,/I •
(a)
/9:

gcalc = g + g¡ - t
(b)

Figura S-lO Sección neta de un angular usado como miembro a tensión con agujeros defasados en
ambos lados.

<!-- p. 270 -->

270 DISEÑO DE MIEMBROS A TENSION

el angular a lo largo de la línea AB y volviéndolo a colocar como se ve en la figura
5-lOb.

Ejemplo 5-4 ¿Cuál será la sección crítica del angular 8 x 6 x 3/4 con tres
agujeros para pernos de 3/4, como se muestra en la figura E5-4? Usense las
especificaciones del AISC.

1- -o" -1- -o" -1 Al
O o B
O 3"
O O D
3" 3" 3" 1\ -2 -4 4.0 • • • Il 1.:JI" F ~~6"

G

Figura E5·4

SOLUCION
D = 0.75 + 0.125 = 0.875 pulg

Ancho neto a lo largo del camino ABDFG:
w = 8 + 6 - 0.75 - 3(0.875) = 10.625 pulg

Ancho neto a lo largo del camino ABCjJEFG:

w" = w - 5 agujeros T s2/4g para B-C, C-D, D-E, y E-F
22 22 22 22
w" = 13.25 - 4.375 + 4(1.5) + 4(1.5) + 4(3 + 1.5) + 4(2.5)
\= 13.25 - 4.375 +0.667 + 0.667 + 0.222 + 0.400
\= 10.83 pulg.

Ancho neto a lo largo del camino ABCDFG:
w" = 13.25 - 4(0:875) + 0.333 + 0.333 = lGA2- pulg,

Ancho neto a lo largo del camino AIIDEFG:

w" = 13.25 - 4(0.875) + 0.222 + 0.400 = 10.37pulg.

<!-- p. 271 -->

DISEÑO DE MIEMBROS A TENSION SEGUN EL AISC 271

Verifíquese el requerimiento del 85 por ciento:

Wn = 13.25(0.85) = 11.26 pulg.
Basándose en el ancho neto crítico de 10.37 pulg y t = 0.75 pulg (nótese que
ambos lados están conectados, por lo que no se requiere una reducción por
rezago del cortante):
\+ Ae = 10.37(0.75) = 7.78 pulg-
Pperm = AgFt = 13.25(0.75)(0.6F;,)
o P perm = Ae~ = 7.78(O.5Fu)

el menor de los dos.

5-7 DISEÑO DE MIEMBROS A TENSION SEGUN EL AISC

Para diseñar miembros a tensión se necesitan ciertos cálculos para determinar la
carga, y otros cálculos adicionales para determinar la sección neta crítica, en donde se usen agujeros para conectores mecánicos. La selección de los miembros se
efectúa teniendo como base satisfacer los requerimientos de área bruta y neta,
incluyendo el máximo de 85 por ciento cuando haya agujeros en el miembro, y
cualquier reducción del área neta por consideraciones de flujo de cortante.
Es preciso cumplir con los requerimientos de L/r en todas las especificaciones, así, las tres especificaciones (AISC, AASHTO y AREA) tienen requerimientos mínimos de capacidad de conexión. El requerimiento mínimo de conexión para el AISC, se encuentra en la sección 1-15.1 y requiere cuando menos 6
kips,

Ejemplo S-S Selecciónese la sección más ligera de un solo angular para los
miembros verticales de la armadura del cobertizo lateral en el edificio in-

194.5 kN

Figura ES·S

<!-- p. 272 -->

272 DISEÑO DE MIEMBROS A TENSION

dustrial del ejemplo 2-6. Es deseable que se utilice la misma sección de angu-
lar en todos los verticales, la misma sección para todas las diagonales, y de
modo similar, sedisefiarán las cuerdas superior e inferior, usando secciones de
tamaño constante. Sólo se diseñarán en este ejemplo los miembros verticales
del alma. Se usará Fy = 250 MPa y las especificaciones del AISC.

SOLUCION De la inspección de la salida de la computadora (parte de la cual
no se muestra en el ejemplo 2-6), se obtienen los valores siguientes, a partir
de las dos condiciones de carga que se usaron: .

Lado derecho Lado izquierdo

Miembro LC-I (kN) LC-2 (kN) Miembro LC-I (kN) LC-2 (kN)

4 0.0 0.0 74 124.73 157.57
8 31.18 48.62 78 93.56 118.18
12 62.36 97.26 82 62.37 78.80
16 93.54 145.88 86 31.18 39.40
20 124.72 ~3tr) 90 0.0 0.0

Como los signos son (+), todos los miembros verticales tendrán solamente
fuerzas a tensión para cualesquiera de las condiciones de carga. Nótese que el
programa de la computadora ajusta automáticamente el producto con el fac-
tor de 0.75 para el viento, por lo que todas las cargas tienen la misma base de
diseño, El miembro 20 tiene la mayor fuerza axial de tensión, con el viento
soplando por la izquierda; el viento soplando por la derecha produciría este
valor de diseño en el miembro 74. El miembro 20 es el miembro más largo de
todos los verticales del cobertizo lateral y tiene una L = 4.5 m. Si alguno
de los otros miembros hubiese sido más largo, esa longitud de miembro
controlaría L/r; en este caso, tanto la longitud de control como la fuerza má-
xima de tensión están en el mismo miembro. Para diseño, P = 194.5 kN. La
máxima L/r = 240 (según el AISC, sección 1-8.4, y suponiendo que se trata
de un miembro principal al tener una fuerza axial tan grande). El radio
mínimo de giro es

\= 4.5(1000) = 1875 r min 240 . mm

Un cálculo preliminar auxiliar indica que el patrón de los tornillos mostrado
en la figura E5-5, tal vez podría utilizarse, ya que es probable que controle la
L/r y no el esfuerzo. Con este patrón se podrían usar distancias estándar de
gramil, y resultaría muy económico. Para dos tornillos en la sección y usan-
do tornillos A-325 de 22 mm:
D = 22 + 3.0 = 25.0 mm

<!-- p. 273 -->

DISEÑO OC MIEMBROS A TENSION SEGUN EL AISC 273

El área efectiva del angular, usando los criterios del AISC para el rezago del
cortante es (véase sección 5-2.3):

Basándose en FI = 0.6Fy , la sección bruta de"i angular debe ser cuando menos

A 194.5 1 2967 10-3 m2 g = 0.6(250) =. X

Basándose en FI = 0.5Fu (se usa la tabla 5-1 para Fu), el área neta efectiva,
A e tiene que ser

Ae = 1~~5 = 0.9725 x 10-3 ro2

Esta área neta efectiva, A e, se ha de obtener de una sección bruta de cuando
menos

A = 0.9725 = 12712 X 10- 3 ro2 \< 1.2967 g 0.85(0.90) .

En general, no se puede, decir de antemano cuál sección de angular será
la mejor, hasta que se hallen una o más que sean adecuadas, para luego seleccionar la más ligera. La mejor manera de obtenerla será con el uso de una
tabla como la siguiente (nótese. también que rmio = rz , para un solo angular):

1, mm Aagujerost m2 A nela, m2 Sección rz' mm A proporcionada ( x
10- 3), m2

6.3 0.315 1.17$':;> 1.081 L152 X 89 X 6.3 19.7 1.490 > 1.2967
7.9 0.395 1.153 > 1.081 L102 X 102 X 7.9 20.1 1.548

En la tabla anterior,

3 Aagujeros = 2Dt = 2(25.0)(0.0063) = 0.315 x 10- m2
\~.9725 -3 2 ~ A ne1a = Ag - Aagujeros _ = 1.?81 X 10 m

Estos son los dos únicos angulares de las tablas V-8 YV-9 que es preciso con-
siderar. En este caso es el radio de giro que controla la selección de la sec-
ción, más bien que los requerimientos de área. Se usará tentativamente: L152

<!-- p. 274 -->

274 DISEÑO DE MIEMBROS A TENSION

x 89 x 6.3 (por ser el más ligero). Se debe seleccionar una sección que se
pueda usar en la junta, de la manera indicada. Compruébese si es posible co-
locar dos tornillos de 22 mm, uno al lado del otro, en el lado más largo del
angular. Con el uso de la tabla V-13 se obtiene:
Distancias estándar de gramil: g¡ = 57.2 mm g2 = 63.5 mm
Especificaciones del AISC: centro a centro de agujero = 2.67D (se pre-
fiere 3D)
Especificaciones del AISC: centro del agujero al borde del lado del an-
gular (véase la tabla 1-16.4 del SSDD = 28 mm (ó 1 118 pulg)
s, = 63.5 > 2.67D Correcto
Diámetro real del agujero = 22 + 1.5 = 23.5 mm
Distancia al borde = 152 - 57.2 - 63.5 = 31.3 > 28 mm correcto

Se usará una sección Ll52 x 89 x 6.3.

Ejemplo s.6 Selecciónese el par de angulares más ligeros para los miembros
verticales de la armadura principal de techo del ejemplo 2-6. Usense las espe-
cificaciones del· AISC y Fy = 250 MPa. El lector debe observar que los
miembros de esta armadura tendrán que diseñarse tanto para tensión como
para compresión (y posiblemente para fatiga). De salida de la computadora,
los miembros 39 y 47 serán críticos para las fuerzas axiales.

Miembro rC-I (kN) LC-2 (kN) L, m

39 -63.65 +20.39 6.76
47 +70.18 -37.60 8.2 (el más largo de las
verticales)

Psr = 70.18 - ( - 37.60) - 107.78kN

El miembro 47 es crítico para el diseño a tensión.

, . 8.2(1000) 3417 r mlDlmo = 240 = . mm

Se usarán tornillos de 25 mm: D 25 + 3.0 = 28.0 mm. Usense dos secciones
L con una placa de relleno de 12mm, como se muestra en la figura E5-6. Su-
pónganse dos líneas de agujeros, ya que Pes solamente 70.18kN, lo queda un
A e = O.90A n•

<!-- p. 275 -->

DISEÑO DE MIEMBROS A TENSION EN LOS PUENTES 275

12 Placa de
conexión

25\<1>

Figura E5-6

Para A e = 0.75A n , el área bruta del angular será cuando menos

70.18. 05504 10-3 2
Ag = (200)(0.85)(0.75) =. X m

Usense los lados largos de los angulares desiguales, espalda con espalda
(¿Por qué?). Establézcase nuevamente una tabla de angulares dobles, usan-
do las tablas V-lO y V-ll del SSDD [Ae = la menor de (A n Ó 0.85A g) x
0.90]:

r, mm Aproporcionada (x 10- 3) , m2

6.3 0.353 2.307 2.03 2Ll27x89x6.3 37.5 2.660
7.9 0.442 3.468 2.991 2Ll27 x 127x7.9 39.9 3.910

No se encuentra nada más ligero que estos dos angulares dobles. Nótese que
la L/r mínima controla el diseño, Verificando luego el rango de esfuerzos y
usando A e, se.tiene

{ = Psr = 107.78 = 540MP Jsr: A 2.03 . a
e

Este valor de 63.6 es mucho menor que cualquier otro valor de Fsr en la tabla
1-4, hasta 2000 x 103 ciclos de esfuerzo para el "metal base" en juntas co-
nectadas mecánicamente. Se usarán dos secciones Ll27 x 89 x 6.3.

5-8 DISEÑO DE MIEMBROS A TENSION EN LOS PUENTES

El diseño de miembros a tensión en los puentes es similar al diseño utilizando las
especificaciones del AISC, excepto que habrá que considerar la fatiga, como se
\-resume en las secciones 5-4 y 1-9. Esto se ilustra con el ejemplo siguiente.

EjemplQ 5-7 En la figura E5-7 se muestra una porción de la armadura de un
puente de carretera. Se requiere seleccionar la sección W12 más ligera, para

• sr = stress range (rango de esfuerzo)

<!-- p. 276 -->

276 DISEÑO DE MIEMBROS A TENSION

usarla en el miembro 9, utilizando acero A-36 y las especificaciones de la
AASHTO. Supóngase 2 x 1()6 ciclos de carga para la vida en servicio de
la estructura.

6

7WI2D 1-17'

4

Figura ES·7

SOLUCION Se obtiene de la salida de la computadora, lo siguiente(seinclu-
ye el impacto en las cargas vivas):
Carga muerta + 80.3 kips
Máxima carga viva + 60.2 kips
Mínima carga viva - 22.8 kips

De las que se obtienen
Prnáx = 80.3 + 60.2 = 140.5 kips
Prnin = 80.3 - 22.8 = 57.5 kips

El rango de fuerzas (análogo al de los esfuerzos) es
Psr = 140.5 - 57.5 = 83 kips

Se supondrán cuatro agujeros en el patín de cualquier sección neta, como se
muestra en el inserto de la figura E5-7. Se usarán tornillos de 7/8 pulg de
diámetro, de modo que el diámetro efectivo del agujero será, D = 7/8 + 1/8
\= 1.0 pulg.

Aagujeros = 4(1)t¡

Se usarán tornillos de alta resistencia para conectar el miembro a la jun-
ta, que producirán condiciones de rango de esfuerzos para "metal base con
conectores de fricción". Los datos dados en la sección 1-12 se basan en un
rango de esfuerzo permisible para el caso en que no ocurra una falla ca-
tastrófica de manera inmediata cuando falle el miembro. No es probable en
este caso que haya un colapso de la armadura si falla el miembro 9. Hecha
esta consideración se obtiene el rango permisible de esfuerzos:

<!-- p. 277 -->

DISEÑO DE MIEMBROS A TENSION EN LOS PUENTES 277
Fsr = 16 kip/pulg- (primera columna y verificando la nota al pie)

Se usará contraventeo horizontal y transversal a través de la parte supe-
rior y extendido entre las dos armaduras para satisfacer la estabilidad, pero
esto no reducirá la longitud libre de los varios miembros del alma con respec-
to al eje Y. (La AASHTO requiere que la profundidad efectiva de este
contraventeo tenga cuando menos 5 pies o 1.8 m.) La fabricación de la junta
requiere orientar el eje X en el plano de la armadura, para secciones lamina-
das. Nótese que, comúnmente, las vigas transversales de piso quedan un po-
co por debajo del punto de intersección de los miembros del alma de la armadura y la cuerda inferior, pero esto no debe afectar significativamente la longitud L.
Parece ser suficiente la limitación de la AASHTO para L/r = 200 para
miembros principales a tensión y sin inversión de esfuerzos (Sec. 1-7.5) Ypara P = 140.5 kips. El área neta, suponiendo que Fa = 0.55Fy es

_ P _ 140.5 _ . 2 Aneta - F - 20 - 7.025 pulg
a
25(1.414)(12)
, min = 200 = 2.12 pulg (para ry)

Se usará arbitrariamente el requerimiento del AISC ce un 85 por ciento, de
manera que A g será cuando menos

7.025 1 2
Ag ~ 0.85 = 8.26 pu g

Se establecerá, por ensayos, la tabla siguiente, donde Aagujeros 4(1.0)//;
A req = A g - Aagl!jeros

Sección I¡, pulg

WI2x53 0.575 2.30 13.30 15.60>8.26 2.48 Correcto
WI2xSO 0.640 2.56 12.14 14.70 1.96 N.S.

La sección W12 x 53 es la W12 más ligera que es satisfactoria tanto pa-
ra los requerimientos del área como para los de la L/r. Se selecciona además
esta sección a fin de que sea más fácil la fabricación de la junta, cuando se diseñe el miembro vertical (No. 7) en el capítulo 6.
Compruébese el rango de esfuerzos para la sección W12 x 53:

i' = Psr = 83.0 = 6.24 K/pulg2 ~ 16 K/pulg2 Correcto Jsr An 13.30

<!-- p. 278 -->

278 DISEÑO DE MIEMBROS A TENSION

y/-------L-------

If

Figura 5-11 Geometría del cable para deducir las ecuaciones de diseño. Nótese que en esta configuración el valor de T en el origen es mayor que el valor de T en el otro extremo del cable.

A1JlPque la fatiga no es un parámetro de control para este miembro, todos los
miembros de esta armadura se deben revisar de modo semejante. Se usará
una sección W12 x 53.

5-9 DISEÑO DE CABLES

La suma de momentos alrededor de un lugar conveniente con respecto a la
geometría parabólica del cable que se muestra en la figura 5-11, da

wL 2
H=- (5-6)
8h
donde h = Flecha a la mitad del claro, como se muestra en la figura 5-11
w = Carga uniforme del cable/unidad de longitud; siempre habrá una
carga uniforme debida al peso del cable
L = Longitud del claro (la longitud del cable es siempre algo mayor)

En general, la flecha y del cable en cualquier punto es

4hx
y = -(x - L) + x· tan O (a) 2 L
Diferenciando, se obtiene
dy 8hx 4h -=----+tanO 2 (b) dx L L
Como
H (dS) dy )2] 1/2 y T----H- ds= dx 0- x - cos [ 1+ ( -dx

<!-- p. 279 -->

DISEÑO DE CABLES 279

se obtiene una ecuación general para la fuerza de tensión en el cable en cualquier
punto:

64h2X2 ( h )2
Tx = H 1.0 + L 4 + 16 L + tarr' O [
64h2x 16hx h] 1/2 - -- + --tan O- S-tan O (5-7) L3 L . L

Tomando nota de que todos los términos dentro de la raíz cuadrada son pequeñ.os
excepto el primero, tercero, y cuarto, se puede simplificar y obtener

h )2 ] 1/2 T; = H 1 + 16( L + tan2 O (5-8) [

Cuando los extremos del cable se hallan a elevaciones muy diferentes, se debe
usar la ecuación (5-7) con preferencia a la ecuación (5-S), porque la tensión en el
extremo superior del cable será en grado considerable diferente ("soporta" el peso del cable + cualquier carga adicional sobre el cable). Para los cables horizontales, T tiene el mismo valor en ambos extremos, y se calcula directamente como

(5-9) T= H[ 1 + 16( 1)]1/2

La longitud del cable viene dada aproximadamente por

(5-10)

Se han usado cables para soportar estructuras de techo sobre un claro muy
grande, así como puentes y vientos para torres. En los edificios, el techo de cables
se construye extendiendo cables a través del espacio abierto con un espaciamiento
suficientemente corto y la aplicación de una fuerza T de pretensado para producir
la flecha deseada, basándose en la ecuación (5-9). La flecha en los edificios es del
orden de 1/12 a 1/16 (en los puentes puede llegar a 1/6 a 1/S). En estructuras redondas, se pueden fijar los cables a un gran anillo de compresión en el perímetro
del edificio, y terminar en el centro en un anillo de tensión. Esta configuración es
la más deseable, ya que la tensión de los cables ha de ser soportada por algún tipo
de anclaje. El anillo de compresión es muy deseable, ya que se pueden usar grandes esfuerzos de compresión si el anillo está hecho de acero. El uso de techos de
concreto preforzado, colocados como "losetas" directamente sobre los cables
produce el techo que se desea y al mismo tiempo tiende a reducir las vibraciones,
puesto que las losetas de concreto son bastante pesadas y desarrollan un gran sistema de masa.

<!-- p. 280 -->

280 DISEÑO DE MIEMBROS A TENSION

Donde el uso de las losetas de concreto no es suficiente para restringir el
amortiguamiento, se debe recurrir a otros medios. El amortiguamiento tiende a
modificar la amplitud natural de un sistema en vibración y, si se aplica de una
manera eficaz, elimina las amplitudes de resonancia de la vibración. La frecuencia natural de un sistema de cables es (lo mismo que cualquier otro tipo de cálculo
de la frecuencia natural)

1, = n-'TT ( -T)I/2 (5-11) n L m
donde m = w/g = masa de todo el cable (incluyendo cualesquiera accesorios,
tales como un techo, etc)
n Cualquier entero, tales como 1, 2, o 3, usados para obtener los mo-
dos fundamentales; el valor para n = 1 es de un interés primario,
pero puede ser que se necesiten valores con n = 2, 3, y quizá 4
T Tensión del cable; se puede escribir como T + !1T, de modo que sea
evidente que un cambio de T produce un nuevo In

Una manera conveniente de amortiguar un cable para controlar la vibración,
consiste en fijarlo a otro cable; como se ilustra en la figura 5-12, el que tiene una
frecuencia natural diferente. Esto se puede efectuar con el uso de la ecuación
(5-11), la que indica que los cambios de Tproducen diferentes valores deln• Será
necesario, entonces instalar los cables usando puntales verticales, con una tensión
suficiente para satisfacer las fuerzas de diseño y con tales valores de T que hagan
que los valores deln en cualesquiera de los modos fundamentales no coincidan, lo
que produciría resonancia (muy grandes amplitudes de vibración que causarían
tal vez un colapso estructural).

La AISI ha sugerido valores para los factores de seguridad cuando se usen
cables que oscilan entre 2.5 y 3.0; compárese la tensión última factorizada para
Pu, según está dado por tablas como la tabla 5-2. La carga factorizada puede ser
u = 1.5 muerta + 3 viva
U = 2.5(D + L)
U = 2(D + L + W o E)
o U = 2.0 x cargas de montaje

Ejemplo 5-8 Diséñense lOS vientos, a un nivel, para una antena de TV de 250
m de altura. Las fuerzas horizontales para el diseño se muestran en la figura
E5-8. Se usarán cuatro vientos, pero cada uno de ellos se diseñará para la
fuerza indicada.

SOLUCION Para el nivel de 100 m, se obtiene, usando la ecuación (5-6)

2
wL = 1lükN w = 8(110) = 0.088
8h h 100z

<!-- p. 281 -->

DISEÑO DE CABLES 281

Colóquese el techo sobre el cable superior

Xt El anclaje en los extremos puede
constituir una importante
.l'b consideración de diseño
Los puntales y el cable inferior producen
un efecto rigidizante en el sistema
(a)

Colóquese el techo sobre el cable superior

Anillo de tensión

(b)

Anillo de compresión
Techo

La disposición del cable en la torre puede
ser radial o unidireccional

Se usará una armadura si el claro inferior fuese grande

Torre

td ¡

Figura 5·12 Varias configuraciones de cables en la construcción de edificios. (a) Cables espaciados a
través del claro para un edificio de planta rectangular. (b) Un solo cable que usa un anillo central de
tensión, para un edificio circular. (e) Sistema de doble cable para mayor rigidez y control de vibración. Para edificios de planta circular. (d) Cables usados en un sistema de soporte de techo. Si los
cables son radiales, las torres pueden ser esencialmente autosoportantes.

<!-- p. 282 -->

282 DISEÑO DE MIEMBROS A TENSION

\-250m

\-200 m- 120 kN

E
oV)
e-

\~_.r~ -100 m- 110 kN

Figura ES-8

Además, la tensión del cable es, ecuación (5-7):

obtenida con una ligera simplificación de los términos. Por ensayos, y usan-
do FS = 2.5, () = 45° - Tan () = 1.0, se construye la tabla:

Prueba h - w/0.088 T w del cable, kN/m Diámetro mm

I 155.6 389 0.024 25 °(supuesto)
2 0.272 m 154.7 386 Suficientemente cerca del valor inicial

Se usará un torón para puentes, de 6 x 7 con 5 mm, con Pu = 407 > 386
kN. El anclaje tendría que ser diseñado para una fuerza de arranque TDÚn'
calculada como
]1/2 )2 T mln = H = 110(1.4065) = 154.7kN + tan2 f) - 8 Lh tan f) 1 + 16( Lh [

Con FS = 3, la resistencia del anclaje sería 3 x 154.7 = 464 kN. / / /

Ejemplo 5-9 Se desea construir un techo en forma de domo sobre un edificio
que se usa como estadio deportivo (figura E5-9). El edificio es aproximada-

<!-- p. 283 -->

DISEÑO DE CABLES 283

mente rectangular, con 350 x 700 pies en planta. Los cables se tenderán en
la dimensión más angosta (claro de 350 pies) como se muestra en el perfil,
usando dos cables, con puntales para controlar el amortiguamiento. El techo
se colocará directamente sobre el cable superior. Los puntales se colocarán
con sus centros a una distancia de 20 pies, y estarán sometidos a compresión.
El diseño de los puntales se considerará en el capítulo 6.

4' de espaciamiento
para una flecha de h = ~3.3'
700'

• 350' :Figura ES-9 t==IE2T

SOLUCION Carga muerta del techo, incluyendo el peso de hs cables
(proyección horizontal) = 6(\ lb/pie
Carga viva a 40 lb/pie': 40 x 4 = 160 lb/pie
Carga total = 220 lb/pie

Como el peso de la carga del cable superior tiende a deprimir el cable, se
imprimirá una tensión arbitraria en él para producir una flecha equivalente
de 23.3 pies, como se muestra, y esta tensión será [combinando las ecuacio-
nes (5-6) y (5-8) para obtener el valor indicado]:

(h)2]1/2- T=-WL2[ 1 + 16 8h L

Tomando 1/2 de la carga del techo como w,
0.220(350i [ ( 23.3 )2] 1/2 . T = 2(8)(23.3) 1 + 16 350 = 74.8 kips

El cable inferior soportará la carga uniforme, que produce la flecha de 23.3
pies del cable superior, además de la carga total del techo:

\= (0.220/2 + 0.22)(350)2 (1 035) = 2244 ki T 8(23.3) . . ps

<!-- p. 284 -->

284 DISEÑO DE MIEMBROS A TENSION

Las áreas requeridas para los cables, usando F = 3.0 serán:
Cable superior: P¿ = 3(74.8) = 223.4 kips - se usará un cable para
puentes con un diámetro de 1 1/2 pulg.
De la tabla 5-2, w = 4.73 lb/pie
Cable inferior: P; = 3(224.4) = 673.2 - se usará un cable para puentes
con un diámetro de 2 1/2 pulg
De la tabla 5-2, w = 12.8 lb/pie.
Los puntales soportarán una carga de compresión basada en q que produce
un valor de h en el cable superior de 23.3 pies. Esto da una carga uniforme
equivalente para el puntal "o diafragma" de 0.220/2 = 0.110 kip/pie. Con
un espaciamiento de 20 pies, la carga sobre el puntal es 20(0.110) = 2.2 kips.
Compruébese la frecuencia natural de los cables superior e inferior: Hállese
primero la longitud del cable:
L=350[1+~(~~~r _352(~~~r]

\= 354.13 pie
Con las cargas vivas y muertas en contacto con el cable superior, y usando
350 pies como el claro de contribución para estas cargas, la masa será

W 0.220350 . m = - = ---- = 0.00676 lb· S2/ p1es g 32.2 354
'1T ( T )1/2 '1T ( 77.4 )1/2 in = n L m = n 350 0.00676 = 0.96n
Para n = 1, 2 Y3, se obtieneIn = 0.96, 1.92, Y2.88 Hz.
Para el cable inferior, se usará sólo el peso de dicho cable, ya que son única-
mente los puntales los que tienen continuidad con el cable superior:
\= ~[232.1(32.2) ]1/2 = 678 j, n n 354 0.0128 . n

Para n = 1,2 Y3, se obtíenej; = 6.78, 13.6, Y20.3 Hz.
Como las frecuencias naturales, 1m de los dos cables son considerablemente
diferentes, no es probable que ocurra resonancia alguna. Cuando un cable
esté en resonancia, el otro está a una frecuencia diferente, 10 que actúa como
amortiguador de las vibraciones de resonancia, de manera que la amplitud
total de la vibración se mantiene pequeña. / / /

5-10 DISEÑO DE MIEMBROS A TENSION USANDO EL DFRC

El diseño de miembros a tensión usando el DFRC es relativamente sencillo. Es necesario identificar nuevamente las cargas muertas y vivas, para poder usar el fac-

<!-- p. 285 -->

DISEÑO DE MIEMBROS A TENSION USANDO EL DFRC 285

tor de carga apropiado. Una vez realizada esta operación, y que se haya obtenido
la carga axial última de tensión, Pu, se tiene
r; == Ancf>F;. (cf> = 0.88, tabla 3-1)
Pu = Ancf>Fu (cf> = 0.74)

Ejemplo 5-10 Se da un miembro de una armadura de techo en la estructura
de un edificio, que tiene una longitud de 11.5 pies, con una carga muerta de
18.52 kips y una carga viva de 22.54 kips (carga de nieve). Se usará el método
DFRC, acero A-36, y tornillos de alta resistencia A-325, y de 7/8 pulg de
diámetro. Diséñese el miembro usando el perfil C más ligero posible.

SOLUCION Se usará el patrón de distribución de tornillos que semuestra en
la figura E5-l O;de este modo seempleará el factor de reducción por rezago del
cortante de 0.85, según el AISC (cuando menos tres conectores en la línea de
esfuerzos).
L-=240 (Valor máximo del AISC para un miembro principal) r
11.5(12) 1 = 0575 rrnln = 240 . pu g

Figura E5·10

Descontando dos agujeros en la sección crítica, el área neta es

De la sección 3-7, se obtiene (factores de la tabla 3-1)

P; = 1.1(l.lD + 1.5S)
\= 1.1 [1.l(18.52) + 1.5(22.54)] = 59.6 kips
A r; 59.6 - 1 88 1 2 n ~ cf>F;. = 0.88(36) -. pu g

\= = 139 pulg2 An~ '/'-'..A;uP 59.6 0.74(58) .

<!-- p. 286 -->

286 DISEÑO DE MIEMBROS A TENSION

Usando el mayor valor de A m la sección bruta, con el factor de eficiencia del
AISC y el factor de rezago del cortante, se tiene un valor para el área bruta
de cuando menos

_ 1.88 _ u1 2
Ag - 0.85(0.85) - 2.602 p g

Se prueba un C7 x 9.80:

Ag ,= 2.87 pulg- ry = 0.625 pulg > 0.575 Correcto

Hay que comprobar si se pueden colocar dos tornillos en el alma, como
se ilustra en la figura ES-lO.
gl = 2.50 pulg y 2g1 = 2(2.50) = 5.00 pulg

Esto deja un espaciamiento para los tornillos de

7.00 - 5.00 = 2.00 \< 2.67(7/8) N.S.

Se prueba un C8 x 11.50:

A = 3.38 pulg-' ry = 0.625pulg > 0.575 Correcto
g I = 2.50 pulg tw = 0.220 pulg
\~
Esto deja para los tornillos, un espaciamiento centro a centro de
8 - 5 = 3 pulg > 3D Correcto

Compruébese el área neta: descontando dos agujeros:

A" = 3.3~ - 2( ~ + ~ )0.22 = 2.940 pulg-'

Compruébese el rezago del cortante:
A e = 2.940(0.85) = 2.499 > 1.88 pulg- Correcto

Eficiencia y rezago de cortante combinados:
Ae = 3.38(0.85)(0.85) = 2.44 > 1.88 Correcto III
Se usará como miembro una sección C8 x 11.50

<!-- p. 287 -->

PROBLEMAS 287

PROBLEMAS

Supóngase para todos los problemas una resistencia adecuada para los conectores, de modo que sean
sólo los requerimientos de sección neta bruta los que controlen.

5·1 Diséñese una barra de ojo para soportar una carga a tensión de 40 kips, usando un pasador de I
pulg de diámetro. Se usará acero A-36 y las especificaciones del AISC. Usese t 2: 3/4 pulg y w en múl-
tiplos de 1/8 pulg,

5-2 Diséñese una barra de ojo para soportar una carga a tensión de 200 kN, usando un pasador de 25
mm de diámetro. Usese Fy = 250 MPa y las especificaciones del AISC. Usese t 2: 15 mm y w en múl-
tiplos de 3 mm.

5·3 ¿Cuál será el ancho neto de la placa de la figura P5-3, usando las unidades pie.lb.seg dadas?
Respuesta: 6.75 pulg.

1.5"

40 1.5"
," E 50 O V>E'o_ 2 75 3"
e-rV> 30 V' 50
40 40 1.5" Figura P5-3
\~-~¿Cuál/""" será el ancho neto de la placa de la figura P5-3, usando las unidades SI dadas?
.-' Respuesta: 176.3 mm
S-S ¿Cuál será el paso de los tornillos en la figura P5-3, para que la sección neta crítica tenga cuando
menos 8 pulg?
5-6 ¿Cuál será el paso de los tornillos en la figura P5-3, para que la sección neta crítica tenga cuando
menos 205 mm?
Respuesta: 62 mm.
5-7 ¿Cuál será la capacidad permisible de la placa de la figura P5-3, si se usa acero A-36 y el espesor
de la placa es de 1/2 pulg?
Respuesta: 97.9 kips.
5-8 ¿Cuál serála capacidad permisible de la placa de la figura P5·3, si se usa acero con F; = 250 MPa
y el espesor de la placa es de 12 mm?
Respuesta: 423 kN
5-9 ¿Cuál será la carga permisible a tensión para la placa de la figura P5-9, usando F, = 345 MPa pa-
ra el acero, tornillos de 20 mm de diámetro, y las especificaciones del AISC?

t » 15mm

\~~ mm !20q») O
I Ó ---+--+25
I O 25 150
! O 20
I 30

Figura P$·9

<!-- p. 288 -->

288 DISEÑO DE MIEMBROS A TENSION

5-10 ¿Cuál será e! paso necesario en el problema 5-9, para que sólo sea necesario deducir tres agujeros
del ancho para producir la sección neta?
Respuesta: 32 mm.
5-11 Selecciónese e! angular individual más ligero para una carga a tensión de 50 kips. La longitud es
de 6 pies y se usarán tornillos de 7/8 pulg de diámetro, con un patrón como el de la figura P5-11. Usese acero A-36 y las especificaciones del AISC.
Respuesta: L6 x 4 x 1/4.

o O O
• p
O O O
Figura PS- 11

5-)2 Selecciónese el angular individual más ligero, para una carga a tensión de 210 kN. La longitud es
de 1.9 m y se usarán tornillos de 22 mm de diámetro, con un patrón similar al de la figura P5-11. Usese
acero con F. = 250 MPa, y las especificaciones del AISC.
5-13 Selecciónese e! par más ligero de angulares colocados espalda con espalda para soportar una carga a tensión de 400 kN. Usense tornillos de 22 mm de diámetro, y placa de conexión de 12mm, y acero
con F. = 345 MPa. Usese e! patrón de tornillos de la figura P5-13 y las especificaciones de! AISC. La
longitud del miembro es de 3.2 m.
Respuesta L102 x 76 x 6.3.

Placa de conexión

O O O O --+--~p

Figura PS-13

5-14 Selecciónese el par más ligero de angulares colocados espalda con espalda para soportar una caro
ga a tensión de 92.5 kips. Usense tornillos de 7/8 pulg de diámetro, una placa de conexión de 1/2 pulg, y
acero con F. = 50 kip/pulg-'. El miembro es de 8.375 pies de largo. Usese el patrón de tornillos de la
figura P5·13 y las especificaciones del AISC.
5-15 Selecciónese el angular individual más ligero para una carga a tensión de 68 kips, suponiendo
que hay un tornillo de 3/4 pulg de diámetro en la sección critica. El miembro tiene 7.5 pies de largo.
Usese acero A-36, el patrón de tornillos de la figura P5-15, y las especificaciones del AISC y de la
AASHTO. Supóngase que en el caso de la AASHTO no hay inversión de esfuerzos.
Respuesta: Según la AASHTO, L7 x 4 x 7/16.

O O O
O O O • p
Figura PS-1S

<!-- p. 289 -->

PROBLEMAS 289

S-16 Selecciónese el angular individual más ligero para una carga a tensión de 220 kN, suponiendo
que hay un tornillo de 20 mm de diámetro en la sección critica. El miembro tiene 4.3 m de largo. Usese
acero con F; = 345 MPa, el patrón de tornillos de la figura P5-15, y las especificaciones del AISC y la
AASHTO. Supóngase que en el caso de la AASHTO no hay inversión de esfuerzos.
S-17 Diséñense los miembros de la cuerda inferior para satisfacer la tensión en la armadura del cobertizo lateral del ejemplo 2-5, usando una sección WT (te estructural), tornillos de 7/8 pulg de diámetro,
acero A-36, y las especificaciones del AISC. Supóngase que hay dos pernos en la sección critica del alma de la te. La te es continua en la junta critica.
Respuesta: WT9 x 27.5.
S-18 Diséñese el miembro 5 de la figura E5-7, usando una sección W12, si la salida de la computadora
(incluyendo el impacto) es:

Carga muerta = 160.51 kips
Carga viva 77.17 kips (maxima)
Carga viva - 5.81 kips (minima)
Usense las especificaciones de la AASHTO y acero A-36.
Respuesta: WI2 x 53.
S-19 Diséñese el viento para el nivel de 200 m de la antena de TV del ejemplo 5-8.
S-20 Diséñense los tensores de los largueros de la figura P5-20. El claro de los largueros es de 28 pies y
están espaciados 8 pies c.a.c. El tensor está a la mitad del claro del larguero. La pendiente del techo es
como se muestra en la figura.
Carga muerta = 25 lb/pie? de superficie de techo
Carga viva = 45 lb/pie? (proyección horizontal)
Usese acero A-36 y las especificaciones del AISC.
. Respuesta: Diámetro = I 1/8 pulg.

45lb/pie2

\------6 (a 8'-------+1 Figura PS-20

5-21' ¿Cuál será la carga máxima permisible a tensión para una CI2 x 25 conectada a una placa de
conexión de 112 pulg, como se muestra. en la figura P5-21. Usese acero A-36 y las especificaciones del
AISC. Hállese también el ancho minimo de la placa de conexión en la última hilera de tornillos en la
canal.
Respuesta: 154 kips.

Cl2 x 25
I
IV)I~- ---tl~p
100
I

Figura P5·21

<!-- p. 290 -->

290 DISEÑO DE MIEMBROS A TENSION

5-22 Cuál será la carga máxima permisible a tensión para una W310 x 52.1, conectada a un par de
placas de conexión de 12 mm, como se muestra en la figura P5-22, con cuatro agujeros en cada sección critica. Usese Fy = 250 MPa y las especificaciones del AISC.
Respuesta: 978.5 kN.

20mm

W3]O X 52.]

(~60-l 1-2::=J: ::
FiguraP5-22

5-23 Resuélvase el problema 5-21 usando las especificaciones de la AASHTO. No se considere la
fatiga.
5-24 Resuélvase el problema 5-22 usando las especificaciones del AREA. No se considere la fatiga.
Respuesta: 747.4 kN.
5-25 Repítase el ejemplo 5-10 usando un solo angular.
Respuesta: L3 112 x 3 x 7/16.
5-26 Repítase el ejemplo 5-10 si la longitud del miembro de la armadura es de 14.5 pies en lugar de
11.5 pies.
5·27 Dada la cuerda inferior de una armadura que usa un par de C200 x 17.11 colocados espalda con
espalda, con una placa de conexión de 15mm entre las mismas y usando dos tornillos A-325 de 25 mm
de diámetro en la sección crítica y para una fuerza por carga muerta en la barra de 120kN, ¿cuál será
la máxima fuerza por carga viva en la barra que se permitirá si se usa FL = 1.67? UseseFy = 250 MPa
y una longitud de panel de 5.1 m. Supóngase cuando menos tres conectores en la línea de esfuerzo y
las especificaciones del AISC, cuando sean aplicables.
Respuesta: LL = 365 kN.
5-28 Diséñese el miembro de la cuerda inferior (No. 12) de la armadura del puente de carretera del
ejemplo 5-7(refiérase a la figura E5-7) usando una sección armada. Usenselos ejemplos 6-7 y 8-3como
guía para seleccionar las secciones laminadas que se usarán para formar la sección. Cargas: muerta =
336.9 kips (tensión); máxima viva = 123.8 kips (tensión); viva mínima = 0.0 kíp. Usenselas especificaciones de la AASHTO, tornillos de alta resistencia de 7/8 pulg de diámetro, y acero A-36. Longitud
del panel = 25 pies, como se muestra en la figura E5-7.

<!-- p. 291 -->



<!-- p. 292 -->

Figura VI-l Miembro a compresión, poste termmal de un puente. til poste termmal es armado y la construccíón es toda soldada. Las juntas se fabrican en el campo, utilizando tornillos de alta resistencia.

<!-- p. 293 -->

CAPITULO
SEIS
COLUMNAS Y PUNTALES AXIALMENTE
CARGADOS

6-1INTRODUCCION

Comúnmente a los miembros verticales a compresión en una estructura se identifican como columnas (en textos extranjeros) a veces se les llama montantes. En
ocasiones a 105 miembros verticales a compresión se les llama postes. Los
miembros diagonales a compresión que forman parte de la cuerda superior de los
accesos del puente son los postes terminales. Las diagonales de una armadura o
los miembros usados en el contraventeo se pueden llamar puntales. Los miembros
cortos a compresión en la unión de las columnas y las armaduras de techo se
pueden llamar puntales de rodilla. Sin embargo, en todos los casos. el miembro
considerado soporta una carga a compresión.
Un miembro estructural que soporte una carga a compresión se llama columna, si la longitud es suficientemente grande. Para longitudes menores el miembro
puede llamarse bloque de compresión. La longitud que divide estas clasificaciones es tal que afecta el esfuerzo máximo de compresión que se puede desarrollar debido a la carga. Al describir el comportamiento de una columna, raras
veces se usa solamente la longitud. Se usa más bien, como una consecuencia de
la fórmula de Euler para las columnas, que se deduce en la sección siguiente, la
relación entre el largo de la columna y el radio de giro, L/r.
Las pruebas indican cuando la relación L/r es igual o mayor que los valores
límites dados, el miembro muestra comportamiento de columna; por debajo de

293

<!-- p. 294 -->

294 COLUMNAS Y PUNTALES AXIALMENTE CARGADOS

Material L/r límite (aproximadamente)

Acero 60
Alumnio 30
Madera lO

este valor de Lrr, el miembro es un bloque de compresión. Un miembro, con una
relación L/r de 60, tiene una longitud sustancial, de manera que el término "bloque de compresión" es un nombre mal aplicado.
El diseño de columnas es considerablemente menos exacto que el diseño de
una viga, por diversas razones, que incluyen las siguientes:

\1. La dificultad de determinar el punto exacto de demarcación entre los bloques
de compresión y las columnas.
\2. Las columnas, aunque parezcan rectas y homogéneas, pueden tener pequeñas
imperfecciones y siempre tienen esfuerzos residuales de las operaciones de
fabricación, tales como el laminado, el enfriamiento, etc. Cualesquiera peque-
ñas imperfecciones darán por resultado una excentricidad neta con respecto a
un (o los dos) eje y producirá deflexiones laterales (pandeo) debido al momento
flector que se produce, como el producto de carga x la excentricidad.
\3. A menudo es difícil aplicar una carga por el centro del área (es decir, aplicar
una carga verdaderamente axial).
\4. El carácter de las restricciones en los extremos afectan de manera pronunciada
el comportamiento de la columna. Por ejemplo, las cuerdas superiores de las
armaduras son generalmente miembros a compresión. Las armaduras se ana-
lizan generalmente como si tuvieran juntas de pasador. El lector estará lejos de
pensar de que exista realmente una junta de pasador en una estructura. Indu-
dablemente que existen muchas juntas que consisten de un gran número de
pernos o remaches, que pasan por placas de conexión para constituir una jun-
ta en el miembro. Además, se debe pensar cuál será el efecto producido sobre el
miembro a compresión si todos los vectores fuerza en una junta no coinciden
en la intersección proyectada.

Es evidente. de estas consideraciones, que si se produce una columna ideal,
isotrópíca.y axialmente cargada, será por accidente. Sin embargo, es conveniente
analizar una amplia clase de miembros estructurales como columnas "axialmente
cargadas", puntales, postes, o cualquiera que sea la terminología local usada para identificar el miembro a compresión.

6-2 LA FORMULA DE EULER PARA COLUMNAS

Una de las fórmulas más populares de columnas que jamás se haya propuesto (y
existe un número muy grande) fue la deducida aproximadamente en 1759 por el

<!-- p. 295 -->

LA FORMULA DE EULER PARA COLUMNAS 295

matemático suizo Leonhard Euler. La fórmula se puede deducir con facilidad de
la siguiente manera (refiérase a la figura 6-1). Al escribir la ecuación fundamental
de flexión para el momento,

se tiene, para el caso de Euler, que el momento es Px, de modo que

(o)

donde el signo negativo de M, es el resultado de pasar de +dy/ dx en el origen a
\<dy/dx para y v- L, de manera que el cambio de pendiente ha de tener un valor
negativo. La solución clásica general para la ecuación diferencial de la forma de
la ecuación (a) es

CO~ ley (b) x = A senky + B
donde
(e)

r; r;

\+x

\1. Rodillo

\+y
L

\2. Articulada

(a) (b)

Figura 6-1 Columna ideal bajo las condiciones de pandeo de la columna de Euler, (o) Caso general
con n = 1. (b) Segundo modo de pandeo (n=2).

<!-- p. 296 -->

296 COLUMNAS Y PUNTALES AXIALMENTE CARGADOS

Con condiciones límite de x = Opara y = O, se obtiene B = OYla ecuación (b) se
convierte en

x=A sen ky (6-1)
Como x = Opara y =L, o bien A =O, o sen ky =o. Si A =O, no hay deflexión del
perfil, de modo que la solución debe obtenerse usando sen ky =O. Esto será solamente posible para valores de kL, como sigue:

kL = w,2w,3w, .. . ,nw (d)
yen general
k = nw (e)
L

Usando las ecuaciones (e) y (c) para obtener P, se tiene que

(6-2)

Esta ecuación para la carga crítica de pandeo, P, se conoce generalmente como la
ecuación de Euler (y la carga es la carga de Euler; el esfuerzo, el esfuerzo de
Euler).
Dividiendo ambos lados de la ecuación (6-2) por el área de la columna, A,
se obtiene, teniendo en cuenta que el radio de giro de la sección r = .JI/A, Fcr =
Pe/A, y que n = 1 da el valor mínimo de Pcr(o Fcr):

(6-3)

Es evidente que si n = 2, se obtiene de la ecuación (6-2)

que es equivalente a la columna que contiene dos sinusoides en la longitud L. A
esto se le llama el segundo modo de pandeo, n = 1 es el primer modo de pandeo
(una sola sinusoide), y resulta evidente, de la ecuación (6-2), que la carga mínima
crítica de pandeo (o esfuerzo) se obtiene con el primer modo de pandeo.
La inspección de la ecuación (6-3) indica que se pueden obtener valores muy
grandes de Fer haciendo L/r-O. Al escribir la ecuación diferencial de flexión
[Ecuación (a)], sin embargo, está implícito que el esfuerzo es proporcional a la
deformación. Resulta por tanto que el límite superior de validez es el límite proporcional, que se toma a menudo como Fcr-Fy•

<!-- p. 297 -->

COLUMNAS CON CONDICIONES DE EXTREMO 297

6-3 COLUMNAS CON CONDICIONES DE EXTREMO

La rotación de los extremos de las columnas en los edificios está restringida por las
vigas que se conectan con ellas. Los extremos de los miembros de las armaduras
están similarmente restringidos. En ambos casos, se puede realizar el diseño sobre
la base de extremos con pasadores. Nótese que la deducción de la ecuación de
Euler se hizo para una columna perfectamente recta y con pasadores en los extremos. La deducción de la carga crítica de pandeo en columnas con diversas restricciones terminales se puede efectuar de una manera similar a la del caso de Euler.
Esto se demostrará para la columna con extremos fijos que se muestra en la figura 6-20. La ecuación diferencial de flexión se convierte entonces en

(J)

Usando como antes el método.normal de solución y teniendo en cuenta que se ha
añadido sencillamente una constante, se obtiene

M
c~s ky - / (g) x = A senky + B

donde k= (P/El)Y2, como antes. Para condiciones límites de x=O paray=O y L,
se obtienen las constantes A y B:

Mo( 1 - cos kL ) x =P sen kL senky + cos ky - 1 (h)

Tomando la derivada dx/dy para la pendiente, se obtiene

dx kMo( 1 - cos kL ) - = -- cos ky - k senky (i)
dy P senkL

Como dx/dy eñ, paray=O, se tiene

kMo 1 - cos kL = O
P senkL

La menor de las raíces de esta ecuación da kL=27r, y con k=(P/El)lh., se tiene

4.,,2EI .,,2EI .,,2EI
P=--= =-- 2 L (0.5L)2 (KL)2

<!-- p. 298 -->

298 COLUMNAS Y PUNTALES AXIALMENTE CARGADOS

r:

X

\'
MOL

y L11

Figura 6-2 Columna con mo-
";1 mentos en los extremos; (a) en
.;;;r ambos extremos; (b) articulada
en un extremo y fija en el extre-
(al (b) mo de la base. 1

o sea, la longitud efectiva de la columna KL es L/2 =0.5L YK =0.5. Con esto se
introduce uno de los primeros intentos de ajustar la longitud de la columna a las
condiciones terminales. La longitud efectiva KL, o algún otro concepto equivalente, se usa en casi todas las fórmulas de diseño de las especificaciones de construcción.
Cuando el tope de la columna está fijo contra traslación y la base está fija
contra tanto la traslación como la rotación, como se ve en la figura 6-2b, se puede
reescribir la ecuación if) como
d 2x y El = -Px + M- dy2 0L
Yobtener de una manera similar

o sea, K =0.7. En la figura 6-3 se muestran algunos de los casos más corrientes de
fijación de los extremos de las columnas.·
Estrictamente hablando, y de acuerdo con la derivación de estas ecuaciones
para la carga critica de pandeo, el módulo tangente de elasticidad; Et, debe sustituir al módulo elástico en la ecuación (6-3) cuando el esfuerzo en la cohimna sea
mayor que el limite proporcional. El concepto de módulo tangente se trató en la
sección 3-7.

6-4 ESFUERZOS PERMISIBLES EN LAS COLUMNAS DE ACERO

El esfuerzo en la columna, obtenido con la ecuación de Euler

'lT2E F =---
cr (KL/r)2

<!-- p. 299 -->

ESFUERZOS PERMISIBLES EN LAS COLUMNAS DE ACERO 299

(a) (h) (e) (d) (e) (n
\~
J ~~ ~ ~ ~~ r!;-T~ ~+~ ~ ¡1-r I I \ / J I
I I \ I I
I I I \ I I
I l I I I I I I \ / I I I
\ \ / I I
\ \ / I I
\ \ I I
\ I I
I / ~f~ ~r ~f~ It~ ~ ~t ~

K teórico 0.5 0.7 1.0 1.0 2.0 2.0

K de diseño que se 0.65 0.80 r.z 1.0 2.1 2.0 recomiend a

\~ Rotación fija Traslacion fija

\~y Rotación libre Traslación fija
Condiciones en
los extremo s
\~ Rotación fija Traslación libre
y Rotación libre Traslación libre

Figura 6-3 Valores de K, teóricos y de diseño, para columnas con diversas condiciones en los extremos.

está representado por la ecuación de una parábola, y parecería apropiado usar
una ecuación de forma parabólica para desarrollar el esfuerzo permisible de la columna. Similarmente, parecería apropiado que KL/r fuera uno de los parámetros
significativos. Además, como el esfuerzo de Euler es un esfuerzo de pandeo, será
necesario aplicar un factor de seguridad que tenga en cuenta este nivel de esfuerzos y tenga en cuenta, además, la excentricidad, esfuerzos residuales, y los otros
varios factores que complican la teoría. Sería también apropiado usar un factor
variable de seguridad que tuviera en cuenta el efecto reductor de algunas de estas
variables según disminuye la longitud (o la KL/r). Por ejemplo, una pequeña excentricidad no es tan crítica para una columna corta como para una larga y esbelta, etc. Hechas estas consideraciones se pasará a investigar la ecuación para columnas axialmente cargadas del AISC.

6-4.1 Esfuerzos de diseño para columnas axialmente cargadas,
según el AISC

Se desarrollan los esfuerzos de diseño del AISC, tomando la ecuación de Euler
para el esfuerzo crítico, para tener, con n =1

<!-- p. 300 -->

300 COLUMNAS Y PUNTALES AXIALMENTE CARGADOS

",2E
F = ----:-
cr (KL/ r)2
y obtener por diferenciación

d(!'er) (o)
d(KL/r)

Como el valor máximo del esfuerzo de Euler, o cualquier otro esfuerzo crítico de
pandeo, está limitado a Fy , se pasará a definir el esfuerzo crítico en cualquier
región donde no sea válido el esfuerzo de Euler (como para pequeños valores
de KL/r):

KL)P (b) r F cr =F-m-y (

Se puede diferenciar esta ecuación para obtener

d(Fer) = _ (KL )P-t (e)
d(KL/r) mp r

Se tomará la pendiente d(Fer)/d(KL/r) = Oen KL/r = O. Además, en algún lugar
en donde se definirá arbitrariamente un parámetro.

las pendientes de las ecuaciones (o) y (e) serán iguales (es decir, las dos curvas definidas por estas dos ecuaciones separadas tendrán una tangente común). Además, los datos experimentales de pruebas en columnas indican que es adecuado
tomar p = 2. Ahora bien, igualando las pendientes para KL/r= CeYparap=2, se
obtiene

de donde se obtiene m como

(d)

Al reordenar la ecuación (b), insertando KL/r= Ce' p = 2, Yutilizando el valor de
Euler para Fer, se obtiene

(e)

<!-- p. 301 -->

ESFUERZOS PERMISIBLES EN LAS COLUMNAS DE ACERO 301

y resolviendo para Ce se obtiene,

(6-4)

Si se insertan en la ecuación (b) los valores de m, p, y C, se obtendrá

7T2EC 2
e = F;, - 0.5F;, = O.5Fy Fcr = F;, - C 4
e

Por tanto, el esfuerzo crítico de pandeo se convierte en 0.5Fy para KL/r = Ce, siguiendo las suposiciones hechas. En general, se tiene el esfuerzo de pandeo, de la
ecuación (b), como:

F = F[l O _ 0.5(KL/ri ] (j) y' cr C 2
e

y se obtiene el esfuerzo permisible para KL/r~Ce, a partir de la ecuación (f).
...Jr F = Fcr =(. :F;, [1.0 _0.5(KL/r)2] (6-5) ~ a FS .FS C 2 '/' e

El AISC ha utilizado desde 1963, el siguiente factor variable de seguridad:

(6-6)

para todos los valores KL/r";?Ce. Para KL/r>Ce se usa un valor constante del
factor de seguridad basado en el uso de KL/r= Ce en la ecuación anterior para
obtener

FS = 23 =(1·92 12 \.

Cuando KL/r> Ce, se usa la ecuación de Euler, con FS=23/12, para obtener el esfuerzo permisible en la columna como

(6-7)

Con valores normales de rE, se obtiene:

pie lb seg F = 149 000 kip/pulg-
a (KL/r)2

<!-- p. 302 -->

302 COLUMNAS Y PUNTALES AXIALMENTE CARGADOS

F = 1.03 X 1()ó SI: MPa
a (KL/r)2

Se usan las ecuaciones (6-5) y (6-7) para miembros principales a compresión. Se
pueden diseñar los miembros secundarios a compresión para un esfuerzo permisible basado en el siguiente factor de amplificación que utiliza Llr (K = 1) cuando
Llr excede 120:

i' = 1 (6-8)
1.6 - L(200r)

Se obtiene el esfuerzo permisible de diseño usando ya sea la ecuación (6-5) o la
ecuación (6-7):

Las ecuaciones (6-5) a (6-7) son algo complicadas para los cálculos de rutina
(aun con los calculadores programables de escritorio), y es conveniente escribir
un programa de computadora para producir una tabla de Fa vs KLlr para valores
varios de Fy , que aparecen en las tablas 11-5, 11-6, YVI-5, VI-6. El manual del
AISC tiene tablas más completas que utilizan los varios grados de F; de uso común, incluyendo el factor de amplificación de las ecuaciones (6-5) Y(6-7) para los
miembros secundarios cuando Llr> 120.

6-4.2 Esfuerzos de diseño para columnas axialmente cargadas,
según la AASHTO

Las fórmulas de la AASHTO para columnas cargadas axialmente se derivan similarmente a los valores del AISC, pero el FS tiende a ser más conservador, ya que
los miembros de la estructura del puente están, en general, en un ambiente más
hostil que los miembros de los edificios. Las fórmulas de la AASHTü son las siguientes:
Para KLlrs.Ce;

F = (KL/r)2] (6-9) F;, [1 _0.5
a FS C 2 e
Para KLlrs.Ce
.,,2E F =-_...:..-- (6-.10)
a FS(KL/r)2

El FS=2.12 para las especíñcactones de la AASHTü y los valores del factor de
longitud K y Ce se calculan igual que para las especificaciones del AISC. En la

<!-- p. 303 -->

ESFUERZOS PERMISIBLES EN LAS COLUMNAS DE ACERO 303
tabla 6-1, se dan los valores de e e para los diversos valores de F y usados comúnmente en las fórmulas de columnas.
Tabla 6-1 Valores de Ce de acuerdo con las espe-
cificaciones del AISC y la AASHTO, para-valo-
res varios de Fy; Ce = (2TEIFy )'I2

Fy
pie-Ib-seg, kíp/pulg2 SI,MPa Ce

36 250 126.1
42 290 116.7
46 315 1l1.6
50 345 107.0
60 415 97.7
65 450 93.8

6-4.3 Esfuerzos de diseño para columnas axialmente cargadas,
según el AREA

Las fórmulas del AREA para los esfuerzos permisibles de diseño de las columnas
son algo parecidas a las fórmulas de la AASHTO y el AISC, y son las siguientes:

Limitación Esfuerzo permisible

kL 107 -\<-- Fa = 0.s5Fy (6-11) r - 'ÍFy
Fy )I.S --\<-~--107 kL 857 (6-12) Fa = 0.6Fy - ( 166.2 . rkL ~r~
kL 857 F _ 147000 ->-- (6-13)
r a (kL/r)2 Vi.y

En las especificaciones del AREA,

F; kip/pulg-
k = 0.75 para las conexiones remachadas, atornilladas o soldados de los
extremos de los miembros a compresión
0.875 para los miembros con extremos articulados

6-4.4 Area de la sección transversal de las columnas,
neta versus bruta
El área neta (=área bruta - la pérdida por los agujeros) se usa en el diseño de
miembros a tensión. En el diseño de cualquier conexión que use conectores mecá-

<!-- p. 304 -->

304 COLUMNAS Y PUNTALES AXIALMENTE CARGADOS

nicos (remaches o tornillos), se supone que el conector llena completamente el
agujero. Esta suposición casi se cumple en las operaciones de remachado, donde
la fabricación de la cabeza ensancha el vástago del remache, y ocurre en su casi
totalidad en las operaciones de atornillado, puesto que el agujero tiene un tamaño
que es sólo mayor en aproximadamente 1.5 mm que el diámetro nominal del tornillo. Bajo compresión axial, aunque existen concentraciones de esfuerzos en el
agujero, se puede suponer con seguridad que no ocurre pérdida alguna de área
neta cuando el conector mecánico llena completamente el agujero. Cuando hay
un agujero intermedio abierto en un miembro a compresión (para servicios, montaje, etc.), el diseñador debe aplicar su criterio para decidir si se usa el área neta o
el área bruta. Las especificaciones del AISC dan el esfuerzo permisible "sobre la
sección bruta de los miembros a compresión axialmente cargados..." Habrá
siempre, indudablemente, un adecuado efecto de arqueamiento para transmitir la
carga alrededor del agujero si se pierde solamente una pequeña cantidad del área
en cualquier sección, a causa de los agujeros. El procedimiento más conservativo
sería usar la sección bruta cuando el agujero tiene un conector mecánico que lo
llena o casi lo llena, y la sección neta en todos los demás casos.

6-4.5 Diseño de las columnas

Es necesario utilizar un proceso iterativo en el diseño de los miembros a compresión usando cualesquiera de las ecuaciones para el esfuerzo permisible, ya sea del
AISC, AASHTO, o AREA, El problema usual de diseño abarca los pasos siguientes.

l. Determinénse las cargas de la columna (a menos que el problema envuelva sola-
mente comprobar lo adecuado de una sección).
\2. Determínese la longitud efectiva de la columna, KL (o k para el AREA).
\3. Hágase una selección tentativa de la sección (a veces se puede hacer uso de
tablas tales como la tabla 11-4 o la tabla VI-4 del SSDD).
\4. Calcular KL/r para la sección seleccionada (ahora que se conoce r) y ÚSese la
ecuación apropiada para calcular Fa (o úsense tablas como la 11-5 del SSDD,
que da Fa para varias relaciones de KL/r).
\5. Calcular la carga permisible sobre la columna, P¿=A x Fa?:,Pdiseño
\6. Revisar la sección hasta que P¿esté razonablemente cerca (y sea ligeramente
mayor) de la P de diseño Se obtiene la sección más ligera (aunque no necesa-
riamente la más económica) cuando P, = PdiseñO.

Se deben considerar dos factores adicionales:

\1. Generalmente, sólo se usan como columnas las secciones W8, WlO, W12, y
W14, y las secciones de tubo rectangulares y redondas, ya que el radio crítico
de giro es con respecto al eje Y. Estas secciones tienen los mejores valores de ry
(y las correspondientes relaciones rx/ry). En el diseño de edificios, es necesario

<!-- p. 305 -->

ESFUERZOS PERMISIBLES EN LAS COLUMNAS DE ACERO 305

a menudo, por consideraciones prácticas, usar un tamaño nominal dado para
las columnas en todo el edificio. Es común en la construcción de edificios ex-
tender una columna cuando menos por dos; y frecuentemente tres o más pisos,
para evitar empalmes de columnas en el campo. El ahorro en mano de obra
más que compensa el aumento en el peso del acero.
\2. Cuando KLlr> Cc' las especificaciones del AISC requieren el uso de la
ecuación (6-7)flas especificaciones de la AASHTO requiere la ecuación (6-10),
y el AREA tiene un requerimiento algo similar para la ecuación (6-13)/ En
t-odas estas ecuaciones, Fa es independiente de F; Por tanto, en el diseño de co-
lumnas, se debe usar acero A-36 para todos los casos en que KLlr exceda a Ce."
O a las limitaciones del AREA, y aún si se usa F,> 36 kip/pulg-, para algunos
de los otros miembros. Por ejemplo, si se usa F; = 60 kip/pulg-, y se encuentra
una sección donde KL/r> 97.7 (refiérase a la tabla 6-1), se debe tratar de espe-
cificar acero A-36 en lugar del acero más costoso de 60 kip/pulg-, El factor de
seguridad ligeramente más alto de la ecuación (6-7) permite hacer la transición
entre XLIT: ~Ce = 126.1(para el acero A-36) y los valores más bajos de Cc para
los aceros de más alta resistencia.
Debe aproveeharse cualquier tipo de que se disponga de ayuda para hacer la
selección preliminar de la columna. Se pueden usar a menudo tablas tales como
la tabla 11-4 o VI-4 del SSDD, para hacer el diseño final. Las tablas 11-5 y 11-6, Ylas
correspondientes tablas SI (tablas VI-5 y VI-6) se pueden usar provechosamente
para cualesquiera otros perfiles (que incluyen las secciones W), para rápidamente
obtener Facuando se calcula KLlr particularmente cuando KL/r\< Cc' puesto que
tanto el esfuerzo como el factor de seguridad dependen ahora de KLlr.

6-4.6 Ejemplos de diseño

El diseño de columnas y puntales simples y axialmente cargados, se ilustrará en
los ejemplos siguientes.

Ejemplo 6-1 Diséñese una columna que se usaría en un edificio comercial.
Las columnas tienen sus centros espaciados 20 pies en cada dirección. La car-
ga del techo se toma como 30 lb/piel para la carga muerta y 60 lb/piel para
la carga de nieve. Esto da una carga sobre la columna de 20(20)(0.090) .= 36
kips. Se usará acero A-36 (Cc=126.1).

SOLUCION De la inspección de la figura E6-1, se toma K= 1. Usando la
tabla 11-4 como guía, la sección W más ligera (W8x 18), para KL = 14 pies,
puede soportar 4 kips. Esto podría ser una solución pero no sería muy econó-
mica. Se comprobará primero esta sección W8 y luego se comparará con una
'columna de tubo.
Se comprueba primero la sección W8 x 18:

A = 5.26pulg-

<!-- p. 306 -->

306 COLUMNAS Y PUNTALES AXIALMENTE CARGADOS

KL = 14(12) = 136.6 > Ce [se usa ecua- ry 1.23 ción 6-7]
149 000 . F = = 7.99 kip/pulg-
a (136.6)2
Pa = 5.26(7.99) = 42.0 > 36 kips Correcta

Se usará una sección W8 x 18 (tentativamente); el valor de 41 kips de la tabla
11-4 se debe al redondeo de la computadora.
Se investigará también una sección de tubo (ver tabla 1-14). Ahora que se
tiene alguna "experiencia" pues se acaba de analizar un perfil W, se investi-
gará un tubo de 4 pulg de diámetro:

rx = ry = 1.51 pulg A = 3.17 pulg- wt = 1O.791b/pie
\~L = 1~~¡) = 111.25 \< Ce

De la ecuación (6-5),

F = ~[1 O _ 05( 111.25)2] = 21.98
a FS' . 126.1 FS

De la ecuación (6-6) se calcula el factor de seguridad como

"12~~15 ) - 0.125( FS = 1.67 + 0.375( "12~~:r
\= 1.915
21.98 k' 2 ( Fa = 1.915 = 11.5 ip/pulg vs. 11.54 en la tabla 11-5)
Pa = 11.5(3.17) = 36.45 > 36 kips Correcta

Se usará la tubería de acero de 4 pulg x 10.79 lb/pie.
Nótese que la tubería y cualesquiera otras secciones donde rx/ry- l son
generalmente los perfiles más económicos cuando KLx =KLy • / / /

Ejemplo 6-2 Diséñ.ese una sección W para las condiciones que se muestran
en la figura E6-2. Úsese Fy = 50 kip/pulg- para el acero yfas especifica-
ciones del AISC.

SOLUCION
KLx = 16 pies
KLy = 8 pies

<!-- p. 307 -->

ESFUERZOS PERMISIBLES EN LAS COLUMNAS DE ACERO 307

"1-
,------, I I
I loO' I ¡-
Sección W I Col. Viga ¡
I O I
I I
I I
I I
IL 20' JI

Figura E6-1

Se puede usar la tabla 11-4para obtener una estimación inicial del tamaño de
la columna. Como la tabla 11-4se basa en F, = 36 kip/pulg-, se usará la re-
lación
Pequiv = (750) ~~ = 540 kips

Como la tabla se basa en KL/ry, se nota que rx/ry ~ 1.6 en los tamaños de
columnas que se acercan a P = 540 kips; por tanto se busca L = 1.6 x 8 =
13 pies para la longitud de la columna, y 540 kips.
Pruébese W 14x 99:
r. = 1.66 A = 29.10 pu l g2 ry = 3.71 pu l g - ry
Calcúlese
rx = 1.66ry - 1.66(3.71) = 6.16 pulg
KL _ 16(12) _ 31 2 controla ya que es el mayor
rx 6.16 .
KL = 8(12) _ 25.9
ry 3.71

<!-- p. 308 -->

308 COLUMNAS Y PUNTALES AXIALMENTE CARGADOS

Trabe de carga I
f f •
T

Viga de bor de
l oo oo Canal >

8' 8't
I
11 11 1 Cimentació n 1 lO ) .. 1

Figura E6-2 I

Ce = 107 (Tabla 6-1)
F = 50 [10 _ O5( = 47.9 31.2)2] a SF' . 107 FS

;~J) 1.78 FS = 1.67 + 0.375( -0.125( ;~Jr=
Fa = ~~7: = 26.9 ksi (a: 27.0 en tabla 11-6)
Pa = 26.9(29.10) = 782.8 > 750 kips Correcta

Esta sección laminada parece ser la más ligera para esta situación de carga.

Ejemplo 6-3 Revísese el par de angulares seleccionados en el ejemplo 5-6,
para ser usados como miembros verticales en la armadura principal de techo
del ejemplo 2-6. Úsese acero A-36 y las especificaciones del AISC.

Miembro LC-l (kN) LC-2(kN) L,ro

39 -63.65 +20.39 6.76
47 +70.18 -37.60 8.2

La sección seleccionada para las consideraciones de tensión era
2Ll27 x 89 x 6.3: A = 2.66 X 10-3 m2 rmío = 37.5 mm

<!-- p. 309 -->

ESFUERZOS PERMISIBLES EN LAS COLUMNAS DE ACERO 309
SOLUCION Tómese K = l. Para el miembro 39:

KL = 6.76(1000) = 180 \< 200 Correcta
r 37.5

Para el miembro 47:

\~L = ~.2~~~) = 218.7 > 200 máx (AISC Sección 1-8.4) N.S.

Se revisa la sección para el r mínimo:

8.2(1000)
r mín = 200 = 41 mm

Nótese que se usa una placa de conexión de 12 mm entre los angulares en la
conexión. Los posibles angulares son:

2Ll52 X 152 X 7.9: r mín = 48.0
A = 4.71 > 0.5504 (requerida por tensión)
2 Ll52 X 102 X 6.3: r mín = 41.5 mm
A = 3.15 > 0.5504

Se comprobará el par de angulares 152x 102x 6.3, ya que son los más ligeros.
Miembro 47:

\~L = 8.2~:~) = 197.6~ Fa = 26.3 MPa (TablaVI-5)
Miembro 39:
\~L = 6.7~\~c;x') = 162.9~ Fa = 38.8 MPa
P39 = 38.8(3.15) = 122.2 kN > 63.65 Correcta
P47 = 26.3(3.15) = 82.8 kN > 37.6 Correcta

Se usarán dos Ll52 X 102X 6.3. Se notará que el Llr controló el diseño, tanto
en tensión como en compresión.

Ejemplo 6-4 Diséñese el miembro 7 de la armadura para puente de carretera
de la figura E6-4 (la misma armadura que en el ejemplo 5-7).

<!-- p. 310 -->

310 COLUMNAS Y PUNTALES AXIALMENTE CARGADOS

\------(Ir)---7 paneles 25' = 175' ----fl-(----.. Figura E6-4

SOLUCION Resultado de la computadora:

Carga muerta -56.75 kips
Carga viva -42.56 kips
Carga-viva +16.11 kips

Nótese que este miembro tiene una longitud efectiva fuera del plano de 17
pies (como en el ejemplo 5-7) debido al ensamblaje del contraventeo horizon-
tal y transversal por sobre el tope de las dos armaduras que forman el puen-
te. El factor de impacto se ha incluído en la carga viva, pero se calcula como
sigue:
50 50
1 = L + 125 = 300 = 0.17

Fuerza máxima en la columna = 56.75 +42.56=99.3 kips (compresión)
Fuerza mínima en la columna = 56.75 - 16.11 = 40.6 kips (compresión)
\- Pmín = 99.3 - (+40.6) = 58.7 kips (rango de esfuerzos) Psr = Pmáx

Las especificaciones de la AASHTO (Sección 1-7.5) limitan KL/r para
los miembros a compresión de KL/r= 120 para los miembros principales o
miembros que estén sometidos a esfuerzos por carga muerta y.carga viva. El
r mínimo es

r mín = 2~~~) = 2.50 pulg

Pruébese una sección W12, puesto que se ha usado una W12 x 53 para el
miembro 9 en el ejemplo 5-7, que se conecta en la junta en un extremo de
este miembro. Una placa de conexión puede cubrir ambos miembros con un
mínimo de material de relleno, si todos los miembros del alma tienen el mis-
mo peralte nominal.
Se nota, además, que la ecuación (6-9) siempre determina el esfuerzo en
la columna para miembros que usan el acero A-36, ya que KL/r-::: 120 y Ce =
126.1> 120.
Por ensayos [y programando la ecuación (6-9) con una calculadora
programable de bolsillo]:

<!-- p. 311 -->

ESFUERZOS PERMISIBLES EN LAS COLUMNAS DE ACERO 311

Sección Asum• pulg2

WI2x53 15.60 2.48 No. bueno. porque ryes demasiado pequeño
W12x58 17.00 2.51 9.35 159.0>99.3 Correcta

El valor rx de la W12 x 58 es 5.28>2.5, de manera que la sección es satisfactoria. Además, esta sección tiene el mismo tamaño que el miembro 9,
por lo que será fácil fabricar la junta. Se usará una sección W12x 58.

Ejemplo 6-5 Diséñense los puntales para el techo soportado por cables del
ejemplo 5-9. La carga de los puntales es de 2.2 kips basada en cables a 4 pies
e.a.e, y los puntales como se muestran en la figura E6-5. La longitud mayor
de los puntales es de 2(23.3) = 46.6 pies.
\- - -
L
Figura E6·5

SOLUCION La máxima KL/r para miembros a compresión está limitada a
\200. Según las especificaciones del AISC, esto requeriría un radio de giro de
cuando menos

r = 1(4~~(12) = 2.80 pulg

En general, se usan puntales de tubo con un rango de diámetros de 4 a 6
pulg. Se tiene en este caso una longitud no soportada lateralmente bastante
grande, por lo que el examen de la tabla 1-14 (SSDD) indica que se puede
usar:

Tubo extra resistente: 8 pulg de diámetro: r=2.88 > 2.80 pulg
A =12.8 pulgPara KL/r = 46.6(12)/2.88 = 194.2,
Fa = 3.95 kíps/pulgz (tabla 11-5)
\~ 2.2 kips P peno = AFa = 12.8(3.95) = 50.6

<!-- p. 312 -->

312 COLUMNAS Y PUNTALES AXIALMENTE CARGADOS

Se usará una tubería extra resistente de 8 pulg de diámetro. Puede ser pro-
vechoso usar una sección menor en la cuarta parte exterior del claro, donde
el valor de L = 2h es menor de 46.6 pies.

6-5 DISEÑO DE MIEMBROS ARMADOS A COMPRESION

En muchas situaciones, una sección armada resulta un diseño más práctico que el
uso de un perfil laminado. Esto es especialmente cierto cuando se trata de una
longitud muy grande de columna sin apoyo lateral, lo que necesitaría el uso de
uno de los perfiles laminados de mayor peso para poder cumplir los requerimientos de L/r. Otro factor de primaria importancia es que el radio de giro de los
miembros armados se puede controlar de manera tal que se haga que el valor de rx
sea lo más parecido posible a ry, para producir la máxima eficiencia de la sección
(véase la tabla 6-2 para una selección de ejemplos). Esta eficiencia no se puede obtener con el uso de los perfiles laminados W normales, donde la relación rx/ry es a

Tabla 6-2 Radio de giro aproximado para varios perfiles armados

y
r, ; O.36h
X.~h 'x : O.29h 'v ; O.45b 'y - O.29b ft-3-J
\..-b-J Lb-l
rb1 r ; O.36h
'x ; O.25h 'y ; O.60b~ 3tfJ
b, r-
\~ :-T ,;--
H + h H 16 r ; O.4~
U ~ ,;035Hm CJ~ I1IlJR

rb~ 'y = el mismo que ¡-b,
\~iL...! para los 2 L 'x ; O.42h
'y ; O.32b .jl -3-1-Et1-1
lb, Ibl
'y = el mismo 'x ; O.39h -,r.
\- - - h queparalos2L 'y;O.2Ib
\--.JLJ --.J L--l --,rt

y Ibi
\-+-r 1..,-.h 'x ; O.4~ ~ll 'x ; O.45h t 'y ; O.235b LI...J-i 'y ; O.42b --J L..--i:
Lb-l

<!-- p. 313 -->

DISEÑO DE MIEMBROS ARMADOS A COMPRESION 313

menudo de 1.5 a 5 o mayor, a menos que no se provea coÍltraventeo con respecto
al eje Y.
Las secciones armadas se usan con mucha frecuencia en armaduras de puentes y en columnas para torres de agua. Las antenas son esencialmente columnas
armadas, aunque no se les considere directamente como tales. En cualquier caso,
cuando se usen miembros a compresión (y tensión) en claros largos sin apoyo lateral, puede que sea necesario considerar un miembro armado. Se puede usar
cualesquiera de las secciones consideradas en el capítulo 5 (refiérase a las figuras
5-4, 5-7, y 5-8) además de cualquiera otra configuración de sección, que puede
ser, o hacerse, apropiada al problema de diseño.
Es algo más difícil producir una sección armada óptima o de peso mínimo,
puesto que hay que satisfacer diversos parámetros de diseño, entre los que se
hallan:

l. Tipos de miembros a usar, que incluyen angulares laminados; canales; perfiles
W, S, o M, así como segmentos de placas.
\2. Distribución de los miembros básicos, incluyendo algunas limitaciones de ta-
maño en las dimensiones totales de la sección.
\3. Los valores resultantes calculados de Ix' Iy, rx y ry y KL/rmáx , que producen el
esfuerzo permisible de compresión.
\4. La obtención de un área aceptable de sección basada en el esfuerzo permisible
del paso 3, el que no se conoce hasta que se haya establecido el área.

Se requieren generalmente una o más repeticiones, para finalmente desarrollar una sección satisfactoria. El número de repeticiones dependerá obviamente de

l. Diseño de ingeniería versus costo material.
\2. Número de secciones a fabricar; si se han de fabricar 100 secciones, puede ser
considerable el ahorro de material, mientras que en la fabricación de solamen-
te cuatro o cinco secciones, el costo de producir un diseño refinado puede ser
mayor que el ahorro de material.
\3. Con fiabilidad de los datos de carga y uso al que se destinan los miembros ar-
mados.

En general, será satisfactorio para un miembro armado un "sobre diseño"
de un 5 a un 15 por ciento.
Las secciones armadas se pueden construir usando perfiles laminados, como
se ve en la figura 6-4, pero se construyen con más frecuencia, usando celosías,
cubreplacas perforadas o listones como se muestra en la figura 5-7. Se obtiene un
mayor radio de giro y un uso más eficiente del acero, al separar todo lo que sea
práctico, las partes que soportan las cargas (y como se hace con los patines de los
perfiles W). Cuando se proceda de esta manera, es necesario interconectar las diversas partes para que actúen como una unidad de soporte de carga. En general,
se usan diversos métodos para la utilización de celosías, listones sencillos y dobles,

<!-- p. 314 -->

314 COLUMNAS Y PUNTALES AXIALMENTE CARGADOS

(a) (bl (e)

Flcara 6-4 Perfiles armados. usando combinaciones de perfiles laminados. La geometría de la sección
está limitada solamente por la imaginación, las cargas, y los claros. (a) Cuatro angulares y una placa.
(b) Dos canales y un perfil S. (e) Dos canales y un perfil S.

y placas perforadas (las que se conocen colectivamente como cubreplacas). Cuando se coloca el acero dentro de un edificio, las cubreplacas pueden ser sólidas, y su
uso reduce los costos de fabricación. En ambientes exteriores, en donde la corrosión es siempre un problema, es necesario tener acceso al interior de la sección para
mantenimiento e inspección; de otro modo, el interior tendría que estar totalmente
sellado. Las cubreplacas "abiertas" y las celosías permiten el acceso al interior de
la sección para limpieza y pintura sin tener que recurrir a la cuidadosa fabricación
que se requiere para sellar completamente el interior. En la actualidad, parece ser
que la economía de fabricación favorece a las cubreplacas perforadas sobre las
celosías, ya que con los métodos de corte automático con gas, permiten el rápido
corte de las aberturas de la placa en una longitud de la misma.
El diseño de las celosías y los listones, en particular, requiere prestar atención
a diversos detalles. Se cree que la falta de atención apropiada en el diseño de la
celosía fue la causa de la falla, en 1907del primer puente de Quebec, en el Canadá.
Es usual asignar una porción de la carga axial como cortante desarrollado en la
celosía o los listones cuando el miembro a compresión se "pandea", como se
muestra en la figura 6-5.
Si se suponen momentos extremos iguales, como se muestra en la figura 6-5c,
y se usa la ecuación diferencial para flexión, como se hizo para deducir la
ecuación de columnas de Euler, y tener en cuenta las condiciones de borde, se obtiene
x= e(tan k~ sen ley + cos ley - 1)

La derivada para y =Oes

dx kL _.- = ke tan-
dy 2

Refiriéndose a continuación a la figura 6-5b, se obtiene para el cortante en la
celosía

<!-- p. 315 -->

DISEÑO DE MIEMBROS ARMADOS A COMPRESION 315

P

P !
J:---X
.1
1 Tómese nota de las
: limitaciones de KL' ,Ir

I
It
Y 1
9 I
dx \ V=psen9=p- \
P dY \ i

(al (bl (e)

Figura 6·5 Desarrollo del cortante para un miembro a compresión con celosías o listones. (o) Columna con celosías. (b) Identificación del cortante Ven la columna con celosías. Para celosias en los dos
lados opuestos, divídase V por igual en ambas. barras de celosía; para celosías en los cuatro úsese 90
como anteriormente. (e) Concepto básico del cortante en la celosía de la sección armada.

\~L ) v = p(ke tan

donde k=PIEI como en la ecuación de Euler. El AISC toma sencillamente

kL ke tanT = 0.02

Las especificaciones de la AASHTO y del AREA hacen la suposición de que
la excentricidad terminal e, que se muestra en la figura 6-5c, es igual y opuesta en
los dos extremos de la columna (en la figura 6-5c se muestran iguales y con el mismo signo). Con algunas simplificaciones adicionales en la ecuación precedente
para V, se obtiene

V _ p (100 L/r ). (6-14) - 100 Lfr + 10 + e/E;,

<!-- p. 316 -->

316 COLUMNAS Y PUNTALES AXIALMENTE CARGADOS
donde r, esfuerzo de fluencia del acero, kip/pulgz o MPa
Llr = valor para todo el miembro con respecto a un eje perpendicular
al plano de la celosía o la cubreplaca, como sigue:

AASHTO AREA
pie lb seg SI pie lb seg SI

3300 22920 3600 25000

Las especificaciones del AASHTO y el AREA requieren también que se aumente
V para cualquier cortante adicional sobre el miembro, tal como el peso de la sección o cualquier otra carga transversal. El viento sobre las armaduras de los puentes puede contribuir también a un aumento de V, según esta interpretación. El
valor de V obtenido por los cálculos de la AASHTO o del AREA, puede ser a tensión o compresión, y la celosía o los listones se deben diseñar de acuerdo.
\ ! El espaciamiento de la celosía y de los listones debe ser tal que el Llr de los
elementos principales entre conectores, no sea mayor que el KLlr del miembro

End
II II l' 1I Le;::: 1.25Lo :' '1
Las dimensiones que se muestran para laI cubreplaca son comunes en las especificaciones L0:-i1 ~
11 AISC. AASHTO y AREA. además:
AISC: Lo/t ~ Ca/.JF; (pie) liT 1)110 011
II Ca = 317 pie Ca = 835 SI
"I'~I$ w LI
II .., 1I AASHTO: rmln = 1.2S pulg b 30 mm
\~ 12 en miembros principales II--.l '1 L I / t ,:S C"¡¡;'
\~ :;;; 16 en miembros secundarios 01' :'0 1I 6 C = 51.4 pies/s
\= 135.5 SI l',1" o -1,
,1 --.l Lo/t ~ C2/"¡¡;' ~ 45
VI " C2 = 126.5 pies rl -o --.l " 011 = 333.4 SI 1I 1'0,1
1, ,1 Usese fa ,:S 0.44 F,.
11 ,1
11 l' L2 AREA: 11 ,1
;;: Lo/50 oompresibn 0" 'lo tptp ;;: Lo/50 tensión
'1 ;;:L¡/I2 I1
\~,-( O.35 F,.)( L 0)( L 2 11Ir además tp - 3L 2V -11 O 110 Ii
Ii

Figun 6-6 Diseño de las cubreplacas perforadas.

<!-- p. 317 -->

DISEÑO DE MIEMBROS ARMADOS A COMPRESION 317

total; de otra manera, se puede originar pandeo local, en particular cuando se
usen angulares, y el Lrr¿ entre los puntos de sujeción puede ser crítico, Actual-
mente, las especificaciones del AASHTü y el AREA limitan-la distancia entre co-
nectores a

L 2 KL -\<--
r - 3 de todo el miembro
\< 40o bien L-r -

el menor de los dos. Puede que sea necesario terminar la celosía en puntos inte-
riores, donde las placas de conexión se usan para unir los miembros transversales.
En los extremos se usan generalmente placas de asiento debido a la presencia de
las placas de conexión para unir al miembro con el resto de la estructura. En la
tabla siguiente se muestran algunos de los requerimientos para la celosía y las pla-
cas de asiento según las tres especificaciones:

AISC AASHTO AREA

K pa: celosía sencilla I I I
celosía doble 0.7 0.7 0.7

L' , celosía sencilla (Fig. 6-50) 15 pulg o 380 mm
L •, celosía doble > 15 pulg o 380 mm

ángulo a, celosía sencilla ~60°
ángulo a, celosía doble ~45°
t de la barra celosía Según se requiera Sencilla L/40
para el L/r Doble L/60
Disminúyase un 25 por cient o
para los miembros secundari os

w de la barra de celosía Según se requiera 3 x diámetro del conector

Las provisiones generales para el diseño de cubreplacas perforadas según las
variasIEl especificacionesdiseño de un miembrode diseñoarmadose resumenrequiereen cuandola figuramenos6-6. los pasos siguien-
tes:

l. Dimensiones generales externas y la carga por soportar.
\2. Se estima tentativamente el área de compresión basada en la suposición de un
valor de Fa entre 15 y 20 kip/pulg- o 100 a 140 MPa (basado en Fy=36
kip/pulg-). Esto permite una modesta reducción en el esfuerzo permisíble de
0.6 Fy debido al KL/r del perfil armado. •

<!-- p. 318 -->

318 COLUMNAS Y PUNTALES AXIALMENTE CARGADOS

\3. Decídase si se usará celosía, listones o cubreplacas (figura 5-7) o si la sección
debe ser algo como la de la figura 6-4.
\4. Calcúlese el área 1\, Iy> rx y ry. El momento de inercia de la sección armada es

donde IO(j) = momento de inercia de la partej con respecto al eje paralelo
i y pasando por el centroide de la parte j
Aj área de la sección transversal de la parte j
dj(j) distancia perpendicular desde el centroide del área j al eje i
\5. Calcúlese el radio de giro con respecto a ambos ejes.
.M Ti =vi

\6. Calcúlese Kl./r, y Kli/r; y obténgase el esfuerzo permisible de compresión,
basado en el mayor valor de KL/r.
\7. Verifíquese Pperm = AFa>Pdisello, repítase si fuera necesario.
\8. Diséñese la celosía, las cubreplacas, los listones, y/o las placas atiesadoras (o
de asientojj

Este procedimiento se ilustrará por medio de los ejemplos siguientes.

Ejemplo 6-6 Diséñese una sección con celosía para el poste terminal de la ar-
madura del puente de carretera que aparece en el ejemplo 6-4, que tiene siete
paneles de 25 pies cada uno (véase figura, E6-6a). La longitud no soportada
Ly =Lx es de 24.04 pies. La salida de la computadora (incluido un factor de
impacto de 0.17) es la siguiente:

Miembro LC-Il,kN Medida del diseño, kips

2 -94.13 -240.77

6

J' 25' 7

4
....-------7 @.. 25' Figun E6-6a

<!-- p. 319 -->

DISEÑO DE MIEMBROS ARMADOS A COMPRESION 319

SOLUCION
Carga total de diseño = 240.77 +94.13
\= 334.9 kips
Suponiendo que Fa~14 kip/pulg-, el área requerida en la sección será aproximadamente

2 ~ A --¡¡-334.9 = 23.92 pu 1g

Se probarán dos canales con una sólida cubreplaca y celosía, como se muestra
en la figura E6-6b. Esta configuración, con la placa sólida por arriba, proveerá alguna protección al interior de la sección armada, y la celosía permitirá el
acceso para pintura y limpieza. El espaciamiento y la configuración serán tales que se pueda hacer una conexión razonablemente fácil de las secciones del
alma de la W12, como se muestra, usando un par de placas de conexión. Nótese que se requerirán placas de relleno, puesto que las secciones W12 tienen
un peralte mayor de 12 pulg.
Datos del C12 x 30:

A = 8.82 pulg- b¡ = 3.17 pulg
t¡ = 0.501 pulg t; = 0.51 pulg
Tanto t¡como tw>0.23 (Sección 1-7.7)
Ix = 162 pulg4 rx = 4.29 pulg
Iy = 5.14 pulg4 ry = 0.763 pulg
x = 0.674 pulg

Io 12" ., ¡..-ls" Soldadura I ]"¡ t"1
I~ '~~
'.ql
°1 I ~'it--- ---¡\<jl--l---L.._ Xx-
12" -+-1#-------+.,¡......;--r

liI"'í"".-...---~"'fo1! r I
I
I
I I.o-Placa de conexión
I
WI2 X I IIIII I w
Placa de relleno
si se requiere
Flgun E6-6b

<!-- p. 320 -->

320 COLUMNAS Y PUNTALES AXIALMENTE CARGADOS

Calcíilese el radio de giro con respecto a los ejes X e Y:
Con respecto al eje X; localícese un nuevo eje X:

(2 x 8.82 + 0.5 x 12.75)y = 0.5(12.75)( ~2 + 0.25)
39.84
Y = 24.02 = 1.66pulg

2 2 /xx = 2/xQ+ 2Acd + Apd
\= 2(162) + 2(8.82)(1.66)2+ 6.375(4.59i
\= 324 + 48.6 + 134.4
\= 507.0 pulg"
507.0 ) 1/2
rx = ( 24.02 = 4.59pulg rige (después de calcular
posteriormente ry)

\= 2(5.14) + 2(8.82)(5.326)2 + 0.5(11~75)3
\- 10.3 + 500.4 + 86.4 = 597.1pulg"
_ ( 597.1 )1/2 _ KL = 24.04(12) = 628
'Y 24.02 - 4.99 pulg rx 4.59 .
36[ 1 - 0.5( :;6~1 f]
Fa = 2.12 = 14.9ksi [usando la eco (6-9) ]
Areqd = 3::: == 22.5 \< 24.02pulg- suministradas Correcta

Es práctica usual usar cubreplacas soldadas a las secciones laminadas
más bien que celosía. Se diseñará en este ejemplo una celosía y se usará sol-
dadura para fijarla a las secciones laminadas. Solamente se usarán tornillos
en las conexiones de campo de las juntas.
En la figura E6-6c se muestra la distancia entre los agujeros del patín (y
la distancia aproximada, centro a centro, de las soldaduras).

L' ... 12 - 2(1.75) = 8.5 \< 15pulg (además AISC)

Se usarán barras individuales de celosía con un ángulo de 60° con el eje del
miembro, como se muestra en la figura (refiérase también a la figura 6-50):

<!-- p. 321 -->

DISEÑO DE MIEMBROS ARMADOS A COMPRESION 321

1.75~8.5"

\~ 60° I I
Soldadura
¡ I v; J00
:..;"
:.".1

Figura E6-6c

8.5 8 L = 300 = 9. 1 pulg cos
L' = 2(8.5)sen30° = 8.5 pulg
L' 8.5 1 40
\= 0.763 = 1.1« 'y (del canal)

Además, 11.1 es menor que 0.67 xL/r( =41.9). Se limita laL/rde la celosía
a 130. El radio de giro de una barra plana es

r = [ 1~1;1) ]1/ 2 = 0.2881

1 = 130~:'~88) = 0.262 pulg

L 9.81
t ~ 40 = 40 = 0.245 pulg

Pruébese tL = ft pulg (= 0.313 pulg, también un mínimo según la AASHTO):

L 9.81 109 C
r 0.288(0.313) = orrecta

Calcúlese la fuerza en la barra de celosía. La componente de la barra,
perpendicular al eje del miembro se calcula usando la ecuación (6-14):

<!-- p. 322 -->

322 COLUMNAS Y PUNTALES AXIALMENTE CARGADOS

P (100 L/r)
V = 100 L/r + 10 + 3300/F;,
334.9 [100 62.8(36) ] . = --¡ro 62.8 + 10 + 3300 = 3.349(2.06) = 6.9 kips

Se aumentar á este valor en 20 por ciento (es decisión del autor), para tener en
cuenta el peso del miembro, el viento, y cualesquiera otros factores; por tan-
to, J"diseño es

Vd = 1.2(6.9) = 8.3 kips
La fuerza axial es
8.3 96 ki Pd = 300 =. ps cos
36[1 - 0.5(109/126.1)2]
Fa = 2.12 = 10.64 kip/pulg-
btFa = 9.6 kips
\- 9.6 _ 288 ul
b- 0.313(10.75) - . P g
Se revisará t para 7/16 pulg: Fa = 13.78 kip/pulg-:
b 9.6 1 58 ul se usará una placa . = 0.44(13.78) = . P g de 11 pulg 4
Las dimensiones finales de la barra de celosía se tomarán como (L =9.81
\+ 1.69 pulg)
l~.w X -kt X 11.5L

Diséñense las placas atiesadoras terminales. Los requerimientos de la
AASHTO son:

L ~ 1.25Lo

Se usará un mínimo de tres sujetadores (o soldadura equivalente) en cada la-
do. Llevado al diseño (figura E6-6d):

L = 1.25(12) = 15 pulg
12 t == 50 == 0.24 se usan 7/16 pulg para ajustarse
a las barras de celosía

<!-- p. 323 -->

DISEÑO DE MIEMBROS ARMADOS A COMPRESION 323

\----llf---...

Soldadura I I
I Placa de I "' I conexión en]
.1 el extremo I
I I
IIp=7/1 ó'' i
1 I

Figura E6·6d

Ejemplo 6-7 Diséñese una sección armada con cubreplacas para usarla como columna en una torre de agua (véase figura E6-7a). La longitud sin apoyo de la columna es de 24.7 m, y la carga axial de diseño es 1350kN. Se usará
F',.v = 250 MPa y las especificaciones del AISC (considerando que una torre
de agua no es un "edificio", y puede situarse en un lugar en el que un colapso
resulta más bien una costosa molestia que un peligro para la gente, por lo que
puede que no sea necesario usar ninguna especificación), puesto que la adherencia a dichas especificaciones, aunque no sean necesarias asegurarán un diseño seguro. Casi siempre hay algún contraventeo en las torres de agua, pero
se supondrá que el contraventeo no es suficiente para desarrollar ninguna
restricción contra el pandeo de la columna.

Figura E6·70

SOLUCION Se tomará como 200 el KL/r mínimo, para los miembros prin-
cipales. Por tanto,

<!-- p. 324 -->

324 COLUMNAS Y PUNTALES AXIALMENTE CARGADOS

\-x

Figura E6-7b

\= 24.7(1000) = 1235 rmio 200 . mm

Para este valor de Llr de 200, el esfuerzo permisible Fa = 25.7 MPa. Por
tanto, es necesario usar un mayor valor de r, o el área de acero será excesiva.
Para un Llr = lOO. el valor de Fa = 90 MPa, y el área de acero será aproxi-
madamente I 350/100= 13.5x 10-3 m-,
Se probarán 4 L 152x 152x 14.3 (una selección algo arbitraria) los da-
tos son:

A = 4.184 X 10-3 m2/ángulo
Iy = t, = 9.199 X 10-6 m4
X =j = 43.4 mm

Se colocarán los ángulos en una sección simétrica con un espaciamiento co-
mo el mostrado en la figura E6-7b. Calcúlese Ix=IyYrx = ryutilizando datos
de la sección:

Ix = 4/0 + 4Ad 2
Ix = 4(9.199) + 4(4.184 x 10-3)(0.2191)2 = 36.796 + 803.4
\= 840.2 x 10-6 m2

6
840.2 X 10- = V 50.2 X 10-3 = 224 mm ';x = 'y = 4 x 4.184 X 10-3
\14000) L, __ 24.7 __ 110.26 b Yde la tabla VI-5 se o tiene . F a = 81 MP a 2(2
P ..d= permm o 81(4.184 x 4) = 1356> 1350kN requerido Correcta

Se considerará adecuada esta sección y se pasará a diseñar las cubreplacas.
El diseño de las cubreplacas no es tanto "diseñar" como satisfacer una
serie de criterios y determinar un espaciamiento de los agujeros que se adapte
a la longitud de la columna.

<!-- p. 325 -->

DISEÑO DE MIEMBROS ARMADOS A COMPRESION 325

\~.-- 500
\~.-: ~ I IIL o -- ~~"1 mm'I I,
, ó I ," ", I Al 11 I I ,,~, I
.s .: I I ,,'->~ I I
\-~l I o~ I I - I I '1 g l' I o I I I I
\+-1 k- : 1 I E I I
t o I 1
E
;.¡V) ¡ ~~D ! I I g I

V) E I 7 I
o I , '
Soldadura 1 Ii-+ I I I
I I I
I Il I : ULl-_..J_~IJ
Figura E6-7r

Haciendo referencia a las figuras E6-7c y 6-6, se obtiene:

Lo = 221 mm
r = 75 mm (selección arbitraria del radio del agujero)
w = 2r = 150 mm
Se usará L 1 ~ 1.25 Lo-0.45 m. Longitud de la cubreplaca = 24.7 - 2(0.45)
\~ 23.8m. Se hace esta selección a fin de que con una longitud de agujero de
L; = 300 mm y L t 0= 200 mm, la longitud de 23. 8 m dará
48agujeros = 48(0.30) = 14.4m
47 agujeros = 47(0.20)= 9.4 m
Total - 23.8 m

Encontrar el espesor de la cubreplaca (refiérase a la figura 6-6):

Lo~~-52.8
\~ V250
221
tp = 52.8 - 4.19 mm

Se usará 6 mm (1/4 pulg). Se usará soldadura y se colocará la placa de la manera indicada. La soldadura puede ser intermitente. Si la soldadura es sufi-

<!-- p. 326 -->

326 COLUMNAS Y PUNTALES AXIALMENTE CARGADOS

ciente para permitir que la cubreplaca y los angulares actúen como una uni-
dad, el AISC permite una contribución de la cubreplaca basada en

(L - 2r)tp = [500 - 2(75)]0.006 = 2.1 X 10- 3 m2

de área que se ha de usar para aumentar la capacidad axial de la sección.

16-6 PLACAS DE BASE DE COLUMNAS

Las columnas de acero se colocan sobre algún tipo de miembro soportante for-
mando una entrecara entre la columna y su soporte. El miembro soportante
puede ser una columna de concreto en un edificio de construcción compuesta, pe-
ro es más común que una columna termine en una cimentación, pedestal, o pi-
lastra. Se usa un pedestal para mantener la columna de metal por encima del
terreno para prevenir la corrosión cuando la cimentación está por debajo del nivel
del terreno. Una pilastra es una sección ensanchada del muro del sótano que se
usa para transmitir la carga de la columna, a través de la zona del muro hasta la
cimentación. A veces, pero no es corriente, la columna termina directamente
sobre la cimentación.
Cuando la columna de acero termina sobre cualquier tipo de mampostería,
es necesaria una placa de base a fin de distribuir la alta intensidad del esfuerzo en
el acero a un valor que pueda ser soportado con seguridad por la mampostería.
Mampostería, significa en este caso, concreto, bloques de concreto, ladrillos, y
bloques de arcilla; el concreto es el que más se usa y será el único material que se
considerará.
La placa de base y el extremo de la columna que está en contacto con dicha
placa se pueden alisar para efectuar la transferencia de carga por asiento directo.
La placa de base se asienta sobre la cimentación usando una lechada de cemento
(mezcla espesa de arena y cemento, a menudo con un agente expansivo para pro-
ducir un estrecho contacto, ya que la pasta de cemento tiende a contraerse en el
secado). La lechada puede igualar un desajuste entre cimentación y columna de
hasta 1 pulg (25 mm) siempre que se trate de una discrepancia de "relleno".
Se pueden usar angulares para atornillar o soldar la placa de base a la colum-
na. Sin embargo, en la práctica esla de usar una placa de base soldada a la columna
en el taller. Se barrénan en la placa de base agujeros para los pernos, de un diáme-
tro ligeramente mayor, para que ajusten sobre los pernos de anclaje colocados en la
cimentación, durante la construcción en el campo. Los agujeros mayores permiten
pequeñas desviaciones en la alineación de los pernos de anclaje, sin que sea nece-
sario volver a barrenar los agujeros en la placa de base, o quitar y recolocar los
anclajes. En la figura 6-7 se ilustra el método general para fijar la columna a la
cimentación.
'Las dimensiones de la placa de base requerida dependen de la presión unita-
ria permisible de contacto de la cimentación. El espesor de la placa de base depen-
de de la presión de contacto de la placa de base, y produce flexión en la sección

<!-- p. 327 -->

p p

Tornillos
/" Pernos de anclaje Soldadura
, Placa de base

(al (b)

(e) (d)

(e)

Figura 6-7 Contacto entre la columna y la cimentación usando placas de base. (a) Uso de angulares
para unir la columna a la cimentación. Método que no se usa mucho al presente debido al trabajo
extra de fabricación (corte de dos angulares y cuidadoso alisado del extremo de la columna y la placa
de base. (b) Columnas y placas de base soldadas en el taller; este método se usa mucho para fijar las
columnas a las cimentaciones [véanse también las fotografias tomadas en elcampo en (e), (d), y (e)l. (e)
Columna de esquina con placa de base soldada en el taller. Se puede ver fácilmente el espacio para el
enlechado. Hay cuatro pernos de anclaje para fijar la columna a la cimentación. El miembro diagonal
es un elemento de contraventeo soldado en el campo. (d) Esta columna usa también una placa de base
soldada en el campo. Se puede ver con facilidad el espacio para enlechado. Se usa el cable para alinear
el marco. (e) Serie de columnas interiores fijadas directamente a las cimentaciones. Se notará de nuevo el uso de placas de base soldadas en el taller.
327

<!-- p. 328 -->

328 COLUMNAS Y PUNTALES AXIALMENTE CARGADOS

\----B---.¡ . A1SC. esfuerzos permisibles Material de contacto •f'"
fps: kips/pulg- SI. MPa

Arenisca y caliza 0.4 2.8
Ladrillo en matriz de cemento 0.25 1.75
Area total de la cimentación de
concreto 0.351:
Menos del área total de la
cimentación 0.351: VAl/A, ~ 0.71:

(a)
Al =B X C
p Al=(B+4d)(C+4d)
\~r

(b)

n o In "1
M 1 unidad de ancho

"(2C:lJ
Sin momento
M = fa:;:'x
Con momento
(e)

Figura 6-8 Dimensiones generales de las placas de base y otros criterios de diseño. (a) Dimensiones de
la placa de base. (b) Esfuerzos permisibles, Fp • (e) Momento de la placa de base para calcular el espesor de la placa base.

crítica con dimensiones como las mostradas en la figura 64c. Cuando la base
de la columna resiste un momento, deben ajustarse las dimensiones de la placa de
manera que

P M
F>'=-+-p -Jp A - S

donde S es el módulo de sección de la placa rectangular de base con respecto al eje
de momentos. En este caso, se muestra también en la figura 6-8c el espesor de la
placa.
De la figura 6-80, el área de la placa de base de la columna es

P B X c=- Fp

<!-- p. 329 -->

PLACAS DE BASE DE COLUMNAS 329
Se puede obtener un número de combinaciones para los lados B y e, pero se debe
usar la combinación que haga que meen, En la práctica de taller se prefiere que B
y e sean números enteros.
Se obtiene el espesor de la placa de base considerando la flexión en una sección crítica a la distancia m o n del borde libre correspondiente (figura 6-8c). Para
una presión uniforme y una franja m o n X 1 unidad de ancho x un espesor t, se
tiene

m n
M = q(m)-2 o M = q(n)-2
Usando el valor mayor de M (y notando que si m = n, estos momentos son iguales), se tiene

(para una franja de ancho unitario)

Resolviendo para t, se obtiene

donde q presión real de contacto
Fb 0.75 Fy(AISC, Sección 1-5.1.4.3, basado en la flexión sobre una
sección rectangular.) I

Ejemplo 6-8 Diséñese la placa de base para una columna como la que se
\~!: muestra en la figura E6-S. Usese F, = 250 = 20.7 MPa, y las especi-
ficaciones de la AISC. /
\~-~

1670 kN

Pedestal

Fi~ura E6-8

<!-- p. 330 -->

330 COLUMNAS Y PUNTALES AXIALMENTE CARGADOS

SOLUCION Las dimensiones del pedestal en la línea de piso serán las mis-
mas que las de la placa de base. Por tanto
F;, = 0.351: = 7.245 MPa (figura 6-8b)
_ 1670 _ -3 2 B x e - 7.245 - 230.5 x 10 m
Supóngase que m~n:
De la tabla V-3 se obtiene d = 360 mm; b¡ = 256 mm
B = 0.80(256) + 2n = 205 + 2n = 205 + 2m
e = 0.95(360) + 2m = 342 + 2m
(0.205 + 2m)(0.342 + 2m) = 0.2305 corriendo el decimal
m 2 + 0.2735m = 0.04009
m = 0.106 m
Verifíquese
B = 205 + 2(106) = 417 mm
e = 342 + 2(106) = 554 mm
B X e = 0.417 x 0.554 = 0.2310 ml > 0.2305 Correcta
La presión real de contacto, q, es
1670
q = 231.0 = 7.229 MPa
n = m = O.106m
M = 7.229(~.I06i = 0.08123MN . m 6(0.08123) ]1/2 t = [ 0.75(250) = 0.0509m
\= 50.9 mm o sea 52 mm

Se usa una placa de base de columna de 417 x 554 x 52 mm de espesor.

1670 kN
265 kN'm

Pedestal
Figura E6-9a

<!-- p. 331 -->

PLACAS DE BASE DE COLUMNAS 331

Ejemplo 6-9 Rediséñese la placa de base de la columna del ejemplo 6-8, para
resistir un momento flector de 265 kN . m, además de la carga axial (figura
E6-9a).

SOLUCION Se diseñará la placa de base soldada a la columna del ejemplo
9-7.
\~ = 7.245 MPa s q
1670 6(265)
q = BC ± BC 2

DespuésI 'Jde varios cálculos auxiliares, se supone que e = 780 mm:

B = 1670 + 6(265)
7245(0.78) 7245(0.782)
\= 656 mm
La figura E6-9b ilustra datos que hasta ahora incluyen q = 7.248 Y -0.724
obtenidos usando B y e en la ecuación precedente para q,
A lo largo de la línea x - x:

q = 7.248 - 10.22x
1O.22x2
V = 7.248x - 2 (integrando)
M = 7.248x2 10.22x3
2 6

Para x = 0.219 m:

M = 7.248~.219)2 1O.22(~.219)3 = 0.1559 MN . m

\-0.724 MPa
x- --R~~~~A-'--x

\~ ~
V) V)
N ""

780 I
I
Y
Figura E6-9b

<!-- p. 332 -->

332 COLUMNAS Y PUNTALES AXIALMENTE CARGADOS

El espesor correspondiente es

\= (6 x 0.1559 )1/2 = 00706
t 187.5 . m
\= 70.6 mm o sea 75 mm

De la otra dirección, en el punto A (línea y - y) se tiene
n =656 - 0.80(256) =226 mm
2
q == 7.248 - 10.22(0.219) = 5.01 MPa (promedio para un
ancho unitario)
M = 5.10(~226)2 = 0.1302 MN· m

\== (6 x 0.1302 )1/2 = 00645 t 187.5 . m
\== 65 mm

Se usará el valor mayor de 75 mm. Las dimensiones finales de la placa de ba-
se de la columna serán 780 x 656 x 75 mm de espesor.
Para pernos de anclaje como los que se muestran en la figura E6-9c, su-
póngase que los pernos soportarán todo el momento, aun cuando la fuerza
axial reducirá considerablemente el momento. Esta suposición provee cierta
capacidad de reserva del sistema de anclaje para resistir una fuerza lateral
considerable (desplazamiento lateral de la columna).

265
T == 0.570 = 465 kN
Se'usará Fy = 345 para los pernos de anclaje.
F, = 0.6J\<;, == 207 kN
_ 465 _ 246 -3 2
A requenoo 207 - 2. x 10m

1670 1f----'7..:.80:...-._
265 kN'm
TIfLJ l~d.'m~1 LC780~ 1m Figura E6-9c

<!-- p. 333 -->

SOPORTE LATERAL DE LAS COLUMNAS 333

Usando tres barras de anclaje en cada lado, el diámetro será

0.002246 ] 1/2
D = [ 3(0.7854) = 0.03087 m

Se usarán tres barras de anclaje de 32 mm de diámetro.
I 6-7 SOPORTE LATERAL DE LAS COLUMNAS
Hay una regla empírica común y ampliamente usada para el soporte lateral de los
patines a compresión tanto de vigas como columnas; según esta regla se provee
un elemento de soporte lateral (es también un miembro a compresión) para so-
portar una fuerza lateral
Pb = 0.02P
donde P es la fuerza axial en el miembro a compresión que se quiere soportar,
esto es, P=A¡fb para miembros a flexión, donde A¡ = área del patín a compre-
sión yfb = esfuerzo a compresión promedio (o máximo) debido a la flexión. Para
columnas, úsese P = carga axial promedio en la columna. Esta recomendación
está dada por el Structural Stability Research Council en Guide to Stability De-
sign Criteria for Metal Structures, 3a ed., editada por Johnst0o/
Pruebas efectuadas por Winter en Cornell University (véase "Lateral Bra-
cing of Columns and Beams", Transactions, ASCE, Vol. 125, 1960)indican que
se requiere muy poco soporte lateral para permitir que el elemento a compresión
desarrolle el esfuerzo permisible de diseño. Esta restricción se puede generalmen-
te desarrollar por medio del sistema de piso sobre las vigas, cuando se tiene con-
tacto total a lo largo del patín a compresíónjljebído a la naturaleza variable del
material de piso (tablero metálico, concreto sobre las vigas, madera sobre las vi-
gas, etc.), se aconseja que se use el criterio del 2 por cientoj' Winter dedujo tam-
bien una expresión analítica para el soporte lateral requerido, basado tanto en la
restricción como la rigidez relativa de la columna y el soporte. Si se usa un FS de
aproximadamente 2.5, con la expresión derivada, se puede obtener la regla
empírica del 2 por ciento.

Ejemplo 6-10 Determínese la viga de borde (o larguero de pared) de dimen-
siones mínimas para soportar, con respecto al eje Y,la secciónW para la carga
axial de 750 kips del ejemplo 6-2. Se puede tomar la distancia entre columnas
como 18pies. F; para la columna = 50kips/pulg-.

SOLUCION La fuerza axial, en la sección canal, usada como soporte, es

Pb = 0.02P = 0.02(750) = 15kips

La máxima L/r = 200 (AISC) para miembros a compresión. El radio
mínimo de giro, ry = 18(12)/200 = 1.08 pulg. Para una relación Llr = 200,

<!-- p. 334 -->

334 COLUMNAS Y PUNTALES AXIALMENTE CARGADOS

el esfuerzo axial permisible Fa = 3.73 kip/pulg- (tabla U-5, SSDD), apli-
cable a todos los valores de Fr

P 15
Areqd = Fa = 3.73 = 4.02 pulg?

Búsquese esta combinación de A y r y, en las tablas 1-6e 1-7, y se hallará

MClO X 28.5: A = 8.37 pulg-
ry = 1.17pulg
Si se satisface también la flexión y otros requisitos, se puede usar la sección
como larguero de pared (o viga de borde).

6-8 DISEÑO DE COLUMNAS Y PUNTALES USANDO EL DFRC

El uso del DFRC requiere la separación de las cargas muertas y vivas sobre la columna. Una vez hecho esto, se obtiene la carga última de la columna en la forma
siguiente:

Además

Se necesita en este caso la tabla 3-1, puesto que los valors de el> caen dentro del
rango de 0.86 a 0.65, dependiendo de "1, la que a su vez depende del KLír de la columna así como de Fr Se notará también que el valor de Fcr depende del valor de
"1 en la forma que se indica a continuación:

Fcr = F;.(1 - 0.251/2)
\-F;.
FCr=2
1/
donde "1 = valor dado en la tabla 3-1, Yque se repite en este lugar:

Ejemplo 6-11 Dadas las columnas del ejemplo 6-1, espaciadas 20 pies c.a.c
en cada dirección, carga muerta 30 lb/pie--carga viva = 60 lb/piel ( nieve),

<!-- p. 335 -->

DISEÑO DE COLUMNAS Y PUNTALES USANDO EL DFRC 335
longitud de la columna = 14 pies, y K = 1 (como en el ejemplo 6-1 y la figura 6-3). Se usará acero A-36 y el método DFRC. (En el ejemplo 6-1 se escogió
para columna un tubo de 4 pulg por 10.79 lb/pie.) Rediséñese la columna
usando el DFRC como se da en la Sección 3-7.

SOLUCION

Pu = 1.1(1.1D + 1.5S)A
\= 1.1[1.1(0.030) + 1.5(0.060)](20 x 20) = 54.12 kips (vs. 36 kips Pw)

Además,

\= 1(I4 x 12) ( 36 )1/2 = 1.884
.,., '1Tr 29 000 r

Usando el ejemplo 6-1 como guía, se prueba un tubo para columna de 4 pulg
x 10.79 lb/pie:

A = 3.17 pulg-
r = 1.51 pulg
1.884 1J = "T5T = 1.25 \< V2

Fe, = FAl - 0.25.,.,2) = 36[ 1 - 0.25(1.25)2] = 21.94
ep = 0.65 (1J > 1.0) kip/pulg-
r; 54.12 3 1 Areqd = epF , = 0.65(21.94) = .79pu g > 3.17 N.S.
e

Se prueba un tubo de 5 pulg x 14.62 lb/pie:

A = 4.30 pulg''
r = 1.88 pulg
\= 1.884 = 1 002 1J 1.88 .
Fe, = 36[ 1 - 0.25(1.002)2] = 26.96 kip/pulg-
ep = 0.65
\- 54.12 _ 309 2
ArequeridoO.65(26.96) - . pulg \< 4.30 Correcta

Se usará una columna de tubo de 5 pulg x 14.62 lb/pie

<!-- p. 336 -->

336 COLUMNAS Y PUNTALES AXIALMENTE CARGADOS

PROBLEMAS

6-1 Determínese la carga permisible que puede soportar una columna Wl4x211, usando acero
Fy = 50 kip/pulg2 y las especificaciones del AISC si:
a) KL = 16 pies.
b) KL = 42 pies.
e) KLx = 68 pies y KLy = 44 pies.
Se harán los comentarios apropiados.
Respuesta: b) 602.7 kips. e) 549.1 kips
6-2 Determínese la carga permisible para una sección laminada W360 x 346.7 que usa Fy = 415 MPa
y las especificaciones del AISC si:
a) KL = 5.1 m.
b) KL = \3.2 m.
e) KLx = 20.5 m y KLy = \3.6 m.
Se harán los comentarios apropiados.
Respuesta: e) 2 669 kN.
6·3 ¿Cuál será la sección cuadrada de tubo más ligera (véase tabla 1-15, SSDD) para una carga de columna de \34 kips y una longitud sin apoyo de 12.4 pies? Se usarán las especificaciones del AISC y
acero A-36.
Respuesta: 6x6xO.375.
6-4 ¿Cuál será la carga permisible, para un tubo usado como columna de sección rectangular de
300 x 200 x 9.52 mm, usando las especificaciones del AISC y Fy = 345 MPa (tabla V-16, SSDD), para
una longitud no soportada de 4.8 m?

6-5 ¿Cuál será la carga permisible, usando las especificaciones del AREA, para una sección
WI4x 145 que se usa como miembro a compresión atornillado en sus extremos en una armadura de
puente? El miembro tiene 15.5 pies de largo y usa acero A-36?
Respuesta: 771.6 kips
6-6 ¿Cuál será la carga permisible, usando las especificaciones del AREA, para una sección laminada
W3lOx 178.6, que se usa como miembro a compresión atornillado en sus extremos en una armadura
de puente? El miembro tiene 4.75 m de largo y usa Fy = 345 MPa para el acero.
Respuesta: 3 163 KN.

6-7 ¿Cuál será la carga permisible para la sección armada de la figura P6-7, usando las especificaciones del AREA y acero A-36? Supóngase una conexión terminal atornillada y una longitud de 5.25 m.

VTC31OX44.6

74.4 ¿80X
Figura P6-7

6-8 ¿Cuál será la carga permisible para el miembro armado de la figura P6-8, usando las especificaciones de la AASHTO, Fy = 50 kip/pulg2, y una longitud no soportada de 18.7 pies?

6-9 Refiriéndose a la figura P6-7, colóquese una segunda canal C310 x 44.64 en la parte inferior del
perfil S para que sea simétrico..¿Cuál será la carga permisible en la columna, usando las especificaciones de la AASHTO, si L=6.6 m, y se usa acero A-36?
Respuesta: 1 %2 kN.
6-10 ¿Cuál será la carga permisible de columna para la sección armada de la figura P6-IO, si el
miembro es de acero A-36, y la longitud es de 14.5 pies? Se usarán las especificaciones de la
AASHTO.

<!-- p. 337 -->

PROBLEMAS 337

4-L's 6" X 6" xl"
4
" I-placa I 2" X 1." 2

Figura P6-S

Figura P6-IO

6-11 ¿Cuál será la carga permisible de columna para la sección armada de la figura P6-11? La longitud es de 5,3 m. Usense las especificaciones del AISC y acero A-36. No se tenga en cuenta la contribución de la cubreplaca perforada.
Respuesta: 3090.3 kN.
l

2-080 X 59.5
I-placa 380 X 20

Cubreplaca c.P. Figura P6-11
perforada

6-12 Diséñese la celosía para la carga permisible que se halla en el problema 6-10, asignando un
aumento del 20 por ciento de aumento de V, para el viento, el peso de los miembros, etc.

6-13 Diséñense las cubreplacas perforadas de cubierta para la carga permisible y sección del problema 6-11.
6-14 Repítase el ejemplo 6-1, si el área de contribución para la columna es de 30x 20 en lugar de
20 x 20, pero con el resto de los datos iguales.
Respuesta: 5 pulg a 14.6 lb/pies.
6-15 Diséñese una sección de columna con celosía para un poste terminal de una armadura de puente
de carretera (refiérase al ejemplo 6-5). La longitud es 7.2.J~ 10.18 m. El calor de la armadura es de
50.4 m y las cargas son: carga muerta = -1120 kN, Ycarga viva = -422 kN (sin impacto). Se usará
F, = 250 MPa y las especificaciones de la AASHTO.
Respuesta: Pruébese con dos C380 x 50.4 y una cubreplaca de 300 x 15 mm.
6-16 Redíséñese el poste terminal de la armadura del ejemplo 6-6 usando una cubreplaca perforada
para ambos lados de los canales. Nótese que la AASHTO permite el uso del área neta de las cubreplacas perforadas al calcular el área de la sección total y la capacidad de la columna.

<!-- p. 338 -->

338 COLUMNAS Y PUNTALES AXIALMENTE CARGADOS

Respuesta: 2 CI2 x 25, A sum 23.7, rmin = 4.58 pulg, incluye dos placas de 12x L/2 pulg con
agujeros de tres pulgadas.

6·)7 Diséñese una placa de base de columna para la capacidad máxima de una columna WI2x 170,
con una longitud sin soportes de 12.0 pies. Supóngase que K¿ = K; = 1.0. Usese F; = 50 kip/pulg/,
f/ = 4 kip/pulg', y las especificaciones del AISC. La columna descansa en un pedestal de concreto.
6-18 Diséñese la placa de base de columna de una sección WI4 x 120 que soporta una carga axial de
500 kips y un momento en la base de 200 pies·kips. Usese acero A-36, f~= 3 kíp/pulgj, y la placa
de base hace contacto directo entre la columna y la cimentación, que tiene un peralte total de 21 pulg.
Respuesta: 243/4 x 223/4 x 2 1/2.
6-19 Diséñese una placa de base de columna para la capacidad máxima de una sección laminada
W310 x 117.6, con una longitud sin soportar de 4.1 m. Supóngase que K, = Ky = O.Usese Fy = 345
MPa, f' e = 28 MPa, y las especificaciones del AISC. La columna hace contacto con un pedestal de
concreto.
6-20 Repitase el ejemplo 6-11 para la sección W8 más ligera que se disponga.
6·21 Repitase el ejemnlo ó-II si las cargas son como sigue: carga muerta = 35 lb/pie"; carga viva
\= 75 lb/píe".
Respuesta: Tubo de 5 pulg con 14.6 lb/pie.
6-22 Repitase el ejemplo 6-11 usando los siguientes datos: carga muerta = 1.75 kPa; carga viva = 3.75
kPa; área de contribución de lacolurnna 6.1 x 7.1 m, longitud de la columna = 4.98 m, yK, = Ky = 1.0.
Se podrá usar lo mismo un tubo redondo o un tubo estructural cuadrado para la columna, y F; = 250
MPa para el acero.

6·23 Diséñese el miembro 6 del ejemplo 6-6 (refiérase a la figura E6-6a), si la fuerza en la barra por
carga muerta = 283.8 kips, la máxima carga viva, incluido el impacto = 109.4 kips, y la minima carga viva = 0.0 kips, Compárese la sección con la obtenida en el ejemplo 6-6. Tómese, P II '" ¡J,({3dDL +
(JI LL), donde ,¡, ~ 1.3, ¡:id = 1.0, Y 13¡ = 1.67 (última edición de las especificaciones de la AASHTO).
Además, PII = 0.85AFcro donde Fa = Fa de la ecuación (6.9) o ecuación (6-10), sin usar fS = 212.
Respuesta: Usese la misma sección que en el problema 6-16.

<!-- p. 339 -->



<!-- p. 340 -->

Figura VII-I Vigas-columna y vigas formando una estructura industrial. Obsérvese la orientación
alternada de fuertes ejes de vigas-columna a los lados de la estructura, Un acercamiento de las juntas
seleccionadas se muestra en la figura 9-15.

<!-- p. 341 -->

CAP/TUL.
SIETE

DISEÑO DE VIGAS-COLUMNAS

7-1 INTRODUCCION

Cuando se carga un miembro estructural de manera que produzca más de un modo de esfuerzos, es necesario efectuar algunos ajustes en los esfuerzos permisibles. Cuando los esfuerzos se producen como una combinación de flexión con
respecto a los ejes X e Y, como en la sección 4-8, los esfuerzos finales de diseño se
obtienen por superposición.

(a)

Como Fhx puede no ser igual a Fhl. (especialmente en el caso de los perfjles W, debido a la geometría del patín) se obtuvo el diseño de la viga del capítulo 4 por iteración. La acumulación de los esfuerzos de compresión (o tensión) en un borde de
uno de los patines, se usó en la forma siguiente de la ecuación (a):

(b)

Esta ecuación se obtuvo dividiendo la ecuación (a) por Fh -
Es frecuente que surja un problema similar a éste cuando el miembro estruc-
tural se encuentre sometido a una combinación de cargas de flexión y axiales. Es-

341

<!-- p. 342 -->

342 DISEÑO DE VIGAS-COLUMNAS

tas situaciones siempre se presentan en la construcción de marcos rígidos (es decir, las columnas soportan axialmente la carga del edificio, así como los momentosen los extremos de las vigas que conectan a las mismas). En los edificios industriales se pueden usar las ménsulas de las columnas para soportar las trabes
carril y, finalmente la carga de la grúa. La resultante excentricidad de la ménsula
produce un momento flector además de las cargas axiales de la columna. En este
caso, el momento de la columna no se encuentra en los extremos de la misma. Similarmente, la presión del viento sobre largos miembros verticales puede producir momentos flectores, puesto que una gran distancia entre pisos (o entre el terreno y el techo) puede invalidar el concepto de que el viento se toma de una manera
análoga a la acción de una losa que opera en una sola dirección. En los ejemplos
2-5 y 2-6, la conexión entre los cobertizos laterales y las columnas del claro principal, producen grandes momentos en las columnas, los que deberán ser tenidos en
cuenta en su diseño (lo que se considerará en una sección posterior).
Otras condiciones de diseño producen flexión además de las fuerzas axiales.
Por ejemplo, las cuerdas superiores de las armaduras de techo y de puentes son
normalmente miembros "articulados" a compresión, por el peso del miembro
produce también flexión. Los largueros, colocados entre las juntas de los paneles
de una armadura de techo, como un medio para reducir tanto el tamaño del larguero como el claro del techo, producirán flexión en la cuerda.
En general, los miembros a compresión están cargados con fuerzas axiales y
momentos. Los momentos (o momento) pueden estar en los extremos del
miembro, como en los edificios de marcos rígidos, o desarrollarse en una ménsula, viga local, u otro tipo de carga. Cuando el efecto del momento es de producir
una curvatura sencilla (véase figura 7-1) se crea una condición de diseño mucho

p p p

JI

(a) (b v (e)

Figura 7·1 Curvatura resultado de la carga de las columnas. La curvatura simple de b) es a menudo la
más critica. (a) Curvatura doble en un marco del edificio. (b) Curvatura sencilla, carga interior. (e)
Curvatura doble, carga interior.

<!-- p. 343 -->

INTRODUCCION 343

más crítica, que cuando el momento, o momentos, producen una curvatura
doble.
También se puede producir flexión en los miembros sometidos a tensión, como las cuerdas inferiores de las armaduras de puentes, en los lugares en que
puedan conectar a los mismos las vigas de piso. Las cuerdas inferiores de las armaduras de edificios se pueden usar para fijar dispositivos de izado; otras cargas
temporales fijadas en las cuerdas inferiores producirán flexión, además de la carga axial presente.
En muchas de estas situaciones, en particular con los miembros de las armaduras, se desprecian los esfuerzos de flexión. Esto puede ser un procedimiento razonable cuando el esfuerzo de flexión sea el resultado del peso del miembro, a hasta
de los largueros, si son relativamente pequeños (y de peso ligero), y que los efectos resultantes sean quizá menores de aproximadamente el 10por ciento de los esfuerzos analizados. Sin duda, existen pequeños esfuerzos de flexión en los elementos de las cuerdas de la armadura, debido a la continuidad a través de uno o
más paneles (una técnica que se utiliza para reducir los costos de fabricación), y,
además existe por lo general algún sobrediseño, ya que es práctica común usar
miembros en las cuerdas, de dimensiones constante, arriba y abajo (también para
reducir los costos de fabricación). Pueden haber excepciones, cuando es seguro
usar un solo tornillo o remache en los extremos del miembro de la armadura, de
manera que se inhiba menos la rotación -no es práctico, por supuesto, fabricar
juntas "articuladas" para las armaduras corrientes de puente o de techo. Se
pueden minimizar los efectos de la flexión real en las juntas, manteniendo la longitud de la junta, con respecto a la longitud del miembro, tan cortas como sea
práctico y, junto con el hecho de que los miembros de las armaduras tienen por lo
general relaciones pequeñas El/L (es decir, miembro largo con pequeño momento de inercia), el gradiente de momento está bien definido y gran parte del
miembro está esencialmente libre de momentos.
Los momentos que se producen en las armaduras, debido al empotramiento
parcial de los extremos (y que por lo común se ignora en el análisis usando juntas
"articuladas") se conocen colectivamente como efectos secundarios. No es necesario ignorar los efectos secundarios, puesto que los métodos modernos de computadora (como el programa de análisis por computadora del apéndice) pueden analizar una armadura "rígida" (con tres grados de libertad) casi tan fácilmente como
una armadura articulada (con dos grados de libertad). Las primeras computadoras
tenían solamente un almacenamiento límite de cpu/núcleo, antes de que se tuvieran los métodos eficientes de solución de matrices, se tenía necesidad de la geometría de la armadura "articulada", ya que la diferencia en el tamaño de la matriz
para una armadura con 100 nudos o juntas era de:
Número de ecuaciones: 100 x 2 = 2000 o rígida: 100 x 3 = 300
Requerimientos de CPU: 2002 = 40 000 palabras 3002 = 90 000 palabras

Como cada número (o palabra) necesita aproximadamente 4 bits, los requerimientos resultan ser:

<!-- p. 344 -->

344 DISEÑO DE VIGAS-COLUMNAS

Articulada: 40 000 x 4 160000 160K secuencias de bits
90000 x 4 360000 360K secuencias de bits

Una capacidad de 360K + los requerimientos del programa, pondriaa'prueba la
capacidad de las mayores computadoras de que se dispone actualmente, si no se
hubieran concebido métodos eficientes de soluciones de matrices, de manera que
con una ingeniosa codificación (reducir a un mínimo el ancho de banda) y/o usar
condiciones de frontera, la armadura con tres grados de libertad, puede que requieran solamente algunas entre 30 a SOK, que está bien dentro de la capacidad de
todas las computadoras, excepto las pequeñas minicomputadoras de escritorio.

7-2 CONSIDERACIONES GENERALES SOBRE LA CARGA
AXIAL COMBINADA CON LA FLEXION

Cuando la carga axial a tensión y la flexión ocurren simultáneamente, se puede
aplicar con seguridad el principio de la superposición. Esto se debe a que la carga
de tensión tiende a reducir los efectos de la flexión (véase figura 7-2a), de modo
que el valor de ..::i se reduce algo, y, naturalmente, el esfuerzo real es también algo
menor, de manera que las condiciones de esfuerzo máximo permisible, calculadas
como

serán seguras. Esta seguridad se obtiene parcialmente despreciando los efectos
P -..::i sobre fb' que se pueden calcular (para ser estrictamente correcta) como

..::i~0, véase figuraCuando Pb está a la mitad del claro, se tiene (con la limitación
7-2)

(a)

Figura 7-2 Efectos del P- t.. sobre miembros a tensión y compresión.

<!-- p. 345 -->

CONSIDERACIONES GENERALES SOBRE LA CARGA AXIAL 345

y el esfuerzo resultante de flexión es

(h)

El esfuerzo real de flexión se puede solamente obtener por iteración de la
ecuación (a) hasta que el valor .l usado en el lado derecho esté lo suficientemente
cerca del valor .l obtenido en el lado izquierdo. Esta solución iterativa puede que
sea razonablemente práctica con una computadora, pero con cálculos manuales,
será en pocos diseños (donde el número de miembros esté limitado) que se justificará económicamente este procedimiento. Despreciar el efecto P-.l en la
ecuación (b) es un error, pero en el lado conservativo. La inspección de la
ecuación (a) indica que el esfuerzo de tensión reduce la deflexión y reduce además
el esfuerzo de compresión debido a la flexión. Siendo un valor constante el esfuerzo permisible de tensión, FI , y recordando que Fb puede depender de la longitud no soportada del patín a compresión (y reduciendo posiblemente el esfuerzo
posible de compresión), se ve que el uso de

r,fb+1,\<1F,-
provee una solución satisfactoria.
Ejemplo 7-1 Dada la porción de un puente de carretera con las cargas y
miembros de la figura E7-1, ¿cuál será el esfuerzo máximo de tensión en la
cuerda inferior?

SOLUCION (despréciese el efecto P-.l)

2 2)(12)
¡ = wL = 0.040(25 = O72 k .
Jb 8Sx 8(51.9) . SI
P 165 .
1, = A ± fb = 1l.8 ± 0.72 kSI
1, = 13.98 + 0.72 = 14.70 ksi (máximo)
1, = 13.98 - 0.72 = 13.26 ksi (mínimo) III
Cuando una carga axial de compresión actúa junto con un momento flector, se
amplifica la deflexión y aumenta el esfuerzo de compresión. Como el esfuerzo
permisible de compresión tiene en cuenta el posible pandeo (deflexiones
laterales), el diseño del miembro resulta más sensible a este tipo de carga, que el
que producen los esfuerzos de tensión.
Haciendo referencia a la figura 7-2b, se observa que la carga axial (que se supone aplicada al final, pues es así más fácil de visualizar) aumenta la deflexión.
Sin embargo, el orden de aplicación de. las cargas no afecta los resultados,

<!-- p. 346 -->

346 DISEÑO DE VIGAS-COLUMNAS

25'

WI2 X 40
Ix = 310 pulg
A = 11.80 pulg2
Sx = 51.90 pulg3 Figura E7·1

siempre que no se produzca fluencia. Lo que importa es que existe un aumento en
la deflexión debido al efecto P -~, con un correspondiente aumento en el esfuerzo de flexión. El valor de la deflexión (con P, a la mitad del claro) es de

(e)

y los esfuerzos resultantes de flexión, con Pe=(- ) son

(d)

Una evaluación crítica de la ecuación (e) indica que se requiere una solución iterativa como para el modo de tensión, pero que la deflexión se "alimenta" de sí misma (la deflexión causa más deflexión), y que para miembros con un valor de 1 demasiado pequeño, o un valor de L demasiado grande, puede que ocurra una falla
por pandeo.
El efecto P- ~ se puede también desarrollar en edificios altos, como se
muestra cualitativamente en la figura 7-3; cuando las fuerzas del viento o sísmicas
o carga asimétrica producen desplazamientos laterales en los pisos superiores,
con respecto a los elementos inferiores del edificio. Se puede efectuar un análisis
por computadora para analizar el efecto P -~, pero se requiere iteración. Las
etapas incluyen:

l. Hágase un análisis convencional por computadora, usando las fuerzas latera-
les.
\2. Obténganse los desplazamientos laterales del piso i. X i+ I (el piso superior que
sigue).
\3. Calcúlese un momento adicional para la matriz P como

y un cortante como se indica en la figura 7-3b, usando

<!-- p. 347 -->

CONSIDERACIONES GENERALES SOBRE LA CARGA AXIAL 347

M.
V=-' I L

el que se aplica a la parte superior e inferior del piso, prestando atención a los
signos.
Pi+ I = fuerza axial en la columna entre los niveles de piso i e i+ 1

\4. Calcúlese el nuevo X, y compárese con los valores anteriores usados en la etapa
\3. Repítase hasta obtener una convergencia satisfactoria, aproximadamente
0.02 pies ó 0.006 m (aproximadamente Y4 pulg).

A los efectos P- 11 se les llama también "efectos secundarios", y han sido
casi totalmente ignorados hasta muy recientemente. Algunos diseñadores han
aumentado arbitrariamente los esfuerzos de diseño (de las cargas) en un factor tal
como un 10 por ciento, para tener en cuenta el P- 11. Otro factor que tiende a mitigar el efecto P- 11 es que este es derivado generalmente de los análisis de viento
o sísmicos, donde el diseñador puede usar esfuerzos permisibles que se han
aumentado en un tercio. Sólo en casos muy raros se tendría que el P - 11 excediera
estos valores. El programa de análisis por computadora que se presenta en el
apéndice se puede modificar fácilmente para revisar de un modo automático la
matriz de deflexión y encontrar los valores apropiados de X, recalcular la matriz
P usando dichos valores, y luego almacenarlos para compararlos con los nuevos

(al (b)
Figura 7-3 Efecto del P - A en edificios altos. (a) Estructura con cargas laterales. (b) Piso j con las
deflexiones demasiado exageradas.

<!-- p. 348 -->

348 DISEÑO DE VIGAS-COLUMNAS

valores obtenidos del ciclo corriente hasta obtener la convergencia y los resultados finales.

7-3 LONGITUDES EFECTIVAS DE COLUMNAS
EN MARCOS DE EDIFICIOS

El concepto de longitud efectiva de columna, L' = KL se presenta en la sección
6-3, y se obtuvo un valor de K para algunos de los casos corrientes. Se observó
que cuando los extremos de las columnas tenían restricción lateral, de manera que
no se podía desarrollar el efecto P-A (como en la figura 7-3), el valor de K era
K:5, 1.0. Para "el asta de bandera" de la figura 6-3e, o la base articulada de la figura 6-3F, el factor K era de 2.0 o más.
Se verá que en los edificios de muchos pisos, que pueden sufrir translaciones,
el valor de K puede ser considerablemente mayor de 2.0, como se ilustra en la figura 7-40. Para la porción del marco elástico, mostrado en la figura 7-4b y usando la ecuación (6-1):

x = A senky (6-1)

Con k = (PIE!)'!' Yusando la longitud efectiva L' = KL, se obtiene

x = A sen 'TT)' (7-1)
KL

Tomando el origen de coordenadas en un punto de inflexión, como se muestra en
la figura 7-4b, se tiene en la parte superior de la columna:
y = YI X = XI
'TT)'\
XI = A sen KL (o)

En la parte inferior de la columna:

y = Y\ - L

Notando que (a - /3) = sen a cos /3 - cos a sen/3,

cos-sen~'TT)'\ 7T ) (b) x 2 = -A ( sen-cos-'TT)'I 7T - KL K KL K
En el tope y la base de la columna, la pendiente es dxldy, y se obtiene, de las
ecuaciones (o) y (b):

(e)

<!-- p. 349 -->

LONGITUDES EFECTIVAS DE COLUMNAS EN MARCOS DE EDIFICIOS 349

y

y

XI

(a) (b) P~

L
_,ti

\~¡-c:::::::jM
11~.f L/2 1 ML ML
12E/ (¡El (,\

Figura 7-4 Marco elástico para la deducción de los términos G¿ y Gb , a fin de obtener la longitud efectiva de la columna, KL. (O) Parte de un marco elástico. KL se define como la distancia entre los puntos
de inflexión. (b) Elemento de la columna, aislado de (o), con la identificación de los términos usados
en la deducción. (e) Viga conjugada y variación del momento (supuesta).

(}2 = KL'ITA ( COS ?7)'\KL cos K'IT + sen ?7)'\KL sen K'IT ) (d)

Del diagrama de momentos flectores para la supuesta distribución de momentos
de variación lineal a lo largo de la viga, como se muestra en la figura 7-4c, la pendiente de la viga en la unión con la columna (usando los principios de las vigas
conjugadas).

<!-- p. 350 -->

350 DISEÑO DE VIGAS-COLUMNAS

\
donde se toma la suma (1:) porque la carga y el momento provienen de ambas direcciones. De la anterior deducción de la ecuación de Euler, y sumando P, se obtiene

LP=L _'!T)2 _Ele ( K i;

Sustituyendo, se obtiene

(e)

Similarmente,

(1)

Sustituyendo XI Yx 2 se obtiene [usando las ecuaciones (a) y (b)]

(g)

'!T)2 A ( 17)'\ '!T '71)'\ "T ) (J
2 = - ( -K -6Lc Gb sen-cos-KL K - cos-sen-KL K (h)

En la intersección columna-viga de los marcos rígidos, la rotación de la columna
equivale a la rotación de la viga, de manera que igualando los dos valores de () l'
se obtiene
'!T G¿ '71)'\ --tan-= 1 (i) K 6 KL

Igualando de manera semejante las ecuaciones (h) y (d), se obtiene
'!T o,('71)'\ '!T) '71)'\ '!T - K (; tan KL - tan K = 1 + tan KL tan K (j)

Sustituyendo el valor de tan 1I"Y/KL de la ecuación (1), se obtiene

GaGb('!TIK)2 -- 36 '!TI K (7-2)
'!TI K + Gb) = tan 6(Ga
Se puede programar la ecuación (7-2) para incrementos de G; y G; e iterar hasta
obtener un valor de F = 11"/K que satisfaga la igualdad. El valor de 11"/K así obtenido se usa para obtener k como

<!-- p. 351 -->

LONGITUDES EFECTIVAS DE COLUMNAS EN MARCOS DE EDIFICIOS 351

K=!!'-F

Se puede hacer un nomograma de Ga Y G; vs. K, como se muestra en la figura
7-Sa. Este nomograma lo desarrollaron inicialmente Julian y Lawrence en notas
de clases no publicadas y ha sido citado en diversas referencias, que incluyen el
libro del Structural Stability Research Council, Guíde to Stability Desígn Critería
for Metal Structures, 3ao ed., editada por Johnston y publicada por John Wiley &
Sons, Inc., Nueva York.
De una manera algo similar, ya que las condiciones de frontera son diferentes, se pueden desarrollar ecuaciones para Ga, Gb Y K, en marcos restringidos
contra traslación lateral como
GaGb(!!...)2+ Ga + Gb(l_ 'Ir/K) + 2 tan 'Ir/K = 1 (7-3)
4 K 2 tan 'Ir/K 'Ir/K

También se puede programar esta ecuación para valores de G; YGb , Yhallar el valor correspondiente de F = "TrIK que satisfaga la igualdad. Este trazado se
muestra en la figura 7-Sb.

Ga K Gb Ca K Gb
20.0 50.0 1.0 50.0 100.0 10.0 100.0 100 10.0 50.0 50.0
\4. 30.0 5.0 30.0 4.05.0 0.9 5·8 200 4.0 20.0 3.0 3.0
2.0 2.0
10.0 3.0 10.0
9.0 9.0 0.8 8.0 8.0
70 7.0 1.0 1.0
6.0 6.0 0.9 0.9 0.8 0.8
5.0 5.0 0.7 0.7
4.0 2.0 4.0 0.6 0.7 0.6
0.5 0.5
3.0 3.0 0.4 0.4

20 2.0 0.3 0.3
1.5 I ?". 0.6 0.2 0.2
1.0 1.0
0.1 0.1

O 1.0 O O 0.5 O

lo a) Con desplazamiento lateral 20 b) Sindesplazamiento lateral
Figura 7·5 Nomograrnas para determinar las longitudes efectivas de las columnas en marcos conti-
nuos, para las condiciones indicadas de restricción lateral.

<!-- p. 352 -->

352 DISEÑO DE VIGAS-COLUMNAS

El uso de ambos nomogramas de la figura 7-5 implica el cálculo de los valores de

"2.Ele/ Le (en el extremo lejano de la columna) (7-4)
/ Lb Ga = "2.Elb
"2.Ele/ Le y (en el extremo cercano de la columna) (7-5)
/ Lb Gb = "2.Elb

Es evidente, de la derivación que implica a Ga YGb , que si se llama G, a uno de los
valores, el otro extremo produce a G; (es decir, los valores se pueden usar en forma intercambiable).
Cuando E = constante, se puede eliminar en las ecuaciones (7-4) y (7-5); sin
embargo, cuando se desarrolle pandeo inelástico, se debe usar E en vez de E en la
relación El!Le' Entre otras consideraciones se incluyen:

l. Cuando la columna está articulada en la base, la relación Elb/ Lb es cero, ya
que el, valor teórico de 1 - Oque da por resultado G - ce , Se sugiere que se use
para este caso un valor G = 10 ya que existen algunas dificultades para obte-
ner una verdadera conexión articulada.
\2. Cuando la columna está fija rígidamente a una base infinitamente rígida, la re-
lación Elb/ L g - 00 y la G correspondiente -O. Se sugiere para este caso que se
use G = 1.0, ya que es dificil producir una conexión verdaderamente rígida.
\3. Cuando la viga o trabe se use con la adecuada fijación a la columna de que se
trate pero:
a. El extremo lejano está articulado: multiplíquese la relación EI/L, x 1.5.
b. El extremo lejano está fijo: mulripliquese la relación El/L. x 2.0.
\4. Si las vigas están conectadas simplemente a ¡a~ coru.nuas, U.>\<"::>"': ¡J.. r., 1\< 1;-0 fig- l1-
ra 6-3.

El uso de los factores K obtenidos de la manera que se acaba de describir, ha
sido requerido por el AISC desde 1963, y por la AASHTü desde 1974. Los factores K tienden a ser considerablemente mayores que los de la figura 6-3, que se usaban por el AISC con anterioridad a 1963. Como se han usado valores menores de
K en estructuras que tenían una adecuada historia de servicios, se le ha dado un
nuevo enfoque a la deducción de Ga, G¿ Y la K resultante. Yura indicó correctamente que cuando la relación KL/r fuera menor que Cco se debía considerar el
pandeo inelástico y que se debía usar E, en las ecuaciones (7-4) y (7-5) (véase The
Effective Length of Columns in Unbraced Frames, AISC Engineering Journal,
abril, 1971). El uso de E, es equivalente a

El
Gineláslica = E Geláslica (7-6)

\~ 1, se sigue que el uso de Uineláslica, da una Kineláslica \< Keláslica'Como El = >. E y >.

<!-- p. 353 -->

LONGITUDES EFECTIVAS DE COLUMNAS EN MARCOS DE EDIFICIOS 353

Como El es algo difícil de obtener, y recordando que en la deducción de las
ecuaciones del AISC para Fa en la región inelástica,

KL
O\<-\<C r - e

se usó esencialmente un FS para F;." donde

'TT'2E F = t
cr (KLjr)2

y en la región elástica

F =-----
a SF(KLjr)2

Se sigue de dichas ecuaciones que (usando i = inelástico, e elástico)

(7-7)

Este cálculo deja a un lado el FS variable, que varía desde 1.67, para KL/r = O
hasta 23/12 (se usará 1.92 para los cálculos manuales) para KL/r = C: Para la
mayoría de las columnas en el rango de KL/r = 40 a 60, la variación del FS es
esencialmente despreciable. El uso de la ecuación (7-7) requiere valores de Fae como los de Fa;, para el mismo valor de KL/r, por lo que es necesario calcular una
tabla de valores como la tabla II-7 o la VI-7 (SSDD) y el uso de Fae = F: para
corresponder con las especificaciones del AISC
F' = 12'TT'2E (7-8)
e 23(KLjr)2

Nótese que este valor es independiente de Fr Los valores que se muestran en la
tabla de F; > F, tienen como fin el uso de la ecuación (7-7), Yno para ser usados
como esfuerzos reales que se pudieran usar en un diseño.
El uso de la ecuación 7-7 en un diseño real requiere iteración; esto es, se supone una columna; se calculan 0a, Ob Yse halla K; se calculan KL/r y F;, F;; se
revisan Oa y 0b; y se halla un nuevo valor de K para .'

l. Varios ciclos, o
\2. Hasta la convergencia, o
\3. Hasta un valor límite arbitrario de K, como 1.2 ó 1.5.

Por supuesto que, si la sección elegida no resulta adecuada, se debe escoger una
nueva sección y repetir los cálculos. Dizque propuso que (véase AISC Engineering

<!-- p. 354 -->

354 DISEÑO DE VIGAS-COLUMNAS
Journal, No. 2, 1973) se podía eliminar la iteración de K, usando fa = P / A en lugar de Fa para obtener

(7-9)

En lugar de usar fa, que podría reducir G, excesivamente, se puede elegir usar Fa
\= 0.6 Fr Nótese cuidadosamente, de nuevo, que el valor reducido de G se usa solamente cuando KL/T \< Cc• Debe ser evidente por sí mismo que los valores de K
\~ 1.0, no se deben ajustar.

Ejemplo 7-2 Dada una porción del marco de un edificio de muchos pisos,
con deflexión lateral no impedida y que se muestra en la figura E7-2; se supo-
ne que hay un soporte adecuado perpendicular al marco, de manera que no
hay que considerar K, (por ejemplo, contacto estrecho con los muros inte-
riores de mampostería); F" = 36. Diséñense las columnas CD, usando las es-
pecificaciones del AISC..

SOLUCION Supóngase que KL ~ 14 pies, y se usa la tabla 11-4 para obtener
una sección tentativa W14 x 99:
A = 29.10 pulg- I Ty = 3.71
t, = 1110.0 pulg" ~ r, - = 1.66
Ty
Calcúlese
_KL = 14(12) = 27.2 \< e
3.71(1.66) e

4~Ok 370k
JD JF
1:'16 X 50 Wl6 X 40 Wl6 X
30' o- 24' 40 o-
X
:!: W16.' 50 W16 X 40
1= 659 pulg4 o- 1=518pulg4 " o-
\<-, x
:!: W16 X 50 W16 X 40 ""
o-o-
X,.
e 3\<
505t t'igura E7-2

<!-- p. 355 -->

LONGITUDES EFECTIVAS DE COLUMNAS EN MARCOS DE EDIFICIOS 355

Hállese K: úsese WI4 x 99 en tres pisos: /

. 'i.Ic/Le IIIOjl4 + lllO/12
/ Lb = 659/30 + 518/24 Ga = Gtope= 'i.Ib
\= 3.94

Redúzcase por efectos inelásticos:

520 6 k' / 2 fa = 29.1 = 17.8 ip pulg

Obténgase de la tabla U-S el valor KL/r = 55, para r, = 17.9. Para KUr =
55 se calcula

F' = .,,2E = 49.4 kip/pulg? (calculado también en la tabla 11-7)
e 23/12 X 552

El valor revisado de

G = G fa ) = 3 a ( F; .94( 49.417.9) = l .43

Se nota, para Gb , que la columna está fija respecto a la base, de modo que lb
\- 00;

\- 'i.IcI Le - lllO/14 - O 10 Gb - 'i.I / Lb - 00 - se usa .
b

Este valor no se reduce por comportamiento inelástico. Se obtiene, de la figura 7-50, K = 1.38. Con K = 1.38,

KL 1.38(14)(12) = 37.6
r. 3.71(1.66)

Se obtiene de la tabla U-5, con este valor de KL/r,

Fa = 19.37 kip/pulg'
Pperm = 29.1(19.37) = 563:6 > 520 kip/pulg'

Como este valor es unos 40 kips más grande de lo necesario, se probará una
sección WI4 x 90:
r, Ix = 999.0 pulg" Ty = 3.70 pulg - = 1.66 A = 26.50 pulg-
Ty

<!-- p. 356 -->

356 DISEÑO DE VIGAS-COLUMNAS

_ 999/14 + 999/12 _
Ga - 659/30 + 518/24 - 3.55
f 520 . 2 KL Ja = 26.50 = 19.62 kip/pulg - = 34 (tabla 11-5) r
Se obtiene de la tabla 11-7 (nótese que esta tabla se obtuvo en la computado-
ra, utilizando un FS = 23/12):
F: = 129.18 kip/pulg/
19.62 )
Ga = 3.55 ( 129.18 = 0.54
G; = 1, como antes, y, de la figura 7-5a, se obtiene K = 1.25.
KL = 1.25(14)(12)/(3.70 X 1.66) = 34.2
r.
Fa = 19.64 kip/pulg- (tabla 11-5)
Pa = 26.50(19.64) = 520.5 > 520 kips Correcta
Se usará una sección W14 x 90 para la columna 1.

Ejemplo 7-3 Dado el marco de la figura E7-3, con posible desplazamiento
lateral, se usarán las especificaciones del AISC y F, = 345 MPa para hallar el
tamaño requerido de las columnas. Usese la misma sección para ambas.

SOLUCION Hágase una estimación inicial del tamaño de la columna, de
modo que KL/r = 40, para la que Fa = 178.2 MPa. Para Fa = 178.2 MPa,
el área tentativa de la columna es

_ 2400 _ -3 2
A - 178.2 - 13.5 x 10 m

2000 kN 2400
W410 X 99.7 kN¡ l
/x=397.1 X 10 6 m4

e ' -,> Contraventeo en el eje y í.,,:
/l'
\~I
Figura E7·3

<!-- p. 357 -->

LONGITUDES EFECTIVAS DE COLUMNAS E:-l MARCOS DE EDIFICIOS 357

Pruébese W250 x 114.6:
A = 14.58 X 10-3 m2
rx = 114.05mm
Ix = 189.4 X 10-6 m"
189.4/4.6 O
Ga(tope)= 397.1/6.5 = .673
2400 KL
fa = 14.58 = 164.6 MPa -.- = 53 (tabla VI-6) r.
ooo~ = 366.6 MPa (También tabla VI-7) F: = '17'2(200
23/12 x 53
Valor ajustado de Ga = 0.673(164.6/366.6) = 0.302.
Columna de la derecha:

' -- 189.4/4.6 __ O • d o. d l AISC) Gb usese 1.00 (Recomen acion e 00
Columna de la izquierda:

G = 189.4/4.6 = 00 úsese 10.0 (recomendación del AISC) b O
Obténgase de la figura 7-50:

K = 1.2 para la columna de la derecha

K = 1.75 para la columna de la izquierda

Compruébese primero la columna de la izquierda, ya que K es mucho mayor
que en la columna de la derecha:
KL = 1.75(4.6 x 1(00) = 70.6
r 114.05
Fa = 143.7 MPa (tabla VI-6)
Pa = AFa = 14.58 x 143.7 = 2095 kN > 2000 Correcta

Compruébese ahora la columna de la derecha:
KL = 1.2(4.6 X 1(00) = 48.4
r, 114.05
Fa = 169.7MPa
Pa = 14.58(169.7) = 2474.2 > 2400 kN Correcta

<!-- p. 358 -->

358 DISEÑO DE VIGAS-COLUMNAS

Una solución; se usan secciones W250 x 114.6. III
Ejemplo 7-4 Repítase el ejemplo 7-3 con el desplazamiento lateral restringido.

SOLUCION Una solución sería usar K = 0.80 para la columna de la izquier-
da de acuerdo con la figura 6-3b; correspondientemente, se obtendrá K =
0.65, usando la figura 6-30 para la columna de la derecha, y usando en am-
bos casos los valores "recomendados" de diseño. Alternativamente, se
puede usar la figura 7-5b.
Como K tiene que ser menor que 1.0, se usarálá r'experíencia" del
problema anterior para comprobar una sección algo más ligera. Pruébese
una sección W250 x 101.2
A = 12.9 X 10- 3 m2 rx = 112.78 mm L; = 164.0 X 10-6 m"
164/4.6
G¿ = 397.1/6.5 = 0.583
¡ 2400 186 MP KL = 31.6 Ja = 12.9 = a r
F; = 1032 MPa (Interpolando en la tabla VI-7)
186 ) Ga = 0.583 ( 1032 = 0.105
Gb = 10 para la columna de la izquierda
Gb = 1.0 para la columna de la derecha

Usando la figura 7-5b, se obtiene
K = 0.72 para la columna de la izquierda
K = 0.65 para la columna de la derecha

Compruébese la columna de la derecha:

KL = 0.65(4.6 X 1000) = 265 Fa = 190.3 MPa rx 112.78 .
r, = 12.9(190.3) = 2455 > 2400 kN Correcta

Compruébese la columna de la izquierda

KL = 0.75(4.6 X 1000) = 30.6 Fa = 186.8 MPa
r. 112.78
r, = 12.9 X 186.8 = 2410 > 2000 kN Correcta
III
Se usará un W250 X 101.2.

<!-- p. 359 -->

REDUCCION DE LAS FORMULAS DE DISEÑO PARA VIGAS-COLUMNAS 359

7-4 DEDUCCION DE LAS FORMULAS DE DISEÑO
PARA VIGAS-COLUMNAS
IAntes de la sexta edición de 1963 del AISC Manual 01 Steel Construction, el dise-
ño de los miembros a compresión sometidos a flexión, se obtenía como I

Dividiendo esta ecuación por Fperm = Fa, se obtenía la ecuación de interacción,
con un uso muy amplio (AISC, AASHTü y AREA) Ycon flexión con respecto a
ambos ejes, Ibx,IbY' así como con carga axial, en la forma siguiente

(7-10)

Antes de 1963, el valor de Fbx = Fby = Fb.lse recuerda ahora que F¿depende de
diversos factores, que incluyen la longitud no soportada y los criterios de la sec-
ción compacta, yen general el AISC permite

Fbx = 0.66~
o Fbx = O.tíOFv
o Fbx = Valores tomados de las ecuaciones (1.5-6a), (1.5-6b) ó (1.5-7)
Fby = 0.75~ para los perfiles W, debido a que tienen patines sólidos
rectangulares ;/

En general, la ecuación (7-10) se usa solamente en ciertas condiciones limita-
das de esfuerzo. Para el resto de los casos de esfuerzo, se usan otras fórmulas ba-
sadas en la investigación, el diseño plástico, y los conceptos de estabilidad elásti-
ca. Estas condiciones se desarrollarán parcialmente en-algunos de los párrafos
que siguen, de manera que el profesionista tenga alguna idea de cómo proceder si
el diseño se apartara de la rutina.
Refiérase a la figura 7-6 para ver una sección rectangular corta (L/r - O), de
dimensiones b x d, que está sometida a esfuerzos tanto por una fuerza axial co-
rno por un momento, suficiente para desarrollar una articulación plástica. El mo-
mento plástico, en presencia de una fuerza de compresión P es

(a)

Sustituyendo Yo (que se muestra en la figura 7-6), se obtiene

(b)

<!-- p. 360 -->

360 DISEÑO DE VIGAS-COLUMNAS

b
P = Acoy = b( Cl'O )0"
" .1'0 '" Picha" T
IH-r?'ti"'?,+- c.\'o-_·- 1. Mpc = máximo momento plástico con una fuerza de
\~\<..J....L.f--'-'I--L compresión P

Ac=hXcI'O
Figura 7-6 Formación de una articulación plástica en un miembro muy corto sometido simultáneamente a fuerza axial y momento.
Multiplicando la relación de P por d-/d» y notando que b2d 2(}; = p/' se obtiene

2 2
M = (}ybd (1 _ p ) (e) pe 4 p2
Y

Sin embargo, de la sección 3, ejemplo 3-3, M; = (}ybd2/4; se obtiene, por consiguiente

(7-11) :;:=I-(~r

10 fk:----,----,-----,----,---r---..,

0,8 1------'''''''~'"'"'7H----+----1---+----i
P)2 ( P"
0,6 1---+----'l."""",----+-'*---1---+__+_

0,c1---+----+----==""""',------>0,\<-----''Q¡-+_-.-Ir+-i

Oc 0.4 0,6 0,8 10
M Figura 7-7 Se muestra la gráfica de
Ma las ecuaciones de interacción. Po Y
M¿ = valores permisibles.

<!-- p. 361 -->

REDUCCION DE LAS FORMULAS DE DISEÑO PARA VIGAS-COLUMNAS 361

Aunque los desarrollos anteriores se han hecho para una sección rectangular, son
también válidos para todos los perfiles (incluyendo W, S, y M). En la figura 7-7 se
muestra una gráfica de la ecuación (7-11). También se muestra la gráfica de una
ecuación lineal de la forma

(d)

Si se trazara

P M
P+M= 1.0 (e)
y p

Para KLlr = 40 y para KLlr = 120, se podrían obtener las líneas rectas que aparecen también en la figura 7-7. Estas curvas tendrán algún error, ya que se ha ignorado el efecto P - f:J.. Se podría usar un método iterativo para incluir el efecto
P- f:J. como en la ecuación (b) de la sección 7-2. Sin embargo, se puede demostrar
[véase, por ejemplo, Timoshenko y Gere, Theory of Elastic Stability, 2a. ed.
(Nneva York: McGraw-Hill Book Company), sección 1-11] que es suficientemente exacto (con un error del orden de 1 a 2 por ciento) amplificar el momento debido a P-f:J.:

(j)

A este factor se le puede llamar factor de amplificación, ya que su efecto es amplificar o aumentar Mo ' Este valor se ha usado en las curvas que aparecen en las figuras 7-8 a 7-10. La razón PIPees la relación entre la carga real de la columna y la
carga de la columna de Euler, yfalF; es sencillamente el resultado de dividir ambas cargas por el área de la columna. Con este ajuste en el momento flector, se
puede reescribir la ecuación (e) para obtener

(g)

En la figura 7-8 se muestra una gráfica de la situación de las cargas cuando MI
\= M 2 = M, yen la figura 7-9, el caso cuando MI = My M 2 = O. Estas dos gráficas representan el rango extremo de los casos cuando se carga una columna con
momentos terminales, como sucede en un marco de edificio. Las curvas que se
muestran en las figuras 7-8 y 7-9 se han trazado usando una modificación de la
ecuación (e), propuesta por Galambos y Ketter (Transactions, ASeE, Vol. 126,
páginas 1-25, 1961), que da para iguales momentos en los extremos:

(h) ~) ~ = 1 - c( - D( ~r

<!-- p. 362 -->

362 DISENO DE VIGAS-COLUMNAS

\.0 r----,-----,r-----,----,----r-----,
\=Af"a P ~ = -- D/P)2]a p. =A\<O_6F,.l M. [1 -e .!....)Pe \p.
0_8 f--~,..--I-a = 1 _ ~----+--,..__II__----1I_:_:------l
Pe

0.6 t--__t-~---:-1I--__t~-__t--+----

Al

0.2 f------I-'::""O;,------1¡...::>o.....

O'---__~__...L-____'____L.__ _= __'
O 0_2 0.4 0.6 0.8 \.0
Figura 7-8 Influencia de KL/r y el
factor de amplificación sobre la in-
teracción de las columnas.

1.0,------,r----,----r------,-----r-----,
\-M = [ F+G -P)~ a P=AF.
M. p. P.=ACO.6Fr l
0.8t---"~t--a= 1 - P/Pe+-- - +- ,,2EI Pe = - -
( KL)2

0.6 f----f---,......P*_
P
Ji;,

0.2 f----f------"'.....::---+_---"'"'lE.::I-'~.----+_~-_e

°O'-------'----'-----L---'----:-"-:---.c-'
0_2 0.4 0.6 0.8 \.0 1.2
Al
\111. Figura 7-9 Gráfica de KL/r de 40
y 120 para una columna con mo-
mento en un extremo.

y para momentos desiguales en los extremos, una ecuación lineal de la forma

(i)

Los coeficientes dependen de KL/r, y entre los diversos valores dados por Galambos y Ketter, se encuentran los siguientes:

<!-- p. 363 -->

REDUCCION DE LAS FORMULAS DE DISEÑO PARA VIGAS-COLUMNAS 363

KL/r e D F G
o 0.42 0.77 1.13 1.11
20 0.70 0.46 1.14 1.18
40 0.99 0.17 1.16 1.23
80 1.81 -0.72 1.19 1.52
120 3.16 -2.51 1.25 2.53

Las gráficas que se han hecho utilizando las ecuaciones (h) e (l) son razonablemente satisfactorias para todos los casos con momentos extremos iguales, pero es
bastante conservador para aquellos casos de momentos extremos desiguales, en
particular para el extremo de M2 = O. Esto se puede tener en cuenta por medio de
un factor de reducción Cm' Entre los varios valores propuestos por los investigadores se tienen los dos siguientes:

(7-12a)

(7-12b)

Se puede tomar nota de que la recíproca de la ecuación (l7-12b) se usa como el
factor de amplificación para las vigas sin soporte lateral. La ecuación (7-12a) se
usa como Cm en las especificaciones de diseño del AISC y de la AASHTO. Es necesario considerar los signos de la manera siguiente, cuando se usa la razón
fttí!M2 y donde MI es el menor de los dos valores de los momentos extremos:

Esto está de acuerdo con la definición de C; (es decir, la flexión con curvatura
simple es más crítica en el caso de la inestabilidad por pandeo que la curvatura doble y, de una manera similar, se reducirán los efectos P-!:J.).
Por lo general, el efecto del uso de Cm es disminuir el efecto del factor de
amplificación y se ilustra en la figura 7-10. El uso de Cm produce una intersección
de la curva real de interacción de la columna con la curva de

[reordenando la ecuación (d)]

para valores diferentes de M¡!M 2• = 1.0 y con una rapidez determinada por la relación M¡!M 2• A la derecha de la intersección de las dos curvas, la ecuación (d) es
la que rige. Esta situación requiere el uso de dos ecuaciones para el diseño, y
luego utilizar el valor más crítico de

<!-- p. 364 -->

364 DISEÑO DE VIGAS-COLUMNAS

P M 1 (h) Pe Cm = 1.0 Py + Mp 1 - P/

ó, M P
\= 1.18 M + 1.18p (d) p y

ooL-----'-------'------L----L----L.---"
0.2 0.4 0.6 0.8 1.0 1.2
M
M.
Figura 7-10 Gráfica de la interacción de columnas con un momento de extremo, y con el efecto de
usar Cmcomo comparación (lineas de puntos).

Esto se debe a que resulta más fácil resolver para el valor más crítico usando las
dos ecuaciones que hacer una gráfica y localizar la intersección y luego usar la
ecuación que gobierne. Estas ecuaciones se ajustan para su uso en el diseño por
la sustitución de Pcr por P, y Mperm por M p , y con un área de sección y un módulo
de sección para obtener los esfuerzos. Esto da
r; P
Fa = A X SF fa = A
Fb = esfuerzo permisible de flexión
M f b = -S

Combinando los términos y extendiendo el caso a la flexión biaxial, se obtiene

AISC Ec. 1.6-1a

(7-13)

<!-- p. 365 -->

REDUCCION DE LAS FORMULAS DE DISEÑO PARA VIGAS-COLUMNAS 365

y
AISC ecuación (1.6-1b)
\~ + lbx + lby \< 1 (7-14)
0.6.F;. F bx F by-

Haciendo nuevamente referencia a la figura 7-7, senota que no hay ninguna reducción en la capacidad de momento hasta que PIPy > 0.18, de manera que redondeando 0.18 a 0.15 por conveniencia y para ser conservadores, se obtiene:

Limitación de faiFa :5 0.15: ecuación (1.6-2) del AISC
fa + Ax + Ji,y \< 1 (7-15)
Fa Fbx Fby-

Como las ecuaciones (7-13) a (7-15) son muy elaboradas, excepto en una
computadora. multipliquemos todas por AFa para obtener [usando la ecuación
(7-13), sinfbY para una particular demostración]:

pero f aA = la carga P real de la columna y AFa =carga máxima permisible en la
columna, Po (y no es el mismo valor que se muestra en las figuras 7-8 Y7-9, Yque
se usó para desarrollar las curvas en dichas figuras). Notando además que A =
MIS, se define AlS = B, se multiplica falF' e por AlA, se toma F' eA = Pe =
0.149 X 106/(KLlr)2 kip/pulg- (unidades p lb seg). Se obtiene el siguiente resultado para la flexión con respecto al eje X:

donde ax = 0.149ArZ X 102 kip/pulgs (unidades p lb seg)
P(KLP = kip/pulgPor analogía, la ecuación (7-13) se convierte en

Fa a F ay x +BC M_a \<P P + B x Cmx M x-F 2 y F y ··V- perm ) bx - by ay _ p(KLy)2 - ax P(KLx
(7-13a)
Para la ecuación (7-14), se obtiene de una manera similar

(7-140)

<!-- p. 366 -->

366 DISEÑO DE VIGAS-COLUMNAS

Cuando fa/Fa (O PIPa) ::5 0.15, se puede obtener

(7-15a)

Un cuidadoso análisis de estas ecuaciones demuestra que Fa se basa en Pero que depende a su vez del valor crítico de KL/r. La resistencia a la flexión y cualquier
amplificación/reducción de los efectos del momento será con respecto al eje de
flexión que tengan los subíndices indicados. Así, en muchos problemas, el esfuerzo axial permisible, Fa' se basará en Kl.rr., pero el término P(KL)Z dependerá del
eje que resista la flexión. Como el eje X es el que se usa generalmente, será el producto P(KLx)Z el que se requerirá comúnmente.
En general, se considera que la forma modificada de estas ecuaciones de interacción son más fáciles de usar, ya que el lado derecho (Prerm) se puede tabular para unas cuantas secciones de columnas, y para varias longitudes supuestas de columnas, basadas en KL/ry- De manera similar, se pueden calcular y tabular los
términos a., ay, B, Y By. Estos valores se muestran en las tablas 11-4 (F; = 36
kip/pulg-) y VI-4 (F, = 250 MPa) para los perfiles W usados comúnmente como
columnas. El manual del AISC tiene también estas tabulaciones para acero F, =
50 kip/pulg- e incluye el uso de perfiles S y secciones de tubos y tuberías. -

7-5 DETERMINACION DEL COEFICIENTE C'I! DE
REDUCCION POR INTERACCION

Cuando una columna de un marco estructural está restringida contra la traslación
lateral, y tiene momentos en los extremos, como se ilustra en las figuras 7-8 a
7-10, y 7-11a, el valor de Cm se calcula usando la ecuación (7-12a):

O.4M,
\~ 0.4 Cm = 0.6 - --¡;¡-
2

poniendo atención en los signos (simple curvatura = - M/Mz). Nótese tambien
que MI se define como el menor de los valores de los dos momentos extremos.
Cuando sea posible el desplazamiento lateral (figura 7-11b), la especificación del
AISC permite

Cm = 0.85 (hay desplazamiento lateral)

Cuando la columna tenga cargas transversales, como en la figura 7-llc, se usará

Cm = 1.0 + ~~
e

donde fa = esfuerzo real en la columna

<!-- p. 367 -->

FORMULAS DE DISEÑO DE LA AASHTO y EL AREA, PARA ViGAS-COLUMNAS 367

F;! = esfuerzo de Euler, como se definió anteriormente (incluyendo FS =
23/12)
'1t = factor determinado de la figura 7-11d, y que depende de la restric-
ción en los extremos y de la carga transversal.

7-6 FORMULAS DE DISEÑO DE LA AASHTO y EL AREA,
PARA VIGAS-COLUMNAS

El diseño de la AASHTO usando el esfuerzo de trabajo utiliza esencialmente las
mismas ecuaciones que el AISC con algunos ajustes adicionales del factor de
amplificación. El factor Cm se define de manera similar al del AISC.

(a) (b) (e)

1/1 1/1

0.0 -0.2 1 -l"""""""~ -f :A;
.-
\-rllllllllllllllll~- -0.3 -0.4 1 -t ~-
_~I IIIIIIIIIIIIIIIII~~ -0.4 -0.6 1 -~ ~-

(d)
Figura 7·11 Factor de reducción Cm' para las ecuaciones de interacción de vigas-columnas. (o) Sin
desplazamiento lateral: Cm = 0.6 -0.4M¡/M2• (b) Con desplazamiento lateral: Cm = 0.85. (e) Co-
lumnas con carga transversal: Cm = I + F'e. (d) Se muestran diversos casos de carga transversal y
factores .

<!-- p. 368 -->

368 DISEÑO DE VIGAS-COLUMNAS

fa + CmJbx + Cmyfby s (7-17)
Fa (1 - fal F:~)Fbx (1 - fal F:;)Fby
y fa + fbx + fby \< 1 (7-18)
0.472Fy Fbx Fby-

2
F" = 7T E
e 2.12(KLlr)2

En general, se usa Cm = 0.85 para las condiciones en los extremos, de las figuras
7-11b y e; se usa Cm = 1.0 cuando el momento interior es mayor que los valores
en los extremos, o con un momento interior y un momento cero en los extremos.

Las ecuaciones del AREA son similares a las ecuaciones del AISC. Para
fa/Fa> 0.15:

(7-19)

donde F'''=----- e 1.431(KL1rf
Además, en los puntos soportados lateralmente en el piano de flexión:

(7-20)

Para/l/Fa :5 0.15, se usa

(7-21)

7-7 DISEÑO DE VIGAS-COLUMNAS USANDO
LAS ECUACIONES DE INTERACCION

El diseño de vigas-columnas usando las ecuaciones de interacción es esencialmen-
te un proceso de ensayo (iterativo). Se selecciona tentativamente una sección y se
analiza, y si la sección es muy pequeña, se elige una nueva sección, y se repite el
proceso hasta que se obtenga una sección satisfactoria (tanto en resistencia como
en peso). Se pueden delinear los pasos como sigue:

l. Determínese la fuerza axial y los momentos de las columnas. Se notará que es-
te paso es también iterativo, ya que no se encuentran los valores indetermina-
dos de un marco, hasta que se haya usado una sección tentativa en el análisis.

<!-- p. 369 -->

DISEÑO DE VIGAS-COLUMNAS USANDO LAS ECUACIONES DE INTERACCION 369

\2. Calcúlese K para obtener KL. Puede que sea necesario determinar tanto K, co-
mo Ky , dependiendo de las condiciones en los extremos de la columna y del so-
porte lateral.
3 o Estímese la contribución del momento (y se usará la flexión con respecto a un
solo eje como ilustración) como una carga axial equivalente tlP:

Fa BM- f3 usando una parte de la ecuación (7-13a) tiP = em Fb

o usando una parte de la ecuación (7-14a)

La inspección de la tabla 11-4 (o VI-4) indica que

(6.5 a 900 en SI)

y (3.3 a 6.5 en SI)

f3 = estimado para -----''------'-
ax - P(KLJ2

Los valores de la flexión con respecto al eje Y son considerablemente mayores,
pero es posible hacer una estimación similar. Si se desea, se puede hacer una
estimación de tiP de una manera algo parecida para usar las ecuaciones de la
AASHTO y el AREA.
\4. Calcúlese la carga equivalente permisible como
P eq = P + tiP =P + (0.2 a 0.3)M (M en pulg kips
\=P + (6.5 a 9.0)M (M en kN . m y SI)

50 Entrese con este valor de P en una tabla como la 11-4 o VI-4 (o en el Manual
del AISC, o en tablas que se han preparado para el diseño usando una compu-
tadora) con el valor de KLyy así obtener el P,ablao Si KJK, :5 fJfy, rigen los va-
lores de KLIr.; si KJK, > fxlr.. rige la relación KLxlfxYes preciso usar un va-
lor ajustado de KL' para entrar en dichas tablas, valor que se obtiene como

Es necesario usar fxlr., ya que la relación es fija para una sección pero no se
conoce hasta que no se haya seleccionado tentativamente una sección.
\6. Regístrense P,abla, A, r., fxlfy, Le, t.; B¡, y a; Se necesitan Le yt.; de modo que.
se pueda hacer una rápida determinación de Fb:

<!-- p. 370 -->

370 DISEÑO DE VIGAS-COLUMNAS

F; = 0.66Fy si Lnosoportada :5 Le
Fb = 0.6Fy si Lnosoportada :5 L;
F; = valor calculado de la ecuación (4-23), (4-26), o (4-27) si~soportada > L;
La longitud no soportada es la real y no el valor KL, y se toma con respecto al eje
de flexión.
\7. Calcúlese el valor crítico de KL/r, obténgase o calcúlese Fa' Ycalcúlese10 =
P/A. Véase silo/Fa :5 0.15. Si es menor la relación, úsese la ecuación (7-15)
para ver si la sección es adecuada. Silo/Fa> 0.15, será necesario comprobar
ambas ecuaciones, la (7-130) y la (7-140). Calcúlese en este caso:
P(KL)2 úsese el valor de KL con respecto al eje de flexión, el que puede ser
diferente del valor critico de KL/r usado para calcular el esfuerzo
axial permisible Fa.
\8. Verifíquese tanto la ecuación (7-130) como la ecuación (7-140) para satisfacer

Se debe tratar de obtener una igualdad tan estrecha como sea posible con una
de las ecuaciones (no se puede hacer simultáneamente con ambas ecuaciones) y
si:
P + Peq «Ptabla investíguese una sección más ligera
P + Peq > Ptabla se usará una sección mayor para satisfacer el diseño

Teniendo cuidado y haciendo un examen preliminar de la tabla 11-4 (o VI-4),
se puede obtener una sección adecuada en uno a tres ensayos. Esto es posible
puesto que las tablas muestran poco cambio en r/ry y B para las dos o tres secciones a cada lado de la sección elegida.

Ejemplo 7-5 Dados la columna y los momentos flectores de la figura E7-5,
como parte del marco de un edificio, en el que es posible el desplazamiento
lateral, se limitará la sección de la columna a una ÍlO mayor que una W12.
Usense las especificaciones del AISC y acero A-36. Selecciónese una sección

42.5

38.4 pie

Figura E7-S

<!-- p. 371 -->

DISEÑO DE VIGAS-COLUMNAS USANDO LAS ECUACIONES DE INTERACCION 371

tentativa y úsense las ecuaciones básicas (7-13), (7-14) o (7-15), según sean
aplicables.

SOLUCION Para mantener el diseño de una\ viga-columna usando las
ecuaciones de interacción en perspectiva, se supondrá que K, = 1.3 YKv =
1.0, Yque los valores de K no cambian con el tamaño de la sección.

Cm = 0.6 - 0.4(+ ~~:~ ) = 0.24 \< 0.4

Usese Cm = 0.85, con desplazamiento lateral. Después de estudiar un poco la
tabla 11-4 (con P \< 110), se ensayará la sección W12 x 50:
\~ 236 kip/pulg- A = 14.7! I pulg' (Se usa la tabla 11-4) p perrn
KL 144
ry = 1.96 pulg rr = 1.96 = 73.5

\~ , - = 2.64 Fa = 16.06 kip/pulg (tabla 11-5)
ry
Le = 8.5 \< 12 Lu = 19.6 > 12 - Fb = 0.6Fy = 22 kip/pulg'
Sx = 64.7 pulg ' (tabla 1-3)

P 110 748' 2 fa = A = 14.70 = . kip/pulg

fa = 7.48 = 0.47 > 0.15
Fa 16.06

Se han de usar ambas ecuaciones, la (7-13) y la (7-14):
F; = '1T2E 2 '1T2E 2 = 113.8 kip/pulg/
, 1.92(KLjrx ) 1.92(36.2)
fa 1 7.48 934 /3 = 1 - F; 113.8 = O. i -
¡ = M = 42.5(12) = 788 kip/pulg/ Jbx Sx. 64.7 .
;1,
Por la ecuación (7-13);
fa + Cmx!bx \<
Fa /3Fbx -
47 0.85(7.88) = 0796 10 0 . + 0.934(22) ..«.

<!-- p. 372 -->

372 DISEÑO DE VIGAS-COLUMNAS

Por la ecuación (7-14):

\~+fbX \<1
0.6F;. Fbx -
7.48 7.88 = 070 10 22 + 22 .«.

Ensáyese una sección menor -pruébese W12 x 40:

2 110 k' / 2 A = 11.80pulg fa = 11.80 = 9.32 rp pulg

KL 'y = 1.94 pulg ~ - = 74.2 Fa = 15.98 kip/pulg'
'y
KLx = 1.3(12)(12) = 36.6
r, 1.94(2.64)
\~ Fb = 0.6F;. = 22 kip/pulg? L u = 16 > 12 ft
S; = 51.9pulg 3
fa 9.32 8 015 f = 42.5(12) = 983kl)/pulg2 Fa = 15.98 = 0.5 > . Jb 51.9 . I

Por la ecuación (7-14):

0.85(9.83) = 0.991 \< 1.0 Correcta O58 . + 0.92(22)

Por la ecuación (7-14):

Correcta

Usese una columna W12 x 40. III

Ejemplo 7-6 Dados la columna y los momentos flectores, que se muestran
para el marco de un edificio, con el desplazamiento lateral para K, restringi-

<!-- p. 373 -->

DISEÑO DE VIGAS-COLUMNAS USANDO LAS ECUACIONES DE INTERACCION 373

do con el uso de contravientos y muros de cortante; úsense las especifica-
ciones del AISC y F; = 250 MPa para el acero, y seleccionar la sección tenta-
tiva de una columna.

SOLUCION Se hace referencia a la figura E7-6 y se supone que

K; = 1.25 K; = 1.0
O.4M)
Cm =06--->04• M - •
2
\= 0.6 - (0.4)( - *) = 0.95 > 0.4
Usese Cm = 0.95 el (AISC permite realmente Cm = 0.85, si así se desea).
Tentativamente:
P a P dada + Pequiv
;;;¡; 445 + 7(61) [estímese el factor como 7 (entre 6.5 y 9)]
;;;: 872 kN
Revísese la tabla VI-4 y elijase W310 x 59.5:
P tabla = 860.5 kN
I
\= 2.64 > 1.25 Correcta A = 7.61 X 10-3 m2 'x 'y 1
'y = 49.28 mm KL = 3.45(1000) = 70 O 'y 49.28 .
Fa = 114.1 MPa (tabla VI-5)
I
Le = 2.58 m Lu = 4.87 m > 3.45
Fb = 0.6F;. = 150MPa
B; = 8.94 0x = 132.8 X loJ kN . m2
P(KLx )2 = 445(1.25 X 3.4Sf = 8.27 X loJ kN . m2 (en la misma forma
como 0x)
445 fa =- = 58.5 MPa = 151~~1 = 0.51 > 0.15 ;a 7.61
real Pperm = AFa = 7.61(114.1) = 868.3 (vs, 860.6 interpolado
Usando la ecuación (7-130):
Fa 0x
P + CmxBxMx «; - s Pperm Fbx P(KLx)
114.1 132.8 445 + 0.95(8.94)(61)150 132.8 _ 8.27 = 865.3 \< 868.3 kN Correcta

<!-- p. 374 -->

374 DISEÑO DE VIGAS-COLUMNAS
445lkN
61 kNr m

E

53kN'm

kN Figura E7-6 t445

Verifíquese la ecuación (7-14a):
F F ~ \< p p--Q- + B M - perm 0.6r;, x x Fb
1 /' (445) = 753 \< 868.3 kN Correcta \1:01 + 8.94(61)1::0
El uso de las ecuaciones (7-13) y (7-14) daría:
865.3
868.3 = 0.997 \< 1.0
Ecuación (7-14):
753 = O867 \< 1.0 868.3 .
Usese como sección tentativa, W310 x 59.5.

Ejemplo 7-7 Se diseñará el miembro No. 6 de la cuerda superior de la arma-
dura usada en los ejemplos 6-4 y 6-5, para incluir el peso del miembro y una
fuerza concentrada temporal de 2.2 kips, la que se aplicará en el centro de la
cuerda durante las operaciones de mantenimiento (véase figura E7-7a). El
puente se puede cerrar temporalmente al tráfico si la carga de mantenimiento
resulta muy grande para ser soportada junto con el tráfico (carga viva).
Otros datos:

Carga muerta = - 283.75 kips
Carga viva = - 109.44 kips
P = - 393.19 kips

SOLUCION Como se usó un par de canales C15 x 40 en el ejemplo 6-4 para
una carga algo menor, se probará un par de canales C15 x 50 (figura E7-7b):

A = 14.70pulg' Iy = 11.00 pulg'
rx = 5.24 pulg x = 0.799 pulg S; = 53.80 pulg 3j canal

<!-- p. 375 -->

DISEÑO DE VIGAS-COLUMNAS USANDO LAS ECUACIONES DE INTERACCION 375
¡--'2"i 6 10

9 -fr~50
x ~--~----"
8

y

(al (b)

Figura E7·7a Figura E7-7b

Calcúlense los nuevos t, y ry:
Iy = 2(11.0) + 2(14.70)(6 - 0.799)2 = 817.3 pulg"

817.3 )1/2
\~ rx controla ry = ( 2(14.70) = 5.27 pulg > 5.24

KL = 25 x 12 = 56.9
r, 5.27

KL j r F;, [ ( )2] Fa = 2.12 1 - 0.5 -c:-

Fa = 2~~2 [ 1 - 0.5( = 15.25 kips/pulg- 152~~1f]
393.19 2 fa = 29.4 = 13.37 \< 15.25 pulg Correcta

Se usará la misma celosía del ejemplo 6-6, y no se volverá a diseñar.
Compruébese a continuación el peso de la columna usando las ecuaciones de
interacción.
\= W L2 = 2(0.05)(825)2(12) = 93.75 kíp/pulg'
Mcarga 8
I M 93.75 087 k' r. dial 1 ) Jb == Sx = 2(53.8) =. lps/pulg2 , con os cana es en par e o

Calcúlese F;' usando la ecuación (7-19):
'lT2E 'lT2(29 000) F" = = = 41.1 kips/pulg-
e 2.12(KLjrx )2 2.12(57.3)2
Usando la ecuación (7-17) con Cm = 1, puesto que el peso de la viga es
carga interior:

<!-- p. 376 -->

376 DISEÑO DE VIGAS-COLUMNAS

Calcúlese

Fb = 0.55;;'[ 1 - 0.5( = 20[ 1 - 0.5( 15~6~1 = 17.96 kips/pulg- K~rf] f]
13.37 1(0.87)
15 23 + ( _ 3 37/ )( ) = 0.878 + 0.071 = 0.949 \< 1 Correcta . 1 l. 41.1 17.96

Compruébese la interacción con la carga de mantenimiento añadida:

M¿ = PL = 2.2(25)(12) = 165 kips/pulg-
4 4
f b = 2(~~~8) = 1.53 kips/pulg-

13.37 1(0.87 + 1.53) = 0.878 + 0.198 = 1.08 > 1.0 N.S. 15.23 + 0.674(17.96) .

Compruébese si hay que cerrar el puente:

P 283.75 . fa = ; = 29.4 = 9.65 kips/pulg-
9.65 + 1(0.87 + 1.53) = 0.634 + 0.175 = 0.809 \< 1 Correcta
15.23 (1 - 9.65/41.1)(17.96)

Verifíquese ahora la ecuación (7-18). Si es adecuada para las cargas del
puente y se cierra el puente al tráfico, es correcta.
Para las cargas del puente:

fa +!a\<1
0.472;;' r;>
13.37 + 0.87 = 0.787 + 0.048 = 0.835 \< 1 Correcta
0.472(36) 17.96

Para el mantenimiento sin tráfico:

\~ 0.87 + 1.53 = O568 O134 = 0.702 \< 1 Correcta 16.992 + 17.96 ... +.

Usense dos canales de sección Cl5 x 50. Se cierra el puente para mante-
nimiento.

<!-- p. 377 -->

COLUMNAS ESCALONADAS Y COLUMNAS CON CARGA AXIAL INTERMEDIA 377

7-8 COLUMNAS ESCALONADAS Y COLUMNAS
CON CARGA AXIAL INTERMEDIA

Con frecuencia elanálisis de las columnas escalonadas sepresenta en eldiseño de edificios industriales, particularmente cuando las columnas soportan trabes de grúas
viajeras. Las condiciones generales de diseño se ilustran en la figura 7-12.

Las figuras 4-1a y lO-la muestran trabes carriles que están soportadas por
columnas armadas y escalonadas. El diseño está muy influenciado por las condiciones en los extremos de la columna. Se puede generalmente suponer que la base
de la columna está fija con respecto a los ejes X e Y. Si se toma ahora el eje X de
la columna principal, orientado para flexión en el plano del pórtico, y el eje Ypara flexión fuera del plano (con respecto a la longitud del edificio), se tienen las siguientes consideraciones:

Trabe o armadura de techo
1

Placas
de celosía

lal ( b) (e)

Figura 7·12 Columnas para grúas en un edificio industrial. (a) Columna con ménsula. (b) Columna
escalonada. (e) Columna escalonada, armada.

Eje X

l. Fija o articulada a nivel de la armadura de techo. La armadura de techo de los
pórticos industriales de los ejemplos 2-5 y 2-6, proveen empotramiento contra
la rotación (o casi), pero puede haber traslación.
\2. Control del pandeo lateral. Los cobertizos laterales de los ejemplos 2-5 y 2-6
además de cualquier contraventeo en el plano de los pórticos primero y últi-
mo, servirán para controlar el desplazamiento lateral. Si continuara siendo ex-
cesivo, puede que se requiera acartelamiento entre la columna y la armadura
de techo. "-
\3. Es probable que haya momentos en la columna a la altura de la armadura de
techo. Son posibles momentos al nivel de la trabe carril debido al empuje late-

<!-- p. 378 -->

378 DISEJIlODE VIGAS-COLUMNAS

ral del trole de la grúa contra los rieles que forman la vía. Habrá un momento
de la columna en la base, debido a la supuesta fijación de la misma. Estos mo-
mentos producen una interacción de viga-columnas, para la que se habrán de
usar las ecuaciones (7-13) y (7-14).

Eje Y

\1. Fija o empernada a nivel del techo. Si se pone algún contraventeo transversal
en el plano de la cuerda inferior de la armadura y contraventeo transversal ver-
tical en una o más de las crujías en los lados opuestos, se podrá controlar la
mayor parte del desplazamiento lateral.
\2. Contraventeo lateral intermedio. Es necesario a fin de reducir el KL/ry de la
columna principal y del segmento de columna por encima de la trabe carril. Se
pueden usar largueros de pared para soportar la cubierta lateral, y como so-
porte lateral. Es necesario, sin embargo, tener cuidado de que los largueros
sean continuos y que, en el caso de que reparaciones en el edificio, si se re-
quiere la remoción de un larguero de pared, se debe hacer en un claro cada
vez, de manera que no pierda el soporte lateral.
\3. Habrán momentos en las columnas al nivel de la grúa viajera, debido al empu-
je longitudinal producido por el arranque o parada súbitas de la grúa. Esto
producirá también un momento en la placa de base, aun cuando se efectúe el
análisis de manera tal que se ignore el momento a nivel de la grúa. Esta fuerza
producirá también un cortante en la columna, el cual tendrán que resistir los
pernos de anclaje de la base.

Se procederá de la manera siguiente para el diseño de una columnade este tipo:

\1. Como en los ejemplos 2-5 y 2-6, se analizará tentativamente la estructura, y se
revisará hasta obtener tamaños de los miembros y deflexiones. Se pueden usar
diferentes tamaños para los miembros. Esto no se hizo inicialmente en los dos
ejemplos, porque el trabajo es todavía muy preliminar.
\2. Basado en la salida de la computadora, se comienza a rediseñar los miembros.
Se aumentan o disminuyen las dimensiones, dependiendo de la fuerza y defle-
xiones.
\3. Se reprograma y se comprueba la salida por fuerzas y deflexiones.
\4. Se repite según sea necesario.

7-8.1 Modificación de K para columnas escalonadas
Una columna articulada, libre de pandearse y con una carga externa Poy una carga interior p I O ' como se ve en la figura 7-13, está en un estado de equilibrio inestable si las cargas son lo suficientemente grandes. Si se usa la ecuación diferencial
dx EI-= -Px
dy

<!-- p. 379 -->

COLUMNAS ESCALONADAS Y COLUMNAS CON CARGA AXIAL INTERMEDIA 379

/0

Pó

E = constante
L = Lo + LI

/1

t

Figura 7·13 Figura para la deducción del coeficiente de longitud efectiva para columna escalonada.

y se provee para las condiciones de frontera de las diferentes cartas en el segmento
inferior, que no hayan desplazamientos laterales en los extremos de la columna,
cambio de 1 en el segmento inferior y una pendiente común en la unión de los segmentos superior e inferior, se obtiene
__k_U_I/C-2cot[(~O)I/2(kL_ akL)] + kU \/2 cot[akL(1 + ~0)\/2]
(Poi PI) I (l + Poi PI) I
1 (7-22)
donde J = 1 + Poi PI - a
a= L1/(Lo + L\)
Esta es la solución que da Sandhu en, "Effective Length of Columns with Intermediate and Axial Load," AISC Engineering Journa/, octubre, 1972. El valor de
kL obtenido como solución de la ecuación (7-22) es como el que se usó en el
capítulo 6:
P )1/2
kL= ( -El
Reordenando se tiene

pero

<!-- p. 380 -->

380 DISEÑO DE VIGAS-COLUMNAS

e igualando esta carga a la carga de Euler, se obtiene

Resolviendo para el factor de longitud equivalente, K, se tiene que

Este valor de K, es para una columna con pasadores en los extremos, y es necesa-
rio multiplicarlo por el valor de K del Alse según se obtuvo de las figuras 7-5 ó
6-3, donde se tienen en cuenta las condiciones reales en los extremos. Para el uso
de diseño general en la oficina, se debe programar la ecuación (7-22) en una computadora, para poder hacer una gráfica de a' = PO/P I Oversus Ke> para diversos
valores del parámetro a.

Ejemplo 7-8 Hágase un diseño tentativo de la columna de la grúa en el edifi-
cio industrial del ejemplo 2-6. Refiérase a la figura E7-8a y supóngase lo si-
guiente:

120.6
Mr-:
\~...,_.. , 338.99 kN·m 1
11262.1l~
t (carga total "':
de la grúa) V) 1

313.6

E
V)-O

\~
M-eV)
l
\~
190.1 kN·m Figura E7-8a

<!-- p. 381 -->

COLUMNAS ESCALONADAS Y COLUMNAS CON CARGA AXIAL INTERMEDIA 381

l. Contraventeo adecuado con respecto al eje Y de la columna principal (a
lo largo de las crujías).
\2. Desplazamiento lateral en el plano del pórtico, sin rotación en el tope, y
con la base fija.
\3. Para el diseño tentativo inicial, úsense solamente las cargas vivas y muertas
de la salida de la computadora + cargas de la grúa.
\4. La trabe carril se colocará a nivel con la parte inferior de la armadura del
cobertizo lateral.
\5. Usese una sección escalonada (armada).

SOLUCION Se usó una sola viga W690 x 264.9 para obtener los resultados
preliminares que apareceri en el ejemplo 2-6. Es necesario este tamaño de sec-
ción (área y momento de inercia) para reducir a valores tolerables las defle-
xiones laterales a nivel del techo de la armadura principal y en la intersección
del cobertizo con la columna. La sección armada requerirá estos o mayores
valores, para proveer desplazamientos laterales satisfactorios. De la salida de
la computadora para Le = 1(y para la repetición de una sección tentativa
inicial armada), las cargas axiales y los momentos (para la columna de la iz-
quierda) son:

Miembro 26 (el más alto):
P = 318.24 kN momento = 120.59 kN.m
Miembro 25 (intermedio):
P = 387.11 kN momento 338.99 kN.m
Miembro 24 (sección inferior):
P = 543.01 kN momento = - 313.6 kN.m

Pruébese, de una manera algo arbitraria una sección compuesta de una co-
lumna principal W360 x 314, y una columna de grúa W360 x 101.2, como
se muestra en la figura E7-8b.

y

W360XIOl.2

\-;-t-----x

W360X314

Figura E7·8b

<!-- p. 382 -->

382 DISEÑO DE VIGAS-COLUMNAS

Datos de la W360 x 314:
t, = 1107.2 X 10- 6 m" Iy = 428.7 X 10-6 m"
401 mm A ... 40.0 X 10- 3 m2 d = 399 mm bJ =

Datos de la W360 x 101.2:

I; = 300.9 X 10-6 m" Iy = 50.4 X 10-6 m"
A ... 12.9 X 10- 3 m2 d = 357 mm = 255 mm bJ
Cálculese r, y ry- Usese I: M X1 = Opara situar el nuevo eje Y-Y.

(40 + 12.9)x = 910(12.90)
x = 91~~~~.9) = 221.9 mm (use 222 mm)

Iyy = 1107.2 + 50.4 + 4O(0.222)2(1\<P) + 12.9(0.688)2(1\<P)
\= 9235.09 x 10-6 m"
0.009235 )1/2
\~ 418 mm ry = ( 0.0529 = 0.418 m
I xx = 428.7 + 300.9 = 729.6 X 10-6 m"
0.0007296 )1/2
\~ 117 mm rx = ( 0.0529 = 0.117 m

Compruébese el esfuerzo permisible Fa' basado en Kl.rr, (ya que la otra di-
rección se considera estable por el uso adecuado de largueros de pared y el
forro). Usese la fuerza más grande en la columna superior, 387.11 kN.

a, = Po = 387.11 PI 543.01 - 387.11 + 1262.11 = 0.273
\+1~:~ + 7.3 = 0.565 a = 16.5

Al sustituir valores en la ecuación (7-22) se tiene que
J = 1 + 0.273 - 0.565 = 0.708
kL(0.708). cot[ \/0.273 kL(1 - a)]
\/0.273
\+ kL(0.708) cot[ (1 + 0.273)1/2(0.565kL)] = 2.877
(1 + 0.273)1/2
1.356kL cot(0.227kL) + 0.627kL cot(0.637kL) = 2.877

<!-- p. 383 -->

COLUMNAS ESCALONADAS Y COLUMNAS CON CARGA AXIAL INTERMEDIA 383

Fijándose que el término que se ha de evaluar como cotangente se ha de expre-
sar en radianes, se puede programar rápidamente el problema en una calcula-
dora programable de bolsillo, y obtener kL = 3.525.

(kL)2 = 3.5252 = 12.426
PI = 543.01 + 1262.11 = 1805.1 kN (actual)
P = 12.426(1 + a')EI = 15.82EI
1 L2 L 2
Además,
15.82EI 7T2EI
\= 2 L (KeL )2
s, = ( 1;~2) 1/2 = 0.790
Valor real deK = K, x Kcond.extremos- Obténgasede la figura 6-3c, Kcond.extr = 1.2.
K = 0.79(1.2) = 0.95
KL = 0.95(16.5) = 375
ry 0.418 .
Se obtiene de la tabla VI-5 Fa = 134.6 Mpa. De la tabla VI-7, se obtiene F;
\= 732.8 Mpa. Compruébese la ecuación de interacción [ecuación (7-13)].
fa = = 1~~~/ = 34.12 MPa :1
. 34.12 relación = 134.6 = 0.25 > 0.15

Se usará Cmx = 0.85 (No se hará comprobación alguna para la flexión con
respecto al eje X en este momento, porque los cálculos son preliminares.
Después de la siguiente corrida de la computadora, si esta sección sigue sien-
do satisfactoria, se verificará la flexión con respecto a ambos ejes.)
k = Me = 313.6(0.816) = 27.7 MPa (nótese el cambio del punto decimal
1 9.235 en n
Supóngase que Fb = 0.6Fyo [Se tendrá que calcularlo mas tarde, usándose co-
mo ecuaciones apropiadas las ecuaciones 1.5-6 y 1.5-7 (numeración del
AISC).]

fa Cmfi, ( 1 ) \<
F: - 1 Fa + Ji; 1 - fa/

27.7 ) ( 1 ) 0.25 + 0.85 ( 150 1 _ 34/733 = 0.25 + 0.16 = 0.41 « 1.0

<!-- p. 384 -->

384 DISEÑO DE VIGAS-COLUMNAS

Por inspección, se satisfará la ecuación (7-14) para el segmento inferior de la
columna.
Se debe verificar el segmento superior de la columna para interacción
para asegurarse que la W360 x 314 es adecuada como columna para la altu-
ra total del pórtico.
Ahora se puede reprogramar este ejemplo con las nuevas secciones de
columna y cualesquiera secciones revisadas para los miembros de la armadu-
ra y ver si las defiexiones laterales para las diversas condiciones de carga son
satisfactorias y que los momentos fiectores y las fuerzas axiales son compa-
tibles con la sección que se analiza. Esto se debe hacer antes de refinar el di-
seño final, para mantener a un mínimo los cálculos de ingeniería y usar al
máximo la computadora.

7-9 CONTROL DEL DESPLAZAMIENTO LATERAL

Es evidente que el diseño más eficiente de la columna resultará cuando el
marco tiene adecuados contravientos contra el desplazamiento lateral. Sin
desplazamiento lateral:

l. Cm puede ser menor que 0.85 (pero puede ser mayor en casos especiales).
\2. El factor de longitud efectiva, K, no es mayor de 1.0.

Una estructura de marco rígido se puede trasladar lateralmente la cantidad
suficiente para sufrir "desplazamiento lateral". Nótese también que la deducción
de las ecuaciones para los factores G se basa en una pendiente común en la junta,
lo que sólo se puede obtener con una junta "rígida". Es por consiguiente necesario proveer resistencia específica contra el desplazamiento lateral para obtener las
columnas más eficientes. Esto se puede obtener por medio de (véase la figura
7-14):

la) lb)
Figura 7-14 Control del desplazamiento lateral. a) Muro de cortante de mamposteria. b) Contraventeo diagonal en crujías seleccionadas.

<!-- p. 385 -->

CONTROL DEL DESPLAZAMIENTO LATERAL 385

l. Muros de cortante (úsense muros rígidos verticales de ladrillo, o bloques de
concreto para detener el movimiento lateral). Si se usan muros de mamposte-
ría, se debe proveer un estrecho contacto con la columna, de modo que la co-
lumna no pueda desplazarse en el vacío de construcción entre los materiales.
\2. Contravientos diagonales (producen esencialmente una armadura orientada
verticalmente) en una o más crujías.

Puede que no sea necesario usar juntas rígidas con muros de cortante o
contravientos diagonales. Sin embargo, se puede obtener alguna economía de
materiales por medio del uso de juntas rígidas así como incrementar el margen
contra incertidumbres.
Los requisitos para los contraventeos laterales son generalmente de poca
monta. Los criterios de control pueden ser las relaciones L/r más bien que los requisitos de área de la sección. Balambos ("Lateral Support for Tier Building Frames", AISC Engineering Journal, enero, 1964), usando esencialmente el mismo
método propuesto por Winter para el contraventeo lateral de columnas y vigas,
desarrolla una expresión para el área del miembro de contraventeo diagonal:

(7-23)

donde Ah = área del contraviento, pulg- o m2
P = suma de todas las cargas de columna al nivel de un piso en el pla-
no de contraventeo
ex = longitud horizontal de contraviento diagonal/longitud de la columna

E = módulo de elasticidad, suponiendo que la columna y el contraviento
son del mismo material, kip/pulg- o MPa

Por lo general, el contraviento diagonal se diseña solamente para tensión. Se supone que el miembro de contraviento es tan pequeño y flexible que se pandeará
bajo una muy pequeña carga de compresión (con el esfuerzo muy por debajo de
F). Para la carga en dirección opuesta, el miembro pandeado se endereza sin
sufrir daños debido a los pequeños esfuerzos de pandeo e impide que ocurra el
desplazamiento lateral al soportar la carga necesaria a tensión.

400 378
\~ kN¡ () I 4\<Jü¡ 4 .-'7 623¡ 685 m
1', /
\ /
\-c / / oC , .... 7- / /' \
/ \
/ \
FiguraE7-9

<!-- p. 386 -->

386 DISEÑO DE VIGAS-COLUMNAS

Ejemplo 7-9 Dado un pISO de un edificio de múltiples claros que se muestra
en la figura E7-9, diséñense los contravientos diagonales del claro interior.
Supóngase que estos contravientos se colocarán en pórticos alternos en la di-
rección fuera del plano.

SOLUCION
Lb = 4.27 m Le = 3.66 m
4.27
a = 3.66 = 1.167

Úsese la ecuación (7-23):
A = 2(1 + 1.1672 )1.5 ~(400 + 490 + 623 + 378) = 0.0504 x 10-3 m2
b 1.1672(200 000)

El contraviento diagonal tiene una longitud de

El Llr máximo para un miembro a tensión es 300.

\= 5.62 x 1000 = 187 r mín 300 . mm

Selecciónese arbitrariamente un perfil de canal para el contraviento. Selecciónese
de la tabla V-7 una MC150 x 22.47:

ry = 22.6 mm (no hay C típico con valor adecuado de ry y un peso ra-
zonable)
A = 2.86 X 10- 3 m2 » 0.0504 requerida

No hay sección de canal que sea más ligera y que esté controlada por r.. / / /

7-10 DISEÑO DE VIGAS-COLUMNAS USANDO EL DFRC

El diseño de vigas-columnas usando el DFRC requiere tener las componentes separadas de los efectos de la carga. La forma usual de interacción de las
ecuaciones que se han propuesto para determinar esta función por el grupo de investigadores que se ocupan de este procedimiento de diseño son como sigue:

(7-24)

<!-- p. 387 -->

DISEÑO DE VIGAS-COLUMNAS USANDO EL DFRC 387

M dx y _u_+_u_+_u_\<r: «: 10 (7-25)
\- • $Py $Mpx $Mpy

$Mp ~ Mud (7-26)
además, siempre hay que satisfacer los siguientes:
Pud S $cPu (7-27)
Cuando hay flexión con respecto a un solo eje se tiene:
Pud «: S 1.0 (con respecto al eje X) (7-28) -+ sr, 1.18$Mp

udy \<10 (con respecto al eje Y) (7-29)y (P~ + M - • $pu r 1.19$Mp
En estas ecuaciones rf> = 0.86 (para vigas), y rf> e = valor dado en la tabla 3-1 para
columnas y teniendo en cuenta que rf> e varía desde 0.65 a 0.86, dependiendo de
KL/r. Los términos de Cm son como en el AISC. Los valores de P; son
P; = Ar;,(I - 0.251]2) 1] S v'2 (7-30)
Af'.y ,,", P =- 1]>v2 (7-31) u 1]2

AFy PE = -- (pero se usará el eje de flexión apropiado) (7-32) 1]2

Las fuerzas de diseño y los momentos son como los calculados en loscapítulos 6y4.
El uso de estas ecuaciones de DFRC se ilustra con el siguiente ejemplo:

Ejemplo 7-10 Dada la viga-columna y la carga de la figura E7-1O, selecciónese el
perfil W310 más ligero, usando F; = 250 MPa y el DFRC.
ID =400 kN
\~ L =600
tí""'\ MIJ = 120 k:\'m
ML = 180

\~ K,> 1.2
:' K y = \.0

Figura E7-10

<!-- p. 388 -->

388 DISEÑO DE VIGAS-COLUMNAS

SOLUCION Usese F L = 1.5 (elegido por el autor).
M ud = 1.1[1.1(120) + 1.5(180)] = 442.2 kN . m
Pud = 1.1[1.1(400) + 1.5(600)] = 1474kN

Con flexión solamente con respecto al eje X, se aplica la ecuación (7-28), de ma-
nera que

La inspección de esta ecuación indica que
1.18epMp > Mud
442 -3 2 1.180.86( ) ZFy > 442 Z > 1.18(0.86)(250) = 1.7422 X 10 m
AFy > r:
1474 3 3
A > 0.86(250) > 6.86 X 10- m

Usando estos valores de A y Z, pruébese una sección W310 x 157.7:
A = 20.13 X lO-3 m2
ry = 79.0 mm rx = 138.9 ry rige
Z; = 2.687 X 10-3 m3
TI = KL (F / E)I/2 = 1(3750) (250/200 000)1/2
str y str
42.2 4 O 6 TI = - = 0.53 > .1 ry

de los cuales

epc = 0.90 - 0.25(0.534) = 0.77
Pu = AFy[t - 0.25(0.534)2] = 20.13(250)(0.9287) = 4674 kN
Mp = ZFy = 2.687(250) = 672 kN . m

Sustituyendo valores en la ecuación (7-28) se obtiene

1474 + 442 = 0.367 + 0.648 = 1.015 > 1.0 N.S.
0.86(4674) 1.18(0.86)(672)

<!-- p. 389 -->

PROBLEMAS 389

Comprobación

cl>cPu 2: Pud
Correcta 0.77(4674) = 3599» 1474

Como esta columna se pasa ligeramente, la siguiente sección mayor de W31O, debe servir. Tabulando los datos para poder comparar, se obtiene
W310 X 178.6: A = 22.77 X 10-3 mi
ry = 79.5 mm (que rige como antes)
Z; = 3.055 X 10-3 m3
Es evidente, de la inspección de estos datos que la sección es adecuada. No es necesario verificar que Pnd~ 4>ePu ya que esta relación es casi la misma que se obtiene del primer término de la ecuación (7-28). Se usará una sección W310 x
178.6.

PROBLEMAS

7-1 Usando la solución general para el pandeo de columnas,
x "" A sen ley + B cos ley + Cy + D y k =y-J;
demuéstrese que K = 0.7 para la columna de la figura 6-3b. Nótense las condiciones de frontera:
x=Oparay=O v r r t-
dx M = O paray - O dy = Oparar = L

7.2 Determínense los coeficientes K de longitud efectiva para las columnas del marco de la figura P7-2.
Nótese que el extremo más lejano de la trabe de la columna FH está articulado.
Respuesta: AB: 1.75; FG: 0.78

W27XI14
E H .-----el G
N) 11'24 x 62 D \<ro • V)N) 11'27 X 84
xr-~ B x ~I
\-~¡ x ~, ~I i i

FJi A e
/--35' ~Ir 40' ~v 30,---1

Figura P7-2

7-3 Determinense los coeficientesK de longitud efectiva para las columnas del marco de la figura P7-3.
Respuesta: BC = 0.65; EF = 0.63

<!-- p. 390 -->

390 DISEÑO DE VIGAS-COLUMNAS

11'540 X 150.3
D E 7.1 m t E
or.
r-.
\<')

11'610 X 101.~ 11'610 X 154.8 F W610XI~5.0
A H
5.4 m e 7.65 m 5.5 m

E
V)

D
B Figura P7-3 rl.,:1

7-4 Selecciónese la sección de columna más ligera para la carga y geometría de columna de la figura
P7-4. Usense las especificaciones del AISC y acero A-36. No se use ninguna columna mayor que el peralte nominal de las secciones W12. Tómese K, = Ky = 1.0
240!k~
60 pies/kips

;,. Sin desplazamiento
lateral para Cm

80 pies/kips
\jJ

Figura P7-4 t
7-5 Selecciónese la sección de columna más ligera para la columna que aparece en la figura P7-5,
cuidando de no usar ninguna sección de columna mayor de la W31O. Tómese K, = 1.2, K; = 0.8.
Usense las especificaciones del AISC y Fy = 250 MPa.
Respuesta: W310 x 142.9

200 kN ti

140kN'm""
\~. Con desplazamiento lateral para Cm

.".

\J./160

Figura P7·S t

<!-- p. 391 -->

DISEÑO DE VIGAS-COLUMNAS USANDO EL DFRC 391

7-6 Dado el marco de la figura P7-6, úsese el programa de computadora para obtener las tuerzas axiales
y los momentos. Verifiquese que las columnas y vigas sean adecuadas y reprográmese siserequiere, para
obtener vigas y columnas razonablemente ligeras. Limítese la deflexión a la mitad del claro a L/360. No
se considere carga alguna de viento. Usense las especificaciones del AISC, acero A-36, y Kv = 1.0.
2.6 kips/ft

WI8 X 50
rl
\-r,~. 3.9 kips/pie "'. x V)x
W21 x 62 "" "":: -
;;.

\-L.L- ......L",-
1- 30' " Figura P7·6
7-7 Dado el marco de la figura P7-7, úsese el programa de computadora y, para las secciones tentativas dadas. obténganse las fuerzas axiales y momentos. Compruébese lo adecuado de las secciones y
reprográmese hasta obtener vigas y columnas razonablemente ligeras. Limitese la deflexión de la viga
de techo a L/360 en la mitad del claro, y la deflexión lateral en D a no más de 0.040 m. Usense las especificaciones del AISC y acero con F; = 250 MPa.
28 kN/m

/:' F

28 kN/m
E D V)
\~lo

e G
9.5 m 14.6 m -1 Figura P7-7
7·8 Diséñese la columna más ligera (úsese una sección armada con perfiles laminados W, corrientes,
si se requiriera) para la carga y geometría que se muestra en la figura P7-S. Usese Fy = 345 MPa (o
más alto si se requiriera) y las especificaciones del AISC. Tómese K¿ = 1.2 YKy = 1.0.
Respuesta: Usense tres W920 x 446.4 con dos cubreplacas de 1969 x 40 mm.

500 kN !37
rt\ 7200 k Nr rn

Figura P7·8

<!-- p. 392 -->

392 DISEÑO DE VIGAS-COLUMNAS

7-9 Diséñese la cuerda superior de una armadura de ferrocarril con una longitud de panel de 27.583
pies para las condiciones siguientes:

Carga viva = 867.2 kips (Carga E-80)
Impacto = 473.6 kips
Carga muerta = 402 kips (estimada)

Usese una sección armada parecida a la que se muestra en la figura P7-9. Usense las especificaciones del AREA y acero A-36. Los extremos de la cuerda pueden ser remachados o atornillados.
Respuesta: Dos perfiles S24 x 100 y uno S24 x 79.9 con una cubreplaca de 30 x Y2.

Parte superior-.L f--- L'S 30"----1
T 1"
"2
Perfil S

Cubreplaca
perforada Figura P7-9

7-10 Compruébese la sección de la columna por encima de la trabe carril del ejemplo 7-8, y rediseñese
si fuera necesario.
7-11 Usando el ejemplo 7-8 como guía, hágase un rediseño tentativo de la columna principal del
ejemplo 2-5. Usese acero A-36 y las especificaciones del AISC.
7-12 Repítase el ejemplo 7-2 con el tamaño de la columna limitado a W12.
Respuesta: W12 x 96.
7-13 Diséñese el contraventeo diagonal para el pórtico de la figura E7-3, para inhibir el desplazamiento lateral. Usese el par de angulares más ligeros, con una placa de conexión de 12 mm.
Respuesta: Dos L63 x 51 x 4.8.
7-14 Compruébense las columnas exteriores del ejemplo 2-3, usando la salida de la computadora y dimensiónense de nuevo las columnas, si fuera necesario. Nótese que ambas columnas exteriores tienen
el mismo tamaño. Se usará una sola columna (sin empalmes) para toda la altura del edificio. Usese
acero A-36 y las especificaciones del AISC.
7-15 Compruébense las columnas interiores del ejemplo 2-3, usando la salida de la computadora y dimensiónense de nuevo las columnas, si fuera necesario. Nótese que las columnas del sótano no tienen
necesariamente el mismo tamaño de la columna superior, la que se ha de usar en toda la altura del edificio. Usese acero A-36, las especificaciones del AISC, y columnas no mayores de WIO.
Respuesta: Inferior, W8 x 48; superior, W8 x 40.
7-16 Usese la salida de la computadora del ejemplo 2-4, para las columnas exteriores descritas en el
problema 7-14. Limítese el tamaño de la columna a W250.
Respuesta: W250 x 67.0.
7-17 Usese la salida de la computadora del ejemplo 2-4 para las columnas interiores, descritas en el
problema 7-15. Limítese el tamaño de la columna a W250.
7-18 Verifíquese, con cálculos que la sección W310 x 178.6 de la columna del ejemplo 7-10, es adecuada.
7.19 Repítase el ejemplo 7-10 si M L = 210 kN.m, y D = 425 kN. Todos los otros datos son los mismos.
Respuesta: W310 x 178.6.
7·20 Repítase el ejemplo 7·10, si momentos My están presentes: M dy = 50 kN.m; M Ly = 75 kN.m.
Respuesta: W310 x 282.8.

<!-- p. 393 -->



<!-- p. 394 -->

(h) (e)

Figura VDI·} Juntas a tornillos de alta resistencia. a) Empalme de una columna menor a una mayor,
usando placas de relleno. b) Empalme de columnas del mismo tamaño. e) Arriostramiento diagonal.

<!-- p. 395 -->

CAPITULO
OCHO
CONEXIONES ATORNILLADAS Y REMACHADAS

8-1 INTRODUCCION

'luna estructura de acero se forma del ensamblaje de los miembros estructurales
que constituyen su armazón. Se requieren conexiones en los lugares donde los di-
versos miembros se deben unir por sus extremos a otros miembros de manera que
permitan que la carga siga su flujo ordenado y continuo hasta llegar a los cimien-
tos. Como la conexión sirve para pasar la carga de o a los miembros adyacentes,
se debe diseñar de manera adecuada. El diseño de las conexiones implica la pro-
ducción de una junta que sea segura, económica en el uso de los materiales, y que
se pueda construir (ha de ser práctica). En general, las conexiones más prácticas
son las más económicas, ya que los costos de fabricación afectan la economía tan-
to de las conexiones (o juntas) como los propios miembros, como ya se mostró es-
pecialmente en lo que concierne a los miembros armados a tensión y compresión.
En la figura 8-1, se presentan diversas conexiones estructurales.
/Las conexiones (o juntas estructurales) se pueden clasificar según:

\1. El método de sujeción, como son los remaches (casi nunca), tornillos, o solda-
dura. Las conexiones que usan tornillos se clasifican además como conexiones
del tipo de aplastamiento o del tipo de fricción.
\2. La rigidez de la conexión, que puede ser simple, rígida (según se obtiene por
un análisis estructural indeterminado), o de rigidez intermedia. El AISC, en la
sección 1.2 de las especificaciones, clasifica las juntas basadas en la rigidez de
la conexión como:
Tipo 1: conexiones rígidas que desarrollan la capacidad total de momento de
los miembros que se conectan y que mantienen un ángulo relativo constante
entre las partes conectadas, bajo cualquier rotación de la junta.

395

<!-- p. 396 -->

396 CONEXIONES ATORNILLADAS Y REMACHADAS

p

11
(a) + '1 + 11
\+ '1 +
\+ 11 +
\+ 111
'1
11
iI

i d ¡

1 I I I I I 1 I

11
\+ + + + ""11 ++++ Placas
\+ + + + "" ++++ ~ del alma I I I I
""11 ) I I 1 I

(e) ~
p
(e)
Figar_A.r· Conexiones estructurales varias que usan tornillos (o remaches). (o) Junta trasladada, cor-
tante sencillo. (b) Junta a tope, doble cortante. (e) Empalme en 1na viga de puente. Las placas del
patin a cortante sencillo; placas del alma a cortante doble, si están en ambos lados. (d) Conexión de
ménsula a cortante sencillo, pero donde se ha de considerar la torsión. (e) Sección T, usada como un
colgante a tensión.
Tipo 2: estructuración simple sin transferencia de momentos entre las partes
conectadas. En realidad, se desarrollará una pequeña cantidad de momento,
pero no se le tiene en cuenta en el diseño. Se desprecia toda excentricidad que
sea menor de unas 2 f pulg. (63 mm).
Tipo 3: conexiones semirrígidas donde se transfiere menos de la capacidad to-
tal de momento de los miembros conectados. El diseño de estas conexiones re-
quiere la suposición (con justificación adecuada) de una cantidad arbitraria de
capacidad de momento (por ejemplo, 20, 30, o 75 por ciento de la capacidad
del miembro).
\3. E tipo de fuerzas transferidas a través de la conexión estructural:
a Fuerzas cortantes: corrientes para vigas de piso y viguetas.
b. Momento: ya sea a flexión o torsión.
c. Cortante y momento: como en las conexiones del tipo 1 ó 3.
d. Tensión o compresión; como para los empalmes de columnas y para
miembros "articulados" de las armaduras.
e. Tensión o compresión con cortante: como para el contraventeo transdiago-
nal.
\4. La geometría de la conexión:
a. Conectores a base de angulares que se usan para unir las viguetas de piso y
los largueros a las vigas y columnas.

<!-- p. 397 -->

INTRODUCCION 397

\~~lE======
\+ Localizacíón
\+ +
\+ + opcional + +~ ~ 1I11
\~ ~ ~

(a) ib I (e)

\-l Angular
\+ 1 opcional en (
\+1 _..J el alma)
Atiesador
de asiento

'-----
(f).t~d) ~ (e)
Diversas conexiones para marcos. Al inspeccionar la manera corno se soporta la carga seti;uA.ii
determina si los tornillos están a cortante o a tensión. Usualmente la soldadura en lugar de los tornillos en todas las conexiones anteriores, excepto (j). (o) Conexión usando un par de angulares. (b)
Conexión que usa una placa terminal soldada en el taller y tornillos colocados en el campo. (e) Usando
un angular de asiento y un angular de tope, o lateral. (ti) Angular atiesado de asiento. (e) Angulares de
asiento y auxiliares de tope, con un angular adicional opcional en el alma. (j) Conexión rígida o
semirrígida que usan perfiles T para soportar el momento, y un angular en el alma para el cortante. Este último angular es opcional.
b. Conexiones soldadas que usan placas y angulares.
c. Placas terminales en vigas o alfardas.
d. Placas o angulares usados a un lado de una vigueta de piso o viga.
e. Angulares de asiento con o sin atiesadores.
Varias de estas conexiones se muestran en la figura 8-2.
\5. El sitio donde se fabrican:
a. Conexiones de taller; hechas en el taller de fabricación.
b. Conexiones de campo: las partes de la junta se fabrican en el taller, pero se
arman en el sitio de la obra.
\6. La resistencia de la junta. Cuando se considera la resistencia de la junta (o co-
nexión), se tiene:
a. Conexiones de fricción. En las conexiones que se diseñan como conexiones
de fricción se supone que su resistencia primaria se desarrolla como cortante
en los conectores (tornillos o remaches) en el plano potencial de desliza-
miento entre las partes conectadas. No se desarrollará ningún movimiento
relativo entre las partes conectadas hasta que no se exceda sustancialmente
la carga de diseño.

<!-- p. 398 -->

398 CONEXIONES ATORNILLADAS y REMACHADAS

\-tL-_-~~"-------,....l

(al

\~ (b) P ~
(el
(Y'

p

(el P
Figura 8·3 Varias maneras de presentarse la resistencia en las juntas. (o) Cortante en el tornillo. (b)
Cortante en la placa o rasgadura. (e) Aplastamiento del tornillo. (ti) Aplastamiento en la placa. (e)
Falla a tensión del tornillo. (j) Tensión sobre la tensión neta.
En realidad, la resistencia de las conexiones de fricción no se desarrollan co-
mo resistencia a cortante de los conectores; se desarrolla, más bien, como el
producto de la fuerza de sujeción producida al apretar los tornillos (o en la
instalación de los remaches) y el coeficiente de fricción entre las partes suje-
tas. Es deseable que esto se use, en el diseño por factor de resistencia de car-
ga, de una manera directa como parámetro de diseño, lo que producirá una
ecuación de la forma general usada en varios otros códigos de diseño (fuera
de los E.U.A.) como

P = q,p.}:AbF;.
donde cf> = factor de rendimiento (0.67 a 0.70)
p. = coeficiente de fricción x número de superficies de deslizamiento
I:AoFy = Fuerza total de agarre, expresada como la suma de todos los tornillos
usados en la conexión

<!-- p. 399 -->

REMACHES Y CONEXIONES REMACHADAS 399

b. Conexiones de aplastamiento. Conexiones donde la resistencia de la junta
se toma como una combinación de la resistencia a cortante del conector y el
aplastamiento del material conectado contra el conector. Este tipo de com-
portamiento se desarrolla según ocurre suficiente deslizamiento para poner
material conectado con la proyección trasera del conector, cerca de la carga
de trabajo o diseño, Como el cortante del conector es parte de la resistencia
en el análisis de la conexión de aplastamiento, el área reducida para cortan-
te de que se dispone para los conectores roscados cuando la rosca esté en
cualquiera de los planos de deslizamiento requiere una reducción de la car-
ga de diseño, En la práctica, la presencia de la rosca en el plano de cortan-
te dará por resultado un esfuerzo permisible de diseño más bajo, para el
cortante en el sujetador.

El diseño de las conexiones tanto de fricción como de aplastamiento implica
el uso de un esfuerzo cortante permisible. Este valor es mucho más bajo para las
conexiones de fricción, puesto que no es deseable ningún deslizamiento de la junta bajo las cargas de trabajo. El valor será considerablemente mayor para las
conexiones de aplastamiento, ya que se puede tolerar una pequeña cantidad de
movimiento relativo entre las partes que forman la junta. Ambos tipos de juntas,
además de diseñarse para "cortante", se verifican por rutina para tensión en la
sección neta y para aplastamiento del material conectado contra el conector.
La práctica usual de fabricación prefiere usar agujeros ovalados de mayor
tamaño en las conexiones de fricción. Este tipo de agujeros permite un montaje
más fácil en el campo, ya que se dispone de mayor tolerancia en la alineación para
los tornillos temporales de montaje.

8-2 REMACHES Y CONEXIONES REMACHADAS

Durante muchos años, los remaches eran el único medio práctico de producir conexiones metálicas fáciles y prácticas. El proceso requería punzonar o barrenar
agujeros con una sobremedida de aproximadamente 1/16 pulg. (1.5 mm), se armaban las partes usando pasadores para alinear los agujeros, y usando uno o más
tornillos para mantener juntas las partes temporalmente. Los remaches se calentaban en un fogón (portátil para usarla en el lugar) hasta el rojo cereza (aproximadamente 9800 C) y se insertaban en el agujero alineado a través de las varias
partes que había que conectar. Un miembro de la cuadrilla de remachadores aplicaba entonces una butrola con un dado de cabeza a la cabeza manufacturada del
remache para mantener el remache en su lugar y mantener la forma. Otro
miembro de la cuadrilla usaba una pistola neumática con un dado de cabeza para
forjar la parte proyectante de la espiga del remache y producir la otra cabeza. La
operación de forja simultáneamente reelaboraba el metal y producía un aumento
de la espiga hasta llenar casi completamente el agujero a sobremedida. Esta reelaboración y aumento en la espiga, junto con la contracción del remache caliente,
producía la mayor parte de las veces una junta sustancial. La contracción del re-

<!-- p. 400 -->

400 CONEXIONES ATORNILLADAS Y REMACHADAS

mache durante el enfriamiento es resistida por el material de la junta, y desarrolla
tensión en el remache, de manera que una junta remachada ocupa una posición
intermedia entre una conexión a fricción y una de aplastamiento (usualmente se
supone una conexión del tipo de aplastamiento). Esta junta transmite la carga de
diseño, principalmente por fricción entre las placas engrapadas que forman la
junta. Durante mucho tiempo, las juntas remachadas han tenido éxito bajo esfuerzos de fatiga en los puentes de ferrocarril. Sólo recientemente ha permitido el
AREA el uso de tornillos de alta resistencia y de soldaduras en las juntas de los
puentes de ferrocarril.
La combinación de ajustar bien el remache más la contracción adicional que
trata de efectuar conforme se enfría, produce esfuerzos de tensión los que en remaches bien colocados se acercan al Fy del metal del remache. Sin embargo,
ocurren algunos problemas, los cuales incluyen el del sobrecalentamiento ocasional de los remaches, que tiene un efecto deletéreo en la resistencia. Si se enfría
un remache muy por debajo de 540°C antes de que se complete la instalación, el
metal no es tan resistente, puesto que el forjado es más bien un proceso de "formado en frío", y la elaboración en frío tiende a hacer frágil el metal. Si el remache no se aprieta bien al colocarlo, quedará flojo después de frío, y se puede
detectar esto golpeándolo con un martillo. Un remache flojo no se puede volver a
remachar para que quede apretado y es preciso extraerlo manualmente (cortarle
la cabeza). La extracción de un remache es un trabajo lento y se requiere una
cuidadosa inspección para asegurarse que la cuadrilla de remachadores no remate
el borde de la cabeza del remache con un cincel y martillo para que parezca que
está apretado cuando el inspector lo golpee con su martillo.
Una cuadrilla de remachadores requiere cuando menos cuatro personas
(herreros), consistentes de uno que calienta y tira los remaches a los que los colocan; uno que recibe el remache caliente en un cubo y lo inserta en el agujero; uno
para manejar la butrola, y uno para remacharlo con un martillo neumático.
Es posible, con martillos neumáticos, colocar remaches en frío (trabajados
en frío), pero si no se tiene un cuidado especial, los remaches no quedarán muy
apretados y no existe, ningún efecto posterior de enfriamiento para efectuar una
contracción final del largo para juntar firmemente las diversas partes. En operaciones tales como la fabricación de aviones, y de los mangos de los cuchillos, los
remaches se colocan corrientemente en frío. En muchos talleres de fabricación se
pueden colocar los remaches en frío, pero se usan grandes prensas hidráulicas en
el proceso de remachado. De hecho, con las grandes presiones que se desarrollan,
se deforman las partes conectadas y, con la remoción de la presión tienden a recobrar su forma y desarrollan esfuerzos de tensión en los remaches formados en
frío.
En la actualidad, y por varias razones, no se usa el remachado en las estructuras de ingenieria, ni en los talleres de fabricación, ni en el campo:
\1. Los costos de mano de obra asociados con las grandes cuadrillas de remacha-
dores.
\2. La cuidadosa inspección que se requiere en las juntas remachadas y los consi-
derables costos para extraer remaches mal colocados.

<!-- p. 401 -->

REMACHES Y CONEXIONES REMACHADAS 401

\3. El desarrollo y la alta confiabilidad de los tornillos de alta resistencia.
\4. El desarrollo y la alta confiabilidad de la soldadura.
\5. El alto nivel de ruido asociado con el remachado, el que sería inaceptable, en
las presentes normas ambientales, en la mayoría de las áreas urbanas; ;
Entre los últimos tipos de construcción remachada que aún existen está la de
los puentes de ferrocarril, ya que los remaches tenían más alta resistencia a la fatiga que los tornillos primitivos. El proceso de forjado tendía a llenar los agujeros
de los remaches y, unido con los altos esfuerzos de tensión, producían un alto nivel de confiabilidad, comparada con la de los remaches primitivos (similares a los
del grado corriente A-30? que se considerará más adelante), que no podían desarrollar altos esfuerzos de tensión; además, las tuercas tenían la tendencia de
aflojarse bajo las cargas dinámicas continuas. La fabricación con remaches en el
taller continuó por algún tiempo después de que se descontinuó en favor de los
tornillos o soldadura de alta resistencia. Al presente, sin embargo, la soldadura

Tabla 8-1 Esfuerzos permisibles de tornillos y remaches en la construcción
de edlñcíoss

Esfuerzo cortante, F;
Esfuerzo de tensión,
F¡ Conexión de fricción> Conexión de aplasta miento
Material kips/pulg 2 Kips/pulg- Kips/pulg-

Remaches
A-502, grado 1 23 160 - - 17.5 120
grado 2 29 200 - - 22 150

A-307 (sin tornear) 20 138 - - 10 70

A-325N" 44 305 17.5 120 22 150
A-325Xd 44 305 17.5 120 30 205

A-449N 0.33Fu 0.33Fu - - 0.17Fu 0.17Fu
A-449X 0.33Fu 0.33Fu - - 0.22Fu 0.22Fu

A-490N 54 370 22 150 28 193
A-490X 54 370 22 150 40 275

a Todos los esfuerzos de esta tabla se han de usar con la sección del tornillo basada en el diámetro
nominal del sujetador.
b Véase el Manual para la Construcción de Acero del AISC, para los esfuerzos de la conexión
usando agujeros ranurados (ovalados).
en el taller y los tornillos han desplazado casi en su totalidad el uso de remaches,
especialmente con el advenimiento de los métodos automáticos y semiautomáticos de soldadura.
Se notará, específicamente, al referirse a tablas tales como la 8-1, que el es-
fuerzo cortante permisible del remache, en conexiones del tipo de aplastamiento

<!-- p. 402 -->

402 CONEXIONES ATORNILLADAS y REMACHADAS

(a)

(b)
Figura 8-4 (a) Diversos tamaños de remaches estructurales, antes de colocarlos. (b) Remaches en aplicaciones estructurales.

<!-- p. 403 -->

TORNILLOS DE ALTA RESISTENCIA 403

es el mismo que el permitido para los tornillos de alta resistencia A-325 y A-490,
en las conexiones de fricción donde la rosca de los tornillos se pueden o no incluir
en los planos de cortante. Por tanto, se puede sustituir un tornillo de alta resistencia en lugar de un remache del mismo diámetro en igualdad de condiciones. Los
requisitos de mano de obra para la instalación de los tornillos, es cuando más de
dos personas.
'Corno los remaches ya no se usan (cuando menos en Norteamérica), el resto
de este capítulo se centrará en las conexiones atornilladas, pero el lector debe es-

Resistencia última, Fu, kips/pulg- (MPa)
112 a I pulg. de I 1/8 a I 1/2 de I 9/16 a 3 pulg. de Tornillo diámetro diámetro diámetro.
A·325 120(825) 105(725)
\-1:. A-449 120(825) 105(725) 90(620)
A-49O ISO (1035) ISO (1035)

e N, roscas incluidas en el plano de cortante (se puede despreciar el alcance de la rosca).
d X, roscas excluidas del plano de cortante.

tar consciente de que el procedimiento de diseño de una conexión remachada es
exactamente el mismo que el de una conexión atornillada. La figura 8-4 ilustra diversos tamaños de remaches sin colocar y aplicaciones estructurales que usan remaches.

8-3 TORNILLOS DE ALTA RESISTENCIA

Existen dos clases generales de tornillos que se usan en las aplicaciones estructurales. Se tienen los A-307 de uso general (designación de la ASTM), llamados a veces tornillos sin tornear. Estos tornillos tienen una espiga algo áspera así como las
superficies de contacto, ya que no se tiene tanto cuidado en su fabricación. Los
tornillos A-307 se hacen de acero con una resistencia última FII , del orden de 60
(grado A) a 100 (grado B) kip/pulg 2 (415 a 690 MPa) y están disponibles en
diámetros de 114 pulg (6 mm) a 4 pulg (102 mm) y en longitudes de 1a 8 pulg en
incrementos de 114 de pulg , y de más de 8 pulg., en incrementos de 112 pulg, Los
tornillos A-307 se pueden obtener con diversas configuraciones de cabeza y tuerca, pero las cabezas cuadradas y hexagonales son las que usan con mayor frecuencia. En la figura 8-5 se ilustran varios tamaños de tornillos A-307.
Los tornillos A-307 son más baratos que los tornillos A-325 y A-49O, y se deben usar en aplicaciones estructurales de cargas estáticas, siempre que sea posible.
Las aplicaciones incluyen su uso en pequeñas estructuras, en lugares en los que la
instalación de los tornillos sea visible para verificaciones regulares de servicio, y
en cargas de servicio que sean relativámente pequeñas.

<!-- p. 404 -->

404 CONEXIONES ATORNILLADAS Y REMACHADAS

Los tornillos de alta resistencia están disponibles en las clasificaciones, tamaños, y resistencia última a tensión, de la ASTM que se muestran en el recuadro inferior de la tabla 8-1:
Las configuraciones generales de longitud, cabeza y tuerca son las mismas
que las de los tornillos A-30?, excepto que puede que no se disponga de los
diámetros mayores. Los tornillos A-325 se pueden obtener con la metalurgia
apropiada para usos especiales, como la resistencia a la corrosión. También se
pueden obtener los tornillos A-325 con una capa galvanizada.
Cuando se introdujeron por primera vez los tornillos de alta resistencia en
aplicaciones estructurales, se requerían roldanas para distribuir la carga sobre el
tornillo en un área mayor del metal más suave de las partes conectadas. Este requisito se debía, en parte, a la tendencia de la tuerca y la cabeza a hincarse (excoriar) en los aceros (A-33 y A-? (Fy = 33 kíp/pulg.s) de que se disponía en aquella
época. Las aplicaciones corrientes de tornillos de alta resistencia requieren el uso
de una roldana endurecida bajo el elemento que se hace girar, como se indica a
continuación:

Método para apretar
Vuelta de tuerca Torque especificado

No Sí
Sí Sí

a Se requerirán roldanas cuando se usen agujeros extragrandes para los tornillos. También se requerirán roldanas cuando la pendiente del patín sea mayor de 1:20 (Los perfiles S y C tienen ambos
una pendiente en el patín interior de aproximadamente 1:6).
b Se usarán roldanas en la cara en pendiente del patín, como en el caso anterior. Se usarán dos
roldanas cuando el material que se ha de sujetar tenga un Fy \< 40 kips/pulg.I.

•"iRura 8-S Se pueden obtener tornillos A-307de uso general con cabezas hexagonales o cuadradas. Se
pueden usar con roldanas.

<!-- p. 405 -->

TORNILLOS DE ALTA RESISTENCIA 405

Se requerirán roldanas achaflanadas en la superficie en pendiente, entre la cabeza
o tuerca del tornillo, cuando la pendiente de la parte conectada sea mayor de
1:20, como para los perfiles C y S. En la figura 8-6, se muestran diversos tipos de
tornillos A-325 y A-490.
Se dispone también de tornillos y accesoriospatentados (véasefigura 8-7)y que
incluyen tornillos de interferencia que se deben insertar en los agujeros de los toro
nillos y que proporcionan un ajuste apretado similar al de un remache ya colocado. También hay disponibles tornillos ranurados de tal manera que un solo insta-

(o) (b)

Figura 8-6 Tornillos de alta resistencia. (a) Tornillos A-325. Las tres marcas a 120° siempre indican
tornillos A-325. Algunos fabricantes los troquelan también "A-325". (b) Tornillos A-490. Nótese que
el grado siempre se marca, como se indica, en la cabeza del tornillo.

lador, usando una llave de potencia, puede darle el torque necesario sin que necesite que un ayudante impida que la cabeza gire. Se tienen también roldanas nervadas, las que se aplanan con el torque especificado, de manera que el instalador
puede observar visualmente la adecuada tensión del tornillo. Hay también tuercas
autotrabadoras para la instalación en conexiones sujetas a cargas dinámicas, de
manera que la tuerca no se afloje durante el servicio.
Los tornillos usados en las aplicaciones estructurales varían de 1/2 a 1 1/2
pulg (ocasionalmente, su utilización de diámetros mayores, especialmente como
pernos de anclaje de columnas en conexiones resistentes al momento en las cimentaciones de concreto). Como hay que establecer un balance entre el tamaño de la
sección neta de la junta y el número de conectores, los diámetros más comúnes de
tornillos y remaches son los de 3/4 y 7/8 pulg (20 y 22 mm).

<!-- p. 406 -->

406 CONEXIONES ATORNILLADAS y REMACHADAS

Figura 8-7 Tornillos y accesorios para aplicaciones especiales. Se muestran dos tipos de tornillos de
interferencia, contracturas y un tornillo ranurado.

tos tornillos de alta resistencia se instalan con una tensión desarrollada en la
espiga del tornillo de aproximadamente el 70 por ciento de la tensión mínima a
tensión especificada por la ASTM por cualesquiera de los dos métodos:

l. Método de la vuelta de tuerca. La tuerca se aprieta inicialmente hasta un ajus-
te sin holguras (siendo el punto en el que una llave de tuerca de impacto em-
pieza a tener efecto, o sea aproximadamente 112vuelta a partir del momento
en que se desarrolla alguna resistencia en la tuerca usando una llave). A partir
de este punto se hace girar la tuerca con respecto a la espiga del tornillo 112
vuelta adicional (3/4 de vuelta cuando L > 8D o 200 mm).
\2. Control del torque. Se usan llavescalibradas de torque o de impacto. Este mé-
todo requiere el uso de roldanas endurecidas bajo el elemento que gira, ya sea
la cabeza o la tuerca del tornillo) para evitar la excoriación y proveer una fric-
ción más uniforme.

Pruebas realizadas en un gran número de juntas atornilladas indican que
cualquiera de estos dos métodos ponen suficiente fuerza en la espiga del tornillo
para producir la tensión requerida. El lector debe tomar nota de que este procedimiento de instalación somete a prueba al tornillo. Si el tornillo está sobresforzado, sencillamente se parte y se puede Instalar un nuevo tornillo. Un tornillo de
fabricación defectuosa se detectará fácilmente. Lo que no se puede detectar es si.
se ha producido la tensión adecuada. Por tanto, es necesario una cuidadosa inspección de la obra, revisando frecuentemente el equipo de instalación para asegurarse de que las juntas son adecuadas. .

<!-- p. 407 -->

TORNILLOS DE ALTA RESISTENCIA 407

Tabla 8-2 Tensión mínima prescrita en los tornillos, para la instalación apropiada
(a estos valores se les llama también "carga de prueba del tornillo")

Tensión en el
tornillo, kips Tensión en el tornillo, kN
Diámetro del Diámetro del A-325 A-449 A-490 A-325 A-449 A-490 tornillo, pulg, tornillo, mm

2" o- 73 I 12 ..,.o o- 17 12.5 52 ..,.o s 19 27 15 i 75 105 -\< -\< 3 -o -c 28 20 40 V"\ 141 200 V"\ N 7 N • M M 39 55 22 170 r 240 ~ ~ 1 51 73 25 220 310 '" ~ J! 56 91 28 8 275 :§ 388 '2 '2 ... J! 71 116 30 322 ... 454 B B • ... P8 85 ~ 138 35 438 ... 618 '"... J!1 104 :J'" 168 40 591 :J'" 834
Mayor de 1 112 O,7Fua Mayor de 40 0.7Fua
\- -- ----------------- - --------------
2 137.5 Kips 50 628MPa
2!• 178.8 60 886 2!2 220 65 1057
2~• 271 70 1215 3 328 75 1440

a Fu = resistencia última a tensión (véase tabla 8-1),

Una tensión en el tornillo de aproximadamente 0.7 Fuprovee adecuada resistencia de reserva para el caso de que el tornillo esté algo sobresforzado (o sea, 3/4
de vuelta en lugar de 112 vuelta). La tensión en el perno actúa como un resorte
macizo para mantener las partes conectadas en su posición relativa. Este efecto de
agarre tiende también a mantener la junta de manera que no se afloje la tuerca en
las situaciones de carga de fatiga, de modo que no se requiere casi nunca una tuerca de cierre. Si los tornillos A-325 no han sido excesivamente sobresforzados (no
más de 1/2 a 3/4 de vuelta de la tuerca) se pueden volver a usar una vez o más.
Las pruebas de reuso indican que, en muchos casos no se deben volver a usar los
tornillos A-490.
La tensión mínima del tornillo, basado en O.7Fu produce la carga mínima de
prueba del tornillo, o la tensión de instalación, como se muestra en la tabla 8-2.
Con pocos tornillos en una junta, desarrollando tensiones cada uno de ellos, como se muestra en la tabla 8-2, se puede calcular fácilmente la carga sobre la junta
que se necesita para producir un deslizamiento relativo entre las partes conectadas:

PdeSliZ = mILN T (8-1)

<!-- p. 408 -->

408 CONEXIONES ATORNILLADAS Y REMACHADAS
donde p, = coeficiente de deslizamiento (se pueden usar generalmente 0.35 para
un tornillo limpio; casi todas las otras superficies tienen un valor me-
nor, y puede que sea necesario determinar dicho valor por ensayos)

m = número de superficies de deslizamiento
N = número de conectores
T = carga de prueba de cada conector (como se ve en la tabla 8-2)

Al considerar la ecuación (8-1) se ve fácilmente que, no importa el tipo diseñado
de junta (fricción o sea sin deslizamiento, o de aplastamiento, con algo de deslizamiento aceptable), la carga aplicada a la junta debe exceder a Pdesliz antes de que se
desarrolle el cortante en el tornillo o el aplastamiento en el mismo. Se puede ver
entonces el fundamento de P, = AgF(, ya que el efecto de agarre se distribuye
fuera de los agujeros a lo largo de la sección crítica neta. Después de Pdesl' la junta
desarrolla realmente resistencia, como una combinación de cortante y aplastamiento en el tornillo.
Ejemplo 8-1 ¿Cuál será el factor nominal de seguridad contra deslizamiento
relativo en una junta de fricción que usa tornillos A-325 de 20 mm? Tómese
p, = 0.35.

SOLUCION La carga de prueba del tornillo es 141 IN (tabla 8-2). El esfuer-
zo cortante permisible utilizando las especificaciones del AISC (tabla 8-1) es
120 MPa con rosca en el plano de cortante. De la ecuación (8-1):

\~deslizF mpNT = ¡d(141)
ya que solamente es necesario considerar un tornillo, y se considerará sola-
mente un plano de deslizamiento, como en una junta traslapada. El factor de
seguridad se define siempre como

P resistente
SF=---
P permisible
El valor de Ppermi. es
Pdesliz = FvAb(nominal)
Combinando, se obtiene el factor de seguridad:

SF = 0.35(141) = 1.31
120(0.7854 X 0.02\<Y)loJ

El lector deberá tener en cuenta que este factor de seguridad es contra el
deslizamiento y no es el factor de seguridad de la junta, que es del orden de
1.67 (para una junta a tensión, y puede depender de la tensión en la sección
neta).

<!-- p. 409 -->

FACTORES QUE AFECTAN EL DISEÑO DE LAS JUNTAS 409

8-4 FACTORES QUE AFECTAN EL DISEÑO DE LAS JUNTAS
En la discusión que precede se consideraron diversos factores implicados en el di-
seño de la conexión, particularmente en lo que respecta a los sujetadores. Se con-
siderarán ahora otros varios factores.

8-4.1 Longitud de la junta

Un factor de considerable importancia es el de las dimensiones de la junta. Obviamente, las juntas más pequeñas son más económicas en el uso del material. Sin
embargo, como se hace la suposición de que cada sujetador en una junta soporta
una parte prorrateada (que es igual para sujetadores de tamaño constante), se
presenta un problema con las juntas largas. Al referirse a la figura 8-8, se ve que
la distribución de deformación no es igual entre el primero y el último tornillo. Si la
junta es muy larga (no se define aquí específicamente la expresión "muy") es evidente que el primer tornillo llevará más de PIN de la carga, y el último tornillo no
llevará nada o casi nada. Si se diseña el metal base o placa como adecuada a tensión en la sección neta, la placa no se raja pero se estira según PLIAE, de manera
que los primeros tornillos (o remaches) o bien sufrirán deformaciones de cortante
compatibles, o si no se cortarán si la deformación y el desplazamiento resultante
hacia adelante del agujero resulta demasiado grande. La pérdida del primer tornillo transferirá la carga al siguiente tornillo (o tornillos) en la línea, y el siguiente
tornillo se podrá cortar y así sucesivamente produciendo una falla progresiva en
la junta (este proceso se llama "desabrochado"). Sin embargo, nótese que con las
grandes cargas involucradas, este proceso es casi instantáneo. Si la junta es lo
suficientemente corta como para que todos los tornillos tengan carga, el primer
tornillo se deforma junto con la placa. Cuando se desarrollen deformaciones
correspondientes al esfuerzo de fluencia (cortante), los tornillos continúan deformándose sin que haya aumento en la carga, yel siguiente tornillo (o tornillo) en
la línea tomará la carga transferida. Se alcanzará la carga última de la junta cuando hayan cedido todos los tornillos. Rara vez se efectúan análisis de compatibilidad de deformación, ya que los factores de seguridad usados, junto con la propiedad de ductilidad del acero son tales que, excepto con juntas largas, solamente
ceden los primeros tornillos (si acaso) en una conexión, o cuando menos están
cerca de ceder. .
Debe tenerse en cuenta que el factor de seguridad de la conexión (especialmente el de los sujetadores) debe ser mayor que el de los miembros que se conectan. Esto se hace para que siempre ocurra la falla del miembro antes que la falla
de la junta. La falla de una junta será por lo general catastrófica, mientras que es
posible que la falla de un miembro dé tiempo para que se tomen medidas de seguridad.
Teniendo en mente que ninguna junta (con agujeros y en tensión) tiene una
eficiencia mayor del 85 por ciento, y basándose en los trabajos de Bendigo, Hansen y Rumpf ("Long Bolted Joints", Proceedings, ASCE, Vol. 89, STO, di-

<!-- p. 410 -->

410 CONEXIONES ATORNILLADAS y REMACHADAS

P ---F~ ~PIN = supuesto
ct=t=t=tj +-p

x I Distribución de la deformación en
\~ la placa inferior de la junta que se
muestra más arriba (aproximada).
Figura 8-8 Distribución de la carga y deformación en las juntas atornilladas.

ciembre, 1963),se puede calcular la eficiencia de la junta como, suponiendo un espaciamiento razonable de los tornillos del orden de 3 X diámetro:

(8-2)
donde
pie. lb. seg. CI = 0.007 SI: CI = 0.00275
C2 = 16pulg. C2 = 406 mm

Esta ecuación indica que las conexiones tienen longitudes hasta de 406 mm,
tienen una eficiencia de 85 por ciento (esto es, no se efectúa reducción alguna en
la capacidad de la conexión debido a la longitud de la junta). Para longitudes mayores, existe una pérdida casi lineal en la capacidad de la junta, hasta alcanzar un
valor de aproximadamente el 60 por ciento de la junta corta, cuando la longitud
sea del orden de 50 pulg (1250 mm).
Las especificaciones actuales del AISC tienen en cuenta indirectamente las
juntas largas usando el factor de eficiencia de 85 por ciento y ajustando el esfuerzo permisible del sujetador. Los valores de los esfuerzos del sujetador (para conexiones de aplastamiento) se consideran válidos hasta una longitud de junta de 50
pulg (1250mm). Para valores mayores que esta longitud el esfuerzo cortante permisible se debe reducir un 20 por ciento. Teniendo en cuenta que las especificaciones proveen los requerimientos mínimos, el diseñador estructural tiene la opción de usar la ecuación (8-2) para longitudes intermedias de la junta, entre 16y
50 pulg.

8-4.2 Distancia al borde

Si los tornillos en la línea de esfuerzos están situados demasiado cerca del borde,
puede que sea posible que se arranque la placa, como se muestra en la figura 8-3b/
yen la junta real que se muestra en la figura 8-9..psto se puede evitar usando una
distancia al borde obtenida igualando las fuerzas cortantes y usando F v = constan-
te tanto para el tornillo como el metal base, para así obtener

<!-- p. 411 -->

FACTORES QUE AFECTAN EL DISEÑO DE LAS JUNTAS 411

AbFv = dtFv
Abde donde se encuentra que la distancia al borde, d, d=- I
t
El AISC requiere esta distancia al borde en la sección 1-16.4, y usar una distancia
al borde d' = 2d, cuando el tornillo está a doble cortante.
Cuando se vaya a punzonar los agujeros, es necesario tener distancias adecuadas al borde y al extremo, para evitar daños por alabeo en el material. Las especificaciones del AISC (Sección 1-16.4) dan estas distancias basadas en el
diámetro nominal del tornillo. Para diámetros de los tornillos, d ::; 1 114 pulg
(30 mm), la dimensión nominal medida del centro del agujero al borde es:
Borde cortado: De = 1.7 X diámetro (redondeado hasta el 118 pulg más
cercano, o 3 mm)
Borde laminado: De = 1.4 X diámetro (redondeado hasta el 118 pulg más
cercano, o 3 mm)

(b)

(a)

Figura 8-9 Diversas maneras de fallar una
junta. (a) Varias juntas. (b) Falla por cortante
de un tornillo. (e) Tensión en la secciónneta.
(d) Falla por rasgamiento debido a que los
tornillos estaban demasiado cerca del extremo
(e) en la dirección del esfuerzo.

<!-- p. 412 -->

412 CONEXIONES ATORNILLADAS y REMACHADAS

Para diámetros del tornillo mayores de 1 ~ pulg. (o 30 mm) se usará:
Borde cortado: De = 1.75 X diámetro
Borde laminado: De = 1.25 X diámetro '

8-4.3 Distribución de los tornillos y distancias de gramil

Es necesario asegurarse de una junta razonablemente compacta y donde el material conectado esté en un contacto razonablemente efectivo, de manera que la
fricción desarrollada por el agarre, sea uniforme entre las partes. Si los tornillos
están muy juntos, se tendrá interferencia, ya que el máximo coeficiente de fricción es p, ==0.35, Yla superposición de los efectos produce una resistencia límite
de fricción (es decir, p, Nno aumenta sin límite con el aumento de N). Un espaciamiento demasiado cercano puede traer dificultades al instalar los sujetadores,
ya que la cabeza de la llave requiere un espacio mínimo de operación. Estos
problemas se resuelven con el uso de los requerimientos mínimos de espaciamiento:
AISC (Sec. 1-16.4): smin = 2.67 X diámetro (preferiblemente 3 x
diámetro),'
AASHTO (Sec. 1-7.22C): smin = 3 x diámetro
AREA (Sec. 1-9.3): smio = 3 x diámetro
, El máximo espaciamiento de una sola línea de sujetadores en la dirección del
esfuerzo se debe generalmente limitar a 121, donde 1 = espesor de la parte más
delgada que se ha de unir. Este espaciamiento se puede usar para el AISC,
AASHTO, y AREA.
, La práctica de fabricación, junto con el amplio uso de los sujetadores con
diámetros de 3/4 hasta 1 pulg., ha llevado a establecer ciertas distancias de gramil
normales. Estos valores se muestran en las tablas de perfiles laminados '(véase
tablas l-e a 1-7, y V-3 a V-7 del SSDD) y dependen del ancho de los lados en los
angulares, como en las tablas 1-13 y V-l3, y/en el manual del A1S9
El usuario debe verificar también la mínima distancia al borde en los angulares de modo que el tamaño del sujetador no resulte en un agujero que está demasiado cerca del borde para satisfacer las especificaciones.
Los perfiles laminados, que tengan patines muy anchos, pueden tener una segunda línea de gramil. Los valores para patines muy anchos (por ejemplo, W14,
mayores que 142 lb/pie) se muestran en el manual del AISC, así como en las
tablas que se obtienen de los fabricantes de acero, pero no aparecen en las tablas
SSDD.
El lector debe fijarse en que las distancias "normales" de gramil resultarán
por lo general en costos de fabricación más económicos, pero estas distancias no
son las únicas que se pueden usar. Sin embargo, el diseñador debe consultar al
fabricante, en el caso de que se contemple usar distancia de gramil distintas de las
normales, a fin de producir una junta económica.

<!-- p. 413 -->

FACTORES QUE AFECTAN EL DISEÑO DE LAS JUNTAS 413
8-4.4 Diseño mínimo de las juntas

Las especificaciones del AISe requieren que todas las conexiones, excepto las de
las armaduras, que soportan esfuerzos calculados se diseñen para la carga de diseño, pero no menos de 6 kips (o 27 kN).
Las especificaciones del AIse requieren que las juntas en las armaduras, ya
sea a tensión o compresión, se diseñen para la carga de diseño, pero que nunca
sea menor que el 50 por ciento de la resistencia efectiva del miembro, basada en el
tipo de esfuerzo de diseño.
Lls especificaciones de la AASHTO requieren que las conexiones se diseñen
sobre¿la base del promedio de la carga de diseño y la resistencia efectiva del
miembro, pero que no sea menor que el 75 por ciento de la resistencia efectiva
del miembro. Esto se debe a que muchos de los miembros estructurales en el diseño de la AASHTO están controlados por otros factores que no son el esfuerzo,
como la L/r. Se requieren cuando menos dos sujetadores en cualquier conexión
diseñada según la AASHTO.
El AREA requiere que las conexiones de los miembros principales se diseñen
para la resistencia efectiva total del miembro. Para miembros secundarios y
contravientos, la conexión se diseñará para el promedio de la resistencia del
miembro y el esfuerzo de diseño. Se requiere un mínimo de tres conectores en
cualquier conexión diseñada según el AREA.

8-4.5 Rezago del cortante

Las juntas largas no son deseables desde el punto de vista de la reducción de la
eficiencia (por debajo de 85 por ciento cuando L > 406 mm), pero en los casos en
que se usan perfiles W, S, o e junto con placas de conexión en los patines (véase
figura 8-10), es necesario obtener una junta suficientemente larga para que el esfuerzo en la sección A-A se pueda transferir a y por los patines.hasta las placas de
conexión. La fuerza axial en el miembro a tensión que se muestra, retarda la
transferencia a la placa de conexión, debido a su distribución a través del
miembro a tensión. Si la longitud de la junta es muy larga, el miembro a tensión
podrá fallar debido a una gran concentración de esfuerzos en el alma, produciendo una rasgadura y una falla progresiva a través de la sección. La medida de la
eficiencia del rezago del cortante se basa en la distancia desde el eje de gravedad
del miembro hasta el plano del sujetador (o placa de conexión). Munse y Chesson
("Riveted and Bolted Joints: Net Section Design", Proceedings, ASeE, STI,
febrero, 1963) dan una ecuación para la eficiencia del rezago del cortante:

(8-3)
donde x = distancia desde el eje de gravedad al plano del sujetador (= dl2 para
los perfiles W y sencillamente x en las tablas de angulares)
L = longitud de la junta

<!-- p. 414 -->

414 CONEXIONES ATORN!LLADAS y REMACHADAS

Para casi todas las secciones bien diseñadas, la ecuación (8-3) debe dar un valor de esl de 85 a 90 por ciento. Las reducciones del AISC para el rezago del cortante se presentaron en la sección 5-3.2.

\3. Transferencia inicial de parte del esfuerzo en el patín a las placas de conexión.

\2. Placa de conexión
Perfil W

P

a=P/A
\4. En este caso, el
1------- L-----.... esfuerzo en el alma
está muy cerca de cero

Figura 8-10 Rezago del cortante en un perfil W conectado a un par de placas de conexión.

sencillo o doble

Figura 8-11 Angulares auxiliares. Se pueden usar angulares auxiliares en ambos lados de la placa de
asiento, cuando se usa un par de angulares como puntal.

8-4.6 Tomillos largos

Las primeras pruebas realizadas con los remaches, indicaban una pérdida de efi-
ciencia debido a la flexión, cuando la relación L/d era mayor que aproximadamen-
te 5. Las pruebas de tornillos de alta resistencia para valores de L/d hasta cerca de
9, no indicaron ninguna pérdida significativa de eficiencia. Con base en estas con-
sideraciones, se requiere un aumento en los remaches y los tornillos A-307, como
se indica a continuación:

<!-- p. 415 -->

FACTORES QUE AFECTAN EL DISEÑO DE LAS JUNTAS 415

Aumento requerido

AISC (remaches y tornillos A-307) 1 por ciento para cada 1116 pulg (3 mm) en exceso de
L = 5D
AASHTO 1 por ciento para cada 1116 pulg (3 mm) en exceso de
L = 4.5D
AREA igual a AASHTO

8-4.7 Angulares auxiliares

Se pueden usar angulares auxiliares para reducir la longitud de la junta y el rezago
del cortante de miembros con uno o dos angulares, como se ve en la figura 8-11.
El uso de un angular auxiliar en el extremo delantero de la junta tiende a hacer cero el término xlL en la ecuación (8-3). Sin embargo, puede que se requiera cierta
inventiva para que la sección neta no se reduzca excesivamente debido a los agujeros de los tornillos extra para el angular auxiliar.

8-4.8 Distribución del cortante y el aplastamiento
entre los sujetadores de un grupo

Una premisa básica en el diseño de conexiones es que cada sujetador soporte una
prorrata de la carga de la conexión. Para una junta con sujetadores de tamaño
Tabla 8-3 Tabla para determinar la longitud requerida de los tornillos, basándose
en el agarre y la longitud de rosca (úsese la tabla para determinar si la rosca caerá
dentro del plano de cortante; véase el ejemplo que aparece más abajo)
L,eq = agarre + L; redondéese L,eq hasta el siguiente 114 pulg o 6 mm
Tamaño del L de la rosca L pulg Tamaño del L de la rosca- L,mma tornillo, pulg tornillo, mm

I 11 12.5 25 18 j 16
7 15 30 22 i i ~ l!• 3 ¡ P8 20 35 25
7 l!2 l!8 22 38 28 i
l~• l!• 25 45 30
¡!8 2 ¡!2 28 50 38
8 30 50 42¡!• 2 P
11• 21• P• 35 55 45
l!1 21• 12• 40 55 50

Ejemplo: Para la conexión que aparece en el dibujo y que usa un tornillo de 3/4 pulg de diámetro,
¿estará la rosca en el plano de cortante (definido por la unión de la placa)?

<!-- p. 416 -->

416 CONEXIONES ATORNILLADAS Y REMACHADAS

Agarre = 3/8 + 7/16 + 3/8 = I 3/16 pulg.
De la tabla, L = I pulg. Agarre = I 3/16"
L req = I 3/16 + I = 23/16
Redondéese hasta el siguiente 114 pulg.

L req = 2 114 pulg. 0.8125"
Longitud de la rosca = I 3/8 (de la tabla)

2.25 - 1.375 = 0.875 1rVA')'.
Distancia para las dos placas = 3/8 + 7/16 = ~RosC~
0.8125 pulg. 2 114"
Por consiguiente, la rosca está fuera del plano de
cortante.
constante, en un patrón simétrico y cargados de tal modo que la carga pase por el
centro del patrón, la carga es

PtotaI Psujet = -----:-='-:---:---- número de sujetadores

Esta suposición se puede hacer para el cortante o el aplastamiento del sujetador.
En algunas especificaciones se considera al aplastamiento como el producido por
el sujetador sobre el metal base y en otras del metal base sobre el sujetador. El
área de cortante se obtiene usando el diámetro nominal del sujetador. El área de
aplastamiento es igual a 1diámetro proyectado del sujetador x espesor de la placa: la carga Pi del sujetador es
P« = A b X F; (cortante)
Pb = D x t X Fb (aplastamiento)

No se tiene en cuenta el hecho de que el tamaño del agujero sea 1116 pulg. (I.Smm
mayor que la espiga del tornillo, para el caso del plastamiento.
Cuando el grupo de sujetadores es asimétrico, o la carga no pasa por el
centroide del grupo los sujetadores no están igualmente esforzados. Esta situación se considera en la siguiente sección.
Se observará que el esfuerzo cortante permisible F; depende de la suposición
de diseño de que la junta sea del tipo defricción o de aplastamiento, y de que si la
rosca del tornillo está en el plano de cortante para la conexión de tipo de aplastamiento; La tabla 8-3 se puede usar para determinar si la rosca está en el plano de
cortante. Se pueden usar las tablas 8-1, 8-4, Y8-S para obtener los esfuerzos permisiblessegún las especificacionesdel AISC, ASSHTO, o AREA, respectivamente..La tabla ·8~6 puede servir para obtener los esfuerzos permisibles de aplastamiento de metal base a tornillo, o de tornillo a metal. Los valores del AISC que
aparecen en esta tabla se basan en la resistencia última del material conectado
calculado como

<!-- p. 417 -->

FACTORES QUE AFECTAN EL DISEÑO DE LAS JUNTAS 417

Tabla 8-4 Esfuerzos permisibles en tornillos y remaches para las especificaciones
de la AASHTO (úsese ~I esfuerzo dado con el área nominal del tornillo, excepto
para los tornillos A-307 a tensión) *)a
Esfuerzo cortante permisible, F;
Aplastamiento,
Tensión, F¡ Fricción- Aplastamiento" Fb

Material Kips/pulg.? Kips/pulg.? Kips/pulg.? Kips/pulg.z

Remaches
A-502, grado 1 - - 40 275 - - 13.5 93
grado 2 - - 40 275 - - 20.0 T38

Tornillos
A-307 13.5 93 20 138 - - 11.0 76
A-325N e 36 250 40 275 13.5 93 - -
A-325X 36 250 40 275 - - 20.0 138
A-490N 48 330 50 345 18.0 124 - -
A-490X 48 330 50 345 - - 29.0 200

a Datos tomados de las especificaciones de la AASHTO, 12a. ed., secciones 1-7.22 y 1-7.41.
b Fb = esfuerzo cortante permisible sobre el remache o tornillo, procedente del material que se
sujeta.
C Se requieren conexiones a fricción en los casos en que la conexión esté sometida a inversión de es-
fuerzos.
d Los tornillos en las conexiones de aplastamiento tienen que ser del tipo X (la rosca está excluída
de los planos de cortante). Se usarán conexiones de tipo de aplastamiento para miembros a compresión, o miembros secundarios. Redúzcase un 20 por ciento los valores de los tornillos de alta resisten-
cia, si la longitud de la junta es mayor que 24 pulg. y F; \< k2 kips/pulg.s.
N, roscas en el plano de cortante; X, roscas excluidas del plano de cortante (igual que para el
AISC).
No se hace distinción alguna entre los sujetadores a simple o doble cortante. El
esfuerzo de aplastamiento de la AASHTO, metal a sujetador es:
F; = 1.22Fy
Tabla 8-5 Esfuerzos en los sujetadores según el AREA (todas las conexiones son
del tipo de "fricción")
F, r,
Sujetador kips/pulg. 2 MPa kips/pulg.I MPa

Remaches»
Remachadas a mano n,o 76
Remachadas a presión 13.5 93
Tomillos>
A-325 36 248 20 138
A-490 36 248 27 186

a Se usará esfuerzo de aplastamiento en los remaches: cortante simple, 27 kíps/pulg- 0185 MPa; cortante doble, 36 kips/pulg- o 250 MPa.
b No es necesario considerar el aplastamiento en los tornillos de las conexiones a fricción.

<!-- p. 418 -->

418 CONEXIONES ATORNILLADAS Y REMACHADAS

y estará generalmente limitado por los esfuerzos del sujetador al metal, como se
muestra en la tabla 8-4, bajo la columna encabezada Fb•
Los valores para el aplastamiento que da el AREA se estipulan según el tipo
de sujetador, excepto que no se considera el aplastamiento en el diseño de cone-
xiones que usan tornillos de alta resistencia. Estos valores se muestran en la tabla
8-6.

Tabla 8-6 Valores de aplastamiento para remaches y tornillos según las varias especificaciones (la parte superior de la tabla es para metal sobre sujetador, la parte
inferior es para sujetador sobre metal 8

Material Fu AISC AASHTO AREA

Kips/pulg.s Kips/pulg.? Kips/pulg.? Kips/pulg.I Kips/pulg.?
A-36 250 58 400 87.0 600 44.0 305 - -
Fy OE 46 315 67 460 100.5 690 56.1 390 - -
Fy =- 50 345 65 450 97.5 675 61.0 421 - -
Fy = 60 415 75 520 112.5 780 73.2 506 - -
Tornillos A-307 - - 20 140 - -
Remaches A-SOl y A-502 - - 40 275 - -
Remaches a presión: cortante simple - - - - 27 185
cortante doble - - - - 36 250
Tornillos A-325 y A-49O - - 40 275 No se requiere n

a Parte superior: Fb = 1.5Fu; AASHTO: Fb = 1.22Fy- Parte inferior: depende del ajustador; el
aplastamiento del sujetador controla generalmente en el diseño de puentes.

8-4.9 Factor nominal de seguridad del conector y conexiones

El factor nominal de seguridad contra el deslizamiento en juntas atornilladas es
del orden de 1.25 a 1.30 (según se calculó en el ejemplo 8-1). Queda por averiguar
cuál será el factor nominal contra la falla, de la junta y de los conectores mecánicos.
El factor de seguridad de los conectores mecánicos se puede estimar fácilmente basándose en los valores últimos de los esfuerzos a tensión y cortante, divididos por los valores permisibles que se dan en las tablas 8-1, 8-4, Y8-5.
Pruebas de resistencia al cortante realizadas sobre tornillos de alta resistencia
(véase Wallaert y Fisher, "Shear Strength of High Strength Bolts", Journal 01
Structural Division, Asee, ST5, octubre, 1965) dan valores para el cortante último en términos de la resistencia última a tensión Fu de (véase tabla 8-1):
Tu = 0.62 Fu (placas a tensión)
Tu = 0.68 Fu (placas a compresión)

<!-- p. 419 -->

FACTORES QUE AFECTAN EL DISEÑO DE LAS JUNTAS 419

Estas pruebas indicaron que la tensión inicial del tornillo (efecto de agarre de la
placa) no afecta la resistencia última a cortante del tornillo.
Si se designa el factor de seguridad F como

se obtiene para los pernos A-325 en conexiones de fricción, como diámetros 25
mm (los de uso más corriente)

F = 0.62(825 MPa) = 426
120 .

La geometria de la junta reduce este valor de F a algo así como del orden de 3.3
para juntas compactas (en las pruebas) a alrededor de 2.0 para juntas cuya longitud sobrepasa los 1270 mm (50 pulg.). Este valor de F se compara con el valor a
tensión sobre la sección transversal para el acero A-36 de
F = ~ = 1.72 (sección neta después del deslizamiento)
0.58Fu
Fu 400
o F = 0.6F;, = 150 = 2.67 (sección bruta antes del deslizamiento)

Las observaciones efectuadas sobre juntas con largo tiempo en servicio indican
que un factor de seguridad para los sujetadores de F > 2.0 da un servicio satisfactorio.

8-4.10 Empalmes en vigas

Es frecuente que las vigas se empalmen para producir claros continuos. Por lo general, estos empalmes se colocan cerca del lugar de cero cortante en el claro.
Cualquier uso que se haga de sujetadores mecánicos en el patín de tensión reducirá algo el área efectiva. Basándose en pruebas, las especificaciones del AISC y las
recientes de la AASHTü permiten que el diseñador use el área bruta del patín para los cálculos de esfuerzo, siempre que los agujeros (en el patín a tensión) representen menos del 15 por ciento del área del patín a tensión. Cuando el área de los
agujeros exceda el15 por ciento, se reduce el área del patín en la porción de agujeros en exceso del 15 por ciento.
Por ejemplo, si A¡(del patín a tensión) = 20, Aagujeros = 4, el porcentaje de
área de agujeros = 4 x 100/20 = 20 por ciento. El exceso de área de los agujeros = 20 - 15 = 5 por ciento, y el área del patín a tensión es 200 - 0,05) = 19, y
no 16como se obtendría descontando toda el área de los agujeros (20 - 4 = 16).
Estos cálculos se deben usar también con las placas de empalme del patín.

<!-- p. 420 -->

420 CONEXIONES ATORNILLADAS Y REMACHADAS

Ejemplo 8-2 ¿Cuántos tornillos A-325 se requieren para el empalme a ten-
sión de la sección C31O, que se muestra en la figura E8-2a, si el metal es de
Fy = 250 MPa, y se supone que la conexión es del tipo de fricción, o del tipo
de aplastamiento?

SOLUCION Se usarán tornillos de 22 mm de manera que el diámetro del
agujero = 22 + 3.0 mm. Además, como cada tornillo debe trabajar a cor-
tante doble que el alma de la viga se deslice entre las dos placas de empalme,
la carga por tornillo es

Ptornillo = 2 X A b X F;
Para una conexión del tipo de fricción:

2)(120) P10rn = 2(0.7854 x 0.022 = 91.2 kN/tornillo (doble cortantej.El
número de tornillos requerido es N = 442.5/91.2 = 4.85. Se usarán cinco
tornillos. Se usará el patrón de tornillos de la figura E8-2b, de tal modo que
el'ancho de la placa de empalme sea un máximo, pero que se obtenga la má-
xima sección neta para el canal.

C310X446

11
¡I
442.5 11
1I
il11 - kN- 40 \ 45 1\ 40 ., I IAl 1 11
o 4() :::E Sl:: o 85
/.. =13.0mm ~S o 85
\~ 11 o 85
11 o 40 ~:

Figura S-2a Figura S-2b

Compruébese la sección neta de las placas de empalme. Descontando
tres tornillos, los requerimientos del área son:

Bruta: A = 442.5 = 1.475 x 10-3 m2
p 2 x 0.6F;,

_ 442.5 _ -3 2 Neta: Ap - 2 x 0.5F - 1.106 x 10 m
u

1.106 -3 2 Ag ;:: 0.85 = 1.301 x 10 m

<!-- p. 421 -->

FACTORES QUE AFECTAN EL DISEÑO DE LAS JUNTAS 421

Pruébese con dos placas de 250 x 5 mm, con tres agujeros en la sección
crítica.
A neta= [250 - 3(25.0)]0.01 = 1.75 X 10-3 > 1.l06
Para una línea de tres tornillos y bordes cortados, la distancia mínima al
borde es
1.7(22) = 37.4 mm se usarán 40 mm
Espaciamiento mínimo de los tornillos = 3D = 3(22) = 66 mm
. . 250 - 2(40) C E spacíamíento por usar = 2 = 85 > 66 mm orrecta
Para los dos tornillos delanteros:
Se centran los tornillos a 40 + 8; = 82.5 mm de los bordes

El espaciamiento hasta el borde es menor que el máximo permisible de 12t
\= 12 x 10 = 120 mm. Usese una distancia de 40 mm del tornillo del frente
al borde de la placa de empalme (1.750 para bordes cortados) y de manera
similar de los tornillos de atrás al borde de la W41O. Establézcase la distan-
cia de gramil de modo tal que solamente haya que deducir dos agujeros de la
sección crítica neta.
4s 2
W ~a = 250 - 3(25) = 250 - 5(25) + -~
4s 2
4(85/2) = 50
s =v'2ill = 46.1 mm úsese s = 50 mm (selección arbítraria)
Compruébese el aplastamiento:
En las placas de empalme: Pb = N X Ab X Fb = 5(0.01)(22)(1.50 X 4(0)
\= 660 > 442.5 Correcta
En el alma del C31O: Pb = 5(0.013)(22)(1.50 X 400)
\= 858 > 442.5 kN Correcta
Usense cinco tornillos s para la conexión de fricción.
Para una conexión de tipo de aplastamiento:
Agarre = 2 x 5 x 13.0 = 23.0 mm
L req. = 23.0 + 28 = 51 se usara 55 mm
Lrosca = 38 mm (tabla 8-3)
Ancho de una placa de empalme + alma de la viga = 5 + 13 = 18.0 mm
Distancia de la cabeza del tornillo hasta el fin de la rosca = 55 - 38 = 17
mm \< 18 mm

<!-- p. 422 -->

422 CONEXIONES ATORNILLADAS Y REMACHADAS

Este cálculo muestra que la rosca está en el plano de cortante, de manera
que F;= 150 MPa (en lugar de 205) y P torn es
Ptornillo = 2 X Ab X Fv = 2(0.7854 x 0.0222)(150)HY = 114 kN ,
P 452.5 Ntornillos =-- =-- = 3.97 sean 4 tornillos
Ptornillo 114
452.5 _ 26 ( bié 4) Nbrg = 0.013 x 22 X 1.50 X 400 -. se usan tam len

Se usarán dos hileras de dos tornillos para el empalme del tipo de aplastamiento.

Ejemplo 8-3 Diséñese la conexión para el miembro vertical a compresión
(No. 7) de la armadura de carretera de los ejemplos 5-7, 6-4, Y6-6. Refiérase
a la figura E6-6 del ejemplo 6-6, y a la figura E8-3 (refiérase también al
puente de la figura 8-4b). Los ejemplos anteriores se usaron para diseñar el
poste terminal y los miembros del alma 7 y 9. Se usará la misma sección que
se usó para el poste terminal para la cuerda superior (todos en compresión).
El resto de los miembros del alma pueden usar la misma sección que el 7 y el
9 (ya que controlaba L/r más bienque el esfuerzo). En cualesquiera de los
casos, se diseñará la conexión para el miembro vertical del alma (No. 7),
que está a compresión. Datos para la W12 X 58:
A = 17.00 pulg.? d = 12.19 pulg. ti = 0.640 pulg. Usese acero A-36 y
las especificaciones de la AASHTü. Usense tornillos A-325 de alta resisten-
cia. P rnáx = - 99.3 kips (P min = - 40.6 kips). t = 5/16 pulg. para la placa
de conexión (t mínimo permitido por la AASHTü para una placa).

\3. Tornillos de 7/8,
según se requieran 4. Miembro No.
l. Se requiere placa de relleno S:¡;;~;;;;;;~;;;:;;;;;;;:;;;;9¡;;;;6;;;;;;;;:;;;;;;;:;;;;~===ntr=12. Cuerda superior
o O O
\--1,--+-- O O ~ O O - ---- ----
O O ,"= C12 X 30 ---l-~ -01X--/~"~::--'\(
I I \<, 5 "
I O 01 / O, x I O Ot I O I/O'~O'1\< O o, 1(,
I 1', O O Wl2X53
I 1, O -,
I O 01 'o
I 0 ""
9 12.1'1"

(12'1.2) 99.3 k

Figura E8-3

<!-- p. 423 -->

FACTORES QUE AFECTAN EL DISEÑO DE LAS JUNTAS 423

SOLUCION El diseño del sujetador se basará en una conexión del tipo de
fricción. La AASHTO no permite una conexión del tipo de aplastamiento
en un miembro principal. No es necesario considerar el rango de esfuerzos en
el diseño de la conexión.
Se probarán cuatro tornillos de 718 pulg. de diámetro, en una sección
como la que se muestra en la figura E8-3, la misma que se supuso en el diseño del miembro 9 a tensión en el ejemplo 5-7. No es necesario hacer la deducción para el área neta para los miembros a compresión, a menos que no
ocurra una inversión total de esfuerzos (lo que no ocurre en este caso).
La AASHTO (Sección 1-7.16) requiere que una conexión se diseñe para
el promedio de la carga de diseño y la resistencia total efectiva del miembro,
pero que no se"á menor del 75 por ciento de la resistencia efectiva del
miembro. Del ejemplo 6-4, el esfuerzo axial permisible de compresión era
de 9.35 kip/pulg.z.
Pstr = AFa = 17.00(9.35) = 159.0kips
P = 159.0; 99.3 = 129.2kips av

El criterio del 75 por ciento de la resistencia para el miembro da
PO.75 = 159.0(0.75) = 119.3 kips \< 129.2
De la tabla 8-4, el esfuerzo cortante permisible en el tornillo es F; = 13.5
kip/pulg.? El número de tornillos requeridos en la conexión para transferir
129.2 kips es
N = -!..~ ... 129.2 = 15.9 tornillos
AóF" 0.7854 x 0.8752 X 13.5
Usese N = 16 tornillos por simetría y porque no es posible usar 0.9 de tor-
nillo. El uso de 16 tornillos requiere cuatro filas. Usese un espaciamiento
para los tornillos de 3D:
s = 3(D = 2~pulg.

Usese una distancia mínima al borde en la línea de esfuerzo de 1 112 pulg,
(1.75D para bordes cortados)
Longitud total de la junta = 4(2.625) + 2(1.5) = 13.5¡pulg

Con una longitud de junta de 13 112pulg. (nominal), el rezago del cortante
no constituye un factor. La distancia transversal mínima que se requiere
hasta el borde = 1.25D, redondeado hasta el 118 pulg. más cercano por
arriba, o 3 mm para los patines de vigas y canales (pero no para placas y
otros elementos). Esto da

de = 1.25(i) = lipulg(1.l25.pulg,)

<!-- p. 424 -->

424 CONEXIONES ATORNILLADAS y REMACHADAS

La distancia suministrada y basada en la distancia normal de gramil = 5.5
pulg (véanse tabla 1-3) se calcula como
bJ - 5.5 10.01 - 5.5
d sum = 2 2 = 2.26pulg Correcta
Compruébese el aplastamiento del perno sobre la placa de conexión, ya que
tp = 0.313 \< 0.640 del patín de una W12.
Papl. = 16(0.875 x 0.313)(40) = 175.3 kips > 129.2 Correcta
La placa de conexión se puede hacer lo suficientemente ancha para que la
tensión sobre la sección neta no constituya un factor. Se necesitarán algunas
placas de relleno entre la placa de conexión y los canales, puesto que la sec-
ción W12 tiene un peralte mayor de 12 pulg. / / /

Ejemplo 8-4 Diséñese la conexión para los miembros verticales de la arma-
dura principal de techo del ejemplo 2-6, que se diseñaron en el ejemplo 5-6.
F; = 250 MPa. Otros datos incluyen:
P = 70.18 kN (tensión)
2 Ll27 x 89 x 6.3 (Lj r- control)
A sum = 266. • X 10- 3 m2 A e = 1.695 X 10-3 m2

Este diseño se basa en el uso de una placa de conexión de 12 mm y tornillos
de alta resistencia de 25 mm.

SOLUCION El AISC requiere que las conexiones para los miembros de ar-
maduras se diseñen, ya sea para la carga de diseño o para el 50 por ciento de
la resistencia efectiva del miembro.
Pso = 0.5(0.6Fy)Ag = 0.5(150)(2.66) = 199.5 kN rige
Pso = 0.5(0.5Fu)Ae = 0.5(200)(1.695) = 169.5 kN
Los tornillos que atraviesan los angulares y la placa de conexión estarán a
doble cortante, como se ilustra en la figura E8-4b. Como prerrogativa del
diseñador, supóngase que es satisfactoria una conexión del tipo de aplasta-
miento (se puede tolerar el deslizamiento). Verifíquese la longitud del tor-
nillo usando la tabla 8-3 para comprobar si la rosca está en el plano de cor-
tante.

L

l. Placa de conexión Figura 8-4a

<!-- p. 425 -->

REMACHES Y TORNILLOS SOMETIDOS A CARGAS EXCENTRICAS 42S

A A

c m m
Tornillos de 25 mm
1c7 X 89 X 6.3~
A-A

Figura S-4b

Agarre del tornillo = 6.3 x 2 + 12 = 24.6 mm
L = 24.6 + 30 = 54.6 se usará 60 mm
Lrosca = 45 mm (tabla 8-3)
Un angular + placa de conexión + 6.3 + 12 18.3 mm
Alcance de la rosca = 60 - 45 = 15 mm

15 mm \< 18.3 la rosca está en el plano de cortante (véase figura E8-4a)
Con la rosca en el plano de cortante, F; = 150 MPa (Tabla 8-1):
P'ornillo= 2(0.7854 x 0.0252)(150)1Q3 = 147kN
N = 1~:~5 = 1.36

Se usan dos tornillos para el cortante, ya que no es posible usar una fracción
de tornillo.

Verifíquese el aplastamiento:
Fb = 1.5(400) = 600 MPa (Fu de la tabla 8-6)

Sobre los angulares: Pb = 2(2 x 0.0063)(25)(600) = 378.0 > 175.9 kN
Correcta
Sobre la placa de conexión: Pb = 2(0.012 x 25)(600) = 360 > 175.9 kN
Correcta
Seusarán dos tomillos A-325 de 25 mm yuna placa de conexión de 12mm. / / /

8-5 REMACHES Y TORNILLOS SOMETIDOS A CARGAS
EXCENTRICAS

En general, se desprecia la excentricidad de la carga en un grupo de tornillos,
cuando dicha excentricidad es menor de 2 112 pulg (60 mm). Dentro de esta
categoría se encuentran las juntas como la simple conexión estructural de la figura 8-20, la que tiene amplia utilización. La conexión de ménsula de la figura 8-120

<!-- p. 426 -->

426 CONEXIONES ATORNILLADAS Y REMACHADAS

está cargada con una excentricidad que es obviamente demasiado grande para poder despreciarla. Se puede tomar nota de que los angulares normales de conexión
estructural del manual de diseño del AISC desprecian la excentricidad para valores hasta unas 3.7 pulg (en la figura 8-12b, se muestra una de las conexiones normales de estructura con angulares, con un valor de máxima excentricidad que es
casi igual).
Una carga que ha de resistir un grupo de tornillos que es excéntrico con respecto al centroide del patrón del grupo, se puede sustituir por una fuerza que
tiene una línea de acción a través del centroide del patrón y un momento con la
magnitud M = Pe, donde e es la excentricidad de la carga. Esto se muestra en la
figura 8-130 y b. Considerando de nuevo que cada tornillo en un patrón que está
centralmente cargado, lleva su prorrata de la carga total, se tiene, para tornillos
p
Psi = N
del mismo tamaño, donde Psi es la fuerza cortante sobre el tornillo de orden i, con
un vector que resiste la carga aplicada P.
El momento excéntrico M = Pe, desarrolla una fuerza adicional en el tornillo. Suponiendo un grupo de tornillos que actúa como una unidad elástica, se
tiene un concepto similar al del desarrollo de la resistencia de la viga y relacionado con el momento de inercia de la misma. Refiriéndose a la figura 8-14, se tiene
un patrón de tornillos con un momento aplicado M, que produce un momento resistente para el equilibrio rotacional que es igual a

i-n
M, = ~ R¡d¡ = M aplic (a)
;-1
Si se supone que el valor de R¡ es proporcional a la distancia del centroide del
p
2t"3"
Para 1 M r-r-N
00 00 b)
00 00
00 00 o o
00 00 o
00 00 o o
o ~-e-
o o f ~I~

R P
e = 3~) + 2!
e) e = 3.625"
Figura8-12 Conexiones con canti eeeentríeída . Refiérase también a la figura 8-15a,
b, y c. (a) Ménsula de columna. (b) Una de las varias conexiones normales de viga a columna, como se
muestran en el manual de diseño del AISC. (c) Fotografia de la viga con los angulares de conexión
iguales a los de (b). Nótense las pequeñas vigas con angulares de conexión y agujeros en los lados de
afuera, que se ven al fondo arriba y a la derecha.

<!-- p. 427 -->

REMACHES Y TORNILLOS SOMETIDOS A CARGAS EXCENTRICAS 427

p
y
\~
O o~ O
PH
O X X ---B- c.g. c.g. O L'0O O O
t(a) (b)

Figura 8-13 Patrón de tornillos excéntricamente cargados. (a) Patrón actual de los tornillos y carga.
(b) Sistema equivalente para el análisis.

M = Pe
R2 2
P
"j \\., -f- - - ~~--- ---,Rb
I I l c.g. I RM1
R] \\., ~ 11' 0.' ~-- I ~ I
I c.g.
3 t = pl4 (en este caso) R4 Rs = PIN
R =y'(Rv+Rs)2+Rh2
(al (b)

Figura 8-14 Patrón excéntrico de los tornillos para obtener la fuerza o esfuerzo resistente en el tornillo. (a) Patrón de los tornillos. (b) Fuerzas sobre el tornillo No. 1 (pero similar a cualquier tornillo).

patrón de los sujetadores, se tiene
R I R2 R3 (b) = "dI = d2 = d3
Se tiene, en términos de R I
dI
R I = Rld (e) I
Sustituyendo la ecuación (e) en la ecuación (o), se obtiene

R Id + Id + R I + (d) u, = Pe = dt R di df I I -d I
Reuniendo términos y simplificando, se obtiene
R l M, = d (dt + di + df + . . . +d;)
l

<!-- p. 428 -->

428 CONEXIONES ATORNILLADAS Y REMACHADAS

Esto se puede simplificar aún más

y resolviendo para R l' se tiene
Pe(dI) M(dI)
R =--=-- (e)
I "i.d2I "i.d.2I
De la ecuación (e),

Similarmente,
Md)
R) = -- etc.
"i.d2I

Como la acción de P al pasar por el centroide del grupo de tornillos produce una
resistencia adicional en el tornillo, la que se debe sumar al vector R momento> es mejor obtener las componentes H y V de RmomentoO Refiriéndose a la figura 8-14b, se
pueden obtener por proporción las componentes de R¡, que son Ri; y Ri:

(J)

Se obtiene, además, para R;
Mx
R" = "i.d.2 (g)
I

Similarmente, de la figura 8-14b, es evidente que

y se puede interpretar como el momento polar de inercia de un grupo de áreas
unitarias. Nótese que si se usa el área A con el denominador de ya sea la ecuación
(j) o (g), se pueden obtener R; y R; como esfuerzos. Multiplicando el numerador
por el área A del tornillo de orden i, se obtiene la fuerza R; o Ri, Con A tanto en
el numerador como en el denominador, se cancela, y da R como una fuerza. Para
el diseño general, las ecuaciones son

(8-4)

<!-- p. 429 -->

REMACHES Y TORNILLOS SOMETIDOS A CARGAS EXCENTRICAS 429

Ejemplo 8·5 Se da la conexión de ménsula de la figura E8-5a; los sujetado-
res son tornillos A-325 de 25 mm, y el acero de la placa es F; = 250 MPa.
¿Resulta adecuado el patrón de los tornillos, y la placa, para la carga dada
en una conexión del tipo de aplastamiento suponiendo que la rosca cae en el
plano de cortante?

SOLUCION Como el patrón de los tornillos es simétrico (como en la
mayoría de los problemas prácticos), es fácil localizar el centroide de dicho
patrón, y se marca como c.g., como se ve en el dibujo.

125

\~~J Q)+®Q) CD75 c.g,
4 0) ¡= 12 mm
60 1---1'---+----(
25-mm
día.
A325 Figura ES-5a

125
\~y2 = 2(2 X 752) = 22 500.0 mrrr' X = 2 = 62.5 mm

\~X2 ~ = 6 X 62.52 = 23 437.5 mnr' = 45 937.5
El número de tornillos se muestra en la figura E8-5b. Trácense rayos
desde c.g. y colóquese el vector R¡ perpendicular a cada rayo d¡ y en la direc-
ción que desarrolle un momento resistente que se oponga al momento apli-
cado.
u I.S
62.5 3S.2 2 ¡--- 1 38.2 ~IS.3 El 18.3
El
""1
3 1.S 1'-1 f,:,1.8 o 3 I+ 6 o 18.3 c.g, *18.3 4 31.8 3~I.S
3S.2 4
IS.3 ~S.3 Figura E8-Sb 4

<!-- p. 430 -->

430 CONEXIONES ATORNILLADAS Y REMACHADAS

Calcúlese
P 110 e, = N = 6 = 18.33 kN

que se muestra en la figura E8-5b, para resistir la fuerza aplicada P.
Calcúlese e = ISO + 125/2 = 212.5 mm:
212.5(1l0)x
Ri(h) = 45 937.5 = 0.5088x
Ri(v) = 0.5088y
Establézcase la tabla siguiente y omítanse los signos de x e y (úsense los
vectores previamente trazados en la figura E8-5b para determinar la direc-
ción de los vectores h y v)

Tornillo x, mm y, mm ~,kN Rh,kN

I 62.5 75 31.8 38.2
2 62.5 75 31.8 38.2
3 62.5 O 31.8 O
4 62.5 O 31.8 O
5 62.5 75 31.8 38.2
6 62.5 75 31.8 38.2

Si se colocan estos valores sobre la figura E8-5b, es fácil observar que los
tornillos 1 y 5 son los de más alto esfuerzo (críticos). El tornillo 3 es el que
tiene la menor carga (13.47 kN 1). La fuerza resistente sobre el tornillo se cal-
cula como
R =y(31.8 + 18.33)2+ 38.22 = V 3972.2 = 63.03 kN
\1. = 63.03 = 128.4 \< 150 MPa Correcta
e 0.7854 X 0.0252 X 1000
Compruébese el aplastamiento de la placa:
(= 63.03 = 210.1 1.5(400) Correcta Jb 0.025(12) \<
Verifíquese la posible ruptura por tensión de la placa, a lo largo de la línea
frontal de tornillos:

Momento de inercial = 0.012\~270)3 - 2(0.012 X 0.025)(0.075)2
l = 16.308 X 10-6 m"
Módulodesección S 16.~~~(2) = 0.1208 x 10-3 m3 =4=

<!-- p. 431 -->

REMACHES Y TORNILLOS SOMETIDOS A CARGAS EXCENTRICAS 431

Momento en la línea frontal de
tornillos = Pe' = 110(0.15) = 16.5 kN . m
M 16.5
0.6~ Correcta lb = S = 0.1208 = 136.6 MPa \<

Verifíquese el pandeo de la placa:
b 150 .rz: 250/V~ Correcta t =12 = 12.5 \<

La junta es adecuada para cortante en el tornillo, aplastamiento de la placa
sobre el tornillo, y flexión. / / /

Ejemplo 8-6 Se da la ménsula para una grúa viajera, con una carga como se
muestra en la figura E8-6. Usese acero A-36 y tornillos A-325 de 7/8 o de 1
pulg de diámetro. Supóngase una conexión del tipo de fricción. Hállese el
número de tornillos y el espesor de la placa de la ménsula.
P =SOk

I
o i T03~ o o I
\~ + J.-2or 1" V"> o c.g. if I 8
I
o 12 o i Tornillos I
O O I1

Figura E8-6.

SOLUCION: Calcúlese
5.5 i e = 15 + 2 = 17.75 pu g
M = 17.75(50) = 887.5 pulg kips
x = 2.75 pulg
y¡ depende del número de tornillos. Pruébense 12 tornillos. Nótese que el
tornillo 1 es siempre el de mayor esfuerzo para un patrón de tornillos como
este.
L(X2 + y2) = 12(2.75)2 + 4(7.52 + 4.52 + 1.52)
\= 405.75
s, = ~~ "'" 4.17 kips

_ 887.5 ) _ . 8875
Rh - 405.75 (7.5 - 16.40 kips R" = 405.75 (2.75) = 6.01 kips

<!-- p. 432 -->

432 CONEXIONES ATORNILLADAS y REMACHADAS

Como 16.4/0.7854 = 20.88 > 17.5 kip/pulg 2, el número de tornillos de 1
pulg de diámetro es demasiado pequeño, aun sin calcular R.
Pruébense 16 tornillos (pasando por alto el 14, ya que los 12 tornillos
estaban tan altamente esforzados):
\~(X2 + y2) = 16(2.75)2 + 4(10.52 + 7.52 + 4.52 + 1.52) = 877.0
Rs = ~~ = 3.12 kips

\= 887.5(10.5) = 1062 ki R h 877 . tpS
R; = 1.012(2.75) = 2.78 kips
R =Y(2.78 + 3.12)2+ 10.622 = 12.15kips \< 0.7854(17.5) Correcta

Usense dieciséis tomillos A-325 de 1 pulg de diámetro.
Hállese el espesor de la placa para el aplastamiento (supóngase que es
adecuado el patín de la columna):
tp( I )(1.5 X 58) = 12.15kips
\- 12.15 _ O ul tp - 87(1) - .139 P g

Compruébese el aplastamiento de la placa a lo largo de la línea frontal de
los sujetadores y no se tenga en cuenta el aumento de 1/16 en el diámetro
del agujero:
h = 7 X 3 + 3 = 24 pulg M = 50(15) = 750 pulg- kips Fb = 22 pulg

t h3
Ip = ~2 - 2tp(IO.5 2 + 7.52 + 4.52 + 1.52) = 774tp

¡ = F, = 22 Me = 750(12)
Jb b + 1 774tp

750(12)
tp = 774(22) = 0.53 pulg

Se comprueba en el AISC, sección 19-1.2, que para elementos no atiesados
sometidos a compresión bit s 951..¡F;.

b 95 - \< -- = 15.8 t - y'36

15.0
t = 15.8 = 0.95pulg se usa '» = 1.0 pulg

<!-- p. 433 -->

REMACHES Y TORNILLOS SOMETIDOS A CARGAS EXCENTRICAS 433

Resumen: úsense diez y seis tornillos A-325 de 1 pulg de diámetro y una pla-
ca de ménsula con un espesor tp = 1.0 pulg.

8-5.1 Excentricidad reducida para conexiones, según el AISC

\
El método anterior de análisis de las juntas considerando la excentricidad tiene
amplio uso. Basándose en una serie de pruebas que demostraron que este método
de análisis de juntas es considerablemente conservador, el AISC usa (en las tablas
para diseño de grupos de sujetadores excéntricamente cargados, en el manual de
diseño) una excentricidad reducida, se calcula, para una sola línea de n sujetadores:

1 + 2n (8-6) 4

Para dos o más líneas de sujetadores, con n sujetadores en cada línea:

l+n
eef = e - -2-- (8-7)

Se notará que el uso de la ecuación 8-7 para la excentricidad del sujetador de
la figura 8-12c dará
1 + 5 eef = 3.625 - -2- = 0.625 pulg

Con esta pequeña excentricidad aparente (para el funcionamiento de la junta), es
fácil ver que la práctica establecida desde hace mucho tiempo de despreciar la
excentricidad en la mayor parte de las conexiones estructurales en las vigas, era un
ptocedimiento razonable de diseño.

Ejemplo8-7 Repítase el ejemplo 8-6 tomando en cuenta la exeentricidad re-
ducida.
k
e = 17.7)" 50
:en I •
\~~ I
O I • O I~15"- I 0; ,§ /" 1 e O 2.75 O I
\-c -ü O O I
\~, ~¡j I
\~ ~ O + O I -c f c.g. I
g O O I
I~ O O I
1 O .) I
Figura E8-7

<!-- p. 434 -->

434 CONEXIONES ATORNILLADAS Y REMACHADAS

SOLUCION Refiriéndose a la figura E8-7, se prueban doce tornillos de 1
pulg de diámetro.
1+6 eeff = 17.75 - -2- = 14.25pulg
M = 50(14.25) = 712.5 pulg. kips

\~(X2 + y2) = 405.75 (ejemplo 8-6)
s, = ~~ = 4.17 kips

s; = ;;~~5 (2.75) = 4.83 kips
Rh = 1.756(7.5) = 13.17kips
R + 4.83i + 13.172 = 15.95kips =y(4.17
15.95
I; = 0.7854 = 20.3 > 17.5 N.S.

Pruébense catorce tornillos de 1 pulg de diámetro:
8 eeff = 17.75 - "2 = 13.75pulg
M = 50(13.75) = 687.5 pulg, kips

\~(x2 + y2) = 14(2.75i + 4(92 + 62 + 32) = 609.9
s, = ~~ = 3.57 kips
D 687.5() . "v = 609.9 2.75 = 3.10 kips
Rh = 1.127(9) = 10.14kips
R + 3.10)2+ 10.142 = 12.14kips =y(3.57
1.v = 1.0(0.7854)12.14 = l.545 k SI. \< 17.5 Correcta

Con el uso de la excentricidad reducida se requieren dos tornillos me-
nos en la conexión. Aún es necesaria la placa con el espesor de 1.0 pulg pa-
ra satisfacer bit y el aplastamiento no es problema.

. El Manual de Diseño del AISC proporciona tablas basadas en una, dos y
cuatro columnas verticales de sujetadores, las cuales se pueden usar para diseñar
conexiones excéntricas. Se supone un número de sujetadores por fila, se hace el
cálculo de eef Ycon n y eef se obtiene un coeficiente que se multiplica por la carga
permisible de los sujetadores para tener la carga excéntrica total del grupo.Es po-

<!-- p. 435 -->

CONEXIONES DE LAS VIGAS A LOS MARCOS 435

sible deducir fácilmente una ecuación para la carga excéntrica permisible para
una sola línea vertical (u horizontal) de sujetadores. Estas ecuaciones aparecen en
varios textos, las que se pueden usar cuando se trate de reducir los esfuerzos de
cálculo al hallar el número de sujetadores de una conexión excéntricamente cargada. El autor sugiere que con el aumento de eficiencia de cálculo de que dispone
el diseñador con las calculadoras de bolsillo, es tan fácil "marcar en la calculadora" como tratar de usar una ecuación desarrollada por cualquier otra persona.
Esto es particularmente cierto porque no existe ninguna ecuación sencilla, y la
mayoría de las ecuaciones requieren de todos modos un poco de iteración.

8-6 CONEXIONES DE LAS VIGAS A LOS MARCOS
En las figuras 8-2a y8-15semuestran los métodos más usuales de estructurar el acero en los edificios pequeños de cinco pisos o menos, donde las conexiones son del ti-

(al (b)

(el (d)
Figura 8-15 Conexiones. (o) Conexión resistente a momento que usa angulares de tope y asiento atornillados al patín de la columna. Los angulares del alma soportan el cortante. Vista hacía abajo. (b) Conexión
resistente a momento en el alma de la columna. Nótese que las placas superior e inferior se sueldan al alma y patín de la columna para actuar como atiesadores de la columna. (e) Sistema de conexión de piso en
una estación de potencia. Nótense los atiesadores para cortante en el alma de la trabe principal. Se
muestra, en primer plano, el corte de las pequeñas vigas de piso. (d) Conexión de los largueros de puente.

<!-- p. 436 -->

436 CONEXIONES ATORNILLADAS y REMACHADAS

po 2 del AISC (conexiones a cortante simple). La excentricidad de 1cortante de la
viga se desprecia en estas conexiones, y se supone que no hay momentos que
transferir a través de la conexión. La estabilidad de la armadura se provee con el
uso de contravientos o muros de mampostería estrechamente unidos a las columnas, y que actúan como muros de cortante.
Algunas de las juntas de la figura 8-20, están "normalizadas" en lo que respecta al patrón de los tornillos y con una longitud de angulares que depende del tamaño de la viga, y que viene dado en el manual de diseño del AISC. Se selecciona el
angular basándose en el aplastamiento del tornillo y en las dimensiones de los lados para que den una distancia adecuada al borde y sin que haya interferencia
entre los tornillos y la llave mecánica durante la instalación, en el caso que los
agujeros de los tornillos se alineen tanto vertical como horizontalmente. El uso de
estas tablas proporciona a menudo una conexión sobrediseñada. Sin embargo, el
costo del sobrediseño está más que compensado por la reducción de los costos de
fabricación al utilizar dimensiones normalizadas.
Este tipo sencillo de conexión estructural se usa para conectar los largueros a
las vigas de piso, y las vigas de piso a las trabes, en la construcción de puentes. En
el diseño de puentes, se deben normalizar las conexiones para cada puente de terminal a fin de reducir los costos de fabricación; no es tan fácil efectuar una normalización general de todos los puentes.
'\
Ejemplo 8-8 Diséñese una conexión para una viga de piso W14 x 30 que se
apoyara en una trabe W18 x 50. La W14 x 30 soporta una carga uniforme
(viva + muerte) = 2.5 kips/pie y el claro es L = 18.0 pies. Usense las especi-
ficaciones del AISC, acero A-36, y tornillos A-325 de alta resistencia.

Wl8 x 50
t ; =0.355"

3" ¡ 1>

[w =0.27"
Figura ES-S

SOLUCION Se debe recortar la parte superior de la W14 x 30, como se
muestra en la figura E8-8, y con un par de angulares (uno a cada lado), pero se
observará que en algunos casos se puede usar un solo angular en un solo lado
del alma.
Con vigas que se conecten por ambos lados, es evidente que los tornillos
en las almas de tanto la trabe de piso como en la viga de piso estarán someti-
dos a doble cortante,

v = ~L = (2.5 + ~03)(18) = 22.77 kips

<!-- p. 437 -->

CONEXIONES DE LAS VIGAS A LOS MARCOS 437

Usese tornillos A-325 de 3/4 pulg, en una conexión de fricción.
Ptornillo = 15.46 kips, a doble cortante (tabla 11-7, SSDD)
En una W14 x 30:
N = 22.77 _
corto 15.46 - 1.47 se usan dos tornillos
N = 22.77 _
apl. 1.5 X 58 x 0.75 x 0.27 - 1.29 se usan dos tornillos
En el alma de una W18 x 50:
N = 22.77(2) _
apl. 1.5 x 58 x 0.75 x 0.355 - 1.96 requiere dos tornillos
_ 22.77(2) _
N corto - 15.46 - 2.95 se usan cuatro tornillos por simetría
Usese un angular en el alma, con una longitud de 6 pulg y 1 a determinar:
Para aplastamiento:
21(0.75)(1.5 x 58) = 22.77
t = 0.174 pulg
Para cortante:
2t(6 - 2(0.75)(0.4¡;;,) = 22.77
t = 0.176 úsese 1 =i pulg
Usese un angular con una longitud de 6 pulg. Dos L4 x 4 x 114 x 6 de lon-
gitud con dos agujeros punzonados de 0.82 pulg (3/4 + 1116) como en la
figura E8-8 - esto proporciona espacio libre adecuado para instalar los tor-
nillos.

Ejemplo 8-9 Diséñese las conexiones de una viga de piso en el puente que se
diseñó parcialmente en los ejemplos 4.15 y 10-5. Según las especificaciones
del AREA. Fy = 250 MPa. Usense tornillos A-325 de alta resistencia. F; =
138 MPa (tabla 8-5). Nótese que el AREA considera solamente conexiones
del tipo de fricción.

SOLUCION Del ejemplo 4-15, se obtiene
Vmuertr 28.3 kN
Vviva = 140.5 kN
V¡mp = 178.0 x 0.795 = 1l1.7 kN
Cortante total = 280.5 kN
La viga de piso es una W760 x 160.7 y se conecta con una trabe armada
(ejemplo 10-5):
twg = 16.0 mm twb = 13.8 mm

<!-- p. 438 -->

438 CONEXIONES ATORNILLADAS Y REMACHADAS

Se usarán tornillos de 22 mm de diámetro:
Ptorn = 0.7854(0.0222)(138)(103) = 52.3 kN

Para el alma de una W760:
280.5
NcortantT 2 X 52.3 = 2.7 Se usan tres tornillos (doble cortante)
Para el aplastamiento con los tornillos a doble cortante, Fb = 250 MPa
(tabla 8-5):
N _ 280.5 _ se usan los tornillos según se apl. - 0.022 X 250 X 13.8 - 3.7 requieran

Para el alma de una trabe armada [tornillos a cortante simple y Fb 185
MPa (valor del remache): tabla 8-51
,N = 280.7 = 4 31 se usan seis tornillos cortante 0.022 X 185 X 16 .
280.7
NaPIas. = 52.3 = 5.36 se usan seis tornillos

Colóquense los tornillos como se muestra en la figura E8-9.
W760 X 160.7 ..... \--16 W760

\~ 1--- Trabe + 127 x 127 X 19.0 o
\+ oo~l

\~ !

Figura E8·9

Diséñese el angular de conexión:
L = 5 X 3D + 2 X 1.75D = 18.5D = 18.5D = 407 mm, úsense 410 mm.
El espesor del angular estará controlado por el aplastamiento de los tres
tornillos en el lado sobresaliente (l.s.) que sujeta la viga a la trabe; por tanto,
1 ~ 16 mm.

2/(0.022)(3)(185) = 280.5
1 ~ 11.5mm
Buscando en las tablas, pruébese: Ll27 x 127 x 11.1 (tabla V-9):
g = 75 mm (tabla V-13)
Distancia efectiva al borde, de = 127 - 75 = 52 mm
d ~ 1.5D = 33 mm
e(requeridos)

<!-- p. 439 -->

SUJETADORES SOMETIDOS A TENSION 439

Un Ll02 x 102 x 11.1 no dará suficiente espacio libre entre los tornillos de
la W760 y los que atraviesan la trabe en ell.s. La pequeña cantidad de sobre-
diseñoes de despreciaren cualquier caso. El diseñose resumeen la figura E8-9.
Nótese que el AREA no requiere una comprobación de "aplastamiento"
usando tornillos A-325. Esta comprobación estableció el valor aproximado
de 1, y se recomienda se requiera o no. / / /

\~-7 SUJETADORES SOMETIDOS A TENSION

La figura 8-6 ilustra las condiciones usuales para los tornillos a tensión/Cuando
se aprieta el tornillo para desarrollar la carga de prueba, se alarga la espiga. Si-
multáneamente se comprimen las placas engrapadas. Cuando se aplica una carga
a la conexión, se tiene el cuerpo libre de la figura 8-16, que da
NT - aA - P aplicado= O (a)
o P = NT - aA (b)
Obviamente, según P se hace cada vezmayor, ocurren simultáneamente dos even-
tos:

l. La tensión T del tornillo aumenta ligeramente, lo que produce una ligera elon-
gación de la espiga.
\2. La elongación de la espiga reduce la presión de agarre de la placa, (1, puesto
\~ que la compresión de la placa, ep aTtp/ A"E es pequeña y se debe a que lp es
relativamente pequeña y A p relativamente grande. Por otra parte, e10rn =
\6. TL/AE es de una magnitud casi constante, siempre que las placas estén en
contacto.
En forma de ecuación, y considerando ahora un solo tornillo, como en la figura 8-16D, se tiene
\- aep = aepolt
ya que las dos placas engrapadas se expansionan y tomando P' = parte prorra-
teada del P total, aplicado a un tornillo:

(c¡ - P')2tp
\-ep = AE (e)
p
(d)
Además, C¡ = 1';, por estática:
P' + Ce = Te [también por estática (figura 8-16d)] (e)

<!-- p. 440 -->

440 CONEXIONES ATORNILLADAS Y REMACHADAS

1M

\~ ¡
Tic Tic
(a) lb)

aA p = e

a¡Ap=C¡ T¡t

\~
\~ p' p •
(e) td¡

Figura 8-16 Tornillos a tensión. (a) Conexión de momento en la viga; puede incluir cortante, así como
tensión. (b) Conexión del colgante con los tornillos en tensión pura. (e) Condiciones iniciales. (d) Ten-
sión final en el tornillo producida por P .

Con 2tp ::::::: Lb, y para E = constante,
C¡-Cf lJ-T¡ (j) Ap Ab
Sustituyendo los valores de C¡ y Cf de las ecuaciones (d) y (e), en la ecuación (j):
(T¡ - 1J + P')Ab
Tf-T¡= ( A
p

con alguna reordenación, se obtiene

P'
Tf = T¡ + 1 + A / (8-8) p Ab
Para espaciamientos comunes de g = 5.5 pulg y distancias al borde de 1.5 pulg,
el área tributaria para un tornillo en una conexión de este tipo es del orden de 10a
20 pulg 2. Para tornillos nominales con diámetros de 7/8 a 1 pulg, el área del tor-

<!-- p. 441 -->

SUJETADORES SOMETIDOS A TENSION 441

nillo es del orden de 0.7, tomando Ap/A b como aproximadamente (10 una estimación razonable y conservadora), se obtiene
P'
1J = 1'; + 1 + 10 = 1'; + 0.1P' (8-8a)
Sin embargo, nótese Quesi P se aplica directamente al sujetador, T¡ = Ti +
P', Yno como viene dado en la ecuación (8-8a). Cuando las placas se separan, no
hay C¡ en la ecuación (e), y un simple análisis de cuerpo libre de la figura 8-16d
dará
T¡ = Ti + P'

Refiriéndose a la figura 8-17a, se ve que los bordes externos de la conexión se
comportan un poco como vigas en voladizo. Puede que sea necesario tener en
cuenta esta "acción separadora" puesto que la fuerza Q mostrada disminuye la
capacidad de la conexión. Las pruebas indican que se deberá considerar Q si las
partes que forman la conexión son muy rígidas. Las pruebas también indican que
a menos que la conexión se atiese de manera adecuada, los dos sujetadores de
afuera de una conexión con más de dos líneas de sujetadores (figura 8-17b) no son
muy efectivas. Considerando un gran número de pruebas realizadas en la Universidad de Illinois y publicadas en el Structural Research Bu/letin No. 353, se han
propuesto las siguientes ecuaciones empíricas:

Para tornillos A-325:
l00b(D2) - 18L(tJ} ]
(8-9) Q = F [ 70a(D2) + 21L(tJ}
Para tornillos A-490
\2)
_ F[ lpob(D - 14L(t}) ] (8-10) Q - 62a(D 2) + 21L(tJ}

donde F = carga sobre un sujetador = PIN
a = distancia de la línea de sujetadores al borde del patín (pero a s; 21j)
b = ancho tributario del patín, como en la figura 8-17c
D = diámetro nominal del sujetador
L = longitud tributaria del patín para cada sujetador = LI2 para dos su-
jetadores, como en una conexión de cuatro tornillos.
Los patines de las vigas que soportan colgadores (ya sean del tipo del
ejemplo 8-10, o varillas de colgar, como en las escaleras) deben ser adecuados pa-
ra la carga. Si la carga es muy grande, el patín se deformará, a menos que se
atiese. Una solución propuesta por Dranger ("Yield Une Analysis of Bolted
Hanging Connections", AISC, Engineering Journal, Vol. 14, No. 3, 1977) da al-
gunas soluciones en términos de F; (y requiere el uso de un FC = 1.70 para obte-
ner las cargas de trabajo).

<!-- p. 442 -->

442 CONEXIONES ATORNILLADAS Y REMACHADAS

F Q
F+Q
P g

1 "
16
or
t.5 mm
Q Q !p
(al

(bl
l· L.1. L.,. "'--t
V -.
r9"l
p • (el 1p
(d)

Figura 8-17 Conexiones de los colgantes. (a) Sujetador con separación. (b) Suposición general para la flexión y la sección critica. (e) Longitud tributaria en un tornillo con separación. (d) Estabilidad del patín
con una carga en el colgante.

Para colgadores engrapados (como en el ejemplo S-lO):
Longitud larga de engrape: F;,t;L
p = 2b(LF) (S-II)
Longitud corta de engrape:
\~F (S-12) P = F;,tl (2r)!( 1 +¡)
Para varillas de colgar (vease figura S-17d y el ejemplo S-II), el menor de los
valores 2 1 1/2( a) P = F;,tb(2r) 1 + b Fe (S-13)

F~ (S-14) P = F;,tl[r(1 +¡)]1/2
donde los términos no definidos previamente en las ecuaciones (S-9) y (S-lO) Yla
figura S-17 son!.
P = fuerza total soportada por el patín en un lado del alma de la viga
r = relación de esfuerzos, definida como (Fy - Fb)/ Fy ; para el acero
A-36,

<!-- p. 443 -->

SUJETADORES SOMETIDOS A TENSION 443

r = (36 - 22)/36 = 0.3889
tb = espesor del patín de la viga que soporta la carga

Ejemplo 8-10 Diséñese un colgador usando una sección WT para una carga
que ha de soportar un par de angulares. Se usarán tornillos A-325 y acero
A-36; la carga es de 62.4 kips. La carga cuelga de la parte inferior de una viga
W33 x 221, como se muestra en la figura E8-lOa.

W33 X 20l

Figura E8·10b

Figura E8·10a

SOLUCION El diseño del colgador requerirá diseñar una WT lo suficiente-
mente grande para sujetar los ángulos que soportan la carga y seleccionar su-
ficientes tornillos del tamaño apropiado para soportar la carga a tensión.
Paso 1. Diseño de los angulares.
Supóngase que LIr no es crítico, y escójanse tornillos de 718 pulg.:

A g -- 2262.4 -- 2 .84 pug1 2
62.4 1 An = 29 = 2.15 pu g2

2.15 - 253 1 2 > A g - 0.85 -. pu g

Elijanse angulares que tengan cuando menos 1/4 pulg de espesor, de modo
que el aplastamiento no constituya problema. Pruébense dos L4 x 3 x 1/4
(con las patas más largas espalda con espalda):
A agujeros = 2[ 1/4 x (7/8 + 1/8)] = 0.50 pulg?
A sum = (3.38 - 0.50)0.90 = 2.60 > 2.15 requeridos Correcta

Paso No. 2. Número de tornillos para los angulares:
Atorn = 0.7854(0.875)2 = 0.601 pulg 2

<!-- p. 444 -->

444 CONEXIONES ATORNILLADAS y REMACHADAS
F; = 22 kip/pulg 2 (conexión de tipo de aplastamiento y rosca en el pla-
no de cortante)
N = 0.601 ~'~2 x 2 = 2.36 se usarán tres tornillos
Compruébese el aplastamiento:

Pb = 3(2 x 0.25 x 1.50 x 58) = 131 \< 62.4 kips Correcta

Obsérvese si el espesor del alma de la WT ~ 2 x tan!' no siendo problema el
aplastamiento y el cortante.
Paso No. 3. Diseño de la WT.
Este paso implica sencillamente el estudio de las tablas después de calcu-
lar un peralte aproximado que se base en las distancias al borde y el espa-
ciamiento de los tornillos en los angulares:

dT ~ 1.5 + 2 x 3 + 1.5 + k
\= 9 + k pulg
Pruébese una WTl2 x 47:
d = ]2.15 pulg bf = 9.065
tf = 0.875 tw = 0.515 k = 1.53pulg
dedge = 9.06\- 5.5 = 1.78 > 1~ (tabla 1.16.4, SSDD)
Peralte requerido = 9 + 1.53 = 10.53 \< 12.5 pulg Correcta
Compruébese el momento flector en el extremo del filete en el alma:

b = 5:} - 1~ = 2.6875 pulg

T = 6;4 = 31.2 kips

2.6875 ) M = 31.2( -2- + 41.92 pulg . kips
Fb = 0.75Fy = 27 kips/pulg-

S = Lt = L(0.:75)2 = 0.1276L

M
S=-r,
L = 0.1~~:~27) = 12.l6pulg úseseL = 12.5pulg

Estímese el número de tornillos para soportar la carga en el colgador. Usense
tornillos de 7/8 pulg de diámetro para el colador y conectar la WT a la viga:

<!-- p. 445 -->

SUJETADORES SOMETIDOS A TENSION 44S

62.4
N = 0.601(44) = 2.35
!18:875.L-W=~125"--l1--521" --l /WTl2X47

Figura E8-10e W
Usense, por simetría, cuatro tornillos. Además, los datos para una W33 x
201:

Paso No. 4 Compruébese la "acción separadora", usando la ecuación
(8-9):
F =4=62.4 156. ki ps
0= dborde= 1.78 > 2(0.875) usese a = 2(0.875) = 1.75 pulg
\= 156{ 100(2.69)(0.875)2 - 14(6.25)(0.875)2 }
Q . 70(1.75)(0.875)2 + 21(6.25)(0.875)2
\= IU kips
El posible momento en el tornillo es
MI = lU( 1.;5) = 9.71 \< 41.92 pulg • kips Correcta
F + Q = 15.6 + lU = 26.7 > 0.601(44) (= 26.44 kips)
Como este valor está solamente 300 lb/perno, por encima de lo permisible,
se considerará satisfactorio. Usese una WTI2 x 47 con cuatro tornillos
A-325 de 7/8 pulg, conectados en el patín de la viga W33 x 201.
L = 12.5 pulg
2 L4 x 3 x 1/4 con los lados más largos espalda con espalda
Paso No. 5. Compruébese lo adecuado del patín de la viga, sin usar
atiesadores.
tb = 1.15 pulg (tpatín de la W33 x 201) t.; = 0.715 pulg g = 5.5
pulg.
De donde b¡ - 5.5 15.745 - 5.5 _ 5 12 a = 2 = 2 -. pulg

<!-- p. 446 -->

446 CONEXIONES ATORNILLADAS Y REMACHADAS

b = g - tw - 1/8 = 5.5 - 0.715 - 0.125 = 233 1 2 2 . pu g.
Sustitúyase en la ecuación (8-12), ya que L es solamente 12.5 pulg, y la carga
de fluencia para cada lado del patín es
P = 36(1.15)2(2 x 0.3889)t(1 + ~:~~) = 61.1 kips
P' = 1~0 = 611.~1 = 35.9 kips > 6~.4 Correcta

Para esta carga, no se requieren atiesadores en el patín.

Ejemplo 8-11 Un colgante para una escalera se fija al patín inferior de una
viga de piso W410 x 59.5. La carga que soportará la barra de colgar se esti-
ma como 38.75 kN. F; = 250 MPa tanto para la barra como para la viga. Di-
séñese el colgante y compruébese si la viga puede llevar esta carga sin un
atiesador entre el alma y el patín.

SOLUCION Diseño de la barra:
3 m2 A = .!.- = 38.75 = O2583 X 10- F, 150 .
2
A D _ 0.9:43 ) e = O.7854(

Por ensayos, obténgase D = 22 mm (con 10 roscas125 mm), ó

24.747)2 3 3 X 10- m2 > 0.2583 Correcta Ae = 0.7854( 22 - -1-0- x 10- = 0.299

Verifíquese la viga para la fuerza de la barra. No se tenga en cuenta la
torsión producida por esta barra en solamente un lado del patín de la viga,
puesto que está situada muy cerca del extremo de la viga. Tómese el agujero
del colgante a la distancia normal de gramil de 88.9 mm para una sección
W410 x 59.5.
Además,
b¡ = 178 mm tw = 7.7 mm t¡ = 12.8mm = tb
b = 89 - 7; - 1.5 = 39.9 mm

a = 178; 89 = 44.5 mm

De la ecuación (8-13) e incorporando directamente FC = 1.7, se obtiene
P = 250(12.8)2(2 x 0.389)t/~ + 44.5/39.9) x 10- 3 = 44.95 kN

<!-- p. 447 -->

CONEXIONES SOMETIDAS A CORTANTE Y TENSION COMBINADOS 447

De la ecuación (8-14):

250(12.8)2[0.389(1 + 44.5/39.9)]!(10-3)
p = 1.7 = 19.8 kN \< 38.75 N.S.
Como 19.8 \< 38.75, kN, el patín de la W410 x 59.5 es demasiado delgado y
se usará una sección con un patín más grueso, o se reforzará el patín de esta
sección. Será aproximadamente tan económico usar una sección con un
patín más grueso.

/&-8 CONEXIONES SOMETIDAS A CORTANTE Y TENSION
COMBINADOS(

En la figura 8-18 se muestran varios casos de conexiones sometidas a cortante y ten-
sión combinados. Se observará que ~na conexión con una combinación de cor-

Atiesadores .....---n Sujetador angular

Angular de asiento

(a) (b)

p

\+
\+
\+

T
(c) (d)
Figura 8-18 Conexiones en las que los sujetadores están sometidos a cortante y tensión combinados. (a)
Conexión resistente al momento, que usa una WT y atíesadores de columna. (b) Conexión tipo 2 (sen-
cilla), o tipo 3 (semirrigida), Siseusa un angular, junto con angulares auxiliares, supóngase que carpa todo
el cortante. (e) Conexión de ménsula, que usa un par de angulares unidos por la espalda o una WT. (d)
Conexión de tipo corriente usada para contraventeo. Se puede usar un cable en lugar del angular mostra-
do.

<!-- p. 448 -->

448 CONEXIONES ATORNILLADAS Y REMACHADAS

tante y compresión será adecuadamente conservativa si se diseña, ya sea como conexión de fricción o de cortante. Es evidente que la fuerza de compresión sobre la
conexión aumenta la resistencia al deslizamiento, mientras que una fuerza de tensión tiende a disminuirlo.
Por lo general, un sujetador sometido a cortante y tensión combinados se
puede tratar de una manera algo semejante a la condición de viga-columna con
esfuerzos combinados. Esto es, los esfuerzos reales de cortante, Iv, calculados
sobre la base del área nominal del sujetador son
fv + 1, s f perm (a)

Se obtiene un mejor ajuste usando un cuadrante de la elipse de esfuerzo, ya que
Fperm tiene valores separados para tensión, F¡, Ycortante, Fv, que dan

(b)

60 \
\ \. 7.8 SO
A-325N,I apoyoconexión de 40 \ ....... p- .1 \1,,

"', 0. I ~
Conexión de G,\ ~t /.-\ ú-.:s- \<1\<11.:' 30 f- fricciónA-325con \J'
agujero estándar P \ ~2~23.7 para el tornillo o~..., 20

10 ~'\ \
O 1\ O 4 8 12 16 20 22

F~

Figura 8-19 Diagramas de interacción del cortante y tensión del tornillo, para el esfuerzo permisible.

El AISC sustituye esta elipse de esfuerzos por tres líneas rectas para' las conexiones de aplastamiento y una sola línea recta para las conexiones de fricción, como se ilustra en la figura 8-19. La ecuación general del AISC para el esfuerzo permisible a tensión en una conexión de aplastamiento junto con cortante es

<!-- p. 449 -->

CONEXIONES SOMETIDAS A CORTANTE y TENSION COMBINADOS 449

(8-15)
La tabla 8-7 da los valores de los factores C. La ecuación del AISC para cortante y
tensión combinados en una conexión del tipo de fricción se obtiene de la ecuación
(b) usando F¡ = TtiA b> donde se usa la carga de prueba del tornillo y se toma F ' v
\= Iv para obtener
F' ) (8-16) v - \< e 4 (1 _1,Ab1',
b
donde Tb = carga de prueba del tornillo, obtenida de la tabla 8-2
ftA b = fuerza nominal de tensión en el tornillo (ft = TIA b)

La ecuación de la AASHTü para los casos de esfuerzos combinados son las
mismas que las del AISC pero con alguna moderación y simplificación adiciona-
les, y donde, para las conexiones del tipo de fricción,
F~ ~ 13.5 - 0.221, ksi (8-17)
F~ ~ 93 - 0.221, MPa (8-17a)
y se obtiene usando un valor promedio de AbTí = 0.017 al considerar el área no-
minal de los tornillos de 314 Y718 pulg, y las cargas de prueba que se indican en la
tabla 8-2.

¡Tabla 8-7 Coeficientes de esfuerzos permisibles en los sujetadores para cone-
xiones a cortante y tensión combinados

AISC
Aplastamiento Fricción AASHTO
CI C2 C) C·4 Cs
Sujetador kips/pulg- SI kips/pulg- SI kips/pulg- SI

A-502, grado I 30 207 1.3 23 158 0.75
grado 2 38 260 I.3 29 200 0.75
Tornillos
A-307 26 180 1.8 20 138
A-325Nb 55 380 1.8 44 303 17.5 121
A-325Xc 55 380 1.4 44 303 17.5 121 0.555
A-449N 38.-¡d 27(J1 1.8 30 207
A-449X 38.7d 27(J1 1.4 30 207
A-49ON 68 470 1.8 54 372 22 152
A-49OX 68 470 1.4 54 372 22 152 0.604e

a Los agujeros normales, 1116 pulg (o 115 mm) mayores que el diámetro nominal del tornillo;
véase el manual del AISC (Sec. 1-6.3) para agujeros ranurados o sobre medida.
b N, roscas en el plano de cortante.
e X, roscas excluidas de cualquier plano de cortante.
d Para diámetros de tornillo mayores de If pulg (38 mm); Fu = 90 kíps/pulg- (629 MPa).
e Solamente se permiten cargas estáticas de tensión.

<!-- p. 450 -->

450 CONEXIONES ATORNILLADAS Y REMACHADAS

Para conexiones del tipo de aplastamiento la AASHTO usa:
F~ + (Csf¡}2 (8-18) sVf;
dondet, u JIson los esfuerzos actuales calculados y eses un coeficiente tomado
de la tabla 8-7.
Usualmente el AREA no tiene estipulaciones para sujetadores en cortante y
tensión combinados.
Ejemplo 8·12 Dada la conexión de cortante y tensión de la figura E8-l2,
¿cuál será la carga permisible P para la conexión entre la columna y la sec-
ción WT, usando las especificaciones del AISC, acero h = 250 MPa, y tor-
nillos A-325 de 25 mm de diámetro?

SOLUCION Supóngase una junta del tipo de aplastamiento con la rosca de
los tornillos incluidos en el plano de cortante.

De la tabla 8-7 (A-325N) se obtiene
CI = 380 C2 = 1.4 C3 = 303
Ab = 0.7854(0.025)(1&) = 0.4908 x 10-3 m2

Tornillos A-325
de 10-25 mm

P Figura 8-12

Hágase F( = 303 MPa, y hállese P basándose en las limitaciones del cortante
\1. = P sen 40 = 0.13ü94P
e 10(0.4908)
303 = 380 - 1.4(0.13ü94P)
P = 420kN

Hállese P basándose en el esfuerzo máximo de tensión.

<!-- p. 451 -->

CONEXIONES POR MOMENTO (TIPO 1) 451

P cos 40°
F, = 303 = 10(0.4908)
P = 1941» 420 kN úsese P = 420 kN
Verifíquese para P = 420 kN.
420
fv = 10(0.4908) = 85 MPa \< 150 MPa de la tabla 8-I.Correcta
F/ = 380 - 1.4(85) = 260 \< 303 MPa Correcta

8-9 CONEXIONES POR MOMENTO (TIPO 1)1

Las figuras 8-160 y 8-170 hasta e presentan conexiones de uso común en la cons-
trucción, usándose las figuras 8-160, y 8-180 y b para conexiones rígidas (o del ti-
po 1 del AISC) que usan sujetadores mecánicos. En la figura 8-18b (véase tam-
bién figuras 8-150 y b)se usa comúnmente tanto para conexiones simples (tipo 2)
como para semirrígidas (tipo 3).lLas designaciones de "simple" y "semirrígida"
para esta conexión se determinan hasta cierto punto por el espesor del angular su-
perior de sujeción. Para conexiones simples, este espesor del angular se limita a
menudo a 1/4 pulg (o 6.3 mm), de manera que el angular se pueda deformar de
modo tal que no se desarrolle momento alguno! La WT de la conexión de la figu-
ra 8-160 se puede diseñar similar a la del ejemplo 8-10. El angular de sujeción de
la conexión de la figura 8-16b requiere un diseño de flexión algo parecido a la WT

Viga

b/t S 95/VF; si L > N, se usatá N
L
R I 1"
N/2iT_~D:_---L~M-L..-=-,Tt

La distancia Xo = LI2 para algunos
diseñadores
Xo = N/2 para algunos
diseñadores

Figura 8-20 Secciones críticas y dimensiones en el diseño de angulares auxiliares (superior) y de asiento.
para usar en la conexión de las vigas a las columnas.

<!-- p. 452 -->

452 CONEXIONES ATORNILLADAS Y REMACHADAS

de la figura 8-180. En la figura 8-20 se muestran secciones críticas y suposiciones
para el diseño del angular sujetador y el angular de asiento.

Ejemplo 8·13 Diséñese una conexión semirrígida (tipo 3) para resistir la mitad
de la capacidad de una sección W460 x 74.4, como se muestra. Se usarán tor-
nillos A-325 de 25 mm de diámetro, acero Fy = 250 MPa, y las especifica-
ciones del AISC.

Figura 8-130

SOLUCION Datos de la sección W460 x 74.4:
205 Correcta d = 457 mm bJ = 190 mm \<
3 m3 'l = 14.5 mm tw = 9.0 mm S; = 1.46 X 10-

Supóngase que se usarán angulares en el alma, de modo que el angular de
asiento soporte solamente compresión debida al momento, y el angular de su-
jeción lleva solamente tensión.
Hállese la fuerza de tensión que ha de resistir el angular de sujeción (su-
póngase que Fb =0.6Fy = 150 MPa):
M = 0.5(0.6Fy ) X 1.46 = 109.5 kN . m
T = M = 109.5 = 2396 kN d 0.457 .
El número de tornillos a tensión en el angular de sujeción se basa en F¡ = 305
MPa y A b = 0.4908 X 10-3 m-

\= 239.6 = 16 se usarán dos tornillos N 305(0.4908) .

Obsérvese que es bueno no tener que usar más de dos tornillos, ya que las filas
adicionales tendrían una eficiencia considerablemente reducida. Refiriéndose
a la figura E8-13b, el número de tornillos necesarios para soportar el valor de
T en cortante, usando F; 150 MPa, será
N = 239.6 = 3.25 úsense cuatro por simetría
150(0.4908)

<!-- p. 453 -->

CONEXIONES POR MOMENTO (TIPO I) 453

¡~t::oT-J1 ti l~~o ~--.'-----.~Ili
1_ 65 "" 90 .."·k-F48' . ina I T=M/d

Figura S-l3b
i~ • •
Figura S·l3e

Diseño del angular. Tómese L -s bj = 190 a 205 mm --- úsese 200 mm. Se
usará un angular de lados desiguales con el lado más largo hacia afuera. El
lado más largo debe tener la longitud suficiente para colocar dos tornillos a
3D + distancia al borde + valor de g¡ de la tabla 1-13 del SSDD.
L ~ 28 + 75 + gl = 28 + 75 + 65 = 168 mm

Pruébese un L178 x 102 x 22.2 (refiérase a la figura E8-13c):

a = 50 - 22.2 = 27.8 mm
M = ~a = (239.6) 0.0~78 = 3.330 kN . m
S = ~2 = 200(0~222)2 = 0.01643 X 10-3 m2

F b = 0.75 F; debido al tipo de conexión, situación, y debido a la forma rec-
tangular de la sección transversal.

Fb = 0.75(250) = 187.5 MPa
3.3~0
lb = 0.01643 = 202.7 > 187.5

Como este es el angular de mayor espesor de este grupo. se va a la parte supe-
rior del grupo siguiente, ya que controla el espesor. No se debe hacer L >
205 mm, porque se extendería fuera del patín de la columna y además haría
dudoso el análisis de la flexión con un ancho muy grande y solamente dos su-
jetadores.
Pruébese L203 x 102 x 25.4 mm.
a = 50 - 25.4 = 24.6 mm
M = (239.6) 0.0~46 = 2.947 kN . m

<!-- p. 454 -->

454 CONEXIONES ATORNILLADAS Y REMACHADAS

3 rrr' s = 200(0~254)2 = 0.0215 X 10-
j¡ = 2.947 = 137 \< 187 MPa Correcta (y no servirá ningún
b 0.0215 ángulo con menor espesor)

Una comprobación de rutina a tensión muestra que la sección es adecuada.
Se pasa ahora a comprobar si es necesario usar un angular en el alma para el
cortante, ya que este angular es bastante grueso. Refiérase a la figura E8-13d
para las dimensiones críticas y otros datos para el análisis.

n = 275 kN

Figura 8-13d

Con 12 mm de espacio libre normal en el extremo de la viga, R = V actúa
con una excentricidad de

e = 203 ; 12 = 95.5 mm

Como este valor es tan grande y debido a que se usa el lado más largo hacia
afuera para proveer una longitud adecuada para dos líneas de tornillos, se pa-
sa a calcular la distancia N requerida para la viga y usar ese valor para deterrni-
nar el momento flector en el angular de asiento. Supóngase que la reacción es-
tá concentrada en N/2 a partir del extremo de la viga, para calcular el momento.
(N + k)twFb = R [Eq. (4-5)]
k = 27.8 mm tw = 9.0 mm
(N + 27.8)(0.009)(187.5) = 275
N = 135.2 mm
135.2
e = -2- = 67.6 mm
67.6 + 12 - 38.1 = 41.5 mm e' = e + 12 - k angu 1=ar
M = Re' = 275(0.0415) = 11.412» 2.947 kN . como se usó para el angular
superior

Esto no es satisfactorio aun cuandose supongaque elangular superiorsoportala
mitad del cortante; por tanto, se requieren angulares para el cortante en el alma.

<!-- p. 455 -->

CONEXIONES POR MOMENTO (TIPO 1) 455

(La conexión de momento que se muestra en la figura 8-18c, se puede
tratar de una de las dos maneras siguientes:
\1. Suponiendo tensión inicial en los tornillos (que siempre se desarrolla en
las conexiones con tornillos de alta resistencia).
\2. Sin suponer tensión inicial.
Estas dos suposiciones se ilustran en las figuras 8-21 y 8-22. Con tornillos de
alta resistencia, la suposición de tensión inicial en el tornillo permite a la co-
nexión actuar como una unidad elástica y se pueden calcular los esfuerzos
utilizando la ecuación usual de momentos, lb = Me!l, que es válida hasta
que se separen las placas de conexión. Como la junta nunca se diseña para un
momento lo suficientemente grande para separar las placas, el método
mostrado en la figura 8-21 es adecuadamente conservador para su uso en el
diseño. El método que se muestra en la figura 8-22 resulta necesario cuando
hay que diseñar o analizar una junta que use remaches, en cuyo caso no se
supone corrientemente que haya tensión inicial.
Nh r =~ fe > O. Las placas no
bh JI S se separan
s=-bll 2 6

Figura 8-21 Conexión de momento suponiendo tensión inicial en el tornillo.

\ Localícese el eje neutro
T¡ \ O O 11'
¿Al'¡= bh'2
O O '-- bh'3 \ 1=3 +¿A.l} O O
O O Cal culese' el I¡ de los tornillos: f l = IMe
O O Calcúlesef v N.A. Ty¡ Verifíquese la ecuación de interacción
O O + 11' = 11/6 a 11/7
O O .l

Figura 8·22 Conexión de momento, sin tener en cuenta la tensión inicial en el tornillo.

Ejemplo 8-14 En la conexión de ménsula que se muestra en la figura E8-14a,
se usa un pedazo de WT y dos pedazos de angular para hacer un asiento atiesado
de viga. Los sujetadores son tornillos A-325 de alta resistencia y acero A-36.
¿Es adecuada la conexión para el cortante y momento que habrá que resistir?
Usense las especificaciones del AISC.

<!-- p. 456 -->

456 CONEXIONES ATORNILLADAS y REMACHADAS

f-- ~ ~
\~_ O'M o-,.....; 1-- 11.20 "--1

1.5"

;"'1 o O .....V) -
x ,V) O O o- s-, 0;
?: ",. O O
1.5" O O

Figura 8-140

SOLUCION Supóngase una junta del tipo de fricción. Para tornillos de 7-8
pulg de diámetro, Tb = 39 kips/tornillo (tabla 8-2)

P 10(39) _ 232 ki 1 2 A = 15(11.20) -. ips/pu g

1O(~~:01) = 13.72 kips/pulg- I; =

s = b~2 = 11.2~(15)2 = 420.0 pulg"

M = 82.5(1.47 + 3.95) = 447.15 kips/pulg-

M 447.15 06 ki 1.t = 1.e = -S =--420 = 1. ips/pulg-

El diagrama resultante de esfuerzos se muestra en la figura E8-14b, la parte
rayada del diagrama MIS representa tensión debido al momento y que se de-

1.26> o 2.32

0.638

\+

3.38 Figura 8-14b

be soportar por los dos tornillos superiores:
0.638 3(11.20) 143 k" /t ·11 = 1.06 + T m X O 2 2 = . ips orm

<!-- p. 457 -->

FACTOR DE RESISTENCIA DE CARGA (DFRC) PARA DISEÑO DE CONEXIONES 457

F~ = 17.5(1 - = 17.5(1 - 1::/) = 11.0S \< 13.7 kips/pulg- N.S. At)

Será necesario rediseñar la conexión, usando tornillos o más grandes o más
largos. / / /

8-10 FACTOR DE RESISTENCIA DE CARGA (DFRC) PARA
DISEÑO DE CONEXIONES

La forma común de la ecuación DFRC para el diseño de conexiones, usando tornillos A-325 y A-490 de alta resistencia (y con el tamaño limitado al diámetro $;
1.5 pulg ) es
R; = l.l(l.lD + 1.4L)

Este valor se compara de la manera siguiente con la resistencia del sujetador o el
aplastamiento de placa a tornillo:

Conexión de tipo de aplastamiento:
\<p = 0.70
Conexión de tipo de fricción:
\<p = 1.00
Cortante y tensión combinados:
(Pu(cortante»2 + (0.6Pu.(tensiÓn) )2 S \<p(0.6Ab F J 2 \<p = 0.75
Aplastamiento de la placa sobre el tornillo:

Rn = 3tdFu (placa) \<p = 0.64
donde A b = área nominal del tornillo
Al = área a tensión del tornillo (en la zona de la rosca) [véase ecuación
(5-4)]
Fu = resistencia última (nominal) del tornillo (= 1 para juntas de solapa
a cortante simple)
m = número de superficies de deslizamiento (= 1 para juntas de solapa
a cortante simple)
p, = coeficiente de fricción (por lo general 0.35 para superficies libres de
la escoria del molino)

Ejemplo 8-15 Dada la conexión de la figura ES-I5, determínese si el espesor
de la placa es adecuado y hállese el número de tornillos A-325 de 20 mm,
usando una conexión de tipo de fricción, .v una conexión de tipo de aplasta-
míento.

<!-- p. 458 -->

458 CONEXIONES ATORNILLADAS Y REMACHADAS

r, =250 MPa t 12 mm
\

20 según se requiera t

Figura 8-15

SOLUCION
R.. = 1.1(1.1D + 1AL)
\= 1.1[1.1(45) + 1.4(75)] = 170kN
Comprobaciónde las dimensionesde la placa.
A n'f",,¡..Fy = 170 (véasesección 5-10)
A = 170 = 0.77272 X 10-3 m2
n 0.88(250)
AnepF" = 170 kN
A = 170 = 0.5743 X 10-3 m2
n 0.74(400)
A = 0.5743 = 0.6756 X 10-3 m2 \< 0.77272 no rige g 0.85
El Ag suministradoes
Ag = [ 120 - 2(23) ]0.012 = 0.888 X 10-3 m2 > 0.77272 Correcta
Hállese el número de tornillos requeridos en una conexión de tipo de fricción
(no se tolera el deslizamiento, pero nótese que después de que se deslicen las
placas, es necesario cortar los tornillos para que falle la conexión). Supónga-
se p. = 0.35 (libre de escoria del molino en la superficie de empalme).
0.9743)2
A, = 0.7854 ( D - -n- (pie lb seg) [eco (54)]

A, = 0.7854(20 - 0.24122 X 10-3 m 24i~47r=
Supóngase 10 roscasl25.4 mm para el tornillo de 20 mm de diámetro.

epRn = 0.7mpA,F" = 170 kN
m = 1 para cortante simple
0.70 X 1 X 0.35 X 0.24122 X 725 X N = 170 kN
N = 3.97 se usan cuatro tomillos

<!-- p. 459 -->

PROBLEMAS 459

Hállese el número de tornillos requeridos en una conexión de tipo de aplasta-
miento (se tolera el deslizamiento Yla falla de la junta es por cortante del tor-
nillo):
q,Rn = q,(0.625AbFu)N = 170 kN
2
X 10-3 m2 Ab = '1T: = 1\<Y = 0.31416 '1T(0.020rX
N = 170 = 1.71 se usan dos tornillos
0.70 X 0.625 X 0.31416 X 725
Compruébese el aplastamiento de la placa usando dos tornillos:
R; = 3tdFu q,= 0.64 Fu = 400 MPa
q,R,. = 0.64(3)(0.012 X 20)(400)(2) = 368.6 kN » 170 kN Correcta

La conexión es "segura" ya sea con dos o con cuatro tornillos. Selecciónese
el número basándose en la decisión final en lo que respecta al tipo de cone-
xión, "fricción" o "aplastamiento".

PROBLEMAS

8-1 Determínese la capacidad a tensión de la conexión que se muestra en la figura P8-I, usando tornillos A-325 y 3/4 pulg de diámetro. Fíjese el gramil para que la sección crítica neta sea un mínimo.
Determínese también el espesor mínimo de las cubreplacas hasta el múltiplo más cercano de 1/16
pulg. Se usarán las especificaciones del AISC y acero A-36. Usese una conexión de aplastamiento.
Respuesta: P = 159 kips.

0 ii O 11
O 11 O
11 o O 0 11 O O J
O 11 O 11
0n O 1
P-E- ~P
\=-------,~r'-
4 Figura P8-l

8·2 Determínese el número de tornillos A-490 de 22 mm de diámetro que se necesitan para desarrollar
la capacidad efectiva total de la conexión a tensión mostrada, usando un par de angulares y la placa de
conexión que aparece en la figura P8-2. Usese un espaciamiento de tornillos de cuando menos 3D. Há-
gase un boceto indicado del diseflo final de la junta, mostrando los tornillos requeridos, longitud, y
cualquier otra información crítica de diseño. Usense las especificaciones del AISC. acero de Fy = 345
MPa, y una conexión de fricción.

<!-- p. 460 -->

460 CONEXIONES ATORNILLADAS Y REMACHADAS

Véase SSDD

p o O
O O

,....::::.""""'::-- Según se requieran

Figura PS-2

S·3 Repitase el problema S-2, usando Fy = 250 MPa y las especificaciones de la AASHTO para la capacidad efectiva total de los angulares. Usense tornillos A-325 y una conexión a fricción.
Respuesta: lS tornillos, L = 610 mm, justamente por debajo del valor de L para que no haya reducción.
8-4 Repitase el problema S-2 para el equivalente pie-lb.seg, del par de angulares y una placa de conexión de 3/4 pulg, para una carga axial de 240 kips, acero A-36, y torníllos A-325 en una conexión de
aplastamiento.
Respuesta: Ocho torníllos de 7/S de diámetro.
S-SDado el empalme de viga de la figura PS-5, úsense las especificaciones de la AASHTO para a) Diseñar pernos y cubreplacas para la capacidad total de momento de la viga. Diseñar tornillos y placas
del alma para la capacidad total de cortante de la viga, Se usarán torníllos A-325 de 7/S pulg de
diámetro, para todas las partes empalmadas y acero A-36.
Respuesta parcial: M = 1950 pulg, kips, T = 107 kips.

Figura PS-S

8-6Diséñese la conexión excéntricamente cargada, de una ménsula, para la carga que se muestra en la
figura PS-6. Usense tornillos A-325 de 25 mm de diámetro en una conexión de fricción. Determinese el
espesor de la placa, tanto para aplastamiento como para rajadura a lo largo de la fila delantera de tornillos.

""",,"+-_-;j~ L según se requiera

Figura PS-6

<!-- p. 461 -->

PROBLEMAS 461

S-1 Determínese el número de colocación de los tornillos A-325 para una conexión de cable a una co-
lumna W360 x 314, como se ve en la figura PS-7. Supóngase cualquier dimensión de Tque seanece-
saria para producir el L disponible. Verifíquese la tensión en el alma de la T de manera que se use una
sección suficientemente grande. Supóngase que se reforzará el agujero de fijación del cable, de mane-
ra que no se limite la capacidad en este punto. Usense las especificaciones del AISC y Fy = 250 MPa
para la sección T.
Respuesta: 10 tornillos.

Figura PS-7

S·S Determínese la máxima P permisible para la conexión atiesada de asiento que se muestra en la fi-
gura PS-S, usando las especificaciones AISC y acero A-36, con tornillos A-325 de 7/8 pulg de
diámetro. Suponer que los angulares y la Tson adecuados para resistir las rajaduras, pero que se debe
verificar el aplastamiento, según se considere apropiado. Todas las lineas de tornillos de los angulares
están a las distancias normales de gramil, como se indica en la tabla 1-13 del SSDD.
Respuesta: 52.2 kips-

p
\- ----
1---- -
O O
O O
O O
O O
O O
es4 x 3t xt
Figura P8·8

S-9 Repítase el ejemplo 8-14 para doce tornillos A-325 de 7/S pulg de diámetro.
Respuesta: 12.
S-lO Repítase el ejemplo 8-14 para diez tornillos A-325 de 1 pulg de diámetro.
S-u Rediséñese la conexión del ejemplo 8-8 si la viga de piso de la izquierda no se estructura con la sección W18 x 50.
S-U Compruébese la conexión del ejemplo S-7, si se omiten los dos tornillos en el c.g. del patrón de tornillos. ¿Será adecuado el patrón?
Respuesta: Sí 10será.
S-13 Diséfl.ense los sujetadores para el miembro 9, que se estructura con la junta diseñada para el
puente de carretera del ejemplo S-3.
S-14Determínese la sección W410 que pueda soportar con seguridad la carga sobre la varilla de colgar en
la escalera del ejemplo 8-11.

<!-- p. 462 -->

462 CONEXIONES ATORNILLADAS Y REMACHADAS

8-15 Diséñese la conexión inferior para el miembro vertical 7 del puente de carretera, utilizando la sección del cordón inferior diseñada en el problema 5-28.
8-16 Repítase el problema 8-1, usando el DFRC.
Respuesta: Pu = 217 kips, N = seis tornillos de 3/4 pulg.
8.17 Repítase el problema 8-2 usando el DFRC.
8-18 Repítase el problema 8-5 usando el DFRC. Supóngase que la carga de 225 kN se compone de D
lOO kN YL = 25 kN. Verifíquese solamente el número de tornillos.
Respuesta: 16 tornillos con lOJo de sobresfuerzo.

<!-- p. 463 -->



<!-- p. 464 -->

(a)

(e)

Figura IX-l Soldaduras. La mayoría de las soldaduras estructurales (80 a 90 por ciento) son soldaduras de filete. a) Uso poco corriente de una soldadura a tope en un empalme de columna. Nótese que la
placa terminal inferior de la columna está soldada a tope a la misma, pero la placa superior tiene soldadura de filete. b) Placa de base de la columna soldada a filete a la columna. e) Soldaduras a filete.
Se usa una Te cortada como asiento de la trabe (vigueta de alma abierta). Nótese que la placa inferior
que suministra estabilidad lateral al patín inferior también usa soldadura de filete con la columna. La
viga, en primer término, a la izquierda, tiene angulares estructurales soldados a filete en el taller (atornillados en el campo al alma de la columna). Se puede ver en el elemento de asiento de la viga WT un
perno de erección 464 también utilizado para dar estabilidad estructural.

<!-- p. 465 -->

CAPITULO
NUEVE
CONEXIONES SOLDADAS

9-1 CONSIDERACIONES GENERALES

La soldadura es un proceso por el cual se unen piezas de metal, calentándolas hasta alcanzar el estado fluído o casi fluídas, con o sin aplicación de presión. Las primeras soldaduras (hace aproximadamente 3 000 años) implicaban el calentamiento de las piezas hasta un estado plástico para luego martillarlas hasta su unión (es
decir, con el uso de presión). Actualmente, se usa muy poco este tipo de soldadu-
ra, excepto en pequeñas operaciones locales de herrería que implican la reparación de equipos agrícolas y el herraje de animales. En la actualidad, la mayoría de
los equipos agrícolas se reparan usando métodos más modernos de soldadura
de gas o eléctrica.
La soldadura estructural es casi toda eléctrica, y se dispone de numerosos
procesos. Se usa poco la soldadura por gas (la palabra "gas" se usa aquí para
indicar el uso de una mezcla de gas/oxígeno para producir una flama muy caliente para calentar las partes y el material de relleno de la soldadura), pero el gas se
usa principalmente para dar forma a las piezas por medio del corte. Con equipo
para corte con gas, mecánicamente controlado, que se usa en talleres de fabricación, se pueden realizar cortes que se acercan a los cortes con segueta por su uniformidad.
Como ya se indicó, la mayoría de los tipos de soldadura usan corriente
eléctrica. La corriente se usa para calentar el electrodo hasta alcanzar el estado
líquido, y luego depositarlo como relleno sobre las superficies de contacto de las
dos o más piezas que se quieren unir. El proceso funde simultáneamente una parte del metal base (el metal que se quiere unir) en la superficie de separación, de
manera que el metal se entremezcla con el metal base y desarrolla continuidad del
material en la junta, cuando tiene lugar el enfriamiento. Si la cantidad de electrodo depositado es pequeña en relación con el espesor de las partes unidas, el proce-

465

<!-- p. 466 -->

466 CONEXIONES SOLDADAS

so tiende a ser poco confiable (es decir, ocurre una fusión insuficiente del metal
base de manera que la soldadura puede reventarse o no efectuar una junta
completa). Esto se puede evitar ya sea precalentando el metal base, o limitando el
tamaño mínimo de la soldadura. Cuando la operación de soldado tiene lugar en
un ambiente muy frío, puede que sea necesario precalentar las partes, espe-
cialmente cuando las partes son muy gruesas, de manera que un gradiente de
temperatura muy grande no puede desarrollarse en una tan corta distancia, tal
que los esfuerzos térmicos resultantes sean tan elevados que falle la zona de solda-
dura.

La soldadura eléctrica implica el paso de una corriente ya sea cd o ca por
medio de un electrodo. Manteniendo el electrodo a muy corta distancia del metal
base, que está conectado a un lado del circuito, se forma un arco al desarrollarse
esencialmente un "corto circuito". Con dicho "corto circuito" tiene lugar un flu-
jo muy alto de corriente, la que funde la punta del electrodo (en el arco) y el metal
base en las cercanías del arco. El flujo de electrones que componen el circuito
"lleva" el metal fundido del electrodo hasta el metal base para formar la junta.
Es necesario un cuidadoso control del tamaño del electrodo y la corriente para
producir una soldadura de calidad con suficiente calor para definir una adecuada zona de fusión mientras se mantienen a un minimo las salpicaduras del
electrodo.
El electrodo puede ser o bien el ánodo del circuito (+) o el cátodo (-). Es
más común que el electrodo sea el ánodo y la operación resultante se efectúa
usando "polaridad inversa". Cuando el electrodo de soldadura es el cátodo (- ),
el circuito usa polaridad directa. La mayoría de las soldaduras se efectúa usando
cd; si se usa ca como fuente de energía se transforma primero a cd.
Delos numerosos procesos de soldadura que existen, los siguientes son los de
uso más probable en aplicaciones estructurales.

\1. Soldadura de arco metálico protegido (SAMP). Este es el método más
usual de soldadura, que usa electrodos de barra. Loselectrodos están disponibles
en longitudes de 9 a 18pulg y están cubiertos de un material que produce un gas y
escoria inertes, cuando la corriente de soldadura funde el metal. Este gas rodea la
zona de soldado para impedir la oxidación (véasefigura 9-1a) lo que constituye un
factor crítico si es necesaria más de una pasada para darle a la soldadura el tamaño requerido. Como la escoria es más ligera que el metal, flota hasta la parte superior de la soldadura y se puede barrer con cepillo. En las pasadas subsiguientes,
es necesario barrer las pasadas anteriores para remover cualquier escoria, suciedad, u otro material extraño cuya presencia pudiera causar un defecto en la
soldadura. Este tipo de soldadura es el método que más se usa en el campo, cuando se usa un equipo de cd de soldadura. El tamaño mayor de soldadura producido en un solo pase, es alrededor de 5/16 pulg u 8 mm.
\2. Soldadura dearco metálico protegido con gas (SAMPG). Este método de
soldadura es el que se usa con mayor frecuencia para soldador en taller, donde se
usan electrodos sin cubrir en una unidad mecánica de soldadura. La unidad con-

<!-- p. 467 -->

CONSIDERACIONES GENERALES 467

trola el espaciamiento de los electrodos y la velocidad de soldado, y tiene una
fuente de gas inerte para proteger la soldadura de la atmósfera que la rodea.
\3. Soldadura de arco sumergido (SAS). Este método también se usa en ta-
lleres de fabricación. Se alinea la junta y se cubre con una capa de material en
gránulos fusible, que contiene agentes de aleación y de fusión, así como produc-
tores de gases inertes. El electrodo se inserta en el material granuloso, se produce
el arco, y tiene lugar la fusión del electrodo y el metal base. El calor fundéla capa
granulosa para formar la capa protectora de gas y obtener cualesquiera otros
efectos que se desee del material. Se barre luego la escoria para dejar expuesta la
soldadura.

Cubierta del electrodo
.---(+) Metal de aportación

Atmósfera protectora
Metal fundido

\~~~~~~~~~~~=7-- Profundidad de
penetración

\-----(-) (a)

Tubo de guia del
electrodo

Añádese escoria según se requiera
Electrodos
Baño de escoria fundida

Metal fundido
Tope enfriado por agua
Material solidificado de
soldadura

Soldadura terminada

Material base

/ Agua /

(b)
Figura 9-1 Dos de los métodos más comunes para soldar. a) Arco metálico protegido. b) Electroescoria.

\4. Soldadura de electroescoria. El proceso de soldado es muy similar al proceso de arco sumergido, pero usa una escoria electroconductiva que se mantiene
en posición entre las dos piezas de metal por soldar por medio de placas de reten-

<!-- p. 468 -->

468 CONEXIONES SOLDADAS

ción enfriadas con agua (véase figura 9-1b). El material de escoria se funde y se
pasa la corriente por el mismo para mantener en estado de fusión la escoria y el
material metálico de relleno. El relleno se obtiene del electrodo de soldadura,
el que pasa dentro de la escoria. Por lo general, el proceso seefectúa en un montaje
vertical, de manera que, según se funde el relleno, las placas de retención se ele-
van lentamente, dejando atrás la soldadura terminada y parcialmente enfriada,
la cual tiene una delgada cubierta de escoria que es necesario remover.
La soldadura de electroescoria se usa en el taller para soldar placas gruesas.
Ha tenido bastante aceptación en las obras de puentes, para soldar placas de tra-
bes con placas de piso. Se pueden soldar placas del orden de 20 a 450 mm por me-
dio de este proceso, utilizando sólo un pase.

9-2 ELECTRODOS PARA SOLDAR

Se dispone de una variedad de electrodos de manera que se puede hacer un ajuste
apropiado de la resistencia y características metalúrgicas del metal base con el
material de la soldadura. En las aplicaciones estructurales, la American Welding
Society, en cooperación con la ASTM, ha establecido un sistema de numeración
de electrodos, que clasifica a estos electrodos de soldar (o varillas) de la manera
siguiente:
Eaaabc

donde E = electrodo
aaa = número de dos o tres dígitos que establecen la resistencia última a
tensión del metal de la soldadura. En general, se dispone de los va-
lores siguientes:

60, 70, 80, 90, 100, 110, y 120kips/pulg-

415, 485, 550, 620, 690, 760, y 825MPa
b = dígito para indicar lo apropiado de la posición de soldado, que
puede ser plana, horizontal, vertical y sobrecabeza.
1 = apropiada para todas las posiciones
2 = apropiada para filetes horizontales y colocación plana del tra-
bajo
e = dígito que indica la fuente de corriente y la técnica de soldadura:
ca, cd polaridad directa, ca polaridad inversa, etc.
Por ejemplo un electrodo E7013 es un electrodo con Fu = 70 kips/pulg-, que se
puede usar en cualquier posición, con ca o cd, y con polaridad directa o inversa.
Para el diseño estructural, la información que interesa es saber si el electrodo
es E60, E70, E80, o lo que fuere. Usualmente las ferreterías tienen en existencia
electrodos E7014 y E6011 (para todas las posiciones de soldadura y para usar
corriente ca o cd; el 4 indica que se ha añadido un polvo de hierro al recubrimiento del electrodo, de manera que sea más fácil mantener el arco). En general, los

<!-- p. 469 -->

TIPOS DE JUNTAS Y SOLDADURAS 469

electrodos E70 son los que se usan más en el trabajo estructural, y son compa-
tibles con todos los grados de acero hasta F; = 60 kips/pulg-.

9-3 TIPOS DE JUNTAS Y SOLDADURAS

Se pueden usar diferentes tipos de soldaduras en aplicaciones estructurales que
incluyen, soldaduras de ranura, de filete, de tapón, de costura, de muesca y de
puntos. La mayoría de las soldaduras en aplicaciones estructurales son de ranura
(aproximadamente 15 por ciento de todas las soldaduras) y de filete (aproximada-
mente SO por ciento de todas las soldaduras). Las juntas básicas estructurales que
se muestran en lafigura 9-2 se pueden producir usando una o más de las soldadu-
ras que se indican en la lista anterior. La junta a tope se obtiene a partir de una
soldadura de ranura como se muestra en la figura 9-3a. Se considera que esta jun-
ta tiene una eficiencia del 100 por ciento, si se construye de manera tal que se ob-
tenga total penetración de la soldadura.

.9-3.1 Esfuerzos permisibles en la soldadura

Es probable que la juntaa tope sea la única juntaque estésometida atensión directa.
Los esfuerzos permisibles de tensión o compresión para el metal de la soldadura,
vienendados en la tabla 9-1. Losesfuerzos permisiblesde tensión o compresión para
el metal de lasoldadura se puedentambién tomar como 0.6 FY' pero con Fu(electrodo) a
60 (E60)o 70 kips/pulg- (ESO), los esfuerzos límites son los del metal base. La AWS
ha introducido cierta moderación al limitar aún más el Fy del metal base a 42
kips/pulg? para los electrodos E60 y a 55 kips/pulg- para los electrodos E70 en el
acero de grado estructural.

/

(a) (b)

(e) td ) (e)
Figura 9-2 Juntas estructurales básicas que utilizan soldaduras. a) Junta a tope. b) Junta de esquina.
e) Junta traslapada. d) Junta T. e) Junta de borde.

<!-- p. 470 -->

470 CONEXIONES SOLDADAS

Placa opcional
de respaldo

Junta de traslape

Placa de
respaldo opcional
MuescaJ
Filetes de esquina
en junta de doble T

Filetes de esquina
en junta T
Soldadura a tope de doble bisel que
requiera soldar por ambos lados
(al

Soldadura de filete entre angular y placa de conexión

(b)

Figura 9-3 Soldadura de ranura y filete en aplicaciones estructurales. a) Soldaduras de ranura usadas
en juntas a tope. b) Juntas de filete, usadas como se indican.

El esfuerzo cortante permisible para soldadura de filete está limitado a
r, = O.3Fu(electrodo)

en las especificaciones del AISC, pero es necesario siempre comprobar que haya
suficiente metal base para resistir los mismos esfuerzos cortantes. En general, el
esfuerzo cortante de la soldadura de O.3Fu(electrodo) producirá mayores esfuerzos
cortantes que el O.4Fydel metal base. Es por esta razón que el esfuerzo cortante del
metal base se debe siempre revisar respecto a las especificaciones que se usen.
El esfuerzo cortante máximo en el metal de la soldadura es el valor límite en
las conexiones en las que la soldadura esté sujeta a esfuerzos combinados de cor-
tante y tensión.

<!-- p. 471 -->

Tabla 9·1 Esfuerzos permisibles en las soldaduras según diversas especificaciones

Esfuerzo permisible
Tipo de soldadura Tipo de esfuerzo AISC AASHTO AREA

Ranura, con penetración Tensión o compresión,
total paralela o normal al
eje de la soldadura Igual que el metal Igual que el metal Igual que el metal
Ranura, con penetración Tensión o compresión, base" base" base"
parcial paralela o normal al Igual que el metal Igual que el metal Igual que el metal
Todas las soldaduras eje de la soldadura base base base
de ranura Cortante 0.30Fu(elecrrodo) 0.27Fu(elemodo) 0.35Fu(electrodo) -l
Soldaduras de filete" Cortante 0.30Fu(electrodo) 0.27Fu(e(ectrodo) 0.35Fu(electrodo) ~
Soldaduras de tapón y Cortante 0.30Fu(electrodo) 0.27Fu(e(ectrodo) 0.35Fu(electrodo) Vl
ranura ~

a El metal base tiene que ser compatible con el electrodo: por ejemplo, los electrodos E60 están li- .....ez
mitados a un metal base con Fy no mayor de 42 kips/pulg/ (290 MPa); los electrodos E70 para metal ~
base con Fy no mayor de 55 kips/pulgé (380 MPa); electrodos E80 para Fy no mayor de 65 kips/pulg'' Vl
(415 MPa).
b El esfuerzo cortante se puede limitar por el máximo esfuerzo de la cortante permisibleen el metal -\<st'"' base (Fv = 0.4Fy en las especificaciones del AISC; F; = 0.33Fy en las especificaciones de AASHTO;
F; = 0.35Fy en las especificaciones del AREA). ~s ~
Vl

". -.¡...

<!-- p. 472 -->

472 CONEXIONES SOLDADAS

9-3.2 Soldaduras de filete

La soldadura de filete que se muestra en la figura 9-4 tiene una sección transversal
aproximadamente triangular. Se debe tener cuidado al rellenar las dimensiones de
la garganta de una manera adecuada¡ como se muestra en la figura 9-4cJ En la
mayoría de los casos, se hacen iguales las dos patas de la soldadura, pero esto no
es necesario, y se pueden usar patas desiguales. Si se usan patas iguales para la
soldadura de filete, las dimensiones en la garganta representan el área mínima para cortante y se calcula como

T = D x cos 45° = D x 0.70711

donde T = dimensión en la garganta
D = dimensión nominal de la pata
La dimensión de la pata para soldaduras de filete, D, debe llevarse hasta el 1116
pulg o 1 mm¡

(a) t b)

Figura 9-4 Area crítica de cortante para soldaduras de mete. a) Soldadura de filetepara junta te. b) Soldadura de filete para junta traslapada. e) Dimensión en la garganta para área mínima de cortante.

'9-3.3 Soldaduras de tapón y de muesca
La soldadura de muesca (figura 9-5) es un tipo especial de soldadura de filete que
se usa a vecescuando es dificil obtener la longitud necesaria para desarrollar la re-
sistencia requerida a cortante en una junta traslapada. Las soldaduras de tapón
(figura 9-5b) ,se pueden usar para impedir el pandeo de las juntas largas trasla-
padas en compresión, o para conectar las placas superiores con las inferiores en
miembros armados. Se pueden usar ya sea en agujeros redondos o muescas con
extremos redondeados. Las especificaciones de la AISC cubren las dimensiones
de las soldaduras de tapón y muesca, como se muestra en la figura. Estas dimen-
siones aseguran agarre y transferencia de cortante adecuados después que el enco-
gimiento sustancial de la soldadura (contracción al enfriarse) haya tenido lugar.
Si se usa una soldadura de filete en una muesca (no se llena la cavidad de la mues-
ca, como sucede con las soldaduras de muesca o tapón) el diseño y dimensiones se
basan en los requerimientos de resistencia, como para las otras soldaduras de file-
te. Esto sucede porque la cantidad de metal fundido de la soldadura es mucho
menor y el encogimiento resultante es mucho menor.

<!-- p. 473 -->

TIPOS DE JUNTAS y SOLDADURAS 473

9-3.4 Tamaño mínimo de la soldadura
Las soldaduras deben tener un tamaño mínimo, basado en el espesor del metal
báse. Esto se hace para asegurar un calentamiento y enfriamiento adecuados del
área de soldadura, de manera que la soldadura y el metal base no se cristalicen y
tiendan a agrietarse o reventarse debido a la insuficiente fusión de la soldadura
con el metal base! Se usan como guía los valores del código lje la AWS, por.el
AISC y la AASHTü, y aparecen en la tabla 9-2.

'9-3.5 Tamaño máximo de la soldadura
El tamaño máximo de las soldaduras de filete a lo largo de los bordes de las partes
conectadas es:

Parte
pie lb seg, pulg SI, mm AISC y AASHTO
t s 1/4 t:s; 6 Usese D = espesor t de la parte
t » 1/4 t > 6 Usese D = t - 1/16 pulg, o t - 1 mm"

aA menos que se construya específicamente la dimensión de la garganta, para usar el valor to-
tal de t.
Cuando se usa el proceso de soldado con arco sumergido, es posible producir en
el taller de fabricación, un espesor específico de la garganta del filete, redondean-
do la soldadura de manera que
D :5 3/8 pulg se usa la garganta = D x 0.70711 (pulg)
D > 3/8 pulg se usa la garganta = D x 0.70711 + 0.11 (pulg)/
Si se quiere hacer esto, se debe tener cuidado de diferenciar entre la soldadura en

\~ 1 ¡ 1- =IIIIV l I
T s «
D ~ I +.¡(; redondeado
R~I R~I al siguiente valor mayor
impar de &," ,además {IV D$ e.SIw
tw ~ t52 pero cuando menos
518" para t/ 518" ¡'S>4w -1
w = lo mismo que D para soldadura de tapón
(al (b)
Figura 9·5 Especificaciones del AISC para soldaduras de tapón y de muesca. a) Soldaduras de mues-
ca. b) Soldaduras de tapón.

<!-- p. 474 -->

474 CONEXIONES SOLDADAS

el taller, donde se pueden controlar las dimensiones de la garganta, y la soldadura
en el campo, donde se obtiene la dimensión nominal.
El tamaño máximo de la soldadura se puede también ver limitado por la resistencia a cortante del metal base. Esto es particularmente cierto cuando los filetes de soldadura se extienden hasta el borde de la placa, o al ajustar D al espesor
de la placa;' En general, se tiene la siguiente ecuación para la evaluación del D máximo efectivo:

donde (31 0.3, 0.27, etc., del código apropiado para la varilla de soldar
(32 0.33, 0.4, etc., del código apropiado para el metal base

Tabla 9-2 Soldadura mínima

Dimensión minima de la soldadura de filete''
Espesor del metal base" AISC AASHTO

pie lb seg, pulg SI,mm pie lb seg, pulg SI, mm pie lb seg, pulg SI,mm
t ~ 1/4 t s 6 1/8 3 3/16 5
1/4 \< t s 1/2 6 \< t s 12.5 3/16 5 3/16 5
1/2 \< t s 3/4 12.5 \< t s 22 1/4 6 1/4 6
t > 3/4 t > 22 5/16 8 5/16c 8

8EIespesor del metal base es el de la parte más gruesa que se va a unir.
bNótese que el AREA no tiene requerimientos mínimos de soldadura.
cVeánse las especificaciones de la AASHTO para t > I( ~ulg o 38 mm.

w :s 8", o entie
soldaduras para
controlar la
flexión
transversal Si L \< 4D, se usa D' = LI4

Usese E L para desarrollar la carga
de tensión

AISC Sec. 1.17.4
Barra plana a placa de conexión

AISC Sec. 1.17.5
Dimensiones de las soldaduras intermitentes

<!-- p. 475 -->

DESGARRAMIENTO LAMINAR 475

AISC Seco 1.17.6
Juntas de traslape

AISC 1.17.7
Diversos remates

Figura 9-6 Especificaciones varias del AISC para conexiones soldadas. Como estas especificacionesse
encuentran en el Structural Welding Codeo de la AWS, se deben seguir en general por el AASHTO y el
AREA.

En la figura 9-6 se muestran algunas otras especificaciones del AISC, concernientes al diseño de conexiones soldadas en la construcción de edificios.

9-4 DESGARRAMIENTO LAMINAR

El desgarramiento laminar (figura 9-7) es un fenómeno que puede ocurrir en ciertas juntas soldadas. No ocurre con frecuencia debido a que requiere de varios factores:

Desgarramiento
t Penetración de la
Placa de respaldo soldadura
Dirección del laminado
\1. Junta deficiente: soldadura de grandes dimensiones
y tensión normal al eje de laminado
Desgarramiento

(a) 2. Junta mejorada: la tensión no es normal
al eje de laminado.

(b)
Figura 9-7 Desgarramiento laminar en el metal de una junta soldada. Semuestra también una solución
para reducir la posibilidad de que ocurra una desgarramiento laminar. a) Desgarramiento laminar en
el metal base. b) Geometría de la junta para reducir el desgarramiento laminar.

<!-- p. 476 -->

476 CONEXIONES SOLDADAS

\1. Tienen que haber grandes deformaciones relativas en el metal base (eldesgarra-
miento laminar no ocurre en el metal de soldadura). Estas deformaciones
tienen lugar en los lugares en que se presentan grandes esfuerzos localizados.
\2. La carga es generalmente perpendicular a la dirección de laminado del molino
que produjo el miembro por soldar. Las vigas soldadas a los patines de las co-
lumnas producen este tipo de carga sobre los patines de las columnas (pero no
sobre el patín de la viga).
\3. Tiene que haber restricción a la deformación en el metal base.

Si se impone una soldadura grande (o soldaduras por ambos lados) sobre
una pieza gruesa de metal base, puede ocurrir un desgarramiento laminar. El desgarramiento puede deberse a que las deformaciones por contracción producidas
por la operación de soldado, serán grandes y estarán restringidas. La restricción
puede desarrollarse de una soldadura en el lado más lejano, o del espesor del
miembro o de una combinación de ambas condiciones. Un considerable desajuste
entre el electrodo y el metal base en una soldadura a tope de penetración completa, tiende a aumentar la posibilidad de desgarramiento (es decir, por usar
electrodo E80 en vez de un E70 con metal base A-36). Un patín delgado yatiesado de una columna es susceptible también al desgarramiento laminar, ya que los
atiesadores del patín que se soldan al patín de la columna producen restricción.
Como métodos prácticos que se usan para evitar el desgarramiento laminar
se tiene: uso de soldaduras de filete, diseño de juntas que permita aliviar la deformación o usar cargas distintas de las normales a la dirección de laminado, y el orden
de las soldaduras para hacer mínimas las deformaciones por contracción. El
folleto del AISC "Commentary on Highly Restrained Welded Connections"
(AISC Engineering Journa/, vol 3, 1973) describe con algún detalle el desgarramiento laminar, y proporciona unas cuantas alternativas para las juntas, que se
pueden usar para reducir el desgarramiento laminar.

9-5 ORIENTACION DE LAS SOLDADURAS

Las pruebas de laboratorio efectuadas con juntas de pequeño a mediano tama-
ño muestran que las juntas topes no limitan la capacidad de la junta, cuando el
electrodo se ha "adaptado" al metal base. La orientación de los esfuerzos aplica-
dos no tiene efecto significativo sobre la resistencia de la junta a tope.
La orientación de los esfuerzos en las soldaduras de filete constituye un factor significativo en la resistencia última de la junta. Las pruebas (véase Butler y
Kulak, "Strenght of Fillet Welds as a Function of Direction of Load", Welding
Journa/, mayo, 1971) sobre algunas juntas que usan soldaduras de filete demuestran que las cargas en la soldadura de filete, perpendiculares al eje de la soldadura son aproximadamente 44 por ciento más fuertes que las soldaduras de filete cargadas paralelamente al eje de la soldadura. Este aumento en la resistencia
se puede atribuir al rezago del cortante en las soldaduras longitudinalmente cargadas, con mayores deformaciones resultantes en la soldadura (se prefiere en las
soldaduras de filete el término "deformación" al término "fluencia") en la cone-

<!-- p. 477 -->

CONEXIONES SOLDADAS 477

xión que está más cercana a la carga. Este aumento en la resistencia de la soldadura no se considera directamente en las especificaciones de diseño porque la dirección de la carga no es suficientemente confiable. Se considera indirectamente por
el AISC (Sección 1-17.7) al limitar el largo longitudinal de la soldadura para
barras planas. También se considera indirectamente en las juntas a solapa al requerir soldaduras de filete a lo largo de ambos extremos de la barra (AISC Sección 1-17.9).

9-6 CONEXIONES SOLDADAS

Las conexiones soldadas son a menudo más fáciles de construir que las conexiones atornilladas. Sin embargo, en las conexiones rígidas, la junta requerirá generalmente tornillos de montaje ya sea en las placas de montaje temporales (o
permanentes), o angulares para sostener las piezas durante la alineación y ajuste
para la soldadura.
En general, el diseño de una conexión soldada implica el proporcionamiento
de las partes, basándose en la sección bruta y en las soldaduras. Las soldaduras a
tope se diseñan por lo general para la resistencia a compresión (o a tensión) del
metal base. Los filetes y otras soldaduras a cortante se diseñan sobre la base de las
mínimas dimensiones en el plano de cortante y la resistencia permisible a cortante
de la soldadura.

Se debe notar que una soldadura a tope usada pararesistir un momento desarrolla esfuerzos.

Me J;, =- 1
dondelb se compara con el esfuerzo permisible a flexión del metal base.
. Si se usa una soldadura de filete en el mismo tipo de conexión (véase figura
9-8), el valor de lb se compara con el esfuerzo permisible a cortante de la soldadura.

Tornillo de
montaje
)M ------....' Placa de I )M
montaje jb
v (a) t

(b)
Figura 9·8 Conexiones de momento, soldadas. (o) Conexiones de momento, a tope. (b) Conexión de
filete.

<!-- p. 478 -->

478 CONEXIONES SOLDADAS

Ejemplo 9-1 Diséñense las soldaduras para la junta traslapada que se muestra
en la figura E9-1a, usando una barra plana y electrodos E60, Fy = 250 MPa,
y las especificaciones del AISC.
\~ P-j \ +mO
p~ : ,---1------rt------J~p
1S
12 Figura E9-lb
SOLUCION
Eficiencia de la junta = 100 por ciento
P = 0.015(150)(0.6;;,) = 337.5 kN
Usese D = 15 - 2.0 = 13 mm.
r; = 0.3 X Fu = 0.3(415) = 124.5 MPa
337.5
Lsoldadura = (0.013 X 0.70711)(124.5) = 295 mm \< 300 mm (2w) Correcta

Se usará una soldadura de 150mm en cada lado de la junta, como se muestra
en la figura E9-1b (apenas satisface el AISC, sección 1-17.4). Se usarán re-
mates de 26 mm en los extremos, según el AISC, sección 1-17.7.

D= 13
\~

\= 26 mm +I}SO mm•.t2D.l
f Fig. E9-1b

Pregunta: ¿Por qué no se usan 150mm de soldadura terminal y 75 mm a lo
largo de cada lado?

Ejemplo 9-2 Diséfl.ense las solduras para conectar un L4 X 3 112 x 114 a
una placa de conexión de 3/8 pulg como se muestra en la figura E9-2a. Usen-
se las especificaciones del AISC, electrodos E70, y acero A-36. Diséfl.ese para
carga estática y carga dinámica.
.-.------1

II 4"--1--.,"
p- ---+---- ~A

(1'=116"
Figura E9-la

<!-- p. 479 -->

CONEXIONES SOLDADAS ~9

SOLUCION Para carga estática

Aangular = 1.81 pulg-
P = 1.81(22) = 39.8 kips
Usese D = 3/16 pulg
F; = 0.3 x 70 = 21 kips/pulgCompárese la capacidad de la soldadura y el angular.
0.70711D(0.3Fu ) ~ ta(O.4F;,)
0.25(0.4 X 36) 3.6
D ~ 0.70711 X 21 = 14.84
\< 0242 (~ 3.9) - . 16
Usese D = 3/16 pulg
4 = (0.70711 ~9~~1875)(21) = 14.3 pulg úsese L; = 14.5 pulg

Se usará la soldadura de la figura E9-2b.

L2

39.8 4 X 2.78 I 4"
1.16

5.~5 r::JI
Figura E9·2b Figura E9-2c

Para la carga dinámica es necesario balancear la soldadura con respecte
al eje neutro del angular (AISC, sección 1-15.3). F w = 14.5 pulg, como ano
tes. Refiriéndose a la figura E9-2c, y colocando la soldadura a traves del res-
paldo del angular, para reducir la longitud de la junta, se tiene
L 1 + L 2 + 4 = 14.5
L 1 + L2 = 10.5
L 1 = 10.5 - L2
Tómese la suma de momentos alrededor del eje neutro del angular, de mane-
ra que se elimine P; además,
Pw = 0.70711 X 0.1875 X 21 = 2.78 kips/pulg
L2(2.78)(4 - 1.16) + 4(2.78)( ~ - 1.16) - L 1(2.78)(1.16) == O

<!-- p. 480 -->

480 CONEXIONES SOLDADAS

Cancelando PW' se obtiene
2.84L2 - 1.16L, = 3.36 (o)
Sustituyendo L, 10.5 - L 2, se obtiene
2.84~ - 1.16(10.5 - ~) = 3.36
L 2 = 3.89 pulg
Sustituyendo ~ = 10.5 - L, en la ecuación (o), se tiene
26.46 62 L, = -4- = 6. pulg
Comprobación: 6.62 + 3.89 + 4 = 4.5 pulg III

9-6.1 Conexiones rígidas de viga a columna

Las conexiones rígidas del AISC, Tipo 1 para vigas y columnas se pueden fácilmente fabricar con el uso de la soldadura. En la figura 9-9 se ilustran diversas conexiones de viga a columna, usando soldaduras.
En la mayoría de las conexiones rígidas es práctica común usar soldadura en
el alma, ya sea como un 'filete o en combinación con una placa o un angular para
soportar el cortante. Este diseño procede como si las soldaduras del patín no so-

00 W
Figura 9-9 Conexiones rígidas de vigaa columna. a) Vigassoldadas a tope con la columna. Nótese el uso
de los atiesadores del alma de la columna opuestos a los patines de las vigas. La columna está en el patio de suministros, lista para su montaje. b)Conexión rígida usando un angular de asiento soldado por
el tope (no se ve). Las soldaduras superiores para el elemento superior resistente a momento, se
pueden ver junto con las soldaduras que mantienen el angular de conexión a la columna para tomar el
cortante.

<!-- p. 481 -->

CONEXIONES SOLDADAS 481

portaran cortante y evitar usar los cálculos de esfuerzos combinados. Si el alma
de la viga soporta el cortante principal y los patines el momento, esta suposición
es razonable y funciona bien en la práctica.
En la figura 9-10 se ilustra un dibujo con el detalle de una conexión típica
de soldadura. Nótese que el uso de la placa superior para desarrollar el momento de
la viga, permite una más holgada tolerancia en el ajuste del espaciamiento de viga
a columna. La placa superior no debe soldarse en una zona de aproximadamente
Lo = 1.2 x el ancho de la placa, de manera que los efectos del rezago del cortante
no sea causa de altos esfuerzos locales y falla de la placa (o de la soldadura).
Puede que se requieran atiesadores, opuestos a los patines de tensión y/o
compresión de la viga que transmiten la carga a la columna. El resto de esta sección se ocupará de la determinación de la necesidad de tener que colocar atiesadores en el alma y patín de la columna.

Atiesadores según se requieran

\+ ~~
/ t
lh!

\---
}---

Placa o angular de montaje r--- l

(a)
Atiesadores según
se requieran. \ 1-() -1"= .- \\
\~g .~'Ü

(e)

Figura 9-10 Conexiones rígidas soldadas de viga a columna, que son de uso común. (O) Conexión rígi-
da. (b) Zona de esfuerzo en el alma de la columna; identificación de los términos usados en la ecua-
ción (9-1). (e) placa superior y soldaduras.

Refiriéndose a la figura 9-lOb, se puede tratar el alma de la columna, opuesta
al patín de compresión de la viga como una placa cargada en el borde. Usando la
ecuación (3-5) con Kc = 1.15 (tabla 3-2, caso 2, para una placa fija de borde
libre.), E = 29000 kips/pulgs, p, = 0.3, d¿ = 0.95d, YFcr = Fyc = Fy de la columna para tener en cuenta la posibilidad de que la columna use un acero Fy de
más alto valor que el de la viga, se obtiene

<!-- p. 482 -->

482 CONEXIONES SOLDADAS

de 183 -=--
tw VF::
Las primeras especificaciones del AISC redondeaban el 183 a 180. Los requerimientos corrientes del AISC vuelven a la ecuación (3-5); reordenando para obtener Per = Fer(Ae), donde el área efectiva del alma de la columna sometida a
compresión se toma como detw' se obtiene, por sustitución de valores

donde el término adicional (Fy /36)1/2 se usa para ajustarse a otros grados de acero. Un ajuste adicional del factor 33 400 para incorporar resultados experimentales (véase Chen y Newlin, "Column Web Strenght in Beam-to-Column Connections", Journal oiStructural Division, ASeE, ST9, septiembre, 1973)da
4100t~y;;
Pcr = d
e
Ahora bien, si se iguala Per a la fuerza de compresión en el patín de la viga (PbJ =
A¡fi) Yse considera de' se obtiene la ecuación corriente del AISC ecuación (1.15-2):

(pie lb seg) (9-1)

(SI) (9-lm)

donde PbJ = fuerza sobre el patín de la viga (a compresión)
F = 5/3 para cargas vivas y muertas, y 4/3 para cargas muertas + vi-
vas, + viento, kips o kN

tw = espesor del alma de la columna, pulg o mm

de = espesor requerido del alma de la columna, como d - 2k, pulg o
mm

F; = esfuerzo de fluencia del acero de la columna, kips/pulg- o MPa

Se requerirá un atiesador opuesto al patín a compresión si el de real de la columna, como se definió previamente, es mayor que el que viene dado por el lado derecho de la ecuación (9-1).

<!-- p. 483 -->

CONEXIONES SOLDADAS 483

Se requerirán atiesadores (para el alma de la columna), opuestos al patín a
tensión de la viga (véase figura 9-lOb y 9-15a) cuando:

Si se satisface esta desigualdad, como se muestra, (el lado derecho igualo mayor)
no se requieren atiesadores en la columna. Un método más conveniente para deter-
minar los requerimientos de atiesadores, es el de igualar

Con Pst = AstFtst, se obtiene

(9-2)

Esta es la ecuación usual del AISC para atiesadores de columna opuestos al patín
a tensión de la viga. Nótese que solamente será válida un área positiva para el
atiesador.
El patín de la columna debe ser del suficiente espesor para resistir, sin excesiva deformación, la fuerza a tensión del patín de la viga. Un análisis de la linea de
fluencia ha dado la siguiente ecuación:
P )1/2
tc! \< 0.4( F:~ (pie lb seg) (9-3)
tc! \< 12.7( ;:~)1/2 (SI) (9-3m)

Si el espesor tcl del patín de la columna es menor que el que viene dado por el lado derecho de las ecuaciones anteriores, se requieren atiesadores en el patín. Las
especificaciones del AISC requieren que cualesquiera atiesadores del alma o el
patín de la columna cumpla los siguientes criterios:

\1. A st ~ ecuación (9-1) si es que se puede aplicar esta ecuación.
\2. Ancho de ambos atiesadores + twc ~ 0.67bbl .
\3. Espesor del atiesador, t , ~ t bfl2 (además, se debe satisfacer la relación bit).
\4. Para vigas en un lado de la columna, los atiesadores sólo se pueden extender
una mitad del peralte de la columna.
\5. La soldadura que une los atiesadores a la columna debe dimensionarse para
que soporte los momentos no balanceados en cada lado de la columna.
\6. Para cumplir los requerimientos de tensión los atiesadores se han de soldar al
patín de la columna lo suficiente para tomar AstFyst (es decir, se usarán solda-
duras a tope de penetración total).
\7. Los atíesadores a compresión se han de soldar, o ajustar exactamente al patín
de la columna que esté opuesta al patín de la viga que suministra la carga de
compresión.

<!-- p. 484 -->

484 CONEXIONES SOLDADAS

Ejemplo 9-3 Diséñese la conexión a momento que se muestra en la: figura
E9-3a, usando electrodos E70, las especificaciones del AISC, y acero A-36.

' ; ~6.4k
11'\6 X 40
o~~:; J; 16.0\" '"1" 0'0' lrl ~ x....:r~,~
("1- 0- hl; 6.995"
_ 11 11 JI (1 ; 0.505"
3:~.!.:..:: S, ; 64.70 in"
r : :
Si se requiere] ~ ~ :L '" Perno de montaje Figura 9-30

SOLUCION Diseñando para la capacidad total a momento:
M = FbSx = 24 x 64.7 = 1552.8 pulg/kips

M - 1552.8 - 97 ki T - - e ------- ps d 16.01

Usese una placa superior que tenga 8 pulg de ancho en la soldadura de la co-
lumna y que disminuya a 3 pulg, como se ve en la figura E9-3b.

97
tp = 22 x 6 = 0.73 úsese una placa de 314 pulg

Tómese D para las soldaduras de filete como 112 pulg.
Pw = 0.70711(0.5)(21) = 7.42 kipsy'pulg
4 = ;~2 = 13 pulg y distribúyase como se muestra

L .\
Placa de 5/8 T _~=+=======::::¡

Figura9-3b

Calcúlese la longitud de la placa. Nótese que la placa tendrá que ser lo
suficientemente larga que permita colocar 5 pulg de soldadura para D = 0.5

<!-- p. 485 -->

CONEXIONES SOLDADAS 485

pulg. Además, tendrá que haber, cierta longitud entre el extremo, a fin de
producir una adecuada deformación. Por proporción:
L .5 - = - L = 8.33 pulg 2.5 1.5
1.2wprom + 5 = 1.2(5.5) + 5 = 11.6 úseseL = 12pulg
Para una compresión de 97, se usará una soldadura a tope de penetración to-
tal, usando la placa de montaje como placa de respaldo.
Para el cortante (figura E9-3c), úsese una placa con una profundidad de
12 pulg, en un lado.

Figura 9·3c

\~60~4F;, = 0.15 úsese una placa de 3/16 pulg tp = 12
SoldaduraD = 0.707112~.412 X 21 = 0.148pulg úsese3/16pulg

Compruébese si la columna necesita refuerzo (AISC, sección 1-15.5):
Pbf - Fyctw(tb + 5kJ
A st ~ F
yst
\= 97(5/3) - 36(0.29:~[0.505 + 5(1.25)J = 161.7 ~ 71.74 = 2.49 pulg2

Portanto, se requieren, un parde placas atiesadoras opuestasal patín a tensión.
Usense placas de 3 pulg de ancho (2 X 3 > 0.67 X 8).

3 x t X 2 = 2.49 pulg''
t = 2.49 = O415lPulg úsese una placa de 7/16 (t = 7/16 > 0.505 correcto) 2P) . 2

Revísese el patín a compresión:

41OOt~'¡;; 4100(0.295)3\1'36
dc(w) > p = 161.7 = 3.91 bf

<!-- p. 486 -->

486 CONEXIONES SOLDADAS

j(; 7 D=!...! 4 t o
f '---t-'

10 n Figura 9-3d

Como de es mayor que 3.91, se requieren también atiesadores de patín a
compresión. Se usarán los mismos atiesadores que para un patín a tensión.
Se soldan los atiesadores a la columna que ha de soportar 97 kips, y a través
de los extremos, hasta el patín adyacente a las cargas. El atiesador podrá te-
ner solamente la mitad del peralte de la columna, ya que el momento actúa
sólo en un lado de la columna. Debido al t wde la columna, se usará un atiesa-
dor de profundidad total, soldado a la columna por tres lados, lo que da L =
10.91 + 2(3) = 16.91 pulg.
97 D Id = = 0.193 pulg. so. (16.91 x 2)(0.70711 x 21)
Usese una soldadura de 1/4 pulg tanto en la parte superior como la inferior
de cada placa atiesadora. / / /

í 9-7 CONEXIONES SOLDADAS SOMETIDAS A CARGAS
EXCENTRICAS
Muchas conexiones producen soldaduras que están excéntricamente cargadas, co-
mo se muestra en las figuras 9-11 y 9-12. El diseño de estos dos tipos de conexión
RI Nosetenganen~ ~:;,~" o .2 mm
No se tenga en cuenta esta zona 'f cuenta los remates ri======4
I---el-- ... 1I\ \ ..... 4
\06\~
"O
R I--~ -
\~~ ~ CIlcgf
/
/
/
/
/
1/
2t e ( Rh(5L/6)(~j3 X 5L/6) =R('¡/~
Rh =54Rej\<25L 2) R, Rv=Rj~L
1 de la línea: L3/3 (con respecto a la base)
1 de la linea: L3/12 (con respecto al centroide)
Figura 9-11 Angulares de conexión de una viga excéntricamente cargada (veáse también la figura
2-12d).

<!-- p. 487 -->

CONEXIONES SOLDADAS SOMETIDAS A CARGAS EXCENTRICAS 487

tienen alguna similaridad en la manera de diseñarlos. El análisis de esfuerzos en la
soldadura implica usar el concepto de que el máximo esfuerzo en la soldadura es

donde R = fuerza o esfuerzo/unidad de longitud (o área). El valor de R; está limitado a -
s; -s Rpermisible

El concepto del uso del momento de inercia (o el momento polar de inercia) de
una línea se usa en el análisis de los esfuerzos en la soldadura.,

9-7.1 Angulares soldados para conexión de vigas

El diseño de los angulares para la conexión de vigas consiste en seleccionar un anguiar (o un par) para satisfacer el cortante. La fuerza máxima de soldadura para
el angular que conecta con el alma de la viga se obtiene calculando el momento
polar de inercia de la soldadura. Es posible, usando el momento polar de inercia,
calcular las componentes horizontales y verticales de la resistencia al cortante de
la soldadura, para equilibrar el momento producido por RI2 y la excentricidad
mostrada. Se calcula, de la fuerza R, un cortante vertical adicional, y la resistencia resultante de la soldadura es igual a la suma vectorial de estas fuerzas. La aplicación de estos diversos conceptos se ilustra en la figura 9-11, Y se usa en el
ejemplo siguiente.

En general, se usan angulares 4 x 3 ó 3 x 3 para la conexión por alma. Si se
usa una construcción toda soldada, con angulares de 4 x 3, el lado de 4 pulg se
debe usar sobre el alma de la viga para reducir la excentricidad de la soldadura a
lo largo del lado exterior del angular sobre el patín de la columna. Si el angular
se suelda al alma de la viga, y se atornilla en el campo al patín de la columna (o el
alma de otra trabe), el lado de 3 pulg se debe soldar a la viga y usar tornillos en el
lado de 4 pulg, de manera que haya un margen adecuado para montaje y distancia al borde.

Ejemplo 9-4 Diseñe las conexiones de angulares para una W18 x 55, como
se muestra en la figura E9-4a para una conexión simple por patín entre una
viga y una columna, la que soporta una reacción terminal de 55 kips, Usense
dos L3 x 3 x t pulg x 12 pulg de largo. Usense las especificaciones del
AISC electrodos E70, y acero A-36.

SOLUCION Para la soldadura en el alma de la viga, sitúese el eje neutro
como

\= 0.367 pulg (12 + 2 x 2.5)x = 2(2.5) 2iS x

<!-- p. 488 -->

488 CONEXIONES SOLDADAS

3
\~ WIgX55
r'¡- 4
c.g. 55
I-.~ k! .,;f
o
'Iii- 3

L-... Figura E9-4a -
Considérese solamente un lado, de manera que
R = ~ = 5~ = 27.5 kips

El momento polar de inercia es (I de la línea con respecto a la base = VI3):
3 3
; 2.133 ) Ip = t, + Iy = 11; + 2(2.5)(6)2 + 12(0.367)2 + 2(0.367
\= 144 + 180 + 1.62 + 6.49 = 332 pulgvancho de la soldadura
La resistencia a cortante de la soldadura
R 27.5 k' R, = L =17 = 1.617 ips/pulg

El punto 1 de la soldadura es crítico, por inspección (o trazando rayos desde
el c.g.)
M = Re = 27.5(3.0 - 0.367) = 72.4 pulg : kips
My 72.4(6) .
Rh = I = 332.1 = 1.308kips Zpulg
p
R" = 0.218x = 0.218(2.5 - 0.367) = 0.465 kips/pulg
R; = «0.465 + 1.617)2 + 1.3082)1/2 = (6.045)1/2 = 2.46 kipsy'pulg
D = 0.707112~~.3 X 70 = 0.165!pulg úsese 3/16 pulg de soldadura

Comprúebese la capacidad a cortante del alma:
2(3/16 x 0.70711)(21) s 0.39(0.4 x 36)
Para la soldadura en el patín de la columna (supóngase 114 ::5 ti \< 3/4: ¿por
qué?)
54Pel
Rh = 25L2 (delafigura9-11,refiérasetambiénalafigura E9-4b)
R = 54 x 55 X 3 = 2.48 ki s/ ul h 25 X 122 P P g
R" = ~ = 2~i5 = 2.29 kipsy'pulg (y despreciando los remates terminales
de2D)
\~ = (2.482 + 2.292)1/2 = (11.4)1/2= 3.38 kips/pulg

<!-- p. 489 -->

CONEXIONES SOLDADAS SOMETIDAS A CARGAS EXCENTRICAS 489

D = O.70~i~8X 21 = 0.227 pulg úsese una soldadura de 114pulg

;¡--1" (-1

3" Figura E9-4b

Compruébese el cortante en el angular:
0.70711(0.25 X 21) s la(O.4F;,)

\~ D Correcta la = 3.7114.4 = O. 257.m
Usese L3 x 3 x 5/16 x 12 pulg de largo. III

9-7.2 Angulares de asiento soldados a las vigas

El angular de asiento de la viga que se muestra en la figura 9-12 se ha de diseñar
para estabilidad a flexión y debe tener el suficiente espesor y longitud en sus lados
para que se pueda colocar un filete adecuado a lo largo de los lados verticales, para soportar el cortante y momento debido a la excentricidad de la reacción. El angular se revisa a flexión en el extremo del filete (distancia k de las tablas) como en
la figura 9-120. El esfuerzo permisible a flexión se toma como

ya que la sección a flexión es rectangular. Calculando el esfuerzo real a flexión
cotno f¿ = MIS = Fb, Ycon el módulo de sección S = btl6, el espesor requerido
para el angular se calcula como
6M )1/2
I ~ ( 0.75F;,b
Donde b = ancho del angular de asiento. El valor de t se obtiene por ensayos. Se
puede inicialmente estimar la excentricidad (suponiendo que la distancia k para
cualquier angular es t + 0.375 pulg o t + 9 mm) para obtener

N einicial = "2 + 0.5 - (1 + 0.375) pulg

<!-- p. 490 -->

4~ CONEXIONES SOLDADAS

N einicial =2" + 12 - (t + 9) mm
El espesor t real requerido para el angular es muy sensible al valor k, por lo que el
angular propuesto se debe comprobar con exactitud.

Ejemplo 9·5 Diséñese un angular de asiento para una viga y la soldadura pa-
ra las condiciones que se muestran en la figura E9-5a. Usese Fy = 250 MPa y
electrodos E70. Datos para una sección W410 x 59.5:

/L102 X 102 x 6.3
f / Atornillado en el campo

Jl'410 X 59.5

12 Tornillos de montaje
T
"V) L152XI02X¡
1-
Figura E9-Sa
59.5:
d = 407 mm bJ = 178 mm
tJ = 12.8mm t; = 7.7 mm k = 26.2 mm

SOLUCION N mínimo es
(N + k)twFb = R
R N= - k t; X r,
144.7
N = 0.0077 x 0.75 x 250 - 26.2 = 74 mm
Pruébese un Ll52 x 102 x 12.7 mm: k = 25.4 mm. Compruébese el espesor
en la punta del filete:
102 - 12 e = 2 + 12 - k = 31.6 mm (supóngase R, en la mitad de la
pata y no en NI2) M = Re = 144.7(0.0316) = 4.57 kN . m
Fb = 0.75J\<;, = 187.5 MPa
Usese el ancho del angular de asiento = 210 mm (b¡ = 178 mm).

<!-- p. 491 -->

CONEXIONES SOLDADAS SOMETIDAS A CARGAS EXCENTRICAS 491
6M)I/2 ( 6 x 4.57 )1/2 X 187 500 = 26.3 mm» 12.7 N.S. t = ( bFb = 0.210
Pruébese un Ll52 x 102 x 22.2: k = 34.9 mm.
e = 45 + 12 - 34.9 = 22.1 mm
6 X 0.1447 X 0.0221 )1/2 t = ( 0.210 X 187.5 = 22.1 :::: 22.2 mm correcta

Patín de la
columna

D = I~ mm

Figura E9-5b

El lector debe considerar la necesidad de los factores de conversión dentro
del radical de una raiz cuadrada para que las dimensiones sean correctas. No
se puede desplazar nomás el decimal, ya que está implicada la raiz cuadrada
de 1 000. Nótese también que el método para calcular la excentricidad de la
reacción es algo conservador comparado con el uso de la distancia N y su medición desde el extremo de la viga. No existe un total acuerdo entre los diseñadores sobre cómo se debe aplicar la distancia de N de la reacción en este
problema.
Usese un angular de asiento Ll52 x 102 X 22.2 mm. Diséñense las soldaduras (e ignórense, como es lo usual los remates terminales de 2D). El esfuerzo cortante debido a una carga directamente aplicada es
P 144.7
fv = 2L = 2 X 152 X De = 0.476De MPa

El esfuerzo cortante debido al momento es
2
M= Re 1.vm = MS S = 2DeL6
\1. = 6(0.1447)(45 + 12) = 1.071 MPa
vm 2De X 0.1522 X 1000 De

<!-- p. 492 -->

492 CONEXIONES SOLDADAS

Esfuerzo permisible en la soldadura 0.3 X 485 145.5 MPa
145.5 = 1.~72
e
De = 0.00805 m
D = De 8.05 0.70711 0.70711 = 11.38mm
Usese D de soldadura = 12 mm. Reviseseel ancho de asiento hasta W = 178
\+ 4 x 12 = 226 mm. El ancho del patín de la columna debe tener cuando
menos 250 mm (figura E9-5b). / / /

4 x 4 x 1/4 L:para la estabilidad lateral, 2 D (no se tenga en cuenta)
úsese para la soldadura el mínimoD \.

L
R
t" o 12mtn ( Suéldesea! asientoo atorníllese la viga
(b)

Sección por flexión. Fb = O.75Fy

(a)

Figun 9-12 Angular de asiento excéntricamente cargado. Se puede usar un angular superior auxi-
liar para la estabilidad lateral de la viga. (o) Situación critica a flexión para un angular de asiento.
(b) Posición de la soldadura de un angular de asiento. (e) Esfuerzos en la soldadura cubiertos por
la carga excéntrica del angular de asiento. (d) Uso de los angulares de conexión para cortante, y
los ángulos de asiento para el montaje. La viga es tan pesada que no se necesitan tornillos de
montaje. El angular de asiento se usa también para resistir el cortante.

<!-- p. 493 -->

CONEXIONES SOLDADAS SOMETIDAS A CARGAS EXCENTRICAS 493

9-7.2 Angulares de asiento atiesados

Cuando elespesorrequerido delasientoo ladistanciadeNseandemasiado grandes para
un angular laminado, esimprescindible usar un asiento atiesado. Esto sepuede hacer
con una sola placa como en la figura 9-13, pero más a menudo es un par de angulares o una WT, de modo que se puedan usar temporalmente tornillos de montaje
para mantener en su lugar la viga sobre el asiento. Como el atiesador del asiento
es una placa a compresión, el bit del borde sin apoyar debe satisfacer al AISC,
sección 1-9.1. Además, los esfuerzos de flexión del atiesador deben ser lo suficientemente bajos para que la placa no se raje. Como la placa atiesadora está soportando a lo largo de dos bordes, los esfuerzos de columna no deben ser críticos,
si los esfuerzos máximos a flexión no exceden el valor permisible. Naturalmente
que el espesor del atiesador debe ser cuando menos tan grueso como el alma de la
viga a la que le sirve de apoyo.
R R

\--]Fp¡erna atiesadora Soldadura construcción}
(a) alterna con
f--/----- tornillos ( b )
R

I I
\+ +
\+ +
\+ + ( e)
\+ +
\+ +

Figura 9-13 Asientos atiesados para vigas (se pueden usar o soldaduras o tornillos [en (b) y (e)].
(a) WT como asiento. (b) Dos angulares y una placa. (e) Dos angulares y una WT para secciones
mayores. Nótese la sujeción alterna, usando tornillos (o parte tornillos y parte soldadura).
Ejemplo 9-6 Rediséñese el ejemplo 9-5 si la reacción R de la viga aumenta a
210.5 kN.

WT

Figura E9·6a

<!-- p. 494 -->

494 CONEXIONES SOLDADAS

SOLUCION Como para el ejemplo 9-5 se usó la sección casi más gruesa,
considérese el uso de un asiento atiesado de viga, hecho con una WT, como
se muestra en la figura E9-6a.

R N=--k
twFb
210.5
0.077 x 187.5 - 26.2 = 119.6 mm

Usese N = 120 mm:
N 120 -=-=60mm 2 2

Usese el alma de la WT que sea tan grande como para la W140 x 59.5 (7.7
mm). Además,

Después de analizar la tabla V-18 (SSDD), pruébese una WT180 x 118.3.

b¡ = 395.4 mm t¡ = 30.2 mm
tw = 18.9 mm d = 190.2 mm

Hállese la máxima dimensión D de la soldadura para cortante en el alma de
la WT con una soldadura a cada lado.
2(0.70711D x 0.3 x 485) = tw(O.4 x 250)
100tw
D = 205.8 = 9.19 mm> 8 como mínimo para t¡

Compruébese el esfuerzo de flexión en la WT (usando solamente el alma):

21O.5~:O+ 12) = 15.16 kN . m M = 210.s( ~ + 12) =
j¡ = 6M = 6(15.16) = 132.9 MPa \< 150 Correcta
b twd2 18.9(0.19022)

<!-- p. 495 -->

CONEXIONES SOLDADAS SOMETIDAS A CARGAS EXCENTRICAS 495

Diséñense las soldaduras: pruébese una soldadura como la que se muestra en
la figura E9-6b.
2(160 + 175 + lOO)y = 2(175)( 1~0) + 2(100)(80 + 30.2)
50040
Y = 870 = 57.5 mm
1~~ ) + 2(160)(57.5)2 + 2(175)(80 - 57.5)2 t, = {2(

\+2(100)(80 + 30.2 - 57.5)2}De

\= 2.4733De X 10-6 m"
2.4733De 2.4733 -3 3
Sarriba= e, = 52.7 = 0.0693De X 10 m

_ 2.4733 _ -3 3
Sabajo - 137.5 - 0.0180eDe X 10 m

Figura E9·6b

Esfuerzo cortante debido a la carga:
\1. - 210.5 _ 0.242
v - 870De - Ji;
Esfuerzo cortante debido al momento:
\1. = M = 15.16 = 0.842
vm S 0.180De De
f;m)I/2 Rv = (J; +
Rv-_ [( --0.242)2 + (0.842-- )2] 1/2 =--0.876 De De De
Igualando R; al esfuerzo cortante permisible y resolviendo para De:
0.~76 = 0.3 X 485 = 145.5
e

<!-- p. 496 -->

496 CONEXIONES SOLDADAS

D 1.006 e = 145.5 = 0.00602m
De 6.02
D = 0.70711 0.70711 = 8.51 mm \< 9.19 Correcta
Usese D = 9 mm.
III
9-8 PLACAS SOLDADAS PARA BASES DE COLUMNAS

Por lo general, las placas de base para columnas se soldan a la columna en el
taller antes de enviarlas al sitio de la obra. En la figura 9-14semuestran diversas si-

(a) (b)

td ¡

(el

Figun 9-14 Ejemplos de placas de base para columnas. (a) Placa de base de columna, fijada a la mis-
ma en el patio de fabricación. (b) Placa de base de columnaque se fija a la misma con angular y torni-
llos. Nótese el buen ajuste entre la columna y la placa de base. La pieza de madera alrededor de la pla-
ca de base actúa como valla retención para la lechada que se usa para alinear con exactitud la placa de
base sobre la cimentación. (e) Placa de base de columna, en su lugar, enlechada y nivelada. Nótese la
placa soldada a la columna para sostener el angular de contraviento. (ti) Croquis de la fotografía de
(b) mostrando el uso de la soldadura. (e) Forma alterna para (d) cuando haya momento en la columna.

<!-- p. 497 -->

PLACAS SOLDADAS PARA BASES DE COLUMNAS 497

tuaciones que usan placas de base en las columnas. La placa de base se puede soldar a la columna con soldaduras a tope o de filete. Por lo general, la decisión la
toma el fabricante, basándose en consideraciones económicas. La placa de base
se punzona previamente con agujeros para los pernos de anclaje, para fijar la columna a la cimentación. Cualquier otra configuración que sea diferente de ésta
(como en la figura 9-14d y e) requiere fabricación adicional. El diseño general de
las dimensiones de las placas de base (ancho x longitud x espesor) es como se
indica en la sección 6-6.
Ejemplo 9·7 Diséñense las soldaduras de filete y rediséñense los pernos de
anclaje para incluir la fuerza axial de la columna para reducir la tensión en
los pernos de anclaje de la placa base diseñada en el ejemplo 6-9 (véase figu-
ra E9-7a). F; = 250 MPa, úsense electrodos E70, y F; = 485 MPa.

SOLUCION Usese soldadura de filete para la unión entre la placa de base y
la columna, de manera que no sea preciso recortar por debajo el extremo de la
columna, para una soldadura de penetración total. Diséñense las soldaduras
de filete para esfuerzos de columna.

M P (para el lado a tensión, que es crítico, con razonable
J;, = -- - - aplastamiento sobre la placa de base en el lado a Sx(COl) A compresión)

670 kN

W310 X 110.1
s, = 1.84
A=14.06
If=19.9mm
bf = 256 mm 265+ilJ 1
Figura E9-7a

Para este esfuerzo sólo se requerirá una mínima soldadura de filete. Pruébe-
se una dimensión mínima de soldadura (AISC, Sección 1-17.2) de 8 mm ya
que la placa de base de 50 mm es mayor de 20 mm.
La fuerza de tensión en el patín es
25.2(A¡} = 25.2(19.9)(0.256) = 128.4kN
La resistencia de la soldadura de filete es (usando solamente un filete en un
lado del patín):
t; = 8(0.70711)(0.3 x 485)(0.256) = 210.7 kN > 128.4 Correcta

<!-- p. 498 -->

498 CONEXIONES SOLDADAS
Rediséñense los pernos de anclaje usando F, = 345 MPa.

Se probarán dos pernos de anclaje roscados de 32 mm de diámetro (n =
o filetes de rosca125 mm). Con los filetes, el área neta a tensión es
Ae = 0.7854( D - ~.9743 ) (unidades pie lb seg)

\= 0.7854(32 - 24.;47) x 10- 3 = 0.6563 X 10- 3 m

Tómense momentos con respecto a la línea de pernos en el lado a compresión
de la columna.
M = 2(0.6 x 345)(0.6563)(0.570) = 154.9kN . m
El esfuerzo resultante, obtenido por la superposición del perno de anclaje re-
sistente sobre el sistema dado de esfuerzos, resulta ser

\= _ p + M carga + JW;ornillo q A - S S
q = 1670 + 6(265) + 6(154.9)
0.780(656) - 0.656(0.78\<Y) - 0.656(0.78\<Y)
Ajustando para unidades consistentes, se obtiene para el lado de tensión de
la placa de base, el esfuerzo
q = -3.264 + 3.984 - 2.329 = -1.609 MPa (compresión) Correcta

Figura E9-7b

Nota: Los pernos se aprietan a que ajusten sin holgura. Cuando el momento tiende a separar la
placa de la cimentación, los pernos desarrollan resistencia para mantener el sistema en su lugar.
La tensión real en el perno será solamente la necesaria para producir un estado de cero esfuerzo
en el lado a tensión de la placa de base, más cualquier residuo a compresión resultante de apretar
las tuercas durante la instalación.

Resumen: Usese una placa de base de 780 x 656 x 50 mm. Se usarán cuatro pernos de
anclaje de 32 mm de diámetro, con acero Fy = 345 MPa. La soldadura de filete de 8 mm, secolo-
cará a lo largo de los patines de la columna, como aparece en la figura E9-7b, / / /

<!-- p. 499 -->

CONEXIONES SOLDADAS PARA PLACAS DE EXTREMO 499

9-9 CONEXIONES SOLDADAS PARA PLACAS DE EXTREMO

Una conexión usual de viga a columna por momento, utiliza una placa soldada a
la viga y atornillada a la columna en el campo. Cuando se use una soldadura a tope con un electrodo compatible con el metal base, los esfuerzos de flexión están limitados por el esfuerzo permisible a flexión en la viga. Cuando se usen soldaduras
de filete, se deben tener en cuenta los esfuerzos cortantes en la garganta de la soldadura, los que generalmente regirán el diseño. Se ilustra con un ejemplo el proceso de diseño, basado en investigaciones recientes y propuesto por Krishnamurty
("A Fresh Look at Bolted End-Plate Behavior and Design", AISC Engineering
Journal, Vol. 15, No. 2, 1978).

tb)

Figura 9-15 Placa soldada entre viga y columna. (a) Placa terminal de la viga, conectada al patín
de la columna. Nótese el uso de atiesadores en el alma de la columna. (b) Uso de una placa solda-
da a los bordes del patín para proporcionar anclaje a la placa terminal de la viga.

Ejemplo 9-8 Diséñese la conexión interior de viga a columna' para el
miembro 15 del ejemplo 2-4. La salida de la computadora muestra que LC-l
(gravedad + viva) controla, y los valores son los que se muestran en la figura
E9-8a. La sección tentativa de la viga usada en el ejemplo 2-5 era una W410
x 59.5. Usese F; = 250 MPa, electrodos E70 para la soldadura de la placa, y
tornillos A-325 para el montaje en el campo.

A 3'S
¡~ldadura Í/
39.5 kN/m

6.5 m

115.6 141.1 kN

Figura E9-8a

<!-- p. 500 -->

500 CONEXIONES SOLDADAS

SOLUCION Otros datos:
W200 x 46.1 (columna): W410 x 59.5:
d = 203 mm d=407mm
bf = 203 mm bf = 178mm
tf = 11.0mm 'r = 12.8mm
tw = 7.2 mm tw = 7.7 mm
Paso No. l. La fuerza en el patín (usando el mayor momento en el lado
derecho) es
F = ~ = 140.64(1000) = 357 kN
f d - tf 407 - 12.8
Paso No. 2. El área aproximada de los tornillos/fila, usando la
ecuación que se dio en el artículo citado y con 8 tornillos A-325 de 22 mm de
diámetro.

fs = ~ = 14;.8 = 17.7kN/tornillo~46.6MPa

O.5Fj
a=--
Ftb
Ftb = 380 - 1.4(46.6) conexión de aplastamiento
\= 315 MPa
3 m2 a = 0.53(~~7) = 0.56667 X 10-

Usando el diámetro nominal y dos tornillos de 22 mm de diámetro en cuales-
quiera de las dos filas superiores, el área suministrada es
Aj = 4(0.7854)(0.0222)(103) = 0.7603 x lO-3m2 ::::; 0.56667 Correcta

22mm
Filete de
10mm

Figura E9-8b

<!-- p. 501 -->

CONEXIONES SOLDADAS PARA PLACAS DE EXTREMO SOl
La distancia al borde, de ~ 1.75 X 20 = 35 mm. Se usarán 55 mm, como en la figura E9-8b, y un gramil normal de 90 mm (aproximadamente) en
la columna.
Paso No. 3. Diséñense las soldaduras de filete para soportar la fuerza j',
en el patín.
0.178(2D x 0.70711)(0.3 x 485) = 357 kN
D = 9.74 úsese 10mm
Colóquese la soldadura de filete en las partes superior e inferior de ambos pati-
nes. Usese un filete de 10 mm en el alma, para resistir un cortante de 141.1
kN. La capacidad efectiva de la soldadura es
Pso1d. = (407 - 2Ij)(0.70711 X 10 X 145.5) = 392 kN > 141.1
Palma = (407 - 2Ij)(0.0077)(0.4 X 250) = 294 kN > 141.1 Correcta -controla
Paso No. 4. La distancia efectiva entre los tornillos, basada en la dis-
tancia real PI' a partir del patín de la viga y del diámetro del tornillo, db = 20
mm y el D de la soldadura efectiva:
Pe = Pj - ~db - 0.70711D
\= 40 - 0.25(20) - 0.70711(10) = 27.9 mm
Paso No. 5. El momento efectivo de la placa, tomado como una sec-
ción WT es
M = Pe = 357(°4°279) = 2.49 kN . m Fj:

Paso No. 6. El coeficiente de material, basado en los esfuerzos de
fluencia de la placa, tornillo (Fab), Yesfuerzo permisible en el tornillo, F;b, se
calcula como
F )0.4( F )0.5
Ca = 1.29( F: 0.7~bF;, b
Fub = 825 Mpa (parte inferior de la tabla 8-1 para un diámetro del
tornillo \< 25 mm)
250 )0.4( 315 )0.5
Ca = 1.29( 825 0.75 X 250 = 1.04

Paso No. 7. Calcúlese un factor de corrección del ancho para la placa,
basándose en el ancho del patín de la viga, b¡, y el ancho de la placa, bp :
bj )0.5 ( 178)0.5 Cb = ( b = 200 = 0.943 p
Paso No. 8. Hállese la relación ArlA w de la viga:
Aj = bj Xlj = 0.178(12.8) = 2.2784 X 10-3 m2
(d - 2lj )tw =[407 - 2(12.8)](0.0077) = 2.9368 X lO-3 m2 Aw =

<!-- p. 502 -->

502 CONEXIONES SOLDADAS

Paso No. 9. Hállese la relación Pe/db = 27.9120 = 1.395

Paso No. 10. El factor de modificación de momento, O/m es
\= ( Af )0.32( Pe)0.25 «: e.e, A d w b

32
\= 1.04(0.943)( (1.395)°·25 ~:~~~t
\= 0.982
Paso No. 11. El momento de diseño M d = MXO/m = 2.49 x 0.982 =
2.45 kN. El espesor de la placa terminal, tp , es (como para otras placas rec-
tangulares a flexión):
x6~;5~ ) 1/2 tp = ( b

6 x 0.00245 )1/2
\= ( 0.200 X 187.5 = 0.0198 m
Usese para la placa terminal, un espesor tp = 20 mm.
Paso No. 12. Compruébese el ancho máximo efectivo de la placa (no ha
de ser menor que el ancho suministrado):
be = bf + 2D + tp
\= 178 + 2(10) + 20 = 218 > 200 mm suministrado. Correcta
Nota: Si be \< bp • es necesario repetir los pasos 7 hasta 12 inclusive. usando bp = be'
Paso No. 13. Compruébese el esfuerzo cortante de la placa.
Fj
\11) = 2bt p
357
2 X 0.200 X 20 = 44.6 MPa « 0.4 X 250 Correcta

Resumen del diseño: placa terminal 200 X 338 X 20 mm de espesor. Se
usarán ocho tornillos A-325 de 20 mm, para conectarla al patín de la colum-
na. Se usará una soldadura de filete de 10 mm, para conectar la viga a la pla-
ca terminal. / / /

9-10 CONEXIONES SOLDADAS EN LAS ESQUINAS

Las conexiones en las esquinas pueden ser rectas o acarteladas. Solamente se considerarán conexiones rectas en este lugar. Por lo general, el diseño de las conexiones rectas de esquina está controlado por consideraciones de cortante. Consi-

<!-- p. 503 -->

CONEXIONES SOLDADAS EN LAS ESQUINAS 503

dérese la conexión de esquina de la figura 9-160. Si se supone uniforme el-esfuerzo cortante sobre el alma de la viga en una distancia de (figura 19-16b), se tiene

C===::::J~ T=M/O.95db
fv--

8 ~ ~lO!
(a)

(b)

,...,.....:::::;==-------,-T--7
As/Fe ~.--,," /
/
/
/
I
/ "---__---'---':..:::1

(e)

ma

Atiesador
vertical Placa de respaldoN ill (d)O

Figura 9-16 Conexiones rectas en esquinas de columnas. (o) (b) (e) (d) (e) Conexiones de esquina
en la columna, con muñones de la viga soldados a tope a la columna.

M
fvdctwb = T = e = O.95d
b
Tomando j", = F; = O.4F)' se obtiene, redondeando ligeramente:
\~ }~~ (pulg ) para el pie lb seg (9-4) twb
y b c
2.5 x I\<fiM (mm) para el SI (9-4m) tbw ~
F;,dbdc

<!-- p. 504 -->

504 CONEXIONES SOLDADAS

donde de> d b = peralte tabulado de la columna y viga, respectivamente, pulg
o mm.
M = momento en la junta, pies . kips o kN . m

En el diseño plástico, recomendado por muchos diseñadores, el uso de M¿ y
t; = Fvy = F/.J3, Y 0.9 db da por resultado

23M
t > P (pulg] (9-5) wb - Fdd y e b

(mm) (9-5m)

donde F)" de> Yd t» son como se definieron previamente. El momento M p = F; Z,
o se puede usar M¿ = M x FC, donde M = momento de la carga de trabajo, como en el diseño elástico, y FC = factor de carga en el diseño plástico. Se recomienda un valor de FC = 1.7. Si el espesor del alma, twb es menor que el que
viene dado por la ecuación (9-4) ó (9-5), se requerirá un atiesador en el alma.
Puede ser una placa doble en el alma (figura 9-l6d), pero se prefiere generalmente
un atiesador diagonal, ya que es más fácil de fabricar. Nótese que la soldadura en
los cuatro lados de la placa doble puede resultar en una falla prematura de la soldadura o de la placa debido a la excesiva restricción de los esfuerzos de contracción. Se le da al atiesador diagonal las proporciones necesarias para tomar la
componente horizontal de la deficiencia de cortante en el alma (figura 9-16c).
Luego, en términos de los esfuerzos reales, se tiene

Sustituyendo los esfuerzos permisibles, se tiene

(9-6)

El valor de Fe(compresión) se puede tomar ya sea como 0.6Fy o, preferiblemente,
Fy/1.7, ya que es algo más conservativo, puesto que el atiesador está a compre-
sión. Usando diseño plástico (y con Fys = Fy del acero del atiesador), se obtiene

(9-7)

Se deben usar unidades consistentes en ambas ecuaciones (9-6)y (9-7). Nótese que
es posible extender la columna para fabricarla esquina, o si no, alternativamente,

<!-- p. 505 -->

CONEXIONES SOLDADAS EN LAS ESQUINAS 505

extender la viga sobre la columna (como se ve en la figura 9-160). Se deben usar
los valores apropiados de de> db, twb' consistentes con las deducciones de las
ecuaciones dadas y el conjunto de la junta en la esquina.

Ejemplo 9·9 Diséñese la junta de esquina de la figura E9-9a. Usense electro-
dos E70, las especificaciones del AISC, y F y = 250 MPa para todo el acero.

244 kN

Viga: W610 x 241.1
d » 635 mm, b¡» 329 mm
Ir = 31 mm, t.; = 17.9 mm
k = 48.4 mm

Placa en el extremo de la columna: 387 x 427 x 20 mm de espesor
Columna: W360 x 261.9
d = 387 mm. br = 398 mm
610 kNr m Ir=33.3mm.l w =21.1 mm
s, = 4.60

Figura E9-9a
SOLUCION
Paso No. 1 Diséñense los atiesadores verticales 1 y 2.
Para el atiesador 1, opuesto al patín a tensión de la columna:
M 610
fb = Sx = 4.60 = 132.6 MPa
X 33.3 = 13.2534 X 10-3 m2 Aje = bJtJ = 0.398
\~(132.6 X 13.2534) = 2929 kN PbJ = VbAJ =
PbJ - F;,etejtbJ = 5k)
Ast ¿ F'
yst
Usese la viga para la dimensión de la "columna" y 2.5 en lugar de 5k, puesto
que el patín a tensión de la columna está en el extremo y no está centrado en
la zona 5k.
A = 2929 - 250 X 0.0179(33.3 ...,... 2.5 X 48.4)
st 250
\= 10.146 x 10- 3 m2
Usese placa terminal:
bp = 398 mm (mismo ancho de columna)
tp = 28 mm
Ast = 0.028 X 398 = 11.14 X 10-3 m2 Correcta
Para el atiesador 2, opuesto al patín de compresión de la columna:
db(alma) = d -2k = 635 - +(48.4) = 538.2 mm

<!-- p. 506 -->

\~ CONEXIONES SOLDADAS

Se requerirá un atiesador si bb >dbw:

10.73tL{i;
dbw > p
bf
10.73(17.9)3V250 = 332.2 mm
\> 2929
Como dbw suministrado = 538.2 > 332.2 requerido, se necesitará un atiesa-
dor en el alma.

El atiesador (un par con uno a cada lado del alma, opuesto al patín a
compresión de la columna) tiene que ser solamente la mitad del peralte de la
viga, ya que la carga está en un lado solamente.

33.3 '« = -2- = 17 mm use tsl = 20 mm taliesador > "2
b . - (0.67 X 329) + 17.9 = 1192 mm use b = 120 mm allesador 2 . SI

Paso No. 2. Compruébese si se requiere un atiesador diagonal.
Usese diseño plástico [ecuación (9-7)]:

Mp = 1.7 x M = 1.7 x 610 = 1037 kN . m
1.8 X 106Mp 1.8 X 106 X 1037
t; ~ F;,dcdb 250 X 387 X 635 = 30.38 mm
Como el valor suministrado twb = 17.9 \< 31.6 requerido es necesario usar
un atiesador diagonal.

_\ 635 o () ~ tan 387 = 58.64 cos () = 0.52042

l (Mp F;,dctw )
\- v'3 ASI = F;,s cos () O.90db
l [1037 250(387)(0.0179) ]
\= 250(0.52042) 0.90 X 0.635 - v'3
\= 6.2615 X 10-3m2

Usense dos placas de 20 mm X 160 mm de ancho:
Ap = 6.4 X 10-3 m2 Correcta

<!-- p. 507 -->

CONEXIONES SOLDADAS EN LAS ESQUINAS 507

Paso No. 3. Diseño de las soldaduras.

La soldadura para la placa 1:
P bi = 2929 KN F; = 0.3Fu x 1.7 = 247 MPa (diseño plástico)
Usando soldaduras de filete interiores (véase figura E9-9b), se obtiene D min =
8 mm, ya que tp = 25 > 20 mm. Compruébese el D efectivo para cortante en
el alma de la viga.
2 x De X 0.70711 x 247 = 17.9 X 250
v'3
De = 7.4 mm

De modo que solamente 7.4 mm de la soldadura en el alma de la viga resulta efectiva, ya que es el cortante del metal base el que controla. Usese D a lo largo del
patín interior, según se requiera y una soldadura de 8 mm en el alma de la viga.

L a1ma = [635 - 2(31)]2 = 1146 mm
Lpalin = (329 - 17.9)2 = 622.2 mm
D X 0.70711 X 0.622 X 247 + 1146 X 0.0074 X 0.70711 X 247 = 2929 kN
1447.8
D = 108.6 = 13.3 mm
Usese para el patín, D = 14 mm.

Soldadura de taller de los atiesadores
y las placas terminables

Los atiesadores se
colocan a ambos lados
del alma de la viga

398 X 427 X 20
Soldadura a tope (en el taller) Soldadura
en el campo

Nota: Todas ias placas, con excepción de la 1
son de 20 mm de espesor. Todas las solda-
duras de filete tienen D = 8 mm, excepto
Figura E9·9b la placa terminal de viga a columna

<!-- p. 508 -->

508 CONEXIONES SOLDADAS
La soldadura para la placa 2: con soldadura máxima efectiva, D = 7.40
mm en el alma, y D = 8 mm, requeridos para las placas atiesadoras de 20
mm, y cuatro tramos de soldadura de filete (refiérase a la figura E9-9b), se
tiene que la parte de Pbi soportada por el alma de la viga es
Palma = F.rtw( te!+ 2tp(col. base) + 2kb )
\= 250(0.0179)[33.3 + 2(20 + 48.4)] = 761.2 kN
Psoldadura = Pbi - Palma = 2929 - 761.2 = 2167.8 kN
4L X 0.0074 X 0.70711 X 247 = 2167.8 kN
L = 419.3 mm
d - 2t¡ = 635 - 2(31) = 573 mm > 419 Correcta (puede ponerse)

Soldadura para el atiesador diagonal:
Paties =As1F.r = 0.12(20)(250) = 600 kN/atiesador

Usense soldaduras de 8 mm, pero sólo son efectivos 7.4 mm:
d - 2t¡ 387 - 2(33.3)
Laties = cos () = 0.52042 = 615.7 mm

Suponiendo que son efectivos 600 mm, compruébese P:

\~ 600 Pso1d = 2(600) (0.0074) (0.70711) (247) = 1550.9 kN

Diséñese la soldadura para la placa terminal de la columna; se usará una sol-
dadura a tope de penetración total. El resumen del diseño está en la figura
E9-9b. / / /

9-11 DISEÑO DE SOLDADURAS DE FILETE, USANDO EL DFRC

El diseño de soldaduras de filete usando el DFRC es similar al diseño DFRC para
las conexiones atornilladas. Es necesario calcular la carga factorizada.

R; = 1.l(1.1D + 1.4L)

o las cargas factorizadas alternas que usan el viento, sismos, etc. El valor de R; se
compara con la resistencia permisible o cortante de la soldadura:
(9-8)
donde EEXX = del electrodo Fu (E60, E70, E80, etc.)
A w = área en la garganta = 0.70711 D
\<1>= 0.80 [valor actual (1978)]

<!-- p. 509 -->

DISEÑO DE SOLDADURAS DE FILETE, USANDO EL DFRC 509

La resistencia a cortante del metal base se calcula como para el alma de las vigas:
\<PE;,
\= 0.86) F vu = -v'3 ('"'t'
Como el electrodo siempre debe estar adaptado al metal base, el diseño de juntas
a tope usa los procedimientos DFRC para el tipo de miembro que utilice la jun-
ta a tope.

PROBLEMAS

Debe tenerse cuidado en todos los problemas al resumir la conexión que se estudia usando un dibujo
bastante claro.

9-1 Diséñese la soldadura para la junta de la figura P9-1, usando electrodos "ajustados", acero A·36
y las especificaciones del AISC, si tI = 5/8 pulg, t2 = 1/2 pulg, w) = 6 pulg, y w2 = 9 pulg.
Determínese P, basándose en el máximo permisible para el metal base.

Respuesta: P = 81 kips, L w = 12 pulg, usando Do 9/16.

Figura P9-l

9-2 Repítase el problema 9-1, si se usa acero con Fy = 50 kips/pulg/ las dimensiones de las placas son
las mismas. Se debe tratar de que sea un mínimo la longitud de la junta.
Respuesta: P = 112.5 kips.
9-3 Diséñese la soldadura para la junta de la figura P9-I, usando electrodos "ajustados", Fy = 345
MPa, y los esfuerzos permisibles para soldaduras de la AASHTO. Tómese t) = 20 mm, t 2 = 15 mm,
w1 = 175 mm, y W2 = 250 mm. Usese P = carga máxima permisible para el metal base según la
AASHTO.
9-4 Repítase el problema 9-1, usando el DFRC, y supóngase que la razón DIL = 1.0.
Respuesta: Pu = 118.8 kips, L w = 19 pulg, D = 5116 pulg.
9-5 Hállese el tamaño requerido de las soldaduras de filete, para unir la viga W610 x 241.1 a la placa
terminal de la columna, que tiene 387 x 427 x 20 mm, del ejemplo 9-9.
9-6 Diséñense las soldaduras y la placa de unión para un angular de 6 x 4 x 5/8 pulg, para el 50 por
ciento de la capacidad a compresión del angular y para L = 8 pies. Se usarán las especificaciones del
AISC, Fy = 50 kips/pulg/, y electrodos E70 y, además, una carga estática.
9·7 Repítase el problema 9-6, con la carga dinámica.
Respuesta: P = 35.5 kips, L) = 2.71, D = 5/16, sin soldadura terminal.
9-8 Repítase el problema 9-6 para una carga dinámica y DIL = 0.75, usando el DFRC.
9·9 Diséñense las soldaduras y las placas de conexión para un par de Ll52 x 102 x 19 mm, para una
carga de 75 por ciento de la capacidad efectiva del angular a tensión estática. Usense Fy = 250 MPa,
electrodos E70, y las especificaciones del AISC. Se mantendrá a un mínimo la tongítua ae la Junta.
9·10 Repítase el problema 9-9 para una carga dinámica.
9·11 Diséñese una conexión soldada para una viga simple, que soporte un cortante de 59.8 kips, entre
una viga W18 x 50 a una columna WI2 x 53. Usese acero A-36, electrodos E70, las especificaciones
del AISC, y angulares de 3 x 3 x t, con una longitud de 12 pulg.
Respuesta: t = 5/16 pulg; Da1ma = 3116; Dcol = 114.

<!-- p. 510 -->

510 CONEXIONES SOLDADAS

9·12 Diséñense los angulares de conexión y la soldadura para conectar los largueros con la viga transversal (de piso) de una armadura de puente. Se usarán soldaduras de taller para conectar los angulares
con los largueros y tornillos en el campo para conectarlos al alma de la viga transversal. Los largueros
son W18 x 50 y se debe suponer que la reacción incluye una carga muerta de 4 kips y una carga viva
con impacto de 35 kips. Se usará acero A-36, electrodos E70, un angular de 4 x 3 x t x 14 pulg y
las especificaciones de la AASHTO que sean aplicables.
Respuesta: ta = 5/16; D = 1/4 pulg.
9.13 Diséñense las conexiones terminales soldadas para que una viga W18 x 55 desarrolle el 70 por
ciento de la capacidad de momento, basada en Fb = 24 kips/pulg-', Usense las especificaciones del
AISC, el electrodos E70, y acero A-36. La columna es una W12 x 65, de momento que se requiere
comprobar si se necesitan atiesadores para el momento que se desarrolla en un solo lado.
9·14 Diséñese una conexión para una viga W460 x 81.8 que soporte un cortante de 152 kN. Se usarán un par de angulares 76 x 76 x t, con L = 200 mm. Usense las especificaciones del AISC, F; =
250 MPa, y electrodos E70.
9·15 Diséñese la soldadura y la placa para la carga que se muestra en la figura P9-15. Usese acero
A-36 y las especificaciones del AISC.
Respuesta: D = 3/16 pulg; t = 112 pulg.

Patín adecuado
j-, de columna

Figura P9·15

9-16 Diséñese un angular de asiento (y un angular auxiliar superior para estabilidad lateral) para apoyar una W16 x 40 en un claro simple de 25 pies que soporta una carga uniforme de 1.54 kips/pie que
incluye el peso de la viga. Téngase cuidado de hacer un dibujo final de diseño que esté claro. Usese
electrodos E70, acero A-36, y las especificaciones del AISC. La viga se conecta con una columna
W12 x 53.
9-17 Diséñese un asiento de viga atiesado usando una WT, para una W530 x 196.4 que soporta una
carga uniforme de 91.9 kN/m, incluyendo el peso de la viga, en un claro simple de 8.75 m. Usense un
angular superior auxiliar para estabilidad lateral, electrodos E70, Fy = 250 MPa, y las especificaciones del AISC.
9·18 Diséñese una conexión soldada de momento para dos vigas W16 x 40 que se conectan en los patines opuestos de una columna W12 x 53. Usense placas soldadas arriba y abajo para desarrollar el
momento y soldadura de filete en el alma, para el cortante. El momento de la viga es de 98.9
pies > kips (en ambos lados) y un cortante de 34.5 kips. Usense las especificaciones del AISC, acero
A-36, y electrodos E60.
9·19 DosvigasW41O x 84.8 seconectan con una trabe W530 x 123.5como se ve en la figuraP9-19,
en una conexión por momento. Diséñenselas conexiones usando electrodos E60, acero Fy = 250 MPa,
y las especificaciones del AISC.
Respuesta: Pruébese una placa superior de 24 x 150 mm x LI2 = 260 mm, y D = 12 mm.
Filete

W410
/Tornillo de montaje

W460 Figura P9·19

<!-- p. 511 -->

DISEÑO DE SOLDADURAS DE FILETE, USANDO EL DFRC 511

9-20 Rediséñese la conexión de esquina del ejemplo 9-9 usando una placa terminal soldada a la viga
para conectarse a la columna. Usense los datos que se dan en el ejemplo 9-9. Téngase cuidado de
mostrar un dibujo del diseño final de la solución.
9·21 Diséñense las placas terminales de una conexión atornillada para la capacidad total de momentos
de una Wl6 x 50 para ser atornilladas al patín de una Wl4 x 211. El cortante de la viga debido a
carga uniforme es de 48.55 kips, incluyendo el peso de la viga. Usense las especificaciones del AISC,
acero A-36, tornillos A-325, y electrodos E70. Muéstrese un dibujo del diseño final.

<!-- p. 512 -->

viga
armad¡

viga
armada

Flgur.a X·} Cuarto de máquinas en una planta de energía. Nótese que se usa una viga armada conti-
nua muy larga para la trabe carril de una grúa. Se escalonan las columnas para el soporte de la trabe
carril.

<!-- p. 513 -->

CAPÍTULO
DIEZ
TRABES ARMADAS

10-1 GENERALIDADES

Las trabes armadas, que incluyen vigas laminadas con cubreplacas, las que se conocen como vigas armadas, se usan cuando la combinación carga y claro son tales
que resulte insuficiente una sección laminada corriente.
Se pueden usar secciones laminadas armadas cuando el peralte total esté limitado en los edificios, y a veces se usan para puentes de carretera y ferrocarril.
En las aplicaciones en edificios, cuando seencuentra limitado el peralte, se pueden
usar como alternativa dos perfiles laminados en paralelo. Aun cuando el peso total sea apreciablemente diferente, los costos adicionales de fabricación (como el
corte de las placas que se añaden y la soldadura de los patines) puede producir un
costo total más alto en el caso de la sección armada.
Las trabes armadas son perfiles estructurales fabricados, que se forman soldando placas de patín a una placa de alma (aunque hay vecesen que se pueden usar
soldaduras o tornillos), para construir un perfil que sea intermedio entre los perfiles laminados S y W. Las trabes armadas encuentran amplio uso en puentes y no
son raras en los edificios. En la figura 10-1, se muestran diversos tipos de trabes.
La trabe carril, que se muestra en el edificio industrial de la figura lO-la, es con
mucho el uso más común de las trabes en la construcción de edificios.
Por lo general, las trabes armadas se fabrican soldando dos placas de patín a
una placa de alma, como se ilustran los croquis de detalle de la figura 10-2.Los ma-

513

<!-- p. 514 -->

514 TRABES ARMADAS

Ampliación de la trabe
carril,queno se ha
montadotodavía,quese
(a) muestra en primerplanoa laderecha

(b)

Figura 10-1 Instalaciones típicas que usan trabes armadas. (o) Trabe armada que se usa en un edificio
industrial. La trabe armada se fabricó de un perfil laminado W, con una canal colocada arriba, como
se indica. (b) Puentes con tablero sobre trabes y largueros, en una intersección carretera. Nótese el uso
de claros simples y continuos. (e) Trabes armadas usadas en un puente de ferrocarril. Se usan en este
caso trabes con tablero abierto de paso superior claros a la derecha colindando con trabes con tablero
abierto de paso a través para el claro de la izquierda. El uso de trabes con tablero como se muestra,
permite el uso de pilares más cortos. El término "tablero abierto" se refiere a que los durmientes se
colocan directamente sobre los patines de las trabes o largueros.

teriales de uso más común son el acero A-36 y electrodos E60 o E70. En los tiempos en que la mano de obra era más barata, y cuando el estado del arte de soldar
no había progresado mucho, se fabricaban las trabes usando angulares remachados a una placa de alma, y usando una o más cubreplacas remachadas también a
los angulares del patín como se ilustra en la figura 1O-2b. Las trabes en cajón, que
consisten de dos placas paralelas de alma, separadas una cierta distancia, tienen
algún uso en los puentes, pero no se les considerará en este lugar.
Los atiesadores verticales (figura lo-2c; también figura lo-b) se requieren generalmente cuando la placa del alma es muy delgada, la relación h/t.; es grande, ylo
el esfuerzo cortante en el alma es relativamente alto. Los atiesadores reducen de
manera efectiva la relación a/b, que se trató en el capítulo 3 (figura 3-6 y tabla 3-1)
y aumentan la capacidad a cortante con respecto al pandeo por cortante del alma.
Las especificaciones requieren casi siempre que se coloquen atiesadores debajo de

<!-- p. 515 -->

GENERALIDADES 515

Peso mínimo: Aj == A w t b )
A¡ = b¡t¡ p
A w = ht.;
(al

II Patín
Atíesador I
de apoyo 1
I1+--a-_f+---a---f---
I
I

(e)

Figura 10-2 Croquis y detalles de las trabes armadas. Nótese la definición del peralte D y la distancia
libre h. La relación ñ/t.; constituye un parámetro significativo en el diseño de las trabes armadas. (a)
Trabe armada soldada. (b) Viga armada remachada o atornillada. (e) Elevación de la trabe (vista lateral) ilustrando otros elementos del diseño,

las cargas concentradas, y en las reacciones de las trabes armadas, sin importar la
intensidad del cortante. Los requerimientos de atiesadores a lo largo del claro
(atiesadores transversales intermedios) dependen del esfuerzo cortante y de las
proporciones del alma.
El espaciamiento a de los atiesadores depende de la relación h/tw• donde h es
la distancia libre del alma entre los patines. La distancia se medirá entre placa de
patín a placa de patín, para una trabe soldada que consista de tres placas. La distancia libre para las trabes que usan angulares de patín es como se muestra en la
figura lo-2b. Se sigue necesariamente, que es posible efectuar un análisis económico, utilizando angulares de patín soldados, con la reducción, o eliminación de
atiesadores, versus placas rectangulares de patín y una mayo'" distancia libre, h,
en el alma.
Las trabes armadas, que se usan en la construcción de edificios pueden resultar económicas con claros hasta de cerca de 300 pies (lOO m). Los peraltes de las
trabes pueden llegar hasta 15pies (5 m) o más. Son comunes peraltes de 4 a 8 pies.

<!-- p. 516 -->

516 TRABES ARMADAS
En términos de la relación peralte/claro (D/ L), el rango es de -k a is, con la mayor parte de los valores del orden de i2 a -Is. Claros más grandes en los edificios
puede que requieran el uso de una armadura.
En los puentes de carretera, cuando el claro excede de 50 a 60 pies (15 a 18m)
se usan las trabes armadas y son generalmente más económicas que las armaduras
para claros hasta 300 pies (100 m) o más. En general, las vigas laminadas son más
económicas para claros en puentes de menos de 50 a 60 pies, y se usan con una
configuración de cubierta con largueros de piso. Aunque por lo general las trabes
son más económicas que las armaduras, estas últimas tienen uso todavía en
muchas situaciones, debido a consideraciones estéticas, en particular cuando se
requieren vías adicionales de tránsito y los miembros en servicio están formados
por armaduras.

Los puentes que usan trabes armadas (tanto de carretera como de ferrocarril)
se pueden clasificar como:

l. Puentes de trabes de tablero superior, donde el piso del puente o la carga está
colocada directamente sobre el patín superior. En la terminología de los ferro-
carriles, puede ser un puente de trabes de paso superior donde los durmientes
descansan directamente sobre los patines (figura 1O-3a y b). En la construcción
de carreteras este tipo de puente soporta el sistema de piso de largueros y vigas
transversales, entre las trabes principales que soportan las cargas.
\2. Puentes de tablero superior con largueros (figura lO-lb), donde tres o más tra-
bes funcionan como largueros de piso, similares a vigas laminadas, pero sobre
claros más largos. Estas trabes deben tener un contraventeo adecuado, con un
sistema de contraventeos ó diafragmas (véase figura 10-15). Este es el tipo más
común de puentes de carretera que usan trabes armadas.
\3. Puentes de paso a través con trabes, donde la carga se mueve entre las trabes
principales y se transfiere a éstas por medio de un sistema de vigas transversa-
les o vigas transversales y largueros (figuras lO-le y 10-3a) situados tan cerca co-
mo sea práctico al patín inferior. Esta distribución tiene amplio uso en puentes
de ferrocarril y se puede usar ya sea para un tablero abierto como para un
tablero con balasto. El uso de un puente de paso a través resulta a menudo
económico al reducir la altura de las pilas y/o el relleno en los aproches, com-
parado con los puentes de tablero superior que requieren de espacio libre para
los pasos inferiores.
\4. Puente de tablero con balasto, donde el sistema de vigas de piso está cubierta
con un tablero fabricado (por lo general de placa de acero) y revestido con una
capa de 6 a 15pulg (150 a 500 mm) de balasto para vías sobre el que se colocan
los durmientes y rieles. En la figura 10-4 se ilustra un puente de tablero con
balasto.
La relación D/L para puentes van desde cerca de ~jj a un mínimo de is (como
en la especificación corriente de la AASHTO). El peralte de un puente de carretera se debe balancear con los parámetros del sitio. Por ejemplo, 12 pulgadas extra

<!-- p. 517 -->

GENERALIDADES 517

(a) (b)

(e) (d)

Figura 10-3 Detalles de los puentes. (a) Vista de la parte inferior de un-viejo puente de tablero inferior
abierto con trabes, que usan un sistema de vigas transversales y cortos largueros longitudinales, sobre
los que descansan directamente los durmientes. Esta es la parte de la izquierda del puente de la figura
l O-Ic, (b) Vista de la parte inferior de un viejo puente de tablero superior abierto con trabes. Nótese el
sistema de contraventeo de las trabes, tanto vertical como horizontal (en el plano del patín inferior).
Esta es la trabe de la parte de la derecha del puente de la figura lO-le. (e) Puente moderno de tablero
inferior con trabes y balasto. (el)Vista de la parte inferior del puente que se muestra en (e), indicando
la placa metálica del tablero, para sostener el balasto, y además el sistema de vigas transversales para
transferir la carga a las trabes principales. Nótese la línea única de diafragmas longitudinales para el
contraventeo de las vigas transversales.

en el peralte de la trabe (300mm) para una estructura de paso superior, que utilice
relleno en los aproches, puede requerir una cantidad sustancial de relleno extra y
derechos de paso, comparada con el mayor peso de la trabe con menor peralte
que requiere un mayor espesor en los patines y posiblemente en el alma.
Las trabes armadas se recomiendan para los puentes de ferrocarril con longitudes de claros de 50 a 150 pies (16 a 45 m), usando las vigas laminadas para claros más cortos. Las armaduras se usan con claros más largos. El rango común de
D/L en los puentes de ferrocarril es de l~ a -lo. Sin embargo, las especificaciones actualmente en uso no usan la D/L como cnterio; se limita más bien, la deflexión
calculada de la trabe bajo la carga muerta total + carga viva, incluyendo el impacto, a .:l/claro ~ 1/640.

<!-- p. 518 -->

518 TRABES ARMADAS

(a) (b)

(e)

Figura 10-4 Puente de ferrocarril de tablero superior con trabes y balasto. (o) Puente en construcción
de tablero inferior, con trabes y balasto. Nótese que las cartelas para la estabilidad lateral soportan
también el patín a compresión a intervalos muy cercanos. Aunque no se ve claramente, las placas del
tablero están soldadas a tope y enrasadas en elcampo. (b) Vista de la parte inferior del puente de tablero
con balasto que semostró más arriba. Nótense las ménsulas del acotamiento para mantenimiento, en la
parte exterior de la trabe, donde se añadirán los tablones de piso. (e) El puente terminado, con el balasto y la viga colocados en su lugar. También está terminado el acotamiento para mantenimiento.

Las trabes se fabrican en segmentos limitados por la capacidad de izaje del
equipo de montaje/transporte y la capacidad de laminado del molino, para producir los tamaños de placa. Las trabes armadas soldadas se usan casi exclusivamente en la práctica de diseño en Norteamérica, debido a la reducción de los costos de fabricación y al hecho de que es posible soldar las placas de patín a las de
alma de un modo casi totalmente automático.
El acero A-36 es el que se usa con más frecuencia para las trabes armadas, y
casi universalmente para almas y atiesadores. Las trabes continuas requieren reducción en las secciones de momento positivo y secciones con mayor peralte en
las regiones de mayor momento negativo, sobre las reacciones. Un aumento en el
peralte de la trabe puede ser, en muchos casos, estéticamente agradable; sin embargo, se aumentan los costos de fabricación, ya que es necesario cortar un alma
de peralte variable, por Jogeneral, se requerirán atiesadores adicionales, debido a
la mayor relación h/t; que se produce. Como alternativa para el aumento del peralte de la trabe, se pueden usar aceros de más alta resistencia en las zonas de mayores momentos. El uso de acero de más alta resistencia para el patín, ya sea en
todo el claro o en zonas locales de más altos esfuerzos da origen a una trabe armada híbrida.
Una inspección de las figuras 10-1 a 10-3 y la observación de otras trabes en
servicioindican que no existeun diseño único para cada trabe que se presente en un

<!-- p. 519 -->

CARGAS 519

problema determinado. Con las restricciones de la DIL y las cargas, existe un número infinito de posibilidades para el área de la sección transversal. Si se define la
optimización del diseño de una trabe armada como la que produce el menor costo
global, no es práctico, aun con el uso de un programa de computación, "optimizar la trabe", puesto que menor peso no significa necesariamente (y quizá nunca
será así) el menor costo global, debido a las consideraciones de fabricación. Lo
que se debe tratar de obtener es un balance entre el peso y el costo de fabricación
a fin de producir una solución tan económica como sea posible (dentro de un esfuerzo razonable de cálculo, que constituye también un factor de costo).

10-2 CARGAS

Las cargas de las trabes se obtienen de manera similar a las de las vigas. Sin embargo, en el diseño de edificios, las cargas están a menudo en movimiento, como
en las trabes de las grúas viajeras en edificios industriales o almacenes. Las especificaciones del AISC requieren el uso de un factor de impacto para estos tipos de
cargas.
El diseño de trabes armadas en puentes de carretera implica la decisión sobre
el número de trabes que se han de usar por vía, y con el uso de las especificaciones
de la AASHTü para hacer la prorrata de la cantidad de carga de camión o vía que
le corresponda a las varias trabes, producir así un análisis del tipo de líneas de
influencia, usando ya sea cargas normales por vía o cargas normales de camión
para encontrar el momento y cortante máximos para el diseño. Las especificaciones de la AASHTü permiten el uso de solamente un camión por vía, para claros simples, por regla general, aunque, como se muestra en la figura 10-5, puede
haber más de un camión en el puente, en la situación crítica en un momento dado.
Cuando haya más de un camión en una vía, no es probable que el máximo momento resultante sea mayor que el producido por un solo camión debido ti los factores de longitud del camión y el posicionamiento de las ruedas. Cuando el claro
sea suficientemente largo, la carga por vía con una sola carga concentrada representa suficientemente bien una línea de camiones, y es más conveniente usarla,
que tratar de encontrar el número de camiones, y su posicionamiento para los
efectos de esfuerzos máximos.
Un programa de computadora que haga correr el camión normal a través del
puente (hacia adelante y hacia atrás), con salidas de cortante y momentos en los
puntos 0.1, resulta muy útil para el análisis de trabes continuas. Se puede notar,
de paso, que no es necesario un análisis por líneas de influencia en los claros continuos cuando se use un programa de computadora.
En todos los diseños de trabes las cargas normales de víalcamión se aumentan
por efecto del factor de impacto, que es una función de la longitud del claro.
En la figura 10-5se ilustra la colocación de la carga normal del camión en un
puente de dos vías, para obtener la contribución de las cargas de camión a cualesquiera de las dos trabes. El diseñador debe efectuar un tipo similar de análisis para vías múltiples que utilicen más de dos trabes.

<!-- p. 520 -->

520 TRABES ARMADAS

Ancho estándar de carga, por camión o carril de tráfico
Carga = ya sea por carril de tráfico o por camión estándar.

t----;----t:---t-y----If---+

..------5-+------.-. x =S/C- 5 (pie)
I----I-----w--+------I---+j X=S/c - I.Sc4(m) Y=X+W/C
l.----w/c---+/

Figura 10-5 Colocación de la carga del camión estándar para las cargas máximas sobre las trabes.
Háganse las modificaciones apropiadas para vías o trabes adicionales.

Ejemplo 10-1 ¿Cuáles serán los valores de diseño de momento y cortante pa-
ra las trabes de un puente de carretera que se muestra en la figura lO-S?
Cargas HS 20, S = 19 pies, W = 28 pies, claro = 110 pies. Carga
muerta debido a la plataforma, banquetas, etc. = 3.1 kips/pie.

SOLUCIÓN El factor de vía, L/, se obtiene por la E M con respecto a la tra-
be de la izquierda, en la figura lO-S, para obtener

X+Y
Lj= S
donde X=S/2 - S = 19/2 - S = 4.S pies
Y= X + W/2 = 4.S + 28/2 = 18.5 pies

Sustituyendo valores, se obtiene
\= 4.S ~918.S = 1.21 Lj
Se calcula el factor de impacto como (véase sección 1-10)

\~ ~ 1 = L + 125 = 110 + 125 = 0.21 \< 0.30 Correcta .
Los momentos son
2
wL 3.1(1l0f 4689' k' M d =-- = = pies' IpS 8 8
Se usan las ecuaciones dadas en la sección 1-9, para L = 110 \< 145.6 pies.
W ML = L [(0.9L + 4.206)(0.5L + 2.33) - 11.2L]

<!-- p. 521 -->

CARGAS 521

Al sustituir valores se tiene
M L = 1~~ {[0.9(11O) + 4.206][0.5(110) + 2.33] - 11.2(1lO)}

\= ~O (5916.8 - 1232.0) = 1703.6 pies· kips

Los valores de la fuerza cortante son
\- wL - 3.1(110) - 1705 k" Vd - 2 - 2 - . lpS
El cortante por carga viva sobre la reacción (una rueda de 32 kips sobre la re-
acción) es

L - 16.8 ) VL = W ( L + 0.8
\= 40( 110 1~016.8 + 0.8) = 65.9 kips

Se notará que M¿ está en el centro del claro, mientras que ML está a 2.33
pies a la izquierda (cuando el camión se mueve de izquierda a derecha). La
diferencia es tan pequeña que se sumarán sencillamente los dos valores, co-
mo si ocurrieran en el centro del claro, y obtener así un diseño de M ligera-
mente conservador:

Mdiseño = ML(Lf ) + impacto + Md
\= 1703.6(1.21)(1 + 0.21) + 4689 = 7183 pies' kips
El cortante de diseño es
Vdiseño = VL(Lf ) + impacto + Vd
\= 65.9(1.21)(1.21) + 170.5 = 267 kips III

Es más difícil diseñar trabes de ferrocarril, ya que hay 18 ruedas en la carga
normal de la serie Cooper E. Se dispone de auxiliares de diseño, como los que
aparecen en la tabla 1-2, que suministra los momentos máximos aproximados (o
exactos) debido al tren en movimiento, ya sea en el centro del claro o muy cerca
del mismo. Estos auxiliares de diseño se basan en la combinación del uso de
dM/dx para claros cortos, donde sólo tres o cuatro ruedas están simultáneamente
sobre el claro, y una línea de influencia con el ápex en el centro del claro para un
gran número de ruedas sobre el claro. En la tabla 1-2 se dan también los valores
de las reacciones en los extremos (cortante) y la máxima reacción (cortante) desarrollada en una viga de piso a la que se conectan dos largueros de piso cuyas
longitudes se muestran en la primera columna. [Por ejemplo, para una viga de piso entre dos largueros de 7 pies, la máxima reacción se obtiene cuando una carga
de rueda de 10 kips está sobre la viga de piso, y las otras dos ruedas están a 5 pies de
distancia, dando R = 10 + 2(217)10 = 15.7 kips; similarmente, para L = 10

<!-- p. 522 -->

522 TRABES ARMADAS

pies, la reacción R = 10 + 2(5/10)10 = 20.0 kips; etc.] Los valores que aparecen
en la tabla son para una carga Cooper E-SO; cualquier otra carga X, será XISO x
el valor de la tabla. )

10-3 PROPORCIONAMIENTO DEL PATIN Y DEL ALMA
DE LAS TRABES Y SECCIONES ARMADAS

La cubreplaca del patín de una sección armada. que usa como base una sección
laminada, se puede proporcionar como sigue (refiérase a la figura 10-6). Suponiendo que el máximo esfuerzo de flexión, lb' es el valor permisible de Fb, el valor
promedio en el patín es aproximadamente 0.95 Fb•* Sea, por tanto

f~Sx MI = = 0.90FbSx (a)
\~)(~b; M 2 = a'tie = (d + x 0.95Fb ) (b)
La capacidad requerida de la sección es
(e)

Al sustituir las ecuaciones (a) y (b) en (e) y tomar (d + C) = (d + ti) que define al
área del patín A¡ = bítí, Ytomando la relación 0.90/0.95 como aproximadamente
igual al, se obtiene
.._---- .. -_._.-- /-
Mw~ ~ ¡
11 - d + e (10-1) A¡ ~ (d + \<:::»0.95Fb \
Resulta evidente que la ecuación (10-1) no da una única solución. y las cubreplacas deben ser investigadas usando lb = MIS :$ Fb. Un valor razonable de e = 1
pulg o 25 mm.

Figura 10-6 Distribución del esfuerzo de flexión en la sección transversal de una viga armada.

• En la unión de la cubreplaca y la sección laminada, el esfuerzo es aproximadamente 0.90 FIr

<!-- p. 523 -->

PROPORCIONAMIENTO DEL PATIN Y DEL ALMA 523

l
Ejemplo 10-2 Diséñese las cubreplacas para una sección W920x 34--2.3,
usando F, = 250 MPa para un momento de 3630 kN . m para las condi-
ciones mostradas en la figura E1O-2a. Usense las especificaciones del AISC.

SOLUCIÓN Datos para una W920 x 342.3:
wt = 3.36 kN/m d = 912 mm
b¡ = 418 mm S; = 13.72 X 10-3 m3

Ix = 6243.5 X 10- 6 m" tj = 32.0 mm
A = 43.61 X 10-3 m2

Los momentos son:

M = wL2 = 72.6(20)2 =3630kN· m L 8 8

M = 3.36(20)2 d = 170kN· m 8
Mdiseño ='3800kN· ID

Tentativamente, el área de cada cubreplaca es [usando la ecuación (10-1)]

3800 13.72 A = ------,--------,- j (0.912 + 0.025)(0.95 X 0.6F;,) 0.912 + 0.025
A.l-~ 28.46 - 14.64 = 13.82 X 10-3 m2

Se podría usar cubreplacas del5' x 548 para el patín; sin embargo, se usará
arbitrariamente un ancho de placa que sea 52 mm mayor que el b¡ de la viga,

JT7 "'1. = 72.6 kN/m l
1- ..1

Figura EIO·2a.

<!-- p. 524 -->

524 TRABES ARMADAS

lo que permite un vuelo de 26 mm a cada lado, para soldar la placa al patín.
Esto da
b; = 4.18 + 52 = 470 mm
, 13.82 294 f¡ = 0.47 = . mm úsese 30 mm

Se comprobará ahora si son adecuadas las placas de 30 x 470:
1x = i o'*-, 2Aá}-o
\=(6243.5 + 2(0.QJ)(D.470)( 912 ; 30r
/ = 12 499.4 x 10-6 m"

El módulo de sección es

1 12-499.4 -3 3 S; = e= 912/2 + 30 = 25.719 x 10 m

El momento adicional debido a las cubreplacas del patín es proporcional al
área del patín:

M = 3QN\'0.030(470) (110) = 3855 kN . total ~v + 43.61 _/ m
3855 fb = 25.719 = 149.9 MPa \< 150 .Correcta

Las cubreplacas se soldarán como se muestra en la figura ElO-2b. Esto requiere la
comprobación deb//t;para que cumpla con el AISC, sección 1-9.2.2 (elemento
con borde atiesado):

670 = 42.4 \< !?.
_~ t -
vE;,

Ir = 30¡--470 rnrn---j
1- I I--bJ =418--1 I
T
soldadura

Figun El8-2b ///

<!-- p. 525 -->

CUBREPLACAS DE LONGITUD PARCIAL 525

b" 418 -L = - = 13.93« 42.4 Correcta tÍ 30
No es necesario verificar el bl2t¡de la viga, puesto que tr = 32.0 mm. Se usa-
rán cubreplacas de 30 x 470 mm.

10-4 CUBREPLACAS DE LONGITUD PARCIAL

Es evidente, de la inspección del diagrama de momentos del ejemplo 10-2, que no
se necesita la cubreplaca para la longitud total de la viga. Se puede obtener alguna
economía proporcionando cubreplacas solamente en la región donde se necesiten.
Sin embargo, las especificaciones son muy rígidas en lo que a proveer se refiere,
una distancia más allá del punto teórico de corte para desarrollar totalmente la
contribución de la cubreplaca a la resistencia a flexión de la sección. En la figura
10-7 se ilustran los requerimientos del código para esta distancia.
La capacidad del sujetador para fijar la cubreplaca a la viga se puede calcu-

AISC Seco 1.10.4 AASHTü Seco 1.7.12
Punto teórico de corte (ptc)
D de la soldadura
tcp
f --------- T bj 3" or 75 m~..I
\--------- Lmin 1 mm b'(
D>0.75tj ¡""-a =1.5bj-
La AASHTü permite cubreplacas ahusadas con el
D \<0.75rj tcp mínimo ancho en la punta que se muestra en la figura

tcp ( f
bj
Alternativa con ahusamiento ) f-4--a =1.5bj- 1
\--------
1--- _
tcp
t 1- a = 2bj---l bj
a =2bj AASHTü: longitud minima L mínde la cubreplaca1 .1 pie lb seg 3db + 3 pie
SI: 3db+0.9 1 m
Nota: El AREA (Sec. 1.7.2.i establece meramente que las cubreplacas se deben extender lo suficiente pasado el
punto teórico de corte para desarrollar la capacidad de la placa.

Figura 10-' Requerimientos del código para las distancias teóricas de corte de las cubreplacas. Los requerimientos serán los mismos para cubreplacas más estrechas (como se muestran arriba) o más
anchas que la placa o patín de la viga que se encuentran inmediatamente debajo.

<!-- p. 526 -->

526 TRABES ARMADAS

\~c (véase figura 10-6);lar como la diferencia entre las fuerzas de compresión e y
en forma alternativa, se puede calcular usando

VQ v =-- (kips/pulg o kN/m) s 1

donde Vs = fuerza/longitud del cortante desarrollado
Q = momento estático de la cubreplaca con respecto al eje neutro
1 = momento de inercia de la sección, incluyendo las cubreplacas

El espaciamiento de los tornillos o soldaduras se puede hallar igualando la capacidad de soldadura/longitud o capacidad del tornillo, y el espaciamiento s como

capacidad de resistencia s =

La capacidad de la soldadura en el punto teórico de corte de la cubreplaca se obtiene igualando el momento de la capacidad total de la soldadura con el momento
en el punto teórico de corte.

F = MQ (kips o kN) w 1

donde Fw fuerza total que ha de soportar la soldadura en la longitud de
corte a
M momento flector en el punto teórico de corte
Q, 1= términos ya definidos

Ejemplo 10-3 ¿Cuál será la distancia teórica de corte para la viga con
cubreplacas del ejemplo 10-2? Diséñese también la soldadura para sujetar
las placas a la viga, usando electrodos E60.

SOLUCION Obténganse los puntos de corte (figura ElO-3a). La capacidad
de la viga sin placas de cubierta es
Fw = 0.3(415) = 124.5 MPa
Como el diagrama de momentos es una parábola con pendiente = Oen la mi-
tad del claro, la ecuación para el momento es

como se muestra en la figura ElO-2a, con el origen a la mitad del claro. Co-
mo M, = Opara x = LI2, se tiene
4Mc 2 M ---x L 2 x = M o

<!-- p. 527 -->

CUBREPLACAS DE LONGITUD PARCIAL 517

77.1 kN/m JT7 l
1- ·1
V~I~~
y = kx 2

E
Z..:\<
V)
V)
OC>
M" C')

Figura EIO-Ja

Con M; = M¿ =~058 k~'i' m a la distancia x de la mitad del claro, donde la
capacidad de la viga es adecuada sin cubreplacas, el punto teórico de corte es

L2 ]1/2
X = (3855 - 2058) 4 x 3855 = 6.828 m [

La longitud teórica de la cubreplaca = 2x = 2(6.865) = 13.73 m.
Diséñense las soldaduras (cubreplaca de 30 x 470 mm; I, = 12499.4 x
10-6 rrr'): en el punto de corte, x' = 10 - 6.83 = 3.1.7 m.

Cortante V = 771 - 77.1(3.17) = 530 kN
Q = Ay = 0.030(0.470)( 9~2 + 15) = 6.41 X 10-3 m3
. 530(6.41)
Os = 12499.4 = 281.6 kN/m

(Tomando nota que 1 es 10-6 y Q = 10-3, se obtiene 281.6 kN/m y no la lectura directa de 0.2816.)
El esfuerzo permisible usando electrodos E60:
Fw = 0.3(415) = 124.5 MPa

Se usará arbitrariamente D = 8 mm para la soldadura (ti> 20 mm según la
sección 1-17.2 del AISC) de manera que la separación teórica en el punto de
corte hacia el interior del claro es
Pw = 2(0.008 x 0.70711)(124.5) = 1.4085 MN/m m

<!-- p. 528 -->

S28 TRABES ARMADAS

Reacción y 1-40 .,- 160--1
! 110-==.,=-==_="_--=-_=_

1 r u 'f-a=3.17m T Cubreplacal3.66----- ¡_g----X = I.Sbj = 705 mm-j:=40"¡-80-¡'-'40 .,- 160 ~I
\~LongitUd total de la cubreplaca = 15.14 m - tJ = 32 mm
• L=20m tj=30mm I
Figura EIO-3b
III

Se usará tentativamente una longitud de soldadura de 40 mm (40 mm = 5D>
2D), que soportará
P; = 40(1.4085) = 56.34 kN

Esto corresponde a una distancia a lo largo de la viga de

_ 56.34 x l\<Y _ 200 Correcta s - 281.6 - mm

Usese longitudes de 40 mm de soldadura intermitente, alternando en cada la-
do, para incremento de 200 mm en la longitud.
La soldadura en la distancia o (o = 1.5bJ puesto que D \< 0.75tl) es
continua y el momento efectivo Me es

'Me =[0.705(2) + 0.418](1.4085)[912 + 2(30)]
\= 2503 kN . m > 2058 Correcta

Si Me hubiera sido menor que el momento en el punto teórico de corte hu-
biera sido necesario aumentar ya sea D o la distancia o (o ambas). El croquis
final es el que se muestra en la figura EIo-3b.

10-5 PROPORCIONES GENERALES DE LAS TRABES
ARMADAS

Todas las trabes armadas se proporcionan por ensayos sucesivos, y se revisan hasta que los esfuerzos de flexión son lb ~ Fb• Se añadirá atiesadores según se re-
\~ E; No existe una soluciónquieran, hasta que el esfuerzo cortante sea tal quelv

<!-- p. 529 -->

PROPORCIONES GENERALES DE LAS TRABES ARMADAS 529

única (a menos que dos personas utilicen el mismo programa de computadora con
los mismos datos de entrada). Se pueden hacer estimaciones iniciales de las dimensiones del patín, usando las contribuciones a flexión del alma y el patín como
se indica a continuación (véase figura 10-8). El momento que soporta el patín es

El momento que toma el alma es:

t h2 M = (liS = (II_W_ W Jb xw i» 6
El momento total es

Si se haceR = R = O.6Fy Yse toma d - tI = h,

La sustitución de valores da

pero twh2 = Awh, Yse obtiene la expresión deseada para el área del patín como

(10-2)

donde A w área del alma de la trabe (aproximadamente - todavía es necesa-
rio comprobar Me/1)

Ii;

D hn
twU~tf

Figura 16-8 Sección de la trabe para obtener una expresión aproximada del área del patino

<!-- p. 530 -->

5~ TRABES ARMADAS
F; = un valor que no ha de exceder 0.6Fy ; sin embargo, una inspección
de la deducción indica que se debe usar un valor algo menor que
0.6Fy (por ejemplo, 21 kips/pulg- en vez de 22 kips/pulg-, 132
MPa en vez de 137.5).

Nótese nuevamente que el peralte total no está fijado por lo general de una
manera exacta, que el espesor del alma puede variar dentro de límites razonablemente amplios, y que el área del patín es una combinación de anchos x espesores, de manera que se puede obtener un número igualmente válido de soluciones.
La única característica que puede establecer la preferencia de un diseño viable
sobre otro sería el costo final in situ.

10-6 TEORÍA DEL DISEÑO DE TRABES ARMADAS-AISC

Las trabes armadas son esencialmente armaduras, donde los patines son los cordones superior e inferior y el alma constituye lo que sería la celosía de la armadura. Como los miembros están formados a base de placas relativamente delgadas, la
teoría de la estabilidad constituye un elemento esencial del diseño. Se usan dos
"teorías" generales en el diseño de las trabes armadas. Un método, el de la resistencia al pandeo, se usa por la AASHTü y el AREA. El otro método, el de capacidad de carga, se usa por el AISC. Este último método reconoce que después que
la celosía se pandea inicialmente, hay una considerable capacidad de reserva para
soportar la carga hasta que se pandee el resto de la celosía. Esta capacidad de reserva se ha verificado mediante varias pruebas en gran escala, sobre trabes.
En la secciónsiguiente se tratarán las consideraciones de diseño de trabe armada que sigue las especificacionesAASHTü y AREA. Los elementos que forman la
sección de la trabe armada y diseño se estudiarán en secciones posteriores.

10-6.1 Patines de las trabes

El patín a compresión de una trabe armada presenta los tres modos corrientes de
falla que se muestra en la figura 10-9a.Los criterios de diseño de alAfy LlrTque se
usan para el desarrollo de las ecuaciones(1.5-60), (1.5-6b), y (1.5-7)del AISC se usan
también en el diseño de las trabes armadas para establecer los esfuerzos máximos
permisibles a flexión en el patín. No es probable que la relación Drt; (la misma
que la relación d/t; de las vigas laminadas) sea tal que se obtenga una sección
compacta, de manera que, en general, el máximo esfuerzo permisible a flexión es

Para Fb :5 0.6 Fy , el límite superior de la relación bfl2tf es

<!-- p. 531 -->

TEORIA DEL DISEÑO DE TRABES ARMADAS-AISC 531

Falla torsional Real
(1--....-
;4- Teórico~ Pandeo vertical Deformación del alma ~Falla / \<, Efecto del bajo un momento flector lateral relativamente bajo / pandeo del alma
torsional _____+.--__en el lado o
compresión, que
produceun
aumentoen el
esfuerzo del
patín

(a) (b) (e)

Figura 10-9 Modos para prevenir las fallas que se requieren en un análisis de la estabilidad de las trabes armadas. (a) Manera como falla el patín a compresión. (b) Pandeo del alma. (e) Distribución observada del esfuerzo (cualitativa) en la sección transversal de una trabe.

pie lb seg: SI: (10-3)

10-6.2 Diseño de la placa del alma

La curvatura a flexión de la placa del alma, es causa de presiones radiales que se
desarrollan en la superficie de contacto entre el alma y las placas del patín (figura
10-10). Si la placa del alma es demasiado delgada, según se la mide con la relación
hit (análoga a la KLlr para una columna), se pandeará.

Af=
bftfn
..----J.L---L-1D

LbfJJ

Figura 10-10 Esfuerzos a compresión que se desarrollan en el alma de la trabe debido a la flexión.

<!-- p. 532 -->

532 TRABES ARMADAS

La figura 10-10 ilustra la carga supuesta sobre la placa del alma de la trabe
en una faja dx (h). En el capítulo 3, se encontró que el esfuerzo crítico de pandeo
era

(3-5)

donde se ha sustituído la relación hit en lugar del valor bit dado anteriormente
por la ecuación (3-5). La fuerza ejercida sobre el alma del segmento que se
muestra en la figura 10-10 es

AJj sen \</> ;;;;; A/¡P

ya que cf> (en radianes) es un ángulo muy pequeño. El esfuerzof¡debe ser de la suficiente magnitud para vencer cualquier esfuerzo residual F; en el alma; por tanto, la deformación del alma (en unidades FL -2) en la fluencia es
Fr + F;,
ef=er +ey =---'-E
y el ángulo cf> es
dx 2(F,. + F;,) dx
\</> = efh/2 = E h

En el punto de fluencia del alma, la fuerza aplicada es

AJj tan \</> = A/¡P

para pequeños ángulos, y cf> en radianes, lo que da

dx
A/¡P = 2F;,(F;, + Fr ) Eh (a)

Este valor no debe ser mayor que la fuerza crítica de pandeo en el alma
kc '1T2E )2 Fc,tdx = ( 2 (t-h (t) dx (b)
121-JL)

Igualando las ecuaciones (a) y (b) Yresolviendo para hit, se obtiene

Cuando se usó el acero A-7, se supuso que se podía aproximar adecuada-
mente el esfuerzo residual F, como F, =f yl2 = 3312 = 16.5 kips/pulg-. Este va-
lor se usa comúnmente para todos los valores del acero Fy• Se supone también que

<!-- p. 533 -->

TEORIA DEL DISEJ'lO DE TRABES ARMADAS-Alse 533
la relación AwlA¡;¡¡¡ i, el coeficiente de Poisson para el acero, ¡t = 0.3, E =
29 000 kips/pulg-, y para k; = 1, se obtiene

h 13 784 -=--------
[Fy(Fy + 16.5)]'/2

El A1SC redondea estos valores para obtener la relación límite de hit como

h 14000 pie lb seg: -\< (10-4) t - [Fy(Fy + 16.s)]'/2
h 97 100 SI: -\< (l0-4m) t - [Fy(Fy + 114) ]'/2

La especificación del AISC permite una relación hit algo mayor si se usan atiesadores transversales con una relación de espaciamiento de alh -s I.S:

h 2000 pie lb seg: -\<-- (lO-S)
t - Vi:

h S270 (lO-Sm) SI: -\<--
t - Vi:

A continuación se muestran las relaciones hit máximas para los varios grados
de acero

Relación hit
F;, w/atiesacores wlatiesadores,
pero
kips/pulg/ MPa [por la ecuación (10-4)1 alh s 1.5

36 250 322 333
50 345 244 284
60 415 207 259
65 450 193 248

Los estudios experimentales realizados sobre trabes de tamaño natural han
demostrado que la placa del alma en la zona de compresión se desvía lateralmente
en pequeñas cantidades en las primerísimas etapas de la flexión, con la resultante
transferencia de esfuerzos de la porción a compresión del alma al patín a compresión. Esto da por resultado un aumento del esfuerzo en el patín por encima de la
cantidad indicada por la teoría, como se muestra en la figura lo-lOc. Este aumento

<!-- p. 534 -->

S34 TRABES ARMADAS

en el esfuerzo a compresión en el patín requiere una reducción en el esfuerzo permisible a compresión, de manera que el esfuerzo que realmente se desarrolla no
sea causa de una falla en el patín. Los estudios experimentales indicaron que esta
reducción del esfuerzo en el patín, se podía expresar en términos de AJ, A w' hit, Y
Fy • Una posible ecuación en términos del momento último sería

F~/Fb' se puede reescribir esta ecuación enComo la razón de MulMy = FulFy =
término de los esfuerzos siempre que el patín a compresión sea suficientemente
estable con respecto a LlrT y diAJ. Esto se logra limitando a Fb el esfuerzo máximo permisible, como lo definen las ecuaciones del AISC (1.5-6) y/o (1.5-7). El
valor de /Jo depende de los efectos de restricción del patín sobre el alma, y si se supone restricción parcial, se puede tomar como 5.7.JE7Fcr (véase Basler y Thürlimann, "Strength of Plate Girders in Bending", Journal of Structural Division,
ASeE, agosto, 1961), donde Fcres el esfuerzo crítico de pandeo en el alma. Si se
sustituye Fcr = 1.65Fb, se obtiene (redondeando ligeramente):

I = Fh pie lb seg: Fh [ 1 - 0.0005 -Aw ( -h - --760)] (10-6) Aj t Vii;,

(1O-6m) SI: F.'h = F.b [1 - O0005• AwA (!!:.t - ,~ j VFh1980)l

La revisión de la ecuación (10-5) indica que si

h 760 -\<-- t - ..¡¡;;

o el equivalente SI, no es necesario ninguna reducción en el esfuerzo en el patín
(es decir, F; = Fb) .

10-6.3 Requerimientos de cortante y atiesadores

Cuando la relación hit es suficientemente pequeña, no ocurrirá pandeo en el al-
ma debido al cortante antes de que ocurra fluencia debido al cortante. En reali-
dad, el alma de una viga, como parte de un miembro a flexión sometido a un mo-
mento flector, soporta el cortante a la manera de un "campo a tensión". Algunos
investigadores han comparado este efecto a una armadura Pratt, donde los

<!-- p. 535 -->

TEORIA DEL DISEÑO DE TRABES ARMADAS-Alse 53S

atiesadores (si los hubiera) son los miembros de compresión y el segmento de alma entre un par de atiesadores es el elemento a tensión, como se ilustra en la figura lO-l1a. Las pruebas reales de las trabes, llevadas hasta la fluencia de manera
que la costra de laminado forme líneas de esfuerzo, muestra un patrón de esfuerzos similar al idealizado en la figura lO-l1b.
Las almas de las trabes se diseñan según las especificaciones del AISC, suponiendo que el cortante lo soporta la acción de cortante de la viga -como en los
perfiles laminados- hasta que se alcanzan los esfuerzos cortantes de pandeo en el
alma; entonces, el cortante adicional lo soporta la acción del campo de tensión.
La resistencia última a cortante en un panel del alma (el espacio entre dos atiesadores) es igual a la suma de las dos contribuciones de cortante (Vbde la viga, y VI
del campo de tensión), o sea

(a)

La contribución de cortante en la viga es

(b)

La capacidad última de fuerza cortante de una trabe para la plastificación del alma (capacidad plástica) es

(e)

pero el esfuerzo cortante de fluencia Fys> según el criterio de von Mises es
F;, F =- (d) ys V3

(a)

Patín
\~-, atiesadoresI ///~ /í; ~ma,\,'" ~~ 'l / I~// /// -, '\'\ -:'\, ~'"-,
rrlion rnfrn
(b)

Figura 10-11 Analogía entre la trabe armada y la armadura Pratt. (o) Armadura Pratt ( -) =
miembro a compresión. (b) Viga armada con campo de tensión.

<!-- p. 536 -->

536 TRABES ARMADAS

De las ecuaciones (e) y (d), se obtiene A w, Ypor sustitución en (b),

(e)

Pero para valores de F'; -s 0.8Fys, se repite aquí el valor de F:" tomado de la
ecuación (3-5)

(3-5)

Si Fl, > 0.8Fys' al usar la ecuación (10-6), se tomará el esfuerzo crítico como el
valor medio entre la ecuación (10-6) y el valor de 0.8Fys, para obtener

(10-7)

y donde, como se definió previamente (véase tabla 3-2):

5.34 a k = 4.00 + Ji s 1.0
(ajhi
(10-8)
4.00 a k = 5.34 + Ji> 1.0 } (ajh)2

La fuerza cortante VI' por acción del "campo de tensión", se puede desarrollar basándose en la geometría del panel y la estática. Refiriéndose a la figura 1O-12b, el ancho del campo de tensión s será
s = h cos q, - a sen e (j)

La fuerza de tensión T w en el alma es

(g)

y la componente vertical V/ es
V, = T", sene = l,sl", sen o (h)

El mayor valor de V/ se obtiene tomando la derivada

dV, = O
dq,

<!-- p. 537 -->

TEORIA DEL DISEÑO DE TRABES ARMADAS-AISC 537

'11" '1
\ / 1
\~1 ) (

(al (bl

P,
F, = J,atw sen t/!
J,
\-'---1""--- N.A.
Tw
2

2
Tf + il Tf ------c- -----l r¡
(el
Figura 10-12 Distribución del esfuerzo cortante y de los "campos de tensión" en los paneles de la trabe. para la deducción de los esfuerzos cortantes permisibles, y de las dimensiones del atiesador. (o) Panel de la trabe, sometido a cortante. (b) Paneles de la trabe, sometidos a la acción del "campo
de tensión". (c) Esfuerzos y diagramas del cuerpo libre tomados de la base de los paneles de las trabes
que se muestran en (b).

Sustituyendo la ecuación (j) en (h), haciendo la derivada = O, y resolviendo para
fj), se obtiene

o tanq,= 1 + (0)2]1/2Ji -Ji [ (i)

Si se fijan los límites de a/h entre 0.5 y 3-0, los valores correspondientes de fj)serán de 9.2 a 31.75°, lo que constituye un rango razonable.
Usando el cuerpo libre de la figura 10-12c, el cambio en la fuerza del patín,
LiT¡, será

Li1J = F, cos q, = ftotw sen q, cos q, (j)

Tomando la EM = Oalrededor del punto Ode la figura lo-l2c se obtiene

(k)

<!-- p. 538 -->

538 TRABES ARMADAS

Igualando las ecuaciones (¡) y (k), Yusando la identidad

1 1 tan 4> 1 1 sen 4> cos 4> = -sen 24> = - ----'--
2 2 1 + tan 24> 2 [1 + (a/hff/2

se obtiene

(1)

Se pueden sustituir en la ecuación (a) las ecuaciones (1) y (e) y tomando hi; =
Vp / F'y. = Y3 Vp / Fy , se obtiene

v - V { r; V3 1, 1 } u - p F'ys + -2- Fy [1 + (a/ h)2f/2

Se puede hacer una aproximación de
1, = 1 _ F:r (m)
Fy e:
para obtener

Al dividir ahora por A w = ht.¿ usando un factor de seguridad de 1.67, Fys =
Fyl.J'f": y tomando Cv = F:JFys, se obtiene la ecuación de diseño del AISC
[ecuación (1.10-2)]:
F=-y-F{C+ l-C}v (10-9)
v 2.89 v 1.15[ 1 + (a/ h)2]'/2

Nótese que el término

1 - Cv

es la contribución del campo de tensión; por tanto, si el esfuerzo cortante real
r.c,
1.v \<--- 2.89

<!-- p. 539 -->

TEORIA DEL DISEÑO DE TRABES ARMADAS-AISC 539

no se requerirán atiesadores. Nótese también que cuando Cy > 1 [véase ecuación
(m)] solamente se usa el primer término de la ecuación (10-9) para tener el esfuerzo cortante permisible F; como

[AISCecuación (1.10-1)] (10-10)

Los términos C, se calculan por sustitución en las ecuaciones (3-5) o (10-7),
como sea más apropiado, para obtener:
Para Cy ~ 0.8:

F;, k1r2E v'3 45398k
Cv = F;,s = 12(1 - F;, = p.2)(h/tw)2 F;,(h/tw)2
El AISC usa
C = 45 000k pie lb seg: (10-11)
v F;,(h/ twi
C = 312 500k SI: (IO-llm)
v F;,(h/ twi
Para e, > 0.8
0.8F;,s k'TT2E v'3
Cv =
12(1 - p.2)(h/tw)2 F;,
El AISC usa
pie lb seg: C = 190h (10-12)
v t(k/F;,)1/2

SI: C = 500h (10-12m)
v t(k/ F;,)1/2

Las especificaciones del AISC limitan aún más el diseño de las trabes y el tamaño
de los paneles, como se indica a continuación:

l. Siempre se requieren atiesadores de asiento para las reacciones (y generalmen-
te, también bajo las cargas concentradas).
\2. No se requerirán atiesadores transversales intermedios (el AISC no tiene una
especificación para atiesadores longitudinales) si se cumplen simultáneamente
los dos criterios que siguen:

h- F;,Cv \< - 260 y 1.v \<--- 2.89 tw

<!-- p. 540 -->

540 TRABES ARMADAS

\3. Se requerirán atiesadores intermedios para cualquier otra condición de esfuer-
zo cortante. Cuando se requieran atiesadores, el espaciamiento se limita a

a (260)2 0.5 s Ji s h/tw

pero a/h :5 3.0.

\4. En las trabes diseñadas sobre la base de la acción del campo de tensión, el es-
paciamiento del primer atiesador interior, a partir del atiesador terminal de
apoyo, o cualesquiera atiesadores adyacentes a agujeros grandes, se determi-
nará en base al esfuerzo cortante dado por la ecuación (1.10-1) del AISC.

10-6.4 Flexión y cortante combinados (Revisión de la interacción)

Cuando una trabe está sometida simultáneamente a valores grandes de cortante y
'flexión, puede que sea necesario reducir los esfuerzos cortantes permisibles. Basler
desarrolló una solución para la interacción (véase "Strength of Plate Girders Under Combined Bending and Shear", Journa/ 01 Structura/ Division, ASCE, octubre, 1961) basándose en pruebas de trabes en la Universidad de Lehigh. El
AISC ha redondeado ligeramente los valores para obtener

0.375fv ) (10-13) 0.825 - --¡;:;- F;, s 0.6F;, r; s (

En general, no se requerirá revisar la interacción si
a) Iv :5 0.6FvYlb :5 O.6Fy
b) J, = Fv, pero lb :5 0.75Fb.

Cuando no se cumpla cualesquiera de estas condiciones, será necesario verificar
la interacción utilizando la ecuación (10-13), y posiblemente reducir el esfuerzo
permisible de flexión en el patín, Fb, con el uso de dicha ecuación.

10-6.5 Atiesadores intermedios

El diseño del atiesador se basa en la obtención de la fuerza vertical del atiesador,
basándose en P; = O, de la figura 1()"12c, para obtener

La sustitución de/t, \<p, y As! = PsiFperm dará

<!-- p. 541 -->

TEORIA DEL DISEÑO DE TRABES ARMADAS-AISC 541
A = 1 - CV {!!.. _ (a/h)2 }YDht (10-14) sI 2 h [1 + (a/h)2r /2 w

que es la ecuación 1.10-3 del AISC. Cuando Y = FysfFyw, para tener en cuenta el
uso de acero de un grado diferente de fluencia para el atiesador que para el alma,
D = factor para tener en cuenta la eficiencia reducida de un atiesador en un solo
lado del alma, o en ambos lados:

D 1.0 para placas de atiesarniento en ambos lados de la placa del alma
D 1.8 para un angular usado como atiesador en un lado del alma
D 2.4 para una placa atiesadora en un solo lado de la placa del alma

Con frecuencia, el área requerida para el atiesador es muy pequeña. Para
asegurar un atiesador suficientemente grande y rígido para mantener en forma el
alma de la trabe, el momento de inercia debe ser cuando menos

(10-15)

Usese h en pulg o m para obtener 1st = pulg' o nr'. Como el atiesador es un
miembro a compresión se debe respetar la relación mínima bit.
El atiesador se debe fijar al alma de tal modo que soporte alguna parte de la
carga vertical. La diferenciación parcial de la ecuación para P, con respecto a alh
dará

Usando Ey = FylE, un factor de seguridad de 1.67, Ysuponiendo que la fuerza del
atiesador se desarrolla en la distancia h13, a partir del patín a compresión, se ob-
tiene
3Ps = 3h(O.0IS) VF3/E
h 1.67 y

y con alguna manipulación adicional y un ligero redondeo, se obtienen las ecuaciones de diseño como

__ [( F;, )3]1/2 kips/pulg (10-16) h 340 pie lb seg: Jvs

__ [( F;, )3]1/2 kN/m (10-16m) h 6.5 SI: i;

Usese h en pulg o m.

<!-- p. 542 -->

542 TRABES ARMADAS

10-6.6 Atiesadores de apoyo

Se requiere que los atiesadores de apoyo sobre las reacciones estén siempre por
pares. Puede que se requieran atiesadores de apoyo bajo las cargas concentradas
que soportan las trabes armadas. Estos atiesadores se deben extender la distancia
total entre patines, y tener un estrecho contacto con el patín que entrega la carga.
El ancho del atiesador debe ser tal que se extienda aproximadamente hasta los
bordes exteriores del patín o los angulares.
Los atiesadores de apoyo se diseñan como columnas, con un área que incluye
el atiesador y un área central del alma de 12tw para los atiesadores terminales de
apoyo y 25 tw para los interiores (véase figura 10-13). Esta área se usa para calcular el radio de giro y para verificar los esfuerzos en la columna. Se puede tomar la
longitud efectiva del atiesador como O.75h debido a que está seguramente conectado al alma.
El área efectiva de apoyo, A;, se toma como el área fuera del filete del patín
del angular, o de las soldaduras del patín al alma.
El diseño requiere que se calcule L' Ir para encontrar el esfuerzo permisible
de la columna, Fa' y verificar

P = AFa ~ carga aplicada o reacción

AISCyAREA AASHTO

(Extremo) (Terminal)

b > lB,. I-bl..

(Terminal)

D o filete

(Intermedio)

Calcúlese L'Ir Calcúlese Llr = h/r
L' = O.75h
r = (1/ A)112
Ambos: Verifiquensecomo una columna, basándose en el área
sombreada de la sección Quese indicó antes.
Verifiquense el apoyo: úsese sólo el área de las placas A b = b;ts'
Verifiquense las relaciones bslts
Figura 10-13 Requerimientos de diseño de los atiesadores de apoyo, para las especificaciones indi-
cadas.

<!-- p. 543 -->

TEORIA DEL DISEÑO DE TRABES ARMADAS-AISC 543
Verifíquese también, usando el área efectiva de apoyo, A b = b;ts (figura 10-13),
para obtener

P = AbFbrg ~ carga aplicada o reacción

El esfuerzo permisible de apoyo, Fapoyo = 0.90Fy (AISC, sección 1-5.5) basándose en el menor valor de Fy , si el patín y el atiesador son de aceros con diferentes
grados de fluencia.

10-6.7 Aplastamiento del alma

Se requiere que las trabes armadas se proporcionen de manera tal que no ocurra
el aplastamiento del alma (el mismo fenómeno que en las vigas laminadas). Esto
se tiene en cuenta en las reacciones con el uso de atiesadores de apoyo. Cuando el
patín a compresión soporte una carga uniforme o cargas concentradas para las
que sea posible que no se requieran atiesadores de apoyo, el esfuerzo de compresión entregado por el patín al alma de la trabe, debe ser suficientemente bajo para
que no ocurra aplastamiento (En la figura 10-9b se ilustra el pandeo). Este es un
problema de estabilidad de una placa cargada en su borde, y se usará de nuevo la
ecuación (3-5) (véase Basler, "New Provisions for Plate Girder Design", Proceedings 1961 AISC National Conference, AISC, Nueva York), FS = 2.65, E =
29 000, y algún redondeo, para obtener el esfuerzo permisible a compresión en el
alma como

10 OOOkc pie lb seg: F= (10-17)
(h/ tw)2
68 90ükc SI: F= (lO-17m)
(h/twf

Basler sugiere (y el AISC lo requiere), para un patín que entrega una carga a
compresión al alma que está libre de rotar (sin restricción),

4 k =2+---
e (a/h)2

y para un patín que entrega una carga a compresión, restringido contra la rotación,

4
kc = 5.5 + 2
(a/h)

En las especificaciones del AISC, se combina directamente la ecuación (10-17) con
el valor apropiado de k; para presentar las ecuaciones de diseño.

<!-- p. 544 -->

S44 TRABES ARMADAS

Ejemplo 10-4 Diséñese una viga armada soldada para soportar dos colum-
nas que salvan el claro de un auditorio en un edificio de muchos pisos. Las
cargas sobre los pisos entregan una carga uniforme equivalentes de 2.8
kips/pie al patín superior (no se incluye el peso de la trabe). El claro y cargas
en general son como aparecen en la figura ElO-4a. Se supondrá contraventeo
lateral del patín a compresión, en los extremos y en las cargas concentradas.
Otros datos de diseño: Electrodos E60, especificaciones del AISC, acero
A-36, y el peralte de la trabe se limita a 84 pulg.

90 k 10Sk
JiS',,'¡i~ ,,,,,1,,¡i~ ~:~'¡:~" J,,,",::",,,,So
1- '1
Figura EIo-4a

SOLUCION Calcúlese las reacciones de la trabe:

RR = 17.5(90 + 2 x 105) + 53(2.8)53/2 = 17325 ki 53 . ps

R = 18(105) + 35.5(~~) + 53(2.8)53/2 = 170.15kips
L

IR = 343.4 kips

Se trazan a continuación los diagramas de cortante y momento como se
muestra en la figura EI0-4b.
Paso No. l. Hágase un diseño preliminar de la placa del alma.

170.15r- l.121 IS

¿1.15 6.375'
11.125' 17.85

122.85
'--

M
Figura Elo-4b

<!-- p. 545 -->

TEORIA DEL DISEÑO DE TRABES ARMADAS-AISC 545

Supóngase que el peralte del alma = 78 pulg. El h/t¿ para que no haya
reducción en el esfuerzo permisible a flexión en el patín es

h 760 760 . - = -- ao -- = 162 (aproximadamente)
t; VF; v'22
Obténgase, para hit = 162, t = 78/162 = 0.48 pulg. Pruébese tentativamente t; = 0.5 pulg.

,. h 14 000 322 maxlmo - = =
tw VF;,(F;; + 16.5)
78
tw(mín) = 322 = 0.242 pulg

Para t; = 0.5 pulg, hit = 78/0.5 = 156
Paso No. 2. Hágase un diseño preliminar de la placa del alma.

M A w A ao---
f fbh 6

\= 2722(12) _ 78(0.5) = 196 - 64 = 13 2 ul 2
21(79) 6 ., . p g

(Supóngase que!b ao 21 kips/pulg-, y una distancia promedio hasta el centro
del área del patín de 79 pulg.) Pruébese una placa para e! patín de 7/8 x 18
pulg.

b 18 ~ (AISC sección 1-9.1.2) \< Vi: 2tf = 2(0.875) = 10.3

Paso No. 3. Calcúlese e! momento de inercia real y el módulo de sección de la sección de prueba y revísense las dimensiones según se requiera.

(no se tenga en cuenta el lo de las placas de! patín
con respecto a su eje centroidal)

\= 0.5g8)3 + 2(0.875)(18)( 7; + 0.~75r
\= 19 773 + 48 992 = 68 765 pulg"
_ 68 765 68 765 _ 3
Sx - 78/2 + 0.875 = 39.875 - 1724.5 pulg

Calcúlese el peso de la trabe:

<!-- p. 546 -->

546 TRABES ARMADAS

w = 0;:0 (2 x 18 x 0.875 + 0.5 x 78) = 0.24 kips/pie

El momento flector adicional aproximado (calculado conservadoramente
puesto que el momento debido a las otras cargas está ligeramente fuera de
centro) es

0.24(53)2 .,
M = 8 = 84.3 pies • kips

El momento total a flexión = 2722 + 84.3 = 2806.3 pies » kips

f = M = 2806.3(12) = 1953 k'
Jb S 1724.5 . IpS

Como esto es considerablemente menor que 21 ó 22 kips/pulg-, se revisa ten-
tativamente el espesor del alma tw' hasta ~ pulg.

h 78 - = -- = 208 \< 322 Correcta t; 0.375
Revísese el cortante en el alma, de manera que la placa no sea demasiado del-
gada (no se tenga en cuenta aquí el peso de la viga):

173.25
Jo = 78(0.375) = 5.92 « OAF;, Correcta

Paso No. 4. Recalcúlese I y lb
Ixx = 14 829.8 + 48 992 = 63 822 pulg"
_ 63 822 _ . ul 3
Sx - 39.875 - 1600 P g
Nuevo ·peso de la trabe = 0;:0 (31.5 + 29.3) = 0.207 kips/pie

El momento adicional aproximado del momento debido al peso de la trabe es

M = 0.20~(53)2 = 72.7
M tota1 = 2722 + 72.7 = 2795 pie > kips
f - 2795(12) _ 2096 k' / 1 2 Jb - 1600 - . IpS pu g
Contínuese el diseño. Usense dos placas de patín de f x 18 pulg Yuna placa
de alma de í x 78.

<!-- p. 547 -->

TEORIA DEL DISEÑO DE TRABES ARMADAS-AISC 547

Paso No. 5. Compruébese el esfuerzo permisible Fb•
Calcúlese L/rn usando Iy del patín a compresión para el cálculo de rT'
El radio de giro se obtiene usando Aj + A w/6:

Iy
rT = A¡ + A•.J6

3
1 = bh = 0.875(18)3 = 425 25 ulz' y 12 12 . P 5
A¡ + ~w = 0.875(18) + 2~.3 = 20.63 pulg?

425.25
rT = 20.63 = 4.54 pulg

Es necesario investigar tanto el panel exterior como el interior (entre las dos
columnas) puesto que Cb es diferente en cada lugar. Para el panel externo:
L = 18 pies (el mayor valor), y mI = O, YM 2 = 2 664 pies. kips

Z~) + 0.3( 1.75 e, = 1.75 + 1.05( Z~r=
Para el panel interior: Cb = 1.0 (ya que el momento interior de 2 722 > 2 664
pies • kips).
!::- = 18(12) = 47.3 \< 53\!Cb rT 4.54

Para esta relación de L/rT, Fb = 0.6Fy = 22 kips/pulg- tanto para el panel
externo como el interno.
Se comprueba la ecuación 1.10-5 del AISC, ya que ñ/t; = 208 > 760/
\--J 22:

F' b = Fb 1 - 00005-'• AwA ( -th - --,,r;;-760)]
[ ¡ w V Fb
\= 22[ l - 0.0005( 12:'~5 )(208 - 162)] = 21.05 > 20.96 kips/pulg-

En este punto, el esfuerzo de flexión y las proporciones de la trabe son
adecuadas, a menos que una comprobación posterior de la interacción re-
quiera una revisión de la sección de la trabe.
Paso No. 6. Calcúlense los requerimientos de atiesadores.

<!-- p. 548 -->

548 TRABES ARMADAS

Las especificaciones del AISC requieren atiesadores de apoyo bajo las
reacciones y las dos cargas concentradas de las columnas. En el panel exter-
no, el esfuerzo cortante real bajo la reacción es
\=- V = 173.25 + 0.207(53/2) = 6.11 ki si ul 2 1.v Aw 0.375(78) . P P g
De acuerdo con la sección 1-10.5.3 del AISC, no se requieren atiesadores in-
termedios (además del atiesador exterior de apoyo) siempre que

\~ \< 260 y t -
Se proveerán atiesadores de apoyo bajo las cargas de las columnas, lo que
deja una distancia libre en el panel exterior de 18 pies, de 18 x 12 = 216
pulg.

h-=208\<260 Correcta
t;
a 216
Ji = 78 = 2.77 > 1
4 4 k = 5.34 + = 5.34 +-- = 5.986
(a/ h)2 (2.77)2

Suponiendo que Cv dará un valor \< 0.8, se probará la ecuación (l0-11):

C = 45 OOOk = 45 000(5.86) = 0.169 \< 0.8
v F/h/ tw)2 36(2082)

Si no se usan atiesadores intermedios el esfuerzo cortante permisible se limita a

r; = 36~;969) = 2.11 kips/pulg- «6.11 N.S. se requieren atiesadores

Pruébese un atiesador a la mitad de la distancia (fijándose en que si esto está
bien para el panel de 18pies, servirá también en el otro panel extremo de 17.5
pies).
216 a = -- = 108 pulg 2
a 108
Ji = 78 = 1.38 \< 3 (menor que el máximo alh permisible)

a 260 (260)2 -h s 2 = 208 = 1.56 > 1.38 Correcta
(h/ tw )

<!-- p. 549 -->

TEORIA DEL DISEÑO DE TRABES ARMADAS-AISC 549

4 k = 5.34 + --2 = 7.44
1.38
C = 45 000(7.44) = 0.215
v 36(208)2
Con atiesadores intermedios y Cv \< 1, se puede usar la ecuación (1.10-2) del
AISC, o la ecuación (10-9):

_ 36 [ 1 - Cv ] _ . 2 F; - 289 Cv + - 7.67 kips/pulg . 1.15(1 + 1.382) 1/ 2

Como 7.67 kips/pulg- es mayor que el esfuerzo cortante real de 6.11 kips/
pulg- en el atiesador de apoyo, y el cortante es menor en los puntos interiores, no es necesario comprobar más el esfuerzo cortante en el análisis del
atiesador. Nótese que se pudo haber obtenido F; de la tabla 11-8 del SSOD,
pero se requiere doble interpolación.
Paso No. 7. Compruébese la interacción en las cargas concentradas
ecuación (10-13).
A dx, a la derecha de la columna de la derecha, el cortante Ves
V = 178.4 - 18(2.80 + 0.207) = 124.6 kips (incluyendo el peso de la
trabe)

Para V = 124.6 kips, el esfuerzo cortante en el alma es

124.6 - 425 k' 1 -- IpS/pU g 2 29.3 -. 1.v

Se acaba de encontrar en el paso 6 que F; = 7.67 en el paso 6.

r, = [0.825 - 0.375( ~:~~) ]36 = 22.2 > 22 kips/pulg-

Como el esfuerzo permisible con interacción es de 22 kips/pulg- (máximo), y
los valores reales y permisibles, basados en la estabilidad del patín son menores, son los valores menores los que rigen.
Fb = 21.05 ksi fb = 20.96 kips/pulg-
Paso No. 8. Verifíquense los requerimientos del claro interior de 17.5
pies, entre columnas.
El cortante máximo se obtiene viniendo de la izquierda:

V = 170.15 + 0.207( 5}) - 17.5(2.8 + 0.207) - 90 = 33.01 kips

<!-- p. 550 -->

550 TRABES ARMADAS

\- 33.01 _ 1 13 ki 2 Iv - 29.3 -. ips/pulg

Pruébese sin atiesadores:
!!. = 17.5(12) = 269 3 O h 78 . \<.,
k = 5.34 + _4_ = 5.89
2.60/
e = 45 000(5.89) = 0.170
v 36(208)2

\- 36(0.170) _ 2 12 113 k· / 1 2 F¿ - 2.89 -. >. ips pu g no se requieren atiesadores

Paso No. 9. Verífiquese el aplastamiento kips/pulg- del alma bajo el
patín a compresión, debido a la carga uniforme.
Supóngase que el patín tiene restricción contra la rotación (ya que so-
porta una carga uniforme). La carga a compresión que soporta el alma es de
2.8 kips/pie + el peso del patín superior. No se tendrá en cuenta el peso del
patín, de manera que el esfuerzo a compresión es

I: = 0.3~~~12) = 0.622 kips/pulg-

El esfuerzo permisible de compresión es igual a (verificando en el lugar don-
de a/h es crítica)

F = 10 000 [5.5 + 4 ] [ecuación (10-17) combinada con kcl
(h/tw)2 (a/h)2
\= 10 000 (5.5 + _4_) = 1.4 > 0.622 kips/pulg-
2082 2.692
Nótese que si F \< Iv, habría que hacer una de estas dos cosas, o añadir
atiesadores para disminuir a/h, o aumentar tw•
Paso No. 10. Diseño de los atiesadores de apoyo e intermedios.
Para los atiesadores de apoyo en los extremos de la trabe (se usará el
mismo tamaño bajo las cargas de las columnas) (se probarán dos placas de
8 x 112 pulg, para un ancho (2 x 8 + 0.375 = 16.375 pulg) que se acerque
al ancho de la placa de patín de 18 pulg.
b 8 16~-95 -=.-= Correcta
t 0.5 ,¡¡;;

<!-- p. 551 -->

TEORIA DEL DISEÑO DE TRABES ARMADAS-AISC SS!

El área "efectiva" de la columna para el radio de giro (véase figura 10-13):

A = 16 X 0.5 + 12(0.375)(0.375) = 9.69 pulg-
_fl829 r = V9:69 = 4.34 pulg
L = 0.75h = 0.75(78) = 58.5 pulg
L = 58.5 = 13.5
r 4.34
De la tabla 11-5, el esfuerzo permisible en la columna es Fa = 20.98
kips/pulg-. El esfuerzo real en la columna es

2 ó k'ips/pu 1g Q -- 178.749.69 -- 1845. > 20 .9" f.

Compruébese el esfuerzo de aplastamiento; supóngase una soldadura de 5/16
pulg, de manera que el área efectiva de aplastamiento = (8 - 0.3125)(0.5)(2) =
7.7 pulg-:
F apeso = 0.9Fy = 32.4 kips/pulg-
Pe = 32.4(7.7) = 249.5:» 178.74kips/pulg2 Correcta

Para los atiesadores intermedios, con un solo atiesador intermedio, se
usarán dos placas.
A = 1 - Cv{!!. _ (a/h)2 }YDht [ecuación (10-14)] Si 2 h [1 + (a/h)2f/2 w

Para una placa en ambos lados del alma de la viga, D = 1.0 e Y = 1 (acero
A-36 tanto para el alma como para el atiesador; C = 0.215 y a/h = 1.38, del
paso 6.

2
A 1 - 0.215 [1.38 _ 1.38 ](1)(1)(29.3) = 3.02 pulg- sI = 2 (1 + 1.382) 1/ 2

En términos de A st x 100/A w, se hubiera podido obtener este valor en la
tabla 11-8, usando doble interpolación. Pruébense dos placas de 3/8 por 6
pulg:

<!-- p. 552 -->

552 TRABES ARMADAS

A = 2(~ X 6) = 4.5 pulg-' > 3.02 Correcta
tb -_ 0.3756 -_ 16 Correcta

El momento mínimo de inercia de los atiesadores es

( ( 5.92 pulg" 5~r= ~~r=
1 .. - (0.375)(12 + 0.375)3 = 5922 l 4 »592 Correcta suministrado - 12 . pu g .

Úsese una longitud de placa para el atiesador
h - 4tw = 78 - 4(0.375) = 76.5 pulg

Paso No. 11. Diséñese la soldadura para fijar los atiesadores al alma.

kips/pulg [ecuación (10-16)]
36 )3]1/2 = 78 340 = 2.7 kips/pulg [(

Para un par de atiesadores, se tiene 2.7 kips/pulg; esto resulta, para cada la-
do 2.7/2 = 1.35 kips/pulg.
Para atiesadores de apoyo de 1/2 pulg, se usará soldadura de 3/16 pulg.
y electrodos E60.
F; = 0.1875(0.70711)(0.3 X 60) = 2.39 kipsy'pulg
Se usará una soldadura de filete continua de 3/16 pulg, tanto para los atiesa-
dores de apoyo como para los intermedios.
Análisis razonado: Se pueden hacer pocos atiesadores y la soldadura en
un solo pase. Resulta muy difícil medir y establecer distancias alternas de sol-
dadura y espacios libres.
Paso 12. Diséñese la soldadura para fijar la placa del patín al alma.
Compruébese el máximo cortante en el extremo:
VQ 178.74(18 X 7/8)[(78 + 0.875)/2] .
v = -¡- = 63 822 = 1.74 kíps / pulg

Usese una soldadura continua de 5/16 pulg (ti> 3/4 pulg), en ambos lados
y para Fw = 3.98 kips/pulg. Nótese que hay un considerable sobrediseño en
la soldadura, pero para una trabe importante no vale la pena ahorrar con sol-
daduras intermitentes - particularmente si se puede hacer la soldadura con
un solo pase, como sucede aquí.

<!-- p. 553 -->

TEORIA DEL DISEÑO DE TRABES ARMADAS-AASHTO 553

105"_~_105"._--+ 210" 4-_108" 108" 8.75' -1- 8.75' -1- 17.5' '1· 9' -~-,1- 9'

Figura EIO-4c

En la figura ElO-4c se muestra el resumen del diseño de la trabe. / / /

10-7 TEORÍA DEL DISEÑ O DE LAS TRABES
ARMADAS-AASHTO y AREA

El diseño de las trabes armadas usando las especificaciones del AASHTO y el
AREA es muy semejante, pero más conservador, que el del AISC debido al ambiente más hostil al que estará sometida la trabe. Sin embargo, se aplican las mismas consideraciones generales:

\1. La trabe se proporciona por el método del momento de inercia.
\2. No es posible una solución única.
\3. Los requerimientos para cortante y atiesadores son más rígidos. Siempre se re-
querirán atiesadores de apoyo, pero la AASHTO permite el uso de atiesadores
longitudinales.*

10-7.1 Los patines de las trabes (AASHTO y AREA)

En general, el esfuerzo permisible básico a flexión es

Sin embargo, si el patín a compresión no tiene apoyo lateral en una longitud L, se
deben reducir los esfuerzos como en la Parte III del SSDD, y en la especificación
apropiada.
Se limita también la relación b/Lt¡ para los patines:
AASHTO:

\* También en el AREA, pero para trabes continuas.

<!-- p. 554 -->

554 TRABES ARMADAS

pie lb seg SI
b 51.4 b 135 -\<-- -\<-- 2t¡ - y¡;, 2t¡ - y¡;,

El valor límite de b/2tr = 12 para acero A-36, cuando lb = Fb = 0.55 Fy-
AREA:
Cuando los durmientes descansan directamente sobre el patín de la trabe:

b 60 b 160 -\<-- -\<-- 2t¡ - 2t¡ - y¡;; y¡;;

El valor límite de b/2tj = 10 para acero A-36.
Cuando los durmientes no descansan directamente sobre el patín de la trabe:

b 72 b 190 -\<-- -\<-- 7.t¡ - 2t¡ - y¡;; y¡;;

El valor límite de bl2tj = 12 para acero A-36.

10-7.2 Diseño de la placa del alma

La AASHTO usa también la ecuación (3-5):

y resolviendo para h/tw> sustituyendo k; = 23.9, E = 29000, y Fcr = 1.19Fb , se
obtiene
h 727 pie lb seg: -=-- (10-17) t; y¡;,
Esto da b/t; = 163 para acero A-36.
La relación límite de h/t¿ para el AREA se obtiene de la ecuación (3-5) por la
sustitución de k¿ = 23.9, E = 29000, y Fcr = 0.6Fy para tener (con un ligero re-
dondeo)

h 1030 pie lb seg: -=-- (10-18)
tw y¡;;

<!-- p. 555 -->

TEORIA DEL DISEÑO DE LAS TRABES ARMADAS-AASHTO SSS
Para el acero A-36, el valor límite de h/r; = 171. Cuando el valor delb \< Fben
el patín a compresión. el AREA permite un aumento en la relación hltw:

La AASHTO y el AREA limitan el espesor del alma en las trabes armadas a:

\~ 0.335 pulg (8.5 mm) AASHTO: t; ~ 5/16 pulg (8 mm) AREA: tw

La AASHTO permite que se aumente el límite de h/t; con un atiesador longitudinal a l/5 del peralte libre del alma, a partir del patín a compresión. Este valor se basa en la ecuación (3-5), usando k¿ = 129(ya que así permite una fijación
más sustancial en el borde) y Fcr = 1.6Fb, para obtener

h 1455 h 3840 pie lb seg: -\<-- SI: -\<-- (10-19) -- y¡" t; - y¡" tw

El valor límite de n/t; para el acero A-36 es 327.

10-7.3 Requerimientos del cortante y de los atiesadores

Los requerimientos del AASHTO para los atiesadores se calcula también con la
ecuación (3-5) y los factores k que vienen dados por la ecuación (10-8), y con fac-
tores de seguridad variables. Si la placa es tal que alh - 00 (no hay atiesadores),
k¿ = 5.34 de la ecuación (10-8), y tomando Fcr- 2.5Iv, se obtiene

h 234 h 618 pie lb seg: -\<-- SI: -\<-- (10-20) i; - VT., t; - VT.,

El valor límite de hltw = 68 para el acero A-36, cuándo Iv = F; = 0.33Fy-
Los requerimientos del AREA son ligeramente más conservadores:

h 360 pie lb seg: -\<-- SI: (10-21) tw - Vi;

El valor límite de h/t; = 60 para el acero A-36.
No se requerirán atiesadores intermedios, por ninguna de las dos especificaciones, si la relación h/twes menor que la que viene dada por la ecuación (10-20)o
la (10-21), y puede que no requieran para relaciones hltw mayores, como se indica
en la siguiente sección.

<!-- p. 556 -->

556 TRABES ARMADAS

Cuando h/w, es mayor que los que dan las ecuaciones precedentes, se obtiene
el espaciamiento de los atiesadores usando la ecuación (3-5) después de reordenarla un poco, para obtener

de la que

Usando FS = 1.5, varias relaciones a/h de 0.5 a 1.0, y calculando k¿ de la
ecuación (l0-8), se obtiene típicamente

a/h k fJ

0.5 25.36 332.8
0.6 18.83 344.4
0.7 14.90 357.2
0.8 12.30 370.9
0.9 10.58 387.2
1.0 9.34 404.0

Con un promedio aproximado de {3 se obtiene 348, que al usarlo para recalcular
el FS, se tiene 1.37 para a/h = 0.5 hasta 2.02 para a/h, = 1.0. En las primeras especificaciones de la AASHTO, se podía calcular el espaciamiento de los atiesado-
res como

3481 9141 pie lb seg: a=-- (pulg) SI: a=-- (mm)
vi -r:
donde t tiene unidades en pulg o mm. Las dos ediciones anteriores de las especifi-
caciones del AISC incluían este requerimiento para espaciar el primer atiesador
interior, a partir del atiesador de apoyo. Comúnmente, las especificaciones de la
AASHTO para atiesadores intermedios son algo más indirectas y se dan en la sec-
ción 10-7.4 que se verá a continuación, bajo el subtítulo"Atiesadores interme-
dios" .
Las especificaciones del AREA reducen ligeramente el factor 348 para obtener

3321 8751 (pulg) SI: a=--·
v: (mm) (10-22) pie lb seg: a = ---r:

<!-- p. 557 -->

TEORIA DEL DISEÑO DE LAS TRABES ARMADAS-AASHTO 557

En estas ecuaciones t tiene sus unidades en pulg o mm. El espaciamiento de los
atiesadores se limita a no más de 72 pulg o 1 800 mm, cuando se use la ecuación
(10-22).

10-7.4 Diseño de los atiesadores

Atiesadores longitudinales El valor de la AASHTO para los atiesadores longitudinales en términos del momento de inercia es (véase Erickson y Ecnam. "Application and Development ofAASHTO Specificaüons to Bridge Design", Journal
of Structural Division, ASeE, julio, 1957)

(10-23)

con el espesor de la placa limitado a

b 188 pies lb seg: SI: -\<-- (10-24) t - y¡;,

donde I» = esfuerzo de flexión calculado en el patín a compresión. Los atiesadores se pueden colocar en un lado del alma, a 1/5 de la distancia del patín a
compresión. El AREA permite atiesadores longitudinales en las trabes continuas
en las regiones de momento negativo y las especificaciones son exactamente las
mismas que las de la AASHTO para Is Ybit.

Atiesadores de apoyo. La AASHTO y el AREA requieren siempre atiesadores de
apoyo en las trabes. Se diseñan como columnas, con un área como la que muestra
en la figura 10-3. El esfuerzo permisible de columna depende de la relación Llr
calculada como se muestra en la figura 10-13. Los atiesadores de apoyo se deben
verificar para el aplastamiento así como en su actuación como columnas. El área
de aplastamiento es la que se indica en la figura 10-13 y el esfuerzo permisible de
aplastamiento es

AASHTO: Fbrg = 0.80Fy AREA: Fbrg = 0.83J\.

Las especificaciones de la AASHTO limitan la relación bslts de los atiesado-
res de apoyo (usando angulares o placas) a

b, 69 pie lb seg: - \< -- SI: (10-25)
ts - Vi:

Los requerimientos del AREA para la relación bs/ts son los mismos que para
cualquier otro miembro a compresión.

<!-- p. 558 -->

5511 TRABES ARMADAS

Atiesadores intermedios. La AASHTü no requiere atiesadores intermedios transversales si
h- \< 150 y tw -
donde
pie lb seg: F = 56 250 SI: F = 387 830 (10-26)
v (h/ tw)2 v (h/ tw)2
pero F, :::; F'y/3. Este criterio da como límite h/t; = 68 para F, = F'y/3 con acero
A-36. Así, cualquier relación ñ/t; que sea menor que 68 no requerirá atiesadores
transversales sifv \< FJ3. Cualquier n/t; \< 150 no requerirá atiesadores si], \<
F; como viene dado en la ecuación (10-26).
Cuando se requieran atiesadores intermedios, o cuando r, > F; de la ecuación
(10-26), el espaciamiento máximo se limita a a :::; 1.5h, Yel esfuerzo cortante permisible se limita a

F = F,. { C + 0.87(1 - C) } (kips/pulg- Ó MPa) (10-27)
v 3 [1 + (a/hif/2
B[t + (h/a)2]
donde C= \< I
Fih/ tw)2 -
B = 222 000 en unidades p lb seg:
\= I 520 000 en unidades SI

A menudo es conveniente hacer una gráfica de dichos esfuerzos, como se ve en la
figura 10-14.
Cuando se requieran atiesadores transversales, se colocará el primer atiesador de tal manera que a/h :::; 0.5 yel esfuerzo cortante realj, :::; F: se obtiene de la
ecuación siguiente:

(10-28)

donde B' = 70 000 en unidades pie lb seg:
\= 483 000 en unidades SI

Las especificaciones de la AASHTü requieren un momento mínimo de inercia
para los atiesadores intermedios (incluyendo otros distintos de los atiesadores de
apoyo en las reacciones) de

at 3 1 = w J (10-29)
s 12(1 - /-12)

<!-- p. 559 -->

TEORIA DEL DISEÑO DE LAS TRABES ARMADAS-AASHTO 559

v~y/3 ~ 83.k
r-, 1""1: r-, 1". 80 "- """ ....."" 1\'1\. ~ r-............ 1"-.....r-, ~r-. r--.... """-t-.. a/h"'05 r--,.;.;;.: "
0.6 \ r-, l'r-, ............ I'-¡...T"-~ loo.... r-r- t--""- 70 ro-.t- -. 0.7 \<, r-, """r--.... I'-¡... T"-"- ro--"""-t--.... ~ ;r: ....... ..... .......r--..... j'..... r-1-- ¡......:~ 60~ \<, r--.... r-1-- f-.. " 1.0
\~ '¡;; , 1.20 r- """- .~ 50 I
e. 1.50 Esfuerzo cortante para "-""- el alma de las trabes _ ~" 40 90\ 1-- Para el primer atiesador" s);
intermedio en los extremos :su \. sin atiesadores trans~ersa\esI I ... Q/4 ' o '\.. I I I I diela ~rabel ...."1"'0 hlt.; ....---Máxima relación I I t::.2 30 ..... ..;.:5 '- sin atiesadores ,,1 1 .. I I I I I 1 ..... tU Máxima relación h/tw para aquellas vigas que no tengan_
atiesadores longitudinales del alma \<, ,,-
20 \<,

10
100 120 140150160 165180 200 220 240 260 280 300
Relación h/tw
Figura 16-14 Esfuerzo cortante permisible para las relaciones h/tw mostradas, y para las relaciones
a/h del espaciamiento de los atiesadores. Nótese que el esfuerzo cortante limite es Fy/3.

donde JI- = 0.3 para el acero
a = separación real de los atiesadores
tw espesor de la placa del alma en la trabe
\~ 5.0 J = 25(h/a)2 - 20, pero J

El área requiere atiesadores intermedios si la relación ñ/t; es mayor que los
valores definidos por la ecuación (10-21). Si se requieren atiesadores, su separación se limita a

332tw a\<--~0.875tw
a\<---Vi, (pulg) Vi, (m)

pero a $ 72 pulg (ó 1.829 m),
donde tw espesor del alma de la trabe, pulg o mm.
r. = esfuerzo cortante real en el alma = V/dtw, kips/pulg- o MPa

Las dimensiones del atiesador deben ser cuando menos las siguientes:

\~ brl4 AASHTO: ancho ~ 2 pulg + DI30 y ancho

<!-- p. 560 -->

560 TRABES ARMADAS

\~ b¡14 ~ 51 mm + DI30 y ancho
espesor ~ ancho/16
AREA: igual que para la AASHTü

10-7.5 Interacción

Las especificaciones de la AASHTü incluyen una reducción en el esfuerzo de flexión si el esfuerzo cortante esIv :5 0.6Fvde acuerdo con

\~ 0.55F;, (10-30) FbI = ( 0.754 - --¡;:-0.34j,,) F;,

10-7.6 Soporte lateral y diafragmas

En las figuras 10-15y 10-16 se ilustra el uso de soportes laterales y diafragmas en
la práctica común. Las especificaciones de la AASHTü requieren o marcos transversales o diafragmas en los extremos y a intervalos a lo largo del claro que no excedan de 25 pies (7.62 m). Los diafragmas (vigas transversales) deben tener un peralte cuando menos de un tercio y preferiblemente de la mitad o más del de la trabe.
Cuando los claros excedan de 125pies (38.1 m) en los puentes de concreto de
tablero superior, se usará un sistema adicional de soporte lateral, paralelo y tan
cerca como sea posible del patín inferior y cuando menos en un tercio de las
crujías (cuando se utilizan trabes múltiples). El angular más pequeño permitido
por la AASHTü para esta situación es de 3 x 24 pulg (76 x 64 mm) sujeto con
dos tornillos por lo menos, o la soldadura equivalente, en cada conexión terminal
de los angulares.

(al (b)

Figura10-15 Soporte lateral de los puentes usando diafragmas. (a) Diafragmas usados con cinco tra-
bes armadas. (b) Diafragma terminal. Se debe colocar suficientemente separado del diafragma adya-
cente o del estribo de apoyo para que se pueda inspeccionar y pintar periódicamente.

<!-- p. 561 -->

TEORIA DEL DISEÑO DE LAS TRABES ARMADAS-AASHTO 561

(a)

(b)

(e)
Figura 10-16 Contraventeo longitudinal y transversal. Nótese el uso de atiesadores verticales y longitudinales. El puente que está detrás en (e) es más viejo y usa construcción remachada, mientras que el
puente que está en primer término está todo soldado. Las tres trabes soportan una calzada de cuatro
vías además de las banquetas y acotamientos en ambos puentes. (a) Contraventeo transversal. (b) Detalles de fabricación. Nótese que las placas del sujetador terminal están soldadas tanto al alma como al
patino En los puentes continuos estas placas proveen puntos de soporte para el patín. (e) Uso de
contraventeo tanto transversal como longitudinal en la armadura. Nótese el atiesador longitudinala
lo largo del patín a compresión, donde hit w resulta excesiva.

El AREA requiere lo siguiente:

\1. Para vigas o trabes menores de 42 pulg (1066 mm), se usarán diafragmas en
forma de 1(vigas transversales) con el mayor peralte que sea práctico, y usan-
do conexiones a la viga de doble angular,
\2. Para trabes con un peralte mayor de 42 pulg y espaciadas a más de 48 pulg
(1 220 mm) centro a centro, se usará un sistema de soporte lateral de marcos
transversales en los que el ángulo 'de las diagonales con la vertical no es mayor
de 60°.
\3. La separación de los diafragmas o marcos transversales será
18 pies (5.5 m) para la construcción de puentes de tablero abierto
12 pies (3.65 m) para puentes de tablero con balasto
\4. Cuando el tablero con balasto se apoyo sobre vigas transversales sin largueros
de piso (como en la figura 10-5), se ha de usar cuando menos una línea de
diafragmas longitudinales, como se muestra en la figura lo-3d.
\5. Se requieren cartelas para soportar el patín a compresión de las trabes de
puentes de paso a través. Estas cartelas (véase figura 10-17)se colocan general-
mente en atiesadores intermedios seleccionados para la facilidad de fijación, y

<!-- p. 562 -->

562 TRABES ARMADAS

Figura 10-17 Soporte lateral del patín superior usando una placa de alma y una cartela, en el puente
de ferrocarril de tablero oon balasto y paso a través de este puente se muestra en la figura 10-4.

varían en pendiente de cerca de 3V:lH a pendientes un poco menores. El espa-
ciamiento máximo se limita a 12 pies (3.66 m). Se puede diseñar como una co-
lumna para una fuerza axial basada en que su componente horizontal sea del
2 t por ciento de la fuerza sobre el patín a compresión

La aproximación de la fuerza axial usando el seno definido por H y V, más
bien que la longitud actual es suficientemente exacta para el diseño.

Ejemplo 16-5 Diséñese una trabe soldada para un puente de ferrocarril de
tablero con balasto y paso a través de una sola vía, para un claro de27.5 m.
Usese la Carga Cooper E-lIO, acero A.36, electrodos E70 y las especifica-
ciones del AREA. La configuración general del puente es como se muestra
en la figura ElO-Sa.

SOLUCION De la tabla 1-2, la carga viva de diseño para la mitad de la vía
(una carga de riel por trabe) y ajustada para carga E-lIO es:

M = S339.1( 1;~) = 7341 pies. kips x 1.36 = 9984 kN . m

<!-- p. 563 -->

TEORIA DEL DISEÑO DE LAS TRABES ARMADAS-AASHTO 563

Pasarela r- 19' > L/20 _
5791 mm

\~:irrr~
f Placa de cubierta de 15 mm ¡ I"'II:+~!::I: Dla. ragrnas
o ~JL!.~ \ e=_=

Vigas transversales a 2.5 pies
(760 mm)

Figura EIO-Sa

El cortante es
V = 274.5( 18~) = 377.4 kips x 4.45 = 1680 kN

El factor de impacto (véase figura EIO-5a) se calcula, basándose en L > 25
como
30.5 185
I = 19 + 16 + 27.5 _ 9 = 27.6 úsese 28 por ciento

(Nótese que este factor de impacto no es el mismo que se usa en el ejemplo
4-15.) El momento de diseño
Md = 9984(1.28) = 12 779.5 kN . m
El cortante de diseño
Vd = 1680(1.28) = 2150.4 kN

No se tendrá en cuenta la carga viva en la banqueta para peatones y de servi-
cio. Haciendo esta suposición, la estimación de la carga muerta será
Peso de la trabe (incluyendo los atiesadores y la soldadura) 10.0 kN
Balastro, incluyendo durmientes con un peralte de 350 mm
y un ancho efectivo reducido: 120(9.807/62.4)(0.350)(4.4212) 14.6 kN
Tablero de acero y vigas transversales y un factor de 1.10
Del ejemplo 4-15, la viga es una W760 x 160.7/1.58
Tablero: 0.015(77 .0)(6.49)(1.10)12.0 4.1 nK
Vigas transversales: 37(1.58)(5.79)/(27.5 x 2) 6.2 kN
Vía a 200 lb/pie: 0.200 x 14.59(Especificaciones del AREA) = 2.9 kN
Banqueta: estimado, 300 lb/pie = 0.300 x 14.59 4.4 kN

Total = 42.2kN

<!-- p. 564 -->

S64 TRABES ARMADAS

Nótese que se ha efectuado cierta aproximación en el tablero de acero para for-
mar la depresión para el balasto y tener una longitud efectiva de 6.49 m. Nótese
también que se aplica un factor estimado en 10 por ciento para tener en cuenta
otras incertidumbres. El momento por carga muerta es
M = wL2 = 42.2(27.5)2 = 3990 kN . m
8 8

El cortante de carga muerta (en reacción) es
v = wL = 40.2(27.5) = 553 kN
2 2
El momento total de diseño es
M diseño = M L + Mrnuerta= 12 780 + 3990 = 16 770 kN . m
Vdiseño = VL + Vrnuerta = 2150.4 + 580 = 2730.4 kN

Paso No 1 Encuéntrense las proporciones de la trabe.
Tómese h ~ 2 134 - 2(50) ~ 2 034 mm. Además, el alma debe tener cuando
menos
t ~ ~ ~ 2730.4 = 15.3
w hFv 2.034(0.35 x 250) mm

El cortante máximo es en la reacción, pero con una carga móvil que es causa
de los mayores efectos (con impacto), no cambiará mucho en cierta distancia
a lo largo de la trabe, de manera que se tomará tw = 16 mm.

!!.... ;;;; 2034 = 127 «170 Correcta
t; 16

El área tentativa del alma
Aw = 0.016(2034) = 32.54 x 10- 3 m2
Usando la ecuación (10-2), se encuentra el área tentativa del patín como

_ 16 580 32.54 -3 2
A¡ - 2034 x 0.5F;, - -6- = 65.21 - 5.42 = 59.79 x 10 m

Pruébense dos placas de patín de 70 X 815 mm (t está disponible solamente en
incrementos de 10 mm):

h = 2134 - 2(70) = 1994 mm
J!.... = 815 = 5.82« 190 Correcta u, 2 X 70 ,¡¡;;

<!-- p. 565 -->

TEORIA DEL DISEÑO DE LAS TRABES ARMADAS-AASHTO 565

h 1994 - = -- = 125« 170
t; 16

Paso No 2. Calcúlese el momento de inercia de la trabe y determínese
el esfuerzo real de flexión, fb' de manera que se pueda verificar fb:5 Fb.
_ 2 b¡t]
t, - /alma+ 2Ar! + 12

\= 1()6(0.01~~(1.994)3 + 2(0.070 X 0.815)(997 + 815(0.~~0)3103 7~r+
\= 10 571 + 121 510 + 24 = 132 114 X 10-6 m"

El módulo de sección es

_ / _ 132 114 _ -3 3
S, - d/2 - 1067 - 123.81 X 10 m

El máximo esfuerzo de flexión correspondiente es

M 16 770
\~Pa \< 137.5 (Correctahasta ahora) fb = Sx = 123.81 = 135.4

Paso No 3. Compruébese el peso de la trabe.
Atotal = 2(0.070)(0.815) + 0.016(1.994) = 0.1460 m2
Wt/m = 77(0.1460) = 11.2 kN/m

Pruébese una placa de alma de 16 x 1 994 mm y dos placas de patín de 70 x
815 mm.

/x = 132 114 X 10-6 m"
S; = 123.81 X 10-3 m3

Paso No 4. Calcúlese el esfuerzo permisible de flexión, Fb•
El patín a compresión estará soportado lateralmente con carteles. como
se ve en la figura 10-17, en cada cuarta viga transversal que soporta el tablero.
Estos intervalos son aproximadamente 4(0.76) = 3.04 m \< 3.66 (máximo se-
gún el AREA). El radio de giro del patín a compresión es

r = ( /f)I/2 = ( /f )1/2
T A Af + Aw/6
Area del patín = 0.070 X 0.815 = 0.05705 m2
\~ 0.016 = 0.0052 m2 total = 0.06237 m2 A¡ = 1.994

<!-- p. 566 -->

S66 TRABES ARMADAS

\~g = = 0.070 ~20.8153 = 0.003158 m" 11
0.003158)1/2 rT = ( 0.06237 = 0.225 m = 225 mm

.!::... = 3.04 X lW = 13.5 \< 282
rT 225 Vi;

El esfuerzo permisible de flexión es
r, = 0.55~[1.0 - ~ (.!::...)2] = 137.0MPa > 135.4 Correcta 12.5 X 106 rT

Paso No 5. Diseño de los atiesadores de apoyo.
Se doblará el patín superior alrededor del extremo de la trabe para pro-
porcionar resistencia adicional del campo de tensión en el poste terminal,
como se muestra en ambas figuras IQ-Ic y 10-5. El atiesador será como el de
la figura EIO-5b.

b 190 -\<-- b = 815; 16 = 399.5 mm
t, - Vi;

Reordenando, t5 = 399.5Vi; /190 = 32.2; use 35 mm.

Asl = 2(0.3995)(0.035) + 0.192(0.016)
\= 0.031Om2
El momento de inercia del atiesador es

\= bt] = 0.035(0.815i = 000158 4 1st 12 12 . m

Figura Et6-Sb

<!-- p. 567 -->

TEORIA DEL DISEÑO DE LAS TRABES ARMADAS-AASHTO 567

El radio de giro es
0.00 158 )1/2 r = ( 0.0310 = 0.2257 m = 226 mm
L' = 0.75(1994) = 662
r 226 .

El esfuerzo permisible como columna para esta Llr es

KL F;, )1'5 ~ = 145.3 MPa > 0.55F;, Fa = 0.60F;, - ( 316

La carga permisible como columna es
Pcol = 0.551';,(31.0 X 10-3 m2) = 4262 kN» 2730.4 Correcta

Verifíquese también el atiesador de apoyo, para el "aplastamiento", y supóngase un filete de soldadura de 6 mm para la reducción de área.
Abrs = (2)35(0.3995 - 0.006) = 27.55 x 10- 3 m2
Pbrs = 27.55(0.83 X 250) = 5717 kN »2730.4 Correcta

Paso No 6. Diséñense los atiesadores intermedios (tanto la sección como el espaciamiento).
La distancia libre a se limita a

0.872tw
a = v: ::; 1.828 m (el AREA limita la separación a 72 pulg)
En el atiesador de apoyo
V 2730.4
Jv = ht = 1994(0.016) = 85.6 MPa \< O.35F;, Correcta
Este valor deIv resulta en una separación permisible de
a = 0.872(16) = 1.51 m \< 1.828 Correcta
Y85.6
Se puede hacer una de dos cosas:

\1. Colóquense todos los atiesadores con aproximadamente esta separación
(pero de tal manera que resulten distancias en números enteros).
\2. Usese esta separación para cada uno de los extremos del puente y una se-
paración mayor para el interior, ya que la carga viva (sin impacto) es de
701 kN (tabla 1-2). Similarmente, el cortante por carga muerta es sola-
mente 1/2 del valor en el extremo.

<!-- p. 568 -->

568 TRABES ARMADAS

Investíguese ahora la separación para la mitad central aproximada del
claro:
Carga viva = 764 X 1.28= 1234kN
Carga muerta = 580/2 = 290 kN
Total = 1524kN

y
\= 1524 _ 47 8 MPa 1.0 1994(0.016) - .
a = .872(16) = 2.01 m > 1.828 máximo
Y47.8

Se usará la separación como se muestra en la figura ElO-5c.
Usese un par de placas atiesadoras para cada atiesador intermedio.
b > 50 + .!!... = 50 + 2134 = 121 mm úsese b = 125 mm s - 30 30 •
b, 125 . t. ~ 16 =16 = 7.8 usese ts = 8.5 mm (Espesor mínimo según el AREA)

Paso No 7. Diseño de la soldadura entre el patín y el alma.
Las especificaciones del AREA permiten o bien soldaduras de ranura de
penetración completa o si no soldaduras de filete; cualesquiera de las dos de-
be ser continua. Se usarán arbitrariamente soldaduras de ranura de penetra-
ción completa. Para este tipo de soldadura solamente se tendrá que compro-
bar el cortante producido y compararlo con el valor máximo permisible para
electrodos E70.

Q = AJy = 0.070(0.815)(997 + 7~)
\= 58.88 X 10-3 m3
\= VQ = 2730.4(58.88 X 10- 3 ) = 1216.6kN/m
v 1 0.132114

67 X 840

('1 ._ oo
\- ">t ~
X X X
V) v;
00 "'1 ~

7.5 7.5 m m m . I ¡T.5 --1 I
(u 1500 7 (a 1785 • • S (~ 1500---¡ mm" 1- S

Figura EIO-5c

<!-- p. 569 -->

TEORIA DEL DISEÑO DE LAS TRABES ARMADAS-AASHTO 569

La resistencia a cortante se limita a
F, = 0.35F;,Ashear = 0.35(250)(0.016)(1 m) X 103
\= 1400kN/m > 1216.6 Correcta

Paso No 8. Compruébese la deflexión.
Suponiendo que el momento por carga viva se debe a una carga equiva-
lente uniforme, se obtiene

8M
w =- L L 2
Y la carga total uniforme equivalente, W3' es
w = w + w = 42.2 + 8(12 780) = 177.3 kN/m
e D L 27.5 2
La deflexión es aproximadamente
5wL4 5(0.1773)(27.5)4
A = 384EI = 384(200 000)(0.132114) = 0.04996 m (sea 50 mm)

.A 43 mm ;;,: 50 mm (considérese correcta) rnáx = 27.5(1000)640 =

Paso No 9. Diseño de la cartela del patín superior.
Se colocará arbitrariamente una cartela en cada cuarta viga de piso, con
una separación de 4(0.76) = 3.04 m. Cuando coincida, o esté "bastante cer-
ca" de un atiesador, se aumentará el espesor del atiesador de 8.5 mm a 12
mm. Para cualquier placa aislada de soporte lateral, se usará una placa de
12 mm. Se soldará en el taller la placa de cartela o el atiesador al alma de la
trabe y al patín a compresión como se muestra en la figura EIO-5d. Se solda-
rá en el campo la parte inferior de la placa atiesadora con la viga transversal.
Se soldará en el taller el angular de la cartela y se punzonarán los huecos para
tres tornillos de alta resistencia de 22 mm, en cada extremo. Tómese la com-
ponente horizontal de la fuerza del atiesador

Fh = 0.025fbA¡ = 0.025(135.4)(0.070 X 815) = 193kN

193 _ 579 kN P kb = 1220/ (3)(1220) -

El número de tornillos A-325 de 22 mm a doble cortante requeridos para
la componente horizontal de la fuerza del atiesador, para fijar este último a la
viga de piso es igual a

N = 193 = 1.83
(0.7854 X 0.0222)(138 X loJ)(2)

<!-- p. 570 -->

570 TRABES ARMADAS

1+---835--_"1

No
N

00~
\~

102 X 102 X 12.7 X 210

Soldadura Viga de piso: W760 x 160.7/1.58 deLcampo

Angulares de conexión diseñados en el ejemplo 8-9

20
Figura Elo-Sd

Se usarán tres sujetadores (Mínimo del AREA para los sujetadores en una
conexión). Prúebese para el atiesador una WT 385 x 73.7
A = 9.39 X 10-3 m2 tI = 17.02 mm
d= 376.6 mm tw = 13.21 mm
rx = 119.95 mm ry = 53.34 mm
L = [1.22\<Y + (1.220/3)2] 1/2= 1.286 m
282 Lfr; = 1286/53.34 = 24.1 >--
{F;
250 ) 1.5
Fa = 0.60(250) - ( 316 (24.1) = 133 MPa
Pa = AFa = 9.39 x 133 = 1249 kN » 579 Correcta

La relación bit del patín es satisfactoria. La relación bit del alma dista bas-
tante del valor permisible de 16t; sin embargo, el AREA lo permite si el área
reducida es adecuada para la carga. En este caso se puede desechar la mayor
parte del alma de la WT y todavía tener suficiente área para soportar la fuer-
za del atiesador.
Paso No lO. Comprobación del soporte lateral.

<!-- p. 571 -->

TEORIA DEL DISEÑO DE LAS TRABES ARMADAS-AASHTO 571

La fuerza lateral/longitud del puente se basa en los requerimientos del
AREA, dados en la sección 1-9.
Viento sobre la trabe: 1.5(0.030 kips/pulg2)(47.88)
(2.134 m peralte) =4.6 kN/m

Viento sobre el tren: 0.300 kips/pie lin (14.59) =4.4 kN /m
Total =9.0 kN/m

Se aplica en cada punto crítico una fuerza concentrada adicional de un cuar-
to de la carga más pesada en los ejes; esto da una fuerza de

110(4.45)(0.25) = 122.4 kN

El AREA permite que esta carga lateral la soporten las vigas de piso (como
en la figura 10-4d). Se puede añadir arbitrariamente un sistema de soporte
transversal en el plano de los patines inferiores. Si se usa un sistema de so-
porte transversal y seis paneles a S = 27.5/6 = 4.58 m, las cargas del panel
son:
Panel extremo: 122.4 + 9(4i58) = 143.01 kN
Paneles interiores: 122.4 + 9.0(4.58) = 163.6 kN

El diseño de los miembros del soporte lateral no se hará en este lugar, ya que
es sencillamente un problema de encontrar la carga axial correspondiente y
seleccionar un miembro a compresión apropiado (probablemente un angu-
lar) para soportar la carga. ///

PROBLEMAS

10-1 Diséñense las cubreplacas para una sección laminada en un claro de 48 pies, que soporta una sola
carga concentrada de 225 kips. Limítese la deflexión a L/360. Considérese cubreplacas tanto de longitud total corno parcial. Supóngase apoyo lateral en los extremos y en la carga concentrada. Usese acero A-36, electrodos E70, las especificaciones del AISC y limítese el peralte a 36 pulg,

Respuesta: Pruébese una W30 x 2\1 y cubreplacas de 1.25 x 24 pulg.

10-2 Diséñense las cubreplacas para una sección laminada en un claro de 15.2 m, que soporta una sola
carga concentrada de 998 kN. Limítese la deflexión a L/360. Considérense cubreplacas tanto de longi-
tud total corno parcial. Supóngase soporte lateral en los extremos y en la carga concentrada. Usese
acero A-36, electrodos E70 (480 MPa) las especificaciones del AISC, limítese el peralte a 900 mm.

Respuesta: Prúebese una W760 x 314, y cubreplacas de 36 x 600 mm.

10-3 ¿Cuál será la capacidad máxima a momento flector de una W36 x 194 con un Cl5 x 40 soldado
al patin superior para formar una trabe armada para la viga carril de una grúa, corno se ve en la figura

<!-- p. 572 -->

572 TRABES ARMADAS

PlO-3? El claro es de 32 pies sin apoyo lateral excepto en los extremos de la trabe. Usense las especifi-
caciones de la AISC, acero A-36, y electrodos E60.

Respuesta: l 492 pies· kips.

10-4 ¿Cuál será la capacidad máxima a momento flector de una W920 x 270.8 con un C380 x 50.45
soldado al patin superior para formar una trabe armada para la viga carril de una grúa, como se ve en
la figura PlO-3? El claro es de 9.75 m, con apoyo lateral solamente en los extremos de la trabe. Usense
las especificaciones de AISCm acero A-36, y electrodos E60 (480 MPa).
Respuesta: l 638 kN . m.

Figura PIO·3

10-5 Diséñese la soldadura entre la canal y la viga para la trabe del problema 10-3.

10-6 Diséñese la soldadura entre la canal y la viga para la trabe del problema 10-4.

Las vigas armadas que aparecen a continuación se han de diseñar en su totalidad, usando la lon-
gitud o longitudes que asigne el instructor. Se puede trabajar en grupos usando una longitud por gru-
po (y otros datos), o cada persona puede tener distintos datos de diseño para la longitud, peralte y car-
ga. Hay que tener cuidado de revisar la siguiente lista de conceptos del diseño: (1) diagramas de cor-
tante v momento; (2) espesor del alma; (3) proporciones de los patines; (4) momentos de inercia yfb;
(5) Fb permisible y la reproporción según se requiera; (6) atiesadores de apoyo; (7) atiesadores inter-
medios; (8) soldadura del patín al alma; (9) soldaduras de los atiesadores al alma; (10) revisión de la
deflexión.
10.7 Diséñese una viga armada soldada, con un claro de pies, que soporte cargas como se mues-
tran en la figura Plo-7. Tómese P = 175 a 250 kips, L = 40 a 60 pies, D = 60 a 96 pulg, según se
asignen. Usese acero A-36, electrodos E70, y las especificaciones del AISC. Supóngase apoyo lateral
en los extremos y en los puntos de carga. (Nota: Si no se asignaran datos específicos, tómese p = 215
kips, L = 54 pies, y D = 80 pulg).

P O.9P
1I---LI3+LI3+LI3----\1 '1
Figura Pl007

10.8 Diséñese una viga armada soldada, con un claro de m. que soporta cargas como se mues-
tran en la figura PIO-7. Tómese P = 780 al 120 kN, L = 12 a 18 m, y D = 1.52 a 2.40 m, según se
asignen. Usese acero A-36, electrodos E70, y las especificaciones del AISC. Supóngase apoyo lateral
en los extremos y en los puntos de carga. (Nota: Si no se asignaran datos específicos, tómese P = 950
kN, L = m, y D = 2.14 m).

<!-- p. 573 -->

TEORIA DEL DISEÑO DE LAS TRABES ARMADAS-AASHTO 573

10-9 Diséñese una viga armada soldada para una trabe carril de grúa, con las condiciones que se
muestran en la figura PIO-9 (las cargs máximas en una trabe). Usese las especificaciones del AISC,
acero A-36, y electrodos E70. Limítese el peralte de la trabe a 84 pulg. Sólo habrá apoyos laterales en
los extremos de la trabe. Usese W/4 = 25 kips, PI2 = 200 kips, L = 80 pies, y S = 15 pies.

W/4 W/4
J;~12
\~ ·1
P/2

Figura P10~9

lO-lO Diséñese una trabe carril armada soldada, con las condiciones que se muestran en la figura PIG-9
(las cargas máximas en una trabe). Usense las especificaciones del AISC, acero A-36, y electrodos E70
(480 MPa). Limítese el peralte de la trabe a 2.15 m. Usese W/4 = 110 kN. PI2 = 950 kN, L = 26.2 m,
y S = 4.6 m.

10-11 Diséñese una trabe armada soldada para un puente de ferrocarril de tablero superior abierto,
con una sola via. Supóngase que cada via contribuye con una carga de 0.25 kips/pie, incluyendo
rieles, durmíentes, etc. Diséñese para las cargas Cooper E-80 o E-IIO, y claros de 40 a 110 pies, según
se asignen. Usese acero A-36, electrodos E70, y las especificaciones del AREA. Limítese el peralte to-
tal de la trabe a L/lO ~ D ~ L/15, pero nunca menor de 4 pies ni mayor de 8 pies. Tómese la sepa-
ración de las trabes como S ~ L/15. Diséñese el soporte contra el desplazamiento lateral y/o los
diafragmas además del alma, patines, atiesadores, y soldaduras. (Nota: Si no se asignaran datos
específicos al problema, usese la carga Cooper E-IIO, L = 90 pies, D = 96 pulg, YS = 6.5 pies).

10-12 Diséñese una trabe armada soldada para un puente de ferrocarril de tablero superior abierto
con una sola vía. Supóngase que la vía contribuye con una carga de 3.65 kN/m, incluyendo rieles,
durmientes, etc. Diséñese para las cargas Cooper E-80 o E-lIO, y claros de 14 a 34 m, según se asig-
nen. Usese los datos del Problema 10-11 para obtener S y el peralte D, pero se limitará D a un valor
entre 1.22 y 2.45 m. Si no se le asignaran datos específicos al problema, se usará la carga Cooper E-80,
L = 23 m, D = 2.3 m, y S = 1.6 m.

<!-- p. 574 -->



<!-- p. 575 -->

APENDICE
SELECCION DE PROGRAMAS DE
COMPUTADORAS

A-l PROGRAMA PARA EL ANALISIS DE UN MARCO

Este programa de computadora analizará cualquier marco plano. El marco puede
ser rígido, articulado, o una combinación. Debe tener un módulo de elasticidad
constantes, E. El programa no tiene en cuenta los asentamientos en los apoyos.
Se pueden considerar dichos asentamientos en los apoyos alimentando manualmente el equivalente en términos de momentos en extremos fijos y de los cortantes resultantes. Se debe consultar el capítulo 2, para la codificación típica de los
varios tipos de problemas que puede analizar este programa.
En general, el usuario debe colocar un nudo donde se desee que haya deflexiones a lo largo del claro de la viga y bajo las cargas concentradas, particularmente si hay más de dos cargas concentradas sobre el miembro. El programa calcula los momentos en extremos fijos para una carga uniforme sobre la viga (con
orientación desde la posición horizontal hasta la posición vertical) Calcula también los momentos en extremos fijos para hasta dos cargas concentradas en el claro. Permite también alimentar los cortantes de las columnas (cargas de fuera del
plano de la columna, como cuando son rígidas en una dirección y simplemente
apoyadas en la otra). Se pueden usar estos valores de-cortante para reducir la carga de la columna debido a reducciones en la carga viva, por medio de valores y
signos apropiados.
Se requieren los pasos siguientes para operar el programa, con terminología
que se ajuste al listado del programa de la computadora.

575

<!-- p. 576 -->

576 SELECCION DE PROGRAMAS DE COMPUTADORAS

\1. Codifíquese la estructura según sea marco rígido, armadura o una combina-
ción. Téngase en cualquier tipo de articulaciones, como en el capítulo 2.
\2. Determínese el NP. El programa de la computadora calcula NPP1 = NP + 1.
\3. Determínese el número de miembros, NM.
\4. Determínese el número de condiciones de carga, NLC.
\5. Determínese el NLC que primero utilice el viento como NLW.
\6. Determínese el NLC que usa D + L, que después se ha de combinar con el
viento (D + L + W). Se le llamará NLC = IDLPL. Cuando aparece este
NLC, las fuerzas D + L del miembro se almacenan en el archivo de disco para
llamarla con cada subsecuente NLC que use viento.
\7. Determínese el NLC que tenga viento en cualesquiera vigas o columnas. Llá-
mesele NLC = IWINBE. Esto será generalmente lo mismo que NLW. Cuan-
do aparezca NLC = IWINBE, se llama el D + L en el disco y se suma a los
valores comunes que deben solamente ser los del viento.
\8. Hállese el NBAND, usando el método cuyo esquema aparece en el texto.
\9. Asegúrese que el ISTIFF tiene dimensión mayor o cuando menos iguales que
el NBAND x NP.

Entrada
\1. Perfórese las tarjetas para las líneas 4, 8 Y10 del listado de la computadora.
\2. Perfórese las tarjetas de datos de los miembros de acuerdo con el FORMAT de
la línea 31. FORMAT(714, 4GlOA, 12)
El formato G permite usar, o bien FlOA o bien xxxE-3 o xxxE-6 para los problemas con SI.
NPE(7) usa el formato 12 y va en la columna 70.
Usese NPE(7) = 1 para todos los miembros sin cargas transversales.
Para cualesquiera miembros con cargas transversales:
NPE(7) = Opara cargas normales de gravedad en las vigas.
NPE(7) = - 1 para cargas de viento sobre las vigas, o para cargas transversa-
les sobre columnas verticales.
Si NPE(7) ~ O, es necesario poner a continuación de la tarjeta de datos del
miembro las tarjetas NLC perforadas según el FORMAT en la línea 51, donde
w = carga uniforme sobre el miembro (kips/pie o kN/m), dirección de la gra-
vedad = (+) PI, P2 = máximo de 2 cargas concentradas sobre el miembro;
se usará ( +) = dirección de la gravedad.
Xl, X2 = distancia horizontal desde el extremo de origen del miembro de PI y
P2, en pies o m
VI, V2 = cortantes en las columnas procedentes de direcciones alternas para
un marco espacial, VI = cortante del lado más cercano; úsese kips o kN y los
mismos signos que en PI, P2
\3. Póngase una tarjeta en blanco al final de los datos de los miembros.
\4. Si hubieran algunas fuerzas concentradas en los nudos (única carga para una
armadura articulada), pásese al DO 991 en la línea 222, la que requiere tarjetas
NNZP en el siguiente orden:

<!-- p. 577 -->

PROGRAMA PARA EL ANALIsrs DE UN MARCO 577

MI = valor NP de la entrada
PR(Ml,L), L = I,NLC Esto alimenta las fuerzas nodales NLC para NP
\= MI Y condiciones NLC usando el formato
SFlO.4. Nótese que esto requiere cuando menos
dos tarjetas para cada NNZP.
\5. Añádase las tarjetas personales de control.
Nótese que se pueden leer (pero no se recomienda hacerlo) momentos nodales en el paso 4 que aparece más arriba. Si se leyera los momentos nodales, habrá
que corregir los momentos en la salida en forma manual para obtener el momento final de diseño como
F final = Fsalida + M¡ectura

prestando cuidadosa atención a los signos. Los signos de la salida se interpretarán usando la figura 2-6. Cuando el programa calcule los momentos de extremos
fijos, la salida queda automáticamente corregida para los MEF, para obtener los
valores de diseño. Las fuerzas en los miembros no tienen que corregirse para ninguna fuerza en los nudos en lecturas que no sean la de los momentos.

Salida
Si las unidades de entrada son como las identificadas aqui, la salida será

x = desplazamientos = pulg, mm, orad
F = fuerzas en los miembros
Miembros de la armadura: kips o kN
Miembros de las vigas: kips o kN para la
fuerza axial
pies . lb o kN . m
para los momentos
Identificación de las variables del programa
ZZZ cualesquiera datos alfanuméricos que no usen más de SO columnas.
Se recomienda usar el propio nombre, número del problema o ambos.
UNITl, UNIT2, UNIT3, UNIT4 identificación de las unidades para problemas
con pie lb seg y SI
UNITl FT oM (se empieza en la columna 1 de la tarjeta)
UNIT4 IN o MM (se empieza en la columna 5)
UNIT2 K-IN o K-MM (se empieza en la columna 11 -unidad usada pa-
ra la matriz P)
UNIT3 K-FT o KN . M (se empieza en la columna 21)
NP número de valores de P codificados = 2 x número de nudos - nú-
mero de reacciones
NM número de miembros (NM = NP para armaduras determinadas)
NLC número de condiciones de carga

<!-- p. 578 -->

578 SELECCION DE PROGRAMAS DE COMPUTADORAS

LISTB I para listar la matriz en banda (parte la matriz ASAT total usada
para encontrar los valores de X)
NLW primera condición de carga con viento
NNZP número de entradas en la matriz P que no son iguales a cero, que se
han de leer separadamente
IMET Opara problemas con pie lb seg = I para problemas con SI
ITRUSS I para todos los miembros de armaduras; = Osi están presentes al-
gunas vigas como miembros
ISTIFF matriz en banda, y sus dimensiones serán cuando menos NP x
NBAND
NBAND ancho de banda usado. ¿Hay alguna diferencia entre el mayor y
menor NP en los extremos de cualquier miembro? El valor puede
ser mayor de lo necesario pero no mayor que NP. Si el valor es sólo
uno o dos números más pequeño, tiene tendencia a dar a veces res-
puestas casi correctas -otras veces da un mensaje de error (por
"overflow")
IDLPL NLC con D + L que se guarda en el archivo de disco para añadirlo
al NLC del viento
IWINBE NLC que usa el D + L del archivo de disco junto con las fuerzas
corrientes
IWRITX I para escribir la matriz X (deflexión)
IWRITX Opara obtener una salida con pocos miembros
I para obtener una salida cuando se usa un gran número de NLC
E módulo de elasticidad, kips/pulg- o MPa
MEMNO número de miembro asignado al elemento durante la codificación
NPE(I) valores NP para el elemento: la armadura los tiene del I hasta el 4:
la viga del I hasta 6
H distancia horizontal hasta el extremo más distante del miembro,
incluyendo el signo, en pies o m
v distancia vertical hasta el extremo más distante del miembro, inclu-
yendo el signo, en pies o m
A área de la sección transversal del miembro, pulg-o m2
XI momento de inercia del miembro, pulg' o nr' (no se necesita en los
miembros de las armaduras)
NPE(7) interruptor de control para miembros con cargas transversales
Opara miembros con cargas transversales
I para miembros sin cargas transversales (véase también las tarjetas
COMMENT en el programa de la computadora)
MI *valor NP de la entrada de la matriz P, donde se halla localizada una
carga concentrada (o momento)
PR(I) valor de la entrada correspondiente de la matriz P. Estas dos tarje-
tas se encuentran en un lazo DO, de manera que se usarán tantos
pares como NNZP.
• Asegúrese de introducir una tarjeta en blanco al final de los datos de los miembros

<!-- p. 579 -->

PROGRAMA PARA EL ANALISlS DE UN MARCO 579

PROGRAM JE81lINPUT.OUTPUT.TAPE1.INPUT.TAPE3.0UTPUT,TAPE51
\~ee •••••••••••••••••••••••••••••••••••••••••••••••••••••••••J E 80WLES STIFFNESS METHOD FOR SOLVING FRANES ANO TRUSSES •••NODEL
e eODE STRueTURE WITH ALL REACTIONS OF lERO DISPLACENENT AS NPPl
C INP + 11. FOR MEM8ERS WTIH MORE THAN 2 eONC. LOADS SU8DIVIDE INTO
C ADDITIONAL MEMBERS WITH NODES AT THE CONC. LOADS. PUT NODES AT POINTS
e eRITICAL DEFLECTION so DEFLECTIONS IXIII'SI ARE D1RECTLY OBTAINED.
e ••••••••••••••••••••••••••••
C IWINRE • COUNTER TO ADO WINO LOAD OF 8EAM TYPE ANALYSIS TO O + L
e IOLPL • COUNTER FOR OEAO + LIVE LOAD NLC
e
e UNITl • K OR KN --- UNIT? • IN-K OR KN-MM --- UNIT3 • FT-K OR KN-M
e UNIT4 • IN OR MM -- ••• NOTE CAREFULLY UNITS OF UNITIII FOR INPUT/OUTPUT
ee
C NP· NO OF NP IN COOING--NM • NO OF NEMBERS IN STRUCTURE--NLC • NO OF LOAD
C CONDITION5--LISTB. 1 TO LIST ~AND "ATRIX IUSUALLY USE Ol----NLW • LOAD CONO
C WHERf WIND STARTS--NNlP • NO Of NON-lERO P-"ATRIX ENTRIES TO READ IREAD ONLY
C CONC LOA051---IMET • 1 FOR NETRIC PR08----ITRUSS • 1 FOR ALL TRUSS NEMBERS
C t5TtH. NO Of STIH ENTRtES INP."BA"DI--NtlAND • 8ANO WIOTH---IOLPL. LOAD
C CONO OF OEAO + LIVE ONLY TO HOLO TO COM8INE WITH WINO----IWINBE • NO Of
C LOAD CONOITION FOR WHICH O + L EFFECTS ARE AOOEO TO OBTAIN OESIGN VALUES
C
C IWRITX • 1 TO WRITE X-NATRIX
C IWRITP • 1 TO WRITE BAR FORCE MATRIX WMEN NLC • 1C • o TO WRITE MAX ANO MIN 8AR FORCES WHEN NLC • LARGE
CITO WRtTE BAR fORCE NATRIX WHEN NLC • LARGE
C
OINENSION NPEI7I,EAI6,3I,llllZOI,E513,3I,ESATI3,6I,EASATI6,6) ,
1 FI3I,FUllOI,FN1199I,FMZ(99),FFUIZ,41
OIMENSION PI115,Z4I,TFII15,Z4I,PRII151,STIFFI1500I,PNAXII151
I.PlHNI1l51
C
DATA FFU/lZ.,1000.,I •• 1000.,I •• 1000000.,IZ.,I.1
ee
C REAO CARO
Z REAOll.lOOOllll,UNIT1,UNIT4,UNITZ,UNIT3
e
1000 FORMATIZOA4,I,AZ.ZX.AZ,4X,4IA4,6XI)
tF I EOF 1111750,3
3 WRITE 13.20001 III
ZOOO FOR"ATI'I',II.1X,ZOA411)
C
C READ CARO
REAOll,lOOIINP,NN,NLC,LISTB,NLW,NNlP,INET,ITRUSS,ISTIFF,MBAMD.
ltDLPL,IwINBE,IWRITX,IWRITP
e
1001 FORNATllbI51
CC •••••• READ NODULUS OF ELASTICITY --KSI OR "PA
REAOll,lOOZIE
C
1002 FORMATIBFlO.41
C
C DEFINE U"IT CONVERSIO" FAeTORS ••••••••••• tuNIT • 1
IFIINET.GT.OIIUNIT • 2
DO 40 1. 1,4
FUIII • FFUIIUNIT.II
40 eONTIMUE
C
"PPl • NP + 1
DO 10Z l. I,ISTIFF
102 STIFflII • O.
DO 103 l. I,NPPl
00 103 J. I,NLC
IFII.EQ.lIPRIJI • 0.0
TFlI,JI • O.

<!-- p. 580 -->

580 SELECCION DE PROGRAMAS DE COMPUTADORAS

103 PCI,JI a O.
WRITEC3~2001IMP.MM.MLC,MLW.MNIP.IMET.ISTIff,~.IWRITX,IWPITP.IOLPL.
lIWIM8E
2001 fORMATC/, 5X,'STIffNESS METHOO Of RIGIO fRAME ANO TRUSS ANALY
lSIS'.II,6X,'NO Of MP a ',I4.5X,'NO Of MEMAERS a ',I4,5X.'MO Of LOA
20 CONOIT a ',14,/, 6X,'NO NLC TO WINO NlC a '.14, 5X,'NO NON-lER
30 P a ',lit, 5X,'METRIC Cl a METRIC) a ',12,/.
It 6X,'NO ISTlff lEROEO a '.I5,4X,'MOO ELASTICITY a ',f8.1,5X.'IWRIT
5X a ',I2,3X,'IWRITP a ',12,/' 10X,
6 'NLC fOR O + L a '.I2,3X,'NLC fOR WINO ON 8EAM a '.12,//)
II a O
E a E+fUC21
C
JJ a 1
C REAO CARO
C REAO NEM8ER DATA AT 1 CARO/MEM8ER ANO fOllOW WITH NLC CAROS Of
C LOAD DATA CSEE A80UT 20 LINES FOLLOWINGI. REAO NPE(7) a 1 FOR ALL TRUSS
e OR OTHER NEN8ERS WITH NO TRANSVERSE lOAO--NPEC71 a O fOR NEM8ERS WITH
C TRAMSVERSE GRAVITY LOAO---NPE(7) a -1 fOR MEM8ERS WITH UNlfORN LOAD
e NORNAL TO NEMBER AXIS.
106 REAOC1.l0071 NENNO,CNPECI),Ia1.6),H,V.A,XI,NPEC71
e
1007 fORNAT C7I","G10.",I2)
C
H a H.fUC11
V a V.FUH)
XL-SORTCH.H+V·VI
IfCNEMMO.GT.OIGO TO 108
xeos-o.o
XSIM-O.O
GO TO 987
108 XCOS-H/XL
XSIM-VIlrL
00 109 I - l,MLe
fNlCII - O.
109 FN2CI) a O.
e
IFCNPE(7).GT.0IGO TO "30
C
IfCJJ.GT.0IWRITEC3,2002)
2002 FORNATC1X, 'NENNO', 4x,'w', 6X,'P1', 7X,'P2',7X,'X1',7X,'X2',
1 7X,'V1',7X, 'V2',/)
JJ - o e
e eONPUTE FEN FOR P-NATRIX FOR ALL LOAD eONOITIONS---NOTE UNIfORN WINO
e wlNO LOAOS eANNOT BE OIRECTLY eON81NEO wlTH UNIFORM GRAVITY 8EAM LOAOS
e OUE TO HORIZ. eOMPONENT--SOLVE SEPARATELY ANO HAVE COMPUTER COMBINE
e RESULTS.
e
Xl - Xl/FUC21
00 98B I - l,NLe
e REAO CARO
READC1,1008)MEMNO,W,P1,P2,X1,X2,V1.V2
e
1008 FORMATCI,,7F10."1
wRITEC3,200,)MEMNO,W,Pl,P2,X1,X2,V1,V2
200' FORNATCI"lF9.3)
U - XUFU(4)
X2 - XUFU!')
IFCABSCXeOS).LE ••000001)GO TO 42
Xl - u/xeas
Xl - U/lleos
e FOR eONeENTRATEO GRAVITY LOAOS ON NEN8ER
42 eONS a 12••FUCIt)
XC - xeos
IFCA8SCXeOS).LT ••00001)Xe - l.
FG1 - C P1.Xl.CXZ-Xl)••2/XZ••2 + P2.X2.CXZ-X2)••2/XZ••2,.Xe
FG2 - CP1.CXZ-Xl).Xl••2/XZ••2 + P2.CXZ-X2).X2••2/XZ•• 2).Xe

<!-- p. 581 -->

PROGRAMA PARA EL ANALISIS DE UN MAReosa1

IFII.GE.NLWIGO TO llZ
C eEAM WITM UNIFORM GRAVITY LOAD
110 ~~W - W.XCOS.XZ•• ZfC~NS
FF"l - BMW + FGl
FE~Z - -BMW - FGZ
GO rn 115
C WINo OP OTHER LOAoS PERPENo. TO BEAM ANofOR + OR - W ON COLU"N--
llZ 8~W - W.XZ•• ZfCONS
FEMl - RMW + FGl
FEMZ - -e~w - FGZ
C
l15 FPl - -IPl.IXZ-Xll + PZ.IXZ-XZI + FElll + fEIlZlfXZ
FRZ - -IPl.Xl + PZ.x? - FE~l - FEllllfXZ
XC - l.
IFII~GE.NLWIXC - vCOS
CON - Z••FUI41
C - -W.XZ.XCfCON + FPl
8 - -W.XZ.XCfCON + FRZ
IFII.LT.NLWIGO TO 118
XS - XSIN
PINPElll,l1 - W.XZ.XSINfCON + PINPEIZI,II - FRl.XS
PINPEI51,II - W.XZ.XSINfCON + PINPEI51,11 - FRZ.XS
118 IFII~FT.EQ.OIGO TO 119
FEMl - FEMl.FUIZI
FEMZ - FEMZ.FUIZI
119 PINPEI31,II - C - VI + PINPEI31,11
PINPElbl,11 - 8 - V2 + PINPElbl,11
44 PINPEIll,II-+FEMl+PINPElll,11
PINPEI41,11-+FEMZ+PINPEI41,11
F~l 1-1 I - FElll
FIlZlI I - FEliZ
988 CONTINUE
430 CONTINUE
C
C
987 WRITEI51IlEIlNO,INPEIII,I-1,6I,H,V;A,XI,XL,XCOS,XSIN,lfll1111,fIlZIII,
1 I-},NLC I
IFIII.LE.O.IGO TO 556
C •••••••••••••••••••••••••••••••••
C RE-ENTER MERE FOR COIlPUTING MEMBER FORCES
C
555 REAoI5IMEIlNO,INPEIII,I-1,61,H,V,A,XI,XL,XCOS,XSIN,lfIl11II,FlltII),1
l-l,NLCI
55b IFIIlEIlNO.GT.oIGO TO lOl
C
C TRANSFEP OF CONTROL oEPENolNG ON ITRUSS ANO IlEIlNO - O
IFIIlEIlNO.EO.O.AND.ITRUSS.GT.O.ANo.II.GT.OIGO TO 188
IFIII.GT.OIGO TO 7Z8
WR ITEI 3, Z0061
ZOOb FOPIlATI//,ZX,'IlEMBER NPl NPZ NP3 NP4 NP5 NPb',6X,'H',7X,'Y',7X,'A'
1,10X,'I', 8X, 'L',bX,'COS', 4X,'SIN',10X,'FElll',6X,'FEIlZ',/1
REWINo 5
00 7Z9 k-}'N"
READI5IMEIlNO,INPEIII,I-1,bl,H,V,A,XI,XL,XCOS,XSIN,FEIl1,FEliZ
WRITEI3,Z0071 MEIlNO,INPEIII,I-l,61,M,V,A,XI,XL,XCOS,XSIN,FE"1,FEIlZ
Z007 FORIlATIlx ,ZI5,514,ZX, ZF9.Z,ZllX,G9.3I,F9.Z,3X,ZFB.5,ZFlO.Z)
729 CONTI NUE
GO TO 728
ZOl IFINPElbl.GT.OIGO TO 185
IFIII.GT.O.AND.NPElbl.EO.OIGO TO lB8
EASATIl,ll - E.A.XCOS.XCOS/xL
EASATIl,ZI - E.A.XCOS.XSINfXL
EASATIl,31 - -EASATIl,ll
EASATIl,41 - -EASATIl,21
EASATIZ,ll - EASATIl,ZI
EASATIZ,ZI - E.A.XSIN.XSINfXL

<!-- p. 582 -->

582 SELECCION DE PROGRAMAS DE COMPUTADORAS

fASATlZ.31 • -EASATlt.21
EASATlZ.41 • -EASATI2.21
EASATI3.11 • -EASATl1.11
EASATI3.21 • -EASATl1.21
EASATI3.~I • EASATl1.11
EASATI3.41 • EASATl1.Z1
EASATI4.11 • -EASATlt.21
fASATI4.21 • -EASATlZ.21
EASATI4.31 • EASATl1.Z1
fASATI4.41 • EASATlZ.21
DO 17Q l' 1.4
IFlNPElII.GE.NPP11GO TO 17Q
N~l • lNPEllI-11.NRANO
DO 17R J. 1.4
IFlNPElJI.GE.NPP11GO T~ 17~
TFlNPElJI.LT.NPElIIIGO T~ 178
NS2 • NPElJI - NPElII + 1
STIFFlNS1 + NS21 • STIFFlNSt+NS21 + EASATlI.JI
17R CONTI NUF
17Q CONTINUF
GO TO 5500
1~5 EAOL • E.A/XL
EIOL • lE.XI/XLI.FUl'I
SINOL • XSIN/XL
COSOL • XCOS/Xl
EAl1.1I • O.
EAl1.21 • 1.
EAll.31 • O.
012.11 • -XCOS
EAlZ.21 • SINOL
EA12.31 • SINOL
EA13.1I • -xSIN
EA13.21 • -COSOL
EA13.31 • -COSOL
EA14.1 I • O.
EAI4.Z1 • O.
EA14.31 • 1.
EA15.1I • XCOS
FAl5.21 • -SINOL
EA15.31 • -SINOL
EA16.11 • XSIN
016.2 I • COSOL
EA16.31 • COSOL
Bll.1I • EAOL
ESll.21 • O.
ESll.31 • O.
ESlZtll • O.
ESI2.Z1 • 4•• EIOL
ESlZ.31 • Z•• EIOL
ES13.11 • O.
ES13.21 • FS12.31
ES13.31 • ES12.21
DO 202 l' 1.3
DO 202 J. 1.6
ESATlI.JI • O.
DO 186 K' 1.3
ESATlI.JI • ESATlI.JI + ESlI.KI.EAlJ.KI
186 CONTI NUF
202 CONTI NUE
C
IFlII.GT.OIGO TO 605
203 DO 204 l' 1.6
DO 204 J. 1.6
EASATlI.JI • O.
00 187 K' 1.3
fASATlI.JI • EASATlI,JI + EAII,KI.ESATIK,JI
187 CONTINUf

<!-- p. 583 -->

PROGRAMA PARA EL ANALISIS DE UN MARCO S83

l04 CONtINUE
DO l06 1 - lt6
IFlNPElII.GE.NPPIIGO TO 206
NSl - lNPElll-ll.NAANO
DO l05 J - 1,6
IFlNPElJI.GE.NPPIIGO TO l05
IFlNPEIJI.lT.NPEIIIIGO TO l05
NSl - NPEIJI - NPElII + 1
STIFFINSl + NSlI - STIFFINSl+NSll + EASATlI,JI
205 CONTINUE
l06 CONTINUE
5500 GO TO 106
C
C THE BANO MATRIX IS NOW FORMEO FOR RFOUCTION IN ISTIFF IN CORE
C WRITE BANO MATRIX IF lISTR • O
C
7lft IFlII.GT.OIGO TO 601
C
C
IFIlISTB.lE.OIGO TO RARCl
WRlTEl3,10091
l009 FOR"ATl TI0, 'THE RANO "ATRIX WITH 1000 FACTOREO',/I
MI - 1
Ml - N8ANO
NCOU - NP.NBANO
DO 305 1 - 1.NP
WRITEl3,1010II.lSTIFFlI1I.Il-Ml,Mll
l010 FORMATIIx.I4.1x,-3Pl9Fll.ll.I. 5X.-3Pl9Fll.ll.l. 5X.-3PI9Fll.ll)
IFlMl.GE.NCOUIGO TO 8889
MI - "'l + 1
Ml - "'l + N8ANO
305 CONTINUE
88A9 WRJTEl3.20111"'l,N8ANO
aoi i FORMATlII.T5,'NO STIFFlII ENTRIES.- '.Ib.l0X.'8ANO wIOTH -',J4,111
C
C
C •••• NOTE--OO NOT RFAO P-MATRIX FNTRJES FOR UNFOR" lOAOS ON 8EA"'S
C DO NOT REAO P-"'ATRJX ENTRJES FOR FEM--INPUT SO CO"PUTER
C CO"'PUTES FEM SO FINAL MO"ENTS ARE CORRECTEO FOR FE" ••••••••
C
IFINNlP.EQ.OIGO TO 4lb
DO 991 NN - l,NN1P
C REAO CARO•••••••••
REAOCl.I0I0 1MI
C
1010 FOR"ATl16151
C REAO CARO•••••••••
REAOll.10llllPRlll.l-1.NlCI
C
1011 FORMATl8FlO.41
00 990 l - ltNlC
PIMl.l1 - PI"1.l1 + PRIlI
990 CONTINUE
991 CONTINUE
416 CONTINUE
DO 99l NSl - 1.NP
DO 99l NSl - l,NlC
99l TFINSltNSlI - O.
C •••••••••••••••••••••••••••••••••••••••••••••
C
406 WRJTEI3,lOlllUNITl,UNITl
lO 12 FORMATI/,lX,'THE P-MATRJX. ',Al,' ANO ',A4,/I
NSl - 1
NSl • 10
427 JFINSl.GT.NlCINSl - NlC
DO 408 J. ltNP
408 WRITEI3.l014II.IPIJ,JI.J-NSl.NSll

<!-- p. 584 -->

584 SELECCION DE PROGRAMAS DE COMPUTADORAS

Z014 FOR"ATIT5, 'NP • ',I3,lX,10Fll.21
IFINS2.EO.NLCIGO TO 4ze
NSl • NSZ + 1
NS2 • NS2 + 10
IIR ITE(3,20161 NSl
Z016 FOR"ATIII,5X,~THE P-NATRIX CONTINUEO BEGINNING IIITH NLC • ',13,/)
GO TO 427
4Z8 CONTINUE
CC SUBROUTINE TO REDUCE THE ~ANO "ATRIX
60 Nl • 1
00 80 N. l,NP
1 • N
00 70 L. 2,NBANO
NL • IN-l).NBANO + L
1 • 1+1
IFISTIFFINL).EO.O.IGO TO 70
B • STIFFINl)/STIFFIN1)
J • O
00 6B K. L.N8ANO
J • J + 1
IJ • II-l).N8ANO + J
NK • IN-l).NBANO + K
68 IFISTIFFINKI.NE.O.ISTIFFIIJI • STIFFIIJ) - 8.STIFFINK)
STIFFINll • 8
C INCLUOE LOAD "ATRIX IN REOUCTION
DO 67 ". I,NLC
67 PII,"I • PI l.") - B.PIN,"I
70 CONTINUE
DO 66 N. 1.NLC
PIN."I • PIN.M)/STIFFIN11
66 CONTINUE
80 NI • Nl + N8ANO
C CO"PLETE SOLUTION BY BACK SUBSTITUTION
N • NP
85 N • N - 1
IFIN.LE.OIGO TO 90
L • N - 1
DO 86 K. Z,NBANO
N~ • IN-ll.NBANO + K
00 B6 ". 1.NLC
IFISTIFFINK).NE.O.)PIN."I • PIN,"I - STIFFINK).PIL+K,")
86 CONTINUE
GO TO 85
90 CONTINUE
CCENO OF "ATRIX REOUCTIDN -- SOLUTION IS IN PII,JI
C
IFIIIIRITX.LE.OIGO TO 4'1
IIRITEI3,Z0171UNIT4
Z017 FORMATIII,5X,'THE X-"ATRIX. ',A2. ' OR RAorANS',')
NSl • 1
NS2 • 10
4Z9 IFINS2.GT.NLC)NSZ • NLC
00 503 1. l,NP
503 IIRITEI3,Z018)I,IPII,J),J.~Sl,NSZI
ZOle FORMATI6X,'NX • ',I3,lX,lOFll.51
IFINSZ.EO.NLCIGO TO 431
NSl • NSZ + 1
NS2 • NSZ + 10
IIR ITE13oZ019 )NS1
2019 FOR"ATI",5X,'THE X-"ATRIX CONT O BEGINNING IIITH NLC • ',13,/)
GO TO 429
431 CONTINUE
C INCRENENT COUNTERS 11 ANO JJ--JJ COUNTS NLC
IIR ITEI 3, 3003)
3003 FOR"ATI/")

<!-- p. 585 -->

PROGRAMA PARA EL ANALISIS DE UN MARCO 585

JJ - o
II - 1
C
601 JJ - JJ + 1
l37 IFIJJ.lE.NlCIGO TO 60l
l38 IlEWINO 5
GO TO 19l
C
60l IFIITRUSS.EO.0.OR.IWIlITP.EO.IIWIlITEI3,lO?0IJJ,UNITI,UNIT3
zoao FOIl"ATII, 4X, 'lOAOING CONl)ITION NO - ',13,1,
1 37X. 'OESIGN END MOMENTS CnRIlECTEO',I. 5X. '"EM8EIl'. 4X,'AXIAl
?F.OIlCF. '. Al, 8X,'FOIl FEM ANI) WINO INEAR ENO FIIlSTl, ',AI"II
RFWIND 5'
ton TO 555
605 PINPP1.JJI-0.
FE"1 - F"lIJJI
FE"l - FMlIJJI
C NOTE IF YOU IlEAD P-MATIlIX ENTRIES FOR FE" THEN OUTPUT MUST BE
C AOJUSTEO BY HANO TO ACCOUNT FOil FIXEO END MOMENTS ON BEAM ENDS
C
00 607 - 1.3
FUI - O.
00 607 K - 1.6
NS3 - NPEIKI
FIII-FIII+ESATII,KI.PIN~3,JJI
607 CONTINUF
FIlI-IFIlI-FEM11/FUI11
FI31-IFI31-FEMlI/FUI11
C
C IlEDUCE MOMENTS FOil WINO
C Al~O NECESSARY TO REDUCE O + l "OMENTS BY 0.75 IF AODEO TO WINO
IFIJJ.EO.IOlPlIGO TO 97l
C
IFIJJ.lT.NlW.OR.NlW.EO.OIGO TO 971,
97l FI11-Fl11.3.1I,.
FIZI-FIll·3.1 ...
FI31-FI3I.3.1I,.
IFIJJ.NE.IOlPlIGO TO 973
C PUT o + l IN TF-MATRIX TO lA TER AOO TO WINO lOAD CONOIT.
00 970 1 - 1.3
970 TFIMEMNO.II - FIII
973 IFIJJ.lT.IWINBE.OR.IWINRE.EO.O.OR.IOlPl.EO.OIGO TO 971,
00 971 1 - 1,3
971 FIII - FIII + TFIME"NO,II
971, WRITEI3,lOlll MEMNO.IFIII,I-l.31
lOZl FORMATIT5.15.F15.l.5X.ZFI5.Z1
GO TO 191
188 CONTINUE
IFIITRUSS.EO.OIGO TO 189
IFIMEMNO.EO.OIGO TO 19Z
P"AXI"EMNOI • O.
P"INIMEMNOI • 1000000.
189 Fl11 • E.A/Xl.IxeOS.IPINPEI31,JJI - PINPEI11,JJII + XSIN.IPINPEII,
11.JJI - PINPEIZI,JJIII
IFIITIlUSS.lE.OIGO TO 190
IFINlC.EO.1IGO TO 195
IFIFI11.GT.P"AXI"E"NOIIPMAXIMF"NOI - Fl11
IFIFIII.lT.PMINIMEMNOIIP"INIME"NOI • Fl11
TFI"EMNO.JJI • Fl11
IFIIWRITP.lE.OIGO TO 1,1,1
e WRITE BAR FOIlCE~ FOR Nle • 1 ANO IWRITP • 1
IFI"EMNO.EO.1IWRITEI3,lOZ5IJJ
ZOl5 FORMATI5X,'BAR FORCES IKIPS OR KNI FOR Nle - ',13,/1
e
190 WRITEI3,ZOl6IME"No,Flll
ZOl6 FORMATIT5,15,F15.2. 10x,'----., lIX,.----.1
1,41 IFIITRUSS.lE.OIGO TO 191
IFIJJ.EO.NlCIGO TO 195

<!-- p. 586 -->

586 SELECCION DE PROGRAMAS DE COMPUTADORAS

JJ - JJ +
GO TO 189
195 JJ - 1
C
191 GO TO 555
192 IFIITRUSS.EQ.OIGO TO 193
IFINLC.EQ.IIGO TO 193
REWINO 5
C WHEN ITRUSS - 1 ANO NLC IS LARGE USE IWRITP - O FOR MAX ANO MIN
C 8AR FORCES ONLY---U~E IWRITP - -1 FOR COMPLETE LISTING OF
C 8ARFORCE5 WHEN NLC IS LARGER THAN 1
C
C
C
WR IH I 3,20331
2033 FORMATIII,8X,'THE MAXIMUM LIVE LOAD BAR FORCES ANO OEAO lOAD VALUE
1~',1,5x,'MEM NO',5X,'MAX LL',9X,'MIN LL',8X,'OEAO LOAD OR LAST NLC
2',11
DO 442 I - 1,NM
WRITEl3,203511,PMAXlII,PMINlII,TFII,NLCI
2035 FORMATlbX,15,4X,F10.2,5X,F10.2,bX,F10.21
442 CONTINUE
C WRITE BAR FORCE MATRIX IF IWRITP - -1
IFllwRITP.NE.-1IGO TO 193
NS1 - 1
N52-10
IFlNS2.GT.NLCINS2-NLC
WR!TE 13,20321 NS1
2032 FORMATIII,5X,'THE BAR fORCE MATRIX STARTING WITH NLC - ',13,1/1
443 DO 444 1-1,N"
444 WRITEl3,202811,lTFII,JI,J-NS1,N521
2028 FOR"ATl2X,13,2X,10Fl1.31
IFINS2.EQ.NLCI GO TO 193
NS1-N52+1
NS2-N52+10
IFlNS2.GT.NLCINS2-NLC
WRnE13,20321NSl
GO TO 443
193 GO TO 2
C
750 STOP
ENO

<!-- p. 587 -->

PROGRAMA PARA EL ANALISIS DE UN MARCO 587

A-2 GENERADOR DE LA MATRIZ DE CARGAS PARA EL CASO
DE CAMIONES, SEGUN LA AASHTO, EN UN PUENTE DE
ARMADURA

Este programa hace avanzar por pasos una carga móvil que consiste en dos o tres
cargas concentradas a lo largo de una armadura. En cada paso, se calculan las
cargas de panel como vigas simples con cargas concentradas. Estas cargas de panel constituyen las entradas de la matriz P para una armadura carente de peso que
se usará en el programa de análisis del marco.
Las cargas -se mueven de izquierda a derecha. Si se usan primero las cargas
mayores de las ruedas, el camión se hace "retroceder" a través de la armadura.
Las limitaciones son:

\1. El usuario debe utilizar cuando menos dos y no más de tres cargas.
\2. El "paso" debe ser un múltiplo entero de la longitud del panel. Como este va-
lor entero se calcula, el paso se debe alimentar con la suficiente exactitud y ser
ligeramente menores, de manera que se obtenga el valor entero en el corte de la
computadora.
\3. Todos los paneles deben tener la misma longitud.

Se calcula automáticamente un factor de impacto y las cargas de panel incluyen el factor de impacto en la salida. Se usa el MET para calcular el factor de impacto ya sea en unidades pie lb seg, o en unidades SI.
El resultado de salida se perfora automáticamente en las tarjetas con el formato correcto para el input directo como matriz P en el programa de análisis del
marco. El usuario podría querer insertar un control opcional de perforación para
inspeccionar la salida antes de que le perfore.

Identificación de variables

Se presenta una lista de un juego de muestra de tarjetas de datos, junto con este
programa, para una armadura de puente que usa unidades pie lib seg o SI; la armadura usa tres cargas de ruedas, siete paneles de armadura (25 pies o 715 m), y
hace avanzar las ruedas 5 pies o 1.5 m. La codificación es tal que los NP del panel
para MI(I) son 26, 2, 6, ... y NPPI = 26 en este caso y no se perfora como salida.
NP número de cargas de ruedas
NS número de paneles de armadura
SL longitud del paso, pies o m
STEP incremento del movimiento de las ruedas, pies o m
MET Opara el puente con pie lb seg; = 1 para los puentes con SI. Este se usa
para calcular en forma apropiada el factor de impacto
P(I) cargas de las ruedas. Nótese el orden en que se usan las ruedas en las
tarjetas de muestra. Usando 8.32.32. hace correr hacia adelante el ca-
mión en el puente.

<!-- p. 588 -->

588 SELECCION DE PROGRAMAS DE COMPUTADORAS
x ( I ) espaciamiento cumulativo de las ruedas, como 14.28, para usar 14pies
entre cada juego de ruedas. Este espaciamiento o el equivalente en uni-
dades SI, será generalmente el espaciamiento más crítico.
Ml(l) Los números NP en orden de izquierda a derecha, en los lugares donde
se sitúan las cargas de panel. MI tiene aquí el mismo significado que en
el programa de análisis .del marco. Nótese que no se usa NPPl. Para
una armadura de tablero inferior, esta sección del programa requiere
una ligera modificación para poner cargas en los lugares de la armadu-
ra donde se pueda encontrar el NPP1, ya que el método corriente que
se usa omite el primero y el último valor de Ml(l) (para la identifica-
ción se clasifican como entradas).

<!-- p. 589 -->

GENERADOR DE LA MATRIZ DE CARGAS PARA EL CASO DE CAMIONES, 589

C NP IS T~E NUM8ER OF LOAOS THAT ARE WANTED ON THE TRUSS SL IS THE
e LENGTH OF EACH PANEL IN THE TRUSS NS IS THE NUM8ER OF PANELS IN THE TRUSS
e STEP IS THE MOVEMENT THAT IS WANTEO FOR THE LOADS 8ETWEEN EACH LOAD
e CONOITION PIII IS THE WEIGHT OF EACH LOAD IN THE SERIES
e XIIIIS THE OISTANCE THE LOAD IS 8EHINO THE FIRST LOAD
e MET=O.O F8S 21.0 METRIC
OIMENSION TEMPIZO,701,REACTIZO,701,PC5I,XC51 ,M1CZO)
5000 REAOC1,l,ENO=~000INP,NS,SL,STEP,MET
1 FORMATCZI5,ZF10.~,151
WRITEI3,5INP,SL,NS,STEP
5 FORMATC'lNUM8ER OF LOAOS ON TRUSS',ZX,I3,II,' SPAN LENGTH OF EACH
1PANEL',F8.Z .rr,» NUM8ER OF PANELS IN TRUSS',ZX,I3'/I,' LENGTH OF
ZMOVEMENTOF THE LOAOS',F8.Z ,1/1
00 ZO 121,ZO
DO ZO J=l,70
TEMPCI,JI=O.O
ZO REACTII,JI=O.O
DO 100 1=1,5
XClI=O.O
100 PIII=O.O
NLS=SL/STEP
NX=NP-1
NSPl=NS+1
NSMl=NS-l
REAOC1,ZICPIII,l sl,NPI,IXCJI,J=I,NXI
Z FORMATC10F8.Z1
WRITEC3,611I,PIII,I=I,NPI
6 FORMATIIII,' P',ll,' =',F8.3)
WRITEI3,7ICJ,XIJI,J=l,NXI
7 FORMATCIII,' X',11,' s',F8.31
5K=0.0
SKZ=O.O
DO 110 Ms1,NP
DO 109 1-1,NS
IP1=I+l
DO 108 J-1,NLS
RR=PCMI*CJ*STEP-SK-SKZ)/SL
ALR=PCMI-RR
IF IJ*STEP+STEP .GT. SLI SK-SL-J*STEP
JZ= ISL/STEPI*II-11
J3=J+JZ
e TEMPERARY STORAGE OF REACTION VALUES
TEMPII,J31=ALR
TEMPClP1,J31 sRR
108 CONTINUE
109 CONTlNUE
C PLACE CONSECUTIVE LOAOS IN THEIR PROPER POSITION
IX=XCMIISTEP
IST=lX*STEP
SKZ-XCM)-IST
INT=O
IF CM.EO.l1 GOTO 105
DO 107 1-1,NSP1
DO 107 J-l,J3
MM1= M-1
INT=XIMM1I1STEP
MZ=J+INT
C AOO TEMPERARY STORAGE TO PERMANENT STORAGE
107 REACTII,MZ)-REACTCI,M21-TEMPCI,J)
GOTO 110
105 DO 104 1-1,NSP1
DO 10~ J-1,J3
104 REACTCI,JI=-TEMPII,JI
110 CONTlNUE
IFCMET.EO.1)GOTO 200
XIMPAT=50./CNS*SL+125.1
GOTO 201
ZOO XIMPAT=15.2~/CNS*SL+38.10)

<!-- p. 590 -->

590 SELECCION DE PROGRAMAS DE COMPUTADORAS

201 CONTlNUE
IF IXIMPAT.GT.0.30t XIMPAT-0.30
00 103 I-1.M2
00 103 J-1.NSP1
103 REACTIJ.It-REACTIJ.I'.I1+XIMPATt
lIRITEI3.4t
4 FORMATI""'.' LOAO'." CONOITION'.T20.' THE REACTIONS"
00 106 J-1.M2
106 lIRITEI3.3t J. eREACTel,J'.I-1.NSP1'
3 FORMATeT5.13.10e5X.F6.1t,
C PUNCH M1 FROM LEFT TO RIGHT ACROSS THE TRUSS
C PUNCH FORMAT IS COMPATI8LE lIITH ANALYSIS PROGRAM FOR OIRECT INPUT
REAOl1.8teM11It.I-1.NSP1 t
8 FORMAre 2014 ,
00 112 I-2.NS
WRITEU.9'MlI U
9 FORMATII5t
112 lIRITEe2.10tlREACTII,J),J-1,M2t
10 FORMAre 8F10.4'
GOTO 5000
4000 STOP
ENO

C FOLLOllING 3 CAROS ARE SET FOR FPS OUTPUT 3 7 ••••25. 5. O
\8. 32. 32. 14. 28.
26 2 6 10 14 18 22 26
C •••• FOLLOlIING 3 CAROS ARE SEr FOR SI OUTPUT
3 7 7.5 1.5 1
36.0 142.0 142.0 4.25 8.5
26 2 6 10 14 18 22 26 ,.

<!-- p. 591 -->

GENERADOR DE LA MATRIZ DE CARGAS PARA EL CASO DE CAMIONE~, 591

A-3 GENERADOR DE LA MATRIZ DE CARGA, SEGUN EL
AREA, PARA LA CARGA COOPER E-SO, EN UN PUENTE DE
ARMADURA

Este programa hace avanzar por pasos un tren con una carga Cooper E-80 a lo
largo de un puente de armaduras. En cada paso (DX) se calculan las cargas de panel como una serie de vigas simples. Estas cargas de panel constituyen las entradas de la matriz P para una armadura carente de peso que se usa en el programa
de análisis de los marcos. Nótese que el programa no se detiene hasta que todas
las ruedas no estén fuera del puente y solamente queda la carga uniforme.
La única limitación de este programa es que las longitudes de los paneles deben ser iguales.
Las cargas Cooper E-80 y el espaciamiento de las ruedas se han incorporado
permanentemente en el programa como DATA FFP/ y DATA FFX/.

Identificación de variables

(véaselas tarjetas de muestra de datos que aparecen al final de la lista del programa)
TITLE hasta 80 columnas de datos alfanuméricos para la identificación
del problema
NOSPAN número de paneles
ISWIT Opara el pie lb seg; 1 para los problemas con SI; se usa para
convertir las cargas de las ruedas y el espaciamiento a unidades SI
y usar la forma correcta del factor de impacto
IPUNCH Opara no perforar la salida en la inspección inicial de la correc-
ción del proceso; = 1 para perforar la salida en el formato para la
entrada directa de la matriz P en el programa de análisis del mar-
co
IMP Ocuando no hay factor de impacto; = 1 para incluir el factor de
impacto
IWRIT 1 para escribir la selección de los cálculos intermedios para elimi-
nar las fallas del programa; = Ocuando el programa trabaja en
forma apropiada
DX incremento del movimiento de las ruedas, de izquierda a derecha,
en pies o m
SPAN longitud del panel, en pies o m
WIDH distancia entre las dos armaduras que forman el puente, y que se
necesitan para calcular el factor de impacto, en pies o n
FAC factor para convertir E-80 a E-llO, E-60, etc.; se usará FAC =
1.0 para la carga E-80
NPS(J) Números NP (iguales a MI) donde se han de establecer los valores
de la matriz P (nótese que estas entradas no incluyen valores de
NPPl -puede que se necesite hacer una modificación para la ar-
madura de un puente de tablero inferior).

<!-- p. 592 -->

592 SELECCION DE PROGRAMAS DE COMPUTADORAS

C J E 80WLES PROGRAM TO FINO TRUSS NODE FORCES FDR AREA 8RIDGES
C
C NOSPAN = NO OF SPANS OR GIRDER SEGMENTS; ISWIT z 1 FDR METRIC
C o FOR FPS; OX = INCR. OF LOAD MOVEMENT, FT OR M; SPAN = LENGTH OF C TRUSS SPAN OR GlROER SEGMENT; FAC = LOAD RATIO IFFP = E80 LOAOINGI USE
C FAC = 0.15 FOR E6G--0.9 FOR E1Z--1.00 FOR E8G--L.315 FOR EllO.
C
C WIOH = CENTER TO CENTER SPACING OF TRUSSES C lWRIT = 1 TO WRITE SELECTEO COMPUTATIONS FOR OE8UGGING
C
C IMP = 1 TO COMPUTE IMPACT TO APPLY TO GIVEN E-LOAOINGANO/OR FOR
C PUNCHED OUTPUT--PRINTEO OUTPUT IS FOR CHECKING ANO FOR USE IN
Ce IPUNCHOESIGNlNG= 1 TOFLOORPUNCHBEAMSCUTPUTWITHINUSEFORMATOF SEPARATEFOR ANALYSISIMPACTPROGRAMFACTOR TO
C OEVELOP 8AR FORCES AS EQUIVALENT INFLUENCE LINE FOR OESIGN
C
OIMENSION TITLEIZOI,PCZOOI,XCZOO"FFXI18"FFPI19', PRIZO,2101
1, PTl50' ,NPSC 40'
C
DATA FFX/B.,5.,5 •• 5 •• 9.,5 ••6.,s.,a ••8.,5.,5.,5.,9.,5.,6.,5. , 5. 1
DATA FFP/40•• 80.,80 •• 80•• 80.,52•• 5Z•• 52 •• 5Z ••40•• 80 ••80.,80 •• 80.,
15Z.,52•• 52 •• 52.,8.1
C
5000 REAOll.1000,ENO=150ITlTLE,NOSPAN,ISWIT.IPUNCH.IMP,IWRIT
C
1000 FORMATI20A4.1,16151
C
REAOl1.100Z'OX,SPAN,WlOH,FAC
1002 FORMATC8FI0.41
C NPSIJI = NP NUM8ERS FOR NON-lERO P-MATRIX ENTRIES
NSPN = NOSPAN - 1
REAOll.1006'CNPSIJI.J zl,NSPNI
1006 FORMATC1615'
NP = 18 OIS = 80. lFllSWIT.GT.OIOIS = 25. 8 = NOSPAN
TOTSPN z 8*SPAN
C SET WHEEL LOAOS ANO WHEEL SPACING
SUMXL = O.
DO 5 I = 1,18
XIlI = FFXMI
IFIISWIT.GT.O'XCII XII'*0.304B
PIll = FFPCI'*FAC
lFIISWIT.GT.OIPCII = PIll*4.4482Z SUMXL = SUMXL ~ XCI'
5 CONTlNUE
WLOAO = FFPI191*FAC IFIISWIT.GT.OIWLOAO = WLOAO*14.59312
PAC = l.
C COMPUTE IMPACT FACTOR FOR AREA 1916 IPAC'
IFIIMP.LE.OIGO TO 1
IFCTOTSPN.GT.OIS'GO TO 6
\~ 40. - 3.*TOTSPN**2/1600.1/100. IFIISWIT.LE.O'PAC = C100./WlOH
\~ 40. - 3.*TOTSPN**2/150.1/100. IFIISWIT.GT.O'PAC = 130.5/WIOH
GO TO 1
\~ 16. - 600./ITOTSPN-30.1)/100. 6 IFCISWIT.LE.OIPAC = C100./WIOH lFClSWIT.GT.O)PAC = C30.5/WIOH ~ 16. - 185./CTOTSPN-9.))/100.
C NOW WRITE DATA FOR CHECKING
1 PAC = l. ~ PAC
WRITEC3.Z000)TITLE.NP,NOSPAN.Dx.SPAN.WLOAO.SUMXL.PAC.FAC.wIDH
ZOOO FORMATCIII,5x.20A4.1.5X.'NP • '.15.3x.'NOSPAN = ·.15,3X. 1ZX.'OX = ',Fl.2.1.5x.'SPAN LENGTH - ',F8.3.3X.'UNIF LOAO/LENGTH = Z'.F6.1. l. 5X.'SUM OF XCL) DF CONC. LOAOS = " Fl.2.3X.'IMPACT F
3ACTOR • ·.F6.3,1.5X, 'FACTOR FOR E-LOADS--l.0 FOR E-80 - ,
4F5.3. 3X.'OIST C-TO-C OF TRUSSES = '.Fl.3.11)
WRITEC3.2004)CXCII,I-1.NPI
Z004 FORMATC5X,'XCI) = ',12F9.1.1.12X. 6F9.1,11)

<!-- p. 593 -->

GENERADOR DE LA MATRIZ DE CARGA SEGUN EL AREA 593

WRITE(3.20051(PIII,I=I,NPI
Z005 FORMAT(5X,'P(11 = ',12F9.1,I,lZX, 6F9.1.111
WRITE13.2006l
2006 FOP"AT(10X.·••• lOAOS W/O IMPACT--USE FOP FlOOR BEAM OESIGN ANO CH
1ECI(ING •••• ,11
C
C
9 lSTOP = TOTSPN + SU~Xl + OX
00 B3 1( = 1.20
00 73 l = 1,210
13 PR(I(,ll = O.
83 CONTINUE
NY = 2.INOSPAN+11
Ce •••••• MAIN 00 lOOP FOR INCREMENTING lOADS
00 1~0 I = 1,210
A = I
DIFF ;. O.
ADX = A.DX
AOXH = AOX
C TO STOP COMPUTATIONS WHEN ONlY UNIFORM lOAO ON 8RIDGE
IFIADX.GT.lSTOPIGO TO 1~1
IFIADX.GE.TOTSPNIAOX = TOTSPN
SUM = O.
MM o
NI = 1
C
C
C FINO NO Of SPANS TO USE
R5 SPUSO = AOX/SPAN
C
C lEPO MATRICES AR81TRARY AMOUNTS
00 86 1( = 19,200
)( (1( I = O.
86 CONTINUE
C
00 88 1( 1,50
PTII(I = O.
88 CONTINUE
1M = SPUSO
RM = 1M
IFI8M.lT.SPUSOIIM = 1M +
8" = II'!
IFIAOXH.GT.TOTSPNIOIFf AOXH - TOTSPN
SUM2 = O.
IFIA8SI0IFFI.lE.0.005IGO TO 15
C
00 12 MM = l,NP
SUMZ = SUMZ + X(MMI
IF(SUM2.GE.OlffIGO TO 15
1Z CONTINUE
15 HC MM + 1
AH = II'!
Ol = BM.SPAN - AOXH + SUM2
NN = He
SUMl = O.
SUH3 = O.
SUMP = O.
SUMPT = O.
IFIMM.EQ.NP.ANO.Ol.lE.O.IOl = O.
C
C lOOP fOR NUM8EP Of SPANS USEO FOR CURRENT lOAD POSITIONS
21 DO 102 JJ = 1,11'1
llX = O. DI = SPAN - Dl
I(C = 2.(IH-JJI + 4
l = JJ

<!-- p. 594 -->

594 SELECCION DE PROGRAMAS DE COMPUTADORAS

C FINO NO OF LOAOS IN CURRENT SPAN
00 95 L. Ne,200
IFIL.EO.NP+l.ANO.AOXH.LE.TOTSPNIXILI '" Z.SPAN - SUMXL
IFIL.EO.NP+l.ANO.AOXH.GT.TOTSPNIXILI - OIFF + Z.SPAN - SUMXL
IFIL.GT.NP+l.OR.XILI.GT.SPANIXILI '" SPAN
IFIXCLI.LT.O.IGO TO 1~8
IFIXILI.NE.SPANIGO TO 22
01 '" SPAN
DZ ,. O.
Z2 SUMl ,. SUMl + XILI
IFISUM1.GE.Ol-0.0001IGO TO 96
IFIL.EO.NP+1IZZX • SPAN - 10Z + 0.0051
IFIL.EO.NP+l.ANO.SUMl.GE.lZXIGO TO 96
95 CONTlNUE
96 CONTtNUE
SUM3 = SUM3 + SUMl
TOTSUM ,. SUM3 + SUMZ
NC L + 1
DZ ,. 01
RR ,. O.
I\L ,. O.
IFIIWRIT.LE.OIGO TO 550
WRITEI3,3005ITOTSPN,NC,AOXH, 1M, OZ, DI, SUM1, Ol, NN, L,SPAN,SUM3
1, SUMZ, OIFF, TOTSUM,JJ,XI191,XI20l,XIZ1I,XILI
3005 FORMATI3X,'TOTSPN - ',F8.1,3X,'Ne=',I5,3X,'AOXXH - ',F7.3,
Z 3X,'IM" ',15, 5X,'OZ - ',F7.3,ZX,'Ol - ',F7.3,' SUMl -',F7.3,
3/,5X, 'OZ - ',F7.3,3X,'NN-',15.ZX,'L-',15,ZX,'SPAN"",F7.3,
\~3X, 'SUM3 - ',F7.3.3X,'SUMZ • ',F7.3,3X,'OIFF-',F7.3,3X, 'TOTSUM ,.
5',F6.l,ZX,'JJ='.12, 1,5X, 'X19 -',F7.3,3X,'XZO-',F7.3,3X,'XZ1-',
6F7.3,3X,'XL-',F7.3,/1
550 CONTINUE
C ACCUMULATE EFFEeTS OF LOAOS IN ANY SPAN
00 99 ll. NN,L
IFILL.LE.NPIGO TO 97
PILLI - WLOAO.XILLI
IFILL.EO.NP+l.0R.NN.EO.LIOZ ,. OZ - XILLI/Z.
97 RR" OZ.PILLI/SPAN
RL ,. PILlI - RR
PTIKCI ,. PTIKCI - RR
PlIKC-ZI ,. PTIKC-ZI - RL
DZ • OZ - XIlll
SUMP ,. SUMP + PILLI
99 CONTINUE
SUMPT = SUMPT + PTIKel
IFIJJ.EO.IMISUMPT - SUMPT + PTIKC-ZI
Z ,. 1M - JJ
DZ ,. Z.SPAN + TOTSUM - AOXH
NN = LL
SU MI ,. O.
10Z CONTINUE
C WRITE ONLY VERTICAL VALUES Al PANEL POINTS IHORIZ ,. 0.1 SO CAN
C USE PRINTEO OUTPUT TO OESIGN TRANSVERSE FLOOR 8EAMS
C 8ASEO ON LARGEST PANEL LOAD - FLOOR 8EAM REAeTIONS
C ANO DEPENOING ON NUM8ER OF TRAeKS ON 8RIOGE •• ooes NOT
C INCLUDE ANY IMPAeT FACTOR •••••••••
WRITEI3,Z0081I,IPTIJI,J-Z,NY,ZI
Z008 FORMATIII,2X,15.1ZF10.Z,I, 5X,lZF10.Z./1
WRITEI3,Z0091SUMP,SUMPT
Z009 FORMATI50X,'SUM TRUSS LOAOS • ',F10.Z,3X, 'SUM NOOE LOAOS - "
1Fl O.Z,11
00 138 J - l,NY
PRlJ,Il '" PTlJI
138 CONTINUE
140 CONTI NUE
1~1 WRJTEI3,ZOll11
ZOll FORMATIII,5X, 'ONLY UNIFORM LOAD ON 8RIOGE, I - ',13.111
IFIIPUNCK.LE.OIGO TO 1~9
1Ml '" I - 1

<!-- p. 595 -->

GENERADOR DE LA MATRIZ DE CARGA SEGUN EL AREA 595

C .PPlY IMPACT FACTOR TO lOAOS IF IMP > O
IFCIMP.lE.OIGO TO 25
00 143 J - 1,IMl
00 142 KK - 2,NY,2
142 PRCKK.JI - PRIKK,JI.PAC
143 CONTlNUE
25 KK - 2
00 145 J - 1,NSPN
KK • KK + 2
JJ - NPSIJI
lfRITEl2,10061JJ
lfRITEI2.20141IPRIKK.MI.M-1.1M11
2014 FORMATI8Fl0.41
145 CONTlNUE
149 GO TO 5000
148 lfRITEC3,20161
2016 FORMATIIII.5X.·... PR08lE" TERMINATED--XIll IS NEGATIVE ••• ·.1111
150 STOP
ENO

C •• FOllOWING 4 CAROS TYPICAl SET OF FPS OATA FOR 9 PANEL TRUSS
J E 80MlES AREA 8RIOGE FOR TeXT USING COOPER E-80 lOAOING ANO IMPACT
9 O O 1 O
3.45 27.60 17.00 1.0
4 8 12 16 20 24 28 32
e •• FOllOMING 4 CAROS TYPICAl ~ET OF SI DATA FOR 9 PANEL TRUSS
J E BOlflES AREA 8RIOGE FOR TEXT USING COOPER E-80 lOAOING. I"PACT ANO ST
9 1 1 1 O
1.05 8.40 5.20 1.0
4 8 12 16 20 24 28 32
l.

<!-- p. 596 -->



<!-- p. 597 -->

INDICE

AASHTü, con flexión, 368 Angulares estructurales soldados, 487
AASHTü, fórmulas para columnas, 302 angulares de asiento, 489
atiesados, 493Acción de arranque en las conexiones, conexiones en esquinas, 502 441 placas terminales, diseño de las, 499
AISC, fórmulas para columnas del AISC, Angulos auxiliares, 415
301 Aplastamiento del alma:
con flexión, 365 trabes, 543
Análisis de armaduras, 78 vigas, 183
codificación para la computadora, 79 AREA, con flexión, 368
AREA, distribución de las cargas sobreAnálisis aproximado de marcas, 72 la vía, 218
método del portal, 72 AREA, espesor mínimo del metal, 555
método del voladizo, 73 AREA, fórmulas para columnas, 303
torsión en el, 75 Area neta:
Análisis de vigas, 75 a tensión, 251,258,265
con flexión asimétrica, 196 diámetro efectivo del agujero para,
265 ecuación diferencial, 77
en columnas, 303 flexión biaxial, 192 en la raíz de la rosca, 251
Angulares, como miembros en tensión, uso de 82 j4g, 266
261 Areas roscadas en tensión, 251
sección neta con agujeros, 269 tabla de datos de diseño para, 263
597

<!-- p. 598 -->

598 INDICE

Articulación plástica, su longitud, 149 situación del juego deruedasAASHTO
Atiesadores, de apoyo, 186, 539, 542, para las, 520
557 tabla de factores, 157
angulares de asiento para los, 493 Cargas, 33
diagonales, para conexiones de esqui- cortantes y momentos tabulados,área,
na, 503 44
patín de la columna, 483 de encharcamiento, 42
alma, 481 de impacto, 48
de nieve, 40 equeridos para las trabes, 514
mapa para la, 41 espaciamiento de los, 557,559
de viento, 37, 44 intermedios, 540, 556, 559
ecuaciones para cortante y momento, longitudinales, AASHTO, 557 43 momento de inercia de los, 542, en puentes: AASHTO, 42, 43 559
AREA,46
excéntricas, sobre los sujetadores,
425
muerta, 33Basler, K., 535, 540, 543
sísmica, 50Bendigo, R., 409
viva, 33, 34Bleich, F., 160 Cargas vivas, 33Butler, L. J., 476 reducción por, 34
Ce para columnas, 301
valores tabulados de, 303
Cables, 249, 255 Celosías:
amortiguamiento de los, 280 fuerza cortante en, 316
datos de diseño, tablas de, 256 secciones armadas para, 315
ecuaciones de diseño para los, 278 Centro de cortante, 200
módulo de elasticidad de los, 257 constante J, 200
Cálculo del cortante en vigas, 171, 186 Chen, W. F.. 483
AISC, 315 Chesson, E., 413
en barras de celosía: AASHTO y Cm para vigas-columnas, 363, 367
AREA,3l5 Cochrane, Y., 266
en trabes, 525 Códigos estructurales, lista de, 32
Capacidad de la soldadura en el punto Coeficiente de expansión, 18
de corte, 525 Coeficiente de expansión térmica, 20
Cargas de viento, 37 Columna Research Council, 206 (ConCargas en edificios, 33 sejo para la investigación en columCargas en puentes, tabla de coeficientes nas)
para, 214 Columnas, 293
Cargas excéntricas sobre los sujetadores Cm' 363, 367
o conectores, 425 escalonadas, 378
reducción de la AISC, 433 factores K para, 351, 378
Cargas sísmicas, 50 fórmulasde,359,364,365,368
mapa de la zona, 53 longitud efectiva, 348, 351
periodo de las, 51 vigas-columnas, 341
Cargas sobre las trabes, 520 Columnas escalonadas, 377
AREA,522 factor K para, 378

<!-- p. 599 -->

INDICE 599

Conexi6n: Diseño de vigas compuestas, 220
en esquina soldada, 502 construcci6n apuntalada, 221
en placa terminal soldada, 499 tabla de relaciones modularespara el,
Condiciones de carga, 90 223
Conexiones de colgantes, 441 Diseño elástico, 136
soluci6n de Dranger para las, 442 Diseño plástico, 136, 140
Conexiones de las vigas, 435 Diseño por factor de resistencia de carga
Conexiones estructurales, 435 (DFRC).157
soldadas, 487 Disque, R., 353
Conexiones soldadas, AISC, 475 Distancia de la reacción en las vigas, 184
Conexiones tipo 1, 395,4&0 soporte lateral en las, 186
Constante de alabeo, Cw,204 Distancia de los sujetadores al borde, 410
Constante de torsión, J, 200,204 Distancia de paso, sujetador, 266
Constantes, de diseño: Cb , 705 Dranger, T., 441
Cw,204 Ductilidad, 17
J. 200
Contraventeo, control de la deflexión
lateral, 384
Cubreplacas Edificios industriales, 60
perforadas, 207 Eenam, N., 557
vigas armadas. 522 Efectos de las bajas temperaturas, 28
Curvas de esfuerzo-deformaci6n, 26,135 Ejes principales de flexi6n, 196
producto de inercia, 196
Electrodos, métodos para designarlos,
466Datos de los perfiles estructurales, tabla Erickson, E., 553
de, 21 Esfuerzo cortante permisible: en vigas,
Deflexión, en vigas, 148, 171, 189 186
Deflexi6n lateral. control de la, 384 en trabes, 537Densidad de masa del acero, 22 Esfuerzos combinados, flexión, 192,345Desgarramiento laminar de las soldadu- conexiones soldadas, 486, 488 ras, 475 en columnas, 359DFRC, 157
en los sujetadores de las conexiones, conexiones, 457
447 diseño de columnas, 334
diseño de las vigas-columnas, 286 su interacción en trabes armadas de
diseño de miembros a tensión, 284 alma llena, 540, 560
diseño de vigas. 241 Esfuerzos de soldadura, permisibles, 469
Diafragmas para trabes, 560 tabla, 471
Diámetro efectivo del agujero, 257 Esfuerzos de tensi6n, 25 1
Diseño de columnas, etapas en el, 304 área neta efectiva para, 257
Diseño de las barras de ojo, .54 valores permisibles, 251
Diseño de las conexiones, 2', 1 Esfuerzos en las vigas, 171
carga mínima, AISC, 271, 413 a flexión, 171
conexiones de asiento. 399,416 a flexi6n biaxial, 193
conexiones de frícc.ón, 397, 416 cortante, 171, 186
distancias al borde, 409 diseño elástico, 175
factor de seguridad en el, 419 permisibles: AASHTO y AREA, 178
soldadas, tipo 1, 481 AISC, 176,203
tipos 1, 11,I1I, 395, 451 sin soporte lateral, 203

<!-- p. 600 -->

600 INDICE

Esfuerzos, permisibles: diseño de la pla- -- Hansen, R., 409
ca de base, 328
a compresi6n: AASHTO, 302
AISC, 299
AREA,303 Johnston, B., 160,352
a flexi6n, 175,203,528,534,553
a tensión, 251
soldadura, 469
tabla de valores, 254 Krishnamurthy, N., 499
cortante, 171, 186 Kulak, G. L., 476
en las almas de las trabes, 539, 551
interacción, 358
sujetadores, tablas, 401,407,416-418
Esfuerzos residuales, 140,532 Largueros de puentes, 214
Esfuerzos secundarios, 343 Longitud efectiva de las columnas, 298
r-t; 345 control de la, 385
Espaciamiento de los tornillos, 412 en marcos, 348
Espesor mínimo: sin deflexi6n lateral, 298
AASHTO,554 tabla de casos, 299
AREA,554 Longitud no soportada lateralmente, 205
Espesor mínimo del metal, 555 Le' 177,323
Excentricidad reducida de los sujetado- Lu,l97
res, 433

Método de análisis por rigidez, 72
Fabricante, de acero, 19 Módulo de elasticidad, 20
Factores de conversión a SI, 67 a cortante, 20
Factor de forma, 143 Módulo de secci6n plástico, 143
Factor de seguridad, 146 factor de forma, 143
diseño elástico para el, 146 Módulo tangente, 160
diseño plástico para el, 148 Munse, W., 413
en las conexiones, 419 Muros de cortante, 385
Factor K:
columnas escalonadas, 378
nomograma para columnas, 352
Fahrenheit, conversión a Celsius, 20 Newlin, D. E., 482
Fatiga, 56, 262 Newmark, N. M., 214
Fisher, J., 418 Nomograma de Julian y Lawrence, 351
Flexión, en columnas, 342
permisible para vigas-columnas, 359
Fórmula de Euler para columnas, 295
definición del esfuerzo F;, 353 Pandeo en placas, 158
Fractura frágil, 30 en las placas de las ménsulas, 430
Perfiles armados, para columnas, 312
celosías para las, 313, 317
para miembros en tensión, 259
Galambos, T. V., 384 valores tabulados de r, para algunos
Gramil de los sujetadores, 266,412 perfiles, 312

<!-- p. 601 -->

INDlCE 601

Perfiles estructurales, 22-25 Soldadura de ranura, 469, 473
Perfiles, laminados, 22·25 especificaciones AISC para, 473
Pernos de cortante, 226 Soldadura de mete, 468, 472, 477
Peso unitario del acero, 22 uso del DFRC para soldaduras de fiPlacas de base, columnas, 326 lete, 508
criterios de diseño para las, 329 Soldaduras:
esfuerzos de flexión en las, 329 desgarramiento laminar de las, 475
lechada de las, 326 orientación para resistencia, 476
soldadas, 497 tamaño máximo, 473
Protección contra incendios, 28 tamaño mínimo, tabla, 474
Puentes, terminología usada en, 64 Soldaduras de tapón, 473Puntal de rodilla, en trabes, 561
especificaciones A1SC para, 473 fuerza en las trabes, 562
Soldaduras, tipos de, 358, 472 marcos industriales, 60
Punto de fluencia, 20 electrodos usados para, 468
tabla de valores para el acero, 21 Soporte lateral:
para columnas, 333
para trabes, 560
puntal de rodilla, 561
Radio de giro, 205, 271, 293, 318,352 para vigas, 177, 183,203
celosías para, 317 Sujetadores o conectores:
fórmula de Euler usada en, 299 cortante y tensión combinados, 447
miembros armados, tablas, 312 tabla de valores para los, 449
patín de compresión de las vigas, 209 esfuerzos permisibles, 401, 407, 415Rango de esfuerzos: . 418
definición, 57 resistencia última, 401
tabla de valores, 58 roscas en el plano de cortante, 415
Relación L]r:
miembros a compresión, 297, 299,
316
miembros a tensión, 264, 271,272, Temperatura vs resistencia, 28
277 Tensores, 263
Relación modular Es/Ee, 223 Thürlimann, B., 534
Relaciones: Timoshenko y Goodier, 160
afh, 533, 540, 558 Tornillos, de alta resistencia, 403
bit, 177, 523, 531,553,557 A-307,403
d/t, 176 instalación de, 406
hit, 514, 543, 555 tensión mínima, tabla de, 407
u-, 302, 311, 316, 352 Trabe armada:
Resistencia de fluencia, 25 diseño de la, 528, 529
Resistencia última, 20 AASHTO,553
tabla de valores, 21 AISC, 530
Rezago del cortante, 413 AREA, 553
longitud de la junta como factor del, esfuerzos: a flexión, 529, 530, 534,
409 553Rumpf, J., 409 cortante, en el alma, 538, 555
interacción, 540
placa del alma, 533, 554
Sandhu, B., 378 aplastamiento en la, 542
Soldadura a tope, 469, 477 espesor de la placa del, 554

<!-- p. 602 -->

602 INDlCE

uso de la, 515 Vigas-columnas, 341
longitudes, típicas, 515 factores G para las, 351
relaciones DjL, típicas, 515, 516 fórmulas de diseño: AASHTO y
Trabes, esfuerzos de flexi6n: permisibles, AREA,368
AASHTO,553 AISC, 359,365-366
pennisibks,AISC, 530,534 Cm para, 363,367,368
permisibles, AREA, 553 longitud efectiva de las, 348, 351
Trabes, vigas armadas que funcionan métodos de diseño, 368
nomograma para el factor K, 351 como, 523
cubreplacas de longitud parcial, 525 reducci6n por efecto inelástico, 353
Vigas continuas, 181 especificaciones para, 525
momentos para el diseño de las, 181 puntos de corte, 525
punto de inflexión, 183 híbridas, 518 Vigas de puente, 214 propiedades de las, 521, 528 AREA,2l6
AASHTO,214
compuestas, 220, 222
pernos de cortante para las, 226Valores de las tablas (véanse las tablas
distribución de las cargas de las rue- espectficast
das, tabla de coeficientes, 216Vigas:
cálculo de los esfuerzos, 173
criterios de la sección compacta, 176
Wallaert, J., 418 deflexiones, 173
sin apoyo lateral, 203
tipos de, 75,170,181,212,213
Vigas acarteladas, 212 Yura, J., 352

\-000 -

<!-- p. 603 -->

INGENIERfA CIVIL OBRAS PUBLICADAS
ISBN 0320 American Hospital MANUAL DE
Association INGENIERfA DE
HOSPITALES
406 páginas
ISBN 1275 Martiniano Aguilar CRITERIOS DE DISEÑO
Rodríguez DE PLANTAS
TERMOELÉCTRICAS
380 páginas
ISBN 1706 José Antonio UNA INTRODUCCiÓN
Aguirre Balcells AL ESTUDIO DE
PERFILES
AERODINÁMICOS Y
SUS APLICACIONES
AL CONSUMO DE
ENERGÉTICOS
152 páginas
ISBN 0449 Albert Schlag HIDRÁULICA
296 páginas
ISBN 1383 James Ambrose DISEÑO
SIMPLIFICADO DE
ESTRUCTURAS DE
EDIFICIOS
272 páginas
ISBN 1803 James Ambrose DISEÑO SIMPUFICADO
Dimitry Vergun DE EDIFICIOS
Para cargas de viento y
sismo
296 páginas
ISBN 0450 James M. Antill MÉTODO DE 'LA RUTA
Ronald W. CRfTICA y SU
Woodhead APLICACiÓN A LA
CONSTRUCCiÓN
320 páginas
ISBN 3014 Francisco J. FUNDAMENTOS DE
Aparicio Mijares HIDROLOGfA DE
SUPERFICIE
304 páginas
ISBN 1988 Christopher Arnold CONFIGURACiÓN Y
Robert Reitherman DISEÑO SfSMICO DE
EDIFICIOS
300 páginas

<!-- p. 604 -->

INGENIERíA CIVIL OBRAS PUBLICADAS

ISBN 2344 Gabriel Auvinet IMPERMEABILIZACiÓN
Raúl Esquivel DE LAGUNAS
ARTIFICIALES
84 páginas

ISBN 2528 Rubén Ávila Espinosa FUNDAMENTOS DE
MANTENIMIENTO
Guías econ6micas,
técnicas y
administrativas
180 páginas

ISBN 1498 Nabor Ballesteros TOPOGRAFíA
Tena 476 páginas

ISBN 1153 B. Austin Barry TOPOGRAfÍA APUCADA
A LA CONSTRUCCiÓN
348 páginas
ISBN 1853 Enrique Bazán Zurita MANUAL DE DISEÑO
Roberto Meli Piralla SíSMICO DE EDIFICIOS
242 páginas
ISBN 1623 Joseph E. Bowles DISEÑO DE ACERO
ESTRUCTURAL
602 páginas
ISBN 1197 Boris Bresler CONCRETO
REFORZADO EN
INGENIERíA. VOL. 1
Materiales,elementos
estructurales
552 páginas

ISBN 0454 Boris Bresler DISEÑO DE
T.Y. Un ESTRUCTURAS DE
John B. Scalzi ACERO
928 páginas

ISBN 1750 Rafael Colindres Selva ESTRUCTURAS
HIPERESTÁTICAS
288 páginas

ISBN 1484 Rafael Colindres Selva DINÁMICA DE SUELOS
Y ESTRUCTURAS
Aplicadas a la
ingeniería sísmica
648 páginas

<!-- p. 605 -->

ISBN 0122 Ramón Companys PLANIFICACiÓN DE
PROYECTOS
Métodos
PERT-ROY-CPM y
derivados
448 páginas

ISBN 1259 John P. Cook CONSTRUCCIONES
COMPUESTAS
376 páginas

ISBN 0458 John P. Cook SELLADORES Y
ADHESIVOS PARA
CONSTRUCCiÓN
Biblioteca L1MUSA para
la industria de la
construcción

ISBN 0459 Miguel Ángel Gorzo INTRODUCCiÓN A LA
INGENIERíA DE
PROYECTOS
228 páginas

ISBN 0109 Carlos Crespo Villalaz VrAS DE
COMUNICACiÓN
Caminos, ferrocarriles,
aeropuertos, puentes y
puertos
688 páginas

ISBN 1416 Carlos Crespo Villalaz MECÁNICA DE
SUELOS Y
CIMENTACIONES
4! edición
572 páginas

ISBN 1938 Carlos Crespo Villalaz PROBLEMAS
RESUELTOS DE
MECÁNICA DE
SUELOS Y DE
CIMENTACIONES
164 páginas

ISBN 0021 Robert Crimmins TRABAJOS DE
Reuben Samuels CONSTRUCCiÓN EN
Bernard P. Monahan ROCA
252 páginas

<!-- p. 606 -->

ISBN 0461 David A Day MAQUINARIA PARA
LA CONSTRUCCiÓN
616 páginas

ISBN 1741 David A. Day MAQUINARIA PARA LA
CONSTRUCCiÓN (tela)
616 páginas

ISBN 0462 Osear de Buen DISEÑO DE
López de Heredia ESTRUCTURAS DE
ACERO
Comportamiento y
diseño
676 páginas

ISBN 1242 Jorge Iván Díaz RESISTENCIA DE
Aguilar MATERIALES
Sergio H. Zapata 580 páginas

ISBN 1627 D.J. Dowriek DISEÑO DE
ESTRUCTURAS
RESISTENTES A
SISMOS
Para ingenieros y
arquitectos
414 páginas

ISBN 0467 Jaeob Feld FALLAS TÉCNICAS EN
LA CONSTRUCCiÓN
456, páginas

ISBN 0468 Gordon A Fletcher ESTUDIOS DE SUELOS
Vernon A. Smoots y CIMENTACIONES EN
LA INDUSTRIA DE LA
CONSTRUCCiÓN
Biblioteca LIMUSA para
la industria de la
construcción
476 páginas

ISBN 1605 AJ. Francis INTRODUCCiÓN A LAS
ESTRUCTURAS
Para arquitectura e
ingeniería
316 páginas

<!-- p. 607 -->

ISBN 2891 Instituto Mexicano CONCRETO
del Cemento y del ARQUITECTÓNICO
Concreto COLADO EN OBRAS
92 páginas

ISBN 2819 Instituto Mexicano EL CONCRETO EN LA
del Cemento y del OBRA. VOL. I
Concreto 128 páginas

ISBN 2723 Instituto Mexicano CONTROL DEL
del Cemento y del AGRIETAMIENTO DE
Concreto ESTRUCTURAS DE
CONCRETO
144 páginas

ISBN 2622 Instituto Mexicano CONTROL DE
del Cemento y del CALIDAD DEL
Concreto CONCRETO
72 páginas

ISBN 2724 . Instituto Mexicano CURADO ACELERADO
del Cemento y del DEL CONCRETO A
Concreto PRESiÓN
ATMOSFÉRICA
104 páginas

ISBN 2725 Instituto Mexicano CURADO DEL
del Cemento y del CONCRETO
Concreto 54 páginas

ISBN 2980 Instituto Mexicano DISEÑO DE JUNTAS
del Cemento y del VIGA-COLUMNA EN
Concreto ESTRUCTURAS DE
CONCRETO (ACI 352)
72 páginas

ISBN 3061 Instituto Mexicano PRÁCTICA PARA
del Cemento y del DOSIFICAR
Concreto CONCRETO NORMAL,
CONCRETO PESADO V
CONCRETO MASIVO
76 páginas

ISBN 2818 Instituto Mexicano DURABILIDAD DEL
del Cemento y del CONCRETO
Concreto 88 páginas

<!-- p. 608 -->

ISBN 2939 Ingenieros Civiles EXPERIENCIAS
Asociados DERIVADAS DE LOS
SISMOS DE
SEPTIEMBRE DE 1985
(tela)
138 páginas

ISBN 3127 Ingenieros Civiles EXPERIENCIAS
Asociados DERIVADAS DE LOS
SISMOS DE
SEPTIEMBRE DE 1985
(rústica). 132 páginas
ISBN 2368 Instituto Mexicano de MANUAL DE
la Construcción en CONSTRUCCiÓN EN
Acero ACERO
238 páginas
ISBN 3060 Instituto Mexicano DETALLES Y
del Cemento y del DETALLADO DEL
Concreto ACERO DE REFUERZO
DEL CONCRETO
(ACI-315-80)
144 páginas
ISBN 2722 Instituto Mexicano ADOQUINES DE
del Cemento y del CONCRETO
Concreto 136 páginas
ISBN 2983 Instituto Mexicano AGREGADOS PARA
del Cemento y del CONCRETO
Concreto 96 páginas
ISBN 2815 Instituto Mexicano DISEÑO Y
del Cemento y del CONSTRUCCiÓN DE
Concreto ESTRUCTURAS DE
BLOQUES DE
CONCRETO
164 páginas
ISBN 2982 Instituto Mexicano CARTILLA DEL
del Cemento y del CONCRETO (ACI-SPI)
Concreto 84 páginas
ISBN 2816 Instituto Mexicano CIMBRAS, MATERIALES,
del Cemento y del MONTAJE Y
Concreto ACCESORIOS. VOL. "
160 páginas

<!-- p. 609 -->

ISBN 2891 Instituto Mexicano CONCRETO
del Cemento y del ARQUITECTÓNICO
Concreto COLADO EN OBRAS
92 páginas

ISBN 2819 Instituto Mexicano EL CONCRETO EN LA
del Cemento y del OBRA. VOL. I
Concreto 128 páginas

ISBN 2723 Instituto Mexicano CONTROL DEL
del Cemento y del AGRIETAMIENTO DE
Concreto ESTRUCTURAS DE
CONCRETO
144 páginas

ISBN 2622 Instituto Mexicano CONTROL DE
del Cemento y del CALIDAD DEL
Concreto CONCRETO
72 páginas

ISBN 2724 'Instituto Mexicano CURADO ACELERADO
del Cemento y del DEL CONCRETO A
Concreto PRESiÓN
ATMOSFÉRICA
104 páginas

ISBN 2725 Instituto Mexicano CURADO DEL
del Cemento y del CONCRETO
Concreto 54 páginas

ISBN 2980 Instituto Mexicano DISEÑO DE JUNTAS
del Cemento y del VIGA-COLUMNA EN
Concreto ESTRUCTURAS DE
CONCRETO (ACI 352)
72 páginas

ISBN 3061 Instituto Mexicano PRÁCTICA PARA
del Cemento y del DOSIFICAR
Concreto CONCRETO NORMAL,
CONCRETO PESADO Y
CONCRETO MASIVO
76 páginas

ISBN 2818 Instituto Mexicano DURABILIDAD DEL
del Cemento y del CONCRETO
Concreto 88 páginas

<!-- p. 610 -->

ISBN 2621 Instituto Mexicano DISEÑO DE
del Cemento y del ESTRUCTURAS DE
Concreto CONCRETO
CONFORME AL
REGLAMENTO
(ACI-318-83). TOMO I
320 páginas

ISBN 2623 Instituto Mexicano DISEÑO DE
del Cemento y del ESTRUCTURAS DE
Concreto CONCRETO
CONFORME AL
REGLAMENTO (ACI
318-83). TOMO 11
284 páginas
ISBN 2620 Instituto Mexicano PRAcTICA
del Cemento y del RECOMENDABLE
Concreto PARA EVALUACiÓN
DE RESULTADOS DE
PRUEBAS DE
RESISTENCIA DEL
CONCRETO
48 páginas
ISBN 2726 Instituto Mexicano DISEÑO DE LOSAS
del Cemento y del POSTENSADAS
Concreto 160 páginas
ISBN 2984 Instituto Mexicano CONSTRUCCiÓN DE
del Cemento y del LOSAS Y PISOS DE
Concreto CONCRETO (ACI 302
IR-80)
160 páginas
ISBN 2981 Instituto Mexicano RECOMENDACIONES
del Cemento y del PARA LA
Concreto CONSTRUCCiÓN DE
PAVIMENTOS Y BASES
DE CONCRETO
92 páginas
ISBN 2624 Instituto Mexicano REGLAMENTOS DE LAS
del Cemento y del CONSTRUCCIONES DE
Concreto CONCRETO REFORZADO
(ACI318-83) y
COMENTARIOS
600 páginas

<!-- p. 611 -->

ISBN 0069 Eulalio Juárez Badillo MECÁNICA DE
Alfonso Rico SUELOS. 3! edición
Rodríguez Fundamentos de la
mecánica de suelos
Volumen I
504 páginas
ISBN 0128 Eulalio Juárez Badillo MECÁNICA DE
Alfonso Rico SUELOS. 3! edición
Rodríguez Teoría y aplicaciones
de la mecánica de
suelos
Volumen"
562 páginas
ISBN 0471 Eulalio Juárez Badillo MECÁNICA DE
Alfonso Rico SUELOS. 3ª edición
Rodríguez Flujo de agua en suelos
Volumen 11I
414 páginas

ISBN 0472 Donald 1. Katz INGENIERrA
Robert O. Goetz Conceptos y
Edward R. Lady perspectivas con
Dale C. Ray ejemplos y problemas
168 páginas
ISBN 1142 Edward Krick FUNDAMENTOS DE
INGENIERrA
Métodos, conceptos y
resultados
424 páginas
ISBN 1083 Edward Krick INTRODUCCiÓN A LA
INGENIERrA V AL
DISEÑO EN LA
INGENIERrA
Guía para el instructor
52 páginas
ISBN 1894 T. William Lambe MECÁNICA DE SUELOS
Robert V. Whitman 584 páginas
ISBN 0478 Jesús Llamas Zamora MANUAL PRÁCTICO
PARA ÁJUSTE DE
APARATOS
TOPOGRÁFICOS
144 páginas

<!-- p. 612 -->

ISBN 1445 Jatln MacSai CONJUNTOS
HABITACIONALES
544 páginas
ISBN 2295 Uriel Mancebo del TEORfA DEL GOLPE
Castillo DE ARIETE Y SUS
APLICACIONES EN
INGENIERfA
HIDRÁULICA
248 páginas
ISBN 1737 Raúl J. Marsal PRESAS DE TIERRA Y
Daniel Reséndiz ENROCAMIENTO
548 páginas
ISBN 0482 Manuel Medina ELEMENTOS DE
Peralta ASTRONOMíA DE
POSICiÓN
148 páginas
ISBN 2640 T.M. Megaw TÚNELES
J.v. Bartlett Planeaci6n, diseño y
construcción
Volumen I
332 páginas
ISBN 1671 Roberto Meli Piralla DISEÑO ESTRUCTURAL
582 páginas
ISBN 2619 TECNOLOGíA DEL Adam M. Neville
Instituto Mexicano CONCRETO. VOL. I
del Cemento y del 288 páginas
Concreto
ISBN 2817 Adam M. Neville TECNOLOGfA DEL
Instituto Mexicano CONCRETO. VOL. 11
del Cemento y del 328 páginas
Concreto
ISBN 2820 Adam M. Neville TECNOLOGíA DEL
Instituto Mexicano CONCRETO. VOL. 111
del Cemento y del . 404 páginas
Concreto
ISBN 1304 Arthur H. Nilson DISEÑO DE
ESTRUCTURAS DE
CONCRETO
PRESFORZADO
604 páginas

<!-- p. 613 -->

ISBN 2894 José Luis Ordóñez MANUAL PARA LA
AUTOADMINISTRACIÓN
DE CONDOMINIOS
132 páginas

ISBN 0490 Portland Cement FABRICACiÓN DE
Association CONCRETO Y
ACABADOS
88 páginas

ISBN 0491 Portland Cement INTERACCiÓN
Association ESTRUCTURAL EN
MARCOS Y MUROS
CORTANTES
52 páginas

ISBN 0488 Portland Cement PROYECTO Y
Association CONTROL DE
MEZCLAS Y
CONCRETO
164 páginas

ISBN 0487 Portland Cement DISEÑO DE
Association PAVIMENTOS DE
CONCRETO PARA
AEROPUERTOS
88 páginas

ISBN 0489 Portland Cement PRESAS PEQUEÑAS
Association DE CONCRETO
64 páginas
ISBN 0100 R. Park ESTRUCTURAS DE
T. Paulay CONCRETO
REFORZADO
796 páginas
ISBN 1794 R. Park LOSAS DE CONCRETO
w.L. Gamble REFORZADO
688 páginas

ISBN 0484 Harry Parker DISEÑO
SIMPLIFICADO DE
ARMADURAS DE
TECHO PARA
ARQUITECTURA Y
CONSTRUCCiÓN
290 páginas

<!-- p. 614 -->

ISBN 0005 Harry Parker INGENIER(A DE
CAMPO SIMPLIFICADO
Para arquitectos y
constructores
264 páginas .

ISBN 2323 Harry Parker DISEÑO
SIMPLIFICADO DE
CONCRETO
REFORZADO
320 páginas
ISBN 0485 Harry Parker INGENIER(A
SIMPLIFICADA
Para arquitectos y
constructores
366 páginas
ISBN 0063 Harry Parker DISEÑO
SIMPLIFICADO DE
ESTRUCTURAS DE
MADERA
296 páginas
ISBN 0486 Harry Parker TEXTO SIMPLIFICADO
DE MECÁNICA Y
RESISTENCIA DE
MATERIALES
308 páginas
ISBN 1414 Ralph B. Peck INGENIER(A DE
Walter E. Hanson CIMENTACIONES
Thomas H. Biblioteca L1MUSA para
Thorburn la industria de la
construcción
544 páginas
ISBN 0428 William G. Rapp MONTAJE DE
ESTRUCTURAS DE
ACERO EN LA
CONSTRUCCiÓN DE
EDIFICIOS
404 páginas
ISBN 1705 Paul F. Rice DISEÑO
Edward S. Hoffman ESTRUCTURAL CON
NORMAS DE ACI
518 páginas

<!-- p. 615 -->

ISBN 0054 Alfonso Rico LA INGENIERrA DE
Hermilo del Castillo· SUELOS EN LAS VrAS
TERRESTRES
Carreteras, ferrocarriles
y aeropistas
Volumen I
460 páginas

ISBN 0079 Alfonso Rico LA INGENIERrA DE
Hermilo del Castillo SUELOS EN LAS VrAS
TERRESTRES
Carreteras, ferrocarriles
y aeropistas
Volumen 11
644 páginas

ISBN 1510 Francisco Robles ESTRUCTURAS DE
Fernández Villegas MADERA
Ramón Echenique 368 páginas
Manrique

ISBN 1961 Delfino Rodríguez DISEÑO PRÁCTICO DE
Peña ESTRUCTURAS DE
ACERO
384 páginas

ISBN 2760 Sociedad Mexicana CIMIENTOS
de Mecánica de PROFUNDOS
Suelos COLADOS EN SITIO
192 páginas

ISBN 0500 Andrew Short CONCRETO LIGERO
William Kinniburgh Cálculo, fabricación,
diseño y aplicaciones
672 páginas

ISBN 1579 Paschoal Silvestre FUNDAMENTOS DE
HIDRÁULICA GENERAL
384 páginas

ISBN 1598 Andrew L. Simon HIDRÁULICA BÁSICA
234 páginas

ISBN 1800 Andrew L. Simon HIDRÁULICA PRÁCTICA
424 páginas

<!-- p. 616 -->

ISBN 2727 Sociedad Mexicana VOCABULARIO DE
de Mecánica de MECANICA DE SUELOS
Suelos Términos usados en
Latinoamérica
112 páginas

ISBN 0503 Gilberto Sotelo Ávila HIDRAuLlCA GENERAL
Fundamentos
Volumen I
564 páginas

ISBN 0506 George B. Sowers INTRODUCCiÓN A LA
George F. Sowers MECANICA DE
SUELOS Y
CIMENTACiÓN
680 páginas

ISBN 1904 David L. Stoner LA SEGURIDAD EN
HOSPITALES
254 páginas

ISBN 1189 Carlos Suárez Salazar ADMINISTRACiÓN DE
EMPRESAS
CONSTRUCTORAS
336 páginas

ISBN 0067 Carlos Suárez Salazar COSTO y TIEMPO EN
EDIFICACiÓN
452 páginas

ISBN 3058 Carlos Suárez Salazar MANUAL DE COSTOS
Y PRECIOS EN LA
CONSTRUCCiÓN 1989
364 páginas

ISBN 2842 Luis Carlos Suárez MANUAL DEL
Carlos Hinojosa ALUMINIO
Salazar 116 páginas

ISBN 1513 Carlos Suárez Salazar EL RÉGIMEN DE
Augusto Fernández TRANSICiÓN EN LA
Sagardi EMPRESA
Alberto Espíndola CONSTRUCTORA
Gómez 138 páginas

<!-- p. 617 -->

ISBN 1157 Francisco Torres OBRAS HIDRÁULICAS
Herrera 276 páginas

ISBN 0511 S. Peter Volpe NORMAS y
PROCEDIMIENTOS EN
LA INDUSTRIA DE LA
CONSTRUCCiÓN
212 páginas

ISBN 0514 Richard N. White INGENIER(A
Peter Gergely ESTRUCTURAL
Robert G. Sexsmith Comportamiento de
miembros y sistemas
Volumen 3
632 páginas

ISBN 0513 Richard N. White INGENIER(A
Peter Gergely ESTRUCTURAL
Robert G. Sexsmith Estructuras
estáticamente
indeterminadas
Volumen 2
366 páginas

ISBN 0512 Richard N. White INGENIER(A
Peter Gergely ESTRUCTURAL
Robert G. Sexsmith Introducción a los
conceptos de análisis y
diseño
Volumen 1
284 páginas

ISBN 0518 Robert M. Rose PROPIEDADES
Lawrence A. ELECTRÓNICAS
Shepard Ciencia de los
John Wulff materiales
Volumen IV
316 páginas

ISBN 0516 William G. Moffatt ESTRUCTURA
George W. Pearsall Ciencia de los
John Wulff materiales
Volumen I
244 páginas

<!-- p. 618 -->

ISBN 1044 IMCYC RECOMENDACIONES
PARA EL DISEÑO
Y CONSTRUCCiÓN
DE SILOS DE
CONCRETO
180 páginas
ISBN 1041 IMCYC PROBLEMAS EN
EL CONCRETO
Causas y soluciones
268 páginas
ISBN 1049 IMCYC DISEÑO DE
CONEXIONES
DE ELEMENTOS
PREFABRICADOS
DE CONCRETO
126 páginas
ISBN 1050 IMCYC INTRODUCCiÓN
A. H. AJlen AL CONCRETO
PRESFORZADO
100 páginas
ISBN 1048 IMCYC CIMBRAS y MOLDES
John G. Richardson Guia práctica para su
construcción y uso
116 páginas
ISBN 1053 IMCYC CIMBRAS. Diseño
John G. Richardson VOL. 1
186 páginas
ISBN 1033 IMCYC ACERO DE REFUERZO
DE ALTA RESISTENCIA
(ACI439)
104 páginas
ISBN 1031 IMCYC COMPACTACiÓN
DEL CONCRETO
128 páginas
ISBN 1030 IMCYC PRAcTICA
RECOMENDABLE
PARA LA MEDICIÓN,
MEZCLADO,
TRANSPORTE Y
COLOCACiÓN
DEL CONCRETO
96 páginas

<!-- p. 619 -->

ISBN 1045 IMCYC ESTRUCTURAS
DE CONCRETO
PARA EL
MEJORAMIENTO
DEL MEDIO
AMBIENTE
100 páginas
ISBN 1051 IMCYC CONCRETO
T.F.Ryan LANZADO
72 páginas
ISBN 1038 IMCYC CONCRETO
PRESFORZADO
SOMETIDO A BAJAS
TEMPERATURAS
176 páginas
ISBN 1036 IMCYC DEMOLICiÓN.
ESTRUCTURAS
ISBN 1039 IMCYC PRODUCCiÓN DE
GRANDES VOLÚMENES
DE CONCRETO
144 páginas
ISBN 3270 T. M. Megaw TÚNELES. Planeación,
J. V. Bartlett diseño y construcción
VOL. 2
360 páginas
'SBN 3072 IMCYC DISEÑO DE
ESTRUCTURAS
DE CONCRETO
CONFORME AL
REGLAMENTO
ACI-318-83
Volumen 111
240 páginas
ISBN 3073 IMCYC CIMBRAS: FALLAS,
J. G. Richardson SEGURIDAD DE
LA CIMBRA Y
DESCIMBRADO
104 páginas
ISBN 1054 IMCYC DISEÑO DE
ESTRUCTURAS
RESISTENTES
A SISMOS
424 páginas

<!-- p. 620 -->

ISBN 1043 IMCYC EL CONCRETO
DE LA OBRA
VOL. 11I
132 páginas
ISBN 1040 IMCYC ESTRUCTURAS
DE CONCRETO
RESISTENTES
AL FUEGO
184 páginas

ISBN 3281 IMCYC FERROCEMENTO
B. K. Paúl 232 páginas
R. P. Pama

ISBN 3443 IMCYC ADITIVOS
SUPERFLUIDIFICANTES
PARA CONCRETO
108 páginas
ISBN 1038 IMCYC CONCRETO
PRESFORZADO
SOMETIDO A BAJAS
TEMPERATURAS
176 páginas

ISBN 3280 IMCYC EL CONCRETO DE
LA OBRA
VOL. U
160 páginas

ISBN 1032 IMCYC CRITERIOS
GENERALES PARA
EL PROVECTO
BÁSICO DE
ESTRUCTURAS
DE CONCRETO
120 páginas
ISBN 1042 IMCYC PRODUCTOS
PREFABRICADOS
DE CONCRETO
132 páginas

ISBN 1037 IMCYC DISEÑO DE VIGAS
Pan E. Branson DE CONCRETO
PRESFp'RZADO
112 páginas

<!-- p. 621 -->

ISBN 0517 H. Wayne Hayden PROPIEDADES
William G. Moffatt MECÁNICAS
John Wulff La ciencia de los
materiales
Volumen 111
256 páginas

ISBN 0045 Jere H. Brophy PROPIEDADES
Robert M. Rose TERMODINÁMICAS
John Wulff La ciencia de los
materiales
208 páginas

ISBN 1237 Leonardo Zeevaert INTERACCiÓN
SUELO-ESTRUCTURA
DE CIMENTACiÓN
256 páginas
