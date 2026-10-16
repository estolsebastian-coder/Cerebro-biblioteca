---
type: libro
title: "Glonass"
author: "dblanco"
categoria: "TOPOGRAFÍA"
paginas: 4
extraccion: "texto"
fuente: "local:E:/MATERIAL DE CONSULTA/TOPOGRAFÍA/agrimensura/Glonass.pdf"
convertido: 2026-10-16
---

# Glonass

> Texto extraído de `TOPOGRAFÍA\agrimensura\Glonass.pdf` (4 páginas, texto). El PDF original está en el disco E: (MATERIAL DE CONSULTA); `<!-- p. N -->` marca el inicio de cada página.

<!-- p. 1 -->

FACULTAD DE INGENIERIA INSTITUTO DE AGRIMENSURA
DEPARTAMENTO DE GEODESIA

INTRODUCCION AL SISTEMA GLONASS

A principios de los 70s, quizá como una respuesta al desarrollo del Sistema GPS, el antiguo
Ministro de Defensa Soviético desarrolló el Sistema Global de Navegación por Satélite
(GLONASS). El Sistema GLONASS es similar al GPS en muchos aspectos, aunque como se
verá también hay muchas diferencias.
En el año 1993, oficialmente el Gobierno Ruso colocó el programa GLONASS en manos de
Fuerzas Espaciales Militares Rusas (RSF). Este organismo es el responsable del desarrollo de
satélites GLONASS, de su mantenimiento y puesta en órbita, y certificación a los usuarios. Este
organismo opera en colaboración con el CSIC (Coordinational Scientific Information Center), el
cual publica la información sobre GLONASS.
Durante los 80s, la información acerca de GLONASS era escasa. No se sabía mucho de las
órbitas de los satélites ni de las señales usadas para transmisión de las señales de
navegación. Pero actualmente, gracias a estudios e investigaciones sobre este sistema, se
dispone ya de gran cantidad de información acerca GLONASS. Los Rusos, a través del RSF y
del CSIC publican el documento ICD (Interface Control Document). Este documento es similar
en estructura al Segmento Espacial del sistema NAVSTAR GPS, donde se describe el sistema,
sus componentes, estructura de la señal y el mensaje de navegación para uso civil.

Los planes de GLONASS en sus comienzos eran el de ofrecer dos niveles de servicio:

• El Channel of Standard Accuracy (CSA), similar al Standar Positioning Service (SPS) del
Sistema GPS, disponible para uso civil.
• El Channel of High Accuracy (CHA), similar al Precise Positioning Service (PPS) del
Sistema GPS, disponible solo para usuarios autorizados.

La Organización Internacional de Aviación Civil (ICAO) aceptó formalmente en Julio 1996, el
uso de GLONASS/CSA para uso en aviación civil, como se hizo en 1994 con el GPS/SPS.

DESCRIPCIÓN DEL SISTEMA

El Sistema GLONASS, al igual que el Sistema GPS, está formado por tres sectores
fundamentales: el Sector de Control, el Sector Espacial y el Sector Usuario.

\1) EL SECTOR DE CONTROL

El Sector de Control está formado por un Sistema Central de Control (SCC) en la región de
Moscú y una red de estaciones de seguimiento y control (Command Tracking Stations, CTS),
emplazadas por todo el área alrededor de Rusia. El Sector de Control GLONASS, al igual que
el de GPS, debe seguir y vigilar el estado de sus satélites, determinar las efemérides y errores
de los relojes de los satélites, es decir, la diferencia entre el tiempo GLONASS y la escala de
tiempo UTC. Además también deben actualizar los datos de navegación de los satélites. Estas
actualizaciones se realizan dos veces al día.

Las estaciones de control (CTSs) realizan el seguimiento de los satélites y almacenan los datos
de distancias y telemetría a partir de las señales de los satélites. La información obtenida en
las CTSs es procesada en el Sistema Central de Control (SCC) para determinar los estados de
las órbitas y relojes de los satélites, y para actualizar el mensaje de navegación de cada
satélite. Esta información es enviada a cada satélite por medio de las CTSs. Las CTSs calibran
periódicamente los datos de distancias a los satélites mediante láser. Para ello, los satélites
GLONASS van provistos de unos reflectores especiales.

La sincronización de todos estos procesos en el Sistema GLONASS es muy importante. Para
conseguir esta sincronización, se dispone de un reloj atómico de hidrógeno de alta precisión, el

<!-- p. 2 -->

FACULTAD DE INGENIERIA INSTITUTO DE AGRIMENSURA
DEPARTAMENTO DE GEODESIA

cual determina la escala de tiempo GLONASS. Los satélites GLONASS llevan a bordo un reloj
de cesio y se sincronizan respecto a la State Etalon en Mendeleevo, a través de la escala de
tiempo del sistema GLONASS.

