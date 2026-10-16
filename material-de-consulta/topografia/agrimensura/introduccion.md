---
type: libro
title: "Introduccion"
author: "dblanco"
categoria: "TOPOGRAFÍA"
paginas: 6
extraccion: "texto"
fuente: "local:E:/MATERIAL DE CONSULTA/TOPOGRAFÍA/agrimensura/Introduccion.pdf"
convertido: 2026-10-16
---

# Introduccion

> Texto extraído de `TOPOGRAFÍA\agrimensura\Introduccion.pdf` (6 páginas, texto). El PDF original está en el disco E: (MATERIAL DE CONSULTA); `<!-- p. N -->` marca el inicio de cada página.

<!-- p. 1 -->

FACULTAD DE INGENIERIA INSTITUTO DE AGRIMENSURA
DEPARTAMENTO DE GEODESIA

INTRODUCCION AL SISTEMA G.P.S.

GPS es la abreviatura de NAVSTAR GPS. Este es el acrónimo en inglés de NAVigation System
with Time and Ranging Global Positioning System (que en español significa Sistema de
Posicionamiento Global con Sistema de Navegación por Tiempo y Distancia). En geodesia
satelitaria, navegación y otros campos de aplicación, se denomina posicionamiento global al
que se logra a partir de un servicio que consta de una constelación que provee en forma
permanente cuatro o más satélites sobre el horizonte, a partir de los cuales es posible
determinar posiciones próximas a la superficie terrestre en forma permanente y hasta en
movimiento.
Hacia la década del sesenta la Armada de los Estados Unidos desarrolla un sistema de
navegación basado en satélites artificiales. Este sistema, conocido como TRANSIT, abrió una
nueva frontera en la tecnología de la navegación. En los años posteriores se llevaron a cabo
muy diversos proyectos y experimentos a los efectos de determinar posiciones próximas a la
superficie terrestre, pero continuaban siendo muy limitados en precisión y funcionalidad. A
principios de los años setenta se propuso un nuevo proyecto –el GPS-, basado en la medición
de distancias (con milímetros de precisión) a satélites artificiales. Este concepto prometía
satisfacer todos los requerimientos del gobierno de los Estados Unidos, principalmente el de
poder determinar (en cualquier momento y bajo cualquier condición atmosférica), una posición
precisa en cualquier punto de la superficie terrestre. La realización del sistema y el desarrollo
de sus posibilidades, insumirían más de veinte años.
El GPS es un sistema basado en satélites artificiales, dispuestos en una constelación de 24 de
ellos, para brindar al usuario una posición precisa. Las primeras aplicaciones principales de tipo
civil fueron para navegación y topografía. Hoy en día, el rango de aplicaciones va desde
navegación de móviles, hasta la automatización de maquinaria de construcción.

DESCRIPCIÓN DEL SISTEMA

Los conceptos operacionales básicos no difieren hoy de los pautados en 1973. GPS es un
sistema de posicionamiento basado en la medición de la distancia a un mínimo de cuatro
satélites simultáneos, que además, transmiten sus posiciones estimadas. Las distancias son
medidas comparando (correlacionando) la señal recibida desde el satélite con una réplica
generada por el receptor. La diferencia de fase entre la señal recibida y la generada localmente
es proporcional al tiempo de propagación (distancia satélite receptor). Como los receptores
generan la señal local usando relojes de cuarzo, la diferencia de fase absorbe también sus
inestabilidades. Observando un mínimo de cuatro satélites bien distribuidos en el cielo, el
receptor puede calcular cuatro incógnitas: tres para la posición del receptor y una para la
corrección al reloj local.

El sistema GPS comprende tres segmentos diferentes:

\1) EL SEGMENTO ESPACIAL

Consiste de 27 satélites distribuidos en seis planos orbitales inclinados 55º respecto al ecuador.
Los satélites se mueven a un altura aproximada de 20600 km, completando dos revoluciones
por día sidéreo. El segmento espacial está diseñado de tal forma que se pueda contar con un
mínimo de 4 satélites visibles por encima de un ángulo de elevación de 15º en cualquier punto
de la superficie terrestre, durante las 24 horas del día. Para la mayoría de las aplicaciones, el
número mínimo de satélites visibles deberá ser de cuatro. La experiencia ha demostrado que la
mayor parte del tiempo hay por lo menos 5 satélites visibles por encima de los 15º, y muy a
menudo hay 6 o 7 satélites visibles.

<!-- p. 2 -->

FACULTAD DE INGENIERIA INSTITUTO DE AGRIMENSURA
DEPARTAMENTO DE GEODESIA

