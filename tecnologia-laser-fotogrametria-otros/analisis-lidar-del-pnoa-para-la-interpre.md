---
type: libro
title: "Analisis_LiDAR_del_PNOA_para_la_interpre"
author: ""
categoria: "Tecnología láser, fotogrametría, otros"
paginas: 5
extraccion: "texto"
fuente: "local:E:/DISCIPLINAS, TEXTOS Y MAPAS/Biblioteca digital/Tecnología láser, fotogrametría, otros/Analisis_LiDAR_del_PNOA_para_la_interpre.pdf"
convertido: 2026-10-13
---

# Analisis_LiDAR_del_PNOA_para_la_interpre

> Texto extraído de `Tecnología láser, fotogrametría, otros/Analisis_LiDAR_del_PNOA_para_la_interpre.pdf` (5 páginas, texto). El PDF original está en el disco E: (DISCIPLINAS, TEXTOS Y MAPAS\Biblioteca digital); `<!-- p. N -->` marca el inicio de cada página.

<!-- p. 1 -->

Congresos UEx. Actas de Congresos. ISSN: 3101-7177,
vol. 2, 2026, XXI Congreso de la Asociación Española de Teledetección
DOI: https://doi.org/10.17398/3101-7177.2.146

Sicre-González, P.; Pecci, A.; Niveau-de-Villedary y Mariñas, A. Análisis LiDAR del PNOA para la interpretación
topográfica del paisaje funerario en el yacimiento del “Castillo de Doña Blanca” (Cádiz, España)

Análisis LiDAR del PNOA para la interpretación
topográfica del paisaje funerario en el yacimiento
del “Castillo de Doña Blanca” (Cádiz, España)

Sicre-González, Pablo ¹ Pecci, Antonio ¹ Niveau-de-Villedary y Mariñas, Ana María ¹

¹ Universidad de Cádiz (España), Departamento de Historia, Geografía y Filosofía

ORCID: Sicre-González 0000-0002-6938-0174 Pecci 0009-0001-9771-3634 Niveau-de-Villedary y Mariñas 0000-0002-
8888-1169

Correspondencia: pablo.sicre@uca.es antonio.pecci@uca.es anamaria.niveau@uca.es

RESUMEN

El presente estudio analiza el potencial del LiDAR del PNOA para la interpretación topográfica del paisaje funerario
asociado al yacimiento fenicio-púnico del Castillo de Doña Blanca (Cádiz), con especial atención a la Necrópolis de las
Cumbres. El procesamiento de datos LiDAR ha permitido generar un Modelo Digital del Terreno de alta resolución,
analizado mediante técnicas de realce del relieve en SIG. Los resultados han posibilitado identificar anomalías
microtopográficas compatibles con estructuras tumulares y redefinir la extensión y organización espacial de la
necrópolis, documentando un número significativamente mayor de posibles túmulos respecto a trabajo previos. El
estudio pone de manifiesto el valor del LiDAR como herramienta no invasiva para la investigación y gestión del
patrimonio arqueológico, estableciendo una base metodológica para futuras prospecciones y análisis geoarqueológicos.

Palabras clave: LiDAR; paisaje funerario; necrópolis tumular; teledetección arqueológica; Castillo de Doña Blanca.

Fecha de recepción: 9 febrero 2026 · Fecha de aceptación: 9 febrero 2026

© 2026 XXI Congreso de la Asociación Española de Teledetección. Página 1

<!-- p. 2 -->

Análisis LiDAR del PNOA para la interpretación topográfica
del paisaje funerario en el yacimiento del “Castillo de Doña
Blanca” (Cádiz, España)

Sicre-González, Pablo (1), Pecci, Antonio (1), Niveau-de-Villedary y Mariñas, Ana María (1)

(1) Universidad de Cádiz (España), Departamento de Historia, Geografía y Filosofía.
0000-0002-6938-0174, pablo.sicre@uca.es.
0009-0001-9771-3634, antonio.pecci@uca.es.
0000-0002-8888-1169, anamaria.niveau@uca.es.

