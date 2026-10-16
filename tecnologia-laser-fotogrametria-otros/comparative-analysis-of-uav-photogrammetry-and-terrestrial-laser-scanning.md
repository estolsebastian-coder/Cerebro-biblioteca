---
type: libro
title: "Comparative Analysis of UAV Photogrammetry and Terrestrial Laser Scanning"
author: ""
categoria: "Tecnología láser, fotogrametría, otros"
paginas: 8
extraccion: "texto"
fuente: "local:E:/Biblioteca digital/Tecnología láser, fotogrametría, otros/Comparative Analysis of UAV Photogrammetry and Terrestrial Laser Scanning.pdf"
convertido: 2026-10-13
---

# Comparative Analysis of UAV Photogrammetry and Terrestrial Laser Scanning

> Texto extraído de `Tecnología láser, fotogrametría, otros/Comparative Analysis of UAV Photogrammetry and Terrestrial Laser Scanning.pdf` (8 páginas, texto). El PDF original está en el disco E: (Biblioteca digital); `<!-- p. N -->` marca el inicio de cada página.

<!-- p. 1 -->

ISPRS Annals of the Photogrammetry, Remote Sensing and Spatial Information Sciences, Volume X-5/W4-2025
Philippine Geomatics Symposium (PhilGEOS) 2025 "Enhancing Human Quality of Life through Geospatial Technologies",
24–25 November 2025, Quezon City, Philippines

Comparative Analysis of UAV Photogrammetry and Terrestrial Laser Scanning
for 3D Building Reconstruction

Jarence David D. Casisirano1, Alexis Richard C. Claridades1

1Department of Geodetic Engineering, University of the Philippines Diliman, Quezon City, Philippines
\-{jdcasisirano, acclaridades}@up.edu.ph

Keywords: UAV photogrammetry, TLS, point cloud comparison, 3D building reconstruction, accuracy assessment

Abstract

Recently, unmanned aerial vehicle (UAV) photogrammetry has gained popularity as an alternative to terrestrial laser scanners (TLS)
for collecting 3D information, particularly for building models. However, comprehensive comparative assessments of the two methods
remain limited in the literature. This study compares TLS and UAV-based photogrammetry for 3D building modeling. 3D point cloud
data is collected in a study area using both methods, with ground truth data collected using a total station. The resulting point clouds
were evaluated through multiple quantitative metrics, including RMSE, cloud-to-cloud distance, surface area, point density, planarity,
roughness, and surface variation, in addition to qualitative assessments of model completeness and feature reconstruction. Results show
that TLS achieved lower RMSE and smoother, more accurate facade geometry, particularly in near-ground areas. However, this method
failed to capture rooftop structures due to occlusion. The UAV model successfully captured upper structures and finer architectural
features but showed noisier surfaces and missing data at the building base. Surface geometry analyses further revealed that TLS outputs
were more planar and consistent. Meanwhile, UAV data exhibited greater variation and reconstruction artifacts. The findings highlight
the strengths and limitations of each method depending on the modeling objective. While UAV photogrammetry may be sufficient for
applications such as solar potential estimation or volume analysis, TLS is more suitable for high-precision tasks like facade
documentation or structural monitoring. For projects requiring both accuracy and coverage, a hybrid approach is recommended. This
study emphasizes their complementary value and offers guidance for urban-scale 3D data acquisition strategies.

\1. Introduction particularly in the Philippines, where 3D modeling and digital
twin technologies are still in the early stages of maturity. Most
1.1 Background of the Study previous studies focus on less detailed but large-scale 3D
mapping using high-end equipment such as Light Detection and
As modern cities rapidly shift toward sustainable and smart Ranging (LiDAR) systems, leaving a gap in understanding how
infrastructure, digital twins and detailed 3d building models consumer-level UAV systems perform against TLS systems in
become increasingly important. Ketzler et al. (2020) stated that micro-scale contexts (Santillan et al., 2015; Villanueva et al.,
“3D city model” is still the most prominent term in the field of 2015). This paper addresses that gap by presenting a case study
3D GIS and that the term “digital twin” has seen a significant comparing 3D building point clouds generated using TLS and
increase in academic literature, particularly in the context of UAV photogrammetry. The comparison is supported by ground
cities and built environment studies. Rightfully so, accurate and truth data collected via total station measurements.
detailed 3D building models play a pivotal role in many modern
geospatial applications, including but not limited to urban 1.2 Significance of the Study
planning, infrastructure monitoring, disaster management, and
climate change adaptation (Fan et al., 2021; Riaz et al., 2023). This study contributes to the growing field of 3D geospatial data
acquisition and analysis by providing a head-to-head comparison
Among the many techniques available to produce accurate 3D of TLS and low-cost UAV photogrammetry for building-scale
building models, terrestrial laser scanners (TLS) and unmanned modeling. While TLS has traditionally been viewed as the
aerial vehicles (UAVs) are two of the most common. TLS can standard in accuracy and completeness, recent advancements in
capture highly accurate, dense, and geometrically reliable point photogrammetry and drone camera technology suggest that even
clouds. However, TLS comes with significant challenges, consumer-grade UAVs can produce, to some extent, competitive
including price, technical know-how, and occlusions brought results. The findings of this study aim to support geospatial
about by line-of-sight (LOS) limitations. On the other hand, UAV professionals, urban planners, and researchers in selecting
photogrammetry has gained popularity in recent years because of appropriate data acquisition techniques for different types of
its portability, cost-effectiveness, and ability to rapidly collect applications. Understanding the trade-offs between these two
data remotely from a range of perspectives (Dominici et al., 2017; methods is critical for digital twin development, urban planning,
Fernández-Hernández et al., 2015). With the emergence of and 3D modeling, especially in contexts where cost, portability,
consumer-grade drones, even non-expert users can now generate and time constraints are significant considerations. This paper
3D spatial data with ease. Still, the quality and accuracy of UAV- aims to help practitioners and researchers who must balance these
derived point clouds will vary depending on factors such as competing factors in their workflows make informed decisions.
camera quality, lighting conditions, target object properties, and
flight path designs, to name a few. 1.3 Research Objectives

