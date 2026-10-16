---
type: libro
title: "analisis_tanque_de_agua"
author: "Administrador"
categoria: "ESTRUCTURA"
paginas: 76
extraccion: "texto"
fuente: "local:E:/MATERIAL DE CONSULTA/ESTRUCTURA/ESTRUCTURAS NO CONVENCIONALES/analisis_tanque_de_agua.pdf"
convertido: 2026-10-16
---

# analisis_tanque_de_agua

> Texto extraído de `ESTRUCTURA\ESTRUCTURAS NO CONVENCIONALES\analisis_tanque_de_agua.pdf` (76 páginas, texto). El PDF original está en el disco E: (MATERIAL DE CONSULTA); `<!-- p. N -->` marca el inicio de cada página.

<!-- p. 1 -->

ANÁLISIS HIDRODINÁMICO DE TANQUES DE

ALMACENAMIENTO DE LÍQUIDOS

CÉSAR A. VELÁSQUEZ

UNIVERSIDAD DE LOS ANDES

FACULTAD DE INGENIERÍA
DEPARTAMENTO DE INGENIERÍA CIVIL Y AMBIENTAL
SANTA FE DE BOGOTA

<!-- p. 2 -->

ANÁLISIS HIDRODINÁMICO DE TANQUES DE

ALMACENAMIENTO DE LÍQUIDOS

CÉSAR A. VELÁSQUEZ

Tesis para optar al título de
Magíster en Ingeniería Civil

Director:
LUÍS EDUARDO YAMÍN LACOUTURE

Ingeniero Civil – MSc.

UNIVERSIDAD DE LOS ANDES
FACULTAD DE INGENIERÍA
DEPARTAMENTO DE INGENIERÍA CIVIL Y AMBIENTAL

SANTA FE DE BOGOTA

<!-- p. 3 -->

César A. Velásquez ANÁLISIS HIDRODINÁMICO DE TANQUES DE ALMACENAMIENTO DE LÍQUIDOS
MIC 2004-I-80

Bogotá D.C., Julio 12 de 2004

Doctor

MAURICIO SILVA
Director Departamento de Ingeniería Civil y Ambiental
Facultad de Ingeniería
Universidad de los Andes

Respetado Doctor:

Mediante esta deseo presentar el proyecto de grado “ANÁLISIS HIDRODINÁMICO DE TANQUES

DE ALMACENAMIENTO DE LÍQUIDOS”, para cumplir con los requisitos pendientes establecidos

por la Universidad de los Andes para optar al título de Magíster en Ingeniería Civil con especialización

en el área de Estructuras y Sísmica.

Cordialmente

____________________________

ING. CESAR A. VELASQUEZ.

Mayo/2004 ii

<!-- p. 4 -->

César A. Velásquez ANÁLISIS HIDRODINÁMICO DE TANQUES DE ALMACENAMIENTO DE LÍQUIDOS
MIC 2004-I-80

A Todas aquellas personas que al conocer han marcado

Mi vida, con su amor, amistad y su confianza.

Especialmente a Dios, a mis padres, hermanos y a mi familia

A ambas la que he tenido y tendré siempre en Manizales

Y la que tengo ahora en Bogotá

Mayo/2004 iii

<!-- p. 5 -->

César A. Velásquez ANÁLISIS HIDRODINÁMICO DE TANQUES DE ALMACENAMIENTO DE LÍQUIDOS
MIC 2004-I-80

AGRADECIMIENTOS

Deseo expresar mi gratitud y admiración al Ingeniero Juan Carlos Reyes por sus

valiosos aportes al desarrollo de esta investigación.

Agradezco al Ingeniero Camilo Phillips por valiosos conocimientos y conceptos.

Agradezco al Dr. Luis E. Yamín por su apoyo durante la realización de este trabajo.

Finalmente agradezco a la empresa Ingeniería Técnica y Científica Limitada por

abrirme las puertas y brindarme completa colaboración y por el material prestado.

Mayo/2004 iv

<!-- p. 6 -->

César A. Velásquez ANÁLISIS HIDRODINÁMICO DE TANQUES DE ALMACENAMIENTO DE LÍQUIDOS
MIC 2004-I-80

RESUMEN

Constantemente estamos expuestos a un sin numero de “catástrofes” generadas por la naturaleza, la

cual solo sigue su curso y fluye en continuo cambio, pero que debido a la manipulación que hacemos

de esta para amoldarla a nuestras necesidades y no por el contrario acomodarnos a su comportamiento

termina teniendo consecuencias funestas por todo el mundo. Siendo una evidencia de esto los

movimientos sísmicos, es por esto que se hace necesario explorar metodologías de análisis que

permitan determinar el nivel de sobreesfuerzos ocasionados por estos movimientos del terreno sobre

las estructuras nuevas u existentes y la mejor forma de intervenirla en caso de que no se cumplan los

estándares y requisitos mínimos de seguridad.

Mediante la mezcla de la teoría y la tecnología actual se facilita el estudio y la predicción de los efectos

que se pueden presentar en una estructura debido al movimiento del terreno; mediante el empleo de

análisis espectrales o cronológicos se puede analizar y determinar el comportamiento de los diferentes

componentes de la estructura y la influencia que sobre estos ejerce el sismo.

Mediante el análisis de estructuras existentes se puede esperar corroborar, refutar o mejorar la teoría

existente referente al análisis de tanques después de un sismo y de verificar el estado y el desempeño

de estos durante la ocurrencia del evento. Se deben proponer metodologías de procedimiento que sean

prácticas y simples para la realización de una estructura nueva, y que tengan un mínimo impacto a

nivel arquitectónico, funcional y económico cuando se trate de una rehabilitación.

En el presente trabajo se presenta la teoría actual referente al análisis de tanques de almacenamiento de

líquidos y esta se emplea de forma que mediante un programa de computador se pueda aplicar a un

modelo realizado para el laboratorio y en la realización de un ejemplo de diseño en el cual se muestra

lo importante que es considerar estos efectos.

Mayo/2004 v

<!-- p. 7 -->

César A. Velásquez ANÁLISIS HIDRODINÁMICO DE TANQUES DE ALMACENAMIENTO DE LÍQUIDOS
MIC 2004-I-80

TABLA DE CONTENIDO

\1. Introducción ........................................................................................................................... 1-1

1.1. OBJETIVO GENERAL.................................................................................................... 1-3

1.2. OBJETIVOS ESPECÍFICOS............................................................................................ 1-3

1.3. ALCANCE....................................................................................................................... 1-3

1.4. TIPOS DE TANQUES ..................................................................................................... 1-4

1.5. MATERIALES................................................................................................................. 1-9

1.5.1. CONCRETO............................................................................................................. 1-9

1.5.2. ACERO .................................................................................................................. 1-11

1.6. VULNERABILIDADES TÍPICAS................................................................................. 1-12

\2. Marco Teórico ........................................................................................................................ 2-1

2.1. ANÁLISIS HIDROSTÁTICO.......................................................................................... 2-1

2.1.1. ANÁLISIS................................................................................................................ 2-1

2.1.2. DISEÑO................................................................................................................... 2-2

2.2. ANÁLISIS HIDRODINÁMICO....................................................................................... 2-2

2.2.1. RELACIONES TEÓRICAS...................................................................................... 2-2

2.2.2. RELACIONES EMPÍRICAS.................................................................................... 2-5

2.2.3. TEORÍAS DE FALLA.............................................................................................. 2-6

2.2.3.1. Teoría de Rankine ............................................................................................. 2-6

2.2.3.2. Teoría de Tresca................................................................................................ 2-7

2.3. CHEQUEOS .................................................................................................................... 2-8

2.3.1. RESISTENCIA AL VUELCO .................................................................................. 2-8

2.3.2. COMPRESIÓN DE LA PARED DEL TANQUE...................................................... 2-9

2.3.2.1. Fuerza actuante en tanques no anclados ............................................................. 2-9

2.3.2.2. Fuerza actuante en tanques anclados.................................................................. 2-9

2.3.2.3. Máxima compresión admisible ........................................................................ 2-10

2.3.3. LAMINAS SUPERIORES DE LA PARED DEL TANQUE ................................... 2-10

Mayo/2004 vi

<!-- p. 8 -->

César A. Velásquez ANÁLISIS HIDRODINÁMICO DE TANQUES DE ALMACENAMIENTO DE LÍQUIDOS
MIC 2004-I-80

\3. Estudio Experimental............................................................................................................. 3-1

3.1. DESCRIPCIÓN DEL MODELO...................................................................................... 3-1

3.2. MODELO EXPERIMENTAL .......................................................................................... 3-3

3.3. DESCRIPCIÓN DEL ENSAYO....................................................................................... 3-4

3.4. RESULTADOS DEL EXPERIMENTO............................................................................ 3-6

3.4.1. Primera Etapa ........................................................................................................... 3-6

3.4.2. Segunda Etapa .......................................................................................................... 3-7

3.5. MODELO TEÓRICO....................................................................................................... 3-8

3.5.1. Modelo con Elementos Finitos .................................................................................. 3-8

\4. Metodología para análisis dinámico ...................................................................................... 4-1

4.1. Información requerida....................................................................................................... 4-1

4.2. Modelo de Análisis........................................................................................................... 4-1

4.3. Cargas .............................................................................................................................. 4-3
• Carga Muerta.................................................................................................................... 4-3
• Carga Viva ....................................................................................................................... 4-3

• Carga Hidrostática............................................................................................................ 4-3
• Carga Sísmica................................................................................................................... 4-3
• Carga Dinámica (Formulación de Housner) ...................................................................... 4-4
• Combinación de Carga...................................................................................................... 4-4

4.4. Resultados ........................................................................................................................ 4-4
• Periodos y Modos de Vibración ........................................................................................ 4-4
• Esfuerzos en la pared del tanque ....................................................................................... 4-4
• Revisiones ........................................................................................................................ 4-5

\5. Caso de Estudio ...................................................................................................................... 5-1

5.1. DISEÑO HIDROSTÁTICO.............................................................................................. 5-1

5.2. DISEÑO HIDRODINÁMICO .......................................................................................... 5-5

5.2.1. MODELO DE ANÁLISIS ........................................................................................ 5-5

5.2.2. CARGAS.................................................................................................................. 5-6

5.2.2.1. Carga Muerta .................................................................................................... 5-6

5.2.2.2. Carga Hidrostática............................................................................................. 5-6

5.2.2.3. Espectro de diseño............................................................................................. 5-7

5.2.2.4. Carga Dinámica (Formulación de Housner)....................................................... 5-7

5.2.3. COMBINACIÓN DE CARGA ................................................................................. 5-8

Mayo/2004 vii

<!-- p. 9 -->

César A. Velásquez ANÁLISIS HIDRODINÁMICO DE TANQUES DE ALMACENAMIENTO DE LÍQUIDOS
MIC 2004-I-80

5.2.4. RESULTADOS ........................................................................................................ 5-9

5.2.4.1. Periodos y Modos de Vibración......................................................................... 5-9

5.2.4.2. Esfuerzos en la pared del tanque...................................................................... 5-11

5.2.4.3. Variación de los esfuerzos en la pared ............................................................. 5-14

5.2.4.4. Chequeos y revisiones ..................................................................................... 5-15

\6. Observaciones y recomendaciones......................................................................................... 6-1

\7. Bibliografía............................................................................................................................. 7-1

Mayo/2004 viii

<!-- p. 10 -->

César A. Velásquez ANÁLISIS HIDRODINÁMICO DE TANQUES DE ALMACENAMIENTO DE LÍQUIDOS
MIC 2004-I-80

TABLA DE FIGURAS

Figura 1-1 Relación económica de diseño......................................................................................... 1-2

Figura 1-2 Tanque Enterrado, sistema de acueducto de Bogotá......................................................... 1-4

Figura 1-3 Tanque Superficial, Acueducto de Bogotá....................................................................... 1-5

Figura 1-4 Tanque Elevado, Acueducto de Manizales ...................................................................... 1-5

Figura 1-5 Tanques a presión ........................................................................................................... 1-6

