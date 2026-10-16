---
type: libro
title: "3D of CH Buildings based on GenAI & Geospatial Data"
author: "Barbero-Álvarez et al."
categoria: "Tecnología láser, fotogrametría, otros"
paginas: 10
extraccion: "texto"
fuente: "local:E:/DISCIPLINAS, TEXTOS Y MAPAS/Biblioteca digital/Tecnología láser, fotogrametría, otros/Amultimodal approach to 3D modelling of Spanish cultural.pdf"
convertido: 2026-10-13
---

# 3D of CH Buildings based on GenAI & Geospatial Data

> Texto extraído de `Tecnología láser, fotogrametría, otros/Amultimodal approach to 3D modelling of Spanish cultural.pdf` (10 páginas, texto). El PDF original está en el disco E: (DISCIPLINAS, TEXTOS Y MAPAS\Biblioteca digital); `<!-- p. N -->` marca el inicio de cada página.

<!-- p. 1 -->

DIGITAL HERITAGE (2025)
S. Campana, D. Ferdani, H. Graf, G. Guidi, Z. Hegarty, S. Pescarin, and F. Remondino (Editors)

A multimodal approach to 3D modelling of Spanish cultural
heritage buildings for visualization and management based on
generative AI and geospatial data

Miguel Antonio Barbero-Álvarez1 & Javier Rodríguez Peña1 & Cristian Olmedo Ferrero1 & Marina A. Álvarez Alonso1

1Universidad Politécnica de Madrid, Spain

Abstract
This work presents a study on blending the latest artificial intelligence technologies with geospatial data for managing and
visualizing Spain’s cultural heritage. The goal is to achieve a new stable simulation using multimodal data that serves as
a foundation for future advancements in AI-driven cultural heritage 3D modeling technology. Fundamentally, the work here
exposed is a proof of concept to assess whether the exploration and visualization of the geospatial information related to Spain’s
cultural heritage can rely on AI concepts to improve its processing and understanding. This will lay ground for enhancing the
visitor experience at heritage sites within their contextual environment. The application of the proposed methodology to a
real-world case, such as the Monastery of El Escorial, has demonstrated the potential of generative AI in the management
and dissemination of cultural heritage resources. This method is innovative because it proposes a new approach in which
the combination of different AI-generated results serves as the starting point for creating 3D models of buildings, which can
be manually refined aftwerwards, instead of the more costly manual acquisition and modelling from scratch. The approach
integrates multimodal sources of graphical information, including videos, photographs, and text, to be blended with geospatial
data. It is concluded that design methods integrating AI techniques and geospatial data add quality to working models, given
that buildings are inherently tied to their spatial context. The addition of these properties allows for a more precise and detailed
digital representation. Furthermore, these models can be visualized in web applications, thus shedding light on AI as a valuable
tool to be added to the already existing modelling solutions in digital cultural heritage.

\1. Introduction where information can be filtered according to different criteria.
The main advantage of using GIS technology is its ability to in-
Currently, the study of heritage uses the latest advances in digi-
telligently create complete 3D digital models with meaningful at-
tization and smart technologies to develop 3D models of histori-
tributes related to materials, construction systems, damage, moni-
cal buildings. The objective is to obtain a digital model that faith-
toring networks, and similar elements. Another key advantage is its
fully represents the geometry and information of the building, such
ability to achieve interoperability and data transformation. All these
as materials and structural conditions [RMFF20, ABM21]. Un-
advantages make GIS technology the best option for managing her-
til recently, HBIM (Historic Building Information Modeling) was itage buildings today [SRB∗20,CKC∗18,RRN∗21]. In this context,
used, but its main problem is interoperability and data transforma-
and considering the current state of the digital technologies, it is
tion due to the limitations of existing software like Revit [rev],
of extreme interest to combine the generating powers of AI with
Rhinoceros [rhi], etc., and its inability to create complex geome-
GIS to enhance the experience of heritage buildings. The aim is
tries. To overcome these limitations, nowadays, geoinformatics
to find a solution that combines innovative techniques for creating
techniques can be used [SPMPL22, ACPG22, Ton19]. This disci-
3D models using AI-based 3D image generation tools and geospa-
pline includes data acquisition methods in the form of point clouds,
tial data, as understood within GIS, in order to take the first steps
such as photogrammetry, laser scanning, LiDAR, remote sensing,
towards enriching the user experience for visitors to heritage sites
drone photographs and videos, and the use of Geographic Informa-
located in their real context. With this multimodal approach, the re-
tion Systems (GIS) [SAdBGMC∗23]. They are based on the use
sults can be visually analyzed through web or mobile apps based
of a geospatial database capable of storing a wide variety of al-
on spatial data infrastructure (SDI) technologies, therefore enhanc-
phanumeric information, as well as raster and vector products, all
ing the understanding of the heritage buildings in their geospatial
properly geolocated. Thanks to this capacity, there are many ap-
context. Fundamentally, it is sought to assess whether generative
plications that use GIS for heritage preservation, both at the city
AI can deserve the considerations of being a valuable asset to the
level and at the building level [LWX21,CKC∗18,FB20,QCAH21],

© 2025 The Author(s).
Proceedings published by Eurographics - The European Association for Computer Graphics.
This is an open access article under the terms of the Creative Commons Attribution License, which
permits use, distribution and reproduction in any medium, provided the original work is properly
cited.

