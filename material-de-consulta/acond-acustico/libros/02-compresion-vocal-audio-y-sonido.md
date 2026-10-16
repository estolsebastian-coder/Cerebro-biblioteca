---
type: libro
title: "02_COMPRESIÓN_VOCAL,_AUDIO_y_SONIDO"
author: ""
categoria: "ACOND. ACÚSTICO"
paginas: 8
extraccion: "texto"
fuente: "local:E:/MATERIAL DE CONSULTA/ACOND. ACÚSTICO/libros/02_COMPRESIÓN_VOCAL,_AUDIO_y_SONIDO.pdf"
convertido: 2026-10-16
---

# 02_COMPRESIÓN_VOCAL,_AUDIO_y_SONIDO

> Texto extraído de `ACOND. ACÚSTICO\libros\02_COMPRESIÓN_VOCAL,_AUDIO_y_SONIDO.pdf` (8 páginas, texto). El PDF original está en el disco E: (MATERIAL DE CONSULTA); `<!-- p. N -->` marca el inicio de cada página.

<!-- p. 1 -->

COMPRESIÓN VOCAL, AUDIO y SONIDO

1002
COMPRESIÓN VOCAL, AUDIO y SONIDO
A cerca de los compresores vocales para señales de telefonía, sonido y audio de alta calidad.

1- COMPRESION VOCAL

1.1 CLASIFICACIÓN

La historia comienza con la codificación del canal vocal a 64 Kb/s; sin embargo, esta velocidad no es la más apropiada para
muchas aplicaciones debido a la elevada tasa de datos. Se pueden aprovechar las características de la señal vocal para
comprimir la velocidad:
\-Distribución de probabilidad de amplitud no-uniforme.
\-Correlación no-cero entre muestras sucesivas.
\-Existencia de ráfagas de muestras (períodos de silencio).
\-Cuasi-periodicidad de la señal vocal.

Los tipos de algoritmos de codificación vocal se codifican mediante los siguientes algoritmos:
\-Los codificaciores de forma de onda en el dominio del tiempo: PCM, ADPCM, Delta.
\-Codificadores de forma de onda en el dominio de la frecuencia: ATC (Adaptative Transform Coding).
\-Los codificadores Vocoders (LPC, IMBE) y los híbridos (RPE, VSELP, CELP).

El ATC utiliza la técnica de Transformada Discreta Coseno DCT utilizada normalmente en codificadores de vídeo. En el
vocoder se codifican los parámetros relacionados con la percepción. El codificador híbrido es del tipo análisis-y-síntesis de la
señal. El orden cronológico y comparativo de las recomendaciones se indica en las Tabla 01.

Tabla 01a: Historia de la codificación digital de la palabra.
Año Organismo Codificación
1972 CCITT G.711 Canal telefónico PCM a 64 kb/s.
1984/90 ITU-T G.721-723-726 Canal telefónico ADPCM a 16, 24, 32 y 40 kb/s.
1988 ITU-T G.722 Canal audio Wideband ADPCM a 48, 56 y 64 kb/s.
1988 ETSI-GSM Telefonía celular RPE-LTP a 13 kb/s.
1990 EIA-TIA Canal vocal celular IS-54 VSELP a 7,95 kb/s para sistema dual celular.
1993 EIA-TIA Canal celular IS-95 QCELP para sistema CDMA a 0,8 a 8,5 kb/s.
1995 ITU-T G.728/729 Telefonía celular LD-CELP a 16 kb/s y CS-ACELP a 8 kb/s.

Fig 01b. Comparación entre sistemas de codificación.
Codificación Velocidad kb/s Norma Año MOS Tamaño trama mseg
PCM 64 G.711/712 1972 4,3 0,125
ADPCM 32 G.721 1984 4,1 0,125
ADPCM 16, 24, 32, 40 G.726 1990 0,125
LD-CELP 16 G.728 1992 4,0 0,625
CS-CELP 8 G.729 1995 10
MPC-MLQ 5,3 y 6,4 G.723.1 1995 30
RPE-LTP 13 GSM 1991 3,5 20
VSELP 8 IS-54 1993 3,5 20
IMBE 6,4 Inmarsat-M 1993 3,4
QCELP 1...8 IS-95 1993 3,4 20
CELP 4,8 FS-1016 1991 3,2 30
LPC-10 2,4 FS-1015 1984 2,3 22,5

1002-(1)

<!-- p. 2 -->

