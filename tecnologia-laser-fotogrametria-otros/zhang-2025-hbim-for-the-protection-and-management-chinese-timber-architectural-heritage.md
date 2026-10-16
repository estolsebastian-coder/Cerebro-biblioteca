---
type: libro
title: "HBIM for the protection and management: a case study of Chinese timber architectural heritage"
author: "Jiamin Zhang"
categoria: "Tecnología láser, fotogrametría, otros"
paginas: 22
extraccion: "texto"
fuente: "local:E:/DISCIPLINAS, TEXTOS Y MAPAS/Biblioteca digital/Tecnología láser, fotogrametría, otros/Zhang 2025 - HBIM for the protection and management - Chinese timber architectural heritage.pdf"
convertido: 2026-10-14
---

# HBIM for the protection and management: a case study of Chinese timber architectural heritage

> Texto extraído de `Tecnología láser, fotogrametría, otros/Zhang 2025 - HBIM for the protection and management - Chinese timber architectural heritage.pdf` (22 páginas, texto). El PDF original está en el disco E: (DISCIPLINAS, TEXTOS Y MAPAS\Biblioteca digital); `<!-- p. N -->` marca el inicio de cada página.

<!-- p. 1 -->

npj | heritage science Article

https://doi.org/10.1038/s40494-025-01926-1
HBIM for the protection and management:
a case study of Chinese timber
architectural heritage

Check for updates

Jiamin Zhang1, Lujia Zhang2,3, Wei Zhao2,4, Yinlong Lu5, Xiangli Wang5, Shanshan Yao2,6 &
Hongyi Lyu2,3,4

The creation of information models for Chinese timber architecture faces challenges due to the
complexity of its structural system and components. This study aims to explore the creation and
application methods of information models for Chinese timber buildings, providing technical solutions1234567890():,; 1234567890():,; for their digital preservation. Using the Main Hall of Chuzu Temple as a case study, the study proposes
a method system for constructing HBIM for timber architecture. The system includes multi-source
data collection, model creation based on Revit, ﬁtting adjustments with point cloud models, non-
geometric information loading, and virtual display utilization. The research ultimately created a HBIM
model for Chinese timber architecture that closely matches the current state, establishing a family
library with 66 family categories and 330 families, and achieved the protection and management of the
Main Hall of Chuzu Temple.

Amid the ongoing evolution of heritage conservation principles, digital by integrating multi-source data, offering accurate and efﬁcient digital
technologies have introduced new tools for the documentation, manage- support for the conservation, restoration, and presentation of timber heri-
ment, and dissemination of cultural heritage1. These technologies help tage buildings10.
overcome the limitations of traditional conservation methods in terms of The creation of the model is fundamental to HBIM. Currently, the
precision, efﬁciency, and collaboration2, thereby addressing the growing automated Scan-to-BIM workﬂow is the dominant approach, utilizing deep
demands for systematic, sustainable, and shareable heritage practices3. learning algorithms, Grasshopper plugins, and other technologies to per-
Building Information Modeling (BIM) has been widely adopted in the form automated or semi-automated modeling of point cloud data11–13. This
Architecture, Engineering, and Construction (AEC) industries4, encom- process can automatically identify and segment the basic components of
passing the generation, management, and exchange of information among brick and stone buildings, such as doors, windows, and walls14,15. Addi-
professionals throughout project development. With the rapid advance- tionally, some scholars have explored localized timber components,
mentofsurveyingtechnologiessuchasTerrestrialLaserScanning(TLS)and including roof trusses, ﬂoors, and staircases16–18.
close-range photogrammetry5, the concept of Heritage Building Informa- In recent years, HBIM has gradually gained attention in Asian timber
tion Modelling (HBIM) was ﬁrst proposed by Murphy et al. in 20096. HBIM architectural systems. Through speciﬁc rule-based algorithms, initial steps
extends the application of BIM to the heritage ﬁeld, aiming to digitally have been taken to generate typical timber components, such as dougong
reconstructhistorical buildings7, semantically model architectural elements, (bracket set), from point cloud models. For example, Liu developed a
and integrate various types of information to support informed decision- method to automatically extract parameters from the 3D scanned point
making8. clouddataofdougongcomponents19.Afewstudieshaveattemptedtomodel
As a crucial category of immovable cultural heritage, timber archi- heritage buildings holistically during restoration. For instance, Hyun-Chul
tecture holds signiﬁcant scientiﬁc, artistic, and cultural value. However, its Youn conducted full 3D scanning of all building components during a
conservation faces substantial technical and managerial challenges due to restoration project to create a realistic Rhino 3D model20. In conclusion,
the intricate structural details, the diversity of components, and the high research on systematically constructing a complete timber building infor-
precision required for interventions9. HBIM provides an effective solution mation model remains scarce. If the goal is to achieve a comprehensive,

1School of Archaeology and Cultural Heritage, Zhengzhou University, Zhengzhou, China. 2School of Architecture, Zhengzhou University, Zhengzhou, China. 3Key
Research Base for the Conservation and Sustainable Development of Grand Archaeological Sites, Zhengzhou University, Zhengzhou, China. 4Henan International
Joint Laboratory of Eco-community & Innovative Technology, Zhengzhou, China. 5Henan YunJi Digital Information Technology Co. Ltd, Zhengzhou, China.
6Archaeology Innovation Center, Zhengzhou University, Zhengzhou, China. e-mail: yss1106@zzu.edu.cn; 492399472@qq.com

npj Heritage Science | (2025)13:399 1

<!-- p. 2 -->

https://doi.org/10.1038/s40494-025-01926-1 Article

component-based expression of architectural heritage, relying solely on dougong components. Using families to create heritage information models
point cloud models is insufﬁcient to meet the practical needs. enables a complete expression of the internal structure of the building.
For architectural heritage that requires accurate representation of However, most current studies focus on creating families based on an
internal structures, creating speciﬁc building component families is crucial. idealized design state, without considering an accurate representation of the
However, BIM, primarily designed for modern building development, has a current condition, which is fundamental to future preservation efforts.
limited library of component families suitable for heritage buildings. Additionally, most of the existing families are designed for masonry
Researchers have mainly focused on the parametric creation of typical buildings, while those for timber structures still require further
building elements. For instance, Murphy M and others developed a para- development.
metric representation of classical architectural elements based on building The primary objective of this study is to explore the creation and
rules21. Rania Aburamadan developed a heritage BIM shared library for application methods of the Chinese timber architecture information model,
typical elements in Jordanian and Arab architecture22. Sampaio A Z witha particularfocusonmeetingthe need foranaccurate representationof
explored the generation of parametric families for representative compo- the current state while constructing component-based models. To this end,
nentsof theLisbonPalace23.SimilarresearchhasemergedinEastAsia.Jiang the study focuses on the Main Hall of Chuzu Temple, a representative
Y, for example, developed an intelligent automatic modeling method using timber building from the Song Dynasty in China, and proposes an HBIM
Dynamo for creating dougong components24. Park deﬁned the parametric frameworkfortimberarchitecturalheritage.Thisframeworkencompassesa
relationships between Korean traditional house elements and developed a comprehensive technical process from model creation, information intesystem family library for these elements. gration, to virtual display. The study ﬁrst creates a component library
Families are the foundation of component-based model creation. They containing the majority of the hall’s components based on multi-source
not only express the composition and internal structure of components but data, then ﬁts the point cloud model to develop an information model that
also facilitate subsequent integration and management of information. accurately reﬂects the current state, while incorporating multiple types of
Some studies have focused on enhancing the semantic expression and non-geometric information. Finally, practical explorations of virtual display
information integration of families by leveraging data programming, based on this model were carried out.
knowledge graphs, or knowledge base platforms25–28. In the ﬁeld of architectural heritage preservation, most existing families focus on typical Methods
components of masonry buildings, with fewer families created for other Research object
types of heritage components1,2. The Chuzu Temple is an integral part of the “Historic Monuments of
Whether through point cloud recognition and segmentation or para- Dengfeng in ‘The Centre of Heaven and Earth’,” a United Nations Educametric modeling of families, current modeling efforts are primarily focused tional, Scientiﬁc, and Cultural Organization (UNESCO) World Heritage
on the creation of speciﬁc building components. In response to this lim- site. The Chuzu Temple is part of the Shaolin Temple, and is located in
itation, some researchers have attempted to parametrize entire frameworks. Zhengzhou City, Henan Province, China, with geographical coordinates of
For example, Kang H carried out parametric modeling of major load- 34°30′N latitude and 112°55′E longitude (Fig. 1a). The Chuzu Temple
bearing components such as columns, beams, and ﬂoors in traditional features a two-courtyard layout, oriented north to south, and covers an area
Korean timber architecture, with other parts relying on scanning data for of ~3000 square meters. The central axis sequentially consists of the main
supplementation29. Xu, on the other hand, explored an automated method gate, the Main Hall of Chuzu Temple (Fig. 1b), and the Thousand Buddha
forgeneratingthe drumtowerframebasedontraditionalChinesecarpentry Hall. On either side of the Thousand Buddha Hall are the East and West
construction rules30. Wings, and other pavilions (Fig. 1c). The courtyard contains forty-nine
For the architectural heritage families and entire frameworks, para- steles from various periods and fourteen ancient trees of notable species.
metrization is typically an idealized model designed based on speciﬁc rules The Main Hall of Chuzu Temple is the central structure of the temple,
or algorithms, making it difﬁcult to accurately reﬂect the actual state of the located on a platform with a nearly square ﬂoor plan. Built during the Song
building. However, realism is the foundation on which future preservation Dynasty (1125), the hall has undergone several renovations in the Jin, Ming,
efforts must be based. In addition to creating information models for Qing,andmodernperiods.However,amongexistingSongDynastywooden
architectural heritage,many scholars have also focusedon the application of structures, its construction methods are the closest to those outlined in the
HBIM in 3D visualization. By integrating Virtual Reality (VR) software, Yingzao Fashi (Song-era construction guide). The puzuo (bracket set)
game engines, and web platforms31, HBIM has been extended for practical arrangement, component detailing, and decorative patterns all align with
use in heritage preservation management, educational display, and other practices recorded in the Yingzao Fashi.
real-world applications32,33. TheMainHallofChuzuTempleisdividedintothreemainlevels.From
SimilartoBIM,thecreationofHBIMalsorequiresadherencetocertain bottom to top, they are the platform base, the main body, and the roof. The
rules. Although various modeling methods are gradually emerging, there is platform level includes the steps and xiangyan (a triangular feature at both
currently no universally accepted HBIM standard across different regions. ends of the tread), while the main body consists of three bays in both width
European countries have developed their own standards, including Italy’s anddepth,incorporatingcomponentssuchascolumns,windows,andwalls.
UNI 1133734 and Spain’s Guía BIM para Patrimonio Cultural35, which The roof is designed in a Xieshan (gable and hip roof) style, featuring a
formally deﬁne the application of BIM methods in cultural heritage pre- zhengji, four chuiji, and four qiangji (three types of roof ridges), with a
servation, covering key aspects like maintenance, restoration, and digital relatively gentle curve. The detailed construction information of the Main
archiving of heritage buildings. On a global scale, ISO 19650 is widely Hall is shown in Fig. 2.
adopted and serves as the cornerstone for BIM practices in many countries, The Main Hall’s puzuo are divided into external and internal puzuo.
and its principles now being integrated into HBIM projects. In contrast, These systems, composed of individual components such as dou, gong, and
countries in Asia, such as China, Japan, and South Korea, have yet to ang (three main components of puzuo), connected by sunmao (a unique
establish independent HBIM standards. Instead, they generally base their component connection method) (Fig. 3a), are vital to the value of Chinese
HBIM practices on general BIM standards and focus on targeted explora- timber architectural heritage. Therefore, creating these components in
tions within speciﬁc projects s36–38. HBIM is essential. The external puzuo comprises twenty-six elements,
In summary, the reverse modeling approach from point cloud models includingcornerpuzuo,capitalpuzuo,and intercolumnarpuzuo(Fig.3b,c).
to HBIM offers the advantage of faithfully representing the building’s sur- The internal puzuo consists of twenty-three elements, four for the interior
face, but the recognition and segmentation of components are key chal- columns puzuo and nineteen for the wujia puzuo.
lenges in the model creation process. In regard to East Asian timber The columns inside and outside the Main Hall of Chuzu Temple
architecture, preliminary work has been done on creating models of display unique characteristics of Chinese timber architecture heritage, such

