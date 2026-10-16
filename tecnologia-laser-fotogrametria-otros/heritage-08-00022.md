---
type: libro
title: "Evaluation of 3D Models of Archaeological Remains of Almenara Castle Using Two UAVs with Different Navigation Systems"
author: "Juan López-Herrera, Serafín López-Cuervo, Enrique Pérez-Martín, Miguel Ángel Maté-González, Consuelo Vara Izquierdo, José Martínez Peñarroya and Tomás R. Herrero-Tejedor"
categoria: "Tecnología láser, fotogrametría, otros"
paginas: 20
extraccion: "texto"
fuente: "local:E:/Biblioteca digital/Tecnología láser, fotogrametría, otros/heritage-08-00022.pdf"
convertido: 2026-10-13
---

# Evaluation of 3D Models of Archaeological Remains of Almenara Castle Using Two UAVs with Different Navigation Systems

> Texto extraído de `Tecnología láser, fotogrametría, otros/heritage-08-00022.pdf` (20 páginas, texto). El PDF original está en el disco E: (Biblioteca digital); `<!-- p. N -->` marca el inicio de cada página.

<!-- p. 1 -->

Article
Evaluation of 3D Models of Archaeological Remains of Almenara
Castle Using Two UAVs with Different Navigation Systems

Juan López-Herrera 1,* , Serafín López-Cuervo 2 , Enrique Pérez-Martín 1 , Miguel Ángel Maté-González 3 ,
Consuelo Vara Izquierdo 4, José Martínez Peñarroya 4 and Tomás R. Herrero-Tejedor 1

1 Departamento de Ingeniería Agroforestal, Escuela Técnica Superior de Ingeniería Agronómica, Alimentaria y
de Biosistemas, Universidad Politécnica de Madrid, 28040 Madrid, Spain; enrique.perez@upm.es (E.P.-M.);
tomas.herrero.tejedor@upm.es (T.R.H.-T.)
2 Departamento de Ingeniería Cartográfica, Geodésica y Fotogrametría, Escuela Técnica Superior de Ingenieros
en Topografía, Geodesia y Cartografía, Universidad Politécnica de Madrid, 28031 Madrid, Spain;
s.lopezc@upm.es
3 Departamento de Ingeniería Cartográfica y del Terreno, Escuela Politécnica Superior de Ávila, Universidad de
Salamanca, 05003 Ávila, Spain; mategonzalez@usal.es
4 Castrvm Patrimonio Histórico SL, 28008 Madrid, Spain; consuvaiz@gmail.com (C.V.I.);
jmp.castrum@gmail.com (J.M.P.)
\* Correspondence: juan.lz.herrera@upm.es

Abstract: Improvements in the navigation systems incorporated into unmanned aerial
vehicles (UAVs) and new sensors are improving the quality of 3D mapping results. In this
study, two flights were compared over the archaeological remains of the castle of Almenara,
situated in Cuenca, Spain. We performed one with a DJI Phantom 4 (DJI Innovations Co.,
Ltd., Shenzhen, China) and the other with a Matrice 300 RTK (DJI Innovations Co., Ltd.,
Shenzhen, China) and the new Zenmuse P1 camera (45 mp, RGB sensor). With the help of
the new software incorporated into the Zenmuse P1 camera gimbal, we could significantly
reduce the flight time. We analysed the data obtained with these two UAVs and the built-in
RGB sensors, comparing the flight time, the point cloud, and its resolution and obtaining a
three-dimensional reconstruction of the castle. We describe the work and the flights carried
Academic Editors: George Alexis
out, depending on the type of UAV and its RTK positioning system. The improvementIoannakis and Anestis Koutsoudis
in the positioning system provides improvements in flight accuracy and data acquisition.
Received: 21 November 2024
We compared the results obtained in similar studies, and thanks to the advances in UAVsRevised: 30 December 2024
Accepted: 8 January 2025 and their sensors with better resolution, we managed to reduce the data collection time
Published: 10 January 2025 and obtained 3D models with the same results as those from other types of sensors. The
Citation: López-Herrera, J.; accuracies obtained with the RTK and the P1 camera are very high. The volumes calculated
López-Cuervo, S.; Pérez-Martín, E.; for a future archaeological excavation are precise, and the 3D models obtained by these
Maté-González, M.Á.; Izquierdo, C.V.; means are excellent for the preservation of the cultural asset. These models can have various
Peñarroya, J.M.; Herrero-Tejedor, T.R. uses, such as the preservation of an asset of cultural interest, or even its dissemination
Evaluation of 3D Models of
and analysis in various studies. We propose to use this technology for similar studies of
Archaeological Remains of Almenara
archaeological documentation and the three-dimensional reconstruction and visualisationCastle Using Two UAVs with
Different Navigation Systems. of cultural heritage in virtual visits on the web.

Heritage 2025, 8, 22. https://doi.org/
10.3390/heritage8010022 Keywords: virtual archaeology; 3D modelling; UAV; photogrammetry; cultural heritage

Copyright: © 2025 by the authors.

Licensee MDPI, Basel, Switzerland.

This article is an open access article
distributed under the terms and 1. Introduction
conditions of the Creative Commons The application of new data capture sensors in photogrammetry and the use of the 3D
Attribution (CC BY) license
model allow an approach to the knowledge, preservation, and spread of cultural heritage [1].
(https://creativecommons.org/
licenses/by/4.0/). The 3D model enables the recreation of an object within its present environment or a

Heritage 2025, 8, 22 https://doi.org/10.3390/heritage8010022

<!-- p. 2 -->

Heritage 2025, 8, 22 2 of 20

simulated context, providing a visually engaging and accessible means of disseminating
historical research [2]. The reconstruction process of virtual models is used as a source to
improve the understanding of the represented object [3].
The use of UAVs in archaeology has expanded significantly in the last twenty years.
The improvements in terms of reliability, size, and manageability of these aircraft have
been largely complemented by high resolution. According to Fiz [4], the functionalities and
improvements that photogrammetry programmes have undergone in recent years represent
a qualitative leap in possibilities, not only for geometric documentation and the presentation
of archaeological data but also for the incorporation of non-intrusive high-resolution
analysis. Progress in research shows that archaeological site surveys using UAVs in non-
invasive surveys contribute to the development of accurate geometric documentation [4–6],
the generation of three-dimensional models from the use of Georadar [7,8], or studies using
UAVs and complementing them with the use of terrestrial laser scanning (TLS) [9–11],
proposing methodologies to generate 2D and 3D models that facilitate the analysis and
evaluation of cultural heritage.
The study has been carried out in the Almenara Castle because it is an element of
heritage of small size in its dimensions, albeit with a great vertical development that has
three distinct areas in height. Its use is therefore justified in the determination of the scale in
the self-calibration of sensors using UAVs with the double processing and the comparative
study of both methodologies that is explained in the development of this article.
The castle of Almenara is located in the municipality of Puebla de Almenara in the
province of Cuenca (Figure 1).

