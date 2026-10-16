---
type: libro
title: "7º CONGRESO IBEROAMERICANO DE INGENIERIA MECANICA"
author: "Rosabel"
categoria: "Tesis doctorales y análisis"
paginas: 15
extraccion: "texto"
fuente: "local:E:/Biblioteca digital/Tesis doctorales y análisis/Fotogrametria_digital_terrestre_versus_e.pdf"
convertido: 2026-10-13
---

# 7º CONGRESO IBEROAMERICANO DE INGENIERIA MECANICA

> Texto extraído de `Tesis doctorales y análisis/Fotogrametria_digital_terrestre_versus_e.pdf` (15 páginas, texto). El PDF original está en el disco E: (Biblioteca digital); `<!-- p. N -->` marca el inicio de cada página.

<!-- p. 1 -->

FOTOGRAMETRÍA DIGITAL TERRESTRE VERSUS ESCÁNER LÁSER:
METODOLOGÍA Y ANÁLISIS MÉTRICO

Silvana Salazar 1, Berenice Eliana Rueda Suspichiatti 1,
Gonzalo Sanchez Rossi 1, Salvatore Barba 2

1 UNC, Facultad de Ciencias Exactas, Físicas y Naturales, Córdoba, Argentina
2 UNISA, Dipartimento di Ingegneria Civile, Salerno, Italia
1 salazar_s@cordoba.gov.ar, 2 sbarba@unisa.it,

RESUMEN

El presente trabajo tiene como objetivo realizar un análisis comparativo de los
procedimientos, precisiones y resultados obtenidos al aplicar dos técnicas diferentes
de levantamiento tridimensional para la documentación del patrimonio. Con el fin de
alcanzar el objetivo propuesto se comparan dos modelos tridimensionales, uno
obtenido a partir de la aplicación de las técnicas de fotogrametría digital y el otro
levantado con escáner láser.
En la primera etapa del trabajo, se detalla cada técnica de levantamiento, el
instrumental utilizado y los procedimientos llevados a cabo para obtener el modelo 3D
de la fachada oeste del Museo Superior de Bellas Artes Evita - Palacio Ferreyra, uno
de los museos de bellas artes más importantes de la Argentina.
Para realizar el análisis métrico de las precisiones conseguidas con cada técnica de
medición, se empleó una estación total con distanciómetro láser con la que se
levantaron puntos fácilmente identificables en el edificio, especificando coordenadas
precisas para estos puntos. A partir de estas coordenadas se identificaron las mismas
en cada una de las nubes de puntos obtenidas con fotogrametría digital y con
escáner láser, comparando las distancias entre los vectores y las diferencias en las
coordenadas a fin de analizar la precisión en cada técnica de levantamiento.
Además, con la utilización de diferentes software de diseño se procesó cada nube de
puntos, se obtuvieron diversos modelos y a partir de ello se generó una malla
poligonal para cada técnica, las cuales se superpusieron analizando la desviación
espacial.
Si bien la importancia de este trabajo radica en el análisis e investigación científicotécnica con el que se ha estudiado cada método de levantamiento para la
documentación del patrimonio, es de destacar que esta metodología puede ser de
aplicación en las estrategias de recuperación, conservación, restauración y
promoción del territorio, como así también la búsqueda de alternativas económicas
para llevar a cabo dichas tareas.

PALABRAS CLAVES:
Levantamiento arquitectónico; Modelo tridimensional; Análisis espacial de errores.

1

<!-- p. 2 -->

\1. INTRODUCCIÓN

