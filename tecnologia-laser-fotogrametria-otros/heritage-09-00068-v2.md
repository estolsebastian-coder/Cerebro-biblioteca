---
type: libro
title: "HBIM Implementation in Architectural Heritage:A Multitemporal Case Study of the Church of La Sang in Llíria"
author: "Inmaculada Oliver-Faubel, María Eugenia Torner-Feltrer, Emma Barelles-Vicente and Sergio Moral Saiz"
categoria: "Tecnología láser, fotogrametría, otros"
paginas: 26
extraccion: "texto"
fuente: "local:E:/Biblioteca digital/Tecnología láser, fotogrametría, otros/heritage-09-00068-v2.pdf"
convertido: 2026-10-13
---

# HBIM Implementation in Architectural Heritage:A Multitemporal Case Study of the Church of La Sang in Llíria

> Texto extraído de `Tecnología láser, fotogrametría, otros/heritage-09-00068-v2.pdf` (26 páginas, texto). El PDF original está en el disco E: (Biblioteca digital); `<!-- p. N -->` marca el inicio de cada página.

<!-- p. 1 -->

Article
HBIM Implementation in Architectural Heritage:
A Multitemporal Case Study of the Church of La Sang in Llíria

Inmaculada Oliver-Faubel 1,*, María Eugenia Torner-Feltrer 2 , Emma Barelles-Vicente 1,3
and Sergio Moral Saiz 4

1 Department of Construction Architecture, Universitat Politècnica de València, Camino de Vera s/n,
46022 Valencia, Spain; ebarelle@arq.upv.es
2 Department of Continuous Medium Mechanics and Theory of Structures, Universitat Politècnica de València,
Camino de Vera s/n, 46022 Valencia, Spain; meutorfe@upvnet.upv.es
3 Building Technology Research Centre, Universitat Politècnica de València, 46022 Valencia, Spain
4 Máster de Formación Permanente in BIM Management, Universitat Politècnica de València,
Camino de Vera s/n, 46022 Valencia, Spain
\* Correspondence: inolfau@csa.upv.es

Abstract

The conservation of architectural heritage poses significant challenges in buildings charac-
terised by complex construction sequences, cumulative transformations and fragmented
documentation, where traditional methods are insufficient to coherently integrate geom-
etry, historical information and stratigraphic analysis. This study proposes and applies
a multitemporal Heritage Building Information Modeling (HBIM) workflow aimed at
reconstructing and managing the historical evolution of architecture, using the Church of
La Sang in Llíria (València, Spain) as a case study characterised by the superposition of
Islamic, Gothic and contemporary phases. The methodology combines documentary and
archaeological analysis, in situ stratigraphic observation and high-resolution terrestrial
laser scanning as the geometric basis of the HBIM model. Historical phases are integrated
as structural components of the information model, with explicit documentation of inter-
pretative hypotheses and associated levels of reliability. The results show that the proposed
approach enables the identification and reinterpretation of spatial and constructive relation-
ships not previously described, the critical assessment of existing historical hypotheses, and
the generation of coherent three-dimensional reconstructions even in contexts with incom-
plete information. The resulting documentary archive facilitates diachronic comparison of
phases, ensures traceability of constructive elements and supports the production of reliable
graphic and analytical documentation, establishing itself as a valuable tool for historical
research, heritage management and the planning of future conservation interventions.

Keywords: HBIM; heritage; BIM; modeling; historical phases; documentary archive;
laser scanning
Academic Editor: Giovanni

Castellazzi

Received: 22 December 2025

Revised: 4 February 2026
Accepted: 6 February 2026 1. Introduction
Published: 10 February 2026 The conservation of architectural heritage poses significant challenges in documentaCopyright: © 2026 by the authors. tion and management processes, particularly in historic buildings characterised by complex
Licensee MDPI, Basel, Switzerland. construction sequences, cumulative transformations and varying degrees of deterioration.
This article is an open access article
The specialised literature emphasises the need for methodologies capable of integrating
distributed under the terms and
accurate geometry, heterogeneous historical information and rigorous stratigraphic analyconditions of the Creative Commons
Attribution (CC BY) license. ses in order to interpret the material evolution of the building in a coherent manner [1,2].

Heritage 2026, 9, 68 https://doi.org/10.3390/heritage9020068

<!-- p. 2 -->

Heritage 2026, 9, 68 2 of 26

In this context, traditional recording methods prove insufficient to reflect the inherent
complexity of historic monuments.
The incorporation of three-dimensional data acquisition technologies, such as terres-
trial laser scanning and digital photogrammetry, has enabled the generation of accurate
point clouds that constitute the basis for advanced digital models [3,4]. Building upon this
foundation, Heritage Building Information Modeling (HBIM) has become established as a
structured environment for the integration and management of multidisciplinary informa-
tion related to architectural heritage [5–7]. Nevertheless, the recent literature highlights
significant limitations in its application, particularly with regard to the standardisation
of levels of representation, the modeling [8] of irregular geometries, interoperability, and
the management of multitemporality [9,10]. These shortcomings are especially critical in
buildings with complex chronologies, where the digital reconstruction of historical phases
is essential for their proper understanding [11,12].
Within this framework, the Church of La Sang in Llíria (València, Spain), characterised
by an Islamic, Gothic and Modern construction sequence, constitutes an ideal case study
for the development of a multitemporal HBIM workflow that combines three-dimensional
data capture, documentary analysis and stratigraphic reading, aimed both at scientific
interpretation and at the future management of the monument.

Background to the Research

The HBIM methodology was developed as a specific framework for structuring and
managing architectural information in heritage contexts, overcoming the limitations of
traditional graphic documentation systems. Its early developments were based on the
integration of accurate geometry, historical documentation and construction data through
reverse-engineering processes applied to point clouds [2,13] and were consolidated with the
systematic incorporation of terrestrial laser scanning and photogrammetry as the geometric
basis of the model [8,14].
However, several studies have pointed out that the adoption of HBIM in conservation
projects has been limited, mainly due to the difficulty of operationally integrating the histor-
ical values of the asset and to the absence of specific methodological protocols [15,16]. These
limitations encouraged the incorporation of criteria derived from architectural archaeology,
which provide stratigraphic tools to organise the material and temporal information of the
building within the digital model [17].
Despite these advances, the digital reconstruction of earlier historical phases remains
relatively uncommon. “While difficulties in establishing reliable chronologies and the
high cost of absolute dating methods have played a role, the limited development of mul-
titemporal HBIM models has mainly been constrained by the difficulty of operationally
implementing historical phases as structured, traceable and semantically consistent com-
ponents within HBIM environments. As a result, until recently, reconstructions were
largely based on non-parametric 2D (two-dimensional) or 3D (three-dimensional) represen-
tations [13], oriented towards visualisation and lacking informational traceability [18].” In
this context, the comprehensive laser scanning of Notre-Dame carried out by Tallon [19]
marked a turning point by demonstrating the potential of reality-based geometry as a
support for rigorous evolutionary analyses.
In parallel, the literature has highlighted the need to adapt levels of representation
to the built heritage, introducing concepts such as the Level of Accuracy (LOA) and the
Level of Information (LOI) to complement traditional BIM (Building Information Modeling)
levels, which were originally conceived for new construction [20]. Likewise, the integration
of HBIM with GIS (Geographic Information Systems) and HGIS (Historical Geographic
Information Systems) has enabled the extension of analysis to urban and territorial scales,

https://doi.org/10.3390/heritage9020068

<!-- p. 3 -->

Heritage 2026, 9, 68 3 of 26

