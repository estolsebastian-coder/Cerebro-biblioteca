---
type: libro
title: "Scan-to-HBIM-to-BA-to-FEM workflow for structural interventions: Integrating HBIM, building archaeology, and structural analysis to preserve archaeological remains"
author: "Fabrizio Banfi"
categoria: "Tecnología láser, fotogrametría, otros"
paginas: 15
extraccion: "texto"
fuente: "local:E:/DISCIPLINAS, TEXTOS Y MAPAS/Biblioteca digital/Tecnología láser, fotogrametría, otros/Scan-to-HBIM-to-BA-to-FEM workflow for structural interventions.pdf"
convertido: 2026-10-14
---

# Scan-to-HBIM-to-BA-to-FEM workflow for structural interventions: Integrating HBIM, building archaeology, and structural analysis to preserve archaeological remains

> Texto extraído de `Tecnología láser, fotogrametría, otros/Scan-to-HBIM-to-BA-to-FEM workflow for structural interventions.pdf` (15 páginas, texto). El PDF original está en el disco E: (DISCIPLINAS, TEXTOS Y MAPAS\Biblioteca digital); `<!-- p. N -->` marca el inicio de cada página.

<!-- p. 1 -->

Journal of Cultural Heritage 82 (2026) 250–264

Contents lists available at ScienceDirect

Journal of Cultural Heritage

journal homepage: www.elsevier.com/locate/culher

Original article

Scan-to-HBIM-to-BA-to-FEM workﬂow for structural interventions:
Integrating HBIM, building archaeology, and structural analysis to
preserve archaeological remains

Fabrizio Banﬁa ,∗, Alberto Viskovic b, Libbio Antonelli c, Francesca Romana Paolillo f,
Clara Spallino d, Marta De Pari e, Stefano Roascio d

a Politecnico di Milano, Italy
b University G. D’Annunzio Chieti-Pescara, Italy
c Society Arcsema Ingegneria Srl, Trasacco, L’Aquila, Italy
d Appia Antica Archaeological Park, Ministry of Culture, Rome, Italy
e Sapienza Università di, Roma, Italy
f Soprintendenza Archeologia, belle arti e paesaggio per la città metropolitana di Bari, Bari, Italy

a r t i c l e i n f o a b s t r a c t

