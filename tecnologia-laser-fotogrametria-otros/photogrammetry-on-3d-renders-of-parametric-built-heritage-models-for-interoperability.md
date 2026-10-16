---
type: libro
title: "Photogrammetry on 3D Renders of Parametric Built Heritage Models for Interoperability"
author: ""
categoria: "Tecnología láser, fotogrametría, otros"
paginas: 8
extraccion: "texto"
fuente: "local:E:/DISCIPLINAS, TEXTOS Y MAPAS/Biblioteca digital/Tecnología láser, fotogrametría, otros/Photogrammetry on 3D Renders of Parametric Built Heritage Models for Interoperability.pdf"
convertido: 2026-10-13
---

# Photogrammetry on 3D Renders of Parametric Built Heritage Models for Interoperability

> Texto extraído de `Tecnología láser, fotogrametría, otros/Photogrammetry on 3D Renders of Parametric Built Heritage Models for Interoperability.pdf` (8 páginas, texto). El PDF original está en el disco E: (DISCIPLINAS, TEXTOS Y MAPAS\Biblioteca digital); `<!-- p. N -->` marca el inicio de cada página.

<!-- p. 1 -->

The International Archives of the Photogrammetry, Remote Sensing and Spatial Information Sciences, Volume XLVIII-2/W12-2026
11th Intl. Workshop 3D-ARCH "3D Virtual Reconstruction and Visualization of Complex Architectures", 10–12 February 2026, Ancona, Italy

Photogrammetry on 3D Renders of Parametric Built Heritage Models for Interoperability

Etienne Sommer1, Vasili Manfredi2, Cecilia Maria Bolognesi2, Mathieu Koehl1, Pierre Grussenmeyer1

1Universit´e de Strasbourg, INSA Strasbourg, CNRS, ICube Laboratory UMR 7357, 67084 Strasbourg, France
(etienne.sommer, mathieu.koehl, pierre.grussenmeyer)@insa-strasbourg.fr
2 Dept. of Architecture, Built environment and Construction engineering, Politecnico di Milano, 20133 Milano, Italy
(vasili.manfredi, cecilia.bolognesi)@polimi.it

Keywords: Virtual Photogrammetry, 3D Reconstruction, Blender, Low-Poly Mesh, Procedural Rendering, Cultural Heritage.

Abstract

Modelling cultural heritage necessitates the use of specific software and file formats that can be difficult to transpose between one
another. These interoperability challenges are particularly acute when employing parametric modelling tools, whether within the
context of HBIM or 4D modelling (i.e., the reconstruction of past states of heritage objects). Standard export workflows often fail to
preserve complex procedural textures or require time-consuming manual UV unwrapping, rendering direct conversion inefficient.
In this study, the potential of applying photogrammetry to synthetic images is investigated as a solution to these limitations. A
rigorous dataset is generated in Blender based on a 4D parametric model of a Rhenish castle currently in ruins, utilising path tracing
to ensure visual fidelity. This method ensures interoperability by consolidating multiple complex, software-dependent parametric
objects into a single, universally compatible mesh. This transformation allows the model to be directly employed across diverse
software environments, independent of the original creation tools. Subsequently, the photogrammetric mesh is decimated and
optimised to facilitate sharing and viewing on all computer configurations. To validate the approach, a quantitative evaluation is
performed: the geometric deviation between the original parametric model and the reconstructed mesh is analysed, and rendering
performance is benchmarked to demonstrate the method’s suitability for dissemination and visualisation tools.

