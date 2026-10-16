---
type: libro
title: "Combining HBIM and AR for Heritage Conservation."
author: ""
categoria: "Tecnología láser, fotogrametría, otros"
paginas: 8
extraccion: "texto"
fuente: "local:E:/DISCIPLINAS, TEXTOS Y MAPAS/Biblioteca digital/Tecnología láser, fotogrametría, otros/Combining HBIM and AR for Heritage Conservation..pdf"
convertido: 2026-10-13
---

# Combining HBIM and AR for Heritage Conservation.

> Texto extraído de `Tecnología láser, fotogrametría, otros/Combining HBIM and AR for Heritage Conservation..pdf` (8 páginas, texto). El PDF original está en el disco E: (DISCIPLINAS, TEXTOS Y MAPAS\Biblioteca digital); `<!-- p. N -->` marca el inicio de cada página.

<!-- p. 1 -->

The International Archives of the Photogrammetry, Remote Sensing and Spatial Information Sciences, Volume XLVIII-2/W12-2026
11th Intl. Workshop 3D-ARCH "3D Virtual Reconstruction and Visualization of Complex Architectures", 10–12 February 2026, Ancona, Italy

Combining HBIM and AR for Heritage Conservation.
From Digital Survey to an Interactive Management Tool

Paolo Clini 1, Chiara Mariotti 1, Renato Angeloni 1, Umberto Ferretti 2

1 Department of Construction, Civil Engineering and Architecture, Università Politecnica delle Marche, Ancona, Italy – (p.clini,
chiara.mariotti, r.angeloni)@staff.univpm.it
2 Department of Science of Antiquities, Sapienza University of Rome, Rome, Italy – umberto.ferretti@uniroma1.it

Keywords: Architectural Heritage, Digital Replica, HBIM, Extended Reality, Preventive and Planned Conservation.

Abstract

This paper presents a Scan-to-HBIM-to-XR workflow aimed at supporting preventive and planned conservation of complex
architectural heritage. The proposed methodology integrates multi-source 3D surveying, semantic information modelling, and
Augmented Reality (AR) technologies into a unified operational framework. Terrestrial Laser Scanning (TLS) and UAV-based
photogrammetry are combined to generate an accurate and georeferenced digital replica, which forms the basis for the development of
a semantically enriched HBIM model. The model is structured to integrate geometric, historical, construction, and diagnostic data,
including quantitative indicators for assessing masonry quality and conservation status.
To enhance accessibility and usability, the HBIM dataset is connected to a lightweight AR application that enables on-site consultation
and updating of alphanumeric BIM data. Through spatial alignment with the real architecture, users can document degradation
phenomena, create AR-based segmentations and georeferenced annotations, and transmit updates to a cloud system, where they are
automatically integrated into the HBIM model, ensuring a continuous feedback loop between field activities and the central model.
Tested on the historic city walls of Fano (Italy), the workflow demonstrates how HBIM and AR can be combined to transform digital
models into dynamic decision-support tools, bridging the gap between documentation, monitoring, and long-term heritage
management.

\1. Introduction characterization, while parametric models support data
integration and advanced management workflows.
In recent years, the integration of accurate 3D surveying Within this evolving panorama, Heritage Building Information
techniques, information modelling, and eXtended Reality (XR) Modelling (HBIM) has emerged as one of the most effective
technologies has become a well-established strategy in the field methodologies for the medium- and long-term conservation and
of Architectural Heritage (AH) documentation and conservation. management of AH (Di Stefano et al., 2020; Jouan and Hallot,
This convergence reflects a broader shift in digital heritage 2019). Since its early formalization (Murphy et al., 2009), HBIM
practices, where the generation of geometrically accurate 3D has generated an extensive body of scientific literature,
models is increasingly coupled with the need to structure, highlighting both its potential and its critical limitations (López
interpret, and manage heterogeneous information over time. et al., 2018; Penjor et al., 2024). One of the main challenges lies
Within this framework, digital representation is no longer in the fact that HBIM environments are commonly implemented
conceived as a purely descriptive output, but as a foundational using BIM software originally conceived for new constructions.
component of knowledge-based systems aimed at supporting This condition raises significant issues related to the faithful
conservation-oriented decision-making processes (Dimitrova et digital reconstruction of irregular, diachronic geometries and to
al. 2020; Bucharest Manifesto 2024). the management of heterogeneous information according to
The modelling of knowledge for the conservation and semantics coherent with conservation practices (Murphy et al.,
management of AH is generally structured around two 2013; López et al., 2018; Simeone et al., 2019; Acierno and
complementary processes: the digital representation of Fiorani, 2025).
architectural geometry and the hierarchical organization of In typical HBIM workflows, architectural modelling is largely
information. Together, these processes enable the creation of based on TLS and photogrammetric data (Diara et al., 2019;
digital environments capable of georeferencing, semantically Alshawabkeh et al., 2021; Ferretti et al., 2022). However, scanstructuring, and interrelating data from different sources, to-BIM processes remain predominantly manual and timesupporting preventive and planned conservation strategies. In consuming (Quattrini et al., 2015; Allegra et al., 2020),
this context, reality-based survey techniques play a central role, particularly when dealing with complex masonry systems.
as they provide the metric foundation for any subsequent Recent research has therefore focused on the development of
analytical or interpretative activity. Laser scanning and innovative approaches aimed at improving modelling efficiency
photogrammetry, in particular, have enabled the production of and flexibility, including the use of reality-based mesh models
highly accurate 3D datasets, typically starting from point clouds (Angeloni et al., 2023) and the integration of AI techniques for
that can be further processed into mesh models or used as a feature recognition and semantic support (Andriasyan et al.,
reference for parametric modelling (Brusaporci, 2015). Each 2020; Abreu et al., 2023; Croce et al., 2023). An important
representation addresses different needs: point clouds ensure research direction is represented by hybrid environments in
morphometric accuracy, mesh models offer detailed surface which point clouds, meshes, and BIM objects coexist and are
used simultaneously (Brookes, 2017). These approaches enable