Article history: The conservation of archaeological heritage requires robust digital approaches capable of managing fragReceived 3 August 2025 mented geometries, stratiﬁed structures, and heterogeneous materials while supporting reliable structural
Accepted 15 September 2026 assessment. Despite the growing adoption of Heritage Building Information Modelling (HBIM), its integra-
tion with ﬁnite element analysis (FEM) remains limited by fragmented workﬂows and weak interoperabilKeywords: ity between modelling and simulation environments. This study introduces an integrated scan-to-HBIMHeritage building information modelling BA-FEM workﬂow that explicitly incorporates Building Archaeology (BA) as a rule-based interpretative
(HBIM) framework. Unlike conventional approaches, BA is not treated as a descriptive layer but as a generative
Scan-to-HBIM-to-BA-FEM system that informs geometric reconstruction, semantic structuring, and structural idealization. This enPreservation ables the development of HBIM models that preserve both metric accuracy and historical–constructive coBuilding archaeology
herence, while ensuring consistency in their transfer to FEM environments. The methodology is validated
Finite element method (FEM)
Structural intervention through its application to the Villa dei Quintili archaeological site (Rome), a complex case characterized
by irregular morphologies and multi-phase stratigraphy. The results demonstrate improved interoperabil-
ity, increased geometric reliability, and more consistent structural assessments, supporting the identiﬁ-
cation of critical structural behaviours and intervention strategies. Although surrogate modelling was not
implemented, in order to maintain direct traceability between survey data, archaeological interpretation,
and numerical modelling, its future integration is identiﬁed as a key direction for enhancing parametric
analyses and decision-making processes. The proposed workﬂow advances digital heritage practices by
bridging the gap among documentation, interpretation, and structural analysis, offering a scalable, inter-
disciplinary framework for the conservation of complex archaeological remains.
© 2026 The Authors. Published by Elsevier Masson SAS. This is an open access article under the CC
BY-NC-ND license ( http://creativecommons.org/licenses/by-nc-nd/4.0/ )

\1. Introduction emerged as a key approach, integrating geometric, material, and
semantic data within a uniﬁed environment to support conserva1.1. Advancements and challenges in integrating HBIM, building tion and management processes [ 1–5 ]. Its development has been
archaeology and FEM for archaeological site preservation reinforced by improved surveying techniques, such as Terrestrial
Laser Scanning and photogrammetry, and by the adoption of stan-
Recent advances in digital technologies have signiﬁcantly trans- dards, including Industry Foundation Classes (IFC) and ISO 19650
formed the documentation, analysis, and preservation of cul- [ 6–8 ]. Despite these advancements, applying HBIM to archaeotural heritage. Heritage Building Information Modeling (HBIM) has logical contexts remains challenging. Archaeological remains are

∗Corresponding author.
E-mail addresses: fabrizio.banﬁ@polimi.it (F. Banﬁ), alberto.viskovic@unich.it (A. Viskovic), antonelli.libbio@tiscali.it (L. Antonelli), francescaromana.paolillo@cultura.gov.it
(F.R. Paolillo), clara.spallino@cultura.gov.it (C. Spallino), epari.2028071@studenti.uniroma1.it (M. De Pari), stefano.roascio@cultura.gov.it (S. Roascio) .

https://doi.org/10.1016/j.culher.2026.09.008
1296-2074/© 2026 The Authors. Published by Elsevier Masson SAS. This is an open access article under the CC BY-NC-ND license
( http://creativecommons.org/licenses/by-nc-nd/4.0/ )

<!-- p. 2 -->

F. Banﬁ, A. Viskovic, L. Antonelli et al. Journal of Cultural Heritage 82 (2026) 250–264

typically characterized by irregular geometries, stratigraphic com- ric ﬁdelity but signiﬁcantly raise computational costs, whereas
plexity, discontinuities, and material degradation, which are diﬃ- coarse grids may oversimplify interfaces, discontinuities, and concult to represent using conventional BIM logic based on standard- struction details that are structurally relevant. Methods such as
ized components [ 9–11 ]. These issues also affect interoperability CLOUD2FEM and its applications [ 38 ] reduce user intervention but
with Finite Element Method (FEM) analysis—essential for structural depend strongly on grid resolution and mesh quality [ 39 ].
assessment—often leading to fragmented workﬂows, semantic in- Retopology, by contrast, is the process of reorganising a highconsistencies, and unreliable simulation results [ 12 , 13 ]. density polygonal mesh into a simpliﬁed and topologically coher-
To address these limitations, this study proposes an inte- ent surface while preserving the overall morphology of the surgrated Scan-to-HBIM-to-BA-to-FEM workﬂow in which Building Ar- veyed object. The resulting mesh is computationally more eﬃcient
chaeology (BA) serves as a central interpretative and generative and better suited for numerical simulations, reducing the complexframework [ 14–19 ]. By incorporating stratigraphic and construc- ity of the original scan data. However, retopology primarily optitive knowledge into the modelling process, BA supports the trans- mises geometric representation and does not inherently preserve
formation of fragmented survey data into historically and struc- semantic information, such as construction phases, material stratiturally meaningful digital models, improving both semantic coher- ﬁcation, or archaeological interpretation. Consequently, additional
ence and analytical reliability. The proposed approach introduces modelling steps are generally required before the model can be
three main contributions: (i) the use of BA to guide segmentation integrated into an HBIM environment or used for structurally inand semantic structuring; (ii) the integration of NURBS-based ge- formed analyses.
ometries within HBIM without reducing modelling to purely ge- Retopology improves mesh usability and computational eﬃometric conversion; and (iii) a controlled interoperability strategy ciency [ 40 , 41 ], yet often lacks the semantic depth required for
that prepares HBIM models for FEM analysis while preserving ge- HBIM-based interpretation and requires extensive preprocessing.
ometric and construction-related information. The methodology is In this context, the choice of geometric representation is critvalidated through its application to the Villa dei Quintili archaeo- ical. Voxel models offer eﬃciency but may oversimplify interlogical site (Rome), demonstrating improved HBIM–FEM interoper- faces; mesh models preserve geometry but are semantically limability, enhanced data reliability, and a more robust framework for ited; whereas NURBS-based modelling enables a controlled tranthe structural assessment and conservation of complex archaeolog- sition from survey data to semantically structured HBIM objects,
ical remains. preserving continuity with archaeological interpretation and FEM
idealization. Unlike voxel- or mesh-based approaches, NURBS pro1.2. Theoretical framework: from HBIM to FEM for built heritage vide mathematically continuous surfaces that can be directly trans-
formed into semantically enriched HBIM objects while maintaining
Finite Element Analysis (FEA), based on the FEM, is widely used geometric control throughout the interoperability process. For this
to simulate the physical behaviour of complex systems in engineer- reason, the present study adopts a NURBS-centered workﬂow.
ing [ 20 , 21 ]. Its application requires discretizable structural models Recent reviews conﬁrm both the diversity of approaches and
suitable for meshing, boundary conditions, and material character- the lack of comprehensive solutions for archaeological applications.
ization. Consequently, the scan-to-FEM transition depends not only Turchetti et al. [ 42 ] reviewed 84 methodologies for generating FE
on survey accuracy but also on the conversion of reality-based ge- models from point clouds, highlighting their accuracy, computaometries into mathematically consistent representations. FEA sup- tional eﬃciency, and reliability [ 43 ], as well as the potential role
ports linear and nonlinear static and dynamic analyses, including of AI in future automation.
seismic pushover simulations [ 22 , 23 ], although advanced nonlin- At the same time, recent studies on failure analysis, structural
ear approaches remain limited by computational cost and lack of vulnerability, and numerical modelling of heritage masonry further
standardization. stress the need for robust and context-sensitive workﬂows, includ-
Since 2014, HBIM has increasingly been applied to structural ing FEM- and DEM-based approaches applied to archaeological and
assessment in heritage contexts. Case studies such as the Basil- monumental case studies [ 44–46 ].
ica of Collemaggio and Masegra Castle demonstrate the potential Within this framework, Building Archaeology (BA) becomes esof Cloud-to-BIM-to-FEM workﬂows to integrate survey data, diag- sential. While HBIM can represent phases, materials, and transnostics, and structural modelling while accommodating geomet- formations in standing historic buildings, archaeological remains
ric irregularities [ 24 , 25 ]. However, these workﬂows remain largely require an interpretative framework that addresses discontinuity,
project-speciﬁc rather than standardized. Similarly, point-cloud- collapse, stratigraphic superposition, and the partial loss of conbased FEM modelling has proven effective [ 26 , 27 ], yet challenges structive logic [ 47 , 48 ]. Unlike conventional HBIM workﬂows, where
persist due to irregular geometries, collapse, and material decay semantic information is mainly associated with predeﬁned build-
[ 28 ], while low-resolution or semantically poor models may lead ing components, BA provides the archaeological criteria needed to
to unreliable results [ 29 , 30 ]. identify stratigraphic units, construction phases, reused masonry,
These limitations are more pronounced in archaeological con- material interfaces, and structural discontinuities directly from the
texts, where fragmentary remains, discontinuous stratigraphy, and survey data. BA provides historical construction knowledge, stratimaterial deterioration hinder the direct application of standard graphic reading, and material interpretation, enabling the transforBIM-to-FEM workﬂows [ 10 , 28 , 31–33 ]. The reconstruction of incom- mation of raw point-cloud data into semantically rich and historplete structures often requires signiﬁcant interpretative input. ically grounded HBIM models [ 18 , 49 , 50 ]. These archaeological in-
Several approaches address these issues [ 34–37 ]. Voxelisation is terpretations do not simply enrich the HBIM model but actively
a geometric discretisation technique that converts a point cloud or guide its generation, determining how complex remains are segsurface model into a regular three-dimensional grid composed of mented, classiﬁed, and converted into semantic objects suitable
volumetric cells (voxels). Each voxel represents a ﬁnite portion of for structural idealisation. For example, at the Villa dei Quintili,
the surveyed object and can be directly assigned material prop- BA enabled the distinction between Hadrianic, Antonine, and Severties, enabling the automatic generation of ﬁnite-element models eran construction phases, the identiﬁcation of masonry interfaces
without requiring explicit surface reconstruction. This approach is characterised by different constructive techniques, and the recogparticularly effective for highly irregular archaeological geometries; nition of structurally signiﬁcant discontinuities that were subsehowever, the geometric accuracy of the resulting model strongly quently considered during FEM modelling. In this way, BA bridges
depends on voxel resolution. Fine voxel grids increase geomet- the gap between geometric ﬁdelity and structural interpretability.

251

<!-- p. 3 -->

F. Banﬁ, A. Viskovic, L. Antonelli et al. Journal of Cultural Heritage 82 (2026) 250–264

The workﬂows compared in Table 1 differ in geometric input, se- fer primarily in the way geometric representations are transformed
mantic enrichment, and the level of remodelling required for FEM into analytical structural models and in the amount of semanimplementation. The proposed HBIM-BA-FEM workﬂow is selected tic information preserved during this process. It also clariﬁes why
because it offers a balanced integration of geometric control, ar- the proposed methodology combines NURBS-based modelling with
chaeological interpretability, and structural transferability for irreg- Building Archaeology, since this conﬁguration provides a balanced
ular Roman ruins. Rather than serving as an additional documen- integration of geometric accuracy, archaeological interpretation, setation layer, BA acts as the interpretative framework that links sur- mantic enrichment and structural transferability for complex Rovey data, semantic modelling, and structural analysis, ensuring that man archaeological remains.
the FEM model reﬂects not only the geometry of the remains but
also their historical and constructive evolution. Its applicability is 1.3. Research aims
particularly relevant where fragmentary remains, complex stratigraphic relationships, and structural discontinuities cannot be reli- This research aims to develop and test an archaeologically inably modelled using purely typological or library-based HBIM pro- formed scan-to-HBIM-to-BA-to-FEM workﬂow for the structural ascedures. sessment of complex Roman ruins. The proposed methodology is
Existing HBIM-to-FEM workﬂows differ not only in the software intended to bridge three gaps commonly found in current scanadopted but also in the geometric representation used to describe to-HBIM-to-FEM applications: (i) the limited semantic integration
the structure. Point-cloud-based approaches generally require sur- of archaeological interpretation into digital modelling; (ii) the difface reconstruction or voxelization before meshing, whereas mesh- ﬁculty of transferring irregular and stratiﬁed geometries into FEM
based workﬂows preserve geometric ﬁdelity but usually lack se- environments without excessive remodelling; and (iii) the lack of
mantic information associated with construction phases and mate- a transparent workﬂow linking survey data, semantic enrichment,
rials. Parametric BIM workﬂows facilitate the assignment of struc- and structural evaluation. The originality of the research lies in intural attributes but often require signiﬁcant simpliﬁcation when ir- tegrating BA into both the generative and interpretative stages of
regular archaeological geometries are involved. Conversely, NURBS- the workﬂow, thereby linking survey-based geometric reconstrucbased workﬂows maintain mathematical continuity of free-form tion to stratigraphic reading, material characterization, and strucsurfaces while allowing their conversion into semantically enriched tural idealization. The Villa dei Quintili case study is used to test
HBIM objects, which can subsequently be idealized for FEM analy- the workﬂow in archaeologically and structurally complex areas,
ses. During this transition, interoperability is achieved through dif- namely the frigidarium and calidarium, to assess its effectiveness,
ferent strategies depending on the adopted workﬂow. Some ap- limitations, and reproducibility ( Fig. 1 ).
proaches transfer only geometric information, requiring the struc- Accordingly, the study addresses the following research objectural model to be manually reconstructed within the FEM environ- tives:
ment, whereas others preserve both geometry and selected semantic attributes (e.g., material assignment, structural typology or el- (1) To deﬁne a scan-to-HBIM modelling strategy suitable for irement hierarchy) through interoperable formats or dedicated in- regular archaeological remains.
terfaces. In most heritage applications, however, the HBIM model (2) To structure HBIM information according to archaeological
cannot be directly analysed: it must ﬁrst be transformed into an and structural requirements.
analytical structural model by simplifying non-structural compo- (3) To transfer the resulting model into a FEM environment
nents, idealising complex geometries, deﬁning structural connec- with controlled geometric and semantic loss; and
tions, assigning mechanical properties and generating a computa- (4) To evaluate how this integration supports structural diagnotional mesh suitable for numerical simulation. Consequently, in- sis and intervention design.
teroperability should be understood not merely as ﬁle exchange
but as the controlled transformation of both geometric and se- 2. Material and methods
mantic information into a structurally consistent analytical model.
Consequently, interoperability depends not only on ﬁle exchange 2.1. The case study: architectural and historical signiﬁcance of the
formats (e.g., IFC, IGES or SAT) but also on the capability of the Villa dei Quintili
adopted representation to preserve both geometric accuracy and
construction-related information throughout the modelling and The Villa dei Quintili, located at the ﬁfth mile of the Via Appia
structural simulation process. Table 1 summarizes these interop- Antica, is a prominent example of Roman architectural grandeur.
erability strategies according to the adopted geometric representa- Built in the early 2nd century AD by the senatorial brothers
tion, data transfer mechanism, semantic content, and level of geo- Sesto Quintilio Condiano and Sesto Quintilio Valerio Massimo, the
metric remodelling required before structural analysis. Rather than complex featured extensive pavilions, marble interiors, and highclassifying workﬂows solely according to the software employed, quality materials from imperial quarries. Its history changed drathe comparison emphasizes how different geometric representa- matically when the brothers were accused of conspiring against
tions (point clouds, meshes, NURBS or parametric BIM objects) in- Emperor Commodus, leading to the conﬁscation of the estate.
ﬂuence the generation of the analytical FEM model, the amount Over time, the villa declined, was looted, and lost many of its
of manual remodelling required, and the preservation of geomet- original artifacts. Early excavations in the 18th and 19th centuries
ric and semantic information during the HBIM-to-FEM transition. revealed important artworks, although the architectural underThe proposed workﬂow was selected because it minimizes geo- standing remained limited. Scholars such as Antonio Nibby, Luigi
metric simpliﬁcations while preserving archaeological interpreta- Canina, and G.B. Guidi recognized its signiﬁcance, but key aspects—
tion and semantic consistency during the transition from survey particularly its stratigraphy—remained unclear. Further discoveries
data to FEM. were made during land reclamation works in the Agro Romano
The workﬂows summarised in Table 1 are derived from repre- (1922–1932), though some areas were damaged.
sentative approaches reported in the literature rather than from a More systematic research began in the 1980s under Andreina
purely theoretical classiﬁcation. Although individual studies may Ricci (University of Tor Vergata), followed by excavation campaigns
combine multiple modelling strategies, the comparison identiﬁes between 1998 and 2018. These investigations revealed a complex
the dominant interoperability approach adopted in each workﬂow. layout, including pavilions with baths, libraries, gymnasia, and porThis synthesis highlights that current HBIM-to-FEM pipelines dif- ticoed courtyards. The richness of its decorative elements—mosaics,

252

<!-- p. 4 -->

F. Banﬁ, A. Viskovic, L. Antonelli et al. Journal of Cultural Heritage 82 (2026) 250–264

the
STL STEP, DWG, OBJ,
SAT, DXF, STL, SAT, 3DM, IGES mechanism, DXF, SAT, XYZ, SAF, PLY, IFC, Formats
SAF, E57, IGES DWG, STL, MSH RVT, transfer DWG, STEP Exchange IFC, IGES, IFC, XML PTS, STEP, IFC, OBJ, IGES, 3DM,

/ BIM HBIM-to-FEM + Ansys workﬂow. / SCIA Tekla/ Ansys Code_Aster SCIA typical each / RFEM/ Gmsh, SAP2000, Gen, the of / / FEA Robot Multiphysics Rhino, (BIM); Midas / Extensions / AutoConverter HyperMesh MIDAS CloudCompare,
/ SCIA Grasshopper Add-ins Designer / Blender, COMSOL / + / / Dynamo Archicad Abaqus, SOFiSTiK Revit representation, limitationsand Revit,

/ + +
Revit Straus7, Engineer Revit Archicad interfaces MeshLab, Mechanical Rhino, Engineer Structural 3DReshaper, Abaqus LS-DYNA Revit Software geometric advantages
dominant principal FEM and deﬁnition complex HBIM expertise the the ineﬃcient handling validation with with archaeology, on and software/plugins heavy load be
detail may experimental of modeling inconsistency information focuses analysis, = FEM struggles information
still interdisciplinary modelling, double compatible geometry material/property model loss careful data FEM) automation of computational property/material interoperability + semantic semantic comparison structural Requires Low Risk Requires Complex High No Diﬃcult Analytic Potential Requires Automation No Poor Low Workﬂow Requires The Cons - (BIM - - - - models - - - - - - - geometries - - - environments - non-standardized - (surveying, FEM) before
heritage. in required HBIM built materials historic NURBS for analysis (e.g., to modeling, (e.g., photogrammetric) awareness and data remodelling tools performance direct or patches adopted scan and structures shapes via granular (laser conceptual geometry manual input from NURBS or constructive
of data compatible errors of enables FEM strategies detail complex accuracy accuracy level and simpliﬁcations scan over model between with ﬁdelity modeling the between BIM preliminary existing irregular/organic from historical conversion archaeology transcription approach for for control for consistency workﬂow SOFiSTiK) geometric analytic arbitrary balance morphological geometrichigh interoperability
\+ analysis information, Greater Lightweight Suitable High Faster Reduces High Direct Avoids Good Flexible Suitable Suitable High Very Automatic Building Enhances Pros - - - - - Revit - - - - - - - - buildings) - - interpolation - objects - - FEM
Scan-to-FEM semantic
and Export Manual BIM + Automated Direct + (No with
\+ representative geometric BIM Reconstruction of of FEM Archaeology Model
\+ Model Cloud BIM) As-built BIM BIM overview preservation Type Point (without Building+ of Modeling Meshing
1 Simpliﬁed Detailed FEM Direct FEM Simpliﬁed Scan-to-Mesh Scan-to-HBIM-to-FEM Workﬂow 1. FEM 2. to 3. in 4. FEM 5. Involved) 6. NURBS Table Comparative degree

253

<!-- p. 5 -->

F. Banﬁ, A. Viskovic, L. Antonelli et al. Journal of Cultural Heritage 82 (2026) 250–264

Fig. 1. Flowchart of the proposed scan-to-HBIM-BA-FEM workﬂow. The diagram illustrates the integrated process from data acquisition to structural analysis and intervention
design, highlighting the roles of NURBS-based modelling, Building Archaeology-driven semantic enrichment, and controlled HBIM-to-FEM data transfer for the assessment of
archaeological remains. Source: author F.B.

marble inlays, and polychrome stucco—reﬂects its elite status. No- scan data acquired in FARO .ﬂs format were registered and extable ﬁnds include the statue of Zeus and the herm of Hermes ported as .e57 or .rcs ﬁles for integration into Autodesk ReCap Pro.
Propylaios, now housed in the Antiquarium. The indexed point-cloud project was managed through the .rcp
The elliptical amphitheater, originally conceived as a gymna- environment. NURBS geometries were transferred via DWG-based
sium and later transformed into a garden, exempliﬁes the villa’s schemas and, for FEM integration, via IGES, which proved to be the
architectural adaptability. Additional features, such as the thermal most reliable format for preserving surface continuity and combaths (frigidarium and calidarium) and porticoed gardens, provide plex load-bearing morphologies. IFC was considered as an open
valuable insights into the leisure and lifestyle of the Roman aris- exchange framework for information management, but not as the
tocracy. primary geometry-transfer format for FEM purposes, due to cur-
rent limitations in handling archaeologically irregular and seman-
tically stratiﬁed components.2.2. Software environment, data formats and interoperability
The interoperability framework, therefore, combined open stan-framework
dards and proprietary exchanges in a controlled way, privileging
the preservation of geometry, semantic traceability, and structural The proposed workﬂow was implemented using a sequence
usability over the adoption of a single universal format.of software environments, each selected for the speciﬁc task at
each stage. Survey registration and ﬁrst-level point-cloud optimization were carried out in FARO Scene, while Autodesk Re- 2.3. Advanced digitisation and surveying techniques at Villa dei
Cap Pro was used for point-cloud aggregation, indexing, and Quintili
preparation of the georeferenced project environment. NURBSbased modelling and geometric interpretation were developed in Over the past three years, the Villa dei Quintili has become a
Rhinoceros, where complex archaeological surfaces could be recon- key archaeological context for testing the proposed methodology,
structed through controlled patch generation. The HBIM environ- a, shedding light on its periods of grandeur, adaptation, and transment was implemented in Autodesk Revit, which was used to con- formation. Ongoing interdisciplinary research, driven by advancevert NURBS-derived geometries into parametric and semantically ments in digital technologies and improved data accessibility, conenriched building objects. Structural analyses were carried out in tinues to uncover new aspects of the villa’s historical and cultural
MIDAS FEA, chosen for its capability to manage complex three- signiﬁcance. A variety of surveying methods, including terrestrial
dimensional masonry models and static/dynamic analyses. and aerial photogrammetry, laser scanning, and total station mea-
Regarding data exchange, the workﬂow relied on multiple ﬁle surements, have established a solid foundation for the villa’s digformats according to the speciﬁc interoperability objective. Raw itization, ensuring high-precision recording of topographic and ar-

254

<!-- p. 6 -->

F. Banﬁ, A. Viskovic, L. Antonelli et al. Journal of Cultural Heritage 82 (2026) 250–264

Fig. 2. Plan view of the archaeological site. Left: orthophoto of the area; right: main archaeological structures. Key: a) Residential Sector – Representative Area, b) Residential
Sector – Private Area, c) Service Sector, d) Frigidarium, e) Calidarium, f) Theatre, g) Tepidarium, h) Small Amphitheatre. Right: The site entrance is located at the bottom of
the image. Source: author F.B.