npj Heritage Science | (2025)13:399 2

<!-- p. 3 -->

https://doi.org/10.1038/s40494-025-01926-1 Article

Fig. 1 | The Chuzu temple. a Location of the Chuzu Temple. b The Main Hall of Chuzu Temple. c The Chuzu Temple courtyard.

Fig. 2 | Structural system of the Main Hall of
Chuzu Temple. This ﬁgure illustrates the complete
structural system of the Main Hall of Chuzu Temple,
with annotations identifying its key components.
Special terminology is presented in pinyin (italicized) for technical accuracy.

npj Heritage Science | (2025)13:399 3

<!-- p. 4 -->

https://doi.org/10.1038/s40494-025-01926-1 Article

Fig. 3 | Construction features of the Main Hall of Chuzu Temple. a Construction composition of capital puzuo. b Rear elevation. c Gable elevation. d Front elevation.
e Plane.

as shengqi, shoufen, and cejiao (three special column constructions). When the Buddha worship area in front and the transport space in the back (Fig.
creating the information model, attention should be paid to these speciﬁc 3e).ThewallsandcomponentsoftheMainHallareadornedwithdecorative
construction details. All columns are octagonal stone columns, with twelve paintings, and the carvings on the stone columns and the xumizuo are
eave columns and four interior columns. The front and rear eave columns, particularly lifelike. This indicates that the Chinese timber architectural
as well as the side eave columns, exhibit signiﬁcant shengqi from the center heritage represented by the Main Hall possesses unique component charto the corner columns (Fig. 3d). Additionally, the stone columns retain the acteristicsandacomplexstructuralsystem,presentingcertainchallengesfor
traditional practices of timber columns, with each column exhibiting a the HBIM creation.
certain degree of shoufen (Fig. 3d). Except for the four columns covered by Due to the geometric complexity and distinctive structural features of
the wall, the remaining columns exhibit cejiao, which enhances the struc- theMainHallofChuzuTemple,aswellastheneedtointegratevarioustypes
tural stability of the Main Hall to some extent. of non-geometric information, this study proposes a structured technical
Additionally, xumizuo (high base with decorated mouldings) is placed framework and workﬂow for HBIM construction. The foundation of model
between the front and rear interior columns of the Main Hall, with the rear construction lies in the accurate acquisition of data, achieved in this study
columns constructed using the yizhuzao (a method of column grid through a multi-source information integration approach. Field measurearrangement) technique. This approach facilitates a reasonable functional ments were combined with a review of historical data to ensure both geodivision of the originally homogeneous interior space, accommodating both metricprecisionandcontextualdepth.Theﬁeldworkinvolvedbothmodern

npj Heritage Science | (2025)13:399 4

<!-- p. 5 -->

https://doi.org/10.1038/s40494-025-01926-1 Article

Fig. 4 | The technical ﬂow of building information model for the Main Hall of Chuzu Temple. This ﬁgure delineates the four-stage modeling process for the Main Hall of
Chuzu Temple: Step.1 Collection of multi-source information, Step.2 Creation of the architectural component family library, Step.3 Contruction of the geometric model,
Step.4 Loading of non-geometric information.

surveyingtechnologies—suchasTLSandUnmannedAerialVehicle(UAV) 2. Creation of the architectural component family library. First, the
photogrammetry—and traditional manual measurements. Historical data building components are categorized, and a naming convention is
primarily included archival records, survey reports, and relevant academic established. Based on the preservation needs of timber architectural
publications. heritage, the Level of Development (LOD) for different components in
This study employs Revit, a widely used HBIM software, as the this model is proposed. A single component family is created based on
primary tool for constructing the information model. The core of the these criteria, which is then used to complete a composite component
modeling process lies in the creating building component families39. family, ultimately establishing the component family library.
Although Revit currently lacks a built-in library speciﬁcally for 3. Construction of the geometric model. A central model is created to
Chinese traditional timber architecture—particularly the family sys- facilitate collaborative modeling among multiple parties, with tasks
tems of the Song Dynasty structures—custom loadable families can allocated based on the division of worksets. The components are built
be created based on the acquired geometric data and structural up layer by layer to complete the basic model. Subsequently, the point
relationships. Moreover, each family in Revit features an expandable cloud model is imported for ﬁtting, and the characterization of comproperty panel, allowing users to enter and customize non-geometric ponent deterioration is referenced to ﬁnalize the model representing
information according to the speciﬁc needs of heritage conservation the current condition.
and research40,41. 4. Loading of non-geometric information. The integration of non-
The study divides the creation of the information model for the Main geometric information was achieved by adding family parameter
Hall of Chuzu Temple into four main steps (Fig. 4). information, creating drawings, and linking point cloud data. This
\1. Collection of multi-source information. An on-site survey of the Main integration of various types of information into the HBIM facilitates
Hall of Chuzu Temple was conducted using methods such as TLS, the work of heritage preservation, research, and management
UAV photogrammetry, and manual measurements. These prelimin- professionals.
ary investigations, combined with historical archives, survey reports,
and related research literature, provided both geometric information HBIM creation
and non-geometric data. This foundational work forms the basis for The geometric information of the Main Hall can be divided into two cate-
the subsequent model creation. gories: one consists of data related to the exterior and interior surfaces of the

npj Heritage Science | (2025)13:399 5

<!-- p. 6 -->

https://doi.org/10.1038/s40494-025-01926-1 Article

Fig. 5 | Geometric information acquisition. a TLS. b UAV ﬂight paths. c Field survey. d TLS workﬂow. e Workﬂow for UAV data processing. f Conservation and restoration
project information.

