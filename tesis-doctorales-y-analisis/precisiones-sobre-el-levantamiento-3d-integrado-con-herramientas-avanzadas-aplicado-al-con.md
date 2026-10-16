---
type: libro
title: "Precisiones sobre el levantamiento 3D integrado con herramientas avanzadas, aplicado al conocimiento y la conservación"
author: ""
categoria: "Tesis doctorales y análisis"
paginas: 361
extraccion: "texto"
fuente: "local:E:/Biblioteca digital/Tesis doctorales y análisis/Precisiones sobre el levantamiento 3D integrado con herramientas avanzadas, aplicado al conocimiento y la conservación.pdf"
convertido: 2026-10-13
---

# Precisiones sobre el levantamiento 3D integrado con herramientas avanzadas, aplicado al conocimiento y la conservación

> Texto extraído de `Tesis doctorales y análisis/Precisiones sobre el levantamiento 3D integrado con herramientas avanzadas, aplicado al conocimiento y la conservación.pdf` (361 páginas, texto). El PDF original está en el disco E: (Biblioteca digital); `<!-- p. N -->` marca el inicio de cada página.

<!-- p. 1 -->

Universitat Politècnica de València

Escuela Técnica Superior de Arquitectura

DOCTORADO EN ARQUITECTURA,
EDIFICACIÓN, URBANÍSTICA Y PAISAJE

PRECISIONES SOBRE EL LEVANTAMIENTOPRECISIONES SOBRE EL LEVANTAMIENTO 3D
3D INTEGRADO CON HERRAMIENTAS INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO ALAVANZADAS, APLICADO AL CONOCIMIENTO Y
CONOCIMIENTO Y LA CONSERVACIÓN DEL LA CONSERVACIÓN DEL PATRIMONIO
PATRIMONIO ARQUITECTÓNICO ARQUITECTÓNICO

TESIS DOCTORAL

Dña. Isabel Mtnez-Espejo Zaragoza
Autora de la Tesis Doctoral
\- Universitat Politècnica de València -

D. Francisco Juan Vidal
Director Académico de la Tesis Doctoral
\- Universitat Politècnica de València –

Dña. Gabriella Caroti
Co-Directora Académica de la Tesis Doctoral
\- Università di Pisa –

D. Filippo Fantini
Co-Director Académico de la Tesis Doctoral
\- Università di Bologna –

Valencia

<!-- p. 2 -->

Universitat Politècnica de València

Escuela Técnica Superior de Arquitectura

TESIS DOCTORAL

Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO
CON HERRAMIENTAS AVANZADAS, APLICADO AL
CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO

Dña. Isabel Mtnez-Espejo Zaragoza
Autora de la Tesis Doctoral
\- Universitat Politècnica de València -

D. Francisco Juan Vidal
Director Académico de la Tesis Doctoral
\- Universitat Politècnica de València -

Dña. Gabriella Caroti
Co-Directora Académica de la Tesis Doctoral
\- Università di Pisa –

D. Filippo Fantini
Co-Director Académico de la Tesis Doctoral
\- Università di Bologna –

<!-- p. 3 -->



<!-- p. 4 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

A mi madre, que me ha enseñado que la constancia y la perseverancia son las claves
para conseguir alcanzar nuestros sueños, por su apoyo constante y su amor infinito.

<!-- p. 5 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

ÍNDICE

<!-- p. 6 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

ÍNDICE

\1. Abstract en español, italiano, inglés y valenciano 1

\2. Introducción (Encuadre del estudio) 5
A. Introducción 6
B. Referencias 10

\3. Estado del arte de las metodologías de levantamiento arquitectónico y
la restitución 11
A. El Levantamiento arquitectónico 12
i. Image-based Modelling 18
ii. Range-based Modelling 33
B. La Restitución 44
i. Tipos y su utilización 47
ii. Objetivos de los diferentes modelos para el levantamiento 49
iii. Primera rama: Los modelos matemáticos 53
iv. Segunda rama: Los modelos numéricos 60
C. Referencias 65

\4. Caso de estudio 1. Restauración virtual: El caso de una bóveda gótica en
Coves de Vinromá 67
A. Breve reseña histórica 68
B. Objeto 74
C. Medios, sistemas y metodología de levantamiento 75
i. Clásico: Medidas directas 76
ii. Láser Escáner 77
D. Tratamiento de los datos 91
E. Análisis 94
F. Modelos obtenidos 101
G. Resultados 111
H. Referencias 114

\5. Caso de estudio 2. Anastilosis virtual de modelos adquiridos mediante
escáner láser: Piazza d’Oro dentro del Recinto Arqueológico de Villa
Adriana (Tívoli, Roma) 116
A. Breve reseña histórica 117
B. Objeto 125
C. Medios, sistemas y metodología de levantamiento 126
i. Láser escáner 127
ii. Image-based Modelling 130
D. Tratamiento de los datos. 133
E. Análisis 139

<!-- p. 7 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

F. Modelos obtenidos 144
G. Resultados 148
H. Referencias 152

\6. Caso de estudio 3. Integración de frescos: Bóveda con frescos del Palacio
Roncioni 154
A. Breve reseña histórica 155
B. Objeto 160
C. Medios, sistemas y metodología de levantamiento 162
i. Láser escáner 163
ii. Levantamiento fotogramétrico para la aplicación de la textura 164
iii. Image-based Modelling 165
D. Tratamiento de los datos 169
E. Análisis 176
F. Modelos obtenidos 188
G. Resultados 193
H. Referencias 200

\7. Caso de estudio 4. Nueva herramienta para el levantamiento de cubiertas:
Iglesia San Miniato en Marciana (Cascina, Pisa) 202
A. Breve reseña histórica 203
B. Objeto 208
C. Medios, sistemas y metodología de levantamiento 210
i. Láser escáner 211
ii. Image-based Modelling a partir de fotogrametría aérea (Drone) 213
D. Tratamiento de los datos 223
E. Análisis 228
F. Modelos obtenidos 230
G. Resultados 232
H. Referencias 235

\8. La Terminología como cuestión abierta 237
A. El Levantamiento como campo multidisciplinar 238
B. Objetivos (del capítulo) 239
C. Metodología (del capítulo) 240
D. Campos 240
E. Términos y conceptos 242
i. Campo 1 242
ii. Campo 2 257
iii. Campo 3 265
iv. Campo 4 272
v. Campo 5 275
vi. Campo 6 280
F. Índice de términos 295

<!-- p. 8 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

G. Índice de autores 310
H. Referencias 317

\9. Conclusiones 322
A. Conclusiones en español 323
B. Conclusiones en italiano (Conclusioni) 334
C. Referencias 345

\10. Bibliografía 346
A. Bibliografía básica 347

\11. Agradecimientos 349

<!-- p. 9 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

CAPÍTULO 1. ABSTRACT

0

<!-- p. 10 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

A. ABSTRACT ESPAÑOL

El objetivo de la tesis es el análisis de las nuevas tecnologías para el levantamiento
arquitectónico integrado, que se desarrollará mediante el estudio de ventajas y limitaciones de
cada una de ellas en los diferentes ámbitos de uso, dando una visión global y buscando unificar
terminología y metodología en el campo de la arquitectura y la ingeniería. En particular, entre
las nuevas tecnologías se ha analizado el láser escáner, sea a tiempo de vuelo que a
triangulación, la modelación 3D a partir de imágenes, la fotogrametría a partir de drone, y su
integración con las técnicas clásicas de levantamiento.

Con este objetivo se realiza una serie de casos de estudio, utilizando diferentes técnicas de
levantamiento avanzadas con diferentes aplicaciones siempre dentro del campo del patrimonio
arquitectónico. Estos casos de estudio nos permiten analizar y estudiar dichas técnicas, teniendo,
sin embargo, clara una cosa, no se busca la comparación de las técnicas de Image-based
Modelling y de Range-based Modelling, sino el estudio de éstas para su integración. Esta
integración se considera esencial para realizar restituciones de modelos a alto nivel de detalle
morfológico y cromático.

Por otra parte, y gracias a la experiencia vivida entre dos facultades diversas (arquitectura en
Valencia, España, e ingeniería civil en Pisa, Italia), más allá del problema entre dos idiomas, se
comprueba la existencia de una divergencia entre la terminología empleada por los diferentes
especialistas que intervienen en el proceso, ya sean ingenieros (de diversas ramas), arquitectos o
arqueólogos. Está claro que cada una de las figuras tiene una visión diferente con respecto al
patrimonio construido, a la construcción en general y al levantamiento. La tendencia actual de
formar grupos multidisciplinares, que intervienen en el patrimonio arquitectónico, nos lleva a
decir que una terminología técnica unificada en esta materia, podría facilitar la comprensión y la
integración entre las diversas figuras, creando un código común.

1

<!-- p. 11 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

B. ABSTRACT ITALIANO

L’obiettivo della tesi è l’analisi delle nuove tecnologie per il rilievo architettonico integrato,
che si svilupperà mediante lo studio di vantaggi e dei limiti di ognuna di queste nei diversi
ambiti di impiego, dando una visione globale e cercando di unificare terminologia e
metodologia nel campo dell’architettura e dell’ingegneria. In particolare, fra le nuove tecnologie
sono state analizzate il laser a scansione, sia a tempo di volo che a triangolazione, la
modellazione 3D da immagini, la fotogrammetria da drone e la loro integrazione con le tecniche
classiche di rilievo.

Con tali finalità sono stati presi in considerazione alcuni casi di studio, che impiegassero
diverse tecniche di rilievo avanzato con diversi fini applicativi, appartenenti al campo del
patrimonio architettonico. I casi di studio affrontati ci permettono di analizzare e di studiare
queste tecniche, avendo, tuttavia, chiara una cosa, vale a dire che non si cerca di confrontare le
tecniche di Image-based Modelling e di Range-based Modelling, ma di studiarle per la loro
integrazione. Questa integrazione è considerata essenziale per realizzare restituzioni di modelli
ad alto livello di dettaglio morfologico e cromatico.

D’altra parte, grazie all’esperienza vissuta tra due facoltà diverse (architettura a Valencia in
Spagna ed ingegneria civile a Pisa in Italia), al di la dei problemi di interpretazione tra le due
lingue, si riscontra l’esistenza di una divergenza tra la terminologia usata dai diversi specialisti
che intervengono nel processo, siano essi ingegneri (anche se di rami differenti), architetti o
archeologi. È chiaro che ognuna delle figure avrà una visione diversa del patrimonio costruito,
degli edifici in generale e del rilievo. La tendenza attuale a formare gruppi multidisciplinari, che
intervengono sul patrimonio architettonico, ci porta a dire che una terminologia tecnica unificata
in questa materia potrebbe facilitare la comprensione e l’integrazione tra le diverse figure,
creando così un codice comune.

2

<!-- p. 12 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

C. ABSTRACT ENGLISH

The aim of the thesis is to analyse new technologies for integrated architectural surveys,
studying the advantages and limitations of each in different architectural contexts, providing a
global vision and unifying terminology and methodology in the field of architecture and
engineering. The new technologies analyzed include laser scanning (both time-of-flight and
triangulation), image-based 3-D modelling and drone-based photogrammetry, along with their
integration with classical surveying techniques.

With this goal, some case studies were examined, using different survey techniques with
several advanced applications, in the field of architectural heritage. The case studies enabled us
to analyze and study these techniques, however having quite clear that Image- and Range-based
Modelling techniques, rather than compared, must be analysed for their integration, which is
essential for the rendering of models with high levels of morphological and chromatic detail.

On the other hand, thanks to the experience of the two different faculties (Architecture in
Valencia, Spain and Civil Engineering in Pisa, Italy), besides the issues of interpretation
between the two languages, divergence was found between the terminology used by the
different specialists involved in the process, be they engineers (although dealing with different
branches), architects and archaeologists. It is obvious that each of these profiles has a different
view of architectural heritage, general construction and surveys. The current trend to form
multidisciplinary teams working on architectural heritage, leads us to conclude that an unified
technical terminology in this field could facilitate understanding and integration between the
different figures, thus creating a common code.

3

<!-- p. 13 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

D. ABSTRACT VALENCIANO

L'objectiu de la tesi és l'anàlisi de les noves tecnologies per a l'alçament arquitectònic
integrat, que es desenrotllarà per mitjà de l'estudi d'avantatges i limitacions de cada una d'elles
en els diferents àmbits d'ús, donant una visió global i buscant unificar terminologia i
metodologia en el camp de l'arquitectura i l'enginyeria. En particular, entre les noves tecnologies
s'ha analitzat el làser escàner, siga a temps de vol que a triangulació, la modelació 3D a partir
d'imatges, la fotogrametria a partir de drone, i la seua integració amb les tècniques clàssiques
d'alçament.

Amb este objectiu es realitza una sèrie de casos d'estudi, utilitzant diferents tècniques
d'alçament avançades amb diferents aplicacions sempre dins del camp del patrimoni
arquitectònic. Estos casos d'estudi ens permeten analitzar i estudiar dites tècniques, tenint, no
obstant això, clara una cosa, no es busca la comparació de les tècniques d'Image-based
Modelling i de Range-based Modelling, sinó l'estudi d'estes per a la seua integració. Esta
integració es considera essencial per a realitzar restitucions de models a alt nivell de detall
morfològic i cromàtic.

D'altra banda, i gràcies a l'experiència viscuda entre dos facultats diverses (arquitectura a
València, Espanya, i enginyeria civil en Pisa, Itàlia) , més enllà del problema entre dos idiomes,
es comprova l'existència d'una divergència entre la terminologia empleada pels diferents
especialistes que intervenen en el procés, ja siguen enginyers (de diverses branques) ,
arquitectes o arqueòlegs. Està clar que cada una de les figures té una visió diferent respecte al
patrimoni construït, a la construcció en general i a l'alçament. La tendència actual de formar
grups multidisciplinaris, que intervenen en el patrimoni arquitectònic, ens porta a dir que una
terminologia tècnica unificada en esta matèria, podria facilitar la comprensió i la integració
entre les diverses figures, creant un codi comú.

4

<!-- p. 14 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

CAPÍTULO 2. INTRODUCCIÓN

5

<!-- p. 15 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

A. INTRODUCCIÓN

La tesis doctoral se presenta como una continuación de la tesina realizada en el Máster
Universitario en Conservación del Patrimonio Arquitectónico de la UPV (Mtnez-Espejo
Zaragoza, I., 2010)1. En ella se realiza un riguroso estudio de restitución de una bóveda gótica
que cubría la capilla mayor de una iglesia del siglo XVI de Castellón. Dicho estudio comienza
partiendo de un levantamiento gráfico tridimensional, mediante sistemas basados en sensores
activos, un escáner láser de triangulación y un escáner láser TOF (Time of Flight). Si bien este
estudio se centra en un caso específico, partiendo del levantamiento hasta llegar a la hipótesis de
su estado original, mediante una anastilosis virtual, permite a su vez hacer un análisis sobre el
uso de estos sistemas dentro del campo de la restauración arquitectónica.

La tesina, por lo tanto, permite argumentar el positivismo de esta técnica, que como se
demostraba, permite la obtención de una cantidad de información difícilmente adquirible con
una toma de datos directa. Los sistemas basados en sensores activos ofrecen indiscutibles
ventajas, fundamentalmente derivadas de la capacidad de adquisición rápida y sistemática de las
coordenadas espaciales de un número inmenso de puntos, en forma de modelo virtual 3D (nube
de puntos), que los hacen especialmente adecuados para levantamientos de bienes
arquitectónicos y arqueológicos.

Sin embargo, también en este estudio, se advierten ciertas limitaciones en dichos sistemas de
levantamiento, que se encuentran en estado de desarrollo, y aunque en pocos años ha visto una
veloz evolución, quedan aspectos por resolver.

Por otra parte, en esta tesis se introduce como novedad la inclusión de sensores pasivos de
última generación al uso ya probado de los sensores activos. A lo largo de toda la tesis se ve el
uso de ambos, teniendo, sin embargo, clara una cosa, no se busca la comparación de las técnicas
de Image-based Modelling y de Range-based Modelling, sino el estudio de éstas para su
integración. Esta integración se considera esencial para realizar restituciones de modelos a alto
nivel de detalle morfológico y cromático.

Por otra parte, y gracias a la experiencia vivida entre dos facultades diversas (arquitectura en
Valencia, España, e ingeniería civil en Pisa, Italia), más allá del problema entre dos idiomas, se
comprueba la existencia de una divergencia entre la terminología empleada por los diferentes
especialistas que intervienen en el proceso, ya sean ingenieros (de diversas ramas), arquitectos o
arqueólogos. Está claro que cada una de las figuras tiene una visión diferente con respecto a los
bienes, a la construcción en general y al levantamiento. Sin embargo, también se debe admitir
que una terminología técnica unificada en esta materia, podría facilitar la comprensión y la
integración entre las diversas figuras, creando un código común, imprescindible sobre todo, en

1
Título de la tesis: La Iglesia de los Desamparados de Les Coves de Vinromá. Hipótesis y restitución
virtual de la bóveda de la capilla mayor. Dirigida por Francisco Juan Vidal (director), Filippo Fantini
(codirector), Francisco Grande Grande (codirector) y Esther Capilla Tamborero (codirector).
Levantamiento arquitectónico de la iglesia con escáner láser 3D realizado por Pablo Navarro Esteve.

6

<!-- p. 16 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

la época actual en la que cobran importancia los grupos multidisciplinares en la intervención en
el patrimonio.

El objetivo de la tesis, por lo tanto, es el análisis de la integración entre nuevas tecnologías
para el levantamiento arquitectónico, estudiando las ventajas y las limitaciones de cada una de
ellas en los diferentes ámbitos arquitectónicos, y sus posibilidades al combinarlas, dándole una
visión global buscando unificar terminología y metodología en el campo de la arquitectura y la
ingeniería.

Con este objetivo se realiza una serie de casos de estudio, utilizando diferentes técnicas de
levantamiento avanzadas con diferentes aplicaciones, integrándose entre ellas, siempre dentro
del campo del patrimonio arquitectónico. Estos casos de estudio nos permiten analizar y
estudiar dichas técnicas poniendo de manifiesto sus ventajas y su carencias, permitiendo
concluir en cada uno de ellos que la mejor opción es siempre la integración entre varias de ellas.
Buscando resolver el problema: “In the field of architectural survey there isn't the better and
decisive technique.” (Vernizzi 2007, Remondino 2011; citados en Casu y Pisu, 2013: 44)

El primer caso de estudio, como se comentaba, se refiere a una bóveda gótica en la
Comunidad Valenciana. Se realiza dicho levantamiento buscando poder efectuar una restitución
virtual, que permita comprobar la posibilidad de ejecutar en una segunda fase una restauración
real utilizando las piezas de la bóveda aún conservadas dentro del recinto que anteriormente
cubría. Este caso de estudio permite comprobar la gran utilidad de este tipo de levantamientos,
pues ha permitido estudiar una hipótesis antecedente sobre la bóveda y comprobar mediante una
construcción en 3D utilizando los modelos escaneados que no era posible debido a los ángulos
de las claves en el sentido vertical, porque si bien el estudio realizado utilizando metodología
tradicional, permitía dentro de un margen razonable el estudio de los ángulos en horizontal de la
dirección de las claves, la inclinación en sentido vertical era tan sutil que no era apreciable en el
estudio realizado anteriormente. Con los modelos 3D de alta precisión, y basándose obviamente
en estudios de trazados antiguos, es posible realizar una nueva hipótesis que nos es posible
reconstruir virtualmente, permitiendo de este modo comprobar su coherencia geométrica, y la
utilidad de la combinación de técnicas avanzadas para obtener dichos resultados.

El segundo caso de estudio, consiste en la anastilosis virtual de algunos frisos de temática de
caza situados en Piazza d’Oro dentro del recinto arqueológico de Villa Adriana (Tívoli, Roma).
En este, se realiza un escaneado de la Piazza d’Oro, prestando una especial atención a la zona
donde se situaban dichos frisos. Cuando se efectúa el escaneado surgen algunos problemas
debidos a la luminosidad, a la distancia, etc., problemas presentes en el escáner láser de
triangulación. Por ello, se introduce la fotogrametría como un complemento que permite
solventar las carencias del escáner láser, y a su vez comenzar a hacer las primeras
comparaciones de precisión y de ventajas e inconvenientes entre ambos, para una buena
integración. La lectura de las marcas en sus muros, aún reconocibles, permite estudiar el módulo
corintio usado en la Piazza.

7

<!-- p. 17 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

El tercer caso de estudio, se realiza sobre una bóveda con un fresco del setecientos del
Palacio Roncioni, que ha perdido pequeñas partes de su revestimiento, y con ello, algunas partes
del fresco. Este caso nos lleva a la búsqueda de la integración de frescos en bóveda, siendo
necesario un estudio preciso y detallado de la bóveda, con su consecuente levantamiento. En
este caso, el color real y la textura se convierten en un aspecto clave de gran importancia,
cobrando así la fotogrametría un papel principal, por ser la técnica que mejores resultados da en
cuanto a color en rendering foto-realistas en Modelos Digitales de Superficies (MDS). Se
realiza un levantamiento con escáner láser y uno fotogramétrico. En la parte de fotogrametría se
realizaran diversas pruebas para llegar al modelo más fiel, haciendo estudios para afrontar los
problemas derivados de la distorsión de las fotografías (calibración de la cámara, distancia
focal, apertura del diafragma…), la zona de solape entre éstas, la iluminación, ángulo de
captura, etc.

El último estudio realizado, busca resolver el problema presente en casi todos los
levantamientos arquitectónicos realizados hasta ahora: el levantamiento de cubiertas (no
transitables) o zonas con imposibilidad de levantamiento por no ser accesibles para poder
realizar la campaña fotográfica o el escaneado. Para esta monografía se ha utilizado la Iglesia de
San Miniato en Marciana (Cascina, Pisa). En este caso, se introduce la fotogrametría aérea,
mediante UAV (Unmanned Aerial Vehicle), llamados en español drone o VANT (Vehículo
Aereo No Tripulado). Estos instrumentos permiten hacen un levantamiento fotogramétrico aéreo
para integrar en el modelo de escáner láser la parte faltante por tratarse de “una zona de sombra”
y, por lo tanto, zona no escaneada. Se realiza a su vez una zona de la iglesia levantada por los
tres sistemas, que permiten una comparación de precisión entre fotogrametría aérea, terrestre y
escáner láser, pudiéndose medir el margen de error introducido en la cubierta.

Estos cuatro casos de estudio, por lo tanto, se presentan como aplicaciones que buscan
demostrar la importancia de un levantamiento integrado por varias técnicas, para un buen
estudio del patrimonio arquitectónico y arqueológico. Verdiani y Tioli, (2008: 564) afirman que
se debe entender “el levantamiento digital como el primer paso para investigar el monumento
arqueológico y para crear su representación digital precisa. De esta manera todo el postprocesado de los datos, los análisis y los desarrollos gráficos se hará teniendo como referencia
uno de los estudios más precisos que se ha hecho en esos monumentos, y que se puede hacer
muy lejos del monumento”.

Aunque también se debe tener en cuenta, que como dice Verdiani y Tioli, es solo el primer
paso, que el levantamiento es “La recolección de datos masivos se convierte en un modelo
geométrico que paso a paso se analiza para investigaciones históricas, estudios de paisaje,
como base para planificar nuevos proyectos para el diseño del museo, verificar las hipótesis y
un punto de partida para nuevos y más precisos levantamientos de detalles arquitectónicos y
hallazgos arqueológicos.” (Verdiani y Tioli, 2008: 69) Después del levantamiento se debe hacer
todo un proceso de elaboración de datos que permita llegar a verificar una hipótesis, diseñar un
museo, etc.

8

<!-- p. 18 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

Por otra parte, se busca una unificación de conceptos, de terminología, dentro del campo del
levantamiento con herramientas avanzadas en la arquitectura y la ingeniería para solventar el
problema citado por Guidi y Remondino (2012): “At present even no common terminology
exists for comparing sensors performances” en el que se afirma que no existe una terminología
común para la comparación de estos sensores; y por Amoruso, G., Apollonio, F.I., Remondino,
F., (2010) “Nel campo dell’acquisizione dei dati tridimiensionali con metodologie e strumenti
digitali moderni... una limitata disponibilità di informazioni e letteratura relativa agli standard,
alle metodologie operative e ai dati di comparazione” que afirman que en el campo de la
adquisición de datos tridimensionales con metodologías e instrumentos digitales modernos
existe una limitada disponibilidad de información y literatura relativa a los estándar, a las
metodologías operativas y a los datos de comparación, convirtiéndose en un problema esencial
que debe ser resuelto. Así se realiza un estudio serio y en profundidad de la terminología
utilizada por los diferentes autores dentro del campo de la arquitectura, la ingeniería y la
arqueología, presentándose un trabajo de análisis que finaliza con la elección de un término
considerado el más adecuado, y la definición de éste, adjuntando el resto de los términos usados
para nominarlo entre las diferentes figuras e idiomas. Este capítulo permite buscar cada uno de
los términos utilizados en el campo del levantamiento arquitectónico con herramientas
avanzadas, y relacionarlo con sus sinónimos. Además, permite conocer los autores que utilizan
cada uno de los conceptos, los artículos o libros donde han sido mencionados y una clara
definición del concepto, incluyendo aclaraciones que permiten ver las variaciones que se pueden
encontrar entre autores que utilizan el mismo término, en algunas ocasiones, referidos a
conceptos diversos o con ciertos matices.

9

<!-- p. 19 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

B. REFERENCIAS

 Amoruso, G., Apollonio, F.I. y Remondino, F. 2010. “Caratterizzazione strumentale di
sensori attivi a tempo di volo (ToF) e a triangolazione. Utilizzo di laser scanner su superfici
marmoree di epoca romana” en Benedetti, B., Gaiani, M. y Remondino, F. (ed.) Modelli
Digitali 3D in archeologia: Il caso di Pompei. Edizioni della Normale. Scuola Normale
Superiore Pisa, pp. 118-161.

 Casu, P. y Pisu, C., 2013. “Photo-modeling and cloud computing. Applications in the
survey of late gothic architectural elements” en International Archives of the
Photogrammetry, Remote Sensing and Spatial Information Sciences, Volume XL-5/W1,
2013 3D-ARCH 2013 - 3D Virtual Reconstruction and Visualization of Complex
Architectures. 25 – 26 Febrero 2013, Trento, Italia, pp. 43-50.

 Mtnez-Espejo Zaragoza, I., 2010. La Iglesia de los Desamparados de Les Coves de
Vinromá. Hipótesis y restitución virtual de la bóveda de la capilla mayor. Tesina del
Máster Oficial de Conservación del Patrimonio de la Universidad Politécnica de Valencia
dirigida por Francisco Juan Vidal. Valencia.

 Verdiani, G., Tioli, F., 2008. “Villa Adriana in Tivoli: Four years of digital surveys and
research growth” en On the Road to Reconstructing the Past Computer Applications and
Quantitative Methods in Archaeology (CAA) Proceedings of the 36th International
Conference Budapest. Abril 2 – 6, Budapest, Hungría, pp. 564-570.

10

<!-- p. 20 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

CAPÍTULO 3

Estado del arte de las metodologías de
levantamiento arquitectónico y restitución

11

<!-- p. 21 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

A. EL LEVANTAMIENTO ARQUITECTÓNICO

Si se busca la definición sobre el levantamiento arquitectónico se pueden encontrar
diferentes descripciones de expertos en el campo, Buill, Núñez y Rodríguez (2007: 15) que
afirman: “El término levantamiento es utilizado en el ámbito topográfico y se refiera a la toma
de datos de un objeto y su representación gráfica, en tres dimensiones o utilizando algún
sistema de proyección siendo el sistema acotado el más utilizado como representación final. En
el caso arquitectónico y arqueológico el levantamiento se concreta en la recapitulación del
proceso desarrollado por el arquitecto, las modificaciones posteriores y el deterioro que ha
sufrido con el paso del tiempo (Cramer, 1986; citado en Buill, Núñez y Rodríguez, 2007). El
levantamiento puede considerarse un método de investigación pues sus resultados nos permiten
profundizar en el conocimiento de nuestro patrimonio, que es la base imprescindible para su
conservación”.

Benedetti, Gaiani y Remondino (2010: 17) lo definen como “un elemento estructural
primario de la disciplina que nos permite tomar consciencia de un objeto artificial, (...), y
comunicar sus características a los potenciales utilizadores mediante su representación”.

Interpretando estas definiciones podemos decir que el levantamiento arquitectónico es una
metodología utilizada para copiar la información de un objeto de estudio, en nuestro caso
arquitectónico, del plano real a su representación ya sea en papel o en modo digital.

El levantamiento arquitectónico es un procedimiento de conocimiento que se viene
realizando desde hace siglos. Desde la antigüedad, el hombre opta por utilizar la herramienta del
dibujo para documentar gráficamente sus propiedades terrestres (Juan Vidal, F., 2012), o para
representar cuanto ha creado o modificado (Docci y Maestri, 1984: 17). En otros casos, la
necesidad de conocer la situación de un edificio para realizar modificaciones o mejoras, o
cualquier tipo de planificación, ha hecho siempre necesario realizar un proyecto previo,
utilizando como base, los datos del edificio precedente. El levantamiento es, como afirman
Docci y Maestri (1984: 7), un elemento indispensable en la restauración, el urbanismo, el
análisis arquitectónico, la historia de la arquitectura, la arqueología, las controversias de carácter
judicial, el censo de los bienes culturales y la didáctica en el ámbito de la facultad de
Arquitectura e Ingeniería. Concretizando más, el levantamiento es necesario, en la restauración
conservativa de un edificio antiguo o moderno, en el caso de la reutilización de un inmueble, en
las excavaciones estratigráficas, etc.

Durante mucho tiempo, los croquis y la cinta métrica son utilizados como la metodología de
levantamiento más preponderante, usándose en otros casos sistemas de telemedición o protoinstrumentos de medición topográfica, utilizados con provecho para mediciones arquitectónicas,
desde la época de los egipcios (Docci y Maestri, 1984: 20-24). Será en el siglo XIX, cuando
aparece la fotogrametría clásica arquitectónica, que supone toda una innovación en el mundo del
levantamiento.

En las últimas décadas, han irrumpido nuevos instrumentos, sistemas y metodologías de
levantamiento, que han supuesto un gran avance, permitiendo obtener en menos tiempo una

12

<!-- p. 22 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

cantidad de información extraordinariamente mayor. Así los croquis y la cinta métrica, son
desplazados por herramientas como el escáner láser 3D, o sistemas como el Image-based
modelling, que sucede a la fotogrametría clásica permitiendo obtener, con procesos automáticos
o semi-automáticos, objetos tridimensionales a partir de fotografías realizadas desde diferentes
puntos de vista, siguiendo ciertos pasos que se comentarán en el apartado adecuado.

El Consejo Internacional de Monumentos y Sitios (ICOMOS) cita cuatro formas principales
de expresión del levantamiento arquitectónico (CIPA-ICOMOS, 1980):

\- Trazados en alzado, plantas y secciones
\- Secciones horizontales y verticales
\- Modos gráficos de expresión de las formas no planas
o Planta-alzado
o Cortes verticales
o Isolíneas (curvas de nivel-profundidad)
\- Levantamiento gráfico completado con puntos acotados

Todos y cada uno de ellos son resultados finales fácilmente obtenibles con estas
metodologías de levantamiento.

Las fases de levantamientos se pueden dividir en cuatro grandes etapas (Buill, Núñez y
Rodríguez, 2007): La primera busca conocer el edificio objeto de estudio, fundamentalmente
edad y estilo, los hechos que ha vivido y su evolución constructiva. La segunda es la toma de
datos, los croquis de apoyo, las fotografías, acotaciones y medidas topográficas necesarias. La
tercera etapa constituye la representación gráfica en la que se desarrollará el trabajo y, por
último, la lectura de la obra, que debe examinar aspectos de tipo formal y compositivo
(modulación, ritmos, simetría), dimensiones (escalas, errores) y constructivos (tipologías
constructivas).

Durante el desarrollo de la tesis se verá reflejada cada una de las etapas en los cuatro casos
de estudio que sirven como ejemplificación del tema que se está tratando.

Dentro del levantamiento arquitectónico se deben tener en cuenta algunos aspectos, como
son la precisión y los métodos.

El tema de la precisión se convierte en un aspecto esencial, en el caso del levantamiento para
la conservación del patrimonio arquitectónico, ya que, como se verá en los casos de estudio, los
resultados vienen directamente ligados a dicha precisión.

Se debe aclarar que dentro del tema de la precisión, se deben considerar otros conceptos,
asociados al tema de la precisión, como la exactitud y la tolerancia. Cuando se habla de la
precisión, en realidad no se utiliza el término correcto, ya que el término correcto según la
definición encontrada en el VIM (International Vocabulary Metrology), sería la exactitud. Éste
la define como “el grado de concordancia entre el valor de la magnitud medida y un valor de la

13

<!-- p. 23 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

cantidad real de un mesurando”1, mientras que la precisión es definida como “el grado de
concordancia entre las medidas o valores de cantidad medida obtenida mediante la réplica de
medidas en el mismo o similar objeto, bajo condiciones específicas”2. Está claro que ambos
conceptos están estrechamente unidos, pero el concepto del que se habla es el de la exactitud.
Sin embargo, se decide dejar el uso del término “precisión” por ser éste el comúnmente usado, y
considerarse por ello, más conveniente. La tolerancia, por otra parte, como la define la RAE, es
“la máxima diferencia que se tolera o admite entre el valor nominal y el valor real o efectivo en
las características físicas y químicas de un material, pieza o producto”.

Teniendo presente dichas ideas, se puede afirmar que la precisión y la tolerancia son dos
conceptos muy importantes a la hora de decidir el método de levantamiento más adecuado, y
dentro de los métodos, que se pueden considerar como grandes grupos, también la elección del
sensor dependiendo de la precisión necesaria o establecida como base y, obviamente, su
tolerancia. La elección de un instrumento sin considerar este factor puede suponer que el más
sofisticado y potente instrumento genere una serie de datos no aprovechables. Sirva como
ejemplo el levantamiento de una fachada de una iglesia. Para hacer la captura de datos, se podría
utilizar un escáner láser (la profundización en este tipo de tecnología se realizará en el apartado
adecuado). Sin embargo, dentro de la gama de escáner láser utilizados para la arquitectura
encontramos tres tipos con precisiones muy diferentes en base a la distancia de captura. El
escáner de triangulación alcanza una precisión igual a décimas de micrón, pero en el caso de la
fachada de una iglesia, dicha precisión no es necesaria, el tiempo necesario para realizar la
captura sería muy elevado convirtiendo el método en no adecuado. Se encuentran, sin embargo,
otros tipos de escáneres como el de diferencia de fase o el de tiempo de vuelo, con precisiones
cercanas al cm, que en un tiempo mínimo de levantamiento da una información de alta calidad,
y óptima para el estudio. Ejemplos similares encontramos en el caso de la fotogrametría o la
topografía.

Por otra parte, la precisión, y su tolerancia, también van ligadas a la escala de representación
que se decida dar al objeto. Se debe tener conciencia que para un mismo objeto, dependiendo de
la escala, necesitará un nivel de detalle diferente. Si se tiene en cuenta la tolerancia visiva,
relativa a la agudeza visual, con el valor usado comúnmente de 0,2mm a escala de
levantamiento para un plano a escala 1/E, la tolerancia será 0.2E mm. Siguiendo esta ecuación
podemos observar la tabla de Buill, F., Núñez, M.A., Rodríguez, J.J. (2007: 17) donde se
observan las tolerancias en las escalas de trabajo más empleadas:

1 Traducción realizada por la autora.
2 Traducción realizada por la autora.

14

<!-- p. 24 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

Escala Tolerancia
1/200 4 cm
1/100 2 cm
1/50 1 cm
1/20 4 mm
1/10 2 mm
1/5 1 mm
1/1 0.2 mm

Además de la precisión, otro elemento que deberá ser tenido en cuenta para la elección del
instrumento de levantamiento es la capacidad del material a cooperar ópticamente con respecto
a la señal emitida por dicho instrumento. Se pueden encontrar algunos estudios sobre dicho
tema, como por ejemplo en el libro de Benedetti, B., Gaiani, M. y Remondino, F. (2010), en el
que se realiza una comparación de diversos sensores activos aplicados sobre un mismo material,
un fragmento de mármol. Los resultados son diversos unos de otros. No se trata solo de una
cuestión de precisión unida a la densidad de la captura, sino también de la respuesta de los
materiales a la señal emitida. En general cuando se realizan levantamientos arquitectónicos se
realiza sobre materiales opacos, que no presentan ningún problema con la reflectancia de la
señal. Sin embargo, cuando se debe hacer un levantamiento sobre un material traslúcido o
transparente, algunos problemas aparecen para ciertos sensores activos. Esto se debe a que parte
de la señal emitida es absorbida por el material. Como se comentaba en el ejemplo del mármol,
este material es cristalino, y en el caso del escáner a variación de fase, parte de la luz emitida
por el sensor es absorbida, y el resultado es inaceptable, ya que presenta una calidad deficiente.

Los métodos de levantamiento podemos dividirlos en 3 grandes grupos. El primero, el más
clásico, engloba las técnicas tradicionales y los aparatos más sencillos utilizados de forma
directa para medir el objeto. El segundo grupo estaría compuesto por los métodos y técnicas
topográficas. Por último, un tercer grupo que incluiría los métodos basados en la fotografía.

\- Métodos de medida directa. La cinta métrica utilizada como instrumento principal es el
más frecuente de estos métodos y brinda una calidad apropiada si no se efectúan
medidas encadenadas. La cinta metálica y el hilo de invar ofrecen en general mejores
resultados, ya que soportan menores deformaciones por estiramiento. Se observa en la
actualidad un creciente uso de los medidores láseres manuales sustituyendo a la cinta
métrica, pero la metodología es análoga.
A parte de la cinta métrica, encontramos otros instrumentos de apoyo empleados
comúnmente: como la plomada para la definición de verticales, el nivel de agua para la
definición de horizontales y el peine de arqueólogo para la medición de molduras.

\- Métodos topográficos. Se pueden catalogar en tres grupos según el tipo de coordenadas
que representen: planimétricas (medida de abscisas y ordenados referenciadas a un
sistema cartesiano, triangulación y/o trilateración, poligonación), altimétricas (mediante
niveles topográficos o taquímetros) o la posición tridimensional directamente
(levantamiento planimétrico más nivelación, teodolitos, estaciones totales, barridos
láser escáner 3D).

15

<!-- p. 25 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

Figura 3.01 y 3.02. Imágenes de dos instrumentos de medición altimétrica. A la izquierda un
nivel topográfico fijo situado dentro de la torre de Pisa. A la derecha un nivel topográfico situado
sobre un trípode.

\- Métodos fotogramétricos. Dependiendo de los datos que proporcionen pueden dividirse
en levantamientos planimétricos (métodos fotogramétricos monoscópicos, métodos
estereofotogramétricos, rectificación simple, mosaico, ortofotografía) o
tridimensionales (métodos fotogramétricos monoscópicos, métodos
estereofotogramétricos, rectificación encadenada).

Entre todos ellos nos centraremos en el levantamiento tridimensional con herramientas
avanzadas, y especialmente en dos tipos de levantamientos: El método “Image-based
modelling” y el “Range-based modeling”, haciéndose esta elección por ser en la actualidad los
dos procedimientos más usados para el levantamiento arquitectónico a partir de nueva
tecnología, para obtener modelos poligonales de alto nivel de detalle.

Sin embargo, antes de introducirnos más específicamente en estos dos métodos, se debe
hablar de lo que son los sensores tridimensionales. Basándonos en Guidi, Russo y Beraldin
(2010: 9), podemos afirmar que los sensores tridimensionales son aquellos instrumentos que
permiten generar una imagen 3D de la escena que encuadran. Estas imágenes 3D pueden ser,
bien la representación de la superficie externa de un objeto; o bien, la representación de todo
aquello que está en el interior de un volumen que tal superficie encierra. Atendiendo a sus
características, los sensores tridimensionales pueden ser clasificados de forma diversa. Cabe
destacar un tipo de sensores que usa radiaciones luminosas no ionizadas para explorar, sin
ningún contacto físico, la superficie de un objeto. Dependiendo de la naturaleza de la luz usada
para efectuar la medida encontramos sensores tridimensionales Pasivos y Activos. Los Pasivos
son aquellos que utilizan la luz natural, presente en el ambiente abierto durante el día a causa de
la irradiación solar, o en ambiente cerrado usando la acción de iluminadores genéricos situados
de cualquier manera con respecto al objeto. Los Activos serán, sin embargo, aquellos que
necesiten la luz codificada de tal modo que desarrolle un roll en el proceso de medida.

16

<!-- p. 26 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

Dentro de estas técnicas para reproducir modelos tridimensionales se deberá elegir la más
adecuada, como comenta Manferdini y Remondino (2010: 164) considerando: los objetivos de
proyecto, el presupuesto disponible, las características y las dimensiones de los objetos a
levantar. Asumiendo que un levantamiento debe siempre ser métrico y geo-referenciado, para
elegir la técnica de levantamiento adecuada, se deberá tener en cuenta:

Levantamiento con sensores pasivos: Los datos se adquieren a través de sistemas poco
costosos y fácilmente transportables. Las imágenes necesitan un modelo matemático para
recabar la información sobre la posición espacial de los puntos del objeto desde las imágenes
bidimensionales. Es necesaria una cierta experiencia en la adquisición de datos y en la
elaboración de la información registrada.

Levantamiento con sensores activos: Los instrumentos activos levantan distancias y
producen directamente medidas tridimensionales del objeto levantado. Ejemplos típicos son el
escáner láser (Time of Flight o a triangulación) o sistemas de proyección de haces (stripe
projection system). Los sensores de distancia permiten obtener detalles de un objeto con cierta
precisión (desde decenas de micrón hasta el cm). Generalmente son de fácil utilización, pero
presentan ciertas desventajas ya que son costosos, aparatosos, específicos para un intervalo de
distancia y volumen determinado, y, presentan problemas con algunos materiales. A pesar de
ello, los sensores de distancia representan una herramienta de trabajo empleada frecuentemente
y conveniente, sobre todo, en caso de usuarios no muy expertos, ya que permiten el
levantamiento de millones de puntos en pocos instantes.

Figura 3.03. Escáner láser a triangulación NextEngine Model 2020i. Figura 3.04. Escáner láser a Tiempo
de Vuelo Leica C10.

Se hablará de los sensores activos y pasivos más extensamente en los próximos apartados.

17

<!-- p. 27 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

i. Image-based Modelling3

La modelación tridimensional del patrimonio cultural partiendo de imágenes digitales a
diferentes escalas ha obtenido recientemente una considerable atención por parte de la
comunidad científica. Probablemente, esto se deba a dos aspectos: por un lado, el creciente
interés por parte de la UNESCO y de otras organizaciones nacionales e internacionales hacia
estas técnicas, y, por el otro, el desarrollo de nueva tecnología (hardware y software) para el
registro, la elaboración, la gestión y la visualización de datos 3D.

Actualmente existen diversas tipologías de imágenes, que varían en función de la resolución
geométrica, de la resolución espectral (número de canales espectrales) y de los costes. Para la
adquisición de datos se utilizan diferentes instrumentos: imágenes de satélite a media y a alta
resolución, cámaras digitales para el levantamiento aéreo, plataformas radar espaciales y aéreas,
modelos de helicópteros (UAV) con cámaras digitales, cámaras panorámicas, video cámaras o
teléfonos móviles. Además de estos instrumentos de adquisición, los sistemas GPS y INS/IMU
permiten navegaciones y localizaciones precisas para la geo-referenciación de los datos.

Figuras 3.05 y 3.06. Imágenes de dos UAV, utilizados para hacer un levantamiento de la cubierta de una
iglesia y el puerto marítimo de Marina di Pisa.

Paralelamente a la amplia variedad de imágenes digitales, en los últimos años se ha avanzado
mucho en el desarrollo de software de fotogrametría y han aparecido nuevos procesos
automáticos destinados, en particular, a la orientación de las imágenes y a la generación de
modelos digitales de superficie (DTM o DSM).

Entre las diferentes plataformas de adquisición, cabe destacar un nuevo instrumento: los
“Unmanned Autonomous Vehicles” (UAV), pequeñas plataformas (aeroplanos o helicópteros
sin piloto a bordo) que pueden ser controlados desde una posición remota o que pueden volar
automáticamente utilizando planos de vuelo pre-programados. Las tecnologías UAV se han

3 Manferdini y Remondino, (2010: 162-199), Guidi, G., Russo, M. y Beraldin, J.A., (2010: 16 - 72), Cueli
López, J., 2010 “http://www.worldphotogrammetry.com/home/itemlist/category/6-cursos-gratuitos.html”
y Slama, CC., (1980).

18

<!-- p. 28 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

utilizado tradicionalmente en tareas de vigilancia y en el ámbito militar. Sin embargo, en la
actualidad se han empezado a utilizar en el campo arqueológico, documental y para el
levantamiento.

La fotogrametría (Kraus, 1994) es la ciencia que permite determinar la posición y la forma
de los objetos a partir de fotografías. Los resultados de las medidas fotogramétricas pueden ser:
numéricos, dibujos o imágenes. Los numéricos son coordenadas de puntos objeto en un sistema
de coordinadas tridimensionales (adquisición de datos numéricos); los dibujos son cartas
topográficas representando detalles planimétricos y curvas de nivel, u otras representaciones
gráficas de objetos; y las imágenes, son en general fotografías rectificadas (orto-fotoplanos) y
mapas derivados de éstas, aunque también son en algunos casos imágenes digitales.

La fotogrametría, según Manferdini y Remondino, (2010: 167) tiene la capacidad de
establecer una relación geométrica entre las imágenes y el objeto real en el momento de la toma
fotográfica. Una vez reconstruida esta relación mediante el uso del modelo matemático
(colinealidad), es posible obtener información métrica sobre el objeto a través de imágenes. En
fotogrametría, sensores ópticos pasivos como las foto-cámaras son utilizadas para capturar la
reflexión de la luz natural sobre la superficie del objeto a levantar. Al contrario, los sensores
activos levantan la luz emitida por el instrumento mismo y reflejada sobre el elemento objeto de
análisis. Análogamente a lo que ocurre en la visión humana, si un objeto se capta en al menos
dos imágenes desde dos puntos de vista diferentes, las diferentes posiciones del objeto en las
imágenes permite obtener vistas estereoscópicas e información 3D en las áreas sobrepuestas de
las imágenes.

Tradicionalmente, se ha considerado un procedimiento largo y manual; sin embargo, el
crecimiento experimentado por esta tecnología durante los últimos años ha tenido como
consecuencia el aumento del rendimiento y la automatización de muchos procesos.

Actualmente, restituir un modelo completo, preciso y detallado, requiere la intervención
manual de un operador en el proceso de modelado. Este hecho no es necesario cuando se busca
crear un modelo 3D cuyo objetivo sea simplemente la visualización o para aplicaciones de
realidad virtual, pues, en este caso es posible recurrir a procesos completamente automatizados
(“shape-from-motion”).

Las ventajas de la fotogrametría son bastante evidentes (Manferdini y Remondino, 2010:
168):

\- Las imágenes contienen toda la información para la restitución de modelos 3D
(geometría y textura).
\- Las operaciones de adquisición fotográfica son generalmente más simples y rápidas si
se comparan con la medición directa de un objeto.
\- El levantamiento mediante las imágenes evita eventuales daños al objeto.
\- Un objeto puede ser reconstruido mediante imágenes de archivo aunque ya no esté
disponible o esté dañado.

19

<!-- p. 29 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

\- Los instrumentos fotogramétricos (cámaras y software) son generalmente menos
costosos, portátiles y fáciles de usar.
\- Los recientes desarrollos en el modelado automático de superficies mediante las
fotografías permiten obtener resultados comparables a aquellos obtenidos con sensores
activos (Remondino et al., 2008; Manferdini y Remondino, 2010)

Como se ha explicado anteriormente, el objetivo primario de la fotogrametría es la
adquisición de información métrica precisa y fiable. Ésta se basa en el principio de la
colinealidad que establece como el centro de proyección de la cámara fotográfica, un punto P’
sobre la imagen y su correspondiente punto P en el espacio deben encontrarse sobre una línea
recta o rayo. Para calcular las coordenadas 3D de un punto identificado en al menos dos
imágenes, se intersectan los rayos homólogos (triangulación fotogramétrica).

Figura 3.07. Imagen del concepto de colinealidad y triangulación fotogramétrica.

El conjunto de trabajos para derivar información 3D y métrica de una escena desde imágenes
comprende la calibración de la foto-cámara, planificación y ejecución del reportaje fotográfico,
orientación de las imágenes, medida y restitución 3D, generación de la superficie, “texture
mapping” y visualización.

La calibración de la cámara y la orientación de las imágenes son procesos de fundamental
importancia. En la fase de calibración es importante distinguir entre parámetros internos y
externos de las cámaras. Los parámetros de orientación internos consisten: en la constante de la
cámara (o longitud focal, f), posición del punto principal (x0, y0) y algunos parámetros
adicionales usados para modelar eventuales errores sistemáticos debidos, por ejemplo, a la
distorsión de la lente. Los parámetros de orientación externos consisten en: las 3 coordinadas
espaciales (posición en el espacio de la cámara, generalmente indicados con X0, Y0, Z0) y en las
3 rotaciones del centro prospectico de la cámara en el espacio. La obtención tanto de los
parámetros internos como el de los externos se puede hacer, en general, utilizando dos imágenes
(orientación relativa) o bien, mediante un set de imágenes (solución “bundle”).

20

<!-- p. 30 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

Calibración

Para poder utilizar una cámara digital con fines métricos y para la correcta y detallada
documentación y conservación digital, el instrumento debe ser calibrado. En muchas
aplicaciones la fase de calibración de la cámara consiste en la sola determinación de la longitud
focal, mientras que, para efectuar restituciones más precisas, es necesario calcular todos los
parámetros de calibración citados anteriormente. Así, con el proceso de calibración se
determina la desviación geométrica entre la realidad (colinealidad) y el sistema de adquisición
de las imágenes.

Existen diversos algoritmos para calibrar las cámaras digitales. El método más difuso es el
llamado “self-calibration bundle adjustment”, introducido en la fotogrametría a finales de los
años setenta. El modelo matemático de base utiliza las ecuaciones de colinealidad con el fin de
obtener los considerados parámetros adicionales (AP). Con ello se consigue eliminar posibles
errores sistemáticos presentes en el interior de la cámara.

Uno de los métodos más comunes para realizar el proceso de calibración consiste en la
adquisición de imágenes de un objeto tridimensional constituido por puntos señalizados (target
o dianas) bien reconocibles, medibles y con elevada precisión en las imágenes. Los target suelen
ser coordenadas 3D conocidas y, por lo tanto, pueden ser utilizadas como puntos de control en
la solución del bundle. Existe también la posibilidad de utilizar puntos naturales pero su medida
tendrá una precisión menor con respecto a aquella de los target.

Figuras 3.08 y 3.09. Targets del programa Photomodeler. A la izquierda diana de 8-bit y a la derecha
diana RAD Coded (parte de una diana de 12-bit).

El algoritmo de bundle adjustment, restituye simultáneamente todos los parámetros
desconocidos del sistema, además de la estimación de las precisiones y de las correlaciones de
dichos parámetros. Los parámetros desconocidos del sistema son: la orientación de la cámara
(interior y exterior), las coordenadas de los puntos homólogos entre las imágenes y los

21

<!-- p. 31 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

parámetros adicionales (AP). Las observaciones son las coordenadas de los puntos homólogos
medidos en las imágenes. Por cada observación se escribe una ecuación de colinealidad y el
sistema de ecuaciones, alineado y resuelto iterativamente, produce las incógnitas buscadas.

Además de los 3 parámetros usados para calcular la longitud focal correcta y la posición del
punto principal sobre el sensor, el modelo contiene 3 parámetros para modelar la distorsión
radial (Ki), dos para la distorsión tangencial (Pi), un parámetro para definir la exacta dimensión
del pixel sobre el sensor y uno para corregir el corte de los pixel sobre el plano de la imagen
(Sx). Los últimos parámetros son, generalmente, poco usados en nuestro ámbito de estudio.

Figura 3.10. Pantalla de Photomodeler con los valores de los parámetros calculados de una cámara al
realizar su calibrado.

Los tres parámetros adicionales responsables de la evaluación de la distorsión radial (∆r) se
expresan mediante la ecuación poligonal:

∆r = K1r3 + K2r5 + K3r7

donde “r” indica la distancia radial. La distorsión radial varía en función de la longitud focal.
Los coeficientes Ki están estrechamente correlacionados y la mayor parte del error se representa
con el término K1r3.

La distorsión tangencial es debida, principalmente, a la ausencia del alineamiento de la lente
a lo largo del eje óptico. Debido a ello, los parámetros de distorsión tangencial (P1, P2) están
fuertemente relacionados con la posición del punto principal (xp, yp).

22

<!-- p. 32 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

Figuras 3.11 y 3.12. Esquemas de las posiciones de la cámara para realizar una óptima calibración.

Para realizar una calibración correcta es preferible utilizar de imágenes que hayan sido
capturadas a diferentes distancias del objeto, obtenidas rotando la cámara de ±90 grados,
convergentes y que, a su vez, los puntos presenten una distribución uniforme en las diversas
imágenes. La calidad de la calibración está fuertemente influenciada por la geometría del objeto
a levantar y por la configuración de las estaciones de captura. Diferentes estudios
experimentales en el ámbito de la fotogrametría close-range han demostrado que (Remondino y
Fraser, 2006: 269):

\- La precisión de la calibración aumenta con la convergencia de las imágenes usadas y
con la relación base/profundidad (B/D).
\- La precisión aumenta al aumentar el número de rayos por cada punto levantado.
\- La precisión aumenta con el número de puntos levantados por cada imagen, teniendo al
menos una decena de puntos por imagen.
\- La auto-calibración es fiable solo en los casos en los cuales la geometría favorece un
buen levantamiento.
\- Un objeto plano puede ser utilizado para calibrar una cámara solo en el caso en el cual
las imágenes se adquieran con ángulos de rotación ortogonales al plano de
levantamiento, sean a distancia variable del objeto y presenten un elevado grado de
convergencia.
\- Es siempre aconsejable tener imágenes rotadas y adquirir imágenes rotando la cámara
en ±90 grados.

Network: Planificación y ejecución del reportaje fotográfico

Para realizar una correcta restitución de un modelo geométrico tridimensional, se deben tener
en cuenta una serie de factores, de los que en parte dependerá la calidad del modelo y la
precisión máxima adquirible.

En primer lugar, es muy importante la configuración de la cámara cuando se van a realizar
las fotografías. La cámara presenta una serie de parámetros que deben ser elegidos con
conciencia:

23

<!-- p. 33 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

o Velocidad ISO. El índice ISO determina la sensibilidad de la imagen hacia la intensidad de
la luz que recibe. Este valor es clave para la correcta exposición de la imagen. En el caso de
las imágenes para restitución cuanto más baja es la velocidad ISO es mejor. Cuanto menor
es el ISO el grano es más fino y la nitidez mayor.

o Número f. Es la apertura del diafragma en el objetivo, o lo que es lo mismo la relación
entre la longitud focal y el diámetro de apertura efectivo (f/d). Su ajuste permite modificar
el tamaño de la pupila y regular la cantidad de luz que alcanza el sensor. Este factor, en
práctica, gestiona la nitidez en los diferentes planos presentes en la imagen. Si el divisor de
“f” es bajo, el resultado es una imagen nítida de los objetos presentes en el primer plano y
una parte difuminada correspondiente a los planos segundarios. En el caso de la fotografía
para la restitución, es interesante que toda la fotografía esté enfocada, por lo que se busca
un “d” alto.

o El tiempo de exposición. Es el tiempo durante el cual el obturador permite pasar la luz al
sensor. Éste varía en función de los parámetros anteriores. Sin embargo, debe tenerse en
cuenta que dependiendo del tiempo de exposición, existe un mayor riesgo de que las
fotografías se presenten “movidas”. Este riesgo se elimina cuando se utiliza el trípode
como elemento sustentante de la cámara.

A parte de los parámetros comentados, otro
factor importante es el estudio de la posiciones
de la cámara en el levantamiento con respecto
al objeto de estudio. Para hacer posible que los
mismos puntos del objeto sean capturados en
dos fotogramas consecutivos, es necesario que
estos presenten un área en la cual ambos
contengan la misma porción de objeto
(Cannarozzo, Cucchiarini y Meschieri, 2012:
35). Un recubrimiento alto es importante para
obtener un modelo de alta calidad.

El factor que permite obtener el
recubrimiento deseado (generalmente llamado,
Figura 3.13. Relación entre la distancia entre dos
μ) es la base de captura (B). En efecto, cuanto capturas (B) y la distancia de la cámara al modelo
menor es el valor de “B” mayor es el (A).
recubrimiento entre capturas y mayor la
precisión. En general, el valor óptimo es un
60% de recubrimiento entre dos fotografías
consecutivas.

Por otra parte, la base de la captura “B” puede ser calculada mediante la siguiente formula
(Cannarozzo, Cucchiarini y Meschieri, 2012: 40):

B = L – μ· L = L · (1 – μ)

Así sabiendo que L = l (A / p)

24

<!-- p. 34 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

Se puede llegar a:

B = ( ) ( )

La base de captura es proporcional a las dimensiones del formato de la cámara y a la
distancia del objetivo al modelo.

Orientación de las imágenes

La fase de orientación consiste en encontrar los parámetros de orientación externa (3 de
posición y 3 de rotación) de cada imagen que se está utilizando.

La orientación externa de las imágenes se calcula siempre a través de un procedimiento que
está compuesto por dos fases. En primer lugar, se realiza una evaluación e individualización de
algunos puntos notables dentro de la imagen y una asociación a cada uno de ellos de la
información más destacada presente en el entorno del punto.4 Tras esta primera identificación de
puntos, utilizando el método bundle-adjustment y el principio de colinealidad se obtienen un
conjunto de puntos homólogos entre las imágenes. Cada ecuación de colinealidad corresponde a
un punto imagen. Tales ecuaciones forman un sistema que se resuelve con el método iterativo
de los mínimos cuadrados (Gauss-Markov), el cual permite obtener las coordinadas
tridimensionales de todos los puntos imagen, los parámetros externos de orientación de la
cámara y los valores estáticos de estima de los parámetros desconocidos.

En la fase de orientación, los parámetros internos de la cámara ya no se consideran como
incógnitas, sino fijos.

4 http://bias.csr.unibo.it/maltoni/v&r/DispensePDF/7_V&R_FeatureLocali.pdf (última fecha de consulta:
17/02/2014)

25

<!-- p. 35 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

Figura 3.14. Imagen de dos fotogramas en las que se pueden observar los puntos homólogos encontrados
en modo automático, dentro del programa PhotoModeler Scanner.

Figura 3.15. Imagen del software PhotoModeler Scanner en la que se pueden visualizar la situación de las
cámaras orientadas.

Figura 3.16. Screenshot del software Agisoft PhotoScan en el que es posible observar la situación de las
cámaras con respecto al objeto.

26

<!-- p. 36 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

Restitución 3D

Una vez realizada la calibración y la orientación de las imágenes se pasa a la fase de
restitución del objeto mediante identificación de puntos homólogos entre las imágenes.

Los puntos se individualizan en las zonas más sobresalientes del objeto que se debe restituir,
de modo que sea posible poder después definirlo a través de líneas y superficies.

Cuando la geometría del objeto puede ser determinada empleando pocos puntos se efectúan
medidas manuales o semi-automáticas. Sin embargo, los procesos automáticos se utilizan para
la adquisición de superficies irregulares en las cuales es necesaria una restitución detallada de
las irregularidades superficiales como: bajo y alto relieve, excavaciones, terrenos, estatuas, etc.
Según el número y la densidad de puntos restituidos, se habla de una nube de puntos densa o
difusa.

Figura 3.17. Screenshot del software Rapidform XOR3, en el que se puede ver la restitución de la nube de
puntos exportada desde PhotoModeler Scanner.

El creciente desarrollo y los últimos resultados en el campo de la correlación automática de
imágenes (image matching) (Remondino et al., 2008) testimonian la gran potencialidad del
método fotogramétrico para obtener información 3D detallada y precisa a diversas escalas,
comparable a aquella obtenida con sensores activos.

La correlación de las imágenes, sin embargo, continúa presentando algunos aspectos
problemáticos, por ejemplo: la completa automatización, la oclusión de algunos puntos, la
presencia de áreas sin textura o con elementos repetidos, objetos en movimientos, artefactos
radiométricos, objetos transparentes, etc.

27

<!-- p. 37 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

Generación de la superficie

Una vez extraídos los puntos más significativos para describir el objeto y sus detalles (nube
de puntos densa o difusa), el conjunto de puntos en general se segmenta (en el caso de
elementos arquitectónicos), se convierte en una mesh (superficie poligonal) o, se utiliza como
una simple nube de puntos (para particulares aplicaciones).

Una mesh, en general constituida por triángulos, permite gestionar en manera muy flexible la
superficie, restituyendo una descripción precisa.

El proceso de restitución de la superficie no puede garantizar la restitución exacta de la
misma ya que se posee información solo sobre un número limitado de puntos.

Una correcta distribución de la información sobre una superficie se correspondería con una
densidad de puntos que aumenta en las áreas de gran discontinuidad y disminuye en aquellas
planas.

Figura 3.18. Imagen de la cubierta de una iglesia, convertida la nube de puntos en mesh, en el programa
Rapidform XOR3.

28

<!-- p. 38 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

Figura 3.19. Screenshot de la malla de la figura 3.17, pero realizada con el programa Agisoft PhotoScan.

Si la información adquirida no satisface algunas propiedades del algoritmo de generación de
la mesh (correcta distribución de los puntos, alta densidad, bajo ruido, etc.) los algoritmos
producirán resultados no correctos.

Consideraciones sobre la calidad de un proyecto de restitución fotogramétrico

En fotogrametría, la calidad de las medidas y de la restitución tridimensional depende de la
calidad de los datos capturados, pero también de la calidad del software disponible, de la
experiencia y del tiempo y la energía utilizada en el proceso de medida de los puntos en las
imágenes.

La precisión de la red de captura crece al aumentar la relación B/A y cuando se usan
imágenes convergentes más que imágenes con eje óptico paralelo. Esto es debido a que la
relación base - altura en las fotografías influye directamente sobre la profundidad de los objetos
en la escena, y el uso de imágenes convergentes permite en muchos casos eliminar zonas de
sombra debidas a ángulos agudos, a detalles con muchas molduras, etc.

La precisión de la restitución 3D mejora significativamente con el número de imágenes en
las cuales es posible identificar el punto, sin embargo, llegado a un cierto extremo, la mejora es
menos significativa. Se ha realizado modelos de un mismo objeto, utilizando primero muchas
fotografías que daban un modelo bastante detallado, y después otros en los que se ha probado a
utilizar menos fotografías. En las pruebas se observa que mientras al principio la introducción
de una fotografía puede aumentar bastante el detalle, a partir de unas 6 fotografías que incluyen
la misma parte, el modelo no mejora de forma apreciable.

29

<!-- p. 39 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

La precisión de la restitución 3D aumenta si la configuración geométrica es adecuada y los
puntos medidos están bien definidos (como target) y bien distribuidos en la imagen. Es
importante distribuir los puntos por toda la imagen de una forma más o menos uniforme, si no
puede producirse una mayor precisión en las partes más pobladas de puntos y encontrar
pequeñas desviaciones entre las imágenes en las zonas que no presenten puntos homólogos.

La precisión de un punto 3D está ligada a la precisión de su localización en la imagen que
varía principalmente en función del operador y de la presencia de target.

Se debe poner especial atención en: la proyección de las redes de captura, la elección del
sensor a utilizar, las medidas de los puntos de las imágenes, la geometría de la red y, la
calibración de la cámara usada. En los casos prácticos es muy útil, en primer lugar, calibrar la
cámara, elegir una longitud focal y proyectar una red lo mejor posible. El siguiente paso
consistiría en recuperar la geometría de los objetos utilizando los parámetros de calibración con
la misma regulación de la cámara.

Texture mapping y visualización

Un modelo digital 3D texturizado no sólo consiste en su representación geométrica si no que,
además, proporciona una visualización foto-realista. Para obtener dicha visualización, se
emplean imágenes a color, las cuales son proyectadas sobre la superficie poligonal del mismo
modelo. En las aplicaciones terrestres, cada cara individual de la mesh poligonal se colorea con
el color correspondiente presente en la foto con mejor visibilidad y mayor perpendicularidad.
Este proceso se realiza de forma automática ya que, en una fase anterior del mismo, se ha
obtenido la relación entre las imágenes y el objeto 3D.

Figura 3.20. Malla
de la cubierta con la
incorporación de la
textura foto-realista
realizada en el
software
PhotoModeler
Scanner.

Se debe hacer una distinción entre textura aplicada, que es un pasaje realizado por algunos
programas de foto-modelización, efectuado como último paso del proceso, y puntos colorados,
o coloreados. Esto se refiere a que los modelo 3D pueden ser texturizados mediante dos
sistemas diferentes, uno generando un sistema de proyección particular UV al que se le
proyectan las fotografías previamente orientadas (habitual en programas de foto-modelización,

30

<!-- p. 40 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

como por ejemplo, Agisoft PhotoScan) y el otro, generándose en una fase intermedia en la
conversión de la nube de puntos a mesh, debido a que los puntos presentan ya una información
RGB asociada a los individuales vértices que formarán en una segunda fase la estructura de la
mesh.

La calidad de la textura en el primer método, o mejor dicho la apariencia del color, es mejor, ya
que presenta una resolución mucho más elevada. Debe tenerse en cuenta, sin embargo, que es
necesario corregir la topología del modelo, ya que mejorando la calidad de la mesh se mejora
también el texturizado. La razón es debida a que el programa efectúa antes de la aplicación de la
textura en sí, una operación llamada parametrización. El “Texture mapping” es la operación que
consiste en la toma de una imagen y su aplicación sobre la superficie del modelo, por lo tanto el
paso de un mapa en 2D aplicado a un modelo 3D, llamado también “mapeado”. La
parametrización, es el sistema que permite asociar un vértice (y de consecuencia polígonos) del
espacio 3D a un espacio bidimensional (Fantini, F., 2012: 314). Sin embargo, como los modelos
poligonales no nacen para una “parametrización natural”, como sucede por ejemplo con los
modelos NURBS, realizados a través del mapeado en 3 dimensiones de cualquier cosa realizada
en 2 dimensiones, éstos deben realizarse mediante programas de “enterteinment” como el
Luxology Modo, Autodesk 3D Studio, etc. En dicho caso, debe ser el usuario el que realiza dicha
parametrización, aunque existan métodos automáticos o semiautomáticos, debe éste ejecutar el
comando.

En el caso concreto de Agisoft PhotoScan, para la realización de texturas se realiza en primer
lugar la parametrización, y en segundo lugar la proyección de las fotos. Las fotos son mezcladas
o elegidas, según la modalidad “average” o mosaic”, y proyectadas sobre el modelo. De
consecuencia, como estos modelos han sido previamente parametrizados, las imágenes converge
en el espacio el espacio UV, y por lo tanto sobre el modelo parametrizado. Así, se obtiene un
modelo a su vez mapeado; un modelo que primero se parametriza, se abre en 2D, y después
sobre éste se aplican en su espacio 2D las fotografías, a través de una relación proyectiva que
permita relacionar el modelo de 3 dimensiones en aquel de 2 dimensiones (proyección en 2D),
una vez obtenida esta textura, el modelo es re-mapeado.

Aclarados los pasos para la texturización del modelo, es posible comprender la importancia de
la eliminación de los errores topológicos, ya que la presencia de éstos, genera errores en la fase
de parametrización trasportándolos en la fase de mapeado. Los errores topológicos generan en la
parametrización polígonos aislados, que comportan un desperdicio abundante del espacio UV, y
por lo tanto, un uso improductivo de algunos píxeles.

31

<!-- p. 41 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

Figura 3.21. Bóveda levantada con Image-based Modelling con textura foto-realista en la que se puede
observar las partes tomadas de cada foto por el cambio de iluminación entre una y otra, pero presentando
una continuidad entre las imágenes que la decoran.

32

<!-- p. 42 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

ii. Range-based Modelling5

Los instrumentos activos, normalmente empleados para levantar objetos y producir modelos
3D, son generalmente llamados “range camera” o, para aquellos que utilizan luz láser, escáner
láser 3D.

Actualmente, al igual que en el caso de la fotogrametría, se observa un uso frecuente de
Escáneres láser 3D para el estudio del patrimonio arquitectónico. A la hora de llevar a cabo
investigaciones dentro de este campo, el escáner láser se ha erigido como una de las
herramientas básicas. En la página de CIPA (International Committee for Documentation of
Cultural Heritage), uno de los comités internacionales de ICOMOS (International Council on
Monuments and Sites), el escáner láser aparece como una de las ramas de especialización dentro
de las investigaciones.6

En el caso de los sistemas activos, las coordenadas espaciales de los puntos de una porción
de objeto encuadrada por el escáner pueden ser adquiridas en modo automático.

El proceso de adquisición no discierne entre los puntos de relleno y las líneas arquitectónicas
que definen la geometría del objeto, comportando un grado de detalle constante, tanto para las
partes planas como para aquellas más articuladas. Esto conlleva que, para garantizar un buen
detalle en las partes más complejas, se tenga que hacer también un levantamiento inútilmente
detallado también en las superficies planas.

Figuras 3.22 y 3.23. Imágenes de un escáner láser a triangulación en las que se puede observar el proceso
de adquisición de datos.

5 Apollonio y Remondino (2010: 94-117), Guidi, Russo y Beraldin (2010: 77-114) y Martínez-Espejo
Zaragoza, I., 2010.
6 CIPA http://cipa.icomos.org/fileadmin/template/pdf/Cipa_Brochure.pdf (última fecha de consulta:
17/02/2014)

33

<!-- p. 43 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

Las range camera se basan sobre principios de funcionamiento que varían dependiendo de las
dimensiones del objeto a levantar:

\- Sensores a triangulación: Se utilizan para objetos pequeños y medios, entre 0,1 y 500
cm., o sea, fragmentos o restos arqueológicos, estatuas, pinturas, etc. El principio de
medida sobre el cual se basan estos instrumentos es el de la triangulación, combinando
una fuente luminosa (luz láser o estructurada) con un sensor digital que recoge la luz
proyectada. Se caracterizan por una precisión del orden de pocas decenas de micrón y
permiten realizar escaneados muy densos con tiempos de escaneado en general muy
bajos (pocos segundos para cada adquisición). Conocida la distancia entre el sensor y la
fuente de luz y los ángulos de proyección y adquisición, a través de relaciones
trigonométricas se obtiene la distancia entre el sensor y el objeto a levantar.
La fuente luminosa genera un haz de luz que produce sobre el objeto a levantar,
dependiendo del sensor empleado, un solo punto, una línea o un área. Desde las fuentes
láser, que se mueven para cubrir toda la superficie a adquirir en general, se producen
puntos individuales o perfiles.
\- Sensores a tiempo de vuelo (ToF) y a diferencia de fase: son empleados para objetos de
dimensiones del orden de metros o decenas de metros, como edificios, excavaciones,
paredes rocosas, etc. El principio de medida que usan es el “tiempo de vuelo”, es decir,
la media del tiempo empleado por una fuente luminosa para ir del instrumento al objeto
a levantar y volver al instrumento. El tiempo de vuelo es directamente proporcional a la
distancia entre el instrumento y el objeto. Un instrumento de estas características
contiene un motor capaz de cambiar en intervalos de tiempo regular la dirección de la
mira y, por lo tanto, conocido el ángulo de dirección, se puede medir automáticamente
el objeto entero gracias al movimiento mecánico de la fuente. La fuente luminosa emite
generalmente luz láser, la cual, requiere instrumentos de medida del tiempo muy
precisos, pues viaja a la velocidad de la luz. Ello introduce una incerteza en la medida
de la distancia de 20-30 veces mayor respecto a los sistemas de triangulación. La
estimación del tiempo de vuelo es seguida en modo directo, es decir, calculando el
intervalo de tiempo entre el inicio del impulso luminoso y su vuelta; o, modulando la
radiación luminosa emitida (CW, Continuous Wave) y calculando el desfase entre la
onda de ida y la de vuelta (modo indirecto). Debe aclararse que el modo de medida, es
el que generalmente diferencia dos grupos de escáner, llamando “escáner a tiempo de
vuelo” a los que realizan la estimación del tiempo de vuelo de forma directa, y “escáner
a diferencia de fase” a aquellos que realizan dicha estimación de modo indirecto. A los
sensores a tiempo de vuelo se les llama también LIDAR (Light Detection And Ranging)
y pueden ser empleados sobre plataformas en movimiento (avión, helicóptero, tren,
auto) o en modalidad estática (levantamiento clásico terrestre).

34

<!-- p. 44 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

Figuras 3.24 y 3.25. Escáneres a Tiempo de Vuelo, a la izquierda Scanner Láser Leica C10, a la
derecha Scanner Láser Leica HDScanStation 2.

Los escáneres a triangulación generan una geometría ya compuesta por triángulos. Pueden
operar solo a distancias reducidas de los objetos a levantar y por lo tanto la parte encuadrable es
limitada. Además tienen serios problemas de empleo al exterior con luz diurna intensa.

Los escáneres a tiempo de vuelo, en cambio, general nubes de puntos que deben ser,
sucesivamente, convertidas en mesh. Tienen la ventaja de permitir levantamientos de superficies
a distancias notables en un tiempo relativamente breve.

Figuras 3.26 y 3.27. A la izquierda podemos ver la nube de puntos de una bóveda esquifada del Palacio
Roncioni, a la derecha la misma bóveda convertida en mesh.

35

<!-- p. 45 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

Los escáneres poseen una serie de características metrológicas de “resolución”, “precisión” y
“exactitud” que, normalmente, varían según las modalidades operativas respecto a la distancia
de trabajo o la inclinación de las superficies. Un procedimiento de levantamiento tridimensional
incluye no solo métodos para la extracción de datos relativos a superficies 3D, sino también el
algoritmo de proceso, que permite transformar el conjunto de datos en coordinadas calibradas;
las características medidas, y los modelos o medidas que puedan ser visualizadas y analizadas.

Adquisición de datos

La fase de adquisición de datos 3D se caracteriza por el número de escaneados efectuados,
desde puntos de vista diversos, destinados a levantar todo el objeto.

Los escaneados pueden variar desde decenas hasta centenas, en función de la complejidad
del objeto a escanear y sobre la base del proyecto en la fase de planificación. Aun así, durante la
fase de adquisición se pueden definir nuevos puntos de escaneado, destinados a resolver
particularidades que puedan ponerse de manifiesto sobre el campo.

El producto de cada escaneado singular, en particular para sistemas de triangulación, se
llama range map, y consiste en una matriz de puntos en pseudo-3D7. Para el sistema de tiempo
de vuelo se utiliza nube de puntos, es decir un conjunto de puntos en 3D.

Figuras 3.28 y 3.29. A la izq., “Datos brutos” del escáner a triangulación en el levantamiento de una
dovela. A la drcha., nube de puntos obtenida de una iglesia a partir del escáner a Tiempo de Vuelo, una
vez se han eliminado los puntos externos del objeto de interés.

Cada escaneado tiene un sistema de referencia centrado en el sensor, por ello, para modelar
enteramente el objeto, los múltiples escaneados deben ser transformados y alineados en un
único sistema de referencia. Para permitir una correcta alineación de los escaneados, cada
adquisición debe tener un buen recubrimiento con la precedente y la sucesiva, si no la alineación
podría converger hacia una solución errónea.

7 Guidi, Russo y Beraldin (2010: 94) lo definen con el termino 2,5D, y se entiende como una medida de
superficie donde en correspondencia a cada punto del plano horizontal (plano del sensor), haya un solo
punto sobre el eje vertical (eje del sensor). Una estructura plenamente 3D, que contiene por ejemplo un
rebaje, no tiene por qué cumplir esta condición

36

<!-- p. 46 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

Registro de los escaneados

El objetivo de la fase de registro consiste en buscar la relación espacial exacta entre una serie
de nubes de puntos (o mesh, en el caso de los escáner de triangulación) relativas a un objeto
adquirido desde varios puntos de vista, con el fin de representarlo sobre la base de una vista
tomada como referencia.
Generalmente, el registro se subdividide en una primera fase de alineación preliminar de los
escaneados (coarse registration), seguida de un afinado del registro (fine registration). La fase
de registro requiere que los escaneados presenten una buena superposición entre ellos. Es por
esto que debe ser considerado en las fases precedentes de planificación y adquisición.

Figuras 3.30 y 3.31. Procesos de registro. A la izquierda se puede observar el alineamiento preliminar,
mediante puntos homólogos seleccionados por el usuario, y a la derecha el registro fino, que se realiza de
modo automático.

La estrategia de registro puede diferir por el hecho de que la alineación de todas las tomas se
realicen simultáneamente (multi-view registration) o a parejas de imágenes en cada interacción
(pair-wise registration).

La mayor parte de los métodos utilizan la distancia punto-punto; mientras que, otros utilizan
la distancia entre un punto dado en la primera toma y el correspondiente plano tangente en la
segunda. El problema de la distancia punto-punto surge cuando el punto individualizado en la
primera vista puede no existir en la segunda, por la limitación del número de puntos adquiridos
por el sensor. Esto es fácilmente detectable en el caso de superficies levantadas a baja
resolución.

Para resolver este problema, algunos autores utilizan la distancia punto-plano. En este caso,
en la segunda vista se computa un plano tangente en la posición individualizada del punto
homólogo de la primera. El método punto-plano converge más rápidamente que el método
punto-punto. Para resolver este problema, el método para el alineamiento final de los
escaneados más usado comúnmente es el del algoritmo ICP (Iterative Closest Point).

El algoritmo ICP se compone de dos pasos. En el primero, se identifican parejas de
hipotéticos puntos correspondientes en el área de superposición de dos range map.
Sucesivamente se realiza el proceso de optimización que computa una transformación rígida que
reduce la distancia (por mínimos cuadrados) entre los dos conjuntos de puntos. El proceso es

37

<!-- p. 47 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

reiterado hasta que los criterios de convergencia sean satisfactorios. El algoritmo ICP permite
obtener buenos resultados aun en presencia de ruido gaussiano.

La fase de alineación preliminar generalmente prevé que el
usuario defina manualmente al menos 3 puntos homólogos
entre una pareja de escaneados. Este proceso iterativo
puede ser reducido o eliminado poniendo target en la
escena a levantar.

El uso de target para realizar alineaciones es
frecuentemente empleado en el ámbito del levantamiento
arquitectónico levantándolos, eventualmente, con sistemas
topográficos que permitan, a su vez, una georeferenciación
de los datos 3D escaneados. La ventaja mayor de este
enfoque es la mayor precisión que permite garantizar en
cada condición, si se consigue distribuir los target en modo
correcto en el interior de la escena. Figura 3.32. Imagen de un target en
el momento del rastreo de su
posición.
Una de las desventajas del registro semiautomático es que éste solo es posible si la superficie
levantada es rica en modelado o relieve. En el caso de superficies planas o privadas de relieve,
las partes de range map parcialmente superpuestas pueden ser simétricas y deslizar la una sobre
la otra durante la fase automática de alineación (ICP).

Fusión de las nubes de puntos y generación de la mesh

Tras la fase de alineación, se presenta un conjunto de escaneados alineados entre ellos, en
forma de nubes de puntos (a excepción del caso del escáner por triangulación, cuyos resultados
son directamente una mesh poligonal), que representan el objeto levantado. A continuación, se
procede a su fusión. La nube resultante, sin embargo, presenta datos redundantes y/o
sobreabundantes en las zonas de superposición de los escaneados individuales.

Por otra parte, si la fase de adquisición no ha cubierto todo el objeto y la sucesiva alineación
no se ha realizado correctamente, la nube de puntos presentará un “ruido” o “rumor” de cierto
nivel y, a menudo, desviaciones y/o lagunas debidas a zonas de sombras no alcanzadas por los
escaneados. Por este motivo, los datos, con frecuencia, deben ser filtrados para reducir los datos
en las zonas redundantes o reordenados para tener una distribución uniforme de los puntos.
Realizada esta acción, la nube de puntos puede convertirse en mesh, teniendo una mayor
garantía sobre su calidad.

Mesh editing

En el modelo poligonal, producido a través de la fusión de los diferentes escaneados y la
sucesiva generación de la mesh, aparecen comúnmente pequeñas anomalías topológicas, lagunas

38

<!-- p. 48 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

o imperfecciones, que deben ser eliminadas. Por ello, es conveniente seguir una serie de fases
que permiten la eliminación de tales imperfecciones y mejoran la calidad de la superficie
poligonal, buscando preservar, en la medida de lo posible, la geometría y la forma original.

Las principales operaciones son:

\- Corrección de errores topológicos: corresponde a la eliminación de todos los polígonos
de la mesh que presentan conexiones anormales, que no tienen razón de ser, generadas
en fase de fusión y triangulación. Típicos problemas topológicos a corregir son:
triángulos degenerados (dos o tres vértices de un triángulo coinciden y el triángulo se
convierte por lo tanto en un borde o vértice), triángulos duplicados (dos triángulos de la
misma mesh tienen los mismos vértices), bordes degenerados (un borde está dividido
por más de dos triángulos), bordes inconsistentes (un borde está dividido por dos
triángulos con dirección de la normal opuesta)

\- Cierre de lagunas presentes en la superficie: la ausencia de datos en zonas de sombra
presentes en el objeto en el momento de la adquisición (o aquellas partes de superficie
no alcanzables por el instrumento), problemas de adquisición debidos a la particular
característica de reflexión del material o una baja densidad de la nube que no permite al
algoritmo de triangulación generar una mesh completa pueden derivar en eventuales
lagunas en la mesh. El cierre de los huecos generalmente se realiza con una nueva
triangulación de las áreas faltantes aprovechando la información dada por los triángulos
que definen el borde de la laguna.

Figura 3.33. Mesh en el momento de edición, en el cuál se están eliminando las lagunas causadas por
zonas de sombra.

39

<!-- p. 49 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

Figura 3.34. Imagen de la figura anterior una vez eliminadas las lagunas.

Post-processing de la mesh

El modelo digital obtenido en las fases precedentes debe, a menudo, ser sometido a un
posterior post-processing, con la finalidad de adaptarlo a las aplicaciones a las que se está
conduciendo. Éste puede presentar una cantidad de detalle mayor o menor, y, por ello, ser un
modelo digital directamente no utilizable para aplicaciones interactivas. Por esto es muy
importante conocer a priori la finalidad del modelo digital, para poder decidir el nivel de detalle,
y por lo tanto, el número de polígonos que debe caracterizar el modelo.

Si el número de polígonos es excesivo, es posible efectuar una disminución de éstos, a través
de un proceso llamado “decimation” de la mesh, que reduce sensiblemente la complejidad
geométrica del modelo, eliminando vértices y manteniendo, aun así, bajo control las variaciones
introducidas respecto a la precisión inicial.

Por otro lado, en ocasiones se encuentran zonas en el modelo mallado muy ruidosas, y es
posible aplicar procesos de mejora que permiten alisar la superficie. El objetivo es reducir estos
“defectos” de manera que la forma global, sea garantizada. El proceso normalmente se
denomina “smoothing”, y actúa tomando en consideración un área alrededor de cada vértice
dentro de la zona donde se debe reducir las diferencias de cota entre los puntos en base a una
tolerancia indicada.

40

<!-- p. 50 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

 Smoothing

El alisado de la mesh representa un instrumento central en la elaboración de la geometría. En
los software comerciales han sido introducidos, por ahora, solo técnicas lineales: la llamada
“smoothing laplaciano” y a influjo de curvatura media. Su principal aplicación es la
eliminación del ruido y la generación de adecuadas superficies con el fin del modelado en multiresolución.

Un requisito posterior es, a menudo, la conservación de algunas características de la
superficie, como bordes agudos y ángulos que no pueden ser definidos en una manera “vaga”.

 Decimation

La decimation describe una clase de algoritmos que transforma una inicial mesh poligonal en
otra con un número menor de caras, bordes y vértices. El proceso es generalmente controlado
por el usuario, una vez definidos los criterios de calidad que caracterizan la mesh, con el fin de
preservar las propiedades específicas de la original, por cuanto sea posible. Los típicos criterios
incluyen la distancia geométrica o la apariencia visual. Todos los algoritmos de simplificación
de polígonos usan combinaciones de varios operadores de simplificación. Estos son
primariamente funciones subsidiarias o métodos para realizar la reducción del número de
vértices o polígonos. Los operadores más comunes son los siguientes (Apollonio, F.I. y
Remondino, F., 2010: 108-109):

\1. Normalización: Eliminación de los polígonos redundantes o degenerativos. No tiene
sentido mantener polígonos que son meramente una subdivisión de un área idéntica más
grande, o son definidos en modo no correcto.
\2. Simplificación de los vértices: Unión de todos los puntos dentro de algunos volúmenes
predefinidos.
\3. Simplificación de los bordes: remoción de todos los bordes más cortos de un
predefinido umbral.
\4. Simplificación basada en los ángulos: Eliminación de los bordes formando ángulos más
cerrados, bordes alineados y bordes unidos.
\5. Simplificación de las dimensiones de la cara: Remoción de las caras más pequeñas de
una dada área de umbral.
\6. Simplificación de las caras según las normales: fusión de las caras adyacentes con
normales casi paralelas.

41

<!-- p. 51 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

Figuras 3.35 y 3.36. Imagen de la mesh antes y después del proceso de “decimation”.

Existen diferentes enfoques conceptuales con respecto a la “decimation” de una mesh. Sobre
todo basándose en la interpretación de la reducción de la complejidad como una operación
singular o como un procedimiento iterativo.

 Error de aproximación

Garantizar una tolerancia de aproximación durante la “decimation” es el requisito más
importante para la mayor parte de las aplicaciones.

La utilidad principal de los instrumentos de medida del error es evaluar si una simplificación
es apropiada, determinando si las diferencias con el modelo original están dentro de las
tolerancias preestablecidas.

Al fin de controlar la simplificación, el error de aproximación es medido localmente, pero el
usuario debe especificar un vínculo global sobre el error.

 Remeshing

El objetivo del remeshing consiste en un aumento de la calidad de la mesh con el fin de un
uso de la superficie poligonal misma como input en aplicaciones diversas. El remeshing se
puede definir del siguiente modo (Apollonio, F.I. y Remondino, F., 2010: 113): “dada una mesh
tridimensional, determinar una nueva superficie poligonal cuyos elementos constitutivos sean
capaces de satisfacer requisitos de calidad, dando una buena aproximación de la mesh inicial”.
El término deber ser entendido tanto en relación a la posición, como a la orientación de las
normales y a otras propiedades de orden superior.

42

<!-- p. 52 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

Realización de modelos 3D foto-realistas

El modelo poligonal obtenido después de las operaciones de edición constituye, en los
límites de la resolución y de la precisión definida en la fase de proyecto del levantamiento, una
copia fiel al original desde el punto de vista cuantitativo (o geométrico), y por lo tanto, en
aquello que concierne a la forma, dimensiones espaciales y proporciones. Queda por definir, sin
embargo, su aspecto cualitativo, la considerada “apariencia visual”, o lo que es lo mismo, la
posibilidad del modelo 3D de representar el objeto real reproduciendo en la manera más fiel
posible, también el comportamiento de la superficie con respecto a la reflexión de la luz,
incluyendo las características del color y de acabado de la superficie misma. Tal propiedad es en
general definida como textura de la superficie. La textura puede incluir descripciones relativas a
la geometría de la superficie de escala fina, como por ejemplo, mapeados a alta resolución
espacial de las normales a la superficie o texturas bi-direccionales. La mayor parte de los
escáneres 3D no poseen una cámara digital adecuada para adquirir imágenes digitales de alta
resolución para la textura del modelo geométrico. Las imágenes por lo tanto son adquiridas con
foto-cámaras y después utilizadas para crear un modelo foto-realista. Las imágenes deben ser
registradas y alineadas al modelo geométrico a través de procesos iterativos, identificando
puntos homólogos entre ellos.

Figuras 3.37 y 3.38. A la derecha, imagen de
la bóveda realizada con escáner láser, a la
cual se le ha introducido una textura foto-
realista mediante fotografías. A la izquierda
la UVmap de dicha bóveda a través de la cual
ha sido posible aplicar dicha textura
mediante imágenes individuales.

43

<!-- p. 53 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

B. LA RESTITUCIÓN

El término restitución, según la RAE significa “restablecer o poner algo en el estado que
antes tenía”. Ana Calvo (1997: 198), sin embargo, hace una definición más extensa
describiendo la restitución como “Reintegración de partes pérdidas o desmembradas. Sinónimo
de reintegración.” Definiendo reintegración (p. 188) como “Acción y efecto de reintegrar o
restituir una parte perdida. Técnica de restauración que permite integrar estéticamente una
obra completando sus pérdidas, ya sean de soporte de decoración o de policromía. Con
independencia del criterio estético seleccionado, se limita exclusivamente a las lagunas
existentes en la pieza, y se realiza con materiales inocuos, reversibles y reconocibles con
respecto al original. La reintegración no siempre es necesaria para la conservación del objeto
y, generalmente se trata de una intervención de tipo estético. En algunos objetos, sobre todo en
piezas arqueológicas como cerámicas o metales, es necesario a veces reintegrar para poder
unir fragmentos o piezas sueltas sin suficientes puntos de apoyo, o para equilibrarlas. (…) El
tema de la reintegración ha sido siempre polémico, existiendo diferentes modas, según las
épocas, y se ha llegado, en algunos casos, a posturas extremas. Actualmente el criterio es bien
claro, la conservación de los objetos es prioritaria, sin falsificaciones o reintegraciones que
puedan llevar al engaño, con un respeto absoluto por la obra como documento histórico, y
valorando adecuadamente su aspecto estético”.

Estas definiciones de restitución, se refieren en todo caso, a una restitución física. En ella, los
criterios de intervención son variados y algunos de ellos regulados por la normativa del país. Sin
embargo, en este apartado, la restitución, de la cual se va a hablar, va a ser siempre una
restitución virtual, por ello, será siempre el usuario quien decidirá los criterios a seguir para su
realización, y el tema de estudio se centrará en los tipos de restitución tridimensional realizables
según los diferentes modeladores geométricos que existen en la actualidad para el modelado
arquitectónico.

La modeladores geométricos digitales, según Fantini, F. (2012a: 215), son programas que
tienen como finalidad la construcción de figuras geométricas en el espacio, mediante varias
formas de representación que, a lo largo de este apartado, se reagruparán a lo largo de este
apartado en dos ramas: la matemática y la numérica.

Utilizando una similitud se puede afirmar que estas dos categorías indican el material
constructivo, empleado para realizar un modelo informático utilizable en la representación de la
arquitectura y de los productos de “design”. A primera vista, las dos formas de representación
pueden parecer iguales, al menos cuando se visualizan sobre la pantalla, pero en el fondo
difieren significativamente desde el punto de vista de las potencialidades expresivas, así como
de las metodologías que se aplican al realizar sendos tipos de modelos. El porqué de tales
diferencias se puede comprender mejor si se observa la historia del “computer aided design”:
los modeladores matemáticos han sido desarrollados para resolver problemas específicos de
representación y gestión de proyectos en el campo de la ingeniería (mecánica, aeroespacial,
etc.), y más recientemente, con el desarrollo de las tecnologías de levantamiento con escáner
láser 3D, han irrumpido en el campo de la documentación de los bienes culturales.

44

<!-- p. 54 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

En realidad, cuando se habla de modelo numérico y de modelo matemático se está
afrontando el tema más general de la cantidad de información transmitida a través de una
restitución: de un lado los modelos numéricos describen las formas en el espacio a través de una
aproximación, ya que emplean un poliedro para reproducir la frontera de un objeto real. Por otro
lado los modelos matemáticos definen la frontera de un objeto gracias a la unión de más
superficies continuas (patch o piezas) cada una de las cuales viene descrita a través de una
función paramétrica en “u” y “v”. Una diferencia muy importante es que los modelos numéricos
presentan un detalle geométrico establecido por parte del operador o sobre la base de un
muestreo instrumental y por lo tanto, se bloquean en una resolución concreta (y en consecuencia
a una escala de representación), al contrario que los modelos matemáticos, que presentan la
importante característica del detalle variable, después que las “patch” individuales de un modelo
así constituido puede ser incrementado o disminuido de resolución.

Se deben evaluar atentamente las ventajas e inconvenientes de los unos y de los otros a la
hora de planificar las operaciones necesarias para la construcción de un modelo digital correcto.
De hecho, en este apartado, aparte de la exactitud topológica, es interesante, en general, la
gestión racional de los recursos disponibles: en definitiva un modelo realizado correctamente no
debe prescindir de las previsiones de los tiempo de elaboración que dependen de la capacidad
del diseñador CAD, pero sobre todo se debe tener en cuenta la potencialidad y los límites
constitutivos de programas y calculadores. La planificación de los pasajes necesarios para la
obtención de los modelos digitales es parte integrante de la honestidad con la cual se realiza un
modelo: elegir una aplicación inapropiada puede generar residuos y retrasos que muy a menudo
no son visibles en el modelo digital una vez acabado, pero, la lentitud del “iter” utilizado habrá
supuesto una carga de trabajo para el operador, que convierte en incorrecto al proceso en su
conjunto.

Figuras 3.38 y 3.39. Imágenes de un modelo matemático, en el cual como se observa en el detalle de la
derecha se ha utilizado perfiles dibujados en 2D, y se han convertido en 3D mediante su extrusión en el
software Rhinoceros.

Sobre la base de cuanto se ha dicho acerca de los campos de proveniencia de las dos
categorías de aplicaciones, se puede afirmar que los modelos matemáticos se prestan
mayormente en la generación de superficies lisas caracterizadas por curvaturas simples o dobles

45

<!-- p. 55 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

y tendencia continua, como ocurre en las cúpulas y espacios abovedados en general; los
modelos numéricos, se presentan mayormente cuando se busca resolver problemas de
representación pura más que de un estudio métrico y morfológico y por ello vienen empleados
en los sectores de videojuegos, de animación digital y, en general, en el sector de la creación de
imágenes de rendering.

Muchos aplicativos admiten la coexistencia de ambas formas de representación, pero se
mantienen siempre mayormente unidos a un sector, más que al otro, y por lo tanto presentan
instrumentos más eficientes para trabajar con los modelos matemáticos o con los numéricos,
pero raramente con ambos al mismo nivel. A menudo es necesario aprovechar las dotes de un
programa para obtener ciertos resultados y seguidamente pasar a otros para el “output”
conclusivo de un trabajo: es por este motivo que los modeladores geométricos pueden dialogar
entre ellos a través de formatos estándar que a menudo implican la conversión de los modelos
numéricos en matemáticos y viceversa. Pero tales operaciones de exportación, suelen presentar
cierta complejidad y es necesaria una cierta experiencia por parte del operador que debe conocer
las características de los formatos de intercambio y evaluar atentamente su utilización.

Existen formatos estándar para los modelos matemáticos (Fantini, F., 2012a: 216) como el
.SAT (Standard ACIS Text) y el formato .IGS (Initial Graphics Exchange Specification, IGES),
así como los formatos .OBJ (Alias: Wavefront Object) y el .3DS (3D Studio object) para los
numéricos, pero el problema es que cada aplicación lee y reinterpreta esta información sobre la
base de sus propias potencialidades y, al mismo tiempo, de sus propios límites. Un operador
concienciado deberá planificar las operaciones de modelación en conformidad y con objetivos
precisos de representación, evitando en la medida de lo posible el empleo de aplicaciones
inapropiadas, ya que la importación/exportación conlleva siempre la corrección automática del
fichero. Por ejemplo, el formato, .obj, que de por sí garantiza el transporte de un gran número de
información, no evita disfunciones: si el modelo a exportar es una mesh, del tipo constitutivo de
una malla de polígonos cuadrangulares y dotada de parametrización, es decir de un sistema
capaz de mapear la superficie interna con una única imagen, debemos constatar que un gran
número de aplicaciones, aun leyendo esos ficheros, no soportan integralmente sus
características. Por lo tanto es posible que en el nuevo ambiente de modelación los cuadrángulos
hayan sido convertidos automáticamente en triángulos, o que el mapeado venga reinterpretado o
no reconocido. Para resolver este género de problemas, se propone una serie de posibilidades
estratégicas para meter en campo para la realización de modelos informáticos que puedan
responder a objetivos específicos, y simultáneamente a las propias características base.

46

<!-- p. 56 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

Figuras 3.40 y 3.41. En la imagen 3.40 se puede observar la cubierta resultado del completo proceso de
levantamiento mediante Image-based modelling con textura foto-realista. Sin embargo, en la imagen 40,
se observa dicho modelo sin textura foto-realista debido a una exportación en formato .obj del
PhotoModeler al Rapidform XOR3.

i. Tipos y su utilización

Dada la cantidad de aplicaciones presentes en el mercado, es difícil hacer una lista de modo
exhaustivo de los modeladores geométricos, sin embargo, se proporcionan aquí unas
indicaciones generales para orientarse en el interior de un panorama vasto y en continuo
movimiento.

\1. Los modeladores geométricos que pertenecen al sector del “entertainment” están
basados en su gran mayoría sobre modelaciones numéricas, pero a veces presentan un
sector de modelación matemática, en algún caso, muy avanzado. No obstante, el
objetivo de estas aplicaciones es principalmente el de realizar personajes u objetos de
fantasía que no necesiten de un control métrico y formal comparable al ofrecido por los
CAID. Las más difusas aplicaciones pertenecientes a este sector son (Fantini, F., 2012a:
216): Autodesk 3D Studio Max, Maxon Cinema 4D, Newtek Light Ware 3D, Blender
Foundation Blender, Luxology Modo. Estos últimos pertenecen a un sector medio alto
del mercado y, aunque son usados para la producción de efectos visivos y videojuegos,
se prestan fácilmente a un empleo en el sector de la arquitectura y del design.
Generalmente proporcionan un set de instrumentos de modelación NURBS bastante
elemental, ya que en el curso de los años en los “software house” han priorizado las
sub-D como forma de representación matemática, dada su mayor versatilidad en el
sector de la animación de personajes. A un extremo superior del mercado pertenecen
programas como: Autodesk Maya, Autodesk Softimage y Side Effects Software Houdini.
Estas últimas son aplicaciones muy potentes, capaces de generar y gestionar tanto
modelos numéricos como modelos matemáticos a altos niveles; están pensadas para
trabajar en grupo en el ámbito de grandes producciones cinematográficas y, de hecho,
ofrecen instrumentos incluso excesivos respecto a la necesidad común de los
arquitectos.

47

<!-- p. 57 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

Figura 3.42. Render realizado en el software Luxology Modo de un modelo de superficies sub-D.

\2. Los programas de reverse modeling gestionan modelos matemáticos y numéricos a
partir del levantamiento con el escáner láser. Las aplicaciones más difusas son:
Raindrop Geomagic, Inus Rapidform y Innovmetric PolyWorks. En general permiten
seguir las operaciones de introducir en registro los escaneados, creación de la mesh y
conversión en modelo matemático, evaluación de varios géneros sobre los modelos
basados en cálculos de superficie, volumen y desviación entre proyecto y ejecución, etc.
\3. Un tercer tipo es aquel al cual pertenecen programas largamente empleados por
arquitectos y diseñadores que aun entrando en el sector CAD, han demostrado su
flexibilidad operativa allanando el sector de la restitución de los levantamientos
arquitectónicos en 3 dimensiones. El más utilizado en este sector es el McNeel
Rhinoceros que ofrece un amplio set de instrumentos de modelación NURBS y una
limitada sección de modelación mesh, pero dada su similitud operativa con Autodesk
Autocad y la capacidad de exportar en un gran número de formatos, se ha ganado la
confianza de un amplio número de usuarios. A esta categoría de programas pertenecen
también otras aplicaciones que ofrecen instrumentos de modelación NURBS también
más potentes como por ejemplo AutoDesSys FormZ. A un sector del mercado aún
superior y, en ciertos casos, más unida al sector de los BIM, pertenece Dassault
Systèmes Catia, programa dividido en varios módulos que le permite de extender la ya
alta potencialidad de base hacia otros sectores productivos. Ha demostrado la propia
eficacia también en el ámbito del diseño arquitectónico, permitiendo la representación y
la gestión de proyectos de gran complejidad.
\4. El tipo de los modeladores sólidos es muy popular entre los arquitectos gracias al hecho
de que el muy notable programa Autodesk Autocad se basa propiamente sobre esta
forma de modelación. Sin embargo, ese género de aplicaciones no siempre se presta a la
restitución en 3D de arquitecturas históricas o arqueológicas. Otros programas basados
sobre tal forma de representación matemática son: Siemens Solid Edge, Parametric
Technology Corporation (PTC) Pro/Engineer, Dassault Systèmes Corporation

48

<!-- p. 58 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

SolidWorks. Entre las características principales de estas aplicaciones, hay una que
puede introducir vínculos dimensionales sobre los cuales basar la construcción de un
modelo matemático (longitud, área, volumen, etc.). Con la variación de estos
parámetros, el modelo se reconfigura para adaptarse a las diferentes exigencias. El
problema es que esta versatilidad no se presta tanto a la documentación de los bienes
culturales como en el diseño en el sector mecánico.

Figura 3.43. Imagen de la sección
longitudinal una iglesia de Coves de
Vinromá (Castellón). Maquetación realizada
en Autodesk Autocad.

\5. Un tipo de aplicación de alta programación y que se desarrolla para resolver específicas
exigencias en el sector de la proyección arquitectónica, son los llamados BIM (Building
Information Modeling): en realidad este acrónimo define el proceso que lleva a realizar
y gestionar una serie de información asociada a un elaborado representado bajo la forma
de modelo digital. La característica principal de estas aplicaciones es la de proporcionar
al diseñador una serie de componentes técnicos típicos de la edificación, en lugar de las
clásicas primitivas geometrías abstractas que se encuentran en los paquetes de baja
programación. La ventaja de estas aplicaciones que, de hecho, introducen en el sector de
la arquitectura los cánones del modelado paramétrico, está constituido por la gran
facilidad con la cual se realizan en ellas cálculos métricos y cálculos en general
(comprobación, análisis, etc.), así como la elaboración de plantas, secciones y detalles a
partir del modelo digital. El problema de esta categoría de programas está generalmente
unido a la dificultad de representar condiciones avanzadas de degrado, morfologías
complejas privadas de regularidad, y otras situaciones típicas de la arquitectura histórica
y de la arqueología. Sin embargo, existen diferentes ejemplos que demuestran cómo es
posible, partiendo de un levantamiento con escáner láser, transferir a un building
information model, que evidentemente presenta una larga serie de ventajas respecto al
levantamiento geométrico puro.

ii. Objetivos de los diferentes modelos para el levantamiento

Es importante aclarar una cuestión terminológica que en ciertos casos constituye aún un
motivo de debate a nivel académico. Se refiere al término “modelo geométrico” que a veces se
sobrepone a los precedentes (numérico, matemático) confundiendo el objetivo de la
representación con su “sustancia” en los términos de la informática gráfica. Es necesario

49

<!-- p. 59 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

establecer que, a parte del material constructivo del modelo informático (como se ha llamado
precedentemente), que puede ser de tipo numérico o matemático, existe una posterior y en
algunos casos más importante cuestión que apunta a la cantidad de información transmitida a
través de las elaboraciones tridimensionales que constituyen la razón por la cual se ha decidido
de introducir el término “modelo geométrico”. Éste modelo es una figura geométrica que
representa arquitectura resultado de una operación efectuada por un usuario en la que se decide
omitir o adjuntar información buscando un objetivo comunicacional.

Dado que los modelos informáticos de los cuales se ha estado hablando, constituyen algunas
de las posibles restituciones de un levantamiento (junto a las clásicas plantas, secciones, etc.),
resulta importante especificar cuál debe ser la relación entre “detalle” del levantamiento y su
restitución tridimensional; en otras palabras, cuál debe ser el equilibrio entre los siguientes
factores:

\- Toma de datos realizada sobre la arquitectura para documentar la forma
(levantamiento).
\- Resultados de la restitución tridimensional; en particular el soporte (video, sitio web,
impresión, etc.) y la escala de representación.
\- Peculiaridad de la forma de restitución elegida (numérica o matemática).

El hecho de que un modelo matemático presente detalle variable puede inducir a creer que
una representación LOD garantiza mayor flexibilidad respecto a las escalas de restitución, pero
en realidad no es siempre verdad, visto que los “patch” que constituyen los elementos de base
de los modelos matemáticos pueden representar a su vez una versión muy simplificada del
levantamiento de partida. Al mismo tiempo, si el objetivo para el cual se realiza un modelo
digital es el de obtener una animación exploratoria, no es estrictamente necesario emplear la
precisión de un modelador matemático para construir todo el modelo, de hecho, este último,
antes del rendering, debería ser siempre teselado y por lo tanto convertido en mesh (a nivel de
detalle bloqueado). En otros términos, la posibilidad de incrementar el detalle antes de seguir
cualquier rendering necesario para la animación, presenta sus ventajas, pero también sus costes
en términos computacionales dado que para mantener la resolución “flexible” las aplicaciones
son grabadas por una pesada fase de teselado que en muchos casos sería más conveniente seguir
antes y no a través de software por medio de parámetros generales (punto de vista de la
telecámara, distancia al objeto, curvatura, etc.) Considerando el tiempo necesario para calcular
varios millones de “frame” y el carácter divulgativo de una animación, puede ser más cómodo
modelar directamente en polígonos las partes más simples del modelo como, por ejemplo,
aquellas obtenidas por extrusión simple, revolución, etc.

Una vez expuesto que no existe una verdadera y propia jerarquía cualitativa entre modelos
numéricos y matemáticos, y que debe ser el operador quien establezca, en cada caso, que forma
de representación resulta mejor, a continuación, enumeramos a modo de ejemplo, las categorías
de los posibles output de los modelos informáticos: investigación y búsqueda sobre la forma y
generación de las fábricas, imágenes sintéticas y animaciones con fines divulgativos,
elaboraciones gráficas tradicionales (plantas, alzados, perspectivas, secciones, proyecciones

50

<!-- p. 60 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

acotadas), modelos para presentar en “restyling” en el sector del “design”, análisis estructurales,
cálculo de superficies, volúmenes, centros de gravedad, producciones de modelos físicos a
través de prototipos, realización de partes integrativas en el ámbito por ejemplo de
restauraciones virtuales para la evaluación compresiva de las propuestas proyectuales,
aplicaciones real-time.

Figura 3.44. En esta imagen se puede
observar el uso de modelos matemáticos y
numéricos para realizar el estudio de una
hipótesis de restitución de una bóveda que
se perdió en la Guerra Civil española.

En el ámbito de estas nociones preliminares, que deben considerarse como un “a priori”
respecto a las estrategias de modelación, debe tenerse presente que los modelos matemáticos
permiten fácilmente recabar diseños vectoriales en proyecciones ortogonales o centrales y por
ello se prestan a un diálogo con los CAD destinados a la realización de tablas técnicas, lo que
los hace generalmente compatibles con documentos gráficos proyectuales de tipo tradicional.
Los modelos matemáticos permiten recabar mucho más eficazmente, respecto a los modelos
numéricos, curvas producidas de la intersección de una superficie o mediante operaciones
booleanas (adiciones, intersecciones, sustracciones) y por lo tanto agilizan los estudios sobre la
concepción geométrica de las fábricas. Sin embargo, se recuerda que las aplicaciones unidas al
“reverse modeling” presentan instrumentos muy potentes para recabar en automático desde
modelos mesh, secciones, proyecciones acotadas y contornos aparentes (sea en forma de
polilíneas o de curvas spline) y por lo tanto no es estrictamente necesario desarrollar un modelo
entero NURBS de una arquitectura para recabar las vistas canónicas de la representación. Por
otra parte, si se quisiese generar una imagen sintética o una animación de una cúpula para ser
sometida a una simulación de sombras propias, portadas y claroscuro, sin duda, los programas
para el “entertainment” resultarían más apropiados a tal objetivo, gracias a la mayor flexibilidad
en la gestión en el interior de las mismas imágenes a alta resolución para emplear como textura.
La conclusión es que el diseñador/modelador debe saber aprovechar los puntos fuertes del

51

<!-- p. 61 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

modelador matemático (control numérico y morfológico de las superficies, empleo de planos de
construcción personalizables para diseñar directrices y generatrices, etc.) y del numérico para el
output final (vasta gama de instrumentos para el mapeado y el texturizado, control avanzado
para la simulación de luces y materiales, instrumentos de optimización y contenido de tiempos
de cálculo). En la práctica se puede afirmar que, según el tipo de output buscado, existen
diversas aplicaciones, a partir de las cuales es más conveniente y apropiado comenzar el trabajo
de modelado. Estas coinciden en muchos casos con los modeladores matemáticos, pero dada su
naturaleza prevalentemente destinada al design, adolecen de un problema muy importante que
es necesario tener en cuenta. La referencia es inevitable a la sobrecarga que hace inmanejables
modelos de arquitectura de gran complejidad: se debe pensar por ejemplo en la pérdida de
energía (software y hardware) como resultado de la réplica de elementos seriales como
columnas, molduras, capiteles realizados con la pericia métrica propia de las NURBS.

Como se ha dicho ya, muchas de las aplicaciones de modelado NURBS empleadas en el
sector de la arquitectura, provienen del campo del design y, por lo tanto, tienen como finalidad
la representación precisa de objetos individuales de uso, también muy complejos, pero que en
ningún caso son comparables con la complejidad debida a la gran cantidad de anomalías
presentes en la arquitectura histórica (el número de detalles, el degrado, las lagunas, las
adiciones, la no perfecta ejecución de algunos elementos, etc.). A un nivel de complejidad aún
más elevado se sitúa la restitución de un levantamiento arqueológico por medio de un modelo
digital que, a parte que el grado de simplificación que se debería adoptar, implica problemas
superiores de naturaleza práctica y conceptual.

Es así que en el caso de output de tipo divulgativo es preferible utilizar programas de
modelado poligonal, proveniente del sector del “entertainment” que gracias a tácticas como las
instancias (replicas no modificables) permiten generar y gestionar fácilmente elementos seriales
que se repiten dentro de una arquitectura. En este caso se sacrifica la fiabilidad métrica del
modelo, pero se gana en integridad de la representación. Existe de todas formas un
inconveniente que está constituido por el tipo de output que necesariamente deberá ser de tipo
bitmap y no vectorial, ya que los programas para el “entertainment” en general no permiten
convertir un modelo en diseño CAD. Si por el contrario el objetivo es realizar un diseño CAD
es evidente que no será necesario dividir el modelo, sino simplemente proyectarlo sobre un
plano gracias a los cómodos instrumentos de dibujo presente en los modeladores legados al
sector del diseño industrial. Se puede pensar, solo por poner un ejemplo, en la comodidad de
poder seguir la proyección ortogonal con un modelo NURBS de un pórtico semicircular
constituido por un gran número de columnas dotadas de capiteles: cada capitel presentaría en
proyección ortogonal una mínima variación de los propios contornos aparentes sea visto en
sección que en perspectiva y si se decidiese dibujar todo dentro de un CAD 2D (o manualmente
con papel y lápiz) es evidente que la cantidad de horas de trabajo sería realmente conspicuo;
pero gracias a un modelo matemático bien construido y simples instrumentos de “array” polar
es posible obtener estos elaborados vectoriales en una fracción del tiempo de otra manera
impensable. También en este caso se vuelve a repetir que no es necesario realizar el modelo
matemático de toda la arquitectura, sino solo de las partes destinadas funcionalmente a asistir
las proyecciones de las partes más complejas del dibujo en 2D.

52

<!-- p. 62 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

A este respecto, las cuestiones de base para definir una metodología que se adapte a los
output antes enumerados, comienza a definirse: por un lado existen aplicaciones que permiten, a
través de los modelos matemáticos, controlar rigurosamente la forma del objeto, su construcción
geométrica mediante el diseño de curvas generatrices y directrices, etc. Por el otro están los
modelos numéricos que aun ofreciendo una representación a detalle bloqueado (producida a
través de divisiones de un modelo matemático, directamente generada en programas de
modelado numérico, o desde mallado de nubes de puntos), permiten realizar imágenes, es decir,
bitmap, de fuerte impacto visivo, capaces de producir una descripción fiel del mismo modo en
el cual un objeto arquitectónico se presenta en el mundo real a un observador.

iii. Primera rama: Los modelos matemáticos

Entrando en las ventajas de las formas de la representación numérica y matemática, a
continuación se proporciona una síntesis de los aspectos más relevantes de ambas, con la
finalidad de que se puedan comprender mejor los argumentos a través de ejemplos.

A esta familia pertenecen 3 tipos de modelos: los de tipo sólido, los de tipo NURBS y las
superficies de subdivisión, o sub-D. Los primeros son más difundidos dentro de los mecanismos
CAD, los segundos en el sector del design, mientras que los últimos prevalentemente se usan en
la animación de personajes (caracter animation).

\- Los modelos solidos

Los modeladores sólidos son a menudo empleados para restituir los levantamientos
(escáner láser o tradicionales) que están basados sobre protocolos operativos típicos del
dibujo más que del levantamiento. En otras palabras, se puede afirmar que tal categoría de
aplicaciones está mayormente concentrada en la aplicación de medidas a objetos sólidos,
más que en la utilización de medidas adquiridas en modelos digitales. La distinción quizás
puede parecer sutil, pero en realidad, si se piensa en la cantidad de información que se
necesita para las prácticas de gestión y de restauración en el campo de la arquitectura
histórica, es posible darse cuenta como los instrumentos de modelado basados sobre sólidos
resultan extremadamente limitados respecto a la restitución en tres dimensiones. Piénsese en
la gestión de lesiones, alteraciones superficiales como las exfoliaciones, los lavados, etc. El
motivo base para la utilización de estas aplicaciones basadas en motores de modelado 3D de
tipos ACIS en el sector del levantamiento es principalmente debido a la gran popularidad de
la que gozan tales sistemas de representación entre los arquitectos. Hecha la excepción de
casos muy esporádicos, se considera desaconsejable emplear este género de instrumentos
para restituir en las 3 dimensiones un levantamiento, a menos que no se trate de modelos
fuertemente esquematizados que no tengan el propósito de reproducir fielmente la gran
cantidad de información adquirida mediante levantamientos con escáner láser, y muy a
menudo también con técnicas tradicionales. Los modeladores sólidos ponen a disposición del
operador una serie de instrumentos para la creación de modelos digitales que van desde la
creación directa de primitivos sólidos, a su combinación y modificación; además gracias a la
utilización de perfiles bidimensionales utilizados como directrices y generatrices es posible

53

<!-- p. 63 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

obtener modelos digitales cada vez más complejos. Los comandos disponibles en tales
ámbitos de modelado son:

\- Extrusiones (recta y según binarios) y revolución de perfiles en 2D
\- Contribución de espesores a superficies (Shell)
\- Fillet/bisel (accesorios circulares o lineales)
\- Operaciones booleanas (adiciones, sustracciones, intersecciones)

\- Los modelos NURBS

Los modeladores NURBS son muy flexibles y permiten restituir formas complejas con
gran precisión y elegancia (se piensa en los órdenes arquitectónicos, cúpulas y bóvedas
morfológicamente complejas). A diferencia de los modelos sólidos, las NURBS no definen
objetos sólidos verdaderos y propios, sino que permiten, a través de la unión de más
superficies llamadas patch, (literalmente piezas) representar los límites externos de un
modelo geométrico. Por esto se utiliza la expresión boundary representation, o B-rep
(Fantini, F., 2012a), ya que las piezas, no teniendo espesor, crean sólidos en sí: es por esto
que a veces se utiliza la expresión “waterproof” para indicar un modelo matemático o
numérico privado de lagunas entre una patch y la otra, o entre un polígono y el otro. Si esta
condición no se verifica, la representación no será correcta; no solo teóricamente, sino
también en la práctica, dado que los output del modelo presentan errores evidentes: desde el
dibujo vectorial 2D, o el modelado rápido, al rendering, etc.

En realidad, hoy la distinción entre modelos sólidos y B-rep no es tan importante como
años atrás, de hecho muchas aplicaciones admiten la interacción entre sólidos y superficies,
sin embargo, se considera más apropiado en este apartado profundizar el tema de las NURBS
dado que se ha consolidado en muchos sectores como la solución más eficaz para restituir de
forma precisa un levantamiento con escáner láser. Los programas de reverse modeling,
empleados sobre todo en el sector de ingeniería mecánica y del dibujo, tienen como principal
objetivo obtener un modelo de superficies NURBS desde un levantamiento digital y para
hacerlo emplean articulados procedimientos automáticos o semi-automáticos. En realidad en
la arquitectura y en el sector arqueológico es posible adoptar estas técnicas tout court, y para
comprender por qué resultará útil que se entiendan algunos aspectos fundamentales de este
género de modelos matemáticos.

Antes de que se consolidasen como estándar, la industria del software había efectuado
varias tentativas, más o menos conseguidas, que después condujeron a las NURBS como
forma de representación general. De algún modo, es posible afirmar, que cada letra de este
complejo acrónimo “Non Uniform Rational Basis Spline” (Migliari, R., 2009: 18) representa
uno de los múltiples pasos evolutivos de los modeladores matemáticos. Sin embargo, es
necesario aclarar un aspecto terminológico que puede ser fuente de equivocaciones sobre el
significado de “representación matemática” en relación a las NURBS: una curva o superficie
descrita con tal metodología no equivale a una representación analítica de una línea, una

54

<!-- p. 64 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

cónica, una hélice, etc. De hecho, mediante las NURBS, los lugares geométricos no son
expresados a través de centros, anillos, rallos, etc., sino que son, de hecho, representaciones
aproximadas fruto de complejos algoritmos. Si se secciona un cono NURBS no se obtiene
una cónica, se obtiene una NURBS: evidentemente la distinción entre apariencia y sustancia
no afecta solo al ámbito teórico, sino que reside también en la práctica. Cualquier operación
de manipulación o de análisis que se quiera hacer sobre una curva presupone que será el
operador quien la reconocerá como una figura geométrica conocida y quien sabrá, en
consecuencia, aprovechar la propiedad.

En algunos casos, los dos mundos del modelado numérico y de las matemáticas acaban
por parecerse: solo que en un caso, la naturaleza discreta de la representación es explicita,
mientras en el otro el operador debe recordar que una superficie o una curva NURBS no
pueden ser consideradas de la misma manera que una representación analítica.

Un cono mesh se describe a través de un número discreto de elementos: los vértices,
conectados a través de los bordes, determinan porciones de planos concatenados. Un cono
representado mediante NURBS, es un producto a través de otros entes, unidos por relaciones
matemáticas más complejas dotadas de otras propiedades, pero de hecho, en la base de
ambas formas de representación, se tiene una lista de elementos que contribuyen a describir
numéricamente las formas en el espacio.

Aclarados estos aspectos de fondo que muy a menudo se dan por descontados, se puede
afrontar más en detalle el significado del acrónimo NURBS y las matemáticas que las
sustentan.

Como se ha mencionado precedentemente, en el ámbito de las NURBS, las curvas son
expresadas en forma paramétrica, es decir se definirán a través de una formula explicita
respecto a una variable:

(A) F= F(x).

Donde el parámetro “x” varía entre 0 y 1. Además, las ecuaciones son expresadas a través
de polinomios y por lo tanto una curva spline en forma vectorial se escribe así:

(B) ( ) ⃗⃗ ⃗⃗

En las NURBS, igual que para formas precedentes formas de representación matemática
como Bézier y B-Spline, las coordenadas de los poli (o vértices de control) se sujetan a una
media ponderada obtenida gracias a estas funciones paramétricas que, en el curso de los
últimos años, han ido evolucionando para enfrentarse a la mayor necesidad de ergonomía e
intuición en el dibujo asistido por ordenador.

En las etapas de evolución del dibujo CAD, las curvas de Bézier juegan un roll
fundamental, pero, aun ofreciendo óptimos resultados, eran demasiado difíciles de controlar
y por ello, a partir de éstas, se desarrollaron las B-Spline (funciones de Base de las Spline o
Basis-Spline) que en la práctica permiten unir en una única curva más trazos curvilíneos de

55

<!-- p. 65 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

tipo Bézier contralando la continuidad en los puntos de unión. El adjetivo Rational del
acrónimo NURBS se refiere, sin embargo, a un problema muy interesante de representación
que debe ser resuelto por los programadores: las curvas cónicas como la circunferencia, las
parábolas, etc., no pueden ser descritas a través de simples polinomios, sino que deben
hacerse a través de relaciones de polinomios (de ahí rational).

La “No Uniformidad” significa que a cada parte de la curva pueden corresponder valores
del parámetro no uniformes: esto significa que si en la formula (A) se asignan como valor de
parámetro x=0,5 (recordando que los valores del parámetro varían entre 0 y 1) no quiere
decir que éste recaiga sobre el punto medio de la curva: esta relación que une el valor del
parámetro a su longitud correspondiente en la curva se le llama “parametrización”.

Las consideraciones hasta aquí expuestas tienen correspondencia en el pasar de las curvas
a las superficies, que se deben entender como el producto de dos curvas: como cuando se
sigue la traslación de una curva generatriz sobre una directriz, solo que en las NURBS, una
será una función paramétrica de “u” y la otra de “v”:

F = F (u,v) En la cual tanto “u” como “v” se encuentran entre 0 y 1.

Así como las curvas NURBS son gobernadas por polígonos concatenados, que a veces se
llaman control polyline, también a las superficies se le asocia un control polygon (o control
cage) cuyos vértices son el equivalente en tres dimensiones de los poli en la base de las
curvas.

Las NURBS presentan además una serie de propiedades notables, que las convierten en
entidades extremadamente útiles (Migliari, R., 2009: 18):

·Posibilidad de controlar la flexibilidad a partir del grado (que en el caso de las curvas de
Bézier coincide con el número de puntos menos 1)

·Facilidad en las transformaciones espaciales: para roto-trasladar una curva basta rototrasladar los polos. Esto vale para todas las transformaciones afines y por lo tanto:
translaciones, rotaciones, escalados, reflexiones.

·Envolvente convexa: la curva siempre se encuentra dentro del polígono convexo de los
polos.

·Control de las tangentes: la tangente inicial a la curva tiene siempre la dirección de la
línea entre el primer y el segundo polo y la final entre el penúltimo y el último.

·Control flexible: la curva no tiene más puntos de inflexión de cuantos cambios de
concavidad tiene el polígono de los polos.

Muchas de las nociones apenas expuestas, aun no siendo esenciales en el conjunto de
conocimientos de un operador, pueden contribuir a hacer comprender los límites
constructivos de los modeladores geométricos basados en NURBS; una de las limitaciones
principales respecto a la creación de modelos matemáticos para la arquitectura, depende de

56

<!-- p. 66 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

la propia naturaleza “cuadrangular” de las partes individuales generadas mediante los
modeladores NURBS. Sin depender del modo usado para crearlas (loft, sweep, revolve, etc.),
las “patch” se mantendrán siempre como el producto de las dos direcciones paramétricas “u”
y “v” y por lo tanto es una labor del operador descomponer mentalmente el modelo
geométrico en un conjunto de “patchwork” (operación llamada “despieze”), a menos que no
se pueda recurrir a las llamadas superficies “trimmed”, o sea, recortadas (Fantini, F., 2012a).
Un simple pentágono no puede ser dibujado mediante una sola patch en dos direcciones a
menos que no se construya como la suma de más patch cuadrangulares unidas.

Por cuanto respecta a la relación de las NURBS con la restitución a partir de campañas de
levantamiento con escáner láser, la tendencia, en arquitectura (y a menudo también en
arqueología), es extraer secciones rectas de una nube de puntos y, eventualmente, curvas
caracterizadas en el caso de conversión de la nube en modelo mesh.

Las polilíneas o las curvas NURBS así obtenidas se emplean para especificar la necesidad
de técnicas que van de la producción de objetos clásicos bidimensionales (únicamente
acompañados de screenshot de la nube de puntos), útiles en las prácticas de gestión y
documentación de un bien, hasta la construcción del “telar” wireframe desde el cual se
desarrolla el modelo matemático.

\- Los modelos sub-D

Inicialmente se ha hecho mención de otro tipo de modelo matemático llamado superficies
de subdivisión, afirmando que, en realidad, no entra en el ámbito de la representación de la
arquitectura dado que está principalmente ligado a la industria de los videojuegos y de los
efectos cinematográficos. Sin embargo, gracias a los instrumentos de conversión de los
modelos a alto detalle geométrico (modelos HP) en especial bitmap aplicadas a las sub-D es
posible aplicar el detalle de los escaneados láser a tales representaciones LOD que entre
otras cosas ocupan un espacio irrisorio de memoria.

Es importante saber que para el paso de la mesh original a sub-d existen diversos criterios.
En práctica, hay algoritmos de subdivisión de tipo aproximativo como el Catmull-Clark y el
Loop y otros de tipo interpolación como el Doo-Sabin, el Butterfly y el Kobbelt (Migliari, R.,
2009: 76-78). La recaída en términos aplicativos de esta distinción es de gran importancia en
el ámbito de la modelización a partir de imágenes de referencia, así como de modelos
numéricos derivados de escaneados con láser. Es fácil imaginar, como en ambos casos, la
exactitud de la modelización dependerá exclusivamente de la conciencia del operador que a
través del recalco, llegará a la forma deseada. En todo caso, cuenta sobre todo la experiencia
y la pericia del operador que deberá superar la falta de instrumentos en grado de garantizar y
cuantificar la adherencia de la sub-d con el objeto a reproducir.

57

<!-- p. 67 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

Figura 3.45. Imagen del software Luxology Modo en la cual se está realizando un “retopology” para
generar un modelo de superficies de sub-D.

Uno de los principales límites de la modelación NURBS es constituido de la necesidad de
trabajar solo con piezas cuadrangulares. El diseño de una superficie plana puede por tanto
comportar problemas también en el caso de formas elementales. Un simple pentágono
regular, por ejemplo, en el ámbito de tal forma de representación, debe ser realizado a través
de una serie de patch cuadrangulares oportunamente definidas por el operador. Además, la
ventaja constituida de la arbitrariedad topológica soportada por las CC presenta algunos
límites ya que en algunas zonas del modelo sub-d no es posible verificar la continuidad de
G2. La continuidad deriva de la derivada segunda, es decir, de la función que describe la
curva de una sub-d, que no es verificable en proximidad de los así llamados “puntos
excepción” (extraordinary point). Estos puntos son fácilmente reconocibles ya que en ellos
converge un número de bordes diverso de cuatro. Tal número exprime la valencia de un
punto y equivale al número de bordes que en este convergen. Si es diversa de cuatro, algo
que ocurre inevitablemente en los polígonos triangulares y en los n-gons convertidos en
cuadrángulos, entonces es posible que la continuidad de la curvatura no sea verificable. En
todo caso, Catmull y Clark (Carmull, E. y Clark, J., 1978) proporcionaron una concreta
alternativa a las NURBS para representar superficies morfológicamente complejas. La
fortuna de este algoritmo en el ámbito del software para el “entertainment” ha sido
determinada también en las sucesivas implementaciones en obras de Pixar Animation
Studios que desarrolló las llamadas Catmull-Clark mismas, en grado de definir ángulos vivos
sobre la base de una variación local del criterio de subdivisión.

La metodología de construcción de las sub-D no difiere de la que se utiliza en los
modeladores mesh para obtener un modelo poligonal, con la diferencia que en este caso la
mesh se utiliza como control polygon (o control cage) de una patch de tipo B-Spline
uniforme y bicúbica. Como en el caso de las NURBS, también las sub-D son el producto de

58

<!-- p. 68 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

una media seguida sobre los vértices de control, pero con algunas importantes diferencias: en
el caso del algoritmo de subdivisión de Catmull y Clarck (CC), el software crea una
subdivisión de los polígonos de la mesh de control (de ahí el nombre de superficies de
subdivisión) para determinar la nueva superficie más densa que, en un proceso iterativo,
lleva a obtener una superficie limite teórica llamada σ:

( )

Con M0 se indica la control cage de inicio y con Mn la enésima mesh sobreexpuesta a
subdivisión: la reiteración de las subdivisiones transforma M0 en una superficie cada vez más
lisa (smooth) y continua, y es por ello que las sub-D se prestan en modo eficaz a representar
superficies complejas a curvatura simple o doble. Los CC son el criterio de subdivisión más
difundido en los programas dedicados al entertainment, pero, como se comentaba, existen
también el Doo-Sabin, el Loop, el Kobbelt, etc., que presentan ventajas y limitaciones
dependiendo del tipo de finalidad. El CC presenta la ventaja de poder subdividir la mesh
desde una topología arbitraria, es decir, polígonos triangulares, cuadrangulares o n-gons, lo
que naturalmente constituye una seria ventaja con respecto a las NURBS que al contrario, por
analogía, trabajan con patch de forma exclusivamente triangular. Los únicos inconvenientes
de este método de representación son:

\- La, ya comentada, presencia de puntos llamados “excepciones”, o sea de vértices de M0
que presentan valencia diferente de 4. Utilizando el algoritmo de subdivisión de CC se
obtiene, en los vértices de valencia 4, la continuidad de la derivada primera y segunda de
la superficie. En todos los otros casos, esta condición no es verificable y entonces el
modelo, en el entorno de estos vértices, podría presentar errores de sombreado (sharing).
\- El otro problema es que el criterio de subdivisión CC es de tipo aproximado. La recaída
más problemática, bajo el perfil de la restitución es que, una vez generada una M0 a través
del recalco (retopology) de una mesh de alta densidad o point cloud, los puntos de σ no
coincidirán con aquellos de M0, y mucho menos con aquellos obtenidos tramite el
levantamiento.

Esta última consideración parecería relegar las sub-D a un ámbito de pura representación,
sin pretender una documentación precisa. Sin embargo, eso se resuelve gracias a apropiadas
texturas de desviación (displacement) ya que calculadas a partir de modelos de alta
resolución, permiten obtener resultados de gran eficacia tanto bajo el aspecto de la
representación como de la documentación de un objeto, en particular en el sector
arqueológico.

Con los años las reglas de subdivisión dada por Catmull y Clark han sido desarrollada
autónomamente por individuales software house, para dar a los usuarios soluciones más
ergonómicas y apetecibles, sin embargo las impostaciones dadas en 1978 por los
investigadores se mantiene eficaz para comprender en términos geométricos el
funcionamiento de las sub-d: una vez realizado un poliedro M0 (con topología arbitraria), el
algoritmo de subdivisión lo convierte en M1, M2, M3,… y así. Conforme la mesh viene
subdividida presentará, además de una mayor resolución, también la interesante propiedad

59

<!-- p. 69 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

que la nueva topología estará totalmente constituida de cuadrángulos. Cada cara de n-bordes
se subdivide en “n” cuadriláteros cuyos vértices son obtenidos a través de una media
ponderada que se basa sobre las coordenadas de los vértices de M0, de los puntos medios de
cada borde, los baricentros de los vértices de cada cara. ¿Pero por qué se ha afirmado que
existe una desviación entre teoría de las sub-D y las aplicaciones para la representación? La
respuesta nos la proporciona por el modo con el cual se representa la superficie límite
obtenida con este proceso interactivo de subdivisión. En realidad el operador trabaja siempre
sobre una mesh de bajo detalle que continuamente convierte en una “representación ficticia”
de M∞ al fin de evaluar el recorrido. En otras palabras, trabajar con las sub-D no implica
engrosar el detalle de un modelo numérico de salida convirtiéndolo en denso y liso, significa
más bien trabajar sobre un modelo mesh muy simplificado y modificarlo continuamente
hasta llegar a la forma deseada. El resultado es visualizado como si fuese un modelo
matemático LOD equivalente a uno constituido por patch b-spline bi-cúbico uniforme.

iv. Segunda rama: Los modelos numéricos

Los modelos numéricos, construidos a partir de muestreo instrumental, o gracias a comandos
de modelación directa, son poliedros que aproximan la frontera del objeto real utilizando
porciones de plano delimitadas por secuencias concatenadas de bordes (de tres, cuatro, n
bordes). Los polígonos son entes privados de espesor, así como las patch NURBS, y por lo tanto
también los modelos mesh entran en el ámbito de la boundary representation (b-rep), ya que
definen unos límites que debe separar, sin error, los puntos del espacio del interior del modelo
de aquellos del exterior.

Figura 3.46. Modelo
numérico resultado
de la transformación
en mesh de una nube
de puntos obtenida
con un escáner láser
de ToF.

Las mesh son la forma de representación tridimensional que desde hace mucho tiempo se usa
en el campo del computer graphic y, sin embargo, el proceso de evolución y de actualización
que los envuelve no muestra señales de pararse. El motivo principal de esta “longevidad” es
debido al hecho de que en las tarjetas video y en los motores de rendering en general, calculan

60

<!-- p. 70 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

mucho más rápido los polígonos respecto a los modelos matemáticos, ya que estos, deben ser
divididos antes del rendering.

En cualquier caso los campos de aplicación de los modelos mesh no están solo unidos a la
visualización, entre los principales output permitidos a partir de estas formas de representación
se encuentran:

\- La foto-simulación y la animación;
\- Las maquetas seguidas a través del modelado rápido;
\- El análisis a los elementos finitos (FEA);
\- Las aplicaciones real-time.

Indudablemente el sector de la visualización es el que hace mayor uso de los modelos
numéricos, tanto de aquellos realizados en apropiadas aplicaciones de modelación geométrica,
como de los que deriven de modelos NURBS o sólidos.

Como se ha dicho, los modeladores matemáticos permiten un mayor control en la fase inicial
de construcción del modelo y por lo tanto su uso es a menudo imprescindible. Por ello, el
problema de la conversión desde NURBS a mesh resulta prioritario para poder obtener un
output de calidad.

La calidad de la conversión depende de la atención con la cual se sigue la división y, por lo
tanto, se considera oportuno hacer sobre ella algunas consideraciones de orden práctico con la
finalidad de que resulte clara la importancia. Es evidente que en el momento de llevar a cabo el
rendering de un modelo matemático, el operador se encuentra con el problema de decidir si la
división deber ser realizada mediante software o si conviene hacerla a priori antes del rendering
bloqueando definitivamente la resolución del modelo. Los motivos para efectuar esta elección
pueden ser de diferente naturaleza, pero en cada caso se recuerda que a menudo la adicción de
algunos detalles es más fácil sobre un modelo numérico que sobre uno matemático. Por
ejemplo, entre los elementos que añaden realismo existen los llamados micro-bevel (literalmente
micro-biselado) que se añaden a lo largo de los bordes de modelos de bajo detalle (low-poly)
para mejorar el aspecto y hacerles parecer menos artificiales y abstractos.

Evidentemente no tendría sentido tratar de someter a micro-beveling un modelo de alta
resolución (high-poly) obtenido mediante mallado de nubes de puntos, dado que presenta el
problema opuesto (el excesivo detalle geométrico respecto a las posibilidades de visualización
de muchos hardware). El peso, en términos computacionales, de este micro-biselado si se realiza
mediante modelados NURBS sería muy alto y por lo tanto es aconsejable convertir en mesh y
sucesivamente aportar estas modificaciones a nivel local.

Existen varios algoritmos que permiten la conversión de una superficie NURBS en mesh
(Delaunay, paramétrica adaptiva, espacial, curvatura, etc.), sin embargo aquí no se busca tratar
específicamente las características de los unos o de los otros, sino dar una serie de indicaciones
generales. En este contexto, se recuerda que si el output de un modelo NURBS deber ser una
imagen de rendering, es preferible exportar hacia los programas para el “entertainment” mesh

61

<!-- p. 71 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

formadas por polígonos cuadrangulares. Este aspecto no es de menor importancia y por lo tanto
en el momento de la exportación desde modeladores matemáticos puede convenir tener en
cuenta, no solo por la mayor facilidad de los modelos a cuadrángulos, recibir la adicción de los
detalles de los cuales se ha hablado precedentemente, pero también porque permite una más
fácil selección de los bordes concatenados a lo largo de lo que en las NURBS eran las
direcciones “u” y “v”. Obviamente no todo un modelo puede ser dividido a cuadrángulos, pero
el operador consciente podrá exportar separadamente las superficies más complejas del modelo,
recordando entre otras cosas, que si los vértices de mallas cuadrangulares presentan valencia
igual a 4, admiten una perfecta conversión en sub-D con las ventajas que esto puede determinar.

Por lo que se refiere al texturizado si se utilizan los formatos .OBJ y .3DS es posibles
guardar en el modelo mesh la parametrización del modelo NURBS; también este aspecto es
muy importante ya que evita el molesto y complejo proceso del mapeado UV del modelo
numérico.

En cuanto a los modelos mesh obtenidos del muestreo, el tipo de problema que
habitualmente se debe resolver es un poco diverso con respecto a la división de las NURBS,
dado que el material de base del cual se parte es extremadamente más denso bajo el perfil del
detalle geométrico. En el caso de los modelos digitales obtenidos con el escáner láser, las
revisiones que se pueden controlar en el ámbito de las aplicaciones de mesh procesing son de
naturaleza general y se refieren a decenas de miles de triángulos a la vez. En su conjunto, los
instrumentos puestos a disposición de estos programas tienen el objetivo principal de crear
topologías correctas y un detalle adecuado respecto a la finalidad del operador.

Los instrumentos de mesh processing facilitan la obtención de tales objetivos, individuando
y reparando con soluciones semiautomáticas y automáticas todas las imperfecciones presentes
en un modelo. Permiten además optimizar las superficies en base a diversos criterios (curvatura,
número final de triángulos, longitud media de los bordes, etc.). En cada caso las tres principales
categorías de errores son las siguientes:

\- Todos los polígonos son dotados de una normal, es decir de un vector perpendicular a la
porción de plano definida por una serie de bordes concatenados; si la normal está
dirigida hacia el observador, el polígono es visible, en el caso contrario no lo es, a
menos que no se “fuerce” al programa a visualizar el polígono por ambos lados. Es
evidente que en el conjunto de la mesh debe presentar una tendencia de estos vectores
que sea congruente y no presente contradicciones, por ejemplo, las seis caras de un
cubo: no pueden ser dirigidas tres hacia el exterior y tres hacia el interior, pues la
frontera del modelo, aunque sin lagunas, aparecerá incompleta. Trabajando con
modelos de bajo detalle es fácil evaluar y reparar manualmente estos errores a través de
comandos del tipo “flip polygon”, que se encuentran también en los programas para el
“entertainment”, pero en el caso de modelos muy densos, es necesario utilizar
instrumentos más potentes puestos a disposición por los programas de reverse
modeling. Lo importante es evitar el recurso de instrumentos que fuercen la
visualización de los polígonos por ambos lados, por lo menos en el ámbito del

62

<!-- p. 72 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

rendering, dado que este género de soluciones aumentan de un modo desmesurado los
tiempos de cálculo necesarios para la simulación de la relación luz-materia.
\- Cada borde de cada polígono de un modelo mesh deberá ser compartido por solo otro
polígono, si no la representación presentará ambigüedad. Este fenómeno llamado
dangling face (cara colgante) está identificado y corregido por los programas de reverse
modeling. De hecho estos polígonos no suponen ninguna contribución respecto al
conjunto principal desarrollado por la mesh, es decir, dividir el espacio en puntos
internos y externos a la b-rep.
\- Los poliedros mesh son complejos de células concadenadas las unas con las otras. En
términos prácticos significa que en un modelo digital correctamente construido, los
polígonos no deben simplemente “tocarse” los unos con los otros a lo largo de los
bordes sino que deben compartir los entes geométricos de contacto. En otros términos,
si dos polígonos triangulares parece que tengan en común un borde, no quiere decir que
este elemento geométrico sea único, podrían ser dos bordes sobrepuestos cada uno
perteneciente a uno de los dos polígonos: lo que parecen dos puntos (los extremos de
los bordes) en realidad son cuatro, solo que, dos a dos, presentan las mismas
coordenadas (x,y,z). En términos topológicos este género de situaciones no es diferente
a un agujero en una mesh. Afortunadamente existen comandos apropósito para fundir
juntos los vértices de un modelo numérico que presenta las mismas posiciones y que
pertenecen a un entorno infinitésimo. Dependiendo de las aplicaciones, tales comandos
vienen indicados con diferentes nombres (optimización, merge, fondos, etc.)

La corrección de estos problemas a través de un software encuentra fundamento teórico en
las fórmulas de Eulero para los poliedros: indudablemente es importante tener constantemente
bajo control los diferentes elementos geométricos presentes en esta importante fórmula
(vértices, bordes, caras), dado que en general evita la presencia de errores topológicos (a
excepción de las dangling face), sin embargo se recuerda que es posible emplear también los
modelos no sólidos, y las superficies. Pensando por ejemplo en un modelo digital que represente
un territorio (Modelo Digital Terrestre, MDT), a veces no es necesario convertirlo en un
volumen cerrado, sino utilizarlo simplemente como superficie privada de espesor, en el caso que
se debiese realizar simplemente un rendering. La fórmula de Eulero aplicada a este género de
modelos no estaría verificada. Sin embargo, prescindiendo del resultado numérico de la
fórmula, se debe observar que para obtener un output de tipo bitmap, puede no ser necesario
cargarse de operaciones necesarias para el cierre del modelo.

63

<!-- p. 73 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

Figura 3.47. En esta imagen se
puede observar un programa de
Reverse modelling (Rapidform
XOR3) en el cual se está
realizando la eliminación de
errores topológicos con un
proceso semi-automático.

Al contrario los output físicos de los modelos numéricos y matemáticos, es decir los prototipos,
las maquetas, y los modelos de estudio, realizados a través de máquinas para el modelado rápido
(tecnología 3D print, estereolitografía y sintetización) necesitan modelos perfectamente
cerrados y privados de errores topológicos. El formato de file más comúnmente empleado en
estos sectores como input para el proceso de trabajo es el .STL que soporta caras trianguladas
para aproximar la forma del objeto. El mismo rigor en la construcción de modelos se realizan
también en el ámbito de los análisis FEA (Finite Element Analysis) llamados “a elementos
finitos”, usados en el campo de la ingeniería para seguir simulaciones físicas.

64

<!-- p. 74 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

C. REFERENCIAS

 Apollonio, F.I. y Remondino, F., 2010. “Modellazione 3D da sensori attivi Pipeline con
laser scanner” en Benedetti, B., Gaiani, M. y Remondino, F. (ed.) Modelli Digitali 3D in
archeologia: Il caso di Pompei. Edizioni della Normale. Scuola Normale Superiore Pisa,
pp. 94-117.

 Benedetti, B., Gaiani, M. y Remondino, F. (ed.), 2010. Modelli Digitali 3D in archeologia:
Il caso di Pompei. Edizioni della Normale. Scuola Normale Superiore Pisa

 Buill, F., Núñez, M.A., Rodríguez, J.J., 2007. La fotogrametría arquitectónica. Edición
UPC. Barcelona.

 Calvo, A., 1997. Conservación y restauración. Materiales, técnicas y procedimientos. De
la A a la Z. Ediciones del Serbal. Barcelona.

 Docci, M. y Maestri, D., 1984. Il rilevamento architettonico. Storia, metodi e disegno. Ed.
Laterza. Roma

 Fantini, F., 2012a. “La modelazione digitale” en Bertocci, S., Bini, M. (ed.) Manuale di
rilievo architettonico e urbano. CittàStudi Edizioni. Novara, Italia, pp. 215-232.

 Fantini, F., 2012b. “Modelos con nivel de detalle variable realizados mediante un
levantamiento digital aplicados a la arqueología” en Revista EGA (Expresión Gráfica
Arquitectónica). Universidad Politécnica de Valencia. Valencia, pp. 306-217.

 Fantini, F., 2009. “Teorie e tecniche della rappresentazione numerica o poligonale” en
Migliari, R. (ed.) Geometria descrittiva, volume II, tecniche e applicazioni. Città Studi
edizioni-De Agostini Scuola. Novara, pp. 60-94.

 Guidi, G., Russo, M. y Beraldin, J.A., 2010. Acquisizione 3D e modellazione poligonale.
McGraw-Hill. Italia.

 Juan Vidal, F., 2012. Applicazioni del rilevamanto avanzato. "Conferencia" impartida en el
Seminario Internazionale di Museografia Premio Piranesi. Prix de Rome, realizado en la
Casa dell'Architettura di Roma. 29 de agosto.

 Juan Vidal, F., Benlloch Castellò, A. y Fantini, F., 2010. Nuevas metodologías para
divulgación del patrimonio disperso. Revista Arché. Publicación del Instituto universitario
de Restauración del Patrimonio (IRP) de la Universidad Politécnica de Valencia (UPV),
Valencia, pp. 319-324

65

<!-- p. 75 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

 Kraus, K., 1994. Fotogrammetria. Vol. 1. Teoria e applicazioni. Libreria universitaria
Levrotto & Bella. Torino.

 Kraus, K., 1997. Photogrammetry. Vol. 2. Advanced Methods and Applications. Dümmler
Verlag. Bonn.

 Mandelli, E. y Velo, U., 2011. Il modello in architettura. Cultura scientifica e
rappresentazione. Editorial Alinea. Italia.

 Manferdini, A.M. y Remondino, F., 2010. “Modellazione 3D da immagini Perperline
fotogrammetrica” en Benedetti, B., Gaiani, M. y Remondino, F. (ed.) Modelli Digitali 3D
in archeologia: Il caso di Pompei. Edizioni della Normale. Scuola Normale Superiore Pisa,
pp. 162-199.

 Martínez-Espejo Zaragoza, I., 2010. La iglesia de los desamparados de les Coves de
Vinromá. Hipótesis y restitución virtual de la bóveda de la capilla mayor. Tesina del
Máster oficial de Conservación del Patrimonio Arquitectónico de la Universidad
Politécnica de Valencia. Valencia.

 Merlo, A. y Fantini, F., 2012. “I sistemi di ottimizzazione image based per la gestione dei
modelli digitali 3D a scala urbana” en Merlo, A. (ed.) Il castello di Pietrabuona, Quaderni
di Rilievo Urbano n° 2, Edizioni ETS, Pisa, pp. 159-165.

 Migliari, R., 2009. “Geometria descrittiva. Volume II – Tecniche e applicazioni”.
CittàStudi Edizioni. Novara, Italia.

 Remondino, F., Fraser, C., 2006. “Digital camera calibration methods: considerations and
comparisons” en International Archives of Photogrammetry, Remote Sensing and Spatial
Information Sciences, Vol. XXXVI, part 5. ISPRS Commission V Symposium, Dresden,
Alemania, pp. 266-272.

 Slama, CC. (ed.), 1980. Manual of Photogrammetry. Fourth Edition. American Society of
Photogrammetry. Virginia.

 Verdiani, G., 2011. Il ritorno all’immagine. Nuove procedure image based per il Cultural
Heritage. Editore: www.lulu.com. Italia.

66

<!-- p. 76 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

1

CAPÍTULO 4. CASO DE ESTUDIO 1

Restauración virtual: El caso de una
bóveda gótica en Coves de Vinromá1

1 Mtnez-Espejo Zaragoza, I, 2010.

67

<!-- p. 77 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

A. BREVE RESEÑA HISTÓRICA

LES COVES DE VIMROMÁ2

El origen del poblamiento de les Coves de Vinromá se sitúa, a partir del 6000 a.C., en el gran
conjunto del denominado “arte rupestre levantino” del barranco de la Valltorta, declarado
Patrimonio de la Humanidad. Se encuentran cuantiosos restos de poblamientos ibéricos en el
término de les Coves: el de la Morería, el de la partida del Molí Consell y el dels Tossalets,
donde se encontró un fragmento de lápida; pero, sobre todo, según Francesc Esteve, “el más
importante quedaba en el áspero roquero de la parte vieja del pueblo” (Esteve i Gálvez, F.,
1992: 597-618).

Durante la época romana, Coves era cruzada longitudinalmente por la Vía Augusta. Se
conservan numerosos restos, entre ellos un relieve funerario hispano romano procedente del
poblado de les Fontanelles o dels Tossalets, de la ocupación que se produjo al comenzar la
época de Augusto, entre el s. II y la primera mitad del siglo III.

Tras el periodo de la ocupación musulmana, del que no se sabe nada,
Jaime I conquistó les Coves, en la segunda mitad de agosto de 1233,
convirtiéndose en un lugar de realengo, hasta el 11 de mayo de 1235,
cuando el rey le cedió los castillos de les Coves y de Culla al noble
aragonés Balasc d’Alagó. La propiedad de este castillo no permaneció
durante mucho tiempo perteneciendo a Don Balasc, ya que en el año
1240, lo vendió a la Orden de Calatrava, para poder pagar sus deudas,
según García Edo2. Sin embargo, unos años después, el 2 de junio de
1275, la propiedad del castillo volvió al apellido d’Alagó, pues los
Figura 5.01. Cruz de
calatravos cedieron, por permuta, la potestad del castillo de les Coves a Calatrava, emblema
N’Artal d’Alagó, bisnieto de Balasc. El 11 de noviembre de 1281, de la orden3
N’Artal otorgó a les Coves carta de población, (el documento que se
conoce es una copia de 1496).

En 1293 el rey Jaime II compró la Tenencia de les Coves a N'Artal por 135.000 sueldos;
pero no fue muy largo el dominio del rey, puesto que el 15 de septiembre de 1294 firmó con los
templarios el cambio de la ciudad de Tortosa por los castillos de Ares, de Olleros (Tarragona),
de Peñíscola y de les Coves. La Orden del Temple conservó la Tenencia de les Coves hasta el
año 1312, cuando desapareció. Así les Coves permaneció en poder del rey hasta el año 1319,
fecha en la que fue cedida a la Orden de Montesa, bajo el gobierno de la cual quedó, de hecho,
hasta la desamortización de Mendizábal (1836), y de derecho, hasta la II República (1931).

En el reinado de Pedro IV el Ceremonioso, la villa de les Coves intervino en la guerra de la
Unión (1347-1349), pero apoyando a los enemigos del rey y de su señor natural, lo que le costó
un grave castigo de 37000 sueldos reales.

2 Información obtenida de la página web: www.lescovesdevinroma.es (última consulta 06/09/2013)
3 Imagen obtenida de la página web: www.wikipedia.org (última consulta 06/09/2013)

68

<!-- p. 78 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

El 31 de mayo de 1421, y durante cuarenta y dos días, las Cortes de Valencia se reunieron en
les Coves para recaudar un subsidio de 22000 libras para el rey Alfonso V el Magnánimo, que
permanecía en Italia, convocadas por la reina María, su esposa.

La participación de la villa de les Coves en la
revuelta de las “Germanías” (1519-1522) no debió de
ser significativa, ya que solo trece vecinos fueron
penados.

Durante la Guerra de Sucesión (1702-1713), les
Coves, al igual que todo el maestrazgo, apoyó al
Archiduque Carles, por lo que los covarxins
intervinieron en la defensa de Sant Mateu, asediada
por los Borbón, a principios de enero de 1706. Figura 5.02. El Portalet de Coves de
Vinromá4

En la primera guerra carlista (1833-1840), entre los días 3, 4 y 5 de julio de 1835, la villa de
les Coves fue asediada por los carlistas, siendo finalmente entregada por sus defensores, que
estaban bajo las órdenes de Baptista Vidal. La tercera guerra carlista (1872-1876) asumirá en la
villa de les Coves, por su situación, uno de los escenarios naturales, dado que al capitoste xivertí
Pascual Cucala tenía un alto conocimiento de esas tierras; y además, los covarxins Pascual
Villalonga y el «Arbolero» eran sus compañeros inseparables.

La etapa que se da en les Coves entre los años 1890 y1936, fue muy positiva económica y
socialmente. En 1921 el pueblo tenía 4594 habitantes, el máximo número alcanzado, y varias
fábricas de abonos minerales, de jabón, de aguardientes y de tejas y ladrillos. Durante la Guerra
Civil, les Coves quedó en zona republicana hasta el 11 de junio de 1938, cuando los soldados
republicanos, tras 45 días de ataques por parte de las tropas franquistas, abandonaron el pueblo.
Antes había comenzado una dramática migración de la población covarxina hacia la Huerta de
Valencia. La posguerra y las grandes heladas de los años 1946 y 1956 fueron la causa de la gran
caída de les Coves. En la actualidad parece que poco a poco va recuperándose de esa situación.

4 Imagen obtenida en la página web: www.ruralcoves.com (última consulta 06/09/2013)

69

<!-- p. 79 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

LA IGLESIA VELLA O DE LOS DESAMPARADOS DE COVES DE VIMROMÁ5

Datos y evolución histórica

No existen muchas referencias documentales sobre la iglesia vieja de Les Coves. El
documento más antiguo es de diciembre de 1248 y se trata de una sentencia arbitral, dada por el
arzobispo de Tarragona entre las partes del obispado tortosino y la Orden de Calatrava, por
cuestiones de diezmos, primicias y otros derechos eclesiásticos de les Coves, Polpís y la
Salzadella6. La sentencia dispone que el obispo de Tortosa tiene que recibir la tercia parte del
diezmo y la cuarta de la primicia, siendo el resto para la Orden de Calatrava, señora de estas
tierras. Sin embargo, se piensa que se trataría de una iglesia anterior a la que con las naturales
modificaciones, se conoce.

Mateo y Llopis, al tratar de las contribuciones de la décima (es decir la décima parte de los
frutos de los beneficios eclesiásticos) correspondiendo a los años 1279 y 1280, habla de una
parroquia, al señalar que paga diecinueve sueldos y nueve dineros para tal requerimiento. Si se
compara esta cantidad con los cincuenta y cinco sueldos que se sacaban de los beneficios de la
Salzadella y los veinticinco de Albocasser, no resuelta difícil pensar que el pueblo era entonces
muy pequeño (si es que no estaba constituyéndose como tal por esas fechas) y que la iglesia, por
lo tanto, contaría, como mucho, con un rector y un solo benefactor (Mateu y Llopis, F., 1946:
494-501).

La visita pastoral que hace el obispo Paholac, en el año 1314-15, solo proporciona el nombre
del rector parroquial, un tal Domingo Porquet, y añade que la iglesia estaba provista de libros
litúrgicos, además de ofrecer otras informaciones, también
curiosas, pero que no hacen referencia directa al edificio
como tal.

Ya hasta el último tercio del siglo XIV no aparecen más
noticias. En el año 1374, Pere de Thous, mestre de
Montesa, autoriza a Pere Çarreal, para edificar una capilla
en la mencionada iglesia, que estaría puesta bajo la
advocación de San Pedro apóstol. La capilla se construiría
al lado del evangelio "es a dreta part de la eclesia en ves
tremontana..." en un callejón que bordeaba toda la iglesia
por la parte norte, hasta llega el cementerio. De este
callejón el maestro de obras podía tomar el espacio que le
hiciera falta "aytant com per a la construccio de dita
Figura 5.03. Planta actual de la
capella ne haurets mester..." iglesia7

Para realizar la capilla, se invade como se comentaba parte del callejón. Se cree que se trata
de la primera capilla (desde los pies de la iglesia) hoy existente junto al evangelio, la que tiene

5 DIAZ MANTECA, E. “Les Coves de Vinromà. Una vila del maestrat històric”. Col.lecció Universitària.
Diputació de Castelló. 2002, pp.87-94.
6 A.H.N., Secció Ordens Militars, Montesa. Manuscrit 543-C. fol. 100 v.i següents.
7 Imagen proporcionada por los arquitectos Francisco Grande Grande e Ignacio Gil Mascarell.

70

<!-- p. 80 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

el bello arco que tanto tiempo estuviera puesto al inicio de las escaleras de casa la villa. Si se
observa el actual plano de la iglesia, se puede comprobar, efectivamente, que esta capilla
sobresale de las otras, invadiendo parte de donde debió estar un primitivo callejón, que
conduciría al viejo cementerio, situado junto al actual depósito del agua.8

Esta capilla tuvo que ser la que sirvió de modelo al maestro picapedrero Bertomeu Duran
(1377-1407), el cual era de la ciudad de Tortosa, quien trabajaba en el año 1377 en la
construcción de la capilla de Sant Miquel i Sant Pere, de la iglesia parroquial de Catí, según
testimonia Joan Puig (1947: 99-100): "Donam a construir e obran a vos, Berthomeu Duran, vey
de la ciutat de Tortosa, present, una capella de pedra piquada dins e de fora, ab croes de pedra
piquada, segons que los croes de les capelles de les Coves o del loch de Onda son construyts e
he dificats…”.

En el año 1921, aparece en el Boletín de la Sociedad Castellonense de Cultura, en uno de los
suplementos escritos por algunos de los fundadores de la institución, una nota titulada "Un día
en el maestrazgo", en la cual Lluís Revest, autor del reportaje, escribía de les Coves, una noticia
de la iglesia vieja (1921:VI-VII): “Huroneamos en su viejo templo gótico, oculto bajo la
apariencia vulgarísima de una fachada frontera, sin más signo religioso que un buen retablo de
azulejos modernos, con la imagen de la Virgen, con un afiligranado pinaculillo gótico por
montera y su buena ménsula pareja, pétreas reliquias que
incitan a penetrar en aquel interesante típico, ruinoso
templo gótico. Es tan atractivo de simpatías en su sencilla y
decorosa vetustez, que su recuerdo perdura como el
encuentro con una viejecilla honorable, limpia y de noble
prestancia que aun viste galas añejas, reliquias de sus años
mozos, allí en su altar mayor nos atrae las miradas una
vieja gótica escultura de San Pedro y bajo la mesa del altar
escudriñamos una imagen de la Virgen de la Aurora, allí
Figura 5.04. Imagen de las arrumbada por su vetustez y digna de un museo de arte
reliquias pétreas que se gótico…”. La escultura de San Pedro, a la que Revest se
conservan en la iglesia refiere, se presume que sería la que presidiría la capilla que
se comentaba en precedencia. Sin embargo, se debe agregar que de las dos imágenes, la
expuesta de San Pedro y la de la Virgen de la Aurora, no queda nada.

Tampoco a los investigadores les ha interesado demasiado el tema de la vieja iglesia, aunque
las fuentes bibliográficas clásicas, señalan siempre la existencia de esta "vieja iglesia", a veces
para contraponerlo al "nuevo y amplio templo", comenzado a edificar en la segunda mitad del
siglo XVIII.

Sólo con motivo de la primera fase de restauración, empieza a hacerse por parte de los
arquitectos, Francisco Grande e Ignacio Gil Mascarell, un exhaustivo estudio arquitectónico-

8 El documento de la contratación de esta capilla se puede ver en Díaz manteca, E. y Olucha Montins, F.
(1991: 29-35).

71

<!-- p. 81 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

arqueológico, que acompaña como memoria del proyecto de intervención.9 También el
arquitecto de Patrimonio, Arturo Zaragozá Catalán (1990: 9-19), publica en el BCEM un
artículo con sus apreciaciones personales sobre tan interesante como abandonado edificio.

Evolución constructiva

Los autores del proyecto, comentado anteriormente, Francisco Grande e Ignacio Gil
Mascarell, apuntan como hipótesis que la iglesia hubiese tenido cuatro fases constructivas. Una
primera, correspondiente a los siglos XIII y XIV, en la que sitúan la edificación de las capillas
cuarta y tercera del lado del evangelio, los arcos de diafragma y los muros del presbiterio. Como
elementos que la identifican, arcos diafragmáticos, ventanas del muro del ábside, arcos formeros
y cruceros, plementerías y claves de las capillas. Una segunda fase, que abarcaría los siglos XIV
y XV, con la edificación de las capillas segunda y primera del lado del evangelio. En la tercera
fase, correspondientes a los siglos XV-XVI, se construiría la bóveda de la nave central y el
presbiterio, con idénticas molduras en las dovelas, la misma iconografía de las claves y los
arranques que se conservan. Finalmente, una cuarta fase, siglos XVII-XVIII, con la
construcción de las capillas del lado de la epístola, con una serie de elementos identificativos:
casetones, impostas corridas, bóvedas vaídas, esgrafiados, etc.10

Adosada la construcción a la muralla por su
cabecera, al realizar las obras de consolidación
aparecieron testimonios de los fundamentos del
primitivo edificio, una iglesia de las llamadas "de
reconquista", de planta rectangular, arcos formeros
y techo de madera a dos vertientes. Este tipo de
cubierta debió mantenerse, según señala A.
Zaragozá hasta la reforma del siglo XVI, cuando
fue sustituido por unas bóvedas de crucería.

De cuatro tramos, además del presbiterio y muy Figura 5.05. Sección transversal de la iglesia
posiblemente con acceso lateral, quizá porticado actual en la que se pueden observar las bóvedas
con un "nártex", tal y como aún hoy se puede ver de crucería11
la iglesia de San Cristofol de Castellnovo
(Rodríguez Culebras, R. y Olucha Montin, F., 1998: 8), sería a partir de la segunda mitad del
siglo XIV cuando se abrirían al lado del Evagelio tres capillas, cubiertas con crucería simple,
una de ellas la de Pedro Çarreal, que como se ha comentado antes estaba dedicada a San Pedro.
La portada, orientada hacia el mediodía, junto a la epístola era de factura muy sencilla, de medio
punto, con impostas y una filigrana doselete, recuerdos de la imagen gótica que debió haber.
Cuando se derribó este tramo, donde estaba la portada, ya no existía el menor rastro de dicha
figura, de la Virgen muy probablemente, y en su lugar figuraba, según permiten comprobar las

9 Agradecer a los autores del proyecto el que hayan permitido la consulta de toda la documentación y de
los materiales aparecidos durante los trabajos, así como la autorización para publicar los planos y dibujos.
10 Proyecto básico y de ejecución para la restauración de la iglesia vieja de los Desamparados de Cuevas
de Vinromá (Castellón), 2ª fase, pp. 6 i 7 de la Memoria Constructiva y de materiales.
11 Imagen proporcionada por los arquitectos que llevaron la restauración de la iglesia D. Francisco Grande
Grande e Ignacio Gil Mascarell.

72

<!-- p. 82 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

fotografías, un pequeño retablo de azulejos, relativamente moderno, con la imagen de la Virgen
de los Desamparados, la última titular de la Iglesia.

En estas capillas del lado del evangelio se conserva, aunque en precarias condiciones, parte
de la primitiva decoración mural, restaurada parcialmente por el Servicio de la Diputación
Provincial. Se trata de una ornamentación basada en dibujos de tipo geométrico y floral, en
tonos ocres, bermellones y negros. Resulta difícil determinar a qué época concreta
corresponden, aunque algunos de los motivos parecen góticos del siglo XV.

A finales del siglo XVI y principios del XVII fue
objeto de reformas: ampliación de la nave por la cabecera,
añadido de un tramo más a los pies; apertura de tres
capillas junto a la epístola y sustitución de la cubierta de
madera por bóvedas con nervaduras simples, con
terceletes. Se conservan en bastante buen estado una serie
de excelentes esgrafiados, decoración bastante frecuente
en algunas iglesias castellonenses de esta época (la de la
Sangre de Nules, sería sólo un ejemplo de otros muchos
existente en estas tierras).

De la descripción que nos hace Luis Revest, puede
deducirse que ya por los años veinte, seguramente
herencia de todo el siglo XIX, la iglesia vieja estaba
prácticamente abandonada, aunque quedaron todavía
muchos testimonios de su origen medieval. Lo que Figura 5.06. Esgrafiados conservados
quedaba de aquellos restos (imágenes, altares, etc.), en una de las capillas de la iglesia.
acabaría por desaparecer durante la guerra civil. Sólo se
salvarían, algunos de los objetos litúrgicos que en su
momento habían sido llevados a la nueva iglesia.

Durante la guerra civil el edificio sufrió
considerablemente en su estructura. Incluso se perforó
parte de la bóveda de alguna capilla para instalar nidos de
ametralladoras. Los bombardeos afectaron a la totalidad
del presbiterio y dependencias anexas, y apenas terminada
la guerra, ante lo que parecía inminente peligro de
Figura 5.07. Parte de las piezas que
derrumbarse, se tomó la opción de volar la bóveda con formaban la bóveda que cubría el
dinamita. Después, y durante muchos años, la iglesia se presbiterio situadas en el interior de
ve convertida en un auténtico vertedero de escombros, éste en el suelo.
hasta que finalmente, en 1983, le llega la hora de su
recuperación.

Hoy, aún sin terminar la última fase de rehabilitación (proyecto que incomprensiblemente
está parado), el edificio ha recuperado gran parte de su primitiva estructura convirtiéndose en un
local destinado a usos culturales.

73

<!-- p. 83 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

B. OBJETO

La restauración siempre ha generado muchos conflictos, ya que a lo largo de la historia ha
habido múltiples corrientes muy diversas y en general bastante opuestas. Un ejemplo claro de
ello fueron la “restauración en estilo” (Restauro Estilístico) y la “restauración arqueológica”,
que si bien se dieron en la misma época, las ideas eran totalmente opuestas. Sin embargo,
dejando a un lado las ideas de conservación y restauración, la normativa es clara, y las cartas
que se han ido realizando a lo largo de los años para orientar a los profesionales de la
restauración también lo son. Así se llega a la carta de Cracovia del 2000, que presenta como una
de sus ideas bases la reversibilidad.

Algo también reflejado, anteriormente, por Cesari Brandi: “El tercer principio (de la
restauración), hace referencia al futuro y prescribe que toda intervención de restauración
deber ser tal que no imposibilite, sino más bien facilite, las posibles intervenciones futuras”

Así, manteniendo este principio como una de las ideas bases, se desarrolla un proyecto que
permite experimentar y estudiar la solución de una hipotética intervención sin necesidad de
ejecutarla in situ. De este modo se conocen cada una de los riesgos y se sabe el resultado final,
antes de intervenir. El procedimiento consiste en hacer una serie de estudios previos, y partiendo
de éstos, se realizan hipótesis de reconstrucción con técnicas informáticas, que permiten
comprobar la viabilidad de la solución, sin necesidad de intervenir en el edificio.

En este caso el estudio se ocupa de una bóveda del siglo XVI, perteneciente a la iglesia de
los Desamparados de Les Coves de Vinromá: la antigua bóveda de su Capilla Mayor o
Presbiterio. Esta bóveda fue derribada durante la Guerra Civil. Sin embargo, gran parte de las
piezas que la formaban todavía se encuentran en el suelo, recuperadas de entre los escombros.
Para este estudio se busca realizar una anastilosis virtual de la bóveda, utilizando tanto métodos
tradicionales (mediciones con metro, peine de arqueólogo, croquis…) como métodos modernos
(escáner láser de dos diferentes precisiones).

En la propuesta, se plantea efectuar la anastilosis virtual, realizando una ficha exhaustiva a
cada una de las piezas que se han encontrado, para después comprobar si sería posible la
reconstrucción de la bóveda, siempre y cuando, el número de piezas conservadas fuera
suficiente. Además de este estudio con métodos tradicionales, se buscaba introducir una nueva
tecnología que aumentase la precisión en dicha investigación. Para ello, se necesitaba realizar el
escaneado de la capilla mayor, de todas las claves conservadas y de algunas dovelas.

La cantidad de piezas conservadas es muy elevada. Todas han sido identificadas, dibujadas y
medidas con métodos tradicionales. El estudio pormenorizado, utilizando la información
obtenida con el escáner láser, se ha ceñido a todas las claves, y a alguna dovela de cada uno de
los tipos de nervios identificados. Con todo esto, ha sido posible replantear digitalmente los
ángulos y las trazas de la bóveda, siguiendo los tratados y las tipologías de entonces.12

12 Para dicho estudio se ha consultado a un experto en el tema, el profesor Juan Carlos Navarro Fajardo.

74

<!-- p. 84 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

La hipótesis sobre la traza de esta bóveda evoluciona desde el estudio realizado por el
profesor Francisco Grande e Ignacio Gil, deducida con la toma de datos directa que se realizó en
el momento en que intervino en la iglesia, hasta la conclusión que se alcanza con este trabajo, al
utilizar instrumentos avanzados de mayor precisión.

Así, finalmente se presenta el proyecto, obteniéndose una solución final, generada como
fusión de esas dos ramas, el estudio y la evolución de trazas de una manera teórica y el análisis
de éstas mediante instrumentos manuales geométricos e informáticos.

C. MEDIOS, SISTEMAS Y METODOLOGÍA DE LEVANTAMIENTO

El proyecto comienza con la toma de
datos. Para realizarla se han utilizado dos
métodos diferentes. Por un lado, se ha
utilizado el método clásico, tomando datos
mediante el empleo de croquis y un
flexómetro para coger las medidas, utilizando,
en algunos casos, un peine de arqueólogo. El
segundo método, es el Scanner Láser 3D, el
cual se ha utilizado en dos tipologías distintas,
uno de mayor tamaño y menor precisión, para
la toma de datos de la iglesia en general, y
otro de menor tamaño y altísima precisión
para tomar los datos de las claves y las
dovelas. No obstante, se hablará de los dos
tipos de escáner, más adelante, en el apartado
correspondiente.

Figura 5.08. La parte azul corresponde a la zona no
restaurada, la parte rosa es la restaurada13

La iglesia vella o de los Desamparados de Coves de Vinromá, consta en la actualidad de dos
partes, una restaurada, que corresponde a 3 tramos de la nave, y otra parte que queda al aire
libre, sin restaurar y que apenas mantiene los cuatro muros que en su día formaron el presbiterio
de la magnífica iglesia gótica que fue. Este trabajo se ha realizado buscando la restauración
hipotética de la bóveda que cubre el presbiterio, lugar en el que se encuentran, además, gran
parte de las piezas que un día la formaron.

Para dicho trabajo, ha sido necesario el
traslado de las piezas al interior de la zona
restaurada, realizando de este modo su ficha

13 Imagen proporcionada por los arquitectos que llevaron la restauración de la iglesia D. Francisco Grande
e Ignacio Gil Marcarell.

75

<!-- p. 85 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

correspondiente, de cada una de ellas, y el
escaneado, de algunas de ellas, siendo en el caso
de las claves, su totalidad. Las piezas
encontradas suman un total de 212 dovelas y 7
claves, sin tener en cuenta otras, no
pertenecientes a la bóveda objeto de estudio.
Para estas labores, se han efectuado varias
campañas, ya que las piezas extendidas para su
medición, no cabían de una sola vez en la
iglesia, que a su vez tenía que compatibilizar los
actos que de vez en cuando se efectuaban en Figura 5.09. Restos del presbiterio, tras la última
ella. Además hubo que contar con la ayuda de restauración1
personal del ayuntamiento para el traslado de las
piezas.

i. Clásico: Medidas directas

La toma de datos ha constado de varias
partes. Una de ellas, ha consistido en
obtener la información necesaria mediante
el uso de flexómetro, peine de arqueólogo
y nivel, reflejada, a continuación, en
dibujos a mano alzada con sus medidas
para su posterior estudio.

Se ha realizado un croquis de cada una
de las dovelas que se han encontrado en la
iglesia, y que pertenecían a la bóveda que
es objeto de estudio, al igual que de las
claves. Para ello se ha dibujado, en el caso
de las dovelas, el alzado, una sección y la
planta (como se puede percibir en la
imagen que se muestra bajo el texto),
pudiendo de este modo, identificar todas
las medidas que se consideraban
necesarias para el estudio de éstas. Para las
claves, se han tenido que realizar algún
Figura 5.10. Croquis de la Clave 1, en la cual setrazo más, ya que con un único alzado, no
reflejan sus medidas
se obtenía la información necesaria.

76

<!-- p. 86 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

Figura 5.11. Croquis de una de las dovelas que forman la bóveda de la capilla mayor, en particular de
un formero.

ii. Láser Escáner

Para realizar los escaneados se han utilizado dos modelos de escáner diferentes. Para
escanear las dovelas y las claves se ha utilizado el láser “NextEngine Model 2020i Desktop 3D
Scanner”. Este láser tiene una precisión de 0,0001 metros; trabaja mediante una tecnología
llamada “laser stripe” que hace un barrido de la figura traspasándola al ordenador como una
nube de puntos, generando un modelo numérico descrito por polígonos y un modelo matemático
descrito por polígonos y ecuaciones. Para escanear la iglesia, los distintos tramos y el
presbiterio, se ha utilizado el escáner “HDScanStation 2”, este escáner tiene una precisión
menor, de 0,01 metros, y su forma de trabajar es mediante dos ventanas que hacen un barrido
frontal primero de -45º a 22,5º y luego uno vertical de 22,5º a 90º girando siempre 360º. Este
escáner también convierte lo escaneado en una nube de puntos. Los dos escáneres utilizados
necesitan un ordenador auxiliar para trabajar.

Se ha considerado interesante explicar las fases que se han de seguir desde que se coloca el
escáner a punto para realizar el barrido hasta que se convierte en un modelo 3D completo, como
un objeto sólido, ya que esto requiere seguir unos pasos con cierto orden. Como los pasos a
seguir son casi iguales con ambos escáneres, se van a exponer los efectuados por uno de ellos
(el escáner NextEngine) y luego brevemente se comentarán las diferencias con respecto al otro.
Las fases serán las siguientes:

77

<!-- p. 87 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

Fase 1: Escaneado in situ con escáner de triangulación.

En primer lugar, explicar que este escáner posee una
pequeña plataforma donde objetos livianos y de
pequeño tamaño se pueden poner y esta trabajaría con
el escáner girando de tal forma que se hiciesen los 360º
sin tocar el objeto. El problema surge cuando el objeto
no es tan pequeño ni tan ligero como para ponerlo en
esa plataforma. Es este el caso de las piezas que se
están estudiando. Así pues, cuando se va a escanear es Figuras 5.12 y 5.13. Escáner realizando
necesario hacer escaneados individuales, y cambiar la el barrido de una clave arriba y de una
posición del escáner y/o la pieza en modo manual. Al dovela abajo
realizar las capturas, se debe recordar mantener una
superposición alta de los escaneados, de modo que en
la fase de alineación sea posible encontrar puntos
homólogos. Se ha decidido no utilizar dianas.

Fase 2: Exportación a un programa de edición de la
nube de puntos (o de la mesh, para escáner a
Triangulación)

Para exportar la nube de puntos (o la mesh) del programa inicial a un programa de edición,
se debe tener en cuenta que no todos los formatos son compatibles con los programas que se
deberán utilizar en la edición. En general, los formatos “*ply” y “*obj”, son formatos
compatibles y que permiten preservar toda la información útil para el trabajo que se busca
acometer.

Figura 5.14. En
esta imagen se
puede observar
el menú del
programa
NextEngine, con
todos los
escaneados
realizados. En
ese momento se
están guardando
las celdas en
\*ply para poder
a continuación
abrirlo en el
programa que
gestiona la nube
de puntos
(Rapidform).

78

<!-- p. 88 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

Fase 3: Alineación de capas.

Debe explicarse que el escáner que se utiliza para tomar datos de las claves y las dovelas
cuando se coloca no se orienta, por lo que cuando se abren las celdas, en el programa de
edición, las capas tienen cada una de ellas una orientación diferente, es decir, están en un
sistema de coordenadas diferentes. Es por ello, como se explicaba en la fase de escaneado, que
las celdas deben presentar partes coincidentes. En esta fase lo que se hace es elegir puntos
homólogos entre las celdas para conseguir una alineación igual en todas ellas. Si el escaneado se
ha realizado correctamente las partes coincidentes entre celdas se verán fusionadas como una
sola formando una red de polígonos más concentrada.

Figura 5.15. En estas imágenes se puede observar la elección de los puntos homólogos para la alineación
de dos mesh.

79

<!-- p. 89 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

Figuras 5.16 y 5.17. En estas imágenes se puede observar la recolocación de dos mesh, una vez se han
elegido los puntos homólogos, y como finalmente quedan situadas en un mismo sistema de coordenadas.

Fase 4: Limpieza de elementos sobrantes.

Cuando se realizan los escaneados, no se puede evitar que, en el barrido, éste capten
elementos no pertenecientes a la pieza que se está escaneando. En esta fase, lo que se pretende
es eliminar tanto los elementos sobrantes como aquellas partes del escaneado, que si bien
forman parte de la pieza, no tienen una buena calidad y es preferible eliminarlas.

Figuras 5.18 y 5.19. En esta imagen se puede observar el elemento sobrante que es captado por el escáner
y el proceso para su eliminación.

80

<!-- p. 90 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

Cuando lo que se quiere es eliminar los bordes que no tienen la calidad óptima, se procede
de forma diferente. En este caso, la forma apropiada, o aconsejada, es la opción que permiten
algunos programas para la edición de bordes.

Figura 5.20. Edición de bordes de la mesh.

Fase 5: Alineación rigurosa

Esta fase es un proceso previo que se realiza como preparación para juntar todas las celdas
en una sola. El procedimiento consiste en elegir todas las capas y hacer una alineación total, ya
no se utilizan puntos homólogos como se hacía en la fase anterior de alineación. En este caso, el
programa solo se encarga de hacer la alineación reconociendo curvas y polígonos.

Figura
5.21.
Alineación
fina de
todas las
mesh
después del
proceso
individual
a pares.

81

<!-- p. 91 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

Fase 6: Fusión de capas en una sola

Esta fase, es sin duda una de las más importantes, ya que una vez que se efectúa, las capas no
se podrán modificar independientemente, todas las capas serán una sola, y las modificaciones se
harán al conjunto entero.

Figuras 5.22, 5.23 y 5.24. En estas imágenes se puede observar el proceso que se va realizando hasta que
se han unido todas las capas o celdas en una sola. Este proceso puede tardar minutos.

Fase 7: Eliminación de los errores topológicos

Tras la fase de fusión, pueden presentarse una serie de errores como: polígonos al contrario,
algunos pares de celdas que no se ha unido del todo bien y presentan en una pequeña zona dos
capas que en principio deberían ser la misma, etc. Estos errores, en general, son fáciles de

82

<!-- p. 92 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

solucionar ya que los programas de edición de la mesh, presentan una serie de comandos que
permitirán arreglarlos.

Fase 8: Relleno de huecos

Terminadas las fases anteriores, se obtiene una figura completa, una malla de polígonos
definida en todas sus caras. Sin embargo, normalmente, quedan pequeños huecos que no se han
cubierto en los distintos escaneados o que se han eliminado por presentar errores topológicos, y
que si no son de gran tamaño se pueden cubrir para conseguir una pieza completamente cerrada
y sólida, sin presentar cambios significativos en su morfología.

Figura 5.25. En esta imagen se ven los huecos que han quedado en el modelo después de la fusión de las
celdas en una sola.

Fase 9: Secciones

Llegado a este punto, ya se tiene una figura perfectamente completa, un objeto totalmente
definido. Con esta última fase realizada, en muchos casos se puede considerar acabado el
trabajo de edición. Sin embargo, en el caso que se está estudiando es conveniente realizar una
serie de secciones que son interesantes de estudiar y que después es posible analizar
individualmente.

Una vez se tienen las secciones hechas, éstas se pueden exportar para su análisis métrico o su
estudio individual. Un formato conveniente para la exportación es *iges.

83

<!-- p. 93 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

Figura 5.26. En esta imagen se puede observar el plano realizado y como se ha utilizado para hacer una
serie de secciones verticales.

Fase 10: Orientación de la pieza

Esta fase, aunque trabajando en un programa de edición puede no parecer muy interesante,
pasa a serlo cuando la figura o partes de ella son exportadas a otros como Rhinoceros o
Autocad, donde la elección de las vistas es primordial.

Figuras 5.27 y 5.28. A la izquierda, imagen del proceso de orientación. A la derecha, la clave después de
haber seguido el proceso de orientación.

84

<!-- p. 94 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

Fase 11: Secciones horizontales para realizar la planta.

Con la clave orientada, se utiliza un plano que sea paralelo a la planta (Top) para hacer un
conjunto de secciones que permitan una total definición de la planta cuando estas secciones se
pasen a 2D.

Figura 5.29. Imagen en la que se puede observar el seccionado de la clave.

A continuación, este conjunto de secciones se exporta a un programa adecuado, por ejemplo
Rhinoceros, que permita su elaboración para convertirlo en un modelo en 2D (paralelo al plano
Top) para obtener la planta que luego formará una de las vistas de la fichas que se van a crear.

85

<!-- p. 95 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

Figuras 5.30 y 5.31. En la imagen inferior se puede observar cómo se queda la figura tras la
transformación a 2D. En la superior se mostraba el proceso.

Fase 12: Reducción de polígonos para utilizar los modelos digitales en programas de animación
3D.

Los escaneados producen archivos demasiado pesados que los programas normales de
animación 3D tienen problemas para gestionar, por eso, si se quiere trabajar en un programa de
este tipo, será necesario primero reducir el número de polígonos del modelo. Para ello, se realiza
un proceso llamado “Decimation”, que permite la reducción del número de polígonos
manteniendo la geometría dentro de un límite conocido. En general, el número de polígonos,
recomendable para los programas de animación, es entre 500000 y 800000.

Figura 5.32. Imagen de la clave en el proceso de reducción de polígonos.

86

<!-- p. 96 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

Fase 13: Render en un programa de animación 3D

Para realizar una
visualización
fotorealista del modelo
(render), se elige la
vista que se desea y
luego se deben de ir
cambiando una serie de
parámetros como la
situación de la cámara,
el color del material, la
intensidad de la luz… y
así se crea el render. Figuras 5.33 y 5.34. Renders de la clave 2

Fase 14: Obtención del eje de las claves en Rhinoceros

Para sacar el eje central de las claves, se escogen algunas secciones horizontales, de las que
se vean más correctas, ya que las claves presentan deformaciones diversas. A continuación, se
marcar puntos incluidos en estas secciones (figura 5.35 y 5.36). Utilizando estos puntos se
realizan círculos idealizados, que serán una aproximación de los círculos originales que definen
las secciones (figura 5.37). Uniendo el centro de los círculos idealizados se obtiene el eje central
(figura 5.38).

Figura 5.35. Imagen del proceso para encontrar el eje vertical de cada una de las claves.

87

<!-- p. 97 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

Figuras 5.36, 5.37 y 5.38. Imágenes del proceso para encontrar el eje vertical de cada una de las claves.

Este eje será útil para obtener las secciones verticales, que se utilizan para obtener los
ángulos de inclinación, de las caras donde inciden los nervios, con respecto a la base.

Figuras 5.39 y 5.40. Exportación del eje para obtener las secciones.

Escáner HD ScanStation diferencias:

La nube de puntos obtenida con este escáner, se exporta al programa “Cyclone” para su
gestión (se usa este programa por ser el recomendado y suministrado por la marca del escáner,
Leica). En él, se alinean los escaneados y cuando se tienen todas las nubes de puntos en el
mismo sistema de coordenadas se exporta al programa de edición.

En el programa de edición (por ejemplo, Inus Technology Rapidform XOR3 o Geomagic
Studio 10) se realiza una fase previa no realizada en el caso del escáner a triangulación. Ésta
consiste en algunos ajustes de las nubes, que permiten, a continuación, generar una mesh de
mayor calidad. Dichos ajustes son: la eliminación de los puntos dispersos, la eliminación de los
puntos que se han separado demasiado del plano y la suavización de los puntos (para que los
puntos se conviertan en una malla más regular).

88

<!-- p. 98 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

Figura 5.41. Imagen de la conversión de la nube de puntos a malla poligonal.

Efectuada esta fase, se realiza la fusión de las nubes en una única, para, posteriormente,
convertir dicha nube en una superficie, o mesh. Debe comentarse que realmente este orden
puede ser invertido, realizando, primero, la conversión en mesh y, en una segunda fase, fusionar
las celdas, como en el caso de las capturas obtenidas con el escáner a triangulación. Existe, en
realidad, también la opción de efectuar en una misma fase y con un solo comando las dos
acciones (conversión en malla y fusión de las diferentes nubes). Estas opciones quedan a
elección del usuario.

Figura 5.42. Imagen
de la mesh
resultante después
de las fases de
conversión y fusión.

89

<!-- p. 99 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

Terminadas estas fases, se pueden hacer cualquiera de las fases que se han realizado con las
tomas del otro escáner (las del NextEngine).

Figura 5.43.
Imagen de
las
secciones
horizontales
para obtener
la planta de
la iglesia.

Figura 5.44.
Imagen del
modelo en
el momento
del estudio
de los radios
de la bóveda
a partir de
los restos
encontrados
en los
muros.

90

<!-- p. 100 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

D. TRATAMIENTO DE LOS DATOS

A partir de los croquis, tomados in situ, se han podido realizar análisis que han arrojado una
serie de conclusiones. Una de ellas ratifica algunas hipótesis de Francisco Grande e Ignacio Gil,
que confirman que hay tres tipos diferentes de dovelas, y unas claves que permiten definir la
planta de la bóveda.

De los tres tipos de dovelas, dos presentan un modelado o sección transversal similar, cuya
única variación reside en las dimensiones, y la otra tiene una sección totalmente diferente a las
anteriores. A las que tienen una forma similar se las ha nombrado como P y G, siendo P, las de
menor tamaño y G la de mayor. Las últimas han sido nombradas como L. Siguiendo este
estudio de dimensiones, y por lo tanto esta clasificación, se ha realizado un recuento, que nos
hace afirmar que hay 110 dovelas “P”, 42 dovelas “G” y 60 dovelas “L”.

Por otra parte, se puede afirmar que las
piezas “L”, son aquellas que en su momento
formaban los arcos formeros de la bóveda,
ya que observando los restos de ésta
adheridos al muro, coinciden en forma y
tamaño. También comprobando las medidas
de las piezas G y P, su correspondencia con
las claves, y la hipótesis formada sobre la
planta de ésta, se puede deducir que las
piezas “G” formaban los dos arcos cruceros,
y las piezas “P” formaban el resto de los Figura 5.45. En esta imagen se pueden observar los
arcos, tanto los terceletes como las restos del arco formero que quedan adheridos al muro
ligaduras.

Como se comentaba, con éstas medidas también se han podido estudiar los ángulos de
incidencia de las claves, y las dimensiones del presbiterio, por lo que como se verá en el
siguiente apartado, se ha podido deducir las trazas de la bóveda que luego darán a la
construcción virtual de la bóveda.

Figuras 5.46 y 5.47.
A la izquierda Clave
7, con las medidas
de los ángulos de
incidencia. A la
derecha hipótesis de
la planta de la
bóveda de la capilla
mayor o presbiterio.

91

<!-- p. 101 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

Estudio de trazas:

Para realizar el estudio de las trazas
se ha partido de diferentes datos. Por un
lado se tienen siete claves, de las
supuestamente nueve que debería
haber, con toda la información que
éstas aportan, y por otro lado, se tienen
el tipo de nervios y la forma que tienen
las claves en donde incidirían estos.

Partiendo de esta información se va
a proceder a plantear las trazas
compatibles, las condiciones físico
geométricas, las posibilidades de las
hipótesis ya realizadas… siempre
comparándolo todo con la tradición, Figura 5.48. Hipótesis de la planta trazada por el arquitecto
con los tratados que explican cómo se Francisco Grande e Ignacio Gil Mascarell, restaurador de
trabajaba entonces y con el trazado de parte de esta iglesia.14
las capillas de la misma época y
tipología.

Fichas:

Para la realización de las fichas se ha buscado introducir de forma esquemática y clara la
información que aporta cada una de las piezas. Por ello, se ha dividido ésta de tal forma que en
una parte aparezcan las vistas (planta, alzado/s y sección), en otra una axonometría de la pieza,
un dibujo general que contenga la planta y la sección general de la bóveda y por último, algunas
anotaciones si son necesarias de la pieza.

La parte de planta, alzado/s y sección se ha ejecutado sacando esta información directamente
de la toma de datos del escáner láser. Como se ha explicado anteriormente, se han marcado
planos que contuviesen cada uno de los alzados (en el caso de las claves), la planta y la sección.
Utilizando visualizaciones foto-realistas (renders) que permitiesen dar riqueza a las fichas,
mostrando imágenes en 3D de la pieza original.

La axonometría se ha obtenido captando una imagen directamente del Rapidform, ya que en
este se muestra la pieza tal y como es. La planta y sección general se han diseñado a partir de la
hipótesis que al final se ha considerado como cierta, marcando la posición de la pieza que se
considera como la correcta.

14 Imagen proporcionada por los arquitectos D. Francisco Grande Grande e Ignacio Gil Marcarell

92

<!-- p. 102 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

Por último, se ha considerado interesante introducir una serie de anotaciones que expliquen
los pequeños detalles que tiene esa pieza que no tienen las demás.

Figuras 5.49 y 5.50. En la imagen de arriba se puede observar una de las fichas de las claves, en la de
abajo una de las fichas de las dovelas.

93

<!-- p. 103 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

E. ANÁLISIS

HIPÓTESIS DE LA PLANTA DE LA BÓVEDA DE FRANCISCO GRANDE GRANDE E

IGNACIO GIL MASCARELL

La hipótesis del trazado de la planta formulada por de Francisco Grande e Ignacio Gil
Mascarell surge a partir del estudio de las claves que encontraron cuando realizaron la
restauración de la iglesia, y de los arranques de la bóveda que todavía quedan en los muros que
la sustentaban. Este será nuestro dibujo de partida, revisado a la luz de los métodos avanzados
de documentación utilizados en este estudio y de las conclusiones de algunas tesis más recientes
en investigaciones especializadas sobre bóvedas de este tipo, como la de Juan Carlos Navarro
Fajardo (Navarro Fajardo, Juan C., 2006).

Así la planta y la sección facilitadas
por Francisco Grande, se considerarán
como el primer acercamiento a la
bóveda que es objeto de estudio.
Partiremos de dos datos dados por él: B

\- Que los cruceros son arcos de
medio punto,

\- Que la altura de los arcos A y B
Figuras 5.51 y 5.52. Imágenes del trazado de la planta es la misma, como se explicará a
según la hipótesis de Francisco Grande e Ignacio Gil.
continuación.

En primer lugar, se ha dibujado el círculo que circunscribe la planta de la bóveda. A
continuación, se ha utilizado la altura de los arcos formeros, tomándola directamente del muro,
ya que quedan todavía empotradas algunas de las dovelas que forman estos arcos, entre ellas las
dos que marcan la clave. Utilizando esta altura, se ha podido comprobar que el arco A, cumple
la regla de arco apuntado con centro en 2/3 de su proyección. Con esta altura se ha obtenido
también el arco B. Ya que sin más datos de este arco formero que su altura en la clave y su luz,
se ha trazado el resto del nervio basándose en una correspondencia de alturas, utilizando la
extrusión del arco A con el B en su cruce.

Observando la sección trazada por Grande y Gil (imagen al final de la explicación), se puede
comprobar que la altura de las claves del anillo de nervios (el rombo), es igual en todas ellas.
Partiendo de esa cota, de la altura de la clave polar y el arranque del arco C, se obtienen las
trazas de éste.

Para obtener el arco D, se utilizará la planta y la sección, poniéndolas en la situación correcta
para que tenga concordancia. Se unirá la clave 3 dibujada en planta, con la clave 3 de la sección
cortando de este modo al arco D (realmente a su simétrico), en la planta y en la sección. Se
utilizará la altura de la sección para tener un punto, la altura del rombo antes explicada será otro
punto y el tercer punto será el arranque.

94

<!-- p. 104 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

Se conseguirán las trazas del arco E, mediante un procedimiento parecido al anterior, se
elegirá el punto medio del arco en planta y se proyectará a la sección para sacar la altura. De
este modo, se obtienen los tres puntos necesarios.

Por último el arco F, no sería un arco, sino una recta ya que como se ha comentado, y se
puede observar en la sección, la altura de las claves en el rombo es la misma.

Figura 5.53. En
esta imagen se
pueden observar
todas las alturas
obtenidas a partir
de la planta y la
sección, además de
la comprobación de
la altura del
formero.

95

<!-- p. 105 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

TRAZAS DE LA BÓVEDA DE ESTRELLA (JC. NAVARRO FAJARDO)

El profesor Navarro Fajardo, sostiene algunos de
los principios fundamentales del trazado de la bóveda
estrellada, según los expertos medievales, basándose
en su geometría. En primer lugar, y teniendo en cuenta
la fecha de su trazado, ha considerado casi con total
seguridad que se partiría de la planta inscrita en un
círculo. Explica que para el trazado de los terceletes se
utilizaban normalmente dos opciones. Una que el
tercelete que sale de una esquina, la línea que lo
describe, concluya en la pared frontal del rectángulo,
en su punto medio. La otra sería similar pero en vez de
ser en el punto medio del rectángulo sería en el del
círculo.
Figura 5.54. Trazas para la búsqueda de los
terceletes15
Comprobando la planta realizada por Grande
y Gil, parecía que ninguna de las dos
alternativas encajaba, pero quedaba claro que la
del rectángulo era la que más lejos quedaba. Se
optó por continuar con la hipótesis del círculo a
ver a qué punto se llegaba. De modo que se
trazaron todos los terceletes con ésta hipótesis.

Tras esto se pasa a dibujar los arcos cruceros,
que continuando con la información sacada de
los tratados medievales y coincidiendo con la
hipótesis de Francisco Grande, se suponen de
medio punto. A continuación, se trazan las
ligaduras uniendo los encuentros entre
terceletes.
Figuras 5.55, 5.56, 5.57 y 5.58. Pasos para el
trazado de la planta siguiendo los tratados
medievales.

Con el trazado de las ligaduras queda la planta completamente
trazada, como se puede observar en la imagen de la derecha.
Teniendo la planta delineada, el siguiente paso sería comprobar que
sus ángulos coinciden. Pero antes se va a tantear el trazado de los
arcos que constituyen la bóveda, suponiendo, según la hipótesis de
Navarro Fajardo, que la bóveda está inscrita en una esfera.

Figura 5.59. Planta final

15 Imagen trazada a partir de los dibujos realizados a mano por JC. Navarro para la explicación

96

<!-- p. 106 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

En primer lugar, se dibujan los arcos crucero que son arcos de medio punto, por lo que
simplemente al inscribir la planta en un círculo, ya quedan trazados, no obstante en la imagen
siguiente (figura 5.60) se puede observar el arco abatido para mayor claridad. Lo siguiente sería
trazar los arcos formeros (figura 5.60). Para el trazado de éstos, y comprobando además en la
iglesia que se trata de arcos apuntados, se trazan con la regla del centro situado a dos tercios de
la planta. El problema es que al no ser una planta cuadrada, si está inscrita en una esfera, los dos
lados encontrados no podrán cumplir ambos esta regla. Así que como ya se comprobó en su
momento, que era el lado menor del rectángulo el que cumplía con la regla, el otro se trazará
cumpliendo con la altura del menor. El resto de los arcos se obtendrán igual que los arcos
cruceros, abatiendo el punto intersección de la línea prolongación del arco con la circunferencia
y el punto donde termina el arco en sí. De este modo se obtienen los arcos.

Figura 5.60. Trazado de los
arcos formeros.

97

<!-- p. 107 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

Figura 5.61. Primera
hipótesis del trazado de los
arcos de tercelete del lado
menor de la planta
rectangular.

Figura 5.62. Trazado de los arcos
crucero.

98

<!-- p. 108 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

Se pueden observar que aparecen dos trazados diferentes para el mismo arco (figura 5.61 y
5.64). Resulta que podrían plantearse dos hipótesis diferentes, que la altura de las claves de
terceletes sea la misma como ocurre con los arcos formeros o que simplemente sigan la esfera.
La primera se trazaría según se muestra en la imagen superior (figura 5.61) y la segunda
hipótesis se refleja en la imagen inferior (figura 5.64).

Figura 5.63. Trazado de los arcos de
tercelete del lado mayor de la planta
rectangular

Figura 5.64. Segunda hipótesis del
trazado de los arcos de tercelete del
lado menor de la planta rectangular.

99

<!-- p. 109 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

ANÁLISIS DE LA BÓVEDA

Con toda la información obtenida hasta ahora (trazas, planta, ángulos de incidencia en las
claves encontradas, restos presentes en los muros…) se planteaban dos hipótesis, y de ellas
surgirá una tercera que se convertirá en la definitiva. La primera sería, como comentaba Navarro
Fajardo, que fuese un casquete de esfera. La otra era que fuese un rombo central esférico con
riñones en definición. La tercera se explicará en la resolución.

Casquete de esfera:

Si se considera que la bóveda que cubría la capilla
mayor de la iglesia de Los Desamparados es un
casquete esférico debería cumplir varios requisitos.
Uno, que en la zona de los arranques la plementería
fuese curva hacia el exterior, quedando el nervio
central (crucero) a la misma altura que los de tercelete
o por detrás de éstos, o sea, más pegados a la esquina
que forma el cruce de los dos muros que sostenían la
bóveda. Por otra parte, debería cumplir que la altura
de los arcos formeros no podría ser similar, ya que la
esfera está inscrita en un rectángulo y no en un Figura 5.65. En esta imagen se puede
cuadrado, además de que dichos arcos deberían ser de observar los arranques escaneados,
medio punto. Por último, las claves debería presentar mostrándose más saliente el nervio central
en el lugar donde acometen los nervios, diferentes alturas en la incidencia del nervio o que éstas
se situasen inclinadas. Basándose en estas afirmaciones, se puede decir que la bóveda que se
está estudiando no es un casquete de esfera, ya que con los restos encontrados en los muros, se
comprueba que la altura de los arcos formeros contiguos es similar o cercana. Además, el
ángulo de incidencia de los nervios en la clave presenta la misma altura en todos ellos.

Rombo central esférico con riñones en definición:

Si este fuese el caso, la plementería no tendría
que formar una curvatura hacia el exterior, podría
ser hacia el interior, como en principio parece y que
más tarde, con los escaneados, se ha confirmado.
La altura de las claves de terceletes podría ser igual
o diferente a la de las claves de los formeros,
siendo por tanto el rombo central esférico y el resto
superficies regladas que seguirían a los nervios. La
condición que se mantendría, sería la de la
variación de los ángulos y alturas de incidencia de
Figura 5.66. En esta imagen se puedelos nervios en las claves. Con estas afirmaciones se
observar como la clave de tercelete no
ha decidido partir de esta hipótesis, porque parece
encaja correctamente, ya que aunque dos
cumplir con todos los condicionantes, cumple con nervios la acometen perfectamente, los otros
la planta, los arcos cruceros se suponen de medio dos no desembocan en los puntos

100

<!-- p. 110 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

adecuados.

punto, y la altura de los arcos formeros,
obtenida a través de los datos adquiridos con
el escáner láser, es bastante cercana… El
problema surge en la última comprobación,
con el 3D montado, con todos los arcos
dibujados, al introducir las claves escaneadas
en 3D, los ángulos coinciden en horizontal,
pero en vertical no, y si se inclinan las claves
para seguir la dirección de incidencia de dos
arcos, los otros dos es imposible hacerlos
coincidir, siendo por tanto esta hipótesis Figura 5.67. En esta imagen se puede observar
también incorrecta. Ha de comentarse que sí como la clave polar queda perfectamente
colocadahay una clave que queda bien encajada, la
clave polar.

F. MODELOS OBTENIDOS (Solución geométrica a partir del análisis)16

Tras analizar en profundidad
varias hipótesis, utilizando
diferentes variables, se llega a la
que se considera la hipótesis
final. Para ello se han estudiado
trazados en tratados de cantería
(Vandelvira, Padre Tosca,
Hernán Ruiz El Joven…),
hipótesis hechas sobre esta
bóveda y, por supuesto, la toma
de datos realizada in situ, tanto Figura 5.68. En esta imagen se puede observar los ejes verticales
con instrumentos tradicionales de las claves y la zona de la bóveda casi plana.
como con instrumentos avanzados. Así se obtienen datos como han sido los ángulos de las
claves y con ello la planta, como se verá a continuación, la forma de algunos arcos, a partir del
escaneado de los arranques, las dimensiones de la capilla mayor, de las dovelas, las claves…
Para llegar a la solución final han sido precisos una serie de pasos.

16 Palacios Gonzalo, José C., 2005. “La geometría de la bóveda de crucería española del XVI”.
Conferencia leída en el III Seminario sobre bóvedas impartido dentro del Máster de Restauración de la
Universidad Politécnica de Valencia.

101

<!-- p. 111 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

El primer paso, aunque realmente se hacen
muchas cosas a la vez, fue estudiar los trazados
según los tratados, las dimensiones de la
bóveda, la hipótesis proporcionada por Grande y
Gil y, por supuesto, la pauta que presentaba la
iglesia en el resto de las capillas y en la nave
central. Viendo la iglesia escaneada, se observan
detalles que en un principio, no habrían sido
observables, como son: la falta de simetría de
las bóvedas, que la zona central de la bóveda
que hay entre terceletes es casi plana, que los
ejes de las claves son verticales… Todo esto se
puede observar al poder estudiar directamente el
3D obtenido del escaneado.

El segundo paso sería sacar la planta. Para
ello se ha escogido la sección de la iglesia a la
Figura 5.69. En esta imagen se puede ver la
altura de los arranques, para obtener la planta iglesia seccionada hacia arriba a una altura de
exacta en la que se montaría la bóveda. 4,082 metros, que es la altura donde comienzan
las jarjas.

En esta planta se han dibujado los arranques para delinear las trazas representando los arcos
por su intradós, ya que era la forma de diseñar que utilizaban los canteros medievales.

Debe tenerse en cuenta, que esta investigación es empírica y no teórica, por lo que
prepondera el uso de las claves conservadas para llegar a la planta definitiva. Por ello, aunque se
estudiaron las soluciones difundidas en los tratados, primó la condición elemental de que los
ángulos de las claves coincidieran con los ángulos de la planta.

Los pasos, según nuestra hipótesis, para llegar al trazado real de la planta son los siguientes:

A. Determinación de la situación de la clave polar (central), en la intersección de las dos
diagonales.

B. Trazado de dos círculos inscritos en el diámetro de la circunferencia circunscrita paralelo al
lado mayor, tangentes entre sí en la clave polar.

C. Al unir las esquinas con el centro de estos círculos se obtienen las claves de terceletes de los
lados menores.

D. A continuación, se divide la mitad del semieje paralelo al lado menor del rectángulo en tres
partes iguales. Así a un tercio de la planta, se obtienen las claves de terceletes de los lados
mayores.

E. Uniendo estas claves a las esquinas se trazan los nervios terceletes de los lados mayores.

102

<!-- p. 112 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

F. Por último, se unen las claves de terceletes formando un rombo, donde interceptan con los
nervios diagonales, surgen las últimas claves, que son claves decorativas.

G. De este modo se obtiene el trazado completo de la planta, y los ángulos de incidencia de los
nervios en las claves coincidentes con los que presentan las claves conservadas, pudiéndose
disponer cada una de ellas en la que se supone su situación correcta.

Figura 5.70. Pasos para el trazado de la planta según la hipótesis final

103

<!-- p. 113 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

Con la planta ya trazada, el siguiente paso, sería el trazado de cada uno de los arcos en
elevación. En primer lugar comentar que estudiando el alzado del muro de la capilla mayor, en
el que se encuentra el arco diafragma, se puede observar, que este presenta un radio de 5,41
metros mientras que las huellas del arco formero que quedan en este muro reflejan un radio de
5,50 metros, dimensiones muy similares que permiten sospechar la presumible pretensión
original de aproximarlos. En el caso de los formeros de los lados menores del rectángulo, al no
poder interpretar las huellas en los muros con seguridad, ya que no son apreciables entre los
restos conservados, se han trazado utilizando el mismo radio (5,50) y centro a un tercio como se
realiza en los formeros de los lados mayores.

Por otra parte, realizando diferentes secciones por los arranques, en el 3D obtenido con el
escáner láser, se observa que el radio del resto de los arcos (cruceros y terceletes) pudiera ser
aproximadamente el mismo, a excepción de las claves de terceletes de los lados de mayor
dimensión, donde el radio que mejor concuerda es aproximadamente la media entre el radio
5,50 y 6,00.

Figuras 5.71. Estudio de los radios a partir de las huellas que quedan en el muro.

104

<!-- p. 114 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

Figura 5.72. Planta
de la iglesia,
dibujada a partir de
una sección
horizontal del
modelo digital
obtenido con el
escáner láser.

Figura 5.73. Sección KK’. Medida en cm.

105

<!-- p. 115 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

Figura 5.74.
Sección HH’.
Medida en cm.

Figura 5.75.
Sección II’.
Medida en cm.17

17 Se puede observar en las secciones un radio similar de los diferentes arcos.

106

<!-- p. 116 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

Figura 5.76. Sección
LL’. Medidas en cm.

Al comprobar los escaneados, en general, también se han encontrado otros datos
interesantes. Al buscar el radio se descubre que los centros de los arcos no se encuentran
contenidos en el plano de los arranques sino que están situados en un plano inferior. Así se
puede decir que los arcos cruceros finalmente no son arcos de medio punto sino que son arcos
rebajados.

Con estas comprobaciones se podría considerar cerrada la hipótesis de trazado de los arcos,
sin embargo, cuando se dibuja el 3D de la bóveda, montando virtualmente las piezas
conservadas en su lugar original, se descubren algunos inconvenientes, que al comprobar el
resto de la iglesia se comprenden. El problema es que aunque las claves coinciden
perfectamente en ángulos
horizontalmente,
verticalmente no es así. Esto
se debe a que a partir de la
ligadura, o sea de las claves,
los arcos mantienen el radio
pero no la trayectoria, que
resulta ligeramente
desplazada. Así que las claves
que se encuentran en los
cruceros, que en principio se
consideraban decorativas,
acaban cumpliendo una
función de encuentro entre Figura 5.77. Imagen del arco crucero en la que se observa que la
trayectorias. clave hacia el lado derecho no coincide con el arco

107

<!-- p. 117 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

Figura 5.78 y 5.79. En la imagen de la izquierda se observa el ámbito en el que se debe encontrar el arco
según la tangente sacada a partir de la clave, y la zona entre la que estará la clave polar. En la derecha se
ve la clave central situada con el arco correctamente situado y con una altura similar a la del resto de los
tramos de la nave central.

108

<!-- p. 118 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

Según la hipótesis hecha, se considera que el motivo de esta búsqueda de bajar la altura de la
capilla mayor pudo ser conseguir una altura similar al resto de la nave en la zona central,
probablemente para conseguir una cubierta plana (terraza o azotea) en toda la iglesia, como era
costumbre en la zona. Así que finalmente se llega a la conclusión de que se plantearon como
condicionantes de partida cuando construyeron la bóveda, que cumpliesen dos condicionantes:
partiendo de las dimensiones y la geometría sensiblemente rectangular en planta del espacio
existente, que la altura fuese en el punto más alto igual a la altura del resto de los tramos de la
nave principal en la parte central.

Esta hipótesis es un
resumen y, a su vez, el
producto de diversas
hipótesis y pruebas
diferentes. Es un
conjunto de pasajes
lógicos a los que se
han llegado, haciendo
una serie de pasos
iterativos de lo general
a lo particular y
viceversa. Un ejemplo
de ello, ha sido la
observación de Figura 5.80. En esta imagen se observa la hipótesis de Grande y Gil de un
diferentes bóvedas que casquete esférico, comprobándose que la altura es diferente con respecto al
nos habrían hecho resto de la nave.

concluir que los arcos tenían todos el mismo radio, porque se ha visto que en la mayoría de los
casos se cumple que cuando los formeros son apuntados, todos los arcos se realizan con el
mismo radio, mientras que si los formeros son de medio punto normalmente corresponde a un
casquete esférico.

Figura 5.81. En esta imagen se observa una altura prácticamente igual a lo largo de la iglesia

109

<!-- p. 119 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

Comentar por último que la clave dos, aunque horizontalmente cumple con los ángulos, se
ha desechado como perteneciente a esta bóveda ya que la forma de la dovela de incidencia se
presenta inclinada con respecto al eje vertical, y además presenta en sus caras la incidencia de
tres dovelas “P” y una “G”, siendo sus ángulos para encajar como una de las claves de los arcos
cruceros, por lo que tendrían que ser dos “P” y dos “G”.

Tras este análisis se pueden resumir una serie de afirmaciones:

 Se trata de una bóveda de crucería estrellada de rampante curvo que cubre un espacio de
planta rectangular ligeramente trapezoidal, siendo sus lados menores de 7,79 y 7,80 metros,
sus lados mayores de 9,33 y 9,49 metros y sus diagonales 12,31 y 12,11 metros. Los
arranques de los arcos de la bóveda están situados a 4,082 metros del suelo, y el intradós de
la clave polar a 9,42 metros.

 La bóveda contaba con 9 claves sustentantes (una central y ocho secundarias), cuatro arcos
formeros y 8 nervios salientes de terceletes (dos de cada arranque). La bóveda presenta una
ligadura en rombo cuyos vértices son las claves de terceletes (cuatro), presentando en la
intersección de la ligadura con los arcos cruceros otras claves, las cuatro restantes.

 Las dovelas documentadas de los nervios de la bóveda que cubría la capilla mayor
encontradas en el suelo, recuperadas de entre los escombros, cuyo inventariado aparece en
las fichas realizadas al efecto, son 212 piezas, con la siguiente denominación P (110 piezas),
L (60 piezas) y G (42 piezas). Las dovelas del tipo P correspondían a los terceletes y a la
ligadura, las L a los formeros y las G a los nervios cruceros. Se localizan en un principio,
siete de las nueve claves que integraban la bóveda, aunque al estudiar más detenidamente se
observa que una de ellas no pertenece a esta bóveda porque presenta en los nervios de
intersección 3P y 1G, cuando entre las claves que integrantes de la bóveda solo pueden ser
de la tipología 4P (si son de terceletes, por ser intersección entre nervios de terceletes y
ligadura) o 2P y 2G (si son las pertenecientes a la intersección entre cruceros y ligadura).
Además, esta clave presenta en una de estas P inclinada, no teniendo un eje vertical como en
el resto de las claves.

 La clave polar, es la única de las claves encontradas que recibe en todos sus lados nervios
tipo G, por lo que se ha podido deducir que solo los nervios crucero tenían este tipo de
dovela.

 De las ocho claves restantes, se observaban dos tipos de claves, las que presentan los
arranques encontrados dos a dos (y que como se comentaba tienen 2P y 2G), que
corresponden a claves que se sitúan en la intersección entre los arcos crucero y la ligadura, y
las que presentan un ángulo en horizontal mucho mayor que el resto, pertenecientes a claves
de terceletes (todos los nervios son P). De éstas se ha determinado su curvatura y los ángulos
entre ellos para poder situarlas espacialmente.

 Los ángulos entre los nervios que llegan a las claves y los ángulos del nervio con respecto al
eje vertical de la clave se han podido obtener a partir de los datos tomados. No así pero no

110

<!-- p. 120 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

los radios de curvatura de las dovelas, ya que su desgaste y escasa flecha no permiten
obtener resultados fiables. También se extraen datos de los arranques, pero el deterioro que
éstos presentan no permite la obtención de datos que nos ratifiquen con una seguridad
absoluta que los radios son correctos.

 De cada arranque (jarja) partían dos arcos formeros, uno diagonal y dos terceletes. Los
arranques escaneados han permitido determinar aproximadamente el radio de cada uno de
los arcos que conforman la bóveda. Con estos datos, se deduce que la situación del centro de
los radios no se encuentra a la altura de los arranques sino en planos más bajos. Quedando
los centros de los formeros en un plano y los de los cruceros y los de terceletes en otro,
aunque esta precisión que ahora se puede estudiar milimétricamente, presentan en el caso de
los centros pequeñas desviaciones. El plano en el que se sitúan los centros de los arcos
formeros está más cercano al suelo que el del resto de los arcos, pero ambos están por debajo
del plano de los arranques.

 Al no existir simetría en la bóveda, los arcos formeros no son iguales, sin embargo, todos
tienen, según nuestra hipótesis, el mismo radio, cumple que su centro está situado a un tercio
del vértice y son apuntados.

 En la hipótesis final se descarta el casquete esférico por deducirse una bóveda menos esbelta,
obtenida por la información de las claves y de los arranques. Presentando como
características ratificables, que las claves presentan un eje vertical situado
perpendicularmente al suelo y paralelo a los muros (este detalle se encuentra además en el
resto de la iglesia, siguiendo por tanto un modelo en toda ella), que los ángulos de las claves
no permiten colocarse para formar parte de un casquete esférico, y que los arcos formeros
son apuntados. Se presentan también datos aproximados, que forman parte de la hipótesis
defendida, como son que los radios que presenta la bóveda se mueven entre 5,50 y 6,00, que
el radio de los formeros del lado menor es igual al del lado mayor, porque si bien, con las
huellas del arco formero del lado mayor se puede obtener claramente este radio, en el lado
menor las huellas son menos claras, pero en cualquier caso compatibles con esta hipótesis.

G. RESULTADOS

Tras realizar todos los pasos comentados en el apartado anterior, el último paso ha sido la
construcción virtual de la bóveda. Para el diseño de esta bóveda han sido necesarios utilizar
varios programas, porque si bien el “Rhinoceros” permitía un buen diseño geométrico con alta
precisión en 3D, para trabajar interactivamente el programa “Luxology Modo” era el adecuado.
Por otro lado, para el dibujo de 2D se ha utilizado el “Autocad”. Cada uno de los programas
utilizados son muy eficaces para partes específicas pero, sin embargo, ninguno reúne las
características que permitirían el uso de un único programa para realizar todo el trabajo.

111

<!-- p. 121 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

Figura 5.82. Así en esta imagen se puede observar cómo una vez trazada la planta en Autocad, se ha
insertado en “Rhinoceros” y se han trazado los arcos en 3D. También se han utilizado las secciones de las
dovelas correspondientes para dibujar correctamente los arcos (con su profundidad, altura, forma de la
moldura…) tras haberse realizado previamente un trazado con simples líneas curvas.

Una vez modelada la bóveda, se introducen las claves con poca resolución, para que no sea
un archivo muy pesado y que se pueda manejar, y se sitúan en su posición correspondiente.
Introducidas, se pasa todo al programa “Luxology Modo 501” porque como se comentaba, este
programa es más interactivo y para colocar las claves de la forma más correcta, es el mejor, y
así se obtiene el resultado final.

En las imágenes (figura 5.83 y 5.84) se puede observar el resultado final, con todas las claves
encontradas encajadas perfectamente, presentando un color diferente las claves que se han
dibujado por simetría pero que realmente no se han encontrado. Debe quedar claro en todo
momento, que es una hipótesis, que muchos datos se pueden confirmar claramente (ángulos de
las claves, verticalidad de los ejes de las claves…), pero otros han sido deducidos (algunos
radios de los arcos de la bóveda, ya que los arranques se encuentran muy deteriorados, los
planos donde se sitúan los centros de los radios de los arcos…), por falta de pruebas más claras.

112

<!-- p. 122 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

Figuras 5.83 y 5.84. En la imagen superior, axonometría de la bóveda vista desde abajo. En la
inferior, axonometría vista desde arriba. En ambas se presentan las claves que no se tienen en
diferente color al resto de la bóveda.

113

<!-- p. 123 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

H. REFERENCIAS

BIBLIOGRAFIA BÁSICA DE REFERENCIA

 Diaz Manteca, E., 2002. Les Coves de Vinromà. Una vila del maestrat històric.
Col.lecció Universitària. Diputació de Castelló. Castellón.

 Fantini, F., 2008. Il modello di stadio da Villa Adriana. Indagine su un progetto
incompiuto. Università degli Studi di Firenze. Florencia.

 Mtnez-Espejo Zaragoza, I., 2010. La Iglesia de los Desamparados de Les Coves de
Vinromá. Hipótesis y restitución virtual de la bóveda de la capilla mayor. Tesina del
Máster Oficial de Conservación del Patrimonio de la Universidad Politécnica de
Valencia dirigida por Francisco Juan Vidal. Valencia.

 Navarro Fajardo, Juan C., 2006. Bóvedas de la arquitectura gótica valenciana: Traza y
montea. Publicación de la Universitat de Valencia.

 Palacios Gonzalo, José C., 2009. La cantería medieval. La construcción de la bóveda
gótica española. Editorial Munilla-Lería. Madrid.

 Palacios Gonzalo, José C., 2005. La geometría de la bóveda de crucería española del
XVI. Conferencia leída en el III Seminario sobre bóvedas impartido dentro del Máster
de Restauración de la Universidad Politécnica de Valencia. Valencia.

 Grande Grande, F. y Gil Mascarell, I. Proyecto básico y de ejecución para la
restauración de la iglesia vieja de los Desamparados de Cuevas de Vinromá
(Castellón).

BIBLIOGRAFIA CONSULTADA:

 Adembri, B., Di Tondo, S. y Fantini, F., 2010. Architecture and Decorative System of
the Teatro Marittimo at Villa Adriana: a New Integrated Approach to an
Understanding of the Build’s Original Aspect. Fusion of Cultures. Granada.

 Capilla Tamborero, E., 2007. El levantamiento arquitectónico como instrumento de
documentación, representación e investigación en espacios desaparecidos. La bóveda
de la sala capitular del monasterio de Santa María de la Valldigna (Valencia). Máster
en conservación del Patrimonio Arquitectónico UPV. Universidad Politécnica de
Valencia. Valencia.

 Departamento de Expresión Gráfica Arquitectónica de la Universidad Politécnica de
Valencia, 2005. Investigando los Bienes Arquitectónicos. Biblioteca TC.

114

<!-- p. 124 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

 Díaz manteca, E. y Olucha Montins, F., 1991. Uns documents per l’estudi de l’art al
Maestrat de Montesa. B.C.E.M. 36, pp. 29-35.

 Docci, M., Maestri, D., 1994. Manuale di rilevamento architettonico e urbano. Edizioni
Laterza. Bari.

 Esteve i Gálvez, F., 1992. “La vía romana per les Coves de Vinromà i Vilanova
d'Alcolea (Castelló)”. Estudios de arqueología ibérica y romana: homenaje a Enrique
Pla Ballester. pp. 597-618.

 Gaiani, M. (a cura di), 2005. La rappresentazione riconfigurata. Edizioni Poli.design.
Milán.

 Mateu y Llopis, F., 1946. La circulación monetaria en la diócesis de Tortosa y
Segorbe-Albarracín en el Reino de Valencia, según la décima de 1279-80. B.S.C.C.
XXII, pp. 494-501.

 Puig, J., 1947. Canteros en Catí. B.S.C.C., XXIII, pp. 99-100.

 Revest Corzo, L., 1921. Un día en el Maestrasgo. B.S.C.C., suplement al núm. XIII. pp.
VI-VII.

 Rodríguez Culebras, R. y Olucha Montin, F., 1998. Ornaments religiosos. Les Coves, p.
\8.

 Zaragoza Catalán, A., 1990 A propósito de las recientes obras de restauración de la
parroquia vieja de Coves de Vinromà. B.C.E.M., 30.

 Zaragoza Catalán, A., 2003. Una arquitectura gótica mediterránea. Consellería de
Cultura i Educació. Valencia.

PÁGINAS WEB CONSULTADAS

 “ www.lescovesdevinroma.es” (02/09/2013)

 “www.gothicmed.es” (04/08/2013)

115

<!-- p. 125 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

CAPÍTULO 5. CASO DE ESTUDIO 2

Anastilosis virtual de modelos adquiridos
mediante escáner láser: Piazza d’Oro dentro
del recinto arqueológico de Villa Adriana
(Tívoli, roma)

116

<!-- p. 126 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

A. BREVE RESEÑA HISTÓRICA

VILLA ADRIANA Y LA “PIAZZA D’ORO” 1

La “Piazza d’Oro” forma parte del complejo arquitectónico de la Villa Adriana, lugar de
retiro y de trabajo institucional del emperador Adriano. Éste creó dicho complejo, para alejarse
del Palacio del monte del Palatino, en la ciudad de Roma, ya que este le disgustaba, por su
relación con el senado que no era del todo cordial. Durante su vida hace múltiples viajes de los
que a menudo toma inspiración para las construcciones de su villa, a la que siempre volvía,
permitiendo supervisar los trabajos que se proyectaban a partir de sus ideas. En ella vivió
durante sus últimos años y gobernó su imperio. Adriano, sin embargo, no muere allí, sino en su
villa de Baiae, en Campania cerca de Nápoles.

La Villa que el emperador construyó a los pies de Tívoli puede ser considerada la reina de
las villas imperiales del mundo antiguo. El emperador Adriano, no solo la adaptó con
grandísimo arte, y distribuyó consecuentemente los edificios en relación a la necesidad de
carácter oficial y según la mayor o menor conveniencia del terreno y de la mayor
correspondencia de los edificios al uso que se deseaba darle en las varias estaciones del año,
sino que la decoró con una magnificencia y un esplendor que no tiene ninguna otra villa. Desde
hace quinientos años la Villa ha estado restituyendo vestigios, y es probable que otros muchos
estén aún entre sus ruinas.

Figura 6.01. Levantamiento topográfico de Villa Adriana, 1905 (Sapelli Ragni, M., 2010: 172).

1 Aurigemma, S. (1996: 19-20, 154-156).

117

<!-- p. 127 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

La Villa Adriana se extiende sobre una loma de la montaña, a dos millas cerca de Tívoli y a
28 kilómetros de Roma (cerca de 17 millas romanas a partir de la antigua Porta Esquilina). Al
amparo de los vientos que soplan del Norte, y protegida por el monte Ripoli y por el monte
Catillo contra los fríos punzantes que vienen del Este y del Nordeste, está abierta al influjo
benéfico de los vientos que exhalan de poniente. Hacia el Sur se extiende a sus pies la llanura
ligeramente ondulada del campo romano hasta el mar.

La loma sobre la que se extiende la Villa está limitada al Norte y al Sur por dos pequeños
valles, que recogen sus aliviaderos en dos fosos: uno al Norte llamado hoy “Fosso dell’Acqua
Ferrata” por un naciente de agua ferruginosa que sobre él descarga, y otro al Sur, más
profundo, llamado “Fosso di Risicoli”. El foso del Acqua Ferrata corre por un estrecho valle
solitario, cerrado por un lado por un alto banco de piedra toba2, que Adriano adaptó de un modo
pintoresco, haciendo precipitar sus paredes, las cuales, de color moreno-rojizo, con el borde
coronado de hierba perenne y de vigorosos árboles siempre verdes, recordaban al emperador el
valle tesálico de Tempe. Ésta es la razón por la cual los eruditos han dado al riachuelo el
nombre de Peneo. Este Peneo y el foso de Risicolo tenían, por tanto, en la antigüedad, una
portada notablemente mayor, por el volumen imponente de agua que Adriano derivada de
Aniene hasta su Villa por medio de un acueducto, con el fin de alimentar, los edificios termales,
el ninfeo y las fontanas esparcidas en gran número por el pomposo predio tiburtino. Los dos
riachuelos, se convertían en uno a poniente de la villa, el Aniene, un poco más allá del Puente
Lucano.

Sobre la loma de monte, así adaptada por Adriano, y que se eleva poco a poco hasta más de
50 metros, pasando de la cota de 62,4 metros (ingreso actual de la Villa), hasta la cota 115,6
metros (que es la cota del llamado “Tempio di Apollo all’Accademia”) están distribuidos los
edificios de la villa.

La villa estaba constituida por cuatro grupos de edificios. La “Piazza d’Oro”, junto al
“Vestibolo”, el “Ninfeo”, el “Cortile delle Biblioteche”, el “Peristilo del Palacio” y los
“Ospitali” formaban lo que se llama habitualmente el “Palazzo Imperiale”. Un segundo grupo
de edificios, con distinta orientación, estaba formado por “Rocabruna” y la “Accademia”
(también llamada, “Piccolo Palazzo” o “Palazzo minore”). En el primer grupo, o Palacio
Imperial (con vistas a Tívoli), es donde el emperador se alojaba en los meses invernales,
mientras que llegados los meses estivales prefería habitar en las edificaciones de la Academia
(con vistas al campo romano y al mar).

Además, había un tercer grupo de construcciones monumentales constituido por el “Pecile”,
la “Sala della Biblioteca” (ahora llamada “Sala dei filosofi”), el “Stadio”, y los edificios al lado
del estadio, sea a poniente (“l’edificio con tre esedre e fontana”), sea a levante (“l’edificio con

2 Piedra caliza, muy porosa y ligera, formada por la cal que llevan en disolución las aguas de ciertos
manantiales y que van depositadas en el suelo o sobre las plantas u otras cosas que hayan a su paso. En
Villa Adriana se utiliza esta piedra para realizar la mayoría de las construcciones.

118

<!-- p. 128 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

criptoportico e peschiera”). El último grupo estaba constituido por el “Canopo” y los dos
complejos de las “Terme”: las consideradas “Piccole Terme” y “Terme Grandi”.

Figura 6.02. Imagen de la
situación de la Piazza d’Oro
en la Villa Adriana, Tivoli.

La Piazza d’Oro se encuentra al Este de la Villa, situada sobre el valle Foso “dell’Acqua
Ferrata” o “Valle de Tempe”. Este grandioso complejo recibe dicho nombre por el
extraordinario número y la suntuosidad de los mármoles que se encontraron, en las
excavaciones realizadas en la segunda mitad del Setecientos, en los tiempos de Piranesi. El
vasto peristilo resulta en cada lado un doble pórtico, apoyado, en el eje mediano, sobre 18
columnas sobre los lados mayores y 12 sobre los menores. A lo largo de la pared del fondo, se
encontraban las columnas, otras semi-columnas en ladrillo revestido de estuco, de tal modo que
permitían una imitación perfecta del mármol, y del lado de la plaza central se alzaban
igualmente ligeras pilastras.

La Piazza se podía considerar un gran jardín porticado, o peristilo. Estaba constituido por
complejos mixtilíneos, que suponían los puntos fuertes del lugar: un vestíbulo con una de las
primeras bóvedas engallonada de la historia de la arquitectura; el pabellón del fondo, organizado
en torno a un ambiente con una inédita silueta cruciforme definida por una línea ininterrumpida
sinuosa cóncavo-convexa, que no se sabe con seguridad como estaba cubierta y un pabellón
lateral que presentaba, hacia un valle boscoso, un frente sinusoidal, igualmente sin precedentes
en espejo sobre una cuenca semicircular (Bozzoni, C., Franchetti Pardo, V., Ortolani, G. y
Viscogliosi, A., 2010: 329).

119

<!-- p. 129 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

Figura 6.03. Imagen de la Piazza tomada desde el lado Norte o Septentrional, en la cual se pueden ver los
restos del vestíbulo con la bóveda engallonada.

El pavimento, bajo el pórtico, se componía de placas de mármoles policromados constituido
de rombos, rectángulos y triángulos, y de una zona pavimentada a pequeñas tiras, también en
mosaicos de mármoles policromados, a base de rombos, cuadraditos y triángulos en torno a las
pilastras cuadradas. Bajo el pórtico cubierto a crucería el pavimento resultaba sin embargo, en la
parte central, de mayores rectángulos alternándose en dos sentidos, con cuadritos en las zonas
angulares, mientras en las placas estaban constituidas por 6 filas de ladrillos marmóreos.

Del lado del pórtico septentrional se encontraba el acceso a la plaza a través del “vestibolo”
(vestíbulo), que era una sala de planta octogonal, con la bóveda engallonada, comentada
anteriormente, como cubierta, con cuatro nichos semicirculares y dos rectangulares, sobre los
cuales se situaban amplias ventanas en los lados de levante y poniente, y con ocho columnas en
correspondencia de los ocho ángulos de la sala.

Sobre el otro frente menor de la “Piazza”, del lado del Sur o Meridional, se situaba la sala de
mayor representación del Palacio Imperial. Es un aula con planta de cruz griega con cuatro
lados fuertemente convexos en dirección del centro de la sala y cuatro lados inflexos hacia el
exterior de la misma sala. Sobre los lados que se curvan hacia el centro del aula, y que fueron
vaciados para recabar pequeños vanos, apoyaba una cúpula de tal audacia que se derrumbó sin

120

<!-- p. 130 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

dejar trazas, a pesar de la consistencia bien conocida del mortero de las fábricas de Villa
Adriana. En el lado cóncavo hacia el Sur, el aula comunicaba a través de un umbral compuesto
por columnas, con una grande exedra, que en cinco nichos contenía 5 estatuas que vertían agua
en tazas marmóreas.

En el medio del aula se situaba un amplio basamento que fue destinado a tener sobre él una
estatua de proporciones mayores a la realidad, quizás la estatua del emperador.

A poniente y a levante del aula mayor se situaban grandiosas salas de las cuales son
conservados muchos elementos de un entablamento marmóreo con cornisa a partes cóncavas y a
partes convexa, y con frisos en los cuales son figurados monstruos marinos, a veces cabalgantes,
a veces estimulados por héroes, y escenas de caza.

Sobre el eje mediano, en el sentido del lado mayor del cuadripórtico hay una fuente
monumental, de la cual se había constatado la existencia en las pruebas realizadas en el 1948, y
que después apareció continua.

LOS FRISOS DE CAZA DE LA “PIAZZA D’ORO”3

La Piazza d’Oro es entendida como uno de los más distinguidos monumentos de Villa
Adriana tanto por la considerable superficie que abarca, como por la originalidad de las
soluciones arquitectónicas. Su carácter peculiar es además enfatizado por el aislamiento
planimétrico con respecto al resto de las construcciones de la Villa, y además, en particular por
el desarrollo de sus volúmenes. Prueba de ellos son, el monumental vestíbulo con la bóveda a
cuñas, las exedras, el edificio sobre el lado meridional proyectado sobre la amplia corte
porticada central, que aún a día de hoy son difícilmente apreciables desde el exterior, a
excepción del ninfeo y de los ambientes largos del lado este, panorámicamente abiertos hacia el
valle

La Piazza d’Oro presentaba una rica decoración conforme a la elegancia de las arquitecturas
que la constituían. Alguna es todavía observable, como los pocos mosaicos in situ, o los resto de
opus sectile en los más raros y apreciados mármoles, además de esculturas, encontradas en
antiguas excavaciones. Tampoco se podía subestimar el arte topiario, destacado en la
investigación de E. Salza Prina Ricotti.

3 Sirano, F., (2000: 85 – 93).

121

<!-- p. 131 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

Deben evidenciarse entre esta decoración,
los frisos figurados en mármol griego con
“amorini” cazadores y procesión marítima que
adornaban los ambientes principales de los
edificios meridionales. Los fragmentos
supervivientes, se encuentran distribuidos entre
los Museos Vaticanos y Villa Adriana,
encontrados en las excavaciones renacentistas.

Años más tarde, en los años sesenta del
novecientos (Sirano, F., 2000: 85), el material se
sustrae para realizar una anastilosis, en la
mayoría de los casos, con posicionamiento de
los fragmentos arbitrario y peligroso, sobre
arquitrabes de hormigón armado.

Se distinguen, según F. Rakob, seis grupos
correspondientes a las probables colocaciones.
Figura 6.04. Anastilosis realizada en los años 60.
Según éste, las escenas de caza decoraban los
vanos adyacentes a la corte y los de procesión marítima los ábsides de las fuentes en los ángulos
de la misma y el ninfeo.

El reexaminado del material en los depósitos de Villa Adriana, conservados por la
“Soprintendenza Archeologica per il Lazio”, ha permitido acrecentar considerablemente el
número de fragmentos conocidos y de formular, preliminarmente, algunas nuevas
observaciones. Por ejemplo, la propuesta del Rakob, en el conjunto aun aceptable, preveía que
el friso del vano central fuese completamente liso, mientras que hoy es posible sugerir que ello
también previera secciones figuradas en base a un fragmento de la serie marina con figuras
sobre ambos lados.

122

<!-- p. 132 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

Figuras 6.05 y 6.06. A la izquierda la planta de la Piazza d’Oro marcando en rojo las zonas donde se
situaban los frisos de caza y a la derecha una imagen aérea de la Piazza marcando con flechas las mismas
zonas4.

En la actualidad, en desarrollo lineal de elementos superficiales, incluidos en los Museos
Vaticanos y en el Pecile, se pueden medir 27,03 metros de friso con escenas de caza, y 10,40
metros de friso con procesión marítima. Teniendo en cuenta que en algunos casos los frisos
figuraban a ambos lados, se considera que, las escenas de caza cubrirían como máximo 23,67
metros, frente al total presupuesto de 40 metros de entablamento.

Dejando a un lado el problema de la reconstrucción del desarrollo del friso, conviene
remarcar la estrecha unión entre éste y el monumento. La decoración era parte integrante de la
arquitectura y fue realizada según un único proyecto, como demuestran los diferentes trabajos
de los bloques destinados a los arquitrabes, a los muros o a los pilares, sea el tipo original de
capitel corintio con volutas angulares revueltas hacia el ábaco, en vez del al exterior, decoradas
con una cabeza de amorino, clara alusión a los protagonistas del friso.

El relieve con la caza presenta una sucesión de combatientes que ven los amorini
generalmente luchando contra leones o grandes felinos, o en el acto de defenderse del ataque
conjunto de más fieras. Los protagonistas, alados y eventualmente adornados solo con una corta
clámide, van armados con una lanza, o menos frecuentemente con un arco o un bastón. El único
eventual compañero, en una batuta de caza que parece implicar singularmente cada uno de los
participantes en un esfuerzo no siempre coronado con la victoria, es un gran perro.

Debe notarse que ninguna de las fieras se representa derrocada, sino al máximo traspasadas
por la lanza, mientras los amorini corren notables peligros, caen, se hieren. En esta última
eventualidad se observan episodios de recíproca ayuda como cuando, sobre los relieves del

4 Imagen de Sapelli Ragni, M. (2010: 23).

123

<!-- p. 133 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

Museo Vaticano, uno de ellos, falto de las alas y herido en una pierna, se reposa sobre una
piedra defendido por un compañero que persigue a un jabalí; o cuando un amorino salva a otro
cazador del asalto de un león. En un contexto similar recuerda, también la delicada imagen de
un amorino que, apoyado en la lanza y al lado del fiel perro, parece llorar el triste destino de un
amigo caído.

Figuras 6.07 y 6.08. Imágenes de dos frisos de caza conservados en una de las estancias de la Piazza
d’Oro, Villa Adriana, fotografiadas en agosto del 2011.

Las fieras, casi siempre al galope o corriendo, avanzan solas o en pareja en direcciones
cambiantes, también sobre el mismo bloque. El bestiario está compuesto de leones, leonas,
antílopes, gamos, jabalís. De particular importancia para la interpretación del friso resultan los
cuadrúpedos de los semblantes equinos que sobre dos fragmentos aparecen traspasados por la
lanza blandida por un amorino. Se trata de una circunstancia que empuja a excluir que puedan
ser caballos, porque no son conocidas cazas cruentas de caballos, e induce a reflexionar sobre la
posibilidad de que pueda tratarse de otros animales. En efecto, particularmente seductor
resultaría la identificación con onagros, literalmente asnos salvajes, équidos bastante comunes
en Asia y África, que sabemos que eran cazados en la antigüedad, mientras menos sostenible
parece la hipótesis de que se trate de cebras, lo que presupondría la caracterización del uso del
color, del cual no se han encontrado trazas sobre los mármoles.

El tema de la caza, en el arte antiguo, expresaba ideales heroicos y aristocráticos. La caza se
convierte, ya en la Roma republicana, en un símbolo de nobleza helenizante como un
instrumento para ganar consenso político a través de espectáculos. Según fuentes, además, nos
describen al emperador como un apasionado cazador, tema sin duda reflejado en los frisos. Se
observa en los frisos de la Piazza que se busca enseñar con claridad la caza dentro de un
contexto natural, poniendo de fondo árboles en un ambiente silvestre, típicamente mediterráneo.
Además, la modalidad de combate de los “amorini” (desnudos, a pie, sin ninguna otra arma que
lanza, bastón o arco) exaltan, como se comentaba, el aspecto heroico y guerrero de la caza.

124

<!-- p. 134 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

B. OBJETO

El argumento de este caso, es el estudio de un espacio arqueológico y arquitectónico
primitivo, para la identificación de la posición en la que estaban situados los fragmentos de los
frisos y la realización de la anastilosis virtual del orden arquitectónico. Este estudio detallado
realizado permite, además, realizar una propuesta de intervención museográfica del conjunto
arquitectónico.

El estudio consta de una parte de levantamiento, con varios métodos que se explicarán en el
apartado correspondiente, y una de investigación del edificio.

La fiabilidad del resultado se avala con el empleo de una metodología rigurosa, basada en
estudios detallados, apoyados en tecnologías avanzadas e inocuas para las ruinas. El
levantamiento de los restos se hace con tecnología láser 3D que tras un estudio métrico y
geométrico de las trazas permite la anastilosis virtual de las piezas arqueológicas conservadas.
Estos estudios convergen en una hipótesis final que permite, entre otras cosas, revisar anastilosis
pretéritas como la formulada en los años 60.

Figura 6.09.
Imagen de la
Piazza d’Oro
en su
situación
actual.

125

<!-- p. 135 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

C. MEDIOS, SISTEMAS Y METODOLOGÍA DE LEVANTAMIENTO

Se parte de los estudios sobre Piazza d’Oro de diferentes autores como Francesco Sirano
“Adriano, architettura e progetto”, Charles-Louis Girault (2002: 105 – 112) “Italia Antiqua”,
Graziella Conti (1970) “Decorazione Architecttonica della “Piazza d’oro” a Villa Adriana”,
Erik Hansen (1960) “La “Piazza d’oro” e la sua cupola” y Andrea Moneti (1992: 67 – 92)
“Nuovi sostegni all’ipotesi di una grande sala cupolata alla “Piazza d’Oro” di Villa Adriana”.

Los estudios realizados hasta ahora no han permitido aclarar de forma concluyente el tema
de los frisos de caza, y su relación con los frisos de tipología de thiasos marino de Piazza
d’Oro. La utilización de nuevas tecnologías ayuda a clarificar su situación, lo que contribuye a
resolver dicha incógnita. Para ello, se ha realizado un nuevo levantamiento con tecnologías
avanzadas, mediante la interacción de diferentes técnicas de levantamiento.

La documentación gráfica de Piazza d’Oro que se presenta, es resultado de la combinación
de levantamientos con métodos topográficos, con tecnología escáner láser 3D y con técnicas
fotogramétricas. Cabe diferenciar entre el levantamiento arquitectónico más genérico, y el
levantamiento arqueológico más preciso, fundamentalmente de los frisos de tipología de caza.
En ambos casos los primeros resultados son modelos virtuales 3D que reproducen, con
considerable precisión, la forma real del objeto. A partir de esos modelos se ha generado toda la
documentación gráfica necesaria para el desarrollo de las diferentes fases de la investigación.

Figuras 6.10 y 6.11. Imágenes de los dos tipos de escáner láser usados en el levantamiento.

126

<!-- p. 136 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

Figura 6.12. Imagen del proceso de Image-based Modelling en el programa Agisoft PhotoScan.

i. Láser escáner

Cuando se escoge este caso, se elige porque se comprende la necesidad de un estudio en
profundidad de los restos del Palacio, para poder hacer una anastilosis, teniendo una base sólida
sobre la que hacer una nueva hipótesis. Observando la Piazza con atención, es fácil darse cuenta
de toda la información que aún conserva en sus restos: huellas que dejaron los soportes de
antiguos revestimientos, bases de columnas, partes de frisos que un día adornaron el lugar…
Todo esto se encuentra en la Piazza, a la intemperie sufriendo un degrado que puede ser
irreversible ya en algunos casos, y en otros lo será si no se realiza una intervención.

Teniendo esto presente, se considera importante realizar un levantamiento tridimensional de
alta precisión, para ese estudio detallado, considerado obligatorio. Una vez decidido, analizando
la plaza es fácil comprobar que se presentan dos escalas de detalle diferentes, uno a nivel
arquitectónico, debido a la magnitud de la Piazza, y otro más a nivel escultórico o decorativo.
Estudiándose la oferta actual de instrumentos para el levantamiento tridimensional de alta
precisión, se decide utilizar dos escáner láser diferentes, uno que utiliza la tecnología de
medición de distancia a tiempo de vuelo (TOF), el Laser Scanner Leica C10, y otro que realiza
la medición por sistemas de triangulación, el NextEngine Model 2020i Desktop 3D Scanner. La
diferencia de estos dos escáneres a parte de su forma de trabajo es su máxima precisión,
mientras que la precisión de un escáner a tiempo de vuelo es sub-milimétrica, la del escáner de
triangulación es de milésimas de milímetro. Esto se traduce, a efectos prácticos, en que para un
levantamiento arquitectónico la necesidad de precisión será cercana al centímetro, siendo útil el
primer tipo de escáner, y para la decoración, la precisión necesaria será milimétrica, siendo
interesante el segundo tipo de escáner. Teniendo en cuenta estos datos se realizan en paralelo el
levantamiento de la Piazza en general y el de algunos frisos de caza en particular.

127

<!-- p. 137 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

Figuras 6.13 y 6.14. En la imagen de la izquierda se puede observar la toma de datos con el escáner a
triangulación de uno de los frisos de caza. En la imagen de la derecha se ve la puesta en marcha del
escáner para el barrido de una de las zonas de la Piazza.

En el caso de los frisos, la toma de datos con escáner láser 3D se combina con técnicas de
Image-based modelling, que se comentarán en el siguiente apartado. Dada su mayor precisión,
los datos obtenidos con escáner se utilizan como documentación base. Se procura además que
sea la herramienta preponderante en el levantamiento de las partes que presentan decoración. En
cuanto a las zonas carentes de ornamentación, así como aquellas cuyas condiciones no son
óptimas para la operatividad del escáner (distancias, luminosidad…), son integradas con
técnicas fotogramétricas. El resultado de la combinación de ambos métodos es la generación de
réplicas virtuales 3D de cada una de las piezas arqueológicas. Partiendo de ellas es posible
producir una ficha gráfica individualizada, combinando las plantas, los alzados y las secciones
más relevantes junto a un esquema de identificación arqueológica y una vista en perspectiva
donde se reconocen los planos de sección.

Figuras 6.15 y 6.16. Imagen de uno de los frisos escaneados, una vez terminado el proceso de mesh
editing y a la derecha imagen de su ficha gráfica.

128

<!-- p. 138 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

En el ámbito arquitectónico, se realiza un levantamiento con 18 estaciones situadas en toda
la zona de interés del lugar. Éste a su vez, es apoyado con un levantamiento topográfico que
permitirá en un futuro unirlo a otros modelos 3D de la Villa y tener un modelo general de la
Villa Adriana.

Figura 6.17. Planta de la Piazza d’Oro en la cual están reflejados los puntos de posición del escáner,
reflejados mediante un círculo gris y un centro rojo.

El trascurso de trabajo de los levantamientos, tanto
para los frisos como para la arquitectura de la Piazza
sigue el mismo proceso que el expuesto en el caso de
Les Coves de Vinromá, usando el procedimiento de las
claves para llegar a las fichas de los frisos, y el
procedimiento de la capilla real para la Piazza. Sin
embargo, en el caso de la Piazza se realizan algunas
variaciones, mientras que para la capilla solo había un
escaneado, y la unión con los otros escaneados se hace
de modo manual en el Cyclone, en este caso se utilizan
target propias del escáner para hacer el registro de las
capturas de modo automático. Así, se realiza una red,
relacionando todos los escaneados. Esto permite en el
software Cyclone mediante un solo proceso colocar
todos los escaneados alineados. Además, de que este Figura 6.18. Imagen de un de los target
escáner tiene una calibración interna que permite tener usados para la alineación de las
siempre definido el eje z, marcando el eje vertical en capturas.
todos los escaneados.

129

<!-- p. 139 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

El levantamiento realizado en la Piazza permite también sacar modelos 3D de las columnas y
de las partes del entablamento, que permite, en un segundo paso, el estudio del orden
arquitectónico usado en este palacio.

ii. Image-based Modelling

Durante el proceso de Range-based Modelling en Coves de Vinromá se observaban algunos
problemas que van unidos al escáner láser a triangulación, y es que requiere unas condiciones
muy precisas para obtener modelos perfectamente cerrados. Esto se debe a que necesita
distancias precisas (aproximadamente 2 palmos, 40 cm.), la luz adecuada, etc. Visto esto, en el
segundo caso de estudio, se busca una alternativa para solventar los problemas encontrados en
el primero. Así se realizan las primeras experimentaciones con técnicas de Image-based
Modelling.

Para realizar los modelos poligonales de los frisos mediante dicho proceso se utiliza el
software Agisoft PhotoScan. Este programa presenta la ventaja y al mismo tiempo la limitación
de que realiza todo el proceso casi automáticamente, debiendo solo impostar una serie de
opciones que permitirán llegar a un modelo de polígonos tridimensional.

El proceso consiste en realizar un reportaje fotográfico teniendo en cuenta que las fotos debe
tener aproximadamente un 60% de superposición y al ser posible exista una convergencia entre
ellas. En el caso de los frisos se realiza un fotografiado rodeando el objeto y a dos alturas
diferentes, dando a una de ellas (la superior) una pequeña inclinación hacia la zona central para
permitir la convergencia entre ellas. Realizadas las fotografías, se introducen en el Agisoft
PhotoScan. En él, se realiza un procedimiento que está compuesto de 3 fases: 1º Calibración y
orientación de las imágenes; 2º Restitución 3D y generación de superficies; 3º Generación de la
textura foto-realista.

130

<!-- p. 140 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

Figura 6.19.
Imagen de la
primera fase
del proceso
de Image-
based
Modelling:
calibración y
orientación
de las
imágenes.

Figura 6.20.
Imagen de la
segunda fase
del proceso:
Restitución
3D y
generación
de
superficies.

131

<!-- p. 141 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

Figura 6.21.
Imagen de la
tercera fase
del proceso:
Generación
de la textura
foto-realista.

Terminado el proceso y teniendo el modelo, se realiza el escalado para tener el modelo en
verdadera dimensión, ya que en el caso del Image-based Modelling, los modelos resultantes no
tienen las medidas del modelo real. Así aprovechando el modelo escaneado, se selecciona una
medida en 3D de la mayor longitud posible, para introducir el menor error en proporción, y se
escala (el programa Agisoft PhotoScan solo permite el ingreso de una medida para escalar).

Con el modelo en verdadera dimensión, éste se exporta al software Rapidform XOR3, donde
se puede comprobar la desviación entre el modelo realizado con Range-based Modelling y éste.
Al comprobar que las diferencias son asumibles, se utiliza el modelo obtenido por procesos
fotogramétricos para integrar el modelo de escáner láser.

Figuras 6.22 y 6.23. Imágenes de la comprobación de la desviación entre los dos modelos realizados con
dos técnicas diferentes.

132

<!-- p. 142 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

D. TRATAMIENTO DE LOS DATOS

PIAZZA D’ORO

Realizado el levantamiento con escáner láser, se pasa a la fase de tratamiento de los datos.
En el caso del levantamiento arquitectónico, el primer software utilizado es el “Cyclone”,
programa propio del escáner (Leica C10), y que permite elaborar las nubes de puntos. El primer
paso en este caso será la alineación de las diferentes nubes para situar todas en el mismo sistema
de referencia, para una posterior conversión en mesh.

En la misma aplicación se genera el plano de planta, realizando varias secciones horizontales
a distintos niveles sobre el modelo de nube de puntos, dibujadas como poli-líneas. El
tratamiento de su representación es el de una topografía, asumiendo el carácter irregular de las
formas de la ruina, carente de líneas arquitectónicas definitorias. Así se realizan tres secciones,
buscando una estrategia que permitiera obtener la máxima información posible, sin
superposición de datos semejantes. Asignando la cota ± 0,00 m al punto de estacionamiento
central, las secciones realizadas son:

\- Una a + 0,10 (plano rasante) como soporte base, a nivel de las bases de las columnas y los
rodapiés, zona con menos faltantes y mayor definición formal, con algunas
reconstrucciones parciales que nos ayudan a entender el perfil cumplido.

\- Una a + 0,50 (plano medio o arqueológico) que alcanza los arranques de la máxima
cantidad posible de fábricas, al tiempo que permite reconocer casi todos los espacios.

\- Una a + 1,50 (plano alto o arquitectónico) por encima de la altura de los antiguos zócalos,
alcanzando los elementos emergentes que todavía quedan en pie o que fueron
reconstruidos en época posterior.

133

<!-- p. 143 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

Figura 6.24. Imagen de la nube de puntos en la que se pueden contemplar los tres planos de sección.

Una vez generada la planta de las fábricas con esas 3 líneas de nivel, se añade la información
restante del firme (relieve, textura…) realizando un “screenshot” proyectado sobre el plano de
cota cero (figura 6.25). Así, se obtiene la planta definitiva del levantamiento, totalmente
definida, de alta precisión y fiabilidad, que permitirá realizar estudios detallados en fases
posteriores.

Figura 6.25.
“Screenshot” de
la planta
proyectada sobre
el plano de cota
cero.

134

<!-- p. 144 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

Figura 6.26. Imagen de la planta de la Piazza d’Oro como resultado de la
elaboración de los datos obtenidos con los diferentes tipos de
levantamiento (2011)

Partiendo del modelo completo de nube de puntos se genera un modelo poligonal 3D
mediante representación de superficies de subdivisión. Para ello es necesario seguir todo un
proceso realizado en diferentes programas. Primero se dividen en estancias la villa desde las
nubes de puntos de Cyclone. Después, utilizando los software Geomagic y Rapidform XOR3, se
realizan modelos mesh de cada una de las estancias a alta resolución (HP). Será necesario
realizar también modelos de baja resolución (LP) para poder usarlos en los programas que no
soportan modelos tan “pesados”, pero mediante las superficies de subdivisión comentadas,
realizadas en Modo, será posible mantener el nivel de detalle. Teniendo los modelos a baja
resolución se consigue generar un modelo que integra todas las estancias.

Teniendo el conjunto de estancias, con niveles de detalle variables, se registran las huellas de
los elementos arquitectónicos en la ruina, a fin de estudiar los vestigios de la posición del orden
arquitectónico en los alzados. Con este criterio, y sobre este segundo modelo digital, se realizan
las dos secciones verticales principales que completan los documentos gráficos del
levantamiento base.

135

<!-- p. 145 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

Sección AA’

Sección BB’

Figuras 6.27 y 6.28. Arriba sección transversal
(sección AA’) de la zona de estudio de la Piazza Sección BB’
d’Oro. Abajo sección longitudinal (sección BB’)
de la misma zona.

Figura 6.29. Planta aclaratoria de las secciones. Sección AA’

FRISOS:

Por otra parte, paralelamente a las elaboraciones de los modelos arquitectónicos, se realiza el
tratamiento de datos de los frisos de caza. Como se comenta en el apartado de metodología, el
modelo final de la mayoría de los frisos escaneados, son el resultado de una integración del

136

<!-- p. 146 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

modelo obtenido mediante Range-based Modelling y el obtenido mediante Image-based
Modelling.

Se utilizará en todos los casos el modelo obtenido con escáner láser como modelo base, por
tener una mayor precisión, usando el otro para reintegrar las zonas que no se han podido
capturar con el escáner por problemas de distancias, luz solar, etc. También se usarán las
técnicas fotogramétricas para la captura de las zonas sin decoración, debido a que con el
modelado, a través de Agisoft PhotoScan, la velocidad de obtención es mayor, ahorrando
tiempo.

Los pasos seguidos para la integración, una vez obtenidos los dos modelos han sido: primero
comparación de la desviación entre ambos modelos, como comentábamos en el apartado de
metodología, y una vez ratificada una desviación aceptable, se procede a tomar del modelo del
Agisoft PhotoScan la parte necesaria. Debe aclararse que cuando se hace el modelo en Agisoft
PhotoScan no se hace solo de la parte faltante del modelo del escáner, sino que se hace el
modelo completo. Sin embargo, las partes que ya están presentes en el modelo del escáner, se
deberán eliminar en el otro, para no tener mesh duplicadas que causarían errores. Por ello, se
deben eliminar con mucha delicadeza las partes coincidentes entre los dos modelos y controlar
con especial atención las zonas de bordes entre ambos modelos para que no se presenten
superposiciones. Teniendo esta parte controlada, se pasa a la fase de unión de ambas mesh. Para
realizar esta unión se utiliza un comando del software Rapidform XOR3, dentro del relleno de
huecos, que consiste en hacer pequeños puentes entre las mallas. Concluidas las uniones, se
rellenan los huecos subsistentes, y con eso se ultima el modelado de los frisos.

Figuras 6.30 y 6.31. Imágenes del proceso para obtener el modelo con técnicas Range-based modelling. A
la izquierda se están alineando las diferentes mesh obtenidas con el escáner a triangulación y a la derecha
se presenta el modelo una vez se han fusionado las mesh en una sola.

137

<!-- p. 147 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

Figuras 6.32 y 6.33. A la izquierda, modelo obtenido con técnicas de Image-based Modelling, a la
derecha, imagen de las dos mesh superpuestas, en azul la del escáner y en verde la del Agisoft PhotoScan.

Figuras 6.34 y 6.35. Imágenes de la integración de ambas técnicas para obtener el modelo final (a la
derecha)

138

<!-- p. 148 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

E. ANÁLISIS

ESTUDIOS TIPOLÓGICOS

Cuando se comienza a plantea la idea de reconstruir virtualmente parte de la edificación, hay
partes que se pueden inducir hipotéticamente a partir de aquello que aún queda en pie. Se
distingue las bóvedas de cañón, gracias a los arranques que todavía se conservan. La posición de
los frisos, por las trazas que se pueden observar aún en los muros. La bóveda de crucería de la
estancia que se sitúa al fondo del lado Este de la plaza. Sin embargo, también surgen dudas en
algunos elementos no tan evidentes. En esos casos la hipótesis se ha formulado mediante
transpolación de otras soluciones tipológicamente similares, observadas en las proximidades,
bien en la misma Piazza d’Oro, bien en sus proximidades dentro de Villa Adriana.

Entre los elementos no tan
evidentes, se observa la
finalización de las cubiertas de
las estancias de los dos
laterales del ninfeo. La
primera opción considerada es
el acabado mediante cubiertas
inclinadas a dos aguas (figura
6.36). Sin embargo, se decide
analizar la zona de estudio
para buscar elementos que
sugieran la posible solución y
estudiar las tipologías
utilizadas en las proximidades
buscando esa armonía formal
Figura 6.36. Croquis de la hipótesis inicialcaracterística de los romanos.
Al realizar el análisis, se
encuentran las trazas de un
arco en el muro de la estancia
intermedia del grupo de las 3
estancias de la zona del Este.
Este arco, en dicho muro, no
parece cumplir ninguna
función, sin embargo, se
considera la posibilidad de que
se presente como un simétrico
de uno situado
precedentemente en la pared
opuesta. Estudiando, como se
Figura 6.37. Imagen de la edificación situada al Noreste de la
comentaba, las tipologías
Piazza.

139

<!-- p. 149 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

empleadas en la zona, se
descubre un uso similar al de
la edificación que se encuentra
en la misma Piazza d’Oro,
pero cercana al vestíbulo,
situado también en la zona del
Este (figura 6.37).

Planteada la hipótesis de
finalización de la parte de las 3
estancias contiguas, queda otro
elemento por resolver: el cierre
de las estancias que se sitúan
en la parte delantera y
posterior del atrio. Así
continuando con el estudio
tipológico de la zona, se Figura 6.38. Imagen del vestíbulo de Piazza d’Oro
encuentra en el vestíbulo
(figura 6.38), una combinación
de triángulos y arcos alternos
que situándolos en la zona de
estudio, concordarían con
coherencia integrando el arco
comentado en el párrafo
precedente. Por lo tanto, las
dos estancias presentarían
cubiertas a dos aguas,
alternando con el arco de la
estancia intermedia. Con esta
hipótesis quedan definidas
todas las estancias que cierran
el atrio (figura 6.39).
Figura 6.39. Croquis de la hipótesis final.

De este modo, la única pregunta que queda en el aire es la cubrición final del conjunto de las
3 estancias contiguas. Entre otras, cabrían dos soluciones. Una que tuviese una cubierta única, a
un agua, con inclinación hacia el exterior, o sea, hacia la parte trasera. La otra solución sería que
las bóvedas llevasen una capa aislante y que la cubrición quedase tal y como se ve en la figura
6.39, teniendo las limahoyas inclinación hacia las bajantes para la evacuación
del agua.

El problema que se presenta en este caso, es que no se ha encontrado nada que pueda
ratificar una de estas dos soluciones. Por ello, se dejaría así, ya que no se considera oportuno
intervenir introduciendo elementos inventados.

140

<!-- p. 150 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

ESTUDIO DEL MÓDULO CORINTIO

Paralelamente, y de forma independiente, se restituye un fragmento del orden arquitectónico
partiendo de sus restos. Se toma como referencia la proporción del orden corintio según
Vitruvio. Siguiendo dicho canon, las columnas deben tener una altura total, incluyendo basa,
fuste y capitel, de 9 diámetros y medio (medio para la basa, 8 para el fuste y uno el capitel). Sin
embargo, asumiendo que en la época imperial las medidas de Vitrubio se aplicaban con cierta
flexibilidad, se comprueba que los capiteles corintios de Piazza d’Oro superan ligeramente la
altura canónica, como era habitual en los casos de capiteles con decoraciones más complejas,
ajenas al modelo vitruviano. También los entablamentos (arquitrabe, friso y cornisa), decorados
con un repertorio ornamental particular, superan en altura las proporciones vitruvianas.

En todo caso las medidas, incluso cuando presentan diferencias respecto a las proporciones
canónicas, se ajustan a unidades métricas romanas prácticamente exactas. Por ejemplo,
comparando el diámetro en el imoscapo del fuste de nuestra columna con las medidas romanas
(1 pie romano = 295,6 mm), obtenemos que 1 diámetro imoscapo = 442,404 mm /295,6 =
1,4966 ≈ 1,5 pie romano = 6 palmos = 1 codo.

Figura 6.40. Imagen de una columna corintia de la Piazza Figura 6.41. Imagen del módulo
d’Oro, obtenida a partir de la nube de puntos sacada con el corintio obtenido a partir de la
escáner láser arquitectónico. combinación de diferentes elementos
escaneados

141

<!-- p. 151 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

La restitución se realiza, en parte, mediante anastilosis virtual, partiendo de los diferentes
restos arqueológicos conservados de piezas que formaban parte de las columnas y los
entablamentos. Se escanean y los modelos 3D generados se montan digitalmente sobre el patrón
vitruviano. Las zonas faltantes se restituyen con el volumen teórico del elemento, a fin de
obtener un fragmento completo del orden arquitectónico, desde la basa hasta la cornisa. La
principal aplicación de dicho fragmento es su utilización como patrón flotante en el estudio
compositivo de la arquitectura en los alzados interiores.

ESTUDIO ESPECÍFICO DE LOS FRISOS

Para identificar la ubicación original de los fragmentos de los frisos se procedió a un examen
de compatibilidad entre la geometría de las piezas y la de las fábricas del monumento en
proyección horizontal. La forma de las primeras se analiza directamente en cada una de las
fichas gráficas. La geometría de las fábricas se estudia en la planta obtenida en la fase de
levantamiento.

La complejidad del trazado de la planta hace que muchos de los fragmentos de frisos
conservados presenten múltiples caras, formando ángulos diversos entre sí. En los casos en que
se identifican restos de decoración, la compatibilidad figurativa de los temas representados
constituye un argumento relevante para identificar su ubicación.

Figuras 6.42 y 6.43. Fichas 1 y 2 de los frisos escaneados.

La pieza de ejemplo (ficha 2, figura 6.43) presenta decoración solo en una de sus caras, y en
la cara contrapuesta la superficie es plana con cierta rugosidad, probablemente para permitir su
adhesión al muro. Además se aprecia que la cara decorada tiene una superficie dispuesta para
recibir otra pieza adyacente, que define el arranque de un elemento no ortogonal.

Este otro ejemplo (ficha 3, figura 6.44) presenta decoración en sus dos caras opuestas, lo que
permite definir el espesor exacto del entablamento exento. Además, presenta en una de las caras

142

<!-- p. 152 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

decoradas, ángulos en su plano horizontal que permiten deducir que esta pieza en uno de sus
lados apoyaba directamente en el muro.

Figuras 6.44 y 6.45. Fichas 3 y 4 de los frisos escaneados

Según los estudios arqueológicos más concluyentes, los frisos de thiasos maritimo se
encontraban situados en las zonas con presencia de agua. Por deducción recíproca se puede
suponer que los frisos con temas de caza se encontraban situados en zonas donde no había
presencia de agua.

Combinando los argumentos geométricos con los figurativos se puede llegar a identificar la
situación de dos de los cuatro frisos escaneados en la campaña de abril de 2011.

Figuras 6.46 y 6.47. Imágenes de la demostración del posicionamiento de los frisos en su situación
original.

El friso LED 04 (ficha 3) presenta decoración en dos de sus caras, siempre del mismo tema,
y los ángulos permiten encontrar la posición justa ya que no se encuentra otro ángulo similar en
Piazza d’Oro. Además, la decoración acaba justo en el punto en el que haría el encuentro con el
muro.

143

<!-- p. 153 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

El friso LED 05 (ficha 2) solo tiene decoración por uno de sus lados, el ángulo es
coincidente y tiene una cara preparada para el apoyo de la pieza que continuaría formando el
diseño justo.

Encontrada la situación de la pieza, se coloca el friso en su posición exacta comprobando
que los ángulos coinciden tanto en vertical como en horizontal, a la vez que las trazas que
quedan marcadas en los muros todavía en pie.

F. MODELOS OBTENIDOS

PIAZZA D’ORO
Como se comentaba en el apartado del análisis, una vez obtenida la nube de puntos en
Cyclone y alineada, esta se exporta a otros programas para su edición. Sin embargo, las nubes
de puntos son muy “pesadas” así que la exportación se debe hacer por partes. Esta edición
realizada entre el Geomagic y el Rapidform XOR3 lleva a obtener un modelo de alta calidad en
Rapidform XOR3, pero demasiado pesado para trabajar (figura 6.48).

Figura 6.48. Modelo de toda la Piazza en Rapidform XOR3

Para permitir la manipulación y tener modelos utilizables se realizan modelos de superficies
de subdivisión, con nivel de detalle variable. Para ello, se realiza un proceso que cosiste en el
siguiente:

Se comienza trabajando singularmente con cada una de las estancias. Esta que tiene un alta
resolución (millones de polígonos) mediante en proceso de “decimation”, permite una reducción
de la cantidad de polígonos (a miles de polígonos) y con ello su reducción de peso, en sentido
de Mb. Teniendo los dos modelos, el de alta resolución, llamado en general HP (High-Poly) y el
de baja resolución, LP (Low-Poly), se exportan ambos modelos al programa Modo. En este

144

<!-- p. 154 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

programa se realiza un proceso llamado “retopology”. Este proceso es definido por Fantini y
Martínez-Espejo Zaragoza (2012) como “la modificación de la topología de un objeto”, dentro
del campo del computer graphic, y en el de las matemáticas. Sin embargo, se define como “la
rama que estudia las propiedades de una figura geométrica que no se modifican mediante el
estirado, la flexión y homeomorfismos similares”.5 En síntesis, se trata de un proceso que
permite redibujar el objeto, pero solo a base de cuadrángulos.

En el caso de la Piazza d’Oro, se realiza el retopology de toda la zona de estudio. Se importa
en el Modo cada uno de los modelos LP (por separado, se hace el proceso para cada uno de
forma independiente) y se “calcan” utilizando polígonos cuadrangulares.

Figuras 6.49 y 6.50. Imágenes del proceso de retopology de una de las estancias de la Piazza.

Tras la fase de retopology, se realiza el UVmap de la estancia (figura 6.51), que permitirá en
una segunda fase realizar los modelos a nivel de detalle variable.

Figura 6.51. Imagen en la que se puede observar una de las UVmap.

5 Definiciones sacadas de Fantini, F. y Martínez-Espejo Zaragoza, I., 2012.

145

<!-- p. 155 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

Terminada la UVmap se introduce en el programa en el mismo sistema de referencia el
modelo HP. Con el modelo HP, se realiza un proceso llamado “baking”, que permite copiar la
información presente en el modelo HP, en el modelo a cuadrángulos, copiando dicha
información en la UVmap (figura 6.52). Después de este proceso, se ha generado una nueva
textura para el modelo generando así los modelos de niveles de detalle variables

Figura 6.52.
Screenshot del
momento en el cual
se está generando
la nueva textura a
partir del baking.

Realizando este proceso con todos se obtiene un modelo final de bajo “peso” y con un alto
nivel de detalle de toda la plaza (figura 6.53)

Figura 6.53. Render de la zona del atrio de la parte Este de la Piazza a partir de modelos de subdivisión a
alto nivel de detalle.

146

<!-- p. 156 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

FRISOS DE CAZA

A partir de los modelos de los frisos realizados mediante las dos técnicas comentadas y su
reintegración, se obtienen modelos que permiten en algunos casos encontrar su posición
original.

Figuras 6.54, 6.55, 6.56 y 6.57. Render de los cuatro frisos levantados y modelados.

147

<!-- p. 157 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

G. RESULTADOS

PROPUESTA DE MUSEALIZACIÓN

Aprovechando este estudio detallado, y la generación de un modelo tridimensional de alta
resolución, ha sido posible plantear una hipótesis museográfica, pormenorizada en la tesis del
master de museografía realizado por la autora (Mtnez-Espejo Zaragoza, I., 2012).

Después del estudio realizado sobre la edificación de la Piazza d’Oro, y en particular, de los
atrios que esta contenía, por ser la zona donde se situaban los frisos de tipología de caza, se
llega a una propuesta de intervención que se considera apropiada, por su doble carácter
didáctico y práctico.

La intervención que se propone es diferente en las estancias que envuelven los dos atrios que
constituyen la Piazza. En el caso de las estancias que se sitúan en el lado oeste del lugar, se
propone realizar únicamente una limpieza y consolidación de ésta. De ese modo, la gente que
visite la zona podrá ver el estado actual de las ruinas, y así interpretar la evolución y el deterioro
que ha sufrido la Piazza d’Oro hasta llegar a la época actual. Sin embargo, al otro lado de la
Piazza, en la zona este, se propone realizar una reconstrucción de las bóvedas de las estancias
que conforman los dos ejes del atrio, zonas de exposición, y de las bóvedas anterior y posterior
a la que forma parte el eje longitudinal (observar la figura 6.58), que tendrán usos diferentes. La
estancia que da a la zona ajardinada (la granate en la imagen), se utilizará como estancia
multimedia, en la cual se explicará la historia de la plaza, su evolución, los trazados que
conformaron el lugar… y toda la información de interés que se ha investigado y que puede
suponer un enriquecimiento para los visitantes. La estancia que contiene un ábside (verde en la
imagen), será dividida en dos zonas, siendo una un lugar de estudio y la otra un taller
interactivo, de carácter didáctico, donde las personas podrán aprender de una forma
participativa. El resto de las salas reconstruidas (azul en la imagen), se utilizarán como museo,
permitiendo resguardar los frisos, que en la actualidad se encuentran a la intemperie, lo que
supone un constante peligro para éstos. Además, los frisos de la zona este, que se logre
encontrar su posición, serán colocados en su posición original, colocando el resto en la zona de
exposición con una ficha al lado, en el que explique su posición, y los datos pertinentes que se
consideren oportunos para una mayor comprensión del lugar y de éstos en particular.

148

<!-- p. 158 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

Reconstrucción de las bóvedas para conservar la arquitectura y musealizar todos los frisos bajo una cobertura
Reconstrucción de la bóveda para estancia multimedia
Consolidación de los muros dejando ver cómo han llegado a nuestra época
Reconstrucción de la bóveda para laboratorio interactivo

Figura 6.58. Imagen esquematica de las zonas de actuación.

Figura 6.59. Sección longitudinal de la parte intervenida por la zona del atrio.

149

<!-- p. 159 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

Figura 6.60. Sección transversal de la parte intervenida por la zona del atrio

Figura 6.61. Modelo de la intervención en 3D realizada sobre el modelo de superficies de subdivisión,
quitando la parte de la bóveda delantera del eje longitudinal para permitir la visión de la intervención en
las 3 estancias consecutivas.

150

<!-- p. 160 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

INTERVENCIÓN FRISOS

En el caso de los frisos, el estudio de adscripción de piezas de frisos a su ubicación
supuestamente original, basado en la compatibilidad formal, geométrica y temática, se propone
como un posible uso del modelo tridimensional, permitiendo de este modo formar parte del
contenido museológico de la propuesta nueva instalación museográfica, disponiendo incluso de
una instalación (taller interactivo), de carácter didáctico, donde el visitante podría adscribir
virtualmente piezas a lugares concretos del edificio, por sí mismo.

151

<!-- p. 161 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

H. REFERENCIAS

BIBLIOGRAFÍA BÁSICA DE REFERENCIA:

 Adembri, B. (a cura di), 2000. Adriano: Architettura e progetto. Ministerio per i beni e le
attività culturali. Soprintendenza archeologica per il Lazio. Editorial Mondadori Electa.
Milano.

 Aurigemma, S., 1996. Villa Adriana. Istituto Poligrafico e zecca dello stato. Libreria dello
stato. Roma.

 Benedetta, A., Juan Vidal, F. y Martínez-Espejo Zaragoza, I., 2011. Hunting friezes of the
Piazza d’Oro at the Hadrian’s Villa: new hypothesis for a virtual reconstruction inside an
integrated research strategy. Texto incluido en el libro de Actas de 16th International
Conference on Cultural Heritage and New Technologies. Museen der Stadt Wien –
Stadtarchäologie. Viena. ISBN: 978-3-200-02740-4, pp.140-153.

 Fantini, F., 2008. Il modello di stadio da Villa Adriana. Indagine su un progetto incompiuto.
Università degli Studi di Firenze. Florencia.

 Martínez-Espejo Zaragoza, I., 2012. Interpretazione museografica dei portici con fregi di
caccia della “Piazza d’Oro”. Tesis del Máster Itinerante en “Museografia, Architettura e
Archeologia. Progettazione Strategica e Gestione Innovativa del Patrimonio Archeologico”
instituido por la “Accademia Adrianea di Architettura e Archeologia Onlus” dirigida por
Francisco Juan Vidal. Roma, Italia.

 Ortíz y Sanz, J., 1787. Los diez libros de la architectura de M. Vitruvio Polión. Madrid en la
Imprenta Real. Madrid.

 Perrault, C., 1981. Compendio de los diez libros de arquitectura de Vitruvio. Comisión de
cultura del Colegio Oficial de aparejadores y arquitectos técnicos. Galería-Librería Yerba.
Consejería de Cultura del Consejo Regional. Murcia.

 Sirano, F., 2000. “Calestia Animalia” a Villa Adriana? Considerazione sul fregio con
amorini della Piazza d’Oro. Adembri, B. Adriano: Architettura e progetto. Ministerio per i
beni e le attività culturali. Soprintendenza archeologica per il Lazio. Editorial Mondadori
Electa. Milano.

BIBLIOGRAFÍA CONSULTADA

 Bozzoni, C., Franchetti Pardo, V., Ortolani, G., Viscogliosi, A., 2010. L’Architettura del
mondo Antico”. Editori Laterza. Bari (Italia).

152

<!-- p. 162 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

 Conti, G., 1970. Decorazione Architettonica della “Piazza d’Oro” a Villa Adriana. Studia
Archaeologia (“Erma” di Bretschneider). Roma.

 Fantini, F. y Martínez-Espejo Zaragoza, I., 2012. Procedure per la realizzazione di modelli
digitali 3D ottimizzati: da Cyclone a Modo. Seminario Tematico: Rilevare e progettare nel
contesto storico: Pietrabuona (Pescia, PT). Università di Firenze. Florencia.

 Girault, C. Louis. 2002. Peristilio del palazzo dell’imperator Adriano, 1885. dentro de
Jacques, A., Verger, S., Virlouvet, C.: Italica Antiqua. Envois degli architetti francesi (1811
– 1950). Italia e area mediterranea. École nationale supérieure des beaux-arts. Paris.

 Hansen, E., 1960. “La “Piazza d’Oro” e la sua cupola” dentro de la Revista: Analecta
Romana Instituti Danici. 1º Supplementum. Copenhagen. Denmark (escrito en italiano)

 Moneti, A., 1992. “Nuovi sostegni all’ipotesi di una grande sala cupolata alla “Piazza
d’Oro” dentro de la Revista: Analecta Romana Instituti Danici. Nº 20. Roma.

 Sapelli Ragni, M. (a cura di) 2010. Villa Adriana. Una historia mai finita. Novitá e
prospettive della ricerca. Ministero per i Beni e le Attività Culturali. Soprintendenza per i
Beni Archeologici del Lazio. Editoriale Mondadori Electa S.p.A., Milano.

153

<!-- p. 163 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

CAPÍTULO 6. CASO DE ESTUDIO 3

Integración de frescos: Bóveda con frescos del
Palacio Roncioni

154

<!-- p. 164 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

A. BREVE RESEÑA HISTÓRICA

EL PALACIO RONCIONI

El Palazzo Roncioni se encuentra situado sobre los márgenes del Arno en la ciudad de Pisa.
Es la única residencia sobre los “Lungarni”1 de las cuales se conserva aún la escalera hacia el
río, una escalinata de acceso a los diques.

El Palacio presenta una fachada de la mitad
del 6002 en la cual se sitúa el emblema de los
propietarios, un caballo robusto, llamado el
“concione” o “ronzone”. Poco más adelante se
encuentra “lo scalo Roncioni”, una de las últimas
rampas de acceso que quedan hacia el Arno
después de las reestructuraciones del siglo XIX.
El edificio surge gracias a la fusión de varias
casas medievales, claramente diferenciables en
algunas trazas sobre los lados externos. La
conformación planimétrica hacia el interior es en
forma de herradura con amplias vistas que se
abren por una logia hacia un jardín a la italiana
encerrado por algunas dependencias.
Figura 7.01. Detalles arquitectónicos de la
fachada tardo manierista (Ciampa, M., 2010:
\128)

Los interiores conservan hermosos frescos del setecientos, y una reciente restauración han
puesto en valor también decoraciones de pintura medieval datadas del siglo XIII y XIV1. Se
trata de 4 decoraciones pictóricas referidas a dos diferentes planos temporales de un edificio que
engloba un conjunto de tapices atacados a los muros. El más antiguo está decorado con un
fresco a ondas blancas y rosas, dominado por una cornisa superior a cinco haces, de los cuales el
central es rosa y los otros son blancos y negros. Se trata de una simple figuración de un ideal
revestimiento textil, adherido al muro y delimitado en su parte superior por un resalto continuo.
La decoración a ondas se encuentra abundantemente en muchos otros ejemplos de pintura mural
pisana (Ciampa, M., 2010: 127-134), utilizados entre los siglos XII y XIV. Reflejo paralelo se
encuenta también en las fuentes escritas.

1 Lungarni, plural en italiano de Lungarno, palabra utilizada para designar las zonas que confrontan los
márgenes del Arno.
2 http://www.turismo.pisa.it/it/cultura/dettaglio/Palazzo-Roncioni-00002/ (fecha de la última consulta:
25/10/2013)

155

<!-- p. 165 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

El otro está decorado con pieles de vero3 estilizadas, presentando en el nivel superior un
fingido tapiz con caballeros en armadura y una simulada pared pétrea.

En un segundo momento se decide decorar la habitación con una nueva pintura al fresco,
más articulada pero de tipología fundamentalmente similar: el aparato a ondas se adapta a los
gustos del tiempo y se sustituye por una decoración estilizada. Esta tipología de decoración se
encuentra en modo recurrente en la arquitectura pisana y a menudo atribuida al siglo XIV.

El palacio pertenece en gran parte aún a la familia Roncioni, descendiente de una de las más
antiguas casas nobiliarias de la Toscana, desde su adquisición por Bali Cesare Roncioni, en
1630 (Ciampa, M., 2010). Un siglo después de su adquisición, el Bali Angiolo Roncioni (17481812) apasionado por el arte, convenció al pintor G.B. Tempesti para decorar con frescos los
muros y las bóvedas y a J.B. Desmarais para realizar algunos retratos de familia. En el 1795,
Vittorio Alfieri recitó “il Saul” en un teatrillo situado en un amplio salón de la planta noble
construido por el arquitecto Alessandro Gherardesca, que desde entonces unió su nombre a la
familia. Entre el Setecientos y el Ochocientos el Palacio alojó temporalmente huéspedes ilustres
ente los cuales se pueden citar: Granduca Pietro Leopoldo, Madame de Staël, Paolina e Luigi
Bonaparte e Lord Byron. En el 1879 el Palacio Roncioni fue sede de reuniones clandestinas de
los Mazzini.

Los Roncioni pertenecen a una de las familias que han escrito la historia de la ciudad y del
territorio; la herencia monumental unida al nombre Roncioni se mantiene aún hoy en vastas
porciones de la provincia, basta citar la Rocca di Ripafratta y su relativo sistema de torres de
vigilancia. Además, redescubriendo las intensas y excelentes relaciones de la familia,
estratificadas en los siglos de vida del palacio urbano y en la Villa de Pugnano, se puede
imaginar la vivacidad cultural relativa a los estratos más altos de la sociedad pisana,
cualificados por la misma historia de la ciudad.

33 Vero o Vay es un tipo de forro heráldico, se cree inspirado en la piel de una marta cebellina o una
ardilla rusa de pelaje gris argento. El vero se compone de campanas pequeñas, colocados en faja y
opuestos unos a otros, de modo que la base de cada uno de metal esté siempre junto a la base de uno de
color [http://es.cyclopaedia.net/wiki/Vero-(heraldica)] (última visita: 02/02/2014)

156

<!-- p. 166 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

El núcleo del Palacio Roncioni
anteriormente propiedad de Gaspare
di Orazio Franchi, fue adquirido por
Luigi Navarrette con un acta del
notario Ser Iacopo Bizzarri. El 13 de
julio de 1630 Navarette vendió la
misma parte del inmueble a Balí
Cesare Roncioni: en esta ocasión
viene redactada la primera
descripción constatada del
monumento (Ciampa, M., 2010):
“Casa di Lungarno con orto e 25
buche da grano e sue appartenenze
[...] confina al Iº di via del Figura 7.02. Vista cenital del Palacio. Imagen obtenida de
Lungarno, IIº chiasso che va a San google map.
Luca, IIIº le casette delle monache di
San Matteo, IVº via che divide tra
Lafranchi e Navarette”4.

4 Casa de Lungarno con huerta y 25 huecos para el grano y sus pertenencias [...] confina con: 1º de la vía
Lungarno, 2º camino que va a San Luca, 3º las casas de las monjas de San Mateo, 4º vía entre los
Lanfranchi y los Navarette.

157

<!-- p. 167 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

Durante la Guerra Mundial el palacio sufrió daños
considerables, por ello el conde Girolamo Roncioni realiza
algunas restauraciones necesarias: la atención de Girolamo por
la edificación histórica pisana es confirmada en su manuscrito
sobre los palacios de Pisa, que recientemente se han publicado
siendo Alessandro Panajia su editor (Panajia, A. y Melis, A.
2004).

Durante la reorganización de la estructura en el seiscientos,
que los Roncioni encargan presumiblemente al ingeniero
Stefano Maruscelli, se llega a arrasar una manzana completa
medieval, convirtiendo la mitad del complejo más distante del
lado del río en jardín, que llega a extenderse hasta el límite de
la Iglesia de San Luca, eliminada en 1783. Así como bien
recoge Paolo Caroli, este jardín, en el levantamiento de la
planta de la ciudad de Pisa realizada por Van Lint en el 1846,
“presentava un disegno geométrico con esedre semicircolari e
un’aiola centrale a forma romboidale”5, luego de impostación
“italiana” y debida a la reforma del complejo en el seiscientos.
El Palacio asume una conformación planimétrica, como se
comentaba, a “herradura” con doble cuerpo sobre el lado este
y, organizada en el interior, según modelos recurrentes del Figura 7.03. Interior del Palacio
Seiscientos, un “cortile” interno con un pórtico compuesto por Roncioni. Alzado abierto hacia el
arcos y con frescos con motivos florales en estilo del jardín, donde se puede observar el
seiscientos. pórtico compuesto por arcos.6

De la época del seiscientos se encuentran hasta cuatro estratos de decoración, pero sobre este
se sitúa el aparato pictórico de los siglos setecientos-ochocientos, de gran importancia, que
engloba algunas de las más altas realizaciones de Giovan Battista Tempesti.

Pisa, aun siendo rica de testimonios similares, no dispone de un estudio sistemático y
multidisciplinar sobre su pintura medieval, aunque no falten validas profundizaciones sobre el
tema, entre las cuales la más reciente es conducida por la doctora Mariagiulia Burresi.

En la fachada que da al Arno se revela, a través de su unidad formal, la voluntad de exprimir
una nueva imagen urbana que ve los frentes sobre el río como parte de una representación
escenográfica.

5 Presentaba un diseño geométrico con exedras semicirculares y un lecho central en forma romboidal.
6 M. Ciampa (2010: 129)

158

<!-- p. 168 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

Este fenómeno, en particular, es visible si se
compara la fuerza expresiva de la fachada de
lenguaje tardo-manierista con el efecto de
“rigiranza” (de “regiro”), bien subrayado por
el objeto de cubrición que se extiende poco
más allá del frente en piedra. La constitución
del Palacio evidencia una fuerte presencia de
la fachada, frente a una voluntad marginal de
incluir los lados del edificio, de nueva
solución formal, permitiendo la lectura de las
trazas marcadas por su historia. Este
“permanecer” de la edilicia medieval se
inserta en la larga tradición edificatoria
pisana donde el “rimaneggiamento”
(persistencia) de las arquitecturas se
demuestra recurrente ya a partir de los siglos Figura 7.04. Vista del Palacio Roncioni desde el
centrales del Medievo. Lungarno Mediceo.

LA BÓVEDA CON FRESCO

La superficie con el fresco objeto del levantamiento pertenece a la estructura abovedada de
uno de los vanos en la planta baja del Palazzo Roncioni de Pisa, uno de los ejemplos más
valioso de arquitectura manierista de la ciudad.

Además del valor
arquitectónico, el edificio
conserva un rico aparato pictórico
decorativo realizado por Giovan
Battista Tempesti, activo en
Toscana y especialmente en Pisa
en la segunda mitad del siglo
XVIII, autor de importantes
frescos entre los cuales se puede
citar aquel de la sala de la música
en el Palacio Pitti en Florencia y
la figuración de la ultima cena en Figura 7.05. Imagen de la bóveda decorada con el fresco de
la catedral de Pisa. Giovan Battista Tempesti.

La raíz geométrica constructiva de la bóveda en examen es referible a la tipología de las
bóvedas esquifadas, impostada sobre una planta rectangular, aunque no propiamente regular.

159

<!-- p. 169 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

El fresco es en gran parte conservado, menos algunas evidentes lagunas creadas en tiempos
recientes por fenómenos de deterioro ambiental. La bóveda presenta además difusas lesiones
debidas a un disector de naturaleza estructural.

El levantamiento de la bóveda se convierte en una necesidad para permitir la documentación
del fresco en vista de los trabajos de restauración, que se están realizando en algunas partes del
palacio.

B. OBJETO

Este caso de estudio se desarrolla en la estancia efectuada en el Laboratorio A.S.T.R.O
(Applicazioni Scientifiche Topografiche per il Rilievo Operativo, Aplicaciones Científicas
Topográficas para el Levantamiento Operativo) del Departamento de Ingeniería Civil e
Industrial de la Università di Pisa, junto a los profesores Gabriella Caroti, Andrea Piemonte y
Marco Bevilacqua.

Con estas premisas se realiza este caso de estudio, elaborando un levantamiento con escáner
láser y fotogramétrico de la bóveda esquifada del siglo XVIII, decorada con un fresco, del
Palacio Roncioni en Pisa. La utilización contemporánea de técnicas activas (láser escáner) y
pasivas (fotogrametría) permite un análisis de las precisiones obtenidas con metodologías de
Image-based modelling. Además, se puede profundizar en la utilidad para la ingeniería y el
cálculo estructural de los modelos obtenidos, así como para la de restauración de los frescos. De
estos levantamientos se realiza también la validación en escala real.

Figura 7.06. Imagen de la nube de puntos resultante del levantamiento con escáner láser 3D.

La finalidad de este proyecto a parte del estudio de las precisiones, es resolver un problema
de cuadratura ligado a la bóveda decorada con el fresco del siglo XVII. Esta bóveda presenta un
fresco que ha sufrido algunas pérdidas en el revestimiento y algunas grietas, debido a un

160

<!-- p. 170 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

pequeño asentamiento. Mientras el problema estructural ha sido resuelto mediante un estudio
independiente, cuando se intenta resolver la reintegración de los faltantes decorativos, los
restauradores se encuentran con una necesidad hasta el momento no resuelta. La necesidad de
obtener el diseño del fresco en verdadera dimensión y en 2D.

En general cuando se desarrollan trabajos de levantamiento de bóvedas en 3D, la
presentación en 2D es realizada mediante rectificaciones fotogramétricas. Éstas, sin embargo,
no representan el diseño real cuando la superficie en sí no es un plano. Por lo tanto en el caso de
las bóvedas, y sobre todo en aquellas que presentan frescos como decoración de las mismas,
esta representación no es suficiente.

Así se concluye con la necesidad de un desarrollo de la superficie de la bóveda, en vez de
una definición básica mediante rectificaciones. Sin embargo, el problema es que aparte de las
bóvedas simples (ej. De cañón), existen muchas bóvedas no desarrollables, por ser el resultado
de más de una superficie simple, como se explica en el apartado de la tipología de bóvedas.

El conocimiento de la arquitectura es necesario para poder resolver los problemas
geométricos que surgen una vez tenemos la nube de puntos o la “mesh”: Necesitamos la ayuda
de la Geometría Descriptiva.

Figura 7.07. Imagen de la desviación entre el modelo realizado con Range-based modelling y el de
Image-based Modelling.

Conseguido el desarrollo plano de la bóveda, además se buscará la calidad en la textura de
los modelos digitales obtenidos por los dos métodos, Image-based Modelling y Range-based
Modelling. Se prueban diferentes técnicas para dar al modelo, obtenido a partir del escáner
láser, la mejor textura foto-realista y se realizan diferentes modelos con técnicas de
fotogrametría que se comparan con el modelo de escáner láser, para el cálculo de su precisión y
desviación.

161

<!-- p. 171 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

C. MEDIOS, SISTEMAS Y METODOLOGÍA DE LEVANTAMIENTO

Como se comentaba en el apartado anterior, uno de los objetivos principales de este estudio
es la comparación entre ambos levantamientos para determinar la precisión. Esto en parte se
debe a que también se busca un levantamiento alternativo al escáner láser, además de
complementario.

Para el estudio de esta bóveda, se
realizan levantamientos fotogramétricos
y uno con escáner láser.

El primer reportaje para el
levantamiento fotogramétrico se realiza
con una cámara Nikon D700.

Figura 7.08. Imagen de la cámara Nikon D700

Para que las fotografías tengan la calidad que precisa un levantamiento fotogramétrico. se
deben atender los siguientes parámetros (Cueli López, J.T. 2011):

o Sensibilidad ISO: La sensibilidad ISO cuanto más baja mejor. Cuanto menor es el ISO el
grano es más fino y la nitidez mayor.

o Distancia Focal: Conviene utilizar una distancia focal mínima de 28mm, para una cámara
analógica tradicional, que equivale en el tipo de cámara digital a una de 50 mm. Tiene un
menor ángulo de visión, pero genera menor distorsión y mayor precisión.

o Apertura del diafragma f: Un f bajo produce escasa profundidad de campo (hace que si se
fotografía a una persona, la figura en primer plano salga muy nítida, presentando el
segundo plano difuminado). En el caso de la fotografía para la restitución, sin embargo,
interesa que toda la fotografía esté enfocada, por lo que cuanto mayor sea el número que
divide a la f mejor. f/11, f/16 o f/22 serían los correctos.

o Con los parámetros anteriores el tiempo de exposición aumentará, pero no tiene
importancia porque se usará el trípode para hacer las fotos.

Así se puede concluir que para hacer fotografías nítidas, de buena calidad para una
restitución a partir de imágenes es aconsejable el uso de una distancia focal de 50 mm, una ISO
baja y un factor de división de la “f” alto. De este modo se obtienen fotografías sobrexpuesta
con una calidad buena para el uso de un modelo con textura foto-realista.

162

<!-- p. 172 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

Aunque en una segunda fase se realiza un levantamiento de una calidad mayor debido a
todos los problemas presentados, son diversas las pruebas realizadas con ese primer
levantamiento, como se explica más adelante.

Paralelamente se realiza el levantamiento con escáner láser, para obtener el modelo que
permitirá el estudio preciso de la bóveda, y comparable con los modelos obtenidos con Imagebased Modelling.

Figura 7.09.
Imagen del
escáner realizando
el levantamiento
de la estancia con
la bóveda objeto
de estudio.

i. Láser escáner

Para el levantamiento con escáner láser se realizan dos estaciones, situadas
aproximadamente a 1/4 y a 3/4 en el sentido longitudinal de la sala, y ambas en el centro en
sentido transversal.

Figura 7.10. Planta de la estancia
obtenida con el escáner láser, en la que
se puede deducir las dos zonas de
estación de éste.

163

<!-- p. 173 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

El levantamiento se realiza a alta densidad, 4mm a 10 metros, permitiendo obtener una nube
de puntos muy cuantificada. En una segunda fase, se exportan las nubes de puntos a un
programa de Reverse Modelling (Inus Technology Rapidform XOR3), para su conversión en
mesh.

En el software Cyclone se
realiza la alineación de las nubes
de puntos, que será
prácticamente automática debido
al uso de target. A continuación,
se realiza la eliminación de los
puntos sobrantes y tras ello, se
aísla en un ModelSpace
independiente solo la parte de la
bóveda. A partir de éste, se
efectuará el estudio de la bóveda
para su desarrollo en 2D,
haciendo las secciones en las 3
direcciones perpendiculares y los
screenshot, como se explica más Figura 7.11. Sección vertical de la nube de puntos de la estancia.
adelante.

Paralelamente, se realizará la exportación de la nube de puntos por partes: por un lado se
efectúa un modelo de la estancia completa, a excepción de la bóveda, y por el otro se ejecuta un
modelo de la bóveda, ambos a alto nivel de detalle. Trabajando en Inus Technology Rapidform
XOR3, se pasan las diferentes fases de edición del modelo (conversión a mesh, eliminación de
los polígonos con errores topológicos, relleno de huecos…). Tras los procesos de edición, y
centrándose ya solo en la bóveda, se realiza la “decimation” de ésta para permitir su exportación
a un programa de entertainment, donde se insertará la textura foto-realista a partir de
fotografías.

ii. Levantamiento fotogramétrico para aplicación de la textura

Como ya se ha dicho anteriormente, se realiza un levantamiento fotogramétrico, para la
inserción de la textura foto-realista en los modelos digitales obtenidos a partir de levantamientos
con sensores activos. Se efectúa, como se comentaba, un primer reportaje fotográfico con una
Nikon D700.

Después del reportaje se procede al trabajo de gabinete. El primer paso es la calibración de la
cámara. Se efectúan 2 calibraciones diversas: una con Rigel y otra con PhotoModeler Scanner.

164

<!-- p. 174 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

La calibración a partir de Rigel presenta un problema, se debe ejecutar a partir de un modelo
exacto dado por el programa y éste se debe imprimir a un tamaño preciso y es necesario tener un
plotter calibrado, si no el error de impresión es superior y se añade al error presentado por la
cámara sin calibrar.

En el caso del PhotoModeler la calibración
no presenta ningún problema, dando buenos
resultados y por lo tanto, se concluye como el
mejor método para la calibración.

Solucionado el problema de la calibración
se procede a la corrección de la distorsión en
las fotografías. Sin embargo, esto también
presenta algunos problemas. Las imágenes
corregidas dan errores cuando se realiza su
orientación, necesaria para obtener la posición
Figura 7.12. Calibración de la camara Nikon D700
de la cámara.

También las fotografías corregidas dan problemas al intentar generar el primer modelo
digital 3D realizado con Agisoft PhotoScan, como se ha comprobado en las pruebas realizadas.
Utilizando las mismas fotografías en dicho software, corregidas y sin corregir, los resultados
son totalmente diversos: con las fotografías corregidas el programa no consigue orientarlas,
realizando nubes de puntos sin coherencia, mientras que en el caso de las fotografías sin
corregir, realiza la orientación de las cámaras sin problemas y, por lo tanto, un conjunto de
nubes de puntos con un único e igual sistema de referencia.

iii. Image-based Modelling

Como ya se comentaba, paralelamente a la búsqueda de la inserción de fotografías al modelo
de escáner, se efectúan diferentes pruebas para la obtención de modelos tridimensionales a partir
de fotografías.

Se intenta generar un modelo con Photomodeler Scanner a partir del primer levantamiento,
dando pésimos resultados: las imágenes poco nítidas generan puntos homólogos con una
cantidad de píxeles, como desviación, demasiado alta. Por ello se realizará un segundo
levantamiento, teniendo en cuenta esta vez, lo comentado de los diferentes factores que se deben
impostar para la realización de fotografías.

165

<!-- p. 175 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

Cámara fotográfica Nikon D700 Nikon D600
Objetivo 20 mm 50 mm
Punto f f/2.8 f/16
Tiempo de exposición 1/5 s ½ s
Velocidad ISO ISO-400 ISO-200
Distancia focal 20 mm 50 mm
Apertura máxima 3 1,6

Figura 7.13. Tabla con los parámetros impostados en las cámaras usadas en las dos calibraciones
realizadas.

Se intenta generar también dos modelos con Agisoft PhotoScan, uno con las imágenes
corregidas, que el programa no consigue efectuar, y un segundo con las imágenes distorsionadas
que si saldrá pero obteniéndose una textura con una baja resolución (por las imágenes algo
desenfocadas).

NUBE DE PUNTOS MESH LP
MESH LP + FOTOGRAFIAS HR
TEXTURA HR REAL TEXTURA HR
MESH HP +
TEXTURA HR NUBE DE PUNTOS MESH HP
ESCÁNER LÁSER MESH HP +
TEXTURA LR TEXTURA LP OBJETO

Figura 7.14. Diagrama de la pipeline, donde HR es High-Resolution, LR es Low-Resolution, HP es HighPoly y LP es Low-Poly.

Tras estos resultados se realiza el nuevo levantamiento, que permite generar un modelo en
PhotoModeler “aceptable”. Este modelo como se comenta en el capítulo del estado del arte, es
recomendable si se busca un modelo para el “entertaiment” o para uso como documentación de
la bóveda con una textura de alta calidad, es bastante más económico, menos aparatoso y
requiere un tiempo de trabajo menor. Sin embargo, se debe aclarar que no es un modelo usable
para un estudio estructural o de precisión milimétrica del volumen de la bóveda. Como se puede
observar en la figura 7.15, el modelo presenta bastante ruido, pero la calidad de la textura es alta
(figura 7.16).

166

<!-- p. 176 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

Figura 7.15 y 7.16. Modelo Digital 3D obtenido mediante técnicas de Image-based Modelling. A la
izquierda sin textura, a la derecha con textura.

La generación de este modelo, sin embargo, permite la orientación de todas las fotografías en
un mismo sistema de referencia, dando la posición de las cámaras para cada captura. A partir de
esta orientación de las cámaras, se podrá usar las fotografías para introducir la textura fotorealista al modelo realizado con escáner, exportado en Photomodeler, situando las dos bóvedas
en un único sistema de referencia.

167

<!-- p. 177 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

Figura 7.17 y 7.18. Modelo Digital 3D obtenido mediante técnicas de Range-based Modelling. A la
izquierda sin textura y a la derecha con la textura aplicada a partir de las fotografías en Photomodeler
Scanner.

Además, se genera, utilizando las fotografías del segundo levantamiento un modelo con el
Agisoft PhotoScan. Este modelo presenta una geometría y una textura de alta calidad. Sin
embargo, como se comenta en el apartado del análisis, el problema de este modelo es que la
escala está basada en un solo dato7, y que el tamaño de los triángulos no es directamente
controlable (no es un parámetro que se puede introducir cuando se va a realizar la mesh), de ahí
que la precisión del modelo pueda ser bastante relativa.

Software Cantidad Calidad Cantidad Tipo de Calidad Calidad
utilizado de deseada de geometría de la de la
fotografías polígonos mesh textura
Primer Agisoft 32 Media 200.000 Rasgos Media- Media
levantamiento PhotoScan acusados baja
0.8.2.985
Segundo Agisoft 47 Media 200.000 Rasgos Media- Alta
levantamiento PhotoScan acusados alta
V0.8.3

Figura 7.19. Comparación de los dos modelos generados con Agisoft PhotoScan, utilizando fotografías de
dos levantamientos diferentes y utilizando dos diversas versiones del mismo software.

7 Esta afirmación es relativa, ya que depende de la versión usada del software. En las primeras versiones
del software (Agisoft PhotoScan 0.8) la escala del modelo solo se podía introducir a partir de un dato. En
las versiones posteriores (Agisoft PhotoScan 0.9) se introduce una mejora en el software permitiendo
introducir la cantidad deseada de puntos de control, que además pueden ser metidos en un sistema de
coordenadas definido, conociendo de antemano las coordenadas de dichos puntos de control. La
generación de dichos modelos se realizan con las versiones 0.8, que aún no permiten introducir diferentes
datos para escalar el modelo.

168

<!-- p. 178 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

D. TRATAMIENTO DE LOS DATOS.

NECESIDAD DE LOS RESTAURADORES DE TENER LA REPRESENTACIÓN
“DESARROLLADA” DE LAS BÓVEDAS.

Las nuevas tecnologías avanzadas son usadas difusamente tanto globalmente para el
levantamiento complejo histórico arquitectónico en su conjunto, como localmente para el
levantamiento de su aparato decorativo y de detalles arquitectónicos. Entre estos, las
decoraciones pictóricas (frescos, pinturas superficiales en general, etc.) constituyen los
elementos a veces más significativos pero ciertamente más frágiles, hacia los cuales se
direcciona la atención constante de todas las profesiones que con diferente especialidad están
interesadas en la programación y en la realización de intervenciones de restauración y
conservación (arquitectos, gestores, técnicos, historiadores del arte, restauradores, etc.).

Si en el pasado las técnicas de restauración del aparato pictórico se basaban en sistemas de
investigación tradicionales a vista, hoy con la llegada de las nuevas tecnologías digitales es
posible obtener un dato objetivo, tridimensional y geométricamente correcto, al cual es posible
referir todos los resultados de las diferentes tipologías de investigación. El levantamiento
térmico, por ejemplo, proporciona índices útiles para describir la situación de deterioro o
conservación de las superficies murales decoradas, poniendo en evidencia la presencia de
patologías superficiales presentes en los muros, unido a fuertes transiciones termohidrométricas; la integración entre el dato térmico y el métrico a mayor resolución es después
esencial para una representación y mapeado preciso del deterioro. Las nuevas tecnologías han
dado por lo tanto un fuerte impulso a la catalogación digital, a la documentación de las
decoraciones pictóricas y al monitoreo de su estado de conservación, y la disponibilidad de los
modelos virtuales constituye ya un indispensable instrumento de valoración del patrimonio
figurativo.

Si por un lado las nuevas tecnologías han determinado una sustancial innovación en las
técnicas de diagnósticos, por el otro, debe entenderse que la parte operativa de la restauración
queda y debe quedar por su naturaleza fuertemente unida a las técnicas tradicionales pictóricas.
Al restaurador, de hecho, se le pide la manualidad “di bottega” (de taller), o lo que es lo mismo
el conocimiento de las técnicas y la capacidad de aplicarlas en la realización de la decoración, al
mismo nivel de los artistas que en el pasado aprendían la técnica de pintura al fresco en talleres
de arte. También el cierre de una pequeña laguna, por ejemplo, requiere toda una serie de
operaciones, desde la investigación del diseño sobre papel y la preparación de la superficie hasta
la aplicación del color; operaciones que, como en el pasado, se resuelven en el tiempo en el cual
se completaba el proceso de carbonatación del yeso.

Parece claro, por lo tanto, que es en el paso desde la fase cognoscitiva y de investigación a la
fase operativa, donde a las nuevas tecnologías se les pide interconectarse e integrarse con las
técnicas tradicionales y metodologías de intervención.

169

<!-- p. 179 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

Por estas razones, los restauradores, aunque pueden visualizar en ámbito virtual el bien en su
tridimensionalidad y consultar y gestionar la información a él asociada, requieren, sin embargo,
poder planificar las intervenciones sobre representaciones planas convencionales del fresco
impreso sobre soportes de papel o similares.

Si para las pinturas parietales, generalmente localizadas sobre superficies planas o a ejes
aproximables, el problema es fácilmente resoluble con los instrumentos que los softwares en
comercio ya tienen para la generación automática de representaciones proyectivas ortogonales,
la cuestión aparece más compleja en el caso en el cual las pinturas están situadas sobre
superficies de intradós de estructuras abovedadas.

En las obras de restauración, los operarios necesitan, de hecho, poder trabajar sobre
elaborados gráficos que reporten las proporciones en verdadera magnitud de las superficies
abovedadas pintadas. En el caso de una bóveda de cañón, por ejemplo, la representación es
generada por el “desarrollo” de la superficie cilíndrica de la bóveda y de la sucesiva
representación en verdadera magnitud sobre el plano horizontal. Tal necesidad aparece más
urgente a la luz del hecho de que también los estamentos encargados de la protección del
patrimonio histórico, con frecuencia requieren de este tipo de representación para la
documentación del estado de las pinturas y de los proyectos de restauración.

A la luz de cuanto se ha dicho, se hace necesario definir una metodología de trabajo que, a
partir de un levantamiento con escáner láser tridimensional de la superficie abovedada, permita
la generación de las proyecciones en verdadera magnitud como en el caso de la bóveda de
cañón, limitando el trabajo que por vía gráfica es necesario para la reconstrucción geométrica de
la superficie sobre el plano y la sucesiva proyección de la imagen de la pintura.

PANORAMICA SOBRE VARIAS TIPOLOGÍAS DE BÓVEDAS. GEOMETRÍAS
IDEALIZADAS DE PROYECTO

La bóveda ha ocupado un puesto preeminente en las arquitecturas del pasado, resolviendo un
conjunto de problemas espaciales, volumétricos, estéticos y constructivos, que los primitivos
sistemas trilíticos no habían satisfecho plenamente.

Las bóvedas se encuentran en la arquitectura en una amplia gama de soluciones constructivas
e interpretaciones arquitectónicas, a menudo majestuosas y brillantes como para crear un
sentido de admiración y asombro. Muestra de ello son las primordiales bóvedas de cañón, como
cobertura de los ambientes asirio-caldea, las grandiosas bóvedas de romanas, con o sin monturas
de ladrillo, las cúpulas semiesféricas bizantinas de terracota, las bóvedas encasetonadas
dispuestas en una espiral de los sistemas bizantino-latinos, los imponentes complejos arcos
abovedados románico-góticos, las ingeniosas cúpulas dobles y las bóvedas con lunetos del
Renacimiento, del seiscientos y del setecientos, hasta la ardita bóveda de rincón de claustro del
ochocientos de la Mole Antonielliana, en Turín.

170

<!-- p. 180 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

Formalmente, las bóvedas pueden ser divididas en dos grupos, bóvedas simples y bóvedas
compuestas. Las primeras son construidas por superficies únicas, por lo que la superficie del
intradós aparece continua y sin bordes o ángulos entrantes. Las segundas, sin embargo, derivan
de la asociación de más bóvedas simples, las cuales intersectándose o uniéndose entre ellas,
forman sobre el intradós bordes o ángulos, que rompen el sentido de continuidad y de
uniformidad que se revela entre las otras. Resulta, en consecuencia, un aspecto mucho más
variado y complejo.

Con referencia a su raíz geométrica, son pertenecientes al grupo de bóvedas simples:

\1. Las bóvedas de cañón o cilíndricas. Son
generadas por una común superficie cilíndrica.
Éstas tienen como sección recta un arco a pleno
centro o rebajado, elíptico, policéntrico, etc.,
que representa la curva directriz, mientras las
generatrices son paralelas a las líneas de
imposta. Son por lo tanto delimitadas por dos
arcos frontales (o de pared) y de la línea de
imposta. Las bóvedas de cañón pueden ser
también inclinadas si son inclinadas sus líneas Figura 7.20. Bóveda de cañón (De la Plaza
de imposta, así como ocurre, por ejemplo, en los Escudero, L., 2008: 115)
vanos de las escaleras; o, como ocurre en los
arcos, cuando son rampantes, si tienen las
impostas situadas a diferente altura.

Figuras 7.21 y 7.22. Imágenes de bóvedas cilíndricas. A la izquierda, bóveda de cañón inclinada para
sujetar una escalera encasada. A la derecha, Bóveda rampante para sostener una escalera exenta (Pera L.,
1987: 63).

171

<!-- p. 181 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

\2. Las bóvedas anulares y helicoidales.
Pueden considerarse como las
bóvedas de cañón, con la diferencia
de que las líneas de imposta han
asumido la forma de círculos
concéntricos, o de dos hélices de
paso y de ejes comunes.

\3. Las bóvedas semiesféricas o cúpulas.
Tienen por intradós superficies de
revolución esféricas o elipsoides.
Éstas pueden ser completas o
incompletas, según sean constituidas
de semiesferas o de semielipsoides.

Figura 7.23 y 7.24. A la izq., bóveda anular y bóveda
helicoidal. A la derecha, bóveda semiesférica (Pera L.,
1987: 64-65).

\4. La bóveda vaída. Proveniente de las cúpulas y
originada de la intersección de éstas con los planos
verticales conducidos por los lados de un cuadrado o de
un rectángulo inscrito en la planta de la bóveda de
origen. Por su forma es apropiada para cubrir espacios
cuadrados.

Figura 7.25. Bóveda vaída (De la
Plaza Escudero, L., 2008: 119).
\5. Las bóvedas cónicas o conoidales (figura 7.26). Formadas de las análogas superficies
geométricas y empleadas para cubrir ambientes en planta circular o poligonal con un gran
número de lados, así de poder considerarse como circular. Se encuentran interesantes
aplicaciones bajo forma de porciones, como elementos de recuerdo en las cúpulas o como
cubierta de ambientes en planta trapezoidal.

172

<!-- p. 182 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

Figuras 7.26 y 7.27.
A la izquierda,
bóveda cónica sobre
planta trapezoidal. A
la derecha, Bóveda de
rincón de claustro
sobre planta
rectangular (Pera L.,
1987: 69).

Las bóvedas compuestas derivan, como se ha dicho, de la asociación de partes de bóvedas
simples, generalmente de raíz cilíndrica o cónica o en algún caso esférica. Éstas pueden ser
distinguidas en:

\1. Bóveda de rincón de claustro (figura 5.27). Originada por la intersección de más bóvedas de
cañón, o mejor de la asociación de más husos cilíndricos, tomado un número correspondiente
a los lados que forman la planta del ambiente a cubrir. Las líneas de intersección sobre la
superficie de intradós, definidas por arcos diagonales, son curvas planas, cuya proyección, en
planta, es representada por líneas rectas que se unen en el centro geométrico del polígono de
imposta con los ángulos individuales. Por tal razón, los arcos diagonales se encuentran en los
planos verticales proyectados en las diagonales de la planta, los husos tienen la misma
montea y un sexto tal que las curvas que delimitan cada uno de ellos coinciden exactamente
con los de los husos adyacentes, a fin de ser común entre ellos.
En las bóvedas de rincón de claustro, por lo tanto, la línea de imposta está constituida por
redes horizontales, encontrándose en un mismo plano y formando el polígono base, mientras
las generatrices de cada huso, son paralelas al respectivo lado de imposta.

173

<!-- p. 183 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

\2. Bóveda de aljibe. Se utiliza generalmente en
ambientes cuadrangulares (rectangulares o
trapezoidales). Éstas provienen de la
intersección de bóvedas de cañón, de la cual una
principal, impostada sobre los lados largos del
polígono de base, y dos menores, impostada
sobre los lados cortos, que forman los lunetos.
\3. Bóveda esquifada, constituida de cuatro husos
cilíndricos de igual monta y sesto, impostados
sobre los lados del ambiente y conectado de
forma centralizada por una superficie
ligeramente curva, dicha espejo. Ésta tiene
analogía con las bóvedas de rincón de claustro o
de cañón con lunetos, y es utilizada
habitualmente con fin decorativo, como bóveda
fingida, para cubrir grandes ambientes.

Figuras 7.28 y 7.29. Arriba, bóveda de aljibe.
Abajo, bóveda esquifada (Pera L., 1987: 71-
72).

DIFERENCIAS ENTRE SUPERFICIES DESARROLLABLES E NO DESARROLLABLES.

Como dicho en precedencia, en las usuales operaciones de levantamiento de superficies
abovedadas pintadas es buscado habitualmente la producción de elaborados gráficos que
representan el desarrollo plano de las superficies de intradós, con el fin de poder documentar las
figuraciones pictóricas en verdadera magnitud.

Dicha operación es aplicable, en línea general, a todas las superficies geométricamente
desarrollables y como tales referibles a raíces cilíndricas o cónicas o troncocónicas.

En línea teórica, el desarrollo del cilindro y del cono es posible según reglas geométricas
bien definidas. Las superficies laterales de un cono o un cilindro, de hecho, tendido sobre
superficies de revolución generadas por una línea recta, pueden ser representadas en el plano
“desarrollándolas” a lo largo de un arco de amplitud apropiada.

174

<!-- p. 184 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

En este modo, el desarrollo de
una superficie cilíndrica está
constituido por un rectángulo que
tiene la base igual a la longitud de la
curva directriz y la altura igual a
aquel del cilindro mismo (fig. 7.30).

Por cuanto se refiere al cono, su
desarrollo está definido por un
sector circular que se obtiene
desarrollando sobre el plano su área
lateral y que tiene el radio igual a la
apotema del cono y el arco largo Figura 7.30. Desarrollo en 2D de un cilindro8
cuanto la circunferencia de base.
(fig. 7.31)

Sobre la base de estas suposiciones y de la clasificación precedente, el problema del
“desarrollo” sobre el plano es geométricamente solucionable para las superficies de intradós de
las bóvedas de cañón, cónicas o conoides y de todas las bóvedas compuestas que presentan
raíces geométricas cilíndricas o cónicas, como las bóvedas de rincón de claustro, de aljibe,
esquifadas.

Figura 7.31 y 7.32. Imágenes del desarrollo de conos en 2D.9

8 http://www.sergiosimone.it/public/upload/arearecords/287/Lo%20sviluppo%20dei%20solidi.pdf (última
consulta: 13/11/2013)

9 http://www.sergiosimone.it/public/upload/arearecords/287/Lo%20sviluppo%20dei%20solidi.pdf (última
consulta: 13/11/2013)

175

<!-- p. 185 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

E. ANALISIS

DESARROLLO DE LA BÓVEDA

Como ya se ha subrayado anteriormente, la bóveda esquifada no representa una superficie
directamente desarrollable. Ésta, sin embargo está constituida por porciones de geometrías
elementales, en particular, cilindros unidos entre ellos.

En primer lugar, se han buscado estas
geometrías elementales para determinar
la desviación del modelo ideal con
respecto a la bóveda real. Con este fin
han sido aisladas las nubes de puntos
parciales que, siguiendo líneas de
separación teóricas, deberían pertenecer a
porciones de diversos cilindros. En
principio se han separado las dos
“Faldas” cortas de las largas siguiendo
Figura 7.33. Imagen de la bóveda dividida en 6 partes o
las líneas individualizadas visualizando, porciones.
desde la vista cenital, el modelo
seccionado a través de planos a un paso
pequeño.

Las “faldas” separadas son teóricamente constituidas de la unión de dos porciones de
cilindros de diferente radio (menor en la porción más cercana a la imposta de la bóveda y mayor
en la más cercana a la cumbre). La línea de separación teórica de las dos porciones se encuentra
aproximadamente a un tercio de la bóveda a partir de la imposta.

Separando, por lo tanto, la parte baja de la bóveda de aquella de la cumbre, se han obtenido
seis nubes de puntos parciales, cada una de las cuales teóricamente representa una parte de
cilindro (figura 7.33).

Utilizando instrumentos de interpolación han sido identificados los cilindros que mejor se
aproximan a las porciones de nubes de puntos obtenidas.

Tomando por ejemplo la “falda” larga, los dos cilindros que la componen tienen como radio
7,349 metros el de la cumbre y 5,280 metros el de la base de imposta. Además, para ambos
cilindros la desviación estándar respecto a la nube de puntos es del orden de 7mm (figura 7.34).
Resultados análogos se han obtenido para las otras “faldas”.

176

<!-- p. 186 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

Figura 7.34. Nube de puntos de la bóveda con los cilindros que más se aproximan a ésta.

Ha sido, además, verificado que la bóveda objeto de estudio sigue con buena aproximación
la geometría teórica de las bóvedas esquifadas. En la evaluación de los valores de desviación
estándar obtenidos debe
también considerarse que,
respecto al modelo
teórico, la bóveda real no
tiene transiciones netas
entre los cilindros y las
“faldas” contiguas ya que
la transición adviene
gradualmente. De hecho,
los valores máximos de la
diferencia entre superficie
real e ideal se encuentran Figura 7.35. Imagen de la desviación de los cilindros con respecto a la
en estas zonas de bóveda
transición (figura 7.35).

177

<!-- p. 187 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

El cilindro constituye una superficie desarrollable y varios software de modelación
tridimensional permiten desarrollarlo una vez definido en base a sus ejes y su radio.

En el caso de la bóveda decorada con un fresco, sin embargo, no se trata de desarrollar una
superficie puramente geométrica, privada de textura. Después de haber realizado diferentes
pruebas, haber utilizado diversos software y haber consultado a algunos expertos, se afirma que
no se ha encontrado un software de reverse modelling que sea capaz de desarrollar una
superficie cilíndrica manteniendo la textura aplicada a alta definición.

Además, desde el punto de vista puramente métrico, si se desarrollase la superficie cilíndrica
se idealizaría la bóveda con un modelo teórico y no se mantendrían las distorsiones reales
respecto al modelo. La geometría real podría ser representada mejor por un modelo mesh a
triángulos. Sin embargo, tal modelo resultaría una superficie no desarrollable directamente. Al
máximo se podría pensar en proyectarla sobre una superficie desarrollable (cilindro, plano,
cono…) evaluando las inevitables distorsiones.

Se ha optado por seguir una metodología que, aunque se caracteriza por un grado menor de
automatización, tiene una mayor consideración sobre la forma real de la bóveda.

Primero, a partir de haces de planos a paso constante de 20 cm con las normales paralelas a
los ejes coordenados, se han generado tres familias de secciones (figuras 7.36 y 7.37).

Figuras 7.36 y 7.37. A la izquierda imagen de la bóveda con las tres familias de secciones. A la
derecha imagen de las polilíneas creadas a partir de las secciones.

Las secciones obtenidas son polilíneas tridimensionales definidas en el mismo sistema de
referencia de la nube de puntos. Las polilíneas han sido, después, exportadas en ambiente CAD
donde se ha obtenido manualmente el desarrollo del plano de la bóveda, representado por las
polilíneas mismas.

178

<!-- p. 188 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

En particular han sido utilizadas
para el desarrollo las polilíneas
representantes de las secciones
horizontales. Se ha hecho la
suposición de que entre una línea de
sección y la otra la bóveda tuviese un
recorrido plano. Tal suposición
encuentra justificación en el hecho
que, siendo las secciones hechas a
paso de 20 cm, la diferencia de
longitud entre la cuerda y el arco Figura 7.38. Imagen en la que se puede comprobar la
delimitante entre dos secciones desviación entre el arco real que forma la sección entre un
contiguas es del orden de pocos paso de 20 cm y la cuerda usada. Medidas en milímetros.
centímetros (figura 7.38).

Así, partiendo de la línea de colmo
de la bóveda, identificada en la vista
desde el alto de las secciones
horizontales a paso pequeño (las
mismas utilizadas para individualizar
las diferentes porciones de la bóveda),
han sido medidas, en el modelo
tridimensional a secciones, las
distancias entre los extremos de las
líneas de secciones sucesivas y
reportadas en el plano. Al mismo
tiempo ha sido posible introducir en el
desarrollo también las secciones
obtenidas con los planos verticales.
(figura 7.39)

Las secciones han sido utilizadas
para la superposición de la textura en el
desarrollo de la bóveda. Se han elegido
Figura 7.39. Imagen de la planta de las secciones
cuatro direcciones, respecto las cuales
horizontales y del desarrollo de las secciones en 2D a partir
impostar una vista ortográfica del del proceso comentado en la columna de la izquierda.
modelo. Las direcciones son
ortogonales a los ejes de los cilindros e inclinadas a 0º, 30º, 60º y 90º respecto al plano de
imposta de la bóveda.

179

<!-- p. 189 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

Por cada dirección de visualización se han salvado las imágenes del modelo (nube de puntos
colorada o modelo texturizado) de una porción de la bóveda incluida en un ángulo de 30º, como
está evidenciado en la figura 7.40.

Figura 7.40 y figura 7.41. A la izquierda, imagen de la disposición de las vistas para hacer los
screenshot. A la derecha, imagen que permite comparar la desviación entre la proyección ortogonal y la
real. La figura 8P presenta sus medidas en metros.

Las imágenes así obtenidas son una proyección ortogonal de la textura de la bóveda sobre el
plano. Contienen por lo tanto una distorsión lineal. La deformación lineal relativa resulta poco
superior al centímetro en las zonas de la bóveda más desfavorables, y por lo tanto, con curvatura
mayor (figura 7.41).

Tal precisión permite realizar elaborados en escala 1:50 e inferiores. En el caso de que
hubiese necesidad de producir elaborados en escala mayor sería necesario aumentar las
direcciones de visualización.

Por cada posición de visualización del modelo texturizado se producen dos imágenes, una
con las secciones visibles y una que solo presenta la textura (figura 7.42).

Figura 7.42. y 7.43 Imágenes de uno de los screenshot con y sin secciones.

180

<!-- p. 190 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

PROCEDIMIENTO DE ALINEAMIENTO EN PHOTOSHOP

Obtenido el desarrollo del esqueleto de la bóveda en Autocad y los screenshot capturados en
el Cyclone, se traspasa toda esta documentación a Photoshop para su elaboración.

En primer lugar, se abre el esqueleto de la bóveda y se pone como fondo de referencia. A
continuación se colocan los screenshots con y sin sección, enlazándolos entre ellos (los que son
similares a excepción de las secciones presente en uno sí y en el otro no), de modo que la
deformación aplicada a uno se refleje igual en el otro. Después siguiendo las secciones del
esqueleto como referencia, se utilizarán los screenshot con secciones para adaptarlos a la forma
real (la del esqueleto). Haciendo esto con cada uno de ellos se obtiene como resultado la bóveda
“desarrollada” en 2D.

Figura 7.44. Imagen del proceso de apertura de la bóveda en Photoshop a partir de su esqueleto realizado
en Autocad y de los screenshot capturados en Cyclone 7.

181

<!-- p. 191 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

Figura 7.45. Imagen final de la apertura de la bóveda a partir de los screenshot realizados a la nube de
puntos en el Cyclone.

PROCESO DEL MODELO DE ESCANER LÁSER PARA LA INTRODUCCIÓN DE LA
TEXTURA FOTOREALISTA

Paralelamente al proceso de apertura de la bóveda, se trabaja en el modelo exportado al
Rapidform XOR3. Dicho modelo, una vez editado, será exportado en Luxology Modo 501 para
la aplicación de la textura foto-realista. Para éste proceso es necesario el uso de 3 programas
diferentes: el Rapidform XOR3, el Photomodeler Scanner y el Luxology Modo 501.

En primer lugar, se escogen una serie de fotografías, lo más perpendicular posible a la zona
que debe cubrir cada una, y el número necesario para cubrir toda la bóveda, eliminando de la
fotografía las partes que generan demasiada distorsión.

Una vez seleccionadas las fotos, se realiza un proceso similar para cada fotografía. Este
consiste en:

1º. Se escogen puntos en el modelo del escáner láser, en el Rapidform XOR3, en la zona
común a la fotografía que se va a usar, con una distribución lo más homogénea posible.
2º. Estos puntos en 3D se exportan y se abren en el software PhotoModeler Scanner.

182

<!-- p. 192 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

3º. Se introduce la fotografía en el PhotoModeler Scanner y se buscan los puntos homólogos
en la fotografía con respecto a los seleccionados en el Rapidform XOR3.
4º. Una vez relacionados los puntos se calcula y se obtiene la posición de la cámara.
5º. Situada la cámara, ésta se exporta al Luxology Modo.

Independientemente de este proceso, exportado el modelo desde Rapidform XOR3 a
resolución media, se calcula el modelo de superficies de subdivisión y, al igual que en el 2º caso
de estudio, se calculará su UV Map (figura 7.46).

Figura 7.46. En esta imagen se puede observar el UV Maps del modelo de superficies de subdivisión de la
bóveda y la bóveda con la proyección de una de las fotografías.

183

<!-- p. 193 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

Continuando con el proceso anterior, se
exporta la cámara de cada una de las
fotografías, una a una, y se calcula el UV
Map con la proyección de la imagen (figura
7.47).

Con los UV Maps de cada fotografía, se
abren en Modo, y se realiza un “collage”,
obteniendo de este modo un UV Map
completo (figura 7.48)10.

Figura 7.47. UV Map de una de las fotografías.

10 Debe comentarse que debido a que las fotografías son del primer levantamiento fotográfico, y que
como se comentaba, presentan demasiada deformación, es necesario la deformación de algunas
fotografías para conseguir la continuidad entre los diferentes UV Maps.

184

<!-- p. 194 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

Figura 7.48. UV Map resultado de la combinación de las UV Map “parciales”.

Arreglada la imagen, ésta se aplica en Modo y se obtiene la bóveda resultado del
levantamiento con escáner láser, pero con una textura fotorealista, a partir de las fotografías
(figuta 7.49). Debe comentarse que en el proceso de la obtención del “collage” es necesario
modificar entre las fotografías factores como la iluminación, la saturación, etc. para obtener una
imagen continua.

185

<!-- p. 195 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

Figura 7.49.
Render de la
bóveda con
la aplicación
de la textura
foto-realista.

186

<!-- p. 196 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

CILINDROS PARA EL “DESARROLLO” DE LA BÓVEDA EN 2D

Como se comentaba anteriormente, se contempla otra posibilidad para el “desarrollo” de la
bóveda de un modo más automático: a partir de cilindros.

Debe comentarse, que aunque se considera que el método más preciso para la obtención de
la bóveda “desarrollada” en 2D es la explicada anteriormente de forma manual, se realizan
pruebas para intentar obtener dicho “desarrollo” de un modo más automatizado.

Para ello se realiza la búsqueda de los cilindros ideales a partir de los cuales se forma la
bóveda objeto de estudio. La primera prueba realizada parte del diseño de los cilindros en el
programa Cyclone. Obtenidos estos cilindros, se intentan “abrir” en Rhinoceros, software que
permite dicha apertura, para los cilindros resultado de un modelo NURBS. Al intentar dicha
apertura, se comprueba que ésta no es posible porque los modelos realizados por Cyclone son
numéricos, no matemáticos.

Comprendido esto, se utiliza los parámetros que definen los cilindros de Modo, para generar
dichos cilindros en Rhinoceros, de modo que estos, en una segunda fase se puedan “abrir” o
“desarrollar”. Estos cilindros son exportados al PhotoModeler Scanner para su orientación y
proyección de la textura. Sin embargo, una vez obtenidos los cilindros texturizados, se descubre
que en la exportación, a pesar de utilizar formatos compatibles con el traspaso de la información
de la textura, igualmente pierden dicha información. Se prueban diferentes formatos, como por
ejm. “.obj”, “.3dm”, pero el resultado es siempre el mismo, por lo que finalmente se descartan
los cilindros como una opción viable.

Figura 7.50. Imagen de los dos cilindros ideales unidos que formarían las faldas más largas de la bóveda,
con la proyección de una de las fotografías que formaría la textura de éstos.

187

<!-- p. 197 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

F. MODELOS OBTENIDOS.

En el caso de estudio, en concreto, la bóveda esquifada en sentido longitudinal es el
resultado de la combinación de dos cilindros de diverso diámetro. Estos cilindros se buscan
mediante una investigación minuciosa: estudiando las bóvedas de la época, la metodología de
construcción… Tras dicho estudio, se busca en la bóveda escaneada los dos cilindros que
definen la bóveda objeto de estudio. Una vez comprendido esto se procede a la apertura de estos
cilindros. Sin embargo, se presentan diferentes problemas al intentar realizar esta apertura o
desarrollo en los diferentes programas de 3D conocidos y utilizados por diferentes
investigadores (Remondino, 2012; Bertocchi, 2012) de la materia. Después de diferentes
pruebas se concluye que estos programas no son capaces de realizar dicho desarrollo con una
medida precisa de desviación de la textura.

Así que se decide volver a la metodología geométrica no automática, realizando una apertura
utilizando secciones realizadas cada 20 cm en las 3 direcciones de los ejes. A partir de estas
secciones se realiza una apertura manual creando “el desarrollo” del “esqueleto” de la bóveda en
2D. Después se hacen screenshot de la bóveda con y sin las secciones (en Cyclone), utilizando
diferentes planos (a 0º, 30º, 60º y 90º) buscando ser lo más paralelo posible a la bóveda,
comprobando que la diferencia máxima entre la distancia real y la que puede venir representada
es de 5 cm, y solo en los casos más desfavorables (las zonas transición o de cambio de plano).
Así utilizando las imágenes con secciones y legando a estas las otras se reconstruye el diseño
del fresco en verdadera dimensión.

Figura 7.51. Imagen de los planos tangentes usados para el “desarrollo” de la bóveda.

188

<!-- p. 198 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

Utilizando el mismo método que para la apertura de la bóveda en 3D con la textura de la
nube de puntos obtenida con el escáner, se realiza la apertura de la bóveda texturizada con
fotografías a partir del modelo de superficies de subdivisión.

Se utiliza el esqueleto obtenido en Autocad, mediante la “apertura” manual, y haciendo en
Luxology Modo “rendering” de la bóveda con y sin secciones, como se efectúa en el caso
anterior, y en las 4 inclinaciones comentadas (0º, 30º, 60º y 90º) se obtiene una bóveda abierta
con una calidad visual de la textura mayor.

Figura 7.52.
Proceso de la
apertura de la
bóveda con
textura foto-
realista, a partir
de las
fotografías del
primer
levantamiento.

189

<!-- p. 199 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

Figura 7.53. Imagen de la bóveda con textura foto-realista “desarrollada”

Una vez realizado el
fresco en 2D, de ambas
bóvedas, se efectúa la
comprobación in-situ de
algunas imágenes
(impresiones en A1, de
partes del fresco, con papel
traslucido). Se comprueba
que la coincidencia de las
imágenes imprimidas de la
textura del modelo hecho
con escáner láser es total.
Sin embargo, no se obtiene
el mismo resultado en el
Figura 7.54. Imagen de la comprobación in situ de los A1 imprimidoscaso del modelo hecho con
del desarrollo de la bóveda en 2D.fotogrametría con fotos
individualizadas.

Este resultado en parte ya se esperaba, ya que cuando se intentan unir las diferentes partes de
la textura resultado de cada imagen, las coincidencias en las zonas de unión no son al 100%. A
partir de este resultado, se buscan alternativas en fotogrametría, ya que si bien, la textura del

190

<!-- p. 200 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

modelo del escáner es perfecta, no lo es tanto el color, debido a la resolución que tienen las
fotos del escáner que es de una calidad media.

Partiendo de esta premisa, se hacen diferentes pruebas de textura, intentando conseguir una
calidad lo más alta posible, para presentar una imagen de alta calidad que permita a los
restauradores trabajar con fidelidad y precisión. En estos trabajos, se utilizan diferentes técnicas
de fotogrametría que darán resultados diversos, presentando la necesidad de compararlos hasta
llegar al resultado, según nuestra opinión, más completo.

Realizado el segundo levantamiento fotográfico, éste se utiliza, como se comentaba para
generar un modelo digital tridimensional. Se realiza con PhotoModeler. Presenta un color en la
textura de alta calidad, pero como se comentaba la precisión geométrica no es la adecuada para
un estudio de precisión milimétrica, ya que presenta demasiado ruido. Sin embargo, en este
caso, se observa que existe una continuidad en la textura a nivel de las imágenes que son
representadas en el fresco de la bóveda, cosa que no sucedía cuando se orientan las fotografías
en PhotoModeler de forma individual para obtener la textura para el modelo del escáner.

Figura 7.55 y 7.56. Imágenes de la bóveda obtenida con escáner láser. A la derecha textura de la nube de
puntos coloreada con las fotos que realiza la cámara que tiene integrado el escáner. A la izquierda textura
a partir de las fotografías del segundo levantamiento en el que se pueden ver las partes que se toman de
cada fotografía, por presentar una irregularidad con respecto a la iluminación, sin embargo presenta una
continuidad de los dibujos que la forman.

191

<!-- p. 201 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

Considerando esta cuestión se toma la opción de orientar la bóveda del escáner con respecto
a la generada con PhotoModeler. Para ello se importa la bóveda de PhotoModeler al Rapidform
y se orienta la bóveda del escáner para meterla en el mismo sistema de referencia. Una vez
situada en ese sistema de referencia, ésta se exporta al PhotoModeler. Teniendo la bóveda
generada por el escáner orientada y a la misma escala, es posible proyectar las fotografías que se
han utilizado para generar el modelo digital tridimensional con PhotoModeler. De este modo se
consigue el modelo más completo: un modelo geométricamente modelado a partir de la nube de
puntos del escáner láser y con una textura de alta calidad, a partir de las fotografías tomadas en
el segundo levantamiento fotográfico (figura 7.56).

Debe comentarse también,
que el modelo obtenido por
Agisoft PhotoScan aunque no
presentaba una buena textura
debido a las fotografías (del
primer levantamiento), la
calidad del modelo a nivel
geométrico es bastante
superior al modelo realizado
con PhotoModeler (figura
7.57). Así que al hacer el
modelo con las fotografías del
segundo levantamiento se
obtiene un modelo con alta
calidad geométrica y de
textura. Como se puede
observar en la figura 7.59, en
la cual se compara con el
modelo del escáner, la
desviación media de la bóveda
es de 5mm. El problema de
este programa sigue siendo la
imposibilidad de controlar
algunos parámetros, como por Figura 7.57 y 7.58. Imágenes de la bóveda obtenida con PhotoScan
ejemplo, el tamaño de los con y sin textura de color.
polígonos, o el que la escala
del modelo se base
exclusivamente en una
medida11.

11 Debe recordarse que esta afirmación se realiza sobre una versión específica del programa, como se
comenta a lo largo de la tesis.

192

<!-- p. 202 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

Figura 7.59. Programa Rapidform XOR3 en el momento de la comparación entre el modelo de escáner y
el modelo del PhotoScan.

G. RESULTADOS

Por un lado, se obtiene el “desarrollo” de la bóveda, que era uno de los objetivos principales,
con un precisión milimétrica, comprobada in-situ, a partir del modelo de nube de puntos. Por lo
que se puede confirmar, que el método de desarrollo de la bóveda es correcto y que la precisión
del escáner para este estudio es totalmente adecuado.

Por otra parte podemos concluir que el uso de
fotografías aisladas para la integración de la
textura foto-realista, no ha dado un buen
resultado, ya que en la comprobación in-situ de
éstos, los dibujos son en parte no coincidentes,
presentando pequeñas desviaciones. Esta
consideración, además, ya era previsible, debido a
que como se observa en la imagen de la derecha,
cuando se estaban uniendo las diferentes partes de Figura 7.60. Imagen del proceso de unión
la textura obtenidas con el UVMap de cada de las diferentes partes de la textura fotofotografía individual, se encontraban realista para la composición de una única.
discontinuidades, que se resuelven uniendo las
imágenes en la zona de superposición
coincidente.

193

<!-- p. 203 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

Se realiza un cuadro comparativo en Excel (figura 7.62), con las dos texturas, tomando como
correcta la textura “desarrollada” del modelo de nube de puntos, y a partir de ahí haciendo una
medición de la otra para calcular su desviación. Marcando una alta cantidad de puntos (171),
repartidos por toda la bóveda, con una distribución lo más homogénea posibles (teniendo en
cuenta que debe ser mediante dianas naturales, puntos reconocibles claramente), se obtiene una
desviación media, en valores absolutos, con respecto a la distancia de 0.071 metros, con
respecto al ancho 0.018 metros y con respecto al alto de 0.057 metros.

Figura 7.61. Imagen parcial de las dos texturas sobrepuestas, que se han usado para calcular la desviación.

Medidas a Escala 1:20
Puntos Angulo Distancia Ancho Alto
1 -79,40 4,61 0,85 4,53
2 -70,90 4,26 1,39 4,02
3 -61,70 3,43 1,62 3,02
4 -61,90 2,73 1,29 2,41
5 -51,40 1,96 1,23 1,53
6 -39,40 1,74 1,34 1,10
7 -23,70 0,64 0,58 0,26
8 -170,60 0,92 -0,91 0,15
9 -143,00 2,47 -1,98 1,49
10 -107,00 2,50 -0,73 2,39
11 -83,70 4,20 0,46 4,17
12 -137,70 0,80 -0,59 0,54
13 -78,80 2,45 0,48 2,40

194

<!-- p. 204 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

14 -91,70 1,78 -0,05 1,78
15 -84,30 0,90 0,09 0,89
16 -112,20 1,26 -0,48 1,16
17 -69,30 0,62 0,22 0,58
18 -102,70 0,44 -0,10 0,43
19 38,70 0,11 0,09 -0,07
20 -45,70 2,03 1,42 1,46
21 -44,50 2,20 1,57 1,54
22 -71,10 0,98 0,32 0,93
23 -84,10 2,90 0,30 2,88
24 11,30 0,22 0,22 -0,04
25 -82,50 1,97 0,26 1,95
26 -70,60 2,81 0,93 2,65
27 -89,60 2,69 0,02 2,69
28 -107,30 2,49 -0,74 2,37
29 -80,00 2,38 0,41 2,34
30 -76,40 2,13 0,50 2,07
31 -117,60 1,53 -0,71 1,35
32 -115,10 1,21 -0,51 1,09
33 -113,90 1,18 -0,48 1,08
34 -44,40 1,68 1,20 1,17
35 -36,80 1,31 1,05 0,78
36 -115,60 1,47 -0,64 1,32
37 -60,50 0,47 0,23 0,41
38 -48,80 0,56 0,37 0,42
39 -20,30 0,43 0,41 0,15
40 -79,60 0,34 0,06 0,34
41 -80,80 2,48 0,40 2,44
42 -79,80 2,48 0,44 2,44
43 -78,20 2,62 0,54 2,57
44 -83,50 1,55 0,18 1,54
45 -94,90 1,54 -0,13 1,53
46 -79,50 2,38 0,43 2,34
47 -79,50 2,38 0,43 2,34
48 -79,20 1,70 0,32 1,67
49 -13,40 0,99 0,96 0,23
50 -18,40 0,47 0,45 0,15
51 -7,90 0,32 0,32 0,04
52 24,80 0,25 0,23 -0,11
53 9,50 1,17 1,16 -0,19
54 1,70 1,18 1,18 -0,04
55 0,00 1,04 1,04 0,00

195

<!-- p. 205 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

56 -2,40 1,07 1,07 0,04
57 -5,10 1,19 1,18 0,11
58 -28,50 1,18 1,04 0,56
59 -74,90 3,53 0,92 3,40
60 -77,10 2,89 0,64 2,81
61 -70,40 3,39 1,14 3,19
62 -75,30 3,12 0,79 3,02
63 -74,70 3,00 0,79 2,89
64 -82,30 3,43 0,46 3,40
65 -73,20 2,50 0,72 2,39
66 -69,10 1,83 0,65 1,71
67 -70,70 2,37 0,78 2,24
68 -70,70 1,81 0,60 1,71
69 -75,90 1,80 0,44 1,74
70 -86,30 1,96 0,13 1,95
71 -83,20 1,54 0,18 1,53
72 -78,00 1,49 0,31 1,46
73 -78,50 1,07 0,21 1,04
74 -76,50 0,97 0,23 0,94
75 -17,50 0,66 0,63 0,20
76 15,60 0,76 0,73 -0,20
77 7,70 0,26 0,26 -0,04
78 -4,10 0,79 0,79 0,06
79 6,10 0,80 0,80 -0,08
80 -32,10 0,78 0,66 0,42
81 -39,60 0,53 0,41 0,34
82 50,50 0,31 0,20 -0,24
83 -18,20 0,65 0,62 0,20
84 -25,10 0,62 0,56 0,26
85 -116,60 0,03 -0,01 0,03
86 -31,90 0,55 0,47 0,29
87 -80,90 3,56 0,56 3,51
88 -84,10 3,07 0,32 3,05
89 -93,70 3,10 -0,20 3,10
90 -96,20 3,00 -0,33 2,98
91 -88,20 0,44 0,01 0,44
92 -90,00 0,50 0,00 0,50
93 -124,10 0,29 -0,16 0,24
94 -99,50 0,30 -0,05 0,30
95 -87,90 0,38 0,01 0,38
96 -178,00 0,41 -0,41 0,01
97 0,00 0,00 0,00 0,00

196

<!-- p. 206 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

98 -121,90 0,44 -0,23 0,37
99 92,00 0,20 -0,01 0,20
100 -74,50 0,48 0,13 0,46
101 -59,90 0,51 0,25 0,44
102 -139,90 0,51 -0,39 0,33
103 114,60 0,57 -0,24 -0,52
104 -84,20 3,16 0,32 3,15
105 -85,80 3,02 0,22 3,01
106 -84,90 2,89 0,26 2,88
107 -87,00 2,89 0,15 2,88
108 -85,00 3,16 0,27 3,15
109 -96,80 2,74 -0,33 2,73
110 -87,00 1,68 0,09 1,68
111 -98,70 2,03 -0,31 2,01
112 -100,70 1,96 -0,36 1,92
113 -99,40 0,81 -0,13 0,80
114 -99,70 1,15 -0,19 1,14
115 -57,80 1,52 0,81 1,29
116 -77,80 1,71 0,36 1,68
117 56,90 0,45 0,25 -0,38
118 -73,90 0,54 0,15 0,52
119 67,20 0,15 0,06 -0,13
120 103,00 0,09 -0,02 0,09
121 74,50 0,34 0,09 -0,33
122 44,30 0,41 0,30 -0,29
123 34,90 0,28 0,23 -0,16
124 -83,80 0,45 0,05 0,45
125 -102,20 0,43 -0,09 0,42
126 160,80 0,40 -0,38 -0,13
127 180,00 0,04 -0,04 0,00
128 -85,40 3,52 0,28 3,51
129 -78,00 3,82 0,79 3,74
130 -84,00 2,97 0,31 2,95
131 -71,00 2,89 0,94 2,73
132 -70,40 2,29 0,77 2,16
133 -16,10 0,48 0,46 0,13
134 10,90 0,89 0,87 -0,17
135 -12,90 1,15 1,12 0,26
136 96,30 0,24 -0,03 -0,24
137 9,10 1,06 1,05 -0,17
138 -10,10 0,56 0,55 0,10
139 -13,70 0,64 0,62 0,15

197

<!-- p. 207 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

140 -14,40 0,64 0,62 0,16
141 -50,20 0,34 0,22 0,26
142 100,20 0,35 -0,06 -0,34
143 -42,90 0,17 0,12 0,11
144 67,20 0,18 0,07 -0,17
145 -5,20 0,10 0,10 0,01
146 60,60 0,39 0,19 -0,34
147 1,70 0,29 0,29 -0,01
148 63,40 0,04 0,02 -0,04
149 -88,60 3,49 0,09 3,49
150 -72,40 3,76 1,14 3,58
151 - - - -
152 -37,80 1,35 1,07 0,83
153 -55,30 1,15 0,65 0,94
154 -36,50 1,05 0,85 0,63
155 -34,30 0,91 0,75 0,51
156 -41,80 1,11 0,83 0,74
157 6,80 1,19 1,18 -0,14
158 -33,30 0,80 0,67 0,44
159 -21,70 1,17 1,08 0,43
160 -18,40 0,92 0,87 0,29
161 -26,20 0,68 0,61 0,30
162 -8,70 0,87 0,86 0,13
163 23,70 0,24 0,22 -0,10
164 67,00 0,83 0,33 -0,77
165 -65,80 2,15 0,88 1,96
166 -77,30 1,84 0,41 1,80
167 -65,50 1,42 0,59 1,30
168 -71,70 1,54 0,49 1,46
169 -59,30 1,21 0,62 1,04
170 -54,00 0,80 0,47 0,64
171 115,90 0,69 -0,30 0,62
Sumatorio -7836,30 242,47 62,02 195,13
Media 1,43 0,36 1,15

Medida real en metros 0,07131471 0,01824118 0,05739118

Figura 7.62. Tabla copiada de excel en la que se calculan las desviaciones con respecto a la distancia, el
ancho y el alto.

En cuanto a los modelos realizados para el cálculo de las precisiones, como se comentaba
anteriormente, los modelos obtenidos con PhotoModeler no presentan una precisión a nivel
geométrico que se considere óptimo para análisis estructurales, para estudios de altas

198

<!-- p. 208 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

precisiones, valoraciones de superficies, volúmenes, centros de gravedad, producciones de
modelos físicos a través de prototipos, etc. Sin embargo, sí será adecuado para imágenes
sintéticas y animaciones con fines divulgativos, realización de partes integrativas en el ámbito
por ejemplo de restauraciones virtuales para la evaluación compresiva de las propuestas
proyectuales, aplicaciones real-time, etc.

En el caso del modelo obtenido con Agisoft
PhotoScan, debe comentarse que se puede llegar a
conseguir un modelo geométrico bastante preciso, y
presenta una textura foto-realista de alta calidad.
Como ya se ha comentado en apartados anteriores, el
problema de la escala a partir de un valor (ya
solucionable con las nuevas versiones), es lo que
limita dicha precisión, y también el hecho de que no
se pueda controlar el tamaño de los polígonos
directamente. Este será el resultado de la relación
entre el tamaño del modelo a realizar y la cantidad
de polígonos elegidos en la fase de la construcción Figura 7.63. Parámetros impostados para la
de la geometría (en este proyecto se ha elegido una generación de la geometría
resolución media y una cantidad de polígonos de
200.000, parámetros marcados por la capacidad de
procesado del ordenador).

La cantidad de polígonos a veces está limitada por el procesador del ordenador utilizado.
Para este estudio se ha utilizado un ordenador INTEL® Core ™ i5 CPU M520 @ 2.40 GHz
2.40 GHz, con una RAM de 4.00 GB y un sistema operativo de 64 bits.

Figura 7.64. Imagen del modelo realizado con PhotoScan, con textura foto-realista de alta calidad.

199

<!-- p. 209 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

H. REFERENCIAS
BIBLIOGRAFÍA BÁSICA DE REFERENCIA:

 Bertocci, S. 2012. Architettura dell’inganno: artifici prospettici dei quadraturisti nella grande
decorazione di età barocca in toscana. XI Congreso internacional de expresión gráfica
aplicada a la edificación. Edita la Universidad Politécnica de Valencia. Valencia, 2012.
ISBN: 978-84-8363-964-1.

 Cueli López, J.T., 2011. Fotogrametría práctica. Ed. Tantin. Santander. ISBN 978-84-9692-
093-4.

 Fantini, F., Rodríguez-Navarro, P., Di Tondo, S., 2012. Il problema della mappatura del
colore nei modelli digitali 3D a displaced subdivision surface da rilevamento laser scanner in
ambito archeologico. Dentro de Colore e colorimentria. Contributi multidisciplinari. Vol.
VIII. Italia.

 M. Ciampa, 2010. Alle radici dei palazzi pisani: il caso di Palazzo Roncioni, in E. Daniele (a
cura di), Le dimore di Pisa, l’arte di abitare i palazzi di una antica Repubblica Marinara dal
Medioevo all’Unità d’Italia, Alinea, Firenze. p. 127-134.

 Pera L., 1987. Tecnica dell’architettura. Tipologia strutturale. Parte seconda. Ed.
Goliardica, Pisa, p. 31-84.

 De la Plaza Escudero, L., 2008. Diccionario visual de términos arquitectónicos. Ed. Grandes
Temas Cátedra. Madrid.

 Remondino, F., Lo Buglio, D., Nony, N., De Luca, L., 2012. Detailed primitive-based 3D
modeling of architectural elements. International Archives of the Photogrammetry, Remote
Sensing and Spatial Information Sciences, Volume XXXIX-B5. XXII ISPRS Congress, 25
August – 01 September 2012, Melbourne, Australia. P. 285-290.

BIBLIOGRAFÍA CONSULTADA

 Fantini, F., 2012. Modelos con nivel de detalle variable realizados mediante un
levantamiento digital aplicados a la arqueología. Revista EGA. Expresión Gráfica
Arquitectónica. Nº19. Universidad Politécnica de Valencia. Valencia P. 306-317.

 Panajia, A. y Melis, A. 2004. I palazzi di Pisa nel manoscritto di Girolamo Camici Roncioni,
ETS, Pisa.

 Regidor Ros, J.L., Delhom Solaz, S., Valcárcel Andrés, J., Zalbidea Muñoz, A. y Soriano
Sancho, P., 2008. Transferencia de impresiones Ink Jet, una herramienta para la
reconstrucción pictórica de faltantes. Arché. Publicación del Instituto Universitario de

200

<!-- p. 210 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

Restauración del Patrimonio de la UPV, 3. Universidad Politécnica de Valencia. Valencia
P.33-42.

 Regidor Ros, J.L, Palumbo, M., Gómez, G., Clavel, I., 2006. Restauración y solución
propuesta para la exposición de los fragmentos conservados en la bóveda de la iglesia de los
Santos Juanes de Valencia. Arché. Publicación del Instituto Universitario de Restauración
del Patrimonio de la UPV, 1. Universidad Politécnica de Valencia. Valencia. P. 45-52.

 Zalbidea Muñoz, M.A., Clavel Piá, I., Gómez Chaparro, G. y Palumbo, M., 2007. Los
lunetos de la Iglesia de los Santos Juanes: su proyección arquitectónica y su ejecución
pictórica. ”, Arché. Publicación del Instituto Universitario de Restauración del Patrimonio
de la UPV, 2. Universidad Politécnica de Valencia. Valencia. P. 39-46.

201

<!-- p. 211 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

CAPÍTULO 7. CASO DE ESTUDIO 4

Nueva herramienta para el levantamiento de
cubiertas: Iglesia San Miniato en Marciana
(Cascina, Pisa)

202

<!-- p. 212 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

A. BREVE RESEÑA HISTÓRICA

El primer documento hasta hoy encontrado que cita el nombre de la Iglesia de San Miniato
en la localidad de Marciana, es un pergamino del 1011 (Ciampi, F., 2011), que habla de
herencias de terrenos y de la iglesia entre diferentes sacerdotes. Se sabe que la Iglesia de San
Miniato en Marciana Minore, existía antes de este documento.

Ciertamente fue construida sobre otra Iglesia, sobre un templo pagano preexistente o, como
parece más probable, sobre una casa romana. Esta última hipótesis es considerada por algunas
notas escritas en el periodo de la restauración hecha en el 1926, en el cual aparecen muros
particulares, al rehacer el pavimento.

Un pergamino del 12 de abril del 970 cita
(Ciampi, F., 2011), entre los pueblos sujetos a
la iglesia parroquial de S. Casciano, Marciana
Maggiore, por lo tanto la iglesia de S. Michele
di Marciana Maggiore nació antes que la de
Marciana Minore. La razón de que hubiese
dos Iglesias en Marciana es debido a que en
aquellos siglos, frecuentemente había
aluviones del Arno con las consiguientes
desviaciones del río. Antes del 1000 el Arno,
durante un desbordamiento en Lugnano, creó
un recodo y el río pasando por Marciana la
dividió en dos. El nuevo curso alcanzó la
localidad de Arnaccio y después de un amplio
recodo llegó a la altura de Navacchio para
después reencontrarse en Zambra. Siendo el
pueblo de Marciana dividido por el Arno,
algunos marcianesi no podían asistir a las
celebraciones religiosas oficiadas en la Iglesia
de San Michele y por ello se construyó la
Figura 8.01. Imagen de la fachada principal de la
Iglesia de San Miniato di Marciana Minore,
iglesia.
después llamada comúnmente Marcianella.

La nueva construcción probablemente fue erigida, como se ha dicho en precedencia, sobre
las ruinas de un templo pagano. Debe marcarse que, la forma particular y la ubicación de las
casas que se encuentran a pocos metros de la Iglesia, dejan presuponer la existencia de un
convento, ya que, el acceso a la Iglesia, antes de su restauración en 1927, era del lado de la casa
Diodati. Parece que unos dos siglos después, el convento se transfirió a una distancia de unos
kilómetros del anterior. Después de otros dos o tres siglos, la mayor parte de los monjes
abandonaron también este convento, porque su número estaba disminuyendo o por la venta de
aquellas tierras.

203

<!-- p. 213 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

San Miniato en Marciana Minore era Parroquia independiente de la de Marciana Maggiore,
con un solo oficio en los días festivos. Durante siglos fue dirigida por monjes que sucedieron a
los sacerdotes. En el 1575, se realizó la unión de las dos Iglesias y la historia de la Parroquia de
S. Miniato en Marciana Minore se unió a la de S. Michele de Marciana Maggiore.

La Iglesia Monumental de S. Miniato de Marcianella, cita Ciampi, F. (2011), es una
auténtica joya del arte Románico del siglo X. De forma rectangular, tiene una longitud de 20
metros, una anchura de 7 y una altura de 8 metros, con 5 ventanas a “aspillera”, de las cuales
una se sitúa en el ábside, tres en la parte de mediodía y una en forma de cruz en la fachada.
Tiene dos puertas, una pequeña, al Sur, y la principal en la fachada, al Oeste. En esa misma
fachada se encuentra un campanario a “Vela o Ventola” con campana. Toda ella es de piedra
verrucana perfectamente cuadrada y suavizada. En el interior de la iglesia, a la derecha de quien
entra, hay una característica pila para el agua Santa apoyada sobre una columna de granito.
Sobre el único altar, perfectamente entonado con el estilo de la Iglesia, hay una tabla del siglo
XVI. Esta representa la Virgen con el Niño que tiene en la mano una golondrina, a los lados de
la Virgen se encuentran S. María Magdalena penitente y San Miniato.

Figura 8.02. Imagen del interior de la iglesia en la que podemos ver el altar de piedra y la tabla con la
pintura del siglo XVI de la Virgen con el niño, Santa María Magdalena y S. Miniato.

Al llevar a cabo los trabajos de restauración de la Iglesia de Marcianella, Don Andrea Del
Seppia transfirió el fresco sobre la tabla a la Iglesia di Marciana poniéndolo en el coro. De un

204

<!-- p. 214 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

inventario seguido por la República Francesa del 1799, se puede tener una idea de cómo fueron
efectuadas las restauraciones: la Canónica, contigua a la Iglesia, tenía seis estancias en la planta
baja y las mismas en la planta superior en el palco, con techos inservibles. La Iglesia cubierta
con estucos y yesos, tenía un Altar con un muro en la pared izquierda y encima un cuadro
figurativo de la Virgen, San José con el Niño y otros Santos, propiedad de la familia Del Seppia
cuyo escudo de armas resultaba esculpido en el pedestal de las columnas del Altar. El Altar
Mayor, con los lados apoyados al muro, dividía la Iglesia del coro. Encima estaba la pintura
sobre la tabla, del siglo XVI. En 1872 se realizó una posterior restauración de la Iglesia.
Realizando una síntesis, anotaba Don Giuseppe Pecori, fue demolido el Altar de S. Giuseppe de
la familia Del Seppia, dado que el lugar en el que estaba situado, resultaba inútil y engorroso. El
cuadro que se encontraba sobre el Altar Mayor, fue trasladado al coro de la Iglesia de S.
Michele y en su lugar fue colocado el de San Giuseppe. Así continuó el arbitraje de la familia
Del Seppia. Además, se hicieron dos muros al lado de la puerta de la iglesia y se abrió una
pequeña estancia al lado.

En el año 1803, Don Stanislao Ercolini
quisó demoler la Iglesia de Marcianella, y
con el material de ésta pretendía agrandar la
Iglesia de Marciana. Pero afortunadamente
hubo quien se opuso impidiendo que se
cometiese una masacre al patrimonio artístico
de Marciana. El 10 de noviembre llegó una
carta a Don Ercolini del Arzobispo de Pisa
Mons. Angiolo Frateschi. Hubo una reunión y
con ella se rechazó la demolición de la
Iglesia.

Don Ercolini se peleó tanto con la viuda
Del Seppia, que el Arzobispo, al que llegaron
las noticias, consideró oportuno contactar
con el Parroco para saber la razón y lo hizo
con una carta el 14 de abril del 1805. Así fue
impedida la demolición del monumento más
insigne de Marciana.

El ayuntamiento de Cascina envió a Don
Giuseppe Pecori una circular en la cual le Figura 8.03. Imagen de la iglesia antes de su última
recordaba la responsabilidad del cuidado y la intervención. (Imagen de Ciampi, F., 1984: 23)
intervención para la conservación de los
edificios monumentales, siendo responsables directos sus propietarios, y por lo tanto en ese
caso, él con respecto a la Iglesia de S. Miniato y Marcianella. Después de algún que otro año la
Iglesia de la Marcianella cayó en un total estado de abandono. El tejado inseguro había hecho
que la Iglesia fuese cerrada al sagrado culto y los visitantes aparecían solo alguno de vez en

205

<!-- p. 215 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

cuando, los muros apenas se entreveían, detrás de la hiedra y otras plantas trepadoras que se
habían aferrado a las grietas de las piedras.

Para que esta obra no se perdiese Don Giuseppe Mazzei constituyó en Marciana un comité
pro-restauraciones. Con las generosas ofertas de algunas personas y de todo el pueblo, se
iniciaron los trabajos de restauración para devolver al culto y al pueblo de Marciana, su Iglesia.

En el archivo parroquial se encuentra un diario de todos los trabajos seguidos en la
restauración de la Iglesia de Marcianella, escrito por Don Mazzei. Este tiene un valor histórico
no indiferente porque refleja el conocimiento de detalles tan interesantes que sin el diario
habrían sido irremediablemente perdidos.

Figuras 8.04 y 8.05. A la izquierda imagen del campanario de la iglesia con la campana bajo el arco. A la
derecha imagen interior de la ventana en forma de cruz que da a la fachada principal.

En él cuenta la intervención de restauración, detallada, entre el año 1926 y 1927. En junio
del 1926, se realizó la demolición completa del tejado y se construyó uno nuevo. Se demolió el
altar de piedra arenisca del 1686. Se eliminó el yeso de todas las paredes internas y un viejo
arco que separaba la Iglesia de un pequeño coro, se devolvieron al desnudo las pequeñas
ventanas románicas y se tiró un pequeño campanario de ladrillos situado sobre la parte
posterior, en la parte de levante de la Iglesia. Además, se eliminó una lápida sepulcral situada en
el interior del muro, a mitad de la Iglesia de la parte Norte, dedicada a Giuseppe Del Seppia. La
campana, una vez quitada del antiestético arco de ladrillos, se volvió a poner en su verdadero
lugar sobre la fachada, en mitad del campanario bajo un arco (figura 8.04).

En abril del 1927 se continúan las obras de restauración. Se levantó el pavimento y se
abrieron muchas tumbas. Los huesos se mantuvieron en su lugar y las tumbas se rellenaron con

206

<!-- p. 216 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

tierra. Unos días después, se quitaron del Camposanto los restos de los sacerdotes Francesco
Batini y Giuseppe Pecori y se transportaron a Marcianella, donde se sepultaron en el centro de
la Iglesia, bajo los escalones del Presbiterio. El lugar principal fue ocupado por el sacerdote
Francesco Batini, ya párroco de Pontasercchio, mientras que más abajo, hacia el centro de la
Iglesia, al lado del mismo Don Batini se situaron las dos tumbas que contenían los restos
mortales de Don Giuseppe Pecori, ya párroco de esta Parroquia y de Don Flaminio Batini ya
Oficiante de Marcianella. En esta susodicha Iglesia de Marcianella se sepultaron los cadáveres
de las personas muertas en la Primera Guerra Mundial, o por causas de ella.

Figura 8.06.
Imagen de la
lápida
situada en el
pavimento
de la iglesia,
en la que se
pueden leer
el nombre de
las personas
del lugar
muertas en
la primera
Guerra
Mundial.

Hasta la época de las restauraciones, el acceso a la Iglesia era desde la corte Diodati. El
Señor Guglielmmo Rossoni cedió todo el terreno circundante a la Iglesia e hizo un nuevo
ingreso, tal como se presenta en la actualidad. El pueblo se volcó mucho en el trabajo de
movimiento de tierras del suelo de la Iglesia: en el arreglo de la nueva y ampliada plaza, en el
transporte de la arena, los ladrillos y los escombros, en la plantación de los cipreses, etc. El
trabajo de demolición del tejado inseguro, que comenzó en mayo del 1926, fue parado y
retomado más de una vez por falta de dinero, y, finalmente, después de tantas peticiones de
ofertas desde diferentes partes, se terminó en octubre del 1927. Ese mismo mes, se realizó la
apertura de la monumental Iglesia de S. Miniato Mártir de Marcianella, con una ceremonia de
bendición y una misa celebrada por el Cardinal Pietro Maffi, Arzobispo de Pisa (Ciampi, F.,
2011).

207

<!-- p. 217 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

B. OBJETO1

Este caso de estudio, al igual que el anterior, se desarrolla en la estancia realizada en el
Laboratorio A.S.T.R.O del Departamento de Ingeniería Civil e Industrial de la Università di
Pisa. Al profundizar en el tema de la restauración arquitectónica, basada en levantamientos
realizados con escáner láser terrestre a diferentes niveles de precisión, trabajando desde una
dimensión escultórica hasta llegar a modelos arquitectónicos, surgen: algunos problemas unidos
al uso del escáner láser, y, como se ha visto en los casos anteriores, la necesidad de integrar los
levantamiento mediante metodologías fotogramétricas. Las integraciones resultantes necesarias
son relativas tanto a la modelación geométrica tridimensional como a la creación de texturas
foto-realistas aplicadas a dichos modelos.

Sin embargo, solventado este problema, aún se presenta una problemática no resuelta, las
zonas no accesibles, derivadas de una altura superior a la alcanzable con el escáner, o,
simplemente, no transitables. En este caso, tanto el escáner como la fotogrametría terrestre no es
una opción. En muchos casos las cubiertas inclinadas, las cúpulas, fachadas situadas en zonas
cercanas a barrancos, o, sencillamente, zonas que presentan muy poco espacio entre una fachada
y la otra, no permiten hacer fotografías o capturas con el escáner que permitan un levantamiento
para generar modelos en 3D. Ante este problema, se busca como solución la introducción de un
nuevo componente en los levantamientos, los UAV (Unmanned Air Vehicle, vehículo aéreo no
tripulado). Se introduce una nueva técnica de adquisición del dato fotogramétrico: los drones.

Los UAV, en el sentido más amplio del término, existen desde hace más de cincuenta años y
han sido desarrollados principalmente en ámbito militar. Un UAV está compuesto por:

o Un vehículo aéreo, sin presencia humana a bordo.

o Una estación de control a tierra (GCS Ground Control Station) para el pilotaje

o Un sistema on-board que permita ser completamente automatizado (es decir, seguir un

perfil de vuelo pre-programado) o semi-automatizado telecomandado a distancia desde la

GSC.

o Un sistema de comunicación (communication link)

o Un sistema de lanzado y recuperación.

Desde hace tiempo los drones han sido considerados solo como un sistema de adiestramiento
para pilotos u operadores de baterías antiaéreas y operadores radar. El desarrollo viene con los
llamados UAV tácticos, aviones sin piloto con instrumentos de ELINT (Electronic Intelligence)
y máquinas fotográficas o tele-cámaras para el control del territorio. El uso de los UAV en

1 Información adquirida a través de la empresa CAM (Costruzioni Aero Meccaniche - Construcciones
Aéreo Mecánicas) de Pisa en el Open Day della Ricerca. Incontri con la scienza, conferenze e progetti di
ricerca in mostra. Università di Pisa. Pisa. 8 y 9 Mayo 2013.

208

<!-- p. 218 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

campo civil se convierte recientemente en objeto de gran interés consecuencia del desarrollo de
las tecnologías complementarias y de la creciente fiabilidad y reducción de los costes de estos
vehículos aéreos. Tales sistemas son ya un elemento clave en la actividad de inteligencia,
vigilancia y reconocimiento, y se están expandiendo también hacia otros tipos de actividad
operativa. En ámbito geomático, las aplicaciones hasta ahora desarrolladas se ocupan
principalmente del levantamiento fotogramétrico y de las definiciones de los modelos digitales
del terreno y consecuentemente de las ortofotos.

La mayor parte de las investigaciones y
ofertas comerciales en el ámbito de la
geomática han sido conducidas a través de
helicópteros con uno o más rotores. Las
casas de producción se están multiplicando,
ofreciendo modelos de prestaciones y costes
muy diversos.

Si se estudian las experiencias de
vehículos aéreos sin piloto, entre los últimos
congresos y artículos, es fácil darse cuenta
que apenas ha habido resultados aún en este
campo, y que las principales aplicaciones
desarrolladas son en ambiente militar. Sin
embargo, en la parte que se refiere al
procesado tras la adquisición de las fotos, el
desarrollo en las técnicas fotogramétricas en
los últimos años ha sido bastante intenso, Figura 8.07. Imagen del drone en el inicio del vuelo
como ya se ha comentado en los casos para capturar las fotografías de San Miniato.
anteriores.

En esta situación se presenta este caso de estudio. Tras diferentes pruebas de ejecución y
elaboración en un campo de vuelo, se procede a la utilización de un drone para realizar el
levantamiento de la cubierta de la iglesia de San Miniato en Marciana, en la Provincia di Pisa.
El objetivo es realizar la planimetría de la iglesia, incluyendo la planta de cubiertas, no
adquirible a través de otra metodología de alta precisión. Para ello, se realiza una captura con el
drone de una alta cantidad de fotos que después con métodos automáticos y semi-automáticos
permiten obtener diferentes modelos de la cubierta. Además, se realiza una captura de la
fachada principal, que ha sido también levantada con escáner láser, para permitir la
comparación entre estos dos métodos de levantamientos en una zona que permite la captura de
datos mediante ambos procedimientos.

La integración de los dos levantamientos para obtener la planimetría permite evidenciar la
problemática unida al registro en un único sistema de referencia y a la diferente precisión
característica de las dos diversas metodologías.

209

<!-- p. 219 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

C. MEDIOS, SISTEMAS Y METODOLOGÍA DE LEVANTAMIENTO

En este caso de estudio se plantea como objetivo principal el levantamiento integrado
mediante las técnicas de Range-based modelling e Image-based modelling y la comparación
entre ambas.

La iglesia de San Miniato, es una iglesia bastante sencilla, de una sola nave, con dos puertas
y una sola planta. Está situada en el centro de un solar exenta de cualquier edificación adosada.
Por lo tanto para su levantamiento, no se presentan excesivas dificultades, más allá de la
restricción de dos de las fachadas (Norte y Este) por presentar una zona adyacente (zona de
paso) bastante estrecha. Se realizan cuatro barrido en el interior y siete en el exterior. Al mismo
tiempo que se realiza el levantamiento con el escáner láser, se capturan los puntos de estación
con el GPS, lo que permitirá situar la iglesia en un sistema de referencia global y no solo en uno
local.

Figuras 8.08 y 8.09. Imagen del GPS sobre un punto de estacionamiento en el exterior de la iglesia, a la
izquierda, y a la derecha, imagen del escáner láser sobre un punto de estacionamiento en el interior.

También mientras se efectúa el levantamiento con escáner láser, se ejecuta el levantamiento
de la fachada principal y de la cubierta con el drone. La metodología de trabajo empleada en
este caso, es la del levantamiento en paralelo de dos metodologías diferentes, una bastante
conocida a nivel de precisión y errores y otra totalmente nueva y en fase de exploración.

210

<!-- p. 220 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

i. Láser escáner

Para el diseño de la planimetría de la iglesia se utilizará como base el levantamiento
realizado mediante escáner láser. Se realizan 4 barridos en el interior de la iglesia y 7 barridos
en el exterior. En el interior se efectúan dos centrales con respecto al eje transversal, en la zona
de los bancos y dos en paralelo con respecto al eje transversal, en la zona del altar (fig. 8.11). En
el exterior, se sitúan 4 en cada una de las esquinas, a una distancia que permite obtener lo
máximo posible de las dos fachadas perpendiculares que forman dichas esquinas, otros dos
escaneados situados a lo largo de las dos fachadas de los dos lados mayores de la planta
rectangular y un último barrido enfrente a la puerta principal, que permitirá la conexión con los
escaneados del interior de la iglesia.

Figuras 8.10 y 8.11. Arriba, imagen de las estaciones del escáner en el exterior de la iglesia. Abajo,
imagen de las estaciones del escáner en el interior. La estación 500 se utiliza como estación de referencia
para realizar la alineación con las escaneados del interior; desde la posición 500 se escanea el target
situado en el punto 100, y viceversa.

Para su posterior alineación se utilizan target en los puntos de estación, formando una red
que permite una vez finalizada la fase de toma de datos, en el programa Cyclone su registro de

211

<!-- p. 221 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

modo automático, colocando todos los escaneados en un único sistema de referencia. Para ello,
previamente en la toma de datos se realiza la captura de los target referenciando entre ellas todas
las estaciones. Los target utilizados son especiales del propio escáner, por lo que éste los
identifica, teniendo ya en su memoria los datos relativos a altura, dimensiones, etc.

Figura 8.12. Imagen del proceso del escaneado 1100 (estación 11), en el cual se están capturando los
target de las estaciones 600 y 1000.

En este caso, el procesado de los datos no pasa por el programa Geomagic. Una vez
realizadas las acciones de registro y limpieza de las nubes de puntos, estas son exportadas
directamente al Inus Technologies Rapidform XOR3, donde son convertidas en mesh, se
eliminan los errores topológicos y se procede al relleno de los huecos. Además se realizan las
secciones que permitirán el diseño de la planta, y secciones para la planimetría, y se realiza la
“decimation” (reducción del detalle), obteniendo un modelo más ligero y manejable que permite
entre otras cosas su exportación al Luxology Modo 501, para realizar render y para poder
introducirle, si se desea, una textura foto-realista a partir de las fotografías tomadas de alta
resolución.

212

<!-- p. 222 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

Figura 8.13 y 8.14. A la izquierda, imagen del momento de la captura del target situado en el
estacionamiento 400. A la derecha, escáner situado en el punto 200.

ii.Image-based Modelling a partir de fotogrametría aérea (drone)

La cámara digital2

Una cámara digital es, en casi todos los aspectos, exactamente idéntica a una cámara
convencional, salvando el hecho de que en vez de la película fotográfica enrollada se usa un
sensor electrónico que puede ser de diversos tipos.

En la cámara digital, la imagen viene metida a fuego sobre el plano del sensor. Las señales
capturadas vienen amplificadas y convertidas en digital. En ese momento los datos digitales
están en forma “bruta” (raw) y pueden ser memorizados sobre un file, para una sucesiva
elaboración en estudio, con otros aparatos informáticos. Sucesivamente, el procesador de
imágenes interno de la cámara transforma los datos, es decir, calcula las componentes primarias
faltantes sobre cada pixel (RGB) y hace compatibles los datos de imagen con los sistemas
normales de visualización de imágenes, almacenando el archivo elaborado en una memoria de

2 Guidi, G., Russo, M. y Beraldin, J.A. (2010: 203-204), definición de “fotocamera digitale” en
Wikipedia (15-08-2013) y Walter, G., 2013. Implementazione software di algoritmi per la progettazione
di rilievi fotogrammetrici da UAV. Tesi di laurea trienale in Ingegneria Civile. Università di Pisa.

213

<!-- p. 223 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

estado sólido. Las tarjetas contienen generalmente un relevante número de imágenes, la cantidad
depende de las dimensiones de la imagen individual, según la modalidad de registro y la
capacidad de la memoria.

La resolución total del sensor se mide en millones de pixel totales. Un pixel es la unidad de
captura del archivo: representa por lo tanto la porción más pequeña de la imagen que la cámara
permite capturar sobre una matriz ideal construida sobre el sensor.

Multiplicando el valor en pixel de la
resolución horizontal por la resolución
vertical se obtiene el número total de
pixel que la cámara distingue en una
imagen.

La elevada cantidad de elementos
fotosensibles garantiza un elevado
detalle de imagen, pero surgen
problemas de velocidad en la
transferencia de los datos al procesador
de imagen. Cuanto mayor es la
resolución, mayor es el número de pixel,
y por lo tanto, mayor será la cantidad de
datos a transferir. Así, a igual velocidad
de transmisión, mayor será el tiempo
necesario para transferir los datos del
Figura 8.15. Imagen del drone capturando la fachada de
procesador de imágenes y el sucesivo
la iglesia
registro de la imagen.

Si la dimensión física del sensor es elevada a igual número de pixel esto conlleva
obviamente a una mayor dimensión física de los pixeles. Por ejemplo, si son sensores de 6 MP
que tienen una dimensión de 5,371 x 4,035 mm (diagonal = 6,721mm), mientras otros sensores
de 6 MP tienen dimensión de 7.176 mm x 5.319mm (diagonal = 8.933mm). La calidad del
sensor es normalmente mayor en el sensor más grande.

Parámetros del vuelo de la fotogrametría aérea

Al igual que en el caso de la fotogrametría terrestre, en la fotogrametría aérea, se encuentran
una serie de parámetros que influyen directamente en la calidad del modelo digital que resulta
de las técnicas de Image-based Modelling. Por ello, se debe realizar un anteproyecto, analizando
dichos parámetros, para que el levantamiento sea adecuado. Los parámetros son los siguientes
(Cannarozzo, Cucchiarini y Meschieri, 2012):

214

<!-- p. 224 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

Escala media:

Los fotogramas representan una vista central en perspectiva del objeto, por lo tanto no es
posible en términos rigurosos hablar de la escala del fotograma, debido a que esta varía de un
punto a otro en la perspectiva.

Sin embargo, es útil definir una escala media de los fotogramas, entendida como la relación
entre la dimensión máxima del fotograma “l” y la correspondiente dimensión real “L” del objeto
contenido en la fotografía:

l

p
O ·
(1)

H Siendo el módulo de la escala.

L

Figura 8.16. Definición de la escala media de los fotogramas en fotogrametría aérea.

Sabiendo que la distancia L es una incógnita, se puede encontrar la escala del fotograma
mediante algunas consideraciones geométricas. Observando la figura 8.16, se puede deducir,
por geometría, que la escala media es igual a la relación entre la distancia focal (p) y la altura de
vuelo (H). No pudiendo variar las características de la cámara utilizada (“l” o “p”), para variar la
escala de los fotogramas, se debe por tanto variar la altura de vuelo H de la cámara al objeto
capturado.

La escala de los fotogramas no es una elección arbitraria, sino que viene obtenida partiendo
de la escala de reproducción del objeto (escala del folio) mediante una oportuna relación. Para
obtener fotogramas con la escala media así determinada, se debe colocar la cámara, para la
captura, a una distancia del objeto prevista a partir de la siguiente expresión:

H = (2)

En la fotogrametría tradicional la escala del fotograma se obtiene de la siguiente relación:

\= (3)

215

<!-- p. 225 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

Siendo el coeficiente “k”:

\- 200-300 para escalas de dibujo inferiores a 1:5000 (escalas medio-pequeñas)

\- 150-200 para escalas de dibujo superiores a 1:2000 (escalas grandes)

Como alternativa, con respecto a la formula precedente, es posible deducir los valores de la
escala media de los fotogramas de la tabla de la figura 8.17, realizada por la “Commissione
Geodetica Italiana”. En esta se han relacionado también, indicativamente, las consiguientes
alturas de vuelo para cámaras con valores comunes de “p”.

Figura 8.17. Tabla de la relación del tamaño del folio con respecto a la escala de los fotogramas
(Cannarozzo, Cucchiarini y Meschieri, 2012: 38).

En definitiva, para determinar la altura de vuelo “H”, se debe partir de la escala de dibujo
, pasando por la escala de los fotogramas según este esquema sintético:

H

Con la fotografía digital la escala media del fotograma puede ser individualizada focalizando
la atención sobre el pixel: la cantidad más pequeña que constituye la imagen digital, y haciendo
referencia al concepto de la escala nominal. En general, se fija convencionalmente, como
tolerancia gráfica, motivada por la agudeza visual, el valor de 0.0002 m a la escala de
restitución como valor mínimo representable (sin imprecisiones o errores de impresión): se
aplica el mismo concepto al elemento más pequeño del pixel. Es decir:

216

<!-- p. 226 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

Cota media de vuelo:

La altura de vuelo (H) representa la distancia entre el UAV (centro de captura) y el terreno.
Sin embargo, la cota levantada desde los instrumentos no coincide con H sino con la cota
ortométrica absoluta Qv.

Este parámetro es fácilmente obtenible sumando a la altura de vuelo H la cota absoluta
media QM del terreno capturado, por lo tanto: Qv = QM + H

La cota media del terreno QM se obtiene como la media aritmética de algunos puntos de cota
conocida presentes sobre el terreno.

Recubrimiento:

Para hacer posible que los mismos
puntos del objeto sean capturados en dos
fotogramas consecutivos, es necesario
que estos presenten un área en la cual
ambos contengan la misma porción de
objeto. La entidad de esta porción de
objeto, común a los dos fotogramas
consecutivos, respecto a la parte entera
de objeto representado en los fotogramas,
se le llama recubrimiento longitudinal.
Su valor, inferior a uno, en general, se
indica con μ.

Figura 8.18. Esquema del recubrimiento
longitudinal, μ, y transversal, ε.

Para evitar que a causa de pequeñas imprecisiones en las operaciones de captura o por la
complejidad del objeto, algunos puntos sean visibles solo en un fotograma, se usa un valor de
recubrimiento: μ = 0,6 – 0,7 (60% - 70%) en relación a la configuración geométrica del objeto o
a la conformación morfológica del terreno. En particular, con la eventual presencia de terreno
fuertemente ondulado se aconseja el aumento del porcentaje del recubrimiento longitudinal
hasta un 80% (figura 8.19).

217

<!-- p. 227 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

Figura 8.19. Pliego de Prescripciones Técnicas para la ejecución de trabajos fotogramétricos. Dirección
General de Obras Hidráulicas. Ministerio de Fomento (Otero, I. et al., 2010: 19).

Base de captura:

El factor que permite obtener el recubrimiento longitudinal deseado es la base de captura
“B”. En efecto, cuanto menor es el valor de “B” mayor es el recubrimiento entre capturas (figura
8.20).

Figura 8.20. La base de la toma B permite obtener el valor deseado del recubrimiento
longitudinal, que al mismo tiempo, permite generar apropiados modelos estereoscópicos
necesarios para la restitución en el levantamiento.

La base de la captura “B” puede ser calculada mediante la siguiente formula:

B = L – μ· L = L · (1 – μ) (4)

Así sabiendo que L = l (H / p) (5)

Se puede llegar a:

B = ( ) ( ) (6)

218

<!-- p. 228 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

La base de captura es proporcional a las dimensiones del formato de la cámara y a la cota
relativa del vuelo.

Intervalo de la apertura del obturador:

La apertura del obturador en la captura aérea es automático por lo tanto es necesario
establecer un oportuno intervalo “t” de apertura del obturador.

La distancia B, entre los centros de captura en la cual vienen generados dos fotogramas
consecutivos, depende de la velocidad de crucero “v” del UAV (supuesta, idealmente,
constante) según la conocida relación del movimiento uniforme. Por lo tanto si ∆t = B / v ,
sustituyendo en esta ecuación la B, a partir de la fórmula obtenida anteriormente, es posible
determinar el intervalo t (en segundos, expresando la v en m/s) al cual se debe capturar las
fotografías:

∆t = = ( ) ( ) (7)

Intereje de las capturas:

El intereje “i” entre los ejes de dos capturas consecutivas se elige en modo de obtener para el
recubrimiento transversal, ε, el valor programado, que en general está comprendido entre el
intervalo 0,10 – 0,30 (entre el 10% y el 30% de L), en función de las irregularidades presentes
en el terreno a levantar. Esto garantiza la total cubrición fotográfica del terreno de interés en el
levantamiento.

Observando la figura 8.18 se concluye evidente que el intereje i se puede deducir a partir de
la siguiente ecuación:

i = ε · L = L· (1 – ε) (8)

Sustituyendo L por su valor obtenido en la ecuación (5):

i = · (1 – ε) = l · · (1 – ε) (9)

El problema del arrastre:

Se define tiempo de exposición como el intervalo de tiempo durante el cual el obturador de
la cámara se mantiene abierto. Los tiempos de exposición deben ser muy breves, dada la
velocidad del UAV, ya que se deben evitar efectos de “arrastre de la imagen”.

219

<!-- p. 229 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

El “arrastre” tiene como origen el hecho que entre el instante de la apertura del obturador y
del cierre trascurre un cierto tiempo t durante el cual el UAV se mueve. Al genérico punto P,
por lo tanto, no corresponderá el punto imagen P’ sino el segmento P0 · P’.

El efecto del arrastre puede por lo tanto resultar particularmente dañino, sobre todo para los
vuelos a gran escala y por lo tanto a baja cota.

Los símbolos utilizados en las figuras serían los siguientes:
 H: altura de vuelo con respecto al terreno
 : recubrimiento longitudinal (en general 0,6)
 ε: recubrimiento lateral (en general 0,2)
 l: formato efectivo útil del fotograma (aproximadamente 230 mm)
 p: distancia principal de la cámara
 v: velocidad de crucero del aéreo en m / s.

Drone

En este caso la toma de fotografías se realiza con un drone, por lo que el levantamiento será
mediante fotogrametría aérea. Dicha toma se realiza a través de un prototipo de vehículo aéreo
sin piloto, no presente aún en el mercado, realizado por la empresa CAM (Costruzioni Aero
Meccaniche - Construcciones Aéreo Mecánicas) de Pisa, que realiza colaboraciones con el
Laboratorio ASTRO.

La ficha técnica de dicho prototipo, proporcionada por la empresa, es la siguiente:

Configuración Hexarotores
Propulsión 6 motores eléctricos brushless de 500W
Sistema di guía Control remoto con auto-pilotaje digital
Alimentación Baterías de polímeros de litio
Longitud 90 cm
Anchura 97 cm
Altura 48 cm
Peso máx. al despegue 9,2 kg
Carga útil 2,5 kg
Autonomía 10 min
Rango máximo 10 Km

Figura 8.21. Tabla de las características del drone.

220

<!-- p. 230 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

Las particularidades que además presenta este
UAV son las siguientes: Este vehículo aéreo se
caracteriza por una arquitectura destinada a
garantizar su empleo en zonas sin infraestructuras.
La estructura está realizada en aluminio aeronáutico,
pero puede ser fácilmente modificada para adaptarse
a las diferentes tipologías de misión sin que sea
necesario un rediseño completo. El número de
motores puede variar de 4 a 8 con una carga útil
máxima de 3,5 kg. Previa petición es posible tener
diversos grados de protección de los agentes
ambientales como polvo o lluvia. La carga útil típica
está constituida por una cámara fotográfica Nikon
D600 alojada en un sistema de estabilización activo
y sobre el roll que permite a la maquina misma estar
siempre nivelada y que permite variar el ángulo de
toma desde 0 a -90º.
Figura 8.22. Imagen del drone con todos
los complementos necesarios para su uso.

En el caso de necesidad es, además, posible introducir cámaras térmicas, videocámaras de
alta resolución y sensores de varios tipos. Es también posible integrar las cargas de fuselaje
desmontables en vuelo. El sistema de guía está basado sobre un autopiloto digital de última
generación que permite pilotar el drone tanto en modo manual como automático. Gracias a la
interfaz hombre máquina de tipo avanzado, es posible adiestrar al operador en tiempo breve y el
elevado nivel de sofisticación permite seguir maniobras complejas como el despegue y el
aterrizaje en manera totalmente automática. Para controlar el UAV es suficiente con un
ordenador portátil y una interfaz para la guía manual. Normalmente el vehículo está, además,
dotado de un sistema de telemetría video que sirve para facilitar el pilotaje en modo manual y de
enfocar con precisión los sensores ópticos. El drone está completamente proyectado y realizado
en Italia, y presenta una disponibilidad total de asistencia tanto para la manutención normal
como para la construcción de versiones personalizadas para usos científicos.

La cámara realiza una captura al segundo y en base a esto y a la altura de vuelo se proyecta
la velocidad con el fin de obtener un recubrimiento mínimo del 70%. Las capturas son
automáticas.

221

<!-- p. 231 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

En el caso del UAV utilizado en el
levantamiento, la duración máxima de cada
vuelo es de aproximadamente 10 minutos,
debido a las baterías que lleva, sin embargo,
se hacen vuelos de unos 4 minutos. Las
baterías usadas son dos de 6000
Miliamperios de iones de litio. Este vehículo
aéreo es teledirigido por un técnico
especialista, que realiza 3 vuelos, uno solo
para la fachada, y dos que incluyen la zona
de la fachada principal y la cubierta. La
altura para la toma de la cubierta es de
aproximadamente 30 metros. La captura de
imágenes se realiza tomando en el primer
vuelo 36 fotografías (solo de la fachada), en
el segundo 197 fotografías (incluyendo
fachada y cubierta) y en el tercero 236 Figura 8.23. Imagen del drone en el proceso de
fotografías (también de la fachada y la levantamiento de la fachada.
cubierta).

Terminada la toma de datos, éstos serán
tratados mediante el proceso de Imagebased Modelling, al igual que se efectúa
para la fotogrametría terrestre.

Los pasos para llegar al modelo
tridimensional serán los mismos y, al igual
que en la fotogrametría terrestre, la
precisión dependerá de las condiciones de
la toma de datos y de la fase posterior de
elaboración.

Figura 8.24. Imagen del drone en el momento del
despegue.

222

<!-- p. 232 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

D. TRATAMIENTO DE LOS DATOS.

IGLESIA

Para la elaboración de los datos del escáner láser, se procede como en los casos anteriores.
Se alinean todo, en Cyclone, en un único sistema de referencia y a continuación se eliminan de
las nubes de puntos las partes que no tienen información útil para el caso de estudio. Después
son exportados por partes al Rapidform XOR3, ya que al ser una nube de puntos bastante densa,
no es posible trabajar con todas las nubes de puntos al mismo tiempo en Rapidform XOR3.

En Rapidform, en una primera fase de elaboración, se mantienen separadas la parte externa e
interna de la iglesia para evitar trabajar con demasiados datos simultáneamente. Una vez se han
realizado los procesos de edición (conversión en mesh, eliminación de errores topológicos,
“curado” de bordes, relleno de huecos, optimización, etc.), se juntan en un solo modelo la parte
interior y exterior de la iglesia.

Figuras 8.25 y 8.26. Imágenes de un modelo de nube de puntos y la mesh después del proceso de mallado.

Figura 8.27. Imagen de la iglesia dentro del programa Rapidform, en la cual se puede observar tanto la
mesh que conforma el interior de la iglesia como la que conforma el exterior.

223

<!-- p. 233 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

CUBIERTA

Paralelamente se realizan los trabajos de Image-based Modelling, para obtener la cubierta de
la iglesia. Para ello se hacen dos pruebas simultáneas: por un lado se realiza en modelo
mediante el software PhotoModeler Scanner y por otro mediante el software Agisoft PhotoScan.
El primero resulta ser más laborioso, pero permite un mayor control de los factores que influyen
en el resultado. El segundo es prácticamente automático, ya que solo se deben elegir algunas
características para que el programa trabaje solo.

Obtenidos los modelos resultantes por ambos métodos, son comparados y haciendo un
análisis se decide cual es el más adecuado para tomarlo como modelo final e integrarlo en el
resto del modelo de la iglesia. La diferencia se basa en que en el Agisoft PhotoScan se puede
decidir entre número de polígonos y calidad del modelo, pero este número de polígonos será
distribuido a su elección, y eligiendo una calidad del modelo muy alta, el software sólo podrá
realizar los cálculos rodando en un hardware de altas prestaciones. En el caso del PhotoModeler
Scanner, la elección no se basa únicamente en el número de polígonos sino en una serie de
parámetros bien definidos (“sampling interval”, “Depth range”, “Matching región radius”,
“Texture type”…), que dan un modelo bastante controlado, en base a la elección de éstos.

Figuras 8.28 y
8.29. Screenshot de
los modelos de la
cubierta con textura
foto-realista.
Arriba, modelo
realizado con
Agisoft PhotoScan;
abajo, modelo
realizado con
Photomodeler.

224

<!-- p. 234 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

Los modelos que se observan en las figuras de la 8.28 a la 8.31, son ambos obtenidos con
métodos de generación de modelos tridimensionales a partir de fotos, sin embargo, presentan
resultados diferentes. Al igual que en el caso del escaner de triángulación, el Agisoft PhotoScan
da como resultado directamente una mesh poligonal, mientras que en el caso del PhotoModeler
Scanner, se puede obtener una nube de puntos de alta densidad, como en el caso de los escaner
ToF (queriendo, también, una mesh, sin embargo, se puede afirmar, a partir de las experiencias
realizadas, que la calidad de la mesh es bastante baja). En este caso concreto, se utiliza un
programa diferente para generar la mesh a partir de la nube de puntos, MeshLab, debido a que
cuando se prueba a generar la mesh con PhotoModeler Scanner, el modelo presenta una calidad
no tolerable.

Figuras 8.30 y 8.31. Modelos de las cubiertas sin textura foto-realista. Arriba, modelo realizado con
Agisoft PhotoScan, abajo, modelo resultante del PhotoModeler+MeshLab.

225

<!-- p. 235 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

Como se puede observar en las imágenes, aunque los modelos con la textura fotorealista
(figura 8.28 y 8.29) parecen más o menos de una calidad similar, al quitarles dicha textura se
puede contemplar claramente que el modelo obtenido con Agisoft PhotoScan tiene una mayor
definición. Esto se debe a que PhotoModeler Scanner precisa de un levantamiento fotográfico
con parámetros más precisos, que en este caso no han sido posible alcanzarlos, debido a que el
drone no presenta la flexibilidad a la que se puede optar en un levantamiento de fotogrametría
terrestre. El modelo de nube de puntos obtenido con PhotoModeler Scanner presenta mucho
ruido. Para realizar la limpieza necesaria y generar la mesh, es complicado realizar la elección
adecuada sin perder la información útil. Ello deja al PhotoModeler Scanner como una opción
menos adecuada que Agisoft PhotoScan.

Con los modelos obtenidos, se opta por utilizar para el trabajo final, el modelo obtenido con
PhotoScan.

FACHADA

Para un análisis de la precisión del drone, aún en fase de estudio, se realiza la captura de una
zona coincidente con otra, barrida con el escáner láser: la fachada principal. Así, se define
también independientemente de la cubierta un modelo en PhotoModeler Scanner de dicha
fachada.

Para la obtención de la fachada, se siguen los pasos de calibración de la cámara, orientación
de las imágenes, definición de la geometría básica, la obtención de la nube de puntos y la
eliminación de los puntos sobrantes en PhotoModeler Scanner. Se efectúa una segunda limpieza
del ruido en CloudCompare, y después se exporta el modelo a MeshLab para obtener la mesh de
la fachada. Este modelo se utiliza para compararlo con el modelo obtenido con el escáner,
permitiendo definir la precisión obtenida con los modelos 3D a partir de las fotografías
capturadas con el UAV, utilizando como base el PhotoModeler Scanner. El resultado es
observable en las figuras 3.34 y 3.35. Al someter los dos modelos para ser comparados en
Rapidform XOR3 solo una zona la calcula, por ser aquella en la cual hay una superposición
adecuada para su cálculo. En esa zona la desviación es de aproximadamente 5 mm.

226

<!-- p. 236 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

Figura 8.32 y
8.33. Imágenes
del
PhotoModeler
Scanner en los
procesos para el
cálculo de la
fachada.

Figuras 8.34 y 8.35. Imagen del programa en el momento de la comparación entre el modelo obtenido con
escáner láser y el realizado con PhotoModeler.

Después del resultado obtenido con PhotoModeler Scanner, se decide hacer otra prueba,
realizando un modelo con Agisoft PhotoScan. Éste, al igual que en el caso anterior, se exporta a
Rapidform XOR3 para su comparación con el del escáner. El modelo de Agisoft PhotoScan
presenta una calidad mayor a la del obtenido en PhotoModeler Scanner: la desviación media
total del modelo obtenido con Agisoft PhotoScan es inferior a 5 mm ya que la superposición de
los modelos adecuada para el cálculo es mayor al 75 %, mientras que la desviación media del
modelo de PhotoModeler Scanner es cercana a 5 mm pero la superposición de los modelos
adecuada para su cálculo es menor a un 50%, siendo el otro 50% por lo tanto con una
desviación bastante mayor, no calculable por el programa. Aunque no es comparable éste con el
obtenido con el escáner, en cuanto a precisión detallada, se puede considerar un modelo bastante
recomendable cuando la precisión requerida es un poco menor, teniendo en cuenta que la
velocidad de obtención y el ahorro de trabajo es muy alto.

227

<!-- p. 237 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

Figuras 8.36 y 8.37. Composición de la comparación de los dos modelos entre sí para comprobar la
desviación entre ambos. Observando la textura del modelo de Agisoft PhotoScan ya se puede intuir que
es un modelo de mayor calidad, además, la coincidencia con el modelo del escáner es mayor.

E. ANÁLISIS

Para la generación del modelo interior y exterior de la iglesia (a excepción de la cubierta por
el exterior), se utilizan las técnicas ya descritas para modelos obtenidos con escáner láser. En
general, no se presentan mayores problemas que el de gestión por el “peso” de los modelos
capturados a una alta resolución. Esto condiciona mucho el tiempo de elaboración, pero los
modelos son bastante completos.

La unión entre el modelo exterior e interior es realizado, simplemente por exportación ya que
al haber orientado los barridos entre ellos en la fase de toma de datos, automáticamente en el
cyclone aparecen en el mismo sistema de referencia. Teniendo ambos modelos unidos, es
posible la obtención de plantas y secciones, en las que se podrá medir al milímetro el grosor del
muro, pudiendo contemplar las pequeñas desviaciones que hayan podido sufrir en cualquier
punto de este. Esta planimetría tan detallada, permitirá en fases futuras el estudio patológico de
la iglesia, pudiendo presentar un proyecto de restauración y mantenimiento.

Por otra parte, a partir del modelo de la fachada, es posible comprobar que la precisión de las
técnicas de modelación a partir de fotografías aún no es comparable con las técnicas de
obtención de datos por Range-based Modelling. Los modelos obtenidos por Image-based
Modelling tanto de la fachada como de la cubierta, presentan en su elaboración nubes de puntos
muy densas que permitirían realizar modelos de alto nivel de detalle. El problema, es que en el
caso de los modelos obtenidos con PhotoModeler Scanner, las nubes de puntos presentan un
nivel de ruido muy alto, y la limpieza de éstos sin pérdida de información es poco operativa,
convirtiéndose en este caso en un método no conveniente para modelos en los que la búsqueda
sea la exactitud geométrica y detallada.

228

<!-- p. 238 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

Como se explicaba en el apartado de estado del arte, estos modelos no serán convenientes si
lo que se busca es la exactitud geométrica, si el modelo sirve para clarificar e investigar
aspectos constructivos, métricos, morfológicos de una arquitectura, ya que en ese caso sería
necesaria una gran fiabilidad y control de la desviación con respecto al original, no obtenibles
con este tipo de levantamiento (como se ha visto en los gráficos precedentes, la superposición
aceptable entre los modelos de escáner láser y los obtenidos con Photomodeler Scanner es
inferior al 50%). Sin embargo, son muy adecuados por su economía y rapidez de elaborado, si
lo que se busca es un modelo más para el design, que no busca un control métrico, sino una
imagen sintética o para una animación, para ofrecer una visión comprensiva de un elaborado, si
se presenta una función expositiva e ilustrativa.

Sin embargo, como se comentaba en el apartado anterior, los modelos obtenidos a partir de
Agisoft PhotoScan, presenta características bastantes aceptables (una desviación media
aproximada de 5 mm), tanto a nivel de mesh como de textura. Controlando el nivel de precisión
buscado, estos modelos pueden ser muy convenientes, ya que no necesitan usuarios altamente
cualificados, se obtienen en un tiempo reducido, y presentan una textura de alta calidad.

Figuras 8.38 y 8.39. A la izquierda, fachada principal obtenida mediante levantamiento con escáner láser.
A la derecha, fachada principal desarrollada con el software Agisoft PhotoScan.

229

<!-- p. 239 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

F. MODELOS OBTENIDOS.

IGLESIA

Tras el levantamiento de la
iglesia se obtiene un modelo
numérico de alto nivel de detalle
geométrico, formado por una
malla poligonal de triángulos
desarrollada dándole una
precisión del escáner de 5 mm.
Este modelo es el resultado de la
unión de 7 nubes de puntos
exteriores y 4 interiores.

A partir de este modelo
preciso se realizaran
paralelamente dos elaboraciones.
Por un lado, se efectúan
secciones en las 3 direcciones
ortogonales de la iglesia,
Figura 8.40. Sección transversal de la iglesia.
obteniéndolas en el software
Rapidform XOR3, y exportándolas a Rhinoceros para su adaptación a formato CAD, y su última
elaboración en AutoCad. Por el otro, se realiza una “decimation” del modelo que permite
exportarlo a un modelador de sector del “entertainment”, Modo, para poder realizar diferentes
render, para su exposición como imagen sintética, y la posible realización de una maqueta de la
iglesia.

Figura 8.41. Sección horizontal visualizando la cubierta desde el interior.

230

<!-- p. 240 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

Figura 8.42. Sección longitudinal de la iglesia del lado Norte.

CUBIERTA

El modelo de la cubierta es también un modelo numérico, resultado de las técnicas de Imagebased Modelling a un conjunto de 36 fotos, seleccionadas entre todas las capturadas por el
drone para realizar dicho modelo. Se efectúa en Agisoft PhotoScan, eligiendo un modelo de
200.000 polígonos, y escalándose a partir de puntos medidos en el modelo del escáner. Como se
puede deducir, el modelo de la cubierta con el escáner y el desarrollado por métodos
fotogramétricos, no es comparable a nivel de detalle geométrico. Sin embargo, gracias a este
modelo, no adquirible con escáner láser, se consigue obtener un modelo completo, que no
habría sido posible de otro modo.

231

<!-- p. 241 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

Figura 8.43. Modelo 3D de la cubierta de la iglesia a partir del levantamiento con UAV.

G. RESULTADOS

Tras este caso de estudio, se puede concluir que los modelos obtenidos con técnicas
fotogramétricas mediante métodos automáticos o semi-automáticos, presentan una alta
variabilidad de la precisión dependiendo del método de adquisición utilizado (tipo de cámara y
medio, fotogrametría aérea o terrestre) y del software empleado en los procesos de generación
del modelo digital tridimensional, no siendo comparables con los obtenidos mediante sensores
activos, que presentan una precisión definida ya de base, que variará dependiendo del modelo
del escáner. Sin embargo, se consideran una buena alternativa cuando no existe otro modo de
adquisición, teniendo claro dichos factores, o cuando la finalidad del levantamiento no es para
un estudio métrico o de cualquier tipo en el que se base su interés en la definición geométrica
precisa.

Debe aclararse, que los modelos a partir de Image-based Modelling, sí que son una
alternativa más que razonable para la obtención de modelos de alta calidad visiva, para la
generación de modelos interactivos de bajo peso, etc., convirtiéndose en muchos casos en una
opción más conveniente debido a su menor precio y su menos tiempo de elaboración.

232

<!-- p. 242 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

233

<!-- p. 243 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

Figuras 8.44 y 8.45. Renders de la iglesia resultados de la integración obtenida mediante las dos
tipologías de levantamiento objeto de estudio.

234

<!-- p. 244 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

H. REFERENCIAS

BIBLIOGRAFÍA

 Bendea H, Boccardo, P., Dequal, S., Giulio Tonolo, F., Marenchino, D., Piras, M., 2008.
Low cost UAV for post-disaster assessment. En The XXI Congress of the International
Society for Photogrammetry and Remote Sensing. Pekín, China, 3-11 Julio 2008. p. 1373-
\1380.

 Bendea, H., Chiabrando, F., Giulio Tonolo, F., Marenchino, D., 2007. Mapping of
archaeological areas using a low-cost UAV. The Augusta Bagiennorum test site. XXICIPA
International symposium. Atenas, Grecia, 1-6 Octubre 2007.

 Cannarozzo, Cucchiarini, Meschieri, 2012. Fotogrammetría. Misure, rilievo, progetto.
Volumen 3. Zanichelli editore S.p.A., Bolonia

 Ciampi, F. 2011. Mille anni della Chiesa di S. Miniato in Marciana Minore. 1011-2011.
Amministrazione Comunale Cascina. Pisa.

 Ciampi, F., 1984. Storia e cronaca di Marciana Maggiore e Marciana Minore. Pacini
Editore Pisa.

 Guidi, G., Russo, M. y Beraldin, J.A., 2010. Acquisizione 3D e modellazione poligonale.
McGraw-Hill. Italia.

 Lingua, A., Marenchino, D., Nex, F., 2009. Automatic Digital Surface model (DSM)
generation procedure from images acquired by Unmanned Aerial Systems (UASs). En
GeoCad 2009, Alba Iulia (Romania), May 7th - 9th. pp. 198-208.

 Otero, I., Ezquerra, A., Rodríguez-Solano, R., Martín, L., Bachiller, I., 2010. Topografía,
cartografía y geodesia. Apuntes de Ingeniería cartográfica, geodésica y fotogrametría de la
Universidad Politécnica de Madrid. Tema 11. Fotogrametría y Teledetección.

 Sciacchitano S., 2009 Conferenza. Free Sky - From Uav to Uas: il volo di terza generazione
per le emergenze territoriali. World Aeronautical Press Agency.

 Walter, G., 2013. Implementazione software di algoritmi per la progettazione di rilievi
fotogrammetrici da UAV. Tesi di laurea trienale in Ingegneria Civile. Università di Pisa.

 Wenzel, K., Rothermel, M., Fritsch, D., Haala, N., 2013. Image acquisition and model
selection for multi-view stereo. International Archives of the Photogrammetry, Remote
Sensing and Spatial Information Sciences, Volume XL-5/W1, 2013 3D-ARCH 2013 - 3D
Virtual Reconstruction and Visualization of Complex Architectures, 25 – 26 Febrero, Trento,
Italia.

235

<!-- p. 245 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

CONFERENCIAS

 Open Day della Ricerca. Incontri con la scienza, conferenze e progetti di ricerca in mostra.
Università di Pisa. Pisa. 8 y 9 Mayo 2013

236

<!-- p. 246 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

CAPÍTULO 8. LA TERMINOLOGÍA COMO
CUESTIÓN ABIERTA

237

<!-- p. 247 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

A. EL LEVANTAMIENTO COMO CAMPO MULTIDISCIPLINAR

El levantamiento arquitectónico, como define la “Carta del rilievo architettonico” es “la
primitiva forma de conocimiento, y por lo tanto, el conjunto de operaciones, medidas y análisis
efectuadas para comprender y documentar el bien arquitectónico en su configuración general
(también referida al contexto urbano y territorial), en sus características métricas
dimensionales, en su complejidad histórica, y en sus características estructurales y
constructivas, además de en las formales y funcionales”1. Entendiendo la complejidad de dicha
actividad, se puede deducir, como además confirma dicha carta, que para su realización, es
necesario la intervención de un equipo multidisciplinar, ya que para tener un levantamiento
preciso y completo se debe realizar un conjunto de actividades y estudios pertenecientes a
diferentes competencias profesionales.

La utilización de un equipo multidisciplinar, como se puede deducir, traen consigo un
conjunto de ventajas: cada uno de los aspectos que se deben considerar en un levantamiento, son
tratados por el experto del campo. Sin embargo, también se encuentran algunos inconvenientes,
como los conflictos que se pueden encontrar teniendo un punto de vista diferente, debiéndose
ocupar de las mismas cosas. Además, aparece el problema del uso de la terminología. Cada uno
de los profesionales que intervienen, han recibido su instrucción de diferentes figuras que
utilizaban un lenguaje concreto en muchos casos no coincidente con el de aquellos con los
cuales tendrán que trabajar.

Debe entenderse, que a parte de las diversas figuras que, teniendo un punto de vista
diferente, se ocupan de las mismas cosas, se encuentran a su vez, dentro de la misma categoría,
diferentes “escuelas” que, debido al lugar de aprendizaje, tienen su herencia a nivel
terminológico y metodológico. Un ejemplo claro de esto, se encuentra en Italia. Dentro del
campo de la arquitectura, podemos encontrar diferentes autores que utilizan la palabra “rilievo”
en un caso tanto para el acto de tomar medidas, como para el dibujo de restitución, mientras que
otros prefieren hacer una diferencia utilizando la palabra “rilevamento” para la toma de datos,
dejando la palabra “rilievo” solo para expresar el acto del dibujo para la restitución.

Así, basándose en este razonamiento, surge la idea del estudio de la terminología utilizada
por los profesionales que intervienen en el campo del levantamiento. El problema que es
expuesto por más de un autor, se considera seriamente, realizando un análisis sobre la
terminología utilizada por arquitectos, ingenieros y el resto de figuras que intervienen en el
campo del levantamiento 3D integrado para la conservación del patrimonio arquitectónico.

1 “la primigenia forma di conoscenza e quindi il complesso di operazioni, di misurazioni e di analisi atto
a comprendere e documentare il bene architettonico nella sua configurazione complessiva (anche riferita
al contesto urbano e territoriale), nelle sue caratteristiche metriche dimensionali, nella sua complessità
storica, nelle sue caratteristiche strutturali e costruttive, oltre che in quelle formali e funzionali.”

238

<!-- p. 248 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

Al problema de la terminología utilizada por diversas figuras, se encuentra añadido, en
muchos casos, el problema del idioma. Los llamados en inglés “false friends”, en algunas
ocasiones hacen que la confusión, ya existente entre términos, se agrande. En esta tesis se han
considerado estudiar los términos en 3 idiomas, el español, porque es el idioma de la tesis, el
inglés porque es el idioma internacional y el italiano por ser el idioma de la arquitectura clásica.

Otro tema a tratar dentro de este estudio es el problema que surge debido a la difusión de
diferentes software y hardware que usan un vocabulario específico, y que, varía de uno a otro.
En estos casos la terminología viene definida por la aplicación utilizada. El uso de varios de
ellos, como sucede a menudo, provoca una gran confusión al intentar definir de manera objetiva
el trabajo realizado. Un ejemplo de esto lo advierte Guidi (Guidi, Russo y Beraldin, 2010: 214)
cuando comenta que uno de los errores que podemos encontrar cuando se crea la malla, es
llamado de un modo diverso en el programa “Innovmetric Polyworks” y en el “Inus technology
Rapidform XOR2”.

B. OBJETIVOS (DEL CAPÍTULO)

La terminología es un problema que siempre ha existido entre arquitectos e ingenieros que se
han visto siempre afectados por moverse dentro del mismo campo de trabajo aun teniendo
diferentes objetivos o finalidades. Sin embargo, este se hace más evidente con la evolución de
una tecnología aplicada en los levantamientos tridimensionales en el mundo del patrimonio
arquitectónico. Diferentes figuras se ven implicada en el uso de esta nueva tecnología que
permite su uso en campos diferentes y, a su vez, relacionados por un interés común, la
conservación del patrimonio. De este modo, un campo que es el de la topográfica, primero
reducido a un campo específico de la ingeniería, se abre puertas entrando en campos como
puede ser el de la arquitectura, la arqueología, la geología, el computer graphics para el
entretenimiento, etc. Personas de estos campos se ven obligadas a aprender rápidamente el uso
de instrumentos que permitan un mayor avance en sus investigaciones en un tiempo menor, pero
eso supone que cada uno utilice una terminología más acorde a su campo, adaptando los
conceptos a su léxico habitual. Así, cuando se intenta hacer un estudio de esta nueva tecnología
más allá de un campo concreto, surge el problema de unir conceptos con un nombre o término
concreto.

El objetivo de este capítulo es por lo tanto ese, unir conceptos con un nombre o termino
concreto. Estudiar los términos que se utilizan en los diferentes campos para un concepto
exacto, y elegir cual se considera el más adecuado, aprovechando, además, este análisis
comparativo, para individualizar términos y conceptos sobrepuestos, análogos y redundantes,
comprendiéndose que a veces no es un problema de confusión, sino la intención de evitar
demasiadas repeticiones en un mismo texto de una palabra en concreto.

2 El software “Inus technology Rapidform XOR” ha sido adquirido recientemente por la empresa 3D
System, por ello, en la actualidad, este programa ha pasado a llamarse “Geomagic Design X”.

239

<!-- p. 249 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

Además, se realizará este estudio en los tres idiomas comentados, permitiendo de este modo,
no marcar una limitación geográfica, sino poder llegar a la gran mayoría de expertos que se
ocupan de este campo.

Debe tenerse en cuenta, sin embargo, que para la elección de los conceptos, y sus relativos
términos, se ha marcado un campo concreto que ha permitido la selección de un conjunto de
términos específicos. Este campo es el levantamiento 3D integrado y la restitución a partir de
éste. Por lo tanto, para la elección de los conceptos se escogen aquellos que tienen una relación
directa con el tema y que a su vez se han utilizado a lo largo de la tesis para explicar la
importancia de la integración entre las técnicas de levantamiento avanzadas para una restitución
en 3D.

C. METODOLOGÍA (DEL CAPÍTULO)

La estructura de este capítulo se ha decido así, buscando en primer lugar una presentación de
los términos y conceptos usados en el lenguaje utilizado para hablar de los temas referentes a la
tesis, y en segundo lugar, permitiendo un fácil uso del capítulo, que permite encontrar cada uno
de los términos, siendo este elegido como el principal o como un sinónimo.

Para el desarrollo de este capítulo se han leído una gran cantidad de artículos y diversos
libros relacionados con el tema del levantamiento 3D integrado con herramientas avanzadas
para la conservación del patrimonio arquitectónico. A partir de esta lectura, se realiza una
selección de artículos, libros y autores que permiten poder identificar los diferentes conceptos
que se consideran interesantes e importantes para poder analizar la terminología y realizar la
clasificación efectuada.

Por otra parte, se considera interesante la agrupación de los términos en diversas familias que
permitan concentrar todos los conceptos referentes a un subtema específico en un mismo
apartado. De este modo la búsqueda se hace más práctica si se desea comprobar un tema
específico y todos los conceptos relacionados con éste. Así, como se explica en el siguiente
apartado, la terminología se divide en diversos campos elegidos por ser las temáticas principales
que se engloban en la tesis.

D. CAMPOS

Para realizar la clasificación de la terminología y permitir una mayor claridad y facilidad de
uso se decide dividir los términos en 6 grandes familias o grupos. Cada uno de ellos concentra
aquellos conceptos considerados interesantes y la combinación de términos usados para
referirlos, ya sea por un uso que el autor da específico a un término para hablar de ese concepto
marcado, o por la elección de diversos vocablos para no repetir la misma palabra, buscando el
uso de sinónimos. Los campos elegidos son los siguientes:

240

<!-- p. 250 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

 Levantamiento-Metodología. Este campo es un poco más genérico por lo que a parte de tener
como el resto la parte de conceptos, tiene una selección de términos que incluye cualidades,
que ciertamente pueden encontarse referidas a cualquiera de los términos de los otros
campos. En esta familia, debe entenderse que se podrían encontrar una cantidad infinita de
términos, sin embargo, se han seleccionado aquellos que formando parte de este tema más
genérico, tienen siempre esta relación directa con la nueva tecnología integrada.

 Fotogrametría. En este grupo se engloban aquellos conceptos que en general se utilizan para
hablar de la fotogrametría y más en lo específico para tratar las nuevas técnicas de Image-
based Modelling.

 Escáner Láser. En esta familia los conceptos seleccionados hacen referencia a las técnicas de
Range-based Modelling, definiendo su terminología tan variante de un autor a otro.

 Topografía. El campo de la topografía es muy amplio como se habla en el capítulo del estado
del arte, por lo que aquí se hace una selección de los conceptos que formando parte de éste
tienen una relación con las herramientas avanzadas referidas a lo largo de la tesis.

 Imagen. Teniendo en cuenta la importancia que cobra el cromatismo en la restitución
integrada y las imágenes utilizadas para ello, es importante definir aquellos conceptos que
forman parte de éste campo.

 Edición 3D. Como se comenta a lo largo de toda la tesis, la finalidad del arquitecto no es el
levantamiento en sí, sino el estudio arquitectónico que puede realizar a partir de éste, de aquí
que este campo sea tan importante como los anteriores.

241

<!-- p. 251 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

E. TÉRMINOS Y CONCEPTOS

i. Campo 1.- LEVANTAMIENTO - METODOLOGÍA
CONCEPTOS

Levantamiento / Rilievo / Survey.
 Sinónimos: Rilevamento, Toma de datos, 3D data acquisition, 3D capturing techniques, Fase
di acquisizione, Adquisición de datos, 3D Acquisition piperline, Acquisizione dei dati.
 Definición: “El término levantamiento es utilizado en el ámbito topográfico y se refiera a la
toma de datos de un objeto y su representación gráfica, en tres dimensiones o utilizando
algún sistema de proyección siendo el sistema acotado el más utilizado como representación
final”
 Comentarios: Algunos conceptos relacionados con este término son: Riprese3 (Apollonio,
F.I. y Remondino, F., 2010) Range map4 (Apollonio, F.I. y Remondino, F., 2010) (Guidi, G.,
Russo, M. y Beraldin, J.A., 2010) (Arbacea, L., et al, 2013)
 Referencias:
Apollonio, F.I., et al, 2010
Apollonio, F.I. y Remondino, F., 2010
Baldissini, S., Gaiani, M. y Remondino, F., 2010
Balzani, M., Ferrari, F. y Viroli, F., 2012
Bertocci, S., Bini, M., 2012
Bianchini, C., 2007
Biosca Taronger, J.M., Navarro Tarín, S. y Lerma García, J.L., 2007
Buill, F., Nuñez, M.A., Rodríguez, J.J., 2007
Docci, M., Maestri, D. 1984
Dore, C. y Murphy, M., 2012
Fantini, F., 2012
Fantini, F., Rodríguez-Navarro, P. y Di Tondo, S., 2012
Guidi, G. y Remondino, F., 2012
Guidi, G., Russo, M. y Angheleddu, D., 2013
Guidi, G., Russo, M. y Beraldin, J.A., 2010
Herráez Boquera, J., Navarro Esteve, P y Denia Ríos, JL., 2010
Koska, B. y Křemen, T., 2013
Lerma, J.L. et al,2011
Manferdini, A.M. y Remondino, F., 2010
Mañana-Borrazás, P., Rodríguez Paz, A. y Blanco-Rotea, R., 2008
Marambio, A. et al, 2009
Merlo, A., 2007
Riveiro Rodríguez, B. et al, 2011
Rodríguez Navarro, P., 2012
Verdiani, G., 2003

3 Scanzioni
4 Apollonio, F.I. y Remondino, F., 2010, p. 100): “prodotto di ogni singola ripresa, in particolare per
sistema a triangolazione, e consiste in una matrice di punti” (Producto de cada individual captura, en
particular por sistema a triangulación, y consiste en una matriz de puntos)

242

<!-- p. 252 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

Wenzel, K. et al, 2013
 Notas: La definición se ha realizado a partir de la descripción de Buill, Nuñez y Rodríguez
(2007, p. 15). Otra definición se encuentra en Guidi, G., Russo, M. y Beraldin, J.A. (2010, p.
196): “La sequenza di operazioni necessaria per giungere al modello digitale (Bernardini e
Rushmeier, 2002)”. En páginas sucesivas añade (p. 203) “adquisizione: fase rappresentata
dal tempo necessario a catturare l’immagine.” (adquisición: fase representada por el tiempo
necesario para capturar la imagen) “L’acquisizione tridimensionale va quindi effettuata
fissando l’attrezzatura su un cavalletto ed orientandola verso la zona di interesse.” (La
adquisición tridimensional va entonces efectuada fijando el equipo sobre un tripode y
orientandola hacia la zona de interés). Apollonio, F.I., et al, (2010, p. 273) la define, sin
embargo, como “consiste nel rilievo della posizione dei punti nello spazio, ponendo
attenzione alle caratteristiche dello strumento.” (Consiste en el levantamiento de la posición
de los puntos en el espacio, teniendo en cuenta las características del instrumento)

Exactitud / Accuratezza / Accuracy.
 Sinónimos:
 Definición: Es el grado de concordancia entre el valor de la magnitud medida y un valor de
la cantidad real de un mesurando.
 Comentarios:
 Referencias:
Amoruso, G., Apollonio, F.I. y Remondino, F. 2010
Apollonio, F.I. y Remondino, F., 2010
Balzani, M., Ferrari, F. y Viroli, F., 2012
Buill, F., Nuñez, M.A., Rodríguez, J.J., 2007.
Guidi, G. y Remondino, F. 2012
Guidi, G., Russo, M. y Beraldin, J.A., 2010
Herráez Boquera, J., Navarro Esteve, P y Denia Ríos, JL., 2010Lerma, J.L. et al, 2010
Manferdini, A.M. y Remondino, F., 2010
Merlo, A., 2007
Migliari, R., 2012
Verdiani, G., 2003
Wenzel, K. Et al, 2013
 Notas: Definición según el VIM (International Vocabulary Metrology) (Guidi, G. y
Remondino, F. 2012, p. 86): “closeness of agreement between a measured quantity value
and a true quantity value of a measurand” Otra definición la encontramos según Guidi, G.,
Russo, M. y Beraldin, J.A., (2010, p. 126) “rappresenta l’errore tra la misura di una
quantità e il suo vero valore (o il valore accettato per vero). Nel caso di misure ripetute di
uno stesso valore si può determinare come la distanza tra la media dei dati misurati e il dato
reale” (representa el error entra la medida de una cantidad y su valor real (o el valor
aceptado como real). En el caso de medidas repetidas de un mismo valor se puede
determinar como la distancia entra la medida de los datos medidos y su dato real). Buill, F.,
Nuñez, M.A., Rodríguez, J.J. (2007), sin embargo, la definen como “es la fidelidad en la
ejecución de una medida, es decir, la diferencia entre el valor medido y el valor real o valor
verdadero de la magnitud medida”

243

<!-- p. 253 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

Error topológico / errore topologico / topological error.
 Sinónimos:
 Definición: Imperfecciones en los polígonos generados en la conversión de la nube de puntos
a malla poligonal.
 Comentarios:
 Referencias:
Biosca Taronger, J.M., Navarro Tarín, S. y Lerma García, J.L., 2007
Guidi, G., Russo, M. y Beraldin, J.A., 2010
Rodríguez Navarro, P., 2012
 Notas: Definición inspirada en Marambio, A. et al (2009, p. 2). Otra descripción se encuentra
en Biosca Taronger, J.M., Navarro Tarín, S. y Lerma García, J.L. (2007, p. 3): “como por
ejemplo son los triángulos que se cruzan o más de dos triángulos que comparten un mismo
lado” También se encuentra otra definición en Guidi, G., Russo, M. y Beraldin, J.A. (2010,
p. 213): “Possono crearsi sporadiche connessioni anormale tra poligoni che non hanno
mitvo logico di esistere e possono essere immediatamente individuate come errori
topologici” (Pueden crearse esporádicamente conexiones anormales entre polígonos que no
tienen un motivo lógico de existir y pueden ser inmediatamente individualizadas como
errores topológicos).

Precisión / precisione / precision.
 Sinónimos: Uncertainty.
 Definición: La precisión es el grado de concordancia entre las indicaciones o medidas o
valores de cantidad medida obtenida mediante la réplica de medidas en el mismo o similar
objeto, bajo condiciones específicas.
 Comentarios: La “Uncertainty” es definida por Guidi, G. y Remondino, F. (2012, p .86)
como precision. Un concepto relacionado con este término es: “Desviación estándar”5
(Lerma, J.L. et al, 2011).
 Referencias:
Arbacea, L., et al, 2013
Balzani, M., Ferrari, F. y Viroli, F., 2012
Biosca Taronger, J.M., Navarro Tarín, S. y Lerma García, J.L., 2007
Buill, F., Nuñez, M.A., Rodríguez, J.J., 2007
Docci, M., Maestri, D. 1984
Guidi, G. y Remondino, F., 2012
Guidi, G., Russo, M. y Beraldin, J.A., 2010
Herráez Boquera, J., Navarro Esteve, P y Denia Ríos, JL., 2010
Lerma, J. L. et al, 2011
Marambio, A. et al, 2009
Riveiro Rodríguez, B. et al, 2011
 Notas: Interpretación de la definición de Guidi, G. y Remondino, F. (2012, p .86) de
Uncertainty “(precision): Precision is the closeness of agreement between indications or
measured or measured quantity values obtained by replicate measurement on the same or
similar object under specified conditions”. La “precisione” según la definición de Guidi, G.,

5 Lerma, J.L. et al (2011, p. 114): “las discrepancias están del orden de la precisión (desviación estándar)
del escáner”

244

<!-- p. 254 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

Russo, M. y Beraldin, J.A., (2010, p. 126) “è rappresentata dalla dispersione delle misure
intorno alla loro media” (es representada de la dispersión de las medidas entorno a su
media). Buill, F., Nuñez, M.A., Rodríguez, J.J. (2007, p. 16) la describen, sin embargo, como
“se puede entender como el número de cifras decimales con las que se representa una
determinada magnitud”

Distorsión / distorsione / Distortion.
 Sinónimos:
 Definición: Es la deformación de una señal tras su paso por un sistema.
 Comentarios:
 Referencias:
Buill, F., Núñez, M.A. y Rodríguez, J.J., 2007
Lerma, J. L. et al, 2011
Wenzel, K. et al, 2013
 Notas: Definición inspirada en la definición de distorsión encontrada en Wikipedia (última
visita 24/11/2013).

Datos brutos / Dati grezzi / Raw data.
 Sinónimos:
 Definición: Datos que se obtienen con el escáner antes de hacer cualquier intervención o de
ser modificados, por parte del operador.
 Comentarios: Algunos conceptos relacionados con este término son: Nuvola grezza
(Bianchini, C., 2007), Barridos (Riveiro Rodríguez, B. et al, 2011).
 Referencias:
Biosca Taronger, J.M., Navarro Tarín, S. y Lerma García, J.L., 2007
Guidi, G., Russo, M. y Beraldin, J.A., 2010
 Notas: El término en este caso ha sido definido por la autora

Medición / Misurazioni / Mesurement.
 Sinónimos:
 Definición: Acción y efecto de comparar una cantidad con su respectiva unidad, con el fin
de averiguar cuántas veces la segunda está contenida en la primera.
Comentarios: Algunos conceptos relacionados con este término son: Documentación
métrica (Biosca Taronger, J.M., Navarro Tarín, S. y Lerma García, J.L., 2007), Sistema de
medición (Riveiro Rodríguez, B. et al, 2011) (Herráez Boquera, J., Navarro Esteve, P y
Denia Ríos, JL., 2010), Photogrammetric measurement (Wenzel, K. et al, 2013).
 Referencias:
Docci, M., Maestri, D. 1984
Guidi, G. y Remondino, F., 2012
Herráez Boquera, J., Navarro Esteve, P y Denia Ríos, JL., 2010
Lerma, J.L. et al, 2010
Lerma, J.L., et al., 2011
Verdiani, G., 2003.
Wenzel, K. et al, 2013
 Notas: Definición de la RAE (última visita: 22/11/2013).

245

<!-- p. 255 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

Recubrimiento / Ricoprimento / Correspondences across.
 Sinónimos: Ricopertura, Sovraposizione delle prese, Image overlapping, área de solape.
 Definición: Superposición de las imágenes captadas, para permitir en el “Image-based
modeling”, mediante la obtención de puntos homólogos.
 Comentarios:
 Referencias:
Amoruso, G., Apollonio, F.I. y Remondino, F. 2010
Apollonio, F.I. y Remondino, F., 2010
Docci, M., Maestri, D. 1984
Guidi, G., Russo, M. y Beraldin, J.A., 2010
Herráez Boquera, J., Navarro Esteve, P y Denia Ríos, JL., 2010
Lerma, J.L. et al, 2011
Remondino et al, 2012
 Notas:

Diana / target / target.
 Sinónimos: Control point, Puntos de control, Diana de control.
 Definición: “Elemento cuya posición fija es registrada en cada escaneo y que sirve como
referencia para combinarlos”
 Comentarios: Algunos autores españoles también usan el término target. Algunos conceptos
relacionados con este término son: Dianas esféricas y circulares (Biosca Taronger, J.M.,
Navarro Tarín, S. y Lerma García, J.L., 2007), Target coordinate system (Wenzel, K. et al,
2013), Dianas naturales (Cueli López, J., 2010), Dianas codificadas = Coded Target (Cueli
López, J., 2010) Guidi, G. y Remondino, F. 2012.
 Referencias:
Amoruso, G., Apollonio, F.I. y Remondino, F. 2010
Apollonio, F.I. y Remondino, F., 2010
Balzani, M., Ferrari, F. y Viroli, F., 2012
Buill, F., Nuñez, M.A. y Rodríguez, J.J., 2007
Cueli López, J., 2010
Dore, C. y Murphy, M., 2012
Guidi, G. y Remondino, F., 2012
Herráez Boquera, J., Navarro Esteve, P y Denia Ríos, JL., 2010
Koska, B. y Křemen, T., 2013
Lerma, J.L. et al,2010
Mañana-Borrazás, P., Rodríguez Paz, A. y Blanco-Rotea, R., 2008
Wenzel, K. Et al, 2013
 Notas: Definición que se encuentra en el artículo (Mañana-Borrazás, P., Rodríguez Paz, A. y
Blanco-Rotea, R., 2008, p. 19). La definición de Guidi, G. y Remondino, F. (2012, p. 90)
sería “Measuring some reference points on the scene with a surveying system like for
example a total station, allows to define a global reference system in which such targets are
represented”.

246

<!-- p. 256 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

Terrestre / terrestre / terrestrial.
 Sinónimos:
 Definición: Adjetivo que se utiliza para referirse a cualquier sustantivo que se realiza, se
utiliza, funciona o sucede en el suelo o corteza terrestre.
 Comentarios:
 Referencias:
Buill, F., Nuñez, M.A. y Rodríguez, J.J., 2007
Buill Pozuelo, F., Núñez Andrés, M.A. y Marambio Castillo, A.
Cannarozzo, Cucchiarini y Meschieri, 2012Dore, C. y Murphy, M., 2012
Guidi, G. y Remondino, F. 2012
Koska, B. y Křemen, T., 2013
Lerma, J.L. et al, 2010
Lerma, J.L. et al, 2011
Mañana-Borrazás, P., Rodríguez Paz, A. y Blanco-Rotea, R., 2008
Marambio, A., Pucci, B., Nuñez, M.A. y Buill, F., 2009
Riveiro Rodríguez, B. et al, 2011
Wenzel, K. Et al, 2013
 Notas: Definición de la autora a partir de las definiciones leídas en Wikipedia y
www.thefreedictionary.com.

Aéreo / aereo / aerial.
 Sinónimos:
 Definición: Adjetivo que se utiliza para referirse a cualquier sustantivo que se realiza, se
utiliza, funciona o sucede en el aire.
 Comentarios:
 Referencias:
Buill, F., Nuñez, M.A. y Rodríguez, J.J., 2007
Cannarozzo, Cucchiarini y Meschieri, 2012
Guidi, G. y Remondino, F. 2012
Herráez Boquera, J., Navarro Esteve, P y Denia Ríos, JL., 2010
Koska, B. y Křemen, T., 2013
Lerma, J.L., et al, 2010
Lerma, J.L., et al, 2011
Wenzel, K. et al, 2013
 Notas: Definición deducida a partir de la definición de terrestre.

Calibración / calibrazione / calibration.
 Sinónimos:
 Definición: La calibración de cualquier sistema activo o pasivo consiste en la extracción de
los parámetros característicos internos de funcionamiento, tales que permitan controlar en
manera global el comportamiento del instrumento y los errores introducidos en la
adquisición del dato

247

<!-- p. 257 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

 Comentarios: Algunos conceptos relacionados con este término son: Calibration and
orientation data (Lerma, J.L. et al, 2010), Calibration pattern (patrón de calibración)
(Wenzel, K. et al, 2013), Geometric camera calibration6 (Guidi, G. y Remondino, F. 2012),
Radiometric calibration (Guidi, G. y Remondino, F. 2012), Calibrar inversamente (Cueli
López, J., 2010), Corrección del eje óptico (Cueli López, J., 2010), Metodo proiettivo
inverso7 (Apollonio, F.I., et al, 2010), Proceso de autocalibración (Biosca Taronger, J.M.,
Navarro Tarín, S. y Lerma García, J.L., 2007)
 Referencias:
Biosca Taronger, J.M., Navarro Tarín, S. y Lerma García, J.L., 2007
Buill, F., Núñez, M.A. y Rodríguez, J.J., 2007
Corsini, M., et al, 2013
Cueli López, J., 2010
Guidi, G. y Remondino, F. 2012
Guidi, G., Russo, M. y Beraldin, J.A., 2010
Herráez Boquera, J., Navarro Esteve, P y Denia Ríos, JL., 2010
Koska, B. y Křemen, T., 2013
Lerma, J.L., et al, 2011
Manferdini, A.M. y Remondino, F., 2010
Rodríguez Navarro, P., 2012
Verdiani, G., 2003
 Notas: Interpretación de la definición de Guidi, G., Russo, M. y Beraldin, J.A. (2010, p.
125): “La calibrazione di un qualsiasi sistema attivo o passivo consiste nell’estrazione dei
parametri caratteristici interni di funzionamento, tali da poter controllare in maniera
globale il comportamento dello strumento e gli errori introdotti nell’acquisizione del dato.”
En otras páginas añaden (pp. 51): “In fotogrammetria si cerca di identificare come e perché
la geometria di un’immagine in una camera reale differisce dalla geometria di una camera
stenopeica. Questa procedura è conosciuta come calibrazione della camera.” (En
fotogrametría se busca determinar cómo y porqué la geometría de una imagen en una
cámara real difiere de la geometría en una cámara métrica. Este proceso es conocido como
calibración de la cámara.) (pp. 62) “Consiste nel determinare tutti i parametri interni alla
camera” (Consiste en determinar todos los parámetros internos de la cámara.) Otra
definición se encuentra en Manferdini, A.M. y Remondino, F. (2010, p. 170): “procedura
per la quale lo strumento viene calibrato. In molte applicazioni la fase di calibrazione delle
camere consiste nella sola determinazione della lunghezza focale (...) con la calibrazione si
determina la deviazione geometrica gra la realità (collinearità) e il sistema di acquisizione
delle immagini.” (Proceso por el cual viene el instrumento calibrado. En muchas
aplicaciones la fase de calibración de las cámaras consiste en la sola determinación de la

6 Guidi, G. y Remondino, F. (2012, p. 82) “is defined as the determination of deviations of the physical
reality from a geometrically ideal imaging system based on the collinearity principle: the pinhole
camera.”(se define como la determinación de las desviaciones de la realidad física de un sistema de
formación de imágenes geométricamente ideales basado en el principio de colinealidad: la cámara de
agujero de alfiler).
7 Apollonio, F.I., et al, (2010, p. 283): “si basa sostanzialmente sul ritrovamento dei parametri interni ed
esterni della camera.” (Se basa sustancialmente en el encuentro de los parámetros internos y externos de
la cámara”

248

<!-- p. 258 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

longitud focal… con la calibración se determina la desviación geométrica entre la realidad
(colinealidad) y el sistema de adquisición de las imágenes).

Auto-calibración / auto-calibrazione / Self-calibration.
 Sinónimos: Automatic camera calibration, Autocalibration.
 Definición: Procedimiento que presentan algunos programas para calcular los parámetros de
calibración de la cámara automáticamente a partir de fotografías que presenten un mínimo
del 30% de superposición.
 Comentarios:
 Referencias:
Biosca Taronger, J.M., Navarro Tarín, S. y Lerma García, J.L., 2007
Buill, F., Núñez, M.A. y Rodríguez, J.J., 2007
Corsini, M., et al, 2013
Cueli López. J., 2010
Guidi, G. y Remondino, F. 2012
Lerma, J.L. et al, 2010
Wenzel, K. et al, 2013
 Notas: Cueli López, J., 2010: Tutorial 4. Calibración de la cámara. Guidi, G. y Remondino,
F. (2012, p. 83) “The solution of a self-calibrating bundle adjustment leads to the estimation
of all the interior parameters and APs, starting from a set of manually or automatically
measured image correspondences (tie points)” (La solución de un paquete de ajuste de auto-
calibración conduce a la estimación de todos los parámetros interiores y parámetros
adicionales, de forma manual o de forma automática, a partir de un conjunto de
correspondencias imágenes medidas (puntos de unión)).

Method Bundle Adjustment / Method Bundle Adjustment / Method Bundle Adjustment.
 Sinónimos:
 Definición: Proporciona una determinación simultánea de todos los parámetros del sistema
junto con las estimaciones de la precisión y la fiabilidad de las incógnitas.
 Comentarios: Algunos conceptos relacionados con este término son: Self-calibration bundle
adjustment8 (Guidi, G. y Remondino, F. 2012) Method Self-calibrating bundle adjustment9
(Guidi, G. y Remondino, F. 2012) (Apollonio, F.I. et al, 2010).

8 Guidi, G. y Remondino, F. (2012, p. 83) “The solution of a self-calibrating bundle adjustment leads to
the estimation of all the interior parameters and APs, starting from a set of manually or automatically
measured image correspondences (tie points)” (La solución de un paquete de ajuste de auto-calibración
conduce a la estimación de todos los parámetros interiores y parámetros adicionales, de forma manual o
de forma automática, a partir de un conjunto de correspondencias imágenes medidas (puntos de unión))
9 Guidi, G. y Remondino, F. (2012, p. 72) “Method bundle adjustment but the interior orientation
parameters are also unknowns.” (Es igual al método “bundle adjustment” pero los parámetros de
orientación interior también son incógnitas). Otra definición se encuentra en Apollonio, F.I. et al, (2010,
p. 294): “consiste nella ripresa da numerosi punti di vista di una serie di target che permettono la loro
misura in maniera automatica ed accurata nelle immagini.” (Consiste en la captura desde numerosos
puntos de vista de una serie de target que permiten su medida en una modo automático y preciso en las
imágenes)

249

<!-- p. 259 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

 Referencias:
Apollonio, F.I. et al, 2010
Guidi, G. y Remondino, F. 2012
Wenzel, K. et al, 2013
 Notas: Guidi, G. y Remondino, F. (2012, p. 72) “provides a simultaneous determination of
all system parameters along with estimates of the precision and realiability of the
unknowns”.

UAV / UAV / UAV.
 Sinónimos: drone
 Definición: Acrónimo de Unmanned Aerial Vehicles. Dicho acrónimo se utiliza para definir
la tecnología inalámbrica en los dispositivos de aire con vehículos aéreos no tripulados,
como helicópteros a control remoto, cometas o globos
 Comentarios:
 Referencias:
Cannarozzo, Cucchiarini y Meschieri, 2012
Guidi, G. y Remondino, F. 2012
Koska, B. y Křemen, T., 2013
Lerma, J.L., et al, 2010
Manferdini, A.M. y Remondino, F., 2010
 Notas: Interpretación de la definición realizada por Lerma, J.L., et al (2010, p. 500) “(UAV):
wireless technology on air devices with unmanned aerial vehicles such as remote-controlled
helicopters, kites or balloons.” Otra definición se encuentra en Manferdini, A.M. y
Remondino, F. (2010, p. 166): “Piccole piattaforme (aeroplani o elicotteri senza piloti a
bordo) che possono essere controllati da una postazione remota o che possono volare
autonomamente utilizando piano di volo pre.programmati.” (Pequeñas plataformas
(aeroplanos o helicópteros sin piloto a bordo) que pueden ser controlados desde una posición
remota o que pueden volar autónomamente utilizando plan de vuelo pre-programados).

Digitalización / Digitalizzazione / digitizing.
 Sinónimos:
 Definición: “Es la generación de un modelo informático tridimensional de un objeto”
 Comentarios: Algunos conceptos relacionados con este término son: Representación virtual
(Biosca Taronger, J.M., Navarro Tarín, S. y Lerma García, J.L., 2007), Reproducción virtual
(Marambio, A., et al, 2009).
 Referencias:
Biosca Taronger, J.M., Navarro Tarín, S. y Lerma García, J.L., 2007
Manferdini, A.M. y Remondino, F., 2010
 Notas: Definición sacada de Torres, J.C., Cano, P., Melero, J., Espana, M., Moreno, J., 2010.
Aplicaciones de la digitalización 3D del patrimonio. Virtual Archaeology Review. Volumen
1 Número 1. ISSN: 1989-9947. P. 51. (http://varjournal.es/doc/varj01_001_14.pdf)

Flujo de trabajo / Pipeline / Pipeline.
 Sinónimos: Workflow

250

<!-- p. 260 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

 Definición: Metodología seguida para llegar a un objetivo concreto.
 Comentarios:
 Referencias:
Corsini, M., et al, 2013
Dore, C. y Murphy, M., 2012
Fantini, F., 2012
Fantini, F., Rodríguez-Navarro, P. y Di Tondo, S., 2012
Guidi, G. y Remondino, F. 2012
Guidi, G. y Remondino, F. 2012
Manferdini, A.M. y Remondino, F., 2010
Wenzel, K. et al, 2013
 Notas:

Modelado inverso / Reverse modelling / Reverse modelling.
 Sinónimos: Reverse engineering process.
 Definición: Se trata de un proceso inverso al proyectual en sentido canónico: el objeto físico
representa el dato de inicio, mientras el modelo digital constituye el producto final del
proceso de modelización.
 Comentarios:
 Referencias:
Apollonio, F.I., et al, 2010
Dore, C. y Murphy, M., 2012
Fantini, F., 2012
Guidi, G., Russo, M. y Beraldin, J.A., 2010
Rodríguez Navarro, P., 2012
 Notas: Traducción de la definición de Guidi, G., Russo, M. y Beraldin, J.A., (2010, p. 195):
“si tratta di un processo inverso a quello progettuale in senso canonico: l’oggetto fisico
rappresenta il dato di partenza, mentre il modello digitale costituisce il prodotto finale del
processo di modellazione”.

Optimización / Ottimizzazione / Optimization.
 Sinónimos:
 Definición: Es un paso útil final, en cualquier caso aplicativo, donde se puede obtener una
reducción significativa del tamaño de malla, realizando una decimación inteligente basada en
la curvatura del modelo. La optimización de un modelo High-poly, convierte a éste en un
modelo Low-poly aplicándole un mapa de normales y de desplazamiento adecuado para
mantener un nivel alto de detalle
 Comentarios:
 Referencias:
Battini, C., Fantini, F., 2007
Biosca Taronger, J.M., Navarro Tarín, S. y Lerma García, J.L., 2007
Fantini, F., 2010
Fantini, F., 2012
Guidi, G. y Remondino, F. 2012
Herráez Boquera, J., Navarro Esteve, P y Denia Ríos, JL., 2010

251

<!-- p. 261 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

Koska, B. y Křemen, T., 2013
Marambio, A., et al, 2009
 Notas: Guidi, G. y Remondino, F. (2012, p. 93) “is instead a final useful step in any
applicative case, where a significant reduction of the mesh size can be obtained”. Fantini, F.
(2010: 1)

Nivel de detalle / Livello di dettaglio / Levels of Detail (LOD).
 Sinónimos: Degree of detail
 Definición: La idea de los niveles de detalle desciende del concepto de optimización del
modelo en base al objetivo para el cual es destinado. La aplicación consiste en generar
modelos a diferentes niveles de resolución geométrica y elegir el nivel según el objetivo para
el cual sea creado.
 Comentarios:
 Referencias:
Apollonio, F.I., Gaiani, M. y Manferdini, A.M., 2010
Fantini, F., 2010
Fantini, F., 2012
Fantini, F., Rodríguez-Navarro, P. y Di Tondo, S., 2012
Guidi, G. y Remondino, F. 2012
Guidi, G., Russo, M. y Beraldin, J.A., 2010
Lerma, J.L. et al, 2010
Marambio, A. et al, 2009
 Notas: Interpretación del término definido por Guidi, G., Russo, M. y Beraldin, J.A. (2010,
p.317): “discende dal concetto di ottimizzazione del modello in base allo scopo cui è
destinato”. Este término, sin embargo, es definido en Marambio, A. et al (2009, p. 4) como
“Distancia entre las posiciones del escáner y distancia entre las medidas adquiridas”.

Iterative Closest Point (ICP) / Iterative Closest Point (ICP) / Iterative Closest Point (ICP).
 Sinónimos:
 Definición: Se compone de dos pasos: en el primero vienen identificadas parejas hipotéticas
de puntos correspondientes en el área de sobreposición de dos “range map”. Sucesivamente
se hace un procedimiento de optimización que consiste en una transformación rígida que
reduce la distancia (mediante el cálculo de mínimos cuadrados) entre los dos conjuntos de
puntos. El proceso viene, entonces, repetido hasta que no son satisfactorios los criterios de
convergencia
 Comentarios:
 Referencias:
Apollonio, F.I. y Remondino, F., 2010
Biosca Taronger, J.M., Navarro Tarín, S. y Lerma García, J.L., 2007
Guidi, G. y Remondino, F. 2012
Rodríguez Navarro, P., 2012
Wenzel, K. et al, 2013
 Notas: Interpretación de la definición encontrada en Apollonio, F.I. y Remondino, F. (2010,
p. 102): “(ICP) Si compone di due passi: nel primo vengono identificate coppie di ipotetici
punti corrispondenti nell’area di sovraposizione di due range map. Succesivamente è
avviata una procedura di ottimizzazione che computa una trasformazione rigida che riduce

252

<!-- p. 262 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

la distanza (nel senso dei minimi quadrati) tra i due insiemi di punti. Il processo viene,
quindi, iterato fino a che non siano soddistatti i criteri di convergenza.” Otra descripción se
encuentra en Guidi, G. y Remondino, F. (2012, p.90): “Using as references natural 3D
features in the scene is a possible alternative somehow similar to the previous one. The only
difference is that no special target has to be fixed on the scene and individually measured by
the operator.” (Utilizar para orientar como referencias características naturales en 3D de la
escena. Una diana natural tiene que ser fija en la escena y se mide de forma individualizada
por el operador).

CUALIDADES

Tridimensional / tridimensionale / 3D Three-dimensional.
 Sinónimos:
 Definición: adjetivo que se utiliza para referenciar un objeto definido en 3 dimensiones.
 Comentarios:
 Referencias:
Arbacea, L., et al, 2013
Baldissini, S., Gaiani, M. y Remondino, F., 2010
Balzani, M., Ferrari, F. y Viroli, F., 2012
Biosca Taronger, J.M., Navarro Tarín, S. y Lerma García, J.L., 2007
Buill, F., Núñez, M.A., Rodríguez, J.J, 2007
Corsini, M., et al, 2013
Dore, C. y Murphy, M., 2012
Guidi, G. y Remondino, F. 2012
Guidi, G., Russo, M. y Beraldin, J.A., 2010
Herráez Boquera, J., Navarro Esteve, P y Denia Ríos, JL., 2010
Lerma, J. L. et al, 2011
Lerma, J.L. et al, 2010
Manferdini, A.M. y Remondino, F., 2010
Mañana-Borrazás, P., Rodríguez Paz, A. y Blanco-Rotea, R., 2008
Marambio, A. et al, 2009
Migliari, R., 2012
Merlo, A., 2007
Riveiro Rodríguez, B. et al, 2011
Rodríguez Navarro, P., 2012
Verdiani, G., 2003
 Notas:

Resolución / Resoluzione / Resolution.
 Sinónimos:
 Definición: El cambio más pequeño en una cantidad medida que causa un cambio
perceptible de la indicación correspondiente. El detalle mínimo geométrico que el
dispositivo de gama es capaz de capturar.
 Comentarios:

253

<!-- p. 263 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

 Referencias:
Amoruso, G., Apollonio, F.I. y Remondino, F., 2010
Arbacea, L., et al, 2013
Biosca Taronger, J.M., Navarro Tarín, S. y Lerma García, J.L., 2007
Buill, F., Nuñez, M.A., Rodríguez, J.J, 2007
Dore, C. y Murphy, M., 2012
Guidi, G. y Remondino, F., 2012
Guidi, G., Russo, M. y Beraldin, J.A., 2010
Koska, B. y Křemen, T., 2013
Lerma, J.L. et al, 2010
Lerma, J.L. et al, 2011.
Marambio, A. et al, 2009.
Remondino, F. et al, 2012
Wenzel, K. Et al, 2013
 Notas: Definición según el VIM (International Vocabulary Metrology) (Guidi, G. y
Remondino, F. 2012, p. 85): “Smallest change in a quantity being measured that causes a
perceptible change in the corresponding indication” “the minimum geometrical detail that
the range device is capable to capture”. Se encuenta definida también por Guidi, G., Russo,
M. y Beraldin, J.A. (2010, p. 126) “(massima): cossiste in generale nella più piccola
variazione del misurando che può essere misurata. Nel caso di uno strumento per rilievo tale
variazione è definita dal minimo passo di campionamento spaziale utilizzabile” (consiste en
general en la más pequeña variación del mesurando que puede ser medida. En el caso de un
instrumento para levantamiento tal variación es definada como el mínimo paso de muestreo
espacial utilizable)

Alta definición / alta definizione / High-Definition.
 Sinónimos: alto nivel de detalle, alto livello di dettaglio, alta resolución, High-resolution,
Highly detailed, Accurate.
 Definición: término que se utiliza para definir acciones realizadas a alto nivel de detalle y
precisión.
 Comentarios: Algunos conceptos relacionados con este término son: Modello HP (high-poly)
(Fantini, F., 2010) (Battini, C., Fantini, F., 2007), Modello master (Apollonio, F.I., Gaiani,
M. y Manferdini, A.M., 2010)
 Referencias:
Balzani, M., Ferrari, F. y Viroli, F., 2012
Biosca Taronger, J.M., Navarro Tarín, S. y Lerma García, J.L., 2007
Fantini, F., 2012
Koska, B. y Křemen, T., 2013
Lerma, J.L. et al, 2010
Mañana-Borrazás, P., Rodríguez Paz, A. y Blanco-Rotea, R., 2008
Marambio, A. et al, 2009
Remondino, F. et al, 2012
 Notas: Término definido por la autora.

Baja definición / bassa definizione / Low-resolution.
 Sinónimos: bajo detalle, Low detailed

254

<!-- p. 264 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

 Definición: termino que se utiliza para definir acciones realizadas a bajo nivel de detalle y
precisión.
 Comentarios: Algunos conceptos relacionados con este término son: Modelos optimizados
(Marambio, A. et al, 2009), Modelos de malla simplificados (Fantini, F., 2012).
 Referencias:
Fantini, F., 2012
Remondino, F. et al, 2012
 Notas:

Digital / digitale / digital.
 Sinónimos:
 Definición: Cuando se habla de que un objeto o un servicio es digital, se está haciendo
referencia a que el mismo se establece a partir del envío discontinuo o discreto de datos. Por
lo general, el término digital (utilizado como adjetivo) se encuentra en los ambientes
tecnológicos y de electrónica ya que es uno de los últimos avances en lo que respecta a
calidad de imagen, de sonido, de efectos, etc.
 Comentarios:
 Referencias:
Arbacea, L., et al, 2013
Baldissini, S., Gaiani, M. y Remondino, F., 2010
Bianchini, C., 2007
Biosca Taronger, J.M., Navarro Tarín, S. y Lerma García, J.L., 2007
Buill, F., Nuñez, M.A., Rodríguez, J.J, 2007
Cannarozzo, Cucchiarini y Meschieri, 2012
Dore, C. y Murphy, M., 2012
Fantini, F., 2012
Fantini, F., Rodríguez-Navarro, P. y Di Tondo, S., 2012
Guidi, G. y Remondino, F. 2012
Guidi, G., Russo, M. y Angheleddu, D., 2013
Guidi, G., Russo, M. y Beraldin, J.A., 2010
Lerma, J.L. et al, 2010Lerma, J.L. et al, 2011
Manferdini, A.M. y Remondino, F., 2010
Mañana-Borrazás, P., Rodríguez Paz, A. y Blanco-Rotea, R., 2008
Marambio, A. et al, 2009
Marambio, A., Pucci, B., Nuñez, M.A. y Buill, F., 2009
Merlo, A., 2007
Migliari, R., 2012
Remondino, F. y El-Hakim, S., 2007
Riveiro Rodríguez, B. et al, 2011
Rodríguez Navarro, P., 2012
Verdiani, G., 2003
Wenzel, K. et al, 2013
 Notas: http://www.definicionabc.com/tecnologia/digital.php#ixzz2leq3RvOO (última visita:
25/11/2013)

255

<!-- p. 265 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

Fotorrealista / fotorealistico / photo-realistic.
 Sinónimos:
 Definición: Adjetivo usado para hablar de modelos digitales, que a la información
geométrica conseguida a través de un instrumento para la adquisición tridimensional,
integran la textura obtenida mediante fotografías.
 Comentarios: Un concepto relacionado con este término es: Apparenza visiva10 (Apollonio,
F.I. y Remondino, F., 2010)
 Referencias:
Apollonio, F.I. y Remondino, F., 2010
Biosca Taronger, J.M., Navarro Tarín, S. y Lerma García, J.L., 2007
Fantini, F., Rodríguez-Navarro, P. y Di Tondo, S., 2012
Guidi, G. y Remondino, F. 2012
Guidi, G., Russo, M. y Beraldin, J.A., 2010
Lerma, J.L. et al, 2010
Lerma, J. L. et al, 2011
Rodríguez Navarro, P., 2012
 Notas: Definición inspirada en la descripción dada a “Modelo fotorrealístico 3D” de Guidi,
G., Russo, M. y Beraldin, J.A. (2010, p. 180) “modelli digitali che integrano le informazioni
geometriche ottenute da uno strumento per acquisizione tridimensionale, con texture
ottenute da una fotocamera” Otra definición encontrada sería (Apollonio, F.I. y Remondino,
F., 2010, p. 114) “Le immagini vengono acquisite con fotocamere (...), devono essere
registrate ed allineate al modello geometrico atraverso processi interattivi, identificando
punti omologi tra loro” (Las imagenes vienen adquiridas con foto-cámaras, que deben ser
registradas y alineadas con respecto al modelo geométrico a través de procesos interactivos,
identificando puntos homólogos entre ellos).

Clásico / clasico / classical.
 Sinónimos: tradicional
 Definición: Adjetivo que se utiliza para designa sustantivos que se adaptan a lo marcado por
la tradición o las reglas establecidas por la costumbre y el uso. También se utiliza para
referirse a un sustantivo perteneciente o relativo al momento histórico de una ciencia, en el
que se establecen teorías o modelos que son la base de su desarrollo posterior.
 Comentarios: Algunos conceptos relacionados con este término son: Croquis (Buill, F.,
Nuñez, M.A., Rodríguez, J.J., 2007), Medida directa (Buill, F., Nuñez, M.A., Rodríguez, J.J.,
2007).
 Referencias:
Guidi, G. y Remondino, F. 2012
Herráez Boquera, J., Navarro Esteve, P y Denia Ríos, JL., 2010

10 Definida por Apollonio, F.I. y Remondino, F. (2010, p. 114) como “aspetto qualitativo. Possibilità del
modello 3D di rappresentare l’oggetto reale riproducendo, nella maniera più fedele possibile, anche il
comportamento della superficie rispetto alla riflessione della luce, includendo le caratteristiche di colore
e di finitura della superficie stessa”. (Aspecto cualitativo. Posibilidad del modelo 3D de representar el
objeto real reproduciendo, en la manera más fiel posible, también el comportamiento de la superficie con
respecto a la reflexión de la luz, incluyendo las características de color y de acabado de la superficie
misma) “Propietà definita come texture della superficie.” (propiedad definida como la textura de la
superficie)

256

<!-- p. 266 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

Lerma, J.L. et al, 2010
Riveiro Rodríguez, B. et al, 2011
 Notas: Definición de la autora deducida a partir de las definiciones encontradas en la RAE y
WordReference (última visita: 25/11/2013)

Virtual / Virtuale / Virtual.
 Sinónimos:
 Definición: Es un adjetivo usado para referirse en este campo a cualquier concepto simulado,
generado o asistido comúnmente por ordenador.11
 Comentarios:
 Referencias:
Bianchini, C., 2007
Buill, F., Núñez, M.A., Rodríguez, J.J, 2007
Guidi, G., Russo, M. y Beraldin, J.A., 2010
Herráez Boquera, J., Navarro Esteve, P y Denia Ríos, JL., 2010
Lerma, J.L. et al, 2010
Manferdini, A.M. y Remondino, F., 2010
Marambio, A. et al, 2009
Remondino, F. y El-Hakim, S., 2007
Rodríguez Navarro, P., 2012
Verdiani, G., 2003
 Notas: Definición de la autora inspirada a partir de algunas definiciones encontradas en
“http://telematica.cicese.mx/computo/super/cicese2000/realvirtual/Part2.html”

ii. Campo 2.- FOTOGRAMETRÍA
CONCEPTOS

Fotogrametría / Fotogrammetria / Photogrammetry
 Sinónimos:
 Definición: Es la ciencia que permite obtener medidas precisas a partir de fotografías
(imágenes) mediante la transformación de información bidimensional en medidas
tridimensionales.
 Comentarios:
 Referencias:
Balzani, M., Ferrari, F. y Viroli, F., 2012
Bianchini, C., 2007
Biosca Taronger, J.M., Navarro Tarín, S. y Lerma García, J.L., 2007
Buill, F., Nuñez, M.A., Rodríguez, J.J., 2007
Cannarozzo, Cucchiarini y Meschieri, 2012
Docci, M., Maestri, D. 1984
Fantini, F., 2012

11

257

<!-- p. 267 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

Guidi, G. y Remondino, F., 2012
Herráez Boquera, J., Navarro Esteve, P y Denia Ríos, JL., 2010
Koska, B. y Křemen, T., 2013
Lerma, J.L. et al, 2010
Lerma, J.L. et al, 2011
Manferdini, A.M. y Remondino, F., 2010
Remondino, F. y El-Hakim, S., 2007
Riveiro Rodríguez, B. et al, 2011
Wenzel, K. Et al, 2013
 Notas: Interpretación de la definición hecha por (Mikhail et al., 2001) encontrada en
Manferdini, A.M. y Remondino, F. (2010, p.166-167): “è la scienza che consente di ottenere
misure accurate da fotografie (immagini) mediante la trasformazione di informazioni
bidimensionali in misure tridimensionali”. Otra definición similar se encuentra en Guidi, G.,
Russo, M. y Beraldin, J.A. (2010, p. 17): “è definita come la scienza che permette di ottenere
una misura accurata delle caratteristiche geometriche di un oggetto, come forma e
posizione, attraverso l’impiego congiunto di fotografie che lo ritraggono da posizioni
differenti” (es definida como la ciencia que permite de obtener una medida precisa de las
características geométricas de un objeto, como forma y posición, a través de la utilización
conjunta de las fotografías que lo capturan desde diferentes posiciones). Lerma, J.L. et al
(2010, p. 500) la define como “can be described as the science and art of measuring and
interpreting imagery in order to reconstruct metrically objects either in 3D or in 2D” (puede
ser descrita como la ciencia y arte de medir e interpreter imagines en orden de reconstrucción
métrica de objetos en 3D o en 2D). Buill, F., Nuñez, M.A., Rodríguez, J.J. (2007, p. 23) dan
dos definiciones: “la métrica de lo escrito con luz” “la disciplina que lleva a cabo medidas
indirectas de objetos utilizando perspectivas fotográficas. El objetivo de la fotogrametría es
conseguir información tridimensional de objetos a partir de medidas efectuadas en
fotografías”

IBM (Image-Based Modelling) / IBM (Image-Based Modelling) / IBM (Image-Based
Modelling)
 Sinónimos: Fotogrametría Digital Automatizada, Método general de la fotogrametría, Image-
based 3D model, Structure-from-motion software (SFM), Fotomodellazione, Reality-based
3D modelling, Close range photogrammetry (CRP), Range images, Modelli Fotogrammetrici
3D, 3D imaging12.
 Definición: Este método por lo general se aplica a los objetos que tienen un tamaño
comprendido entre algunos decímetros hasta 200 m. Tomando la orientación en el espacio de
una imagen, cada imagen genera un haz de rayos que pueden ser utilizados para generar
nubes de puntos, modelos de textura (modo autónomo) o medidas de objetos en el espacio (si
hay más de una imagen, y se cruzan los haces de rayos que vienen de cada una de ellas).
 Comentarios: Algunos conceptos relacionados con este término son: Image-based technique
(Guidi, G. y Remondino, F. 2012), Image survey (Dore, C. y Murphy, M., 2012), Pair of
images (Wenzel, K. et al, 2013), Image-based 3D reconstruction (Remondino, F., et al, 2012)

12 Guidi, G., Russo, M. y Beraldin, J.A. (2010, p. 123): “l’insime delle tecnologie e dei metodi che
permettono di trasformare un oggetto fisico in un artefatto digitale catturandone la forma.” (El conjunto
de las tecnologías y de los métodos que permiten transformar un objeto físico en un artefacto digital
capturando la forma)

258

<!-- p. 268 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

(Corsini, M., et al, 2013), Close range stereo pairs (Lerma, J.L. et al, 2010),
Photogrammetric survey (Dore, C. y Murphy, M., 2012) (Balzani, M., Ferrari, F. y Viroli, F.,
2012).
 Referencias:
Alsadik, B. et al, 2013
Bertocci, S., Bini, M., 2012
Bianchini, C., 2007
Buill, F., Nuñez, M.A. y Rodríguez, J.J., 2007
Corsini, M., et al, 2013
Guidi, G. y Remondino, F., 2012
Guidi, G., Russo, M. y Angheleddu, D., 2013
Guidi, G., Russo, M. y Beraldin, J.A., 2010
Koska, B. y Křemen, T., 2013
Lerma, J.L. et al, 2010
Remondino, F. et al, 2012
Remondino, F. y El-Hakim, S., 2007
Rodríguez Navarro, P., 2012
Wenzel, K. et al, 2013
 Notas: Interpretación de la descripción de Lerma, J.L. et al, (2010, p. 500): “Close range
photogrammetry usually applies to objects ranging froma few decimetres up to 200 m in size.
If the orientation in space of one image is known, every image generates a bundle of rays
that can be used to either texture models (standalone mode) or measure objects in space (if
more than one image is available and intersect the bundle of rays coming from different
pictures).” Buill, F., Nuñez, M.A. y Rodríguez, J.J. (2007, p. 23) lo llaman “método general
de la fotogrametría” y lo definen como: “Para pasar de información bidimensional
proporcionada por las fotografías a la información tridimensional, a partir de la
reconstrucción de la forma de cada uno de los haces fotográficos y de su situación en el
espacio con respecto a un cierto sistema de referencia externo, y usando la visión
estereoscópica para la identificación de los rayos homólogos de cada haz, es capaz de
proporcionar las coordenadas tridimensionales de cada punto objeto medido”.

Image matching / Image matching / Image matching.
 Sinónimos: Automated procedures (“image matching”), Automatic image processing
methods, Photogrammetric image processing methods, Image processing.
 Definición: Proceso por el cual se realiza una correlación automática de las imágenes
generando una nube de puntos.
 Comentarios: Un concepto relacionado con este término es: Restituzione 3D13 (Manferdini,
A.M. y Remondino, F., 2010) (Merlo, A., 2007)(Bianchini, C., 2007).
 Referencias:
Guidi, G. y Remondino, F. 2012
Lerma, J.L., et al, 2010
Wenzel, K. et al, 2013

13 Manferdini, A.M. y Remondino, F. (2010): “mediante misure (manuali, semi automatiche o
automatiche) di punti omologhi tra le immagini” (mediante medidas (manuales, semi automáticas o
automáticas) de puntos homólogos entre las imágenes).

259

<!-- p. 269 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

 Notas: Manferdini, A.M. y Remondino, F., 2010: “correlazione automatica di immagini
(Remondino et al., 2008)” En Guidi, G., Russo, M. y Beraldin, J.A. (2010, p. 213) se
encuentra la misma definición.

Fotograma / Fotogrammi / Photographs
 Sinónimos:
 Definición: “Fotografías analógicas que en su formato métrico se denominan fotogramas”
 Comentarios: Algunos conceptos relacionados con este término son: Imágenes con carácter
métrico (Lerma, J.L. et al, 2011), Fotografía14 (Buill, F., Nuñez, M.A., Rodríguez, J.J.,
2007).
 Referencias:
Buill, F., Nuñez, M.A., Rodríguez, J.J., 2007
Cannarozzo, Cucchiarini y Meschieri, 2012
Docci, M., Maestri, D. 1984
Fantini, F., Rodríguez-Navarro, P. y Di Tondo, S., 2012
Lerma, J.L. et al, 2011
Rodríguez Navarro, P., 2012
Verdiani, G., 2003
 Notas: Lerma, J.L. et al, 2011

Sensor pasivo / Sensore passivo / Passive sensor.
 Sinónimos: Passive technique, Tecniche di misura passiva.
 Definición: Un tipo de sensor “que se limita a observar la escena a través de un sistema
óptico u óptico-electrónico, con el objetivo de obtener de esta visión, la información de
carácter geométrico (Guidi, 2010, p.10)”.
 Comentarios: Un concepto relacionado con este término es: Sensores de imagen (Lerma, J.L.
et al, 2011)
 Referencias:
Guidi, G. y Remondino, F. 2012
Guidi, G., Russo, M. y Beraldin, J.A., 2010
Manferdini, A.M. y Remondino, F., 2010
Rodríguez Navarro, P., 2012
 Notas: Rodríguez Navarro, P. (2012, p. 101)

Ortofoto / Ortofoto / Orthophoto
 Sinónimos: Ortofotografía
 Definición: “Imágenes en la que todo el plano está representado sin deformaciones y con
validez métrica”

14 Buill, F., Nuñez, M.A., Rodríguez, J.J. (2007, p. 31) “de un objeto es una proyección o perspectiva
cónica del mismo, desde el centro óptico o centro de perspectiva de la cámara, sobre el plano de la
fotografía” (p. 32) “registro permanente en forma de imagen causado por la acción de la luz sobre una
superficie sensible, que en el caso analógico suele estar formado por sales de plata”

260

<!-- p. 270 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

 Comentarios: Algunos conceptos relacionados con este término son: Ortoimágenes (Mañana-
Borrazás, P., Rodríguez Paz, A. y Blanco-Rotea, R., 2008), Orthoimage15 (Koska, B. y
Křemen, T., 2013), Orthographic images (Dore, C. y Murphy, M., 2012), Ortho photo
creation (Dore, C. y Murphy, M., 2012), Fotoplano (Buill, F., Núñez, M.A., Rodríguez, J.J.,
2007), Ortoproyección16 (Buill, F., Núñez, M.A., Rodríguez, J.J., 2007) (Marambio, A. et al,
\2009.
 Referencias:
Baldissini, S., Gaiani, M. y Remondino, F., 2010
Buill, F., Núñez, M.A., Rodríguez, J.J., 2007
Cueli López, J., 2010
Koska, B. y Křemen, T., 2013
Wenzel, K. Et al, 2013
 Notas: Mañana-Borrazás, P., Rodríguez Paz, A. y Blanco-Rotea, R. (2008, p. 24). Otra
definición se encuentra en Baldissini, S., Gaiani, M. y Remondino, F. (2010, 228):
“immagini in cui viene rimosso l’effetto prospettico dovuto alla procedura di acquisizione
dell’immagine. L’ortofoto viene generata utilizzando il modello digitale con un approccio
diretto o indiretto e poi mappata direttamente sul modello attraverso un metodo proiettivo
ortogonale.” (imágenes en las cuales viene eliminado el efecto perspectivo debido al
procedimiento de adquisición de la imagen. La ortofoto viene generada utilizando el modelo
digital con un enfoque directo o indirecto y después mapeada directamente sobre el modelo a
través de un método de proyección ortogonal). Buill, F., Núñez, M.A., Rodríguez, J.J. (2007,
p. 121) la definen como: “fotografía ortoproyectada” (leer definición de ortoproyección)

Orientación / Orientamento / Orientation.
 Sinónimos: Camera resectioning, Resezione.
 Definición Consiste en encontrar los parámetros de orientación externa (3 posiciones y 3
rotaciones) de cada imagen que se está utilizando
 Comentarios:
 Referencias:
Bianchini, C., 2007
Buill, F., Núñez, M.A., Rodríguez, J.J., 2007
Fantini, F., Rodríguez-Navarro, P. y Di Tondo, S., 2012
Guidi, G. y Remondino, F. 2012
Guidi, G., Russo, M. y Beraldin, J.A., 2010
Koska, B. y Křemen, T., 2013
Lerma, J.L., et al., 2011
Manferdini, A.M. y Remondino, F., 2010

15 Se define según Koska, B. y Křemen, T. (2013, p. 133): “An orthoimage is an orthogonal view on a
point cloud, which has a colour based on the intensity of the returned signal or from an image. An ortho
image has a resolution limited by resolution of the point cloud.” (Una ortoimagen es una visualización
ortogonal de una nube de puntos, la cual tiene un color basado en la intensidad del retorno de la señal
presa de una imagen. Una orto imagen tiene una resolución limitada por la resolución de la nube de
puntos).
16 Buill, F., Núñez, M.A., Rodríguez, J.J. (2007, p. 121) “proceso de transformación de una perspectiva,
generalmente fotográfica, en una proyección ortogonal”

261

<!-- p. 271 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

Rodríguez Navarro, P., 2012
Verdiani, G., 2003
Wenzel, K. et al, 2013
 Notas: Interpretación de la descripción realizada por Manferdini, A.M. y Remondino, F.
(2010, p. 173): “consiste nel trovare i parametri di orientamento esterno (3 posizioni e 3
rotazioni) di ciascuna immagine che si sta utilizzando.” Buill, F., Núñez, M.A., Rodríguez,
J.J. (2007, p. 105) la definen como: “proceso que permite establecer la posición de las
cámaras fotogramétricas tal como estaban en el momento de efectuar cada fotografía,
respecto a un sistema de referencia terrestre”.

Parámetros de orientación / Parametri Addicionali (AP) / Additional Parameters (Aps)
 Sinónimos:
 Definición: “Los parámetros de orientación de la cámara son el conjunto de parámetros
internos y externos de la cámara. Los parámetros de orientación internos consisten en la
constante de la cámara (o longitud focal, f), posición del punto principal (x0, y0) y algunos
parámetros adicionales usados para modelar eventuales errores sistemáticos debidos, por
ejemplo, a la distorsión de la lente. Los parámetros de orientación externos consisten en las
3 coordinadas espaciales (posición en el espacio de la cámara, generalmente indicados con
X0, Y0, Z0) y en las 3 rotaciones del centro prospectico de la cámara en el espacio”
 Comentarios: Algunos conceptos relacionados con este término son: Exterior orientation
parameters (Lerma, J.L. et al, 2010), Interior orientation parameters17 (Lerma, J.L. et al,
2010), Intrinsic camera parameters (Wenzel, K. et al, 2013), Principal point offset (Guidi, G.
y Remondino, F., 2012).
 Referencias:
Biosca Taronger, J.M., Navarro Tarín, S. y Lerma García, J.L., 2007
Buill, F., Nuñez, M.A. y Rodríguez, J.J., 2007
Guidi, G. y Remondino, F., 2012
Lerma, J.L. et al, 2010
Manferdini, A.M. y Remondino, F., 2010
 Notas: Concepto inspirado en Manferdini A.M. y Remondino, F., (2010, p. 169): “parametri
di orientamento interno ed esterno delle camere. I parametri di orientamento interno
consistono nella costante della camera (lunghezza focale f), posizione del punto principale
(x0, y0) e alcuni parametri addizionali (AP) usati per modellare eventuali errori sistematici
dovuti, per esempio, alla distorsione della lente. I parametri di orientamiento esterno
consistono nelle 3 coordinate spaziali (posizione nello spazio della camera, generalmente
indicate con X0, Y0, Z0) e nelle 3 rotazioni del centro prospettico della camera nello spazio”.

Puntos homólogos / Punti omologi / Homologous point.
 Sinónimos:
 Definición: Son puntos semejantes medidos en las imágenes, de los cuales sale de cada uno
de ellos una ecuación de colinealidad, que permite resueltas las ecuaciones la calibración de
la cámara y la orientación de las imágenes.
 Comentarios:
 Referencias:

17 Los parámetros de orientación interior son según Lerma, J.L. et al (2010, p. 500) “focal length,
principal point coordinates and distorsion parameters” (distancia focal, coordenadas del punto principal
y los parámetros de distorsión).

262

<!-- p. 272 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

Apollonio, F.I. y Remondino, F., 2010
Biosca Taronger, J.M., Navarro Tarín, S. y Lerma García, J.L., 2007
Buill, F., Nuñez, M.A. y Rodríguez, J.J., 2007
Fantini, F., Rodríguez-Navarro, P. y Di Tondo, S., 2012
Herráez Boquera, J., Navarro Esteve, P y Denia Ríos, JL., 2010
Lerma, J.L. et al, 2010
Manferdini A.M. y Remondino, F., 2010
Rodríguez Navarro, P., 2012 Cueli López, J., 2010
 Notas: Concepto inspirado en Manferdini A.M. y Remondino, F., (2010, p. 170) a partir de
la descripción del algoritmo de “bundle adjustment”. Otra descripción la encontramos en
Buill, F., Nuñez, M.A. y Rodríguez, J.J. (2007, p. 161) “Puntos imagen de un par
fotogramétrico que se corresponden con un mismo punto terreno”

Rectificación / Raddrizzamento / rectification.
 Sinónimos:
 Definición: Normalmente las fotografías se toman con el eje de la cámara inclinado
levemente respecto a la vertical u horizontal, puesto que es casi imposible lograr su
verticalidad u horizontalidad perfecta. No existe ningún mecanismo que posibilite la
obtención de fotografías perfectamente verticales u horizontales. La rectificación consiste,
por lo tanto, en la corrección de las fotografías con respecto a un plano horizontal o vertical
de referencia. En el fotograma rectificado sólo podemos reproducir en verdadera forma y
dimensión los elementos contenidos en un plano del modelo.
 Comentarios:
 Referencias:
Apollonio, F.I., et al, 2010
Buill, F., Nuñez, M.A., Rodríguez, J.J., 2007
Docci, M., Maestri, D. 1984
Lerma, J.L., et al., 2011
Mañana-Borrazás, P., Rodríguez Paz, A. y Blanco-Rotea, R., 2008
 Notas: Inspirada en la descripción de fotografías rectificadas de los apuntes de “Topografía,
cartografía y geodesia” de Ingeniería cartográfica, geodésica y fotogrametría de la
Universidad Politécnica de Madrid. Tema 11. Fotogrametría y Teledetección. P. 7. Otra
definición la podemos encontrar en - Buill, F., Núñez, M.A. y Rodríguez, J.J. (2007, p. 91):
“Proceso que consigue transformar o enderezar una perspectiva fotográfica obteniendo una
representación semejante a la que se conseguiría en la fotografía estrictamente
perpendicular al plano”.

Cámara / camera / camera.
 Sinónimos:
 Definición: Aparato que sirve para hacer fotografías, y que consta de un medio óptico, el
objetivo, y de un medio mecánico, el obturador.
 Comentarios:
 Referencias:
Bianchini, C., 2007
Biosca Taronger, J.M., Navarro Tarín, S. y Lerma García, J.L., 2007
Buill, F., Nuñez, M.A. y Rodríguez, J.J., 2007

263

<!-- p. 273 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

Cueli López, J., 2010
Guidi, G. y Remondino, F. 2012
Lerma, J.L. et al, 2011
Marambio, A., Pucci, B., Nuñez, M.A. y Buill, F., 2009
Wenzel, K. et al, 2013
 Notas: Definición de la RAE (última visita: 23/11/2013).

Distancia focal / Distanza focale / Focal length.
 Sinónimos:
Definición: Distancia en mm desde el centro óptico de la lente hasta el plano focal.
 Comentarios:
 Referencias:
Buill, F., Nuñez, M.A. y Rodríguez, J.J., 2007
Cueli López, J., 2010
Guidi, G. y Remondino, F., 2012
Wenzel, K. et al, 2013
 Notas: Inspirada en la definición de Guidi, G. y Remondino, F. (2012, p. 76) “Distance in
mm from the optical centre of the lens to the focal plane”.

Colinealidad / collinealità / Collinearity.
 Sinónimos:
 Definición: El principio de colinealidad establece que dado el centro de proyección de la
cámara fotográfica, un punto P’ sobre la imagen y su correspondiente punto P en el espacio
deben yacer sobre una línea recta.
 Comentarios:
 Referencias:
Biosca Taronger, J.M., Navarro Tarín, S. y Lerma García, J.L., 2007
Buill, F., Nuñez, M.A. y Rodríguez, J.J., 2007
Guidi, G. y Remondino, F., 2012)
Lerma, J.L. et al, 2010
Guidi, G., Russo, M. y Beraldin, J.A., 2010
Manferdini, A.M. y Remondino, F., 2010
 Notas: Definición del principio de colinealidad de Manferdini, A.M. y Remondino, F. (2010,
p. 168): “che stabilisce come il centro di proiezione della camera fotografica, un punto P’
sull’immagine e il suo corrispondente punto P nello spazio devono giacere su una linea
retta”.

Analógica / analogica / Analogical.
 Sinónimos:
 Definición: “Dicho de un aparato o de un instrumento de medida, que la representa
mediante variables continuas, análogas a las magnitudes correspondientes”
 Comentarios:
 Referencias:
Cannarozzo, Cucchiarini y Meschieri, 2012
Lerma, J.L. et al, 2011

264

<!-- p. 274 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

 Notas: Definición de la RAE (última visita: 23/11/2013)

Analítica / analitica / Analytical
 Sinónimos:
 Definición: Adjetivo usado para hablar de elementos a los que se llega mediante la
descomposición o el análisis.
 Comentarios:
 Referencias:
Cannarozzo, Cucchiarini y Meschieri, 2012
Lerma, J.L. et al, 2011
 Notas: Definición de la autora a partir de la descripción de la RAE (última visita:
23/11/2013).

Estereoscópico / Stereoscopico / Stereoscopic.
 Sinónimos:
 Definición: Adejetivo que referencia a cualquier técnica capaz de recoger información visual
tridimensional y/o crear la ilusión de profundidad mediante una imagen estereográfica,
un estereograma, o una imagen tridimensional.
 Comentarios: Algunos conceptos relacionados con este término son: Fotografías
estereoscópicas (Lerma, J.L., et al, 2011), Estereofotogrametría18 (Buill, F., Nuñez, M.A. y
Rodríguez, J.J., 2007), Restitución estereofotogramétrica (Buill, F., Nuñez, M.A., Rodríguez,
J.J., 2007), Coppia Stereofotogrammetrica (Bianchini, C., 2007).
 Referencias:
Guidi, G. y Remondino, F., 2012
Lerma, J. L. et al, 2011
Rodríguez Navarro, P., 2012
 Notas: Definición de la autora a partir de la descripción de “Estereoscopía” de Wikipedia
(última visita: 23/11/2013).

iii. Campo 3.- ESCÁNER LÁSER
CONCEPTOS

Escáner Láser 3D / 3D laser scanner / 3D laser scanner.
 Sinónimos: Escáner Láser 3D, Láser escáner, 3D laser scanner, Laser Scanning, Laser scan,
Scanner laser, Laserscan, Scanner 3D, Laser-based equipment, Barredores (escáneres) láser,
Sensores de barrido láser, Sensor láser, equipo de medición de láser.
 Definición: “Es un dispositivo, por lo general montado sobre un trípode o plataforma
estable que explora, por medio de un haz de láser (radiación electromagnética
monocromática, coherente y colimada), los elementos del espacio circundante en forma tal,

18 (Buill, F., Nuñez, M.A. y Rodríguez, J.J. (2007, p. 24): “permite la obtención de un modelo idéntico al
original a partir de un par fotográfico. El poder trabajar con la visión estereoscópica posibilita que se
pueda observar dicho modelo y medir de una forma exacta las líneas, superficies y volúmenes del
elemento a levantar”

265

<!-- p. 275 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

que a cada punto del objeto explorado, se le asigna las coordenadas reales que está
ocupando en el sistema de representación espacial”.
 Comentarios:
 Referencias:
Apollonio, F.I. y Remondino, F., 2010
Amoruso, G., Apollonio, F.I. y Remondino, F. 2010
Balzani, M., Ferrari, F. y Viroli, F., 2012
Bianchini, C., 2007
Biosca Taronger, J.M., Navarro Tarín, S. y Lerma García, J.L., 2007
Buill, F., Núñez, M.A., Rodríguez, J.J, 2007
Buill Pozuelo, F., Núñez Andrés, M.A. y Marambio Castillo, A.
Corsini, M., et al, 2013
Dore, C. y Murphy, M., 2012
Fantini, F., 2012
Fantini, F., Rodríguez-Navarro, P. y Di Tondo, S., 2012
Guidi, G. y Remondino, F. 2012
Herráez Boquera, J., Navarro Esteve, P y Denia Ríos, JL., 2010
Koska, B. y Křemen, T., 2013
Lerma, J.L., et al, 2010
Lerma, J.L., et al, 2011
Mañana-Borrazás, P., Rodríguez Paz, A. y Blanco-Rotea, R., 2008
Marambio, A., Pucci, B., Nuñez, M.A. y Buill, F., 2009
Merlo, A., 2007
Riveiro Rodríguez, B. et al, 2011
 Notas: Riveiro Rodríguez, B. et al. (2011, p. 4).

LiDAR / LiDAR / LiDAR.
 Sinónimos:
 Definición: Acrónimo de Light Detection And Ranging. Los sistemas basados en la medida
de distancias son in general llamados como LIDAR, sin embargo, en el área de topografía el
acrónimo es usado frecuentemente para indicar la categoría específica de escáner láser
aerotransportado.
 Comentarios:
 Referencias:
Apollonio, F.I. y Remondino, F., 2010
Guidi, G. y Remondino, F. 2012
Guidi, G., Russo, M. y Beraldin, J.A., 2010
Lerma, J.L., et al, 2010
Mañana-Borrazás, P., Rodríguez Paz, A. y Blanco-Rotea, R., 2008
 Notas: Definición inspirada en Guidi, G. y Remondino, F. (2012, p. 79): “(Light Detection
And Ranging): Systems based on the measurement of distance are in general indicated as
LiDAR (Light Detection And Ranging), even if in the topographic area this acronym is often
used for indicating the specific category of airborne laser scanner.” Otra definición similar
se encuentra en Mañana-Borrazás, P., Rodríguez Paz, A. y Blanco-Rotea, R. (2008, p. 16)
“Láser escáner que opera sobre una plataforma aerotransportada”. Otra definición

266

<!-- p. 276 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

diferente se encuentra en Apollonio, F.I. y Remondino, F. (2010, p. 98) (Light Detection
And Ranging): “Sensori a tempo di volo che possono essere impiegati su piattaforme in
movimiento (aereo, elicottero, treno, auto) o in modalità statica (rilievo classico terrestre)”
(Sensores a tiempo de vuelo que pueden ser empleados sobre plataformas en movimiento
(avión, helicóptero, auto) o en modalidad estática (levantamiento clásico terrestre). Guidi,
G., Russo, M. y Beraldin, J.A. (2010, p. 97) lo describen como: “I sistemi che si basano sul
principio della misura di distanza, sono in genere indicate como Laser Radar o LIDAR”
(Los sistemas que se basan sobre el principio de medida de distancia son generalmente
nominados como Láser Radar o LIDAR).

RBM (Range-Based Modelling) / RBM / RBM.
 Sinónimos: Escáner Láser 3D, Láser escáner, 3D laser scanner, Laser Scanning, Laser scan,
Scanner laser, Laserscan, Scanner 3D, Laser-based equipment, Barredores (escáneres) láser,
Sensores de barrido láser, Sensor láser, Fotogrametría de escáner láser.
 Definición: Es un método que se basa en “un instrumento que adquiere mediante rayos
láser, en forma digital, la tendencia de las superficies externas de un objeto, sobre las cuales
no viene hecha ninguna presunción a priori.”
 Comentarios: Algunos conceptos relacionados con este término son: Elementos barridos
(Buill Pozuelo, F., Núñez Andrés, M.A. y Marambio Castillo, A.,) Laser Range Camera
(LRC) (Guidi, G., Russo, M. y Beraldin, J.A., 2010), Barridos escáner láser (Buill, F.,
Nuñez, M.A., Rodríguez, J.J., 2007), Scansione 3D (Bianchini, C., 2007), Escaneado
(Fantini, F., 2012) (Buill, F., Núñez, M.A., Rodríguez, J.J, 2007) (Lerma, J.L., et al, 2011),
Scansione 3D (Balzani, M., Ferrari, F. y Viroli, F., 2012). Registro fotogramétrico digital
(Herráez Boquera, J., Navarro Esteve, P y Denia Ríos, JL., 2010)
 Referencias:
Mañana-Borrazás, P., Rodríguez Paz, A. y Blanco-Rotea, R., 2008
Apollonio, F.I. y Remondino, F., 2010
Amoruso, G., Apollonio, F.I. y Remondino, F. 2010
Balzani, M., Ferrari, F. y Viroli, F., 2012
Bianchini, C., 2007
Biosca Taronger, J.M., Navarro Tarín, S. y Lerma García, J.L., 2007
Buill, F., Núñez, M.A., Rodríguez, J.J, 2007
Buill Pozuelo, F., Núñez Andrés, M.A. y Marambio Castillo, A.
Corsini, M., et al, 2013
Dore, C. y Murphy, M., 2012
Fantini, F., 2012
Fantini, F., Rodríguez-Navarro, P. y Di Tondo, S., 2012
Guidi, G. y Remondino, F. 2012
Herráez Boquera, J., Navarro Esteve, P y Denia Ríos, JL., 2010
Koska, B. y Křemen, T., 2013
Lerma, J.L., et al, 2011
Merlo, A., 2007
Riveiro Rodríguez, B. et al, 2011
 Notas: Término inspirado en la descripción de Guidi, G., Russo, M. y Beraldin, J.A. (2010,
p. 78): “l’acquisizione in forma digitale dell’andamento nello spazio delle superfici esterne

267

<!-- p. 277 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

di un oggetto, sulle quali non viene fatta nessuna assunzione a priori” Buill, F., Núñez,
M.A., Rodríguez, J.J. (2007, p. 129) lo definen como: “está compuesto por un sistema que
genera un haz láser (luz monocromática, coherente, intensa y sin dispersión) y un sistema de
barrido, horizontal y vertical, de modo que efectuando una serie de perfiles se consigue
cubrir toda la superficie a levantar, en forma de rejilla de paso impuesto por el operador.
No necesita, por tanto, contacto directo con el modelo a levantar”.

Sensor activo / Sensori attivi / Active sensor.
 Sinónimos: Sensores 3D Activos, Active 3D sensor, Sensori 3D attivi, Active range sensing,
Range image19, Range camera20, 3D active methods, Range device, Sensori di distanza.
 Definición: Sensores que “emiten una luz desde el propio instrumento; esta luz tiene una
estructura definida y conocida por el sensor que debe captarla (Guidi, 2010, p. 12)”
 Comentarios: Un concepto relacionado con este término es: Rilievo con sensori attivi21
(Manferdini, A.M. y Remondino, F., 2010).
 Referencias:
Amoruso, G., Apollonio, F.I. y Remondino, F. 2010
Apollonio, F.I. y Remondino, F., 2010
Guidi, G. y Remondino, F. 2012
Guidi, G., Russo, M. y Beraldin, J.A., 2010
Lerma, J.L. et al, 2011
Manferdini, A.M. y Remondino, F., 2010
Rodríguez Navarro, P., 2012
 Notas: Término definido por Rodríguez Navarro, P. (2012, p. 103).

Nube de puntos / Nuvola di punti / point clouds.
 Sinónimos: Nube de puntos 3D, 3D point clouds.
 Definición: Conjunto de coordinadas 3D que reflejan la superficie externa de un objeto y
vienen de la captura con escáner láser 3D o desde la correspondencia entre las imágenes de
éste utilizando siempre ecuaciones de colinealidad y los parámetros internos y externos
obtenidos precedentemente.

19 Guidi, G. y Remondino, F. (2012, p. 74): “The output attainable from such a device can be seen as an
image having in each pixel the spatial coordinates (x, y, z) expressed in millimetres, optionally enriched
with colour information (R, G, B) or by the laser reflectance (Y). This set of 3D data, called “range
image”, is generally a 2.5D entity (i.e. at each couple of x,y values, only one z is defined)”
20 Apollonio, F.I. y Remondino, F. (2010, p. 95) “Gli strumenti attivi, normalmente impiegati per rilevare
oggetti e produrre modelli 3D, sono generalmente detti range camera o, per quelli che utilizzano luce
laser, laser scanner 3D” (Los instrumentos activos, normalmente empleados para levantar objetos y
producir modelos 3D, son generalmente llamados “range camera” o, para aquellos que utilizan luz láser,
“laser scanner 3D”). La misma definición se encuentra en Guidi, G., Russo, M. y Beraldin, J.A. (2010, p.
\78)
21 Manferdini, A.M. y Remondino, F. (2010, p. 164): “strumenti attivi rilevano distanze e forniscono
direttamente misure tridimensionali dell’oggetto rilevato” (Instrumentos activos levantan distancias y
proporcionan directamente medidas tridimensionales del objeto de interés) (p. 167): “I sensori attivi (...)
rilevano la luce emessa dallo strumento stesso e riflessa dall’elemento oggetto di analisi” (Los sensores
activos detectan la luz emitida por el instrumento mismo y reflejada desde el elemento objeto de análisis)

268

<!-- p. 278 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

 Comentarios: Algunos conceptos relacionados con este término son: Nube de puntos de
color (Marambio, A., et al, 2009), Nube di punti non strutturata22 (Guidi, G., Russo, M. y
Beraldin, J.A., 2010), Nube di punti strutturata23 (Guidi, G., Russo, M. y Beraldin, J.A.,
2010), Nube ligera (Cueli Lopez, J., 2010). Merlo llama al modelo de nube de puntos:
Modello discreto (Merlo, A., 2007).
 Referencias:
Alsadik, B., et al, 2013
Apollonio, F.I. y Remondino, F., 2010Lerma, J.L., et al, 2010
Bianchini, C., 2007
Biosca Taronger, J.M., Navarro Tarín, S. y Lerma García, J.L., 2007
Buill, F., Nuñez, M.A., Rodríguez, J.J, 2007
Buill Pozuelo, F., Núñez Andrés, M.A. y Marambio Castillo, A.
Corsini, M., et al, 2013
Cueli López, J., 2010
Dore, C. y Murphy, M., 2012
Guidi, G. y Remondino, F. 2012
Guidi, G., Russo, M. y Beraldin, J.A., 2010
Herráez Boquera, J., Navarro Esteve, P y Denia Ríos, JL., 2010
Koska, B. y Křemen, T., 2013
Lerma, J.L., et al, 2011
Mañana-Borrazás, P., Rodríguez Paz, A. y Blanco-Rotea, R., 2008
Manferdini, A.M. y Remondino, F., 2010
Marambio, A., et al, 2009
Merlo, A., 2007
Riveiro Rodríguez, B. et al, 2011
Rodríguez Navarro, P., 2012
Verdiani, G., 2003.
Wenzel, K., et al, 2013
 Notas: Definición de la autora incluyendo una parte de la interpretación de la descripción
hecha por Guidi, G., Russo, M. y Beraldin, J.A., (2010, p. 70) “coordinate 3D che vengono
dalla correspondenza tra le immagini utilizzando sempre le equazioni di collinearità e i
parametri interni ed esterni ottenuti precedentemente”. Otra definición se encuentra en
Apollonio, F.I. y Remondino, F. (2010, p. 100): “per sistemi a tempo di volo, un insieme di
punti in 3D.” (por sistemas a tiempo de vuelo, un conjunto de puntos en 3D).

22 Definida por Guidi, G., Russo, M. y Beraldin, J.A. (2010, p. 207) como “(unstructured point cloud):
Una nube non strutturata è costituita da punti nello spazio che non risultano organizzati”. (Nube de
puntos no estructurada: Una nube no estructurada está constituida por puntos en el espacio que no
resultan organizados)
23 Definida por Guidi, G., Russo, M. y Beraldin, J.A. (2010, p. 207) como “(structured point cloud): nube
di punti strutturata si compone di una serie di coordinate 3D allocate logicamente su una griglia
bidimiensionale e può essere a tutti gli effetti vista come una immagine 3D, dove a posto del colore
troviamo una tripletta di coordinate spaziali.” (Nube de puntos estructurada: una nube de puntos
estructurada se compone de una serie de coordenadas 3D situadas lógicamente sobre una malla
bidimensional y puede ser en todos los efectos vista como una imagen 3D, donde en lugar del color se
encuentra un triplete de coordenadas espaciales)

269

<!-- p. 279 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

Diferencia de fase / Variazione di fase / Phase-shift distance.
 Sinónimos: CW, Scanner phase-based
 Definición: Se llama escáner de diferencia de fase cuando la distancia se calcula con una luz
láser cuya intensidad es modulada sinusoidalmente a una frecuencia conocida, generando
una onda continua (CW) de energía de la luz dirigida hacia el objetivo. La retrodispersión
sobre la superficie de destino devuelve una onda de luz con retraso respecto a la sinusoidal
transmitida por él, y por lo tanto caracterizado por una diferencia de fase con ella.
 Comentarios:
 Referencias:
Biosca Taronger, J.M., Navarro Tarín, S. y Lerma García, J.L., 2007.
Buill, F., Núñez, M.A., Rodríguez, J.J, 2007
Buill Pozuelo, F., Núñez Andrés, M.A. y Marambio Castillo, A.
Fantini, F., 2010
Guidi, G. y Remondino, F. 2012
Guidi, G., Russo, M. y Angheleddu, D., 2013
Koska, B. y Křemen, T., 2013
Lerma, J.L., et al, 2010
Lerma, J.L., et al, 2011
Riveiro Rodríguez, B. et al, 2011
 Notas: Interpretación de la definición realizada por Guidi, G. y Remondino, F. (2012, p. 80)
“(phase shift): In this case distance is estimated with a laser light whose intensity is
sinusoidally modulated at a known frequency, generating a Continuous Wave (CW) of light
energy directed toward the target. The backscattering on the target surface returns a
sinusoidal light wave delayed respect to the transmitted one, and therefore characterized by
a phase difference with it.” Buill, F., Núñez, M.A., Rodríguez, J.J, (2007, p. 130) lo
describen como: “Mediante la diferencia de fase entre la onda emitida por el sensor y la
recibida después de que ésta haya sido reflejada por le objeto a medir. A ésta medida se le
añada el número completo de longitudes de onda existentes entre el instrumento y la
superficie”.

Tiempo de vuelo / Tempo di volo / Time Of Flight.
 Sinónimos: Medida de distancia, Medición del tiempo de vuelo (TOF), TOF, Medición de
distancia, Medición basados en el tiempo.
 Definición: “Consiste en medir la distancia a partir del tiempo que tarda un fotodiodo en
emitir y detectar una luz láser, de forma similar al proceso que utilizan los distanciómetros
electrónicos”.
 Comentarios:
 Referencias:
Apollonio, F.I. y Remondino, F., 2010
Bianchini, C., 2007
Buill, F., Núñez, M.A., Rodríguez, J.J., 2007
Corsini, M., et al, 2013
Guidi, G. y Remondino, F. 2012
Guidi, G., Russo, M. y Beraldin, J.A., 2010

270

<!-- p. 280 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

Lerma, J.L., et al, 2010
Lerma, J.L., et al, 2011
Riveiro Rodríguez, B. et al, 2011
Rodríguez Navarro, P., 2012
 Notas: Buill, F., Núñez, M.A., Rodríguez, J.J. (2007, p. 130). Otra definición realizada por
Guidi, G., Russo, M. y Beraldin, J.A. (2010, p. 97) sería: “il tempo che l’impulso luminoso
impiega per andare e tornare dal bersaglio” (el tiempo que el impulso luminoso emplea en
ir y venir del blanco).

Triangulación / triangolazioni / Triangulation.
 Sinónimos: Triangulation devices, Triangulación óptica.
 Definición: Tipología de instrumentos basada en el individual punto láser con un sensor
lineal o bidimensional que mide los ángulos generados por el rayo. Utiliza los sistemas de
áreas de luz láser (hoja de luz) o escáner de diapositivas con sensores bidimensionales que
registran los ángulos de haz de luz.
 Comentarios: Un concepto relacionado con este término es: Tecnología láser stripe
(Rodríguez Navarro, P., 2012)
 Referencias:
Apollonio, F.I. y Remondino, F., 2010
Buill, F., Núñez, M.A., Rodríguez, J.J, 2007
Guidi, G. y Remondino, F. 2012
Guidi, G., Russo, M. y Beraldin, J.A., 2010
Lerma, J.L., et al, 2010
Lerma, J.L., et al, 2011
Riveiro Rodríguez, B. et al, 2011
Rodríguez Navarro, P., 2012
 Notas: Interpretación de la definición de Guidi, G., Russo, M. y Beraldin, J.A. (2010, p.
103): “tipologia di strumenti basata sul singolo spot laser con un sensore lineare o bi-
dimensionale che misura gli angoli generati dal raggio” “basato sulle aree di luce laser
(sheet light) o scanner a slitta con sensori bidimensionali che registrano gli angoli del fascio
di luce” Buill, F., Núñez, M.A., Rodríguez, J.J. (2007, p. 130) lo definen como: “se basa en
el cálculo de las coordenadas espaciales a partir de la intersección directa, similar al caso
estereofotogramétrico, con la diferencia de que en un extremo del sistema se sitúa el diodo
emisor y en otro extremo se sitúa el diodo receptor por lo que necesita solamente una única
cámara”

Alineación / Allineamento / Alignment.
 Sinónimos: Registro, Registration, Registrazione, empalme (Herráez Boquera, J., Navarro
Esteve, P y Denia Ríos, JL., 2010)
 Definición: El objetivo de la fase de registro o alineación consiste en buscar la justa relación
espacial entre una serie de nube de puntos relativas a un objeto captado desde varios puntos
de vista con el fin de representarlo sobre la base de una vista tomada como referencia.

271

<!-- p. 281 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

Comentarios: Algunos conceptos relacionados con este término son: Point cloud
alignament (Guidi, G. y Remondino, F. 2012), Scansioni allineate24 (Apollonio, F.I. y
Remondino, F., 2010), Point constraint (Herráez Boquera, J., Navarro Esteve, P y Denia
Ríos, JL., 2010)
 Referencias:
Apollonio, F.I. y Remondino, F., 2010
Arbacea, L., et al, 2013
Bianchini, C., 2007
Biosca Taronger, J.M., Navarro Tarín, S. y Lerma García, J.L., 2007
Corsini, M., et al, 2013
Dore, C. y Murphy, M., 2012
Guidi, G., Russo, M. y Beraldin, J.A., 2010
Lerma, J.L., et al, 2010
Marambio, A., et al, 2009
Rodríguez Navarro, P., 2012
 Notas: Interpretación de la descripción de Apollonio, F.I. y Remondino, F. (2010, p. 100)
“L’obiettivo della fase di registrazione consiste, quindi, nel cercare la giusta relazione
spaziale fra una serie di nuvole di punti relative ad un oggetto ripreso da vari punti di vista
al fine di rappresentarlo sulla base di una vista presa come riferimento.” (pp. 100
“allineamento preliminare delle scansioni” (Alineación preliminar de los escaneados).
Guidi, G., Russo, M. y Beraldin, J.A. (2010, p. 211) la definen como: “una delle range map
viene utilizzata come riferimento iniziale. Se ne sceglie una adiacente e si avvia una
procedura semiatomatica che consente di trovare il posizionamento ottimale della seconda
ripresa rispetto alla prima. Una volta che le prime due sono allineate le si considerano come
un blocco unico, e si passa all’allineamento di una successiva ripresa adiacente, fino ad
arrivare all’allineamento dei tutti i pezzi” (Una de las “range map” (capturas) se utiliza
como referencia inicial. Se elige una adyacente y se inicia un proceso semiautomático que
consiste en encontrar la posición óptima de la segunda captura respecto a la primera. Una
vez que las primeras dos están alineadas, se consideran como un bloque único, y se pasa a la
alineación de la sucesiva captura adyacente, hasta llegar a la alineación de todas las nubes de
puntos o mesh).

iv. Campo 4.- TOPOGRAFÍA
CONCEPTOS

Topografía / Topografía / Topography
 Sinónimos:
 Definición: “Ciencia que estudia la representación gráfica en un plano, a una escala
determinada, de una porción limitada de la superficie terrestre, con todos sus detalles
naturales o artificiales, y el conjunto de métodos, procedimientos e instrumentos que
permiten realizar mediciones para materializar dicha representación.”
 Comentarios:
 Referencias:

24 Apollonio, F.I. y Remondino, F. (2010, p. 104) “messe nello stesso sistema di riferimento” (metidos en
el mismo sistema de referencia)

272

<!-- p. 282 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

Balzani, M., Ferrari, F. y Viroli, F., 2012
Bianchini, C., 2007
Buill, F., Nuñez, M.A. y Rodríguez, J.J., 2007
Docci, M., Maestri, D. 1984
Dore, C. y Murphy, M., 2012
Guidi, G., Russo, M. y Angheleddu, D. 2013
Guidi, G., Russo, M. y Beraldin, J.A., 2010
Herráez Boquera, J., Navarro Esteve, P y Denia Ríos, JL., 2010
Riveiro Rodríguez, B. et al, 2011
Rodríguez Navarro, P., 2012
 Notas: Definición sacada de los apuntes de Topografía de Arquitectura Técnica de la
Universidad Politécnica de Cartagena (UPV). Tema 1, p. 5.

SIG / GIS / GIS.
 Sinónimos: Geographic Information System, Sistemi Informativi Geografici.
 Definición: Acrónimo de Sistema de Información Geográfica (SIG), se utiliza para
almacenar, visualizar y analizar los datos geográficos. Las características espaciales se
almacenan como geometría y se referencian con proyecciones de mapas y coordenadas. Los
atributos almacenados en las tablas son entonces asociados con las características espaciales
para permitir el análisis espacial de los datos.
 Comentarios: Un concepto relacionado con este término es: Sistemas de Información
Arquitectónica (SIA)25 (Buill, F., Nuñez, M.A. y Rodríguez, J.J., 2007).
 Referencias:
Buill, F., Nuñez, M.A. y Rodríguez, J.J., 2007
Dore, C. y Murphy, M., 2012)
Manferdini, A.M. y Remondino, F., 2010
Marambio, A. et al, 2009
Remondino, F. y El-Hakim, S., 2007
 Notas: Interpretación de la definición hecha por Dore, C. y Murphy, M., 2012 (pp. 370): “A
Geographic Information System (GIS) is used for storing, visualizing and analyzing
geographic data. Spatial features are stored as geometry and referenced with map
projections and coordinates. Attributes stored in tables are then associated with spatial
features to allow for spatial analysis of data” Buill, F., Nuñez, M.A. y Rodríguez, J.J. (2007,
p. 21), sin embargo, lo definen como: “un sistema de hardware, software y procedimientos
diseñado para realizar la captura almacenamiento, manipulación, análisis, modelado y
presentación de datos referenciados espacialmente para la resolución de problemas
complejos de planificación y gestión”.

MDT / MDT / DTM.
 Sinónimos: Modelo Digital del Terreno, Modelli Digitali del Terreno, Digital Terrain Model.

25 Buill, F., Nuñez, M.A. y Rodríguez, J.J. (2007, p. 21): “puede gestionar la información arquitectónica
de una ciudad en relación con la trama urbana en la que se encuentra, o bien con la manzana o el
edificio objeto de estudio, vinculando información gráfica y alfanumérica mucho más detallada”

273

<!-- p. 283 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

 Definición: Acrónimo de Modelo Digital del Terreno. “Es un modelo matemático, generado
por ordenador a partir de coordenadas tridimensionales de los puntos que definen la
superficie del mismo, obtenidas mediante un levantamiento taquimétrico o por
fotogrametría”
 Comentarios: Un concepto relacionado con este término es: Ground terrain Model (Dore, C.
y Murphy, M., 2012).
 Referencias:
Guidi, G., Russo, M. y Beraldin, J.A., 2010
Mañana-Borrazás, P., Rodríguez Paz, A. y Blanco-Rotea, R., 2008
Marambio, A. et al, 2009
Remondino, F. y El-Hakim, S., 2007
 Notas: Definición sacada de los apuntes de Topografía de Arquitectura Técnica de la
Universidad Politécnica de Cartagena (UPV).

Georreferenciación / Georeferenziazione / Geo-referencing.
 Sinónimos:
 Definición: “Es un neologismo que refiere al posicionamiento con el que se define la
localización de un objeto espacial (representado mediante punto, vector, área, volumen) en
un sistema de coordenadas y datum determinado.”
 Comentarios: Algunos conceptos relacionados con este término son: Georeferenced point
cloud/mesh (Koska, B. y Křemen, T., 2013), Georeferenced position (Dore, C. y Murphy,
M., 2012), GPS (Sistema de Posicionamiento Global) (Buill, F., Nuñez, M.A., Rodríguez,
J.J., 2007).
 Referencias:
Dore, C. y Murphy, M., 2012
Guidi, G. y Remondino, F. 2012
Koska, B. y Křemen, T., 2013
Marambio, A. et al, 2009
Verdiani, G., 2003
 Notas: Definición sacada de Wikipedia (última visita: 23/11/2013).

Estación total / Stazione totale / Total station
 Sinónimos:
 Definición: “Es un instrumento topográfico universal, formado por un teodolito, un IEMD y
un microprocesador en una sola unidad. Estos aparatos, pueden medir automáticamente
ángulos horizontales y verticales, así como distancias inclinadas desde una sola estación.
Con base a estos datos, ellos pueden calcular instantáneamente lasa componentes
horizontales y verticales de las distancias, las elevaciones y coordenadas.”
 Comentarios: Un concepto relacionado con este término es: Teodolito (Buill, F., Nuñez,
M.A., Rodríguez, J.J., 2007).
 Referencias:
Buill, F., Nuñez, M.A., Rodríguez, J.J., 2007
Herráez Boquera, J., Navarro Esteve, P y Denia Ríos, JL., 2010
Koska, B. y Křemen, T., 2013
Riveiro Rodríguez, B. et al, 2011
Verdiani, G., 2003

274

<!-- p. 284 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

 Notas: Sacada de los Apuntes de Topografía de Arquitectura Técnica de la Universidad
Politécnica de Cartagena (UPCT).

v. Campo 5.- IMAGEN
CONCEPTOS

Imagen Digital / Immagine digitale / Digital Image.
 Sinónimos:
 Definición: “La imagen digital es la representación bidimensional de una imagen
empleando bits, unidad mínima de información compuesta por dígitos binarios (1 y 0), que
se emplea a instancias de la informática y cualquier dispositivo de tipo digital”
Comentarios: Algunos conceptos relacionados con este término son: Aerial images (Lerma, J.L.
et al, 2010), Aerial imagery (Wenzel, K. et al, 2013), Documentación digital (Marambio, A. et
al, 2009), Foto digitali (Bianchini, C., 2007).
 Referencias:
Biosca Taronger, J.M., Navarro Tarín, S. y Lerma García, J.L., 2007
Lerma, J.L. et al, 2011
Marambio, A. et al, 2009
Verdiani, G., 2003
 Notas: Definición sacada de “http://www.definicionabc.com/tecnologia/imagen-digital.php”
(última visita: 10/10/2013).

Color / Colore / color.
 Sinónimos: Informazione cromática (RGB), Información de color.
 Definición: Es generalmente definido como la sensación visiva que se tiene cuando las ondas
electromagnéticas de varia longitud reflejadas desde los cuerpos golpean la retina del ojo
humano. En lenguaje común, es también, la apariencia cromática que presentan los objetos
examinados a su luz natural.
 Comentarios: Algunos conceptos relacionados con este término son: Códigos RGB de color
del punto (Cueli López, J., 2010), Color per vertex26 (Apollonio, F.I., Baldissini, S.,
Manferdini, A.M., Remondino, F., 2010).
 Referencias:
Apollonio, F.I., Baldissini, S., Manferdini, A.M., Remondino, F., 2010
Arbacea, L., et al, 2013
Baldissini, S., Gaiani, M. y Remondino, F., 2010
Corsini, M., et al, 2013
Cueli López, J., 2010
Fantini, F., 2012.
Fantini, F., Rodríguez-Navarro, P. y Di Tondo, S., 2012
Guidi, G., Russo, M. y Beraldin, J.A., 2010
Herráez Boquera, J., Navarro Esteve, P y Denia Ríos, JL., 2010

26 Apollonio, F.I., Baldissini, S., Manferdini, A.M., Remondino, F. (2010, pp. 284) “in cui ogni vertice è
assegnato un valore di colore RGB” Apollonio, F.I., Baldissini, S., Manferdini, A.M., Remondino, F.
(2010, pp. 284)

275

<!-- p. 285 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

Lerma, J. L. et al, 2011
Rodríguez Navarro, P., 2012
Verdiani, G., 2003
 Notas: Interpretación de la definición realizada por Baldissini, S., Gaiani, M. y Remondino,
F. (2010, p. 201): “è generalmente definito come la sensazione visiva che si ha quando le
onde elettromagnetiche di varia lunghezza riflesse dai corpi colpiscono la retina dell’occhio
umano” Remondino, F. y El-Hakim, S. (2007): “è (in lenguaggio comune) anche
l’apparenza cromatica che presentano gli oggetti esaminati alla loro luce naturale”

Mapa de color / Mappatura del colore / Color mapped.
 Sinónimos:
 Definición: El mapa de color es una imagen bidimensional que añade detalles con respecto al
color y es reproducida sobre una o más caras de un modelo poligonal tridimensional.
 Comentarios:
 Referencias:
Arbacea, L., et al, 2013
Corsini, M., et al, 2013
Fantini, F., 2012.
Fantini, F., Rodríguez-Navarro, P. y Di Tondo, S., 2012
Rodríguez Navarro, P., 2012
Notas: Definición inspirada a partir de la definición de “mapeado del modelo”. Debe aclararse
que existen dos tipos de mapas de color: de color difuso y de color aparente. El mapa de color
aparente es aquel que incluye las condiciones precisas de luminosidad, iluminación, etc.
presentes en el momento de la captura de las imágenes, mientras el color difuso es aquel que
presenta un efecto compresivo compuesto por diferentes canales como el de rugosidad,
especularidad, etc. (en general modificados cuando se realiza el render).

Píxel / Pixel / Pixel.
 Sinónimos: Picture element.
 Definición: Un pixel es la porción homogénea más pequeña de la imagen, en forma de
rectángulo y estructurada en una matriz, en la cual se subdivide una imagen digital.
 Comentarios: Algunos conceptos relacionados con este término son: Pixel size (Wenzel, K.
Et al, 2013), Textel27 (Baldissini, S., Gaiani, M. y Remondino, F., 2010) (Guidi, G., Russo,
M. y Beraldin, J.A., 2010).
 Referencias:
Arbacea, L., et al, 2013
Buill, F., Nuñez, M.A., Rodríguez, J.J., 2007
Cueli López, J., 2010
Fantini, F., 2010.
Guidi, G. y Remondino, F. 2012
Marangoni, R. y Geddo, M., 1996

27 Se define en Guidi, G., Russo, M. y Beraldin, J.A. (2010, p. 302) como “i pixel della texture” (los
píxeles de la textura). También es definido por Baldissini, S., Gaiani, M. y Remondino, F. (2010, p.220221) como “un elemento unitario di texture applicato al polígono” (un elemento unitario de textura
aplicado al polígono).

276

<!-- p. 286 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

Verdiani, G., 2003.
 Notas: Según la Real Academia Española, se define como “Superficie homogénea más
pequeña de las que componen una imagen, que se define por su brillo y color” Buill, F.,
Nuñez, M.A., Rodríguez, J.J. (2007, p. 27) lo definen como: “pequeñas unidades de
información radiométrica que elimina la parte mecánica de medición y convierte en
digitales los sistemas fotogramétricos” Cannarozzo, Cucchiarini y Meschieri, 2012.
Volumen 3. P.5 “immagini non fotografiche, ma numeriche, cioè immagini digitali,
strutturate in una matrice di piccoli elementi detti pixel.” (imágenes no fotográficas, sino
númericas, es decir, imagenes digitales, estructuradas en una matriz de pequeños elementos
llamados pixel). Marangoni, R. y Geddo, M. (1996, p. 6): “Il campionamento spaziale
consiste nella suddivisione della superficie dell’immagine in un determinato numero di
rettangoli chiamati pixel ( dall’inglese picture element) (...) in cui essa viene suddivisa ne
determina la risoluzione spaziale ”

Mapeado / Mappatura / Mapped.
 Sinónimos: Texturización, Texturing.
 Definición: El mapeado del modelo en “computer graphyc” es un método para añadir
detalles, una imagen de superficie o un color a imágenes generadas por el ordenador o a un
modelo 3D. Este mapeado genera una textura. La textura es una imagen bidimensional que
es reproducida sobre una o más caras de un modelo poligonal tridimensional.
 Comentarios: Un concepto relacionado con este término es: Baking28 (Fantini, F., Rodríguez-
Navarro, P. y Di Tondo, S., 2012).
 Referencias:
Arbacea, L., et al, 2013
Biosca Taronger, J.M., Navarro Tarín, S. y Lerma García, J.L., 2007
Corsini, M., et al, 2013
Dore, C. y Murphy, M., 2012
Fantini, F., 2010
Fantini, F., 2012
Fantini, F., Rodríguez-Navarro, P. y Di Tondo, S., 2012
Guidi, G., Russo, M. y Angheleddu, D., 2013
Guidi, G., Russo, M. y Beraldin, J.A., 2010
Herráez Boquera, J., Navarro Esteve, P y Denia Ríos, JL., 2010
Lerma, J.L., et al, 2011
Rodríguez Navarro, P., 2012
 Notas: Interpretación del término definido por Thomas, D., Orland, K., Steinberg, S. (2007,
p.62): “Il texture mapping in computer grafica è un metodo per aggiungere dettagli,
un'immagine di superficie o un colore ad immagini generate al computer o ad un modello
3D. Una texture è un'immagine bidimensionale (sprite) che viene riprodotta su una o più

28 Fantini, F., Rodríguez-Navarro, P. y Di Tondo, S. (2012, 33): “(oppure render to texture, bake from
object to texture, etc.) calcolo che permette di codificare esattamente, sotto forma di imagine, i valori di
scostamento esistenti fra il modello subD e il modello ad alto dettagglio geometrico da laser scanner o
high-poly.” (Cálculo que permite codificar exactamente, mediante forma de imagen, los valores de
desviación existentes entre el modelo de subdivisión y el modelo de alto nivel de detalle geométrico del
escáner láser o “high-poly”)

277

<!-- p. 287 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

facce di un modello poligonale tridimensionale”. Guidi, G. y Remondino, F. (2012, p. 94) lo
llaman “texturing” y lo definen como “is achieved mapping a colour images onto the 3D
geometric data” (Mapeo de imágenes en color de los datos geométricos 3D).

Bump mapping / Mappe bump / Bump mapping.
 Sinónimos: Mappa di rugosità.
 Definición: Es una técnica de simulaciones de irregularidad superficial que permite mostrar
sobre la superficie del material una serie de golpes de frecuencia y dimensiones controlables
mediante los parámetros de anchura y altura.
 Comentarios:
 Referencias:
Battini, C., Fantini, F., 2007
Guidi, G. y Remondino, F. 2012
Guidi, G., Russo, M. y Beraldin, J.A., 2010
Manferdini, A.M. y Remondino, F., 2010
 Notas: Interpretación de la definición de Manferdini, A.M. y Remondino, F., (2010, p. 178)
“è una tecnica di simulazione di irregolarità superficiali che permette di mostrare sulla
superficie del materiale una serie di bozzi di frequenza e dimensioni controllabili tramite i
parametri di larghezza e altezza”. Otra definición se encuentra en Guidi, G., Russo, M. y
Beraldin, J.A. (2010, p. 287): “Sono mappe di differenza ottenute calcolando la distanza di
una superficie dall’altra” (Son mapas de diferencia obtenidos calculando la distancia de una
superficie a otra”.

Normal mapping / Mappe delle normali / Normal mapping.
 Sinónimos:
 Definición: Mientras el “bump mapping” obtenido con mapas de altura utiliza imágenes en
tonos de gris para simular irregularidad y detalles de superficie sin modificar la geometría, la
“normal mapping” utiliza imágenes multicanal (canales RGB).
 Comentarios: Un concepto relacionado con este término es: Surface normal (Wenzel, K. et
al, 2013).
 Referencias:
Battini, C., Fantini, F., 2007
Guidi, G. y Remondino, F. 2012
Guidi, G., Russo, M. y Beraldin, J.A., 2010
Manferdini, A.M. y Remondino, F., 2010
Remondino, F. et al, 2012
 Notas: Interpretación de la definición de Manferdini, A.M. y Remondino, F., (2010, p. 190)
“mentre il bump mapping ottenuto con height maps utilizza immagini in toni di grigio per
simulare irregolarità e dettagli di superficie senza modificare la geometria, il normal
mapping utilizza immagini multicanale (canali RGB)”. Se encuentra otra descripción en
Guidi, G., Russo, M. y Beraldin, J.A. (2010, p 287): “sono mappe di differenza ottenute
calcolando la variazione della normale del modello acquisito rispetto a quella del modello
da texturizzare” (son mapas de diferencia obtenidas calculando la variación de las normales
del modelo adquirido respecto a aquellas del modelo a texturizar).

278

<!-- p. 288 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

Displacement mapping / Mappe di scostamento / Displacedment mapping.
 Sinónimos: Mapa de desplazamiento, Displacement map.
 Definición: Es una técnica de “rendering” digital que utiliza mapas de altura (imágenes
ráster en tonos de gris), o mapas de las normales y texturas procesadas para obtener efectos
de relieve y de profundidad donde el modelo geométrico inicial no presenta el mismo grado
de precisión.
 Comentarios: Algunos conceptos relacionados con este término son: Mappe di differenza29
(Guidi, G., Russo, M. y Beraldin, J.A., 2010), Displaced subdivision surface (Fantini, F.,
Rodríguez-Navarro, P. y Di Tondo, S., 2012) (Fantini, F., 2012), Superfici di suddivisione
(Fantini, F., Rodríguez-Navarro, P. y Di Tondo, S., 2012).
 Referencias:
Fantini, F., 2012
Fantini, F., Rodríguez-Navarro, P. y Di Tondo, S., 2012
Guidi, G. y Remondino, F. 2012
Manferdini, A.M. y Remondino, F., 2010
Remondino, F. et al, 2012
 Notas: Interpretación de la definición dada por Manferdini, A.M. y Remondino, F. (2010, p.
\195) “è una tecnica di rendering digitale che utiliza height map (imagine raster in toni di
grigio), oppure mappe delle normali e texture procedurali per ottenere effetti di rilevi e di
profondità dove il modello geometrico iniziale non presenta lo stesso grado di accuratezza.”
(Szimay-kalos e Umenhoffer, 2008).

Visualización / Visualizzazione / Visualization.
 Sinónimos:
 Definición: “Es la generación de una imagen mental o una imagen real de algo abstracto o
invisible”
 Comentarios: Algunos conceptos relacionados con este término son: Rendering30 (Guidi, G.
y Remondino, F., 2012) (Manferdini, A.M. y Remondino, F., 2010), Shared31 (Guidi, G. y

29 Guidi, G., Russo, M. y Beraldin, J.A. (2010, p. 287): “Cuando l’accuratezza è importante, si può fare
uso di tecniche di rilievo tridimensionale per catturare i dettagli superficiali, che possono poi essere
simulati sulla mesh a più bassa definizione tramite l’uso di mappe di differenza” (Cuando la precisión es
importante, se puede hacer un levantamiento tridimensional para capturar los detalles superficiales, que
pueden después ser simulados sobre la malla a más baja definición mediante el uso de mapas de
diferencia)

30 Tipo de visualización
31 Tipo de visualización. Es definida por Guidi, G., Russo, M. y Beraldin, J.A. (2010, p. 280): “Per
visualizzare un modello tridimensionale, questo deve essere associato ad uno shader, ovvero un insieme
di istruzioni che determina come visualizzarne la geometria. Lo shader in sostanza definisce quale debba
essere l’aspetto del materiale di un modello digitale tridimensionale, si che si tratti di un modello
realizzato al CAD, che di un modello poligonale frutto di una acquisizione tridimensionale” (Para
visualizar un modelo tridimensional, este debe ser asociado a un “shader”, o un conjunto de instrucciones
que determina como visualizar la geometría. El “shader” en sustancia define cual debe ser el aspecto
material de un modelo digital tridimensional, sea un modelo realizado en CAD, sea un modelo poligonal
fruto de una adquisición tridimensional).

279

<!-- p. 289 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

Remondino, F., 2012) (Guidi, G., Russo, M. y Beraldin, J.A., 2010), Wireframe32 (Guidi, G.
y Remondino, F., 2012), Photo-realistic perspective (Lerma, J.L. et al, 2010).
 Referencias:
Bianchini, C., 2007
Dore, C. y Murphy, M., 2012
Guidi, G. y Remondino, F., 2012
Marambio, A. et al, 2009
Migliari, R., 2012
Verdiani, G., 2003
 Notas: Definición de Wikipedia (última visita 22/11/2013). Otras definiciones se encuentra
en la RAE. “Acción y efecto de representar mediante imágenes ópticas fenómenos de otro
carácter / Hacer visible una imagen en un monitor”.

Renderización / Rendering / Rendering.
 Sinónimos: Imágenes de renderizado.
 Definición: Restitución visual del modelo.
 Comentarios: Un concepto relacionado con este término es: Rendering fotorealistico
(Fantini, F., Rodríguez-Navarro, P. y Di Tondo, S., 2012).
 Referencias:
Biosca Taronger, J.M., Navarro Tarín, S. y Lerma García, J.L., 2007
Fantini, F., 2012
Guidi, G., Russo, M. y Beraldin, J.A., 2010
Herráez Boquera, J., Navarro Esteve, P y Denia Ríos, JL., 2010
Rodríguez Navarro, P., 2012
 Notas: Definición de Guidi, G., Russo, M. y Beraldin, J.A. (2010, p. 279): “Restituzione
visiva del modello”.

vi. Campo 6.- EDICIÓN 3D
CONCEPTOS

Edición 3D / Edizione 3D / 3D Editing.
 Sinónimos: Mesh editing
 Definición: Serie de fases que llevan con si la eliminación de incoherencias y al mejorado de
la calidad de la superficie poligonal, buscando mantener dentro de lo posible la geometría y
la forma original.
 Comentarios: Algunos conceptos relacionados con este término son: Corrección de bordes
(Marambio, A., et al, 2009), Generation of cut section (Dore, C. y Murphy, M., 2012),
Spigoli degeneri33 (Apollonio, F.I. y Remondino, F., 2010), Spigoli inconsistenti34

32 Tipo de visualización
33 Apollonio, F.I. y Remondino, F. (2010, p.105): “uno spigolo è condiviso da più di due triangoli” (un
borde que está dividido en más de dos triángulos)
34 Apollonio, F.I. y Remondino, F. (2010, p.105): “uno spigolo è condiviso da due triangoli con direzione
della normale oposta” (un borde que está dividido en dos triángulos con direcciones normales opuestas)

280

<!-- p. 290 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

(Apollonio, F.I. y Remondino, F., 2010), Triangoli degeneri35 (Apollonio, F.I. y Remondino,
F., 2010), Triangoli duplicati36 (Apollonio, F.I. y Remondino, F., 2010), Crossing face37
(Guidi, G., Russo, M. y Beraldin, J.A., 2010), Degenerate edges38 (Guidi, G., Russo, M. y
Beraldin, J.A., 2010), Degenerate triangles39 (Guidi, G., Russo, M. y Beraldin, J.A., 2010),
Duplicate triangle40 (Guidi, G., Russo, M. y Beraldin, J.A., 2010), Inconsistent edges41
(Guidi, G., Russo, M. y Beraldin, J.A., 2010), Non-mainfold face42 (Guidi, G., Russo, M. y
Beraldin, J.A., 2010), Redundant face43 (Guidi, G., Russo, M. y Beraldin, J.A., 2010),
Unstable face44 (Guidi, G., Russo, M. y Beraldin, J.A., 2010)
 Referencias:
Apollonio, F.I. y Remondino, F., 2010
Fantini, F., Rodríguez-Navarro, P. y Di Tondo, S., 2012
Guidi, G. y Remondino, F. 2012
 Notas: Interpretación de la definición realizada por Apollonio, F.I. y Remondino, F. (2010,
p. 105): “serie di fasi che portano all’eliminazione di artefatti e al miglioramento della
qualità della superficie poligonale, cercando di preservare il più possibile la geometria e la
forma originale”. Otra definición se encuentra en Guidi, G. y Remondino, F. (2012, p. 93)

35 Apollonio, F.I. y Remondino, F. (2010, p.105): “due o tre vertici di un triangolo sono uguali e il
triangolo diventa quindi uno spigolo o un vertice” (dos o tres vértices de un triángulo son iguales y el
triángulo se convierte en un borde o vértice)
36 Apollonio, F.I. y Remondino, F. (2010, p.105): “due triangoli della stessa mesh hanno gli stessi
vertici” (dos triángulos de la misma malla tienen los mismos vértices)
37 Guidi, G., Russo, M. y Beraldin, J.A. (2010, 215): “Sono quelle facce che si intersecano con la mesh
senza connettersi a nessun nodo di essa (dentro del software Rapidform)” (son aquellas caras que se
intersectan con la malla sin conectarse a ningún vertice de ella)
38 Guidi, G., Russo, M. y Beraldin, J.A. (2010, 214): “È un bordo condiviso da più di due triangoli
(dentro del software Polyworks)” (es un borde dividido en más de dos triángulos)
39 Guidi, G., Russo, M. y Beraldin, J.A. (2010, 214): “Si verifica quando due o tre vertici di una faccetta
triangolare della mesh sono uguali: in tal caso il triangolo degenera rispettivamente in un punto o in un
segmento (dentro del software Polyworks)” (Se verifica cuando dos o tres vertices de una cara poligonal
de la malla son iguales: en tal caso el triángulo degenera respectivamente en un punto o en un segmento)
40 Guidi, G., Russo, M. y Beraldin, J.A. (2010, 214): “Questo errore si verifica quando due triangoli nella
stessa mesh hanno identici vertici (dentro del software Polyworks)” (Este error se verifica cuando dos
triángulos en la misma malla tienen idénticos vértices)
41 Guidi, G., Russo, M. y Beraldin, J.A. (2010, 214): “Un bordo inconsistente è condiviso da due triangoli
adiacenti che hanno orientazione opposta (normali invertite) (dentro del software Polyworks)” (Un borde
inconsistente está compartido por dos triángulos adyacentes que tienen una orientación opuesta (normales
invertidas))
42 Guidi, G., Russo, M. y Beraldin, J.A. (2010, 214): “Si ha questo errore quando più di due facce
condividono uno stesso bordo (equivale a Degenerate edges) (dentro del software Rapidform)” (Se tiene
este error cuando más de dos caras comparten un mismo borde (equivalente a Degenerate edges))
43 Guidi, G., Russo, M. y Beraldin, J.A. (2010, 214): “Sono facce anormali che si possono trovare in una
mesh quando un vertice insistono un numero diverso di vertici e di bordi (dentro del software
Rapidform)” (Son caras anormales que se pueden encontrar en una malla cuando un vertice tiene un
número diverso de vértices y de bordes)
44 Guidi, G., Russo, M. y Beraldin, J.A. (2010, 215): “Sono quelle facce adiacenti caratterizzate da
normali invertite (equivale a Inconsistent edges) (dentro del software Rapidform)” (Son aquellas caras
adyacentes caracterizadas por tener normales invertidas (equivale a Inconsistent edges)

281

<!-- p. 291 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

“allows to correct all possible topological incoherence generated after the polygonal surface
generation”. (Permite corregir toda posible incoherencia topológica generada después de la
generación de la malla poligonal)

Modelado / Modellismo / Modelling.
 Sinónimos:
 Definición: Consiste en la creación o modificación de modelos en tres dimensiones.
 Comentarios:
 Referencias:
Alsadik, B. et al, 2013
Apollonio, F.I., et al, 2010
Bertocci, S., Bini, M., 2012
Fantini, F., 2012
Guidi, G. y Remondino, F. 2012
Guidi, G., Russo, M. y Angheleddu, D., 2013
Guidi, G., Russo, M. y Beraldin, J.A., 2010
Marambio, A., Pucci, B., Nuñez, M.A. y Buill, F., 2009
Remondino, F. et al, 2012
 Notas: Definición de la autora.

Modelo Digital de Superficies (MDS) / Modelli digitali di superfici (MDS) / Digital Surface
Model (DSM).
 Sinónimos: Modelo de superficies, Modelo de polígonos, Modelo poligonal, Surface model,
Modello poligonale, Modelo de mallas, Mesh model, 3D model triangles, Modello a
superfici, Polygonal model.
 Definición: Conjunto extremadamente denso de puntos, unidos entre ellos mediante
pequeñas caras planas.
 Comentarios:
 Referencias:
Buill, F., Núñez, M.A., Rodríguez, J.J, 2007
Dore, C. y Murphy, M., 2012
Fantini, F., 2010
Fantini, F., 2012
Guidi, G. y Remondino, F. 2012
Guidi, G., Russo, M. y Beraldin, J.A., 2010
Koska, B. y Křemen, T., 2013
Lerma, J.L. et al, 2010
Lerma, J. L. et al, 2011
Manferdini, A.M. y Remondino, F., 2010
Mañana-Borrazás, P., Rodríguez Paz, A. y Blanco-Rotea, R., 2008
Marambio, A. et al, 2009
Merlo, A., 2007
 Notas: Definición inspirada en Guidi, G., Russo, M. y Beraldin, J.A. (2010) “Insieme
estremadamente denso di punti, collegati tra loro da poccole faccete planari”.

282

<!-- p. 292 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

Modelo Digital / Modelli digitali / Digital Model.
 Sinónimos:
 Definición: “Un modelo 3D que se pueda manipular, medir, utilizar para reelaboraciones
físicas, visualizar estática o dinámicamente, con el auxilio de un ordenador, representado en
BIT, puede ser definido como modelo tridimensional digital”
 Comentarios:
 Referencias:
Arbacea, L., et al, 2013
Baldissini, S., Gaiani, M. y Remondino, F., 2010
Buill, F., Nuñez, M.A., Rodríguez, J.J, 2007
Fantini, F., 2012
Fantini, F., Rodríguez-Navarro, P. y Di Tondo, S., 2012
Guidi, G. y Remondino, F. 2012
Guidi, G., Russo, M. y Beraldin, J.A., 2010
Mañana-Borrazás, P., Rodríguez Paz, A. y Blanco-Rotea, R., 2008
Merlo, A., 2007
Migliari, R., 2012
Verdiani, G., 2003.
 Notas: La definición viene de la interpretación de la encontrada en Guidi, G., Russo, M. y
Beraldin, J.A. (2010, p. 324): “Un modelo 3D che si possa manipolare, misurare, utilizzare
per rielaborazioni fisiche, visualizzare staticamente o dinamicamente, con l’ausilio di un
computer, in quanto rappresentato da BIT, può essere definito senza tema di smentita come
modello tridimensionale digitale”. Siempre en la misma página encontramos otra definición:
“si intende in generale un modello tridimensionale che, come dice il nome è rappresentato
da digit, ovvero da numeri, che se rappresentati in forma binaria all’interno di un computer
diventano Binary digiT, ovvero BIT.” (Se entiende en general un modelo tridimensional que,
como dice el nombre está representado mediante “digit”, o de números, que representados en
forma binaria dentro de un ordenador se convierten en Binarios digiT, o BIT)

Modelo matemático / Modello matematico / Mathematical model.
 Sinónimos: Rappresentazione matemática.
 Definición: Es aquel modelo fruto de una modelización manual, en la cual el operador
dibuja, con ayuda de los oportunos software, sólidos, elementos para componer, o curvas
más articuladas de las cuales generar complejas superficies matemáticas.
 Comentarios: Algunos conceptos relacionados con este término son: Modello geometrico
(Bertocci, S., Bini, M., 2012) (Bianchini, C., 2007), Modello numerico (Bertocci, S., Bini,
M., 2012) (Fantini, F., 2010).
 Referencias:
Bertocci, S., Bini, M., 2012
Fantini, F., 2012
Guidi, G., Russo, M. y Beraldin, J.A., 2010
Migliari, R., 2012
 Notas: Interpretación de la definición de Guidi, G., Russo, M. y Beraldin, J.A. (2010, p. 325)
“Quelli frutto di una modellazione manuale, in cui l’operatore disegna, con l’ausilio di
opportuni software, solidi elementi da comporre, oppure curve più articolate da cui
generare complesse superfici matematiche”

283

<!-- p. 293 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

Modelización / Modellazione / modelling.
 Sinónimos:
 Definición: Parte de una formulación conceptual del objeto, que viene progresivamente
definida en sus detalles con las técnicas de representación propias del dibujo. Solo en un
segundo momento este sistema abstracto se transforma en objeto físico.
 Comentarios: Algunos conceptos relacionados con este término son: Automated 3D
modelling procedures (Guidi, G. y Remondino, F. 2012), Digital photo modelling (Dore, C.
y Murphy, M., 2012), Modelados fotorrealísticos 3D (Lerma, J.L., et al., 2011).
 Referencias:
Rodríguez Navarro, P., 2012
Lerma, J.L., et al., 2011
Dore, C. y Murphy, M., 2012
Balzani, M., Ferrari, F. y Viroli, F., 2012
Guidi, G. y Remondino, F. 2012
Manferdini, A.M. y Remondino, F., 2010
Merlo, A., 2007
Migliari, R., 2012
Guidi, G., Russo, M. y Beraldin, J.A., 2010
 Notas: Interpretación de la descripción dada por Guidi, G., Russo, M. y Beraldin, J.A.,
(2010, p. 195): “parte da una formulazione concettuale dell’oggetto, che viene
progressivamente definita nei suoi dettagli con le tecniche di rappresentazione proprie del
disegno. Solo in un secondo momento questo sistema astratto viene trasformato in oggetto
físico”.

Reconstrucción virtual / Ricostruzione virtuale / virtual reconstruction.
 Sinónimos: Reconstrucciones 3D, Digital reconstruction, Restituzione virtuale.
 Definición: Reconstrucción de escenarios y objetos en tres dimensiones en el ordenador.
“Modelos que representan sea la síntesis interpretativa de las investigaciones históricas que
un terreno de confrontación divisible entre diversos estudios en merito a las diversas
soluciones reconstructivas adoptadas y como instrumento útil para la simulación de todos
los aspectos de utilidad de los diversos ambientes, hasta el uso de estos modelos como
instrumento de conocimiento y valorización para el público”
 Comentarios: Algunos conceptos relacionados con este término son: Image based surface
reconstruction (Wenzel, K. et al, 2013), Sparse reconstruction form images (Koska, B. y
Křemen, T., 2013), Photogrammetric surface reconstruction (Wenzel, K. et al, 2013)
Reconstruct the 3D shapes (Guidi, G. y Remondino, F. 2012).
 Referencias:
Balzani, M., Ferrari, F. y Viroli, F., 2012
Bianchini, C., 2007
Buill, F., Nuñez, M.A., Rodríguez, J.J., 2007
Guidi, G., Russo, M. y Angheleddu, D., 2013
Guidi, G., Russo, M. y Beraldin, J.A., 2010
Lerma, J.L., et al., 2011
Manferdini, A.M. y Remondino, F., 2010

284

<!-- p. 294 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

Merlo, A., 2007
Remondino, F. y El-Hakim, S., 2007
Riveiro Rodríguez, B. et al, 2011
Verdiani, G., 2003
Wenzel, K. et al, 2013
 Notas: Interpretación de la descripción de la reconstrucción virtual de Guidi, G., Russo, M. y
Beraldin, J.A. (2010, p. 335): “Questi modelli infatti rappresentano sia la sintesi
interpretativa delle ricerche storiche che un terreno di confronto condivisibile tra i diversi
studiosi in merito alle diverse soluzioni ricostruttive adottate e come strumento utile per la
simulazione di tutti gli aspetti di fruibilità dei diversi ambienti, fino all’uso di questi modelli
come strumento di conoscenza e valorizzazione al pubblico”.

Malla - Mesh / mesh / mesh.
 Sinónimos: Malla de polígonos, 3D triangular mesh, Maglia, Maglia di poligoni, Mesh
surface, Modelo poligonal sin estructura (malla).
 Definición: Modelo poligonal resultante de la conversión de la nube de puntos. Restitución
de la geometría compuesta por triángulos.
 Comentarios:
 Referencias:
Apollonio, F.I. y Remondino, F., 2010
Bianchini, C., 2007
Cueli López, J., 2010
Dore, C. y Murphy, M., 2012
Fantini, F., Rodríguez-Navarro, P. y Di Tondo, S., 2012
Guidi, G., Russo, M. y Beraldin, J.A., 2010
Herráez Boquera, J., Navarro Esteve, P y Denia Ríos, JL., 2010
Koska, B. y Křemen, T., 2013
Lerma, J.L. et al, 2010
Manferdini, A.M. y Remondino, F., 2010
Mañana-Borrazás, P., Rodríguez Paz, A. y Blanco-Rotea, R., 2008
Marambio, A., et al, 2009
Merlo, A., 2007
Rodríguez Navarro, P., 2012
Verdiani, G., 2003
Wenzel, K. et al, 2013
 Notas: Definición inspirada en la descripción de Apollonio, F.I. y Remondino, F. (2010, p.
104-105). Además añade: “modello poligonale prodotto attraverso la fusione delle differenti
scansioni” (modelo poligonal producido a través de la fusión de los diferentes escaneados).
Manferdini, A.M. y Remondino, F. (2010, p. 175) la describen como “superficie poligonale”
(superficie poligonal). La descripción de Guidi, G., Russo, M. y Beraldin, J.A. (2010, p. 196)
enuncia “i punti vengono successivamente trasformate in un insieme di faccette poligonali
interconnesse fra di loro, che approssimano l’andamento della superficie dell’oggetto
secondo una geometria poligonale” (Los puntos vienen sucesivamente transformados en un
conjunto de caras poligonales interconectadas entre ellas, que aproximan el curso de la
superficie del objeto según una geometría poligonal). Mañana-Borrazás, P., Rodríguez Paz,
A. y Blanco-Rotea, R. (2008, p. 21) la describen como “triangular la nube de puntos”.

285

<!-- p. 295 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

Triangulación / Triangolarizzazione / Meshing.
Sinónimos: Generación de superficies poligonales, Fase de triangulación, Polygonal model
generation, Meshing of the 3D point cloud, Triangulation, Merge, TIN45, Unión de los puntos de
escaneo, Facetear.
 Definición: Una vez que se obtiene una nube de puntos mediante la concordancia de
imágenes o un conjunto de nubes de puntos alineados adquiridos con un sensor activo,
generalmente se produce un modelo poligonal ("malla").
 Comentarios:
 Referencias:
Apollonio, F.I., et al, 2010
Biosca Taronger, J.M., Navarro Tarín, S. y Lerma García, J.L., 2007
Cueli López, J., 2010
Dore, C. y Murphy, M., 2012
Guidi, G. y Remondino, F. 2012
Guidi, G., Russo, M. y Beraldin, J.A., 2010
Lerma, J.L., et al, 2010
Mañana-Borrazás, P., Rodríguez Paz, A. y Blanco-Rotea, R., 2008
Marambio, A., et al, 2009
 Notas: Interpretación de la definición de Guidi, G. y Remondino, F. (2012, p. 91) “Once a
point cloud from image matching or a set of aligned point clouds acquired with an active
sensor are obtained, a polygonal model (“mesh”) is generally produced” Otra definición se
encuentra en Biosca Taronger, J.M., Navarro Tarín, S. y Lerma García, J.L. (2007, p. 3): “las
nubes de puntos se convierten en mallas de triángulos o cuadriláteros y constituye la parte
central del proceso de reconstrucción tridimensional de un objeto”. Apollonio, F.I., et al,
(2010, p. 277) definen el proceso como “fusione in un’unica mesh, consiste nella
trasformazione delle nuvole di punti in precedenza allineate in un’unica superficie
poligonale”. (Fusión en una única malla, consiste en la transformación de las nubes de
puntos en precedencia alineados en una única superficie poligonal). Guidi, G., Russo, M. y
Beraldin, J.A. (2010, p. 206) la describe como: “Il passaggio dalla nube grezza di punti 3D
prodotta dal sensore ad un reticolo di poligoni connessi tra loro, i cui vertici coincidono con
i punti misurati (mesh), è quando viene indicato con el termine meshing” (El paso de la
nube inicial de puntos 3D, producida por el sensor, a un retículo de polígonos conectados
entre ellos, cuyos vértices coinciden con los puntos medidos (mesh), es cuando viene
indicado con el término “meshing”)

Subdivisión / Subdivisione / Subdivision.
 Sinónimos:
 Definición: Corresponde al proceso inverso respecto a la “decimación” (reducción de
polígonos), y por lo tanto, a la introducción de un número superior de polígonos.
 Comentarios:
 Referencias:
Guidi, G. y Remondino, F. 2012
Guidi, G., Russo, M. y Beraldin, J.A., 2010

45 Mañana-Borrazás, P., Rodríguez Paz, A. y Blanco-Rotea, R. (2008, p. 26) “Crear una superficie en base
a la triangulación de los puntos”

286

<!-- p. 296 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

 Notas: Interpretación de la descripción encontrada en Guidi, G., Russo, M. y Beraldin, J.A.
(2010, p. 218): “corrisponde al processo inverso rispetto alla decimazione (...) consiste nella
introduzione di un numero superiore di poligoni”

Decimación / Decimazione / Decimated.
 Sinónimos: Reducción del número de polígonos, Reducción del número de triángulos,
Reduced model size, Point/triangles reduction.
 Definición: Reduce sensiblemente la complejidad del modelo eliminando vértices y
manteniendo, sin embargo, bajo control las variaciones introducidas respecto a la precisión
inicial. Este proceso describe una clase de algoritmos que transforman una malla poligonal
base en otra con un número menor de caras, bordes y vértices.
 Comentarios:
 Referencias:
Apollonio, F.I., et al, 2010
Apollonio, F.I. y Remondino, F., 2010
Biosca Taronger, J.M., Navarro Tarín, S. y Lerma García, J.L., 2007
Guidi, G. y Remondino, F. 2012
Guidi, G., Russo, M. y Beraldin, J.A., 2010
Koska, B. y Křemen, T., 2013
Lerma, J.L., et al, 2010
Marambio, A., et al, 2009
 Notas: Interpretación de la definición realizada por Apollonio, F.I. y Remondino, F. (2010,
p. 106) “riduce sensibilemente la complessità del modello, eliminando vertici e mantenendo
comunque sotto controllo le variazioni introdotte rispetto alla precisione iniziale”. Añade
más dos páginas después “descrive una classe di algoritmi che trasforma una data mesh
poligonale in un’altra con un numero minore di facce, spigoli e vertici”. Otra descripción se
encuentra en Apollonio, F.I., et al, (2010, p. 281): “definizione dell’algoritmo più idoneo a
semplificare la superficie e diminuire il rumore, pur mantenendo la complessità formale
richiesta” (Definición del algoritmo mejor para simplificar la superficie y disminiur el ruido,
manteniendo la complejidad formal requerida). Otra descripción se encuentra en Guidi, G.,
Russo, M. y Beraldin, J.A. (2010, p. 217): “Il numero dei poligoni può essere ridotto
intervenendo direttamente con algoritmi che decimano la mesh, riducendo sensibilmente la
complessità del modello e mantenendo comunque sotto controlo le variazioni introdotte
rispetto alla precisione iniciale (Soucy e Laurendeau, 1995)” (El número de polígonos puede
ser reducido interviniendo directamente como algoritmos que “deciman” la malla,
reduciendo sensiblemente la complejidad del modelo e manteniendo, aún así, bajo control las
variaciones introducidas respecto a la precisión inicial).

Oclusión / Lacune / occlusion.
 Sinónimos: Zone d’ombra, Zonas de sombra.
 Definición: “Zonas de sombras sin información en la nube de puntos”
 Comentarios: Un concepto relacionado con este término es: Zonas ocultas (Biosca Taronger,
J.M., Navarro Tarín, S. y Lerma García, J.L., 2007)
 Referencias:
Apollonio, F.I. y Remondino, F., 2010
Biosca Taronger, J.M., Navarro Tarín, S. y Lerma García, J.L., 2007
Fantini, F., Rodríguez-Navarro, P. y Di Tondo, S., 2012

287

<!-- p. 297 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

Guidi, G., Russo, M. y Beraldin, J.A., 2010
Lerma, J.L. et al,2011.
Mañana-Borrazás, P., Rodríguez Paz, A. y Blanco-Rotea, R., 2008
 Notas: Mañana-Borrazás, P., Rodríguez Paz, A. y Blanco-Rotea, R., 2008, p. 19. Definición
similar se encuentra en (Biosca Taronger, J.M., S. Navarro Tarín y J. L. Lerma García, 2007,
p. 5): “Aquellas zonas del modelo que no salen en una determinada imagen tomada del
objeto reconstruido”. En italiano, Apollonio, F.I. y Remondino, F. (2010, p.105) las definen
como: “assenza di dati in zone d’ombra presenti sull’oggetto al momento dell’acquisizione
(ovvero quelli parti di superficie non raggiungibili dallo strumento) o da problemi di
acquisizione legati alla particolare caratteristica di riflessione del materiale o da una bassa
densità della nuvola che non consente all’algoritmo di triangolazione di generare una mesh
completa” (ausencia de datos en zonas de sombra presentes sobre el objeto en el momento de
la adquisición {o aquellas parte de superficie no alcanzables por el instrumento} o por
problemas de adquisición unidos a las particulares características de reflexión del material o
de una baja densidad de la nube que no consiente mediante el algoritmo de triangulación
generar una malla completa). Guidi, G., Russo, M. y Beraldin, J.A. (2010, p. 215) las
definen, sin embargo, como: “Possono essere generate da zone d’ombra presenti
sull’oggetto o da problemi d’acquisizione legati alla particolare caratteristica di reflessione
del materiale.” (Pueden ser generadas mediante zonas de sombra presentes en el objeto o por
problemas de adquisición unidos a las características particulares de reflexión del material).

Relleno huecos / Chiusura di fori / Fill holes.
 Sinónimos: Reducción del número de zonas ocultas, Eliminación de las sombras, Rellenar
los agujeros.
 Definición: Generación de una parte de la superficie poligonal ausente, debido a la presencia
de sombras en el momento de adquisición, por problemas de adquisición unidos a las
particulares características de reflexión del material o de una baja densidad de la nube que no
consiente mediante el algoritmo de triangulación generar una malla completa, utilizando la
información de los bordes que la circundan.
 Comentarios:
 Referencias:
Biosca Taronger, J.M., Navarro Tarín, S. y Lerma García, J.L., 2007
Buill, F., Núñez, M.A., Rodríguez, J.J, 2007
Lerma, J.L., et al., 2011
Marambio, A., et al, 2009
Verdiani, G., 2003
 Notas: Inspirada en las definiciones usadas en el término “oclusiones”.

Ruido / Rumore / Noise.
 Sinónimos: Puntos erróneos.
 Definición: Puntos erróneos que surgen en la adquisición de datos, debido a un problema con
el material o por la geometría del objeto (ej. objetos curvos presentan problemas en las zonas
tangentes), o en la fase de registro debido a una alineación incorrecta entre diferentes nubes
de puntos.

288

<!-- p. 298 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

 Comentarios: Un concepto relacionado con este término es: Superficie rumorosa46 (Guidi,
G., Russo, M. y Beraldin, J.A., 2010)
 Referencias:
Apollonio, F.I. y Remondino, F., 2010
Biosca Taronger, J.M., Navarro Tarín, S. y Lerma García, J.L., 2007
Buill Pozuelo, F., Núñez Andrés, M.A. y Marambio Castillo, A.
Lerma, J. L. et al, 2011
Marambio, A. et al, 2009
Verdiani, G., 2003
Wenzel, K. et al, 2013
 Notas: Definición realizada por la autora.

Textura / Tessitura / Texture
 Sinónimos:
 Definición: Es típicamente una imagen digital que reproduce la variación cromática de una
superficie.
 Comentarios: Algunos conceptos relacionados con este término son: Apparenza visiva47
(Apollonio, F.I. y Remondino, F., 2010), Texturas del color (Rodríguez Navarro, P., 2012),
Fast texture (Cueli López, J., 2010), Quality texture (Cueli López, J., 2010).
 Referencias:
Apollonio, F.I. y Remondino, F., 2010
Biosca Taronger, J.M., Navarro Tarín, S. y Lerma García, J.L., 2007
Buill, F., Núñez, M.A., Rodríguez, J.J, 2007
Buill Pozuelo, F., Núñez Andrés, M. A. y Marambio Castillo, A.
Cueli López, J., 2010
Guidi, G., Russo, M. y Beraldin, J.A., 2010
Herráez Boquera, J., Navarro Esteve, P y Denia Ríos, JL., 2010
Koska, B. y Křemen, T., 2013
Lerma, J.L. et al, 2010
Lerma, J. L. et al, 2011.

46Guidi, G., Russo, M. y Beraldin, J.A. (2010, p. 213) la definen como “Possono essere legate alla scelta
di un strumento di acquisizione non coerente con l’oggetto da rilevare, alla non perfetta eliminazione
delle incoerenze in fase di allineamento, oppure alla generazione di errori topologici e alla non corretta
triangolarizzazione di alcune aree in fase di fusione” (Pueden ser legadas a la elección de un instrumento
de adquisición no coherente con el objeto a levantar, a la no perfecta eliminación de las incoherencias en
la fase de alineación, o debido a la generación de errores topológicos y a la no correcta triangulación de
algunas áreas en fase de fusión).
47 Definida por Apollonio, F.I. y Remondino, F. (2010, p. 114) como “aspetto qualitativo. Possibilità del
modello 3D di rappresentare l’oggetto reale riproducendo, nella maniera più fedele possibile, anche il
comportamento della superficie rispetto alla riflessione della luce, includendo le caratteristiche di colore
e di finitura della superficie stessa”. (Aspecto cualitativo. Posibilidad del modelo 3D de representar el
objeto real reproduciendo, en la manera más fiel posible, también el comportamiento de la superficie con
respecto a la reflexión de la luz, incluyendo las características de color y de acabado de la superficie
misma) “Propietà definita come texture della superficie.” (propiedad definida como la textura de la
superficie)

289

<!-- p. 299 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

Manferdini, A.M. y Remondino, F., 2010
Marambio, A. et al, 2009
Merlo, A., 2007
Remondino, F. y El-Hakim, S. (Eds.), 2007
Rodríguez Navarro, P., 2012
Wenzel, K. Et al, 2013
 Notas: Interpretación de la definición de Guidi, G., Russo, M. y Beraldin, J.A. (2010, p. 279)
“È tipicamente un’immagine digitale che riproduce la variazione cromatica di una
superficie; (...) possono essere utilizzate per simulare altre caratteristiche visive oltre al
colore, quali la lucità, la trasparenza, la rifrazione, ecc.”. Otra referencia que se encuentra
con respecto a la descripción de la textura, se observa en Apollonio, F.I. y Remondino, F.
(2010, p. 114) “può includere descrizioni relative alla geometria della superficie di scala
fine, come ad esempio mappe ad alta risoluzione spaziale delle normali alla superficie o
texture bi-direzionali. Tessitura del modello geométrico” (puede incluir descripciones
relativas a la geometría de la superficie de escala fina, como por ejemplo mapas de alta
resolución espaciales de las normales a la superficie o texturas bi-direccionales).

Texture mapping / Texture mapping / Texture mapping
 Sinónimos: Texture map
 Definición: Proyección de imágenes sobre la estructura geométrica tridimensional.
 Comentarios: Este término se usa siempre en inglés.
 Referencias:
Apollonio, F.I. et al, 2010
Baldissini, S., Gaiani, M. y Remondino, F., 2010
Corsini, M., et al, 2013
Fantini, F., 2012
Guidi, G. y Remondino, F. 2012
Guidi, G., Russo, M. y Beraldin, J.A., 2010
Koska, B. y Křemen, T., 2013
Lerma, J.L. et al, 2010
Lerma, J. L. et al, 2011
 Notas: Interpretación de la definición dada por Guidi, G., Russo, M. y Beraldin, J.A. (2010,
p. 279) “proiezione di immagini sulla struttura geometrica tridimensionale.” Continuando en
la misma página, agrega que: “Il processo di texture mapping permette di aggiungere al
modello tridimensionale alcune informazioni riguardanti il materiale e alcuni dettagli
formali non presenti nel modello digitale, il tutto senza aumertarne la compessità
geometrica. Tale risultato viene raggiunto proiettando opportunamente un’immagine
(texture) sulla superficie dell’oggetto, che è resa fruibile al momento della restituzione visiva
del modello.” (El proceso de “texture mapping” permite de adjuntar al modelo tridimensional
alguna información con respecto al material y algunos detalles formales no presentes en el
modelo digital, todo sin aumentar la complejidad geométrica. El resultado viene adjunto
proyectando oportunamente una imagen (textura) sobre la superficie del objeto, que se hace
accesible en el momento de la restitución visiva del modelo) Otra definición la encontramos
en Baldissini, S., Gaiani, M. y Remondino, F. (2010, p.220): “Il texture mapping consiste nel
mappare un’immagine sulla geometria di un oggetto per creare l’aspetto del dettaglio di
superficie fine.” (El “texture mapping” consiste en mapar una imagen sobre la geometría de
un objeto para crear el aspeto del detalle de superficie fina) “Il texture mapping sia la

290

<!-- p. 300 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

mappatura di una funzione su una superficie 3D” (El “texture mapping” es el mapeado de
una función sobre una superficie 3D). En Apollonio, F.I. et al (2010, p. 284) se describe “in
cui una singola immagine texture è “mappata” sul modello” (en la cual una imagen
individual texturizada es mapeada sobre el modelo).

Espacio UV / Spacio UV / Space UV.
 Sinónimos: Sistema di riferimento UV
 Definición: Cuando se aplica una proyección a una malla, el vértice de cada triángulo se
combinado con un par de coordenadas adicionales, U y V, que determinan la posición en el
espacio de la textura. Cada triángulo se encuentra así asociado a una porción específica de la
textura. El espacio de la textura es un plano cartesiano, llamado espacio UV, donde U es la
coordenada horizontal y V la coordenada vertical.
 Comentarios:
 Referencias:
Fantini, F., 2011
Fantini, F., 2010.
Guidi, G., Russo, M. y Beraldin, J.A., 2010
 Notas: Interpretación de la definición de Guidi, G., Russo, M. y Beraldin, J.A. (2010, p.
296): “Quando si applica una proiezione ad una mesh il vertice di ciascun triangolo viene
abbinato ad una coppia di coordinate aggiuntive, U e V, che ne determinano la posizione
nello spazio delle texture. Ciascun triangolo si trova così associato ad una porzione
specifica della texture. Lo spazio della texture è un piano cartesiano, detto spazio UV, dove
U è la coordinata orizzontale e V la coordinata verticale”

CAD / CAD / CAD.
 Sinónimos: Computer Aided Desing
 Definición: “El diseño asistido por computadora, más conocido por sus siglas inglesas CAD
(computer-aided design), es el uso de un amplio rango de herramientas computacionales
que asisten a ingenieros, arquitectos y a otros profesionales del diseño en sus respectivas
actividades. Estas herramientas se pueden dividir básicamente en programas de dibujo en
dos dimensiones (2D) y modeladores en tres dimensiones (3D). Las herramientas de dibujo
en 2D se basan en entidades geométricas vectoriales como puntos, líneas, arcos y polígonos,
con las que se puede operar a través de una interfaz gráfica. Los modeladores en 3D añaden
superficies y sólidos”
 Comentarios:
 Referencias:
Bianchini, C., 2007
Dore, C. y Murphy, M., 2012
Guidi, G. y Remondino, F., 2012
Guidi, G., Russo, M. y Beraldin, J.A., 2010
Herráez Boquera, J., Navarro Esteve, P y Denia Ríos, JL., 2010
 Notas: Definición sacada de Wikipedia (última visita: 22/11/2013).

NURBS / NURBS / NURBS.
 Sinónimos:

291

<!-- p. 301 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

 Definición: Es el acrónimo de Non Uniform Rational B-Splines (NURBS). Es una clase de
curvas geométricas, las B-Splines racionales no uniformes, utilizadas en computer graphic
para representar curvas y superficies. Una NURBS es por lo tanto la representación
matemática que un programa software, por ejemplo un sistema CAD 3D, crea de un objeto,
para definir con precisión su forma.
 Comentarios: Algunos conceptos relacionados con este término son: Rappresentazione
matematica (Migliari, R., 2012) (Benedetti, B., Gaiani, M. y Remondino, F., 2010), Modello
numerico (Bertocci, S., Bini, M., 2012) (Fantini, F., 2010), Displaced subd (Bertocci, S.,
Bini, M., 2012) (Fantini, F., 2011).
 Referencias:
Fantini, F., 2012
Guidi, G. y Remondino, F. 2012
Guidi, G., Russo, M. y Beraldin, J.A., 2010
Merlo, A., 2007
Migliari, R., 2012
Verdiani, G., 2003
 Notas: Inspirada en la descripción de Benedetti, B., Gaiani, M. y Remondino, F. (2010, p.
356): “Non Uniform Rational B-Splines (NURBS): È una clase di curve geometriche, le B-
Splines razionali non uniformi, utilizzate in computer grafica per reppresentare curve e
superfici. Una NURBS è quindi la rappresentazione matematica che un programma
software, ad esempio un sistema CAD 3D, crea di un oggetto, per definirne accuratamente
la forma”.

Filtrado / Filtraggio / Filtering.
 Sinónimos:
 Definición: Filtrar un dato significa modificar intrínsecamente la información unida a cada
punto individual, interviniendo directamente sobre las coordenadas espaciales o sobre la
información cromática. El filtrado de los datos puede afectar a dos principales aspectos: por
un lado la eliminación de los elementos externos a la geometría levantada, o por el otro la
modificación de los datos afectados por un error incompatible con las características
geométricas del modelo físico.
 Comentarios: Algunos conceptos relacionados con este término son: Limpiar los datos
(Marambio, A., et al, 2009), Remove redundancies (Lerma, J.L., et al, 2010).
 Referencias:
Dore, C. y Murphy, M., 2012
Guidi, G., Russo, M. y Beraldin, J.A., 2010
Lerma, J.L., et al., 2011
 Notas: Interpretación de la definición de Guidi, G., Russo, M. y Beraldin, J.A. (2010, 205):
“Filtrare un dato significa modificare intrinsecamente le informazioni legate ad ogni singolo
punto, agendo direttamente sulle coordinate spaziali o sulla informazione cromatica (...) Il
filtraggio dei dati può riguardare due principali aspetti: da un lato l’eliminazione degli
elementi estranei alla geometria rilevata, dall’altro la modifica dei dati affetti un errore
incompatibile con le caratteristiche geometriche del modello fisico”.

292

<!-- p. 302 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

Pre-procesamiento / pre-elaborazione / pre-processing.
 Sinónimos:
 Definición: “incluye la reducción del ruido, el ajuste del color, contraste y luminosidad de
las imágenes, el coloreado de las nubes de puntos y el registro de las posiciones del
escáner”.
 Comentarios: Algunos conceptos relacionados con este término son: Post procesamiento48
(Marambio, A., et al, 2009), Post processing (Balzani, M., Ferrari, F. y Viroli, F., 2012).
 Referencias:
Dore, C. y Murphy, M., 2012
Lerma, J.L., et al, 2010
Marambio, A., et al, 2009
 Notas: Marambio, A., et al. (2009, p. 5)

Post-producción / post-elaborazione / Post-processing.
 Sinónimos:
 Definición: El modelo digital 3D obtenido a partir de las fases de registro de los escaneados,
triangulación y edición debe, a menudo, ser sometido a más de un post-procesado para
adaptarlo a la aplicación que se está llevando a cabo.
 Comentarios: Algunos conceptos relacionados con este término son: Remeshing49
(Apollonio, F.I. y Remondino, F., 2010) (Guidi, G., Russo, M. y Beraldin, J.A., 2010),
Smoothing50 (Apollonio, F.I. y Remondino, F., 2010), Retopology51 (Fantini, F., Rodríguez-

48 Marambio, A., et al. (2009, p. 5): “incluye la optimización de la nube de puntos general y la creación
de secciones y ortoimágenes de los edificios a una resolución “x” para la representación de la escala
“y””
49 Apollonio, F.I. y Remondino, F. (2010, p.113): “data una mesh tridimensionale, determinare una
nuova superficie poligonale i cui elementi costrutivi siano in grado di soddisfare requisiti di qualità,
fornendo una buona approssimazione della mesh di partenza.Il termine approssimazione deve essere
inteso sia in relazione alla posizione, che all’orientamento delle normali e ad altre proprietà di ordine
superiore” (Dada una malla tridimensional, determinar una nueva superficie poligonal en la cual los
elementos constructivos satisfagan requisitos de calidad, dando una buena aproximación de la malla de
partida. El termino aproximado deber ser entendido sea en relación a la posición que a la orientación de
las normales y a otras propiedades de orden superior) Otra definición se encuentran en Guidi, G., Russo,
M. y Beraldin, J.A. (2010, p. 218): “è una regolarizzazione generale della posizione dei vertici della
mesh, generalmente molto disordinata al termine del processo di editing e ottimizazione” (es una
regularización general de la posición de los vértices de la malla, generalmente muy desordenada al
terminar el proceso de edición y optimización)
50 Apollonio, F.I. y Remondino, F. (2010, p.106): “redurre (lisciare) artefatti in modo tale che la forma
globale, o i componenti a bassa frequenza, sia garantita. Prende in considerazione un’area attorno a
ciascun vertice entro cui ridurre le differenze di quota tra i punti in base ad una tolleranza indicata”
(reducir (alisar) artefactos de tal modo que la forma global, o los componentes a baja frecuencia, sea
garantizada. Tiene en consideración un área en torno a cada vértice dentro del cual reduce las diferencias
de cota entre puntos basado en la tolerancia indicada).
51 Fantini, F., Rodríguez-Navarro, P. y Di Tondo, S. (2012, p. 32): “tecnica di modellazione che di fatto è
una sorta di remeshing controllato interattivamente dall’utente ed ha come finalità quella di ottenere una
topologia prevalentemente quadrangolare che “ricalca” la forma complessa ottenuta mediante rilievo

293

<!-- p. 303 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

Navarro, P. y Di Tondo, S., 2012) (Fantini, F., 2012), Verificación del modelo (Marambio,
A., et al, 2009).
 Referencias:
Apollonio, F.I. y Remondino, F., 2010
Guidi, G., Russo, M. y Beraldin, J.A., 2010
Rodríguez Navarro, P., 2012
 Notas: Interpretación de la definición encuentrada en Apollonio, F.I. y Remondino, F.,
(2010, p. 105): “il modello digitale 3D ottenuto dalle fasi di registrazione delle scanzioni,
triangolazione ed editing deve, spesso, essere sottoposto ad un’ulteriore post-processing al
fine di adattarlo all’applicazione che si sta conducendo.”

laser scanner o mediante sistemi di scultura digitale 3D.” (Técnica de modelación que de hecho es un
conjunto de “remesing” controlado interactivamente por el usuario y tiene como finalidad obtener una
topología prevalentemente cuadrangular que “recalca” la forma compleja obtenida mediante láser escáner
o mediante sistemas de escultura digital 3D)

294

<!-- p. 304 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

F. ÍNDICE DE TÉRMINOS

Español

Términos Página Términos Página

A

Adquisición de datos 242 Alto nivel de detalle 254

Aéreo 247 Analítica 265

Alineación 271 Analógica 264

Alta definición 254 área de solape 246

alta resolución 254 Auto-calibración 249

B

Baja definición 254 Barridos 245

bajo detalle 254 Barridos escáner láser 267

Barredores (escáneres) láser 265, 267 Bump mapping 278

C

CAD 291 Colinealidad 264

Calibración 247 Color 275

Calibrar inversamente 248 Color per vertex 275

Cámara 263 Corrección de bordes 280

Clásico 256 Corrección del eje óptico 248

Códigos RGB de color del punto 275 Croquis 256

D

Datos brutos 245 Diana de control 246

Decimación 287 Dianas circulares 246

Desviación estándar 244 Dianas codificadas 246

Diana 246 Dianas esféricas 246

295

<!-- p. 305 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

Dianas naturales 246 Distorsión 245

Diferencia de fase 270 Documentación digital 275

Digital 255 Documentación métrica 245

Displacement mapping 279 Drone 250

Distancia focal 264

E

Edición 3D 280 Escáner Láser 3D 265, 267

Elementos barridos 267 Espacio UV 291

Eliminación de las sombras 288 Estación total 274

Empalme 271 Estereofotogrametría 265

Equipo de medición de láser 265 Estereoscópico 265

Error topológico 244 Exactitud 243

Escaneado 267

F

Facetear 286 Fotograma 260

Fase de triangulación 286 Fotogrametría 257

Filtrado 292 Fotogrametría de escáner láser 267

Fotogrametría Digital
Flujo de trabajo 250 Automatizada 258

Fotografía 260 Fotoplano 261

Fotografías estereoscópicas 265 Fotorrealista 256

G

Generación de superficies GPS (Sistema de
poligonales 286 Posicionamiento Global) 274

Georreferenciación 274

296

<!-- p. 306 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

I

IBM (Image-Based Modelling) 258 Imágenes de renderizado 280

Image matching 259 Información de color 275

Imagen Digital 275 Iterative Closest Point (ICP) 252

Imágenes con carácter métrico 260

L

Láser escáner 265, 267 LiDAR 266

Levantamiento 242 Limpiar los datos 292

M

Malla - Mesh 285 Modelado 282

Malla de polígonos 285 Modelado inverso 251

Mapa de color 276 Modelados fotorrealísticos 3D 284

Mapa de desplazamiento 279 Modelización 284

Mapeado 277 Modelo de mallas 282

MDT 273 Modelo de polígonos 282

Medición 245 Modelo de polígonos 282

Medición basados en el tiempo 270 Modelo de superficies 282

Medición de distancia 270 Modelo Digital 283

Medición del tiempo de vuelo Modelo Digital de Superficies
(TOF) 270 (MDS) 282

Medida de distancia 270 Modelo Digital del Terreno 273

Medida directa 256 Modelo matemático 283

Modelo poligonal sin
Method Bundle Adjustment 249 estructura (malla) 285

Método general de la Modelos de malla
fotogrametría 258 simplificados 255

Modelos optimizados 255

297

<!-- p. 307 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

N

Nivel de detalle 252 Nube de puntos de color 269

Normal mapping 278 Nube ligera 269

Nube de puntos 268 NURBS 291

Nube de puntos 3D 268

O

Oclusión 287 Ortofotografía 260

Optimización 251 Ortoimágenes 261

Orientación 261 Ortoproyección 261

Ortofoto 260

P

Parámetros de orientación 262 Pre-procesamiento 293

Píxel 276 Proceso de autocalibración 248

Post-producción 293 Puntos de control 246

Precisión 244 Puntos homólogos 262

R

Reducción del número de
RBM (Range-Based Modelling) 267 triángulos 287

Reducción del número de
Reconstrucción virtual 284 zonas ocultas 288

Reconstrucciones 3D 284 Registro 271

Rectificación 263 Registro fotogramétrico digital 267

Recubrimiento 246 Rellenar los agujeros 288

Reducción del número de
polígonos 287 Relleno huecos 288

298

<!-- p. 308 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

Rendering fotorealistico 280 Resolución 280

Restitución
Renderización 280 estereofotogramétrica 265

Representación virtual 250 Ruido 288

Reproducción virtual 250

S

Sensor activo 268 Sensores de imagen 260

Sensor láser 265, 267 SIG 273

Sistemas de Información
Sensor pasivo 260 Arquitectónica (SIA) 273

Sensores 3D Activos 268 Subdivisión 286

Sensores de barrido láser 265, 267 Superficie rumorosa 289

T

Terrestre 247 Toma de datos 242

Textura 289 Topografía 272

Texturas del color 289 Tradicional 256

Texture mapping 290 Triangulación 271, 286

Texturización 277 Triangulación óptica 271

Tiempo de vuelo 270 Tridimensional 253

U

UAV 250 Unión de los puntos de escaneo 286

V

Verificación del modelo 294 Visualización 279

Virtual 257

Z

Zonas de sombra 287 Zonas ocultas 287

299

<!-- p. 309 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

Inglés

Términos Página Términos Página

3D acquisition piperline 242 3D laser scanner 265, 267

3D active methods 268 3D model triangles 282

3D capturing techniques 242 3D point clouds 268

3D data acquisition 242 3D 253

3D editing 280 Three-dimensional 253

3D imaging 258 3D triangular mesh 285

A

Accuracy 243 Alignment 271

Accurate 254 Analogical 264

Active 3D sensor 268 Analytical 265

Active range sensing 268 Autocalibration 249

Automated 3D modelling Active sensor 268 284
procedures
Automated procedures (“image
Additional Parameters (Aps)
262 matching”) 259

Aerial 247 Automatic camera calibration 249

Automatic image processing
Aerial imagery 275 methods 259

Aerial images 275

B

Baking 277 Bump mapping 278

C

CAD 291 Camera resectioning 247

Calibration 247 Classical 275

Camera 263 Close range photogrammetry (CRP) 276

300

<!-- p. 310 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

Close range stereo pairs 259 Computer Aided Desing 291

Coded Target 246 Control point 246

Collinearity 264 Correspondences across 246

Color 275 Crossing face 281

Color mapped 276 CW 270

D

Decimated 287 Digital Terrain Model 273

Degenerate edges 281 Digitalizzazione 250

Degenerate triangles 281 Digitizing 250

Degree of detail 252 Displaced subd 292

Digital 255 Displaced subdivision surface 279

Digital Image 275 Displacedment mapping 279

Digital Model 283 Displacement map 279

Digital photo modelling 284 Distortion 245

Digital reconstruction 284 DTM 273

Digital Surface Model (DSM) 282 Duplicate triangle 281

E

Exterior orientation parameters 262

F

Fast texture 289 Filtering 292

Fill holes 288 Focal length 264

G

Georeferenced point
Generation of cut section 280 cloud/mesh 274

Geographic Information System 273 Georeferenced position 274

301

<!-- p. 311 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

Geo-referencing 274 Ground terrain Model 274

GIS 273

H

High-Definition 254 High-resolution 254

Highly detailed 254 Homologous point 262

I

IBM (Image-Based Modelling) 258 Image-based 3D reconstruction 258

Image based surface
reconstruction 284 Image-based technique 258

Image matching 259 Inconsistent edges 281

Image overlapping 246 Interior orientation parameters 262

Image processing 259 Intrinsic camera parameters 262

Image survey 258 Iterative Closest Point (ICP) 252

Image-based 3D model 258

L

Laser Range Camera (LRC) 267 Levels of Detail (LOD) 252

Laser scan 265, 267 LiDAR 266

Laser Scanning 265, 267 Low detailed 254

Laser-based equipment 265, 267 Low-resolution 254

M

Mapped 277 Mesh model 282

Mathematical model 283 Mesh surface 285

Merge 286 Meshing 286

Mesh 285 Meshing of the 3D point cloud 286

Mesh editing 280 Mesurement 245

302

<!-- p. 312 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

Method Bundle Adjustment 249 Modelling 282, 284

Method Self-calibrating bundle
adjustment 249

N

Noise 288 Normal mapping 278

Non-mainfold face 281 NURBS 291

O

Occlusion 287 Orthographic images 261

Optimization 251 Orthoimage 261

Orientation 261 Orthophoto 260

Ortho photo creation 261

P

Pair of images 258 Pixel 276

Passive sensor 260 Pixel size 276

Passive technique 260 Point cloud alignament 272

Phase-shift distance 270 Point clouds 268

Photogrammetric image
processing methods 259 Point constraint 272

Photogrammetric surface
reconstruction 284 Point/triangles reduction 287

Photogrammetric survey 259 Polygonal model 282

Photogrammetry 257 Polygonal model generation 286

Photographs 260 Post processing 293

Photo-realistic 256 Post-processing 293

Photo-realistic perspective 280 Precision 244

Picture element 276 Pre-processing 293

Pipeline 250 Principal point offset 262

303

<!-- p. 313 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

Q

Quality texture 289

R

Range camera 268 Redundant face 281

Range device 268 Registration 271

Range image 268 Remeshing 293

Range images 258 Remove redundancies 292

Range map 242 Rendering 279

Raw data 245 Rendering 280

RBM 267 Resezione 261

Reality-based 3D modelling 258 Resolution 253

Reconstruct the 3D shapes 284 Retopology 293

Rectification 263 Reverse engineering process 251

Reduced model size 287 Reverse modelling 251

S

Sparse reconstruction form
Scanner 3D 265, 267 images 284

Scanner laser 265, 267 Stereoscopic 265

Structure-from-motion
Scanner phase-based 270 software (SFM) 258

Self-calibration 249 Subdivision 286

Self-calibration bundle
adjustment 249 Surface model 282

Shared 279 Surface normal 280

Smoothing 293 Survey 242

Space UV 291

T

304

<!-- p. 314 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

Target 246 Time Of Flight 270

Target coordinate system 246 TIN 286

Tecnología láser stripe 271 TOF 270

Terrestrial 247 Topography 272

Textel 276 Topological error 244

Texture 289 Total station 274

Texture map 290 Triangulation 271, 286

Texture mapping 290 Triangulation devices 271

Texturing 277

U

UAV 250 Unstable face 281

Uncertainty 244

V

Virtual 257 Visualization 279

virtual reconstruction 284

W

Wireframe 280 Workflow 250

Italiano

Términos Página Términos Página

3D laser scanner 265

A

Accuratezza 243 Aereo 247

Acquisizione dei dati 242 Allineamento 271

305

<!-- p. 315 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

Alta definizione 254 Analogica 264

Alto livello di dettaglio 254 Apparenza visiva 256, 289

Analitica 265 Auto-calibrazione 249

B

Bassa definizione 254

C

CAD 291 Chiusura di fori 288

Calibration and orientation data 248 Clasico 256

Calibration pattern 248 Collinealità 264

Calibrazione 247 Colore 275

Camera 263 Coppia Stereofotogrammetrica 265

D

Dati grezzi 245 Digitalización 250

Decimazione 287 Distanza focale 264

Digitale 255 distorsione 245

E

Edizione 3D 280 Errore topologico 244

F

Fase di acquisizione 242 Fotogrammi 260

Filtraggio 292 Fotomodellazione 258

Foto digitali 275 fotorealistico 256

Fotogrammetria 257

G

Geometric camera calibration 248 GIS 273

Georeferenziazione 274

306

<!-- p. 316 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

I

IBM (Image-Based Modelling) 258 Informazione cromática (RGB) 275

Image matching 259 Iterative Closest Point (ICP) 252

Immagine digitale 275

L

Lacune 287 Livello di dettaglio 252

LiDAR 266

M

Maglia 285 Modellazione 284

Maglia di poligoni 285 Modelli digitali 283

Mappa di rugosità 278 Modelli Digitali del Terreno 273

Modelli digitali di superfici
Mappatura 277 (MDS) 272

Mappatura del colore 276 Modelli Fotogrammetrici 3D 258

Mappe bump 278 Modellismo 282

Mappe delle normali 278 Modello a superfici 282

Mappe di differenza 279 Modello discreto 269

Mappe di scostamento 279 Modello geometrico 283

MDT 283 Modello HP (high-poly) 254

Mesh 285 Modello master 254

Method Bundle Adjustment 249 Modello matematico 283

Metodo proiettivo inverso 248 Modello numerico 283, 292

Misurazioni 245 Modello poligonale 282

N

Nube di punti non strutturata 269 NURBS 291

Nube di punti strutturata 269 Nuvola di punti 268

307

<!-- p. 317 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

Nuvola grezza 245

O

Orientamento 261 Ottimizzazione 251

Ortofoto 260

P

Parametri Addicionali (AP) 262 Post-elaborazione 293

Photogrammetric measurement 245 Precisione 244

Pipeline 250 Pre-elaborazione 293

Pixel 276 Punti omologi 262

Post procesamiento 293

R

Raddrizzamento 263 Reverse modelling 251

Radiometric calibration 248 Ricopertura 246

Rappresentazione matematica 283, 282 Ricoprimento 246

RBM 267 Ricostruzione virtuale 284

Registrazione 271 Rilevamento 242

Rendering 280 Rilievo 242

Resoluzione 253 Rilievo con sensori attivi 268

Restituzione 3D 259 Riprese 242

Restituzione virtuale 284 Rumore 288

S

Scansione 3D 267 Sensori 3D attivi 268

Scansioni allineate 272 Sensori attivi 268

Sensore passivo 260 Sensori di distanza 268

308

<!-- p. 318 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

Sistema di riferimento UV 291 Spigoli inconsistenti 280

Sistemi Informativi Geografici 273 Stazione totale 274

Sovraposizione delle prese 246 Stereoscopico 265

Spacio UV 291 Subdivisione 286

Spigoli degeneri 280 Superfici di suddivisione 279

T

target 246 Topografía 272

Tecniche di misura passiva 260 Triangolarizzazione 286

Tempo di volo 270 triangolazioni 271

terrestre 247 Triangoli degeneri 281

Tessitura 289 Triangoli duplicati 281

Texture mapping 290 tridimensionale 253

U

UAV 250

V

Variazione di fase 270 Visualizzazione 279

Virtuale 257

Z

Zone d’ombra 287

309

<!-- p. 319 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

G. ÍNDICE DE AUTORES

Para realizar este estudio terminológico ha sido importante hacer una selección de los autores
que eran apropiados estudiar, haciendo una selección en los campos objeto de estudio
(arquitectura, ingeniería y el patrimonio, dentro del levantamiento y la restitución de modelos en
3D) y en los tres idiomas que se contemplan en esta tesis (español, inglés e italiano). Por ello, se
ha hecho una breve descripción de cada uno de los autores, que permita una contextualización
general.

 BUILL POZUELO, Felipe52. Felipe Buill es doctor en Ingeniería del Terreno,
Cartográfica y Geofísica, profesor titular de Fotogrametría en la EPSEB, IngenieroTécnico
en Topografía, licenciado en Geografía y responsable del laboratorio de fotogrametría de la
EPSEB. Además es profesor en el Máster en Restauració de Monuments de la Universidad
Politécnica de Cataluña.

 CUELI LÓPEZ, Jorge Tomás53. Nacido en Unquera, Cantabria, es un ingeniero
industrial por la Escuela Técnica Superior de Ingeniería Industrial (ETSII) de la
Universidad de Valladolid. Trabaja en Punto Arquitectura, S.L.P., empresa que desde su
fundación se ha caracterizado por la creación de equipos multidisciplinares que den
respuesta a todas las facetas que en la actualidad plantean la construcción, rehabilitación y
patología de edificaciones. Está certificada en ISO 9.001 y 14.001 como Sistema de
Gestión Empresarial dirigidas al Estudio y Desarrollo de Proyectos Arquitectónicos,
Dirección de Obra y Coordinación de Seguridad y Salud. En ella, se ha desarrollado una
división dedicada a Project Management con actuaciones importantes en Cantabria. Al
mismo tiempo se potencia la fotogrametría arquitectónica, método mediante el cual son
capaces de proporcionar planos de cualquier edificio existente.

 DOCCI, Mario. Nacido en Siena, en el 1935, Adquiere el título de arquitecto por la
“Facoltà d’Architettura di Roma” en el 1962. Trabaja como arquitecto y urbanista en
Roma. Es profesor catedrático de la Facoltà d’Architettura dell’Università La Sapienza, en
la cual es Presidente del 1988 a septiembre del 2000. Además, enseña en la Scuola di
Specializzazzione in Restauro dei Monumenti (Escuela de Especialización en Restauración
de los Monumentos) en la misma universidad. Es Vicerrector de la Università La Sapienza
desde el año 1997 al 2000. Representante italiano en el “Comitato Consultivo CEE” para la
Profesión de Arquitecto desde el 1992 hasta la actualidad. Desarrolla actividad didáctica y
de investigación en colaboración con instituciones nacionales y extranjeras, coordinando
numerosos grupos de investigación. Es fundador y director de la revista “Disegnare, idee,
immagini”. Ha desarrollado una intensa actividad de investigación centrada sobre la
temática de la historia y la metodología del levantamiento, la historia de los métodos de
Representación, las problemáticas entre el diseño y proyecto, y, la proyectación

52 http://mrmbcn.net/equipo-docente-2/#.UgC0bJKNLzw (última visita: 13/12/2013)
53 http://www.worldphotogrammetry.com/sobre-nosotros/item/9-quienes-somos.html (última visita:
13/12/2013)

310

<!-- p. 320 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

arquitectónica y urbanistica. Siempre ha desarrolla su actividad profesional en el sector de
la proyectación arquitectónica y urbanística, pero desde hace muchos años su interés ha
prevalecido concentrado sobre la restauración arquitectónica y urbana. Es miembro de
diversas asociaciones culturales, entre ellas, “La Pontificia Accademia dei Virtuosi del
Pantheon”, y además, de algunas instituciones científicas, como “Consiglio Superiore dei
Lavori Pubblici” y “ASS.I.R.CO (Associazione italiana recupero e consolidamento
costruzioni)”. Ha escrito numerosos libros, entre ellos “Il rilevamento architettonico.
Storia, metodi e disegno” y “Manuale di rilievo architettonico e urbano”.54

 FANTINI, Filippo. Arquitecto por la Universidad Politécnica de Milán, desde el 2003.
Desde siempre activo en el ámbito de la investigación y de la formación sobre temas de
computer graphic, se ocupa de levantamiento y representación mediante el uso de nueva
tecnología que aplica en el campo de la tutela y la valorización de los Bienes Culturales.
Desde el 2004 colabora constantemente con el laboratorio de levantamiento del
Departamento de Proyección de la Arquitectura de la Università degli Studi di Firenze con
la cual participa en numerosas campañas de levantamiento finalizadas a la documentación
de sitios de particular interés histórico-artístico entre los cuales se encuentra: Villa Adriana
(Tívoli), Sperlonga (Latina), Massa Marittima (Grosseto) e Xian (Shanghái, China).
Profesor a contrato de Diseño Automático dentro del curso universitario en Diseño
Industrial de la Università degli Studi di Firenze en el 2005, gana el concurso de doctorado
de investigación en el sector científico disciplinar ICAR 17 en diciembre del mismo año.
Desde julio del 2009 a junio del 2011 es becario de la beca “Santiago Grisolia” en el
Instituto de Restauración del Patrimonio (IRP) de la Universidad Politécnica de Valencia
donde colabora con un grupo interdisciplinar de expertos en un proyecto financiado por la
Comisión Europea “ATHENA”. Desde octubre del 2011 pasa a la posición de contratado,
en calidad de “técnico superior” en el mismo instituto de la Universidad Politécnica donde
al mismo tiempo es involucrado en otros proyectos de cooperación internacional con
Marruecos (arquitectura de tierra) y Guatemala (arqueología Maya). Participa en
seminarios de estudio sobre temas de levantamiento digital y de museografía; edita
publicaciones y frecuenta los principales convenios internacionales sobre temas de
Patrimonio Cultural en relación al uso de las nuevas metodologías de representación.
Actualmente trabaja en el desarrollo de su tesis de doctorado en la Universidad Politécnica
de Valencia sobre el tema de la proyección de los lugares para el espectáculo en el mundo
antiguo, en particular sobre el teatro romano. Desde septiembre del 2013 es investigador a
tiempo determinado en la facultad de Ingeniería del “Alma Mater Studiorum di Bologna”
Campus de Ravenna.

54 www.zam.it/biografia_Mario_Docci y
http://gomppublic.uniroma1.it/Docenti/Render.aspx?UID=d800c29f-7bd7-4d7e-aee2-c2ef93388f94
(última visita: 13/12/2013)

311

<!-- p. 321 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

 GAIANI, Marco55. Marco Gaiani es un profesor catedrático de Design en la Facultad de
Ingeniería de la Universidad de Bolonia. Nace en Bolonia el 8 de febrero de 1960 y se
licencia en 1985 en Ingeniería Civil sección Edilicia con cum laude en la “Università degli
Studi di Bologna”. En 1989 se laurea como técnico en el “Istituto di Architettura e
Urbanistica dell'Università degli Studi di Bologna”. En 1993 se convierte en investigador
confirmado por el grupo disciplinar “H11X Disegno”, dentro de la Facultad de
Arquitectura de la “Università di Ferrara”. En 1999 entra como profesor asociado en el
área H11X-“Disegno” en la Facultad de Arquitectura Leonardo del Politécnico de Milán,
Departamento DITEC. El 1 de marzo del 2002 pasa a ser profesor extraordinario del sector
científico-disciplinar H11X (ICAR 17) - “Disegno” en la Facultad del Design del
Politécnico de Milano y profesor titular en marzo del 2005. En el año 2002-2003 es
Director vicario y más tarde (2003-2004) se convierte en Director del Departamento
INDACO (Departamento de Diseño Industrial, de las Artes, de la Comunicación y de la
Moda) del Politécnico de Milan. Del 1 de abril de 1993 al 31 de enero del 1999 es fundador
y responsable del centro de computer graphic de la Facultad de Arquitectura de la
Universidad de Ferrara. Miembro del Comité Directivo del Centro para la Gráfica
Informatizada del Centro Informático de Ateneo del Politecnico di Milano desde diciembre
del 1999. Fundador y responsable del Laboratorio de “Virtual Prototyping & Reverse
Modeling” del Politécnico de Milán desde el 2002. Especializado en la modelación digital
para la arquitectura y para el design, se ha empeñado en el último decenio, en el estudio y
en la optimización de métodos y sistemas para el levantamiento y la documentación de la
arquitectura histórica y moderna, de las obras de interés arqueológico y de la escultura y,
más recientemente, en el campo del virtual prototyping y el redering aplicado a la industria
del design y a la investigación sobre métodos didácticos de enseñanza de las técnicas de
representación digital tridimensional.

 GUIDI, Gabriele56. Gabriele Guidi es Profesor asociado de Design (ICAR/17) en la
Facultad de Design del Politécnico de Milán. Se licenció en Ingeniería en la Università
degli Studi di Firenze en febrero del 1988. Su experiencia nace en el mundo de la imagen
en el cual inició a hacer investigación en 1988. En julio del 1992 consigue el título de
Doctor de Investigación. En septiembre de 1994 vence un concurso para un puesto de
investigador en la Facultad de Ingeniería de la Universidad de Florencia. En 1998 recibe la
confirmación de Investigador. Desde 1999 orienta su investigación sobre temáticas con
relación al levantamiento tridimensional iniciando un estudio que acaba en el 2001 con la
terminación de una estancia como “Visiting Researcher” en el “Visual Information
Technology (VIT) Group del National Research Council Canada (Ottawa, Ontario),
reconocido como uno de los centros de referencia internacional en el sector del
levantamiento y del modelado tridimensional. Es autor de más de 100 publicaciones
nacionales e internacionales sobre técnicas de levantamiento tridimensional, sea con

55http://www.unibo.it/SitoWebDocente/default.htm?UPN=marco.gaiani%40unibo.it&TabControl1=TabC
V (última visita: 13/12/2013)
56http://guida.design.polimi.it/guida/2009/index.php/faculty_docenti/docente/5967 (última visita:
13/12/2013)

312

<!-- p. 322 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

métodos activos (escaneados láser), que con pasivos (fotogrametría). Se ha ocupado de
aplicaciones en el campo de los bienes culturales cuidando, entre otros, el modelado de
famosas estatuas de Donatelo incluso la Magdalena y el David de bronce. En el campo del
design ha introducido el levantamiento digital con integraciones de fotogrametría y escáner
láser.

 HAALA, Norbert57. Es doctor ingeniero, profesor adjunto y Diputado Director del
“Institute for Photogrammetry” de la “University of Stuttgart” (Alemania). En la actualidad
trabaja en las líneas de investigación de “Dense 3D Surface Reconstruction by Aerial
Image Matching”. (Métodos de Image matching usados para la reconstrucción 3D de
superficies a partir de imágenes aéreas), “Unmanned Airborne Systems/Vehicles
(UAS/UAV)” (Drone) y “Virtual City Models” (Modelos virtuales de la ciudad). Ha escrito
una gran cantidad de artículos sobre fotogrametría.

 KŘEMEN, Tomás58. Doctor ingeniero en la Facultad de Ingeniería Civil, Departamento de
Geodesia Especial de la Universidad de Praga (República Checa). Profesor de Topografía
en Ingeniería y de Levantamiento de Edificios.

 LERMA GARCÍA, José Luis59. José Luis Lerma es profesor de “Fotogrametría analítica”
y “Procesos digitales” en el Departamento de Ingeniería Cartográfica, Geodesia y
Fotogrametría (DICGF) adscrito a la Escuela Técnica Superior de Ingeniería Geodésica,
Cartográfica y Topográfica (ETSICGT) de la Universidad Politécnica de Valencia (UPV).
Es Ingeniero Técnico en Topografía desde el 1992 e ingeniero en Geodesia y Cartografía
desde el 1996. En 1999 obtiene el título de doctor en Geodesia y Cartografía. Es profesor
de fotogrametría en la Facultad de Gestión de la Información y Medio (Máster
Internacional en Geomática) de la Universidad de Ciencias Aplicadas Karlsruhe
(Alemania). Sus líneas de investigación son “Fotogrametría del objeto cercano”,
“Automatización de sistemas fotogramétricos digitales. Desarrollo de software”, “Análisis
termográficos en conservación y restauración”, “Integración de datos multiespectrales: UV,
visible, IR y LiDAR”, “Escaneado láser aerotransportado y terrestre”, “Generación de
ortoimágenes convencionales y verdaderas”, “Creación de entornos fotorrealísticos y
productos multimedia”, “Realidad virtual y visualización fotorrealística” y “Visualización
3D y animación de ciudades”. Ha publicado diversos libros sobre fotogrametría, y
diferentes artículos sobre fotogrametría y escáner láser.

 MAÑANA-BORRAZÁS, Patricia60. Licenciada en Historia en 1997 por Universidad de
Santiago de Compostela, con orientación curricular en Arqueología y Prehistoria.
Arqueóloga y especialista en registro geométrico del patrimonio. Técnica de investigación
en Instituto de Ciencias del Patrimonio (Incipit). Consejo Superior de Investigaciones

57 http://www.ifp.uni-stuttgart.de/institut/staff/haala_publikationen.htm (última visita: 13/12/2013)
58 http://k154.fsv.cvut.cz/~kremen/ (última visita: 13/12/2013)
59 http://jllerma.webs.upv.es/ (última visita: 13/12/2013)
60 http://csic.academia.edu/PatriciaMananaBorrazas/CurriculumVitae (última visita: 13/12/2013)

313

<!-- p. 323 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

Científicas (CSIC) en Santiago de Compostela desde enero de 2009, ejecutando tareas
concretas de documentación tridimensional del patrimonio cultural, empleando diversas
técnicas de registro: escáneres láser 3D, escáner de luz estructurada, fotogrametría, así
como diverso software de edición y modelado de los datos 3D para su representación.

 MURPHY, Maurice61. Profesor, Presidente Superior del programa Cert. Líneas de
investigación: “Building Conservation and new technology applications” (Conservación de
Edificios y aplicaciones de nueva tecnología), “Application of CD ROM andWEB design
for educational courseware in building technology” (la aplicación de CD ROM y diseño
web para cursos educativos en tecnología de la construcción), “Training and education in
building conservation” (formación y la educación en la conservación de Edicicios), “Laser
Scanning of existing buildings, BIM” (Escaneado láser de los edificios existentes, BIM)

 REMONDINO, Flabio. Estudia Ingeniería Medioambiental en el Politécnico de Milán
(1993-1998). En el 2006 obtiene el título de doctor en fotogrametría en Suiza. En el 2010,
realiza el post-doc en SOI unit, FBK Trento, Italia. A partir del 2010, se convierte en el jefe
de la unidad de investigación 3DOM, FBK Trento. Del 2000 al 2008, es “webmaster” en
ISPRS (International Society of Photogrammetry and Remote Sensing). En el 2002,
comienza a trabajar como delegado nacional de Suiza en CIPA (International Committee
for Documentation of Cultural Heritage), hasta el 2007. Del 2004 al 2008 trabaja como
Copresidente de WGV/4 “Virtual Reality and Computer Animation”. En el 2008, se
convierte en consejero ejecutivo del CIPA, y, en este mismo año, pasa a ser presidente del
WGV/4 “Imaged- and range-based 3D modelling” hasta el 2012. En el 2012, es nombrado
presidente del ISPRS Technical Commision V, cargo que durará hasta el 2016. También en
el 2012, es nombrado presidente de la Comisión Técnica I en EuroSDR. Sus ámbitos de
investigación son la fotogrametría, el escáner láser, el modelado 3D, el procesado de
imágenes y la teledetección (remote sensing). Ha realizado numerosas conferencias en
dichos ámbitos, organizado, además, diversos eventos científicos internacionales sobre
ello. Ha participado en diversos comités científicos, casi todos a nivel internacional y ha
escrito una gran cantidad de artículos, dirigiendo, además, algunas tesis doctorales, siempre
sobre el campo de la fotogrametría, el escáner láser y el modelado 3D.

 RIVEIRO RODRÍGUEZ, Belén62. Es licenciada en ingeniería estructural por la
Universidad de Vigo, e ingeniera en levantamiento terrestre y fotogrametría por la
Universidad de Newcastle. También ha estudiado en EEUU. Hoy es profesora e
investigadora en la Universidad de Vigo. Doctora por la Universidad de Vigo, con Mención
Europea (2011). Sus líneas de investigación son “Aplicación de las técnicas de medición
geomática con monitorización dimensional/estructural de obras de ingeniería civil”,
“Automatización dos procedimientos de inspección de infraestructuras en base a

61http://www.dit.ie/construction/departmentofconstructionmanagementtechnology/staff/ (última visita:
13/12/2013)
62 http://webs.uvigo.es/departamentot05/personalbelen.html (última visita: 13/12/2013)

314

<!-- p. 324 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

metodologías avanzadas para la parametrización geométrica y de comportamiento de los
materiales” y “Desenvoltura de sistemas de gestión de infraestructuras”.

 RODRÍGUEZ NAVARRO, Pablo63. Desde el año 1994 imparte docencia en el Dep. de
Expresión Gráfica Arquitectónica de la UPV, y en el 2000 inicia la docencia en una nueva
asignatura, “Fotografía”. Dos años después activa una nueva asignatura que se denominó
“Rectificación Fotogramétrica”. En el último Plan de estudios estas dos asignaturas se
adecuaron y avanzaron denominándose respectivamente “Tratamiento digital de la imagen”
y “Fotogrametría Arquitectónica”. En paralelo, y desde la creación del Máster Oficial CPA,
imparte la misma disciplina en la asignatura de “Metodologías y Técnicas de
Reconocimiento y Evaluación”. En cuanto a la parte investigadora, siempre ha estado
vinculada a la Fotografía y sus aplicaciones para el levantamiento gráfico. A principios de
los 2000 con el asesoramiento del prof. Pablo Navarro, monta el laboratorio de “Fotografía
y Fotogrametría” de la ETS de Ingeniería de Edificación. Será también el Prof. Navarro el
que lo introduzca en el mundo del escáner láser. Más tarde, en el año 2011, realizo una
estancia de investigación en la Facultad de Arquitectura de Florencia, en el grupo de la
prof. Emma Mandelli; un año después, realiza una nueva estancia de investigación, en el
Politécnico de Milán, en el grupo de investigación del prof. Gabriele Guidi, siendo en la
actualidad Profesor Visitante de ambas Universidades. En cuanto al ámbito internacional,
destaca su participación en el comité del VSMM 2012 (Milano) donde participa como
sesión chair de la sección de Patrimonio Arquitectónico; actualmente trabaja para Digital
Heritage 2013 (Marsella) dónde participará como Programm Comité. Trabaja para la
revista DISEGNARECON (Bolognia) donde es editor del número en curso que está
dedicado a los usos de la fotografía en el levantamiento llevando por título “Disegnare con
la fotografia digitale”. Si bien hasta ahora se ha dedicado a la investigación en
levantamientos 3D, realizando trabajos tanto en base fotogramétrica y obtención de nubes
de puntos a través del escáner láser, actualmente sus mayores intereses se centran en las
fases de “obtención, edición y aplicación” de las fotografías para su aplicación en los
modelos tridimensionales.

 SCOPIGNO, Roberto. Director de investigación en el CNR-ISTI (Consiglio Nazionale
delle Ricerche – Istituto di Scienza e Tecnologie dell’Informazione, Consejo Nacional de
las Investigaciones - Instituto de la Ciencia y Tecnología). Roberto gana la posición de
investigador en el CNR-CNUCE en 1986, convirtiéndose en Investigador Senior en 1997 y,
finalmente, en Director de investigación en el 2001 en el ISTI. Desde 1990 trabaja en el
Departamento de Ingeniería Informática y en el Departamento de Computer Science de la
Università di Pisa, donde imparte cursos de Computer Graphics. Ha sido investigador
visitante en la Universidad de Vigo y en la Universidad de California en Santa Cruz (USA).
Además, ha sido invitado para estancias cortas, seminarios y cursos de Doctorado en otras
universidades internacionales. Roberto ha sido nombrado coordinador de la acción de
investigación nacional sobre el Cultural Heritage & ICT (titulado en italiano “Fruizione e

63 Información aportada por Pablo Rodriguez.

315

<!-- p. 325 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

Valorazione del Patrimonio Culturale”), que es una de las seis actuaciones del “Cultural
Heritage Department”. Ha participado en varios proyectos de investigación (financiados
por la UE y agencias nacionales). Se ocupa de: modelado con datos de multiresolución y
rendering, Láser escáner 3D, reconstrucción de superficies, gráficos interactivos y realidad
virtual, visualización científica, e, interpretación del volumen. Cultural Heritage (CH) y
Computer-Aiede Medicine/Surgery (Patrimonio Cultural y Medicina asistida por
ordenador/ Cirugía) son los principales campos de aplicación para las metodologías y
tecnologías desarrolladas por él. Ha publicado más de ciento ochenta artículos en revistas,
conferencias y libros internacionales.64

64 http://vcg.isti.cnr.it/~scopigno/ (última visita: 13/12/2013)

316

<!-- p. 326 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

H. REFERENCIAS

 Alsadik, B., Remondino, F., Menna, F., Gerke, M. y Vosselman, G., 2013. “Robust
extraction of image correspondences exploiting the image scene geometry and approximate
camera orientation” en International Archives of the Photogrammetry, Remote Sensing and
Spatial Information Sciences, Volume XL-5/W1, 20133D-ARCH 2013 - 3D Virtual
Reconstruction and Visualization of Complex Architectures. 25 – 26 Febrero, Trento, Italy,
pp. 1-9.

 Amoruso, G., Apollonio, F.I. y Remondino, F. 2010. “Caratterizzazione strumentale di
sensori attivi a tempo di volo (ToF) e a triangolazione. Utilizzo di laser scanner su superfici
marmoree di epoca romana” en Benedetti, B., Gaiani, M. y Remondino, F. (ed.) Modelli
Digitali 3D in archeologia: Il caso di Pompei. Edizioni della Normale. Scuola Normale
Superiore Pisa, pp. 118-161.

 Apollonio, F.I., Baldissini, S., Manferdini, A.M., Remondino, F., 2010. “Rilievo 3D
nell’area archeologica di Pompei: risultati e considerazioni.” en Benedetti, B., Gaiani, M. y
Remondino, F. (ed.) Modelli Digitali 3D in archeologia: Il caso di Pompei. Edizioni della
Normale. Scuola Normale Superiore Pisa, pp. 270-307.

 Apollonio, F.I., Gaiani, M. y Manferdini, A.M., 2010. “Modellazione semantica. Metodi a
multirisoluzione” en Benedetti, B., Gaiani, M. y Remondino, F. (ed.) Modelli Digitali 3D
in archeologia: Il caso di Pompei. Edizioni della Normale. Scuola Normale Superiore Pisa,
pp. 236-269.

 Apollonio, F.I. y Remondino, F., 2010. “Modellazione 3D da sensori attivi Pipeline con
laser scanner” en Benedetti, B., Gaiani, M. y Remondino, F. (ed.) Modelli Digitali 3D in
archeologia: Il caso di Pompei. Edizioni della Normale. Scuola Normale Superiore Pisa,
pp. 94-117.

 Arbacea, L., Sonninob, E., Callieri, M., Dellepianec, M., Fabbrid, M., Idelsone, A.I.,
Scopigno, R., 2013. “Innovative uses of 3D digital technologies to assist the restoration of
a fragmented terracotta statue” en Journal of Cultural Heritage. Editorial Elsevier.Volume
14, Number 4, Julio – Agosto 2013, pp. 332-345.

 Baldissini, S., Gaiani, M. y Remondino, F., 2010. “Rilievo, gestione e mappatura del
colore” en Benedetti, B., Gaiani, M. y Remondino, F. (ed.) Modelli Digitali 3D in
archeologia: Il caso di Pompei. Edizioni della Normale. Scuola Normale Superiore Pisa,
pp. 200-235.

 Balzani, M., Ferrari, F. y Viroli, F., 2012. “La cittadella di Gozo a Malta. Strategie di
restauro e di valorizzazione del sistema di fortificazione maltese” en Actas de 16a
Conferenza Nazionale ASITA. Vicenza 6-9 novembre 2012, pp.107-114.

317

<!-- p. 327 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

 Battini, C., Fantini, F., 2007. “Clouds and clay. Superfici di suddivisione ed
ottimizzazione” en De Carlo, L. (ed.) Informatica e fondamenti scientifici della
rappresentazione. Editrice Gangemi. Roma, pp. 175-186.

 Bertocci, S., Bini, M., 2012. Manuale di rilievo architettonico e urbano. CittàStudi
Edizioni. Novara, Italia.

 Bianchini, C., 2007. “Laser scanning X” en Docci, M. (ed.) Metodi e tecniche integrate di
rilevamento per la costruzione e fruizione di modelli virtuali 3D dell'architettura e della
città. Gangemi editore, Roma, pp. 24-31.

 Biosca Taronger, J.M., Navarro Tarín, S. y Lerma García, J.L., 2007. Modelado
tridimensional de una bóveda barroca mediante la combinación de láser escáner y
fotogrametría, 7 Setmana Geomàtica, Febrero 20–23, Barcelona, España.

 Buill Pozuelo, F., Núñez Andrés, M.A. y Marambio Castillo, A. “Estudio de la calidad en
la medida con láser escáner.” Disponible en: http://www-
cpsv.upc.es/documents/SG7pap065.pdf. (última visita 13/12/2013)

 Buill, F., Nuñez, M.A., Rodríguez, J.J., 2007. La fotogrametría arquitectónica. Edición
UPC. Barcelona.

 Cannarozzo, Cucchiarini, Meschieri, 2012. Fotogrammetría. Misure, rilievo, progetto.
Volumen 3. Zanichelli editore S.p.A., Bolonia.

 Corsini, M., Dellepiane, M., Ganovelli, F., Gherardi, R. , Fusiello, A. & Scopigno, R.,
\2013. “Fully Automatic Registration of Image Sets on Approximate Geometry” en
International Journal of Computer Vision. Editorial Springer US. Volumen 102, Número
1-3, Marzo 2013, pp. 91-111.

 Cueli López, J., 2010. Cursos gratis de fotogrametría. Tutoriales Photomodeler.
Disponible en: http://www.worldphotogrammetry.com/home/itemlist/category/6-cursos-
gratuitos.html (última visita: 13/12/2013)

 Docci, M., Maestri, D., 1984. Il rilevamento architettonico. Storia, metodi e disegno.
Editori Laterza. Bari.

 Dore, C. y Murphy, M., 2012. “Integration of Historic Building Information Modelling
(HBIM) and 3D GIS for Recording and Managing Cultural Heritage Sites” en 18th
International Conference on Virtual Systems and Multimedia (VSMM). VSMM 2012
Virtual Systems in the Information Society. 2 - 5 Septiembre 2012 Milan, Italia, pp. 369-
\376.

318

<!-- p. 328 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

 Fantini, F., 2010. “Image Based Data Processing (IBDP): la restituzione attraverso
displaced subD a partire da rilevamento laser scanner” en Mandelli, E. y Velo, U. (ed.) Il
modello in architettura. Cultura scientifica e rappresentazione. Materia e Geometria.
Alinea Editrice. Florencia. pp. 1-10.

 Fantini, F., 2011. “La modellazione in Displaced sub-D. Modelli a dettaglio variabile da
scansione laser” en Verdiani, G. (ed.), Il ritorno all'immagine, nuove procedure image
based per il Cultural Heritage. Lulu.com, pp. 37-72. (última visita: 13/12/2013)

 Fantini, F., 2012. “Modelos con nivel de detalle variable realizados mediante un
levantamiento digital aplicados a la arqueología” en Revista EGA (Expresión Gráfica
Arquitectónica). Universidad Politécnica de Valencia. Valencia, pp. 306-217.

 Fantini, F., Rodríguez-Navarro, P. y Di Tondo, S., 2012. “Il problema della mappatura del
colore nei modelli digitali 3d a displaced subdivision surface da rilevamento laser scanner
in ambito archeologico” en Rossi, M. y Siniscalco, A., (ed.) Colore e colorimentria.
Contributi multidisciplinari. Vol. VIII A. Dip. Indaco. Politecnico di Milano, pp. 31-38.

 Guidi, G. y Remondino, F., 2012. “3D Modelling from Real Data” en Modelling and
Simulation in Engineering. Edited by Catalin Alexandru, InTech, 3 de Marzo, pp. 69-102.

 Guidi, G., Russo, M. y Angheleddu, D. 2013. “Digital reconstruction of an archaeological
site based on the integration of 3d data and historical sources” en International Archives of
the Photogrammetry, Remote Sensing and Spatial Information Sciences, Volume XL-5/W1,
2013 3D-ARCH 2013 - 3D Virtual Reconstruction and Visualization of Complex
Architectures, 25 – 26 Febrero, Trento, Italia, pp. 99-105.

 Guidi, G., Russo, M. y Beraldin, J.A., 2010. Acquisizione 3D e modellazione poligonale.
McGraw-Hill. Italia.

 Herráez Boquera, J., Navarro Esteve, P y Denia Ríos, JL., 2010. “Fundamentos y
aplicaciones de la tecnología de Escáner Láser para documentación y restauración del
patrimonio. Algunos ejemplos de aplicación en La Comunidad Valenciana” en Alcántara
Onofre, A., Lara Gutiérrez, A. M. (ed.) Implementación de nuevos métodos de
documentación y registro fotogramétrico digital para la protección y puesta en valor del
patrimonio monumental mexicano. Ciudad de México: Universidad Politécnica de
Valencia, pp. 17-41.

 Koska, B. y Křemen, T., 2013. “The combination of laser scanning and structure from
motion technology for creation of accurate exterior and interior orthophotos of St. Nicholas
Baroque church” en International Archives of the Photogrammetry, Remote Sensing and
Spatial Information Sciences, Volume XL-5/W1, 2013 3D-ARCH 2013 - 3D Virtual

319

<!-- p. 329 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

Reconstruction and Visualization of Complex Architectures, 25 – 26 Febrero, Trento, Italia,
pp. 133-138.

 Lerma, J.L., Navarro, S., Cabrelles, M. y Villaverde V., 2010. “Terrestrial Laser Scanning
and Close Range Photogrammetry for 3D Archaeological Documentation: the Upper
Palaeolithic Cave of Parpalló As a Case Study” en Journal of Archaeological Science 37.
Elsevier, pp. 499–507.

 Lerma, J.L., Cabrelles, M., Navarro, S., and Seguí, A.E., 2011. “La documentación
patrimonial mediante sensores de imagen o de barrido láser” en Documentación gráfica del
patrimonio, Ministerio de Cultura, pp. 108-117.

 Manferdini, A.M. y Remondino, F., 2010. “Modellazione 3D da immagini Perperline
fotogrammetrica” en Benedetti, B., Gaiani, M. y Remondino, F. (ed.) Modelli Digitali 3D
in archeologia: Il caso di Pompei. Edizioni della Normale. Scuola Normale Superiore Pisa,
pp. 162-199.

 Mañana-Borrazás, P., Rodríguez Paz, A. y Blanco-Rotea, R., 2008. “Una experiencia en la
aplicación del Láser Escáner 3D a los procesos de documentación y análisis del Patrimonio
Construido: su aplicación a Santa Eulalia de Bóveda (Lugo) y San Fiz de Solovio (Santiago
de Compostela)” en Arqueología de la arquitectura. 5 enero-diciembre, Madrid / Vitoria.
pp. 15–32.

 Marambio, A., Pucci, B., Nuñez, M.A. y Buill, F., 2009. “La aplicación del escáner láser
terrestre en la catalogación del patrimonio arquitectónico del casco histórico de Castellfollit
de la Roca” en VIII Semana Geomática Internacional, pp. 1-8.

 Marangoni, R. y Geddo, M., 1996. Le immagini digitali. Formati e gestione. Hoepli
Informatica. Milán.

 Merlo, A., 2007. “Dal “modelo” della città ai Sistemi Informativi Urbani: Sorana 3D” en
Docci, M. (ed.) Metodologie integrate per il rilievo, il disegno, la modellazione
dell’architettura e della città. Dipartimento di Storia, Disegno e Restauro dell’architettura.
Sapienza, Università di Roma. Gangemi Editore. Roma, pp.114-117.

 Migliari, R., 2012. “La Geometria descrittiva nel quadro storico della sua evoluzione dalle
origini alla rappresentazione digitale” en Carlevaris, L., De Carlo, L. y Migliari, R. (ed.)
Attualità della Geometria descrittiva. Seminario nazionale sul rinnovamento della
Geometria descrittiva. Sapienza Università di Roma. Roma, pp. 15-42.

 Remondino, F. y El-Hakim, S. (ed.), 2007. 2nd International Workshop "3D-ARCH'07" -
3D Virtual Reconstruction and Visualization of Complex Architectures, 12-13 July, ETH
Zurich, Suiza.

320

<!-- p. 330 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

 Remondino, F., Lo Buglio, D., Nony, N. y De Luca, L., 2012. “Detailed primitive-based 3d
modeling of architectural elements” en International Archives of the Photogrammetry,
Remote Sensing and Spatial Information Sciences, Volume XXXIX-B5. XXII ISPRS
Congress, 25 Agosto – 01 Septiembre 2012, Melbourne, Australia, pp. 285-290.

 Riveiro Rodríguez, B., Armesto González, J., González Jorge, H., Arias Sánchez, P., 2011.
Manual práctico para modelado 3D con escáner láser RIEGL LMS Z390 y software
RISCAN PRO. ETS de Ingenieros de Minas. Universidad de Vigo.

 Rodríguez Navarro, P., 2012. “La fotogrametría digital automatizada frente a los sistemas
basados en sensores 3D activos” en Revista EGA (Expresión Gráfica Arquitectónica).
Universidad Politécnica de Valencia. Valencia, pp.100-111.

 Thomas, D., Orland, K., Steinberg, S., 2007. The videogame style guide and reference
manual. Power Play Publishing, p. 62.

 Verdiani, G., 2003. Il battistero di Pisa, rilievo e rappresentazione digitale tra ricerca e
innovazione. Dottorato di ricerca. Rilievo e Rappresentazione dell’Architettura e
dell’Ambiente. XV Ciclo. Università degli Studi di Firenze. Florencia.

 Wenzel, K., Rothermel, M., Fritsch, D. Y Haala, N., 2013. “Image acquisition and model
selection for multi-view stereo” en International Archives of the Photogrammetry, Remote
Sensing and Spatial Information Sciences, Volume XL-5/W1, 2013 3D-ARCH 2013 - 3D
Virtual Reconstruction and Visualization of Complex Architectures, 25 – 26 Febrero,
Trento, Italia, pp. 251-258.

321

<!-- p. 331 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

CAPÍTULO 9. CONCLUSIONES

322

<!-- p. 332 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

A. CONCLUSIONES EN ESPAÑOL

La tesis se presenta, conforme a su estructura, como un documento dividido en dos partes:
una parte introductoria, compuesta por el abstract, la introducción y el estado del arte de los
sistemas de levantamiento innovadores actuales y de restitución; y una segunda parte que
supone el desarrollo en sí de ésta, compuesta por 4 casos de estudio y un capítulo de
terminología, que permiten una comparación lexical y un análisis detallado, en el ámbito de la
integración de los diferentes métodos de levantamiento con herramientas avanzadas y su
restitución.

El aporte de esta tesis tiene una doble naturaleza, por un lado una parte operativa y por el
otro una parte teórica. El desarrollo de ésta se presenta como un estudio detallado sobre la
modelación 3D a partir de la integración mediante diferentes técnicas avanzada de
levantamiento tridimensional. Los cuatro capítulos de casos de estudios son una parte aplicativa
que integra los diversos métodos de levantamiento, que permiten obtener modelos
tridimensionales con o sin textura, funcionales o no para operaciones de anastilosis, el mapeado
riguroso del color sobre ellos, el uso de la fotogrametría aérea a partir de UAV, pero que en todo
caso permiten una integración entre ellos. Aunque en algunos casos se realiza su comparación,
no es su finalidad, y esta comparación se realiza solo para comprobar la posible fusión de éstos
manteniendo el alto nivel de detalle que los caracteriza.

En el primero caso de estudio, se utilizan dos sistemas de levantamiento de diferente nivel de
precisión, pero de igual categoría (sensores activos), uno para objetos pequeños y otro para
objetos de mayor tamaño. Dicho uso, permite confrontar el uso de ambos para obtener un único
modelo 3D en el cual realizar todas las pruebas necesarias para el fin buscado, la anastilosis de
la bóveda. En el segundo caso de estudio, se realiza una comparación entre dos sistemas
diversos (sensores activos y pasivos) para analizar la posibilidad de esta unión formando un solo
modelo. En estos dos primeros casos, se le da una exclusividad al tema de la morfología,
descartando el interés por textura, no siendo relevante en ambos casos.

En el tercer caso de estudio, siguiendo en la vertiente de la integración, la forma pierde la
exclusividad dividiéndose con la textura, que cobra importancia. Este caso, además, tiene una
finalidad también funcional. Presenta como primer objetivo realizar una serie de
experimentaciones funcionales a una restauración: ejecutar las integraciones de las partes
faltantes de un fresco. Este objetivo, se utiliza, a su vez, como pretexto para efectuar diversas
experimentaciones sobre otros sistemas de levantamiento externos al escáner láser (herramienta
preponderante hasta el momento). Se emplean programas de foto-modelación para resolver el
problema de la textura de alta definición, en particular, el Agisoft Photoscan y el Eos Systems
PhotoModeler. Se usa, además, un programa de modelación 3D (fuera del campo del
levantamiento), Luxology Modo, unido a PhotoModeler, para la fase de proyección de
fotogramas.

Para el tema de la textura se prueban dos vías diversas, buscando una alta precisión
morfológica acompañada de una alta resolución cromática. Se debe aclarar que, si se marca
como único objetivo la integración a través de diseños bidimensionales, el uso del escáner láser

323

<!-- p. 333 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

es suficiente, pero si se presenta a su vez la necesidad de obtener una imagen de alta calidad
cromática, entra en juego la experimentación con técnicas de Image-based Modelling, por ser
este el camino considerado más adecuado para llegar a dicha finalidad.

La primera vía usada es aquella en la que el modelo se obtiene a partir de un levantamiento
con escáner láser y se utiliza el programa de fotogrametría solo para encontrar la posición
relativa de las cámaras con respecto al modelo, usando después programas de Reverse
Modelling para aplicarle la textura. El resultado a nivel morfológico es el mejor, ya que el
modelo proviene directamente del levantamiento mediante Range-based Modelling pero
presenta cierta discordancia en la textura, en las zonas de unión entre fotogramas. La segunda
vía, consiste en obtener todo el modelo (morfología y textura) mediante técnicas de Imagebased Modelling. Se usan programas como Agisoft PhotoScan o PhotoModeler, integrados o
separadamente, dando buenos resultados, sea sobre el perfil de la exactitud, pero sobre todo
desde un punto de vista de fiabilidad cromática.

De esta doble vía se consigue obtener un modelo de alta definición morfológica (a partir del
levantamiento con el escáner) y un modelo de alta definición cromática (mediante técnicas de
Image-based Modelling). ¿Dónde nace el límite? Para generar el desarrollo en 2D, con textura,
buscado de la bóveda (objetivo principal del caso de estudio), los programas que actualmente
están disponibles en el mercado no proporcionan soluciones simples. En consecuencia, visto
que el modelo tridimensional adecuado, morfológicamente hablando, para los restauradores es
el del escáner láser, se procede a una apertura manual. Considerando, a su vez, que en cualquier
modo, esta apertura manual, que se ha realizado al modelo de escáner láser se puede aplicar
también a cualquier modelo poligonal, siendo, sin embargo, una operación costosa, y no directa
y automatizada. El problema, por lo tanto, es la falta de automatización que, en este momento,
presentan algunos programas.

En el 4º caso de estudio, continuando con la experimentación de la integración con diversas
técnicas de levantamiento se introduce la innovación del drone, modelación mediante
fotogrametría aérea captada con UAV. Tanto en el 3 caso como en éste, se observa que el
programa Agisoft PhotoScan es una de las vías más eficaces por la automatización del proceso
usando técnicas de Image-based Modelling. Esta confirmación es importante, ya que pone en
evidencia que cuanto más automático es un proceso y menor la intervención, este proporciona
una fiabilidad mayor. El concepto es que si se introducen técnicas empíricas y se usan muchos
programas, quizás se obtiene un buen resultado, pero se deben usar diversos filtros y cambios de
formatos para la exportación e importación de los file. Todos estos pasajes introducen
alteraciones en el file original, que quizás van en la dirección adecuada si el objetivo es obtener
un buen modelo 3D mapeado, pero si nos quedamos solo en la parte de levantamiento, el
discurso cambia, porque se debe continuamente verificar las alteraciones introducidas con
respecto al dato original.

En este caso, tanto la fachada como la cubierta de la iglesia se obtienen mediante un proceso
automatizado generando un modelo texturizado en Agisoft PhotoScan 0.9.1., que como se
comprueba puede fácilmente integrarse con el modelo de escáner láser. También en este caso, la

324

<!-- p. 334 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

utilización de Agisoft PhotoScan demuestra su eficacia, tanto desde un punto de vista de la
calidad de la mesh como cromático. No sucede lo mismo con el programa Photomodeler, que
demuestra ser más costoso, presentando tiempos de procesado largos (time consuming)
combinados con un trabajo por parte del operador mayor, generando a su vez una mesh que si
bien permite un control puntual alto sobre el error, no es compensable con la calidad de la mesh,
no aceptable en comparación con la calidad morfológica que presentan el resto de los modelos
3D.

Por lo tanto, se puede decir, después de este conjunto de experiencias, independientemente
de la parte lexical, nomenclatura, etc., que cuanto más automatizadas son las soluciones, en
línea de máxima, mejores son, y más fácil la integración entre los modelos resultantes. El
aumento de operaciones manuales (como en el caso de la bóveda del Palacio Roncioni: tomar
los puntos en Rapidform, importarlos en Photomodeler, después re-proyectar el fotograma…),
genera un pipeline más largo y articulado, y no proporciona la precisión necesaria. Se puede
declarar, por lo tanto, que aunque el programa Photomodeler Scanner es un buen programa en
sí, cuando se trata de obtener modelos 3D, probado tanto en la iglesia como en el palacio
Roncioni, aunque permite un gran control en cada una de los pasos individuales, después, esta
capacidad de control no corresponde a una calidad de la restitución final, que sin embargo, para
nosotros es lo más importante, porque nos interesa la calidad topológica de los modelos. Una
alta calidad topológica de los modelos, permite una intervención más simple, una mayor
correspondencia de los modelos y, por lo tanto, una mejor integración entre ellos. Como ya se
ha dicho, la finalidad de la tesis no es analizar cuanto es mejor una técnica con respecto a otra,
sino como hacer dialogar estos tipos de tecnologías.

Con esta premisa, se puede afirmar que, aunque el interés del arquitecto, va siempre unido a
un estudio para obtener un conocimiento de la arquitectura, la intención del operador con un
objetivo de integración entre modelos puramente técnico y científico, es la búsqueda de
soluciones con una mayor eficacia productiva, considerando la posibilidad de que esta eficacia
presente ciertos límites. Uno de estos límites es, por ejemplo, la imposibilidad de programas
como el Agisoft PhotoScan de ver punto por punto cual es el error. La automatización
comentada, como una ventaja, presenta la desventaja, en algunos programas, de lo que algunos
expertos llaman la “black box” (caja negra), que no permite controlar los cálculos internos del
programa paso a paso. Sin embargo, se puede estudiar la calidad general del modelo, de la
textura, etc. Así, considerando la automatización general del proceso, se puede confirmar la
preferencia hacia estas soluciones, ya que no son solo más eficaces desde un punto de vista del
tiempo necesario sino también con respecto a la calidad del producto acabado, del modelo, que
es nuestro objetivo.

Analizando cada caso de estudio por separado se pueden declarar las siguientes afirmaciones
o conclusiones:

Del primer caso de estudio, “Restauración virtual: El caso de una bóveda gótica en Coves de
Vinromá”, se deduce que los modelos obtenidos a partir del escáner a triangulación y del
escáner TOF, pueden ser fusionados en un único modelo para permitir una reconstrucción

325

<!-- p. 335 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

virtual. En el momento en el que se realiza este caso de estudio, no se considera la
fotogrametría, pero debe comprenderse, también, que tratándose de un trabajo sobre arquitectura
gótica, sobre todo, sobre trazas, monteas y reconstrucciones formales, el interés sobre la textura
es mínimo. Así, se afirma que la fotogrametría no interesa, ya que existen tanto diversos
sistemas para obtener modelos cuya finalidad sea el aspecto topológico, sin tener en cuenta la
textura. En este caso de estudio, es importante el comprobar cómo es posible la integración
entre modelos obtenidos con dos sensores activos con diferente nivel de detalle. Estos dos
modelos independientes, convergen para ser filtrados con las técnicas propias de los análisis que
se hacen en el ámbito de la arquitectura, se usan los esquemas gráficos y proyectuales que se
utilizaban en el ámbito del gótico. Utilizando todo lo que ha llegado a través de los estudios de
las bóvedas de esa época y tipología, se analizan los datos obtenidos con el escáner. Partiendo
de diversos levantamientos, se integra todo en un único modelo para permitir hacer un
elaborado estudio analítico.

Como se comprueba en el resultado, efectivamente este único modelo permite obtener una
solución, difícilmente alcanzable sin esta tecnología de última generación. Estudiando la
arquitectura gótica y observando en general, la primera idea marcaba que la bóveda fuese un
casquete esférico. Sin embargo, gracias al levantamiento de pequeños objetos (las claves y las
dovelas) y su integración a un objeto mayor (la capilla) es posible comprobar que no es la
solución que cubría la capilla mayor de la iglesia. Esto permite demostrar la utilidad de la
integración de dos técnicas diferentes, escáner a triangulación y escáner TOF.

Toda la tesis se basa sobre este aspecto, la convergencia de los modelos obtenidos a partir de
diversas técnicas para permitir su integración y obtener un único modelo con la máxima
información y el máximo nivel de detalle posible (con o sin textura, con o sin superficies de
subdivisión, etc.). El objetivo principal es la conversión de todo en un único modelo 3D, desde
el cual en una segunda fase es posible realizar los diversos análisis que en cada momento
precisan los arquitectos. Para dicha conversión es necesario el uso de varios programas, ya que
como se ha comentado por ahora no es posible realizar todo el trabajo en un único programa.

326

<!-- p. 336 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

Tiempo de elaboración Range-based
Modelling

Rapidform XOR3 Luxology Modo Cyclone 7 Otros

10%
10%

20% 60%

Tiempo de elaboración Image-based
Modelling

Rapidform XOR3 PhotoModeler / PhotoScan Luxology Modo Otros

10%
40% 20%

30%

Figuras 9.01 y 9.02. Gráficos del tiempo de elaboración de las técnicas de Range-based Modelling y
Image-based Modelling.

El 2º Caso de estudio, “Anastilosis virtual de modelos adquiridos mediante escáner láser:
Piazza d’Oro dentro del Recinto Arqueológico de Villa Adriana (Tívoli, Roma)” combina los
dos métodos de levantamiento del primer caso, pero además introduce la innovación del uso de
Image-based Modelling (Agisoft PhotoScan) para la integración de los modelos realizados a
partir de Range-based Modelling. Este estudio, datando su comienzo a finales del 2010,
presenta en su momento un aspecto incoativo, ya que es uno de los primeros casos realizados.
En este caso, el objetivo principal se centra en el uso instrumental de Agisoft PhotoScan para
rellenar partes no detectables o partes que por la naturaleza misma de objeto no permiten un
buen levantamiento mediante un escáner a triangulación. El escáner a triangulación presenta
ciertas limitaciones, como el problema de la distancia, de la iluminación, del material o según la

327

<!-- p. 337 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

morfología del objeto. Como se ha podido comprobar, el escáner a triangulación presenta una
alta limitación debido a la distancia, requiere un rango de medición bastante marcado,
presentando problemas si la distancia se reduce o se aumenta fuera de cierta holgura permitida.
Por otra parte, este escáner también se ve influenciado por la iluminación, si ésta es demasiado
alta, los resultados son en algunos casos la absoluta ausencia de algunas zonas levantadas. El
material también se convierte en una limitación cuando éste no es totalmente opaco, como en el
caso del vidrio o el mármol, ya que la reflectancia de los rayos emitidos por el escáner es
diferente, no permitiendo realizarse una buena captura de la señal remitente. En el caso de la
morfología, se hace evidente una buena respuesta en el caso de objetos con relieves,
presentando, al contrario, problemas en la fase de alineamiento cuando el objeto exhibe partes
demasiado planas. El Agisoft PhotoScan demuestra ser una solución óptima para resolver estos
problemas y también en casos en los que la falta de detalles del objeto hace innecesario la
inversión de tiempo que necesita el escáner, presentándose la fotogrametría como la opción más
adecuada.

Alejándonos, sin embargo, del detalle podemos concluir, que en los dos primeros casos, el
objetivo principal es la forma; entender diversas cosas sobre un objeto que ya no está presente.
En estos dos casos, sirven los modelos integrativos, reconstructivos, pero no la textura, por lo
que las técnicas de Image-based Modelling son únicamente utilizadas como integración. Con
esto se pretende decir, que el uso de esta tecnología no es tan imprescindible, ya que se podría
haber usado un escáner ToF, eligiendo una densidad alta, en las zonas que presentaban
problemas al escáner a triangulación y el resultado habría sido el mismo.

Entendiéndose esto, se puede decir que los resultados son bastante positivos porque el tipo
de error que se obtiene es bastante limitado, pudiendo resolverse mediante instrumentos de
modelación, en programas de reverse modelling, mediante “smooting” aplicado a las partes de
superposición que no salen exactamente iguales.

En las otras dos experiencias no se muestra esta presencia del análisis desde un punto de
vista de la interpretación. Los dos primeros casos son estudios más formales. Sin embargo, en el
caso 3º, “Integración de frescos: Bóveda con frescos del Palacio Roncioni”, es justo que se
considere que se parte de exigencias profesionales dentro del campo de la restauración. En este
caso, se mantiene un cierto interés por la forma, pero cobra un alto protagonismo el color, la
forma interesa junto al color. El objetivo final, en este caso, es el de obtener grandes tablas
impresas, que sirvan como base para trabajar los restauradores. Por lo tanto, en este estudio la
forma es importante pero pierde la exclusividad, debido a la alta importancia del color.
Centrándonos en el problema, se presume que actualmente no existe un software que realice el
desarrollo en 2D de la bóveda de un modo automático, ya que si bien existen soluciones, en fase
de experimentación, sobre la conversión de un modelo mesh a una versión bidimensional con la
textura, por ej. la parametrización (llamado comúnmente en los programas de “entertainment”
los UVmapping), estos no son exactamente la solución al problema presente.

Con esta base, se realiza un estudio, basándose en la forma. Se analiza la tipología de las
bóvedas, superficies compuestas generalmente de cilindros o conos, y mediante el uso de las

328

<!-- p. 338 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

propiedades geométricas, se obtiene un desarrollo. Para el levantamiento se utiliza
fundamentalmente el escáner TOF, con colorización del punto: el punto viene caracterizado del
RGB y su reflectancia. También se realiza una campaña fotográfica destinada a una restitución
fotogramétrica.

En el empleo de programas de fotogrametría se utilizan dos vías diferentes, como ya se
comentaba, por un lado el uso integrado para la obtención de la geometría y de la forma con dos
programas de foto-modelación, Agisoft PhotoScan y Photomodeler, de los cuales haremos
valoraciones más adelante, y por otro, un sistema para aplicar la textura siempre unido a
Photomodeler con un uso estrictamente unido a la operación de “alineación” de la cámara
fotográfica, con el fin de encontrar los parámetros de orientación de la cámara. Esta segunda vía
tiene como fin re-proyectar los fotogramas, con un sistema que se encuentra en los programas
de modelación, y con ello, obtener una textura, fundamentalmente a partir de una imagen. Este
sistema realiza el desarrollo del modelo mediante una UVmap, obtenida en el programa Modo
(programa que pertenece al sector del Enterteinment).

Las conclusiones que se pueden hacer sobre este caso específico están unidas a una
fiabilidad que ha sido comprobada en el lugar. A través de la impostación de planos dentro de
un programa de gestión de los datos del escáner láser, Leica Cyclone, se obtiene un desarrollo
manual. El tipo de levantamiento realizado incluye el color y la reflectancia de la luz, por lo
tanto mediante una discretización de la superficie continua sobre estos planos es posible obtener
un resultado extremamente fiable con respecto al perfil métrico del desarrollo. No se puede
decir lo mismo del aspecto cromático, ya que es bastante decadente. Se puede afirmar que, a día
de hoy, el escáner no da un resultado satisfactorio en los casos en los que prevalece la
importancia del color. La resolución y la calidad de los fotogramas, capturados mediante
máquinas fotográficas posicionadas dentro el escáner, es muy baja. Algunos escáneres presentan
también la posibilidad de introducir una cámara externa, o sea, hacer un levantamiento y reproyectar la imagen, pero aun así las soluciones no muestran la calidad esperada. Sin embargo,
la situación es diversa cuando dentro del campo de la modelación geométrica, sobre la
superficie se decide aplicar una imagen. Esta vía es más eficaz porque, aunque se debe trabajar
más (tiene una fase manual de UV mapping, etc.), tiene bajo control mucho más la calidad, el
resultado final.

Desde el punto de vista funcional, para los restauradores, el desarrollo de la bóveda en 2D a
partir de la mesh obtenida con el escáner láser, es suficiente, considerando que con ello ya es
posible obtener todos los perfiles y los límites de los frescos que la adornan, permitiendo esta
operación de integración. Sin embargo, si se quiere aprovechar dicho levantamiento para tener
una documentación del fresco de alta calidad, esto no es posible. Pensando en dicha posibilidad,
se aprovecha este caso de estudio para realizar las prueban que permiten incluir en un modelo de
alta calidad morfológica, una alta calidad cromática.

Buscando este modelo con alta resolución cromática, se prueban dos programas de Imagebased Modelling, Photomodeler y Agisoft PhotoScan. Ambos dan buenos resultados pero
presentan ciertas diferencias. En el perfil operativo, el programa Photomodeler presenta el

329

<!-- p. 339 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

problema de que para seguir la resección de la foto-cámara, o lo que es lo mismo, para encontrar
los parámetros de los que se hablaba previamente, útiles para la proyección de las fotos sobre el
modelo, la operación es larga, y compleja, presentando a su vez el inconveniente de que los
resultados no son de alta calidad: aunque presenta un alto aspecto estético no se puede decir lo
mismo del aspecto métrico de la re-proyección.

Por lo tanto, dadas las pruebas realizadas, y apoyándonos en los resultados especificados en
el caso de estudio 3, se puede afirmar que, siguiendo un desarrollo de este modelo con las fotos
re-proyectadas (haciendo el baking etc.), además de ser una vía más fatigosa, es una vía que no
permite obtener suficiente exactitud.

Por otra parte, por cuanto concierne a los dos modelos obtenidos con PhotoModeler y
Agisoft PhotoScan, para la obtención no solo de la estructura de la escena (el network de la fotocámara) sino también para la generación del modelo, los dos programas no dan los mismos
resultados.

Agisoft PhotoScan es la solución que, a pesar de ser casi fundamentalmente automatizada, no
permitiendo una intervención, o un conocimiento puntual, como PhotoModeler Scanner (que
permite estudiar punto por punto los errores), y desde un cierto punto de vista en contraposición
a un estudio que se ponga como objetivo el análisis de la precisión morfológica, al mismo
tiempo, en la integración entre modelos, éste permite obtener una mesh más limpia y, en
consecuencia, una textura de calidad mayor. Este programa, además, presenta una mejor
combinación entre los fotogramas individuales, una mayor homogeneización del color y una
mayor calidad de la mesh a nivel morfológico.

Hasta aquí se puede, por lo tanto, afirmar, que el escáner es el método más eficaz, ya que
toma además de la posición de los puntos en el espacio, el color, que aunque no es un color
fiable al 100%, presenta una reflectancia que varía según la transición de la pintura de los
colores claros y oscuros, mostrando una reflectancia diversa1, y siendo una solución automática,
en la que en una sola captura se obtiene toda la información, no influyendo acciones intermedias
como puede ser la re-proyección (asociación entre punto en el espacio y pixel en los fotogramas
obtenidos de la foto-cámara). Como solución automática se puede considerar también el Agisoft
PhotoScan, ya que para la generación del modelo es necesaria solamente la impostación de un
mínimo conjunto de parámetros. Además, en las últimas versiones permiten también obtener
una fiabilidad mayor gracias a la introducción de un nuevo comando, “optimización”, que tiene
en cuenta los parámetros internos de la cámara, obtenidos a través de un gran número de
imágenes que hacen de red como sucede en el PhotoModeler Scanner en la fase de alineación
(también llamada fase de registro).

Una carencia que se encuentra, por ejemplo, en estos programas de Image-based Modelling
es la ausencia de instrumentos que permitan colocar planos de las posiciones que conocemos

1 Es importante aclarar que para el tema de la restauración, en efecto, es suficiente con la reflectancia ya
que documenta exactamente la forma definida del fresco sobre la superficie de la bóveda, pero no sería
así si se busca la documentación del fresco en su color original.

330

<!-- p. 340 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

exactamente, como los reference plane de Leica Cyclone 7. No hay instrumentos de desarrollo.
Sí que presentan instrumentos de UVmapping, pero estos instrumentos, en todo caso, son
diversos con respecto a un desarrollo que pueda servir a un restaurador.

Por último, en el cuarto caso de estudio, “Nueva herramienta para el levantamiento de
cubiertas: Iglesia San Miniato en Marciana (Cascina, Pisa)” se introduce una nueva herramienta,
el drone, la foto-modelación a partir de fotogrametría aérea. Para trabajar las fotografías
capturadas desde el UAV, se prueban dos programas, como en el caso de estudio precedente.
También en este caso, se observa que la calidad y la resolución de la mesh obtenida en las zonas
comunes capturadas con el escáner a Tiempo de Vuelo (ToF) y mediante las técnicas de Imagebased Modelling no son comparables. Sin embargo, comparando los dos modelos obtenidos
mediante Image-based Modelling, el resultado, al igual que en el caso de la bóveda del Palacio
Roncioni, es el mismo, la calidad de la mesh a nivel morfológico y topológico es superior en el
modelo obtenido con Agisoft PhotoScan. Se debe comentar que este programa, aunque aún
presenta ciertas limitaciones de control interno y es susceptible de mejoras, ha sufrido una gran
evolución durante el ámbito temporal del desarrollo de la tesis. Ha cambiado y crecido
muchísimo, permitiendo en el último caso de estudio conseguir un modelo de alta calidad
morfológica y cromática. Mientras en un primer momento permitía solo producir modelos para
hacer render, o sea, como una función accesoria, ahora, sin embargo, se ha convertido en una
herramienta potente capaz de generar modelos que permiten una integración con los datos del
escáner. (Por ej. La antigua versión de Agisoft PhotoScan no exportaba nubes densas, la nueva
si, y por lo tanto da la posibilidad de exportarlas a programas como Leica Cyclone 7,
permitiendo combinar elaborados extremamente precisos). Como se ha visto antes, para la
restauración del color, en los frescos, esta puede ser la solución, proyectar la información
cromática de la versión de Agisoft PhotoScan a la nube de puntos del escáner. Además, permite
confrontar datos que provienen de instrumentación diversa, como escáner láser terrestre, UAV,
etc.

La integración de modelos, y consecuentemente, de las técnicas de modelación, es
fundamental, y resulta, por lo tanto, importante, sea para el análisis de carácter arquitectónico
que para aquel que están unido a técnicas de intervención, como en el caso de la bóveda
principalmente.

La introducción del drone es importante para las técnicas de intervención, pero sobre todo es
importante porque introduce una nueva posibilidad para el levantamiento en zonas no accesibles
o de difícil accesibilidad (ej. La cubierta). Otra ventaja del drone, es la posibilidad a nivel de
seguridad en la obra, como por ejemplo si es necesario hacer un levantamiento de una iglesia en
ruinas tras un terremoto. Entre ir una persona a hacer el levantamiento y utilizar un UAV, la
elección es clara, tanto a nivel económico como “social”, ya que el uso de máquinas es cada vez
más rentable mientras que la intervención de personas siempre incluye un gasto en seguros que
aumenta notablemente el precio, si se quiere analizar desde un punto de vista económico,
dejando de lado el punto de prevención y seguridad de riesgos laborales.

331

<!-- p. 341 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

La diferencia entre modelos basados en técnicas de Image-based Modelling y Range-based
Modelling se ha reducido notablemente, ya que la fiabilidad de los modelos realizados con el
primer tipo está muy unida a la capacidad de una persona de estructurar apropiadamente el
network (la posición de las diferentes cámaras respecto al objeto). Desde este punto de vista, el
drone, ha supuesto un gran avance, ya que permite eliminar uno de los problemas más
frecuentes, presente siempre que se efectúa un levantamiento de elementos cercanos, las
capturas en el plano vertical. Un ejemplo claro son las casas, con una cámara es posible captar
esencialmente un plano horizontal, se puede intentar hacer una zona más amplia usando el
zoom, pero en definitiva se obtiene un plano de desarrollo del objeto esencialmente horizontal.
Por ello la fiabilidad de este levantamiento será muy elevada en la parte inferior y mucho menor
en la superior. En el caso del drone, el network tiene una cierta flexibilidad mayor, da la
posibilidad de documentar el objeto desde varias partes y, en consecuencia, aumentar la
capacidad. Permite acercar el levantamiento fotogramétrico al del escáner láser, integrándolo.

Cerrando las conclusiones particulares de cada caso de estudio, se afirma que en general, la
integración es el futuro, no solo en el ámbito de la modelación 3D, sobre la cual buena parte de
la tesis está girando, sino en el acercamiento entre programas de fotogrametría y aquellos que
sirven para el tratamiento de datos del láser escáner. De tal modo que, la profesionalidad de
programas de fotogrametría que trabajan en modo extremamente automatizado, nos permitan
obtener no solo datos de alta calidad para permitir una buena integración con el láser escáner,
sino también que permitan una absoluta combinación.

Se puede comprender esta tesis, además, como una evolución que va desarrollándose al
mismo tiempo que los programas que van apareciendo y por lo tanto las técnicas de
modelización. El programa Agisoft PhotoScan pasa de ser una herramienta de Computer Vision
(para uso visivo más que técnico) a un programa que genera modelos comparables con los del
escáner. La restitución en 3D, también va sufriendo una evolución en la tesis, que pasa de un
interés centrado únicamente en la forma (ya que el tema del color presenta aún demasiados
problemas2) a un interés por la restitución total que genere modelos similares a la realidad,
modelos tridimensionales de alta resolución en forma y color. Hoy, gracias a la implementación
de sistemas siempre más avanzados, se combina la posibilidad de mantener la ventaja de la
automatización y la posibilidad de generar modelos donde a la alta resolución morfológica se le
suma la alta resolución cromática. Esto es un aspecto importante, ya que se puede pensar que,
en un futuro inmediato, se presente como solución, una metodología bastante útil basada en la
realización de modelos fotogramétricos y modelos láser escáner juntos. De manera tal que se
pueda obtener los beneficios de los dos a la vez, la potencialidad mejor de uno y del otro:
escáner láser para la forma y las técnicas de Image-based Modelling para el color.

Esta tesis, se ve altamente influenciada por el transcurso del tiempo: la evolución y el paso
del tiempo son la clave. Años atrás la fotogrametría era una solución concerniente solo a los
expertos de topografía. Hoy, con estos sistemas, se ha convertido en algo más cercano y fuera
de un ámbito tan específico, los topógrafos han dado soluciones en las que el programa hace

2 Ver las actas de Conferenza Nazionale del colore, Florencia, 19-20 Septiembre 2013 y Conferenza
Nazionale del colore, Roma, Septiembre 2011.

332

<!-- p. 342 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

casi todo en automático. Evidentemente, esto no solo interesa a los arquitectos sino que
interesará también a aquellos que vienen del otro sector, el de la ingeniería. Es importante
señalar, que los desarrolladores de los programas están escuchando las peticiones que vienen de
ambos sectores. En la actualidad la fotogrametría ha vuelto a tomar un puesto relevante dentro
del levantamiento de bienes culturales, algo que no sucedía pocos años atrás3. Los
desarrolladores de software han demostrado la voluntad de dar a las personas que trabajan en el
sector de la geomática o de la fotografía, instrumentos que de alguna manera compensen, la ya
comentada “black box”, que supone el no saber exactamente el trabajo interno del programa. Se
sabe que tienen sistemas de reconocimiento de la forma, que calcula los parámetros de la
cámara, etc., pero mientras en el PhotoModeler Scanner es mostrado todo de forma explícita, no
es el caso de programas como Agisoft PhotoScan. Sin embargo, se ve una continua evolución,
en la que cada vez son más los datos proporcionados para permitir hacer un levantamiento
certificado en el que se pueda controlar cuales son los errores que vienen realizados por dichos
programas.

Se puede afirmar que, por un lado, el beneficio de los sensores activos es innegable, pero al
mismo tiempo la profesionalización o la mejora cualitativa de los programas de fotogrametría
está permitiendo unir estos dos modelos en modelos que en cualquier caso sintetizan al máximo
la calidad bajo el perfil de la medida y del color.

Sin embargo, una de las cuestiones actualmente abiertas en la investigación es la de
proporcionar a los desarrolladores de software la idea de introducir en los programas
instrumentos fiables para los objetivos de los restauradores. Los programas de Reverse
modelling nacen para satisfacer las exigencias de ingenieros o diseñadores, Agisoft PhotoScan o
Photomodeler Scanner, la de los topógrafos, pero a partir de este estudio se comprueba que aún,
en este momento, existen carencias en los programas para las necesidades específicas que
presentan los restauradores. A lo largo de los diferentes casos de estudio, se comprueba, en
diversas ocasiones, los problemas debidos a la necesidad de exportar e importar por no
encontrar en un único programa las herramientas que permitirían realizar todo el proceso, desde
el levantamiento mediante fotografías o escáner láser hasta la restitución final del modelo.

Así se puede concluir que con este conjunto de experiencias se va siguiendo, a su vez, la
evolución y las mejoras que van surgiendo en el mundo de levantamiento y la restitución.
Además, se puede afirmar que también la terminología, es muy importante, porque el
vocabulario de los arquitectos (que son los que se dedican principalmente a la construcción de
modelos 3D) se está acercando, en un aspecto más profesional, a estos instrumentos, cosa que
antes ocurría menos.

La cuestión terminológica ha sido afrontada con la voluntad de efectuar una comparación
lexical entre los 3 idiomas. Como se comenta en la introducción de la tesis, apoyado por
diferentes expertos del campo, se ha observado una carencia de paridad en el uso del lenguaje
técnico que usan los expertos en el campo del levantamiento y la restitución en 3D.
Observándose continuamente esta falta de igualdad y uniformidad en los términos, se presenta

3 Conferencia de Remondino en Corso MICMAC, Politecnico di Torino. 3 - 6 febrero 2014.

333

<!-- p. 343 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

en el último capítulo de la tesis un estudio de la terminología específica, en la que se comparan
términos y permite marcar en los 3 idiomas un concepto y los términos que se utilizan para
referirse a él. Con este capítulo se pretende aportar una homogeneidad en la terminología no
obtenida hasta ahora en dicho ámbito, y comentada por diversos autores (Amoruso, G.,
Apollonio, F.I., Remondino, F., 2010, Guidi y Remondino, 2012).

B. CONCLUSIONES EN ITALIANO (CONCLUSIONI)

La tesi si presenta conformemente alla sua struttura, come un documento diviso in due parti:
una parte introduttiva, composta dall’abstract, l’introduzione e lo stato dell'arte dei sistemi di
rilievo innovativi attuali e di restituzione; e una seconda parte contenente lo sviluppo di essa,
con quattro casi di studio e un capitolo di terminologia, che permette una comparazione
lessicale e un’analisi dettagliata, nell’ambito dell’integrazione dei diversi metodi di rilievo con
strumenti avanzati e la loro restituzione.

Il contributo di questa tesi ha una duplice natura, una parte operativa e un'altra teorica. Lo
sviluppo di quest’ultima si presenta come uno studio dettagliato di modellazione 3D, a partire
dall’integrazione mediante differenti tecniche avanzate di rilievo tridimensionale. I quattro
capitoli di casi di studio sono una parte applicativa che integra i diversi metodi di rilievo, che
permettono di ottenere modelli tridimensionali con o senza texture, funzionali o meno per
operazioni di anastilosi, la mappatura rigorosa del colore su di essi e l'uso della fotogrammetria
aerea a partire da UAV. Ognuno di questi casi, seppur in modo diverso, consente l'integrazione
tra i vari metodi di rilievo. Sebbene in alcuni casi il confronto si realizza tramite comparazione,
la sua finalità non è questa, perchè questo confronto viene eseguito solo per verificare
l'eventuale fusione di essi per mantenere elevato il livello di dettagli che li caratterizza.

Nel primo caso di studio si utilizzano due sistemi di rilievo con differente livello di
precisione ma di medesima categoria (sensori attivi), uno per oggetti piccoli e l’altro per oggetti
di dimensioni maggiori. Questo studio permette di confrontare l’uso di entrambi i sistemi per
ottenere un unico modello 3D nel quale realizzare tutte le prove necessarie per il fine ricercato:
l’anastilosi della volta. Nel secondo caso di studio, invece, si realizza una comparazione tra due
sistemi diversi (sensori attivi e passivi) per analizzare le possibilità di un’unione formando un
solo modello. In questi primi due casi, si dà un’esclusività al tema della morfologia, scartando
l’interesse per la texture che in entrambi i casi non è rilevante.

Nel terzo caso di studio, dal punto di vista dell’integrazione, la forma perde la sua esclusività
dividendosi con la texture che acquista importanza. Questo caso, inoltre, ha anche una finalitá
funzionale. Presenta come primo obiettivo la realizzazione di una serie di sperimentazioni
funzionali su una restaurazione: effettuare le integrazioni delle parti mancanti di un affresco.
Questo obiettivo si utilizza allo stesso tempo come pretesto per effettuare diverse
sperimentazioni su altri sistemi di rilievo estranei allo scanner laser (strumento predominante
fino a questo momento). Si utilizzano programmi di foto-modellazione per risolvere il
problema della texture di alta definizione, in particolare vengono utilizzati: Agisoft Photoscan,

334

<!-- p. 344 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

ed Eos Systems PhotoModeler. Viene anche usato un programma di modellazione 3D (fuori dal
campo del rilievo) chiamato Luxology Modo unito a PhotoModeler per la fase di proiezione dei
fotogrammi.

Per quanto riguarda la texture si tentano due percorsi diversi, cercando di ottenere un’alta
precisione morfologica accompagnata da un’alta risoluzione cromatica. Si deve chiarire che, se
si insegue come unico obiettivo l’integrazione attraverso il disegno bidimensionale, l’uso dello
scanner laser è sufficiente, però se si presenta a sua volta la necessità di ottenere un’ immagine
di alta qualità cromatica entra in gioco la sperimentazione con le tecniche di Image-based
Modelling, in quanto questo percorso è il più appropriato per raggiungere tale obiettivo.

Il primo percorso seguito è quello in cui il modello si ottiene a partire da un rilievo con
scanner laser e si utilizza il programma di fotogrammetria solo per individuare la posizione
relativa delle telecamere rispetto al modello, usando successivamente programmi di Reverse
Modelling per poter applicare la texture. Il risultato a livello morfologico sarà dunque migliore,
perchè il modello proviene direttamente dal rilievo mediante Range-Based Modelling ma
presenta una certa discordanza nella texture nella zona di unione tra i fotogrammi. La seconda
strada consiste nell’ottenere tutto il modello (morfologia e texture) mediante tecniche di ImageBased Modelling. Per questo si usano programmi come Agisoft Photoscan o Photo Modeler,
integrati tra loro o separatamente, dando buoni risultati, sia sul profilo dell'accuratezza, ma
soprattutto dal punto di vista dell'affidabilità cromatica.

Da questo doppio percorso si riesce a ottenere un modello ad alta definizione morfologica
(dal rilievo con il laser scanner) e un modello ad alta definizione cromatica (utilizzando tecniche
di Image-based Modelling). Dove nasce il limite? Per generare lo sviluppo in 2D (con texture)
cercato della volta (obiettivo principale del caso di studio), i programmi che sono attualmente
disponibili sul mercato non forniscono soluzioni semplici. Di conseguenza, dato che il modello
tridimensionale adeguato, morfologicamente parlando, per i restauratori è quello del laser
scanner, si procede all’apertura manuale. Considerando, allo stesso tempo, che in ogni caso,
questa apertura manuale che è stata fatta sul modello di laser scanner è applicabile a qualsiasi
modello poligonale, essendo tuttavia un'operazione costosa, e non diretta e automatizzata. Il
problema dunque è la mancanza di automazione che in questo momento presentano alcuni
programmi.

Nel quarto caso di studio , continuando con la sperimentazione dell’integrazione con varie
tecniche di rilievo, viene introdotta l’innovazione del drone (modellazione da fotogrammetria
aerea catturata da UAV). Sia nel terzo caso che in questo, si osserva che il programma Agisoft
PhotoScan è uno dei modi più efficaci per l’automatizzazione del processo utilizzando tecniche
di Image-based Modelling. Questa conferma è importante, poiché dimostra che quanto più
automatico è un processo meno lo è l’intervento e questo offre una maggiore affidabilità. Il
concetto è che se vengono introdotte tecniche empiriche e utilizzati molti programmi, si può
ottenere un buon risultato, ma è necessario utilizzare diversi filtri e modifiche del formato per
l'esportazione e l'importazione dei file. Tutti questi passaggi causano delle alterazioni al file
originale, che possono andare nella giusta direzione se l'obiettivo è quello di ottenere un buon

335

<!-- p. 345 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

modello 3D mappato, ma il discorso cambia se rimaniamo solo nella parte del rilievo, poiché si
devono continuamente verificare le alterazioni introdotte ai dati originali.

In questo caso, sia la facciata sia il tetto della chiesa sono ottenuti attraverso un processo
automatizzato generando un modello texturizzato da Agisoft PhotoScan 0.9.1., che, come si
verifica, può essere facilmente integrato con il modello di scanner laser. Anche in questo caso,
l'uso di Agisoft PhotoScan dimostra la sua efficienza, sia dal punto di vista della qualità della
mesh che dal punto di vista cromatico. Non succede così con il programma Photomodeler, che
risulta essere più costoso, presentando lunghi tempi di elaborazione (time consuming) combinati
con un maggiore lavoro da parte dell'operatore, e generando allo stesso tempo una mesh che
anche se permette un alto controllo puntuale sull’errore, non compensa con la sua qualità, e ciò
non è accettabile in confronto alla qualità morfologica che presentano gli altri modelli 3D.

Pertanto si può dire, dopo questa serie di esperienze, qualunque sia la parte lessicale,
nomenclatura, ecc., che le soluzioni più automatizzate sono in linea di massima le migliori, ed è
più facile l’integrazione tra i modelli risultanti. L’aumento di operazioni manuali (come nel caso
della volta del Palazzo Roncioni: prendere i punti in Rapidform, importarli in Photomodeler, poi
ri-progettare il fotogramma...), genera una pipeline più lunga e articolata, e non fornisce la
precisione necessaria. È possibile dichiarare quindi, che, anche se il programma Photomodeler è
un buon programma in sé, quando si tratta di ottenere modelli 3D, testati sia nella chiesa che
nel Palazzo Roncioni, anche se permette un grande controllo in ciascuna delle fasi individuali,
in seguito, questa capacità di controllo non corrisponde a una qualità della restituzione finale,
che tuttavia, per noi è la più importante, perché ci interessa la qualità topologica dei modelli.
Un’alta qualità topologica dei modelli, permette un semplice intervento, una migliore
corrispondenza dei modelli e, di conseguenza, una migliore integrazione tra loro. Come già
detto, lo scopo della tesi non è analizzare quanto sia meglio una tecnica rispetto ad un'altra, ma
come far dialogare questi tipi di tecnologie.

Con questa premessa, si può affermare che, sebbene l'interesse dell’architetto, sia sempre
legato a uno studio per ottenere una conoscenza dell'architettura, l'intenzione dell'operatore con
un obiettivo di integrazione tra modelli puramente tecnici e scientifici, è quello di trovare
soluzioni con una maggiore efficienza produttiva, considerando la possibilità che questa
efficienza abbia effettivamente dei limiti. Uno di questi limiti è, per esempio, l'incapacità di
programmi come Agisoft PhotoScan di vedere punto per punto qual è l’errore. L'automazione ,
riportata come vantaggio, ha lo svantaggio, in alcuni programmi, quello che alcuni esperti
chiamano la " black box" (scatola nera), di non permettere di controllare i calcoli interni del
programma passo dopo passo. Tuttavia, si può studiare la qualità complessiva del modello, della
texture, ecc. Pertanto, considerando l'automazione globale del processo, si può confermare una
preferenza per queste soluzioni, poiché sono non solo più efficaci dal punto di vista del tempo
richiesto, ma anche per quanto riguarda la qualità del prodotto finito, ill modello, che è il nostro
obiettivo.

Analizzando ogni caso di studio separatamente si possono dichiarare le seguenti
affermazioni o conclusioni:

336

<!-- p. 346 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

Dal primo caso di studio, "Restauro virtuale: Il caso di una volta gotica in Coves de
Vinromá", si deduce che i modelli ottenuti dallo scanner a triangolazione e dallo scanner TOF,
possono essere uniti in un unico modello per consentire una ricostruzione virtuale. Nel
momento in cui viene realizzato questo caso di studio, la fotogrammetria non viene considerata,
ma si dovrebbe anche comprendere che, essendo un lavoro sull'architettura gotica, specialmente
su tracce, battute ed ricostruzioni formali, l’interesse sulla texture è minimo. Quindi, si afferma
che la fotogrammetria non interessa, dato che ci sono tanti sistemi per ottenere modelli la cui
finalità sia l'aspetto topologico, a prescindere dalla texture. In questo caso di studio, è
importante dimostrare come sia è possibile l'integrazione tra modelli ottenuti con due sensori
attivi con diverso livello di dettaglio. Questi due modelli indipendenti, convergono per essere
filtrati con le tecniche proprie delle analisi che si effettuano nel campo dell'architettura, vengono
utilizzati gli schemi grafici progettuali che si utilizzavano nell’ambito del gotico. Usando tutto
ciò che è arrivato attraverso gli studi delle volte di questo periodo e tipologia, si analizzano i
dati ottenuti con lo scanner. Sulla base dei vari rilievi, si integra il tutto in un unico modello per
consentire uno elaborato studio analitico.

Come si può vedere nel risultato, effettivamente questo unico modello permette di ottenere
un esito difficilmente raggiungibile senza questa tecnologia di ultima generazione. Studiando
l’architettura gotica e osservando in generale, la prima idea indicava che la volta fosse un
casquete sferico. Tuttavia, grazie al rilievo di piccoli oggetti (le chiavi e i segmenti di arco) e la
loro integrazione in un oggetto più grande (la cappella) è possibile verificare che non è la
soluzione che copriva il presbiterio della chiesa. Questo permette di dimostrare l'utilità dell’
integrazione delle due diverse tecniche, scanner a triangolazione e scanner TOF.

L'intera tesi si basa su questo aspetto, la convergenza dei modelli ottenuti partendo da
diverse tecniche per permettere la loro integrazione e ottenere un unico modello con il massimo
di informazioni e massimo livello di dettaglio possibile (con o senza texture, con o senza le
superfici di suddivisione, ecc). L'obiettivo principale è quello di convertire tutto in un unico
modello 3D, dal quale in una seconda fase, è possibile realizzare le varie analisi che in ogni
momento richiedono gli architetti. Per questa conversione è necessario l’uso di diversi
programmi, poiché come si è discusso finora non si può fare tutto il lavoro con un unico
programma.

337

<!-- p. 347 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

Tempo di elaborazione Range-based
Modelling

Rapidform XOR3 Luxology Modo Cyclone 7 Altri

10%
10%

20% 60%

Tempo di elaborazione Image-based
Modelling

Rapidform XOR3 PhotoModeler / PhotoScan Luxology Modo Altri

10%
40% 20%

30%

Figure 9.03 y 9.04. Grafici del tempo di elaborazione nel caso di Range-based Modelling e Image-based
Modelling.

Il secondo caso di studio, "Anastilosi virtuale di modelli acquisiti da scanner laser: Piazza d'
Oro nel Sito Archeologico di Villa Adriana ( Tivoli , Roma)" combina i due metodi di rilievo
del primo caso, ma introduce anche l'innovazione dell’utilizzo di Image-based Modelling
(Agisoft PhotoScan) per l'integrazione di modelli realizzati da Range -based Modelling. Questo
studio, il cui inizio risale alla fine del 2010 , presenta allo stesso tempo un aspetto innovativo,
poiché è uno dei primi casi realizzati. In questo caso, l'obiettivo principale è l'uso strumentale di
Agisoft PhotoScan per riempire parti non rilevabili o parti che per la natura stessa dell'oggetto
non consentono un buon rilievo mediante uno scanner a triangolazione. Lo scanner a
triangolazione presenta alcune limitazioni, come il problema della distanza, dell’illuminazione,
del materiale o della morfologia dell'oggetto. Come si è potuto verificare, lo scanner a

338

<!-- p. 348 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

triangolazione presenta una alta limitazione dovuta alla distanza, richiede un intervallo di
misurazione piuttosto marcato, presentando problemi se la distanza si riduce o aumenta oltre
una certa ampiezza consentita. Inoltre, questo scanner è influenzato anche dall’illuminazione, se
è troppo alta, i risultati sono in alcuni casi la totale mancanza di alcune aree di rilievo. Il
materiale diventa anche una limitazione quando non è completamente opaco, come nel caso del
vetro o del marmo, poiché la riflettanza dei raggi emessi dallo scanner è diversa, non
permettendo di eseguire una buona cattura del segnale mittente. Per la morfologia, si fa evidente
una buona risposta nel caso di oggetti con rilievi , mostrando, al contrario, problemi nella fase di
allineamento quando l’oggetto esibisce parti troppo piatte. L’Agisoft PhotoScan dimostra essere
una soluzione ottimale per risolvere questi problemi e anche nei casi in cui la mancanza di
particolari dell'oggetto rende non necessario l'investimento di tempo di cui ha bisogno lo
scanner, presentandosi la fotogrammetria come l'opzione più appropriata.

Allontanandoci, tuttavia, dal particolare si può concludere che nei primi due casi, lo scopo
principale è la forma; capire diverse cose su un oggetto che non è più presente. In questi due
casi, servono i modelli integrativi, ricostruttivi, ma non la texture, essendo le tecniche di Imagebased modelling unicamente usate come integrazione. Questo vuol dire che l'uso di questa
tecnologia non è essenziale, poiché si sarebbe potuto utilizzare uno scanner TOF, scegliendo
una alta densità, nelle aree che presentavano problemi con lo scanner a triangolazione e il
risultato sarebbe stato lo stesso.

Capendo questo, si può dire che i risultati sono molto positivi, perché il tipo di errore che si
ottiene è piuttosto limitato, potendosi risolvere con strumenti di modellazione, in programmi di
reverse modelling, attraverso "smooting" applicati alle parti sovrapposte che non appaiono
esattamente uguali.

Nelle altre due esperienze non si mostra questa presenza dell’analisi dal punto di vista
dell'interpretazione. I primi due casi sono studi più formali. Tuttavia, nel terzo caso,
"Integrazione di affreschi: Volta affrescata del Palazzo Roncioni", è lecito supporre che si parte
dai requisiti professionali richiesti nel campo del restauro. In questo caso, rimane un certo
interesse per la forma, ma il colore la fa da protagonista, la forma interessa insieme al colore.
L'obiettivo finale, in questo caso, è quello di ottenere grandi tabelle stampate, che servano come
base per lavori di restauro. Pertanto, in questo studio, la forma è importante ma perde
l’esclusività a causa della elevata importanza del colore. Concentrandosi sul problema, si
presume che non esiste attualmente alcun software che esegue lo sviluppo 2D della volta in
modalità automatica, poiché anche se ci sono soluzioni in fase di sperimentazione, sulla
conversione di un modello mesh in una versione bidimensionale con la texture, per es. la
parametrizzazione (comunemente chiamato nei programmi di "entertainment" UVmapping),
questi non sono esattamente la soluzione al problema presente.

Su questa base, viene eseguito uno studio, basato sulla forma. Si analizza la tipologia delle
volte, superfici generalmente composte di cilindri o coni, e utilizzando le proprietà geometriche,
si ottiene uno sviluppo. Per il rilievo è principalmente utilizzato lo scanner TOF, con

339

<!-- p. 349 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

colorazione del punto: il punto è caratterizzato dal RGB e dalla sua riflettanza. Viene eseguita
anche una campagna fotografica per la restituzione fotogrammetrica.

Nell'impiego dei programmi di fotogrammetria vengono seguiti due percorsi differenti, come
già osservato, da una parte l’uso integrato per avere la geometria e la forma con due programmi
di fotomodellazione, Photomodeler e Agisoft PhotoScan, dei quali si farà la valutazione in
seguito, e dall'altra, un sistema per applicare la texture unita sempre a Photomodeler con un uso
strettamente legato alla fase di "allineamento" della fotocamera, al fine di trovarne i parametri di
orientamento. Questo secondo percorso è finalizzato al riprogetto dei fotogrammi, con un
sistema che si trova nei programmi di modellazione, e ad ottenere così una texture
prevalentemente a partire da un'immagine. Questo sistema esegue lo sviluppo del modello
attraverso una Uvmap, ottenuta nel programma Modo (programma appartenente al settore del
Enterteinment).

Le conclusioni che possono essere fatte in questo caso specifico sono collegate a una
affidabilità che si è dimostrato sul posto. Attraverso l'impostazione di piani all'interno di un
programma di gestione dei dati del laser scanner, Leica Cyclone, si ottiene un sviluppo manuale.
Il tipo di rilievo eseguito comprende il colore e la riflettanza della luce, pertanto attraverso una
discretizzazione della superficie continua su questi piani è possibile ottenere un risultato
altamente affidabile rispetto al profilo metrico di sviluppo. Non si può dire lo stesso dell’aspetto
cromatico, poiché è molto decadente. Possiamo dire che ad oggi, lo scanner non dà risultati
soddisfacenti nei casi in cui l'importanza del colore prevale. La risoluzione e la qualità dei
fotogrammi, catturati dalle macchine fotografiche posizionate all'interno dello scanner, è molto
bassa. Alcuni scanner hanno anche la possibilità di introdurre una fotocamera esterna, cioè, fare
un rilievo e riproiettare l'immagine, ma anche così le soluzioni non mostrano la qualità attesa.
Tuttavia, la situazione è diversa quando nel campo di modellazione geometrica, si decide di
applicare un'immagine sulla superficie. Questo percorso è più efficace perché, anche se è
necessario più lavoro (ha una fase di mappatura UV manuale, ecc.), ha molto di più sotto
controllo la qualità: il risultato finale.

Dal punto di vista funzionale, per i restauratori, lo sviluppo della volta in 2D dalla mesh
ottenuta con lo scanner laser è sufficiente, considerando che con esso è già possibile ottenere
tutti i profili e i limiti degli affreschi che la adornano, permettendo questa operazione di
integrazione. Tuttavia, se si vuole approfittare di questo rilievo per avere una documentazione
degli affreschi di alta qualità, ciò non è possibile. Pensando a questa possibilità, questo caso di
studio viene utilizzato per eseguire i test che permettono di includere in un modello di alta
qualità morfologica, un alta qualità cromatica.

Cercando questo modello con alta risoluzione cromatica, si testano due programmi di Imagebased modelling: Photomodeler e Agisoft PhotoScan. Entrambi funzionano bene, ma hanno
alcune differenze. Nel profilo operativo, il programma Photomodeler presenta il problema che
per seguire la resezione della fotocamera, o per dire lo stesso, per individuare i parametri di cui
si è parlato in precedenza utili per la proiezione delle immagini sul modello. L'operazione è
lunga e complessa, presentando allo stesso tempo l’inconveniente che i risultati non sono di

340

<!-- p. 350 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

elevata qualità, poiché anche se ha un notevole aspetto estetico non si può dire lo stesso
dell'aspetto metrico della riproiezione.

Pertanto, date le prove realizzate, e basandosi sui risultati specificati nel terzo caso di studio,
possiamo dire che, seguendo uno sviluppo di questo modello con le foto riprogettate (facendo il
baking, ecc.), oltre ad essere un percorso più faticoso, è un percorso che non consente di
ottenere abbastanza accuratezza.

Inoltre, per quanto riguarda i due modelli generati con Photomodeler e Agisoft PhotoScan,
per ottenere non solo la struttura della scena (il network delle macchine fotografiche), ma anche
per la generazione del modello, i due programmi non danno gli stessi risultati.

Agisoft PhotoScan è la soluzione che, pur essendo quasi prevalentemente automatizzata, non
permettendo alcun intervento, o di ottenere informazioni puntuali come fa Photomodeler (che
consente di studiare gli errori punto per punto), e da un certo punto di vista in contraposizione a
uno studio che si pone come obiettivo l’analisi della precisione morfologica, allo stesso tempo,
nella integrazione tra modelli, permette una mesh più pulita e, conseguentemente, una texture di
qualità superiore. Questo programma presenta anche una migliore combinazione tra i singoli
fotogrammi, una maggiore omogeneizzazione del colore e una migliore qualità della mesh a
livello morfologico.

Finora si può quindi affermare che lo scanner è il metodo più efficace, poiché prende la
posizione dei punti nello spazio, e anche il colore, che pur non essendo un colore affidabile al
100%, ha un riflettanza che varia con il passaggio della pittura dai colori chiari e scuri
(mostrando una riflettanza diversa4) ed essendo una soluzione automatica, in cui con una sola
cattura tutte le informazioni vengono raccolte, non influenzate da azioni intermedie come la
riproiezione (associazione tra punto nello spazio e pixel nei fotogrammi ottenuti dalla
fotocamera). Come soluzione automatica si può anche considerare l’Agisoft PhotoScan, poiché
per la generazione del modello è necessaria solo l’impostazione di un set minimo di parametri.
Inoltre, le versioni più recenti consentono anche di ottenere una maggiore affidabilità, grazie
all'introduzione di un nuovo comando, "ottimizzazione", che tiene conto dei parametri interni
della camera, ottenuti attraverso un gran numero di immagini che fanno da rete come accade nel
PhotoModeler nella fase di allineamento (detta anche fase di registrazione).

Una carenza che si trova, per esempio, in questi programmi di Image-based Modelling è la
mancanza di strumenti per permettere di introdurre piani delle posizioni che conosciamo
esattamente, come i reference plane di Leica Cyclone 7. Non ci sono strumenti di sviluppo.
Hanno sì strumenti di UVmapping, ma questi, in ogni caso, sono differenti rispetto ad uno
sviluppo che può servire a un restauratore.

Infine, nel quarto caso di studio, "Nuovo strumento per il rilievo di coperture: Chiesa di San
Miniato a Marciana (Cascina, Pisa)" viene introdotto un nuovo strumento, il drone, la foto-

4 È importante chiarire che per il tema del restauro, infatti, è sufficiente la riflettanza poiché documenta
esattamente la forma definita dell’affresco sulla superficie della volta, ma non sarebbe così se si cerca la
documentazione dell’affresco nel suo colore originale.

341

<!-- p. 351 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

modellazione da fotogrammetria aerea. Per elaborare le fotografie catturate dal UAV, vengono
testati due programmi, come nel caso di studio precedente. Ancora una volta, si osserva che la
qualità e la risoluzione della mesh ottenuta nelle aree comuni catturate dallo scanner a tempo di
volo (TOF) e attraverso le tecniche di Image-based Modelling non sono comparabili. Tuttavia,
confrontando i due modelli ottenuti mediante Image-based Modelling, il risultato, come nel caso
della volta del Palazzo Roncioni, è la stessa: la qualità della mesh a livello morfologico e
topologico è superiore nel modello ottenuto con Agisoft PhotoScan. Si deve commentare che
questo programma, anche se presenta alcune limitazioni di controllo interno ed è suscettibile di
miglioramento, ha subìto una grande evoluzione nel periodo di sviluppo della tesi. É cambiato e
cresciuto enormemente, permettendo in quest'ultimo caso di studio di ottenere un modello di
alta qualità morfologica e cromatica. Mentre in un primo momento permetteva solo di produrre
modelli per fare rendering, cioè, come un ruolo accessorio, ora, , è diventato un potente
strumento in grado di generare modelli che permettono l'integrazione con i dati dello scanner.
(Es. La vecchia versione di Agisoft PhotoScan non esportava nuvole dense, la nuova sì, e quindi
dà la possibilità di esportarle in programmi come Leica Cyclone 7, consentendo di combinare
elaborati estremamente accurati). Come visto in precedenza, per il restauro del colore negli
affreschi, questa potrebbe essere la soluzione: progettare le informazioni cromatiche della
versione di Agisoft PhotoScan nella nuvola di punti dello scanner. Inoltre, permette anche di
confrontarsi con i dati provenienti da strumenti diversi, come laser scanner terrestre, UAV, ecc.

L'integrazione di modelli, e di conseguenza, delle tecniche di modellazione, è essenziale, ed
è quindi importante, sia per l'analisi di carattere architettonico che per coloro che sono collegati
a tecniche di intervento, come principalmente nel caso della volta.

L'introduzione del drone è importante per le tecniche di intervento, ma è particolarmente
importante perché introduce una nuova possibilità per il rilievo in zone non accesibili o di
difficile accesso (ad esempio, la copertura). Un altro vantaggio del drone, è la possibilità a
livello di sicurezza nella costruzione, come per esempio se bisogna fare un rilievo di una chiesa
in rovina dopo un terremoto. Tra mandare una persona a fare il rilievo e utilizzare un UAV, la
scelta è chiara, sia economicamente che come "sociale", poiché l'uso delle macchine è sempre
più redditizio, mentre l’intervento delle persone comprende sempre la spesa per l'assicurazione
che aumenta in modo significativo il prezzo, se si vuole analizzare da un punto di vista
economico, lasciando da parte la questione della sicurezza e la prevenzione dei rischi
professionali.

La differenza tra modelli basati su tecniche di Image-based Modelling e Range-based
Modelling si è notevolmente ridotta, in quanto l'affidabilità dei modelli realizzati con il primo
tipo è strettamente legata alla capacità di una persona di strutturare correttamente il network (la
posizione delle diverse fotocamere rispetto all'oggetto). Da questo punto di vista, il drone è stato
un avanzamento importante perché elimina uno dei problemi più comuni, presente ognivolta che
viene effettuato un rilievo di elementi vicini: le catture nel piano verticale. Un chiaro esempio
sono le case, una macchina fotografica è in grado di catturare essenzialmente un piano
orizzontale, si può provare a fare una zona più ampia utilizzando lo zoom , ma in definitiva
viene ottenuto un piano di sviluppo dell’oggetto sostanzialmente orizzontale. Pertanto,

342

<!-- p. 352 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

l'affidabilità di questo rilievo sarà molto alta nella parte inferiore e molto meno in quella
superiore. Nel caso del drone, il network ha una flessibilità maggiore, offre inoltre la possibilità
di documentare l'oggetto da più parti, e quindi di aumentarne i dettagli. Consente di avvicinare il
rilievo fotogrammetrico a quello dello scanner laser, integrandolo.

Chiudendo i risultati particolari di ciascun caso di studio, si afferma che, in generale,
l'integrazione è il futuro, non solo nel campo della modellazione 3D, attorno a cui gran parte
della tesi ruota, ma nell’avvicinamento tra i programmi di fotogrammetria e quelli che servono
per il trattamento dei dati di scansione laser. In modo che, la professionalità dei programmi di
fotogrammetria che lavorano in modo estremamente automatizzato, ci permettano non solo di
ottenere dati di alta qualità per consentire una buona integrazione con il laser scanner, ma
permettano anche una combinazione assoluta.

Si può intendere questa tesi, inoltre, come un’evoluzione che va sviluppandosi nello stesso
tempo che vanno apparendo i programmi e quindi le tecniche di modellazione. Il programma
Agisoft PhotoScan passa per essere uno strumento di Computer Vision (per un uso visivo più
che tecnico) a un programma che genera modelli comparabili con quelli dello scanner. La
restituzione in 3D, subisce anch’essa un’evoluzione nella tesi, che passa da un interesse
focalizzato esclusivamente sulla forma (poiché il tema del colore presenta ancora troppi
problemi5) a un interesse per la restituzione totale che genera modelli simili alla realtà: modelli
tridimensionali ad alta risoluzione di forma e colore. Oggi, grazie alla realizzazione di sistemi
sempre più avanzati, si combina la capacità di mantenere il vantaggio dell’automazione e la
possibilità di generare modelli dove all’alta risoluzione morfologica si aggiunge l’elevata
risoluzione cromatica. Questo è un aspetto importante, poiché si può pensare che, in un futuro
molto vicino, si presenti come una soluzione: una metodologia molto utile bassata nella
realizzazione di modelli fotogrammetrici e modelli di scanner laser insieme. Al fine di ottenere i
vantaggi di entrambi allo stesso tempo, il migliore potenziale di uno e del'altro : scanner laser
per la forma e le tecniche di Image-based Modelling, per il colore.

Questa tesi è fortemente influenzata dal passaggio del tempo: l'evoluzione e il trascorrere del
tempo sono fondamentali. Anni fa la fotogrammetria era una soluzione riguardante solo esperti
di topografia. Oggi, con questi sistemi, è diventata qualcosa di più vicino e al di fuori di un
campo tanto specifico: i topografi hanno dato soluzioni in cui il programma fa quasi tutto
automaticamente. Ovviamente, questo non è solo di interesse per gli architetti, ma anche per chi
proviene da un altro settore, l’ingegneria. È importante notare che gli sviluppatori dei
programmi stanno ascoltando le richieste provenienti da entrambi i settori. Oggi la
fotogrammetria è tornata a prendere una posizione rilevante all'interno del rilievo dei beni
culturali, fatto che non succedeva pochi anni fa6. Gli sviluppatori di software hanno dimostrato
la volontà di dare alle persone che lavorano nel campo della geomatica o fotografia, strumenti
che in qualche modo compensino, la già citata "black box", che suppone il non sapere
esattamente il lavoro interno del programma. Sono noti che hanno sistemi di riconoscimento

5 Vedere gli atti di Conferenza Nazionale del colore, Firenze, 19-20 Settembre 2013 y Conferenza
Nazionale del colore, Roma, Settembre 2011.
6 Conferenza di Remondino in Corso MICMAC, Politecnico di Torino. 3 - 6 febbraio 2014.

343

<!-- p. 353 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

della forma, che calcola i parametri della fotocamera, ecc., ma mentre nel PhotoModeler viene
mostrato tutto esplicitamente, non è il caso di programmi come Agisoft PhotoScan. Tuttavia, si
vede una continua evoluzione, in cui sono sempre di più i dati forniti per consentire un rilievo
certificato rivolto a permettere di controllare quali sono gli errori che vengono fatti da questi
programmi.

Si può dire che, da un lato, il beneficio di sensori attivi è innegabile, però allo stesso tempo
la professionalità o il miglioramento qualitativo dei programmi di fotogrammetria sta
permettendo di unire questi due modelli in modelli che in qualsiasi caso sintetizzano al massimo
la qualità sotto il profilo della misurazione e del colore.

Tuttavia, una delle questioni attualmente aperte nel campo della ricerca è quella di fornire
agli sviluppatori di software l'idea di introdurre nei programmi strumenti affidabili ai fini degli
obiettivi dei restauratori. I programmi di Reverse modelling nascono per soddisfare le esigenze
di ingegneri o progettisti, Agisoft PhotoScan o Photomodeler, quelle dei topografi, ma da questo
studio si è constatato che ancora in questo momento, ci sono lacune nei programmi per le
specifiche esigenze presentate dai restauratori. Nel corso dei diversi casi di studio, si verificano,
in diverse occasioni, i problemi dovuti alla necessità di esportare e importare per non trovare in
un unico programma gli strumenti che consentirebbero di realizzare l'intero processo: dal rilievo
attraverso fotografie o scanner laser fino alla restituzione finale del modello.

Quindi si può concludere che questo insieme di esperienze sta seguendo, a sua volta,
l’evoluzione e i miglioramenti che si stanno introducendo nel mondo del rilievo e della
restituzione. Inoltre, si può affermare che anche la terminologia è molto importante, perché il
vocabolario degli architetti (che sono quelli che si dedicano principalmente nella costruzione di
modelli 3D) si sta avvicinando, in un aspetto più professionale, a questi strumenti, cosa che in
precedenza si verificava meno.

La questione terminologica è stata affrontata con la volontà di fare un confronto lessicale tra
le tre lingue. Come si racconta nella parte introduttiva della tesi, sostenuta da diversi esperti del
settore, si è trovata una mancanza di parità nell'uso del linguaggio tecnico usato dagli esperti nel
campo del rilievo e della restituzione in 3D. Osservando continuamente questa mancanza di
uguaglianza e uniformità dei termini, si presenta nell'ultimo capitolo della tesi uno studio della
terminologia specifica, in cui i termini sono confrontati e permettono di comporre nelle tre
lingue un concetto ed i termini che vengono utilizzati per fare riferimento ad esso. Con questo
capitolo si cerca di fornire una coerenza nella terminologia non ottenuta finora in questo campo,
e discussa da vari autori (Amoruso, G., Apollonio, F.I. e Remondino, F., 2010, Guidi e
Remondino, 2012).

344

<!-- p. 354 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

C. REFERENCIAS

 Amoruso, G., Apollonio, F.I. y Remondino, F. 2010. “Caratterizzazione strumentale di
sensori attivi a tempo di volo (ToF) e a triangolazione. Utilizzo di laser scanner su superfici
marmoree di epoca romana” en Benedetti, B., Gaiani, M. y Remondino, F. (ed.) Modelli
Digitali 3D in archeologia: Il caso di Pompei. Edizioni della Normale. Scuola Normale
Superiore Pisa, pp. 118-161.

 Guidi, G. y Remondino, F., 2012. “3D Modelling from Real Data” en Modelling and
Simulation in Engineering. Edited by Catalin Alexandru, InTech, 3 de Marzo, pp. 69-102.

345

<!-- p. 355 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

CAPÍTULO 10. BIBLIOGRAFIA

346

<!-- p. 356 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

A. BIBLIOGRAFIA BÁSICA1

 Benedetti, B., Gaiani, M. y Remondino, F. (ed.), 2010. Modelli Digitali 3D in archeologia:
Il caso di Pompei. Edizioni della Normale. Scuola Normale Superiore Pisa, pp. 118-161.

 Bertocci, S., Bini, M. (ed.), 2012. Manuale di rilievo architettonico e urbano. CittàStudi
Edizioni. Novara, Italia, pp. 215-232.

 Buill, F., Núñez, M.A., Rodríguez, J.J., 2007. La fotogrametría arquitectónica. Edición
UPC. Barcelona.

 Cannarozzo, Cucchiarini, Meschieri, 2012. Fotogrammetría. Misure, rilievo, progetto.
Volumen 3. Zanichelli editore S.p.A., Bolonia

 Cueli López, J.T., 2011. Fotogrametría práctica. Ed. Tantin. Santander. ISBN 978-84-
9692-093-4.

 Cueli López, J., 2010. Cursos gratis de fotogrametría. Tutoriales Photomodeler.
Disponible en: http://www.worldphotogrammetry.com/home/itemlist/category/6-cursos-
gratuitos.html (última visita: 13/12/2013)

 Docci, M. y Maestri, D., 1984. Il rilevamento architettonico. Storia, metodi e disegno. Ed.
Laterza. Roma

 Fantini, F., 2008. Il modello di stadio da Villa Adriana. Indagine su un progetto
incompiuto. Università degli Studi di Firenze. Florencia.

 Guidi, G., Russo, M. y Beraldin, J.A., 2010. Acquisizione 3D e modellazione poligonale.
McGraw-Hill. Italia.

 Guidi, G. y Remondino, F., 2012. “3D Modelling from Real Data” en Modelling and
Simulation in Engineering. Edited by Catalin Alexandru, InTech, 3 de Marzo, pp. 69-102.

 Herráez Boquera, J., Navarro Esteve, P y Denia Ríos, JL., 2010. “Fundamentos y
aplicaciones de la tecnología de Escáner Láser para documentación y restauración del
patrimonio. Algunos ejemplos de aplicación en La Comunidad Valenciana” en Alcántara
Onofre, A., Lara Gutiérrez, A. M. (ed.) Implementación de nuevos métodos de
documentación y registro fotogramétrico digital para la protección y puesta en valor del
patrimonio monumental mexicano. Ciudad de México: Universidad Politécnica de
Valencia, pp. 17-41.

1 En este capítulo se señala solo una bibliografía general de la tesis, ya que para los temas específicos de
cada capítulo se puede consultar directamente en el apartado “referencias” de éstos.

347

<!-- p. 357 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

 Kraus, K., 1994. Fotogrammetria. Vol. 1. Teoria e applicazioni. Libreria universitaria
Levrotto & Bella. Torino.

 Kraus, K., 1997. Photogrammetry. Vol. 2. Advanced Methods and Applications. Dümmler
Verlag. Bonn.

 Martínez-Espejo Zaragoza, I., 2012. Interpretazione museografica dei portici con fregi di
caccia della “Piazza d’Oro”. Tesis del Máster Itinerante en “Museografia, Architettura e
Archeologia. Progettazione Strategica e Gestione Innovativa del Patrimonio Archeologico”
instituido por la “Accademia Adrianea di Architettura e Archeologia Onlus” dirigida por
Francisco Juan Vidal. Roma, Italia

 Migliari, R. (ed.), 2009. Geometria descrittiva, volume II, tecniche e applicazioni. Città
Studi edizioni-De Agostini Scuola. Novara, pp. 60-94.

 Mtnez-Espejo Zaragoza, I., 2010. La Iglesia de los Desamparados de Les Coves de
Vinromá. Hipótesis y restitución virtual de la bóveda de la capilla mayor. Tesina del
Máster Oficial de Conservación del Patrimonio de la Universidad Politécnica de Valencia
dirigida por Francisco Juan Vidal. Valencia.

348

<!-- p. 358 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

CAPÍTULO 11. AGRADECIMIENTOS

349

<!-- p. 359 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

A. AGRADECIMIENTOS

En primer lugar quiero expresar mi agradecimiento a Francisco Juan Vidal, un profesor, que
desde que llegué al Master hace unos cuatro años, ha puesto siempre en mí su confianza. Un
persona a la que admiro por su capacidad de trabajo, su paciencia y su sabiduría. Agradecerle
que me haya apoyado siempre en mis proyectos, y haya sabido ver en mí, la persona que yo a
veces dudo ser.

Agradecer a Filippo Fantini toda su dedicación. El haberme abierto este mundo, para mi
nuevo, de la tecnología para el levantamiento del patrimonio arquitectónico, del que me ha
enseñado tantísimo. Agradecer sinceramente toda su ayuda, en todos esos días trabajando hasta
las tantas, y su conexión con el mundo italiano que tanto me ha enseñado.

Agradecer a la profesora Gabriella Caroti, no solo el que me haya enseñado y ayudado tanto
y que haya puesto su confianza en mí, dándome tantas oportunidades, que me han hecho sentir
de verdad valorada, sino el hecho de haberme hecho conocer a una persona que de verdad se ha
convertido en mi persona de referencia, sobre a donde me gustaría llegar. Mi admiración por
ella, hace que cuando me siento flaquear, aparezcan las fuerzas para continuar. Es una persona
decidida en los momentos claves, cercana en los momentos en que te sientes perdida, fuerte
cuando no está de acuerdo para defender sus ideas, y tantas cosas más que se podrían decir. Es
esa persona en la que piensas cuando te preguntan a quién te gustaría parecerte “cuando seas
mayor”.

Agradecer a Andrea Piemonte, su cercanía, su ayuda, su disponibilidad y su simpatía, que te
ayuda a pedirle consejo cuando el camino no es tan claro. Agradecerle que me haya enseñado
tanto, con esas cualidades que te hacen darte cuenta que, de verdad, es un magnífico profesor.

A Benedetta Adembri, directora de la Villa Adriana, su ayuda para conocer a fondo la Villa
Adriana, su apoyo en algunos momentos de dificultad, y su fascinación por su trabajo, que tanto
me ha inspirado para realizar una investigación que ella ha convertido en apasionante.

A Pablo Navarro por ayudarme con el primer levantamiento con escáner láser TOF, una de
las piezas claves que ha permitido aflorar mi interés por la nueva tecnología aplicada al
levantamiento arquitectónico.

A Marco Bevilacqua, Juan Carlos Navarro Fajardo, Pablo Rodríguez, Rafa Marín y Sergio
Di Tondo, que siendo profesores no directamente ligados a mi doctorado, me ha enseñado
muchísimo, mostrándose siempre disponibles y ayudándome siempre que los he necesitado.

A Jorge Martínez, por su ayuda en el trabajo, por los momentos de despacho de apoyo mutuo
cuando venían las dudas existenciales sobre el trabajo que estábamos realizando, y por haberse
convertido en un gran amigo y apoyo.

350

<!-- p. 360 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

A Federico Capriuoli, por trabajar conmigo probando algunos modelos, y endulzando esas
mañanas de desesperación, de largas horas de espera, con esas ricas muestras de gastronomía
italiana.

A Jorge Cueli experto en Photomodeler, que me ha aclarado muchas dudas de este programa
sin las que habría sido imposible llegar a los resultados obtenidos, agradecerle su rapidez
respondiéndome siempre y su gran disponibilidad.

A mis compañeros de Pisa, Andrea Bedini y Jessica Micheloni, que me han apoyado
muchísimo desde que llegué, compartiendo cada uno de mis logros, y enseñándome a nivel
profesional y sentimental.

A Federico Caliari y a todos los miembros del Premio Piranesi y del Master de la Academia
Adrianea, que en parte me inspiraron para que mi doctorado cogiese este camino, enseñándome
que aprender y estudiar no siempre tiene que ser aburrido.

A Pedro Collado, que desde que me conoció en la carrera y lo elegí como director del
proyecto final, siempre ha estado apoyándome y ayudándome, recomendándome siempre los
mejores caminos para llegar a cumplir mi sueño.

A Fernando y Sara, Erasmus de la politécnica de Valencia, que he conocido en Pisa, y con
los que hemos compartido la fase de levantamiento con escáner de la iglesia de San Miniato. Ha
sido una experiencia poder compartir un poco de mi conocimiento del escáner con ellos y que
ellos me hayan ayudado a darme cuenta de algunas cosas que debía revisar en mi investigación.

A mi familia, que ha soportado como nadie, todos mis momentos de incomprensión, de
dificultad, de intentos de tirar la toalla… y en conclusión todos esos momentos que pasa una
persona cuando debe afrontar un trabajo muy duro e intenso. Agradecer, en especial a mi madre,
el apoyo que me ha dedicado, el que me haya soportado en mis momentos difíciles, cuando la
tensión me ha hecho comportarme, digamos, menos agradable, y sobre todo esa confianza ciega,
que en algunos momentos dentro de mí ha estado ausente, de que lo conseguiría. Gracias por tu
entrega, por ponerme siempre delante a todas tus necesidades, por ser mi apoyo constante
siempre, un siempre con mayúsculas que hace que mi sienta realmente afortunada.

Agradecer, en general, a todas las personas que de un modo u otro me han ayudado y
apoyado para poder realizar este proyecto, y sin las cuales no podría haberlo realizado.

Por último, agradecer a mis amigos, tanto los españoles como los italianos, haberme ayudado
anímicamente para poder continuar en mi trabajo día tras día sin desistir en esos días en que
parece que todo se tuerce. En especial, quiero agradecer más concretamente a dos personas, a mi
amiga María Martínez Valado, que de verdad ha estado ahí aguantando carros y carretas, y ha
sido siempre un apoyo constante, hasta los días en que yo misma me habría mandado a algún
sitio lejano, por ser un ejemplo a seguir y una figura a la que admirar, además de una verdadera

351

<!-- p. 361 -->

PRECISIONES SOBRE EL LEVANTAMIENTO 3D INTEGRADO CON HERRAMIENTAS
AVANZADAS, APLICADO AL CONOCIMIENTO Y LA CONSERVACIÓN DEL PATRIMONIO
ARQUITECTÓNICO
Universidad Politécnica de Valencia. Doctorado en Arquitectura, Edificación, Urbanística y Paisaje

Isabel Martínez-Espejo Zaragoza Tesis Doctoral

amiga, y a Maurizio Ginghiali, que se ha convertido en el apoyo que me ha permitido llegar al
final, el hombro que me ha sostenido en los últimos momentos de desesperación, por ponerme
por delante de sus necesidades, por estar ahí sin rechistar cuando me he convertido en una
persona difícil, por conocerme y querer seguir estando a mi lado. A veces no hay palabras que
puedan expresar suficiente la gratitud, por lo que solo os puedo decir: gracias.

Isabel Mtnez-Espejo Zaragoza

352