Figura 1-6 Tanque a presión atmosférica, Ecopetrol ......................................................................... 1-6

Figura 1-7 Tanque Paralelepípedo, Acueducto de Bogotá................................................................. 1-7

Figura 1-8 Tanque Cilíndrico, Ecopetrol .......................................................................................... 1-7

Figura 1-9 Tanque Vertical, Ecopetrol.............................................................................................. 1-8

Figura 1-10 Tanque Horizontal ........................................................................................................ 1-8

Figura 1-11. Curva esfuerzo vs deformación del concreto.............................................................. 1-10

Figura 1-12. Modelo esfuerzo-deformación del concreto confinado [Modelo de Mander] .............. 1-11

Figura 1-13. Curva típica esfuerzo – deformación del acero [Modelo de Park Modificado]............ 1-12

Figura 1-14 Falla por compresión, “Pata de Elefante”..................................................................... 1-13

Figura 1-15 Falla por compresión, “Forma de Diamante”............................................................... 1-13

Figura 1-16 Falla en la zona superior debido al oleaje .................................................................... 1-14

Figura 1-17 Falla en los elementos de conexión perimetrales.......................................................... 1-14

Figura 2-1 Modelo Análogo de Housner........................................................................................... 2-2

Figura 2-2 Masas dinámicas del líquido ........................................................................................... 2-4

Figura 2-3 Altura de la masa dinámica ............................................................................................. 2-4

Figura 2-4 Criterio de Falla de Rankine............................................................................................ 2-7

Figura 2-5 Criterio de Falla de Tresca .............................................................................................. 2-7

Figura 3-1. Modelo Construido ........................................................................................................ 3-2

Figura 3-2. Modelo Construido ........................................................................................................ 3-2

Figura 3-3. Modelo experimental – Prueba Hidrostática .................................................................. 3-3

Figura 3-4. Mesa Vibratoria. CIMOC Uniandes. ............................................................................. 3-4

Mayo/2004 ix

<!-- p. 11 -->

César A. Velásquez ANÁLISIS HIDRODINÁMICO DE TANQUES DE ALMACENAMIENTO DE LÍQUIDOS
MIC 2004-I-80

Figura 3-5. Ciclos de desplazamiento ............................................................................................... 3-5

Figura 3-6. Espectro de Respuesta de la Señal empleada .................................................................. 3-5

Figura 3-7. Señal Empleada ............................................................................................................. 3-6

Figura 3-8. Altura Alcanzada ........................................................................................................... 3-6

Figura 3-9. Movimiento del líquido.................................................................................................. 3-7

Figura 3-10. Respuesta obtenida en el Strain Gage No1.................................................................... 3-8

Figura 3-11. Malla de elementos finitos............................................................................................ 3-9

Figura 3-12. Patrón de Carga Hidrostática (kg/cm²)........................................................................ 3-10

Figura 3-13. Respuesta obtenida en el modelo................................................................................ 3-10

Figura 3-14. Comparación de Deformación por carga Hidrostática ................................................ 3-11

Figura 3-15. Comparación de Deformación por análisis dinámico sentido positivo ......................... 3-12

Figura 3-16. Comparación de Deformación por análisis dinámico sentido negativo ........................ 3-12

Figura 4-1 Modelo de Housner........................................................................................................ 4-4

Figura 5-1 Esquema de disposición de la cubierta............................................................................. 5-4

Figura 5-2 Vista del Modelo............................................................................................................. 5-5

Figura 5-3 Corte del modelo tridimensional desarrollado.................................................................. 5-5

Figura 5-4 Condiciones de borde del Modelo .................................................................................. 5-6

Figura 5-5 Carga Hidrostática Ton/m² .............................................................................................. 5-6

Figura 5-6 Espectro de Diseño ......................................................................................................... 5-7

Figura 5-7 Modelo de Housner........................................................................................................ 5-8

Figura 5-8 Modos Fundamentales del tanque................................................................................. 5-10

Figura 5-9 Esfuerzos para carga gravitacional ............................................................................... 5-11

Figura 5-10 Esfuerzos para presión hidrostática............................................................................. 5-12

Figura 5-11 Esfuerzos para sismo.................................................................................................. 5-13

Figura 5-12 Líneas de verificación de esfuerzos máximos ............................................................. 5-14

Figura 6-1. Comparación de un espectro típico a diferentes niveles de amortiguamiento................... 6-2

Figura 6-2. Espectro de diseño compuesto........................................................................................ 6-2

Mayo/2004 x

<!-- p. 12 -->

\1. Introducción

Para el almacenamiento de líquidos, el uso de tanques es el sistema mas empleado alrededor de todo el

mundo. Para el diseño de estas estructuras por lo general se emplean métodos simplificados, bien sea

mediante tablas en los cuales se presentan coeficientes de esfuerzo según las relaciones geométricas o

mediante la realización de modelos de computador simples que permitan conocer de manera muy

aproximada a al realidad la situación de esfuerzos en los limites del tanque. El diseño ante eventos

sísmicos se realiza mediante el empleo de ecuaciones simples obtenidas de la experiencia en sismos

previos del desempeño observado de los tanques afectados.

Este diseño simplificado usado por organismos internacionales en sus estandares, como el API y la
AWWA1, específicamente las normas API650 y AWWA D100. Este análisis se basa principalmente en
estudios anteriores2 un poco mas desarrollados para considerar en la ecuación mas parámetros del

tanque, en este análisis se evalúa la fuerza lateral y el momento volcante de manera global; Para estas

normas el efecto en las paredes se realiza en base a relaciones de espesor y otros parámetros de la

geometría del tanque los cuales son comparados contra relaciones que funcionaron en sismos
anteriores. Recientemente esfuerzos de otros ingenieros3 han permitido considerar otros efectos como

la interacción suelo estructura.

Aunque desde antes4 de 1954 se han adelantado estudios que permitan cuantificar y evaluar de manera

mas precisa los efectos de un sismo sobre las paredes del tanque, no ha sido posible sino hasta hace

1 API ese el acrónimo para American Petroleum Institute, AWWA lo es para American Water Works Association.
2 La ecuación para evaluar la fuerza del sismo se basa en el desarrollo de G. W. Housner realizado en 1954.
3 El mas representativo de estos es Anestides Velettsos
4 Aunque no se pudo conseguir bibliografía anterior a 1954 para el desarrollo de esta tesis, diversos documentos de la BSSA e

incluso el reporte mencionado hacen referencia a documentos que datan de 1949.

<!-- p. 13 -->

César A. Velásquez ANÁLISIS HIDRODINÁMICO DE TANQUES DE ALMACENAMIENTO DE LÍQUIDOS
MIC 2004-I-80

pocos años involucrar dichos estudios en la realización de modelos de computador. Esto con el fin de

poder evaluar los efectos generados de una manera más detallada y precisa.

A pesar de las capacidades computacionales actuales, la inelasticidad se tiene en cuenta reduciendo la

demanda sísmica usando coeficientes de reducción de carga R relacionados con la capacidad de

disipación de energía.

El fin del diseño estructural es garantizar la seguridad y funcionalidad de las estructuras al mismo

tiempo que se tiene en cuenta los efectos económicos, logrando así un punto de equilibrio Figura 1-1.

Sobre esta base se deben explorar técnicas de análisis que permitan optimizar el diseño y hacer un uso

completo de los materiales

NivelNivel óptimoóptimo dede diseñodiseño desdedesde elel puntopunto dede
vistavista económicoeconómico

CostosCostos

NivelNivel dede DiseñoDiseño

PerdidaPerdida EsperadaEsperada CostoCosto InicialInicial CostoCosto TotalTotal

Figura 1-1 Relación económica de diseño

Es importante destacar que, aún cuando se habla de tanques de almacenamiento, generalmente se

piensa en empresas petroleras y en los tanques en los cuales estas almacenan hidrocarburos, también

existen en la mayoría de ciudades tanques donde se almacena agua potable y hacen parte del sistema

principal de distribución de agua para las ciudades, tanto para consumo como para el sistema contra

incendios, por lo tanto en un evento sísmico que llegue a comprometer la estabilidad o el

funcionamiento integro de estas estructuras debe verse como una catástrofe.

Mayo/2004 Capitulo 1 - Introducción 1-2

<!-- p. 14 -->

César A. Velásquez ANÁLISIS HIDRODINÁMICO DE TANQUES DE ALMACENAMIENTO DE LÍQUIDOS
MIC 2004-I-80

1.1. OBJETIVO GENERAL

El objetivo general de esta investigación es indagar en las diferentes metodologías de análisis y diseño

de tanques circulares de almacenamiento.

1.2. OBJETIVOS ESPECÍFICOS

Los objetivos específicos de esta investigación son:

• Recolectar y analizar la información existente sobre modelación inelástica de tanques de

almacenamiento para tener una aproximación al estado del arte en el tema.

• Investigar, evaluar y seleccionar los modelos matemáticos existentes utilizados en el diseño.

• Comparar las metodologías de análisis (simplificada y dinámica) utilizadas en cuanto a semejanza

de los resultados, esfuerzo computacional y descripción del comportamiento.

• Desarrollar un modelo experimental a escala para efectuar una medición de esfuerzos actuantes.

1.3. ALCANCE

El alcance de esta investigación se limita a los lineamientos mencionados a continuación:
• El análisis realizado se limita solo a tanques cilíndricos metálicos.
• El modelo se realizara utilizando elementos planos tipo “shell” y elementos tipo “frame”.
• El modelo computacional que se realice será evaluado según la metodología del espectro de

respuesta y la metodología de análisis cronológico.
• En el presente estudio no se realizará modelamiento detallado del suelo. En todos los casos se

supondrá empotramiento en la base.
• Se ensayara el modelo experimental según las capacidades de los equipos actuales del laboratorio

de la universidad de los andes.
• En ningún caso se llevara a condiciones últimas o de falla el modelo experimental.

Mayo/2004 Capitulo 1 - Introducción 1-3

<!-- p. 15 -->

César A. Velásquez ANÁLISIS HIDRODINÁMICO DE TANQUES DE ALMACENAMIENTO DE LÍQUIDOS
MIC 2004-I-80

1.4. TIPOS DE TANQUES

Los tanques se pueden clasificar de diversas formas dependiendo alguna característica de estos.

Por Altura:

• Enterrados

Figura 1-2 Tanque Enterrado, sistema de acueducto de Bogotá

Mayo/2004 Capitulo 1 - Introducción 1-4

<!-- p. 16 -->

César A. Velásquez ANÁLISIS HIDRODINÁMICO DE TANQUES DE ALMACENAMIENTO DE LÍQUIDOS
MIC 2004-I-80

• Superficiales

Figura 1-3 Tanque Superficial, Acueducto de Bogotá

• Elevados

Figura 1-4 Tanque Elevado, Acueducto de Manizales

Mayo/2004 Capitulo 1 - Introducción 1-5

<!-- p. 17 -->

César A. Velásquez ANÁLISIS HIDRODINÁMICO DE TANQUES DE ALMACENAMIENTO DE LÍQUIDOS
MIC 2004-I-80

Por Presión de trabajo
• A Presión de confinamiento.

Figura 1-5 Tanques a presión, tomado del sitio en internet de

FG Industrial Access & Maintenance Services BV

• A Presión atmosférica.

Figura 1-6 Tanque a presión atmosférica, Ecopetrol

Mayo/2004 Capitulo 1 - Introducción 1-6

<!-- p. 18 -->

César A. Velásquez ANÁLISIS HIDRODINÁMICO DE TANQUES DE ALMACENAMIENTO DE LÍQUIDOS
MIC 2004-I-80

Por Forma:
• Paralelepípedos

Figura 1-7 Tanque Paralelepípedo, Acueducto de Bogotá

• Cilíndricos

Figura 1-8 Tanque Cilíndrico, Ecopetrol

• Esféricos, ver Figura 1-5

Mayo/2004 Capitulo 1 - Introducción 1-7

<!-- p. 19 -->

