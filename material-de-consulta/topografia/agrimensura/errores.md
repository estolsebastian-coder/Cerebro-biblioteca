---
type: libro
title: "errores"
author: "dblanco"
categoria: "TOPOGRAFÍA"
paginas: 4
extraccion: "texto"
fuente: "local:E:/MATERIAL DE CONSULTA/TOPOGRAFÍA/agrimensura/errores.pdf"
convertido: 2026-10-16
---

# errores

> Texto extraído de `TOPOGRAFÍA\agrimensura\errores.pdf` (4 páginas, texto). El PDF original está en el disco E: (MATERIAL DE CONSULTA); `<!-- p. N -->` marca el inicio de cada página.

<!-- p. 1 -->

FACULTAD DE INGENIERIA INSTITUTO DE AGRIMENSURA
DEPARTAMENTO DE GEODESIA

ERRORES EN EL POSICIONAMIENTO GPS

Examinaremos los errores que afectan a las medidas de distancia receptor – satélite hechas
por un único receptor estándar GPS. Veremos las causas de los errores y sus magnitudes
típicas.
La ecuación de observación para la seudodistancia que relaciona las medidas con los
diferentes componentes involucrados en la medición, puede escribirse como:

R = ρ + c ∆ δ + v

v denominado error de medición, puede escribirse explícitamente como la suma de una serie
de efectos debidos a la perturbación que sufre la señal en su recorrido, es decir, podemos
escribir:

v = Ι RS + TRS + d mRS + ε RS

donde: Ι RS es el retardo en distancia producido por la presencia de la ionosfera.
TRS retardo en distancia producido por la troposfera.
d mRS retardo en distancia producido por caminos múltiples que sufre la señal al llegar a
la
antena receptora.
S error intrínseco de la medición. ε R
Por lo tanto en forma explícita la ecuación de observación para la seudodistancia es:

R = ρ + c ∆δ + Ι RS + TRS + d mRS + ε RS

Generalmente se analiza la contribución de cada fuente particular de errores, en medida de sus
efectos en la determinación de distancias. El efecto combinado de todas las fuentes de error
proyectado en la línea satélite – receptor, se llama error de distancia equivalente de usuario
(User Equivalent Range Error (UERE)). Los receptores indican en pantalla el UERE de cada
satélite, informando sobre la exactitud de la observación actual.

ERROR DE EFEMERIDES

Las órbitas transmitidas de los satélites son una extrapolación temporal y esta es la principal
causa del error de efemérides. El efecto del error de efemérides en la medida de la
seudodistancia es obtenido proyectando el vector de error de posición del satélite en el vector
que une el satélite con el receptor. Dicho error es del orden de 1 a 3 metros.

ERROR DE LOS RELOJES

Los satélites GPS están equipados con relojes atómicos de muy alta tecnología y de gran
estabilidad. A pesar de ello el tiempo medido por estos relojes no es coincidente con el tiempo
del sistema GPS, por lo cual es necesario un continuo ajuste de los mismos. Para esto la
Estación de Control Maestro calcula para cada reloj de los satélites los coeficientes de
corrección del reloj. Estos son dados a través del mensaje de navegación del satélite. Después
que se aplica la corrección al reloj del satélite, el error residual estimado es de 10
nanosegundos o menos, esto produce un error en la determinación de la seudodistancia de
menos de 3 metros.
La desincronización del reloj del receptor se introduce como una nueva incógnita en la
resolución del posicionamiento.

<!-- p. 2 -->

FACULTAD DE INGENIERIA INSTITUTO DE AGRIMENSURA
DEPARTAMENTO DE GEODESIA

ERROR POR RETARDO IONOSFERICO Y TROPOSFERICO

Si las ondas electromagnéticas se propagasen en el vacío la distancia recorrida surgiría
simplemente del producto entre el tiempo de propagación entre el emisor y el receptor y la
velocidad de la luz en el vacío.
Sin embargo, cuando las señales atraviesan la atmósfera terrestre, la interacción entre el
campo electromagnético y los electrones libres, los átomos neutros y moléculas modifica tanto
la velocidad como la dirección de propagación, dando lugar al fenómeno conocido como
refracción atmosférica.
La ionosfera es la región de la atmósfera donde se encuentran electrones libres en suficiente
cantidad como para afectar la propagación de una onda electromagnética. Esta se extiende
desde los 50 km a los 1000 km aproximadamente.
Debido al efecto de la ionosfera la distancia medida utilizando los códigos GPS es más larga
que la distancia geométrica entre el receptor y el satélite. Este efecto puede alcanzar valores
de hasta 30 metros para un señal que se propaga zenitalmente y puede llegar a tres veces
mayor para una señal que se propaga cerca del horizonte.
El efecto de la ionosfera puede corregirse aplicando diversos modelos. Luego de aplicarlos
sobre las mediciones puede suceder en el peor de los casos que persista un error residual de 7
metros.

La troposfera es la región más baja de la atmósfera donde la temperatura decrece cuando
aumenta la altura. La presencia de átomos neutros y moléculas es lo que afecta la propagación
de la señal. Los errores encontrados del error troposférico total en la dirección cenital son del
orden de 2.3 a 2.6 metros.
El efecto de la troposfera es modelado mediante diversas funciones analíticas. Luego de
aplicar los modelos el error residual alcanza el de 1 a 2 centímetros dependiendo de las
condiciones atmosféricas.

MULTIPATH (ERROR DE MULTICAMINO)

