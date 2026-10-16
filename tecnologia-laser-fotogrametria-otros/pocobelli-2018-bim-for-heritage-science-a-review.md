---
type: libro
title: "BIM for heritage science: a review"
author: "Danae Phaedra Pocobelli"
categoria: "Tecnología láser, fotogrametría, otros"
paginas: 15
extraccion: "texto"
fuente: "local:E:/Biblioteca digital/Tecnología láser, fotogrametría, otros/Pocobelli 2018 - BIM for heritage science - a review.pdf"
convertido: 2026-10-14
---

# BIM for heritage science: a review

> Texto extraído de `Tecnología láser, fotogrametría, otros/Pocobelli 2018 - BIM for heritage science - a review.pdf` (15 páginas, texto). El PDF original está en el disco E: (Biblioteca digital); `<!-- p. N -->` marca el inicio de cada página.

<!-- p. 1 -->

Pocobelli et al. Herit Sci (2018) 6:30
https://doi.org/10.1186/s40494-018-0191-4

REVIEW Open Access
BIM for heritage science: a review
Danae Phaedra Pocobelli1*  , Jan Boehm2, Paul Bryan3, James Still4 and Josep Grau‑Bové1

Abstract
Building Information Modelling (BIM) is a new process that is spreading in the Architecture, Engineering and Con‑
struction field. It allows the creation of virtual building models, which can be linked to numerical data, texts, images,
and other types of information. Building components, such as walls, floors, etc. are modelled as “smart objects”, i.e.
they are defined by numerical parameters, such as dimensions, and are embedded with other kinds of information,
such as building materials and properties. Stored data are accessible and modifiable by all different professionals
involved in the same project. The BIM process has been developed for new buildings, and it allows to plan and man‑
age the whole building life-cycle. BIM for built heritage has started to be researched recently, and its use is still not
widespread. Indeed, built heritage is characterised by complex morphology and non-homogeneous features, which
clash with BIM’s standardised procedures. Moreover, to date, BIM does not allow fully automated procedures to model
heritage buildings. This review focuses on the survey and digitisation phases, which can be seen as the initial phases
of application of BIM in conservation projects. It also briefly covers the modelling stage. Here we present the main
methodologies developed for BIM for built heritage. Issues about digitisation are also highlighted, principally in con‑
nection with the unavailability of automated processes. During the last 10 years, research has led to promising results;
for example, videogame interfaces have been used to simulate virtual 3D tours that display in a single interface the
3D model and the database containing metadata, and new software plug-ins have been developed, to easily create
“smart objects”. Nevertheless, further research is needed to establish how BIM can support the practice of building
conservation. There is a gap in BIM’s information holding capacities, namely the storage of cultural and historical
documentation, as well as monitored and simulated data relevant for preventive conservation. Future work should
focus on the development of new tools that will be able to store and share all the relevant metadata.
Keywords:  BIM, HBIM, Heritage building, Conservation, Survey, Parametric smart object library, Smart object, Point
cloud

Introduction file [1–7], creating what has been called “smart” models
In the last decades, a quick development in Information [1, 3].
Technology (IT) has taken place, and architectural rep- Building Information Modelling should be considered
resentation procedures have been affected by it. At the a process, rather than a technology. It is a three-dimenend of the last century, professionals could use Computer sional (3D) project computational representation that
Aided Design (CAD) to draw their projects without for- connects all the available information to each 3D object
mal procedures to share and store the associated meta- of the model [3, 7]. Whilst a CAD is essentially a 3D
data. Nowadays a key development is taking place under model that allows creating plans, sections, etc., but still
the name of Building Information Modelling (BIM). formed by purely geometrical elements, a smart model
Using BIM technology, it is possible to condense all the has all its elements linked to a database containing all the
information required during building works in one single related metadata [1, 2, 6]. The expression “smart models”
refers to models composed of parametric objects [4, 5,
8–23], i.e. virtual building components that are identified
\*Correspondence: danae.pocobelli.15@ucl.ac.uk
1 The Bartlett School of Environment, Energy and Resources, Institute by modifiable parameters, such as dimensions. These virfor Sustainable Heritage, University College London, Central House, 14 tual objects may also contain other types of data, such as
Upper Woburn Place, London WC1H 0NN, UK material information [4, 5, 7–9, 19, 20, 23–26], and they
Full list of author information is available at the end of the article

