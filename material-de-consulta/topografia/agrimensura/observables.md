---
type: libro
title: "observables"
author: "dblanco"
categoria: "TOPOGRAFÍA"
paginas: 5
extraccion: "texto"
fuente: "local:E:/MATERIAL DE CONSULTA/TOPOGRAFÍA/agrimensura/observables.pdf"
convertido: 2026-10-16
---

# observables

> Texto extraído de `TOPOGRAFÍA\agrimensura\observables.pdf` (5 páginas, texto). El PDF original está en el disco E: (MATERIAL DE CONSULTA); `<!-- p. N -->` marca el inicio de cada página.

<!-- p. 1 -->

FACULTAD DE INGENIERIA INSTITUTO DE AGRIMENSURA
DEPARTAMENTO DE GEODESIA

OBSERVABLES GPS

Cuatro magnitudes básicas de observación (observables) pueden ser identificadas:

Seudodistancias basadas en mediciones de los códigos.
Diferencias de seudodistancias basadas en el recuento integrado Doppler.
Fases portadoras o diferencia de fases portadoras.
Diferencias del tiempo de propagación basadas en mediciones interferométricas.

En la práctica solamente se hace uso de dos observables fundamentales que pueden ser
consideradas como mediciones de seudodistancia:

Seudodistancias basadas en observaciones de código.
Seudodistancias basadas en observaciones de portadora.

OBSERVACIONES DE CODIGO

Para realizar la medición del tiempo de propagación de la señal usando código, el receptor
genera un código idéntico al del satélite y mide el tiempo de desfasaje entre el código recibido y
el replicado. Para esto desplaza el replicado hasta alinearlo con el recibido y mide la magnitud
de dicho desplazamiento.
Si los relojes del satélite y del receptor estuvieran sincronizados, este tiempo medido sería el
que la señal empleó para viajar desde el satélite hasta el receptor. Como esto no ocurre a la
distancia determinada de esta manera se la denomina seudodistancia.
La ecuación de observación para la medición de código la podemos escribir como:

R = ρ + c ∆δ + v donde: R = seudodistancia medida.
ρ = distancia satélite receptor
∆δ = error de los relojes.
v = error de la medición.

Los códigos modulados en la señal son el CA y el P. El código P forma parte del Servicio de
Posicionamiento Preciso y su acceso se halla restringido para los usuarios no autorizados. La
mayoría de las firmas fabricantes de receptores GPS han desarrollado distintas tecnologías
para recuperar parte de la información contenida en el código P. El código CA forma parte del
Servicio de Posicionamiento Estándar, SPS, y es por tanto accesible para cualquier usuario.

OBSERVACIONES DE FASES DE PORTADORAS

Al igual que en la observación de código los receptores miden comparando la señal que llega
del satélite con una copia generada localmente. La cantidad observada es una diferencia de
tiempo que al ser multiplicada por la velocidad de la luz, constituye la seudodistancia. Los
receptores GPS pueden hacer esto con el código. Con la fase la situación es diferente. Cuando
el receptor comienza a observar un satélite y mide por primera vez la diferencia de fase entre
las ondas portadoras recibida y generada localmente por él mismo, esta diferencia de fase
inicial es un numero entero N de ciclos más una fracción de ciclo. Al ser todos los ciclos de la
portadora idénticos, el receptor puede medir solamente la parte fraccional ϕ, mientras que la
cantidad N no puede ser observada y permanece como una incógnita más en el problema del
posicionamiento con fase.
La ecuación de observación para la medición de fase la podemos escribir como:

λ (ϕ + N) = ρ + c ∆δ + v donde: ϕ = observación de fase en ciclos.
ρ = distancia satélite receptor
λ = longitud de onda de la portadora de que se trate.

<!-- p. 2 -->

FACULTAD DE INGENIERIA INSTITUTO DE AGRIMENSURA
DEPARTAMENTO DE GEODESIA

N = ambigüedad.
∆δ = error de los relojes.
v = error de la medición.

CONCEPTO DE AMBIGÜEDAD (N)