Resumen: El presente estudio analiza el potencial del LiDAR del PNOA para la interpretación
topográfica del paisaje funerario asociado al yacimiento fenicio-púnico del Castillo de Doña
Blanca (Cádiz), con especial atención a la Necrópolis de las Cumbres. El procesamiento de datos
LiDAR ha permitido generar un Modelo Digital del Terreno de alta resolución, analizado mediante
técnicas de realce del relieve en SIG. Los resultados han posibilitado identificar anomalías
microtopográficas compatibles con estructuras tumulares y redefinir la extensión y organización
espacial de la necrópolis, documentando un número significativamente mayor de posibles
túmulos respecto a trabajo previos. El estudio pone de manifiesto el valor del LiDAR como
herramienta no invasiva para la investigación y gestión del patrimonio arqueológico,
estableciendo una base metodológica para futuras prospecciones y análisis geoarqueológicos.

Palabras clave: LiDAR; paisaje funerario; necrópolis tumular; teledetección arqueológica; Castillo de Doña
Blanca.

LiDAR data from the PNOA for the topographic interpretation of the funerary
landscape at the Castillo de Doña Blanca (Cádiz)

Abstract: This study analyses the potential of the PNOA’s LiDAR data for the topographical
interpretation of the funerary landscape associated with the Phoenician-Punic site of Castillo de
Doña Blanca (Cádiz), with particular focus on the Necropolis of Las Cumbres. The processing of
LiDAR data has enabled the generation of a high-resolution Digital Elevation Model, analysed
using GIS-based relief enhancement techniques. The results have made it possible to identify
microtopographical anomalies consistent with burial mounds and to redefine the extent and
spatial organisation of the necropolis, documenting a significantly higher number of potential
mounds compared to previous studies. The study highlights the value of LiDAR as a non-invasive
tool for the research and management of archaeological heritage, establishing a methodological
basis for future surveys and geoarchaeological analyses.

Keywords: LiDAR; funerary landscape; tumulus necropolis; archaeological remote sensing; Castillo de Doña
Blanca.

\1. INTRODUCCIÓN Mientras que el asentamiento principal del CDB ha sido
objeto de numerosas campañas arqueológicas entre
El Castillo de Doña Blanca (CDB), localizado en el 1979 y 2005, retomadas desde 2024 por un equipo de la
término municipal del El Puerto de Santa María (Cádiz, Universidad de Cádiz, el grado de intervención en las
España) (Fig. 1A), constituye uno de los asentamientos restantes zonas que integran el Bien de Interés Cultural
fenicio-púnicos más relevantes del Mediterráneo (Decreto 82/2001) es variable. El poblado de la SSC ha
occidental, con ocupación desde finales del siglo IX sido objeto de algunas intervenciones, aunque menos
hasta el III a.n.e. Su conjunto patrimonial incluye el tell sistemáticas que las del CDB. La necrópolis NC ha sido
principal, donde se localiza el asentamiento, además de parcialmente excavada (campañas de 1984-1985, con
otras áreas arqueológicas, como la necrópolis tumular dos estructuras funerarias), mientras que la finca LM solo
de “Las Cumbres” (NC) (Fig. 1B) o el asentamiento es conocida hasta el momento por prospecciones
situado en la cima de la Sierra de San Cristóbal (SSC) geofísicas sin intervenciones arqueológicas directas
(Fig. 1C) (Ruiz Mata, 1993; Ruiz Mata y Pérez, 1995). (Ruiz Gil et al., 2023).
Además, a estas zonas se le ha de añadir una nueva área
La necrópolis (NC), parcialmente afectada porde gran potencial arqueológico documentada gracias a
infraestructuras modernas, solo ha sido intervenidatécnicas geofísicas no invasivas (Ruiz Gil et al., 2023) en
arqueológicamente durante las campañas de 1984-la finca “La Martela” (LM) (Fig. 1D).

