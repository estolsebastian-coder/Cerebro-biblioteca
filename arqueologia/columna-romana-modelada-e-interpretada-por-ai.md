---
type: libro
title: "Columna romana modelada e interpretada por AI"
author: ""
categoria: "Arqueología"
paginas: 8
extraccion: "texto"
fuente: "local:E:/DISCIPLINAS, TEXTOS Y MAPAS/Biblioteca digital/Arqueología/Columna romana modelada e interpretada por AI.pdf"
convertido: 2026-10-12
---

# Columna romana modelada e interpretada por AI

> Texto extraído de `Arqueología/Columna romana modelada e interpretada por AI.pdf` (8 páginas, texto). El PDF original está en el disco E: (DISCIPLINAS, TEXTOS Y MAPAS\Biblioteca digital); `<!-- p. N -->` marca el inicio de cada página.

<!-- p. 1 -->

ISPRS Annals of the Photogrammetry, Remote Sensing and Spatial Information Sciences, Volume X-M-2-2025
30th CIPA Symposium “Heritage Conservation from Bits:
From Digital Documentation to Data-driven Heritage Conservation”, 25–29 August 2025, Seoul, Republic of Korea

A Roman Carved Tale Modelled in 3D and Interpreted with AI

Gabriele Mazzacca1,2 , Andrea Sterpin3,4, Simone Rigon1, Marco Medici3, Fabio Remondino1

1 3D Optical Metrology (3DOM) unit, Bruno Kessler Foundation (FBK), Trento, Italy – (gmazzacca, srigon, remondino)@fbk.eu
2 Dept. Mathematics, Computer Science and Physics, University of Udine, Italy
3 INCEPTION, Spinoff of the University of Ferrara, Italy – marco.medici@inceptionspinoff.com
4 Department of Architecture, University of Ferrara, Italy – andrea.sterpin@unife.it

Keywords: Photogrammetry, 3D Modelling, Semantic Segmentation, Multimodal Large Language Models.

Abstract
This study proposes an innovative methodology for documenting and semantically analysing cultural heritage by integrating
artificial intelligence (AI) with a photogrammetric 3D model. The case study is the Trajan’s Column in Rome, a monumental
structure adorned with a continuous helical relief depicting Emperor Trajan’s Dacian campaigns. AI-driven semantic
segmentation is used to identify key elements (such as human figures, battle scenes and natural motifs) within the digitised
sculptural narrative. Starting from a high-resolution photogrammetric 3D model, the column’s texture is divided into multiple
segments and a multimodal large language model (MLLM) is applied to produce context-aware segmentation masks via natural
language prompts. Results are then projected onto the 3D geometry and visualised through a web-based 3D viewer.

b)

a) c)
Figure 1. The Trajan’s column in Rome, ca 44 m height, located within the forum (a; source: National Geographic); close-up of
the tale which commemorate Traian's win against the Dacian (b); MLLM-based identification of the Emperor Trajan (repeated 58
times) within the 200 m long carved frieze (c).

\1. Introduction its shaft. As highlighted by Hölscher (2004) and Conti and Moffa
(2022), the frieze of Trajan’s Column functions as a monumental
In recent years, 3D documentation of Cultural Heritage scenarios semantic system: a complex compositional narrative that projects
has been democratised with reliable, efficient and automated the symbolic power of imperial triumph into stone, combining
procedures based on image or range data, acquired from ground historical accuracy and evocative strength in a form of immersive
or UAV platforms (Remondino, 2011; Remondino et al., 2017; 3D storytelling.
Stathopoulou et al., 2019; Farella et al., 2022). However, This iconic carved narrative serves as a compelling case study for
automatic semantic enrichment and analysis of such 3D models testing the capabilities of the proposed segmentation approach.
remain an open challenge. Augmenting 3D data with qualitative Nevertheless, the intricate compositional layout, stylised figures
information is crucial for enhancing its accessibility and usability, and scenes, monochromatic surfaces, and visible erosion make
yet this task has posed significant difficulties for years (De Luca, the automated semantic segmentation particularly challenging.
2013; Maietti et al., 2018; Yang et al., 2023). Cultural heritage
assets, with their complex geometries, material diversity, and 1.1 Paper’s aim
stylistic variability, present significant challenges for recently
developed artificial intelligence (AI) solutions for semantic The work presents the 3D documentation of the Trajan's Column
in Rome and its interactive analysis through a multimodal largesegmentation.
language model (MLLM). The paper will examine the followingThis paper focuses on the emerging opportunities offered by
innovative aspects of this work:multimodal large language models (MLLMs), which leverage
natural language and zero-shot learning strategies. The proposed • the complex 3D survey of the Column;
method uses photogrammetrically derived mesh textures as input • an automated methodology to unwrap the 3D column and
for the AI-based semantic segmentation process. derive high-resolution orthoimages of the carved frieze;
To validate the proposed workflow, the study focuses on the • a zero-shot referring image segmentation process that uses a
Trajan’s Column, an iconic monument in the Imperial Fora of natural language-driven querying interface, requires no
Rome, renowned for the helical frieze that encircles and adorns specific retraining, and is capable of interpreting, identifying,

This contribution has been peer-reviewed. The double-blind peer-review was conducted on the basis of the full paper.
https://doi.org/10.5194/isprs-annals-X-M-2-2025-253-2025 | © Author(s) 2025. CC BY 4.0 License. 253