\1. Introduction polygon count prior to texturing. Finally, the reliability of this
method is assessed through quantitative analysis, specifically
The importance of 3D modelling applied to built heritage has regarding geometric deviation and rendering performance.
been increasingly highlighted in recent years. It provides a
digital record of heritage objects, regardless of their size or
\2. Related Worklocation, ensuring continuous monitoring while also preserving
a digital archive in case of destruction or alteration. Such
3D models can take different forms: on-site surveys using Cultural heritage surveys are no longer limited to simple
conventional topographic methods (Tsiachta et al., 2024), the geometry; they now incorporate semantic data, information on
use of field data for modelling within an HBIM environment state changes, or elements of geometric alteration (Niccolucci
(Rocha et al., 2020), or parametric modelling applicable to et al., 2023). Consequently, the mesh or 3D object is no
various elements of the same type (Parrinello and Pettineo, longer treated as a static representation of the real object at
2025). a specific moment. Instead, it is viewed as an entity capable
of evolving over time, reflecting changes caused by human
However, in the latter case, significant interoperability issues activity or environmental factors (Cinquepalmi and Cumo,
arise. The resulting models are often optimised for the 2022). To manage this evolution, the static geometry of a
native software in which they are produced and rely on standard mesh is insufficient. Tools capable of adapting to
complex procedural textures or node graphs that fail to translate the shapes and specific characteristics of heritage elements
through standard exchange formats (such as FBX or IFC). are therefore required (Murphy et al., 2009). The ability to
Consequently, these assets are not directly usable in other modify geometry makes it possible to test new hypotheses
environments without manual conversion. regarding construction and historical evolution (Christenson,
2025). Although these methods are highly effective, they often
Beyond conservation, the dissemination of heritage to the suffer from a lack of interoperability or remain specific to
public is also a key objective (Innocente et al., 2024). To proprietary software (Di Donato et al., 2022; Moyano et al.,
achieve this, models must be interoperable across different 2022).
environments and sufficiently optimised to enable sharing on
platforms or real-time visualisation (Bolognesi and Manfredi, To address these challenges, virtual photogrammetry offers a
2024). In response to this challenge, photogrammetry is applied universal solution by shifting the exchange from code to image.
to synthetic 3D renders of a parametric model of a medieval It enables the conversion of any complex procedural object
castle in Alsace, France, created in Blender. This workflow into a standardised mesh through the generation of synthetic
addresses the limitations of standard export methods by views (Esmaeili and Thwaites, 2016). This process fixes the
consolidating multiple software-dependent parametric objects state of the parametric model to a defined geometry with
into a single, unified mesh. This process makes it possible controlled precision and has multiple applications (Frommholz,
to convert the model into a conventional format optimised for 2019; Rubinstein, 2025), while remaining iterative: a new
visualisation and dissemination, by drastically reducing the virtual acquisition can be done after each modification. The

This contribution has been peer-reviewed.
https://doi.org/10.5194/isprs-archives-XLVIII-2-W12-2026-447-2026 | © Author(s) 2026. CC BY 4.0 License. 447

<!-- p. 2 -->

The International Archives of the Photogrammetry, Remote Sensing and Spatial Information Sciences, Volume XLVIII-2/W12-2026
11th Intl. Workshop 3D-ARCH "3D Virtual Reconstruction and Visualization of Complex Architectures", 10–12 February 2026, Ancona, Italy

interoperability of the resulting meshes depends not only approach employed in a drone survey. The terrain is from
on their format but also on model optimisation to allow the scene prior to this process. This exclusion allows for
manipulation in third-party software (Koehl et al., 2024), unrestricted camera placement, facilitating a greater number
ensuring that the necessary data is retained according to the of convergent views onto the model, while also avoiding the
final objective (Banfi, 2017). unnecessary processing of vegetation which does not require
re-modelling. From this initial configuration, a preliminary
set of renders was generated to produce a simplified mesh,
\3. Methodology
serving to verify the reconstruction quality and identify areas
lacking sufficient coverage. Consequently, supplementary
Based on data acquired on-site or available online, a 4D model camera positions were added to target these occluded zones,
of the Birkenfels Castle was produced. This model incorporates ensuring that the GSD remained consistent with the global
elements visible in the current ruins, alongside structures project parameters. This iterative process resulted in a complete
that are no longer extant. The latter were reconstructed dataset of 823 images.
based on archaeological hypotheses and comparisons with
ruins still visible at other similar castles of the region. Each To assess the efficiency of this distribution, a comparison
component was modelled using parametric and procedural was performed using the ’Plan Mission’ tool in Agisoft
processes, following the methodology described by Sommer Metashape (Agisoft Metashape, 2025), which automates
et al. (2025b). This approach enables individual objects to camera positioning based on an input mesh. With a comparable
be adapted rapidly, allowing for structural modifications in GSD of 4.5 mm and a standard image overlap of 70%, the
accordance with feedback from archaeologists specialising in automated tool projected a survey of 737 images in a very
these edifices. Furthermore, this method offers the advantage similar way to the icosphere. This figure is not significantly
of being applicable to various types of ruins, thereby covering lower than the 823 images obtained via the icosphere method,
a wider scope of application. suggesting that the time required to compute a strictly optimised
new set offers limited gain. Furthermore, increasing the overlap
3.1 Proposed Method for Synthetic Data Acquisition
to 80% caused the projected count to surge to 1,874 images, a
number considerably higher than that of the proposed method.
The parametric modelling method is carried out directly within
the Blender software. It notably utilises an instancing system
For each position on the icosphere, the camera is oriented
that allows an initial object to be referenced, duplicated,
towards the model or a specific point of interest. Renders
translated, scaled, or rotated without increasing the scene’s
are subsequently generated via path tracing (Sommer et al.,
polygon count. This instancing system is applicable to any
2025a), with all lighting effects such as shadows or reflections
type of object, provided that its geometry remains unmodified.
removed beforehand to simulate overcast weather conditions
For example, altering the position of a single vertex relative to
with diffuse lighting. The use of path tracing enables the
the initial model is not feasible, as this no longer constitutes a
creation of high-quality image renderings and also allows for
reference to the original object, but rather a modification of its
the correct processing of procedural textures applied to different
geometry. Consequently, the primary advantage of this system
objects. Figure 1 shows an example of a rendering used in the
is that it enables the creation of complex and dense scenes while
virtual photogrammetry process.
maintaining a low polygon count.