El registro gráfico del patrimonio puede abordarse de manera más expeditiva mediante
croquis o fotografías en combinación de mediciones con cinta métrica o distanciómetro
láser, o de manera rigurosa mediante técnicas topográficas y fotogramétricas. Si nos
centramos en la componente métrico-topográfica como base y soporte científico de los
estudios analíticos anteriores, presentes o posteriores al proceso de conservación y/o
restauración, comprobaremos que en la actualidad predominan los procesos
fotogramétricos digitales realizados a partir de imágenes fotográficas y los
levantamientos mediante escáner láser. Ello no implica que sólo y exclusivamente se
deban realizar documentaciones mediante estas alternativas indirectas, sino que lo
normal es que se combinen con procesos de medición directa, estación total o
sistemas de posicionamiento global por satélite (GNSS). La decisión final dependerá de
la complejidad y del tamaño del objeto, monumento o sitio y de otros aspectos como
los requerimientos de coste, el plazo de entrega y el tipo de producto final. Además es
importante considerar, por ejemplo: la accesibilidad, la complejidad de los detalles a
registrar, el peligro de deterioro gradual debido a factores múltiples, y el estado de
conservación en el momento en que se efectúa el levantamiento.
La documentación del patrimonio a partir de imágenes fotográficas se remonta a los
orígenes de la fotografía a mediados del siglo XVIII, y luego de la Segunda Guerra
Mundial se desarrollaron la fotogrametría analógica, analítica y digital en sus múltiples
versiones: fotogrametría de objeto cercano, fotogrametría terrestre y fotogrametría
aérea. Si bien las técnicas clásicas de fotogrametría limitaban el uso masivo debido al
alto costo de cámaras métricas calibradas, con la revolución digital y el desarrollo de
nuevos software hoy la fotogrametría digital puede preferirse en relación al costo
frente a levantamiento con escáner láser los cuales realizan la captura automatizada
de grandes nubes de puntos, permitiendo su adquisición de manera sistemática, a
altas frecuencias (hasta un millón de puntos por segundo), en tiempo casi real y junto
con valores de intensidad o color asociados.

\2. OBJETIVOS

El propósito de la investigación es realizar un análisis comparativo de los
procedimientos, precisiones y resultados obtenidos al emplear dos técnicas diferentes
de levantamiento tridimensional aplicado a la documentación y representación gráfica
del patrimonio (siendo el objeto de estudio el Museo Superior de Bellas Artes Evita -
Palacio Ferreyra de la Ciudad de Córdoba, Argentina).
La finalidad de este trabajo es experimentar si las precisiones obtenidas a partir de
estas nuevas técnicas de levantamiento fotogramétricas con cámaras digitales
pueden equipararse con las obtenidas con la técnica de levantamiento a partir de
escáner laser, para lo que se realizan análisis estadísticos, gráficos y espaciales de
los datos y resultados obtenidos.

2

<!-- p. 3 -->

Figura 1: Ubicación del Palacio Ferreyra en su entorno en la Ciudad de Córdoba.

\3. METODOLOGÍA

La metodología propuesta para dar respuesta a los objetivos planteados de
comparación de dos técnicas de levantamiento tridimensional aplicables a la
representación gráfica del patrimonio, como lo son la fotogrametría digital y el
escáner laser, responde a una serie de etapas y/o procedimientos a seguir, que se
exponen a continuación.
Primera etapa: estudio de antecedentes de registros gráficos y levantamientos
métricos. Consiste en la búsqueda y recopilación de datos gráficos preexistentes,
analógicos y digitales, como así también de antiguos levantamientos del patrimonio
en estudio.
En esta primera fase se realizó una compilación de información gráfica preexistente;
esta información permitió planificar los levantamientos a realizar y poder efectuar
comparaciones con los datos obtenidos a través de las técnicas de levantamiento
digital desarrolladas.
Segunda etapa: levantamiento digital tridimensional (fotogrametría digital y
escáner laser). Comprende la realización de un exhaustivo levantamiento con
fotogrametría digital y con escáner laser, de manera normalizada y siguiendo
procedimientos y reglas pre establecidas. Estos levantamientos se complementan
con las tomas de coordenadas espaciales empleando una estación total láser, el
cual se ejecuta con el fin de obtener mayor precisión en la reconstrucción

3

<!-- p. 4 -->