<!-- p. 2 -->

ISPRS Annals of the Photogrammetry, Remote Sensing and Spatial Information Sciences, Volume X-M-2-2025
30th CIPA Symposium “Heritage Conservation from Bits:
From Digital Documentation to Data-driven Heritage Conservation”, 25–29 August 2025, Seoul, Republic of Korea

and segmenting scenes, characters, and anthropic or natural foundation models. First attempts were done by Reby et al.
elements within the carved narrative; (2023) combining Segment Anything (SAM) (Kirillov et al.,
• an online 3D viewer for interactive access to the results. 2023), Grounding Dino (Liu et al. 2024) and CLIP (Radford et
Compared to other works that have coupled AI foundation al., 2021) to perform low-level characterisation of building
models to perform segmentation of low-level heritage classes objects. More recently, the rise of Multi-modal Large Language
(Reby et al., 2023), our approach relies solely on recent MLLM Models (MLLMs) has allowed more complex image scenefoundation models to tackle complex semantic segmentation understanding tasks using natural language inputs (Fei et al.,
tasks that require advanced image and text understanding as well 2024; Yan et al., 2024; Zhang et al., 2024). One of these tasks,
as interpretative capabilities. known as referring image segmentation (RIS), allows a user
to describe the target object for segmentation through the means
\2. Related works of descriptive textual inputs (“prompts”). This is a highly
desirable feature in the cultural heritage field because it leverages
The semantic enrichment of 2D and 3D digital heritage data experts’ core knowledge to generate precise prompts that produce
fundamentally improves their interpretative potential and meaningful segmentation results.
usability, enabling more nuanced documentation, analytical
processes and visualisations (Poux et al., 2017; Teruggi et al., 3. The Trajan’s Column in Rome
2021). For years, authors have presented manual and interactive
frameworks to represent 3D heritage structures based on their Erected in 113 AD at the centre of Trajan’s forum, the column is
morphological description and constituent elements (Attene et al., widely regarded as one of the most sophisticated expressions of
2007; Manferdini et al., 2008; Serna et al., 2012; De Luca et al., Roman imperial visual culture and rhetoric (Beard, 2007).
2013). Commissioned by Emperor Trajan to commemorate the Dacian
The semantic segmentation of 2D images has been a subject of wars (101-102 and 105-106 AD), it stands as a masterpiece of
research for many years, from the early classical methods based ancient engineering and sculptural narrative, serving for
on pixel-level features and graph-based algorithms (Boykov and centuries as a monument of historical memory (Beard, 2007;
Jolly, 2001) to the first deep learning approaches, such as Coarelli, 2000). With an overall height of approximately 44
AlexNet model, which demonstrated unprecedented performance meters (including a 6.3 m for the base, 0.8 m for the pedestal,
on the largest image dataset of the time, ImageNet (Krizhevsky 26.6 m for the shaft, 1.5 m for the platform, 4.7 m for the capital
et al., 2012). Then, the introduction of convolutional neural block and a 4.2 m statue on the top), the column is composed of
networks revolutionised the field, enabling end-to-end 17 blocks of Luna marble enclosing a helical staircase lit by small
segmentation without the need for manually designed low-level slit windows. Its most celebrated feature is the spiralling frieze,
features. Long et al. (2015) introduced Fully Convolutional stretching over 200 meters in length and depicting more than
Networks for entire images, preparing the arrival of subsequent 2,500 carved figures. The carved narrative sequence reports
models such as U-Net (Ronneberger et al., 2015) and Mask R- scenes of marches, battles, military councils, rituals and
CNN (He et al., 2017), which are now fundamental for the construction phases, distinguished by naturalism, iconographic
segmentation of complex images. richness and refined compositional structure. The visual
The last decade has seen significant progress in 3D semantic progression is organised along hierarchical and perspectival lines,
segmentation of point clouds. Early efforts employed traditional guiding the viewer’s gaze upward along the shaft. To read the
machine learning methods (Weinmann et al., 2015; Grilli et al., entire story, a viewer would have to move 23 times around the
2019), but researchers have increasingly investigated deep column. Trajan himself appears nearly 60 times in commanding
learning approaches (Matrone et al., 2020a,b). PointNet and positions, embodying the idealised figure of the Roman princepsPointNet++ (Qi et al., 2017a, 2017b) pioneered this transition, strategist, legislator and guarantor of order. Beyond its
and subsequent models, such as PointCNN (Li et al., 2018), celebratory function, the column serves as a vital historical
KPConv (Thomas et al., 2019), Point Transformer (Zhao et al., source, offering insight into Roman military logistics, Dacian
\2021) and Super Point Transformer (Robert et al., 2023), have ethnography, construction techniques, and imperial iconography
further expanded the capabilities of 3D semantic segmentation (Lepper and Frere, 1988; Coarelli, 2000; Hölscher, 2004).
techniques. Due to its elaborate formal and narrative structure, as well as its
A third option, involving the integration of 2D and 3D complex material characteristics, the Trajan's Column is a
methodologies, has also seen a great deal of research in the last representative case study for testing advanced digital approaches
years, with two main types of approaches tested. The first for scene understanding in cultural heritage documentation and
employs deep learning techniques on high-resolution images valorisation.
obtained from photogrammetric surveys, to then accurately
reproject inferences onto the corresponding 3D point clouds by 4. Methodology
leveraging known camera orientations (Bassier et al. 2024). The
second focuses on the direct semantic segmentation of textured 4.1 3D surveying and modelling
3D meshes, generating UV maps from the textured 3D model, The geometric survey of the column and its surroundings was
training segmentation algorithms to identify semantic classes first conducted using a multi-sensor approach, combining
within the texture space and then mapping back the segmented terrestrial laser scanning (TLS) with photogrammetric
texture onto the 3D meshes (Grilli et al., 2018; Grilli and techniques. The TLS acquisition was performed with a Leica
Remondino, 2019). P40, acquiring a total of 21 scan positions, which are
The connection between the 2D and 3D world opens up the subsequently aligned through iterative closest point (ICP)
possibility to leverage the most recent advancements in the registration. The pairwise registration yielded a RMSE of 6.7
Computer Vision field. Specifically, the employment of recent mm, with a standard deviation of 0.64 mm across the scan pairs,
foundation models (i.e. large deep learning models trained on indicating internal consistency and stability within the alignment
massive amounts of data) is used to accomplish a wide variety of network. Given the instrumental specifications of the Leica P40
functions. Nevertheless, the use of foundation models in digital - declaring a typical ranging error of 3 mm at 50 meters - the
heritage remains limited due to the peculiarity of the subject, achieved alignment results are well within the expected precision
which is often very different from the data used to train these range of the device, supporting the reliability of the TLS dataset