although interoperability issues persist, particularly in IFC–SHP (Industry Foundation
Classes—Shapefile) conversion processes [21–23]. Recent research has demonstrated the
potential of the HBIM–HGIS approach to articulate architectural and territorial information
within a shared framework [23], as well as its evolution towards advanced monitoring
models characteristic of early heritage digital twins [7].
The foundations of HBIM lie in the structured integration and management of the
full construction history of a building, enabling the explicit modelling and visualisation of
specific historical states within a coherent temporal framework. This entails integrating
all relevant information into the model, including archival records, graphic and written
sources, oral testimonies and even 3D survey data, in order to reliably reconstruct the
interventions and transformations that have occurred over time.
Although HBIM is presented as a powerful tool for the management, documentation
and conservation of heritage assets, its application has not yet been fully transferred to
the domain of rigorous historical reconstruction, which poses challenges beyond the mere
representation of time, particularly with regard to disappeared or poorly documented
construction phases. This reveals a dissonance between the theoretical potential of HBIM
and its actual practical application.
Adapting BIM to historical contexts requires a conceptual transformation that has
not yet been fully achieved in either professional practice or academic research. There
exists a fundamental knowledge limitation: even if HBIM can integrate large volumes
of information, the reliability of reconstructions ultimately depends on the quality and
precision of the input data. HBIM, in itself, does not resolve historical uncertainty; it can
only organise it. Moreover, the methodology runs the risk of conveying an appearance of
accuracy due to its parametric and geometrically precise nature, while the historical basis
may in fact be incomplete or hypothetical.
This situation reveals a disciplinary gap: while digital humanities tend to produce
visual reconstructions, HBIM specialists usually work on the existing building. There is
no genuine integration between these two practices. At the same time, a methodological
tension emerges: historical heritage requires working with hypotheses, yet HBIM has not
been designed to manage them in a natural or explicit manner.
As a result, a lack of a methodological framework for historical phases becomes
evident. There is no clear protocol for developing evolutionary HBIM models capable
of incorporating different construction phases of a building, representing uncertainty,
handling date ranges, justifying hypotheses through links to sources, or differentiating
between measured data and inferred data [24].
This calls for a conceptual evolution of HBIM itself, which should move from be-
ing a system for documenting the present to a historical–temporal management system
capable of incorporating the complexity of the past. This approach aligns with current
research trends on HBIM applied to heritage [25], which emphasise the need for traceable,
replicable workflows capable of synthesising heterogeneous information within a single
digital environment. Ultimately, there is a clear opportunity, but also a methodological
gap that must be addressed before HBIM can become a reliable tool for simulating past
architectural phases.
In recent years, several research projects and studies have addressed the integra-
tion of temporal dimensions within HBIM environments. Among them, the European
project INCEPTION (Inclusive Cultural Heritage in Europe through 3D semantic mod-
elling) represents a relevant milestone, as it introduced the concept of a “time machine”
applied to heritage assets and promoted the semantic aggregation of heterogeneous in-
formation, historical, archival, archaeological and restoration-related, within parametric
digital models [5,26,27].

https://doi.org/10.3390/heritage9020068

<!-- p. 4 -->

Heritage 2026, 9, 68 4 of 26

Despite these advances, the operational integration of historical phases as structured,
traceable and semantically enriched components of HBIM models at the architectural
scale remains limited. Existing approaches frequently rely on visual stratification or non-
parametric reconstructions, with reduced capacity to manage interpretative hypotheses
and semantic consistency across phases. Related research on multitemporal BIM has been
more extensively developed at the urban scale, focusing on diachronic representation and
historical transformation processes [28,29].
Within this context lies the main objective of this work: starting from a conventional
workflow in HBIM project management, to propose a modeling methodology based on
historical phases that enables the reliable and traceable simulation of previous architectural
configurations of the building. This methodological proposal is applied to the case of the
Church of La Sang in Llíria, with the aim of addressing its evolutionary reconstruction and
coherently integrating geometric, documentary, material and chronological information
within a single digital repository.
To this end, the following specific objectives are defined: (i) to establish a reasoned dat-
ing of the different construction phases through the combination of stratigraphic evidence,
historical sources and three-dimensional analysis; (ii) to generate historical simulations that
allow comparison between past configurations and the current state of the building; (iii) to
contrast these hypotheses with the results of previously available traditional architectural
survey methods; and (iv) to assess the effectiveness of the HBIM approach as a tool for the
visualisation, understanding and management of architectural transformation over time.

\2. Materials and Methods

The proposed methodology is structured into four main blocks, developed in a se-
quential and complementary manner, which define an HBIM workflow oriented towards
the multitemporal historical reconstruction of the building Figure 1.

Figure 1. General workflow proposed for the development of a multitemporal HBIM model.
Source: Authors.

It should be noted that, within a broader professional context, this workflow could
be extended through the incorporation of additional phases depending on the scope of
the project, such as restoration, maintenance, management or dissemination. However,
the present study focuses exclusively on the methodological blocks required for historical
research and for the generation of evolutionary HBIM models, in accordance with the
scientific objectives of the research.

2.1. BIM Uses Strategy

Within the framework of information management in accordance with ISO 19650 [30]
(International Organization for Standardization), the owner defines their expectations
and information requirements through the Exchange Information Requirements (EIR)
document. The technical team establishes the strategy and procedures to comply with
these requirements through the BIM Execution Plan (BEP), agreed upon and accepted by
all parties involved [5].
To achieve this, the definition of a BIM Uses strategy based on the taxonomy defined
by the University of Pennsylvania [31] and selectively applied within an HBIM approach is

https://doi.org/10.3390/heritage9020068

<!-- p. 5 -->

Heritage 2026, 9, 68 5 of 26

fundamental to guarantee information consistency, version control and temporal traceabil-
ity in accordance with the requirements of the ISO 19650 standard.
In this context, the priority HBIM uses are the following. For the simulation of
historical construction phases and the digital recreation of the construction sequence, the
uses 3D/4D Planning, 3D Control and Planning, and Construction Design are essential, as
they respectively allow the assignment of a temporal dimension to the model, the spatial
organization of each stage, and the modeling of solutions corresponding to each period,
enabling a clear and progressive reconstruction of the original evolution. In the traceable
management of information associated with each construction period, that is, preserving
and structuring data by phases, the prominent uses are Record Model, Asset Management,
and Maintenance Scheduling, because they document each state of the building, link
changes with operational consequences, and project that traceability toward conservation,
turning the model into a historical repository. Finally, for the generation of comparative
documentation between different evolutionary states, allowing physical changes over time
to be analyzed, Design Authoring, Design Review, and 3D Coordination are the priority
uses, as they enable the production of consistent documentation, the evaluation of spatial
variations, and the overlay of models to identify differences, consolidating HBIM as a tool
for historical and technical analysis.

2.2. Documentary Sources, In Situ Analysis and Geometric Data Acquisition

This methodological block aims to provide the documentary, material, and geometric
basis required for the multitemporal historical reconstruction of the building and for the
subsequent generation of the different phases of the HBIM model.
The process begins with an exhaustive review of all available documentary sources,
including historical archives, graphic sources, and written documentation, to establish
a preliminary framework of the building’s constructive evolution. This analysis makes
it possible to identify documented interventions, potential construction phases, and rel-
evant periods of transformation, which are subsequently contrasted with material and
geometric evidence.
In parallel, an in situ architectural survey is carried out, aimed at verifying and comple-
menting the information derived from documentary sources through direct observation of
the building. This analysis includes the identification of building fabrics, materials, reused
elements, construction traces and regularizations, as well as any other evidence relevant
to stratigraphic interpretation. In order to facilitate subsequent verification and modeling
tasks, this work is supported by a systematic and georeferenced photographic record.
The geometric data acquisition was carried out through a terrestrial laser scanning
(TLS) survey designed according to architectural surveying criteria. Scan positions were
planned to ensure full coverage of the building, minimise occlusions and accurately capture
the geometric complexity of both interior and exterior spaces.
The registration of the individual scans was performed using reference targets and a
controlled alignment process, subsequently optimised using Cyclone Register 360 (2022.1.0)
software. The quality of the registration was assessed through the analysis of residual errors
between overlapping scans, allowing the verification of the overall geometric consistency
of the point cloud. The resulting dataset therefore provides a reliable geometric basis for
subsequent HBIM modelling and for local dimensional verification, in accordance with the
objectives of representation and analysis of the study [32].
The set of documentary, material and geometric information obtained at this stage
constitutes the empirical basis upon which the HBIM modeling of the current state and the
subsequent reconstruction of the historical configurations of the building are articulated, as
described in the following section.

https://doi.org/10.3390/heritage9020068

<!-- p. 6 -->

Heritage 2026, 9, 68 6 of 26

2.3. HBIM Modeling, Chronological Integration and Generation of Historical Phases

