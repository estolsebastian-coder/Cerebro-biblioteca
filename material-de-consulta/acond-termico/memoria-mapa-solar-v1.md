---
type: libro
title: "memoria-mapa-solar-v1"
author: ""
categoria: "ACOND. TÉRMICO"
paginas: 65
extraccion: "texto"
fuente: "local:E:/MATERIAL DE CONSULTA/ACOND. TÉRMICO/memoria-mapa-solar-v1.pdf"
convertido: 2026-10-16
---

# memoria-mapa-solar-v1

> Texto extraído de `ACOND. TÉRMICO\memoria-mapa-solar-v1.pdf` (65 páginas, texto). El PDF original está en el disco E: (MATERIAL DE CONSULTA); `<!-- p. N -->` marca el inicio de cada página.

<!-- p. 1 -->

Mapa Solar del Uruguay
versi´on 1.0

Memoria T´ecnica

G. Abal, M. D’Angelo,
Instituto de F´ısica

J. Cataldo, A. Gutierrez
Instituto de Mec´anica de los Fluidos
e Ingenier´ıa Ambiental

Facultad de Ingenier´ıa

Universidad de la Rep´ublica

4 de junio de 2010

<!-- p. 2 -->

´Indice general

\1. Introducci´on 1

\2. Datos disponibles 4
2.1. Series de irradiaci´on . . . . . . . . . . . . . . . . . . . . . . . 4
2.1.1. Series Uruguayas . . . . . . . . . . . . . . . . . . . . . 5
2.1.2. Datos regionales de irradiaci´on . . . . . . . . . . . . . . 6
2.2. Series de Heliofan´ıa . . . . . . . . . . . . . . . . . . . . . . . . 7
2.3. Pre-tratamiento de los datos . . . . . . . . . . . . . . . . . . . 13
2.3.1. Geometr´ıa Solar . . . . . . . . . . . . . . . . . . . . . . 13
2.3.2. Irradiancia solar extra-atmosf´erica . . . . . . . . . . . . 15
2.3.3. Normalizaci´on . . . . . . . . . . . . . . . . . . . . . . . 16
2.3.4. Filtrado de datos . . . . . . . . . . . . . . . . . . . . . 20

\3. Mapa Solar del Uruguay 23
3.1. Metodolog´ıa . . . . . . . . . . . . . . . . . . . . . . . . . . . . 23
3.2. Mapas mensuales . . . . . . . . . . . . . . . . . . . . . . . . . 28
3.3. An´alisis de incertidumbre . . . . . . . . . . . . . . . . . . . . . 42
3.4. Validaci´on . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 45

\4. Comentarios Finales 54

i

<!-- p. 3 -->

´Indice de ﬁguras

2.1. Heliofan´ıa media mensual . . . . . . . . . . . . . . . . . . . . 9
2.2. Ubicaci´on de las series de datos utilizadas . . . . . . . . . . . 12
2.3. Movimiento aparente del Sol . . . . . . . . . . . . . . . . . . . 14
2.4. Heliofan´ıa para Artigas . . . . . . . . . . . . . . . . . . . . . . 16
2.5. Heliofan´ıa relativa promedio . . . . . . . . . . . . . . . . . . . 17
2.6. serie ZUELA . . . . . . . . . . . . . . . . . . . . . . . . . . . 18
2.7. Indice de claridad diario . . . . . . . . . . . . . . . . . . . . . 19
2.8. M´aximo m´ovil para series ZUELA y ARCHI . . . . . . . . . . 21
2.9. M´aximo m´ovil para series Melilla y Potrerillo . . . . . . . . . 22

3.1. Regresiones lineales . . . . . . . . . . . . . . . . . . . . . . . . 24
3.2. Variaci´on espacial de a y b . . . . . . . . . . . . . . . . . . . . 26
3.3. Mapa Solar del Uruguay - Enero . . . . . . . . . . . . . . . . . 29
3.4. Mapa Solar del Uruguay - Febrero . . . . . . . . . . . . . . . . 30
3.5. Mapa Solar del Uruguay - Marzo . . . . . . . . . . . . . . . . 31
3.6. Mapa Solar del Uruguay - Abril . . . . . . . . . . . . . . . . . 32
3.7. Mapa Solar del Uruguay - Mayo . . . . . . . . . . . . . . . . . 33
3.8. Mapa Solar del Uruguay - Junio . . . . . . . . . . . . . . . . . 34
3.9. Mapa Solar del Uruguay - Julio . . . . . . . . . . . . . . . . . 35
3.10. Mapa Solar del Uruguay - Agosto . . . . . . . . . . . . . . . . 36
3.11. Mapa Solar del Uruguay - Setiembre . . . . . . . . . . . . . . 37
3.12. Mapa Solar del Uruguay - Octubre . . . . . . . . . . . . . . . 38
3.13. Mapa Solar del Uruguay - Noviembre . . . . . . . . . . . . . . 39
3.14. Mapa Solar del Uruguay - Diciembre . . . . . . . . . . . . . . 40
3.15. Mapa Solar del Uruguay - Anual . . . . . . . . . . . . . . . . . 41
3.16. Error relativo para Jaguar˜ao y Bag´e . . . . . . . . . . . . . . . 46
3.17. Error relativo para localidades argentinas . . . . . . . . . . . . 47
3.18. Ubicaciones para estimadores del modelo UM-SBR . . . . . . 49
3.19. Mapa UM-SBR, Enero a Junio . . . . . . . . . . . . . . . . . 52
3.20. Mapa UM-SBR, Julio a Diciembre . . . . . . . . . . . . . . . . 53

ii

<!-- p. 4 -->

´Indice de cuadros

2.1. Series de irradiaci´on uruguayas analizadas . . . . . . . . . . . 6
2.2. Series de irradiaci´on del INMET . . . . . . . . . . . . . . . . . 7
2.3. Localidades Argentinas . . . . . . . . . . . . . . . . . . . . . . 7
2.4. Irradiaci´on diaria promedio . . . . . . . . . . . . . . . . . . . 8
2.5. Datos de heliofan´ıa analizados . . . . . . . . . . . . . . . . . . 10
2.6. Localidades con datos de heliofan´ıa . . . . . . . . . . . . . . . 11
2.7. Estaciones del INIA . . . . . . . . . . . . . . . . . . . . . . . . 11
2.8. Datos de heliofan´ıa utilizados . . . . . . . . . . . . . . . . . . 12
2.9. Heliofan´ıa relativa usada . . . . . . . . . . . . . . . . . . . . . 17
2.10. Datos de ´ındice de claridad usados . . . . . . . . . . . . . . . 20

3.1. Valores de a y b . . . . . . . . . . . . . . . . . . . . . . . . . 25
3.2. Valores de a y b para localidades con heliofan´ıa . . . . . . . . 27
3.3. Estimadores de irradiaci´on global . . . . . . . . . . . . . . . . 27
3.4. Error efectivo mensual . . . . . . . . . . . . . . . . . . . . . . 43
3.5. Incertezas de los coeﬁcientes a y b . . . . . . . . . . . . . . . . 43
3.6. Incerteza en irradiaci´on estimada . . . . . . . . . . . . . . . . 45
3.7. Estimadores de irradiaci´on diaria . . . . . . . . . . . . . . . . 46
3.8. Estimadores modelo UM-SBR . . . . . . . . . . . . . . . . . . 50
3.9. Comparaci´on MSU con modelo UM-SBR . . . . . . . . . . . . 50

iii

<!-- p. 5 -->

Cap´ıtulo 1

Introducci´on

A ra´ız del impulso que est´an recibiendo las fuentes de energ´ıa renovables
en nuestro pa´ıs, se ha planteado con fuerza la necesidad de contar con un
conocimiento adecuado del recurso solar promedio de que se dispone en diferentes zonas del pa´ıs. La informaci´on de calidad sobre la radiaci´on solar
incidente es un insumo clave para dise˜nar cualquier equipamiento para la
conversi´on de la energ´ıa solar en energ´ıa ´util (ya sea el´ectrica o t´ermica). Por
otra parte, en un pa´ıs esencialmente agr´ıcola, un conocimiento detallado del
recurso solar es ´util para estimar el rendimiento de las cosechas, dise˜nar dispositivos para el secado de productos vegetales o para planiﬁcar estrategias
de irrigaci´on.
Es una pr´actica com´un en el mundo presentar la informaci´on sobre la
distribuci´on del recurso solar promedio en forma de mapas solares o mapas
de irradiaci´on media. Esta presentaci´on visual hace la informaci´on m´as accesible al usuario, que puede aprovecharla en forma inmediata. El desarrollo
de mapas de radiaci´on solar ha sido llevado a cabo en Europa [PAW01],
EEUU [GM99, MGW99], M´ejico [AL75] y, posteriormente, en Argentina
[GS07, GG98b, GG98a] y Brasil [TFL+97, Tib04, CP98], entre otros pa´ıses.
En todos los casos, estos mapas son el resultado de una actividad incremental
que ha insumido d´ecadas de trabajo de varios equipos cient´ıﬁcos y a la cual
conﬂuyen aportes desde diferentes abordajes. Los m´argenes de error se reducen progresivamente, a medida que se cuenta con series de datos de radiaci´on
m´as largas y conﬁables y con modelos atmosf´ericos m´as detallados y precisos.
En los ´ultimos a˜nos se han comenzado a incorporar los datos de irradiaci´on
solar estimados a partir de modelos f´ısicos que describen la interacci´on entre
la radiaci´on incidente y el sistema tierra-atm´osfera integrando informaci´on
obtenida a partir de im´agenes satelitales. Esta metodolog´ıa permite estimar
con per´ıodos de horas, o incluso minutos, el grado de nubosidad sobre ´areas
de territorio con una resoluci´on espacial de unos pocos kil´ometros.

1

<!-- p. 6 -->

Cap´ıtulo 1. Introducci´on

Los sensores de radiaci´on solar de calidad son costos y requieren un mantenimiento adecuado durante los largos per´ıodos de tiempo (varios a˜nos)
necesarios para tener datos con signiﬁcancia estad´ıstica. Por esta raz´on, las
series de irradiaci´on de largo adecuado y buena calidad son escasas. A nivel mundial se estima que 1 de cada 500 estaciones de medida agrometereol´ogica incluyen mediciones de irradiaci´on solar y cuando lo hacen suele
ser con sensores de baja calidad y con poco mantenimiento. Sin embargo,
la mayor´ıa de las estaciones de medida toman registros diarios de Heliofan´ıa (horas radiaci´on solar en suelo que superan cierto umbral) utilizando
heli´ografos de Campbell-Stokes, un instrumento sumamente robusto que no
requiere de mayores cuidados, m´as all´a de mantenerlo limpio. Desde 1924
se conoce que existe una correlaci´on lineal, conocida como la ecuaci´on de
Angstrom-Prescott [Ang24, Pre40], entre la media de heliofan´ıa relativa y la
media de irradiaci´on normalizada. Una pr´actica usual [DB06] para estimar
la irradiaci´on global media sobre grandes extensiones territoriales a partir de
pocas medidas, consiste en especiﬁcar la correlaci´on para estaciones en las
cuales existen simult´aneamente medidas de heliofan´ıa y de radiaci´on solar
y luego extrapolarla a estaciones donde existen medidas de heliofan´ıa, pero
no de irradiaci´on solar. Este m´etodo ha sido usado extensamente en la regi´on [Tib04, RGGR04, GGR05, GG98b, GG98a] para estimar la distribuci´on
espacial y estacional de la irradiaci´on global media incidente.
En el Uruguay, las estaciones de la Direcci´on Nacional de Metereolog´ıa
(DNM) y las cinco del Instituto de Investigaciones Agropecuarias (INIA)
tienen largos registros diarios de heliofan´ıa, con una adecuada cobertura
geogr´aﬁca de nuestro territorio. Grossi Gallegos y su equipo han llevado a
cabo valiosos trabajos sobre estos datos de heliofan´ıa analizando su variabilidad espacial y temporal y veriﬁcando su consistencia desde un punto de vista
estad´ıstico [RGR06, RF06, GS07]. En cuanto a medidas de irradiaci´on, en
Uruguay existen hoy pocas series con signiﬁcaci´on estad´ıstica y las mismas
est´an muy concentradas espacialmente. Para este trabajo hemos considerado
cuatro series de irradiaci´on. Luego de un an´alisis de los datos, dos de estas
series fueron utilizadas. El mapa solar ha podido ser elaborado gracias a que
el territorio uruguayo es relativamente peque˜no y uniforme y a que hemos
podido contar con los datos de irradiaci´on de pa´ıses vecinos.
Las principales diﬁcultades que se encuentran al intentar acceder a informaci´on de calidad sobre la variaci´on espacial y estacional de los promedios
de irradiaci´on solar en el Uruguay se resumen en tres puntos:

Se dispone de pocos datos estad´ısticamente signiﬁcativos sobre irradia-
ci´on solar.

la calidad de los datos existentes es muy variable.

2

<!-- p. 7 -->

Cap´ıtulo 1. Introducci´on

existe un rezago en cuanto al modelado del recurso solar, en relaci´on a
otros pa´ıses del mundo e incluso de la regi´on.