tridimensional de la obra objeto de estudio y para identificar puntos coordenados
que ayudarán a efectuar las comparaciones posteriores.
Para el levantamiento fotogramétrico se utilizó una cámara digital réflex NIKON
D100 de 6,1Mpx, con una lente de 28mm; además, dicha cámara estaba montada
sobre una barra estabilizadora de Menci solidaria a un trípode. En tanto que, para
efectuar el levantamiento con escáner laser se dispuso de un escáner laser Leica
HDS 3000 de tiempo de vuelo, con: cámara fotográfica integrada, un campo de
visual máximo de 360° x 270° y alcance bueno y eficaz entre 1m y 100m del objeto
a escanear.
Tercera etapa: procesamiento de datos y obtención de modelos tridimensionales.
Se utilizan dos software para la reconstrucción y análisis de los modelos
tridimensionales:
\- PhotoScan Professional Edition de Agisoft LLC, destinado al procesamiento
de las imágenes adquiridas con cualquier tipo de cámara digital ya sea métrica o
no métrica, dando una solución fotogramétrica a la generación automática de
modelos poligonales texturizados georreferenciados, ortomosaicos, y modelos
digitales del terreno y de superficie. Este software permite procesar de manera
rápida, simple e intuitiva, proveyendo resultados ‘sumamente’ precisos. Entre sus
usos destaca la aplicación en la preservación del patrimonio cultural y
arquitectónico, ya que PhotoScan es una herramienta de calidad para resolver
las tareas de modelado arquitectónico, permitiendo obtener fotos orto-rectificadas
de fachadas o reconstrucciones de edificios enteros. Los modelos
tridimensionales de monumentos parcialmente en ruinas y de objetos generados
con PhotoScan presentan una base fiable para los trabajos de restauración
gracias a su precisión en los resultados de la reconstrucción.
\- Geomagic Studio, es un software destinado al diseño, tratamiento y análisis de
nubes de puntos y modelos tridimensionales, que proporciona funciones de
edición de nubes de puntos, edición de mallas, creación de superficies y análisis
de modelos, bastante potentes y sobre todo fácil de usar incorporando muchas
herramientas automatizadas, que permiten producir modelos de alta calidad. Se
aplica en ingeniería inversa, diseños de productos, creación rápida de prototipos,
exportación de resultados y análisis. Además, Geomagic Studio es compatible
con una amplia gama de digitalizadores, cámaras y escáneres laser 3D, y ha sido
optimizado para un procesamiento de datos rápido, con la capacidad de
gestionar nubes de puntos muy densas de forma eficaz.
Cuarta etapa: comparación entre las técnicas de levantamiento empleadas,
mediante nubes de puntos.
Se comparan las precisiones obtenidas para cada técnica de medición, para ello se
empleó una Estación Total Sokkia SET650RX, la cual trae incorporado un
distanciómetro láser que permite medir distancias sin la utilización de prisma ni
tarjeta reflectante para puntos que están ubicados a una distancia máxima de 400
m. Dicho instrumental tiene una precisión angular de 6” y si se utiliza el método de

4

<!-- p. 5 -->

medición precisa, la precisión en la distancia es de ± (3 + 2 ppm x D) mm. Con
dicho instrumental se ejecutó un levantamiento planialtimétrico tomando puntos
fácilmente identificables en el edificio y definiendo coordenadas “exactas” para
estos puntos. A partir de éstos, se identificaron los mismos puntos en cada una de
las nubes obtenidas con fotogrametría digital y con escáner láser, comparando las
distancias entre los vectores medidos en las respectivas nubes de puntos con las
distancias de los vectores medidos con estación total. Los vectores medidos con
estación total fueron tomados como medida patrón de comparación, con el fin de
comparar las precisiones logradas mediante cada técnica de levantamiento
tridimensional.
Quinta etapa: comparación entre las técnicas de levantamiento empleadas,
mediante modelos de mallas. Se compara la correlación espacial entre los
productos obtenidos en base a las técnicas de levantamiento tridimensional
empleando fotogrametría digital terrestre y escaneo laser terrestre en forma de
modelos de mallas o de superficie, confeccionados en base a los modelos de nubes
de puntos correspondientes a cada técnica. De esta manera se intenta presentar
una metodología sistematizada que permita y facilite el análisis y procesamiento de
los datos obtenidos.

\4. DESARROLLO: LEVANTAMIENTO DIGITAL TRIDIMENSIONAL