\2) EL SECTOR ESPACIAL

El Sector Espacial está formado por la constelación de satélites. La constelación completa se
compone 24 satélites en tres planos orbitales separados 120º entre sí. Cada plano contiene 8
satélites espaciados regularmente, con argumento de latitud de 45º. Los planos están
inclinados 64,8º respecto al Ecuador. Los satélites GLONASS se encuentran a una distancia de
aproximadamente 19100 Km y se sitúan en órbitas casi circulares con semieje mayor de
aproximadamente 25510 Km, siendo el periodo orbital de 11 horas y 15 minutos.
El primer satélite se lanzó el 12 de Octubre de 1982, y en la actualidad sólo 13 están
operativos.
Cada satélite GLONASS dispone de un pequeño reflector, que es usado para el seguimiento
de los satélites por láser desde las estaciones de control.

\3) EL SECTOR DEL USUARIO

El Sistema GLONASS es un sistema militar y civil. Todos los usuarios militares y civiles
constituyen el Sector Usuario.

Un equipo de recepción de señales GLONASS, al igual que uno de GPS, está formado por una
antena y un receptor. La antena suele llevar un plano de tierra para evitar el efecto multipath,
es decir, la recepción de señales reflejadas en el suelo u otros objetos, que empeoran la
precisión. Los receptores disponen de un reloj para sincronizar las señales recibidas.

CARACTERÍSTICAS DE LA SEÑAL GLONASS

Los satélites GLONASS llevan a bordo relojes atómicos de Cesio con un oscilador de
frecuencia fundamental de 5 MHz. A partir de esta frecuencia fundamental se pueden obtener o
modular los códigos C/A y P, de frecuencias 0.511 MHz y 5.11 MHz respectivamente. En la
señal también se introduce un mensaje de 50 bits por segundo. La banda L1 funciona en la
frecuencia 1602 + 0.5625 · k MHz, donde k es el canal (0-24), lo genera un rango de
frecuencias que van desde 1602 - 1615.5 MHz. La banda L2 funciona en la frecuencia 1246 +
0.4375 · k MHz, lo que genera un rango de frecuencias que van desde 1246 - 1256.5 MHz. Por
lo tanto cada satélite tiene una frecuencia diferente.

GLONASS transmite el código P en ambas bandas L1 y L2 y el código C/A, de momento sólo
en la banda L1.
A diferencia de los satélites GPS, todos los satélites GLONASS transmiten los mismos
códigos. Esto es así porque en GLONASS la identificación de los satélites se hace por la
frecuencia de las portadoras y no por el PRN de los códigos como se hace en GPS.
MENSAJE DE NAVEGACION

El mensaje de navegación se transmite con una velocidad de 50 bit/s y se modula junto con los
códigos C/A y P. El mensaje de navegación GLONASS del código C/A divide los datos en
datos operacionales o inmediatos y datos no operacionales o no inmediatos.
Los datos operacionales son las efemérides, los parámetros de reloj y época del reloj del
satélite. Las efemérides de los satélites se dan en términos de posición, velocidad, y vector de
aceleración de la época de referencia.

<!-- p. 3 -->

FACULTAD DE INGENIERIA INSTITUTO DE AGRIMENSURA
DEPARTAMENTO DE GEODESIA

Los datos no operacionales comprenden el almanaque (o efemérides aproximadas) de la
constelación, junto con los estados de salud de todos los satélites GLONASS. Los datos de
salud de los satélites no tienen tiempo de actualización. Además, en los datos no
operacionales hay un parámetro que indica la diferencia entre el sistema de tiempo GLONASS
y el UTC. Estos datos se determinan para el comienzo de cada día.
Los parámetros de efemérides son generalmente cargados en cada satélite una vez al día. Los
parámetros de reloj son grabados dos veces al día. El mensaje completo tiene una duración de
2 min. y 30 seg., pero las efemérides y la información de reloj se repite cada 30 seg.

EL TIEMPO DEL SISTEMA GLONASS

El Sistema GLONASS dispone de un sistema de tiempos (GLONASST) y de un sistema de
referencia propio y distinto al de GPS. El tiempo GLONASS está referido al UTC(SU) (tiempo
universal coordinado determinado para Rusia). El UTC(SU) se diferencia en unos
microsegundos al UTC(BIPM) (tiempo universal coordinado determinado por el Bureau
Internacional de Pesos y Medidas). El NTFS (National Time and Frecuency Service) se
encarga de que el desfase sea de un microsegundo o menos. Para ello, en determinadas
ocasiones se introduce un salto de unos segundos, a diferencia del tiempo GPS que no
requiere de estos saltos.

