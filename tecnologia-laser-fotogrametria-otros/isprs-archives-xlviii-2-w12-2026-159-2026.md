---
type: libro
title: "isprs-archives-XLVIII-2-W12-2026-159-2026"
author: ""
categoria: "Tecnología láser, fotogrametría, otros"
paginas: 8
extraccion: "texto"
fuente: "local:E:/Biblioteca digital/Tecnología láser, fotogrametría, otros/isprs-archives-XLVIII-2-W12-2026-159-2026.pdf"
convertido: 2026-10-13
---

# isprs-archives-XLVIII-2-W12-2026-159-2026

> Texto extraído de `Tecnología láser, fotogrametría, otros/isprs-archives-XLVIII-2-W12-2026-159-2026.pdf` (8 páginas, texto). El PDF original está en el disco E: (Biblioteca digital); `<!-- p. N -->` marca el inicio de cada página.

<!-- p. 1 -->

The International Archives of the Photogrammetry, Remote Sensing and Spatial Information Sciences, Volume XLVIII-2/W12-2026
11th Intl. Workshop 3D-ARCH "3D Virtual Reconstruction and Visualization of Complex Architectures", 10–12 February 2026, Ancona, Italy

Multiscale Digital Survey and HBIM-GIS Integration for the Conservation
of the Kasbah of Mehdya (Morocco)

Elena Gigliarelli¹, Giovanni Cangi¹, Luciano Cessari¹, Stefano Cursi¹, Chadi Khoury¹, Youssef El Ganadi², Elena Verticchio¹, Anna
Paola Pola¹, Alma Vecchiotti¹, Letizia Martinelli¹, Filippo Calcerano¹

¹ CNR ISPC, Roma, Italia — elena.gigliarelli@ispc.cnr.it
² Université Internationale de Rabat, Rabat, Marocco — y.elganadi@uir.ac.ma

Keywords: Historic Building Information Modeling (HBIM), Geographic Information System (GIS), integrated survey, fortified
architecture, conservation strategies, Kasbah of Mehdya.

Abstract

This paper presents the development and validation of a multiscale digital workflow to document and support the conservation of the
Kasbah of Mehdya, a coastal fortified complex located at the mouth of the Sebou River (northern Morocco). Data acquisition integrates
UAV survey (photogrammetry and aerial LiDAR) to capture site morphology and topography, SLAM-based mobile mapping for rapid
point-cloud acquisition in GPS-denied or partially constrained areas, and high-resolution terrestrial imagery, including spherical
panoramas, to enhance material and decay interpretation. The datasets are processed, filtered, and aligned to generate georeferenced
orthophotos and dense point clouds that feed a scan-to-HBIM pipeline. HBIM models are structured as semantic repositories of
construction phases (12th–17th centuries), traditional materials, and mapped decay patterns, and are exported through interoperable
standards (e.g., IFC) to enable integration within a GIS geodatabase. The resulting HBIM–GIS environment supports multiscale spatial
queries, correlation analyses between observed pathologies and key coastal environmental drivers (e.g., sea-salt aerosol exposure and
vegetation colonisation), and the progressive validation and refinement of pre-existing territorial datasets through “as-built” survey
data. Beyond format-level interoperability, the approach treats geo-referencing consistency and data reliability as prerequisites for a
transferable heritage digital twin bridging architectural and territorial scales. Finally, it lays the groundwork for participatory
dissemination through a WebGIS interface and immersive visualisation tools to support evidence-based, time-sensitive conservation
strategies.