Este trabajo es un primer paso en la direcci´on de revertir esta situaci´on.
El mismo se enmarca dentro de las actividades del Convenio “Evaluaci´on
del potencial solar t´ermico en Uruguay y an´alisis de la factibilidad de su
utilizaci´on” entre la Direcci´on Nacional de Energ´ıa y Tecnolog´ıa Nuclear
(DNETN) del Ministerio de Industria y Energ´ıa y la Facultad de Ingenier´ıa
de la UdelaR, cuyos responsables son los Profs. J. Cataldo y V. Nunes. En el
marco de este convenio, se esta montando una red automatizada de monitoreo
de irradiaci´on en al menos tres puntos del interior del pa´ıs. Adem´as, se esta
instalando un banco de pruebas para paneles solares t´ermicos en la Facultad
de Ingenier´ıa de la UdelaR.
Este documento tiene la siguiente estructura. En el Cap´ıtulo 1 se describe
la situaci´on mundial y especialmente, regional, en cuanto a la caracterizaci´on
del recurso solar. En el Cap´ıtulo 2 se realiza un relevamiento y se describe
el pre-tratamiento de los datos disponibles. En el Cap´ıtulo 3 se describe la
metodolog´ıa utilizada para elaborar el Mapa Solar del Uruguay, se presentan
los mapas mensuales, se realiza un an´alisis de incerteza y se comparan los
resultados obtenidos con datos de la regi´on y con los resultados de otros
modelos. En el Cap´ıtulo 4 se incluye un resumen conceptual de los resultados
y una breve descripci´on de la perspectiva a futuro.

3

<!-- p. 8 -->

Cap´ıtulo 2

Datos disponibles

Existen en Uruguay varias series de datos de irradiaci´on y de heliofan´ıa,
algunas de acceso p´ublico y otras de acceso restringido. Las series de irradiaci´on global diaria u horaria son escasas, tanto en cuanto a su distribuci´on
geogr´aﬁca como temporal. La calidad de los datos es variable y algunas de
ellas pueden estar afectadas por errores sistem´aticos. En cuanto a los datos
de heliofan´ıa1, la situaci´on es otra. En general, las estaciones de la Direcci´on
Nacional de Meteorolog´ıa del Uruguay (DNM), que tienen una adecuada cobertura geogr´aﬁca del territorio nacional, llevan registros de heliofan´ıa diaria
utilizando heli´ografos de Campbell-Stokes y tienen series digitalizadas que
abarcan largos per´ıodos de tiempo. Hasta donde sabemos la DNM no tiene
registros digitalizados de irradiancia diaria2. El Instituto de Investigaciones Agropecuarias (INIA) tambi´en registra heliofan´ıa en sus cinco estaciones
distribuidas en el territorio nacional y los datos se encuentran disponibles
p´ublicamente en su p´agina web.

2.1. Series de irradiaci´on

Para este trabajo se consideraron cuatro series de irradiaci´on registradas
en el Uruguay y ocho registradas en los pa´ıses vecinos. De este conjunto
de datos, se utilizaron cuatro series de irradiaci´on como base para el mapa
solar y cinco series de pa´ıses vecinos fueron reservadas para una validaci´on
posterior.

1Deﬁnida, de acuerdo a la Organizaci´on Meteorol´ogica Mundial (WMO), como el tiempo durante el cual la irradiancia esta sobre el umbral de 120 W/m2.
2Si bien hemos constatado (G.A.) que la DNM almacena una serie con registros de m´as
de 20 a˜nos de irradiancia diaria, en bandas de papel, para la localidad de Bella Uni´on.

4

<!-- p. 9 -->

2.1. Series de irradiaci´on Cap´ıtulo 2. Datos disponibles

2.1.1. Series Uruguayas

A continuaci´on se detallan las cuatro series de irradiaci´on consideradas
para el Uruguay, incluyendo la informaci´on disponible3 sobre los antecedentes
y metadatos asociados.

Serie ZUELA
Datos de irradiaci´on global diaria para el per´ıodo 1969-1979. Medida en
la estaci´on meteorol´ogica de “La Estanzuela” (Colonia) del Centro de
Investigaciones Agr´ıcolas Alberto Boerger (CIAAB) (actual INIA), de-
pendiente del Ministerio de Ganader´ıa, Agricultura y Pesca (MGAP).
Se utiliz´o un piran´ometro Kipp & Zonen, se registr´o sobre banda de
papel y se planimetr´o para obtener los registros de irradiaci´on dia-
ria. Este trabajo fue realizado por el Dr. Walter Corsi. Esta serie es
p´ublica y est´a disponible completa en la p´agina web de la Mesa Solar,
http://www.mesasolar.org.

Serie ARCHI
Esta serie de medidas de irradiaci´on Solar global diaria, fue obtenida
en la Facultad de Arquitectura de UdelaR (Montevideo) a partir de
una iniciativa de la Directora del Instituto de F´ısica de la Facultad de
Ingenier´ıa, Irene W. de Ewenson. Los datos diarios abarcan el per´ıodo
1980-1984 y se utiliz´o un piran´ometro Eppley Black and White con
registro sobre banda de papel. Esta serie incluye registros parciales
de radiaci´on directa medidos pon un Pirheli´ometro Eppley provisto
de un mecanismo de seguimiento autom´atico. El mantenimiento del
equipo estuvo a cargo del Instituto de la Construcci´on de Ediﬁcios de
la Facultad de Arquitectura (Arq. Rivero) y el procesamiento de los
datos (incluyendo la digitalizaci´on de los mismos) fue realizado en el
Instituto de F´ısica de la Facultad de Ingenier´ıa. Esta serie es p´ublica
y est´a disponible completa en la p´agina web del Instituto de F´ısica
de la Facultad de Ingenier´ıa http://www.ﬁng.edu.uy/solar, as´ı como
tambi´en en la de la Mesa Solar, http://www.mesasolar.org.

Series Melilla
Medidas de irradiaci´on global horaria obtenidas en el Despacho de Car-
gas de UTE en la localidad de Melilla, Montevideo. Se utiliz´o un sensor
fotovoltaico Davis con registro digital por data logger. La serie corres-
pondiente a los ´ultimos cuatro a˜nos (10/2005 -. 09/2009) es propiedad
de UTE y fue cedida a la Facultad de Ingenier´ıa para la realizaci´on de

3Utilizamos aqu´ı la nomenclatura y los metadatos aportados por el Ing. J. Duomarco
y disponibles en la p´agina de la Mesa Solar.

5

<!-- p. 10 -->

2.1. Series de irradiaci´on Cap´ıtulo 2. Datos disponibles

nombre localidad LAT LON per´ıodo a˜nos instrumento instituci´on
ZUELA Colonia -34.6 -58.3 10/1969 – 11/1977 8 Kipp & Zonnen1,3 INIA
ARCHI Montevideo -34.9 -56.2 01/1980 – 12/1984 5 Eppley Black& White1,3,4,5 UdelaR
MELILLA-α Montevideo -34.8 -56.3 10/2005 – 09/2009 4 Sensor fotovoltaico Davis2,4 UTE
POTRERILLO-α Rocha -34.0 -53.6 01/2007 – 07/2009 2.5 Fotodiodo ES2 2,4 Probides

Notas:
(1) registro original en banda de papel, luego digitalizada.
(2) registro electr´onico autom´atico.
(3) disponible p´ublicamente en http://mesasolar.org
(4) serie con registros horarios
(5) incluye medidas de componente directa

Cuadro 2.1: Series de irradiaci´on uruguayas analizadas para este trabajo.

este estudio. En este trabajo nos referiremos a estos datos como la serie
Melilla-α. Existe un per´ıodo corto de aproximadamente 18 meses (8/97
– 01/99) que es de libre acceso, al que nos referiremos como Melilla-β,
y que se encuentra disponible en la p´agina de la Mesa Solar.

Series Potrerillo
Esta serie de medidas de irradiaci´on global horaria fue obtenida en
la Estaci´on Biol´ogica de PROBIDES en el Potrerillo de Santa Teresa,
Rocha. All´ı funciona una estaci´on de registros meterol´ogicos autom´ati-
cos Delta-T devices, basada en un data logger DL2. El piran´ometro es
fotovoltaico, modelo ES2 de Delta-T devices. Se cuenta con registros
horarios de irradiaci´on solar, temperatura media del aire, precipitacio-
nes y humedad relativa ambiente. Estos datos son procesados por la
Unidad de Clima de la Facultad de Agronom´ıa, quienes los han ce-
dido para este estudio los datos correspondientes al per´ıodo 01/2007
– 07/2009. Nos referimos a esta serie como Potrerillo-α, para diferen-
ciarla de los registros anteriores de irradiaci´on global (01/96-06/97)
disponibles p´ublicamente en la p´agina de la Mesa Solar, a los que nos
referiremos como Potrerillo-β.

En la Tabla 2.1 se indican las cuatro series nacionales consideradas para
este estudio y se dan las ubicaciones (latitud y longitud, en grados sur y
oeste, respectivamente) y otras caracter´ısticas de los aparatos de medida.

2.1.2. Datos regionales de irradiaci´on

Se solicitaron datos de irradiaci´on diaria y heliofan´ıa al INMET (Instituto
Nacional de Meteorolog´ıa) de Basil, que opera cientos de estaciones de medida
autom´aticas y convencionales. Se recibieron datos de irradiaci´on diaria para

6

<!-- p. 11 -->

2.2. Series de Heliofan´ıa Cap´ıtulo 2. Datos disponibles

c´odigo localidad LAT LON ALT (m) per´ıodo a˜nos
A804 Livramento -30.8 -55.6 328 11/2001 – 09/2009 7.8
A836 Jaguar˜ao -32.6 -53.4 47 01/2007 – 09/2009 2.6
A827 Bag´e -31.3 -54.0 230 01/2007 – 09/2009 2.6
A899 Chu´ı -33.7 -53.4 26 03/2008 – 09/2009 1.5

Cuadro 2.2: Series de irradiaci´on diaria recibidas del INMET - Brasil. Los c´odigos
corresponden a la clasifaci´on del INMET.

c´odigo localidad LAT LON ALT a˜nos
MCa Monte Caseros -30.3 -57.7 54
CUr Concepci´on del Uruguay -32.5 -58.3 25
Gua Gualeguaych´u -33.0 -58.6 21
SGA Salto Grande (Arg.) -31.2 -57.9 37

Cuadro 2.3: Localidades Argentinas para las cuales se usaron datos de la Red
Solarim´etrica Argentina reportados en la Ref. [GGR05]. Las coordenadas est´an en
grados (sur y oeste), la altura en metros; no se dispone de informaci´on sobre el
per´ıodo. Los correspondientes valores medios de irradiaci´on ﬁguran en la Tabla
2.4.

cinco localidades Brasile˜nas cercanas al Uruguay. Los detalles se muestran
en el Cuadro 2.2.
Para contar con datos del litoral oeste se recurri´o a valores de irradiaci´on
media utilizados para el Atlas Solar Argentino por H. Grossi Gallegos y su
equipo [RGGR05, GG98b, GG98a] y que fueran publicados en la versi´on
electr´onica del mismo [GGR05]. En el Cuadro 2.3 se resumen los detalles de
las localidades Argentinas consideradas para este trabajo.
En suma, fueron consideradas cuatro series de irradiaci´on Uruguayas,
cuatro series Brasileras (INMET) y valores medios para cuatro localidades
Argentinas, usados para el Atlas Solar Argentino y basados en medidas de la
Red Solar´ım´etrica Argentina. Luego de un proceso de ﬁltrado y an´alisis de
consistencia, como se describe m´as adelante, algunas de las series regionales
series fueron reservadas para una validaci´on posterior del mapa y algunas de
las nacionales no fueron utilizadas para este trabajo.

2.2. Series de Heliofan´ıa

Los datos de heliofan´ıa diaria (horas de sol sobre el umbral de 120 w/m2)
son relevados hace d´ecadas en todas las estaciones de la Direcci´on Nacional de

7

<!-- p. 12 -->

2.2. Series de Heliofan´ıa Cap´ıtulo 2. Datos disponibles

c´odigo uso 1 2 3 4 5 6 7 8 9 10 11 12 anual
ZUELA B 6.8 6.0 5.1 3.8 2.7 2.2 2.3 3.3 4.5 5.7 7.0 7.0 4.7
Melilla-α B 6.1 5.4 4.3 3.4 2.4 1.9 2.0 2.7 3.5 5.1 6.4 6.5 4.1
A804 B 6.9 6.1 5.0 3.9 3.0 2.4 2.7 3.3 4.1 5.2 6.6 7.0 4.7
A836 V 6.8 6.2 4.9 4.0 2.7 2.1 2.4 2.9 3.7 4.8 7.1 7.1 4.6
A827 V 6.9 6.4 5.2 4.5 3.2 2.4 2.8 3.3 4.0 4.8 7.4 7.6 4.9
MCa V 6.9 6.1 5.2 4.1 3.1 2.5 2.7 3.3 4.2 5.6 6.5 7.0 4.8
CUr V 6.7 6.1 5.0 3.9 2.9 2.4 2.5 3.2 4.3 5.4 6.5 6.9 4.7
Gua V 6.6 5.9 4.5 3.7 2.6 2.0 2.2 2.9 3.7 5.0 6.2 6.3 4.3
SGA B 6.9 6.1 4.9 3.9 3.0 2.4 2.5 3.3 4.1 5.5 6.3 6.8 4.6

Cuadro 2.4: Irradiaci´on diaria promedio (en kWh/m2) de cada mes. Los c´odigos
indican la localidad, ver Cuadros 2.1, 2.2 y 2.3 con los metadatos. La ´ultima
columna muestra el promedio anual de irradiaci´on diaria. Los datos argentinos son
de la Ref. [GGR05]. Las cuatro series indicadas (B) fueron usadas como base para
el mapa. Los datos de las cinco estaciones indicadas (V) fueron reservadas para
validaci´on posterior.

