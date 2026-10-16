---
type: libro
title: "2017_Geometrical_processing_of_real_dat"
author: "Mateo Aires Llinares"
categoria: "Metodologías y técnicas de reconocimiento y evaluación"
paginas: 11
extraccion: "texto (OCR pendiente)"
fuente: "local:D:/UPV/MCPA/Asignaturas/Metodologías y técnicas de reconocimiento y evaluación/Documentación UPV/10. Otras publicaciones/2017_Geometrical_processing_of_real_dat.pdf"
convertido: 2026-10-16
---

# 2017_Geometrical_processing_of_real_dat

> Texto extraído de `Metodologías y técnicas de reconocimiento y evaluación\Documentación UPV\10. Otras publicaciones\2017_Geometrical_processing_of_real_dat.pdf` (11 páginas, texto (OCR pendiente)). El PDF original está en el disco D: (UPV\MCPA\Asignaturas); `<!-- p. N -->` marca el inicio de cada página.

<!-- p. 1 -->

6

<!-- p. 2 -->

DEFENSIVE ARCHITECTURE OF THE MEDITERRANEAN
XV TO XVIII CENTURIES
Vol. VI

<!-- p. 3 -->

FORTMED 2017

Colección Congresos UA

Los contenidos de esta publicación han sido evaluados por el Comité Científico que en ella se
relaciona y según el procedimiento de la ``revisión por pares´´.

© editor
Ángel Benigno González Avilés

© de los textos: los autores

© 2017, de la presente edición: Editorial Publicacions Universitat d’Alacant.
www.publicaciones.ua.es/

Imprime:

ISBN: 978-84-16724-76-5 (Vol.VI)

Depósito legal: A 494-2017

FORTMED – Modern Age Fortifications of the Mediterranean Coast, Alicante, October 26th, 27th, 28th
2017

<!-- p. 4 -->

Defensive Architecture of the Mediterranean. XV to XVIII centuries / Vol VI / González Avilés (Ed.)
© 2017 Editorial Publicacions Universitat d’Alacant

Geometrical processing of real data for Finite Element Analysis of
historical fortified structures
Sara Gonizzi Barsantia, Gabriele Guidia, Pablo Rodriguez Navarrob
aPolitecnico di Milano, Milan, Italy, (sara.gonizzi, gabriele.guidi)@polimi.it
b Universitat Politècnica de València, Valencia, Spain, rodriguez@upv.es

Abstract
The use of Finite Elements Analysis (FEA) for ancient structures and artefacts has recently shown great
potentialities. The typical workflow of such analysis involves the use of CAD 3D models made by
mathematical surfaces, representing the ideal shape of the object to be simulated. For Cultural Heritage
objects, altered by the time passed since their original creation, the representation with a schematic CAD
model may introduce an excessive level of approximation leading to wrong simulation results. The focus
of this paper is to present a new method, based on a wise use of retopology procedures, aiming at
generating the most accurate 3D representation of a real artefact/scenario from 3D models derived from
reality-based techniques, maintaining as much as possible the accuracy of the high-resolution polygonal
models in the solid ones while minimizing the number of nodes to a level compliant with FEA. This
allows to obtain FEA results that are closer to the actual mechanical behaviour of the analysed heritage
asset. Such methodology is here described and applied to the structural analysis of the Tower of the
Marenyet in Valencia (Spain).

Keywords: FEA, Structural Analysis, Retopology, Cultural Heritage