chitectural data. This multidisciplinary approach not only preserves higher density retained in areas characterized by stratigraphic inthe villa’s architectural heritage but also supports future research terfaces, deformations, or structurally signiﬁcant irregularities.
and discoveries.
The survey strategy was designed as an integrated acquisition 2.4. Scan-to-HBIM-to-FEM modelling and interoperability process
system rather than as a simple juxtaposition of techniques. The meets building archeology
total station was used to establish the control network and ensure a common spatial reference; terrestrial laser scanning pro- The scan-to-HBIM phase was structured as a sequence of convided dense metric information for the standing structures; and trolled transformations from survey data to semantically interterrestrial/aerial photogrammetry complemented the dataset in ar- pretable architectural objects. The process included registration,
eas affected by occlusions, surface discontinuities, or limited scan- georeferencing, segmentation, and optimization of point clouds,
ner accessibility. The integration of these sources enabled the re- followed by the extraction of geometrically meaningful portions
duction of data gaps and the improvement of morphological conti- corresponding to structural and archaeological elements. These
nuity in the ﬁnal digital model. data were then used to generate NURBS-based surface models, bet-
Signiﬁcant progress in 3D scanning—achieving resolutions of ter suited than standard parametric families for representing irreg10 0 to 20 0 million points per scan—has enabled the detailed cap- ular Roman masonry and deformed components.
ture of architectural, structural, and natural features, culminat- Data acquired from the FARO scanner (.ﬂs) were processed in
ing in a large-scale photogrammetric campaign. Photogrammetry, FARO Scene, exported to interoperable formats (.e57 or .rcs), and
based on systematic ground-level photography with digital cam- imported into Autodesk ReCap Pro to create a georeferenced .rcp
eras on tripods, has proven invaluable in documenting fragile or project. Within this environment, key elements, such as walls and
inaccessible areas, improving coverage and expanding the scope ﬂoors, were identiﬁed and classiﬁed according to HBIM standards,
of digital recording. The integration of topographic surveys, laser enabling integration with platforms including AutoCAD, Rhino, and
scanning, and photogrammetry has enhanced data-collection ac- Revit. Accurate geo-referencing was ensured through GPS-based tocuracy and optimized workﬂows. The total station established a pographic data.
geodetic control network across the site, achieving a measurement The generative modelling phase addressed challenges related
precision of ±2.0 mm and a scan-target accuracy of ±4.5 mm. This to irregular geometries and structural anomalies. NURBS interpocoordination of techniques minimized errors and streamlined data lation was used to convert high-resolution scans and photogramprocessing. The post-processing phase generated two main out- metric data into HBIM-compatible geometries. As shown in Fig. 3 ,
puts: a georeferenced point-cloud dataset used as the metric ref- this required moving beyond traditional 2D representations toward
erence for modelling, and a textured mesh used mainly for visual surface-based modelling. NURBS were selected for their balance
inspection and interpretative support. Since the textured mesh did between geometric continuity, modelling control, and interopernot provide the semantic and constructive structure required for ability with both HBIM and FEM environments.
HBIM and FEM applications, it was not used directly as the ﬁnal In contrast, textured meshes—although visually detailed—do not
analytical model, but as an intermediate representational support encode constructive logic, stratigraphic segmentation, or material
for identifying discontinuities, surface anomalies, and inaccessible properties, and are therefore not suitable for semantically strucportions of the remains. The resulting dataset provides a robust tured HBIM modelling or FEM idealization. For this reason, mesh
platform for ongoing data management, historical analysis, and the models were used only as intermediate representations to support
development of scan-to-HBIM-to-FEM workﬂows aimed at preser- the generation of NURBS-based HBIM components.
vation, monitoring, and structural assessment ( Fig. 2 ). The proposed approach enabled the creation of high-precision
To support downstream modelling and interoperability, the NURBS representations of architectural elements, achieving geopoint-cloud data were segmented and decimated according to el- metric accuracy of approximately 0.5 mm.
ement type, spatial extension, and local geometric complexity. The modelling strategy follows the Grades of Generation (GOG)
The decimation process was calibrated to reduce ﬁle size and framework introduced by Banﬁ, which deﬁnes the relationship becomputational burden while preserving the accuracy required for tween surveyed data, interpretative modelling, and resulting HBIM
NURBS interpolation and architectural interpretation. In this sense, geometry [ 10 ]. To clarify its use, GOG 9 refers to advanced surfacedata reduction was applied selectively rather than uniformly, with based reconstruction from survey data, while GOG 10 represents a

