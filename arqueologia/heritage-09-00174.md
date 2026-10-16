---
type: libro
title: "An Integrated Workflow from Reality-Based Survey to HBIM and Immersive Reconstruction: The Aeclanum Archaeological Park"
author: "Marco Limongiello, Lorenzo Radaelli and Laura De Girolamo"
categoria: "Arqueología"
paginas: 19
extraccion: "texto"
fuente: "local:E:/Biblioteca digital/Arqueología/heritage-09-00174.pdf"
convertido: 2026-10-12
---

# An Integrated Workflow from Reality-Based Survey to HBIM and Immersive Reconstruction: The Aeclanum Archaeological Park

> Texto extraído de `Arqueología/heritage-09-00174.pdf` (19 páginas, texto). El PDF original está en el disco E: (Biblioteca digital); `<!-- p. N -->` marca el inicio de cada página.

<!-- p. 1 -->

Article
An Integrated Workflow from Reality-Based Survey to HBIM and
Immersive Reconstruction: The Aeclanum Archaeological Park

Marco Limongiello 1,*, Lorenzo Radaelli 2 and Laura De Girolamo 2

1 Department of Civil Engineering, Pegaso Telematic University, 80132 Naples, Italy
2 Department of Cultural Heritage Sciences, University of Salerno, 84084 Fisciano, Italy;
lradaelli@unisa.it (L.R.); ldegirolamo@unisa.it (L.D.G.)
\* Correspondence: marco.limongiello@unipegaso.it

Abstract

Archaeological sites present critical issues related to fragmented documentation systems,
the difficulty of integrating stratigraphic analyses with three-dimensional survey data,
and the lack of digital tools capable of connecting scientific documentation, conservation
needs, and public dissemination. This study proposes an integrated digital workflow for
the archaeological park of Aeclanum, in which reality-based multi-scale survey data are
transformed into an HBIM model structured through stratigraphic interpretation, material
analysis, and semantically organised information. The resulting three-dimensional dataset
supports the subsequent Scan-to-BIM process, ensuring consistency between the digital
representation and the existing remains. Within this framework, the HBIM model is con-
ceived not only as a geometric representation of the current state, but also as an information
environment incorporating data on construction techniques, materials, and decay condi-
tions, thus providing a basis for conservation-oriented assessment and future intervention
priorities. At the same time, the model supports digital reconstruction hypotheses consis-
tent with archaeological evidence, later developed within an immersive environment that
allows visitors to compare the present condition of the site with its reconstructed historical
configuration. The workflow highlights the potential of HBIM as an interface between
survey, knowledge organisation, conservation support, and digital enhancement.

Keywords: HBIM; reality-based modelling; historical reconstruction; remote heritage
access; multiscale 3D survey

\1. Introduction

Archaeological heritage in Italy is characterised by a high degree of complexity, due to
the geographical extent of the sites, their stratified nature, and the continuity of settlements
Academic Editors: Grazia Tucci,
Lidia Fiorini and Franco Niccolucci over thousands of years that have shaped the historical landscape. The Italian territory
preserves an extraordinary density of material evidence—including ancient urban centres,
Received: 28 February 2026
Revised: 24 April 2026 historical infrastructures, monumental complexes, and archaeological sites—which form inAccepted: 25 April 2026 terconnected systems where historical, architectural, landscape, and identity values overlap.
Published: 30 April 2026 Such complexity requires digital approaches capable of integrating spatial documentation,
Copyright: © 2026 by the authors. chronological interpretation, and conservation-related information within structured and
Licensee MDPI, Basel, Switzerland. interoperable environments. Recent literature has highlighted the growing role of digital
This article is an open access article tools in cultural heritage for combining geometric documentation, semantic content, and
distributed under the terms and
data on the state of conservation within coherent information systems [1].
conditions of the Creative Commons

Attribution (CC BY) license.

Heritage 2026, 9, 174 https://doi.org/10.3390/heritage9050174

<!-- p. 2 -->

Heritage 2026, 9, 174 2 of 19

Within this context, information models for cultural heritage have shown signifi-
cant potential for integrating three-dimensional representations with non-geometric data,
enabling more structured forms of documentation and knowledge organisation [2]. In
archaeological contexts, however, this process becomes particularly complex because of
the fragmentary nature of the preserved remains and the presence of multi-phase stratifi-
cation. As a result, the integration of metric survey data, stratigraphic interpretation, and
semantic information requires methods capable of combining geometric reliability with
interpretative transparency [3].
Beyond these methodological issues, archaeological sites also involve significant
operational and resource-related challenges. According to the 2017 ISTAT survey,
293 archaeological areas and parks in Italy are open to the public as cultural sites, un-
der both public and private management [4]. This condition highlights the need to optimise
available resources, to support conservation efforts according to priority criteria, and to rely
on information tools capable of organising survey data and analytical knowledge within a
coherent digital environment. From this perspective, the digitisation of archaeological sites
should not be understood merely as a process of archiving, but rather as the construction of
a dynamic knowledge infrastructure in which reality-based documentation and structured
information can converge.
Within this framework, the archaeological site of Aeclanum was selected as a case
study to test the proposed digital workflow. Its historical stratification, fragmented state
of preservation, and strong relationship with the Via Appia make it a particularly suitable
context for investigating the integration of multi-scale survey, HBIM, conservation-oriented
information, and digital reconstruction.
In this perspective, the evolution of three-dimensional survey techniques—particularly
Terrestrial Laser Scanning and digital photogrammetry—has made it possible to generate
highly accurate and metrically controlled datasets, which now represent a fundamen-
tal basis for the digital documentation of archaeological heritage [5,6]. Rather than being
limited to geometric recording, these datasets provide the objective reference needed to sup-
port subsequent interpretative and information-modelling processes, ensuring consistency
between the surveyed remains and their digital representation.
The most critical step in the process is modelling. In the context of Heritage/Historical
Building Information Modelling (HBIM), this phase cannot be considered neutral: mod-
elling necessarily involves interpretation. Each modelled element is a synthesis of what is
metrically detectable, what can be deduced from stratigraphic and material analysis, and
what is formally necessary for the construction of a coherent information structure [7]. The
process, therefore, involves explicit methodological choices: which elements to reconstruct
by typological analogy, which to simplify to ensure readability and interoperability, and
which to leave deliberately undefined but documented as knowledge gaps [8]. The issue
is not exclusively geometric, but eminently semantic. The construction of the model re-
quires clear criteria for associating information with digital objects, ensuring consistency,
traceability and updatable over time [9].
It is therefore essential to distinguish between data acquired with certainty, informa-
tion derived from documentary evidence, and reconstructive hypotheses, while explicitly
declaring the different levels of reliability associated with each of them. From this per-
spective, HBIM—or, in the archaeological field, ArcheoBIM [10,11]—may be defined as
an information environment that facilitates the organisation of heterogeneous knowledge
and provides a robust basis for conservation-oriented assessments, the planning of future
interventions, and the identification of priority areas [12,13]. At the same time, the integra-
tion of information modelling and immersive technologies has demonstrated the ability to
transform the digital model into an active communication tool, reducing the gap between

https://doi.org/10.3390/heritage9050174

<!-- p. 3 -->

Heritage 2026, 9, 174 3 of 19

scientific research and public enjoyment. In small archaeological sites, the surviving struc-
tures often fail to convey the site’s original complexity and monumentality to visitors. In
this context, digitisation assumes a dual role: on the one hand, it serves as a structured
repository of information to support conservation and the planning of interventions; on the
other, it provides the geometric and semantic foundation for the development of immersive
environments and digital historical reconstructions capable of engaging visitors with the
site’s historical evolution.
More broadly, this integrated perspective may also be understood as a step towards
future Digital Twin-like developments, in which information models are progressively
connected with dynamic monitoring and updating systems.

