---
type: libro
title: "Formato Proyectos Fin de Grado / Máster"
author: "Daniel Almagro"
categoria: "Tecnología láser, fotogrametría, otros"
paginas: 108
extraccion: "texto"
fuente: "local:E:/DISCIPLINAS, TEXTOS Y MAPAS/Biblioteca digital/Tecnología láser, fotogrametría, otros/ANALISIS_DE_METODOS_PARA_EL_LEVANTAMIENT.pdf"
convertido: 2026-10-13
---

# Formato Proyectos Fin de Grado / Máster

> Texto extraído de `Tecnología láser, fotogrametría, otros/ANALISIS_DE_METODOS_PARA_EL_LEVANTAMIENT.pdf` (108 páginas, texto). El PDF original está en el disco E: (DISCIPLINAS, TEXTOS Y MAPAS\Biblioteca digital); `<!-- p. N -->` marca el inicio de cada página.

<!-- p. 1 -->

Escuela
Politécnica

UNIVERSIDAD DE EXTREMADURA

Escuela Politécnica

Máster Universitario de Especialización
en Geotecnologías Topográficas en la
Ingeniería

Trabajo Fin de Máster

ANÁLISIS DE MÉTODOS PARA EL
LEVANTAMIENTO
ARQUITECTÓNICO

Daniel Almagro Caballero de León
Septiembre, 2016

<!-- p. 2 -->

Escuela
Politécnica

UNIVERSIDAD DE EXTREMADURA
Escuela Politécnica

Máster Universitario de Especialización en
Geotecnologías Topográficas en la Ingeniería
Trabajo Fin de Máster
ANÁLISIS DE MÉTODOS PARA EL
LEVANTAMIENTO ARQUITECTÓNICO

Autor: Daniel Almagro Caballero de León

Fdo.: .
Directora: Aurora Cuartero Sáez

Fdo.: .
Tribunal Calificador
Presidente: Álvaro Gómez Gutiérrez

Fdo.: .

Secretaria: Mª Mar Pozo Ríos

Fdo.: .

Vocal: Manuel Guerrero Castro

Fdo.: .

CALIFICACIÓN: _________________
FECHA: septiembre de 2016

<!-- p. 3 -->

Máster Universitario de Especialización en
Geotecnologías Topográficas en la Ingeniería.

Análisis de métodos para el Levantamiento Arquitectónico. Escuela Politécnica

Daniel Almagro Caballero de León 3
Universidad de Extremadura

<!-- p. 4 -->

Máster Universitario de Especialización en
Geotecnologías Topográficas en la Ingeniería.

Análisis de métodos para el Levantamiento Arquitectónico. Escuela Politécnica

RESUMEN

El siguiente trabajo explica las diferentes técnicas de levantamiento
arquitectónico y de fachada existentes en la actualidad y cuál podría resultar
más asequible, fiable y rápido para realizarlo. Por ello, nos acabamos centrando
en la fotogrametría de objeto cercano o fotogrametría terrestre como método
más interesante para realizar esta serie de trabajos.

Teniendo presentes todas las técnicas de levantamiento arquitectónico
existentes, desde las manuales-tradicionales como croquis y flexómetro,
pasando por las topográficas con estación total o nivel topográfico y finalizando
con las últimas técnicas como el escáner láser 3D, nos decantamos por realizar
una comparación entre 4 software fotogramétricos existentes a nuestra
disposición y de libre adquisición para el registro de un mismo edificio.

El desarrollo de las técnicas fotogramétricas en estas últimas décadas
(Structure From Motion) hacen que este método sea cada vez más sencillo y
tenga procesos más automatizados. Esto nos permite obtener información
métrica de gran precisión a partir de realizar varias fotografías con cámara
digital.

Realizando los levantamientos con este tipo de programas obtenemos una
nube de puntos del edificio que levanta el modelo tridimensionalmente con
medidas fiables. Si, además, estos puntos contienen la gama de colores que
posee el edificio, se puede realizar el texturizado de las superficies. Por lo tanto,
esto nos añade el gran valor de quedar representado el estado real en el que se
encontraba el objeto a la hora de haber sido realizado el fotografiado y, como
consecución, el levantamiento.

Los trabajos resultantes de este levantamiento son: vectorización de planos,
ortoimágenes, modelo 3D del objeto y maquetación virtual, entre otros, en el
campo de la arquitectura.

En el presente trabajo fin de máster, en el caso práctico que se realiza, se
utiliza como objeto de comparación el edificio de Ingeniería de
Telecomunicaciones de la Escuela Politécnica de Cáceres de la Universidad de
Extremadura

PALABRAS CLAVE

Levantamiento arquitectónico, Estación total, Escáner láser, Fotogrametría terrestre,
Structure from Motion, 123D Catch, Agisoft PhotoScan, Pix4D, VisualSFM.

Daniel Almagro Caballero de León 4
Universidad de Extremadura

<!-- p. 5 -->

Máster Universitario de Especialización en
Geotecnologías Topográficas en la Ingeniería.

Análisis de métodos para el Levantamiento Arquitectónico. Escuela Politécnica

AGRADECIMIENTOS

A mi madre y hermanos por el apoyo incondicional y por su ayuda.

A mi Nana por aguantarme todos los días delante del ordenador y ser capaz de
alentarme para conseguir acabar con ello.

A mi tutora, Aurora Cuartero, por saber encauzarme y guiarme hasta el final.

Gracias a todos, de corazón.

Daniel Almagro Caballero de León 5
Universidad de Extremadura

<!-- p. 6 -->

Máster Universitario de Especialización en
Geotecnologías Topográficas en la Ingeniería.

Análisis de métodos para el Levantamiento Arquitectónico. Escuela Politécnica

Daniel Almagro Caballero de León 6
Universidad de Extremadura

<!-- p. 7 -->

Máster Universitario de Especialización en
Geotecnologías Topográficas en la Ingeniería.

Análisis de métodos para el Levantamiento Arquitectónico. Escuela Politécnica

ÍNDICE

\1. INTRODUCCIÓN ____________________________________ 9

\2. ANTECEDENTES____________________________________ 10

2.1. ESTADO DEL ARTE ______________________________________________ 10
\3. METODOLOGÍA ____________________________________ 18

3.1. MÉTODOS SIMPLES _____________________________________________ 18
3.2. MÉTODOS TOPOGRÁFICOS _____________________________________ 18
3.3. MÉTODOS FOTOGRAMÉTRICOS _________________________________ 22
3.4. MÉTODOS AVANZADOS: ESCÁNER LASER 3D ___________________ 26
3.5. CONCLUSIONES DE LOS MÉTODOS _____________________________ 31
\4. CASO PRÁCTICO ___________________________________ 33

4.1. LEVANTAMIENTO TOPOGRÁFICO REALIZADO CON ESTACIÓN
TOTAL _________________________________________________________________ 34
4.1.1. POLIGONAL ________________________________________________________ 34
4.1.2. RADIACIÓN ________________________________________________________ 38
4.1.3. PLANO DE PUNTOS RADIADOS _____________________________________ 40
4.1.4. PLANO DE PUNTOS DE LA FACHADA PRINCIPAL ____________________ 41
4.1.5. PROCESADO DE LOS DATOS Y REPRESENTACIÓN EN 3D CON
AUTOCAD PARA TOMA DE MEDIDAS _______________________________________ 42
4.2. TOMA DE MEDIDA DE REFERENCIA CON FLEXÓMETRO _________ 46
4.3. LEVANTAMIENTOS ARQUITECTÓNICOS REALIZADO CON
PROGRAMAS FOTOGRAMÉTRICOS ____________________________________ 46
4.3.1. TRABAJO DE CAMPO ____________________________________________ 48
4.3.1.1. TOMA DE IMÁGENES _____________________________________________ 48
4.3.2. PROCESADO DE LAS IMÁGENES _________________________________ 50
4.3.2.1. LEVANTAMIENTO FOTOGRAMÉTRICO REALIZADO CON EL
PROGRAMA “123D CATCH DE AUTODESK” _________________________________ 51
4.3.2.2. LEVANTAMIENTO FOTOGRAMÉTRICO REALIZADO CON EL
PROGRAMA ”PHOTOSCAN PROFESSIONAL DE AGISOFT” ___________________ 56
4.3.2.3. LEVANTAMIENTO FOTOGRAMÉTRICO REALIZADO CON EL
PROGRAMA “PIX4D” _______________________________________________________ 63
4.3.2.4. LEVANTAMIENTO FOTOGRAMÉTRICO REALIZADO CON EL
PROGRAMA “VISUAL SFM Y MESHLAB” _____________________________________ 69
\5. EVALUACIÓN DE LA CALIDAD MÉTRICA DE LOS
MODELOS 3D __________________________________________ 79

\6. RESULTADOS ______________________________________ 82

\7. CONCLUSIONES____________________________________ 86

Daniel Almagro Caballero de León 7
Universidad de Extremadura

<!-- p. 8 -->

Máster Universitario de Especialización en
Geotecnologías Topográficas en la Ingeniería.

Análisis de métodos para el Levantamiento Arquitectónico. Escuela Politécnica

\8. LÍNEAS FUTURAS DE TRABAJO _____________________ 88

\9. BIBLIOGRAFÍA _____________________________________ 89

\10. INDICE DE FIGURAS Y TABLAS _____________________ 93

ANEXO I. Reseñas de las estaciones bases __________________ 95

ANEXO II. Toma de datos y cálculo de las coordenadas de la
Poligonal _______________________________________________ 98

ANEXO III. Toma de datos y cálculo de las coordenadas de la
Radiación _____________________________________________ 100

ANEXO IV. Modelos 3D ________________________________ 104

Daniel Almagro Caballero de León 8
Universidad de Extremadura

<!-- p. 9 -->

Máster Universitario de Especialización en
Geotecnologías Topográficas en la Ingeniería.

Análisis de métodos para el Levantamiento Arquitectónico. Escuela Politécnica

\1. INTRODUCCIÓN

En el presente proyecto se pretende analizar los diferentes métodos para la
realización de Levantamientos Arquitectónicos (Almagro A. , 2004) (Rodríguez
M. Á., 2008) y de fachadas de edificios, centrándonos en los métodos
fotogramétricos (Almagro A. , Simplified methods in Architectural
Photogrammetry, 1991) y el análisis de la fiabilidad y precisión de los softwares
libres existentes en la actualidad.

Las técnicas para el levantamiento Arquitectónico de edificios son múltiples
actualmente (Rodríguez M. Á., 2008): desde los clásicos métodos de medición
manual donde se realizan los primeros croquis y se mide con cinta métrica,
pasando por los métodos topográficos donde los instrumentos topográficos de
precisión emplean métodos de reiteración e intercesión, junto con los métodos
fotogramétricos donde a partir de fotografías apoyadas en medición de puntos
de control por métodos topográficos son rectificadas para medir sobre ellas,
hasta los métodos más avanzados como son los escáneres láser (García-Gómez
et al, 2011) para realizar directamente levantamientos en 3D.

Después de realizar una investigación de los antecedentes y el estado del arte
y una explicación más profunda de los diferentes métodos, llevaremos a cabo
un caso práctico de levantamiento eligiendo la aplicación de varios programas
fotogramétricos. Explicaremos el proceso de obtención del modelo con cada
software, de los cuales extraeremos unas medidas de comparación para analizar
la fiabilidad de cada uno además del análisis de otros parámetros.

Daniel Almagro Caballero de León 9
Universidad de Extremadura

<!-- p. 10 -->

Máster Universitario de Especialización en
Geotecnologías Topográficas en la Ingeniería.

Análisis de métodos para el Levantamiento Arquitectónico. Escuela Politécnica

\2. ANTECEDENTES

Definición de levantamiento arquitectónico

La palabra levantamiento es un término que pocos entienden tal y como los
técnicos del ámbito de la arquitectura y de la ingeniería lo hacen. En la Real
Academia Española de la lengua no está recogido con este sentido, solo
arquitectos y topógrafos lo entienden así, aunque cada vez está más extendido
entre profesionales ligados a este oficio, como arqueólogos e historiadores (A.
Almagro, 2004).

En otros idiomas si tienen una palabra que define claramente esta actividad
como puede ser rilievo en italiano, relevé en francés, survey en inglés o
bauforshungen en alemán.

Así, para definir la palabra Levantamiento arquitectónico vamos a tomar
palabras de D. Antonio Almagro Gorbea:

(…) se debe entender por levantamiento arquitectónico la forma primigenia de
conocimiento y por lo tanto el conjunto de operaciones, de medidas y de análisis
necesarios para comprender y documentar el bien arquitectónico en su configuración
completa, referida incluso al contexto urbano y territorial, en sus características
dimensionales y métricas, en su complejidad histórica, en sus características
estructurales y constructivas, así como en las formales y funcionales (Almagro 2004).

Por tanto, podemos concretar que un levantamiento arquitectónico tiene
como objetivo principal el conocimiento morfológico y constructivo del edificio
o parte del edificio que nos interese, habiéndose documentado previamente con
lo existente, si lo hubiese, y realizando todas las operaciones necesarias para
documentar con fidelidad y el nivel de precisión que sea necesario en el trabajo
a realizar.

2.1. ESTADO DEL ARTE

De entre las diferentes técnicas que vamos a analizar sobre levantamiento
arquitectónico, nos centraremos en el método fotogramétrico. Por ello, en este
apartado revisaremos la actualidad de la fotogrametría, nos familiarizaremos
con los órganos nacionales e internacionales de regularización, revisaremos
libros, artículos, revistas y trabajos para actualizar los conocimientos de dicha
técnica.

Daniel Almagro Caballero de León 10
Universidad de Extremadura

<!-- p. 11 -->

Máster Universitario de Especialización en
Geotecnologías Topográficas en la Ingeniería.

Análisis de métodos para el Levantamiento Arquitectónico. Escuela Politécnica

La fotogrametría

A continuación, se realiza una breve revisión del concepto de fotogrametría.
Para ello, se ha seleccionado una serie de definiciones extraídas de los Apuntes
de la asignatura Iniciación a la Investigación Aplicada en Fotogrametría y
Geodesia (Cuartero, 2012).

"... técnica para estudiar y definir con precisión la forma, dimensiones y posición en
el espacio de un objeto cualquiera, utilizando medidas realizadas sobre una o varias
fotografías...", (Bonneval, 1972).

“Fotogrametría es la ciencia de realizar mediciones e interpretaciones
confiables por medio de las fotografías, para de esa manera obtener
características métricas y geométricas (dimensión, forma y posición), del objeto
fotografiado” (ISPRS, 2007).

“Fotogrametría es el arte, ciencia y tecnología de obtener información
fidedigna de los objetos físicos y del medio ambiente mediante procesos de
registro, medición e interpretación de imágenes fotográficas y de modelos de
energía radiante electromagnética y otros fenómenos” (ASPRS, 1934).

La fotogrametría de objeto cercano es un proceso por el cual permite
reconstruir la posición, orientación, forma y tamaño de los objetos a partir de la
toma de una serie fotografías de los objetos usados como modelo, llegando a
obtener una imagen tridimensional de los mismos. Si te toman dos fotografías
de un objeto, puede llegarse a identificar una serie de puntos comunes en
ambas imágenes que mediante sofisticados algoritmos de cálculo nos llevaría a
conocer los parámetros indicados anteriormente (orientación, posición, tamaño,
color...) obteniendo nubes de puntos que pueden definir con mucha precisión
su imagen tridimensional. También se define como una disciplina que crea
modelos 3D a partir de imágenes 2D, para de esta manera obtener
características geométricas de los objetos que representan, mediante el uso de
relaciones matemáticas establecidas en la geometría proyectiva, y de la visión
estereoscópica que posee de forma natural el ser humano.

Structure From Motion

Llegados a este punto, tenemos que hacer una pequeña revisión sobre las
técnicas para obtener un objeto tridimensionalmente a partir de imágenes
digitales. Entre estas técnicas nos encontramos con la fotogramétrica tradicional
y con Structure From Motion, a partir de ahora SFM.

La fotogrametría es una técnica bastante antigua en la que se establecen
puntos comunes entre las imágenes tomadas de forma controlada y con

Daniel Almagro Caballero de León 11
Universidad de Extremadura

<!-- p. 12 -->

Máster Universitario de Especialización en
Geotecnologías Topográficas en la Ingeniería.

Análisis de métodos para el Levantamiento Arquitectónico. Escuela Politécnica

cámaras calibradas con la finalidad de tomar mediciones entre estos puntos. En
la actualidad se pueden extraer modelos 3D con cierta eficacia.

Por otro lado, no encontramos con SFM, desarrollado en la década de los 90,
que está inspirada en la fotogrametría, pero viene del campo de la visión
artificial. Esta técnica permite recrear modelos 3D a partir de un grupo de
imágenes no estructuradas, ni cámaras calibradas, e incluso utilizar distintas
cámaras (Westoby et al, 2012).

Actualmente estas dos técnicas se unen en diversos programas
fotogramétricos que dan soporte a este tipo de tareas, simplifican el proceso de
obtención del modelo (Pereira J. , 2012).

Scale-invariant feature transform (SIFT)

Característica invariante de la escala transformada, posible traducción a
nuestro idioma, es un algoritmo usado en visión artificial para extraer
características relevantes de las imágenes que posteriormente pueden usarse en
reconocimiento de objetos, detección de movimientos, registro de imágenes
entre otras. (Lowe, 2004)

SFM se basa en este algoritmo para detectar los puntos homólogos de las
imágenes tomadas. El algoritmo fue publicado por primera vez por David
Lowe en 1999 pero lo describió completamente y patentó en Estados Unidos en
\2004.

Utilidad y herramienta de estas técnicas

Los campos de la arqueología, artes rupestres, levantamientos
arquitectónicos y de fachadas, reproducciones de lugares y monumentos,
cartografía, conservación de bienes culturales, documentación de piezas
arqueológicas en museos y en general, todas las disciplinas de protección,
documentación, digitalización o virtualización del patrimonio se están
beneficiando de los trabajados realizados con programas fotogramétricos. Es
una herramienta, muy asequible, de cierta simpleza en su uso y una fuente de
documentación bastante relevante.

Algunos de los procesos fotogramétricos que se realizan con este tipo de
programas son rectificación, restitución, ortoproyección y generación de
modelos digitales de elevaciones (García Léon & Cuartero Sáez, 2002).
Ampliando lo anterior, los programas actuales añaden la creación de nube de
puntos, del mallado de éstas y la aplicación de texturas, por lo que recrean en
3D los objetos.

Daniel Almagro Caballero de León 12
Universidad de Extremadura

<!-- p. 13 -->

Máster Universitario de Especialización en
Geotecnologías Topográficas en la Ingeniería.

Análisis de métodos para el Levantamiento Arquitectónico. Escuela Politécnica

En la actualidad no hay gran oferta en el mercado de este tipo de
herramientas computacionales. Pueden destacar la veterana Photomodeler de la
empresa Eos Systems, Photoscan de la empresa rusa Agisoft y Pix4d de origen
suizo. Todas ellas inspiradas en SFM.

Las alternativas de software libre (open source) o gratuitas también están muy
limitadas.

“…por una parte tenemos la aplicación online desarrollada por Microsoft
denominada Photosynth la cual, para poder descargar los trabajos realizados online,
necesitamos una herramienta intermedia denominada SynthExport disponible sólo para
las plataformas de Microsoft. En el terreno online tenemos otra herramienta
denominada Hypr3D que nos permite crear modelos 3D a partir de fotografías y
exportarlos a otros entornos. Otra alternativa es INSIGHT3D disponible para Windows
y Linux, pero cuyo desarrollo se encuentra obsoleto, siendo muy difícil su instalación ya
que no es compatible con las últimas librerías de OpenCV, presentando además una
cierta inestabilidad. Como última opción también tenemos a nuestro alcance ARC3D
una herramienta con una orientación hacia usos relativos a la digitalización 3D del
patrimonio, que está disponible de forma a través de un cliente que acceder por servicios
web a un servidor online, donde se realiza en todos los procesos, al igual que el resto de
soluciones web hay que estar registrado previamente en la plataforma…” (Pereira J. ,
2012).

También tenemos el software gratuito 123D catch de AutoDesk, dentro de los
programas libres es unos de los más potentes y fáciles de usar, con una buena
interfaz. Este realiza los procesos para crear el modelo virtual en un servidor
propio después de subir las fotografías tomadas del objeto.

Otra alternativa libre son las herramientas tipo Bundler, que se fundamentan
en procesos similares de SFM, pero su uso suele ser por línea de comandos, lo
cual se hace más tedioso.

Organismos Nacionales e Internacionales

Los principales organismos internacionales que regulan los trabajos
fotogramétricos son:

ISPRS. International Society for Photogrammetry and Remote Sensing.

La Sociedad Internacional de Fotogrametría y Teledetección es una
organización no gubernamental dedicada al desarrollo de la cooperación
internacional para el avance de la fotogrametría y teledetección y sus
aplicaciones (ISPRS, 2015).

ASPRS. American Society for Photogrammetry and Remote Sensing.

Daniel Almagro Caballero de León 13
Universidad de Extremadura

<!-- p. 14 -->

Máster Universitario de Especialización en
Geotecnologías Topográficas en la Ingeniería.

Análisis de métodos para el Levantamiento Arquitectónico. Escuela Politécnica

Fundada en 1934, la ASPRS es una asociación científica que sirve a más de
7.000 miembros profesionales de todo el mundo. Promueve la aplicación
responsable de la fotogrametría, teledetección, sistemas de información
geográfica (GIS), y tecnologías de apoyo. La ASPRS ha incorporado
oficialmente a "La Imagen y Sociedad de la Información Geoespacial," como
parte de la identidad. Este lema representa a la Sociedad de la "Nueva Visión",
ya que hace los cambios necesarios para una mejor posición de su enfoque para
el futuro (ASPRS, 2012).

CIPA. Comité Internacional para la Documentación del Patrimonio Cultural.
(International Commitee for Architectural Photogrammetry).

El CIPA se creó como resultado de una resolución del Coloquio Internacional
sobre la Aplicación de la fotogrametría a la Arquitectura, organizada en julio de
1968 por el Consejo Internacional de Monumentos y Lugares (ICOMOS). CIPA
es una de las comisiones especializadas internacionales de ICOMOS, pero al
mismo tiempo es también un comité de enlace entre ICOMOS e ISPRS, que
patrocinan conjuntamente. Está en la actualidad compuesta por ocho miembros
activos del comité. Sus objetivos son promover la fotogrametría arquitectónica,
para contribuir a su desarrollo técnico, y para asegurar el enlace entre
fotogrametristas y los que utilizan comisión o levantamientos fotogramétricos
de edificios en la arquitectura. Para lograr estos objetivos, la Comisión trabaja
en la recogida y la difusión de información sobre el tema de la fotogrametría
arquitectónica, en la organización de reuniones internacionales y en el apoyo al
estudio de las técnicas y actividades de formación (Carbonel & Dallas, 2003).

