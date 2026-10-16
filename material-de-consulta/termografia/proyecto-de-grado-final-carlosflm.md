---
type: libro
title: "Proyecto de Grado Final - CarlosFLM"
author: "Daniela Ramirez"
categoria: "TERMOGRAFÍA"
paginas: 86
extraccion: "texto"
fuente: "local:E:/MATERIAL DE CONSULTA/TERMOGRAFÍA/Proyecto de Grado Final - CarlosFLM.pdf"
convertido: 2026-10-16
---

# Proyecto de Grado Final - CarlosFLM

> Texto extraído de `TERMOGRAFÍA\Proyecto de Grado Final - CarlosFLM.pdf` (86 páginas, texto). El PDF original está en el disco E: (MATERIAL DE CONSULTA); `<!-- p. N -->` marca el inicio de cada página.

<!-- p. 1 -->

IDENTIFICACIÓN DE PATOLOGÍAS EN FACHADAS DE EDIFICACIONES POR

MEDIO DE LA APLICACIÓN DE TERMOGRAFÍA INFRARROJA: ESTUDIO DE

CASO

Programa de Maestría en Ingeniería Civil

Presentado por:
Carlos Felipe Londoño Marin

Director:
Manuel Alejandro Rojas Manzano

Pontificia Universidad Javeriana Cali
Facultad de Ingeniería y Ciencias

Diciembre de 2024

1

<!-- p. 2 -->

AGRADECIMIENTOS

Quiero dedicar estas palabras a las personas que han sido pilares fundamentales en este

camino de formación académica.

En primer lugar, a mis padres, quienes con su amor incondicional, su apoyo constante y

sus sabias palabras me han enseñado a perseverar y a superar los desafíos que se presentaron en

este proceso. Gracias por creer en mí y por darme las herramientas para alcanzar mis metas. Este

logro también es de ustedes.

A mi novia, quien fue mi compañera incansable durante este viaje. Tu ayuda, paciencia y

compañía fueron un refugio en los momentos más difíciles y una fuente de motivación constante.

Gracias por estar a mi lado y por ser mi mayor apoyo emocional y práctico en este proyecto.

Finalmente, quiero expresar mi profundo agradecimiento a mi director de tesis, quien,

con su guía y conocimiento, me acompañó en este proceso formativo. Su orientación, paciencia y

compromiso fueron esenciales para dar forma a este trabajo, y su ejemplo será siempre una

inspiración en mi vida profesional y personal.

A todos ustedes, mi más sincero agradecimiento. Este logro no habría sido posible sin su

presencia en mi vida.

2

<!-- p. 3 -->

RESUMEN

El desarrollo y aumento de la construcción de edificaciones para suplir las necesidades de

vivienda o infraestructura de trabajo y producción ha conllevado a la búsqueda y avances en

tecnologías para la realización de ensayos no destructivos en las estructuras implementando el

uso de la termografía infrarroja, debido a que no afecta la integridad estructural y puede ser más

rápido y efectivo. Entre las patologías más estudiadas con este tipo de ensayo se encuentran:

humedades y filtraciones, grietas y fisuras, desprendimientos de fachaletas.

El objetivo general de este trabajo fue evaluar el uso de la termografía infrarroja como

técnica para la identificación de patologías en las fachadas de edificaciones. Para el

cumplimiento de este objetivo se siguió la siguiente metodología la cual se dividió en 2 fases:

una primera que consistió en poder calibrar el equipo y realizar pruebas a escala de laboratorio

en placas con patologías inducidas. En una segunda fase, se ejecutó el diagnóstico patológico de

la fachada de un edificio por medio del uso de la cámara termográfica.

Entre los principales resultados obtenidos se identificó en ambos escenarios la

viabilidad de observar en los termogramas las patologías por humedades y desapego de la

fachaleta, donde su identificación es representada por una diferencia de temperatura que puede

variar frente a otros puntos en los termogramas. Por otro lado, se observó que las patologías

por fisuras tras las fachaletas de hasta 2.5cm de profundidad no pueden ser identificados

mediante el uso de termografía infrarroja ya que no se observan variaciones claras en los

termogramas. En conclusión, la termografía infrarroja puede ser aplicada como una

metodología no destructiva para la identificación de patologías como lo son humedades,

filtraciones y desapego de fachaletas.

3

<!-- p. 4 -->

TABLA DE CONTENIDO

\1. INTRODUCCIÓN .......................................................................................................... 6

1.1. Planteamiento del problema y justificación ............................................................ 7

1.2. Alcance del trabajo ................................................................................................. 8

1.3. Pregunta de investigación ....................................................................................... 8

1.4. Objetivos del trabajo ............................................................................................... 8

\2. REVISIÓN BIBLIOGRÁFICA .................................................................................... 10

2.1. Termografía infrarroja (TIR) ................................................................................ 10

2.2. Principios básicos de la termografía infrarroja ..................................................... 11

2.3. Ensayos termográficos .......................................................................................... 13

2.4. Factores que influyen en la medición de radiación infrarrojo .............................. 16

2.5. Ventajas y limitaciones de la termografía infrarroja ............................................. 19

2.6. Termografía aplicada en edificaciones ................................................................. 19

2.7. Patologías y defectos estudiados con termografía infrarroja en construcción ...... 20

2.9. Avances de la termografía infrarroja en América Latina ...................................... 27

\3. METODOLOGIA ......................................................................................................... 28

3.1. Estudio sobre placas .............................................................................................. 29

3.2. Descripción de las placas ensayadas ..................................................................... 32

3.3. Construcción de pruebas y descripción del experimento ...................................... 36

3.4. Estudio de caso ..................................................................................................... 37

3.5. Levantamiento patológico e inspección visual ..................................................... 40

3.6. Incidencia del sol en las fachadas del edificio ...................................................... 45

3.7. Pruebas con la cámara termográfica en el estudio de caso ................................... 48

4

<!-- p. 5 -->

\4. ESTUDIO SOBRE PLACAS ....................................................................................... 52

4.1. Placa con desapego ............................................................................................... 52

4.2. Placa con fisuras ................................................................................................... 54

4.3. Placa con humedades y filtraciones Prueba No 1 ................................................. 57

4.4. Placa con humedades y filtraciones prueba No 2 ................................................. 59

4.5. Resultados y análisis del estudio preliminar sobre placas .................................... 62

\5. ESTUDIO DE CASO ................................................................................................... 64

5.1. Fachada Frontal zona A ........................................................................................ 64

5.2. Fachada frontal zona B ......................................................................................... 67

5.3. Fachada posterior zona A ...................................................................................... 69

5.4. Fachada posterior zona B ...................................................................................... 72

5.5. Resultados y análisis del estudio de caso .............................................................. 75

\6. CONCLUSIONES Y RECOMENDACIONES ........................................................... 77

6.1. Conclusiones ......................................................................................................... 77

6.2. Recomendaciones para trabajos futuros................................................................ 78

\7. BIBLIOGRAFÍA .......................................................................................................... 79

5

<!-- p. 6 -->

\1. INTRODUCCIÓN

Los métodos de detección de patologías tradicionales en revestimientos pueden presentar

varios problemas al momento de su ejecución, algunas de estas son los ensayos destructivos

como lo es el ensayo de percusión, donde con un martillo se golpea una fachaleta y a criterio del

operador se determina si esta presenta alguna patología, donde en la mayoría de los casos se daña

la fachaleta aun así esta no presente patologías incurriendo en costos de reparaciones

innecesarios. Otra de las limitaciones que pueden representar estos ensayos son la accesibilidad a

las zonas de estudio ya que en muchos casos se requiere de andamios o equipos de altura para

estos trabajos, los cuales aumentan costos y múltiples casos no se pueden alcanzar las zonas de

estudio por la geometría de las estructuras. Estas problemáticas han conllevado a la búsqueda y

avances en tecnologías para la realización de ensayos no destructivos en las estructuras

implementando el uso de la termografía infrarroja, debido a que no afecta la integridad

estructural y puede ser mucho más rápido y efectivo. Entre las patologías más estudiadas con

este tipo de ensayo se encuentran: humedades, filtraciones, grietas, fisuras y desprendimientos de

fachaletas.

La aplicación de la termografía infrarroja en este campo de estudio tiene dos ventajas

importantes: la duración del ensayo es corta y proporciona la información de distribución de

temperaturas en una imagen en el rango infrarrojo conocido como termograma (González, 2006).

Estos termogramas pueden ser empleados para realizar un diagnóstico de manera directa. No

obstante, también es posible extraer la información de distribución de temperaturas a través de

programas de post-procesamiento de datos para ejecutar un análisis cualitativo del defecto

observado a través de mapas térmicos 3D o cuantitativo mediante curvas transitorias (Silva

,2020).

La termografía infrarroja se ha convertido en una herramienta para la ingeniería civil,

transformando la manera en que se realizan las inspecciones y mantenimientos de

infraestructuras. Esta tecnología, basada en la detección de radiación térmica, permite obtener

imágenes precisas del estado térmico de los materiales sin necesidad de contacto físico (Mina et

al., 2021). La capacidad para visualizar diferencias térmicas hace que la termografía infrarroja

6

<!-- p. 7 -->

sea particularmente valiosa para identificar y analizar diversos problemas en estructuras y

edificaciones.

En síntesis, la termografía infrarroja proporciona una metodología avanzada y no invasiva

para la inspección y mantenimiento en ingeniería civil. Su capacidad para detectar patologías en

edificaciones, desde problemas en el aislamiento hasta defectos estructurales, contribuye

significativamente a la prevención de daños graves y a la optimización de recursos en la gestión

de infraestructura. Mediante la presente tesis se realizaron diferentes estudios de patologías por

medio del uso de termografía infrarroja, esto con el fin de determinar parámetros para la

identificación de las patologías como lo son: desapego de fachaleta, fisuras tras las fachaletas,

humedades y filtraciones.

Para esto se realizó la construcción de prototipos a escala en el laboratorio de la Pontificia

Universidad Javeriana de Cali, donde se indujeron las patologías de estudio bajo diferentes

condiciones en un ambiente controlado y también se realizó la construcción de dos dispositivos

de calentamiento que ayudaron a simular el calentamiento efectuado por el sol sobre los

edificios. Con los resultados obtenidos en los prototipos a escala se ejecutó el estudio de caso en

el Edificio de Educación Continua que pertenece a la Pontificia Universidad Javeriana de Cali.

Este trabajo presenta una gran importancia para la definición de parámetros que ayuden para la

identificación de las patologías anteriormente mencionadas debido a que en la actualidad en

Colombia no se presentan normas que definan los parámetros para la aplicación de este tipo de

ensayos como en otros países de América latina y el mundo.

1.1.Planteamiento del problema y justificación

En la actualidad muchos de los métodos para la detección de patologías son costosos o

inexactos, un ejemplo de estos es el de percusión donde un operario utiliza un martillo para dar

golpes sobre la fachaleta o cerámica y a criterio del operador se define si esta se encuentra

desprendida o hueca donde el método también puede presentar desafíos en la aplicación ya que

la geometría de la estructura puede presentar limitaciones para la ejecución de las pruebas.

Estas deficiencias justifican el uso de la termografía infrarroja como otra metodología para

la detección de estas patologías ya que se presenta como un método que permite realizar

mediciones remotas y sin contacto, pudiendo mapear una mayor cantidad de zonas en las que

otros métodos pueden tener limitaciones de acceso. Sin embargo, en Colombia aún no se han

7

<!-- p. 8 -->

definido parámetros o normas específicas para la detección de estas patologías por medio del uso

de la termografía infrarroja, por lo que este trabajo pretende realizar la identificación de

parámetros que ayuden a realizar mediciones más exactas utilizando esta metodología.

1.2.Alcance del trabajo

La presente propuesta es el estudio de un caso único localizado en la ciudad de Santiago de

Cali, la selección de la obra se realizó bajo los siguientes criterios: Evidencia de patologías por

humedades o desprendimiento en sus fachadas, edificación en la cual no se hayan ejecutado

remodelaciones en sus fachadas, y que la edificación con más de 10 años de antigüedad. Donde

los resultados obtenidos son válidos para las condiciones particulares del trabajo en donde

influirán los equipos seleccionados para el estudio, las condiciones climatológicas y la

edificación seleccionada para el caso de estudio.

Para la ejecución y definición de los parámetros de análisis del estudio se ejecutaron

previamente pruebas en laboratorio, en las cuales se construyeron 3 placas de mortero cemento

que simulan la superficie de una fachada de edificio donde se simularon 3 condiciones de

patologías (patologías por humedades, patologías por fisuras, patologías por desapego de la

fachaleta o cerámica), se utilizó la cámara FLIR T4XX para ejecutar las mediciones y con estas

obtuvieron los termo gramas que sirvieron para la definición de parámetros en la identificación

de las patologías.

1.3.Pregunta de investigación

¿Como la aplicación de la termografía infrarroja puede ser una herramienta para la detección

de patologías en fachadas de edificaciones?

1.4.Objetivos del trabajo

A continuación, se describen los objetivos desarrollados con la presente propuesta.

Objetivo general

Evaluar el uso de la termografía infrarroja como técnica para la identificación de

patologías en las fachadas de edificaciones.

Objetivos específicos

El objetivo general se alcanzó al desarrollar los siguientes objetivos específicos:

8

<!-- p. 9 -->

• Determinar los parámetros de la termografía infrarroja que sirvan como base para la

evaluación de las manifestaciones patológicas típicas en fachadas de edificaciones.

• Validar la técnica de termografía por medio de ensayos de laboratorio en

prototipos a escala.

• Analizar el potencial del uso de la termografía infrarroja para el diagnóstico

patológico de fachadas en un estudio de caso tipo edificación.

9

<!-- p. 10 -->

\2. REVISIÓN BIBLIOGRÁFICA

En este capítulo se realizó una revisión sistemática acerca de la termografía infrarroja (TIR)

y su importancia, usos y normativas en el área de la ingeniería civil. Toda la información se

obtuvo de bases de datos y repositorios como Google Scholar, Scopus, Web of Science, IEEE

Xplore Digital Library, repositorios institucionales, entre otros. Para la obtención de los artículos

se emplearon durante la búsqueda algunas palabras clave como "termografía infrarroja",

"edificios", "patologías", "no destructivo", "construcción", "aislamiento", "humedad", etc.

2.1. Termografía infrarroja (TIR)

Es un estudio no destructivo (END) que se aplica en edificaciones para verificar,

diagnosticar y controlar fugas de agua y humedades, pérdidas térmicas, fugas de aire, cubiertas,

muros, paredes, techos; de forma rápida y precisa (Pavón, 2017). Esta técnica se ha convertido

en una herramienta en la ingeniería civil, cambiando la manera en que se realizan las

inspecciones y mantenimientos de infraestructuras. Es una tecnología que se basa en la detección

de radiación térmica, la cual permite obtener imágenes precisas del estado térmico de los

materiales sin necesidad de contacto físico (Mina et al., 2021). La capacidad para visualizar

diferencias térmicas hace que la termografía infrarroja sea particularmente valiosa para la

identificación y análisis de diversos problemas en estructuras y edificaciones.

En el ámbito de la ingeniería civil, la termografía infrarroja tiene algunas aplicaciones

cruciales al ser una herramienta altamente eficaz para la investigación del estado estructural de

materiales, así como para la evaluación de daños. Este método al no ser invasivo y sin contacto,

facilita la realización de diagnósticos rápidos y precisos (Rao, 2008). Entre las aplicaciones más

destacadas se pueden encontrar:

\- Detección de Defectos en aislamiento y humedad: permite identificar deficiencias

en el aislamiento térmico de edificaciones. Las imágenes térmicas revelan puntos fríos y

calientes que indican pérdidas de eficiencia energética y problemas en el aislamiento (He

& Zhang, 2020). Además, la termografía es altamente eficaz para la detección de