HBIM modeling is conceived as an evolutionary and information-driven process, in
which the model progressively incorporates geometric, historical and chronological data
according to the objectives of the research. This approach is consistent with international
information management frameworks such as ISO 19650 [30] and the Royal Institute of
British Architects (RIBA) Plan of Work [33], which promote a structured and progressive
development of information throughout the life cycle of the asset. In heritage contexts,
however, this process necessarily requires the explicit definition of how constructive el-
ements are structured within the model and how temporal and historical information is
associated with them.
Within this framework, the HBIM environment is not limited to the geometric re-
construction of different historical states, but functions as a parametric information sys-
tem capable of organising, relating and managing heterogeneous data across multiple
construction phases. The model is structured through a hierarchy of parametric objects
corresponding to the main constructive elements of the building, such as walls, slabs,
structural components and relevant construction systems. These elements are modelled as
individualised objects with simplified but metrically coherent geometries, allowing their
identification and analysis at an architectural scale.
Each parametric object is associated with a set of non-geometric attributes that con-
stitute the HBIM database, including information related to construction phases, material
characteristics, construction techniques, state of conservation and documentary sources.
Historical and chronological information is therefore integrated through object attributes
rather than through independent graphic states, ensuring traceability of interpretative
decisions and enabling diachronic analysis within a single digital environment.
Stratigraphic analysis is integrated into the HBIM model in accordance with the scale
and objectives of the research. Rather than modelling individual stratigraphic units at
a micro-scale, the stratigraphic reading is synthesised at the level of macro-constructive
elements, such as walls, structural systems and significant building assemblies. These
elements are associated with specific construction phases defined through the correlation of
material evidence, documentary sources and in situ observation. Stratigraphic information
is thus incorporated as semantic attributes linked to each object, indicating its chronological
attribution and phase interpretation, rather than as explicit geometric subdivisions.
Based on this conceptual and informational structure, the modeling process begins
with the initial configuration of the BIM project, including the management of units, ge-
ographical location, levels, and phase definition, explicitly incorporating the identified
historical phases. Using the processed point cloud as the primary metric reference, the
HBIM model of the current state is developed through parametric modeling that integrates
architectural and structural elements, materials, construction properties and spatial rela-
tionships. This contemporary model constitutes the basis upon which both the subsequent
phases inherent to an intervention project and the different historical phases analysed in
the present study are articulated.
The reconstruction of past configurations is carried out through the critical integration
of documentary evidence, stratigraphic analysis, photographic records, and geometric
interpretation of the point cloud. Changes in masonry patterns, traces of disappeared
interventions, regularisations and embedded elements are identified, allowing the inference
of earlier construction phases. Where documentation is fragmentary or contradictory,
reasoned hypotheses are formulated, supported by typological parallels and comparisons
with buildings of similar typology or chronology. Reconstruction is therefore not based
on isolated hypothetical modeling, but on the systematic correlation between material
evidence, documentary sources, and geometric analysis.

https://doi.org/10.3390/heritage9020068

<!-- p. 7 -->

Heritage 2026, 9, 68 7 of 26

All interpretative decisions are explicitly recorded within the HBIM model itself. From
an operational perspective, this is implemented through phase-related parameters and cus-
tom non-geometric attributes assigned to each parametric object within the HBIM authoring
environment, allowing the explicit association of chronological attribution, documentary
sources and reliability levels. Interpretative decisions, therefore, differentiate levels of
reliability according to the nature of the available evidence and document the adopted
hypotheses, in accordance with the principles of transparency and traceability advocated in
the recent literature on digital heritage reconstruction [34,35]. The result is a multitemporal
HBIM model, structured through phase parameters that allow the activation and deacti-
vation of the different historical configurations of the building. This approach facilitates
direct comparison between stages, automated generation of graphic documentation, and
the coherent integration of geometric, historical and analytical information within a single
repository, aligned with conceptual frameworks of digital twins applied to heritage [36,37].
In this context, and in order to facilitate operational understanding, methodological
transparency, and reproducibility, the HBIM model incorporates a structured set of non-
geometric object-level parameters with predefined and controlled values. Each constructive
element includes a Historical Phase parameter (enumerated type), whose allowed values
correspond to the main evolutionary stages identified in the building: Main Mosque,
13th-century Christian Church, and Current State. This parameter enables chronological
classification and, in cases of documented constructive reuse, allows a single element to
maintain reference to its original construction phase while being functionally associated
with subsequent phases through a complementary reuse attribution field.
In parallel, a Confidence Level parameter (enumerated type) explicitly defines the
epistemic status of each element, with controlled values: Direct Material/Documentary
Evidence, Stratigraphic Inference, and Typological Hypothesis. This parameter is sys-
tematically assigned during modelling to ensure transparency in the distinction between
evidence-based and interpretative reconstruction.
Additional object-level attributes include: (i) Type of Supporting Evidence (survey
data, archival documentation, stratigraphic analysis, comparative study), and (ii) Interpre-
tative Status (existing, reconstructed, or hypothetical). All parameters are implemented as
shared project parameters to enable filtering, scheduling, multitemporal visualization, and
structured data extraction.
This semantic framework not only structures the multitemporal information em-
bedded in the model but also ensures traceability of historical attributions, controlled
management of uncertainty, and replicability of the proposed HBIM workflow in heritage
contexts characterised by complex constructive stratification.

2.4. Geometric, Semantic, Chronological and Functional Review of the HBIM Model

The review of the HBIM model is conceived as a phase of methodological control,
aimed at verifying the coherence of the resulting model from geometric, informational,
chronological and functional perspectives, without introducing additional interpretations
beyond those generated during the modeling process [38].
Firstly, geometric verification is carried out by comparing the model with the cleaned
point cloud, assessing morphological correspondence, and the absence of significant devia-
tions beyond the tolerance defined in relation to the objectives of the model, the adopted
Level of Development (LOD) and the architectural scale of representation.
Secondly, an informational and semantic review is conducted, consisting of checking
the correct assignment of materials, construction typologies, historical phases and docu-
mentary references to the modelled elements, ensuring source traceability and internal
coherence of the associated information [37].

https://doi.org/10.3390/heritage9020068

<!-- p. 8 -->

Heritage 2026, 9, 68 8 of 26

Chronological coherence is then verified by contrasting the reconstructed historical
phases with the stratigraphic analysis and the available historical documentation, explic-
itly documenting the hypotheses adopted in cases where the evidence is incomplete or
interpretative in nature [34,35].
Finally, the functionality of the model is analysed, that is, its capacity to generate
documentation, manage multitemporal information, interoperate with other environments
and operate as a digital repository for heritage research and conservation, in line with
digital twin approaches applied to the built heritage [38].
In this context, the HBIM model can be understood as an information-rich digital repre-
sentation of the physical asset, approaching some principles associated with the concept of
a digital twin. However, it does not establish a continuous bidirectional exchange with the
physical building, as it focuses on the structured integration of historical, constructive and
interpretative information for documentation, analysis and heritage management rather
than real-time monitoring.
This review process ensures that the multitemporal HBIM model functions as a struc-
tured, traceable and replicable repository for the analysis and management of architectural
heritage, without seeking to establish validation metrics beyond the methodological scope
of the study.

\3. Case Study: La Sang Church and Multitemporal HBIM

The Church of Santa María, also known as La Sang (Figure 2), is located in Llíria
(València, Spain), an area characterised by continuous occupation since the Bronze Age.
The church stands on a site that, during the Andalusí period, housed a fortified enclosure
and the main mosque of Lyria, which was possibly built over Roman remains that have
not yet been confirmed. Following the Christian conquest in the 13th century, the Islamic
building was adapted and transformed, giving rise to the present Gothic church. Figure 3
summarises constructive and spatial transformations of the church, highlighting the key
historical phases that affected its architectural configuration. The timeline focuses on
structural and volumetric interventions relevant to the multitemporal HBIM modelling,
and does not include minor liturgical, ornamental or movable alterations that did not
modify the overall spatial or constructive organisation of the building.

(a) (b)

Figure 2. The Church of La Sang in Llíria (València, Spain): (a) general exterior view showing the
nave and tower; (b)general view showing the original entrance and rear façade. Source: Authors.

https://doi.org/10.3390/heritage9020068

<!-- p. 9 -->

Heritage 2026, 9, 68 9 of 26

Figure 3. Chronological timeline. Source: Authors.

The result of these transformations was the configuration of a conquest church, an
early typology of Mediterranean Gothic that is clearly identifiable in La Sang due to the
good preservation of its constructive stratigraphy. The building is currently organised as a
single-nave structure with lateral chapels inserted between the buttresses, a differentiated
presbytery at the north, and a high choir located at the south above the main entrance. A
tower is integrated into the original fabric, and the church presents a clear longitudinal
spatial arrangement that has remained largely unaltered since the late medieval period,
despite later additions and restoration works. Its significance has been institutionally
recognised: it was declared a National Monument in 1919, the first religious building in the
Valencian Community to receive this designation and was subsequently listed as a Bien de
Interés Cultural, the highest level of heritage protection under Spanish law.
The coexistence of elements of Islamic and Christian origin, together with the clarity
of its evolutionary phases, makes La Sang an ideal case for the application of HBIM
methodologies, enabling the digital reconstruction of its historical stages and the precise
analysis of the spatial and structural evolution of the complex. The historical evolution
of the church, documented through archival sources and previous studies, provides the
chronological framework for the definition of the different construction phases addressed
in the following sections.
Detailed, constructive and material analyses are beyond the scope of the present study
and would require specific diagnostic investigations not addressed in this work.

