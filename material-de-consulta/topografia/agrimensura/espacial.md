---
type: libro
title: "espacial"
author: "dblanco"
categoria: "TOPOGRAFÍA"
paginas: 8
extraccion: "texto"
fuente: "local:E:/MATERIAL DE CONSULTA/TOPOGRAFÍA/agrimensura/espacial.pdf"
convertido: 2026-10-16
---

# espacial

> Texto extraído de `TOPOGRAFÍA\agrimensura\espacial.pdf` (8 páginas, texto). El PDF original está en el disco E: (MATERIAL DE CONSULTA); `<!-- p. N -->` marca el inicio de cada página.

<!-- p. 1 -->

FACULTAD DE INGENIERIA INSTITUTO DE AGRIMENSURA
DEPARTAMENTO DE GEODESIA

EFEMÉRIDES DEL SISTEMA DE POSICIONAMIENTO GLOBAL GPS

Tres sistemas de datos están disponibles para la determinación de los vectores de posición y
velocidad de los satélites en un marco terrestre de referencia para cualquier instante. Estos
sistemas son: datos del almanaque, efemérides transmitidas, y efemérides precisas.
Los datos se diferencian en su exactitud y en que están disponibles en tiempo real o después
del evento.

DATOS DEL ALMANAQUE

El propósito del almanaque es el de proveer al usuario de datos menos exactos para facilitar la
búsqueda de los satélites por parte del receptor o para las tareas de planificación tales como el
cálculo de las máscaras de la visibilidad del horizonte. El almanaque es transmitido por el
mensaje de los satélites y esencialmente contiene parámetros de la representación de la órbita,
parámetros de corrección de los relojes del satélite, y otras informaciones.

EFEMERIDES TRANSMITIDAS

Están basadas en observaciones de cinco de las estaciones de monitoreo del segmento de
control del sistema GPS. Estas estaciones reciben permanentemente las señales emitidas por
los satélites y envían las observaciones a la Estación de Control Maestro, quien se encarga de
calcular las órbitas de los satélites. Para el cálculo orbital se realiza el razonamiento inverso al
del cálculo de la posición del receptor. Se invierten los papeles que cumplen la posición del
receptor, que pasa a ser el dato conocido en lugar de la incógnita a determinar y la posición del
satélite, que pasa a ser la incógnita a determinar en lugar del dato conocido. Todas las
estaciones poseen una ubicación perfectamente conocida y es con respecto a ellas que se
determinan las posiciones de los satélites GPS. Estas estaciones determinan el marco de
referencia utilizado por el GPS, denominado WGS84 (World Geodetic System 1984). Con todas
las observaciones colectadas a lo largo de 7 días por las estaciones de rastreo, la estación de
control maestro calcula la órbita de los satélites GPS. Esta órbita refleja el movimiento de los
satélites en el período que fue realizado el cálculo y no el movimiento presente. La estación de
control maestro utiliza las órbitas calculadas para predecir órbitas que describan el movimiento
de los satélites en el futuro. Luego estas órbitas predichas son enviadas desde tierra a los
satélites. De esta manera, cuando se realizan observaciones, es el mismo satélite quien le
transmite al usuario la órbita que describe su propio movimiento en el momento de la
observación.

Estas órbitas se definen a través de los elementos keplerianos de las mismas, con parámetros
adicionales de perturbación.

<!-- p. 2 -->

FACULTAD DE INGENIERIA INSTITUTO DE AGRIMENSURA
DEPARTAMENTO DE GEODESIA

Los parámetros se refieren a una época de referencia dada toe para las efemérides y toc para
el reloj, teniendo validez por un lapso de tiempo de más o menos dos horas antes y dos horas
después de la época de referencia. Por lo tanto, se obtiene la representación de la trayectoria
satelital a través de una secuencia de distintas órbitas de Kepler disturbadas. Cada 120
minutos, se transmite un grupo de datos nuevos, lo cual ocasiona pequeños saltos que se
pueden distinguir al superponer las distintas representaciones. Estos saltos pueden alcanzar
algunos decímetros de altura. La precisión de las coordenadas de los satélites a partir de las
efemérides transmitidas es generalmente de 1 a 3 m..

EFEMERIDES PRECISAS