This contribution has been peer-reviewed. The double-blind peer-review was conducted on the basis of the full paper.
https://doi.org/10.5194/isprs-annals-X-M-2-2025-253-2025 | © Author(s) 2025. CC BY 4.0 License. 254

<!-- p. 3 -->

ISPRS Annals of the Photogrammetry, Remote Sensing and Spatial Information Sciences, Volume X-M-2-2025
30th CIPA Symposium “Heritage Conservation from Bits:
From Digital Documentation to Data-driven Heritage Conservation”, 25–29 August 2025, Seoul, Republic of Korea

as the primary geometric constraint for the photogrammetric The dense image matching process on the Column generated a
process. In fact, given the ongoing underground works of the coloured dense point cloud of approximately 117 million points,
metro line below the archaeological area, TLS is adopted as the providing additional radiometric detail complementary to the
primary surveying method instead of a traditional network of TLS geometry. As the used checkpoints (13) revealed a quite
fixed topographic points. TLS acquisition, indeed, provides a high RMSE within the bundle adjustment, the photogrammetric
dense and redundant geometric dataset, enabling the selection a and TLS point clouds are further aligned using an ICP approach.
posteriori of architectural features for the photogrammetric The cloud-to-cloud distance between the two datasets resulted in
alignment and control. The final TLS point cloud has a mean distance of 5mm (Figure 4c), which is considered a
approximately 307 mil. points with an average sampling distance satisfactory metric given the size of the Column.
of 2 mm (Figure 2).

b)

c)

d)

Figure 2. TLS point cloud of the surveyed area (ca 50x50m).

The photogrammetric survey was performed with both terrestrial
and drone images (Table 1), acquired ca 2-3 weeks after the TLS.

e)
Camera Resol. Focal # Min/Max
img GSD (*)
ground Sony Alpha 7 33 Mpx 24-105 801 1-3 mm
IV mm
drone DJI Mavic 20 Mpx 24 mm 1485 0.75-2
3M mm
Table 1. Specifications of the terrestrial and aerial a) f)
photogrammetric data (* on the Column). Figure 4. Textured photogrammetric 3D model (a) with close-
up views on the carved frieze and tale (b, c, d, e) with and
The photogrammetric adjustment integrated both image sets without texture. Cloud-to-cloud comparison of the TLS and
(Figure 3, Table 2), with image orientation and scaling photogrammetric surveys (f).
constrained through a set of homologous points identified
between the TLS point cloud and the photogrammetric images. A high-resolution mesh model is then derived from the dense
point cloud, containing around 20 million faces. This model is
RMSE on Check Points 8.6 mm textured with 12 high-resolution texture maps (8192x8192
Avg redundancy 9.17 pixels), featuring a resolution of 1 mm/pix and enabling detailed
Mean reprojection error 1.19 px visual analysis of the monument’s sculptural elements (Figure 4).
Avg. observation per image 6350
Table 2. Bundle adjustment metrics.

a) b) c)
Figure 3. Different views of the recovered camera poses and sparse point cloud of the Column and its surrounding.

This contribution has been peer-reviewed. The double-blind peer-review was conducted on the basis of the full paper.
https://doi.org/10.5194/isprs-annals-X-M-2-2025-253-2025 | © Author(s) 2025. CC BY 4.0 License. 255

<!-- p. 4 -->

ISPRS Annals of the Photogrammetry, Remote Sensing and Spatial Information Sciences, Volume X-M-2-2025
30th CIPA Symposium “Heritage Conservation from Bits:
From Digital Documentation to Data-driven Heritage Conservation”, 25–29 August 2025, Seoul, Republic of Korea