COMPRESIÓN VOCAL, AUDIO y SONIDO

Fig 01c. Standard desarrollados para aplicaciones de multimedia.
Network ISDN PSTN Ethernet ATM IP
Standard H.320 H.324 H.322 H.310/321 H.323
Vocal G.711/728 G.723.1/729 G.711/G.728 G.711/G.728 G.711/723.1/729
Velocidad 16 a 64 kb/s 5,3 a 8 kb/s 16 a 64 kb/s 16 a Nx64 kb/s 5,3 a 64 kb/s
Vídeo H.261 H.261/263 H.261 H.261/262 H.261/263
Datos T.120 T.120 T.120 T.120 T.120
Múltiplex H.221 H.223 H.221 H.221/222 H.225
Control H.242 H.245 H.242 H.242/245 H.245
Señalización Q.931 Q.931 Q.931/2931 Q.931

ADPCM (Diferencial PCM Adaptativa). Consiste en una codificación PCM donde se transmite codificada la diferencia entre
la muestra y un valor de predicción. En general, la diferencia entre muestras tiene una distribución de amplitudes más
concentrada que las propias muestras. Se dice que las muestras se encuentran fuertemente correlacionadas entre sí; en otras
palabras, existe redundancia en la señal vocal.

El predictor y la distribución de niveles de cuantificación del codificador se realizan en forma adaptativa de acuerdo con la
variación de la señal. En la Fig 01 se muestra un diagrama esquemático del Codec ADPCM. Obsérvese la presencia del
circuito predictor que calcula una predicción de la muestra sobre la base de los valores anteriores, es decir, a la historia de la
señal. Este método se utiliza para codificar canales telefónicos satelitales y para señales de vídeo. Permite una considerable
ganancia de velocidad a cambio de una complejidad mayor a PCM.

Fig 01. Codificadores de señales en banda vocal.

CODIFICACIÓN DELTA. Es un caso especial de ADPCM. El número de bits de codificación por muestra es 1 y el
predictor es un integrador; en cambio, la velocidad de muestreo es mucho más alta (32 o 64 kHz). La frecuencia de muestreo
debe ser suficiente para impedir el efecto de sobrecarga en la pendiente. En la Fig 01 se muestra el diagrama a bloques. La
mayor pendiente de crecimiento de la señal senoidal se produce en el cruce por cero y vale 2π.f.A (f la frecuencia y A la
amplitud). Con una frecuencia de muestreo fs y un escalón de altura S la pendiente de la codificación es S.fs. La sobrecarga
se produce cuando (2π.f.A) ≥ (S.fs). El valor de frecuencia de muestreo fs se obtiene de esta desigualdad.

Siempre que se detecta una sobrecarga se puede recurrir al cambio de amplitud conforme a un algoritmo predeterminado;
esto implica la codificación Delta Adaptativa. En la codificación delta no se requiere una trama para reconocer los octetos
como en PCM ya que cada muestra se codifica con un solo bit. Es simple y de baja eficiencia. Se ha usado para codificar
canales de servicio de mantenimiento, no tiene actualmente otras aplicaciones importantes.

1002-(2)

<!-- p. 3 -->

COMPRESIÓN VOCAL, AUDIO y SONIDO

1.2- TELEFONÍA ADPCM

En ITU-T G.721 se determina la forma de codificación para reducir la velocidad de 64 kb/s (8 bits por muestra), mediante la
técnica Diferencial PCM Adaptativa a una velocidad de 32 kb/s (4 bits por muestra). Pudiéndose usar velocidades aún
menores (En ITU-T G.726 se dispone de información referida a las velocidades de 40/32/24/16 kb/s). A cambio de la
reducción de velocidad se tiene una inferior S/Nq. Por ejemplo, mientras en una codificación PCM ley A la S/Nq es mejor
que 33 dB en una amplia gama de señal de entrada, en el caso de ADPCM a 32 kb/s se reduce a 30 dB.

En la Fig 01 se presenta el diagrama a bloques de funcionamiento. Cada muestra es convertida en una codificación uniforme
de 12 bit. Se pasa entonces de la señal S(k) a S1(k). Con k se identifica una muestra genérica. Se calcula la señal de
predicción Se(k) y se obtiene la diferencia entre ambos d(k). Luego se procesa la señal d(k) mediante un codificador
adaptativo no-uniforme de 16 niveles de cuantificación (4 bit). La señal de salida I(k) consta de un bit de signo y 3 de
magnitud.