infiltraciones y acumulación de humedad detrás de revestimientos y techos, lo que facilita

una intervención temprana antes de que estos problemas causen daños estructurales

significativos (Kowalski et al., 2019).

10

<!-- p. 11 -->

\- Inspección de Concreto y Materiales Estructurales: En el caso de las estructuras de

concreto, la termografía infrarroja ayuda a identificar delaminaciones y defectos internos

que no son visibles superficialmente. Estas anomalías térmicas pueden indicar problemas

como la separación de capas o deterioro en la estructura por desprendimientos (Kuhn et

al., 2022). En estructuras metálicas, la tecnología es útil para detectar

sobrecalentamientos que podrían señalar fallos en la integridad del material o en el

sistema de calefacción (Li et al., 2023).

\- Evaluación de Sistemas de calefacción, ventilación y aire acondicionado (HVAC):

La termografía infrarroja también es empleada para la evaluación del rendimiento de los

sistemas de calefacción, ventilación y aire acondicionado. Las imágenes térmicas pueden

detectar fugas en los conductos, problemas en el aislamiento y fallos en los componentes

del sistema, permitiendo una reparación más eficiente y menos invasiva (Li et al., 2023).

En síntesis, la termografía infrarroja proporciona una metodología avanzada y no invasiva

para la inspección y mantenimiento en ingeniería civil. Su capacidad para detectar patologías en

edificaciones, desde problemas en el aislamiento hasta defectos estructurales, contribuye

significativamente a la prevención de daños graves y a la optimización de recursos en la gestión

de infraestructura; aunque hasta ahora los resultados e interpretaciones de las investigaciones

realizadas con este método dependan de las condiciones específicas del objeto al momento de

realizar la evaluación (Fokaides, et.al; 2011).

2.2.Principios básicos de la termografía infrarroja

El proceso de obtención de imágenes térmicas ha experimentado una notable simplificación

en los últimos años, gracias a la disponibilidad de cámaras infrarrojas eficientes y de alta

resolución. Estas cámaras convierten la radiación emitida por las superficies en imágenes

térmicas (FLIR systems, 2016).

2.2.1. El espectro electromagnético y la radiación infrarroja.

El espectro electromagnético abarca todas las formas de radiación electromagnética, que se

clasifican según su longitud de onda y frecuencia como se muestra en la Figura 2. Cada tipo de

radiación presenta características distintivas y aplicaciones específicas en diversos campos de la

ciencia y tecnología (Rojas, 2009).

11

<!-- p. 12 -->

Figura 2. Radiaciones electromagnéticas

Nota. Fuente: Alejandra León Castellá, CIENTEC (s.f).

La radiación infrarroja se encuentra en el rango de longitudes de onda entre los 700 nm y 1

mm; lo que la sitúa entre la luz visible y las microondas en el espectro electromagnético (Rocha,

2017). Según este autor, la radiación infrarroja puede ser emitida por cualquier objeto que tenga

una temperatura superior al cero absoluto (-273.15°C). Esto se debe a la emisión de radiación

térmica, donde la intensidad y longitud de onda de la radiación deben depender directamente de

la temperatura del objeto (Rocha, 2017).

2.2.2. Radiación del cuerpo negro

El cuerpo negro hace referencia a un objeto que absorbe toda la radiación que incide sobre

él, en cualquier longitud de onda. Este término es un concepto netamente teórico para limitar

superiormente la emisión de la radiación, considerándolo así un emisor perfecto (López

Rodríguez, 2010). En cuerpos más fríos que el Sol, este valor emisivo máximo se produce en

longitudes de onda más largas, hasta que se alcanza una temperatura tal que se emite muy poca

energía radiante en el rango visible (Rocha, 2017).

2.2.3. Radiación del cuerpo no negro

En un cuerpo no negro, solamente una parte de la radiación que incide sobre él será

absorbida; el resto se reflejará y se transmitirá. Esto dependerá además de la longitud de onda

(Rocha, 2017).

2.2.4. Medición de temperatura por termografía infrarroja

Las ondas electromagnéticas presentan una amplia gama de longitudes de onda, que pueden

clasificarse en función de la fuente que genera la radiación. Para expresar la longitud de onda en

12

<!-- p. 13 -->

cada una de las distintas regiones espectrales, se emplean diferentes unidades para evitar

números demasiado grandes o pequeños. En este caso, para el infrarrojo la unidad empleada es la
micra (μm=10 -6m) (Rojas, 2009).

2.3. Ensayos termográficos

Al momento de analizar los registros de las cámaras térmicas de la envolvente de los

edificios, la literatura propone dos métodos de medición distintos: termografía infrarroja

cualitativa y cuantitativa. Entre las principales diferencias entre estos dos métodos es la

normativa vigente, que se debe conocer especialmente para la termografía cualitativa. En el

contexto de la norma internacional (International Organization for Standardization, 1998), los

métodos cualitativos son utilizados generalmente para detectar amplias variaciones en las

propiedades térmicas de los componentes que constituyen la envoltura externa de los edificios y

la estanqueidad al aire. Por otro lado, para la determinación del grado de aislamiento térmico y

estanqueidad al aire de una estructura se aplican métodos cuantitativos. A través de métodos

cuantitativos y cualitativos, las irregularidades de la distribución térmica en las superficies se

detectan visual o numéricamente con base en patrones térmicos en los termógrafos (Fox, et.al,

2014).

En cualquiera de los enfoques que se empleen se deben considerar varios factores que

pueden afectar la precisión de las imágenes térmicas y su interpretación en el contexto de

construcción, entre los cuales se encuentran:

\- Emisividad: se reconoce como la capacidad que tiene un material para emitir

radiación térmica, la cual varía según el tipo de material. En construcción, materiales

como concreto, ladrillo y vidrio tienen diferentes emisividades lo cual puede afectar la

precisión de las mediciones (Vollmer & Möllmann, 2017).

\- Condiciones ambientales: la temperatura, humedad y viento pueden influir en

mediciones térmicas. Para obtener resultados precisos, las inspecciones térmicas suelen

realizarse en condiciones estables (Kaplan, 2007).

\- Calibración del equipo: calibrar correctamente la cámara es fundamental para la

termografía cuantitativa; si no se encuentra calibrada adecuadamente los resultados

obtenidos podrían ser incorrectos y afectar de manera negativa las conclusiones

(Maldague, 2001).

13

<!-- p. 14 -->

2.3.1. Análisis cualitativo

Se conoce a la termografía cualitativa por ser más sencilla y fácil de entender; se emplea

cuando se desea obtener datos más superficiales del problema. Este análisis permite, con ayuda

de los termogramas, evaluar sin gran detalle las condiciones térmicas del objeto estudiado

(Barreira, 2004). En construcción se emplea principalmente para la localización de zonas que

cuenten con pérdidas de energía o para la identificación de defectos en el aislamiento. Estos

problemas se identifican en la imagen térmica (termogramas) como áreas de diferente color, que

hacen referencia a variaciones de temperatura superficial (Vavilov & Burleigh, 2020).

Aunque este tipo de termografía cualitativa sólo considera la diferencia de temperatura a

nivel superficial, este análisis puede verificar la existencia o no de patologías en una zona

determinada (Alam et.al, 2016). Para reducir los errores que pueden presentarse en este tipo de

análisis, Barreira (2004) propone que el termógrafo obtenga imágenes de referencia en sitios no

afectados para poder compararlas con las áreas problemáticas en un futuro. El autor reconoce

que este procedimiento se puede tener en consideración siempre que las condiciones del ensayo y

de las fachadas sean las mismas. En casos donde se puede implementar este tipo de método sin la

identificación de la temperatura precisa de la superficie pueden ser vigilancia, inspecciones de

construcción, localización de una fuga de aire, nivel de fluido de un tanque, entre otros (Holst,

2000). Cabe resaltar que la interpretación de los termogramas obtenidos depende además de la

experiencia del operador, ya que no se realizan mediciones numéricas precisas (Usamentiaga et

al., 2014).

En síntesis, el análisis cualitativo se centra en el análisis de la imagen térmica para delatar y

descubrir la existencia de las anomalías y evaluarlas (López, 2013). Este es el tipo de método que

se implementa en primera instancia. Se identifica el problema y a simple vista ya se puede

concluir sobre su origen, por lo que no es necesario la ejecución de un análisis más exhaustivo.

Un punto importante es que en este método no se compensan las imágenes, por lo tanto, se

estudia la temperatura aparente de la superficie (Melgosa, 2011).

2.3.2. Análisis cuantitativo

La termografía cuantitativa se emplea cuando se requiere clasificar la importancia de una

anomalía (Bauer, et.al, 2014). Este tipo de análisis requiere de más tiempo, ya que requiere de

mayor detalle y pruebas más rigurosas. En este método sí se presenta la temperatura real del

14

<!-- p. 15 -->

objeto, por lo que es empleada en actividades de monitoreo y mantenimiento predictivo, al

identificarse una temperatura fuera del rango predefinido (Holst, 2000). Sin embargo, en

comparación con la termografía cualitativa, este método parecer ser más efectivo ya que permite

conocer la temperatura de la superficie (Barreira, 2004). Se debe recalcar que para que las

mediciones sean precisas, se debe calibrar de manera correcta la cámara termográfica, además de

tener en cuenta la emisividad de los materiales y las condiciones ambientales que pueden tener

influencia en las lecturas (Vollmer & Möllmann, 2017).

La termografía cuantitativa se clasifica en dos métodos principales: pasivo y activo, la

termografía infrarroja pasiva se basa en la observación de la radiación térmica natural emitida

por el objeto en estudio, sin necesidad de aplicar estímulos externos. Esta técnica es útil para

monitorear procesos industriales en funcionamiento o para la inspección de estructuras expuestas

a condiciones ambientales que generan gradientes térmicos, como puentes o sistemas eléctricos

(Oh et al., 2013; Kee et al., 2012; Alfredo-Cruz et al., 2015).

Por otro lado, la termografía infrarroja activa requiere la aplicación de una fuente externa de

energía, como pulsos de calor o excitaciones acústicas, para inducir un flujo térmico en el

material. Este método es particularmente eficaz para detectar defectos internos profundos, ya que

el contraste térmico generado facilita la identificación de anomalías subsuperficiales (Maldague,

2001; Meola et al., 2002). la elección entre termografía infrarroja activa y pasiva depende de la

naturaleza del objeto a inspeccionar, la profundidad de los defectos a detectar y las condiciones

operativas del entorno.

Algunos autores como Kylili (2014) afirman que las pruebas cualitativas tienen una gran

ventaja en la detección temprana de anomalías en pinturas y mampostería, las cuales

generalmente se asocian a la acumulación de humedad y moho; destacando además que la

detección temprana de estos defectos ayuda a la prevención de daños irreversibles y proporciona

información importante para la restauración y conservación de las edificaciones. Por otro lado,

Hart (1991) asegura que, en una inspección la primera etapa debe ser de enfoque cualitativo para

identificar detalles ocultos, seguido de la etapa cuantitativa.

En resumen, análisis cuantitativo toma en cuenta la medida de la temperatura para la

determinación de la gravedad de un problema y poder establecer la prioridad de su restauración

(Menéndez et al, 2015). En este método, las conclusiones a las que se lleguen serán basadas en

15

<!-- p. 16 -->

las temperaturas reales de la edificación y teniendo en cuenta algunos parámetros como son la

emisividad; la temperatura aparente reflejada, entre otras, además de comparaciones con estados

anteriores de la misma zona sin alteraciones (Mora y Céspedes, 2014).

2.4. Factores que influyen en la medición de radiación infrarrojo

El empleo de la termografía infrarroja exige gran precisión para la recopilación de datos y

realizar el análisis de los resultados debido a la cantidad de variables que influyen en las

mediciones. Según Pavón (2017), estas variables se dividen en dos grupos principales: aquellas

relacionadas con el equipo y relacionadas con el objeto de estudio.

2.4.1. Variables relacionadas con el equipo

Las variables relacionadas principalmente con el equipo incluyen la resolución geométrica

IFOV (campo de visión instantáneo), la cámara, el enfoque térmico y el ángulo de visión (Pavón,

2017). El campo de visión instantáneo (IFOV), como se muestra en la Figura 3, es la medida que

refleja la capacidad del detector para captar detalles en combinación con el objetivo. La

resolución geométrica, expresada en milirradianes (mrad), determina el tamaño más pequeño de

un objeto que puede ser captado en la imagen del visor, en función de la distancia de medición.

En termografía, este tamaño equivale a un píxel. El valor en mrad indica el tamaño del punto

visible [mm] que ocupa un píxel a una distancia de 1 metro (ITC, 2008).

Figura 3.

Explicación del campo de visión instantáneo (IFOV)

Nota. Fuente: FLIR (2018)

16

<!-- p. 17 -->

El enfoque térmico (thermal tuning, en inglés), se trata de ajustar la escala de color de una

imagen para la optimización del contraste de una anomalía en el objeto analizado (ITC,2008).

Este es de gran importancia, debido a que una imagen que esté mal enfocada no será una imagen

precisa y se dificultará el análisis del termograma; lo que puede provocar en algunos casos

algunos cambios en la precisión de las mediciones, dando como resultado lecturas de

temperaturas distintas a las reales.

Cabe aclarar entonces que es importante comprobar correctamente el IFOV, la resolución de

la cámara y el enfoque térmico, ya que pueden provocar cambios en los valores de temperatura

(Bauer y Pavón, 2015). Además, cuanto mayor sea la resolución de la cámara, mayores serán las

posibilidades de obtener más píxeles sobre el objetivo a una mayor distancia, logrando resultados

precisos. El zoom digital no mejora la exactitud, por lo que es fundamental contar con una

resolución más alta o un campo de visión más reducido (FLIR ,2018).

2.4.2. Variables relacionadas con el objeto de estudio

La detección y evaluación de las variables asociadas al objetivo resultan complejas y

requieren gran atención para obtener termogramas de alta calidad. No prever o medir

incorrectamente estas variables puede causar errores en los termogramas, lo que podría derivar

en valores de temperatura inexactos. Entre las variables más importantes se encuentran la

emisividad, la reflexión y la distancia (Pavón, 2017). Estos parámetros deben ser medidos de

manera correcta para poder obtener termogramas adecuados (Fox et al, 2015).

2.4.2.1. Emisividad

La emisividad (ε), es un parámetro adimensional que se encarga de establecer la relación que

existe entre la cantidad de energía radiada por el cuerpo en estudio y la que emitiría un cuerpo

negro, a la misma temperatura y longitud de onda, presentando valores entre 0 y 1 (Incropera et

al. 2008).

El valor de uno (1) hace referencia al cuerpo negro, conocido como un medio o sustancia

que absorbe toda la energía que incide en él (Avdelidis y Moropoulou, 2003). La emisividad

tiene variaciones con la temperatura, longitud de onda y el ángulo con el que se adquiere la

imagen (Taylor et al, 2014). Se destaca que los materiales empleados en la construcción de obras

civiles en general presentan valores de emisividad superiores a 0,8; lo cual es un punto a favor

17

<!-- p. 18 -->

para la precisión de las mediciones, dado que objetos con mayor emisividad van a reflejar más

radiación a diferencia de su entorno (Maldague, 2001). Por otro lado, los objetos que presentan

una emisividad baja tienden a presentar valores de temperatura similares a los de su entorno

debido a una baja radiación reflejada (ITC, 2008).

2.4.2.2. Reflexión (ρ)

Una de las principales limitaciones de estudios en edificaciones realizados con termografía

es la reflexión que puede provenir tanto del suelo como de edificaciones vecinas, como se

observa en el ejemplo de la Figura 4.

Figura 4.

Presencia de reflexión que afecta a los valores de temperatura de fachada

Nota. Fuente: (Bauer et al., 2015)