Las efemérides precisas son determinadas por el International GPS Service (IGS), en base a
los datos recogidos por sus estaciones de referencia GPS distribuidas por todo el globo
terrestre. El IGS calcula dos tipos de soluciones:
Una primera solución rápida (código igr) se calcula al finalizar cada día, una vez los Centros de
Análisis de Datos del IGS han recogido, de todas las estaciones de referencia, los datos GPS
registrados por las mismas durante el día anterior. Esta solución rápida igr está disponible 17
horas después del final del día correspondiente (24h UTC), y tiene una precisión que el propio
IGS estima en mejor que 5 cm. en cada una de sus tres componentes geocéntricas (X,Y,Z).
La solución final de las efemérides de precisión que procesa el IGS (código igs), resulta de una
combinación ponderada entre todos sus Centros de Análisis, siendo su actualización semanal y
no está disponible hasta 13 días después de concluida la semana GPS, a las 24 horas UTC de
cada sábado.

Las efemérides precisas se encuentran en archivos diarios (de 0:00 a 23:45 UTC) en el formato
ASCII universal SP3 que contiene las posiciones geocéntricas X, Y, Z, así como las
correcciones a sus relojes en intervalos de 15 minutos. Las posiciones están referidas al Marco
de Referencia Terrestre Internacional (ITRF).
Se encuentran disponibles para los usuarios en: http://igscb.jpl.nasa.gov

<!-- p. 3 -->

FACULTAD DE INGENIERIA INSTITUTO DE AGRIMENSURA
DEPARTAMENTO DE GEODESIA

CALCULO DE LA POSICIÓN DE UN SATELITE GPS

El usuario del sistema GPS debe tener acceso en tiempo real a las posiciones satelitales y al
tiempo del sistema satelital para resolver tareas de navegación. Esto es posible por medio de la
información orbital, es decir por medio del mensaje de navegación, que está contenido en la
señal de los datos (efemérides transmitidas). En este mensaje se encuentran parámetros que
describen la orbita satelital y el estado del reloj del satélite. En base a esto, se calculan las
coordenadas X, Y, Z del satélite referidas al sistema geodésico mundial WGS84 en tiempo real.
Los parámetros que describen la órbita de un satélite son (parámetros de Kepler referidos a
una época de referencia toe):

A = semieje mayor de la órbita.
e = excentricidad de la órbita.
io = ángulo de inclinación de la órbita.
Ωo = ascensión recta del nodo ascendente.
ω = argumento del perigeo.
Mo = anomalía media.

Ωo,io → ubican el plano orbital.
ω → determina la órbita en el plano orbital (ubica el perigeo).
A, e → determina la forma de la órbita.
Mo → sirve para ubicar la posición del satélite a la época de referencia.

Estos parámetros están incluidos en las efemérides transmitidas. Otros parámetros que se
transmiten con la señal GPS son:

Parámetros de Tiempo:

toe = tiempo de referencia para los parámetros de las efemérides (s).
toc = tiempo de referencia para los parámetros del reloj del satélite (s).
ao, a1, a2 = coeficientes polinomiales de corrección del reloj del satélite.

<!-- p. 4 -->

FACULTAD DE INGENIERIA INSTITUTO DE AGRIMENSURA
DEPARTAMENTO DE GEODESIA

Parámetros de Perturbación:

∆n = Diferencia de la moción media de los valores computados ( rad/s).
•
Ω = tasa de la ascensión recta (rad/s).
•
i = tasa de la inclinanción (rad/s).
Cus = Amplitud del término de corrección armónico del seno del argumento de latitud (rad).
Cuc = Amplitud del término de corrección armónico del coseno del argumento de latitud (rad).
Cis = Amplitud del término de corrección armónico del seno del ángulo de inclinación (rad).
Cic = Amplitud del término de corrección armónico del coseno del ángulo de inclinación (rad).
Cis = Amplitud del término de corrección armónico del seno del ángulo de inclinación (rad).
Crs = Amplitud del término de corrección armónico del seno del radio orbital (rad).
Crc = Amplitud del término de corrección armónico del coseno del radio orbital (rad).

CALCULO DEL TIEMPO