Figure 1. The castle of Almenara (a), located in Cuenca (Spain) (b) in the municipality of Puebla de Al-
menara (2◦50′31′′ W, 39◦47′28′′ N) (c). View of the municipality of Puebla de Almenara and the castle
of Almenara, Cuenca (Spain), in the foothills of Sierra Jarameña (d). WGS84 spatial reference system.

This unique fortress is chronologically framed in the Late Middle Ages. We still do
not know exactly when the construction of the castle started. Some authors have dated
its origin to the period of the Almoravids and Almohads, who arrived from the Maghreb
and occupied these lands in the 12th century. Others have dated it to the measures of the
Order of Santiago to bring about peace, which took place throughout the 13th century.

<!-- p. 3 -->

Heritage 2025, 8, 22 3 of 20

However, the first document in which the castle is mentioned is the town charter granted by
D. Juan Manuel in 1322, which is the origin of the foundation of the town located at the
foot of the mountain.
The castle remained garrisoned and probably inhabited until the end of the
16th century. In 1982, a restoration project was sponsored by the Ministry of Education and
Culture of the Spanish Government and carried out in 1985. The actions were limited to
removing debris from inside the enclosures, grouting with mortar on the external side of
the walls of the first and second enclosures, replacing plundered masonry pieces (especially
in the barrier artillery), and reconstructing some sections of the fortification. This project
included an archaeological excavation campaign where five archaeological surveys were
carried out, in which ceramic material from late mediaeval chronology was recovered, and
many fragments of decorative reliefs were made in plaster. These are preserved in the
Museum of Cuenca.
In line with the preservation actions, a consolidation and safety project was carried out
between 2020 and 2021 in order to provide the castle with the minimum elements required
to guarantee its visits. A new study process was undertaken with the financing of the
Provincial Council of Cuenca and the owners of the building. It started with the execution
of a 3D photogrammetric model that made it possible to obtain complete and updated
building planimetry results, and it continued with the drafting of the corresponding archi-
tectural consolidation projects and archaeological excavation. However, this process lacked
the aerial vision that was critical for this modelling. According to Benavides [12], new
three-dimensional (3D) aerial capture and display systems are changing the paradigm in
architectural heritage documentation, being much more efficient and accurate. According
to Potje et al. [13], the cost of autonomous aerial platforms equipped with cameras is
steadily decreasing. This high-quality documentation is fundamental for the archaeological
research of the building sequence of fortresses, making dissemination research and the
corresponding results considerably easier. According to Barreau et al. [14], the 3D digitisa-
tion of existing structures allows analytical approaches to increase the democratisation of
projects, in particular, those involving the restoration of sites.
At present and after the consolidation and cleaning of several rooms of the castle,
we know the inner layout of the fortress a little better (Figure 2). The building is placed
between a sharp slope to the west and north and a gentler slope to the east and south.
The first enclosure, the innermost one, is articulated around a large cistern dug into the
rock, which must also have served as a quarry for the first walls of the castle. Surrounding
this cistern, there is a room with four areas, where the vault only remains in three of them.
Above this room and the cistern are the remains of a central courtyard, which must have
been colonnaded at the last moment of the castle’s habitation, according to a base that has
survived in situ. This courtyard is surrounded by the remains of four rooms, the most
interesting being the west cliff, with the presence of a tower with a round floor plan larger
than the rest of the castle’s towers. It is in this place that the fragments of plaster reliefs that
were part of the decoration of a main room of the castle were found.
The second enclosure is just a wall to the gate of the enclosure described above,
which is located to the south and, as it occurs in other walls of the castle, has been
greatly transformed with the opening of holes and alterations possibly carried out in the
16th century for its adaptation into a residential palace, once it lost its military status at the
end of the 15th century. Between this second enclosure and the third one, there is an empty
space about a thousand metres long, which defines the interior of the castle along with the
artillery barrier that was built at the end of the aforementioned 15th century.
This is a unique fortified architectural complex that has suffered the vicissitudes of
seven centuries, inhabited for just three and partially dismantled in the 16th century to

<!-- p. 4 -->

Heritage 2025, 8, 22 4 of 20

obtain construction material. At present, its progressive deterioration has been slowed
down and stabilised, and an encouraging plan is being developed within the framework
of monumental buildings that can be visited to gain knowledge of the historical period
known as the Late Middle Ages. Physical conservation is no longer enough for a resource
as valuable as cultural heritage; it needs to be complemented with comprehensive digital
preservation in all its forms, being essential and necessary for its proper safeguard.

Figure 2. The location of the castle treated in this study with its lights and shadows. Own source
image from drone flight using Phantom 4. Spatial reference system WGS_1984_UTM_Zone_30N.

To protect this monument, we have opted in this project for the use of Geospatial
Information Technologies (GITs) to provide data and digital documentation. The 3D model
is the result of the use of GIT for the geospatial analysis of the heritage, which, together with
other techniques such as multiresolution data processing, data management, conservation,
and visualisation and presentation of the results, allows the sharing and dissemination
of the results of this research to protect the cultural heritage and promote its knowledge.
Three-dimensional high-definition digital models have achieved remarkable success in the
conservation, management, and education of cultural property [15–17].
The novelty of our study lies in the evaluation of 3D models based on the use of
different airborne sensors in UAVs for the analysis of hidden areas or areas with poor
visibility due to the presence of high walls in the archaeological remains.
Two UAVs were used for this work: a Phantom 4 with a 12 Mpx camera and
2.3 mm focal length, and a Matrice 300 RTK where a 45 Mpx Zenmuse P1 camera with a
35 mm focal length was installed. The intention of using both UAV solutions was to contrast
the importance of the sensor in both size (which allows greater lighting in the shots) and
resolution, seeking to contrast the possible noise that may occur in the estimation of the
digital models of point clouds on the walls of the castle with the analysis of the options of
greater precision in the positioning of the UAV and in the estimation quality of the dense
point clouds. If this is the case, the lower noise and quality of the point clouds obtained

<!-- p. 5 -->

Heritage 2025, 8, 22 5 of 20

by photogrammetry in a complex object in volume may prevail over precision. The use of
this method is in line with [18], whose authors state that the use of UAVs in archaeology
has made great progress in recent years, with a focus on landscape documentation and 3D
photogrammetry. Similarly, Ref. [19] states that the preliminary analysis of an archaeologi-
cal site requires the acquisition of information through various diagnostic techniques, in
which remote sensing plays an important role, and UAVs with these airborne cameras are a
good method for 3D model surveys.
Therefore, the aim of this study was to propose an innovative approach for the eval-
uation of 3D models applied to archaeological remains, highlighting their potential in
conservation, the generation of high-precision planimetry for excavations, and the creation
of detailed three-dimensional models. A technical analysis of the UAV photogrammetric
flight system, specifically designed to generate high-precision 3D geometric models and
to overcome the visual occlusions caused by the presence of high walls in archaeological
structures, as in the case of the Almenara castle, was carried out. The main contribution
of this research lies in the evaluation and optimisation of the generation of 3D models
using UAV photogrammetric flights in archaeological contexts that present hidden or
difficult-to-access areas due to complex architectural features, such as high walls.

