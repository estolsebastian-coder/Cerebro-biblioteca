---
type: libro
title: "An Integrated HBIM Framework for the Sustainable Digital Documentation and Management of Nabataean Architectural Heritage"
author: "Yahya Alshawabkeh y Ahmad Baik"
categoria: "Tecnología láser, fotogrametría, otros"
paginas: 27
extraccion: "texto"
fuente: "local:E:/Biblioteca digital/Tecnología láser, fotogrametría, otros/An Integrated HBIM Framework for the Sustainable Digital Documentation and Management of Nabataean Architectural Heritage.pdf"
convertido: 2026-10-21
---

# An Integrated HBIM Framework for the Sustainable Digital Documentation and Management of Nabataean Architectural Heritage

> Texto extraído de `Tecnología láser, fotogrametría, otros\An Integrated HBIM Framework for the Sustainable Digital Documentation and Management of Nabataean Architectural Heritage.pdf` (27 páginas, texto). El PDF original está en el disco E: (Biblioteca digital); `<!-- p. N -->` marca el inicio de cada página.

> **Nota:** Sustainability 18 (2026): 10533 (MDPI, acceso abierto). DOI 10.3390/su182010533.

<!-- p. 1 -->

Article
An Integrated HBIM Framework for the Sustainable Digital
Documentation and Management of Nabataean
Architectural Heritage

Yahya Alshawabkeh 1 and Ahmad Baik 2,*

1 Department of Conservation Science, Queen Rania Faculty of Tourism and Heritage, The Hashemite
University, Zarqa 13133, Jordan; yahya.alshawabkeh@hu.edu.jo
2 Geomatics Department, Architecture and Planning Faculty, King Abdulaziz University,
Jeddah 21589, Saudi Arabia
\* Correspondence: abaik@kau.edu.sa; Tel.: +966‑505663599

Abstract

The Nabataean Kingdom, which flourished between the fourth century BCE and the sec‑
ond century CE, produced a remarkable architectural heritage across the arid landscapes
in northwestern Arabia and Jordan. Nabataean architectural heritage is characterized
by complex rock‑cut monuments, intricate decorative carvings, and ongoing deteriora‑
tion processes, creating significant challenges for accurate digital documentation, informa‑
tion management, and conservation. Despite the increasing scholarly attention devoted
to these sites, the available documentation and datasets remain fragmented across insti‑
tutions, disciplinary domains, and digital formats, limiting their accessibility and long‑
term management. While Historic Building Information Modeling (HBIM) has become
an effective system for modeling historic structures, existing approaches often emphasize
geometric reconstruction of monuments with limited integration of detailed decorative
elements and multidisciplinary heritage information. This study proposes a centralized
HBIM framework for the documentation and management of Nabataean architectural
heritage by integrating terrestrial laser scanning, close‑range photogrammetry, and para‑
metric HBIM. The proposed workflow combines accurate geometric acquisition with se‑
mantic information management within a unified workset‑based HBIM environment. A
major contribution of this research is the development of a dedicated digital library of
Nabataean decorative motifs, comprising high‑resolution textured mesh models that pre‑
serve the intricate geometry and visual characteristics of recurring sculptural elements.
These meshes are accurately scaled and georeferenced using laser scanning data and inte‑
grated into the HBIM environment to support systematic classification, reuse, and heritage
information management. Furthermore, a hybrid mesh–HBIM approach is introduced by
integrating realistic mesh models with the parametric HBIM representation of the monu‑
Academic Editors: Ana Tomé, ment, enabling detailed documentation and analysis of intricate carvings and deteriorated
Jesse Rafeiro and Miquel Reina Ortiz surfaces that cannot be adequately represented using conventional parametric modeling
Received: 9 September 2026 alone. Finally, architectural, historical, conservation, geological, and condition assessment
Revised: 6 October 2026 datasets are consolidated within a centralized HBIM platform organized through the pro‑
Accepted: 12 October 2026 posed workset structure to facilitate efficient data management, and interdisciplinary col‑
Published: 16 October 2026
laboration. The proposed framework advances current HBIM methodologies by integrat‑
Copyright: © 2026 by the authors.
ing realistic decorative asset libraries, hybrid mesh–parametric modeling, and centralized
Licensee MDPI, Basel, Switzerland.
This article is an open access article heritage information management, providing a transferable methodology for the digital
distributed under the terms and documentation and information management of Nabataean and other complex archaeo‑
conditions of the Creative Commons logical heritage sites. The framework establishes a structured basis for future applications

Attribution (CC BY) license.

Sustainability 2026, 18, 10533 https://doi.org/10.3390/su182010533

<!-- p. 2 -->

Sustainability 2026, 18, 10533 2 of 27

in condition monitoring, conservation planning, knowledge preservation, and sustainable
heritage management.

Keywords: Nabataean heritage; centralized HBIM; decorative motifs; mesh–HBIM inte‑
gration; laser scanner; photogrammetry; heritage conservation

\1. Introduction

The Nabataean civilization, known for its architectural ingenuity and cultural signifi‑
cance, left behind a remarkable legacy, as evidenced by the ancient cities of Hegra (Al‑Hijr)
in Saudi Arabia and Petra in Jordan [1,2]. These UNESCO World Heritage sites are not only
symbols of regional identity, but they also provide invaluable resources for studying an‑
cient Arab urbanism, engineering, and artistic expression [3–5]. Despite the considerable
historical and cultural significance of Nabataean architecture, it faces complex challenges
related to environmental degradation [6–8], increasing tourism pressures [9,10], and diffi‑
culties in heritage site management [11]. Additionally, the fragmentation of such heritage
data across institutions and countries impedes the pursuit of sustainable preservation and
effective documentation. Considering these challenges, the establishment of a comprehen‑
sive digital archive that consolidates digital survey results, historical documentation, and
conservation records into a single system is essential for ensuring accessibility and collab‑
oration among stakeholders [12,13].
Accordingly, the development of centralized Historic Building Information Model‑
ing (HBIM) for Nabataean architectural heritage provides a unified digital platform that
supports coordinated stakeholder collaboration while ensuring sustainable preservation
and management of heritage data [14,15]. HBIM integrates diverse datasets—including
historical documentation, geometric survey data, weathering analyses, and conservation
records—within a unified parametric digital environment [16–18]. HBIM may thus be uti‑
lized to link data and associate information to both the entire constructed building and
specific architectural features [19,20]. Organizing the central model into multiple thematic
worksets allows different specialists to work simultaneously on specific components while
maintaining data integrity and avoiding conflicts. However, the development of special‑
ized parametric objects capable of accurately representing the architectural geometry and
construction methodologies of historic buildings continues to present considerable chal‑
lenges. This difficulty stems from the inherent limitations of existing BIM‑based modeling
libraries, which are predominantly oriented toward contemporary architectural practices
and offer insufficient support for the complexities and uniqueness of historical structures.
As a result, the research field is increasingly focused on the creation of HBIM libraries
of specific architectural components [21,22], along with the advancement of open‑source
platforms to facilitate data sharing and collaboration [23,24].
Developing useful HBIM libraries for historical structures requires the collection of
highly detailed and accurate spatial and visual data [25]. This process begins with the
use of advanced data acquisition methods such as terrestrial laser scanning (TLS) and pho‑
togrammetry [26]. Terrestrial laser scanning (TLS) produces high‑density point clouds that
accurately capture the geometric characteristics of the architectural elements [27]. Despite
the potential of TLS, these systems are not capable of being exclusively employed for the
purpose of recording historical structures in a detailed and realistic manner [28,29]. The
majority of TLS devices have the ability to color their point clouds by acquiring digital im‑
ages through an attached built‑in camera. Nonetheless, the ideal camera placement may
not always align with the scanner’s location, resulting in color data that may lack the req‑

https://doi.org/10.3390/su182010533

<!-- p. 3 -->

Sustainability 2026, 18, 10533 3 of 27