4.2 3D model simplification additional polylines, derived from the cornice, marking the lower
and upper edges of the sculptural register. This polyline triplet is
In addition to the comprehensive 3D documentation of the essential to accurately capture both the unfolding trajectory of the
Column, the development of an AI-assisted tool for the relief and its vertical extent, providing a stable geometric
interpretation of the carved frieze required a structured approach framework for mesh simplification.
to data preparation. Two key processing stages are identified as A lofting operation is indeed performed between the curves of
essential to achieve this objective: (i) the discretisation of the each group, resulting in the 26 meshes that comprise the
frieze into a continuous, ribbon-like structure, guided by the simplified wrapped model of the shaft. The use of these three
visual segmentation naturally suggested by the cornice that curves allowed the creation of ribbon-like mesh segments that
separates the sculptural registers; (ii) the optimisation of the maintain topological consistency across the model, ensuring
model’s geometric and textural components to enable efficient seamless alignment between adjacent areas as neighbouring
AI-based querying, analysis, and visualization. meshes share common borders.
The high-resolution textured 3D model is processed to generate This structure also enabled the generation of both a wrapped
a simplified mesh representation of the column shaft. This is (cylindrical) and an unwrapped (planar) version of the model,
achieved through the subdivision of the model into smaller, supporting flexible applications in visualisation, texture mapping,
logically organised segments via parametric scripting and AI-driven analysis.
(Rhinoceros3D + Grasshopper), producing both a cylindrical To preserve dimensional coherence between the two
(wrapped) configuration and a corresponding planar configurations, the central helical polyline served as the primary
(unwrapped) version. Simplified geometries are essential to reference during the unwrapping process. Its segments are
reduce computational complexity, while smaller mesh segments reoriented onto a vertical plane, maintaining their original lengths,
facilitate the handling of high-resolution textures during both while the lower and upper polylines are adjusted accordingly to
generation and AI-based processing. fit the transformed layout. This approach ensured that the
A crucial step in this workflow is the extraction of a guiding simplified mesh retained the proportions and spatial logic of the
polyline along the neutral axis of the cornice, which served as a original column, despite its geometric complexity.
geometric reference for segmentation. This polyline is derived
through a surface analysis based on local covariance features - a) b)
linearity, planarity, surface variation, and omnivariance -
ensuring precise alignment with the central trajectory of the
sculptural frieze (Figure 5).

Linearity Surf. Planarity Omnivariance
variation

Figure 6. The cylinder split into 26 ribbons (a). Subdivision of
textures into multiple overlapping tiles for semantic
segmentation (b).

4.3 UV mapping, texturing and surface remeshing

Using the 26 ribbons created as described above, an automated
Figure 5. Covariance features at various radii (top) used to pipeline is developed within SideFX Houdini to extract both
extract the polyline (bottom) delimiting the tale along the chromatic and geometric information from the photogrammetric
Column. textured mesh and allows for their reprojection onto the
simplified (wrapped and unwrapped) mesh counterparts with the
As a first step, an approximate cylindrical surface is generated by goal of reconstructing the monument’s original details.
lofting a series of circular sections with varying diameters, The process began with the computation of UV coordinates on
spaced at regular 1-meter intervals along the shaft. This surface the simplified wrapped ribbons. Using these coordinates and
provides a geometric reference for the frieze's development. Then, taking the photogrammetric textured mesh as input, texture maps
a helical curve with a constant pitch is created following the are generated through baking operations. These included diffuse,
frieze’s central path. Both the central path curve and the cornice ambient occlusion, curvature, and normal maps.
polyline are segmented into 26 polylines using a vertical plane The UV coordinates derived from the wrapped configuration are
aligned with the column’s longitudinal axis (Figure 6a). then transferred to the unwrapped segments, ensuring a
Within each of the 26 segments, a group of three reference consistent spatial correspondence between the two versions of the
polylines is defined to guide the surface generation: the central shaft. This transfer is made possible by the similar topological
helical one, representing the main path of the frieze, and two base structure shared by both configurations, as established

This contribution has been peer-reviewed. The double-blind peer-review was conducted on the basis of the full paper.
https://doi.org/10.5194/isprs-annals-X-M-2-2025-253-2025 | © Author(s) 2025. CC BY 4.0 License. 256

<!-- p. 5 -->

ISPRS Annals of the Photogrammetry, Remote Sensing and Spatial Information Sciences, Volume X-M-2-2025
30th CIPA Symposium “Heritage Conservation from Bits:
From Digital Documentation to Data-driven Heritage Conservation”, 25–29 August 2025, Seoul, Republic of Korea