On the other hand, a limitation of this method is quickly
encountered: as this system is specific to the Blender software,
instances cannot be exported directly. It is possible to convert
these instances to generate actual geometry, but this introduces
a substantial quantity of polygons into the scene, potentially
causing the software to terminate unexpectedly. This high
polygon count hinders straightforward use in external software.
Furthermore, the issue of texturing presents similar challenges.
Although texture baking is feasible and capable of automation
(Blender enables process automation via a Python API), the
individual export of each element with its own texture poses
significant problems regarding file management and detail
resolution. UV unwrapping and specific dimensions would
need to be performed for each object in relation to the detail
required for visualisation, to avoid the unnecessary storage of
Figure 1. Example of a rendering in Blender used for virtualdata that offers no subsequent utility.
photogrammetry
The virtual photogrammetry method proposed in this article
addresses these issues. It enables the consolidation of all
elements into a single comprehensive mesh and the application 3.2 Orientation via Structure from Motion (SfM) on
of textures according to a specific Ground Sampling Distance Synthetic Data
(GSD), depending on the desired level of detail. This GSD
is defined using standard methods based on the acquisition Image orientation and photogrammetric model reconstruction
distance and virtual camera parameters, such as sensor size, are performed using Metashape. Generally, the use of Ground
pixel count, and focal length (Luhmann et al., 2023). An Control Points (GCPs) within a photogrammetric project
icosphere is positioned around the study object so that its enables the referencing and scaling of the model by determining
vertices serve as locations for each render, similar to the camera positions in three-dimensional space. In the context

This contribution has been peer-reviewed.
https://doi.org/10.5194/isprs-archives-XLVIII-2-W12-2026-447-2026 | © Author(s) 2026. CC BY 4.0 License. 448

<!-- p. 3 -->

The International Archives of the Photogrammetry, Remote Sensing and Spatial Information Sciences, Volume XLVIII-2/W12-2026
11th Intl. Workshop 3D-ARCH "3D Virtual Reconstruction and Visualization of Complex Architectures", 10–12 February 2026, Ancona, Italy

of this study, the position and rotation of each image are note that, for this study, no translation is performed between
already known, owing to the positioning method described the two models to align them. This facilitates the evaluation
in subsection 3.1. This configuration eliminates the need for of the method’s ability to correctly position the reconstruction
GCPs. in space in the absence of control points, relying only on the
known camera positions and rotations.
The Blender virtual camera was configured to simulate a
full-frame camera. Its sensor measures 36 × 24 mm with a 4.1.1 Study of Surface Planarity The capability of the
resolution of 7680 × 5120 pixels, resulting in a pixel size of method to reproduce planar surfaces is assessed by comparing
36 ÷ 7680 = 24 ÷ 5120 ≈4.69 µm. Consequently, the images points from the photogrammetric mesh against the reference
have a GSD of approximately 4.5 mm. Image orientation surface exported from Blender. This comparison is performed
was performed using the ”High” setting in Metashape, with within the CloudCompare software utilising the Cloud/Mesh
positioning accuracy of the images set to 0.00001 metres, the distance tool. Signed distances are thereby obtained, as
minimum value permitted by the software. This extremely low presented in the histogram in figure 3. The distribution of these
uncertainty is derived directly from the a priori knowledge of deviations across the mesh is illustrated in figure 4.
the image positions and rotations. No distortion correction is
applied to the images since they were taken using a ”perfect”
virtual lens without optical distortions. The results of SfM
on these images are shown in figure 2. Once this basis has
been established, the 3D reconstruction, mesh optimisation, and
quantitative and qualitative analysis of the models are presented
in Section 4.

Figure 3. Histogram of signed distances for a planar surface

Figure 2. Orientation of the 3D renders in Metashape

\4. 3D reconstruction and mesh optimisation