DOI: 10.2312/dh.20253085 https://www.eg.org https://diglib.eg.org

<!-- p. 2 -->

2 of 10 Barbero-Álvarez et al. / 3D of CH Buildings based on GenAI & Geospatial Data

Figure 1: The Monastery of El Escorial

heritage scientist for an effective but simple and quick modelling 2023: Opportunities for data.europa.eu [Ces]. This is one of the arrequiring minor adjustements, instead of relying on the more costly eas where this work is framed, using a lightweight Cesium-based
manual construction. Furthermore, it is desirable that this asset can visualization client [SAdBGMC∗23], to display 3D models of herbe used by everyone regardless of their technical background, in itage created with AI. Currently, within GIS technology, there are
order to alleviate the chain of production of heritage modelling. two ways to generate 3D models (M3D) using AI. The first way
This work is innovative compared to other studies due to the use of is photographic modeling using AI through text-to-image, imagesmart technology capable of simplifying the creation of these 3D to-image, and video-to-image methods. These generate 2D and 3D
models, by applying the latest technologies for the management representations that capture architectural features but do not conand representation of spatial data. Lastly, it is intended that this in- tain spatial coordinates. The output format is GLB (GL Transformation is accessible to all people interested in 3D simulation or mission Format Binary), a binary version of GLTF, used for 3D
the conservation of Spanish, and by extension, the worldly cultural models in web applications, video games, and augmented reality.
heritage. This paper is structured in the following manner: After When these are deployed in Spatial Data Infrastructure (SDI) viewthe introduction, a section describing the related work is outlined. ers for geospatial information, they have to be georeferenced —
Afterwards, explanations of the methodology, justifying the usage that is, assign spatial coordinates using GIS software that mainly
of data and software, is given. The experiments and visualizations works with geospatial data such as Shapefiles, GeoJSON, Geoaround the sought proof of concept are described, and critically ex- TIFF, KML, DXF, among others. The second way is to use AI techplained. Lastly, conclusions and future work are prompted. niques with geospatial point clouds obtained from laser scanning
and photogrammetry. This method allows for generating accurate
3D models that capture both the architectural characteristics and
\2. Related work the geospatial coordinates [MST∗20]. The work carried out shows
There exists different focuses on how to generate a 3D model of a an unique approach to other works by integrating different informaCultural Heritage Building. The most widespread are the Building tion sources to create intelligent 3D models using geospatial data
Information Model (BIM) focused, and the GIS focused. The us- accessible to everyone from official sources and open-source AIage of AI to generate 3D models of heritage buildings [CNG∗22, based tools. This creates a project that can continue to evolve with
DKS21] using geospatial data and techniques plays an important the help of anyone interested in it.
role [NSA∗19, HDP21, EMK21]. Its visual analysis through Web
Apps or Mobile Apps [SAMGA∗20, dBGGCAM∗24], based on
Spatial Data Infrastructure (SDI) technologies [Cen], which as a 3. Materials and Methods
product of the OGC (Open Geospatial Consortium) [22] are open
to continuous innovation, make these tools flexible, multi-content, The Monastery of El Escorial, located in the town of the same name
and always expandable. This approach fits within the lines of in the Community of Madrid, was built in the 16th century by the
GeoAI, Geospatial Artificial Intelligence combined with geospatial architect Juan de Herrera for King Philip II, is considered one of the
data, which was addressed in 2023 in the report Geospatial Trends "jewels" of Spain’s cultural heritage. It is a monumental complex

© 2025 The Author(s).
Proceedings published by Eurographics - The European Association for Computer Graphics.

<!-- p. 3 -->

Barbero-Álvarez et al. / 3D of CH Buildings based on GenAI & Geospatial Data 3 of 10

Figure 2: Representation of the Monastery of El Escorial in OSM

that includes a royal palace, a basilica, a pantheon, a library and a and editing small areas or adding information that may be of intermonastery, among other buildings (see Figure 1). est in the future. As shown in Figure 2, it is possible to add roads
or points that might not have been marked.
In order to generate and visualize the intended models, a traditional methodology of a chain of steps was followed. This method- Additionally, images and videos representing the building were
ology is perfectly suited to small software development projects downloaded from publicly available sources, such as YouTube.
with specific and clearly defined objectives, as it organizes the dif- Concretely, videos of different lenghts (1:10 minutes and 4:30) and
ferent phases in a rigorous and sequential way: qualities were employed. The reason of employing these sources
• Data acquisition and processing is because of the aim of this work of comprising easy to follow
• Study of the software and model creation guidelines so even teams/organizations of few resources can pro-
• Implementation of a Web3D viewer capable of displaying the duce their models.
developed 3D models.