Metereolog´ıa (DNM) y tambi´en en las cinco estaciones del Instituto Nacional
de Investigaciones Agropecuarias (INIA). De modo que para la heliofan´ıa, se
puede aﬁrmar que existe una buena cobertura geogr´aﬁca y temporal. Sin
embargo, en este caso, la diﬁcultad reside en la calidad de los datos. Por
ejemplo, para una localidad dada, hay muchas series de datos de diferentes
procedencias y los valores medios mensuales muestran que no siempre son
consistentes entre si.
Se consideraron para este trabajo datos de heliofan´ıa para el Uruguay
procedentes de 17 estaciones de la DNM y 5 estaciones del INIA que, en
conjunto, corresponden a 18 localidades en el territorio nacional. Los datos
provienen de cuatro fuentes, que denominaremos (DNM-1, DNM-2, DNM-3
e INIA), para los per´ıodos que se detallan en el Cuadro 2.5.
El conjunto DNM-1 contiene horas de sol acumuladas por mes, promediadas en el per´ıdo 1981-1990, para las 12 estaciones de la DNM indicadas
en el Cuadro 2.6. Estos datos se encuentran disponibles en l´ınea4.
El conjunto DNM-2 contiene horas de sol acumulades en el mes (no promediadas) para el per´ıodo 1986-2005 y fu´e recientemente analizado por H.
Grossi Gallegos5 y colaboradores [RGR06, RF06, GS07]. Trabajando sobre
este conjunto de datos, Grossi estudia la relaci´on entre su variabilidad espacial y la distancia entre pares de estaciones en [RGR06]. Conluye que, con

4 http://www.meteorologia.com.uy/
5Este conjunto fue solicitado a la DNM uruguaya por el Servicio Meteorol´ogico Nacional
argentino (SMN) a pedido de H. Grossi. En una etapa temprana de este trabajo, estos
datos nos fueron gentilmente cedidos por H. Grossi con la autorizaci´on previa del SMN
argentino.

8

<!-- p. 13 -->

2.2. Series de Heliofan´ıa Cap´ıtulo 2. Datos disponibles

Figura 2.1: Heliofan´ıa media mensual para tres localidades con datos son de los
conjuntos DNM-1,2,3 seg´un se indica.

9

<!-- p. 14 -->

2.2. Series de Heliofan´ıa Cap´ıtulo 2. Datos disponibles

c´odigo dato estaciones per´ıodo a˜nos
DNM-1 promedio de total mensual 12 1981–1990 9
DNM-2 total mensual sin promediar 11 1986–2005 20
DNM-3 valor diario promedio 14 2000–2008 9
INIA valor diario promedio 5 1971–2008 38

Cuadro 2.5: Conjuntos de datos de heliofan´ıa analizados para este trabajo. Hay
superposiciones entre las localidades, ver el Cuadro 2.6.

un nivel de conﬁanza del 90 %, es posible extrapolar los valores obtenidos
en las estaciones de medici´on de insolaci´on en Uruguay hasta distancias de
285 km sin exceder un error del 15 %. Teniendo en cuenta que la distancia
promedio entre las 11 estaciones consideradas en este estudio es de 290 km,
concluye que el pa´ıs tiene una cobertura adecuada, dada la homogeneidad
de su territorio. En un segundo estudio [RF06], de car´acter regional para la
Pampa H´umeda y que incluye datos de heliofan´ıa de Argentina, Uruguay,
Paraguay y del sur de Brasil, Grossi et al. llegan a conclusiones similares.
En un tercer estudio [GS07], buscando en las series de heliofan´ıa uruguayas
posibles variaciones temporales relacionadas con el Cambio Clim´atico, Grossi y colaboradores analizan en este conjunto de datos (DNM-2) la existencia
de tendencias en los promedios anuales. Trabajando con un intervalo de conﬁanza de 95 %, concluyen que ninguna de las estaciones uruguayas analizadas
muestra en sus series hist´oricas tendencias signiﬁcativas (al 5 %).
El conjunto DNM-3 es el mas reciente, contiene datos de heliofan´ıa diaria
promedio para el per´ıodo 2000-2008. Este conjunto fu´e comprado a la DNM
en octubre 2009 por la Facultad de Ingenier´ıa de UdelaR, para la realizaci´on
de este trabajo.
Finalmente, el conjunto INIA contiene datos de heliofan´ıa promedio mensual para las cinco estaciones del INIA indicadas en el Cuadro 2.7. Estos datos
se encuentran disponibles en l´ınea6.
Ya que se dispon´ıa de datos de diversas fuentes para la misma localidad,
se realiz´o un an´alisis de consistencia entre ellos, a nivel de medias mensuales. La Fig. 2.1 muestra esta comparaci´on para tres de las localidades donde
se contaba con datos de diversas fuentes y per´ıodos de tiempo. Los datos
presentan diferencias que llegan a ser de 1 hora, lo cual es sorprendente, ya
que se trata de valores medios para el mes sobre varios a˜nos de datos diarios
y que en deﬁnitiva, est´an basados en el mismo instrumento de medida ya
que son todos datos DNM. Esto puede tener diversas causas. Los per´ıodos
de tiempo para cada conjunto de datos son diferentes y los datos han sido

6http://www.inia.org.uy/

10

<!-- p. 15 -->

2.2. Series de Heliofan´ıa Cap´ıtulo 2. Datos disponibles

Estaci´on LAT LON ALT DNM-1 DNM-2 DNM-3 INIA
ARTIGAS -30,40 -56,51 121 x x x
CARRASCO -34,83 -56,01 33 x x x
COLONIA -34,46 -57,84 23 x x x x
DURAZNO -33,35 -56,50 93 x
FLORIDA -34,09 -56,19 67 x
LAS BRUJAS (INIA) -34,67 -56,33 32 x
MELO -32,37 -54,19 100 x x x
MERCEDES -33,25 -58,07 17 x x x
PASO DE LOS TOROS -32,80 -56,53 76 x x
PAYSANDU -32,35 -58,04 61 x x x
PRADO -34,86 -56,21 16 x
RIVERA -30,90 -55,54 242 x x x
ROCHA -34,49 -54,31 18 x x x
SALTO -31,40 -57,97 34 x x x x
SAN JOS´E -34.35 -56.76 72 x
TACUAREMB´O -31.71 -55.99 134 x x
TREINTA Y TRES -33,22 -54,39 47 x x x x
YOUNG -32,69 -56,65 81 x

Cuadro 2.6: Localidades donde se cuenta con datos de heliofan´ıa media diaria. Se
indican las coordenadas en grados y la altura sobre el nivel del mar, en metros.
Salvo para Las Brujas, la ubicaci´on de las estaciones corresponde a las de la DNM.
La ubicaci´on de las estaciones del INIA se muestra en el cuadro 2.7.

procesados de formas diferentes. En deﬁnitiva, se ha optado por trabajar
exclusivamente con datos del conjunto DNM-3, complementados en por datos de dos estaciones del INIA (Salto y La estanzuela), por la cercan´ıa del
heli´ografo con el piran´ometro que registr´o la irradiaci´on. Se consider´o importante utilizar datos de heliofan´ıa correspondientes a un per´ıodo de tiempo
deﬁnido (2000-2008), se opt´o por trabajar exclusivamente sobre los datos del
conjunto DNM-3. En el Cuadro 2.8 se indican los valores medios mensuales
utilizados, para cada localidad. La Fig. 2.2 muestra las ubicaciones de las
series de datos utilizadas para este trabajo.

Estaci´on Departamento LAT LON ALT Inicio
La Estanzuela Colonia -34.33 -57.68 81 1965
Las Brujas Canelones -34.67 -56.33 32 1970
Salto Grande Salto -31.27 -57.88 50 1970
Treinta y Tres Treinta y Tres -33.23 -54.25 100 1970
Tacuaremb´o Tacuaremb´o -31.70 -55.82 140 1970

Cuadro 2.7: Detalles de las cinco estaciones del INIA. La ubicaci´on esta en grados,
la altura en metros. Se indica el a˜no de inicio de los registros de heliofan´ıa.

11

<!-- p. 16 -->

2.2. Series de Heliofan´ıa Cap´ıtulo 2. Datos disponibles

Localidad Fuente USO 1 2 3 4 5 6 7 8 9 10 11 12
Colonia INIA AP 9.1 8.6 8.0 7.4 5.6 4.8 5.1 6.1 7.2 8.1 9.6 9.6
Salto INIA AP 9.4 8.5 7.9 6.4 6.0 4.7 5.5 6.3 6.8 7.6 8.9 9.2
Salto DNM-3 ER 9.6 8.5 7.5 6.3 5.6 4.1 5.7 6.4 6.8 6.8 9.1 9.4
Paysand´u DNM-3 ER 9.6 8.5 7.2 6.6 5.8 4.9 6.0 6.4 7.0 7.4 9.0 9.6
Carrasco DNM-3 AP,ER 9.6 8.6 7.0 6.4 5.3 4.4 5.0 5.3 6.0 7.0 8.8 9.1
San Jos´e DNM-3 ER 9.7 8.2 6.8 5.8 5.0 4.2 4.5 4.9 6.0 7.0 9.0 9.5
Florida DNM-3 ER 9.5 8.4 6.8 6.1 5.1 4.3 4.5 5.2 6.0 7.3 9.0 9.2
Durazno DNM-3 ER 9.8 8.6 7.3 6.3 5.2 4.5 5.4 5.8 6.7 7.2 9.1 9.7
Rocha DNM-3 ER 8.8 7.9 6.7 6.4 5.0 4.3 4.7 5.3 5.7 6.5 8.4 8.2
Treinta y Tres DNM-3 ER 9.2 8.0 6.6 6.1 5.0 4.3 4.9 5.3 5.7 6.9 8.6 8.9
Melo DNM-3 ER 9.4 8.2 7.0 6.3 5.4 4.4 5.3 5.9 6.0 6.6 8.8 9.2
Rivera DNM-3 AP,ER 9.1 8.1 7.0 5.8 5.3 4.0 5.5 6.1 6.3 6.7 8.3 8.7
Tacuarembo DNM-3 ER 9.4 8.4 6.8 6.2 5.3 4.1 5.6 5.8 6.3 6.8 8.8 9.1
Artigas DNM-3 ER 9.4 8.5 7.2 6.1 5.6 4.1 5.6 6.6 6.3 6.9 8.9 9.1

Cuadro 2.8: Datos de heliofan´ıa diaria promedio utilizados en este trabajo. Las
columnas numeradas indican el mes. En la columna USO, AP signiﬁca que fueron
usados para determinar los coeﬁcientes a y b de la correlaci´on de Armstrong-
Prescott y ER signiﬁca que fueron usados como estimadores de irradiaci´on en la
Ec. (3.2).

Figura 2.2: Ubicaci´on de las series de datos usadas para este trabajo. En rojo se
indican locales con datos de irradiaci´on diaria promedio, en azul los locales con
datos de heliofan´ıa (DNM) y en verde, los locales con datos de irradiaci´on diaria
promedio que fueron usados para validaci´on a-posteriori.

12

<!-- p. 17 -->

2.3. Pre-tratamiento de los datos Cap´ıtulo 2. Datos disponibles

2.3. Pre-tratamiento de los datos

Los conjuntos de datos elegidos, se han sometido a un pre–tratamiento
que implica por ejemplo su ﬁltrado para detectar outliers y su normalizaci´on.
Una parte importante de la dependencia estacional de los datos es trivial
y puede eliminarse normalizando adecuadamente. A continuaci´on deﬁnimos
los ´angulos relevantes y damos las expresiones utilizadas para normalizar los
valores medios mensuales de heliofan´ıa e irradiaci´on. Utilizaremos para este
breve resumen la notaci´on de [DB06], referencia que puede ser consultada
por detalles adicionales.

2.3.1. Geometr´ıa Solar

La normal al plano orbital de la tierra deﬁne una direcci´on especial, con
respecto a la cual el eje de rotaci´on de la tierra (el eje N–S o eje polar)
forma un ´angulo de aproximadamente 23,5o. Este ´angulo puede considerarse
constante en la escala de tiempo de inter´es para este trabajo. La posici´on
del eje polar relativa al Sol es responsable de los cambios estacionales en la
irradiancia solar incidente en cada hemisferio terrestre.
El ´angulo que forman el plano ecuatorial del la Tierra y la l´ınea TierraSol7 cambia diariamente a medida que la tierra recorre su ´orbita, como se
muestra en la Fig. 2.3. Este ´angulo se denomina declinaci´on solar, δ, es nulo
en los equinoccios (primavera y oto˜no) y es de aproximadamente ±23,5o en
los solsticios (verano e invierno). La declinaci´on solar en grados esta dada,
aproximadamente, por la expresi´on

284 + n
δn = 23,45o sin 360 (2.1)
365

donde n = 1, 2 . . . 365 es d´ıa en el ciclo anual. Esta expresi´on es adecuada
para los prop´ositos de ´este trabajo, pero existen expresiones m´as precisas,
v´ease por ejemplo [DB06].
Para describir el movimiento aparente del sol, se usan dos ´angulos: el
´angulo zenital, θz, es el ´angulo que forma la l´ınea Tierra-Sol con la vertical
en el punto del observador y el ´angulo horario, ω, que indica el desplazamiento angular del sol de este a oeste, debido a la rotaci´on de la Tierra. El
´angulo horario es nulo en el mediod´ıa solar, aumenta en 15o por hora y por
convenci´on se toma negativo en la ma˜nana. Estos ´angulos se relacionan con
la latitud del observador, φ, y con la declinaci´on a trav´es de la expresi´on,

cos θz = cos φ cos δn cos ω + sin φ sin δn. (2.2)

13

<!-- p. 18 -->

2.3. Pre-tratamiento de los datos Cap´ıtulo 2. Datos disponibles

Figura 2.3: Esfera celeste mostrando el movimiento aparente del Sol visto desde la
Tierra. La l´ınea Tierra-Sol forma un ´angulo δ ∈[−23,45o, 23,45o] (la declinaci´on)
con el plano de la ecl´ıptica. Referido al Hemisferio Sur, δ = 23, 45o en el solsticio
de invierno y δ = −23, 45o en el solsticio de verano. En los equinoccios, la l´ınea
Tierra-Sol esta en el plano de la ecl´ıptica y δ = 0.