While, independently, both technologies are already well This study aims to evaluate and compare the performance of
established, academic literature discussing the comparative terrestrial laser scanning (TLS) and UAV photogrammetry in
assessment between TLS and UAV photogrammetry is scarce, generating 3D building models. It involves generating point

This contribution has been peer-reviewed. The double-blind peer-review was conducted on the basis of the full paper.
https://doi.org/10.5194/isprs-annals-X-5-W4-2025-143-2026 | © Author(s) 2026. CC BY 4.0 License. 143

<!-- p. 2 -->

ISPRS Annals of the Photogrammetry, Remote Sensing and Spatial Information Sciences, Volume X-5/W4-2025
Philippine Geomatics Symposium (PhilGEOS) 2025 "Enhancing Human Quality of Life through Geospatial Technologies",
24–25 November 2025, Quezon City, Philippines

cloud datasets of the same structure using a DJI Mini 3 Pro drone 2. Methodology
and a terrestrial laser scanner. The study also assesses the
accuracy and quality of the UAV-derived point cloud using TLS This section discusses the methodology for this study, as
data and total station measurements as references and evaluates illustrated and summarized in Figure 1.
the models based on various spatial metrics. Finally, the study
identifies the strengths and limitations of each method in terms
of spatial quality and provides recommendations on their
suitability for various geospatial modeling applications.

1.4 Review of Related Work

TLS has long been established as a benchmark for acquiring
highly accurate and dense 3D data in the built environment
(Sternberg et al., 2004). By emitting laser pulses and measuring
their returns, TLS can capture precise geometric details with
millimeter-level accuracy (Stenz et al., 2020), making it preferred
for reliable as-built documentation and structural monitoring.
However, it is limited by high equipment costs, restricted
mobility, and occlusions from line-of-sight (LOS) obstructions.

In contrast, UAV photogrammetry reconstructs 3D models from
overlapping aerial images, with modern software automating
image alignment and point cloud generation. Its affordability,
ease of deployment, and rapid data acquisition have driven its
popularity (Nex et al., 2022) and it has been successfully applied Figure 1. Overall methodology workflow.
in construction monitoring, disaster response, and archaeology
(Dominici et al., 2017; Fernández-Hernández et al., 2015). 2.1 Study Area
Compact, consumer-grade UAVs have made 3D spatial data
collection more accessible, though quality remains dependent on The study was conducted at the National Institute of Molecular
environmental conditions, image resolution, surface texture, and Biology and Biotechnology (NIMBB), located within the
flight planning. In urban settings, insufficient overlap, motion University of the Philippines Diliman campus in Quezon City,
blur, and narrow-corridor occlusions may produce gaps in the Philippines (approximately 14.65072° N, 121.07157° E), as
data (Wu et al., 2018). shown in Figure 2.

Both TLS and UAV photogrammetry have proven valuable for The building was selected as the target structure due to its well3D building modeling, each with unique strengths. Comparative defined geometry, multiple accessible facades, and relatively
studies typically evaluate geometric accuracy, completeness, and clear surrounding space, which are advantageous characteristics
structural fidelity, using metrics such as cloud-to-cloud (C2C) for both TLS and UAV photogrammetry. The building is a multidistance (Kamnik et al., 2019; Liu et al., 2023), root mean square story facility composed of multiple rectangular artifacts and
error (RMSE) from ground control points or total station data, overhangs. It also has a uniform white paint with trees present in
point density, completeness, and sometimes roughness, planarity, the surrounding area of the building, both of which introduce
and volume deviation. Kersten & Lindstaedt (2012) found TLS difficult but necessary challenges in aerial image acquisition and
denser and more accurate, while photogrammetry provided processing. This specific setting reflects common use-case
adequate detail for visualization. Fernández-Hernández et al. scenarios for 3D building modeling in urban areas using TLS and
(2015) showed UAV photogrammetry could produce accurate, UAV photogrammetry. It provides a relevant test for evaluating
interpretable models with sufficient overlap and camera the performance and suitability of low-cost UAV
calibration. photogrammetry compared to TLS in similar built environments.

Most prior comparisons use high-end UAVs and TLS in open,
controlled settings. Fewer assess low-cost drones, which lack
RTK modules and are more sensitive to environmental
conditions. Micro-scale studies such as on single buildings or in
dense urban contexts are especially scarce, particularly in the
Philippines. This study addresses these gaps by comparing point
clouds from a consumer-grade UAV (DJI Mini 3 Pro) and a TLS
unit for a single building in a micro-scale urban context. Ground
truth from total station measurements provides an independent
accuracy benchmark, offering a practical evaluation of low-cost
3D data acquisition workflows in real-world conditions.
Figure 2. Study area (Google Earth, 2025)

This contribution has been peer-reviewed. The double-blind peer-review was conducted on the basis of the full paper.
https://doi.org/10.5194/isprs-annals-X-5-W4-2025-143-2026 | © Author(s) 2026. CC BY 4.0 License. 144

<!-- p. 3 -->

ISPRS Annals of the Photogrammetry, Remote Sensing and Spatial Information Sciences, Volume X-5/W4-2025
Philippine Geomatics Symposium (PhilGEOS) 2025 "Enhancing Human Quality of Life through Geospatial Technologies",
24–25 November 2025, Quezon City, Philippines