La cantidad de ciclos enteros presente en la diferencia de fase inicial medida a un satélite
constituye la ambigüedad de ese satélite respecto del receptor que los está observando.

El receptor mide entonces la diferencia de fase entre las señales recibida y local, pero sólo
dentro de un ciclo de la portadora, equivalente a un segmento de 19 cm o 24 cm de largo
según se trate de L1 o de L2 respectivamente.

La precisión de los resultados con las técnicas que usan códigos se deben a la precisión de la
observación misma. En consecuencia, si necesitamos resultados mas precisos es necesario
utilizar la fase de las ondas portadoras L1 y L2, cuya precisión es de solamente unos pocos
milímetros. Con este observable se pueden obtener las máximas precisiones alcanzables con
GPS en posicionamiento.
La observación de fase con GPS es muy precisa. Su inconvenientemente principal es que es
ambigua. La resolución de ambigüedades es el principal problema que condiciona la
productividad de los levantamientos GPS con fases.

ARCHIVOS RINEX DE OBSERVACIÓN.

En el archivo de datos de observaciones la seudodistancia se mide en metros. Se aceptan tres
tipos de seudodistancias, la C1 (código C/A o estándar sobre la frecuencia L1), la P1 (código P
o Precise en L1) y la P2 (código P en L2).

La medición de fase también se puede realizar sobre las frecuencias L1 o L2, y se denominan
del mismo modo L1 y L2. Se mide en ciclos completos, aunque en los primeros receptores la
unidad era el medio ciclo, debiéndose convertidos los datos a ciclos completos.

El RINEX también dispone de lugar para las mediciones Doppler en aquellos receptores donde
esté disponible la lectura de sus observables D1 y D2. En el RINEX se expresan en Hertz.

Ninguna de estas observables debe ser corregida por sesgos externos tales como la refracción
atmosférica o el retardo del reloj del satélite.

<!-- p. 3 -->

FACULTAD DE INGENIERIA INSTITUTO DE AGRIMENSURA
DEPARTAMENTO DE GEODESIA

Características del fichero de observación:

ETIQUETA DE CABECERA DESCRIPCIÓN

RINEX VERSION / TYPE - Versión de RINEX.
\- Tipo de fichero (“O” observ.)
\- Sistema de satélite:
\* G: GPS.
\* R: GLONASS.
\* T: NNSS Transit.
\* M: Mixto.

PGM / RUN BY / DATE - Programa de creación del fichero.
\- Agencia de creación del fichero.
\- Día de creación del fichero.

COMMENT - Comentarios.

MARKER NAME - Nombre del punto de observación.

MARKER NUMBER - Número del punto de observación.

OBSERVER / AGENCY - Nombre del observador y agencia.

REC # / TYPE / VERS - Número de receptor, tipo y software.

ANT # / TYPE - Número y tipo de antena.

APPROX POSITION XYZ - Posición absoluta aproximada del punto en la
última época.

ANTENNA: DELTA H/E/N - Altura de antena y excentricidades relativas al
este y al norte (m).

WAVELENGTH FACT L1/2 - Factores de λ para L1 y L2:
\* 1: Ciclo completo.
\* 2: Medio ciclo (cuadratura).
\* 0 en L2: Sólo una frecuencia.
\- Número de satélites con estos factores.
\- Lista de PRNs satélites.

\# / TYPES OF OBSERV - Número de observables grabados.
\- Tipos de observables grabados.
\* L1,L2: Medidas de fase L1 o L2.
\* C1: Pseudodist. con C/A en L1.
\* P1,P2: Idem con P en L1 o L2.
\* D1,D2: Doppler en L1 o L2.
\* T1,T2: Transit Integrated Doppler en 150 o 400
MHz.
\- Las unidades de las medidas son:
\* Fase: ciclos enteros.
\* Pseudodistancia: metros.
\* Doppler: Hz.
\* Transit: ciclos.

<!-- p. 4 -->

FACULTAD DE INGENIERIA INSTITUTO DE AGRIMENSURA
DEPARTAMENTO DE GEODESIA

INTERVAL - Intervalo de observación (épocas) en s.