A la salida o puesta del sol, se tiene θz = ±90o y cos θz = 0, por lo que el
´angulo horario a la salida o puesta del sol, ωs, cumple

cos ωs = −tan φ tan δn. (2.3)

Dado que el ´angulo ω aumenta en 15o por hora, el n´umero m´aximo de horas
de sol en un d´ıa y lugar dados es

2ωs 2
N0(φ, n) = = arc cos (−tan φ tan δn) (2.4)
15 15

donde el arcoseno debe expresarse en grados.
Si llamamos Ωm al subconjunto de valores de n correspondientes al mes
m (m = 1, 2, . . . 12), el n´umero medio de horas de sol en el mes, ¯N0, esta
dado por
1
¯N0(φ, m) = X N0(n, φ) (2.5)
\|Ωm|
n∈Ωm

donde |Ωm| es el n´umero de d´ıas en el mes m.

7Es decir, la l´ınea que une los centros del Sol y de la Tierra

14

<!-- p. 19 -->

2.3. Pre-tratamiento de los datos Cap´ıtulo 2. Datos disponibles

2.3.2. Irradiancia solar extra-atmosf´erica

La irradiancia solar incidente en el d´ıa solar n en un plano horizontal
fuera de la atm´osfera esta dada por [DB06],

G0 = GscFn cos θz (2.6)

donde Gsc = 1367 W/m2 es la Constante Solar, el primer factor

360 n
Fn ≡ 1 + 0,033 cos (2.7)
365

es una correcci´on que tiene en cuenta la variaci´on de la distancia TierraSol debido a la eccentricidad de la ´orbita terrestre y el factor direccional
cos θz, dado por la Ec. (2.2), resulta del producto escalar entre la direcci´on
de incidencia y la normal a la superﬁcie terrestre en el punto de incidencia.
G0 representa el ﬂujo de energ´ıa solar incidente fuera de la atm´osfera para
una ubicaci´on dada en un instante dado. La dependencia en posici´on se da
a trav´es de la latitud, (φ), la dependencia temporal a trav´es del d´ıa solar n
y del ´angulo horario ω.
La irradiaci´on diaria incidente fuera de la atm´osfera en un d´ıa y latitud
determinadas, H0, se obtiene por integraci´on de la Ec. (2.6), en kJ/m2 se
expresa como

Z t2
H0(n, φ) = G0(ω(t), φ, n) dt
−t1
dt Z ωs
\= G0(ω, φ, n) dω (2.8)
dω −ωs
\= K0Fn (cos φ cos δn sin ωs + ωs sin φ sin δn)

donde ωs en radianes, esta dado por la Ec. (2.3) y, dado que dω/dt = π/12
rad/hora, resulta
K0 ≡24 × 1h × Gsc ≈37,6 MJ/m2 = 10, 4 kWh/m2. (2.9)
π

Esta es la m´axima energ´ıa incidente en un d´ıa sobre la atm´osfera. Debido a
los efectos de la absorci´on y reﬂexi´on en la atm´osfera, al suelo llegar´a una
fracci´on de esta cantidad.
Finalmente, el valor medio de la irradiancia diaria, ¯H0, para un mes m se
obtiene a partir de

1
¯H0(φ, m) = X H0(φ, n) (2.10)
\|Ωm|
n∈Ωm

15

<!-- p. 20 -->

2.3. Pre-tratamiento de los datos Cap´ıtulo 2. Datos disponibles

Figura 2.4: Promedios diarios de heliofan´ıa para la ciudad de Artigas. Los promedios correspondientes al per´ıodo 2000-2008 (conjunto DNM3). La curva continua
muestra el m´aximo n´umero de horas de sol para esta estaci´on, N0, dado por la
Ec. (2.4).

donde |Ωm| es el n´umero de d´ıas en el mes m. Las horas de sol promedio, ¯N0, y
la irradiancia diaria promedio, ¯H0, para cada mes son las cantidades de inter´es
para normalizar los datos de heliofan´ıa e irradiaci´on diaria, respectivamente.

2.3.3. Normalizaci´on

La normalizaci´on de la heliofan´ıa diaria se lleva a cabo dividiendo entre
el n´umero m´aximo de horas de sol para la localidad y d´ıa del a˜no de que se
trate, dado por la Ec. (2.4). Deﬁnimos la heliofan´ıa relativa diaria, n, como

n(φ, i) ≡N(φ, i) (2.11) N0(φ, i).

En el caso de la heliofan´ıa media mensual, usamos el valor medio de N0 en el
mes, dado por la Eq. (2.5), para normalizar. Deﬁnimos entonces la heliofan´ıa
relativa media para el mes m como,

¯N(φ, m)
n(φ, m) ≡ ¯N0(φ, m). (2.12)

En el Cuadro 2.9 se indican los valores de heliofan´ıa relativa media correspondientes al conjunto de datos DNM-3 utilizado para este trabajo.

16

<!-- p. 21 -->

2.3. Pre-tratamiento de los datos Cap´ıtulo 2. Datos disponibles

Figura 2.5: Heliofan´ıa relativa promedio, calculada dividiendo los valores medios
diarios mostrados en la Fig. 2.4 entre el valor de N0 calculado a partir de la
Ec. (2.4).

Localidad 1 2 3 4 5 6 7 8 9 10 11 12
Colonia∗ 0.65 0.65 0.66 0.66 0.55 0.50 0.51 0.57 0.61 0.63 0.70 0.67
Salto∗ 0.68 0.65 0.65 0.57 0.58 0.47 0.54 0.58 0.58 0.59 0.65 0.66

Salto 0.69 0.65 0.61 0.57 0.54 0.41 0.56 0.58 0.57 0.53 0.67 0.67
Paysand´u 0.70 0.64 0.59 0.59 0.56 0.49 0.59 0.59 0.59 0.58 0.66 0.68
Carrasco 0.68 0.64 0.57 0.58 0.52 0.45 0.51 0.49 0.51 0.54 0.63 0.64
San Jos´e 0.70 0.62 0.56 0.52 0.49 0.43 0.45 0.46 0.50 0.55 0.65 0.67
Florida 0.68 0.63 0.56 0.55 0.50 0.44 0.45 0.48 0.51 0.56 0.65 0.65
Durazno 0.70 0.65 0.59 0.57 0.51 0.46 0.53 0.53 0.57 0.56 0.66 0.68
Rocha 0.63 0.60 0.55 0.57 0.49 0.44 0.47 0.49 0.49 0.51 0.61 0.57
Treinta y Tres 0.66 0.61 0.54 0.55 0.49 0.44 0.48 0.49 0.48 0.53 0.62 0.63
Melo 0.68 0.62 0.58 0.56 0.52 0.45 0.52 0.55 0.51 0.51 0.64 0.65
Rivera 0.66 0.62 0.57 0.52 0.51 0.40 0.54 0.56 0.53 0.52 0.61 0.62
Tacuarembo 0.68 0.64 0.56 0.55 0.51 0.41 0.55 0.53 0.53 0.53 0.64 0.65
Artigas 0.68 0.65 0.59 0.55 0.53 0.41 0.55 0.60 0.53 0.54 0.65 0.65

Cuadro 2.9: Datos de heliofan´ıa normalizada diaria media utilizados en este trabajo. Las columnas numeradas indican el mes. Los valores, calculados con la
Ec. (2.12), corresponden a los datos del conjunto DNM-3 (Cuadro 2.8) excepto
los marcados (∗) que correspondientes a estaciones INIA.

17

<!-- p. 22 -->

2.3. Pre-tratamiento de los datos Cap´ıtulo 2. Datos disponibles

Figura 2.6: Datos de irradiaci´on diaria, H, para el a˜no 1971 de la serie ZUELA
(la Estanzuela, Colonia) comparados con 0,8 H0, el 80 % de la irradiaci´on diaria
extraterrestre.

La irradiaci´on diaria se normaliza adecuadamente usando la irradiaci´on
diaria incidente fuera de la atm´osfera, dada por la Ec. (2.8). Esto deﬁne el
´ındice de claridad diario, KT,

KT(φ, n) ≡H(φ, n) (2.13) H0(φ, n).

Es un hecho emp´ıricamente establecido que KT \< 0,8, ya que al menos el
20 % de la irradiaci´on es absorbido o reﬂejado por la atm´osfera en un d´ıa
claro. Esto puede ser usado como un ﬁltro ﬁltro simple, ya que datos que
resultan en KT > 0,80 suelen corresponder a un instrumento mal calibrado
o mal ubicado (que recibe irradiaci´on reﬂejada por superﬁcies cercanas). A
modo de ejemplo, en la Fig. 2.6 se muestran los datos de irradiaci´on diaria
H para el a˜no 1971 de la serie ZUELA (la Estanzuela, Colonia) comparados
con el 80 % de la irradiaci´on diaria extraterrestre, H0. La Figura 2.7 muestra
el ´ındice de claridad diario para estos datos. Una comparaci´on entre ambas
ﬁguras muestra como esta normalizaci´on elimina parte de la dependencia
estacional de los datos.
Para trabajar a nivel mensual, se puede calcular el valor medio de la irradiaci´on diaria del mes, ¯H, y normalizarlo usando el correspondiente promedio
extraterrestre, ¯H0, dado por la Ec. (2.10). Esto deﬁne un ´ındice de claridad

18

<!-- p. 23 -->

2.3. Pre-tratamiento de los datos Cap´ıtulo 2. Datos disponibles

Figura 2.7: Indice de claridad diario, KT , deﬁnido en la Ec. (2.13), para los datos
de irradiaci´on diaria del a˜no 1971 de la serie ZUELA (la Estanzuela, Colonia)
mostrados en la Fig. 2.6.

19

<!-- p. 24 -->

2.3. Pre-tratamiento de los datos Cap´ıtulo 2. Datos disponibles

Serie irradiaci´on 1 2 3 4 5 6 7 8 9 10 11 12
ZUELA 0.57 0.55 0.56 0.55 0.50 0.48 0.48 0.53 0.54 0.56 0.60 0.57
Salto Grande 0.58 0.56 0.52 0.53 0.52 0.48 0.47 0.50 0.48 0.53 0.54 0.56
Livramento 0.58 0.56 0.53 0.52 0.52 0.47 0.51 0.49 0.48 0.50 0.56 0.57
Melilla-α 0.51 0.50 0.47 0.49 0.45 0.44 0.43 0.45 0.44 0.51 0.55 0.53

Cuadro 2.10: Datos de irradiaci´on normalizada (´ındice de claridad) diaria promedio
utilizados en este trabajo. Las columnas numeradas indican el mes.

mensual
¯H(φ, m)
kT(φ, m) ≡ ¯H0(φ, m). (2.14)
En el Cuadro 2.10 damos los valores del ´ındice de claridad mensual correspondientes a las cuatro series de irradiaci´on usadas para este trabajo.

2.3.4. Filtrado de datos

Un primer ﬁltrado surge de las condiciones de normalizaci´on. Por deﬁnici´on, la heliofan´ıa relativa diaria debe estar entre 0 y 1. Por otra parte, ya
se mencion´o que el ´ındice de claridad debe ser inferior a 0, 8. Pr´acticamente
todos los datos utilizados cumpl´ıan estos criterios, realizando el descarte de
muy pocos puntos.
Tanto los datos de irradiaci´on como los de heliofan´ıa fueron analizados
adem´as por el m´etodo de outliers a 2,5σ, bajo la hip´otesis de una distribuci´on
normal. A partir de un conjunto de N datos Xi, con i = 1 . . . N, se calcula el
valor medio ¯X y la desviaci´on est´andar σX. Luego se marcan aquellos datos
que se apartan de la media mas de rσ, es decir se descartan aquellos Xj para
los cuales
\|Xj −¯X|
\> z (2.15)
σX
donde z es un par´ametro. Si los datos est´an normalmente distribuidos, entonces ﬁjando z se conoce la probabilidad Pout(z) de que se cumpla la condici´on
(2.15). Por ejemplo, Pout(z = 1) = 0,317 y Pout(z = 2, 5) = 0,0124. Si la fracci´on de datos marcados es consistente con esta probabilidad, el conjunto se
considera aceptable. Si es muy superior, los datos pueden no estar distribuidos normalmente. Hemos usado z = 2, 5, valor para el cual una distribuci´on
normal predice que en media 1, 24 % de los datos satisfacen la condici´on
(2.15). Los niveles de datos marcados han sido consistentes con la hip´otesis
de distribuci´on normal, observ´andose en la mayor´ıa de los casos ∼1 % de
outliers y en el peor caso, un 3 % de outliers.

20

<!-- p. 25 -->

2.3. Pre-tratamiento de los datos Cap´ıtulo 2. Datos disponibles

Figura 2.8: M´aximo m´ovil (ventana de 10 d´ıas) del ´ındice de claridad diario, KT de
las series de ZUELA (Colonia) y ARCHI (Montevideo) vs. fecha. La serie ARCHI
no fu´e utilizada en este trabajo.