uisite quality to effectively view surface characteristics and conditions [30]. Another issue
is the mixed‑pixel effect, which can occur when laser pulses interact with surface edges,
potentially affecting the accuracy of the coordinates of the collected points [31,32]. In such
cases, the laser beam may have difficulty accurately recording sharp edges, thin protru‑
sions, and abrupt surface transitions, which can result in erroneous point‑cloud measure‑
ments and localized data gaps [33]. Unfortunately, the impact of these inaccuracies cannot
be evaluated separately [34]. On the other hand, photogrammetry provides a valuable com‑
plementary approach for generating high‑resolution three‑dimensional models of fine dec‑
orative elements, where both geometric precision and realistic surface textures are essen‑
tial for detailed analysis and digital heritage documentation. The significant advantage of
photogrammetry lies in its flexibility during data acquisition. Images can be captured from
a wide range of positions and angles, enabling the documentation of complex geometries
and hard‑to‑reach areas that may be difficult to capture using terrestrial laser scanners [35].
The primary obstacles include limitations in image quality, camera networks surrounding
the surveyed item, shadows, and model scale, which may affect the final 3D point cloud of
the photogrammetric model [36,37]. Recent studies have confirmed the potential of com‑
bining multi‑source data to support the digitization of complex heritage structures [38,39].
Several hybrid approaches have recently been proposed to enhance input datasets for ac‑
curate HBIM object modeling [40–44]. Murphy et al. developed an HBIM approach based
on laser‑ and image‑based surveys and parametric libraries, enabling the creation of de‑
tailed models that represent information beyond the visible surface of historic structures,
including their construction methods and material composition.
On the one hand, the irregular and unique characteristics of historic buildings make
HBIM more challenging and complex than conventional BIM modeling. Currently, many
research groups are investigating methods to address the irregular geometries of his‑
toric structures within HBIM workflows. Murphy et al. [45] developed irregular HBIM
structures using Geometric Description Language (GDL). Barazzetti [46] employed non‑
uniform rational B‑splines (NURBS) curves to preserve the geometric details of com‑
plex structures during BIM‑based reconstruction from point clouds. Yang et al. [47]
proposed a mesh‑to‑HBIM workflow that transfers holistic surface meshes into semanti‑
cally enriched HBIM models while reducing the need for manual intervention during the
modeling process.
This study builds upon the authors’ previous research on the digital documentation
and HBIM of Nabataean architectural heritage [48,49]. While the earlier studies focused on
the documentation and modeling of individual monuments, the present work extends this
research by proposing centralized HBIM for comprehensive heritage information manage‑
ment and long‑term conservation. The new proposed framework integrates multi‑source
datasets, introduces a dedicated digital library of Nabataean decorative motifs, combines
high‑resolution mesh models with parametric HBIM representations, and organizes her‑
itage information within a workset‑based collaborative environment. Within this frame‑
work, shown in Figure 1, TLS data are employed to reconstruct the primary architectural
geometry as parametric HBIM elements, providing the structural backbone of the model,
while photogrammetry is used to capture complex and decorative elements, which are
subsequently processed into high‑resolution textured mesh models. These photogrammet‑
ric meshes are scaled and accurately oriented using the georeferenced TLS data, ensuring
both spatial consistency and geometric fidelity within the HBIM environment. The deco‑
rative meshes are incorporated into a dedicated HBIM family library, allowing standard‑
ized reuse across multiple monuments. The proposed central HBIM models are further
organized into thematic worksets, enabling multiple specialists to collaborate efficiently
on specific components while maintaining data integrity.

https://doi.org/10.3390/su182010533

<!-- p. 4 -->

Sustainability 2026, 18, 10533 4 of 27

Figure 1. Proposed methodological workflow for the development of a centralized HBIM framework
for Nabataean architecture.

Accordingly, this study addresses the following research questions: (1) How can TLS,
close‑range photogrammetry, and HBIM be integrated within a unified workflow for docu‑
menting complex Nabataean architectural heritage? (2) How can recurring irregular deco‑
rative elements be represented as reusable mesh‑based HBIM components while retaining
their geometric and visual characteristics? (3) How can heterogeneous geometric, histori‑
cal, conservation, geological, and condition‑related information be organized within a cen‑
tralized HBIM environment to support structured heritage information management?
Overall, the proposed framework advances current HBIM methodologies through the
following key contributions:

\1. A centralized HBIM framework is proposed integrating geometric, semantic, histori‑
cal, conservation, geological, and condition assessment data within a unified workset‑
based platform.
\2. A digital library of Nabataean decorative motifs is developed, comprising high‑
resolution textured mesh models for systematic documentation, classification, reuse,
and heritage information management.
\3. A hybrid mesh–HBIM integration approach is used that combines realistic pho‑
togrammetric meshes with parametric HBIM models, preserving both geometric fi‑
delity and semantic information for accurate representation and analysis of complex
and deteriorated architectural features that cannot be adequately represented using
conventional parametric modeling alone.

The article is organized as follows: Section 2 provides an overview of Nabataean
heritage sites, emphasizing their most significant monuments and architectural features.
Section 3 details the data acquisition and modeling of Nabataean monuments and tombs
using terrestrial laser scanning and photogrammetry. Section 4 discusses data fusion.
Section 5 presents the development of an HBIM family library for Nabataean decorative
elements, while Section 6 outlines the proposed central HBIM model and the collaborative
workflow. Section 7 discusses the results, and Section 8 concludes the paper.

https://doi.org/10.3390/su182010533

<!-- p. 5 -->

Sustainability 2026, 18, 10533 5 of 27

\2. Nabataean Heritage Sites

The Nabataeans were an Arab tribe that first appeared in the sixth century BC in
the desert east of Jordan after migrating from the southeastern Arabian Peninsula. The
Nabataean Kingdom controlled many of the trade routes of the region which formed the
main source of their wealth between the second century BCE and the end of the first cen‑
tury CE. Among the most important urban centers of the Nabataean Kingdom was Hegra
(also known as Madā’in Ṣāliḥ), located in AlUla in Saudi Arabia. Following Petra in im‑
portance, Hegra was the second major city of the Nabataean Kingdom and remains one of
the most significant archaeological landscapes that illustrate the development and achieve‑
ments of Nabataean civilization. The site extends across approximately 52 hectares and is
distinguished by its sandstone outcrops that host a remarkable concentration of rock‑cut
funerary monuments. Hegra is particularly renowned for its well‑preserved tomb façades,
shown in Figure 2, whose architectural complexity and decorative richness reflect the so‑
cial and economic status of the families or groups interred within them. In addition to
the monumental façades carved into isolated rock formations, simpler burial pits located
higher on the surrounding outcrops likely belonged to individuals of lower social stand‑
ing. The quantity, preservation, and diversity of decorated tombs at Hegra make the site
unique within the broader Nabataean cultural landscape [50].

Figure 2. Hegra Tombs, Jabal al‑Khuraymat necropolis.

Another remarkable example of rock‑cut architecture and urban planning, reflecting
the cultural, economic, and political significance of the Nabataeans in the region, is Petra,
the capital city of the Nabataean Kingdom. Petra was inscribed on the UNESCO World
Heritage List in 1985 and was later recognized in 2007 as one of the Seven New Won‑
ders of the World. The city flourished as a major urban and commercial hub along the
Nabataean trade network, and its archaeological landscape preserves a remarkable assem‑
blage of temples, tombs, colonnaded streets, water management systems, and ceremonial
spaces that collectively demonstrate the technological sophistication and artistic achieve‑
ments of Nabataean civilization. Among the most impressive monuments in Petra is Al‑

https://doi.org/10.3390/su182010533

<!-- p. 6 -->

Sustainability 2026, 18, 10533 6 of 27

Deir (The Monastery), Petra, one of the largest and most monumental rock‑cut façades at
the site, shown in Figure 3. The monument is accessed through an ascending pathway of
approximately 800 rock‑cut steps that lead to a remarkably well‑preserved façade measur‑
ing approximately 47 m in width and 48.3 m in height. Architecturally, the upper register
of the façade is composed of two half‑pediments flanking a central circular tholos crowned
by a conical roof and urn. The tholos is framed by columns with characteristic Nabataean
horned capitals, while the pediments are linked by a continuous frieze decorated with a
simplified motif of alternating triglyphs and discs. The façade is further articulated by
a monumental central doorway framed by pilasters, capitals, and additional decorative
architectural elements, emphasizing the monumentality and symbolic significance of the
structure. Despite its exceptional preservation and global significance, increasing concerns
have emerged in recent decades regarding the conservation of Petra’s monuments. Envi‑
ronmental monitoring studies conducted at the site have identified significant deteriora‑
tion and weathering affecting the interior chamber walls of several monuments. These
degradation processes have been attributed to multiple interacting factors, including fluc‑
tuations in internal relative humidity, salt crystallization, intensive visitor activity, and
limitations in conservation strategies and site management practices [7,8,51,52].

Figure 3. Al‑Deir monument in ancient Petra city.

The Tombs at Hegra Historical Site

Hegra is a collection of over 110 massive sandstone tombs carved directly into the
rocks protruding from the desert, demonstrating the ingenuity and creativity of ancient
Nabataean culture. The rock‑cut tombs of Hegra stand as remarkable testaments to the
Nabataean civilization, providing valuable insights into their social and cultural practices.
Many tombs bear inscriptions detailing the identities of their commissioners, the dates of
construction, and the craftsmen responsible for their creation. Numerous mythological
animals, vegetal motifs, and religious symbols are shown on both the interior and exterior
of the main Nabataean tombs, reflecting to a significant extent Nabataean funerary beliefs
and ritual practices. A wide variety of symbolic elements are carved on the tomb façades,
including grotesque masks, serpents, falcons, sphinxes, Medusa reliefs, rosettes, and solar
disks, which represent some of the most prominent motifs in Nabataean funerary architec‑
ture. The most prominent tomb is Liyhan Son of Koza’s 72‑foot‑tall sandstone monolith;
it is designated as IGN 110 and shown in Figure 4a. The enormous, stand‑alone rock,
although unfinished, is the unofficial image of Hegra. Another distinguished tomb desig‑