The 3D reconstruction of the virtual photogrammetric model is
performed directly within Metashape software. It is generated
from depth maps using the ”High” parameter for both quality
and face count configuration. The result is a comprehensive
mesh of the scene that meets the study’s requirements: all
individual parametric objects from the Blender project are
consolidated into a single object. Furthermore, the procedural
textures of each object are converted into photogrammetric
textures applied directly to the mesh. In the subsequent part Figure 4. Distribution of deviations on the planar surface
of the study, a quantitative and qualitative analysis of the The colour scale is similar to that of figure 3
photogrammetric mesh is presented. Following this, a mesh
decimation process aimed at optimisation is performed and
quantified. The mesh optimisation method employed is that For 8,735 compared points, the mean distance is 0.2 mm
proposed by Manfredi et al. (2025). and the standard deviation is 1.1 mm. It is noteworthy that
the spatial distribution of these deviations corresponds to the
4.1 Quantitative Analysis of the Photogrammetric Mesh texture applied to the parametric model (a Voronoi-style pattern
used to simulate the ground). Based on these results, it
The quantitative analysis of the reconstruction is performed by is possible to conclude that the method enables the faithful
comparing the model reconstructed via photogrammetry to the reconstruction of planar surfaces. Should higher accuracy be
parametric model employed as a case study. This presents required, investigating the influence of the parametric mesh’s
a significant advantage: the ground truth can be considered texture on the capacity to preserve surface planarity would be
perfect. However, given the complexity of the scene and the of interest.
topology of the modelled objects, a simultaneous comparison
of the entire mesh is not appropriate. Consequently, the analysis 4.1.2 Study of a Complex Surface Composed of Stones
focuses on several individual elements of the mesh in relation of Varying Dimensions Paragraph 4.1.1 demonstrated the
to the specific objects they represent. It is also important to method’s capability to reconstruct a planar surface. This

This contribution has been peer-reviewed.
https://doi.org/10.5194/isprs-archives-XLVIII-2-W12-2026-447-2026 | © Author(s) 2026. CC BY 4.0 License. 449

<!-- p. 4 -->

The International Archives of the Photogrammetry, Remote Sensing and Spatial Information Sciences, Volume XLVIII-2/W12-2026
11th Intl. Workshop 3D-ARCH "3D Virtual Reconstruction and Visualization of Complex Architectures", 10–12 February 2026, Ancona, Italy

section now focuses on the examination of a complex surface. from 1,276,458 faces in the original parametric model to
It comprises a collection of stones with varying lengths 725,026 in the final mesh.
and heights, each measuring approximately several tens of
centimetres. These stones correspond to the bossage masonry 4.1.3 Conclusion of the Quantitative Study of the
typical of Rhenish castles: they feature a convex protrusion Photogrammetric Reconstruction Comparisons between
of several centimetres at the centre, which contains a lifting the photogrammetric model and the ground truth have
hole. Both features are accurately represented in the theoretical demonstrated the method’s reconstruction capability. Surface
model. The histogram in figure 5 presents the distribution of planarity is preserved with millimetric precision, providing
these deviations for 363,574 points, while figure 6 illustrates a robust foundation for subsequent mesh decimation.
the spatial distribution of these deviations across the mesh. Furthermore, complex surfaces can also be faithfully
reconstructed. It should be noted that the reconstruction
tends to smooth surfaces, potentially resulting in larger
deviations in areas of high curvature or when joining distinct
objects. Finally, the near-zero mean deviation confirms that the
photogrammetric reconstruction, performed without control
points, successfully georeferenced the model by relying on the
a priori known camera positions and rotations. These results
extend to other surface types within the model, not presented
here for the sake of conciseness.

4.2 Reduction of the Number of Polygons in the
Photogrammetric Mesh

The workflow evaluates the decimation method PixelVR
proposed by Manfredi et al. (2025). The objective is to
assess its effectiveness in reducing geometric complexity
Figure 5. Histogram of signed distances for a complex surface while preserving visual fidelity for visualisation. Standard
optimisation strategies relying on Blender’s native architecture,
specifically a legacy approach using the collapse modifier and a
mixed strategy incorporating planar decimation, were initially
established as comparative baselines. The legacy strategy
necessitates a segmentation process where boundary vertices
must be manually protected to ensure seamless re-joining, while
the mixed strategy augments this with manual edge collapsing
and vertex merging. However, these operator-driven workflows
require extensive manual intervention to maintain topological
continuity and prevent artefacts. Due to this high dependency
on manual oversight and the resulting variability, these native
methods were excluded from the primary pipeline in favour
of the PixelVR solution, which offers a more automated
and standardised workflow specifically optimised for real-time
constraints.
Figure 6. Detail of the stone wall reconstruction deviations. The
Prior to optimisation, the dataset underwent a cleaning phase
joints, shown in dark yellow, clearly exhibit larger deviations
in Blender in order to remove detached or unused polysurfaces,
The colour scale is similar to that of figure 5
reconstruction noise, and incongruent geometry not belonging
to the primary subject. Additionally, operations included
the removal of overlapping vertices, coplanar faces, and
It is observed that the mean is approximately 0.7 mm and non-manifold elements, which are the main issues inducing
the standard deviation approximately 3.4 mm, values which instability during decimation and texture baking.
are slightly higher than those obtained for the planar surface.
Analysis of the location of these deviations reveals that they 4.2.1 PixelVR Decimation It introduces a procedural,
occur mostly at the surfaces generated to join the individual segmentation-aware, and curvature-informed semi-automated
stones. However, these connecting surfaces do not exist in the workflow in Blender. This approach prioritises reproducibility,
reference parametric model, where the stones are positioned scalability, and consistency for large photogrammetric
adjacently. This identifies the primary source of error: datasets targeting real-time environments. The process
the generation of a continuous surface to connect multiple starts with model segmentation. Following cleaning, the
disjointed elements. Figure 6 highlights this effect. This high-poly mesh is segmented into spatially and topologically
error is compounded by inaccuracies found at the lifting holes, coherent parts. Unlike geometric subdivision, this considers
where the photogrammetric mesh tends to smooth the cavity in structural continuity to reduce local complexity and stabilise
comparison to the reference model. These errors remain within optimisation. Concurrently, a curvature-based vertex
the range of a few millimetres and affect only a fraction of the classification is performed. An analysis evaluates local
points, leading to the conclusion that the method is capable of edge density and geometric variation to identify regions where
reconstructing complex parametric surfaces while effectively aggressive decimation would cause perceptual degradation.
merging separate objects. This consolidation enables a drastic These vertices are assigned to a protected group excluded
optimisation of the geometry, reducing the model complexity from simplification. While not universally linked to perceptual