Es bien conocido que la presencia de unos pocos outliers esp´ureos (debidos a errores espor´adicos de lectura, transcripci´on, suciedad en los sensores,
etc), puede afectar fuertemente el valor de los par´ametros de una regresi´on
lineal. Existen m´etodos estad´ısticos, como el m´etodo de Grubbs [HA04], para identiﬁcar y descartar medidas que no se ajustan a la hip´otesis de una
distribuci´on normal, trabajando a determinado nivel de conﬁanza. En nuestro caso, dado que la proporci´on de outliers observada es consistente con la
hip´otesis de distribuci´on normal, se ha considerado innecesario adoptar estos
m´etodos. Alternativamente, hemos calculado las regresiones de dos formas:
(i) usando estad´ıstica robusta a la presencia de outliers
(ii) usando la regresi´on lineal usual sobre conjuntos datos de los cuales los
outliers fueron depurados.
Al obtener consistencia entre ambos m´etodos de regresi´on, estamos seguros
de que la presencia de outliers no afecta signiﬁcativamente la determinaci´on
de estos coeﬁcientes.
Finalmente, se ha realizado un chequeo de consistencia sobre los conjuntos
de datos. En el caso de los datos de heliofan´ıa, los datos son en general
consistentes entre si y se ha optado por usar datos del conjunto DNM3,
asociados a un mismo per´ıodo temporal, como estimadores de radiaci´on.
Para el caso de las cuatro series de radiaci´on Uruguayas, hemos estudiado

21

<!-- p. 26 -->

2.3. Pre-tratamiento de los datos Cap´ıtulo 2. Datos disponibles

Figura 2.9: M´aximo m´ovil (ventana de 10 d´ıas) del ´ındice de claridad diario, KT
de las series de Melilla y Potrerillo (Rocha) vs. fecha. La serie Potrerillo no fu´e utilizada en este trabajo.

la consistencia entre si de los valores normalizados (KT, ´ındice de claridad
diario). La Fig. 2.8 muestra una comparaci´on de los valores m´aximos de KT
(en una ventana de 10 d´ıas) para las series m´as antiguas, ZUELA (Colonia) y
ARCHI (Montevideo). Los valores m´aximos de la serie ZUELA permanecen
estables en el tiempo, en tanto que los m´aximos de la serie ARCHI muestran
una tendencia decreciente en el tiempo, posiblemente debida a la degradaci´on
de la calibraci´on del piran´ometro. Se opt´o por no utilizar la serie ARCHI para
este trabajo. La Figura 2.9 muestra la misma comparaci´on para las series m´as
recientes, MELILLA−alpha y POTRERILLO (Rocha), en el tiempo en que
son simult´aneas. Los valores de KT para la serie Potrerillo son anormalmente
bajos, y la subida abrupta al ﬁnal de la serie es inexplicable, a no ser que
responda a un cambio o recalibraci´on del sensor. Esta serie tampoco fue
utilizada para este trabajo.

22

<!-- p. 27 -->

Cap´ıtulo 3

Mapa Solar del Uruguay

3.1. Metodolog´ıa

La metodolog´ıa utilizada en este trabajo se basa en la correlaci´on lineal
existente entre los promedios mensuales de irradiaci´on diaria normalizada y
los promedios mensuales de heliofan´ıa normalizada

kT = a + b n, (3.1)

donde el indice medio de claridad, kT, y la heliofan´ıa relativa media, n, se
deﬁnen en las Ecs. (2.12) y (2.14). Esta relaci´on fue propuesta originalmente
por Angstr¨om [Ang24] y luego modiﬁcada por Prescott [Pre40]. Dada la
relativa abundancia de datos de heliofan´ıa, la misma ha sido utilizada para
estimar la variaci´on espacial del recurso solar en la regi´on [RGGR05, Tib04].
Una vez conocidos los coeﬁcientes a y b para aquellos lugares en los que
se cuenta simult´aneamente con datos de irradiaci´on y heliofan´ıa, se utilizan
m´etodos est´andar de interpolaci´on para estimar la variaci´on espacial de los
coeﬁcientes en el territorio nacional. A partir de esta informaci´on, se estiman
los valores de los coeﬁcientes, a(x, y) y b(x, y) para aquellas localidades (x, y)
en las cuales se dispone de datos de heliofan´ıa. Utilizando los coeﬁcientes
espec´ıﬁcos para cada localidad, se utiliza nuevamente la Ec. (3.1), ahora
como estimador de la irradiaci´on media,

¯N(x, y)
¯H(x, y) = ¯H0(x, y) a(x, y) + b(x, y) . (3.2)
¯N0(x, y)

para la localidad con coordenadas (longitud y latitud) (x, y).
Esta metodolog´ıa tiene en cuenta la variaci´on espacial de los coeﬁcientes
a y b, pero descarta su variabilidad estacional, asumiendo que la misma
es una correcci´on menor. Se podr´ıa incluir la dependencia temporal de los

23

<!-- p. 28 -->

3.1. Metodolog´ıa Cap´ıtulo 3. Mapa Solar del Uruguay

Figura 3.1: Regresiones lineales para determinar los par´ametros a y b de la Ec. (3.1)
para cuatro ubicaciones en el territorio nacional.

24

<!-- p. 29 -->

3.1. Metodolog´ıa Cap´ıtulo 3. Mapa Solar del Uruguay

serie irradiaci´on serie heliofan´ıa a b R2
ZUELA Estanzuela (INIA) 0.21 0.55 0.92
Melilla Carrasco (DNM-3) 0.22 0.47 0.70
Livramento Rivera (DNM-3) 0.28 0.45 0.72
Salto Grande Salto (INIA) 0.23 0.49 0.72

Cuadro 3.1: Series de datos utilizadas, valores de a y b obtenidos y se da el coeﬁciente de regresi´on, R2, como indicativo del grado de correlaci´on.

coeﬁcientes reagrupando los datos y realizando ajustes de par´ametros para
cada estaci´on, por ejemplo. Esto podr´ıa ser adecuado en caso de contar con
series de datos m´as largas y de calidad controlada1.
Utilizando cuatro series de irradiaci´on y cuatro de heliofan´ıa, se estimaron
cuatro pares de coeﬁcientes a, b para el territorio nacional mediante regresi´on
lineal. Los valores del ´ındice de claridad y la heliofan´ıa relativa utilizados se
indican en los Cuadros 2.10 y 2.9, respectivamente. El ajuste se muestra en
la Fig. (3.2) y los resultados se resumen en el Cuadro 3.1. Estos valores de a
y b se extrapolan a todo el territorio nacional, utilizando para ello software
estad´ıstico de uso libre2. La Fig. /refﬁg:ayb muestra la variaci´on espacial
de los coeﬁcientes a y b para el territorio uruguayo. La pendiente (b) var´ıa
entre 0,40 y 0,56, con una tendencia creciente hacia el oeste del territorio. El
par´ametro a var´ıa entre 0,21 a 0,26 con tendencia creciente hacia el noreste
del territorio. Estos valores y tendencias son consistentes con las estimaciones,
de base mensual, realizadas para el territorio argentino [RGGR04, RGGR05].
A partir de esta informaci´on se determinaron los valores de (a, b) para las
doce localidades con datos de heliofan´ıa, tal como se indica en el Cuadro 3.2.
Finalmente, utilizando los datos de heliofan´ıa media diaria (Cuadro 2.8) y
los valores de a y b locales (Cuadro 3.2), se estima la irradiaci´on global
media diaria para cada sitio, ¯H(x, y), utilizando la Ec. (3.2). Estos valores
de irradiaci´on diaria media estimada se indican en el Cuadro 3.3.

1Entendemos que el largo de las series y el nivel de incerteza asociado no justiﬁcan
seguir este procedimiento con los datos actuales.
2M´as espec´ıﬁcamente, se uso el software libre GMT (Generic Mapping Tools) y el
paquete de estad´ıstica R, bajo una plataforma Linux est´andar.

25

<!-- p. 30 -->

3.1. Metodolog´ıa Cap´ıtulo 3. Mapa Solar del Uruguay

Figura 3.2: Isolineas que representan la variaci´on espacial de los par´ametros a
(rojo) y b (azul) de la Ec. (3.1).

26

<!-- p. 31 -->

3.1. Metodolog´ıa Cap´ıtulo 3. Mapa Solar del Uruguay

localidad LAT LON a b
Salto -31.43 -57.98 0.23 0.50
Paysand´u -32.35 -58.04 0.22 0.52
Carrasco -34.83 -56.01 0.22 0.46
San Jos´e -34.35 -56.76 0.22 0.50
Florida -34.09 -56.19 0.23 0.47
Durazno -33.35 -56.50 0.23 0.48
Rocha -34.49 -54.31 0.25 0.39
Treinta y Tres -33.22 -54.39 0.26 0.41
Melo -32.37 -54.19 0.28 0.41
Rivera -30.90 -55.54 0.28 0.45
Tacuaremb´o -31.71 -55.99 0.26 0.46
Artigas -30.40 -56.51 0.26 0.46

Cuadro 3.2: Valores de a y b para las localidades con datos de heliofan´ıa.

localidad 1 2 3 4 5 6 7 8 9 10 11 12 media
Salto 6.9 6.1 5.0 3.8 2.9 2.2 2.7 3.5 4.4 5.1 6.6 6.9 4.5
Paysand´u 7.0 6.1 4.9 3.8 2.9 2.3 2.7 3.4 4.4 5.4 6.6 7.0 4.7
Carrasco 6.4 5.6 4.4 3.3 2.4 1.9 2.2 2.7 3.7 4.8 6.0 6.3 4.1
San Jos´e 6.8 5.7 4.5 3.3 2.5 2.0 2.2 2.8 3.9 5.0 6.4 6.8 4.3
Florida 6.6 5.7 4.5 3.4 2.5 2.0 2.2 2.9 3.9 5.1 6.3 6.6 4.3
Durazno 6.8 5.9 4.7 3.6 2.6 2.1 2.4 3.1 4.2 5.1 6.4 6.8 4.5
Rocha 5.9 5.2 4.2 3.3 2.3 1.9 2.1 2.7 3.6 4.6 5.7 5.8 3.9
Treinta y Tres 6.4 5.6 4.4 3.5 2.5 2.1 2.3 2.9 3.8 4.9 6.0 6.4 4.2
Melo 6.7 5.8 4.8 3.7 2.8 2.2 2.5 3.3 4.1 5.1 6.3 6.7 4.5
Rivera 6.9 6.1 5.0 3.8 3.0 2.3 2.8 3.6 4.5 5.4 6.5 6.8 4.7
Tacuaremb´o 6.9 6.1 4.8 3.8 2.8 2.2 2.7 3.3 4.3 5.2 6.5 6.8 4.6
Artigas 6.9 6.1 5.0 3.8 3.0 2.3 2.8 3.6 4.4 5.3 6.5 6.8 4.7
promedios 6.7 5.8 4.7 3.6 2.7 2.1 2.5 3.2 4.1 5.1 6.3 6.6 4.4

Cuadro 3.3: Estimadores de irradiaci´on global media diaria (en kWh/m2) calculados utilizando la Ec. (3.2) con los coeﬁcientes (a, b) del Cuadro 3.2. Las columnas
numeradas indican los meses del a˜no.

27

<!-- p. 32 -->

3.2. Mapas mensuales Cap´ıtulo 3. Mapa Solar del Uruguay

3.2. Mapas mensuales

A partir de los estimativos de irradiaci´on obtenidos para 12 localidades
distribuidas en el territorio nacional (Cuadro 3.3), se utilizan utilizan t´ecnicas
de interpolaci´on para estimar la variaci´on de la irradiaci´on media en una
grilla de 20 × 20 km2 sobre todo el territorio nacional. Se generan isol´ıneas
de irradiaci´on media y se representa la informaci´on utilizando un c´odigo
de colores adecuado. El resultado de este proceso es la serie de 12 mapas
mensuales de irradiaci´on media diaria para el Uruguay, que se presenta a
continuaci´on. Tambi´en se incluye un mapa correspondiente a la distribuci´on
espacial de la irradianci´on media anual.
A partir de los valores que ﬁguran en el Cuadro 3.3 es posible concluir
que el valor t´ıpico de la irradiaci´on global diaria (el promedio anual sobre el
territorio uruguayo) es de 4,4 kWh/m2. La variaci´on estacional es grande, con
valores m´ınimos en torno a 2 kWh/m2 en el mes de Junio y valores m´aximos
que llegan a 7 kWh/m2 en los meses de Diciembre y Enero.
La variaci´on territorial resulta ser mucho menor a la estacional, debido
a la relativa uniformidad geogr´aﬁca de nuestro territorio. Por ejemplo, las
medias anuales muestran un m´ınimo en Rocha (3,9 kWh/m2) y un m´aximo
(4,7 kWh/m2) en la zona Norte (Artigas, Rivera, Paysand´u). La variaci´on
debida al factor territorial es de solo 0,8 kWh/m2. En t´erminos relativos al
promedio, la variabilidad territorial es algo mayor en invierno (llegando a
14 %) que en verano (cuando es del orden de 8 %). Los sitios costeros al sur
del pa´ıs (Rocha, Maldonado, Montevideo) son los que presentan menor irradiaci´on media, en tanto los mayores valores aparecen en el norte (Artigas,
Rivera, Salto, Paysand´u). Una caracter´ıstica interesante emergente de este
estudio es la rotaci´on estacional de las isol´ıneas de irradiaci´on constante. En
los meses de invierno, aparecen casi alineadas con los paralelos. A medida
que se avanza hacia el verano, se observa una rotaci´on de las isol´ıenas en sentido antihorario, de modo que en tanto en los meses de verano presentan una
orientaci´on SW-NE, y son aproximadamente paralelas a la costa oce´anica.
Esta rotaci´on de las isol´ıneas se presenta, a´un mucho mas marcada, en mapas obtenidos a partir de estimativos de irradiaci´on global basados en datos
satelitales (vea las Figuras en la Secci´on 3.4).
A continuaci´on se presenta la serie de mapas de irradiaci´on global media
diaria para el territorio nacional.

28

<!-- p. 33 -->

3.2. Mapas mensuales Cap´ıtulo 3. Mapa Solar del Uruguay

Figura 3.3: Mapa Solar del Uruguay: valores medios de irradiaci´on global diaria
para el mes de Enero.

29

<!-- p. 34 -->

3.2. Mapas mensuales Cap´ıtulo 3. Mapa Solar del Uruguay