https://doi.org/10.3390/su182010533

<!-- p. 7 -->

Sustainability 2026, 18, 10533 7 of 27

nated as IGN 22, shown in Figure 4b, is regarded as one of the most elaborate and richly
decorated tombs within the Jabal al‑Khuraymat necropolis. Refs. [53,54] were the first
scholars to systematically map and catalogue the Nabataean monuments, during which
they also proposed the earliest typological classification of Nabataean tomb façades. Ac‑
cording to their classification, seven main tomb types were identified. The archaeological
site of Hegra preserves examples of five of these types, including Pylon Tombs, Step Tombs,
Proto‑Hegr Tombs, Hegr Tombs, and Arch Tombs.

Figure 4. (a) Tomb IGN 110 known as the tomb of Liyhan, son of Kuza; (b) Tomb IGN 22 in Jabal
al‑Khuraymat necropolis.

Pylon‑type tombs (Figure 5a,b) are characterized by façades ornamented with one
or two rows of stepped crowsteps, complemented by a half‑crowstep at each corner and
framed by relief moldings above and below. A horizontal groove positioned above the
entrance was likely intended to accommodate either the tomb owner’s inscription or an
ornamental stone molding. In contrast, step tombs (Figure 5c) feature façades composed
of two opposing stepped motifs situated above a cavetto (concave) cornice. The stepped
motif, which originated in the Assyrian–Achaemenid architectural tradition, was subse‑
quently adopted and reinterpreted by the Nabataeans, who modified it to create a distinc‑
tive decorative element for these tomb façades.

Figure 5. (a) Pylon tomb of one crowstep; (b) Pylon tomb with two crowstep; (c) Step tomb.

The Proto‑Hegr tomb façade (Figure 6) features two opposing sets of steps, comple‑
mented by a cavetto cornice and fascia, creating a distinctive architectural arrangement.
The architraves are supported by pilasters with Nabataean capitals. This type has steps,

https://doi.org/10.3390/su182010533

<!-- p. 8 -->

Sustainability 2026, 18, 10533 8 of 27

pilasters, but no attic. The Hegr tomb type on the other hand, shown in Figure 7a,b, is
characterized by a distinct architectural composition. Over a cavetto cornice, the tomb
façade has two sets of steps that face each other and fascia. The classical entablature is
supported by pilasters, with a non‑decorative attic above it. Finally, the arch‑type tomb
façade (Figure 7c) is characterized by a single or double arch supported by corner pilasters.
In some cases, the entrance doorway is additionally framed by pilasters crowned with cap‑
itals, which support a second arch that may feature a central decorative element.

Figure 6. Examples of Proto‑Hegr tombs.

Figure 7. (a,b) Examples of Hegr tombs; (c) The Arch tomb.

\3. Data Collection and Processing

The data were systematically collected from the archaeological site of Hegra and Pe‑
tra, employing advanced techniques such as laser scanning and photogrammetry. These
methodologies enabled the generation of highly accurate 3D models and high‑resolution
imagery as input for facilitating comprehensive documentation of the sites’ architectural
features. Laser scanning, with its precise measurement capabilities, and photogrammetry,
with its ability to capture intricate surface details and color, proved essential in preserving
and analyzing this historically significant architecture.

3.1. Laser Data

The Leica RTC360 scanner was employed to capture TLS data from the Hegra archae‑
ological site. This scanner is capable of acquiring up to two million colored points per

https://doi.org/10.3390/su182010533

<!-- p. 9 -->

Sustainability 2026, 18, 10533 9 of 27

second, with a measurement range extending from 0.5 to 130 m and a wide field of view of
360◦× 300◦. It is equipped with a calibrated spherical 36‑megapixel camera that captures
images within the same 360◦× 300◦field of view. The RGB values acquired are mapped
onto 3D coordinates to generate color representation of the scene. A key advantage of the
Leica RTC360 system is its automatic registration of the captured scans, enhancing field ef‑
ficiency during data acquisition. However, this process requires careful planning of scan
locations to ensure sufficient overlap between adjacent stations. For the tomb of Liyhan
IGN 110, a total of twenty‑nine scans were collected, four of which were taken from the
interior. The resulting model consists of over 403 million points, with an average ground
sampling distance (GSD) of 6 mm. In contrast, the scanning plan for Tomb IGN 22 in the Ja‑
bal al‑Khuraymat necropolis involved seven stations, three exterior and four interiors. The
merged point‑cloud model for this tomb contains over 77.1 million colored points, with an
average GSD of 8 mm for the exterior scans and 5 mm for the interior scans. Following the
acquisition of TLS data, a post‑processing phase was conducted to remove noise and un‑
wanted points. Subsequently, the interior and exterior scans were registered into a unified
coordinate system using Autodesk ReCap Pro 2026.1 software, producing the final point‑
cloud scene with integrated color information captured by the TLS camera. The scanning
workflow including the planning of scan positions, registration and merging of the individ‑
ual scans, and generation of the resulting registered point clouds is shown in Figure 8. The
interior scans of Hegra Tomb IGN 22. which further reveal the spatial arrangement of the
burial graves within the tomb chamber, providing detailed geometric documentation of
the internal architectural configuration, are shown in Figure 9. The data from Petra on the
other hand was acquired using the Mensi GS100 laser scanner, which offers a panoramic
field of view of 360◦horizontally and 60◦vertically. The instrument is capable of recording
up to 5000 points per second, with a measurement accuracy of approximately 6 mm at a
maximum scanning range of 100 m. During data acquisition, an integrated calibrated cam‑
era captures video snapshots at a resolution of 768 × 576 pixels, which are automatically
registered and mapped onto the corresponding laser point measurements. To mitigate oc‑
clusions, five scans were conducted from different viewpoints at the Al‑Deir monument,
resulting in a dataset comprising nearly six million points, shown in Figure 10, with an
average ground sampling distance (GSD) of approximately 3 cm.

Figure 8. Laser scanning data for Tomb IGN 110 and IGN 22. (a) Scanning work plan. (b) Merging
the scans. (c) Top view.

https://doi.org/10.3390/su182010533

<!-- p. 10 -->

Sustainability 2026, 18, 10533 10 of 27

Figure 9. Interior scans of Hegra Tomb IGN 22 reveal the spatial arrangement of the burial graves
within the tomb chamber.

Figure 10. Laser scanning data for Petra Monastery: (a) 3d point cloud. (b) Meshed model.

3.2. Photogrammetric Data

Laser scanning techniques, while highly effective for capturing large‑scale architec‑
tural geometry, may present certain limitations when documenting fine reliefs and dis‑
continuous edges. In such cases, the laser beam may have difficulty accurately recording
sharp edges, thin protrusions, and abrupt surface transitions, which can result in erroneous
point‑cloud measurements and localized data gaps, as shown in Figure 11. As a result, pho‑
togrammetry provides a valuable complementary approach for generating high‑resolution
three‑dimensional models of fine decorative elements, where both geometric precision and
realistic surface textures are essential for detailed analysis and digital heritage documen‑
tation. The significant advantage of photogrammetry lies in its flexibility during data ac‑
quisition. Images can be captured from a wide range of positions and angles, enabling
documentation of complex geometries and hard‑to‑reach areas that may be difficult to
capture using terrestrial laser scanners. Consequently, digital images were acquired for
photogrammetric processing using a Canon EOS 5D Mark IV camera, with a resolution of
6720 × 4480 pixels at Hegra, and a Nikon D2X camera, with a resolution of 4288 × 2848 pix‑
els at Petra. The digital images of the monument were acquired in near‑simultaneous inter‑
vals to ensure consistent lighting conditions and uniform radiometric properties, thereby
enhancing the visual quality and interpretability of surface features and tomb inscriptions.
Image acquisition was performed using a 35 mm fixed focal length lens to ensure consistent
camera geometry throughout the photogrammetric survey. Agisoft Metashape was used
to process the captured images and generate three‑dimensional models within an arbitrary
coordinate system; selected results are illustrated in Figures 12 and 13. The next section
will demonstrate how terrestrial laser scanning (TLS) was employed to establish ground
control points (GCPs) for the orientation and scaling of the photogrammetric datasets.

https://doi.org/10.3390/su182010533

<!-- p. 11 -->

Sustainability 2026, 18, 10533 11 of 27