255

<!-- p. 7 -->

F. Banﬁ, A. Viskovic, L. Antonelli et al. Journal of Cultural Heritage 82 (2026) 250–264

Fig. 3. Textured mesh model of the frigidarium, showing intricate geometries. Although detailed, the mesh model is not directly usable in scan-to-BIM or FEM processes
and requires semantic modeling to convert the geometry into architectural and structural components. Source: Author F.B.

further stage in which NURBS-based entities are structured for di- splines facilitated the identiﬁcation of key features, enabling accurect transformation into HBIM objects. In this study, GOGs 9 and rate reconstruction paths and optimal control-point selection for
10—based on NURBS surface patches—were applied to accurately NURBS interpolation. An Automatic Veriﬁcation System (AVS) was
represent complex geometries while exploiting the computational employed to quantify the model’s geometric reliability by comparadvantages of GOG 10 [ 51 ]. ing the point cloud with the HBIM representation. To gain a more
Unlike meshes, which are often diﬃcult to convert into HBIM detailed understanding of the error distribution and, consequently,
elements, NURBS surface patches can be directly transformed into the model’s consistency with the surveyed reality, the standard deparametric components. This approach preserves geometric accu- viation was calculated. This statistical measure enabled assessment
racy without simpliﬁcation and improves computational eﬃciency of the variability of deviations from the mean, providing a reliable
in subsequent simulations. A NURBS surface patch is deﬁned math- indication of the model’s overall geometric accuracy. The standard
ematically through control points, weights, and knot vectors, en- deviation was computed using the following formula:
abling precise modelling of smooth, free-form geometries typical
n
of historical architecture. Individual patches can be independently 1 2
σ = xi −¯x
controlled and then combined to reconstruct complex architectural n −1
i =1
elements.
A NURBS surface patch can be represented as where:
m n xi represents the error of the individual point,
i=0 j=0 wij pij Ni , k ( u) Nj , l ( v) ¯x is the average error calculated over the entire sample,
r( u , v ) = m n
i=0 j=0 wij Ni , k ( u)Nj , l ( v) n is the total number of points analyzed.
These formulations clarify the rationale for adopting NURBS in
where wij > 0 s a weighting factor. This formulation enables the ex- the workﬂow. Their parametric nature allows control over surface
act representation of surface geometry derived from a point cloud. continuity, edge constraints, and local deformation, enabling the
In the parametric representation, the coordinates of a point ( x, y, z) reconstruction of irregular vaults, walls, and interfaces as matheon the surface patch are expressed as functions of the parameters matically coherent surfaces. Unlike polygonal meshes, NURBS preu and v within a closed rectangular domain: serve analytical surface deﬁnitions, facilitating both geometric verix = x( u, v ), y = y( u, v ), z = z( u, v ) , u1 ≤u ≤u2 , v ≤v ≤v2 , ﬁcation and subsequent transformation into information-rich HBIM
objects. These analytical surfaces can then be converted into HBIM
The explicit representation is given by: components and transferred to the structural-analysis environz = F( x, y ) ment.
Error analysis showed a low standard deviation, indicating
The patch surface method approximates geometric entities via strong agreement between the HBIM model and survey data and
adaptive base-plane deformation and integrates point clouds to conﬁrming geometric accuracy within required tolerances ( Fig. 4 ).
manage variable values, forming the foundation of the GOG 10 This veriﬁcation was a necessary step before semantic enrichment
framework. This method requires precise input curves and con- and FEM transfer, ensuring that the reconstructed geometry faithtrol over sampling points, especially for complex archaeological el- fully represented the surveyed remains and could be reliably used
ements, and enables the automatic transformation of NURBS-based for subsequent structural idealisation rather than merely providing
entities into HBIM objects in Autodesk Revit. Fig. 4 illustrates how a geometrically plausible representation.
a closed external boundary and the correctly imported frigidarium The interoperability between Rhinoceros and Autodesk Revit repoint cloud enable surface generation that aligns with laser scan lies on the transfer of mathematically deﬁned NURBS geometries
data, reducing manual effort and improving the Grade of Accuracy rather than polygonal meshes. Following geometric reconstruction
(GOA). The GOG 10 process required: in Rhinoceros, each NURBS surface is veriﬁed for continuity, clo-
sure, and topological consistency to ensure that it can be con-
• A cleaned segment of the point cloud matching the target ele-
verted into a valid Boundary Representation (B-Rep) solid. The ge-
ment.
ometries are subsequently exported using a DWG-based exchange
• A closed boundary curve intersecting the primary shape’s
schema (2007 Solids), which preserves the B-Rep description and
edges.
avoids the tessellation typically associated with mesh-based ex-
In addition to modeling, GOG 10 aided point cloud interpreta- change formats. Within Autodesk Revit, the imported B-Rep solids
tion, guiding the understanding of scan geometry. Drawing closed are converted into native parametric HBIM objects through cus-