Para calcular el valor de predicción Se(k) se parte de la señal I(k) y mediante un cuantificador inverso se obtiene la señal
dq(k). La predicción se calcula mediante la siguiente expresión:

Se(k) = Σ2 ai(k-1).Sr(k-i) + Σ6 bi(k-1).dq(k-i)

En palabras: la señal Se(k) tiene en cuenta 6 diferencias anteriores dq y 2 muestras anteriores de Sr(k). La señal Sr(k) es la
muestra reconstruida por la suma de la predicción y la señal transmitida (Sr+dq). (Se puede asimilar a predecir el tiempo
meteorológico de un cierto día en base al estado del tiempo de los 2 días anteriores y el error de predicción de los 6
anteriores).

El cuantificador es adaptativo; es decir, cambia el factor de escala de acuerdo con las características de la señal muestreada.
El factor de escala tiene dos posibles estados: el modo rápido y el modo lento. El primer caso ocurre con señales que tienen
grandes fluctuaciones (señales de telefonía) y el segundo ocurre con señales de pequeñas fluctuaciones (señales de datos en la
banda de frecuencia vocal). La transcodificación desde la ley A a ADPCM a 32 kb/s produce una distorsión pequeña en
telefonía, nula en facsímil del grupo 3 y elevada en conexiones de datos a velocidad por encima de 4800 b/s mediante modem
de datos.

1002-(3)

<!-- p. 4 -->

COMPRESIÓN VOCAL, AUDIO y SONIDO

2- CODIFICACIÓN PARA TELEFONIA CELULAR

2.1- TELEFONÍA VOCODER

Una forma más eficiente de codificación es la predicción lineal LPC (Linear Predictive Coders) o LPAS (Linear Prediction
Analysis-by-Syntesis). Es útil para señales que pueden modelarse como un sistema lineal. Mientras que PCM-ADPCM-Delta
son «técnicas de codificación de forma de onda», LPC se basa en la «estimación lineal de la fuente». En la Fig 01 se muestra
un diagrama a bloques del funcionamiento del LPC. Las muestras X(n) se determinan como una función lineal de una
Secuencia de Excitación V(n) (señal de pulsos) y una predicción en base a las muestras anteriores X(n-i). Matemáticamente:

X(n) = A.V(n) + ΣN ai.X(n-i)

El orden de cálculo N es el valor total de muestras X(n-i) usadas en la predicción. Los valores de A y ai se codifican y
transmiten en lugar de la muestra X(n). Para reducir el número de bits se toman varias muestras y se transmiten los
parámetros A y ai. En lugar de codificar cada muestra individual se codifican los parámetros de un grupo de ellas (parámetros
del sistema lineal). Este tipo de codificación da lugar a diferentes métodos de reducción de velocidad en sistemas de telefonía
móvil. Algunos detalles adicionales se encuentran en los trabajos referidos a sistemas radioeléctricos móviles.

CODEC VSELP (Vector Sum Excited Linear Predictive). Es una versión de codec desarrollado por Motorola. Se utilizan 3
fuentes de excitación al filtro de síntesis LPC. Uno de ellos utiliza un código de largo plazo adaptativo (code-book). Los
restantes son conjuntos de códigos de 128 vectores cada uno. Las 3 señales se multiplican por la ganancia para obtener la
amplitud adecuada y se suman para ingresar al filtro de síntesis. El resultado se utiliza para actualizar al código adaptativo. El
filtro de síntesis es de orden 10. Actúa sobre 40 muestras de entrada en 5 mseg. Es usado en el sistema celular dual
americano D-AMPS (IS-54) y en Iridium a una velocidad de 7,95 kb/s.

Las características de codificación son:
\-La codificación VSELP tiene una tasa de muestreo de 8 kHz y la codificación inicial es de 13 bits por muestra. Las muestras
se reúnen en tramas con longitud de 160 muestras (20 mseg). La trama se divide en 4 sub-tramas de 40 muestras (5 mseg). El
filtro de síntesis digital es un predictor LPC con señal de excitación de corto y largo plazo y de orden 10. La tasa de
información de la codificación es 7950 b/s y corresponde a 159 bits/trama. Este proceso introduce un retardo de 100 mseg y
entrega una calidad MOS cercana a 3.