3.2. Creation of the 3D Models
3.1. Data Acquisition
In this step resides the core point of this research. Several 3D modIn order to correctly carry out the research, appropriate data for both
els of El Escorial are produced employing different approaches to
the geospatial context and the physical dimensions, proportions and
generative AI, and their visual results analyzed. The considered
architectonical appearance of El Escorial are needed. Spatial pre-
methods are:
cision is an essential requirement to ensure the realism of the intended models. Therefore, visual sources as images, Digital plans • Text-to-3D models
(raster or vector), Digitized plans (for example, historical plans), • Image-to-3D models
CAD files or Digital elevation models (DEMs) of the heritage en- • AI-powered photogrammetry models
vironment were consulted. These allow to infer all the visual and
dimensional characteristics and make it fit perfectly into the envi- Since it is of interest that the results outlined in this paper serve as
sioned scenarios of display. The aim is to build them on a well- guidelines and steps for heritage professionals to perform other redocumented geographical and geometric base rather than on vir- constructions regardless of their technological background, readytual, abstract environments - therefore corresponding to the geospa- to-use AI services via API or online dashboards have been favoured
tial requirements of this research. Regarding the geographic spatial over the usage of code.
context of the building for its placement in the visualization, several
tools and data sources were selected: Orthophotos provided by the
3.2.1. Text-to-3D models
Spanish National Geographic Institute and images collected from
Google Earth, drone videos of El Escorial for processing with pho- For the generation of the 3D model using text, Meshy AI was chotogrammetry tools and data from OpenStreetMap (OSM). OSM a sen [Mes]. This is a generative AI tool based on a diffusion model
collaborative tool where spatial data from around the world can be powered by GANs (Generative Adversarial Networks) to convert
edited and visualized. It can been used to create the base layers of a text into 3D images and apply textures, prompted by texts describcustom 3D visualizer if desired. Modifications and planning can be ing the model intended to be generated in more or less degree of
done using the OSM web editor, which is very useful for delimiting detail. In Meshy, this GAN model is adapted to produce 3D data.

© 2025 The Author(s).
Proceedings published by Eurographics - The European Association for Computer Graphics.

<!-- p. 4 -->

4 of 10 Barbero-Álvarez et al. / 3D of CH Buildings based on GenAI & Geospatial Data

Figure 3: Models resulting from the prompts given before

Instead of generating a 2D image, it creates three-dimensional vol- which were then condensed with a Summarization of the obtained
umes such as meshes, voxel grids (similar to pixels but represent- result. All of these steps were performed using the Iteration teching space in 3D), or point clouds, which are sets of points in 3D nique, where in each step different aspects, such as dimensional
space representing the surface of an object. Since the generation information, external appearance, or a combination of both, was
is text-based, the prompting strategy has been of great importance. specified.
A combination of several prompt engineering guidelines and techniques has been used:
• Write clear and specific instructions (do not confuse clear with 3.2.2. Image-to-3D models
short)
Meshy also incorporates the functionalities of 3D generation of a
• Expansion: The opposite of summarization, expansion involves
3D object employing a single image, using the same GAN princi-
developing an initial idea or response by adding more details,
ple. To obtain a high-quality image of the entire monastery with
examples, or explanations. It is useful for exploring a specific
relief and depth information, Google Earth was used.
topic in more depth or providing additional context to an initial
question.
• Transformation: This refers to changing the form or structure
of a sentence, question, or idea without altering its fundamental 3.2.3. AI-powered Photogrammetry
meaning. In prompt development, it is useful for rephrasing a
Photogrammetry is a generative technique that attempts to define
query to make it clearer or better suited to the language model
the shape, position, and dimensions of any object using several pho-
being used.
tographs of that object, allowing the construction of a 3D model
• Iteration: This technique involves repeating or refining an ini-
from a series of 2D images taken from different perspectives. The
tial query with the goal of obtaining a clearer or more detailed
images are matched, depth and shape are estimated, and the model
response. In the context of language models like GPT-3.5, for
is generated applying texture on a mesh-based structure. The result
example, iteration can be used to refine an initial question based
can be calculated by choosing an appropriate number of images
on the partial response given by the model. It can also include or
representing the same object from different perspectives. Images
breaking down the task into subtasks with a specific order.
can be manually taken or extracted from video frames. In this use
Following these guidelines and strategies, from an initial sentence case, Luma AI, a fremium video-based photogrammetry tool, was
the techniques of Transformation and Expansion were applied, used [Lum].

© 2025 The Author(s).
Proceedings published by Eurographics - The European Association for Computer Graphics.

<!-- p. 5 -->

Barbero-Álvarez et al. / 3D of CH Buildings based on GenAI & Geospatial Data 5 of 10