2.2 Data Collection 2.2.2 TLS Data Collection: TLS data collected from a
previous study (Ingles et al., 2024) in the same area was used in
2.2.1 UAV Data Collection: The data acquisition process for this paper. The TLS data collection was conducted using a
the building followed a segmented approach. The building was handheld Foxtech SLAM100 device. It utilizes simultaneous and
divided into five main sections: a nadir (top-down) view of the localization mapping technology for mobile 3D point cloud
building and its immediate surroundings and one view for each acquisition. The scanning followed a predefined walking route
of the four cardinal sides. As a result, aerial image acquisition around the building. One operator carried the scanner, and
was not continuous; the drone was manually repositioned another monitored the trajectory using the SLAM GO
between segments to capture each facade individually. This application. A steady walking pace of approximately 5km/h was
strategy was necessary due to space limitations and the presence ensured under clear weather conditions to ensure optimal data
of surrounding trees on all sides of the building, which restricted quality, and a 60-second initialization phase was completed
continuous flight paths. All flights were conducted during before scanning. To reduce the noise in the point cloud, the best
favorable weather conditions—either around 10:00 AM or 1:00 effort was made to minimize movement during acquisition. This
PM—under clear skies and bright sunlight, providing adequate method allowed access to areas difficult to capture using tripodillumination for capturing surface details. mounted scanners. However, care was taken to maintain
consistent motion and scanner orientation.
Initially, flight automation and pre-programmed waypoints using
advanced drone software were heavily considered to streamline 2.2.3 Ground Truth Measurements: Ground truth
data collection. However, this approach proved virtually measurements were obtained using a total station (TS). The TS
impossible in practice due to the physical constraints of the study was operated in reflector-less mode, providing an independent
site. The presence of narrow gaps, tight corners, and tree reference dataset for evaluating the geometric accuracy of the
branches extending close to the building walls made it difficult point clouds generated by UAV photogrammetry and TLS.
to define safe flight paths with adequate clearance. Furthermore, Establishing a conventional geodetic or project control network
flight planning involved not only horizontal trajectories for nadir using known reference points for TS setup was not feasible for
views but also vertical paths for capturing building facades, the study due to environmental constraints such as dense
further complicating the process and increasing operational risk. vegetation and obstructed sightlines. Instead, the TS was
These challenges, combined with the potential for GPS signal positioned at stable and site-appropriate locations near each
degradation and collision hazards during automated flights, led building facade. It was operated locally to collect the relative
to the decision to carry out all image acquisition through manual coordinates of identifiable structural features and artifacts, such
piloting. This approach provided precise control over both drone as building corners and window edges. This process was
positioning and camera orientation, thereby ensuring data quality conducted separately for each facade, resulting in four distinct
and equipment safety during close-range image captures. local coordinate systems—each internally consistent but not
references to a global reference network. While this approach did
UAV-based imagery was acquired using the DJI Mini 3 Pro, a not allow for absolute georeferencing of the ground truth
compact, consumer-grade remotely piloted aircraft (RPA) measurements, it enabled the collection of dimensionally valid
equipped with a 1/1.3” CMOS camera capable of capturing 48 and reliable measurements within each localized setup. This
MP still images. A total of 1,392 images were collected during adaptive methodology, though unconventional, was appropriate
the mission and distributed across five main building sections: 50 for the study’s primary goal of evaluating the geometric fidelity
images for the nadir view, 406 for the front facade (south-facing), of the 3D reconstructions rather than their absolute positioning.
527 for the back facade (north-facing), 265 for the right facade The relative coordinates collected were sufficient for calculating
(east-facing), and 144 for the left facade (west-facing). The physically meaningful dimensions such as object length and
number of images per facade varied due to differences in wall widths used for quantitative assessment of model accuracy in
dimensions, drone-to-surface distance, and shooting density relation to real-world building geometry.
driven by on-the-fly overlap estimation.
2.3 Processing Workflow
Because the image acquisition was performed manually, overlap
percentages were only estimated based on flight trajectory and 2.3.1 UAV Photogrammetry Processing: First, a custom
shooting intervals. An approximate 60% forward overlap and Python script was used to group the captured UAV images based
60% side overlap were achieved across most segments. Image on the acquisition time stamps, effectively segregating them into
capture for the facades followed a vertical sweeping approach in five sets corresponding to the nadir view and each of the four
which the drone was flown up and down to capture multiple building facades. All the UAV photogrammetric data were
height levels per wall. As a result, the altitude varied processed using Agisoft Metashape following a structured and
continuously throughout this process, in contrast to the nadir semi-automated workflow. The image groups were imported into
segment, which was captured at a relatively constant altitude of separate chunks within the Metashape project to allow for
approximately 50 meters. Additionally, the drone’s lateral independent processing. Within each chunk, images were aligned
distance from the facades was dynamically adjusted to avoid using medium accuracy settings that enabled both generic and
nearby obstructions, such as tree branches, which posed collision reference preselection. After alignment, dense point clouds were
risks. While these adjustments ensured safe proximity and generated via depth map computation with medium quality and
equipment protection, they also contributed to variations in mild filtering. This process was repeated for each of the five
acquisition geometry. Nevertheless, these adaptations were chunks. To integrate the datasets, shared markers were manually
necessary due to the tight spatial constraints and environmental placed on common architectural features across the chunks for a
obstructions present at the study site. marker-based chunk alignment. Finally, the chunks were then
merged into a unified project while preserving their respective
point clouds and tie points.

This contribution has been peer-reviewed. The double-blind peer-review was conducted on the basis of the full paper.
https://doi.org/10.5194/isprs-annals-X-5-W4-2025-143-2026 | © Author(s) 2026. CC BY 4.0 License. 145

<!-- p. 4 -->

ISPRS Annals of the Photogrammetry, Remote Sensing and Spatial Information Sciences, Volume X-5/W4-2025
Philippine Geomatics Symposium (PhilGEOS) 2025 "Enhancing Human Quality of Life through Geospatial Technologies",
24–25 November 2025, Quezon City, Philippines