El tiempo del sistema GPS es una escala de tiempo atómica. Se caracteriza por el número
semanal y el número de segundos transcurridos desde el comienzo de la semana actual; por lo
tanto el tiempo GPS puede variar entre 0, al comienzo de una semana y 604800, al final de una
semana.
La época inicial de GPS es el 6 de enero de 1980 a las 0 horas de UTC. Es por eso que la
semana GPS comienza a medianoche del sábado (tiempo universal). En ese momento
coincidieron los tiempo GPS y UTC.
El tiempo del sistema GPS es una escala continua de tiempo definida por el reloj principal de
la Estación Central de Control. Los segundos desplazados en la escala de tiempo UTC y la
desviación en el reloj de la Estación indican que las escalas de tiempo UTC y GPS no son
idénticas. Esta diferencia es controlada continuamente por el segmento de control y se la
transmite a los usuarios en el mensaje de navegación.

Debido errores de frecuencia constantes e irregulares de los osciladores satelitales, difiere el
reloj del satélite respecto al tiempo del sistema GPS. El tiempo del satélite individual tSAT se
corrige para obtener el tiempo t del sistema GPS:

t = t SAT − ∆t SAT ∆ t SAT = a 0 + a 1 (t − t oc ) + a 2 (t − t oc )2

Las coordenadas cartesianas Xk, Yk, Zk se calculan para una época dada t (tiempo GPS),
referidas a un sistema convencional terrestre.
El tiempo tk necesario para éstos cálculos es el transcurrido desde la época de referencia toe de
los parámetros de las efemérides:

t k = t − t oe

<!-- p. 5 -->

FACULTAD DE INGENIERIA INSTITUTO DE AGRIMENSURA
DEPARTAMENTO DE GEODESIA

ARCHIVOS RINEX: Archivos de Intercambio de Información GPS.

Introducción.

El RINEX (Receiver Independent Exchange Format), son las siglas de un formato de
intercambio de información GPS. Fue presentado en el 5º Simposium Geodésico Internacional
de Posicionamiento por Satélites que tuvo lugar en Las Cruces (México) en marzo de 1989. En
Agosto de ese mismo año es recomendado por la Asociación Internacional de Geodesia (IAG)
como formato estándar de intercambio de ficheros GPS.
En este Simposium compitió con otros tres formatos de datos:
FICA (Floating Integer Character ASCII): desarrollado por el Applied Research Laboratory
de la Universidad de Texas.
ARGO (Automatic Reformatting GPS Observations), programa desarrollado por la NGS
estadounidense.
ASCII: Formato de intercambio ASCII de la Geodetic Survey de Canadá para uso interno.
Tras una serie de deliberaciones, finalmente se optó por el formato RINEX pero con una serie
de reformas sobre su desarrollo inicial.
El responsable de la primera versión de este formato fue el Instituto Astronómico de la
Universidad de Berna (Suiza), empleándose por primera vez en la campaña geodésica
EUREF-89 que realizó este mismo Instituto. En ella, se dispuso de 60 receptores de 4 marcar
distintas, por lo que la necesidad de disponer de un fichero de intercambio de datos que
facilitara el cálculo de bases en conjunto era primordial.
Esta primera versión del RINEX solamente era capaz de transformar los datos de
posicionamientos estáticos. Posteriores versiones incluyeron el resto de posicionamientos
(estático-rápido, pseudocinemático, cinemático, etc). La versión 2 salió a la luz en Septiembre
de 1990, en el Simposium de Ottawa (Canadá), resultando ser una versión abierta a futuras
pequeñas modificaciones, como la de 1993 que incluye un pequeño cambio en los datos
tomados bajo el Antispoofing (A/S), o la de inclusión de archivos de la constelación rusa
GLONASS de principios de 1997. La NGS es la institución que ha actuado como coordinador
de la normalización de este formato.

Base del Formato RINEX.

La base del RINEX parte de que la mayoríadel software para GPS emplea los siguientes
observables:
La medida de la portadora de fase en una o dos frecuencias (L1 o L1 y L2).
El tiempo obtenido en el instante de validar las medidas de fase y código.
La medida de la Pseudodistancia o código.