256

<!-- p. 8 -->

F. Banﬁ, A. Viskovic, L. Antonelli et al. Journal of Cultural Heritage 82 (2026) 250–264

Fig. 4. The surface patch properties facilitate the interpolation between the point cloud (a) and the outer edge (b) in 3D, based on the user’s interpretation of the initial data
and the individual points that make up the cloud. This interpolation results in a NURBS surface (c), which precisely captures the geometric irregularities identiﬁed through
curvature analysis (d). Once the structural component is deﬁned, its accuracy can be assessed by calculating the standard deviation (e) between (a) and (c), validating its
geometric reliability. Following this veriﬁcation, the NURBS structural element (c) can be converted into an HBIM object (f), thereby extending its semantic value. Source:
Author F.B.

tom families. During this process, the original geometric deﬁni- For successful NURBS-to-HBIM transformation in Autodesk Retion is maintained while semantic attributes—including material vit, U and V divisions should range between 32 × 32 and
properties, construction phases, stratigraphic units, conservation 50 × 50, as deviations may cause failure. This subdivision enstate, and restoration records—are associated with each element. sures suﬃcient geometric continuity for reliable B-Rep generaConsequently, Revit does not modify the reconstructed geome- tion while avoiding unnecessary computational complexity. This
try but enriches it with structured information required for doc- optimized process enabled the creation of granular HBIM obumentation, information management, and interoperability with jects, which Revit converted into parametric elements capable
structural-analysis software. of storing both numerical (e.g., volume, area, material prop-

257

<!-- p. 9 -->

F. Banﬁ, A. Viskovic, L. Antonelli et al. Journal of Cultural Heritage 82 (2026) 250–264

erties) and semantic data (e.g., stratigraphy, historical phases, interconnected, and prepared for interoperability with the FEM
restoration). model. Each object thus functioned not only as a geometric entity
Accordingly, the proposed workﬂow separates geometric mod- but also as an information container linking morphology, chronolelling from semantic modelling. Rhinoceros is exclusively em- ogy, materiality, and structural relevance.
ployed for the accurate reconstruction of complex archaeologi- The semantic attributes assigned to the HBIM objects were incal geometries through NURBS-based modelling, whereas Autodesk formed not only by archaeological interpretation but also by the
Revit functions as the HBIM authoring environment, where NURBS- results of diagnostic investigations, which provided complementary
derived solids become semantically structured information ob- information on material properties, construction techniques, and
jects. This distinction justiﬁes the use of both software platforms: structural condition. The diagnostic methodology adopted in this
Rhinoceros guarantees geometric ﬁdelity for highly irregular ar- study is described in the following subsection.
chaeological remains, while Revit provides the semantic organisation and information management required for HBIM implementation and the controlled transfer of geometrically and semantically 2.6. Diagnostic investigations supporting archaeological
consistent models to the FEM environment. interpretation, HBIM semantic enrichment and FEM calibration
In the proposed workﬂow, Revit is therefore not used for geometric reconstruction, which is entirely performed in Rhinoceros, Diagnostic investigations were carried out to support the arbut as the HBIM authoring environment in which NURBS-derived chaeological interpretation of the Villa dei Quintili and to provide
solids become semantically structured building objects suitable for reliable information for the mechanical characterization required
interoperability with the subsequent FEM environment. by the FEM analyses. These investigations were not part of the
HBIM modelling process itself; rather, they constituted external
2.5. Building-archaeology-informed semantic enrichment knowledge sources that informed both the semantic enrichment of
the HBIM model and the calibration of the structural model.
A second modelling step ensured that the HBIM model was not Non-invasive and minor-destructive investigations were peronly geometrically reliable but also aligned with the requirements formed including ﬂat-jack tests, endoscopic inspections, and corof archaeological interpretation and structural analysis. In accor- ing.
dance with current technical standards, this study adopts the con- Flat-jack tests were used to estimate the in situ stress state and
cept of Level of Information Need, which integrates the geomet- the deformability of the masonry, endoscopic inspections provided
ric, alphanumeric, and documentation requirements necessary for information on the internal texture, void distribution, and cona speciﬁc purpose. Rather than considering geometric detail and struction interfaces, while coring allowed the characterization of
information content separately, the Level of Information Need con- foundation geometry and the internal composition of the masonry.
cept deﬁnes the amount and quality of information required to The information obtained from these investigations complemented
support a particular use case. For the purposes of the proposed the archaeological interpretation by validating construction hyworkﬂow, the Level of Information Need was deﬁned to support potheses, identifying mechanically signiﬁcant discontinuities, and
three main objectives: (i) the representation of irregular archaeo- supporting the assignment of material properties to the structural
logical morphologies; (ii) the semantic encoding of stratigraphic, model. Consequently, diagnostic investigations were considered an
material, and constructive information; and (iii) the transfer of the external source of knowledge that enriched the HBIM information
model to the FEM environment while minimizing geometric and model and informed the subsequent FEM analyses, rather than besemantic information loss. ing an intrinsic component of the HBIM workﬂow. Stratigraphic
Within Autodesk Revit, the semantic enrichment phase trans- analysis identiﬁed key construction phases—particularly between
lated archaeological interpretation into parametric objects and as- the Hadrianic and Severan periods—while crack-pattern mapping
sociated attributes. Rather than assigning semantic information di- revealed structural weaknesses, especially at poorly bonded interrectly to the surveyed geometry, the workﬂow ﬁrst segmented the faces. Their combined interpretation improved the understanding
archaeological remains according to the results of the BA analysis. of the villa’s structural behaviour and seismic response.
Each segment corresponded to a meaningful archaeological entity, In Fig. 5 b, colour mapping represents the semantic differentiasuch as a stratigraphic unit, construction phase, masonry typol- tion of volumetric or quasi-volumetric stratigraphic entities within
ogy, or structural interface, which subsequently became an inde- the HBIM environment. Where volumetric reconstruction was pospendent HBIM object. NURBS-derived geometries were converted sible, SUs were modelled as information-bearing components; othinto HBIM elements and organized according to their structural erwise, colour coding provided interpretative support. Three main
and stratigraphic roles. Custom Revit families and shared parame- phases were identiﬁed: the Hadrianic phase (dark pink), featuring
ters were created to associate each HBIM object with both geomet- a large tuff-and-brick hall; the Antonine phase (light yellow), charric and non-geometric information. Besides conventional attributes acterized by structural integration and reinforcement; and the Sevsuch as dimensions, material properties, and volumes, the seman- eran phase (dark blue), marked by the closure of niches.
tic structure included archaeological information, including con- Crack-pattern analysis ( Fig. 5 c) highlights signiﬁcant structural
struction chronology, stratigraphic relationships, masonry typology, issues. The ﬁrst-phase wall shows widespread fractures at brick–
conservation state, diagnostic evidence, and structural relevance. tuff interfaces, indicating weak bonding. In the second-phase
Consequently, each HBIM component functioned not merely as a arch, keystone damage and rotation of the right pier generated
geometric representation but as an information container support- cracks radiating toward the opening. At phase interfaces, torsional
ing archaeological interpretation, conservation management, and stresses induced additional cracking extending toward the outer
structural idealisation. Rather than adapting archaeological remains wall portions. Notably, the upper brick sections added in later
to standard construction categories, custom families and shared phases show no visible damage, conﬁrming different mechanical
parameters were used to represent masonry bodies, stratigraphic behaviour across construction stages.
units (SUs), construction phases, material types, decay conditions, The combined interpretation of archaeological evidence, diand diagnostic-test results. In this workﬂow, BA therefore acts agnostic investigations, and crack-pattern mapping provided the
before HBIM modelling, deﬁning how the surveyed remains are knowledge base required to deﬁne mechanically meaningful HBIM
decomposed into semantic entities. HBIM subsequently provides objects and to support the subsequent transfer of reliable geometthe digital environment in which these entities are parameterised, ric and material information to the FEM environment.

258

<!-- p. 10 -->

F. Banﬁ, A. Viskovic, L. Antonelli et al. Journal of Cultural Heritage 82 (2026) 250–264

Fig. 5. Structural and Geotechnical tests equipment, such as double ﬂat jack, for masonry strength and stiffness test, and hydraulic crawler drills, for geotechnical investigations, surveys, and exploratory wells, carried out by Aureli Soil srl (a); Frigidarium, north wall (exterior) – HBIM mapping of building volumetric SUs (b); north wall
(exterior) – HBIM mapping of crack patterns (c). Source: author F.B., S.R., M.D.P.