\1. Intoduction heritage in marginal areas, developing WebGIS platforms and
tools for public engagement.
1.1 Background and state of the art In the field of structural assessment (Chiabrando et al., 2016,
Sammartano et al., 2023) researches propose integrated HBIM–
The ongoing digital transformation of cultural heritage practices GIS workflows for seismic vulnerability and structural instability
has positioned Building Information Modeling (BIM) as a central analysis, combining laser scanning surveys with semantically
methodology for the documentation, analysis, and management informed HBIM models. Other investigation (Sammartano et al.,
of existing architectural assets. 2021), extends this approach to the urban scale, testing city-wide
Within the domain of heritage conservation, BIM has evolved semantic digital twins. In archaeological contexts, (Limongiello
into its specialized form—Historic or Heritage BIM (HBIM)— et al., 2025) demonstrate the potential to reconstruct and simulate
enabling the integration of geometric data with material, historical scenarios through parametric integration of HBIM and
structural, and historical information. However, the application GIS.
of HBIM to complex, stratified, or large-scale territorial contexts Overall, the current state of the art reveals a clear shift toward
still presents significant challenges, mainly related to integrated, intelligent, and interoperable information systems—
representation scale, data heterogeneity, and the absence of tools capable of connecting building and landscape scales, improving
to manage broader spatial relationships. long-term data management, and enabling participatory and
To address these gaps, Geographic Information Systems (GIS) evidence-based conservation and enhancement strategies.
have emerged as complementary environments capable of
expanding the scope of analysis, supporting risk assessment, and 1.2 Research gap
integrating environmental and territorial dynamics. The
integration of HBIM and GIS thus facilitates the development of Most HBIM–GIS applications have focused on individual
multiscale information models that can simultaneously manage monuments (e.g., churches, palaces) or relatively homogeneous
architectural and landscape components, while supporting historic fabrics. Coastal fortifications remain under-represented,
evidence-based and time-sensitive decision-making processes. although they are exposed to aggressive environmental agents
Several studies have demonstrated the effectiveness of this and are often affected by long periods of neglect. These contexts
integration. Matrone et al. (2019) and Pepe et al. (2021, 2024) require workflows capable of managing multiscale geometries
highlight how HBIM models can be semantically enriched and and semantics while addressing data reliability and discrepancies
queried within three-dimensional GIS environments, promoting between pre-existing territorial sources and high-precision
new forms of spatial and historical analysis. Other contributions, survey products.
such as those by Bruno et al. (2020) and Pozzoni et al. (2024), The Kasbah of Mehdya is a particularly relevant case: a stratified
focus on temporal integration and the management of dispersed fortified complex whose transformation spans multiple phases,

This contribution has been peer-reviewed.
https://doi.org/10.5194/isprs-archives-XLVIII-2-W12-2026-159-2026 | © Author(s) 2026. CC BY 4.0 License. 159

<!-- p. 2 -->

The International Archives of the Photogrammetry, Remote Sensing and Spatial Information Sciences, Volume XLVIII-2/W12-2026
11th Intl. Workshop 3D-ARCH "3D Virtual Reconstruction and Visualization of Complex Architectures", 10–12 February 2026, Ancona, Italy

including Almoravid and Saadian periods, a Spanish occupation reconquered by the ʿAlawite sultan Moulay Ismāʿīl and
between 1614 and 1681, and a subsequent reorganisation under reconfigured with new architectural and defensive elements,
the ʿAlawite dynasty. Today the site is largely abandoned and including Bab Jadīd, the governor’s palace (Dar al-Maghzen), a
exhibits widespread decay and structural vulnerabilities, mosque, and a hammam (Saladin, 1913).
including local collapses, wall settlements, invasive vegetation Over time, channel silting and the establishment of the port of
growth, and accelerated material deterioration associated with Kénitra reduced the site’s strategic role; it was later reused during
marine aerosol exposure. the French colonial period and involved in events of World War.
II (Raoui, 2010; Coindreau, 1946). After independence, the
1.3 Objectives

The project “Study, Conservation and Valorization of the
Kasbahs in Morocco”, launched in 2024 with the support of the
Italian Ministry of Foreign Affairs and International Cooperation
(MAECI), the International University of Rabat, and the Ministry
of Youth, Culture and Communication of the Kingdom of
Morocco, aims to establish a replicable operational model for
documenting, managing, and enhancing the fortified heritage of
Moroccan kasbahs.
The initiative develops a multiscale digital acquisition workflow
integrating UAV photogrammetry, Insta360 spherical imaging,
and SLAM-based mobile mapping to capture high-resolution
geometric and chromatic data, providing the basis for highfidelity digital twins of selected kasbahs. The collected datasets
are then processed through a scan-to-HBIM pipeline to structure
construction phases, traditional materials, building pathologies,
and past restoration interventions. HBIM outputs are
subsequently integrated into a GIS geodatabase, enabling
territorial-scale analyses—from structural vulnerability to Figure 1. Plan of the Kasbah de Mehdya (La Mamora), dated
environmental risk exposure—and supporting long-term January 18, 1633. Signed by Cristóbal Lechuga, the plan
conservation planning. documents the Spanish defense system during the occupation
To enhance dissemination and stakeholder engagement, the
(1614–1681). Source: Bueno Soto, F.J., 2010: Larache y Laproject also explores WebGIS platforms, immersive tours, and
virtual/augmented reality tools targeting researchers, Mamora: dos fortificaciones españolas en tiempos de Felipe
policymakers, and the wider public, with the goal of ensuring III, Aldaba (34), 87.
open-access availability of the collected information and scalable
guidelines for similar fortified heritage sites across Morocco.
Accordingly, this study aims to: (i) develop and validate a
multiscale acquisition workflow integrating UAV survey,
SLAM-based mobile mapping, and high-resolution terrestrial
imaging; (ii) implement a scan-to-HBIM process to structure
construction phases, materials, and pathologies; (iii) integrate
HBIM outputs into a GIS geodatabase for spatial analysis and
long-term management; and (iv) test a progressive densification
strategy for a heritage digital twin by validating and refining preexisting territorial datasets through “as-built” survey data.