El RINEX implica que los datos binarios propios de cada tipo de receptor pueden ser
transformados a formato independiente universal ASCII durante el proceso de descarga,
permitiendo así usar otro tipo de software o intercambiar datos procedentes de otros
receptores. Dado que la estructura de los datos fuente (binario) difiere de cada receptor, es
necesario que cada proveedor de software GPS genere un interprete para este formato.
Dado que el RINEX es un archivo de intercambio de información cumple con la mayoría de los
condicionantes que se imponen a un fichero de intercambio (información únicamente
necesaria, fácilmente transportable entre los diversos sistemas operativos, no-redundancia de
datos, posibilidad de agregar nuevas observaciones), excepto con uno fundamental: la gran
longitud de sus ficheros. Inicialmente pudo haberse optado por la disminución de dicho tamaño
escogiendo un formato binario pero a costa de perder accesibilidad a su contenido y
disponibilidad para el usuario. En la actualidad con los programas de comprensión de ficheros
se consigue reducir indiscutiblemente el fichero RINEX en un factor de tres o más. Por ejemplo,
un archivo de medio día de observación, con épocas de 30 segundos, puede llegar a ocupar de
1.5-2 Mb fácilmente comprensibles a 500-600 kb o incluso menos. Pueden emplearse los ya
conocidos formatos de compresión (ARJ, ZIP), aunque la Universidad de Delft (Holanda) ha

<!-- p. 6 -->

FACULTAD DE INGENIERIA INSTITUTO DE AGRIMENSURA
DEPARTAMENTO DE GEODESIA

desarrollado un formato propio binario denominado CB18, especialmente diseñado para
RINEX.

Formato RINEX.

El formato RINEX se compone de la creación de cuatro tipos de archivos para su versión 2 en
adelante. Estos cuatro tipos son:

El fichero de los datos de observación.
El fichero de datos meteorológicos.
El fichero con el mensaje de navegación.
El fichero del mensaje de navegación del sistema GLONASS.

En las primeras versiones únicamente se disponía de dos ficheros, el de observación y el de
navegación.
La grabación de estos archivos tiene un máximo de 80 caracteres por línea, facilitando así una
fácil inspección del archivo en su visualización en la pantalla del ordenador, además cada
fichero se compone de una cabecera y de una sección de datos.
La cabecera contiene la información general del fichero como puede ser la relativa a la
estación, el receptor o la antena. La sección de datos contiene los datos referentes al tipo de
archivo. Los datos de observación y meteorología son creados para cada sesión y lugar,
mientras que el mensaje de navegación es independiente de estos.
La versión 2 de RINEX permite cabeceras adicionales para incluir nuevos registros en la
sección de datos. Esto es muy útil cuando se producen cambios en la información de la
estación durante la observación, como por ejemplo un cambio del método de observación
empleado: de rápido estático a cinemático. Dentro de cada cabecera es posible incluir
comentarios, solo hace falta situar el registro “END OF HEADER” al final de dichas líneas.
Cada fichero RINEX hace referencia a los datos recolectados por un receptor en una estación y
en una sesión. Aunque en la versión 2 es posible dejar colgado el fichero y recoger datos en
modo secuencial para medidas cinemáticas o estático- rápidas. Además, el RINEX de esta
versión permite combinar observaciones de otros sistemas de observación como puede ser el
TRANSIT.

Archivo de Navegación.

El fichero con el mensaje de navegación contiene los datos orbitales, los parámetros del reloj y
la precisión de las medidas de pseudodistancia de los satélites observados. Su cabecera
puede contener opcionalmente datos del mensaje de navegación tales como los parámetros
del modelo ionosférico para aparatos de una sola frecuencia y términos de correcciones
relacionados con los tiempos GPS y UTC. Una gran parte de este fichero está basado en el
formato ARGO de la NGS.
El fichero de navegación GLONASS sigue esta misma filosofía para su cabecera. Sin embargo,
la estructura de datos difiere mucho de la empleada por el GPS, sobre todo en lo que refiere a
los sistemas de tiempo empleados en las dos constelaciones. Además define las órbitas de los
satélites por sus coordenadas, insertadas desde las bases centrales a unas horas
determinadas e indicándose la antigüedad de dicha información. La definición del tiempo
GLONASS también ha dado sus problemas, siendo necesario indicar la procedencia del tiempo
de referencia de las observaciones.

Características del Archivo de navegación:

ETIQUETA DE CABECERA DESCRIPCION

RINEX VERSION / TYPE - Formato y tipo de fichero(“N” Navegación).