3.3. Blending with Geospatial data and Visualization 207 m por 161 m, con torres de 55 m en cada esquina. Cuenta
con 15 claustros, 86 escaleras, 1.200 puertas y 2.673 ventanas.
Once the model has been generated, the last step consists in its
Construido con granito de la sierra de Guadarrama, tiene tejavisualization using geospatial data. Web-based GIS visualization
dos de pizarra azulada. Su fachada austera, de líneas rectas y
clients, or custom-made visualization apps, can easily be employed
sin molduras, se remata con torres esquineras con chapiteles de
for this. Georeferencing, or spatial localization, consists in the as-
pizarra y plomo."
signment of spatial coordinates to the model. If the generated 3D
file contains spatial data, relevant geospatial information for its While the AI was was able to recognize the Monastery of El Esgeoreferencing can be extracted by checking if it can be exported corial as a real building and tried to generate a figure based on the
to GeoJSON, WKT, or Shapefile from the software where it was available information online it can access, the results are subpar for
created. In cases where the models are generated without spatial a building of such magnitude. Therefore, a different strategy based
coordinates, different options are available: on specifying smaller sections of the monastery was carried on. The
prompts were the following:
• Convert the model’s GLB file to a compatible format such as
DXF or OBJ, which can then be imported into a GIS, such as • Specification 1 (Basilica): "Réplica exacta de La Basílica del
QGIS, as a vector layer or mesh. Monasterio del Escorial, con una nave central de 84 metros de
• Georeferencing them manually with geospatial solutions such as largo, 30 metros de ancho y una altura similar, se distingue por su
Cesium Ion. imponente fachada renacentista de líneas sobrias y geométricas,
construida en piedra y granito que combinan tonalidades grisesThe second option has been favoured due to its easiness to use
con detalles en blanco tallado. Con 1 torre con techo en forma dethanks to its GUI and possibilities of taking part of Cesium’s Cloud.
bóveda acabado en un chapitel en el centro de la nave central y 2Once georeferenced, the model can be deployed by any compatible
torres simétricas a los lados con chapiteles de pizarra y plomo."visualization client. For example, a custom WebGIS viewer devel-
• Specification 2 (Courtyard 1): "Réplica exacta de los patiosoped with the Cesium development library using the OSM base
cuadrangulares del Monasterio del Escorial, que tienen unaplans, or the aforementioned Cesium Ion.
bóveda en forma de cruz que suelen construida en piedra y
granito, tejados de pizarra azulada y que combinan tonalidades
\4. Experiments and Results grises con detalles en blanco tallado, con 1 torre de chapiteles de
pizarra y plomo en medio de la cruz."In this section, the results of the different techniques are shown and
• Specification (Courtyard 2): "Réplica exacta del Patio de losdiscussed.
Mascarrones del Monasterio del Escorial el cual, es de forma
cuadrangular, construido en piedra y granito, con tejados de
4.1. Text-to-3D pizarra azulada y que combinan tonalidades grises con detalles
en blanco tallado."Firstly, the prompts in Spanish designed to generate the model of
the Monastery of El Escorial are given in the next list. Considering The results of all the prompts are shown in figure 3
that the generative AI models are sensitive to the specific wording,
translation to English of those could mean slightly different results. It is worth noting that, when generating the model, this AI is
Therefore, in order describe the results of the experiments with the not capable of differentiating depth. Combining this with the apparbiggest fidelity, the untranslated prompts are reproduced here: ently limited information this AI can handle, the results via prompt-
ing only are insufficient for such a detailed piece. However, it is
• Basic prompt: "Una replica real del Monasterio del Escorial, lo- noteworthy that this solution can be very valid for generating more
calizado en Madrid, España" basic shapes, or smaller subsections, that can be added to complete
• Specification of location and dimensions: "Una réplica exacta other models.
del Monasterio de El Escorial situado en la ladera meridional
del monte Abantos a 1.028 metros de altitud, abarca una superfi- Thus, on an exercise on patience, several smaller parts of the
cie de 33.327 metros cuadrados. Su estructura rectangular mide monastery can be separatedly generated, and manually georrefer-
aproximadamente 207 metros de largo por 161 metros de ancho, enced in Cesium Ion, so they can appropriately be placed so they
con torres de 55 metros de altura en cada esquina. El edificio do not overlap. Figure 4(a) shows this puzzle-like model, that fea-
cuenta con 15 claustros, 86 escaleras, 1.200 puertas y 2.673 ven- tures a vague but sufficient resemblance to the monastery. It is com-
tanas." posed by 10 differently generated architectonical elements, includ-
• Addition of external appearance details: "Una réplica exacta del ing towers, walls, courtyards and domes.
Monasterio de El Escorial, construido con sillares de granito
gris amarillento extraído de las canteras de la sierra de Guadar-
4.2. Image-to-3D
rama, y cubierto por tejados de pizarra azulada a dos vertientes,
que reflejan fielmente su austera fachada de líneas rectas y ven- In order to test the Image-to-3D capabilities of Meshy, a highly de-
tanas cuadradas sin molduras, rematada por torres esquineras tailed photo of the building was employed. So the problems of the
con chapiteles de pizarra y plomo." lack of depth could be overcome, photos with relief were favoured.
• Combination of previous prompts: "Réplica exacta de El Monas- Google Earth was used to obtain said photo (Figure 4(b) left). The
terio de El Escorial ubicado en el monte Abantos a 1.028 m intention was to assess if one detailed photo was enough to generate
de altitud y ocupa 33.327 m². Su estructura rectangular mide a compelling model, as the first approach.

© 2025 The Author(s).
Proceedings published by Eurographics - The European Association for Computer Graphics.

<!-- p. 6 -->

6 of 10 Barbero-Álvarez et al. / 3D of CH Buildings based on GenAI & Geospatial Data

The result was not very satisfactory (Figure 4(b) right), produc-
ing a shape similar to a gray rock vaguely resembling El Escorial.
This happens due to the great complexity of the building and the
fact that these types of applications are not capable of generating a
realistic image using only a single image. Reasons that contribute
to this are (1) The lack of depth and texture information in the pro-
vided 2D image, which causes the 3D object to be imprecise, with
imperfections and deformed building elements; (2) the simplifica-
tion of details due to the amount of information in the image used
as a model, which leads to complex textures being ignored; and (3)
the lighting, shading, and colors in the original image create inac-
curacies in the placement of building elements.