through their generation process outlined in Section 4.2. validated by a human operator to remove erroneous segmentation.
Subsequently, each wrapped segment undergoes a remeshing The segmented images are then reassembled into the original 26
phase aimed at achieving a denser and more uniform distribution ribbons for being visualised on the wrapped and unwrapped
of vertices, thereby enhancing the mesh’s potential for local meshes of the 3D model.
detail representation. For each newly generated vertex, the
distance from the original surface is calculated and stored as a 5. Segmentation and visualisation results
geometric attribute. Then the spatial data is transferred from the
wrapped to the unwrapped geometry by leveraging the shared 5.1 Quantitative analysis
UV layout. The depth of the meshes is then reconstructed,
preserving the original geometric features. A subset of the predicted images (6) is used for deriving some
In preparation for the AI-based segmentation described in metrics to evaluate the performance of the MLLM-based
Section 4.4, the images are further processed to aid the model in segmentation method. For each target object, the prediction is
its task by increasing the visibility of contours and critical details. compared with a corresponding mask annotated by an expert user.
As the column is made of a single material and presents limited To evaluate the outcome of the segmentation pipeline, common
radiometric information, the diffuse map is blended with the Machine Learning metrics are used:
𝑇𝑝
curvature map to combine the subtle detail cues highlighted by 𝑃𝑟𝑒𝑐𝑖𝑠𝑖𝑜𝑛=
the shadows in the diffuse map with the geometric features of the 𝑇𝑝+ 𝐹𝑝 𝑇𝑝
frieze, such as edges and creases, emphasised by the curvature 𝑅𝑒𝑐𝑎𝑙𝑙=
𝑇𝑝+ 𝐹𝑛map. Since the variation of the curvature is more significant than
the absolute depth alone for identifying the contours, the use of 𝐹1 𝑠𝑐𝑜𝑟𝑒= 2 ∗𝑅𝑒𝑐𝑎𝑙𝑙∗𝑃𝑟𝑒𝑐𝑖𝑠𝑖𝑜𝑛 𝑅𝑒𝑐𝑎𝑙𝑙+ 𝑃𝑟𝑒𝑐𝑖𝑠𝑖𝑜𝑛
the depth map was not considered necessary. 𝑇𝑝
The hybrid images are then subdivided into 1152 tiles of 640×640 𝐼𝑜𝑈= 𝑇𝑝+ 𝐹𝑝+ 𝐹𝑛
pixels (Figure 6b) to feed to the MLLM model. This specific tile
size is deemed optimal in our specific case because it offers a where, for each considered class, Tp (true positive), 𝑇𝑛 (true
good balance between image detail and manageable data size, but negative), Fp (false positive), and Fn (false negative) come from
working with higher resolution images may produce different the computed Confusion Matrix. All metrics, reported in Table 3,
results. Each tile has an 80% overlap with the adjacent ones to are the averages of the metrics calculated for each class on each
reach a good contextual understanding of the scene and to avoid image.
excessive straight cuts. Since the original hybrid images have
variable dimensions due to the shape of the frieze, particularly in
length, the number of tiles generated per image differs
accordingly. Some images produce only fifteen tiles, while others, %
being longer, require fifty or more to ensure full coverage. People Trajan Battle scenes Roman military Emperor standards VegetationBecause tiles overlap by 80%, each pixel is predicted five times
in the final image; a threshold-based vote is then applied to select Precision 79.09 89.66 45.26 79.28 92.13
the final pixel value and generate the final masked images. Recall 87.71 87.33 47.71 80.70 58.19
F1 Score 82.07 88.44 46.34 79.84 63.02
4.4 AI semantic segmentation IoU 69.78 83.39 43.41 77.07 53.22
Table 3. Per-class metrics for the MLLM-based segmentationsAmong the methods able to perform referring image
(visual in Figure 7).segmentation (RIS), Sa2VA (Yuan et al., 2025) is employed:
Sa2VA is a multi‑modal large language model able to segment a
5.2 Qualitative analysisspecific object in an image or video based on an input linguistic
query (“prompt”). Sa2VA combines SAM‑2 (Ravi et al., 2024),
The segmentation results across all five classes (people, Emperora foundational video segmentation engine, with LLaVA (Li et al.,
Trajan, battle scenes, Roman military standards, and vegetation),2024), a state‑of‑the‑art vision language model. In our pipeline,
while occasionally incomplete, often provided meaningfulwe handcrafted “instruction tokens” to generate segmentation
semantic insights, especially considering the complexity of themasks for the interpretation of the Column. According to the
scenes (Figure 7).carved narrative explored above, five distinct semantic classes
The prediction of the class people is generally correct, especiallyare identified on the frieze: people, Emperor Trajan, battle
in scenes with clearly defined human figures. Despite somescenes, Roman military standards, and vegetation. Each of these
inconsistencies, such as the inclusion of shields in some instancestarget classes is chosen because it requires high levels of scene
and their exclusion in others, Roman soldiers are correctlyunderstanding, and each prompt is designed to describe the main
identified and segmented. This suggests that more precise promptcharacteristics of each class. While the classes people, Roman
phrasing, particularly concerning the description of weapons,military standards, and vegetation are mainly discernible by their
could yield more consistent results. Inconsistencies due to partialgeometric and physical characteristics, the segmentation of battle
or over-segmentation can also be seen in other instances,sequences and Emperor Trajan is based on the interpretation of
probably due to occlusion problems (human figures hidden bydynamic cues, such as gestures and group interactions, not just
other objects in the scene) or lack of crisp contours, determinedphysical appearance, and allow us to test the MLLM model
by the damaged eroded surface of the frieze in that area. Finally,capabilities to successfully process highly interpretational
over-segmentation of human figures by including nearby animals.queries. Classes requiring very specific domain knowledge, but
For the Emperor Trajan class, the segmentation proved to beof potential heritage interest nonetheless, are excluded from the
particularly challenging. The Emperor's depiction in the frieze iscurrent study because the model lacks specific heritage-based
not consistently clear, often blending with other figures, makingtraining.
it difficult to distinguish even for the expert human eye. TheAfter the prompt designing phase, the generated 1152 image tiles
MLLM had to identify Trajan as a subcategory within the broaderare queried to perform the inference of the target classes. For
people class. Despite a detailed prompt (“short and cropped hair,every tile, a query per class is performed, and the results are

This contribution has been peer-reviewed. The double-blind peer-review was conducted on the basis of the full paper.
https://doi.org/10.5194/isprs-annals-X-M-2-2025-253-2025 | © Author(s) 2025. CC BY 4.0 License. 257

<!-- p. 6 -->

ISPRS Annals of the Photogrammetry, Remote Sensing and Spatial Information Sciences, Volume X-M-2-2025
30th CIPA Symposium “Heritage Conservation from Bits:
From Digital Documentation to Data-driven Heritage Conservation”, 25–29 August 2025, Seoul, Republic of Korea

no beard, no helmet, no laminar armour, wearing a long, pleated The Roman military standards category features small
tunic that reaches his knees and a cloak draped over his shoulders dimensions of the emblems, morphological resemblance to other
and across one of his arms...”), some partial and incorrect vertical elements (such as limbs or branches) and occasional
classifications or clear misidentifications in more ambiguous surface erosion. Nonetheless, the segmentation results are
contexts are present. generally satisfactory, despite errors due to partial occlusions,
The battle scenes class yielded the highest number of erosions or crowded areas.
segmentation errors. Given the stylised and dynamic nature of The vegetation class, though stylised and often depicted in the
combat illustrations, character postures and contextual elements background, is segmented with generally positive results. Trees
often led to confusion. Missing or false positive detections are and branches are correctly identified in many instances, though
present in the results, e.g. in scenes depicting troops in motion partial or incorrect segmentations are also observed.
but without explicit combat cues.