Es importante analizar el área alrededor del objeto de estudio, en busca de fuentes de

reflexión. Una forma de identificar estas fuentes es movilizando la cámara termográfica con

respecto al objeto de estudio, cambiar el ángulo en el que se toma la imagen y evaluar si la

región critica de estudio también se mueve; así sabremos entonces que se está produciendo un

efecto de reflexión (Bauer et al, 2015).

Este valor de ρ está influenciado por las características de la superficie, la temperatura y el

tipo de material; en general, las superficies lisas y pulidas reflejan mucho más que aquellas que

son irregulares y no pulidas, incluso si son del mismo material. La temperatura de la radiación

reflejada puede ajustarse manualmente en la cámara termográfica (Pavón, 2017).

18

<!-- p. 19 -->

2.4.2.3. Distancia

Esta variable afecta los termogramas ya que cada píxel del termograma es responsable de

representar un área determinada del objeto de estudio, por lo que, a medida que aumenta la

distancia de la cámara al objeto, cada píxel es responsable de representar un área mayor

(Giménez et al, 2019). Barreira et al (2015) llegaron a la conclusión de que distancias de hasta

10m no tienen una influencia significativa y presentan solo una pérdida en la precisión de la

imagen.

2.5. Ventajas y limitaciones de la termografía infrarroja

Después de lo explicado en los apartados anteriores, se puede llegar a la conclusión de que

la termografía infrarroja tiene gran cantidad de cualidades. Según autores como Mendonça,

Amaral y Catarino (2012), la termografía infrarroja al ser una prueba no destructiva ni invasiva

no requiere contacto directo con el objeto de estudio y tiene la capacidad de análisis de áreas

pequeñas y grandes; es eficaz en términos de trabajos y equipos y se emplea en la detección de

patologías no visibles. Para Mendonça (2005), el uso de la termografía infrarroja tiene un gran

beneficio que es la ausencia de emisión de radiación y la reducción del tiempo de trabajo.

Barreira (2004), también menciona que además de ser una técnica rápida y eficaz; permite

el diagnóstico de patologías a gran escala. El autor también destaca la seguridad que aporta este

método, ya que no se requiere de ningún tipo de plataformas de trabajo ni otros equipos de

medición. Otro punto que destacar en el texto de Barreira (2004) es que la termografía infrarroja

tiene una gran importancia debido a su capacidad para inspeccionar el sistema constructivo en

una fase preliminar, lo que permite tener datos iniciales sobre las patologías de las

construcciones.

A pesar de la gran cantidad de ventajas que presenta la termografía infrarroja, esta también

tiene sus limitaciones, ya que no tiene la capacidad de determinar el espesor y profundidad de las

patologías (Mendonça et al, 2012). Por otro lado, para Pavón (2017), una de las grandes

limitaciones de este método es la reflexión sobre la superficie que está siendo estudiada.

2.6. Termografía aplicada en edificaciones

La termografía infrarroja puede emplearse en varias áreas de la ingeniería civil, entre las que

se destacan la evaluación de las características térmicas de las envolventes de edificaciones

19

<!-- p. 20 -->

(Sandberg et al, 2015), estudio de la eficiencia energética de los edificios, estudio de problemas

en los materiales aislantes, detección de fallas en la adhesión entre elementos (Barreira; De

Freitas, 2007), detección de humedad, detección de elementos estructurales (Weritz et al, 2005),

detección de fisuras, defectos internos y desprendimiento de cerámicas (Pavón, 2017).

Entre la diversidad de aplicaciones de la termografía infrarroja que existe para edificaciones

se puede mencionar la detección de patologías no visibles, así como la identificación de las

causas de patologías visibles (Mendonça et al, 2012). Los autores destacan que esta técnica

puede ser utilizada para:

\- Detección de infiltraciones o fugas de agua

\- Detección de grietas en las estructuras

\- Análisis térmicos de edificaciones

\- Ubicación de redes interiores

Como se mencionó anteriormente, la termografía infrarroja permite la identificación de

patologías y de igual forma permite hacer un mapeo de las zonas afectadas; lo que contribuye al

mantenimiento y restablecimiento del sistema constructivo (Barreira, 2004). El autor también

menciona que este método puede ser aplicado a:

\- Detección de zonas con mal aislamiento en fachadas

\- Detección de problemas en techado

\- Detección de fugas de aire por ventanas

\- Detección de defectos en revestimientos de fachadas

\- Detección de puntos de menor resistencia en ensayos de fuego

\- Evaluación del confort de los revestimientos del suelo

2.7. Patologías y defectos estudiados con termografía infrarroja en construcción

La termografía infrarroja (TIR) hace parte de los estudios no destructivos (END) que han

venido ganando popularidad en el campo de la construcción por su alta capacidad para la

identificación de defectos ocultos en las estructuras, mediante la medición de radiación térmica.

Esta técnica, como ya se ha mencionado en este documento, utiliza cámaras termográficas para

la detección y visualización de variaciones de temperatura en superficies; lo que permitiría la

20

<!-- p. 21 -->

identificación de anomalías que podrían estar asociadas a problemas estructurales como lo son

las grietas, desprendimiento de materiales y presencia de humedad. A continuación, se describe

de manera detallada las patologías más comunes presentadas en construcción y la manera en que

la termografía infrarroja es empleada para su diagnóstico.

2.7.1. Humedades en paredes y techos

Esta patología es una de las más perjudiciales en construcción, debido a que puede afectar la

durabilidad de los materiales (Figura 5) y el confort y salud de quienes ocupan la edificación.

Las fuentes de humedad pueden incluir desde filtraciones de agua hasta condensaciones internas

o fugas en tuberías (Guerrero, 2013). En muchas ocasiones los problemas de humedad no son

visibles hasta el momento en que los daños son significativos, lo cual destaca la importancia de

una detección temprana.

Figura 5. Humedad en techos y paredes

Nota. Fuente: (El País, 2023)

En este caso la termografía infrarroja es una herramienta muy eficaz debido a la manera en

que la presencia de agua afecta la conductividad térmica de los materiales. Según Balaras y

Argiriou (2002), las áreas que presentan humedad van a retener mayor calor que las áreas secas;

mientras que durante la inspección termográfica las zonas húmedas se presentan como áreas más

frías a diferencia del resto de la superficie. Esto es útil generalmente en techos y paredes, donde

la humedad puede estar oculta detrás de revestimientos o en capas internas del material (Figura

6).

21

<!-- p. 22 -->

Figura 6. Humedad en pared de mampostería

Nota. Fuente: (Kominsky et al. 2007 citado por Pavón 2017)

Una de las principales ventajas que presenta la termografía infrarroja en este caso es que

permite la detección de esta patología en su fase inicial, incluso antes de la formación de

manchas visibles o presencia de moho. Esto facilita la corrección temprana de los problemas

para así también prevenir daños estructurales severos y mejorar la eficiencia energética de la

edificación al evitar que el aislamiento térmico se vea comprometido por acumulación de

humedad (Kylili et al, 2014).

2.7.2. Fisuras y grietas estructurales

Las grietas son uno de los defectos que más se presentan en estructuras de edificaciones y se

deben a varios factores, como movimientos diferenciales del terreno, sobrecargas, vibraciones y

cambios térmicos extremos. Esta patología puede comprometer la estabilidad de la estructura de

un edificio, y si no es identificada y corregida a tiempo, puede generar daños mayores. De

manera tradicional, las grietas son detectadas de forma visual, como se muestra en la Figura 7,

aunque es un método que puede pasar por alto algunas fisuras internas o de difícil acceso.

(González, 2020)

22

<!-- p. 23 -->

Figura 7. Fisuras y grietas estructurales en edificios

Nota. Fuente: (PIRESA®,s.f)

La termografía infrarroja es una herramienta eficaz para la detección de grietas por su

capacidad para la identificación de anomalías térmicas. Según Maldague (2001), las grietas

alteran las propiedades térmicas del material, lo cual termina provocando una diferencia de

temperatura en el área que se encuentra afectada en comparación a zonas circundantes. Esto es

debido a la variación que se da en la conductividad térmica, donde el flujo de calor se interrumpe

por la presencia de la patología (grieta), creando así patrones térmicos irregulares visibles en la

imagen infrarroja.

Un buen ejemplo de esta patología se puede observar en una inspección de una pared en

concreto (Figura 8); la termografía infrarroja puede mostrar líneas irregulares que determinan la

ubicación de las grietas, donde las diferencias de temperatura son claramente visibles. Las grietas

pueden aparecer en los termogramas como áreas más frías o cálidas en función de la situación

ambiental al momento de la toma, ya que la acumulación de aire frio o la infiltración de calor a

través de la grieta pueden modificar la temperatura superficial (Balaras & Argiriou, 2002).

23

<!-- p. 24 -->

Figura 8. Grietas ramificadas evaluadas con termografía

Nota. Fuente: (Bauer et al, 2016a).

2.7.3. Desprendimientos de revestimientos

El desprendimiento de revestimiento de las edificaciones es otro defecto común que afecta la

integridad de las construcciones. Revestimientos como ladrillos, azulejos o capas de yeso pueden

ir perdiendo adherencia con el paso del tiempo por fatiga de los materiales, presencia de

humedad o malas prácticas al momento de la instalación (Figura 9). Un desprendimiento

superficial puede no parecer crítico al principio, pero con el tiempo puede llevar a la caída del

material, creando un peligro para quienes transiten constantemente por la zona y afectando la

estabilidad estructural (Freitas et al, 2014).

Figura 9. Desprendimiento fachaletas en ladrillo

Nota. Fuente: (Rtarquitectura, s.f).

24

<!-- p. 25 -->

La termografía infrarroja permite la detección temprana de estos desprendimientos antes de

que sean visibles. De acuerdo con Grinzato, Bison y Marinetti (2002), el aire que se encuentra

atrapado detrás del revestimiento desprendido va a presentar una alteración en el flujo de calor

de esa área, creando un patrón térmico distintivo. En una inspección termográfica, estas áreas

que presentan la anomalía mostraran vacíos o burbujas de aire que son más frías o calientes que

las áreas donde el material se encuentre bien instalado (Figura 10).

Figura 10. Desprendimiento de fachada con revestimiento de mortero

Nota. Fuente: (Mario 2011, citado por Pavón 2017)

La capacidad que tiene la termografía infrarroja para la detección de desprendimientos

presenta varias ventajas. En primer lugar, se destaca que es una técnica no invasiva que no

requiere remoción de partes de la edificación para la inspección. En segundo lugar, permite la

inspección de áreas grandes en un corto periodo de tiempo, lo que hace posible que se

identifiquen defectos en etapas tempranas antes de que se conviertan en un riesgo mayor

(Maldague, 2001).

En conclusión, se puede decir que la termografía infrarroja es una técnica valiosa para el

diagnóstico de patologías en construcción, lo cual permite la detección temprana de las mismas.

Al ser de carácter no invasivo y al tener la capacidad de inspeccionar grandes áreas rápidamente

la convierten en una herramienta esencial para el mantenimiento de edificaciones.

2.8. Normas sobre termografía infrarroja aplicadas en construcción

La Sociedad Estadounidense para Pruebas y Materiales, ASTM, por sus siglas en inglés, es

una entidad sin ánimo de lucro que dedicada a la elaboración y publicación de alrededor de

12,000 normas técnicas, las cuales abarcan procedimientos de prueba y clasificación de

25

<!-- p. 26 -->

materiales para diversas industrias. En Estados Unidos, es común que se cite estas normas

ASTM, siendo numerosas las que abordan los métodos de prueba relacionados con la envolvente

de los edificios. Asimismo, muchas de las normas ASTM vinculadas a la tecnología de

infrarrojos (IR) hacen referencia a la norma ISO 6781-1:2023 de la Organización Internacional

de Normalización (Grey et al, 2017).

Las ASTM relacionadas con la aplicación de termografía infrarroja en la inspección de

edificios son (ASTM INTERNATIONAL, 2023):

\- ASTM C1060 – 11a (2015): Práctica estándar para la inspección termográfica de

instalaciones de aislamiento en cavidades cerradas dentro de la estructura de edificios.

Esta norma se basa en una guía para el uso apropiado de la termografía infrarroja para

inspecciones térmicas cualitativas en muros, techos y suelos, que pueden contener

aislamiento en su interior (Guerrero, C, 2013). Esta normativa se limita a la

construcción con entramado, aunque la termografía infrarroja se puede usar en todos

los tipos de edificios (ASTM International, 2013).

\- ASTM C1153 - 10 (2015): Práctica estándar para localizar humedad en sistemas de

impermeabilización de cubiertas mediante imágenes infrarrojas. Según el texto de

Guerrero (2013), esta normativa explica las técnicas que emplean imágenes

infrarrojas en la noche para la determinación de la ubicación de aislamiento

humedecido en los sistemas de techado que tengan aislamiento encima de la cubierta

en contacto con la impermeabilización.

\- ASTM D4788 - 03 (2013): Método de prueba estándar para la detección de

desprendimientos en tableros de puentes mediante termografía infrarroja. Esto se

logra al medir las diferencias en la temperatura superficial de las estructuras, que

pueden ser causadas por la variación de humedad o por el daño estructural

subyacente, como los desprendimientos.

Normas ISO:

\- ISO 6781-1:2023. Rendimiento de los edificios. Detección de irregularidades de

calor, aire y humedad en edificios mediante métodos infrarrojos. Establece requisitos

y metodologías para servicios de termografía infrarroja para la detección de

irregularidades de calor, aire y humedad en edificios.

26

<!-- p. 27 -->

2.9. Avances de la termografía infrarroja en América Latina

Como se ha mencionado en capítulos anteriores, la termografía infrarroja (TIR), ha surgido

como una herramienta fundamental en la construcción, que permite la evaluación de manera no

destructiva de edificaciones y la identificación de anomalías térmicas que podrían indicar

problemas. En Latinoamérica y especialmente en Colombia, su adopción ha mostrado un

crecimiento notable en las últimas décadas.

En Latinoamérica la TIR ha ido ganando relevancia en el sector de la construcción, en

especial en países como lo son Brasil y Argentina. En este caso, en Brasil aun no existen

normativas específicas que regulen su implementación en las edificaciones, pero se ha recurrido

a estándares internacionales para su aplicación en la detección de patologías (Silva, G, et.al.,

2019). Por otro lado, en Argentina, la termografía infrarroja ha sido empleada para la evaluación

del comportamiento térmico de edificios; lo que permite detectar defectos en la envolvente,

puentes térmicos e infiltraciones de aire y humedad (Larsen et al, 2012).

En el caso de Colombia, la implementación de la termografía infrarroja en la construcción

ha tenido un avance significativo. Esta tecnología se ha utilizado desde hace aproximadamente

30 años para facilitar tareas de mantenimiento y su crecimiento ha sido notable (Serrano et al,

2011). Algunas instituciones académicas como lo es la Universidad del Valle ha realizado

avances a nivel de softwares para el análisis de las imágenes infrarrojas, lo cual permitiría un

análisis de estas imágenes a través de interfaces gráficas (Erazo et al, 2022). Cabe resaltar

además que, en el ámbito industrial, algunas empresas colombianas han adaptado el uso de la

TIR en el área de mantenimiento predictivo. Sin embargo, su uso en otros sectores aún se ve un

poco limitado y se reconoce que es necesario concientizar sobre el uso y beneficios de esta

tecnología, como la mejora en calidad de servicios y reducción de costos (Serrano et al, 2011).

27

<!-- p. 28 -->

\3. METODOLOGIA

A continuación, se presenta el diagrama de la metodología implementada para la ejecución

de este trabajo, el cual se dividió en 3 fases, cada una en función de cada uno de los objetivos

específicos planteados anteriormente.

Figura 11. Diagrama de la metodología de trabajo.