\1. Introduction
Conservation of Cultural Heritage is a key issue exterior surfaces, to a volumetric one, with nodes
and structural changes and damages can influence distributed both on the exteriors and the interiors
the structural behavior of Cultural Heritage of the volume, connected each other by
artefacts and buildings. In order to achieve elementary geometric cells. This workflow is
diagnostic studies to understand the level of appropriate in the mechanical field, where a
decay of Cultural Heritage and to select the physical element to be simulated is very close to
appropriate preservation methods and materials, a its ideal drawings within strict tolerances.
scientific base would be fundamental. The use of Conversely, when applied to 3D models of
Finite Elements Analysis (FEA) for modelling the Cultural Heritage (CH) objects or structures,
stress behavior of a structure, is largely used in often altered by the time passed since their
investigating its mechanical features. The typical original creation, the representation with a
workflow involves the use of CAD 3D models schematic CAD model may introduce an
made by Non Uniform B-SplineS (NURBS) excessive level of approximation leading to
surfaces, representing the ideal shape of the wrong simulation results. Nowadays, 3D
object to be simulated (Höllig, 2003). The major documentation of CH has been widely developed
FEA packages have meshing modules capable to through active sensors or passive approaches like
transform a NURBS model, made only of its photogrammetry, but the related 3D models,

377

<!-- p. 5 -->

representing the exterior surfaces of the objects, generating a volumetric mesh from the point
are not suitable for a direct use in FEA. The mesh cloud with no preliminary surface meshing.
has in fact to be converted from superficial to The first approach has been used for simulating
volumetric, and the density has to be reduced the behavior of the Trajan's Markets (Brune and
since the computational complexity of FEA Perucchio, 2012), and in many other applications
grows exponentially with the number of nodes (Erkal and Ozhan, 2014; Riveiro et al, 2011). In
representing the simulated object. The focus of some cases, the reconstructed mathematical
this paper is to present a method aiming at model was refined with the insertion of limited
analyzing a real artefact/scenario with Finite patches of reality-based superficial meshes
Elements Methods, using for this purpose a (Zvietcovich et al., 2014).
volumetric 3D representation of the scenario as The second approach has a range of slightly
close as possible to the reality, while maintaining different methods, such as bare simplification of
a vertex density compliant with the computational the triangular surface mesh before converting it in
complexity of FEA. This result is obtained by a volumetric one, that may give significant
properly deriving the volumetric representation deviations between the actual shape and the
from highly accurate digital reality-based models. simulated one. The simplified description of the
The approach here proposed is based on a wise shape in this case are discretized profiles giving a
use of retopology procedures, aiming at creating low-resolution representation of the interior and
a topology that is more favorable for the the exterior of the structure, from which produce
automatic NURBS conversion. The output of a volumetric model (Castellazzi et al., 2015).
such process results as close as possible to the real Finally, the last strategy does not even consider
shape, but also suitable to be transformed in the mesh, generating a volumetric approximation
reasonably complex volumetric 3D models of the shape from the raw 3D cloud of points
through standard mesh generators available in (Shapiro and Tsukanov, 1999).
FEM packages.
This paper validates such approach using as a test 1.2. Retopology of reality-based meshes
object the tower of Marenyet (Valencia), Topology is referred to the study of geometricalacquiring a high resolution 3D model of it. The properties and spatial relations between theoriginal data are then processed with the novel polygons of a mesh, independently by continuousapproach proposed, analyzing different variation of shape and size of them. Any abruptvolumetric meshing densities, and proposing a change in this relationship is considered aproper FEA validation process. Such analysis can topological error, like for example the flip of thehelp in finding possible structural threats and normal in two adjacent polygons. Retopology is apotential causes for future problems, providing key 3D process that has been developed forinformation for a more accurate conservation of optimizing the use of polygons in describing 3Dthe structure. shapes in Computer Graphics (CG) animations,
where the rendering time is directly related to the
1.1. State of the art number of polygons of the represented 3D
Few preliminary experiments have been done on geometry. Retopology is the creation of a new
real CH structures digitized with active or passive topology for a 3D model. In practical
methods, whose models have been processed for applications, like computer animation, it is
simulating stress behavior and predicting possible obtained by laying down a low-polygon mesh
damages for improve their conservation. By over top of the high-density model for
analyzing the previous works, different simplifying it and in the meantime start a brand
approaches have been followed: a) redrawing new polygonal organization, possibly created in
with a CAD modeler a new surface model order to follow the main geometrical feature of
following the superficial mesh originated by the the object described by the 3D model. The
acquired 3D cloud; b) using directly the triangular retopologized mesh is typically based on
mesh as starting point for volumetric models; c) quadrangular element (quads) instead of