SECFT. La Sociedad Española de Cartografía, Fotogrametría y Teledetección.

Es una asociación al amparo de la Ley Orgánica 1/2002, de 22 de marzo, y
sus normas complementarias, con personalidad jurídica y plena capacidad de
obrar, careciendo de ánimo de lucro.

En el momento de su creación se tuvieron en cuenta las dos sociedades
internacionales que existían en estos campos: la Asociación Cartográfica
Internacional (ICA) y la ISPRS a las que representa en España, decidiéndose con
acierto que su denominación recogiese precisamente los nombres de ambas
para cubrir a nivel nacional los ámbitos de actuación que se contemplaban a
nivel internacional (SECFT, 2016).

Revista MAPPING. International journal of geomatics and earth sciences.

MAPPING es una publicación técnico-científica especializada en la
Geomática y Ciencias de la Tierra relacionadas a dicha disciplina. Con 23 años
de historia, y fuerte impacto en Iberoamérica, esta publicación periódica es
editada en España y abarca campos como Tecnologías de la Geoinformación,

Daniel Almagro Caballero de León 14
Universidad de Extremadura

<!-- p. 15 -->

Máster Universitario de Especialización en
Geotecnologías Topográficas en la Ingeniería.

Análisis de métodos para el Levantamiento Arquitectónico. Escuela Politécnica

Cartografía, Topografía, Teledetección, Fotogrametría, Patrimonio, Medio
Ambiente y demás disciplinas y tecnologías vinculadas a la geomática. (Revista
MAPPING, 2013).

Son varios los artículos y trabajos publicados en los que se realizan el análisis
de las diferentes alternativas a los métodos tradicionales de levantamiento
arquitectónico y en los que se determina la dificultad de la realización del
método, la fiabilidad y precisión y su utilidad.

Dejando a un lado los métodos tradicionales, como son el uso de la estación
total, de los que ya se han comprobado su fiabilidad, su precisión y la
simplicidad de su elaboración, nos hemos centrado en recabar más información
sobre los métodos alternativos como son los fotogramétricos y el escáner láser
3D. También, en muchos casos, se utilizan la combinación de varios métodos
para realizar el levantamiento arquitectónico o de fachada. (García-León et al,
2014), (Souto Vidal et al, 2015)

El levantamiento de fachadas es un trabajo muy demandado en muchos
campos como la planificación arquitectónica y el planeamiento. (Souto Vidal et
al, 2015) La fotogrametría puede ser un método de gran precisión geométrica y
la cual te permite visualizar la textura del objeto estudiado, añadiendo además
la rapidez y la existencia de software libres. Todo esto convierte a esta técnica
en una de las más asequibles actualmente (Martínez Rodríguez, Evaluación en
campo de una nueva técnica fotogramétrica de rango cercano y bajo coste
basada en la correlación automática de imágenes., 2014).

En la mayoría de trabajos realizados se complementan la utilización de toma
de puntos de control con estación total y la utilización de la fotogrametría.
(Souto Vidal et al, 2015), (Salcedo Galera & Calvo López, 2014) (García-León et
al, 2014). Esto es necesario para determinar la calidad de las medidas que se
pueden obtener del modelo 3D recreado con los softwares fotogramétricos
además de su escalado para toma de medidas.

También se suelen introducir en la escena algún objeto de medidas conocido,
como pueden ser los jalones o las miras métricas. Esto nos ayuda a escalar y
tener una referencia dentro de la imagen.

Los resultados de análisis de precisión llevados a cabo en diferentes trabajos
(Souto Vidal et al, 2015) (Martínez Rodríguez, Evaluación en campo de una
nueva técnica fotogramétrica de rango cercano y bajo coste basada en la
correlación automática de imágenes., 2014) (Salcedo Galera & Calvo López,
\2014) (Rivas, 2013) presentan errores que oscilan entre 30 a 9 mm lo que puede
limitar la aplicabilidad cuando se precisan escalas superiores a 1/100 pero que
en los que se pueden utilizar para gran cantidad de trabajos. Aun así, estas

Daniel Almagro Caballero de León 15
Universidad de Extremadura

<!-- p. 16 -->

Máster Universitario de Especialización en
Geotecnologías Topográficas en la Ingeniería.

Análisis de métodos para el Levantamiento Arquitectónico. Escuela Politécnica

medidas se pueden afinar mucho más con programas fotogramétricos
comerciales que dan mejores resultados.

Las conclusiones obtenidas en estos trabajos se asemejan a la mayoría de los
realizados sobre levantamientos arquitectónicos de edificios a través de
fotogrametría. Los autores coinciden en que es un sistema fiable, rápido y
sencillo para obtener levantamientos tridimensionales precisos.

Fotogrametría VS Escáner Láser

De los métodos más actuales que tenemos a día de hoy, fotogrametría y
escáner láser, comentamos lo siguiente:

Del método fotogramétrico destacamos la facilidad y automatización de los
softwares fotogramétricos que permiten su utilización por usuarios sin alta
especialización. Además, se obtiene documentación métrica con una textura
fotorrealista de buena calidad, la cual es más fácilmente interpretable que los
documentos cartográficos convencionales y pueden ser una potente
herramienta en el ámbito arquitectónico y cultural.

El coste del equipo y la posibilidad de utilizar software gratuito aumenta el
potencial de esta técnica. Sin embargo, estas herramientas muestran carencias
en trabajos que requieran gran precisión, limitándolo a una serie de usos.

De igual forma la obtención de modelos tridimensionales en formato digital,
abre nuevas puertas a la forma en que consideramos el registro de la
información geoespacial. Este formato es estable y preciso, de fácil distribución
y visualización por gran número de dispositivos móviles. Además, no debemos
olvidar que estas réplicas no solo registran la información espacial, sino que
también registran un momento determinado del tiempo, convirtiéndolas en una
herramienta ideal para cuantificar el deterioro y evolución de los inmuebles.

Del método de escáner láser podemos decir que empieza a consolidarse
como una alternativa muy a tener en cuenta conjuntamente con otras técnicas
de levantamiento arquitectónico como la fotogrametría.

Los altos costes y la falta de autonomía son los contras de este método, pero
la posibilidad de alquilar el instrumental ofrece flexibilidad para poder utilizar
en cada caso el escáner que, por prestaciones, se considere más adecuado para
un proyecto (con una buena planificación de los escaneos esta opción puede ser
ciertamente económica).

Concluyendo sobre el uso de ambas técnicas observamos que son
perfectamente válidas para documentar el patrimonio construido y necesitan

Daniel Almagro Caballero de León 16
Universidad de Extremadura

<!-- p. 17 -->

Máster Universitario de Especialización en
Geotecnologías Topográficas en la Ingeniería.

Análisis de métodos para el Levantamiento Arquitectónico. Escuela Politécnica

poco tiempo para la captura de datos en campo. Las desventajas son similares
en ambas técnicas, les afecta las obstrucciones, la gran cantidad de datos deben
de ser depurados y ninguna vectoriza de forma automática lo que facilitaría
mucho los procesos de levantamiento.

La diferencia más destacable entre las dos es su facilidad de adquisición,
donde el sistema fotogramétrico se lleva la palma. (Fernández et al, 2012)

Con un presupuesto de entre 1000 y 3000 € puedes hacerte con un equipo de
levantamiento muy aceptable para la realización de los trabajos.
Descomponiendo el equipo en cámara réflex digital (400 – 2000 €)1, ordenador
de sobremesa o portátil (500 – 3000 €)1 entre los gastos más importantes. Es
necesario tener en cuenta que los ordenadores deben de tener unas
características mínimas de software y hardware para que los programas
fotogramétricos funcionen sin problemas.

Los escáneres láser 3D tienen costes de entre 36.000 a 90.000 €2 dependiendo
de la gama y fabricante, además hay que añadir la compra de la licencia del
software para manejar la nube de puntos recogidas en los escaneos.
Normalmente cada casa tiene el suyo propio por lo que no hay uno general que
sirva para todos. Los alquileres por día suelen estar entre 170 – 1200 €
dependiendo como siempre del fabricante y del modelo.

En definitiva, vemos que los trabajos con este tipo de instrumental son
bastante caros en comparación con los instrumentos necesarios para el sistema
fotogramétrico.

\1. Precios consultados en: www.mediamarkt.es/

\2. Precios consultados en:
http://www.cartesia.org/foro/viewtopic.php?t=28108&sid=8c3827e5e54
46432801e0301ac20e3d5
http://www.sinluz.com/servicios/topografia/escaneado-3d-para-
arquitectura/292-comparativa-entre-equipos-laser-3d

Daniel Almagro Caballero de León 17
Universidad de Extremadura

<!-- p. 18 -->

Máster Universitario de Especialización en
Geotecnologías Topográficas en la Ingeniería.

Análisis de métodos para el Levantamiento Arquitectónico. Escuela Politécnica

\3. METODOLOGÍA

Los levantamientos arquitectónicos se realizan para poder conocer las
dimensiones y formas de un edificio o monumento en el ámbito de la
arquitectura. Por ello, los diferentes métodos existentes podemos agruparlos
según la complejidad de los instrumentos utilizados.

3.1. MÉTODOS SIMPLES

En primer lugar, tendremos los instrumentos más simples, la cinta métrica, la
plomada y el nivel. Utilizando estos instrumentos distinguimos dos tipos de
levantamientos simples: el directo y el diferido (Almagro A. , 2004).

El levantamiento directo es el que se realiza en el propio lugar y no requiere
más elaboración posterior que pasarlo a limpio. Es muy utilizado sobre todo en
arqueología.

El levantamiento diferido es el que se toman los datos necesarios en el lugar
y después, en la oficina o estudio, se elaboran los dibujos. Es el utilizado en la
mayoría de trabajos.

3.2. MÉTODOS TOPOGRÁFICOS

Cuando tenemos casos en los que no es posible acceder a los puntos de
medición se hace preciso acudir a técnicas instrumentales que nos permiten la
medición a distancia y sin tener accesibilidad, de cuantos puntos del edificio
podamos observar desde la zona de visualización. Esta metodología se basa en
la determinación de las direcciones y las distancias en que se encuentran los
puntos a medir, desde puntos accesibles desde los que se realizan las
observaciones.

En este sistema las herramientas utilizadas son varias, teodolito, estación
total con prisma…, pero las que han solventado todos los problemas en la
recogida de datos mediante esta técnica es la estación total con distanciómetro
de rayo láser que permite saber a qué distancia está el punto del instrumento
sin necesidad de llegar a él. Estos son ya muy sofisticados teniendo memoria
interna para guardar los datos de los puntos medidos y su posterior volcado en
el ordenador para ser tratados a través del programa adecuado de CAD, así se
consigue precisión y rapidez en los levantamientos.

Los distintos métodos topográficos son los 3 en los que aumenta su precisión
de menos a más:

Daniel Almagro Caballero de León 18
Universidad de Extremadura

<!-- p. 19 -->

Máster Universitario de Especialización en
Geotecnologías Topográficas en la Ingeniería.

Análisis de métodos para el Levantamiento Arquitectónico. Escuela Politécnica

Método de radiación

Basado en la medida de ángulos y distancias. Consiste en estacionar el
instrumento topográfico, generalmente la estación total, en un punto
aproximadamente central de los puntos que tenemos que levantar. Estos
quedan definidos por sus coordenadas polares. Se utiliza en levantamientos en
los que no es necesario el cambio de posición de la estación total.

Método de itinerario (poligonación)

Basado en la medida de ángulos y distancias. Es utilizado cuando el edificio
a medir es muy extenso. Primero definiremos una serie de estaciones dispuestas
en un recorrido de tal manera que desde cada una de ellas podamos ver la
estación anterior y posterior. Este recorrido arranca y termina en la misma
estación cuyas coordenadas estarán prefijadas, en el caso de la poligonal
cerrada. También tenemos el caso de la poligonal abierta.

Método de intersección

Basados en la medida de ángulos, permite obtener coordenadas de uno o
varios puntos apoyándonos en otros vértices con coordenadas determinadas en
fases previas, la aplicación fundamental consiste en permitir la densificación de
redes existentes.

Para resumir, la medición con teodolito o estación total, nos proporciona los
resultados en coordenadas cartesianas y nos permite pasar la información a un
sistema CAD y obtener finalmente documentos gráficos por medios de un
plotter que nos dibujará con gran rapidez y precisión todos los puntos sobre el
papel. Igualmente podremos continuar la realización de todo el dibujo del
levantamiento mediante el propio CAD.

Errores comunes cometidos en mediciones topográficas

En cualquier medición siempre se va a generar algún grado de error, que es
toda medida que no se ajusta o sea igual a la distancia real.

La causa de los errores puede agruparse en tres grupos:

Errores instrumentales. Toma de medidas erróneas (tanto ángulos como
distancias), debido a la mala calibración de los aparatos o por desgaste de los
componentes.

Errores personales. Son los errores asociados a limitaciones en los sentidos,
especialmente de la pérdida de la agudeza visual. La mayoría de equipos

Daniel Almagro Caballero de León 19
Universidad de Extremadura

<!-- p. 20 -->

Máster Universitario de Especialización en
Geotecnologías Topográficas en la Ingeniería.

Análisis de métodos para el Levantamiento Arquitectónico. Escuela Politécnica

ópticos permite realizar ciertos ajustes para garantizar una buena visión, si el
problema visual es muy acusado, se van a presentar errores por la
imposibilidad de leer adecuadamente el instrumento.

Errores por factores atmosféricos. En este caso se tienen la lluvia, el viento y
la más importante la temperatura.

Añadiendo más información, se puede decir que un error es negativo cuando
la medida obtenida, bien sea de distancias o ángulos, está por debajo de lo real.
Se dice que es positivo cuando la medida está por encima de lo real.

Otra forma de agrupar los errores es por la tipología, en lugar de la causa
como se ha visto en el párrafo anterior:

Errores sistemáticos. Son aquellos que se repiten por igual a lo largo de todo
el conjunto de mediciones. Estos están asociados a imperfecciones o a
descalibración de los instrumentos.

Errores accidentales. Estos están asociados a los encargados de realizar las
mediciones, sin embargo, tienen la condición que no se cometen por negligencia
de los operarios sino por causas que éstos no pueden eliminar de las mismas.
Por esto a este tipo de errores se les denomina fortuitos. El más común es el
que tiene que ver con la falta de agudeza visual, esto quiere decir que no se
reconocen con claridad las separaciones de las cintas, por ejemplo, los
milímetros dando como resultados errores de lectura.

Es importante definir dos conceptos asociados al concepto de error: Precisión
y exactitud. Estos dos conceptos son universales, es decir, son válidos para
cualquier método de medición que utilicemos y que pretendamos calcular su
error. Por ello, en los demás métodos haremos referencia a este apartado
cuando sean nombrados.

Precisión. La precisión representa la posibilidad de repetición entre varias
medidas de la misma cantidad, es decir, está asociado a la posibilidad de contar
con instrumentos bien calibrados que para varias medidas entreguen el mismo
valor. Otra manera de describirla: es una indicación de la proximidad entre las
observaciones a sus valores verdaderos. Cuanto más alejado está una
observación de su verdadero valor, menos exacta es.

En medidas lineales, es decir de distancias, se puede expresar el grado de
precisión con la relación:

1
𝑃𝑟𝑒𝑐𝑖𝑠𝑖ó𝑛= 𝐾= 1: 𝐾

Daniel Almagro Caballero de León 20
Universidad de Extremadura

<!-- p. 21 -->

Máster Universitario de Especialización en
Geotecnologías Topográficas en la Ingeniería.

Análisis de métodos para el Levantamiento Arquitectónico. Escuela Politécnica

Donde K, es la medida en la cual se comete un error de tipo unitario. Es
decir, cuando se tiene una precisión de 1:5000, quiere decir que por cada 5000
metros se comete un error de 1 metro, obsérvese que se colocan las mismas
unidades a cada lado, de esta forma podría leerse igualmente que por cada 5000
milímetros se comete un error de 1 milímetro.

Para la mayoría de los levantamientos topográficos, se han definido grados
de precisión recomendados. Estos valores deben compararse con los valores
obtenidos en campo, debiéndose conservar siempre que la precisión en campo
sea mayor o igual que la precisión recomendada.

Cuando se trata de medidas angulares, se ha definido el error de cierre, en
este caso angular, solo para poligonales cerradas, en este caso el error de cierre,
impide que la figura cierre, es decir que al graficar los datos de campo no se
puede generar una poligonal cerrada.
Precisión
Tipo de levantamiento Precisión lineal (1: K)
angular
Preliminar 1:1000 1.5√𝑛
Común con buena precisión 1:3000 1"√𝑛∗
Precisión alta para trabajo en ∗
1:5000 30"√𝑛ciudad
Máxima precisión 1:10000 15"√𝑛∗
Tabla 1. Precisión recomendada para levantamientos topográficos.
Fuente: Pérez (1999: 281 – 282)

El error poligonal de cierre se define como la diferencia entre la suma de los
ángulos internos de la poligonal medidos en campo y la suma teórica de los
ángulos internos de la poligonal. La suma teórica de los ángulos internos de
una poligonal cerrada viene dada por la siguiente expresión:

Σ 𝑡𝑒ó𝑟𝑖𝑐𝑎= 200(𝑛−2)

Donde n, representa el número de lados de la poligonal. Por ejemplo, un
triángulo, presenta tres lados, luego la suma de ángulos internos interna teórica
es:

Σ teórica = 180(𝑛−2) = 200(𝑛−2)

Σ teórica = 180(3 −2) = 200 (𝑛−2)

Σ teórica = 180 = 200

Daniel Almagro Caballero de León 21
Universidad de Extremadura

<!-- p. 22 -->

Máster Universitario de Especialización en
Geotecnologías Topográficas en la Ingeniería.

Análisis de métodos para el Levantamiento Arquitectónico. Escuela Politécnica

Exactitud. Se puede definir exactitud, como el acercamiento al valor real de
lo que se mide, bien sea distancia o ángulo. O de otra manera, la precisión se
refiere a la proximidad entre las observaciones repetidas de un mismo
fenómeno. Si las observaciones están próximas entre ellas (reunidas), entonces
se dice que han sido obtenidas con mucha precisión.

Esto quiere decir que la precisión no implica exactitud, es decir un equipo
mal calibrado puede dar la misma medida en varias repeticiones (precisión),
aunque esta no se acerque al valor real (exactitud), (DATATECA, 2016).

Generalmente, se suele hablar únicamente de precisión, pero está es una
medida relativa de la calidad de los datos. Un dato puede ser muy preciso, pero
no exacto: si las observaciones están agrupadas, pero entorno a un valor que es
diferente al real. De forma que este dato puede no ser útil para algunos
propósitos.

De la misma forma, un conjunto de observaciones puede ser exacto, pero no
preciso; si están distribuidas alrededor del valor real, pero dispersas.

Por último, el caso óptimo, es aquel en el que las observaciones son precisas
y exactas, si están agrupadas en un entorno reducido del valor real.

Figura 1. Concepto gráfico sobre exactitud y precisión. Fuente:
https://instrumentacionelectronicai.wordpress.com/tag/exactitud/

3.3. MÉTODOS FOTOGRAMÉTRICOS

Hoy día la fotografía es un campo de aplicación muy importante en la
documentación arquitectónica.

Daniel Almagro Caballero de León 22
Universidad de Extremadura

<!-- p. 23 -->

Máster Universitario de Especialización en
Geotecnologías Topográficas en la Ingeniería.

Análisis de métodos para el Levantamiento Arquitectónico. Escuela Politécnica

La fotogrametría, como ya hemos explicado anteriormente, es un sistema de
medición basado en el uso de fotografías. Se apoya en los mismos principios
que los sistemas topográficos, es decir, determinar direcciones en el espacio y
definir mediante ellas la posición de determinados elementos de un objeto o
edificio.

Por lo tanto, podremos definirla como aquella técnica que permite medir
objetos, edificios o la misma superficie terrestre, a partir de imágenes
perspectivas obtenidas por procedimientos fotográficos. Se rige por principios
geométricos y matemáticos por lo que es una técnica rigurosa y precisa.

Son muchas las aplicaciones que podemos encontrar en la fotogrametría
terrestre, por citar algunas de ellas:
 Levantamientos en general
 Estructuras arquitectónicas
 Cuevas
 Estatuas
 Excavaciones
 Relieves
 Mosaicos
 Estudios de deformaciones

Técnicas de la fotogrametría

Los diferentes tipos de fotogrametrías que existen son:

La fotogrametría analógica, surge en la década de los 30 basada en aparatos
de restitución y la responsable de la realización de la mayoría de cartografía
mundial.

La fotogrametría analítica, aparece en 1957 como un desarrollo natural de la
interrelación entre los aparatos restituidores analógicos y el surgimiento de la
computación. En ella, la toma de información es analógica y el modelado
geométrico es matemático.

La fotogrametría digital, desarrollada en los 80-90, se basa, como su nombre
indica, en la utilización de imágenes digitales o numéricas. Una imagen digital
es simplemente un mapa de píxeles, es decir, un mosaico de pequeños
cuadrados, tal como se nos aparecen en el monitor del ordenador, que se
almacena de forma digital, mediante número. Existen dos procedimientos para
la obtención de imágenes digitales. Uno, el más rápido y sencillo, consiste en
utilizar una cámara digital formando de esa manera la matriz numérica
directamente. El otro sistema, algo más lento, consiste en obtener una imagen
fotogramétrica normal y digitalizarla mediante un scanner.

Daniel Almagro Caballero de León 23
Universidad de Extremadura

<!-- p. 24 -->

Máster Universitario de Especialización en
Geotecnologías Topográficas en la Ingeniería.

Análisis de métodos para el Levantamiento Arquitectónico. Escuela Politécnica

Cámaras utilizadas en fotogrametría

El tipo y modelo de cámara fotográfica, la lente y su calibración, son factores
que afectan de forma importante a la calidad de medida en fotogrametría,
principalmente porque conforman el sistema de entrada de datos en el proceso
fotogramétrico. La bibliografía recoge tres tipologías de cámaras diferentes: las
métricas, las no métricas y las semimétricas. (Lerma García, 2002).

Las cámaras métricas permiten recrear la orientación interna de cada
fotograma mediante el empleo de marcas fiduciales o sensores de estado sólido
calibrados, es decir, garantizan la posición de los puntos principales sobre la
imagen. Nos permite reconstruir la geometría al momento de la toma
fotográfica eliminando, de esta forma, la fase de calibración.