259

<!-- p. 11 -->

F. Banﬁ, A. Viskovic, L. Antonelli et al. Journal of Cultural Heritage 82 (2026) 250–264

2.7. HBIM-to-FEM transfer and ﬁnite-element modelling strategy Boundary conditions were deﬁned based on observed construc-
tive continuity, foundation data from surveys and coring, and the
The interpretation and analysis of survey data, alongside the current structural conﬁguration of the frigidarium and calidarium.
identiﬁcation and representation of Stratigraphic Units (SUs), en- Particular attention was given to discontinuities between construcabled the creation of volumetric parametric objects within a BIM tion phases, the absence of horizontal diaphragms, and the partial
environment, accommodating heterogeneous, multi-source infor- loss of upper structural continuity, as these factors strongly inﬂumation ( Fig. 5 b). Each structural component and SU, interpreted ence the global response. The adopted constraints, therefore, aimed
through BA, was characterized and assigned material properties di- to represent the actual support conditions of the archaeological rerectly in Autodesk Revit, eliminating the need for third-party soft- mains, avoiding idealized full-ﬁxity assumptions.
ware or plug-ins. Upon completion, the HBIM model was exported
in Revit native format (RVT) for model continuity and internal co- 2.9. The structural analyses – FEM analyses, general aspects
ordination, in IFC for open information exchange, and in IGES for
FEM-oriented geometric transfer. This distinction is important be- The structural analysis follows three main phases:
cause each format supported a different interoperability objective: • Pre-processing: This phase involves deﬁning the structure’s geRVT preserved the authoring environment and semantic structure; ometry, material properties, and boundary conditions. In the
IFC supported structured information exchange; and IGES proved case of the Villa dei Quintili ruins, boundary conditions were
the most effective option for preserving NURBS-based geometries deﬁned by considering foundation continuity, the connection
during transfer to the structural-analysis platform. (or lack thereof) between orthogonal walls, interruptions in
For structural analysis purposes, only the load-bearing compo- upper masonry, and the absence of effective horizontal dinents identiﬁed during the HBIM semantic modelling phase were aphragms. These assumptions were essential to represent the
exported to the FEM environment. Architectural elements without actual structural behaviour of the archaeological remains and to
structural relevance were excluded in order to reduce computa- avoid an overestimation of global stiffness. Loads are applied in
tional complexity and avoid unnecessary meshing operations. The terms of both magnitude and position, and the structure is diIGES format was selected because it preserves the Boundary Rep- vided into ﬁnite elements, each with its own shape and degrees
resentation (B-Rep) of NURBS-derived solids, allowing the receiving of freedom (DOF). The elements form a computational mesh
FEM software to reconstruct geometrically continuous solid bodies that must be veriﬁed for irregularities and optimized for ressuitable for ﬁnite-element discretisation. olution and computational eﬃciency. The mesh also needs to
After import into MIDAS FEA, the transferred solids were ver- reﬂect the heterogeneous nature of materials and historic maiﬁed for geometric continuity and topological consistency before sonry. The ﬁnal step assigns mechanical properties (e.g., elastic
mesh generation. The ﬁnite-element mesh was therefore generated modulus, Poisson’s ratio, density) to each material type in the
directly from the imported solid geometry rather than from polyg- model.
onal meshes or triangulated surfaces, minimizing geometric ap- • Processing: A system of algebraic equations is solved to deproximation during the discretisation process. Material properties, termine key structural parameters such as reactions, internal
boundary conditions, and structural constraints were subsequently stresses, and strains. Using interpolation functions, these paassigned according to the archaeological interpretation and diag- rameters are also calculated at any point within each element,
nostic investigations previously incorporated into the HBIM model. generating a continuous mechanical response throughout the
While semantic information stored in Revit was not transferred au- model.
tomatically through the IGES format, it was used as the reference • Post-processing: Numerical results are visualized to aid interfor deﬁning the corresponding mechanical properties and struc- pretation. Graphical outputs, such as colour-mapped stress distural assumptions within the FEM environment. tributions, highlight critical zones (e.g., red areas) where struc-
Consequently, interoperability between HBIM and FEM should tural performance may fall below acceptable limits. These vinot be interpreted as the automatic transfer of the complete in- sualizations help reﬁne the model and guide further structural
formation model, but as a controlled workﬂow in which geomet- evaluations or conservation decisions.
ric ﬁdelity is preserved through IGES while semantic information
is intentionally translated into the mechanical parameters required 2.10. Dynamic and static analyses
for structural simulation.
Linear Dynamic Analysis: Modal analyses focus on investigating
2.8. Model calibration and analysis setup the modal forms of vibration—deformation shapes and their natu-
ral frequencies. This analysis provides insights into the structure’s
The FEM model was calibrated through an iterative compari- global dynamic behavior, identifying potential weaknesses. Seismic
son between the numerical response and the structural evidence response spectra simulate realistic seismic loading, enabling examobtained from the survey, archaeological interpretation, and diag- ination of stress distributions under dynamic conditions ( Fig. 6 ).
nostic investigations. In this study, calibration primarily relied on Static Analysis: Linear and nonlinear static analyses evaluate
comparing computed natural frequencies with the dynamic be- stress states under gravitational and seismic loads to determine if
haviour inferred from structural conﬁguration and modal analysis. materials stay within their resistance limits.
Modal shapes were assessed qualitatively to verify the plausibility
• Linear Static Analysis: Assumes elastic material behavior and
of global deformation patterns, but were not included in a formal
considers gravitational loads.
objective function for automated model updating.
• Nonlinear Static (Pushover) Analysis: Applies incremental load
This approach reﬂects the exploratory and application-oriented
increases (vertical or horizontal) in discrete steps. Structural elnature of the workﬂow, which aims to establish a robust path for
ements are checked for mechanical failure after each step, and
interoperability from survey to structural analysis in an archaeo-
failed elements are removed from the system, simulating crack
logical context. More advanced calibration procedures—combining
formation and damage progression.
frequencies and modal assurance indicators within multi-objective
frameworks—are recognized as a promising direction for future re- These analyses provide essential data for understanding strucsearch, particularly as more extensive experimental dynamic data tural performance and informing conservation strategies. To furbecome available. ther enhance the reliability of the safety assessment, local collapse

260

<!-- p. 12 -->

F. Banﬁ, A. Viskovic, L. Antonelli et al. Journal of Cultural Heritage 82 (2026) 250–264

Fig. 6. Frigidarium, present state FEM (MIDAS) modal dynamic analyses frigidarium: mode of vibration No 1 plan view (left) and axonometric view (right), mode of vibration
No 17 plan view (botton). Source: authors A.V. and L.A.

mechanisms—identiﬁed from detailed 3D survey data—are evalu- indicate low seismic safety coeﬃcients under horizontal actions
ated using Limit Analysis Theory. This approach is particularly rel- (0.39–0.48). Local collapse analyses further highlight critical condievant for masonry structures, where out-of-plane failure or local tions, including horizontal bending mechanisms affecting individmechanisms can be critical. ual walls.
In both linear and nonlinear analyses, the safety evaluation ultimately rests on comparing the horizontal load capacity at collapse 3. Design and evaluation of the structural interventions in
with the design seismic action for the speciﬁc site and structure. terms of safety improvement
This comparison enables a quantitative assessment of the structure’s seismic performance, informing targeted conservation or re- In the ﬁrst phase of the project, seismic and static safety iminforcement interventions. provements focused on the frigidarium, while similar interventions
for the caldarium are planned for a subsequent phase. The main
objective was to improve global seismic behaviour, alongside lo2.11. Present-state structural assessment
cal reinforcement and the reconstruction of missing elements for
static safety. The critical issue concerned the horizontal disconti-
The HBIM–FEM integration is grounded in digital documen-
nuities at the tops of the perimeter walls, particularly the absence
tation, parametric modelling, and structural analysis. HBIM pro-
of the wall and arch above the large upper eastern window.
vides a repository of geometric and semantic information, while
Three intervention strategies were evaluated:
FEM enables simulation of structural behaviour and stability, allowing a more comprehensive understanding of complex archae- • Traditional rebuilding with steel reinforcement: This option reological structures. In the case of the caldarium and frigidarium, constructs the missing masonry and arch, restoring structural
the analyses reveal signiﬁcant relative movements between struc- continuity, and integrates steel beams (two coupled C-proﬁles)
tural elements due to internal discontinuities. Despite their box- along the upper perimeter ( Fig. 7 ). It achieved a seismic safety
like conﬁguration, both structures lack horizontal closures and ex- index of 0.73 but is considered invasive, as it alters the monuhibit pronounced discontinuities at the top of the perimeter walls, ment’s established appearance.
as conﬁrmed by modal analysis. As a result, the global behaviour • Conservative steel reinforcement: This solution avoids reconwas assessed using static equivalent pushover analyses, which struction and instead reinforces the eastern wall with a steel