Para la ejecución del trabajo se realizó inicialmente un estudio de la técnica de termografía

infrarroja como se observó en el capítulo anterior de revisión bibliográfica, donde se analizaron

los diferentes factores a tener en cuenta para la aplicación de la técnica, sus limitaciones y

características principales, adicionalmente también se revisaron normas de tipo internacional y

nacional que se tuvieran definidas para estudios con termografía infrarroja.

Finalizada la revisión teórica de la técnica de termografía infrarroja se procedió con la

siguiente fase del trabajo donde la investigación principal se dividió en dos fases, la primera fase

consistió en un estudio preliminar sobre prototipos a escala construidos en el laboratorio de

mezclas de la Pontificia universidad javeriana de Cali, y la segunda fase de la investigación

consistió en un estudio de caso como se muestra a continuación.

28

<!-- p. 29 -->

3.1.Estudio sobre placas

El estudio sobre placas constituye la primera etapa experimental del trabajo la cual se

basó en parte a la metodología implementada por Pavón (2017), en esta se analizó

cualitativamente el comportamiento de defectos, patologías y elementos en los termogramas y

los parámetros termográficos de las principales variables relacionadas con las tres patologías de

estudio (desprendimiento de fachaletas, filtraciones o humedades y fisuras tras las fachaletas).

Para el programa experimental en placas se utilizaron fachaletas del edificio Educación

Continua de la universidad Javeriana de Cali, las cuales están compuestas principalmente de

ladrillo recortado que fueron pegadas a una placa base previamente moldeada en mortero de

cemento y arena.

En estas se indujeron las 3 patologías de estudio (desprendimiento de fachaletas,

filtraciones o humedades y fisuras tras las fachaletas) para intentar analizar las principales

anomalías encontradas en los termogramas, las placas se calentaron artificialmente con lámparas

infrarrojas (Utilizando bombillos de 250 watts en los cuales el 90% de su energía se libera en el

rango infrarrojo como calor) en un flujo directo de 1500 watts y fueron enfriadas de manera

natural.

La primera parte del estudio sobre placas fue cualitativa, donde se analizó que se pueden

evaluar diferentes condiciones patológicas con termografía, y la forma en la que se reflejan en el

termograma con un flujo de calor determinado y con un aumento en el tiempo de exposición. La

segunda parte del estudio sobre placas fue cuantitativa y se revisó el comportamiento de los

parámetros termográficos (Delta-T) en las condiciones propuestas para el experimento.

3.1.1. Materiales y equipos utilizados

Los materiales utilizados para la fabricación de las placas fueron: cemento UG (cemento de

uso convencional que se utiliza en casos donde no se requieren propiedades específicas y arena

(material granulado compuesto por sílice, extraída del rio Cauca). Para este mortero se utilizó un

diseño de mezcla de 1:4, el cual fue incorporado en las formaletas de madera con las medidas de

50x25x4 cm que se fabricaron para el experimento como se muestra en la Figura 12, estas

especificaciones fueron similares a la utilizadas por Pavón (2017) para su estudio sobre placas.

29

<!-- p. 30 -->

Figura 12. Fabricación de probetas en mortero

Para la construcción de todas las placas se utilizaron las mismas fachaletas que tiene

actualmente el edificio del caso de estudio (edificio de educación continua en la universidad

Javeriana de Cali), para esto se usaron las caras de ladrillo (fachaletas) de 20 cm de largo por 10

cm de ancho y 3 cm de espesor, como se muestra en la Figura 13. Donde también se utilizó el

mismo mortero con un diseño de mezcla 1:4 para la pega de fachaletas.

Figura 13. Dimensiones de las fachaletas de estudio

Después de la fabricación, las probetas fueron colocadas en cámara húmeda durante 28

días y luego 3 días dentro de un horno de secado a 50.0°C como se muestra en la Figura 14, esto

con el fin de lograr un buen acabado en la parte superior de la losa sin fisuras y humedades que

30

<!-- p. 31 -->

pudieran afectar los resultados del experimento al igual que se ejecutó en el trabajo de Pavón

(2017).

Figura 14. Placas de mortero: a) fundición y curado y b) secado en horno a 50°C.

a) b)
Se realizó también la fabricación de 2 dispositivos para proporcionar calor a las placas y

fachaletas del experimento como se muestra en la Figura 15, estos se construyeron con 3

bombillos de 250 watts cada uno en los cuales el 90% de su energía se libera en el rango

infrarrojo como calor, estos son utilizados en actividades agrícolas y para el secado de pintura de

vehículos, en conjunto los dos dispositivos generan un flujo de 1500 watts.

Figura 15. Dispositivo de calor fabricados para el experimento.

Para el experimento también se utilizó un termómetro laser convencional el cual utiliza

tecnología de infrarrojos para medir la temperatura de un objeto sin necesidad de tener contacto

con el mismo, manejando un rango de medición entre -20.0°C y 500.0°C y una exactitud de

medida de entre más o menos 2.0°C la cual varía dependiendo de la distancia a la que se

encuentre el objeto al cual se le realiza la medición (Ver Figura 16)

31

<!-- p. 32 -->

Figura 16. Termómetro laser utilizado

El equipo principal para realizar las mediciones y obtener los termogramas de todas las

pruebas y el trabajo de campo fue la cámara FLIR – T 420 (ver Figura 17), la cual maneja una

matriz 320*240 pixeles y un bloque óptico giratorio, su rango de temperatura es de -20.0°C hasta

los 650.0°C y ofrece funciones de grabación de video, almacenamiento en memoria extraíble,

conexión a Wifi y control remoto, la cámara se encontraba calibrada por parte del fabricante

antes de ser utilizada para todas las pruebas ejecutadas.

Figura 17. Cámara FLIR T – 420

Nota. Fuente: FLIR (2018)

3.2. Descripción de las placas ensayadas

La Tabla 1 presenta el resumen del estudio de placa preliminar, donde se pueden observar

las patologías de estudio, condiciones inducidas, que son las modificaciones ejecutadas sobre las

placas para análisis de las patologías definidas, variables y la nomenclatura de cada placa de

estudio.

32

<!-- p. 33 -->

Tabla 1.

Resumen de patologías, defectos o condiciones inducidas y variables.

A partir de lo anterior, los objetivos de estudio preliminar sobre placas fueron:

\- Definir qué tipo de patologías y condiciones inducidas son visibles en el termograma.

\- Determinar cómo aparecen las patologías (zonas frías o calientes) en el termograma.

\- Determinar si las variables definidas generan diferencias en los termogramas.

3.2.1. Placa con desapego

Para la primera placa P1, se localizaron 3 fachaletas separadas 3 cm entre cada una, donde

adicionalmente se recubrieron zonas de 5 cm con cinta de enmascarar para dejar el espacio sin

mortero de pega simulando el desapego, la cinta se localizó en diferentes puntos en cada una de

las fachaletas. Para la fachaleta superior se localizó del lado izquierdo, en la central se ubicó la

cinta en el centro de la fachaleta y en la inferior se ubicó en el lado derecho como se muestra en

la Figura 18 se utilizó aproximadamente entre 1 y 1.5cm de mortero para pega.

Figura 18. Construcción de la placa P1 (fachaleta con desapego): a) marcación de zonas sin

mortero b) aplicación de mortero

a) b)

33

<!-- p. 34 -->

3.2.2. Placa con fisuras

Para la construcción de la segunda placa P2, se ejecutó la inducción de fisuras por medio de

una pulidora en la placa de concreto en la zona donde se ubicaron las fachaletas, estas variaban

con profundidades desde los desde los 5 mm hasta los 2.5 cm, se realizaron 3 cortes horizontales

en el área tras la fachaleta superior (cortes de 5 mm, 1 y 2.5 cm de profundidad), en el área tras la

fachaleta del medio se realizaron 4 cortes verticales (cortes de 5 mm,1, 2 y 2.5 cm de

profundidad), y finalmente para la fachaleta inferior se realizaron 3 cortes transversales (cortes

de 5mm, 1.5 y 2.5cm) como se muestra en la Figura 19.

Figura 19. Construcción de la placa P2 (inducción de fisuras): a) medición de profundidad b)

fisuras finalizadas

a) b)

Para la medición de cada una de las profundidades se utilizó un pie de rey digital esto

para asegurar que todas las profundidades de estudio planteadas fueran correctas, se utilizó entre

1 y 1.5 cm de mortero de pega donde no se cubrió ninguna de las fisuras inducidas para el

estudio como se muestra en la Figura 20 y todas las fachaletas quedaron separadas a 3 cm entre

ellas.

34

<!-- p. 35 -->

Figura 20. Construcción de la placa P2: a) aplicación de mortero b) pega de fachaleta

a) b)

3.2.3. Placa con humedades y filtraciones

Para la construcción de la tercera placa P3, se realizó el delineamiento de una zona de 10 cm

de apertura y un canal para la incorporación de agua en la parte trasera de las fachaletas de 18 cm

de largo, las fachaletas se pegaron sin ninguna separación entre si simulando la pega de las

mismas en el edificio, se utilizó entre 1 y 1.5 cm de mortero de pega y para el área trasera de la

fachaleta inferior se usó pega de manera uniforme con el fin de contrastar los cambios de

temperatura frente a las fachaletas superiores donde se almacenaría el agua incorporada como se

muestra en la Figura 21.

Figura 21. Construcción de la placa P3 (placa con humedades): a) delimitación de la zona b) pega

de fachaleta

a) b)

35

<!-- p. 36 -->

Cabe resaltar que se deben tener en cuenta las filtraciones de agua que se pueden presentar

en las juntas o laterales de la fachada a la hora de la incorporación del agua, esto debido a que no

se realizó ningún tipo de impermeabilización ni sellado con algún producto químico para la

retención del agua en el depósito construido, con el fin de dar una aproximación más real al caso

de estudio.

3.3.Construcción de pruebas y descripción del experimento

Para la ejecución de las pruebas sobre las placas inicialmente se realizó el

posicionamiento de los equipos de calentamiento en el área de pruebas del laboratorio como se

muestra en la Figura 23, para todas las pruebas ejecutadas en el laboratorio las placas recibieron

un flujo directo de 1500 watts, donde se tenía una distancia de 90 cm entre las placas y los

equipos de calor, una apertura de 80 cm entre los equipos de calor, los cuales se posicionaban en

sentido directo a las placas y finalmente las tomas que se realizaban con la cámara y el

termógrafo laser se ejecutaron a una distancia de 130 cm entre las placas y los equipos de

medición como se muestra en diagrama de la Figura 22.

Figura 22. Distancias entre los equipos utilizados en las pruebas

Las placas se ubicaban de manera vertical utilizando ladrillos en la parte posterior como

soporte y así garantizar que la radiación de calor emitida por los equipos llegara de manera

directa sobre las placas con la fachaleta como se evidencia en la Figura 23.

36

<!-- p. 37 -->

Figura 23. Posicionamiento de equipos y encendido de los dispositivos de calentamiento

Ya con los equipos ubicados en la zona de pruebas se indujeron las condiciones de

estudio para cada una de las placas y se realizaron las pruebas específicas, donde para todas las

pruebas se tomaron mediciones tanto de temperatura con el termógrafo laser y con los

termogramas obtenidos con la cámara Flir T-420.las mediciones fueron tomadas en intervalos de

15 min, donde se tomaba una imagen y temperatura inicial y a partir de esto se encendían los

equipos de calentamiento hasta que se llegara a los 40.0°C o más sobre las placas de estudio

como se ejecutó en la tesis de Pavón (2017).

En casi todas las pruebas se registró un periodo de calentamiento de aproximadamente 1

hora donde se alcanzaban los 40.0°C o más sobre las placas y se realizaron mediciones en un

periodo de enfriamiento que oscilaba entre los 45 y 90 minutos donde se alcanzaba la

temperatura ambiente.

3.4.Estudio de caso

La última etapa de este trabajo corresponde al estudio de caso, con el fin de validar los

diferentes parámetros y criterios obtenidos de los experimentos sobre placas, se realizó la

selección de una edificación ubicada en el área de Santiago de Cali para realizar la investigación.

La edificación seleccionada debía cumplir con ciertos criterios como: presentar patologías

de fisuras, desapego de fachaletas, humedades y filtraciones. También debía tener más de 10

años de construcción y no haber sido remodelada o que su fachada no fuera reemplazada.

37

<!-- p. 38 -->

Donde finalmente se realizó la selección del Edificio de Educación Continua de la Pontificia

Universidad Javeriana de Cali, el cual cumplía con todos los criterios anteriores para ejecutar el

estudio y del cual se extrajeron las fachaletas en ladrillo que se utilizaron en la fase experimental

de las placas.

El edificio de Educación Continua fue construido bajo un sistema de pantallas, columnas,

vigas, losa y pórticos en concreto; donde también se presentan elementos de mampostería no

estructural, como los son mochetas y muros en ladrillo que van desde el piso 1 hasta la cubierta,

adicionalmente se presenta un recubrimiento con fachaleta en ladrillo en sus 4 fachadas. A

continuación, se presenta un esquema en la Figura 24 de cómo se encuentra instalada la fachaleta

en múltiples puntos del edificio.

Figura 24. Esquema de fachaleta instalada sobre elemento de concreto en la edificación.

El edificio cuenta con 3 niveles más una cubierta constituida por muros en ladrillo, tejas de

Eternit y barro marcados en color morado en el plano (ver Figura 25). La primera planta del

edificio se utiliza como oficinas de la universidad, donde también se tiene el acceso a las

escaleras que conducen a los pisos superiores, este nivel cuenta también con un espacio

designado para restaurante, salas de reuniones y un cuarto de almacenamiento de equipos como

se muestra en la Figura 26.

38

<!-- p. 39 -->

Figura 25.

Plano arquitectónico de la cubierta del edificio de educación continua.

Figura 26.

Plano arquitectónico de la planta 1 del edificio de educación continua.

En la planta 2 del edificio se encuentran 6 aulas de clase y dos zonas destinadas para baños,

en el plano también se observan las zonas de pasillos y escaleras que conducen a los otros pisos

(ver Figura 27). La tercera planta cuenta con los mismos espacios de la planta 2 y un acceso a la

cubierta del edificio (ver Figura 28).

39

<!-- p. 40 -->

Figura 27. Plano arquitectónico de la planta 2 del edificio de educación continua.

Figura 28. Plano arquitectónico de la planta 3 del edificio de educación continua.

3.5. Levantamiento patológico e inspección visual

Para el estudio de caso se realizó también una inspección e identificación de las zonas del

edificio que presentaban patologías, se ejecutó una inspección en las 4 fachadas donde se

observó el estado actual en el que se encontraban. En la Figura 29 se muestra la fachada frontal

del Edificio de Educación Continua, donde también se presenta el plano arquitectónico de esta

fachada en el cual se marca de color rojo las tejas de la cubierta, de color azul se marca la

40

<!-- p. 41 -->

ubicación de la ventanería, de color morado se marcan los dinteles en concreto, en la parte

central de color rojo se marcan los muros en ladrillo y en la parte blanca se tiene la fachaleta en

ladrillo.

Figura 29. Fachada frontal del Edificio de Educación Continua con su plano arquitectónico: a)

fachada frontal izquierda b) fachada frontal derecha c) plano arquitectónico

a) b)

c)
En la Figura 30 se muestra el estado de la fachada derecha del Edificio de Educación

Continua, donde también se presenta su plano arquitectónico en el cual se marca de color azul

claro y negro las zonas donde se encuentra instalada la fachaleta en ladrillo, en este plano

también se muestra la ubicación de la ventanería en color azul oscuro.

41

<!-- p. 42 -->

Figura 30. a) Fachada lateral derecha del Edificio de Educación Continua b) plano arquitectónico

a) b)
En la Figura 31 se muestra el estado de la fachada izquierda del Edificio de Educación