Cada satélite GPS lleva a bordo varios relojes atómicos muy precisos. Estos relojes operan en
una frecuencia de fundamental de 10.23MHz, la cual se emplea para generar las señales
transmitidas por el satélite.

\2) EL SEGMENTO DE CONTROL

El segmento de control consistía en sus orígenes en una estación de control maestro en
Colorado Springs (EEUU), 5 estaciones de observación y 4 antenas de tierra distribuidas entre
5 puntos muy cercanos al ecuador terrestre.

En la actualidad se han anexado varias estaciones de rastreo: Australia, Quito, Usno, Buenos
Aires, Bahrain, Inglaterra
El segmento de Control tiene la función de:

Supervisar y controlar continuamente el sistema satelital.
Determinar el tiempo del sistema GPS.
Predecir las efemérides satelitales y el comportamiento de los osciladores en los satélites.
Actualizar periódicamente la información de navegación para cada satélite en particular.

El segmento de Control rastrea los satélites GPS, actualiza su posición orbital, calibra y
sincroniza sus relojes. Otra función importante consiste en determinar la órbita de cada satélite
y predecir su trayectoria para las siguientes 24 horas. Esta información es cargada a cada
satélite y posteriormente transmitida desde allí. Esto permite al receptor GPS conocer la
ubicación de cada satélite.

<!-- p. 3 -->

FACULTAD DE INGENIERIA INSTITUTO DE AGRIMENSURA
DEPARTAMENTO DE GEODESIA

Las señales de los satélites son leídas desde las estaciones de rastreo. Estas mediciones son
entonces enviadas a la Estación de Control Maestro en Colorado Springs, donde son
procesadas para determinar cualquier error en cada satélite. La información es enviada
posteriormente a las cuatro estaciones de observación equipadas con antenas de tierra y de
allí cargada a los satélites.

\3) EL SEGMENTO DEL USUARIO

El segmento de Usuarios comprende a cualquiera que reciba las señales GPS con un receptor,
determinando su posición y/o la hora. Algunas aplicaciones típicas dentro del segmento
Usuarios son: la navegación en tierra para excursionistas, ubicación de vehículos, topografía,
navegación marítima y aérea, control de maquinaria, etc.

PRINCIPIO DEL POSICIONAMIENTO SATELITARIO

El principio del posicionamiento satelitario es simple y se basa en relacionar tres componentes:

Una cantidad conocida, que es la posición del satélite (XS, YS, ZS).
Una cantidad mensurable, que es la distancia satélite receptor ρ.
Una cantidad desconocida, que es la posición del receptor (XR, YR, ZR).

s 2 s 2 s 2 ρ = (X − X R ) + (Y − YR ) + (Z − Z R )

El objetivo de la medición es obtener la posición de nuestro receptor en el mismo sistema de
referencia en el que se dan las coordenadas de los satélites.
La distancia satélite - receptor puede ser determinada por el receptor GPS. A partir de la
distancia hacia un satélite y la posición de éste, sabemos que la posición del receptor debe
estar en algún punto sobre la superficie de una esfera imaginaria cuyo origen es el satélite
mismo. Si consideramos tres satélites y sus respectivas distancias al receptor podemos
intersectar tres esferas imaginarias, con lo cual quedan definidos dos puntos de intersección.
Uno de ellos será una posición ilógica para ser la de nuestro receptor y la podremos descartar.

Luego veremos que existe una razón técnica adicional debido a la cual debemos involucrar un
cuarto satélite.

<!-- p. 4 -->

FACULTAD DE INGENIERIA INSTITUTO DE AGRIMENSURA
DEPARTAMENTO DE GEODESIA

MEDICION DE DISTANCIA SATELITE - RECEPTOR

Esta distancia se mide a partir del tiempo de propagación de la señal emitida desde el satélite.
Los satélites y los receptores cuentan con relojes que controlan el tiempo de emisión y
recepción de la señal respectivamente. De esta manera, la simple diferencia entre el instante
de recepción y el de emisión proporciona el tiempo de propagación, o sea, el tiempo que la
señal empleó para viajar desde el satélite hasta el receptor. Multiplicado por la velocidad de
propagación de la señal dicho tiempo se convierte luego en la distancia satélite – receptor.
Las señales GPS se propagan a la velocidad de la luz, aproximadamente 300000 km/s, es
decir, en un milisegundo la señal se propaga 300 km. Es por ello que la sincronización de los
relojes del satélite y del receptor es muy importante ya que un error entre los relojes de tan solo
1 milisegundo produce un error en la distancia de 300 km.
En los satélites se encuentran relojes atómicos de la mas alta tecnología que son controlados
permanentemente desde tierra por la Estación de Control. Los satélites transmiten al usuario
junto con la información orbital, las correcciones que deben ser aplicadas a sus relojes para
compensar los errores que éstos puedan ocasionar.
No es posible equipar a los receptores con relojes de tan alta tecnología pues su operación
sería muy complicada y muy costosa. Por esta razón los relojes de los receptores pueden estar
afectados de errores intolerables. Debido a ello la distancia determinada satélite – receptor se
denomina pseudo – distancia.