1.1. Advanced Tools for Studying and Managing Heritage

The digitisation of archaeological sites now relies on the integration of reality-based
three-dimensional surveying techniques capable of producing geometrically reliable, met-
rically controlled models. Among these, Terrestrial Laser Scanning (TLS), close-range
photogrammetry for the analysis of wall stratigraphy and materials, and aerial UAV
photogrammetry for the overall documentation of the site represent some of the most
established tools in the current scientific landscape [14].
Recent studies provide significant examples of digital applications in archaeological
contexts. D’Aprile and Piscitelli applied image-based survey, orthophotomosaics, and
photo-based 3D modelling to support the knowledge, stratigraphic reading, conservation,
and enhancement of the archaeological park of Avella [15]. Ebolese et al. developed an
integrated 3D survey workflow combining TLS, close-range photogrammetry, and UAV
acquisition for the complete documentation and virtualisation of the archaeological envi-
ronment of the “Sybil hypogeum” in the Archaeological Park of Lilibeo [16]. Condorelli
and Bonetto, instead, showed how photogrammetry and virtual reality systems can sup-
port different archaeological goals, including stratigraphic analysis, virtual tours, and the
digital visualisation of artefacts in the cases of Gortyn, Nora, and the Museo Civico agli
Eremitani [17].
The integration of active and passive sensors allows for the intrinsic limitations of
each technology to be overcome [18]. Photogrammetry guarantees high radiometric quality
and detailed documentation of surface textures but can be problematic when dealing with
homogeneous surfaces or uncontrolled lighting conditions. TLS, on the other hand, ensures
high metric accuracy and is independent of lighting conditions, although it is less effective
for colour rendering. The convergence of datasets into a single georeferenced point cloud
allows for the construction of an integrated geometric base, overcoming the weaknesses of
individual systems and providing a unified reference for subsequent modelling phases [19].
In addition to these established techniques, solutions based on SLAM (Simultaneous
Localization and Mapping) systems are gaining increasing relevance, especially for the
rapid documentation of large or difficult-to-access areas [20]. However, although these
technologies offer important advantages in terms of acquisition speed and operational
flexibility, they may also be affected by cumulative drift errors during data capture, par-
ticularly over long trajectories or in geometrically repetitive environments. This aspect,
together with current limitations in texture quality and fine metric accuracy, may reduce
their suitability for analytical applications and for the detailed documentation of wall
stratigraphy in archaeological parks [21].
Following the survey phase, the digital workflow proceeds through the Scan-to-BIM
process, in which the point cloud is interpreted and translated into parametric objects within
an HBIM paradigm [22]. In archaeological contexts, this step is particularly critical, since the
objective is not the literal reproduction of every geometric irregularity, but the construction

https://doi.org/10.3390/heritage9050174

<!-- p. 4 -->

Heritage 2026, 9, 174 4 of 19

of a semantically coherent model capable of representing masonry units, construction
phases, stratigraphic relationships, and interpretative hypotheses as structured information
entities. One of the central issues in HBIM for heritage concerns the reliability of the
resulting model [23]. Excessive adherence to the point cloud may fragment the architectural
object into discontinuous, non-parametric elements, thereby compromising the consistency
and interoperability that are fundamental to the BIM process. In current practice, model
quality is often assessed primarily based on the deviation between the model and the point
cloud, with the implicit assumption that smaller deviations correspond to greater reliability.
This approach has been formalised through the concept of Level of Accuracy (LoA), which
classifies the model according to the acceptable tolerance with respect to measured reality.
However, reducing reliability to geometric accuracy alone overlooks the informational
and interpretative dimension of HBIM [24]. A model cannot be considered reliable merely
because it is metrically accurate; rather, reliability also depends on the explicit declaration
of sources, margins of error, modelling assumptions, and adopted approximations. While
BIM processes for new buildings are typically structured according to criteria such as Level
of Development (LOD) or Level of Information Need (LOIN) [25], HBIM in archaeological
contexts requires a parallel assessment of the reliability of the information embedded in
the model. For this reason, the concept of Level of Reliability (LoR) becomes particularly
relevant, as it makes explicit the origin, verifiability, and interpretative status of the data
associated with the digital representation [26,27].
In this context, the concept of Level of Reliability (LoR) is introduced as an index
of the trustworthiness of the information contained in the model, relative to the origin,
verifiability, and quality of the sources [24]. LoR is consistent with the principles of scientific
transparency established by the London Charter and the Seville Principles, according to
which each reconstruction choice should be traceable, justifiable, and replicable [28,29].
Operationally, HBIM should be constructed through a process of controlled abstraction.
Masonry, for example, should not be fragmented into micro-elements that merely adhere
to the point cloud, but rather modelled as coherent semantic units—such as Stratigraphic
Masonry Units or homogeneous masonry entities—to which metric deviations, material
characteristics, chronological information, and conservation data can be associated. In
this way, geometry becomes a support for semantics rather than an end in itself. From a
broader methodological perspective, digital tools applied to archaeological heritage should
not be limited to static information models but may progressively evolve towards Digital
Twin configurations [30,31]. In the field of structural and conservation monitoring, there
are already successful cases in which the digital model is continuously updated with data
from sensors and control systems, transforming it into a dynamic system that reflects the
building’s actual conditions over time [32]. The parameters that can be monitored may
vary depending on the application requirements and include, for example, humidity, dis-
placement, acceleration, temperature or other environmental and structural variables [32].
In such configurations, the HBIM/BIM model serves as both an information container and
a graphic scene for the Digital Twin: no longer a simple geometric representation, but a
visual and semantic interface through which to view updated data, identify anomalies,
and locate alerts directly on the architectural elements concerned. In this sense, the Digital
Twin should not be understood as synonymous with BIM/HBIM. While the latter provides
the structured geometric and semantic model, the Digital Twin introduces a dynamic
dimension based on the continuous or periodic updating of the model through sensor
data, monitoring systems, or other live information streams. The direction in which digital
applications in cultural heritage should converge is therefore that of progressive integra-
tion between information modelling and real-time monitoring systems, so that the model

https://doi.org/10.3390/heritage9050174

<!-- p. 5 -->

Heritage 2026, 9, 174 5 of 19

becomes an active tool for management, prevention, and scheduled maintenance, rather
than just as a digital archive of the current state.

1.2. A Case Study Along the via Appia: The City of Aeclanum

The ancient centre of Aeclanum is located at Passo di Mirabella, within the municipality
of Mirabella Eclano (province of Avellino, Campania, Italy). It occupies a plateau in a
strategic position between the Calore and Ufita valleys, covering an area of approximately
18 hectares. Its location along the Campanian section of the Via Appia—a major route
connecting Rome with southern Italy—underpinned its political, economic, and military
significance over several centuries, establishing it as a primary territorial hub within the
Sannio Irpino region (Figure 1). Little is known about the Samnite settlement, which must
have been structured as a synoecism during the 3rd century BC. It was later involved in the
Social War, during which it was plundered (89 BC) [33]. Most of the known evidence can
be traced back to the Roman city, which, after its reconstruction, was granted the status of
municipium (1st century BC) and was surrounded by a walled circuit in opus quasi reticulatum
extending for about 1800 m [34]. Subsequently (around 120 AD), it obtained the status of a
colony, with the name of Colonia Aelia Augusta Aeclanum, and this marked the beginning of
a complete urban redevelopment of the centre: during the 2nd and 3rd centuries AD, the
thermal complex was built in opus mixtum [35], the forum area, which included the macellum,
was subject to successive reorganisations, and a residential district with a domus a peristilio
was developed. In addition to these elements, necropolises were located at the entrance
and exit of the city along the Via Appia.

