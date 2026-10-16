---
type: libro
title: "Documentación y análisis geométrico del patrimonio arquitectónico a partir de métodos fotogramétricos con una y múltiples imágenes"
author: "Jesús Mª García Gago"
categoria: "Tesis doctorales y análisis"
paginas: 114
extraccion: "mixto: 8 páginas por OCR (eng)"
fuente: "local:E:/DISCIPLINAS, TEXTOS Y MAPAS/Biblioteca digital/Tesis doctorales y análisis/Documentación y análisis geométrico del patrimonio arquitectónico a partir de métodos fotogramétricos con una y múltiples imágenes.pdf"
convertido: 2026-10-13
---

# Documentación y análisis geométrico del patrimonio arquitectónico a partir de métodos fotogramétricos con una y múltiples imágenes

> Texto extraído de `Tesis doctorales y análisis/Documentación y análisis geométrico del patrimonio arquitectónico a partir de métodos fotogramétricos con una y múltiples imágenes.pdf` (114 páginas, mixto: 8 páginas por OCR (eng)). El PDF original está en el disco E: (DISCIPLINAS, TEXTOS Y MAPAS\Biblioteca digital); `<!-- p. N -->` marca el inicio de cada página.

<!-- p. 1 -->

DEPARTAMENTO DE INGENIERIA CARTOGRAFICA Y DEL TERRENO
ESCUELA POLITÉCNICA SUPERIOR DE ÁVILA

TESIS DOCTORAL
Documentación y análisis geométrico del
patrimonio arquitectónico a partir de
métodos fotogramétricos con una y
múltiples imágenes

Jesús Mª García Gago

Directores
Dr. Diego González Aguilera
Dr. Javier Gómez Lahoz

Ávila, Octubre 2014

<!-- p. 2 -->



<!-- p. 3 -->

Departamento de Ingeniería Cartográfica y del Terreno

Escuela Politécnica de Avila

Universidad de Salamanca

AUTOR:

Jesús Mª García Gago

DIRECTORES:

Dr. Diego González Aguilera Dr. Javier Gómez Lahoz

2014

<!-- p. 4 -->



<!-- p. 5 -->

La presente tesis doctoral corresponde a un compendio de 3 trabajos previamente
publicados que se especifican a continuación:

\1) Historical Single Image-Based Modeling: The Case of Gobierna Tower, Zamora
(Spain)

Jesús García-Gago 1, Javier Gómez-Lahoz 1, Javier Rodríguez-Méndez 2 and Diego
González-Aguilera 1

1 Departamento de Ingeniería Cartográfica y del Terreno, Escuela Politécnica de Ávila,
Universidad de Salamanca.

2 Departamento de Construcción y Agronomía, Área de Construcciones Arquitectónicas,
Escuela Politécnica de Zamora, Universidad de Salamanca.

Remote Sens. 2014, 6, 1085-1101; doi:10.3390/rs6021085

\2) A Photogrammetric and Computer Vision-Based Approach for Automated 3D
Architectural Modeling and Its Typological Analysis

Jesús García-Gago 1, Diego González-Aguilera 1, Javier Gómez-Lahoz 1 and Jesús Ignacio
San José-Alonso 2

1 Departamento de Ingeniería Cartográfica y del Terreno, Escuela Politécnica de Ávila,
Universidad de Salamanca.

2 Laboratorio de Fotogrametría Arquitectónica, Escuela Técnica Superior de
Arquitectura, Universidad de Valladolid.

Remote Sens. 2014, 6, 5671-5691; doi:10.3390/rs6065671

\3) Confronting passive and active sensors with Non-Gaussian statistic

Pablo Rodríguez-Gonzálvez, Jesús García-Gago, Javier Gómez-Lahoz and Diego
González-Aguilera

Departamento de Ingeniería Cartográfica y del Terreno, Escuela Politécnica de Ávila,
Universidad de Salamanca.

Sensors 2014, 14, 13759-13777; doi:10.3390/s140813759

<!-- p. 6 -->



<!-- p. 7 -->

“Documentación y análisis geométrico del patrimonio arquitectónico a partir de
métodos fotogramétricos con una y múltiples imágenes”,

Tesis Doctoral presentada por Jesús María García Gago
Informe de los Directores de Tesis

La Tesis Doctoral “Documentación y análisis geométrico del patrimonio arquitectónico
a partir de métodos fotogramétricos con una y múltiples imágenes”, presentada por
Jesús María García Gago, se inserta en la línea de investigación de documentación del
patrimonio arquitectónico por medio de técnicas fotogramétricas que pretenden
reunir tres factores críticos: automatización, consecución de modelos densos de alta
calidad geométrica y radiométrica y empleo para ello de medios de bajo coste.
Se trata de una línea muy activa y relevante en la comunidad internacional con
múltiples propuestas de mejora que se estimulan unas a otras gracias a lo cual
estamos viviendo un periodo que franco progreso de las Geotecnologías en este
campo en cuestión. El trabajo desarrollado se sitúa de forma significativa y eficaz en el
contexto de dichas aportaciones y logros con un alto grado de sintonía y de
contribución al avance del conocimiento científico y tecnológico.

Se trata asimismo de una línea de investigación promovida y desarrollada por un
Grupo de Investigación reconocido de la Universidad de Salamanca, que viene
desarrollando propuestas en el seno de Proyectos de Investigación competitivos y en
colaboración con otros grupos punteros a nivel nacional.
La Fotogrametría viene experimentando una serie de innovaciones de gran alcance
que han transformado profundamente su contexto hasta hacerla prácticamente
irreconocible respecto de lo que ofrecía tan sólo unos años atrás. Estas innovaciones
se articulan fundamentalmente en torno a la automatización de los procesos de
orientación y modelización de superficies con finalizado fotográfico, al empleo de
sistemas de bajo coste, tanto en la componente del equipo empleado como en la
metodología de documentación y procesamiento y, por último, en el imprescindible
control de calidad que debe llevarse a su máximo extremo cuando la automatización
está implicada y que cuestiona las convencionales y clásicas técnicas basadas en la
estadística gaussiana.
Además, en los últimos diez años, la Fotogrametría experimenta una estimulante
rivalidad con los logros aportados por el láser escáner. Esta competencia ha conducido
a que, lejos de quedarse rezagada respecto al mismo en la escena de la producción
cartográfica – como parecía que iba a ocurrir tan sólo cinco años atrás - se haya
situado en un horizonte muy prometedor en todos los contextos, pero muy
especialmente en el de la documentación arquitectónica y patrimonial.

<!-- p. 8 -->

La Tesis aborda un adecuado Estado de la Cuestión de manera que permite identificar
claramente la oportunidad estratégica de la aportación que se realiza como lo
demuestra el hecho de que la Tesis se articula en torno a la modalidad de compendio
de artículos publicados en revistas científicas y tecnológicas con impacto reconocido.
Estos artículos han verificado los correspondientes procesos de evaluación crítica y
revisión por parte de expertos internacionales de trayectoria reconocida. Estas
contribuciones se centran en:
• El análisis dimensional de edificios a partir de imágenes históricas y únicas
tomadas con cámaras desconocidas.
• La generación de modelos densos 3D con textura fotográfica mediante la
fotogrametría múltiple y convergente con el propósito de realizar estudios
tipológicos de la arquitectura religiosa popular.
• La comparación de modelos obtenidos mediante fotogrametría múltiple con los
obtenidos por láser escáner utilizando tanto métodos estadísticos clásicos
Gaussianos tanto como métodos robustos no paramétricos.
La Tesis concluye con el correspondiente apartado de Conclusiones en el que de forma
precisa y concreta se especifican las principales aportaciones realizadas de tal manera
que puedan ser objeto de crítica y de proyección hacia el desarrollo de futuros trabajos
integrados en línea de investigación.

En Ávila, a 24 de octubre de 2014,

Diego González Aguilera Javier Gómez Lahoz

<!-- p. 9 -->

AGRADECIMIENTOS

Quiero dar las gracias a todas las personas que me han acompañado en este

camino, ofreciéndome su apoyo, consejo y ánimo, y sin las que nada de esto habría

sido posible:

En primer lugar, a mis directores de tesis, Dr. D. Diego González Aguilera y Dr. D.

Javier Gómez Lahoz, no solo por compartir sus amplios conocimientos y experiencia

profesional, sino también por su entrega, dedicación, apoyo y ánimo en todo

momento. Gracias por vuestra infinita paciencia.

Al Dr. D. Jesús Ignacio San José Alonso, por guiarme en las primeras fases de la

investigación, y transmitirme su pasión por el dibujo y el patrimonio. Sus ideas,

consejos y todo el trabajo desarrollado en aquellos primeros pasos, han sido la

semilla de este trabajo.

Al Dr. D. Francisco Javier Rodríguez Méndez, por ser el “culpable“ de todo esto,

por confiar en mí hace más de diez años, por ayudarme con su experiencia y

ofrecerme su amistad, y por darme la oportunidad de divertirme cada día entre

rectas y planos. Espero seguir compartiendo despacho y proyectos durante muchos

años.

Además, a todos ellos y a Pablo Rodríguez Gonzálvez, como coautores de los

artículos aquí presentados, por su consentimiento para que éstos formen parte de

esta Tesis Doctoral.

Y por último a mis padres, por sembrar en mí la curiosidad y el deseo de aprender,

por ser ejemplo de humildad, generosidad y bondad, por apoyarme en todas las

decisiones de mi vida y seguir siendo mi guía y referencia.

A todos, gracias.

<!-- p. 10 -->



<!-- p. 11 -->

TABLA DE CONTENIDO

RESUMEN ............................................................................................................................

1 INTRODUCCIóN ......................................................................................................... 1

2 ESTADO DEL ARTE ..................................................................................................... 7

3 HIPóTESIS DE TRABAJO Y OBJETIVOS ...................................................................... 13

4 ARTÍCULOS CIENTÍFICOS.......................................................................................... 15

4.1 Historical Single Image-Based Modeling: The Case of Gobierna Tower, Zamora

(Spain).......................................................................................................................... 15

4.2 A Photogrammetric and Computer Vision-Based Approach for Automated 3D

Architectural Modeling and Its Typological Analysis .................................................. 35

4.3 Confronting passive and active sensors with Non-Gaussian statistic ............. 59

\5. CONCLUSIONES ....................................................................................................... 81

ANEXO - FACTOR DE IMPACTO DE LAS PUBLICACIONES ....................................................

<!-- p. 12 -->



<!-- p. 13 -->

Documentación y análisis geométrico del patrimonio arquitectónico a partir de métodos
fotogramétricos con una y múltiples imágenes

RESUMEN

El objetivo general de esta Tesis Doctoral es el desarrollo y aplicación de métodos
y procedimientos de trabajo que permitan generar una documentación geométrica
de un bien arquitectónico de una forma sencilla y eficiente, utilizando sistemas de
sensor remoto de bajo coste basados en técnicas de fotogrametría a partir de una y
múltiples imágenes. Para alcanzar este objetivo general hemos seguido tres líneas de
trabajo:
1 – Fotogrametría de una sola imagen o “single view”, mediante la cual
explotaremos las propiedades geométricas de una única fotografía oblicua para
obtener la geometría de un edificio, tema de especial relevancia cuando se trata de
un edificio desaparecido del que solo se conservan algunas fotografías antiguas.
2 – Fotogrametría múltiple mediante la cual obtendremos un modelo denso 3D a
partir de múltiples fotografías horizontales y convergentes, aplicado a la clasificación
tipológica de la arquitectura religiosa.
3 - Diagnóstico de la calidad (accuracy assessment) de los resultados de los
modelos densos 3D obtenidos mediante fotogrametría múltiple en comparación con
los obtenidos por láser escáner utilizando métodos estadísticos clásicos Gaussianos
y robustos no paramétricos.
Esta Tesis Doctoral se presenta como un compendio de tres artículos científicos
que han sido publicados en revistas científicas internacionales de impacto (ver
Anexo 1). Cada artículo desarrolla una de las tres líneas de trabajo fijadas:
• En el primer artículo se aborda el análisis dimensional y el modelado 3D de
un edificio desaparecido a partir de una única imagen antigua (histórica), la
Torre de Gobierna, perteneciente a la ciudad de Zamora.
• En el segundo desarrollaremos un método de trabajo que permite obtener
modelos densos 3D foto-realísticos mediante la fotogrametría múltiple
(horizontal y convergente), de los que se pueda generar la documentación
geométrica necesaria para realizar un estudio tipológico de la arquitectura
religiosa popular de los municipios fronterizos de la comarca de Aliste,
ubicadas en la provincia de Zamora.

<!-- p. 14 -->

Documentación y análisis geométrico del patrimonio arquitectónico a partir de métodos
fotogramétricos con una y múltiples imágenes

• En el tercero se compararán los modelos densos 3D obtenidos mediante
fotogrametría múltiple con los obtenidos por láser escáner utilizando tanto
métodos estadísticos clásicos Gaussianos tanto como métodos robustos no
paramétricos. Los casos de estudio se han realizado sobre dos iglesias de
estilo románico, las Iglesias de San Pedro y San Segundo, ubicadas en la
ciudad de Ávila.

<!-- p. 15 -->

Documentación y análisis geométrico del patrimonio arquitectónico a partir de métodos
fotogramétricos con una y múltiples imágenes

1 INTRODUCCIÓN

La protección del patrimonio arquitectónico responde a la necesidad de cualquier
sociedad de conservar sus valores culturales históricos y mantener vivas sus señas de
identidad cultural. El primer paso para esta protección es el conocimiento del objeto
arquitectónico, al que se llega a través de un proceso de investigación conocido como
documentación. Dentro de la documentación gráfica del patrimonio podemos
diferenciar dos tipos: la documentación no métrica, empleada a nivel divulgativo y
didáctico; y la documentación métrica, en la que se reflejan las medidas y la
representación geométrica a escala del patrimonio.
La documentación gráfica de un bien arquitectónico, debe de servir de soporte y
base para el desarrollo de investigaciones sobre el mismo, que facilitarán su gestión
y mantenimiento, favoreciendo su difusión y divulgación, acarreando a la larga un
aumento del interés y la participación de la población en su conservación.
Esta documentación gráfica conlleva dos fases bien diferenciadas. La primera es la
toma de datos, que se realiza en el edificio por medio de diferentes medios o
técnicas; y la segunda, consistente en plasmar esos datos en forma de dibujos u otros
tipos de documentos gráficos y que se suele realizar en el estudio.
En el II Congreso Internacional de Arquitectos y Técnicos de Monumentos
Históricos, celebrado en Venecia en 1964, se redacta la “Carta internacional sobre la
conservación y la restauración de monumentos y sitios (Carta de Venecia, 1964)”,
estableciendo los principios comunes que deben presidir la conservación y
restauración de monumentos, asociando a estos trabajos, “una documentación
precisa, en forma de informes analíticos y críticos, ilustrados con dibujos y
fotografías”. En este Congreso se funda el Consejo Internacional de Monumentos y
Sitios (ICOMOS), dedicado a promover la teoría, la metodología y las técnicas
científicas para la conservación, protección y mejora de monumentos y sitios. En
1968, este organismo celebra en Paris un coloquio internacional sobre las
“Aplicaciones de la Fotogrametría en monumentos históricos”, constituyéndose, en
colaboración con la Sociedad Internacional de Fotogrametría y Teledetección (ISPRS),
el CIPA (antiguo Comité Internacional de Fotogrametría Arquitectónica y actual

1

<!-- p. 16 -->

Documentación y análisis geométrico del patrimonio arquitectónico a partir de métodos
fotogramétricos con una y múltiples imágenes

Comité Internacional para la Documentación del Patrimonio Cultural). El objetivo de
este comité es fomentar y promover el desarrollo de principios y buenas prácticas
para el registro, documentación y gestión de la información del patrimonio cultural,
obtenidos por varios métodos, bajo la consideración especial de la fotogrametría.
Los métodos de toma de datos empleados a lo largo del tiempo, a excepción de
los métodos directos, efectuados con cinta o distanciómetro, exigían verdaderos
especialistas en la toma de datos, tanto para el uso de métodos topográficos como
fotogramétricos, además de equipos sofisticados. La fotogrametría clásica
estereoscópica, con la utilización de instrumentos sofisticados, complejos y caros
(cámaras métricas y restituidores) así como con su necesidad de obtener un apoyo
topográfico, dificultaba mucho a los técnicos intervinientes en la conservación del
patrimonio arquitectónico tanto el proceso de toma de datos como el procesamiento
de los mismos.
Pero en los últimos tiempos, a partir de la integración de la fotogrametría y la
visión computacional, aparecen nuevos sistemas y métodos que simplifican y
automatizan el proceso de la generación de modelos 3D a partir de fotografías
tomadas con cámaras convencionales, popularizando este método de toma de datos.
Es por esto que la fotogrametría se consolida como herramienta de bajo coste, al
alcance de todos, permitiendo acortar los tiempos de trabajo de campo y obteniendo
unos resultados de calidad, donde a la forma se le añade la información de textura y
color, condicionantes que hacen de este método de toma de datos un sistema
óptimo para la documentación gráfica arquitectónica.
Por ello, estudiaremos las aplicaciones de la fotogrametría en el campo de la
documentación patrimonial siguiendo tres líneas de trabajo:
1 – Fotogrametría de una sola imagen o “single view”, mediante la cual
explotaremos las propiedades geométricas una única fotografía oblicua para obtener
la geometría de un edificio o cualquier objeto que presente una forma regular y su
análisis dimensional, tema de especial relevancia cuando se trata de un edificio
desaparecido del que solo se conservan algunas fotografías antiguas.
Ya en el siglo XIX, Meydenbauer utilizó fotografías estereoscópicas para
documentar los elementos patrimoniales más importantes con el fin de que pudiesen
ser reconstruidos en el caso de destrucción, siendo utilizado su archivo de más de

2

<!-- p. 17 -->

Documentación y análisis geométrico del patrimonio arquitectónico a partir de métodos
fotogramétricos con una y múltiples imágenes

20.000 negativos en placas de vidrio para la reconstrucción de edificios después de
la Segunda Guerra Mundial. Pero por desgracia, la mayor parte de los edificios
desaparecidos no cuentan con este tipo de documentación estereográfica, y tan sólo
se conservan algunas fotografías aisladas.
Una línea de desarrollo reciente muy utilizada en el contexto de la Documentación
del Patrimonio Arquitectónico ha sido la rectificación. En los tiempos analógicos de
la fotogrametría se trataba de un proceso ingrato pues implicaba la reproducción
fotográfica del objeto en cuestión, eliminando de la misma los efectos de
perspectiva. Sin embargo, tras la digitalización de la imagen representa un proceso
sencillo, rápido, con resultados satisfactorios y al alcance de personas sin ninguna
formación previa al respecto. Como es bien sabido, su principal limitación es que
requiere que el objeto sea bidimensional, esto es, resulta aplicable al caso de
fachadas arquitectónicas pero no a objetos articulados o con relieve.
Varios autores han propuesto enfoques y métodos basados en la geometría de una
sola vista basados en el conocimiento, aunque sea de forma parcial, de determinadas
propiedades geométricas del objeto. Sin embargo, sólo unos pocos se han centrado
en el caso del modelado de edificios demolidos mediante una fotografía histórica,
aspecto que presenta una tarea difícil al ser completamente desconocido el tipo y la
geometría de la cámara, siendo en ocasiones imposible la evaluación de los
resultados debido a la inexistencia del edificio.
En esta línea de investigación realizaremos el análisis dimensional y el modelado
3D de un edificio desaparecido del que sólo se conservan algunas fotografías
históricas aprovechando las propiedades geométricas de la toma fotográfica oblicua,
del propio edificio y la potencia del cálculo del software sv3DVision (GonzalezAguilera y Gomez-Lahoz, 2008), desarrollado en 2005 en la Universidad de Salamanca
y que automatiza el proceso.
2 – Fotogrametría múltiple mediante la cual obtendremos un modelo denso 3D a
partir de múltiples fotografías (convergentes y paralelas), aplicado a la clasificación
tipológica de la arquitectura religiosa rural de los municipios fronterizos de la
comarca de Aliste ubicados en la provincia de Zamora.
La fotogrametría ha sido ampliamente utilizada en la documentación
arquitectónica, desde métodos simples de rectificación fotográfica para superficies

3

<!-- p. 18 -->

Documentación y análisis geométrico del patrimonio arquitectónico a partir de métodos
fotogramétricos con una y múltiples imágenes

planas, como ya se ha comentado, hasta la fotogrametría clásica basada en pares
estereoscópicos, orientados mediante puntos de apoyo topográfico, para crear un
modelo estereoscópico sobre el que el operador puede capturar detalles específicos
tridimensionales o crear curvas de nivel para representar el relieve. Bajo el
paradigma analógico, este proceso requería de restituidores sofisticados de difícil
manejo, coste elevado y con resultados en soporte duro (papel o película) pero con
la digitalización de la Fotogrametría, la técnica ha experimentado un proceso de
simplificación y de mejora considerable en la calidad y versatilidad del resultado.
Cabe mencionar que esta digitalización permitió en su momento la entrada, en el
sistema de producción cartográfica, de imágenes múltiples y oblicuas que rebasaban
la tradicional configuración estereoscópica clásica lo que facilitaba mucho la fase de
adquisición. Sin embargo, en su etapa inicial, este planteamiento requería de la
captura manual de todos los detalles a modelizar.
La aparición de los sistemas basados en láser escáner terrestre ha revolucionado
la adquisición 3D masiva de datos en tiempo real, datos que además pueden ir
acompañados de valores radiométricos mediante la integración de color verdadero
con una cámara fotográfica o el propio valor de intensidad del láser, obteniendo una
nube de puntos 3D foto-realística o de intensidades, respectivamente. Pero el alto
coste de los equipos y del software asociado así como la especialización de los
operadores, hacen que este sistema esté al alcance de muy pocos.
En los últimos años hemos presenciado una popularización en el uso de la
fotogrametría con la aparición de la fotogrametría a partir de múltiples imágenes,
gracias a la automatización en el proceso de orientación y el propio proceso de
reconstrucción, obteniendo en este último caso modelos tridimensionales densos
con acabado foto-realístico, que vienen a superar en muchos casos la propia
resolución de los sistemas láser. Además, se garantiza una mayor flexibilidad en la
toma de las imágenes, ya que permiten trabajar con cualquier tipo de imágenes, no
solo la clásica imagen vertical/horizontal estereoscópica, sino también imágenes
oblicuas y múltiples convergentes e incluso con cualquier tipo de cámara, calibrada
y no calibrada. Todo ello sumado a la precisión y fiabilidad de los resultados, hacen
que la fotogrametría basada en múltiples imágenes se desmarque como un serio
competidor de bajo coste de los sistemas láser.

4

<!-- p. 19 -->

Documentación y análisis geométrico del patrimonio arquitectónico a partir de métodos
fotogramétricos con una y múltiples imágenes

En esta línea de investigación realizaremos mediante fotogrametría múltiple los
modelos densos 3D con acabado foto-realístico de los edificios religiosos de la zona
de estudio, que nos permitan posteriormente obtener la documentación gráfica
necesaria para realizar un estudio tipológico.
3 - Diagnóstico de la calidad (accuracy assessment) de los resultados de los
modelos densos 3D obtenidos mediante fotogrametría múltiple en comparación con
los obtenidos por los sistemas láser escáner terrestre utilizando métodos estadísticos
clásicos Gaussianos y robustos no paramétricos.
Durante la segunda mitad de la década pasada, los potentes sistemas de escáner
láser utilizados para la documentación del patrimonio, tanto los de tiempo de vuelo
como los de diferencia de fase, parecen establecerse como una tecnología
inalcanzable para la fotogrametría clásica, anclada en esta carrera tecnológica. Pero
la aparición en los últimos años de la fotogrametría a partir de múltiples imágenes
ha supuesto una autentica resurrección de las técnicas fotogramétricas, gracias a su
alianza con la visión computacional.
La automatización, tanto en el proceso de orientación de las imágenes como en la
reconstrucción, generando modelos tridimensionales densos con resoluciones
similares a las de los sistemas laser, así como posibilidad de utilizar cualquier tipo de
cámara fotográfica y cualquier tipo de toma, han contribuido en popularizar este
método. Cabe destacar como parte de esta popularización de la fotogrametría
múltiple, la proliferación de herramientas de código abierto, de coste reducido o
incluso gratuitas que permiten afrontar este paso del 2D al 3D utilizando sólo
imágenes.
Esta tercera línea de trabajo tendrá dos objetivos: en primer lugar, comparar los
Modelos Digitales de Superficie (DSM) obtenidos por fotogrametría múltiple
mediante sistemas de sensores remotos pasivos (cámara digital) y activos (láser
escáner terrestre), aplicada a objetos arquitectónicos específicos, en concreto a las
portaladas románicas de San Pedro y San Segundo de Ávila. En segundo lugar, poner
a prueba cómo se adaptan las estadísticas clásicas Gaussianas, con su principio de
Mínimos Cuadrados, a los conjuntos de datos donde pueden aparecer errores
groseros asimétricos y si este enfoque se debe cambiar por uno no paramétrico.
Debe tenerse en cuenta que la automatización en el procesamiento de los datos

5

<!-- p. 20 -->

Documentación y análisis geométrico del patrimonio arquitectónico a partir de métodos
fotogramétricos con una y múltiples imágenes

conlleva la presencia de múltiples errores groseros que deben provocar que dichos
datos no se ajusten al modelo de una población normal.

6

<!-- p. 21 -->

Documentación y análisis geométrico del patrimonio arquitectónico a partir de métodos
fotogramétricos con una y múltiples imágenes

2 ESTADO DEL ARTE