This contribution has been peer-reviewed.
https://doi.org/10.5194/isprs-archives-XLVIII-2-W12-2026-447-2026 | © Author(s) 2026. CC BY 4.0 License. 450

<!-- p. 5 -->

The International Archives of the Photogrammetry, Remote Sensing and Spatial Information Sciences, Volume XLVIII-2/W12-2026
11th Intl. Workshop 3D-ARCH "3D Virtual Reconstruction and Visualization of Complex Architectures", 10–12 February 2026, Ancona, Italy

importance, in heritage datasets curvature provides a robust previously introduced in section 4.1.1, is not detailed herein.
heuristic for preserving carved, ornamented, or organic This surface comprises a minimal number of faces that maintain
features. For reduction, the strategy employs a recursive the planarity of the original parametric geometry, rendering
decimation protocol. Instead of a single aggressive pass, further detailed discussion unnecessary. Conversely, it is of
a multi-stage process uses predefined presets. Each stage greater relevance to examine the effects of decimation on
operates on mesh instances, enabling controlled evaluation of complex surfaces characterised by geometric irregularities.
optimisation levels. Here, protected vertices remain intact, To achieve this, the area selected for analysis corresponds
redundant planar regions are collapsed, and topological checks identically to the zone described in section 4.1.2. The histogram
remove non-manifold edges. This approach reduces the illustrating the deviations between the parametric reference and
instability of extreme one-pass decimation on dense meshes. the optimised model is presented in figure 9.
Finally, segmented parts are reunited into a unified mesh.
Consistent boundary vertices ensure adjacent segments align
without visible seams. Coincident vertices are merged, normals
recalculated, and scale transformations applied to produce a
watertight, engine-ready asset. From the original 6,919,582
faces, the process yielded 281,005 faces, with adaptive density
simplifying each section to its specific level of detail. Figures 7
and 8 show the original reconstruction and the final decimated
mesh. A colour scale representing face surface area is used to
visualise the decimation.

Figure 9. Histogram of signed distances for a complex surface
on the optimised mesh

The analysis reveals a mean deviation of approximately 6 mm
and a standard deviation of 7 mm. These deviation values
are higher than those observed for the initial photogrammetric
model. An analysis of the distribution reveals a pronounced
asymmetry towards positive values. The vast majority of points
are located above zero, indicating a systematic bias wherein
the optimised model tends to protrude slightly relative to the Figure 7. High poly photogrammetric mesh from 3D renders
reference model. Furthermore, the distribution is not unimodal. with faces coloured according to their surface area
It exhibits multiple local peaks, specifically around 0 mm, 5 (6,919,582 faces)
mm, and 12 mm. This suggests that the error is not random
but structural in nature, corresponding to distinct levels of
geometric detail, such as the stone surfaces versus the masonry
joints, which are processed differently during the simplification
stage. These discrepancies can be attributed to the surface
approximation process, which inevitably results in a reduction
of detail and a divergence from the original geometric features.
However, given the calculated metrics, the outcome of the
decimation process remains satisfactory, maintaining a close
fidelity to the original surface structure.

Furthermore, in contrast to the parametric model, which is
composed of multiple distinct elements constructed on an
object-by-object basis, it is possible in this case to perform a
direct comparison between the entire photogrammetric mesh
and the optimised model. While this global approach does
not permit a precise, localised analysis of specific surface
Figure 8. Low poly mesh decimated with PixelVR with faces reconstruction quality, it provides a comprehensive overview
coloured according to their surface area of the decimation process across the dataset. Figure 10, which
(281,005 faces) illustrates these geometric deviations, reveals a mean deviation
of 1.2 mm and a standard deviation of 4.6 mm. The histogram
is characterised by a highly peaked unimodal distribution that
4.2.2 Quantitative Analysis of the Optimised Mesh is centred approximately on zero. In contrast to the preceding
Following the same methodology applied to compare the local analysis, no significant secondary peaks are observed in
photogrammetric mesh with the initial parametric model, this global dataset. The majority of points are concentrated
the quality of the decimated model is evaluated using the within a minimal error range, specifically between -2 mm and
CloudCompare software. The analysis of the planar surface, +5 mm. Although the tails of the distribution extend to several