Figura 3.4: Mapa Solar del Uruguay: valores medios de irradiaci´on global diaria
para el mes de Febrero.

30

<!-- p. 35 -->

3.2. Mapas mensuales Cap´ıtulo 3. Mapa Solar del Uruguay

Figura 3.5: Mapa Solar del Uruguay: valores medios de irradiaci´on global diaria
para el mes de Marzo.

31

<!-- p. 36 -->

3.2. Mapas mensuales Cap´ıtulo 3. Mapa Solar del Uruguay

Figura 3.6: Mapa Solar del Uruguay: valores medios de irradiaci´on global diaria
para el mes de Abril.

32

<!-- p. 37 -->

3.2. Mapas mensuales Cap´ıtulo 3. Mapa Solar del Uruguay

Figura 3.7: Mapa Solar del Uruguay: valores medios de irradiaci´on global diaria
para el mes de Mayo.

33

<!-- p. 38 -->

3.2. Mapas mensuales Cap´ıtulo 3. Mapa Solar del Uruguay

Figura 3.8: Mapa Solar del Uruguay: valores medios de irradiaci´on global diaria
para el mes de Junio.

34

<!-- p. 39 -->

3.2. Mapas mensuales Cap´ıtulo 3. Mapa Solar del Uruguay

Figura 3.9: Mapa Solar del Uruguay: valores medios de irradiaci´on global diaria
para el mes de Julio.

35

<!-- p. 40 -->

3.2. Mapas mensuales Cap´ıtulo 3. Mapa Solar del Uruguay

Figura 3.10: Mapa Solar del Uruguay: valores medios de irradiaci´on global diaria
para el mes de Agosto.

36

<!-- p. 41 -->

3.2. Mapas mensuales Cap´ıtulo 3. Mapa Solar del Uruguay

Figura 3.11: Mapa Solar del Uruguay: valores medios de irradiaci´on global diaria
para el mes de Setiembre.

37

<!-- p. 42 -->

3.2. Mapas mensuales Cap´ıtulo 3. Mapa Solar del Uruguay

Figura 3.12: Mapa Solar del Uruguay: valores medios de irradiaci´on global diaria
para el mes de Octubre.

38

<!-- p. 43 -->

3.2. Mapas mensuales Cap´ıtulo 3. Mapa Solar del Uruguay

Figura 3.13: Mapa Solar del Uruguay: valores medios de irradiaci´on global diaria
para el mes de Noviembre.

39

<!-- p. 44 -->

3.2. Mapas mensuales Cap´ıtulo 3. Mapa Solar del Uruguay

Figura 3.14: Mapa Solar del Uruguay: valores medios de irradiaci´on global diaria
para el mes de Diciembre.

40

<!-- p. 45 -->

3.2. Mapas mensuales Cap´ıtulo 3. Mapa Solar del Uruguay

Figura 3.15: Mapa Solar del Uruguay: valores medios de irradiaci´on global diaria
promediados en el a˜no.

41

<!-- p. 46 -->

3.3. An´alisis de incertidumbre Cap´ıtulo 3. Mapa Solar del Uruguay

3.3. An´alisis de incertidumbre

La estimaci´on de la incerteza asociada a los estimativos ﬁnales de irradiaci´on global diaria resulta una tarea compleja, dado que no se dispone de
la informaci´on necesaria para caracterizar el error de los datos usados como
base para este trabajo. Adoptamos una hip´otesis conservadora, asignando
una incertidumbre δN ≃1 hora a todas las medidas de heliofan´ıa diaria.
Para todas las medidas de irradiaci´on global diaria adoptamos una incerteza δH ≃0,5 kWh/m2. Estos valores, que corresponden aproximadamente
al 10 % del valor diario medio anual, son estimados teniendo en cuenta los
metadatos disponibles, en especial sobre los instrumentos utilizados y las
condiciones en las cuales se procesaron los datos.
Para estimar como estas incertezas en los datos de base afectan a los
coeﬁcientes a y b de la correlaci´on entre la heliofan´ıa y la irriadiaci´on global, se
analizaron los casos de Melilla y La Estanzuela. A partir de la cantidad de d´ıas
(para cada mes del a˜no) con datos de irradiaci´on LH ≫1 y heliofan´ıa LN ≫
1, los valores medios, ¯H y ¯N, tendr´an una distribuci´on aproximadamente
normal (Teorema Central del L´ımite, [Bev69]) con desviaciones est´andar para
el mes m (donde m = 1 . . . 12),

δH δN
σH,m = √LH , σN,m = √LN . (3.3)

A efectos de estimar el error en la regresi´on lineal, se asigna usualmente
todo el error del punto (xm, ym) a la variable dependiente ym, reasignando
su incerteza como la media cuadr´atica de las incertezas en ambas variables
[Bev69]. Es decir se supone la variable independiente afectada por una incerteza (error efectivo) σm = (σ2x,m + σ2y,m)1/2 y se toma el valor de xm como
exacto. En el caso que nos ocupa la variable dependiente es la irradiaci´on
global diaria promedio y el error efectivo, en kWh/m2, para el mes m es

s 2 ¯Hm
σm = σ2H,m + σ2N,m. (3.4) ¯Nm

Utilizando t´ecnicas est´andar de propagaci´on de errores se calcula la incidencia de este error efectivo en los coeﬁcientes de la regresi´on lineal [Bev69].
Resumimos los resultados, para el caso de los par´ametros a y b para Melilla
y La Estanzuela, en el Cuadro 3.4. El error efectivo es, en todos los casos, del
orden de 0, 05 kWh/m2 y esto se traduce en las mismas incertezas σa = 0, 02
y σb = 0, 03 para ambos lugares. Asumiremos que estos valores se aplican
tambi´en a los datos correspondientes a las ubicaciones de Salto-Salto Grande

42

<!-- p. 47 -->

3.3. An´alisis de incertidumbre Cap´ıtulo 3. Mapa Solar del Uruguay

Mes La Estanzuela Melilla
1 0.06 0.06
2 0.06 0.06
3 0.05 0.06
4 0.05 0.06
5 0.04 0.05
6 0.04 0.05
7 0.04 0.05
8 0.05 0.05
9 0.05 0.06
10 0.05 0.06
11 0.06 0.06
12 0.06 0.06
σa 0.02 0.02
σb 0.03 0.03

Cuadro 3.4: Error efectivo mensual (en kWh/m2) estimado a partir de la Ec. (3.4).
Las dos ´ultimas ﬁlas muestran como se propaga a incertezas en los par´ametros
(adimensionados) a y b, para las ubicaciones Melilla-Carrasco y La Estanzuela.

serie irradiaci´on serie heliofan´ıa a b
ZUELA Estanzuela (INIA) 0,21 ± 0,02 0,55 ± 0,03
Melilla Carrasco (DNM-3) 0,22 ± 0,02 0,47 ± 0,03
Livramento Rivera (DNM-3) 0,28 ± 0,02 0,45 ± 0,03
Salto Grande Salto (INIA) 0,23 ± 0,02 0,49 ± 0,03

Cuadro 3.5: Incertezas (calculadas y asignadas) para los coeﬁcientes a y b (Cuadro 3.1) para las cuatro ubicaciones consideradas.

43

<!-- p. 48 -->

3.3. An´alisis de incertidumbre Cap´ıtulo 3. Mapa Solar del Uruguay

y Rivera-Livramento. Por lo tanto, los valores de los par´ametros a y b se
suponen afectados por las incertidumbres indicadas en el Cuadro 3.5.
Para estimar como afecta la incerteza en los coeﬁcientes a y b usados
como base para la interpolaci´on a los estimativos de irradiaci´on global en
cada ubicaci´on, seguiremos el siguiente procedimiento. Obtendremos valores
extremos de irradiaci´on, para cada mes y cada localidad, usando los valores
extremos de los coeﬁcientes y de la heliofan´ıa. A partir de ellos, estimamos
la incerteza en el valor de irradiaci´on global.
Deﬁnimos por lo tanto, los valores extremos
a↑= a + σa b↑= b + σb N↑,m = ¯Nm + σN,m (3.5)
a↓= a −σa b↓= b −σb N↓,m = ¯Nm −σN,m (3.6)

A partir de estos valores extremos, trabajando para cada mes m, utilizamos la Ec. (3.2) para estimar los valores extremos de irradiaci´on global diaria
media,

N↑,m
H↑,m = ¯H0,m a↑+ b↑ (3.7) ¯ N0,m
N↓,m
H↓,m = ¯H0,m a↓+ b↓ (3.8)
¯N0,m

donde la dependencia espacial esta impl´ıcita. A partir de ´estos valores extremos, estimamos la incerteza ∆H,m en la irradiaci´on global como
∆H,m ≡1 (H↑,m −H↓,m) . (3.9)
2
Las incertezas obtenidas para cada mes en cada localidad, se indican en el
Cuadro 3.6. Examinando estos valores, que var´ıan entre 0,4 y 0,9 kWh/m2
se ve claramente que la variaci´on estacional es mucho m´as relevante que la
variaci´on espacial. En la pen´ultima ﬁla del Cuadro 3.6 se muestra la incertezas
promedio para cada mes. Estas incertidumbres pueden expresarse tambi´en
en t´erminos relativos, como un porcentaje del valor estimado para cada mes
en cada localidad, ¯Hm,
∆H,m
εm = 100 × . (3.10)
¯Hm
Estos errores relativos medios basados se presentan, para cada mes, en la
´ultima ﬁla del Cuadro 3.6. Como es usual, los errores relativos var´ıan desde
14 % para los meses de verano y se incrementan hasta un 19 % en los meses
de invierno, debido a los menores registros absolutos. El promedio mensual
de εm es ≃16 %, un valor que puede tomarse como un indicador global de la
incertidumbre de los estimativos de irradiaci´on, teniendo en cuenta que las
incertezas dependen del mes de a˜no y son diferentes para cada localidad.

44

<!-- p. 49 -->

3.4. Validaci´on Cap´ıtulo 3. Mapa Solar del Uruguay

Estaci´on 1 2 3 4 5 6 7 8 9 10 11 12
Salto 0.9 0.9 0.7 0.6 0.5 0.4 0.5 0.6 0.7 0.8 0.9 0.9
Paysand´u 0.9 0.8 0.7 0.6 0.5 0.4 0.4 0.5 0.7 0.8 0.9 0.9
Carrasco 0.9 0.8 0.7 0.6 0.4 0.4 0.4 0.5 0.6 0.8 0.9 0.9
San Jos´e 0.9 0.8 0.7 0.6 0.4 0.4 0.4 0.5 0.6 0.8 0.9 0.9
Florida 0.9 0.8 0.7 0.6 0.4 0.4 0.4 0.5 0.6 0.8 0.9 0.9
Durazno 0.9 0.8 0.7 0.6 0.5 0.4 0.4 0.5 0.7 0.8 0.9 0.9
Rocha 0.9 0.8 0.7 0.6 0.4 0.4 0.4 0.5 0.6 0.8 0.9 0.9
Treinta y Tres 0.9 0.8 0.7 0.6 0.5 0.4 0.4 0.5 0.6 0.8 0.9 0.9
Melo 0.9 0.8 0.7 0.6 0.5 0.4 0.4 0.5 0.7 0.8 0.9 0.9
Rivera 0.9 0.8 0.7 0.6 0.5 0.4 0.5 0.6 0.7 0.8 0.9 0.9
Tacuaremb´o 0.9 0.8 0.7 0.6 0.5 0.4 0.4 0.5 0.7 0.8 0.9 0.9
Artigas 0.9 0.9 0.7 0.6 0.5 0.4 0.5 0.6 0.7 0.8 0.9 0.9
Promedio 0.9 0.8 0.7 0.6 0.5 0.4 0.4 0.5 0.7 0.8 0.9 0.9
εm ( %) 14 14 15 16 17 19 18 17 16 15 14 14

Cuadro 3.6: Incerteza estimada, ∆H,m, a partir de la Ec. (3.9) para cada mes del
a˜no y para cada estaci´on, en kWh/m2. La pen´ultima ﬁla muestra los promedios
sobre todas las localidades. La ´ultima ﬁla muestra los errores relativos asociados
a estos promedios, deﬁnidos en la Ec. (3.10).

3.4. Validaci´on

Para el proceso de validaci´on se han seguido dos caminos diferentes. En
primer lugar, se comparan los resultados obtenidos con datos disponibles
para la regi´on. Para este ﬁn fueron reservadas cinco series de irradiaci´on. En
segundo lugar, se comparan los resultados obtenidos con los resultados de la
NASA basados en un modelo de atm´osfera y datos de im´agenes satelitales.

Comparaci´on con datos regionales

Los datos correspondientes a cinco estaciones regionales, indicadas con
“V” en el Cuadro 2.4 han sido comparados, mes a mes, con los valores inferidos para cada localidad del Mapa Solar correspondiente. En el Cuadro 3.7 se
registran estos valores de irradiaci´on media. Las Figs. 3.16 y 3.17 muestran el
error relativo ( %) para cada mes para las cinco localidades, tomando como
base el valor estimado. Los desv´ıos positivos indican valores medidos superiores a los estimados, los desv´ıos negativos indican valores medidos menores
a los estimados. El mayor error relativo es de 20 % y se observa para Bag´e en
el mes de abril. En general las diferencias est´an debajo de 15 % y en tres
localidades se observan meses donde coinciden el estimativo y los registros.

45

<!-- p. 50 -->

3.4. Validaci´on Cap´ıtulo 3. Mapa Solar del Uruguay