La documentación gráfica del patrimonio arquitectónico se ha venido realizando
tradicionalmente por métodos directos, mediante croquis o fotografías combinados
con cintas métricas o distanciometros, o mediante técnicas topográficas y
fotogramétricas. Cuando se trata de trabajos rigurosos, predominan los
levantamientos fotogramétricos con apoyo topográfico.
La fotogrametría, traducido etimológicamente como “la medida de lo escrito con
luz”, permite la obtención de información tridimensional del objeto a partir de
medidas realizadas en fotografías.
La fotogrametría arquitectónica ha sido utilizada para la documentación
patrimonial basándose en imágenes estereoscópicas y rectificaciones fotográficas,
utilizando cámaras métricas y restituidores, primero de forma analógica, hasta la
llegada de la era digital, al principio de 1990.
Como ventajas de la fotogrametría podemos destacar la posibilidad de obtener
datos métricos sin tener contacto con el objeto, proporciona gran cantidad de datos
a diferentes escalas y con alta precisión métrica y que el uso de las fotografías
proporciona información de la textura del objeto.
La desventaja más significativa de la fotogrametría convencional sería el uso de
instrumental muy específico y operadores expertos y la necesidad de obtener puntos
de apoyo mediante técnicas topográficas.
La aparición de los sistemas basados en láser escáner terrestre a principios del
siglo XXI revolucionó el sector de la documentación patrimonial. Estos instrumentos
son sensores activos, bien sean basados en tiempo de vuelo o diferencia de fase, y
permiten la adquisición masiva de coordenadas 3D, obteniendo una nube de puntos,
más o menos densa en función de la resolución requerida, en tiempo real.
La adquisición masiva de datos supuso un cambio en el concepto de
documentación y rápidamente aparecieron seguidores y detractores de este nuevo
procedimiento. Los primeros veían en este sistema un paso más hacia la utopía del
dibujo automático mientras que los segundos defendían la toma selectiva e
interpretada de datos, que obliga a una simplificación del objeto basada en una
selección de los elementos más significativos, facilitando la comprensión del

7

<!-- p. 22 -->

Documentación y análisis geométrico del patrimonio arquitectónico a partir de métodos
fotogramétricos con una y múltiples imágenes

elemento a documentar.
Su uso es adecuado en levantamientos de grandes dimensiones, con geometría
compleja, de elementos con relieve, como retablos, bóvedas, portaladas, etc… Pero
a pesar de que algunas de sus desventajas se van aminorando, como el peso y las
dimensiones de los equipos, su autonomía (batería y equipo informático externo) y
aunque el coste de los equipos va descendiendo, todavía continúa siendo elevado,
así como el software necesario para el procesamiento de los datos. Esto, sumado a
la necesaria especialización de los operadores, hace que este sistema no esté al
alcance de cualquier usuario.
La auténtica revolución en la documentación del patrimonio ha venido en los
últimos años de la mano de la fotogrametría a partir de múltiples imágenes, que
obtiene productos similares a los obtenidos mediante los sistemas laser, pero sin los
inconvenientes de éste y bajo las exigencias de máxima calidad que han sido siempre
la filosofía de la fotogrametría.
De esta forma, desaparecen las mayores desventajas de la fotogrametría mediante
el uso masivo de material digital y cámaras digitales, de mayor resolución y menor
coste, software de bajo coste y fácil manejo y el menor uso de apoyo topográfico. Así
aparece el término de “fotogrametría de bajo coste” o “fotogrametría para todos”,
acercando el proceso de documentación arquitectónica a cualquier técnico
interviniente en la conservación del patrimonio.
El procesamiento de múltiples imágenes para generar modelos geométricos y
radiométricos 3D requiere la resolución de dos cuestiones previas de gran
importancia geométrica en fotogrametría: conocer los parámetros internos de la
cámara (distancia principal o focal, coordenadas del punto principal y parámetros de
distorsión de las lentes) junto con sus parámetros externos (posición espacial y
angular) (Robertson and Cipolla, 2009).
1 - La orientación interna o calibración de la cámara:
Consiste en la reconstrucción del haz perspectivo, o lo que es lo mismo, determinar
los parámetros internos de la cámara: distancia principal o focal, coordenadas del
punto principal y parámetros de distorsión de las lentes.
En sistemas de una sola imagen, se puede resolver la orientación interna,
estableciendo restricciones geométricas (planeidad, ortogonalidad y paralelismo),

8

<!-- p. 23 -->

Documentación y análisis geométrico del patrimonio arquitectónico a partir de métodos
fotogramétricos con una y múltiples imágenes

características frecuentes en los objetos arquitectónicos, a partir de la pirámide
perspectiva, cuya base está formada por los tres puntos de fuga y el punto principal
el vértice y la longitud focal, la altura de la pirámide.
Durante años la fotogrametría clásica ha conseguido resolver este paso mediante
la aplicación de rigurosos procesos de calibración de laboratorio y/o campo junto con
la existencia de una red bien distribuida de puntos de paso y apoyo.
2 - La orientación externa:
Consiste en la reconstrucción de la posición y orientación del haz perspectivo
respecto del objeto, orientando los haces perspectivos entre sí (orientación relativa)
y posteriormente situándolos respecto al objeto (orientación absoluta)
El cálculo de los ángulos y la posición de la cámara a partir de una sola imagen, se
obtienen a partir de la pirámide perpectiva utilizada anteriormente en la orientación
interna, para el cálculo de los ángulos de rotación, mientras que el origen y la escala
requiere información de la geometría del objeto apoyada por restricciones
geométricas (coplanaridad y paralelismo).
En la fotogrametría con múltiples imágenes, la orientación relativa entre las
imágenes o la orientación externa de cada una de las imágenes respecto del sistema
de referencia, se resuelven aplicando la condición de colinealidad (Kraus, 1993), que
establece que la recta que une cada punto imagen con su correspondiente punto
objeto pasa por el centro de proyección de la cámara en el momento de toma. La
resolución múltiple de la orientación externa de todas las imágenes que conforman
la toma se resuelve mediante el procedimiento de Ajuste de Haces heredado de los
procedimientos habituales de Aerotriangulación. La orientación absoluta, necesaria
tras la orientación relativa, se resuelve bien mediante el uso de puntos de apoyo
expresados en el sistema de coordenadas de referencia o bien mediante la definición
explícita de dicho sistema de referencia a través de la identificación sobre las
imágenes de un origen, la dirección de los ejes cartesianos y el establecimiento de
una escala, lo que implica necesariamente la determinación de al menos una
distancia sobre el objeto. Mediante la intersección de los rayos correspondientes
obtendremos las coordenadas en el modelo, que nos permitirá reconstruir el modelo
3d o simplemente realizar un análisis dimensional-métrico del objeto o escenario.
En los desarrollos recientes es práctica habitual que orientación externa e interna

9

<!-- p. 24 -->

Documentación y análisis geométrico del patrimonio arquitectónico a partir de métodos
fotogramétricos con una y múltiples imágenes

se resuelvan simultáneamente en el denominado proceso de Autocalibración. Es
también posible que estos dos procesos se integren con el proceso de cálculo del
propio modelo 3D, integrando éste en el proceso de Ajuste de Haces mencionado.
Para ello se requiere previamente la extracción y matching de puntos homólogos
entre las imágenes.
Las estrategias robustas de matching múltiple basado en características (FBMFeature Based Matching) y áreas (ABM- Area Based Matching) desarrolladas en los
últimos años permiten vincular las imágenes entre sí y obtener la orientación relativa
de las imágenes, así como una nube dispersa, correspondiente a los puntos extraídos
del matching (Hartley and Zisserman, 2003).
Posteriormente podemos proceder a la intersección múltiple directa basada en la
condición de colinealidad, que nos permitirá la reconstrucción del modelo 3D o
simplemente su análisis métrico-dimensional.
Aquí también se han conseguido grandes progresos en los últimos años gracias a
las técnicas de matching. El potente semi-global matching (SGM) (Hirschmüller,
2008), que ha permitido generar modelos 3D densos con resoluciones iguales al GSD
(Ground Sample Distance) de la imagen, es decir un punto en el terreno por cada
pixel de la imagen, aunque depende de una geometría favorable. Apero-Micmac
(Deseilligny, 2010) como software libre es un buen ejemplo junto con herramientas
fotogramétricas comerciales (eATE, NGATE,Dense Matcher, ISAE, Match-T, Xpro,
Tridicon, etc).
Existen otros logros importantes en el caso de la geometría desfavorable, como
los patch-based methods basados en surfels (Seitz et al., 2006; Lhuillier and Quan,
2005; Habbecke and Kobbelt, 2006). Así, el Patch-based Multi-View Stereo (PMVS)
(Furukawa and Ponce, 2009) utiliza un acercamiento híbrido, usando imágenes sin
distorsiones, parámetros de orientación de las imágenes, un conjunto escaso de
puntos y las matrices de proyección para obtener un conjunto denso de small
oriented rectangular patches a nivel de pixel. Además incorpora un filtrado por
visibilidad que le permite ser robusto y eliminar falsos puntos de matching.
Sin embargo, el mayor inconveniente que tienen este tipo de herramientas,
comercial and web-based tools (Bundler, Photosynth, Photofly Insight3D, 123Catch)
es que se sustentan en algoritmos de visión computacional que calculan la

10

<!-- p. 25 -->

Documentación y análisis geométrico del patrimonio arquitectónico a partir de métodos
fotogramétricos con una y múltiples imágenes

orientación de las imágenes por modelos independientes y con parámetros internos
diferentes para cada imagen, lo que se aleja de la orientación rigurosa por ajuste de
haces (bundle adjustment) que aplica la fotogrametría sustentada en unos
parámetros internos previamente calibrados, no arrojando la calidad esperada.
También podemos destacar como inconveniente de estos métodos basados en la
web, su coste computacional, sobre todo si trabajamos con un gran número de
imágenes de alta resolución.
Los productos obtenidos mediante la fotogrametría a partir de múltiples
imágenes, modelos tridimensionales densos con acabado foto-realístico, superan en
muchos casos la propia resolución de los sistemas láser, sin olvidar la precisión y
fiabilidad de los resultados al estar basada en técnicas fotogramétricas. Si a ello le
sumamos la flexibilidad en la toma de las imágenes, el uso de cualquier tipo de
cámara, la aparición de herramientas software con un coste reducido e incluso
gratuito y de código abierto, así como la automatización del proceso, tanto de
orientación como de reconstrucción, convierten a la fotogrametría a partir de
múltiples imágenes en un método idóneo para la documentación patrimonial.
Los modelos tridimensionales densos obtenidos no están libres de errores, pues
pueden contener falsas correspondencias surgidas durante el proceso de matching.
Cuando se trata de comparar modelos obtenidos mediante fotogrametría a partir de
múltiples imágenes y modelos obtenidos mediante escáner láser, hay que tener en
cuenta que ambos sistemas tienen sus propias fuentes de error, además de que los
puntos en ambos sistemas no son los mismos y que no todas las superficies de los
objetos son capturadas por igual en los dos métodos, pues las posiciones de ambos
sensores no son las mismas. Por todo ello, los errores groseros asociados a los
conjuntos de datos aumenta, mostrando asimetría en ambos sistemas.
La comparación de la calidad de los modelos obtenidos mediante sistemas laser y
mediante fotogrametría de múltiples imágenes, se ha realizado tradicionalmente
mediante métodos estadísticos clásicos Gaussianos, con su principio de mínimos
cuadrados.
Pero la asimetría existente debida a la presencia de errores groseros, sugiere que
los parámetros normales estándar no son adecuados para evaluar este tipo de datos,
sobre todo cuando la precisión es de suma importancia, mientras que la estadística

11

<!-- p. 26 -->

Documentación y análisis geométrico del patrimonio arquitectónico a partir de métodos
fotogramétricos con una y múltiples imágenes

basada en métodos robustos no paramétricos, arroja unos resultados que cumplen
con lo que cabría esperar en relación con la evaluación de la exactitud.

12

<!-- p. 27 -->

Documentación y análisis geométrico del patrimonio arquitectónico a partir de métodos
fotogramétricos con una y múltiples imágenes

3 HIPÓTESIS DE TRABAJO Y OBJETIVOS

Se establecen tres hipótesis de trabajo en la presente Tesis Doctoral:
\1. Se puede obtener medidas de un edificio desaparecido explotando las
propiedades geométricas de una sola fotografía antigua.
\2. Mediante la fotogrametría múltiple podemos obtener modelos densos 3D que
permitirán generar la documentación necesaria para realizar un estudio
tipológico de la arquitectura religiosa de una zona determinada.
\3. Los resultados obtenidos con la fotogrametría son equiparables a los obtenidos
con el láser escáner terrestre.

Los objetivos a alcanzar seguirán las líneas de trabajo propuestas:
1 – Desarrollar un método que permita la obtención de la geometría y análisis
dimensional de un edificio histórico desaparecido a partir de una única imagen
antigua y generar su modelo 3D.
Utilizaremos como caso de estudio la “Torre de la Gobierna”, una de las torres que
se elevaba en la margen izquierda del puente de piedra de Zamora y que fue
demolida en la reforma de 1905. El caso de estudio es significativo pues formaría
parte de una posible reconstrucción del puente de piedra de la ciudad que
respondería a una demanda popular basada en motivos sociales y culturales
relacionados con la identidad de la sociedad zamorana.
2 – Desarrollar un método de trabajo que permita obtener modelos densos 3D
mediante la fotogrametría múltiple, de los que se pueda generar la documentación
geométrica necesaria para realizar un estudio tipológico de la arquitectura religiosa
popular de los municipios fronterizos de la comarca de Aliste (Zamora), siguiendo la
línea de trabajo de Jesús Ignacio San José Alonso en relación con la Arquitectura
Religiosa en Sanabria (San José, 1994), en la cual analiza los espacios, organizaciones
y tipologías de las iglesias de la comarca sanabresa, partiendo de una documentación
gráfica obtenida mediante métodos directos de medición.
Se desarrollará una metodología de trabajo que permita abordar un estudio de
estas características, en el cual se necesita generar la documentación gráfica de un
gran número de edificaciones, de una forma fácil y rápida, con reducción de los

13

<!-- p. 28 -->

Documentación y análisis geométrico del patrimonio arquitectónico a partir de métodos
fotogramétricos con una y múltiples imágenes

tiempos de trabajo de campo pero sin perder calidad y mediante métodos de bajo
coste.
Se ha elegido esta zona por su situación periférica, tanto geográfica como
socioeconómica a lo largo de la historia y por la proximidad con la comarca
sanabresa, de la cual existen estudios anteriores en la misma línea con los que poder
establecer estudios comparativos de las tipologías de los edificios religiosos.
3 – Realizar una comparación de los modelos obtenidos por fotogrametría múltiple
y los obtenidos por láser escáner terrestre utilizando métodos estadísticos clásicos
Gaussianos y robustos no paramétricos.
Se someterán a comparación los modelos obtenidos por diferentes métodos y
sensores de las portaladas románicas de San Pedro y San Segundo de Ávila.
Se realizarán modelos densos 3D obtenidos mediante diferentes tipos de sensores:
dos tipos sensores activos láser (tiempo de vuelo y diferencia de fase) y dos sensores
pasivos (dos cámaras fotográficas digitales reflex), utilizando para estos últimos dos
programas fotogramétricos diferentes (Agisoft y PW-Photogrammetry Workbench)
para obtener el modelo denso. Es decir, un total de seis modelos tridimensionales
por cada una de las portaladas analizadas.

14

<!-- p. 29 -->

Documentación y análisis geométrico del patrimonio arquitectónico a partir de métodos
fotogramétricos con una y múltiples imágenes

4 ARTÍCULOS CIENTÍFICOS

4.1 HISTORICAL SINGLE IMAGE-BASED MODELING: THE CASE OF GOBIERNA
TOWER, ZAMORA (SPAIN)

Resumen: Las imágenes históricas con perspectiva han demostrado ser muy útiles
para proporcionar adecuadamente un análisis dimensional de fachadas de edificios
o, incluso generar una reconstrucción parcial a partir de imágenes rectificadas de
todo el elemento. En este trabajo, se analiza el caso de la Torre de la Gobierna
(Zamora, España) a partir de un enfoque de modelado basado en una única fotografía
antigua. En particular, aprovechando las ventajas de la perspectiva de la imagen la
existencia de los tres puntos de fuga y las restricciones geométricas habituales
(planeidad, ortogonalidad y paralelismo), se lleva a cabo el análisis dimensional y la
reconstrucción parcial de un edificio histórico desaparecido. Los resultados fueron
comparados con la verdad terreno de mediciones de existentes en un antiguo
levantamiento topográfico, obteniendo discrepancias de aproximadamente un 1%.
Palabras clave: fotografías históricas; una sola imagen; puntos de fuga; edificios
demolidos; perspectiva

15

<!-- p. 30 -->



<!-- p. 31 -->

Remote Sens. 2014, 6, 1085-1101; doi:10.3390/rs6021085
OPEN ACCESS
remote sensing
ISSN 2072-4292
www.mdpi.com/journal/remotesensing
Case Report

Historical Single Image-Based Modeling: The Case of
Gobierna Tower, Zamora (Spain)

Jesús Garcia-Gago 1, Javier Gomez-Lahoz 1, Javier Rodríguez-Méndez 2
and Diego González-Aguilera 1,*

1 Department of Cartographic and Terrain Engineering, Polytechnic School of Avila,
University of Salamanca, Hornos Caleros 50, Avila 05003, Spain;
E-Mails: jesusmgg@usal.es (J.G.-G.); fotod@usal.es (J.G.-L.)
2 Department of Construction and Agronomy, Architectural Area, Polytechnic School of Zamora,
University of Salamanca, Avda. Cardenal Cisneros, 34, Zamora 49022, Spain;
E-Mail: rodmen@usal.es

\* Author to whom correspondence should be addressed; E-Mail: daguilera@usal.es;
Tel.: +34-920-353-500; Fax: +34-920-353-501.

Received: 17 November 2013; in revised form: 14 January 2014 / Accepted: 14 January 2014 /
Published: 27 January 2014

Abstract: Historical perspective images have been proved to be very useful to properly
provide a dimensional analysis of buildings façades or even to generate a pseudo-3D
reconstruction based on rectified images of the whole structure. In this paper, the case of
Gobierna Tower (Zamora, Spain) is analyzed from a historical single image-based modeling
approach. In particular, a bottom-up approach, which takes advantage from the perspective
of the image, the existence of the three vanishing points and the usual geometric constraints
(i.e., planarity, orthogonality, and parallelism) is applied for the dimensional analysis of a
destroyed historical building. Results were compared with ground truth measurements
existing in a historical topographical surveying obtaining deviations of about 1%.

Keywords: historical photographs; single image; vanishing points; demolished
buildings; perspective

17

<!-- p. 32 -->

Remote Sens. 2014, 6 1086

\1. Introduction

Despite the high proliferation of three-dimensional scanning systems, which have revolutionized
the data acquisition fashion, photogrammetry, and computer vision techniques, have evolved to offer
powerful and friendly tools that can render virtual worlds that meet the most demanding expectations:
high geometric accuracy on the points, high radiometric quality on the surfaces of the object, and an
integrated environment where the user can interact and even play with the model or demand from its
data base sophisticated information. In addition, historical buildings modeling through laser scanner
become impossible when the structure does not exist or the whole building has been destroyed.
In these cases, the problem increases since the building cannot be reconstructed from two or more
images [1–3]. Trying to find a solution to these situations, several authors have proposed approaches
and methods based on the single view geometry [4–8]. However, only a few have been focused on the
case of demolished buildings modeling from historical photography [9–11]. This last aspect represents
a hard task as the type and geometry of the camera is completely unknown and the accuracy
assessment of the results is, sometimes, impossible due to the nonexistence of the building. In this
sense, some authors have developed approaches for obtaining internal camera parameters from a single
view [12,13] and to provide a quality control of the resulting model or dimensional analysis based on a
controlled virtual camera embedded into a CAD (Computer Aided Design) environment [14].
This contribution relies on software, sv3DVision, developed in 2005 [4,15] at the University of
Salamanca. The main aim that inspired the design of the program was to join the strength of the
simplicity involved in the geometry-that guarantees that the user can easily get involved in the task-and
the high performance expected on every highly automated approach. As a result, the hybrid method
enables to extract and exploit the image information that leads to the determination of the object
structure (through its vanishing points), besides the reliability provided by the application of robust
estimators, M-type and RANSAC (see infra). Last but not least, the program provides a twofold
aspiration: a technical one that should prove to be efficient on modeling different structures under a
diversity of circumstances; and a pedagogical one based on a simulation background that should
motivate students or researchers to keep going deeper on the topic.
Through the years, the software has been successfully tested on a variety of environments, such as
architecture, forensic sciences, traffic scenes and engineering; it has been awarded by the ISPRS
Organization and has been used in the teaching/learning of Cartographic Engineering. However, this is
not the main motivation that has decided us to present this contribution, but rather the importance of using
our work to preserve, enhance, and highlight the historical heritage of our community, Castilla-Leon.
This paper addresses the problem of single historical photography dimensional analysis and
pseudo-3D modeling (see infra for an explanation of this term) of demolished buildings, focusing the
case of study on the emblematic “Gobierna Tower” located in Zamora (Spain). The proposed method
is suitable for those regular structures, which contain several geometric constraints, such as planarity,
orthogonality, and parallelism, and hold the three orthogonal principal directions (i.e., three vanishing
points). In fact, the key to success relies on a robust approach for vanishing points computation, which
allows us to obtain more accurate results. To this end the paper has been organized as follows: after
this introduction, Section 2 remarks the historical background around the “Gobierna Tower” and its
importance for the city of Zamora; Section 3 depicts briefly some basic theory about projective

18

<!-- p. 33 -->

Remote Sens. 2014, 6 1087

geometry and vanishing points; Section 4 describes the method applied to the “Gobierna Tower”
putting special emphasis in the vanishing points computation method; a final section is devoted to put
across the concluding remarks.

\2. Historical Background

One of the most highlighted cases in lost buildings, that belonged to the architectural heritage of the
city of Zamora (Spain) [16], is the demolition of the towers that characterized the Stone Bridge on the
river Duero.
During its long-term presence, the Stone Bridge has undergone continuous transformations,
transformations that have been necessary to reduce the devastating effects of the endemic swellings
that knocked down the city slums.
At the end of the 19th century, its state was so worrisome that it was closed to the traffic and
replaced upstream by another viaduct. Once the local authorities dealt with the construction of a new
metallic bridge, also decided to recover the battered Stone Bridge. Between 1905 and 1908, Luis de
Justo, Civil Engineer, designed and executed eleven projects that modified radically the appearance of
the medieval bridge of Zamora, in addition to repairing it. Up to then, the Stone Bridge of Zamora
displayed a similar configuration to the original one. Several documents show this fact, such as the
View of Zamora by Anton van Wyngaerde (1570) (Figure 1), the plan by Blas de Vega (1820) [17],
the photography of J. Laurent (c. 1870) (Figure 2), and, finally, the 1905 previous state plans by Luis
de Justo. Sixteen pointed arches -one more than nowadays- laid out a 280-meter-long bridge, which
leaned in fifteen foundations, finished off by cutwaters and lightened by spillways. Two towers
controlled bridge crossing. The deck, straight guidelined and double downgrade ended, angled sharply
towards the east to make difficult enemy assault, once surpassed the exit tower. The deck was finished
off by 0.40 m wide parapets. At that moment, it was crowned by more than 300 battlements.
Over the cutwater of the previous tympanum to the angle, rose the tower of La Gobierna, popularly
known due the weather vane that topped it. Moreover, in Wyngaerde’s View or in Blas de Vega’s
elevation, an initial door prevented parking on the deck during the night. In the other extreme, over the
northern pier, an arc rose that opened the bridge by to the city.

Figure 1. Detail of the Stone Bridge of the Zamora city drawn by Antón van den
Wyngaerden, in 1570.

19

<!-- p. 34 -->

Remote Sens. 2014, 6 1088

Figure 2. Bridge over the Duero river in Zamora, photograph acquired by J. Laurent, in
\1870. Photograph of the southern half (arcs 7–3).

Nothing remains today. After Luis de Justo rehabilitation, the slopes were modified and the
spillways were extended, and even new ones were added. The works undertaken by the Department of
Public Work between 1905 and 1907 [18] consisted of the demolition of towers, parapets, and
tympanums to facilitate the later integral repair of the bridge. Thus, vaults were reviewed, tympanums
were reconstructed, and new asphalt paved the existing surface. In the northern part, the arc was
replaced with one roundabout, and, in the southern, in the angled stretch, the previous arc to the
“Gobierna Tower” was totally recovered. Fortunately, before disappearing, some of these architectures
were documented with building survey, while others did so with photography. This is the case of the
Stone Bridge that appears with its towers and doors, in several documents.

\3. Theoretical Basis: Single View Photogrammetry

The vanishing points, (VPx, VPy, VPz, see Figure 3) related to the perspective image of a box-like
shape (like a building) contain information, both of the camera and of the image pose. Thus, the
determination of these vanishing points can lead, firstly, to the determination of the interior and
exterior orientation of the image and secondly, to the computation of the metric properties of any
element pertaining to the faces of such a solid.
As can be seen from Figure 3, the intersections, from the point of view (S), of the three directions
(XYZ) of the box with the image plane give the three vanishing points: VPx, VPy, and VPz, conforming
a so-called perspective pyramid, The location of these points depends on: the focal length SP, with P,
the principal point (the intersection of the image axis with the image plane), the horizontal angle
QSVPx (horizontal angle of the camera axis with the main façade), and the vertical angle PSQ (angle
of the camera axis with the vertical direction). As will be seen later, the angle that renders the rotation
of the camera around its own axis (swing angle) can be derived from the angle of the horizon line with
the edge of the image.
It can be seen that the principal point, P, is the orthocenter of the triangle VPx, VPy, VPz, and that
the position of the point of view can be derived easily once the previous parameters have been
computed and a restriction from the object is provided (e.g., a known distance).

20

<!-- p. 35 -->

Remote Sens. 2014, 6 1089

Figure 3. Vanishing point geometry: S, point of view; P, principal point; (VPx, VPy, VPz),
vanishing points; VPx, VPy, horizon line; PVPz, maximum slope line; Q, intersection of the
maximum slope and horizon lines.