2.3.2 TLS Point Cloud Integration: The initially 3.1 Visual Comparison of Point Clouds
unreferenced TLS-derived point cloud was also imported into
Metashape as a separate chunk. Using the same marker-based Figure 3 shows the point clouds produced from UAV
alignment method, it was aligned to the UAV model. Markers photogrammetry and TLS. These outputs exhibit contrasting
were placed on visually identifiable features (e.g., building qualities that reflect their respective acquisition methods. The
corners and facade edges) present in both datasets. The alignment UAV-derived model captures comprehensive top-down and
was performed without adjusting the scale of the TLS point cloud angled views. It effectively reproduced roof geometry and facade
to ensure that the original dimensions of both the datasets were textures with realistic color. However, occlusion due to
preserved. This method allowed for a meaningful comparison vegetation and the presence of floating artifacts slightly
between the UAV and TLS point clouds. diminishes its structural definition. On the other hand, the TLS
point cloud resulted in clearer wall and base geometry because of
2.3.3 Ground Truth Data Processing: The ground truth data its close-range and ground-based acquisition. Still, it suffers from
from the total station contains relative ENZ (Easting, Northing, substantial vegetation obstruction, introducing extraneous points,
Elevation) coordinates. Using these coordinates, linear distances and lacks color information, which limits visual interpretability.
between structural features, such as wall lengths and window These visual and structural differences formed the basis for the
spans, were computed directly. Although not georeferenced, succeeding quantitative and qualitative assessments.
these measurements were dimensionally accurate and provided a
reliable basis for comparing real-world dimensions against those
derived from point cloud reconstructions.

2.4 Point Cloud Assessment

The accuracy and quality of the 3D building models were
assessed using selected metrics. All evaluations were conducted Figure 3. Point clouds derived from UAV (left) and TLS (right)
using CloudCompare, an open-source point cloud analysis
platform. The first metric was the completeness assessment. It 3.2 RMSE of Measured Distances
involved a visual comparison of both datasets to identify missing
or occluded regions. Then, the root mean squared error (RMSE) A total of 23 architectural features across all the building façades
of measured distances was calculated by comparing real-world were measured and compared against total station ground truth
lengths obtained from total station measurement data with data to evaluate the dimensional accuracy of the UAV- and TLSequivalent dimensions extracted from the UAV- and TLS- derived point clouds. The resulting overall RMSE is 0.120 meters
derived models. Key features such as wall windows and wall for the UAV and 0.070 meters for the TLS, as shown in Table 1.
lengths were measured. Second, C2C deviation analysis was The TLS consistently achieved lower absolute errors across most
performed to quantify the spatial differences between UAV and features, especially in horizontal spans such as façade and
TLS point clouds. The TLS dataset was used as the reference. window widths. These errors indicate that, overall, TLS provided
The statistical outputs were generated to assess consistency a more accurate representation of real-world distances. For
across surfaces. Finally, point cloud density was calculated to context, previous UAV-based building modeling studies have
compare the resolution of each dataset. This calculation provided reported RMSE values as low as 0.015 m when conditions are
insight into the level of surface detail captured by each method. optimal (Sani et al., 2022).

The point clouds were also converted into triangulated mesh Facade UAV RMSE (m) TLS RMSE (m)
models, which were manually segmented by building sections Back Facade 0.1106 0.0601
using 3D processing software to calculate surface areas. Right Facade 0.0189 0.0753
Planarity, roughness, and surface variation analyses were Left Facade 0.1216 0.0305
performed using neighborhood-based geometric descriptors to Front Facade 0.1613 0.0882
quantify surface flatness, local texture deviations, and changes in Overall 0.1195 0.0697
surface normal orientation, respectively. Scalar field
Table 1. RMSE Comparison per Facade
visualizations and histograms were used to interpret geometric
characteristics. Additionally, a qualitative assessment was
The most pronounced UAV error was recorded on the front
conducted by visually inspecting the models’ structure,
facade (0.1613 m), likely due to visual obstructions such as trees
completeness, and mesh quality, with attention to occlusions,
near the building entrance. In contrast, the TLS data showed the
artifacts, and fine architectural features. All data processing and
highest error on the right facade (0.0753 m). However, this is still
analysis were performed using Agisoft Metashape and
relatively low compared to UAVs. Interestingly, the left facade
CloudCompare.
showed the most favorable result for TLS (0.0305 m RMSE),
possibly due to minimal obstructions and simpler geometry on
\3. Results and Discussion
that side. While the UAV-derived model demonstrated slightly
higher RMSE overall, the deviations remained within theThis section presents a comparative analysis of the 3D data
commonly accepted tolerance of a few centimeters for buildinggenerated from UAV photogrammetry and TLS. These datasets
modeling, considering equipment grade and environmentalwere also evaluated against ground truth data obtained from the
limitations during acquisition (Mirza et al., 2023; Sani et al.,total station survey. Quantitative metrics were checked, and
2022). The above results emphasize the strength of TLS inqualitative assessments were performed to evaluate geometric
accurate facade reconstruction while also demonstrating thefidelity, surface quality, and completeness. These results
UAV model’s adequacy in areas with less occlusion.collectively provide insight into the relative performance and
limitations of UAV- and TLS-derived point clouds.

This contribution has been peer-reviewed. The double-blind peer-review was conducted on the basis of the full paper.
https://doi.org/10.5194/isprs-annals-X-5-W4-2025-143-2026 | © Author(s) 2026. CC BY 4.0 License. 146

<!-- p. 5 -->

ISPRS Annals of the Photogrammetry, Remote Sensing and Spatial Information Sciences, Volume X-5/W4-2025
Philippine Geomatics Symposium (PhilGEOS) 2025 "Enhancing Human Quality of Life through Geospatial Technologies",
24–25 November 2025, Quezon City, Philippines