César A. Velásquez ANÁLISIS HIDRODINÁMICO DE TANQUES DE ALMACENAMIENTO DE LÍQUIDOS
MIC 2004-I-80

Por Orientación
• Vertical

Figura 1-9 Tanque Vertical, Ecopetrol

• Horizontal

Figura 1-10 Tanque Horizontal, tomado del sitio en Internet

http://www.state.sd.us/denr/DES/Ground/tanks/

Mayo/2004 Capitulo 1 - Introducción 1-8

<!-- p. 20 -->

César A. Velásquez ANÁLISIS HIDRODINÁMICO DE TANQUES DE ALMACENAMIENTO DE LÍQUIDOS
MIC 2004-I-80

Por Material
• Concreto, ver Figura 1-7
• Acero, ver Figura 1-3
• Otros Metales
• Plásticos, ver Figura 1-11

Tipo de cimentación
• Anclados
• No Anclados

1.5. MATERIALES

1.5.1. CONCRETO

El concreto hidráulico es una roca fabricada por el hombre, en este se realiza una mezcla de cemento,

agregados y agua, los cuales en las proporciones adecuadas producen un material durable, resistente y

económico. La principal característica del concreto es su alta resistencia a la compresión, la cual varía

normalmente entre los 21 MPa hasta los 42 MPa. En general el concreto posee buena resistencia a la

humedad, a la oxidación, al fuego y al desgaste. Su principal desventaja es su baja resistencia a

tensión.

Las principales propiedades del concreto usadas en la ingeniería civil para el diseño con concreto son

el Modulo de Elasticidad, la Resistencia a la Compresión, la Densidad y el Coeficiente de Poisson.

Estas características se pueden obtener fácilmente en laboratorio, pero esto es una vez se esta en el

proceso de construcción, para el proceso de diseño se requiere entonces usar tablas o ecuaciones que

permitan suponer un valor cercano al que se obtendrá.

El proceso normal es suponer un valor de resistencia a la compresión del concreto, f´c y en base a este

valor calcular las demás propiedades según relaciones obtenidas estadísticamente para los materiales

de la región.

Mayo/2004 Capitulo 1 - Introducción 1-9

<!-- p. 21 -->

César A. Velásquez ANÁLISIS HIDRODINÁMICO DE TANQUES DE ALMACENAMIENTO DE LÍQUIDOS
MIC 2004-I-80

En una curva esfuerzo deformación del concreto, como la que se presenta en la Figura 1-11, se calcula

el modulo de elasticidad Ec, como la pendiente de la recta que une el origen con un punto ubicado entre
0.3f´c y 0.4f´c.

Figura 1-11. Curva esfuerzo vs deformación del concreto

En la Norma Sismo Resistente Colombiana se establece la siguiente ecuación para determinar el valor

medio de modulo de elasticidad en función de la resistencia a la compresión, f´c:

E c = 3 900 f ´ c [MPa ]

Si al concreto se restringe a una deformación lateral, como puede ser el uso de estribos de acero, el

comportamiento presenta una completa variación. El efecto del refuerzo trasversal sobre la sección es

equivalente a aplicar una presión lateral que impida la expansión y la dispersión de las partículas del

núcleo produciendo un notorio aumento en la capacidad al esfuerzo como de deformación. El

confinamiento incrementa la resistencia a la compresión así como la capacidad de deformación, Figura

1-12.

1Mayo/2004 Capitulo 1 - Introducción
10

<!-- p. 22 -->

César A. Velásquez ANÁLISIS HIDRODINÁMICO DE TANQUES DE ALMACENAMIENTO DE LÍQUIDOS
MIC 2004-I-80

f'cc

f'c
Esfuerzo Concreto Inconfinado
Concreto Confinado

0 0.002 0.004 0.006 0.008 0.01 0.012 0.014 0.016 0.018 0.02

Deformación unitaria

Figura 1-12. Modelo esfuerzo-deformación del concreto confinado [Modelo de Mander]

1.5.2. ACERO

Los aceros pueden ser catalogados según su composición química, de la cual dependen todas sus

propiedades de resistencia y ductilidad, es así como dependiendo el porcentaje de carbono y otras

sustancias como manganeso, silicio y otras se tiene mas o menos resistencia, ductilidad, resistencia a la

corrosión u otros factores que son determinantes para escoger el mas adecuado para determinada

función. La prueba típica que se realiza al acero es el ensayo de tensión o tracción directa, a partir del

cual se obtiene una curva esfuerzo – deformación como la mostrada en la Figura 1-13. Esta grafica es

diferente según el acero que se este ensayando. Sin embargo, esta se caracteriza por presentar una zona

elástica hasta un valor de esfuerzo (esfuerzo de fluencia), a partir de este punto se aumenta la

deformación del material permaneciendo constante el nivel de esfuerzo, luego se llega a un punto en el

cual el esfuerzo vuelve a incrementarse, esta etapa se conoce como endurecimiento por deformación,

esta empieza con una relación diferente a la inicial y va decayendo hasta llegar al máximo esfuerzo, a

partir de este punto empieza a decaer hasta que se presenta la fractura.

1Mayo/2004 Capitulo 1 - Introducción
11

<!-- p. 23 -->

César A. Velásquez ANÁLISIS HIDRODINÁMICO DE TANQUES DE ALMACENAMIENTO DE LÍQUIDOS
MIC 2004-I-80

fu

Esfuerzo fy

0 0.02 0.04 0.06 0.08 0.1 0.12 0.14 0.16 0.18
Deformación

Figura 1-13. Curva típica esfuerzo – deformación del acero [Modelo de Park Modificado]

En la norma API-650 se establecen diversos tipos de aceros permitidos para la construcción de tanques,

con cierta variación especifica respecto a los estándares ASTM, CSA e ISO. También se establecen los

valores máximos permitidos de materiales adicionales que se pueden encontrar en el acero a emplear.

1.6. VULNERABILIDADES TÍPICAS

Las diferentes fallas que se pueden presentar en los tanques de almacenamiento tienen grandes

implicaciones tanto económicas como sociales, ya que aunque no se llegue hasta la perdida total de la

estructura, el solo daño en las líneas de conducción puede dejar la instalación fuera de funcionamiento

con lo cual no se tiene acceso al contenido del tanque, lo cual en el caso de las petroleras genera un

paro en esta actividad económica lo cual deja grandes perdidas para la sociedad, por otra parte el caso

de los sistemas de acueducto metropolitanos, este tipo de falla puede dejar sin agua potable a la

población en el momento que mas la requiere, tanto para consumo como para uso en el combate de

incendios. En el caso en el que se presente una falla total del tanque los efectos son aun mas nocivos,

dados los daños que pueden causar los materiales contenidos, los cuales pueden provocar nubes

toxicas, incendios, inundaciones y otras calamidades.

1Mayo/2004 Capitulo 1 - Introducción
12

<!-- p. 24 -->

César A. Velásquez ANÁLISIS HIDRODINÁMICO DE TANQUES DE ALMACENAMIENTO DE LÍQUIDOS
MIC 2004-I-80

• Las fuerzas laterales del sismo producen un momento volcante, el cual unido a las fuerzas

longitudinales de compresión a lo largo de las paredes del tanque, generan altos esfuerzos en la

zona inferior cerca de la base, lo cual puede ocasionar un abultamiento exterior, conocido como

“Pata de Elefante” o hacia el interior conocido como “Forma de Diamante”.

Figura 1-14 Falla por compresión, “Pata de Elefante”,

tomado del archivo electrónico “Simple design”

Figura 1-15 Falla por compresión, “Forma de Diamante”,

Tomado de la tesis de A. Zeiny de la “University of California” disponible “online”

1Mayo/2004 Capitulo 1 - Introducción
13

<!-- p. 25 -->

César A. Velásquez ANÁLISIS HIDRODINÁMICO DE TANQUES DE ALMACENAMIENTO DE LÍQUIDOS
MIC 2004-I-80

• El oleaje del líquido contenido puede generar pandeo en las cubiertas o en la parte superior de las

paredes, también puede ocasionar la falla de las columnas de soporte de la cubierta interiores.

Figura 1-16 Falla en la zona superior debido al oleaje,

Tomado de los archivos electrónicos “Effects of nonlinear geometric …” y “Simple Design”

Respectivamente

• El movimiento del tanque puede ocasionar la falla en los elementos de conexión perimetrales

Figura 1-17 Falla en los elementos de conexión perimetrales,

Tomado del sitio en Internet “http://www.eqe.co.uk/”

1Mayo/2004 Capitulo 1 - Introducción
14

<!-- p. 26 -->

César A. Velásquez ANÁLISIS HIDRODINÁMICO DE TANQUES DE ALMACENAMIENTO DE LÍQUIDOS
MIC 2004-I-80

• Fallas del suelo pueden ocasionar asentamientos diferenciales. Las fallas del suelo pueden ser por

licuefacción, sobreesfuerzos por redistribución de cargas, lavado de material de soporte por

rupturas de las tuberías perimetrales del tanque.

• Altos desplazamientos verticales de las paredes del tanque generan grandes esfuerzos en la base

cerca de la pared del tanque. Esto puede ocasionar una fluencia del material de la base generando

una ruptura y una perdida de contenido.

1Mayo/2004 Capitulo 1 - Introducción
15

<!-- p. 27 -->

\2. Marco Teórico

2.1. ANÁLISIS HIDROSTÁTICO

2.1.1. ANÁLISIS

Para el análisis de los efectos hidrostáticos sobre las paredes del tanque, los ingenieros cuentan con

varias herramientas, las cuales según la forma de este son mas o menos complejas, así para un tanque

cilíndrico se tienen pequeñas ecuaciones que permiten obtener en relación a el diámetro y a la altura
del liquido almacenado, la presión actuante o directamente el espesor requerido5. Para un tanque

rectangular, dada la complejidad de los momentos en las zonas de las esquinas se tienen tablas que en

función a la relación de los lados y la altura del líquido dan como resultado unos coeficientes que

permiten suponer de manera conservadora los esfuerzos actuantes.

Otra forma de aproximarse a la solución es mediante el uso de programas de computador que tengan

implementados elementos finitos adecuados para tal fin, mediante los cuales se puede suponer una

respuesta mucho mas adecuada y precisa al problema.

Cualquiera sea el camino escogido se deberá tener presente ciertos valores mínimos que exigen las

normas y códigos internacionales para el diseño de este tipo de estructuras; además del valor limite que

se pone a la resistencia de los materiales empleados, según sea el factor de seguridad que se requiera en

cada instalación.

5 Se tomo como referencia el codigo API 650

<!-- p. 28 -->

César A. Velásquez ANÁLISIS HIDRODINÁMICO DE TANQUES DE ALMACENAMIENTO DE LÍQUIDOS
MIC 2004-I-80

2.1.2. DISEÑO

El diseño deberá basarse en el código pertinente según el uso que tendrá el tanque, ya que según esto se

establece determinado rango de materiales, factores de seguridad y limites a la resistencia de los

materiales a emplear.

2.2. ANÁLISIS HIDRODINÁMICO

2.2.1. RELACIONES TEÓRICAS

Modelo Análogo de Housner

En este modelo se tienen varias simplificaciones a la solución rigurosa del problema hidrodinámico del

líquido almacenado en un tanque; la primera de ellas es que las paredes se consideran infinitamente

rígidas, otra se puede describir como una membrana sobre el liquido la cual solo permite pequeñas

deformaciones y por ultimo no se considera que el tanque se pueda levantar de su fundación.

En el modelo de Housner se consideran dos tipos de efectos dinámicos debidos a la masa del líquido

contenido. El primer efecto conocido como impulsivo, corresponde a un movimiento inercial del

líquido confinado en la parte inferior, el segundo efecto es conocido como convectivo y corresponde al

primer modo de la masa del líquido de la parte superior.

k/2 k/2

m1

m0
h1
h0

Figura 2-1 Modelo Análogo de Housner

Mayo/2004 Capitulo 2 – Marco Teórico 2-2

<!-- p. 29 -->

César A. Velásquez ANÁLISIS HIDRODINÁMICO DE TANQUES DE ALMACENAMIENTO DE LÍQUIDOS
MIC 2004-I-80