378

<!-- p. 6 -->

triangles. In this way, animators can rework such NURBS based 3D model is in general the
models with shapes close enough to the original composition of a certain number of NURBS
but without the huge number of polygons typical patches, connected such to maintain a positional
of models originated by a 3D digitization (G0), tangential (G1), or curvature (G2)
pipeline. continuity (Farin et al., 2002).
The volumetric meshing module embedded in The conversion of a polygonal model in a
any FEA package is generally able to process NURBS model is available on some CAD
CAD models, whose standard output is a set of packages as automatic process, that in general
connected NURBS. The idea behind this paper is tend to produce a higher number of small patches
that a more organized topology can be favorable when the original mesh is topologically
for converting a polygonal mesh in a NURBS unorganized. As a result, by rearranging the
model, while maintaining a better coherence with initial topology of the mesh, a preliminary
the digitized artefact. This can be useful when condition for minimizing the number of NURBS
dealing with reality-based models of Cultural patches of the converted model is set. And this
Heritage, typically characterized by complex represents a better starting point for the
geometries, gaps, missing parts or jagged profiles volumetric mesher embedded in any standard
that are the results of the action of time, FEM package.
atmospheric agents or human behaviors. Such
features have to be maintained during the process 2. Historical overview of the analyzed
if the goal is to provide a structural analysis as structure
close as possible to the real scenario.
During the 16th century, a fortified architecture
1.3. NURBS Conversion was born in the Valencian coast of Spain,
produced mainly by the confluence of a particular
In mathematics a Spline is a curve defined by social and political context, and aspects of
segments of polynomial functions defined by a technological development. In 1557, Philip II
certain number of interpolating points or control became King and began an ambitious project that
nodes. The polynomial degree associated to a had already traced by Bernardino de Cardenas,
certain number n of control points, is in general Duke of Maqueda, for his father, who wanted to
n-1, so that a spline passing from 2 points will be build a network of watchtowers and defensive
a polynomial of first degree (a line), a spline structures for the coast. These constructions had
passing from three points will be a quadratic the mission of alerting neighboring towns of the
polynomial (a conic), a spline passing from four frequent pirate attacks, and in addition to be the
points will be a cubic polynomial, and so forth. first line of defense. The Spanish king decided to
B-Splines, the short for Base Splines, are spline entrust the ambitious network of watchtowers and
curves with specific mathematical properties defense of the east coast to one engineer:
(minimal support). So, any spline function of a Giovanni Battista Antonelli "il Vecchio", who
given degree can be expressed as a linear designed and constructed the buildings during the
combination of B-splines of that degree. NURBS sixteenth and seventeenth centuries. Nowadays,
curves are a generalization of this formulation, all these towers form an important architectural
represented in form of a ratio between two heritage that has lost its main feature, the unit.
polynomial expressions, that make them They were built as part of a unique defense
“rational”. Like B-splines, they are defined by project, but now we find them abandoned both
their order and a set of control points, but unlike physically and in terms of research effort for its
simple B-splines, each control point has a weight. value. The Marenyet tower (Fig.1) is a circular
When all weights are equal to 1, a NURBS is defensive tower erected in the right margin of the
simply a B-spline. A NURBS surface (patch) is Júcar, in the Spanish locality of Cullera. This
obtained as the tensor product of two NURBS tower is an archetypal defense tower on the coast
curves, originating a quadrangular patch. A of the Kingdom of Valencia in the 16th century.

379

<!-- p. 7 -->