261

<!-- p. 13 -->

F. Banﬁ, A. Viskovic, L. Antonelli et al. Journal of Cultural Heritage 82 (2026) 250–264

Fig. 7. Frigidarium, showing the three proposed solutions: the ﬁrst (left), the second (center), and the selected solution (right), which was ultimately chosen for its suitability
and effectiveness. Source: authors A.V. and L.A.

Fig. 8. Frigidarium, the modal dynamic analyses with the chosen intervention: axonometric views of mode 1 (left) and mode 17 (right). The site work preparation (below).
Source: authors.

plate connected to perimeter beams. While less invasive, it re- The diameter of these tubular elements is dimensioned in such
sulted in a lower seismic safety index of 0.56. a way as to avoid instability in case of compression actions, but it
• Hybrid solution: The selected option combines both ap- is limited in such a way as not to disturb/alter the monument’s
proaches, avoiding masonry reconstruction while connecting present image. This solution yields a highly eﬃcient outcome,
the perimeter steel beams to two tubular elements spanning more eﬃcient than the initial one. The seismic safety reaches a
the eastern opening. This solution balances structural improve- signiﬁcant improvement, with a value of 0,85. The results obtained
ment with minimal visual impact. enabled progression to the ﬁnal phase of the construction process,
with the goal of optimizing restoration and conservation efforts
while ensuring the eﬃcient integration of historical and structural
information into the recovery project ( Fig. 8 ). The hybrid solution was ultimately adopted, as it provided the
The numerical results conﬁrm that the most critical aspect ofbest compromise between seismic performance and conservation
the present structural conﬁguration is the discontinuous behaviourrequirements.

262

<!-- p. 14 -->

F. Banﬁ, A. Viskovic, L. Antonelli et al. Journal of Cultural Heritage 82 (2026) 250–264

of the upper portions of the perimeter walls, which promote rela- The results demonstrate that integrating Building Archaeology entive out-of-plane and torsional movements. This ﬁnding is consis- hances both the semantic richness of the model and the cohertent with the archaeological and crack-pattern readings, which had ence between geometric reconstruction, structural interpretation,
already highlighted weak interfaces between different construction and intervention design.
phases and poor structural continuity at selected wall junctions. A ﬁrst key outcome is that, in archaeological contexts, interIn this respect, the FEM results should not be interpreted as an operability cannot be reduced to the transfer of geometry beisolated computational output, but as a conﬁrmation of a broader tween software environments. Reliable structural assessment recross-reading involving geometry, stratigraphy, damage mapping, quires an interpretative phase capable of identifying construction
and material investigation. phases, stratigraphic discontinuities, reuse processes, and material
Speciﬁcally, the seismic improvement plan focused on restor- variability. In this respect, Building Archaeology plays a central role
ing the building’s structural continuity, including the reconstruc- in transforming survey data into structurally and historically meantion of the collapsed arch in the façade. Scaffolding was imple- ingful information.
mented to facilitate restoration work in OG2, a category of works A second outcome concerns geometric modelling. While highdeﬁned in Italy’s Public Works Classiﬁcation System. This cate- resolution meshes and point clouds provide accurate documengory is primarily used in public procurement and building regula- tation, they must be translated into controlled and semantically
tions. More speciﬁcally, OG2 encompasses restoration and conser- structured representations to support HBIM and FEM applicavation work on protected heritage buildings. These works include tions. NURBS-based modelling and the grades of generation (GOGs)
the maintenance, renovation, and preservation of structures with proved particularly effective in mediating between survey comhistorical, cultural, or architectural value, making the term applica- plexity and analytical usability.
ble to conservation-focused restoration projects. Therefore, in this A third outcome relates to conservation practice. The workﬂow
context, OG2 indicates that the restoration phase involves interven- enabled transparent comparison of intervention scenarios and suption in a protected or historic building, with a particular focus on ported the development of a strengthening solution that improved
preserving and restoring existing structural elements. the frigidarium’s seismic safety index from 0.39 to 0.85 while lim-
iting visual impact, conﬁrming the method’s value for evidence-
based decision-making.
\4. Discussion
The originality of the research lies in the explicit integration of
archaeological interpretation within the generative, semantic, and
The main contribution of the proposed scan-to-HBIM-to-BA-to-
structural stages of the workﬂow, proposing a uniﬁed process in
FEM workﬂow is to frame interoperability not only as ﬁle ex-
which HBIM, Building Archaeology, and FEM are mutually informachange, but as a knowledge-transfer process linking survey data,
tive.
archaeological interpretation, semantic modelling, and structural
Some limitations remain. The workﬂow still depends on expertassessment. Compared with many scan-to-BIM-to-FEM approaches,
driven modelling, interoperability is only partially standardized,
it emphasizes the interpretative role of BA, which is essential for
and calibration is constrained by available experimental data. Fuanalysing discontinuous, stratiﬁed, and partially collapsed remains.
ture work should focus on automation, improved standardization
The application to the Villa dei Quintili shows that integrating BA
of archaeological semantics, and more advanced model-updating
improves coherence between geometric reconstruction and struc-
procedures, including the potential integration of surrogate modtural interpretation. Archaeological analysis of phases, interfaces,
elling.
and reuse processes enabled the deﬁnition of semantically mean-
Overall, the proposed HBIM-BA-FEM integration represents a
ingful HBIM entities and informed FEM idealization, advancing be-
robust and scalable approach for the preservation of complex aryond approaches focused mainly on geometric automation. Some
chaeological heritage, particularly where documentation, structural
limitations remain. The workﬂow still requires expert intervention
assessment, and stratigraphic interpretation must be addressed siin segmentation, NURBS modelling, semantic structuring, and FEM
multaneously.
preparation. Interoperability is only partially standardized, as no
single format preserves both geometry and semantics, and calibra- References
tion is constrained by limited experimental data, requiring further
development through formal model-updating procedures. [1] L.J. Lovell, R.J. Davies, D.V.L. Hunt, The application of historic building informa-
Another key outcome concerns the balance between geometric tion modelling (HBIM) to cultural heritage: a review, Heritage 6 (10) (2023)
6691–6717, doi: 10.3390/heritage6100350 .
ﬁdelity and analytical usability. In archaeological contexts, higher [2] X. Yang, P. Grussenmeyer, M. Koehl, H. Macher, A. Murtiyoso, T. Landes, Regeometric detail does not necessarily improve structural reliabil- view of built heritage modelling: integration of HBIM and other information
ity; instead, it depends on the controlled transformation of sur- techniques, J. Cult. Herit. 46 (2020) 350–360 .
[3] J. Moyano, E. Carreño, J.E. Nieto-Julián, I. Gil-Arizón, S. Bruno, Systematic apveyed complexity into analytically meaningful representations. In proach to generate historical building information modelling (HBIM) in archithis respect, combining NURBS-based modelling with archaeolog- tectural restoration project, Autom. Construct. 143 (2022) 104551 .
ically informed semantic enrichment proved more effective than [4] M. Attenni, C. Bianchini, M. Griffo, L.J. Senatore, HBIM meta-modelling: 50 (and
more) shades of grey, ISPRS Int. J. Geoinf. 11 (9) (2022) 468 .
relying solely on high-resolution meshes or automated discretiza- [5] T. Penjor, S. Banihashemi, A. Hajirasouli, H. Golzad, Heritage building infortion. More broadly, the study highlights the interpretative nature of mation modeling (HBIM) for heritage conservation: framework of challenges,
digital modelling in heritage conservation. Digital models should gaps, and existing limitations, Digit. Applic. Archaeol. Cult. Heritage 35 (2024)
be seen not as neutral replicas but as structured environments e00366 .
[6] J. Cassandro, C. Mirarchi, M. Gholamzadehmir, A. Pavan, Advancements and
that integrate metric data, historical knowledge, and structural prospects in building information modeling (BIM) for construction: a rehypotheses, thereby supporting transparent and interdisciplinary view, Eng., Construct. Archit. Manag. 32 (9) (2024) 6006–6026, doi: 10.1108/
decision-making. ECAM- 04- 2024- 0435 .
[7] C. Portalés, J.L. Lerma, S. Navarro, Augmented reality and photogrammetry:
a synergy to visualize physical and virtual city environments, ISPRS J. Pho-
togramm. Remote Sens. 65 (1) (2010) 134–142 .
\5. Conclusions [8] A. Georgopoulos, C. Ioannidis, Photogrammetric and Surveying Methods for
the Geometric Recording of Archaeological Monuments, FIG Working Week,
This study presented a scan-to-HBIM-to-BA-to-FEM workﬂow Athens, 2004 .
[9] M. Lombardi, D. Rizzi, Semantic modelling and HBIM: a new multidisciplinary
for the structural assessment and conservation-oriented modelling workﬂow for archaeological heritage, Digit. Applic. Archaeol. Cult. Heritage 32
of archaeological remains, tested on the Villa dei Quintili (Rome). (2024) e00322 .