Página 2

<!-- p. 3 -->

1985, excavándose dos estructuras funerarias. Por su El espacio funerario NC se emplaza al norte del CDB, en
parte, en la finca LM se ha propuesto la hipótesis de la la falda meridional de la Sierra de San Cristóbal,
existencia de una amplia zona portuaria a partir de datos ocupando un espacio amplio caracterizado por suaves
de teledetección (Ruiz Gil et al., 2023). elevaciones y pequeñas lomas de escasa altura. Desde
el punto de vista geomorfológico, el terreno combina
Aprovechando la disponibilidad actual de metodologías zonas ligeramente onduladas con cerros aislados que
no invasivas de fácil acceso, como el análisis LiDAR a dominan visualmente el entorno inmediato, configurando
partir de datos del PNOA, se ha aplicado este enfoque al un paisaje propicio para la implantación de estructuras
estudio de la Necrópolis de las Cumbres con el objetivo tumulares visibles en el territorio. La disposición de los
de mejorar y facilitar la documentación del territorio, más túmulos sobre cimas y laderas sugiere una selección
allá de las publicaciones monográficas existentes sobre consciente de puntos elevados con potencial simbólico
el Túmulo 1 (Ruiz Mata, 1985, 1991; Ruiz Mata y Pérez, y visual, favoreciendo tanto la monumentalidad como la
1989; Córdoba Alonso, 1996; Córdoba Alonso, Ruiz relación visual con el asentamiento protohistórico del
Mata, 2000; Pérez, 2025), resulta necesario recurrir a CDB y con los corredores naturales de circulación. La
metodologías no invasivas capaces de documentar el posible presencia de canales o surcos excavados en la
territorio desde una perspectiva integral. En este roca evidencia además una dinámica hídrica
contexto, el empleo de datos LiDAR procedentes del condicionada por la pendiente de la sierra, lo que habría
Plan Nacional de Ortofotografía Aérea (PNOA) permite influido en la conservación diferencial de las estructuras
reconocer anomalías microtopográficas, identificar y en la organización espacial del conjunto funerario.
posibles estructuras tumulares apenas visibles en
superficie y contrastar las evidencias previamente 2.2. Estado de la cuestión
sugeridas por la arqueología aérea y el reconocimiento Las referencias textuales sobre la necrópolis del CDB se
topográfico in situ. Este enfoque amplía el conocimiento centran principalmente en la morfología y el registro
sobre la organización espacial del paisaje funerario material del denominado Túmulo 1. La información
protohistórico y evidencia el valor de la reutilización de procede de las campañas de 1984-1985 (Ruiz Mata,
recursos abiertos para investigar y reevaluar yacimientos 1985, 1991; Ruiz Mata y Pérez, 1989; Córdoba Alonso,
previamente estudiados. 1996; Pérez, 2025), en las que se excavaron dos
Los resultados aquí presentados constituyen una estructuras: el Túmulo 1 y el Hipogeo 1 (algunas
contribución preliminar dentro de los proyectos del GI1, referencias en Ruiz Mata, 2022, p. 328); se menciona
cuyos aspectos metodológicos, interpretativos y además la identificación superficial de un Túmulo 2 y la
contextuales serán abordados con mayor detalle en posible existencia de construcciones asociadas que
futuras publicaciones. configurarían complejos tumulares (Ruiz Mata, 2022, p.
329). Las prospecciones visuales sugieren la presencia
de numerosos túmulos actualmente ocultos por la
vegetación y una organización espacial en dos sectores:
uno occidental, con mayor concentración de estructuras,
y otro oriental, próximo a la Sierra de San Cristóbal, con
evidencias de menor entidad (Ruiz Mata, 2022, pp. 327-
328). Las sepulturas se disponen sobre pequeñas
elevaciones, ocupando cimas y laderas, en un paisaje
marcado por suaves relieves y posibles cauces
excavados en la roca que canalizarían el agua desde
cotas superiores (Ruiz Mata, 1991, p. 207).
Morfológicamente, se documentan túmulos de sección
semicircular, en ocasiones interpretables como
troncocónicos por procesos erosivos comparables
tipológicamente a los túmulos A, B y E de Setefilla (Lora
del Río, Sevilla) (Aubet Semmler, 1975), que constituyen
Figura 1. Localización del área arqueológica del Castillo de uno de los paralelos más cercanos para el análisis de
Doña Blanca (El Puerto de Santa María, Cádiz) A) Castillo de este tipo de estructuras.
Doña Blanca, B) Necrópolis “Las Cumbres”, C) Poblado de la
Sierra de San Cristóbal, D) Finca “La Martela”. Elaboración El Túmulo 1, único ejemplo protohistórico excavado,
propia. presenta unos 22 m de diámetro y una altura media de
1,5 m, con al menos 62 enterramientos de incineración
datados en el siglo VIII a.n.e. (Ruiz Mata, 1985, 1991; Ruiz
\2. CASO DE ESTUDIO Mata y Pérez, 1989; Córdoba Alonso, 1996; Pérez, 2025).
2.1. Características topográficas de la NC El Hipogeo 1, de planta circular (3 m de diámetro y 1,8
m de altura), adscrito a la Edad del Cobre, albergaba
restos de entre 24 y 25 individuos y evidencias de