Figure 11. Examples of limitations in terrestrial laser scanning when capturing fine reliefs and sharp
edges, resulting in localized gaps and inaccuracies in the point cloud.

Figure 12. Examples of camera positions for photogrammetric data acquisition.

Figure 13. Final 3D textured models of Hegra Tombs, Jabal al‑Khuraymat necropolis.

The datasets integrated in this study originate from documentation campaigns con‑
ducted at different sites and periods. Consequently, a fully harmonized archival record of

https://doi.org/10.3390/su182010533

<!-- p. 12 -->

Sustainability 2026, 18, 10533 12 of 27

all photogrammetric processing parameters, such as exact Agisoft processing‑quality set‑
tings, mesh face counts, texture resolution, final model file sizes, and equivalent LOD de‑
scriptors, was not consistently available for all datasets at the time of the present compara‑
tive integration study. To avoid retrospectively reconstructing or inferring undocumented
values, the manuscript reports only acquisition and processing parameters that could be
verified from the available project records. This limitation does not affect the demonstrated
integration workflow but restricts direct benchmarking of processing performance across
all case‑study datasets.

\4. Data Integration and Registration Assessment of Laser Scanning
and Photogrammetry

The registration assessment presented in this section is intended to evaluate the inter‑
nal consistency of the TLS–photogrammetry alignment for the demonstrated case rather
than to provide independent end‑to‑end validation of the complete HBIM workflow.
The integration of terrestrial laser scanning (TLS) and photogrammetry represents a
fundamental step in the development of an accurate and scalable HBIM framework for
Nabataean heritage. This integration enables the production of metrically accurate and
scale‑consistent photogrammetric outputs. These outputs are subsequently utilized to
generate HBIM families representing fine architectural details, preserving both geometric
precision and morphological richness. To integrate models derived from heterogeneous
sensor datasets, accurate registration is essential. The spatial alignment of the photogram‑
metric model with respect to the three‑dimensional laser scanning model was achieved
through pose estimation, which determines both position and orientation, as illustrated
in Figure 14. This process relied on a set of clearly identifiable corresponding points that
could be reliably recognized in both datasets. At least three corresponding points were
selected from clearly identifiable and geometrically distinctive features within the over‑
lapping areas of the two datasets and spatially distributed across the model to ensure a
stable initial alignment. A preliminary alignment was first established using CloudCom‑
pare v2.14.beta software, followed by fine registration using the Iterative Closest Point
(ICP) algorithm implemented in CloudCompare [55]. The results of the combined pose
and scale registration of the image‑based point cloud withw the laser‑scanning point cloud
are presented in Figure 14. For the Tomb of IGN 110, presented in Figure 15, the alignment
of the photogrammetric and TLS datasets was refined using the ICP algorithm in Cloud‑
Compare. As reported in the ICP registration results shown in Figure 16, the alignment
achieved a root mean square (RMS) residual of 0.18 mm, calculated by CloudCompare
using 50,000 points selected by the software.

Figure 14. Pose estimation and scaling process of the photogrammetric point cloud aligned with the
laser scanning reference.

https://doi.org/10.3390/su182010533

<!-- p. 13 -->

Sustainability 2026, 18, 10533 13 of 27

Figure 15. (a) Photogrammetric dataset in an arbitrary (scale‑less) coordinate system; (b) terrestrial
laser scanning (TLS) data utilized as a reference framework for scaling and accurate registration.

Figure 16. Final registration results of the photogrammetric and TLS datasets, including the aligned
point clouds and associated registration parameters.

The reported 0.18 mm RMS value refers specifically to the ICP fine‑registration test
conducted for Tomb IGN 110 and was not used as a common accuracy metric for all monu‑
ments or datasets examined in this study. The remaining datasets were processed accord‑
ing to their respective acquisition and modeling requirements, and no claim is made that
the same numerical registration accuracy was achieved across all cases.
The photogrammetric point cloud is shown in red, while the laser‑scanner (TLS) point
cloud is shown in yellow. This value represents the internal residual of the ICP registra‑
tion between the photogrammetric and TLS point clouds and should not be interpreted
as the absolute accuracy or overall uncertainty of the complete survey, registration, or
HBIM workflow.
No dedicated sensitivity analysis was conducted to quantify the robustness of ICP un‑
der systematically varied point‑cloud density or noise conditions. The ICP result should
therefore be interpreted as a dataset‑specific fine‑registration outcome rather than as ev‑
idence of algorithmic robustness across heterogeneous acquisition conditions. The influ‑
ence of point density, noise level, overlap, and initial alignment quality on registration
performance represents an important topic for future comparative assessment.

\5. HBIM Families’ Library of the Nabataean Decorative Elements

The development of an HBIM families’ library for Nabataean decorative elements is
essential due to the wide variety and symbolic significance of motifs carved on Nabataean
tomb façades. These façades feature numerous symbolic elements, including grotesque

https://doi.org/10.3390/su182010533

<!-- p. 14 -->

Sustainability 2026, 18, 10533 14 of 27

masks, serpents, falcons, sphinxes, Medusa reliefs, rosettes, and solar disks, which repre‑
sent some of the most prominent motifs in Nabataean funerary architecture. Such elements
are repeatedly used across many tombs and monumental façades, often with similar ge‑
ometric configurations and stylistic characteristics as shown in Figure 17. This repetition
highlights the importance of creating a structured digital library of HBIM families that can
be reused directly within BIM models.

Figure 17. Examples of recurring Nabataean decorative elements carved on various tomb façades,
documented and reconstructed using 3D photogrammetric modeling.

Reuse within the HBIM environment follows a component‑based principle: a dec‑
orative family may be reused when the motif type and morphological characteristics
are sufficiently comparable, while project‑specific scale, provenance, condition, and doc‑
umentation attributes are retained or updated for the receiving monument rather than
copied indiscriminately.
For the purposes of this study, the decorative‑element library is organized as a struc‑
tured, heritage‑specific collection rather than as a fully standardized external repository.
The primary classification level is based on motif type (e.g., eagle, sphinx, serpent, rosette,
Medusa, and related recurring elements), while provenance information records the mon‑
ument and site from which each component was documented. Each HBIM component
is associated with a unique identifier and a set of descriptive metadata fields, including
motif type, material, source monument, documentation method, condition information,
and external documentation references. The present implementation focuses on classifi‑
cation, reuse, and information association within the HBIM environment. Formal cross‑
platform version management, standardized naming conventions across institutions, and
public open‑access repository mechanisms were not implemented and are therefore iden‑
tified as future development requirements rather than demonstrated outcomes of the
present study.
Due to the highly intricate geometry and irregular relief of Nabataean decorative carv‑
ings, parametric modeling approaches are often insufficient to accurately represent their
complex morphological details. Therefore, mesh‑based modeling is adopted as a more
suitable method for preserving the authenticity and geometric complexity of these carv‑
ings. To accurately document these decorative components, photogrammetry techniques
are employed to capture both their detailed geometry and surface color information. The
resulting high‑resolution models are processed into mesh geometries and subsequently in‑
tegrated into the HBIM environment as reusable components. Figures 18 and 19 illustrate
examples of photogrammetry‑derived mesh models of Nabataean decorative elements,
while Figure 20 presents an example of the HBIM family generated in Autodesk Revit for
the eagle motif.

https://doi.org/10.3390/su182010533

<!-- p. 15 -->

Sustainability 2026, 18, 10533 15 of 27

Figure 18. Photogrammetric reconstruction process of Nabataean decorative motifs showing the
modeling stages: (a) point cloud generation; (b) triangulated mesh formation; (c) solid model deriva‑
tion; (d) textured mesh model.

Figure 19. Examples of photogrammetry‑derived mesh models of Nabataean decorative elements.

Figure 20. An example of the HBIM family generated in Autodesk Revit for the eagle motif.

https://doi.org/10.3390/su182010533

<!-- p. 16 -->

Sustainability 2026, 18, 10533 16 of 27

\6. Proposed HBIM Central Model

The significance of BIM resides in its capacity to transform static documentation into
an intelligent, dynamic archive that facilitates multidisciplinary collaboration. At the core
of this approach is the central HBIM model, which functions as a consolidated digital repos‑
itory, integrating heterogeneous datasets into a single coordinated environment. By cen‑
tralizing these diverse data sources, the central model ensures data consistency, enables
iterative updates, and preserves legacy material in a manner that is accessible, reusable,
and scalable for future research, conservation planning, and educational initiatives. The
proposed HBIM workflow adopted for the documentation of Nabataean monuments is
based on the integration of survey data, parametric modeling, and collaborative infor‑
mation management within a unified central BIM model. The geometric data acquired
through terrestrial laser scanning and close‑range photogrammetry provide the primary
source for accurate three‑dimensional representation. The BIM model is developed in Au‑
todesk Revit using a central model‑based work‑sharing approach, where the central model
functions as a shared digital archive, as shown in Figure 21. Within this collaborative en‑
vironment, Revit worksets are employed as a core work‑sharing mechanism to subdivide
the BIM model into editable subsets, enabling simultaneous multi‑user collaboration. Each
element is assigned to a specific workset, allowing controlled access, ownership manage‑
ment, and coordinated synchronization of changes.