3.3 Cloud-to-Cloud (C2C) Distance Analysis TLS data on the roof. Since the TLS scan lacked visibility for
elevated horizontal surfaces such as the roof, large discrepancies
To evaluate geometric alignment between the UAV- and TLS- in those regions are expected and do not necessarily indicate
derived point clouds, a C2C distance analysis was conducted modeling error. Instead, these results underscore the need for
using the TLS dataset as the reference, resulting in the top-down integrating complementary datasets when full coverage is
C2C scalar field map in Figure 4 and the histogram of C2C required. These results affirm that while both datasets are mostly
distances shown in Figure 5. While the TLS dataset lacked point aligned in the building’s primary geometry, further refinement is
coverage for the roof due to its ground-based acquisition needed in occlusion-prone zones.
perspective, the top-view comparison was still conducted to
assess alignment across the building’s visible horizontal and 3.4 Point Cloud Density
upper façade structures. Roof regions in the TLS dataset appear
as high-deviation zones in the C2C results; however, these Surface density analysis reveals significant contrasts between the
differences are not indicative of modeling errors in either dataset, TLS and UAV-derived point clouds in terms of data resolution,
but rather a direct consequence of occlusion and incomplete completeness, and spatial coverage. The TLS dataset showed
overlap. This reinforces the complementary nature of the two extremely high-density values, particularly concentrated near the
methods and highlights the potential benefits of integrating scanner’s position—primarily at the base of the scan box—where
UAV-derived roof data with TLS-acquired facade detail for oversampling often occurred, while very few points were
complete building coverage. captured on the roof. This uneven distribution is a result of the
TLS scanner’s ground-based position, which leads to dense point
capture near the scanner but limited visibility and data loss in
higher, occluded areas such as the roof. These patterns
underscore the occlusion-sensitive limitation of TLS when used
alone for capturing complex vertical structures.

The UAV dataset, as reflected in the surface density distribution
shown in Figure 6, demonstrated a more consistent point density
overall. Unlike the TLS model, which exhibited a widespread due
to localized high-density clusters near the scanner, the UAV point
cloud shows a tighter range of values with fewer extreme outliers.
This consistency can be attributed to uniform flight coverage and Figure 4. Top View C2C Absolute Distance Visualization
overlapping image acquisition. While the UAV’s maximum
density was lower than that of TLS, the reduced SD suggestsAs visualized in Figure 4, most deviations fall within the blue-to-
more reliable coverage across the building envelope. However,green spectrum. These deviations correspond to sub-meter
the density near ground-level facade sections remained limiteddifferences. However, significant deviations were observed in the
due to the difficulty of safely piloting the UAV at low altitudesroof—represented by circular zones with higher C2C values.
while maintaining sufficient overlap. Overall, the histogramThis result was primarily caused by the TLS dataset lacking point
supports the UAV’s strength in producing a more balanced andcoverage for the roof area, leading to exaggerated discrepancies
predictable data distribution despite its lower peak density.in those areas when compared to the fully captured UAV model.

Figure 5. Distribution of C2C Distances between Point Clouds Figure 6. UAV point cloud surface density value distribution

In contrast, the facade walls exhibit consistent alignment with 3.5 Surface Area
only minimal variation along vertical surfaces where both
datasets have complete overlap. The histogram in Figure 5 Surface area measurements for each building section were
confirms this spatial observation. The distribution is right- extracted from both UAV- and TLS-derived meshes and are
skewed, with a peak around 1.2 meters and a long tail extending summarized in Table 2. The UAV model recorded the highest
to higher values, further supporting the presence of localized surface area for the roof (1495.11 m²), while the TLS reported no
outliers and roof deviations. The computed mean distance of roof data due to its limited vertical field of view. On the facades,
1.217 m and standard deviation (SD) of 1.301 m reflects the TLS generally produced larger surface areas, notably on the
moderate geometric variation, primarily due to the absence of back facade (1007.95 m² TLS vs. 869.67 m² UAV) and right

This contribution has been peer-reviewed. The double-blind peer-review was conducted on the basis of the full paper.
https://doi.org/10.5194/isprs-annals-X-5-W4-2025-143-2026 | © Author(s) 2026. CC BY 4.0 License. 147

<!-- p. 6 -->

ISPRS Annals of the Photogrammetry, Remote Sensing and Spatial Information Sciences, Volume X-5/W4-2025
Philippine Geomatics Symposium (PhilGEOS) 2025 "Enhancing Human Quality of Life through Geospatial Technologies",
24–25 November 2025, Quezon City, Philippines

facade (325.17 m² TLS vs. 256.78 m² UAV). These of 0.48 and a comparable spread (std. Dev. 0.22). This value
measurements suggest that the TLS system more effectively suggests a more diverse spread of geometric surface conditions.
captured lower facade sections and vertical geometry, likely due The corresponding point cloud map reflects this with more
to its closer proximity to the structure. In contrast, the UAV had scattered mid-range planarity values, particularly in areas near
difficulty capturing near-ground areas, which were affected by windows and vegetation intrusions at the base. These results
altitude restrictions and obstructions such as trees. emphasize that while TLS provides high-resolution data, it is
more sensitive to local structural and textural variations,
Surface Area Surface Area especially in occluded or cluttered regions, whereas the UAV
Facade (m²) – UAV (m²) – TLS data benefits from its holistic visibility, producing smoother
Front (South) 744.82 774.475 facade representations in open areas like the building’s rear.
Back (North) 869.668 1007.95
3.6.2 Roughness: The comparison of the surface roughness of
Left (West) 149.944 143.741 the back facade, illustrated in Figure 8, reveals a clear distinction
Right (East) 256.779 325.168 between TLS and UAV datasets in terms of localized surface
irregularities. Cooler blue tones dominate the TLS-derived pointRoof (Top) 1495.11 0
cloud (bottom-left). This result indicates consistently low
Table 2. Surface area per facade derived from the point clouds
roughness values across most of the facade surface. This visual
uniformity is supported by the TLS histogram (top-left), where
These discrepancies may also have resulted from residual mesh
values are distributed more broadly but still skewed toward the
artifacts and the manual nature of surface segmentation, where lower end. The broader spread may reflect geometric details
boundary delineation was subject to researcher judgment and
captured by the scanner, such as window frames, vertical edges,
software limitations. Overestimated values in the TLS model,
and surface protrusions that produce slight variability but do not
especially along tree-covered facades, may reflect fused
compromise the overall smoothness of the wall plane.
vegetation rather than true wall geometry. Meanwhile, the UAV
model likely underestimates facade areas due to missing lower
segments. Overall, UAV data performed better in capturing
elevated and roof structures, while TLS excelled in vertical and
near-ground coverage. This complementarity reinforces the value
of integrating both methods for full-envelope structural coverage.