\2. Study area

The Kasbah of Mehdya is located on a promontory at the mouth
of the Sebou River along the Atlantic coast of northern Morocco,
approximately 30 km north of Rabat. Its position historically
enabled the control of both the Atlantic shoreline and the river
corridor connecting the Gharb plain with inland regions.
Ancient sources associate the area with the Phoenician port of
Thymiaterion, although localisation remains debated. In the Figure 2. The Kasbah of Mehdya in a 1932 drawing. Source:
Roman period, the site is linked to Subur (Raoui, 2010). Guillermo Guastavino Gallent in Tirso de Molina, 1939.
Historical reconstructions indicate reoccupation around the
complex underwent limited conservation actions; partialIfranid period (c. 900 AD); the association with the toponym al-
interventions occurred in 2010 under ALINSAP.Maʿmūra/Marsā al-Maʿmūra is reported in modern syntheses but
At present, the Kasbah is characterised by abandonment and highrequires caution when early sources are not explicit (Ajaraam et
vulnerability: local collapses, wall displacements, vegetational., 2024; Lakhdar, 2026). In the 12th century, the Almohad
colonisation, and accelerated decay consistent with coastalcaliph ʿAbd al-Muʾmin reportedly established a naval arsenal
exposure.supporting fleets operating in al-Andalus.
The current bastioned layout is primarily associated with the
Spanish occupation (1614–1681), when the fortress of San
Miguel de Ultramar was built, adopting a “tenaille” configuration
with a floodable moat (Bueno Soto, 2010). In 1681, the site was

This contribution has been peer-reviewed.
https://doi.org/10.5194/isprs-archives-XLVIII-2-W12-2026-159-2026 | © Author(s) 2026. CC BY 4.0 License. 160

<!-- p. 3 -->

The International Archives of the Photogrammetry, Remote Sensing and Spatial Information Sciences, Volume XLVIII-2/W12-2026
11th Intl. Workshop 3D-ARCH "3D Virtual Reconstruction and Visualization of Complex Architectures", 10–12 February 2026, Ancona, Italy

\3. Methodology ZEB Horizon, suitable for rapid acquisition in partially
constrained or GPS-denied conditions. Although the team had
3.1 Multiscale and multimodal data acquisition previously conducted large-scale SLAM surveys by connecting
multiple routes into a single macro acquisition (Bernabei et al.,
The site’s logistical complexity and invasive vegetation required 2023), the Kasbah site posed additional constraints, including
a survey strategy balancing extensive coverage and targeted discontinuous accessibility, lack of direct connections between
detail. The idea from the very beginning was to integrate a buildings, uneven terrain, and limited possibilities for placing
comprehensive acquisition with more detailed spot surveys by connection markers. Therefore, SLAM acquisitions were
studying the feasibility of a management platform for these two performed as targeted “spot” surveys.Due to discontinuous
scales of information (Gigliarelli, Pontrandolfi, and Calcerano, accessibility, irregular terrain, and limited opportunities for
2020). Two field campaigns (2024–2025) were designed to (i) establishing continuous connections between buildings, SLAM
capture the overall morphology and main volumes, and (ii) acquisitions were performed as targeted “spot” surveys, later
document selected structures at architectural scale, prioritising positioned within the UAV reference framework.
areas of conservation concern. At site scale, UAV survey was To support high-resolution surface documentation and masonry
used to provide a georeferenced framework and to capture interpretation—often insufficient in RGB SLAM outputs—the
topography and major architectural bodies. dataset was complemented with terrestrial imagery: spherical
panoramas acquired with Insta360 Pro2 and conventional high-
resolution photographs captured with Canon EOS R5. Spherical
imagery covered interior spaces (e.g., mosque, palace sectors)
and selected interior/exterior transitions, while DSLR imagery
focused on elevations and areas requiring detailed reading of
materials and decay.

3.2 Data processing and georeferencing