Figure 21. HBIM work‑sharing using the Revit central HBIM model that allows multiple team mem‑
bers to work on the same project model at the same time.

For the HBIM documentation of Nabataean monuments, the proposed workset struc‑
ture organizes the central HBIM model into thematic worksets, as illustrated in Figure 22.
The worksets provide a structured environment for integrating and managing heteroge‑
neous heritage information within a single centralized HBIM platform. All spatial datasets
used within each case study were aligned within a common project coordinate framework
derived from the available survey control. Because the investigated datasets originate from
different documentation campaigns and sites, a single common EPSG code is not asserted
for all datasets in this study.
The processed point clouds and photogrammetric outputs constitute the primary ge‑
ometric reference for the modeling process. Architectural elements, including rock‑cut
walls, façades, chambers, columns, architectural features, and decorative elements, are
modeled as HBIM objects and positioned according to the surveyed geometry. Each mod‑

https://doi.org/10.3390/su182010533

<!-- p. 17 -->

Sustainability 2026, 18, 10533 17 of 27

eled element is assigned a unique identifier and a set of customized HBIM parameters.
These parameters provide the link between the geometric objects and their associated his‑
torical, material, conservation, and condition‑assessment information.

Figure 22. Proposed HBIM workset structure for the collaborative documentation of Nabataean mon‑
uments using the central HBIM model.

The historical‑phase workset associates architectural elements with their correspond‑
ing construction or modification phases, while the conservation and condition‑assessment
workset records information such as material type, deterioration category, damage loca‑
tion, severity, and conservation status. Photographs, orthophotos, inspection records, and
other documentation can be associated with the relevant HBIM elements through their
unique IDs and corresponding parameters or external file references. In this way, the cen‑
tral HBIM model functions not only as a three‑dimensional representation of the monu‑
ment but also as an information hub in which geometric, historical, architectural, and con‑
servation datasets are spatially and semantically linked to individual heritage elements.
To demonstrate the implementation of this workflow, two representative case stud‑
ies are examined: Al‑Farid monument in Hegra and Al‑Deir monument in Petra. The
first phase focuses on the precise production of HBIM models representing the architec‑
tural and decorative components of Nabataean monuments. The second phase involves
the establishment of a central HBIM model organized through multiple worksets, which
function as thematic layers for the management and enrichment of heritage information.
The BIM process was carried out in two stages. In the first stage the geometric re‑
construction of architectural elements—such as walls, columns, façades, and structural
features—is carried out based on point‑cloud data derived from laser scanning, whereas
the second stage involved the incorporation of previously developed mesh‑based families
representing complex decorative motifs derived from photogrammetric models. Standard
BIM workflows typically rely on predefined two‑ and three‑dimensional object families
that facilitate efficient and rapid model generation. However, Nabataean monuments in‑
corporate distinctive architectural and structural features that are not represented within
conventional BIM libraries. Consequently, the modeling process required the creation of
customized components within the BIM environment. The HBIM models were therefore
developed in Autodesk Revit using a combination of system families and in‑place families
in order to accurately represent the architectural characteristics of the monuments. Sys‑
tem families were primarily employed to model standard architectural components such
as walls and roofs. These families rely on defined dimensional parameters—including
wall and roof thicknesses, as well as door width, height, and depth—to generate accurate
geometric profiles while maintaining the parametric behavior of the modeled elements.
In contrast, in‑place families proved more suitable for representing unique, highly com‑
plex, and free‑form architectural elements that are specific to the Nabataean monuments.

https://doi.org/10.3390/su182010533

<!-- p. 18 -->

Sustainability 2026, 18, 10533 18 of 27

Accordingly, new in‑place families were created and implemented within the BIM envi‑
ronment, with their geometric profiles directly derived from point‑cloud data. For each
component, a set of family parameters was defined, including dimensional attributes, ma‑
terial properties, and descriptive information related to condition assessment.
For example, an in‑place façade component was assigned dimensional parameters de‑
scribing its width, height, and depth, together with material‑related attributes and descrip‑
tive fields including Element_ID, Material_Type, Condition_Status, Deterioration_Type,
Damage_Severity, Conservation_Status, and Documentation_Reference. These parame‑
ters enable each modeled component to function not only as a geometric object but also
as an information‑bearing heritage entity that can be linked to photographs, orthophotos,
condition records, and external documentation.
To accurately identify and delineate these architectural elements, the point‑cloud data
were segmented into sectional views and elevations, which served as the primary refer‑
ence for tracing and reconstructing the components within the HBIM model as shown in
Figure 23. In the second stage of the HBIM process, the previously developed mesh‑based
families representing complex decorative motifs derived from photogrammetric models
were directly integrated into the produced HBIM model, as illustrated in Figure 24.

Figure 23. Tracing and modeling architectural elements in the HBIM reconstruction workflow.

Figure 24. Mesh‑based families of Nabataean decorative motifs incorporated into the HBIM model.

In the second phase, the central HBIM models of Al‑Farid Tomb in Hegra and Al‑
Deir Monument in Petra were developed in Autodesk Revit using a centralized modeling
workflow. The process began with the creation of a single central HBIM project file that
serves as the primary repository for all modeling and documentation activities as shown in
Figure 25a. To facilitate efficient collaboration and structured data management, the cen‑
tral model was organized using a set of HBIM‑oriented worksets shown in Figures 25b–27.

https://doi.org/10.3390/su182010533

<!-- p. 19 -->

Sustainability 2026, 18, 10533 19 of 27

This hierarchical organization allows multiple researchers to work simultaneously on dif‑
ferent components of the model while maintaining data consistency and semantic clarity
within the shared HBIM environment. For individual modeling tasks, team members gen‑
erated local copies of the central model within Revit. These local models enable researchers
to work independently on specific elements of the monuments, including tomb façades,
parametric architectural components, and decorative or epigraphic features. During the
modeling process, users periodically synchronized their work with the central model us‑
ing the Synchronize with central function. This process uploads individual modifications,
incorporates updates made by other collaborators, and automatically manages element
ownership. Through this workflow, the HBIM models of Al‑Farid and Al‑Deir were pro‑
gressively enriched, ensuring version consistency and supporting collaborative develop‑
ment of a comprehensive digital archive of Nabataean monuments.

Figure 25. (a) Producing central HBIM models; (b) the proposed worksets.

Figure 26. Central HBIM model of the Tomb of Liyhan, Son of Kuza, showing the integration and
linkage of heritage information from different thematic worksets.

https://doi.org/10.3390/su182010533

<!-- p. 20 -->

Sustainability 2026, 18, 10533 20 of 27

Figure 27. Central HBIM model of the Tomb of Al‑Deir in Petra, showing the integration and linkage
of heritage information from different thematic worksets.

\7. Results and Discussion

The implemented workflow produced three principal outcomes. First, multi‑source
TLS and photogrammetric datasets were integrated into common monument‑scale HBIM
environments. For Tomb IGN 110, the ICP fine‑registration procedure in CloudCompare
produced an internal RMS residual of 0.18 mm over 50,000 points; this value represents
registration residual rather than absolute model accuracy. Second, recurring Nabataean
decorative motifs were reconstructed as reusable high‑resolution mesh‑based HBIM com‑
ponents. Third, central HBIM models were organized through thematic worksets and
customized parameters linking geometric elements with historical, material, condition,
conservation, and contextual information. These results demonstrate the technical imple‑
mentation of the proposed workflow; however, collaboration efficiency, user performance,
long‑term monitoring effectiveness, and conservation‑decision outcomes were not quanti‑
tatively evaluated in the present study.
The management of Nabataean heritage data has long been challenged by fragmenta‑
tion, as datasets are typically dispersed across multiple institutions, disciplinary domains,
and heterogeneous digital formats. This dispersion limits not only data accessibility but
also its long‑term usability, ultimately constraining effective conservation, monitoring, and
research continuity. The absence of a shared and centralized platform results in dupli‑
cated efforts, inconsistent documentation standards, and difficulties in integrating new
data with existing records. Therefore, this paper proposes an HBIM framework tailored
for Nabataean heritage. Unlike previous HBIM studies that mainly focused on the digital
documentation of individual heritage buildings or the geometric reconstruction of archi‑
tectural elements [21,25,44,45,52], the proposed framework introduces a more comprehen‑
sive and integrated approach for managing Nabataean architectural heritage. The main
contribution lies in the development of a centralized HBIM environment that combines
multi‑source datasets, including high‑resolution photogrammetric models, laser scanning