<!-- p. 7 -->

FACULTAD DE INGENIERIA INSTITUTO DE AGRIMENSURA
DEPARTAMENTO DE GEODESIA

PGM / RUN BY / DATE - Nombre, agencia y día de creación.

COMMENT - Comentario.

ION ALPHA - Parámetros ionosféricos A0-A3 del
almanaque.

ION BETA - Parámetros ionosféricos B0-B3 del
almanaque.

DELTA-UTC: A0,A1,T ,W - Parámetros del almanaque para calcular el tiempo
en el sistema UTC:
\* A0,A1: Términos del polinomio.
\* T: Tiempo de referencia para
datos UTC.
\* W: Número de la semana UTC
de referencia.

LEAP SECONDS - Error en el tiempo por el salto de segundo

END OF HEADER - Final de cabecera.

OBS. RECORD Grupo 1 -Número PRN, año, mes, día, hora, min., sec.
\- Error del reloj del satélite (s).
\- Deriva del reloj del satélite (s/s).
\- Período de deriva (s -1).

Grupo 2 - Edad de las efemérides (s).
\- Corrección Crs (m).
\- Diferencia media de movimiento (rad / s).
\- Anomalía media (rad).

Grupo 3 - Corrección Cuc (rad).
\- Excentricidad.
\- Corrección Cus (rad).
\- Raíz cuadrada del semieje mayor (m1/2).

Grupo 4 - Tiempo de las efemérides (segundos de semana
GPS).
\- Corrección Cic (rad).
\- Nodo de longitud (OMEGA) (rad).
\- Corrección Cis (rad).

Grupo 5 - Inclinación (rad).
\- Corrección Crc (m).
\- Argumento del perigeo (omega) (rad).
\- Velocidad del nodo de longitud (OMEGA DOT)
(rad/s) .

Grupo 6 - Velocidad de inclinación (IDOT) (rad / s)
\- Códigos en el canal L2.
\- Semana GPS.
\- Aviso de datos de código P en L2.

Grupo 7 - Precisión del satélite (m).

<!-- p. 8 -->

FACULTAD DE INGENIERIA INSTITUTO DE AGRIMENSURA
DEPARTAMENTO DE GEODESIA

\- Salud del satélite (entrada MSB).
\- Retardo ionosférico (TGD) (s).
\- Edad de los datos del reloj (s).

Grupo 8 - Tiempo de transmisión del mensaje (s de semana
GPS).
\- De repuesto / sin información.
\- De repuesto / sin información.
\- De repuesto / sin información.

Ejemplo de fichero de navegación de datos GPS:

2 NAVIGATION DATA RINEX VERSION / TYPE
EPHTORNX Version 2.1 08-OCT-97 13:39 PGM / RUN BY / DATE
END OF HEADER
14 97 10 8 9 59 60.0 0.228183344007D-04 0.341060513165D-12 0.000000000000D+00
0.590000000000D+02-0.460312500000D+02 0.431589386451D-08 0.123485942917D+01
\-0.239536166191D-05 0.151082023513D-02 0.914372503757D-05 0.515376567459D+04
0.295200000000D+06 0.279396772385D-07 0.136000332260D+01 0.130385160446D-07
0.969519034508D+00 0.206718750000D+03 0.294364805951D+01-0.789104337429D-08
0.140720143871D-09 0.100000000000D+01 0.926000000000D+03 0.000000000000D+00
0.700000000000D+01 0.000000000000D+00-0.232830643654D-08 0.590000000000D+02
0.000000000000D+00
16 97 10 8 9 59 44.0 0.310195609927D-04 0.159161572810D-11 0.000000000000D+00
0.820000000000D+02-0.466250000000D+02 0.445554260153D-08 0.109773916963D+01
\-0.235624611378D-05 0.221713271458D-02 0.879168510437D-05 0.515362895393D+04
0.295184000000D+06 0.465661287308D-07 0.136628704583D+01 0.186264514923D-07
0.965927376055D+00 0.210343750000D+03 0.664243366688D-01-0.796533150549D-08
0.717887069235D-10 0.100000000000D+01 0.926000000000D+03 0.000000000000D+00
0.700000000000D+01 0.000000000000D+00-0.232830643654D-08 0.820000000000D+02
0.000000000000D+00