In an attempt to solve these problems, the image has to be sim-
plified, and ideally, separated into simpler shapes. Using an editor,
the size of the photos was reduced by selecting specific parts of
the Monastery, which helped decrease complexity when forming
the objects. The background noise in the image was also reduced,
and areas like the sky or other background details were removed.
Thus, a simpler image containing only the sections of interest was
produced. In this work CSM 3D Viewer was used — a free tool for
viewing and generating 3D objects that provides much more con-
trol over the images used to generate the models. As the cropped
section, the the back of the basilica were chosen, as shown in the
left of Figure 4(c).

The produced mesh is then given more realistic textures —
smoothing them, adding details that may have been missing, or
improving lighting and depth errors. Curiously, as shown in fig-
ure 4(c) right, if only only a single photograph is given, the tool
assumes that the object will have the same appearance from all the
sides. This probably happens because only one view of the building
is provided. This leads to problems when trying to create a faith-
ful representation of buildings that are not completely symmetrical.
The final result (Figure 4(d)) — after processing 23 architectonical
subelements of the Monastery of El Escorial individually and geor-
referenced following the same process as in the previous section —
while more faithful to reality in shape, features a great texture and
colour discordance. This happens due to the lack of uniformity in
the photographs used: factors such as the time of the day the picture
was taken, the cameras used, lighting, etc, if not having them under
great control, can cause great disparity. This very effect caused the
generated 3D objects to have different color tones, ranging from
very dark blues to pure whites, which led to an uneven result when
trying to join the pieces.

4.3. Photogrammetry

The complexity of the building makes it difficult to obtain enough
images from the building from all possible angles (including from
above) without using drones. This would break the goal and gap of
this work. Because of this, video-based photogrammetry using pub-
licly available was favoured. For this, high-definition drone videos
Figure 4: From top to bottom: (a) Puzzle-like model composed by of the Monastery of El Escorial were searched. Two videos were
10 separatedly text-to-3D generated architectural elements of the used: a shorter of 1 minute and 10 seconds (Figure 5) and a longer
monastery; (b) Photo used for image-to-3D generation and 3D ob- of 4 minutes and 30 seconds with better definition (Figure 6).
ject generated through image-to-3D processing; (c) Isolated architectonical element of the monastery to be generated and The image- Since video-based photogrammetry provides a large number of
to-3D generated detail based on the left picture; (d) Puzzle-like images to apply textures and correct colors, it is considerately more
model composed by 23 separatedly image-to-3D generated architectural elements of the monastery © 2025 The Author(s).
Proceedings published by Eurographics - The European Association for Computer Graphics.

<!-- p. 7 -->

Barbero-Álvarez et al. / 3D of CH Buildings based on GenAI & Geospatial Data 7 of 10

Figure 5: Model resulting from photogrammetry using the short
video

Figure 7: Noisy model generated by photogrammetry

Figure 6: Model resulting from photogrammetry using the long
video

Figure 8: Model showing the absence of one side of the monastery,
faithful to reality and a competent model to deploy. Nevertheless, corresponding to the non-covered area by the drone
it not completely perfect. Whilst certainly faithful and having performed a compelling result, the great complexity of the building
provokes the appearance of noise (figure 7). This appears over the
Image-to-3D models. The different models can be separately georproperly generated textures, and also on the gaps between archi-
referenced using Cesium Ion, thus blended together, or piecewise
tectonical elements, such as the courtyards. Additionally, it can
blended in a 3D modelling program, as if it was a puzzle. This combe seen that the tool also generates textures in the exterior of the
posed model can also be georreferenced and visualized afterwards
building, corresponding to the streets, which can also be consid-
(Figure 9).
ered as noise. The most important consideration is, however, that
the available videos available do not show the northern side of The concrete geospatial incorporated were the ubication coordithe Monastery. This happens because of Spain’s prohibition to fly nates of the building and its terrains for a correct placing of the
drones over residential areas, and the non-covered parts stand-face model within its spatial context. This is made easy working with
to face to the close by houses in the town of El Escorial. This im- Cesium software. Knowing the virtual counterpart of the placement
plies a complete lack of one side of the monastery (Figure 8). and its surroundings does not only allow a more realistic simula-
tion, but also helps understanding about the nature of the building
In spite of these phenomena, since a video implies a multitude
in nuance and comparison with its geospatial context: reasons for
of frames, only one video is enough to adequately represent the
its materials of construction, state of the facade, etc.
building, at least from a presentation perspective from the better
angle. Additional manual processes for removing the noise, and Additionally, it also helps for a more complete metadatation of
the possibility to join it in the visualizer with other models to fill in the model as a document and an easier migration within software
the lacking area, can make the photogrammetry the most suitable without needing a manual input of geospatial context.
option.

\5. Conclusions
4.4. Geospatial Visualization
At the start of this project, it was assumed that for the Monastery
As it was mentioned before, the final model can be achieved by of El Escorial, one of the most important buildings in Spanish hercombining different parts of the generated models. Using the pho- itage, there would be a large amount of data available — such as
togrammetry as a base, the underrepresented perspectives can be photographs, building plans, point clouds, videos of all its façades,
completed using details and subsections from the Text-to-3D or or a full digitalization of the site. Unfortunately, after an exhaustive

© 2025 The Author(s).
Proceedings published by Eurographics - The European Association for Computer Graphics.

<!-- p. 8 -->

8 of 10 Barbero-Álvarez et al. / 3D of CH Buildings based on GenAI & Geospatial Data

