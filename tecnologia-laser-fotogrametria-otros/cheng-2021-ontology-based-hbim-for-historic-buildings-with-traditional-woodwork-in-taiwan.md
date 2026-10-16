---
type: libro
title: "Cheng 2021 - Ontology-based HBIM for historic buildings with traditional woodwork in Taiwan"
author: ""
categoria: "Tecnología láser, fotogrametría, otros"
paginas: 18
extraccion: "texto"
fuente: "local:E:/DISCIPLINAS, TEXTOS Y MAPAS/Biblioteca digital/Tecnología láser, fotogrametría, otros/Cheng 2021 - Ontology-based HBIM for historic buildings with traditional woodwork in Taiwan.pdf"
convertido: 2026-10-14
---

# Cheng 2021 - Ontology-based HBIM for historic buildings with traditional woodwork in Taiwan

> Texto extraído de `Tecnología láser, fotogrametría, otros/Cheng 2021 - Ontology-based HBIM for historic buildings with traditional woodwork in Taiwan.pdf` (18 páginas, texto). El PDF original está en el disco E: (DISCIPLINAS, TEXTOS Y MAPAS\Biblioteca digital); `<!-- p. N -->` marca el inicio de cada página.

<!-- p. 1 -->

Journal of Civil Engineering and Management
ISSN 1392-3730 / eISSN 1822-3605
2021 Volume 27 Issue 1: 27–44
https://doi.org/10.3846/jcem.2021.14115

ONTOLOGY-BASED HBIM FOR HISTORIC BUILDINGS
WITH TRADITIONAL WOODWORK IN TAIWAN

Ying-Mei CHENG1*, Chiao-Ling KUO2, Chia-Ching MOU1

1Civil Engineering and Hazard Mitigation, China University of Technology, Taipei 116, Taiwan
2Research Center for Humanities and Social Sciences, Academia Sinica, Taipei 115, Taiwan

Received 9 April 2020; accepted 27 November 2020

Abstract. In recent years, the use of Historic Building Information Modeling (HBIM) has grown prevalent and thus pro-
vided a research opportunity. Differing from newly constructed buildings, structural components of historic buildings
come with unique physical configurations and have amassed impressive amount of restoration data, all of which must be
taken into consideration when incorporating Building Information Modeling. In terms of modelling, it is critical to deter-
mine the appropriate level of detail (LoD), level of information (LoI), especially the comprehensiveness and expandability
of the database. International Committee for Documentation/Conceptual Reference Model (CIDOC CRM) is a widely ac-
cepted standard for ontology model. This study aims to integrate the HBIM and CIDOC CRM to construct a framework
and comprehensive operational procedure for the modeling of traditional Minan architecture and a database with complete
semantics archiving the background and restoration data. Autodesk A360 is ideal for collaborative. However, there are
limitations when it comes to developing advanced models for data management or query; interactive experience; meeting
model applications derived from future scenarios. Therefore, the study also offers a 3D modeling platform constructed us-
ing Unity, as well as a comparison of the platforms built with Unity, three.js and Autodesk A360 as a reference for users.
Keywords: HBIM, CIDOC CRM, historic building, conservation, semantic data, ontology.

Introduction
Every year, UNESCO singled out natural and cultural original shape and material of certain building elements,
landmarks from around the world because of their “out- the restoration techniques applied, the backgrounds of
standing universal value” to humanity (UNESCO, 2020). the artisans, and so on. In recent years, advancement in
International conventions such as “Convention Concern- BIM technology has enhanced the ability of public and
ing the Protection of the World Cultural and Natural Heri- private entities to handle the complexity and diversity of
tage” are giving these heritage sites more attention and projects involving digitally archiving historic building reprotection to keep them safe from destruction. Each year, cords. Logothetis et al. (2015) presented a review of the
countries around the world are trying to win the world use of BIM in the field of cultural heritage documentaheritage site designation for their cultural or heritage sites tion. They concluded that the diversity and complexity of
from UNESCO. However, this designation cannot keep BIM technology is obvious in many different fields, such
them safe from manmade or natural disasters such as the as environment, buildings, construction, monument, and
devastating fires at Notre Dame Cathedral in Paris and structure framework. BIM also integrates both tangible
Gusuku Sites and Related Properties of the Kingdom of and intangible values as well as external documents into
Ryukyu in Japan in 2019. Rapid technological develop- a single model, which serves as a central hub for all inment has put digital conservation technology in a vital po- formation relating to a historic asset (Antonopoulou &
sition when it comes to the preservation of historic build- Bryan, 2017). Fadli and AlSaeed (2019) even went as far as
ings. Such technology is capable of digitally maintaining designing and establishing the nationwide Qatar Historirestoration/reconstruction data, which can be accessed in cal Buildings Information Modeling (Q-HBIM) platform.
the event that a historic building is destroyed. The data- Many recent studies explore the use of digital technolbase developed may contain information pertaining to the ogies in conserving cultural heritage. Historic Building In-

\*Corresponding author. E-mail: yingmei.cheng@msa.hinet.net

Copyright © 2021 The Author(s). Published by Vilnius Gediminas Technical University