This contribution has been peer-reviewed.
https://doi.org/10.5194/isprs-archives-XLVIII-2-W12-2026-447-2026 | © Author(s) 2026. CC BY 4.0 License. 451

<!-- p. 6 -->

The International Archives of the Photogrammetry, Remote Sensing and Spatial Information Sciences, Volume XLVIII-2/W12-2026
11th Intl. Workshop 3D-ARCH "3D Virtual Reconstruction and Visualization of Complex Architectures", 10–12 February 2026, Ancona, Italy

centimetres, they represent a negligible proportion of the total The geometric details present in the photogrammetric model
surface area. It can be concluded that the decimation method have been faithfully reconstructed. Edges are sharp, and
maintains fidelity to the initial reconstruction, and by extension, planar surfaces appear free of noise. Moreover, the
to the original parametric model by preserving global coherence geometric optimisation of the model facilitated the smoothing
despite the significant simplification of the mesh geometry. of planar surfaces through face count reduction, whilst
retaining sufficient geometry to accurately depict more
complex morphological transitions. Additionally, the textures
correspond accurately to the level of detail present in the
initial images, and they have been correctly mapped onto the
model. Originating from procedural textures mathematically
generated within Blender using its proprietary node system, the
resulting photogrammetric textures enabled the conversion and
consolidation of the entire texture set directly onto the unified
model. The subsequent baking of these textures ensured the
preservation of this level of detail on the optimised model,
thereby maintaining visual quality consistency throughout each
stage of the processing workflow. Figure 11 presents these
results, comparing the wireframe and the rendering for each
model.

Figure 10. Histogram of signed distances for the entire 5. Performance Gain Analysis for Rendering and
reconstruction Visualisation

The geometric and textural optimisation of parametric
4.3 Qualitative Analysis of the Conversion from the models offers significant advantages. Primarily, it enhances
Parametric Model to the Photogrammetric and interoperability between diverse software environments by
Optimised Models eliminating dependencies on proprietary parameters inherent
to the original modelling tools. Furthermore, it facilitates theHaving established that the photogrammetric reconstruction
manipulation and editing of models, thereby enabling theirand its optimisation exhibit minimal deviation from the initial
utilisation on lighter, more portable computing configurations.parametric model, the qualitative analysis of the reconstruction
enables the determination of whether the result is visually Within the context of heritage dissemination, which frames
satisfactory in comparison to the initial parametric reference. this study, the production of high-quality images and videos
In the context of this study, the analysis is restricted to is essential for sharing digital assets. However, for complex
a qualitative comparison of the renderings. Mathematical parametric models, rendering times can extend to tens of
comparison indices exist, such as the Structural Similarity minutes or even hours per frame. Reducing this computational
Index (SSIM) score proposed by Wang et al. (2004), but burden is therefore critical to enable the generation of
in the present case, a geometric alteration of the model is substantial volumes of content.
performed. This transformation could yield SSIM results that
are not reflective of rendering quality, but rather biased by the To quantify the efficiency gains achieved through the proposed
underlying changes in the model’s geometric structure. workflow, a comparative analysis is conducted using path

Parametric Model High Poly Model Optimised Model

Figure 11. Qualitative comparison of wireframes and textured renders of each model

This contribution has been peer-reviewed.
https://doi.org/10.5194/isprs-archives-XLVIII-2-W12-2026-447-2026 | © Author(s) 2026. CC BY 4.0 License. 452

<!-- p. 7 -->

The International Archives of the Photogrammetry, Remote Sensing and Spatial Information Sciences, Volume XLVIII-2/W12-2026
11th Intl. Workshop 3D-ARCH "3D Virtual Reconstruction and Visualization of Complex Architectures", 10–12 February 2026, Ancona, Italy