This contribution has been peer-reviewed.
https://doi.org/10.5194/isprs-archives-XLVIII-2-W12-2026-97-2026 | © Author(s) 2026. CC BY 4.0 License. 97

<!-- p. 2 -->

The International Archives of the Photogrammetry, Remote Sensing and Spatial Information Sciences, Volume XLVIII-2/W12-2026
11th Intl. Workshop 3D-ARCH "3D Virtual Reconstruction and Visualization of Complex Architectures", 10–12 February 2026, Ancona, Italy

the integration of data derived not only from TLS and preventive, knowledge-driven, and sustainable approach to the
photogrammetric surveys (Spettu et al., 2021), but also from non- conservation and management of AH.
destructive diagnostic techniques (Garcia-Gago et al., 2022;
Mugnai et al., 2023), supporting a more informed interpretation 2. Methodology and case study application
of conservation issues. Despite their potential, hybrid workflows
are still only partially supported by mainstream BIM platforms, The methodological framework adopted in this research is
highlighting the need for complementary tools and interoperable conceived as an integrated and scalable workflow aimed at
systems. supporting the documentation, on-site inspection, conservation
To address these limitations, recent studies have increasingly and management of complex AH systems. The city walls of Fano,
focused on the development of shared platforms and dedicated distinguished by their centuries-old history, extension,
management tools. The European HeritageCare project, for stratification, and heterogeneous conservation conditions,
instance, demonstrates how raw point clouds can be enriched represent an exemplary case for testing a methodology that
with structured data and immersive visualization, transforming combines high-resolution 3D survey techniques, semantic
HBIM environments into effective knowledge infrastructures for information modeling, and virtual interaction tools within a
conservation planning and comparative analysis over time (Mora unified digital environment.
et al., 2021; Masciotta et al., 2021; Masciotta et al., 2023). The workflow is structured around the concept of a digital replica
Similarly, Clini et al. (2024) propose the integration of multiple that evolves from a geometrically accurate representation into a
2D and 3D representations within HBIM environments to semantically enriched information system, capable of supporting
support preventive conservation and maintenance strategies, preventive and planned conservation strategies. Rather than
enhancing data accessibility and interdisciplinary collaboration. treating survey, modeling, and visualization as independent
In parallel, several studies have explored the integration of HBIM phases, the methodology establishes a continuous and
with other digital environments, particularly GIS platforms bidirectional relationship between data acquisition, analytical
(Vacca et al., 2018; Matrone et al., 2023; Fortunato et al., 2025), interpretation, and operational use. In this perspective, the digital
as well as the development of point-cloud-based platforms in model is not conceived as a static archive, but as a dynamic
emergency contexts, such as the digital reconstruction of Notre- system designed to be updated, queried, and validated over time.
Dame Cathedral (Roussel and De Luca, 2023; Néroulidis et al., The methodological process is articulated into three main phases:
2024). These experiences underline the importance of  Data acquisition (2.1): the first phase focuses on the acquisiinteroperability and long-term data management in complex tion of geometric data through the integration of Terrestrial Laheritage scenarios. ser Scanning (TLS) and UAV-based photogrammetry, ensuring
More recently, the integration of HBIM with XR technologies metric accuracy and completeness in the representation of the
has opened new perspectives by extending digital models beyond architectural system.
desktop-based environments. Scan-to-HBIM-to-XR pipelines  Data processing (2.2): the second phase concerns survey data
have demonstrated their effectiveness in linking semantically processing to obtain a 3D model, enriched with semantic inforstructured models with on-site inspection and analysis activities mation related to construction techniques, stratigraphic rela-
(Banfi et al., 2022). XR tools are increasingly conceived not tionships, material characteristics, and conservation conditions.
merely as visualization layers, but as interactive interfaces Within this phase, the Masonry Quality Index (IQM) is impleenabling users to query, annotate, and update model-linked data mented as a quantitative parameter to support diagnostic asdirectly in situ, supporting long-term conservation through the sessment and comparative analysis.
prioritization and scheduling of tasks (Assefa et al., 2025; Clini  Implementation (2.3): The third phase introduces an XR-based
et al., 2025). tool designed as an operational interface for in situ interaction
Building upon this state of the art, this paper proposes a Scan-to- with the enriched model, enabling data consultation, annotaHBIM-to-XR workflow (Figure 1) specifically designed for tion, and updating directly in the field.
historic masonry systems and tested on the city walls of Fano This methodological framework aims to bridge the gap between
(Italy). The proposed methodology integrates multi-scale 3D digital documentation and conservation practice, providing a
survey data acquired through TLS and UAV photogrammetry coherent and interoperable system capable of supporting both
with a semantically enriched HBIM model oriented toward analytical interpretation and decision-making processes related
conservation analysis and management. The workflow is further to the management of AH.
extended through an AR-based interactive tool that enables onsite expert interaction with the digital model, supporting a