Housner planteo las siguientes ecuaciones para el caso de un tanque cilíndrico, otros casos pueden

observarse en su documento original.

Efectos impulsivos:

⎡ r ⎤
tanh 3
⎢⎣ h ⎥⎦ m = M
0 r
3
h
3 h = h
0 8
Efectos convectivos:

1 27 r ⎡ 27 h ⎤ m = M tanh ⎢ ⎥ 1 4 8 h 8 r ⎣ ⎦
⎡ ⎤
⎢ ⎥ 1 1 h = h ⎢1− + ⎥
1 ⎢ 27 h ⎛ 27 h ⎞ 27 h ⎛ 27 h ⎞ ⎥
⎢ tanh ⎜⎜ ⎟⎟ sinh⎜⎜ ⎟⎟ ⎥ ⎣ 8 r ⎝ 8 r ⎠ 8 r ⎝ 8 r ⎠ ⎦

g 27 ⎡ 27 h ⎤ w = tanh ⎢ ⎥ 1 r 8 8 r ⎣ ⎦
k = m1w2

Donde:

r : radio de la base del tanque
h : altura del liquido contenido en el tanque
ρ: densidad del liquido contenido en el tanque
g : aceleración gravitacional

M : masa total del liquido contenido, M = ρπr 2 h
m : masa impulsiva del liquido 0
h : altura a la cual esta aplicada la masa impulsiva ( m ) 0 0
m : masa convectiva del liquido 1
h : altura a la cual esta aplicada la masa convectiva ( m ) 1 1
w : frecuencia de oscilación de la masa convectiva ( m ) 1 1
k : rigidez requerida para la oscilación de la masa convectiva (m ) 1

Mayo/2004 Capitulo 2 – Marco Teórico 2-3

<!-- p. 30 -->

César A. Velásquez ANÁLISIS HIDRODINÁMICO DE TANQUES DE ALMACENAMIENTO DE LÍQUIDOS
MIC 2004-I-80

1.0

0.9

0.8
Mi/Mo
0.7
Mc/Mo
Mc/Mo 0.6 0.5

0.4 Mi/Mo,

0.3

0.2

0.1

0.0
0.0 1.0 2.0 3.0 4.0 5.0 6.0 7.0 8.0 9.0 10.0
H/R

Figura 2-2 Masas dinámicas del líquido

1.0

0.9

0.8
hi/ho
0.7 hc/ho
hc/ho 0.6
0.5
hi/ho, 0.4

0.3

0.2

0.1

0.0
0.0 1.0 2.0 3.0 4.0 5.0 6.0 7.0 8.0 9.0 10.0

H/R

Figura 2-3 Altura de la masa dinámica

Mayo/2004 Capitulo 2 – Marco Teórico 2-4

<!-- p. 31 -->

César A. Velásquez ANÁLISIS HIDRODINÁMICO DE TANQUES DE ALMACENAMIENTO DE LÍQUIDOS
MIC 2004-I-80

Ecuaciones de la norma API 650 – Apéndice E

M = ZI (C W X + C W H + C W X + C W X ) 1 S S 1 r t 1 1 1 2 2 2

Donde

M : Momento de Vuelco
Z : Factor por zona sísmica
I : Factor de importanci a
C , C : Coeficient e de Fuerza lateral debida al sismo 1 2
W : Peso total de las paredes del tanque S
X : Altura del centroide de la pared del tanque, medida desde el fondo S
W : Peso total del techo del tanque r
H : Altura total de la pared del tanque t
W : Masa Impulsiva Efectiva del liquido 1
X : Altura de aplicacion de la masa impulsiva efectiva, medida desde el fondo 1
W : Masa Convectiva a Efectiva del liquido 2
X : Altura de aplicacion de la masa convectiva efectiva, medida desde el fondo 2

2.2.2. RELACIONES EMPÍRICAS

Metodología de G. C. Manos

La siguiente ecuación fue planteada por Manos en 1986, según el estudio de relaciones de diámetro,

altura del contenido y espesor de las paredes del tanque que funcionaron en sismos ocurridos alrededor

del mundo.

2 ⎛ t S ⎞ 1.0 ⎛ R ⎞ n − .015
M RES = .048.S . E . R.t S ⎜⎜ ⎟⎟ ⎜ ⎟ ⎝ t P ⎠ ⎝ H ⎠
⎛ t S ⎞ 1.0 ⎛ R ⎞ n − .015
M RES = .106 .S .FY . R 2.t S ⎜⎜ ⎟⎟ ⎜ ⎟ ⎝ t P ⎠ ⎝ H ⎠

2 ⎛ H ⎞ .015
M RES = π R H g ρw G * .125 R ⎜ ⎟
⎝ R ⎠

Mayo/2004 Capitulo 2 – Marco Teórico 2-5

<!-- p. 32 -->

César A. Velásquez ANÁLISIS HIDRODINÁMICO DE TANQUES DE ALMACENAMIENTO DE LÍQUIDOS
MIC 2004-I-80

En donde:

M : Momento Resistente , el menor de los anteriores RES
t : Espesor de la pared del tanque S
t : Espesor de la placa de fondo p
n = 0.1 + 0.2(H/R) ≤ 0.25
E : Modulo de Elasticida d del material de las paredes del tanque
S : Coeficient e de deformabil idad de la cimentació n

2 2 M 1 ⎛ R ⎞ .015M OT = .1 29 ρw GH R C EQ ⎜ ⎟
M T ⎝ H ⎠

En donde:

M : Momento de Vuelco Actuante OT
ρ : Densidad del agua [lf/ft³] w
G : Gravedad especifica del contenido
H : Altura del liquido [ft]
R : Radio del tanque [ft]
C : Aceleración impulsiva EQ
M / M : Relación masa impulsiva / masa total del contenido 1 T

2.2.3. TEORÍAS DE FALLA

2.2.3.1. Teoría de Rankine6

Este criterio de falla se emplea en materiales frágiles como el concreto, en esta teoría se establece que

la falla ocurre cuando el máximo esfuerzo principal, el cual ocurre en una de las dos direcciones

principales, alcanza el limite a tensión o compresión uníaxial.

Gráficamente, los esfuerzos principales no pueden salir de los limites de la Figura 2-4.

6 Adaptado del sitio en Internet “Engineering Fundamentals”

Mayo/2004 Capitulo 2 – Marco Teórico 2-6

<!-- p. 33 -->

César A. Velásquez ANÁLISIS HIDRODINÁMICO DE TANQUES DE ALMACENAMIENTO DE LÍQUIDOS
MIC 2004-I-80

σ2
σt

−σc σ1
σt

−σc

Figura 2-4 Criterio de Falla de Rankine

2.2.3.2. Teoría de Tresca7

Este criterio se emplea en materiales dúctiles, como los aceros de bajo carbono, en esta teoría se

considera que la falla se presenta cuando la energía de distorsión alcanza el mismo valor de la energía

de fluencia o de falla en tensión uníaxial.
σ2

σy

−σy σ1
σy

−σy

Figura 2-5 Criterio de Falla de Tresca

7 Adaptado del sitio en Internet “Engineering Fundamentals”

Mayo/2004 Capitulo 2 – Marco Teórico 2-7

<!-- p. 34 -->

César A. Velásquez ANÁLISIS HIDRODINÁMICO DE TANQUES DE ALMACENAMIENTO DE LÍQUIDOS
MIC 2004-I-80

2.3. CHEQUEOS

2.3.1. RESISTENCIA AL VUELCO

La resistencia al volcamiento es provista por el peso de las paredes del tanque, y el anclaje del mismo.

En el caso de que el tanque no tenga un sistema de anclaje una porción del líquido adyacente a las

paredes de esté se considerara efectiva para la resistencia al volcamiento. La porción de contenido que

se puede usar para resistir el vuelco, es definido por la siguiente ecuación de la norma API650

w L = 99 t b Fby GH ≤ 196GHD

En donde:

w : Máximo peso del contenido del tanque que se puede considerar para resistir el L
Mom ento de Vuelco Actuante, en N/m de circunfere ncia del tanque.
t : Espesor de la placa de fondo bajo la pared [mm] b
F : Esfuerzo de fluencia mínimo de la placa de fondo bajo la pared [MPa] by
H : Altura del liquido [m]
G : Gravedad especifica del liquido almacenado
D : Diametro nominal del tanque [m]

Mayo/2004 Capitulo 2 – Marco Teórico 2-8

<!-- p. 35 -->

César A. Velásquez ANÁLISIS HIDRODINÁMICO DE TANQUES DE ALMACENAMIENTO DE LÍQUIDOS
MIC 2004-I-80

2.3.2. COMPRESIÓN DE LA PARED DEL TANQUE

2.3.2.1. Fuerza actuante en tanques no anclados

Para determinar la fuerza longitudinal compresiva, en la zona inferior de la pared del tanque, se

procede a calcular el termino M/[D²(wt+wL)] y determinar en que intervalo esta para aplicar la formula

correspondiente. El API 650 señala tres intervalos diferentes el primero de ellos se da cuando el

termino anterior es inferior o igual a 0.785; otro intervalo se presenta cuando se esta en el intervalo

0.785\< M/[D²(wt+wL)] ≤ 1.5, en este intervalo es necesario obtener un valor de la grafica E-5 de la API
650 y por ultimo se presenta el intervalo entre 1.5\< M/[D²(wt+wL)] ≤ 1.57. Para cuando este valor es

superior a 1.57 se considera que el tanque es estructuralmente inestable y deberá realizarse una medida

que permita eliminar esta condición.

2.3.2.2. Fuerza actuante en tanques anclados

En este caso a diferencia del anterior solo se presenta una formula única que permita obtener la fuerza

longitudinal compresiva actuante.

.1 273 M
b = wt +
D ²

En donde

b : Fuerza longitudin al compresiva máxima, en la zona inferior de la pared del tanque,
en N/m de circunfere ncia
w : Peso de la pared del tanque y de la porcion de la cubierta fija soportada por la pare, t
en N/m de circunfere ncia del tanque
M : Momento Actuante según API650
D : Diametro nominal del tanque

Mayo/2004 Capitulo 2 – Marco Teórico 2-9

<!-- p. 36 -->

César A. Velásquez ANÁLISIS HIDRODINÁMICO DE TANQUES DE ALMACENAMIENTO DE LÍQUIDOS
MIC 2004-I-80

2.3.2.3. Máxima compresión admisible

La máxima compresión longitudinal admisible, b/12t, no puede exceder el esfuerzo admisible, Fa, el

cual considera el efecto de la presión interna debida al liquido contenido.

Cuando GHD²/t² es mayor o igual a 44 m³/mm²

83t
Fa =
D

Cuando GHD²/t² es menor a 44 m³/mm²

83 Fty
Fa = + 5.7 GH
5.2 D

En donde:

G : Gravedad especifica del liquido a almacenar
H : Máximo nivel del liquido, [m]
D : Diametro nominal del tanque [m]
t = Espesor de la lamina inferior de la pared del tanque,
excluyendo cualquier prevision para corrosión, [mm]0
F : Máximo Esfuerzo por compresión longitudin al permitido, [MPa] a
F : Esfuerzo de fluencia mínimo de la lamina inferior de la pared del tanque, [MPa] ty
para este valor se debe verificar la seccion de materiales en la norma API650

2.3.3. LAMINAS SUPERIORES DE LA PARED DEL TANQUE

Cuando el espesor requerido para resistir las fuerzas adicionales impuestas por el sismo es superior al

espesor requerido para los efectos estáticos (en ningún caso se tomara en consideración el sobre –

espesor proporcionado por corrosión), entonces en las laminas superiores se incrementara el espesor en

la misma proporción, a menos que se realice un análisis detallado que permita determinar el momento

de vuelco y el esfuerzo correspondiente en la zona inferior de cada lamina superior.

2Mayo/2004 Capitulo 2 – Marco Teórico
10

<!-- p. 37 -->

\3. Estudio Experimental