UAV photogrammetry was processed in Agisoft Metashape
Professional through image alignment (aerotriangulation) and
dense point-cloud generation, producing georeferenced
orthophotos and 3D products. To improve completeness at
Figure 3. External fortified walls of the citadel, with the view building scale and strengthen the overall dataset, mobile mapping
of Bab Jadīd, the main gate of the site. © Photo by the authors data acquired via GeoSLAM were integrated within the same
processing pipeline, enabling a coherent fusion between rapid,
high-resolution local mapping and the extensive spatial coverage
provided by aerial survey.
Georeferencing and co-registration were managed through a
consistent spatial reference framework to ensure interoperability
with regional GIS datasets and repeatability across campaigns.
For metric operations and local processing steps, datasets were
handled in a projected coordinate reference system; final
deliverables and GIS publication layers were provided in WGS84
(World Geodetic System 1984), corresponding to EPSG:4326.
Accuracy control was supported by Ground Control Points
(GCPs) collected during fieldwork (where available) and/or
stable control features identifiable across datasets, used to anchor
orthophotos and point c Point clouds from multiple sources were
then filtered, aligned, and merged in CloudCompare to obtain a
clean and consistent dataset supporting subsequent modelling
and analysis (Diara et al., 2023). The unified cloud was
segmented and classified to facilitate scan-to-HBIM
operations.louds to a global datum and minimise positioning
errors (fig.4).

3.3 Structural inspection and damage mapping

A technical–structural inspection was conducted to identify crack
patterns, deformation phenomena, and construction
vulnerabilities, with particular focus on rammed earth (tapial)
Figure 4. Results of the data processing and georeferencing and rubble-stone masonry. Observed issues include settlement-
workflow: (a) georeferenced point cloud accurately positioned related cracking, loss of cohesion in binders, plaster detachments,
within the terrestrial geographic reference system; (b) 3D partially collapsed vaults, and out-of-plane mechanisms in
model of the site, including photorealistic texture and vulnerable sectors. These observations were organised into a
integration of existing buildings.
In 2025 a complete UAV campaign included both
photogrammetric acquisitions and aerial LiDAR to improve
coverage and robustness in vegetated sectors. At building scale,
SLAM-based mobile mapping was conducted using GeoSLAM

This contribution has been peer-reviewed.
https://doi.org/10.5194/isprs-archives-XLVIII-2-W12-2026-159-2026 | © Author(s) 2026. CC BY 4.0 License. 161

<!-- p. 4 -->

The International Archives of the Photogrammetry, Remote Sensing and Spatial Information Sciences, Volume XLVIII-2/W12-2026
11th Intl. Workshop 3D-ARCH "3D Virtual Reconstruction and Visualization of Complex Architectures", 10–12 February 2026, Ancona, Italy

preliminary damage map and translated into structured resolution acquisition of point clouds in partially constrained or
information layers for HBIM integration (fig.5). complex environments, providing a robust spatial dataset to
support subsequent modelling phases. To build a coherent and
reliable reference model, point clouds derived from different
acquisition methods were filtered, aligned, and merged in
CloudCompare, ensuring clean geometry and correct orientation
prior to BIM generation (Diara et al., 2023).

Figure 7. The workflow process divided into three sections:
point cloud acquisition, spherical panoramas, and HBIM
modeling. ©Elaborations by the authors

Figure 5. General view of the Mosque and view of the western The workflow combined point-cloud segmentation and
gate currently affected by structural settlements that classification, extraction of reference sections and profiles,
compromise the stability of the arch and the adjacent masonry. NURBS-based reconstruction of architectural surfaces, object-
The diagram illustrates the kinematic mechanisms. © Photo and based HBIM modelling, and export to open standards to support
elaboration by the authors interoperability (Fig. 7). The pipeline was first applied to the
mosque and subsequently extended to the governor’s palace (Dar
Pathology classification follows the Italian PCM Guidelines for al-Maghzen), establishing a scalable procedure for modelling
seismic risk assessment of cultural heritage (PCM, 2011) and is additional structures. In this process, different approaches to 3D
cross-referenced with ICOMOS principles (ICOMOS, 2003) and modelling were considered, including NURBS modelling based
CEN EN 16096:2012 (CEN, 2012), enabling consistent on mathematical curves and control points for surface
documentation and future comparative monitoring. reconstruction (Diara et al., 2020), mesh-based modelling for
visually driven and texture-oriented representations, and BIM
3.4 Scan-to-HBIM modelling pipeline modelling based on intelligent objects enriched with structured
information. High-resolution spherical panoramas (Insta360
Pro2) supported visual documentation and, where relevant,
texture mapping, improving the readability of materials and