This is an Open Access article distributed under the terms of the Creative Commons Attribution License (http://creativecommons.org/licenses/by/4.0/), which permits unrestricted use, distribution, and reproduction in any medium, provided the original author and source are credited.

<!-- p. 2 -->

28 Y.-M. Cheng et al. Ontology-based HBIM for historic buildings with traditional woodwork in Taiwan

formation Modeling (HBIM) is a widely recognized modeling approach which integrates 3D models (elements/
components) with construction information such as the
shape and size of each element, the background of historic
buildings and the expertise of the artisans with a focus on
the consistency between historic building information and
the 3D parametric model. It can be applied toward documenting materials and construction techniques, providing
assistance in the management of conservation efforts as
well as the restoration/reconstruction of historic buildings
in cases where past records are poorly maintained or no
longer in existence. However, the use of this new technology is not without challenges. First, simply trying to
digitally document the historic building may be met with
obstacles. Due to human or natural factors, the structure
may have been modified multiple times and appear far Figure 1. Research process and phased outcomefrom similar to the original design. Therefore, the modeling efforts must involve advanced technology with high
level of precision and detail such as laser scanning and sults are shown in Figure 1, and the details are provided
photogrammetry accompanied with thorough literature below:
review. The second challenge arises when trying to sys- 1. The study proposes the application of ontologytematically define each element in a historic building with based HBIM to establish comprehensive framework
proper semantics, and to establish and integrate the rela- and operational procedure for the conservation of
tionship between the building elements and relevant in- traditional Minan structure.
formation. In other words, it is critical to apply the HBIM 2. Huangxi Academy from central Taiwan is chosen
technology to simultaneously record both geometric and as the case study. Its wooden building components
non-geometric information. Volk et al. (2014) found sev- are disassembled and categorized in a systematic
eral challenges of BIM. Extracted here are some points format with characteristics of each component anawhich converge with the perspective presented in this lyzed. HBIM is then used to establish the compopaper: 1) the automation of creating BIM (without pre- nent library in the building information model and
existing BIM) and capturing the data; 2) undefined LoD to complete the 3D model for the entire historic
for deconstruction functionalities; 3) the maintenance and building.
update of information in BIM. This paper aims to provide 3. CIDOC CRM is used as the reference to create the
solutions that address these challenges. ontological model. The model integrates the historic
Having been colonized by the Dutch and Spanish in building information model and restoration records
the 17th century, ruled by the Kingdom of Tungning and on the historic building components to complete the
Qing Dynasty from the late 17th century to early 20th cen- database framework containing background and
tury, and occupied by the Japanese in the first half of the restoration information.
20th century, Taiwan, the island nation, is left with many 4. To meet different requirements for different modhistoric structures. Based on the 2019 statistics from the eling approaches, different 3D browsing platforms
Ministry of Culture, there are a total of 941 historic mon- may be needed. The ultimate goal for this study is
uments in Taiwan, including ancestral shrines, temples, to establish the database with a 3D browsing platchurches and fortresses. Each comes with different struc- form using Unity and three.js. A comparison of
tural framework and characteristics. This paper focuses on platforms created with Unity, three.js and Autodesk
a particular branch of traditional structure, the Minan- A360 (https://a360.autodesk.com/) is conducted to
style wooden structure, whose origin can be traced to provide recommendations for choosing the proper
the southern Fujian province in China, and has become platform to search for background information and
symbolic of historic buildings in Taiwan. HBIM is used to restoration records on building components.
construct the model for historic building information and Researchers continue to make progress in the inInternational Committee for Documentation/Conceptual novation of automated and semi-automated modeling:
Reference Model (CIDOC CRM) serves as the blueprint Tang et al. (2010) dealt with as-built BIM; Thomson and
to systematically establish the ontology for historic build- Boehm (2015) worked on BIM from point clouds; Barazings, background information and restoration database. zetti (2016) used point cloud data for heritage modelling;
Lastly, a 3D browsing platform for modeling information Antón et al. (2018, 2019) focused on the semi-automatic
is established to provide a comprehensive narrative for as-built modelling for HBIM and accurate analyses; and
the complete framework and operational procedure that Moyano et al. (2020) applied HBIM to create parametric
the conservation of traditional Minan wooden structures objects in archaeology (A-BIM). Boeykens et al. (2012)
should be equipped with. The objectives and phased re- noted that “virtual reconstruction itself is not new”. They

<!-- p. 3 -->

Journal of Civil Engineering and Management, 2021, 27(1): 14–26 29

concluded that the modeling process is influenced by per- the complete process from extracting the 3D point cloud
sonal decisions, experience and expertise. Research ob- to establishing a well-structured 3D digital model with
jectives 1 and 2 proposed the comprehensive framework rich semantics. Basilica di Santa Maria di Collemaggio in
and operational procedure for regional historic buildings L’Aquila AQ, Italy is the first HBIM case utilizing advanced
and established a component library for such buildings. 3D measurement. The parametric modeling improved
During the process, the complexity of traditional Minan the quality and management during the restoration efbuilding structure must be taken into consideration. That forts after the 2009 earthquake (Barazzetti et al., 2014).
includes how the building structure is disassembled and Brumana et al. (2014) utilized drone video, laser scancomponents defined. For example, if the definition of the ning and Revit (https://www.autodesk.com/products/revit/
component unit is too small, the modeling process will overview) to conduct post-earthquake maintenance and
be time-consuming. On the other hand, if the definition conservation for Basilica Santa Maria di Collemaggio, and
is too large, the model may fail to provide the necessary adopted NURBS to build the models for the north wall.
information for reconstruction. Therefore, research ob- Meanwhile, the structural software, MIDAS, is applied to
jectives 1 and 2 are expected to strike a balance between run the Finite Element Method in order to understand
the completeness of and the time spent on modeling. The the effects that the earthquake has on the particular comcomponent library can also be used for subsequent model- ponent. Nieto Julián et al. (2016) used Palace of Charles
ing. Further research into HBIM is with the incorporation V as a case study and built a model using laser scanning
of ontology (Acierno et al., 2017; Quattrini et al., 2017; and ARCHICAD. The study demonstrates the use of point
Dezen-Kempter et al., 2018; Yen & Lu, 2019; Previtali cloud and ARCHICAD to document the maintenance
et al., 2020). Scholars focusing on CIDOC CRM, such as records for sculpted bricks and tiles. Chiabrando et al.
Dezen-Kempter et al. (2018), Yen and Lu (2019), Previ- (2016) studied the town, Pollenzo. Using laser scanning,
tali et al. (2020), point out that HBIM information can the research builds the model using the plug-in of Revit to
be presented more comprehensively and systematically extract the contour of the point cloud semi-automatically,
with CIDOC CRM. Research objective 3 aims to com- and construct a model with complicated curvatures with
plete the database framework for background and resto- ARCHIDCAD. Dhanda et al. (2017) analyzed and comration information for the historic building components pared the characteristics of the common modeling simulausing CIDOC CRM. Yen and Lu (2019) once discussed tion software. In addition, a small number of studies menHBIM with LoI (Level of Information) for the life cycle of tioned the significance of information in HBIM. For inhistoric buildings from a conceptual and top-down per- stance, Han et al. (2017) point out that HBIM can be used
spective. Yen and Lu (2019) divide the life cycle into 3 as the framework of index for tangible cultural heritage.
phases – Investigation/Designation; Rehabilitation; Man- Banfi (2017) stresses that the development of BIM mainly
agement. According to their definition, objective 3 ad- gears toward the establishment of information managedresses phases I and II from a bottom-up perspective, and ment system, as well as the importance of new concepts
pays more attention to the modeling process and the con- such as Grade of Generation (GoG), Grade of Informanection between the components and semantic data. The tion (GoI) and Grade of Accuracy (GoA). Brumana et al.
intent of objective 4 is to create a 3D browsing platform (2013) utilize LiDAR and photogrammetry to reconstruct
with Unity. However, considering the fact that Logothe- historic buildings. Aside from building the 3D models,
tis and Stylianidis (2016) once encouraged the utilization the approach takes the historic information of the historic
of open source software (OSS) for documenting cultural buildings into consideration, and include them in HBIM.
heritage, and the accessibility and convenience offered by Fregonese et al. (2015) use LiDAR scan for the modeling
Autodesk A360, a comparison is also offered in this study of historic buildings and separate that from the attributes.
to evaluate platforms generated with 3 different software The component attribute information (basic attributes in
options – Unity, three.js and Autodesk A360. The paper Revit) is saved in the database for future applications and
is organized as follows: Section 1 – literature review; Sec- editing, and BIM3DSG is used to view the 3D model. The
tion 2 – methodology; Section 3 – case study (Huangxi attribute database is plugged into BIM3DSG to display
Academy); Section 4 – application of HBIM in Huangxi datasets for both the model and attributes. However, the
Academy; last section – conclusion. attributes here refer to the basic component information
rather than cultural attributes. Acierno et al. (2017) pro-
pose that there is a connection between the subject and1. Literature review ontology for the study on architectural heritage. There
There are quite a number of HBIM-related studies around are four domains – Artefact Domain, Artefact Lifecycle
the world, including Murphy et al. (2009), Banfi (2017), Domain, Architectural Heritage Investigation Process
Banfi et al. (2017), Pöchtrager et al. (2017) and Barazzetti Domain and Actors Domain. It is evident that comparing
et al. (2017). Most of them focus on ways of accelerating to newly constructed buildings, information concerning
the construction of the 3D model for historic buildings historic buildings or architectural heritage are much more
with higher precision. Hichri et al. (2013) indicates that in complicated. In addition to architectural and civil engiorder to establish a highly effective digital presentation of neering professionals, experts in archeology, medicine,
a historic building, it is crucial to analyze and comprehend chemistry and biology are also involved. Antonopoulou

<!-- p. 4 -->

30 Y.-M. Cheng et al. Ontology-based HBIM for historic buildings with traditional woodwork in Taiwan

and Bryan (2017) offered a guidance for owners, end-users ure 3. The upper part is the so-called reverse-engineering
and professionals in the fields of heritage and construc- modeling process, which generally includes the following
tion by raising awareness of the potential advantages of a tasks: 1) Data capture; 2) Segmentation of point clouds;
BIM approach. In the 2018 paper on the review of HBIM, 3) Classification of the regions identified in the segmentaLópez et al. (2018) mentioned “only a few research deals tion step; and 4) Reconstruct the 3D model (Buonamici
with the automation of the reverse engineering process, et al., 2018), while the conventional modeling approach
as well as the processes of interoperability, management, (bottom half of Figure 3) is called the top-down modeldocumentation, and maintenance of the ‘as-is model’ ing approach, which completes floor plans and elevations
building”. in CAD through the traditional surveying and drawing
method, and CAD separates the individual components
to be imported into Revit to construct the components2. Methodology for historic buildings. Currently, many scholars have proIn addition to establishing the component library of his- posed semi-automatic as-built approaches, hoping to obtoric buildings with a systematic approach, the study also tain accurate 3D models more effectively to represent the
establishes an ontological model and database for back- actual protection status of historic buildings so that these
ground information as well as restoration records for his- assets can be accurately analyzed. However, the emphasis
toric buildings. A browsing platform for the 3D model is of this study is to systematically deconstruct the historic
then completed to provide a comprehensive discourse of building structure into independent components carrythe framework and operational procedure, which can be ing their own background and restoration information,
which does not require a high LoD. In the case of build-representative of projects dealing with the conservation
ing exteriors, the details can be better presented throughof traditional Minan style wooden structures. The mod-
a linked image or video. Nevertheless, a minimum LoDeling flow chart, methods and tools are shown in Figure 2.
for the structural components must be maintained. BasedThe methodology and tools applied for each stage are de-
on general requirements for the LoD of BIM models inscribed in the following sections.
AEC, LoD 300 is chosen to build the 3D model using the
manual theoretical modeling approach. At LoD 300, the2.1. 3D Modeling geometric shapes of the components can be clearly idenRegular 3D modeling process can be done through the tified and do not need to meet the fineness requirements
conventional surveying and drawing, and with the help of for construction drawings or other applications which
laser scanning. The drafting process is illustrated in Fig- require further analysis. The study utilizes Revit and the