Para realizar una comprobación de la teoría existente para la evaluación de las fuerzas inducidas en un

sistema de almacenamiento cilíndrico de liquido, se decidió realizar un ensayo en la mesa vibratoria

presente en la universidad, se eligió realizar un recipiente cilíndrico en lamina delgada, considerando

que con este material seria mas probable medir los diferentes esfuerzos que se pudieran presentar.

Como objetivo se plantea conocer el comportamiento dinámico y las propiedades de la masa de agua.

En la prueba se limito la señal de entrada considerando los factores de seguridad de la metodología

API.

3.1. DESCRIPCIÓN DEL MODELO

Se construyo un tanque con diámetro de 97 cm, considerando las dimensiones de la mesa vibratoria

presente en los laboratorios de la universidad, la cual tiene una plataforma cuadrada de 102.5x102.5

cm. Por limitaciones en la longitud de las láminas disponibles comercialmente se decidió que las

paredes del tanque se conformaran por dos láminas diferentes unidas por cordones de soldadura

laterales.

<!-- p. 38 -->

César A. Velásquez ANÁLISIS HIDRODINÁMICO DE TANQUES DE ALMACENAMIENTO DE LÍQUIDOS
MIC 2004-I-80

Figura 3-1. Modelo Construido

Figura 3-2. Modelo Construido

El recipiente elaborado esta fabricado en lámina delgada de acero. Se han soldado lateralmente las

láminas que confinaran el líquido, para dar simetría y disminuir en lo posible cualquier efecto que se

pueda presentar por la irregularidad.

Mayo/2004 Capitulo 3 – Estudio Experimental 3-2

<!-- p. 39 -->

César A. Velásquez ANÁLISIS HIDRODINÁMICO DE TANQUES DE ALMACENAMIENTO DE LÍQUIDOS
MIC 2004-I-80

3.2. MODELO EXPERIMENTAL

Las pruebas realizadas en el laboratorio tienen como finalidad corroborar las propiedades dinámicas

determinadas según la teoría de Housner, y verificar que la modelación realizada sea acorde a lo que se

presenta realmente durante un sismo.

El modelo se instrumento mediante la ubicación de 4 Strain Gages alrededor del tanque, los cuales

gracias al equipo presente en el laboratorio de la universidad de los andes, pueden registrar varios

cientos de datos por segundo.

La ubicación de los strain gages (SG) se puede indicar como sigue: SG1, Sentido horizontal a 4 cm de

la base, SG2, sentido vertical a 24 cm de la base, SG3, sentido vertical a 3.5 cm de la base, SG4

sentido horizontal a 26 cm de la base. Todos los strain gages estaban alineados con el sentido de la

señal inducida.

El modelo se elaborado soldando y sellando todas las uniones de las laminas.

Figura 3-3. Modelo experimental – Prueba Hidrostática

Mayo/2004 Capitulo 3 – Estudio Experimental 3-3

<!-- p. 40 -->

César A. Velásquez ANÁLISIS HIDRODINÁMICO DE TANQUES DE ALMACENAMIENTO DE LÍQUIDOS
MIC 2004-I-80

3.3. DESCRIPCIÓN DEL ENSAYO

El modelo se ensayó en la Mesa Vibratoria (mostrada en la Figura 3-4.) del Centro de Investigación en

Materiales y Obras Civiles (CIMOC) de la Universidad de los Andes, la cuál permite aplicar una señal

de desplazamiento en la base contra el tiempo de forma controlada. El desplazamiento se aplicó con

una distribución armónica uniforme en el tiempo, aplicada en una fase (ver Figura 3-5)

Figura 3-4. Mesa Vibratoria. CIMOC Uniandes.

• 15 ciclos de desplazamiento llevando la probeta hasta un desplazamiento de 2.7 mm en cada

dirección. Estos límites de desplazamiento se escogieron debido a la limitante de la altura del

líquido durante el evento sísmico.

Mayo/2004 Capitulo 3 – Estudio Experimental 3-4

<!-- p. 41 -->

César A. Velásquez ANÁLISIS HIDRODINÁMICO DE TANQUES DE ALMACENAMIENTO DE LÍQUIDOS
MIC 2004-I-80

3

2

1
(mm)

0
Desplazamiento -1

\-2

\-3
0 1 2 3 4 5 6 7 8 9 10 11 12 13 14 15 16
Tiempo (seg)

Figura 3-5. Ciclos de desplazamiento

0.4

0.35

0.3

0.25

[g]
0.2
Sa

0.15

0.1

0.05

0
0 0.5 1 1.5 2 2.5 3 3.5 4 4.5 5
Periodo [Seg]

Figura 3-6. Espectro de Respuesta de la Señal empleada

Mayo/2004 Capitulo 3 – Estudio Experimental 3-5

<!-- p. 42 -->

César A. Velásquez ANÁLISIS HIDRODINÁMICO DE TANQUES DE ALMACENAMIENTO DE LÍQUIDOS
MIC 2004-I-80

3.4. RESULTADOS DEL EXPERIMENTO

3.4.1. Primera Etapa

Para determinar de manera indirecta el amortiguamiento del liquido al interior del cilindro se aplico

una distribución armónica uniforme a una altura de agua de 45 cm, para determinar mediante una

correlación con la altura alcanzada por el agua el amortiguamiento del liquido almacenado.

20

15

10

(mm) 5

0
0 1 2 3 4 5 6 7 8 9 10 11 12

\-5 Desplazamiento

\-10

\-15

\-20

Tiempo (seg)

Figura 3-7. Señal Empleada

Figura 3-8. Altura Alcanzada

Mayo/2004 Capitulo 3 – Estudio Experimental 3-6

<!-- p. 43 -->

César A. Velásquez ANÁLISIS HIDRODINÁMICO DE TANQUES DE ALMACENAMIENTO DE LÍQUIDOS
MIC 2004-I-80

Según la altura que alcanza el liquido durante la excitación ejercida sobre este, y las ecuaciones

descritas en el capitulo 2, la altura que alcanza el liquido es de aproximadamente 80 cm, la cual se

obtiene a un amortiguamiento del liquido del 0.5 %.

3.4.2. Segunda Etapa

Se cambio la altura del líquido almacenado y la señal empleada, considerando el espectro que se

obtiene de la señal construida y diferentes parámetros como la seguridad al vuelco y al deslizamiento,

además se considero evitar el escape del líquido debido al oleaje.

Figura 3-9. Movimiento del líquido

Mayo/2004 Capitulo 3 – Estudio Experimental 3-7

<!-- p. 44 -->

César A. Velásquez ANÁLISIS HIDRODINÁMICO DE TANQUES DE ALMACENAMIENTO DE LÍQUIDOS
MIC 2004-I-80

0.00008

0.00006

0.00004

0.00002

0 (mm/mm)

\-0.00002

\-0.00004 Deformación

\-0.00006

\-0.00008

\-0.0001
0 5 10 15 20 25 30 35 40 45

Tiempo (seg)

Figura 3-10. Respuesta obtenida en el Strain Gage No1

3.5. MODELO TEÓRICO

3.5.1. Modelo con Elementos Finitos

Se elabora un modelo lineal en elementos finitos elásticos para verificar el comportamiento

experimental y poder estudiar la interacción de todos los elementos. Para llevar a cabo el

modelamiento se utilizó el programa SAP2000 de la Casa “Computer and Structures Inc.”. Las

características más relevantes del modelo son:

• Geometría y Apoyos: El modelo esta conformado por 9719 elementos finitos tipo “shell”, los

cuales tienen tres grados de libertad por nudo. La malla elaborada se muestra en la Figura 3-11.

Mayo/2004 Capitulo 3 – Estudio Experimental 3-8

<!-- p. 45 -->

César A. Velásquez ANÁLISIS HIDRODINÁMICO DE TANQUES DE ALMACENAMIENTO DE LÍQUIDOS
MIC 2004-I-80

Figura 3-11. Malla de elementos finitos

• Material y sección: el material del modelo es acero con las siguientes características :

Es = 200 Gpa
ν = 0.30

Las secciones de los elementos del modelo tienen un espesor constante de 0.9 mm.

Característica Unidad Valor

Material Acero

Diámetro Interno m 0.98

Altura m 1.00

Gs Contenido 1.0

Espesor pared mm 9

• Carga: se empleo una carga hidrostática aplicada en contra de las paredes del tanque, según el nivel

del líquido presente. Además se considero el líquido como una serie de masas pegadas a las

paredes del tanque. Se llevaron dos tipos de análisis sobre este modelo: Un análisis espectral y una

análisis contra el tiempo.

Mayo/2004 Capitulo 3 – Estudio Experimental 3-9

<!-- p. 46 -->

César A. Velásquez ANÁLISIS HIDRODINÁMICO DE TANQUES DE ALMACENAMIENTO DE LÍQUIDOS
MIC 2004-I-80

Figura 3-12. Patrón de Carga Hidrostática (kg/cm²)

• Respuesta del Modelo

60

40

20

0

\-20

\-40

\-60
0 2 4 6 8 10 12 14 16 18

Desplazamiento de la masa de liquido Señal introducida

Figura 3-13. Respuesta obtenida en el modelo

3Mayo/2004 Capitulo 3 – Estudio Experimental
10

<!-- p. 47 -->

César A. Velásquez ANÁLISIS HIDRODINÁMICO DE TANQUES DE ALMACENAMIENTO DE LÍQUIDOS
MIC 2004-I-80

En la figura anterior se puede observar como la masa de agua se mueve de una lado a otro,

siguiendo un periodo similar al de la señal de entrada, pero con valores de oscilación que se

incrementan lentamente hasta alcanzar un nivel de estabilidad como denotan los últimos ciclos.

En las siguientes graficas se muestra una comparación entre la deformación alcanzada en los strain

gages contra la obtenida analíticamente en el modelo de computador según la metodología

empleada.

1.60E-05

Resultados de SAP2000 1.40E-05
Medición en Laboratorio

1.20E-05

1.00E-05

8.00E-06

6.00E-06

4.00E-06

2.00E-06

0.00E+00
SG1 SG2 SG3 SG4

Figura 3-14. Comparación de Deformación por carga Hidrostática

3Mayo/2004 Capitulo 3 – Estudio Experimental
11

<!-- p. 48 -->

César A. Velásquez ANÁLISIS HIDRODINÁMICO DE TANQUES DE ALMACENAMIENTO DE LÍQUIDOS
MIC 2004-I-80

7.00E-05

Analisis Espectral
6.00E-05 Analisis Cronologico

Medición en Laboratorio

5.00E-05

4.00E-05

3.00E-05

2.00E-05

1.00E-05

0.00E+00
SG1 SG2 SG3 SG4

Figura 3-15. Comparación de Deformación por análisis dinámico sentido positivo

8.00E-05

7.00E-05 Analisis Espectral
Analisis Cronologico

Medición en Laboratorio
6.00E-05

5.00E-05

4.00E-05

3.00E-05

2.00E-05

1.00E-05

0.00E+00
SG1 SG2 SG3 SG4

Figura 3-16. Comparación de Deformación por análisis dinámico sentido negativo

Como se puede observar en las graficas anteriores ambas metodologías de análisis dinámico son

algo conservadoras respecto a la medición realizada, lo cual garantiza que se cubre cualquier

3Mayo/2004 Capitulo 3 – Estudio Experimental
12

<!-- p. 49 -->

César A. Velásquez ANÁLISIS HIDRODINÁMICO DE TANQUES DE ALMACENAMIENTO DE LÍQUIDOS
MIC 2004-I-80

detalle adicional que pueda haberse omitido, como pueden ser imperfecciones en el material o en la

forma del tanque de almacenamiento.

Tabla 3.1. Comparación de los resultados – modelo elementos finitos y modelo experimental

Modelo Simplificado Modelo Teórico Modelo Teórico
Parámetro
API650 Espectral Cronológico

Fuerza de Vuelco 3.65 kgf 2.38 kgf 2.58 kgf

Momento de Vuelco 339.7 kgf-mm 360.06 kgf-mm 278.38 kgf-mm