Figure 1. Passo di Mirabella. Aerial view of Aeclanum showing the principal archaeological remains:
A = baths; B = residential quarter; C = forum; D = Basilica. The remains and the city walls are marked
in red; the hypothetical urban course of the Via Appia is shown in black.

https://doi.org/10.3390/heritage9050174

<!-- p. 6 -->

Heritage 2026, 9, 174 6 of 19

A final phase of renovation took place in late antiquity with the establishment of a
bishopric and the construction of the Early Christian Basilica (late 4th–early 5th century
AD), built atop a previous roman residential structure, around which the late antique
urban centre was structured [36–38]. From the second half of the 6th century AD on-
wards, Aeclanum gradually disappeared from documentary sources, entering a phase of
decline. The current archaeological area, extending across the northern half of the plateau,
shows an overlap of construction phases, functional transformations and different building
techniques: this is the result of complex urban stratification, now visible in the emerging
structures but fragmented in the overall perception of the site [39,40]. It is precisely this
historical and morphological articulation that makes Aeclanum a significant case study
for the application of HBIM methodologies oriented towards the integration of survey
data, stratigraphic interpretation, semantic modelling of masonry, and the representation
of transformations over time. The site therefore provides an effective context for testing
an integrated digital workflow that combines reality-based documentation, information
modelling, and digital enhancement tools. In this sense, Aeclanum serves as a methodologi-
cal test bed for approaches applicable to other archaeological sites characterised by high
historical stratification and fragmented visibility of the built remains. Furthermore, the
settlement’s deep connection with the Via Appia, which forms the backbone of the urban
layout, and the latter’s inclusion on the UNESCO World Heritage List offer an opportunity
to explore new lines of research and protection for a similar urban and territorial context.

\2. Materials and Methods

2.1. Integrated 3D Survey Techniques

The three-dimensional surveying of the Ancient city of Aeclanum was set up as a pre-
liminary phase essential for understanding, documenting and analysing the site, forming
the basis for subsequent information modelling and studies of material characterisation and
degradation. Given the morphological and stratigraphic complexity of the context, we used
an integrated strategy that combined different reality-based technologies to converge on a
single data environment and generate a high-density georeferenced point cloud. The inte-
gration involved the use of Terrestrial Laser Scanning (TLS), Remote Piloted Aircraft System
(RPAS) photogrammetry, close-range photogrammetry for analysing wall stratigraphy and
material feature, and GNSS measurements for plano-altimetric control and georeferencing
of the entire system. The choice of a multi-scale methodology was determined by the need
to document both the territorial and volumetric layout of the city and the construction
details of the wall structures (Figure 2). The different techniques were designed to operate
in a complementary manner, ensuring complete coverage, metric redundancy and spatial
consistency between datasets. The methodological pipeline followed this sequence: survey
design, data acquisition, post-processing and registration of datasets, integration into a
common environment, and final delivery of two-dimensional and three-dimensional out-
puts. The alignment and merging operations enabled the creation of a three-dimensional
georeferenced model in the EPSG:32633 reference system, which is metrically controlled
and queryable.
The result is an integrated, measurable, and scalable three-dimensional dataset that
provides the geometric reference basis for the subsequent Scan-to-HBIM process and sup-
ports thematic analyses related to materials, wall stratigraphy, and conservation conditions.

https://doi.org/10.3390/heritage9050174

<!-- p. 7 -->

Heritage 2026, 9, 174 7 of 19

Figure 2. Operational flowchart applied to the case study of the archaeological site of Aeclanum: from
3D surveying to the information model and remote access via a virtual tour.

2.2. UAV Photogrammetric 3D Survey

The aerial photogrammetric acquisition of the city of Aeclanum was conducted using
a DJI Mavic 2 Pro (DJI Innovations Technology Co., Ltd., Shenzhen, China) remote pilot-
ing system, equipped with a Hasselblad RGB camera with a 1′′ sensor and 20-megapixel
resolution. The flight was planned using DJI Ground Station (version 1.4.63), setting up a
regular grid for nadir shots, which were then supplemented by manually acquired oblique
shots to ensure complete coverage of vertical surfaces and wall facings. This combina-
tion reduced shadow areas and improved the quality of three-dimensional reconstruction,
adapting to the site’s morphological conditions. The campaign involved the acquisition of
440 photogrammetric images, with an average Ground Sample Distance (GSD) of approxi-
mately 1.2 cm/px, covering a total area of approximately 14 hectares. The point cloud was
georeferenced in the EPSG:32633 (WGS 84/UTM 33N) reference system using 14 Ground
Control Points (GCPs) surveyed in nRTK (network real-time kinematics) mode with an
Emlid Reach RX receiver (Emlid, Saint Petersburg, Russia). The accuracy of the control
point measurements was maintained within 1.5 cm in both planimetry and altimetry, with
an overall error of less than 2.5 cm. For the UAV photogrammetric survey, aerial targets
measuring 60 cm per side were used as ground control markers for georeferencing and
alignment. Photogrammetric processing was carried out using Agisoft Metashape software
version 2.1.0, (St. Petersburg, Russia) setting the quality to ‘Maximum’ and disabling auto-
matic filters in order to preserve maximum information density. The GCPs were included
in the orientation process through a self-calibrating bundle adjustment, which allowed the
estimation of the camera’s internal orientation parameters; these parameters were then kept
constant throughout the entire Structure-from-Motion (SfM) process, ensuring consistency
and stability in image orientation. At the end of processing, a dense point cloud consisting
of over 110 million points was generated, from which a mesh with more than 40 million
faces and approximately 20 million vertices was derived, subsequently textured with an
8192-pixel map. A colour orthophoto with a minimum resolution of 2 cm and a Digital
Surface Model (DSM) with a resolution of 4 cm were also produced. The UAV survey
thus enabled the overall morphological documentation, providing the general planimetric

https://doi.org/10.3390/heritage9050174

<!-- p. 8 -->

Heritage 2026, 9, 174 8 of 19

framework and geometric basis for integration with the data acquired through TLS and
close-range photogrammetry.

2.3. The Terrestrial Laser Scanning (TLS) Survey

The three-dimensional survey of the archaeological site of Aeclanum was carried out
using a Faro Focus3D S Series laser scanner (FARO Technologies, Inc., Lake Mary, FL, USA),
a phase-difference instrument equipped with an integrated colour camera, GNSS system,
and a biaxial compensator for verticality control. The instrument has an operating range of
0.6–150 m, an acquisition speed of up to 2 million points per second, and a declared linear
error of ±2 mm, making it suitable for high-precision surveys in complex architectural
contexts. The choice of this technology was driven by the need to acquire a high-density
point cloud with millimetre accuracy, suitable for both the production of detailed graphic
drawings and subsequent information modelling in an HBIM environment. In a context
characterised by volumetric articulation, wall stratification and the presence of indoor and
outdoor environments, TLS ensured geometric continuity and metric robustness regardless
of lighting conditions. During the campaign, approximately 90 scans were performed, with
an average resolution of 6 mm at 10 m, strategically distributed to reduce shadow cones and
ensure adequate overlap between the different scanning stations. The scans were recorded
using a cloud-to-cloud procedure, without the use of spherical or flat targets, optimising
alignment with best-fit algorithms and subsequently verifying residual deviations. The
alignment procedure between scans resulted in an average RMS across all scans of 8 mm.
The resulting dataset was then integrated into the georeferenced reference system already
adopted for the UAV survey (EPSG: 32633), ensuring spatial consistency between the
different acquisition sources. The processing generated a comprehensive point cloud
of approximately 300 million points, including the interior and exterior environments
of the city walls, the Basilica, the domus, the macellum, and the thermal complex. This
dataset constitutes the highly accurate metric basis for the subsequent Scan-to-HBIM phase,
ensuring geometric continuity and dimensional reliability throughout the construction of
the HBIM information model (Figure 3).