Figure 2. Modeling flow chart, methods and tools

Figure 3. 3D modeling procedure

<!-- p. 5 -->

Journal of Civil Engineering and Management, 2021, 27(1): 14–26 31

conventional modeling approach to integrate the model formats. In particular, support the automatic data
with a point cloud file in order to identify the spatial loca- conversion from local data structure to global data
tion of the components. During the modeling process, the structure without losing its meaning.
parametric component library is also established for the 4. Support queries related to resource integration
wooden structures. through the integration of basic classes and con-
nected global model.
2.2. Ontology and CIDOC CRM The ontology established through the form and struc-
ture of CRM is expandable. Users from various fields mayIt is crucial to determine ways of systematically integrat-
establish and expand the ontological model to fit the needsing and establishing 3D models for historic buildings and
tailored to certain fields. In order to connect with the in-maintaining the information, especially for presenting descriptions of restoration and restoration records individual ternational community, this study adopts standardized
on building components of traditional architecture. The ontological model based on CIDOC CRM to establish
adoption of ontology is essential in order to present the the model for historic Minan wooden structures. It is the
information in a methodical and comprehensive manner hope to more effectively document and present cultural
and connect to the global communities by using the com- information related to the historic building. Currently,
mon language, and to ensure pertinent updates as time Protégé, which is developed by Stanford University, is the
progresses. Ontology is typically applied toward deduc- most commonly used tool for establishing the ontological
tive reasoning regarding the attributes of a field in which model. The software, which is applied in multiple fields, is
one is interested. It can also be applied toward defining a capable of establishing massive visual ontological models
specific field for which the model is established. For on- with various presentation formats. This is helpful towards
tological models, CIDOC CRM (http://www.cidoc-crm. the understanding of connections among components.
org/) is a widely accepted and promoted standard. It is Protégé is the software of choice for establishing the ontoable to expand the standardized ontological model and logical model in this study.
has received ISO 21127:2006 certification in 2006 (International Organization for Standardization [ISO], 2006), 2.3. Database and query platform
which was revised in 2014 (ISO, 2014). It can be regarded
as the common language shared among the field experts Prior to establishing the database, several interviews were
and implementers. conducted with field experts. The interviews were held in
CIDOC CRM is the conceptual reference model es- the form of official advisory meetings with 4 to 8 experts
tablished by the International Committee for Documenta- invited to each meeting. These experts include architects
tion (CIDOC) under International Council of Museums who have been in the field of historic preservation for
(ICOM). It is a formal ontology intended to facilitate the more than 10 years; contractors specializing in conservaintegration, mediation and interchange of heterogeneous tion of historic structures; university professors who have
cultural heritage information. The intent is to allow for ex- conducted years of research in the field of ontological
change and integration of information on heterogeneous methodology. The experts discussed several issues during
cultural heritage among different countries and different each project stage, including the definitions of architeclanguages, providing definition for languages and catego- tural components and their names; ways of deconstructries so that regionalized information can be transformed ing the components; information to be embedded within
into universal resources across the globe. Specifically, the components; the framework of CIDOC CRM. After
formal ontology defines and limits the basic semantics of each meeting concluded, expert opinions were compiled
the database model and document structure used within with project modification made accordingly. Additionally,
cultural heritage and museum documents. Its objective is restoration reports of historic wooden buildings are also
not to propose the content that cultural institutions should referenced to classify the historic building information
document. Rather, it explains the logic behind the docu- and establish the relation structure of the data sets. Key
mentation, which in turn realized the interoperability of comments provided by field experts are stated below:
the semantics. CRM is meant to support the specific func- 1. The components are titled with terms currentlytions below (ICOM/CIDOC, 2019): used in Taiwan, including Minan and Hakka terms. 1. Serve as guidelines for developers of the informa- Terms used in China and historical terms from the tion system for best practice of conceptual modeling Song and Qing dynasties are not included in this to effectively construct and connect information re-
paper. lated to cultural heritage.
\2. The components are classified based on how the 3D 2. Serve as the common language for field experts and
model will be integrated. The components are cat- IT developers, and enable them to have accurate un-
egorized based on functions first, and divided into derstanding of the relevant cultural information as
vertical and horizontal components from bottom to well as be consistent in terms of identifying needs
and establishing system functions. the top. Identical components may receive alterna-
\3. Serve as the official language for identifying com- tive names when the form varies. To avoid confu-
mon information content among different data sion, the alterative names are not considered.

<!-- p. 6 -->

32 Y.-M. Cheng et al. Ontology-based HBIM for historic buildings with traditional woodwork in Taiwan