building, and the other includes the forms, dimensions, and connections of of scanning stations was designed, with a total of 110 stations deployed,
various components within the structure. The former geometric data can be achievingover90% data coverage. The scanning resolutionwas setto 6 mm.
obtained through TLS and UAV photogrammetry42,43, with supplemental To ensure comprehensive data collection for the upper beams and roof
manual measurements conducted to verify or reﬁne the dimensional structure, a boom arm was used on-site to extend the scanning range veraccuracyofspeciﬁccomponents.Thelattergeometricdatawasderivedfrom tically (Fig. 5a).
an analysis of historical archival drawings and research literature related to After scanning the entire Main Hall, the acquired point cloud data was
the Main Hall, conducted by experts in traditional Chinese architecture. registered, merged, and denoised (Fig. 5d). Point cloud registration was
These methods were employed to construct a geometric model that accu- carried out using cloud-to-cloud reference points in FARO SCENE softrately reﬂects the current condition of the building. The acquisition of non- ware. High-precision alignment and fusion of multi-station point clouds
geometricinformationisprimarilybasedonﬁeldsurveysandsupplemented were achieved by identifying and extracting the 3D coordinates of control
or validated through archival documents and scholarly research on the points, with a Root Mean Square Error (RMSE) controlled within 3 mm46.
conservation of the Main Hall of Chuzu Temple. Noise reduction was performed using the Clipping Boxes and Export Filter
Using TLS and UAV photogrammetry allows for the precise and tools in FARO SCENE software. The ﬁnal point cloud model achieved
comprehensive collection of surface data for both the building and its sur- millimeter-level accuracy, consisting of approximately 1.1 billion points.
rounding environment44,45. The project uses the FARO Focus S70 3D laser In addition to using TLS for detailed documentation of the Main Hall,
scanner to capture geometric data of both the interior and exterior surfaces the DJI Phantom 4 RTK was employed to capture data of the outdoor
of the Main Hall. This phase-based scanner features a high scanning speed ground surface, building façades, roofs, and surrounding environment
and a measurement range of 0 to 70 m. Before scanning, a systematic layout (Fig. 5b). Images were captured from four oblique directions (east, west,

npj Heritage Science | (2025)13:399 6

<!-- p. 7 -->

https://doi.org/10.1038/s40494-025-01926-1 Article

Table 1 | Classiﬁcation of family components of the Main Hall The architectural components of the Main Hall are diverse, requiring
of Chuzu Temple categorization before creating the component family library. Based on the
structural characteristics of the Main Hall, the components are divided into
No. Classiﬁcation of building components Family category Family
12 major categories: platform, main body section, puzuo layer, upper beam,
1 Platform 1 2 upper puzuo, upper tie, upper purlin layer, muji (roof structure) layer,
2 Main body section 9 27 interior wooden decoration, interior furniture, tiles, and ridge. Subse-
3 Puzuo layer 8 105 quently, the 12 major categories are classiﬁed according to the family
category and hierarchy in Revit software (Table 1). As a result, the com- 4 Upper beam 8 11
ponents of the Main Hallare classiﬁedinto 66 familycategories,totaling330
5 Upper puzuo 11 74
families.
6 Upper tie 2 6 The construction of ancient Chinese timber structures is intricate,
7 Upper purlin layer 5 12 accompanied by a wide range of terminology. Given the practical needs of
8 Muji layer 6 40 preserving and managing historical buildings, assigning unique codes to
architectural components is essential. This practice clariﬁes the character-
9 Interior wooden decoration 1 1
istics of each component, resolves issues of vague naming and difﬁcult
10 Interior furniture 1 1 positioning, and facilitates their use in later restoration and management
11 Tile 7 30 efforts.
12 Ridge 7 21 The naming of the components in the Main Hall integrates two
approaches: a unique numerical identiﬁcation system and a spatial grid
positioning system. The unique numerical identiﬁcation system assigns
numerical codes to all architectural components, simplifying their location,
south, and north) as well as a vertical direction, with both forward and side retrieval, and quantity statistics. The spatial grid positioning system indioverlaps set to 80%. A total of 10 control points were deployed using a cates the spatial location and categorical attributes of each component. This
combination of RTK and total station to ensure high positional accuracy. includes eight speciﬁc information elements: reference axis grid, horizontal
The UAV photogrammetry produced three types of data: raw images, axis grid, vertical axis grid, elevation, category, properties, order, and name
camera parameter ﬁles, and position and orientation system data, with a (Fig. 6).
total of ~3000 images captured. The data were processed using Context The information data of timber architectural heritage is extensive and
Capture software (Fig. 5e). During the aerial triangulation process, auto- intricate, leading to a signiﬁcant workload in building the information
matic image matching combined with control point adjustment was model. However, not all component information is of equal importance.
employed to complete image alignment. The accuracy of 3D reconstruction Detailing every component could resulted in an excessive workload,
was controlled within ±1 cm. potentially reducing efﬁciency in future use. Conversely, overly simpliﬁed
To integrate TLS and UAV data, Geomagic Studio was used to align component information may fail to meet the requirements of the model’s
and merge multi-source point clouds. The uniﬁed point cloud data was then future applications58.
imported into Autodesk Recap for format conversion and simpliﬁcation The concept of LOD was ﬁrst introduced by the American Institute of
before being integrated into the modeling process using Autodesk Revit. In Architects (AIA), which formally deﬁned ﬁve levels—LOD100–LOD500—
addition to data acquisition using TLS and UAV photogrammetry, manual in the AIA Document E-203 (2013), to specify the degree of detail at difmeasurements were employed to supplement and verify geometric infor- ferent stages of a BIM model. Brusaporci et al. highlighted the difﬁculty of
mation in areas where technical methods were limited (Fig. 5c). Speciﬁcally, applying LOD standards designedfor newconstructions directly to heritage
manual measurements were used to: (1) obtain dimensional data of com- buildings, emphasizing the need for standardized LOD protocols tailored to
ponents that were occluded or inaccessible to laser scanning due to struc- the complexity of heritage modeling47,59. In the realm of built heritage, the
tural obstructions, and (2) verify or reﬁne dimensions in areas where LOD framework must remain ﬂexible, enabling professionals to adjust the
material color, reﬂectivity, or lighting conditions caused point cloud data to level of detail according to speciﬁc project requirements and application
be unclear or incomplete. scenarios60,61. For example, Chow et al. proposed customized LOD deﬁni-
The construction of Chinese timber architectural heritage, exempliﬁed tions for historic buildings62, while Pinto-Puerto et al. introduced new
by the Main Hall of Chuzu Temple, primarily consists of internal sunmao, conceptssuchasLevelofKnowledge(LOK)andLevelofInformation(LOI),
particularlythepuzuomadeupofdou,gong,ang,andtheinterlockingupper placing greater emphasis on the semantic information hierarchy inherent in
beams. Relying solely on point cloud data makes it difﬁcult to clearly heritage assets47,63.
delineate the various building components, and the connections between To ensure modeling efﬁciency and enhance the use and management
them are even harder to discern23. Therefore, to analyze the internal of the model, it is essential to classify the information detail levels of the
structural connections of the Main Hall, it is essential to utilize archived building components prior toconstructing the information model. Building
preservation and repair drawings from the Henan Provincial Administra- on the original concept of LOD14, this study deﬁnes and categorizes LOD
tion of Cultural Heritage, the Dengfeng City Administration of Cultural levels from 100 to 400 based on the structural characteristics of traditional
Heritage, and the Henan Provincial Institute of Architecture Heritage Chinese timber architecture, incorporating both geometric and nonConservation and Research (Fig. 5f). This information, combined with ﬁeld geometric information (Table 2). For the Main Hall, the components are
survey, enables professional architectural heritage researchers to analyze classiﬁed into six types: walls, doors and windows, structural columns,
and verify the internal divisions and connection relationships of the com- timber beam frames, puzuo, and roofs. Considering the contribution of
ponents,thusprovidingaccurateguidancefortheentiremodelingprocess47. these components to the heritage value and future information usage needs,
Additionally, related research literature on the Main Hall of Chuzu the modeling depth requirements for walls, doors and windows, and
Temple offers important references. These studies primarily fall into three structural columns are set at LOD300, while those for timber beam frames,
categories: basic surveys and mapping48,49, structural and morphological puzuo, and roofs are set at LOD400.
analysis50–54, and heritage conservation research55–57. The ﬁrst two categories In Revit, there are three types of families: system families, loadable
contribute to the reﬁnement and validation of the geometric infor- families, and in-place families. Currently, the settings for system families in
mation of the Main Hall, while the latter provides a valuable foun- Revit are developed based on the structural composition and design
dation for integrating non-geometric data such as material requirements of modern buildings. Some scholars have researched the
deterioration and past interventions. parametric creation of families for classical European architecture, but this

npj Heritage Science | (2025)13:399 7

<!-- p. 8 -->

https://doi.org/10.1038/s40494-025-01926-1 Article

Fig. 6 | Building component coding meaning. This ﬁgure shows the speciﬁc horizontal axis grid, vertical axis grid, elevation, category of component, component
expressions of Unique Number Naming and Spatial Grid Positioning Naming, properties, order of components, name of component.
among which the latter includes eight information elements: Reference axis grid,

Table 2 | Modeling requirements at different levels of detail

LOD Geometric information Non geometric information

100 relative position, rough shape —

200 relative position, dimension, basic form material

300 relative position, dimension, detailed construction material, construction method

400 relative position, dimension, detailed construction, component status material, construction method, deterioration information

approach clearly does not meet the requirements for building information modelingprocessbeginswith2Ddrafting,followedbycreationofa3Dsolid
models of East Asian architectural heritage. However, Revit provides model of the nidaogong using operations such as extrusion, lofting, and
another method for family creation, allowing users to customize families in merging. Finally, appropriate materials and colors are applied to the model.
the family editor and subsequently load them into the project for use. These The process of creating a composite nested family can be illustrated
are known as loadable families and are characterized by high ﬂexibility, using the intercolumnar puzuo as an example, employing a method similar
making them the primary construction method for the architectural com- to that used for the nidaogong to complete the other components of the
ponentsintheMainHallinformationmodel.Componentssuchasplatform intercolumnar puzuo (Fig. 7). Based on the preceding analysis of the geoandﬂoorsharesimilarparametricelementsandarecreatedusingthesystem metric dimensions and structural characteristics of the intercolumnar
family “ﬂoor” in Revit. Conversely, components such as roof board, which puzuo, corresponding reference planes are deﬁned. Each single component
require dimensions and shapes to be determined based on adjacent com- family is then loaded and sequentially positioned at its designated spatial
ponents, are created using in-place families. location,layerbylayer,completingtheassemblyoftheintercolumnar puzuo
The architectural families of the Main Hall consist of various com- (Fig. 8).
ponents,whichcanbecategorizedintotwotypes:singlecomponentfamilies Based onthestructuralcharacteristicsof theMainHall,sevenelevation
(indivisible building components) and composite nested families (families levels are deﬁned from bottom to top: indoor ﬂoor, top of the pingzhu
formed by combining single component families). For example, the process (central bay column), lower surface of the eave tie, upper surface of the
ofcreatingasingle-componentfamilyfornidaogong(atypeofgongmember niujituan (a type of purlin), upper surface of the purlin, upper surface of the
in bracket set) of the intercolumnar puzuo is as follows: the nidaogong is upper purlin, and upper surface of the ridge purlin. A grid system is then
positioned atop the ludou (a type of dou member in bracket set) and aligned created, in addition to the base grid for the columns, a second shared grid is
centrally along the line between the inner and outer puzuo. Based on the set up at the surface of the top of corner column to facilitate the accurate
geometric dimensions of the nidaogong obtained from prior research, a positioning of the puzuo layer and upper components. Based on the
reference line or plane is established using the 3D point cloud model. The established family library, the construction of the platform, main body