Continua, donde también se presenta su plano arquitectónico en el cual se marca de color azul

claro, rojo y amarillo las zonas donde se encuentra instalada la fachaleta en ladrillo, en este plano

también se muestra la ubicación de la ventanería en color azul oscuro.

Figura 31. a) Fachada lateral izquierda del Edificio de Educación Continua b) plano

arquitectónico

a) b)
En la Figura 32 se muestra el estado de la fachada posterior del edificio donde también se

muestra el plano arquitectónico en el cual se marca de color azul la ubicación de la ventanería, de

color morado se marcan los dinteles en concreto, en la parte central de color rojo se marcan los

muros en ladrillo y en la parte blanca interna se tiene la fachaleta en ladrillo

42

<!-- p. 43 -->

Figura 32. a) Fachada posterior del Edificio de Educación Continua b) plano arquitectónico

a)

b)

Se realizó también una prueba de percusión tradicional, la cual consistía en golpear

diferentes zonas de la fachada para localizar puntos que presentaran desapego, filtraciones o

daños. Este ensayo se ejecutó utilizando un martillo de goma con el fin de no afectar las

fachaletas que se encontraran en buenas condiciones como, se muestra en la Figura 33. Solo se

pudo ejecutar la prueba en el perímetro del piso 1 debido a que una de las limitaciones de esta

prueba es que se requiere de acceso y contacto con el punto de estudio, ya que no se contaban

con los andamios o equipos de altura necesarios.

43

<!-- p. 44 -->

Figura 33. Prueba de percusión zona con desapego de fachaleta, fachada lateral derecha

Con la inspección visual ejecutada se localizaron zonas en los pisos superiores 2 y 3

donde se observaban patologías como humedades, filtraciones, desapegos y fisuras, como se

muestra en la Figura 34.

Figura 34. Fachada posterior: a) Zona con presencia de humedades fachada posterior piso 3 b)

zona con presencia de desapego piso 2 esquina fachada posterior

a) b)

Ya con estos puntos localizados se procedió a realizar el análisis de incidencia del sol en

todas las fachadas de la edificación, esto con el fin de identificar cuáles son las fachadas donde

se tiene más radiación directa del sol a lo largo del día y poder definir los puntos en los cuales se

utilizó la cámara termografía para realizar las tomas y obtener los diferentes termogramas donde

se pueden evidenciar estas patologías.

44

<!-- p. 45 -->

Se decidió solo utilizar la cámara termográfica para realizar tomas en los pisos superiores,

esto con el fin de aprovechar al máximo las bondades de esta técnica en la cual no se requiere de

equipos de alturas o andamios para poder realizar mediciones de puntos con difícil acceso, por lo

que todas las tomas y termogramas que se obtuvieron para el estudio de caso son de los pisos 2 y

3 de la edificación.

3.6. Incidencia del sol en las fachadas del edificio

Con las zonas del edificio identificadas donde se presentaban las patologías se realizó un

estudio de la incidencia del sol en las fachadas del Edificio de Educación Continua mediante el

uso del programa SunEarthtools, con el cual se puede identificar la trayectoria del sol y la

incidencia de los rayos de luz a lo largo de un día en un punto determinado del mapa global. Para

este caso se localizó un punto central en el programa para cada una de las fachadas del edificio.

Con los puntos localizados se procedió a realizar una configuración del mes y año en el

cual se realizaron las tomas, para este caso se programó en el mes de septiembre de 2024. Un

dato muy importante a la hora de ejecutar el programa ya que la posición del sol y la incidencia

de su luz sobre un punto del mapa global varía según el mes del año, esto se debe a la rotación de

la tierra y un ejemplo claro de este fenómeno es el solsticio de invierno y verano en donde la

tierra cambia de posición por su rotación teniendo una mayor y menor incidencia del sol en

varios puntos del planeta a lo largo de un día.

En la Figura 35 se observa el resultado obtenido por el programa para el mes de

septiembre de 2024 localizando la ubicación sobre la fachada lateral derecha del Edificio de

Educación Continua, en esta se muestra en una línea amarilla la posición del sol a lo largo del día

marcando también las diferentes horas. Se obtiene también con el programa que la mayor

incidencia del sol sobre esta fachada se tiene en el horario de 13:00 a 16:00, dato que también se

puede observar en la línea de trayectoria del sol ya que en horas tempranas de la mañana el sol

no se encuentra en una posición que genere una gran incidencia sobre esta fachada, pasa sobre el

edificio lo que junto a la vegetación que se encuentra cerca a esta fachada puede generar sombra

sobre la misma.

45

<!-- p. 46 -->

Figura 35. Fachada lateral derecha Edificio de Educación Continua

Nota. Mayor incidencia del sol se presenta entre las 13:00 y las 16:00 Fuente: info@sunearthtools.com.

(s. f.).

En la Figura 36 se observa el resultado obtenido por el programa para el mes de

septiembre de 2024 localizando la ubicación sobre la fachada frontal del edificio de educación

continua, en esta figura también se puede observar la trayectoria del sol a lo largo de las

diferentes horas del día marcada sobre la línea amarilla, el programa también nos indica que el

horario de mayor incidencia del sol sobre esta fachada se encuentra entre las 11:00 y las 16:00,

dato que se puede corroborar al observar la trayectoria del sol en la Figura 49.

Figura 36. Fachada frontal Edificio de Educación Continua

Nota. Mayor incidencia del sol se presenta entre las 11:00 y las 16:00 Fuente: info@sunearthtools.com.

(s. f.).

46

<!-- p. 47 -->

En la Figura 37 se observa el resultado obtenido por el programa para el mes de

septiembre de 2024 localizando la ubicación sobre la fachada posterior del edificio de educación

continua, en esta figura también se puede observar la trayectoria del sol a lo largo de las

diferentes horas del día marcada sobre la línea amarilla, el programa también nos indica que el

horario de mayor incidencia del sol sobre esta fachada se encuentra entre las 11:00 y las 16:00,

dato que se puede corroborar al observar la trayectoria del sol en la Figura 50.

Figura 37. Fachada posterior Edificio de Educación Continua

Nota. Mayor incidencia del sol se presenta entre las 11:00 y las 16:00 Fuente: info@sunearthtools.com.

(s. f.).

En la Figura 38 se observa el resultado obtenido por el programa para el mes de

septiembre de 2024 localizando la ubicación sobre la fachada lateral izquierda del edificio de

educación continua, en esta se muestra la en una línea amarilla la posición del sol a lo largo del

día marcando también las diferentes horas. Se obtiene también con el programa que la mayor

incidencia del sol sobre esta fachada se tiene en el horario de 10:00 a 12:00, dato que también se

puede observar en la línea de trayectoria del sol ya que en horas de la tarde el sol no se encuentra

en una posición que genere una gran incidencia sobre esta fachada, pasa sobre el edificio lo que

junto a la vegetación que se encuentra cerca a esta fachada puede generar sombra sobre la

misma.

47

<!-- p. 48 -->

Figura 38. Fachada lateral izquierda Edificio de Educación Continua

Nota. Mayor incidencia del sol se presenta entre las 10:00 y las 12:00 Fuente: info@sunearthtools.com.

(s. f.).

Aunque todas la fachadas del edificio presentan patologías como se evidenció en el ítem

anterior, después de revisar los resultados obtenidos se decidió solo realizar las tomas con la

cámara termográfica sobre las fachadas frontal y posterior ya que en estas se presenta una mayor

incidencia directa del sol a lo largo del día, mientras que en ambas fachadas laterales se presenta

el inconveniente de que la trayectoria del sol pasa por encima del edificio en diferentes horarios

del día lo que puede generar sombra en varios momentos del día, además de esto en estas

fachadas también se presenta mucha vegetación que genera sombra la cual podría alterar los

resultados de las tomas con la cámara termográfica y no se encontraron patologías importantes.

3.7.Pruebas con la cámara termográfica en el estudio de caso

Se seleccionaron 4 puntos para realizar las tomas con la cámara termográfica los cuales se

ubicaban en las fachadas frontal y posterior, de acuerdo con lo definido en el capítulo anterior.

Dos puntos con humedades y filtraciones (uno en la fachada frontal y otro en la posterior) y

también dos puntos donde se evidenciaba desapego (uno en la fachada frontal y otro en la

posterior), estos puntos se encontraban en los pisos 2 y 3, esto con el fin de probar una de las

ventajas del método alcanzando zonas de difícil acceso frente a otras pruebas tradicionales.

En la Figura 39 se observan las dos zonas seleccionadas de la fachada frontal, las cuales

se encontraban entre los pisos 2 y 3 del edificio. En el punto a se muestra la zona de estudio A

donde se evidencian humedades y filtraciones. En el punto b se marca la zona de estudio B

48

<!-- p. 49 -->

donde se evidencia desapego de las fachaletas, finalmente, en la parte inferior en el punto c se

marcan de color rojo las zonas de estudio en el plano de la fachada frontal del edificio.

Figura 39. Fachada frontal: a) zona A con presencia de humedades y filtraciones piso 3 fachada

frontal b) zona B con presencia de desapego entre piso 2 y 3 fachada frontal c) plano arquitectónico de la

fachada frontal donde se marcan la zona A y B.

a) b)

c)
En la Figura 40 se observan los dos puntos seleccionados de la fachada posterior, los

cuales se encontraban en el piso 2 del edificio. En el punto a se muestra la zona A de estudio

donde se evidencia desapego de las fachaletas. En el punto b se marca la zona de estudio B

donde se evidencian humedades y filtraciones, finalmente, en el punto c de la parte inferior se

marcan de color rojo los puntos de estudio en el plano de la fachada posterior del edificio.

49

<!-- p. 50 -->

Figura 40. Fachada posterior: a) zona A con presencia de desapego fachada posterior piso 2 b)

zona B con presencia de humedades y filtraciones, Fachada posterior, piso 2 c) Plano arquitectónico

donde se marcan las zonas A y B.

a) b)

c)

Las tomas con la cámara termográfica se ejecutaron en 2 días diferentes (2 y 7 de

septiembre de 2024). Consistieron en realizar una toma inicial en cada uno de los puntos

seleccionados de las fachadas a las 8:00. Posterior a esto se realizaron tomas en intervalos de 1

hora hasta llegar a la última que se realizó 17:00. En total se realizaron 10 tomas por punto en

cada uno de los días, esto con el fin de obtener la mayor cantidad de datos posibles en los

termogramas y así poder validar los resultados y diferencias de temperatura en las zonas de las

patologías estudiadas.

La Figura 41 muestra el grafico de temperaturas que se registraron en el transcurso del

2/09/2024 para la ciudad de Cali, donde se alcanzó una máxima temperatura ambiente de 33.0°C

50

<!-- p. 51 -->

en el intervalo de las 14:00 y las 15:00, se resalta también que este día no se presentaron

precipitaciones en el transcurso de las tomas con la cámara termográfica.

Figura 41. Gráfico de temperaturas registradas el 2/09/2024 en la ciudad de Cali.

Nota. Fuente: El tiempo histórico en Cali en 2 de septiembre de 2024 (Colombia) - Weather Spark. (s/f).

La Figura 42 muestra el grafico de temperaturas que se registraron en el transcurso del

7/09/2024 para la ciudad de Cali, donde se alcanzó una máxima temperatura ambiente de 33.0°C

a las 15:00, se resalta también que este día no se presentaron precipitaciones en el transcurso de

las tomas con la cámara termográfica.

Figura 42. Gráfico de temperaturas registradas el 7/09/2024 en la ciudad de Cali.

Nota. Fuente: El tiempo histórico en Cali en 7 de septiembre de 2024 (Colombia) - Weather Spark. (s/f).

Se resalta también que todas las tomas se ejecutaron con ángulos de inclinación distintos

ya que el objetivo principal de estas tomas era solamente localizar las áreas marcadas para el

estudio y al tener tomas desde diferentes perspectivas se podría recopilar una mayor cantidad de

datos.

51

<!-- p. 52 -->

\4. ESTUDIO SOBRE PLACAS

En este capítulo se presenta el análisis y los resultados obtenidos de las pruebas sobre placas,

donde también se presentan tablas que muestran todos los datos recopilados en cada una de las

pruebas, se ejecutaron 4 pruebas a lo largo del experimento, 1 para la placa con desapego,1 para

la placa con fisuras y 2 dos pruebas para la placa con filtraciones y humedades.

4.1.Placa con desapego

Para el primer el caso de estudio en la placa P1, se obtuvo el calentamiento de la placa a

más de 40.0°C pasados los 75 min, y el enfriamiento a la temperatura ambiente se consiguió

pasados los 60 min, en la Tabla 2 se pueden observar las mediciones de temperatura que se

obtuvieron con el termógrafo para cada intervalo de tiempo, donde se realizaron mediciones en

el centro de cada fachaleta superior, media e inferior (para las dos primeras mediciones la

temperatura obtenida era igual en los tres puntos por lo que solo se muestra un valor de

temperatura), también en una de las columnas de la tabla se muestra el rango de las imágenes

térmicas (termogramas) que se tomaron en cada intervalo de tiempo.

Tabla 2.

Resumen de los datos obtenidos con el termógrafo y la cámara en la prueba No 1 Sobre la placa P1.

Flujo de calor alto 1500 watss
Fachaleta con Desapego localizado
Tiempo (min) Hora Temperatura °C Camara imágenes
inicio 9:10 22.6 3819 a la 3921
15 9:25 30.4 3822 a la 3826
15 9:40 33.4-33.4-37.1 3828 a la 3831
15 9:55 35.2-34.6-37.6 3832 a la 3834
15 10:10 36,6-36,1-39,6 3835 a la 3839
15 10:25 37.6-36.6-40.8 3838 a la 3842
15 enfriamiento 10:40 32.2-31.6-32.8 3843 a la 3845
15 enfriamiento 10:55 29.8-29.6-30.4 3846 a la 3848
15 enfriamiento 11:10 28.4-28.4-29.4 3849 a la 3851
15 enfriamiento 11:25 27.4-27.7-28 3852 a la 3854

Nota. Se resalta la hora en la que se alcanzan más de los 40°C.

A lo largo de la prueba se evidenció que en las zonas donde se presentaba el desapego

localizado de las fachaletas superior e inferior se presentaba una variación de la temperatura en

52

<!-- p. 53 -->

el ciclo de calentamiento de entre 2.0°C a 3.5°C más frente a los puntos de estas fachaletas

donde se había ejecutado la pega de una manera correcta como se puede apreciar en la Figura 43.

Figura 43. Termogramas sobre las fachaletas superior e inferior de la placa P1 pasados 75

minutos: a) fachaleta inferior b) fachaleta superior

a) b)
De igual manera, se evidenció en los termogramas que en el caso de la fachaleta

central, en la zona donde se localizó el desapego no se presentaron variaciones significativas de

temperatura lo cual pudo ser causado por un movimiento del mortero de pega a la zona central lo

cual generó una distribución más uniforme de la temperatura sobre esta fachaleta alcanzó

también los 40.0°C en su punto de mayor temperatura como se muestra en la Figura 44.

Figura 44. Termograma sobre la fachaleta ubicada en la mitad de la placa P1 pasados 75 minutos.

En el periodo inicial no se evidenciaron mayores cambios de temperatura en ningún

punto de la placa como se muestra en la Figura 45, mientras que en el periodo de enfriamiento se

observó en los termogramas que las fachaletas presentan una pérdida de temperatura mayor

53

<!-- p. 54 -->

frente a la placa en mortero cemento donde se tuvieron variaciones de temperatura de entre 0.4°C

a 1.3°C ver Figura 46.

Figura 45. Termogramas al iniciar la prueba en la placa P: a) temperatura mínima b) temperatura

máxima.

a) b)
Figura 46. Termogramas en el periodo de enfriamiento de la placa P1: a) variación de 1.3°C b)