Figure 1. Workflow of the proposed methodology.

This contribution has been peer-reviewed.
https://doi.org/10.5194/isprs-archives-XLVIII-2-W12-2026-97-2026 | © Author(s) 2026. CC BY 4.0 License. 98

<!-- p. 3 -->

The International Archives of the Photogrammetry, Remote Sensing and Spatial Information Sciences, Volume XLVIII-2/W12-2026
11th Intl. Workshop 3D-ARCH "3D Virtual Reconstruction and Visualization of Complex Architectures", 10–12 February 2026, Ancona, Italy

Figure 2. Detail of the masonry texture reconstructed in 3D through laser scanning.
2.1 Data acquisition The TLS and UAV-derived datasets were subsequently
integrated within a common spatial reference system using
The data acquisition phase represents the foundational step of the GNSS-RTK–acquired GCPs, ensuring metric coherence and
proposed methodology, as it provides the geometric and metric interoperability between the different sources. The combined
basis upon which all subsequent modeling, analysis, and dataset offers a comprehensive and multi-scale geometric
interaction processes are built. Given the complexity and representation of the city walls, balancing global completeness
extension of the city walls of Fano, an integrated multi-scale with local detail. This unified point cloud constitutes the
survey strategy was adopted to capture both the overall geometric foundation for the subsequent 3D modeling and data
configuration of the defensive system and the local details enrichment phase, enabling a consistent transition from survey
required for conservation-oriented analysis. data to semantic interpretation and conservation-oriented
TLS was employed as the primary technique for documenting analysis (Figure 3).
vertical and sub-vertical surfaces, including wall elevations,
towers, gates, and areas characterized by material decay and 2.2 3D modeling and data enrichment
structural discontinuities. The TLS survey was carried out using
a Leica ScanStation P40 and Leica RTC360. Scan positions were The integrated TLS and UAV point cloud constituted the
carefully planned along the perimeter of the walls to ensure geometric basis for the construction of a three-dimensional
uniform coverage, reduce shadow zones, and capture both information model oriented toward conservation analysis and
external and internal faces of the masonry where accessible. The management. In accordance with the methodological framework
119 individual scans acquired were registered using a cloud-to- outlined in Section 2, the modeling phase was conceived not
cloud alignment procedure, allowing the generation of a unified merely as a process of geometric reconstruction, but as a
and metrically consistent point cloud. This approach ensured semantic interpretation of the architectural system, aimed at
high geometric reliability without the need for an extensive structuring heterogeneous data within a coherent and queryable
target-based network, while maintaining sufficient accuracy for environment.
detailed modeling and diagnostic purposes. The resulting TLS The modeling activities focused on the pilot area of Porta della
dataset provided a representation of surface geometry, enabling Mandria and the adjacent towers and curtain walls. A componentthe identification of construction techniques, material textures, based approach was adopted, allowing the subdivision of the
degradation and deformation patterns relevant to conservation walls into homogeneous portions according to construction
assessment (Figure 2). techniques, material characteristics, stratigraphic relationships,
To complement the terrestrial survey and overcome limitations and visible traces of transformation. This segmentation was
related to accessibility and line-of-sight constraints, a UAV- informed by direct observation of the masonry fabric, archival
based photogrammetric survey was conducted using a DJI Mavic documentation, and previous diagnostic investigations, enabling
3T. The aerial acquisition focused on the upper portions of the the distinction between original Roman structures, medieval and
walls, tower crowns, and horizontal surfaces that are typically early modern modifications, and integration works related to
difficult to document from ground level. Over 4200 high- restoration campaigns carried out during the twentieth and early
resolution images were acquired following a flight plan designed twenty-first centuries.
to ensure sufficient overlap and image quality for
photogrammetric processing. The images were processed using a
Structure-from-Motion (SfM) workflow combined with dense
image matching techniques, resulting in a photogrammetric point
cloud capturing roof-level and upper masonry features.