In any case, it can be seen that the first step is always to determine the position of the three
vanishing points related to a certain building and this relies heavily on both the robustness of the pose
configuration and on the ability of extracting straight lines from the image that intersect on each of the
vanishing points. The quality of the process, as will be discussed later, thus, depends on the definition
of the image lines and on the angle that each bundle of vanishing lines spans. From this, it can be seen
that when the perspective angles are poor, the vanishing point are far away from the center of the
image, decreasing, therefore, the reliability of the process.

\4. A Case Study: The Historical and Demolished “Gobierna Tower”

The “Gobierna Tower” together with its bridge was documented through several drawings,
historical photographs and even with a topographical surveying performed by the engineer Luis de Justo
in 1905. In particular, the most relevant documents correspond to Wygaerden [19] who performed some
perspective drawings of the bridge with its tower, or the historical photographs of Laurent
in 1870. In our case, different documents and perspective historical images have been analyzed in
order to test the historical single image-based modeling approach (Figure 4). In addition, the topographical
surveying, which contains a dimensional analysis of the tower has been considered as “ground truth”
to assess the accuracy of the process.
The following figure (Figure 4) outlines the workflow developed:

21

<!-- p. 36 -->

Remote Sens. 2014, 6 1090

Figure 4. Workflow developed for the historical single image-based modeling applied to
the case study of the “Gobierna Tower”.

4.1. Data Processing

There are two ways of retrieving the metric information of the object from a single image:
automatic and manual. The first one is always preferable when the image exhibits high quality
(high-resolution and definition of the vanishing lines), when the ratio between correct observations
(automatically extracted line segments) and mistaken observations (blunders derived from shadows,
scars on the image, reflections, etc.) is above 4 (environ) and when the perspective geometry is strong
enough. The second one is the alternative to weak cases in which these drawbacks are combined: low
number of vanishing lines, poor quality image, high number of blunders, and poor perspective geometry.
The automatic approach is structured in three steps:

(a) Extracting edge pixels by means of the Canny filter [20].
(b) Clustering pixels into raster segments according to neighboring criteria and with length
restrictions in a fashion very similar to the Burns Method [21].
(c) Determining vector lines (first and last points) from raster segments according to a plane
collinearity condition.

The output from these processes is the input in the following one: the determination of the
vanishing points. Several methods of approaching this have been implemented [15]: minimization of
the area of the triangle, modified Gaussian sphere, Tales theorem, modified Hough Transform, etc.
In all of them, a central role is played by the RANSAC (RANdom SAmple Consensus) robust
estimator [22] and its ability of determining and erasing blunders.

22

<!-- p. 37 -->

Remote Sens. 2014, 6 1091

A whole set of possibilities have been applied to automatically process the target image but none of
them has been successful due to the reasons outlined above. Thus, finally, the manual procedure was
applied and even though there is really a very small set of lines, an acceptable result has been reached
and this have been possible by the application of the modified Hough Transform Method, which is
briefly described in the following lines:

Figure 5. Interpretation of several cases of the Hough Transform applied to straight lines.
For each of the four cases, the Image Space is represented at the left and the Parameter
Space is represented at the right. In the Image space, there can be seen: (1) A straight line;
(2) A point; (3) A set of collinear points; (4) A vanishing point.

As is well known, the Hough Transform [23] deals with the relation between the space representation
of some geometric feature (points, straight lines, circles, etc.) and the representation of its geometric
parameters under the same Cartesian principles. For the following, we will focus on the problem we
are trying to overcome: determining lines from pixels extracted on the image and determining vanishing
points from these lines. The strength of the Hough Transform relies on the complete symmetry
between points and lines. According to the conventional expression of a 2D straight line y = ax + b,
the parameters to render a point (x,y) are exchangeable with the parameters to describe a line (a,b).
Thus a straight line in the image space is transformed to a point in the parameter space and vice versa,
a point in the image space is transformed to a straight line in the parameter space (Figure 5).
This leads (at least) to the following series of consequences (Table 1):

Table 1. Different cases between image and parameter spaces for the Hough transform.

Case Image Space Parameter Space
1 A straight line A point
A point (family of straight lines that
2 A straight line (family of points that belong to a line)
intersect on a point)
A set of collinear points
3 A set of lines that intersect on the same point
(that belong to the same line)
A vanishing point A set of collinear points (the straight line to which
4
(set of lines that intersect on a point) they belong represents the vanishing point)

23

<!-- p. 38 -->

Remote Sens. 2014, 6 1092

The Hough procedure works by quantizing the image space, then extracting all information for
every discrete cell, translating this information to the equivalent parameter space, and, finally, proceeding
to some voting scrutiny to find out the relevant feature that meets the target criteria (The drawback
related to the singularity of the parameter a when lines are close to verticality is overcome by tuning
from the Cartesian (a,b) representation of the line to its polar (r,α) expression).
To determine a vanishing point the procedure is as follows:

(a) For every start and end point of every line segment rendered by the automatic or manual
extraction, the correspondent line in the parameter space is computed and represented. Every
cell that lies on the line receives one vote.
(b) A voting procedure is undertaken so that the most visited cells give the lines that form
families of lines that pass through each of the vanishing points.
(c) For all these lines the correspondent parameters (a,b)i are computed.
(d) The best coordinates of each of the vanishing points are computed by applying a least
squares criteria to the equation: y0 = aix0 + bi in which (x0,y0) are the coordinates of a
vanishing point.
(e) In order to avoid residual outliers, a weighting procedure is applied to the above task, so that
a robust M-estimator, modified Danish estimator [24] can be implemented and, thus, the
blunders may be expelled from the computation and the reliability can be improved.

Once the coordinates of the three vanishing points are computed the interior and exterior orientation
parameters are addressed from the perspective pyramid, built from these points plus the point of view
(Figure 6c):

(a) The orthocenter of the triangle formed by the three vanishing points (VPx, VPy, VPz) yields the
principal point (P) (Figure 6c).
(b) The rotation angles (θ,ν) and the focal length (f) can be derived from the following relations
(Figure 6).

On the horizontal triangle (Figure 6a) formed by the point of view, S, and the horizontal vanishing
points, VPx and VPy, the following relations hold Equation (1):

QVPx SQ tan  
SQ QVPy
(1)
QVPx tan 
QVPy

with SQ 2  QVPx  QVPy (in the horizontal triangle).
On the vertical triangle (Figure 6b) formed by the point of view, S, the vertical vanishing point VPz
and the intersection of the horizon and maximum slope lines, Q, the following relations hold Equation (2):

PQ tan (2) PVPz

with f 2  PQ  PVPz (in the vertical triangle).

24

<!-- p. 39 -->

Remote Sens. 2014, 6 1093

Figure 6. (a) Horizontal triangle formed by the point of view, S, and the horizontal
vanishing points VPx and VPy ,with the azimuth angle (θ); (b) Vertical triangle formed by
the point of view, S, the vertical vanishing point, VPz, and the intersection of the horizon
and maximum slope lines, Q, with the tilt angle (ν); (c) Perspective triangle formed by the
three vanishing points (VPx, VPy, VPz) that contains the principal point (P) as the
intersection of the heights of the triangle and image showing the swing angle (χ) around the
camera axis: the horizon line and the width image edges are not parallel (in addition,
the maximum slope line and the height image edges are not parallel).

(a) (b) (c)

Finally, the swing angle (Figure 6c) can be computed from Equation (3):

(YVPx  YVPy ) tan  (3) ( X VPx  X VPy )

(c) Once these parameters are known, the coordinates of the point of view, S, can be easily derived
by applying a certain restriction to the object (in addition to the point of view itself) and then
solving from the collinearity equations (Figure 7). An example case is measuring a horizontal
distance in the object and setting the origin of the Datum at one of these points. We can, thus,
write six equations for five unknowns: (XYZ)S and the two scale factors for each collinearity
condition [25] Equation (4).

 xa  x p   X A  X S   X S 
      y a  y p  aA  R  YA  YS aA  R  YS      
  f   Z A  Z S   Z S 
(4)  xb  x p   X B  X S   X S  D AB 
      yb  y p  bB  R  YB  YS bB  R  YS      
  f   Z B  Z S   Z S 

where xa, ya, xb, yb are the image coordinates of the ground points A and B, respectively, which
define the Datum and the known horizontal distance DAB; xp, yp are the principal point, P,
coordinates; R is the rotation matrix and Xs, Ys, Zs and λaA, λbB are the unknowns corresponding
to the point of view, S, and the two scale factors, respectively.

25

<!-- p. 40 -->

Remote Sens. 2014, 6 1094

Figure 7. The coordinates of the point of view, S, can be computed once the principal point
(P), focal length (f), and rotation angles (θ,ν,χ) are known by proceeding to a Datum
definition by which two imaged points (a and b) receive two object coordinates: A(0,0,0)
and B(DAB,0,0) and by means of the collinearity equations. In this case, the X coordinate of
point B, that lies on X axis, is the measured distance between A and B.

Figure 8. Dimensional analysis on a plane (in this case Y = 0) of the object and
pseudo-3D modeling based on the rectification of the whole plane. The coordinates of any
object point T can be computed from its image t, and the constraint YT = 0, by means of the
collinearity equations.

Finally, once the interior and the exterior orientations are solved, the dimensional analysis process
and the pseudo-3D modeling process are available (Figure 8). By pseudo-3D modeling we mean that
the object facades can be rectified, that is, digitally transformed to eliminate any perspective effect
and, furthermore, if two facades are related by a orthogonality condition, as is usually the case,
a double rectification step can be applied, that is, from the two 2D documents linked to each other a 3D

26

<!-- p. 41 -->

Remote Sens. 2014, 6 1095

document can be obtained by an orthogonality relation. If more photographs, containing other pair of
(orthogonal) facades are available, this process could be extended to complete the four (orthogonal and
parallel) faces of the object. Both the dimensional analysis and the pseudo-3D modeling procedures are
based on the collinearity equations and both require the definition of a geometric constraint
(i.e., working plane) on the object. For example, we can work with the XZ plane for which
the-planarity, verticality, and parallelism with XZ plane-constraint Y = 0 is applied. Furthermore,
we can also work with YZ plane for which the-planarity, verticality, and parallelism with YZ
plane-constraint X = 0 is applied. Obviously, both constraints imply an orthogonality relation between
them. If more photographs, depicting other facades, were available, similar constraints could be applied
to complete the whole building. Note that the scale factor could be propagated from the first image to
the others although it would be highly convenient to measure more distances on the facades.
For any object point T (with YT = 0), which is imaged on the photograph as t, we have Equation (5):

 xt  x p   X T  X S   xt  x p   X T  X S 
    1 T     yt  y p   R  YT  YS ;   R  yt  y p  YS (5)        
  f   Z T  Z S    f   Z T  Z S 

In addition, dividing the first and third equations by the second one and rearranging we get
Equation (6):
r11 ( x  x p )  r21 ( yt  y p )  r31 f
X T  X S  YS
r12 ( x  x p )  r22 ( yt  y p )  r13 f
(6)
r13 ( x  x p )  r23 ( y t  y p )  r33 f
Z T  Z S  YS
r12 ( x  x p )  r22 ( y t  y p )  r13 f

where all the terms at the right side of the equation are known. This can be applied to discrete points or
in a scanning fashion to all the pixels that lie in the face related to the XZ plane and therefore, obtain
the pseudo-3D model of the façade.

4.2. Results

After analyzing more than ten images, the only historical photograph that properly worked presents
a size of 7.7 × 12.18 cm and is scanned with a pixel resolution of 150 dpi providing an image
of 455 × 719 pixels (Figure 9). The secret to success remains in the distance to the object (very close,
around 70 m), as well as the well-defined perspective of the photograph towards the main three
orthogonal directions. Furthermore, the selected photograph is based on the following hypotheses, as
far as the building’s geometry is concerned: (i) façades are planar geometric structures; (ii) lens
distortion is not considered; (iii) façade edges are straight and constitute the input data of the described
method; and (iv) the existence of constraints (parallelism, perpendicularity, and coplanarity) of
building’s edges and facades.

27

<!-- p. 42 -->

Remote Sens. 2014, 6 1096

Figure 9. Historical photograph (1900) used for the single image-based modeling approach.

According to the proposed approach, the photograph is manually vectorized with lines clustered along
the three main object directions (X,Y,Z). As a result, the three main vanishing points (VPx, VPy, VPz) are
computed, based on the robust Hough approach described above. The coordinates of these relevant
points together with its RMSE (Root Mean Square Error), in pixel units, are outlined in Table 2.
It should be noted the subpixel precision obtained.

Table 2. Vanishing points coordinates and its errors.

Hough Transform + Danish Estimator: (units: pixels) VPx VPy VPz
x 2,253.8 −587.42 283.55
y 504.79 582.40 −7,425.58
RMSE 0.057 0.046 0.318

Computed the main structural components of the process, the geometric internal camera parameters,
i.e., focal length and principal point, are estimated based on the perspective pyramid construction
(Figure 10) taking the three vanishing points as vertices. The principal point of the image (P) is the
orthocenter of this triangle, whereas the height of the pyramid corresponds to the focal length (f). The
solved internal geometry of the camera, the camera pose (i.e. orientation and position) is computed.
The orientation of the camera (θ,ν,χ) is computed, based on the geometric relations developed in
Equations (1–3), which establish a relationship between the orthogonal directions (X,Y,Z) and the
corresponding vanishing points (VPx,VPy,VPz), assuming the intrinsic geometric parameters of the
camera known. For the spatial position (X,Y,Z)S, the user must introduce some known measurement of
the building together with some geometric constraint in order to overcome the indetermination problem
i.e., it is not possible to compute indirectly the camera position only with one image. In our case, a known

28

<!-- p. 43 -->

Remote Sens. 2014, 6 1097

horizontal distance (8.70 m) together with a coplanarity constraint (Y = 0) was defined. This measure
was extracted from the topographical surveying performed by the engineer Luis de Justo in 1905.

Figure 10. Perspective pyramid computed for the single image-based modeling approach.
The vanishing points (VPx, VPy, VPz) constitute the base of the pyramid, whereas the point
of view, S, and the focal length, f, are the vertex of the pyramid and its height, respectively.

The following table (Table 3) outlines the intrinsic and extrinsic parameters estimated for the
unknown camera.

Table 3. Internal and external parameters of the unknown camera.

Internal Parameters (units: millimetres) External Parameters (units: degrees, meters)
P [x] (mm) 25.29 θ: 38.114° XS: −29.71
P [y] (mm) 65.40 ν: 105.5167° YS: −60.18
f (mm) 44.86 χ: 177.5282° ZS: −13.66

It should be noted, the more weakness along the Z axis in the vanishing points computations as the
parallelism of the lines renders an intersection that is close to the infinite (Figure 10). This situation
provides a weakness in this direction as the vanishing lines intersection contains more uncertainty
along this vertical direction. This is confirmed in Table 2 with the worst RMSE obtained for the VPz.
Again, from Table 3, it could be analyzed the weakness along Z direction since the vertical angle, v,
does not provide enough perspective, only 5°above the horizontal. The swing angle reflects that the
image has been taken in vertical position since the horizontal one is 90°. However, this angle does not
provide perspective and, thus, is not relevant for the vanishing points computation. The spatial camera
position is relative with relation to the known horizontal distance defined by the user.
Fixed the camera pose, a dimensional analysis was performed based on distances. This process was
performed using the collinearity condition constrained with some geometric clues, such as coplanarity,
parallelism, or perpendicularity Equations (5) and (6). This dimensional analysis is outlined in
Figure 11a and Table 4 together with its accuracy assessment. This quality control was
performed based on the measurements existing on the topographical surveying executed by the
engineer Luis de Justo in 1905. The discrepancies show an average relative error around 1%, included
metric data inaccuracy.

29

<!-- p. 44 -->

Remote Sens. 2014, 6 1098

Figure 11. (a) Dimensional analysis based on distances for the accuracy assessment;
(b) Pseudo-3D model of the “Gobierna Tower” obtained through the single image-based
modeling approach; (c) Virtual 3D reconstruction that integrates the “Gobierna Tower” in
the Zamora Stone Bridge.

Table 4. Accuracy assessment: dimensional analysis of distances.

Code Distances (m) Discrepancies (m) Code Distances (m) Discrepancies (m)
L1 1.84 δL1 = 0.01 L6 4.66 δL6 = 0.04
L2 4.08 δL2 = 0.02 L7 10.05 δL7 = 0.04
L3 4.40 δL3 = 0.05 L8 5.18 δL8 = 0.02
L4 4.45 δL4 = 0.05 L9 0.87 δL9 = 0.03
L5 14.38 δL5 = 0.07 Known Distance 8.70 δKD = 0.00

Finally, a pseudo-3D model was generated based on the rectified facades computed geometrically
from vanishing points, that is, using the collinearity equations supported by a geometric constraint
(i.e., working plane) on the object Equations (5) and (6). The result is showed in Figure 11b.
Furthermore, in order to visualize this result integrated with its current state, a virtual recreation of the
Stone Bridge with the “Gobierna Tower” has been generated (Figure 11c).

\5. Conclusions

When the lack of information is clearly due to the non-existence of the object of interest, such as
historical demolished buildings, classical but solid perspective geometry statements can be of great
utility, instead of advanced image processing techniques, especially in those cases in which only
individual or single images exist. The main goal of this study was to provide a dimensional analysis

30

<!-- p. 45 -->

Remote Sens. 2014, 6 1099

and even a pseudo-3D reconstruction of the demolished historical building “Gobierna Tower” using
single historical photographs. To this end, a single image-based modeling method has been developed
and adapted to this specific case. The accuracy assessment results come to confirm that from a single
view we can measure distances and areas and even to provide a simple 3D model with enough quality.
The results obtained could be useful for the authorities of Zamora’s Council as they have been
considering reconstructing the “Gobierna Tower”. The monument would play an important touristic
role but specially would meet a popular demand supported by social and cultural reasons which would
be directly connected with the identity of Zamora’s society.
With relation to the workflow developed and the results obtained the main conclusions are
the following:

(a) Manual processing permits achieve better results than automatic processing. This is due to the
weakness related to low number of vanishing lines, poor quality image, high number of
blunders and poor perspective geometry.
(b) Although robust estimators (especially RANSAC) have proven largely its efficiency in filtering
gross errors, this is not the case. As just stated, when the image is poor both in geometry and
radiometry, the automatic approach leads to an excessive number of blunders and so,
the manual identification of vanishing lines is better.
(c) An original vanishing point method based on the Hough Transform, which guarantees
efficiency and quality in the results, even with unfavorable cases (a three-point perspective
getting close to two-point perspective), has been successfully applied. Other methods to
compute the vanishing points, such as the triangle area minimization or the Gaussian sphere,
have not provided good results.
(d) A relative error of 1% has been obtained for the accuracy assessment of the results. This value
can be considered very good since the single image-based modeling approach developed
involves many steps and thus the corresponding error propagation.
(e) Finally, it should be remarked that the method is only applicable in scenes with strong
geometric contents (i.e., presence of structural planes and lines). In addition, the image must
have perspective along the three main directions (X,Y,Z) in order to compute the corresponding
three vanishing points (VPx,VPy,VPz). Obviously, if these vanishing points are well defined
more precision and reliability can be reached for the single image-based modeling approach.

Author Contributions

All authors contributed extensively to the work presented in this paper.

Conflicts of Interest

The authors declare no conflict of interest.

References

\1. Hartley, R.; Zisserman, A. Multiple View Geometry in Computer Vision; Cambridge University
Press: Cambridge, UK, 2000; Volume 2.

31

<!-- p. 46 -->

Remote Sens. 2014, 6 1100

\2. Faugeras, O. Three Dimensional Computer Vision: A Geometric Viewpoint; The MIT Press:
Cambridge, UK, 1993.
\3. Zucchelli, M.; Santos-Victor, J.; Christensen, H.I. Pattern Recognition. In Proceedings of the IEEE
16th International Conference on Constrained Structure and Motion Estimation from Optical
Flow, Québec City, QC, Canada, 11–15 August 2002; pp. 339–342.
\4. Gonzalez-Aguilera, D.; Gomez-Lahoz, J. From 2D to 3D through modelling based on a single
image. Photogram. Record 2008, 23, 208–227.
\5. Debevec, P.E.; Taylor, C.J.; Malik, J. In Modeling and Rendering Architecture from Photographs:
A Hybrid Geometry- and Image-Based Approach. In Proceedings of the SIGGRAPH,
New Orleans, LA, USA, 4–9 August 1996; ACM: New Orleans, LA, USA; pp. 11–20.
\6. Van den Heuvel, F.A. Automation in Architectural Photogrammetry: Line-Photogrammetry for
the Reconstruction from Single and Multiple Images. Ph.D. Thesis, Delft University of
Technology, Delft, The Netherlands, 2003.
\7. Grammatikopoulos, L.; Karras, G.; Petsa, E. Camera Calibration Approaches Using Single
Images of Man-Made Objects. In Proceedings of the XIX CIPA International Symposium,
Antalya, Turkey, 30 September–4 October 2003; pp. 328–332.
\8. Wilczkowiak, M.; Boyer, E.; Sturm, P. 3D Modeling Using Geometric Constraints:
A Parallelepiped Based Approach. In Proceedings of the European Conference on Computer
Vision, Copenhagen, Denmark, 28–31 May 2002; Volume IV, pp. 221–236.
\9. Kalisperakis, I.; Rova, M.; Petsa, E.; Karras, G. On Multi-Image Reconstruction from Historic
Photographs. In Proceedings of the XIX CIPA International Symposium, Antalya, Turkey,
30 September–4 October 2003; pp. 216–219.
\10. Styliadis, A.D.; Sechidis, L.A. Photography-based façade recovery & 3-D modeling: A cad
application in cultural heritage. J. Cult. Herit. 2011, 12, 243–252.
\11. Georgoula, O.; Stamnas, A.; Patias, P.; Georgiadis, C.; Fragkoulidou, V. Historical coastal urban
landscapes digital documentation and temporal study with 2d/3d modeling functionality: The case
of Thessaloniki, Greece. J. Cult. Herit. 2012, 14, 396–402.
\12. Gonzalez-Aguilera, D.; Gomez-Lahoz, J.; Rodriguez-Gonzalvez, P. An automatic approach for
radial lens distortion correction from a single image. IEEE Sens. J. 2011, 11, 956–965.
\13. Caprile, B.; Torre, V. Using vanishing points for camera calibration. Int. J. Comput. Vis. 1990, 4,
127–139.
\14. Styliadis, A.D. Historical photography-based computer-aided architectural design: Demolished
buildings information modeling with reverse engineering functionality. Autom. Constr. 2008, 18,
51–69.
\15. Gonzalez-Aguilera, D. Reconstrucción 3D a Partir de una Sola Vista. Ph.D. Theses, University of
Salamanca, Salamanca, Spain, 2005.
\16. i uela Ximenez, A. , su Provincia y Obispado;
Diputación de Zamora, Instituto de Estudios Zamoranos “Flori n de campo”: Zamora, España,
\1987.
\17. Chías Navarro, P.; Abad Balboa, T. Los Caminos y la Construcción del Territorio en Zamora:
Catálogo de Puentes; Ministerio de Fomento, Diputación de Zamora, Instituto de Estudios
Zamoranos “Flori n de campo”: Zamora, España, 2004.

32

<!-- p. 47 -->

Remote Sens. 2014, 6 1101

\18. Rodríguez Méndez, F.J.; Andrés Rodrigo, H.; Rubio Cavero, M.P.; García Gago, J.M. El Puente
Medieval de Zamora a Comienzos del Siglo XX. Un Estudio del Alcance de la Intervención del
Ingeniero Luis de Justo. Anuario 2009 Instituto de Estudios Zamoranos Florián de Ocampo, Zamora,
España. 2012; Vol. 26, pp. 227–268. Available online: http://www.iezfloriandeocampo.com/
?id=17&idn=54&titulo=Colecci%F3n%20Anuarios (accessed on 21 January 2014) (In Spanish).
\19. Kagan, R.L. Ciudades del Siglo de oro: Las Vistas Españolas de Anton. van den Wyngaerde;
Ediciones El Viso: Madrid, España, 1986.
\20. Canny, J. A computational approach to edge detection. IEEE Trans. Pattern Anal. Mach. Intell.
1986, 8, 679–698.
\21. Burns, J.B.; Hanson, A.R.; Riseman, E.M. Extracting straight lines. IEEE Trans. Pattern Anal.
Mach. Intell. 1986, 8, 425–455.
\22. Fischler, M.A.; Bolles, R.C. Random sample consensus: A paradigm for model fitting with
applications to image analysis and automated cartography. Commun. ACM 1981, 24, 381–395.
\23. Hough, P.V.C. Method and Means for Recognizing Complex Patterns. US Patent No. 3,069,654.
18 December 1962.
\24. Domingo-Preciado, A. Investigación Sobre los Métodos de Estimación Robusta Aplicados a la
Resolución de los Problemas Fundamentales de la Fotogrametría. Ph.D. Theses, University of
Cantabria, Santander, Spain, 2000.
\25. Kraus, K. Photogrammetry (Volume 1); Dümmler Verlag: Bonn, Germany, 1993.