Figure 3. Integration of aerial UAV photogrammetric point clouds and TLS data, both georeferenced
using the same GCP framework. The figure highlights the complementarity of the two datasets: the
UAV survey provides broad areal coverage, mainly from a zenithal perspective, while the TLS survey
is more concentrated on the masonry structures and produces a much denser dataset focused on the
architectural remains.

https://doi.org/10.3390/heritage9050174

<!-- p. 9 -->

Heritage 2026, 9, 174 9 of 19

2.4. Close-Range Photogrammetry for RGB Orthophotos of Wall Surfaces

Close-range photogrammetry was used to produce high-resolution metric orthophotos
of the wall surfaces, with particular focus on the characterisation of geomaterials and the
mapping of degradation forms. The survey involved 13 wall samples selected within
the archaeological area, considered representative of the different construction techniques
and conservation conditions documented on the site. The photographic acquisitions were
processed in Agisoft Metashape, including Ground Control Points, to estimate internal
orientation parameters using self-calibrating bundle adjustment. The estimated parameters
were kept constant throughout the Structure-from-Motion (SfM) process, ensuring metric
stability and consistent image orientation. The produced orthophotos are georeferenced
and at the correct metric scale, with a resolution of up to 2 mm/px, enabling detailed
analysis of individual blocks, mortars, and surface discontinuities. Unlike the UAV and
TLS datasets, the point cloud derived from close-range photogrammetry was not integrated
into the site’s overall three-dimensional cloud. This choice was motivated by the desire
to avoid potential alignment errors arising from the different acquisition scale, and, at
the same time, by the redundancy of information relative to the data already acquired at
the territorial and architectural scales. The TLS and UAV photogrammetric point clouds
were first integrated through georeferencing based on the same set of control points. The
alignment was then further refined by identifying a common surface between the two
datasets and applying an Iterative Closest Point (ICP) procedure, resulting in a final RMS
of 1.2 cm. Close-range photogrammetry was therefore used as a detailed analytical tool,
independent but consistent with the general reference system.
The results produced formed the basis for mapping lithotypes, identifying weathering
forms according to ICOMOS-ISCS guidelines, defining damage categories and calculating
linear and progressive degradation indices. The methodological integration of TLS survey-
ing, UAV aerial photogrammetry, and close-range photogrammetry enabled the operational
limitations of the individual techniques to be overcome, converging towards a metrically
controlled multi-scale documentation system with GNSS accuracy of approximately 1 cm
in planimetry and 2.5 cm in altimetry.
This geometric and analytical basis provides the reference for the subsequent Scan-to-
HBIM phase and for the attribution of information related to wall stratigraphy, material
characterisation, and conservation conditions, thus enabling the morphological, material,
and diagnostic dimensions of the site to be integrated into the digital model.

\3. Result

3.1. Scan-to-BIM Architectural Modelling in the Archaeological Site

The HBIM model was developed from the architectural and geometric documentation
obtained through the multi-scale three-dimensional survey described in the previous sec-
tions. The adopted Scan-to-BIM methodology is based on a structured process integrating
metric acquisition, historical-architectural analysis, and parametric modelling, with the aim
of constructing a three-dimensional representation that is not only geometrically accurate,
but also semantically organised and consistent with the stratified nature of the archaeologi-
cal site. The first phase involved the critical processing of the three-dimensional dataset,
including TLS point clouds, UAV photogrammetric models and close-range orthophotos.
The interpretation of the metric data was accompanied by a historical-architectural study
to understand the construction rules, masonry techniques, and settlement transformations
that characterised the site’s different phases. This step represented a central methodological
moment, as it made it possible to move beyond purely descriptive modelling, orienting
the process towards informed information construction. In this context, terrain modelling
played a decisive role as a structural element of the settlement and an essential component

https://doi.org/10.3390/heritage9050174

<!-- p. 10 -->

Heritage 2026, 9, 174 10 of 19

for the correct interpretation of the spatial relationships between the archaeological features.
The morphology of Aeclanum is characterised by significant altimetric variations distributed
throughout the site, which directly affect the volumetric perception of the structures, the
understanding of the original levels of frequentation, and the reconstruction of the area’s
evolutionary dynamics. The topographic surface was processed from point clouds gener-
ated by integrating terrestrial laser scanner surveys and UAV aerial photogrammetry. In the
first phase, the point cloud was cleaned in Autodesk Recap Pro (version 2024), isolating the
terrain data and removing irrelevant architectural and vegetation components. Although
this operation could also have been performed in Agisoft Metashape, the automatic filtering
of anthropogenic structures for contour line extraction was not considered effective enough
for this case study, preferring manual cleaning tools. For this reason, Autodesk Recap Pro
was preferred for the preliminary cleaning of the dataset, after which the filtered cloud was
imported into Autodesk Revit (version 2024) to directly generate the topographic surface
from the three-dimensional data within the same environment adopted for the subsequent
HBIM workflow. To ensure a balance between metric accuracy and the model’s manage-
ability, an alternative strategy was adopted; the point cloud was suitably simplified and
processed in Autodesk Civil 3D, enabling the extraction of contour lines from the collected
altimetric data. This step made it possible to synthesise the morphological information
while maintaining accuracy but significantly reducing the overall file size. The curves
thus obtained were then used to generate the final georeferenced topographic surface
in Autodesk Revit, ensuring a faithful representation of the terrain and more efficient
management of the BIM model (Figure 4).

Figure 4. Representation of the terrain using contour lines generated by filtering anthropogenic
elements from the point cloud and nadir orthoimages of the basilica area (south) and the thermal
area (north).

The emerging structures were then modelled. The walls were reconstructed through an
integrated interpretation of the point cloud and stratigraphic reading, adopting a criterion
of semantic simplification. Instead of fragmenting the wall surfaces into microelements
that adhere precisely to the data collected, they were modelled as homogeneous entities
consistent with the identified Stratigraphic Wall Units.
In this sense, the reliability of the model does not refer only to geometric correspon-
dence with the survey data, but also to the semantic coherence of the represented structures,
especially in the distinction between physically preserved masonry remains and interpreta-
tive reconstruction hypotheses.

https://doi.org/10.3390/heritage9050174

<!-- p. 11 -->

Heritage 2026, 9, 174 11 of 19

This approach allows a balance to be maintained between geometric accuracy and
informational consistency, avoiding the proliferation of non-parametric objects that would
compromise the management and future updateability of the model [41] (Figure 5).

Figure 5. Examples of wall modelling from point clouds with projection of orthoimages produced
in photogrammetry.