correct segmentation (a) partial / missing segmentation (b) over- / wrong-segmentation (c)

People

Trajan
Emperor

scenes
Battle

standards
military
Roman

Vegetation

Figure 7. Visual results of the MLLM-based segmentation of the frieze’s texture for the selected classes. Metrics in Table 3.

This contribution has been peer-reviewed. The double-blind peer-review was conducted on the basis of the full paper.
https://doi.org/10.5194/isprs-annals-X-M-2-2025-253-2025 | © Author(s) 2025. CC BY 4.0 License. 258

<!-- p. 7 -->

ISPRS Annals of the Photogrammetry, Remote Sensing and Spatial Information Sciences, Volume X-M-2-2025
30th CIPA Symposium “Heritage Conservation from Bits:
From Digital Documentation to Data-driven Heritage Conservation”, 25–29 August 2025, Seoul, Republic of Korea

Nevertheless, achieved results point to clear opportunities for
further refinement, which would require extending beyond a pure
zero-shot approach. Introducing a small set of manually
segmented examples could indeed adapt the model to the unique
visual and semantic features of ancient friezes, improving its
sensitivity to carved contours, symbolic motifs, and stylistic
conventions. Moreover, adding structured historical or
iconographic information - such as figure roles, attributes, or
scene hierarchies - would support clearer semantic
disambiguation and more consistent labelling across complex
scenes.
In conclusion, the complete workflow - from 3D data acquisition
to automated texture generation and zero-shot AI-based
segmentation - demonstrates a scalable and adaptable pipeline for
digital heritage documentation and analysis. By further refining
the AI methods integrating domain-specific training and
contextual data, the reported workflow can be replicated and
reused across a broad range of decorated 3D artefacts: spiral
columns, sarcophagi, temple reliefs, narrative friezes, or any
context where figurative content is distributed on curved or
morphologically complex surfaces. To maximise accessibility
and scholarly reuse, the segmentation results are also being
deployed through an interactive web-based 3D viewer (Figure 8)
developed with Three.js, supporting detailed exploration,
annotation, and cross-disciplinary collaboration.

Acknowledgments

The data acquisition in Rome was carried out by INCEPTION
s.r.l. as part of the works of Cooperativa Archeologia,
commissioned by Metro C and authorized by Roma
Metropolitane.

References