tracing rendering. This evaluation compares two distinct than resource-intensive procedural mathematical evaluations.
states of the castle: the reference parametric model and the This optimisation is quantified by the data: generating
initial high-poly photogrammetric mesh. For each model, the imagery at a high resolution of 7680×5120 pixels using the
rendering time per sample is evaluated in order to compare photogrammetric mesh requires approximately the same time
the time savings of the method for generating images from as rendering the parametric model at a resolution of 1920×1280
the model. Within the Blender environment, path tracing pixels.
is the primary method employed to achieve photorealistic
results. However, this technique relies on a large number
\6. Conclusion
of iterations to reach noise convergence. The rate of this
convergence is inversely proportional to the scene’s complexity;
This study has validated the application of virtual
as the number of elements and their complexity increase,
photogrammetry utilising synthetic imagery generated within
so does the computational burden. By utilising the Blender
the Blender software environment. A substantial number of
Python API, the precise duration of individual iterations can
individual parametric objects whose creation is inherently
be extracted. This allows for a comparative analysis of the total
software-specific were successfully consolidated into a
time required to reach a fixed iteration threshold for each model
single, unified mesh. This resulting geometry is compatible
typology. To ensure the validity of these benchmarks, all tests
with any standard 3D modelling environment, thereby
are conducted from a fixed camera viewpoint under identical
ensuring significant cross-platform interoperability. Beyond
lighting conditions, provided by a High Dynamic Range Image
the consolidation of geometric elements, the mathematical
(HDRI) environment. Additionally, the surrounding terrain is
procedural textures native to the source software were
excluded from the scene to strictly isolate the computational
effectively converted into unified photogrammetric texture
load attributable to the castle geometry, preventing vegetation
maps. This methodology circumvents the requirement for
or ground surfaces from biasing the performance metrics.
the individual UV unwrapping of each object, as well as
Furthermore, the study is replicated across various resolutions
the necessity to generate discrete textures for every separate
to assess the impact of output size, a decisive factor in
element. It also enables the precise definition of the desired
determining the perceptibility of fine details. Figure 12
level of detail for texture generation based on virtual camera
illustrates the temporal evolution of the rendering process
parameters, thus guaranteeing a consistent resolution and
across the tested scenarios.
visual homogeneity across the entire model. Finally, it has
been demonstrated that, in addition to producing a unified
and interoperable asset, this approach yields substantial time
savings when utilising the model for subsequent photorealistic
rendering tasks.

Several avenues for future research warrant further
investigation. In particular, it would be beneficial to establish
a more rigorous methodology for defining the optimal
positions and orientations of virtual cameras during the virtual
photogrammetric survey. Such an optimisation would serve to
limit the requisite number of images, thereby streamlining the
subsequent photogrammetric processing workflow. Moreover,
this method facilitates the creation of models that are readily
integrable into applications where performance fluidity is
paramount, such as Virtual Reality (VR) environments or
Figure 12. Rendering time for both models at different online sharing platforms accessible via mobile devices, which
resolutions typically lack the computational capacity to render excessively
complex and voluminous datasets.

While an increase in resolution logically correlates with
extended render times, the data reveals a fundamental disparity Acknowledgement
in computational behaviour between the two modelling
approaches. The parametric model (denoted as ’Param’) We extend our thanks to the ”Chˆateaux Rh´enans: Burgen am
exhibits a non-linear trajectory, particularly evident at the Oberrhein” Interreg VI Project (2023-2025) involving France,
highest resolution (7680×5120). In this configuration, the Germany, and Switzerland, coordinated by the European
computational cost does not scale linearly with the sample Collectivity of Alsace. We appreciate the opportunity to
count; rather, a sharp initial increase is observed, suggesting contribute to this innovative approach to digital heritage
a heavy overhead per ray-intersection. This can be attributed conservation.
to the rendering engine’s requirement to dynamically evaluate
complex geometry node trees and procedural texture functions References
for every sample. On the other hand, the model derived from
virtual photogrammetry (’High Res’) demonstrates a highly Agisoft Metashape, 2025. Agisoft Metashape.
linear and stable progression, regardless of output resolution.
The efficiency gap between the two methods is substantial. Banfi, F., 2017. BIM Orientation: Grades of Generation and
The baked geometry significantly attenuates the rendering Information for Different Type of Analysis and Management
load by converting complex procedural instructions into static Process. The International Archives of the Photogrammetry,
mesh data and pre-computed texture maps. Consequently, Remote Sensing and Spatial Information Sciences, XLII-2/W5,
the path-tracer performs efficient texture lookups rather 57–64.

This contribution has been peer-reviewed.
https://doi.org/10.5194/isprs-archives-XLVIII-2-W12-2026-447-2026 | © Author(s) 2026. CC BY 4.0 License. 453

<!-- p. 8 -->

The International Archives of the Photogrammetry, Remote Sensing and Spatial Information Sciences, Volume XLVIII-2/W12-2026
11th Intl. Workshop 3D-ARCH "3D Virtual Reconstruction and Visualization of Complex Architectures", 10–12 February 2026, Ancona, Italy