Como se puede observar en la tabla anterior los tres modelos dan resultados similares, los cuales

se pueden considerar que están dentro de un margen de error aceptable respecto a los otros.

Desafortunadamente para esta comparación no existe un punto base experimental contra el cual se

pueda comparar dado que la medición de estos efectos no es fácilmente mesurable mediante los

equipos y tecnología disponibles para la elaboración de este trabajo. Sin embargo y dada la

relación observada anteriormente se puede considerar confiable y se puede estimar que es cercana

y un poco superior a la actuante.

3Mayo/2004 Capitulo 3 – Estudio Experimental
13

<!-- p. 50 -->

\4. Metodología para análisis
dinámico

4.1. Información requerida

Se debe buscar recopilar la mayor cantidad de información posible de la construcción del tanque, en lo

cual se incluye, materiales, geometría, anchos de lámina, tipos de conexiones, aberturas, cubierta,

columnas interiores y el tipo de cimentación o soporte que tenga el tanque. Cuando sea posible se debe

verificar en campo cada uno de estos detalles.

Adicionalmente se debe recopilar toda la información posible acerca del tipo de suelo sobre el cual se

apoya, la sismicidad de la región o el espectro de diseño de la zona en la cual se encuentre ubicado el

tanque.

4.2. Modelo de Análisis

Se debe generar un modelo de análisis lo mas cercano posible a lo encontrado en planos y en la visita

de campo, se debe considerar para la discretización el sistema coordenado a utilizar y lo refinado de la

malla, según la capacidad computacional disponible.

En el modelo se debe incluir todos los cambios de espesor en las paredes, el tipo de apoyo (ya que el

suelo sobre el cual se cimienta no es completamente rígido y es sujeto a deformaciones), el tipo de

conexión presente en la cubierta y en el pie del tanque, la cubierta (las vigas y las laminas que la

conforman) y las columnas que le brindan soporte

<!-- p. 51 -->

César A. Velásquez ANÁLISIS HIDRODINÁMICO DE TANQUES DE ALMACENAMIENTO DE LÍQUIDOS
MIC 2004-I-80

4.3. Cargas

• Carga Muerta

La carga muerta está representada por el peso de todos los elementos permanentes a saber: peso de la

estructura, componentes constructivos adicionales (escaleras, etc.) que existen en el edificio. La carga

muerta se ha clasifica de acuerdo a su aplicación en dos grandes grupos distribuidas y puntuales.

• Carga Viva

Se debe considerar una carga viva según se especifique en el código local de diseño, por lo general esta

carga se aplica únicamente sobre la cubierta y los accesos del tanque (escaleras u otros)

• Carga Hidrostática

Corresponde a la presión ejercida por el líquido en las paredes y en el fondo del tanque. Así según la

altura del líquido y su densidad, y por tratarse de un líquido incompresible se obtiene la presión que

este ejerce.

• Carga Sísmica

Se define el posible escenario correspondiente al sismo de diseño. El espectro de aceleración se

determina a partir del estudio geotécnico realizado sobre el sitio y según el espectro de diseño aportado

por el estudio de Microzonificación para la ubicación de la estructura. El espectro implementado en el

programa de computador utilizado para determinar las respuestas de la estructura, Debe ser factorizado

según el coeficiente de importancia correspondiente.

Para realizar el presente análisis se uso un espectro de diseño, este análisis se basa en el calculo de

fuerzas las cuales según el periodo de los modos de vibración y su participación en la estructura

generan una excitación de la estructura, dada la cantidad de formas modales evaluadas, estas se

combinan mediante una formulación matemática que permite considerar todos los modos de vibración,

teniendo en cuenta el grado de influencia de cada uno.

Mayo/2004 Capitulo 4 – Metodología para Análisis4-3
Dinámico

<!-- p. 52 -->

César A. Velásquez ANÁLISIS HIDRODINÁMICO DE TANQUES DE ALMACENAMIENTO DE LÍQUIDOS
MIC 2004-I-80

• Carga Dinámica (Formulación de Housner)

Siguiendo la formulación planteada en el capitulo 3, se obtienen los valores que describen el

comportamiento dinámico de la estructura a analizar.

k c / 2 k c / 2

m C

m i
h c
h i

Figura 4-1 Modelo de Housner

• Combinación de Carga

Se establecen las combinaciones de carga requeridas por el código de diseño empleado.

4.4. Resultados

• Periodos y Modos de Vibración

Se debe revisar que la masa participante supere el 90% de la masa presente en el modelo, y se debe

verificar la coincidencia del primer periodo del análisis con el periodo del líquido en movimiento según

la teoría de Housner para corroborar que los valores de masa estén correctamente asignados en el

modelo de análisis.

• Esfuerzos en la pared del tanque

Mediante la obtención de esfuerzos para cada tipo de análisis realizado y combinación de carga

definida, se obtienen los valores de la variación de esfuerzos a diferentes alturas de las láminas del

tanque, estos valores que por lo general se obtienen en las direcciones normales de los elementos se

Mayo/2004 Capitulo 4 – Metodología para Análisis4-4
Dinámico

<!-- p. 53 -->

César A. Velásquez ANÁLISIS HIDRODINÁMICO DE TANQUES DE ALMACENAMIENTO DE LÍQUIDOS
MIC 2004-I-80

convierten a los esfuerzos principales, y mediante una teoría de falla como la de Tresca se verifica que

la lamina pueda soportar correctamente los sobreesfuerzos inducidos por el movimiento de la masa de

liquido.

• Revisiones

Los códigos de diseño presentan diferentes chequeos para los efectos que ocurren sobre el tanque,

donde se analiza la susceptibilidad al pandeo, al volcamiento y al deslizamiento del tanque. Estos

deben realizarse aunque se realice un análisis mas detallado para poder cumplir con el código de

diseño.

Mayo/2004 Capitulo 4 – Metodología para Análisis4-5
Dinámico

<!-- p. 54 -->

\5. Caso de Estudio

5.1. DISEÑO HIDROSTÁTICO

Se desea construir un tanque con una capacidad máxima de 34600 m³, el cual almacenara un

combustible con una gravedad especifica de 0.9 tonf/m³

Se escoge un diámetro para el tanque y una altura máxima para el contenido almacenado.

Característica Unidad Valor
Material Acero
Diámetro Interno m 54.86
Altura Libre m 14.63

Volumen Util m³ 34632
Gs Contenido 1.08
W Contenido Max Ton 31169

Escogemos el material a usar y buscamos sus propiedades para diseño.

Material Acero ASTM A – 285 Gr C
Resistencia a la Fluencia 205 MPa
Resistencia Ultima Mínima 380 MPa
Módulo de Elasticidad 200 GPa
Esfuerzo de diseño 137 Mpa
Esfuerzo para la prueba hidrostática 154 Mpa

<!-- p. 55 -->

César A. Velásquez ANÁLISIS HIDRODINÁMICO DE TANQUES DE ALMACENAMIENTO DE LÍQUIDOS
MIC 2004-I-80

En la norma API 650 se establece el método de diseño de “1 foot Method” el cual se basa en diseñar

cada nivel de la pared del tanque 30 cm (1 foot) más arriba de la zona inferior de cada nivel. Este

método es el estándar para diseño de tanques siempre y cuando su diámetro sea inferior a los 60 m.

9.4 D ( H − )3.0 G
t d = + CA
S d

9.4 D ( H − 3.0)
t t =
S t

En donde

td : Espesor de diseño, [mm]
t : Espesor de diseño hidrostati co, [mm] t
H : Nivel de diseño [m]
Altura desde el fondo del nivel de la lamina en considerac ión
hasta el nivel que limite el llenado del tanque.
G : Gravedad especifica del liquido almacenado
CA : Sobre espesor dado para corrosión, [mm]
Sd : Esfuerzo de diseño admisible, [MPa]
St : Esfuerzo admisible para la condición de prueba hidrostati ca , [MPa]

Haciendo uso de las ecuaciones anteriores obtenemos

Espesor Espesor
H td tt Lamina Minimo Escogido
[m] [mm] [mm]
[mm] [mm]
1 2.03 3.67 3.02 8 8.0

2 4.13 8.12 6.69 8 8.0
3 6.23 12.57 10.35 8 12.0
4 8.33 17.02 14.02 8 17.0
5 10.43 21.47 17.68 8 21.5
6 12.53 25.92 21.35 8 26.5

7 14.63 30.37 25.01 8 31.0

Mayo/2004 Capitulo 5 – Caso de Estudio 5-2

<!-- p. 56 -->

César A. Velásquez ANÁLISIS HIDRODINÁMICO DE TANQUES DE ALMACENAMIENTO DE LÍQUIDOS
MIC 2004-I-80

Llevando a cabo un análisis elástico, tenemos

Espesor de Pared (mm)

31.0 26.5 21.5 17.0 12.0 8.0
σ11 - cara externa 134.10 102.90 105.40 100.00 99.30 48.04
Esfuerzos
Actuantes σ22 - cara externa 80.10 -6.27 0.98 -1.13 3.55 8.92
σ12 - cara externa 3.05 0.29 0.07 0.06 0.46 -1.28
σI - cara externa 134.27 102.90 105.40 100.00 99.30 48.08
Esfuerzos
Principales σII - cara externa 79.93 -6.27 0.98 -1.13 3.55 8.88
σIII- cara externa 0.00 0.00 0.00 0.00 0.00 0.00
Esf. de Von Mises σVM - cara externa 116.98 105.72 103.91 99.13 95.53 41.28
σ11 - cara interna 95.08 104.05 103.20 98.70 96.02 46.98
Esfuerzos
Actuantes σ22 - cara interna -58.67 5.69 -0.77 0.48 -2.12 -5.92
σ12 - cara interna 2.07 0.29 0.05 0.04 -0.37 -1.75
σI - cara externa 95.11 104.05 103.20 98.70 96.02 47.04
Esfuerzos
Principales σII - cara externa -58.70 5.69 -0.77 0.48 -2.12 -5.98
σIII- cara externa 0.00 0.00 0.00 0.00 0.00 0.00
Esf. de Von Mises σVM - cara externa 134.44 100.79 102.61 96.98 95.23 48.47

Como puede observarse el esfuerzo presente en las diferentes alturas de la lámina es siempre inferior al

esfuerzo de diseño permitido para el material seleccionado.

Otras consideraciones especiales han de tenerse en cuenta para el diseño de la cubierta y su respectivo

apoyo, ya que esto escapa al alcance de este trabajo, se presenta un esquema tipo para este tipo de

elementos.

Mayo/2004 Capitulo 5 – Caso de Estudio 5-3

<!-- p. 57 -->

César A. Velásquez ANÁLISIS HIDRODINÁMICO DE TANQUES DE ALMACENAMIENTO DE LÍQUIDOS
MIC 2004-I-80

m
1

Ø

Figura 5-1 Esquema de disposición de la cubierta

Mayo/2004 Capitulo 5 – Caso de Estudio 5-4

<!-- p. 58 -->

César A. Velásquez ANÁLISIS HIDRODINÁMICO DE TANQUES DE ALMACENAMIENTO DE LÍQUIDOS
MIC 2004-I-80

5.2. DISEÑO HIDRODINÁMICO

5.2.1. MODELO DE ANÁLISIS

• Geometría

Figura 5-2 Vista del Modelo

Tipo de Elemento No de Elementos
Joint 5402
Frame 2240
Shell 4302

Figura 5-3 Corte del modelo tridimensional desarrollado

• Condiciones de borde

Parámetro Unidad Valor

Tipo de Suelo Arena

Capacidad Admisible Tonf/m² 30

Mayo/2004 Capitulo 5 – Caso de Estudio 5-5

<!-- p. 59 -->

César A. Velásquez ANÁLISIS HIDRODINÁMICO DE TANQUES DE ALMACENAMIENTO DE LÍQUIDOS
MIC 2004-I-80

Figura 5-4 Condiciones de borde del Modelo

5.2.2. CARGAS

5.2.2.1. Carga Muerta

Carga Unidades Valor

Peso del Tanque Vacío Ton 664