EL SISTEMA DE REFERENCIA DATUM PZ-90

Las efemérides GLONASS están referidas al Datum Geodésico Parametry Zemli 1990 o PZ-90,
o en su traducción Parámetros de la Tierra 1990 o PE-90. Este sistema reemplazó al SGS-85,
usado por GLONASS hasta 1993.
El sistema PZ-90 es un sistema de referencia terrestre con coordenadas definidas de la misma
forma que el Sistema de Referencia Internacional Terrestre (ITRF). Las constantes y
parámetros del PZ-90 se muestran en la siguiente tabla:

Parámetro Valor
Rotación de la Tierra 72.92115 · 10-6 rad/s
Constante Gravitacional 398600.44 · 109 m3/s2
Constante Gravitacional de la atmósfera 0.35 · 109 m3/s2
Velocidad de la luz 299792458 m/s
Semieje mayor del elipsoide 6378136 m
Aplanamiento del elipsoide 1 / 298.257839303
Aceleración de la gravedad en el Ecuador 978032.8 mgal

La realización del Sistema PZ-90 por medio de la adopción de coordenadas de estaciones de
referencia ha dado como resultado el desfase en el origen y orientación de los ejes, así como la
diferencia en escala con respecto al ITRF y al Sistema WGS-84.
USO COMBINADO DE LOS SISTEMAS GPS Y GLONASS

Los Sistemas GPS y GLONASS son sistemas autónomos, es decir, cada uno tiene su propio
sistema de referencia y su propio sistema o escala de tiempo. Usan diferentes sistemas de
referencia para expresar las posiciones de sus satélites, y por lo tanto, para determinar las
posiciones de los usuarios.

Para poder utilizar los dos Sistemas de Posicionamiento por Satélite, GPS y GLONASS, es
decir, recibir señales de los satélites de la constelación GPS y de la constelación GLONASS,
es necesario establecer la relación entre los sistemas de tiempo y sistemas de referencia
utilizados en los dos sistemas. El Sistema GPS utiliza el sistema de referencia WGS-84,

<!-- p. 4 -->

FACULTAD DE INGENIERIA INSTITUTO DE AGRIMENSURA
DEPARTAMENTO DE GEODESIA

mientras que el Sistema GLONASS utiliza el PZ-90. Los parámetros que definen los dos
sistemas de referencia son significativamente diferentes.

Con la disponibilidad de receptores GPS/GLONASS, el usuario puede tener acceso a un
sistema combinado de hasta 48 satélites (con la dos constelaciones completas). Con todos
estos satélites, los trabajos en desfiladeros y otras localizaciones de visibilidad restringida, tales
como áreas boscosas, etc., es mejorada debido a la posibilidad de mayor información de más
satélites. El tiempo de inicialización para alcanzar precisiones de nivel centimétrico mejora en
un factor de 3 a 6 con una constelación de 48 satélites.
Además existe una mayor confianza en los datos calculadas, para un mismo tiempo de
observación.

Los parámetros que definen los dos sistemas de referencia PZ-90 y WGS-84 son
significativamente diferentes. Para poder utilizar el sistema combinado GPS/GLONASS es
necesario el conocimiento de las posiciones de todos los satélites utilizados, satélites GPS y
GLONASS, en el mismo sistema de referencia. Para ello, lo que se realiza es el paso de las
posiciones de todos los satélites GLONASS al sistema de referencia WGS-84, y así trabajar
con la constelación de los 48 satélites en un mismo sistema de referencia.
Además de la unificación del sistema de referencia, es necesario establecer también la relación
entre los dos sistemas o escalas de tiempo utilizados. Esto se resuelve por medio de la
información contenida en los mensajes de navegación de cada uno de los sistemas, donde
aparecen las diferencias entre los tiempos GPS o tiempos GLONASS con respecto al Tiempo
Universal Coordinado.
Para obtener las efemérides de los satélites GLONASS en el sistema WGS-84 es necesario
conocer los parámetros de transformación de PZ-90 a WGS-84, para lo cual se necesita un
cierto número de satélites GLONASS con coordenadas en ambos sistemas.
Las coordenadas de los satélites GLONASS en PZ-90 aparecen en el mensaje de navegación
que mandan los satélites. La estimación de las posiciones de los satélites GLONASS en WGS84 es realizada por una serie de estaciones de seguimiento que utilizan técnicas de medición
láser, radar y ópticas para la determinación de las órbitas. Estas estaciones están localizadas
por todo el mundo.

Una vez que tenemos los parámetros de la transformación del sistema PZ-90 al sistema WGS84 ya podemos tener las efemérides de todos los satélites GLONASS en el sistema WGS-84, y
por lo tanto podremos utilizar el sistema combinado GPS/GLONASS.