Attene M., Robbiano F., Spagnuolo M., Falcidieno B., 2007.
Semantic Annotation of 3D surface meshes based on feature
Figure 8. Interactive online viewer displaying the wrapped characterisation. Lecture Notes in Computer Science, Vol. 4816, pp.
(top) and unwrapped (bottom) 3D model of Trajan’s Column 126-139.
with segmentation results for the people class.
Bassier, M., Mazzacca, G., Battisti, R., Malek, S., Remondino, F.,
\6. Conclusions 2024. Combining image and point cloud segmentation to improve
heritage understanding. ISPRS Int. Arch. Photogramm. Remote Sens.
This study shows that semantic segmentation of complex 3D Spatial Inf. Sci., XLVIII-2/W4-2024, 49-56.
heritage models, guided by natural language and enabled by Beard, M., 2007: The Roman Triumph. Harvard University Press,
multimodal large language models (MLLMs) in a zero-shot Cambridge, MA and London, England.
configuration, is technically feasible and produces meaningful
results without domain-specific training or manual annotations. Boykov, Y., Jolly, M.-P., 2001. Interactive graph cuts for optimal
Despite promising outcomes, some limitations persist due to the boundary & region segmentation of objects in N-D images. In: Proc.
domain representation gap in existing foundation models and the ICCV, 105-112.
iconographic complexity of the heritage case study” Coarelli, F., 2000. The Column of Trajan. Colombo, Roma.
• Limited domain representation: cultural heritage, especially
ancient sculpture, is poorly covered in most training datasets, Conti, C., Moffa, F., 2022. Lectures on Trajan’s Column and its
Architect Apollodorus of Damascus. In “L'Erma di Bretschneider”. making it challenging for models to process textures that are
monochromatic, stylised, or eroded - very different from De Luca, L., Busayarat, C., Stefani, C., Veron, P., Florenzano, M.,
typical modern training images. 2013. A semantic-based platform for the digital analysis of the
• Iconographic complexity: figures are often occluded, architectural heritage. Computers & Graphics, Vol. 35(2).
overlapping, ruined by the time or shown in non-standard
De Luca, L., 2013. 3D Modelling and Semantic Enrichment in
perspectives, which complicates automatic recognition. Cultural Heritage. Proc. Photogrammetric Week, pp. 323-333.
Semantic boundaries can appear fragmented or ambiguous,
with errors even in non-eroded and clearly legible areas. Farella, E.M., Morelli, L., Rigon, S., Grilli, E., Remondino, F.,
• Fragmented context: the frieze’s length required generating 2022. Analysing Key Steps of the Photogrammetric Pipeline for
more than 1000 texture tiles. Even with overlapping tiles and a Museum Artefacts 3D Digitisation. Sustainability, 14, 5740.
voting mechanism, the system analyses only partial scenes at a Fei, H., Wu, S., Zhang, H., Chua, T. S., & Yan, S., 2024. Vitron: A
time, limiting its ability to recognise relationships between unified pixel-level vision LLM for understanding, generating,
adjacent figures. This affects semantic coherence but the segmenting, editing. Proc. NeurIPS.
workflow still performs robustly under these constraints.

This contribution has been peer-reviewed. The double-blind peer-review was conducted on the basis of the full paper.
https://doi.org/10.5194/isprs-annals-X-M-2-2025-253-2025 | © Author(s) 2025. CC BY 4.0 License. 259

<!-- p. 8 -->

ISPRS Annals of the Photogrammetry, Remote Sensing and Spatial Information Sciences, Volume X-M-2-2025
30th CIPA Symposium “Heritage Conservation from Bits:
From Digital Documentation to Data-driven Heritage Conservation”, 25–29 August 2025, Seoul, Republic of Korea

Grilli, E., Dininno, D., Petrucci, G., and Remondino, F., 2018. From Qi, C.R., Yi, L., Su, H., Guibas, L.J., 2017b. PointNet++: Deep
2D to 3D supervised segmentation and classification for cultural hierarchical feature learning on point sets in a metric space. Advances
heritage applications, Int. Arch. Photogramm. Remote Sens. Spatial in Neural Information Processing Systems, 5105-5114.
Inf. Sci., XLII-2, 399-406.
Radford, A., Kim, J. W., Hallacy, C., Ramesh, A., Goh, G., Agarwal,
Grilli, E., & Remondino, F., 2019. Classification of 3D Digital S., ... & Sutskever, I., 2021. Learning transferable visual models from
Heritage. Remote Sensing, 11(7), 847. natural language supervision. Proc. ICML, pp. 8748-8763.

Grilli, E., Farella, E. M., Torresani, A., Remondino, F. 2019. Ravi, N., Gabeur, V., Hu, Y. T., Hu, R., Ryali, C., Ma, T., ... &
Geometric features analysis for the classification of cultural heritage Feichtenhofer, C., 2024. SAM2: Segment anything in images and
point clouds. ISPRS Int. Arch. Photogramm. Remote Sens. Spatial videos. arXiv preprint arXiv:2408.00714.
Inf. Sci., Vol. 42, 541-548.
Réby, K., Guilhelm, A., & De Luca, L. 2023. Semantic segmentation
He, K., Gkioxari, G., Dollár, P., Girshick, R., 2017. Mask R-CNN. using foundation models for cultural heritage: An experimental study
Proc. ICCV, 2961–2969. on Notre-Dame de Paris. Proc. ICCV, pp. 1689-1697.