3.1. HBIM Modeling of Historical Phases

After the study of documentary sources and the on-site architectural analysis, the
data acquisition phase begins through laser scanning. To this end, a scanning plan is
developed defining the number and location of scanner positions, the areas to be covered,
the minimization of shadowed zones, and the balance between scanning quality and
acquisition time. This plan is graphically represented in Figure 4, which illustrates the
distribution of the scanning stations and the overall data capture strategy.
Data acquisition using a Leica® RTC 360 scanner is carried out within a single working
day. An exterior and interior circular scanning sequence is performed in a counterclockwise
direction, starting from the main façade. A scanning position is placed at the main gate,
enabling proper alignment and connection between the exterior and interior point clouds.
The resulting point clouds are processed using Cyclone® Register 360 software, where
they are registered and optimised, and finally exported in the open-standard E57 format.
The dataset is then imported into Archicad®, allowing the modelling phase to begin.

https://doi.org/10.3390/heritage9020068

<!-- p. 10 -->

Heritage 2026, 9, 68 10 of 26

(a) (b)

Figure 4. Scanning plan: (a) exterior scanning plan; (b) interior scanning plan. Symbols indicate the
laser scanner station points used for data acquisition. In (b), solid and dashed lines correspond to
conventional architectural drawing representations of visible and inferred elements in the 2D plan.
Source: Authors.

3.1.1. Initial Configuration of the HBIM Environment

The first step in the modeling process is the introduction of the project information.
The next step is the definition of the project levels, Figure 5, based on the previously
exported point cloud:

Figure 5. Defining project levels. Source: Authors.

Next, the project phases are defined, which correspond to three relevant historical
phases of the church:

https://doi.org/10.3390/heritage9020068

<!-- p. 11 -->

Heritage 2026, 9, 68 11 of 26

• Phase 01: Current state, 21st century.
• Phase 02: Original church, 13th century.
• Phase 03: Main Mosque, 12th century.

The numerical ordering of the phases reflects the sequence of the modelling process
rather than their chronological order, as the HBIM workflow starts from the current state of
the building and progressively reconstructs earlier historical configurations.

3.1.2. Modeling of the Current Phase: La Sang in the 21st Century

As this is an existing building, the modeling of the current state is based on a high-
resolution terrestrial laser scanning survey, which provides the geometric reference for
defining the overall volumetry and spatial configuration of the asset. The processing
and registration of the point cloud were carried out using Cyclone Register 360 software,
resulting in a mean registration error of 0.002 m, as reported by the registration quality
report generated after the alignment and optimisation of the different scanning stations.
This value corresponds to the mean registration error of the point cloud and expresses
the overall quality of the alignment between the individual scans, rather than a homo-
geneous metric resolution or a geometric accuracy directly applied to all elements of the
HBIM model. Based on this geometric reference, the modeling of the current state was
initially developed at a Level of Development (LOD) 200, suitable for defining the general
geometry and the main spatial relationships of the building.
Subsequently, the model is progressively refined to higher Levels of Development
through the incorporation of additional geometric and constructive information, while the
point cloud acts as a reference for the local geometric verification of the correspondence
between the modeled geometry and the survey data. The overall level of detail and
precision of the HBIM model is therefore defined in coherence with an architectural-scale
representation, suitable for documentation, analysis and heritage research purposes.
To achieve a LOD 300, the remains, vestiges, and elements from other historical phases
are modeled as structural and load-bearing components, including pillar moldings, arch
and vault profiles, decorative moldings of the altarpiece, carpentry details, terrain details,
and remnants in walls that persist in the present day (Figure 6). All these elements together
define the current state and, as they will be visible across the different visualizations of
historical phases, they will subsequently allow for a more accurate modeling of earlier
phases, for which less information is available than for the current state.

(a) (b) (c)

Figure 6. Interior of the nave, current state. (a) Photograph; (b) point cloud; (c) LOD 300 model.
Source: Authors.

The modeling of Phase 01 is not completed until interferences are detected and re-
solved using Archicad’s “Solid Element Operations” (SEO) tool, reaching a LOD 350 suit-
able for obtaining reliable measurements for future restoration works. At this stage, materi-
als have been defined by adjusting their appearance and incorporating physical properties,

https://doi.org/10.3390/heritage9020068

<!-- p. 12 -->

Heritage 2026, 9, 68 12 of 26

reinforcing the fact that the model manages detailed information beyond its purely vi-
sual representation.

3.1.3. Modeling of the Original Phase: La Sang in the 13th Century

The modeling of the original church in the 13th century, immediately after the com-
plete construction of its plan, is developed based on the knowledge obtained through the
collection and synthesis of information and the vestiges modeled in the previous phase.
The three-dimensional model of the 13th century (Figure 7) represents the reconstructed
configuration of the building at this phase; the following points highlight the main differ-
ences with respect to the current state, including later additions that are not represented in
this model:

• The second body of the tower was built at least a century after the church.
• The chapels were expanded on both sides of the nave between the 14th and
15th centuries.
• The doorway on the southeast façade, originally the main access, was relocated fol-
lowing the construction of the chapels.
• The current main entrance was built in the 15th century.
• The buttresses visible in the 13th century became integrated into the structure after
the expansion of the chapels.

Figure 7. Original church, 13th century. Elements. Source: Authors.

3.1.4. Modeling of the Previous Phase: The Main Mosque Before the 12th Century

From the Main Mosque, after its demolition in the 12th century, several structural
elements were reused at the time to initiate the construction of the church plan. Its modeling
is undoubtedly the most complex historical phase, due to the scarcity of documentary
information about the building. With regard to physical remains, only the mosque’s
cistern and the well are currently preserved, allowing an approximation of its ground
plan. Two columns that today support the choir of La Sang are also preserved; these
provide information about the height of the building and make it possible to formulate
hypotheses regarding its original elevation. Likewise, remains of the mosque integrated
into the walls of La Sang are preserved, especially on the northwest façade, which likely

https://doi.org/10.3390/heritage9020068

<!-- p. 13 -->

Heritage 2026, 9, 68 13 of 26

corresponds to the transitional wall between the sahn, courtyard for purification, and the
hypostyle prayer hall.
To complete the model of this early phase, it is necessary to rely on the theories pro-
posed by municipal archaeologists regarding the layout of the plan, on historical research
on hypostyle mosques in Spain, and on an informed interpretation of the possible rela-
tionships between the construction elements shared by both buildings throughout history.
Figure 8 shows the different representative elements of the proposed interpretation of the
mosque. It should be noted that the minaret, or mosque tower, was not modeled due to the
lack of reliable data to establish its exact location or even to confirm its existence.

Figure 8. Interpretation of the mosque. Elements. Source: Authors.

In order to reinforce methodological transparency, the decisions adopted in the recon-
struction of the Islamic phase are articulated through a clear distinction between measured
evidence, documentary sources, and reasoned hypotheses. Preserved elements, such as
the cistern, the well, and selected components reused within the later church fabric, con-
stitute the most reliable basis for defining the general layout and scale of the building,
while the stratigraphic reading of embedded masonry supports the proposal of functional
relationships compatible with a hypostyle mosque scheme.
Where direct evidence is incomplete, spatial and volumetric configurations are derived
from typological inferences tested against coeval architectural examples and assessed for
overall geometric coherence, with their interpretative nature explicitly acknowledged.
Conversely, architectural elements lacking sufficient material or documentary support
have not been incorporated into the model, in accordance with a deliberately conservative
methodological approach.
Reconstruction reliability is managed through the explicit differentiation of confidence
levels, integrated within the HBIM model itself, allowing a clear distinction between com-

https://doi.org/10.3390/heritage9020068

<!-- p. 14 -->

Heritage 2026, 9, 68 14 of 26

ponents supported by direct evidence and those of a more hypothetical nature. In this way,
uncertainty is not suppressed but documented and incorporated as an inherent part of the
historical interpretative process. Although the application of probabilistic methods or confi-
dence intervals would be conceptually relevant, their implementation requires independent
and quantifiable datasets that are not available for the present case study; consequently,
such approaches are identified as a line of future methodological development.