variación de 0.4°C

a) b)
4.2.Placa con fisuras

Para el segundo caso estudiado sobre la placa P2, se obtuvo el calentamiento de la placa a

más de 40.0° grados Celsius pasados los 60 min, y el enfriamiento a la temperatura ambiente se

consiguió pasados los 60 min ver (Tabla 3). En esta también se pueden observar las mediciones

de temperatura que se obtuvieron con el termógrafo para cada intervalo de tiempo, donde se

realizaron mediciones en el centro de cada fachaleta superior, media e inferior (para la primera

mediciones la temperatura obtenida era igual en los tres puntos por lo que solo se muestra un

54

<!-- p. 55 -->

valor de temperatura), también en una de las columnas de la tabla se muestra el rango de las

imágenes térmicas (termogramas) que se tomaron en cada intervalo de tiempo.

Tabla 3.

Resumen de los datos obtenidos en la prueba No 2 sobre la placa P2

Nota. Se resalta la hora en la que se alcanzan más de los 40°C.

A lo largo de la prueba no se presentaron variaciones de temperatura significativas en los

termogramas para zonas donde se indujeron las fisuras en la placa de mortero cemento, tampoco

se observó en los termogramas de manera clara las fisuras inducidas, ya que solo se presentaba

una distribución de temperatura casi uniforme en cada una de las fachaletas de la placa donde

cada una presentaba una temperatura diferente de calentamiento pero sin marcar los puntos

donde se encontraban las fisuras, como se observa en la Figura 47.

Figura 47. Termograma durante el periodo de calentamiento de la placa P2

55

<!-- p. 56 -->

Al igual que en la fase de enfriamiento de la placa P1, se evidenció también en la placa

P2 que las fachaletas presentan una pérdida de temperatura mayor frente a la placa en mortero

cemento donde tampoco en esta fase se pudieron apreciar en los termogramas las fisuras

inducidas en la placa de mortero cemento como se muestra en la Figura 48, solo se pudo

observar una distribución de temperatura casi uniforme sobre la placa sin variaciones

significativas en los puntos donde se indujeron las fisuras.

Figura 48. Termograma durante el periodo de enfriamiento de la placa P2.

En la Fase inicial de las pruebas tampoco se pudieron observar variaciones de

temperatura en los puntos donde se ejecutaron las fisuras, se observó una distribución de

temperatura muy similar en todas las fachaletas y una disminución de temperatura en la placa lo

cual puede deberse a la diferencia de materiales y su diferente comportamiento térmico como se

observa en la Figura 49.

Figura 49. Termograma al inicio de las pruebas sobre la placa P2

56

<!-- p. 57 -->

Para esta prueba también es muy probable que las fisuras no fueran visibles en los

termogramas debido a que al inducirse y luego pegar la fachaleta el mortero se pudo incorporar

en las fisuras sellándolas y no permitiendo que se reflejaran en los termogramas.

4.3.Placa con humedades y filtraciones Prueba No 1

La placa P3 se dividió en dos pruebas, para la primera se realizó la incorporación de 300

ml de agua al inicio por el canal que se dejó construido en la fachaleta superior y de la mitad,

alcanzados los 40.0°C se incorporaron nuevamente 300 ml de agua y se realizó la toma de los

termogramas.

Para esta prueba se alcanzó la temperatura de 40.0°C o más pasados 60 min desde el

inicio del calentamiento de la placa, y el enfriamiento a temperatura ambiente se logró en 45 min

como se evidencia en la Tabla 4. De igual manera en esta también se observan los datos de

temperatura obtenidos con el termógrafo en el centro de la fachaleta donde se encontraba el

compartimiento de almacenamiento del agua y los rangos de imágenes térmicas que se tomaron

con la cámara termográfica para cada intervalo de tiempo.

Tabla 4.

Resumen de los datos obtenidos en la prueba No3 sobre la placa P3

Nota. Se resalta la hora en la que se alcanzan más de los 40°C.

En esta prueba se pudieron observar en los termogramas las variaciones de temperatura

generadas por las filtraciones sobre la placa al inicio como se muestra en la Figura 50,

alcanzados lo 40.0°C y al incorporar los 300 ml de agua se evidenció en los termogramas una

57

<!-- p. 58 -->

variación de 2.5°C a 5.6°C frente a las zonas donde no se presentaba la acumulación de agua,

tanto en la placa superior como en la inferior Como se muestra en la Figura 51.

Figura 50. Termogramas al inicio de la prueba 3 sobre la placa P3, con la incorporación inicial de

300 ml de agua: a) temperatura máxima b) temperatura mínima.

a) b)

Figura 51. Termogramas al alcanzar los 40.0°C de la prueba 3 sobre la placa P3, con la

incorporación secundaria de 300 ml de agua: a) diferencia de temperatura entre fachada centra y superior

b) diferencia de temperatura entre zona de filtraciones y fachada superior.

a) b)

Ya en el periodo de enfriamiento se observó una disminución de la temperatura en la

placa inferior, esto debido al escurrimiento del agua por las fisuras, donde en el termograma se

pueden evidenciar estas zonas de filtración del agua sobre las fachaletas, como se muestra en la

Figura 52

58

<!-- p. 59 -->

Figura 52. Termogramas durante el periodo de enfriamiento de la prueba No 3 sobre la placa P3:

a) diferencia de temperatura entre la fachaleta del centro y la superior b) diferencia de temperatura entre

la fachaleta superior y la junta entre fachaletas.

a) b)
4.4.Placa con humedades y filtraciones prueba No 2

En la segunda prueba sobre la placa P3, se realizó la incorporación de 100 ml de agua

cada 15 min hasta finalizar la prueba, en este caso se alcanzaron los 40.0°C pasados los 60 min

desde el inicio del calentamiento, donde también el periodo de enfriamiento tuvo una duración

de 60 min hasta lograr la temperatura ambiente (ver tabla 5). En esta tabla también se pueden

observar las mediciones de temperatura que se obtuvieron con el termógrafo para cada intervalo

de tiempo, donde se realizaron mediciones en el centro de cada fachaleta superior, media e

inferior (para la primera mediciones la temperatura obtenida era igual en los tres puntos por lo

que solo se muestra un valor de temperatura), también en una de las columnas de la tabla se

muestra el rango de las imágenes térmicas (termogramas) que se tomaron en cada intervalo de

tiempo.

59

<!-- p. 60 -->

Tabla 5.

Resumen de los datos obtenidos en la prueba No4 sobre la placa P3

Nota. Se resalta la hora en la que se alcanzan más de los 40°C.

En esta prueba se pudieron observar las filtraciones del agua durante todo el transcurso de

la prueba en los termogramas, donde también se evidenciaron en los termogramas variaciones de

temperatura de entre 2.0°C a 3.5°C menos entre las zonas donde no se presentó ningún tipo de

filtración o acumulación de agua y las zonas con filtraciones y acumulaciones de agua, como se

muestra en la Figura 53.

Figura 53. Termogramas durante la prueba 4 sobre la placa P3.

En la etapa inicial de la prueba no se evidenciaron diferencias significativas de

temperatura, solo se observó un cambio de 1.5°C entre el punto de acumulación del agua y la

60

<!-- p. 61 -->

fachaleta inferior, pero esto puede deberse a que el agua podría haber estado a una mayor

temperatura al momento de su incorporación (ver Figura 54). Ya en la etapa de enfriamiento se

observaba una pérdida de calor mayor en las fachaletas de la mitad y en la fachaleta inferior

donde se tenían también diferencias de 2.0°C aproximadamente, de igual manera en estos

termogramas se podía evidenciar mejor las zonas de filtración del agua en las juntas de mortero

entre las fachaletas, como se muestra en la Figura 55.

Figura 54. Termogramas al inicio de la prueba 4 sobre la placa P3: a) diferencia de temperatura

de 0.2°C b) diferencia de temperatura de 1.5°C

a) b)

Figura 55. Termogramas en la etapa de enfriamiento de la prueba 4 sobre la placa P3: a)

diferencia de temperatura de 2.1°C b) diferencia de temperatura de 2.6°C

a) b)

61

<!-- p. 62 -->

Con esta prueba se pudieron comprobar también una variación de temperatura de casi

6.0°C entre la fachaleta con humedad y filtraciones frente a 2 ladrillos que se utilizaron en la

parte inferior de la placa con el fin de conservar su verticalidad frente a las lámparas de calor

como se muestra en la Figura 56.

Figura 56. Termogramas de las fachaletas instaladas en la placa P3 frente a ladrillos secos

durante la prueba.

a) b)

4.5.Resultados y análisis del estudio preliminar sobre placas

Con base a los resultados obtenidos en el estudio preliminar de placas este ítem presenta

las conclusiones respecto a el estudio ejecutado en el laboratorio dando criterios y parámetros

que ayudaron para la ejecución del caso de estudio.

Respecto al comportamiento térmico de las tres patologías estudiadas en este trabajo con

los termogramas generados se concluye que:

\- Humedades, Filtraciones y desapego de la fachaleta se pueden detectar con termografía

infrarroja (esto sólo aplicaría para las condiciones del experimento, sobre fachaleta en

ladrillo como la que se utilizó), debido a que se obtienen diferencias de temperatura que

marcan estos puntos, las cuales se pueden producir por agentes externos como el agua o

en el caso del desapego al no tener una trasmisión de calor frente a otro material como lo

puede ser el concreto.

62

<!-- p. 63 -->

\- No se evidenciaron variaciones en los termogramas para realizar la detección de fisuras

de hasta 2.5 cm de profundidad tras las fachaletas en ladrillo, lo cual podría ser causado

por un error al momento en la pega de la fachaleta ya que las fisuras pudieron ser

rellenadas de mortero, esto podría cambiar en otras condiciones donde se presentarán

humedades ya que un agente externo como el agua podría servir como marcador de la

zona en la fisura que se presente su acumulación.

\- En las zonas donde se presentaba desapego se tenían aumentos de temperatura de 2.0°C a

3.5°C más que en las zonas sin desapego. Lo que podría servir como parámetro para de

detección de esta patología en el estudio de caso.

\- Al incorporar el agua tras las fachaletas, las zonas donde se presentaban acumulaciones

de agua o filtraciones mostraban diferencias de temperatura de entre 2.0°C y 3.5°C,

menos que en zonas donde no se tenía esta patología. Lo que podría servir como

parámetro de detección de esta patología.

\- En los termogramas de la placa P3 se pudieron evidenciar las zonas donde se presentaban

filtraciones de agua, marcadas por la escorrentía sobre las fachaletas en las cuales se

mostraba también una disminución de la temperatura.

\- En la fase de enfriamiento de varias de las pruebas se mostró que las fachaletas presentan

una mayor pérdida de calor en el tiempo que la placa de mortero cemento, donde se

podría evidenciar mejor el estado de una estructura en concreto aplicándola en un edificio

o estructura de mayor tamaño.

63

<!-- p. 64 -->

\5. ESTUDIO DE CASO

En este capítulo se presenta el análisis y los resultados obtenidos en el estudio de caso al

realizar las tomas en el Edificio de Educación Continua con la cámara termográfica.

5.1.Fachada Frontal zona A

Para la zona A localizada en el piso 3 de la fachada frontal donde se presentaban

humedades y filtraciones, se evidenció que al realizar las tomas con la cámara termográfica

desde las 8:00 hasta las 17:00 se tienen diferencias de temperatura entre la zona donde se

presentan las humedades y la fachada en condiciones normales.

Estas diferencias de temperatura van desde los 2.2°C hasta los 8.9°C en las horas donde

se presenta un mayor aumento de la temperatura ambiente (12:00 a 15:00) como se muestran en

los termogramas a continuación.

En la Figura 57 se muestra el termograma obtenido a las 8:00 (lado izquierdo) y el

termograma obtenido a las 9:00 (lado derecho) en la zona A, donde se delimita en ambos con un

recuadro de color rojo la zona de estudio, en el primer termograma se presenta una diferencia de

temperatura de 4.4°C y en el segundo una diferencia de 4.3°C.

Figura 57. Termogramas tomados en la zona A de la fachada frontal: a) toma realizada a las 8:00

b) toma realizada a las 9:00

a) b)
En la Figura 58 se muestra el termograma obtenido a las 12:00 (lado izquierdo) y el

termograma obtenido a las 13:00 (lado derecho) en la zona A, donde se delimita en ambos con

un recuadro de color rojo la zona de estudio, en el primer termograma se presenta una diferencia

de temperatura de 2.7°C entre el punto 3 donde se evidencia humedad y filtraciones y el punto 1

64

<!-- p. 65 -->

que corresponde a una fachaleta en óptimas condiciones. En el segundo se presenta una

diferencia de 8.9°C entre un punto de la zona de estudio donde se presenta humedad y una

fachaleta de la parte superior en condiciones normales.

Figura 58. Termogramas tomados en la zona A de la fachada frontal: a) toma realizada a las

12:00 b) toma realizada a las 13:00

a) b)
En la Figura 59 se muestra el termograma obtenido a las 16:00 (lado izquierdo) y el

termograma obtenido a las 17:00 (lado derecho) en la zona A, donde se delimita en ambos con

un recuadro de color rojo la zona de estudio, en el primer termograma se presenta una diferencia

de temperatura de 2.3°C entre el punto 3 donde se evidencia humedad y filtraciones y el punto 1

el cual corresponde a una fachaleta en óptimas condiciones. En el segundo termograma se

presenta una diferencia de 2.2°C entre un punto de la zona de estudio donde se presenta humedad

y una fachaleta de la parte superior en condiciones normales.

Figura 59. Termogramas tomados en la zona A de la fachada frontal: a) toma realizada a las

16:00 b) toma realizada a las 17:00

a) b)

65

<!-- p. 66 -->

En la Figura 60 se muestra el grafico de variaciones de temperatura que se obtuvieron en

los termogramas, se presenta un dato atípico de 8.9° C a la 13:00, lo cual se debe a que se realizó

una diferencia de temperatura entre un punto de la zona de estudio con humedades y filtraciones

frente a un punto de la parte superior de la fachada el cual pudo haber estado expuesto a una

mayor radiación solar aumentando en un rango mayor su temperatura. Se muestra también un

comportamiento decreciente de los delta-T a través del paso de las horas, lo cual puede deberse a

que con el paso de las horas aumenta la radiación solar acumulada en las fachadas disminuyendo

la brecha de temperaturas entre las zonas con humedades y las zonas en condiciones normales.

Figura 60. Comportamiento del delta-T a través de las horas de la prueba en la zona A.

Esto corrobora los resultados obtenidos en el laboratorio donde las diferencias de

temperatura entre los puntos normales y los puntos donde se presentaban filtraciones y

humedades de las fachaletas variaban entre los 2.0°C y 3.5°C, viéndose resultados muy similares

en este estudio de caso, cabe resaltar que las tomas fueron realizadas en un día donde no se

presentaron condiciones climáticas lluviosas ni precipitaciones sobre el edificio, se presentaron

temperaturas normales para la ciudad de Cali Colombia.

66

<!-- p. 67 -->

5.2.Fachada frontal zona B

Para la zona B localizada entre el piso 2 y 3 de la fachada frontal del edificio de

educación continua se evidencio que en el horario de 8:00 a 17:00, al realizar las tomas con la

cámara termográfica se evidenciaron variaciones de temperatura que van desde los 4.0°C a los

5.6°C en los puntos donde se evidenciaba la patología de desapego.

En la Figura 61 se muestra el termograma obtenido a las 8:00 (lado izquierdo) y el

termograma obtenido a las 9:00 (lado derecho) la zona B, donde se delimita en ambos con un

recuadro de color rojo la zona de estudio, en el primer termograma se presentan diferencias de

temperatura entre un punto de la zona de estudio y dos puntos que no presentan tanta incidencia