Las técnicas de levantamiento digital empleadas, tanto la fotogrametría digital como
así también el escaneo láser, permiten una rápida adquisición de datos, con
altísimos niveles de precisión. Además, ofrecen la posibilidad de ajustar estas
precisiones a través de la configuración de los parámetros de calibración de los
instrumentos, como así también del software utilizados para el tratamiento de los
datos. Estos procedimientos contemporáneos han reducido las dimensiones y los
tiempos de trabajo en medidas significantes, contribuyendo a una disminución
significativa en la cantidad de personal necesario para realizar estos levantamientos
en comparación con la aplicación de técnicas tradicionales.
Los diferentes métodos de levantamiento que se explican a continuación, fueron
aplicados en la fachada Oeste del Palacio Ferreyra.

Fotogrametría digital
La metodología que se siguió con esta técnica, consistió en levantar el edificio
tomando una serie de fotografías con una cámara digital Nikon D100 y realizando
los disparos manteniendo fija la distancia de separación entre toma y toma sobre el
eje horizontal. La distancia entre el objeto (fachada) en cuestión y el
posicionamiento de la cámara debe ser en preferencia aproximadamente igual, de
manera paralela o convergente a ella (nunca divergente). Superponiendo franjas
fotográficas a lo alto y ancho de la fachada siempre garantizando un solapamiento
mayor al 50% en horizontal y 70% en vertical.

5

<!-- p. 6 -->

Figura 2: Vista en planta de la localización de las cámaras y del solapamiento.

Escáner laser
Se realizó un levantamiento polar ubicando el escáner en dos estaciones (Figura 3), las
cuales estaban georreferenciadas a través de targets de puntería que permiten
combinar los levantamientos realizados desde cada estación.

Estación Total
Se empleó el método polar, registrando las coordenadas tridimensionales desde sólo
una estación, ubicada frente a la fachada del Palacio Ferreyra. Sobre dicha fachada se
levantaron 109 puntos, correspondientes a elementos constructivos debido a la
imposibilidad de colocar targets de puntería. El criterio de elección de estos elementos
estuvo vinculado a la posición, geometría y contraste, para que fueran fácilmente
identificables con su correspondiente pixel en las imágenes para un mejor ajuste
fotogramétrico y post-proceso de los datos, como así también para lograr la
identificación en las nubes de puntos para una correcta comparación de precisiones.

Procesamiento de datos y obtención de modelos
Con el uso del software ruso de procesamiento de imágenes PhotoScan de Agisoft
LLC se logró reconstruir la geometría de la fachada Oeste, obteniendo así un modelo
tridimensional de carácter métrico. Luego de la obtención de 252 imágenes, se
organizaron en un mismo espacio de trabajo, ya que todas pertenecen a un área
homogénea, para realizar la reconstrucción tridimensional del objeto.

6

<!-- p. 7 -->

Figura 3: Localización de las estaciones de levantamiento: estación total (rojo)
escáner Láser (azul) y estimación del eje donde se posicionó la cámara para la
captura de las fotografías (amarillo).

Básicamente se siguió el siguiente esquema de trabajo para el procesamiento de
imágenes y reconstrucción del modelo 3D, consistente en los pasos citados a
continuación:
\- ajustes previos y confección de las máscaras, se enmascararon las áreas de las
imágenes que no son parte del objeto levantado y que pueden ser confusas
para el programa o causantes de llevar a resultados de reconstrucción
incorrectos, excluyéndolas del procesamiento;
\- alineación de las fotografías, el algoritmo encuentra la posición de la cámara y
la orientación de cada fotografía a partir de la correspondencia entre puntos
homólogos, y se construye un modelo de nube de puntos de baja densidad;
\- filtrado, se eliminaron aquellos puntos que tenían un alto error de registración y
un alto nivel de ruido;
\- creación de los marcadores, se especificaron sus ubicaciones (definida por sus
proyecciones en las fotos de origen) dentro de la escena, para utilizar aquellos
seleccionados para la creación de un sistema de coordenadas con el fin de
optimizar la alineación de las fotos y realizar mediciones;
\- optimización del modelo, se fijan los parámetros finales de orientación de la
cámara y escala, se georreferencia el modelo minimizando los errores y
deformaciones para mejorar las precisiones a la hora de realizar mediciones;

7

<!-- p. 8 -->

\- generación de la nube de puntos densa, el programa calcula a partir de la
posición de las cámaras y de las imágenes de origen una nube de puntos densa
(cabe mencionar que dicha nube de puntos tiene una densidad similar a una
nube de puntos LIDAR);
\- construcción de la mesh y textura, el programa calcula y genera una malla
poligonal 3D para así representar texturizada la geometría del modelo.