npj Heritage Science | (2025)13:399 8

<!-- p. 9 -->

https://doi.org/10.1038/s40494-025-01926-1 Article

Fig. 7 | Intercolumnar puzuo component member. a Ludou. b Chentoumu. c Guazigong. d Guazimangong. e Huagong. f Huatouzi. g Jiaohudou. h Linggong(angshang).
i Linggong. j Mazhatou. k Nidaogong. l Nidaomangong. m Qixindou. n Sandou. o Shangang. p Shuatou. q Timu. r Xiaang. s Xuexie. t Timuzhengxin.

section, and puzuo proceeds (Fig. 9), it is essential to check the relationships decorative paintings information into the model: (1) adding family attribute
between adjacent components and control the overall dimensions. parameters. By including ﬁle paths in the corresponding family type attri-
There are discrepancies between the current state of the Main Hall and bute URL parameters, high-deﬁnition scans of the decorative paintings can
the design model. The hall’s materials are quite diverse, predominantly be linked to the model, or the ﬁle paths can be added to the family attribute
usingnaturalmaterials.Duetoitslonghistoryandexposuretotheelements, ﬁeldforexternalviewingonathird-partyplatform.(2)Insertingdecals.This
the overall structure has experienced twisting and misalignment, with some approach allows the images to be displayed directly within the information
components showing signs of deterioration or loss. To meet the modeling model, although its accuracy is relatively lower.
precision requirements for the Main Hall’s architectural components, TheMainHallfeaturesﬁnelycrafted innerand outerstonecolumns,as
adjustments are made to the geometric dimensions, shapes, and spatial wellasxumizuo,representingraremasterpiecesfromtheSongDynasty.The
coordinate positions of the component families. This ensures that the integration of carving information also involves two methods: (1) The ﬁrst
geometric accuracy of timber beam frames, puzuo, and roof components method is similar to that used for decorative paintings. File paths are
reaches LOD400. included in the family attributes of the corresponding components, linking
In Revit, the component models were aligned with the point cloud64, them to high-precision point clouds or high-deﬁnition images of the carwith a deviation of no more than 3 mm (Fig. 10). The resulting ﬁtted vings. (2) Importing the point cloud model. During the construction of the
geometric models accurately represent the existing conditions, helping Main Hall information model, the point cloud model is importedtoprovide
preservation researchers and managers in gaining a comprehensive anapproximaterepresentationofthecarvings’currentstate.Thismodelcan
understanding of the building’s current state. This provides reliable geo- be viewed later using the point cloud display (Fig. 11).
metric data to support future monitoring, maintenance, and conservation The architectural components of the Main Hall exhibit complex and
efforts. diverse forms of deterioration, posing signiﬁcant threats to their structural
integrity. Given the varying levels of modeling detail for different compoLoading of non-geometric information nents in the Main Hall information model, this study explores methods for
TheMainHallfeaturesintricatedecorativepaintings,includingtwenty-four incorporating deterioration information for timber beam frames, puzuo,
images of Zen patriarchs on the east, west, and north walls, as well as xuanzi and roofs. The following elaborates on two methods for integrating detecaihua (a decorative painting style) on the inner and outer eave puzuo and rioration information, using the puzuo layer as an example.
other architectural components. The painting techniques are reﬁned, and The ﬁrst method for loading deterioration information involves
the ﬁgures are vividly depicted. Two methods are used to integrate expressing the condition through the creation of annotated views in

npj Heritage Science | (2025)13:399 9

<!-- p. 10 -->

https://doi.org/10.1038/s40494-025-01926-1 Article

Fig. 8 | Modeling process of intercolumnar puzuo. a First layer. b Second layer. c Third layer. d Fourth layer. e Fifth layer. f Sixth layer. g Seventh layer. h Eighth layer.

drawings, aligning with the drawing-oriented work habits of architectural Main Hall. This information is stored in the family model ﬁles and can be
professionals. The generation of deterioration drawings for the Main Hall added or updated as needed. Once the information is loaded, selecting a
involves three main steps: First, adjust the perspective and view range of the speciﬁc component in the 3D information model of the Main Hall will
3D information model based on the location of the deterioration, and display the detailed deterioration conditions in the property panel (Fig. 12).
capturethenecessaryimages.Second,createa newdrawingbyinsertingand Additionally, the Revit’s schedule tool can be used to generate a deterioraarranging the prepared views and images. Finally, add annotations to tion details schedule by adding relevant information ﬁelds, allowing for a
describe the speciﬁc condition of the deterioration. To facilitate later quick summary of the deterioration conditions of all architectural comporeference, each drawing is named using the format “deterioration, category- nents in the Main Hall. The ﬁlter, sort, and group tools in the schedule’s
number-speciﬁc,architecturalcomponent”,whichconveyskeyinformation property panel allow for basic ﬁltering, grouping, and statistical analysis of
about the drawing. The creation of deterioration drawings for the Main Hall the deterioration data. The schedule can also be exported as a .txt ﬁle, which
not only aligns with the working habits of architectural professionals but can then be converted and imported into specialized data analysis software
also establishes an interactive relationship between the deteriorated com- for further study.
ponents in the 3D information model and their corresponding 2D deterioration drawings. Virtual display application
The second method for loading deterioration information involves The virtual roaming experience is created using the game engine software
creating text parameters within the family attribute properties to represent UnrealEngine,whichrequirestheimportofthreetypesofdata.First,dataof
the speciﬁc deterioration conditions of each architectural component in the the Main Hall, derived from its information model, is imported. Second,

npj Heritage Science | (2025)13:399 10

<!-- p. 11 -->

https://doi.org/10.1038/s40494-025-01926-1 Article

Fig. 9 | Modeling process of the Main Hall of Chuzu Temple. a Platform. b Main body section. c Puzuo layer. d Upper beam. e Upper puzuo. f Upper tie. g Upper purlin.
h Muji layer. i Tile. j Ridge.

data is sourced from Geographic Information System (GIS) platforms to
obtain geographic and spatial information of the surrounding area. By
importing these three types of data into Unreal Engine, a realistic envir-
onmental atmosphere is constructed through scene arrangement.
Based on the completed HBIM model and the game engine platform,
the entire construction process can be virtually simulated. By reasonably
disassembling and classifying the architectural heritage information model,
and exporting it in specialized formats to Navisworks, virtual construction
animations can be generated. The classiﬁcation of building components is
crucial for the subsequent production of 3D animations. Additionally, the
software loads various model parts by linking ﬁle paths, which improves
performancebyreducingﬁlesizeandhelpsresolveoperationalissuescaused
by the model complexity.
In the practical implementation, the information model of the Main
Hall was divided into 45 parts, including the platform, column bases, and
columns, which were then imported into Navisworks to create new
Fig. 10 | Information model of the main hall of Chuzu Temple. This ﬁgure shows operational ﬁles. The TimeLiner tool was used to simulate the construction
the comparison between the 3D Model and Point Cloud of the Main Hall of Chuzu process of the architectural heritage in Navisworks (Fig. 13). By combining
Temple. Red represents the y–z plane, green represents the x–z plane, and blue the simulation with animation, virtual construction can be presented along
represents the x–y plane.
with real-time roaming, enhancing the overall effect of the animation.

data from other buildings within the courtyard is included. Models of the Results
main gate, east and west wing rooms, and the Thousand Buddha Hall are Point cloud model and drawings
constructed in 3 ds Max based on ﬁeld survey results, and subsequently Using UAV photogrammetry, data on the courtyard and surrounding
imported into Twinmotion for material application. Third, environmental environment of the Main Hall was collected and processed to generate a

npj Heritage Science | (2025)13:399 11

<!-- p. 12 -->

https://doi.org/10.1038/s40494-025-01926-1 Article

Fig. 11 | Loading decorative paintings and carving information. a Decorative painting information. b External link for carving information.

three-dimensional reality model. This model serves to supplement and Deterioration drawing
verify roof data while also providing contextual scene information for Based on the modeling accuracy requirements of the information model of
surrounding virtual display applications of the Main Hall. the Main Hall, the study produced detailed drawings for each deteriorated
Additionally, TLS was employed to gatherinformation about the Main componentinthetimberbeamframes,puzuo,androofstructures.Atotalof
Hall itself. Following registration, stitching, and point cloud denoising, a 23 deterioration drawings were produced, including 5 for the timber beam
crucial reference for constructing the information model—the three- frames, 15 for the puzuo, and 3 for the roof. These drawings provide a
dimensional point cloud model—was obtained. To facilitate data acquisi- relatively comprehensive visual representation of the deterioration situation during the model construction process, the point cloud model was tion, supporting the protection, restoration, and further research efforts for
sliced to produce two-dimensional sliced drawings, including sections, the Main Hall.
elevations, plans, roof framing, and top view. This approach greatly Figure 17 presents the deterioration drawing of puzuo No. 1, which
enhancesthereliabilityoftheoveralldimensionsoftheMainHall.Thepoint includes the position of the puzuo within the puzuo layer, speciﬁc locations
cloud model and sliced drawings accurately reﬂect the current condition of of the deterioration, characterization (corresponding 3D model and realthe Main Hall and serve as the primary basis for creating and ﬁtting the scene photographs), and detailed textual descriptions. The drawing indiinformation model (Fig. 14). cates that this puzuo is located in the southwest corner of the puzuo layer,
with deterioration observed at the guazigong, linggong, pingpandou, and
Family library sandou (constituent components of puzuo) components, including six
Thefamilyis centralto the creationofthearchitecturalheritageinformation cracks and two ﬁssures.
model. Based on the composition and spatial relationships of building
components, a family library was established, encompassing both single Virtual display results
componentfamiliesand compositenestedfamilies.Thislibraryservesasthe Based on the data of the Main Hall, courtyard, and surrounding environfoundation for constructing the information model of the Main Hall. ment, a virtual tour scene was developed using a game engine (Fig. 18).
The family library for the Main Hall includes twelve major types Through virtual reality devices such as head-mounted displays and position
of building components. Each major type contains multiple family trackers, general visitors can engage in an immersive exploration of the
categories. For example, the upper purlins include ﬁve family cate- architectural style of Chinese timber structures.
gories: bofengban (located at the ends of the roof), tie, jituan (a purlin LeveragingthecompletedHBIM modelandthegameengineplatform,
at the top of the roof), shengtoumu (a triangular piece of wood), and a simulated demonstration of the virtual construction process of the Main
xuanyu (located right in the middle of the mountain face of the roof). Hall was developed. Figure 19 presents several key frames from the virtual
In total, the library consists of 66 family categories, each of which construction video of the Main Hall. The intuitive presentation of the
contains multiple individual families, reaching up to 330 families in architectural structure delivers a visual impact, allowing viewers to truly
total. Most components in the family library are loadable families, appreciate the intricacy of traditional Chinese timber construction. The
created through customizations in the Revit family editor, allowing virtual display offers direct references for conservation and restoration
them to be imported into other projects. The family library for the professionals, while also providing the public with an innovative means of
Main Hall offers a comprehensive set of family templates for con- understandingthecraftsmanshipinvolvedinChinesetimberarchitecture.It
structing information models of Chinese timber architecture represents a signiﬁcant approach to balancing the protection, restoration,
(Fig. 15). and utilization of architectural heritage.