1 eXperimental Unmanned Aerial System with LiDAR, financiado Grupo de Investigación del PAIDI “PHOENIX MEDITERRANEA de la Comisión Europea (MSCA PF, Proyecto 101155484);
(HUM-509); Proyecto PDC2025-164863-I00 financiado por «Mapping Gadir» (proyecto PDC2025-164863-I00) financiado
MICIU/AEI /10.13039/501100011033; PHOENIX-UASL. de la Agencia Estatal de Investigación (AEI).
Research on PHOENIcian-Punic sites in Andalusia with

Página 3

<!-- p. 4 -->

posibles prácticas rituales (Ruiz Mata y Pérez, 1995, p. Analysis Tool) evalúa la visibilidad acumulada desde el
114). El Túmulo 2 y las estructuras secundarias carecen terreno (Fig. 3).
aún de caracterización morfológica y dimensional 3.2. Análisis SIG
precisa, ya que no se han excavado.
Una vez procesada la información LiDAR, se procedió al
\3. MATERIAL Y MÉTODOS análisis detallado de las anomalías detectadas en el SIG
(QGIS). En primer lugar, se diferenciaron aquellas de
3.1. Análisis LiDAR origen contemporáneo mediante el uso de ortofotos
Los datos LiDAR empleados en el caso de estudio del históricas del PNOA, prestando especial atención a la
CDB proceden de los archivos digitales disponibles en el posible interferencia de la vegetación de baja densidad
Instituto Geográfico Nacional, correspondientes al en la lectura de las distintas visualizaciones. Tras depurar
programa “LiDAR de 3ª Cobertura (2022-2025)” con una los datos y minimizar posibles errores derivados de
densidad aproximada de 5 puntos/m². Tras su interpretaciones imprecisas, fue posible identificar con
clasificación y procesamiento, dichos datos permitieron claridad diversas anomalías de carácter convexo, que
generar un Modelo Digital del Terreno (MDT) ráster de fueron georreferenciadas mediante puntos en el entorno
alta resolución y calidad, base fundamental para los SIG.
análisis posteriores.
\4. RESULTADOS