Tabla 02. Contenido de la trama VSELP.
R0 (5 bits). Energía de trama. Señala el nivel de energía promedio de las muestras.
LPC (38 bits). Coeficientes de predicción del filtro de corto plazo. Son 10 coeficientes LPC con longitud desde 6
a 2 bits. Se trata de un filtro de síntesis Predictivo Lineal.
LAG (28 bits). Retardo del predictor a largo plazo con 7 bits para cada una de las 4 sub-tramas.
CODE (56 bits). Se usan 2 secuencias de códigos (codebook 1 y 2) y se cambian en cada subtrama. Identifica al
bloque usado. Son 2 palabras de códigos para cada una de las 4 subtramas (2x4x7 bits).
GSPO (32 bits). Identifica la ganancia con 8 bits/subtrama.

\-Protección contra errores: La secuencia de 159 bits de la trama son protegidos contra errores mediante la codificación
convolucional. Los bits se separan en dos grupos 77+82 bits (clase I y II). Los 82 bits de clase II no se someten a la
protección. A los 77 bits de clase I se le añaden 7 bits de control CRC con el polinomio generador 10110111. A los 84 bits
resultantes se le agregan 5 bit de Tail y se los someten a una codificación convolucional del tipo 1/2. Los polinomios
generadores para FEC-1/2 son 111101 y 101011. El conjunto de bits de clase I es 178 bits. El conjunto de clase I y II forma
una secuencia de 260 bits por trama. Para reducir el efecto de las ráfagas de errores se aplica un codificador interleaver. El
interleaver es una matriz de 26x10 bits que afecta a dos tramas sucesivas y distribuye los datos en el tiempo. La velocidad
final es 13 kb/s.

RPE-LTP (Regular Pulse Excitation-Long Term Prediction). Este código combina las propuestas de Francia RELP y de
Alemania MPE-LTP. El proceso agrupa las muestras en intervalos de 20 mseg. Luego se realiza una predicción a corto plazo
y a largo plazo. Se transmite el código de error residual. Es usado en GSM y DCS1800 a una velocidad de 13 Kb/s.

CELP (Code Excited Linear Prediction). En este caso se dispone de un Codebook de señales de excitación al filtro. Por cada
grupo de muestras se busca el código que genera la mejor aproximación como excitador. Se transmite el índice del código
seleccionado. Es una codificación muy compleja, que requiere 500 millones de operaciones al segundo y entrega elevada
calidad con una tasa de 2,4 Kb/s. Es usado en CDMA (IS-95) con un ajuste de velocidad de acuerdo con el nivel de ruido
desde 9,6 Kb/s a 2,4 Kb/s. Fue desarrollado por Qualcomm.

El CELP se aplica en la norma G.729 para aplicaciones de voz sobre protocolo IP (VoIP). La variante es CS-CELP
(Conjugate Structure-CELP) que es un vocoder del tipo LPAS (Linear Predictive Analysis-by-Synthesis). Por vocoder se

1002-(4)

<!-- p. 5 -->

COMPRESIÓN VOCAL, AUDIO y SONIDO

entiende un análisis/síntesis en el dominio de la frecuencia; esto puede ser realizado mediante la emisión de los parámetros
de vocoder, mediante filtros DTF (Discrete Fourier Transform) o por LPC. Una comparación entre métodos se indica en la
siguiente Tabla 03.

Tabla 03a. Comparación entre sistemas de compresión vocal para multimedia y VoIP.
Standard ITU-T G.729 ITU-T G.729.A ITU-T G.723.1
Velocidad en kb/s 8 8 5,3 a 6,3 kb/s
Longitud de trama 10 mseg 10 mseg 30 mseg
Subtrama 5 mseg 5 mseg 7,5 mseg
Retardo 15 mseg 15 mseg 37,5 mseg
MIPS 20 10 14 a 20
RAM necessary 5,2 kByte 4 kByte 4,4 kByte
Calidad MOS 3,5 3,5 3,5
Tabla 03b. Elementos de comparación de calidad vocal.
CM5 Calidad excelente.
CM4 Calidad buena, señal con algo de ruido.
CM3 Calidad fallada, requiere algunas repeticiones.
CM2 Calidad pobre, requiere repeticiones permanentes.
CM1 Calidad insatisfactoria, no se reconoce la señal vocal.
MOS4 a MOS4,5 Circuito PCM de 64 kb/s y ADPCM de 32 kb/s.
MOS3 a MOS4 Para un canal digital de tipo ADPCM de 16 kb/s.
MOS2,5 a MOS3 Para la codificación del tipo LPC a 2,4 kb/s.