© The Author(s) 2018. This article is distributed under the terms of the Creative Commons Attribution 4.0 International License
(http://creat​iveco​mmons​.org/licen​ses/by/4.0/), which permits unrestricted use, distribution, and reproduction in any medium,
provided you give appropriate credit to the original author(s) and the source, provide a link to the Creative Commons license,
and indicate if changes were made. The Creative Commons Public Domain Dedication waiver (http://creat​iveco​mmons​.org/
publi​cdoma​in/zero/1.0/) applies to the data made available in this article, unless otherwise stated.

<!-- p. 2 -->

Pocobelli et al. Herit Sci (2018) 6:30 Page 2 of 15

are an accurate—for conservation purposes—represen- the documentation of heritage buildings during consertation of the corresponding real ones [3]. Murphy et al. vation processes. Secondly, it identifies which areas need
[19] enhance this notion, and they claim that, in BIM, further research for the purpose of using BIM in heritage
parameters are assigned prior to the modelling phase. science processes: monitoring, forecasts and preventive
This means that they can be modified anytime as needed conservation. Finally, it discusses the latest technological
[7, 13, 14, 19, 22, 27, 28]. This feature may become cru- developments of this rapidly evolving field.
cial for heritage buildings, as models need to be updated
frequently due to new discoveries or new interpretations Building conservation practice
[5, 7, 23], interventions [2, 7, 29] or unintended changes Building conservation is a complex and multi-layered
in the building fabric such as weathering processes [1, 4, process that requires collaboration between different
5, 8, 20]. specialists [2, 29]. Many of the data typologies involved in
Building Information Modelling allows controlling this process could, in principle, be introduced in building
buildings from their planning phase until their manage- models that can enable collaboration. This section lists
ment, maintenance and, eventually, their restoration [2, the types of information that could potentially be part of
5, 30]. Various authors [2, 3, 7, 17] emphasise that one of an Historic Building Information Modelling (HBIM). In
the most interesting properties in BIM is interoperability. the following sections, the potential of this implementaDifferent professionals are usually involved in a building tion is assessed critically.
project [5, 21], and through BIM’s flexibility, they are able One of the key phases is the building analysis, during
to access all information they may need [3, 5, 16, 19, 21]. which a great diversity of information sources needs to
Currently BIM is mostly applied to buildings under be combined [29, 32–34]. Traditionally, building analyconstruction, rather than to existing ones [5, 7, 23, 31]; sis is carried out using manual methods, especially in the
this has been attributed by some to the scepticism of survey phase. Through triangulation and Digital Photoheritage professionals [17, 23], but it may also happen grammetry, it is possible to obtain the geometric and the
because the effort of modelling and converting to smart texture/material properties of a building; this informaobjects is high, and, while handling data, existing build- tion is then digitised on a CAD platform, and a 3D model
ings usually have problems of uncertainty and interpre- is produced. At the same time, historical analysis is pertation [23]. Moreover, heritage buildings usually do not formed, examining past sources, documentation, and
allow standardisation procedures—which are BIM’s generally all existing evidence [34]. The next step is to
strength—, as they are the result of different historical detect any surface degradation and to plan an intervenlayers, additions and demolitions, changes of use/func- tion session accordingly.
tion, etc. Ordinary information for heritage building to be con-
This paper is not a “conventional” state-of-the-art lit- served include:
erature review; it rather assesses the use of BIM within
the Heritage sector, with practical case study references. 1. Geometrical data, such as dimensions and volumetry
Two literature reviews exist on the use of BIM in built [32];
heritage. Logothetis [16] presents a complete account of 2. Architectural grammar, intended as architectural
software platforms and the steps involved in the crea- style. It could include specific building components
tion of BIM models of existing buildings, focusing also and construction techniques [32];
on the difference between CAD and BIM—identified in 3. Material characterisation [32, 35]. This information
the concept of “information”. The second one [23] revises is commonly detailed with elevation views where
many historic BIM projects to conclude that the main each material is depicted with a different hatch. The
challenges to the use of BIM in historic buildings are “(i) hatches are then illustrated by labels;
the automation of data capture and BIM creation (ii) the 4. Façade degradation [32, 36]. Elevation views are
update and maintenance of information in BIM and (iii) embedded with hatches representing specific degthe handling and modelling of uncertain data” [23]. In radations. Degradation typologies may be described
this context, “uncertain data” refers to spatial and compo- using glossaries, such as the ICOMOS-ISCS [37];
nent data which are not easily standardisable. 5. Façade interventions. Facade degradation scripts
The present review addresses issues that have not are used to plan specific interventions. Intervention
been explicitly discussed in previous research. Firstly, it handouts are again elevation views embedded with
explores the use of BIM to capture and store the typolo- hatches, symbols and tables to detail planned actions.
gies of data that can support heritage science, or in other 6. If the building is suffering from any structural damwords, the scientific analysis of historic buildings. Specif- age, a damage survey is required [32] to adequately
ically, it aims to explain how BIM can be used to support plan structural consolidation interventions.

<!-- p. 3 -->

Pocobelli et al. Herit Sci (2018) 6:30 Page 3 of 15

\7. Data collection, and possibly simulation, of environ- camera continuously, trying to detect convergent images,
mental parameters and their future effects on the and then digitally reconstructing the geometry [55].
building fabric, inform the maintenance of the build- Some Terrestrial laser scanners (TLS) are based on
ing and support-decision making. Recent develop- the triangulation principle as well [2, 18, 53, 56]. They
ments in the prediction and interpretation of risks to produce a point cloud of the scanned object [49], which
buildings may be used, such as Computational Fluid needs to be post-processed and then is transformed into
Dynamics (CFD) simulations [38, 39] and spatially a 3D model [4, 8, 18, 49, 57, 58]. Point clouds post-pro-
resolved monitoring data [40]. cessing is still a time-consuming task [23, 29, 57], even
if there have been some attempts to speed it up [15, 48,
Conservation practice is usually carried out with the 49, 59, 60]. TLS can be integrated with Geographic Inforinvolvement of many different professionals, and it is mation System (GIS), to geo-locate the scanned object
common to face issues of data loss and data replication through Cartesian coordinates and to analyse geospatial
[1, 41, 42]. data [2, 11, 22, 24]. Latest techniques use Unmanned Aer-
ial Vehicle (UAV, commonly known as drones) with GIS
BIM in heritage to scan the surroundings. This is particularly useful when
This section reviews the different usage of BIM in the landscape is connected to the studied building, as it
heritage and assesses which areas are under active has been done for the Borobudur Temple [51].
development.
Point cloud post‑processing
Survey TLS outputs are point clouds and need to be processed
Surveying a building means detecting its dimensions, its to be used in building the BIM model [34]. There are not
geometry, its style, its materials, etc. This phase is crucial, specific heritage-related issues with this practice; howas it helps to enhance the understanding of the building ever, it is a propaedeutic task to build the BIM model.
[34], and actively supports conservation planning [34, The most common operations are:
43].
Traditionally, surveys were carried out with the trian- • • Noise elimination [8, 18, 23], which consists in
gulation methodology, which consists of taking measure- detecting and eliminating scanned items that are not
ments manually, fixing reference-points (called stations) part of the case study;
and triangulating every corner through a laser device or • • Point cloud registration [8, 18, 49, 57, 58], which cona meter rule tape. Error propagation is contained, since sists in merging different point clouds of the same
every point of the building is determined through two object, deriving from different scanning sessions;
measures [44]. • • Meshing [18, 29, 57], which consists of creating tri-
The current trend is, however, to combine Digital Pho- angulated surfaces to be turned into 3D models aftertogrammetry with Laser Scanning, as described in many wards—to be done with specific software.
of the articles reviewed [7–9, 15, 18, 19, 34, 41, 42, 45–
52]. Digital Photogrammetry is based on the triangulation This task is long and elaborate, but there are some
principle [18, 52, 53], as the images produced are taken attempts to automate it [15, 41, 48, 49, 57, 61]. Automafrom different viewpoints [52]. Combining it with Laser tion is an aspect where research is strongly active, as it
Scanning allows the capture of high-resolution photo- would allow quicker and cheaper surveys when applied
graphs of materials’ textures [1, 18, 32, 53, 54] and as a to the heritage sector. Moreover, an architect/restorer
consequence, information of material degradation [32]. charged to digitise and provide a conservation project
The photographs need to be post-processed, and this is of a heritage building, would be struggling if they had to
normally possible with just one piece of software [4, 8]. manually post-process point clouds by themselves. These
However, the combination of Laser Scanning outputs tasks are not particularly straightforward, and very often
and Digital Photogrammetry ones can be delicate, as the specific photogrammetry knowledge is required.
devices must be both properly calibrated, and error prop- For instance, Garagnani developed a new plug-in,
agation is likely to occur [53]. It is also possible to com- called GreenSpider, which helps in the automation of
pose a structure from high-resolution images through importing point clouds [15, 48, 49]. GreenSpider imports
Structure from Motion (SfM) [50, 55] methodology. SfM some selected points of the point cloud and it transforms
is based on the principle that 4 non-coplanar surfaces them into snaps (i.e. reference points), allowing the bonds
can be detected by three orthographic projections [55]. to be retraced and converted into 3D smart objects. PracThis method consists in taking photographs moving the tically, GreenSpider allows the user to select which points
of the cloud are needed, and it converts them into masses

<!-- p. 4 -->

Pocobelli et al. Herit Sci (2018) 6:30 Page 4 of 15

(i.e. 3D undefined objects). These masses can be • • “Level 0: Unmanaged CAD, probably 2D, with paper
imported in any 3D modelling platform—after being […] as the most likely data exchange mechanism.”
embedded with semantic information, such as materials, • • “Level 1: Managed CAD in 2D or 3D format […] with
dimensions, etc., and then be inserted into the BIM a collaboration tool providing a common data envimodel as “families”, i.e. categories of similar objects. ronment, possibly some standard data structures and
Additionally, a metadata enrichment can be provided by formats. […].”
saving GreenSpider objects as Industry Foundation • • “Level 2: Managed 3D environment held in separate
Classes (IFC). IFC is an exchange file format standard “BIM(M)3” tools with attached data. […] The
that describes virtual objects able to store information approach may utilise 4D Programme data and 5D
and data.1 GreenSpider is a noteworthy example of auto- cost elements.”
mation endeavours, as it has been designed to run • • “Level 3: Fully open process and data integration […].
directly on a BIM platform as a plug-in. This study tries Managed by a collaborative model server. Could be
to overcome typical conversion problems that are often regarded as iBIM4 or integrated BIM(M) potentially
faced with heritage BIM. However, the process is rather employing concurrent engineering processes.”
long and laborious, and it should be considered as a
work-in-process research. Historic Scotland [5] “translates” this definition into a
Other attempts of automation of post-processing have heritage-specific language:
been made. In 2014, Oreni et al. [59, 60] developed a
methodology using Non Uniform Rational Basis Splines • • “Level 0: this could refer to a scenario where survey
(NURBS). NURBS allow modelling through vector information is manually obtained on site using tapes
extraction from point clouds using mathematical func- and dumpy levels, drawn up using a CAD package
tions. Another example is the Cloud-to-BIM-to-FEM [62] in an unstructured format, and then communicated
method, which is not exactly an automation, it is rather using paper plots.”
a procedure that converts point clouds to BIM and then • • “Level 1: this could be a scenario where the site data
simulates the structural behaviour using Finite Element is obtained digitally with an EDM (electronic disMethod (FEM). tance meter, commonly known as “Total Station”)
and then transferred to a 2D or 3D CAD environBIM maturity levels ment that uses standardised data structures.”
BIM models can be created with different levels of accu- • • “Level 2: this could be a scenario where the site data
racy. During conversion between point cloud and geo- is obtained digitally in an-inherently 3D format using
metrical model, several decisions can be made, in order a laser scanner, for instance, which is then transferred
to achieve different ranges of precision. The BIM litera- to a discipline-specific, standardised, parametric 3D
ture refers to Level of Detail (LoD) and to Level of Infor- modelling environment, but communicates and colmation (LoI). LoD refers to the graphical elements of the laborates with other disciplines using industry-standmodel, whilst LoI refers to non-graphical information.2 ard interface tools (e.g., IFCs). […].”
Specifically, BSI PAS 1192:2-2013 [63] define LoD as “the
level of detail should as a minimum represent the space It is worth noticing that no Level 3 is considered for
allocation for the product’s access space for maintenance, heritage buildings. Note as well that, while the industry
installation and replacement space in addition to its definitions of these levels include non-structural inforoperational space. For example, the space required to mation such as cost, their heritage equivalents concenturn on or turn off valves. […] The “level of model detail” trate exclusively on the geometry of the building.
is the description of graphical content of models at each Tendencies in BIM for heritage are to create HBIM
of the stages […].”, whilst LoI is defined as “[…] the models that have a maturity level of 2,5 i.e. which geodescription of non-graphical content of models at each of metrical data have been derived through automatic prothe stages”. The BIM Task Group [64] defines the BIM cedures—such as laser scanning sessions—and the BIM
levels of maturity, where the geometry is linked to its model is created through parametric objects.
information holding capability. Four levels have been
identified, defined as the following:

3  BIM(M) refers to management of “collection and exploitation of informa-
tion across a project” [62].
4  iBIM stands for “Integrated Building Information Modelling” and it is a
1  https​://www.iso.org/stand​ard/51622​.html; http://build​ingsm​art.org/ifc/. BIM model that includes “concurrent engineering processes” [62].
2  https​://www.desig​ningb​uildi​ngs.co.uk/wiki/Level​_of_detai​l_for_BIM. 5  http://bim4h​erita​ge.org/.

<!-- p. 5 -->

Pocobelli et al. Herit Sci (2018) 6:30 Page 5 of 15

Fig. 1  Wall Façade as a GDL object. a Variables for opening, b GDL script, c single panel, d automated panels Source Dore and Murphy [11]. Cour‑
tesy of C. Dore and IEEE

Modelling: smart object libraries Detail a represents the variables that define the location
The modelling phase is where all the task previously of an opening these are illustrated in the vector diagram
explained culminates. BIM software allows the digitisa- in the centre. The variable consists of the size of the opention of buildings, providing geometrical, architectural ing and the distance of the opening from other objects,
and material information [3, 7]. Moreover, environmen- in this case other openings. The GDL script is illustrated
tal data and energy performance analysis can be added in detail b, which generates the single panel in detail c.
through dedicated plug-ins. BIM models are not just The panel can then be repeated to form the full panel in
drawings, but they hold semantic information [65], with detail d. The use of GDL scripts are an example of buildparametric smart object libraries, such as the previously ing code-based library objects (as opposed to graphic
mentioned HBIM [9–12, 18, 19, 66] Parametric elements based) which include as many geometric parameters as
are digital objects that can be modified/updated when possible allowing for the objects to be revised to comply
needed [7, 14, 19, 20, 22]. They are modelled in Geomet- with different scenarios and plotted from point cloud or
ric Descriptive Language (GDL) [9, 12, 18, 19, 66], which other survey data.
means that are defined by parameters (See Fig. 1). Fig- HBIM is commonly intended as a specific library of
ure 1 illustrates the potential to automate library parts parametric smart objects [21, 62]. However, when it was
based on numeric data extracted from the point cloud. created in 2009 [9–12, 18, 19, 66], the authors themselves

<!-- p. 6 -->

Pocobelli et al. Herit Sci (2018) 6:30 Page 6 of 15

described it as a specific BIM process for built heritage, JHBIM is an HBIM extension designed for Old Jedwhich consists of three main phases: dah built heritage [4, 8, 24]. Its purpose is to produce a
parametric smart object library that can be used both for
\1. Data collection, carried out integrating TLS and Digi- buildings in Jeddah (specific materials, common mate-
tal Photogrammetry, as it is recommended to reduce rial degradations, local construction techniques) and
error probability [67]; for heritage buildings in general. JHBIM study can help
\2. Data processing, performed through noise cleaning, in management performance and in decision-making
points re-sampling, and point cloud registration; for conservation interventions [4], and it practically
\3. Modelling phase, i.e. polygonal surface meshing and demonstrates that BIM technology is possible for herit-
texturing. A parametric library is created, modelling age buildings. JHBIM has provided a complete library of
the elements by the combination of simple geomet- Jeddah-specific smart objects, which are already linked to
rical shapes, where parameters are decided before graphics, tables and metadata. They can be modified and
shaping. fitted into any BIM model [4, 8, 24].

HBIM should be intended as procedural modelling Metadata handling
[10–12, 14, 19, 52, 68]. Specifically, it creates objects Building Information Modellings most powerful feature
following procedural modelling rules, based on shape is considered to be integration of data [7, 16]. Creating
grammars—shape grammars are 3D elements automati- a BIM parametric 3D model means that every modelled
cally created from a basic “vocabulary” following specific object is linked to a table/spreadsheet, where its param-
“production rules” [10, 12, 19, 52, 66]. These elements eters and its characteristics are displayed [4, 7, 25]. The
can then be adapted case-by-case. They were firstly intro- main problem is metadata handling: these tables show
duced during the 70s by Stiny and Gips [12, 19, 49, 52, specific parameters, but metadata—such as histori69]. cal documentation, photographs, texts, etc. are miss-
HBIM processes are continuously evolving. Latest ing, despite being strongly required in heritage field [34,
studies attempt to automate the HBIM process, creat- 35, 70, 71]. Indeed, previous records, i.e. metadata, help
ing an accessible and modifiable parametric library of the analysis tasks, as they support material recognition,
pre-defined digital objects that can represent a diversity degradation prevention and adequate interventions.
of actual objects. This, for example, has been attempted Additionally, beyond the survey phase accuracy, lack of
with the architectural grammar of classical Europe and historical information strongly affects reliability [17, 72].
Ireland in the seventeenth and eighteenth century [19]. Currently, external database content must be manually
This approach may be argued to be at odds with the copy-pasted inside BIM spreadsheets. This means that
nature of heritage: while historic objects and building if any external databases change their information, BIM
components are valued for their individuality, parametric spreadsheet will not be synchronised, i.e. BIM model
libraries implicitly assume that they can be reproduced will not be updated, and it needs to be changed manudigitally with generalisable digital objects. The possi- ally [20]. Some authors [50, 73] have proposed the use of
bilities and limitations of parametric libraries are under videogame engines to produce a virtual tour into the 3D
active research. Dore and Murphy [11] propose an inte- model, and metadata are provided when clicking on the
gration of HBIM library using ADE, a CityGML extension interested object. Others [56, 74] use Semantic Web Plat-
(GML stands for Generative Modelling Language). ADE form (SWP), where 3D models are displayed and linked
enriches the existing semantic class in CityGML, making to a PHP (PHP: Hypertext Preprocessor) page where texts,
library objects more suitable for describing built herit- documents, photographs and graphics are embedded.
age. Indeed, ADE divides the model into sub-elements A few attempts [75] have been made to use BIM to
that are enriched with attributes and external references. describe thermal behaviour and to monitor energetic
External references can be databases or web resources, parameters, such as temperature, relative humidity, etc.
containing heritage-specific information such as his- in built heritage. Unfortunately, thermo-hygrometric
torical data, chronological phases, different layers, etc. models are still confined in BIM for new buildings [2],
Efforts like ADE have developed the mainstream HBIM even if variation of these parameters are often the main
knowledge. However, many researchers agree on the fact cause of materials’ degradation [32, 40, 76, 77]. A BIM
that—in general—further research is needed [11, 16, 27, model of a heritage building featuring environmental
30, 62] to simplify essential tasks,—and specifically— parameters could play an important role in supporting
especially parametric library creation, which is still man- risk assessment and decision-making for interventions
ual [9, 27] and time-consuming [7, 62]. and for forecasting possible future degradations [32, 77,
78].

<!-- p. 7 -->

Pocobelli et al. Herit Sci (2018) 6:30 Page 7 of 15

Table 1  BIM maturity levels supporting heritage-specific metadata

Heritage-specific metadata BIM level 0 BIM level 1 BIM level 2

Archival photos [81] [7, 81]
[1, 22]
Archival texts/docs [81] [1, 2, 11, 22, 25, 46, 47, 74]
[4, 7, 8, 20, 24, 81]
Historical layers [81] [1, 2, 11, 22, 25, 46, 47, 74]
[4, 7, 8, 20, 24, 81]
Previous interventions [1, 2, 11, 22, 25, 46, 47, 74]
[4, 7, 8, 20, 24]
Degradation patterns [22]
[4, 8, 20, 24]
Material properties and characterisation [11, 22, 25]
[4, 7–9, 19, 20, 24]
Environmental data [2]
Predictions of degradation development
Architectural style and grammar [11, 18, 22]
[4, 8, 9, 19, 24]

: done successfully with BIM platforms. This means that integration of heritage-specific metadata into BIM models has been done successfully using BIM
platforms, and it is possible to reference these researches
: done successfully with integration of external-BIM-environment platforms. This means that integration of heritage-specific metadata has been done
successfully using software/platforms that are not usually considered BIM
: never done, but potentially feasible. This means that integration of heritage-specific metadata has never been attempted, but it reasonable to suppose that it
could be done given the available technologies

Until now, there have been a few attempts to represent • • Environmental data [2, 5];
condition (which could be defined as an assessment of the • • Architectural data [4, 5, 8, 9, 18, 19, 22, 24]; and
state of conservation of an object in view of its desired • • All other data describing the heritage building.
uses) in heritage field with BIM. Essentially, there have
been hypothetical reconstructions of ruins/damaged All the procedures above described can be considered
buildings [28, 46, 56, 79], and stratigraphic depictions part of heritage science, as defined by The National Her-
[27, 50]. It is evident that representing condition is a dif- itage Science Forum [82]: “Heritage science plays a vital
ficult task, as professionals’ interpretational skills play a part in understanding and preserving […] [our] heritage
master role [23, 56, 72, 74, 79, 80]. In practice, the out- and, equally importantly, in giving us fuller understandcome of condition assessments strongly depends on the ing and appreciation of its significance.” Indeed, all metaprofessionals’ experience and rigorousness. data that could potentially be embedded to BIM would
The above-mentioned experiments are certainly effec- have the primary purpose of supporting an increased
tive, even if they do not completely solve BIM integra- understanding of heritage buildings. As shown above,
tion problem, as conversions from volumetric objects (i.e. many researchers have proposed different ways to include
simple digital masses) to “smart” (i.e. parametric) ones several types of information in a BIM environment.
are complicated without strong IT background. However,
they represent an important achievement and a potential Case studies
starting point for further research [6]. Table 1 above shows the relationship between heritage-
To brief, typical metadata for heritage buildings are: specific metadata and BIM maturity levels. Its main aim
is to present how active research is carried out about
• • Archival photographs [1, 5, 22, 81]; embedding metadata, and which techniques are used,
• • Archival research texts/documents, including history relating them to the maturity levels as defined by Historic
of the building, its interventions and previous reports Scotland (cfr. “BIM maturity levels” section). Specifically,
[1, 2, 4, 5, 7, 8, 11, 20, 22, 24–26, 46, 47, 74, 81]; it illustrates what kind of heritage-specific metadata has
• • Condition reports, including survey photographs and been included in which BIM maturity level, and if it has
degradation patterns [4, 5, 8, 20, 22, 24]; been done with a BIM-related method, or with a meth-
• • Material characterisation [4, 5, 7–9, 19, 20, 22, 24– odology external to the BIM environment. Notice that
26]; BIM level 3 has not been included in this table, as it has

<!-- p. 8 -->

Pocobelli et al. Herit Sci (2018) 6:30 Page 8 of 15

not been defined for built heritage (yet) (cfr. “BIM matu- drawing and photographs available online on the CyArk
rity levels” section). The papers reviewed under this sec- database.6 The embedding of metadata has been obtained
tion are clearly not the only ones existing, but they are through modelling of architectural elements in GDL,
a major number and can be considered representative obtaining parametric objects organised into libraries and
of the current trends. Results of this analysis show that referenced inside the models. They used BIM software
combination between Laser Scanning and Digital Photo- GraphiSoft ArchiCAD. Through three different case
grammetry is currently one of the most used techniques, studies, they manage to produce 3D models where inforwhilst metadata are added to 3D models chiefly through mation is embedded in different formats. Specifically for
spreadsheets, images and texts. Parametric smart object the National Monument Edinburgh case study, data were
libraries are created with GDL scripts, following the inserted as it follows (this list is not exhaustive):
shape grammars procedural modelling as in Murphy’s
HBIM and Baik’s JHBIM. However, there seems not to • • Floor plans are directly derived from survey;
exist any attempt to insert degradation pattern predic- • • Rectified images detail elevations and cross sections,
tions yet. and reference the location of library objects;
For the Batawa Project, Fai et al. [81] managed to • • Locations of library objects are expressed in coordiinclude archival photo, previous reports and historical nates, which are stored into spreadsheets.
layers into a mixed-level BIM model, which was obtained
through laser scanning (BIM level 2) and through exist- These experiments show an innovative way of embeding digital files (that could be considered BIM level 1). ding metadata using survey outputs, existing data and
Through Navisworks they also managed to simulate the existing database.
timeline of the different renovation phases the build- Similarly, Murphy et al. [19], produce a BIM level 2
ing has been subjected to. This research is an attempt of model, using integration of laser scanning and phoembedding both quantitative and intangible data in the togrammetry, and modelling with BIM software Gravirtual model, as they are both characterising heritage phiSoft ArchiCAD as well. Dore and Murphy [11] try
buildings. again to improve HBIM ad metadata insertion, this time
Saygi et al. [22] include almost all heritage-specific by uploading the finished BIM model to an international
metadata in their BIM level 2 model of the Kurşunlu GIS platform called CityGML (i.e. external-BIM platKhan in Turkey, to highlight the importance of meta- form), in order to facilitate management and further
data for conservation and management processes. Their analysis. On the other hand, Murphy et al. [18], in one of
approach is an integration of BIM-related methods/ their first experiments, use laser scanning to produce a
software—specifically, they use Autodesk Revit—and BIM level 2 model. Architectural elements are modelled
GIS. Similarly, Oreni et al. [20] (see Fig. 2) produce a using a range of different software, from point clouds ediBIM level 2 model through laser scanning, and manage tors to meshing tools. Similar to Murphy’s HBIM is Baik’s
to include heritage-specific metadata using two different JHBIM [4, 8, 24], as previously stated. JHBIM methodolBIM platform (Autodesk Revit and GraphiSoft Archi- ogy produces a BIM level 2 model through laser scanCAD) and comparing them. This research focuses on the ning, using Autodesk Revit as the main BIM platform.
reconstruction of vaults and floor in the Soldi Palace in It includes almost all metadata such as history, degradaCremona, Italy. The authors conducted a deep analysis tion patterns, material characterisation and—of course—
and survey on the stratigraphy of the building, and they architectural grammar (see Fig. 4). Main objective of this
emphasise the importance of the knowledge of historical research is the creation of an Old Jeddah-specific object
layers and construction techniques in heritage buildings, library, focusing on the Al-Balad district, in order to
specifically for structural elements. They also under- facilitate future digitisations. The authors point out the
line the urgency for a common vocabulary of semantic potential use of JHBIM in future applications, specifically
objects, particularly needed for preventive conservation related to GIS mapping, reconstructions, documentation,
practices. education, dissemination and management support.
Chenaux et al. [9] (see Fig. 3) carry out an experiment In the same way, Ángulo Fornos [1] produces a BIM
to have evaluated a virtual learning environment tool and level 2 model for his case study Casa de Hylas in Spain,
a surveying process conducted by students. Using the as shown in Fig. 5. He uses—again—laser scanning to
survey data produced by the students, a BIM level 2 survey the building. Modelling took place using BIM
model is created, using laser scanning outputs, CAD platform Autodesk AutoCAD Architecture, whilst

6  http://www.cyark​.org/.

<!-- p. 9 -->

Pocobelli et al. Herit Sci (2018) 6:30 Page 9 of 15

Fig. 2  HBIM (©Autodesk Revit) of wooden vault in Soldi Palace in Cremona (Italy): 3D elements modelling process using laser scanner point clouds
and hands on measurements. Information on materials, their stratigraphy and geometrical data of architectural elements are indicated in the data‑
base. Source Oreni et al. [20]. Courtesy of D. Oreni

<!-- p. 10 -->

Pocobelli et al. Herit Sci (2018) 6:30 Page 10 of 15

Fig. 3  Students on-site surveying and HBIM model. Source Chenaux et al. [9]. Courtesy of M. Murphy and A. Čepek—Geoinformatics CTU FCE 2011

metadata—such as archival texts/photographs, histori- reasonable to think that it is feasible/it will be possible in
cal layers and past interventions—were inserted using the near future.
Microsoft ODBC and OLE DB. This research brings Worrell [7] analyses different BIM software and methattention to the current tendency of data loss and data odologies to produce a BIM level 3 model. She finally
replication, as different professionals are often involved produces it, laser scanning during the survey phase and
in the same conservation projects. Its aim is therefore to using BIM platform Autodesk Revit for the modelling.
produce a unique tool, based on a virtual model, that is She also manages to add some metadata and visualise it
capable to hold and display all the needed information— through another BIM platform—Autodesk Navisworks.
and ensure accessibility. This research introduces to the USA’s current trends,
Arayici [2] uses as well laser scanning to digitise his which are following Europe’s ones. Cost is also mencase study in East Manchester. Point cloud editing and tioned: whilst the benefits of using BIM in conservameshing produce an output that can then be used to cre- tion are recognised, the issue of the cost is presented as
ate a CAD model. The CAD model is transferred to BIM a factor that can be a barrier to small trusts/charities or
and information is stored in the Triforma (a MicroSta- enterprises.
tion platform, i.e. BIM-external) library. The actual BIM All the examples cited above, show that integration
model is reached as soon as the elements are turned between laser scanning and photogrammetry is a typiinto IFC objects. Arayici suggests also the possibility of cal way to produce a textured point cloud that will be
integrating BIM models with environmental data. In his converted afterwards into a BIM level 2 model. It is then
paper, he does not specify if he has done it, but it seems common practice to work within a BIM-environment,
using Revit, ArchiCAD, etc., and embedding metadata

<!-- p. 11 -->

Pocobelli et al. Herit Sci (2018) 6:30 Page 11 of 15

Fig. 4  Steps of the Roshan modelling. Source Baik et al. [4]. Courtesy of A. Baik

Fig. 5  View of the textured model from North-West. Source Ángulo Fornos [1]. Courtesy of S. A. Llamas—Arqueología de la Arquitectura

<!-- p. 12 -->

Pocobelli et al. Herit Sci (2018) 6:30 Page 12 of 15

through either external database or BIM spreadsheets/ can represent individual features of historic buildother BIM software. Table 1 cites works done by other ings. Their advantage is that they contain objects that
researchers as well. Discussion of these further studies is are virtual format of existing constructive elements,
omitted for brevity, as results are comparable to the ones and need to be modelled just once. Their parametric
examined above. Table 1 also illustrates that BIM level 0 nature is of great advantage as they can be modified
has been largely surpassed in the heritage sector. Finally, and updated as needed, e.g. when there has been a
Table 1 shows that—to the authors’ knowledge—there maintenance, a process of change, a new discovery,
has not been any attempt to include any predictions of etc. Parametric libraries can contain different kind of
degradation patterns so far. This is logical, as inclusion objects: constructive elements, architecture-language
of environmental parameters is still in its initial phase components, constructive techniques, etc. There are
of research—and weathering forecasts are possible only two main libraries so far: HBIM and JHBIM, which
having a clear understanding of the environment. is a specific HBIM extension for Old Jeddah. These
Concluding, Table 1 and the consequent discussion libraries have been created following procedural
show that research about how to embed metadata is modelling rules, coded with GDL scripts, in order
active and mostly successful. However, inclusion of envi- to automatically create elements that are based on
ronmental parameters—including monitoring and fore- shape grammars. Nevertheless, using parametric
casting—has just started to be studied, and developments smart objects libraries can be slightly restrictive,
are hopefully expected to happen in the near future. since if a specific architectural style is not present in
parametric libraries, they need to be manually modiFuture work and conclusions fied. As new libraries for historical styles are develThe present piece summarises the main findings in the oped, research will be needed in order to identify the
current literature concerning BIM process for heritage limitations of this approach.
buildings. Potentially, BIM is able to support the informa- • • Unified visualisation between 3D model and metation used for conservation and in heritage science pro- data: BIM’s most advantageous feature for heritage
jects; however, technology has not yet been developed to science is perhaps its ability to link 3D models to
a level to permit it. Except for some noteworthy exam- metadata. Through this paper, a table has been creples, nowadays it is common practice to use BIM in the ated to detail the relationships between existing litdevelopment of new buildings, but there are some issues erature and BIM maturity levels, in order to show
with existing buildings. how researchers are currently dealing with the meta-
What follows is a list of the various technological data-embedding issue. Types of metadata are listed,
aspects of BIM and the research issues that emerge in as well as ways in which researchers have managed
relation to heritage science: to embed them into the 3D models. So far, this con-
nection has been made through tables/spreadsheets,
• • Survey techniques: different methods are in use, database and PHP pages. There have also been inter-
from traditional approaches to advanced automated esting experiences in the use of videogame engines
methods such as TLS integrated with GIS, Digital to perform a virtual tour of a 3D model populated
Photogrammetry and UAV. Through these methods, with related metadata. However, research is urgently
a cloud of points representing the digital format of needed in the development of a heritage-specific
the real building is obtained. A common problem is technology that can sustain and display heritage sci-
the optimisation of the conversion from point clouds ence information; that is, historical data, condition,
to 3D models. The exportation step is still difficult environmental parameters, risks to the materials and
and time-consuming, even if there have been some their forecasts.
attempts at automation.
• • Point clouds: the latest survey techniques for built From the achieved findings and from the made
heritage present data into point cloud format, which remarks, it comes out that further research is needed.
has the capacity of capturing very fine details but, at Specifically, future work should focus on:
the same time, the conversion to a 3D model is still
intricate and time-consuming. Further research is • • How to (visually) unify 3D smart models and meta-
needed in order to identify which LoD is required to data;
enable different tasks (analysis, monitoring, record- • • How to automate importation process (from points
ing of condition). cloud to 3D smart model).
• • Parametric smart object libraries are an attempt to • • How to include condition, risks, environmental
square the circle: to create generalizable objects that parameters and forecasts.

<!-- p. 13 -->

Pocobelli et al. Herit Sci (2018) 6:30 Page 13 of 15

Abbreviations 2. Arayici Y. Towards Building Information Modelling for existing structures.
3D: three dimensions; AEC: Architecture, Engineering and Construction; Struct Surv. 2008;26(3):210–22. http://www.emera​ldins​ight.com/doi/
BIM: Building Information Modelling; CAD: Computer Aided Design; CFD: abs/10.1108/S1479​-3563%28201​2%29000​012B0​07. Accessed 2 Nov 2015.
Computational Fluid Dynamics; FEM: Finite Element Method; GDL: Geometric 3. Azhar S, Khalfan M, Maqsood T. Building Information Modelling (BIM):
Descriptive Language; GIS: Geographic Information System; GML: Genera‑ now and beyond. Australas J Constr Econ Build. 2012;12(4):15. http://
tive Modelling Language; HBIM: Historic Building Information Modelling; IFC: epres​s.lib.uts.edu.au/journ​als/index​.php/AJCEB​/artic​le/view/3032/3245.
Industry Foundation Classes; ISH: Institute for Sustainable Heritage; IT: Informa‑ https​://doi.org/10.5130/AJCEB​.v12i4​.3032.
tion Technology; JHBIM: Jeddah Historic Building Information Modelling; 4. Baik A, Alitany A, Boehm J, Robson S. Jeddah historical Building Informa‑
LoD: Level of Detail; LoI: Level of Information; NURBS: Non Uniform Rational tion Modelling “JHBIM” object library. ISPRS Ann Photogramm Remote
Basis Splines; PHP: Hypertext Pre-processor; SfM: Structure from Motion; SWP: Sens Spat Inf Sci. Vol. 2(5), 2014 ISPRS Tech Comm V Symp 23–25 June
Semantic Web Platform; TLS: Terrestrial Laser Scanner; UAV: Unmanned Aerial 2014, Riva del Garda, Italy. 2014;2(5):41–7. http://www.isprs​-ann-photo​
Vehicle. gramm​-remot​e-sens-spati​al-inf-sci.net/II-5/41/2014/. ​Accessed 2 Nov
\2015.
Authors’ contributions 5. Maxwell I. Integrating digital technologies in support of historic Building
DPP has written the main body and the conclusions. JG-B has written the Information Modelling: Bim4conservation (HBIM). 2014. http://www.
abstract and the introduction with DPP, and has repeatedly reviewed the cotac​.org.uk/docs/COTAC​-HBIM-Repor​t-Final​-A-21-April​-2014-2-small​.pdf. ​
whole text, making precious comments and suggestions. PB, JB and JS have Accessed 10 Jan 2017.
reviewed the whole text and have made comments and suggestions to 6. Yen YN, Weng KH, Huang HY. Study on information management for the
improve it. All authors read and approved the final manuscript. conservation of traditional Chinese Architectural Heritage—3D modelling
and metadata representation. ISPRS Ann Photogramm Remote Sens Spat
Author details Inf Sci. 2013;2(5)/W1:331–6. http://www.isprs​-ann-photo​gramm​-remot​
1 The Bartlett School of Environment, Energy and Resources, Institute e-sens-spati​al-inf-sci.net/II-5-W1/331/2013/. ​Accessed 15 Nov 2015.
for Sustainable Heritage, University College London, Central House, 14 Upper 7. Worrell LL. Building information modeling (BIM): the untapped potential
Woburn Place, London WC1H 0NN, UK. 2 Department of Civil, Environmental for preservation documentation and management. Clemson University;
& Geomatic Engineering, Faculty of Engineering Science, University College 2015.
London, Chadwick Building, Gower Street, London WC1E 6BT, UK. 3 Historic 8. Baik A, Boehm J, Robson S. Jeddah historical building information mod‑
England, 37 Tanner Row, York YO1 6WP, UK. 4 Point 2 Surveyors, 17 Slingsby eling “JHBIM” Old Jeddah-Saudi Arabia. Int Arch Photogramm Remote
Place, London WC2E 9AB, UK. Sens Spat Inf Sci. 2013;40(5W2):73–8. http://www.scopu​s.com/inwar​d/
recor​d.url?eid=2-s2.0-84924​28937​3&partn​erID=40&md5=8c861​67738​Acknowledgements 7fca1​ecba4​6c9b0​2343a​33. ​Accessed 2 Nov 2015.
The authors would like to thank David Thickett, English Heritage, for the 9. Chenaux A, Murphy M, Keenaghan G, Jenkins J, McGovern E, Pavia S.
precious comments and suggestions made. Thanks also to Julia Schütz of Combining a virtual learning tool and onsite study visits of four conserva‑
ScanLAB Projects for helping with scanning and point cloud post-processing. tion sites in Europe. Geoinformatics FCE CTU. 2011;6(0):157–69. https​://
Thanks to the Institute for Sustainable Heritage (ISH) of University College ojs.cvut.cz/ojs/index​.php/gi/artic​le/view/2656. https​://doi.org/10.14311​/
London (UCL) for the facilities and the support provided. We would also like to gi.6.21. ​Accessed 1 Nov 2015.
thank SEAHA EPSRC doctoral training centre. 10. Dore C, Murphy M, McCarthy S, Brechin F, Casidy C, Dirix E. Structural
simulations and conservation analysis—historic building information
Competing interests model (HBIM). ISPRS Int Arch Photogramm Remote Sens Spat Inf Sci.
The authors declare that they have no competing interests. 2015;40(5)/W4(5W4):351–7. http://www.int-arch-photo​gramm​-remot​
e-sens-spati​al-inf-sci.net/XL-5-W4/351/2015/. ​Accessed 6 Nov 2015.
Availability of data and materials 11. Dore C, Murphy M. Integration of historic building information modeling
Not applicable. (HBIM) and 3D GIS for recording and managing cultural heritage sites. In:
2012 18th International conference on virtual systems and multimedia.
Consent for publication IEEE. 2012. p. 369–76. http://arrow​.dit.ie/besch​recco​n/71/. https​://doi.
Not applicable. org/10.1109/vsmm.2012.63659​47. ​Accessed 3 Nov 2015.
\12. Dore C, Murphy M. Semi-automatic modelling of building façades with
Ethics approval and consent to participate shape grammars using historic Building Information Modelling. Proc Int
Not applicable. Arch Photogramm Remote Sens Spat Inf Sci. 2013;40:57–64.
\13. Fai S, Filippi M, Paliaga S. Parametric modelling (BIM) for the documenta‑
Funding tion of vernacular construction methods: a BIM model for the commis‑
This paper is part of Danae P Pocobelli’s Ph.D. The above-mentioned Ph.D. is sariat building, Ottawa, Canada. ISPRS Ann Photogramm Remote Sens
funded by SEAHA, an EPSRC doctoral training centre. Spat Inf Sci. 2013;2(5)/W1(5):115–20. http://adsab​s.harva​rd.edu/abs/2013I​
SPAn.II5a.115F. ​Accessed 10 Nov 2015.
\14. Fai S, Sydor M. Building Information Modelling and the documentation
Publisher’s Note of architectural heritage: between the “typical” and the “specific”. In: 2013
Springer Nature remains neutral with regard to jurisdictional claims in pub‑ digital heritage international congress (DigitalHeritage). IEEE; 2013. p.
lished maps and institutional affiliations.
731–4. http://ieeex​plore​.ieee.org/xpls/abs_all.jsp?arnum​ber=67438​28. ​ Accessed 10 Nov 2015.
Received: 27 July 2017 Accepted: 9 April 2018 15. Garagnani S, Manferdini AM. Parametric accuracy : building information
modeling process applied to the cultural heritage preservation. ISPRS
Int Arch Photogramm Remote Sens Spat Inf Sci. 2013;40(5)/W1:87–92.
http://www.int-arch-photo​gramm​-remot​e-sens-spati​al-inf-sci.net/XL-
5-W1/87/2013/. ​Accessed 10 Nov 2015.
\16. Logothetis S, Delinasiou A, Stylianidis E. Building Information ModellingReferences
for cultural heritage: a review. ISPRS Ann Photogramm Remote Sens Spat1. Angulo Fornos R. Construcción de la base gráfica para un sistema de
Inf Sci. 2015;2(5)/W3:177–83. http://www.isprs​-ann-photo​gramm​-remot​ información y gestión del patrimonio arquitectónico: Casa de Hylas.
e-sens-spati​al-inf-sci.net/II-5-W3/177/2015/. ​Accessed 11 Nov 2015. Arqueol la Arquit. 2013;0(9):11–25. http://arqar​qt.revis​tas.csic.es/index​
\17. Di Mascio D, Wang X. Building Information Modelling (BIM)-supported .php/arqar​qt/artic​le/view/138/132. https​://doi.org/10.3989/arqar​
cooperative design in sustainable renovation projects. In: Cooperative qt.2012.10005​. Accessed 3 Nov 2015.
design, visualization, and engineering SE-30. 2013. p. 205–12. http://
dx.doi.org/10.1007/978-3-642-40840​-3_30. ​Accessed 2 Nov 2015.

<!-- p. 14 -->

Pocobelli et al. Herit Sci (2018) 6:30 Page 14 of 15

\18. Murphy M, McGovern E, Pavia S. Historic Building Information Modelling 33. McCaig I. Practical building conservation. Conservation basics. Farnham:
(HBIM). Struct Surv. 2009;27(4):311–27. http://www.emera​ldins​ight.com/ English He, Ashgate; 2013. p. 384.
doi/book/10.1108/S1479​-3563%28201​2%2912_Part_B. ​Accessed 13 Nov 34. Williams J. NHSS report 2—the use of science to enhance our under‑
\2015. standing of the past. 2009. www.herit​agesc​ience​strat​egy.org.uk. ​
\19. Murphy M, McGovern E, Pavia S. Historic Building Information Model‑ Accessed 23 Feb 2016.
ling—adding intelligence to laser and image based surveys of European 35. Historic England. Conservation principles, policies and guidance. 2008.
classical architecture. ISPRS J Photogramm Remote Sens. 2013;76:89–102. https​://conte​nt.histo​ricen​gland​.org.uk/image​s-books​/publi​catio​ns/conse​
https​://doi.org/10.1016/j.isprs​jprs.2012.11.006. rvati​on-princ​iples​-susta​inabl​e-manag​ement​-histo​ric-envir​onmen​t/conse​
\20. Oreni D, Brumana R, Georgopoulos A, Cuca B. HBIM for conservation and rvati​onpri​ncipl​espol​icies​guida​nceap​r08we​b.pdf/. ​Accessed 17 Mar 2017
management of built heritage : towards a library of vaults and wooden 36. Williams J. NHSS Report 3—understanding capacity in the heritage sci‑
bean floors. ISPRS Ann Photogramm Remote Sens Spat Inf Sci. 2013;2(5)/ ence sector. 2009. www.herit​agesc​ience​strat​egy.org.uk. ​Accessed 23 Feb
W1:215–21. http://www.isprs​-ann-photo​gramm​-remot​e-sens-spati​ 2016.
al-inf-sci.net/II-5-W1/215/2013/. https​://doi.org/10.5194/isprs​annal​s-ii- 37. ICOMOS, ISCS. Illustrated glossary on stone deterioration patterns. 2008.
5-w1-215-2013. ​Accessed 13 Nov 2015. http://www.icomo​s.org/publi​catio​ns/monum​ents_and_sites​/15/pdf/
\21. Oreni D. From 3D content models to HBIM for conservation and manage‑ Monum​ents_and_Sites​_15_ISCS_Gloss​ary_Stone​.pdf. ​Accessed 15 Aug
ment of built heritage. In: The 13th international conference on computa‑ 2016.
tional science and its applications. 2013. p. 344–57. http://link.sprin​ger. 38. D’Agostino D, Congedo PM, Cataldo R. Computational fluid dynam‑
com/10.1007/978-3-642-39649​-6_25. ics (CFD) modeling of microclimate for salts crystallization control and22. Saygi G, Agugiaro G, Hamamcıoğlu-Turan M, Remondino F. Evaluation of artworks conservation. J Cultur Herit. 2014;15(4):448–57.
GIS and BIM roles for the information management of historical buildings. 39. Grau-Bové J, Mazzei L, Malki-Ephstein L, Thickett D, Strlič M. Simulation of
ISPRS Ann Photogramm Remote Sens Spat Inf Sci. 2013;2:283–8. http:// particulate matter ingress, dispersion and deposition in a historical build‑
adsab​s.harva​rd.edu/abs/2013I​SPAn.II5a.283S. ​Accessed 14 Nov 2015. ing. J Cultur Herit. 2016;18:199–208.
\23. Volk R, Stengel J, Schultmann F. Building Information Modelling (BIM) for 40. Lopez-Gonzalez L, de Cosca RO, Gomez-Heras M, Garcia-Morales S. A 4D
existing buildings—literature review and future needs. Autom Constr. GIS methodology to study variations in evaporation points on a heritage
2014;38:109–27. https​://doi.org/10.1016/j.autco​n.2013.10.023. building. Environ Earth Sci. 2016;75(14):1113.
\24. Baik A, Yaagoubi R, Boehm J. Integration of Jeddah historical BIM and 3D 41. Koehl M, Viale A, Reeb S. A historical timber frame model for diagnosis
GIS for documentation and restoration of historical monument. ISPRS Int and documentation before building restoration. ISPRS Ann Photogramm
Arch Photogramm Remote Sens Spat Inf Sci. 2015;40(5)/W7(5W7):29–34. Remote Sens Spat Inf Sci. 2013;2(2)/W1:201–12. http://www.isprs​
http://www.int-arch-photo​gramm​-remot​e-sens-spati​al-inf-sci.net/XL- -ann-photo​gramm​-remot​e-sens-spati​al-inf-sci.net/II-2-W1/201/2013/. ​
5-W7/29/2015/. ​Accessed 2 Nov 2015. Accessed 11 Nov 2015.
\25. Columbu S, Verdiani G. Digital survey and material analysis strategies 42. Tang P, Huber D, Akinci B, Lipman R, Lytle A. Automatic reconstruction of
for documenting, monitoring and study the Romanesque churches in as-built building information models from laser-scanned point clouds: a Sardinia, Italy. In: Ioannides M, Magnenat-Thalmann N, Fink E, Žarnić R, review of related techniques. Autom Constr. 2010;19(7):829–43. https​://
Yen A-Y, Quak E, editors. Cultural heritage: documentation, preservation, doi.org/10.1016/j.autco​n.2010.06.007.
and protection: 5th international conference, EuroMed 2014, Limassol, 43. Di Giulio R, Balzani M, Ferrari F. Digital morphometric survey for docu‑
Cyprus, November 3–8, 2014. Cham: Springer International Publishing; mentation, conservation and restoration works: the MUDI project. In: 2014. p. 446–53 (Lecture Notes in Computer Science; vol. 8740). http:// Ioannides M, Magnenat-Thalmann N, Fink E, Žarnić R, Yen A-Y, Quak E, edi‑
link.sprin​ger.com/10.1007/978-3-319-13695​-0. ​Accessed 4 Nov 2015. tors. Digital heritage. Progress in cultural heritage: documentation, pres‑
\26. Ma Y-P, Hsu CC, Lin M-C, Tsai Z-W, Chen J-Y. Parametric Workflow (BIM) ervation, and protection: 5th international conference, EuroMed 2014,
for the repair construction of traditional historic architecture in Taiwan. Limassol, Cyprus, November 3–8, 2014. Proceedings. Cham: Springer
ISPRS Int Arch Photogramm Remote Sens Spat Inf Sci. 2015;40(5)/ International Publishing; 2014. p. 617–24 (Lecture Notes in Computer
W7(5W7):315–22. http://www.int-arch-photo​gramm​-remot​e-sens-spati​ Science; vol. 8740). http://link.sprin​ger.com/10.1007/978-3-319-13695​-0.
al-inf-sci.net/XL-5-W7/315/2015/. ​Accessed 28 Oct 2017. 44. Carpiceci M. Il rilievo dello spazio architettonico Principi geometrici e
\27. Brumana R, Oreni D, Raimondi A, Georgopoulos A, Bregianni A. From sur‑ grafici. Edizioni d. Roma: Kappa; 2000. p. 64.
vey to HBIM for documentation, dissemination and management of built 45. Baila A, Mazza L, Anzani A. Design for knowledge and restoration.
heritage: the case study of St. Maria in Scaria d’Intelvi. In: Proceedings instrumental survey at Santa Maria in Celso. In: Ioannides M, Magnenat- of the DigitalHeritage 2013—federating the 19th Int’l VSMM, 10th Euro‑ Thalmann N, Fink E, Žarnić R, Yen A-Y, Quak E, editors. Cultural heritage:
graphics GCH, and 2nd UNESCO Memory of the World Conferences, Plus documentation, preservation, and protection: 5th international confer‑
Special Sessions from CAA, Arqueologica 20 et al. IEEE; 2013. p. 497–504. ence, EuroMed 2014, Limassol, Cyprus, November 3–8, 2014. Cham:
http://ieeex​plore​.ieee.org/docum​ent/67437​89/. Accessed 2 Nov 2015. Springer International Publishing; 2014. p. 427–37. (Lecture Notes in
\28. Ludwig M, Herbst G, Rieke-Zapp D, Rosenbauer R, Rutishauser S, Zell‑ Computer Science; vol. 8740). http://link.sprin​ger.com/10.1007/978-3-
weger A. The advantages of parametric modeling for the reconstruction 319-13695​-0.
of historic buildings. The example of the in war destroyed church of St. 46. Balletti C, Brussa N, Gottardi C, Guerra F. The documentation and reinte‑
Catherine (Katharinenkirche) in Nuremberg. ISPRS Int Arch Photogramm gration of a lost past. ISPRS Ann Photogramm Remote Sens Spat Inf Sci.
Remote Sens Spat Inf Sci. 2013;40(5)/W1:161–5. http://www.int-arch- 2014;2(5):49–55. http://www.isprs​-ann-photo​gramm​-remot​e-sens-spati​
photo​gramm​-remot​e-sens-spati​al-inf-sci.net/XL-5-W1/161/2013/. ​ al-inf-sci.net/II-5/49/2014/. ​Accessed 2 Nov 2015.
Accessed 11 Nov 2015. 47. Cuca B, Agapiou A, Kkolos A, Hadjimitsis D. Integration of innovative
\29. Arias P, Armesto J, Di-Capua D, González-Drigo R, Lorenzo H, Pérez-Gracia surveying technologies for purposes of 3D documentation and valorisa‑
V. Digital photogrammetry, GPR and computational analysis of structural tion of St. Herakleidios monastery. In: Ioannides M, Magnenat-Thalmann damages in a mediaeval bridge. Eng Fail Anal. 2007;14(8):1444–57. ​ N, Fink E, Žarnić R, Yen A-Y, Quak E, editors. Cultural heritage: documenta‑
Accessed 3 Nov 2015. tion, preservation, and protection: 5th international conference, EuroMed
\30. Brumana R, Oreni D, Cuca B, Binda L, Condoleo P, Triggiani M. Strategy for 2014, Limassol, Cyprus, November 3–8, 2014. Cham: Springer Interna‑
integrated surveying techniques finalized to interpretive models in a Byz‑ tional Publishing; 2014. p. 387–95. (Lecture Notes in Computer Science;
antine Church, Mesopotam, Albania. Int J Archit Herit. 2014;8(6):886–924. vol. 8740). http://link.sprin​ger.com/10.1007/978-3-319-13695​-0.
https​://doi.org/10.1080/15583​058.2012.75607​7. 48. Garagnani S. Building Information Modeling semantico e rilievi ad alta
\31. Del Giudice M, Osello A. BIM for cultural heritage. Int Arch Photogramm risoluzione di siti appartenenti al Patrimonio Culturale. DISEGNARECON.
Remote Sens Spat Inf Sci ISPRS Arch. 2013;40(5W2):225–9. http:// 2012;5(10):297–302. https​://diseg​narec​on.unibo​.it/artic​le/view/3359. ​
www.scopu​s.com/inwar​d/recor​d.url?eid=2-s2.0-84924​33016​9&partn​ Accessed 10 Nov 2015.
erID=tZOtx​3y1. ​Accessed 1 Nov 2015. 49. Garagnani S. Building information modeling and real world knowledge:32. Odgers D, Henry A. Practical building conservation: stone. Farnham: a methodological approach to accurate semantic documentation for
Ashgate, English He; 2012. p. 338. the built environment. In: 2013 Digital heritage international congress

<!-- p. 15 -->

Pocobelli et al. Herit Sci (2018) 6:30 Page 15 of 15

(DigitalHeritage). IEEE; 2013. p. 489–96. http://ieeex​plore​.ieee.org/lpdoc​s/ 65. Losciale LV, Lombardo J, De Luca L. New semantic media and 3D archi‑
epic0​3/wrapp​er.htm?arnum​ber=67437​88. ​Accessed 10 Nov 2015. tectural models representation. In: 2012 18th international conference50. Micoli L, Guidi G, Angheleddu D, Russo M. A multidisciplinary approach on virtual systems and multimedia. IEEE; 2012. p. 533–6. http://ieeex​plore​
to 3D survey and reconstruction of historical buildings. In: 2013 digital .ieee.org/docum​ent/63659​70/. ​Accessed 11 Nov 2015.
heritage international congress (DigitalHeritage). IEEE; 2013. p. 241–8. 66. Dore C, Murphy M. Semi-automatic techniques for as-built BIM façade
http://ieeex​plore​.ieee.org/docum​ent/67447​60/. ​Accessed 11 Nov 2015. modeling of historic buildings. In: 2013 digital heritage international
\51. Suwardhi D, Menna F, Remondino F, Hanke K, Akmalia R. Digital 3D congress (DigitalHeritage). IEEE; 2013. p. 473–80. http://ieeex​plore​.ieee.
Borobudur-integration of 3D surveying and modeling techniques. ISPRS org/docum​ent/67437​86/. ​Accessed 05 Nov 2015.
Int Arch Photogramm Remote Sens Spat Inf Sci. 2015;40(5)/W7:417–23. 67. Remondino F, El-Hakim S. Image-based 3D modelling: a review.
http://www.int-arch-photo​gramm​-remot​e-sens-spati​al-inf-sci.net/XL- Photogramm Rec. 2006;21(115):269–91. https​://doi.org/10.111
5-W7/417/2015/. ​Accessed 15 Nov 2015. 1/j.1477-9730.2006.00383​.x.
\52. Dore C, Murphy M. Semi-automatic generation of as-built BIM façade 68. Baik A. From point cloud to Jeddah heritage BIM Nasif historical house—
geometry from laser and image data. J Inf Technol Constr. 2014;19:20–46. case study. Digit Appl Archaeol Cultur Herit. 2017;4:1–18. https​://doi.
\53. Beraldin J-A. Integration of laser scanning and close-range photogram‑ org/10.1016/j.daach​.2017.02.001.
metry—the last decade and beyond. Int Arch Photogramm Remote Sens. 69. Stiny G, Gips J. Shape grammars and the generative specification of
2004;35(Part B5):1031–42. painting and sculpture. In: Inf Process 71 Proc IFIP Congr 1971. vol. 2,
\54. Rossi D. An image-based modelling experience about social facilities, 1972.
built during the fascist period in middle-Italy. ISPRS Int Arch Photogramm 70. Department for Culture Media and Sport. Scheduled monuments &
Remote Sens Spat Inf Sci. 2012;38(5):83–9. http://www.int-arch-photo​ nationally important but non-scheduled monuments. 2013. http://
gramm​-remot​e-sens-spati​al-inf-sci.net/XXXVI​II-5-W16/83/2011/isprs​archi​ www.histo​ric-scotl​and.gov.uk/index​/herit​age/searc​hmonu​ments​.htm. ​
ves-XXXVI​II-5-W16-83-2011.pdf. ​Accessed 14 Nov 2015. Accessed 25 Oct 2017.
\55. Manferdini AM, Galassi M. Assessments for 3D reconstructions of cultural 71. Gaiani M. Creare Sistemi informativi per studiare, conservare, gestire
heritage using digital technologies. ISPRS Int Arch Photogramm Remote e comunicare sistemi architettonici e archeologici complessi. Diseg‑
Sens Spat Inf Sci. 2013;40(5)/W1:167–74. http://www.int-arch-photo​ nareCon. 2012;5(10):9–20.
gramm​-remot​e-sens-spati​al-inf-sci.net/XL-5-W1/167/2013/isprs​archi​ves- 72. English Heritage. Discovering the past, shaping the future: research
XL-5-W1-167-2013.pdf. ​Accessed 11 Nov 2015. strategy 2005–2010. 2005. http://www.engli​sh-herit​age.org.uk/resea​rch. ​
\56. Kurdy M, Biscop J-L, De Luca L, Florenzano M. 3D Virtual anastylosis and Accessed 23 Feb 2016.
the reconstruction of several buildings in the site of Saint-Simeon, Syria. 73. Pauwels P, Bod R, Di Mascio D, De Meyer R. Integrating Building Informa‑
ISPRS Int Arch Photogramm Remote Sens Spat Inf Sci. 2012;38(5):45–52. tion Modelling and semantic web technologies for the management of
http://www.int-arch-photo​gramm​-remot​e-sens-spati​al-inf-sci.net/XXXVI​ built heritage information. In: 2013 digital heritage international congress
II-5-W16/45/2011/. ​Accessed 11 Nov 2015. (DigitalHeritage). IEEE; 2013. p. 481–8. http://ieeex​plore​.ieee.org/docum​
\57. Allen PK, Troccoli A, Smith B, Murray S, Stamos I, Leordeanu M. New ent/67437​87/. ​Accessed 14 Nov 2015.
methods for digital modeling of historic sites. Comput Graph Appl IEEE. 74. Stefani C, Busayarat C, Renaudin N, De Luca L, Véron P, Florenzano M. An
2003;23(6):32–41. http://ieeex​plore​.ieee.org/xpls/abs_all.jsp?arnum​ image-based approach for the architectural modeling of past states. Int
ber=12423​80. ​Accessed 3 Nov 2015. Arch Photogramm Remote Sens Spat Inf Sci. 2011;38:2–4. http://sam.58. Basir WNFWA, Setan H, Majid Z, Chong A. Geospatial database for ensam​.eu/handl​e/10985​/9806. ​Accessed 15 Nov 2015.
heritage building conservation. IOP Conf Ser Earth Environ Sci. 75. Percy K, Ward S, Quintero MS, Morrison T. Integrated digital technologies
2014;18(1):12087. http://www.scopu​s.com/inwar​d/recor​d.url?eid=2- for the architectural rehabilitation & conservation of Beinn Bhreagh Hall &
s2.0-84902​31241​1&partn​erID=tZOtx​3y1. ​Accessed 2 Nov 2015. surrounding site, Nova Scotia, Canada. ISPRS Ann Photogramm Remote59. Oreni D, Brumana R, Della Torre S, Banfi F, Barazzetti L, Previtali M. Survey Sens Spat Inf Sci. 2015;2(5)/W3:235–41. http://searc​h.proqu​est.com/
turned into HBIM: the restoration and the work involved concerning the openv​iew/68bdd​d48cb​bd9ee​aa5d7​271a3​5528f​80/1?pq-origs​ite=gscho​
Basilica di Collemaggio after the earthquake (L’Aquila). ISPRS Ann Photo‑ lar&cbl=20376​81. ​Accessed 14 Nov 2015. gramm Remote Sens Spat Inf Sci. 2014;2(5):267–73. 76. Sandrolini F, Franzoni E. An operative protocol for reliable measurements
\60. Oreni D, Brumana R, Banfi F, Bertola L, Barazzetti L, Cuca B, et al. Beyond of moisture in porous materials of ancient buildings. Build Environ.
crude 3D models: from point clouds to historical building information 2006;41(10):1372–80.
modeling via NURBS. In: Ioannides M, Magnenat-Thalmann N, Fink E, 77. Williams J. NHSS Report 1—the role of science in the management of the Žarnić R, Yen A-Y, Quak E, editors. Cultural heritage: documentation, pres‑ UK’ s heritage. 2009.
ervation, and protection: 5th international conference, EuroMed 2014, 78. Science and Heritage. Details of the call for collaborative research stu‑
Limassol, Cyprus, November 3–8, 2014. Cham: Springer International dentships in science and heritage October 2007. 2007.
Publishing; 2014. p. 166–75 (Lecture Notes in Computer Science; vol. 79. Bruno Jr A, Spallone R. Cultural heritage conservation and communica‑
8740). http://link.sprin​ger.com/10.1007/978-3-319-13695​-0. tion by digital modeling tools. Case studies: minor architectures of the
\61. Quattrini R, Malinverni ES, Clini P, Nespeca R, Orlietti E. From TLS to HBIM. thirties in the Turin area. ISPRS Ann Photogramm Remote Sens Spat Inf
High quality semantically-aware 3d modelling of complex architec‑ Sci. 2015;2(5)/W3:25–32. http://www.isprs​-ann-photo​gramm​-remot​
ture. ISPRS Int Arch Photogramm Remote Sens Spat Inf Sci. 2015;40(5)/ e-sens-spati​al-inf-sci.net/II-5-W3/25/2015/. ​Accessed 2 Nov 2015.
W4(5W4):367–74. http://www.int-arch-photo​gramm​-remot​e-sens-spati​ 80. English Heritage. Research Agenda : an introduction to English Heritage’s
al-inf-sci.net/XL-5-W4/367/2015/. Accessed 14 Nov 2015. research themes and programmes. London: English Heritage; 2005.
\62. Barazzetti L, Banfi F, Brumana R, Gusmeroli G, Previtali M, Schiantarelli G. 81. Fai S, Graham K, Duckworth T, Wood N, Attar R. Building Information Mod‑
Cloud-to-BIM-to-FEM: structural simulation with accurate historic BIM elling and heritage documentation. In: Proceedings of the 23rd interna‑
from laser scans. Simul Model Pract Theory. 2015;57:71–87. https​://doi. tional symposium, international scientific committee for documentation
org/10.1016/j.simpa​t.2015.06.004. of cultural heritage (CIPA). 2011. p. 12–6. https​://www.seman​ticsc​holar​
\63. British Standards Institution. PAS 1192-2:2013. Specification for informa‑ .org/paper​/Build​ing-Infor​matio​n-Model​ling-and-Herit​age-Fai-Graha​m/
tion management for the capital/delivery phase of construction projects b76a6​be1ab​4c5c1​48757​eac8c​73dc7​a5c29​95999​/pdf. Accessed 10 Nov
using Building Information Modelling. 2013. 2015.
\64. BIM Industry Working Group. A report for the Government Construction 82. NHSS Steering Group. Our vision and strategy for heritage science. NHSS
Client Group—March 2011. Communications. 2011. http://www.bimta​ Vision & Strategy. 2010.
skgro​up.org/wp-conte​nt/uploa​ds/2012/03/BIS-BIM-strat​egy-Repor​t.pdf. ​
Accessed 25 Oct 2017.