3.6 Local Surface Geometry

3.6.1 Planarity: The planarity analysis for the back facade
reveals marked differences between the UAV- and TLS-derived
point clouds. As shown in Figure 7, the UAV dataset exhibits a
histogram skewed toward higher planarity values. It also has a
pronounced peak around 0.73 and an SD of 0.21, indicating that
most of its points lie on geometrically consistent flat surfaces.

Figure 8. Comparison of surface roughness for the back facade.
(Top-left: TLS roughness histogram. Top-right: UAV roughness
histogram. Bottom-left: TLS roughness point cloud. Bottom-
right: UAV roughness point cloud.)

In contrast, the UAV-derived roughness visualization (bottom-
right) exhibits a broader spatial distribution of green and yellow
hues, signifying higher roughness in certain regions. This
distribution is particularly noticeable in flat wall areas that ideally
should be smoother. The UAV histogram (top-right) appears
more sharply peaked near zero, yet this statistical concentration
hides the rougher appearance in the spatial data. This pattern
suggests that while most points have low roughness, the
photogrammetric model introduces noise artifacts more visibly
across otherwise flat areas. This discrepancy may be due to visual
limitations during image matching, particularly in low-texture Figure 7. Planarity comparison between TLS and UAV point
surfaces. Overall, TLS provides a more visually coherent and clouds for the back facade. (Top-left: TLS planarity histogram.
geometrically stable surface for the back facade. In contrast, the Top-right: UAV planarity histogram. Bottom-left: TLS point
UAV data, although adequate, shows increased susceptibility to cloud visualization with planarity scalar field. Bottom-right:
reconstruction noise in smooth, texture-poor surfaces. UAV point cloud visualization with planarity scalar field.)

3.6.3 Surface Variation: Surface variation is a measure ofThis result is visually affirmed by the dense red-to-yellow color
local geometric complexity and change in normal directiongradient in the scalar field map, representing high planarity
within a neighborhood, providing additional insight into theacross large contiguous regions. This result aligns with the
structural roughness of a point cloud surface. In Figure 9, the TLSUAV's aerial vantage, which facilitates clearer capture of
dataset (top-left and bottom-left) shows a narrower histogramuniform wall structures, especially on unobstructed surfaces like
distribution with a lower mean of 0.0121 and an SD of 0.0266.the back facade. In contrast, the TLS dataset yields a histogram
These values suggest that the TLS point cloud had relatively lesswith a near-normal distribution centered around a mean planarity

This contribution has been peer-reviewed. The double-blind peer-review was conducted on the basis of the full paper.
https://doi.org/10.5194/isprs-annals-X-5-W4-2025-143-2026 | © Author(s) 2026. CC BY 4.0 License. 148

<!-- p. 7 -->

ISPRS Annals of the Photogrammetry, Remote Sensing and Spatial Information Sciences, Volume X-5/W4-2025
Philippine Geomatics Symposium (PhilGEOS) 2025 "Enhancing Human Quality of Life through Geospatial Technologies",
24–25 November 2025, Quezon City, Philippines