2.2- COMPARACION DE SISTEMAS DE CODIFICACION

Los atributos de los codificadores vocales se comparan mediante los siguientes parámetros:
\-Velocidad de codificación: en términos de kb/s.
\-Retardo de codificación: consiste en el algoritmo de codificación, el análisis vocal y el retardo de comunicación.
\-Complejidad: medido en millones de instrucciones por segundo (MIPS) y tamaño de memorias ROM y RAM.

Por ejemplo ITU-T G.723 requiere para 6,3 kb/s una trama de 30 mseg con un retardo de algoritmo de 37,5 mseg; requiere
entre 14 y 20 MIPS y 4,4, kByte de memoria RAM. En cambio la ITU-T G.729 para 8 kb/s requiere una trama de 10 mseg y
un retardo de algoritmo de 15 mseg; son 20 MIPS y 5,2 kByte de memoria RAM.

CRITERIOS DE PERFORMANCE. La calidad vocal de un sistema celular se mide sobre la base de un criterio subjetivo
de la señal. Se trata de la cifra de mérito CM (Circuit Merit). El valor obtenido mediante el promedio de evaluación de
usuarios se denomina MOS (Mean Opinion Score). Un criterio de calidad adicional es el GOS (Grade Of Service) definido
como la posibilidad de acceso al sistema. La definición de CM y MOS tienen los valores indicados en la Tabla 03.

Uno de los problemas típicos de la compresión vocal es la pérdida del “tinte de la voz” de forma que resulta dificultoso
distinguir quien es el que habla. La detección de actividad vocal y la interrupción de la codificación que involucra es otro
problema clásico: resulta difícil de entender la mención de números sucesivos con intervalos de tiempo cortos, debido a que
el tiempo para recomenzar la transmisión es una fracción importante del tiempo de duración. La detección del umbral entre
ruido y señal vocal se dificulta cuando se realiza desde medios móviles donde el nivel de ruido es normalmente elevado.

1002-(5)

<!-- p. 6 -->

COMPRESIÓN VOCAL, AUDIO y SONIDO

3- SONIDO DE ALTA CALIDAD

COMPARACIÓN. Los canales de audio, sonido (asociado a señales de vídeo o para programas de calidad profesional) y
CD, disponen de las características de la Tabla 04.

Tabla 04: Comparación entre sistemas de codificación de alta calidad.
Canal Codificado Telefonía Audio Sonido Disco CD 1) Dolby AC-3
Inicio de banda 300 Hz 50 Hz 40 Hz 15 Hz 3 Hz
Final de banda 3400 Hz 7000 Hz 15000 Hz 24000 Hz 20000 Hz
Fm de muestreo 8000 Hz 16000 Hz 32000 Hz 48000 Hz 48000 Hz
Tolerancia 50 ppm 50 ppm 50 ppm
Conversión lineal 12 bits 14 bits 14 bits 16 bits 16 bits
Compresión G.712 G.722 J.41 ISO ATSC
Codificación PCM DPCM-4 bits PCM PCM AC-3
Bits de paridad No No 1 bit BCH-RS CRC-16
Velocidad total 64 kb/s 64 kb/s 2x384kb/s 2x768kb/s 5ch: 384 kb/s

3.1- CANAL DE SONIDO.

Se trata del canal asociado a señales de TV analógica comercial o radios FM. El valor de 384 Kb/s coincide con 6x64 Kb/s
que corresponde a un común denominador de los sistemas de 1544 (24x64) y 2048 (30x64) Kb/s. En ITU-T J.41 se entrega
la curva de compresión de 14 a 11 bits (1 bit de polaridad, 3 bits de segmento, 7 bits de código y 1 bit de paridad). Se trata de
la ley A de compresión con 7 grupos de 128 niveles cada uno y 6 segmentos (el primero es común para los 2 primeros
grupos). La resolución efectiva de los segmentos varía desde 9 a 14 bits/muestra.