Cámaras no métricas (cámaras digitales convencionales) se caracterizan por
tener una geometría interna desconocida, por lo que se hace necesaria la
determinación de los parámetros de calibración (orientación interna)
simultáneamente con el trabajo. Las ventajas respecto a las cámaras métricas
son su tamaño y peso reducido, la capacidad de utilizar objetivos
intercambiables, facilidad de compra y menor precio.

Por último, algunos autores han empleado cámaras semimétricas. Se trata de
una conversión de una cámara no métrica a métrica mediante, generalmente, la
incorporación de una placa de Roseau, es decir, una placa de vidrio que tiene
grabada una retícula calibrada de cruces que se impresionan sobre la fotografía
y que permiten controlar y corregir las deformaciones de la imagen que se
producen por alteraciones dimensionales en su soporte. A pesar de que la
geometría interna de las cámaras comerciales convencionales no métricas es
generalmente inestable, sobre todo de las lentes (R Wackrow, 2008), el
desarrollo de la informática en los últimos años y la aparición de software de
calibración ha supuesto la sustitución de las cámaras métricas y semimétricas

Fotogrametría digital

La fotogrametría digital se basa, como su nombre indica, en la utilización de
imágenes digitales o numéricas. Una imagen digital es simplemente un mapa
de píxeles, es decir, un mosaico de pequeños cuadrados, tal como se nos
aparecen en el monitor del ordenador, que se almacena de forma digital,
mediante número.

El procedimiento para la obtención de imágenes digitales es rápido y
sencillo. Consiste en utilizar una cámara digital formando de esa manera la
matriz numérica directamente.

Errores cometidos en mediciones fotogramétricas

Daniel Almagro Caballero de León 24
Universidad de Extremadura

<!-- p. 25 -->

Máster Universitario de Especialización en
Geotecnologías Topográficas en la Ingeniería.

Análisis de métodos para el Levantamiento Arquitectónico. Escuela Politécnica

Como ya se comentó en el punto 3.2., exactamente en los errores comunes en
el método topográfico, los aspectos del dato según la fuente son: Exactitud,
precisión y, en este apartado añadimos, fiabilidad. La calidad de los datos y de
los resultados que con ellos se obtienen se mide según éstos tres parámetros.

Uno de los aspectos no desarrollados en el apartado anterior es la fiabilidad,
concepto que también es aplicable a cualquier método de medición. La
fiabilidad se puede medir mediante dos aspectos, el primero es, hasta qué
punto un pequeño error (grosero) en las observaciones puede ser detectado con
una probabilidad determinada, y segundo, el efecto que este error puede tener
en los resultados. El primero se conoce como fiabilidad interna, y al segundo
como fiabilidad externa.

Continuando con el análisis de los errores de medición, se puede dar una
estimación de la precisión utilizando medidas estadísticas de la dispersión. Las
más utilizadas son la varianza o su raíz cuadrada y la desviación estándar.

Media,

𝛴𝑖=1𝑛 𝑥𝑖 𝑥̅ = . 𝑛

Varianza,

𝑛
∑ 𝑖=1 (𝑥𝑖−𝑥̅)2 𝛿2 = . 𝑛

Desviación estándar es la raíz cuadrada de la varianza.

Otras medidas de la precisión se obtienen utilizando otros estadísticos que
mencionamos a continuación:

Peso: cuanto mayor es la precisión, menor es la varianza. El peso se define
como la cantidad que es inversamente proporcional a la varianza, para
variables independientes e incorreladas. La nombramos, pero no será utilizada.

Precisión relativa: es un índice de las medidas de la precisión, generalmente
la desviación estándar, en relación a la cantidad medida o estimada. Por
ejemplo, si una distancia “s” ha sido medida con una desviación estándar
entonces, la precisión relativa es: el cociente de la desviación estándar 𝜎𝑠 partida
la distancia s.

⁄ Precisión relativa = 𝜎𝑠𝑠

Daniel Almagro Caballero de León 25
Universidad de Extremadura

<!-- p. 26 -->

Máster Universitario de Especialización en
Geotecnologías Topográficas en la Ingeniería.

Análisis de métodos para el Levantamiento Arquitectónico. Escuela Politécnica

Error medio cuadrático: se aplica cuando se dispone de los valores reales, de
forma que pueden compararse con las observaciones.

𝛴(𝑋𝑂−𝑋𝑉)2
𝐸𝑀𝐶=
𝑛

Donde,

𝑥0 es el valor observado

𝑥𝑣 es el valor verdadero

n es el número de observaciones

Estos índices de la calidad de los datos de pueden aplicar de igual forma
para dar una indicación de la calidad de MDT.

La precisión admitida según algunos estudios revisados (García-Leónet al,
\2014) (Ortiz Ortiz et al, 2010) (Souto Vidal et al, 2015), ya que no hay normativa
que regule los levantamientos ni los estudios de este tipo hechos con
fotogrametría, pueden ser admitidos tolerancias de milímetros. Para unos de los
trabajos revisados (Souto Vidal et al, 2015) con fotografías realizadas a
distancias de 10 y 20 m los errores medios dados están entorno a los 20 mm,
precisión que puede limitar la aplicabilidad cuando se precisan escalas
superiores a 1:100. Estos errores se dan con algunos softwares libres que se
pueden utilizar descargando su programa de Internet de forma gratuita. En
otros casos y con software mucho más precisos (García-León et al, 2014) se
pueden alcanzar tolerancias por debajo de los milímetros, de esta forma se
pueden realizar trabajos con precisiones en las medidas más que suficientes
para realizar planos a escalas mayores de 1:100.

3.4. MÉTODOS AVANZADOS: ESCÁNER LASER 3D

Sobre el año 2000 empezaron a utilizarse las estaciones totales con medida
directa de distancia, gracias al láser eran capaces de medir distancias sin
necesidad de emplear prisma reflectante. Más adelante empezaron a incorporar
servomotores, cosa que dio lugar a las estaciones totales robotizadas, y más
adelante al láser escáner, que como el resto de instrumental topográfico de uso
corriente en la actualidad se beneficia de las últimas mejoras en la electrónica de
la medida de distancias, tanto en precisión como en velocidad.

Mecánica del láser escáner

Daniel Almagro Caballero de León 26
Universidad de Extremadura

<!-- p. 27 -->

Máster Universitario de Especialización en
Geotecnologías Topográficas en la Ingeniería.

Análisis de métodos para el Levantamiento Arquitectónico. Escuela Politécnica

El láser escáner consta de dos componentes básicos:

 Un dispositivo de medida de distancias, el láser.

 Un mecanismo de barrido, es decir, un sistema motorizado de espejos que
desvía el láser procedente del distanciómetro en las direcciones verticales
y horizontales.

Provisto de este equipamiento, el escáner es capaz de medir la distancia de
una gran cantidad de puntos, obteniendo al mismo tiempo datos referidos a los
ángulos y al valor de la reflectancia de las distintas superficies impactadas con
el láser. Con los valores angulares y la distancia registrados, se podrán calcular
las coordenadas tridimensionales – x, y, z – de cada uno de esos puntos.

Figura 2. Esquema básico del funcionamiento de un láser-escáner. Fuente: García et al. (2011). Láser escáner
y nubes de puntos. Un horizonte aplicado al análisis arqueológico de edificios.

Los equipos existentes de escáner láser tienen diversas características. Aquí
diferenciamos si van montados sobre plataforma móvil o no, por ello, podemos
diferenciar, primeramente, podemos hablar de unidades dinámicas (LiDAR,
Mobile Mapping, etc.). En segundo lugar, podemos hablar de unidades
estáticas. Las unidades estáticas son las utilizadas habitualmente en
arquitectura y que a su vez se clasifican (según el sistema de medición de
distancias) en escáneres basados en la medida del tiempo y escáneres basados
en la medida de una triangulación (García et al, 2011).

La nube de puntos

La nube de puntos es el producto del trabajo realizado con el escáner láser, y
su definición no es otra que un conjunto de puntos en un sistema de
coordenadas tridimensional.

Daniel Almagro Caballero de León 27
Universidad de Extremadura

<!-- p. 28 -->

Máster Universitario de Especialización en
Geotecnologías Topográficas en la Ingeniería.

Análisis de métodos para el Levantamiento Arquitectónico. Escuela Politécnica

Otros enunciados que entran en más detalle especifican que las nubes de
puntos están compuestas por “miles de mediciones individuales en un sistema
de coordenadas (x, y, z), que en sí mismas componen un modelo tridimensional
de los objetos registrado, aunque como tal conjunto puntos sin procesado
posterior, son un modelo muy simplificado que opera sólo visualmente, pues se
compone únicamente de entidades singulares de tipo de punto” (Mañana et al,
2008).

Un modelo de nube de puntos no es más que una copia virtual del edificio,
compuesto por puntos cuya captura ha sido realizada de forma altamente
automatizada. De este modelo, la exactitud y la calidad con la que se realice está
limitada por los errores inherentes al instrumental de medida y a los métodos
de observación, además de la buena o mala distribución de las tomas. Para
poder conseguir un registro lo más fiable posible será necesario atender a dos
cuestiones clave: la resolución y la reflectividad.

La resolución: con ello nos referimos al nivel de detalle del trabajo. Para ello,
tenemos que tener en cuenta la finalidad del trabajo y el nivel de detalle que
necesitamos. También que a mayor detalle más tiempo de escaneo, mayor
tamaño de los ficheros y mayor volumen de datos a manejar. A esto debemos
sumar que debemos saber la precisión máxima que puede ofrecer el
instrumental que vamos a utilizar.

La reflectividad: cuando el láser impacta en la superficie de un objeto, una
parte de la energía del haz de luz es absorbida por el material que lo compone,
y otra parte es reflejada al medio original. Ésta última es la que tiene que
detectar el escáner para calcular la distancia. Cuanto mayor sea la intensidad de
la señal de retorno, más precisa será la distancia medida. De la reflectividad
dependen las características del material (rugosidad y color) y las condiciones
geométricas de la observación, ya que en distancias largas y ángulos escorados
aumenta el ruido de la señal. La geometría perfecta se consigue cuando
colocamos la dirección del haz del láser perfectamente perpendicular a la
superficie.

Modelo 3D. Errores del sistema

Una vez obtenida la nube de puntos la procesaremos y depuraremos para
tener un resultado fiable de la geometría del objeto de estudio y así poder
elaborar productos derivados de éste. Una buena georreferenciación de los
escaneos es fundamental para componer el modelo final.

En este apartado hablaremos sobre los errores instrumentales y el depurado
de las nubes de puntos.

Daniel Almagro Caballero de León 28
Universidad de Extremadura

<!-- p. 29 -->

Máster Universitario de Especialización en
Geotecnologías Topográficas en la Ingeniería.

Análisis de métodos para el Levantamiento Arquitectónico. Escuela Politécnica

Por ello, comenzamos diciendo que la precisión de los instrumentos es finita
y muy difícil de determinar, ni siquiera las mismas empresas suministradoras
de los equipos láser son capaces de facilitar datos seguros.

La precisión de un instrumento está asociada a la apreciación (la unidad de
magnitud mínima que puede detectar) y la exactitud a la calidad de la
calibración.

También existen errores que no dependen del mecanismo del instrumento de
detección remota, es decir, agentes externos como pueden ser las condiciones
ambientales y las características del objeto que se mide. Las fuentes de error
pueden descomponerse en dos grupos:

Erros debidos al diámetro del láser. El láser no es infinitamente delgado por
lo que al incidir en una arista puede reflejarse en dos planos diferentes
devolviendo dos distancias diferentes. En ambientes de mucha humedad o
polvo, el láser puede reflejarse incluso en partículas en suspensión.

Errores debidos a la reflexión de la señal. La medida de distancia depende
de la calidad de la señal reflejada, que depende de varios factores:
 Las condiciones atmosféricas. Cuando la temperatura y la presión están
en condiciones extremas puede variar la velocidad del pulso láser.
 Los ángulos de incidencia. El ángulo de incidencia que mejor refleja el
pulso láser es el perpendicular a la superficie escaneada.
 El nivel de reflectividad de los materiales. Los materiales claros reflejan
mejor la señal que los oscuros.

Todos estos errores son sistemáticos, pero también pueden considerarse
accidentales ya que combinados entre ellos no se repiten en una magnitud
conocida. Pero en cualquier caso estamos obligados a eliminar o corregir los
puntos con errores más evidentes. Para ello existen programas ad hoc que se
sirven de algoritmos para examinar cada punto del escaneo y comprobar si
cumplen con las condiciones de calidad establecidas.

Por otra parte, también es necesario hablar sobre la georreferenciación y
propagación de errores.

Al documentar por completo un edificio casi siempre son necesarios varios
posicionamientos del escáner para registrar todas las partes del inmueble. Por
ello, si las especificaciones de nuestro escáner nos dicen que tiene un cierto
error, en cada posicionamiento se irían sumando, pero normalmente estos
errores suelen producirse tanto por exceso como por defecto por lo que al final
tienden a compensarse.

Daniel Almagro Caballero de León 29
Universidad de Extremadura

<!-- p. 30 -->

Máster Universitario de Especialización en
Geotecnologías Topográficas en la Ingeniería.

Análisis de métodos para el Levantamiento Arquitectónico. Escuela Politécnica

Cada escaneo que realizamos tiene un sistema de coordenadas relativo, por
lo que cada uno de ellos debe de contar con referencias comunes que permitan
encajar unas nubes de puntos con otras y conocer las coordenadas de estas
referencias para poder orientar el levantamiento al sistema de coordenadas
absoluto.

La propagación de errores debido a la georreferenciación tiene que ser
analizada para ver las causas de las incertidumbres que intervienen:

 Primero, cuantas mediciones han sido necesarias para alcanzar la
magnitud final.

 Segundo, con qué desviaciones se ha realizado cada una (según el método
o los instrumentos empleados).

 Tercero, cuál es el sentido de transmisión de los errores (longitudinal o
perpendicular).

Casi se puede asegurar que las precisiones milimétricas de las que se habla
en el campo del escáner láser son inalcanzables en la mayoría de los trabajos.

El modelo resultante de la georreferenciación

La información que recoge el láser escáner se compone de simples valores
numéricos que son los que definen las características de cada punto medido (los
valores de posición x, y, z, los valores de intensidad y, en su caso, los valores
RGB). El software es el que luego lee y traduce esos valores generando a partir
de ellos la representación gráfica que observamos en la pantalla.

Gestión de los archivos de nube de puntos