It was precisely in this town, Cullera, where in Cyclone V9.1. CloudCompare and Polyworks
May 1550, one of the bloodiest events of the (Rodriguez-Navarro et al. 2015). The final mesh,
Turkish pirates took place. This fact was originated by an integration of the two datasets,
determinant for the construction of this tower in was approximately 1 mil polygons and represents
1577, under the orders of the viceroy of Valencia, both the interiors and the exteriors of the
Vespasiano Gonzaga, under the kingdom of structure, as shown in fig. 1b.
Philip II. The survey of the tower was made in the frame of
the R&D project “Surveillance and Defense
Towers of the Valencian Coast. Metadata
generation and 3D models for interpretation and
effective enhancement”. The project is funded by
the National Program for Fostering Excellence in
Scientific and Technical Research, National Sub-
Program for Knowledge Generation, Ministry of
Economy and Competitiveness (Government of
Spain).

3.2. Decimation and NURBS creation

The decimation of the model was performed
using retopology. A previous work on small
a b mono-material objects have shown that a re-
topologized mesh surface is a more suitable
Fig. 1 - The Marenyet tower: a) image from the starting point for generating the volumetric meshdrone dataset; b) mesh originated by the acquired used during the FEA process (Gonizzi and Guidi,data, sectioned with an axial plane.
2017). This is due to the better elements
organization on the decimated mesh, especially3. Experimental results
when the number of the final polygons is much
3.1. Acquisition of the high-resolution model lower than the number of the elements in the high-
resolution mesh. In this paper the same concepts
The Marenyet tower was surveyed with both are applied to a big structure made of composite
close range and UAV photogrammetry and with material. Several model have been created
a laser scanner. The camera used was the Sony starting from the lower number allowed by the
RX100 II, with a 20.2 MP resolution, a 13.2 x 8.8 process and doubling the number of vertexes at
mm CMOS sensor and Zeiss F1.8 lens with 10.4- each step, for a total of 4 steps. Considering that
37.1 mm focal length (equivalent to 28-100mm the high-resolution mesh of the tower has
on a full-frame camera). The technical approximately 1 mil vertexes (Fig. 1b), the
specification of the shots are: ISO 100; aperture F retopologized model with the lower number
6.3; image size 5472x3648 pixel. In the survey of possible, has 20K vertexes. The subsequent
the Marenyet Tower a quadcopter manufactured models were doubled, obtaining 40K, 80K and
was used, handled by a single person acting both 160K vertexes respectively (Fig. 2a-d). The
as pilot and camera operator. The model was retopology parameters were set o have the
processed with Agisoft Photoscan associating the maximum flexibility in the polygons sizing. This
two different models provided by the UAV and originated retopologized models as close as
terrestrial images. The tower was also surveyed possible to the high-resolution one. The mean and
with a ZF 5006h Zoller+Fröhlich phase-shift the standard deviation among the different
scanner, with a maximum effective distance of 79 models are summarized in Table 1.
m and a measuring speed of more than a million
points/sec. The software chosen to manage the
point clouds and the mesh have been Leica

380

<!-- p. 8 -->

process. Such model was then volumetrically
sampled for the following FEA.