localidad 1 2 3 4 5 6 7 8 9 10 11 12
Jaguar˜ao 6.7 5.9 4.9 3.8 2.9 2.3 2.7 3.4 4.2 5.1 6.3 6.6
Bag´e 6.4 5.6 4.6 3.6 2.7 2.1 2.4 3.1 3.9 4.9 6.0 6.4
M. Caseros 7.1 6.3 5.1 3.9 3.1 2.4 2.9 3.7 4.6 5.6 6.7 7.0
C. Uruguay 7.0 6.1 4.9 3.7 2.8 2.2 2.6 3.3 4.4 5.4 6.6 7.0
Gualeguaych´u 7.0 6.1 4.8 3.7 2.8 2.2 2.6 3.2 4.3 5.4 6.6 7.0

Cuadro 3.7: Valores medios de irradiaci´on diaria (media mensual) estimados a
partir del Mapa Solar para las localidades indicadas.

Figura 3.16: Error relativo entre los datos de irradiaci´on media diaria (Cuadro 2.4)
y los valores estimados (Cuadro 3.7) para las localidades Brasile˜nas de Jaguar˜ao
y Bag´e. Los datos son del INMET-Brasil.

46

<!-- p. 51 -->

3.4. Validaci´on Cap´ıtulo 3. Mapa Solar del Uruguay

Figura 3.17: Error relativo entre los datos de irradiaci´on media diaria (Cuadro 2.4)
y los valores estimados (Cuadro 3.7) para las localidades argentinas de Monte Caseros, Concepci´on y Gualeguaych´u. Los datos son de la Red Solarim´etrica Argentina.

47

<!-- p. 52 -->

3.4. Validaci´on Cap´ıtulo 3. Mapa Solar del Uruguay

Comparaci´on con resultados basados en datos de sat´elite

Otra forma de validar los resultados obtenidos es compararlos con estimativos basados en metodolog´ıas, datos y modelos completamente diferentes.
Una alternativa para estimar irradiaci´on global en superﬁcie esta basada en
el uso de datos satelitales para estimar la nubosidad. Este tipo de metodolog´ıas han permitido el desarrollo de herramientas y servicios de informaci´on
en l´ınea a trav´es de los cuales se accede a estimativos de irradiaci´on solar
para extensos territorios. A partir de este dato, con un modelo f´ısico de los
procesos de dispersi´on y absorci´on de la radiaci´on en la atm´osfera es posible
obtener estimativos de irradiaci´on incidente en el suelo.
Uno de estos modelos es el UM-SBR desarrollado por Pinker y Lazlo en
la Universidad de Maryland, EEUU [PL92] y usado en la base de datos del
Atmosferic Science Data Center de la Agencia espacial norteamericana NASA/SSE. A trav´es de la implementaci´on en l´ınea de este modelo3 se pueden
obtener estimativos de irradiaci´on global media diaria, mes a mes, con una
resoluci´on espacial de un grado en latitud y en longitud, lo cual corresponde
a una resoluci´on espacial d = Rθ ≈111 km, donde R = 6371 km es el radio
medio terrestre y θ = π/180 radianes. Los promedios est´an basados en datos
sobre un per´ıodo de 23 a˜nos (Junio 1983 a Junio 2006) y el modelo esta
ajustado a las condiciones de las planicies de Winsconsin. Estimativos de
medias mensuales de irradiaci´on basados en este modelo fueron contrastados
con datos reales para varias localidades Argentinas, encontr´andose errores
rms entre 4 y 25 % [GG99].
Hemos utilizado este modelo para generar estimativos de irradiaci´on global diaria promedio para cada mes, sobre la grilla de ubicaciones mostradas
en la Fig. 3.18. Los valores estimados se indican en el Cuadro 3.8. A partir
de estos estimativos es posible interpolar, calcular isol´ıneas de irradiaci´on y
obtener la variaci´on espacial de la irradiaci´on media sobre el territorio uruguayo que implica este modelo. Las Figuras 3.19 y 3.20 muestran los mapas
de irradiaci´on global para cada mes del a˜no.
De acuerdo al modelo UMB-SR, el valor medio anual de irradiaci´on global
promediado sobre todo el territorio es de 4.6 kWh/m2. El correspondiente
valor del Mapa Solar del Uruguay es de 4.4 kWh/m2. Dado que las incertezas,
discutidas en la secci´on anterior, son mayores a 0.4 kWh/m2 el acuerdo entre
ambos valores parece muy bueno.
Dado que la mayor variaci´on es la estacional, se puede hacer un an´alis
mes a mes de las diferencias ∆≡¯HNASA −¯HMSU de ambos modelos. En el
Cuadro 3.9 se indican estas diferencias y se observa que son siempre inferiores
a 0.3 kWh/m2, por lo cual concluimos que ambos modelos son compatibles

3Ver http://eosweb.larc.nasa.gov/cgi-bin/sse/sse.cgi

48

<!-- p. 53 -->

3.4. Validaci´on Cap´ıtulo 3. Mapa Solar del Uruguay

Figura 3.18: Ubicaciones para las cuales se estim´o la irradiaci´on media diaria a
partir del modelo NASA. Los sitios distan entre si un grado de latitud y un grado
en longitud, correspondiente a una separaci´on entre puntos vecinos de unos 111 km.
Las coordenadas ﬁguran en el Cuadro 3.8.

49

<!-- p. 54 -->

3.4. Validaci´on Cap´ıtulo 3. Mapa Solar del Uruguay

LAT LON 1 2 3 4 5 6 7 8 9 10 11 12 anual
\-30.5 -57.5 6.8 5.9 5.1 3.7 3.1 2.5 2.9 3.7 4.6 5.4 6.5 6.9 4.8
\-31.5 -57.5 6.9 5.9 5.1 3.7 3.0 2.5 2.8 3.6 4.6 5.5 6.5 6.9 4.7
\-32.5 -57.5 7.0 5.9 5.1 3.7 2.9 2.4 2.7 3.5 4.6 5.4 6.5 6.9 4.7
\-33.5 -57.5 7.0 5.9 5.0 3.7 2.8 2.3 2.5 3.4 4.5 5.4 6.5 7.0 4.7
\-34.5 -57.5 6.9 6.0 4.9 3.6 2.7 2.2 2.5 3.3 4.5 5.4 6.5 7.0 4.6
\-30.5 -56.5 6.8 5.9 5.0 3.8 3.1 2.5 2.9 3.7 4.6 5.4 6.5 6.9 4.8
\-31.5 -56.5 6.9 5.9 5.0 3.7 3.0 2.5 2.8 3.5 4.5 5.4 6.5 6.9 4.7
\-32.5 -56.5 6.9 5.9 5.0 3.7 2.9 2.4 2.7 3.4 4.5 5.4 6.5 6.9 4.7
\-33.5 -56.5 6.9 5.9 5.0 3.6 2.8 2.3 2.5 3.3 4.4 5.3 6.5 7.0 4.6
\-34.5 -56.5 6.9 5.8 4.8 3.6 2.7 2.2 2.4 3.2 4.3 5.2 6.3 6.9 4.5
\-30.5 -55.5 6.7 5.8 5.0 3.7 3.1 2.5 2.8 3.6 4.5 5.4 6.4 6.9 4.7
\-31.5 -55.5 6.7 5.7 4.9 3.7 3.0 2.4 2.7 3.5 4.4 5.4 6.4 6.9 4.6
\-32.5 -55.5 6.8 5.7 4.9 3.6 2.9 2.3 2.6 3.3 4.4 5.3 6.4 6.9 4.6
\-33.5 -55.5 6.9 5.8 4.9 3.6 2.8 2.3 2.5 3.3 4.4 5.3 6.4 7.0 4.6
\-34.5 -55.5 6.9 5.8 4.8 3.5 2.7 2.2 2.4 3.1 4.3 5.2 6.3 6.9 4.5
\-30.5 -54.5 6.6 5.7 4.9 3.7 3.1 2.5 2.8 3.6 4.4 5.3 6.4 6.9 4.6
\-31.5 -54.5 6.6 5.7 4.9 3.7 2.9 2.4 2.7 3.4 4.3 5.3 6.4 6.9 4.6
\-32.5 -54.5 6.7 5.7 4.9 3.7 2.9 2.3 2.6 3.3 4.3 5.3 6.4 6.9 4.6
\-33.5 -54.5 6.7 5.7 4.8 3.6 2.8 2.3 2.5 3.2 4.3 5.2 6.3 6.9 4.5
\-34.5 -54.5 6.7 5.7 4.7 3.5 2.6 2.1 2.3 3.1 4.2 5.1 6.2 6.8 4.4
\-31.5 -53.5 6.5 5.6 4.8 3.7 2.9 2.4 2.6 3.4 4.3 5.2 6.2 6.9 4.5
\-32.5 -53.5 6.6 5.6 4.8 3.6 2.9 2.3 2.6 3.3 4.2 5.1 6.2 6.8 4.5
\-33.5 -53.5 6.6 5.6 4.7 3.5 2.7 2.2 2.4 3.1 4.2 5.1 6.1 6.7 4.4

6.8 5.8 4.9 3.6 2.9 2.3 2.6 3.4 4.4 5.3 6.4 6.9 4.6

Cuadro 3.8: Estimadores de irradiaci´on media diaria (en kWh/m2) para 23 puntos
que cubren el territorio nacional obtenidos del modelo NASA. Las ubicaciones se
muestran en la Fig. 3.18. La ´ultima columna indica las medias anuales para cada
ubicaci´on y la ´ultima ﬁla valores promedio sobre todas las ubicaciones.

1 2 3 4 5 6 7 8 9 10 11 12 anual
MSU 6.7 5.8 4.7 3.6 2.7 2.1 2.5 3.2 4.1 5.1 6.3 6.6 4.4
UM-SBR 6.8 5.8 4.9 3.6 2.9 2.3 2.6 3.4 4.4 5.3 6.4 6.9 4.6
∆ 0.1 0.0 0.2 0.0 0.2 0.2 0.1 0.2 0.3 0.2 0.1 0.3 0.2

Cuadro 3.9: Se reproducen, para cada mes, los estimativos de irradiaci´on global
diaria promediada en el territorio para el Mapa Solar del Uruguay, MSU (Cuadro
3.3), y para el modelo UM-SBR usado por NASA (Cuadro 3.8). La tercera ﬁla
muestra la diferencia absoluta ∆≡¯HNASA −¯HMSU en kWh/m2. Las diferencias est´an por debajo de la incertezas asociadas, por lo que ambos modelos son
consistentes entre si.

50

<!-- p. 55 -->

3.4. Validaci´on Cap´ıtulo 3. Mapa Solar del Uruguay

dentro del margen de error de los estimativos. Finalmente, una inspecci´on de
las Figs. 3.19 y 3.20 que muestran la distribuci´on territorial de la irradiancia
global media para cada mes del a˜no en el modelo UM-SBR, permite ver
que la rotaci´on de las isol´ıneas de irradiaci´on constante tambi´en aparece en
este modelo. Se observa una tendencia de las mismas a alinearse con los
paralelos en invierno, rotando en sentido antihorario hasta alinearse con la
direcci´on SW-NE en verano. La rotaci´on aparece m´as acentuada en el modelo
UM-SBR. Teniendo en cuenta que ambos modelos se basan en metodolog´ıas,
per´ıodos temporales y conjuntos de datos completamente diferentes, llegar a
valores consistentes entre si y a las mismas conclusiones cualitativas es un
elemento de validaci´on importante.

51

<!-- p. 56 -->

3.4. Validaci´on Cap´ıtulo 3. Mapa Solar del Uruguay

Figura 3.19: Estimativos de irradiancia media diaria basados en el modelo UMBSR usado por NASA para los meses de Enero a Junio.
52

<!-- p. 57 -->

3.4. Validaci´on Cap´ıtulo 3. Mapa Solar del Uruguay

Figura 3.20: Estimativos de irradiancia media diaria basados en el modelo UMBSR usado por NASA para los meses de Julio a Diciembre.
53

<!-- p. 58 -->

Cap´ıtulo 4

Comentarios Finales

En este trabajo se describen los pasos seguidos para elaborar la primer
versi´on del Mapa Solar del Uruguay. Se analizaron cuatro series de irradiaci´on
y numerosas series de heliofan´ıa (horas de sol) a nivel nacional. Se utilizaron dos series de irradiaci´on nacionales y dos regionales como base para el
mapa solar. La metodolog´ıa seguida consisti´o en el uso de la correlaci´on de
Amstrong-Prescott entre los promedios normalizados de irradiaci´on y heliofan´ıa. A trav´es de la misma, es posible estimar irradiaci´on en lugares donde
se cuenta con medidas de heliofan´ıa. El procedimiento seguido implica analizar la variaci´on espacial de los coeﬁcientes de correlaci´on y luego utilizar
coeﬁcientes locales para estimar la irradiaci´on a partir de la heliofan´ıa.
Se realiz´o una serie de mapas mensuales y uno anual, en los cuales se
codiﬁc´o en color la informaci´on sobre el estimativo de irradiaci´on diaria promedio para cada punto del territorio, trabajando con una resoluci´on de entre
10 y 30 km. Adem´as, se trazaron isol´ıneas de irradiaci´on media en todos los
casos. A partir de un an´alisis de incertidumbre, se estima que la incerteza en
los valores del Mapa Solar var´ıa entre el 14 y 19 % seg´un el mes del a˜no, con
los errores relativos mayores asociados a los meses de invierno (con menor
irradiaci´on media). Los valores medios de irradiaci´on global estimados para el
territorio nacional var´ıan entre 2,1±0,4 kWh/m2 en Junio y 6,7±0,9 kWh/m2
para Enero. El promedio anualizado es de 4,4 ± 0, 7 kWh/m2. Estos resultados fueron comparados con los promedios diarios correspondientes a cinco
estaciones de la regi´on cercanas a nuestras fronteras, pero ubicadas en Argentina y Brasil y se encontr´o que los estimativos son consistentes con las
mediciones, dentro de estos m´argenes de error.
Por otra parte, usando el modelo UM-SBR se puede estimar a partir
de informaci´on satelital y de un modelo f´ısico, la irradiaci´on global diaria
promedio para varios puntos de nuestro territorio. Partiendo de los datos
generados con este modelo para una red de puntos que distan unos 110 km