La posición de los satélites es un dato conocido que nos proveen en su emisión los mismos
satélites. La distancia entre el receptor y el satélite se puede determinar mediante la medición
del tiempo que la señal emplea en recorrer la trayectoria satélite – receptor. Con toda ésta
información ya podríamos determinar la posición del receptor. Pero para el problema real
encontramos una deficiencia adicional. Lo que medimos es seudo – distancias y no distancias
con lo que hay cuatro incógnitas a determinar, las tres coordenadas que definen la posición del
receptor y la corrección al reloj del receptor que permite convertir las seudo – distancias en
distancias, por lo tanto necesitamos medir la distancia a al menos cuatro satélites y no solo a
tres.

<!-- p. 5 -->

FACULTAD DE INGENIERIA INSTITUTO DE AGRIMENSURA
DEPARTAMENTO DE GEODESIA

LA SEÑAL GPS

Los satélites envían señales en la región de radio del espectro electromagnético.
Los satélites transmiten constantemente en dos ondas portadoras. Estas ondas
portadoras se encuentran en la banda L (utilizada para transmisiones de radio) y
viajan a la Tierra a la velocidad de la luz. Dichas ondas portadoras se derivan de
la frecuencia fundamental, generada por un reloj atómico muy preciso.

La portadora L1 es transmitida a una frecuencia de 1575.42 MHz (10.23 x 154) con una
longitud de onda de 19.05 cm.
La portadora L2 es transmitida a una frecuencia de 1227.60 MHz (10.23 x 120) con una
longitud de onda de 24.45 cm.

Las ondas portadoras están diseñadas para llevar los códigos binarios C/A y P en un
proceso conocido como modulación. Modulación significa que los códigos están
superpuestos sobre la onda portadora. Los códigos son códigos binarios. Esto significa
que sólo pueden tener dos valores -1 y +1. Cada vez que el valor cambia, hay un
cambio en la fase de la portadora.

Cada satélite transmite señales en ambas frecuencias, siendo éstas, las señales de
navegación (códigos), y los datos de navegación y sistema (mensaje).
Los códigos que se modulan en la señal son:
El Código C/A o Código de Adquisición Gruesa modula a una frecuencia de 1.023MHz
(10.23/10). Tiene una duración de un milisegundo y su longitud de onda es de
aproximadamente 300 m. El código C/A se transmite actualmente sólo por medio de la
frecuencia portadora L1.
El Código P o Código de Precisión modula a una frecuencia de 10.23MHz. La secuencia de
este código es de 267 días y su longitud de onda es de 29.31 cm. Se les ha asignado a los
distintos satélites porciones de siete días y como resultado de ello, todos los satélites
pueden trasmitir en la misma frecuencia y ser identificados por sus segmentos únicos de
una semana.
El código P se encuentra disponible en ambas frecuencias portadoras (L1 y L2) y las pseudo –
distancias derivadas de él tienen una mayor precisión que las obtenidas con el código C/A. La
Armada de los Estados Unidos ha decidido encriptar el código P generando un nuevo código
denominado Y, limitando su uso para usuarios no autorizados.

<!-- p. 6 -->

FACULTAD DE INGENIERIA INSTITUTO DE AGRIMENSURA
DEPARTAMENTO DE GEODESIA

Los datos de navegación GPS, llamados “mensaje”, están organizados de la siguiente manera:
El conjunto completo de datos está subdividido en cinco subconjuntos de seis segundos de
duración cada uno, lo que hace que el conjunto completo tiene un ciclo de tiempo de 30
segundos.

En estos subconjuntos podemos encontrar:

Subconjunto 1: Datos de los parámetros de los relojes de los satélites.
Subconjuntos 2 y 3: Datos de las efemérides transmitidas.
Subconjuntos 4 y 5: Datos del almanaque y parámetros Ionosféricos.

Los subconjuntos 4 y 5 no se repiten cada 30 segundos, diferenciándose de los otros
subconjuntos. Ambos subconjuntos contienen 25 páginas que aparecen sucesivamente. Cada
página contiene los datos de almanaque de un satélite de la constelación, de tal modo que se
dispone del contenido total de información cada 12.5 minutos.