The HBIM methodology also involved creating a library of parametric objects, based
on the architectural rules identified during the analytical phase. For elements not present in
the software’s standard libraries, customised components were developed, calibrated to the
proportions and geometric characteristics documented by the survey and historical research.
This process was particularly relevant in modelling recurring architectural elements, for
which a comparative approach was adopted to reconstruct the original spatial configuration,
keeping the surveyed component distinct from the interpretative one [41]. The HBIM
model was designed as an open, progressively implementable system, ready for continuous
enrichment with geometric and information data relating to both the entire complex and
individual architectural and structural components. The final phase of the process involved
the automated extraction of graphic designs and informational documents—plans, sections,
elevations and tables—for the scientific documentation of the site and to support analysis,
conservation and management activities.

3.2. Informative Attribution and Semantic Structuring in the HBIM Model

The information attribution phase represents the moment when the three-dimensional
model fully assumes the nature of an HBIM system. As highlighted in the literature,
the modelling of historical heritage cannot be limited to the purposes of restoration in-
terventions only, but must be based on an ontological structure capable of organising,
hierarchising and making the information associated with individual construction ele-
ments queryable. In the case study, the masonry entities modelled in Autodesk Revit
were enriched by associating shared and customised parameters, structured according to a
hierarchy consistent with the site’s stratigraphic reading. Each element was assigned data
on its chronological phase, construction technique, wall type, constituent materials, and
state of preservation. This organization makes it possible to distinguish explicitly between
information derived from metric surveys, documentary data from historical sources and
reconstructive interpretations, avoiding overlaps between different levels of knowledge.
By combining the geometric survey of the structures with high-resolution texture
acquisition and the mapping of materials and decay patterns, the model also provides

https://doi.org/10.3390/heritage9050174

<!-- p. 12 -->

Heritage 2026, 9, 174 12 of 19

a basis for a conservation-oriented management phase, supporting the comparison of
different wall conditions and the programming of future interventions according to the
documented state of preservation. A central aspect of the process concerns information
transparency. In line with the methodological approach referred to in the literature, each
modelled element has been conceived as a container of metadata that explains the origin of
the information, the level of geometric accuracy, and the degree of interpretative reliability.
In this way, the model operationally integrates the concept of Level of Reliability (LoR),
making modelling choices traceable and distinguishing between certain data, deduction by
analogy, and reconstructive hypotheses [42].
The semantic dimension thus becomes a structural element of the model, not merely
an accessory attribute. At the same time, high-resolution metric orthophotos were used
to project textures onto the modelled masonry surfaces, ensuring consistency between the
photorealistic representation and the metric data. The visual component was not treated as
a mere graphic coating, but as a tool to support stratigraphic and material reading. The
information derived from the analysis of lithotypes and degradation forms was integrated
into the objects’ information parameters, establishing a direct relationship among photo-
graphic evidence, metric data, and the model’s semantic structure [43]. The integration of
results obtained using the evaluation method proposed by Fitzner & Heinrichs enabled
quantitative damage indices to be associated with individual masonry entities [44], thereby
allowing comparison between different portions of the site and supporting the identifica-
tion of priority areas for future intervention [45,46]. The thematic maps were first vectorised
from raster images derived from the orthophotos and then imported into the HBIM model,
where they were associated with the corresponding masonry entities both as documenta-
tion outputs and as numerical indices linked to each wall unit. In this way, the attribution
of linear and progressive damage indices transformed the model into an operational tool
for conservation-oriented analysis, capable of supporting technical-scientific assessments
and informed evaluation processes.
In this configuration, HBIM is not limited to serving as a digital archive of acquired
information; it is configured as a dynamic knowledge platform, in which the geometric,
material, and diagnostic dimensions converge into a coherent information system that
can be verified and updated over time. The model thus becomes a decision-making
infrastructure supporting the planned conservation and evolutionary management of
archaeological heritage (Figure 6).

Figure 6. Information attributed to the HBIM model for the maintenance phase: wall stratigraphy,
material maps, damage and alteration maps on the wall.

https://doi.org/10.3390/heritage9050174

<!-- p. 13 -->

Heritage 2026, 9, 174 13 of 19

3.3. HBIM-Based Reconstruction Hypothesis of the Basilica

The integration of metric documentation, stratigraphic analysis, and historical-
architectural data has enabled the construction of an HBIM model of the Basilica that
not only represents its current state but also formulates reconstruction hypotheses consis-
tent with the available evidence. The modelling of the Basilica was developed starting from
the emerging masonry structures surveyed using TLS and close-range photogrammetry,
on which an integrated analysis of construction techniques and stratigraphic relationships
was conducted. Information relating to the construction phases, constituent materials,
and degradation indices was associated with the masonry entities as parametric attributes,
enabling an explicit distinction among preserved configuration, material gaps, and portions
subject to interpretative reconstruction. In the HBIM model, the preserved structures were
represented directly from the three-dimensional survey, while the parts that no longer
exist were reconstructed using a comparative approach based on typological analogies
with contemporary Basilicas, planimetric analysis, and documented stratigraphic relation-
ships. The volumetric hypothesis of the naves, the roofing system, and the portico in front
was developed as a separate level of information from the surveyed walls, clarifying the
distinction between the data and interpretative proposals (Figure 7).

Figure 7. (a–c) Plan and axonometric view of the virtual reconstruction of the Basilica; (d) integration
of the volumetric model on the 3D surveys and the existing archaeological evidence; (e) reconstruction
hypothesis of the Basilica’s roof.

Particular attention was paid to the consistency between the building’s spatial config-
uration and liturgical organisation. The presence of the cruciform baptismal font and the
tripartite articulation of the interior space guided the reconstruction of the elevations and
the definition of the volumetric proportions. The model, therefore, does not reproduce an
arbitrary form, but integrates material evidence, functional interpretation and typological
comparison in a structured interpretative process. From a technical point of view, the
hypothesised parts were modelled in Autodesk Revit as parametric families independent
of the components surveyed. They are not derived from a direct replica of the point cloud,
but from a controlled geometric reconstruction based on proportions deduced from the
planimetric layout, typological comparisons, and analysis of residual heights.
The roofs, elevations and portico system were developed as independent objects,
associated with specific parameters that explicitly declare their interpretative nature and
level of reliability. To make the distinction between the actual state and the hypotheti-

https://doi.org/10.3390/heritage9050174

<!-- p. 14 -->

Heritage 2026, 9, 174 14 of 19

cal reconstruction immediately perceptible, a differentiated representation strategy was
adopted. The parts documented by the survey are visualised with photorealistic textures
derived from orthophotos, while the reconstructed elements are represented in wireframe
mode or with semi-transparent neutral materials (Figure 8). This criterion was applied not
only to the HBIM model itself, but also to the visual reintegration of the Basilica, in order
to preserve the recognisability of the reconstructed parts and avoid ambiguity between
surveyed data and interpretative reconstruction. This choice is not purely graphic but
methodological and is consistent with other archaeological reconstruction approaches
based on visually distinguishable restitutions, such as the cases of the Temple of Apollo of
Veii and the Basilica of Siponto in Manfredonia.

Figure 8. Rendering of the wireframe volumetric reconstruction of the Basilica.

This approach echoes the principle of recognisability inherent in restoration theory,
according to which any additions must be distinguishable from the original without com-
promising its legibility. Similarly, in the digital model, the reconstruction is made visually
distinct, avoiding ambiguity between real data and interpretation. The HBIM model not
only makes explicit the different levels of information reliability but also translates these
levels into a visual language that is understandable even to a non-specialist audience.
Reconstruction thus becomes a critical and educational tool, capable of conveying the
complexity of the interpretative process underlying archaeological knowledge.

3.4. Virtual Tour and Immersive Reconstruction Hypotheses