El análisis de los datos LiDAR permitió identificar con
claridad diversas anomalías microtopográficas en el
ámbito de la NC (Fig. 4), distinguiéndose tanto
alteraciones negativas asociadas a colapsos de antiguas
canteras de extracción de caliza como variaciones
superficiales vinculadas a dinámicas hídricas.
Paralelamente, la georreferenciación de las estructuras
previamente documentadas posibilitó integrar por
primera vez en un entorno SIG la localización precisa de
los túmulos 1 y 2 y a otros elementos tumulares
conocidos. A partir del MDT se obtuvieron datos
altimétricos relativos que facilitaron la caracterización
morfológica de las estructuras y la detección de nuevas
anomalías convexas compatibles con túmulos. Como
Figura 2. Visualización Multi-Hillshading RGB. Obra derivada resultado preliminar, se identificaron 35 posibles nuevas
de LiDAR-PNOA-cob3 2022-2025 CC-BY 4.0 scne.es estructuras tumulares de tamaño medio y grande,
elevando el número total estimado hasta 59. La totalidad
de las evidencias documentadas, incluidas las de
reducidas dimensiones no señaladas en este estudio,
deberán ser verificadas mediante trabajo de campo.

Figura 3. Visualización VAT. Obra derivada de LiDAR-PNOA-
cob3 2022-2025 CC-BY 4.0 scne.es