\3. Finite Element Analysis
The description of the laws of physics for space-
and time-dependent problems are usuallya b
expressed in terms of partial differential
equations (PDEs). For the vast majority of
geometries and problems, these PDEs cannot be
solved with analytical methods. In place of them,
an approximation of the equations can be
constructed by discretizing a complex physical
c d problem on many smaller and far simpler
Fig.2 - The four retopologized meshes of the problems. Such discretization approximates the
original triangular mesh shown in fig.1b: a) 20K; PDEs with numerical model equations, which can
b) 40K; c) 80K; d) 160K. be solved using numerical methods. The solution
to the numerical model equations are, in turn, anDespite the strong simplification involved in the approximation of the real solution to the PDEs.four analyzed models, ranging from 1:6,25 (160k The finite element method (FEM) is used tovertexes) to 1:50 (20 k vertexes), the numerical compute such approximations. Typical areas ofresults, obtained by comparing the simplified interest include structural analysis, heat transfer,models is with respect of the high resolution one fluid flow, mass transport and electromagnetics.with the CloudCompare open source software, In particular, in mechanics’ problems, if a force isgave very encouraging results. applied on a solid, once its physical parameters
20K 40K 80K 160K are known, the values of stress, displacements
and strain at each material point can be calculated Mean 0.32 0.13 0.02 0.07
by means of Finite Elements Analysis (FEA). STD Dev. 3.2 1.3 0.3 0.3
The general process of FEA works on the
Table 1 - Comparison (mm) among the high-res following steps: a) a NURBS model is imported
models and the retopologized ones. in a FEA package and meshed as solid model,
As clearly shown by the numbers in table 1, performing therefore a discretization of the whole
thanks to the relatively regular shape of the tower, shape in small volumetric subdomains made by
even with the strongest simplification the tetrahedrons or hexahedrons, connected each
maximum value of the mean geometrical other through their sides and vertexes. On each
deviation is 0,32 mm, that for a structure taller elementary cell, a certain number of physical
than 16 m can be considered negligible. In nodes is considered, as shown in fig. 3; b) a force
addition, the corresponding standard deviation of and a boundary condition has to be set for
error, is 3.2 mm, a number of the same order of initializing the state of each involved node; c) on
the measurement uncertainty of the laser scanner the above mentioned nodes the software takes
used for 3D capturing this tower. For this reason, into account the physics of the problem applying
the 20k vertexes version was chosen as the one the proper set of equations, calculating the local
suitable for the structural analysis. stress and deformations and taking into account
The creation of the NURBS was performed using the mutual interaction between adjacent nodes.
the software Rhinoceros that permits an The FEA package chosen for the experiments
automatic transformation of the mesh in a closed reported in this paper is ANSYS, because of its
surface model, composed of many patches. The great flexibility in handling solid models with a
NURBS were then cut on the bottom in order to high number of elements, like those associated
have a flat surface on which imposing the with complex structures of historical buildings.
boundary conditions for the Finite Element

381

<!-- p. 9 -->

In order to decide the reliability of the FEA
results, some additional analyses were made, not
published in the above mentioned paper. What
was determined are basically three parameters: a)
what is the optimal retopology parametrization;
b) how to choose the relative sizing of the
simplified surface mesh with respect of the
original one for maintaining enough details
a b suitable for analyzing its geometry; c) which is
the best sizing of the elementary cell in the
volumetric mesh. Due to the large difference in
size between this specimen and the architectural
structure we are analyzing in this paper, all the
evaluations were made in relative terms.
The specimen’s original mesh, whose resolution
c d was high enough to represent all the geometric
Fig. 3 – Elementary cells typically used in FEA: details with the spatial resolution captured by the
a) tetrahedral, 4 nodes; b) tetrahedral 10 nodes; c) 3D device (0.2 mm), resulted to be 350k vertexes
hexahedral 8 nodes; d) hexahedral 20 nodes. and was simplified with different retopology
strategy. The best of them resulted to be the one
with a dynamic adaptation of the polygon size to
3.1. Test on static simulation the size of the corresponding geometric details.
This same strategy was applied for simplifying
The test performed was a simple static-structural the tower model.
test. In this case, a crucial choice is the type of The test made, whose results are reported in table
elementary cell among those shown in figure 3 2, involved the analysis on the whole structure
and its sizing that has been shown to be critical in with FEA with the extraction of the peak stress in
a previous study of the same authors (Gonizzi and correspondence of the thinner section of the
Guidi, 2017). specimen (Von Mises).
In that case the work involved the analysis of a
148 mm long small metallic specimen (fig. 4a),
whose shape was simple enough for analyzing it 1k 2k 4k 8k 16k 32k 64k
in advance with analytical methods, determining 0,1 37 31 25 35 33 25 20
the peak stress in correspondence of the thinner 0,5 18 18 11 9 8 8 3
section of it, in the center of the object.
1 7 5 2 0 1 1 3
1,5 8 5 0 -1 1 1 3
2 7 -2 2 0 1 1 3
a 2,5 7 -2 -1 -1 1 1 3