3.1.5. HBIM Model Review

The review of the developed HBIM model is conceived as a process aimed at ensuring
the reliability of the multitemporal dataset generated across the four defined levels. This
review phase is conceived as a methodological coherence assessment rather than as an
external archaeological or statistical validation, which would require independent datasets
not available for the present case study. The levels are:

(a) The metric accuracy of the current-state model is verified through direct comparison
with the original point cloud, assessing deviations and adjusting elements where
necessary. Detected differences are maintained when they correspond to real defor-
mations of the building, thereby preserving the material and spatial authenticity of
the monument.
(b) The review of the architectural and constructive consistency of each phase involves
verifying that the proposed geometry corresponds to plausible solutions for each
period, such as the modulation of arches and vaults in the Gothic church or the
relationship between both layouts at points of structural continuity, among others.
(c) The review of historical coherence focuses on the 13th-century phase and the Islamic
period. As the mosque represents the most hypothetical phase, the review relied
especially on stratigraphic analysis, on the compatibility of its ground plan with
the elements reused in the medieval church, and on architectural parallels with
hypostyle mosques.
(d) Overall, the review process confirmed that the HBIM model provides a geometrically
consistent representation of the current state, based on its correspondence with the
registered point cloud, and supports historically grounded reconstructions derived
from documented sources and interpretative assessment. The model further enables
the extraction of structured information in multiple formats for research and heritage
documentation purposes.

3.1.6. Generation of the Documentary File

Once the modeling is completed, the result is a document that contains the information
about the asset. Within this document, the information can be consulted in different ways:

a. 2D views. Traditional drawings, dimensionable and measurable. The elements shown
in the drawings are logically linked to the elements of the model; therefore, any
modification of elements in the model will directly affect the views. The fact that the
starting point of the modeling process was a point cloud makes it possible to obtain
2D views that are fully consistent with the real geometric dimensions of the asset,
Figure 9a.
b. 3D views. Within the 3D views, it is possible to navigate in order to access visualiza-
tions that would not be possible otherwise. The correct definition of the historical
phases and the elements belonging to each of them makes it possible to switch between
the different defined states of the asset, as shown in the comparison in Figure 9b.
c. Data tables. These allow the direct and detailed visualization and management of the
model information, facilitating the quantification of elements and the calculation of
unit totals. Each element has its own ID (identifier), which enables its identification in

https://doi.org/10.3390/heritage9020068

<!-- p. 15 -->

Heritage 2026, 9, 68 15 of 26

the tables and ensures traceability throughout the project, as long as the element is
not deleted.
d. Realistic infographics. Although they are not strictly a type of BIM view within the
documentary file, infographics provide non-vector images from a specific project
perspective. This facilitates the visualization of the elements in a realistic and easily
interpretable manner for any type of audience, professional or non-professional, as
shown in Figure 10.

(a) (b)

Figure 9. 2D and 3D views. (a) Planimetry of the mudejar roof; (b) 3D view of the mudejar roof.
Mudéjar architecture is a hybrid artistic tradition that emerged from the coexistence of Islamic and
Christian cultures in medieval Spain. Source: Authors.

Figure 10. Interior infographic. Central nave of La Sang viewed from the choir. Source: Authors.

Finally, it should be added that the resulting documentary file constitutes a “living”
document, capable of incorporating new information throughout the entire life cycle of

https://doi.org/10.3390/heritage9020068

<!-- p. 16 -->

Heritage 2026, 9, 68 16 of 26

the building, both from future phases with physical and geometric characteristics different
from the current ones, and from past phases, should new archaeological surveys be carried
out that provide additional information about the asset.

\4. Results

4.1. Dating of Historical Phases

The results obtained from the HBIM model generally confirm consistency with the
existing historical documentation on the church of La Sang, including a rectangular plan,
an open interior space, thick walls and the presence of buttresses, although the detailed
geometric analysis reveals significant deviations that had not been previously described.
In particular, the comparison between the model and archival drawings highlights the
lack of orthogonality in the plan, with the main deviations concentrated in the first and
second nave bays (Figure 11). Likewise, a rotation of 4.59◦is identified between the main
façade and the frontal plane of the tower, revealing a relevant geometric discrepancy in the
configuration of the building.

Figure 11. Comparative analysis between a historically assumed perimeter layout (a) and the HBIM-
based plan obtained from the survey and modelling process (b). Source: Authors.

The analysis of the buttresses suggests their placement between bays, structurally
associated with the diaphragm arches. However, the lack of precise information regarding
their original dimensions has led to the formulation of different volumetric hypotheses,
modeling alternatives that consider both freestanding buttresses and larger volumes, very
likely absorbed in later phases through the addition of lateral chapels.

https://doi.org/10.3390/heritage9020068

<!-- p. 17 -->

Heritage 2026, 9, 68 17 of 26

The hypothetical modeling of the Main Mosque of Llíria, based on the preserved
vestiges and on typological studies of hypostyle mosques in the Iberian Peninsula, has
made it possible to approximate the dimensions of the courtyard (s.ah.n), the hypostyle
prayer hall and the probable height of the complex based on the two surviving columns.
The identification of Islamic remains integrated into the current walls, especially on the
northwest façade, reinforces the hypothesis that this wall corresponded to the boundary
between the ablution courtyard and the prayer hall (Figure 12).

Figure 12. Longitudinal section of the Great Mosque and its underground cistern from the documen-
tary archive. Source: Authors.

Although both the plan and the volumetry of the mosque constitute a hypothetical
reconstruction, its three-dimensional representation, nonexistent until now, provides a
solid interpretative framework for understanding the historical evolution of the complex
and the process of constructive reuse following the Christian conquest. Once the different
historical phases have been defined and dated, the HBIM model allows their simultaneous
activation, facilitating comparative visualization and the analysis of spatial relationships
between phases. The superposition of the Islamic phase and the original construction of
La Sang after the demolition of the mosque demonstrates, for example, the direct reuse
of the mosque façade as the northwest façade of the Christian church. In Figure 13, the
perimeter of the former mosque is identified by a dashed red outline, while the wall shared
by both the Islamic phase and the original construction of La Sang is highlighted with
a solid red shading, making explicit the continuity and reuse of this structural element.
When constructive reuse is documented, the same wall is modelled as a single HBIM object
associated with multiple historical phases through semantic parameters, rather than being
duplicated geometrically. Within this interpretative framework, additional hypothetical
elements are explicitly identified. The column layout of the prayer hall, represented in
green, is proposed on the basis of the standard typological configuration of hypostyle
mosques and the presence of two columns preserved in situ. Likewise, the lateral walls of
the former mosque prayer hall, shown in yellow, are interpreted as a hypothesis derived
from the continuity of the courtyard (s.ah.n) walls and from stratigraphic analysis of the
existing building fabric. These elements are therefore presented as reasoned hypotheses,
clearly differentiated from documented remains within the multitemporal HBIM model.

https://doi.org/10.3390/heritage9020068

<!-- p. 18 -->

Heritage 2026, 9, 68 18 of 26

(a) (b)

Figure 13. (a) 2D plan: dashed red, mosque perimeter; solid red, reused wall; green, hypothetical
column layout; yellow, interpreted lateral walls of the prayer hall. (b) 3D view of the HBIM model of
the Islamic phase, showing the spatial relationship between the prayer hall and the courtyard (s.ah.n).
Source: Authors.

4.2. Application of the Documentary Archive

The generated documentary archive constitutes the main result of the HBIM method-
ological process and the fundamental added value of the study, being configured as a
comprehensive deliverable for the management of the heritage asset by the local admin-
istration. This digital repository coherently integrates geometric, historical, material and
chronological information and enables multiple fields of application.
From an educational and cultural perspective, the archive facilitates interactive visu-
alization of the church across different historical phases and their comparison, offering
a high degree of accessibility for both specialists and the public. The hypothetical 3D
representations of the Main Mosque of Llíria, for example, can be used in museographic or
exhibition contexts, contributing to the dissemination of the city’s Islamic past and to the
enhancement of the monument.
The model also enables virtual access to elements that are difficult to observe directly,
such as interior ornaments or the polychrome roof structure, through selective layer man-
agement and isolated visualization of specific components. This functionality is particularly
relevant for both cultural dissemination and the planning of conservation and restoration
interventions (Figure 14).
In the technical field, the archive allows the isolation of specific construction systems,
such as the load-bearing structure, for the generation of basic schemes of structural behavior
as well as the identification, cataloguing and traceability of singular elements through a
unique ID (Identifier) (Figure 15). This traceability is key in dismantling, restoration and
replacement operations, ensuring consistency between 2D and 3D documentation.
Furthermore, the model enables accurate two-dimensional and three-dimensional mea-
surements to be taken directly within the digital environment or on the point cloud, opening
the door to long-term comparative analyses, such as monitoring structural deformations,
displacements, deflections or the evolution of cracks.