In parallel with the three-dimensional surveying operations using Terrestrial Laser
Scanning, an immersive photographic acquisition campaign was conducted using an
Insta360 X3 (Shenzhen, China) camera (COMS sensor 1/2′′ 72 MP—11,968 × 5984 pixels),
with the aim of creating an interactive Virtual Tour of the archaeological area. The objective
was not exclusively documentary but rather to create a digital tool integrated with the
HBIM model and the reconstruction hypotheses developed for the Basilica.
The 360◦spherical images were processed using 3D Vista Pro software version 2023.3.2
(Granada, Spain.)which enabled the creation of a navigable virtual environment structured
through information hotspots, connection points, and the integration of multimedia content.
The Virtual Tour was designed to be accessible both remotely and in situ, via a QR code
installed within the archaeological area. This solution allows two modes of use: on the
one hand, remote access for users not physically present on the site; on the other hand, the

https://doi.org/10.3390/heritage9050174

<!-- p. 15 -->

Heritage 2026, 9, 174 15 of 19

integration of the real experience with digital content that can be consulted directly during
the visit (Figure 8) [47,48]. The same digital reconstruction images may also support the
preparation of on-site interpretative panels, combining QR codes and visual restitutions to
help visitors better understand the original spatial configuration of the Basilica (Figure 9).

Figure 9. Virtual tour that includes the current situation through 360◦images of the area and tags
with renderings and video reconstructions of the Basilica.

The HBIM model has been integrated into the Virtual Tour by including rendered
views and video sequences of the reconstruction of the Basilica. This content allows the cur-
rent configuration of the structures to be perceptually related to the hypothetical volumetric
layout of the late antique building, facilitating understanding of the original spatiality and
monumentality of the work, which today can only be perceived through fragmentary wall
remains. The immersive environment thus becomes a communicative extension of the
information model, translating stratigraphic data and volumetric hypotheses into a spatial
experience that is understandable even to a non-specialist audience [49].
Even in the virtual context, the methodological distinction between real data and
reconstructive hypotheses has been maintained. The documented parts are shown through

https://doi.org/10.3390/heritage9050174

<!-- p. 16 -->

Heritage 2026, 9, 174 16 of 19

high-resolution photographic images and textures derived from the survey, while the
hypothesised components are represented in wireframe mode or with semi-transparent
neutral materials. This choice, consistent with the principle of recognisability inherent in
restoration theory, ensures a clear visual separation between what has been preserved and
what has been digitally reconstructed, avoiding interpretative ambiguity and preserving
the scientific transparency of the process.

\4. Discussion and Conclusions

The Aeclanum case study demonstrates how the integration of multi-scale three-
dimensional surveys, Scan-to-HBIM, and immersive tools can be structured into an inte-
grated digital workflow for archaeologically stratified contexts. The approach adopted
transcends the traditional separation between metric documentation, archaeological in-
terpretation, and digital enhancement, proposing a unified process in which geometric
data, semantic organization, and diagnostic information are closely interconnected. From
a conservation perspective, the integration of degradation indices and material analysis
into the HBIM model extends the role of digital representation beyond mere geometric
documentation and provides an informed basis for identifying priority areas and planning
future interventions, a particularly important aspect in contexts characterized by large
archaeological surfaces and limited resources.
One of the study’s key methodological contributions lies in the explicit distinction
between observed data and reconstructive hypotheses, implemented both at the informa-
tional and visual levels. The adoption of distinct parametric families for the hypothesized
parts, along with their wireframe representation, translates the principle of recognizability
inherent in restoration theory into the digital model, avoiding overlaps between material
evidence and interpretation. In this way, the model becomes not only descriptive but also
critically transparent.
In the broader perspective of historical documentation, HBIM does not merely record
the present condition of the ruins but also provides a graphic and documentary basis
for the development of reconstruction hypotheses anchored to surveyed geometry and
archaeological interpretation. Within this broader workflow, the reconstruction of the
Basilica represents a pilot application of the interpretive potential of the HBIM model. At
the same time, the model’s integration into a virtual tour accessible via QR code enhances
its communicative value.
Within this broader workflow, the reconstruction of the Basilica represents a pilot
application of the interpretive potential of the HBIM model. At the same time, the model’s
integration into a virtual tour accessible via QR code enhances its communicative value.
The immersive representation allows the current state of the remains to be correlated with
their hypothesized volumetric configuration, helping visitors understand the site’s original
monumentality and its historical transformations, while maintaining methodological rigor.
The Aeclanum experience highlights that HBIM and immersive environments should
not be understood as separate fields, but as complementary components of a broader
digital ecosystem oriented towards documentation, conservation, and heritage valorisation.
Looking ahead, periodic model updates through new survey campaigns and the potential
integration of dynamic monitoring systems could further extend this approach toward
Digital Twin-like configurations, strengthening the model’s role as a constantly evolving,
non-static knowledge infrastructure.
The proposed workflow can therefore be considered a methodological framework
applicable to archaeological sites characterized by high historical stratification, morpholog-
ical complexity, and fragmented visibility of built remains. In this sense, the study offers

https://doi.org/10.3390/heritage9050174

<!-- p. 17 -->

Heritage 2026, 9, 174 17 of 19

a coherent approach in which surveying, interpretation, semantic modeling, and digital
communication converge within a single verifiable system.

Author Contributions: Conceptualization, M.L., L.R. and L.D.G.; data curation, M.L.; formal analysis,
M.L., investigation, M.L., L.R. and L.D.G.; methodology, M.L.; software, M.L.; validation, M.L., L.R.
and L.D.G.; writing—review and editing, M.L., L.R. and L.D.G. All authors have read and agreed to
the published version of the manuscript.

Funding: This research received no external funding.

Data Availability Statement: The original contributions presented in this study are included in the
article. Further inquiries can be directed to the corresponding author.

Acknowledgments: We would like to express our sincere gratitude to the Direzione Regionale Musei
Nazionali Campania, Alfonso Santoriello (Scientific Coordinator of the Appia Project at the University
of Salerno), Angela Ferroni (Coordinator of the Technical-Scientific Committee for the nomination of
the Via Appia Regina Viarum to the UNESCO World Heritage List), Gabriel Ezequiel Petrelli Heras,
and the Mineralogy and Petrography Laboratory of the University of Sannio for their availability and
for sharing the materials produced during the on-site analyses. We would also like to thank Sandra
Lo Pilato for her valuable support in the interpretation and virtual reconstruction of the Basilica,
based on her studies.

Conflicts of Interest: The authors declare no conflict of interest.

References