Table 2 – Deviation (%) of the maximum stress
calculated with FEA against the value calculated
analytically on the lab specimen for different
sizes of the simplified surface mesh (columns) b
Fig. 4 – Preliminary experiments for determining and different sizes in mm of the tetrahedral cell in
the proper volumetric sampling of geometry: a) the volumetric mesh (rows). The yellow cells
image of a lab specimen; b) mapping of stress corresponds to a deviation within 3%.
obtained with FEA in the chosen conditions Instead of the absolute values, table 2 reports the(surface simplified with 4k vertexes, volume
percentage of deviation with respect of the valuemeshed with 1mm tetrahedra).

382

<!-- p. 10 -->

calculated analytically, for different sizes of the a non-ductile material like the stone and lime
simplified surface mesh and different sizes of the composition used for building the tower. In table
tetrahedral cell in the volumetric mesh. Such 3 such values have been reported.
percentage was considered acceptable within 3%,
corresponding to the yellow cells in table 2. Tetrahedron side Maximum Principal
(mm) (MPa)
As shown here, the most simplified surface mesh 80 1.51
that gave results within the threshold for most of 100 1.58the tetrahedral volumes, was the one made by 4k
120 1.17vertexes, that compared with the original mesh
140 1.04involves an approximate vertex ratio of 1:90. In
160 1.16that condition the minimal polygon size is 1.06
180 0.95mm. The minimal tetrahedral volume giving a
200 0.90result within the threshold is 1mm, similar to the
surface mesh polygon size (1:1). 220 1.14
These ratios have been considered when choosing 240 1.00
the tetrahedral volume for analyzing the Table 3 - Maximum Principal (MP) in Mega
Merenyet tower 3D model. The analysis was Pascal, obtained by FEA on the 20k vertexes
carried out on the NURBS derived from the 20k retopologized models with increasing element
vertexes retopologized model shown in fig. 2a. size.
The volumetric meshing was based on 10-nodes
tetrahedral elements like those shown in fig. 3b.
Different cell sizes around a starting point chosen
after the specimen tests were used, starting from
a maximum value of 240 mm and decreasing it
with 20mm steps. This procedure was followed in
order to check for which element size the result
of the analysis goes to convergence remaining
approximately the same while the cell size is
progressively decreased, before an abrupt jump to
higher values that typically happens when the cell
size becomes too small. The cell size immediately
before this point is that usually considered as the Fig.5 – Trend of the FEA results listed in table 3
most reliable. As clearly visible in Fig. 5, except the result
This convergence is important especially dealing obtained with a meshing size of 80 and 100 mm,
with models of objects whose structural behavior the others meshing parameters gave similar
cannot be calculated with analytical approach. results. In this conditions the most reliable choice
The static-structural analysis was performed for the volumetric meshing seems to be a 120 mm
setting the parameter for a composition of lime side tetrahedron. This, as in the previous
and stone, with density 2.739 kg/m3; Young simulations, appears to be of the same order than
Modulus 900MPa; Poisson Ratio 0.23; 10-nodes the minimal polygon side in the 20K
tetrahedral cell; sizing from 80 to 240 mm; retopologized mesh (130mm).
standard gravity force on -Y axis; fixed support
as boundary conditions. The results of the Finite 4. Conclusion
Element Analysis are very complex involving the
The use of retopology showed great performancesstress estimation on every node of the structure.
in the process and permitted to directly use aA simple way for comparing different run of the
reality-based model for Finite Element Analysis.same simulation with different cell sizing, is
considering a critical value like the Maximum The use of the 3D measurement uncertainty as
Principal stress, that is used as synthetic index for simplification criterion, allowed to dramatically