Primeramente, en el procesado se realizan las fases de importación de la
nube, filtrado de puntos y unión de los escaneos (que se realizarán con el
software que proporciona el fabricante del escáner. A continuación, en función
del tipo de análisis que se pretenda, será preciso que los escaneos tengan una
mayor o menor resolución, lo que repercutirá directamente en el tamaño del
fichero.

Productos

Todos los productos que es posible extraer de un modelo de nube de puntos,
plantas, secciones, vistas, etc. hacen que la información geométrica referente a
un edificio sea más comprensible y manejable, pero a la vez menos exactas

Daniel Almagro Caballero de León 30
Universidad de Extremadura

<!-- p. 31 -->

Máster Universitario de Especialización en
Geotecnologías Topográficas en la Ingeniería.

Análisis de métodos para el Levantamiento Arquitectónico. Escuela Politécnica

debido a que los procesos para obtenerlos implican varias transformaciones de
los datos.

A continuación, se comenta brevemente la diferencia de levantar un edificio
con estación total o con escáner láser.

 En el primer caso, los datos originales son sólo aquellos referentes a la
x, y, z, de los puntos que se han medido con el equipo, estación total,
mientras que las polilíneas que conforman el modelo vectorial no son
otra cosa que interpolaciones que no tienen por qué responder a la
realidad salvo en los puntos extremos.

 En el segundo caso, en los levantamientos realizados con alta
definición, mediante escáner láser, es posible obtener productos sin
delinear, que respetan el dato original solo con diseccionar el modelo
de nube de puntos. Que una serie de puntos alineados parezcan una
línea continua es cuestión de escala.

3.5. CONCLUSIONES DE LOS MÉTODOS

Después de analizar los distintos métodos que existen hoy día para el
levantamiento arquitectónico, podemos decir que tenemos un amplio abanico
(métodos simples, estación total, fotogrametría, escáner láser) y que en la
mayoría de trabajos son utilizados de forma conjunta. De todos ellos, podemos
elegir el que cumpla los requisitos que necesitamos para nuestro trabajo.

Como requisitos podemos diferenciar una serie de aspectos como pueden
ser: el nivel de detalle requerido en el trabajo, la dificultad de la morfología del
objeto, rapidez del levantamiento, presupuesto disponible, medios disponibles.

De la variedad de métodos que tenemos en la actualidad, la realidad de
nuestra sociedad es que la mayor parte de técnicos y expertos relacionados con
la conservación del patrimonio cultural siguen empleando las técnicas de corte
tradicional. (Martínez Rodríguez, Evaluación en campo de una nueva técnica
fotogramétrica de rango cercano y bajo coste basada en la correlación
automática de imágenes., 2014). Esto es debido a la sencillez de su uso y coste,
pero implica la pérdida de información en la transferencia de datos del
elemento real al modelo y su precisión puede ser insuficiente (Yilmaz et al.,
2008). Por otra parte, los métodos topográficos, están limitados cuando el objeto
de estudio presenta formas irregulares no asimilables a formas geométricas
sencillas.

Daniel Almagro Caballero de León 31
Universidad de Extremadura

<!-- p. 32 -->

Máster Universitario de Especialización en
Geotecnologías Topográficas en la Ingeniería.

Análisis de métodos para el Levantamiento Arquitectónico. Escuela Politécnica

La obtención de documentación 3D con programas fotogramétricos tiene
muchas ventajas con respecto a los métodos tradicionales. Tienen mayor nivel
divulgativo o de archivo, salvaguarda el patrimonio histórico y cultural
permitiendo el trabajo distribuido y ahorra costes de desplazamiento para el
estudio y planificación de las intervenciones (Martínez Rodríguez, 2014).

A diferencia de los modelos teóricos o idealizados obtenidos mediante
métodos tradicionales, los métodos fotogramétricos o de escáner láser 3D
reproducen la morfología real del objeto con todas sus irregularidades.
Además, obtener modelos digitales permite generar productos derivados como
restituciones 2D o 3D muy precisas, que son muy útiles a la hora de acometer
obras de rehabilitación o restauración en edificios históricos que en ocasiones
carecen incluso de planos arquitectónicos originales (Martínez Rodríguez,
2014).

A día de hoy, en el caso de levantamientos arquitectónicos del patrimonio el
escáner láser sigue dominando fuertemente debido a su alta captación de datos,
su precisión relativamente elevada y la alta densidad de datos espaciales.
Aunque hay que tener presente que para la documentación de elementos de
grandes dimensiones se utiliza al uso combinado de levantamientos
topográficos de precisión y técnicas fotogramétricas junto al láser escáner 3D
(García-León et al, 2014).

Hay que tener en cuenta que el fuerte desarrollo que están teniendo los
programas fotogramétricos en los últimos años y el nivel de precisión que están
obteniendo junto con la velocidad de adquisición de datos y su bajo coste
(Fernández et al, 2012), éstos pueden desbancar a láser escáner 3D en un futuro
próximo.

Tras realizar esta revisión de trabajos y métodos sobre levantamientos
arquitectónicos, el presente trabajo fin de Máster se centrará en evaluar una de
las metodologías con más visión de futuro, la fotogrametría terrestre o de objeto
cercano.

El siguiente punto desarrolla un caso práctico sobre unos de los edificios de
la Escuela Politécnica de Cáceres.

Daniel Almagro Caballero de León 32
Universidad de Extremadura

<!-- p. 33 -->

Máster Universitario de Especialización en
Geotecnologías Topográficas en la Ingeniería.

Análisis de métodos para el Levantamiento Arquitectónico. Escuela Politécnica

\4. CASO PRÁCTICO
COMPARACIÓN DE SOFTWARES FOTOGRAMETRICOS
APOYADOS EN PUNTOS TOMADOS CON ESTACIÓN TOTAL
Y FLEXÓMETRO

Tras analizar los diferentes métodos de levantamiento arquitectónico y
habernos decantado por el levantamiento fotogramétrico como el más
interesante y potencial hoy día, vamos a realizar un estudio de comparación y
de fiabilidad de cuatro softwares fotogramétricos más conocidos en la
actualidad para llevar a cabo dicho trabajo.

El objeto arquitectónico seleccionado para realizar el levantamiento es el
edificio de Ingeniería de Telecomunicaciones de la Escuela Politécnica de
Cáceres de la universidad de Extremadura.

Figura 3. Fachada principal del edificio de Telecomunicaciones de Politécnica de la UNEX.

En una primera parte del caso práctico vamos a realizar un levantamiento de
fachada con estación total para obtener las medidas que tomaremos como reales
del edificio.

También disponemos de la medida tomada con flexómetro de la puerta
principal.

Después realizaremos los levantamientos con los distintos softwares
fotogramétricos explicando los pasos dados.

Tras realizar los modelos haremos un estudio y revisión de los datos
obtenidos.

Por último, discutiremos los resultados y sacaremos unas conclusiones del
trabajo llevado a cabo.

Daniel Almagro Caballero de León 33
Universidad de Extremadura

<!-- p. 34 -->

Máster Universitario de Especialización en
Geotecnologías Topográficas en la Ingeniería.

Análisis de métodos para el Levantamiento Arquitectónico. Escuela Politécnica

4.1. LEVANTAMIENTO TOPOGRÁFICO REALIZADO CON
ESTACIÓN TOTAL

En esta parte del TFM se va a explicar la realización del levantamiento de la
fachada principal y partes colindantes del edificio de telecomunicaciones de la
Escuela Politécnica de Cáceres con estación total para obtener medidas reales
con precisión milimétrica para su posterior comparación con los diferentes
softwares fotogramétricos seleccionados en el trabajo. No es necesario el
levantamiento completo del edificio por carecer de relevancia para la finalidad
del estudio.

Para realizar el levantamiento hemos tenido que estacionar en tres puntos,
bases topográficas, diferentes para poder obtener las medidas necesarias de la
fachada que nos interesan para el trabajo.

De esta manera, hemos hecho las correcciones de error pertinentes para
realizar un levantamiento fiable con dimensiones precisas para su posterior
comparación.

Por lo tanto, las coordenadas obtenidas han sido tanto planimétricas como
altimétricas, por lo que tenemos coordenadas tridimensionales de todos los
puntos.

En esta parte del proyecto, hay que decir, que nos apoyamos en un trabajo
realizado por alumnos de segundo curso del grado de Ingeniería de Edificación
de la Escuela Politécnica de Cáceres. De ello se han extraído los datos de campo
y se han depurado de manera que sean fiables para nuestro interés. Las reseñas
de las bases topográficas se pueden ver en el Anexo I del presente trabajo.

4.1.1. POLIGONAL

Material empleado:
\1. Estación total.

\2. Trípode.

\3. Prisma.

\4. Metro.

Metodología
Poligonales: las poligonales o itinerario, es una sucesión encadenada de
líneas, unidas mediante vértices, de los cuales se pretende obtener las
coordenadas planimétricas (X, Y), las altimétricas (H), y en la mayoría de los
casos ambas.

Daniel Almagro Caballero de León 34
Universidad de Extremadura

<!-- p. 35 -->

Máster Universitario de Especialización en
Geotecnologías Topográficas en la Ingeniería.

Análisis de métodos para el Levantamiento Arquitectónico. Escuela Politécnica

Lo primero que realizamos es la selección de las bases de la poligonal, las
cuales fueron tres, distribuidas para visualizar los puntos que nos interesan del
edificio. Una de ellas tiene coordenadas absolutas conocidas, pero que
obviaremos en nuestro trabajo por carecer de interés y dificultar un poco los
cálculos y su manejo.

Coordenadas absolutas del punto BT 1000, que corresponde con el punto
llamado E_A de coordenadas en el sistema de referencia propio (0,0,0) m, para
posibles trabajos posteriores:

Figura 4. Base topográfica BT 1000.

Desde A hay que visar al prisma situado en un punto, también de
coordenadas absolutas conocidas BT 1001 (X= 728564,210m, Y= 4373269,808m,
Z= 423,690m). Después visaremos a las bases B y C con ayuda del prisma,
subiéndolo o bajándolo si fuera necesario, al visar a una base anotamos el
ángulo horizontal y vertical y la distancia reducida en Círculo Directo y
anotamos lo mismo en Círculo Inverso (Regla de Bessel). También es necesario
apuntar la altura de la estación total i (en metros) y la altura que el prisma tenía
en cada base m (en metros).

Repetir este proceso estacionando en la base B y en la C.

Memoria de cálculos
Para el cálculo de la poligonal se ha hecho el promedio de los ángulos
horizontales, verticales y las distancias:

La distancia total de la poligonal es:

\- A-B: 26,251 m

Daniel Almagro Caballero de León 35
Universidad de Extremadura

<!-- p. 36 -->

Máster Universitario de Especialización en
Geotecnologías Topográficas en la Ingeniería.

Análisis de métodos para el Levantamiento Arquitectónico. Escuela Politécnica

\- B-C: 56,872 m

\- C-A: 39,892 m

Longitud total = 123,015 m

El error total máximo de una poligonal es el mayor de los dos: error
transversal o error longitudinal.
Error transversal
L ea(lh) + 1)(2n + 1) 123,015 21,55 + 1)(2 × 3 + 1)et = √2√n(n = √2√3(3 = n r 6 3 636620 6
\= 0,0073 m = 7,3 mm
 Error de verticalidad y de lectura.
S 40
ev = = = 3,33cc el = a = 10cc
12 12
 Error de dirección.
\+ ec 𝑐𝑐 ed = (ee ) × r = (0,025 × 636620 = 15,92 D 1000)
 Error de puntería.
10´´ 4A 10´´ 4 × 30
ep = (1 + = (1 + ) = 0´73´´ = 2,25cc A 100) 30 100
 Error angular.
ea = √ev2 + el2 + ed2 + ep2 = √10,282 + 102 + 15,922 + 2,252 = 21,55cc

Error longitudinal
ED 12,143
eL = √n = √3 = 14,872 mm
√2 √2
 Error máximo de la distancia.
ED = √ed2 + ee2 + es2 + ej2 = √5,242 + 22 + 102 + 42 = 12,143 mm
 Error de distancia a estación total.
ed = (5 mm + 3 ppm × 0,08) = 5,24 mm)
 Error de estación, de señal y de inclinación del jalón.
ee = 2 mm es = 1 cm = 10 mm ej = 4 mm

TOLERANCIA DEL CIERRE ACIMUTAL
Ta ≤ea(lh)√2√n = 21,52√2√3 = 52,713cc

TOLERANCIA EN DISTANCIAS
TD ≤eD√2 eD√2 = 12,143√2 = 17,173 mm
Error de cierre planimétrico
ecierre = √ex2 + ey2 √0,0062 + 0,0032 = 0,0067 m = 6,7 mm ≤14,872 mm

Daniel Almagro Caballero de León 36
Universidad de Extremadura

<!-- p. 37 -->

Máster Universitario de Especialización en
Geotecnologías Topográficas en la Ingeniería.

Análisis de métodos para el Levantamiento Arquitectónico. Escuela Politécnica

Por lo tanto, el error máximo de la poligonal es el error longitudinal, es decir,
14,872 mm. Si el error está dentro de tolerancia, que en este caso es así, se
compensa.

Cálculo de la poligonal
Lo primero de todo es calcular los valores promedios de Lh, Lv y Dr.

A continuación, se ha calculado el azimut y su error y como dicho error está
dentro de tolerancia se ha compensado.

Se calculan las coordenadas planimétricas parciales se han calculado los
incrementos de X e Y mediante las siguientes formulas:

∆𝑋𝐴𝐵= 𝐷𝑟𝐴𝐵sin 𝜃𝐴𝐵 ∆𝑌𝐴𝐵= 𝐷𝑟𝐴𝐵sin 𝜃𝐴𝐵

Una vez calculado los incrementos, calculamos las coordenadas absolutas de
cada vértice sumando los incrementos de coordenadas a vértice:

𝑋𝐵= 𝑋𝐴+ ∆𝑋𝐴𝐵 𝑌𝐵= 𝑌𝐵+ ∆𝑌𝐴𝐵

Para el cálculo de las coordenadas altimétricas primero se calcula los
desniveles con la siguiente fórmula:

∆𝑍𝐴𝐵= 𝑡+ 𝑖−𝑚

Y se calcula las coordenadas absolutas de cada vértice sumando los
incrementos de coordenadas a vértice:

𝑍𝐵= 𝑍𝐴+ ∆𝑋𝐴𝐵 𝑍𝐶= 𝑍𝐵+ ∆𝑋𝐵𝑐

En nuestro proyecto vamos a tomar la base A con las coordenadas (0, 0, 0) y
las demás estarán representadas en torno a ella. Sabiendo que sus coordenadas
absolutas son X=728624.380 m, Y=4373254.473 m, Z=423.780 m, (Figura 4).

El sistema de coordenadas se orientó tomando otro punto de sistema de
coordenadas absolutas Punto 2, X= 728564.210 m, Y= 4373269.808 m, Z= 423,690
m.

Daniel Almagro Caballero de León 37
Universidad de Extremadura

<!-- p. 38 -->

Máster Universitario de Especialización en
Geotecnologías Topográficas en la Ingeniería.

Análisis de métodos para el Levantamiento Arquitectónico. Escuela Politécnica

Figura 5. Fotografía aérea con situación de las bases topográficas empleadas en la toma de datos por
topografía.

La toma de datos y los cálculos de las coordenadas de la poligonal se pueden
consultar sus reseñas con más detalle en el ANEXO II.

4.1.2. RADIACIÓN

Material empleado.
\1. Estación total

\2. Trípode

\3. Prisma

\4. Metro

Metodología
Radiación: Es un método topográfico directo que permite determinar las
coordenadas (X, Y, Z) desde un punto fijo, “Polo de radiación”.

Para hacer esta parte del trabajo con estación total hay que seguir un método
muy similar al seguido en el apartado de poligonal.

Hay que estacionar en las bases y visar los puntos necesarios para dibujar la
planta del edificio que nos interesa y también hay que radiar los puntos de la
fachada principal que son objeto de las medidas de comparación con los
métodos fotogramétricos.

Para coger los puntos estacionamos en la base A, visamos a los puntos de
interés y anotamos los ángulos horizontales y verticales y la distancia reducida
en Circulo Directo. También hay que apuntar la altura de la estación total y la
altura del prisma, si se ha utilizado.

Daniel Almagro Caballero de León 38
Universidad de Extremadura

<!-- p. 39 -->

Máster Universitario de Especialización en
Geotecnologías Topográficas en la Ingeniería.

Análisis de métodos para el Levantamiento Arquitectónico. Escuela Politécnica

Realizaremos el mismo procedimiento estacionando en las otras dos bases, B
y C.
Memoria de cálculos
La toma de datos y el cálculo de este apartado se pueden consultar en el
ANEXO III.
Cálculo de la radiación
Cálculo de errores a priori:
El error total máximo de una radiación es el mayor de los dos: error
transversal o error longitudinal.
𝑒𝑎 (𝐿ℎ) 21,55
𝑒𝑡= 𝐷= 123,015 = 0.004164 𝑚= 4,164 𝑚𝑚 𝑟 636620

𝑒𝐿= √𝑒𝑑2 + 𝑒𝑒2 + 𝑒𝑠2 + 𝑒𝑗2 = √5,242 + 22 + 102 + 42 = 12,143 𝑚𝑚

Por lo tanto, el error máximo de la radiación es el error longitudinal, es decir,
12,143 mm.

Daniel Almagro Caballero de León 39
Universidad de Extremadura

<!-- p. 40 -->

Máster Universitario de Especialización en
Geotecnologías Topográficas en la Ingeniería.

Análisis de métodos para el Levantamiento Arquitectónico. Escuela Politécnica

4.1.3. PLANO DE PUNTOS RADIADOS

Daniel Almagro Caballero de León 40
Universidad de Extremadura

<!-- p. 41 -->

4.1.4. PLANO DE PUNTOS DE LA FACHADA PRINCIPAL

Puntos radiados desde A

Puntos radiados desde B

Puntos radiados desde C

<!-- p. 42 -->

Máster Universitario de Especialización en
Geotecnologías Topográficas en la Ingeniería.

Análisis de métodos para el Levantamiento Arquitectónico. Escuela Politécnica

4.1.5. PROCESADO DE LOS DATOS Y REPRESENTACIÓN EN 3D
CON AUTOCAD PARA TOMA DE MEDIDAS

Después de realizar el levantamiento y de calcular los datos tomados de cada
punto con la estación total, se ha procedido a realizar un plano en 3
dimensiones con AutoCAD. Gracias a esto tendremos los puntos visualizados y
en los que uniremos con líneas gracias a las herramientas de dicho programa
También podremos acotar las dimensiones que no son de interés con precisión
milimétrica para proceder a la comparación con las medidas que obtendremos
de los softwares fotogramétricos.

El procedimiento que se ha realizado ha sido el siguiente:

Primero, después de a haber obtenido todas las coordenadas en Excel, las
hemos unificado en mismo archivo, que hemos depurado primero con
Microsoft Word para poner la separación entre coordenadas con punto y coma.

Después de realizar esto lo hemos exportado como archivo con formato .txt y
lo hemos guardado con todas las coordenadas de los puntos, ejemplo de este
paso se muestra en la Figura 6.

Figura 6. Coordenadas de los puntos en un archivo de bloc de notas.

A continuación, hemos utilizado el programa Topocal, un software libre, que
nos ayuda dibujar los puntos en un espacio virtual. Este programa lo he
utilizado más bien para exportar los datos como .dxf para tratar mejor con
AutoCAD, ya que este programa está un poco limitado en la faceta de dibujo

Daniel Almagro Caballero de León 42
Universidad de Extremadura

<!-- p. 43 -->

Máster Universitario de Especialización en
Geotecnologías Topográficas en la Ingeniería.

Análisis de métodos para el Levantamiento Arquitectónico. Escuela Politécnica

asistido. Hemos importado los puntos en formato .txt separado con punto y
coma como se puede ver en la Figura 7.

Figura 7. Coordenadas de los puntos exportadas a Topocal.

En la Figura 8 se muestra una imagen de las coordenadas de los puntos
representadas en TOPOCAL.

Figura 8. Vista de los puntos en Topocal.

Este programa tiene la opción de exportar los datos como .dxf, así se hizo y
se abrió con el programa AutoCAD. El programa tiene la capacidad de
visualizar los puntos en 3D como se presenta en la Figura 9.

Daniel Almagro Caballero de León 43
Universidad de Extremadura

<!-- p. 44 -->

Máster Universitario de Especialización en
Geotecnologías Topográficas en la Ingeniería.

Análisis de métodos para el Levantamiento Arquitectónico. Escuela Politécnica

Figura 9. Vista de los puntos en 3D con el programa AutoCAD.

Después de familiarizarnos con la nube de puntos comenzamos a unirlos de
manera que fuera cogiendo forma la silueta del edificio. Los resultados de este
dibujo, que está escalado y del que se pueden tomar medidas exactas con
precisión milimétrica lo observamos en la Figura 10.

Figura 10. Vista en 3D del edificio delineado.

A continuación, vamos a representar el plano de alzado de la fachada con las
cotas, Figura 11, que serán objeto de comparación con las medidas obtenidas
con los softwares libres fotogramétricos.

Daniel Almagro Caballero de León 44
Universidad de Extremadura

<!-- p. 45 -->

Máster Universitario de Especialización en
Geotecnologías Topográficas en la Ingeniería.

Análisis de métodos para el Levantamiento Arquitectónico. Escuela Politécnica

Plano de alzado de la fachada principal del edificio de Telecomunicaciones.

Figura 11. Plano fachada principal con mediciones.

Medidas entre los puntos:

2-1 20.038 m

46-2 12.309 m

25-18 05.117 m

40-41 03.293 m

17-16 04.860 m

14-39 06.091 m
Tabla 2. Medidas obtenidas con la Estación Total.

 Entrada ppal. = 4.855 m

En la Tabla 2 tenemos las medidas seleccionadas de la fachada con precisión de
milímetros. Ahora realizaremos los levantamientos con los diferentes softwares
libres de fotogrametría seleccionados para este trabajo.

Daniel Almagro Caballero de León 45
Universidad de Extremadura

<!-- p. 46 -->

Máster Universitario de Especialización en
Geotecnologías Topográficas en la Ingeniería.

Análisis de métodos para el Levantamiento Arquitectónico. Escuela Politécnica

4.2. TOMA DE MEDIDA DE REFERENCIA CON FLEXÓMETRO

Gracias a mi tutora del TFM obtuve la medida de la entrada principal del
edificio tomada con flexómetro. Se midió a la altura del suelo y a un metro
sobre éste. La medida obtenida fue:

Ancho puerta principal = 4.820 m

4.3. LEVANTAMIENTOS ARQUITECTÓNICOS REALIZADO CON
PROGRAMAS FOTOGRAMÉTRICOS

El levantamiento va a ser realizado con programas fotogramétricos disponibles
en internet. Son fáciles de adquirir, algunos tienen una versión de prueba
gratuita y otros son completamente gratuitos. Algunos poseen la versión
profesional que permiten funciones más avanzadas pero que requieren un pago
para su adquisición. Los softwares seleccionados, son los siguientes:

 123D Catch de Autodesk. Empresa EEUU. También se encarga del
prestigioso software Autocad que además es líder en diseños 3D, publicó
en 2012 esta aplicación para dispositivos iOS, Android y ordenador.

http://www.123dapp.com/catch

 PhotoScan de Agisoft. Empresa Rusa. Fundada en 2006 como una
compañía de investigación innovadora con enfoque en la tecnología de
visión por ordenador. Esta empresa ha adquirido experiencia en
algoritmos de procesamiento de imágenes, con las técnicas de
fotogrametría digital, para el desarrollo de herramientas aplicadas.

http://www.agisoft.com/

 Pix4D. Empresa suiza. La compañía desarrolladora de este programa fue
fundada en 2011 en Lausana, Suiza y actualmente son el mayor
proveedor de software de procesado de imágenes para drones en la

Daniel Almagro Caballero de León 46
Universidad de Extremadura

<!-- p. 47 -->

Máster Universitario de Especialización en
Geotecnologías Topográficas en la Ingeniería.

Análisis de métodos para el Levantamiento Arquitectónico. Escuela Politécnica

industria, además de convertirse en un referente. Poseen oficinas en
Lausana, San Francisco y Shanghai (Ricardo, 2015).

https://pix4d.com/

 Visual SFM. Inventor es el ingeniero Changchang Wu, estudiante de la
universidad de North Carolina. EEUU. Este software tiene su origen en
la universidad de Seattle, cuyo y es una herramienta que nos permite
realizar modelos 3D a partir de imágenes en 2D.

http://ccwu.me/vsfm/

Todos estos programas trabajaban a través del sistema SFM y algunos los
combinan con las bases de la fotogrametría tradicional. …

En general, vamos a dividir los trabajos de levantamientos fotogramétricos en
dos partes, al igual que los trabajos topográficos, una será la sesión fotográfica o
trabajo de campo y la otra, la creación del modelo con el programa que es el
procesado fotogramétrico.

Daniel Almagro Caballero de León 47
Universidad de Extremadura

<!-- p. 48 -->

Máster Universitario de Especialización en
Geotecnologías Topográficas en la Ingeniería.

Análisis de métodos para el Levantamiento Arquitectónico. Escuela Politécnica

4.3.1. TRABAJO DE CAMPO

4.3.1.1. TOMA DE IMÁGENES

La toma de imágenes será común a todos los programas utilizados en el trabajo,
con ello partimos con unas mismas imágenes, es decir, un mismo trabajo de
campo para dejar a los programas comparados mostrar sus cualidades a la hora
de hacer el levantamiento tridimensional del edificio.

Vamos a tener una serie de consideraciones a la hora de tomar las fotografías
del objeto, en este caso parte del edificio de telecomunicaciones, ya que estos
softwares utilizan la combinación de imágenes del mismo elemento (SFM).
Estas son:

 Tener buena iluminación y homogénea, es decir, condiciones de luz
constantes. Lo óptimo es realizar la sesión de fotografiado en días
nublados y a primeras horas de la mañana para evitar sombras en las
fachadas del edificio. Estas pueden disminuir la calidad del modelo, ya
que el movimiento del sol hace que las posiciones de las sombras también
varíen en las imágenes dificultando su orientación (AGISOFT, s.f.).

 Usar la cámara sin flash y no alterar el zoom en ningún caso.

 Realizar un recorrido continuo alrededor del objeto y tomando las
imágenes con solape, es decir, que haya partes comunes entre las
imágenes correlativas.

 Deben evitarse objetos que se interpongan entre la cámara y el objeto. En
este caso, un par de coches entorpecieron el modelado de una parte del
edificio pero que no intercedían en la zona de toma de las medidas
comparativas.

 Al guardar las fotos en la carpeta se debe verificar que todas estén rotadas
en la misma posición. Así serán reconocidas mejor por el programa.

Vamos a nombrar unas recomendaciones para la toma de imágenes. Éstas
fueron presentadas por primera vez por Peter Whadausl y Cliff Ogleby en 1994,
la Regla 3x3 es una manera práctica de tomar imágenes para futuras
aplicaciones métricas usando la fotogrametría. Comité Internacional para la
documentación del Patrimonio Cultural (CIPA 3X3 Rules, 2014).

Son reglas sencillas para la toma de fotografía con cámaras no métricas.

3 reglas geométricas.

Daniel Almagro Caballero de León 48
Universidad de Extremadura

<!-- p. 49 -->

Máster Universitario de Especialización en
Geotecnologías Topográficas en la Ingeniería.

Análisis de métodos para el Levantamiento Arquitectónico. Escuela Politécnica

 Dotar de información de control.
 Recubrimiento fotográfico múltiple en rededor.
 Tomar par estereoscópico para restitución estereoscópica.

3 reglas fotográficas.

 La geometría interna debe mantenerse constante (no emplear zoom)
 Elegir una iluminación homogénea.
 Elegir la cámara más estable y de mayor formato disponible.

3 reglas de organización.

 Hacer croquis apropiados.
 Rellenar unos formularios adecuados.
 Realizar la comprobación final.

A continuación, se muestra en la Figura 12 cuál es la forma apropiada de
planificación del proceso de toma de imágenes.

FACHADAS (Incorrecto) FACHADAS (Correcto)

INTERIOR (Incorrecto) INTERIOR (Correcto)

OBJETO AISLADO (Incorrecto) OBJETO AISLADO (Correcto)

Figura 12. Esquema de toma de imágenes de objetos cercanos.

Daniel Almagro Caballero de León 49
Universidad de Extremadura

<!-- p. 50 -->

Máster Universitario de Especialización en
Geotecnologías Topográficas en la Ingeniería.

Análisis de métodos para el Levantamiento Arquitectónico. Escuela Politécnica

Fuente: http://www.agisoft.com/pdf/tips_and_tricks/Image%20Capture%20Tips%20-
%20Equipment%20and%20Shooting%20Scenarios.pdf

La toma de fotografías se realizó con dos cámaras:

 Cámara réflex digital, marca OLYMPUS, modelo E 330 y objetivo
OLYMPUS digital, 14-45mmm, 1:3.5-5.6. El sensor de imagen cuanta
con una resolución máxima de 7.94 megapíxeles.

Figura 13. Cámara Réflex Olympus.

 Cámara integrada en el móvil Huawei P8 Lite de 13,5 megapíxeles,
4160x3120 pixeles con autofocus.

Figura 14. Cámara de Smartphone Huawei P8 Lite.

Las fotografías que se han utilizado para hacer los modelados han sido las de
la cámara digital réflex, por dar mejores resultados. Se hicieron
reconstrucciones del modelo con fotografías tomadas con ambas cámaras y los
resultados se vieron claramente favorecidos con la utilización de ésta. El grupo
de lentes que monta la cámara réflex es obviamente mucho mejor que la cámara
del Smartphone siendo así los resultados también mejores.

4.3.2. PROCESADO DE LAS IMÁGENES

Flujo de trabajo de los programas fotogramétricos basados en SFM.

Daniel Almagro Caballero de León 50
Universidad de Extremadura

<!-- p. 51 -->

Máster Universitario de Especialización en
Geotecnologías Topográficas en la Ingeniería.

Análisis de métodos para el Levantamiento Arquitectónico. Escuela Politécnica

En general, el proceso de obtención del modelo 3D con los programas
fotogramétricos que se basan en SFM y en el algoritmo SIFT, explicados en el
estado del arte, tienen la siguiente secuencia (Pereira Uzal, 2016):

\1. Se añaden las fotografías realizadas al objeto.
\2. Se alinean y emparejan las fotografías.
\3. Reconstrucción de la nube de puntos discreta.
\4. Reconstrucción de la nube de puntos densa.
\5. Escalar y Georreferenciar.
\6. Texturizar. *
\7. Exportar nube de puntos. *
 Estos dos últimos pasos son opcionales y no necesariamente hay que
ejecutarlos para poder comparar los modelos.

Han sido necesarios tres ordenadores, todos ellos portátiles con diferentes
hardware y software para poder ejecutar y trabajar con los programas
fotogramétricos.

HP ProBook 4520s (Personal)
 Procesador Intel(R) Celeron® P4500 @ 1.87 GHz.
 Memoria instalada (RAM) de 3.00 GB (2.86 GB utilizables)
 Intel(R) HD Graphics 3000
 Sistema operativo Windows 7 Home Premiun de 32 bits.

ASUS (Facilitado)
 Procesador CPU: Intel(R) Core(TM) i3-2350M CPU @ 2.30GHz
 Memoria instalada (RAM) de RAM: 6GB
 Intel(R) HD Graphics 3000
 Sistema operativo Windows 7, 64-bit

MOUNTAIN ONYX 17 (Facilitado)
 Procesador CPU: Intel(R) Core(TM) i7-6700HQ CPU @ 2.60GHz
 Memoria instalada (RAM) de 16GB
 HD Graphics 530 NVIDIA GeForce GTX
 Sistema operativo Windows 7 Professional, 64-bit

4.3.2.1. LEVANTAMIENTO FOTOGRAMÉTRICO REALIZADO CON
EL PROGRAMA “123D CATCH DE AUTODESK”

El software fotogramétrico utilizado en este caso fue 123D Catch de
Autodesk, su versión original fue llamada Proyecto Photofly y fue lanzado en
\2011. Es un programa gratuito y muy fácil de manejar. Su funcionamiento está
basado en SFM, el cual determina de forma automática la orientación interna de
la cámara, por lo que no es necesario realizar la calibración de la cámara. Esta
Daniel Almagro Caballero de León 51
Universidad de Extremadura

<!-- p. 52 -->

Máster Universitario de Especialización en
Geotecnologías Topográficas en la Ingeniería.

Análisis de métodos para el Levantamiento Arquitectónico. Escuela Politécnica

orientación se realiza en el servidor propio del programa (la nube), una vez
subidas las fotografías, por ello la rapidez de la obtención del modelo depende
del volumen de datos y de la velocidad de conexión a Internet (Souto Vidal et
al, 2015).

CREACIÓN DEL MODELO

Una vez realizada la secuencia fotográfica, descargamos de forma gratuita de
su página web el programa y lo instalamos. (http://www.123dapp.com/catch)

Los pasos dados para obtener el modelo fueron los siguientes:

Iniciamos el programa y en la primera pantalla que nos muestra
seleccionamos la pestaña “Create a New Capture”, ver Figura 15.
Posteriormente, pedirá que te registre como usuario. Esta vez se realizó con
cuenta de la red social Facebook.

Una vez realizado esto, seleccionamos las fotografías, 29 en este caso, y
pulsamos en Create Project. Rellenamos una serie de información muy escueta
que nos pide y le damos a “Create”, Figura 15.

Figura 15. Pantalla principal 123D Catch.

Lo que hace en este momento es subir las fotografías a la nube, las procesa y
nos devuelve el modelo para que podamos visualizarlo en el programa, Figura
\16.

Daniel Almagro Caballero de León 52
Universidad de Extremadura

<!-- p. 53 -->

Máster Universitario de Especialización en
Geotecnologías Topográficas en la Ingeniería.

Análisis de métodos para el Levantamiento Arquitectónico. Escuela Politécnica

Figura 16. Procesado de imágenes en 123d Catch.

Una vez finalizado el proceso, tenemos el modelo en 3D como observamos
en la Figura 17, el cual tendremos que afinarlo, depurarlo y escalarlo en esta
secuencia. El programa fue capaz de orientar 29 de 29 imágenes (100%).

Figura 17. Visión 3D del edificio procesado con 123D Catch.

Para refinar el modelo y hacer que el resultado sea más preciso, el programa
tiene una opción que es chequear los puntos homólogos en cada imagen
manualmente. Esto es lo que vamos a realizar en este paso para obtener un
modelo de más calidad. Hay que identificar un mínimo de 4 puntos en cada
imagen para ayudar a que el programa regenere de nuevo el modelo con
calidad, Figura 18.

Daniel Almagro Caballero de León 53
Universidad de Extremadura

<!-- p. 54 -->

Máster Universitario de Especialización en
Geotecnologías Topográficas en la Ingeniería.

Análisis de métodos para el Levantamiento Arquitectónico. Escuela Politécnica

Figura 18. Chequeo manual de puntos homólogos en 123D Catch.

Hecho esto con cada fotografía volvemos a subir el modelo al servidor del
programa para que nos regenere con más fidelidad para, ahora sí, depurarlo, de
manera que nos quede la parte del modelo que nos interese y escalarlo con una
medida obtenida del levantamiento con estación total.

Lo primero lo realizaremos con dos herramientas que se llaman “Rectangular
Selection” y “Lasso Selection”, con las cuales iremos eliminando los trozos de
malla que no nos interesen, como se observa en la Figura 19.

Figura 19. Eliminación de puntos no relevantes en 123D Catch.

Por último, escalaremos el modelo con una herramienta que se llama “Define
Reference Distance”, primero hay que definir con dos puntos del modelo la
distancia a escalar, utilizar la herramienta y damos el valor a la distancia entre
esos dos puntos seleccionados, quedando así escalado el objeto tridimensional.

En todos los levantamientos utilizaremos como medida de referencia el
ancho de la entrada principal del edificio, obtenida mediante flexómetro, y cuyo
valor es de 4.82 metros.

Daniel Almagro Caballero de León 54
Universidad de Extremadura

<!-- p. 55 -->

Máster Universitario de Especialización en
Geotecnologías Topográficas en la Ingeniería.

Análisis de métodos para el Levantamiento Arquitectónico. Escuela Politécnica

Después de esto se acotaron las distancias comparativas de la fachada,
quedando el modelo como se muestra en la Figura 20.

Figura 20. Medida de los puntos objeto de estudio con 123D Catch.

Las dimensiones, se tomaron con la herramienta “Create Distance Measure”.

Las medidas entre los puntos es la que se muestra en la Tabla 1:

2-1 20.00 m

46-2 12.28 m

25-18 05.07 m

40-41 03.28 m

17-16 04.82 m

14-39 06.04 m
Tabla 3. Medidas obtenidas con 123D Catch.

Como podemos observar en la Tabla 1, la precisión del programa es
centimétrica a diferencia de la estación total que nos dio valores milimétricos.

Tenemos la opción de exportar el modelo con los puntos tomados a formato
.dwg, que posteriormente podemos abrir con un programa CAD, este caso
DraftSight y volver a tomar medidas. Ver Figura 21.

Daniel Almagro Caballero de León 55
Universidad de Extremadura

<!-- p. 56 -->

Máster Universitario de Especialización en
Geotecnologías Topográficas en la Ingeniería.

Análisis de métodos para el Levantamiento Arquitectónico. Escuela Politécnica

Figura 21. Medida de las distancias con DraftSight.

De esta manera tenemos más precisión en los valores de las medidas como se
muestra en la Tabla 2:

2-1 20.0005 m

46-2 12.2772 m

25-18 05.0726 m

40-41 03.2786 m

17-16 04.8204 m

14-39 06.0416 m
Tabla 4. Medidas obtenidas con AutoCAD tras ser importadas desde 123D Catch.

4.3.2.2. LEVANTAMIENTO FOTOGRAMÉTRICO REALIZADO CON
EL PROGRAMA ”PHOTOSCAN PROFESSIONAL DE
AGISOFT”

Agisoft PhotoScan es un programa que permite crear fácilmente modelos 3D
de formas complejas con textura de alta definición a partir de múltiples
imágenes, que pueden ser tomadas incluso con diferentes cámaras.

Principales características PhotoScan:

 Triangulación fotogramétrica

 La generación de nubes de puntos (escaso / denso)

Daniel Almagro Caballero de León 56
Universidad de Extremadura

<!-- p. 57 -->

Máster Universitario de Especialización en
Geotecnologías Topográficas en la Ingeniería.

Análisis de métodos para el Levantamiento Arquitectónico. Escuela Politécnica

 Generación de modelos poligonales (normal / textura)

 Ajuste del sistema de coordenadas

Estas son las más importantes entre muchas otras disponibles en la versión
profesional.

El objetivo del programa es virtualizar modelos 3D de objetos fotografiados
con cámara digital. Este objeto se consigue con tres pasos de procesamiento:

\1. .Definición de los términos y parámetros de orientación externa e
interna de las cámaras. En esta etapa PhotoScan encuentra puntos
comunes de las fotos y define todos los parámetros de las cámaras: la
posición, la orientación, geometría interna (distancia focal, los
parámetros de distorsión, etc.). Los resultados de esta fase son puntos
comunes de nubes dispersas en modelos 3D y los datos sobre la posición
y orientación de la cámara.
\2. Restauración de la geometría del objeto. En la segunda etapa PhotoScan
construye un modelo tridimensional poligonal, que describe la forma del
objeto. Aquí PhotoScan permite editar el modelo para eliminar zonas de
no interés, optimizar el modelo, crear marcas de puntos para poder
medir la distancia entre ambos.
\3. •Texturizado del objeto. La última etapa incluye texturizado y / o
construcción de ortofotos.

CREACIÓN DEL MODELO

Como se presenta en la Figura 22, al abrir el programa nos encontramos con
esta pantalla inicial con la que podemos empezar a trabajar:

Figura 22. Pantalla principal de PhotoScan.

Daniel Almagro Caballero de León 57
Universidad de Extremadura

<!-- p. 58 -->

Máster Universitario de Especialización en
Geotecnologías Topográficas en la Ingeniería.

Análisis de métodos para el Levantamiento Arquitectónico. Escuela Politécnica

Todos los pasos que se van a realizar son metódicos y consecutivos, y todos
parten de la pestaña de la barra superior de herramientas llamada "flujo de
trabajo".

Lo primero que vamos a realizar es añadir las fotografías al trabajo clicando
la pestaña "flujo de trabajo" y después "añadir fotos", ver Figura 23.

Figura 23. Selección fotografías para procesar con PhotoScan.

Una vez añadidas las imágenes, 29 en este caso, vamos a editarlas para que le
sea más fácil al programa recrear el modelo. Lo único que haremos será restar
de la foto el cielo visible en la imagen con la herramienta "varita mágica" que
posee el programa, ver Figura 24.

Figura 24. Selección del cielo para restar de la imagen con PhotoScan.

Ahora, se orientan las fotos y se crea una primera nube de puntos inicial del
modelo. El programa fue capaz de orientar las 30 imágenes (100%). La ventana
en la que seleccionar los parámetros de orientación se pueden ver en la figura
\25.

Daniel Almagro Caballero de León 58
Universidad de Extremadura

<!-- p. 59 -->

Máster Universitario de Especialización en
Geotecnologías Topográficas en la Ingeniería.

Análisis de métodos para el Levantamiento Arquitectónico. Escuela Politécnica

Figura 25. Ventana de parámetros para orientación de imágenes con PhotoScan.

Los resultados de este paso se observan en la Figura 26.

Figura 26. Resultado edificio 3D con PhotoScan.

El siguiente paso es "crear nube de puntos densas", ver en Figura 27.

Figura 27. Creación de nube de punto densa con PhotoScan.

En la Figura 28 se obtienen los siguientes resultados, en los que el modelo ya
tiene una geometría bastante realista del edificio.

Daniel Almagro Caballero de León 59
Universidad de Extremadura

<!-- p. 60 -->

Máster Universitario de Especialización en
Geotecnologías Topográficas en la Ingeniería.

Análisis de métodos para el Levantamiento Arquitectónico. Escuela Politécnica

Figura 28. Resultados nube de puntos densa con PhotoScan.

A continuación, depuramos el modelo eliminando puntos que no son
necesarios, ver Figura 29.

Figura 29. Depuración del modelo con PhotoScan.

Los siguientes pasos son "Crear malla..." (Figura 30) y "Crear texturas..."
(Figura 31) del modelo, uno a continuación del otro en el mismo orden dicho
anteriormente.

Figura 30. Crear malla con PhotoScan.

Daniel Almagro Caballero de León 60
Universidad de Extremadura

<!-- p. 61 -->

Máster Universitario de Especialización en
Geotecnologías Topográficas en la Ingeniería.

Análisis de métodos para el Levantamiento Arquitectónico. Escuela Politécnica

Figura 31. Crear textura con PhotoScan.

Los resultados de estos dos procesos Se muestran en la Figura 32 y 33.

Figura 32. Resultado tras mallar y texturizar el modelo con PhotoScan.

Figura 33. Modelo con medida tomadas en PhotoScan.

Este programa nos da la opción de poder importar puntos dentro de nuestro
modelo ya escalado y referenciado según nuestro sistema de coordenadas. Por
lo que hemos introducido todos los puntos que obtuvimos con la estación total.

En las siguientes Figuras, 34 y 35, vemos desde un plano de la planta del
edificio y otra desde el alzado de la fachada principal.

Daniel Almagro Caballero de León 61
Universidad de Extremadura

<!-- p. 62 -->

Máster Universitario de Especialización en
Geotecnologías Topográficas en la Ingeniería.

Análisis de métodos para el Levantamiento Arquitectónico. Escuela Politécnica

Figura 34. Vista superior del modelo con PhotoScan.

Figura 35. Vista de alzado del resultado final con PhotoScan.

Ya realizado el modelado completo de la parte del edificio objeto de estudio
realizamos las mediciones de comparación.

En la Tabla 3 se presentan las medidas entre los puntos para controlar los
resultados de calidad geométrica del modelo generado.

2-1 20.026 m

46-2 12.300 m

25-18 05.083 m

40-41 03.328 m

17-16 04.837 m

14-39 06.130 m
Tabla 5. Medidas obtenidas con PhotoScan.

Daniel Almagro Caballero de León 62
Universidad de Extremadura

<!-- p. 63 -->

Máster Universitario de Especialización en
Geotecnologías Topográficas en la Ingeniería.

Análisis de métodos para el Levantamiento Arquitectónico. Escuela Politécnica

4.3.2.3. LEVANTAMIENTO FOTOGRAMÉTRICO REALIZADO CON
EL PROGRAMA “PIX4D”

El software Pix4D es un procesador de imágenes que realiza mapeados y
modelados en 2D y 3D a partir de fotografías tomadas desde el aire mediante
drones o desde la Tierra mediante cámara digital.

El software se encarga de procesar automáticamente las imágenes obtenidas por
cualquier tipo de cámara digital, usando una tecnología basada puramente en
contenido gráfico. El procesado se puede utilizar además en una gran variedad
de programas de Diseño Asistido por Ordenador (CAD) y Sistemas de
Información Geográfica (SIG).

CREACIÓN DEL MODELO

Abrimos el programa, damos nombre al proyecto y ponemos la ubicación
donde queremos que se guarden los datos de éste. Ver Figura 36.

Figura 36. Pantalla principal programa fotogramétrico Pix4D.

El siguiente paso es seleccionar las fotografías con las queremos hacer el
levantamiento fotogramétrico. Cómo en los casos anteriores, seleccionamos 29
fotos del levantamiento realizado con la cámara digital Olimpus. Ver figura 37.

Daniel Almagro Caballero de León 63
Universidad de Extremadura

<!-- p. 64 -->

Máster Universitario de Especialización en
Geotecnologías Topográficas en la Ingeniería.

Análisis de métodos para el Levantamiento Arquitectónico. Escuela Politécnica

Figura 37. Selección de fotografías en Pix4D.

Nota: el programa detecta, y por ello emerge una pequeña ventana de
información, que más del 80 % de las fotografías tienen las mismas
coordenadas, por lo que pueden ser borradas por defecto, pero solo hay que
aceptar los pasos para continuar con el proceso. Esto es debido a que las
imágenes tomadas son terrestres por lo que prácticamente tienen coordenadas
muy cercanas o simplemente carecen de esta información. Esto lo utiliza Pix4D
en caso de tomas aéreas. Ver Figura 38.

Figura 38. Imágenes cargadas por el programa Pix4D.

El paso que continúa es poner el sistemas de referencia del proyecto, en este
caso no es nesario poner un sistemas de referencia conocido por lo que será un
sistemas de referencia arbitrario con coordenas en metros. Ver Figura 39.

Daniel Almagro Caballero de León 64
Universidad de Extremadura

<!-- p. 65 -->

Máster Universitario de Especialización en
Geotecnologías Topográficas en la Ingeniería.

Análisis de métodos para el Levantamiento Arquitectónico. Escuela Politécnica

Figura 39. Selección de sistema de referencias arbitrario y unidades en metros en Pix4D.

En este paso el programa te da elegir unas opciones de procesado del modelo
según las imágenes tomadas. En nuestro caso, al ser un edificio y no una
extensión de terreno, seleccionamos “3D models”. Ver Figura 40.

Figura 40. Selección de opción de procesado "3D models" con Pix4D.

Ahora ya están cargadas las imágenes, un total de 29, y creado el proyecto, por
lo que continuaremos con el siguiente paso del proceso. Para proceder al
modelado el programa realiza 3 fases o pasos. Ver Figura 41:

\- Paso 1 es un proceso inicial para obtener la configuración de las
imágenes.
\- Paso 2 ejecuta la densificación de los puntos.
\- Paso 3 es la realización del modelo digital de superficies pero que en este
caso no se realiza por no ser toma de imágenes aéreas.

Daniel Almagro Caballero de León 65
Universidad de Extremadura

<!-- p. 66 -->

Máster Universitario de Especialización en
Geotecnologías Topográficas en la Ingeniería.

Análisis de métodos para el Levantamiento Arquitectónico. Escuela Politécnica

Figura 41. Indicación de los pasos que ejecuta Pix4D.

Tenemos la opción, al igual que PhotoScan, de importar los puntos tomados con
la estación total (“Select GPCs Files”) que nos servirán de control. Estos datos
están guardados en un bloc de notas, con extensión del archivo .txt, éstos son
los puntos con coordenadas X, Y, Z separadas con punto y coma (;). En este
paso, como podemos ver en la Figura 42, importamos dichos puntos.

Figura 42. Importación de coordenadas de puntos con Pix4D.

Después de este paso, procedemos a realizar la nube de puntos clicando “start”
y dejamos que el programa ejecute los procesos necesarios para realizar el
modelado. Ver Figura 43.

Figura 43. Procesado de las imágenes con Pix4D.

Daniel Almagro Caballero de León 66
Universidad de Extremadura

<!-- p. 67 -->

Máster Universitario de Especialización en
Geotecnologías Topográficas en la Ingeniería.

Análisis de métodos para el Levantamiento Arquitectónico. Escuela Politécnica

Observamos en la Figura 44 la nube de puntos y la posición de las cámaras al
igual que en los otros programas. El programa fue capaz de calibrar un total de
28 imágenes de 29.

Figura 44. Nube de puntos generado con Pix4D.

Visualizamos en la Figura 45 la nube de puntos densa y como queda el modelo
finalmente con este programa.

Figura 45. Visualización de la nube de puntos densa con Pix4D.

Lo último que vamos a realizar con este programa y que es el objeto del
levantamiento es escalarlo y tomar las medidas de comparación.

Primero lo escalamos con la medida tomada del ancho de la puerta principal
(4,82 m). Es un proceso muy parecido a los anteriores programas. Ver Figura 46.

Daniel Almagro Caballero de León 67
Universidad de Extremadura

<!-- p. 68 -->

Máster Universitario de Especialización en
Geotecnologías Topográficas en la Ingeniería.

Análisis de métodos para el Levantamiento Arquitectónico. Escuela Politécnica

Figura 46. Toma de medidas con Pix4D.

Después vamos creando puntos en el modelo para luego unir los con líneas que
nos muestran las medidas y que nos sirven para realizar la comparación. Ver
Figura 47.

Figura 47. Toma de medidas con Pix4D con más detalle.

Los resultados finales se muestran en la Figura 48, tras finalizar el proceso de
levantamiento con el software Pix 4D.

Figura 48. Resultado final del modelo con Pix4D.

Medidas entre los puntos con Pix4D:

Daniel Almagro Caballero de León 68
Universidad de Extremadura

<!-- p. 69 -->

Máster Universitario de Especialización en
Geotecnologías Topográficas en la Ingeniería.

Análisis de métodos para el Levantamiento Arquitectónico. Escuela Politécnica

2-1 20.064 m

46-2 12.317 m

25-18 05.117 m

40-41 03.286 m

17-16 04.819 m

14-39 06.091 m
Tabla 6. Medidas obtenidas del modelo con Pix4D.

4.3.2.4. LEVANTAMIENTO FOTOGRAMÉTRICO REALIZADO CON
EL PROGRAMA “VISUAL SFM Y MESHLAB”

Al igual que los programas analizados anteriormente, el objetivo de éste es
crear una nube de puntos en 3D, con la ayuda de diversas herramientas.
Estas nubes de puntos formadas por simples puntos descritos por unas
coordenadas espaciales XYZ y unos valores RGB que serán los encargados de
restituir la textura original a través de lo que se conoce como nube de puntos
densa. Con este programa no es necesario establecer puntos de referencia
entre las imágenes ni calibrar la cámara, lo que agiliza el proceso y nos
permite trabajar con gran cantidad de imágenes. Este programa no incorpora
una herramienta de medición como las anteriores por lo que tendremos que
exportar el modelo para trabajar con otro programa de manipulación de
nube de puntos. En este caso utilizaremos el software libre MESHLAB.

El proceso de funcionamiento de VisualSFM, como el de muchas
herramientas de SFM se fundamenta en los siguientes pasos:

\1. SIFT (Scale-invariant feature transform): algoritmo de detección de puntos
clave o coincidentes entre las múltiples imágenes.

\2. Bundle Adjustment: Crea la nube de puntos dispersa a partir de los puntos
clave detectados en el paso anterior. En este paso se puede intuir la
forma de nuestro modelo y disponer de la posición de las cámaras.

\3. Multi-View Stereo: Será el proceso encargado de generar la nube de
puntos densa a partir de todos los datos anteriores. De este proceso se
encargan las herramientas CMVS y PMVS2 de Yasutaka Furukawa,
ingeniero de Google Maps.

CREACIÓN DEL MODELO

Daniel Almagro Caballero de León 69
Universidad de Extremadura

<!-- p. 70 -->

Máster Universitario de Especialización en
Geotecnologías Topográficas en la Ingeniería.

Análisis de métodos para el Levantamiento Arquitectónico. Escuela Politécnica

En el proceso de instalación del programa hay que descargar el ejecutable
desde la web de Changchang y adicionalmente descargar las herramientas
PMVS y CMVS de Yasutaka, ya compilados, para ello podemos acudir a la web
de Pierre Moulon, elegir el tipo de sistema y descargar cmvs.exe,
genOption.exe, pmvs2.exe y pthread.dll que hay que ubicar simplemente junto
al ejecutable de VisualSFM.exe. (Pereira J. , 2012)

Ejecutamos el programa y nos encontramos con la interfaz inicial. Ver Figura
\49.

Figura 49. Pantalla principal del programa fotogramétrico VisualSFM.

Cargamos el grupo de imágenes tomadas. Antes de realizar este paso se
cambiaron el formato de las imágenes realizadas con la cámara digital
Olympus, el formato de éstas era .tiff y VisualSFM solo abre imágenes tipo .jpg,
.ppom, .pgm. Con el programa de Windows, “Paint” se puede hacer fácilmente.

Clicamos en File > Open + Multi Images. Y cargamos un total de 29 imágenes.
Ver Figura 50.

Daniel Almagro Caballero de León 70
Universidad de Extremadura

<!-- p. 71 -->

Máster Universitario de Especialización en
Geotecnologías Topográficas en la Ingeniería.

Análisis de métodos para el Levantamiento Arquitectónico. Escuela Politécnica

Figura 50. Carga de imágenes con VisualSFM.

Una vez cargadas las imágenes el programa tiene que buscar las
coincidencias entre ellas para orientar el modelo, esto se hace con el botón
simbolizado con las cuatro flechas opuestas.

En este paso el programa fue capaz de orientar 22 de 29 imágenes por lo que
no fue 100% efectivo.

Cuando este proceso finaliza, usamos el botón contiguo formado por dos
puntas flecha (roja y azul) para crear la nube de puntos. Ver Figura 51.

Figura 51. Nube de puntos creado con VisualSFM.

Finalmente, con el botón simbolizado por las siglas CMSVS, reconstruimos
la textura. En este punto se nos indica la ruta para guardar el proyecto.

Cuando el proceso anterior ha finalizado, puede llevar algunos minutos,
para ver el resultado final vamos al menú View y activamos Dense 3D
Points. Ver Figura 52.

Daniel Almagro Caballero de León 71
Universidad de Extremadura

<!-- p. 72 -->

Máster Universitario de Especialización en
Geotecnologías Topográficas en la Ingeniería.

Análisis de métodos para el Levantamiento Arquitectónico. Escuela Politécnica

Figura 52. Nube de puntos densa con VisualSFM.

Como vemos en el resultado, la recreación 3D es un poco tosca, ya que se
forma numeroso ruido entorno al objeto inicial fruto de los fondos de las
imágenes, por lo que será necesario limpiar la imagen para obtener una buena
recreación de la misma, de forma similar se puede observar diversos “agujeros”
provocados por la falta de información o densidad de puntos comunes que
dificulta la reconstrucción exacta de la textura (Pereira J. , 2012).

Ahora vamos a exportar la nube de puntos a MeshLab para poder crear la
malla, escalarlo y poder tomar las medidas de comparación con este último
trabajo. Ver Figura 53.

MeshLab es un programa de código abierto (open source) para edición de
nube de puntos y mallas triangulares 3D. (FAROGB, 2012)

MeshLab V 1.3.3. Última versión (02/04/2014)

http://meshlab.sourceforge.net/

Daniel Almagro Caballero de León 72
Universidad de Extremadura

<!-- p. 73 -->

Máster Universitario de Especialización en
Geotecnologías Topográficas en la Ingeniería.

Análisis de métodos para el Levantamiento Arquitectónico. Escuela Politécnica

Figura 53. Visualización de la nube de puntos densa de VSFM con MeshLab.

En la Figura 54 se puede observar cómo se realiza el depurado de la nube de
puntos que no son de interés.

Figura 54. Depurado de la nube de puntos con MeshLab.

Una vez depurada la nube de puntos podemos observar el resultado en la
Figura 55.

Daniel Almagro Caballero de León 73
Universidad de Extremadura

<!-- p. 74 -->

Máster Universitario de Especialización en
Geotecnologías Topográficas en la Ingeniería.

Análisis de métodos para el Levantamiento Arquitectónico. Escuela Politécnica

Figura 55. Visualización del modelo depurado con MeshLab.

Para construir la malla con la nube de puntos vamos a realizar los siguientes
pasos.

Primero clicamos en >Filters>Normal, Curvatures and Orientation>Compute
Normals for Point Set. Dejamos los parámetros por defecto y pulsamos Apply.
Con esta función le decimos al programa la cantidad de puntos vecinos tiene
que reconocer para recrear la malla.

Después >Filters>Remesing, Simplification and Reconstruction>Surface
Reconstruction: Poisson. Dejamos los parámetros por defecto y creamos la malla.
Ver Figura 56 y 57.

Figura 56. Opciones de mallado con MeshLab.

Daniel Almagro Caballero de León 74
Universidad de Extremadura

<!-- p. 75 -->

Máster Universitario de Especialización en
Geotecnologías Topográficas en la Ingeniería.

Análisis de métodos para el Levantamiento Arquitectónico. Escuela Politécnica

Figura 57. Visualización de la malla creada con MeshLab.

Tras crear la malla también podemos exportar los colores de cada punto a la
malla para hacer el texturizado, este paso es opcional. Ahora ya tenemos el
modelo en 3D, con mucha menos calidad que los otros programas analizados.
Ver Figura 58.

Figura 58. Texturizado del modelo con MeshLab.

Tenemos creado el modelo.

Para escalar el modelo hacemos clic en >Filters>Normals, Curvatures and
Orientation>Transform: Scale. Primero hemos utilizado la herramienta Measuring
Tool y hemos medido el ancho de la puerta principal dando una distancia de
0.64598, en la realidad tiene una medida de 4,82 m como sabemos. Por lo que el
factor de escala se calcula de la siguiente manera:

4.82
𝐹𝑎𝑐𝑡𝑜 𝑑𝑒 𝑒𝑠𝑐𝑎𝑙𝑎= = 𝟕. 𝟒𝟔𝟐
0.64598

Daniel Almagro Caballero de León 75
Universidad de Extremadura

<!-- p. 76 -->

Máster Universitario de Especialización en
Geotecnologías Topográficas en la Ingeniería.

Análisis de métodos para el Levantamiento Arquitectónico. Escuela Politécnica

Este valor lo añadimos a la función y ya tenemos el modelo escalado.

De nuevo con la herramienta “Measuring Tool”, ver Figura 59 y 60, vamos
tomando las medidas de comparación en el modelo. No se pueden tomar
medidas de los mismos puntos exactamente con esta herramienta por lo que se
toman 3/4 veces y se hace la media para obtener el valor de comparación.

Figura 59. Medición de los puntos con MeshLab.

Figura 60. Visualización más cercana de las medidas tomadas con MeshLab.

Medidas entre los puntos:
2-1 20,3185/20,3293/20,3671/20,3292 Media = 20,3360 m
46-2 12,265/12,4156/12,4714/12,4062 Media = 12,3896 m
Media = 05,1155 m 25-18 5,1249/5,0999/ 5,1217
Media = 03,2975 m 40-41 3,3141/ 3,2978/ 3,28061
Media = 04,8483 m 17-16 4,8197/ 4,8736/ 4,8433/ 4,8567
Media = 06,1125 m 14-39 6,0901/ 6,1501/ 6,0962/ 6,1137
Tabla 7. Medidas obtenidas con MeshLab aplicando la media de los valores.

Daniel Almagro Caballero de León 76
Universidad de Extremadura

<!-- p. 77 -->

Máster Universitario de Especialización en
Geotecnologías Topográficas en la Ingeniería.

Análisis de métodos para el Levantamiento Arquitectónico. Escuela Politécnica

Para contrastar las mediciones por el método anterior, recurrimos a otra
opción que es obtener las coordenadas de los puntos con la herramienta “Pick
Point” de MeshLab, exportarlas a Topocal con un archivo .txt y de ahí
exportarlas de nuevo como archivo .dxf para trabajar con AutoCAD y tomar las
medidas. Esta operación la hicimos con anterioridad en el proyecto para
representar los puntos tomados con la estación total. Ver Figura 61.

Figura 61. Coordenadas de los puntos tomados con MeshLab.

En la Figura 62 podemos ver las coordenadas en el sistema de referencia que
posee el modelo en MeshLab.

Figura 62. Coordenadas de los puntos con MeshLab.

Daniel Almagro Caballero de León 77
Universidad de Extremadura

<!-- p. 78 -->

Máster Universitario de Especialización en
Geotecnologías Topográficas en la Ingeniería.

Análisis de métodos para el Levantamiento Arquitectónico. Escuela Politécnica

Después de realizar el procedimiento anteriormente descrito de exportación
de los puntos con sus coordenadas nos quedan los valores de las medidas de
comparación. Ver Figura 63.

Figura 63. Toma de medidas entre los puntos anteriores con AutoCAD.

Medidas entre los puntos:

2-1 20.2581 m

46-2 12.3850 m

25-18 05.0990 m

40-41 03.0084 m

17-16 04.8322 m

14-39 06.1452 m
Tabla 8. Medidas del modelo realizado con VisualSFM y MeshLab obtenidas en AutoCAD.

Daniel Almagro Caballero de León 78
Universidad de Extremadura

<!-- p. 79 -->

Máster Universitario de Especialización en
Geotecnologías Topográficas en la Ingeniería.

Análisis de métodos para el Levantamiento Arquitectónico. Escuela Politécnica

\5. EVALUACIÓN DE LA CALIDAD MÉTRICA DE
LOS MODELOS 3D

Conocer en qué medida las dimensiones del modelo tridimensional recreado
se asimilan a la realidad y cómo se desvían es muy importante. Como
consecuencia, debe analizarse la precisión y exactitud de estos modelos.

En la actualidad, revisando la bibliografía, no hay definido un procedimiento
estándar o normas para determinar dicha calidad, aunque ya hay algunos
intentos por estandarizarlos en los diferentes campos en los que interviene la
fotogrametría (Martínez et al, 2013).

A pesar de no encontrar un procedimiento estandarizado, unificando los
sistemas encontrados en la mayoría de trabajos (Martínez Rodríguez, 2014)
podemos diferenciar tres operaciones básicas: obtención de puntos de contraste
reales (TCP, “true check points”), obtención de los puntos de contraste
fotogramétricos (PCP, “photogrammetric check points”) y el cálculo de la calidad
de medida (MQ, “metric quality”) de la técnica fotogramétrica evaluada.

En este trabajo se ha escogido el método de evaluación MQ, es decir, calidad
de medida, tomando 6 medidas de referencia en los 4 modelos generados.

Como anteriormente se explicó en el análisis de errores de los métodos de
levantamiento arquitectónico, es importante conocer los conceptos relacionados
con la calidad métrica de un modelo: exactitud y precisión. La exactitud nos
informa de lo cerca que el resultado de una medición está del valor verdadero.
Por otro lado, la precisión de un instrumento o método de medición está
asociada a la sensibilidad o menor variación de la magnitud que se pueda
detectar, es decir, a la dispersión del conjunto de los valores obtenidos de
mediciones repetidas. Cuanto menor es la dispersión, mayor es la precisión.

Los diferentes autores (Martínez et al, 2013) (García-León et al, 2014) (Souto
Vidal et al, 2015) (Salcedo Galera & Calvo López, 2014) toman diferentes índices
estadísticos para proporcionar información de la exactitud y la precisión del
modelo. Por ello, realizando la diferencia entre las medidas obtenidas en el
modelo y las medidas reales del objeto nos dan como resultados unos errores en
la medición. Para analizar estos errores los estadísticos tomados en esta práctica
son los siguientes:

 Para la estimación de la exactitud:
o Error Máximo: Máximo valor de los errores obtenidos. Valor
positivo.

Daniel Almagro Caballero de León 79
Universidad de Extremadura

<!-- p. 80 -->

Máster Universitario de Especialización en
Geotecnologías Topográficas en la Ingeniería.

Análisis de métodos para el Levantamiento Arquitectónico. Escuela Politécnica

o Error Mínimo: Mínimo valor de los errores obtenidos. Valor
negativo.
o Media: Media aritmética, también llamada promedio o
simplemente media, muestra el valor central de los errores
obtenidos.
o Media error valor absoluto: Media aritmética de los errores en
valor absoluto.
o Error cuadrático medio. RMSE: medida de la diferencia entre
los valores pronosticados por un modelo y los valores
observados de la realidad.
𝐸𝑀𝐶= √𝛴(𝑋𝑂−𝑋𝑉)2
𝑛
Donde,
x0 es el valor observado
xv es el valor verdadero
n es el número de observaciones

 Para la estimación de la precisión:

o Desviación estándar o típica: Es una medida de dispersión que
nos da idea de cuánto tienden a alejarse los valores puntuales
del promedio en una distribución.

1 𝑛 ∑ 𝜎= √ 𝑖=1(𝑥𝑖−𝑥̅)2 , donde 𝑥 ̅es el promedio de los valores. 𝑛−1

o Desviación típica absoluto. Desviación típica tomando los
errores en valor absoluto.

Los errores absolutos se utilizan cuando interesa conocer la magnitud de los
errores y no su signo y, por otra parte, permiten hacer afirmaciones de
probabilidad sin necesidad de asumir una distribución simétrica (Hohle &
Hohle, 2009).

Se pueden encontrar algunas clasificaciones de la exactitud de los métodos
fotogramétricos en función del error absoluto (Carbonell, 1989). Aquí se
distinguen 3 grupos: muy precisos (exactitud de 1 mm o menor), precisos
(rango de exactitud en torno a 1 o 2 mm) y métodos fotogramétricos sencillos y
rápidos (métodos con simpleza y bajo coste del equipo requerido; errores
máximos de 5 cm son aceptables).

Por otra parte, el error relativo nos permite estimar la exactitud referida al
tamaño del objeto.

Daniel Almagro Caballero de León 80
Universidad de Extremadura

<!-- p. 81 -->

Máster Universitario de Especialización en
Geotecnologías Topográficas en la Ingeniería.

Análisis de métodos para el Levantamiento Arquitectónico. Escuela Politécnica

𝐷 Error Relativo = 1: 𝐸

donde, D es el valor tomado como real del objeto estudiado y E el valor de la
medida en el modelo.

Para finalizar, en función a la MQ (Metric Quality) es posible realizar análisis
comparativos de diferentes técnicas fotogramétricas empleadas (Martínez
Rodríguez, 2014). Por lo tanto, en los trabajos se suelen comparar técnicas que
difieren en la cámara fotográfica empleada, en el número de puntos de control
empleado, en el número de fotografías realizadas, en la técnica de calibración
empleada o, como es el caso de éste trabajo fin de máster, en el software
utilizado.

Daniel Almagro Caballero de León 81
Universidad de Extremadura

<!-- p. 82 -->

Máster Universitario de Especialización en
Geotecnologías Topográficas en la Ingeniería.

Análisis de métodos para el Levantamiento Arquitectónico. Escuela Politécnica

\6. RESULTADOS

Los resultados obtenidos en los cálculos estadísticos realizados a partir de los
datos obtenidos de los levantamientos hechos anteriormente los mostramos en
las siguientes tablas. Las medidas están en metros.

Distancias Estación Total
2-1 20,038 m
46-2 12,309 m
25-18 5,117 m
40-41 3,293 m
17-16 4,860 m
14-39 6,091 m
Tabla 9. Medidas comparativas de la estación total.

Distancias 123D Catch PhotoScan Pix4d VisualSFM VisualSFM2
2-1 20,053 20,026 20,064 20,336 20,258
46-2 12,310 12,300 12,317 12,390 12,385
25-18 5,086 5,083 5,117 5,116 5,099
40-41 3,287 3,328 3,286 3,298 3,008
17-16 4,833 4,837 4,819 4,848 4,832
14-39 6,058 6,130 6,091 6,113 6,145
Tabla 10. Medidas obtenidas de los levantamientos fotogramétricos. Medidas en metros.

Distancias 123D Catch PhotoScan Pix4d VisualSFM VisualSFM2
2-1 0,015 -0,012 0,026 0,298 0,220
46-2 0,001 -0,009 0,008 0,081 0,076
25-18 -0,031 -0,034 0,000 -0,002 -0,018
40-41 -0,006 0,035 -0,007 0,004 -0,285
17-16 -0,027 -0,023 -0,041 -0,012 -0,028
14-39 -0,033 0,039 0,000 0,021 0,054
Tabla 11. Diferencia entre las medidas de cada programa y la estación total.

123D Catch PhotoScan Pix4D VisualSFM VisualSFM2
Error Máximo 0,015400 0,039000 0,026000 0,298000 0,220100
Error Mínimo -0,033400 -0,034000 -0,041000 -0,012000 -0,284600
Media de error -0,013483 -0,000667 -0,002333 0,065183 0,003317
Disv. Típica
0,019897 0,030507 0,022079 0,118689 0,166845 error
Media error v.
0,018850 0,025333 0,013667 0,069683 0,113450 absoluto
Desv. Típica
0,013699 0,012691 0,016428 0,115581 0,111379 error v. abs.
RMSE 0,022621 0,027857 0,020290 0,126444 0,152344
Tabla 12. Análisis estadísticos de los errores cometidos por cada programa en la toma de medidas.

Daniel Almagro Caballero de León 82
Universidad de Extremadura

<!-- p. 83 -->

Máster Universitario de Especialización en
Geotecnologías Topográficas en la Ingeniería.

Análisis de métodos para el Levantamiento Arquitectónico. Escuela Politécnica

Distancias 123D Catch PhotoScan Pix4d VisualSFM VisualSFM2
2-1 0,077% -0,060% 0,130% 1,487% 1,098%
46-2 0,006% -0,073% 0,065% 0,655% 0,617%
25-18 -0,606% -0,664% 0,000% -0,029% -0,352%
40-41 -0,173% 1,063% -0,213% 0,137% -8,643%
17-16 -0,553% -0,473% -0,844% -0,247% -0,572%
14-39 -0,548% 0,640% 0,000% 0,353% 0,890%
PROMEDIO -0,300% 0,072% -0,144% 0,393% -1,160%
Tabla 13. Errores relativos en %.

Primeramente, vamos a desechar el segundo método por el que se
obtuvieron las medidas con VisualSFM por tener dos valores que superan los 20
cm de error. De esta manera nos quedamos con el método 1 para evaluar los
resultados.

Observando los resultados obtenidos en la Tabla 12 podemos decir que el
valor superior del error máximo se produce con VisualSFM con casi 30 cm de
error. El valor máximo del error mínimo, en cambio se produce en Pix4D con -
0,041 m y el valor mínimo en este caso con VisualSFM con -0,012.

La media de error con menor magnitud (próximo a 0 es lo ideal) es la
obtenida con PhotoScan seguida de Pix4D. VisualSFM queda de nuevo como la
última con peores resultados. En cambio, al tener los errores en valor absoluto
donde importa más la magnitud que la simetría de las mediciones, como
explicamos anteriormente, Pix4D es el que muestra más exactitud, seguido de
123DCatch, después PhotoScan y por último VisualSFM (ver en Tabla 12).

Los valores resultantes de los errores cuadráticos medios (ver en Tabla 12)
confirman lo anterior. Pix4D muestra con sus valores en los estadísticos de los
errores una mayor exactitud al resto, seguido de 123DCatch. Por lo tanto,
podemos clasificar según la exactitud los programas quedando en el siguiente
orden: Pix4D, PhotoScan, 123DCatch y VisualSFM.

En términos de precisión, observando los valores en la desviación típica (ver
en Tabla 12) y en ésta con los valores absolutos podemos decir que, en este caso,
123DCatch se muestra más precisa que los demás programas fotogramétricos
como consecuencia de que sus valores no se alejan mucho del promedio de los
errores de la medición. VisualSFM muestra una vez más los peores resultados.

Por último, para tener una idea de exactitud de los programas en función del
tamaño del objeto, vemos que en los valores de los errores relativos PhotoScan

Daniel Almagro Caballero de León 83
Universidad de Extremadura

<!-- p. 84 -->

Máster Universitario de Especialización en
Geotecnologías Topográficas en la Ingeniería.

Análisis de métodos para el Levantamiento Arquitectónico. Escuela Politécnica

muestra una mayor exactitud (0,072%), seguida de Pix4D, a continuación,
123DCatch y, por último, VisualSFM (ver en Tabla 13).

Una vez analizado los resultados, podemos decir que el programa más
exacto es Pix4d y el más preciso 123DCacth.

Los valores obtenidos en general (ver en Tabla 11), exceptuando 3
mediciones, no sobrepasan el error de los 4 cm. Así pues, llegamos a la
conclusión de que son modelos con buena exactitud, pero que en trabajos que
necesitasen precisiones por debajo del centímetro no podrían ser aceptados.

Podemos llegar a la conclusión, de que estos errores pueden verse mucho
más reducidos realizando una mejor planificación de la toma de imágenes, es
decir, haber tomado un mayor número de capturas, con mayor solapamiento, a
diferentes alturas o a una altura mayor si hubiéramos utilizado un mástil dónde
elevar la cámara.

En función de lo expuesto en el anterior párrafo se pueden desarrollar líneas
de investigación futuras como se nombrará en su respectivo apartado.

En esta parte del TFM también se muestra la representación del edificio 3D
con cada software, también se pueden ver con más detalle en el Anexo IV.
123D Catch PhotoScan

Pix4D VisualSFM

Figura 64. Comparación de los diferentes modelos.

Daniel Almagro Caballero de León 84
Universidad de Extremadura

<!-- p. 85 -->

Máster Universitario de Especialización en
Geotecnologías Topográficas en la Ingeniería.

Análisis de métodos para el Levantamiento Arquitectónico. Escuela Politécnica

Como podemos observar, 123DCatch y PhotoScan dan mejores resultados en
la representación del modelo ya que ambos permiten realizar el mallado y
texturizado con el propio programa. En cambio, Pix4D y VisualSFM finalizan el
proceso del modelado en la nube de puntos densa, lo cual genera una
recreación bastante conseguida del modelo y con una fiabilidad aceptable, pero
muestran agujeros en la nube de puntos.

Tras la experiencia de utilizar los 4 programas, el programa PhotoScan es
para mí el seleccionado como programa adecuado para realizar trabajos de
levantamiento arquitectónico. Las mayores ventajas son la interfaz, los
resultados generados y la información que nos facilita. En conclusión, es un
programa fiable, con mayor cobertura y detalle que el resto.

Daniel Almagro Caballero de León 85
Universidad de Extremadura

<!-- p. 86 -->

Máster Universitario de Especialización en
Geotecnologías Topográficas en la Ingeniería.

Análisis de métodos para el Levantamiento Arquitectónico. Escuela Politécnica

\7. CONCLUSIONES

Por una parte, tras analizar en profundidad los diferentes sistemas de
levantamiento arquitectónico llegamos a la conclusión de que el método
fotogramétrico tiene un gran potencial en la actualidad y puede llegar a ser el
más indicado para la documentación del patrimonio cultural y arquitectónico si
sigue con este desarrollo.

La fotogrametría es un método para análisis de objetos tridimensionales muy
eficaz, rápido y claro. Con éste se recoge gran volumen de información en poco
tiempo, con pocos medios y sin dañar físicamente al objeto.

Su uso en el estudio del Patrimonio es fundamental, ya que permite obtener
documentación sobre el estado del objeto a analizar. La reconstrucción del
mismo es de gran precisión y realismo, y con ellos se pueden generar planes de
conservación o de restauración.

Durante el desarrollo de la práctica, en el trabajo de campo hay que resaltar
que hay que realizar una buena planificación en la toma de imágenes con
cámara, lo cual es fundamental para la efectividad de la reconstrucción del
modelo. Por ello, debemos realizar una primera calibración de la cámara,
determinar los parámetros de la toma fotográfica como son la distancia al objeto
en las capturas, el enfoque, el tiempo de exposición, la distancia focal, el
recorrido a seguir, las alturas de tomas, la hora del día por generación de
sombras, el estudio de las limitaciones espaciales del entorno del elemento o el
número de estaciones necesarias para garantizar que cada superficie aparezca
en al menos tres fotografías. Todo ello evitará posibles errores en el procesado
de las imágenes.

También es necesario tener en cuenta el volumen de datos a procesar y del
software y hardware del que se dispone. La velocidad e incluso la efectividad
de los programas fotogramétricos están íntimamente relacionados con la
capacidad del equipo computacional del que disponemos. En este caso práctico
tuvimos que cambiar 2 veces de computador para poder obtener datos fiables
de uno de los programas (Pix4D).

El desarrollo de los programas fotogramétricos y la aparición de nuevos
algoritmos dan mucho valor al método fotogramétrico frente a los métodos
topográficos o el escáner láser, pero debemos, por otra, parte tener en cuenta
que el uso combinado de ellos permite mejorar bastante los resultados.

La técnica de escáner láser 3D muestra modelos de gran exactitud y precisión
con errores por debajo del mm. Éste es un método muy aceptable si se dispone

Daniel Almagro Caballero de León 86
Universidad de Extremadura

<!-- p. 87 -->

Máster Universitario de Especialización en
Geotecnologías Topográficas en la Ingeniería.

Análisis de métodos para el Levantamiento Arquitectónico. Escuela Politécnica

de los recursos necesarios para poder adquirir este tipo de instrumental, el cual
requiere una inversión mayor a los 40.000 € como vimos en el apartado
correspondiente.

Por ello, la fotogrametría como método rápido, de gran precisión y
fiabilidad, que genera buenos resultados en el modelado y las dimensiones del
objeto, y por su fácil adquisición, hace de éste uno de los más potenciales en la
actualidad para realizar trabajos de levantamiento arquitectónico.

Por otra parte, podemos decir que casi cualquier trabajo puede ser resuelto
por un usuario que tenga conocimientos de fotografía y sepa usar el software,
aunque no tenga conocimientos previos de fotogrametría.

Por último, incidir en que este trabajo permite mostrar el potencial alcanzable
con el método fotogramétrico en la elaboración de los modelos 3D digitales
para obtener ortofotos y planos-

Daniel Almagro Caballero de León 87
Universidad de Extremadura

<!-- p. 88 -->

Máster Universitario de Especialización en
Geotecnologías Topográficas en la Ingeniería.

Análisis de métodos para el Levantamiento Arquitectónico. Escuela Politécnica

\8. LÍNEAS FUTURAS DE TRABAJO

Siguiendo con la misma línea de comparación de estos programas
fotogramétricos, podríamos realizar la comparación teniendo en cuenta otra
serie de parámetros como podrían ser:

\- El número de fotografías realizadas sobre el inmueble.

\- La utilización de diferentes cámaras digitales: Réflex, Smartphone,
compactas…

\- La altura de toma de las imágenes ayudándose de un mástil.

Este análisis podría ser un desarrollo de las líneas futuras de trabajo más
interesantes para poder seguir comparando estos programas y así decantarse
por el que mejores prestaciones dé.

Daniel Almagro Caballero de León 88
Universidad de Extremadura

<!-- p. 89 -->

Máster Universitario de Especialización en
Geotecnologías Topográficas en la Ingeniería.

Análisis de métodos para el Levantamiento Arquitectónico. Escuela Politécnica

\9. BIBLIOGRAFÍA
AGISOFT. (s.f.). Useful Tips on Image Capture: How to Get an Image Dataset that
Meets PhotoScan Requirements? Obtenido de
http://www.agisoft.com/pdf/tips_and_tricks/Image%20Capture%20Tips%20-
%20Equipment%20and%20Shooting%20Scenarios.pdf
Almagro, A. (1991). Simplified methods in Architectural Photogrammetry. Delphi,
Greece: XIV CIPA International Symposium. Obtenido de Almagro, A. (1991).
“Simplified methods in Architectural Photogrammetry”. XIV CIPA
International Symposium, Delphi, Greece.
Almagro, A. (2001). Simple Methods of Photogrammetry - Easy and Fast. Postdam,
Germany: XVIII International Symposium of CIPA.
Almagro, A. (2004). Levantamientos Arquitectónicos.
ASPRS. (1934). American Society of Photogrammetry and Remote Sensing. Obtenido
de www.asprs.org
ASPRS. (2012). Obtenido de https://www.asprs.org/
Bonneval, H. (1972).
Carbonel, M., & Dallas, R. W. (10 de 04 de 2003). ScienceDirect. Obtenido de
http://www.sciencedirect.com/science/article/pii/0031866385900122
Carbonell, M. (1989). Architectural photogrammetry, Karara HM, Non-topographic
photogrammetry. Falls Church, Virginia.
CIPA. (s.f.). Obtenido de http://cipa.icomos.org/text%20files/TURIN/485.pdf
CIPA 3X3 Rules. (08 de 12 de 2014). Obtenido de The International Committee for
Documentation of Cultural Heritage (CIPA):
http://cipa.icomos.org/index.php?id=20&tx_ttnews%5Btt_news%5D=38&cHas
h=5cd6f8216e31d77658fc70ca84c7455d
Cuartero, A. (Noviembre de 2012). Introducción a la fotogrametría. Universidad de
Extremadura.
DATATECA. (2016). UNAD. Obtenido de
]Http://datateca.unad.edu.co/contenidos/201620/MODULO%20TOPOGRAFIA/
leccin_10_errores_comunes_en_topografa.html
Engineering, D. o. (s.f.). Department of Computer Science and Engineering. (Indian
Institute of Technology Delhi) Obtenido de
http://www.cse.iitd.ac.in/~mcs112609/Meshlab%20Tutorial.pdf
FAROGB. (5 de 10 de 2012). SCENECT 5.1 Tutorial MeshLab Create a mesh for 3D
printing. Recuperado el 04 de 07 de 2016, de YOUTUBE:
https://www.youtube.com/watch?v=u0Q1A1zA32U
Fernández, G., Fernández, José, S., Martines, García, & Marcos. (2012). Study of
efficiency for heritage documentation from image and rangebased information.
Case study: San Martín Church, Segovia. Fabbrica della Conoscenza numero
\16.
García Léon, J., & Cuartero Sáez, A. (2002). Tendencias y recopilación práctica de
programas utilizados. Mapping, 26-32.
García, I., Fernández, M., & Mesanza, A. (2011). Láser escáner y nubes de puntos. Un
horizonte aplicado al análisis arqueológico de edificios. Arqueología de la
arquitectura., 25-44.
García-Gómez, I., Fernández de Gorostiza López de Viñaspre, M., & Mesanza Moraza,
A. (2011). Láser escáner y nubes de puntos. Arqueología de la arquitectura,
(págs. 25-44). Madrid.

Daniel Almagro Caballero de León 89
Universidad de Extremadura

<!-- p. 90 -->

Máster Universitario de Especialización en
Geotecnologías Topográficas en la Ingeniería.

Análisis de métodos para el Levantamiento Arquitectónico. Escuela Politécnica

García-León, Vázquez, Ros, García, & Moreno. (2014). Levantamiento tridimensional
mediante fotogrametría y láser escáner del Palacio Nazarí de la Casa Dorda.
APEGA, (págs. 216-225).
Hohle, J., & Hohle, M. (2009). Accuracy assessment of digital elevation models by
means of robust statistical methods. ISPRS Journal of Photogrammetry and
Remote Sensing, 398-406.
ISPRS. (2007). International Society for Photogrametry and Remote Sense. Obtenido de
http://www.isprs.org: /http://onlinelibrary.wiley.com/doi/10.1111/j.1477-
9730.2012.00693.x/epdf?r3_referer=wol&tracking_action=preview_click&show
_checkout=1&purchase_referrer=www.isprs.org&purchase_site_license=LICE
NSE_DENIED
ISPRS. (13 de 11 de 2015). ISPRS. Obtenido de
http://www.isprs.org/society/Default.aspx
Lerma García, J. L. (2002). Fotogrametría moderna: analítica y digital. Valencia.
Lowe, D. G. (14 de 05 de 2004). Distinctive Image Features from Scale-Invariant
Keypoints. Recuperado el 15 de 06 de 2016, de Wikipedia, La enciclopedia
libre: https://es.wikipedia.org/w/index.php?title=Scale-
invariant_feature_transform&oldid=82420854
Mañana, P., Rodríguez, A., & Blanco, R. (2088). Una experiencia en la aplicación del
láser escáner a los procesos de documentación y análisis del Patrimonio
Construido: su aplicación a Santa Eulalia de Bóveda (Lugo) y San Fiz de
Solovio. Arqueología de la arquitectura, 15-32.
Martínez Rodríguez, S. (2014). Evaluación en campo de una nueva técnica
fotogramétrica de rango cercano y bajo coste basada en la correlación
automática de imágenes.
Martínez Rodríguez, S. (2014). Tesis Doctoral, EVALUACIÓN EN CAMPO DE UNA
NUEVA TÉCNICA FOTOGRAMÉTRICA DE RANGO CERCANO Y BAJO
COSTE BASADA EN LA CORRELACIÓN AUTOMÁTICA DE IMÁGENES .
SANTIAGO DE COMPOSTELA / LUGO : Universidad de Santiago de
Compostela.
Martínez Rodríguez, S. (2014). Tesis Doctoral, evaluación en campo de una nueva
técnica fotogramétrica de rango cercano y bajo coste basada en la correlación
automática de imágenes. SANTIAGO DE COMPOSTELA / LUGO:
Universidad de Santiago de Compostela.
Martínez, S., Ortiz, J., Gil, M. L., & Rego, M. T. (2013). Recording Complex Structures
Using Close Range Photogrammetry: The Cathedral of Santiago De
Compostela. The Photogrammetric Record. The Photogrammetric Record, 375–
\395.
Ortiz Ortiz, J., GIL, M. L., Martínez, S., Rego, T., & Meijide, G. (2010). A simple
methodology for recording petroglyphs using low-cost digital image correlation
photogrammetry and consumer-grade digital cameras. JOURNAL OF
ARCHAEOLOGICAL SCIENCE, V.37, 3158.
Pereira Uzal, J. M. (2016). Modelado 3D en patrimonio cultural por técnicas de
structure from motion.
Pereira, J. (20 de Diciembre de 2012). Digital Heritage. Recuperado el 04 de 07 de
2016, de http://www.jpereira.net/apuntes-breves/virtualizar-visualsfm-para-
windows

Daniel Almagro Caballero de León 90
Universidad de Extremadura

<!-- p. 91 -->

Máster Universitario de Especialización en
Geotecnologías Topográficas en la Ingeniería.

Análisis de métodos para el Levantamiento Arquitectónico. Escuela Politécnica

Pereira, J. (8 de 10 de 2012). Digital Heritage. Recuperado el 04 de 07 de 2016, de
http://www.jpereira.net/software-revisiones-y-consejos/introducicon-a-la-
fotogrametria-parte-1
Pereira, J. (08 de 10 de 2012). DIGITAL HERITAGE. Obtenido de
http://www.jpereira.net/software-revisiones-y-consejos/introducicon-a-la-
fotogrametria-parte-1
R Wackrow, J. C. (2008). A convergent image configuration for DEM extraction that
minimises the systematic effects caused by an inaccurate lens model. The
Photogrammetric Record 23, 6-18.
REIRA UZAL, J. M. (2013). Modelado 3D en patrimonio cultural por técnicas de
structure from motion ph investigación. (1).
Revista MAPPING. (2013). Obtenido de
http://www.mappinginteractivo.es/ojs/index.php/MAPPING/index
Ricardo. (29 de 10 de 2015). Pix4D: ¿el mejor software de mapeado 3D? Obtenido de
http://www.drones.openopin.com/pix4d-software-mapeado/
Rivas, I. L. (09 de 2013). PROYECTO FIN DE MÁSTER. TOMA DE DATOS
FOTOGRAMÉTRICOS, RECONSTRUCCIÓN VIRTUAL, REALIDAD
AUMENTADA Y DIFUSIÓN EN LA RED DE LA IGLESIA NUESTRA
SEÑORA DE LA ASUNCIÓN.
Rodríguez, M. Á. (2008). Sobre la medición instrumental en el levantamiento
arquitectónico. XII Congreso Internacional de Expresión Gráfica
Arquitectónica.
Rodríguez, S. M. (2014). Evaluación en campo de una nueva técnica fotogramétrica de
rango cercano y bajo coste basada en la correlación automática de imágenes.
SANTIAGO DE COMPOSTELA / LUGO .
Salcedo Galera, M., & Calvo López, J. (2014). La cabecera de Santa María de
Chinchilla. Levatamiento y análisis geométrico. XII CONGRESO
INTERNACIONAL DE EXPRESIÓN GRÁFICA APLICADA A LA
EDIFICACIÓN, (págs. 184-193). Madrid.
SECFT. (2016). Sociedad Española de Cartografía, Fotogrametría y Teledetección.
Obtenido de http://www.secft.es/secft,1,1,quienes-somos.html#mas
Souto Vidal, M., Ortiz-Sanz, J., & Gil Docampo, M. (2015). Implementación del
levantamiento eficiente de fachadas mediante fotogrametría digital automatizada
y el uso de software gratuito. Informes de la construcción.
Universidad Nacional. Abierta y a Distancia. (s.f.). Recuperado el 15 de 05 de 2016, de
UNAD:
Http://datateca.unad.edu.co/contenidos/201620/MODULO%20TOPOGRAFIA/l
eccin_10_errores_comunes_en_topografa.html
Westoby, M., Brasington, N., Hambrey, M., & Reynolds, J. (2012). ‘Structure-from-
Motion’ photogrammetry: A low-cost, effective tool for geoscience applications.
Geomorphology.

Daniel Almagro Caballero de León 91
Universidad de Extremadura

<!-- p. 92 -->

Máster Universitario de Especialización en
Geotecnologías Topográficas en la Ingeniería.

Análisis de métodos para el Levantamiento Arquitectónico. Escuela Politécnica

INDICE DE REFERENCIAS PARTE PRÁCTICA

Pix4D
https://pix4d.com/
Pix4D Introduction Guide. https://support.pix4d.com/hc/en-
us/articles/202561499-Pix4D-Introduction-Guide#gsc.tab=0
Reconstrucción 3D usando PIX4D Monumento "Norma Patricia".
https://www.youtube.com/watch?v=QltTKhlxyBw

PhotoScan
http://softpcfull.com/agisoft-photoscan-professional-1-2-4-ml/
http://www.agisoft.com/index.php?id=32
http://www.agisoft.com/pdf/PS_1.1%20-Tutorial%20(BL)%20-%203D-
model.pdf
http://www.agisoft.com/pdf/PS_1.1%20-Tutorial%20(IL)%20-
%20Building.pdf

123D Catch

http://ecobarriosgrancanaria.es/contenido/tutoriales/autodesk123d.pdf
http://www.sacosta.org/ra/Autodesk_123D_Catch_2013.pdf

Visual SFM y MeshLab
http://ccwu.me/vsfm/
http://www.jpereira.net/software-revisiones-y-consejos/introducicon-a-la-
fotogrametria-parte-1
http://www.jpereira.net/apuntes-breves/virtualizar-visualsfm-para-
windows
https://www.youtube.com/watch?v=ZRTEMKS3Sw0

Daniel Almagro Caballero de León 92
Universidad de Extremadura

<!-- p. 93 -->

Máster Universitario de Especialización en
Geotecnologías Topográficas en la Ingeniería.

Análisis de métodos para el Levantamiento Arquitectónico. Escuela Politécnica

\10. INDICE DE FIGURAS Y TABLAS

Figura 1. Concepto gráfico sobre exactitud y precisión. Fuente:
https://instrumentacionelectronicai.wordpress.com/tag/exactitud/ _______________ 22
Figura 2. Esquema básico del funcionamiento de un láser-escáner. Fuente: García et al.
(2011). Láser escáner y nubes de puntos. Un horizonte aplicado al análisis arqueológico
de edificios. __________________________________________________________ 27
Figura 3. Fachada principal del edificio de Telecomunicaciones de Politecnica de la
UNEX. _____________________________________________________________ 33
Figura 4. Base topográfica BT 1000. ______________________________________ 35
Figura 5. Fotografía aérea con situación de las bases topográficas empleadas en la toma
de datos por topografía. ________________________________________________ 38
Figura 6. Coordenadas de los puntos en un archivo de bloc de notas. _____________ 42
Figura 7. Coordenadas de los puntos exportadas a Topocal. ____________________ 43
Figura 8. Vista de los puntos en Topocal. __________________________________ 43
Figura 9. Vista de los putnos en 3D con el programa AutoCAD.d _______________ 44
Figura 10. Vista en 3D del edificio delineado. _______________________________ 44
Figura 11. Plano fachada principal con mediciones. __________________________ 45
Figura 12. Esquema de toma de imágenes de objetos cercanos. _________________ 49
Figura 13. Cámara Réfles Olympus. ______________________________________ 50
Figura 14. Cámara de Smartphone Huawei P8 Lite. __________________________ 50
Figura 15. Pantalla principal 123D Catch. __________________________________ 52
Figura 16. Procesado de imágenes en 123d Catch. ___________________________ 53
Figura 17. Visión 3D del edificio procesado con 123D Catch. __________________ 53
Figura 18. Chequeo manual de puntos homólogos en 123D Catch. ______________ 54
Figura 19. Eliminación de puntos no relevantes en 123D Catch. ________________ 54
Figura 20. Medida de los puntos objeto de estudio con 123D Catch. _____________ 55
Figura 21. Medida de las distancias con DraftSight. __________________________ 56
Figura 22. Pantalla principal de PhotoScan. _________________________________ 57
Figura 23. Selección fotografías para procesar con PhotoScan.__________________ 58
Figura 24. Selección del cielo para restar de la imagen con PhotoScan. ___________ 58
Figura 25. Ventana de parámetros para orientación de imágenes con PhotoScan. ___ 59
Figura 26. Resultado edificio 3D con PhotoScan. ____________________________ 59
Figura 27. Creación de nube de punto densa con PhotoScan. ___________________ 59
Figura 28. Resultados nube de puntos densa con PhotScan. ____________________ 60
Figura 29. Depuración del modelo con PhotoScan. ___________________________ 60
Figura 30. Crear malla con PhotoScan. ____________________________________ 60
Figura 31. Crear textura con PhotoScan. ___________________________________ 61
Figura 32. Resultado tras mallar y texturizar el modelo con PhotoScan. ___________ 61
Figura 33. Modelo con medida tomadas en PhotoScan.________________________ 61
Figura 34. Vista superior del modelo con PhotoScan. _________________________ 62
Figura 35. Vista de alzado del resultado final con PhotoScan. __________________ 62
Figura 36. Pantalla principal programa fotogramétrico Pix4D. __________________ 63
Figura 37. Selección de fotografías en Pix4D. _______________________________ 63
Figura 38. Imágenes cargadas por el programa Pix4D. ________________________ 63
Figura 39. Selección de sistema de referencias arbitrario y unidades en metros en
Pix4D. ______________________________________________________________ 63
Figura 40. Selección de opción de procesado "3D models" con Pix4D. ___________ 63

Daniel Almagro Caballero de León 93
Universidad de Extremadura

<!-- p. 94 -->

Máster Universitario de Especialización en
Geotecnologías Topográficas en la Ingeniería.

Análisis de métodos para el Levantamiento Arquitectónico. Escuela Politécnica

Figura 41. Indicación de los pasos que ejecuta Pix4D. ________________________ 63
Figura 42. Importación de coordendas de puntos con Pix4D. ___________________ 63
Figura 43. Procesado de las imágenes con Pix4D. ____________________________ 63
Figura 44. Nube de puntos generado con Pix4D. _____________________________ 63
Figura 45. Visualización de la nube de puntos densa con Pix4D. ________________ 63
Figura 46. Toma de medidas con Pix4D. ___________________________________ 63
Figura 47. Toma de medidas con Pix4D con más detalle. ______________________ 63
Figura 48. Resultado final del modelo con Pix4D. ___________________________ 63
Figura 49. Pantalla principal del programa fotogramétrico VisualSFM. ___________ 70
Figura 50. Carga de imágenes con VisualSFM. ______________________________ 71
Figura 51. Nube de puntos creado con VisualSFM. ___________________________ 71
Figura 52. Nube de puntos densa con VisualSFM. ___________________________ 72
Figura 53. Visualización de la nube de puntos densa de VSFM con MeshLab. _____ 73
Figura 54. Depurado de la nube de puntos con MeshLab. ______________________ 73
Figura 55. Visualización del modelo depurado con MeshLab. __________________ 74
Figura 56. Opciones de mallado con MeshLab. ______________________________ 74
Figura 57. Visualización de la malla creada con MeshLab. _____________________ 75
Figura 58. Texturizado del modelo con MeshLab. ____________________________ 75
Figura 59. Medición de los puntos con MeshLab. ____________________________ 76
Figura 60. Visualización más cercana de las medidas tomadas con MeshLab. ______ 76
Figura 61. Coordenadas de los puntos tomados con MeshLab. __________________ 77
Figura 62. Coordenadas de los puntos con MeshLab. _________________________ 77
Figura 63. Toma de medidas entre los puntos anteriores con AutoCAD. __________ 78
Figura 64. Comparación de los diferentes modelos. __________________________ 84

Tabla 1. Precisión recomendada para levantamientos topográficos. ______________ 21
Tabla 2. Medidas obtenidas con la Estación Total. ___________________________ 45
Tabla 3. Medidas obtenidas con 123D Catch. _______________________________ 55
Tabla 4. Medidas obtenidas con AutoCAD tras ser importadas desde 123D Catch. __ 56
Tabla 5. Medidas obtenidas con PhotoScan. ________________________________ 62
Tabla 6. Medidas obtenidas del modelo con Pix4D. __________________________ 69
Tabla 7. Medidas obtenidas con MeshLab aplicando la media de los valores. ______ 76
Tabla 8. Medidas del modelo realizado con VisualSFM y MeshLab obtenidas en
AutoCAD. ___________________________________________________________ 78
Tabla 9. Medidas comparativas con flexómetro y estación total. ________________ 82
Tabla 10. Medidas obtenidas de los levantamientos fotogramétricos. _____________ 82
Tabla 11. Diferencia entre las medidas de cada programa y la estación total. _______ 82
Tabla 12. Análisis estadísticos de los errores cometidos por cada programa en la toma
de medidas. __________________________________________________________ 82
Tabla 13. Errores relativos en %. _________________________________________ 83

Daniel Almagro Caballero de León 94
Universidad de Extremadura

<!-- p. 95 -->

Máster Universitario de Especialización en
Geotecnologías Topográficas en la Ingeniería.

Análisis de métodos para el Levantamiento Arquitectónico. Escuela Politécnica

ANEXO I. Reseñas de las estaciones bases

Reseña del vértice A

Reseña literal

Vértice A, clavo de coordenadas absolutas situado en la explanada de baldosines que está en el edificio azul.
Está junto a un banco y cuyas coordenadas del GPDd son: x= 728624,380m, y= 4373254,473m y z= 423,78m.
Este vértice es un clavo grande con un cruz central.

Reseña pequeña escala

Reseña gran escala (fotografías)

Daniel Almagro Caballero de León 95
Universidad de Extremadura

<!-- p. 96 -->

Máster Universitario de Especialización en
Geotecnologías Topográficas en la Ingeniería.

Análisis de métodos para el Levantamiento Arquitectónico. Escuela Politécnica

Reseña del vértice B

Reseña literal

Vértice B, situado en la explana de baldosines del pabellón de informática, en el lado que se encuentra junto el
edificio de teleco. Este vértice es un clavo pequeño con arandela situado al lado de una tabadera de un registro de
agua.

Reseña pequeña escala

Reseña gran escala (fotografías)

Daniel Almagro Caballero de León 96
Universidad de Extremadura

<!-- p. 97 -->

Máster Universitario de Especialización en
Geotecnologías Topográficas en la Ingeniería.

Análisis de métodos para el Levantamiento Arquitectónico. Escuela Politécnica

Reseña del vértice C

Reseña literal

Vértice C, situado en el bordillo que delimita la escuela politécnica, entre el edificio azul y la carretera. Este
clavo es un clavo pequeño con arandela que se sitúa junto a la farola de esa zona.

Reseña pequeña escala

Reseña gran escala (fotografías)

Daniel Almagro Caballero de León 97
Universidad de Extremadura

<!-- p. 98 -->

Máster Universitario de Especialización en
Geotecnologías Topográficas en la Ingeniería.

Análisis de métodos para el Levantamiento Arquitectónico. Escuela Politécnica

ANEXO II. Toma de datos y cálculo de las coordenadas de la Poligonal

Daniel Almagro Caballero de León 98
Universidad de Extremadura

<!-- p. 99 -->

Máster Universitario de Especialización en
Geotecnologías Topográficas en la Ingeniería.

Análisis de métodos para el Levantamiento Arquitectónico. Escuela Politécnica

Cáculo de coordenadas planimétricas

Incremento de coordenadas Coordenadas absolutas Corrección Coordenadas finales
Estación Punto DX DY X Y DX DY X Y Punto
nº visado Calculada Calculada Calculada Calculada Compensada Compensada
Ea Ec --- --- --- --- --- --- --- ---
Eb -12,368 23,155 -12,368 23,155 0,000 0,001 -12,368 23,156 Eb
Eb Ea --- --- 0,000 0,000 --- --- --- ---
Ec 52,253 -22,452 39,885 0,703 -0,001 0,002 39,884 0,705 Ec
Ec Eb --- --- --- --- --- --- --- ---
Ea -39,886 -0,699 -0,001 0,004 -0,001 0,004 0,000 0,000 Ea
Error -0,0012 0,0042
Tolerancia para cierre de coordenadas 0,0149

Cálculo de coordenada altimétricas
Incremento de coordenadas Coordenadas absolutas Corrección Coordenadas finales
Estación Punto DZ Z DZ Z Punto
nº visado Calculada Calculada Compensada
Ea Ec --- --- --- ---
Eb -0,098 -0,098 0,013 -0,085 Eb
Eb Ea --- 0 --- ---
Ec -0,098 -0,196 0,019 -0,177 Ec
Ec Eb --- --- --- ---
Ea 0,158 -0,038 0,038 0,000 Ea
Error 0,038
Tolerancia para cierre en Z

Daniel Almagro Caballero de León 99
Universidad de Extremadura

<!-- p. 100 -->

Máster Universitario de Especialización en
Geotecnologías Topográficas en la Ingeniería.

Análisis de métodos para el Levantamiento Arquitectónico. Escuela Politécnica

ANEXO III. Toma de datos y cálculo de las coordenadas de la
Radiación

RADIACIÓN DESDE E. A.

Datos de la Estación Total
Aumentos (A) 30X
Sensibilidad (S) 40''
Apreciación (a) 10ᶜᶜ
Estadillo de campo
Dist Altura Lh Orientada a Lh Orientada a Punto Estación L.Horiz. L.Vert. reducida prisma NG NG Lv visado
(Dr) (m) (g) (Rad) (Rad)
E1 Ref. Eb 52,9472 - - - 368,768 5,793 -
1 155,7518 81,1698 35,252 0,000 71,573 1,124 1,275
Altura equipo: 2 119,2650 72,8530 23,627 0,000 35,086 0,551 1,144
(i) 3 114,3222 79,0934 31,434 0,000 30,143 0,473 1,242
1,567 4 104,4434 78,5820 30,706 0,000 20,265 0,318 1,234
5 104,4338 88,4114 30,722 0,000 20,255 0,318 1,389
6 94,4522 88,4770 30,733 0,000 10,273 0,161 1,390
7 104,4370 78,7088 30,706 0,000 20,258 0,318 1,236
8 154,2238 84,7104 0,000 70,045 1,100 1,331
9 153,1734 84,4356 32,688 0,000 68,995 1,084 1,326
10 152,4408 84,2608 0,000 68,262 1,072 1,324
11 151,3374 83,9874 32,680 0,000 67,159 1,055 1,319
12 150,5762 83,7900 32,261 0,000 66,397 1,043 1,316
13 149,3790 83,5072 31,656 0,000 65,200 1,024 1,312
14 148,4720 83,2942 31,222 0,000 64,293 1,010 1,308
15 147,2046 82,9912 30,648 0,000 63,026 0,990 1,304
16 145,3410 82,5286 29,844 0,000 61,162 0,961 1,296
17 136,6070 80,7726 26,927 0,000 52,428 0,824 1,269
18 134,0938 80,3002 26,270 0,000 49,915 0,784 1,261
19 132,3164 80,0256 25,851 0,000 48,138 0,756 1,257
20 130,9710 79,8112 25,553 0,000 46,792 0,735 1,254
21 129,1076 79,5148 25,174 0,000 44,929 0,706 1,249
22 127,7902 79,3410 24,918 0,000 43,611 0,685 1,246
23 125,8046 79,0750 24,568 0,000 41,626 0,654 1,242
24 124,4550 78,8872 24,354 0,000 40,276 0,633 1,239
25 122,3954 78,6344 24,055 0,000 38,217 0,600 1,235
26 122,3916 56,7154 24,073 0,000 38,213 0,600 0,891
27 124,4238 86,8214 24,371 0,000 40,245 0,632 1,364
28 125,8198 86,9612 24,591 0,000 41,641 0,654 1,366
29 127,7740 87,1088 24,929 0,000 43,595 0,685 1,368
30 129,0870 87,2738 25,175 0,000 44,908 0,705 1,371
31 130,9538 87,4048 25,554 0,000 46,775 0,735 1,373
32 131,5026 89,1340 31,451 0,000 47,324 0,743 1,400
33 148,9420 89,1340 31,451 0,000 64,763 1,017 1,400
34 149,3896 89,8454 0,000 65,211 1,024 1,411
35 150,5892 90,0022 32,280 0,000 66,410 1,043 1,414
36 151,3334 90,1564 0,000 67,155 1,055 1,416
37 152,4334 90,3178 0,000 68,255 1,072 1,419
38 153,1295 90,4370 0,000 68,951 1,083 1,421
39 154,2136 90,6004 34,335 0,000 70,035 1,100 1,423
40 122,4158 91,3900 24,064 0,000 38,237 0,601 1,436
41 122,4164 100,0475 24,073 0,000 38,238 0,601 1,572
42 131,5114 91,9230 25,662 0,000 47,333 0,743 1,444
43 148,8592 93,4136 31,402 0,000 64,680 1,016 1,467
44 145,3102 93,1638 29,835 0,000 61,131 0,960 1,463
45 136,6072 92,4276 26,903 0,000 52,428 0,824 1,452
46 119,3304 100,1700 23,601 1,500 35,152 0,552 1,573
47 155,8470 100,1714 15,262 1,500 71,668 1,126 1,573
48 114,2770 99,1554 31,391 1,978 30,098 0,473 1,558
49 94,4282 98,5894 30,708 2,200 10,249 0,161 1,549
Ref 0,0000 - - - - - -

Error cierre V_Horizonte 0,0000

Cálculo del error angular de la Estación Total
ev 10,28ᶜᶜ Error a priori 12,143
el 10ᶜᶜ
ed 15,92ᶜᶜ Errror de cierre 0
ep 2,25ᶜᶜ

ea 21,55ᶜᶜ

Daniel Almagro Caballero de León 100
Universidad de Extremadura

<!-- p. 101 -->

Máster Universitario de Especialización en
Geotecnologías Topográficas en la Ingeniería.

Análisis de métodos para el Levantamiento Arquitectónico. Escuela Politécnica

CALCULO de la Radiación

Ea 0,000 0,000 0,000

Estadillo de calculo

Punto visado Azimut t ΔX ΔY ΔZ X Y Z

Ref. Eb 368,768
1 71,573 10,742 31,796 15,223 12,309 31,796 15,223 12,309
2 35,086 10,734 12,372 20,129 12,301 12,372 20,129 12,301
3 30,143 10,711 14,334 27,976 12,278 14,334 27,976 12,278
4 20,265 10,739 9,610 29,163 12,306 9,610 29,163 12,306
5 20,255 5,655 9,611 29,180 7,222 9,611 29,180 7,222
6 10,273 5,624 4,938 30,334 7,191 4,938 30,334 7,191
7 20,258 10,670 9,607 29,164 12,237 9,607 29,164 12,237
8 70,045
9 68,995 8,155 28,887 15,298 9,722 28,887 15,298 9,722
10 68,262
11 67,159 8,398 28,427 16,121 9,965 28,427 16,121 9,965
12 66,397 8,397 27,870 16,249 9,964 27,870 16,249 9,964
13 65,200 8,390 27,043 16,455 9,957 27,043 16,455 9,957
14 64,293 8,386 26,438 16,608 9,953 26,438 16,608 9,953
15 63,026 8,389 25,623 16,816 9,956 25,623 16,816 9,956
16 61,162 8,402 24,461 17,098 9,969 24,461 17,098 9,969
17 52,428 8,389 19,752 18,300 9,956 19,752 18,300 9,956
18 49,915 8,399 18,551 18,600 9,966 18,551 18,600 9,966
19 48,138 8,388 17,737 18,806 9,955 17,737 18,806 9,955
20 46,792 8,387 17,136 18,956 9,954 17,136 18,956 9,954
21 44,929 8,392 16,328 19,161 9,959 16,328 19,161 9,959
22 43,611 8,382 15,766 19,296 9,949 15,766 19,296 9,949
23 41,626 8,379 14,944 19,501 9,946 14,944 19,501 9,946
24 40,276 8,386 14,400 19,641 9,953 14,400 19,641 9,953
25 38,217 8,391 13,589 19,849 9,958 13,589 19,849 9,958
26 38,213 19,463 13,598 19,865 21,030 13,598 19,865 21,030
27 40,245 5,118 14,401 19,661 6,685 14,401 19,661 6,685
28 41,641 5,108 14,962 19,515 6,675 14,962 19,515 6,675
29 43,595 5,118 15,768 19,309 6,685 15,768 19,309 6,685
30 44,908 5,101 16,322 19,167 6,668 16,322 19,167 6,668
31 46,775 5,123 17,131 18,961 6,690 17,131 18,961 6,690
32 47,324 5,421 21,285 23,154 6,988 21,285 23,154 6,988
33 64,763 5,421 26,755 16,533 6,988 26,755 16,533 6,988
34 65,211
35 66,410 5,112 27,890 16,252 6,679 27,890 16,252 6,679
36 67,155
37 68,255
38 68,951
39 70,035 5,107 30,601 15,571 6,674 30,601 15,571 6,674
40 38,237 3,275 13,600 19,852 4,842 13,600 19,852 4,842
41 38,238 -0,018 13,605 19,860 1,549 13,605 19,860 1,549
42 47,333 3,273 17,370 18,890 4,840 17,370 18,890 4,840
43 64,680 3,260 26,692 16,542 4,827 26,692 16,542 4,827
44 61,131 3,216 24,445 17,105 4,783 24,445 17,105 4,783
45 52,428 3,215 19,735 18,284 4,782 19,735 18,284 4,782
46 35,152 -0,063 12,379 20,094 0,004 12,379 20,094 0,004
47 71,668 -0,041 13,775 6,570 0,026 13,775 6,570 0,026
48 30,098 0,416 14,294 27,948 0,005 14,294 27,948 0,005
49 10,249 0,681 4,923 30,311 0,048 4,923 30,311 0,048

Daniel Almagro Caballero de León 101
Universidad de Extremadura

<!-- p. 102 -->

Máster Universitario de Especialización en
Geotecnologías Topográficas en la Ingeniería.

Análisis de métodos para el Levantamiento Arquitectónico. Escuela Politécnica

RADIACIÓN DESDE E. B.

Estadillo de campo
Dist Altura Lh Orientada a Lh Orientada a
Punto Lv
Estación L.Horiz. (g) L.Vert. (g) reducida prisma NG NG
visado
(Dr) (m) (g) (Rad) (Rad)
EB Ref, Ea 0,0000 - - - 168,756 2,651 -
b2 338,9570 73,8950 24,911 0,000 107,713 1,692 1,161
Altura equipo:
b3 319,8826 75,8306 27,130 0,000 88,638 1,392 1,191 i(m)
b4 314,2176 71,7590 22,771 0,000 82,973 1,303 1,127
1,580 b5 306,2124 81,1302 18,724 0,000 74,968 1,178 1,274
b6 296,2728 83,4386 21,494 0,000 65,028 1,021 1,311
b7 278,4758 88,6412 31,613 0,000 47,231 0,742 1,392
b8 267,7058 92,3148 47,005 0,000 36,461 0,573 1,450
b9 263,6892 93,1782 0,000 32,445 0,510 1,464
b10 263,6910 87,2596 53,319 0,000 32,447 0,510 1,371
b11 283,4095 86,1192 25,593 0,000 52,165 0,819 1,353
b12 343,1164 90,1238 34,739 0,000 111,872 1,757 1,416
Ref 0,0001 - - - - - -

Error cierre V_Horizonte 0,0001

CALCULO de la Radiación

Eb -12,368 23,156 -0,085

Estadillo de calculo
Punto visado Acimut t ΔX ΔY ΔZ X Y Z
Ref, Ea 168,7555
b2 107,7125 10,829 24,728 -3,011 12,409 12,360 20,145 12,324
b3 88,6381 10,825 26,699 4,816 12,405 14,331 27,972 12,320
b4 82,9731 10,821 21,961 6,018 12,401 9,593 29,174 12,316
b5 74,9679 5,718 17,295 7,174 7,298 4,927 30,330 7,213
b6 65,0283 5,721 18,332 11,222 7,301 5,964 34,378 7,216
b7 47,2313 5,701 21,361 23,305 7,281 8,993 46,461 7,196
b8 36,4613 5,702 25,473 39,504 7,282 13,105 62,660 7,197
b9 32,4447
b10 32,4465 10,815 26,014 46,542 12,395 13,646 69,698 12,310
b11 52,1650 5,670 18,702 17,471 7,250 6,334 40,627 7,165
b12 111,8719 5,433 34,137 -6,441 7,013 21,769 16,715 6,928

Daniel Almagro Caballero de León 102
Universidad de Extremadura

<!-- p. 103 -->

Máster Universitario de Especialización en
Geotecnologías Topográficas en la Ingeniería.

Análisis de métodos para el Levantamiento Arquitectónico. Escuela Politécnica

RADIACIÓN DESDE E. C.

Estadillo de campo
Dist Altura Lh Orientada a Lh Orientada a
Punto L.Vertica Lv
Estación L.Horiz. reducida prisma NG NG
visado l
(Dr) (m) (g) (Rad) (Rad)
EC Ref a A 0,0000 - - - 298,8845 - -
C2 40,2830 78,7920 33,631 - 339,1675 5,3276 1,2377
Altura
C13 111,4512 68,2212 20,272 - 10,3357 0,1624 1,0716
equipo: i(m)
C14 84,1310 71,8170 23,246 - 383,0155 6,0164 1,1281
1,520 C15 91,1938 75,9976 22,016 - 390,0783 6,1273 1,1938
C16 89,0704 76,2958 22,354 - 387,9549 6,0940 1,1985
C17 87,4910 76,5576 22,619 - 386,3755 6,0692 1,2026
C18 85,4706 76,9035 22,992 - 384,3551 6,0374 1,2080
C19 85,4710 85,2492 22,990 - 384,3555 6,0374 1,3391
C20 87,5020 85,0434 22,616 - 386,3865 6,0693 1,3359
C21 89,0194 84,8646 22,357 - 387,9039 6,0932 1,3331
C22 91,1462 84,6988 22,026 - 390,0307 6,1266 1,3304
C23 91,1598 89,6760 22,020 - 390,0443 6,1268 1,4086
C24 89,0538 89,8174 22,349 - 387,9383 6,0937 1,4108
C25 87,4825 89,9256 22,620 - 386,3670 6,0690 1,4125
C26 85,4704 90,0476 22,994 - 384,3549 6,0374 1,4145
C27 85,4704 93,5312 22,993 - 384,3549 6,0374 1,4692
C28 91,1780 99,1488 22,021 - 390,0625 6,1271 1,5574
C29 116,1442 88,5032 60,417 - 15,0287 0,2361 1,3902
C30 112,4650 73,2132 24,638 - 11,3495 0,1783 1,1500
C31 49,1484 84,5574 22,962 - 348,0329 5,4669 1,3282
C32 65,5394 91,5566 17,539 - 364,4239 5,7244 1,4382
Ref 0,0000 - - - - - -

Error cierre V_Horizont 0,0000

CALCULO de la Radiación
Ec 39,884 0,705 -0,177
Estadillo de calculo
Punto visado Acimut t ΔX ΔY ΔZ X Y Z
Ref
C2 339,1675 11,637 -27,464 19,410 13,157 12,420 20,115 12,980
C13 10,3357 11,053 3,277 20,005 12,573 43,161 20,710 12,396
C14 383,0155 11,020 -6,129 22,424 12,540 33,755 23,129 12,363
C15 390,0783 8,718 -3,417 21,749 10,238 36,467 22,454 10,061
C16 387,9549 8,731 -4,204 21,955 10,251 35,680 22,660 10,074
C17 386,3755 8,727 -4,804 22,103 10,247 35,080 22,808 10,070
C18 384,3551 8,728 -5,594 22,301 10,248 34,290 23,006 10,071
C19 384,3555 5,424 -5,593 22,299 6,944 34,291 23,004 6,767
C20 386,3865 5,413 -4,799 22,101 6,933 35,085 22,806 6,756
C21 387,9039 5,418 -4,222 21,955 6,938 35,662 22,660 6,761
C22 390,0307 5,398 -3,435 21,756 6,918 36,449 22,461 6,741
C23 390,0443 3,603 -3,430 21,751 5,123 36,454 22,456 4,946
C24 387,9383 3,605 -4,209 21,949 5,125 35,675 22,654 4,948
C25 386,3670 3,610 -4,807 22,103 5,130 35,077 22,808 4,953
C26 384,3549 3,624 -5,594 22,303 5,144 34,290 23,008 4,967
C27 384,3549 2,344 -5,594 22,302 3,864 34,290 23,007 3,687
C28 390,0625 0,294 -3,423 21,753 1,814 36,461 22,458 1,637
C29 15,0287 11,031 14,131 58,741 12,551 54,015 59,446 12,374
C30 11,3495 11,025 4,369 24,248 12,545 44,253 24,953 12,368
C31 348,0329 5,682 -16,730 15,727 7,202 23,154 16,432 7,025
C32 364,4239 2,340 -9,299 14,871 3,860 30,585 15,576 3,683

Daniel Almagro Caballero de León 103
Universidad de Extremadura

<!-- p. 104 -->

Máster Universitario de Especialización en
Geotecnologías Topográficas en la Ingeniería.

Análisis de métodos para el Levantamiento Arquitectónico. Escuela Politécnica

ANEXO IV. Modelos 3D

123D CATCH

Daniel Almagro Caballero de León 104
Universidad de Extremadura

<!-- p. 105 -->

Máster Universitario de Especialización en
Geotecnologías Topográficas en la Ingeniería.

Análisis de métodos para el Levantamiento Arquitectónico. Escuela Politécnica

PHOTOSCAN

Daniel Almagro Caballero de León 105
Universidad de Extremadura

<!-- p. 106 -->

Máster Universitario de Especialización en
Geotecnologías Topográficas en la Ingeniería.

Análisis de métodos para el Levantamiento Arquitectónico. Escuela Politécnica

PIX4D

Daniel Almagro Caballero de León 106
Universidad de Extremadura

<!-- p. 107 -->

Máster Universitario de Especialización en
Geotecnologías Topográficas en la Ingeniería.

Análisis de métodos para el Levantamiento Arquitectónico. Escuela Politécnica

VISUAL SFM

Daniel Almagro Caballero de León 107
Universidad de Extremadura

<!-- p. 108 -->