\1. Alshawabkeh, Y.; Baik, A.; Miky, Y. HBIM for Conservation of Built Heritage. ISPRS Int. J. Geoinf. 2024, 13, 231. [CrossRef]
\2. Banfi, F. The Evolution of Interactivity, Immersion and Interoperability in HBIM: Digital Model Uses, VR and AR for Built
Cultural Heritage. ISPRS Int. J. Geoinf. 2021, 10, 685. [CrossRef]
\3. Nieto-Julián, E.; Bruno, S.; Moyano, J. An Efficient Process for the Management of the Deterioration and Conservation of
Architectural Heritage: The HBIM Project of the Duomo of Molfetta (Italy). Remote Sens. 2024, 16, 4542. [CrossRef]
\4. ISTAT. I Musei, Le Aree Archeologiche e i Monumenti in Italia. Anno 2017; ISTAT: Rome, Italy, 2019.
\5. Aricò, M.; Lo Brutto, M.; Maltese, A. A Scan-to-BIM Approach for the Management of Two Arab-Norman Churches in Palermo
(Italy). Heritage 2023, 6, 1622–1644. [CrossRef]
\6. Aricò, M.; Ferro, C.; La Guardia, M.; Lo Brutto, M.; Taranto, G.; Ventimiglia, G.M. Scan-to-BIM Process and Architectural
Conservation: Towards an Effective Tool for the Thematic Mapping of Decay and Alteration Phenomena. Heritage 2024, 7,
6257–6281. [CrossRef]
\7. Banfi, F. HBIM, 3D Drawing and Virtual Reality for Archaeological Sites and Ancient Ruins. Virtual Archaeol. Rev. 2020, 11, 16–33.
[CrossRef]
\8. Brusaporci, S.; Maiezza, P.; Marra, A.; Tata, A.; Vespasiano, L. Scan-to-HBIM Reliability. Drones 2023, 7, 426. [CrossRef]
\9. Stanga, C.; Banfi, F.; Roascio, S. Enhancing Building Archaeology: Drawing, UAV Photogrammetry and Scan-to-BIM-to-VR
Process of Ancient Roman Ruins. Drones 2023, 7, 521. [CrossRef]
\10. Scianna, A.; Serlorenzi, M.; Gristina, S.; Filippi, M.; Paliaga, S. Sperimentazione di tecniche BIM sull’archeologia romana: Il caso
delle strutture rinvenute all’interno della cripta della chiesa dei SS. Sergio e Bacco in Roma. Archeol. E Calc. Suppl. 2015, 7,
199–212.
\11. Garagnani, S.; Gaucci, A.; Govi, E. ArchaeoBIM: Dallo scavo al Building Information Modeling di una struttura sepolta. Il caso
del tempio tuscanico di Uni a Marzabotto. Archeol. E Calc. 2016, 27, 251–270. [CrossRef]
\12. Bolognesi, C.M.; Fiorillo, F. Virtual Representations of Cultural Heritage: Sharable and Implementable Case Study to Be Enjoyed
and Maintained by the Community. Buildings 2023, 13, 410. [CrossRef]
\13. Bellazzi, A.; Bellia, L.; Chinazzo, G.; Corbisiero, F.; D’Agostino, P.; Devitofrancesco, A.; Fragliasso, F.; Ghellere, M.; Megale, V.;
Salamone, F. Virtual Reality for Assessing Visual Quality and Lighting Perception: A Systematic Review. Build. Environ. 2022,
209, 108674. [CrossRef]
\14. Limongiello, M.; Musmeci, D.; Radaelli, L.; Chiumiento, A.; di Filippo, A.; Limongiello, I. Parametric GIS and HBIM for
Archaeological Site Management and Historic Reconstruction Through 3D Survey Integration. Remote Sens. 2025, 17, 984.
[CrossRef]

https://doi.org/10.3390/heritage9050174

<!-- p. 18 -->

Heritage 2026, 9, 174 18 of 19

\15. D’Aprile, M.; Piscitelli, M. Survey, stratigraphy of the elevations, 3D modelling for the knowledge and conservation of archae-
ological parks: The castle of Avella. In The International Archives of the Photogrammetry, Remote Sensing and Spatial Information
Sciences, 8th International Workshop 3D-ARCH “3D Virtual Reconstruction and Visualization of Complex Architectures”, Bergamo, Italy,
6–8 February 2019; ISPRS: Hannover, Germany, 2019; Volume XLII-2/W9, pp. 289–296. [CrossRef]
\16. Ebolese, D.; Lo Brutto, M.; Dardanelli, G. The integrated 3D survey for underground archaeological environment. In The
International Archives of the Photogrammetry, Remote Sensing and Spatial Information Sciences, 8th International Workshop 3D-ARCH
“3D Virtual Reconstruction and Visualization of Complex Architectures”, Bergamo, Italy, 6–8 February 2019; ISPRS: Hannover, Germany,
2019; Volume XLII-2/W9, pp. 311–317. [CrossRef]
\17. Condorelli, F.; Bonetto, J. 3D digitalization and visualization of archaeological artifacts with the use of photogrammetry and
virtual reality system. In The International Archives of the Photogrammetry, Remote Sensing and Spatial Information Science, 7th
International Workshop LowCost 3D–Sensors, Algorithms, Applications, Würzburg, Germany, 15–16 December 2022; ISPRS: Hannover,
Germany, 2022; Volume XLVIII-2/W1-2022, pp. 51–57. [CrossRef]
\18. Abate, N.; Ronchi, D.; Vitale, V.; Masini, N.; Angelini, A.; Giuri, F.; Minervino Amodio, A.; Gennaro, A.M.; Ferdani, D. Integrated
Close Range Remote Sensing Techniques for Detecting, Documenting, and Interpreting Lost Medieval Settlements under Canopy:
The Case of Altanum (RC, Italy). Land 2023, 12, 310. [CrossRef]
\19. Iliodromitis, A.; Tsilimantou, E.; Kopelou, P.; Anastasiou, D.; Koulidou, S.; Spanodimos, C.; Chrysostomou, G.; Dimou, V.; Pagou-
nis, V. Three-Dimensional Digital Geospatial Documentation for Cultural Heritage Preservation and Sustainable Management of
Tourism Through a Web Platform: The Case Study of the Archaeological Park of Dion, Greece. Land 2025, 14, 1062. [CrossRef]
\20. Maset, E.; Valente, R.; Haider, M.; Iamoni, M. Digital Documentation of the Ain Akrine Archaeological Site (Lebanon): A Hybrid
UAV Photogrammetry and SLAM-Based Survey Approach. In The International Archives of the Photogrammetry, Remote Sensing and
Spatial Information Sciences, 11th Intl. Workshop 3D-ARCH “3D Virtual Reconstruction and Visualization of Complex Architectures”,
Ancona, Italy, 10–12 February 2026; ISPRS: Hannover, Germany, 2026; Volume XLVIII-2/W12-2026, pp. 287–294. [CrossRef]
\21. Aricò, M.; Cherif, S.; La Guardia, M.; Lo Brutto, M. Innovative Approaches Through 3D Survey and Virtual Technologies for the Geometric
and Semantic Fruition of Built Heritage Sites on the Web; The Eurographics Association: Geneva, Switzerland, 2025. [CrossRef]
\22. D’Auria, S.; D’Agostino, P. scan-to-bim and segmentation processes for the conservation of cultural heritage. A workflow
proposal. Disegnarecon 2024, 17, 131–139. [CrossRef]
\23. Bianchini, C.; Nicastro, S. From BIM to H-BIM. In Proceedings of the 2018 3rd Digital Heritage International Congress (Digital-
HERITAGE) Held Jointly with 2018 24th International Conference on Virtual Systems & Multimedia (VSMM 2018), San Francisco,
CA, USA, 26–30 October 2018; pp. 1–4.
\24. Bianchini, C.; Attenni, M.; Potestà, G. Regenerative Design Tools for the Existing City: HBIM Potentials. In Rethinking Sustainability
Towards a Regenerative Economy; Andreucci, M.B., Marvuglia, A., Baltov, M., Hansen, P., Eds.; Springer International Publishing:
Cham, Switzerland, 2021; pp. 23–43, ISBN 978-3-030-71819-0.
\25. Pham, T.-A.; Ioannou, P.G.; Likhitruangsilp, V. Designing a BIM-Enhanced Digital Twin Architecture for Construction Pollution
Management in Building Renovation Projects. Int. J. Constr. Manag. 2026, 1–26. [CrossRef]
\26. Empler, T.; Caldarone, A.; Rossi, M.L. “BIM Survey”. Critical Reflections on the Built Heritage’s Survey. In Proceedings of the From
Building Information Modelling to Mixed Reality; Bolognesi, C., Villa, D., Eds.; Springer International Publishing: Cham, Switzerland,
2021; pp. 109–122.
\27. Mazzei, A.; Martinelli, L.; Empler, T.; Cessari, L.; Gigliarelli, E. Modelling for Uncertainty in HBIM Processes. Vitruvio 2024, 9,
2–18. [CrossRef]
\28. López-Menchero, V.M.; Grande, A. The Principles of the Seville Charter. In Proceedings of the CIPA Symposium Proceedings; CIPA
Heritage Documentation/CIPA–ICOMOS: Prague, Czech Republic, 2011; pp. 1–6.
\29. The London Charter for the Computer-Based Visualisation of Cultural Heritage. In Paradata and Transparency in Virtual Heritage;
Routledge: Abingdon, UK, 2009.
\30. Colace, F.; Limongiello, M.; Lorusso, A.; Pellegrino, M.; Santaniello, D.; Santoriello, A. Digital Twin for Cultural Heritage:
A Computational Approach to Predictive Conservation. Digit. Appl. Archaeol. Cult. Herit. 2026, 40, e00519. [CrossRef]
\31. Niccolucci, F.; Felicetti, A.; Hermon, S. Populating the Data Space for Cultural Heritage with Heritage Digital Twins. Data 2022,
7, 105. [CrossRef]
\32. Petti, L.; Lupo, C.; D’Angelo, T. Dynamic Monitoring of the Temple of Neptune in Paestum (Italy)-Preliminary Results. J. Phys.
Conf. Ser. 2024, 2647, 222005. [CrossRef]
\33. Di Giovanni, V. Aeclanum romana: Le evidenze archeologiche. In Storia illustrata di Avellino e dell’Irpinia. L’Irpinia Antica; Sellino
& Barra: Pratola Serra, Italy, 1996; pp. 241–255.
\34. De Simone, G.F.; Russell, B. Excavation and Survey at Aeclanum in 2018 (Comune Di Mirabella Eclano, Provincia Di Avellino,
Regione Campania). Pap. Br. Sch. Rome 2019, 87, 336–340. [CrossRef]
\35. Grenzi Editore, C. Aerea Studi Di Aerotopografia Archeologica. In Archeologia Aerea; Claudio Grenzi Editore: Foggia, Italy, 2013;
ISBN 9788884315502.