Resulta demasiado extenso detallar las diferentes configuraciones de los
parámetros en cada una de las etapas que definen el flujo de trabajo, pero es
pertinente aclarar que los parámetros de configuración pueden variar ampliamente
los resultados. El software ruso ofrece la posibilidad de exportar nubes de puntos,
datos de calibración y orientación, mallas, ortofotos, modelos digitales de
elevación, entre otros en múltiples formatos.

Para los datos obtenidos con escáner laser se utilizó el software de diseño
Geomagic Studio para realizar un filtrado, eliminando aquellos puntos que tenían
un alto nivel de ruido e inconsistencia, lo que permitió trabajar exclusivamente con
la zona en estudio de manera más simple. Conjuntamente, se generó un
sombreado de la nube de puntos para facilitar la identificación de puntos
coordenados. Luego, se procesó un modelo tridimensional en forma de malla
partiendo del modelo en forma de nubes de puntos, para efectuar comparaciones
con el correspondiente modelo obtenido por fotogrametría digital terrestre.

Figura 4: Nube de puntos fotogramétrica de 12.500.358 puntos.

8

<!-- p. 9 -->

Figura 5: Ortofoto de la fachada Oeste del Palacio Ferreyra.

Figura 6: Nube de puntos desde escáner laser, de 11.775.180 puntos.

\5. COMPARACIÓN ENTRE LAS TÉCNICAS EMPLEADAS

Para un correcto análisis comparativo entre las técnicas de levantamiento, es
necesario mencionar que ambas deben ser planificadas y llevadas a cabo
adecuadamente y de acuerdo a una misma finalidad de trabajo para que los
resultados sean coherentes.
Para el desarrollo de esta etapa se estableció como data base la información
obtenida a partir de la reconstrucción de la geometría del objeto en forma de
modelos tridimensionales obtenidos a partir de fotogrametría digital y de escáner

9

<!-- p. 10 -->

laser, los cuales presentan una escala real del objeto, lo que permite realizar un
análisis con un alto nivel de precisión.

En una primera instancia, para llevar a cabo la comparación se identificaron en la
geometría de ambos modelos los puntos coordenados medidos con estación total
laser, criteriosamente seleccionados para lograr una correcta distribución en los
modelos a comparar, como se muestran en la Figura 7.
Una vez identificados, se procedió a tomar los valores de coordenadas para cada
uno de estos puntos en su correspondiente modelo, y luego se confeccionó una
matriz que permita el cálculo de la distancia de los vectores, formados por la
combinación entre todos los puntos coordenados. Esta matriz de vectores se
confeccionó tanto para los puntos medidos con la estación total laser, como así
también para los puntos medidos sobre los modelos obtenidos del levantamiento
con la técnica de fotogrametría digital y de escáner laser.
Posteriormente, con la obtención de estas matrices, se llevó a cabo la comparación
entre la matriz de vectores obtenidos a partir del modelo generado por la técnica de
levantamiento fotogramétrico versus la matriz de vectores medidos con estación
total laser (utilizada como patrón de comparación), para así obtener los errores
correspondientes para cada vector. El mismo procedimiento se ejecutó para la
matriz de vectores definidos a partir del modelo generado con la técnica de
levantamiento con escáner laser versus la matriz de vectores medidos con estación
total laser.

Figura 7: Puntos coordenados utilizados en la comparación.

10

<!-- p. 11 -->

Los resultados logrados fueron los siguientes:

Figura 8: Resultados obtenidos empleando fotogrametría y escáner laser terrestre.

Figura 9: Gráficos comparativos, diagrama de distribución de frecuencias (izquierda)
y diagrama de caja (derecha).

11

<!-- p. 12 -->