https://doi.org/10.3390/heritage9020068

<!-- p. 19 -->

Heritage 2026, 9, 68 19 of 26

Figure 14. Representation of the mudejar frieze of La Sang, polychrome and decorate with mythologi-
cal creatures. Source: Authors.

Figure 15. Basic structural stress diagram of La Sang. Arrows represent the direction and flow of
structural loads acting on the main supporting elements. Source: Authors.

Finally, the scanning and modeling process has revealed inconsistencies with previous
historical interpretations, especially regarding the position of the passage arcade between
the courtyard and the hypostyle prayer hall of the mosque. The comparison between the
point cloud and traditional representations suggests new hypotheses about the extent of
the mosque (Figure 16) or the possible existence of a minaret associated with that arcade.
As these hypotheses require further archaeological research and specialized studies, the
generated documentary archive is established as the fundamental basis for future historical
revisions and for a critical reassessment of the pre-existing buildings on the site of La Sang.
The visualisation of the different historical configurations presented in this section is
supported by the multitemporal structure of the HBIM model, which allows the selective
display of elements associated with specific construction phases. Documentary and archival
sources are linked to the model through object-based associations, enabling contextual
access to the related information in direct relation to both geometry and the corresponding
historical phase. This approach facilitates the interpretation of the building’s diachronic

https://doi.org/10.3390/heritage9020068

<!-- p. 20 -->

Heritage 2026, 9, 68 20 of 26

evolution and the coherent consultation of geometric and documentary data within a single
digital environment.

(a) (b)

Figure 16. Detection of inconsistencies with pre-existing archaeological data of the Great Mosque.
(a) conflict between the wall and the arcade; (b)adaptation of the wall to validate the arcade. Arrows
highlight the specific areas where the inconsistency is identified under each proposed interpretation.
Source: Authors.

\5. Discussion

The results obtained through the application of a multitemporal HBIM workflow to
the Church of La Sang confirm the potential of this approach as a solid methodological
framework for the historical–evolutionary interpretation of heritage buildings characterised
by complex construction sequences. Beyond the specific findings related to the Islamic and
Gothic phases of the monument, this study contributes to the current debate on the need
for HBIM to evolve from a tool primarily oriented towards documenting the present state
into a system capable of structuring, managing and interpreting the temporal dimension of
the built heritage.
Recent literature has repeatedly pointed out that, although HBIM enables the in-
tegration of geometric, material and documentary information within a single digital
environment, its practical application remains largely focused on the representation of the
building’s current condition, with a limited incorporation of history as an operative variable
of the model [35,37,39]. In contrast, the main methodological contribution of this study lies
in the consideration of historical phases as structural components of the information model.
These phases are not conceived as independent graphic states, but as informational entities
explicitly linked to material evidence, documentary sources and reasoned interpretative
decisions, allowing a coherent, verifiable and traceable management of the architectural
evolution of the building.
Within this framework, geometry derived from terrestrial laser scanning plays a fun-
damental role not only as a metric reference but also as an active tool for historical analysis.
The systematic comparison between the point cloud and the HBIM model made it possible
to identify significant geometric irregularities, such as deviations from orthogonality, rota-
tions between construction axes, or volumetric mismatches between phases, that had not
been precisely described in previous studies. These geometric evidences proved decisive
for reinterpreting the construction sequence of the building and for supporting hypotheses
related to the reuse and adaptation of Islamic structures during the configuration of the
Gothic church, reinforcing the stratigraphic reading of the ensemble [26].
The explicit integration of criteria derived from building archaeology within the
HBIM environment emerges, in this sense, as one of the core elements of the proposed

https://doi.org/10.3390/heritage9020068

<!-- p. 21 -->

Heritage 2026, 9, 68 21 of 26

approach. As highlighted by several authors, the incorporation of stratigraphic tools into
digital models makes it possible to overcome the traditional separation between historical
analysis and graphic representation, fostering a critical reading of the building based on
the correlation between materiality, chronology and transformation [26,40]. This approach
positions the present study in an intermediate methodological space between HBIM and
building archaeology, enabling the model to function simultaneously as an instrument for
historical analysis and as a structured repository of heritage information.
The modeling of the earliest phases of the complex also highlights one of the main
methodological challenges of HBIM applied to historical reconstruction: the management
of uncertainty. Recent literature has warned about the risk that parametric models may con-
vey a false sense of historical accuracy when the available evidence is partial or indirect [35].
In this study, HBIM is not conceived as a tool to resolve historical uncertainty, but rather as
a system to make it explicit, document it and manage it in a structured manner. The differ-
entiation between measured, inferred and comparative data, together with the assignment
of reliability levels and the documentation of adopted hypotheses, reinforces the scientific,
critical and revisable nature of the model, in line with the principles of transparency and
paradata advocated in the field of digital heritage [41]. For this reason, while uncertainty is
primarily managed and documented at the semantic level of the HBIM model, a simplified
graphic code is also provided in key reconstruction figures to support immediate visual
comprehension of evidence-based versus interpretative components.
From a methodological perspective, the use of historical phases as operative param-
eters within the HBIM model offers clear advantages over conventional representations
based on layers or non-parametric models. The possibility of activating, comparing and
superimposing different chronological states within a single digital repository facilitates a
diachronic reading of the building and allows the direct analysis of spatial, constructive and
functional relationships between phases. This approach is consistent with recent research
exploring HBIM–GIS integration and the development of advanced temporal models for
the analysis of the built heritage [42,43].
The results further demonstrate that the proposed workflow goes beyond the scope
of historical interpretation and provides solid support for the future management of the
heritage asset. The generated documentary archive is configured as an evolutionary or
“living” model, capable of incorporating new information derived from archaeological
research, conservation interventions or monitoring processes over time. This capability
aligns with current trends that envisage the evolution of HBIM towards integrated heritage
management systems and digital twins, oriented towards preventive conservation and
informed decision-making [39,41].
In this sense, the future life of the HBIM model should be understood in terms of
institutional stewardship rather than mere authorship. Although developed within an
academic research context, the model is conceived to be transferable to heritage authorities
or public institutions responsible for the conservation and management of the asset. Its
long-term maintenance and updating would require specialised technical expertise for
model editing and data integration, while non-specialised users could interact with the
model through extracted views, drawings or visual outputs for analytical, educational
or dissemination purposes. This distinction between expert management and mediated
access reinforces the applicability of the proposed workflow beyond research, without
compromising its scientific rigor.
Despite these contributions, certain limitations inherent to the study must be ac-
knowledged. The reconstruction of the Islamic phase relies on comparative typological
analyses and reasoned hypotheses, constrained by the absence of extensive archaeological
excavations. Although the HBIM model provides a coherent and rigorously documented

https://doi.org/10.3390/heritage9020068

<!-- p. 22 -->

Heritage 2026, 9, 68 22 of 26

interpretative framework, future research may refine or reformulate some of the proposed
hypotheses. This circumstance reinforces the need to understand HBIM not as a closed
representation of the past, but as an open interpretative platform capable of evolving as
new evidence is incorporated [37,40].
Overall, the discussion confirms that the main contribution of this work lies in the
formulation of a replicable and transparent methodological framework for multitemporal
HBIM modeling applied to complex heritage buildings. By explicitly integrating strati-
graphic reasoning, documentary analysis, reality-based geometry and uncertainty manage-
ment, the proposed approach contributes to narrowing the gap between digital modeling
practices and rigorous historical research. In doing so, HBIM is consolidated not merely
as a tool for documenting or managing the built heritage, but as a methodological frame-
work capable of articulating historical analysis, stratigraphic reasoning and temporal
simulation, fostering a critical, dynamic and scientifically grounded understanding of
historical architecture.
Beyond the specific case study, the proposed workflow highlights the potential of
multitemporal HBIM modelling as an interpretative framework for complex heritage
buildings characterised by stratification and successive transformations. Rather than
treating historical phases as static attributes, the approach structures them as an integral
dimension of the model, enabling the coherent correlation of geometry, documentary
sources and interpretative assessments. This perspective extends conventional HBIM
practices by emphasising diachronic analysis and supporting the management of historical
complexity within a single, structured digital environment.
At the same time, the proposed workflow presents a number of methodological
constraints that must be acknowledged. Its effectiveness is strongly dependent on the avail-
ability and quality of documentary, stratigraphic and geometric data, and its application
becomes more speculative in data-scarce or highly hypothetical contexts, such as early
or poorly preserved construction phases. While the approach shows clear potential for
supporting heritage monitoring, comparative analysis and virtual restoration scenarios, its
scalability to large and highly complex heritage ensembles requires careful management
of information density, modelling effort and interoperability. These limitations highlight
current technical bottlenecks, particularly regarding uncertainty management and the inte-
gration of independent archaeological and diagnostic data, which constitute key directions
for future methodological development.