This contribution has been peer-reviewed.
https://doi.org/10.5194/isprs-archives-XLVIII-2-W12-2026-97-2026 | © Author(s) 2026. CC BY 4.0 License. 99

<!-- p. 4 -->

The International Archives of the Photogrammetry, Remote Sensing and Spatial Information Sciences, Volume XLVIII-2/W12-2026
11th Intl. Workshop 3D-ARCH "3D Virtual Reconstruction and Visualization of Complex Architectures", 10–12 February 2026, Ancona, Italy

enrichment strategy, the 3D model becomes an operative
information system supporting diagnostic interpretation,
monitoring, and conservation actions. The entire workflow was
implemented in the open-source Blender environment using the
Bonsai add-on, resulting in an HBIM model serving as the
primary reference for the structured organization and long-term
management of geometric and semantic information. (Figure 4).

2.3 XR tool

The third phase of the methodology concerns the development
of an Augmented Reality (AR) application conceived as an
operational interface for the on-site access, consultation, and Figure 3. View of a portion of the point cloud of the Walls of
updating of the information contained in the HBIM model Fano, derived from the integration of TLS and UAV
(Figure 5). The AR tool is integrated within an interoperable photogrammetry.
workflow that connects the modeling environment, a cloud-based
infrastructure, and a mobile application running on AndroidEach modeled element was associated with a structured set of
devices, with the aim of ensuring continuity between modelingattributes designed to support conservation-oriented analysis.
activities, on-site inspection, and data management. However,These attributes include construction phase, masonry typology,
the HBIM model is not transferred directly to the AR application.material composition, stratigraphic layers, and references to
Instead, the data required for on-site visualization and interactionhistorical sources and restoration records – the latter derive
are organized and made available through a cloud-basedmainly from archival research. Areas affected by decay and
infrastructure built on Google Cloud, which acts as the centralalteration phenomena were spatially identified and described
node for data storage, synchronization, and sharing. Within thisusing standardized terminology derived from conservation
infrastructure, Google Drive is used for the storage of digitalguidelines and technical standards. This approach allowed the
assets, including derived models, simplified geometries, images,model to function as a centralized repository of both geometric
and technical documentation, while Google Sheets is employedand descriptive information, facilitating a comprehensive
as a flexible data structure for managing alphanumericunderstanding of the architectural system and its state of
information associated with architectural elements andconservation.
degradation entities. This solution allows heterogeneous data toA key aspect of the data enrichment process was the integration
be managed within a unified system, while maintaining aof the Masonry Quality Index (IQM – Indice di Qualità Muraria)
structure that can be easily queried and updated from differentas a quantitative parameter supporting diagnostic assessment
environments. Access to cloud services is mediated by a Web(Borri and De Maria, 2019). The IQM was calculated for each
App, which functions as an interface layer between the BIMhomogeneous wall portion by evaluating a set of parameters
environment, the AR application, and the cloud infrastructure.related to construction rules, material characteristics, and mortar
The Web App centralizes data read and write operations,quality, considering vertical actions, in-plane actions, and out-of-
avoiding direct access to cloud service APIs from client devices.plane actions. The resulting values provide a synthetic
In this configuration, the AR application functions as arepresentation of the constructive quality and structural reliability
lightweight client that queries the system and submits updatesof the historical masonry, enabling comparative analysis across
through standardized requests, keeping the BIM environment anddifferent wall sections.
cloud infrastructure decoupled from the mobile application.The IQM values were directly linked to the corresponding
From the AR functionality perspective, the system is based on anmodeled elements as structured attributes within the information
environment-based tracking approach using an Area Target. Themodel. This integration enables thematic visualization of
Area Target was generated from the three-dimensional pointconstruction quality and conservation conditions, supporting the
cloud of the city walls of Fano, derived from the TLS surveyidentification of critical areas and the prioritization of
campaign described in the data acquisition phase. The point cloudintervention strategies. By embedding quantitative indicators
was processed to produce a spatial reference that provides awithin the same environment used for geometric representation
concise yet accurate description of the real environment, enablingand qualitative description, the model facilitates a direct
automatic recognition of the architectural context by the ARconnection between survey data, analytical evaluation, and
application. The use of an Area Target derived from reality-basedconservation planning. Through this modeling and data
data overcomes the limitations of marker-based tracking systems