Figure 6. Example of dense clouds acquired by the GeoSLAM.
A) Mosque B) Governor’s Palace (Dar Al Makhzen),
Medhyia, Kenitra (May 2025). © Elaborations by the authors
Figure 8. Example of two spherical panoramic images in
HBIM modelling was implemented to manage irregular equirectangular projection acquired by the Insta360 Pro2. A)
geometries and ensure parametric control, starting from the Mosque B) Governor’s Palace, Kenitra (May 2025). © Photo
filtered and aligned point cloud as a metric backbone. The
by the authors
GeoSLAM ZEB Horizon proved fundamental for the rapid, high-

This contribution has been peer-reviewed.
https://doi.org/10.5194/isprs-archives-XLVIII-2-W12-2026-159-2026 | © Author(s) 2026. CC BY 4.0 License. 162

<!-- p. 5 -->

The International Archives of the Photogrammetry, Remote Sensing and Spatial Information Sciences, Volume XLVIII-2/W12-2026
11th Intl. Workshop 3D-ARCH "3D Virtual Reconstruction and Visualization of Complex Architectures", 10–12 February 2026, Ancona, Italy

decay patterns and strengthening the communication and with Grasshopper, selected for advanced parametric control and
dissemination potential (Paris et al., 2017). extensibility through dedicated plugins. The pre-processed and
georeferenced point cloud—previously filtered and aligned in
3.5 Modeling and BIM integration CloudCompare—provided the geometric backbone of the
workflow, enabling metric control during the generation of
The HBIM modelling phase aimed to produce a semantically rich architectural components.
and geometrically accurate digital representation of the Kasbah, To extract orthogonal profiles for surface reconstruction, the
aligned with international standards for built-heritage VolvoX plugin for Grasshopper was used to slice the point cloud
documentation. Modelling was performed in Rhino 3D coupled along defined X, Y, and Z axes and generate planar sections

Figure 9 Stages of 3D modeling with VolvoX and Grasshopper: from point cloud to geometric reconstruction. © Elaborations by the
authors

Figure 10. On the left, the extraction of profiles from the point cloud; on the right, one of the extracted curves used as reference for
3d modeling. © Elaborations by the authors

Figure 11. On the left, the final 3D model of the mosque; on the right, the spherical panoramas used for texture application and
enhanced visual realism. © Elaborations by the authors

This contribution has been peer-reviewed.
https://doi.org/10.5194/isprs-archives-XLVIII-2-W12-2026-159-2026 | © Author(s) 2026. CC BY 4.0 License. 163

<!-- p. 6 -->

The International Archives of the Photogrammetry, Remote Sensing and Spatial Information Sciences, Volume XLVIII-2/W12-2026
11th Intl. Workshop 3D-ARCH "3D Virtual Reconstruction and Visualization of Complex Architectures", 10–12 February 2026, Ancona, Italy

exported as vector CAD files. These profiles supported NURBS- coverage. The spatial reference framework followed the
based modelling, allowing flexible adaptation to the irregular approach described above: datasets were managed in a projected
geometries and stratified fabric of the fortified complex (fig.9). CRS for metric processing, while GIS-oriented layers and
The transition from surface modelling to BIM objectification was deliverables were provided in WGS84 (EPSG:4326) to ensure
achieved through VisualARQ, a Rhino plugin for semantic interoperability. The Kasbah of Mehdya is located approximately
enrichment and object classification. VisualARQ enables the at Latitude 34° 15′ 50″ N and Longitude 6° 39′ 45″ W. Accuracy
transformation of geometric components into parametric control was supported by GCPs (where available) and/or stable
architectural elements enriched with metadata. Support for the control features, allowing orthophotos and point clouds to be
IFC (Industry Foundation Classes) standard ensured anchored to a global datum and seamlessly overlaid with regional
interoperability within OpenBIM environments (e.g., Revit, cartographic layers.
ArchiCAD), facilitating multidisciplinary collaboration across The transition from point clouds to the information system
architectural, structural, and conservation domains (Bianchini et enabled the transformation of surveyed geometry into spatially
al., 2021). referenced information. By exporting Metashape outputs to GIS
platforms in standard geospatial formats (GeoTIFF for raster
orthophotos and LAS for point clouds), each mapped element of
the Kasbah was associated with unique coordinates. This
acilitated multiscale spatial analysis of decay patterns and
supported the management of conservation data within relational
geodatabases, strengthening the linkage between HBIM-derived
information and the territorial dimension addressed by GIS. In
this integrated perspective, the HBIM–GIS environment supports
long-term monitoring and evidence-based decision-making
processes for site preservation.
A dedicated step addressed the reliability of pre-existing
territorial datasets for urban modelling. A preliminary urban
model was generated in Autodesk InfraWorks 2025 using
“Model Builder” and ArcGIS baseline data. Architectural-scale
evaluation revealed limitations typical of generalised datasets
(e.g., incomplete geometries and unreliable heights), which are
unsuitable for HBIM-informed decision processes. To mitigate
these issues, a high-density SLAM dataset was processed in
FARO Connect, converted to LAS in CloudCompare,
transformed to RCP in Autodesk ReCap, and integrated into
InfraWorks; manual co-registration supported discrepancy
identification and correction. HBIM models were integrated into
InfraWorks (FBX) to enable direct comparison between surveyed
and baseline geometries and to support progressive densification
of the heritage digital twin. Figure 12. Before-and-After Perspective of Geospatial from
Autodesk Infraworks to Data Integration in the software.
\4. Results and discussion
© Elaborations by the authors