Por lo general, la distribución del ruido es uniforme dentro de la
Frecuencia Ponderación Preénfasis
banda, pero la distribución de energía del canal no lo es. Por lo 0 Hz 18,75 dB
tanto en ITU-T J.17 se presenta una curva para el pre-énfasis del 100 Hz -19,8 dB
canal de radiodifusión. La misma tiene los valores de inserción de 800 Hz - 1,9 dB 13,10 dB
la Fig 02. La medición del nivel de tensión de ruido en un canal 1 kHz 0 dB
de radiodifusión sonora debe concordar con pruebas subjetivas. 2 kHz + 0,6 dB 6,98 dB
En la norma ITU-R (CCIR) Rc 468 se determina la red de 8 kHz +11,4 dB 1,01 dB
ponderación para dicha medida. La curva posee el nivel de 10 kHz 0,68 dB
referencia en 1 kHz, el máximo en 6,3 kHz. 12,5 kHz 0 dB
16 kHz -11,7 dB
La Fig 02 indica por otra parte, el funcionamiento del bit de 31,5 kHz -42,7 dB
paridad que acompaña a los 11 bits de información. Obsérvese
que un error en el bit de paridad obliga a repetir la muestra anterior. Cuando se detectan con error 3 o 4 paridades en 4
muestras consecutivas se atenúa hasta el silenciamiento del canal de sonido. Cuando se reciben 5 códigos correctos
consecutivos se repone el canal eliminando la atenuación.

En ITU-T J.21 se determina las mediciones a efectuar sobre el circuito radiofónico:
\-Impedancia (600 ohm simétrica) y niveles (máximo +9 dBmOs);
\-Respuesta de amplitud vs frecuencia (±0,5 dB entre 0,125-10 kHz);
\-Respuesta de amplitud vs nivel (±0,5 dB entre -6 y +6 dBmOs);
\-Ruido en el canal en reposo (máximo -51 dBqOps);
\-Variación de retardo de grupo; Diferencia de ganancia y fase entre canales estéreo.
\-Distorsión de armónica, intermodulación, diafonía;

\1) La grabación de un CD se efectúa mediante un disco de 120 mm de diámetro y 1,2 mm de espesor con la superficie de
aluminio y una cubierta plástica transparente. La información se graba como pequeños relieves codificados (1 lógico cambia
el relieve y 0 lo mantiene). La capacidad del disco es cercana a 500 MByte de datos (75 minutos de grabación). La corrección
de errores BCH-RS permite eliminar un máximo de 14000 errores en ráfaga equivalente a una surco en la superficie de 2 mm
de diámetro.

1002-(6)

<!-- p. 7 -->

COMPRESIÓN VOCAL, AUDIO y SONIDO

Fig 02. Codificación del canal de sonido de alta calidad.

3.2- CODIFICACION EN SUB-BANDA

Este proceso convierte las muestras de la señal de audio en el dominio de la frecuencia mediante la Transformada Discreta de
Fourier DTF (Discrete Fourier Transform). La expresión matemática de la DTF de una secuencia Xn de longitud N es:

Ck = 1/N . ΣN Xn . exp (-j2πkn/N)

Esta señal se descompone en frecuencias cuyas características corresponden a estudios subjetivos humanos. El proceso de
separación se denomina Filtering. Este tipo de circuito se realiza mediante filtros FIR (Finite Impulse Response). El
resultado es un banco de filtro de análisis que pueden estar solapados o no entre sí. Los resultados se codifican en forma
exponencial en una mantisa y el exponente.

Mediante un proceso denominado Bit Allocation se procede a seleccionar la mejor forma de cuantificación final de los
resultados. Este proceso es dinámico autoadaptativo y corresponde a estudios de tipo subjetivos. En la Tabla 03 se disponen
de dos normas que utilizan este proceso.

ITU-T G.722. Esta norma codifica la palabra con una banda de 7 kHz y una frecuencia de muestreo de 16 kHz. Cada
muestra se codifica en 14 bits de codificación uniforme. Esto se pasa por un juego de filtros de 14 coeficientes. La salida de
los filtros es submuestreado con una tasa de dos (mitad de muestras) y se codifica en ADPCM. La banda baja (hasta 4 kHz)
ocupa 48 kb/s y la banda alta (desde 4 a 7 kHz) ocupa los 16 kb/s restantes para obtener un total de 64 kb/s.

AUDIO PARA DTV-ATSC. La codificación de la señal de audio para el sistema Digital de TeleVisión DTV (norma ATSC)
se denomina AC-3 (Audio Compresor). Se disponen de 6 canales de sonido para el sistema DTV; los mismos son: izquierdo,
central y derecho normales; izquierdo y derecho Surround; LEF (Low Frequency Enhancement). El ancho de banda de los
canales de sonido es de 3Hz-20 kHz con excepción del LEF que tiene 120 Hz para efectos especiales de baja frecuencia.