Figure 4. View of the 3D model with degradation mapping, where erosion areas are identified and segmented as
IfcBuildingElementProxy within the HBIM model to support analysis, monitoring, and planned conservation activities.

This contribution has been peer-reviewed.
https://doi.org/10.5194/isprs-archives-XLVIII-2-W12-2026-97-2026 | © Author(s) 2026. CC BY 4.0 License. 100

<!-- p. 5 -->

The International Archives of the Photogrammetry, Remote Sensing and Spatial Information Sciences, Volume XLVIII-2/W12-2026
11th Intl. Workshop 3D-ARCH "3D Virtual Reconstruction and Visualization of Complex Architectures", 10–12 February 2026, Ancona, Italy

Figure 5. Main AR functionalities of the smartphone application: a) visualization of past restorations directly on the
architecture; b) color-coded mapping of conservation state and degradations; c) access to Masonry Quality Index (IQM)
results and related interpretative information; d) management of on-site inspections, including consultation of previous
records and creation of new ones.

and is particularly suitable for extended and complex attributes, and photographic documentation acquired on site.
architectural environments. When the user frames the walls with These data are transmitted to the cloud infrastructure and made
a smartphone, the application compares the data acquired from available for subsequent integration into the HBIM model.
the device’s camera and sensors with the spatial reference Degradation is managed as an information entity associated with
defined by the Area Target, determining the position and architectural elements, keeping the primary wall geometry
orientation of the device relative to the real architecture. Once separate from interpretative and conservation-related data.
spatial alignment is established, digital content is displayed
overlay on the corresponding wall surfaces. This mechanism
enables stable and repeatable visualization of digital information,
even in outdoor environments characterized by variable lighting
conditions and complex geometries. The adoption of the Area
Target also ensures compatibility with established AR
frameworks such as Vuforia, allowing the application to run on
standard mobile devices without the need for specialized
hardware configurations.

\3. Results

The following section presents the results of the proposed
workflow, illustrating how the AR tool enables access,
visualization, and on-site acquisition of semantic information.
Through a mobile device, users can access contextual data
associated with the architectural elements being observed.
Selecting a wall portion or a specific architectural component
triggers a request to the cloud-based system, which returns the
associated data in the form of textual information, numerical
values, or references to documentation stored in the cloud. In this
way, the AR application does not locally store the information
dataset, but functions as an interface for dynamic access to a
distributed information system. A relevant operational function
concerns the documentation of degradation phenomena observed Figure 6. Users can define decay areas directly on the masonry
during on-site inspections. By exploiting the spatial alignment through touch-based vertex placement, visualize the
provided by the Area Target, users can identify and record interpolated surface in real time, and record decay typology via
degradation areas directly on the real architecture (Figure 6). The voice input. The resulting data are exported as JSON and
collected information includes spatial localization, descriptive synchronized with the HBIM environment.

This contribution has been peer-reviewed.
https://doi.org/10.5194/isprs-archives-XLVIII-2-W12-2026-97-2026 | © Author(s) 2026. CC BY 4.0 License. 101

<!-- p. 6 -->

The International Archives of the Photogrammetry, Remote Sensing and Spatial Information Sciences, Volume XLVIII-2/W12-2026
11th Intl. Workshop 3D-ARCH "3D Virtual Reconstruction and Visualization of Complex Architectures", 10–12 February 2026, Ancona, Italy

Within the same AR environment, users can also create
georeferenced AR annotations, which are seamlessly integrated
into the HBIM model as contextual on-site observations (Figure
7). The use of flexible cloud-based data structures allows
degradation data and annotations to be queried and updated
efficiently, supporting monitoring activities and conservation
planning. The AR application further enables the consultation
and editing of alphanumeric information associated with
architectural elements and degradation entities. Modifications
performed on site are transmitted in real time to the cloud system
and subsequently made available for updating the information
model.