Following BIM integration, textures were applied using high- Preliminary results confirm the effectiveness of the proposed
resolution spherical panoramas acquired with the Insta360 Pro2. workflow in unifying survey acquisition, HBIM modelling, and
The imagery was mapped onto 3D surfaces to increase visual GIS-based multiscale analysis within a single information
fidelity and improve the readability of materials and decay environment. The integrated dataset enables consistent
patterns. The same sequence—point-cloud segmentation, documentation of the Kasbah’s construction features and
NURBS reconstruction, BIM conversion, and texture mapping— conservation conditions, supporting the identification and
was applied to the Governor’s Palace (Dar al-Maghzen), localisation of critical issues such as wall settlements, local
establishing a repeatable and scalable procedure for the structural instabilities, invasive vegetation colonisation, and saltdocumentation of additional structures within the Kasbah (fig10). related material deterioration in the most exposed sectors.
By embedding element-level HBIM information within a
3.6 GIS integration and territorial baselines validation territorial GIS framework, the HBIM–GIS integration supports
multiscale spatial queries and correlation analyses between
To link architectural-scale information to the territorial context, mapped pathologies and environmental drivers typical of coastal
HBIM outputs and survey-derived products (GeoTIFF fortified contexts (e.g., sea-salt aerosol exposure, site
orthophotos; LAS point clouds; IFC models) were integrated into morphology, and vegetation dynamics). A key outcome concerns
GIS platforms (QGIS/ArcGIS Pro). The integration of multiscale the critical verification of pre-existing territorial baselines:
data required a rigorous georeferencing and co-registration
framework, ensuring that heterogeneous sources could be
reliably combined within a single GIS environment.
Drone-acquired imagery was processed in Agisoft Metashape
Professional via high-precision aerotriangulation and dense
point-cloud generation. Mobile mapping data acquired via
GeoSLAM were integrated within the same pipeline to
strengthen completeness and robustness, ensuring coherent
fusion between high-resolution local mapping and aerial

This contribution has been peer-reviewed.
https://doi.org/10.5194/isprs-archives-XLVIII-2-W12-2026-159-2026 | © Author(s) 2026. CC BY 4.0 License. 164

<!-- p. 7 -->

The International Archives of the Photogrammetry, Remote Sensing and Spatial Information Sciences, Volume XLVIII-2/W12-2026
11th Intl. Workshop 3D-ARCH "3D Virtual Reconstruction and Visualization of Complex Architectures", 10–12 February 2026, Ancona, Italy

Figure 13. Workflow approach for the mosque of the Kasbah of Mehdya: Through GIS, Scan and BIM integration. © Elaborations by
the authors