54

<!-- p. 59 -->

Cap´ıtulo 4. Comentarios Finales

entre si, se realiz´o un mapa solar basado en informaci´on satelital a los efectos
de compararlo con el obtenido a partir de medidas en tierra. Se obtuvo una
muy buena concordancia entre ambos estimativos, dentro del margen de error
de ambos modelos.
La metodolog´ıa utilizada es la misma que se ha usado para elaborar los
primeros mapas solares en pa´ıses vecinos [GG98b, GG98a, TFL+97, Tib04] y
los resultados obtenidos son consistentes con los de estos primeros trabajos.
Sin embargo, los m´argenes de error que resultan de esta metodolog´ıa son
relativamente grandes. En la ´ultima d´ecada se han impuesto metodolog´ıas
alternativas para estimar radiaci´on solar a partir de informaci´on obtenida de
im´agenes de sat´elite. El radi´ometro del sat´elite mide la irradiancia reﬂejada
por la capa de nubes y por la superﬁcie en diferentes bandas espectrales o
canales. En el canal visible, el agua, siendo un un buen absorbente de la
radiaci´on, reﬂeja poco y aparece oscura. En general, para las ´areas de tierra,
el albedo (en ausencia de nieve) es bastante menor que el de las nubes, lo
cual lo hace un buen indicador del tipo la cobertura nubosa asociada a cada
pixel de la im´agen. Para cada pixel, puede complementarse esta informaci´on
– dependiendo del modelo elegido – con la de los canales infrarrojo (IR)
o ultravioleta (UV). Estas metodolog´ıas requieren de un modelo (f´ısico o
estad´ıstico) que vincule la irradiancia detectada por el sat´elite (o alguna
cantidad derivada derivada de la misma, como el albedo) con la irradiancia
inicidente en el suelo [MNRF93a, MNRF93b]. Los modelos estad´ısticos deben
ser calibrados y controlados a partir de medidas en tierra. Los modelos f´ısicos
deben ser puestos a puntos y luego controlados en sus m´argenes de error,
tambi´en a partir de medidas de irradiaci´on en tierra. La resoluci´on espacial y
temporal aportada por estos m´etodos es grande ya que se trabaja con grillas
de pocos km de lado y se cuenta con datos diariamente a intervalos menores
a una hora. En la regi´on, Brasil muestra un importante grado de desarrollo
en el tema a trav´es del trabajo de J.C. Ceballos del Centro de Pesquisas
Espaciales (CPTEC/INPE/MCT) [CM97, CBS04, CB04] y en Argentina este
mismo investigador ha participado de varios trabajos sobre la aplicaci´on de
estas metodolog´ıas [CBG05, CB08, Ceb09]. En Uruguay, no se ha trabajado
hasta el momento con modelos que permitan el uso de datos satelitales para
estimar la irradiaci´on global a nivel de suelo. Este es claramente un camino a
seguir para lograr una nueva versi´on del Mapa Solar del Uruguay, con mayor
resoluci´on espacial y menores margenes de de error.
Por otro lado, tanto si la metodolog´ıa usada se basa en datos satelitales,
como si se utiliza la metodolog´ıa m´as tradicional, basada en la correlaci´on
de Amstrong-Prescott, es esencial contar con medidas de irradiaci´on de calidad controlada con una adecuada distribuci´on en el territorio nacional. Los
primeros pasos en esta direcci´on ya se est´an dando en el marco del Convenio

55

<!-- p. 60 -->

Cap´ıtulo 4. Comentarios Finales

entre la Facultad de Ingnenier´ıa y la DNETN/MIEM, mediante el cual esta
prevista la instalaci´on de 3 estaciones de medida remotas en el interior del
pa´ıs equipadas con piran´ometros Kipp & Zonen CMP 6. La primera de estas
estaciones, en Las Brujas, Canelones, ya se encuentra en funcionamiento desde hace tres meses. Siguiendo estos primeros pasos, se tiene previsto instalar
m´as sensores en los pr´oximos a˜nos.

56

<!-- p. 61 -->

Cap´ıtulo 4. Comentarios Finales

Agradecimientos

Los siguientes individuos e instituciones han colaborado directa o indirectamente con este trabajo, aportando RRHH, datos, ﬁnanciamiento, uso
de equipamientos e instalaciones o asesoramiento:

Direcci´on Nacional de Energ´ıa y Tecnolog´ıa Nuclear, DNETN/MIEM

PEDECIBA – F´ısica

UTE, Gerencia de Planiﬁcaci´on de la Explotaci´on

Direcci´on Nacional de Metereolog´ıa – DNM, Uruguay

GRAS (Clima), Unidad de Agro-clima y Sistemas de informaci´on del
Instituto Nacional de Investigaciones Agropecuarias – INIA

Mesa Solar – Uruguay

Dr. Hugo Grossi Gallegos, GER Solar, Divisi´on F´ısica, Depto. de Cien-
cias B´asicas, Universidad Nacional de Luj´an, Argentina

Ing. J. L. Duomarco

Mag. Ing. Gabriel Cazes, IMFIA, Facultad de Ingenier´ıa, UdelaR

Ing. Pedro Galione

Ing. Ventura Nunes, IIE, Facultad de Ingenier´ıa - UdelaR

Bach. Pablo Toscano, IIE, Facultad de Ingenier´ıa - UdelaR

Dra. Graciela Lesino y Dr. Luis Saravia, Departamento de F´ısica, Fa-
cultad de Ciencias Exactas, Universidad Nacional de Salta (UNSA),
Rep´ublica Argentina

Servicio Metereol´ogico Nacional – SMN, Argentina.

Instituto Nacional de Metereolog´ıa – INMET Brasil.

PROBIDES

Unidad de Sistemas Ambientales, Facultad de Agronom´ıa, UdelaR

Institutos de F´ısica (IF), de Ingenier´ıa El´ectrica (IIE), de Mec´anica de
Flu´ıdos e Ing. Ambiental (IMFIA), Facultad de Ingenier´ıa - Universidad
de la Rep´ublica, Uruguay.

57

<!-- p. 62 -->

Bibliograf´ıa

[AL75] R. Almanza and S. L´opez. Radiaci´on solar global en la rep´ublica
mexicana mediante datos de insolaci´on. Technical report, Insti-
tuto de Ingenier´ıa, UNIVERSIDAD NACIONAL AUT´ONOMA
DE M´EXICO, 1975.

[Ang24] A. Angstrom. Solar and terrestrial radiation. Report to the
international commission for solar research on actinometric in-
vestigations of solar and atmospheric radiation. Q. J. Royal
Meteorological Society, 50(210):121 – 126, 1924.

[Bev69] P.R. Bevington. Data Reduction and Error Analysis for the
Physical Sciences. McGraw-Hill, New York, 1969.

[CB04] J.C. Ceballos and Marcus Jorge Bottino. Estimativa de radia¸c˜ao
solar por sat´elite: desempenho do modelo operacional gl1.2. In
XIII CBMET - Congresso Brasileiro de Metereologia, Fortaleza,
\2004.

[CB08] J.C. Ceballos and Marcus Jorge Bottino. Radiaci´on solar en ar-
gentina estimada por sat´elite: algunas caracter´ısticas espaciales
y temporales. In Anales del IX Congreso Argentino de Mete-
reolog´ıa, Buenos Aires, 2008.

[CBG05] J.C. Ceballos, Marcus Jorge Bottino, and H. Grossi Gallegos.
Radiaci´on solar en argentina estimada por sat´elite: algunas ca-
racter´ısticas espaciales y temporales. In IX Congremet, Buenos
Aires, 2005.

[CBS04] J.C. Ceballos, Marcus Jorge Bottino, and Jaidete Monteiro De
Souza. A simpliﬁed physical model for assessing solar radiation
over Brazil using goes 8 visible imagery. Journal of Geophysical
research, 109:1–14, 2004.

58

<!-- p. 63 -->

Bibliograf´ıa Bibliograf´ıa

[Ceb09] J.C. Ceballos. Algunas caracteristicas del r´egimen de radiacion
solar en argentina, per´ıodo 1996-2006. In X Congreso Argentino
de Metereolog´ıa, Congremet, Buenos Aires, 5-9 Octubre, 2009.

[CM97] J.C. Ceballos and G.B.A. Moura. Solar radiation assessment
using meteosat 4-vis imagery. Solar Energy, 60:209–219, 1997.

[CP98] S. Colle and E. B. Pereira. Atlas de irradiacao solar do brasil,
(1a vers˜ao para irradia¸c˜ao global derivada de sat´elite e validada
na superf´ıcie). Technical report, LABSOLAR - Laborat´orio de
Energia Solar Departamento de Engenharia Mecˆanica – UFSC,
\1998.

[DB06] J.A. Duﬃe and W.A. Beckman. Solar Engineering of Thermal
Processes. Wiley and Sons, Hoboken, New Jersey, 2006.

[GG98a] H. Grossi-Gallegos. Distribuci´on de la radiaci´on solar global en
la Argentina. I. an´alisis de la informaci´on. Energ´ıas Renovables
y Medio Ambiente - ASADES, 4:13–17, 1998.

[GG98b] H. Grossi-Gallegos. Distribuci´on de la radiaci´on solar global
en la Argentina. II. cartas de radiaci´on. Energ´ıas Renovables y
Medio Ambiente - ASADES, 5:33–42, 1998.

[GG99] H. Grossi Gallegos. Comparaci´on de los valores satelitales del
surface solar energy (sse) data set version 1.0 con datos de tierra
de la red solarim´etrica. Energ´ıas Renovables y Medio Ambiente
\- ASADES, 6:1–6, 1999.

[GGR05] H. Grossi-Gallegos and R. Righini. Atlas Solar de la Rep´ublica
Argentina. Technical report, Depto. de Ciencias B´asicas de la
Universidad de Luj´an, 2005.

[GM99] R. George and E. Maxwell. High-resolution maps of solar co-
llector performance using a climatological solar radiation model.
In Proceedings of the 1999 Annual Conference, American Solar
Energy Society, Portland, ME, 1999.

[GS07] H. Grossi Gallegos and M. I. Spreaﬁchi. An´alisis de las series
de promedios anuales de heliofan´ıa (duraci´on de la insolaci´on)
en Uruguay. Energ´ıas Renovables y Medio Ambiente, 20:31– 35,
\2007.

59

<!-- p. 64 -->

Bibliograf´ıa Bibliograf´ıa

[HA04] V. Hodge and J. Austin. A survey of outlier detection methods.
Artiﬁcial Intelligence Review, 22:85–126, 2004.

[MGW99] E. Maxwell, R. George, and S. Wilcox. A climatological solar
radiation model. In Proceedings of the 1998 Annual Conference,
American Solar Energy Society, Albuquerque, NM, 1999.

[MNRF93a] M. M.˜Noia, C.F. Ratto, and R. Festa. Solar irradiance esti-
mation from geostationary satellite data: 1. statistical models.
Solar Energy, 51:449–456, 1993.

[MNRF93b] M. M.˜Noia, C.F. Ratto, and R. Festa. Solar irradiance estima-
tion from geostationary satellite data: 2. physical models. Solar
Energy, 51:457–465, 1993.

[PAW01] J. Page, M. Albuisson, and L. Wald. The european solar ra-
diation atlas: a valuable digital tool. Solar Energy, 71:81–83,
\2001.

[PL92] R.T. Pinker and I. Laszlo. Modeling surface solar irradiance for
satellite applications on global scale. J. Appl. Meteorol., 31:194–
211, 1992.

[Pre40] J.A. Prescott. Evaporation from a water surface in relation to
solar radiation. Trans. R. Soc. Sci. S. Austr, 64:114–118, 1940.

[RF06] C. Raichijk and H. F. Variabilidad espacial de la heliofan´ıa (du-
raci´on de la insolaci´on) en la pampa h´umeda Argentina, Uru-
guay y sur del Brasil. Energ´ıas Renovables y Medio Ambiente,
19:33– 37, 2006.

[RGGR04] R. Righini, H. Grossi-Gallegos, and C. Raichijk. Trazado de
nuevas cartas de irradiaci´on solar global para Argentina a partir
de horas de brillo solar (Heliofan´ıa). Energ´ıas Renovables y
Medio Ambiente - ASADES, 14:23–31, 2004.

[RGGR05] R. Righini, H. Grossi-Gallegos, and C. Raichijk. Approach to
drawing new global solar irradiation contour maps for Argenti-
na. Renewable Energy, 30:1241–1255, 2005.

[RGR06] C. Raichijk, H. Grossi Gallegos, and R. Righini. An´alisis de
los datos de heliofan´ıa en la Rep´ublica Oriental del Uruguay.
Avances en Energ´ıas Renovables y Medio Ambiente, 10:101–105,
\2006.

60

<!-- p. 65 -->

Bibliograf´ıa Bibliograf´ıa

[TFL+97] C. Tiba, N. Fraidenraich, F.J.M. Lyra, A.M. Nogueira, H. Gros-
si Gallegos, Moszkowitcz M., and E.S. Cavalcanti. Atlas sola-
rim´etrico do Brasil. relat´orio t´ecnico ﬁnal, vol. i a iv. Technical
report, Convenio No. 004 Universidade Federal de Pernambu-
co/Centro de Pesquisas de Energia El´etrica – ELETROBR´AS.,
\1997.

[Tib04] C. Tiba. Brazilian Solar Resource Atlas CD-ROM. Renewable
Energy, 29(6):991–1001, mayo 2004.

61