\4. Conclusion

The proposed workflow demonstrates how HBIM models of
complex and extensive architectural heritage can function as
operational and decision-support tools for sustainable
conservation management. By integrating multi-source 3D
documentation, HBIM-based semantic structuring, and AR-
based visualization and on-site editing, the study defines a
scalable and replicable methodology that effectively bridges
digital representation and field-based heritage practice (FigureFigure 7. The operator frames a specific portion of the masonry
8). using a mobile AR interface; a tap generates a georeferenced
The workflow combines geometric accuracy, semanticannotation anchored to the real structure. The annotation can be
modelling, and interactive tools, transforming the HBIM model recorded via voice input or text and is then transmitted to the
into a dynamic system for diagnosis, monitoring, and cloud, where it is automatically converted into a JSON file
conservation planning. Multi-scale survey data ensure a reliable readable and interoperable with the HBIM environment.
representation of complex masonry systems, while structured
This approach allows complex and discontinuous phenomena to semantic information supports the management of historical,
be documented without altering the architectural representation, material, and diagnostic data. The introduction of the Masonry
preserving the consistency of the HBIM model, and supporting Quality Index (IQM) as a parametric attribute enables
diachronic analysis. quantitative assessment of structural conditions which, together
The system supports the management of multiple degradation with the AR-based segmentation and mapping of degradation
phenomena associated with the same architectural element, phenomena, supports comparative analysis and the prioritization
enabling the representation of heterogeneous conservation of conservation interventions.
conditions and the recording of successive updates over time.

Figure 8. The figure shows the on-site AR preview of the operations and the corresponding final result in the HBIM model.
Georeferenced annotations are represented as grey IfcAnnotation elements, while decay segmentations are imported as colored
IfcBuildingElementProxy elements, with colors reflecting the associated decay typology and linked to the parent IfcWall.

This contribution has been peer-reviewed.
https://doi.org/10.5194/isprs-archives-XLVIII-2-W12-2026-97-2026 | © Author(s) 2026. CC BY 4.0 License. 102

<!-- p. 7 -->

The International Archives of the Photogrammetry, Remote Sensing and Spatial Information Sciences, Volume XLVIII-2/W12-2026
11th Intl. Workshop 3D-ARCH "3D Virtual Reconstruction and Visualization of Complex Architectures", 10–12 February 2026, Ancona, Italy