surface variation, indicating more uniform and smoother surfaces while UAV photogrammetry enhances overall coverage and
on the back facade. This pattern is supported by the TLS point detail visibility, particularly for higher or occluded elements.
cloud visualization, where the dominant color is deep blue,
corresponding to very low surface variation values across most 4. Conclusions and Recommendations
of the wall area.
This study examined and compared the capabilities of TLS and
consumer UAV-based photogrammetry in capturing the
geometric features of a multi-facade building. Through a
combination of quantitative metrics such as RMSE, C2C
distance, surface area, density, planarity, roughness, and surface
variation, as well as qualitative visual inspections, we found that
both methods have distinct strengths and limitations. TLS
produced highly accurate and dense facade models with
consistent geometric surface quality, particularly in lower areas
close to the scanner. However, it suffered from occlusions,
especially in roof sections. Conversely, the UAV-derived point
cloud provided more complete coverage of rooftops and upper
walls due to its aerial vantage but exhibited increased surface
noise and incomplete ground-level detail. It also faced
reconstruction difficulties in areas with poor texture or limited
visibility.
Figure 9. Comparison of surface variation for the back facade.
(Top-left: TLS surface variation histogram. Top-right: UAV Despite these differences, the results highlight the potential
surface variation histogram. Bottom-left: TLS surface variation benefits of a hybrid or targeted approach depending on the
point cloud. Bottom-right: UAV surface variation point cloud.) specific application. For less detail-sensitive tasks such as solar
potential estimation, where capturing the roof structure and
In contrast, the UAV dataset (top-right and bottom-right) general building envelope is more critical than fine facade details
recorded a slightly higher mean of 0.0209 and an SD of 0.0305. and structure, the UAV-derived point cloud may already be
These values mean that there is greater variability in local surface sufficient (Han et al., 2020). On the other hand, TLS is more
orientations of the UAV dataset. While the difference in average appropriate for applications demanding high geometric accuracy
values may seem small, it is visually evident in the point cloud and precision, such as as-built documentation, structural
visualization, displaying more green tones interspersed with blue. deformation monitoring, or facade conservation, where fine
This result is especially true around window edges and other finer detail, surface smoothness, and accurate scale are essential
architectural features. Understandably, these regions are (Bouziani et al., 2021). Meanwhile, tasks that require both
typically more geometrically complex and more likely to exhibit complete coverage and accurate modeling—like heritage
higher variation in point orientation due to occlusion, digitization or energy modeling—may benefit most from a hybrid
reconstruction artifacts, or limitations in image overlap. method that combines TLS's ground-level precision with UAV's
Nonetheless, the UAV model still captured the overall facade aerial completeness (Le et al., 2022). Established workflows for
structure with sufficient geometric stability, although with integrating UAV and TLS datasets typically involve point cloud
slightly more noise and local irregularities than the TLS model. alignment through iterative closest point (ICP) registration,
followed by noise filtering, resolution harmonization (e.g., voxel
3.7 Qualitative Assessment downsampling), and merging within software platforms such as
CloudCompare. These methods leverage UAV’s aerial coverage
Visual inspection of the two models offers further qualitative and TLS’s detailed façade capture to produce complete, highinsights into their respective strengths and limitations. The TLS- accuracy building models. In all cases, aligning the data
derived point cloud, though uncolored, exhibits a notably cleaner collection strategy with the intended analytical goals ensures that
structure with well-preserved geometric details across the limitations in either method do not compromise the project
facades. Its strength lies in capturing large-scale architectural outcomes.
elements with minimal noise. The majority of the wall features
are also consistently represented. However, the model lacks roof To support more consistent and reproducible assessments in
geometry entirely, a direct consequence of occlusion from the future work, we recommend the use of standardized parameter
ground-based scan position. Smaller features, such as vents, are settings for surface geometry metrics, as variations in scale were
also difficult to distinguish. On the other hand, the UAV- shown to affect interpretability. If possible, automated feature
generated model benefits from photogrammetric colorization, extraction and measurement tools should also be incorporated to
which not only improves visual interpretability but also helps reduce potential human-induced errors. For both TLS and UAV
highlight minor surface details like small vents. However, it methods, strategic planning of scan positions or flight paths is
suffers from greater noise and evident data exclusions at the base essential to reduce occlusions and improve completeness. Future
of the building—areas where UAV flight paths did not studies should also test diverse building forms, materials, and
adequately capture low-angle views. Reconstruction accuracy settings to validate results across different urban environments.
also appears to be affected by surface reflectance and texture. In Ultimately, the selection of a scanning method should be guided
particular, white or smooth walls, especially on the building’s left by the specific spatial needs and resolution requirements of the
facade, exhibit patchy reconstruction. Nevertheless, unlike the project.
TLS model, the UAV point cloud successfully includes the full
rooftop structure, offering a more complete volumetric Acknowledgments
representation of the building. These complementary strengths
highlight how TLS excels in dense and accurate facade capture, This work is supported by the PHD Incentive Award (242413
PhDIA Y1), funded by the Office of the Vice Chancellor for

This contribution has been peer-reviewed. The double-blind peer-review was conducted on the basis of the full paper.
https://doi.org/10.5194/isprs-annals-X-5-W4-2025-143-2026 | © Author(s) 2026. CC BY 4.0 License. 149

<!-- p. 8 -->

ISPRS Annals of the Photogrammetry, Remote Sensing and Spatial Information Sciences, Volume X-5/W4-2025
Philippine Geomatics Symposium (PhilGEOS) 2025 "Enhancing Human Quality of Life through Geospatial Technologies",
24–25 November 2025, Quezon City, Philippines

Research and Development (OVCRD) of the University of the model. Journal of Mining and Earth Sciences.
Philippines Diliman. doi.org/10.46326/jmes.2022.63(4).03.

References Liu, J., Willkens, D., Lopez, C., Cortés-Meseguer, L., García-
Valldecabres, J., Escudero, P., & Alathamneh, S., 2023.
Bouziani, M., Chaaba, H., & Ettarid, M., 2021. Evaluation of 3D Comparative Analysis of Point Clouds Acquired from a TLS
Building Model Using Terrestrial Laser Scanning and Drone Survey and a 3D Virtual Tour for HBIM Development. Int. Arch.
Photogrammetry. Int. Arch. Photogramm. Remote Sens. Spatial Photogramm. Remote Sens. Spatial Inf. Sci.
Inf. Sci. doi.org/10.5194/isprs-archives-xlvi-4-w4-2021-39- doi.org/10.5194/isprs-archives-xlviii-m-2-2023-959-2023.
\2021.
Mirza, A., Zakiyon, A., Idris, A., Razali, M., Nasri, M., Ghani,
Dominici, D., Alicandro, M., & Massimi, V., 2017. UAV A., & Syafuan, W., 2023. Evaluating the Accuracy of UAV and
photogrammetry in the post-earthquake scenario: case studies in TLS for 3D Indoor Modelling in Large-Scale Building
L'Aquila. Geomatics, Natural Hazards and Risk, 8, 103 - 87. Environments. IOP Conference Series: Earth and Environmental
doi.org/10.1080/19475705.2016.1176605. Science, 1240. doi.org/10.1088/1755-1315/1240/1/012003.