search, almost no geographically relevant data was found that could 6. Appendix
be used for its transformation into a 3D object. Thus, the solution
6.1. Impact assessment
was found on being savvy on how to use the available AI-based
tools, combined with the well-documented known geospatial in- As with most technical works relating to AI models, and especially
formation about its placement and spatial context and coordinates. generative models hosted online on a free or fremium access, raisIt should also be noted that in mid-2024, the Ministry of Culture ing some questions about ethical and environmental impact is alcommissioned a digitalization project of El Escorial, but its results ways interesting. Including these questions helps raising awareness
have not yet been published. However, even with the low-quality of the nature of such systems in today’s geosocial context.
data, the results show that the development of 3D objects using
Quantifying the exact environmental impact of any specific gen-these technologies could be a major step forward in the field of ar-
erative modelling platform is difficult without access to backendchitectural heritage. Although the Community of Madrid currently
model specifications, energy mix of data centers used, or if tech-does not have a large amount of high-quality geospatial data for the
niques of energy optimization have been used. Following sourcesMonastery of El Escorial, the results demonstrate that the combi-
[DWS∗25] [JAEH25], enviromental cost of a 3D generation can benation of the publicly available AI-based tools (Text-to-3D, Image-
0.1–5 g CO2e per 3D generation or 10-50 liters of water for coolingto-3D and Photogrammetry) could represent a great advance in im-
purposes.proving the digitalization and visualization of Spanish cultural heritage, even with a lack of enough compelling data. This technology Considering an ethical usage of generative AI models, there exwould also make it easier to digitize any building for which geospa- ists always the issue with the data, both for training and for infertial data can be obtained — such as housing developments — which ence (in case of the Image/Video-to-3D generation). There is alcould help in urban planning, housing organization, or any other ways the delicate difference between visability vs. ethical usability
field of architecture where creating 3D simulations improves the of online data resources. For this work, accessible and open imfinal outcome. The usefulness of the Cesium tools has also been ages and videos have been employed, such as the OSM images or
demonstrated, not only for the blending the models with geospa- videos in YouTube with Creative Commons license. Nevertheless,
tial data, but thanks its cloud storage capabilities, as it can load any the nature of the data that have been employed to train the models
model without the need for a dedicated database. Furthermore, its and platforms under usage will remain obscure if they do not disavailable library allows the development of custom visualization close them. Furthermore, future usage of the guidelines presented
clients if desired so. The use of AI-based photogrammetry tools in this work by people less conscious of ethical considerations may
was also essential to achieving the results. Luma AI it is currently include restricted, or directly private data.
one of the most powerful video-based photogrammetry tools, capa-
In order to keep the generation as ethical as possible, paying at-ble not only of digitizing buildings but also any type of object for
tention to the license of the data, or using self-generated data (e.g.use in simulations or projects that require 3D elements. Finally, it is
drone videos or photographs manually taken) is imperative. How-important to remind that all the tools used in this project are free or
ever, the topic of the training data will remain obscure, as it is ex-open-source software, and that all the data was obtained from pub-
pected that the destined usrbase of these guidelines will not havelicly available sources. This means that anyone in the world, even
resources or time to build their own models.with little knowledge in these fields, can create their own building digitalization project and contribute to the advancement of this On another hand, transparency about what is real vs. generated is
area. critical in contexts of heritage and research. The more data used for
inference, the more similar will be the model to the real counterpart,
as it has been seen before when generating less precise models with
a limited amount of data. But this also enters the realm of what data
to use. Having enough legally and ethically available data for gen-
eration can mean tedious process of selection, acquisition, cleaning
and augmentation. Therefore, disclosure on the limits of the mod-
els and transparency on its generation will always be a must when
documenting, presenting, and storing models such as the generating
following our guidelines.

6.2. English translation of the Spanish prompts

In this appendix we show the translation from Spanish to English
of the text prompts used in the Text-to-3D pipeline for a better un-
derstanding. It has been automatically performed via Deepl:

Figure 9: Visualization of the final model in a custom geospatial • Basic prompt: “A real replica of the Escorial Monastery, located
visualization client in Madrid, Spain”.
• Specification of location and dimensions: "An exact replica of
the El Escorial Monastery located on the southern slope of
Mount Abantos at an altitude of 1,028 meters, covering an area

© 2025 The Author(s).
Proceedings published by Eurographics - The European Association for Computer Graphics.

<!-- p. 9 -->

Barbero-Álvarez et al. / 3D of CH Buildings based on GenAI & Geospatial Data 9 of 10