\3. Deficiencies of the field functions should be ad- 3. Case study
dressed to cover both practical and theoretical pur-
Huangxi Academy` is the oldest structure remaining in poses. Subforms should be provided for attributes,
Dadu District of Taichung, Taiwan. Being the cultural and such as construction methods, tools and materials.
educational center of the community in the past, Huangxi The worksheets can be linked through key values to
Academy has over 130 years of history. The construction perform crosstab query afterwards.
of Huangxi Academy was commissioned to artisans from 4. The LOD of a model can be affected by human fac-
the so-called San-yi region (Jingjiang, Nanan, Huian) tors at times. Models of several structural compo-
in Quanzhou, China. The architecture is representative nents commonly used for traditional Minan struc-
of the Huian style during the late Qing dynasty (1633– tures have been created for this study, and they can
1912), which is characterized by the enclosed courtyard be applied towards other projects simply by modi-
layout. Its significance in terms of architectural heritage fying internal parameters to minimize human-in-
is paramount. Intricate craftsmanship can be found in the duced discrepancies. In the future, more common
construction materials, styles and techniques. The tradi- component models will be created to make this
methodology more widely accepted. tional building has a double-square layout and a courtyard
\5. LoI should be changed to LoD to explore differences separating the front and back. The width of the building
among different levels, the content to be included, is about 28 meters. The depth is approximately 30 me-
and how to determine corresponding descriptions ters. The spatial layout starting from the outside includes
for the components as well as background or resto- shanman (front gate), courtyard, baidian (hall of worship),
ration information. main hall (lecture hall), east and west chambers, and con-
Typically, one can add attributes/information needed necting hallways. Building materials include red brick
during building restoration to the newly added elements tiles, granite, bluestone and China-fir. The spatial layout
while creating 3D models with Autodesk Revit. As the and current status of Huangxi Academy is shown in Figmodeling process completes, so does the restoration da- ure 4. The main structures include the main hall and hall
tabase. In Revit, each element is assigned a unique code, of worship. The details are described as follows:
which is what links the attributes/information and the el- 1. Front gate (shanman): Shanman refers to the enement itself. When the completed 3D model is uploaded try gate of a Buddhist temple. It is also known as
to A360, the query function is ready. As a user-friendly “three gates (also pronounced ‘shanman’ in Mandasoftware, Autodesk A360 is ideal for collaborative tasks rin)”. In Buddhism, the term is a metaphor for the
where members across all teams may review the same 3D three ways (gates) that lead to liberation – liberation
model or examine information pertaining to certain struc- through emptiness (sunyata), liberation through the
tural components. However, the scope of query conducted absence of perpetual attributes (animitta), and libby directly clicking the elements on a 3D model is limited. eration through wishlessness (apranihita).
The lack of data structure and planning cannot accom- 2. Hall of worship (baidian): In Taiwanese temples,
modate querying functions across multiple applications. baidian refers to the structure directly in front of
Additionally, attaching the attributes directly onto the el- the main hall where the main presiding deity is worement ID may lead to overly large files that run the risk shipped.
of causing system crash during the query process. Due 3. Main hall (lecture hall): Main hall refers to the
to these reasons, the authors attempt to establish a sepa- structure centrally located within a palatial or temrate database and browsing platform for the restoration ple complex. It is where the main presiding deity
records rather than constructing the database in the same is placed. It is also typically the tallest and largest
Revit file, which may be cumbersome to the maintenance structure within the complex.
efforts or future expansion. It is also the hope that in addi- 4. East and west chambers: In a residential complex,
tion to conducting data browsing through the 3D model, the east and west chambers are two symmetric rows
the model may also accommodate basic data query. of structures built on each side of and parallel to
The information platform for the 3D model is devel- the main central axis. They are used mostly as the
oped with Unity and three.js. Unity is an inter-platform kitchen or sleeping quarters for the more junior
game engine used to develop single player games for Win- members in the family. The Hakka calls them heng
dows, MacOS and Linux systems, or iOS and Android wu (horizontal structure). In Kinmen and Punghu
mobile systems. Three.js is a cross-browser script that areas, they are referred to as ju tou (side chambers).
uses JavaScript function libraries or APIs to create and 5. Connecting hallways: The connecting hallways refer
display animated 3D computer graphics in a web browser. to the pathways connecting the main hall and huTWAMP is used to develop the database for the 3D model long (wing), or between various wings. Sometimes
of Huangxi Academy. TWAMP provides phpMyAdmin, a they are structured like a pavilion, which allows
PHP-based database management tool constructed on the the water to pass through underneath and provides
mainframe in a web-based format. It allows administrators shelter from the rain. It is also referred to as Guto manage MySQL database through the web interface. oshui Ting (Passing Water Pavilion).

<!-- p. 7 -->

Journal of Civil Engineering and Management, 2021, 27(1): 14–26 33

Figure 4. Spatial layout and current status of Huangxi Academy

In 1984, Dadu Township Office in Taichung County 4.1. Component library and
commissioned Han Guang Architectural Firm to conduct 3D model for case study
the first survey study on Huangxi Academy. The first res- The market offers many BIM options, among which aretoration project undertaken by Han Guang Architectural Autodesk Revit, Tekla and ArchiCAD. Each comes withFirm took place between 1986 and 1989. In 2000, the Min-
unique characteristics and functions. Revit, which is builtistry of the Interior approved the funding for restoration.
with the grouping concept, offers comprehensive func-And the restoration of the hall of worship and the main
tions, such as defining attributes, which is helpful for re-hall was conducted by Cultural Affairs Bureau, Taichung
cording restoration information. Autodesk also providesCounty in 2002. The roof over shanmen (front gate) was
A360, which offers a common platform for multiple teamrestored between 2005 and 2006. After three survey and
members to collaborate on and management the samerenovation projects, Huangxi Academy finally returns to
project on the cloud, making it easier for users to browseits formal glory. The historic building has significant his-
through background information from the Revit 3D mod-toric and architectural values, and is a precious cultural
el. Revit has been chosen to create the components andheritage. The restoration records are listed in Table 1 (Yen,
3D model for this project, in which, RFA files are family2018; National Cultural Heritage Database Management
files that can either be uploaded into a project or savedSystem, 2020).
externally. This is a crucial quality for building component
libraries that can be applied toward similar projects.
\4. Application Historic wooden structures consist of large numbers
To study Huangxi Academy, onsite surveys historical re- of building components, which are classified for the purcords, point cloud files, pictures and videos for the onsite pose of this study. The basic principles for the classificabuilding components are compiled. Wooden components tion are: 1) Starting from the front of the building to the
are isolated individually to build the Revit component and back along the main axis of the building; 2) Classifying all
construct the 3D model. Building components are identi- trusses on the structure from the exterior to the interior,
fied and named while drawing their 3D counterparts. The from the front to back and from the left to right; 3) From
framework of the restoration report and CIDOC CRM the lowest building component under the truss, identifymanual served as references to establish the ontological ing every interval at different height. Additional details
model and database. The Revit model output is then con- can be found in Cheng et al. (2018a). In order to convert
verted into FBX files to be imported into Unity, where the them into Revit components systematically without any
material is then reset. The restoration database and report omissions, the components must be coded properly. The
are consulted for C# coding, and imported into Unity to site layout is divided into Front Gate (A); Hall of Worestablish the query platform for restoration records. ship (B); Main Hall (C); East and West Chambers (D);

<!-- p. 8 -->

34 Y.-M. Cheng et al. Ontology-based HBIM for historic buildings with traditional woodwork in Taiwan

Table 1. Restoration records on Huangxi Academy (source: compiled from Huangxi Academy restoration report and meetings with
field experts)

Restoration Restored space Artisans Methods Tools period
− Front gate − Major woodwork: − Major woodwork; − Major woodwork: plywood, cardboard,
− Hall of worship; Chen o-Fu, Li o-E, Lin − Wood carving; steel square, chalk line, flexible curve
− Connecting o-Zhong, Chen o-Shan, − Masonry; ruler, tape measure, electric planer,
hallway; Zhang o-De; − Roof tile work; electric knife sharpener, chainsaw;
− Newly built; − Wood carving: Cai − Clay sculpture and − Wood carving: Chisels, scroll saw,
front chambers; o-Cheng, Yan o-Yi, applique; sharpening stone, power drill;
− Rear chambers Huang o-Fa, Xu o-Fu; − Brick and tile work − Masonry: threads, plumb bob, trowels,
− Masonry: Xiao o-Yuan, − Brick sculpture; triangle hammer, steel plate, large iron
Song o-Qin, You o-Gen, − Wall construction bucket, spade, tape measure, wheel
Wen o-Ji; barrow, and crane;
1986–1989 − Roof tile work: Xiao − Roof tile work: Trowels, greyboard,
o-Yuan, Song o-Qin; mortar mixing bucket;
− Clay sculpture and − Clay sculpture and applique: wire, barb
applique: Cheng o-Hua, wire, steel bar, metal trowel, small iron
Li o-Huang, Lin o-Song; bucket;
− Brick and tile work: You − Brick and tile work: electric engraver,
o-Chong; stone ax, iron hammer, knife, water jet
− Brick sculpture: You cutter, plumb bob, and sponge;
o-Chong; − Brick sculpture: electric engraver
− Wall construction: Wen set, chisels, iron hammer, chisel set,
o-Ji sharpening stone;
Main hall and Construction Company − Wall construction: threads, plumb bob, 2002–2002 worshipping hall water jet cutter, metal trowel, triangular
hammer, spade, wheelbarrow, manual Restoration of Construction Company crane, pen brush, chalk line, tape the roof over 2006–2007 measure, template, wooden ruler. Sanchuan Hall at
the front gate
Note: In order to protect personal information, this table omits a part of the name of the artisans.

Connecting Hallway (E). The letters in the parentheses porting bracket) and B15 ying (roof beam), are defined as
are the codes assigned for each area. They are followed family component with parameters, whose geometric paby serial numbers to indicate the component name and rameters can be established. The bottom of Figure 5 shows
type. The components established for Huangxi Academy the parameters and various sizes of the B14 supporting
include parametric universal components – tong (main brackets. Others, such as tuomu (angle bracket), guatong
beam), dou (supporting bracket) and ying (roof beam); (gourd-shaped supporting bracket), roof and fence, are
non-parametric universal components – shumu (con- complicated in form. It is difficult to establish the paramnecting beam), column base (zuzhu), shusui (decorative eters so they are defined as family component without
Shu bracket), guatong (gourd-shaped supporting bracket). parameters or custom component. Such designation alFigure 5 shows that all components of Hall of Worship are lows for systematical conversion of the common Minan
classified into either parametric or non-parametric com- architectural components into the component library with
ponents. In the code, B010418, for example, B represents parametric attributes pre-established in Revit. The compothe area, Hall of Worship; 01 is the code for plinth; 04 is nents can be applied repeated during the modeling prothe code for the 4th type, referring to the fourth type of cess. Table 2 shows how regular components correspond
plinth in the hall of worship; 18 indicates that this is the to the built-in Revit components for Huangxi Academy.
18th plinth after entering the front gate. Center for Cultural Sites Rehabilitation and Develop-
To allow these components to be transferrable for oth- ment provided the point cloud, drafts of floorplans and eler projects, most of them are created as RFA file. Basically, evations of Huangxi Academy. The RCP file is linked with
the component types are divided into the three following the 3D model to support the identification of spatial posiclassifications based on how each component would be tion. Figure 6 shows the point cloud of Huangxi Academy
utilized in the model. They are family component with and Figure 7 shows the layering of shanman and point
parameters, family component without parameters and cloud as well as the final assembly. All of the established
custom component (Cheng et al., 2018a). During the components are loaded into the Huangxi Academy project
drawing process, building components that appear in high and assembled. Figure 8 shows the completed model for
frequency, such as B13 tong (main beam), B14 dou (sup- Huangxi Academy.

<!-- p. 9 -->

Journal of Civil Engineering and Management, 2021, 27(1): 14–26 35

Figure 5. Types of components in hall of worship

Figure 6. Point cloud of Huangxi Academy

Figure 7. Layering of Shanman components with point cloud, and final assemblage (partial)

<!-- p. 10 -->

36 Y.-M. Cheng et al. Ontology-based HBIM for historic buildings with traditional woodwork in Taiwan

Figure 8. Finalized Revit model of Huangxi Academy

Table 2. Common building components of traditional Minan architecture and corresponding Revit components

Name in Revit Commonly used components
Column & related Qianjinzhu (Front Golden Column), Houjinzhu (Back Golden Column), Diaotong (Short Hanging Column),
family Guazu (Gourd Shaped Column), Guatong (Short Gourd Shaped Column), Zuzhu (Column Base)
Beam and related Shumu (Connecting Beam), Tong (Main Beam), Ying (Roof Beam)
family
Bracket related Shusui (Decorative Shu Bracket)
family Shuwei (Protuding end of Shu Bracket)
Kansui (Decorative Kan Bracket)
Yuanguang (Decorative Connecting Bracket)
Yuanguangji (Protruding end of decorative connecting bracket)
Toujin (Top Connecting Bracket)
Yidoushansheng (One beam with three brackets)
Tuomu (Angle bracket)
Dou (Bracket)
Wall Use the built-in function to change the dimension and materials, and rename.
Floor Use the built-in function to change the dimension and materials and rename to, for instance, grass.
Roof The front, middle and back roofs over the connecting hallways, the left, middle and right roofs of the front
gate, and the roof over the hall of worship.

4.2. Ontological model for restoration 3. Restoration records: Determine information to be
records of historic buildings included based on the type of information required
for restoring the historic building, for example,Huangxi Academy Restoration Report (Yen, 2018) and
the name of the building component, constructionGuji Tujieshidian (A Pictorial Guide for Historic Sites)
method, measurement units and the type of disasterby Professor Chien-Lang Lee (Lee, 2003) are referenced
that had caused damages.for this paper. Several experts were also consulted dur-
In order to be consistent with the international com-ing multiple meetings to establish the taxonomy for the
munity, the ontological model in this study is establishedbuilding components in the component library. The meet-
with the CIDOC CRM framework as reference. And Pro-ings also include discussions on items and component related information to be included in the ontological model. tégé is used to establish the ontological model for the hall
Three ontological models are established for this study: of worship of Huangxi Academy. Set the relationship in
\1. Basic information concerning the building compo- “object property” as P and “class” is set as E, as indicated
nents of the historic building: name, survey infor- in Tables 3 and 4. Under “individual”, set the information
mation, units, dimensions, materials, and so on. regarding the artisan, restoration time as well as material
\2. Artisans: This is a human-centric approach to de- or dating of components based on the restoration records
termine information to be included, for example, an of Huangxi Academy. The final ontological models are
artisan’s expertise and personal information. shown in Figures 9 to 11.

<!-- p. 11 -->

Journal of Civil Engineering and Management, 2021, 27(1): 14–26 37

Table 3. CIDOC CRM property name included in each object property hierarchy

Basic items Artisan Restoration records
P1 is identified by (identifies) P1 is identified by (identifies) P1 is identified by (identifies)
P2 has type (is type of) P2 has type (is type of) P2 has type (is type of)
P3 has note P3 has note P3 has note
P4 has time-span (is time-span of) P4 has time-span P4 has time-span (is time-span of)
P43 has dimension (is dimension of) (is time-span of) P7 took place at (witnessed)
P45 consists of (is incorporated in) P41 classified (was classified by) P16 used specific object (was used for)
P48 has preferred identifier (is preferred identifier of) P42 assigned (was assigned by) P33 used specific technique
P53 has former or current location (is former P53 has former or current (was used by)
or current location of) location (is former or current P34 concerned (was assessed by)
P67 refers to (is referred to by) location of) P35 has identified (was identified by)
P71 lists (is listed in) P71 lists (is listed in). P67 refers to (is referred to by)
P78 is identified by (identifies) P78 is identified by (identifies) P71 lists (is listed in)
P87 is identified by (identifies) P87 is identified by (identifies) P78 is identified by (identifies)
P90 has value P92 brought into existence P87 is identified by (identifies)
P91 has unit (is unit of) (was brought into existence by) P92 brought into existence (was brought
P92 brought into existence (was brought into P93 took out of existence (was into existence by)
existence by) taken out of existence by) P93 took out of existence (was taken
P93 took out of existence (was taken out of existence by) out of existence by)

Table 4. CIDOC CRM class name included in each class hierarchy

Basic items Artisan Restoration records
E1 CRM Entity E1 CRM Entity E3 Condition State
E18 Physical Thing E17 Type Assignment E5 Event
E41 Appellation E39 Actor E14 Condition Assessment
E42 Identifier E41 Appellation E29 Design or Procedure
E47 Spatial Coordinates E42 Identifier E48 Place Name
E48 Place Name E45 Address E49 Time appellation
E49 Time appellation E49 Time appellation E53 Place
E53 Place E52 Time-Span E55 Type
E54 Dimension E53 Place E41 Appellation
E55 Type E55 Type E47 Spatial Coordinates
E57 Material E62 String E49 Time appellation
E58 Measurement Unit E63 Beginning of Existence E62 String
E60 Number E64 End of Existence E63 Beginning of Existence
E62 String E64 End of Existence
E63 Beginning of Existence E71 Man-Made Thing
E64 End of Existence E89 Propositional Object

4.3. Establishment of information platform tion, the data may be updated. In terms of maintenance,
it would be easier than maintaining the built-in attributesThe setting for the fields within the database is established within Revit.based on expert opinions and data collected. The fields A VR platform is established using Revit and Unity
for component names and basic component information, to allow users to search for restoration records of the hissuch as model ID, names, physical location and dimension toric building within the VR domain as well as maintain
(as shown in Table 5), as well as the fields for compo- and manage the historic building. The main reason behind
nent restoration records, such as time, degree of damage, choosing Unity to develop the platform is that the software
tool, restoration method (as shown in Table 6) are cat- allows the user to customize the content of the tables using
egorized into char, varchar and int for the corresponding c# so that essential attributes related to the historic building
types based on the data type to finalize the database. Once can be added and irrelevant attributes are left out. To those
constructed, the database allows users to conduct queries engaging in restoration efforts, this software allows for addthrough the worksheets, which covers the names and de- ed flexibility, and users are able to choose the appropriate
scriptions of the components, external links and material platform based on actual needs. Figure 13 shows the flowtypes, etc. The queries may be combined with SQL. An ex- chart of the platform establishment process. In addition to
ample is to query using the description, external reference the computer platform, Unity is also compatible with moID and materials of the hanging bracket. In worksheet e1, bile platforms such as Apple iOS (https://www.apple.com/
which contains information on external resources of the tw/) and Google Android (https://www.android.com/),
component, External Reference E42 indicates the com- handheld game consoles such as 3DS and PSV, and TV
ponent ID in Revit. Figure 12 shows the query process game console such as Xbox One (https://www.xbox.com/
and outcome. As the historic building undergoes restora- zh-TW/) and PS4 (https://www.playstation.com/cht-tw/).

<!-- p. 12 -->

38 Y.-M. Cheng et al. Ontology-based HBIM for historic buildings with traditional woodwork in Taiwan

Figure 9. Overview of ontological model for background information

Figure 10. Overview of ontological model for artisan information

Figure 11. Overview of ontological model for restoration records

<!-- p. 13 -->

Journal of Civil Engineering and Management, 2021, 27(1): 14–26 39

Table 5. Basic information for building components

Field title Definition Example for data entry
Model ID ID for the 3D model of building components –
Name Name of building component Dou (supporting bracket), zuzhu (column
base), gong (bow-shaped bracket)
Spatial location The space which the building occupies Relative spatial location
Absolute spatial location
Materials Material of building component Wood, brick, stone
3D Dimensions of building component Length x width x height
Descriptions Descriptive information about the building Surface treatment
component Cultural value
Audio and video attributes of Audio and video records which help users fully Storage location and web address for the audio
building component understand actual conditions and video files
Time Time information related to the building Date of creation
component Date of restoration

Table 6. Restoration information for building components

Name of field Definition Example for data entry
Coding for restoration Coding for information related to restoration –
records of building components
Time Schedule for restoration of building Research and survey stage, planning and design
components stage, subcontracting, etc.
Degree of damage Evaluate degree of damages prior to restoration Rooftop damages, wood damages
Main construction method Construction methods used during restoration Principles and construction methods for restoration
Tool Tools used for this project Chisels, scroll saw, sharpening stone, power drill.
Material Materials used for this project Red tile, flat tile, ceramic shard pasting decoration,
etc.
Link to construction records Link to records, audio and video information The website or physical address of where the files
or audio and video files documented during construction are stored
Link to work report Link to the work report for construction
project

Figure 12. SQL query – background information for hanging bracket

<!-- p. 14 -->

40 Y.-M. Cheng et al. Ontology-based HBIM for historic buildings with traditional woodwork in Taiwan

Figure 13. Flowchart of platform establishment

In addition to the computer program, an Android applica- During the research process, three.js (https://threejs.
tion is also developed to accommodate the VR technology. org/) was also used to develop a similar system, but the
The process is similar to the one previously described (ap- system was applied towards another traditional Minan
plicable to Unity 2017). However, during the initial set- historic building (Cai Ancestral Shrines in Qionglin). The
ting, users should choose Android as the platform, and software, three.js, is a cross-browser open source JavaSunder the player setting, choose Google Cardboard as VR cript library and application programming interface (API)
support under XR Setting. Lastly, choose the appropriate that is developed based on WebGL. It is used to display
items under Resolution and Presentation (as shown in 3D models and for information visualization. Being open
Figure 14). source allows for added flexibility. However, users must
have programming capability. The technology used dur-
ing the development of the three.js platform includes
3D model conversion, database data conversion and the
generation of semantic data. In order to integrate the 3D
model with the webpage, and make the 3D model cre-
ated for this study viewable on the website, the 3D model
is converted to XML based data exchange format (also
ISO standard) – COLLADA (https://www.khronos.org/
collada/) with DAE extension. The database content for
the historic building and restoration data are established
in accordance with the Minan architectural components
and restoration data analyzed in the previous section. The
program for generating semantic data is developed with
PHP based on ontology (*.owl) to convert the content in
the database into semantic with meanings and RDF data
that can be linked. For additional details, please refer to
Kuo et al. (2018).
Autodesk A360 is a program developed specifically for
architects, civil engineers and designers. A360 is compat-
ible with over 100 CAD files and other formats, such as
RVT, NWD, DWG and DXF. Regardless of the software
used to create the initial file, the file can be uploaded to
Figure 14. XR Settings & Android settings for resolution A360 for review. Within the model, the single component
and presentation will display characteristics of the component established

<!-- p. 15 -->

Journal of Civil Engineering and Management, 2021, 27(1): 14–26 41

in Revit, and users can view Huangxi Academy through The 3D model is linked with the database through the
the first-person camera view. component id, which minimizes the need to import all
All of the finalized platforms from this research are relevant data into Revit, and therefore reduces the Revit
shown in Figure 15. Users may click on the components file size. The A360 platform is the most intuitive and confor relevant data in the platforms developed with Unity venient in terms of browsing, which can be done as soon
and three.js, which is similar to the functions of A360. as the model is uploaded. Programming is not a necessary
However, in Unity and three.js, the data fields are estab- capability for users. However, there are limitations when
lished with ontology/CIDOC CRM. Such approach is bet- it comes to further applications of the 3D model, such as
ter aligned with international practice and leaves room for advanced visualization for fire prevention or immersion
future expansion, which is appropriate for various types experience, as well as data maintenance and update. As
of historic structures, such as temples, churches and for- to three.js, since it is open source, users may customize
tresses when such need arises. Additionally, since the data- the interface to suit individual needs. However, it takes
base is not created as a Revit file, users may conduct que- decent programming ability to create an ideal interface.
ries such as the query on the background information of In terms of Unity, which is a gaming platform, may be
hanging bracket through MySQL, as shown in Figure 12. further developed to enhance user interaction or to be ap-

a) Unity platform – query result 1 b) Unity platform – query result 2

c) three.js platform – query result 1 d) three.js platform – query result 2
Source: Cheng et al. (2018b) Source: Cheng et al. (2018b)

e) Finalized platform (VR) f) A360 browsing platform

Figure 15. Finalized platform

<!-- p. 16 -->

42 Y.-M. Cheng et al. Ontology-based HBIM for historic buildings with traditional woodwork in Taiwan

plied toward disaster relief drills. Aside from data query allows flexibility for future expansion of the database and
toward historic conservation, it has potential in applica- ontological model. It is believed that this framework will
tions toward 3D modeling for historic buildings. Details be able to accommodate the documentation and deducof the comparison of the three platforms are provided in tive reasoning of pertinent information regarding historic
Table 7. buildings as time progresses. Applications of the process
developed in this paper and its outcome go beyond tradi- Table 7. Platform comparison
tional wooden architecture. They are also applicable to-
Item A360 Unity three.js ward studies of ancestral shrines, temples and fortresses,
Technical limitations Low Medium High and the database developed may also serve as a reference
Convenience High Medium Low for future modeling.
Establishing digital archives of historic buildings has Future development Medium High High
been widely recognized as an eminent task, and it is made Viewable model
Yes Yes Yes possible with the development of HBIM. Technological information
advances have introduced automated and semi-automated Flexibility and
Low Medium High technologies to the field. However, due to budget concerns expandability of database
Rendering of model or the lack of fully-developed supporting technology, it is
Medium High Low difficult for the authority to access and adopt cutting-edge exterior
technology immediately, or to create digital models of
historic buildings containing background and restoration
Conclusions data that can be readily available for the general public.
Rather than waiting for the funding or for the supportingRapid technological development has taken conservation
technology to mature, it would be more practical to taketechniques and documentation of restoration records for
advantage of existing technology, which is developed andhistoric structures beyond the conventional approaches in
accessible at a relatively low cost. This rationale gives waysurveying, drawing and reporting. Using digital model-
to why this study focuses on the logic and process be-ing, building exteriors, restoration techniques and overall
hind manual 3D modeling. In terms of the data embeddedinformation on building components are documented.
within each component, the study concentrates on estab-In the event that the historic structures are damaged, the
lishing a systematic approach with the possibility of futuredigital model may serve as a key reference during restora-
expansion while staying connected to international prac-tion, which also enhances the value of digital archiving for
historic buildings. The study proposes a comprehensive tice. Recommendations are provided in terms of methodframework and operational procedure for the modeling ology and software application. To choose the proper tools
of traditional Minan architecture. The research process in- and LoD for the modeling, those in the field of heritage
corporates BIM, CIDOC CRM ontological model¸ game conservation must base their decisions on actual needs
engine and database building techniques. By integrating and available funding. In the case of conducting structural
current information technology, the study explores the analysis to determine safety requirements, the LoD of the
digitization of historic building components of Huangxi model would be crucial. However, it would not be the case
Academy, a traditional Minan wooden architecture located for documentation purposes. LoD 300, as recommended
in central Taiwan. The 3D model of Huangxi Academy is in this study, would suffice for documenting information
constructed with Autodesk Revit, the ontological models regarding building components. The study reveals that the
are then built and analyzed using CIDOC CRM and Proté- higher the familiarity with software operation, the more
gé, while the database is established through phpMyadmin. efficient users become when building structural compoThe outcomes from the process mentioned above are final- nents with unique physical configurations for the Minan
ized and presented in the 3D platform established in Uni- historic wooden structures. This is partly due to one’s faty. Lastly, a comparison is conducted to evaluate the plat- miliarity with the software, and partly because one can
forms built within Unity, three.js and Autodesk A360. To choose existing components with similar configurations
examine the building components of a traditional Minan from the database to modify, which is much less time-conwooden architecture, a systematic analysis is conducted. suming. Actually, placing the components at the proper
The components are examined individually with attributes position is a relatively lengthier operation comparing to
clearly defined when they are converted to the 3D mod- others during the entire process, which is why in addition
el. The components are positioned and categorized into to referring back to the floor plan and elevation drawings
parametric and non-parametric component database for provided by the Center for Cultural Sites Rehabilitation
more efficient analysis. Using the framework of CIDOC and Development, point cloud is also incorporated to deCRM to establish the content and context of information termine the precise location for the components. Lookrelated to the historic building helps users establish an on- ing into the future, automated positioning system or the
tological model containing restoration records and quickly development of such system would be research directions
understand the information framework. The process also worth further efforts.

<!-- p. 17 -->

Journal of Civil Engineering and Management, 2021, 27(1): 14–26 43

Acknowledgements Barazzetti, L., Mezzino, D., & Quintero, M. S. (2017). Digital
workflow for the conservation of Bahrain built heritage: The
This study is sponsored by the Bureau of Cultural Herit- Sheik Isa Bin Ali House. International Archives of the Photoage, Ministry of Cultural for 2018 Research and Develop- grammetry, Remote Sensing and Spatial Information Sciences,
ment Project Plan (107-5). The author would like to thank XLII-2/W5, 65–70.
all participating experts, especially Ya-Ning Yen and the https://doi.org/10.5194/isprs-archives-XLII-2-W5-65-2017
center for cultural sites rehabilitation and development. Boeykens, S., Himpe, C., & Martens, B. (2012). A case study
of using BIM in historical reconstruction. The VinohradyWithout their valuable contributions, this research would Synagogue in Prague. eCAADe 30 (Virtual Architecture), 1,not have been made possible. 729–738.
Brumana, R., Oreni, D., Raimondi, A., Georgopoulos, A., & BreAuthor contributions gianni, A. (2013, October). From survey to HBIM for docu-
mentation, dissemination and management of built heritage:
Dr. Cheng conceived and performed the research and The case study of St. Maria in Scaria d’Intelvi. Digital Heritage
wrote the manuscript. Dr. Kuo helped to supervise the International Congress (Digital Heritage), 1, 497–504.
process of ontology modeling. Mr. Mou built the models https://doi.org/10.1109/DigitalHeritage.2013.6743789
and the Unity browsing platform. Brumana, R., Oreni, D., Torre, S. D., Banfi. F, Barazzetti, L., &
Previtali, M. (2014). Survey turned Into BIM: The restoration
and the work involved concerning the Basilica Di CollemagDisclosure statement gio after the earthquake. ISPRS Annals of the Photogramme-
try, Remote Sensing and Spatial Information Sciences, II-5,The authors have no affiliations with or involvement in 267–273. https://doi.org/10.5194/isprsannals-II-5-267-2014
any organization or entity with any financial interest or Buonamici, F., Carfagni, M., Furferi, R., Governi, L., Lapini, A., &
non-financial interest in the subject matter or materials Volpe, Y. (2018). Reverse engineering modeling methods and
discussed in this manuscript. tools: a survey. Computer-Aided Design and Applications, 15(3),
443–464. https://doi.org/10.1080/16864360.2017.1397894
Cheng, Y. M., Mou, C. C., Lu, Y. C., & Yen, Y. N. (2018a). HBIMReferences in cultural heritage conservation component library for woodAcierno, M., Cursi, S., Simeone, D., & Fiorani, D. (2017). Archi- work in historic buildings in Taiwan. Springer International
tectural heritage knowledge modelling: An ontology-based Publishing. https://doi.org/10.1007/978-3-030-01762-0_32
framework for conservation process. Journal of Cultural Herit- Cheng, Y. M., Yen, Y. N., Kuo, C. L., Mou, C. C., & Lu, Y. C.
age, 24, 124–133. https://doi.org/10.1016/j.culher.2016.09.010 (2018b). Research on the application of HBIM in the preservaAntón, D., Medjdoub, B., Shrahily, R., & Moyano, J. (2018). Ac- tion of cultural assets (I) – taking the Southern Fujian-style
curacy evaluation of the semi-automatic 3D modeling for wooden architecture as an example. Bureau of Cultural Herit-
historical building information models. International Journal age, Ministry of Culture, Taiwan.
of Architectural Heritage, 12(5), 790–805. Chiabrando, F., Sammartano, G., & Spanò, A. (2016). Histori-
https://doi.org/10.1080/15583058.2017.1415391 cal buildings models and their handling via 3D survey: From
Antón, D., Pineda, P., Medjdoub, B., & Iranzo, A. (2019). As-built points clouds to user-oriented HBIM. The International Ar-
3D heritage city modelling to support numerical structural chives of the Photogrammetry, Remote Sensing and Spatial In-
analysis: Application to the assessment of an archaeological formation Sciences, XLI-B5, 633–640.
remain. Remote Sensing, 11(11), 1276. https://doi.org/10.5194/isprsarchives-XLI-B5-633-2016
https://doi.org/10.3390/rs11111276 Dezen-Kempter, E., Cogima, C. K., de Paiva, P. V. V., & de CarAntonopoulou, S., & Bryan, P. (2017). BIM for heritage: develop- valho, M. A. G. (2018). BIM for heritage documentation: An
ing a historic building information model. Historic England. ontology-based approach. eCAADe 36 (BIM Applications), 1,
Banfi, F. (2017). BIM orientation: Grades of generation and 213–222.
information for different type of analysis and management Dhanda, A., Fai, S., Graham, K., & Walczak, G. (2017). Leverag-
process. International Archives of the Photogrammetry, Remote ing existing heritage documentation for animations: Senate
Sensing and Spatial Information Sciences, XLII-2/W5, 57–64. virtual tour. International Archives of the Photogrammetry,
https://doi.org/10.5194/isprs-archives-XLII-2-W5-57-2017 Remote Sensing and Spatial Information Sciences, XLII-2/W5,
Banfi, F., Fai, S., & Brumana, R. (2017). BIM automation: Ad- 171–175.
vanced modeling generative process for complex structures. https://doi.org/10.5194/isprs-archives-XLII-2-W5-171-2017
ISPRS Annals of The Photogrammetry, Remote Sensing and Fadli, F., & AlSaeed, M. (2019). Digitizing vanishing architec-
Spatial Information Sciences, IV-2/W2, 9–16. tural heritage; The design and development of Qatar historic
https://doi.org/10.5194/isprs-annals-IV-2-W2-9-2017 buildings information modeling [Q-HBIM] platform. SusBarazzetti, L. (2016). Parametric as-built model generation of tainability, 11, 2501. https://doi.org/10.3390/su11092501
complex shapes from point clouds. Advanced Engineering In- Fregonese, L., Achille, C., Adami, A., Fassi, F., Spezzoni, A., &
formatics, 30, 298–311. Taffurelli, L. (2015). BIM: An integrated model for planned
https://doi.org/10.1016/j.aei.2016.03.005 and preventive maintenance of architectural heritage. 2015
Barazzetti, L., Brumana, R., Oreni, D., Previtali, M., & Roncoro- Digital Heritage, 2, 77–80. IEEE.
ni, M. (2014). True-orthophoto generation from UAV images: https://doi.org/10.1109/DigitalHeritage.2015.7419456
Implementation of a combined photogrammetric and com- Han, S., Wu, C., Li, D., Li, J., Liu, Y., Feng, K., & Di, Y. (2017).
puter vision approach. ISPRS Annals of The Photogrammetry, Workflows for condition inspection documentation of archi-
Remote Sensing and Spatial Information Sciences, II-5, 57–63. tectural heritage based on HBIM: Taking three duty rooms
https://doi.org/10.5194/isprsannals-II-5-57-2014 in Forbidden City of Beijing as an example. ISPRS Annals of

<!-- p. 18 -->

44 Y.-M. Cheng et al. Ontology-based HBIM for historic buildings with traditional woodwork in Taiwan

the Photogrammetry, Remote Sensing and Spatial Information Tang, P., Huber, D., Akinci, B., Lipman, R., & Lytle, A. (2010).
Sciences, IV-2/W2, 123–129. Automatic reconstruction of as-built building information
https://doi.org/10.5194/isprs-annals-IV-2-W2-123-2017 models from laser-scanned point clouds: A review of related
Hichri, N., Stefani, C., De Luca, L., Veron, P., & Hamon, G. (2013). techniques. Automation in Construction, 19(7), 829–843.
From Point Cloud to BIM: A survey of existing approaches. https://doi.org/10.1016/j.autcon.2010.06.007
International Archives of the Photogrammetry, Remote Sensing Thomson, C., & Boehm, J. (2015). Automatic geometry gen-
and Spatial Information Sciences, XL-5/W2, 343–348. eration from Point Clouds for BIM. Remote Sensing, 7(9),
https://doi.org/10.5194/isprsarchives-XL-5-W2-343-2013 11753–11775. https://doi.org/10.3390/rs70911753
International Organization for Standardization. (2006). Infor- UNESCO. (2020). New inscribed properties (2019). https://whc.
mation and documentation – A reference ontology for the in- unesco.org/en/newproperties/?date=2019&mode=list&inscri
terchange of cultural heritage information (ISO Standard No. bed=1
21127:2006). https://www.iso.org/standard/34424.html Volk, R., Stengel, J., & Schultmann, F. (2014). Building InforInternational Organization for Standardization. (2014). Informa- mation Modeling (BIM) for existing buildings – Literature
tion and documentation – A reference ontology for the inter- review and future needs. Automation in Construction, 38,
change of cultural heritage information (ISO Standard No. 109–127. https://doi.org/10.1016/j.autcon.2013.10.023
ISO 21127:2014). https://www.iso.org/standard/57832.html Yen, Y. N. (2018). Restoration and reuse plan for Huangxi AcadKuo, C.-L., Cheng, Y.-M., Lu, Y.-C., Lin, Y.-C., Yang, W.-B., & emy, a municipal historic site. Bureau of Cultural Heritage,
Yen, Y.-N. (2018). A framework for semantic interoperability Ministry of Culture, Taiwan.
in 3D tangible cultural heritage in Taiwan. In EuroMED 2018, Yen, Y. N., & Lu, Y. C. (2019). Research on HBIM and level of
Cyprus. https://doi.org/10.1007/978-3-030-01765-1_3 information for the life cycle of traditional Chinese built
Lee, C. L. (2003). Guji Tujieshidian (A Pictorial Guide for Historic heritage in Taiwan. The International Archives of the Photo-
Sites). grammetry, Remote Sensing and Spatial Information Sciences,
Logothetis, S., & Stylianidis, E. (2016). BIM open source software XLII-2/W11, 1159–1163.
(Oss) for the documentation of cultural heritage. Virtual Ar- https://doi.org/10.5194/isprs-archives-XLII-2-W11-1159-2019
chaeology Review, 7(15), 28–35.
https://doi.org/10.4995/var.2016.5864
Logothetis, S., Delinasiou, A., & Stylianidis, E. (2015). Building
information modelling for cultural heritage: A review. ISPRS
Annals of Photogrammetry, Remote Sensing and Spatial Infor-
mation Sciences, II-5/W3, 177–183.
https://doi.org/10.5194/isprsannals-II-5-W3-177-2015
López, F. J., Lerones, P. M., Llamas, J., Gómez-García-Bermejo, J.,
& Zalama, E. (2018). A review of heritage building informa-
tion modeling (H-BIM). Multimodal Technologies and Inter-
action, 2(2), 21. https://doi.org/10.3390/mti2020021
Moyano, J., Odriozola, C. P., Nieto-Julián, J. E., Vargas, J. M.,
Barrera, J. A., & León, J. (2020). Bringing BIM to archaeologi-
cal heritage: Interdisciplinary method/strategy and accuracy
applied to a megalithic monument of the Copper Age. Journal
of Cultural Heritage, 45, 303–314.
https://doi.org/10.1016/j.culher.2020.03.010
Murphy, M., McGovern, E., & Pavia, S. (2009). Historic build-
ing information modelling (HBIM). Structural Survey, 27(4),
311–327. https://doi.org/10.1108/02630800910985108
National Cultural Heritage Database Management System.
(2020). https://nchdb.boch.gov.tw/assets/overview/monu-
ment/19851127000003
Nieto Julián, J. E., Campos, J. J. M., Delgado, F. R., & García, D.
A. (2016). Management of built heritage via HBIM Project:
A case of study of flooring and tiling. Virtual Archaeology
Review, 7(14), 1–12. https://doi.org/10.4995/var.2016.4349
Pöchtrager, M., Styhler-Aydın, G., Döring-Williams, M., &
Pfeifer, N. (2017). Automated reconstruction of historic roof
structures from point clouds – Development and examples.
ISPRS Annals of the Photogrammetry, Remote Sensing and
Spatial Information Sciences, IV-2/W2, 195–202.
https://doi.org/10.5194/isprs-annals-IV-2-W2-195-2017
Previtali, M., Brumana, R., Stanga, C., & Banfi, F. (2020). An on-
tology-based representation of vaulted system for HBIM. Ap-
plied Sciences, 10, 1377. https://doi.org/10.3390/app10041377
Quattrini, R., Pierdicca, R., & Morbidoni, C. (2017). Knowledge-
based data enrichment for HBIM: Exploring high-quality
models using the semantic-web. Journal of Cultural Heritage,
28, 129–139. https://doi.org/10.1016/j.culher.2017.05.004