En la figura 8 se presentan gráficos estadísticos donde se visualizan
comparativamente los resultados obtenidos. A la izquierda se presenta el diagrama
de distribución de frecuencias, donde puede observarse que para el modelo obtenido
mediante fotogrametría el 64,67% de los vectores comparados tienen una diferencia
de distancia menor a 2cm respecto a la distancia medida con estación total, de los
cuales el 37,69% es menor a 1cm; mientras que en el modelo obtenido con escáner,
el 60,13% de los vectores comparados tienen una diferencia de distancia menor a
2cm, de los cuales el 37,69% es menor a 1cm. A la derecha, el diagrama de caja
refleja las medidas descriptivas y el sesgo de la variable, observando en ambos
modelos diferencias similares entre la media y la mediana.
Si bien puede presumirse que los valores del modelo con escáner laser arrojen menor
error, es de mencionar que los resultados obtenidos en este trabajo utilizando
fotogrametría se debieron a que se realizó un procedimiento normalizado y muy
riguroso, con gran tiempo de levantamiento y post-proceso; considerando además que
la nube de puntos fotogramétrica era más densa que la obtenida con escáner láser.

Además se generó un análisis de las bondades del modelo confeccionado por
fotogrametría digital, donde se obtuvo la incertidumbre de un punto en el espacio
tridimensional teniendo como patrón de comparación los puntos coordenados
obtenidos con estación total laser. En la figura 9 se presentan las medidas
descriptivas que resultan de dicho análisis estadístico y a través de un diagrama de
cajas y bigotes se describen al mismo tiempo varias características importantes del
conjunto de datos, tales como el centro, la dispersión, la asimetría y la identificación
de observaciones atípicas. Del diagrama se interpreta que la distribución de los datos
es asimétrica por la derecha, ya que la longitud de los rectángulos de valores por
debajo y por encima de la mediana, así como los bigotes, indican que los datos están
más agrupados en sus valores inferiores que en los superiores; además se observa
que la media es mayor a la mediana.

Figura 10: Análisis de las bondades del modelo fotogramétrico.

12

<!-- p. 13 -->

Como puede observarse el valor medio resultó igual a 0.0396m, se puede
interpretar como el error más probable en cualquier punto del modelo 3D obtenido
con respecto a la realidad, siendo un valor aceptable para este tipo de aplicación en
lo que respecta a la indeterminación de un punto en el espacio tridimensional.
Los errores analizados comprenden tanto errores accidentales como sistemáticos:
errores en la topografía, es decir en la medición de los puntos coordenados de control
sobre puntos característicos de la fachada empleando estación total laser sin prisma;
error en el marcado de los GCP, es decir por la dificultad para identificar cada punto
coordenado de control sobre el modelo 3D; errores derivados de la inestabilidad de
los parámetros internos de la cámara; errores algorítmicos en la construcción del
modelo 3D en el software; tal vez incluso pueden darse afecciones atmosféricas que
distorsionan las imágenes por gradiente de temperatura, reverberación, etc.

Para una comparación a partir de modelos en forma de mallas, se analizaron las
desviaciones entre los modelos tridimensionales obtenidos a partir de fotogrametría
digital terrestre y de escáner laser terrestre en forma de mallas poligonales 3D. Para
ello, se exportaron sendos modelos en el software Geomagic Studio donde se
realizó una alineación mediante un procedimiento iterativo y automático con el fin de
lograr la mínima desviación espacial entre ellos. Una vez alineados los modelos,
donde se obtuvo una convergencia media de 5cm con una desviación estándar de
aproximadamente 5cm, se empleó una herramienta de análisis para confeccionar
un mapa codificado a través de colores que permite visualizar las desviaciones 3D
entre ambos modelos tridimensionales de mallas comparados.

Figura 11: Procedimiento de alineación de los modelos de mallas.

13

<!-- p. 14 -->

Figura 12: Desviación entre los modelos 3D en forma de mallas.

Se puede interpretar que existe una muy buena correlación espacial entre ambos
modelos analizados, donde las desviaciones de mayor intensidad se presentan en
la zona derecha de la fachada, donde el levantamiento, por supuesto, careció del
levantamiento de tomas convergentes a la edificación, lo que seguramente hubiera
permitido mejorar estos resultados. Este mapa codificado además permite visualizar
cómo en un área tal como el acceso al edificio, la cual no estuvo planificada dentro
del estudio, las desviaciones se manifiestan de una manera considerable por estar
en un segundo plano dentro de las imágenes capturadas.

\6. CONCLUSIONES