Fan, C., Zhang, C., Yahja, A., & Mostafavi, A., 2021. Disaster Nex, F., Armenakis, C., Cramer, M., Cucci, D., Gerke, M.,
City Digital Twin: A vision for integrating artificial and human Honkavaara, E., Kukko, A., Persello, C., & Skaloud, J., 2022.
intelligence for disaster management. Int. J. Inf. Manag., 56, UAV in the advent of the twenties: Where we stand and what is
\102049. doi.org/10.1016/j.ijinfomgt.2019.102049. next. ISPRS Journal of Photogrammetry and Remote Sensing.
doi.org/10.1016/j.isprsjprs.2021.12.006.
Fernández-Hernández, J., González-Aguilera, D., RodríguezGonzálvez, P., & Mancera-Taboada, J., 2015. Image-Based Riaz, K., Mcafee, M., & Gharbia, S., 2023. Management of
Modelling from Unmanned Aerial Vehicle (UAV) Climate Resilience: Exploring the Potential of Digital Twin
Photogrammetry: An Effective, Low-Cost Tool for Technology, 3D City Modelling, and Early Warning Systems.
Archaeological Applications. Archaeometry, 57, 128-145. Sensors (Basel, Switzerland), 23. doi.org/10.3390/s23052659.
doi.org/10.1111/ARCM.12078.
Sani, N., Tahar, K., Maharjan, G., Matos, J., & Muhammad, M.,
Google Earth., 2025. [Satellite imagery of the Nat’l Inst. of 2022. 3D Reconstruction of Building Model Using UAV Point
Molecular Biology and Biotechnology, Univ. of the Philippines Clouds. Int. Arch. Photogramm. Remote Sens. Spatial Inf. Sci.
Diliman] [Online application]. Google. earth.google.com (14 doi.org/10.5194/isprs-archives-xliii-b2-2022-455-2022.
August 2025)
Santillan, J. R., Makinano-Santillan, M., Cutamora, L. C., &
Han, Y., Pan, Y., Zhao, T., and Sun, C., 2019. Evaluating Serviano, J. L., 2015. 3D building GIS database generation from
Buildings’ Solar Energy Potential Concerning Urban Context LiDAR data and free online web maps and its application for
Based on UAV Photogrammetry. Proc. Building Simulation flood hazard exposure assessment. In 36th Asian Conference on
2019: 16th Conference of IBPSA, Rome, Italy, 2–4 Sept. 2019, Remote Sensing (pp. 2037-2050).
Vol. 16, pp. 3610–3617. researchgate.net/publication/303486377_3D_Building_GIS_Dat
doi.org/10.26868/25222708.2019.210902. abase_Generation_From_LiDAR_Data_And_Free_Onlineweb_
Maps_And_Its_Application_For_Flood_Hazard_Exposure_Ass
Ingles, H. A., Legaspi, A. M. M., Sarmiento, C. J. S., and essment (22 October 2025)
Claridades, A. R. C., 2024. Accuracy Assessment of a SlamAcquired Point Cloud Data Using a Variety of Classification Stenz, U., Hartmann, J., Paffenholz, J., & Neumann, I., 2020.
Applications, Int. Arch. Photogramm. Remote Sens. Spatial Inf. High-Precision 3D Object Capturing with Static and Kinematic
Sci., XLVIII-4/W8-2023, 307–312, doi.org/10.5194/isprs- Terrestrial Laser Scanning in Industrial Applications -
archives-XLVIII-4-W8-2023-307-2024. Approaches of Quality Assessment. Remote. Sens., 12, 290.
doi.org/10.3390/rs12020290.
Kamnik, R., Perc, N., & Topolšek, D., 2019. Using the scanners
and drone for comparison of point cloud accuracy at traffic Sternberg, H., Jahn, I., & Kinzel, R., 2004. Terrestrial 3D Laser
accident analysis. Accident; analysis and prevention, 135, Scanning – Data Acquisition and Object Modelling for Industrial
\105391. doi.org/10.1016/j.aap.2019.105391. As-Built Documentation and Architectural Applications. In 20th
ISPRS Congress Technical Commission V (pp. 1012-1017).
Kersten, T. P., & Lindstaedt, M., 2012. Automatic 3D object isprs.org/proceedings/xxxv/congress/comm5/papers/183.pdf (22
reconstruction from multiple images for architectural, cultural October 2025)
heritage and archaeological applications using open-source
software and web services. Photogrammetrie-Fernerkundung- Villanueva, J., Ang, M., Inocencio, L., & Rejuso, M., 2015.
Geoinformation, 2012(6), 727-740. doi.org/10.1127/1432- Semi-Automated Building Footprint Extraction, Delineation and
8364/2012/0152 3D Visualisation of the University of the Philippines Main
Campus from LIDAR Data Using GIS-Based Open Source
Ketzler, B., Naserentin, V., Latino, F., Zangelidis, C., Thuvander, Software, Proc. FOSS4G Conference 2015, Seoul, South Korea,
L., & Logg, A., 2020. Digital Twins for Cities: A State of the Art 14-19 Sept. 2015, 15, 19. doi.org/10.7275/R5KD1W3F.
Review. Built Environment, 46, 547-573.
doi.org/10.2148/benv.46.4.547. Wu, B., Xie, L., Hu, H., Zhu, Q., & Yau, E., 2018. Integration of
aerial oblique imagery and terrestrial imagery for optimized 3D
Le, H., Van Nguyen, T., Pham, L., Tong, S., Nguyen, L., & Vo, modeling in urban areas. ISPRS Journal of Photogrammetry and
O., 2022. Combined use of Terrestrial Laser Scanning and UAV Remote Sensing, 139, 119-132.
Photogrammetry in producing the LoD3 of 3D high building doi.org/10.1016/J.ISPRSJPRS.2018.03.004.

This contribution has been peer-reviewed. The double-blind peer-review was conducted on the basis of the full paper.
https://doi.org/10.5194/isprs-annals-X-5-W4-2025-143-2026 | © Author(s) 2026. CC BY 4.0 License. 150