HBIM Discussion
Based on the structural characteristics of the Main Hall and aligned with the Scholars in Europe and the United States primarily approach HBIM from a
elevation and axis grid, the model was constructed layer by layer in the measurement-oriented perspective, with concept deﬁnitions and modeling
following sequence: platform, main body section, puzuo, upper beams, logic centered on three-dimensional point cloud data. The construction of
upper puzuo, upper tie, upper purlins, muji layer, wooden decorations, heritage information models is largely based on reverse modeling using
furniture, tiles, and ridges. The result output is the completed design model point cloud data65. Many researchers have explored automatic point cloud
of the Main Hall of Chuzu Temple. segmentation to facilitate the semi-automated generation of HBIM66.
Then, the model was ﬁtted to the point cloud data to sure that all Reverse modeling is driven by the intrinsic characteristics of existing
components met the required modeling depth, resulting in the ﬁnalized architectural heritage. In Western masonry heritage, the geometrical forms
information model of the Main Hall. This model not only includes geo- of building components are relatively prominent, with most conmetric information such as dimensions, spatial positions, current condi- nections involving vertical stacking or compression and fewer
tions, and structural relationships, but also integrates non-geometric interlocking joints. Some researchers have applied deep learning
information (Fig. 16). techniques to enable the semi-automated segmentation of basic

npj Heritage Science | (2025)13:399 12

<!-- p. 13 -->

https://doi.org/10.1038/s40494-025-01926-1 Article

Fig. 12 | Loading result of deterioration information. a The Deteriorated drawing interact with the three-dimensional model. The deteriorated drawing is shown on the left,
while the three-dimensional model is displayed on the right. b Attribute of Guazigong: deteriorated information.

components within point cloud models67, allowing for modular captures surface-level geometric information. Chinese timber architecture
separation suitable for reverse modeling. primarily relies on sunmao joints for structural connections. Whether using
In contrast, Chinese timber structures, such as the Main Hall of Chuzu parametric modeling or the segmentation of point cloud data to create the
Temple, feature unique construction techniques and complex structural information model, current technologies face signiﬁcant challenges in
compositions. Although point cloud data offers high precision, it only achieving this.

npj Heritage Science | (2025)13:399 13

<!-- p. 14 -->

https://doi.org/10.1038/s40494-025-01926-1 Article

Fig. 13 | Virtual construction process diagram. This diagram shows that during the virtual construction process, the construction is divided into 45 stages according to the
logic of building the main hall of the Chuzu Temple, and is arranged in a time sequence.

Fig. 14 | 3D reality model and point cloud slice drawing. a 3D reality model. b Point cloud slice drawing. It includes longitudinal section, plane, roof framing, top view, east
elevation, south elevation and cross section.

npj Heritage Science | (2025)13:399 14

<!-- p. 15 -->

https://doi.org/10.1038/s40494-025-01926-1 Article

Fig. 15 | Component family of the Main Hall of
Chuzu Temple. a Platform. b Main body section.
c Puzuo. d Upper beam. e Upper puzuo. f Upper tie.
g Upper purlin. h Muji layer. i Wooden decoration.
j Furniture. k Tile. l Ridge.

Therefore,for Chinesetimber structures liketheMainHall,inaddition of the Main Hall41,68. This component-based approach enables the threeto relying on point cloud data that captures the building’s exterior, it is dimensional representation of all component sizes and structure details
essential to infer internal construction methods based on survey data and while also supporting the integration of material properties, deterioration
historical documentation. By creating a family library of building compo- data, and other relevant information. The information model developed
nents, the information model can be constructed and subsequently reﬁned using architectural component families serves as the foundation for the
using point cloud data to ensure accurate representation of the current state implementation the data integration platform.

npj Heritage Science | (2025)13:399 15

<!-- p. 16 -->

https://doi.org/10.1038/s40494-025-01926-1 Article

This technical workﬂow is well-suitable for standalone timber struc- modeling phase. The entire process should be supported by mid-to-hightures that require prioritized conservation. To ensure optimal scanning end hardware, including a mainstream CPU (e.g., Intel i7 or above), a
results,theareasurroundingthebuildingshouldbeopen,unobstructed,and dedicated graphics card, and sufﬁcient memory capacity.
fully accessible to survey personnel. A minimum clearance of two meters Mainstream BIM software platforms such as Revit, Archicad, and
should be maintained between the building’s outermost edge and any sur- Bentley currently lack dedicated components for heritage buildings69, parrounding obstructions. It is recommended that ﬁeld data acquisition be ticularly for Chinese timber architecture with its unique structural forms.
conducted by a team of six, with approximately four staff members This deﬁciency has, to some extent, hindered the development and appliresponsible for post-processing and three individuals involved in the cation of heritage building information models. Many scholars have
exploredthe parametric modeling of Chinese timber structures, focusing on
speciﬁccomponentssuch as puzuo,roof, doors,and windows70–72.However,
constructinga fullyparametric modelforan entire timberstructureremains
a signiﬁcant challenge. In this study, a predominantly manual modeling
approach was adopted to build a comprehensive component library for the
MainHall73.Althoughthismethodrequiressubstantialtimeandlaborinthe
initialstages,mostofthefamiliescreatedareloadableandreusableinsimilar
heritage contexts. This improves the scalability and transferability of the
HBIM model, providing valuable templates for future projects involving
comparable architectural typologies74.
Parametricmodelingofbuildingcomponentsandoverallstructurecan
enhance construction efﬁciency, as the inherent relationships are based on
simpliﬁed construction assumptions75. However, these assumptions are
often derived from contemporary architecture, making it difﬁcult to meet
the parametric requirements of heritage buildings76. A comprehensive
Fig. 16 | Information model of the Main Hall of Chuzu Temple. This model family library that includes all component types of the Main Hall not only
contains not only all the geometric information of the building components, but also offers detailed examples for studying the modulus, scale, and construction
non-geometric information such as decorative paintings, carving information, and techniques of timber structures, but also serves as a substantial “family
deterioration information. template” for building information modeling77. More importantly, by

Fig. 17 | Drawing of puzuo deterioration. This picture shows the detailed situation of the damage to the corner puzuo of the main hall of the ChuZu Temple. The speciﬁc
diseased components are correspondingly represented in the model on the left and the real scene picture on the right.

npj Heritage Science | (2025)13:399 16

<!-- p. 17 -->

https://doi.org/10.1038/s40494-025-01926-1 Article

Fig. 18 | Virtual roaming important nodes of the Main Hall of Chuzu Temple. a The Chuzu Temple courtyard. b The Main Hall of Chuzu Temple. c Timeber framework.
d Puzuo.

Fig. 19 | Virtual construction important nodes of the Main Hall of Chuzu Temple. a Platform. b Column. c Lane. d PuzuoI. e PuzuoII. f Beam frameI. g Beam frameII.
h Rafter. i wangban. j Ridge. k Tile. l Wall.

summarizing and generalizing the foundational styles of architectural monitoring results, and maintenance records. Analyzing the interconneccomponents, it becomes possible to develop a parametric family system tions among these datasets can provide a scientiﬁc basis for the repair and
speciﬁcally tailored to Chinese timber heritage buildings. protection of heritage buildings78. However, for most heritage sites, different
As research on architectural heritage conservation deepens, many types of information are often managed by separate departments, resulting
scholars have undertaken more rigorous scientiﬁc investigations, resulting in fragmentation that hampers the extraction of their full value. Integrating
in a wealth of data such as structural stress measurements, environmental diverse information is urgently needed for government agencies, the public,

npj Heritage Science | (2025)13:399 17

<!-- p. 18 -->

https://doi.org/10.1038/s40494-025-01926-1 Article