383

<!-- p. 11 -->

reduce the mesh size. The resulting model was 50
times smaller of the original one, made of
polygons whose size is adapted to the shape of the
tower, with a minimum of 130 mm.
The convergence analysis permitted then to
understand the best solution for the volumetric
sampling, giving the optimal result at 120mm, not
much different from the size of the smaller
polygons in the retopologized surface mesh. This
result was coherent with previous experiments
made on a small lab specimen.
Thanks to this mesh preprocessing method, we
can state that FEA analysis can be easily extended
to reality-based models of complex CH structures
like the Marenyet tower, paving the way for
gathering important structural information from
computer simulations, aiming at improving CH Fig.6 – The results of FEA on the 20Kpreservation. retopologized model.

References
Brune, P., Perucchio, R. (2012). Roman Concrete Vaulting in the Great Hall of Trajan’s Markets: A
Structural Evaluation. J. Archit. Eng. 18, 332–340. doi:10.1061/(ASCE)AE.1943-5568.0000086
Castellazzi, G., Altri, A.M.D., Bitelli, G., Selvaggi, I., Lambertini, A. (2015). From Laser Scanning to
Finite Element Analysis of Complex Buildings by Using a Semi-Automatic Procedure. Sensors 15,
18360–18380. doi:10.3390/s150818360
Erkal, A., Ozhan, H.O. (2014). Value and vulnerability assessment of a historic tomb for conservation.
Sci. World J. 2014, Article ID 357679. doi:10.1155/2014/357679
Farin, G.E., Hoschek, J., Kim, M.-S., 2002. Handbook of Computer Aided Geometric Design, Elsevier.
Freytag, M., Shapiro, V., Tsukanov, I. (2011). Finite element analysis in situ. Finite Elem. Anal. Des. 47,
957–972. doi:10.1016/j.finel.2011.03.001
Gonizzi Barsanti, S. and Guidi, G. (2017). A Geometric Processing Workflow for Transforming Reality-
Based 3D Models in Volumetric Meshes Suitable for FEA, Int. Arch. Photogramm. Remote Sens.
Spatial Inf. Sci., XLII-2/W3, 331-338, doi:10.5194/isprs-archives-XLII-2-W3-331-2017, 2017.
Guidi, G., Angheleddu, D. (2016). Displacement Mapping As a Metric Tool for Optimizing Mesh Models
Originated by 3D Digitization. J. Comput. Cult. Herit. 9, 9:1--9:23. doi:10.1145/2843947
Höllig, K. (2003). Finite Element Methods with B-Splines. Society for Industrial and Applied
Mathematics, Stuttgart, Germany. doi:10.1137/1.9780898717532
Riveiro, B., Caamaño, J.C., Arias, P., Sanz, E. (2011). Photogrammetric 3D modelling and mechanical
analysis of masonry arches: An approach based on a discontinuous model of voussoirs. Autom.
Constr. 20, 380–388. doi:10.1016/j.autcon.2010.11.008
Rodríguez-Navarro, P., Verdiani, T., Veridani, G., PIqueras, G. (2015). Comprehensive Methodology for
Documenting the Defense Towers of the Valencian Coast (Spain) in Defensive Architecture of the
Mediterranean. XV to XVIII Centuries, Vol 1, Editorial Universitat Politècnica de València, Valencia,
Spain, 2015, pp. 321-328. ISBN 978-84-9048-425-8
Shapiro, V., Tsukanov, I. (1999). Meshfree simulation of deforming domains. CAD Comput. Aided Des.
31, 459–471. doi:10.1016/S0010-4485(99)00043-3
Zvietcovich, F., Castaneda, B., Perucchio, R. (2014). 3D solid model updating of complex ancient
monumental structures based on local geometrical meshes. Digit. Appl. Archaeol. Cult. Herit. 2, 12–
\27. doi:10.1016/j.daach.2015.02.001

384