Bolognesi, C. M., Manfredi, V., 2024. Optimization of VR Rubinstein, J., 2025. [DC] Exploring virtual photogrammetry
Application in Texturing Cultural Heritage. The International techniques and applications for advancement of digital twin
Archives of the Photogrammetry, Remote Sensing and Spatial generation. IEEE Conference on Virtual Reality and 3D User
Information Sciences, XLVIII-2/W4-2024, 73–78. Interfaces Abstracts and Workshops (VRW), IEEE, Saint Malo,
France, 1550–1551.
Christenson, M., 2025. Parametric Analysis as a Tool for
Hypothesis Generation: A Case Study of the Federal Archive Sommer, E., Koehl, M., Grussenmeyer, P., 2025a. Comparative
Building in New York City. Infrastructures, 10(4). Study of Path Tracing Rendering Parameters and Visual
Quality in Blender. The International Archives of the
Cinquepalmi, F., Cumo, F., 2022. Using Digital Twin Models Photogrammetry, Remote Sensing and Spatial Information
(DTM) for Managing, Protecting and Restoring Historical
Sciences, XLVIII-M-9-2025, 1387–1394.
Buildings. Conservation Science in Cultural Heritage, 22(1),
425–445. Sommer, E., Koehl, M., Grussenmeyer, P., 2025b. Parametric
Modelling Techniques for Rhine Castle Models in Blender.
Di Donato, D., Morganti, R., Tosone, A., Abita, M., 2022.
Heritage, 8(1).
Procedural Modelling for HBIM of Italian Railways Iron
Bridges. The International Archives of the Photogrammetry, Tsiachta, A., Argyrou, P., Tsougas, I., Kladou, M., Ravanidis,
Remote Sensing and Spatial Information Sciences, P., Kaimaris, D., Georgiadis, C., Georgoula, O., Patias, P.,
XLVI-2/W1-2022, 207–214. 2024. Multi-Sensor Image and Range-Based Techniques for the
Geometric Documentation and the Photorealistic 3D ModelingEsmaeili, H., Thwaites, H., 2016. Virtual photogrammetry.
of Complex Architectural Monuments. Sensors, 24(9), 2671.22nd International Conference on Virtual System & Multimedia
(VSMM), IEEE, Kuala Lumpur, Malaysia, 1–6. Wang, Z., Bovik, A., Sheikh, H., Simoncelli, E., 2004.
Image Quality Assessment: From Error Visibility to StructuralFrommholz, D., 2019. A Synthetic 3d Scene for the Validation
Similarity. IEEE Transactions on Image Processing, 13(4),of Photogrammetric Algorithms. The International Archives of
600–612.the Photogrammetry, Remote Sensing and Spatial Information
Sciences, XLII-2/W13, 1221–1228.

Innocente, C., Nonis, F., Lo Faro, A., Ruggieri, R., Ulrich,
L., Vezzetti, E., 2024. A Metaverse Platform for Preserving
and Promoting Intangible Cultural Heritage. Applied Sciences,
14(8).

Koehl, M., Heitz, J.-E., Sommer, E., Fuchs, M., 2024.
Valorization of 3D/4D Models of Disappeared or Ruined
Heritage Sites in 3D Modeling Environments. The International
Archives of the Photogrammetry, Remote Sensing and Spatial
Information Sciences, XLVIII-2/W8-2024, 235–242.

Luhmann, T., Robson, S., Kyle, S., Boehm, J., 2023.
Close-Range Photogrammetry and 3D Imaging. De Gruyter,
Berlin, Boston.

Manfredi, V., Bolognesi, C. M., Fai, S., 2025. PIXEL VR:
Optimizing Photogrammetric Datasets for Standalone VR. The
International Archives of the Photogrammetry, Remote Sensing
and Spatial Information Sciences, XLVIII-M-9-2025, 973–980.

Moyano, J., Carre˜no, E., Nieto-Juli´an, J. E., Gil-Ariz´on, I.,
Bruno, S., 2022. Systematic Approach to Generate Historical
Building Information Modelling (HBIM) in Architectural
Restoration Project. Automation in Construction, 143, 104551.

Murphy, M., McGovern, E., Pavia, S., 2009. Historic Building
Information Modelling (HBIM). Structural Survey, 27(4),
311–327.

Niccolucci, F., Markhoff, B., Theodoridou, M., Felicetti, A.,
Hermon, S., 2023. The Heritage Digital Twin: A Bicycle Made
for Two. The Integration of Digital Methodologies into Cultural
Heritage Research. Open Research Europe, 3(64).

Parrinello, S., Pettineo, A., 2025. Databases and Information
Models for Semantic and Evolutionary Analysis in Fortified
Cultural Heritage. Heritage, 8(1).

Rocha, G., Mateus, L., Fern´andez, J., Ferreira, V., 2020.
A Scan-to-BIM Methodology Applied to Heritage Buildings.
Heritage, 3(1), 47–67.

This contribution has been peer-reviewed.
https://doi.org/10.5194/isprs-archives-XLVIII-2-W12-2026-447-2026 | © Author(s) 2026. CC BY 4.0 License. 454