https://doi.org/10.3390/su182010533

<!-- p. 21 -->

Sustainability 2026, 18, 10533 21 of 27

data, historical documentation, condition assessments, and conservation information. An‑
other key advancement is the integration of a structured workset‑based organization strat‑
egy, which provides a structured mechanism for data organization, collaborative model
development, and future updating of the HBIM model. This approach is intended to fa‑
cilitate interdisciplinary workflows among archaeologists, conservators, architects, and re‑
searchers, providing a sustainable digital framework for the documentation, analysis, and
preservation of Nabataean heritage.
Furthermore, the proposed framework introduces a novel HBIM‑based library of
Nabataean decorative motifs, representing recurring sculptural elements such as mytho‑
logical faces, eagles, snakes, sphinxes, and griffins. This library represents a dedicated
reusable collection of Nabataean decorative components developed within the scope of the
present study. Rather than claiming a universally first‑of‑its‑kind library, its contribution
lies in structuring recurring Nabataean decorative motifs as reusable high‑resolution mesh‑
based HBIM components within a centralized heritage‑information environment. The in‑
tegration of these detailed mesh‑based assets within a centralized HBIM environment pro‑
vides a reusable digital resource for heritage documentation, comparative analysis, and
conservation applications. The proposed framework therefore extends the role of HBIM
from building‑level information management toward the preservation and management
of detailed architectural heritage components as shown in Figures 26 and 27.
Another significant contribution of the proposed framework is the integration of high‑
resolution photogrammetric mesh models with the parametric HBIM representation of the
monument. The mesh models are accurately registered to the parametric model using geo‑
referenced laser scanning data, ensuring consistent scale, spatial alignment, and seamless
data integration within the centralized HBIM environment. This hybrid representation
combines the advantages of both approaches: the parametric model provides efficient in‑
formation management and semantic organization, while the mesh model preserves the
fine geometric and textural details that cannot be adequately represented by parametric
objects alone. The integration is particularly valuable for architectural components exhibit‑
ing surface deterioration, weathering, or complex sculptural features, where realistic mesh
data enable detailed condition assessment and support further multidisciplinary investi‑
gations as shown in Figure 28.
In addition to the architectural and archaeological components, the framework incor‑
porates topographic information describing the natural setting, rock formations, terrain
characteristics, and spatial relationship between the monuments and their surrounding
landscape, as shown in Figure 29. These datasets are georeferenced and integrated within
a common spatial reference framework, ensuring consistent spatial positioning across the
HBIM environment. All spatial datasets are referenced to a common coordinate system,
allowing geometric information derived from terrestrial laser scanning (TLS), photogram‑
metry, topographic surveys, and survey control points to be accurately aligned with the
HBIM model. This georeferenced integration establishes a spatial link between the mon‑
ument, its geological context, and the surrounding topography, thereby supporting com‑
prehensive documentation, spatial analysis, conservation assessment, and future manage‑
ment of Nabataean heritage sites. Contextual information, orthophoto, along with other
derived data, were also integrated into the Historic Building Information Model (HBIM), as
illustrated in Figure 30. This integration provides a unified environment for stakeholders
involved in the conservation process.

https://doi.org/10.3390/su182010533

<!-- p. 22 -->

Sustainability 2026, 18, 10533 22 of 27

Figure 28. Integration of high‑resolution photogrammetric mesh models with the centralized para‑
metric HBIM model, where realistic mesh data enable detailed surface deterioration.

Figure 29. Integration of topographic information with the HBIM model through georeferenced sur‑
vey points, establishing a spatial link between the monument and its surrounding terrain.

https://doi.org/10.3390/su182010533

<!-- p. 23 -->

Sustainability 2026, 18, 10533 23 of 27

Figure 30. Examples of associating orthophotos, and inspection/condition records with correspond‑
ing HBIM elements.

The proposed workflow can be compared with previous approaches developed by
Yang et al. and Barazzetti et al. to address the geometric complexity of historic structures.
Yang et al. [47] proposed a mesh‑to‑HBIM workflow in which the surface mesh is first seg‑
mented in the Rhino 3D environment and subsequently transformed into solid geometry
and semantic HBIM elements. This approach provides a systematic pathway for convert‑
ing detailed surface meshes into semantically structured BIM components. However, the
workflow remains largely building‑specific, as the surface mesh of each building must be
segmented and interpreted to generate the corresponding HBIM elements. In contrast,
the present workflow focuses on documenting recurring decorative motifs and irregular
architectural elements using photogrammetry and converting them into reusable HBIM
families. Once developed, these families can be incorporated into other HBIM projects con‑
taining similar architectural features, thereby reducing the need to repeatedly reconstruct
and segment recurring components for each building. The proposed approach therefore
shifts the emphasis from building‑specific mesh segmentation toward the development of
a reusable library of heritage‑specific HBIM components. Similarly, Barazzetti [46] pro‑
posed a multi‑step, manual or semi‑automated workflow based on NURBS curves and
surfaces for reconstructing complex and irregular architectural elements. Their approach
involves the extraction of discontinuity lines corresponding to the boundaries of construc‑
tive elements, followed by the generation and parametrization of NURBS surfaces. While
this method can effectively preserve the geometric characteristics of complex structures,
the reconstruction of highly fragmented or heavily ornamented elements remains challeng‑
ing. The parametrization of complex geometries may introduce local geometric problems,
such as surface intersections resulting from the offsetting of objects composed of multiple
surfaces. In comparison, the present workflow addresses recurring decorative elements,
enabling the representation of fine‑grained irregular geometric details and morphological
variations characteristic of Nabataean decorative motifs.
Beyond digital documentation and information management, geometrically reliable
HBIM models may also provide a structured basis for future quantitative structural and
conservation analyses. Previous studies have demonstrated that geometric irregularities
derived from surveying and modeling can influence the predicted structural response of
historic masonry, while integrated experimental and numerical approaches can support
the evaluation of conservation‑compatible interventions. Although no structural or nu‑
merical simulation was conducted in the present study, the centralized HBIM environ‑
ment may provide a future interface through which geometric, material, condition, and
structural‑analysis information can be linked to specific heritage components. Accord‑
ingly, numerical modeling is considered a prospective extension of the framework rather
than a capability validated in the present study.

https://doi.org/10.3390/su182010533

<!-- p. 24 -->

Sustainability 2026, 18, 10533 24 of 27

The proposed workflow combines parametric modeling of the main building compo‑
nents with mesh‑based BIM of irregular and fine architectural details; this hybrid strat‑
egy helps reduce the size and computational complexity of the final BIM model while
preserving the geometric characteristics of complex elements. However, the accuracy
and efficiency of the registration process may be influenced by computational perfor‑
mance, particularly when handling large‑scale buildings and high‑density laser‑scanning
and photogrammetric datasets. The substantial size of point clouds and meshes may ex‑
ceed the processing capabilities of available hardware, potentially affecting the efficiency
and stability of the registration workflow. In addition, the level of detail captured in dec‑
orative motifs depends largely on the number and quality of the acquired images and
the subsequent mesh‑generation process. Insufficient image coverage or image quality
may therefore result in incomplete or less detailed geometric representations of intricate
decorative elements.

Limitations and Transferability

The proposed workflow also presents several practical limitations. Its implementa‑
tion currently depends substantially on proprietary software, particularly Autodesk Revit,
which may limit reproducibility across alternative HBIM environments. The exchange of
complex textured meshes together with associated semantic information through IFC or
other openBIM workflows was not systematically evaluated in this study and requires fur‑
ther investigation.
Similarly, formal compliance with broader information‑management and semantic‑
interoperability standards, including Industry Foundation Classes (IFC), and CIDOC
CRM, was not evaluated in the present implementation. These standards provide impor‑
tant reference frameworks for future development of cross‑platform information exchange,
lifecycle information management, and semantic interoperability beyond the current Revit‑
based environment.
The creation of customized in‑place families and the organization of heritage‑specific
semantic information also involve significant manual interpretation and modeling effort.
In addition, scalability may become challenging when the framework is applied to sub‑
stantially larger archaeological complexes or very high‑density datasets. While TLS–
photogrammetry integration, hybrid mesh–HBIM representation, semantic association,
and thematic worksets are conceptually transferable to other heritage contexts, the pro‑
posed decorative‑motif library is inherently site‑ and typology‑specific and would require
adaptation for other architectural traditions.

\8. Conclusions