El codec de sonido trabaja en el dominio de la frecuencia debido a que permite una mejor compresión sicoacústica. La
frecuencia de muestreo es de 48 kHz para soportar una banda de 20 kHz de los canales de sonido. La codificación se realiza
en forma uniforme a 16 bits antes de ser comprimida. Los pasos de codificación para la reducción de la velocidad son los
siguientes:

1002-(7)

<!-- p. 8 -->

COMPRESIÓN VOCAL, AUDIO y SONIDO

1- Banco de filtro de análisis: Trabaja con un total de 256 muestras de audio las que se convierten desde el dominio del
tiempo al dominio de la frecuencia. Para esta operación se utiliza una variante de la transformada rápida de Fourier FFT
(Fast Fourier Transform) que permite remover el 100% de la redundancia. Como resultado se obtienen 256 coeficientes de
frecuencia. Cada uno de los coeficientes es representado en notación exponencial (con valor máximo 1): mantisa y
exponente.

2- Codificación de envolvente espectral: Los exponentes de la notación exponencial anterior se codifican para obtener la
envolvente espectral. Esta información será enviada hacia el decodificador junto con la mantisa y además alimenta una rutina
que determina la cantidad de bits necesarios en la codificación de la mantisa. Esta rutina se basa en un modelo sicoacústico
para determinar la S/N óptima para cada coeficiente de frecuencia.

3- Cuantificación de mantisa. Cada mantisa se codifica desde 0 a 16 bits de acuerdo con el algoritmo anterior.

4- Formación de la trama AC-3: La información de la envolvente espectral y de la mantisa de los 6 canales de audio se
ingresan en una trama. Esta trama contiene 1536 muestras de audio; son 6 canales de audio por 256 muestras. Contiene
además información de sincronismo para alineamiento SI (Sync Information); información de servicio indicando el tipo de
codificación utilizado BSI (Bit Stream Information); y paridad para control de errores del tipo CRC-16.

3.3- COMPACT-DISC.

El diseño del disco compacto CD se debe a Philips-Sony-1979. La frecuencia de muestreo es de 44,1 kHz y la codificación
del sonido es en 16 bits (2 Bytes). Utiliza dos procesos de importancia: corrección de errores FEC-RS Reed-Solomon e
interleaver. Ambos permiten:

\-Máxima longitud de bits corregibles: 4000. Esto equivale a una marca de 2,5 mm.
\-Máxima longitud de bits interpolables: 12000. Lo cual equivale a 8 mm.
\-Interpolación: 1000 muestras/minuto (BER=10-3). Error no detectado: 1 cada 750 hs a BER=10-3.

Cada muestra tiene 2 Byte por cada canal estéreo. Se llevan a una trama de 24 Bytes (período de 6 muestras). El conjunto se
somete a 3 etapas de interleaver y a dos etapas de corrección de errores RS. Las 5 etapas de codificación son las siguientes:

Tabla 05. Etapas de codificación de la señal digital en CD.
∆ Se dispone una primer etapa de interleaver. Son 6 muestras de 2 Bytes y para 2 canales estéreo (L-R). Los
24 Bytes se intercalan de a 4 Bytes (LLRR): 4 Bytes sin retardo, 4 Bytes con 2 tramas (24 Bytes) de
retardo.
C1 Inner Code. Se agrega un codificador FEC RS de 4 Bytes para los 24, llegando a 28 Bytes en total.
D* Interleaver convolucional donde cada Byte se retarda un tiempo distinto.
C2 Outer Code. Se agrega un codificador FEC RS de 4 Bytes para los 28, llegando a 32 Bytes en total.
D Se dispone una tercera etapa de interleaver. Intercalado cruzado entre Bytes pares de una trama y Bytes
impares de la próxima.

De esta forma los FEC-RS(28,24) y RS(32,28), permiten la corrección de errores y los interleaver permiten la distribución de
los datos a lo largo de las pistas del CD. Un hueco sobre el disco no produce ráfagas de error. En caso de tener una muestra
irreconocible se inserta una muestra estimada (proceso de interpolación). Cuando 48 o más tramas se detectan con ráfagas de
errores o si 2 o más muestras consecutivas son irreconocibles se produce un corte de la señal (proceso soft blacked-out). Si
esto dura menos de 5 mseg es imperceptible para el oído humano.

1002-(8)