\6. Conclusions

This study has demonstrated the capacity of HBIM to function as an effective method-
ological framework for reconstructing and managing the historical evolution of heritage
buildings characterised by complex construction sequences. Through the case study of
the Church of La Sang in Llíria, it has been shown that the integration of reality-based
geometry, documentary analysis and stratigraphic reading enables the temporal dimension
of the built heritage to be structured coherently within a single digital environment.
The main contribution of the research lies in the proposal of a multitemporal HBIM
workflow in which historical phases are incorporated as structural components of the
information model and associated, within the HBIM environment, with material evidence,
documentary sources and interpretative hypotheses. This approach enhances traceabil-
ity, transparency and critical review of historical reconstructions, addressing one of the
principal limitations identified in the recent literature on HBIM applied to heritage.
The results confirm that geometry derived from terrestrial laser scanning not only
ensures the metric accuracy of the model but also supports historical analysis by reveal-
ing geometric irregularities relevant to the interpretation of construction sequences and

https://doi.org/10.3390/heritage9020068

<!-- p. 23 -->

Heritage 2026, 9, 68 23 of 26

architectural reuse processes. Likewise, the integration of building archaeology criteria
within the HBIM environment reinforces the analytical nature of the model and its ability
to address phases with different degrees of certainty.
The generated documentary archive is configured as an evolutionary or “living”
model, with the potential to incorporate new information derived from archaeological
investigations, conservation interventions or monitoring processes over time. In this sense,
the proposed approach goes beyond the visualisation of the past and provides an operative
support for the future management of the heritage asset and for informed decision-making
in conservation and restoration contexts.
Regarding future research directions, the study opens several promising avenues.
First, the proposed methodology could be expanded through the incorporation of data
derived from systematic archaeological excavations, archaeometric analyses or absolute
dating techniques, allowing the refinement of chronological hypotheses and increasing the
reliability of the earliest phases of the model. Second, the integration of multitemporal
HBIM with GIS or HGIS environments would facilitate the analysis of the building in
relation to its urban and territorial context, enabling the study of transformation processes
at a broader spatial scale.
Further research could also explore the integration of structural and environmental
monitoring systems within the HBIM model, advancing towards heritage digital twin
configurations oriented to preventive conservation and long-term performance assessment.
Another relevant line of work would involve the development of standardised protocols
for the explicit representation of uncertainty, chronological ranges and reliability levels
in historical HBIM models, contributing to the consolidation of shared methodological
standards in the field of digital heritage.
This research demonstrates how a multitemporal HBIM approach can support the
documentation, interpretation and management of complex historic buildings through the
structured integration of geometric, historical and interpretative information. Applied to
the Church of La Sang, the workflow enables the reconstruction and comparison of different
historical phases while maintaining geometric consistency and transparency of sources.
Although the proposed methodology does not aim to provide exhaustive constructive or
material analyses, it offers a replicable framework for addressing the diachronic dimension
of heritage assets and contributes to ongoing discussions on the role of HBIM in heritage
knowledge management.

Author Contributions: Conceptualization, I.O.-F.; methodology, I.O.-F., M.E.T.-F. and E.B.-V.; soft-
ware, S.M.S.; validation I.O.-F. and S.M.S., formal analysis I.O.-F., M.E.T.-F. and E.B.-V.; investigation,
I.O.-F., M.E.T.-F. and E.B.-V.; data curation, I.O.-F. and S.M.S.; writing—original draft preparation,
I.O.-F., M.E.T.-F. and E.B.-V.; writing—review and editing, I.O.-F., M.E.T.-F. and E.B.-V.; visualization,
I.O.-F. and S.M.S. All authors have read and agreed to the published version of the manuscript.

Funding: This research received no external funding.

Data Availability Statement: The original contributions presented in the study are included in the
article; further inquiries can be directed to the corresponding author.

Conflicts of Interest: The authors declare no conflicts of interest.

https://doi.org/10.3390/heritage9020068

<!-- p. 24 -->

Heritage 2026, 9, 68 24 of 26

Abbreviations

The following abbreviations are used in this manuscript:

HBIM Heritage Building Information Modeling
2D Bidimensional representation
3D Tridimensional representation
LOA Level of Accuracy
LOI Level of Information
BIM Building Information Modeling
GIS Geographic Information System
HGIS Historical Geographic Information System
IFC-SHP Industry Foundation Classes—Shapefile
ISO International Organization for Standardization
EIR Exchange Information Requirements
BEP BIM Execution Plan
RIBA Royal Institute of British Architects
LOD Level of Development
SEO Solid Element Operations
ID Identifier

References

\1. Murphy, M.; Mcgovern, E.; Pavia, S. Historic building information modelling (HBIM). Struct. Surv. 2009, 27, 311–327. [CrossRef]
\2. Dore, C.; Murphy, M. Current state of the art historic building information modelling. Int. Arch. Photogramm. Remote Sens. Spat.
Inf. Sci. 2017, XLII-2-W5, 185–192. [CrossRef]
\3. Pepe, M.; Ackermann, S.; Fregonese, L.; Achille, C. New perspectives of point clouds color management—The development of
tool in Matlab for applications in cultural heritage. Int. Arch. Photogramm. Remote Sens. Spat. Inf. Sci. 2017, XLII-2-W3, 567–571.
[CrossRef]
\4. Liu, J.; Azhar, S.; Willkens, D.; Li, B. Static Terrestrial Laser Scanning (TLS) for Heritage Building Information Modeling (HBIM):
A Systematic Review. Virtual Worlds 2023, 2, 90–114. [CrossRef]
\5. Bruno, S.; De Fino, M.; Fatiguso, F. Historic Building Information Modelling: Performance assessment for diagnosis-aided
information modelling and management. Autom. Constr. 2018, 86, 256–276. [CrossRef]
\6. Martinelli, L.; Calcerano, F.; Gigliarelli, E. Methodology for an HBIM workflow focused on the representation of construction
systems of built heritage. J. Cult. Herit. 2022, 55, 277–289. [CrossRef]
\7. Costa, A.P.; Cuperschmid, A.R.M.; Neves, L.O. HBIM and BEM association: Systematic literature review. J. Cult. Herit. 2024, 66,
551–561. [CrossRef]
\8. Roggio, D.S.; Shokrollahi, S.; Forte, A.; Bitelli, G. Exploring Historical Changes to Architectural Heritage Through Reality-Based
3D Modeling and Virtual Reality: A Case Study. ISPRS Int. J. Geo-Inf. 2025, 14, 353. [CrossRef]
\9. Hamed, W.; El Antably, A. Knowledge-based HBIM for conservation: The case of Yahya al-Shabih mausoleum. Digit. Appl.
Archaeol. Cult. Herit. 2023, 30, e00278. [CrossRef]
\10. Salah, R.; Károlyfi, K.A.; Szép, J.; Géczy, N. A structured framework for HBIM standardization: Integrating scan-to-BIM
methodologies and heritage conservation standards. Digit. Appl. Archaeol. Cult. Herit. 2025, 37, e00420. [CrossRef]
\11. Angulo-Fornos, R.; Castellano-Román, M. HBIM as Support of Preventive Conservation Actions in Heritage Architecture.
Experience of the Renaissance Quadrant Façade of the Cathedral of Seville. Appl. Sci. 2020, 10, 2428. [CrossRef]
\12. Franczuk, J.; Koszewski, K. Algorithmic Design in Architectural Heritage: Innovation in Virtual Reconstruction of the Roman
Forum Transitorium in Musti, Tunisia. Heritage 2025, 8, 362. [CrossRef]
\13. Aparicio, L.J.S.; Del Blanco García, F.L.; Talaverano, R.M.; Klapa, P.; Pepe, M. 3D Heritage Reconstruction Through HBIM and
Multi-Source Data Fusion: Geometric Change Analysis Across Decades. Appl. Sci. 2025, 15, 8929. [CrossRef]
\14. Ma, Y.; Tong, Q.; He, X.; Su, B. Exploring virtual restoration of architectural heritage through a systematic review. npj Herit. Sci.
2025, 13, 167. [CrossRef]
\15. Chiabrando, F.; Turco, M.L.; Rinaudo, F. Modeling the decay in an HBIM starting from 3D point clouds. A followed approach for
cultural heritage knowledge. Int. Arch. Photogramm. Remote Sens. Spat. Inf. Sci. 2017, XLII-2-W5, 605–612. [CrossRef]