del sol directa con el fin de delimitar la zona de estudio al ser la primera toma. En el segundo una

diferencia de 4.5°C entre una fachaleta en condiciones normales y una que presenta desapego.

Figura 61. Termogramas tomados en la zona B de la fachada frontal: a) toma realizada a las 8:00

b) toma realizada a las 9:00

a) b)
En la Figura 62 se muestra el termograma obtenido a las 12:00 (lado izquierdo) y el

termograma obtenido a las 13:00 (lado derecho) en la zona B, donde se delimita en ambos con un

recuadro de color rojo la zona de estudio, en el primer termograma se presenta una diferencia de

temperatura de 5.6°C entre un punto en condiciones normales y uno con desapego. En el

segundo se presenta una diferencia de 4.0°C entre un punto en condiciones normales y uno con

desapego de la zona de estudio.

67

<!-- p. 68 -->

Figura 62. Termogramas tomados en la zona B de la fachada frontal: a) toma realizada a las

12:00 b) toma realizada a las 13:00

a) b)

En la Figura 63 se muestra el termograma obtenido a las 15:00 pm (lado izquierdo) y el

termograma obtenido a las 17:00 pm (lado derecho) la zona B, donde se delimita en ambos con

un recuadro de color rojo la zona de estudio, en el primer termograma se presenta una diferencia

de temperatura de 5.0°C entre un punto en condiciones normales y uno con desapego. En el

segundo se presenta una diferencia de 4.7°C entre un punto en condiciones normales y uno con

desapego de la zona de estudio.

Figura 63. Termogramas tomados en la zona B de la fachada frontal: a) toma realizada a las

15:00 b) toma realizada a las 17:00

a) b)
En la Figura 64 se muestra el grafico de variaciones de temperatura que se obtuvieron en

los termogramas, se presenta un dato atípico de 4.0°C a la 13:00, lo cual se debe a que en este

horario se tenía una menor incidencia de la radiación solar sobre la zona B disminuyendo su

temperatura. Se muestra también un comportamiento ascendente de los delta-T en horas de la

68

<!-- p. 69 -->

mañana y decreciente en horas de la tarde, lo cual puede deberse a que con el paso de las horas

en la mañana aumentaba la radiación solar que recibía la zona de estudio B generando mayores

diferencias de temperatura y en horas de la tarde disminuía la radiación que se recibía

disminuyendo las diferencias de temperatura.

Figura 64. Comportamiento del delta-T a través de las horas de la prueba la zona B.

Con estos resultados se pudieron validar los obtenidos en el laboratorio en donde los

puntos que presentaban desapego en la fachaleta tenían aumentos de temperatura de entre 2.0°C

a 3.5°C frente a los puntos sin esta patología, en el estudio para la zona B se tuvieron diferencias

de temperatura mayores de entre 4.0°C y 5.6°C.

5.3.Fachada posterior zona A

Para el punto A localizado en el piso 2 de la fachada posterior se evidenció que en el

horario de 8:00 a 17:00, al realizar las tomas con la cámara termográfica se presentaron

variaciones de temperatura que van desde los 1.2°C a los 2.9°C en los puntos donde se

evidenciaba la patología de desapego.

En la Figura 65 se muestra el termograma obtenido a las 8:00 (lado izquierdo) y el

termograma obtenido a las 9:00 (lado derecho) en la zona A, donde se delimita en ambos con un

recuadro de color rojo la zona de estudio, en el primer termograma se presentan diferencias de

temperatura de 1.5°C entre un punto con desapego y un fachaleta en condiciones normales. En el

segundo una diferencia de 1.2°C entre una 2 fachaletas en condiciones normales (punto 1 y 3) y

una que presenta desapego (punto 2).

69

<!-- p. 70 -->

Figura 65. Termogramas tomados en la zona A de la fachada posterior: a) toma realizada a las

8:00 b) toma realizada a las 9:00

a) b)
En la Figura 66 se muestra el termograma obtenido a las 13:00 (lado izquierdo) y el

termograma obtenido a las 14:00 (lado derecho) en la zona A, donde se delimita en ambos con

un recuadro de color rojo la zona de estudio, en el primer termograma se presenta una diferencia

de temperatura de 2.3°C entre un punto en condiciones normales y uno con desapego. En el

segundo se presenta una diferencia de 2.9°C entre un punto en condiciones normales y uno con

desapego de la zona de estudio.

Figura 66. Termogramas tomados en la zona A de la fachada posterior: a) toma realizada a las

13:00 b) toma realizada a las 14:00

a) b)

En la Figura 67 se muestra el termograma obtenido a las 16:00 (lado izquierdo) y el

termograma obtenido a las 17:00 pm (lado derecho) en la zona A, donde se delimita en ambos

con un recuadro de color rojo la zona de estudio, en el primer termograma se presenta una

diferencia de temperatura de 2.2°C entre un punto en condiciones normales y uno con desapego.

70

<!-- p. 71 -->

En el segundo se presenta una diferencia de 1.9°C entre un punto en condiciones normales y uno

con desapego de la zona de estudio.

Figura 67. Termogramas tomados en la zona A de la fachada posterior: a) toma realizada a las

16:00 b) toma realizada a las 17:00

a) b)

En la Figura 68 se muestra el grafico de variaciones de temperatura que se obtuvieron en

los termogramas. Se muestra un comportamiento ascendente de los delta-T en horas de la

mañana y decreciente en horas de la tarde, lo cual puede deberse a que con el paso de las horas

en la mañana aumentaba la radiación solar que recibía la zona de estudio A generando mayores

diferencias de temperatura y en horas de la tarde disminuía la radiación que se recibía

disminuyendo las diferencias de temperatura.

Figura 68. Comportamiento del delta-T a través de las horas de la prueba en la zona A.

Nuevamente con estos resultados se pudieron validar también los obtenidos en el

laboratorio, en donde los puntos que presentaban desapego en la fachaleta tenían aumentos de

71

<!-- p. 72 -->

temperatura de entre 2.0°C a 3.5° C frente a los puntos sin esta patología, en el estudio para el

punto A se tuvieron diferencias de temperatura mayores de entre 1.2°C y 2.9° C.

Se resalta también que para la fachada superior no se presentó una incidencia tan directa

del sol en el transcurso de los días donde se realizaron las tomas de datos, por lo que no se

presenta una diferencia de 3.0°C o más de temperatura como en el punto B de la fachada frontal

donde se tuvo mayor incidencia del sol en los días de las tomas.

5.4.Fachada posterior zona B

Finalmente, para la zona B ubicada en el piso 2 de la fachada posterior, se observó que en

el horario de 8:00 a 17:00, al realizar las tomas con la cámara termográfica se evidenciaron

variaciones de temperatura que van desde los 1.9°C a los 7.0°C en los puntos donde se

evidenciaba la patología de filtraciones y humedades frente a los puntos sin esta patología de

referencia.

En la Figura 69 se muestra el termograma obtenido a las 8:00 (lado izquierdo) y el

termograma obtenido a las 9:00 (lado derecho) en la zona B, donde se delimita en ambos con un

recuadro de color rojo la zona de estudio, en el primer termograma se presenta una diferencia de

temperatura de 2.7°C entre una fachaleta en condiciones normales (punto1) y una fachaleta que

presenta humedades (punto 3) y en el segundo una diferencia de 3.2°C.

Figura 69. Termogramas tomados en la zona B de la fachada posterior: a) toma realizada a las

8:00 b) toma realizada a las 9:00

a) b)

En la Figura 70 se muestra el termograma obtenido a las 13:00 (lado izquierdo) y el

termograma obtenido a las 14:00 (lado derecho) en la zona B, donde se delimita en ambos con un

recuadro de color rojo la zona de estudio, en el primer termograma se presenta una diferencia de

72

<!-- p. 73 -->

temperatura de 3.7°C entre una fachaleta en condiciones normales y una fachaleta que presenta

humedades y en el segundo una diferencia de 7.0°C entre estos puntos.

Figura 70. Termogramas tomados en la zona B de la fachada posterior: a) toma realizada a las

13:00 b) toma realizada a las 14:00

a) b)

En la Figura 71 se muestra el termograma obtenido a las 16:00 (lado izquierdo) y el

termograma obtenido a las 17:00 (lado derecho) en la zona B, donde se delimita en ambos con un

recuadro de color rojo la zona de estudio, en el primer termograma se presenta una diferencia de

temperatura de 1.9°C entre una fachaleta en condiciones normales y una fachaleta que presenta

humedades y en el segundo una diferencia de 1.8°C entre estos puntos.

Figura 71. Termogramas tomados en la zona B de la fachada posterior: a) toma realizada a las

16:00 b) toma realizada a las 17:00

a) b)

En la Figura 72 se muestra el grafico de variaciones de temperatura que se obtuvieron en

los termogramas, se presenta un dato atípico de 7.0°C a las 14:00, lo cual se debe a que se realizó

73

<!-- p. 74 -->

una diferencia de temperatura entre un punto de la zona de estudio con filtraciones evidentes las

cuales pueden disminuir la temperatura de este frente a un punto en condiciones normales el cual

está en una de las horas de mayor exposición a la radiación solar. Se muestra también un

comportamiento creciente y decreciente de los delta-T, lo cual puede deberse a que con el paso

de las horas aumenta la radiación en los puntos donde la fachaleta se encuentra sin patologías y

al tener filtraciones evidentes en este punto estas pueden disminuir la temperatura de las

fachaletas contra las que se realiza la diferencia de temperaturas.

Figura 72. Comportamiento del delta-T a través de las horas de la prueba en la zona B.

Con esto nuevamente se corroboran los resultados obtenidos en el laboratorio donde las

diferencias de temperatura entre los puntos normales y los puntos donde se presentaban

filtraciones y humedades de las fachaletas variaban entre los 2.0°C y 3.5°C, viéndose rangos

similares en el estudio la zona B de la fachada posterior, donde se obtuvo un dato de 7.0°C de

diferencia en el horario de mayor incidencia del sol.

Cabe resaltar también que en este punto eran muy evidentes las filtraciones ya que en este

punto se tenía presencia de un desagüe donde a su alrededor se evidenciaban humedades en la

fachaleta y filtraciones, para estas tomas tampoco se presentaron precipitaciones sobre la

edificación.

La incidencia del sol sobre la zona B de la fachada posterior era muy similar a la zona A

de la fachada frontal, la zona B de la fachada frontal era el punto con mayor incidencia del sol

donde se presentaban mayores temperaturas a lo largo del estudio.

74

<!-- p. 75 -->

5.5. Resultados y análisis del estudio de caso

Con base a los resultados obtenidos en el estudio de caso, este ítem presenta las

conclusiones del estudio.

Respecto al comportamiento térmico de las dos patologías seleccionadas para este estudio

de caso (Desapego de fachaletas, Filtraciones y humedades) en los termogramas obtenidos se

concluye que:

• Los desapegos en fachaletas se pueden observar en los termogramas como

las áreas más calientes ya que en estos puntos se puede generar una mayor absorción

de calor frente a puntos en condiciones normales que pueden trasmitir también el calor

al elemento al cual se encuentra adherido.
• Las humedades y filtraciones se pueden evidenciar en los termogramas

como las áreas más frías debido a que en estos puntos se presentan disminuciones de

temperatura por la acumulación de agua.
• En las horas de la mañana cuando la temperatura es menor no se

presentaron mayores variaciones de temperatura tanto para las fachaletas con desapego

como para las fachaletas con humedades.
• En el horario donde se presenta una mayor incidencia del sol sobre las

zonas de estudio fue donde se encontraron valores más elevados de diferencias de

temperatura y es más fácil identificar los puntos con patologías en los termogramas.
• En el horario de la tarde se puede observar en los termogramas la

estructura interna de la edificación en concreto ya que las fachaletas de ladrillo tienden

a conservar por más tiempo el calor como se evidenció en el estudio experimental

sobre placas.
• Se puede utilizar la termografía infrarroja para identificar patologías como

desapego en fachaleta, humedades y filtraciones en puntos de difícil acceso de la

edificación (pisos superiores), lo cual podría disminuir gastos para un levantamiento

patológico y riesgo para los trabajadores que lo ejecuten.
• Se observo un comportamiento decreciente en los delta-T para la zona de

estudio A en la fachada frontal, lo cual puede deberse a que en horas de la mañana se

presenta una menor temperatura en las zonas con presencia de agua acumulada, pero al

75

<!-- p. 76 -->

avanzar las horas y por su ubicación en un piso 3 donde no tiene elementos que puedan

generar sobra, se genera una mayor absorción de radiación solar en todas las fachaletas

disminuyendo los deltas T. En cambio, se observó un comportamiento creciente y

decreciente en los delta-T para la zona de estudio B en la fachada frontal, lo cual puede

deberse que al avanzar las horas aumenta la radiación solar que recibe esta zona, pero

ya en horas de la tarde el sol cambia de posición y al encontrarse en un piso 2 donde

tiene elementos de vegetación que generan sombra, se genera una disminución de las

temperaturas sobre la zona de estudio.
• Para las zonas A y B de la fachada posterior Se presentó un

comportamiento creciente y decreciente en los delta-T, lo cual puede deberse a que en

esta fachada en horas de la mañana se tenía una mayor incidencia de la radiación solar

generando aumento en los delta-T, debido a que se generaba un aumento de

temperatura en las fachaletas con desapego y en las fachaletas en condiciones normales

frente a las que presentaban filtraciones ya que estas mantenían una temperatura

menor. Con el transcurso de tiempo y al cambiar la posición del sol se tenía una menor

incidencia de la radiación solar en estas fachadas generando un comportamiento

decreciente en los delta-T

76

<!-- p. 77 -->

\6. CONCLUSIONES Y RECOMENDACIONES

Con base a los resultados obtenidos en el estudio experimental y el estudio de caso, este

capítulo las conclusiones del trabajo y recomendaciones que se pueden aplicar para futuros

trabajos donde se implemente el uso de la termografía infrarroja para la detección de patologías

en fachadas de edificaciones.

6.1.Conclusiones

Respecto al comportamiento térmico de las dos patologías seleccionadas para este trabajo

en los termogramas obtenidos tanto en el estudio experimental como en el estudio de caso se

concluye que:

\- Se aplicó la técnica de termografía infrarroja mediante la construcción de prototipos a

escala donde se pudieron evidenciar las patologías por desapego de fachaleta, humedades

y filtraciones en los termogramas obtenidos. En estas pruebas no se pudo observar la

patología de fisuras de hasta 2.5cm tras las fachaletas ya que no marcaban ninguna

anomalía o se mostraba alguna referencia de estas zonas en los termogramas.

\- Se podría definir como una variable para la identificación de desapego de fachaleta las

áreas o puntos que presenten una variación de temperatura superior de entre 2.0°C y

4.0°C más frente a la temperatura promedio que se presente en la edificación al momento

de realizar el termograma como se pudo observar en el estudio de caso. También para las

humedades o filtraciones áreas o puntos que presenten una variación de temperatura

inferior de entre 2.0°C y 4.0°C menos frente a la temperatura promedio que se presente

en la edificación al momento de realizar el termograma.

\- Por medio del estudio de caso se pudo evidenciar que el uso de la de la termografía

infrarroja para identificar patologías como desapego en fachaleta, humedades y

filtraciones en puntos de difícil acceso de la edificación (pisos superiores), lo cual podría

disminuir gastos para un levantamiento patológico y riesgo para los trabajadores que lo

ejecuten. También se pueden evidenciar áreas y puntos exactos de estas patologías para

realizar sus correcciones sin tener que intervenir toda la estructura los que podría ayudar

a disminuir costos de mantenimiento.

77

<!-- p. 78 -->

6.2.Recomendaciones para trabajos futuros

Con base a los resultados obtenidos en el estudio experimental y el estudio de caso, este ítem