and conservation researchersalike,which isaninevitableoutcomeof the big However, the lack of systematic standards and practical experience in areas
data era. In addition, cross-platform compatibility is essential to promote such as data-sharing mechanisms, platform compatibility, and security
the dissemination and practical application of modeling outcomes. By management currently limits the broader application of such models across
adopting the IFC data standard, interoperability among HBIM platforms regions and institutions.
such as Revit, Archicad, and FreeCAD can be achieved, thereby minimizing Furthermore, to ensure the effectiveness and feasibility of heritage
information loss and ensuring consistency across systems. building information models in practical applications, a systematic eva-
The Main Hall has successfully integrated non-geometric information. luation mechanism should be introduced in future work. The model’s
Insubsequentwork,maintenanceinformation canbeincorporated through functional adaptability, operational usability, and application efﬁciency
full life cycle management in Revit79,80. Additionally, experiments and should be assessed from multiple perspectives, including expert feedback,
simulations have been conducted on the structural stress of both the puzuo user testing, and performance benchmarking. Through a multidimensional
and the overall frameworkto analyzetheirstress characteristics.Monitoring post-evaluation framework, the model can be appropriately adjusted and
and simulation analyses of the surrounding microclimate have also been iterated to further enhance its practical value.
carried out, providing preliminary insights into the relationship between ThispapertakestheMainHallofChuzuTempleastheresearchsubject
current deterioration and microclimate conditions. Integrating such and investigates the application and implementation of HBIM technology
information into the information model is crucial for understanding dete- in the conservation and management of wooden heritage buildings.
rioration mechanism and informing protection and restoration efforts81. Through modern surveying techniques, various data related to the Main
Achieving this may require collaboration with computer science profes- Hall were collected, and the building’s geometric characteristics were
sionals. Furthermore, the future integration of the Internet of Things (IoT) identiﬁed in conjunctionwith relevanthistoricalmaterials.The information
could support further development of preventive conservation strategies. model of the Main Hall was then created using a family library developed in
TheinformationmodeloftheMainHallofChuzuTemple,developed based Revit and ﬁtted with the point cloud model. Approaches for integrating
on family components, provides a solid foundation for implementing these non-geometric information were also examined. Finally, based on this
functions. information model, virtual display methods for the Main Hall were
TheapplicationofHBIMinthedocumentation,conservationresearch, explored. The key ﬁndings of this study are summarized as follows:
andrepairmanagementofculturalheritagerepresentsitsmostfundamental A methodical system suitable for the creation of HBIM for Chinese
and essential function. Beyond this, the potential of HBIM in public com- timberarchitecturalheritagehasbeenestablished.Thissystemencompasses
munication and virtual presentation is also recognized, as it can enhance data collection, model construction, and information integration, and is
public awareness and engagement, thereby indirectly supporting heritage demonstrated through the case study of the Main Hall of Chuzu Temple. It
conservation. As such, educational displays and tourism promotion are provides a technical foundation for the development of information models
regarded as important components of preservation strategies82. With the for timber architectural heritage.
advancement of modern 3D visualization technologies, virtual display AnHBIM has beencreatedthatcloselyreﬂectsthe current conditionof
applications for cultural heritage have emerged, including VR, Augmented the Main Hall of Chuzu Temple. This model captures not only the surface
Reality (AR), Mixed Reality (MR), and holographic projections83. These detailsofthearchitecturalcomponentsbutalsotheirstructuralconnections.
technologies have primarily been applied in museums, exhibition halls, and It provides comprehensive data support for the research, conservation, and
educational institutions, signiﬁcantly enhancing user immersion. They also restoration of the Main Hall.
have potential for broader application in contexts such as archaeological A complete library of architectural component families for the Main
sites, scenic areas, and historical architectural complexes. HallofChuzuTemplehasbeenestablished.Thislibrarycomprises66family
This research has effectively explored virtual display applications, categories and a total of 330 families. This work contributes to the develincluding virtual tours and virtual construction, using the completed opment of a comprehensive HBIM family library for Chinese timber
information model of the Main Hall and collected environmental data via architecture, thereby enriching the component library for heritage archirelevant game engine platforms. This approach greatly reduces repetitive tecture within the Revit environment.
tasks and expands the application potential of the information model. In the Various methods for integrating multiple types of information into
future, we plantogradually apply thisapproach to other monuments within HBIM have been explored. By utilizing family attributes, creating drawings,
the “Historical Monuments of Dengfeng in ‘The Centre of Heaven and and linking point clouds data, non-geometric information such as decEarth’,” such as the Talin and the Songyue Temple Pagoda. The goal is to orative paintings, carvings, and deterioration has been successfully inteleverage digital technology to foster new forms of productivity and support grated into the HBIM model, offering a practical approach for nonlocal tourism development. geometric data incorporation.
Building upon this study, the scalability of heritage building information models demonstrates signiﬁcant potential for application, particularly within an integrated BIM-GIS framework that allows for the Terminologys
comprehensive management of both heritage assets and their surrounding
environments. By optimizing the BIM model for lightweight performance Ang 昂 A long slanted lever arm balanced on the ludou.
and uploading it to a cloud-based platform, tiered, permission-based access Its “tail” bears the load of a purlin and is
can be provided to various user groups, including heritage conservation counterbalancedbytheeaveloadatthelowerend,
agencies, research institutions, and public education platforms84. in Tang and Song construction.
However, several challenges remain in this process. On the one hand, Bofengban 博 Located at the ends of the roof, used to shield the
lightweighting often involves data simpliﬁcation or compression. Achieving 风板 purlin, see Fig. 2.
efﬁcient transmission and online visualization while maintaining relative
data completeness and semantic integrity remains a key technical challenge. Cejiao 侧脚 The tops of the columns lean toward the
On the other hand, BIM and GIS differ in semantic structures and opera- building’s center.
tional logic, and their effective integration requires uniﬁed standards and Chuiji 垂脊 In gable and hip roof, this refers to the ridge that
further development efforts85. intersectsperpendicularlywiththemainridge,see
In the future, heritage building information models are expected to be Fig. 2.
integrated with existing national or regional data platforms—such as
Dou 斗 Bearing block.environmental monitoring systems and cultural heritage databases—to
enable more comprehensive and real-time dynamic management.

npj Heritage Science | (2025)13:399 18

<!-- p. 19 -->

https://doi.org/10.1038/s40494-025-01926-1 Article

Gong 拱 Bow-shaped timber, set in a bearing block, it Xuanzi 旋子 It is one of the ancient decorative painting styles
supports a smaller block at each upraised end and caihua 彩画 on ancient Chinese buildings, named for the
often in the center, like bracket arm. spinning ﬂower pattern painted on it.

Guazigong 瓜 A type of gong member in bracket set, see Fig. 3a. Yizhuzao 移 The practice of shifting a number of interior
子拱 柱造 columns to increase or decrease column spacing
to achieve the desired space and function, see Huagong 华拱 A type of gong member in bracket set, bracket
Fig. 3e.
extending forward and back from the ludou, at
right angles to the wall plane, see Fig. 3a. Yingzao 营造 It was the ﬁrst ofﬁcial work in China to deal in
Fashi 法式 detail with the practice of architectural Jituan 脊槫 A purlin at the top of the roof.
engineering,andwasa collectionandsummaryof
Linggong 令拱 A type of gong member in bracket set, often the experience of architectural design and
intersected by a shuatou cross, see Fig. 3a. construction at Song Dynasty.
Ludou 栌斗 The principal bearing block, lowest in a bracket Zhengji 正脊 Main ridge, see Fig. 2.
set, see Fig. 3a.
Mujiceng 木 It refers to the part of the wooden structure above Data availability
基层 the purlin and below the tile of the entire wooden The datasets used and/or analyzed during the current study are available
frame of the house, including rafters, boards, etc. from the corresponding author on reasonable request.
Nidaogong 泥 A type of gong member in bracketset, mounted in
道拱 the mouth of the ludou, parallel to the wall, see Abbreviations
Fig. 3a. BIM Building Information Modelling
HBIM Heritage Building Information Modelling
Niujituan 牛 The purlin between the lower pingtuan and the
AEC Architecture, Engineering, and Construction
脊槫 eave tie, see Fig. 2.
UNESCO United Nations Educational, Scientiﬁc, and Cultural
Pingpandou 平 A type of dou member in bracket set. Organization
盘斗 TLS Terrestrial Laser Scanning
UAV Unmanned Aerial Vehicle Pingzhu 平柱 Central bay column, see Fig. 2.
RMSE Root Mean Square Error
Puzuo 铺作 Bracket set, referred to as puzuo during the Song LOD Level Of Development
Dynasty and as dougong from the Qing Dynasty LOK Level of Knowledge
onward, see Fig. 3a, b, c. LOI Level of Information
Qiangji 戗脊 In gable and hip roof, the ridge that intersects the VR Virtual Reality
Chuiji, see Fig. 2. AR Augmented Reality
MR Mixed Reality
Sandou 散斗 Bearing block, usually placed on the ends of a GIS Geographic Information System
bracket arm to support timbers parallel to the
building plane.
Shengqi 升起 Gradual elevation of the column from the central Received: 19 March 2025; Accepted: 1 July 2025;
bay column to the angular columns on both sides,
see Fig. 3d.
References
Shengtoumu 生 It is a triangular piece of wood between the eave
\1. Wallace, A. B. & Deazley, R. Display At Your Own Risk: An
头木 purlin and the corner eave rafter.
Experimental Exhibition of Digital Cultural Heritage. (Display At Your
Shoufen 收分 The cross-sectionofthecolumngraduallyshrinks Own Risk, 2016).
according to certain rules, see Fig. 3d. 2. Di Giulio, R. et al. Integrated data capturing requirements for 3D
Sunmao 榫卯 Mortise and tenon semantic modelling of cultural heritage: the inception protocol.
https://doi.org/10.5194/isprs-archives-XLII-2-W3-251-2017 (2017).
Wujia 屋架 Bracket set on the upper roof frame 3. Trillo, C., Aburamadan, R., Mubaideen, S., Salameen, D. & Makore, B.
puzuo 铺作 C. N. Towards a systematic approach to digital technologies for
Xiangyan 象眼 The stones on the left and right sides of the heritage conservation. insights from Jordan. Preserv. Digit. Technol.
treadway are stacked inward to form an inward- Cult. 49, 121–138 (2020).
lookingtriangularhole,whichistheXiangyan,see 4. Panah, R. S. & Kioumarsi, M. Application of building information
Fig. 2. modelling (BIM) in the health monitoring and maintenance process: a
systematic review. Sensors 21, 837 (2021).
Xieshan 歇山 Gable and hip roof, see Fig. 2. 5. Khodeir, L. M., Aly, D. & Tarek, S. Integrating HBIM (heritage building
Xumizuo 须 High base with decorated mouldings, the plane is information modeling) tools in the application of sustainable
弥座 usually square, wide at the top and bottom, retroﬁtting of heritage buildings in Egypt. Procedia Environ. Sci. 34,
narrowing in the middle layer by layer, with the 258–270 (2016).
narrowest layer in the middle, called the girdle. 6. Dore, C. & Murphy, M. Semi-automatic modelling of building façades with
shape grammars using historic building information modelling. Int. Arch.
Xuanyu 悬鱼 Located right in the middle of the mountain face
Photogramm. Remote Sens. Spat. Inf. Sci. XL-5-W1, 57–64 (2013).
of the roof, which reinforces the two side
\7. Sztwiertnia, D., Ochałek, A., Tama, A. & Lewińska, P. HBIM (heritage
bofengban, see Fig. 2.
Building Information Modell) of the Wang Stave Church in Karpacz –
Case Study. Int. J. Archit. Herit. 15, 713–727 (2021).