Peso del Contenido Ton 31169

5.2.2.2. Carga Hidrostática

Se evaluó las cargas actuantes en la estructura en su estado estático, las cuales para este caso

corresponden a la presión ejercida por el líquido en las paredes y en el fondo del tanque. Así según la

altura del líquido y su densidad, y por tratarse de un líquido incompresible se obtiene la presión que

este ejerce.

Figura 5-5 Carga Hidrostática Ton/m²

Mayo/2004 Capitulo 5 – Caso de Estudio 5-6

<!-- p. 60 -->

César A. Velásquez ANÁLISIS HIDRODINÁMICO DE TANQUES DE ALMACENAMIENTO DE LÍQUIDOS
MIC 2004-I-80

5.2.2.3. Espectro de diseño

Para realizar el presente análisis se uso un espectro de diseño, este análisis se basa en el calculo de

fuerzas las cuales según el periodo de los modos de vibración y su participación en la estructura

generan una excitación de la estructura, dada la cantidad de formas modales evaluadas, estas se

combinan mediante una formulación matemática que permite considerar todos los modos de vibración,

teniendo en cuenta el grado de influencia de cada uno.

0.60

0.50

0.40

(g) 0.30
Sa

0.20

0.10

0.00
0.0 1.0 2.0 3.0 4.0 5.0 6.0 7.0
Periodo (seg)

Figura 5-6 Espectro de Diseño

5.2.2.4. Carga Dinámica (Formulación de Housner)

Siguiendo la formulación planteada en el capitulo 3, se obtienen los siguientes valores que describen el

comportamiento dinámico de la estructura a analizar.

Mayo/2004 Capitulo 5 – Caso de Estudio 5-7

<!-- p. 61 -->

César A. Velásquez ANÁLISIS HIDRODINÁMICO DE TANQUES DE ALMACENAMIENTO DE LÍQUIDOS
MIC 2004-I-80

Propiedad Unidad Valor

mi Ton.s²/m 974.7
Masa Impulsiva
hi m 5.49

mc Ton.s²/m 2060.8
k c / 2 k c / 2
hc m 7.85
m C
Ks Ton/m 1018.4
Masa Convectiva
ω2 (rad/s)² 0.49 m i
h c
fn Hz 0.11
h i
Τ seg 8.94

Altura del Oleaje HO m 0.66

Figura 5-7 Modelo de Housner

5.2.3. COMBINACIÓN DE CARGA

E
D + PCONTENIDO +
R

En donde:

D: Efectos generados por la cargas muertas (Peso propio de los elementos estructurales)

PCONTENIDO: Efectos generados por la presión del contenido

E: Efectos generados por las solicitaciones sísmicas.

R: Factor de reducción sísmico (R = 2.0)

Mayo/2004 Capitulo 5 – Caso de Estudio 5-8

<!-- p. 62 -->

César A. Velásquez ANÁLISIS HIDRODINÁMICO DE TANQUES DE ALMACENAMIENTO DE LÍQUIDOS
MIC 2004-I-80

5.2.4. RESULTADOS

5.2.4.1. Periodos y Modos de Vibración

Periodo Masa UX Masa UX
Modo No
(seg) (%) Acumulada (%)

1 9.00 66.61% 66.61%

2 1.58 0.00% 66.61%

3 1.58 0.00% 66.61%

4 1.56 0.00% 66.61%

5 1.42 0.00% 66.61%

6 1.42 0.00% 66.61%

7 1.28 0.00% 66.61%

8 1.16 0.00% 66.61%

9 1.10 0.00% 66.61%

10 1.05 0.00% 66.61%

11 0.96 0.00% 66.61%

12 0.85 0.00% 66.61%

13 0.71 0.00% 66.61%

14 0.58 0.00% 66.61%

15 0.47 0.04% 66.65%

16 0.40 1.06% 67.72%

17 0.34 9.78% 77.50%

18 0.28 15.44% 92.93%

19 0.22 5.88% 98.81%

20 0.08 0.44% 99.26%

Mayo/2004 Capitulo 5 – Caso de Estudio 5-9

<!-- p. 63 -->

César A. Velásquez ANÁLISIS HIDRODINÁMICO DE TANQUES DE ALMACENAMIENTO DE LÍQUIDOS
MIC 2004-I-80

Modo 1 T = 9.00 seg

Modo 17 – T = 0.34 seg

Modo 18 – T = 0.28 seg

Figura 5-8 Modos Fundamentales del tanque

5Mayo/2004 Capitulo 5 – Caso de Estudio
10

<!-- p. 64 -->

César A. Velásquez ANÁLISIS HIDRODINÁMICO DE TANQUES DE ALMACENAMIENTO DE LÍQUIDOS
MIC 2004-I-80

5.2.4.2. Esfuerzos en la pared del tanque

• Peso Propio

σ22

σ12
σ11 σ11
σ12

σ22

Esfuerzo σ11 (MPa)

σ22

σ12
σ11 σ11
σ12

σ22

Esfuerzo σ22 (MPa)

σ22

σ12
σ11 σ11
σ12

σ22

Esfuerzo σ12 (MPa)

Figura 5-9 Esfuerzos para carga gravitacional

5Mayo/2004 Capitulo 5 – Caso de Estudio
11

<!-- p. 65 -->

César A. Velásquez ANÁLISIS HIDRODINÁMICO DE TANQUES DE ALMACENAMIENTO DE LÍQUIDOS
MIC 2004-I-80

• Presión Hidrostática

σ22

σ12
σ11 σ11
σ12

σ22

Esfuerzo σ11 (MPa)

σ22

σ12
σ11 σ11
σ12

σ22

Esfuerzo σ22 (MPa)

σ22

σ12
σ11 σ11
σ12

σ22

Esfuerzo σ12 (MPa)

Figura 5-10 Esfuerzos para presión hidrostática

5Mayo/2004 Capitulo 5 – Caso de Estudio
12

<!-- p. 66 -->

César A. Velásquez ANÁLISIS HIDRODINÁMICO DE TANQUES DE ALMACENAMIENTO DE LÍQUIDOS
MIC 2004-I-80

• Sismo

σ22

σ12
σ11 σ11
σ12

σ22

Esfuerzo σ11 (MPa)

σ22

σ12
σ11 σ11
σ12

σ22

Esfuerzo σ22 (MPa)

σ22

σ12
σ11 σ11
σ12

σ22

Esfuerzo σ12 (MPa)

Figura 5-11 Esfuerzos para sismo

5Mayo/2004 Capitulo 5 – Caso de Estudio
13

<!-- p. 67 -->

César A. Velásquez ANÁLISIS HIDRODINÁMICO DE TANQUES DE ALMACENAMIENTO DE LÍQUIDOS
MIC 2004-I-80

5.2.4.3. Variación de los esfuerzos en la pared

Caso de Carga Espesor de Pared (mm) 31.0 26.5 21.5 17.0 12.0 8.0
σ11 - cara externa -0.12 -0.24 -0.23 -0.19 -0.14 -0.44
σ22 - cara externa -0.42 -0.82 -0.70 -0.59 -0.52 -1.00
σ12 - cara externa 0.25 0.29 0.25 0.25 0.32 0.42
Peso Propio
σ11 - cara interna -0.64 -0.07 0.13 0.11 0.06 0.27
σ22 - cara interna -1.07 -0.65 -0.55 -0.46 -0.43 0.38
σ12 - cara interna 0.16 0.19 0.24 0.29 0.38 0.49
σ11 - cara externa 134.10 102.90 105.40 100.00 99.30 48.04
σ22 - cara externa 80.10 -6.27 0.98 -1.13 3.55 8.92
Presión σ12 - cara externa 3.05 0.29 0.07 0.06 0.46 -1.28
Hidroestática σ11 - cara interna 95.08 104.05 103.20 98.70 96.02 46.98
σ22 - cara interna -58.67 5.69 -0.77 0.48 -2.12 -5.92
σ12 - cara interna 2.07 0.29 0.05 0.04 -0.37 -1.75
σ11 (max) - cara externa 4.88 52.51 71.24 135.11 37.47 12.65
σ22 (max)- cara externa 15.26 17.87 7.40 90.92 22.87 16.99
Sismo σ12 (max)- cara externa 2.38 2.17 1.17 6.66 7.69 4.16
Línea 1 σ11 (max)- cara interna 7.87 49.08 71.33 86.14 32.98 4.77
σ22 (max)- cara interna 14.65 10.47 20.06 49.29 21.14 14.64
σ12 (max)- cara interna 1.58 2.14 2.24 6.86 3.87 4.16
σ11 (max) - cara externa 27.45 55.02 57.36 57.28 40.23 101.15
σ22 (max)- cara externa 41.38 43.30 65.03 82.63 88.30 30.61
Sismo σ12 (max)- cara externa 13.00 11.87 8.76 8.52 15.90 33.38
Línea 2 σ11 (max)- cara interna 22.54 44.04 40.55 36.92 23.40 60.94
σ22 (max)- cara interna 23.48 14.63 29.50 39.16 61.88 25.63
σ12 (max)- cara interna 16.92 13.35 8.84 9.78 19.17 38.70

Línea 2

Línea 1

Figura 5-12 Líneas de verificación de esfuerzos máximos

5Mayo/2004 Capitulo 5 – Caso de Estudio
14

<!-- p. 68 -->

César A. Velásquez ANÁLISIS HIDRODINÁMICO DE TANQUES DE ALMACENAMIENTO DE LÍQUIDOS
MIC 2004-I-80

5.2.4.4. Chequeos y revisiones

• Revisión de Fluencia en la pared del Tanque

Espesor de Pared (mm) 31.0 26.5 21.5 17.0 12.0 8.0
σ11 - cara externa 136.42 128.91 140.79 167.37 117.89 53.92
Esfuerzos σ22 - cara externa 72.05 -16.02 -3.42 -47.18 -8.40 -0.57
σ12 - cara externa 4.49 1.66 0.91 3.64 4.63 1.22
σI - cara externa 136.73 128.93 140.80 167.43 118.06 53.95
Esfuerzos σII - cara externa 71.74 -16.04 -3.43 -47.24 -8.57 -0.60
Principales σIII- cara externa 0.00 0.00 0.00 0.00 0.00 0.00
1 Esf. de Von Mises σVM - cara externa 118.46 137.66 142.54 195.38 122.57 54.25
Línea σ11 - cara interna 98.37 128.52 138.99 141.88 112.57 49.64
Esfuerzos σ22 - cara interna -67.07 -0.19 -11.35 -24.63 -13.12 -12.86
σ12 - cara interna 3.02 1.55 1.41 3.76 1.95 0.82
σI - cara interna 98.43 128.54 139.00 141.96 112.60 49.65
Esfuerzos σII - cara interna -67.12 -0.21 -11.36 -24.71 -13.15 -12.87
cara interna 0.00 0.00 0.00 0.00 0.00 0.00 (MPa) Principales σIII-
Esf. de Von Mises σVM - cara interna 144.22 128.64 145.02 155.80 119.72 57.18
σ11 - cara externa 147.70 130.17 133.85 128.45 119.28 98.18
Esfuerzos σ22 - cara externa 58.99 -28.74 -32.24 -43.03 -41.12 -7.38 Esfuerzos
σ12 - cara externa 9.80 6.52 4.70 4.57 8.73 15.83
σI - cara externa 148.77 130.44 133.98 128.57 119.75 100.50
Esfuerzos σII - cara externa 57.92 -29.01 -32.37 -43.16 -41.59 -9.71
Principales σIII- cara externa 0.00 0.00 0.00 0.00 0.00 0.00
2 Esf. de Von Mises σVM - cara externa 129.89 147.10 152.76 154.73 145.09 105.69
Línea σ11 - cara interna 105.71 126.00 123.60 117.27 107.78 77.72
Esfuerzos σ22 - cara interna -71.48 -2.28 -16.07 -19.56 -33.49 -18.35
σ12 - cara interna 10.69 7.15 4.71 5.22 9.60 18.09
σI - cara interna 106.35 126.40 123.76 117.47 108.43 81.02
Esfuerzos σII - cara interna -72.12 -2.67 -16.23 -19.76 -34.14 -21.65
Principales σIII- cara interna 0.00 0.00 0.00 0.00 0.00 0.00
Esf. de Von Mises σVM - cara interna 155.51 127.75 132.62 128.49 128.93 93.73