presenta las recomendaciones aplicables a futuros estudios. Respectó al comportamiento térmico

de las patologías estudiadas en este trabajo:

\- Realizar la inducción de las fisuras directamente en la parte frontal de la fachaleta para

evitar la incorporación de mortero que pueda cubrir las fisuras y no dejarlas visibles en

los termogramas, donde también al incorporar agua se podrán analizar las marcaciones

que se podrían generar en los termogramas.

\- Evaluar la recolección de datos en días donde se presenten precipitaciones de agua, esto

con el fin de observar el cambio que un factor externo puede generar en las mediciones

de los termogramas y como se podría presentar la marcación de estas patologías en los

termogramas.

\- Utilizar sensores térmicos que puedan instalarse en los lugares de estudio esto con el fin

de obtener una mayor cantidad de información y realizar análisis mas detallados en las

zonas que presenten patologías.

\- Evaluar otros tipos de patologías que se puedan presentar en fachadas de edificaciones

por medio del uso de la termografía infrarroja.

\- Realizar la construcción de muretes a escala e inducir las patologías en un ambiente

controlado, donde se pueda realizar una recopilación y análisis de datos en estas

estructuras.

78

<!-- p. 79 -->

\7. BIBLIOGRAFÍA

Alam, F. W. A., et al. (2016). Potencial da termografia infravermelha na detecção de

manifestações patológicas ocultas ocasionadas pela umidade acidental em paredes de

alvenarias cerâmicas com revestimento de argamassa e pintura. Revista de Arquitetura

IMED, 5(1), 28–47.

Alfredo-Cruz, J., et al. (2015). La termografía infrarroja como un ensayo no destructivo para la

inspección de puentes de concreto armado: Revisión del estado del arte. Recuperado de

https://www.scielo.org.mx/scielo.php?pid=S2007-68352017000300200&script=sci_arttext

Angeliki Kylili, Paris A. Fokaides, Petros Christou, Soteris A. Kalogirou, (2014). Infrared

thermography (IRT) applications for building diagnostics: A review, Applied Energy,

134, 531-549, ISSN 0306-2619, https://doi.org/10.1016/j.apenergy.2014.08.005.

ASTM INTERNATIONAL (2023). Standard Practice for Thermographic Inspection.

https://www.astm.org/c1060-11ar15.html

Avdelidis, N. P., & Moropoulou, A. (2003). Emissivity considerations in building thermography.

Energy and Buildings, 35(7), 663–667.

Balaras, C. A., & Argiriou, A. A. (2002). Infrared thermography for building diagnostics.

Energy and Buildings, 34(2), 171-183. https://doi.org/10.1016/S0378-7788(01)00105-0

Barreira, E., Almeida, R. M. S. F., Freitas, V. P., & Soares, T. (2015). Sensitivity analysis of

quantitative infrared thermography. 1st International Symposium on Building Pathology, 6.

Barreira, E., & de Freitas, V. P. (2007). Evaluation of building materials using infrared

thermography. Construction and Building Materials, 21(1), 218–224.

Barreira, E., & Almeida, R. M. S. F. (2015). Drying evaluation using infrared thermography.

Energy Procedia, 78, 170–175.

Barreira, E. S. B. M. (2004). Aplicação da termografia ao estudo do comportamento

higrotérmico dos edifícios. Dissertação de mestrado, Faculdade de Engenharia, Universidade

do Porto.

79

<!-- p. 80 -->

Bauer, E., et al. (2014). Critérios para a aplicação da termografia de infravermelho passiva

como técnica auxiliar ao diagnóstico de patologias em fachadas de edifícios. Revista

Politecnica (Bahia), 21, 266–277.

Bauer, E., & Pavón, E. (2015). Termografia de infravermelho na identificação e avaliação de

manifestações patológicas em edifícios. Concreto e Construções: Requisitos de projeto,

normalização e execução para estruturas com longa vida útil, 93–98.

Bauer, E., Pavón, E., Pereira, C. H. F., & Nascimento, M. L. M. (2016a). Criteria for

identification of ceramic detachments in building facades with infrared thermography.

Recent Developments in Building Diagnosis Techniques.

Erazo, J. (2022). El ensayo no destructivo usando termografía infrarroja en el mundo y en

América Latina: Una Revisión. Revista Universidad Tecnológica de Pereira.

https://doi.org/10.22517/23447214.24717

FLIR Systems, Inc. (2016). FLIRT4xx series. User´s manual.

Flores Larsen, S. E., & Hongn, M. E. (2012). Termografía infrarroja en la edificación:

aplicaciones cualitativas. Avances en Energías Renovables y Medio Ambiente, 16, 25–32.

Flores, S; Hongn, M (2012). Infrared thermography in buildings: qualitative applications.

Revista: Avances En Energias Renovables y Medio Ambiente. Asociación Argentina de

Energía Solar. 16; -1-2012; 25-32. https://ri.conicet.gov.ar/handle/11336/14563

Fox, M., Coley, D., Goodhew, S., & De Wilde, P. (2014). Thermography methodologies for

detecting energy related building defects. Renewable Sustainable Energy Reviews, 40, 296–

\310. https://doi.org/10.1016/j.rser.2014.07.188

Fox, M., Coley, D., Goodhew, S., & De Wilde, P. (2015). Time-lapse thermography for building

defect detection. Energy and Buildings, 92, 95–106.

Freitas, J. G., Carasek, H., & Cascudo, O. (2014). Utilização de termografia infravermelha para

avaliação de fissuras em fachadas com revestimento de argamassa e pintura. Ambiente

Construído, 14(1), 57-73.

80

<!-- p. 81 -->

Gimenez, L. (2019). Metodologia de inspeção e análise de termogramas para estudo de

fachadas em revestimento cerâmico. Universidade De Brasília. faculdade de tecnologia

departamento de engenharia civil e ambiental.

González, D. A. (2006). Contribuciones a las técnicas no destructivas para evaluación

y prueba de procesos y materiales basadas en radiaciones infrarrojas [Tesis de

Doctorado, Universidad de Cantabria] Archivo digital.

https://repositorio.unican.es/xmlui/handle/10902/1130

González, J. (2020). Aplicaciones con termografía Infrarroja: caracterización de grietas

verticales y medida de la difusividad térmica. [Tesis de doctorado, Politécnico Nacional

unidad Mérida, Yucatán, México]. Archivo digital

https://repositorio.cinvestav.mx/bitstream/handle/cinvestav/3393/SSIT0016641.pdf?sequ

ence=1

Grey, C; Wartman, E. (2017). Infrared Technology application in Building Envelopes:

Applications, ASTM Standards, and Limitations. ITC User Conference. Archivo digital

https://www.sgh.com/wp-content/uploads/2021/08/11_grey.pdf

Grinzato, E., Bison, P. G., & Marinetti, S. (2002). Monitoring of ancient buildings by the thermal

method. Journal of Cultural Heritage, 3(1), 21-29. https://doi.org/10.1016/S1296-

2074(02)01159-7

Guerrero, C (2013). “Evaluación de la Aplicabilidad de la Técnica de la Termografía Infrarroja

al Reconocimiento del Estado de Elementos de Hormigón”. Universitat Politecnica de

Catalunya. Barcelona.

https://upcommons.upc.edu/bitstream/handle/2099.1/19610/CelyGuerrero_TFM.pdf?sequ

ence=1&isAllowed=y

Hart, J. M. (1991). A practical guide to infra-red thermography for building surveys. Building

Research Establishment.

He, X., & Zhang, M. (2020). Thermography in Civil Engineering: Principles and Applications.

Springer.

Holst, G. C. (2000). Common sense approach to thermal imaging. JCD Publishing.

81

<!-- p. 82 -->

Incropera, F. P., & DeWitt, D. P. (1999). Fundamentos de transferencia de calor 4ª edicion.

Pearson Educación.

https://www.academia.edu/36019670/Fundamentos_de_transferencia_de_calor_y_de_m

asa_4ta

Incropera, P. I., Dewitt, D. P., Bergman, T. L., & Lavine, A. S. (2008). Fundamentos de

transferência de calor e de massa. LTC. Rio de Janeiro.

International Organization for Standardization. (1998). Thermal insulation — qualitative

detection of thermal irregularities in building envelopes — infrared method.

ITC. (2008). Thermografia - Manual do curso (Nível 1). Sorocaba-SP: Infrared Training Center.

Kaplan, H. (2007). Practical Applications of Infrared Thermal Sensing and Imaging Equipment

third edition. SPIE Press. https://doi.org/10.1117/3.725072

Kee, S., et al. (2012). La termografía infrarroja como un ensayo no destructivo para la

inspección de puentes de concreto armado: Revisión del estado del arte. Recuperado de

https://www.scielo.org.mx/scielo.php?pid=S2007-

68352017000300200&script=sci_arttext

Kowalski, T., Lander, H., & Hughes, M. (2019). Infrared Thermography for Building and

Structural Inspection. Wiley-Blackwell.

Kuhn, R., Riedel, R., & Müller, J. (2022). Advanced Infrared Thermography Techniques. CRC

Press.

Kylii, A., Fokaides, P. A., Christou, P., & Kalogirou, S. A. (2014). Infrared thermography (IRT)

applications for building diagnostics: A review. Applied Energy, 134, 531-549.

Li, Y., Zhang, H., & Chen, L. (2023). Innovations in Infrared Thermography for Civil

Engineering. Elsevier.

López Davó, J. (2013). Apuntes de aplicaciones de la termografía infrarroja en la edificación.

Curso de manejo de la cámara termográfica. Colegio Oficial de Aparejadores y Arquitectos

Técnicos.

82

<!-- p. 83 -->

López Rodríguez, G. (2010). Aplicación de la Termografía Infrarroja en la Evaluación No

Destructiva de Estructuras de Madera. Valladolid: Universidad de Valladolid. Tesis

Doctoral.

Maldague, X.P.V. (2001). Theory and Practice of Infrared Technology for Nondestructive

Testing. Wiley-Interscience. https://www.abebooks.com/9780471181903/Theory-

Practice-Infrared-Technology-Nondestructive-0471181900/plp.

Maldague, X. (2001). Infrared thermography: Recent advances and future directions. Infrared

Physics & Technology, 43(3), 187-199. https://doi.org/10.1016/S1350-4495(01)00013-3.

Melgosa Revillas, S. (2011). Guía de la termografía infrarroja: Aplicaciones en ahorro y

eficiencia energética. FENERCOM.

Menéndez Suárez, A. I., & Menéndez Suárez, I. (2015). Rehabilitación energética de edificio

catalogado como bien de interés cultural (BIC). Eficiencia Integral Constructiva.

Recuperado de http://docplayer.es/10584637-Casa-alvarez-mendoza-1914-rehabilitacion-

energetica-de-edificio-catalogado-como-bien-de-interes-cultural-bic.html.

Mendonça, L. V., Amaral, M. M., & Caratino, P. S. (2012). Termografia por infravermelhos

como ferramenta para auxílio à inspeção e manutenção dos edifícios. Jornadas de

Engenharia de Manutenção, Lisboa.

Meola, C., et al. (2002). Active thermography for the detection of defects in composite materials.

Composites Science and Technology, 62(3-4), 463-472. https://doi.org/10.1016/S0266-

3538(01)00179-3.

Mina, R., Sullivan, J., & Williams, P. (2021). Applications of Infrared Thermography in

Infrastructure. Academic Press.

Mora, R. T., & Céspedes, M. F. (2014). Sistemas de Información Geográfica en la gestión de la

edificación. Grado en Arquitectura Técnica.

Neita, L. Y. & Peña, E. O. (2014). Principios básicos de la termografía infrarroja y su

utilización como técnica para mantenimiento predictivo. Recuperado de:

http://hdl.handle.net/20.500.11912/1561.

83

<!-- p. 84 -->

Nuno, R. (2017). Diagnóstico de Patologias na Construção Apoiada na Análise Termográfica.

Instituto Superior de Engenharia de Lisboa.

Oh, S., et al. (2013). Passive thermography for the detection of defects in concrete structures.

Construction and Building Materials, 40, 1-8.

https://doi.org/10.1016/j.conbuildmat.2012.09.014.

Paris A. Fokaides, Soteris A. Kalogirou. (2011). Application of infrared thermography for the

determination of the overall heat transfer coefficient (U-Value) in building envelopes.

Applied Energy. Volume 88, Issue 12. Pages 4358-4365.

https://doi.org/10.1016/j.apenergy.2011.05.014.

Pavón de la FÉ, E. (2017). Critérios e padrões de comportamento para avaliação de

descolamentos cerâmicos com termografia de infravermelho.xxii, 227 f., il. Tese [Doutorado em

Estruturas e Construção Civil—Universidade de Brasília, Brasília].

http://www.realp.unb.br/jspui/handle/10482/31912

Rao, P (2008). Infrared termography and its applications in civil engineering. The Indian

Concrete Journal.

https://www.researchgate.net/publication/237671448_Infrared_thermography_and_its_ap

plications_in_civil_engineering

Rojas, K. (2009). Radiación electromagnética. Universidad Pontificia Bolivariana.

https://repository.upb.edu.co/bitstream/handle/20.500.11912/432/digital_17516.pdf?sequenc

e=1&isAllowed=y

Sandberg, M., Mattsson, M., Wigö, H., Hayati, A., Claesson, L., Linden, E., & Khan, M. A.

(2015). Viewpoints on wind and air infiltration phenomena at buildings illustrated by field

and model studies. Building and Environment, 92, 504–517.

Serrano, L., & Núñez, A. (2011). Estado del arte de la termografía infrarroja como herramienta

en los procesos industriales. Universidad Pontificia Bolivariana, Bucaramanga. Recuperado

de

https://repository.upb.edu.co/bitstream/handle/20.500.11912/1644/digital_21065.pdf?utm_s

ource=chatgpt.com

84

<!-- p. 85 -->

Silva, (2012). Diagnóstico de patologías en fachadas mediante termografía. Maestría. Ingeniería

Civil. Universidad de Oporto.

Silva, G. (2020). APLICACIÓN DE TERMOGRAFÍA INFRARROJA PARA EL DIAGNÓSTICO

ESTRUCTURAL DE EDIFICACIONES HISTÓRICAS DE ADOBE Y QUINCHA [Tesis de

pregrado, PONTIFICIA UNIVERSIDAD CATÓLICA DEL PERÚ]. Lima.

https://tesis.pucp.edu.pe/repositorio/handle/20.500.12404/16698

Silva, G. P., Batista, P. I. B., & Povóas, Y. V. (2019). Uso de termografía infrarroja para

estudiar el desempeño térmico de paredes: una revisión bibliográfica. Revista ALCONPAT,

9(2), 117–129.http://dx.doi.org/10.21041/ra.v9i2.341

Taylor, T., Counsell, J., & Gill, S. (2014). Combining thermography and computer simulation to

identify and assess insulation defects in the construction of building façades. Energy and

Buildings, 76, 130–142.

Usamentiaga, R., Venegas, P., Guerediaga, J., Vega, L., & Molleda, J. (2014). Infrared

Thermography for Temperature Measurement and Non-Destructive Testing. Sensors,

14(7), 12305-12348. doi:10.3390/s140712305

Vavilov, V.P., & Burleigh, D.D. (2020). Infrared Thermography and Thermal Nondestructive

Testing. Springer. https://doi.org/10.1007/978-3-030-48002-8

Vollmer, M., & Möllmann, K.P. (2017). Infrared Thermal Imaging: Fundamentals, Research

and Applications. John Wiley & Sons.

https://onlinelibrary.wiley.com/doi/book/10.1002/9783527693306

Weritz, F., Arndt, R., Rühe, K., & Zinn, W. (2005). Active thermography in material research

and production monitoring. Insight, 47(4), 191–194.

85

<!-- p. 86 -->

86