https://doi.org/10.3390/heritage9020068

<!-- p. 25 -->

Heritage 2026, 9, 68 25 of 26

\16. Jordan-Palomar, I.; Tzortzopoulos, P.; García-Valldecabres, J.; Pellicer, E. Protocol to Manage Heritage-Building Interventions
Using Heritage Building Information Modelling (HBIM). Sustainability 2018, 10, 908. [CrossRef]
\17. Talaverano, R.M.; Fragero, J.I.M.; De los Ángeles Utrero Agudo, M. Reflexiones y criterios relativos a la creación de modelos BIM
de edificios históricos. Arqueol. Arquit. 2021, 18, e113. [CrossRef]
\18. Hu, Y.; Gao, B.; Chen, H. Application of 4D Technologies in Heritage: A Comprehensive Review. Buildings 2025, 15, 4369.
[CrossRef]
\19. Tallon, A. Divining Proportions in the Information Age. Archit. Hist. 2014, 2, 15. [CrossRef]
\20. Alshawabkeh, Y.; Baik, A.; Miky, Y. HBIM for Conservation of Built Heritage. ISPRS Int. J. Geo-Inf. 2024, 13, 231. [CrossRef]
\21. Šmit, Ž.; Menart, E. Special Issue of ‘Material Analysis in Cultural Heritage’. Materials 2023, 16, 2370. [CrossRef]
\22. Colucci, E.; Murtiyoso, A.D.; Raed, A.A.; Quist, W.; Pottgiesser, U. Preserving Modern Heritage in the Emirate of Dubai: A Digital
Documentation and Semantic HBIM Approach. Heritage 2025, 8, 263. [CrossRef]
\23. Dionizio, R.F.; Dezen-Kempter, E. HBIM-HGIS for a multi-level knowledge-based approach. Digit. Appl. Archaeol. Cult. Herit.
2025, 39, e00461. [CrossRef]
\24. Messaoudi, T.; Véron, P.; Halin, G.; De Luca, L. An ontological model for the reality-based 3D annotation of heritage building
conservation state. J. Cult. Herit. 2018, 29, 100–112. [CrossRef]
\25. Fai, S.; Sydor, M. Building Information Modelling and the documentation of architectural heritage: Between the ‘typical’ and
the ‘specific’. In Digital Heritage 2013—Federating the 19th Int’l VSMM, 10th Eurographics GCH, and 2nd UNESCO Memory of the
World Conferences, Plus Special Sessions from CAA, Arqueologica 2.0, et al.; IEEE: New York, NY, USA, 2013; Volume 1, pp. 731–734.
[CrossRef]
\26. Banfi, F.; Brumana, R.; Landi, A.G.; Previtali, M.; Roncoroni, F.; Stanga, C. Building archaeology informative modelling turned
into 3D volume stratigraphy and extended reality time-lapse communication. Virtual Archaeol. Rev. 2022, 13, 1–21. [CrossRef]
\27. INCEPTION|Home. Available online: https://www.inception-project.eu/en (accessed on 15 January 2026).
\28. Brumana, R.; Dellatorre, S.; Oreni, D.; Previtali, M.; Cantini, L.; Barazzetti, L.; Franchi, A.; Banfi, F. HBIM challenge among the
paradigm of complexity, tools and preservation: The basilica di collemaggio 8 years after the earthquake (L’aquila). Int. Arch.
Photogramm. Remote Sens. Spat. Inf. Sci. 2017, XLII-2-W5, 97–104. [CrossRef]
\29. Logothetis, S.; Delinasiou, A.; Stylianidis, E. Building Information Modelling for Cultural Heritage: A review. ISPRS Ann.
Photogramm. Remote Sens. Spat. Inf. Sci. 2015, II-5-W3, 177–183. [CrossRef]
\30. ISO 19650-1:2018; Organization and Digitization of Information About Buildings and Civil Engineering Works, Includ-
ing Building Information Modelling (BIM)—Information Management Using Building Information Modelling—Part 1:
Concepts and Principles. International Organization for Standardization: Geneva, Switzerland, 2018. Available online:
https://www.iso.org/standard/68078.html (accessed on 15 December 2025).
\31. BIM Execution Planning Guide|BIM Planning. Available online: https://bim.psu.edu/downloads/ (accessed on 15 December 2025).
\32. Masciotta, M.G.; Sanchez-Aparicio, L.J.; Oliveira, D.V.; Gonzalez-Aguilera, D. Integration of Laser Scanning Technologies and
360o Photography for the Digital Documentation and Management of Cultural Heritage Buildings. Int. J. Archit. Herit. 2023, 17,
56–75. [CrossRef]
\33. RIBA Plan of Work 2020 Overview RIBA Plan of Work. 2020. Available online: www.ribaplanofwork.com (accessed on 15
December 2025).
\34. Losè, L.T.; Murtiyoso, A.D.; Horkai, A. From Archives to 3D Models: Managing Uncertainty with Paradata in Virtual Heritage.
Heritage 2025, 8, 441. [CrossRef]
\35. Mazzei, A.; Martinelli, L.; Empler, T.; Cessari, L.; Gigliarelli, E. Modelling for uncertainty in HBIM processes. Vitr.-Int. J. Archit.
Technol. Sustain. 2024, 9, 22093. [CrossRef]
\36. Hermon, S.; Niccolucci, F.; Bakirtzis, N.; Gasanova, S. A Heritage Digital Twin ontology-based description of Giovanni Baronzio’s
‘Crucifixion of Christ’ analytical investigation. J. Cult. Herit. 2024, 66, 48–58. [CrossRef]
\37. Penjor, T.; Banihashemi, S.; Hajirasouli, A.; Golzad, H. Heritage building information modeling (HBIM) for heritage conservation:
Framework of challenges, gaps, and existing limitations of HBIM. Digit. Appl. Archaeol. Cult. Herit. 2024, 35, e00366. [CrossRef]
\38. Chiabrando, F.; Sammartano, G.; Spanò, A. Historical buildings models and their handling via 3D survey: From points clouds to
user-oriented HBIM. Int. Arch. Photogramm. Remote Sens. Spat. Inf. Sci. 2016, XLI–B5, 633–640. [CrossRef]
\39. Ávila, F.; Blanca-Hoyos, Á.; Puertas, E.; Gallego, R. HBIM: Background, Current Trends, and Future Prospects. Appl. Sci. 2024,
14, 11191. [CrossRef]
\40. Lombardi, M.; Rizzi, D. Semantic modelling and HBIM: A new multidisciplinary workflow for archaeological heritage. Digit.
Appl. Archaeol. Cult. Herit. 2024, 32, e00322. [CrossRef]
\41. Niccolucci, F.; Felicetti, A. Digital Twin Sensors in Cultural Heritage Ontology Applications. Sensors 2024, 24, 3978. [CrossRef]

https://doi.org/10.3390/heritage9020068

<!-- p. 26 -->

Heritage 2026, 9, 68 26 of 26

\42. Gabriele, M.; Previtali, M. HBIM-GIS integration with an IFC-to-shapefile approach: The palazzo trotti vimercate pilot case study.
ISPRS Ann. Photogramm. Remote Sens. Spat. Inf. Sci. 2021, VIII-4-W2-2021, 167–174. [CrossRef]
\43. López-Ortiz, E.; García-Jiménez, I.; Dong, J.; Pineda, P. A multi-scale stratigraphic HBIM-GIS method for the characterization of
structures in heritage sites. J. Cult. Herit. 2025, 76, 357–372. [CrossRef]

Disclaimer/Publisher’s Note: The statements, opinions and data contained in all publications are solely those of the individual
author(s) and contributor(s) and not of MDPI and/or the editor(s). MDPI and/or the editor(s) disclaim responsibility for any injury to
people or property resulting from any ideas, methods, instructions or products referred to in the content.

https://doi.org/10.3390/heritage9020068