Este error se produce cuando la antena del receptor recibe simultáneamente la señal del
satélite y un reflejo de la misma producido en algún objeto cercano (la superficie del terreno, un
vehículo, una persona, una construcción, etc.). Afecta tanto las mediciones de código como las
de la portadora. El efecto en las mediciones de código son mayores que en la fase de la
portadora.
El multipath produce tanto un aumento como una disminución en la medida de la
seudodistancia. Se han registrado medidas de multipath en código de alrededor de medio
metro en un medio despejado y de 4 o 5 metros en un medio con alta reflectividad.

<!-- p. 3 -->

FACULTAD DE INGENIERIA INSTITUTO DE AGRIMENSURA
DEPARTAMENTO DE GEODESIA

Este tipo de errores pueden ser reducidos eligiendo sitios de observación libres de superficies
reflectantes cercanas o utilizando antenas GPS especiales que incorporan un plano de tierra
(un disco circular metálico de aproximadamente 50cm de diámetro), el cual evita que las
señales con poca elevación lleguen a la antena. Para obtener la más alta exactitud, la solución
preferida es la antena de bobina anular (choke ring antenna). Una antena de bobina anular
tiene 4 o cinco anillos concéntricos alrededor de la antena que atrapan cualquier señal
indirecta.

ERROR DE MEDICION

Es el error intrínseco de cualquier error de medición electrónica y depende de la calidad del
receptor. Los errores en la determinación de la distancia utilizando el código C/A son
aproximadamente 100 veces mayores que utilizando la portadora.

DISPONIBILIDAD SELECTIVA Y ANTI - SPOOFING

El Departamento de Defensa de los Estados Unidos estableció una política para degradar
intencionalmente la exactitud del sistema si es usado por personas no autorizadas. Esto se
lleva a cabo a través de dos acciones:

a) La disponibilidad selectiva (SA). La misma consiste en una degradación intencional en las
efemérides transmitidas y en el reloj del satélite lo que impone una limitación en la precisión del
posicionamiento aislado (un solo receptor). Este efecto es parte del Servicio de
Posicionamiento Estándar (SPS).
En esta condiciones el SPS provee una precisión de 100 metros en las coordenadas
horizontales durante el 95% del tiempo.
Afortunadamente, la SA fue desactivada en mayo de 2000, y la precisión mejoró
sustancialmente. La mayor parte del tiempo, los errores en Latitud y Longitud son del orden de
los
3 m aunque pueden llegar a los 10 m y excepcionalmente algo más.
No obstante la activación es una decisión unilateral de los EEUU.

b) El Anti – spoofing (AS), que es la encriptación del código P, impide el acceso directo al
mismo. La forma de acceder al mismo depende de la calidad del receptor.

GEOMETRÍA DE LOS SATELITES Y MEDIDAS DE LA EXACTITUD

La exactitud del posicionamiento absoluto GPS depende de dos factores:

La exactitud de una sola medición de seudodistancias, expresada por el error de distancia
equivalente de usuario (UERE).
La configuración de los satélites usados.

La geometría de los satélites visibles en un posicionamiento es muy importante para obtener
resultados de alta calidad. Al número que se relaciona con esta geometría se lo denomina
Factor de Dilución de la Precisión (DOP). Está relacionado con la distancia entre los satélites y
su posición en el cielo.

<!-- p. 4 -->

FACULTAD DE INGENIERIA INSTITUTO DE AGRIMENSURA
DEPARTAMENTO DE GEODESIA

Si interpretamos el efecto de la dilución geométrica en dos dimensiones, se tiene que para
satélites muy cercanos, los círculos que definen la posición del receptor se cruzan de tal
manera que el área de error en torno a la posición crece enormemente.

Si en cambio los satélites se encuentran lo suficientemente separados, el ángulo al que se
cruzan los círculos que definen la posición, es casi recto y por lo tanto el área de error es
mínima.

Este razonamiento que acabamos de describir, puede extenderse para el caso real en tres
dimensiones, donde en vez de tratar con círculos y áreas de error trataremos con esferas y
volúmenes de error.
Por lo tanto se tiene que el posicionamiento puntual es más preciso cuando los satélites tienen
una buena distribución espacial en el cielo.

Se pueden calcular diferentes tipos de Dilución de la Precisión:

VDOP: Dilución Vertical de la Precisión. Proporciona la degradación de la exactitud en la
dirección vertical.
HDOP: Dilución Horizontal de la Precisión. Proporciona la degradación de la exactitud en la
dirección horizontal.
PDOP: Dilución de la Precisión en Posición. Proporciona la degradación de la exactitud en
posición 3D.
GDOP: Dilución de la Precisión Geométrica. Proporciona la degradación de la exactitud en
posición 3D y en tiempo.

El PDOP se puede interpretar como el valor recíproco del volumen V del tetraedro conformado
por el satélite y las posiciones del usuario:
1
PDOP =
V

Los DOP multiplicados por todos los errores involucrados en el posicionamiento puntual nos
dan una estimación de la precisión en el posicionamiento.
Cuanto más bajo sea el valor de los DOP mejor será el posicionamiento con GPS. Un PDOP
de 5 a 6 es el valor límite que se recomienda generalmente. Existen softwares que calculan el
valor de los DOP previo a la observación.

La relación entre el UERE y la desviación estándar asociada del posicionamiento esta descrita
de la siguiente manera:
σ = DOP × UERE

Dependiendo del DOP usado se obtiene la desviación correspondiente.