© 2014 by the authors; licensee MDPI, Basel, Switzerland. This article is an open access article
distributed under the terms and conditions of the Creative Commons Attribution license
(http://creativecommons.org/licenses/by/3.0/).

33

<!-- p. 48 -->



<!-- p. 49 -->

Documentación y análisis geométrico del patrimonio arquitectónico a partir de métodos
fotogramétricos con una y múltiples imágenes

4.2 A PHOTOGRAMMETRIC AND COMPUTER VISION-BASED APPROACH FOR
AUTOMATED 3D ARCHITECTURAL MODELING AND ITS TYPOLOGICAL
ANALYSIS

Resumen: Actualmente, en la digitalización del patrimonio arquitectónico, a la
dificultad en el proceso de toma de datos hay que sumar un mayor grado de
especialización en el manejo de software tanto láser como fotogramétrico. Gracias a
los avances en la integración de la fotogrametría y la visión computacional así como
en parte de los métodos y algoritmos numéricos de cálculo, es posible poder aspirar
al paso del 2d (imágenes) al 3d (nubes de puntos) de forma automática, flexible y con
calidad. Este artículo presenta un método novedoso concretado en el desarrollo de
una herramienta, PW-Photogrammetry Workbench y su utilidad para el modelado
arquitectónico. Esta herramienta permite, a partir de imágenes, generar modelos
tridimensionales a escala en forma de nubes de puntos que superan incluso la
resolución de los sistemas láser y que además pueden ir acompañadas de las
correspondientes ortofotos con textura fotográfica de alta resolución. El método
permite abordar estudios sobre la tipología de la arquitectura y ha sido testeado de
forma exitosa sobre un muestreo de diez edificios religiosos representativos de cada
una de las tipologías detectadas en los municipios fronterizos de la comarca de Aliste,
Zamora (España).
Palabras clave: modelado basado en imágenes; fotogrametría; visión
computacional; correspondencia; patrimonio cultural; arquitectura; desarrollo de
software; análisis tipológico

35

<!-- p. 50 -->



<!-- p. 51 -->

Remote Sens. 2014, 6, 5671-5691; doi:10.3390/rs6065671
OPEN ACCESS
remote sensing
ISSN 2072-4292
www.mdpi.com/journal/remotesensing
Article

A Photogrammetric and Computer Vision-Based
Approach for Automated 3D Architectural Modeling and
Its Typological Analysis

Jesús García-Gago 1, Diego González-Aguilera 1,*, Javier Gómez-Lahoz 1
and Jesús Ignacio San José-Alonso 2

1 Department of Cartographic and Terrain Engineering, Polytechnic School of Avila, University of
Salamanca, Hornos Caleros 50, 05003 Avila, Spain;
E-Mails: jesusmgg@usal.es (J.G.-G.); fotod@usal.es (J.G.-L.)
2 Lab of Architectural Photogrammetry, High Technical School of Architecture ,University of
Valladolid, Av. Salamanca 32, 47014 Valladolid, Spain; E-Mail: jesussanjose@telefonica.net

\* Author to whom correspondence should be addressed; E-Mail: daguilera@usal.es;
Tel.: +34-920-353-500; Fax: +34-920-353-501.

Received: 13 March 2014; in revised form: 12 June 2014 / Accepted: 12 June 2014 /
Published: 17 June 2014

Abstract: Thanks to the advances in integrating photogrammetry and computer vision, as
well as in some numeric algorithms and methods, it is possible to aspire to turn 2D
(images) into 3D (point clouds) in an automatic, flexible and good-quality way. This article
presents a new method through the development of PW (Photogrammetry Workbench)
(and how this could be useful for architectural modeling). This tool enables the user to turn
images into scale 3D point cloud models, which have a better quality than those of laser
systems. Moreover, the point clouds may include the respective orthophotos with
photographic texture. The method allows the study of the typology of architecture and has
been successfully tested on a sample of ten religious buildings located in the region of
Aliste, Zamora (Spain).

Keywords: image-based modeling; photogrammetry; computer vision; matching; cultural
heritage; architecture; software development; typological analysis

37

<!-- p. 52 -->

Remote Sens. 2014, 6 5672

\1. Introduction

There is no doubt that photogrammetry is gaining an audience. Furthermore, it stands as a serious
competitor against the popular laser scanner systems, both terrestrial (TLS (Terrestrial Laser Scanner))
and aerial (ALS (Airborne Laser Scanner)) and both static and dynamic systems (MLMS (Mobile
LiDAR Mapping System)) [1]. The success of photogrammetry lies in two aspects: the reliability of
the system and the fact that it uses the image as the most valuable source of information, as well as the
beneficial “marriage” with computer vision [2]. This hybridization has made it possible to overcome
two important obstacles. First, the automation in the orientation process and the reconstruction process
itself, which results in dense 3D models that, in some cases, have a higher resolution than those
obtained from laser scanners. Second, the flexibility of the image capturing process, as, due to the
substantial technological development of photogrammetric software in recent years, it is possible to
use any type of image. It even allows any type of camera, calibrated or uncalibrated [3], smartphone or
tablet [4]. Photogrammetry has even a third advantage: its commitment to the accuracy and reliability
of the results [5]. This means that, for many uses, photogrammetry stands out as a serious competitor
against the low-cost laser systems.
Terrestrial photogrammetry makes it possible to obtain precise 3D models of highly irregular
elements, in a non-contact way, that minimizes the measurement time and enables the evaluation of the
structural safety of any construction [6]. It can also be combined with other techniques, such as
ground-penetrating radar (GPR) for archaeological purposes, with great success [7]. In addition, the
radiometric content of the data allows the introduction of analytical constraints derived from the
regular shape of architectural surfaces to obtain accurate 3D CAD models [8].
There are also many tools that, for different purposes and at a low cost, or even free and open
source, allow us to turn 2D images into 3D point clouds. Such a challenge requires solving two
preliminary important geometric issues. First, knowing the internal parameters of the camera (focal
length, principal point coordinates and lens distortion parameters) and, second, knowing the external
parameters (spatial and angular position) [9]. For years, photogrammetry has succeeded in solving
those issues by applying rigorous laboratory and/or field calibration processes and also thanks to a
well-planned network of pass and control points. However, the integration of algorithms and
techniques from computer vision has enabled such obstacles and dependence to be overcome and
automatically solved during the 3D model calculation process (structure from motion (SfM)) [10,11].
More specifically, the main advances concern multiple image matching strategies based on FBM
(feature-based matching) and ABM (area-based matching), which allow one to obtain, by means of
collinearity equations [5], the spatial and angular position of the image, as well as a preliminary
dispersed geometry of the scene in an arbitrary and local system of coordinates [12]. Once the image
resections are solved, the direct process may begin multiple direct intersections; this process also
sustained on the concept of collinearity, which leads to the reconstruction of the 3D model or a
dimensional-metric analysis of the object or scene. In this process, major advances have once again
taken place thanks to matching techniques. The process starts from the powerful, although constrained
to the favorable geometry of the so-called normal case, semi-global matching (SGM) [13]. This
technique allows the creation of dense 3D point clouds models from multiple images with the same
resolution as the GSD (ground sample distance) of the image; that is, each pixel of the image renders a

38

<!-- p. 53 -->

Remote Sens. 2014, 6 5673

specific point of the model. Apero-Micmac [14] is a good example of open source software, as well as
other commercial photogrammetric tools (eATE, NGATE, Dense Matcher, ISAE, Match-T, Xpro,
Tridicon, PhotoScan, etc.). Nevertheless, the use of patch-based methods based on surfels has also
helped develop the creation of dense models from multiple images with oblique and converging
geometry [15,16]. In this regard, Patch-based Multi-View Stereo (PMVS) [17] (Furukawa and Ponce,
\2009) takes a hybrid approach based on providing a dense set of small oriented rectangular patches on
the pixel level. Moreover, it includes a visibility filter, which allows deleting false matched points.
However, the greatest disadvantage of these commercial and web-based tools (Bundler, Photosynth,
Photofly Insight 3D, 123Catch) is that they are based on computer vision algorithms, which calculate
the image orientation by using independent models. The main drawbacks of this approach are that the
internal parameters of the camera are not treated in a thorough and global way and that the exterior
parameters must be transmitted from one model to another, thus being subject to an exponential
propagation error. Therefore, the outcome is far from the rigorous orientation of photogrammetric
bundle adjustment, which is based on a global minimization error approach and, in addition, on the
explicit inclusion of internal parameters, either as unknowns (self-calibration) or as previously
calculated. As a result, the quality is not as good as expected. Another great disadvantage of
commercial and web-based tools is the computational cost due to both the number and the size of the
images, especially if we are working with large format images. Therefore, it can be concluded that
there is still a lot to do and that we need to aspire to parallel and GPU programming, which may not
allow us to work in real time, but will help us get acceptable processing times and image volumes.
In this regard, the article presents the tool, Photogrammetry Workbench, as an attempt to bring
photogrammetry and computer vision even closer with the aim of avoiding the aforementioned
disadvantages, applied to architectural modeling. The starting point is to rigorously tackle the image
orientation process by carrying out a preliminary approximation based on computer vision and a
precise and reliable refinement resulting from photogrammetric bundle adjustment. Then, the tool
enables the user to choose the generation method that creates the dense 3D model according to the
geometry of the image acquisition network, which has been previously calculated. That is to generate a
dense model from vertical and horizontal images with the SGM (semi-global matching) strategy, or to
create the dense model from oblique multiple images by encircling the object with a “ring” and using
the patch-based method. In this way, quality 3D model generation can be achieved thanks to the
rigorous orientation procedures of photogrammetry. As a result of the automatic 3D modeling, graphic
information is obtained—orthophotos—which enable the analysis of architectural cultural heritage.
The article is structured as follows; after the Introduction, Section 2 details the method for turning
2D images into 3D point clouds placing strong emphasis on the processing steps (image matching and
object reconstruction). Section 3 covers the typological analysis of ten churches in the border towns of
the region of Aliste (Zamora, Spain), using PW (Photogrammetry Workbench) for the architectural
modeling. Section 4 summarizes and condenses the main article contributions together with the
possible future action lines.

39

<!-- p. 54 -->

Remote Sens. 2014, 6 5674

\2. Methodology

From the capture of multiple images and after following a simple protocol, it is possible to obtain a
non-manipulated 3D model, which allows the extraction of the relevant metric information of the
building. However, one of the most critical steps in the process is the extraction and matching of the
structural elements, lines and points, with high accuracy and reliability. These elements are the main
support of the whole process, as they provide the necessary data to indirectly solve the spatial and
angular position of the images (orientation), the camera self-calibration and the 3D reconstruction of
the building. The following graphic (Figure 1) illustrates the steps taken in the 3D modeling
from images.

Figure 1. Workflow for automatic reconstruction from images. ASIFT, affine scale-invariant
transform; SGM, semi-global matching; PMVS, Patch-based Multi-View Stereo.

2.1. Data Collection Protocol

The data collection in the form of images is the key to success, as it presents the input data of the
process. The CIPA (Comite International de Photogrammetrie Architecturale) 3 × 3 Rules developed
by [18] were designed to cope with image acquisition for the simple photogrammetric documentation
of architecture. However, nowadays, the proliferation of digital cameras and the improvement of
automatic algorithms have proven that these rules must be reformulated in terms of a higher number of
images required. To this end, a specific image acquisition protocol has been designed for architectural
modeling, which guarantees an easy and efficient data acquisition and ensures a dense surface

40

<!-- p. 55 -->

Remote Sens. 2014, 6 5675

reconstruction. Three different acquisition protocols are proposed in order to cope with as best as
possible the size, morphology and external elements (i.e., occlusions, obstacles, etc.) of the buildings.

 Circular or “ring” network: used to obtain a 3D model of the whole building, which will then
allow establishing the sections necessary to sketch the ground plan. The images axis must
converge at the center of the object, and the minimum overlap between adjacent images must
be about 80%. Moreover, the number of images in the corners should be higher, so that the user
can “tie” the different façades of the object. The network of the shooting process should
maintain an appropriate proportion between the base (distance between shots) and the distance
to the object. As a general rule, in order to ensure image correspondence in the orientation
process, the distance between two adjacent camera stations must be so that the camera axis
forms an angle of intersection of approximately 15° with the object. The number of images
necessary to obtain all of the measurements depends on the size, shape, morphology and
location of the object (in relation to adjacent buildings) and the focal length (Figure 2, left).
 Planar or mosaic network: particularly recommended to document the façade of a building. It
requires taking some frontal images of the façade, with an overlap higher than 80% between
adjacent shots (Figure 2, center).
 Independent basic network: When documenting a small and accessible façade or any isolated
architectonic element, the shooting network may consist of five images forming a cross with an
overlap between adjacent shots higher than 90%. The main shot is a frontal image of the
façade, which is then combined with four more images of the left, right, upper and lower part
of the main shot, to conform a global, slight converging perspective (Figure 2, right).

Figure 2. Different acquisition protocols for architectural modeling: circular or ring
network (left), planar or mosaic network (center) and independent basic network (right).

Finally, in order to endow the object with metric properties, it is necessary to know the exact
distance between two well-defined points in the image by measuring it with a tape measure or by
incorporating some kind of surveying rod into the scene. That extra element must then appear in at
least three images, so as to establish the scale of the model. Likewise, it should be highlighted the
importance of choosing the output scale of the product, which will depend on the purpose and means
of representation, as these determine the data capture [19]. Every scale entails a maximum accuracy,
connected with the standard human eye acuity (0.2 mm).
Such accuracy matches the object pixel size or ground sample distance (GSD) through the
following expression:

41

<!-- p. 56 -->

Remote Sens. 2014, 6 5676

p  D
GSD 
f (1)

where D is the distance to the object, ƒ the focal length and p the pixel size.
When using the digital camera, we only need to multiply the number of pixels along the height and
width of the image by the GSD to get the object size covered by every frame. Besides, it is clear that
the GSD, the pixel size and the focal length will determine the shooting distance to the object and the
scale of the image.
In that way, depending on the maximum shooting distance, the size of the building and the
minimum overlap between images, it will be possible to determine the number of images needed to
fully document each face. However, in most cases, the maximum shooting distance is determined by
the characteristics of the building location. Narrow streets, buildings, vehicles and vegetation near the
object may block the way to getting the necessary distance to fit the whole building into the image.
This means an increase in the number of images and sometimes in the maximum accuracy and,
therefore, a larger scale in the final product, but it also means higher processing times and a higher
probability of error.

2.2. Extraction and Matching of Features

The field of architectural documentation requires robust analysis for the extraction and
correspondence of points of interest in the image, as the scale, perspective and lightning are variable.
In the field of photogrammetry, the classic methods on correspondence between grey levels are ABM
(area-based matching) [20] and LSM (least squares matching) [21]. However, for complex scenes, a
more sophisticated and stable study is needed, which provides favorable and solid solutions to the
geometric and radiometric variations. Such studies might be developed by applying algorithms, like
SUSAN (smallest univalue segment assimilating nucleus) [22], SIFT (scale-invariant feature
transform) [23], MSER (efficient maximally stable extremal region) [24] or SURF (Speeded Up
Robust Features) [25]. Nevertheless, all of these new algorithms are not robust to the perspective
variations of different images.
In this respect, a variation of the SIFT algorithm called ASIFT (affine scale-invariant
transform) [26] has been added to the PW tool. The most remarkable improvement is the possibility of
including two additional affinity parameters to control the perspective of the images, which correspond
to the two perspective angles of the optical axis of the camera, ϖ (tilt) angle and φ (axis) angle
(Equation (2)). The ASIFT algorithm will therefore allow working with images in perspective, which
are frequent in these cases. The result is a descriptor, which stays the same regardless of the scale,
rotation, movement and important deformations caused by the different perspectives of the images.
The following expression accounts for the resulting descriptor:
 a b  cos   sin  t 0  cos  sin
A   H R1 ()T1 R2 ()   (2)  c d   sin  cos  0 1   sin cos 

where A is the affine transformation with the scale λ, κ the rotation around the optical axis (swing) and
the perspective parameters for the inclination of the optical axis of the camera: φ (tilt) = arccos (1/t),

42

<!-- p. 57 -->

Remote Sens. 2014, 6 5677

the angle between the optical axis and the normal to the image plane, and ϖ (axis), the azimuth angle
between the optical axis and a fixed vertical plane.
The extraction of features is performed following the same SIFT workflow [27], but adding the two
remarked perspective parameters (ϖ, φ), that is, the ASIFT descriptor incorporates a simulation of
perspective caused by a variation of the camera optical axis direction. In particular, ASIFT proceeds by
the following steps: (i) each image is converted by simulating all possible perspectives caused by the
change of the camera’s optical axis orientation from a frontal position; (ii) these perspective rotations
are performed from a finite and small number of tilt-φ and ϖ-axis angles; (iii) for each simulated
image, the key points are extracted through gradient magnitude and orientation and based on histogram
analysis for each pixel in a 4 × 4 neighborhood.
Finally, the matching process is carried out by the employment of the SIFT descriptors over the
simulated images. These descriptors are matched firstly according to the Euclidean distance [23] and
secondly filtered by the Moisan–Stival ORSA (optimized random sampling algorithm) [28]. This
algorithm is a variant of RANSAC (Random Sample Consensus) [29] with an adaptive criterion to
filter the mismatches by the employment of the epipolar geometry constraints.

2.3. Hierarchical Orientation of Images

After the extraction and matching of the aforementioned features, the orientation of the images is
carried out by following a dual level that integrates computer vision with photogrammetry. The aim is
to obtain an approximate orientation of the images within an arbitrary system of coordinates (computer
vision), which may later be completely refined and improved for every image (photogrammetry).
First, it is necessary to carry out a relative orientation of the images through independent models by
calculating the fundamental matrix using the Longuet–Higgins algorithm [30]. One of the main
advantages of the fundamental matrix is that it is independent of the scene. Therefore, the matrix can
be calculated from the point correspondence in the image and does not require knowing the internal
parameters and initial approximations of the cameras. The fundamental matrix is defined by the
following equation:

x' T Fx  0 (3)

For each pair of matching points xi ↔ x'i (8 minimum), Equation (4) allows one to calculate the
fundamental matrix. More specifically, by writing x = (x,y,1) and x' = (x',y',1)T, each matching point
allows the creation of a linear equation,
x' xf 11  x' yf12  x' f13  y'xf 21  y' yf22  y'f 23  xf 31  yf32  f 33  0 (4)

It should be noted that this procedure guarantees full automation in comparison with other
photogrammetric approaches, where the user necessarily has to establish the initial approximations and
also know the internal parameters of the camera. Horn [31] provides an algorithm to recover the
baseline and relative orientation from the essential matrix, that is, assuming that an approximation for
the geometric internal parameters of the camera (focal length and principal point) are available, i.e., the
homogeneous 2D image coordinates are expressed as 3D photo vectors.
Second, once the relative angular and spatial position of the images is solved, we carry out a
comprehensive bundle adjustment by means of an iterative and least-squares process based on the

43

<!-- p. 58 -->

Remote Sens. 2014, 6 5678

collinearity condition [5] and by adding the object coordinates to allow a full georeferencing of the images
(Equation (5)). These object coordinates are incorporated into the orientation process thanks to the targets
spread about the scene or by means of natural points, whose coordinates are measured by expeditious
topographic survey (i.e., tape measure, manual measurement devices). In those cases when the internal
calibration parameters (focal length, principal point and lens distortion) are unknown, this step enables us
to add the calibration parameters of the camera to the equation as unknown quantities (self-calibration).
r11(X  S X )  r21(Y  S Y )  r31(Z  S Z ) (x - x0 )  x   f
r13 (X  S X )  r23 (Y  S Y )  r33 (Z  S Z )
(5)
r12 (X  S X )  r22 (Y  S Y )  r32 (Z  S Z ) (y - y0 )  y   f
r13 (X  S X )  r23 (Y  S Y )  r33 (Z  S Z )

where x and y are the image coordinates; X, Y, Z are the object control points coordinates from the
targets or natural points that allow the georeferencing of the scene; rij are the rotation matrix elements,
which include the rotation of the camera; SX, SY, SZ are the object coordinates of the points of view of
the camera; f is the principal distance; x0, y0 the principal point coordinates of the image; and ΔX, ΔY
the translations due to the radial and tangential distortion of the lens according to Equation (6).
x  2 4 6 2 2  2 x   r p1  2 p 2 x y  b1 x   b2 y  x x p  f x   r k1  r k 2  r k 3   f
(6)
y  2 4 6 2 2 2 y   r p 2 y y p  f y   r k1  r k 2  r k 3   2 p1 x y    f

This is the Fraser model [32], which takes into account additional parameters compared to the
Gaussian distortion model [33]: besides the principal distance (f) and principal point coordinates
(xp, yp), the radial distortion (k1, k2, k3) and tangential distortion (p1, p2) parameters are included.
Furthermore it considers terms for affinity (b1) and non-orthogonality (b2).
Two important considerations must be taken into account: (a) the bundle adjustment can be carried
out with or without the knowledge of the camera’s parameters. In the first case, the interior and the
lens distortion parameters are entered by their known value. In the second case, they must be
considered as unknown (self-calibration) and solved with the whole set of unknowns; (b) this is the
moment in which an absolute datum can be defined. This can be done by means of the object
coordinates of ground control points measured with any topographic method or even by means of
geometric constraints that define the 7 parameters of the coordinate frame.

2.4. Dense Model Generation

On the basis of the robust orientation of the image, a dense matching process has been developed.
Depending on the geometry of the shooting configuration, the process will use either an SGM or a
PMVS strategy by means of the projectivity Equation (7) [12]. This allows generating a dense model
capable of determining the exact 3D coordinate of the object for each pixel.
xk  C DRi  X k  Si  (7)

44

<!-- p. 59 -->

Remote Sens. 2014, 6 5679

where X is the object point, x the corresponding point in the image, R the camera rotation matrix, S the
center of projection of the camera, C the internal calibration function and D the lens distortion
function; and the k and i subscripts refer to the point and the image, respectively.
The SGM process consists of minimizing an energy function (8) along the 8 basic directions of a
pixel (every 45°). This function consists of a cost function, M (pixel matching cost), which accounts
for the degree of similarity of the pixels between two images, x and x', and the inclusion of two
restrictions, P1 and P2, which account for potential gross errors in the SGM process. In addition, a
further restriction based on the epipolar geometry of photogrammetry [34] has been added to the
SGM process. This restriction allows limiting the search space for each pixel, so that the high
computational cost of generating a dense model from multiple images is reduced, thus achieving better
processing times.

 
E ( D )  P2T  Dx  Dx '  1 (8) M  x , Dx    P1T  Dx  Dx '  1     
x  x 'N x x 'N x 

where E(D) represents the energy function to be minimized on the basis of disparity (parallax) between
matching features; function C (pixel matching cost) evaluates the degree of similarity between pixel p
and its correspondent q by means of its disparity or parallax Dp; the terms P1 and P2 represent two
restrictions, which avoid potential gross errors in the dense matching process caused by disparities in
one or more pixels.
On the other hand, the PMVS method allows obtaining a dense model through a hierarchical and
sequential process, which includes matching, expansion and filtering. In the matching phase, the points
of interest and corners are extracted by applying the Harris [35] and the difference-of-Gaussian (DoG)
operators. Later, a multiple image matching process is carried out on the basis of the previous
extraction and the normalized cross-correction (NCC) operator [36]. After the initial matching,
expansion and filtering functions are applied, which allow extending the initial matching to the nearest
pixels, as well as detecting and deleting erroneous matches by applying visibility restrictions.

\3. Results and Discussion

3.1. Context

The area of study is the region of Aliste (Zamora), with a total of 33 towns grouped into six
municipalities. The region of Aliste is located to the west of the province of Zamora (Spain), bounded
on the north by the mountain range of “La Culebra”, and adjacent to the regions of Sanabria and
La Carballeda. It is bordered to the east by the regions of “Tierras de Tábara” and “Tierras de Alba”,
and to the south by the region of Sayago. The west is adjacent to the Portuguese border, in the area
known as “la raya” (“The line”). Such a location highlights the outlying position, both geographic and
socioeconomically, which has marked the region throughout time. This area has been chosen due to its
geographical location, near the Portuguese border and the region of Sanabria, of which there are
previous similar studies. Therefore, it is possible to undertake comparative studies of the different
typologies of religious buildings. A total of 32 parish churches and five chapels have been analyzed
(Table 1).

45

<!-- p. 60 -->

Remote Sens. 2014, 6 5680

Table 1. Towns under analysis.

Municipality Town Municipality Town Municipality Town

Alcañices Fonfría Rábano de Aliste

Alcorcillo Arcillera San Mamed
ALCAÑICES RABANO
Santa Ana Bermillo de Alba Sejas de Aliste

Vivinera Brandilanes Tola

Figueruela de Arriba FONFRIA Castro de Alcañices Trabazos

Figueruela de Abajo Ceadea Latedo

Gallegos del Campo Fornillos Nuez de Aliste

Moldones Moveros San Martín del Pedroso

FIGUERUELA Riomanzanas Salto de Castro TRABAZOS Villarino tras la Sierra

Villarino de Manzanas Viñas de Aliste

Flechas Ribas
VINAS
San Blas

Vega de Nuez

Due to its location, the region of Aliste has always been a border area between different people and
cultures. The presence of Arabs in the area led to the depopulation of the Douro Valley, although the
subsequent Christian advance in the ninth century brought the population back. The emergence of new
monasteries inhabited by monks from the south of the Peninsula, who came to occupy the conquered
territories, was of central importance. That is how a series of monasteries arose, which gave new value
to fields that had not been farmed or were abandoned. In the same way, the individuals, nobles and
priests carried out a rural repopulation through the establishment of churches that fostered rural
development, thus promoting the creation of parish churches. Parish churches were not only a religious
center for the population, but also the center of administrative, social, economic and cultural activities
of the community.
The towns in Aliste were part of the Diocese of Braga until 1297, when the Treaty of Alcañices
transferred them to the Kingdom of León, thus creating the border with Portugal. The Templar Knights
settled in Aliste during the expansion of religious orders all over the Iberian Peninsula, which began in
the 13th century. In the 14th century, Aliste joined the Diocese of Santiago, after being part of the
Diocese of Astorga. Finally, in the 19th century, it joined the Diocese of Zamora.

3.2. Fieldwork

The method chosen to carry out the fieldwork is supposed to allow the documentation of a great
amount of buildings in a relatively short period of time (at least five churches per day). Moreover, the
cost is minimum (only a digital camera and a metric tape is necessary), and one person is enough for
the dataset acquisition.
The aim is to generate the necessary graphic documentation to carry out a typological study of the
religious buildings of the border municipalities in the region of Aliste (Zamora). The results are
presented in the form of ground plans and profiles with photographic texture and axonometric view.
The output scale is 1/200, as such documentation may be included in what several authors refer to as

46

<!-- p. 61 -->

Remote Sens. 2014, 6 5681

the “preliminary level of documentation” [37,38], this being the minimum scale recommended. The
scale demands a minimum accuracy of 40 mm.
The photos were taken with a reflex camera, Canon EOS 350D, set to the lowest ISO and with an
aperture in the range from ƒ/4 to ƒ/5. Moreover, the focal length, 18 mm, was fixed throughout the
shooting process. According to Equation (1), a 1/200 scale allows a maximum distance to the object of
112.5 m, which means a footprint of 138 × 92 m in every shot. Therefore, the shooting distance is
lower than the maximum recommended, thus guaranteeing a higher accuracy than the minimum
required for the 1/200 scale. However, the major problem was the width of the streets that surrounded
the churches, as they define the maximum distance allowed to take the photos, as well as the part of the
scene that can fit into every image and, therefore, the minimum number of images needed.
The circular or “ring” shot strategy was used for documenting the building, trying to maintain a
constant distance to the building. The images’ network around the building is designed to keep an
appropriate proportion between the distance to the object and the distance between images, which is
around 0.26 (Figure 3). This factor is the result of calculating the tangent of the 15° angle of
intersection with the object, referred to in Subsection 2.1. This factor is important for the generation of
dense models, since it guarantees small baselines between cameras and, thus, a fully documented
point cloud.

Figure 3. Images following a “ring” shot strategy around the parish church of Ceadea.

Every church had external conditioning factors (e.g., narrow perimeter streets, fences, private
properties, etc.), which made it impossible to fit the whole object into the image, at least for one of the
façades. In such cases, a planar or mosaic shot of the area was performed, making sure that the images
had an overlap rate of at least 80%. We made sure of having convergent (oblique) images to “tie” the
circular shots and the mosaic shots in order to obtain a precise orientation.
According to Figure 3, the best scenario was the church in Ceadea. The fact that the church is
isolated from the urban area, small and low, made it possible to take the photos at a sufficient distance
to close the ring with just 28 shots, which includes the roofs of the building. The mosaic network was
used only for the south façade, as the minimum distance was five meters (the six last images in
Figure 4). The other churches were part of the urban area and were adjacent to other buildings, which

47

<!-- p. 62 -->

Remote Sens. 2014, 6 5682

made it impossible to fit the whole image in one single shot, thus forcing us to take more photos with
an overlap rate of 80%. On the other side, the worst scenario was the church in Trabazos, which is one
of the biggest churches in our study. It has a high belfry tower and three façades facing narrow
streets three to four meters wide, which forced us to take 177 photos in order to close the shooting ring
around the building. We had to use the mosaic network technique for every façade, except for the
eastern one, which faces a big square (Figure 4).

Figure 4. Some of the images used to document the parish church in Trabazos.

Finally, the distance between two points in the images were measured so as to establish the metric
requirements of the 3D model, which was later created in the laboratory. Simple methods (tape
measure, manual measurement devices) were used to measure the distance between two distant points
for each of the building faces. However, this step may be skipped by incorporating some kind of stake,
whose size must be known and which must appear in at least three images to allow the establishing of
the scale of the model.

3.3. Laboratory Work

We used PW for the laboratory work, which allows us to generate the 3D models that determine the
outside geometry of the church and, therefore, the scaled 3D models and the resulting photo-realistic
profiles. The interior of the churches has not been modeled through a rigorous photogrammetric
procedure. Instead, the most important features (e.g., wall thickness and internal distances) were
measured with tape measure in order to complete the ground plans of every church.
Following the aforementioned workflow (Figure 1), the automatic orientation of the images was
undertaken, which resulted in a scattered point cloud (Figure 5, left). Then, the erroneous points
were deleted for a better outcome. Afterwards, a dense point cloud was automatically generated
(Figure 5, right).
In order to generate the dense point cloud of the church in Ceadea, 28 images were used, while in
the case of Trabazos, 121 images were used (those more perpendicular to the faces to be modeled).
Due to the different geometric characteristics and the external conditions in both buildings, the roofs of
the church in Ceadea were modeled, thanks to the shooting distance. However, the modeling of the
church in Trabazos was not possible, because of the adjacent buildings and the height of the church.
On the contrary, and due to the proximity to the faces, the point density is higher in the model of
Trabazos, and therefore, the level of detail is higher than that of the church in Ceadea.

48

<!-- p. 63 -->

Remote Sens. 2014, 6 5683

Figure 5. Scattered point cloud from the matching process (left) and dense point cloud
from the SGM or PMVS strategy (right). The parish church in Ceadea (top) and the parish
church in Trabazos (bottom).

After removing noise from the images, the point cloud was divided into sections in order to outline
the ground plan and export it to a CAD program, so as to draw the geometry. Moreover, we obtained
the orthogonal profiles of the façades and then processed them with a CAD program to get the final
product (Figure 6).
The main technical data obtained in the processing phase are recorded in Table 2.
The number of images for each model reflects the size of the building and the characteristics of its
surroundings. The time spent on fieldwork is determined by the number of images and the use of a
tripod depending on the lightning conditions. The time spent on laboratory work can be divided into
two phases. The first phase consists of masking the images by hand, whereas the image orientation and
the generation of the dense point cloud are completed automatically. The time spent on these processes
is directly related to the number of images. The second phase consists of removing noise from the
model, generating the orthophotos and outlining the plans. In this case, the amount of time depends on
the size of the church.

49

<!-- p. 64 -->

Remote Sens. 2014, 6 5684

Figure 6. Final graphic documentation of the churches of Ceadea (top) and Trabazos
(bottom): ground plan, orthogonal profiles with photographic texture and photorealistic
3D model.

Table 2. Main technical data obtained from the processing of the ten case studies. GSD,
ground sample distance.

Fornillos Vivinera Rabano Tola Trabazos Sejas Santa Ana Ribas Ceadea S. Martin Pedroso

FIELDWORK

25 × 16 18 × 16 21 × 13 22 × 16 27 × 16 32 × 17 20 × 15 23 × 16 19 × 10 22 × 15
Measurements (m)
× 20 × 12 × 12 × 14 × 23 × 22 × 10 × 11 × 11 × 13

No. of images 86 72 127 152 177 78 38 91 28 79

Distance max/min (m) 22.40/10.30 16.20/4.50 30.80/3.50 25.30/2.90 25.30/2.60 16.50/2.80 15.10/4.50 19.30/9.70 30.15/5.20 31.10/5.70

Fieldwork (minutes) 45 40 50 60 70 45 35 40 30 45

LABORATORY WORK

Tie points 227,666 252,895 407,975 651,467 429,726 353,976 188,221 249,567 82,149 224,492

No. of 3D points 22,319,921 20,913,054 39,624,832 53,447,764 44,416,441 25,141,761 11,138,274 17,894,546 4,854,354 17,302,829

GSD (m) 0.008 0.007 0.006 0.006 0.006 0.006 0.006 0.008 0.007 0.008

RMSE (m/pix) 0.0022/0.28 0.0014/0.260.0018/0.31 0.0037/0.330.0011/0.18 0.0017/0.280.0015/0.26 0.0023/0.300.0015/0.22 0.0022/0.29

Laboratory work (hours) 14 10 15 15 17 16 7 12 6 12

Once the graphic data of every church is collected, a typological study of the buildings, together
with its classification in families, types and variants, is carried out.

3.4. Typological Analysis

The working line followed by San José(1994) [39] has been a point of reference for the typological
analysis. A similar study for the religious buildings of the border towns in the area of Aliste has been
developed, though in this case, the last generation of low-cost photogrammetric and computer vision
methods both in the shooting process and the generation of 3D models have been used. In order to
classify the churches, the starting point were the families, which are made up of the different building

50

<!-- p. 65 -->

Remote Sens. 2014, 6 5685

systems, and these, in turn, divided into subsystems and variants. The study was limited to the
classification of the parish churches in the rural areas of Aliste, as they are the most numerous and
representative group.
The parish churches have been classified according to the study of their ground plans, by means of
analyzing the layout of the essential architectural elements: nave, chapel and transept. As a result, two
groups or families have been established: churches with transept and churches with chapel. From these
two groups, the different types of churches in the area were classified according to the number of
naves, which resulted in new subtypes. The variants were established according to the size of the
essential structures, the layout of the belfry and the complementary architectural elements attached to
the main structure (e.g., chapels, sacristy, arcade, etc.).

Figure 7. Typological classification of the parish churches according to the ground plan of
the essential architectural structures.

The methodology adopted for the typological analysis of the churches consisted of visiting and
studying each temple to establish by means of comparison the different types. For this, the study is
based on the structures that make up the temples and the way in which they are linked together. Thus,
the first classification is attained: temples with transept and temples with chapel. On this basis, the
number of naves determines the variants or subtypes.

51

<!-- p. 66 -->

Remote Sens. 2014, 6 5686

With regard to the classification, the differences previously established on the basis of shape,
number and arrangement, linked together to shape the temple, are essential for gathering the studied
buildings into groups with similar characteristics. This results in the final classification of the different
types and its classification into typologies and variants. Thirty two parish churches and five chapels
have been analyzed, and the typological classification of the churches has been outlined in accordance
to the layout of the nave and either the chapel or transepts, as well as its size. We have chosen one
church from each group to be included in the results (Figures 7 and 8). The parish churches consisting
of one single nave and a chapel are by far the most numerous group of religious architecture in the
area. The structure includes the rectangular ground plan of the nave and the square ground plan of the
main chapel, which, according to Christian tradition, is oriented east-west. The final structure results
from attaching the supplementary architectural elements, such as entrance arches, sacristy, belfry, etc.,
to the main structure. The belfry is especially relevant in the volumetric configuration of the temples.
In this study, every church is crowned by a bell gable, though there are different types.

Figure 8. Typological classification of the parish churches according to the spatial design
of the essential architectural structures.

With regard to the building system, these churches are simple constructions consisting of perimeter
load-bearing walls and semicircular arches in the junction between the nave and the chapel. The roof

52

<!-- p. 67 -->

Remote Sens. 2014, 6 5687

consists of a wood couple roof (a gabled roof in the nave and a hipped roof in the chapel) in those
cases where the chapel is higher than the nave.
The variants of this type of buildings are determined by the volumetric ratio between the nave and
the chapel (Figure 8). Therefore, there are some churches in which the nave and chapel are the same
size and height, others where the nave and the chapel have the same width, but the chapel is higher
than the nave and, finally, those where the nave and the chapel have different sizes and heights. The
most numerous group within the churches in this study belong to the latter group, thus being the
prevailing typology of religious architecture in the area. The last variation would be a church where the
chapel and the nave have a different width and height, thus creating two well-differentiated parts
within the essential spaces of the temple.
The group made up of churches with three naves and one chapel is the less numerous one. The
structure consists of two side naves attached to the main nave and chapel, which are accessed from the
central nave through semicircular arches on columns.
The parish churches of one nave and crossing are the biggest ones and are normally located in the
most populated towns.

\4. Conclusions

The study shows the capacity of photogrammetric programs, which are aimed towards the full
automation of the cartographic modeling process, for the architectural interpretation of religious
buildings. By means of a relatively simple working methodology, used both in the shooting and
processing phase, accurate and high graphic quality results can be obtained. Thanks to
photogrammetric tools, the aim of creating a typological classification of the parish churches in the
region of Aliste has been made easier and is based on technical data.
The following conclusions from the present study can be drawn:

(a) The graphic quality of the models is supported basically by the point quantity, between
20 and 50 million points, which usually equals or surpasses the resolution provided by
terrestrial laser systems (TLS).
(b) Even though the data volume may seem high, the working times must be taken into account:
between 30 and 60 min of fieldwork and from 6 to 16 h of laboratory work, which, once
again, can be compared with laser scanner performance. The image capture times are lower
than those of a laser scanner (between 1/2 and 1/3 depending on the TLS performance),
whereas the laboratory work times are similar. Therefore, compared to laser scanner
technology in terms of devices availability and the difficulty of processes, photogrammetry
stands out as a more advantageous solution.
(c) The high degree of accuracy (root mean square deviation of block adjustment; the results
range from 1/4 to 1/3 of a pixel) is mainly due to the high level of redundancies (high
number of tie points), which allows the user to adjust the images accurately
(d) The high level of redundancies (tie points), between 80,000 and 650,000 with an average of
about 300,000, is due to the high number of images, between 28 and 177 with an average of
about 90. Although the number of images may seem excessive, this issue must be contrasted
to the time spent in the process.

53

<!-- p. 68 -->

Remote Sens. 2014, 6 5688

(e) The results are highly consistent with each other: RMS are always between 0.18 and
0.33 pixels or between 0.0011 and 0.0037 mm, which guarantee the quality and reliability of
the methodology chosen for the study.
(f) The different number of images needed for each church, which ranges from 28 to 177, as
stated before, depends on the surroundings of the religious building, as well as on the
possibility of fitting the whole object into the image. The size of the building is also
important, although all the different aspects do not result in relevant differences, either in
time or accuracy.
(g) With regard to the typological analysis, the approach developed improves the current
techniques for the recording of architectural cultural heritage. Moreover, the method is
suitable to carry out a typological classification study, where the reduction of image capture
times (between 1/2 and 1/3, as stated above) allows the researcher to document a great
number of buildings/architectural heritage in little time and by non-specialist staff, due to
the simplicity of the process. Besides, the high resolution of the models, with GSDs between
0.006 and 0.008 mm, indicates that the method could be used for projects that require
larger scales.
(h) These methods are appealing to architects due to their simplicity and speed. Better quality
and more robust surveys are obtained, as not only the shape of the building was accessed,
but also the information about its color and texture. The fieldwork hours are reduced with no
negative effect on accuracy, and it is easier to systematize the process, by following the
protocol set out in the present study.

With regard to future action lines, it is worth mentioning:
The aim would be to apply the methodology to other contexts and architectural typologies, in order
to compare the scope and validity of the method. This could lead to the creation of a good practices
guide to help the inexperienced user choose a line of action that optimizes the relation between
accuracy and working time.
It will be important to look at further ways of adding any type of metric constraint to the
methodology, so as to avoid manual measuring between several points of the object, thus reducing the
working times and, more importantly, reducing the potential sources of error.
Finally, the implementation of processing strategies that enable progress on the automation
of point clouds should also be undertaken, in order to facilitate the process of turning point clouds into
vector models.

Author Contributions

All authors contributed extensively to the work presented in this paper.

Conflicts of Interest

The authors declare no conflict of interest.

54

<!-- p. 69 -->

Remote Sens. 2014, 6 5689

References

\1. Haala, N.; Peter, M.; Kremer, J.; Hunter, G. Mobile lidar mapping for 3D point cloud collection in
urban areas—A performance test. Int. Arch. Photogramm. Remote Sens. Spat. Inf. Sci. 2008, 37,
1119–1127.
\2. Schindler, K. An overview and comparison of smooth labeling methods for land-cover
classification. IEEE Trans. Geosci. Remote Sensi. 2012, 50, 4534–4545.
\3. Liu, G.-H.; Liu, X.-Y.; Feng, Q.-Y. High-accuracy three-dimensional shape acquisition of a
large-scale object from multiple uncalibrated camera views. Appl. Opt. 2011, 50, 3691–3702.
Gruen, A.; Akca, D. Mobile Photogrammetry. In Dreiländertagung SGPBF, DGPF und OVG; In
Proceedings of 2007 Wissenschaftlich-Technische Jahrestagung der DGPF, Muttenz, Basel,
19–21 June 2007; Volume 16, pp. 441–451.
\4. Kraus, K. Photogrammetry. Fundamentals and Standard Processes; Dummlers Verlag: Bonn,
Germany, 1993; Volume 1.
\5. Arias, P.; Caamano, J.C.; Lorenzo, H.; Armesto, J. 3D modeling and section properties of ancient
irregular timber structures by means of digital photogrammetry. MICE Comput.-Aided Civ.
Infrastruct. Eng. 2007, 22, 597–611.
\6. Lorenzo, H.; Arias, P. A methodology for rapid archaeological site documentation using
ground-penetrating radar and terrestrial photogrammetry. Geoarchaeology 2005, 20, 521–535.
\7. Arias, P.; Armesto, J.; Vallejo, J.; Lorenzo, H. Close range digital photogrammetry and software
application development for planar patterns computation. Dyna 2009, 76, 7–15.
\8. Robertson, D.P.; Cipolla, R. Structure from Motion. In Practical Image Processing and Computer
Vision; John Wiley: Hoboken, NJ, USA, 2009; p. 49.
\9. Quan, L. Image-Based Modeling; Springer: New York, NY, USA, 2010.
\10. Szeliski, R. Computer Vision: Algorithms and Applications; Springer: New York, NY, USA,
2011; p. 824.
\11. Hartley, R.; Zisserman, A. Multiple View Geometry in Computer Vision; Cambridge University
Press: Cambridge, UK, 2000.
\12. Hirschmüller, H. Accurate and Efficient Stereo Processing by Semi-Global Matching and Mutual
Information. In Proceedings of the 2005 IEEE Computer Society Conference on Computer Vision
and Pattern Recognition, San Diego, CA, USA, 20–25 June 2005.
\13. Deseilligny, M.P.; Clery, I. Apero, an Open Source Bundle Adjusment Software for Automatic
Calibration and Orientation of Set of Images. In Proceedings of the 2011 ISPRS Commission V
Symposium, Image Engineering and Vision Metrology, Trento, Italy, 2–4 March 2011;
Volume XXXVIII-5/W16; pp. 269–276.
\14. Habbecke, M.; Kobbelt, L. Iterative Multi-View Plane Fitting. In Proceedings of the
2006 International Fall Work-Shop Vision, Modeling, and Visualization. Aachen, Germany,
22–24 November 2006; pp. 73–80.
\15. Seitz, S.M.; Curless, B.; Diebel, J.; Scharstein, D.; Szeliski, R. A Comparison and Evaluation of
Multi-View Stereo Reconstruction Algorithms. In Proceedings of the 2006 IEEE Computer
Society Conference on Computer Vision and Pattern Recognition, Washington, DC, USA, 17–22
June 2006; Volume 1, pp. 519–528.

55

<!-- p. 70 -->

Remote Sens. 2014, 6 5690

\16. Furukawa, Y.; Ponce, J. Accurate, dense, and robust multiview stereopsis. IEEE Trans. Pattern
Anal. Mach. Intell. 2010, 32, 1362–1376.
\17. Waldhäusl, P.; Ogleby, C. 3 × 3 rules for simple photogrammetric documentation of architecture.
Int. Arch. Photogramm. Remote Sens. 1994, 30, 426–429.
\18. Patias, P.; Santana Quintero, M. Introduction to Heritage Documentation. In CIPA
Heritage Documentation Best Practices and Applications; Stylianidis, E., Patias, P.,
Santana Quintero, M., Eds.; The ICOMOS & ISPRS Committee for Documentation of Cultural
Heritage: Athens, Greece, 2011; Volume XXXVIII-5/C19, pp. 9–13.
\19. Joglekar, J.; Gedam, S.S. Area based image matching methods—A survey. Int. J. Emerg. Technol.
Adv. Eng. 2012, 2, 130–136.
\20. Gruen, A. Adaptive least squares correlation: A powerful image matching technique. S. Afr. J.
Photogramm. Remote Sens. Cartogr. 1985, 14, 175–187.
\21. Smith, S.M.; Brady, J.M. Susan—A new approach to low level image processing. Int. J. Comput.
Vis. 1997, 23, 45–78.
\22. Lowe, D.G. Object Recognition from Local Scale-Invariant Features. In Proceedings of the 1999
IEEE International Conference on Computer Vision, Kerkyra, Greece, 20–27 September 1999;
Volume 2, pp. 1150–1157.
\23. Matas, J.; Chum, O.; Urban, M.; Pajdla, T. Robust Wide Baseline Stereo from Maximally Stable
Extremal Regions. In Procceding of the 2002 British Machine Vision Conference, Citeseer,
Cardiff, UK, 2–5 September 2002; pp. 384–393.
\24. Bay, H.; Ess, A.; Tuytelaars, T.; van Gool, L. Speeded-up robust features (surf). Comput. Vis.
Image Underst. 2008, 110, 346–359.
\25. Morel, J.-M.; Yu, G. Asift: A new framework for fully affine invariant image comparison.
SIAM J. Imaging Sci. 2009, 2, 438–469.
\26. Lowe, D.G. Distinctive image features from scale-invariant keypoints. Int. J. Comput. Vis. 2004,
60, 91–110.
\27. Moisan, L.; Stival, B. A probabilistic criterion to detect rigid point matches between two images
and estimate the fundamental matrix. Int. J. Comput. Vis. 2004, 57, 201–218.
\28. Fischler, M.A.; Bolles, R.C. Random sample consensus: A paradigm for model fitting with
applications to image analysis and automated cartography. Commun. ACM 1981, 24, 381–395.
\29. Longuet-Higgins, H.C. A computer algorithm for reconstructing a scene from two projections.
Nature 1981, 293, 133–135.
\30. Horn, B.K.P. Recovering baseline and orientation from essential matrix. J. Opt. Soc. Am. 1990,
1–10.
\31. Fraser, C.S.; Shortis, M.R.; Ganci, G. Sensor and System Calibration. In Multisensor System
Self-Calibration; Society of Photo-Optical Instrumentation Engineers (SPIE): Philadelphia, PA,
USA, 1995; pp. 2–18.
\32. Brown, D. Close-range camera calibration. Photogramm. Eng. 1971, 37, 855–866.
\33. Luhmann, T.; Robson, S.; Kyle, S.; Harley, I. Close Range Photogrammetry: Principles, Methods
and Applications; Whittles: Dunbeath, UK, 2007; p. 528.
\34. Harris, C.; Stephens, M. A Combined Corner and Edge Detector. In The Fourth Alvey Vision
Conference; University of Sheffield Printing Office: Manchester, UK, 1988; pp. 147–151.

56

<!-- p. 71 -->

Remote Sens. 2014, 6 5691

\35. González, R.C.; Woods, R.E. Digital Image Processing, 3rd ed.; Addison-Wesley: Massachusetts,
MA, USA, 1992.
\36. Almagro Gorbea, A. Levantamiento Arquitectónico; Universidad de Granada: Granada,
Spain, 2004.
\37. Letellier, R.; Schmid, W.; LeBlanc, F.; Eppich, R.; Chabbi, A. Recording, Documentation, and
Information Management for the Conservation of Heritage Places: Guiding Principles;
Getty Conservation Institute: Los Angeles, CA, USA, 2007.
\38. San José Alonso, J.I. Arquitectura Religiosa en Sanabria: Sus Espacios, Organizaciones y
Tipologías; Instituto de Estudios Zamoranos Florián de Ocampo: Zamora, Spain, 1994.

© 2014 by the authors; licensee MDPI, Basel, Switzerland. This article is an open access article
distributed under the terms and conditions of the Creative Commons Attribution license
(http://creativecommons.org/licenses/by/3.0/).

57

<!-- p. 72 -->



<!-- p. 73 -->

Documentación y análisis geométrico del patrimonio arquitectónico a partir de métodos
fotogramétricos con una y múltiples imágenes

4.3 CONFRONTING PASSIVE AND ACTIVE SENSORS WITH NON-GAUSSIAN
STATISTIC

Resumen: Este trabajo tiene dos hitos: en primer lugar, comparar los Modelos
Digitales de Superficie (DSM) obtenidas por sistemas de sensores remotos pasivos
(cámara digital) y activos (láser escáner terrestre), aplicada a los objetos
arquitectónicos específicos; y en segundo lugar, poner a prueba cómo se comportan
las estadísticas clásicas Gaussianas, con su principio de Mínimos Cuadrados, a los
conjuntos de datos donde pueden aparecer errores groseros asimétricos y si este
enfoque se debe cambiar por uno no paramétrico. El campo de la Geomática se
encuentra inmerso en una carrera competitiva hacia la automatización y mejora de
instrumentos y técnicas. Hoy en día, parece que estamos presenciando una mejora
de la fotogrametría y su integración con la visión computacional en favor de mejorar
la automatización y calidad de resultados frente a su competidor más cercano, los
sistemas de escaneo láser. A través de este trabajo se realiza una comparativa entre
ambos sistemas en términos de calidad. Los resultados obtenidos muestran una
buena concordancia entre los dos sensores, a pesar de la asimetría presente en
ambos sistemas debido a la presencia de errores groseros. Esta asimetría sugiere que
los parámetros normales estándar no son adecuados para evaluar este tipo de datos,
especialmente cuando la precisión es de suma importancia. En este caso, la
desviación estándar no proporciona una buena estimación de los resultados,
mientras que los resultados obtenidos para la desviación media absoluta y para la
Bivarianza Ponderada son medidas más apropiadas.
Palabras clave: sensores pasivos; sensores activos; cámara digital; láser escáner;
estadística no gaussiana; estadística no paramétrica; medición

59

<!-- p. 74 -->



<!-- p. 75 -->

Sensors 2014, 14, 13759-13777; doi:10.3390/s140813759
OPEN ACCESS
sensors
ISSN 1424-8220
www.mdpi.com/journal/sensors
Case Report

Confronting Passive and Active Sensors with
Non-Gaussian Statistics

Pablo Rodríguez-Gonzálvez, Jesús Garcia-Gago, Javier Gomez-Lahoz and
Diego González-Aguilera *

Department of Cartographic and Land Engineering, University of Salamanca,
Polytechnic School of Avila. Hornos Caleros, 50, 05003, Avila, Spain;
E-Mails: pablorgsf@usal.es (P.R.-G.); jesusmggago@gmail.com (J.G.-G.); fotod@usal.es (J.G.-L.)

\* Author to whom correspondence should be addressed; E-Mail: daguilera@usal.es;
Tel.: +34-920-353-500; Fax: +34-920-353-501.

Received: 21 May 2014; in revised form: 22 July 2014 / Accepted: 28 July 2014 /
Published: 30 July 2014

Abstract: This paper has two motivations: firstly, to compare the Digital Surface Models
(DSM) derived by passive (digital camera) and by active (terrestrial laser scanner) remote
sensing systems when applied to specific architectural objects, and secondly, to test how
well the Gaussian classic statistics, with its Least Squares principle, adapts to data sets
where asymmetrical gross errors may appear and whether this approach should be changed
for a non-parametric one. The field of geomatic technology automation is immersed in a
high demanding competition in which any innovation by one of the contenders
immediately challenges the opponents to propose a better improvement. Nowadays, we
seem to be witnessing an improvement of terrestrial photogrammetry and its integration
with computer vision to overcome the performance limitations of laser scanning methods.
Through this contribution some of the issues of this “technological race” are examined
from the point of view of photogrammetry. A new software is introduced and an
experimental test is designed, performed and assessed to try to cast some light on this
thrilling match. For the case considered in this study, the results show good agreement
between both sensors, despite considerable asymmetry. This asymmetry suggests that the
standard Normal parameters are not adequate to assess this type of data, especially when
accuracy is of importance. In this case, standard deviation fails to provide a good
estimation of the results, whereas the results obtained for the Median Absolute Deviation
and for the Biweight Midvariance are more appropriate measures.

61

<!-- p. 76 -->

Sensors 2014, 14 13760

Keywords: passive sensor; active sensor; digital camera; laser scanner; non-Gaussian
statistic; non-parametric statistic; measurement

\1. Introduction

1.1. Motivation

There is little doubt that use of photogrammetry has undergone a resurgence in its duel with the
powerful laser scanning systems, both terrestrial (TLS-Terrestrial Laser Scanner) and aerial
(ALS-Airborne Laser Scanner), and both static and dynamic (MMS-Mobile Mapping System) [1].
During the second half of the last decade, the latter seemed to pose an insurmountable challenge for
the former technology which looked almost decadent, but quite surprisingly, we are witnessing a return
of photogrammetry in the geomatic market, where nothing is yet decided.
The secret of the success of the recent photogrammetry proposals is based on two issues: firstly, its
bid to continue trusting/relying on the strength of its information source, the image; secondly, its
“marriage” with its “relative”, computer vision [2]. This hybridization has enabled the discipline to
overcome two important hurdles. The first one has been surpassed by the automation of the orientation
and reconstruction processes. This led to highly dense three dimensional models that in many cases
surpass the resolution of laser scanning ones. The second obstacle was related to the classical rigid
geometric configuration in the shooting network, namely, the so called, normal case. Nowadays, this
configuration has been substituted by a highly flexible one. In addition, any type of sensor, calibrated
and non-calibrated [3], or even smartphone or tablet devices [4] can be used. Besides these two recent
performance developments, there is a third issue that has characterized photogrammetry over the years
as a metrology discipline: its compromise with respect to accuracy in order to increase reliability [3].
This traditional line has yielded results that, in many applications, can stand as a low cost competitor to
the laser systems.
On the other hand, but no less important, we are aided by a proliferation of multipurpose, low cost
or even free, open source tools that deal with multiple image processing to render 3D geometric and
radiometric models. This challenge requires solving two previous important geometric issues: how to
compute the camera parameters (interior orientation, principal distance or focal length, coordinates
of the principal point, and radial and tangential distortion parameters) and how to compute the
shooting parameters (exterior orientation, world coordinates of the point of view and angular
parameters—rotation matrix—of the camera axis when shooting) [4]. For years, photogrammetry
addressed these problems by applying rigorous laboratory calibration protocols and later with robust
and accurate control points networks, but the implementation and fusion of algorithms and techniques
largely developed on the computer vision community has led to the automatic computation of these
items while computing the 3D model itself.
More specifically, great advances have occured in the use of robust strategies for image matching
based on features (FBM-Feature Based Matching) and on areas (ABM-Area Based Matching) that
enable the task of linking the images to one another or to some external element and thus, making

62

<!-- p. 77 -->

Sensors 2014, 14 13761

available the transition from the 2D information to the 3D information, an issue that was traditionally
performed through stereoscopic skills.
As is well known this is the basis of photogrammetry since it can enable the computation of the
interior and relative exterior orientations and, at the same time, the computation of a sparse model of
the object on a local and arbitrary frame [5]. A certain knowledge of the frame (through control points
or through an explicit datum definition), enables the application of the colinearity equations [6] that
leads to an absolute model location through: (a) the reverse intersection problem that renders the
absolute exterior orientation of the images and (b) the forward intersection problem that yields the
absolute coordinates of any object point from corresponding image sets (at least two) of points.
In this regard, very important and powerful innovations in the field of matching have been achieved
in the last years. Firstly there is the powerful but dependent on a favourable geometry (photogrammetric
normal case) semi-global matching (SGM) strategy [7] which permits rendering of high density
3D point clouds with resolutions up to the Ground Sampling Distance (GSD), that is, one 3D object
point for each pixel of the image. Apero-Micmac [8] is a good example of Open Source software
beside commercial photogrammetric tools (eATE, NGATE,Dense Matcher, ISAE, Match-T, Xpro,
Tridicon, etc.). In any case, other important achievements exist in the case of unfavourable geometry,
such as those patch-based methods supported by surfels [9–11]. In this sense, Patch-based Multi-view
Stereo (PMVS) assumes a hybrid approach, using undistorted images, orientation parameters of the
images, a sparse set of points and the projection matrixes to determine a dense set of rectangular
patches. Nevertheless, the major drawback of these commercial and web-based tools (Bundler,
Photosynth, Photofly, PMVS, etc.) is that they are only based on computer vision algorithms and thus
they do not provide accurate results. Last but not least, an additional drawback for these web-based
methods is their computation cost, especially if large format cameras and high resolution images are
involved. All these considerations suggest the need for further research towards the implementation
of parallel processing techniques and the use of the graphical memory in order to minimize the
processing effort.
One of the main goals of this paper is to present the Photogrammetry Workbench (PW) software as
an attempt to reinforce the relation between photogrammetry and computer vision in the context of the
Heritage Architecture field according to the considerations stated above, but an even more important
motivation is to implement and assess some statistical tools to improve the processing of data that does
not behave in a Gaussian fashion, which is the usual case when dealing with automated point clouds,
regardless of whether they are generated by photogrammetry or laser scanning.
About 15 years ago, Kraus coined the motto “quantity vs. quality”. He did so to try to illustrate the
change of paradigm that digital photogrammetry was leading. Traditional photogrammetry was very
much based on quality, that is, on human skill, and therefore, on Gaussian statistics. As is well known [3],
the redundant display that underlies aerial triangulation or the bundle adjustment is solved through the
Least Squares Criteria that assumes that the image observations follow a normal distribution, namely,
they can be represented by means of a standard deviation. This was representative of the human ability
to perform good but few observations (redundancy not higher than 50). Contrary to this manual
paradigm is the automatic one that relies heavily on the computer’s capacity to perform poor but
abundant observations, that is, based on quantity. This means that besides a high number of correct

63

<!-- p. 78 -->

Sensors 2014, 14 13762

redundant observations (many more than 100) the process is plagued by a number of gross errors
(outliers) and consequently, the mean—standard deviation—least squares assumptions must be revised.

1.2. Objectives

The main objectives of this case report were to test the comparison of photogrammetric and laser
scanning point clouds and to test the performance of Gaussian and non-Gaussian statistics when
comparing data sets. For this purpose an experiment was designed in which two Romanesque portals
were captured by means of two laser scanning systems and photogrammteric systems (digital
cameras). The photogrammetric processing of the images was done by means of two software
packages: one developed in-house by the authors and a well-known commercial software (see
Section 4 for a more detailed description of the experiment).

\2. From a Set of 2D Images to a Dense 3D Point Cloud

The software here presented, PW, is a multiplatform software which integrates photogrammetric
robust algorithms with automatic and flexible approaches coming from computer vision operating
behind a user-friendly interface that works with terrestrial or aerial images and with vertical or oblique
geometries. This software works on two parts that correspond to the classical main steps in
photogrammetry: orientation and modelling. The input of the first part (orientation) is a dense set of
matching points extracted from a set of images by means of a robust operator and the output is the
exterior orientation parameters of these set of images. The input of the second part (modelling) are
these set of orientation parameters and an optimized version of the same set of matching points used
for the first part. The final output is a dense point cloud that can withstand the comparison with 3D
laser scan point clouds.

2.1. Extraction of Matching Points from the Images

The task of finding matching features that appear in corresponding images, and the degree of
variation between the patches of images to be compared are very important issues. On the most simple
side of the wide range of approaches that have been implemented to deal with this question, we have
the most classical matching method in photogrammetry: ABM [12]. This method works efficiently
because it demands a priori that images have been taken under the classical geometric paradigm of
aerial photogrammetry: the so called, normal case. As is well known, this implies, firstly, that images
must be almost parallel to the object and thus, with no perspective effects between them. Secondly, the
variation implies, secondly, that the variation of distance to the object must be kept under small
thresholds (terrain surface, the object of aerial photogrammetry, is usually smooth). So, when dealing
with images that exhibit important perspective variations or important scale variations, this method
does not render acceptable results.
Thus, a variety of methods have been developed in recent years to handle these variations between
images. It has been usually assumed that these variations can be modelled by a translation, a change in
scale and a rotation. Some of these methods are Smallest Univalue Segment Assimilating Nucleus
(SUSAN) [13], Scale Invariant Feature Transform (SIFT) [14], Maximally Stable Extremal Region

64

<!-- p. 79 -->

Sensors 2014, 14 13763

(MSER) [15], or Speeded Up Robust Features (SURF) [16]. None of these algorithms are robust
enough to cope with high perspective variations between images.
Affine Scale Invariant Transform (ASIFT) [17] is a method that is affine invariant on a local region
patch and has proved to be robust enough to deal with images that present rather large perspective
effects as a whole. In ASIFT, two rotation parameters are added to the plane rotation that is included in
the methods mentioned above. This provides the two degrees of freedom that render the two angles of
a line (camera axis) with respect to a plane (main object plane). Consequently, the algorithm enables
one to work with perspective images, which are frequent in terrestrial photogrammetry.

2.2. Orientation Procedure

The matching points derived from the ASIFT operator are the input for the orientation procedure
which is performed in two steps. In the first one, a pairwise orientation is executed by relating the
images to each other by means of the fundamental matrix model. In the second one, this initial and
partial approximation to the solution is used to perform a global bundle adjustment by means of the
colinearity equations which include the determination of the camera parameters (self-calibration).

2.2.1. Relative Orientation

The five degrees of freedom that underlie the non-linear equations (coplanarity equation [6] that
relate whatever two images that share corresponding features can be expressed by a eight parameter
linear model, based on the so called fundamental matrix [5] computed by the Longuet-Higgins
algorithm [18] according to the equation:
x' xf11 + x' yf12 + x' f13 + y' xf 21 + y' yf 22 + y' f 23 + xf 31 + yf32 + f 33 = 0 (1)

where fij are the terms of the 3 × 3 fundamental matrix and (x, y) and (x´, y´) are the image coordinates
of every pair of matching points. Once these terms are obtained, the five geometric parameters that
express the relative position (up to scale) and attitude of one image respect the other can be
derived [19] provided an approximate description of the camera is known. In this way we obtain an
initial estimation of a pairwise orientation of the images given an arbitrary datum.

2.2.2. Bundle Adjustment

The knowledge derived from the previous section provides approximations good enough to solve
the so called bundle adjustment [6] which permits to stablish a relationship between images and
object by means of colinearity Equation (2) in a non-linear fashion, that is, an iterative approach of
progressively better solutions until convergence is achieved:

r11 (X − S X ) + r21 (Y − S Y ) + r31 (Z − S Z )
(x - x p ) + Δ x = − f
r13 (X − S X ) + r23 (Y − S Y ) + r33 (Z − S Z )
(2) r12 (X − S X ) + r22 (Y − S Y ) + r32 (Z − S Z )
(y - y p ) + Δ y = − f
r13 (X − S X ) + r23 (Y − S Y ) + r33 (Z − S Z )

where x and y are the image coordinates; X, Y, Z are the object coordinates; (rij, SX, SY, SZ) are the
parameters of the exterior orientation of each image; (xp, yp, f) are the geometrical parameters of the

65

<!-- p. 80 -->

Sensors 2014, 14 13764

interior orientation of the camera, that is, the image principal point coordinates and the focal length;
(ΔX, ΔY) are the corrections to be applied to the image coordinates of an observed point because of the
radial and tangential distortion of the lens according to Equation (3):

x ′ 2 4 6 2 2
′y ′ + b1 x ′ + b2 y ′ Δ x = − x p − Δ f + x ′ ( r k1 + r k 2 + r k 3 ) + ( 2 x ′ + r ) p1 + 2 p2 x
f
(3) y ′ 2 4 6 2 2 Δ y = − y p − Δf + y ′ ( r k1 + r k 2 + r k 3 ) + 2 p1 x ′y ′ + ( 2 y ′ + r ) p2 f

This is the Fraser model [20] which takes into account additional parameters to the Gaussian
distortion model [21]: besides the principal distance (f), and principal point coordinates (xp, yp), the
parameters (k1, k2, k3) are used to render the radial distortion whereas (p1, p2) address the tangential
distortion. Furthermore, it considers terms for affinity (b1) and non-orthogonality (b2).
Two important considerations must be taken into account: (a) the bundle adjustment can be carried
on with or without the knowledge of the camera. In the first case the interior and the lens distortion
parameters are entered as their known value. In the second case, they must be considered as unknowns
(self-calibration) and solved with the whole set of unknowns; (b) this is the moment in which an
absolute datum can be defined. This can be done by means of the object coordinates of ground control
points expressed in whatever geodetic system or by means of geometric restrictions that define the
seven parameters of the coordinate frame.

2.3. Modelling Procedure

Once the orientations step is completed, the whole set of images can be processed based on the
epipolarization constraints [22], that is, for a given pixel on a given image the search space of the
correspondent pixel in some other image can be computed as an (epipolar) line, thus minimizing the
search cost. Relying on this principle a Digital Surface Model (DSM) can be computed by means of
forward ray intersection [6]. To solve this process, a SGM (Semi-Global Matching) technique [7] has
been developed. The final 3D coordinates are calculated using the Equation (4):

X k = C ( D( Ri ( xik − S i ))) (4)

where the k-th unknown ground point (Xk) is related to its projection (xik) on an i-th image by means of
the extrinsic parameters of this image parameterized by the rotation matrix (Ri) and the known
projection center of the image (Si). The intrinsic parameters are the camera matrix (C) and the lens
distortion function (D).

\3. Normal vs. Non-Normal Statistics

The automation of the matching task is a process where a high number of false correspondences
occur. These errors must be filtered in successive steps to determine the orientation, but even though a
good orientation solution may be achieved, that does not imply that the subsequent Digital Surface
Model (DSM) is free from blunders since there may be correspondences that do not belong to the
object but to alien elements such as vegetation, urban artefacts, traffic, people, birds, etc.

66

<!-- p. 81 -->

Sensors 2014, 14 13765

On the other hand, when comparing the DSM obtained by means of photogrammetry to the DSM
obtained by means of laser scanning it is important to have in mind that both systems have their own
sources of error and their own sensitivity to the impact of outliers. In addition, if both systems are to be
compared, it is important to notice that the points on both DSMs are not the same and thus, a strategy
to find the best correspondences must be applied. An additional source of gross error is that the
positions of both sensors are not identical and thus, not all the object surfaces are equally captured in
the data sets.
Due to the reasons mentioned above, it should be expected that the percentage of gross errors
associated to the data sets increases and thus, the methods based on normal Gaussian statistic do not
perform well. To do so, the steps to be applied are the following: firstly, to check the normality
assumption based on statistical graphics (QQ-plots) and numerical methods (skewness and kurtosis
indices). Secondly, to test the accuracy measures of discrepancies dataset for the normal distribution
based on mean error (µ), standard deviation (σ) and their corresponding confidence intervals (CI). And
thirdly, to apply a robust model based on non-parametric estimation using sample quantiles as
reference and adding the median (m) and the biweight midvariance (BWMV) as robust measures of the
mean and standard deviation, respectively.
Therefore, we propose a break with the “deeply rooted custom” of the zero and normal distribution
of errors being considered as the appropriate standard measure of accuracy in the photogrammetric and
laser scanning studies (e.g., as adopted by the National Standard for Spatial Data Accuracy—NSSDA),
incorporating and establishing a comparison between parametric and nonparametric statistical methods.
Although the sensitivity of normality tests to non-normal data could seem an efficient alternative, it
should be remarked that these tests do not work properly with large datasets since the central limit
theorem comes into play [23], so that normality tests were only applied in those cases with a reduced
number of observations. To large datasets, a better diagnostic for checking a deviation from the normal
distribution is the visual plot quantile-quantile (QQ-plot). In this case, the quantiles of the empirical
distribution function are plotted against the theoretical quantiles of the normal distribution. If the
distribution follows a Gaussian function, the QQ-plot should be a diagonal straight line. The skewness
parameter (Equation (5)) provides an indication of departure from symmetry in a distribution
(asymmetry around the mean value), whereas kurtosis parameter (Equation (6)) is a measure of
whether the data are peaked or flat relative to a normal distribution. If the distribution is perfectly
normal, skewness and kurtosis values of zero are obtained:

n
( x i − μ) 3 
i =1 (5) Skewness =
( n − )1σ3

( xi − μ) 4 n
i =1 (6) Kurtosis = − 3
( n − )1σ4

where µ is the mean, n is the number of data points and σ is the standard deviation.
When the datasets follow a normal distribution the classical accuracy measures such as mean error
(µ) and standard deviation (σ) are considered. Likewise, confidence intervals (CI) are provided for
parameters based on the theory of errors and considering the interval (x ± 1.96σ), where x is the

67

<!-- p. 82 -->

Sensors 2014, 14 13766

parameter and σ its standard deviation for a confidence level of 95%. In those cases where some
minimum outliers could remain, the parametric approaches establish the 3σ rule to remove outliers
which can corrupt the true statistical distribution of errors. If after applying the 3σ rule error data
sets still follow a non-normal distribution, robust and non-parametric methods for the derivation of
accuracy measures should therefore be applied. For a small Gaussian sample size, the 3σ rule could be
replaced by Chauvenet’s criterion [24] that rejects those errors which have a probability of occurrence
that is less than the probability of occurrence corresponding to a proportion of 1 − 1/(4n) of the
sample, being n the sample size [25]. For those cases for which the distribution of the data is not
known, other approaches for deriving accuracy measures need to be applied. Interquartile range is an
unbiased estimator of standard deviation [26], whereas the BWMV (Equation (7)) is a robust estimator
of the statistical dispersion for heavy tailed distributions [27]:

n
2 2 4 n a i ( x i − m ) (1 − U i ) 
BWMV = i =1 2 (7) n  2 2   a i (1 − U i )(1 − 5U i ) 
 i =1 

μi − m
U i = (8)
9 MAD

where m is the median, n is the number of points, U is a parameter that comes from Equation (8), µ is
the mean and MAD is the median absolute deviation, being:

MAD = m ( xi − m x ) (9)

where m denotes de median and mx is the median of the data. Finally, the value of the parameter a
(Equation (7)) could be 0 or 1 depending on the U value. If −1 ≤ U ≤ 1, thus a is1; in any case a is 0.

\4. Methodology

Two similar sites were chosen to undertake the experiment: the portals of two Romanesque
churches—San Pedro and San Segundo—located in the city of Ávila (Spain) (see Figure 1). For these two
sites, two data sets with two different instruments, digital camera and terrestrial laser scanner (Table 1)
were acquired:

• A double data set by means of convergent photogrammetry, using two different reflex cameras
(Canon EOS 500D, Nikon D80).
• A double data set by means of two different types of terrestrial laser scanner, Faro Photon 80 and
Trimble GX (Table 1).
• In addition, when processing the photogrammetric data sets, two different tools were used, the
commercial software (CS), Agisoft Photoscan, and the PW-Photogrammetry Workbench,
the in-house software.

This gives us a total of six DSMs for each of the portals: two laser scanner data sets processed once
each, and two images data sets processed by two methods each. When comparing photogrammetry vs.
laser scanner all the photogrammetric DSMs (four per portal) were compared with all the laser

68

<!-- p. 83 -->

Sensors 2014, 14 13767

scanning DSMs (two per portal) which gives a total of eight comparisons per portal. The camera
positions are depicted in Figure 2 along with images of both portals and some examples of the points
cloud. To guarantee a common reference frame some control points were accurately observed by
means of a total station, Topcon IS Imaging Station.

Table 1. Main characteristics of the instruments that have been used.

Laser Scanner
Model Trimble GX Faro Photon 80
Principle Time of Flight-ToF Phase Shift-PS
Wavelength 534 nm (Visible - Green) 785 nm (Near Infrared)
Field of view 360 °H × 60 °V 360 °H × 320 °V
Standard deviation 1.4 mm at 50 m 2 mm at 25 m
Measurement Range 2–350 m 0.6–72 m
Spot size (beam diameter) 3 mm a 50 m 8 mm a 50 m
Scanning speed 5,000 points/sec 120,000 points/s
Reflex Cameras
Model Nikon D80 Canon 500D
Sensor type CCD (DX format) APS-C CMOS
Sensor size 23.6 × 15.8 mm 22.3 × 14.9 mm
Resolution 10.2 MP 15.1 MP
Image size 3872 × 2592 pixels 4752 × 3168 pixels
Pixel density 2.7 MP/cm2 4.5 MP/cm2
File format 12-bit compressed RAW, JPG 14-bit compressed RAW, JPG
Total Station
Model Topcon IS Imaging Station
Minimum Reading 1"/5" | (0.1/0.5 mgon)
Accuracy 1", 3" | (0.3 mgon)
Tilt Correction Dual Axis
Compensating Range ±6'
Non-Prism (range) 1.5 m 250 m
Prism (accuracy) Fine 0.2 mm/1 mm ± (2 mm+2 ppmxD*) m.s.e.

Both cameras have been chosen for their medium-range performance together with their affordable
cost. They provide a 4.7–6 μm pixel size (see Table 1) that guarantees small enough Ground Sample
Distances (GSDs): about 3 mm for a focal length of 17–18 mm and a shooting distance of about
10 m. These values, which concern the a priori accuracy as well as those that express the a posteriori
accuracy, are collected on Table 2 and further commented below this table.
The laser scanners are different in their performance: different scanning speed and different vertical
field of view (see Table 1). Both sensors are also different in their accuracy: 1.4 mm at 50 m and
2 mm at 25 m. (see Table 1). For the specific case of the two portals data acquisition, the a priori
accuracy values (as well as the a posteriori values) are collected on Table 2 and further commented
immediately below.

69

<!-- p. 84 -->

Sensors 2014, 14 13768

The total station was chosen for its performance and high accuracy. In any case, this last issue is not
very important since its role was to provide a unique coordinate frame (see Figure 2) for all the data
sets so that they could be compared to each other. In other words, it is the relative (and not the
absolute) accuracy which is relevant here.

Table 2. A priori and a posteriori accuracies. For a priori photogrammetric accuracies
the first term stands for planimetric accuracy whereas the second term stands for relief
direction accuracy.

A Priori Accuracy (mm) A Posteriori Accuracy (mm)
Canon-CS 2.8/4.8 4.4
Canon-PW 2.8/4.8 3.9
Nikon-CS 3.4/5.8 5.4
Nikon-PW 3.4/5.8 3.7
Faro 3.6 4.2
Trimble 1.7 3.5

The software to process the laser scanners point clouds was Trimble Realworks for a time of flight
laser scanner and Faro Scene for the phase-shift sensor, whereas the georeferencing of the points
clouds according to the total station coordinates was performed in Helios in-house software (own
developed software).
Finally, it should be remarked that both portals exhibit an a priori radiometric good behaviour. The
surfaces materials are wood or stone with rich density level patterns so that matching algorithms can
perform well. Figure 1 below shows examples of both set of images whereas Figure 2 shows examples
of some of the Digital Surface Models obtained.

Figure 1. (a) Portal of San Segundo; (b) Portal of San Pedro.

70

<!-- p. 85 -->

Sensors 2014, 14 13769

Figure 2. (a) Perspective view of the DSM of San Pedro obtained by PW software,
showing the local coordinate system; (b) Cenital view of the point cloud of San Pedro,
showing the photogrammetric shooting geometry; (c) Perspective view of the DSM of San
Pedro obtained by CS software; (d) Perspective view of the DSM of San Pedro obtained by
Trimble GX laser scanner; (e) Perspective view of the DSM of San Pedro obtained by Faro
Photon 80 laser scanner.

Table 2 shows values of the a priori and a posteriori accuracy of the datasets. For the a priori
photogrammetric accuracy, the Ground Sample Distance (GSD) is assumed for planimetry (XZ plane)
while GSD*D/B is assumed for the relief direction (Y axis), where D is the average distance along the
Y axis between camera stations and object and B is the maximum distance between camera stations.
For the a priori laser scanning accuracy, the Reshetyuk equation [28] is used. For the photogrammetric
case, a posterior accuracy, the sigma naught of the bundle adjustment “projected” on the object (by
means of the quotient between the GSD and the pixel size) is used. For the a posteriori laser scanning
accuracy, the root mean square error (RMSE) of geo-referencing of the point cloud with the Ground
Control Points (GCP) is used. In order to provide a good assessment of the degree of agreement
between DSM from photogrammetry and laser scanning the following procedure was assumed:

71

<!-- p. 86 -->

Sensors 2014, 14 13770

(a) To match the points of the laser scanning DSM to the points of the photogrammetric DSM
a minimum distance approach was applied.
(b) Once a pair of points was set, the difference of the three coordinate components was
evaluated. This threefold strategy is due to the fact that a 2.5D photogrammetric structure
configuration must be assumed rather than a 3D one and a different behaviour for the
fundamental plane XZ and for the relief direction (Y) must be expected. X is the width
dimension of the portal, Z is the height of the portal; Y is the depth of the portal.

\5. Experimental Results

As a previous step and in order to assess the agreement between photogrammetric results and laser
scanner results, the non-parametric correlation coefficients were computed, by means of Spearman’s
correlation coefficient. On Table 3 the results for the Spearman coefficient between data sets for the
three coordinates are collected. From them we can see a very high and consistent agreement regarding
the X and Z coordinates (higher for the Z case) and a not so high and not so consistent agreement for
the Y coordinate. These results confirm that photogrammetric and laser scanning derived point clouds
are very largely equivalent for the planimetric dimensions (XZ), but that along depth dimension (Y) the
agreement should be addressed much more carefully.

Table 3. Spearman’s correlation between laser scanning and photogrammetric sensors.

Case Laser Camera Software X Y Z
PW 0.9992 0.9868 0.9997
Canon
CS 0.9998 0.6751 0.9994
Faro
PW 0.9998 0.9965 0.9971
Nikon
CS 0.9999 0.9948 0.9999
San Pedro
PW 0.8731 0.6084 0.9328
Canon
CS 0.7981 0.4232 0.9991
Trimble
PW 0.9998 0.9977 0.9996
Nikon
CS 0.9997 0.9849 0.9997
PW 0.9702 0.9520 0.9992
Canon
CS 0.9998 0.6219 0.9994
Faro
PW 0.9999 0.9993 0.9995
Nikon
CS 0.9957 0.8806 0.9987
San Segundo
PW 0.9999 0.9950 0.9998
Canon
CS 0.9996 0.9178 0.9992
Trimble
PW 0.9998 0.9857 0.9992
Nikon
CS 0.9985 0.8766 0.9985

After this, and in order to assess how well the Gaussian and non-Gaussian parameters, discussed on
Section 4, describe the differences between pairs of data sets, for both portals, the items that appear on
Table 4 (first column) were computed for the three coordinate components (X,Y,Z) for each of the
comparisons resulting from the laser scanners (Faro Photon 80, Trimble GX) against the
photogrammetric approaches (PW, CS) using digital cameras (Canon 500D, Nikon D80). This means
that, as described on the previous section, for each pair of data sets (one from scanner laser and the

72

<!-- p. 87 -->

Sensors 2014, 14 13771

other from photogrammetry) and for each of the three coordinates, a new data set was computed
consisting of the difference between matching points from both original data sets. Once obtained this
“discrepancy set” the items of the first column were computed by means of statistical tools of Matlab
software as well as own implemented statistical software (STAR). Certainly, not all these parameters
have the same significance but they are shown here for illustration purposes. Table 4 is an example
showing the results obtained for the Z component.

Table 4. Statistical values calculated for the Z discrepancies in the case of the portal of San
Pedro. SEM stands for Standard Error of the Mean. LCI-UCI, for Lower-Upper Confidence
Interval. MAD stands for Median Absolute Deviation. BWMV, for Biweight Midvariance.
±2.326*σ, for the range of values of the frequencies Gaussian distribution curve that leaves
outside 2% of the sample (see text below for an explanation) LB-UP, for Lower-Upper
percentage of Blunders (see below for an explanation). All values except Kurtosis and
Skewness (adimensional) and percentages are in meters.

FARO TRIMBLE
Canon Nikon Canon Nikon

PW CS PW CS PW CS PW CS
Sample size (n) 125,379 164,950 138,089 156,154 93,028 128,412 105,628 118,837
Min (m) −0.1124 −0.1494 −0.0786 −0.0984 −0.1085 −0.1362 −0.1041 −0.1132
Max (m) 0.1742 0.1474 0.0713 0.1294 0.2004 0.1660 0.1104 0.1132
Sample mean (m) 0.0010 0.0011 0.0007 0.0012 0.0007 0.0009 0.0007 0.0009
Standard deviation (m) 0.0084 0.0088 0.0038 0.0045 0.0093 0.0090 0.0056 0.0049
Median (m) 0.0003 0.0006 0.0003 0.0006 0.0001 0.0005 0.0003 0.0005
Quantile 25 (m) −0.0011 −0.0013 −0.0009 −0.0013 −0.0015 −0.0013 −0.0010 −0.0015
Quantile 75 (m) 0.0019 0.0027 0.0016 0.0027 0.0017 0.0024 0.0016 0.0025
SEM (m) 0.0000 0.0000 0.0000 0.0000 0.0000 0.0000 0.0000 0.0000
LCI of the mean (m) 0.0010 0.0010 0.0007 0.0012 0.0007 0.0008 0.0006 0.0008
UCI of the mean (m) 0.0011 0.0011 0.0007 0.0012 0.0008 0.0009 0.0007 0.0009
LCI of the SD (m) 0.0084 0.0088 0.0038 0.0045 0.0093 0.0089 0.0056 0.0049
UCI of the SD (m) 0.0084 0.0089 0.0038 0.0045 0.0094 0.0090 0.0056 0.0049
MAD (m) 0.0015 0.0020 0.0012 0.0020 0.0016 0.0019 0.0013 0.0020
SQRT(BWMV) (m) 0.0026 0.0035 0.0021 0.0033 0.0028 0.0031 0.0023 0.0031
Percentile 0.1 (m) −0.0029 −0.0034 −0.0020 −0.0028 −0.0037 −0.0031 −0.0025 −0.0030
Percentile 0.9 (m) 0.0048 0.0075 0.0038 0.0060 0.0045 0.0059 0.0042 0.0049
Kurtosis (adim.) 93.59 29.07 37.11 33.75 104.11 39.79 74.62 60.53
Skewness (adim.) 6.11 −0.02 0.94 1.64 6.89 0.48 2.97 2.72
Percentile 0.01(m) −0.0159 −0.0272 −0.0073 −0.0073 −0.0168 −0.0274 −0.0120 −0.0092
Percentile 0.99 (m) 0.0288 0.0311 0.0140 0.0162 0.0302 0.0327 0.0175 0.0168
±2.326*σ (m) ±0.0196 ±0.0205 ±0.0087 ±0.0105 ±0.0217 ±0.0209 ±0.0130 ±0.0114
LB (−2.326*σ) (%) 0.72% 1.66% 0.71% 0.43% 0.65% 1.54% 0.88% 0.65%
UB (+2.326*σ) (%) 1.78% 2.32% 2.78% 3.93% 1.45% 2.11% 1.84% 2.41%

73

<!-- p. 88 -->

Sensors 2014, 14 13772

The last five rows of Table 4 show the behaviour of gross errors according to the following criteria:
Percentile 0.01 and Percentile 0.99 collect the observed values that correspond to such percentiles
whereas ±2.326*σ, shows the value of observations that lie outside the range of a standard deviation of
±2.326. This threshold is chosen to agree with the percentile 0.01–0.99 criteria, that is, that includes
98% of the sample (or leaves out 2% of the sample). The two last rows show the percentage of
observations whose value is smaller than −2.326*σ or larger than +2.326*σ, respectively (according to
strict Gaussian theory it should always be 1%).
Besides this, the QQ-plots of all of the 48 comparisons were obtained. Figure 3 shows two
examples. From the visualization of every one of these plots it could be concluded that there is a large
departure from the normal distribution of all the samples due to the presence of gross errors.

Figure 3. Examples of QQ-plots.

In order to assess and discuss the results, the following Tables 5 and 6 show a synthesis of all the
comparisons for each of the portals. Each cell gives the average and the [minimum ; maximum]
interval are presented for the following parameters: Mean (mm), Standard Deviation (mm), Median
(mm), Interquartile (Q25–Q75) (mm), Median Absolute Deviation (MAD) (mm), Biweight
Midvariance (BWMV) (mm), Kurtosis (adimensional), Skewness (adimensional) and percentage of
left (lower) and right (upper) blunders (values larger than ±2.326). From these tables it is possible to
highlight the following issues:
The sample mean should show that a certain disagreement is presented between the data sets. For
the X coordinate in San Segundo, the values are slightly smaller than 1 mm and for the Z, the values
are even smaller. All the results are very consistent, with small deviations within them and always with
the same sign for X and Z. In the case of San Pedro a systematic effect occurs between data sets that
involve Faro or Trimble laser scanner (Table 7). The total displacement between both lasers samples is
around 2 mm, affects the width dimension (X) and does not appear on the height dimension (Z). This
question also appears when looking at the median values (see infra) and could be due to an X shift
when referencing both laser data sets at San Pedro.

74

<!-- p. 89 -->

Sensors 2014, 14 13773

Table 5. Synthesis of parametric and non-parametric statistical results for the portal of San
Segundo. All magnitudes, except Kurtosis and Skewness (adimensional) and percentages,
are in millimetres. LB-UB stand for Lower-Upper Blunders (see text for explanation).

X Y Z
Sample mean −1.0 ∈ [−1.6; −0.4] 2.8 ∈ [−2.0; 7.8] 0.1 ∈ [0.0; 0.5]
Standard deviation 5.4 ∈ [3.6; 7.7] 9.2 ∈ [4.8; 19.3] 4.5 ∈ [2.6; 6.9]
Median −0.3 ∈ [−0.5; −0.1] 2.4 ∈ [−1.6; 7.7] 0.1 ∈ [0.0; 0.2]
Quantile 25 −1.8 ∈ [−2.6; −1.2] −0.7 ∈ [−4.3; 3.5] −1.3 ∈ [−1.8; −1.1]
Quantile 75 1.2 ∈ [0.9; 1.6] 5.9 ∈ [0.6; 12.2] 1.5 ∈ [1.0; 2.0]
MAD 1.5 ∈ [1.1; 2.0] 3.3 ∈ [2.2; 4.6] 1.4 ∈ [1.0; 1.9]
√BWMV 2.4 ∈ [1.8; 3.2] 5.0 ∈ [3.4; 6.7] 2.3 ∈ [1.8; 3.0]
Kurtosis 61.68 ∈ [18.72; 149.71] 129.48∈ [26.47; 496.93] 125.84∈ [28.22; 311.97]
LB 0.28% ∈ [0.05; 0.50] 2.36% ∈ [0.14; 4.08] 1.59% ∈ [0.97; 2.28]
UB 2.96% ∈ [1.52; 5.14] 0.73% ∈ [0.11; 1.87] 1.32% ∈ [0.83; 1.59]

Table 6. Synthesis of parametric and non-parametric statistical results for the portal of San
Pedro. All magnitudes, except Kurtosis and Skewness (adimensional) and percentages, are
in millimeters. LB-UB stand for Lower-Upper Blunders (see text for explanation).

X Y Z
Sample mean 0.0 ∈ [−2.0; 2.0] −0.1 ∈ [−1.4; 1.6] 0.9 ∈ [0.7; 1.2]
Standard deviation 11.2 ∈ [5.4; 25.7] 11.9 ∈ [7.0; 24.1] 6.8 ∈ [3.8; 9.3]
Median 0.2 ∈ [−1.0; 2.7] −0.2 ∈ [−1.5; 2.7] 0.4 ∈ [0.1; 0.6]
Quantile 25 −2.0 ∈ [−3.4; −1.0] −3.4 ∈ [−5.9; −1.6] −1.2 ∈ [−1.5; −0.9]
Quantile 75 2.2 ∈ [1.0; 6.8] 2.8 ∈ [1.7; 7.6] 2.1 ∈ [1.6; 2.7]
MAD 2.1 ∈ [1.3; 4.4] 3.1 ∈ [1.8; 4.9] 1.7 ∈ [1.2; 2.0]
√BWMV 3.7 ∈ [2.4; 8.4] 5.2 ∈ [2.9; 8.1] 2.8 ∈ [2.1; 3.5]
Kurtosis 41.41 ∈ [21.39; 61.42] 101.66 ∈ [18.21; 341.64] 59.07 ∈ [29.07; 104.11]
LB 1.56 ∈ [0.21; 2.74] 1.27 ∈ [0.78; 1.91] 2.33 ∈ [1.45; 3.93]
UB 1.81 ∈ [0.28; 4.86] 1.49 ∈ [0.30; 2.98] 0.91 ∈ [0.43; 1.66]

Table 7. Systematic effect that appears between both laser data sets concerning the width
dimension (X) in San Pedro. The systematic trend involves the mean and the median.
Values in millimetres.

FARO TRIMBLE
Canon Nikon Canon Nikon
PW CS PW CS PW CS PW CS
Sample mean −1.3 −1.3 −1.0 −2.0 1.3 2.0 1.5 0.6
Median −0.1 −0.4 −0.2 −1.0 0.2 2.7 0.4 0.0

Regarding the depth dimension (Y coordinate) in the case of San Pedro it can be appreciated that the
values are very similar to the planimetric dimensions values, but that the range variation of these
values is slightly higher (and, thus, worse) than the planimetric ones. In the case of San Segundo, there
appears a difference between 1 and 2 mm between photogrammetry and laser scanner for five of the
cases and of 5, 6 and 7 mm for the other three cases which always involve the Trimble laser scanner.

75

<!-- p. 90 -->

Sensors 2014, 14 13774

Consequently, although there seems to be a discrepancy between photogrammetry and laser scanner
this is too small to declare as significant. In any case, if some systematic trend is appearing it affects
the comparative performance between the scanners rather than between the laser scanning and the
photogrammetric ones (see Table 7).
Regarding the values of the median, it must be said, first of all, that they always confirm the
behaviour that has been stated above concerning the values of mean. The values of the median are
sometimes smaller than the values of the mean, sometimes equivalent and sometimes larger but the
differences are always very small and always affect the three coordinate components X, Y and Z in a
very consistent way.
In addition, under the assumption that the sample median is a more robust estimator than the mean
is, the values of this parameter should show a significant disagreement between the data sets but this
disagreement is not apparent from the values that have been obtained: the median shows consistently
the same small discrepancies that the mean does. Thus, it can be concluded that the existence of
blunders or observations that do not conform to the Normal Distribution does not have an influence on
the disagreement between data sets. But, as has been said before, the discrepancies are too small to be
regarded as significant.
Concerning the values of the standard deviation, it can be seen that for X and Z, in the case of San
Segundo, consistent values around 5 mm are obtained and not as much consistent values around 8 mm
are obtained for Y. This confirms what is predicted by theory: the precision along the depth direction
(Y) is worse than for the planimetric coordinates (X, Z). For these cases (San Segundo), the maximum
values (up to 17 mm along Y direction) are obtained when using the Nikon camera and the commercial
photogrammetric software (CS).
In San Pedro, the standard deviation results are worse than for San Segundo, concerning the X and
Z coordinates: around 11 mm for the former and around 7 mm for the latter. Also, the consistency is
not as high as in the San Segundo case: for both dimensions, the results for the Canon camera are twice
as worse than for the Nikon camera. The Y results are also worse than the results of San Segundo,
about 11 mm, and also show the same differential performance between both cameras.
In any case, the values of the standard deviation are always worse than the a priori values that
should be expected from theory. They also show that the Y dimension accuracy is worse than the X-Z
dimensions accuracy at should be expected. This fact is not as clear for San Pedro as it is for San Segundo.
When analysing the percentage of blunders, the first result that must be remarked is that this
percentage is 1.6% on average, that is, slightly above what should be expected (1%) and this is not an
excessive number of outliers, but much more relevant than this raw and small number is the large
variety of results that can be found: from sets that only show 0.05% of blunders to sets where the
number of gross errors is 5.4%. Furthermore: there is almost always a significant lack of symmetry
between the number of gross errors at the left (lower) and at the right (upper) on the distribution of the
frequencies curve. So, what should be highlighted is that it is not a matter of a high number of blunders
but of an asymmetric distribution of them.
Confirming what has just been said, all the values that are obtained for the interquantiles as well as
for the skewness, show that the data sets do not conform to the symmetry of the Normal curve. It
should be remembered that this result is also apparent from the QQ-plots. It should be added that the
values of the quantiles (Q25 and Q75) and the median are always consistent with the values of the

76

<!-- p. 91 -->

Sensors 2014, 14 13775

skewness showing a lack of symmetry to the left or to the right. The consistency is also high for all the
comparisons within the same dimension, X, Y or Z.
Finally, when examining the values of the Median Absolute Deviation (MAD) and the Biweight
Midvariance (BWMV), very consistent results are achieved for X and Z, slightly better for Z than for
X. This behaviour (Z better than X) can be due to the fact that both portals are less complex (in their
shapes) along height (Z) direction than along width (X) direction. It must also be noted that the X-Z
values are significantly better in the case of San Segundo than in the case of San Pedro. This could be
related to the same explanation: San Pedro surfaces are more articulated than San Segundo surfaces. In
any case, the values of the Biweight Midvariance for X and Z lie between 2 and 4 mm and these values
certainly meet the a priori expectations. It should be remembered that, on the contrary, the standard
deviation values do not meet what the theory predicts.
The MAD and BWMV results for the depth dimension (Y coordinate) are also very consistent within
them. They are also very similar between the two portals. These values also meet the a priori
expectations and, therefore, also show the relation with the planimetric accuracy values that theory
states. In addition, this relation between the accuracy of X-Z dimensions and Y dimension, expressed
through MAD and BWMV, is much clear than when it is expressed through the standard deviation.

\6. Conclusions

The DSMs obtained from photogrammetry are largely equivalent to the DSMs obtained from the
laser scanner. Some very small inconsistencies have arisen, but these affect the comparative performance
of the laser scanners or the comparative performance of the cameras rather than the comparative
performance of photogrammetry and laser scanning.
All sets show a large lack of symmetry that leads to the conclusion that the standard Normal
parameters are not adequate to assess this type of data. The Normal distribution fails to appropriately
describe the data for the cases that have been examined. In particular, this is especially the case when
assessing accuracy through the standard deviation, since this parameter fails to provide a good
estimation of the results.
Use of non-Normal statistics gives a more appropriate description of the data and yields results that
meet what may be expected concerning the assessment of accuracy. The results obtained for the
Median Absolute Deviation and for the Biweigth Midvariance agree with the values predicted by
the theory.
This can be extended to what usually happens in photogrammetry in a 2.5D case. The planimetric
dimensions show better results than the relief (depth) dimension according roughly to the factor D/B
(distance to the object-camera base quotient). Some results appear to agree with the shape itself of the
objects but these values are not apparent enough to consider them a straightforward conclusion.
Regarding future work and in order to extend the validity of these results in the wider field of
imaging, this type of experiment could be applied to other cases in which some other shapes, depth
variations, images settings or some other network designs (to include real 3D cases) should be
analysed. Also, other materials (metal or uniformly painted walls) that should not be as favourable as
the ones tested here (wood and stone) must be considered. Of course, more hardware and software
should be tested to extend the validity of the conclusions presented here.

77

<!-- p. 92 -->

Sensors 2014, 14 13776

Author Contributions

All authors contributed extensively to the work presented in this paper.

Conflicts of Interest

The authors declare no conflict of interest.

References

\1. Haala, N.; Peter, M.; Kremer, J.; Hunter, G. Mobile LiDAR mapping for 3D point cloud
collection in urban areas—A performance test. Int. Arch. Photogramm. Remote Sens Spatial Inf.
Sci. 2008, 37, 1119–1127.
\2. Schindler, K. An overview and comparison of smooth labeling methods for land-cover
classification. IEEE Trans. Geosci. Remote Sens. 2012, 50, 4534–4545.
\3. Kraus, K. Photogrammetry. Fundamentals and Standard Processes; Dummlers Verlag: Bonn,
Germany, 1993; Volume 1, p. 397.
\4. Robertson, D.P.; Cipolla, R. Structure from Motion. Practical Image Processing and Computer
Vision; John Wiley: Hoboken, NJ, USA, 2009; Volume 49.
\5. Hartley, R.; Zisserman, A. Multiple View Geometry in Computer Vision; Cambridge University
Press: Cambridge, UK, 2003; p. 655.
\6. Kraus, K. Photogrammetry: Advanced Methods and Applications; Dümmler: Bonn, Germany,
1997; Volume 2, p. 466.
\7. Hirschmuller, H. Stereo processing by semiglobal matching and mutual information. IEEE Trans.
Pattern Anal. Mach. Intell. 2008, 30, 328–341.
\8. Deseilligny, M.P.; Clery, I. Apero, an open source bundle adjusment software for automatic
calibration and orientation of set of images. In Proceedings of the ISPRS Commission V
Symposium, Image Engineering and Vision Metrology, Trento, Italy, 2–4 March 2011;
Volume XXXVIII-5/W16, pp. 269–276.
\9. Habbecke, M.; Kobbelt, L. Iterative Multi-View Plane Fitting. In Proceedings of the 11th
International Fall Work-Shop Vision, Modeling, and Visualization; Akademische Verlagsgesellschaft
Aka GmbH: Aachen, Germany, 2006; pp. 73–80.
\10. Lhuillier, M.; Quan, L. A quasi-dense approach to surface reconstruction from uncalibrated
images. IEEE Trans. Pattern Anal. Mach. Intell. 2005, 27, 418–433.
\11. Seitz, S.M.; Curless, B.; Diebel, J.; Scharstein, D.; Szeliski, R. A comparison and evaluation of
multi-view stereo reconstruction algorithms. In Proceedings of the 2006 IEEE Computer Society
Conference on Computer Vision and Pattern Recognition (CVPR’06), Washington, DC, USA,
17–22 June 2006; Volume 1, pp. 519–528.
\12. Joglekar, J.; Gedam, S.S. Area based image matching methods—A survey. Int. J. Emerg. Technol.
Adv. Eng. 2012, 2, 130–136.
\13. Smith, S.M.; Brady, J.M. SUSAN—A new approach to low level image processing. Int. J.
Comput. Vision 1997, 23, 45–78.

78

<!-- p. 93 -->

Sensors 2014, 14 13777

\14. Lowe, D.G. Object recognition from local scale-invariant features. In Proceedings of the Seventh
IEEE International Conference on Computer Vision, Kerkyra, Greece, 20–27 September 1999;
Volume 2, pp. 1150–1157.
\15. Matas, J.; Chum, O.; Urban, M.; Pajdla, T. Robust wide baseline stereo from maximally
stable extremal regions. In Procceding of the British Machine Vision Conference, Cardiff, UK,
2–5 September 2002; pp. 384–393.
\16. Bay, H.; Ess, A.; Tuytelaars, T.; van Gool, L. Speeded-up robust features (SURF). Comput.
Vision Image Underst. 2008, 110, 346–359.
\17. Morel, J.-M.; Yu, G. ASIFT: A new framework for fully affine invariant image comparison.
SIAM J. Imaging Sci. 2009, 2, 438–469.
\18. Longuet-Higgins, H.C. A computer algorithm for reconstructing a scene from two projections.
Nature 1981, 293, 133–135.
\19. Horn, B.K.P. Recovering baseline and orientation from essential matrix. J. Opt. Soc. Am. 1990,
1–10.
\20. Fraser, C.S.; Shortis, M.R.; Ganci, G. Multisensor System Self-Calibration. In Proceedings of
Videometrics IV, 13 September 1995; pp. 2–18.
\21. Brown, D. Close-range camera calibration. Photogramm. Eng. 1971, 37, 855–866.
\22. Luhmann, T.; Robson, S.; Kyle, S.; Harley, I. Close Range Photogrammetry: Principles, Methods
and Applications; Whittles: Dunbeath, UK, 2007; p. 528.
\23. Chang, H.-J.; Huang, K.-C.; Wu, C.-H. Determination of sample size in using central limit
theorem for weibull distribution. Int. J. Inf. Manag. Sci. 2006, 17, 31–46.
\24. Chauvenet, W. A Manual of Spherical and Practical Astronomy, 5th ed.; JB Lippincott & Co.:
Philadelphia, PA, USA, 1863; Volume 1.
\25. Blessing, R.H. Outlier treatment in data merging. J. Appl. Cryst. 1997, 30, 421–426.
\26. Mood, A.M.; Graybill, F.A.; Boes, D.C. Introduction to the Theory of Statistics, 3rd ed.;
McGraw-Hill: New York, NY, USA, 1974.
\27. Lax, D.A. Robust Estimators of Scale: Finite-Sample Performance in Long-Tailed Symmetric
Distributions. J. Am. Stat. Assoc. 1985, 80, 736–741.
\28. Reshetyuk, Y. Self-Calibration and Direct Georeferencing in Terrestrial Laser Scanning. Ph.D
Thesis; KTH Royal institute of Technology: Stockholm, Sweden, 2009.

© 2014 by the authors; licensee MDPI, Basel, Switzerland. This article is an open access article
distributed under the terms and conditions of the Creative Commons Attribution license
(http://creativecommons.org/licenses/by/3.0/).

79

<!-- p. 94 -->



<!-- p. 95 -->

Documentación y análisis geométrico del patrimonio arquitectónico a partir de métodos
fotogramétricos con una y múltiples imágenes

\5. CONCLUSIONES

En esta Tesis Doctoral se han propuesto, desarrollado y probado diferentes
metodologías para la documentación geométrica del patrimonio arquitectónico y su
análisis dimensional mediante métodos de bajo coste basados en la fotogrametría
de una y múltiples imágenes. Estos métodos resultan sencillos, rápidos en su
aplicación, acortan los tiempos de trabajo de campo sin pérdida de calidad respecto
a otros sistemas y son accesibles para la mayoría de los técnicos intervinientes en la
conservación del patrimonio arquitectónico, implicándolos de una forma más activa
en el proceso del levantamiento arquitectónico.

A continuación se pasan a reseñar las conclusiones más relevantes asociadas a
cada una de las tres líneas de trabajo desarrolladas:

• En primer lugar, se ha planteado en esta Tesis Doctoral un método de trabajo
para realizar el análisis dimensional y la reconstrucción parcial 3D de un edificio
histórico desaparecido, del que sólo existen imágenes individuales, utilizando para
ello los principios geométricos de la fotogrametría oblicua. El caso de estudio ha sido
la desaparecida “Torre de la Gobierna”, una de las dos torres que caracterizaban la
imagen del medieval puente de piedra sobre el Duero, en Zamora, que fue demolida
tras la reforma de 1905. El método desarrollado ha permitido la obtención de
medidas a partir de una sola fotografía antigua para afrontar posteriormente la
reconstrucción parcial, métrica y gráfica, de la Torre.
El método propuesto para el análisis dimensional y reconstrucción parcial 3D de
un edificio desaparecido a partir de una única fotografía antigua está basado en el
software sv3DVision (Gonzalez-Aguilera y Gomez-Lahoz, 2008), desarrollado en el
año 2005 en la Universidad de Salamanca. Este software permite llevar a cabo los
procesos de extracción de líneas y puntos de fuga, los procesos de orientación
(interna y externa) de la imagen, así como los procesos de análisis dimensional y
reconstrucción parcial del objeto.
En el caso de la Torre de Gobierna la primera fase del proceso, consistente en la
extracción y clasificación de las líneas de fuga, se ha realizado de forma asistida por

81

<!-- p. 96 -->

Documentación y análisis geométrico del patrimonio arquitectónico a partir de métodos
fotogramétricos con una y múltiples imágenes

el usuario, debido a que la imagen antigua presenta unas pésimas condiciones de
color y además la perspectiva en la dirección vertical (punto de fuga cercano al
infinito) es muy pobre. En cambio, la segunda fase del proceso, consistente en el
cálculo de los 3 puntos de fuga asociados a las direcciones X,Y,Z, se ha aplicado con
éxito de forma automática mediante un método específico basado en la
Transformada de Hough, garantizando eficiencia y calidad en los resultados, incluso
en la reseñada dirección vertical donde la intersección de las líneas de fuga
representa un caso desfavorable.
En la última fase, como resultado del análisis dimensional, se ha obtenido un error
relativo del 1% en la evaluación de la exactitud de los resultados. Este valor puede
ser considerado suficientemente satisfactorio ya que el método de modelado basado
en una imagen implica la concatenación de muchos pasos y por lo tanto la
correspondiente propagación de errores.
No obstante, conviene reseñar que el método sólo es aplicable en escenas
arquitectónicas regulares con fuerte contenido geométrico (es decir, la presencia de
planos estructurales y aristas) y donde son aplicables restricciones geométricas en
forma de planeidad, ortogonalidad y paralelismo entre sus formas. Además, la
imagen debe tener perspectiva a lo largo de las tres direcciones principales (X, Y, Z)
con el fin de calcular los tres puntos de fuga correspondientes (VPX, VPy, VPZ).
Obviamente, si estos puntos de fuga están bien definidos, se puede conseguir mayor
automatismo, precisión y fiabilidad en el modelado basado en una única imagen.

• Por otro lado, se ha demostrado en esta Tesis Doctoral la capacidad de los
programas fotogramétricos basados en múltiples imágenes que se orientan hacia la
automatización total del proceso a la hora de obtener modelos cartográficos válidos
para la interpretación arquitectónica de edificios religiosos. Con una metodología de
trabajo que resulta ser, tanto en la fase de toma como en la fase de procesamiento,
relativamente sencilla pueden obtenerse resultados de alta calidad métrica y gráfica.
El enfoque desarrollado mejora las técnicas actuales para el registro del
patrimonio cultural arquitectónico, siendo adecuado para llevar a cabo un estudio
de clasificación tipológica, donde la reducción de los tiempos de captura de imágenes
permite al investigador documentar un gran número de edificios en poco tiempo y

82

<!-- p. 97 -->

Documentación y análisis geométrico del patrimonio arquitectónico a partir de métodos
fotogramétricos con una y múltiples imágenes

por personal no especializado, debido a la simplicidad del proceso. Además, dada la
alta resolución de los modelos obtenidos, el método podría ser utilizado en proyectos
que requieran escalas superiores: (1/100 – 1/50).
Algunas de las ventajas del método propuesto son: reducción de los tiempos de
trabajo de campo sin pérdida de precisión, facilidad para sistematizar el proceso de
toma siguiendo un sencillo protocolo y facilidad y rapidez en su aplicación,
acometiendo levantamientos de edificios y fachadas de calidad, en los que junto a la
geometría se obtiene información de la textura del edificio.
La calidad gráfica de los modelos generados se basa en buena medida en la
cantidad de puntos calculados: entre 20 y 50 millones de puntos, lo que sitúa a la
metodología fotogramétrica en niveles de resolución similares o incluso superiores a
los obtenidos mediante los sistemas láser escáner terrestre. Los tiempos de captura
de imagen son más bajos que los requeridos por los sistemas láser, mientras que los
tiempos de trabajo de laboratorio son similares. Sin embargo, cuando se trabaja con
el láser escáner, la disponibilidad de dispositivos y la dificultad de proceso son peores
que el instrumental y el software necesarios con la fotogrametría.
Las precisiones obtenidas (error medio cuadrático del ajuste del bloque) son
satisfactorias (se obtienen resultados que se sitúan entre 1/4 y 1/3 de píxel), lo que
se debe, en gran medida, al alto nivel de redundancias que permiten ajustar la red
de toma fotográfica de forma precisa y robusta. Este elevado número de
redundancias es, a su vez, debido al elevado número de imágenes capturadas.
Aunque pudiera parecer un número de imágenes excesivo, debe tenerse en cuenta
que los tiempos invertidos son completamente asumibles, entre 30 y 60 minutos de
trabajo de campo y de 6 a 16 horas de trabajo en el laboratorio.
Los resultados son altamente coherentes entre sí lo que refrenda la calidad y
fiabilidad de la metodología empleada.
Las diferencias que se aprecian en los números de imágenes obtenidas se deben
principalmente a las características del entorno donde se sitúa el edificio religioso y
la posibilidad o no de alejarnos lo suficiente para encuadrar todo el objeto en la
imagen, así como a las dimensiones del edificio, no traduciéndose en diferencias
significativas ni en los tiempos invertidos ni las precisiones alcanzadas.

83

<!-- p. 98 -->

Documentación y análisis geométrico del patrimonio arquitectónico a partir de métodos
fotogramétricos con una y múltiples imágenes

• Finalmente y como cierre de esta Tesis Doctoral, se ha propuesto un método
para realizar un diagnóstico de la calidad (accuracy assessment) de los modelos
fotogramétricos comparando modelos densos 3D generados mediante
fotogrametría de múltiples imágenes (con distintas cámaras y con distinto software)
con modelos densos 3D obtenidos mediante dos sistemas de láser escáner, de
tiempo de vuelo y de diferencia de fase. Para diagnosticar dicha calidad, se han
utilizado métodos estadísticos clásicos Gaussianos y robustos no paramétricos,
arrojando unos resultados que verifican que dichos modelos son equivalentes en
gran medida.
Bajo el supuesto de que la mediana de la muestra es un estimador más robusto
que la media, los valores de este parámetro deberían mostrar discrepancias
importantes entre los conjuntos de datos, pero esto no se observa con los valores
obtenidos: la mediana presenta consistentemente las mismas discrepancias que la
media. Por lo tanto, la existencia de errores u observaciones que no se ajustan a la
distribución normal, no tienen una influencia en las discrepancias entre los conjuntos
de datos.
En los dos casos analizados, los valores de la desviación estándar son siempre
peores que los valores a priori esperados por la teoría. También se observa que la
precisión en la dimensión Y (profundidad) es peor que en las dimensiones
planimétricas (X y Z).
Habría que destacar que no se trata de un alto número de errores, sino de una
distribución asimétrica de los mismos. Los conjuntos de datos no se ajustan a la
simetría de la curva normal.
Al observar los valores de la Desviación Media Absoluta y la Bivarianza Ponderada
se obtienen resultados muy consistentes para X y Z, y también para la dimensión de
profundidad, Y. Estos resultados también cumplen las expectativas marcadas a priori
y muestran la relación con los valores de la precisión planimétrica de la teoría. Esta
relación entre la exactitud de las dimensiones X y Z y la dimensión Y, expresada
mediante la Desviación de la Media Absoluta y la Bivarianza Ponderada es mucho
más clara que cuando se expresa a través de la desviación estándar.
Todos los conjuntos de datos estudiados muestran una gran falta de simetría,
debido a la presencia de errores groseros, lo que lleva a la conclusión de que los

84

<!-- p. 99 -->

Documentación y análisis geométrico del patrimonio arquitectónico a partir de métodos
fotogramétricos con una y múltiples imágenes

parámetros normales estándar no son adecuados para evaluar este tipo de datos.
Más concretamente, se concluye que la estadística Normal Gaussiana no puede
llegar a los valores adecuados para los casos que se han examinado, en especial
cuando analizamos la desviación estándar resultante de la comparación entre
modelos, la cual no proporciona una buena estimación de los resultados.
En cambio, la estadística basada en métodos no paramétricos, rinde mejor y arroja
resultados que cumplen con lo que cabría esperar en relación con la evaluación de la
exactitud. Los resultados obtenidos por los parámetros de la Desviación de la Media
Absoluta y para la Bivarianza Ponderada están de acuerdo con los valores predichos
por la teoría.

85

<!-- p. 100 -->



<!-- p. 101 -->

Documentación y análisis geométrico del patrimonio arquitectónico a partir de métodos
fotogramétricos con una y múltiples imágenes

ANEXO - FACTOR DE IMPACTO DE LAS PUBLICACIONES

I

<!-- p. 102 -->



<!-- p. 103 -->

Documentación y análisis geométrico del patrimonio arquitectónico a partir de métodos
fotogramétricos con una y múltiples imágenes

ARTÍCULO 1: HISTORICAL SINGLE IMAGE-BASED MODELING: THE CASE OF
GOBIERNA TOWER, ZAMORA (SPAIN)

ARTÍCULO 2: A PHOTOGRAMMETRIC AND COMPUTER VISION-BASED
APPROACH FOR AUTOMATED 3D ARCHITECTURAL MODELING AND ITS
TYPOLOGICAL ANALYSIS

Descripción de factor de impacto y documentación de la revista.

Nombre de la revista: REMOTE SENSING
www.mdpi.com/journal/remotesensing
Editorial: MDPI
ISSN: 2072-4292
Factor de impacto (2013): 2.623
Ranking de la revista: 6/27
Cuartil: Q1

II

<!-- p. 104 -->



<!-- p. 105 -->

IS| Web of Knowledge™

Journal Citation Reports®

5 obs, RETURN 70 |
fe WELCOME | ? Hew?| | fmt 2013 JCR Science Edition

© Journal: Remote Sensing

5-Year Cited Citing

Impact Impact Immediacy Citable Half- Half-

Mark Journal Title ISSN Total Cites Factor Factor Index Items life _ life
C] REMOTE SENS-BASEL 2072-4292 1739 2.623 2.729 0.883 316 2.4 7.5

Cited Journal [JQ Citing Journal [JJ Source Data Journal Self Cites

\| qTepsournaLoata | | cIINGJoURNALDATA | — [jj IMPACTFACTORTREND | | RELATED JOURNALS
Journal Information U a
Full Journal Title: Remote Sensing Eigenfactor® Metrics
ISO Abbrev. Title: Remote Sens. Eigenfactor® Score
JCR Abbrev. Title: REMOTE SENS-BASEL 3 oosse
ISSN: 2072-4292 ~~ ®
Issues/Year: 12 article Influence
Language: ENGLISH ea
Journal Country/Territory: SWITZERLAND "
Publisher: MDPI AG
Publisher Address: POSTFACH, CH-4005 BASEL, SWITZERLAND
Subject Categories: REMOTE SENSING
\| C\ view JOURNAL suMMaRy List | |G) VIEW CATEGORY DATA. |
Journal Rank in Categories:
Journal Impact Factor i) =

Cites in 2013 to items published in: 2012 =421 Number of items published in: 2012 =184

2011 =421 2011 =137
Sum: 842 Sum: 321
Calculation:Cites to recent items 842 =2.623
Number of recent items 321
5-Year Journal Impact Factor =

Cites in {2013} to items published in: 2012 =421 Number of items published in: 2012 =184

2011 =421 2011 =137
2010 =423 2010 =141
2009 =195 2009 =73
2008 =0 2008 =0
Sum: 1460 Sum: 535
Calculation:Cites to recent items 1460 =2.729
Number of recent items 535
Journal Self Cites i a

The tables show the contribution of the journal's self cites to its impact factor. This information is also represented in
the cited journal graph.

Total Cites 1739 Self Cites 669 (38% of 1739)
Cites to Years Used in Self Cites to Years Used 0

Impact Factor Calculation 842 in Impact Factor Calculation 317 (37% of 842)
Impact Factor 2.623 Impact Factor without Self Cites 1.636

Journal Immediacy Index / r

<!-- p. 106 -->

Cites in 2013 to items published in 2013 =279

Number of items published in 2013 =316
Calculation: Cites to current items 279 =0.883
Number of current items 316

Journal Cited Half-Life v /

The cited half-life for the journal is the median age of its items cited in the current JCR year. Half of the citations to the
journal are to items published within the cited half-life.
Cited Half-Life: 2.4 years

Breakdown of the citations to the journal by the cumulative percent of 2013 cites to items published in the following
years:

Cited Year 2013 2012 2011 2010 2009 2008 2007 2006 2005 2004 2003-all
\# Cites from 2013. 279 «421 9 «4210 423 195 0 0 0 0 0 0
Cumulative % 16.04 40.25 64.46 88.79 100.00 100.00 100.00 100.00 100.00 100.00 100

Cited Half-Life Calculations:
The cited half-life calculation finds the number of publication years from the current JCR year that account for 50% of
citations received by the journal. Read help for more information on the calculation.

Cited Journal Graph
Click here for Cited Journal data table

This graph shows the distribution by cited year of citations to items published in the journal REMOTE SENS-BASEL.
Citations to the journal (per cited year)

\- The white/grey division indicates
500 ——- 7 — the cited half-life (if \< 10.0). Half of
the journal's cited items were
published more recently than the

421 421 425
: cited half-life.

\- The top (gold) portion of each
column indicates Journal Self

ooo Citations: citations to items in the

a i [Js Half-Life |journal from items in the same
([] + Half-Life journal.
\| is [eels cites ;

200 -— _] mifother cites |” The bottom (blue) portion of each
column indicates Non-Self Citations:
citations to the journal from items

rh | | in other journals.

\- The two lighter columns indicate
\| citations used to calculate the
ate | Impact Factor (always the 2nd and

DNS 2012 2011 2010 2009 2008 2007 2006 2005 2004 3rd columns).
Cited Years

Hunber of Cites

Journal Citing Half-Life v 4

The citing half-life for the journal is the median age of the items the journal cited in the current JCR year. Half of the
citations in the journal are to items published within the citing half-life.
Citing Half-Life: 7.5 years

Breakdown of the citations from the journal by the cumulative percent of 2013 cites to items published in the
following years:

Cited Year 2013 2012 2011 2010 2009 2008 2007 2006 2005 2004 2003-all
\# Cites from 2013 746 1352 1313 1131 1027 #1015 886 857 800 703 6015
Cumulative % 4.71 13.24 21.53 28.67 35.15 41.55 47.14 52.55 57.60 62.04 100

Citing Half-Life Calculations:
The citing half-life calculation finds the number of publication years from the current JCR year that account for 50% of
citations in the journal. Read help for more information on the calculation.

Citing Journal Graph /
Click here for Citing Journal data table

This graph shows the distribution by cited year of citations from current-year items in the journal REMOTE SENS-

BASEL.

Citations from the journal (per cited year)
\- The white/grey division indicates
the citing half-life (if \< 10.0). Half of
the citations from the journal's

<!-- p. 107 -->

current items are to items published
A — T a more recently than the citing halflife.
\- The top (gold) portion of each
aan column indicates Journal Self1952 Citations: citations from items in the
” 1513 ; : :
2 journal to items in the same
‘i200 L—_ 1134 | +4 journal.
oi 1027 dais | [1 Half-Life
5 Pee [[)> Half-Life |- The bottom (blue) portion of each
5 aa [jse1r cites [column indicates Non-Self Citations:
4 Sy ee 703°) mother cites [Citations from the journal to items
\= in other journals.
409 /— ] —
. 20135 2012 2011 2010 2009 2008 2007 20068 2005 2004
Cited Years
Journal Source Data v) =
Citable items
Articles Reviews Combined Other items
Number in JCR year 2013 (A) 311 5 316 5
Number of references (B) 14620 1197 15817 28.00
Ratio (B/A) 47.0 239.4 50.1 5.6

Acceptable Use Policy
Copyright © 2014 Thomson Reuters.

THOMSON REUTERS

<!-- p. 108 -->

IS| Web of Knowledge™

Journal Citation Reports®

RETURN TO |

\| @wercome| | ? HELP | bal JOURNAL 2013 JCR Science Edition

© Rank in Category: Remote Sensing

Journal Ranking
For 2013, the journal Remote Sensing has an Impact Factor of 2.623.

This table shows the ranking of this journal in its subject categories based on Impact Factor.

Total Journals Journal Rank Quartile
in Category in Category in Category

REMOTE SENSING 27 6 Ql

Category Name

Category Box Plot i)
For 2013, the journal Remote Sensing has an Impact Factor of 2.623.

This is a box plot of the subject category or categories to which the journal has been assigned. It provides
information about the distribution of journals based on Impact Factor values. It shows median, 25th and
75th percentiles, and the extreme values of the distribution.

REMOTE SENS-BASEL, IF = 2.629.

a
T

bo

.

on
T

Impact Factor
T

»

.

on
T

1.5

Key

0 i
A a. REMOTE
Subject Category SENSING

<!-- p. 109 -->

Documentación y análisis geométrico del patrimonio arquitectónico a partir de métodos
fotogramétricos con una y múltiples imágenes

ARTÍCULO 3: CONFRONTING PASSIVE AND ACTIVE SENSORS WITH NONGAUSSIAN STATISTIC

Descripción de factor de impacto y documentación de la revista.

Nombre de la revista: SENSORS
www.mdpi.com/journal/sensors
Editorial: MDPI
ISSN: 1424-8220
Factor de impacto (2013): 2.048
Ranking de la revista: 10/57
Cuartil: Q1

III

<!-- p. 110 -->



<!-- p. 111 -->

IS| Web of Knowledge™

Journal Citation Reports®

. ; RETURN TO
\| Cal WeLcome | ? HELP | | Mote | 2013 JCR Science Edition

© Journal: SENSORS

5-Year Cited Citing
Impact Impact Immediacy Citable Half- HalfMark Journal Title ISSN Total Cites Factor Factor Index Items life life

C] SENSORS-BASEL 1424-8220 9689 2.048 2.457 0.348 955 3.7 6.6

Cited Journal [IQ Citing Journal [97 Source Data Journal Self Cites

\| CITEDJOURNALDATA | | CITINGJOURNALDATA | [jf] IMPACT FACTORTREND | | RELATED JOURNALS |
Journal Information i) =
Full Journal Title: SENSORS Eigenfactor® Metrics
ISO Abbrev. Title: Sensors Eigenfactor® Score
JCR Abbrev. Title: SENSORS-BASEL 003 150
ISSN: 1424-8220 : . ®
Issues/Year: 12 article Influence
Language: ENGLISH Oeve
Journal Country/ Territory: SWITZERLAND ‘
Publisher: MDPI AG
Publisher Address: POSTFACH, CH-4005 BASEL, SWITZERLAND
Subject Categories: CHEMISTRY, ANALYTICAL
\| \ VIEW JOURNAL SUMMARY List | |G) VIEW CATEGORY DATA |
ELECTROCHEMISTRY
\| ©) VIEW JOURNAL SUMMARY List | |) VIEW CATEGORY DATA. |
INSTRUMENTS & INSTRUMENTATION
\| scorenoTe | | \\ VIEWJOURNAL SUMMARY LIST |
ey VIEW CATEGORY DATA. |
Journal Rank in Categories:
Journal Impact Factor i) a

Cites in 2013 to items published in: 2012 =1770 Number of items published in: 2012 =950

2011 =1545 2011 =669
Sum: 3315 Sum: 1619
Calculation: Cites to recent items 3315 =2.048
Number of recent items 1619
5-Year Journal Impact Factor 1 —

Cites in {2013} to items published in: 2012 =1770 Number of items published in: 2012 =950

2011 =1545 2011 =669

2010 =1667 2010 =641

2009 = 1698 2009 =572

2008 =1471 2008 =486

Sum: 8151 Sum: 3318
Calculation: Cites to recent items 8151 =2.457

Number of recent items 3318

<!-- p. 112 -->

Journal Self Cites i y

The tables show the contribution of the journal's self cites to its impact factor. This information is also
represented in the cited journal graph.

Total Cites 9689 Self Cites 1323 (13% of 9689)
Cites to Years Used in Self Cites to Years Used 0

Impact Factor Calculation 3315 in Impact Factor Calculation 689 (20% of 3315)
Impact Factor 2.048 Impact Factor without Self Cites 1.622

Journal Immediacy Index i} =

Cites in 2013 to items published in 2013 =332

Number of items published in 2013 =955
Calculation: Cites to current items 332 =0.348
Number of current items 955
Journal Cited Half-Life i —

The cited half-life for the journal is the median age of its items cited in the current JCR year. Half of the
citations to the journal are to items published within the cited half-life.
Cited Half-Life: 3.7 years

Breakdown of the citations to the journal by the cumulative percent of 2013 cites to items published in the
following years:

Cited Year 2013 2012 2011 2010 2009 2008 2007 2006 2005 2004 2003-all
\# Cites from 2013 332 1770 1545 1667 1698 1471 641 252 71 31 211
Cumulative % 3.43 21.69 37.64 54.85 72.37 87.55 94.17 96.77 97.50 97.82 100

Cited Half-Life Calculations:
The cited half-life calculation finds the number of publication years from the current JCR year that account for
50% of citations received by the journal. Read help for more information on the calculation.

Cited Journal Graph .v =
Click here for Cited Journal data table

This graph shows the distribution by cited year of citations to items published in the journal SENSORS-BASEL.
Citations to the journal (per cited year)

\- The white/grey division
0 — 7 a indicates the cited half-life
it0 | (if \< 10.0). Half of the
tage 1838 journal's cited items were
: published more recently
than the cited half-life.

1600 -—

\- The top (gold) portion of
— each column indicates
[]* Half-Life |Journal Self Citations:
[[)+ Half-Life |citations to items in the
[sel# cites |journal from items in the
MM Other Cites |Same journal.

i209 LS

aoe

Number of Cites

\- The bottom (blue) portion
of each column indicates

Non-Self Citations: citations
to the journal from items in

1 other journals.
2S 1__]
2013 2012 2041 2019 2003 2008 2007 Zane 2005 2004

ey
\=
\=
cos
o
ced

oo

\- The two lighter columns
Cited Years indicate citations used to
calculate the Impact Factor
(always the 2nd and 3rd
columns).

Journal Citing Half-Life *

The citing half-life for the journal is the median age of the items the journal cited in the current JCR year. Half
of the citations in the journal are to items published within the citing half-life.
Citing Half-Life: 6.6 years

<!-- p. 113 -->

Breakdown of the citations from the journal by the cumulative percent of 2013 cites to items published in the
following years:

Cited Year 2013 2012 2011 2010 2009 2008 2007 2006 2005 2004 2003-all
\# Cites from 2013 1240 3403 3272 3162 2813 2549 2204 2013 1790 1522 11576
Cumulative % 3.49 13.06 22.27 31.16 39.08 46.25 52.45 58.11 63.15 67.43 100

Citing Half-Life Calculations:
The citing half-life calculation finds the number of publication years from the current JCR year that account for
50% of citations in the journal. Read help for more information on the calculation.

Citing Journal Graph i) =
Click here for Citing Journal data table

This graph shows the distribution by cited year of citations from current-year items in the journal SENSORSBASEL.

Citations from the journal (per cited year)

\- The white/grey division
5000 -— > + = indicates the citing half-life
(if \< 10.0). Half of the
citations from the journal's
current items are to items
published more recently
than the citing half-life.

4000 — —

— - The top (gold) portion of
[-]¢ Half-Life Jeach column indicates
[)> Half-Life |Journal Self-Citations:
[self Cites [citations from items in the
Mi Other Cites [journal to items in the

same journal.

oo
\=
\=
\=

Number of Cites
be

\- The bottom (blue) portion
of each column indicates
Non-Self Citations: citations
from the journal to items in
—T other journals.

1009 LE

2015 2012 2011 2010 2009 2008 2007 2006 2005 2004

Cited Years

Journal Source Data i) =

Citable items
Articles Reviews Combined Other items
Number in JCR year 2013 (A) 875 80 955 10
Number of references (B) 27140 8262 35402 142.00
Ratio (B/A) 31.0 103.3 37.1 14.2

Acceptable Use Policy
Copyright © 2014 Thomson Reuters.

"is THOMSON REUTERS

<!-- p. 114 -->

ISI Web of Knowledge™

Journal Citation Reports®

a , RETURN TO
\| @awercome| | ? HEL? | JOURNAL 2013 JCR Science Edition

© Rank in Category: SENSORS

Journal Ranking
For 2013, the journal SENSORS has an Impact Factor of 2.048.

This table shows the ranking of this journal in its subject categories based on Impact Factor.

Total Journals Journal Rank Quartile

Category Name in Category in Category in Category

CHEMISTRY, ANALYTICAL 76 36 Q2
ELECTROCHEMISTRY 27 15 Q3
INSTRUMENTS & INSTRUMENTATION 57 10 Qi

Category Box Plot
For 2013, the journal SENSORS has an Impact Factor of 2.048.

This is a box plot of the subject category or categories to which the journal has been assigned. It provides information
about the distribution of journals based on Impact Factor values. It shows median, 25th and 75th percentiles, and the
extreme values of the distribution.

SENSORS-BASEL, IF = 2.046,
t=]

7a2e

Bad bh ——$-——_- o

\5.
a
Ba.a-e
a
Lied
woah
_
eS
Qa 3.26-
\=
\| ml

2.45

1.65 Key

\| _ CHEMISTRY,
08 A ANALYTICAL
0 — \ B - ELECTROCHEMISTRY
A B c. INSTRUMENTS &
Subject Catesory INSTRUMENTATION

Acceptable Use Policy
Copyright © 2014 Thomson Reuters.