npj Heritage Science | (2025)13:399 19

<!-- p. 20 -->

https://doi.org/10.1038/s40494-025-01926-1 Article

\8. Diara, F. & Rinaudo, F. ARK-BIM: open-source cloud-based HBIM 29. Kang, H., Byun, H. & Lee, J. Parametric modeling technology for
platform for archaeology. Appl. Sci. 11, 8770 (2021). applying Hbim to Korean traditional wooden architecture. Int. Arch.
\9. Kim, S. & Lee, J. A study on the digital restoration of an ancient city Photogramm. Remote Sens. Spat. Inf. Sci. XLVIII-M-2–2023,
based on historic building information modeling of wooden 815–820 (2023).
architectural heritage: focusing on Suwon Hwaseong. Herit. Sci. 12, 30. Xu,F., Zou, Y. & Li, Y. Procedural modelingof historicbuildings’ timber
1–15 (2024). frames for HBIM based on carpenters’ architectural rules. Autom.
\10. Santos, D., Sousa, H. S., Cabaleiro, M. & Branco, J. M. HBIM Constr. 168, 105862 (2024).
application in historic timber structures: a systematic review. Int. J. 31. Meegan, E. et al. Virtual Heritage Learning Environments. in Digital
Archit. Herit. 17, 1331–1347 (2023). Heritage. Progress in Cultural Heritage: Documentation, Preservation,
\11. Antón, D., Medjdoub, B., Shrahily, R. & Moyano, J. Accuracy and Protection (eds. Ioannides, M., Fink, E., Cantoni, L. & Champion,
evaluation of the semi-automatic 3D modeling for historical building E.) 427–437. https://doi.org/10.1007/978-3-030-73043-7_35.
information models. Int. J. Archit. Herit. 12, 790–805 (2018). (Springer International Publishing, 2021).
\12. Andriasyan, M., Moyano, J., Nieto-Julián, J. E. & Antón, D. From point 32. Lee, J., Kim, J., Ahn, J. & Woo, W. Mobile Risk Management for
cloud data to building information modelling: an automatic parametric Wooden Architectural Heritage in Korea using HBIM and VR. in 2018
workﬂow for heritage. Remote Sens 12, 1094 (2020). 3rd Digital Heritage International Congress (DigitalHERITAGE) held
\13. Koo, B., Jung, R. & Yu, Y. Automatic classiﬁcation of wall and door jointly with 2018 24th International Conference on Virtual Systems &
BIM element subtypes using 3D geometric deep neural networks. Multimedia (VSMM 2018) 1–8 https://doi.org/10.1109/
Adv. Eng. Inform. 47, 101200 (2021). DigitalHeritage.2018.8810133 (2018).
\14. Costantino, D., Pepe, M. & Restuccia, A. G. Scan-to-HBIM for 33. Murphy, M. et al. Armagh Observatory—historic building information
conservation and preservation of cultural heritage building: the case modelling for virtual learning in building conservation. Int. Arch.
study of San Nicola in Montedoro church (Italy). Appl. Geomat. 15, Photogramm. Remote Sens. Spat. Inf. Sci. XLII-2-W5, 531–538
607–621 (2023). (2017).
\15. Yang, J., Wang, X., Wu, C. & Bai, C. Regularized reconstruction of grid 34. BrochureBIM2024-1.pdf.
system for traditional chinese timber structure building In Hbim. Int. 35. Guías uBIM. Buildingsmart Spain http://www.buildingsmart.es/
Arch. Photogramm. Remote Sens. Spat. Inf. Sci. XLII-2-W15, recursos/guías-ubim/.
1229–1233 (2019). 36. Herr, C. M. & Fischer, T. BIM adoption across the Chinese AEC
\16. Santini, S., Borghese, V. & Baggio, C. HBIM-based decision-making industries: an extended BIM adoption model. J. Comput. Des. Eng. 6,
approach for sustainable diagnosis and conservation of historical 173–178 (2019).
timber structures. Sustainability 15, 3003 (2023). 37. Kaneta, T., Furusaka, S. & Deng, N. Overview and problems of BIM
\17. Mol, A., Cabaleiro, M., Sousa, H. S. & Branco, J. M. HBIM for storing implementation in Japan. Front. Eng. Manag. 4, 146–155 (2017).
life-cycle data regarding decay and damage in existing timber 38. Park, J. J., Kim, K., Ji, S.-Y. & Jun, H. J. Framework for BIM-based
structures. Autom. Constr. 117, 103262 (2020). repair history management for architectural heritage. Appl. Sci. 14,
\18. Oreni, D., Brumana, R., Georgopoulos, A. & Cuca, B. Hbim for 2315 (2024).
conservation and management of built heritage: towards a library of 39. Penjor, T., Banihashemi, S., Hajirasouli, A. & Golzad, H. Heritage
vaults and wooden bean ﬂoors. ISPRS Ann. Photogramm. Remote building information modeling (HBIM) for heritage conservation:
Sens. Spat. Inf. Sci. II-5-W1, 215–221 (2013). framework of challenges, gaps, and existing limitations of HBIM. Digit.
\19. Liu, H. et al. A method of automatic extraction of parameters of multi- Appl. Archaeol. Cult. Herit. 35, e00366 (2024).
LoD BIM models for typical components in wooden architectural- 40. Habte, B. & Guyo, E. Application of BIM for structural engineering: a
heritage structures. Adv. Eng. Inform. 42, 101002 (2019). case study using Revit and customary structural analysis and design
\20. Youn, H.-C., Yoon, J.-S. & Ryoo, S.-L. HBIM for the characteristics of software. J. Inf. Technol. Constr. 26, 1009–1022 (2021).
Korean traditional wooden architecture: bracket set modelling based 41. Yang, X. et al. Review of built heritage modelling: Integration of HBIM
on 3D scanning. Buildings 11, 506 (2021). and other information techniques. J. Cult. Herit. 46, 350–360 (2020).
\21. Murphy, M. et al. Shape grammar libraries of European classical 42. Klapa, P., Mitka, B. & Zygmunt, M. Application of integrated
architectural elements for historic BIM. in The International Archives of photogrammetric and terrestrial laser scanning data to cultural heritage
the Photogrammetry, Remote Sensing and Spatial Information surveying. IOP Conf. Ser. Earth Environ. Sci. 95, 032007 (2017).
Sciences vol. XLVI–M 479–486 (Beijing, China, 2021). 43. Alshawabkeh, Y. & Baik, A. Integration of photogrammetry and laser
\22. Aburamadan, R. et al. Developing a heritage BIM shared library for two scanning for enhancing scan-to-HBIM modeling of Al Ula heritage
case studies in Jordan’s heritage: the house of art in Amman and the site. Herit. Sci. 11, 147 (2023).
Qaqish House in the world heritage city of As-Salt. Herit. Sci. 10, 196 44. Ulvi, A. Documentation, three-dimensional (3D) modelling and
(2022). visualization of cultural heritage by using unmanned aerial vehicle
\23. Sampaio, A. Z., Pinto, A. M., Gomes, A. M. & Sanchez-Lite, A. (UAV) photogrammetry and terrestrial laser scanners. Int. J. Remote
Generation of an HBIM library regarding a palace of the 19th century in Sens. 42, 1994–2021 (2021).
Lisbon. Appl. Sci. 11, 7020 (2021). 45. Christofori, E. & Bierwagen, J. Recording cultural heritage using
\24. Jiang, Y. et al. Development and application of an intelligent modeling terrestrial laserscanning–dealing with the system, the huge datasets
methodforancientwoodenarchitecture.ISPRSInt.J.GeoInf.9,167(2020). they create and ways to extract the necessary deliverables you can
\25. Yang, S. & Hou, M. Knowledge graph representation method for work with. Int. Arch. Photogramm. Remote Sens. Spat. Inf. Sci. XL-5-
semantic 3D modeling of Chinese grottoes. Herit. Sci. 11, 266 (2023). W2, 183–188 (2013).
\26. Simeone, D., Cursi, S. & Acierno, M. BIM semantic-enrichment for 46. Radanovic, M., Khoshelham, K. & Fraser, C. Geometric accuracy and
built heritage representation. Autom. Constr. 97, 122–137 (2019). semantic richness in heritage BIM: a review. Digit. Appl. Archaeol.
\27. Wang,R.,Sun, W. X. & Zhang,X. Realization methodof theBIM-based Cult. Herit. 19, e00166 (2020).
MingQing ancient architecture model system. J. Donghua Univ.39, 47. Brusaporci, S., Maiezza, P. & Tata, A. A framework for architectural
421–426 (2013). heritage hbim semantization and development. Int. Arch.
\28. Wang, R., Sun, W. X. & Zhang, X. Research on parametric information Photogramm. Remote Sens. Spat. Inf. Sci. XLII–2, 179–184 (2018).
model of ancient buildings of Ming and Qing dynasties. J. Xi’ Univ. 48. Liu, D. Collected Works of Liu Dunzhen, Vol. 2. (China Architecture &
Archit. Technol.45, 479–486 (2013). Building Press, 1984).

npj Heritage Science | (2025)13:399 20

<!-- p. 21 -->

https://doi.org/10.1038/s40494-025-01926-1 Article