Variable Unidades Valor

Esfuerzo Máximo de Von Misses MPa 156

Esfuerzo Resistente a Fluencia MPa 205

Relación de Esfuerzos Actuante/Resistente 0.76

5Mayo/2004 Capitulo 5 – Caso de Estudio
15

<!-- p. 69 -->

César A. Velásquez ANÁLISIS HIDRODINÁMICO DE TANQUES DE ALMACENAMIENTO DE LÍQUIDOS
MIC 2004-I-80

• Revisión de Pandeo en la pared del tanque

Variable Unidades Valor

Espesor pared promedio mm 19

wL N/m 45258

w t N/m 21298

M/[D²*(wL+wt)] API 650 0.404

M/[D²*(wL+wt)] Modelo 0.509

b API 650 N/m 55559

b Modelo N/m 64400

σ COMPRESIÓN API 650 MPa 2.92
σ COMPRESIÓN Modelo MPa 3.39

GHD² / t² m³/mm² 110

Fa MPa 28.7

Fty/2 MPa 102

FS COMPRESIÓN API 650 9.82

FS COMPRESIÓN Modelo 8.47

• Chequeo de Volteo y Deslizamiento

Solicitaciones

Variable Unidades API 650 Modelo

W1 Ton 9351 9562

W2 Ton 19325 20217

H1 m 5.5 5.5

H2 m 8.0 7.8

k 0.67

T seg 8.99 8.94

C1 0.60

C2 0.05

Momento de Vuelco Ton.m 8246 10205

Fuerza Horizontal Ton 1842 1715

5Mayo/2004 Capitulo 5 – Caso de Estudio
16

<!-- p. 70 -->

César A. Velásquez ANÁLISIS HIDRODINÁMICO DE TANQUES DE ALMACENAMIENTO DE LÍQUIDOS
MIC 2004-I-80

Resistencia (API 650)

Variable Unidades Valor

Espesor de la placa de fondo tb mm 8.00

Esfuerzo de Fluencia placa fondo MPa 205

wL N/m 41148

Perímetro Tanque m 172
Fuerza Resistente al Volcamiento Ton 710

Momento de Vuelco Resistente Ton.m 19481

Fuerza Resistente al Deslizamiento Ton 9125

F.S. Volcamiento API 650 2.40
F.S. Volcamiento Modelo 1.91

F.S. Deslizamiento API 650 6.58

F.S. Deslizamiento Modelo 5.32
\* F.S. Factor de Seguridad

• Metodología Alternativa (Manos 1986).

2 ⎛ t S ⎞ 1.0 ⎛ R ⎞ n − .015
M RES = .048.S . E . R.t S ⎜⎜ ⎟⎟ ⎜ ⎟ = 144587 Ton.m ⎝ t P ⎠ ⎝ H ⎠
2 ⎛ t S ⎞ 1.0 ⎛ R ⎞ n − .0 15
M RES = .1 06.S .FY .R .t S ⎜⎜ ⎟⎟ ⎜ ⎟ = 463561 Ton.m ⎝ t P ⎠ ⎝ H ⎠

2 ⎛ H ⎞ .015
M RES = π R H g ρw G * .1 25 R ⎜ ⎟ = 973178 Ton.m
⎝ R ⎠

En donde:

MRES : Momento resistente

ts: espesor de la pared.
tp: espesor de la placa de fondo.

n: 0.1 + 0.2 (H/R) \< 0.25

E: Módulo de Young

S: coeficiente de deformabilidad de la cimentación (1.2)

5Mayo/2004 Capitulo 5 – Caso de Estudio
17

<!-- p. 71 -->

César A. Velásquez ANÁLISIS HIDRODINÁMICO DE TANQUES DE ALMACENAMIENTO DE LÍQUIDOS
MIC 2004-I-80

2 2 M 1 ⎛ R ⎞ .015M OT = .129 ρw GH R C EQ ⎜ ⎟ = 191050159 lb. ft = 26414 Ton.m
M T ⎝ H ⎠

En donde:

MOT : Momento de vuelco actuante (lb.ft)
ρW: densidad del agua (62.4 lb/ft³ / g)

G: gravedad específica del contenido

H: altura del líquido (ft)

R: radio del tanque (ft)

Ceq: aceleración impulsiva limitante (g) – 0.517

M1/MT: relación masa impulsiva/ masa del contenido

De lo anterior M RES = 144587 Ton.m y M OT = 26414 Ton.m con lo cual se obtiene para el
presente caso, un factor de seguridad al volcamiento de 5.47 valor superior al encontrado con la
metodología presentada en el API 650.

5Mayo/2004 Capitulo 5 – Caso de Estudio
18

<!-- p. 72 -->

\6. Observaciones y
recomendaciones

• La altura alcanzada por el liquido al interior del tanque durante un movimiento oscilatorio, debe

calcularse en base a un amortiguamiento del liquido en oscilación del 0.5% de la señal usada o del

espectro a emplear.

• El amortiguamiento a considerar en el análisis de una estructura como estas deberá replantearse

según las características de la geometría y de los materiales del proyecto, ya que estos por lo

general se encuentran en los códigos de diseño con un amortiguamiento intrínseco del 5%, el cual

es adecuado para analizar Estructuras de edificios, pero para el tipo de elementos analizados en

esta tesis se encuentra que este amortiguamiento es muy bajo lo cual da un espectro de pseudos-

aceleración inferior al que realmente se presentaría.

0.80

0.70

ξ=5.0%
0.60
ξ=2.0%

0.50 ξ=0.5%

(g) 0.40
Sa

0.30

0.20

0.10

0.00
0.0 1.0 2.0 3.0 4.0 5.0 6.0 7.0
Periodo (seg)

<!-- p. 73 -->

César A. Velásquez ANÁLISIS HIDRODINÁMICO DE TANQUES DE ALMACENAMIENTO DE LÍQUIDOS
MIC 2004-I-80

Figura 6-1. Comparación de un espectro típico a diferentes niveles de amortiguamiento

Para realizar un análisis espectral se debe emplear una señal combinada con el amortiguamiento

2% para los periodos mas bajos (los de las paredes del tanque) y con un amortiguamiento del

0.5% para el periodo del liquido.

0.80

0.70 ξ=2.0%

ξ=0.5%
0.60
Espectro a Emplear

0.50

(g) 0.40
Sa

0.30

0.20

0.10

0.00
0.0 1.0 2.0 3.0 4.0 5.0 6.0 7.0
Periodo (seg)

Figura 6-2. Espectro de diseño compuesto

• Los modelos con elementos finitos permiten conocer de forma aceptable el comportamiento ante

un movimiento del terreno de un tanque de almacenamiento, mostrando a la vez el nivel de

esfuerzos presente en todos sus elementos, contrario a lo que sucede con los métodos simplificados

los cuales permiten obtener un valor para los efectos globales que ocurren sobre el tanque y que

pueden indicar mediante formulas desarrolladas por correlaciones el nivel de esfuerzos presente en

la zona inferior de las paredes del tanque.

• En los modelos matemáticos se dificulta valorar las imperfecciones geométricas y del material, lo

que ocasiona diferencias con los resultados experimentales.

• Se plantean ciertas dudas en como enfrentar el análisis y diseño de estas estructuras, ya que

comparativamente con el análisis convencional para eventos sísmicos, se considera una

modificación en el valor de la aceleración empleada por un factor de importancia. Si se considera

Mayo/2004 Capitulo 5 – Caso de Estudio 6-2

<!-- p. 74 -->

César A. Velásquez ANÁLISIS HIDRODINÁMICO DE TANQUES DE ALMACENAMIENTO DE LÍQUIDOS
MIC 2004-I-80

que un tanque puede contener millones de litros de líquidos inflamables y no inflamables, volátiles,

explosivos, gases, químicos tóxicos además de agua, la cual puede ser para combatir incendios o

para consumo, todos estos materiales que se almacenan representan un enorme riesgo para la

población y para el medio ambiente.

• Aparte de la anterior se debe considerar el coeficiente de reducción de energía (R), el cual es una

representación de la capacidad de disipación de energía de la edificación al permitir cierto nivel de

daño a los elementos estructurales y entrar al rango inelástico. Debemos cuestionarnos si un

elemento que contiene en su interior sustancias como las mencionadas en el punto anterior puede o

no presentar y soportar cierto nivel de daño, cuanto seria adecuado y según esto determinar un

factor R para realizar el análisis. A criterio del autor la respuesta seria que no se debe tolerar el

daño y al igual que una instalación de energía nuclear no deben fallar jamás y deben permanecer en

buena condición aun cuando la raza humana no este, es un compromiso con el medio ambiente y

con el planeta.

Mayo/2004 Capitulo 5 – Caso de Estudio 6-3

<!-- p. 75 -->

\7. Bibliografía

\1. CAMBRA, Frank J., Earthquake response considerations of broad liquid storage tanks. University

of California, 1982.

\2. Chopra, A. K. Dynamics of Structures – Theory and Applications to Earthquake Engineering.

Prentice – Hall Inc. Englewood Cliffs, NJ, USA. 1998.

\3. Garcia R., Luis Enrique. Dinámica Estructural Aplicada al Diseño Sísmico. Universidad de Los

Andes. Bogotá, Colombia. 1998.

\4. HURTADO, Jorge E., Dinámica Estructural. Universidad Nacional de Colombia, Sede Manizales.

\2000.

\5. YAMÍN, Luis Eduardo. Análisis y Diseño Avanzado de Estructuras, Notas de clase. Universidad

de los Andes 2002.

\6. BERNAL, Carlos E. Elementos Finitos, Notas de Clase. Universidad de los Andes 2003.

\7. AMERICAN PETROLEUM INSTITUTE. Welded Steel Tanks for Oil Storage, API Standard

650, 10th Edition

\8. ASOCIACIÓN DE INGENIERÍA SÍSMICA. Norma Sismorresistente Colombiana, NSR-98 –

Decreto 084/98.

<!-- p. 76 -->

César A. Velásquez ANÁLISIS HIDRODINÁMICO DE TANQUES DE ALMACENAMIENTO DE LÍQUIDOS
MIC 2004-I-80

\9. Mander, J.B., Priestley, M. J. N., Observed Stress-Strain Behavior of Confined Concrete. Journal

of Structural Engineering ASCE. Vol. 114, No. 8, August 1988, pp. 1827-1845

\10. SAP2000 – Integrated Structural Analysis & Design Software, Computers and Structures Inc.,

Berkeley, California, USA, 1997.

\11. ATC-13. Earthquake damage evaluation data for California. Applied Technology Council.

Redwood City, California. USA. 1985

\12. ATC-40. Seismic evaluation and retrofit of concrete buildings. Applied Technology Council.

Redwood City, California, USA. 1996

\13. FEMA-273. NEHRP guidelines for the seismic rehabilitation of buildings. Washington, D.C.:

Building Seismic Safety Council. USA. 1997.

\14. FEMA-356. NEHRP guidelines for the seismic rehabilitation of buildings. Washington, D.C.:

Building Seismic Safety Council. USA. 2000.

RECURSOS ELECTRÓNICOS

\15. HOUSNER, G. W., Earthquake pressures on fluid containers. Caltech 1954.

\16. LIU, He. SCHUBERT, Daniel H., Effects of Nonlinear Geometric and Material Properties on the

Seismic Response of Fluid/Tank Systems. University of Alaska Anchorage.

\17. MALHOTRA, Praveen K., WENK, Thomas, WIELAND, Martin. Simple Procedure for Seismic

Analysis of Liquid-Storage Tanks. Structural Engineering International 3/2000.

\18. MEIER, Stephen W., Upcoming changes to seismic design criteria – 2000.

Mayo/2004 Capitulo 6 – Bibliografía 7-2