263

<!-- p. 15 -->

F. Banﬁ, A. Viskovic, L. Antonelli et al. Journal of Cultural Heritage 82 (2026) 250–264

[10] F. Banﬁ, HBIM, 3D drawing and virtual reality for archaeological sites and an- [29] D. Antón, P. Pineda, B. Medjdoub, A. Iranzo, As-built 3D heritage city modelling
cient ruins, Virt. Archaeol. Rev. 11 (23) (2020) 16 . for structural analysis, Remote Sens. (Basel) 11 (11) (2019) 1276 .
[11] V. Bagnolo, R. Argiolas, A. Cuccu, HBIM for archaeological sites: from [30] G. Castellazzi, N.L. Presti, A.M. D’Altri, Miranda S. de, Cloud2FEM: a mesh gen-
SFM-based survey to algorithmic modeling, Int. Arch. Photogramm., Remote erator based on point clouds, SoftwareX 18 (2022) 101099 .
Sens. Spatial Inf. Sci. 42 (2019) 57–63 . [31] R. Quattrini, P. Clini, R. Nespeca, L. Ruggeri, Measurement and HBIM represen-
[12] V. Jagota, A.P.S. Sethi, K. Kumar, Finite element method: an overview, Walailak tation, Disegnarecon 9 (16) (2016) 14 .
J. Sci. Technol. 10 (1) (2013) 1–8 . [32] M. Murphy, E. Meegan, G. Keenaghan, A. Chenaux, A. Corns, S. Fai, O. Prizeman,
[13] I.D. Erhunmwun, U.B. Ikponmwosa, Review on ﬁnite element method, J. Appl. Shape grammar libraries for historic BIM, ISPRS Arch. 46 (2021) 479–486 .
Sci. Environ. Manag. 21 (5) (2017) 999 . [33] A . Ursini, A . Grazzini, F. Matrone, M. Zerbinatti, From scan-to-BIM to FEM for
[14] K. Giles, Buildings archaeology, in: Encyclopedia of Global Archaeology, dynamic simulation, Autom. Constr. 142 (2022) 104518 .
Springer, New York, 2014, pp. 1033–1041 . [34] G. Bitelli, G. Castellazzi, A.M. D’Altri, S. De Miranda, A. Lambertini, I. Selvaggi,
[15] C. Stanga, F. Banﬁ, S. Roascio, Enhancing building archaeology: drawing, Generation of numerical models from point clouds, IOP Conf. Ser. 364 (2018)
UAV photogrammetry and scan-to-BIM-to-VR process of ancient Roman ruins, 012083 .
Drones 7 (8) (2023) 521 . [35] G. Bitelli, G. Castellazzi, A.M. D’Altri, S. De Miranda, A. Lambertini, I. Selvaggi,
[16] F. Diara, F. Rinaudo, Building archaeology documentation and analysis through Automated voxel model from point clouds, ISPRS Arch. 41 (2016) 191–197 .
open source HBIM solutions via NURBS modelling. International Archives of [36] A.M. D’Altri, S. de Miranda, G. Castellazzi, B. Glisic, Numerical modelling-based
the Photogrammetry, Remote Sens. Spatial Inf. Sci. 43 (2020) 1381–1388 . damage diagnostics, J. Cult. Herit. 61 (2023) 1–12 .
[17] I. Trizio, F. Savini, Archaeology of buildings and HBIM methodology: integrated [37] N. Lo Presti, G. Castellazzi, A.M. D’Altri, G. Bertani, S. de Miranda, M. Azenha,
tools for documentation and knowledge management of architectural heritage, C. Mazzotti, Streamlining FE and BIM modeling for historic buildings, Int. J.
in: Proceedings of IMEKO MetroArchaeo, 2020, pp. 84–89 . Archit. Heritage 19 (7) (2025) 1086–1099 .
[18] S. Brusaporci, I. Trizio, G. Ruggeri, P. Maiezza, A. Tata, A. Giannangeli, AH- [38] S.S. Kaushal, M. Gutierrez Soto, R. Napolitano, Structural analysis using
BIM per l’analisi stratigraﬁca dell’architettura storica, Restauro Archeol. 26 (1) CLOUD2FEM, ISPRS Arch. 48 (2023) 827–834 .
(2018) 112–131 . [39] S. Gonizzi Barsanti, M. Guagliano, A. Rossi, 3D reality-based survey and re-
[19] P. Borin, R.A. Bernardello, A. Grigoletto, Connecting historical information with topology, Sensors 22 (24) (2022) 9593 .
BIM ontologies, in: Graphical Heritage, Springer, 2020, pp. 757–770 . [40] A. Lucidi, E. Giordano, F. Clementi, R. Quattrini, Point cloud exploitation for
[20] S.S. Bhavikatti, Finite Element Analysis, New Age International, 2005 . structural modeling, ISPRS Arch. 43 (2021) 891–898 .
[21] D. Addessi, D. Liberatore, R. Masiani, Force-based beam ﬁnite element for the [41] X. Zou, S.B. Lo, R. Sevilla, O. Hassan, K. Morgan, Tetrahedral meshes for NURB-
pushover analysis of masonry buildings, Int. J. Archit. Heritage 9 (3) (2015) S-enhanced FEM, Eng. Comput. 40 (6) (2024) 3949–3977 .
231–243 . [42] F. Turchetti, B. Cuca, D. Oreni, A. Agapiou, Recording historic buildings for FEA,
[22] K.K. Kuria, O.K. Kegyes-Brassai, Pushover analysis in seismic engineering: a de- Heritage 8 (2) (2025) 55 .
tailed chronology and review, Appl. Sci. 14 (1) (2023) 151 . [43] S. Brusaporci, P. Maiezza, A. Marra, A. Tata, L. Vespasiano, Scan-to-HBIM relia-
[23] D. Oreni, R. Brumana, T.S. Della, F. Banﬁ, L. Barazzetti, M. Previtali, Survey bility, Drones 7 (7) (2023) 426 .
turned into HBIM: the restoration of the Basilica di Collemaggio after the [44] A.L. Monaco, N. Grillanda, I. Onescu, M. Foﬁu, F. Clementi, M. D’Amato,
earthquake, ISPRS Ann. II-5 (2014) 267–273 . M. Mosoarca, Seismic assessment of masonry churches, Eng. Fail Anal. 153
[24] L. Barazzetti, F. Banﬁ, R. Brumana, G. Gusmeroli, M. Previtali, G. Schiantarelli, (2023) 107539 .
Cloud-to-BIM-to-FEM: structural simulation with accurate historic BIM from [45] M. Schiavoni, E. Giordano, F. Roscini, F. Clementi, Numerical modeling of ma-
laser scans, Simul. Modell. Pract. Theory 57 (2015) 71–87 . sonry structures, Eng. Fail Anal. 149 (2023) 107293 .
[25] M. Bassier, G. Hadjidemetriou, M. Vergauwen, N. Van Roy, E. Verstrynge, Im- [46] M. Schiavoni, M. Di Giosaffatte, F. Roscini, F. Clementi, Mechanisms detection
plementation of scan-to-BIM and FEM for heritage timber structures, Digit. via FEM and DEM, Bull. Earthq. Eng. (2025) .
Heritage (EuroMed) (2016) 79–90 . [47] G.P. Brogiolo, Archeologia dell’architettura, All’Insegna del Giglio (1996) .
[26] R. Rolin, E. Antaluca, J.L. Batoz, F. Lamarque, M. Lejeune, From point cloud data [48] Brogiolo G.P., Cagnana A., 2012. Archeologia dell’architettura: metodi e inter-
to structural analysis through hBIM, J. Comput. Cult. Heritage 12 (2) (2019) pretazioni.
1–26 . [49] I. Trizio, F. Savini, A. Ruggieri, Archeologia dell’architettura e rappresentazione
[27] S. Santini, M. Canciani, V. Borghese, V. Sabbatini, C. Sebastiani, From digital digitale, Atti del Convegno (2020) 2821–2842 .
restitution to structural analysis of a historical adobe building, Heritage 6 (5) [50] F. Banﬁ, R. Brumana, A.G. Landi, M. Previtali, F. Roncoroni, C. Stanga, Building
(2023) 4362–4379 . archaeology informative modelling, Virtual Archaeol. Rev. 13 (26) (2022) 1–21 .
[28] D. Giaccone, The peristyle of the Temple of Apollo at syracuse: reconstruction [51] F. Banﬁ, Virtual Heritage: dalla Modellazione 3D all’HBIM e Realtà Estesa, Mag-
via FEM, Digi. Applic. Archaeol. Cult. Heritage 16 (2020) e00138 . gioli Editore, Milano, 2023 .

264