TIME OF FIRST OBS -Tiempo de la primera época de grabación (año,
mes, día, hora, minuto y segundo).
\- Sistema de tiempo:
\* GPS: tiempo GPS.
\* GLO: tiempo UTC.

TIME OF LAST OBS - Tiempo de la última época de grabación.
La estructura es análoga a la anterior.

LEAP SECONDS - Salto de segundos desde el 6-1-1980. Es
recomendable su uso con datos mixtos.

END OF HEADER - Final de cabecera.

OBS RECORD - Epoca (año, mes, mes, día, min, seg).
\- Señal 0 (OK) ó 1 (falta de sincronismo
entre la época anterior y la actual.
\- Número de satélites en la época actual.
\- Lista de PRNs en la época actual.
\-Valores de las observables.
\- Desfase del reloj del receptor.

Ejemplo de fichero de observación de datos GPS:

2 OBSERVATION DATA G (GPS) RINEX VERSION / TYPE
ASHTORIN 03 - JUN - 05 10:39 PGM / RUN BY / DATE
COMMENT
AZCOLLAZO MARKER NAME
AZCOLLAZO MARKER NUMBER
OBSERVER / AGENCY
ASHTECH UZ-12 ZC00 0A12 REC # / TYPE / VERS
ANT # / TYPE
2914743.3800 -4349235.7900 -3630528.7900 APPROX POSITION XYZ
1.6794 0.0000 0.0000 ANTENNA: DELTA H/E/N
1 1 WAVELENGTH FACT L1/2
7 L1 L2 C1 P1 P2 D1 D2 # / TYPES OF OBSERV
15.0000 INTERVAL
LEAP SECONDS
2005 6 1 14 7 15.000000 GPS TIME OF FIRST OBS
2005 6 1 14 17 30.000000 GPS TIME OF LAST OBS
END OF HEADER

05 6 1 14 14 45.0000000 0 8G24G29G04G05G28G07G09G26 -0.000000411
\-1141092.180 1 -858175.70141 24050109.953 24050109.4254 24050114.9034 1500.960 1169.579
11848812.762 1 9226732.11341 21579719.970 21579719.2754 21579723.4644 -2896.707 -2257.174
9342253.295 1 7325006.35541 24228163.608 24228163.2754 24228169.2834 2555.472 1991.277
9526236.019 1 7468540.31541 23421284.708 23421283.6634 23421288.7844 2210.912 1722.789
11855297.841 1 9231355.60041 23741196.752 23741195.7164 23741199.1654 -2857.781 -2226.842
11170496.528 1 8703036.02441 20659580.848 20659579.6344 20659584.0994 -1484.192 -1156.513
9326304.344 1 7278675.36741 22535276.343 22535275.4524 22535279.5474 2584.784 2014.117
11079132.526 1 8632470.94241 20789941.963 20789941.3854 20789945.4404 -1299.818 -1012.845

05 6 1 14 15 0.0000000 0 8G24G29G04G05G28G07G09G26 -0.000000400
\-1163312.816 1 -875490.44741 24045881.478 24045881.0554 24045886.5814 1492.920 1163.314
11892553.355 1 9260815.67541 21588043.600 21588042.8674 21588047.0564 -2903.656 -2262.589
9304184.278 1 7295342.19041 24220919.247 24220918.8774 24220924.9324 2552.708 1989.123
9493321.347 1 7442892.53541 23415021.283 23415020.2294 23415025.2914 2209.127 1721.398
11898383.200 1 9264928.57141 23749395.652 23749394.5674 23749398.1144 -2856.815 -2226.090
11193063.668 1 8720620.78641 20663875.135 20663873.9224 20663878.4934 -1492.975 -1163.357

<!-- p. 5 -->

FACULTAD DE INGENIERIA INSTITUTO DE AGRIMENSURA
DEPARTAMENTO DE GEODESIA

9287778.661 1 7248655.35541 22527945.141 22527944.2914 22527948.3374 2583.181 2012.868
11098946.412 1 8647910.30641 20793712.461 20793711.8784 20793715.9294 -1310.312 -1021.022