\2. Materials and Methods

The castle has three walled enclosures 11, 20, and 25 m high. These enclosures, and es-
pecially the third one, generated a significant number of shadows in the photographs, some-
times making it difficult to take a large number of photographs to cover the interior walls.
This arrangement represented the greatest difficulty in recreating the three-dimensional
models, not only because of the final height of the last towers with respect to the flight
height of the drone, which was 35 m, but also because of the significant number of shadows
that the walls threw at the photographs taken and the shadows of light (Figure 2). This was
clearly the greatest difficulty in generating the castle’s digital model.

2.1. UAV Data

For the acquisition of the images, two UAVs were used for data collection. The first part
of the task was carried out with a Phantom 4, which has a 12 Mpx camera (4000 × 3000 px)
with a 12 mm focal length. It is a drone that has a standard GNSS with an autonomous
solution. To georeference the flights, four given ground control points were used with a
GEOMAX ZENITH40 RTK system (Geomax AG, Widnau, Switzerland) connected to the
IGN Network of Reference Bases (Figure 2). The precision of the GCPs (Ground Control
Points) was 1.2 cm in planimetry and 2.5 cm in altimetry. As indicated, the flight was made
with autonomous positioning. The second of the UAV systems was a Matrice 300 RTK (DJI
Innovations Co., Ltd., Shenzhen, China). The task was conducted connected to the same
IGN GNSS Network (Instituto Geográfico Nacional, Madrid, Spain), working with a VRS
solution, and the flight was carried out in RTK positioning. This UAV was fitted with a
Zenmuse P1 camera with a 45 Mpx (8192 × 5460 px) resolution and 35 mm focal length. In
addition, 11 ground control points were given over the castle, both on top of the walls and
accessible areas with the GNSS (2.5 cm) and on the facades with ET (5 mm), as shown in
Figure 2. These points are analysed as the ground truth in the results section to validate the
method used to geometrically compare the point clouds obtained with both flights.
The images were captured in October 2021. In both cases, the flight height was 60 m
from the drone’s take-off position. The highest part of the battlements with respect to the
take-off level was 25 m, which means 35 m in height in this zone of flight. For this reason,
in the flights carried out with the Phantom 4, we carried out cross-planning with a nadiral
flight and another with an oblique angle of 35◦provided with a density of 254 points per

<!-- p. 6 -->

Heritage 2025, 8, 22 6 of 20

square metre. This angle allowed the capture of vertical walls as well as the ground, which
would be difficult to capture at a different angle (Figure 3). In the case of the Matrice
300 with P1, we used the DJI Pilot2 application, with which we performed two capture
methodologies. On one hand, a grid of 5 flights—1 nadiral and 4 oblique with inclinations
of 35◦with respect to the vertical—provided a density of 1860 points per square metre.
The last case used the SmartOblique technique, in which the UAV modifies the data
collection sequence by adjusting it to the position of the object and the flight. With this last
pattern, a density of 1760 points per square metre was obtained (Table 1). The height of the
flight was 60 m, and the overlap was 80 × 80.

Figure 3. The location of the castle treated in this study with its lights and shadows. Own source of
flight patterns used: (a) Phantom 4 nadiral flight; (b) Phantom 4 oblique flight; and (c) Matrice 300
RTK–P1 with one nadiral and four independent oblique flights, one for each direction.

Table 1. Flight data (Oblique, O; Nadir, N; Combined, C; SmartOblique, SO).

Flight Time GSD Density
UAV Flight Data Photo
(min) (cm) (Pts/m2)

O 144 12 1.2 167
Phantom 4 N 224 17 1.2 87
C 368 29 1.2 254
Matrice 300 O 832 21 0.87 1860
RTK P1 SO 973 15 0.75/0.87 1760

In the case of SmartOblique, the UAV passes in a single direction of flight, and it is
the camera that rotates and tilts to cover the different shots necessary to comply with the
flight plan. The SmartOblique case is a flight–gimbal–camera methodology that allows
the oblique directions of the camera to be taken both vertically and in the four inclined
directions of the camera (Figure 4), making it so we can cover all the oblique directions
required with a single flight plan, instead of the traditional oblique flight case that required
five independent flights, one for each camera inclination. This methodology improves the
capture of images in cases of high-altitude objects such as the castle object in this study.
This allowed the acquisition times to be reduced from 20.54 to 15.41 min.

<!-- p. 7 -->

Heritage 2025, 8, 22 7 of 20

Figure 4. Flight patterns used: Matrice 300 RTK–P1 SmartOblique flight Omega angles:
blue (135◦SE), red (45◦NW), green (45◦NE), and yellow (135◦SW); the flight combined all with a
Kappa angle.

2.2. Processing Methodology