comparison between generalised urban datasets and “as-built” activities; the project is co-directed by UIR. The authors also
survey-derived geometry highlights architectural-scale acknowledge the Moroccan cultural heritage authorities for
inaccuracies (e.g., incomplete volumes and unreliable height collaboration, in particular the Ministry of Youth, Culture and
information), confirming the need for progressive densification Communication – Department of Culture – General Secretariat –
of the heritage digital twin based on high-precision survey data Directorate of Cultural Heritage of the Kingdom of Morocco, the
and HBIM modelling. Regional Directorate for Cultural Heritage Conservation of
Beyond file-format interoperability, the workflow reduces Rabat–Salé–Kénitra, and the Provincial Directorate for Cultural
interpretive ambiguity by grounding geometric reconstruction Heritage Conservation of Kénitra. The authors also thank
and semantic attribution on survey evidence, and improves ETAFAT (3DRC-BIM Department) for conducting a
operational efficiency by combining UAV coverage, rapid comprehensive UAV survey campaign at the Kasbah of Mehdya,
SLAM mapping, and targeted high-resolution imagery. The including aerial LiDAR acquisitions and drone-based
resulting information framework establishes a scalable basis for photogrammetry. The project was carried out by the Institute of
conservation prioritisation and scenario definition, to be Heritage Science of the Italian National Research Council (CNR
progressively refined through quantitative indicators and ISPC) with MAECI institutional recognition and the support of
repeated monitoring campaigns. In this perspective, a WebGIS- the European Research Infrastructure for Heritage Science (Ebased dissemination layer is envisaged to facilitate multi-actor RIHS) within a bilateral scientific cooperation programme. The
consultation and collaborative updating of georeferenced scientific mission was led by Elena Gigliarelli, head of the
contents over time. BHiLab at CNR ISPC (Rome).

\5. Conclusions and prospects References