The use of AR as an on-site interface extends the HBIM model Cerato, Int. Arch. Photogramm. Remote Sens. Spatial Inf. Sci.,
beyond a static repository, enabling direct interaction with the XLVIII-M-9-2025, 63–69, https://doi.org/10.5194/isprsdigital replica in situ. Experts can consult and edit alphanumeric archives-XLVIII-M-9-2025-63-2025, 2025.
BIM data, generate georeferenced annotations, and define or
update degradation segmentations directly on the architecture. Banfi, F., Brumana, R., Roascio, S., Previtali, M., Roncoroni, F.,
Data recorded on site are transmitted to a cloud-based system and Mandelli, A., and Stanga, C.: 3D Heritage Reconstruction and
automatically integrated into the reference HBIM model, Scan-to-HBIM-to-XR Project of the Tomb of Caecilia Metella
establishing a continuous feedback loop between field operations and Caetani Castle, Rome, Italy, Int. Arch. Photogramm. Remote
and the central information environment. This approach Sens. Spatial Inf. Sci., XLVI-2/W1-2022, 49–56,
reinforces HBIM as a dynamic framework for adaptive and https://doi.org/10.5194/isprs-archives-XLVI-2-W1-2022-49knowledge-driven heritage conservation. 2022, 2022.
From a broader perspective, the methodology contributes to
redefining the concept of conservation, from ‘reactive’ Borri, A., and De Maria, A.: Il Metodo IQM per la Stima delle
restoration to ‘proactive’, knowledge-driven management (Della Caratteristiche Meccaniche delle Murature: Allineamento alla
Torre 2021). The proposed framework has the capacity to be Circolare n. 7/2019, Proceedings of the XVIII Convegno ANIDIS
adapted for use in other historic sites, with particular relevance to – L’ingegneria sismica in Italia, Ascoli Piceno, 15–19, 2019.
historic urban systems. The case of city walls exemplifies Brusaporci, S.: The Representation of Architectural Heritage in
heritage sites that persist in contemporary society and the the Digital Age, in Encyclopedia of Information Science and
environment without a specific use, yet whose presence is Technology, 3rd edn., 4195–4205, IGI Global Scientific
essential for understanding the processes of urban development Publishing, 2015.
in which they continue to play a fundamental role. For such
heritage, ensuring sustainable preservation requires support from Brookes, C.: The Application of Building Information Modelling
advanced digital tools that optimize both conservation and (BIM) within a Heritage Science Context, Discovery, Innovation
management processes. and Science in the Historic Environment, Historic England
Future developments will focus on integrating automated data Research Project Report 7351, 2017.
analysis, such as AI-assisted recognition of decay typologies
from high-resolution imagery, and on the use of IoT-based sensor Clini, P., Mariotti, C., Angeloni, R., and Muñoz Cádiz, J.:
networks for the acquisition of real-time environmental and Architectural Heritage Digital Representations for Conservation
structural data. In this sense, this workflow aligns with ongoing Strategies, Int. Arch. Photogramm. Remote Sens. Spatial Inf. Sci.,
research trends that aim to transform HBIM models into fully XLVIII-2/W4, 111–118, https://doi.org/10.5194/isprs-archivesoperational digital twins for heritage conservation and XLVIII-2-W4-2024-111-2024, 2024.
management, supporting both heritage professionals and
institutional decision-makers in the sustainable care of our built Clini, P., Nespeca, R., Angeloni, R., and Ferretti, U.: Aboveenvironments. Ground and Underground Architectural Heritage
Documentation: A Scan-to-HBIM-to-XR Approach for Historic
Acknowledgments Centres, Int. Arch. Photogramm. Remote Sens. Spatial Inf. Sci.,
XLVIII-M-9-2025, 345–351, https://doi.org/10.5194/isprsThe authors would like to express their sincere gratitude to the archives-XLVIII-M-9-2025-345-2025, 2025.
Centro Studi Vitruviani (Fano, Italy) for promoting and
supporting the research activities related to the Murum Dedit – Croce, V., et al.: H-BIM and Artificial Intelligence:
Mura Digitali project. Special thanks are extended to all the Classification of Architectural Heritage for Semi-Automatic
public and private institutions that supported the initiative. Scan-to-BIM Reconstruction, Sensors, 23(5), 2497,
https://doi.org/10.3390/s23052497, 2023.
References Della Torre, S.: Italian Perspective on the Planned Preventive
Conservation of Architectural Heritage, Frontiers of
Acierno, M., and Fiorani, D.: Conservation Process Model: An Architectural Research, 10(1), 108–116,
Ontology for Conservation in Architecture, Sapienza Università https://doi.org/10.1016/j.foar.2020.07.008, 2021.
Editrice, 2025.
Delpozzo, D., Appolonia, L., Scala, B., and Adami, A.: Federated
Allegra, V., Di Paola, F., Lo Brutto, M., and Vinci, C.: Scan-to- HBIM Models for Cultural Heritage: Survey Model and
BIM for the Management of Heritage Buildings: The Case Study Conceptual Model, Int. Arch. Photogramm. Remote Sens. Spatial
of the Castle of Maredolce (Palermo, Italy), Int. Arch. Inf. Sci., XLVI-2/W1-2022, 191–197,
Photogramm. Remote Sens. Spatial Inf. Sci., XLIII-B2-2020, https://doi.org/10.5194/isprs-archives-XLVI-2-W1-2022-1911355–1362, 2020. 2022, 2022.
Alshawabkeh, Y., Al-Rawashdeh, S., and Haala, N.: Developing Di Stefano, F., et al.: Knowledge Modeling for Heritage
a BIM-Based Digital Documentation for Heritage Buildings Conservation Process: From Survey to HBIM Implementation,
Using Laser Scanning and Photogrammetry, 2021. Int. Arch. Photogramm. Remote Sens. Spatial Inf. Sci., XLIV,
19–26, 2020.
Angeloni, R., Mariotti, C., Petetta, L., and Coppetta, L.: Enabling
Scan-to-BIM Workflow for Heritage Conservation and Diara, F., and Rinaudo, F.: From Reality to Parametric Models of
Management Process, Int. Arch. Photogramm. Remote Sens. Cultural Heritage Assets for HBIM, Int. Arch. Photogramm.
Spatial Inf. Sci., XLVIII-M-2-2023, 79–86, 2023. Remote Sens. Spatial Inf. Sci., XLII, 413–419, 2019.
Assefa, A. G., Scala, B., and Adami, A.: Information Modelling Dimitrova, E., Lavenir, M.-L., McMahon, P., Mūrniece, B.,
for Planned Preservation: The HBIM Model of Villa Forni Musso, S. F., Nagy, G., Rauhut, C., Rourke, G. D., Sciacchitano,