This study presented a comprehensive HBIM framework for the digital documenta‑
tion and management of Nabataean architectural heritage through the integration of ter‑
restrial laser scanning, close‑range photogrammetry, and Historic Building Information
Modeling. The proposed workflow combines accurate geometric acquisition with seman‑
tic information to establish a centralized digital heritage platform. A major contribution
of this research is the development of a dedicated digital library of Nabataean decorative
motifs, captured as high‑resolution textured mesh models that preserve the intricate ge‑
ometry and visual characteristics of recurring architectural elements. These models are
accurately georeferenced using laser scanning data and converted into BIM families to
support classification, reuse, and information management. The proposed workset‑based
organization will further improve data management and interdisciplinary collaboration
by integrating architectural models, photogrammetric meshes, historical documentation,
condition assessments, and geological information within a unified HBIM environment.

https://doi.org/10.3390/su182010533

<!-- p. 25 -->

Sustainability 2026, 18, 10533 25 of 27

Despite these contributions, several limitations remain. The decorative motifs are cur‑
rently represented as non‑editable mesh geometry and therefore lack fully modifiable ge‑
ometric parameters. In addition, the registration and modeling workflow may become
computationally demanding when processing large‑scale monuments and high‑density
laser‑scanning and photogrammetric datasets. Future work will therefore focus on devel‑
oping more flexible and parametric representations of decorative motifs, while retaining
the fine geometric characteristics captured through photogrammetry. The computational
performance of the workflow will also be optimized through improved data processing
and mesh simplification, and more efficient registration strategies to facilitate the handling
of large‑scale buildings and high‑density datasets. Furthermore, the integration with GIS
will be developed to establish a spatially referenced heritage information system, where
GIS serves as a large‑scale foundation map for integrating multiple Nabataean monuments
and their surrounding landscape. This integration will enable spatial analysis, site‑level
heritage management, and seamless linkage between regional geospatial information and
detailed monument‑scale HBIM models.

Author Contributions: Conceptualization, Y.A. and A.B.; methodology, Y.A.; software, Y.A. and
A.B.; validation, Y.A. and A.B.; formal analysis, Y.A.; resources, Y.A. and A.B.; data curation, Y.A.
and A.B.; writing—original draft preparation, Y.A.; writing—review and editing, Y.A. and A.B.; visu‑
alization, Y.A. and A.B. All authors have read and agreed to the published version of the manuscript.

Funding: The authors gratefully acknowledge the Deanship of Scientific Research (DSR) at King
Abdulaziz University, Jeddah, Saudi Arabia, for funding this project under grant No. (IPP: 1011‑137‑
\2026) and for providing technical support.

Institutional Review Board Statement: Not applicable.

Informed Consent Statement: Not applicable.

Data Availability Statement: Data are not available for legal reasons. The site documentation was
conducted under confidentiality agreements with the relevant stakeholders. These agreements per‑
mit publication of the results and outputs presented in this article but do not permit sharing addi‑
tional site files or underlying datasets with third parties, including for internal archiving. Therefore,
no additional dataset is available for public access or internal archiving.

Acknowledgments: The authors would like to express their sincere appreciation to King Abdulaziz
University and the Deanship of Scientific Research (DSR), Jeddah, Saudi Arabia, for their valuable
technical and administrative support throughout this research.

Conflicts of Interest: The authors declare no conflicts of interest.

References

\1. Tschanz, D.W. The Nabataeans: A Brief History of Petra and Madain Saleh; Medina Publishing: Cowes, UK, 2012.
\2. Bowersock, G.W. Roman Arabia; Harvard University Press: Cambridge, CA, USA, 1983.
\3. McKenzie, J. The Architecture of Petra; Oxford University Press: Oxford, UK, 1990.
\4. Taylor, J. Petra and the Lost Kingdom of the Nabataeans; Harvard University Press: Cambridge, MA, USA, 2001.
\5. Nehmé, L. The Nabataeans: The Mada’in Saleh Excavations. In Winter Enrichment Program; KAUST: Thuwal, Saudi Arabia, 2015.
\6. Paolini, A.; Vafadari, A.; Cesaro, G.; Santana Quintero, M.; Van Balen, K.; Vileikis, O.; Fakhoury, L. Risk Management at Heritage
Sites; UNESCO: Paris, France, 2012.
\7. Paradise, T.R. Architecture and Deterioration in Petra: Issues, Trends, and Warnings. In Tourism and Archaeological Heritage
Management at Petra; Comer, D.C., Ed.; Springer: New York, NY, USA, 2012; Volume 1, pp. 79–104. [CrossRef]
\8. El‑Gohary, M.A. Environmental Impacts: Weathering Factors, Mechanism and Forms Affected the Stone Decaying in Petra. J.
Afr. Earth Sci. 2017, 135, 204–212. [CrossRef]
\9. Mustafa, M.H.; Tayeh, S.N.A. The Impacts of Tourism Development on the Archaeological Site of Petra and Local Communities
in Surrounding Villages. Asian Soc. Sci. 2011, 7, 88–95. [CrossRef]
\10. Lubick, N. Petra: An Eroding Ancient City. Geotimes 2004, 49, 22–27.

https://doi.org/10.3390/su182010533

<!-- p. 26 -->

Sustainability 2026, 18, 10533 26 of 27

\11. Cesaro, G.; Jamhawi, M.; Al‑Taher, H.; Farajat, I.; Orbaşli, A. Learning from Participatory Practices: The Integrated Management
Plan for Petra World Heritage Site in Jordan. J. Herit. Manag. 2023, 8, 125–141. [CrossRef]
\12. Quintero, M.; Cesaro, G.; Ishakat, F.; Vandesande, A.; Vileikis Tamayo, O.; Vadafari, A.; Paolini, A.; Van Balen, K.; Fakhoury, L.
Protecting unesco world heritage properties’s integrity: The role of recording and documentation in risk management for petra.
Int. Arch. Photogramm. Remote Sens. Spat. Inf. Sci. 2012, XXXIX‑B5, 121–126. [CrossRef]
\13. Amato, A. Towards the Interoperability of Metadata for Cultural Heritage. In Complex, Intelligent and Software Intensive Systems;
Barolli, L., Ed.; Springer Nature: Cham, Switzerland, 2023; pp. 309–317.
\14. Parente, M.; Bruno, N.; Ottoni, F. HBIM and Information Management for Knowledge and Conservation of Architectural Her‑
itage: A Review. Heritage 2025, 8, 306. [CrossRef]
\15. Lovell, L.J.; Davies, R.J.; Hunt, D.V.L. The Application of Historic Building Information Modelling (HBIM) to Cultural Heritage:
A Review. Heritage 2023, 6, 6691–6717. [CrossRef]
\16. Giovannini, E.C.; Bono, J. From Sources to Levels of Reference (LoRef) for the Virtual Reconstructions of the Priene Theatre: An
Interoperable and Informative HBIM Workflow. Int. Arch. Photogramm. Remote Sens. Spat. Inf. Sci. 2026, XLVIII‑2/W12‑2026,
167–174. [CrossRef]
\17. Argasiński, K.; Tomczak, A. Enhancing Semantic Interoperability of Heritage BIM‑Based Asset Preservation. Heritage 2025, 8,
\410. [CrossRef]
\18. Lanzara, E.; Scandurra, S.; Pulcrano, M.; Acquaviva, S.; Gallo, M.; Palomba, D.; di Luggo, A. VPL for HBIM: Algorithmic Gener‑
ative Processes for the Thematic Mapping of Information Models. In Architectural Graphics; Ródenas‑López, M.A., Calvo‑López,
J., Salcedo‑Galera, M., Eds.; Springer International Publishing: Cham, Switzerland, 2022; pp. 453–463.
\19. Song, Y.M.; Kang, S.H.; Han, J.Y.; Kim, H.J.; Kim, S.Y.; Do, H.R. HBIM (Heritage Building Information Modeling) Strategy for
Managing Repair of Wooden Architectural Heritage in Korea. Int. Arch. Photogramm. Remote Sens. Spat. Inf. Sci. 2025, XLVIII‑
M‑9‑2025, 1407–1412. [CrossRef]
\20. Moyano, J.; Carreño, E.; Nieto‑Julián, J.E.; Gil‑Arizón, I.; Bruno, S. Systematic Approach to Generate Historical Building Infor‑
mation Modelling (HBIM) in Architectural Restoration Project. Autom. Constr. 2022, 143, 104551. [CrossRef]
\21. Daniels, L.; Georgopoulos, A. Doric temple HBIM library for cultural heritage management. ISPRS Ann. Photogramm. Remote
Sens. Spat. Inf. Sci. 2023, X‑M‑1‑2023, 55–62. [CrossRef]
\22. Baik, A. A Comprehensive Heritage BIM Methodology for Digital Modelling and Conservation of Built Heritage: Application
to Ghiqa Historical Market, Saudi Arabia. Remote Sens. 2024, 16, 2833. [CrossRef]
\23. Scandurra, S.; di Luggo, A. BSDD to document state of preservation of architectural heritage in open‑HBIM systems. Int. Arch.
Photogramm. Remote Sens. Spat. Inf. Sci. 2023, XLVIII‑M‑2–2023, 1427–1434. [CrossRef]
\24. Diara, F. HBIM Open Source: A Review. ISPRS Int. J. Geo‑Inf. 2022, 11, 472. [CrossRef]
\25. Banfi, F.; Liu, W. The State of HBIM in Digital Heritage: A Critical and Bibliometric Assessment of Six Emerging Frontiers
(2015–2025). Appl. Sci. 2026, 16, 906. [CrossRef]
\26. Bac‑Bronowicz, J.; Piech, I.; Wojciechowska, G. Integrated TLS‑UAV Workflow for HBIM Generation in Heritage Documentation.
Remote Sens. 2026, 18, 857. [CrossRef]
\27. Liu, J.; Willkens, D.; Gentry, R. Developing a Practice‑Based Guide to Terrestrial Laser Scanning (TLS) for Heritage Documenta‑
tion. Heritage 2025, 8, 313. [CrossRef]
\28. Alshawabkeh, Y. Color and Laser Data as a Complementary Approach for Heritage Documentation. Remote Sens. 2020, 12, 3465.
[CrossRef]
\29. Gines, J.L.C.; Cervera, C.B. Toward Hybrid Modeling and Automatic Planimetry for Graphic Documentation of the Archaeolog‑
ical Heritage: The Cortina Family Pantheon in the Cemetery of Valencia. Int. J. Archit. Herit. 2020, 14, 1210–1220. [CrossRef]
\30. Dostal, C.; Yamafune, K. Photogrammetric Texture Mapping: A Method for Increasing the Fidelity of 3D Models of Cultural
Heritage Materials. J. Archaeol. Sci. Rep. 2018, 18, 430–436. [CrossRef]
\31. Stałowska, P.; Suchocki, C.; Rutkowska, M. Crack Detection in Building Walls Based on Geometric and Radiometric Point Cloud
Information. Autom. Constr. 2022, 134, 104065. [CrossRef]
\32. Wang, Q.; Sohn, H.; Cheng, J.C.P. Development of a Mixed Pixel Filter for Improved Dimension Estimation Using AMCW Laser
Scanner. ISPRS J. Photogramm. Remote Sens. 2016, 119, 246–258. [CrossRef]
\33. Tang, P.; Akinci, B.; Huber, D. Quantification of Edge Loss of Laser Scanned Data at Spatial Discontinuities. Autom. Constr. 2009,
18, 1070–1083. [CrossRef]
\34. Mechelke, K.; Kersten, T.; Lindstaedt, M. Comparative Investigations into the Accuracy Behaviour of the New Generation of Ter‑
restrial Laser Scanning Systems. In Proceedings of the 8th Conference on Optical 3D Measurement Techniques, Zurich, Switzer‑
land, 9–12 July 2007; Volume 1.
\35. Sapirstein, P. Accurate Measurement with Photogrammetry at Large Sites. J. Archaeol. Sci. 2016, 66, 137–145. [CrossRef]