https://doi.org/10.3390/heritage9050174

<!-- p. 19 -->

Heritage 2026, 9, 174 19 of 19

\36. Lo Pilato, S. Il territorio di Aeclanum in età tardoantica ed altomedievale. In Mons. Nicola Gambino (1921–2000). Sacerdote e storico
dell’Irpinia Antica nel Ricordo di Amici ed Estimatori, Rocca San Felice, Italy, 10 December 2011; Atti del Convegno di Studi; Passaro, G.,
Ed.; Delta 3 Edizioni: Grottaminarda, Italy, 2013; pp. 59–96.
\37. Lo Pilato, S. La Via Appia tra Ponte Rotto e Aeclanum. Archeol. Aerea 2013, 7, 44–52.
\38. Lo Pilato, S. Il primo Tratto Irpino della Via Appia. In Via Appia Regina Viarum. Ricerche, Contesti, Valorizzazione; Marchi, M.L., Ed.;
Polieion: Athens, Greece, 2019; pp. 153–185.
\39. Colucci Pescatori, G. Evidenze Archeologiche in Irpinia. In La Romanisation du Samnium aux IIe et Ier Siècles Av. J.-C.; Actes du
Colloque International: Naples, Italy, 1988; pp. 85–122.
\40. Musmeci, D. Sui Sistemi Difensivi in Irpinia (IV–I Sec. a.C.). Un Quadro di Sintesi Tra Dati Archeologici e “Architettura
Rappresentata”. Otium. Archeol. Cult. Mondo Antico 2024, 15, 1–84.
\41. Park, J.J.; Kim, K.; Ji, S.Y.; Jun, H.J. Framework for BIM-Based Repair History Management for Architectural Heritage. Appl. Sci.
2024, 14, 2315. [CrossRef]
\42. Demetrescu, E.; Ferdani, D. From Field Archaeology to Virtual Reconstruction: A Five Steps Method Using the Extended Matrix.
Appl. Sci. 2021, 11, 5206. [CrossRef]
\43. Grifa, C.; Barba, S.; Fiorillo, F.; Germinario, C.; Izzo, F.; Mercurio, M.; Musmeci, D.; Potrandolfo, A.; Santoriello, A.; Toro, P.; et al.
The Domus of Octavius Quartio in Pompeii: Damage Diagnosis of the Masonries and Frescoed Surfaces. Int. J. Conserv. Sci. 2016,
7, 885–900.
\44. Trizio, I.; Savini, F. Archaeology of Buildings and HBIM Methodology: Integrated Tools for Documentation and Knowledge
Management of Architectural Heritage. In Proceedings of the TC4 MetroArchaeo 2020 IMEKO TC4 International Conference on
Metrology for Archaeology and Cultural Heritage, Trento, Italy, 22–24 October 2020.
\45. Germinario, C.; Gorrasi, M.; Izzo, F.; Langella, A.; Limongiello, M.; Mercurio, M.; Musmeci, D.; Santoriello, A.; Grifa, C. Damage
diagnosis of Ponte Rotto, a roman bridge along the ancient Appia. Int. J. Conserv. Sci. 2020, 11, 277–290.
\46. Izzo, F.; Furno, A.; Cilenti, F.; Germinario, C.; Gorrasi, M.; Mercurio, M.; Langella, A.; Grifa, C. The Domus Domini Imperatoris
Apicii Built by Frederick II along the Ancient Via Appia (Southern Italy): An Example of Damage Diagnosis for a Medieval
Monument in Rural Environment. Constr. Build. Mater. 2020, 259, 119718. [CrossRef]
\47. Trizio, I.; Savini, F.; Marra, A.; Ruggieri, A. The Virtual Tour as a Digital Tool for Linking the Disciplines of the Drawing and the
Archaeology of Buildings. Disegno 2021, 2021, 157–168. [CrossRef]
\48. Tommasi, C.; Fiorillo, F.; Jiménez Fernández-Palacios, B.; Achille, C. Access and web-sharing of 3d digital documentation of
environmental and architectural heritage. In The International Archives of the Photogrammetry, Remote Sensing and Spatial Information
Sciences, 8th Intl. Workshop 3D-ARCH “3D Virtual Reconstruction and Visualization of Complex Architectures”, Bergamo, Italy, 6–8
February 2019; ISPRS: Hannover, Germany, 2019; Volume XLII-2/W9, pp. 707–714. [CrossRef]
\49. Roggio, D.S.; Shokrollahi, S.; Forte, A.; Bitelli, G. Exploring Historical Changes to Architectural Heritage Through Reality-Based
3D Modeling and Virtual Reality: A Case Study. ISPRS Int. J. Geoinf. 2025, 14, 353. [CrossRef]

Disclaimer/Publisher’s Note: The statements, opinions and data contained in all publications are solely those of the individual
author(s) and contributor(s) and not of MDPI and/or the editor(s). MDPI and/or the editor(s) disclaim responsibility for any injury to
people or property resulting from any ideas, methods, instructions or products referred to in the content.

https://doi.org/10.3390/heritage9050174