The software used to adjust the photographs was Agisoft Metashape (https://www.
agisoftmetashape.com/). The computer had an MSI Intel Core i7 8750H @2.2 Ghz with
32 Mb of RAM (https://www.msi.com), PCI3—SSD (https://www.pcisig.com), and an
NVIDIA 2070 6Gb Graphics Card (https://www.nvidia.com).
For the georeferencing of the flight images with the Phantom 4 and for the control
of the camera’s self-calibration, it was necessary to take ground control points (GCPs). In
the case of the Matrice 300 RTK, the metadata obtained in the RTK flight were sufficient to
establish the georeferencing and the camera data that were pre-calibrated by the standard
process proposed by the manufacturer DJI in a previous flight.
The initial accuracies of the coordinates given by the metadata of the images were
1.431 m for the case of the Phantom 4 (standalone GNSS accuracy), 0.045 m for the case of
the Matrice 300 (RTK GNSS accuracy) in Oblique, and 0.025 m for the case of SmartOblique.
This difference in accuracy before processing would result in worse key point detection.
After processing with Agisoft, both aero-triangulation models showed similar accuracies
below 2 pixels error medium quadratic (EMC).
The following UAV flight plan was therefore taken into account:

– Carry out RTK flights so that the flight height is known; the scale of the photographs
improves the inaccuracies of the data calculated in point clouds and thus the subse-
quent production of three-dimensional models.
– Carry out oblique flights, as opposed to traditional nadir flights, to reduce clutter and
errors on irregular surfaces.

<!-- p. 8 -->

Heritage 2025, 8, 22 8 of 20

In this way, the flight with a low-precision and low-resolution UAV, such as the
Phantom 4, achieves a similar resolution in the point cloud to be able to compare the
modelling of both sets of data, as is carried out in Section 2.3. It matches the accuracy
and positioning of the Matrice 300 RTK in the georeferencing of the products (photos, 3D
models, DEM, and Orthophotos), but it may show significant deviations in terms of scale
errors, modelling, etc.
The generation of the dense point clouds, prior to the texture models that were finally
used for the final reproduction of the castle, led to 3.8 million points in the case of the
Phantom 4, 30.8 million points for Oblique, and 38.6 million points for SmartOblique. With
these clouds, the texture models used in the recreation of the models were produced. Finally,
SmartOblique was the one selected for detail and precision and the one used in Section 2.3.
Figure 5 explains the workflow methodology proposed and followed in this research.

Figure 5. Workflow followed in the process of UAV data acquisition (a); processing and 3D model
creation (b); and 3D model evaluation (c).

2.3. Modelling Methodology

The objective in this phase was the creation of geographically referenced 3D pho-
togrammetric models (Figure 6). The resulting dense point cloud from the photogrammet-
ric models was edited to remove trees and vegetation that were outside the study area.
The software used for editing the 3D point cloud was Agisoft Metashape (version 2.2.0).
The post-processed model was exported in .las format to be used and imported into differ-
ent three-dimensional point cloud processing software tools.
In the virtual reconstruction carried out, CloudCompare software was used to manage
the 3D point cloud (http://www.cloudcompare.org/), and SketchUp was used in the
virtual recreation of the 3D model (https://www.sketchup.com/es).
From a basic model of volumes, we detailed the geometry of different sections of the
preserved walls of the castle (Figure 7). We used the imported 3D model to raise and build
the different sections of these walls.

<!-- p. 9 -->

Heritage 2025, 8, 22 9 of 20

Figure 6. Three-dimensional point cloud model of the castle of Almenara. (a) Northeast, (b) northwest,
(c) southeast, and (d) southwest views.

Figure 7. Planimetry of the walled enclosure obtained from the generated orthophotography and the
3D point cloud model of the Almenara castle.

Intermediate spaces were analysed in areas where there were no walls, and following
the most likely paths of the walls and the shapes of the structures, new virtual defences
were raised.
Different shots made for the architectural inventory with a CANON EOS 1300D
(https://global.canon) digital camera (18 Megapixels and image size of 3456 × 1944) were
specifically used for texture recreation. This was carried out only in some narrow and
vertical areas for the UV maps. These maps were made using terrestrial photographs of

<!-- p. 10 -->

Heritage 2025, 8, 22 10 of 20

those wall areas under the best conditions to prepare the textures to apply to the 3D model.
The resulting 3D model was a lighter model with high-quality textures, easier to handle
and move in digital environments (Figure 8).

Figure 8. Three-dimensional model of the point cloud of the Almenara castle with recreation of
virtual walls.

\3. Results

The results obtained have been grouped into flight data, triangulation adjustment,
point clouds, digital models, creation of the digital twin, and estimation of the volumes of
earth for archaeological excavation.

3.1. Data Flight Results

Regarding the flight data, and as shown in Table 1, the GSD of the flights with
the Phantom 4 is 1.2 cm, and those of the Matrice 300 are 0.75/0.87 cm, which means
four pixels of extra information in the Matrice 300. The flight time, adding the nadiral
and oblique cases in Phantom 4, takes 29 min, while in the Matrice 300, it takes almost
21 min for Oblique and almost 16 min for SmartOblique. The problem encountered in the
case of the Phantom 4 is the need for a second battery to cover 100% of the castle, which
affected lighting changes on the object. These differences are minor in the Oblique case of
P1, although the different flight directions can also affect lighting differences. It is important
to indicate that these differences are always conditioned by external parameters such as
clouds and the inclination of the sun. However, the quality of the models and their lighting
differences are shown in the final result and are affected by these external parameters.
In order to validate the methodology used to obtain point clouds from calibrated
high-resolution RGB sensors versus uncalibrated sensors of lower resolution, a geometrical
comparison was made between the flight performed with the P1 camera and the P4P. As
stated in the introductory section and presented in the data in the materials (Section 2.2),
the support performed for the Phantom 4P aimed to establish a common coordinate system.
On the other hand, the points obtained with ET and GNSS over different points of the castle
allowed us to evaluate how the point clouds obtained with both flights behave (Table 2)
and, beyond indicating a better density of the point cloud, to propose a methodology in
which it is not necessary to have points over the object to calibrate its height. The result of
the comparison is shown in Table 3.

<!-- p. 11 -->

Heritage 2025, 8, 22 11 of 20

Table 2. Elevation ground control points used in the reference system combination (Point P).
Units in metres.

ZGNSS ZP1 ZP4P Error P1 Error P4P

P 1 995.047 995.031 995.041 0.016 0.006

P 2 996.441 996.414 996.405 0.027 0.036

P 3 1000.240 1000.242 1000.238 −0.002 0.002

P 4 1001.686 1001.653 1001.639 0.033 0.047

Table 3. Elevation control points used in the point cloud comparison. Units in metres.

Dif.
Control Point Type ID Z ZP1 ErrorP1 ZP4P ErrorP4P RelativeElev
P1–P4P

Total Station Point A 1023.135 1023.120 0.015 1023.310 −0.175 36.880 0.190

GNSS Point B 1011.360 1011.349 0.011 1011.479 −0.119 48.651 0.130

GNSS Point C 1007.677 1007.686 −0.009 1007.756 −0.079 52.314 0.070

Total Station Point D 1007.045 1007.065 −0.020 1007.153 −0.108 52.935 0.088

Total Station Point E 1012.719 1012.709 0.010 1012.818 −0.099 47.291 0.109

Total Station Point F 1023.764 1023.751 0.013 1023.919 −0.155 36.249 0.168

Total Station Point G 1023.660 1023.659 0.001 1023.855 −0.195 36.341 0.196

Total Station Point H 1007.330 1007.341 −0.011 1007.401 −0.071 52.659 0.060

Total Station Point I 1017.678 1017.688 −0.010 1017.822 −0.144 42.312 0.134

Total Station Point J 1022.778 1022.758 0.020 1022.957 −0.179 37.242 0.199

GNSS Point K 1009.594 1009.574 0.020 1009.686 −0.092 50.426 0.112

As shown in Figure 9, the error in altitude increases proportionally with scale error due
to the self-calibration performed in the case of the flight with the Phantom 4, demonstrating
that in flights without an RTK system that allows the altitudes of the perspective centres to
be determined with precision, it is necessary to perform additional field support, while the
methodology used in this research removes this need. The R2 obtained on the 11 points
specifically for this quality control is 0.9.

Figure 9. A comparative plot of accuracies obtained between both point clouds P1 vs. Phantom 4 and
castle control points at different altitudes with an R2 of 0.9.

Figure 10 shows the proportionality of the errors in the profile generated on both point
clouds in four specific areas and at different heights of the castle.

<!-- p. 12 -->

Heritage 2025, 8, 22 12 of 20

Figure 10. Profile and errors obtained at different altitudes with the quality control performed with
Total Stations and GNSS RTK.

3.2. Processing and Adjustment Results: Point Cloud and Digital Model Extraction

Regarding the aero-triangulation adjustment process and generation of the initial key
point cloud that allows the precision of the aero-triangulation of the image blocks used
in each case to be determined, the following results were obtained: RMS of 1.2 cm for the
Phantom 4 and RMS of 0.85 cm for the cases of the Matrice 300 RTK. Comparing the errors
found between the two models and the errors shown in Table 3, the RMS of the checked
points using the P1 model was 1.8 cm, and that of the P4P model was 16.8 cm. In the P4P, it
is important to show that the model had 12.8 cm of offset, while the P1 model had only
3 mm. The high number of images allows high precision in all cases, and the density of
each of the clouds will depend on the number of images available, their resolution, and
their quality. The large number of points obtained and stated in Section 2.3 allowed us to
achieve great detail in the representation of the walls and in the details of the castle. The
estimate of the error of fit, as shown in [20], depends a lot on the flight planning. In the
case of flights with a flat surface, the best results are obtained by adding crossed strips
of lower flight heights at both ends, an aspect that is not contemplated in current flight
planning programmes. In our case, it is a terrain with great unevenness, and the planning of
both flights is a double grid, which is the one recommended by these authors.
The point clouds obtained with the Phantom 4 have 3.8 M points compared to
the 38.6 M points of the P1 camera, as shown in Figures 11–14 and the differences be-
tween the two generated flights with a different camera.

Figure 11. Images (a,c) correspond to the Phantom 4 point cloud and (b,d) correspond to the Matrice
300 RTK and P1.

<!-- p. 13 -->

Heritage 2025, 8, 22 13 of 20

Figure 12. Images (a,c) correspond to the Phantom 4 point cloud and (b,d) correspond to the Matrice
300 RTK and P1.

Figure 13. Images (a,c) correspond to the Phantom 4 point cloud and (b,d) correspond to the Matrice
300 RTK and P1.

Figure 14. Images (a,c) correspond to the Phantom 4 point cloud and (b,d) correspond to the Matrice
300 RTK and P1.

<!-- p. 14 -->

Heritage 2025, 8, 22 14 of 20

In Figure 11b, the detail of the battlements is clearer than in Figure 11a. The same
occurs with the base of the second walled enclosure and greater clarity in the piles of
stone collected from the last excavation (Figure 11d compared to Figure 11c), as expected,
given the resolution of the sensors used in the cameras. The resolution of the P1 camera
(Figure 11b,d) is much better than that of the Phantom 4.

3.3. Volume and Product Results

The estimation of the volume that will be needed for the archaeological excavation that
is intended to be carried out is based on the digital surface model (DSM). The volume of
earth that belongs to the collapse of the north-eastern external wall was analysed. Once the
collapse zone between the road and the wall was limited, a triangulated irregular network
(TIN) was generated (Figure 15).

Figure 15. A digital model of surfaces in the area near the castle and generation of the TIN model for
the estimate of volume (in grey). The perimeter of the study is defined as the base area.

Subsequently, a perimeter was defined as a base surface for the estimation of the
volume, taking its lowest point (1052 m) as a reference plane, which is the height of the
battlement that does not present collapse on the way. The result for the studied area
was a surface of 222.37 m2 and a perimeter of 62.442 m, with a volume of 1039.89 m3.
The analysis of the data is shown in Table 4. For the restoration of the northeast wall and
the archaeological excavation that is intended to be carried out, it is necessary to calculate
the collapse produced. The data set used was that of the DSM obtained by drone flight at a
height of 60 m and with a GSD of 0.016 m.

Table 4. Analysis and estimation of soil volume.

Zone Area, m2 Perimeter, m Reference, m Volume, m3

Zone 1 222.37 62.442 1052 1039.89

Figure 16 shows the area and profile of the excavation.

<!-- p. 15 -->

Heritage 2025, 8, 22 15 of 20

Figure 16. A DSM in the area near the collapsed wall and cross-sectional profile of the terrain.

\4. Discussion

Solutions are proposed to facilitate the study of the dissemination and preservation of
heritage and therefore remain faithful to the London Charter [21] and the Seville Princi-
ples [22]. This work is guided by the principles of the Spanish Society of Virtual Archaeology
(SEAV) as set out in [22], which promotes the responsible use of new technologies and their
levels of quality applied to the comprehensive management of archaeological heritage.
Virtual reconstructions contribute to improving knowledge and understanding of
this type of cultural heritage [23], such as the archaeological remains of the Almenara
castle and other archaeological remains of cultural heritage that are being destroyed and
are not being valued. Some castles are located in hard-to-reach places, as they were built
as fortresses in safe places. We agree with Pan et al. [24] about improving the accuracy
of the 3D reconstruction of the hidden parts, and this information must be available to
improve the accuracy of the 3D models, such as the one we have made with the flight of the
Matrice 300 RTK UAV and the P1 camera. Our work also provides the estimate of the most
precise volumes for future archaeological excavations and recovery of the castle’s remains.
We agree with Enriquez et al. [25] that it is necessary for the historical heritage to be studied
and properly preserved so that, generation after generation, it is transmitted without
blurring its essence. An enormous amount of information about an archaeological site can
be obtained in a single day with current UAVs like the two we have used in this study.
Additionally, 3D modelling is improving the accuracy and efficiency of registration methods.
In fact, these models allow the archaeologist to measure and analyse the characteristics
of the objects, their location, and the surrounding landscapes with a level of detail and
precision that has never before been possible with cameras such as the P1, as demonstrated
by the accuracies obtained in Table 3 at the numerical level and in Figure 10, where the
errors in different areas of the 3D models are clearly shown, when the definition of the
models contains errors due to different scales that cause offsets in the result. However, the
problem is that these high precisions require computers with high processing memory and
good graphic cards, as without them, the data cannot be downloaded. New ways to collect
field information in a short time are proposed with this more precise camera and a drone
with RTK.

<!-- p. 16 -->

Heritage 2025, 8, 22 16 of 20

With these means, we can create 3D models and orthoimages of cultural heritage sites
to document the current state of other castles in Spain that are also in ruins.
The work developed by Del Pozo et al. [26] with the SAMBA program is not applicable
in this case, as, with sensors such as the P1 camera, we have a similar resolution for surfaces
similar to that of “Cueva Pintada” and with much less data collection work, as the flights
were made in less than half an hour. Its system with a telescopic structure is slow and
requires many hours of data collection. In addition, the problem of low light outdoors does
not exist in this case. This work demonstrates that it is feasible to make high-precision 3D
models with RTK UAV flights, avoiding taking many control points and performing faster
and more precise work.
As Emmitt et al. [27] expresses, there may be a benefit to recording each layer of the
archaeological excavation with a high degree of detail, creating a record of the stages of
the excavation; however, it is necessary to make a record like ours before the excavation
in order to save the data and analyse the volume of remains that will have to be moved,
and another at the end of excavation to document the work carried out. It must be taken
into account that these studies require time to prepare and significant costs, although in the
future, this methodology will be cheaper and will be carried out more automatically.
In our work, we carried out this same 3D reconstruction with precise and well-
georeferenced measurements, reducing the workload, and the volume of data generated in
the point cloud was lower. In addition, our work generates 2D raster layers for future work,
as well as vector layers to calculate parameters such as the volume of buried structures.
In the 8th International Workshop on 3D Virtual Reconstruction and Visualization of
Complex Architectures (3D-ARCH), authors such as [28] propose 3D models such as the one
presented in this paper for future archaeological excavations. The 3D renderings made with
the two flights paid off because the resulting models provide a solid base for future updates,
and after such archaeological work, it is necessary to fly a UAV again and reconstruct the
3D models with the new images. Therefore, the comparison between these two flights that
were made is a good comparison for the final work, for which we need precision.
These 3D models can also be used to evaluate the safety and conservation requirements
of the structures, which can give way, as in all excavations, there are many risks that are
not detected just by looking, such as workers’ safety in the event of possible collapses of
the structures in the castle walls. In this sense, the work of Cascini et al. [29] presents a
good model for the selection of a rehabilitation intervention, which should be based on
compliance with various preservation and conservation requirements, in addition to the
study of structural resistance, avoiding risks to workers. As this paper very well states,
the analysis revealed that the failure mechanisms and the collapse load multipliers are
relevant and that reinforcement interventions can be conveniently evaluated when the
behaviour of a complete structural unit is investigated, but we must take into account that
the methodology proposed by Cascini et al. [29] provides an idea of the structural capacity
only. Our 3D modelling and volume estimate work is then used for this complete structural
evaluation that is required in future excavations of the collapsed walls.
UAV flights, like the ones used in this study, are highly precise, requiring a short
time for data acquisition. Therefore, compared to other geomatics techniques, labour costs
decrease. As in [30], the results demonstrate the effectiveness of topographic techniques
based on images captured with drones when we want to make 3D models in structures of
considerable size, characterised by the difficulty of accessibility of some areas and the lack
of well-known geometric characteristics defined, as in our case, where there are areas of
the castle that are very difficult to access and with large slopes that prevent high-precision
terrestrial photogrammetric work. In our case, the unevenness is in several facades of

<!-- p. 17 -->

Heritage 2025, 8, 22 17 of 20

the castle from the northwest to the southwest where the facade is a few metres away, a
difference of more than 30 m in height, as shown in Figure 6d.
The use of an RTK system in flight improves the vertical scale of the model, which is
of great importance in this case, as access to the tops of the towers is not possible.
Although the accuracy after aero-triangulation of both flights is not high
(Phantom 2 cm—M300RTK, 1 cm, both with mark signals), the use of RTK achieves
kinematic support in the perspective centres that the Phantom 4 GNSS does not have
by methodology, resulting in a greater need for ground support. This is one of the advan-
tages of using RTK equipment over GNSS Standalone, even if the difference in elevation in
GCPs was 10 m to establish the vertical scale in the case of Phantom 4.
As stated by [31], our work presented in this paper is a good example of the use of
virtual scientific reconstruction for the development and consolidation of new excavations,
not only reconstructive but also interpretive of this cultural heritage. As a 3D graphic re-
source, the data obtained with the two flights serve to disseminate historical archaeological
knowledge, a fundamental objective when carrying out any scientific work. In addition, as
a result of this work, we have the possible three-dimensional reconstructions of the walls
and battlements that are not preserved but are used for virtual visits of what the castle
could have been.
As Radulescu [32] pointed out in the 3D modelling of the Rákóczi–Bánffy castle in
Urmenis,, as a whole, the final products of the UAV aerial photogrammetry are sufficient.
For the same reason, no work has been conducted on 3D modelling with denser point
clouds with a terrestrial laser scanner. In their case, the differences they have are less than
15 mm. Otherwise, it requires a large volume of work and data to process. The virtual
reconstruction of the monuments can be a low-cost solution in these cases since rebuilding
a castle would involve considerable investments of money. That is why these 3D modelling
studies are used for virtual visits and the preservation of archaeological remains. UAV
flights and 3D reconstruction with models, printed in 3D, will be increasingly feasible
solutions for the preservation of cultural heritage such as castles, of which Spain has many
in ruins.
The work of Manferdini [33] shows us its evaluation of 3D scans carried out with
different methodologies and technologies, and the cost reduction that is carried out with
the flight times and the high precision. The studies demonstrate the high quality of the
model produced by the tandem of the P1 + vertical and oblique methodology from the
UAVs followed in this research. The high density of the point cloud (Table 1) shows
the high definition of all places in the castle, removing the typical shadows and holes
that are difficult for this type of study. Our study is similar to the methodology used
by Abdurahman [5], where the aerial images are taken at noon, with high-resolution
sensors and flight planning from different angles (nadir and oblique), which facilitates the
reconstruction of the 3D model and avoids obtaining hidden areas that are difficult to access.
The GSD obtained in our flight with the Matrice 300 UAV is 0.75 cm/pixel, lower than that
obtained in Abdurahman’s study (0.95 cm/pixel), even for a structure with different height
levels. The proposed planning with different angles (nadir and oblique) reduces costs
and time, improving the acquisition of aerial images over archaeological remains where
access is complex or where there is arboreal vegetation, as in the case of the study carried
out by Cianci [11] or Kompoti [10]. Contrary to the flight plan used by Kompoti, where
different images are manually taken towards the facades of the walls with an orientation
of 45 and 20 degrees, in our study, through the flight pattern with SmartOblique, images
of 135◦SE, 45◦NW, 45◦NE, and 135◦SW were obtained (Figure 4), which implies a
significant improvement in the acquisition of images in the case of high walls, as in the case
of the castle of Almenara.

<!-- p. 18 -->

Heritage 2025, 8, 22 18 of 20

With this new P1 camera installed in the Matrice 300 RTK, the oblique flight was
achieved in 20.54 min and 15.41 min for the SmartOblique flight, which means that the
two flights had very short data collection times. The same was obtained for the flights of the
Phantom 4, with a flight time of 12 min for Oblique and 17 min for SmartOblique. Compared
to traditional land surveying methods (Total Stations) and terrestrial photogrammetry,
the time required for data acquisition is significantly reduced. The same takes place
with terrestrial laser scanners, which would require more time for data collection and,
subsequently, for data processing. We can confirm that the two flights carried out improved
the data collection time considerably compared to other traditional alternatives. If the
required precision is less than 1 cm, we would opt for the flight of the Matrice 300 RTK as
the preferred choice, whereas if you want to make models whose scale accuracy can be less
than 2 cm, then the Phantom 4 is sufficient. Actually, some are already equipped with RTK
today, so checkpoints in the field can be reduced for flight.
The method proposed by Scianna [34] can be replaced by the flights performed in this
study. Our work can serve as a methodology for 3D documentation and digitisation of
cultural heritage usable for any cultural asset.

\5. Conclusions

New information and communication technologies offer solutions for data acquisition.
With the aim of preserving and disseminating the archaeological remains of the castle of
Almenara (Cuenca), two flights with different UAVs were evaluated for data acquisition.
We analysed the flights with different navigation systems and RGB cameras, achieving
an improvement in the GSD of more than 40% and a density of the point cloud 10 times
higher. The 3D models generated with these new cameras and RTK positioning systems
improve the quality and precision and can be used to calculate the volume of archaeological
excavations to be carried out in the future. They can also be used to analyse deterioration
due to erosion over time. The models generated can be used for other parallel studies
that may arise, such as the analysis of visibility and accessibility or territorial studies and
archaeological work. In addition, experts in the preservation and dissemination of cultural
heritage use social networks as a new source of information to monitor and document
sites in inaccessible areas. This study will serve as a basis for the planning of future
archaeological excavation works, modern virtual tourism, and accurate and well-organised
3D documentation of historical monuments.
As interest in a virtual approach to these historic properties has grown, the need for
high-quality data for 3D modelling has arisen [35]. Thanks to research activity and in-
depth studies in the field of 3D modelling, future developments will seek to optimise data
collection with the ultimate aim of minimising the number of applications used. This work
demonstrates the improvements that can be achieved with this RTK navigation system and
improved gimbal-mounted sensors on UAVs. We have analysed whether we want to have
high accuracy with the drawbacks of downloading data from virtual tours or to improve
the speed required by these tours. Both flights give us two possibilities: putting control
points on the ground is sufficient to generate virtual tours, but to achieve an accuracy of less
than 10 mm, a flight with cameras similar to those of the P1 and RTK flights is necessary.
Thanks to this flight comparison, one can choose a specific flight depending on their needs.

Author Contributions: Conceptualisation, J.L.-H., S.L.-C. and T.R.H.-T.; methodology, J.L.-H., E.P.-M.
and M.Á.M.-G.; validation, J.L.-H. and S.L.-C.; formal analysis, T.R.H.-T. and S.L.-C.; investigation,
C.V.I. and J.M.P.; resources, M.Á.M.-G. and E.P.-M.; data curation, S.L.-C., J.L.-H. and T.R.H.-T.;
visualisation, E.P.-M. and M.Á.M.-G.; supervision, J.L.-H., T.R.H.-T., S.L.-C. and E.P.-M. All authors
have read and agreed to the published version of the manuscript.

<!-- p. 19 -->

Heritage 2025, 8, 22 19 of 20

Funding: This research received no external funding.

Data Availability Statement: Dataset available on request from the authors.

Acknowledgments: We want to thank Grupo Acre for their support in this work, allowing us to test
the new P1 camera.

Conflicts of Interest: The authors declare no conflicts of interest.

References

\1. Koutsoudis, A.; Vidmar, B.; Ioannakis, G.; Arnaoutoglou, F.; Pavlidis, G.; Chamzas, C. Multi-image 3D reconstruction data
evaluation. J. Cult. Herit. 2014, 15, 73–79. [CrossRef]
\2. Abad, P.V.; Fernandez, A.F.; Novoa, A.A.R. Lost archaeological heritage: Virtual reconstruction of the medieval castle of San
Salvador de Todea. Virtual Archaeol. Rev. 2022, 13, 22–44. [CrossRef]
\3. Demetrescu, E. Virtual Reconstruction as a Scientific Tool: The Extended Matrix and Source-Based Modelling Approach. Digit.
Res. Educ. Archit. Herit. 2018, 817, 102–116. [CrossRef]
\4. Fiz, J.; Martin, P.; Cuesta, R.; Subías, E.; Codina, D.; Cartes, A. Examples and Results of Aerial Photogrammetry in Archeology
with UAV: Geometric Documentation, High Resolution Multispectral Analysis, Models and 3D Printing. Drones 2022, 6, 59.
[CrossRef]
\5. Yigit, A.; Uysal, M. Automatic crack detection and structural inspection of cultural heritage buildings using UAV photogrammetry
and digital twin technology. J. Build. Eng. 2024, 94, 109952. [CrossRef]
\6. Harshit, H.; Kushwaha, S.; Jain, K. Geometric features interpretation of photogrammetric point cloud from unmanned aerial
vehiclE. In Proceedings of the 17th 3D Geoinfo Conference, Sydney, Australia, 18–21 October 2022; pp. 83–88.
\7. Barrile, V.; Bernardo, E.; Fotia, A.; Bilotta, G. Integration of Laser Scanner, Ground-Penetrating Radar, 3D Models and Mixed
Reality for Artistic, Archaeological and Cultural Heritage Dissemination. Heritage 2022, 5, 1529–1550. [CrossRef]
\8. Puente, I.; Solla, M.; Laguela, S.; Sanjurjo-Pinto, J. Reconstructing the Roman Site “Aquis Querquennis” (Bande, Spain) from GPR,
T-LiDAR and IRT Data Fusion. Remote Sens. 2018, 10, 379. [CrossRef]
\9. Stal, C.; Covataru, C.; Müller, J.; Parnic, V.; Ignat, T.; Hofmann, R.; Lazar, C. Supporting Long-Term Archaeological Research in
Southern Romania Chalcolithic Sites Using Multi-Platform UAV Mapping. Drones 2022, 6, 277. [CrossRef]
\10. Kompoti, A.; Kazolias, A.; Panagiotidis, V.; Zacharias, N. 3D Laser Scanning and UAVs in cultural heritage: The case of Old
Navarino castle in Pylos, Greece. J. Archaeol. Sci. Rep. 2023, 52, 104223. [CrossRef]
\11. Cianci, M.; Calisi, D.; Colaceci, S.; Botta, S.; Pontisso, M.; Quilici, S.; Spallino, C. Integrated 3D methodologies for the survey of
archeological heritage. Disegnarecon 2023, 16, 4.1–4.12. [CrossRef]
\12. Benavides Lopez, J.A.; Martin Civantos, J.M.; Rouco Collazo, J. Architectural survey and archaeological analysis of the pinar
castle as a starting point for its conservation. Virtual Archaeol. Rev. 2020, 11, 95–115. [CrossRef]
\13. Potje, G.; Resende, G.; Campos, M.; Nascimento, E. Towards an efficient 3D model estimation methodology for aerial and ground
images. Mach. Vis. Appl. 2017, 28, 937–952. [CrossRef]
\14. Barreau, J.-B.; Bernard, Y.; Petit, Q.; Beuchet, L.; Petit, E.; Platen, V.; Gaugne, R.; Le Rumeur, J.; Gouranton, V. Combination of 3D
Scanning, Modeling and Analyzing Methods around the Castle of Coatfrec Reconstitution. Digit. Herit. Progress. Cult. Herit. Doc.
Preserv. Prot. 2014, 8740, 418–426.
\15. García-Molina, D.; González-Merino, R.; Rodero-Pérez, J.; Carrasco-Hurtado, B. 3D documentation for the conservation of
historical heritage: The castle of priego de cordoba (Spain). Virtual Archaeol. Rev. 2021, 12, 115–130. [CrossRef]
\16. ¸Sasi, A.; Yakar, M. Photogrammetric modelling of hasbey dar’ülhuffaz (masjid) using an unmanned aerial vehicle. Int. J. Eng.
Geosci. 2018, 3, 6–11. [CrossRef]
\17. Yimaz, H.; Yakar, M.; Gulec, S.; Dulgerler, O. Importance of digital close-range photogrammetry in documentation of cultural
heritage. J. Cult. Herit. 2007, 8, 428–433. [CrossRef]
\18. Cuenca-Garcia, C.; Risbol, O.; Bates, C.R.; Stamnes, A.A.; Skoglund, F.; Odegard, O.; Viberg, A.; Koivisto, S.; Fuglsang, M.;
Gabler, M.; et al. Sensing Archaeology in the North: The Use of Non-Destructive Geophysical and Remote Sensing Methods in
Archaeology in Scandinavian and North Atlantic Territories. Remote Sens. 2020, 12, 3102. [CrossRef]
\19. Balsi, M.; Esposito, S.; Fallavollita, P.; Melis, M.G.; Milanese, M. Preliminary Archeological Site Survey by UAV-Borne Lidar:
A Case Study. Remote Sens. 2021, 13, 332. [CrossRef]
\20. Arevalo-Verjel, A.N.; Lerma, J.L.; Prieto, J.F.; Carbonell-Rivera, J.P.; Fernandez, J. Estimation of the Block Adjustment Error in
UAV Photogrammetric Flights in Flat Areas. Remote Sens. 2022, 14, 2877. [CrossRef]
\21. Charter, L. The London Charter for the Computer-Based Visualisation of Cultural Heritage. 2009. Available online:
http://www.londoncharter.org (accessed on 10 March 2024).

<!-- p. 20 -->

Heritage 2025, 8, 22 20 of 20

\22. Lopez-Menchero, V.M.; Grande, A. The principles of the Seville Charter. In Proceedings of the CIPA Symposium Proceedings,
Prague, Czech Republic, 12–16 September 2011; pp. 2–6.
\23. Rojas-Sola, J.I.; del Rio-Cidoncha, G.; Fernandez-de La Puente Sarria, A.; Galiano-Delgado, V. Blaise Pascal’s Mechanical
Calculator: Geometric Modelling and Virtual Reconstruction. Machines 2021, 9, 136. [CrossRef]
\24. Pan, J.; Li, L.; Yamaguchi, H.; Hasegawa, K.; Thufail, F.I.; Brahmantara; Tanaka, S. Integrated High-Definition Visualization of
Digital Archives for Borobudur Temple. Remote Sens. 2021, 13, 5024. [CrossRef]
\25. Enriquez, C.; Manuel Jurado, J.; Bailey, A.; Callen, D.; Jose Collado, M.; Espina, G.; Marroquin, P.; Oliva, E.; Osla, E.; Isabel Ramos,
M.; et al. The UAS-Based 3D Image Characterization of Mozarabic Church Ruins in Bobastro (Malaga), Spain. Remote Sens. 2020,
12, 2377. [CrossRef]
\26. Del Pozo, S.; Rodriguez-Gonzalvez, P.; Hernandez-Lopez, D.; Onrubia-Pintado, J.; Guerrero-Sevilla, D.; Gonzalez-Aguilera, D.
Novel Pole Photogrammetric System for Low-Cost Documentation of Archaeological Sites: The Case Study of “Cueva Pintada”.
Remote Sens. 2020, 12, 2644. [CrossRef]
\27. Emmitt, J.; Pillay, P.; Barrett, M.; Middleton, S.; Mackrell, T.; Floyd, B.; Ladefoged, T.N. A Comparison of Volumetric Reconstruction
Methods of Archaeological Deposits Using Point-Cloud Data from Ahuahu, Aotearoa New Zealand. Remote Sens. 2021, 13, 4015.
[CrossRef]
\28. Landes, T.; Heissler, M.; Koehl, M.; Benazzi, T.; Nivola, T. Uncertainty visualization approaches for 3D models of castles restituted
from archeological knowledge. In Proceedings of the 8th International Workshop 3D-Arch: 3D Virtual Reconstruction and
Visualization of Complex Architectures, Bergamo, Italy, 6–8 February 2019; pp. 409–416. [CrossRef]
\29. Cascini, L.; Brando, G.; Portioli, F.P.A.; Forgione, M.R.; Mazzanti, C.; Vasta, M. Force-Based Seismic Evaluation of Retrofitting
Interventions of Historic Masonry Castles by 3D Rigid Block Limit Analysis. Appl. Sci. 2020, 10, 5035. [CrossRef]
\30. D’Aprile, M.; Piscitelli, M. Survey, stratigraphy of the elevations, 3D modelling for the knowledge and conservation of archaeo-
logical parks: The castle of avella. In Proceedings of the 8th International Workshop 3D-Arch: 3D Virtual Reconstruction and
Visualization of Complex Architectures, Bergamo, Italy, 6–8 February 2019; pp. 289–296. [CrossRef]
\31. Aparicio-Resco, P.; Garcia Alvarez-Busto, A.; Muniz-Lopez, I.; Fernandez-Calderon, N. 3D virtual reconstruction of the Gauzon
Castle (Castrillon, Principado de Asturias). Virtual Archaeol. Rev. 2021, 12, 158–176. [CrossRef]
\32. Radulescu, V.M.; Radulescu, G.M.T.; Nas, S.; Radulescu, A.T.; Bondrea, M.; Radulescu, C.M. Geoinformatics Technologies for
Preservation of Cultural Heritage, Case Study, Rákóczi-Bánffy Castle, Urmenis,, Bistri¸ta Năsăud County, Romania. J. Appl. Eng.
Sci. 2021, 11, 41–48. [CrossRef]
\33. Manferdini, A.M.; Galassi, M. Assessments for 3D reconstructions of cultural heritage using digital technologies. In Proceedings
of the 3D-Arch 2013—3D Virtual Reconstruction and Visualization of Complex Architectures, Trento, Italy, 25–26 February 2013;
pp. 167–174.
\34. Scianna, A.; La Guardia, M. Survey and Photogrammetric Restitution of Monumental Complexes: Issues and Solutions—The
Case of the Manfredonic Castle of Mussomeli. Heritage 2019, 2, 774–786. [CrossRef]
\35. Banfi, F. HBIM, 3D drawing and virtual reality for archaeological sites and ancient ruins. Virtual Archaeol. Rev. 2020, 11, 16–33.
[CrossRef]

Disclaimer/Publisher’s Note: The statements, opinions and data contained in all publications are solely those of the individual
author(s) and contributor(s) and not of MDPI and/or the editor(s). MDPI and/or the editor(s) disclaim responsibility for any injury to
people or property resulting from any ideas, methods, instructions or products referred to in the content.