of 33,327 square meters. Its rectangular structure measures ap- [CNG∗22] COMES R., NEAM C., GREC C., BUNA Z., GAZDAC C.,
proximately 207 meters long by 161 meters wide, with towers MATEESCU-SUCIU L.: Digital reconstruction of fragmented cultural
heritage assets: The case study of the dacian embossed disk from pi- 55 meters high at each corner. The building has 15 cloisters, 86
atra ros, ie. Applied Sciences 12 (2022), 8131. doi:10.3390/
staircases, 1,200 doors and 2,673 windows." app12168131. 2
• Addition of external appearance details: “An exact replica of the
[dBGGCAM∗24] DEL BLANCO GARCÍA F. L., GONZÁLEZ CRUZ
Monastery of El Escorial, built with ashlars of yellowish gray A. J., AMENGUAL MENÉNDEZ C., SANZ ARAUZ D., AIRA ZUN-
granite extracted from the quarries of the Sierra de Guadarrama, ZUNEGUI J. R., PALMA CRESPO M., GARCÍA MORALES S.,
and covered by blue slate gable roofs, which faithfully reflect SÁNCHEZ-APARICIO L. J.: A unified virtual model for real-time visu-
its austere facade of straight lines and square windows without alization and diagnosis in architectural heritage conservation. Buildings
14, 11 (2024), 3396. doi:10.3390/buildings14113396. 2
moldings, topped by corner towers with slate and lead spires.”
• Combination of previous prompts: "Exact replica of El Escorial [DKS21] DENG X., KIM I. T., SHEN C.: Research on convolutional
neural network-based virtual reality platform framework for the intan-
Monastery located on Mount Abantos at 1,028 m altitude and
gible cultural heritage conservation of china hainan li nationality: Boat-
occupies 33,327 m². Its rectangular structure measures 207 m shaped house as an example. Mathematical Problems in Engineering
by 161 m, with 55 m towers at each corner. It has 15 cloisters, 2021 (2021), 5538434. doi:10.1155/2021/5538434. 2
86 stairways, 1,200 doors and 2,673 windows. Built with granite [DWS∗25] DING Z., WANG J., SONG Y., ZHENG X., HE G., CHEN
from the Sierra de Guadarrama, it has bluish slate roofs. Its aus- X., ZHANG T., LEE W.-J., SONG J.: Tracking the carbon foot-
tere facade, with straight lines and no moldings, is topped with print of global generative artificial intelligence. The Innovation 6,
corner towers with slate and lead spires." 5 (2025), 100866. URL: https://www.sciencedirect.com/
science/article/pii/S2666675825000694, doi:https:
• Specification 1 (Basilica): "Exact replica of The Basilica of the //doi.org/10.1016/j.xinn.2025.100866. 8
Escorial Monastery, with a central nave 84 meters long, 30 me-
[EMK21] ELABD N., MANSOUR Y., KHODIER L.: Utilizing innova-
ters wide and a similar height, it is distinguished by its imposing tive technologies to achieve resilience in heritage buildings preservation.
Renaissance facade of sober and geometric lines, built in stone Developing Built Environment 8 (2021), 100058. doi:10.1016/j.
and granite that combine gray tones with details in carved white. dibe.2021.100058. 2
With 1 tower with a vaulted roof finished in a spire in the center [FB20] FATIGUSO F., BULDO M.: Complesso della ss. trinità di venosa
of the central nave and 2 symmetrical towers on the sides with (pz). In La Diagnostica per Gli Edifici Storici: Metodi non Distruttivi
slate and lead spires." e Tecnologie Innovative per la Valutazione e il Controllo, DeFino M.,
• Specification 2 (Courtyard 1): “Exact replica of the quadrangular Fatiguso F., (Eds.), Collana Architettura Sostenibile/Culture Costruttive
per il Recupero Sostenibile. EdicomEdizioni, Monfalcone (GO), Italy,
courtyards of the Escorial Monastery, which have a cross-shaped 2020, pp. 169–180. 1
vault usually built in stone and granite, bluish slate roofs and
[HDP21] HONCHAR A., DOVGYI S., POPOVA M.: Ontological ap-
combining gray tones with carved white details, with 1 tower of proach to consolidation of 3d models of objects of historical and cultural
slate and lead spires in the middle of the cross.” heritage and gis. Radio Electronics and Computer Systems 1 (2021),
• Specification (Courtyard 2): “Exact replica of the Patio de los 81–91. 2
Mascarrones of the Escorial Monastery which, is quadrangular [JAEH25] JEGHAM N., ABDELATTI M., ELMOUBARKI L., HENDAWI
in shape, built in stone and granite, with bluish slate roofs and A.: How hungry is ai? benchmarking energy, water, and carbon footprint
combining gray tones with carved white details.” of llm inference, 2025. URL: https://arxiv.org/abs/2505.
09598, arXiv:2505.09598. 8

[Lum] LUMA AI: Luma labs — 3d capture, made easy. https://
References lumalabs.ai/. Accessed: 2024-04-01. 4