The HBIM–GIS workflow developed for the Kasbah of Mehdya Ajaraam, R., Chergui, A., El Bouzidi, S., 2025: The Historic
provides a methodological contribution to the documentation and Sebou Basin: An asset of universal value. Ex Novo: Journal of
conservation of vulnerable coastal fortified heritage. By Archaeology, 9, 5–21. doi:10.32028/exnovo-vol-9-pp.5-21.
integrating multiscale survey datasets, semantically structured
HBIM modelling, and GIS-based geospatial analysis within a Bernabei, L., Calderoni, L., Calvano, M., Martinelli, L.,
single heritage digital-twin framework, the approach strengthens Calcerano, F., Gigliarelli, E., 2023: Integrated digital processes
the connection between architectural knowledge (materials, for the management and conservation of large cultural sites and
techniques, decay patterns) and territorial context, supporting historic building complexes: the former Florio plant of the
monitoring and evidence-based decision-making processes. Favignana tuna fishery. 3D Modeling & BIM 2023 - Soluzioni per
The main contribution lies in a replicable and modular procedure il Cultural Heritage. DEI, Roma, 20–31.
based on interoperable standards and an open-data orientation, hdl.handle.net/20.500.14243/464300
enabling transferability to other stratified fortified sites. Future
Bianchini, C.; Attenni, M.; Potestà, G., 2021: Regenerativedevelopments will focus on: (i) extending HBIM coverage to
Design Tools for the Existing City: HBIM Potentials. Inadditional structures of the complex; (ii) integrating
Rethinking Sustainability Towards a Regenerative Economy—complementary diagnostic datasets (materials, microclimate,
Future City; Springer: Cham, Switzerland; Volume 15.and—where available—geotechnical and structural
https://doi.org/10.1007/978-3-030-71819-0_2investigations); (iii) implementing a WebGIS interface for
consultation and collaborative updating; and (iv) exploring Bruno, N., Rechichi, F., Achille, C., Zerbi, A., Roncella, R., Fassi,
predictive approaches (e.g., machine-learning-assisted trend F., 2020: Integration of Historical GIS Data in a HBIM System.
analysis) to support monitoring of degradation across repeated The International Archives of the Photogrammetry, Remote
campaigns. Further work will also address interoperability with Sensing and Spatial Information Sciences, XLIII-B4-2020.
territorial-scale BIM environments to strengthen integration with
planning and management workflows. Bueno Soto, F.J., 2010: Larache y La Mamora: dos
fortificaciones españolas en tiempos de Felipe III, Aldaba (34),
Acknowledgements 51–96. doi.org/10.5944/aldaba.34.2010.20519

The authors acknowledge the Italian Ministry of Foreign Affairs Chiabrando, F., Donadio, E., Sammartano, G., Spanò, A., 2016:
and International Cooperation (MAECI) and the Italian Embassy La tecnologia laser scanning per la valutazione statica delle
in Rabat for institutional support. Special thanks are extended to strutture storiche. Geomedia (4), 12–17.
the Director of the École d’Architecture de Rabat at the
Université Internationale de Rabat (UIR) for enabling fieldwork Coindreau, R., 1946: La Casbah de Mehdia. Les éditions la porte,
Rabat, 65–70.

This contribution has been peer-reviewed.
https://doi.org/10.5194/isprs-archives-XLVIII-2-W12-2026-159-2026 | © Author(s) 2026. CC BY 4.0 License. 165

<!-- p. 8 -->

The International Archives of the Photogrammetry, Remote Sensing and Spatial Information Sciences, Volume XLVIII-2/W12-2026
11th Intl. Workshop 3D-ARCH "3D Virtual Reconstruction and Visualization of Complex Architectures", 10–12 February 2026, Ancona, Italy

Diara, F., & Roggero, M., 2023: The Frinco Castle: From an Sammartano, G., Avena, M., Cappellazzo, M., Spanò, A., 2021:
Integrated Survey to 3D Modelling and a Stratigraphic Analysis Hybrid GIS-BIM Approach for the Torino Digital-Twin: the
for Helping Knowledge and Reconstruction. Remote Sensing, Implementation of a Floor-Level 3D City Geodatabase. The
15(19), 4874. doi.org/10.3390/rs15194874 International Archives of the Photogrammetry, Remote Sensing
and Spatial Information Sciences, XLIII-B4-2021.
Diara, F. and Rinaudo, F., 2020: Building Archaeology
documentation and analysis through Open Source HBIM Saladin, H., 1913: Les monuments de Méhédiya (Maroc).
solutions via NURBS modelling. Int. Arch. Photogramm. Remote Bulletin archéologique du comité des travaux historiques et
Sens. Spatial Inf. Sci., XLIII-B2-2020, 1381–1388. scientifiques, 267–283.
doi.org/10.5194/isprs-archives-XLIII-B2-2020-1381-2020

Direction Régionale de la Culture, 2020. Fiche sur la Kasbah,
Rabat.

European Committee for Standardization (CEN), 201. EN
16096:2012 – Conservation of cultural property – Condition
survey and report of built cultural heritage. Brussels: CEN.

Gigliarelli, E., Pontrandolfi, R., Calcerano, F., 2020:
Regeneration and enhancement strategies of minor historical
settlements and use of ICT tools for multi-scale analyses and
integrated assessments. The experience of the village of Artena.
Valori e Valutazioni, 25, 75–82.

International Council on Monuments and Sites (ICOMOS), 2003.
Principles for the analysis, conservation and structural restoration
of architectural heritage

Lakhdar, K., 2026: Mahdiyya Kasbah. Discover Islamic Art
(Museum With No Frontiers).

Limongiello, M., Musmeci, D., Radaelli, L., Chiumiento, A., di
Filippo, A., Limongiello, I., 2025: Parametric GIS and HBIM for
Archaeological Site Management and Historic Reconstruction
Through 3D Survey Integration. Remote Sensing, 17(6), 984.

Matrone, F., Colucci, E., De Ruvo, V., Lingua, A., Spanò, A.,
2019: HBIM in a Semantic 3D GIS Database. The International
Archives of the Photogrammetry, Remote Sensing and Spatial
Information Sciences, XLII-2/W11.

Paris, L., Calvano, M., Nardinocchi, C., 2017: Web Spherical
Panorama for Cultural Heritage 3D Modeling. In: New Activities
For Cultural Heritage. Springer, Cham. doi.org/10.1007/978-3319-67026-3_20

Pepe, M., Costantino, D., Alfio, V. S., Garofalo Restucci, A.,
Papalino, N. M., 2021: Scan to BIM for the digital management
and representation in 3D GIS environment of cultural heritage
site. Journal of Cultural Heritage, 50, 115–125.

Pepe, M., Palumbo, D., Dewedar, A. K. H., Spacone, E., 2024:
Toward to Combination of GIS-HBIM Models for Multiscale
Representation and Management of Historic Center. Heritage,
7(1).

Pozzoni, L., Barazzetti, L., Cuca, B., Oteri, A. M., 2024: An
Integrated HBIM-GIS Digital Environment for Heritage
Preservation and Enhancement in the Inner Italian Territory. The
International Archives of the Photogrammetry, Remote Sensing
and Spatial Information Sciences, XLVIII-2/W4-2024.

Raoui, S., 2010: “Casbah de Mahdiya”: une fortification
espagnole au coeur de l’atlantique. Aldaba (34), 97–144.
doi.org/10.5944/aldaba.34.2010.20514

Sammartano, G., Avena, M., Fillia, E., Spanò, A., 2023:
Integrated HBIM-GIS Models for Multi-Scale Seismic
Vulnerability Assessment of Historical Buildings. Remote
Sensing, 15(3), 833.

This contribution has been peer-reviewed.
https://doi.org/10.5194/isprs-archives-XLVIII-2-W12-2026-159-2026 | © Author(s) 2026. CC BY 4.0 License. 166