El tratamiento y análisis de la información se llevó a cabo Figura 4. Túmulos ubicados previamente y anomalías
mediante QGIS, FugroViewer y LAStools. Las detectadas mediante LiDAR en la NC. Obra derivada de
visualizaciones se generaron con Relief Visualization LiDAR-PNOA-cob3 2022-2025 CC-BY 4.0 scne.es
Tool (RVT), aplicando un conjunto de técnicas de realce
del relieve seleccionadas por su eficacia en la detección
de anomalías microtopográficas en contextos 5. DISCUSIÓN
arqueológicos (Kokalj et al., 2019; Štular et al., 2021). Los resultados del análisis LiDAR permiten plantear la
Entre ellas, Multi-Hillshading RGB (Fig. 2) combina hipótesis de que la extensión y complejidad espacial de
iluminaciones desde múltiples direcciones para reducir la necrópolis podrían ser mayores de lo considerado en
la dependencia de la orientación de la luz y VAT (Visibility estudios previos. Las investigaciones llevadas a cabo en

Página 4

<!-- p. 5 -->

las últimas décadas del siglo XX, basadas en Archaeological Topography, II(February 2016), 100–
intervenciones puntuales y reconocimiento superficial 114. https://doi.org/10.2307/j.ctvh1dqdz.13
con visibilidad limitada, no pudieron beneficiarse de las Pérez, C. (2025). El Túmulo 1 de la necrópolis de Las
herramientas de teledetección actuales. La identificación Cumbres en el Puerto de Santa María (Cádiz).
de nuevas anomalías compatibles con túmulos, Análisis arqueológico, histórico-cultural, ritual y
especialmente en el sector occidental, apunta a la simbólico. Tesis doctoral inédita. Universidad
posibilidad de un área funeraria más amplia y organizada Autónoma de Madrid.
de manera más compleja, con posibles estructuras
Ruiz Gil, J. A., Lagóstena Barrios, L. G., Pérez Marrero,principales acompañadas por túmulos secundarios.
J., Trapero Fernández, P., Catalán González, J.,
No obstante, factores de ambigüedad como cavidades Rondán-Sevilla, I. M., y Ruiz Barroso, M. (2023). GPR
subterráneas, procesos erosivos y variaciones asociadas Survey in the Punic Harbour of La Martela (El Puerto
a cauces o escorrentías, ya señalados en estudios de Santa Maria, Spain) and the methodology used for
anteriores (Ruiz Mata, 2022, p. 325), introducen the processing and archaeological visualisation of the
incertidumbre en la interpretación. Por ello, estas data. En I. P. Haynes, T. Ravasi, S. Kay, S. Piro, y P.
hipótesis requieren contrastación directa mediante Liverani (Eds.), Non-Intrusive Methodologies for
prospecciones sistemáticas y estudios Large Area Urban Research (pp. 99–105).
geoarqueológicos que permitan validar la naturaleza Archaeopress.
antrópica de las anomalías detectadas. https://doi.org/10.2307/jj.15136039.20
Ruiz Mata, D. (1985). Excavación del Túmulo 1 de la
\6. CONCLUSIONES necrópolis de Las Cumbres (Puerto de Santa María,
Cádiz). En Anuario Arqueológico de Andalucía, II
El análisis LiDAR ha demostrado ser una herramienta de
Actividades Sistemáticas (pp. 158–160).
gran utilidad para el estudio de paisajes funerarios
protohistóricos poco intervenidos. La generación de un Ruiz Mata, D. (1991). El Túmulo 1 de la necrópolis de Las
MDT de alta resolución a partir de datos PNOA ha Cumbres. Treballs Del Museu Arqueologic D´Eivissa
permitido aproximarse a la microtopografía del área con e Formentera, 24, 207–220.
un nivel de detalle difícil de alcanzar mediante métodos Ruiz Mata, D. (1993). La colonización fenicia en la Bahía
convencionales, si bien estos también habrían podido de Cádiz a través del Castillo de Doña Blanca. Puerto
aportar información relevante, aunque con mayor de Santa María. En J. M. Campos Carrascto y F.
complejidad y coste. Nocete Calvo (Eds.), Investigaciones arqueológicas
en Andalucía (1985-1992) Proyectos. VI Jornadas de
Los resultados obtenidos sugieren, como hipótesis a
Arqueología andaluza. (pp. 489–496).
contrastar, que la necrópolis de Las Cumbres podría
presentar una extensión, densidad y complejidad Ruiz Mata, D. (2022). La ciudad fenicia del Castillo de
mayores de lo que se conocía hasta ahora, con cerca de Doña Blanca (El Puerto de Santa María, Cádiz).
medio centenar de anomalías convexas compatibles con Historia y Arqueología, investigaciones (1979-2003).
posibles túmulos. Esta organización apuntaría, en caso Cuadernos de Arqueología Mediterránea 28.
de confirmarse su naturaleza antrópica, a un paisaje Ruiz Mata, D., y Pérez, C. J. (1989). El Túmulo 1 de la
funerario articulado y jerarquizado, vinculado a la necrópolis de “Las Cumbres” (Puerto de Santa
topografía y la visibilidad. María, Cádiz). En M. E. Aubet Semmler (Ed.),
Tartessos. Arqueología protohistórica del bajo
Metodológicamente, la combinación de visualizaciones
Guadalquivir. (pp. 287–295). Editorial AUSA.
LiDAR con SIG ha proporcionado una base espacial
coherente para la detección y reevaluación de Ruiz Mata, D., y Pérez, C. J. (1995). El poblado fenicio del
evidencias arqueológicas. En conjunto, el estudio Castillo de Doña Blanca (El Puerto de Santa María,
confirma el valor del LiDAR de acceso abierto para la Cádiz). Ayuntamiento de El Puerto de Santa María.
investigación y gestión patrimonial, estableciendo una Štular, B., Lozić, E., y Eichert, S. (2021). Airborne LiDARbase sólida para futuras fases de validación empírica e Derived Digital Elevation Model for Archaeology.
integración territorial del conjunto protohistórico del Remote Sensing, 13(9).
Castillo de Doña Blanca. https://doi.org/10.3390/rs13091855

\7. REFERENCIAS
Aubet Semmler, M. E. (1975). La necrópolis de Setefilla
en Lora del Río, Sevilla. Departamento de Prehistoria
y Arqueología. Universidad de Barcelona.
Córdoba Alonso, I. (1996). La Cerámica Pintada con
Motivos Radiales del Túmulo 1 de la Necrópolis de
las Cumbres (El Puerto de Santa María, Cádiz). En
Actas do II Encontro de Arqueología do Sudoeste
Peninsular (pp. 131–139). Universidade do Algarve.
Kokalj, Ž., Zakšek, K., & Oštir, K. (2019). Visualizations of
lidar derived relief models. Interpreting

Página 5
