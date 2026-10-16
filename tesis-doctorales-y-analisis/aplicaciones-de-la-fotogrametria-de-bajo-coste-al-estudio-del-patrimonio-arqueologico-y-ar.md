---
type: libro
title: "aplicaciones de la fotogrametría de bajo coste al estudio de patrimonio arqueológico y arquitectónico"
author: "Usuario de Windows"
categoria: "Tesis doctorales y análisis"
paginas: 224
extraccion: "mixto: 12 páginas por OCR (spa)"
fuente: "local:E:/Biblioteca digital/Tesis doctorales y análisis/Aplicaciones de la fotogrametría de bajo coste al estudio del patrimonio arqueológico y arquitectónico.pdf"
convertido: 2026-10-13
---

# aplicaciones de la fotogrametría de bajo coste al estudio de patrimonio arqueológico y arquitectónico

> Texto extraído de `Tesis doctorales y análisis/Aplicaciones de la fotogrametría de bajo coste al estudio del patrimonio arqueológico y arquitectónico.pdf` (224 páginas, mixto: 12 páginas por OCR (spa)). El PDF original está en el disco E: (Biblioteca digital); `<!-- p. N -->` marca el inicio de cada página.

<!-- p. 1 -->

TESIS DOCTORAL

APLICACIONES DE LA
FOTOGRAMETRÍA DE BAJO
COSTE AL ESTUDIO DE
PATRIMONIO ARQUEOLÓGICO
Y ARQUITECTÓNICO

Simón Peña Villasenín

ESCOLA DE DOUTORAMENTO INTERNACIONAL

PROGRAMA DE DOUTORAMENTO EN ENXEÑARÍA PARA O DESENVOLVEMENTO
RURAL E CIVIL

SANTIAGO DE COMPOSTELA / LUGO

2019

<!-- p. 2 -->



<!-- p. 3 -->

AUTORIZACIÓN DE LOS DIRECTORES DE LA
TESIS

Dra. Dña. Mª Luz Gil Docampo y Dr. D. Juan Ortiz Sanz,
Profesores Titulares del Departamento de Ingeniería
Agroforestal de la Universidad de Santiago de Compostela
Como Directores de la Tesis Doctoral titulada:
APLICACIONES DE LA FOTOGRAMETRÍA DE BAJO
COSTE AL ESTUDIO DE PATRIMONIO ARQUEOLÓGICO
Y ARQUITECTÓNICO.

Por la presente DECLARAMOS:
Que la tesis presentada por D. Simón Peña Villasenín
Es idónea para ser presentada, de acuerdo con el artículo 41
del Reglamento de Estudios de Doctorado.

Lugo, 1 de Julio de 2019.

Fdo. Dra. Dña. Mª LUZ GIL DOCAMPO

Fdo. Dr. D. JUAN ORTIZ SANZ

<!-- p. 4 -->



<!-- p. 5 -->

AGRADECIMIENTOS

Me gustaría que estas líneas sirvieran para expresar mi más
profundo y sincero agradecimiento a todas aquellas personas que con
su ayuda han colaborado en la realización de la presente tesis doctoral,
en especial a los directores Dra. MªLuz Gil y Dr. Juan Ortiz, por la
orientación, el seguimiento y la supervisión continua de la misma, pero
sobre todo por la motivación y apoyo recibidos a lo largo de estos años.

De forma especial quiero agradecer a mis padres, porque siempre
me han ayudado y apoyado en todas mis decisiones y porque han sido
y son un ejemplo y referencia; al resto de mis familiares y amigos
cercanos, a los cuales prometo dedicar el tiempo que les debo ahora que
finalizo esta etapa de mi vida en la que he estado tan ocupado; y a mi
abuelo Gonzalo, a quién le dedico esta tesis.

A los miembros del Colectivo A Rula por su labor en la difusión y
defensa del patrimonio gallego, y en lo personal, por su colaboración
en esta tesis y por enseñarme a apreciar la magnitud cultural del
fenómeno del Arte Rupestre “Atlántico”.

Finalmente, me gustaría agradecer a la USC, y extender ese
agradecimiento al grupo de investigación CIGEO por acogerme en esta
etapa de formación como investigador, así como a la Xunta de Galicia
por aportar parte de la financiación necesaria para el desarrollo de este
proyecto, bajo el programa operativo FSE Galicia 2014-2020 (2016).

A todos ellos, muchas gracias.

<!-- p. 6 -->



<!-- p. 7 -->

RESUMEN

APLICACIONES DE LA FOTOGRAMETRÍA DE
BAJO COSTE AL ESTUDIO DE PATRIMONIO
ARQUEOLÓGICO Y ARQUITECTÓNICO

RESUMEN
Esta tesis se enmarca en el campo de la documentación
fotogramétrica de patrimonio arquitectónico y arqueológico, y muestra
que en determinadas circunstancias esta documentación puede ser
llevada a cabo de un modo colaborativo, por parte de profesionales y
aficionados con medios y conocimientos limitados. Con el objetivo de
evaluar la variabilidad metodológica de la fotogrametría SfM en
términos de calidad geométrica, calidad visual, rendimiento y
accesibilidad técnica, se testean flujos de trabajo simples y de bajo
coste, que permiten obtener modelos 3D en situaciones complejas y
mejoran los resultados de técnicas de partida más avanzadas como el
TLS.

RESUMO
Esta tese enmarcase no campo da documentación fotogramétrica
de patrimonio arquitectónico e arqueolóxico, e mostra que en
determinadas circunstancias esta documentación pode ser levada a
cabo de un modo colaborativo, por parte de profesionais e afeccionados
con medios e coñecementos limitados. Co obxectivo de avaliar a
variabilidade metodolóxica da fotogrametría SfM en termos de calidade
xeométrica, calidade visual, rendemento e accesibilidade técnica,
téstanse fluxos de traballo simples e de baixo coste, que permiten obter
modelos 3D en situacións complexas e melloran os resultados de
técnicas a priori más avanzadas como o TLS.

7 | Página

<!-- p. 8 -->

SIMÓN PEÑA VILLASENÍN

ABSTRACT
This thesis is part of the field of photogrammetric documentation
of architectural and archaeological heritage, and shows that in certain
circumstances professionals and amateurs with limited means and
knowledge can carry out this documentation in a collaborative way.
With the aim of evaluating the methodological variability of SfM
photogrammetry in terms of geometric quality, visual quality,
performance and technical accessibility, simple and low-cost
workflows are tested, which allow obtaining 3D models in complex
situations and improve the results of more advanced starting techniques
such as TLS.

8 | Página

<!-- p. 9 -->

ÍNDICE

ÍNDICE
\1. ESTRUCTURA DE LA TESIS 23
\2. JUSTIFICACIÓN 25
\3. INTRODUCCIÓN 31
Documentación geométrica del patrimonio................................. 31
Fotogrametría SfM ....................................................................... 36
Variabilidad metodológica de la fotogrametría SfM ................... 38
Evaluación de las variables metodológicas de la fotogrametría .. 46
\4. OBJETIVOS 55
\5. CAPITULO I 59
Introducción ................................................................................. 61
Algoritmos Structure from Motion (SfM). .................................. 63
Toma fotográfica ......................................................................... 65
Metodología ................................................................................. 68
Resultados y discusión ................................................................ 81
Conclusiones................................................................................ 89
\6. CAPITULO II 95
Introducción ................................................................................. 97
Metodología ............................................................................... 102
Discusión de resultados. ............................................................ 117
Conclusiones.............................................................................. 127
\7. CAPITULO III 129
Introducción y objetivos ............................................................ 131
Metodología ............................................................................... 134
Resultados y discusión .............................................................. 142
Conclusiones.............................................................................. 150

9 | Página

<!-- p. 10 -->

SIMÓN PEÑA VILLASENÍN

\8. CAPITULO IV 161
Introducción ............................................................................... 163
Metodología ............................................................................... 167
Resultados y discusión ............................................................... 175
Conclusiones .............................................................................. 190
\9. CONCLUSIONES 193
\10. BIBLIOGRAFÍA 203

10 | Página

<!-- p. 11 -->

RESUMEN

APLICACIONES DE LA FOTOGRAMETRÍA DE
BAJO COSTE AL ESTUDIO DE PATRIMONIO
ARQUEOLÓGICO Y ARQUITECTÓNICO

RESUMEN
El 16 de noviembre de 1972, la “Convención para la protección
del Patrimonio Cultural y Natural del Mundo”, fue adoptada por la
“Conferencia General de la UNESCO” con el objetivo de promover la
identificación, protección y preservación del patrimonio cultural y
natural de todo el mundo. En el ámbito autonómico, entre los retos
prioritarios establecidos en las “Estrategias para la Especialización
Inteligente de Galicia”, se encuentra el desarrollo tecnológico en la
puesta en valor del patrimonio cultural, tanto en la gestión de
contenidos, como en su digitalización o catalogación. Para alcanzar
estos objetivos, resulta esencial documentar geométricamente el
patrimonio cultural, es decir, adquirir, procesar, presentar y registrar
los datos necesarios para la determinación de la posición, la forma y el
tamaño de un monumento en el espacio tridimensional. Las técnicas
tradicionales de documentación geométrica de patrimonio, convergen
actualmente hacia técnicas de adquisición de datos métricos masivas
que permiten obtener modelos 3D que proporcionan un registro
geométrico y radiométrico de alta resolución, aportando una
documentación del patrimonio mucho más completa, rigurosa y
adecuada que la proporcionada por las técnicas tradicionales.
En concreto, la fotogrametría de rango cercano ha evolucionado
considerablemente en las últimas décadas principalmente gracias al
desarrollo de los algoritmos Structure from Motion (SfM), los cuales
propiciaron su expansión como método de documentación patrimonial.
No obstante, su aplicación para la documentación de elementos
arquitectónicos no siempre es sencilla, en especial cuando las

11 | Página

<!-- p. 12 -->

SIMÓN PEÑA VILLASENÍN

limitaciones de espacio en la escena de trabajo son extremas como
ocurre habitualmente en los cascos históricos de las ciudades donde se
ubica la mayoría de casos. Otro ejemplo de dificultades en la aplicación
de estas tecnologías, la encontramos en el patrimonio de tipo
arqueológico, concretamente en el arte rupestre al aire libre o
petroglifos, los cuales además de geometrías complejas que dificultan
la aplicación de estos métodos de registro, requieren tratamientos
específicos que permitan registrar grabados no detectables a simple
vista. Además, la abundancia y dispersión de ambos tipos de
patrimonio en Galicia, hace que su documentación no sea viable solo
por medios profesionales avanzados. Por ello es importante el
desarrollo de metodologías sencillas y de bajo coste, que sean
accesibles a profesionales, o incluso a aficionados, no expertos en
métodos de modelado 3D.
La presente tesis doctoral se enmarca en el campo de la
documentación fotogramétrica de elementos patrimoniales por parte de
técnicos y aficionados con medios y conocimientos limitados en una
tecnología cada día más a su alcance. Dada la variabilidad
metodológica que presenta actualmente la fotogrametría SfM, el
objetivo principal de esta tesis es evaluar diferentes flujos de trabajo
fotogramétrico de bajo coste para modelado 3D de patrimonio
arquitectónico en cascos históricos y de muestras de arte rupestre al
aire libre, analizando los resultados obtenidos fundamentalmente en
términos de calidad geométrica, calidad visual, rendimiento y
accesibilidad técnica, mostrando la fotogrametría SfM como una
tecnología accesible a perfiles no expertos en la adquisición de datos
3D.
En los casos de estudio de patrimonio arquitectónico en cascos
históricos, las metodologías descritas permite obtener modelos 3D de
calidad, incluso en situaciones extremas donde la aplicación de
metodologías estandarizadas no son aplicables debido a las
limitaciones del espacio de trabajo; En lo referente a las tareas de
documentación geométrica de petroglifos, los flujos de trabajo
descritos, mejoran los resultados y rendimientos de técnicas a priori
más avanzadas como el TLS. Además, se define un flujo de trabajo
completo mediante software gratuito en todo el proceso, basado en la

12 | Página

<!-- p. 13 -->

RESUMEN

aplicación de fotogrametría SfM, renderizados de realce y
vectorización automática, que permite documentar un número elevado
de petroglifos en un periodo corto de tiempo, siendo además capaz de
registrar de modo objetivo grabados de arte rupestre “Atlántico” que
los métodos tradicionales no consiguen detectar.

Capítulo 1: Modelado 3D de fachadas históricas mediante
fotogrametría SfM. Documentación geométrica de distintas
tipologías arquitectónicas de un casco histórico
El patrimonio arquitectónico o inmueble se define por la UNESCO
(1972) como los monumentos, conjuntos de edificios o lugares, con un
valor excepcional desde el punto de vista de la historia, el arte o la
ciencia. Al igual que para otras tipologías patrimoniales, en el estudio
del patrimonio arquitectónico es fundamental la topografía y los
métodos de documentación geométrica. El desarrollo de técnicas de
documentación avanzadas como el TLS o la fotogrametría SfM
adquiere gran relevancia, ya que permite realizar una efectiva
restauración en caso de deterioro o destrucción parcial o total, el
replicado del mismo, o un poder de análisis y estudio de mayor grado.
Además, los edificios históricos no se ajustan a formas geométricas
sencillas, especialmente en fachadas significativas donde además de
los posibles defectos constructivos, es habitual la presencia de
esculturas, relieves o grabados en piedra, entre otros elementos con
formas complejas. En estos casos, las técnicas de adquisición masiva
de datos son imprescindibles.
La metodología de adquisición de modelos 3D de edificios de
centros históricos se estudió en el capítulo 1 de esta tesis, titulado
“Modelado 3D de fachadas históricas mediante fotogrametría SfM.
Documentación geométrica de distintas tipologías arquitectónicas de
un casco histórico”. En este capítulo, se analiza uno de los principales
factores que afectan a la calidad de los resultados en la aplicación de
técnicas fotogramétricas para el modelado 3D de elementos
patrimoniales, como es la limitación de espacio en la escena de trabajo.
Estudios previos muestran la confiabilidad de la fotogrametría
Structure from Motion (SfM) cuando el objeto está ubicado en un

13 | Página

<!-- p. 14 -->

SIMÓN PEÑA VILLASENÍN

espacio grande y accesible; sin embargo, en cascos históricos, la toma
fotográfica debe adaptarse a las limitaciones de espacio particulares de
cada ubicación.
El centro histórico de Santiago de Compostela (España) ha sido
elegido para este estudio, seleccionando cuatro casos representativos
de diferentes tipologías urbanas: “fachada significativa”, “fachada en
una calle estándar”, “calle estrecha” (relación entre ancho de calle y
alto de fachada menor que 1/3) y “fachada con soportales”.
En los dos primeros casos de estudio, fachada significativa, y
fachada en calle estándar, el espacio no era un factor limitante,
obteniéndose resultados satisfactorios en ambos, incluso en el segundo
caso, donde se utilizó la cámara integrada en un Phone como
dispositivo de toma. En el tercer y cuarto caso de estudio, fachada en
calle estrecha y fachada con soportales, las limitaciones de espacio
impedían la aplicación de disposiciones de imágenes estandarizadas,
por lo que se adoptaron soluciones ingeniosas, extrapolables a
tipologías similares, y que permitieron obtener una reconstrucción de
la escena geométrica y visualmente correcta.

Capítulo 2: Comparación de software desktop profesional y
software gratuito cloud computing en el modelado 3D de edificios
históricos: Monasterio de San Martín Pinario
Cuatro factores destacan en la evolución de la fotogrametría SfM
y que han propiciado que en las últimas décadas, se haya establecido
como un método de adquisición de datos 3D en el campo del
patrimonio, la arquitectura, la ingeniería y la construcción entre otros.
En primer lugar el desarrollo de los algoritmos de identificación
automática de puntos homólogos, Scale-Invariant Feature Transform
(SIFT), los cuales han permitido que la identificación de los puntos
homólogos sea automática. En segundo lugar, la automatización del
proceso de calibración mediante el cálculo inverso de los parámetros
de orientación internos y externos de las cámaras a partir del algoritmo
de ajuste Bundler, capaz de realizar este proceso en un solo paso, sin
la necesidad de una calibración previa de la cámara. En tercer lugar, la

14 | Página

<!-- p. 15 -->

RESUMEN

posibilidad de obtener una nube de puntos de mayor densidad
implementando el algoritmo Clustering view for Multiview Stereo
(CMVS) y Patch-based Multiview Stereo (PMVS2). La aparición de
estos algoritmos nos ha permitido mediante un proceso automatizado,
obtener nubes de puntos, mallas de triángulos y posteriormente un
modelo texturizado tridimensional completo. En cuarto lugar, las
capacidades de computación, especialmente incrementadas debido a la
aparición de la computación “en la nube” o cloud computing.
Estos avances hacen que la fotogrametría sea una técnica “viva”,
ya que la evolución constante de las versiones de software integrando
mejoras en los algoritmos, justifica un análisis periódico de los
resultados de la misma. Las distintas opciones de software de
procesado fotogramétrico se analizan en este capítulo, en donde el
procesado con software fotogramétrico profesional (PhotoScan y
Pix4D), se compara con el procesado con software fotogramétrico de
bajo coste (Autodesk Remake), para el levantamiento de fachadas de
edificios históricos.
El objetivo principal es analizar la precisión de los resultados
obtenidos, así como la facilidad de uso y accesibilidad de distintas
opciones de software fotogramétrico. En este caso, el modelado 3D se
testea sobre una colección de imágenes de la fachada de San Martín
Pinario, el segundo monasterio más grande de España. Tras un análisis
de los resultados de procesado, la calidad y precisión geométrica, los
resultados visuales y la utilidad operacional de las distintas opciones
de software, se muestra que el software de computación “en la nube”
ofrece modelos 3D con calidad y precisión visual similares a los
obtenidos con el software de escritorio. El ahorro de costes y la
facilidad de uso de este, hacen que la computación fotogramétrica “en
la nube” sea una excelente opción como herramienta de medición 3D
ágil y económica, para los profesionales del patrimonio y la
construcción que no son especialistas en fotogrametría.

15 | Página

<!-- p. 16 -->

SIMÓN PEÑA VILLASENÍN

Capítulo 3: Comparación de TLS y fotogrametría SfM para el
modelado 3d de arte rupestre y la aplicación del realce Radiance
Scaling Shader para la detección de grabados
El conjunto arqueológico gallego de arte rupestre constituye una
expresión artística significativa de las comunidades que habitaron estas
tierras en la edad de bronce catalogados dentro de la familia de arte
rupestre “Atlántico”, estos petroglifos tienen una fuerte personalidad
que los hace reconocibles entre muchos otros. Considerando el número
y la calidad de los diseños, el arte rupestre gallego es una de las
manifestaciones culturales más importantes de este tipo en Europa.
El inventario geométrico y la documentación del arte rupestre es
complejo debido a la gran cantidad de petroglifos presentes en el
territorio, la distancia entre ellos, en muchos casos el estado de
abandono de las áreas forestales, las limitaciones de acceso y las
características geométricas de este patrimonio, en el que predominan
grabados poco profundos en muchos casos altamente erosionados, que
hacen del arte rupestre gallego un fenómeno difícil de documentar.
Este complejo registro ha dado lugar a documentaciones e
interpretaciones parciales del conjunto de arte rupestre gallego. En la
mayoría de los casos la única documentación existente es una
descripción textual y su geolocalización aproximada, lo que deriva en
una interpretación parcial del fenómeno. La documentación
geométrica de todo el patrimonio rupestre no es factible por razones
técnicas y económicas, y al mismo tiempo, esta documentación es una
tarea muy necesaria debido al alto riesgo de deterioro del mismo, ya
que estas muestras de arte rupestre al aire libre, están totalmente
expuestas a múltiples agentes externos.
En las últimas décadas, la fotogrametría Structure from Motion
(SfM) se posicionó como una técnica óptima para la documentación
patrimonial, pero esta técnica tiene una gran variabilidad en su
metodología y coste de ejecución. La metodología de adquisición de
modelos 3D de petroglifos se estudia en el capítulo 3 titulado
“Comparación de TLS y fotogrametría SfM para el modelado 3D de
arte rupestre y la aplicación del realce Radiance Scaling Shader para
la detección de grabados”. En este estudio, se desarrolla un método

16 | Página

<!-- p. 17 -->

RESUMEN

muy simple y eficaz basado en la fotogrametría SfM con software de
computación “en la nube” de bajo coste, el cual se somete a análisis
mediante 3 experimentos:
En primer lugar, la comparación de sus resultados con los
obtenidos con un escáner láser terrestre (TLS) de última generación
para la documentación 3D de un mismo petroglifo, en este caso el PT
de O Castriño de Conxo, Santiago de Compostela. Las mallas se
comparan mediante el análisis de criterios visuales, geométricos y
operacionales y su adaptación para la aplicación del renderizado de
grabados Radiance Scaling Shader.
A continuación, la documentación de diferentes petroglifos aún no
documentados geométricamente se realizó en un área geográfica con
un radio de 6 km. Sus localizaciones se muestran en la Figura 1 (Punto
2). La metodología de la documentación fue la toma fotográfica simple
con una cámara convencional. Esta tarea fue realizada por un técnico
con 5 años de experiencia en fotogrametría terrestre, con el objetivo de
evaluar el número de elementos que podrían documentarse en una
jornada de campo.
Finalmente, la metodología desarrollada es probada en varias
ubicaciones con muestras de arte rupestre no documentadas por
métodos 3D hasta la fecha, con la particularidad de que en estos casos,
la toma fotográfica fue realizada por miembros del Colectivo A Rula
no expertos en esta tecnología.
Los resultados muestran que con una metodología de
fotogrametría SfM, que es muy simple y accesible a perfiles no
expertos, es posible obtener mejores resultados en aspectos
geométricos y visuales que los obtenidos con TLS, siendo estos válidos
para un análisis detallado de arte rupestre y que por tanto, permite de
un modo colaborativo una documentación masiva del fenómeno que
no es posible exclusivamente por medios profesionales. El flujo de
trabajo descrito mostró además, un gran rendimiento, permitiendo a
una sola persona en una única jornada de campo la documentación de
hasta 20 muestras de arte rupestre dispersas en un radio de 6km.

17 | Página

<!-- p. 18 -->

SIMÓN PEÑA VILLASENÍN

Capítulo 4: Una metodología de trabajo simple y de bajo coste
al alcance de múltiples perfiles para el modelado 3D y
vectorización automatizada de grabados de arte rupestre
“Atlántico”
Actualmente, solo en Galicia, hay catalogados más de 3000
petroglifos, sin embargo, la mayoría de ellos aún no se han
documentado geométricamente. A pesar de los avances técnicos de los
últimos años en tecnologías 3D, el inventario geométrico y la
documentación del arte rupestre en Galicia continúan presentando
muchos desafíos, en especial debido a la gran cantidad de petroglifos
presentes en el territorio. La fotogrametría Structure from Motion
(SfM) se ha mostrado como una técnica óptima para la documentación
de este tipo de patrimonio, no obstante se acostumbran a utilizar flujos
de trabajo complejos que requieren el empleo de instrumental
topográfico, pértigas, drones o software de pago, por lo que su coste de
ejecución y accesibilidad se reduce notablemente, haciendo inviable su
aplicación de modo masivo.
Además, debido a la sinuosidad de algunos grabados, es necesario
utilizar métodos de realce para obtener una mejor visualización de los
mismos. En este sentido en los últimos años, métodos desarrollados por
las comunidades de computación gráfica, que se basan en el análisis
morfológico de los modelos 3D, han sido utilizados en la detección de
grabados, mostrando resultados satisfactorios en el análisis de arte
rupestre al permitir entre otras posibilidades la obtención automatizada
de calcos vectoriales.
La aplicación de los renderizados de realce sobre modelos 3D
obtenidos mediante fotogrametría SfM, se estudia en profundidad el
capítulo 4 titulado, “Una metodología de trabajo simple y de bajo coste
al alcance de múltiples perfiles para el modelado 3D y vectorización
automatizada de grabados de arte rupestre Atlántico”. El principal
objetivo de este estudio es el desarrollo de un flujo de trabajo completo,
sencillo y de bajo coste, para el análisis objetivo de grabados rupestres,
el cual consta de tres pasos principales. En primer lugar la obtención
de un modelo 3D de alta resolución geométrica a partir de la
metodología desarrollada en el capítulo anterior. En segundo lugar, el

18 | Página

<!-- p. 19 -->

RESUMEN

realzado de los grabados a partir de la aplicación de los renderizados
Radiance Scaling Shader. Finalmente, la publicación directa de los
modelos 3D realzados, a través de la plataforma Sketchfab, o la
extracción del calco digital automatizada a partir de un proceso de
sobreexposición y subexposición de capturas 2D del modelo realzado
y su vectorización automática a partir del servicio online gratuito
“Vectorizer” (Massow, 2015).
El experimento, constó en el estudio de las distintas variables de
configuración de las tres fases de trabajo sobre un petroglifo que
engloba la mayoría de tipologías de grabado de la familia de arte
rupestre “Atlántico” como es el petroglifo de Fontão do Eido en
Verdoejo, Valença do Minho (Portugal). Posteriormente, tras analizar
los resultados de las distintas variables de del proceso, se determina un
flujo de trabajo optimizado, cuyo rendimiento fue sometido a análisis
sobre otras muestras de arte rupestre.
Todas las sesiones fotográficas fueron realizadas por aficionados
al patrimonio pertenecientes al Colectivo A Rula de Santiago de
Compostela, demostrando que el uso de estas técnicas avanzadas de
adquisición de datos 3D, son accesibles para todos los perfiles debido
a su bajo coste de ejecución y facilidad de uso. Este estudio muestra
que el flujo de trabajo desarrollado, permite la documentación
geométrica de un fenómeno cultural de registro complicado como son
los sutiles grabados de arte rupestre “Atlántico”, de un modo
colaborativo y con suficiente poder analítico para obtener
interpretaciones objetivas de los mismos.
Además, la publicación directa de modelos 3D realzados es
posibles gracias a plataformas como Sketchfab, permitiendo mostrar el
arte rupestre de un modo más evidente, atractivo y moderno. Este modo
de difusión aporta mayor objetividad en el análisis de arte rupestre, ya
que las interpretaciones a partir del estudio directo sobre los modelos
3D, no están afectadas por errores derivados de la proyección de la
información tridimensional del grabado, en un formato de
representación bidimensional, lo que es de gran relevancia para el
estudio de las adaptaciones morfológicas de los diseños a la roca.

19 | Página

<!-- p. 20 -->



<!-- p. 21 -->

TESIS DOCTORAL

APLICACIONES DE LA
FOTOGRAMETRÍA DE BAJO
COSTE AL ESTUDIO DE
PATRIMONIO ARQUEOLÓGICO
Y ARQUITECTÓNICO

Simón Peña Villasenín

ESCOLA DE DOUTORAMENTO INTERNACIONAL

PROGRAMA DE DOUTORAMENTO EN ENXEÑARÍA PARA O DESENVOLVEMENTO
RURAL E CIVIL

SANTIAGO DE COMPOSTELA / LUGO

2019

<!-- p. 22 -->



<!-- p. 23 -->

ESTRUCTURA DE LA TESIS

\1. ESTRUCTURA DE LA TESIS

Tras una justificación del interés de la investigación desarrollada en esta
tesis, se aborda la sección introductoria, en la cual, en primer lugar, se
describen las necesidades técnicas y métodos tradicionales empleados
en la documentación geométrica tanto de patrimonio arquitectónico
como arqueológico, así como las ventajas que suponen los métodos
modernos de modelado 3D en esta labor. A continuación se profundiza
en la metodología de modelado 3D denominada fotogrametría Structure
from Motion (SfM) y se describen las variables metodológicas presentes
en la técnica y los principales indicadores a considerar para su análisis
en términos de precisión geométrica, calidad visual, rendimiento y
accesibilidad. A continuación se plantea el objetivo general y los
específicos de esta tesis y se exponen, en diferentes capítulos, los cuatro
casos de estudio que se han desarrollado para alcanzar dichos objetivos:

• Capítulo I. Modelado 3d de fachadas históricas mediante
fotogrametría SfM. Documentación geométrica de distintas
tipologías arquitectónicas de un casco histórico.
Capítulo publicado en Journal of Architectural Heirtage
(Peña-Villasenín et al., 2017)
Peña-Villasenín, S., Gil-Docampo, M., & Ortiz-Sanz, J. (2017). 3D Modelling
of Historic Facades Using SfM Photogrammetry Metric
documentation of different building types of a historic centre.
International Journal of Architectural Heritage.

https://doi.org/10.1080/15583058.2017.1317884

23 | Página

<!-- p. 24 -->

SIMÓN PEÑA VILLASENÍN

• Capítulo II. Comparación de software desktop profesional y
software gratuito cloud computing en el modelado 3d de
edificios históricos: Monasterio de San Martín Pinario
(Capitulo II)
Pendiente de revisión por pares en la revista:
Measurement. ISSN: 0263-2241.

• Capítulo III. Comparación de TLS y fotogrametría SfM para
el modelado 3d de arte rupestre y la aplicación del realce
Radiance Scaling Shader para la detección de grabados.
Capítulo publicado en Journal of Cultural Heirtage
(Peña-Villasenín et al., 2018)
Peña-Villasenín, S., Gil-Docampo, M., & Ortiz-Sanz, J. (2018). Professional
SfM and TLS vs a simple SfM photogrammetry for 3D modelling of
rock art and Radiance Scaling shading in engraving detection. Journal
of Cultural Heritage.

https://doi.org/10.1016/j.culher.2018.10.009

• Capítulo IV. Una metodología de trabajo simple y de bajo
coste al alcance de múltiples perfiles para el modelado 3D y
vectorización automatizada de grabados de arte rupestre
“Atlántico”.
Pendiente de publicación en la revista:
Archaeological Prospection. ISSN: 1099-0763.

Posteriormente, se presentan las principales conclusiones extraídas
del estudio y, finalmente, se indica la bibliografía empleada en cada
caso de estudio así como en el resto del documento.

24 | Página

<!-- p. 25 -->

JUSTIFICACIÓN

\2. JUSTIFICACIÓN

En la convención de la UNESCO del 1972, se establece la necesidad
imprescindible de la documentación geométrica del patrimonio
cultural con el objetivo de promover la identificación, protección y
preservación del mismo. Como se observa en la figura 1, en Galicia
hay presente una abundante riqueza patrimonial con una gran
dispersión territorial. Según el Plan Básico Autonómico (PBA, 2018),
hay catalogados aproximadamente 57.000 elementos patrimoniales, de
los cuales cerca de los 40.000 son de tipo arquitectónico (Figura 1-A),
si se integran en este grupo tanto los bienes de interés artístico como
etnográfico, y más de 17.000 de tipo arqueológico (Figura 1-B). Estos
elementos de patrimonio arquitectónico y arqueológico, como los
cascos históricos o las muestras de arte rupestre al aire libre, se
encuentran habitualmente expuestos a agentes externos dañinos que
comprometen su preservación en el tiempo. Esta situación, se agrava
en la comunidad gallega debido al gran número y dispersión de los
elementos patrimoniales y por factores como la despoblación rural; el
abandono o la dedicación a cultivos intensivos de las zonas forestales;
incluso el propio desconocimiento de la presencia del mismo por parte
de la población local.

Figura 1. Cartografía obtenida a partir de la información incluida en el Plan
Básico Autonómico (PBA, 2018). (A) Patrimonio arquitectónico. (B) Patrimonio
arqueológico. (C) Yacimientos de arte rupestre.

25 | Página

<!-- p. 26 -->

SIMÓN PEÑA VILLASENÍN

El patrimonio arquitectónico de cascos históricos
Gran parte del patrimonio arquitectónico, se agrupa en los centros
históricos de las ciudades y pueblos. Según el Comité de Patrimonio
Mundial de la UNESCO en la Convención de La Haya para la
protección de los Bienes Culturales en caso de Conflicto Armado, (La
Haya, 1954), se denomina centro o casco histórico al
núcleo urbano original de planeamiento y construcción de un área
urbana, generalmente el de mayor atracción social, económica,
política y cultural, que se caracteriza por contener los bienes vinculados
con la historia de una determinada ciudad, a partir de la cultura que le
dio origen. Se trata de una zona aún viva, es decir, en la ciudad histórica
todavía concurren actividades de vida propias que se resisten a los
procesos de desplazamiento. La capacidad de carga o de intervención
que sostienen los centros históricos vivos es muy limitada, las
intervenciones para dotar a la población de servicios actualizados son
de difícil ejecución; por este motivo en ocasiones el abandono de las
zonas residenciales históricas no se hace por sustitución de funciones,
sino por la ausencia de tejido social. Pasan a ser zonas deprimidas,
desiertas incluso en estado de ruina. El resultado del mismo son
ciudades históricas despobladas. La necesidad de que los cascos
históricos sean adecuadamente conservados como legado común nace
en primer lugar como herencia histórica a conservar, y por consiguiente,
su inventariado y caracterización para enfrentar de manera más efectiva
su conservación se hace imprescindible; pero también como posible
objeto de intervención urbanística (ej. dotación de servicios,
rehabilitación de viviendas, restauraciones, derribos) con el fin de evitar
la desaparición de su tejido social; o incluso como producto generador
de riqueza para el sector turístico (Jamal & Orbasli, 2008). En
ocasiones, la abundancia de estos elementos patrimoniales y las
limitaciones en medios económicos y técnicos hacen inviable afrontar
de manera efectiva la documentación del mismo. La conservación de
este patrimonio depende en gran medida de que los profesionales
encargados de dicha tarea, habitualmente limitados en medios y
conocimientos técnicos, cuenten con herramientas accesibles en coste
y facilidad de uso, que les permitan realizar las labores cotidianas que
requiere la documentación arquitectónica patrimonial (Yilmaz et al.,

26 | Página

<!-- p. 27 -->

JUSTIFICACIÓN

2007). En otras ocasiones, en las que los elementos patrimoniales son
destruidos sin documentación previa, el único medio posible para la
restauración es su documentación en base a imágenes tomadas por los
visitantes que lo “registraron” antes dicha destrucción (Grün et al.,
2004; Snavely et al., 2006, 2008).

Arte rupestre en Galicia
Los yacimientos arqueológicos pertenecientes a todo tipo de
adscripción cultural, se encuentran expuestos a agentes externos que los
ponen en riesgo de deterioro, siendo especialmente delicado el estado
de conservación de muchas de las muestras de arte rupestre “Atlántico”
de Galicia y Norte de Portugal. Estos yacimientos del grupo de
grabados rupestres del tipo “al aire libre” (Varela, 1982), además del
deterioro que sufren debido a los agentes climatológico, se sitúan
habitualmente en zonas forestales intensivas, que incluso en ocasiones
son afectadas por incendios que degradan enormemente los grabados
por procesos como la termoclastia (Carrera Ramírez et al., 1994); o
incluso por actos vandálicos como evidencia la reciente agresión que ha
sufrido el petroglifo de O Castriño de Conxo, una de las muestras más
representativas del arte rupestre gallego (17 de mayo de 2019, La Voz
de Galicia).
La investigación de este fenómeno es relativamente reciente,
espacialmente sesgada (Carrera Ramírez et al., 1994; Veiga, 2005) al
situarse la mayoría de elementos catalogados en la provincia de
Pontevedra (Buhigas-Sobrino, 2000) e incompleta (Rodríguez Rellán et
al., 2018). Prueba de ello, es que cada año en Galicia y norte de
Portugal, numerosas muestras de arte rupestre son todavía descubiertas.
A pesar de esto, la concentración de arte rupestre en Galicia
documentada, es ya de gran relevancia (Figura 1-C), siendo
aproximadamente 2700 las muestras las oficialmente catalogadas según
el Plan Básico Autonómico (PBA, 2018). Algunos autores aseguran que
esta cifra es de largo superior a las 3000 (Rodríguez Rellán et al., 2018).
Los petroglifos o grabados rupestres de nuestra comunidad, se integran
dentro de la familia del arte rupestre “Atlántico” y teniendo en cuenta
tanto el número como la complejidad de sus diseños, puede afirmarse
que el arte rupestre gallego se encuentran entre las manifestaciones

27 | Página

<!-- p. 28 -->

SIMÓN PEÑA VILLASENÍN

culturales de este tipo más destacadas de Europa. Fenómenos culturales
de similares características, son declarados patrimonio de la humanidad
en otras zonas geográficas como en el caso de Tanum en Suecia, Alta
en Noruega, el Val Camónica en Italia o el Val de Cõa en Portugal.
Afrontar de manera efectiva la protección, divulgación, difusión y
explotación turística de este recurso cultural, es en la actualidad todavía
un reto en nuestra comunidad.
Ante esta situación, han surgido en los últimos años asociaciones y
colectivos de aficionados al estudio de distintos tipos de elementos
patrimoniales y especialmente del arte rupestre, que promueven la
defensa y divulgación de los mismos como principal dinámica para su
conservación. Ejemplo de ello es la asociación de aficionados al arte
rupestre Colectivo A Rula de Santiago de Compostela y que ha realizado
en los últimos años una importante labor promoviendo la protección y
difusión del patrimonio rupestre de Galicia y Norte de Portugal.
Organizaciones como Capitán Gosende de Cercedo (Pontevedra), el
Grupo de Arqueoloxía Terras de Trasancos de Betanzos (A Coruña),
Codeseda Viva de A Estrada (Pontevedra), Colectivo Patrimonio dos
Ancares (Lugo), o patrimoniogalego.net en Pontevedra, son ejemplos
de otras entidades sociales que han promovido en los últimos años la
protección del patrimonio cultural de Galicia y en concreto del arte
rupestre “Atlántico” gallego. La labor de estos colectivos sociales es
necesaria para llevar a cabo estas tareas de catalogación patrimonial que
no serían viables exclusivamente por medios profesionales. Una
corriente cultural, que gracias a las redes sociales y al alto grado de
concienciación de las nuevas generaciones tiende a expandirse en el
futuro.

Documentación geométrica del patrimonio
La conservación del patrimonio requiere tareas como la
documentación geométrica del mismo, disponer de información precisa
y actualizada de la forma, características, materiales y análisis
estructural del patrimonio es un requisito indispensable para su correcta
conservación (Genovese, 2005). Tradicionalmente, los métodos de
documentación geométrica de carácter manual fueron los más
empleados en documentaciones patrimoniales de todo tipo (Lodeiro-

28 | Página

<!-- p. 29 -->

JUSTIFICACIÓN

Pérez, 1995), no obstante su aplicación, es tediosa y además acostumbra
a implicar una importante pérdida de información durante la fase de
transferencia de datos desde el elemento real al modelo teórico (Yilmaz
et al., 2007). En lo referente a grabados rupestres, los métodos
tradicionales de documentación geométrica (Arias et al., 2007)
acostumbran además a ser agresivos al requerir no solo el contacto
directo con el soporte, si no también interacción física con el mismo. Se
tratarían de técnicas ampliamente empleadas para la documentación de
petroglifos en Galicia como el Frotagge o el calco con plástico (Arcà,
2006; González-Aguilera et al., 2009; Lewis-Williams & Pager, 1990;
Moneva Montero, 1993). Otras metodologías tradicionales más
avanzadas, como los métodos topográficos, ven limitada su
funcionalidad cuando el elemento a estudiar presenta formas irregulares
no asimilables a formas geométricas sencillas (Barazzetti et al., 2009,
2011), lo cual es muy común en elementos de tipo patrimonial. En este
sentido es importante el desarrollo de metodologías y herramientas
accesibles a profesionales y aficionados del patrimonio, que permitan
realizar documentaciones de geometrías complejas de forma ágil y
precisa.
A pesar de que muchos profesionales que actualmente trabajan en
proyectos relacionados con la conservación del patrimonio cultural
todavía siguen empleando las técnicas tradicionales, lo cierto es que en
las últimas décadas la documentación geométrica mediante técnicas
modernas de adquisición de datos 3D como el láser escáner terrestre
(TLS) o la fotogrametría Structure from Motion (SfM) se ha utilizado
ampliamente con grandes resultados (Santagati et al., 2013; Yilmaz et
al., 2007). Ambas técnicas proporcionan modelos 3D fotorrealistas de
alta resolución que permiten conocer con precisión la posición, la
forma, la textura y el tamaño de cualquier elemento patrimonial en el
espacio, en un momento dado en el tiempo; Algunos autores justifican
incluso una revisión de los petroglifos ya documentados mediante los
métodos tradicionales ya que los métodos modernos de documentación
3D, son capaces de detectar de modo objetivo un mayor número de
grabados (Rodríguez Rellán et al., 2018).
En cuanto al patrimonio arquitectónico, el desarrollo de técnicas de
documentación avanzadas como el TLS o la fotogrametría SfM adquiere

29 | Página

<!-- p. 30 -->

SIMÓN PEÑA VILLASENÍN

gran relevancia, permitiendo realizar una efectiva restauración en caso
de destrucción parcial o total; el replicado del mismo; o un poder de
análisis y estudio de mayor grado. Además, los edificios históricos no
se ajustan a formas geométricas regulares, especialmente en fachadas
significativas donde habitualmente se presentan esculturas, relieves y
grabados en piedra, entre otros elementos con formas complejas donde
las técnicas masivas de adquisición de datos métricos son
imprescindibles (Barazzetti et al., 2011).

Las TIC y la documentación 3D
Por otro lado, el desarrollo de la realidad virtual y las TIC juegan
actualmente un papel fundamental en la conservación patrimonial, ya
que la difusión y la divulgación, para crear concienciación local e
identidad territorial en base a este patrimonio, puede realizarse
actualmente con medios visualmente atractivos (Caro & Hansen, 2015;
Gaitatzes et al., 2001). Las TIC y los nuevos métodos de documentación
3D como la fotogrametría, ponen a disposición de aficionados,
investigadores y profesionales, herramientas de un gran potencial para
el estudio, difusión y divulgación patrimonial. Por ello, los avances
metodológicos que se producen en esta dirección, además de contribuir
a alcanzar los objetivos de identificación, protección y preservación
fijados por la UNESCO, fomentan el cumplimiento de la Estrategia
para la Especialización Inteligente de Galicia (RIS3 subgrupo GT5),
la cual establece como uno de los retos prioritarios para esta comunidad,
el desarrollo tecnológico en la puesta en valor del patrimonio cultural,
tanto en la gestión de contenidos, como en su digitalización o
catalogación.

30 | Página

<!-- p. 31 -->

INTRODUCCIÓN

\3. INTRODUCCIÓN

“El patrimonio cultural es el conjunto de bienes tangibles, intangibles
y naturales, considerados de interés relevante para la sociedad, que
fueron heredados de generaciones pasadas y que deben ser
conservados y transmitidos a las generaciones futuras” (Unesco,
1972). La necesidad de que perdure adecuadamente en el tiempo como
nuestra herencia histórica es imprescindible, pero también como
posible foco de atracción para la creciente demanda turística cultural
(Bedate et al., 2004). Es por ello que se promueve el estudio,
conservación y difusión del patrimonio como una fuente de riqueza
cultural, pero también económica, generadora de identidad territorial y
fomentadora del asentamiento poblacional que supone un caudal de
recursos para las generaciones futuras.

Documentación geométrica del patrimonio
La documentación geométrica es una parte importante de la
documentación general del patrimonio cultural y fue definida por la
UNESCO (Unesco, 1972), como: “La acción de adquirir, procesar,
presentar y registrar los datos necesarios para la determinación de la
posición, la forma y el tamaño de un monumento en el espacio 3D en
un momento dado en el tiempo. La documentación geométrica registra
el presente de los monumentos, como se han ido formando a lo largo
del tiempo y es la base necesaria para el estudio de su pasado, así
como el de su futuro”. Dada la importancia de esta labor, es
conveniente definir las necesidades documentales y particularidades
físicas presentes en distintas tipologías patrimoniales y que
condicionan la realización de esta tarea.

31 | Página

<!-- p. 32 -->

SIMÓN PEÑA VILLASENÍN

Patrimonio arquitectónico
La UNESCO (Unesco, 1972), define como patrimonio
arquitectónico o inmueble, los monumentos, conjuntos de edificios o
lugares, con un valor excepcional desde el punto de vista de la historia,
el arte o la ciencia. Este organismo, establece que el término bienes
inmuebles se refiere a una manifestación material, imposible de ser
movida o trasladada. El patrimonio inmueble está constituido por
monumentos, obras de la arquitectura y de la ingeniería, sitios históricos
y centros industriales, zonas, calles, puentes, viaductos, etc. de interés
o valor relevante desde el punto de vista arquitectónico. Dentro de esta
tipología patrimonial, se incluyen no solo edificios históricos, sino
también el patrimonio etnográfico, el cual, según la ley de patrimonio
Histórico Español, son todas aquellas edificaciones e instalaciones cuyo
modelo constitutivo es expresión de conocimientos adquiridos,
arraigados y transmitidos consuetudinariamente y cuya factura se
acomode, en su conjunto o parcialmente, a una clase, tipo o forma
arquitectónicos utilizados tradicionalmente por las comunidades o
grupos humanos, una tipología patrimonial muy común en Galicia.
Al igual que para otras tipologías patrimoniales, en el estudio del
patrimonio arquitectónico es fundamental la topografía y los métodos
de documentación geométrica (Böhler & Heinz, 1999). Arqueólogos,
historiadores y conservadores necesitan a menudo documentar
geométricamente los monumentos para su correcto estudio y
conservación (Charalambos Ioannidis et al., 2000). También
arquitectos, ingenieros y profesionales de la construcción (Carnevali et
al., 2018; Kwak et al., 2013; Yang et al., 2016), necesitan planos de
detalle para la correcta reparación, remodelación o mantenimiento de
construcciones. El levantamiento métrico de edificios mediante
técnicas tradicionales es tediosa y en ocasiones imprecisa. Estas
técnicas implican la realización de mediciones individuales mediante
instrumentos de medida como cinta métrica, flexómetro o
distanciómetro láser y la transmisión de estas del elemento real al
modelo teórico (Yilmaz et al., 2007). Otras técnicas más avanzadas
como los métodos topográficos, requieren de instrumental y
conocimientos específicos y no son del todo funcionales para
geometrías patrimoniales complejas (Barazzetti et al., 2011).

32 | Página

<!-- p. 33 -->

INTRODUCCIÓN

Arte rupestre
En labores de documentación geométrica de patrimonio
arqueológico, se presentan tareas que requieren metodologías
específicas como la documentación de inscripciones en piedra o
grabados rupestre. Para la documentación de estas manifestaciones
culturales concretas, existen metodologías tradicionales específicas
como el Frotagge o el calco con plástico (Díaz-Andreu et al., 2006) y
que han sido ampliamente utilizadas en los petroglifos gallegos. Estas
técnicas, además de tediosas, son altamente agresivas con el soporte, al
requerir no solo el contacto directo con el elemento, si no también
interacción física con el mismo frotándolo, como en el caso de la técnica
de Frotagge, o pintando directamente sobre el grabado, como en la
técnica del calco con plástico. Por ello, es conveniente caminar hacia la
sustitución de estas técnicas de contacto por técnicas de documentación
geométrica no invasivas como la fotogrametría o el láser escáner
terrestre que permiten obtener modelos 3D del patrimonio sin contacto
con el mismo (Bea & Angás, 2017; Díaz-Guardamino & D, 2013;
Meijer, 2015; Ortiz-Sanz et al., 2010).

Los modelos 3D del patrimonio
Actualmente, las distintas técnicas tradicionales de documentación
geométrica tanto en patrimonio arquitectónico como de arte rupestre,
convergen hacia técnicas de adquisición de datos métricos masivas que
permiten obtener modelos 3D como la tecnología Láser Escáner
Terrestre (TLS), la luz estructurada o la fotogrametría Structure from
Motion (SfM). La información obtenida mediante estas metodologías
proporciona un registro métrico 3D que permiten la documentación y
el análisis de formas, dimensiones y texturas del elemento a altas
resoluciones, proporcionando una documentación mucho más
completa, rigurosa y adecuada que la proporcionada por las técnicas
tradicionales.
Por esta razón, las técnicas de modelado 3D y especialmente la
fotogrametría SfM se han incorporado en las labores de documentación
geométrica de todo tipo de patrimonio (Dai & Lu, 2010; Ordóñez et
al., 2010). Dado que la inversión requerida para equipos fotográficos y
software es sustancialmente menor que la requerida para el escáner 3D

33 | Página

<!-- p. 34 -->

SIMÓN PEÑA VILLASENÍN

y además es más adaptable a los lugares poco estables y con geometrías
complejas. Además, hay situaciones en las que ni el TLS ni la
utilización de técnicas tradicionales es viable, como en el caso de
fachadas con zonas inaccesibles o incluso en edificios dañados o
destruidos, donde los métodos involuntarios como la fotogrametría son
la única posibilidad (Grün et al., 2004; Resco et al., 2014). Por estos
motivos, la fotogrametría ha avanzado considerablemente en las
últimas décadas y ha sido utilizada cada vez más no solo por
arqueólogos (Bea & Angás, 2017; Gonizzi Barsanti et al., 2013),
historiadores (Johnson & Solis, 2016) y conservadores (MartínezRodríguez et al., 2015; Juan Ortiz et al., 2013), sino también por
ingenieros civiles (Bhatla et al., 2012; Kwak et al., 2013; Stavroulaki
et al., 2016) o arquitectos (Sužiedelytė-Visockienė et al., 2015; Yang
et al., 2016). No obstante, en el mercado sigue estando muy presente la
tecnología láser escáner terrestre, probablemente debido a su alta tasa
de adquisición de datos, su precisión relativa y la alta densidad de datos
espaciales que proporciona (Ergun, 2010), además de unas necesidades
de conocimientos metodológicos menos complejos que los que
requiere la fotogrametría (J. H. Chandler & Buckley, 2016).
Cabe señalar que a pesar de que los métodos tradicionales de
documentación geométrica acostumbran a tener una ejecución tediosa,
estos son simples y con un alto grado de estandarización. Por el
contrario, la aplicación de tecnologías modernas como TLS o la
Fotogrametría SfM, requiere conocimientos específicos, una
adaptación mayor a la escena u objeto de estudio, tienen un alto coste
respecto a las técnicas tradicionales como el croquis, además de
dificultar la integración con el resto de información 2D (Campana &
Remondino, 2007). Es por ello que los métodos de modelado 3D
modernos siguen más ligados a un perfil experto, por lo que los
métodos tradicionales son ampliamente utilizados todavía por muchos
profesionales en sus tareas cotidianas. Además gran parte del
patrimonio arquitectónico se encuentra en los cascos históricos de
pueblos y ciudades, donde la limitación de espacio, o las complejas
geometrías son comunes las cuales dificultan en gran medida la
aplicación de técnicas “sin contacto” como la fotogrametría o el TLS.
Por estos motivos, es conveniente profundizar en la aplicación de estas

34 | Página

<!-- p. 35 -->

INTRODUCCIÓN

técnicas en casos de estudio donde encontramos habitualmente las
mayores limitaciones en este sentido y caminar hacia flujos de trabajo
ágiles y sencillos para profesionales y técnicos no especialistas en
fotogrametría.
En lo referente a las documentaciones de arte rupestre, las técnicas
como la fotogrametría SfM, además de proporcionar modelos 3D de
alta resolución que aportan una información geométrica y radiométrica
más completa y precisa de los grabados que los métodos específicos
tradicionales, por su naturaleza no invasiva, siendo una técnica
totalmente respetuosa con elementos frágiles como las estaciones de
arte rupestre y por la capacidad de documentar elementos que los
métodos tradicionales no consiguen detectar, suponen en este campo
un avance todavía de mayor relevancia. No obstante, si bien los
modelos 3D en sí mismos son especialmente útiles para estudios de
arte rupestre, debido a la sinuosidad de algunos gravados, todavía es
necesario utilizar algún método de realce para obtener una mejor
visualización de los mismos. La bibliografía recoge varias
posibilidades para conseguir el realce de grabados, como por ejemplo
la generación de sombras relevantes basadas en la modificación de los
puntos de iluminación virtuales sobre el modelo 3D, como se muestra
en (Mudge et al., 2006). Otra posibilidad es la magnificación de los
ejes perpendiculares del objeto (eje Z), como se describe en (OrtizSanz et al., 2010). Otro método más avanzado denominado Reflectance
Transformation Imaging (RTI) (Díaz-Guardamino & D, 2013; Earl et
al., 2010; Mudge et al., 2006, 2012), que se basa en un análisis del
cambio del punto de iluminación en una colección de fotos del grabado,
ha supuesto un avance importante en el análisis de arte rupestre. En los
últimos años, otro flujo de trabajo originado en la comunidad de
gráficos por computadora (Pires et al., 2015; Saito & Takahashi, 1990),
denominado Radiance Scaling, basado en el análisis morfológico de
los modelos 3D como se describe en (Vergne et al., 2010, 2018) y que
es utilizado para la detección de grabados en (Carrero-Pazos et al.,
2012; López-Menchero Bendicho et al., 2017; Medici & Rossi, 2015),
ha demostrado un gran potencial para esta tarea. No obstante, conviene
profundizar y tratar de estandarizar, simplificar y objetivar los

35 | Página

<!-- p. 36 -->

SIMÓN PEÑA VILLASENÍN

procedimientos y variables de configuración posibles en la aplicación
de este realce.

Fotogrametría SfM
La fotogrametría de rango cercano se ha denominado históricamente a
la técnica que permite obtener datos métricos de objetos mediante
fotografías terrestres de los mismos (Albertz, J., Wiedemann, 1996;
Brown, 1972; Clarke & Fryer, 1998). Es una metodología con una
amplia trayectoria, que ha evolucionado considerablemente en las
últimas décadas en parte gracias al desarrollo de los algoritmos
Structure from Motion (SfM) y los cuales propiciaron su expansión
como método de documentación geométrica del patrimonio. A
diferencia de la fotogrametría convencional y las primeras versiones
del software de fotogrametría de corto alcance, que permiten la
manipulación exclusiva de puntos seleccionados discretamente y, por
lo tanto, de superficies simples, el software actual de fotogrametría SfM
permite la documentación de superficies complejas mediante un
proceso prácticamente automatizado en el que a partir de imágenes se
generan nubes de puntos, mallas de triángulos y modelos 3D
texturizados (Remondino & El-Hakim, 2006; Westoby et al., 2012).
Los orígenes de la fotogrametría SfM se encuentran en la
comunidad de visión artificial. (Furukawa et al., 2010; Spetsakis &
Aloimonos, 1991) y en el desarrollo de los algoritmos de identificación
automática de puntos homólogos (Harris & Stephens, 1988; Otto &
Chau, 1989). Cuatro factores destacan en la evolución de esta técnica.
En primer lugar el desarrollo de los referidos algoritmos. El paso de
procesado inicial en la fotogrametría SfM es la identificación de rasgos
característicos en imágenes para determinar su correspondencia
(Puntos homólogos). Mientras la fotogrametría convencional requiere
su identificación manual, los algoritmos automáticos, como el
algoritmo Scale-Invariant Feature Transform (SIFT), tal como se
describe en (Chandran et al., 1997; Lowe, 2004), han permitido que la
identificación de los puntos coincidentes en los pares estereoscópicos
sea automática, lo que ha reducido significativamente el tiempo
requerido para realizar esta tarea. El estado del arte en los algoritmos

36 | Página

<!-- p. 37 -->

INTRODUCCIÓN

de identificación automática de rasgos característicos de la imagen se
describe en (Remondino et al., 2014).
En segundo lugar, la automatización del proceso de calibración
mediante el cálculo inverso de los parámetros de orientación internos
y externos de las cámaras. Tal como se describe en (Clarke & Fryer,
1998; Fraser, 2013), el software reconstruye la escena de acuerdo con
los parámetros internos aproximados contenidos en los datos EXIF
(Exchangeable image file format) de cada imagen, junto con los puntos
homólogos obtenidos en el primer paso. El algoritmo de ajuste
Bundler, que se describe en (Snavely et al., 2008; Triggs et al., 2000),
se utiliza para estimar la posición de la cámara y extraer una primera
nube de puntos de poca densidad (sparse point cloud) formada por los
puntos homólogos detectados por el algoritmo SIFT (Tie Points). Por
lo tanto, las orientaciones internas y externa y la geometría de la escena
se reconstruyen simultáneamente en un solo proceso, sin la necesidad
de una calibración previa de la cámara. Estas características permiten
realizar estimaciones iniciales de las posiciones de la cámara y las
coordenadas del objeto, que luego se refinan de forma iterativa
utilizando la minimización no lineal de mínimos cuadrados.
En tercer lugar, utilizando las posiciones de cámara derivadas de
Bundler como entrada, es posible obtener una nube de puntos de mayor
densidad como salida (dense point cloud), implementando el algoritmo
Clustering view for Multiview Stereo (CMVS) y Patch-based Multiview
Stereo (PMVS2) (Furukawa et al., 2010; Furukawa & Ponce, 2010).
CMVS descompone las imágenes de entrada solapadas en subconjuntos
de tamaño manejable, y PMVS2 se usa para reconstruir datos 3D de
estos grupos individuales. La aparición de estos algoritmos nos ha
permitido mediante un proceso automatizado, trabajar con superficies
complejas (Barazzetti et al., 2011) y obtener nubes de puntos, mallas
de triángulos y, posteriormente un modelo texturizado tridimensional
completo (Westoby et al., 2012).
En cuarto lugar, unas mayores capacidades de computación,
especialmente incrementadas debido a la aparición de la computación
“en la nube” o cloud computing (Santagati & Inzerillo, 2013). Estos
avances han facilitado que en sectores como la arqueología (Ortiz-Sanz

37 | Página

<!-- p. 38 -->

SIMÓN PEÑA VILLASENÍN

et al., 2010), la arquitectura (Roncella et al., 2012), la conservación y
restauración (Guidi et al., 2004) o incluso en el mundo de la realidad
virtual (Bellotti et al., 2011) se utilice ampliamente la fotogrametría en
la última década. La fotogrametría SfM es capaz de obtener resultados
próximos a los del TLS (Bayram et al., 2015; J. H. Chandler & Buckley,
2016), y su comparación en coste tan favorable, hace que esta sea una
gran alternativa técnica para la adquisición de modelos 3D de alta
resolución. Además, esta técnica parece mostrar un grado de
adaptabilidad mayor a escenas complejas, como son los yacimientos
de arte rupestre, ya que estos avances, también han propiciado que la
fotogrametría SfM se muestre como una técnica flexible y adaptable a
múltiples tareas de documentación geométrica. No obstante, dada la
variabilidad metodológica que la fotogrametría SfM presenta, en
especial en las tareas previas al procesado, conviene tratar de
estandarizar los procedimientos que conlleva su aplicación.

Variabilidad metodológica de la ¡Error!
Marcador no definido.
Para llevar a cabo un modelado mediante fotogrametría SfM, deben
analizarse previamente los requisitos o condiciones técnicas del trabajo
de documentación y que marcarán en gran medida el desarrollo del
mismo, ya que la fotogrametría SfM presenta una gran variabilidad
metodológica en este sentido. Por ejemplo, para la documentación
geométrica de un área arqueológica extensa mediante fotogrametría, la
obtención de información métrica de precisión es uno de los objetivos
principales. Por otro lado, en trabajos de análisis de arte rupestre, la
precisión geométrica pasa a un segundo plano, siendo la obtención de
mallas de alta resolución para conseguir la detección del grabado el
principal objetivo en ese caso. En otras ocasiones, las necesidades
documentales no requieren obtener modelos 3D completos, sino
simplemente una planimetría suficientemente precisa y detallada que
es posible obtener mediante vectorización discreta a partir de los
emparejamientos estereoscópicos, o para tomar medidas sobre la malla
3D, para el traslado de las mismas a un modelo teórico. Por ello, la
fotogrametría siendo una técnica masiva de captura de datos puede

38 | Página

<!-- p. 39 -->

INTRODUCCIÓN

utilizarse también de forma discreta. En estos casos, es posible una
optimización de la metodología de captura en campo ya que no
necesariamente es un problema que los modelos 3D resultantes tengan
huecos o ciertas imprecisiones. Esta variabilidad en los objetivos del
trabajo, tiene una alta influencia en la técnica proporcionando a la
fotogrametría una horquilla de costes y tiempos de ejecución que
requiere estudiar detenidamente.
En la mayoría de trabajos realizados de documentación de
patrimonio arquitectónico, arqueológico y especialmente de arte
rupestre a nivel científico, así como las documentaciones geométricas
de petroglifos realizadas en Galicia a nivel profesional hasta la fecha,
se han utilizado habitualmente metodologías complejas que incluyen
la utilización de pértigas, drones, o instrumental topográfico, lo cual
resta a la técnica agilidad y sobretodo accesibilidad, de este modo, se
pierden las principales ventajas con las que cuenta de partida frente a
otras técnicas de modelado 3D. La accesibilidad de la fotogrametría
SfM, en cuanto a su facilidad de aprendizaje, está ampliamente
demostrada en artículos como (Gil-Docampo et al., 2019; Charalabos
Ioannidis et al., 2016), donde se muestra que estas técnicas a niveles
básicos son accesibles incluso a escolares. Para la obtención de datos
métricos fiables, son necesarios unos conocimientos previos, pero
estos se pueden adquirir con relativa facilidad y el software moderno
de fotogrametría es de uso sencillo e intuitivo sobre todo para tareas
rutinarias (Jim H. Chandler et al., 2007). Es por ello, que ante la
necesidad de documentar un número elevado de elementos
patrimoniales, es importante valorar los objetivos de dicha
documentación, los productos y precisiones deseadas en ella y adaptar
la metodología a las necesidades del trabajo, optimizando los tiempos
de ejecución con metodologías sencillas y ágiles. Por lo tanto, es
importante diferenciar los trabajos de documentación geométrica de
patrimonio con el objetivo de obtener un resultado de alta calidad
métrica y visual, habitualmente de un único elemento patrimonial, lo
cual requiere del empleo de tiempo, esfuerzo y medios técnicos más
avanzados, respecto de documentaciones patrimoniales menos
exigentes, pero de un número de elementos masivo, como puede ser la
documentación geométrica de ciudades históricas completas o

39 | Página

<!-- p. 40 -->

SIMÓN PEÑA VILLASENÍN

múltiples yacimientos de arte rupestre. Una vez determinado los
objetivos del trabajo de documentación y en función de estos, cinco
factores principales deben ser tenidos en cuenta para la planificación y
ejecución de los trabajos según se detallan en los apartados siguientes.

Escala del trabajo y Ground Sample Distance (GSD)
En fotogrametría aérea, se denomina resolución geométrica, en
adelante Ground Sample Distance (GSD), al tamaño de la porción de
terreno que representa cada pixel en una fotografía. Este concepto, es
trasladable a la fotogrametría de rango cercano y está relacionado
directamente con la escala del trabajo. Mediante fotogrametría de
rango cercano, es posible documentar desde áreas arqueológicas
extensas a objetos de pequeño tamaño. Incluso, en la documentación
de un mismo elemento patrimonial, es posible utilizar distintas escalas
de trabajo por zonas, en función de si se desea obtener mayor o menor
resolución geométrica en cada una de ellas. Es por ello que
previamente a la planificación de las tareas, es importante determinar
el GSD máximo exigido o GSD de trabajo.
Independientemente de la metodología empleada, la escala del
producto o resultado deseado en un trabajo de documentación
geométrica, y el límite de percepción visual determinan la tolerancia
del error métrico de dicho trabajo. Por otro lado, en trabajos de
fotogrametría SfM la determinación de las coordenadas 3D de cada
punto presenta mayor ambigüedad en la componente de profundidad
que en las componentes planimétricas. Siendo el error esperado en
planimetría igual al GSD de trabajo y de entre el doble y el triple en la
componente de profundidad (Peppa et al., 2016; Sanz-Ablanedo et al.,
2018). Por ello, para cumplir los requisitos de precisión métrica, la
planificación de la toma se debe realizar considerando la obtención de
un GSD entre la mitad y un tercio de la tolerancia de error en el mismo.
No obstante en trabajos de fotogrametría de rango cercano sobre
elementos con geometrías complejas, la disposición de imágenes puede
adoptar distintas distancias objeto, por lo que cabe valorar cómo afecta
esto a la calidad geométrica y visual de los resultados.

40 | Página

<!-- p. 41 -->

INTRODUCCIÓN

El sensor, la cámara fotográfica
Una vez establecido el GSD de trabajo, es momento de determinar
el tipo y componentes del sensor o cámara fotográfica a emplear. La
fotogrametría SfM permite gran variabilidad en este aspecto, pudiendo
emplearse desde cámaras de gran calidad, a cámaras de bajo coste,
incluso la integrada en dispositivos SmartPhone. La bibliografía de la
fotogrametría convencional recoge tres tipologías de cámaras:
métricas, no métricas y semimétricas (Lerma-García, 2002). Las
cámaras métricas o semimétricas se caracterizan por contar con
parámetros internos conocidos permitiendo reconstruir la geometría de
la escena a partir de las marcas fiduciales. Las cámaras no métricas
(cámaras convencionales) se caracterizan por tener una geometría
interna desconocida, por lo que es imprescindible previamente la
determinación de los parámetros de orientación internos para extraer
información métrica a partir de sus imágenes (Duane, 1971; LermaGarcía, 2002). A pesar de que la geometría interna de las cámaras
comerciales convencionales no métricas es generalmente inestable,
sobre todo de las lentes (Wackrow & Chandler, 2008), existen desde
hace décadas procesos de calibración interna, en los que se evalúan
parámetros como la distancia focal, distorsión radial y tangencial de la
lente (Duane, 1971), posición del centro óptico (Roelofs, 1950) o el
tamaño del CCD (Clarke & Fryer, 1998; Shortis et al., 1995), entre
otros, permitiendo su utilización en fotogrametría.
No obstante, gracias a los avances de la fotogrametría SfM, y
concretamente la automatización del proceso de calibración mediante
el cálculo inverso de los parámetros de orientación internos (Clarke &
Fryer, 1998; Fraser, 2013), actualmente es posible realizar las
orientaciones de la cámara en base a las imágenes del propio objeto sin
la necesidad de una calibración previa de la misma. La fotogrametría
SfM, permite además la calibración inversa de prácticamente cualquier
tipo y modelo de cámara, incluso con objetivos ojo de pez, los cuales
presentan una gran distorsión, es posible llevar a cabo trabajos
fotogramétricos con garantías (Beekmans et al., 2016). Por este
motivo, y aunque la elección del sensor fotográfico sigue teniendo gran
influencia en los resultados, los algoritmos de calibración inversa

41 | Página

<!-- p. 42 -->

SIMÓN PEÑA VILLASENÍN

permitiendo calibraciones internas de calidad de casi cualquier cámara,
hacen que esta variable sea cada vez menos importante.
En cuanto a las características de la cámara fotográfica, cabe
prestar especial atención en el tamaño y resolución del sensor así como
en el tamaño de la focal y calidad de la lente. En este sentido, se
recomienda el empleo de objetivos de focal fija con una distancia focal
comprendida entre el ancho y el largo del sensor, el cual debe contar
con una relación entre tamaño y resolución compensado (Mosbrucker
et al., 2017). En cualquier caso, cabe valorar el grado de influencia que
tiene la elección de la cámara e incluso valorar la posibilidad de
utilización de dispositivos SmartPhone en las tareas de documentación
geométrica básicas.

La red fotogramétrica
La precisión en trabajos de fotogrametría SfM actualmente no
depende tanto de la calidad del sistema fotográfico si no de una correcta
planificación y ejecución de la toma, ya que la disposición fotográfica,
o lo que es lo mismo, el diseño de la red fotogramétrica, es uno de los
factores que afectan a la calidad métrica de los resultados en mayor
medida (Remondino & El-Hakim, 2006). Por ello, una vez fijadas las
variables de resolución espacial (GSD) deseada y conocidas las
características de la cámara a utilizar, conviene planificar la toma
fotográfica para conseguir una red fotogramétrica robusta, formada por
fotos con orientaciones adecuadas para poder proporcionar modelos
3D con calidad métrica en todas las zonas del objeto. Además de en la
calidad geométrica, la disposición de tomas fotográficas también
influye en la calidad visual o radiométrica del modelo. En este sentido,
dejando zonas sin documentar fotográficamente o con perspectiva
oblicua lo que produce un fenómeno de estiramiento de la textura
(Santiago Martínez et al., 2013); o debido a los elementos que ocultan
parte del objeto al estar situados entre la cámara y este, provocando una
doble proyección (Al-kheder et al., 2009), incluso debido a las
diferencias de exposición o balanceado de colores en la toma
fotográfica, incluso la presencia de reflejos o brillos sobre el objeto
durante el fotografiado (Trinchão Andrade et al., 2012); son factores

42 | Página

<!-- p. 43 -->

INTRODUCCIÓN

que producen errores radiométricos en el mapeado de texturas
(Apollonio et al., 2012), no obstante, si el contraste no es excesivo, el
software actual es capaz de corregir en gran medida estos defectos
mediante técnicas de balance de color aplicadas sobre cada imagen.
Por lo tanto, entre los factores que se deben tener en cuenta para el
diseño de la red fotogramétrica, y que influyen en la calidad métrica y
visual de los resultados, se encuentran la distancian entre la cámara
fotográfica y el objeto, la disposición angular de la toma con respecto
a la superficie del mismo, el solape y orden de toma de las imágenes,
las limitaciones espaciales en el entorno del elemento, o la cobertura
de todas las superficies del mismo con suficientes fotografías.
Numerosos estudios y manuales de desarrolladores de software
fotogramétrico, proporcionan indicaciones estandarizadas de las
distribuciones espaciales de la toma fotográfica para la implementación
de fotogrametría SfM. Sin embargo, es común encontrar elementos
patrimoniales con geometrías complejas, donde estas indicaciones
metodológicas no son fácilmente aplicables y requieren una adaptación
mayor. Los mejores resultados (malla de triángulos sin agujeros, con
densidad uniforme y textura realista) se obtienen preferentemente con
imágenes tomadas con el eje de la cámara perpendicular a la superficie
del objeto, lo que requiere tomar estereopares para cada plano a
modelar, lo cual es tedioso o inviable en elementos de geometrías
complejas. Por otro lado, analíticamente la toma convergente u oblicua,
obtiene resultados más precisos que la toma perpendicular, requiere
menos imágenes para obtener la misma cobertura estereográfica, y
tiene una mayor confiabilidad interna (Mason, 1994). Cabe analizar
cómo se comportan los motores de procesado de fotogrametría SfM
modernos, y si pueden conseguir la correcta orientación externa de
combinaciones de fotos perpendiculares y oblicuas lo que permitiría
una gran adaptación a cualquier zona de estudio.
En cuanto a los parámetros fotográficos como la velocidad de
obturación, la sensibilidad y la apertura de diafragma, estarán
condicionados en gran medida por la cantidad de luz que entre en el
sistema fotográfico, la cual incluso será variable dependiendo de la
situación y ángulo de cada punto de toma. La elección de unos
parámetros fotográficos apropiados tendrá por lo tanto también

43 | Página

<!-- p. 44 -->

SIMÓN PEÑA VILLASENÍN

influencia en la calidad visual como geométrica de los resultados. En
este sentido, se recomienda la utilización de sensibilidades ISO bajas,
velocidades de obturación tan altas como la estabilidad de la toma
permita sin provocar “trepidación” (Peres, 2013) y aperturas de
diafragma preferentemente pequeñas sin alejarse en exceso del punto
dulce del objetivo donde la lente ofrece mayor nitidez (Hollows &
Singer, 2009).
Por otro lado, especialmente para trabajos de patrimonio
arquitectónico, la altura del elemento a modelar, suele ser uno de los
aspectos más restrictivos ya que puede implicar la utilización de
sistemas de elevación de la toma. Con estos se consiguen obtener
fotografías desde perspectivas superiores que fortalecen
geométricamente la red fotogramétrica y además, permiten capturar
elementos no visibles correctamente desde las fotografías a nivel de
suelo, no obstante son medios que hacen más compleja la toma
restando agilidad y accesibilidad a la técnica. En cuanto al empleo de
dispositivos de estabilización como trípodes, que permiten la
realización de largas exposiciones para la obtención de imágenes de
gran nitidez, es otro factor que puede afectar a los resultados finales
favorablemente, pero prolongar los tiempos de ejecución en campo,
por lo que su utilización, al igual que los dispositivos de elevación,
conviene valorarla en función de los requisitos del trabajo.

El sistema de orientación y escalado de la escena
Otro aspecto a tener en cuenta, con gran influencia en los tiempos
y costes de ejecución de un trabajo fotogramétrico, es el método
empleado en el establecimiento de la red de puntos de apoyo o medidas
de referencia. Los puntos de apoyo, son puntos de coordenadas
conocidas, identificables en las imágenes y que cumplen una doble
función en el ajuste fotogramétrico, por un lado escalar y orientar el
modelo 3D en el espacio, bien sea en coordenadas relativas o absolutas,
y por otro lado, mejorar el propio ajuste fotogramétrico teniendo
influencia tanto en los parámetros de orientación interna de las cámaras
como en los de orientación externa. El establecimiento de una red de
puntos de apoyo suele ir ligada al empleo de instrumental topográfico,

44 | Página

<!-- p. 45 -->

INTRODUCCIÓN

lo que reduce considerablemente la agilidad de ejecución de la técnica.
Por otro lado, el empleo de medidas de referencia permite escalar y
orientar el modelo ágilmente con una precisión nada despreciable
como se muestra en estudios previos (Remondino & El-Hakim, 2006).
Además en ocasiones, como en estudios de arte rupestre o
inscripciones donde los objetivos del trabajo son la detección y análisis
de los grabados, la calidad métrica del modelo pasa a un segundo plano,
permitiendo la utilización de una metodología de toma de datos en
campo realmente ágil, por lo que conviene valorar qué método de
orientación y escalado se debe utilizar.

Las variables y configuraciones del procesado SfM
Por último, la elección del motor de procesado tendrá también
influencia en la calidad de los resultados, rendimiento y accesibilidad
de la técnica. La popularización de la fotogrametría SfM, se ha
producido especialmente a raíz de su utilización por una gama de
motores de procesado “en la nube” entre los que destacan Photosynth
(Microsoft Corporation, EE. UU.) (Snavely et al., 2008), 123D Catch
(Autodesk Inc., USA) (Lavy et al., 2015), ARC3D (Ku Leuven,
Belgium) (Tingdahl & Van Gool, 2011), o Recap Photo (Autodesk
Inc., USA) (Eulitz & Reiss, 2015; Greif et al., 2017) los cuales han
permitido la expansión del uso de la fotogrametría SfM de un modo
básico al público en general. Posteriormente, en el software profesional
de fotogrametría, se implementan los algoritmos SfM, surgiendo
soluciones de software de procesado local como Photomodeler
Scanner (Eos Systems Inc, Canada) (Alby et al., 2009), Pix4D (EPFL,
Switzerland) (Turner et al., 2014) o el antiguo PhotoScan (Agisoft
LLC., Rusia) (De Reu et al., 2013a) actualmente llamado MetaShape,
entre otros.
Los procesados SfM tienen un alto grado de automatización, pero
el operario todavía puede influir en gran medida en la calidad de los
resultados. En este sentido, el software desktop profesional permite
configurar un número mayor de parámetros pero requiere de
conocimientos de manejo específicos. En las opciones de computación
“en la nube”, más enfocadas a aficionados o profesionales no expertos

45 | Página

<!-- p. 46 -->

SIMÓN PEÑA VILLASENÍN

en fotogrametría, prácticamente no es posible configurar ningún
parámetro del procesado excepto el grado de calidad o profundidad del
mismo. Las variables de configuración del procesado fotogramétrico
que influyen en los resultados son numerosas, no obstante el parámetro
denominado “calidad” es el más relevante y está presente tanto en
software cloud computing como en distintas fases del procesado en
software desktop. Por ello, es el principal parámetro de influencia en la
calidad de los resultados en cuanto al método de procesado. Este
parámetro hace referencia a un tipo de representación de imágenes a
múltiples escalas desarrollada por las comunidades de visión por
computadora denominado “imágenes piramidales”, que permite que el
software trabaje con reducciones de la resolución de la imagen original
de cara a agilizar el procesado. La necesidad de agilizar el procesado
se debe a que este requiere de altas capacidades de computación, por
lo que la elección del parámetro “calidad” tiene gran influencia en los
tiempos de ejecución y consecuentemente en los costes del trabajo. En
este sentido, las opciones de computación “en la nube” pueden ser
interesantes para agilizar documentaciones de elementos masivos, ya
que no requieren conocimientos específicos de manejo ni grandes
inversiones en hardware y software.

Evaluación de las variables metodológicas de la
fotogrametría
Para evaluar cómo influyen las distintas variables metodológicas de un
proceso fotogramétrico en la calidad geométrica y visual de los
resultados del mismo, así como en el rendimiento y accesibilidad de la
técnica, es necesario diseñar experimentos que permitan aislar y
analizar su comportamiento. En este sentido, los más habituales son
aquellos trabajos que comparan técnicas que difieren en la cámara
fotográfica empleada (J.H. Chandler et al., 2005; Chiabrando et al.,
2011; J Ortiz et al., 2005); en el número y distribución de puntos de
control (Deng & Faig, 2001; Karras et al., 1999; Sanz-Ablanedo et al.,
2018); en el número de fotografías realizadas (Jim H Chandler et al.,
2003; Stojic et al., 1998); en la técnica de calibración empleada (Jim H
Chandler et al., 2003; Pappa et al., 2001; Schneider et al., 2009); o en

46 | Página

<!-- p. 47 -->

INTRODUCCIÓN

el software utilizado (Barazzetti et al., 2011). Una vez diseñado el
experimento, y establecido el aislamiento de las variables, para su
evaluación en términos de calidad geométrica, calidad visual,
rendimiento y accesibilidad de la técnica, para su evaluación la
bibliografía recoge distintos indicadores que se detallan a
continuación.

Indicadores de calidad geométrica
Para la evaluación de la calidad geométrica de los resultados
obtenidos mediante fotogrametría terrestre, actualmente en la
bibliografía no hay definido un procedimiento estándar, tal y como si
existe en fotogrametría aérea (ISO 19115-2:2009) (Di et al., 2013). No
obstante, en la mayoría de estudios previos se emplea un sistema
basado en el cálculo de la calidad de medida (MQ, metric quality), en
base a la comparación de puntos de contraste reales (True Check
Points, TCPs) y la obtención de puntos de contraste fotogramétricos
(Photogrammetric Check Points, PCPs) (Bolognesi et al., 2015;
Martínez-Rodríguez et al., 2015; Uysal et al., 2015). Para ello en
primer lugar es necesario la medición de los TCPs mediante una
técnica más precisa que la técnica fotogramétrica evaluada. A pesar de
que hay trabajos que emplean tecnología específica (Abd Elbasit et al.,
2009; Jiang & Jauregui, 2007), en la mayor parte de los casos se utiliza
la estación total (Arias et al., 2006; Barazzetti et al., 2011; Desmond &
Bryan, 2003; Fujii et al., 2009; Kvamme et al., 2006); un calibre (OrtizSanz et al., 2010), un flexómetro (Martínez-Rodriguez et al., 2013) o
un láser escáner terrestre (Sturzenegger & Stead, 2009).
A continuación, se extraen las características métricas de los PCPs
a partir del modelo 3D fotogramétrico. Es importante incidir en la
diferenciación entre los puntos de apoyo terrestre (GCPs) y los PCPs
(Jim H Chandler et al., 2003). Los primeros intervienen en el ajuste
fotogramétrico mejorando la calibración de los parámetros internos y
externos de las cámaras, y por lo tanto, como parte del proceso, no
deben formar parte de la evaluación de los resultados; los segundos, se
definen con posterioridad al ajuste fotogramétrico y por lo tanto
permiten que el control de calidad geométrica sea independiente al
mismo. Para su establecimiento, principalmente se utilizan dos

47 | Página

<!-- p. 48 -->

SIMÓN PEÑA VILLASENÍN

métodos: el marcado de los mismos directamente sobre las imágenes
del trabajo, lo cual proporciona un análisis de la calidad geométrica de
la restitución discreta sobre los emparejamientos estereoscópicos; o el
marcado de los puntos directamente sobre el modelo 3D texturizado
que proporciona un análisis real de la calidad geométrica de este. Es
posible evaluar también la calidad geométrica de otros entregables,
como las ortoimágenes o los Modelos Digitales de Elevación (MDE),
a través del marcado directo de PCPs para el control planimétrico, en
el caso de las ortofotos, o para el control altimétrico o de profundidad
sobre los modelos de elevación.
Finalmente, para obtener una expresión numérica que proporcione
un valor de la MQ de las variables fotogramétricas evaluadas, es
necesario seguir un procedimiento estadístico de comparación de las
diferencias observadas en dos parámetros de contraste (errores en la
estimación de coordenados y/o en la estimación de la distancias) entre
los TCPs y los PCPs.
La evaluación del error en la estimación de coordenadas se realiza
mediante la comparación directa de las coordenadas de los PCPs y los
TCPs. Para ello es necesario que ambos tengan el mismo sistema
espacial de coordenadas. De esta forma se obtiene el error en cada una
de las componentes, siendo el error total la raíz cuadrada de la suma
del cuadrado de los errores anteriores.
Para la evaluación de los errores entre TCPs y PCPs mediante la
medición de distancias se comparan las distancias medidas entre los
TCPs tomados dos a dos, con las mismas distancias entre los PCPs
(Jiang & Jauregui, 2007). A diferencia del análisis en base a las
coordenadas, en este caso no es necesario que exista un sistema de
coordenadas común siendo el único requisito que el modelo se
encuentre escalado.
Los indicadores anteriores nos proporcionan la MQ de los puntos
individuales empleados para el control de calidad geométrica, no
obstante es necesario obtener un valor final representativo e indicativo
de la calidad global del método fotogramétrico, por lo que conviene
realizar un tratamiento estadístico de todos los puntos comparados. La
media aritmética, muestra el valor central de los datos observados,

48 | Página

<!-- p. 49 -->

INTRODUCCIÓN

siendo la que más se utiliza tanto para estimar el error entre distancias
(Guidi et al., 2003) como en coordenadas (Aguilar et al., 2005);
Algunos autores recurren a la media del error (Jiang & Jauregui, 2007;
Lejot et al., 2007) o a la media del valor absoluto del error (Barazzetti
et al., 2011). Otros índices empleados son, el MSE, que calcula la
media aritmética de los cuadrados de los errores (J Ortiz et al., 2005) y
el RMSE, una medida de la diferencia entre los valores pronosticados
por un modelo o un estimador y los valores observados de la realidad
(Abd Elbasit et al., 2009; Aguilar et al., 2005; Arias et al., 2007; Yilmaz
et al., 2007).
Por otro lado, para la estimación de la precisión se recurre a la
desviación estándar o desviación típica. Es una medida de dispersión
que nos indica cuánto tienden a alejarse los valores individuales del
valor promedio. La desviación estándar se emplea como estimador de
la MQ tanto en el caso de comparación de distancias como de
coordenadas (Aguilar et al., 2005; Jim H Chandler et al., 2003;
Chiabrando et al., 2011; González-Aguilera et al., 2009; Wackrow &
Chandler, 2008). Finalmente, cabe señalar que es importante
proporcionar la estimación del error de modo relativo al tamaño del
objeto referenciando este a la diagonal principal del mismo.

Indicadores de calidad visual
La calidad visual de un modelo fotogramétrico, en primera
instancia está ligada a la resolución geométrica (GSD) con la que se
hayan obtenido la colección de imágenes para la generación del mismo.
Este parámetro marca la resolución máxima posible para obtener la
textura del modelo 3D sin el remuestreo de la información de las
fotografías.
Por otro lado, para evaluar la calidad visual del modelo, será
necesario también estudiar la presencia de errores en la textura en zonas
sin documentar fotográficamente o con deformaciones. En estas,
habitualmente se produce un fenómeno de estiramiento de la textura
(Juan Ortiz et al., 2013), en un intento del software por completar esa
parte carente de información. En otras ocasiones se produce una doble
proyección originada cuando la textura se aplica dos veces, una

49 | Página

<!-- p. 50 -->

SIMÓN PEÑA VILLASENÍN

primera sobre la parte correcta del elemento, y otra sobre la zona
oculta, es decir, los píxeles del elemento situado delante se proyectan
sobre el que se encuentra detrás según la perspectiva de la foto (Alkheder et al., 2009). Otro aspecto a considerar en la evaluación de la
calidad visual del modelo, es la presencia de diferencias radiométricas
en el mapeado de texturas (Apollonio et al., 2012), las cuales
repercuten en la calidad estética y en el realismo del modelo 3D,
aunque su posición sobre la malla poligonal sea correcta. Estas se
deben a las variables condiciones de iluminación que se van
sucediendo durante el proceso de fotografiado y que ofrecen como
resultado desigualdades de color entre los diferentes parches de textura
extraídos de las fotografías seleccionadas por el software. Si el
contraste no es excesivo, el software actual es capaz de corregir este
defecto mediante técnicas de balance de color aplicadas sobre cada
imagen. En (Trinchão Andrade et al., 2012) se recogen también errores
en el color por la presencia de reflejos o brillos sobre el objeto durante
el fotografiado.

Indicadores de rendimiento y accesibilidad
Los principales indicadores de rendimiento y accesibilidad se
definen a continuación de modo independiente para tiempos y costes,
facilidad de aprendizaje y cobertura de necesidades en
documentaciones de patrimonio arquitectónico y arte rupestre.

Tiempos y costes
Para la evaluación del rendimiento de una técnica deben
considerarse principalmente los tiempos y costes que conlleva su
ejecución, estos deben ser medidos individualmente para cada fase del
proceso diferenciando entre el trabajo de campo y de oficina.
Para la evaluación de los tiempos de trabajo de campo, la toma
fotográfica y el establecimiento de la red de GCPs son las principales
tareas a considerar. Cabe señalar que los tiempos empleados para el
establecimiento de la red de TCPs, no deben ser considerados en la
evaluación ya que no son indispensables para la ejecución de la técnica,

50 | Página

<!-- p. 51 -->

INTRODUCCIÓN

y solo se ejecutarían en campo si se desea obtener un control de calidad
geométrica independiente al procesado.
En cuanto al trabajo de oficina, deben considerarse los tiempos de
procesado y post procesado de los modelos 3D. En este aspecto, cabe
diferenciar entre el trabajo que requiere la interacción del usuario y los
tiempos de computación informática automatizada en los que la
presencia del técnico no es necesaria.
Para la evaluación de los costes de ejecución de la distintas
variables metodológicas, deben considerarse tanto los costes de
equipamiento de campo como de los equipos informáticos y licencias
de software necesarias para el procesado y desarrollo completo de las
tareas.

Adaptabilidad a zonas complejas
Las metodologías de adquisición de datos 3D como la
fotogrametría SfM o el TLS, por su naturaleza masiva, son técnicas con
una gran adaptabilidad en cuanto al objeto de estudio, ya que permiten
la obtención de datos métricos y radiométricos de alta resolución de
casi cualquier elemento. No obstante, más allá de la adaptabilidad al
objeto de estudio, es importante analizar la adaptabilidad de ambas
técnica a las necesidades y limitaciones presentes en distintos
escenarios de trabajo.
Para ello, es necesario testear la calidad de sus resultados en
escenarios de distinta complejidad, ya que si bien es importante evaluar
cómo se comporta la técnica en escenarios tipo o estándar, es también
importante evaluar el rendimiento en escenarios complejos o extremos,
los cuales son habituales en estudios de patrimonio arquitectónico y
arqueológico. Es importante también analizar las necesidades y
limitaciones que en dichos escenarios presenta la técnica para la
ejecución de la toma de datos, en especial aquellas metodologías que
requieren el uso de trípodes como en caso del TLS o en ocasiones la
fotogrametría, y que por lo tanto requieren de lugares relativamente
amplios y estables para su correcto desarrollo.

51 | Página

<!-- p. 52 -->

SIMÓN PEÑA VILLASENÍN

Por último, el indicador cuantitativo principal a considerar para la
evaluación de la adaptabilidad de la técnica a distintos escenarios es el
peso de los equipos, siendo un indicador importante si los trabajos son
en zonas forestales o de difícil acceso, lo cual es habitual en estudios
de patrimonio arqueológico.

Facilidad de aprendizaje
Para estudiar la accesibilidad de una técnica en cuanto a su
facilidad de aprendizaje y ejecución, es conveniente someter su
utilización a distintos perfiles de usuario. Se considerará una técnica
con facilidad de implementación aquella que sea fácilmente asimilable
y ejecutable por perfiles no técnicos como escolares, aficionados al
patrimonio o profesionales no especializados en metrología como
arqueólogos, historiadores o conservadores (Gil Docampo et al., 2019;
Charalabos Ioannidis et al., 2016).

Cobertura de necesidades en estudios de arte
rupestre
Además de las necesidades métricas y visuales en la obtención
de los modelos 3D para documentación patrimonial, cabe analizar la
cobertura de necesidades en lo referente a los estudios de detección y
análisis de arte rupestre, debido a que la calidad geométrica y visual
del modelo 3D pasa a un segundo plano en estos casos. En estudios de
arte rupestre, el entregable final son los calcos vectoriales del grabado,
los cuales son comparables directamente a los obtenidos con otras
metodologías sobre la misma muestra de estudio, todo ello con el
objetivo de analizar el mayor o menor potencial en la detección y
discriminación de grabados antrópicos de la metodología empleada
(Carrero-Pazos et al., 2012, 2018), independientemente de la calidad
geométrica y visual del modelo 3D. Por otro lado, el arte rupestre
gallego integra distintas tipologías en el diseño de los grabados
(Cuevillas, 1951; Varela, 1982), por lo que el análisis debe realizarse
sobre una muestra representativa del fenómeno.

52 | Página

<!-- p. 53 -->

INTRODUCCIÓN

Cobertura de necesidades en estudios de
patrimonio arquitectónico
En ocasiones las necesidades de documentar el patrimonio
arquitectónico no tienen como objetivo obtener modelos 3D ni
ortofotos de alzados, habitualmente en su lugar se demandan planos
vectoriales y por lo tanto, aunque la textura del modelo o la ortofoto
presente errores, estos no necesariamente impiden obtener de forma
correcta dichas vectorizaciones. Es por ello que cabe analizar la
cobertura de necesidades de la técnica, no solo en la obtención de
modelos 3D de alta calidad geométrica y visual, sino también en este
sentido.

53 | Página

<!-- p. 54 -->



<!-- p. 55 -->

OBJETIVOS

\4. OBJETIVOS

Dada la variabilidad metodológica que presenta actualmente la
fotogrametría SfM, el objetivo principal de esta tesis es evaluar
diferentes metodologías fotogramétricas SfM de bajo coste para la
documentación geométrica del patrimonio arquitectónico y
arqueológico, analizando los resultados obtenidos fundamentalmente
en términos de calidad geométrica, calidad visual, rendimiento y
accesibilidad de la técnica. Para lograr este objetivo general es
necesario alcanzar los siguientes objetivos específicos:

\1. Con el objetivo de analizar la calidad geométrica y visual, el
rendimiento y la accesibilidad de la fotogrametría SfM para el
levantamiento de fachadas de centros históricos de ciudades, se efectúa
el modelado de varias tipologías arquitectónicas en el casco histórico
de Santiago de Compostela, proponiendo una estandarización
metodológica en lo referente al establecimiento de una correcta red
fotogramétrica con dos enfoques principales: la búsqueda de un alto
rendimiento y accesibilidad de la técnica mediante un flujo de trabajo
muy simple en los casos de estudio “estándar” donde la aplicación de
la fotogrametría SfM es sencilla; y la búsqueda de una metodología que
permita el levantamiento de fachadas consideradas casos complejos
donde las limitaciones geométricas de la escena son “extremas” o más
dificultosas para el empleo de la técnica, como una calle estrecha o una
fachada con soportales. Estos objetivos se consiguen en el primer
capítulo de esta tesis.

55 | Página

<!-- p. 56 -->

SIMÓN PEÑA VILLASENÍN

\2. Con el objetivo de evaluar las variables de software de procesado
fotogramétrico para documentaciones de patrimonio arquitectónico, se
realiza la comparación de resultados entre dos opciones de software
fotogramétrico profesional de computación local como son PhotoScan
y Pix4D, con software fotogramétrico de uso gratuito para fines sin
ánimo de lucro como es Recap Photo. La comparación es realizada
sobre dos colecciones de imágenes comunes correspondientes al
Monasterio de San Martín Pinario y a la fachada oeste de Praza da
Inmaculada, ambos casos en el casco histórico de Santiago de
Compostela. La metodología, resultados y conclusiones del estudio se
recogen en el segundo capítulo de esta tesis.

\3. Con el objetivo de evaluar la calidad geométrica, calidad visual,
rendimiento y accesibilidad de la fotogrametría SfM en la
documentación geométrica de petroglifos de geometrías complejas, se
ha realizado el modelado del petroglifo de O Castriño de Conxo en
Santiago de Compostela, mediante un flujo de trabajo simple,
optimizado y con software gratuito y sus resultados se comparan con
los obtenidos mediante tecnología TLS de última generación. La misma
metodología fotogramétrica es aplicada en otros casos de arte rupestre
galaico-portugués con el objetivo de evaluar la técnica en una muestra
representativa de este fenómeno cultural. Además, con el objetivo de
analizar la cobertura de necesidades para la documentación de arte
rupestre, se testea el método de realce de modelos 3D basado en el
renderizado Radiance Scaling, comparando sus resultados con
documentaciones previas realizadas con métodos convencionales. La
metodología, resultados obtenidos y conclusiones del estudio se
recogen en el tercer capítulo de esta tesis.

\4. Por último, con el objetivo de evaluar la facilidad de aprendizaje
y cobertura de necesidades de la metodología desarrollada en el capítulo
anterior en la documentación vectorial de grabados rupestres, se ha
realizado un estudio en el que se evalúa el trabajo colaborativo en el
que participaron miembros de la asociación de amantes del arte rupestre
“Colectivo A Rula” (Santiago de Compostela), quienes tras una breve
sesión de formación de 3 horas, realizaron la toma de imágenes en

56 | Página

<!-- p. 57 -->

OBJETIVOS

campo de varias muestras de arte rupestre, en algunos casos inéditas,
para un modelado 3D mediante software cloud computing de uso
gratuito. Además, con el objetivo de estandarizar y objetivar una
metodología simple y un flujo de trabajo completo para el análisis de
arte rupestre, se testean distintas opciones de configuración de
renderizados de realce y vectorización automática sobre los casos de
estudio documentados. Estos objetivos se consiguen en el cuarto
capítulo de esta tesis.

57 | Página

<!-- p. 58 -->



<!-- p. 59 -->

CAPITULO I

\5. CAPITULO I

MODELADO 3D DE FACHADAS HISTÓRICAS
MEDIANTE FOTOGRAMETRÍA SFM.
DOCUMENTACIÓN GEOMÉTRICA DE
DISTINTAS TIPOLOGÍAS
ARQUITECTÓNICAS DE UN CASCO
HISTÓRICO.

RESUMEN
Uno de los principales factores que afectan a la calidad de los
resultados en la aplicación de técnicas fotogramétricas para el modelado
3D de elementos patrimoniales, es la limitación de espacio en la escena
de trabajo. Numerosos estudios muestran la confiabilidad de la
fotogrametría Structure from Motion (SfM) cuando el objeto está
ubicado en un espacio grande y accesible; sin embargo, al aplicar esta
técnica a un caso particular, la toma fotográfica debe adaptarse a las
particularidades de cada ubicación. Este artículo presenta la
documentación fotogramétrica de fachadas urbanas de diferentes
tipologías en cascos históricos, centrándose en el establecimiento de
una red fotogramétrica que permita resolver las particularidades
geométricas de cada caso. El centro histórico de Santiago de
Compostela (España) ha sido elegido para este estudio. Se
seleccionaron cuatro casos representativos de diferentes tipologías
urbanas: “fachada significativa”, “fachada en una calle estándar”, “calle

59 | Página

<!-- p. 60 -->

SIMÓN PEÑA VILLASENÍN

estrecha” (relación entre ancho de calle y alto de fachada menor que
1/3) y “fachada con soportales”. Todos se han resuelto
satisfactoriamente, obteniéndose errores relativos entre 1/770 y 1/1040.

60 | Página

<!-- p. 61 -->

MODELADO 3D DE FACHADAS HISTÓRICAS MEDIANTE FOTOGRAMETRÍA SFM.
DOCUMENTACIÓN GEOMÉTRICA DE DISTINTAS TIPOLOGÍAS
ARQUITECTÓNICAS DE UN CASCO HISTÓRICO.

Introducción
La necesidad de preservar los centros históricos se deriva
principalmente de su papel como elemento integrante del patrimonio
cultural y como recurso para el sector turístico-cultural (Chang et al.,
1996; Steinberg, 1996). Su documentación es esencial para abordar
adecuadamente su protección efectiva. Una parte importante de la
documentación de construcciones históricas es la adquisición de datos
geométricos. El uso de técnicas de adquisición de datos de ingeniería,
como el escáner láser terrestre, en el proceso de documentación del
patrimonio cultural se ha realizado ampliamente en la última década
con excelentes resultados (Arayici, 2007; Brumana et al., 2014). Este
método proporciona mayor precisión que los métodos tradicionales,
acelera significativamente el proceso y proporciona modelos
tridimensionales completos y de alta calidad. El modelado
tridimensional puede ser una herramienta de gran potencial en la
identificación, seguimiento, conservación y restauración de todo tipo de
patrimonio arquitectónico (Lerones et al., 2010). La utilidad de los
modelos 3D, por ejemplo en el caso de un elemento del patrimonio
perdido o dañado, para utilizarlo en exposiciones virtuales o para fines
educativos se ha demostrado en muchas ocasiones, resultando en una
expansión en el uso de esta nueva tecnología para la documentación del
patrimonio por parte de diferentes técnicos (Martínez et al., 2012).
Paralelamente a la expansión del escaneo láser terrestre, causada por la
creciente demanda de modelos 3D, la fotogrametría digital,
especialmente la fotogrametría de corto alcance, se ha beneficiado de
avances significativos y una creciente popularidad en sectores como la
arqueología (De Reu et al., 2013 and Yilmaz et al., 2008), la
arquitectura (Guarnieri et al., 2013 y Kang et al., 2010), el urbanismo
(Stojakovic and Tepavcevic, 2011), la restauración y conservación
(Martínez et al., 2013), e incluso en el mundo de la realidad virtual
(Bellotti et al., 2011). Esto se debe principalmente a que la inversión
requerida para el modelado en 3D por fotogrametría es
significativamente menor que la de la adquisición de un escáner láser
terrestre, y proporciona una adaptación más operativa a las necesidades
de estos grupos (Sanz et al., 2010).

61 | Página

<!-- p. 62 -->

SIMÓN PEÑA VILLASENÍN

La fotogrametría digital convencional de corto alcance es una
técnica que se ha utilizado durante muchos años. Desde su aparición, se
ha convertido en una herramienta poderosa y ampliamente utilizada
para el modelado tridimensional (Remondino and El-Hakim, 2006,
and Fraser and Cronk, 2009). El desarrollo de la aerotriangulación y los
algoritmos de extracción de información 3D a partir de imágenes, han
mejorado radicalmente la calidad de los datos 3D obtenidos con estas
técnicas (Chandler, 1999 and Lane et al., 2000). Del mismo modo, las
mejoras en el coste y la calidad de las cámaras réflex compactas y de
lente única (Single lens réflex, SLR) y los métodos para la calibración
de dichas cámaras no métricas (Clarke and Fryer, 1998 and Chandler et
al., 2005) han contribuido a una mayor expansión de estas técnicas
abaratando su coste de ejecución.
Numerosos estudios muestran que la precisión de los modelos 3D
generados con estas técnicas están en valores cercanos al centímetro
(Arias et al., 2007, Yilmaz et al., 2008, Chiabrando et al., 2015, Galizia
et al., 2015 and such). En estas investigaciones, se ha evaluado la
precisión del método comparando las coordenadas proporcionadas por
la estación de trabajo fotogramétrica digital con las coordenadas
obtenidas por medio de métodos topográficos más precisos con respecto
a una serie de puntos distribuidos homogéneamente en el objeto. En
este capítulo, se muestra un método fotogramétrico emergente de bajo
coste para la documentación geométrica de alta resolución,
fotogrametría Structure from Motion (SfM), que es ideal para la
investigación de patrimonio arquitectónico de bajo presupuesto. Los
manuales fotogramétricos para desarrolladores de software brindan
indicaciones estandarizadas de las distribuciones espaciales de la toma
fotográfica para la implementación de SfM. Sin embargo, en el campo
de los centros históricos, es común encontrar lugares donde estas
indicaciones metodológicas no son aplicables. El objetivo de esta
investigación es desarrollar una metodología que se ajuste a estas
particularidades geométricas, permitiendo el procesado de imágenes a
partir de esta técnica.
El capítulo está estructurado de la siguiente manera. El procesado
Structure from Motion se describe en la sección 2. La metodología de
toma de imágenes se muestra y analiza en la sección 3. La sección 4

62 | Página

<!-- p. 63 -->

MODELADO 3D DE FACHADAS HISTÓRICAS MEDIANTE FOTOGRAMETRÍA SFM.
DOCUMENTACIÓN GEOMÉTRICA DE DISTINTAS TIPOLOGÍAS
ARQUITECTÓNICAS DE UN CASCO HISTÓRICO.

describe en detalle la adaptación metodológica de la toma que permite
la restitución fotogramétrica de tipologías comunes en un centro
histórico, así como las tareas principales que requiere este proceso. Los
resultados gráficos y numéricos se presentan en la sección 5.
Finalmente, las conclusiones principales de este estudio se presentan en
la sección 6.

Algoritmos Structure from Motion (SfM).
La fotogrametría SfM, funciona bajo los mismos principios básicos que
la fotogrametría convencional, es decir, que los datos 3D pueden
resolverse desde un mínimo de dos puntos de vista diferentes como se
muestra en la figura 1, donde P (X, Y, Z) es el punto 3D que debe ser
medido, P1 y P2 son sus proyecciones en las imágenes y C1 y C2 son
los centros ópticos de las dos cámaras (Orteu, 2009). Sin embargo,
difiere fundamentalmente de la fotogrametría convencional en que la
geometría de la escena, las posiciones y la orientación de la cámara se
determinan automáticamente mediante un procedimiento de ajuste del
bloque de modo iterativo y altamente redundante, basado en
características de las imágenes extraídas automáticamente (Snavely et
al., 2008).

Figura 1. Principio de Visión Estereoscópica

63 | Página

<!-- p. 64 -->

SIMÓN PEÑA VILLASENÍN

Esta técnica tiene sus orígenes en la comunidad de visión por
ordenador (Spetsakis & Aloimonos, 1991; Richard Szeliski & Kang,
\1994) y el desarrollo de algoritmos automáticos de coincidencia de
características (Harris & Stephens, 1988; Otto & Chau, 1989). Una
gama de motores de procesado “en la nube”, especialmente Photosynth
(Microsoft Corporation, EE. UU.) Ha popularizado la técnica de SfM
(Snavely et al., 2008). Recientemente, servicios gratuitos de
computación “en la nube”, como 123D Catch (Autodesk Inc., EE. UU.)
(Lavy et al., 2015), ARC3D (Ku Leuven, Belgium) (Tingdahl & Van
Gool, 2011) o Recap Photo (Autodesk Inc., USA) (Ružić et al., 2014),
o servicios de computación local, como Apero MicMac (IGN, France)
(Deseilligny & Clery, 2011), se han presentado como alternativas
gratuitas o de bajo coste, a opciones de software profesional como
PhotoScan (Agisoft LLC., Russia) (De Reu et al., 2013b),
Photomodeler Scanner (Eos System Inc., Canada) (Barazzetti et al.,
\2011) o Pix4D (EPFL, Switzerland) (Turner et al., 2014).
Los métodos fotogramétricos tradicionales requieren las
ubicaciones tridimensionales de una serie de puntos de control en las
imágenes. Los puntos de control se identifican manualmente, y
mediante el método general de la fotogrametría, se determina la
posición y orientación de las tomas fotográficas. Por el contrario, en
SfM, la ubicación y orientación de las cámaras y la geometría de la
escena se reconstruyen simultáneamente a través de la identificación
automática de las características coincidentes, o lo que es lo mismo,
identificación automática de puntos homólogos. Estos puntos permiten
realizar estimaciones iniciales de las posiciones de la cámara y las
coordenadas del objeto, que luego se refinan de forma iterativa por
mínimos cuadrados. El paso inicial es la identificación de
características en imágenes individuales (puntos clave). Una solución
popular para esto es el algoritmo Scale-Invariant Feature Transform
(SIFT) (Chandran et al., 1997). Tras la identificación de los puntos
clave, se utiliza el algoritmo Bundler Adjusment (Pierrot Deseilligny &
Clery, 2012; Snavely et al., 2008) para estimar las posiciones y
orientaciones de las cámaras y extraer una nube de puntos dispersa de
objeto. Posteriormente, se puede obtener una nube de puntos de mayor
densidad a partir del algoritmo Clustering View for Multi-view Stereo

64 | Página

<!-- p. 65 -->

MODELADO 3D DE FACHADAS HISTÓRICAS MEDIANTE FOTOGRAMETRÍA SFM.
DOCUMENTACIÓN GEOMÉTRICA DE DISTINTAS TIPOLOGÍAS
ARQUITECTÓNICAS DE UN CASCO HISTÓRICO.

(CMVS) y del algoritmo Patch-based Multi-view Stereo (PMVS2)
(Furukawa and Ponce, 2007 and Furukawa et al., 2010
Una de las características de la fotogrametría de SfM es la
calibración inversa de los parámetros de orientación. La calibración
previa de la cámara no es necesaria ya que la escena en sí se utiliza
como plantilla de calibración. La aparición de estas técnicas nos ha
permitido trabajar con superficies complejas. (Barazzetti et al., 2011) y
obtener nubes de puntos, mallas de triángulos y, finalmente, un modelo
texturizado tridimensional completo (Westoby et al. 2012).

Toma fotográfica
Además de las capacidades del software y la calidad de las imágenes,
ya que el procesado de las fotografías se realiza automáticamente, uno
de los principales factores que afectan la calidad de los resultados de
un procesado fotogramétrico, es la situación de las tomas fotográficas.
Como se señala en la figura 2, los diferentes tipos de toma se pueden
clasificar por la relación entre sus direcciones y las líneas que unen los
centros ópticos (líneas base). La toma convergente (Figura 2 -A),
obtiene resultados más precisos que la configuración perpendicular
(Figura 2 -B). Se requieren menos imágenes para obtener la misma
cobertura estereográfica, y tiene una mayor confiabilidad interna
(Mason, 1995). La disposición oblicua (Figura 2 -C) también es una
opción a considerar.

Figura 2. Clasificación de los tipos de toma. (A) Toma perpendicular. (B) Toma
convergente. (C) Toma oblicua.

65 | Página

<!-- p. 66 -->

SIMÓN PEÑA VILLASENÍN

En este capítulo se utiliza Agisoft PhotoScan para el procesado de
las imágenes. Como se describe en el manual del software, la figura 3
muestra la disposición convergente óptima de las tomas de fotos para
obtener un modelo 3D de un objeto aislado. Para la documentación de
las fachadas, el manual de PhotoScan recomienda una disposición
fotográfica normal, como se muestra en la figura 4. Como se menciona
en el apartado introductorio, las características geométricas del centro
histórico (fachadas complejas, calles estrechas, soportales)
condicionan en gran medida la elección de la metodología de la
fotografía. Por lo tanto, la disposición de la toma debe adaptarse a las
singularidades de cada caso particular.

Figura 3.Disposición de toma fotográfica para un objeto aislado. Figura
obtenida del manual de usuario de Agisoft PhotoScan.

66 | Página

<!-- p. 67 -->

MODELADO 3D DE FACHADAS HISTÓRICAS MEDIANTE FOTOGRAMETRÍA SFM.
DOCUMENTACIÓN GEOMÉTRICA DE DISTINTAS TIPOLOGÍAS
ARQUITECTÓNICAS DE UN CASCO HISTÓRICO.

Figura 4. Disposición de toma fotográfica para fachadas. Figura obtenida del
manual de usuario de Agisoft PhotoScan.

Según lo indicado por los desarrolladores, el software acepta
diferentes tipos de disposición fotográfica, convergiendo en el caso de
una figura aislada y perpendicular en el caso de una fachada. Ambas
disposiciones pueden modificarse, o incluso combinarse, como se
muestra en (Boukerch et al., 2016). Teniendo en cuenta esta
adaptabilidad, este estudio muestra cómo resolver los problemas
geométricos planteados por las fachadas de los centros históricos para
obtener modelos 3D del patrimonio arquitectónico a partir de
fotogrametría SfM. Se utilizan para ello varias opciones de disposición
fotográfica, en casos con limitaciones de espacio extremas, donde las
indicaciones estándar no son aplicables. El objetivo es encontrar una
metodología universal aplicable para el modelado de fachadas dentro
del centro histórico de cualquier ciudad, adaptando las consideraciones
hechas por estudios anteriores y por los desarrolladores de software a
la documentación geométrica de los edificios en centros históricos.
Esta metodología cumplirá las condiciones de alta precisión, alta
velocidad y bajo coste de implementación, proporcionando así una
alternativa viable y técnicamente más avanzada a los métodos
tradicionales.

67 | Página

<!-- p. 68 -->

SIMÓN PEÑA VILLASENÍN

Metodología

Fachadas analizadas
Para cumplir con el objetivo del estudio, el espacio se divide en
unidades de intervención menores, denominados casos individuales,
que se clasifican según sus características geométricas (calles, plazas,
soportales, etc.). Para cada caso individual, se selecciona un ejemplo
de una fachada ubicada en el centro histórico. La figura 5 -C muestra
su ubicación específica. La ciudad de Santiago de Compostela (Figura
5 -B), en España (Figura 5 -A), es elegida para ilustrar este estudio.

Figura 5. Localización de casos individuales en el centro histórico de Santiago
de Compostela (C), Galicia (B), España (A). Fachada significativa (Caso 1),
fachada en una calle estándar (Caso 2), fachada en calle estrecha (Caso 3),
fachada con soportales (Caso 4).

68 | Página

<!-- p. 69 -->

MODELADO 3D DE FACHADAS HISTÓRICAS MEDIANTE FOTOGRAMETRÍA SFM.
DOCUMENTACIÓN GEOMÉTRICA DE DISTINTAS TIPOLOGÍAS
ARQUITECTÓNICAS DE UN CASCO HISTÓRICO.

Figura 6. Fachadas estudiadas. (A) Fachada en calle estrecha. (B) Fachada
significativa. (C) Fachada con soportales. (D) Fachada en calle tipo.

Caso N. 1: Fachada significativa.
Este caso incluye todas las fachadas significativas, tales como
edificios religiosos o institucionales. Como ejemplo, se ha elegido la
fachada del convento de San Martin Pinario en la plaza San Martiño
(Figura 6 -B).

Caso N. 2: Fachada en calle estándar.
Este es el caso individual más común en los centros históricos.
Abarca todas las fachadas ubicadas en calles que tienen anchos más
cortos que las alturas de las fachadas que se deben documentar. La
fachada del Hostal dos Reis Católicos, ubicado en Rúa de San

69 | Página

<!-- p. 70 -->

SIMÓN PEÑA VILLASENÍN

Francisco, es el ejemplo considerado para este grupo. Un caso
excepcional sería una calle con un ancho inferior a un tercio de la altura
de la fachada, que se tratará en el siguiente grupo (Figura 6 -D).

Caso N. 3: Fachada en calle estrecha.
También comunes en los centros históricos, pero que
conllevan una mayor complejidad en la documentación de fachadas,
son las calles estrechas con anchos que limitan la práctica de la
fotogrametría según la metodología estándar (menos de un tercio de la
altura de la fachada). Para ilustrar este caso, se selecciona la calle “Rúa
da Troia”, de 2 a 2,5 m. de ancho con una altura de fachada aproximada
de 12 m. (Figura 6 -A).

Caso N. 4: Fachada con soportales.
Los edificios con soportales en sus fachadas serán tratadas
dentro de este grupo. Los soportales son parte de las fachadas y, debido
a sus morfologías, se presentan como un caso extremo para la
aplicación de técnicas fotogramétricas. Para ilustrar este caso, ha sido
elegida como ejemplo la fachada ubicada en “Praza da Inmaculada”
(Figura 6 -C).

Material
El uso de una cámara réflex de objetivo único (SLR) para el
escaneo fotogramétrico se recomienda especialmente desde un punto
de vista técnico. Aunque una cámara compacta permite obtener
resultados aceptables, el uso de un dispositivo de captura para el cual
se puede ajustar el tiempo de exposición, el formato de archivo, el
enfoque, la apertura y otros parámetros fotográficos, garantiza
resultados más precisos. Esta es la razón por la que, en los casos 1 y 3,
se utiliza una cámara SLR digital Canon EOS 60D con 18 megapíxeles
(5184 × 3456 píxeles) y un tamaño de sensor de 22,3 × 14,9 mm, que
se corresponde a un tamaño de píxel de 4,30 × 4,30 micras, junto con
una lente Canon EF-S 18-135 mm f / 3.5-5.6.

70 | Página

<!-- p. 71 -->

MODELADO 3D DE FACHADAS HISTÓRICAS MEDIANTE FOTOGRAMETRÍA SFM.
DOCUMENTACIÓN GEOMÉTRICA DE DISTINTAS TIPOLOGÍAS
ARQUITECTÓNICAS DE UN CASCO HISTÓRICO.

También se utiliza un trípode fotográfico profesional de aluminio
para la toma en estos casos, no obstante, para los casos 2 y 4, se
prescinde de su utilización, en favor de una toma más ágil. Además, en
estos casos, se utilizó la cámara integrada de un SmartPhone, iPhone
5, con una resolución de 8 megapíxeles (3264 × 2448 píxeles) y un
tamaño de sensor de 4.56 × 3.43 mm, que se corresponde a un tamaño
de píxel de 1.40 × 1.40 micras. Este dispositivo tiene una lente de zafiro
con una distancia focal de 4 mm y una apertura máxima de f / 2.4.
Para escalar y orientar los modelos y verificar su precisión, se
midieron las coordenadas de una serie de puntos de control en las
fachadas utilizando una estación total con medición láser, en este caso
una Pentax R-325EX, con un error de distancia de ± 5 mm + 3 ppm y
6 “de precisión angular.
Para el procesado de imágenes, se utilizó el software PhotoScan
Professional (64 bits) con licencia de Agisoft LLC St. Petersburg
(Rusia). El equipo informático consistía en un procesador Q6600 con
8 GB de RAM, por lo que los tiempos de procesado son relativos a la
velocidad del mismo.

Toma fotográfica
A pesar de las recomendaciones del desarrollador del software,
con el objetivo de demostrar la adaptabilidad de esta técnica, logrando
así una disposición de imágenes que sea más adecuada para la
reconstrucción de la escena, la disposición fotográfica empleada en
cada caso de estudio es variable. Como se justifica en la introducción,
el tipo de sesión fotográfica recomendable es la convergente cuando el
espacio disponible lo permite. Para los casos en los que no es posible
adoptar esta disposición fotográfica, debido a las limitaciones de
espacio (casos 2, 3 y 4), se proponen soluciones alternativas. Las
especificaciones metodológicas para la adquisición de imágenes de
cada caso individual de este estudio se describen a continuación.

71 | Página

<!-- p. 72 -->

SIMÓN PEÑA VILLASENÍN

Fachada significativa - Caso 1
El espacio no suele ser una limitación cuando se trata de una
fachada significativa; Por ello, se utiliza una distribución fotográfica
convergente en este caso. Es decir, se tomó una serie de fotografías
describiendo un arco, con tomas dirigidas hacia un punto ficticio
ubicado detrás del elemento, cubriendo toda la superficie de la fachada,
como se muestra en el gráfico (Figura 7). Para evitar errores en el
procesado, las fotos tomadas deben formar un ángulo de intersección
de menos de 15 grados. Se tomaron veintiocho fotografías, repartidas
en dos pasadas (superior e inferior), con la cámara Canon Eos 60D.

Figura 7. Disposición de toma fotográfica. Fachada significativa (Toma
convergente).

Aunque el espacio no es una limitación en este caso, la altura de la
fachada puede serlo. Es común encontrar salientes en las partes
superiores, sobre el plano de fachada, que generarán partes ocultas en
el modelo (Figura 8). Este problema se puede resolver elevando la toma

72 | Página

<!-- p. 73 -->

MODELADO 3D DE FACHADAS HISTÓRICAS MEDIANTE FOTOGRAMETRÍA SFM.
DOCUMENTACIÓN GEOMÉTRICA DE DISTINTAS TIPOLOGÍAS
ARQUITECTÓNICAS DE UN CASCO HISTÓRICO.

con un dispositivo como una pértiga, aunque en este caso, la técnica
puede ser menos operativa y además este problema ya está presente
tanto en las técnicas tradicionales como en el escaneo láser terrestre.
Esta es la razón por la que se descartó su uso en este estudio,
solventando esta problemática a partir una sesión de fotos, realizada a
una distancia de la fachada (D) igual a la altura de la fachada (H), como
se muestra en la figura 8. Por lo tanto, el ángulo de incidencia vertical
en la fachada será de 45 grados en el caso más desfavorable, en el cual
se puede generar un área oculta de la misma magnitud que el saliente
que la causa.

Figura 8. Zona oculta causada por un saliente. Ángulo máximo de incidencia.

Fachada en calle estándar o tipo - Caso 2
Este caso es el más común en los centros históricos; por lo
tanto, se opta por la opción técnica que permite una mayor flexibilidad
de implementación. Para este caso en particular, se utilizaron pautas
que representan un punto de partida para la documentación métrica de
un área completa, con una geometría longitudinal como la fachada a lo

73 | Página

<!-- p. 74 -->

SIMÓN PEÑA VILLASENÍN

largo de una calle, desarrollando de este modo un flujo de trabajo
rápido, flexible y económico para dicha documentación, como indican
los objetivos de este estudio.
Este caso consiste en el levantamiento de un elemento longitudinal
en el que el espacio está limitado por la fachada opuesta. Para abordar
este problema y crear una situación más favorable, se utiliza una
disposición fotográfica oblicua con un ángulo de 45 grados con
respecto al plano de la fachada, logrando así una superposición del
90%. En este caso, es necesario tomar fotografías en ambas
direcciones, como se muestra en el gráfico (Figura 9). Al final de cada
pasada, se toma además una serie de fotografías de enlace para evitar
cambios repentinos en las perspectivas de las imágenes adyacentes,
cambiando progresivamente el ángulo oblicuo de 45 grados a la
perpendicular y, finalmente, a un ángulo oblicuo de 45 grados en la
dirección opuesta. Esto permitirá que el software conecte las fotos de
ambas pasadas, mientras que en ausencia de estas imágenes de enlace,
el software no es capaz de unir ambos grupos, a no ser que se
identifiquen manualmente puntos comunes entre ellos.

Figura 9. Disposición de toma fotográfica. Fachada en calle tipo.

74 | Página

<!-- p. 75 -->

MODELADO 3D DE FACHADAS HISTÓRICAS MEDIANTE FOTOGRAMETRÍA SFM.
DOCUMENTACIÓN GEOMÉTRICA DE DISTINTAS TIPOLOGÍAS
ARQUITECTÓNICAS DE UN CASCO HISTÓRICO.

Fachada en calle estrecha - Caso 3
El modelado de fachadas en este caso excepcional es difícil
de ejecutar mediante la disposición espacial habitual de la sesión
fotográfica. Inicialmente, se tomaron fotografías oblicuas a
aproximadamente 30 grados con respecto al plano de la fachada. Como
en el ejemplo anterior, se obtuvieron dos pasadas junto con fotos de
enlace, como se muestra en la figura 10-A.
Para la parte superior del edificio, se tomaron tantas fotografías
como fue necesario desde cada punto de vista, para cubrir la altura de
la fachada, avanzando aproximadamente un tercio del área cubierta en
la imagen anterior para asegurar la superposición vertical (solape
vertical del 66%). De manera similar, para garantizar una
superposición horizontal suficiente entre las imágenes adyacentes, el
progreso entre los puntos de muestreo se limitó a no más de un tercio
de la distancia del área documentada horizontalmente en las fotografías
inferiores. Las fotografías inferiores se tomaron como referencia
porque son las más limitantes en términos de ángulo de visión.

75 | Página

<!-- p. 76 -->

SIMÓN PEÑA VILLASENÍN

Figura 10. Disposición fotográfica. Caso 3, fachada en calle estrecha. (A) Tomas
oblicuas. (B) Tomas longitudinales.

Aplicando esta disposición de toma, se obtuvieron fotografías de
diferentes ángulos de visión de todas las áreas de la fachada, utilizando
el limitado espacio disponible y proporcionando la mejor calidad visual
posible. Incluso las partes superiores, que son las más alejadas,
obtienen una mayor superposición entre las fotografías,
homogeneizando el resultado final.
Sin embargo, aunque proporcionó una buena calidad visual en la
obtención de textura, esta distribución de tomas de fotos causó errores
geométricos en ciertas áreas. Debido a que la técnica de SfM se basa en
la correlación de imágenes, un error en las orientaciones de una imagen
provoca errores en las orientaciones de las imágenes posteriores. Para
resolver este problema, se obtuvieron dos nuevas pasadas,

76 | Página

<!-- p. 77 -->

MODELADO 3D DE FACHADAS HISTÓRICAS MEDIANTE FOTOGRAMETRÍA SFM.
DOCUMENTACIÓN GEOMÉTRICA DE DISTINTAS TIPOLOGÍAS
ARQUITECTÓNICAS DE UN CASCO HISTÓRICO.

correspondientes a cada una de las direcciones de avance, colocando la
cámara en el medio de la calle y ajustándola longitudinalmente, como
se muestra en la imagen (Figura 10 -B). En las imágenes obtenidas, se
registraron las fachadas de ambos lados. Por lo tanto, el espacio
limitado, que originalmente era un problema, se convirtió en una
ventaja, ayudando al software a determinar la geometría correcta de la
escena. Esto se debe a que la superposición de estas imágenes fue muy
alta, ya que están enfocadas en la parte inferior de la calle, agregando
nuevos ángulos de visión que proporcionaron solidez al cálculo.
Finalmente, la cantidad de imágenes necesarias para cubrir la
sección apenas aumentó porque se necesitaron menos puntos de toma
para cubrir la misma área. Además, estas imágenes se utilizaron en la
documentación de la fachada y su fachada opuesta.

Fachada con soportales - Caso 4
Para la documentación 3D de un conjunto de fachadas con
soportales, se identificaron dos áreas de trabajo diferentes: la fachada
externa la cual se trata en primer lugar, y su contraparte interior, tratada
en segundo lugar. Para modelar la fachada externa, recurrimos a la
misma técnica que en el caso 1 “fachada significativa”, por lo que se
aplica una distribución fotográfica convergente (Figura 11 -A).
La documentación de la parte interior del soportal está limitada en
términos de espacio e iluminación, por lo que se dividió en porciones
longitudinales de 20 m, que se documentan individualmente. Se
probaron diferentes ubicaciones de cámaras. Primero, se trató de
generar el modelo a partir de una toma longitudinal a través del
soportal. Como resultado, se obtuvo la orientación correcta en la
primera dirección de la toma, pero el software no orientó las imágenes
en la otra dirección. En segundo lugar, se intentó una toma oblicua en
esta área. Sin embargo, el contraste de la luz dentro del soportal, entre
las zonas internas y externas creó dificultades para tomar fotografías,
y no fue posible generar la reconstrucción completa de la escena.
Finalmente, se diseñó una distribución de imágenes que unen ambas
zonas (interna y externa). Se obtuvieron dos pasadas a lo largo del eje

77 | Página

<!-- p. 78 -->

SIMÓN PEÑA VILLASENÍN

longitudinal del soportal, capturando sus dos fachadas interiores en
cada fotografía. Para unir las dos pasadas internas y externas, se
tomaron dos conjuntos de fotografías que rodean los pilares del arco en
los extremos del soportal como fotos de enlace (Figura 11 -B).

Figura 11. Disposición fotográfica. Caso 4, fachada con soportales. (A) Fachada
externa. (B) Fachada interior.

Esta ubicación de la cámara obtuvo los mejores resultados para
este caso en términos de calidad geométrica y visual. La alta estabilidad
geométrica en la sesión de fotos se descartó en favor de un mayor

78 | Página

<!-- p. 79 -->

MODELADO 3D DE FACHADAS HISTÓRICAS MEDIANTE FOTOGRAMETRÍA SFM.
DOCUMENTACIÓN GEOMÉTRICA DE DISTINTAS TIPOLOGÍAS
ARQUITECTÓNICAS DE UN CASCO HISTÓRICO.

número de fotografías tomadas con mayor agilidad, un modo de trabajo
que se adapta mejor a este caso complejo.

Procesado fotogramétrico
Una vez que se realiza la toma fotográfica, el flujo de trabajo
continúa con el software Agisoft PhotoScan. En primer lugar, se cargan
las fotos y se inicia el proceso inicial, “orientar cámaras”. Para orientar,
escalar y verificar la precisión del modelo, se midieron una serie de
puntos de control con la estación total en las fachadas originales. Cinco
de ellos se utilizaron para escalar y orientar el modelo. Una vez que los
cinco puntos de control se marcaron sobre las imágenes, se realizó la
transformación y este se ajustó y orientó de acuerdo con el sistema de
referencia de la estación total.
La nube de puntos y la malla 3D fueron generadas por los procesos
“Crear nube densa” y “Crear malla”. Finalmente, el modelo de textura
fotorrealista se calculó mediante el proceso de “Generar textura”
(Figura 12). Estos últimos tres procesos se realizan automáticamente,
con la opción de elegir la “calidad” de procesado tanto de la nube como
de la malla.

79 | Página

<!-- p. 80 -->

SIMÓN PEÑA VILLASENÍN

Figura 12. Modelo 3D con textura fotorealista.

Al final del proceso, los restantes puntos medidos, se marcaron
directamente en la malla, proporcionando las coordenadas del modelo
que se compararon, obteniendo de ese modo las desviaciones métricas
reales del producto final.

Obtención y digitalización de ortofotos
Para generar las ortofotos, el software PhotoScan permite la
definición de los ejes del X e Y, que forman el plano sobre el que se
obtiene la vista ortogonal. Posteriormente, en el software CAD, estas
ortofotos se escalaron utilizando los puntos de control y se digitalizaron
los rasgos característicos de la fachada.
Otra opción es la posibilidad de digitalizar vectorialmente los
rasgos característicos utilizando el software fotogramétrico. PhotoScan
permite la creación de formas en las ortofotos, obteniendo las entidades
vectoriales de la escena directamente. Estas entidades vectoriales
pueden exportarse en distintos formatos para su importación en
software CAD o BIM.

80 | Página

<!-- p. 81 -->

MODELADO 3D DE FACHADAS HISTÓRICAS MEDIANTE FOTOGRAMETRÍA SFM.
DOCUMENTACIÓN GEOMÉTRICA DE DISTINTAS TIPOLOGÍAS
ARQUITECTÓNICAS DE UN CASCO HISTÓRICO.

Resultados y discusión

Toma fotográfica
Cuando el espacio no es una limitación como en el primer caso, la
disposición convergente es la mejor opción (Figura 7). En calles
estrechas y estándar, las distribuciones de toma oblicua, con diferentes
ángulos (dependiendo de las limitaciones de espacio) proporcionan
mejores resultados. Las disposiciones perpendiculares y convergentes
se combinan y aplican, en ocasiones solo para crear imágenes de enlace
(Figura 9 y 10). En el caso 4, las fotos de enlace convergen alrededor
del pilar del arco (Figura 11). Además, para calles estrechas y
soportales interiores es importante capturar ambas fachadas en cada
fotografía. Esto es posible mediante la toma de fotografías a lo largo
del eje longitudinal de la calle o soportal. Esta metodología ha
permitido obtener modelos 3D de calidad, transformando el problema
de las limitaciones de espacio, en una ventaja. La información de
fachada opuesta y la mayor superposición de estas fotos, aportan
robustez geométrica a la escena.

81 | Página

<!-- p. 82 -->

SIMÓN PEÑA VILLASENÍN

Modelos 3D
En la tabla 1 se muestra una instantánea de cada uno de los
modelos obtenidos (Figura 13) y los resultados del procesado.

Tabla 1: Resultados del procesado

Densidad Caso Puntos Triángulos (puntos/m2)

Caso 1
Fachada 1.841.811 3.104.417 2.512
significativa

Caso 2
Fachada en 313605 658.342 505
calle tipo

Caso 3
Fachada en 557.105 1.110.691 2.790
calle estrecha

Caso 4
Fachada con 1.001.323 2.555.187 5.610
soportales

82 | Página

<!-- p. 83 -->

MODELADO 3D DE FACHADAS HISTÓRICAS MEDIANTE FOTOGRAMETRÍA SFM.
DOCUMENTACIÓN GEOMÉTRICA DE DISTINTAS TIPOLOGÍAS
ARQUITECTÓNICAS DE UN CASCO HISTÓRICO.

Figura 13. Capturas de los modelos 3D. (A) Fachada significativa, Caso 1 (B)
Fachada en calle tipo Caso 2. (C) Fachada en calle estrecha Caso 3. (D) Fachada
con soportales, Caso 4.

83 | Página

<!-- p. 84 -->

SIMÓN PEÑA VILLASENÍN

Precisión
La precisión se evaluó mediante la obtención de coordenadas
directamente sobre la malla texturizada, proporcionando así valores
reales del error del modelo 3D. La tabla 2 muestra las precisiones
obtenidas, el dispositivo fotográfico utilizado y los tiempos empleados
en el trabajo de campo y el procesado en cada caso.

TABLA 2: Trabajo de campo y resultados del procesado

Trabajo Nº Error Error Caso Cámara de Procesado Imágenes medio relativo campo
Caso 1 Canon 60D 28 15 min. 7h 0.039 m. 1/1010

Caso 2 Iphone 5 175 20 min. 10h 0.049 m. 1/1030

Caso 3 Canon 350D 113 50 min. 18h 0.026 m. 1/770

Caso 4 Canon 60D + 128 30 min. 16h 0.021 m. 1/1040 Iphone 5

Para verificar la precisión de los modelos, el error promedio se
obtuvo como la media aritmética de los valores absolutos de las
diferencias entre los puntos de coordenadas tomados con la estación
total y los mismos puntos obtenidos de los modelos digitales después
de escalarse y orientarse en el mismo sistema de referencia utilizado
por el instrumental topográfico, en este caso un sistema de referencia
local. El error relativo es el resultado de dividir el error medio por la
diagonal más larga del elemento. En las figuras 14 a 17, se puede ver
la distribución de puntos de control en las fachadas, mostrando en color
gris los puntos utilizados para la georreferenciación del modelo.

84 | Página

<!-- p. 85 -->

MODELADO 3D DE FACHADAS HISTÓRICAS MEDIANTE FOTOGRAMETRÍA SFM.
DOCUMENTACIÓN GEOMÉTRICA DE DISTINTAS TIPOLOGÍAS
ARQUITECTÓNICAS DE UN CASCO HISTÓRICO.

Figura 14. Distribución de los puntos de control (GCPs) en el caso 1.

Figura 15. Distribución de los puntos de control (GCPs) en el caso 2.

1

85 | Página

<!-- p. 86 -->

SIMÓN PEÑA VILLASENÍN

Figura 16. Distribución de los puntos de control (GCPs) en el caso 3.

Figura 17. Distribución de los puntos de control (GCPs) en el caso 4.

A continuación se muestran los alzados (Fig. 18) y la
digitalización vectorial de los mismos (Fig. 19 y Fig. 20 -A) o ambos
productos superpuestos (Fig. 20 -B). Los resultados obtenidos
muestran que la pequeña cantidad de espacio frente a la fachada es una
limitación que se puede superar. Una toma convergente, a pesar de no

86 | Página

<!-- p. 87 -->

MODELADO 3D DE FACHADAS HISTÓRICAS MEDIANTE FOTOGRAMETRÍA SFM.
DOCUMENTACIÓN GEOMÉTRICA DE DISTINTAS TIPOLOGÍAS
ARQUITECTÓNICAS DE UN CASCO HISTÓRICO.

ser la disposición de la cámara recomendada por los desarrolladores de
software, garantiza una buena precisión con un número de fotos menor
(Caso 1). Cuando el espacio es limitado, será necesario aumentar el
número de imágenes y adaptar su disposición espacial.

Figura 18. Ortofoto en alzado. Fachada en calle tipo, Caso 2.

Figura 19. Digitalización vectorial, fachada en calle estrecha, Caso 3.

87 | Página

<!-- p. 88 -->

SIMÓN PEÑA VILLASENÍN

Figura 20. Fachada con soportales, caso 4. (A) Digitalización vectorial. (B)
Digitalización vectorial sobre ortofoto.

Dentro de una ciudad histórica y para casos no excepcionales, se
obtuvieron buenos resultados utilizando una distribución oblicua (Caso
2). Cabe señalar aquí que la necesidad de una colección de imágenes
en cada dirección de avance nos obligó a tomar fotografías de enlace
entre las dos pasadas. Esto se debe a que el software no puede vincular
las áreas entre las imágenes con ángulos de incidencia muy diferentes.
Cuando la ubicación es un caso excepcional (casos 3 y 4), las
características geométricas del elemento determinan la disposición de
tomas a emplear. Este estudio ha resuelto dos ejemplos extremos que
pueden ser útiles para resolver casos similares. En el caso 3 (fachada
en calle estrecha), la cercanía de la fachada opuesta, que a priori era un
problema, se convirtió en una ventaja al usar imágenes en las que se

88 | Página

<!-- p. 89 -->

MODELADO 3D DE FACHADAS HISTÓRICAS MEDIANTE FOTOGRAMETRÍA SFM.
DOCUMENTACIÓN GEOMÉTRICA DE DISTINTAS TIPOLOGÍAS
ARQUITECTÓNICAS DE UN CASCO HISTÓRICO.

registran ambas fachadas, logrando así un modelado automático y un
buen resultado. En el caso 4 (fachada con soportales), se deben
documentar las dos fachadas interiores. La metodología aquí es similar
a la del caso anterior, excepto que el enlace de ambas pasadas se realiza
en el área que rodea al último pilar, y las dos pasadas interiores se unen
con una pasada externa. Esto aporta solidez geométrica a la escena
mejorando los resultados.

Conclusiones
A la vista de los resultados del estudio, después de haber resuelto
satisfactoriamente ejemplos específicos en los que los procedimientos
habituales no son aplicables, se puede afirmar que el modelado 3D de
fachadas mediante fotogrametría SfM de corto alcance es una técnica
adaptable, confiable y de alto rendimiento, que ha obtenido precisiones
cercanas a las obtenidas por la misma técnica en condiciones óptimas.
Se han resuelto cuatro casos, que abarcan las tipologías
edificatorias más comunes en una ciudad histórica. Este enfoque es
posible porque actualmente, las capacidades del software nos permiten
utilizar disposiciones de toma fotográfica más flexibles, siempre que
cumplamos con los requisitos de superposición entre las imágenes y
que las variaciones de ángulo en las tomas de fotos correlativas sean lo
más pequeñas posible. Siempre que se respete este criterio en el diseño
de la disposición de las tomas, puede resolverse mediante
fotogrametría SfM cualquier otra ubicación en un centro histórico.
En los centros históricos, el uso de dispositivos accesibles, como
SmartPhones, ofrece ventajas como la georreferenciación automática
de las imágenes y la posibilidad de obtener modelos 3D de casi
cualquier elemento arquitectónico sin una planificación previa de los
trabajos. Es por esto que este dispositivo se utilizó en ciertos casos,
logrando resultados cercanos a los obtenidos con cámaras SLR.
Además, el uso de este dispositivo revela que el número de fotografías
utilizadas es más decisivo para la precisión del modelo que la calidad
geométrica de las imágenes. En este sentido, la toma con un trípode,
especialmente en casos excepcionales como en centros históricos, que

89 | Página

<!-- p. 90 -->

SIMÓN PEÑA VILLASENÍN

requieren un mayor número de imágenes y donde el espacio de trabajo
es limitado, se vuelve complejo y tedioso, perdiendo efectividad en la
técnica.
Una conclusión importante de este estudio es la necesidad de
obtener fotografías de enlace para unirse a los diferentes grupos de
fotografías, aunque no es necesario para obtener la alta resolución y la
geometría precisa de un modelo, el uso de fotografías vinculadas es
necesario para conectar fotografías de pasadas con diferentes
direcciones de toma. Esto se debe a que la técnica SfM funciona en
fotos correlacionadas para calcular las posiciones 3D de los puntos de
muestreo. Un cambio brusco de perspectiva entre dos imágenes
adyacentes puede causar errores geométricos en el modelo o una
situación en la que el software no podrá calcular la geometría completa
de la escena.
Después de analizar los resultados, se puede concluir que es de
mayor relevancia para obtener modelos 3D de calidad a partir de
fotogrametría SfM, el número de imágenes y el solape entre ellas, que
la calidad y la estabilidad con la que se tomen las mismas. Es por esto
que tomar fotos con una gran superposición, de una manera más ágil y
sin el uso de un trípode, proporciona modelos con igual o mejor
precisión y acelera el proceso, siendo la mejor metodología para
resolver las características geométricas complejas habituales en centros
históricos, donde la disposición de tomas estándar no es operativa.
Como línea de investigación futura, queda testear la posibilidad de
digitalizar dentro del software de fotogrametría y exportar los
resultados directamente al software BIM, un flujo de trabajo que puede
generar muchas posibilidades para la documentación y el estudio de
estos elementos del patrimonio.

90 | Página

<!-- p. 91 -->

MODELADO 3D DE FACHADAS HISTÓRICAS MEDIANTE FOTOGRAMETRÍA SFM.
DOCUMENTACIÓN GEOMÉTRICA DE DISTINTAS TIPOLOGÍAS
ARQUITECTÓNICAS DE UN CASCO HISTÓRICO.

CAPITULO 1. RESUMEN GRÁFICO

TOMA FOTOGRÁFICA

91 | Página

<!-- p. 92 -->

SIMÓN PEÑA VILLASENÍN

MODELO 3D

ORTOMOSAICO

92 | Página

<!-- p. 93 -->

MODELADO 3D DE FACHADAS HISTÓRICAS MEDIANTE FOTOGRAMETRÍA SFM.
DOCUMENTACIÓN GEOMÉTRICA DE DISTINTAS TIPOLOGÍAS
ARQUITECTÓNICAS DE UN CASCO HISTÓRICO.

VECTORIZACIÓN

93 | Página

<!-- p. 94 -->

SIMÓN PEÑA VILLASENÍN

ORTOMOSAICO Y VECTORIZACIÓN

im

94 | Pagina

<!-- p. 95 -->

CAPITULO II

\6. CAPITULO II

COMPARACIÓN DE SOFTWARE DESKTOP
PROFESIONAL Y SOFTWARE GRATUITO
CLOUD COMPUTING EN EL MODELADO 3D
DE EDIFICIOS HISTÓRICOS: MONASTERIO
DE SAN MARTÍN PINARIO

RESUMEN
En las últimas décadas, las técnicas de adquisición de datos en
3D han reemplazado a las técnicas de medición tradicionales en el
campo de la arquitectura, la ingeniería y la construcción (AEC). Este
estudio emplea fotogrametría SfM para el levantamiento de una
fachada de un edificio histórico. El procesado con software
fotogramétrico profesional (Agisoft PhotoScan y Pix4D) se compara
con el procesado con software fotogramétrico de bajo coste (Autodesk
Remake). El objetivo es analizar la precisión de estos programas de
software y comparar las posibilidades y la facilidad de uso que ofrecen
en el flujo de trabajo completo. En este caso, el modelado 3D se realizó
en la fachada de San Martín Pinario, que es el segundo monasterio más
grande de España. Este monasterio se encuentra en la ciudad histórica,
de Santiago de Compostela. Se analizan los resultados de procesado, la
calidad y precisión geométrica de los mismos, los resultados visuales
y la facilidad de uso y posibilidades del software, mostrando que el
software de computación “en la nube” ofrece modelos 3D con calidad
y precisión visual similares a los obtenidos con el software de escritorio

95 | Página

<!-- p. 96 -->

SIMÓN PEÑA VILLASENÍN

sin requerir equipos de alto rendimiento y con un flujo de trabajo muy
simple. El ahorro de costes y la facilidad de uso hacen que la
computación fotogramétrica “en la nube” sea una excelente
herramienta de medición para los profesionales del patrimonio no
especialistas en fotogrametría.

96 | Página

<!-- p. 97 -->

COMPARACIÓN DE SOFTWARE DESKTOP PROFESIONAL Y SOFTWARE
GRATUITO CLOUD COMPUTING EN EL MODELADO 3D DE EDIFICIOS
HISTÓRICOS: MONASTERIO DE SAN MARTÍN PINARIO

Introducción
Los avances tecnológicos han conducido a cambios continuos en los
métodos de trabajo para los profesionales de la arquitectura
patrimonial. Se observa un claro ejemplo de tales cambios en las
herramientas de adquisición de datos métricos, con la aparición de
tecnologías de escáner láser y fotogrametría SfM que representan
alternativas precisas a los métodos de medición tradicionales. Algunas
comparaciones de ambas técnicas en aplicaciones arquitectónicas se
muestran en (Boehler & Marbs, 2004; Grussenmeyer et al., 2008; Teza
et al., 2016). Los profesionales de la arquitectura, la ingeniería y la
construcción (AEC), necesitan planes de trabajo y planos detallados
para reparaciones, remodelación o mantenimiento de edificios
patrimoniales. La inspección de fachadas con técnicas tradicionales es
tediosa, difícil y ocasionalmente imprecisa. Estas técnicas implican la
realización de mediciones individuales utilizando una herramienta de
medición, como una cinta métrica o un distanciómetro láser. Otras
técnicas más avanzadas, como la medición con estación total, implican
medios más costosos y requieren conocimientos de manejo. Además,
hay situaciones en las que las técnicas tradicionales no son operativas,
como por ejemplo en fachadas con zonas inaccesibles o incluso en
edificios destruidos o dañados cuando la fotogrametría es el único
método aplicable. En estos casos, la fotogrametría permite a los
arquitectos realizar dibujos para reconstruir con precisión un edificio
histórico como se muestra en (Yilmaz et al., 2007) con un edificio
destruido por un incendio, en el que no existe la posibilidad de realizar
mediciones de campo tradicionales o con escáner láser.
Las técnicas, como los escáneres láser y la fotogrametría Structure
from Motion (SfM), están revolucionando el modo de obtener
documentaciones geométricas de fachadas de edificios (Dai & Lu,
2010; Ordóñez et al., 2010). Los avances en los escáneres láser han
aumentado la demanda de modelos 3D que permiten la documentación
y el análisis de formas y dimensiones a altas resoluciones. Estos
modelos representan tanto la geometría de los edificios como su
textura, por lo que pueden utilizarse en estudios ambientales como se
demuestra en (Bui et al., 2009) en el cual se mide la erosión de una

97 | Página

<!-- p. 98 -->

SIMÓN PEÑA VILLASENÍN

chimenea. Paralelamente a la expansión de los escáneres láser y
provocada por la creciente demanda de modelos 3D, la fotogrametría
digital, particularmente la fotogrametría SfM, ha avanzado
considerablemente y ha sido utilizada cada vez más por varios tipos de
especialistas, como ingenieros civiles. (Bhatla et al., 2012; Kwak et al.,
2013; Stavroulaki et al., 2016), arquitectos (Sužiedelytė-Visockienė et
al., 2015; Yang et al., 2016), arqueólogos e historiadores (Bea &
Angás, 2017; Gonizzi Barsanti et al., 2013; Johnson & Solis, 2016;
Martínez-Rodríguez et al., 2015; Juan Ortiz et al., 2013) o especialistas
en medioambiente (Butler et al., 2002; Kaufmann & Ladstädter, 2007).
La fotogrametría SfM ha ganado interés dado que la inversión requerida
para equipos fotográficos y de software es sustancialmente menor que
la requerida para un escáner 3D. Además, un conjunto de datos se
puede integrar en el software BIM como se muestra en (Tzedaki &
Kamara, 2013). TLS y fotogrametría están reemplazando las
metodologías tradicionales como se muestra en (Almagro, 2002),
pudiéndose incluso combinar ambas técnicas (Al-kheder et al., 2009;
Yastikli, 2007).

Fotogrametría SfM
La fotogrametría digital ha evolucionado considerablemente en las
últimas décadas. El desarrollo de la triangulación y los algoritmos de
extracción de datos 3D basados en imágenes ha mejorado
sustancialmente la calidad de los modelos 3D, como se demuestra en
(Heipke et al., 2016). De manera similar, las mejoras en la calidad y el
coste de las cámaras réflex compactas y de lente única (SLR) y los
métodos de calibración que permiten utilizar cámaras no métricas (Jh
Chandler et al., 2005), han contribuido a una mayor expansión de estas
técnicas. A diferencia de la fotogrametría convencional y las primeras
versiones del software de fotogrametría de corto alcance, que permiten
la manipulación exclusiva de puntos seleccionados discretamente y,
por lo tanto, de superficies simples, el software actual de fotogrametría
SfM permite el uso de un proceso automatizado con superficies
complejas. Las nubes de puntos, las mallas triangulares y los modelos
texturizados tridimensionales completos se obtienen de las fotos como
se indica en (Remondino & El-Hakim, 2006; Westoby et al., 2012).

98 | Página

<!-- p. 99 -->

COMPARACIÓN DE SOFTWARE DESKTOP PROFESIONAL Y SOFTWARE
GRATUITO CLOUD COMPUTING EN EL MODELADO 3D DE EDIFICIOS
HISTÓRICOS: MONASTERIO DE SAN MARTÍN PINARIO

Cabe destacar cuatro factores en la evolución de esta técnica. El primer
factor es la automatización de la coincidencia de características de
imagen (puntos homólogos). El primer paso del procesado inicial en la
fotogrametría SfM, es la identificación de características en imágenes
individuales que se pueden usar para la correspondencia entre ellas. La
fotogrametría convencional requiere la identificación de una serie de
puntos en las fotos para calcular los parámetros de orientación (Puntos
homólogos). Los algoritmos automáticos de coincidencia de
características, como el algoritmo Scale-Invariant Feature Transform
(SIFT) descrito en (Chandran et al., 1997; Lowe, 2004), han permitido
que la identificación de los puntos homólogos en los entre fotografías
sea automática, lo que ha reducido significativamente el tiempo
requerido para realizar esta tarea. El estado del arte en la coincidencia
de imágenes de alta densidad se describe ampliamente en (Remondino
et al., 2014). En segundo lugar, en la automatización del proceso de
calibración mediante el cálculo inverso de los parámetros de
orientación interna como se describe en (Clarke & Fryer, 1998; Fraser,
2013), el software reconstruye la escena de acuerdo con datos EXIF de
cada imagen, junto con los coincidencias entre imágenes obtenidas en
el primer paso. Luego, estos parámetros se ajustan de forma iterativa.
El algoritmo System Bundler, que se describe en (Snavely et al., 2008;
Triggs et al., 2000), se utiliza para estimar la posición de la cámara y
extraer una nube de puntos “dispersa”. Por lo tanto, las orientaciones
internas y relativas y la geometría de la escena se reconstruyen
simultáneamente en un solo proceso, sin la necesidad de una
calibración previa de la cámara. En tercer lugar, se puede obtener una
nube de puntos de mayor densidad gracias al algoritmo Clustering view
for Multiview Stereo (CMVS) y el algoritmo Patch-based Multiview
Stereo (PMVS2) (Furukawa et al., 2010; Furukawa & Ponce, 2010).
Ambos algoritmos permiten obtener modelos 3D de geometrías
complejas de forma automatizada. En cuarto lugar, los avances
continuos en las capacidades de computación, en especial con la
aparición del software de fotogrametría de computación “en la nube”.

99 | Página

<!-- p. 100 -->

SIMÓN PEÑA VILLASENÍN

Software de fotogrametría SfM
Los orígenes del software de fotogrametría SfM se encuentran en
la comunidad de visión artificial (Spetsakis & Aloimonos, 1991; R
Szeliski & Sing Bing, 1993) y el desarrollo de los algoritmos
automáticos de coincidencia de características descritos en (Harris &
Stephens, 1988; Otto & Chau, 1989). Una gama de motores de
procesado “en la nube” ha generalizado de la fotogrametría de corto
alcance. Recientemente, la computación “en la nube” ha cambiado la
comprensión del software en general y del software fotogramétrico en
particular. Los profesionales tienen a su disposición opciones de
software de escritorio y de computación “en la nube”. Como ejemplos
de software de escritorio, encontramos Apero Micmac (IGN, Francia)
(Deseilligny & Clery, 2011), Eos Photomodeler (Eos System Inc.,
Canada) (Barazzetti et al., 2011), Agisoft PhotoScan (Agisoft LLC.,
Russia) (De Reu et al., 2013b) y Pix4D Mapper (EPFL, Switzerland)
(Strecha et al., 2012). Sin embargo, la tendencia en software se está
moviendo hacia el uso de recursos de computación “en la nube”. Estos
servicios de procesado de imágenes se realizan en un servidor externo.
Un ejemplo de este software es Photosynth (Microsoft Corporation,
EE. UU.) o ARC3D (Ku Leuven, Bélgica) (Tingdahl & Van Gool,
2011). Otro ejemplo de gran popularidad es 123DCatch (Autodesk Inc.,
EE. UU.) (Jim; Chandler & Fryer, 2013); sin embargo, este servicio,
no ha evolucionado desde su lanzamiento inicial en 2009, y solo ha
estado disponible hasta marzo de 2017. Autodesk Company ha
implantado en su lugar los servicios de computación SfM “en la nube”
con Recap Photo (2012) (Fritsch et al., 2013), Autodesk Memento
(Johnson & Solis, 2016), y Autodesk Remake (Nikolov & Madsen,
2016). Desde 2017 Recap Photo es la única opción disponible. Incluso
los dispositivos móviles son capaces de tomar fotos y realizar un
procesado fotogramétrico a través de la nube (123D Catch) o con
aplicaciones locales como TRNIO o SCANN3D.

100 | Página

<!-- p. 101 -->

COMPARACIÓN DE SOFTWARE DESKTOP PROFESIONAL Y SOFTWARE
GRATUITO CLOUD COMPUTING EN EL MODELADO 3D DE EDIFICIOS
HISTÓRICOS: MONASTERIO DE SAN MARTÍN PINARIO

Modelado de edificios con fotogrametría SfM
El uso de la fotogrametría SfM ofrece nuevas posibilidades en el
estudio de la arquitectura como se demuestra en (Murtiyoso et al.,
2017), en el que emplea drones para el modelado 3D de edificios, y una
gran adaptabilidad a zonas complejas como se señala en (PeñaVillasenín et al., 2017), donde se analiza el proceso de modelado 3D
de diferentes tipos de edificios. Un ejemplo de software de
fotogrametría de computación “en la nube” aplicado en el patrimonio
arquitectónico se presenta en (Santagati & Inzerillo, 2013). Sin
embargo, en estos estudios, los resultados y el flujo de trabajo de la
fotogrametría SfM se comparan con otros métodos de medición, como
los métodos tradicionales en (Peña-Villasenín et al., 2017) o láser
escáner en (Murtiyoso et al., 2017; Santagati & Inzerillo, 2013; Teza
et al., 2016). En (Murtiyoso et al., 2017), también se analizan algunas
opciones de escritorio; sin embargo, la confiabilidad de la computación
“en la nube” en comparación con el software de escritorio sigue sin
estar clara. Los algoritmos son similares en el software de computación
de escritorio y en la nube, no obstante las actualizaciones constantes de
los mismos, y la pérdida de control por parte del técnico del procesado
fotogramétrico en la computación “en la nube” hace que se necesiten
estudios periódicos para evaluar la calidad de los modelos resultantes.
Por este motivo, en este estudio se analizan los resultados de la
documentación de fachadas obtenidas con el software de computación
“en la nube” de bajo coste Autodesk Remake, con el software
profesional de escritorio como Pix4D Mapper y Agisoft PhotoScan.
Este estudio también compara los resultados obtenidos con las dos
opciones de software de escritorio mencionadas, los cuales son
utilizados ampliamente para trabajos fotogramétricos profesionales. En
esta comparación, se analizan los rendimientos del procesado en
tiempos y costes, la calidad visual y la precisión geométrica de los
modelos 3D resultantes y la facilidad de uso y posibilidades del
software estudiado.

101 | Página

<!-- p. 102 -->

SIMÓN PEÑA VILLASENÍN

Metodología

Caso de estudio: fachada posterior del Monasterio
de San Martín Pinario.
La comparación se realiza considerando una colección de
imágenes de la fachada del monasterio de San Martín Pinario, que se
construyó entre los siglos XVI y XVIII. El monasterio de San Martín
Pinario y la catedral de Santiago de Compostela (Figura 1-A)
representan el conjunto barroco gallego más relevante. Este monasterio
es el segundo más grande de España (Figura 1-B) después de El
Escorial (Madrid). De su importancia se destaca su relevancia
arquitectónica, religiosa y artística (Croci et al., 1997; Vicente López,
2016). Sus características y variedad de superficies hacen que sea una
opción idónea para este estudio. El monasterio incluye varias zonas con
distintas superficies, incluyendo zonas lisas, ásperas, planas y muy
texturizadas con algunas ventanas y puertas e incluye algunas zonas de
ornamentos altamente detallados, siendo un caso representativo de una
fachada significativa de un centro histórico.
El monasterio de San Martín Pinario se encuentra cerca de la
catedral de Santiago de Compostela. La Figura 1-C muestra la posición
prominente del edificio en relación con su entorno, lo que demuestra
su importancia cultural. Su fachada este (Figura 1-D) está bien situada
para facilitar el acceso fotográfico debido a su ubicación en una plaza
amplia.

102 | Página

<!-- p. 103 -->

COMPARACIÓN DE SOFTWARE DESKTOP PROFESIONAL Y SOFTWARE
GRATUITO CLOUD COMPUTING EN EL MODELADO 3D DE EDIFICIOS
HISTÓRICOS: MONASTERIO DE SAN MARTÍN PINARIO

Figura 1. (A) Galicia. (B) España. (C) Callejero Santiago de Compostela. (D)
Fachada del Monasterio de San Martín Pinario.

Equipamento
Se utilizó una cámara digital réflex, Canon EOS 60D, con 18
megapíxeles (5,184 × 3,456 píxeles) y un tamaño de sensor de 22.3 ×
14.9 mm, que corresponde a un tamaño de píxel de 4.30 × 4.30 µm. La
lente empleada se corresponde con una Canon EF-S 18-135 mm f / 3.55.6. Para la toma se utilizó un trípode fotográfico profesional de
aluminio.

103 | Página

<!-- p. 104 -->

SIMÓN PEÑA VILLASENÍN

Para escalar, orientar y verificar la precisión de los modelos 3D,
se midieron las coordenadas de varios puntos distribuidos en la fachada
utilizando una estación total con medición laser Pentax R-325EX con
un error de distancia de ± 5 mm + 3 ppm y una precisión de ángulo de
6”. Los primeros 6 puntos medidos se dispusieron en las esquinas y en
el área central de la fachada, y estos puntos se utilizaron como puntos
de control (GCP) para escalar y orientar el modelo 3D. Otros 17 puntos
en la fachada fueron medidos y utilizados como puntos de verificación
o Check Points (CP). Los CP medidos se compararon con las
coordenadas identificadas en la malla 3D para determinar la precisión
geométrica del modelo.
Las versiones que son testeadas en este estudio son la 1.2.0 de
Agisoft PhotoScan, la versión 2.0.104 de Pix4D Mapper y la versión
17.23.1.69 de Remake. El equipo informático utilizado consta de un
procesador i5 4460 con 32 GB de memoria RAM. El precio actual de
una licencia permanente para PhotoScan es de 3.500 USD. La licencia
permanente de Pix4D es de aproximadamente 6,900 USD. Autodesk
Remake no ofrece una licencia permanente, pero ofrece una suscripción
anual de 300 USD. Remake y Pix4D permiten licencias mensuales por
30 y 280 USD respectivamente.

Toma fotográfica
Para cumplir con el objetivo de este estudio, se usó una sesión de
fotos común de tal manera que los tres programas de software usaron
la misma información gráfica. Se obtuvieron un total de 28 fotos a una
distancia similar a la altura de la fachada, con velocidades de
obturación relativamente largas (1/25 a 1/40), con una sensibilidad ISO
100, con una apertura de F / 8 y utilizando trípode y un disparador. De
esta manera, se minimizó la vibración de la cámara y los parámetros de
la foto fueron apropiados para obtener imágenes de alta estabilidad
geométrica. Las disposiciones de las tomas fotográficas se alinearon en
la medida de lo posible con una toma convergente, como se muestra en
la Figura 2-B. Esta es la disposición de toma de fotos recomendada por
los desarrolladores de software y ofrece la mejor precisión teórica para
la orientación (Mason, 1994). En la toma paralela (Figura 2-A), el

104 | Página

<!-- p. 105 -->

COMPARACIÓN DE SOFTWARE DESKTOP PROFESIONAL Y SOFTWARE
GRATUITO CLOUD COMPUTING EN EL MODELADO 3D DE EDIFICIOS
HISTÓRICOS: MONASTERIO DE SAN MARTÍN PINARIO

ángulo de los rayos homólogos es más pequeño que en la toma
convergente, lo que genera una zona de incertidumbre mayor (zona
indicada en color gris).

Figura 2. Disposiciones fotográficas. La incertidumbre generada por los rayos
homólogos puede observarse sombreada en gris. (A) Toma paralela. (B) Toma
convergente.

Procesado fotogramétrico SfM
En esta sección, se describen los pasos de procesado
fotogramétrico en cada opción de software estudiado.

Agisoft PhotoScan.
La primera etapa en este software trata de realizar la
alineación de las cámaras. Las imágenes JPEG se cargan, y el software
emplea un algoritmo SIFT para buscar puntos característicos de las
imágenes (Key Points), posteriormente busca sus coincidencias con
otras imágenes (Tie Points) y a partir de dicha relación calcula las
posiciones de las cámaras (Figura 3). En este paso, PhotoScan permite
la selección de diferentes grados de precisión. En el estudio, se utilizó
una “precisión alta” en los parámetros de configuración del procesado,

105 | Página

<!-- p. 106 -->

SIMÓN PEÑA VILLASENÍN

lo cual emplea el tamaño de la foto original sin aplicar reducción
alguna. En la configuración avanzada, el límite de puntos clave (Key
Points limit) indica el límite superior de los puntos característicos en
cada imagen que se tendrá en cuenta durante la etapa de procesado
inicial. El parámetro límite de punto de enlace (Tie Points limit)
determina el número de puntos de cada imagen que se considerarán
para el cálculo del posicionamiento de las cámaras a partir del
algoritmo Bundler. En total, se utilizaron 40,000 como límite de puntos
clave y 1,000 como límite de puntos de enlace.

Figura 3. Orientación de tomas y nube de puntos dispersa. Agisoft PhotoScan.

106 | Página

<!-- p. 107 -->

COMPARACIÓN DE SOFTWARE DESKTOP PROFESIONAL Y SOFTWARE
GRATUITO CLOUD COMPUTING EN EL MODELADO 3D DE EDIFICIOS
HISTÓRICOS: MONASTERIO DE SAN MARTÍN PINARIO

Figura 4. Nube de puntos 3D texturizada obtenida a partir de un procesado de
calidad alta y un filtrado de profundidad agresivo. Agisoft PhotoScan.
.
La toma fotográfica se realizó con enfoque automático, lo que
resultó en pequeñas variaciones individuales en los parámetros de
orientación interna de cada imagen. Para el cálculo inicial, el software
establece parámetros de orientación internos comunes
predeterminados para todas las fotos agrupadas según sus datos EXIF.
Sin embargo, en el menú de calibración, estos grupos se pueden separar
y los parámetros internos se pueden volver a optimizar individualmente
para cada imagen. Posteriormente, se introdujeron 6 GCP medidos con
la estación total y se realizó una transformación de similitud (Helmert).
De esta manera, el modelo 3D se puede escalar y orientar
correctamente. Los 17 CPs restantes se ingresaron al final del proceso
para evaluar la precisión del modelo.

107 | Página

<!-- p. 108 -->

SIMÓN PEÑA VILLASENÍN

Después de la optimización de la calibración y la transformación
Helmert, se procesó la nube de puntos densa. En este paso, se probaron
diversas calidades de procesado, que incluyen calidad media (tamaño
1/4), baja calidad (tamaño 1/8) y calidad alta, que se refiere al
procesado con la resolución de la foto original. El filtrado de
profundidad se puede utilizar en esta etapa de procesado. En las
opciones avanzadas, es posible elegir entre filtros deshabilitados,
moderados o agresivos, estas opciones son también testeadas en este
estudio. El procesado se ejecuta, proporcionando una nube de puntos
con textura 3D (Figura 4) al final del mismo.
Posteriormente, el software genera una malla triangular a partir de
la nube de puntos obtenida en el paso anterior. Los parámetros de
reconstrucción de la malla se pueden seleccionar en el cuadro de
diálogo. En este caso de modelados de fachadas, se debe utilizar un
tipo de superficie arbitraria. Se reconstruyó una textura en modo
genérico y el modelo se exportó al formato Wavefront (.obj).
Para obtener la vista frontal, se definió un plano de proyección
utilizando GCP como marcadores, como se muestra en la Figura 5. Se
seleccionaron tres puntos en el modelo 3D para formar los ejes del
plano en el que se obtendrá la vista ortogonal. En este caso, los números
de punto 17 y 4 definen el eje horizontal, y los puntos 20 y 4 definen
el eje vertical.

Figura 5. Procesado del ortomosaico con Agisoft PhotoScan. (Izq) Menú de
configuración de procesado del ortomosaico. (Der) Marcadores utilizados para
definir los ejes del plano de proyección.

108 | Página

<!-- p. 109 -->

COMPARACIÓN DE SOFTWARE DESKTOP PROFESIONAL Y SOFTWARE
GRATUITO CLOUD COMPUTING EN EL MODELADO 3D DE EDIFICIOS
HISTÓRICOS: MONASTERIO DE SAN MARTÍN PINARIO

Pix4D Mapper
La primera etapa en este software es la selección de un sistema
de referencia de puntos de control y el tipo de proyecto. En este caso,
se usó un sistema de coordenadas arbitrarias para la salida, y se
seleccionó un modelo 3D como se recomienda para la construcción de
trabajos de tipo fachada. La configuración del proceso inicial permite
seleccionar la configuración de búsqueda de coincidencia. Para trabajar
con los mismos parámetros que en Agisoft PhotoScan, se seleccionaron
el tamaño de la imagen original y 40,000 puntos clave coincidentes.
Los parámetros de configuración restantes se conservaron de forma
predeterminada. El primer proceso se ejecutó para obtener una nube de
puntos dispersa y los parámetros de orientación interna y externa
relativa de las imágenes (Figura 6). Luego se marcaron los 6 GCPs, y
el proyecto se re-optimiza, se orienta y se escala correctamente.

109 | Página

<!-- p. 110 -->

SIMÓN PEÑA VILLASENÍN

Figura 6. Orientación de tomas y nube de puntos dispersa.
Pix4D.

Figura 7. Malla de triángulos texturizada con calidad de procesado
“alta” y filtrado de profundidad activado. Pix4D.

110 | Página

<!-- p. 111 -->

COMPARACIÓN DE SOFTWARE DESKTOP PROFESIONAL Y SOFTWARE
GRATUITO CLOUD COMPUTING EN EL MODELADO 3D DE EDIFICIOS
HISTÓRICOS: MONASTERIO DE SAN MARTÍN PINARIO

La segunda configuración del proceso permite seleccionar la nube
de puntos y la configuración de procesado de la malla. Nuevamente, se
seleccionó el tamaño original para esta etapa y los parámetros restantes
se conservaron de manera predeterminada. El segundo proceso, el
procesado de la nube de puntos y la malla, se ejecuta y produciendo
una nube de puntos densa y una malla triangular (Figura 7) la cual es
guardada automáticamente en el directorio del proyecto en formato
Wavefront (obj). El segundo procesado se repite con todos los filtros
de profundidad desactivados para evaluar la eficiencia de los mismos.
La herramienta de generación de ortoplanos (Figura 8), permite
definir el plano sobre el que se obtiene la ortofoto. En este caso se
configuró para obtener la vista frontal de la fachada. Al final del
proceso, los CPs restantes se introducen para evaluar la precisión del
modelo.

Figura 8. Configuración del ortoplano. (A) Ortoplano por defecto. (B) Ortoplano
alineado.

111 | Página

<!-- p. 112 -->

SIMÓN PEÑA VILLASENÍN

Autodesk Remake
En este software, la única opción configurable es la calidad
del procesado; es más simple pero mucho menos configurable que
PhotoScan y Pix4D. En este caso, se eligió la calidad más alta posible.
El flujo de trabajo se describe en la Figura 9. El procesado se realiza
automáticamente mediante computación SfM “en la nube”.

Figura 9. Etapas del procesado con Autodesk Remake. (A) Carga de imágenes.
(B) Selección del directorio. (C) Selección del modo de procesado. (D)
Selección de calidad de procesado.

Cuando se completa el procesado, el software permite descargar el
modelo 3D en formato RCM (el formato nativo de Autodesk Remake).
Varias herramientas internas permiten la edición modelo. Como se
muestra en la Figura 10, para orientar y escalar el modelo de Remake,
se introducen los GCPs para calcular una transformación Helmert que
escala y coloca el modelo en la orientación correcta. Después de la
transformación, los puntos CP se marcaron para evaluar la precisión
del modelo. Finalmente, el modelo 3D se exportó en un formato
Wavefront (.obj) (Figura 11).

112 | Página

<!-- p. 113 -->

COMPARACIÓN DE SOFTWARE DESKTOP PROFESIONAL Y SOFTWARE
GRATUITO CLOUD COMPUTING EN EL MODELADO 3D DE EDIFICIOS
HISTÓRICOS: MONASTERIO DE SAN MARTÍN PINARIO

Figura 10. Configuración del sistema de coordenadas en Autodesk
Remake a partir de GCPs.

Figura 11. Malla de triángulos texturizada obtenida en Autodesk
Remake.

113 | Página

<!-- p. 114 -->

SIMÓN PEÑA VILLASENÍN

No es posible obtener ortofotos a partir de este software. Por lo
tanto, Meshlab fue utilizado con este propósito. Se realizó una rotación
en el eje Z para ubicar el plano de la fachada en la perspectiva ortogonal
(Figuras 12-A y 12-B), permitiendo que la vista frontal del modelo se
pueda obtener a partir de las vistas predefinidas (Figura 12-C).

Figura 12. Rotación del modelo 3D de Remake en MeshLab. (A) Orientación
original. (B) Orientación después de la rotación sobre el eje Z. (C) Vista frontal
del modelo 3D.

Digitalización vectorial
Las ortofotos contienen información completa sobre las fachadas
pero en un formato ráster. Existen dos métodos principalmente para
vectorizar esta información: la digitalización de las entidades
características en el software CAD sobre la ortofoto, o la digitalización
directa a través del software fotogramétrico. PhotoScan y Pix4D
permite una digitalización de modo intuitivo de las entidades
vectoriales sobre el modelo 3D en formato compatible con BIM
(Figura 13). Autodesk Remake no permite esta opción; por lo tanto, un
software externo debe ser utilizado para la vectorización.

114 | Página

<!-- p. 115 -->

COMPARACIÓN DE SOFTWARE DESKTOP PROFESIONAL Y SOFTWARE
GRATUITO CLOUD COMPUTING EN EL MODELADO 3D DE EDIFICIOS
HISTÓRICOS: MONASTERIO DE SAN MARTÍN PINARIO

Figura 13. Ejemplo de vectorización BIM en Pix4D.

Comparación de resultados
En primer lugar, se evalúan los resultados del procesado, para lo
cual se analizan el número de puntos y triángulos obtenidos, la
densidad de puntos por m2, el tiempo empleado y la relación entre estos
dos últimos parámetros.
Para evaluar la precisión geométrica, se introducen 6 GCPs en la
etapa de procesado con todas las opciones de software testeadas, como
se señala anteriormente, garantizando que los modelos 3D se
encuentran en el mismo sistema de referencia. Los restantes puntos de
coordenadas conocidas, un total de 17 CPs, se introducen
posteriormente sin influencia en la calidad del procesado. Estas
coordenadas se compararon directamente con respecto a las
coordenadas consideradas reales obtenidas con la estación total,

115 | Página

<!-- p. 116 -->

SIMÓN PEÑA VILLASENÍN

permitiendo hallar los valores de error en cada punto de control. La
Figura 14 presenta el menú de administración de GCPs y CPs en
Remake. En todas las opciones de software, se utilizan los mismos
puntos de chequeo marcados sobre la malla 3D, obteniendo los valores
de la precisión del producto final.

Figura 14. Análisis de precisión, a partir de Check Points (CPs) en
Remake.

En tercer lugar, se analizaron los resultados visuales, incluida la
calidad de la ortofoto y la textura, que se evaluaron mediante
comparación visual.
Finalmente, en base a la opinión de técnicos fotogramétricos, se
evaluó la utilidad operacional del software, analizando las ventajas y

116 | Página

<!-- p. 117 -->

COMPARACIÓN DE SOFTWARE DESKTOP PROFESIONAL Y SOFTWARE
GRATUITO CLOUD COMPUTING EN EL MODELADO 3D DE EDIFICIOS
HISTÓRICOS: MONASTERIO DE SAN MARTÍN PINARIO

desventajas del software de computación de escritorio frente al de
computación en la nube, así como entre los dos software de escritorio
testeados.

Discusión de resultados.

Resultados del procesado SfM
Pix4D y PhotoScan pueden generar nubes de puntos de alta
densidad en sus opciones de procesado de alta calidad como se muestra
en la Tabla 1. Autodesk Remake produce nubes de puntos de resolución
más baja, aunque la resolución es suficiente para las mediciones de
fachada. Los tiempos de procesado para el software de escritorio
fueron sustancialmente más bajos en comparación con los del software
de computación “en la nube”. Los tiempos de procesado del software
de escritorio corresponden a la potencia de la computadora utilizada.

TABLA 1: Resultados de la etapa de procesado en PhotoScan, Pix4D y Remake.

Config. del Puntos Número de Densidad Nº de Tiempo procesado porSoftware puntos de la nube triángulos total de de la nube tiempo de obtenido puntos/m² de la malla procesado de puntos procesado
Alta 38.885.878 30.864 86.833.482 3h 26 min. 188.766
PhotoSca Media 2.816.435 1.708 6.909.440 14 min. 201.174 n
Baja 555.418 337 1.106.545 8 min. 69.427

Alta 39.944.546 24.379 Lim. a 10 M 2 h 51 min. 233.594

Pix4D Media 9.310,279 5.646 Lim. a 10 M 52 min. 79.044

Baja 632.752 384 1.261.948 25 min. 25.310

Remake Alta 937.111 568 1.659.497 60 min. 15.619

En la Figura 15 se presentan las relaciones entre la cantidad de
puntos y el tiempo de procesado en todas las opciones de calidad
analizadas del escritorio y del software de computación “en la nube”.

117 | Página

<!-- p. 118 -->

SIMÓN PEÑA VILLASENÍN

Figura 15. Gráfica del rendimiento de PhotoScan, Pix4D, y Autodesk Remake.

La Figura 16 presenta los resultados del procesado de PhotoScan
sin filtros (Figura 16-A), con un filtro moderado (Figura 16-B) y con
un filtro agresivo (Figura 16-C). Incluso el filtro agresivo genera una
cantidad considerable de ruido. Este ruido se debe principalmente al
color de fondo blanco del cielo en las fotos. Este problema podría
haberse resuelto utilizando máscaras para este fondo.

Figura 16. Opciones de filtros de profundidad en PhotoScan. (A) Desactivado.
(B) Moderado. (C) Agresivo.

118 | Página

<!-- p. 119 -->

COMPARACIÓN DE SOFTWARE DESKTOP PROFESIONAL Y SOFTWARE
GRATUITO CLOUD COMPUTING EN EL MODELADO 3D DE EDIFICIOS
HISTÓRICOS: MONASTERIO DE SAN MARTÍN PINARIO

En contraste con PhotoScan (Figura 17-A), tanto Remake (Figura
17-B) como Pix4D (Figura 17-C) generaron modelos con poco ruido.

Figura 17. Filtrados de profundidad en el software estudiado. (A)PhotoScan con
filtrado agresivo. (B) Pix4D con filtrado activo. (C) Remake, no permite
configuración del fitlrado.

A partir de este punto el análisis hace referencia al procesado de
mayor calidad y los resultados de filtrado más agresivos en ambas
opciones del software de escritorio.

Calidad geométrica y análisis de precisión
El modelo obtenido utilizando Remake, aunque con menos
triángulos, muestra una calidad geométrica similar a la de los modelos
de PhotoScan y Pix4D de alta calidad en todos los tipos de superficies.
La Figura 18, muestra que en la malla obtenida en Remake, los vértices
no están distribuidos homogéneamente como en Pix4D o PhotoScan,
pero la malla se presenta como una alta densidad de vértices en zonas
no planas. Esta distribución de vértices explica por qué se obtiene la
alta definición con un número reducido de puntos. Autodesk Remake
obtiene automáticamente modelos en los que las áreas planas tienen
menos densidad de triángulos. Esta característica también es posible en
el software de escritorio si se realiza una reducción de la malla con la
herramienta de reducción. Esta es una opción interesante porque agiliza
el uso del modelo. En los otros tipos de geometría, como los salientes
de las ventanas o en áreas de ornamentación altamente detallada, los
resultados son similares en todos los programas testeados.

119 | Página

<!-- p. 120 -->

SIMÓN PEÑA VILLASENÍN

Figura 18. Malla triangular texturizada obtenida a partir de Remake.
Calidad alta.

La Figura 19 presenta capturas de las mallas 3D obtenidas en
PhotoScan (Figura 19-A), Pix4D (Figura 19-B) y Remake (Figura 19C) en las mejores calidades.

Figura 19. Mallas 3D. (A) PhotoScan. (B) Pix4D. (C) Remake.

La Tabla 2 presenta los resultados de la evaluación de la precisión
de cada punto medido y el error medio calculado para cada paquete de
software analizado. Los valores de error se calcularon como el
promedio de las diferencias entre las coordenadas de los puntos
medidos con la estación total en las fachadas y los obtenidos en los

120 | Página

<!-- p. 121 -->

COMPARACIÓN DE SOFTWARE DESKTOP PROFESIONAL Y SOFTWARE
GRATUITO CLOUD COMPUTING EN EL MODELADO 3D DE EDIFICIOS
HISTÓRICOS: MONASTERIO DE SAN MARTÍN PINARIO

modelos. Teniendo en cuenta que existe incertidumbre al marcar
puntos en el modelo, los resultados de los tres paquetes de software en
términos de precisión pueden considerarse idénticos. El error más alto
en el modelo de cada paquete de software está escrito en negrita y es
inferior a 35 mm en todos los casos.

Tabla 2. Resultado del análisis de precisión (errores expresados en metros).

Point PhotoScan Pix4D Remake

1 0.025 0.022 0.024
2 0.013 0.013 0.012

3 0.018 0.017 0.023

4 0.02 0.017 0.021

5 0.017 0.019 0.011
6 0.005 0.012 0.014

7 0.035 0.022 0.015
Check 8 0.021 0.016 0.020
Points 9 0.008 0.009 0.029
(CPs) 10 0.021 0.021 0.012

11 0.015 0.015 0.009

12 0.013 0.012 0.016

13 0.014 0.011 0.012
14 0.01 0.005 0.005

15 0.011 0.012 0.011

16 0.016 0.024 0.020

17 0.019 0.008 0.010
Media de 0.017 0.015 0.016 error
Desv. 0.00701 0.0054 0.0063 Estándar

121 | Página

<!-- p. 122 -->

SIMÓN PEÑA VILLASENÍN

Calidad visual
Los modelos 3D texturizados obtenidos en Remake (Figura 20-C)
son visualmente similares a los obtenidos en PIX4D (Figura 20-B) y
PhotoScan (Figura 20-A) como se muestra en la Figura 20.

Figura 20. Modelos 3D texturizados. (A) PhotoScan. (B) Pix4D. (C) Remake.

La Figura 21 muestra las ortofotos obtenidas en cada paquete de
software. Los resultados obtenidos en PhotoScan (Figura 21-A) son
ligeramente mejores que los obtenidos en PIX4D (Figura 21-B), esto
se debe principalmente a la diferencia entre ambos en el modo de
procesado de dicha ortofoto. La calidad de la ortofoto obtenida con
Remake (Figura 21-C) es notablemente peor debido a las limitaciones
del software. En lugar de un mosaico de imágenes corregidas por
distorsión, la ortofoto es una vista ortogonal del modelo texturizado
generado en el software Meshlab.

Figura 21. Ortoimágenes. (A) PhotoScan. (B) Pix4D. (C) Remake.

122 | Página

<!-- p. 123 -->

COMPARACIÓN DE SOFTWARE DESKTOP PROFESIONAL Y SOFTWARE
GRATUITO CLOUD COMPUTING EN EL MODELADO 3D DE EDIFICIOS
HISTÓRICOS: MONASTERIO DE SAN MARTÍN PINARIO

Facilidad de uso y opciones de exportación
En esta sección se describe, la facilidad de uso relativa de cada
paquete de software junto con otras consideraciones globales con
respecto a su uso como herramienta de procesado, ventajas y
limitaciones y opciones de exportación.

Software de computación local vs computación “en
la nube”.
El flujo de trabajo de Remake es muy simple, apenas es
necesario un aprendizaje previo para ejecutar un procesado. En
PhotoScan y Pix4D, el flujo de trabajo es más complejo, pero también
tiene un nivel de automatización muy alto. Por lo tanto, 3-4 semanas
de aprendizaje podría ser suficiente para su manejo general. PhotoScan
y Pix4D tienen más opciones de procesado que Remake. Al emplear
puntos de referencia con coordenadas conocidas en el elemento, el
software profesional puede calcular un ajuste óptimo de la malla que
puede ser altamente preciso si se ingresan muchos puntos. Tanto Pix4D
como Agisoft PhotoScan permiten la generación y exportación de
entidades vectoriales 3D. Esta digitalización permite exportar
información a formatos compatibles con el software BIM. El software
profesional de computación local, también ofrece más opciones de
exportación en 2D y 3D que el software cloud computing analizado,
por ejemplo, ortofotos o PDFs en 3D.
Remake es un paquete de software de bajo coste con un flujo de
trabajo simple, que permite a cualquier usuario crear modelos
fotorrealistas en 3D con una cámara convencional y un PC de usuario
medio. El software Remake proporciona un proceso automatizado en
el que la escena se reconstruye utilizando el servidor. Este software,
también incluye herramientas de edición intuitivas para la reparación
de errores, la impresión 3D y la exportación de video. En este caso de
estudio, los resultados de precisión de Remake fueron similares a los
obtenidos con software profesional. Sin embargo, Remake tiene varias
limitaciones que pueden ofrecer malos resultados en otros tipos de
fachadas. El usuario tiene un número limitado de imágenes (250 en este
caso), y la densidad de la malla es limitada, lo que puede ser un

123 | Página

<!-- p. 124 -->

SIMÓN PEÑA VILLASENÍN

problema para modelar fachadas más ornamentadas. Además, pocos
parámetros de proceso pueden ser controlados y en el caso de una
orientación automática incorrecta, el programa no ofrece la opción de
identificación manual de puntos de paso que corrijan la misma. No
permite la digitalización directamente en la malla, pero se puede
utilizar un software externo para realizar esta tarea. La Figura 22
presenta el resultado de la digitalización vectorial en software CAD
superpuesta al alzado obtenido en Meshlab a partir del modelo 3D de
Remake.

Figura 22. Ortofoto y digitalización vectorial a partir del modelo obtenido en
Remake.

124 | Página

<!-- p. 125 -->

COMPARACIÓN DE SOFTWARE DESKTOP PROFESIONAL Y SOFTWARE
GRATUITO CLOUD COMPUTING EN EL MODELADO 3D DE EDIFICIOS
HISTÓRICOS: MONASTERIO DE SAN MARTÍN PINARIO

Aunque la fotogrametría permite obtener productos más
avanzados, puede ser útil simplemente como herramienta de
recopilación de datos métricos para profesionales de la arquitectura y el
patrimonio. El software de computación en la nube, es una gran opción
en estos casos por su facilidad de uso como se muestra en la Figura 23.
Solo se necesita una distancia de referencia para escalar el modelo
y una colección de fotos para obtener medidas de todos los elementos
presentes en una fachada. El uso de métodos tradicionales o software
de escritorio sería más lento, difícil y tedioso.

Figura 23. Múltiples mediciones individuales sobre un elemento de la
fachada (metros).

Cabe señalar que la naturaleza en línea de las herramientas de
computación “en la nube” dará lugar a actualizaciones periódicas no
opcionales en los servicios de modelado 3D. Un ejemplo claro es
Autodesk Remake, el cual sustituye a 123DCatch en 2009. El programa

125 | Página

<!-- p. 126 -->

SIMÓN PEÑA VILLASENÍN

se convirtió más tarde en el servicio Recap Photo y, posteriormente, en
Project Memento, que evolucionó a Autodesk Memento, que
posteriormente pasó a llamarse Autodesk Remake y actualmente de
nuevo Autodesk Recap Photo. Este última evolución del software de
procesado fotogramétrico de Autodesk puede incluso procesar trabajos
aéreos. No obstante el cambio continuo de nombre y condiciones del
servicio genera inseguridad técnica y confusión.
Los diferentes productos que se pueden obtener en el software
descrito se resumen en la Tabla 3.

Tabla 3. Opciones de exportación.

PDF Vectorización Informe de Software Ortomosaico Video 3D BIM procesado

PhotoScan Sí Sí Sí Sí No

Pix4D Sí Sí Sí Sí Sí
Proyección
ortogonal del Software Remake No No Sí modelo externo
texturizado

Pix4D vs. PhotoScan
Pix4D tiene ciertas ventajas en comparación con PhotoScan
en términos de facilidad de uso, gracias a una interfaz más intuitiva.
Permite la posibilidad de exportar video, y un mayor número de
opciones de visualización. El ruido de la nube de puntos es
considerablemente menor que en PhotoScan. Pix4D ofrece diferentes
configuraciones de visualización tanto para malla como para nubes de
puntos. La Figura 24 presenta la nube de puntos obtenida en este
software en el modo de visualización de altitud. No obstante,
PhotoScan ofrece mejores resultados en la obtención ortofotos en
alzado.

126 | Página

<!-- p. 127 -->

COMPARACIÓN DE SOFTWARE DESKTOP PROFESIONAL Y SOFTWARE
GRATUITO CLOUD COMPUTING EN EL MODELADO 3D DE EDIFICIOS
HISTÓRICOS: MONASTERIO DE SAN MARTÍN PINARIO

Figura 24. Nube de puntos con color por alturas.

Conclusiones.
La fotogrametría de corto alcance es una técnica interesante para
obtener modelos 3D de edificios y ofrece numerosas vías de estudio en
patrimonio y arquitectura, ya que solo una cámara y un instrumento de
medición, como un flexómetro, son necesarios para la toma de datos.
Tanto el software de escritorio como el de computación “en la nube”
testeados, pueden producir resultados precisos como se demuestra en
este estudio. Se espera que la progresión de los sensores, los algoritmos
de cálculo y la computación en la nube, además de las actualizaciones
continuas de los servicios web fotogramétricos, proporcionen
herramientas de mayor potencial para los profesionales del patrimonio,
permitiendo la capacidad de obtener medidas de manera confiable y
simple, documentar texturas o formas complejas, mostrar
visualizaciones atractivas o diseñar directamente sobre los modelos 3D
de edificios existentes, entre otras opciones.
Los paquetes de software de computación “en la nube” y de
escritorio ofrecen resultados similares en términos de precisión y

127 | Página

<!-- p. 128 -->

SIMÓN PEÑA VILLASENÍN

calidad visual. Por lo tanto, la computación “en la nube” es una opción
interesante para los profesionales del patrimonio que no se han
especializado en fotogrametría y que están buscando una buena
relación entre precio, calidad y facilidad de uso en la adquisición de
software fotogramétrico. Además, el software de computación “en la
nube” tiene un flujo de trabajo simple, apenas es necesario un
aprendizaje previo, y solo requieren equipos informáticos de nivel
usuario. Los modelos de Remake obtienen una buena evaluación en las
variables estudiadas por lo que el software obtiene un gran
rendimiento.
El software profesional es una opción recomendada si se necesitan
productos derivados, como ortofotos o directamente vectorizaciones
BIM; sin embargo, estas funciones también se pueden obtener con
software de computación “en la nube” mediante software externo. El
análisis de los resultados del software de escritorio demuestra que tanto
Pix4D como PhotoScan tienen un alto rendimiento. Sin embargo,
algunas de las ventajas que ofrece PhotoScan se encuentran en la
calidad geométrica y visual de los resultados, y las ventajas de Pix4D
son la facilidad de uso y la amplia variedad de opciones visuales.
Como una limitación notable de la fotogrametría, en las áreas
superiores de la fachada, ciertas partes ocultas no aparecen en el
modelo, por lo que sería recomendable usar pértigas o drones para
levantar la cámara y capturar información de estas áreas. Otra
limitación podría ser el espacio disponible para la sesión de fotos, ya
que el espacio de trabajo representa una importante desventaja. En este
estudio, la fachada de piedra es un material perfectamente adaptado a
esta prueba; Las líneas futuras de investigación deberían analizar el
comportamiento de la computación “en la nube” en superficies más
reflexivas, ya que el software no permite una configuración del
procesado adaptada a dicha situación, lo que si sería posible en el
software profesional.

128 | Página

<!-- p. 129 -->

CAPITULO III

\7. CAPITULO III

COMPARACIÓN DE TLS Y FOTOGRAMETRÍA
SFM PARA EL MODELADO 3D DE ARTE
RUPESTRE Y LA APLICACIÓN DEL REALCE
RADIANCE SCALING SHADER PARA LA
DETECCIÓN DE GRABADOS

RESUMEN
El inventario geométrico y la documentación del arte rupestre
presentan grandes desafíos debido a la gran cantidad de petroglifos
existentes en el territorio, la distancia entre ellos, en muchos casos el
estado de abandono de las áreas forestales, las limitaciones de acceso
y las características geométricas de este patrimonio. La fotogrametría
Structure from Motion (SfM) se posiciona como una técnica ideal para
su documentación, pero esta técnica tiene una gran variabilidad en su
metodología y coste de ejecución. En este estudio, se compara un
método simple y eficaz basado en la fotogrametría SfM con software
de computación “en la nube” de bajo coste con el uso de un escáner
láser terrestre (TLS) para generar modelos 3D de petroglifos. La
comparación se realiza en la documentación 3D del petroglifo de O
Castriño de Conxo en Santiago de Compostela, España, y se extiende
a dos experimentos prácticos en otros petroglifos. Las mallas se
comparan mediante el análisis de criterios visuales, geométricos y
operacionales y su grado de adaptación a la aplicación del renderizado
de grabados Radiance Scaling Shader. Los resultados muestran que

129 | Página

<!-- p. 130 -->

SIMÓN PEÑA VILLASENÍN

con una metodología de fotogrametría SfM accesible a perfiles no
expertos, es posible obtener mejores resultados en aspectos
geométricos y visuales que los obtenidos con TLS, siendo estos válidos
para un análisis detallado de arte rupestre y que por tanto, permite de
un modo colaborativo una documentación masiva del fenómeno que
no es posible exclusivamente por medios profesionales.

130 | Página

<!-- p. 131 -->

COMPARACIÓN DE TLS Y FOTOGRAMETRÍA SFM PARA EL MODELADO 3D DE
ARTE RUPESTRE Y LA APLICACIÓN DEL REALCE RADIANCE SCALING SHADER
PARA LA DETECCIÓN DE GRABADOS

Introducción y objetivos
Los nuevos métodos de adquisición de datos geométricos están
revolucionando las formas de documentar el patrimonio arqueológico
(J.H. Chandler et al., 2005; Cirulis et al., 2015; Gonizzi Barsanti et al.,
2013; Karsli et al., 2003; Simpson et al., 2004). Para representar con
precisión la información de sitios complejos u objetos con
irregularidades o curvaturas, es necesario construir nubes de puntos 3D
de alta densidad. Actualmente, la fotogrametría Structure from Motion
(SfM) (Remondino & El-Hakim, 2006), el láser escáner terrestre (TLS)
(Altuntas et al., 2007) y la combinación de ambos (Al-kheder et al.,
2009; Grussenmeyer et al., 2012; Guidi et al., 2004; Lambers et al.,
2007; José Luis Lerma et al., 2010; Yastikli, 2007) se han establecido
como las técnicas más utilizadas en la adquisición de nubes de puntos
texturizados de alta precisión y resolución. Estas técnicas, que
permiten la adquisición de modelos 3D de resultados métricos y
fotorrealistas de alta calidad, representan una herramienta poderosa
para la identificación, monitoreo, conservación y restauración de
elementos del patrimonio (Campana & Remondino, 2008; Chiabrando
et al., 2011; Martínez-Rodríguez et al., 2015).
El conjunto arqueológico gallego de arte rupestre es la expresión
artística más significativa de las comunidades que habitaron estas
tierras en la edad de bronce. Catalogados dentro de la familia de arte
rupestre “Atlántico”, estos petroglifos tienen una fuerte personalidad
que los hace reconocibles entre muchos otros. Considerando el número
y la calidad de los diseños, el arte rupestre gallego es una de las
manifestaciones culturales más importantes de este tipo en Europa
(Bradley, 2002; Bradley et al., 1994; Bradley & Fábregas-Valcarce,
1998; Santos-Estévez, 2015). La documentación del fenómeno de los
petroglifos gallegos es desafiante por sus características geométricas
con grabados poco profundos, que tienden a ubicarse en las caras semi
horizontales de afloramientos rocosos de poca altura, lo que los hace
difíciles de apreciar bajo luz natural. Tradicionalmente, se han
utilizado técnicas como el Frotagge o el calco con plástico (LewisWilliams & Pager, 1990; Medici & Rossi, 2015; Moneva Montero,
1993). Estas técnicas son lentas y tediosas, tienen un alto grado de

131 | Página

<!-- p. 132 -->

SIMÓN PEÑA VILLASENÍN

subjetividad y pueden dañar el soporte. Este complicado registro ha
dado lugar a documentaciones e interpretaciones parciales del conjunto
arqueológico, como se discute en (Rodríguez Rellán et al., 2018),
donde se muestra que el territorio gallego tiene un número de
petroglifos catalogados por encima de 3000 y que año tras año, este
catálogo aumenta. Sin embargo, en la mayoría de los casos, la única
documentación existente es una descripción textual y su
geolocalización aproximada, lo que conduce a una interpretación
parcial del fenómeno. La documentación geométrica de todo el arte
rupestre no es factible por razones técnicas y económicas, y al mismo
tiempo, esta documentación es una tarea muy necesaria debido al alto
riesgo de deterioro de este patrimonio que está totalmente expuesto a
agentes externos. La colaboración social es la única forma de
documentar geométricamente este fenómeno cultural de manera
masiva. Por esta razón, es de vital importancia que los agentes sociales
conozcan y administren herramientas y técnicas cuyo uso para esta
tarea sea ágil, simple, económico y efectivo.
La fotogrametría ha demostrado ser más adaptable a las
particularidades de diferentes escenas, como se muestra en (PeñaVillasenín et al., 2017). Además, las principales ventajas de la
fotogrametría se presentan en el tiempo y coste de ejecución; Por lo
tanto, es la técnica más apropiada para esta documentación masiva. Sin
embargo, estas variables empeoran si se utilizan en el proceso software
profesional y puntos de control en tierra (GCP). Por otro lado, artículos
como (Ortiz-Sanz et al., 2011) describen metodologías simples que
también resultan ser precisas para el estudio del arte rupestre. Por lo
tanto, la fotogrametría se puede ejecutar con diferentes metodologías
de recopilación de datos, entre las cuales, independientemente de la
calidad de los resultados, hay diferencias notables de rendimiento en
tiempos y costes que cabe analizar.
Con respecto a la TLS, la operatividad, por ejemplo, en
condiciones de poca iluminación, es superior a la de la fotogrametría
SfM. Sin embargo, a pesar de los beneficios del TLS en la
documentación del patrimonio arqueológico, el tiempo requerido para
el trabajo de campo, el coste del equipo, los problemas en el transporte
y la complejidad de la administración de datos, a menudo conducen a

132 | Página

<!-- p. 133 -->

COMPARACIÓN DE TLS Y FOTOGRAMETRÍA SFM PARA EL MODELADO 3D DE
ARTE RUPESTRE Y LA APLICACIÓN DEL REALCE RADIANCE SCALING SHADER
PARA LA DETECCIÓN DE GRABADOS

graves problemas de practicidad en lugares arqueológicos (Campana
& Remondino, 2008). Además, la combinación de escaneos introduce
inconsistencias en la orientación de los mismos, y en la mayoría de los
TLS no se especifica correctamente la precisión que obtienen (Boehler
& Marbs, 2004). Estudios anteriores han comparado la fotogrametría
SfM y el TLS, normalmente en condiciones óptimas para registrar el
patrimonio cultural, con resultados similares para ambos (D.D. Lichti,
S. J. Gordon, M. P. Stawart, J. Franke, 2002). Otras comparaciones
como en (Baltsavias, 1999; Grussenmeyer et al., 2008) han demostrado
que la elección óptima de la técnica depende del objeto a modelar y las
condiciones del trabajo, que requieren una evaluación de la eficiencia
de ambas opciones en cada caso particular: por ejemplo, en el
modelado de petroglifos, donde existen factores determinantes en la
aplicación de ambas técnicas, como la geometría de la roca, la
vegetación del entorno y las limitaciones de acceso.
Existen otras comparaciones entre TLS y fotogrametría, como en
los estudios (Guarnieri et al., 2013; Lato et al., 2015; López-Menchero
Bendicho et al., 2017; Skarlatos & Kiparissi, 2012; Wilkinson et al.,
2016), pero la metodología de fotogrametría utilizada en ellos es
demasiado compleja para perfiles no expertos porque requiere GCP
(que implica el uso de dispositivos topográficos y software de
escritorio) o el uso de otros dispositivos como pértigas, drones o
cámaras de alto coste. Por este motivo, este caso de estudio compara
los resultados de una documentación compleja utilizando TLS con la
aplicación de una metodología simple de fotogrametría SfM. Además,
se verifican otros flujos de trabajo fotogramétricos con software
profesional y uso de GCP para evaluar la diferencia en el consumo de
tiempo entre estas metodologías fotogramétricas. Se analizan
diferentes variables como el coste, el trabajo de campo, el rendimiento
del procesado, la calidad geométrica y visual y el potencial de
detección de los grabados del TLS y la fotogrametría simple. Además,
con el objetivo de extrapolar los resultados y evaluar la eficiencia real
y la simplicidad de la técnica, se llevan a cabo dos experimentos
prácticos en los que se utiliza esta metodología simple para otros
ejemplos de arte rupestre.

133 | Página

<!-- p. 134 -->

SIMÓN PEÑA VILLASENÍN

Metodología
Esta sección describe el objeto de estudio, la metodología utilizada en
el procesado de fotogrametría TLS y SfM, el método de comparación y
los dos experimentos en otros ejemplos de arte rupestre.

Caso de estudio: O Castriño de Conxo
El petroglifo de O Castriño de Conxo se encuentra en Santiago de
Compostela, Galicia, en el noroeste de España. Es uno de los “paneles
de armas” más importantes (La Peña-Santos, 1969) dentro del grupo
de arte rupestre “Atlántico”. Además de las particularidades generales
de este tipo de patrimonio, varias condiciones complican la
documentación completa de este elemento, como por ejemplo, la
suavidad de los grabados en forma de “U” que tienen de 2 a 3 cm de
ancho por 0.5 a 1 cm de profundidad, las grandes dimensiones y la
pendiente de la roca (aproximadamente 8.20 × 2.80 m), la existencia
de valla metálica en el extremo sur del afloramiento y la existencia de
una importante vegetación en el entorno que limita considerablemente
el espacio de trabajo, una situación que se produce en la mayoría de los
petroglifos gallegos, lo que dificulta la aplicación de ambas técnicas y
justifica la elección de este petroglifo como representativo. La
ubicación de este elemento se muestra en la Figura 1 (Punto 1).

134 | Página

<!-- p. 135 -->

COMPARACIÓN DE TLS Y FOTOGRAMETRÍA SFM PARA EL MODELADO 3D DE
ARTE RUPESTRE Y LA APLICACIÓN DEL REALCE RADIANCE SCALING SHADER
PARA LA DETECCIÓN DE GRABADOS

Localización de los ejemplos de arte rupestre. (1) O Castriño de Conxo, en
Santiago de Compostela. (2) Monçao, en Portugal donde, (A1-6) Terreiros, (B1-
\2) Nossa Senhora da Assunçao, (C1-3) Badim, (D1-4) Segade y (E1) Sá. (3)
Monte Castelo, en Ames. (4) Pedra da Grada, en Moraña. (5) O Pumariño, en
Brión. (6) Cortellos, en Santiago de Compostela. (7) Pedrouzos, en Vimianzo.
(8) Chan das Lamas, en A Estrada.

Láser escáner terrestre
Desde el desarrollo del primer TLS en 1999, esta tecnología ha sido
testigo de una fase de desarrollo, crecimiento y expansión continua en
múltiples campos. En este método de modelado masivo (Beraldin et
al., 2000; Blais, 2004), se utilizan sensores activos que capturan
directamente la información geométrica 3D del objeto mediante el uso
de láser o luz estructurada, como se muestra en (McPherron et al.,
2009). Estos dispositivos recuperan información en 3D aplicando
diferentes principios de medición como la triangulación, el tiempo de
vuelo o la amplitud modular. Son sistemas robustos y costosos que
presentan problemas de manejo complejos, presentando, en ocasiones,

135 | Página

<!-- p. 136 -->

SIMÓN PEÑA VILLASENÍN

problemas graves de operatividad para la documentación de arte
rupestre, o son demasiado costosos para la documentación de todos los
elementos catalogados en tareas de prospección (El-Hakim et al.,
2005).

Toma de datos
El afloramiento rocoso donde se ubica el petroglifo fue
escaneado utilizando un escáner Focus3D X 130 de la empresa FARO
(Florida, EE. UU.). Este TLS es un escáner de 360° con una precisión
de 2 mm y un rango de 0,6 a 130 m. La toma de datos se realizó a
aproximadamente 1,5 a 2 m de la roca en cinco posiciones. Estas
posiciones se eligieron adaptándose a las limitaciones y condiciones
geométricas para minimizar las partes ocultas. Se utilizaron cuatro
esferas de referencia para la alineación relativa de los escaneos. Las
posiciones de los puntos de escaneo y esferas se muestran en la Figura
2-A.

Procesado
El procesado y alineación de cada escaneo se realizó con el
software FARO SCENE, que procesa los datos obtenidos directamente
del TLS. El software detecta automáticamente las esferas de referencia
y alinea y unifica el conjunto de datos. Una vez que se obtiene la nube
de puntos definitiva, se refina y se exporta en el formato PTX.
Posteriormente, el software Geomagic Studio importa el archivo de
nube de puntos para generar la malla triangular. Los pequeños orificios
de la malla en áreas donde las protuberancias de la roca no permiten un
escaneo correcto se rellenan para obtener una rejilla homogénea.
Además, para trabajar de manera eficiente, el modelo se simplifica a 8
millones de triángulos.

Fotogrametría SfM
La fotogrametría es una técnica con una larga trayectoria que,
paralelamente a la expansión del escáner láser, sufrió una importante
evolución que propició una creciente popularidad en sectores como el

136 | Página

<!-- p. 137 -->

COMPARACIÓN DE TLS Y FOTOGRAMETRÍA SFM PARA EL MODELADO 3D DE
ARTE RUPESTRE Y LA APLICACIÓN DEL REALCE RADIANCE SCALING SHADER
PARA LA DETECCIÓN DE GRABADOS

de la arqueología (De Reu et al., 2014) y particularmente para la
documentación de arte rupestre (Bea & Angás, 2017; Jim H. Chandler
et al., 2007; Ortiz-Sanz et al., 2010). El desarrollo de algoritmos de
extracción de datos 3D basados en imágenes (Jim Chandler, 1999;
Lane et al., 2000), y los métodos de calibración para cámaras no
métricas. (Jh Chandler et al., 2005; S. Martínez, 2012) han contribuido
a la expansión de SfM. Esta tecnología utiliza un proceso automatizado
para obtener nubes de puntos, mallas triangulares y modelos 3D con
textura, a partir de fotografías (Remondino & El-Hakim, 2006;
Westoby et al., 2012).
El desarrollo de ciertos algoritmos, como los algoritmos de
transformación de característica invariante de escala (SIFT) (Chandran
et al., 1997; Keypoints & Lowe, 2004), el ajuste Bundler (Clarke &
Fryer, 1998; Fraser, 2013; Snavely et al., 2008; Triggs et al., 2000) y
los algoritmos Clustering Views for Multi-view Stereo (CMVS) y
Patch-based Multi-view Stereo (PMVS) (Furukawa et al., 2010;
Furukawa & Ponce, 2010) son factores notables en la evolución de esta
técnica. Software de escritorio como Eos Photomodeler (Barazzetti et
al., 2011), Agisoft PhotoScan (De Reu et al., 2013b) o Pix4D Mapper
(Strecha et al., 2012) son las herramientas de software fotogramétricas
más utilizadas por los profesionales. Software de código abierto, como
VisualSfM (Remondino et al., 2012) también está disponible. Sin
embargo, durante la última década, el uso de los recursos de
computación “en la nube” ha aumentado y muchos servicios de
procesado de imágenes se realizan en un servidor externo. Ejemplos de
tales servicios son ARC3D (Tingdahl & Van Gool, 2011), 123DCatch
(Jim; Chandler & Fryer, 2013; Santagati & Inzerillo, 2013), el cual ha
dejado de estar disponible, y Autodesk Memento (Johnson & Solis,
\2016) (que es la versión beta de Autodesk Remake (Nikolov & Madsen,
2016), actualmente denominado Autodesk Recap Photo (2017). Incluso
los teléfonos inteligentes modernos se pueden utilizar para tomar fotos
y generar y visualizar modelos 3D en un solo dispositivo con
aplicaciones como SCANN3D o TRNIO.

137 | Página

<!-- p. 138 -->

SIMÓN PEÑA VILLASENÍN

Toma fotográfica.
La toma fotográfica se realizó del modo más simple posible,
utilizando una cámara convencional, en concreto una Olympus Pen Ep1 con una longitud de focal fija de 14 mm, que equivale a 35 mm en el
formato Full Frame. Se toman un total de 99 fotos (64 desde el exterior
hacia el interior y 35 longitudinalmente al afloramiento, como se
muestra en la Figura 2-B) la sensibilidad empleada fue ISO 200, una
velocidad de obturación de 1/160 y una apertura de diafragma de 6.3.
No se utilizó ningún trípode porque esto retrasa significativamente la
toma y es un factor limitante en la elección de la disposición de las
fotos. Se desactivaron todos los automatismos estabilizadores del
objetivo, excepto el enfoque automático.

Figura 2. (A) Puntos de escaneo y esferas de referencia. (B) Disposición de
tomas fotográficas.

138 | Página

<!-- p. 139 -->

COMPARACIÓN DE TLS Y FOTOGRAMETRÍA SFM PARA EL MODELADO 3D DE
ARTE RUPESTRE Y LA APLICACIÓN DEL REALCE RADIANCE SCALING SHADER
PARA LA DETECCIÓN DE GRABADOS

Para la estabilización de las tomas, el único método utilizado fue
la fijación al cuello con una correa en el momento de la captura. El
único requisito en la toma fue cubrir toda la superficie de la roca a una
distancia de aproximadamente 1,5 m desde el punto de toma con
fotografías suficientemente solapadas.
Con el objetivo de evaluar el tiempo de trabajo de campo de esta
tarea, se midieron los GCP, los cuales mejoran el ajuste fotogramétrico
en el procesado con software profesional (PhotoScan y Pix4D); por lo
tanto, antes de la toma, 10 dianas fueron colocados en la escena. Las
coordenadas de estas se midieron con la estación total sin prisma
TOPCON GPT 7005, con una precisión angular de 5” y una precisión
de medición en distancias sin prisma de 5 mm + 2 ppm.

Procesado fotogramétrico.
Con la misma colección de imágenes, se realizan tres procesos
fotogramétricos independientes para evaluar el tiempo de procesado de
la fotogrametría profesional con el uso de GCP y software de
escritorio, Agisoft PhotoScan y Pix4D; y una fotogrametría simple sin
GCP y con el software de bajo coste y de computación “en la nube”
Autodesk Remake.
En ambos programas de escritorio, el flujo de trabajo es similar.
Las fotografías se importan y se realiza una primera orientación del
conjunto de imágenes. A continuación, los puntos de control terrestre
(GCP) se introducen para la georreferenciación y proporcionar
precisión geométrica a la escena. Luego, la orientación de imágenes se
reajusta y, finalmente, se procesan la nube de puntos densa y la malla
triangular.
En Autodesk Remake, el flujo de trabajo presenta gran simpleza.
El procesado se realiza en la nube, y el usuario puede cerrar el
programa una vez que se complete la carga de las fotos. Cuando
finaliza el este, se envía una notificación de mensaje de correo
electrónico, y es posible descargar y visualizar la malla final en la
aplicación. En este paso, la malla se puede escalar y orientar

139 | Página

<!-- p. 140 -->

SIMÓN PEÑA VILLASENÍN

simplemente basándose en una medición de referencia y una
restricción de orientación por medio de una plomada y una brújula.

Comparación de resultados
El TLS y diferentes flujos de trabajo fotogramétricos fueron
comparados. Para ello, se analizaron los costes, tiempos de trabajo y
los resultados estadísticos de la nube de puntos y de la malla. Luego,
se realizó una comparación entre la malla obtenida a través de TLS y la
obtenida mediante la metodología de fotogrametría simple descrita. Se
analizaron tres criterios: la precisión geométrica de la malla, la calidad
de la textura y el potencial de detección y análisis de grabados.
Para el estudio de la precisión geométrica, los modelos
fotogramétricos y el obtenido a partir de TLS, se importaron a
Geomagic Studio. Los modelos se encuentran en diferentes sistemas de
referencia, no obstante este software alinea las mallas mediante un
proceso automatizado, mostrando los errores máximos, las medias, el
error medio cuadrático (RMS) y los valores de desviación de dicha
alineación. Además, de cara a evaluar no solo la precisión métrico si
no la calidad geométrica de la malla, se analizó la presencia de huecos
o inconsistencias en los modelos.
Para los criterios visuales, se analizó la calidad de la textura y el
color de las mallas generadas mediante una comparación visual
subjetiva.
Para evaluar el potencial de las tareas de detección y análisis de
grabados, cabe señalar que aunque los modelos 3D de fotogrametría o
TLS aportan información geométrica completa de estos, un procesado
posterior de realce es necesario para observar los mismos de un modo
más evidente. Durante los últimos años, la aplicación de varios
renderizado Radiance Scaling (Carrero-Pazos et al., 2012) o
Decorrelation Stretching como DStretch (Harmon, 2008; Le Quellec
et al., 2015), se han utilizado para realzar los grabados y pinturas
rupestres con grandes resultados. Como se muestra en (Vergne et al.,
2010), el complemento Radiance Scaling Shader ayuda a realzar las
variaciones menores en la profundidad de un modelo, en muchos casos,

140 | Página

<!-- p. 141 -->

COMPARACIÓN DE TLS Y FOTOGRAMETRÍA SFM PARA EL MODELADO 3D DE
ARTE RUPESTRE Y LA APLICACIÓN DEL REALCE RADIANCE SCALING SHADER
PARA LA DETECCIÓN DE GRABADOS

identifica detalles que no son visibles a simple vista. Este complemento
ajusta las intensidades de luz reflejada en función de la curvatura de la
superficie, mejorando así la visualización de las concavidades y
convexidades de la misma (Vergne et al., 2010). El renderizado
Radiance Scaling se utiliza en este caso para realzar los grabados
presentes en la roca. Los resultados se comparan con las
documentaciones anteriores realizadas con métodos tradicionales,
como el Frotagge o la fotografía digital con luz artificial.

Documentación de arte rupestre con fotogrametría
SfM
El estudio se amplía en dos líneas de trabajo. En primer lugar, en
el experimento 1, se realiza la documentación geométrica de varios
petroglifos ubicados en un área geográfica con un radio de 6 km. Sus
localizaciones se muestran en la Figura 1 (Punto 2). Se realizó una toma
fotográfica simple con una cámara convencional. Esta tarea fue
realizada por un técnico con 5 años de experiencia en fotogrametría
terrestre, con el objetivo de evaluar el número de elementos que
podrían documentarse en una jornada de campo. En segundo lugar,
en el experimento 2, la documentación de varios petroglifos, algunos
de ellos aún no documentados geométricamente hasta la fecha, fue
realizada por aficionados al arte rupestre, con una sesión de formación
de 1 hora y utilizando cámaras convencionales. Sus localizaciones se
muestran en la Figura 1 (Puntos 3 a 8). El flujo de trabajo en ambos
experimentos se ejecutó de acuerdo con la metodología de toma
fotográfica descrita anteriormente, utilizando para el procesado el
software de computación “en la nube” Recap Photo de Autodesk y sin
utilizar GCPs en el ajuste. Sobre los resultados se aplica
posteriormente el renderizado Radiance Scaling Shader de Meshlab.

141 | Página

<!-- p. 142 -->

SIMÓN PEÑA VILLASENÍN

Resultados y discusión
Como resultado del trabajo de campo de TLS, se obtuvieron cinco
archivos de nube de puntos, que se alinearon y exportaron como una
nube única de 9.5 millones de puntos. De esta nube, se obtuvo una
malla texturizada simplificada de 8 millones de triángulos (Figura 3A). La Figura 3-B muestra la malla obtenida con fotogrametría SfM. El
nivel de detalle es alto y los grabados de la escena se documentan
fielmente. Los resultados obtenidos por tres opciones de software son
visualmente similares.

Figura 3. Comparación de mallas. (A) TLS. (B) Autodesk Remake

142 | Página

<!-- p. 143 -->

COMPARACIÓN DE TLS Y FOTOGRAMETRÍA SFM PARA EL MODELADO 3D DE
ARTE RUPESTRE Y LA APLICACIÓN DEL REALCE RADIANCE SCALING SHADER
PARA LA DETECCIÓN DE GRABADOS

Costes y tiempos
La Tabla 1 muestra los costes y resultados del procesado con la
técnica TLS y los flujos de trabajo fotogramétricos analizados. Los
costes y los tiempos de trabajo de campo son considerablemente más
bajos para la fotogrametría SfM que para el TLS. Con la metodología
simple, sin GCP, el tiempo de campo es notablemente inferior al flujo
de trabajo de fotogrametría profesional con GCP. Los costes de
Remake son para licencias anuales, pero este software ofrece la
posibilidad de adquirir una licencia mensual, que podría ser una opción
adecuada para muchos profesionales y no expertos la técnica. El coste
de la cámara utilizada en este trabajo es de aproximadamente 300 €.
Con TLS, el tiempo de georreferenciación, es la suma del tiempo de las
tareas de colocación de las esferas y el procesado de la alineación de
los de escaneo, mientras que en el procesado fotogramétrico, el tiempo
es la suma de las tareas de colocar y medir las dianas en campo y su
marcado en el software en oficina. El tiempo de georreferenciación en
el flujo de trabajo SfM simple es el tiempo de escalado con una
distancia de referencia y orientación a partir de una plomada y una
brújula.

143 | Página

<!-- p. 144 -->

SIMÓN PEÑA VILLASENÍN

Tabla 1. Comparación de costes, tiempos y resultados del procesado

Software SfM Software TLS Profesional SfM CC

Faro Focus3D X Indicador Pix4D PhotoScan Remake 130

Coste de
software y 20000 6800 3800 300 anual
hardware ($)
Tiempo de
trabajo en 120 40 40 40
campo

Tiempo de
referenciado 50 80 80 10
(minutos)

Tiempo de
procesado 4 6 6 5
(horas)

Nº de puntos 9,5 10 3,5 3,5 (millones)

Nº de
triángulos 8 10 9,5 7,5
(millones)

Precisión geométrica
Una diferencia significativa en el flujo de trabajo del software
fotogramétrico es que tanto PIX4D como PhotoScan permiten la
introducción de GCP en las fotos que intervienen en el ajuste
fotogramétrico. Sin embargo, Remake solo nos permite introducir
puntos en el modelo que reajustan su posición en el espacio pero no
influyen en la calibración de la cámara. Por lo tanto, dado que los GCP
en Remake no se utilizan en el ajuste, sus resultados de precisión son
menos seguros. Se espera que la marcación de los puntos en todas las
fotos en el software de escritorio sea más precisa, ya que esto influye
en el ajuste, pero el procedimiento es más tedioso que utilizar los
marcados en la malla, como se requiere en Remake. En el caso de la
búsqueda de un método ágil para los profesionales de la arqueología,
el uso de Remake como software de procesado, el escalado en base a

144 | Página

<!-- p. 145 -->

COMPARACIÓN DE TLS Y FOTOGRAMETRÍA SFM PARA EL MODELADO 3D DE
ARTE RUPESTRE Y LA APLICACIÓN DEL REALCE RADIANCE SCALING SHADER
PARA LA DETECCIÓN DE GRABADOS

una medida de referencia y la orientación en base a una plomada y una
brújula, puede ser el procedimiento más oportuno.
En esta etapa, el modelo obtenido con el software Remake se aísla
para su comparación con el modelo del TLS. El modelo obtenido con
este software fue elegido por sus costes más bajos, su simplicidad de
uso y su naturaleza de computación “en la nube” que permite el uso de
un PC de bajo rendimiento, lo que lo convierte en un software
particularmente interesante para profesionales y aficionados de la
arqueología. Además, si la precisión de la malla de Remake es
suficiente para la documentación de arte rupestre, sus resultados
pueden extrapolarse al software de escritorio, que se espera que sea
más preciso.
El análisis muestra que en torno al 90% de la superficie del
afloramiento, las diferencias entre las mallas no superan los 2 mm. La
Tabla 2 muestra los resultados estadísticos de la alineación del TLS y
la malla de fotogrametría. El RMS muestra que a pesar de un error
máximo alto de 11 cm en las zonas marginales, los resultados de ambas
mallas son similares. El error máximo y la media se calculan de forma
independiente en función de los valores positivos y negativos.3

Tabla 2. Resultados estadísticos de la alineación de mallas

Error máximo +0,117 / -0,094
Media +0,001 / -0,002m

RMS 0,002 m.

Desv. estándar 0,001 m.

Incluso cuando se escanea desde cinco posiciones, la malla final
generada a partir del TLS tiene huecos debido a la forma de la piedra
que causa áreas ocultas (Figura 3-A). Para detectar grabados en zonas
verticales, el TLS captura las mediciones perpendiculares a la
superficie y obtiene excelentes resultados. Sin embargo, este gran

145 | Página

<!-- p. 146 -->

SIMÓN PEÑA VILLASENÍN

rendimiento no es habitual con muestras de arte rupestre gallego que
normalmente se encuentran en afloramientos horizontales de baja
altura. En dicha situación, la recopilación de datos es complicada para
el TLS, ya que es necesario realizar tomas oblicuas a la superficie de la
roca.

Calidad visual
Como se muestra en la Figura 3, la textura y el color del modelo
de fotogrametría SfM (Figura 3-B) tienen mejor contraste que el
obtenido por TLS (Figura 3-A). Este resultado era el esperado ya que
las fotografías del proceso fotogramétrico se toman con una
orientación más perpendicular y más cercana al afloramiento que las
tomadas por el TLS, que está más limitado en su posicionamiento ya
que utiliza exclusivamente las fotografías de 360 ° con resolución de
100 MPx en total, que captura desde los 5 puntos de escaneo
exclusivamente. Este aspecto es importante ya que una textura
satisfactoria de la piedra puede ser útil para estudios de conservación.

146 | Página

<!-- p. 147 -->

COMPARACIÓN DE TLS Y FOTOGRAMETRÍA SFM PARA EL MODELADO 3D DE
ARTE RUPESTRE Y LA APLICACIÓN DEL REALCE RADIANCE SCALING SHADER
PARA LA DETECCIÓN DE GRABADOS

Figura 4. Cuatro ejemplos de documentación de los grabados del Castriño de
Conxo. (A) Fotografía digital realizada por miembros del Colectivo A Rula. (B)
Frotagge realizado por A. de la Peña-Santos (1979). (C) Modelo TLS. (D) Modelo
de fotogrametría SfM.

147 | Página

<!-- p. 148 -->

SIMÓN PEÑA VILLASENÍN

Potencial en la detección de grabados
No se observan diferencias significativas entre los resultados
obtenidos con la malla 3D de Remake (Figura 4-D) y la malla TLS
(Figura 4-C), pero la fotogrametría ofrece resultados con menos ruido
después de la aplicación de los renderizados Radiance Scaling. Esto se
atribuye a los posibles errores en la combinación de escaneos. La
Figura 4-A es una fotografía digital obtenida con luz artificial, que
también proporciona resultados satisfactorios. La Figura 4-B muestra
una documentación utilizando la técnica tradicional de Frotagge la
cual no detecta tantos grabados como el modelo fotogramétrico.

Resultados de los experimentos
En el primer experimento, en un solo día de campo, fue posible
documentar un total de 20 petroglifos de distinta tipología. Los
resultados de la documentación de 4 de los 20 elementos junto con la
disposición fotográfica utilizada en ellos se muestran en la Figura 5. La
metodología ha sido realmente eficiente debido a las indicaciones de
los colaboradores locales para la ubicación de los petroglifos y la
agilidad de la técnica empleada, la cual permite ejecutar una
documentación masiva en un área con afluencia de arte rupestre. En el
segundo experimento, voluntarios no expertos en fotogrametría
realizaron la documentación geométrica de petroglifos no
documentados hasta la fecha o cuya documentación estaba incompleta.
El experimento muestra que la metodología simple es accesible para
los no expertos en esta técnica.

148 | Página

<!-- p. 149 -->

COMPARACIÓN DE TLS Y FOTOGRAMETRÍA SFM PARA EL MODELADO 3D DE
ARTE RUPESTRE Y LA APLICACIÓN DEL REALCE RADIANCE SCALING SHADER
PARA LA DETECCIÓN DE GRABADOS

Figura 5. Experimento 1, disposición fotográfica y resultados finales.

149 | Página

<!-- p. 150 -->

SIMÓN PEÑA VILLASENÍN

Conclusiones
La principal conclusión de este estudio es que con una técnica de
fotogrametría simple que es accesible para perfiles no técnicos y que
tiene un gran rendimiento en términos de tiempo de ejecución y coste,
se obtuvieron resultados que mejoraron los obtenidos con TLS para la
documentación de un petroglifo con geometría compleja.
La comparación muestra que la fotogrametría es una alternativa
más avanzada, ya que permite obtener resultados precisos con modelos
sin agujeros, con mejores texturas y con mejor detección de grabados
en relación con los obtenidos con el TLS. El tiempo de trabajo con
fotogrametría SfM es mucho menor que con el TLS, y varios equipos
pueden trabajar simultáneamente a bajos costes. La comparación de
precisión geométrica muestra que las diferencias entre ambas mallas
en el área de estudio son menores de 2 mm. Por lo tanto, la
fotogrametría SfM simple puede considerarse geométricamente
cercana al TLS.
Los experimentos realizados en este estudio muestran el
rendimiento y la accesibilidad de la técnica. Es posible que a través de
metodologías simples de fotogrametría SfM, se pueda lograr la
documentación de un gran número de elementos en un solo día de
trabajo de campo, como se muestra en el primer experimento. Además,
esta técnica es accesible para todos con un mínimo de instrucción,
como se muestra en el segundo experimento. Solo se necesita una
cámara convencional para realizar una documentación con la calidad
suficiente para un análisis geométrico del arte rupestre, y debido a la
colaboración social altruista, es posible que se puedan llevar a cabo
futuras campañas de documentación masiva de varias rocas que de otra
forma no serían documentable por razones técnicas y económicas y que
requeriría pericia profesional.
Además, en este estudio, se realizó un análisis de los grabados con
los renderizados Radiance Scaling tanto en el modelo obtenido con
TLS como con fotogrametría. Los resultados muestran que esta técnica
representa una alternativa potencialmente superior a la de las
metodologías tradicionales en ambos casos. La fotogrametría muestra
resultados ligeramente mejores que el TLS después de la aplicación de

150 | Página

<!-- p. 151 -->

COMPARACIÓN DE TLS Y FOTOGRAMETRÍA SFM PARA EL MODELADO 3D DE
ARTE RUPESTRE Y LA APLICACIÓN DEL REALCE RADIANCE SCALING SHADER
PARA LA DETECCIÓN DE GRABADOS

este tratamiento. Otros realces, como el DStretch utilizado en (Le
Quellec et al., 2015), que se utiliza más a menudo en pinturas rupestre,
puede ser efectivo para grabados, sería conveniente realizar un análisis
en profundidad del funcionamiento de estos métodos de postprocesado y evaluar su potencial en el contexto de otros ejemplos de
arte rupestre.

151 | Página

<!-- p. 152 -->



<!-- p. 153 -->

COMPARACIÓN DE TLS Y FOTOGRAMETRÍA SFM PARA EL MODELADO 3D DE
ARTE RUPESTRE Y LA APLICACIÓN DEL REALCE RADIANCE SCALING SHADER
PARA LA DETECCIÓN DE GRABADOS

MATERIAL SUPLEMENTARIO

Suplemento 1. Perfiles del afloramiento.

153 | Página

<!-- p. 154 -->

SIMÓN PEÑA VILLASENÍN

.

Suplemento 2. Análisis de resultados de la alineación de las mallas de TLS y
fotogrametría.

154 | Página

<!-- p. 155 -->

COMPARACIÓN DE TLS Y FOTOGRAMETRÍA SFM PARA EL MODELADO 3D DE
ARTE RUPESTRE Y LA APLICACIÓN DEL REALCE RADIANCE SCALING SHADER
PARA LA DETECCIÓN DE GRABADOS

Suplemento 3. Captura de alta resolución de la malla obtenida con fotogrametría SfM y
la aplicación del pluging Radiance Scaling de Meshlab, Castriño de Conxo.

155 | Página

<!-- p. 156 -->

SIMÓN PEÑA VILLASENÍN

Suplemento 4. Resultados finales de los restantes elementos del experimento 1.

156 | Página

<!-- p. 157 -->

COMPARACIÓN DE TLS Y FOTOGRAMETRÍA SFM PARA EL MODELADO 3D DE
ARTE RUPESTRE Y LA APLICACIÓN DEL REALCE RADIANCE SCALING SHADER
PARA LA DETECCIÓN DE GRABADOS

Suplemento 4. Resultados finales de los restantes elementos del experimento 1.

157 | Página

<!-- p. 158 -->

SIMÓN PEÑA VILLASENÍN

Suplemento 5. Resultados finales del experimento 2. (3) Monte Castelo, Ames.
(4) Pedra da Grada, Moraña (5) O Pumariño, Brión. (6) Cortellos, Santiago de
Compostela. (7) Pedrouzos, Vimianzo. (8) Chan das Lamas, A Estrada.

158 | Página

<!-- p. 159 -->

COMPARACIÓN DE TLS Y FOTOGRAMETRÍA SFM PARA EL MODELADO 3D DE
ARTE RUPESTRE Y LA APLICACIÓN DEL REALCE RADIANCE SCALING SHADER
PARA LA DETECCIÓN DE GRABADOS

Suplemento 5. Resultados finales del experimento 2. (3) Monte Castelo, Ames.
(4) Pedra da Grada, Moraña (5) O Pumariño, Brión. (6) Cortellos, Santiago de
Compostela. (7) Pedrouzos, Vimianzo. (8) Chan das Lamas, A Estrada.

159 | Página

<!-- p. 160 -->

SIMÓN PEÑA VILLASENÍN

Suplemento 5. Resultados finales del experimento 2. (3) Monte Castelo, Ames.
(4) Pedra da Grada, Moraña (5) O Pumariño, Brión. (6) Cortellos, Santiago de
Compostela. (7) Pedrouzos, Vimianzo. (8) Chan das Lamas, A Estrada.

160 | Página

<!-- p. 161 -->

CAPITULO IV

\8. CAPITULO IV

UNA METODOLOGÍA DE TRABAJO SIMPLE Y
DE BAJO COSTE AL ALCANCE DE
MÚLTIPLES PERFILES PARA EL MODELADO
3D Y VECTORIZACIÓN AUTOMATIZADA DE
GRABADOS DE ARTE RUPESTRE
“ATLÁNTICO”

RESUMEN:
En los últimos años, el modelado 3D con fotogrametría y los
métodos de realce originarios en las comunidades de gráficos por
ordenador se han utilizado con excelentes resultados para estudios de
grabados de arte rupestre. Sin embargo, la mayoría de los elementos
del arte rupestre “Atlántico” en la Península Ibérica aún no se han
documentado geométricamente. Los objetivos de este estudio incluyen
profundizar en la aplicación de la fotogrametría Structure from Motion
(SfM), en el post-procesado digital de la información 3D y en las
herramientas de difusión online disponibles actualmente,
determinando un flujo de trabajo que sea accesible para los
investigadores, profesionales y aficionados de este patrimonio,
permitiendo la documentación de este fenómeno de un modo masivo.
Por ello, en este estudio se obtuvieron los modelos 3D de una muestra
representativa del arte rupestre “Atlántico” utilizando una metodología
de fotogrametría SfM simple y se muestra un flujo de trabajo

161 | Página

<!-- p. 162 -->

SIMÓN PEÑA VILLASENÍN

optimizado para el realce y obtención de los resultados vectoriales
finales. Este estudio muestra el gran potencial del flujo de trabajo
propuesto para obtener interpretaciones 2D objetivas además de la
publicación directa de modelos 3D realzados, que actualmente es
posible con plataformas como Sketchfab, eliminando los posibles
errores interpretativos derivados de la proyección de información 3D
en un formato 2D. Esta posibilidad en combinación con un flujo de
trabajo de fotogrametría SfM simple y de bajo coste puede sentar las
bases de una catalogación masiva colaborativa de este patrimonio.

162 | Página

<!-- p. 163 -->

UNA METODOLOGÍA DE TRABAJO SIMPLE Y DE BAJO COSTE AL ALCANCE DE
MÚLTIPLES PERFILES PARA EL MODELADO 3D Y VECTORIZACIÓN
AUTOMATIZADA DE GRABADOS DE ARTE RUPESTRE “ATLÁNTICO”

Introducción
La documentación geométrica es una parte importante de las tareas que
engloba la protección del patrimonio. La evolución de los estudios de
arte rupestre se caracteriza por la búsqueda continua de técnicas de
registro confiables y precisas. En concreto, para la documentación
geométrica de grabados de arte rupestre, se han utilizado
tradicionalmente diferentes métodos, como el dibujo a mano alzada, el
Frotagge, el calco sobre plástico o la fotografía nocturna (Arcà, 2006;
González-Aguilera et al., 2009; Lewis-Williams & Pager, 1990;
Moneva Montero, 1993). Su ejecución además de tediosa, en algún
caso puede ser agresiva con el elemento al requerir contacto directo
con este. Actualmente, el uso de técnicas de adquisición de datos,
provenientes de la ingeniería, como el escáner láser terrestre (TLS)
(Arayici, 2007; Brumana et al., 2014; Jim H. Chandler et al., 2007;
McPherron et al., 2009; Simpson et al., 2004) o la fotogrametría
Structure from Motion (SfM) (Jalandoni et al., 2018; López et al., 2016;
Meijer, 2015), están creciendo en popularidad en el sector patrimonial.
Ambas metodologías se basan en la obtención de modelos 3D de alta
resolución, hasta varios puntos por mm2, que permiten la
documentación de la geometría compleja y el color de los elementos
de patrimonio (Grussenmeyer et al., 2012; Remondino & El-Hakim,
2006; De Reu et al., 2013a; Yilmaz et al., 2007). Además, ni la
fotogrametría SfM ni la tecnología TLS, tienen las limitaciones
asociadas con las técnicas tradicionales, en cuando a que son agresivas,
limitadas en precisión o consumen mucho tiempo (Díaz-Andreu et al.,
2006). Aunque ambas técnicas se utilizan ampliamente, la inversión
requerida para el modelado 3D con fotogrametría SfM es
significativamente menor que con TLS, y la adaptación de esta técnica
a las geometrías complejas de los afloramientos rocosos suele ser mejor
que con el TLS (Peña-Villasenín et al., 2018). Esta adaptación a las
tareas de documentación de grabados se debe en parte a que la
fotogrametría SfM tiene una amplia variabilidad metodológica, lo que
le permite ejecutarse con flujos de trabajo simples. La adquisición de
datos mediante esta tecnología es relativamente fácil de aprender y
además el software fotogramétrico es de uso sencillo dado el alto grado
de automatización del proceso.

163 | Página

<!-- p. 164 -->

SIMÓN PEÑA VILLASENÍN

La fotogrametría es una técnica con una larga trayectoria que ha
experimentado importantes avances con la aparición de los algoritmos
de Structure from Motion (SfM). Los orígenes de la fotogrametría SfM
se encuentran en la comunidad de visión artificial (Furukawa et al.,
2010; Spetsakis & Aloimonos, 1991) y en el desarrollo de los
algoritmos automáticos de emparejamiento de características (Harris &
Stephens, 1988; Otto & Chau, 1989). En la fotogrametría SfM, la
posición de la cámara y la geometría de la escena se reconstruyen
simultáneamente a través de la identificación automática de las
características coincidentes (Chandran et al., 1997). Estas
características permiten realizar estimaciones iniciales de las
posiciones de la cámara y las coordenadas del objeto, que luego se
refinan de forma iterativa utilizando una minimización no lineal de
mínimos cuadrados. El sistema de ajuste Bundler (Snavely et al., 2008)
se utiliza para esta tarea. Posteriormente, se puede obtener una nube de
puntos de mayor densidad utilizando los algoritmos Clustering view
for Multiview Stereo (CMVS) y Patch-based Multiview Stereo
(PMVS2) (Furukawa et al., 2010; Furukawa & Ponce, 2010). La
aparición de estas técnicas nos ha permitido trabajar con superficies
complejas (Barazzetti et al., 2011) y obtener nubes de puntos, mallas
de triángulos y, finalmente, un modelo texturizado tridimensional
completo (Westoby et al., 2012). Una gama de motores de procesado
en la nube, especialmente Photosynth (Microsoft Corporation, USA)
han popularizado la técnica SfM (Snavely et al., 2008). Se desarrollaron
servicios gratuitos de computación en la nube, como 123D Catch
(Autodesk Inc., USA.) (Lavy et al., 2015), ARC3D (Ku Leuven,
Bélgica) (Tingdahl & Van Gool, 2011), y Recap Photo (Autodesk Inc.,
USA) (Eulitz & Reiss, 2015; Greif et al., 2017), así como software de
escritorio profesional como PhotoScan (Agisoft LLC., Rusia) (De Reu
et al., 2013a), Pix4D (EPFL, Suiza) (Turner et al., 2014), entre otros.
Esta técnica es fácilmente asimilable por perfiles no expertos
como se muestra en estudios en numerosos campos como en el del
diseño (Borysenko, 2018), en la medicina (Grant et al., 2019; Koban et
al., 2014; Mahmoud & Bennett, 2015; Salazar-Gamarra et al., 2016),
en biología (Gutierrez-Heredia et al., 2016; Lavy et al., 2015), en
geología (Chidburee et al., 2016; Micheletti et al., 2015) en educación

164 | Página

<!-- p. 165 -->

UNA METODOLOGÍA DE TRABAJO SIMPLE Y DE BAJO COSTE AL ALCANCE DE
MÚLTIPLES PERFILES PARA EL MODELADO 3D Y VECTORIZACIÓN
AUTOMATIZADA DE GRABADOS DE ARTE RUPESTRE “ATLÁNTICO”

(Mills, 2015), en arquitectura (Peña-Villasenín et al., 2017) en esdios
de patrimonio (Uygun et al., 2016) y concretamente en petroglifos
(Jim; Chandler & Fryer, 2013; José L. Lerma et al., 2014).
Los modelos 3D de fotogrametría son de forma evidente útiles
para el estudio geométrico de petroglifos, pero a pesar de la utilidad de
los mismos, debido a la sinuosidad de los grabados, todavía es
necesario utilizar algún método de realce para obtener una mejor
visualización de los grabados. Una posibilidad de realce es la
generación de sombras relevantes basadas en la modificación de puntos
de iluminación virtuales en el modelo 3D, como se muestra en (Mudge
et al., 2006). Otra posibilidad es la magnificación de los ejes
perpendiculares del objeto (eje Z), como se describe en (Ortiz-Sanz et
al., 2010). La utilización de otros métodos más avanzados, como
Reflectance Transformation Imaging (RTI) (Díaz-Guardamino & D,
2013; Domingo et al., 2013; Duffy et al., 2013; Earl et al., 2010; Mudge
et al., 2006, 2012), que se basan en un análisis del cambio del punto de
iluminación en una colección de fotos, supuso un avance importante en
el análisis de grabados de arte rupestre. En los últimos años, otros flujos
de trabajo originados en la comunidad de gráficos por computadora
(Pires et al., 2015; Saito & Takahashi, 1990), en concreto los
renderizados Radiance Scaling, que se basan en el análisis morfológico
de los modelos 3D como se describe en (Vergne et al., 2010, 2018) y
utilizado para la detección de grabados en (Carrero-Pazos et al., 2012;
López-Menchero Bendicho et al., 2017; Medici & Rossi, 2015), han
demostrado un gran potencial para esta tarea. El software Meshlab
(Visual Computing Lab, ISTI-CNR, Italy), (Vergne et al., 2018) y
Xshade (exaggerated shading for depicting shape and detail)
(Rusinkiewicz et al., 2006) permiten realzar los modelos 3D con
resultados similares. Además, el estudio directo de modelos 3D es
actualmente posible de modo online, como se muestra en plataformas
como Sketchfab o 3DHOP (Potenziani et al., 2015; Scopigno et al.,
2017).

A pesar de los realces y las herramientas de publicación online
citadas, todavía se demanda una vectorización esquemática de los

165 | Página

<!-- p. 166 -->

SIMÓN PEÑA VILLASENÍN

grabados para facilitar el estudio y la interpretación. Para lograr la
objetividad metodológica en este paso, se recomienda que la
vectorización de las capturas ráster sea automática. La vectorización
automática de imágenes, como Edge Detector en pinturas rupestres, se
muestra en (Clogg et al., 2000; Harmon, 2008; Mark & Billo, 2002;
Mas Cornellà et al., 2010), donde se analizan diferentes técnicas como
Decorrelation Stretch para la vectorización automática de pinturas
rupestres a partir de imágenes digitales; Las técnicas de vectorización
automática también se utilizan en grabados en roca, como se muestra
en (Ortiz-Sanz et al., 2010). Recientemente, se describe un tratamiento
previo de capturas 2D basadas en subexposición y sobreexposición de
la captura, generando un resultado que mejora y facilita la
vectorización posterior (Carrero-Pazos et al., 2018), la cual se puede
completar fácilmente usando recursos online gratuitos como
Vectorizer (Massow, 2015), Online-Convert o Vector Magic (Godfrey
& Eveleth, 2015; Lacroix, 2009).
Aunque los avances técnicos citados anteriormente han supuesto
un avance importante en la tarea de documentación, el inventario
geométrico del arte rupestre continúa presentando muchos desafíos
debido a la gran cantidad de petroglifos presentes en el territorio.
Actualmente, solo en Galicia, como se muestra en (Rodríguez Rellán
et al., 2018), se han localizado más de 3000 petroglifos; por lo tanto, la
documentación masiva de este fenómeno del patrimonio no es factible
por razones técnicos y económicas, y al mismo tiempo, la protección
del mismo es altamente necesaria debido al gran riesgo de deterioro
que presentan debido a la exposición total a agentes externos. Por ello,
es necesario continuar profundizando en la comprensión y el en uso de
técnicas de documentación con gran objetividad, como la
fotogrametría, en sus variantes simples y de bajo coste, así como en los
renderizados Radiance Scaling y en las aplicaciones de vectorización
automática. Los estudios citados anteriormente han demostrado la
eficacia de estas técnicas y su uso es ya un hecho. Sin embargo, para
obtener modelos en 3D, generalmente se proponen metodologías
fotogramétricas complejas que requieren el uso de dispositivos
topográficos, software de pago, drones, postes o cámaras especificas,
equipos que no suelen ser accesibles a perfiles no especializados.

166 | Página

<!-- p. 167 -->

UNA METODOLOGÍA DE TRABAJO SIMPLE Y DE BAJO COSTE AL ALCANCE DE
MÚLTIPLES PERFILES PARA EL MODELADO 3D Y VECTORIZACIÓN
AUTOMATIZADA DE GRABADOS DE ARTE RUPESTRE “ATLÁNTICO”

Además, las variables de configuración posibles en el uso de realces
son extensas, así como de las herramientas de vectorización
automática. También es importante profundizar la comprensión y en el
uso de aspectos como los tratamientos de malla previos a los realzados,
así como el comportamiento de los tratamientos sobre diferentes tipos
de materiales rocosos o tipos de grabado. Además, es posible la
difusión online de los modelos 3D para su difusión científica mundial.
Es por ello que en este estudio, se evalúan diferentes variables de
configuración del realce de modelos 3D fotogramétricos y distintas
posibilidades para su difusión de los mismos, sobre una muestra
representativa de arte rupestre “Atlántico”. Se propone y testea un flujo
de trabajo muy simple, accesible a perfiles no expertos, que permite la
documentación y difusión de este fenómeno patrimonial de un modo
masivo.

Metodología
La tipología de petroglifos del arte rupestre “Atlántico” es muy amplia
e incluye formas predominantemente geométricas con trazos largos,
formas naturalistas con trazos cortos y cavidades circulares (Bradley et
al., 1994; Bradley & Fábregas-Valcarce, 1998). Para este estudio, se
eligen varios petroglifos como muestras representativas de los tipos de
grabado y soporte de roca comunes. A continuación se muestra la
ubicación de estos petroglifos, la metodología de fotogrametría SfM
empleada para generar los modelos 3D, los post-tratamientos de la
malla, los post-tratamientos digitales 2D, la vectorización automática
y el flujo de publicación online de los modelos.

Localización
Los ejemplos de arte rupestre de este estudio se ubican para el caso
1 en el norte de Portugal y los casos 2 a 7 en Galicia. El caso 1 es el
petroglifo (PT) de Fontão do Eido (en Verdoejo, Valença do Minho),
que fue elegido para el análisis principal debido a su variedad de
grabados, incluyendo zoomorfos, figuras geométricas, cazoletas,
líneas, elipses, etc. Los otros casos de estudio se relacionan a

167 | Página

<!-- p. 168 -->

SIMÓN PEÑA VILLASENÍN

continuación: PT de Pedra da Grada, Moraña (Caso 2), PT de Pedra
da Loba, Ames (Caso 3), PT de Peneda Negra, Ames (Caso 4), PT de
Outeiro dos Furados, Muros (Caso 5), PT de A Fieiteira, Ponteceso
(Caso 6) y PT de O Castriño de Conxo, Santiago de Compostela (Caso
7). Las ubicaciones de todos los casos se muestran en la Figura 1.

Figura 1. Localización de los ejemplos de arte rupestre estudiados.

168 | Página

<!-- p. 169 -->

UNA METODOLOGÍA DE TRABAJO SIMPLE Y DE BAJO COSTE AL ALCANCE DE
MÚLTIPLES PERFILES PARA EL MODELADO 3D Y VECTORIZACIÓN
AUTOMATIZADA DE GRABADOS DE ARTE RUPESTRE “ATLÁNTICO”

Materiales
Para el modelado 3D con fotogrametría SfM, en la toma
fotográfica, se utilizaron diferentes cámaras convencionales y de
SmartPhone. Para el procesado SfM, se utilizó el software Recap Photo
en todos los casos. Los modelos se importaron en Meshlab y las
capturas en 2D se trataron en GIMP (Programa de manipulación de
imágenes de GNU). La vectorización automática se realizó en el
servicio online Vectorizer.io (Massow, 2015) y Sketchfab se utilizó
como plataforma para la publicación online de los modelos 3D. Todos
los programas utilizados son gratuitos para fines no lucrativos. A
continuación se muestran los flujos de trabajo probados y el software
utilizado en cada paso.

• Para la obtención del calco vectorial:

Suavizado de
Modelado 3D la malla, Post-
SfM aplicación del tratamiento Vectorización
(100 imagenes realce y digital de automática
max.) obtención de imagen (Vectorizer.io)
capturas(Recap Photo) (GIMP)
(Meshlab)

• Para el estudio y difusión online en 3D:

Modelado 3D Carga en la Simplificación Publicación SfM y de la malla plataforma del modelo(100 imágenes configuración del (50 Mb Max. ) realce 3D realzado max.)
(Meshlab) (Sketchfab) (Sketchfab) (Recap Photo)

169 | Página

<!-- p. 170 -->

SIMÓN PEÑA VILLASENÍN

Modelado 3D con fotogrametría SfM.
Para obtener un modelo 3D de los casos de estudio, se empleó una
metodología simple de toma fotográfica. Se utilizaron cámaras
convencionales para obtener imágenes oblicuas a aproximadamente 45
grados verticalmente, describiendo un círculo alrededor del elemento.
En general, las imágenes deben tomarse consecutivamente sin cambios
en la perspectiva de más de 15 grados horizontalmente. Siempre que
sea posible, todas las superficies de roca deben cubrirse desde
múltiples perspectivas, ya que la disposición fotográfica debe
adaptarse a las particularidades de cada caso. Si el elemento tiene
grandes dimensiones, se recomiendan varias pasadas longitudinales en
el afloramiento en ambas direcciones de avance. Otras técnicas
topográficas complementarias no son necesarias si el modelo está
escalado por una o más mediciones de referencia. Estas indicaciones
se proporcionaron a un grupo de investigadores aficionados del arte
rupestre, y estos completaron la fase de adquisición de datos en el
campo para todos los casos de estudio y, por lo tanto, se utilizaron
diferentes cámaras en cada uno de ellos. No se utilizó trípode y se
emplearon un máximo de 100 imágenes por caso de estudio.

Tratamiento de realce de los modelos 3D
Las mallas obtenidas en la etapa anterior se importaron al software
Meshlab para la aplicación del realce del grabado. En primer lugar, se
analiza la aplicación de una luz lateral virtual. Por otro lado, debido a
la textura granular de la piedra y los posibles errores del modelo 3D, el
suavizado de la malla antes de la aplicación del realce puede mejorar
los resultados de detección de grabado. Meshlab permite la aplicación
de diferentes métodos de suavizado; en este caso, se aplicó el suavizado
Laplacian Smooth a las mallas originales para evaluar cómo esta
técnica de suavizado afecta sobre el resultado final. Posteriormente, se
aplicaron diferentes opciones de aplicación de realce, en primer lugar
el renderizado Minnaert (Ganovelli et al., 2014), sobre el cual se
aplicaron diferentes intensidades de iluminación.
A continuación, se utilizaron los renderizados Radiance Scaling.
Hay cuatro opciones posibles en la aplicación de esta realce, que se

170 | Página

<!-- p. 171 -->

UNA METODOLOGÍA DE TRABAJO SIMPLE Y DE BAJO COSTE AL ALCANCE DE
MÚLTIPLES PERFILES PARA EL MODELADO 3D Y VECTORIZACIÓN
AUTOMATIZADA DE GRABADOS DE ARTE RUPESTRE “ATLÁNTICO”

describen en (Vergne et al., 2018). El renderizado Lambert Radiance
Scaling se muestra de forma predeterminada. En este renderizado, la
disposición del punto de luz tiene influencia en la apariencia, por lo
que se obtuvieron diferentes capturas considerando este aspecto. A
continuación se testea el realce Lit Sphere Radiance Scaling, Colored
Descriptor y Grey Descriptor; En estos casos, la disposición del punto
de iluminación no influye en el resultado. Particularmente, en el realce
Lit Sphere Radiance Scaling (Sloan et al., 2001) codifica el entorno de
iluminación y las propiedades de reflexión sobre una imagen de una
esfera (Figura 4-A). Para mejorar aún más la legibilidad, en este caso
se puede configurar la esfera iluminada para las regiones convexas y
cóncavas, y es posible cargar otras esferas iluminadas personalizadas.
Los colores blanco y negro se cargaron como esferas para obtener el
mayor contraste posible (Figura 4-B).

171 | Página

<!-- p. 172 -->

SIMÓN PEÑA VILLASENÍN

Figura 4. Menú de configuración del renderizado Lit Sphere Radiance Scaling
Shader (A) Esferas por defecto (B) Colores negro y blanco cargados como
esferas.

Con respecto al renderizado Grey Descriptor, en el que
simplemente se realza la curvatura para cada posición del objeto, y con
respecto a Colored Descriptor, en el que las convexidades y
concavidades se muestran con dos colores distintos (azul y rojo), solo
el parámetro transition es configurable.
Después de aplicar cada una de las opciones de realce
mencionadas anteriormente, se realizaron capturas de los resultados
desde la perspectiva superior utilizando la herramienta Snapshot. Esta
herramienta permite la configuración del factor multiplicador de la

172 | Página

<!-- p. 173 -->

UNA METODOLOGÍA DE TRABAJO SIMPLE Y DE BAJO COSTE AL ALCANCE DE
MÚLTIPLES PERFILES PARA EL MODELADO 3D Y VECTORIZACIÓN
AUTOMATIZADA DE GRABADOS DE ARTE RUPESTRE “ATLÁNTICO”

resolución de la imagen cuando se exporta esta captura, en este sentido,
también se probaron diferentes valores de calidad de exportación.

Post-tratamiento digital 2D
La técnica descrita en (Carrero-Pazos et al., 2012) se aplica en a
los archivos ráster obtenidos como resultado del paso anterior. Esta
técnica, consiste en oscurecer y aclarar la imagen mediante las
herramientas del software Photoshop, con la diferencia que en este
caso se utilizó GIMP como una opción de software libre para esta tarea.

Vectorización automática
Posteriormente, se aplicó un tratamiento de vectorización
automático a las capturas dando lugar a los productos vectoriales
finales. Debido a la facilidad de uso y la posibilidad de configurar
diferentes variables en esta vectorización, se utilizó el servicio online
gratuito Vectorizer (Massow, 2015). En este servicio, es posible
seleccionar diferentes parámetros de configuración, como el número
de colores a segmentar, la agrupación de colores (tolerancia), el área
mínima en número de píxeles, el desenfoque y varias opciones para el
fondo, como se muestran en la Figura 5.

173 | Página

<!-- p. 174 -->

SIMÓN PEÑA VILLASENÍN

Figura 5. Configuraciones del servicio online de vectorización automática
Vectorizer.io.

174 | Página

<!-- p. 175 -->

UNA METODOLOGÍA DE TRABAJO SIMPLE Y DE BAJO COSTE AL ALCANCE DE
MÚLTIPLES PERFILES PARA EL MODELADO 3D Y VECTORIZACIÓN
AUTOMATIZADA DE GRABADOS DE ARTE RUPESTRE “ATLÁNTICO”

Publicación online.
Finalmente, los modelos 3D fueron publicados en la plataforma
online Sketchfab aplicando el realce Skin Light Matcap, que es similar
al renderizado Lit Sphere Radiance Scaling de Meshlab en algunos
casos y Old Metal Matcap, similar a Minnaert shader en otros casos.
Para la publicación gratuita, fue necesario reducir el número de
triángulos ya que el límite de la cuenta gratuita es de 50 Mb. Se utilizó
un solo archivo en STL comprimido en formato RAR, sin textura para
conservar la mayor densidad de malla. De este modo, fue posible
cargar mallas de aproximadamente 2.5 millones de triángulos. En
algunos casos, fue necesario reducir la densidad de exportación de la
malla; en otros casos, la malla fue cortada, descartando las zonas donde
no se observaron grabados.

Resultados y discusión

Modelado 3D con fotogrametría SfM
La Tabla 1 muestra un resumen de los resultados obtenidos en las
labores de documentación:

Tabla 1. Fotogrametría SfM. Resultados del modelado 3D.
Vértices Triángulos Caso Imágenes Cámara (millones) (millones)

Caso 1 100 Canon EOS 600D - 18 Mpx 3.4 6.9

Caso 2 54 Canon EOS 600D - 18 Mpx 1.0 2.1
Caso 3 100 Olympus-E-P2 - 12 Mpx 1.5 2.9

Caso 4 100 Olympus-E-P2 - 12 Mpx 2.2 4.4

Caso 5 100 Sony-a6000 - 24 Mpx 4.0 8.1

Caso 6 54 Xiaomi MI 4I - 10 Mpx 0.8 1.5
Caso 7 100 Olympus-E-P1 - 12 Mpx 3.7 7.3

175 | Página

<!-- p. 176 -->

SIMÓN PEÑA VILLASENÍN

El factor más limitante en la publicación modelo es el tamaño, ya
que los 50 Mb de límite permiten la publicación de una malla con 2.53 millones de triángulos, mientras que la metodología fotogramétrica
sencilla y de bajo coste utilizada permite obtener mallas que exceden
este límite en la mayoría de los casos. La Figura 6 muestra el modelo
3D obtenido en el Caso 1 y la disposición de la foto utilizada. Esta
figura muestra que la técnica de disposición de toma fotográfica es
flexible y permite la adaptación a las particularidades de cada
elemento. En este caso, la disposición de las fotos obtenidas por el
colaborador no experto, no se adapta exactamente a la metodología
recomendable para la sesión de fotos, no obstante, el software pudo
correlacionar las imágenes y obtener resultados válidos para un análisis
objetivo de los grabados. Los demás casos de estudio también
mostraban desajustes similares en la disposición de toma fotográfica,
pero el software Recap Photo también pudo correlacionar las imágenes
en todos los casos.
Cabe señalar que a los colaboradores aficionados que participaron
en este estudio con conocimientos previos de manejo de cámaras
fotográficas, no les resultó difícil asimilar las tareas necesarias para la
toma de datos fotogramétrica, por otro lado, aquellos que carecían de
experiencia en el manejo de cámaras fotográficas presentaron más
dificultades de aprendizaje, aunque esto fúe fácilmente solventable en
la mayoría de casos, empleando los modos automáticos de las cámaras
digitales, sin tener una influencia significante en los resultados. Por
otro lado, los colaboradores no experimentadas en la técnica de toma
de datos fotogramétricos, acostumbran a obtener una colección de
imágenes con un nivel de solape insuficiente para el procesado de las
mismas por SfM, por ello, es importante incidir en la necesidad de
realizar un número de fotos muy elevado y con gran solape ya que este
suele ser el error más común en no expertos. Un exceso de fotografías
siempre será solventable mientras que su insuficiencia implica la
repetición del trabajo. Otros problemas como los derivados de las
geometrías complejas de los afloramientos rocosos, en ocasiones
invadidos por la vegetación; la orientación de los mismos con respecto
al sol que impiden la realización de fotografías sin generar sombras en
la roca; o su estado de conservación en cuanto a la presencia de

176 | Página

<!-- p. 177 -->

UNA METODOLOGÍA DE TRABAJO SIMPLE Y DE BAJO COSTE AL ALCANCE DE
MÚLTIPLES PERFILES PARA EL MODELADO 3D Y VECTORIZACIÓN
AUTOMATIZADA DE GRABADOS DE ARTE RUPESTRE “ATLÁNTICO”

musgos/líquenes, sedimentos o humedades, son condicionantes
negativos en la aplicación de la técnica, pero los cuales también se
presentan en trabajos profesionales, y con los cuales aficionados y
profesionales debemos lidiar.

Figura 6. Disposición de tomas fotográficas y modelo 3D resultado del Caso 1.

Tratamiento de realce del grabado
Los resultados de la aplicación de las diferentes variables de
configuración del realce testeadas en Meshlab se muestran a
continuación. En primer lugar, en la Figura 7 se muestra el modelo con
4 direcciones de iluminación (arriba A, abajo B, izquierda C y derecha
D).

177 | Página

<!-- p. 178 -->

SIMÓN PEÑA VILLASENÍN

Figura 7. Caso 1: Modelo 3D con cuatro direcciones de iluminación (superior A,
inferior B, lateral izquierda C, y lateral derecha D).

A continuación, en la figura 8, se muestran los resultados
obtenidos con el renderizado Minnaert (Figuras 8-A y 8-B), con el
renderizado Lambert Radiance Scaling (Figura 8-C) y este mismo con
variaciones en el ángulo de iluminación (Figura 8-D), el renderizado
Lit Sphere Radiance Scaling (Figura 8-E) y el renderizado Grey
Descriptor (Figura 8-F).

178 | Página

<!-- p. 179 -->

UNA METODOLOGÍA DE TRABAJO SIMPLE Y DE BAJO COSTE AL ALCANCE DE
MÚLTIPLES PERFILES PARA EL MODELADO 3D Y VECTORIZACIÓN
AUTOMATIZADA DE GRABADOS DE ARTE RUPESTRE “ATLÁNTICO”

Figura 8. Distintas variables de configuración testeadas en Meshlab. (A)
Minnaert con intensidad de iluminación alta. (B) Minnaert con baja intensidad.
(C) Lambertian Radiance Scaling. (D) Lambertian Radiance Scaling con
iluminación lateral. (E) Lit Sphere Radiance Scaling. (F) Grey Descriptor.

Los realces en los que los puntos de luz son configurables, como
el renderizado Minnaert y Lambertian Scaling, son visualmente
atractivos pero no son útiles para un análisis objetivo de los grabados.
Por la contra, el realce Lit Sphere Radiance Scaling genera resultados
de gran objetividad. Este renderizado puede observarse con colores

179 | Página

<!-- p. 180 -->

SIMÓN PEÑA VILLASENÍN

blancos y negros en las esferas de luz (Figura 9-A) para mejorar el
contraste de los grabados. Por otro lado, en la figura 9-B, se puede
observar el mismo renderizado después de la aplicación previa del
suavizado de la malla Laplacian Smooth. Se puede observar que el
modelo suavizado mantiene los detalles del grabado que el modelo
original, eliminando parte del ruido. Este efecto positivo es más
relevante cuando el soporte sobre el que se colocan los grabados es de
grano grueso, como se muestra en las figuras 9-C y 9-D (Caso 2).
Cuando los grabados son sinuosos, como en las figuras 9-E y 9-F (Caso
3), o la malla 3D no tiene resolución suficiente (Caso 6), no es
aconsejable aplicar este suavizado porque puede generar que algunos
grabados no sean registrados.

180 | Página

<!-- p. 181 -->

UNA METODOLOGÍA DE TRABAJO SIMPLE Y DE BAJO COSTE AL ALCANCE DE
MÚLTIPLES PERFILES PARA EL MODELADO 3D Y VECTORIZACIÓN
AUTOMATIZADA DE GRABADOS DE ARTE RUPESTRE “ATLÁNTICO”

Figura 9. Lit Sphere Radiance Scaling con negro y blanco como Lit Spheres (A)
Modelo 3D realzado original. (B) Modelo 3D suavizado y realzado. (C) Bitmap del
modelo original del Caso 2 (D) Bitmap del modelo suavizado del Caso 2. (E) Bitmap
del modelo original del Caso 3. (F) Bitmap del modelo suavizado del Caso 3.

181 | Página

<!-- p. 182 -->

SIMÓN PEÑA VILLASENÍN

Las figuras 10-A y 10-B muestran las calidades de exportación
altas y bajas del Snapshot en Meshlab. En la opción de baja calidad,
los grabados se aprecian mejor.

Figura 10. Distintas calidades de exportación de capturas 2D en Meshlab.
(A) Calidad alta (B) Calidad baja.

Post-tratamiento digital
Las Figuras 11-A y 11-B muestran los resultados del mapa de bits
del Caso 1 y del Caso 4. Se utilizaron las capturas de baja calidad de la
malla suavizada, ya que este fue el flujo de trabajo que ofreció los
mejores resultados. En particular, el método de generación de mapa de
bits que implica una bajoexposición y una sobreexposición de la
captura, se puede aplicar con mayor o menor agresividad, como se
muestra en las Figuras 11-C y 11-D para el Caso 5. Aunque la Figura
11-D presenta menos ruido, los grabados se definen mejor en Figura
11-C, este aspecto introduce cierta subjetividad al proceso.

182 | Página

<!-- p. 183 -->

UNA METODOLOGÍA DE TRABAJO SIMPLE Y DE BAJO COSTE AL ALCANCE DE
MÚLTIPLES PERFILES PARA EL MODELADO 3D Y VECTORIZACIÓN
AUTOMATIZADA DE GRABADOS DE ARTE RUPESTRE “ATLÁNTICO”

Figura 11. Bitmaps resultantes. (A) Caso 1. (B) Caso 4. (C) Bitmap de alta
densidad del Caso 5. (D) Bitmap de baja densidad del Caso 5.

183 | Página

<!-- p. 184 -->

SIMÓN PEÑA VILLASENÍN

Vectorización automática
La vectorización automática del mapa de bits se genera fácilmente
después de los tratamientos anteriores. El mapa de bits y la imagen
vectorizada del Caso 6 se muestran en las Figuras 12-A y 12-B. Al
realizar la vectorización automática en los mapas de bits en lugar de en
una imagen con una resolución radiométrica más alta, la subjetividad
intrínseca a este proceso se elimina por completo.

Figura 12. Caso 6, calcos vetoriales. (A) A partir de fotogrametría SfM. (B) A
partir de técnicas tradicionales (Mañana-Borrazás & Santos-Estévez, 2002).

184 | Página

<!-- p. 185 -->

UNA METODOLOGÍA DE TRABAJO SIMPLE Y DE BAJO COSTE AL ALCANCE DE
MÚLTIPLES PERFILES PARA EL MODELADO 3D Y VECTORIZACIÓN
AUTOMATIZADA DE GRABADOS DE ARTE RUPESTRE “ATLÁNTICO”

Incluso en este caso, donde las fotos se tomaron con una cámara
de un SmartPhone, en comparación con una documentación previa de
este ejemplo de arte rupestre (Mañana-Borrazás & Santos-Estévez,
\2002) los resultados se muestran similares. Los resultados de otros
ejemplos de arte rupestre documentados en este estudio se muestran en
la Figura 13 (Caso 6).

Figura 13. Resultados de la vectorización. (A) Caso 3. (B) Caso 7.

185 | Página

<!-- p. 186 -->

SIMÓN PEÑA VILLASENÍN

Publicación online
A pesar de los intentos de preservar las mismas perspectivas
durante el proceso de obtención de las instantáneas, se observan
pequeñas diferencias, como las que se encuentran entre las Figuras 9A y 9-B. Estos cambios sutiles en la perspectiva hacen que la espiral
en la parte inferior derecha parezca ser circular en la Figura 9-A y
elíptica en la Figura 9-B. Las figuras 12-A y 12-B muestran planos
blancos de roca con diferentes orientaciones, lo que indica que las rocas
en estas figuras pueden ser malinterpretadas por no mostrarse en sus
verdaderas perspectivas. Esta diferencia indica que después de la
aplicación de realces, el formato 2D en el cual se exportan los
resultados, sigue teniendo el mismo problema que tienen los métodos
tradicionales, relacionado con el error producido cuando la
información 3D se proyecta sobre un formato 2D. Sin embargo, los
resultados de los modelos realzados se pueden observar directamente
en formato 3D en plataformas como Sketchfab. Este modo de difusión
permite el estudio de grabados sin esos errores intrínsecos a la
proyección. Los modelos 3D realzados de los casos de estudio de este
capítulo se pueden observar en los siguientes enlaces:

Caso 1. PT de Fontão do Eido: https://skfb.ly/6CyoW

186 | Página

<!-- p. 187 -->

UNA METODOLOGÍA DE TRABAJO SIMPLE Y DE BAJO COSTE AL ALCANCE DE
MÚLTIPLES PERFILES PARA EL MODELADO 3D Y VECTORIZACIÓN
AUTOMATIZADA DE GRABADOS DE ARTE RUPESTRE “ATLÁNTICO”

Caso 2. PT de Pedra da Grada: https://skfb.ly/6E7HX

Caso 3. PT da Pedra da Loba: https://skfb.ly/6E7EX

187 | Página

<!-- p. 188 -->

SIMÓN PEÑA VILLASENÍN

Caso 4. PT da Peneda Negra: https://skfb.ly/6E7Ew

Caso 5. PT dos Buracos: https://skfb.ly/6Ew7R

188 | Página

<!-- p. 189 -->

UNA METODOLOGÍA DE TRABAJO SIMPLE Y DE BAJO COSTE AL ALCANCE DE
MÚLTIPLES PERFILES PARA EL MODELADO 3D Y VECTORIZACIÓN
AUTOMATIZADA DE GRABADOS DE ARTE RUPESTRE “ATLÁNTICO”

Caso 6. PT de A Fieiteira: https://skfb.ly/6Ewrp

Caso 7. PT de O Castriño de Conxo: https://skfb.ly/6EzFV

189 | Página

<!-- p. 190 -->

SIMÓN PEÑA VILLASENÍN

A pesar de la limitación de 50 Mb, utilizando el formato STL y la
compresión RAR de alta calidad, es posible cargar mallas de más de 2
millones de triángulos que permiten su estudio eficiente.

Formato 2D vs 3D
A medida que se analizan los resultados finales, el proceso de
publicación en 2D y 3D de bajo coste, fue ejecutado con éxito por
perfiles no expertos en la documentación y la difusión de varios
ejemplos de este fenómeno del patrimonio. El modo de estudio en 3D
y su difusión es más simple que el modo de difusión en 2D y los
resultados son más completos y sin errores de proyección.

Conclusiones
El uso de técnicas avanzadas de adquisición de datos 3D, realces
digitales y tratamientos de vectorización automática, que son
accesibles para perfiles no expertos debido a la facilidad y bajo coste
de su ejecución, permite la documentación geométrica de los sutiles
grabados del arte rupestre “Atlántico”, de un modo masivo y con
suficiente poder analítico para obtener interpretaciones objetivas de los
mismos. Además, después de analizar ampliamente los resultados del
software fotogramétrico así como de las opciones de post-proceso
disponibles, se proporciona un flujo de trabajo con software de licencia
gratuita, optimizado para lograr la mayor facilidad de uso y objetividad
en las interpretaciones de grabados rupestres.
Con respecto al análisis de las diferentes opciones de
configuración de los renderizados de realce, se muestra cómo a partir
de un software ampliamente utilizado como Meshlab, es posible
obtener resultados visualmente atractivos que son similares a los
obtenidos a partir de fotografías e iluminación artificial mediante los
renderizados afectados por el ángulo de iluminación. El uso de
renderizados afectados por la iluminación elimina la necesidad de
realizar fotografía nocturna. Además, las posibilidades de iluminación
artificial en los modelos 3D son más flexibles que las que se presentan
in situ. Por otro lado, los renderizados que no se ven afectados por la
iluminación proporcionan resultados objetivos para las

190 | Página

<!-- p. 191 -->

UNA METODOLOGÍA DE TRABAJO SIMPLE Y DE BAJO COSTE AL ALCANCE DE
MÚLTIPLES PERFILES PARA EL MODELADO 3D Y VECTORIZACIÓN
AUTOMATIZADA DE GRABADOS DE ARTE RUPESTRE “ATLÁNTICO”

interpretaciones del grabado. En concreto el renderizado Lit Sphere
Radiance Scaling ofrece los mejores resultados con esferas en blanco
y negro. La exportación de baja calidad de capturas y el suavizado de
la malla mejoró significativamente los resultados en la mayoría de
casos, por lo cual estos procesos pueden ser recomendados para
optimizar los resultados, no obstante, el efecto de suavizado es
contraproducente en grabados muy sutiles o con mallas triangulares de
baja resolución. Por otro lado, destacar que una interpretación mínima
por parte del técnico en la aplicación del tratamiento de “caja oscura”
para la generación del mapa de bits sigue siendo necesaria.
Finalmente, en este estudio, se evidencia que el formato 2D puede
producir errores de interpretación de los diseños rupestres. Debido a
estos errores potenciales y debido a una mínima e inevitable
interpretación necesaria por parte del técnico en la fase de generación
del mapa de bits, se puede concluir que la tendencia debe avanzar hacia
el estudio directo de los grabados a partir del modelo 3D realzado. Este
es el modo más completo y objetivo que tienen los técnicos para
interpretar este fenómeno, evitando el error de proyección de
información sobre un formato 2D. Además, plataformas como
Sketchfab permiten la difusión mundial de los modelos 3D realzados
de una manera visualmente atractiva y moderna. Estas herramientas de
difusión online junto con los métodos de adquisición de modelos 3D
como la fotogrametría SfM simple y de bajo coste, son un conjunto
idóneo para la documentación masiva de este patrimonio en riesgo.

191 | Página

<!-- p. 192 -->



<!-- p. 193 -->

CONCLUSIONES

\9. CONCLUSIONES

En el primer capítulo de estudio de modelado 3D de fachadas
históricas mediante fotogrametría SfM (Capítulo I), las principales
conclusiones alcanzadas fueron:
\1. El modelado 3D de fachadas de edificios históricos mediante
fotogrametría terrestre puede realizarse de forma masiva, a bajo
coste, con agilidad y con suficiente precisión para múltiples
aplicaciones, como muestran los resultados del levantamiento de
las fachadas de los casos estándar resueltos en este capítulo (Caso
1 y 2).

\2. La fotogrametría SfM es una técnica capaz de adaptarse a las
geometrías complejas habitualmente presentes en el patrimonio
arquitectónico de cascos históricos, como evidencian los
resultados obtenidos en el caso 3, “calle estrecha” y en el caso 4
“fachada con soportales”. La disposición fotográfica habitual para
el establecimiento de la red fotogramétrica no era aplicable en
estos casos, por lo que ha sido necesario aportar soluciones
adaptadas a las geometrías complejas presentes, obteniendo
esquemas de trabajo extrapolables a ejemplos de similares
características. Esta adaptación de la red fotogramétrica, se basa
en la combinación de imágenes oblicuas y perpendiculares,
evidenciando que no solo es posible la combinación de las mismas,
sino recomendable para obtener modelos 3D geométrica y
visualmente correctos.

193 | Página

<!-- p. 194 -->

SIMÓN PEÑA VILLASENÍN

\3. El software empleado (Agisoft PhotoScan) permite utilizar
preselección de imágenes en los emparejamientos, lo que agiliza
notablemente los tiempos de procesado inicial y facilita la correcta
orientación de las imágenes, siempre y cuando la toma se realice
de forma correlativa, es decir, que la colección de imágenes sea
una concatenación de imágenes solapadas, cuya cadena de enlace
no se rompa en toda la toma fotográfica.

\4. La utilización de dispositivos de estabilización de la toma
fotográfica como trípodes, mengua en gran medida el rendimiento
de la técnica especialmente en casos complejos donde los espacios
limitan el posicionamiento estable del mismo. En su lugar, si se
prescinde de su utilización, es posible obtener modelos 3D de
precisión mediante una toma de fotos a mano alzada, de un modo
más ágil, con mayor número de capturas y por lo tanto, con mayor
solape y que mejora los resultados tanto geométricos como
visuales.

\5. La utilización de dispositivos de elevación de la toma fotográfica
como pértigas o RPAS, no es un requisito indispensable para
obtener datos métricos de precisión de fachadas históricas de
varias alturas, ya que se han obtenido resultados satisfactorios en
estos casos empleando exclusivamente imágenes tomadas con
medios terrestres.

\6. El uso de cámaras profesionales no es un requisito indispensable
para obtener mediante fotogrametría SfM, modelos 3D de
suficiente calidad geométrica y visual para documentaciones
patrimoniales, ya que se han obtenido resultados satisfactorios en
uno de los casos de este estudio a partir de colecciones de
imágenes tomadas con la cámara integrada en un SmartPhone.

\7. El sistema y escalado de la escena mediante una o varias medidas
de referencia en lugar de mediante puntos de coordenadas
conocidas, agiliza notablemente este proceso, proporcionando
resultados con suficiente precisión para múltiples aplicaciones.

194 | Página

<!-- p. 195 -->

CONCLUSIONES

En el segundo capítulo de estudio de comparación de software
desktop profesional y software gratuito cloud computing en el
modelado 3D de edificios históricos (Capítulo II), las principales
conclusiones alcanzadas fueron:
\8. La comparación entre software desktop profesional y el
software cloud computing de uso gratuito muestra resultados
próximos en términos de precisión geométrica y calidad visual,
y suficientes para considerarse ambas opciones válidas para
múltiples tareas de documentación de elementos patrimoniales.

\9. El software de computación “en la nube” es accesible en costes
y obtiene un gran rendimiento en tiempos, tiene un flujo de
trabajo simple, no es necesario aprendizaje previo para su
utilización y no requiere un desembolso grande en equipos
informáticos al procesar los resultados “en la nube”, por lo que
se adapta a la perfección, a las tareas documentales cotidianas
de los profesionales del patrimonio arquitectónico no
especialistas en fotogrametría.

\10. Para garantizar la orientación de los procesados
fotogramétricos SfM en software cloud computing, es
conveniente que la toma sea correlativa. Por otro lado, las
variables de configuración del emparejamiento entre imágenes
que permite el software desktop, permiten obtener correctas
orientaciones de imágenes solapadas de modo no correlativo,
no obstante esto ralentiza el procesado y aumenta la
probabilidad de obtener una orientación de imágenes fallida.

\11. A pesar de que mediante la utilización de software externo es
posible obtener productos secundarios como ortofotos o
modelados BIM a partir de modelos 3D obtenidos con software
de computación “en la nube”, la utilización de software
profesional de computación local, el cual integra esta
posibilidad y ofrece más variables de configuración en este
sentido, sería recomendable si se requieren dichos productos.

195 | Página

<!-- p. 196 -->

SIMÓN PEÑA VILLASENÍN

\12. El parámetro de configuración del procesado fotogramétrico
SfM bajo la denominación de “calidad”, común a todas las
opciones de software SfM, siendo configurable de modo
independiente en distintas fases del procesado en software
desktop, y constante en software cloud computing, es el
parámetro de mayor influencia en la calidad geométrica y
visual de los resultados y tiempos de ejecución del procesado
fotogramétrico.

\13. La comparación de resultados de las opciones de software
desktop, muestra que la calidad de los resultados y el
rendimiento en tiempos es similar para ambas. A pesar de que
las diferencias entre ambos software varían con el desarrollo de
actualizaciones de versión, cabe destacar varias diferencias que
se mantienen constantes: PhotoScan presenta un procesado SfM
más configurable que Pix4D, mientras que este, muestra un
entorno de trabajo visualmente más atractivo e intuitivo. En la
generación de ortofotos y texturas, es donde encontramos las
mayores diferencias de resultados. PhotoScan permite un
mayor grado de configuración del procesado permitiendo
generar ortomosaicos y texturas con distintos modos de
mapeado, mientras que Pix4D está más limitado en este
aspecto.

\14. La continua progresión de los algoritmos del software SfM y de
las capacidades de computación de los ordenadores y servicios
de computación “en la nube” hacen de la fotogrametría una
técnica “viva”, permitiendo que una misma colección de
imágenes tomadas en un momento concreto, pueda ser
procesada en el futuro con mejores capacidades de
computación y algoritmos más eficientes. Por ello, debe
reflexionarse sobre la toma de datos fotográficos en bruto
susceptibles de utilizarse para procesado fotogramétrico como
entregable principal en los trabajos, en lugar del modelo 3D en
sí mismo, ya que en el futuro, la misma colección de imágenes

196 | Página

<!-- p. 197 -->

CONCLUSIONES

dará lugar a un modelo 3D mejor al que se puede generar o
manejar con los medios actuales.

En el tercer capítulo de estudio de comparación de TLS y
fotogrametría SfM para el modelado 3D de arte rupestre y la aplicación
del realce Radiance Scaling Shader para la detección de grabados
(Capitulo III), las principales conclusiones alcanzadas fueron:
\15. La comparación de precisión geométrica muestra que las
diferencias entre ambas mallas son menores de 2 mm. Por lo
tanto, la metodología fotogramétrica simple utilizada puede
considerarse cercana en precisión al TLS para la tarea de
modelado 3D de petroglifos de geometrías complejas.

\16. Mediante TLS y mediante fotogrametría SfM es posible obtener
modelos 3D de suficiente calidad geométrica para realizar un
análisis objetivo de inscripciones de arte rupestre basado en la
utilización de los filtro de Radiance Scaling de Meshlab.

\17. La fotogrametría se adapta en mayor grado que el TLS a la tarea
de documentación de elementos de arte rupestre con
morfologías complejas, obteniendo resultados de mayor
calidad geométrica y visual con mejor rendimiento en tiempos
y costes y mayor accesibilidad técnica. Los resultados de la
fotogrametría son precisos, sin huecos, con mejores texturas
que las obtenidas con TLS. Además permite trabajar fácilmente
a distintas resoluciones sobre el mismo elemento en función del
grado de definición necesaria para cada zona permitiendo un
ahorro de tiempo notable en zonas con pocos detalles o
secundarias. Con la metodología TLS es posible trabajar
también a múltiples resoluciones pero el ahorro de esfuerzo no
es tan relevante. El tiempo de trabajo con fotogrametría SfM es
menor que con el TLS y además varios equipos pueden trabajar
simultáneamente a bajo coste, por todo ello es una técnica más
operativa en labores de prospección de arte rupestre donde es
necesario documentar un número elevado de elementos
dispersos en amplios territorios, en un periodo corto de tiempo.

197 | Página

<!-- p. 198 -->

SIMÓN PEÑA VILLASENÍN

Mediante fotogrametría es posible realizar la documentación de
una gran cantidad de elementos en un solo día de campo a un
coste muy bajo.

\18. Esta técnica es accesible a perfiles no expertos con un mínimo
de instrucción, como se muestra en el segundo experimento de
este estudio, en el cual mediante colaboración altruista se
obtuvieron resultados satisfactorios en la documentación
geométrica de varias muestras de arte rupestre inéditas no
documentadas hasta la fecha.

\19. Los filtros Radiance Scaling aplicados sobre los modelos de
TLS o fotogrametría, muestran un potencial en la detección de
grabados mayor que las metodologías tradicionales, ya que se
registraron grabados no documentados por estudios previos en
este mismo petroglifo (PT de Castriño de Conxo). No obstante,
conviene profundizar en las variables de configuración de estos
tratamientos, lo cual se aborda en el siguiente capítulo.

En el cuarto capítulo de estudio de desarrollo de una metodología
de trabajo simple y de bajo coste al alcance de múltiples perfiles para
el modelado 3D y vectorización automatizada de grabados de arte
rupestre “Atlántico” (Capítulo IV), las principales conclusiones
alcanzadas fueron:
\20. A partir de un flujo de trabajo de bajo coste y fácil
implementación basado en la adquisición de modelos 3D
mediante fotogrametría SfM y la aplicación sobre estos de
tratamientos digitales de realce y vectorización automática, es
posible obtener calcos virtuales de inscripciones en piedra
como los petroglifos de arte rupestre “Atlántico” con un alto
grado de objetividad.

198 | Página

<!-- p. 199 -->

CONCLUSIONES

\21. El software Meshlab, aporta posibilidades de iluminación
artificial sobre los modelos 3D más flexibles que las que
permiten los yacimientos de arte rupestre in situ y elimina la
visita nocturna a estos facilitando notablemente su estudio.

\22. Mediante Meshlab, es posible utilizar renderizados de realce
denominados “Radiance Scaling Shader”. Algunas opciones de
este realce, permiten la variación de intensidad y dirección del
punto de iluminación, mostrando resultados visualmente
atractivos pero con cierta subjetividad; otras opciones de
realces no se ven afectados por los cambios digitales de
iluminación, lo que proporciona resultados más objetivos. En
concreto el denominado como “Lit Sphere Radiance Scaling”
obtiene grandes resultados en la detección de grabados.
Además, la utilización de colores negro y blanco sólidos en las
esferas de este renderizado, genera un mejor contraste en los
resultados y proporciona una captura en blanco y negro
fácilmente interpretable por los vectorizadores automáticos.

\23. El suavizado de la malla habitualmente mejora los resultados
en la detección de grabados, no obstante, en grabados muy
sutiles o en mallas de triángulos de baja densidad, el efecto de
suavizado puede ser contraproducente, provocando que se
“pierda” el grabado, por lo que se debe considerar su utilización
en cada caso.

\24. La calidad en la exportación de las capturas de los modelos
realzados, tiene influencia en los resultados, siendo
habitualmente más fácilmente detectables los grabados en las
capturas exportadas en baja resolución, aunque en grabados
poco profundos, esto no tiene por qué ser así. Por lo tanto, es
recomendable exportar las capturas en distintas resoluciones
con el objetivo de realizar un análisis lo más preciso posible de
los mismos.

199 | Página

<!-- p. 200 -->

SIMÓN PEÑA VILLASENÍN

\25. En la fase de preparación para la vectorización de calcos
virtuales a partir de las capturas obtenidas sobre los modelos
realzados, se realiza la subexposición y sobrexposición de la
imagen. En este paso tiene influencia la interpretación del
técnico en el grado de subexposición y sobrexposición de las
capturas, no obstante esta es la última fase del flujo de trabajo,
antes de la vectorización automática, por lo que su influencia
en el resultado no es de gran relevancia.

\26. Los resultados de este estudio evidencian que el formato 2D
producen errores de interpretación de los grabados, por ello se
debe avanzar hacia el estudio directamente sobre los modelos
3D realzados, ya que esta es la forma más completa y objetiva
que tienen los técnicos para realizar las interpretaciones de los
mismos, evitando errores intrínsecos a la proyección de la
información tridimensional sobre un formato bidimensional.
Esto es posible actualmente gracias a plataformas online como
Sketchfab que permiten de un modo abierto, visualmente
atractivo y moderno, la difusión de modelos 3D con
renderizados de realce similares a los aplicados en el software
Meshlab.
Por tanto, la principal conclusión de esta tesis es que la
fotogrametría SfM es accesible a perfiles no técnicos como
arqueólogos, historiadores o incluso aficionados al patrimonio,
permitiendo obtener modelos 3D de gran calidad geométrica y visual.
Permite además obtener un gran rendimiento en tiempos y costes, por
lo que cuenta con un gran potencial en la documentación geométrica tanto
del patrimonio arquitectónico como arqueológico.
En esta tesis, se definen asimismo flujos de trabajo sencillos que
permiten la obtención de modelos 3D de calidad, en ocasiones, en
situaciones extremas donde la aplicación de las metodologías de toma de
imagen estandarizadas no es aplicable, como en cascos históricos o
petroglifos de geometrías complejas donde esta técnica mejora los
resultados y rendimientos de metodologías a priori más avanzadas como
el TLS en todos los parámetros analizados.

200 | Página

<!-- p. 201 -->

CONCLUSIONES

Además, se define un flujo de trabajo completo basado en la
aplicación de fotogrametría SfM, renderizados de realce y
vectorización automática, mediante software gratuito en todo el
procesado, que permite documentar un número elevado de petroglifos
en un periodo corto de tiempo y además es capaz de registrar de modo
objetivo grabados de arte rupestre “Atlántico” que los métodos
tradicionales no consiguen detectar.

201 | Página

<!-- p. 202 -->



<!-- p. 203 -->

BIBLIOGRAFÍA

\10. BIBLIOGRAFÍA

Abd Elbasit, M. A. M., Anyoji, H., Yasuda, H., & Yamamoto, S. (2009). Potential of low cost
close-range photogrammetry system in soil microtopography quantification.
Hydrological Processes. https://doi.org/10.1002/hyp.7263

Aguilar, M. A., Aguilar, F. J., & Agüera, F. (2005). Mapping small areas using a low‐cost close
range photogrammetric software package with aerial photography. The
Photogrammetric Record, 20(112), 335–350.

Al-kheder, S., Al-shawabkeh, Y., & Haala, N. (2009). Developing a documentation system for
desert palaces in Jordan using 3D laser scanning and digital photogrammetry. Journal
of Archaeological Science, 36(2), 537–546. https://doi.org/10.1016/j.jas.2008.10.009

Albertz, J., Wiedemann, A. (1996). From Analogue To Digital Close-Range Photogrammetry.
First Turkish-German Joint Geodetic Days, 245–253. Retrieved from
http://www.alwie.net/lit/IstCR.pdf

Alby, E., Smigiel, E., Assali, P., Grussenmeyer, P., & Kauffmann-Smigiel, I. (2009). Low cost
solutions for dense point clouds of small objects: Photomodeler Scanner vs. David
Laserscanner. In 22nd CIPA Symposium.

Almagro, A. (2002). Simple Methods of Photogrammetry: Easy and Fast. In XVIII International
Symposium of CIPA, Potsdam, September 18-21, 2001. (pp. 32–38).

Altuntas, C., Yildiz, F., Karabork, H., Yakar, M., Karasaka, L., Konya-turkey, P. E., et al. (2007).
Surveying and Documentation of Detailed Historical Heritage By Laser Scanning.
Heritage, (October), 3–5.

Apollonio, F. I., Gaiani, M., & Benedetti, B. (2012). 3D reality-based artefact models for the
management of archaeological sites using 3D Gis: A framework starting from the case
study of the Pompeii Archaeological area. Journal of Archaeological Science.
https://doi.org/10.1016/j.jas.2011.12.034

Arayici, Y. (2007). An approach for real world data modelling with the 3D terrestrial laser
scanner for built environment. Automation in Construction, 16(6), 816–829.
https://doi.org/10.1016/j.autcon.2007.02.008

203 | Página

<!-- p. 204 -->

SIMÓN PEÑA VILLASENÍN

Arcà, A. (2006). Rupestrian Archaeology: A methodological approach to the rock engravings
of Valcamonica, 51–58.

Arias, P., Ordóñez, C., Lorenzo, H., & Herraez, J. (2006). Methods for documenting historical
agro-industrial buildings: a comparative study and a simple photogrammetric method.
Journal of Cultural Heritage. https://doi.org/10.1016/j.culher.2006.09.002

Arias, P., Ordóñez, C., Lorenzo, H., Herraez, J., & Armesto, J. (2007). Low-cost documentation
of traditional agro-industrial buildings by close-range photogrammetry. Building and
Environment, 42(4), 1817–1827. https://doi.org/10.1016/j.buildenv.2006.02.002

Baltsavias, E. P. (1999). A comparison between photogrammetry and laser scanning. ISPRS
Journal of Photogrammetry and Remote Sensing, 54(2–3), 83–94.
https://doi.org/10.1016/S0924-2716(99)00014-3

Barazzetti, L., Remondino, F., & Scaioni, M. (2009). Combined use of photogrammetric and
computer vision techniques for fully automated and accurate 3D modeling of
terrestrial objects. In Videometrics, Range Imaging, and Applications X.
https://doi.org/10.1117/12.825638

Barazzetti, L., Binda, L., Scaioni, M., & Taranto, P. (2011). Photogrammetric survey of complex
geometries with low-cost software: Application to the ’G1′ temple in Myson, Vietnam.
Journal of Cultural Heritage, 12(3), 253–262.
https://doi.org/10.1016/j.culher.2010.12.004

Bayram, B., Nemli, G., Özkan, T., Oflaz, O. E., Kankotan, B., & Çetin, A. (2015). Comparison of
laser scanning and photogrammetry and their use for digital recording of cultural
monument case study: Byzantine land walls-istanbul. ISPRS Annals of the
Photogrammetry, Remote Sensing and Spatial Information Sciences, 2(5W3), 17–24.
https://doi.org/10.5194/isprsannals-II-5-W3-17-2015

Bea, M., & Angás, J. (2017). Geometric documentation and virtual restoration of the rock art
removed in Aragón (Spain). Journal of Archaeological Science: Reports, 11, 159–168.
https://doi.org/10.1016/j.jasrep.2016.11.025

Bedate, A., Herrero, L. C., & Sanz, J. Á. (2004). Economic valuation of the cultural heritage:
Application to four case studies in Spain. Journal of Cultural Heritage.
https://doi.org/10.1016/j.culher.2003.04.002

Beekmans, C., Schneider, J., Läbe, T., Lennefer, M., Stachniss, C., & Simmer, C. (2016). Cloud
photogrammetry with dense stereo for fisheye cameras. Atmospheric Chemistry and
Physics, 16(22), 14231–14248.

Bellotti, F., Berta, R., Cardona, R., & De Gloria, A. (2011). An architectural approach to efficient
3D urban modeling. Computers and Graphics (Pergamon), 35(5), 1001–1012.
https://doi.org/10.1016/j.cag.2011.07.004

204 | Página

<!-- p. 205 -->

BIBLIOGRAFÍA

Beraldin, J.-A., Blais, F., Boulanger, P., Cournoyer, L., Domey, J., El-Hakim, S. F., et al. (2000).
Real world modelling through high resolution digital 3D imaging of objects and
structures. ISPRS Journal of Photogrammetry & Remote Sensing, 55, 230–250.
https://doi.org/10.1016/S0924-2716(00)00013-7

Bhatla, A., Choe, S. Y., Fierro, O., & Leite, F. (2012). Evaluation of accuracy of as-built 3D
modeling from photos taken by handheld digital cameras. Automation in Construction,
28, 116–127. https://doi.org/10.1016/j.autcon.2012.06.003

Blais, F. (2004). Review of 20 years of range sensor development. Journal of Electronic
Imaging. https://doi.org/10.1117/1.1631921

Boehler, W., & Marbs, A. (2004). 3D Scanning and Photogrammetry for Heritage Recording :
a Comparison. Proc. 12th International Conference on Geoinformatics, University of
Gävle, Sweden, (June), 7–9.

Böhler, W., & Heinz, G. (1999). Documentation, surveying, photogrammetry. In XVII CIPA
Symposium. Recife, Olinda. Brazil (Vol. 1).

Bolognesi, M., Furini, A., Russo, V., Pellegrinelli, A., & Russo, P. (2015). TESTING THE LOW-
COST RPAS POTENTIAL IN 3D CULTURAL HERITAGE RECONSTRUCTION. International
Archives of the Photogrammetry, Remote Sensing & Spatial Information Sciences.

Borysenko, D. V. (2018). USE OF MOBILE APPLICATIONS FOR DEVELOPING DESIGN-PRODUCTS
IN TRAINING OF FUTURE EXPERTS IN DESIGN. Information Technologies and Learning
Tools, 68(6), 47–63.

Boukerch, I., Takarli, B., Mahmoudi, R., Tellai, S., & Chadli, D. (2016). APPLICATION OF DIGITAL
TERRESTRIAL PHOTOGRAMMETRY IN ARCHITECTURAL CONSERVATION: THE MOSQUE
OF ABDULLAH IBN SALAM OF ORAN. ISPRS - International Archives of the
Photogrammetry, Remote Sensing and Spatial Information Sciences.
https://doi.org/10.5194/isprs-archives-xli-b5-989-2016

Bradley, R. (2002). Access, Style and Imagery : the Audience for Prehistoric Rock Art in Atlantic
Spain and Portugal, 4000-2000 Bc. Oxford Journal of Archaeology, 21(3), 231–247.
https://doi.org/10.1111/1468-0092.00160

Bradley, R., & Fábregas-Valcarce, R. (1998). Crossing the border: contrasting styles of rock art
in the prehistory of north-west Iberia. Oxford Journal of Archaeology, 17(3), 287–308.
https://doi.org/10.1111/1468-0092.00064

Bradley, R., Criado-Boado, F., & Valcarce, R. F. (1994). Rock art research as landscape
archaeology: a pilot study in Galicia, north-west Spain. World Archaeology, 25(3), 374–
\390. Retrieved from
http://www.tandfonline.com/doi/abs/10.1080/00438243.1994.9980252

205 | Página

<!-- p. 206 -->

SIMÓN PEÑA VILLASENÍN

Brown, D. C. (1972). Close Range Calibration.

Brumana, R., Oreni, D., Cuca, B., Binda, L., Condoleo, P., & Triggiani, M. (2014). Strategy for
Integrated Surveying Techniques Finalized to Interpretive Models in a Byzantine
Church, Mesopotam, Albania. International Journal of Architectural Heritage, 8(6),
886–924. https://doi.org/10.1080/15583058.2012.756077

Buhigas-Sobrino, R. (2000). Corpus Petroglyphorum Gallaeciae (Do Castro).

Bui, Q. B., Morel, J. C., Venkatarama Reddy, B. V., & Ghayad, W. (2009). Durability of rammed
earth walls exposed for 20 years to natural weathering. Building and Environment,
44(5), 912–919. https://doi.org/10.1016/j.buildenv.2008.07.001

Butler, J., Lane, S., Chandler, J., & Porfiri, E. (2002). Through-Water Close Range Digital
Photogrammetry in Flume and Field Environments. The Photogrammetric Record,
17(99), 419–439. https://doi.org/10.1111/0031-868X.00196

Campana, S., & Remondino, F. (2007). Fast and detailed digital documentation of
archaeological excavations and heritage artifacts. Layers of Perception: Proceedings of
the 35th International Conference on Computer Applications and Quantitative
Methods in Archaeology (CAA), Berlin, Germany, April 2-6, 2007, 36–42. Retrieved from
https://publikationen.uni-
tuebingen.de/xmlui/bitstream/handle/10900/61506/18_Campana_Remondino_CAA
2007.pdf?sequence=2

Campana, S., & Remondino, F. (2008). Fast and detailed digital documentation of
archaeological excavations and heritage artifacts. Layers of Perception: Proceedings of
the 35th International Conference on Computer Applications and Quantitative
Methods in Archaeology (CAA), Berlin, Germany, April 2-6, 2007, 36–42.

Carnevali, L., Ippoliti, E., Lanfranchi, F., Menconero, S., Russo, M., & Russo, V. (2018). CLOSE‐
RANGE MINI‐UAVS PHOTOGRAMMETRY FOR ARCHITECTURE SURVEY. ISPRS-
International Archives of the Photogrammetry, Remote Sensing and Spatial
Information Sciences, 422, 217–224.

Caro, J. L., & Hansen, S. (2015). De la fotogrametría a la difusión del patrimonio arqueológico
mediante game engines : Menga un caso de estudio. VAR. Virtual Archaeology Review,
6(12), 58. https://doi.org/10.4995/var.2015.4159

Carrera Ramírez, F., Costas Goberna, F. J., Peña Santos, A. de la, & Rey García, J. M. (1994). El
arte rupestre galaico: una reflexión crítica sobre el presente y una propuesta para el
futuro. Trabajos de Prehistoria, 51, No2, (c), 41–54.

206 | Página

<!-- p. 207 -->

BIBLIOGRAFÍA

Carrero-Pazos, M., Vilas-Estévez, B., & Vázquez-Martínez, A. (2012). Digital imaging
techniques for recording and analysing prehistoric rock art panels in Galicia (NW
Iberia). Digital Applications in Archaeology and Cultural Heritage, (July), 1–11.
https://doi.org/10.1016/j.daach.2017.11.003

Carrero-Pazos, M., Vilas-Estévez, B., & Vázquez-Martínez, A. (2018). Digital imaging
techniques for recording and analysing prehistoric rock art panels in Galicia (NW
Iberia). Digital Applications in Archaeology and Cultural Heritage, 8(October 2017), 35–
\45. https://doi.org/10.1016/j.daach.2017.11.003

Chandler, J. H., & Buckley, S. J. (2016). Structure from motion ( SFM ) photogrammetry vs
terrestrial laser scanning. In Geoscience Handbook 2016: AGI Data Sheets (pp. 0–4).
Retrieved from
https://dspace.lboro.ac.uk/2134/21673%0Ahttps://dspace.lboro.ac.uk/dspace-
jspui/handle/2134/21673

Chandler, J.H., Fryer, J., & Kniest, H. (2005). Non-invasive three-dimensional recording of
aboriginal rock art using cost-effective digital photogrammetry. Rock Art Research,
22(2), 119–130. Retrieved from
http://scholar.google.com/scholar?hl=en&btnG=Search&q=intitle:Non-
Invasive+Three-dimensional+recording+of+aboriginal+rock+art+using+cost-
effective+digital+photogrammetry#0

Chandler, Jh, Fryer, J., & Jack, A. (2005). Metric capabilities of low cost digital cameras for
close range surface measurement. The Photogrammetric Record, 17(March), 1–16.
https://doi.org/10.1111/j.1477-9730.2005.00302.x

Chandler, Jim;, & Fryer, J. (2013). AutoDesk 123D Catch : How accurate is it? Geomatics
World, (January 2013), 28–30.

Chandler, Jim. (1999). Effective application of automated digital photogrammetry for
geomorphological research. Earth Surface Processes and Landforms, 24(1), 51–63.
https://doi.org/10.1002/(SICI)1096-9837(199901)24:1\<51::AID-ESP948>3.0.CO;2-H

Chandler, Jim H., Bryan, P., & Fryer, J. G. (2007). The development nd application af a simple
methodology for recording rock art using consumer-grade digital cameras.
Photogrammetric Record, 22(117), 10–21. https://doi.org/10.1111/j.1477-
9730.2007.00414.x

Chandler, Jim H, Buffin‐Bélanger, T., Rice, S., Reid, I., & Graham, D. J. (2003). The accuracy of
a river bed moulding/casting system and the effectiveness of a low‐cost digital camera
for recording river bed fabric. The Photogrammetric Record, 18(103), 209–223.

Chandran, V., Carswell, B., Boashash, B., & Elgar, S. (1997). Pattern recognition using
invariants defined from higher order spectra: 2-D image inputs. IEEE Transactions on
Image Processing, 6(5), 703–712. https://doi.org/10.1109/83.568927

207 | Página

<!-- p. 208 -->

SIMÓN PEÑA VILLASENÍN

Chang, T. C., Milne, S., Fallon, D., & Pohlmann, C. (1996). Urban heritage tourism: The Gobal-
Local Nexus. Annals of Tourism Research. https://doi.org/10.1016/0160-
7383(95)00064-X

Chiabrando, F., Nex, F., Piatti, D., & Rinaudo, F. (2011). UAV and RPV systems for
photogrammetric surveys in archaelogical areas: Two tests in the Piedmont region
(Italy). Journal of Archaeological Science, 38(3), 697–710.
https://doi.org/10.1016/j.jas.2010.10.022

Chidburee, P., Mills, J. P., Miller, P. E., & Fieber, K. D. (2016). TOWARDS A LOW-COST, REAL-
TIME PHOTOGRAMMETRIC LANDSLIDE MONITORING SYSTEM UTILISING MOBILE AND
CLOUD COMPUTING TECHNOLOGY. International Archives of the Photogrammetry,
Remote Sensing & Spatial Information Sciences, 41.

Cirulis, A., Paolis, L. T. De, & Tutberidze, M. (2015). Virtualization of Digitalized Cultural
Heritage and Use Case Scenario Modeling for Sustainability Promotion of National
Identity. In Procedia Computer Science (Vol. 77, pp. 199–206).
https://doi.org/10.1016/j.procs.2015.12.384

Clarke, T. A., & Fryer, J. G. (1998). The Development of Camera Calibration Methods and
Models. The Photogrammetric Record, 16(91), 51–66. https://doi.org/10.1111/0031-
868X.00113

Clogg, P., Dı́az-Andreu, M., & Larkman, B. (2000). Digital Image Processing and the Recording
of Rock Art. Journal of Archaeological Science, 27(9), 837–843.
https://doi.org/10.1006/jasc.1999.0522

Croci, G., Villa, F. G., Carluccio, G., De Vito, S., & Viskovic, A. (1997). Repair of the grand
staircases in the monastery of San Martin Pinario in Santiago de Compostela and in the
Colegio del Cardenal in Monforte de Lemos. In International Series on Advances in
Architecture (Vol. 3).

Cuevillas, F. L. (1951). La clasificación tipológica del arte rupestre del noroeste hispánico y
una hipótesis sobre la cronología de alguno de sus tipos. Zephyrvs, 2.

D.D. Lichti, S. J. Gordon, M. P. Stawart, J. Franke, M. T. (2002). Comparison of digital
photogrammetry and laser scanning, 00(January 2002), 39–44.

Dai, F., & Lu, M. (2010). Assessing the Accuracy of Applying Photogrammetry to Take
Geometric Measurements on Building Products. Journal of Construction Engineering
and Management, 136(2), 242–250. https://doi.org/10.1061/(ASCE)CO.1943-
7862.0000114

Deng, G., & Faig, W. (2001). An evaluation of an off-the-shelf digital close-range
photogrammetric software package. Photogrammetric Engineering and Remote
Sensing, 67(2), 227–233.

208 | Página

<!-- p. 209 -->

BIBLIOGRAFÍA

Deseilligny, M. P., & Clery, I. (2011). APERO, an Open Source Bundle Adjustment Software for
Automatic Calibration and Orientation of Sets of Images. International Archives of
Photogrammetry, Remote Sensing, and Spatial Information Sciences, XXXVIII(5-W16),
269–276. https://doi.org/10.5194/isprsarchives-XXXVIII-5-W16-269-2011

Desmond, L. G., & Bryan, P. G. (2003). Recording architecture at the archaeological site of
Uxmal, Mexico: A historical and contemporary view. Photogrammetric Record.
https://doi.org/10.1111/0031-868X.t01-1-00013

Di, L., Yue, P., Ramapriyan, H. K., & King, R. L. (2013). Geoscience data provenance: An
overview. IEEE Transactions on Geoscience and Remote Sensing, 51(11), 5065–5072.

Díaz-Andreu, M., Brooke, C., Rainsbury, M., & Rosser, N. (2006). The spiral that vanished: the
application of non-contact recording techniques to an elusive rock art motif at
Castlerigg stone circle in Cumbria. Journal of Archaeological Science, 33(11), 1580–
\1587. https://doi.org/10.1016/j.jas.2006.02.010

Díaz-Guardamino, M., & D, W. (2013). Rock Art and Digital Technologies: The Application of
Reflectance Transformation Imaging (RTI) and 3D Laser Scanning to the Study of Late
Bronze Age Iberian Stelae. MENGA 04, Journal of Andalusian Prehistory.

Domingo, I., Villaverde, V., López-Montalvo, E., Lerma, J. L., & Cabrelles, M. (2013). Latest
developments in rock art recording: towards an integral documentation of Levantine
rock art sites combining 2D and 3D recording techniques. Journal of Archaeological
Science, 40(4), 1879–1889. https://doi.org/10.1016/j.jas.2012.11.024

Duane, C. B. (1971). Close-range camera calibration. Photogramm. Eng, 37(8), 855–866.

Duffy, S., Bryan, P., Earl, G., Beale, G., Pagi, H., & Kotoula, E. (2013). Multi-light Imaging for
Heritage Applications. English Heritage.

Earl, G., Martinez, K., & Malzbender, T. (2010). Archaeological applications of polynomial
texture mapping: Analysis, conservation and representation. Journal of Archaeological
Science, 37(8), 2040–2050. https://doi.org/10.1016/j.jas.2010.03.009

El-Hakim, S., Beraldin, J. A., Gonzo, L., Whiting, E., Jemtrud, M., & Valzano, V. (2005). A
Hierarchical 3D Reconstruction Approach for Documenting Complex Heritage Sites.
CIPA 2005 XX International Symposium, (January 2016). Retrieved from
http://nparc.cisti-icist.nrc-cnrc.gc.ca/npsi/ctrl?action=rtdoc&an=5765060

Ergun, B. (2010). A novel 3D geometric object filtering function for application in indoor area
with terrestrial laser scanning data. Optics and Laser Technology.
https://doi.org/10.1016/j.optlastec.2009.12.006

209 | Página

<!-- p. 210 -->

SIMÓN PEÑA VILLASENÍN

Eulitz, M., & Reiss, G. (2015). 3D reconstruction of SEM images by use of optical
photogrammetry software. Journal of Structural Biology, 191(2), 190–196.
https://doi.org/10.1016/j.jsb.2015.06.010

Fraser, C. S. (2013). Automatic Camera Calibration in Close Range Photogrammetry.
Photogrammetric Engineering & Remote Sensing, 79(4), 381–388.
https://doi.org/10.14358/PERS.79.4.381

Fritsch, B., Rinner, E., & Graßhoff, G. (2013). 3D Models of Ancient Sundials: A Comparison.
International Journal of Heritage in the Digital Era, 2(3), 361–373.
https://doi.org/10.1260/2047-4970.2.3.361

Fujii, Y., Fodde, E., Watanabe, K., & Murakami, K. (2009). Digital photogrammetry for the
documentation of structural damage in earthen archaeological sites: The case of Ajina
Tepa, Tajikistan. Engineering Geology. https://doi.org/10.1016/j.enggeo.2008.11.012

Furukawa, Y., & Ponce, J. (2010). Accurate, dense, and robust multiview stereopsis. IEEE
Transactions on Pattern Analysis and Machine Intelligence, 32(8), 1362–1376.
https://doi.org/10.1109/TPAMI.2009.161

Furukawa, Y., Curless, B., Seitz, S. M., & Szeliski, R. (2010). Towards internet-scale multi-view
stereo. In Proceedings of the IEEE Computer Society Conference on Computer Vision
and Pattern Recognition (pp. 1434–1441).
https://doi.org/10.1109/CVPR.2010.5539802

Gaitatzes, A., Christopoulos, D., & Roussou, M. (2001). Reviving the past: cultural heritage
meets virtual reality. In Proceedings of the 2001 conference on Virtual reality,
archeology, and cultural heritage (pp. 103–110). ACM.

Ganovelli, F., Corsini, M., Pattanaik, S., & Di Benedetto, M. (2014). Introduction to Computer
Graphics: A Practical Learning Approach.

Genovese, R. (2005). Architectural, archaeologic and environmental restoration planning
methodology: historic researches and techniques of survey aiming to conservation.
Proc. CIPA. Retrieved from
http://globalrestorationnetwork.org/uploads/files/LiteratureAttachments/39_archite
ctural-archaeologic-and-environmental-restoration-planning-methodology.pdf

Gil-Docampo, M., Ortiz-Sanz, J., Rego-Sanmartin, T., & Arza-Garcia, M. (2019). A World Wide
Web-Based Practice That Disseminates Photogrammetry: Inspiring Secondary
Students to Pursue Geomatics Careers [Education]. IEEE Geoscience and Remote
Sensing Magazine, 7(1), 86–97. https://doi.org/10.1109/MGRS.2018.2876565

Gil Docampo, M. L., Ortiz Sanz, J., Rego Sanmartín, T., & Arza García, M. (2019). A World Wide
Web-Based Practice That Disseminates Photogrammetry. Inspiring secondary students
to pursue geomatics careers. Retrieved from http://hdl.handle.net/10347/18498

210 | Página

<!-- p. 211 -->

BIBLIOGRAFÍA

Godfrey, B., & Eveleth, H. (2015). An adaptable approach for generating vector features from
scanned historical thematic maps using image enhancement and remote sensing
techniques in a geographic information system. Journal of Map and Geography
Libraries. https://doi.org/10.1080/15420353.2014.1001107

Gonizzi Barsanti, S., Remondino, F., & Visintini, D. (2013). 3D SURVEYING AND MODELING OF
ARCHAEOLOGICAL SITES &amp;ndash; SOME CRITICAL ISSUES &amp;ndash; ISPRS
Annals of Photogrammetry, Remote Sensing and Spatial Information Sciences, II-5/W1,
145–150. https://doi.org/10.5194/isprsannals-II-5-W1-145-2013

González-Aguilera, D., Muñoz-Nieto, A., Gómez-Lahoz, J., Herrero-Pascual, J., & Gutierrez-
Alonso, G. (2009). 3D Digital Surveying and Modelling of Cave Geometry: Application
to Paleolithic Rock Art. Sensors, 9(2), 1108–1127. https://doi.org/10.3390/s90201108

Grant, C. A., Johnston, M., Adam, C. J., & Little, J. P. (2019). Accuracy of 3D surface scanners
for clinical torso and spinal deformity assessment. Medical Engineering & Physics, 63,
63–71.

Greif, M., Greiner, C., Schenke, B., Schlichting, S., & Xu, Z. (2017). Collectivity in small systems
\- Initial state vs. final state effects, 25–35.
https://doi.org/10.1051/epjconf/201817205007

Grün, A., Remondino, F., & Zhang, L. I. (2004). Photogrammetric reconstruction of the great
buddha of Bamiyan, Afghanistan. Photogrammetric Record.
https://doi.org/10.1111/j.0031-868X.2004.00278.x

Grussenmeyer, P., Landes, T., Voegtle, T., & Ringle, K. (2008). Comparison methods of
terrestrial laser scanning, photogrammetry and tachometry data for recording of
cultural heritage buildings. The International Archives of the Photogrammetry, Remote
Sensing and Spatial Information Sciences., Vol. XXXVI, 213–218.

Grussenmeyer, P., Alby, E., Landes, T., Koehl, M., Guillemin, S., Hullo, J. F., et al. (2012).
Recording approach of heritage sites based on merging point clouds from high
resolution photogrammetry and Terrestrial Laser Scanning. International Archives of
the Photogrammetry, Remote Sensing and Spatial Information Sciences - ISPRS
Archives. https://doi.org/10.5194/isprsarchives-XXXIX-B5-553-2012

Guarnieri, A., Milan, N., & Vettore, A. (2013). Monitoring of complex structure for structural
control using terrestrial laser scanning (Tls) and photogrammetry. International
Journal of Architectural Heritage. https://doi.org/10.1080/15583058.2011.606595

Guidi, G., Beraldin, J. A., Ciofi, S., & Atzeni, C. (2003). Fusion of range camera and
photogrammetry: A systematic procedure for improving 3-D models metric accuracy.
IEEE Transactions on Systems, Man, and Cybernetics, Part B: Cybernetics.
https://doi.org/10.1109/TSMCB.2003.814282

211 | Página

<!-- p. 212 -->

SIMÓN PEÑA VILLASENÍN

Guidi, G., Beraldin, J.-A., & Atzeni, C. (2004). High-Accuracy 3-D Modeling of Cultural Heritage:
The Digitizing of Donatello’s “Maddalena.” IEEE Transactions on Image Processing,
13(3), 370–380. https://doi.org/10.1109/TIP.2003.822592

Gutierrez-Heredia, L., Benzoni, F., Murphy, E., & Reynaud, E. G. (2016). End to end digitisation
and analysis of three-dimensional coral models, from communities to corallites. PloS
One, 11(2), e0149641.

Harmon, J. (2008). Using Decorrelation Stretch to Enhance Rock Art Images. Society for
California Archaeology, 2008(11 November). Retrieved from
http://www.petroglyphs.us/article_using_decorrelation_stretch_to_enhance_rock_a
rt_images.htm

Harris, C., & Stephens, M. (1988). A Combined Corner and Edge Detector. In Procedings of the
Alvey Vision Conference 1988 (pp. 23.1-23.6). https://doi.org/10.5244/C.2.23

Heipke, C., Madden, M., Li, Z., & Dowman, I. (2016). Theme issue “State-of-the-art in
photogrammetry, remote sensing and spatial information science.” ISPRS Journal of
Photogrammetry and Remote Sensing, 115, 1–2.
https://doi.org/10.1016/j.isprsjprs.2016.03.006

Hollows, G., & Singer, S. (2009). Matching lenses and sensors. Vision System Design.

Ioannidis, Charalabos, Soile, S., & Verykokou, S. (2016). Low cost technique for accurate
geometric documentation of complex monuments by non-experts. In Lecture Notes in
Computer Science (including subseries Lecture Notes in Artificial Intelligence and
Lecture Notes in Bioinformatics). https://doi.org/10.1007/978-3-319-48496-9_6

Ioannidis, Charalambos, Potsiou, C., Soile, S., & Badekas, J. (2000). Detailed 3d
representations of archaeological sites. IAPRS, 33, B5.

Jalandoni, A., Domingo, I., & Taçon, P. S. C. (2018). Testing the value of low-cost Structure-
from-Motion (SfM) photogrammetry for metric and visual analysis of rock art. Journal
of Archaeological Science: Reports. https://doi.org/10.1016/j.jasrep.2017.12.020

Jamal, T., & Orbasli, A. (2008). Tourists in Historic Towns: Urban Conservation and Heritage
Management. APT Bulletin. https://doi.org/10.2307/4126422

Jiang, R., & Jauregui, D. V. (2007). A NOVEL NETWORK CONTROL METHOD FOR
PHOTOGRAMMETRIC BRIDGE MEASUREMENT. Experimental Techniques.
https://doi.org/10.1111/j.1747-1567.2007.00150.x

Johnson, R. A., & Solis, A. (2016). Using photogrammetry to interpret human action on
Neolithic monument boulders in Ireland’s Cavan Burren. Journal of Archaeological
Science: Reports, 8, 90–101. https://doi.org/10.1016/j.jasrep.2016.05.055

212 | Página

<!-- p. 213 -->

BIBLIOGRAFÍA

Karras, G. E., Mavromati, D., Madani, M., Mavrellis, G., Lymperopoulos, E., Kambourakis, A.,
& Gesafidis, S. (1999). Digital orthophotography in archaeology with low-altitude non-
metric images. International Archives of Photogrammetry and Remote Sensing,
32(5/W11), 8–11.

Karsli, F., Ayhan, E., & Tunc, E. (2003). Building 3D photo-texture model integrated with GIS
for architectural heritage conservation. In Proceedings of the XIXth International
Symposium, CIPA 2003: new perspectives to save cultural heritage: Antalya (Turkey),
30 September-04 October, 2003 (pp. 144–147). https://doi.org/10.4271/2010-01-0065

Kaufmann, V., & Ladstädter, R. (2007). Application of Terrestrial Photogrammetry for Glacier
Monitoring in Alpine Environments. Change, 2700, 813–818.

Keypoints, S., & Lowe, D. G. (2004). Distinctive Image Features from. International Journal of
Computer Vision, 60(2), 91–110.
https://doi.org/10.1023/B:VISI.0000029664.99615.94

Koban, K. C., Leitsch, S., Holzbach, T., Volkmer, E., Metz, P. M., & Giunta, R. E. (2014). 3D-
imaging and analysis for plastic surgery by smartphone and tablet: an alternative to
professional systems? Handchirurgie, Mikrochirurgie, Plastische Chirurgie: Organ Der
Deutschsprachigen Arbeitsgemeinschaft Fur Handchirurgie: Organ Der
Deutschsprachigen Arbeitsgemeinschaft Fur Mikrochirurgie Der Peripheren Nerven
Und Gefasse: Organ Der V..., 46(2), 97–104.

Kvamme, K. L., Ernenwein, E. G., & Markussen, C. J. (2006). Robotic total station for
microtopographic mapping: An example from the Northern Great Plains.
Archaeological Prospection. https://doi.org/10.1002/arp.270

Kwak, E., Detchev, I., Habib, A., El-badry, M., Asce, M., & Hughes, C. (2013). Precise
Photogrammetric Reconstruction Using Model-Based Image Fitting for 3D Beam
Deformation Monitoring. ASCE Journal of Surveying Engineering, Vol. 139(No. 3,
August), 143–155. https://doi.org/10.1061/(ASCE)SU.1943-5428.0000105.

Lacroix, V. (2009). Raster-to-vector conversion: problems and tools towards a solution a map
segmentation application. In Proceedings of the 7th International Conference on
Advances in Pattern Recognition, ICAPR 2009. https://doi.org/10.1109/ICAPR.2009.96

Lambers, K., Eisenbeiss, H., Sauerbier, M., Kupferschmidt, D., Gaisecker, T., Sotoodeh, S., &
Hanusch, T. (2007). Combining photogrammetry and laser scanning for the recording
and modelling of the Late Intermediate Period site of Pinchango Alto, Palpa, Peru.
Journal of Archaeological Science, 34(10), 1702–1712.
https://doi.org/10.1016/j.jas.2006.12.008

Lane, S. N., James, T. D., & Crowell, M. D. (2000). Application of Digital Photogrammetry to
Complex Topography for Geomorphological Research. The Photogrammetric Record,
16(95), 793–821. https://doi.org/10.1111/0031-868X.00152

213 | Página

<!-- p. 214 -->

SIMÓN PEÑA VILLASENÍN

Lato, M. J., Hutchinson, D. J., Gauthier, D., Edwards, T., & Ondercin, M. (2015). Comparison
of airborne laser scanning, terrestrial laser scanning, and terrestrial photogrammetry
for mapping differential slope change in mountainous terrain. Canadian Geotechnical
Journal. https://doi.org/10.1139/cgj-2014-0051

Lavy, A., Eyal, G., Neal, B., Keren, R., Loya, Y., & Ilan, M. (2015). A quick, easy and non-intrusive
method for underwater volume and surface area evaluation of benthic organisms by
3D computer modelling. Methods in Ecology and Evolution, 6(5), 521–531.
https://doi.org/10.1111/2041-210X.12331

Lejot, J., Delacourt, C., Piégay, H., Fournier, T., Trémélo, M. L., & Allemand, P. (2007). Very
high spatial resolution imagery for channel bathymetry and topography from an
unmanned mapping controlled platform. In Earth Surface Processes and Landforms.
https://doi.org/10.1002/esp.1595

Lerma-García, J. L. (2002). Fotogrametría Moderna.

Lerma, José L., Navarro, S., Seguí, A. E., & Cabrelles, M. (2014). Range-based versus
automated markerless image-based techniques for rock art documentation.
Photogrammetric Record, 29(145), 30–48. https://doi.org/10.1111/phor.12054

Lerma, José Luis, Navarro, S., Cabrelles, M., & Villaverde, V. (2010). Terrestrial laser scanning
and close range photogrammetry for 3D archaeological documentation: the Upper
Palaeolithic Cave of Parpalló as a case study. Journal of Archaeological Science, 37(3),
499–507. https://doi.org/10.1016/j.jas.2009.10.011

Lerones, P. M., Fernández, J. L., Gil, Á. M., Gómez-García-Bermejo, J., & Casanova, E. Z. (2010).
A practical approach to making accurate 3D layouts of interesting cultural heritage
sites through digital models. Journal of Cultural Heritage.
https://doi.org/10.1016/j.culher.2009.02.007

Lewis-Williams, J. D., & Pager, H. (1990). Documentation, Analysis and Interpretation:
Dilemmas in Rock Art Research. The South African Archaeological Bulletin, 45(152),
\126. https://doi.org/10.2307/3887979

Lodeiro-Pérez, J. M. (1995). Aplicaciones de la topografía en la documentación arquitectónica
y monumental. (Colegio Of).

López-Menchero Bendicho, V. M., Marchante Ortega, Á., Vincent, M. L., Cárdenas Martín-
Buitrago, Á. J., & Onrubia Pintado, J. (2017). Uso combinado de la fotografía digital
nocturna y de la fotogrametría en los procesos de documentación de petroglifos: el
caso de Alcázar de San Juan (Ciudad Real, España). Virtual Archaeology Review, 8(17),
64–74. https://doi.org/10.4995/var.2017.6820

214 | Página

<!-- p. 215 -->

BIBLIOGRAFÍA

López, J. A. B., Jiménez, G. A., Romero, M. S., García, E. A., Martín, S. F., Medina, A. L., &
Guerrero, J. A. E. (2016). 3D modelling in archaeology: The application of Structure
from Motion methods to the study of the megalithic necropolis of Panoria (Granada,
Spain). Journal of Archaeological Science: Reports.
https://doi.org/10.1016/j.jasrep.2016.11.022

Lowe, G. (2004). SIFT - The Scale Invariant Feature Transform. International Journal, 2, 91–
\110.

Mahmoud, A., & Bennett, M. (2015). Introducing 3-dimensional printing of a human anatomic
pathology specimen: potential benefits for undergraduate and postgraduate
education and anatomic pathology practice. Archives of Pathology & Laboratory
Medicine, 139(8), 1048–1051.

Mañana-Borrazás, P., & Santos-Estévez, M. (2002). Arte rupestre no promontorio de Corme
(Ponteceso). Gallaecia. Retrieved from http://digital.csic.es/handle/10261/54851

Mark, R., & Billo, E. (2002). Application of Digital Image Enhancement in Rock Art Recording.
American Indian Rock Art, 28, 121–128.

Martínez-Rodriguez, S., Ortiz-Sanz, J., Gil-Docampo, M. L., & Rego-Sanmartín, M. T. (2013).
Recording complex structures using close range photogrammetry: The cathedral of
santiago de compostela. Photogrammetric Record, 28(144), 375–395.
https://doi.org/10.1111/phor.12040

Martínez-Rodríguez, S., Ortiz-Sanz, J., & Gil-Docampo, M. L. (2015). Geometric
documentation of historical pavements using automated digital photogrammetry and
high-density reconstruction algorithms. Journal of Archaeological Science, 53, 1–11.
https://doi.org/10.1016/j.jas.2014.10.003

Martínez, S. (2012). Fotogrametría terrestre de objeto cercano en la documentaci?n 3D:
Revisi?n de casos. Spanish Journal of Rural Development, III(Special 3), 47–56.
https://doi.org/10.5261/2012.ESP3.06

Martínez, Santiago, Ortiz, J., Gil, M. L., & Rego, M. T. (2013). Recording complex structures
using close range photogrammetry: The cathedral of santiago de compostela.
Photogrammetric Record, 28(144), 375–395. https://doi.org/10.1111/phor.12040

Mas Cornellà, M., Maura Mijares, R., Solís Delgado, M., & Pérez González, J. (2010).
Reproducción digital, microfotografía estereoscópica y fotografía esférica aplicadas a
la interpretación del arte rupestre prehistórico. Cuadernos de Arte Rupestre: Revista
Del Centro de Interpretación de Arte Rupestre de Moratalla, ISSN 1699-0889, No. 6,
2013, Págs. 77-83, 6(6), 77–83. Retrieved from
https://dialnet.unirioja.es/servlet/articulo?codigo=5902470

215 | Página

<!-- p. 216 -->

SIMÓN PEÑA VILLASENÍN

Mason, S. (1994). Expert system based design of photogrammetric networks.
https://doi.org/10.3929/ETHZ-A-000943695

Massow, A. (2015). Online image vectorizer. Retrieved from https://www.vectorizer.io/

McPherron, S. P., Gernat, T., & Hublin, J. J. (2009). Structured light scanning for high-
resolution documentation of in situ archaeological finds. Journal of Archaeological
Science, 36(1), 19–24. https://doi.org/10.1016/j.jas.2008.06.028

Medici, P., & Rossi, G. (2015). Valcamonica 3.0: a new dimension in rock art recording. From
tracing to structure from motion and postprocessing. Research Perspectives On
Prehistoric Art. Pre-Proceedings of the XXVI Valcamonica Symposium, 9–12.

Meijer, E. (2015). Structure from Motion as documentation technique for Rock Art.
Adoranten. International Rock Art Magazine.

Micheletti, N., Chandler, J. H., & Lane, S. N. (2015). Investigating the geomorphological
potential of freely available and accessible structure‐from‐motion photogrammetry
using a smartphone. Earth Surface Processes and Landforms, 40(4), 473–486.

Mills, H. (2015). Use of mobile devices for e-learning in geomatics. The International Archives
of Photogrammetry, Remote Sensing and Spatial Information Sciences, 40(6), 5.

Moneva Montero, M. (1993). Primeros sistemas de reproducción de arte rupestre en España.
Espacio, Tiempo y Forma. Serie I. Prehistoria y Arqueología, 6, 413–441.

Mosbrucker, A. R., Major, J. J., Spicer, K. R., & Pitlick, J. (2017). Camera system considerations
for geomorphic applications of SfM photogrammetry. Earth Surface Processes and
Landforms, 42(6), 969–986.

Mudge, M., Malzbender, T., Schroer, C., Lum, M., & Schroer…, C. (2006). New Reflection
Transformation Imaging Methods for Rock Art and Multiple-Viewpoint Display. The 7th
International Symposium on Virtual Reality, Archaeology and Cultural Heritage
(VAST2006), 195–200. https://doi.org/10.2312/VAST/VAST06/195-202

Mudge, M., Schroer, C., Noble, T., Matthews, N., Rusinkiewicz, S., & Toler-Franklin, C. (2012).
Robust and Scientifically Reliable Rock Art Documentation from Digital Photographs.
In A Companion to Rock Art. https://doi.org/10.1002/9781118253892.ch36

Murtiyoso, A., Koehl, M., Grussenmeyer, P., & Freville, T. (2017). ACQUISITION AND
PROCESSING PROTOCOLS FOR UAV IMAGES: 3D MODELING OF HISTORICAL BUILDINGS
USING PHOTOGRAMMETRY. ISPRS Annals of Photogrammetry, Remote Sensing and
Spatial Information Sciences, IV-2/W2, 163–170. https://doi.org/10.5194/isprs-annals-
IV-2-W2-163-2017

216 | Página

<!-- p. 217 -->

BIBLIOGRAFÍA

Nikolov, I., & Madsen, C. (2016). Benchmarking close-range structure from motion 3D
reconstruction software under varying capturing conditions. In Lecture Notes in
Computer Science (including subseries Lecture Notes in Artificial Intelligence and
Lecture Notes in Bioinformatics) (Vol. 10058 LNCS, pp. 15–26).
https://doi.org/10.1007/978-3-319-48496-9_2

Ordóñez, C., Martínez, J., Arias, P., & Armesto, J. (2010). Measuring building façades with a
low-cost close-range photogrammetry system. Automation in Construction, 19(6),
742–749. https://doi.org/10.1016/j.autcon.2010.03.002

Orteu, J. J. (2009). 3-D computer vision in experimental mechanics. Optics and Lasers in
Engineering. https://doi.org/10.1016/j.optlaseng.2007.11.009

Ortiz-Sanz, J., Gil-Docampo, M. L., Martínez-Rodríguez, S., Sanmartín-Rego, M. T., & Meijide-
Cameselle, G. (2010). A simple methodology for recording petroglyphs using low-cost
digital image correlation photogrammetry and consumer-grade digital cameras.
Journal of Archaeological Science, 37(12), 3158–3169.
https://doi.org/10.1016/j.jas.2010.07.017

Ortiz-Sanz, J., Gil-Docampo, M., Meijide-Cameselle, G., Martínez-Rodríguez, S., & Rego-
Sanmartín, M. T. (2011). Modelado 3D de una estación completa de petroglifos
mediante escáner fotogramétrico de bajo coste: Pena de Chaos (Antas de Ulla, Lugo).
Férvedes: Revista de Investigación, 7, 115–120.

Ortiz, J, Núñez, R., & Rego, T. (2005). Use of Volumetric Targets To Improve Accuracy in
Architectural Photogrammetry At Low Cost. Engineering.

Ortiz, Juan, Gil, M. L., Martínez, S., Rego, T., & Meijide, G. (2013). Three-dimensional
Modelling of Archaeological Sites Using Close-range Automatic Correlation
Photogrammetry and Low-altitude Imagery. Archaeological Prospection, 20(3), 205–
\217. https://doi.org/10.1002/arp.1457

Otto, G., & Chau, T. (1989). “Region-growing” algorithm for matching of terrain images. Image
and Vision Computing, 7(2), 83–94. https://doi.org/10.1016/0262-8856(89)90001-2

Pappa, R. S., Giersch, L. R., & Quagliaroli, J. M. (2001). Photogrammetry of a 5m inflatable
space antenna with consumer-grade digital cameras. Experimental Techniques.
https://doi.org/10.1111/j.1747-1567.2001.tb00028.x

PBA. (2018). PLAN BÁSICO AUTONÓMICO DE GALICIA. ANEXO IX . LISTADO DE BENS DO
CATÁLOGO DE PATRIMONIO CULTURAL DE GALICIA DXOTU. Retrieved from
https://cmatv.xunta.gal/c/document_library/get_file?file_path=/portal-
cmaot/Documentos_SXOTU/PBA/20180827_10_Anexo_IX.II_BCPCG.pdf

La Peña-Santos, A. de. (1969). Las representaciones de alabardas en los grabados rupestres
gallegos. Zephyrus, 30/31, 115–129.

217 | Página

<!-- p. 218 -->

SIMÓN PEÑA VILLASENÍN

Peña-Villasenín, S., Gil-Docampo, M., & Ortiz-Sanz, J. (2017). 3-D Modelling of Historic
Facades Using SFM Photogrammetry Metric documentation of different building types
of a historic centre. International Journal of Architectural Heritage,
15583058.2017.1317884. https://doi.org/10.1080/15583058.2017.1317884

Peña-Villasenín, S., Gil-Docampo, M., & Ortiz-Sanz, J. (2018). Professional SfM and TLS vs a
simple SfM photogrammetry for 3D modelling of rock art and radiance scaling shading
in engraving detection. Journal of Cultural Heritage.
https://doi.org/10.1016/j.culher.2018.10.009

Peppa, M. V., Mills, J. P., Moore, P., Miller, P. E., & Chambers, J. E. (2016). Accuracy
assessment of a uav-based landslide monitoring system. In International Archives of
the Photogrammetry, Remote Sensing and Spatial Information Sciences - ISPRS
Archives. https://doi.org/10.5194/isprsarchives-XLI-B5-895-2016

Peres, M. R. (2013). The focal encyclopedia of photography. Taylor & Francis.

Pierrot Deseilligny, M., & Clery, I. (2012). Apero, an Open Source Bundle Adjusment Software
for Automatic Calibration and Orientation of Set of Images. ISPRS - International
Archives of the Photogrammetry, Remote Sensing and Spatial Information Sciences,
XXXVIII-5/(snavely), 269–276. https://doi.org/10.5194/isprsarchives-XXXVIII-5-W16-
269-2011

Pires, H., Rubio, J. M., & Arana, A. E. (2015). Techniques for revealing 3D hidden archeological
features: Morphological residual models as virtual-polynomial texture maps.
International Archives of the Photogrammetry, Remote Sensing and Spatial
Information Sciences - ISPRS Archives, 40(5W4), 415–421.
https://doi.org/10.5194/isprsarchives-XL-5-W4-415-2015

Potenziani, M., Callieri, M., Dellepiane, M., Corsini, M., Ponchio, F., & Scopigno, R. (2015).
3DHOP: 3D Heritage Online Presenter. Computers and Graphics (Pergamon), 52(April
2014), 129–141. https://doi.org/10.1016/j.cag.2015.07.001

Le Quellec, J. L., Duquesnoy, F., & Defrasne, C. (2015). Digital image enhancement with
DStretch®: Is complexity always necessary for efficiency? Digital Applications in
Archaeology and Cultural Heritage, 2(2–3), 55–67.
https://doi.org/10.1016/j.daach.2015.01.003

Remondino, F., & El-Hakim, S. (2006). Image-based 3D Modelling: A Review. The
Photogrammetric Record, 21(115), 269–291. https://doi.org/10.1111/j.1477-
9730.2006.00383.x

Remondino, F., Pizzo, S. Del, & Kersten, T. P. (2012). Progress in Cultural Heritage
Preservation, 7616(March). https://doi.org/10.1007/978-3-642-34234-9

218 | Página

<!-- p. 219 -->

BIBLIOGRAFÍA

Remondino, F., Spera, M. G., Nocerino, E., Menna, F., & Nex, F. (2014). State of the art in high
density image matching. The Photogrammetric Record, 29(146).
https://doi.org/10.1111/phor.12063

Resco, P. A., Barrero, J. D. C., Díaz, M. F., & Serrano, P. M. M. (2014). “Involuntary
Photogrammetry”: rescuing 3D geometric information from library pictures. Virtual
Archaeology Review, 5(10), 11–20.

De Reu, J., Plets, G., Verhoeven, G., De Smedt, P., Bats, M., Cherretté, B., et al. (2013a).
Towards a three-dimensional cost-effective registration of the archaeological heritage.
Journal of Archaeological Science, 40(2), 1108–1121.
https://doi.org/10.1016/j.jas.2012.08.040

De Reu, J., Plets, G., Verhoeven, G., De Smedt, P., Bats, M., Cherretté, B., et al. (2013b).
Towards a three-dimensional cost-effective registration of the archaeological heritage.
Journal of Archaeological Science, 40(2), 1108–1121.
https://doi.org/10.1016/j.jas.2012.08.040

De Reu, J., De Smedt, P., Herremans, D., Van Meirvenne, M., Laloo, P., & De Clercq, W. (2014).
On introducing an image-based 3D reconstruction method in archaeological
excavation practice. Journal of Archaeological Science, 41, 251–262.
https://doi.org/10.1016/j.jas.2013.08.020

Rodríguez Rellán, C., Vázquez Martínez, A., & Fábregas Valcarce, R. (2018). Cifras e imágenes:
una aproximación cuantitativa a los petroglifos gallegos. Trabajos de Prehistoria, 75
(1), 109–127.

Roelofs, R. (1950). Distortion, principal point, point of symmetry and calibrated principal
point. Photogrammetria, 7, 49–66.

Roncella, R., Re, C., & Forlani, G. (2012). Performance Evaluation of a Structure and Motion
Strategy in Architecture and Cultural Heritage. ISPRS - International Archives of the
Photogrammetry, Remote Sensing and Spatial Information Sciences, XXXVIII-
5/(March), 285–292. https://doi.org/10.5194/isprsarchives-xxxviii-5-w16-285-2011

Rusinkiewicz, S., Burns, M., & DeCarlo, D. (2006). Exaggerated shading for depicting shape
and detail. Acm Transactions on Graphics, 25(3), 1199–1205.
https://doi.org/http://doi.acm.org/10.1145/1141911.1142015

Ružić, I., Marović, I., Benac, Č., & Ilić, S. (2014). Coastal cliff geometry derived from structure-
from-motion photogrammetry at Stara Baška, Krk Island, Croatia. Geo-Marine Letters.
https://doi.org/10.1007/s00367-014-0380-4

Saito, T., & Takahashi, T. (1990). Comprehensible rendering of 3-D shapes. ACM SIGGRAPH
Computer Graphics. https://doi.org/10.1145/97880.97901

219 | Página

<!-- p. 220 -->

SIMÓN PEÑA VILLASENÍN

Salazar-Gamarra, R., Seelaus, R., da Silva, J. V. L., da Silva, A. M., & Dib, L. L. (2016).
Monoscopic photogrammetry to obtain 3D models by a mobile device: a method for
making facial prostheses. Journal of Otolaryngology-Head & Neck Surgery, 45(1), 33.

Santagati, C., & Inzerillo, L. (2013). 123D Catch: Efficiency, Accuracy, Constraints and
Limitations in Architectural Heritage Field. International Journal of Heritage in the
Digital Era, 2(2), 263–289. https://doi.org/10.1260/2047-4970.2.2.263

Santagati, C., Inzerillo, L., & Paola, F. Di. (2013). Image-based modeling techniques for
architectural heritage 3d digitalization: limits and potentialities. The International
Archives of …, XL(September), 2–6. https://doi.org/10.5194/isprsarchives-XL-5-W2-
555-2013

Santos-Estévez, M. (2015). Deer and Horses in Atlantic Rock Art: A Structural Analysis of
Iconography in the Landscape. Time and Mind, 8(3), 257–277.
https://doi.org/10.1080/1751696X.2015.1066128

Sanz-Ablanedo, E., Chandler, J. H., Rodríguez-Pérez, J. R., & Ordóñez, C. (2018). Accuracy of
Unmanned Aerial Vehicle (UAV) and SfM photogrammetry survey as a function of the
number and location of ground control points used. Remote Sensing.
https://doi.org/10.3390/rs10101606

Schneider, D., Schwalbe, E., & Maas, H. G. (2009). Validation of geometric models for fisheye
lenses. ISPRS Journal of Photogrammetry and Remote Sensing.
https://doi.org/10.1016/j.isprsjprs.2009.01.001

Scopigno, R., Callieri, M., Dellepiane, M., Ponchio, F., & Potenziani, M. (2017). Delivering and
using 3D models on the web: are we ready? Virtual Archaeology Review.
https://doi.org/10.1109/ICTON.2017.8024856

Shortis, M. R., Snow, W. L., & Goad, W. K. (1995). Comparative Geometric Tests of Industrial
and Scientific CCD Cameras using Plumb Line and Test Range Calibrations. International
Archives of the Photogrammetry, Remote Sensing and Spatial Information Sciences.

Simpson, A., Clogg, P., Díaz-Andreu, M., & Larkman, B. (2004). Towards three-dimensional
non-invasive recording of incised rock art. Antiquity, 78(301), 692–698.
https://doi.org/10.1017/S0003598X00113328

Skarlatos, D., & Kiparissi, S. (2012). Comparison of Laser Scanning, Photogrammetry and Sfm-
Mvs Pipeline Applied in Structures and Artificial Surfaces. ISPRS Annals of the
Photogrammetry, Remote Sensing and Spatial Information Sciences, I–3(September),
299–304. https://doi.org/10.5194/isprsannals-I-3-299-2012

Sloan, P.-P., Martin, W., Gooch, A., & Gooch, B. (2001). The Lit Sphere: A Model for Capturing
NPR Shading from Art. Proceedings of Graphics Interface 2001 (Ottawa, Canada, 7--9
June 2001). https://doi.org/http://doi.acm.org/10.1145/780986.781004

220 | Página

<!-- p. 221 -->

BIBLIOGRAFÍA

Snavely, N., Seitz, S., & Szeliski, R. (2006). Photo Tourism: Exploring Photo Collections in 3D.
SIGGRAPH Conference Proceedings, 835--846.
https://doi.org/10.1145/1141911.1141964

Snavely, N., Seitz, S. M., & Szeliski, R. (2008). Modeling the world from Internet photo
collections. International Journal of Computer Vision, 80(2), 189–210.
https://doi.org/10.1007/s11263-007-0107-3

Spetsakis, M., & Aloimonos, J. Y. (1991). A Multi-Frame Approach to Visual Motion
Perception. International Journal of Computer Vision, 6, 245–255.

Stavroulaki, M. E., Riveiro, B., Drosopoulos, G. A., Solla, M., Koutsianitis, P., & Stavroulakis, G.
E. (2016). Modelling and strength evaluation of masonry bridges using terrestrial
photogrammetry and finite elements. Advances in Engineering Software, 101, 136–
\148. https://doi.org/10.1016/j.advengsoft.2015.12.007

Steinberg, F. (1996). Conservation and rehabilitation of urban heritage in developing
countries. Habitat International. https://doi.org/10.1016/0197-3975(96)00012-4

Stojic, M., Chandler, J. H., Ashrnore, P., & Luce, J. (1998). The assessment of sediment
transport rates by automated digital photogrammetry. Photogrammetric Engineering
& Remote Sensing.

Strecha, C., Küng, O., & Fua, P. (2012). Automatic Mapping from Ultra-Light UAV Imagery.
EuroCOW 2012, 2–5.

Sturzenegger, M., & Stead, D. (2009). Close-range terrestrial digital photogrammetry and
terrestrial laser scanning for discontinuity characterization on rock cuts. Engineering
Geology. https://doi.org/10.1016/j.enggeo.2009.03.004

Sužiedelytė-Visockienė, J., Bagdžiūnaitė, R., Malys, N., & Maliene, V. (2015). CLOSE - RANGE
PHOTOGRAMMETRY ENABLES DOCUMENTATION OF ENVIRONMENT - INDUCED
DEFORMATION OF ARCHITECTURAL HERITAGE. Environmental Engineering and
Management Journal, 14(6), 1371–1381.

Szeliski, R, & Sing Bing, K. (1993). Recovering 3D shape and motion from image streams using
nonlinear least squares. In Computer Vision and Pattern Recognition, 1993.
Proceedings CVPR ’93., 1993 IEEE Computer Society Conference on (pp. 752–753).
https://doi.org/10.1109/CVPR.1993.341157

Szeliski, Richard, & Kang, S. B. (1994). Recovering 3d shape and motion from image streams
using nonlinear least squares. Journal of Visual Communication and Image
Representation. https://doi.org/10.1006/jvci.1994.1002

221 | Página

<!-- p. 222 -->

SIMÓN PEÑA VILLASENÍN

Teza, G., Pesci, A., & Ninfo, A. (2016). Morphological Analysis for Architectural Applications:
Comparison between Laser Scanning and Structure-from-Motion Photogrammetry.
Journal of Surveying Engineering, 142(3), 04016004.
https://doi.org/10.1061/(ASCE)SU.1943-5428.0000172

Tingdahl, D., & Van Gool, L. (2011). A Public System for Image Based 3{D} Model Generation.
Lecture Notes in Computer Science, 6930/2011, 262–273.

Triggs, B., McLauchlan, P. F., Hartley, R. I., & Fitzgibbon, A. W. (2000). Bundle Adjustment A
Modern Synthesis. In Vision Algorithms ’99 (Vol. 34099, pp. 298–372).
https://doi.org/10.1007/3-540-44480-7_21

Trinchão Andrade, B., Mazetto Mendes, C., de Oliveira Santos, J., Pereira Bellon, O. R., & Silva,
L. (2012). 3D preserving xviii century barroque masterpiece: Challenges and results on
the digital preservation of Aleijadinho’s sculpture of the Prophet Joel. Journal of
Cultural Heritage. https://doi.org/10.1016/j.culher.2011.05.003

Turner, D., Lucieer, A., & Wallace, L. (2014). Direct georeferencing of ultrahigh-resolution UAV
imagery. IEEE Transactions on Geoscience and Remote Sensing, 52(5), 2738–2745.
https://doi.org/10.1109/TGRS.2013.2265295

Tzedaki, V., & Kamara, J. M. (2013). Capturing As-Built Information for a BIM Environment
Using 3D Laser Scanner: A Process Model. Aei 2013, 486–495.
https://doi.org/10.1061/9780784412909.047

Unesco. (1972). Convención sobre la protección del patrimonio mundial , cultural y natural.
Unesco.

Uygun, F., Turan, M. H., & Ocalı, O. (2016). Photogrammetric evaluation options of an ancient
monument for different survey levels. Journal of Archaeological Science: Reports, 8,
200–205.

Uysal, M., Toprak, A. S., & Polat, N. (2015). DEM generation with UAV Photogrammetry and
accuracy analysis in Sahitler hill. Measurement, 73, 539–543.

Varela, J. M. V. (1982). Los petroglifos gallegos. Zephyrvs, 36.

Veiga, Y. S. (2005). Galician Rock Art, 5–19.

Vergne, R., Pacanowski, R., Barla, P., Granier, X., & Schlick, C. (2010). Radiance Scaling for
versatile surface enhancement. Proceedings of the ACM SIGGRAPH Symposium on
Interactive 3D Graphics and Games - I3D 10, 143.
https://doi.org/10.1145/1730804.1730827

222 | Página

<!-- p. 223 -->

BIBLIOGRAFÍA

Vergne, R., Pacanowski, R., Granier, X., Reuter, P., Vergne, R., Pacanowski, R., et al. (2018).
Enhancing surface features with the Radiance Scaling Meshlab Plugin To cite this
version : HAL Id : hal-00877158.

Vicente López, S. (2016). Mateo López y la planta de la iglesia monástica de San Martín Pinario
de Santiago. Archivo Español de Arte, 89(353), 85–94.
https://doi.org/10.3989/aearte.2016.07

Wackrow, R., & Chandler, J. H. (2008). A convergent image configuration for DEM extraction
that minimises the systematic effects caused by an inaccurate lens model.
Photogrammetric Record. https://doi.org/10.1111/j.1477-9730.2008.00467.x

Westoby, M. J., Brasington, J., Glasser, N. F., Hambrey, M. J., & Reynolds, J. M. (2012).
Structure-from-Motion photogrammetry: A low-cost, effective tool for geoscience
applications. Geomorphology, 179, 300–314.
https://doi.org/10.1016/j.geomorph.2012.08.021

Wilkinson, M. W., Jones, R. R., Woods, C. E., Gilment, S. R., McCaffrey, K. J. W., Kokkalas, S.,
& Long, J. J. (2016). A comparison of terrestrial laser scanning and structure-
frommotion photogrammetry as methods for digital outcrop acquisition. Geosphere,
12(6), 1865–1880. https://doi.org/10.1130/GES01342.1

Yang, J., Shi, Z. K., & Wu, Z. Y. (2016). Towards automatic generation of as-built BIM: 3D
building facade modeling and material recognition from images. International Journal
of Automation and Computing, 13(4), 338–349. https://doi.org/10.1007/s11633-016-
0965-7

Yastikli, N. (2007). Documentation of cultural heritage using digital photogrammetry and
laser scanning. Journal of Cultural Heritage, 8(4), 423–427.
https://doi.org/10.1016/j.culher.2007.06.003

Yilmaz, H. M., Yakar, M., Gulec, S. A., & Dulgerler, O. N. (2007). Importance of digital close-
range photogrammetry in documentation of cultural heritage. Journal of Cultural
Heritage, 8(4), 428–433. https://doi.org/10.1016/j.culher.2007.07.004

223 | Página

<!-- p. 224 -->