\49. He, Y. et al. Research on Architectural History. (China Architecture & 69. Dore, C. & Murphy, M. Current state of the art historic building
Building Press, 1992). information modelling. Int. Arch. Photogramm. Remote Sens. Spat.
\50. Wang, H. An explain how to building technology in Jiangnan area Inf. Sci. XLII-2-W5, 185–192 (2017).
affected the book yingzao fashi in the Light of Chuzhuan Temple. 70. N.Panayiotou, P. & Kontovourkis, O. A holistic documentation and
Huazhong Architecture. 104–107 https://doi.org/10.13942/j.cnki. analysis of timber roof structures in heritage buildings using scan to
hzjz.2003.03.035 (2003). HBIM approaches. in 715–724 (Nicosia,). https://doi.org/10.52842/
\51. Zhang, S. Analysis of the phenomenon of the main temple Hall of the conf.ecaade.2024.1.715 (2024).
Chuzu An Nunnery. Hist. Archit. 84, 89 (2006). 71. Yang, X., Koehl, M. & Grussenmeyer, P. Parametric modelling of as52. Yu, M. On the segmented column style Tingtang framework during built beam framed structure in Bim environment. Int. Arch.
Song and Jin Dynasty. Huazhong Archit. 34, 143–146 (2016). Photogramm. Remote Sens. Spat. Inf. Sci. XLII-2-W3, 651–657
\53. Liu, C. & Sun, C. Interpretation of survey data from the main hall of (2017).
Chuzu Temple of Shaolin Temple. J. Chin. Archit. Hist. 129, 157 72. Tan, J., Leng, J., Zeng, X., Feng, D. & Yu, P. Digital twin for Xiegong’s
(2009). architectural archaeological research: a case study of Xuanluo Hall,
\54. Fu, X. Research on Ancient Chinese Urban Planning, Architectural Sichuan, China. Buildings 12, 1053 (2022).
Complex Layout, and Architectural Design Methods, Vol. 1, 2nd edn. 73. Yang, X., Koehl, M. & Grussenmeyer, P. Automating parametric
(China Architecture & Building Press, 2015). modelling from reality-based data by Revit Api Development. in Latest
\55. Tong, L. & Liu, C. Study on structureproperties of Timber Frame Load- Developments in Reality-Based 3D Surveying and Modelling (MDPI,
bearing System of the Chu Zu-an Temple. Struct. Eng. 34, 9–15 2018).
(2018). 74. Martinelli, L., Calcerano, F. & Gigliarelli, E. Methodology for an HBIM
\56. Liu, Y. et al. Quasi-static experiment on bracket complexes model of workﬂow focused on the representation of construction systems of
the main hall of the ancestor’s monastery in Shaolin Temple. J. For. built heritage. J. Cult. Herit. 55, 277–289 (2022).
Eng. 6, 46–53 (2021). 75. Cavalliere, C., Dell’Osso, G. R., Favia, F. & Lovicario, M. BIM-based
\57. Yao, Z. et al. Statusinvestigationanddamage analysisof thedougong assessment metrics for the functional ﬂexibility of building designs.
under the external eaves of the main hall of Chuzu Temple in the Autom. Constr. 107, 102925 (2019).
Shaolin Temple Complex. BioResources 14, 4110–4123 (2019). 76. Martín-Lerones, P., Olmedo, D., López-Vidal, A., Gómez-García58. Godinho, M. et al. BIM as a resource in heritage management: An Bermejo, J. & Zalama, E. BIM supported surveying and imaging
application for the National Palace of Sintra, Portugal. J. Cult. Herit. combination for heritage conservation. Remote Sens 13, 1584 (2021).
43, 153–162 (2020). 77. López, F. J., Lerones, P. M., Llamas, J., Gómez-García-Bermejo, J. &
\59. Stefano BrusaporciAlessandra Tata, & Pamela Maiezza. The ‘LoH - Zalama, E. A framework for using point cloud data of heritage
Level of History’ for an Aware HBIM Process. in 42th international buildings toward geometrymodeling in a BIM context: a case studyon
conference of representation disciplinesteachers. Congressof unione Santa Maria La Real De Mave Church. Int. J. Archit. Herit. 11, 965–986
italiana per il disegno. Proceedings 2020. Linguaggi, distanze, (2017).
tecnologie (FrancoAngeli srl,). https://doi.org/10.3280/oa-693.117. 78. De Luca, L., Busayarat, C., Stefani, C., Véron, P. & Florenzano, M. A
(2021). semantic-based platform for the digital analysis of architectural
\60. Salah, R. A structured framework for HBIM standardization: heritage. Comput. Graph. 35, 227–241 (2011).
integrating scan-to-BIM methodologies and heritage conservation 79. Biagini, C., Capone, P., Donato, V. & Facchini, N. Towards the BIM
standards. (2025). implementation for historical building restoration sites. Autom.
\61. Tang, L. et al. An application-driven LOD modeling paradigm for 3D Constr. 71, 74–86 (2016).
building models. ISPRS J. Photogramm. Remote Sens. 161, 194–207 80. Guo, L. et al. Digital preservation of classical gardens at the San Su
(2020). Shrine. Herit. Sci. 12, 66 (2024).
\62. Chow, L. et al. The evolution of modelling practices on Canada’s 81. Moropoulou, A., Labropoulos, K. C., Delegou, E. T., Karoglou, M. &
parliament hill: an analysis of three signiﬁcant heritage building Bakolas, A. Non-destructive techniques as a tool for the protection of
information models (Hbim). Int. Arch. Photogramm. Remote Sens. built cultural heritage. Constr. Build. Mater. 48, 1222–1239 (2013).
Spat. Inf. Sci. XLII-2-W11, 419–426 (2019). 82. Chiabrando, F., Sammartano, G. & Spanò, A. Historical buildings
\63. Castellano-Román, M. & Pinto-Puerto, F. Dimensions and levels of models and their handling via 3D survey: from points clouds to user-
knowledge in heritage building information modelling, HBIM: the oriented Hbim. Int. Arch. Photogramm. Remote Sens. Spat. Inf. Sci.
model of the Charterhouse of Jerez (Cádiz, Spain). Digit. Appl. XLI-B5, 633–640 (2016).
Archaeol. Cult. Herit. 14, e00110 (2019). 83. Banﬁ, F. HBIM, 3D drawing and virtual reality for archaeological sites
\64. Bagnolo, V., Argiolas, R. & Cuccu, A. Digital survey and algorithmic and ancient ruins. Virtual Archaeol. Rev. 11, 16–33 (2020).
modeling in HBIM. Towards a library of complex construction 84. Matrone, F., Colucci, E., De Ruvo, V., Lingua, A. & Spanò, A. Hbim in a
elements. Int. Arch. Photogramm. Remote Sens.Spat. Inf. Sci. XLII-4- Semantic 3d Gis database. Int. Arch. Photogramm. Remote Sens.
W12, 25–31 (2019). Spat. Inf. Sci. XLII-2-W11, 857–865 (2019).
\65. Murphy, M., McGovern, E. & Pavia, S. Historic building information 85. Arroyo Ohori, K. et al. Towards an integration of Gis and Bim data:
modelling (HBIM). Struct. Surv. 27, 311–327 (2009). What are the geometric and topological issues?. ISPRS Ann.
\66. Moyano, J., León, J., Nieto-Julián, J. E. & Bruno, S. Semantic Photogramm. Remote Sens. Spat. Inf. Sci. IV-4-W5, 1–8 (2017).
interpretation of architectural and archaeological geometries: point
cloud segmentation for HBIM parameterisation. Autom. Constr. 130, Acknowledgements
103856 (2021). This project was supported by the following research projects: Key
\67. Pierdicca, R. et al. Point cloud semantic segmentation using a deep Research Funding of Henan Province (Project NO. 231111520800), the
learning framework for cultural heritage. Remote Sens 12, 1005 National Natural Science Foundation of China (No. 52208037), the
(2020). University Scheme of Social Sciences Research Fund of Henan
\68. León-Robles, C. A., Reinoso-Gordo, J. F. & González-Quiñones, J. J. Province (No. 2025-ZZJH-354) and the Open Research Fund of the
Heritage building information modeling (H-BIM) applied to a stone National Cultural Heritage Administration Key Scientiﬁc Research Base
bridge. ISPRS Int. J. Geo-Inf. 8, 121 (2019). (No. 2024CKBKF04).

npj Heritage Science | (2025)13:399 21

<!-- p. 22 -->

https://doi.org/10.1038/s40494-025-01926-1 Article

Author contributions Open Access This article is licensed under a Creative Commons
J.Z., H.L. and S.Y. proposedthe overall modeling scheme, carried out model Attribution-NonCommercial-NoDerivatives 4.0 International License,
creation, and wrote the paper. L.Z. and W.Z. completed the virtual which permits any non-commercial use, sharing, distribution and
presentation part, and Y.L. and X.W. carried out the pre-information col- reproduction in any medium or format, as long as you give appropriate
lection and model construction. All authors reviewed the manuscript. credit to the original author(s) and the source, provide a link to the Creative
Commons licence, and indicate if you modiﬁed the licensed material. You
Competing interests do not have permission under this licence to share adapted material
The authors declare no competing interests. derived from this article or parts of it. The images or other third party
material in this article are included in the article’s Creative Commons
Additional information licence, unless indicated otherwise in a credit line to the material. If material
Correspondence and requests for materials should be addressed to isnot includedin thearticle’s CreativeCommons licenceandyour intended
Shanshan Yao or Hongyi Lyu. use is not permitted by statutory regulation or exceeds the permitted use,
you will need to obtain permission directly from the copyright holder. To
Reprints and permissions information is available at view a copy of this licence, visit http://creativecommons.org/licenses/byhttp://www.nature.com/reprints nc-nd/4.0/.

Publisher’s note Springer Nature remains neutral withregardtojurisdictional © The Author(s) 2025
claims in published maps and institutional afﬁliations.

npj Heritage Science | (2025)13:399 22