https://doi.org/10.3390/su182010533

<!-- p. 27 -->

Sustainability 2026, 18, 10533 27 of 27

\36. Tscharf, A.; Rumpler, M.; Fraundorfer, F.; Mayer, G.; Bischof, H. On the use of uavs in mining and archaeology—Geo‑accurate
3d reconstructions using various platforms and terrestrial views. ISPRS Ann. Photogramm. Remote Sens. Spat. Inf. Sci. 2015,
II‑1/W1, 15–22. [CrossRef]
\37. Arza‑García, M.; Gil‑Docampo, M.; Ortiz‑Sanz, J. A Hybrid Photogrammetry Approach for Archaeological Sites: Block Align‑
ment Issues in a Case Study (the Roman Camp of A Cidadela). J. Cult. Herit. 2019, 38, 195–203. [CrossRef]
\38. Murtiyoso, A.; Grussenmeyer, P.; Suwardhi, D.; Awalludin, R. Multi‑Scale and Multi‑Sensor 3D Documentation of Heritage
Complexes in Urban Areas. ISPRS Int. J. Geo‑Inf. 2018, 7, 483. [CrossRef]
\39. Reinoso‑Gordo, J.F.; Gámiz‑Gordo, A.; Barrero‑Ortega, P. Digital Graphic Documentation and Architectural Heritage: Deforma‑
tions in a 16th‑Century Ceiling of the Pinelo Palace in Seville (Spain). ISPRS Int. J. Geo‑Inf. 2021, 10, 85. [CrossRef]
\40. Alshawabkeh, Y.; Baik, A.; Miky, Y. Integration of Laser Scanner and Photogrammetry for Heritage BIM Enhancement. ISPRS
Int. J. Geo‑Inf. 2021, 10, 316. [CrossRef]
\41. Sztwiertnia, D.; Ochałek, A.; Tama, A.; Lewińska, P. HBIM (Heritage Building Information Modell) of the Wang Stave Church
in Karpacz—Case Study. Int. J. Archit. Herit. 2021, 15, 713–727. [CrossRef]
\42. López, F.J.; Lerones, P.M.; Llamas, J.; Gómez‑García‑Bermejo, J.; Zalama, E. A Framework for Using Point Cloud Data of Heritage
Buildings Toward Geometry Modeling in A BIM Context: A Case Study on Santa Maria La Real De Mave Church. Int. J. Archit.
Herit. 2017, 11, 965–986. [CrossRef]
\43. Banfi, F.; Brumana, R.; Stanga, C. Extended Reality and Informative Models for the Architectural Heritage: From Scan‑to‑Bim
Process to Virtual and Augmented Reality. Virtual Archaeol. Rev. 2019, 10, 14–30. [CrossRef]
\44. Miky, Y.; Alshawabkeh, Y.; Baik, A. Using Deep Learning for Enrichment of Heritage BIM: Al Radwan House in Historic Jeddah
as a Case Study. Herit. Sci. 2024, 12, 255. [CrossRef]
\45. Murphy, M.; McGovern, E.; Pavia, S. Historic Building Information Modelling—Adding Intelligence to Laser and Image Based
Surveys of European Classical Architecture. ISPRS J. Photogramm. Remote Sens. 2013, 76, 89–102. [CrossRef]
\46. Barazzetti, L. Parametric As‑Built Model Generation of Complex Shapes from Point Clouds. Adv. Eng. Inform. 2016, 30, 298–311.
[CrossRef]
\47. Yang, X.; Lu, Y.‑C.; Murtiyoso, A.; Koehl, M.; Grussenmeyer, P. HBIM Modeling from the Surface Mesh and Its Extended Capa‑
bility of Knowledge Representation. ISPRS Int. J. Geo‑Inf. 2019, 8, 301. [CrossRef]
\48. Alshawabkeh, Y.; Baik, A. Integration of Photogrammetry and Laser Scanning for Enhancing Scan‑to‑HBIM Modeling of Al Ula
Heritage Site. Herit. Sci. 2023, 11, 147. [CrossRef]
\49. Alshawabkeh, Y.; Baik, A.; Miky, Y. HBIM for Conservation of Built Heritage. ISPRS Int. J. Geo‑Inf. 2024, 13, 231. [CrossRef]
\50. Nehmé, L. Towards an Understanding of the Urban Space of Madāʾin Ṣāliḥ, Ancient Ḥegrā, through Epigraphic Evidence. In
Proceedings of the Seminar for Arabian Studies; Archaeopress: London, UK, 2005; pp. 155–175.
\51. Fitzner, B.; Heinrichs, K. Damage Diagnosis at Stone Monuments—Weathering Forms, Damage Categories and Damage Indices.
Acta‑Univ. Carol. Geol. 2001, 1, 12–13.
\52. Eklund, S. Stone Weathering in the Monastic Building Complex on Mountain of St Aaron in Petra, Jordan, Faculty of Arts,
Institute for Cultural Research. 2008. Available online: https://api.semanticscholar.org/CorpusID:161354391 (accessed on 1 July
2026).
\53. Brünnow, R.E.; von Domaszewski, A. Die Provincia Arabia; K.J. Trübner: Strassburg, France, 1904; Volume 1.
\54. Musil, A. Die Provincia Arabia von R. E. Brünnow, A. v. Domaszewski Und J. Euting. Wien. Z. Kunde Morgenl. 1904, 18, 379–404.
\55. Besl, P.J.; McKay, N.D. A Method for Registration of 3‑D Shapes. IEEE Trans. Pattern Anal. Mach. Intell. 1992, 14, 239–256.
[CrossRef]

Disclaimer/Publisher’s Note: The statements, opinions and data contained in all publications are solely those of the individual au‑
thor(s) and contributor(s) and not of MDPI and/or the editor(s). MDPI and/or the editor(s) disclaim responsibility for any injury to
people or property resulting from any ideas, methods, instructions or products referred to in the content.

https://doi.org/10.3390/su182010533