Hölscher, T., 2004. The Language of Images in Roman Art. Remondino, F., 2011. Heritage Recording and 3D Modeling with
Cambridge University Press, Cambridge. Photogrammetry and 3D Scanning. Remote Sensing, 3(6), pp. 1104-
\1138.
Kirillov, A., Mintun, E., Ravi, N., Mao, H., Rolland, C., Gustafson,
L., & Girshick, R. 2023. Segment anything. Proc. ICCV, pp. 4015- Remondino, F., Nocerino, E., Toschi, I., Menna, F., 2017. A critical
\4026. review of automated photogrammetric processing of large datasets.
ISPRS Int. Arch. Photogramm. Remote Sens. Spatial Inf. Sci., Vol.
Krizhevsky, A., Sutskever, I., Hinton, G., 2012. ImageNet XLII-2/W5, pp. 591-599.
classification with deep Convolutional Neural Networks. Proc.
NeurIPS. Robert, D., Raguet, H., & Landrieu, L., 2023. Efficient 3D semantic
segmentation with superpoint transformer. Proc. ICCV.
Lepper, F., Frere, S., 1988. Trajan’s Column: A New Edition of the
Cichorius Plates. Alan Sutton Publishing, Gloucester. Ronneberger, O., Fischer, P., Brox, T., 2015. U-Net: Convolutional
networks for biomedical image segmentation. Proc. MICCAI.
Li, B., Zhang, Y., Guo, D., Zhang, R., Li, F., Zhang, H., Zhang, K.,
Li, Y., Liu, Z., Li, C., 2024. LLaVA-onevision: Easy visual task Secord, J., & Zakhor, A., 2007. Tree detection in urban regions using
transfer. arXiv preprint arXiv:2408.03326. aerial lidar and image data. IEEE Geoscience and Remote Sensing
Letters, 4(2), 196-200.
Li, Y., Bu, R., Sun, M., Wu, W., Di, X., & Chen, B., 2018.
PointCNN: Convolution on x-transformed points. Advances in Serna, S.P., Schmedt, H., Ritz, M., Stork, A., 2012. Interactive
neural information processing systems, 31. Semantic Enrichment of 3D Cultural Heritage Collections. Proc.
VAST, Eurographics Association, pp. 33-40.
Liu, S., Zeng, Z., Ren, T., Li, F., Zhang, H., Yang, J., Li, C., Yang,
J., Su, H., Zhu, J., 2023. Grounding dino: Marrying dino with Stathopoulou, E.K., Welponer, M., Remondino, F., 2019. Opengrounded pre-training for open-set object detection. arXiv preprint source image-based 3D reconstruction pipeline: review, comparison
arXiv:2303.05499, 2023. and evaluation. ISPRS Int. Arch. Photogramm. Remote Sens. Spatial
Inf. Sci., Vol. XLII-2/W17, pp. 331-338.
Long, J., Shelhamer, E., Darrell, T., 2015. Fully convolutional
networks for semantic segmentation. Proc. CVPR, 3431-3440. Teruggi, S., Grilli, E., Fassi, F., Remondino, F., 2021. 3D surveying,
semantic enrichment and virtual access of large cultural heritage.
Maietti, F., Medici, M., Ferrari, F., Ziri, A. E., & Bonsma, P., 2018. ISPRS Annals Photogramm. Remote Sens. Spatial Inf. Sci., VIII-MDigital cultural heritage: Semantic enrichment and modelling in BIM 1-2021, 155–162
environment. Lecture Notes in Computer Science, Vol 10605.
Springer, pp. 104-118. Thomas, H., Qi, C. R., Deschaud, J. E., Marcotegui, B., Goulette, F.,
& Guibas, L. J., 2019. Kpconv: Flexible and deformable convolution
Manferdini, A.M., Remondino, F., Baldissini, S., Gaiani, M., for point clouds. Proc. ICCV, pp. 6411-6420.
Benedetti, B., 2008. 3D modeling and semantic classification of
archaeological finds for management and visualization in 3D Weinmann, M., Jutzi, B., Hinz, S., Mallet, C., 2015. Semantic point
archaeological databases. Proc. VSMM, pp. 221-228. cloud interpretation based on optimal neighborhoods, relevant
features and efficient classifiers. ISPRS Journal of Photogrammetry
Matrone, F., Grilli, E., Martini, M., Paolanti, M., Pierdicca, R., and Remote Sensing, 105, 286-304.
Remondino, F., 2020a. Comparing Machine and Deep Learning
methods for large 3D heritage semantic segmentation. International Yan, C., Wang, H., Yan, S., Jiang, X., Hu, Y., Kang, G., ... & Gavves,
Journal of Geo-Information, 9, 535. E., 2024. Visa: Reasoning video object segmentation via large
language models. Proc. ECCV, pp. 98-115.
Matrone, F., Lingua, A., Pierdicca, R., Malinverni, E. S., Paolanti,
M., Grilli, E., Remondino, F., Murtiyoso, A., Landes, T., 2020b. A Yang, S., Hou, M., Li, S., 2023. Three-Dimensional Point Cloud
benchmark for large-scale heritage point cloud semantic Semantic Segmentation for Cultural Heritage: A Comprehensive
segmentation. Int. Arch. Photogramm. Remote Sens. Spatial Inf. Sci., Review. Remote Sensing, 15(3):548
XLIII-B2-2020, 1419-1426.
Yuan, H., Li, X., Zhang, T., Huang, Z., Xu, S., Ji, S., ... & Yang, M.
Poux, F., Neuville, R., Van Wersch, L., Nys, G.-A., Billen, R., 2017. H., 2025. Sa2VA: Marrying SAM2 with LLaVA for Dense
3D point clouds in archaeology: Advances in acquisition, processing Grounded Understanding of Images and Videos. arXiv preprint
and knowledge integration applied to quasi-planar arXiv:2501.04001.
objects. Geosciences, 7, 96.
Zhang, T., Li, X., Fei, H., Yuan, H., Wu, S., Ji, S., ... & Yan, S. 2024.
Qi, C.R., Su, H., Mo, K., Guibas, L.J., 2017a. PointNet: Deep Omg-llava: Bridging image-level, object-level, pixel-level reasoning
learning on point sets for 3D classification and segmentation. Proc. and understanding. Advances in Neural Information Processing
CVPR, 652-660. Systems, 37, 71737-71767.

Zhao, H., Jiang, L., Jia, J., Torr, P. H., & Koltun, V., 2021. Point
transformer. Proc. ICCV, pp. 16259-16268.

This contribution has been peer-reviewed. The double-blind peer-review was conducted on the basis of the full paper.
https://doi.org/10.5194/isprs-annals-X-M-2-2025-253-2025 | © Author(s) 2025. CC BY 4.0 License. 260