[22] Geospatial trends 2023: Opportunities for data.europa.eu. https: [LWX21] LI M., WANG Y., XU Y.-Q.: Computing for chinese cul-
//data.europa.eu/. Accessed: 2024-04-01. 2 tural heritage. Visual Informatics 6 (2021), 1–13. doi:10.1016/
j.visinf.2021.01.001. 1
[ABM21] ALSHAWABKEH Y., BAIK A., MIKY Y.: Integration of laser
scanner and photogrammetry for heritage bim enhancement. ISPRS [Mes] MESHY AI: Meshy — your ai assistant for 3d content creation.
International Journal of Geo-Information 10 (2021), 316. doi:10. https://www.meshy.ai/. Accessed: 2024-04-01. 3
3390/ijgi10050316. 1 [MST∗20] MILDENHALL B., SRINIVASAN P., TANCIK M., BARRON
[ACPG22] ALFIO V. S., COSTANTINO D., PEPE M., GAROFALO A. R.: J. T., RAMAMOORTHI R., NG R.: Nerf: Representing scenes as neu-
A geomatics approach in scan to fem process applied to cultural heritage ral radiance fields for view synthesis. In Computer Vision – ECCV 2020,
structure: The case study of the colossus of barletta. Remote Sensing 14 16th European Conference, Glasgow, UK, August 23–28, 2020, Proceed-
(2022), 664. doi:10.3390/rs14030664. 1 ings, Part I, vol. 12346 of Lecture Notes in Computer Science. Springer,
2020, pp. 405–421. doi:10.1007/978-3-030-58452-8_24. 2
[Cen] CENTRO NACIONAL DE INFORMACIÓN GEOGRÁFICA: Geoportal
oficial de la infraestructura de datos espaciales de españa. https:// [NSA∗19] NOOR S., SHAH L., ADIL M., GOHAR N., SAMAN G. E.,
idee.es/. Accessed: 2024-04-01. 2 JAMIL S., QAYUM F.: Modeling and representation of built cultural
heritage data using semantic web technologies and building informa-
[Ces] CESIUM: The platform for 3d geospatial. https://cesium.
tion model. Computational and Mathematical Organization Theory 25
com/. Accessed: 2024-04-01. 2
(2019), 247–270. doi:10.1007/s10588-018-09280-1. 2
[CKC∗18] CHATZISTAMATIS S., KALAITZIS P., CHAIDAS K.,
[QCAH21] QUINTILLA-CASTÁN M., AGUSTÍN-HERNÁNDEZ L.: 3d
CHATZITHEODOROU C., PAPADOPOULOU E., TATARIS G.,
survey and virtual reconstruction of heritage. the case study of the city
SOULAKELLIS N.: Fusion of tls and uav photogrammetry data
council and lonja of alcaniz. Vitruvio 6 (2021), 12–25. doi:10.4995/
for post-earthquake 3d modeling of a cultural heritage church. In
vitruvio-ijats.2021.16013. 1
International Archives of the Photogrammetry, Remote Sensing and
Spatial Information Sciences (2018), vol. XLII-3/W4, pp. 143–150. [rev] Autodesk revit. https://www.autodesk.com/es/
doi:10.5194/isprs-archives-XLII-3-W4-143-2018. 1 products/revit/overview. Accessed: 2025-07-03. 1

© 2025 The Author(s).
Proceedings published by Eurographics - The European Association for Computer Graphics.

<!-- p. 10 -->

10 of 10 Barbero-Álvarez et al. / 3D of CH Buildings based on GenAI & Geospatial Data

[rhi] Rhinoceros. https://www.rhino3d.com/es/. Accessed:
2025-07-03. 1

[RMFF20] ROCHA G., MATEUS L., FERNÁNDEZ J., FERREIRA V.:
A scan-to-bim methodology applied to heritage buildings. Heritage 3
(2020), 47–67. doi:10.3390/heritage3010004. 1
[RRN∗21] RADULESCU V. M., RADULESCU G. M. T., NAS S., RAD-
ULESCU A. T., BONDREA M., RADULESCU C. M.: Geoinformatics
technologies for preservation of cultural heritage, case study, rakoczi-
banffy castle, urmeni, bistria nasaud county, romania. Journal of Applied
Engineering Sciences 11 (2021), 41–48. 1
[SAdBGMC∗23] SÁNCHEZ APARICIO L. J., DEL BLANCO GAR-
CÍA F. L., MENCÍAS CARRIZOSA D., VILLANUEVA LLAURADÓ P.,
AIRA ZUNZUNEGUI J. R., SANZ ARAUZ D., GARCÍA GAGO J.: De-
tection of damage in heritage constructions based on 3d point clouds: A
systematic review. Journal of Building Engineering 77 (2023), 107440.
doi:10.1016/j.jobe.2023.107440. 1, 2
[SAMGA∗20] SÁNCHEZ-APARICIO L. J., MASCIOTTA M.-
G., GARCÍA-ALVAREZ J., RAMOS L. F., OLIVEIRA D. V.,
MARTÍN-JIMÉNEZ J. A., GONZÁLEZ-AGUILERA D., MON-
TEIRO P.: Web-gis approach to preventive conservation of her-
itage buildings. Automation in Construction 118 (2020), 103304.
doi:10.1016/j.autcon.2020.103304. 2

[SPMPL22] SKUBLEWSKA-PASZKOWSKA M., MILOSZ M.,
POWROZNIK P., LUKASIK E.: 3d technologies for intangible cultural
heritage preservation: literature review for selected databases. Heritage
Science 10 (2022), 3. doi:10.1186/s40494-021-00574-0. 1
[SRB∗20] SESTRAS P., ROS S., BILAS S., NAS S., BURU S. M.,
KOVACS L., SPALEVIC V., SESTRAS A. F.: Feasibility assess-
ments using unmanned aerial vehicle technology in heritage buildings:
Rehabilitation-restoration, spatial analysis and tourism potential analy-
sis. Sensors 20 (2020), 2054. doi:10.3390/s20072054. 1

[Ton19] TONG Z. L. W.: Application of oblique photography and gis
technologies in the integrated conservation and development of historic
cities in china: Practices in shigatse, tibet and quanzhou (zayton), fujian.
In International Archives of the Photogrammetry, Remote Sensing and
Spatial Information Sciences (2019), vol. XLII, pp. 1203–1208. 1

© 2025 The Author(s).
Proceedings published by Eurographics - The European Association for Computer Graphics.