El escaso conocimiento y conciencia sobre la situación actual que atraviesan
nuestros patrimonios, lleva a plantear la necesidad de una adecuada aplicación de
metodologías de documentación gráfica-métrica, realizar proyectos de conservación y
de intervención. Las posibilidades que brinda la aplicación de las técnicas de
levantamiento tridimensional mediante fotogrametría, nos permiten contar con la
información necesaria a la hora de realizar las actividades de preservación del
patrimonio, sin mayores inconvenientes por el nivel de precisión que se alcanza. En
efecto, de manera precisa, como se demuestra en la etapa de comparación entre
ambas técnicas de levantamiento, se obtienen productos de muy alta calidad –
modelos tridimensionales, nubes de puntos, ortofotos, etc. – y en tiempos muy
reducidos en comparación a métodos clásicos. De esta manera se cumple el objetivo
planteado de verificar las precisiones obtenidas a partir de estas técnicas de
levantamiento, observando que las mediciones fotogramétricas pueden equipararse
con las obtenidas con escáner laser, ya que los valores de error promedio como así
también su desviación con respecto a la media resultaron similares. Así mismo, con la
comparación a partir del modelo de mallas se puede interpretar que existe una muy

14

<!-- p. 15 -->

buena correlación espacial entre ambos modelos analizados. Se debe resaltar que si
bien el valor del instrumental necesario para efectuar un levantamiento con escáner
laser es muy elevado, mientras, que la técnica fotogramétrica tiene la ventaja que se
utilizan instrumentales de un costo significativamente menor, se obtienen resultados
igualmente precisos y de calidad, con la particularidad que la nube de puntos se
encuentra texturizada a partir de las fotografías tomadas para reconstruir el objeto,
pero con la desventaja de un mayor tiempo de adquisición y procesamiento.
Por último, es significativo mencionar que la importancia de este trabajo radica en el
análisis e investigación científico-técnica con el que se ha estudiado cada método
de levantamiento, pero es de destacar que esta metodología puede ser de
aplicación en las estrategias de recuperación, conservación, restauración y
promoción del territorio, como así también la búsqueda de alternativas económicas
para llevar a cabo dichas tareas.

RECONOCIMIENTOS

Los autores desean agradecer al Agrim. Marcelo Sarmiento por brindarnos su
levantamiento con escáner laser; como así también a los profesores de la cátedra de
Trabajo Final que acompañaron en este trabajo y autorizaron el uso del instrumental
del Departamento de Agrimensura, al Departamento de Representación Gráfica, y al
Centro de Vinculación de Estudios Territoriales de la Facultad de Ciencias Exactas,
Físicas y Naturales de Córdoba, Argentina.

REFERENCIAS

ALMAGRO GORBEA A.; Levantamiento Arquitectónico. UG, Granada, 2004, ISBN
\9788433831903.
ARRANZ JUSTEL J.J.; “Diseño, optimización y análisis de sistemas basados en
técnicas láser, para el modelado geométrico, registro y documentación, aplicados a
entidades de interés patrimonial”. Directores: Dr. S. Ormeño Villajos, Dr. J.M. Vicent
García. Tesis de Doctorado, UPM, Madrid, 2013.
AMOEDO M.C., RUEDA SUSPICHIATTI B.E., SALAZAR S.; “Proyecto de
restauración a partir del relevantamiento fotogramétrico de la iglesia de la compañía
de Jesús, Córdoba”. En V EGraFIA, CUES (editorial) y FLASHBAY (edición digital),
Rosario, 2014, ISBN 9788897821809.
BARBA S.; Tecniche digitali per il rilievo di contatto. CUES, Salerno, 2008. ISBN
\9788895028231.
BUILL F., NÚÑEZ M.A., RODRÍGUEZ J.J.; Fotogrametría arquitectónica, UPC,
Barcelona, 2008. ISBN 9788498803419.
MARTÍNEZ-ESPEJO ZARAGOZA I.; “Precisiones sobre el levantamiento 3D integrado
con herramientas avanzadas, aplicado al conocimiento y la conservación del patrimonio
arquitectónico”. Director: F. Juan Vidal. Tesis de Doctorado, UPV, Valencia, 2014.

15