This contribution has been peer-reviewed.
https://doi.org/10.5194/isprs-archives-XLVIII-2-W12-2026-97-2026 | © Author(s) 2026. CC BY 4.0 License. 103

<!-- p. 8 -->

The International Archives of the Photogrammetry, Remote Sensing and Spatial Information Sciences, Volume XLVIII-2/W12-2026
11th Intl. Workshop 3D-ARCH "3D Virtual Reconstruction and Visualization of Complex Architectures", 10–12 February 2026, Ancona, Italy

E., and Selfslagh, B.: European Quality Principles for EU- Construction, 97, 122–137,
Funded Interventions with Potential Impact upon Cultural https://doi.org/10.1016/j.autcon.2018.10.018, 2019.
Heritage, European Commission, 2020.
Spettu, F., Teruggi, S., Canali, F., Achille, C., and Fassi, F.: A
Europa Nostra: Bucharest Manifesto for Quality-Driven Cultural Hybrid Model for the Reverse Engineering of the Milan
Heritage Practice in Europe, European Cultural Heritage Agora, Cathedral: Challenges and Lessons Learnt, Proceedings of
\2024. ARQUEOLÓGICA 2.0 – 9th International Congress & 3rd
GEORES – GEOmatics and pREServation, 281–291, 2021.
Garcia-Gago, J., et al.: HBIM for Supporting the Diagnosis of
Historical Buildings: Case Study of the Master Gate of San
Francisco in Portugal, Automation in Construction, 141, 104453,
https://doi.org/10.1016/j.autcon.2022.104453, 2022.

Jouan, P., and Hallot, P.: Digital Twin: A HBIM-Based
Methodology to Support Preventive Conservation of Historic
Assets through Heritage Significance Awareness, Int. Arch.
Photogramm. Remote Sens. Spatial Inf. Sci., XLII, 609–615,
\2019.

López, F. J., Lerones, P. M., Llamas, J., Gómez-García-Bermejo,
J., and Zalama, E.: A Review of Heritage Building Information
Modeling (HBIM), Multimedia Tools and Applications, 77,
2341–2371, 2018.

Masciotta, M. G., et al.: A Digital-Based Integrated Methodology
for the Preventive Conservation of Cultural Heritage: The
Experience of the HeritageCare Project, International Journal of
Architectural Heritage, 15(6), 844–863,
https://doi.org/10.1080/15583058.2019.1678938, 2021.

Masciotta, M. G., Sanchez-Aparicio, L. J., Oliveira, D. V., and
Gonzalez-Aguilera, D.: Integration of Laser Scanning
Technologies and 360º Photography for the Digital
Documentation and Management of Cultural Heritage Buildings,
International Journal of Architectural Heritage, 17(1), 56–75,
https://doi.org/10.1080/15583058.2021.2015444, 2023.

Mora, R., Sánchez-Aparicio, L. J., Maté-González, M. Á.,
García-Álvarez, J., Sánchez-Aparicio, M., and GonzálezAguilera, D.: An HBIM-Based Methodology for the Preventive
Conservation of Heritage Buildings, Automation in Construction,
121, 103426, 2021.

Murphy, M., McGovern, E., and Pavia, S.: Historic Building
Information Modelling (HBIM), Structural Survey, 27(4), 311–
327, 2009.

Murphy, M., McGovern, E., and Pavia, S.: Historic Building
Information Modelling – Adding Intelligence to Laser and
Image-Based Surveys, ISPRS Journal of Photogrammetry and
Remote Sensing, 76, 89–102, 2013.

Penjor, T., et al.: Heritage Building Information Modeling
(HBIM) for Heritage Conservation: Framework of Challenges,
Gaps, and Existing Limitations of HBIM, Digital Applications in
Archaeology and Cultural Heritage, 35, e00366,
https://doi.org/10.1016/j.daach.2024.e00366, 2024.

Quattrini, R., Malinverni, E. S., Clini, P., Nespeca, R., and
Orlietti, E.: From TLS to HBIM: High-Quality SemanticallyAware 3D Modeling of Complex Architecture, Int. Arch.
Photogramm. Remote Sens. Spatial Inf. Sci., XL-5/W4, 367–374,
\2015.

Simeone, D., Cursi, S., and Acierno, M.: BIM SemanticEnrichment for Built Heritage Representation, Automation in

This contribution has been peer-reviewed.
https://doi.org/10.5194/isprs-archives-XLVIII-2-W12-2026-97-2026 | © Author(s) 2026. CC BY 4.0 License. 104
