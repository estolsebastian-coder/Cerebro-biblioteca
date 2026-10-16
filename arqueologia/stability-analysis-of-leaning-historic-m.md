---
type: libro
title: "Stability_analysis_of_leaning_historic_m"
author: ""
categoria: "Arqueología"
paginas: 30
extraccion: "texto"
fuente: "local:E:/DISCIPLINAS, TEXTOS Y MAPAS/Biblioteca digital/Arqueología/Stability_analysis_of_leaning_historic_m.pdf"
convertido: 2026-10-12
---

# Stability_analysis_of_leaning_historic_m

> Texto extraído de `Arqueología/Stability_analysis_of_leaning_historic_m.pdf` (30 páginas, texto). El PDF original está en el disco E: (DISCIPLINAS, TEXTOS Y MAPAS\Biblioteca digital); `<!-- p. N -->` marca el inicio de cada página.

<!-- p. 1 -->

D'Altri AM, Milani G, de Miranda S, Castellazzi G, Sarhosis V. Stability analysis
of leaning historic masonry structures. Automation in Construction 2018, 92,
199-213.

Copyright:

© 2018. This manuscript version is made available under the CC-BY-NC-ND 4.0 license

DOI link to article:

https://doi.org/10.1016/j.autcon.2018.04.003

Date deposited:

30/04/2018

Embargo release date:

25 April 2019

This work is licensed under a
Creative Commons Attribution-NonCommercial-NoDerivatives 4.0 International licence

Newcastle University ePrints - eprint.ncl.ac.uk

<!-- p. 2 -->

Stability Analysis of Leaning Historic Masonry Structures

Antonio Maria D’Altri1*, Gabriele Milani2, Stefano de Miranda1, Giovanni Castellazzi1, Vasilis Sarhosis3

1 Department of Civil, Chemical, Environmental, and Materials Engineering (DICAM), University of Bologna, Viale
del Risorgimento 2, Bologna 40136, Italy

2 Department of Architecture, Built Environment and Construction Engineering (A.B.C.), Politecnico di Milano, Piazza
Leonardo da Vinci 32, Milan 20133, Italy

3 School of Civil Engineering and Geosciences, Newcastle University, Newcastle upon Tyne NE1 7RU, UK

\*corresponding author: antoniomaria.daltri2@unibo.it

ABSTRACT

This paper introduces an automatic, powerful and easy to use procedure for undertaking stability analyses of leaning
historic masonry structures, based on an upper bound finite element limit analysis (FELA) approach. The procedure
proposed here consists of a comprehensive workflow which involves the automatic point cloud manipulation, the 3D
mesh generation of the actual geometry for structural purposes (e.g. FE mesh), and a two-step FELA that reduces
drastically optimization variables assuming only active few elements inside a restricted processing zone. To generalize
the Heyman’s intuition to complex real geometries, the use of a 3D upper bound FELA with a recursive kernel of variables
reduction becomes necessary for a precise evaluation of the limit inclination that makes the structure collapse under
gravity loads. This outcome permits to estimate the structural health condition of a historic structure by comparing the
critical inclination angle with the actual one. To demonstrate the effectiveness of the automated procedure, the southwest
leaning tower of the Caerphilly castle (Wales, UK) is investigated and failure mechanisms with collapse inclination angles
are evaluated through FELA. The proposed procedure presents a high degree of automation at each operational level and,
hence, could be effectively used to assess the stability of historic structures at a national scale and provide useful
information to asset owners to classify the structural health condition of leaning historic masonry structures in their care.

Keywords: Leaning tower; Limit analysis; Point cloud; Mesh generation; Masonry; Actual geometry

1 Introduction

Leaning historic masonry structures are fascinating to observe. Perhaps the most famous examples include the
Pisa [1, 2] and the Ghirlandina towers [3]. The reason why historic masonry structures lean is a complex area
of study and have stimulated the interest of the scientific community for over a century [4, 5, 6, 7]. Due to their
narrow foundations, tall and slender historic masonry structures such as towers, whose height is much greater
than their width, are generally more prone to lean. Two major reasons why masonry towers tilt are: (a) lack of
foundation strength; and (b) lack of foundation stiffness aggravated by progressive soil creep phenomena [4].
Several advanced soil-structure interaction models have been developed to study these phenomena [3].
However, such models require the setting of a numerous amount of mechanical parameters; most of them
correlated with in-depth in-situ soil tests. Furthermore, they do not allow for a rapid check on the structural
condition of the structure.

Heyman [8] was probably the first to study analytically the safety of leaning towers by assuming masonry as
a rigid material unable to withstand tensile stresses. Such simplification allowed deriving a quite simple
differential equation describing the crack curve delimiting the failure mechanism and providing very useful
hints on the limit inclination angle associated with the collapse of the structure. However, the hypothesis of
rectangular full or thin-walled sections and the absence of any irregularity along the height represent a
remarkable limitation of the approach, since in practice it is not realistic. Vertical walls of towers vary

1

<!-- p. 3 -->

considerably in thickness and they often present irregular openings [1]. Furthermore, historic towers, or other
height-prevalent historic structures (e.g. walls in churches, curtain-defensive walls etc.), frequently stand in a
ruined condition, and have been subjected to unforeseen load events (e.g. bombing, successive demolitions,
sabotages, raids etc.) over the centuries [9]. Often, such structures suffered alternations and today, only a few
portions of the original structure remain standing. Consequently, the geometry of these structures is generally
extremely complex and irregular (see for instance [6]). Their complex geometries suggest to consider advanced
methods of analysis where the actual 3D geometry of the structure is accounted for in the calculations [10].

One of the first challenging tasks that appears when dealing with the numerical modelling of this kind of
structures lasts in acquiring their 3D geometric features. The use of automated surveying techniques, such as
terrestrial laser scanning [11] and close-range photogrammetry [12] which produce dense point clouds, appears
particularly suitable for obtaining the geometry of historic structures [13, 14, 15]. From such studies, it is
evident that the use of terrestrial laser scanning and close-range photogrammetry surveying techniques could
result in accurate representation of the geometry of a structure in a relatively reduced cost [16, 17, 18, 19].
Documentation for supporting restoration works as well as monitoring of historic structures are common
motivations for the use of these surveying techniques on structures of architectural heritage [20, 21, 22, 23].

Nevertheless, the exploitability of laser scanning and photogrammetric surveys outputs, i.e. point clouds, for
structural analysis of historic building is still challenging. A significant contribution to this field is proposed
in [24], where an attempt to accurately capture the geometry of a structure by automatic reconstruction is
presented. Moreover, in [25], a point-based voxelization method for automatic transformation of point cloud
data into solid models for computational modelling was proposed. The approach involves the construction of
a triangular irregular network (TIN) mesh by means of a voxel grid bounding the cloud region. However, such
approach is limited to building façades and it does not capture the entire geometrical domain of the structure.

Dealing with actual buildings, two main difficulties arise: (i) the automatic filling of very long vacancies (roof
structures for instance), and (ii) reduction of the whole model in a more simplified and compressed form. To
overcome these issues, a semi-automatic procedure (called CLOUD2FEM) to transform three-dimensional
point clouds of complex objects into a three-dimensional finite element model has been presented in [26]. The
procedure conceives of the point cloud as a stacking of point sections and aims at solving the problems
connected to the generation of finite element models of these complex structures by constructing a fine
discretized geometry with a reduced amount of time and outputs ready to be used for structural analysis
problems [27]. A recent application of this procedure to a full-scale medieval fortress and its subsequent
seismic assessment by means of nonlinear static analysis is reported in [28].

Once the mesh is available, it can be used within several computational tools for the structural analysis of
historic masonry buildings. Particularly, these such approaches are usually based on: a) the finite element
method (FEM) [29, 30, 31, 32, 33, 28, 34, 35]; b) the discrete element method (DEM) [36, 37]; and c) limit
analysis [38, 39]. Interesting comparisons of computational techniques are provided in [40, 41, 42].

Another interesting issue is to determine the maximum inclination angle that leads to the collapse of a tower
due to the loss of stability under the application of gravity loads. Concerning a no-tension material with
rectangular cross section, Heyman [8] was able to analytically determine the collapse inclination angle and the
corresponding crack pattern shape. Unfortunately, an analytical approach for real irregular geometries is hardly
applicable, and an automatic procedure is needed. To deal with such key issue is one of the two aims of the
present paper.

Firstly, a simplified and rapid procedure for the automatic transformation of point clouds (surveyed on historic
structures) to 3D FE meshes, passing from the concept of watertight mesh, is proposed. The accuracy of the
geometry of the mesh generated appears suitable for structural purposes. Secondly, following the Heyman’s
work [8], the use of a two-step 3D upper bound finite element limit analysis (FELA) on the generated mesh is
conducted and to evaluate the critical condition (i.e. maximum inclination capacity) of a leaning historic
masonry structure is evaluated.

2

<!-- p. 4 -->

The procedure is indeed an upper bound limit analysis with FE discretization obtained by means of tetrahedron
rigid elements and rigid-perfectly plastic interfaces exhibiting frictional behaviour and very low cohesion (i.e.
mimicking a quasi no-tension material with friction).

Considering that FE meshes obtained from detailed laser scanner surveys would be constituted by hundreds of
thousands of elements and interfaces, the limit analysis problems derived would be characterized by millions
of variables, i.e. in practice impossible to solve even with super-computers. An alternative to parallelization is
proposed for the first time here, which is essentially a master-slave approach conceived with the aim of
reducing drastically the total number of optimization variables. The procedure is based on the hypothesis that
the tower collapses for the plasticization of few elements located in a limited processing zone, which is a-priori
established in the first step. Elements with centroids inside the processing zone are assumed potentially active.
The rest of the mesh is excluded from computations and it is treated as a single rigid body characterized by six
degrees of freedom (i.e. three centroid velocities and three rotation rates). The solution of the linear
programming problem found in the first step provides a more accurate estimation of the potential interfaces
undergoing plasticization. In the second step, the processing zone is further reduced to those elements whose
interfaces exhibit meaningful inelastic deformation rates plus few contiguous ones, to further drop-down the
optimization variables. Conversely, the failure surface linearization on the active interfaces is refined to obtain
more accurate estimates of the collapse multiplier. The master-slave kernel is then coupled with a sequential
linear programming algorithm to deal with the linearization of the normalization condition equation, which
results nonlinear due to the assumption of the inclination angle at failure as collapse multiplier.

The outcome obtained with the limit analysis permits to practically estimate the structural health condition of
a leaning historic structure, e.g. by comparing the maximum critical inclination angle with against the actual
one. Since the computational approach proposed herein presents a high degree of automation at each
operational level (i.e. survey, point cloud manipulation, mesh generation, numerical analysis), its usage could
be addressed to the stability analysis of historic structures at a national scale. In particular, this approach could
be very beneficial for asset managers, which want to classify the structural condition of leaning historic assets
in their care and devise action plans for their survival.

In this research, the southwest leaning ruined masonry tower of the Caerphilly castle (Wales, UK) is employed
as a case study to demonstrate the effectiveness of the proposed approach. The paper is organized as follows.
Section 2 briefly presents the case study. Section 3 describes the automatic procedure for the stability analysis
of leaning historic structures. Section 4 reports the analyses results and their discussion. Finally, Section 5
highlights the main conclusions of this research work.

2 The leaning tower of Caerphilly castle, UK

In this section, a brief description of the case study related to the southwest leaning tower of Caerphilly castle,
used to test the effectiveness of the proposed approach is reported. The case study is merely used to
demonstrate the effectiveness of the proposed automatic procedure for assessing the structural stability of
leaning historic masonry structures.

Caerphilly castle is a medieval fortification in Caerphilly, South Wales, UK. The castle was constructed by
Gilbert de Clare in the 13th century [43] and it is the second largest in the UK. Fig. 1Fig. 1 shows the southwest
leaning ruined tower of the Caerphilly castle. The tower has been in a ruined and leaning condition for several
centuries [8, 44].

3

<!-- p. 5 -->

a b c
Fig. 1 – Southwest tower of Caerphilly castle: a) historic drawing (A.D. 1773) and b,c) photos of the tower in its actual
condition.

The tower is approximately 17 m tall. It used to have a circular ground plant of approximately 9 m in diameter.
Today, the inclination of the tower is approximately 10 degrees. For the sake of comparison, the campanile of
Pisa is 55.86 m tall and leans at an angle of 5.5 degrees. The southwest tower is made of stone masonry with
a fully irregular texture. No information is available about masonry material properties, soil stratigraphy and
foundations. However, medieval fortified structures were generally characterized by particularly shallow
foundations [9]. According to Renn [43], the deterioration subsequent leaning of the tower was probably the
result of subsidence caused by dewatering in the 18th century, as there is no evidence of deliberate destruction
having been ordered.

In 2014, a detailed survey of the southwest tower commissioned to document its health condition [44]. A total
of 27 scans were surveyed using a FARO focus 3D X130 terrestrial laser scanner. The inclinometer, altimeter,
compass, clear contour and clear sky were also activated and far distance deactivated. A series of scans have
been taken from points on the ground around the base of the tower. During the scanning, challenges were
mainly due to scaffolded areas around the tower and the presence of tourists. The complexity of the geometry
also proved challenging in the placement of targets. Twelve spherical targets used to locate the scans. The
resulting points’ cloud is shown in Fig. 3Fig. 3a.

3 The procedure

In this section, the automatic procedure for the stability analysis of leaning historic structures is described. It
comprises the automatic FE mesh generation starting from point cloud, the 3D limit analysis model description
and its utilization for the stability analysis of masonry structures. The case study presented in the previous
section is used to explicitly show the main steps of the procedure.

3.1 FE mesh generation

In the following, a simple approach for processing of point clouds is suggested for the automatic transformation
of point clouds (surveyed on historic structures) to 3D FE meshes, following the concept of watertight mesh.
Watertight means that the mesh on all of the surfaces is complete, so that the volume is fully enclosed. This
approach appears appealing for historic ruined structures, which are generally characterized by the absence of
inner spaces, furniture, doors and window frames etc. The proposed mesh generation approach treats historical
structures similar to 3D objects such as stone sculptures, building ornamental components [45], etc and follows
an akin concept of digital reproduction of 3D objects from 3D scanning to 3D printing [45]. However, in this
instance, instead of using the mesh to perform 3D printing, its usage is aimed to for structural analysis purposes
(i.e. FE mesh made of 3D continuum elements).

4

<!-- p. 6 -->

The proposed procedure requires a point cloud of the historic structure under study. The point cloud could be
the output of either terrestrial laser scanning or close-range photogrammetry. These survey techniques generate
dense clouds of 3D points, generally characterized by several millions of points for full-scale buildings.

Often, a few preliminary and standardized operations on the point cloud dataset may be required to facilitate
the subsequent operations. Firstly, a specific algorithm [46] is used to populate a new dataset of points with a
sampling generated according to a Poisson-disk distribution. The resulting reduced point cloud is characterized
by a regular spatial sampling, which can be chosen depending on the level of detail desired for the case at hand.
Dealing with historic structures, a point cloud density between 10,000 and 40,000 pts/m2 results a good
compromise between the manageability of the dataset and the accuracy in the representation of the geometry
for structural purposes [26]. Indeed, millimetric details are generally negligible to analyse the structural
behaviour of historic constructions. Successively, the point cloud has to be cleaned mainly by removing all
neighbour points, which are not relevant to the structure. Although this operation is manual, it is easy to
implement and substantially fast.

Afterward, a TIN mesh is generated based on the point cloud (in the condition after sampling and cleaning).
The TIN mesh is created by linking triplets of nodes to form non-overlapped triangles [47]. Ideally, if every
portion of the object’s surface is meticulously surveyed, this mesh could be already watertight. However, this
never occurs for large-scale and complex structures since their surfaces are continuous with the terrain.
Furthermore, few parts of the object’s surface are commonly missing, due to access difficulties during the
survey.

Since the aim is to obtain a watertight mesh, further processing of the data is necessary. Thus, the Poisson
surface reconstruction [48] can be adopted. Poisson surface reconstruction is a well-known computer graphics
technique for creating watertight surfaces from oriented point samples acquired with 3D range scanners. This
algorithm expresses surface reconstruction as the solution to a Poisson equation. Therefore, Poisson
reconstruction considers all the data at once, creating very smooth surfaces that robustly approximate noisy
data [48], suffering, however, from a tendency to over-smooth the data. All these operations are basically
common and standardized, and they can be conducted by means of any 3D mesh processing software.

Once the watertight mesh has been obtained, it can be directly exploited for setting up the 3D FE mesh. The
main aim is to generate a final mesh that will be robust when used for finite element calculations. Although an
adaptive (skin) mesh could be used in areas where more detail is desired, it is even more important to have a
final (solid) mesh with appropriate topology. To this aim, three alternative operations are suggested herein.

In the first case, the triangles which constitute the watertight mesh are directly transformed into FE triangles.
Then, the triangles are transformed into solid 4-nodes tetrahedral FEs filling the whole volume by means of
automatic advancing front methods which are already implemented in most commercial software packages
(see for example the one implemented in Abaqus [49]). This operation is fully automatic, and, therefore,
extremely fast. In addition, it does not introduce any further geometric approximation. Nevertheless, being the
watertight mesh not conceived for FE analysis, this approach could lead to excessively distorted finite elements
and, therefore, it could fail. In most cases, few local manual refinements could overcome this drawback, but
sometimes the simple regularization of the metrics on the surface (watertight mesh) cannot lead to a good
(undistorted) solid mesh. This aspect mainly depends upon on the mesh generation software that can or cannot
employ robust mesh generation procedures.

In the second case, the volume defined by the watertight mesh is filled by voxel, using well-known and
established voxelization algorithms (see for instance [50]). The outcome strictly relies on the adopted voxel
dimension, which can be chosen depending on the case at hand (possibly comprised in between 0.05 and 0.25
m for historic structures [26]). In this case, the voxel model is nothing more than a 3D matrix in which the
value 1 refers to the structure and the value 0 represents voids, as well as the information of the voxel
dimensions. Therefore, their transformation to 8-nodes hexahedral FEs is a simple, common and standardized
operation [26]. The voxel dimension should represent a good compromise between geometric accuracy and
computational effort of FE analyses. Given a watertight mesh, its voxelization is always possible and the

5

<!-- p. 7 -->

generation of the FE mesh is guaranteed. Therefore, although the voxelized model is generally rougher than
the one obtained through direct transformation of the watertight mesh, the voxelization of the domain
represents a robust and always guaranteed approach for the FE mesh generation.

In the latter case, the watertight mesh is processed by means of a retopology algorithm (see for example [51])
to generate a coarser representation of the surface [52]. This kind of algorithms are able to re-mesh a surface
into a triangular mesh, with a certain resolution chosen by the user, using unified local smoothing operators
that optimize both the edge orientations and vertex positions in the output mesh [51]. Then, the triangles are
transformed into solid 4-nodes tetrahedral FEs. Therefore, the problem dimensions, as well as the number of
solid FEs, are broken down thanks to the reduction of the triangles of the watertight mesh. This operation
produces a further approximation of the surface depending on the resolution of the triangles chosen.

In the a case when where the surveyed structure presents several inner spaces (e.g. rooms) and the presence of
furniture, doors and windows, i.e. the TIN mesh cannot become watertight, other semi-automatic mesh
generation approaches can be employed. The interest reader is referred to the CLOUD2FEM procedure,
recently developed by part of the authors of this manuscript [26, 27, 28]. Indeed, although this procedure is
more laborious than the proposed one, being not completely automatic, it always guarantees the mesh
generation of the 3D geometry. It has to be pointed out that the transformation of hexahedral FEs into
tetrahedral FEs is always possible and it is a very common operation, see for instance [53]. In Fig. 2Fig. 2, a
general flowchart for the FE mesh generation from point clouds is shown.

6

<!-- p. 8 -->

Fig. 2 – Exploiting point cloud of historic constructions for structural purposes: a general flowchart for FE mesh
generation.

7

<!-- p. 9 -->

3.1.1 FE mesh generation of the case study

Fig. 3Fig. 3 presents the main outcomes of the mesh generation operations conducted on the case study. Fig.
3Fig. 3a shows the initial point cloud and Fig. 3Fig. 3b-c shows the TIN mesh. As it can be observed, several
portions of the structure surface are lacking due to the aforementioned drawbacks in the surveying operations.
However, the main geometric features of the structure were successfully collected. The Poisson surface
reconstruction has been conducted on the case study’s data set, characterized by a point cloud density equal to
20,000 pts/m2. Although no significant variation of the mesh quality has been observed with point cloud
densities between 10,000 and 40,000 pts/m2, substantially finer values (e.g. 400,000 pts/m2) leaded to
excessively large meshes which were unable to be processed, whereas considerably coarser values (e.g. 1000
pts/m2) leaded to an excessive approximation of the geometry. Fig. 3Fig. 3d-e shows the resulting watertight
mesh consisting of triangles, where it is superimposed on the TIN mesh of the previous step. As can be noted,
the watertight mesh reasonably approximates the original TIN mesh. In this case, the open source mesh
processing tool MeshLab [54] has been utilized. The level of approximation introduced in the geometry in this
circumstance appears to be included, in the authors’ opinion, within the engineering tolerance.

On the one hand, the FE model of the case study obtained through voxelization is shown in Fig. 3Fig. 3f, where
the value 0.175 m has been adopted as voxel dimension. On the other hand, Fig. 3Fig. 3g shows the solid FE
model obtained through the direct transformation. In this case, no excessive distortion arose. Therefore, this
latter model has been herein preferred over the voxelized model since it does not introduce further geometric
approximations, as voxelization does. Fig. 3Fig. 3h shows the mesh used for the analyses. The mesh consists
of 28,738 nodes and 145,893 4-nodes tetrahedral FEs. All the nodes of the bottom part of the mesh have been
projected to a horizontal plane to allow the easy setup of the boundary conditions in the model (Fig. 3Fig. 3h).
Finally, the solid mesh (Fig. 3Fig. 3i) obtained through retopology [51] (with an average size of the side of the
triangles equal to 60cm) consists of 5,639 nodes and 27,114 tetrahedral FEs. As can be noted, the mesh is
characterized by a largely reduced number of solid FEs. Nevertheless, it is still suitable for structural purposes.

8

<!-- p. 10 -->

a b c

d e f

g h i
Fig. 3 – Points cloud manipulation and mesh generation: a) rough points cloud, b-c) tower’s TIN mesh, d-e) superposition
of TIN mesh and watertight mesh, f) example of voxelization of the domain, g) transformation of the watertight mesh
into a tetrahedral mesh, h) mesh used for numerical analyses and i) solid mesh obtained through retopology.

9

<!-- p. 11 -->

3.2 Limit analysis for the stability assessment of 3D leaning masonry structures

The stability assessment of 3D masonry structures having complex geometry by means of limit analysis can
be performed with 4-nodes rigid infinitely resistant tetrahedrons and triangular interfaces where plastic
dissipation can occur. The utilization of interfaces has proved to be effective for cohesive frictional materials
[55, 56, 57, 58], even if yield lines are fixed and re-meshing would be required. However, the utilization of
rigid elements reduces to a great extent the optimization variables, which is desired in case of complex
geometries. The following formulation permits the flow rule to be violated in the discontinuities preserving,
nevertheless, the upper bound property of the solution. The discontinuity occurs at the common edge between
two adjacent tetrahedrons. To be kinematically admissible, the normal and tangential velocity jumps across
the discontinuity must satisfy the flow rule.

3.2.1 Finite element limit analysis 3D model

The kinematic variables of a tetrahedron are the three centroid velocities and the three rotation
rates around the centroid (Fig. 4Fig. 4). Jump of velocities at a point 𝐸 (𝑢𝑥𝐸, 𝑢𝑦𝐸, 𝑢𝑧𝐸)
on an interface between two adjoining elements and are evaluated as follows: (Φ𝑥𝐸, Φ𝑦𝐸, Φ𝑧𝐸) [𝐔(𝑃)] 𝑃= (𝑥𝑃, 𝑦𝑃, 𝑧𝑃) 𝐼 𝑀 𝑁 [𝐔𝑃𝑀−𝐔𝑃𝑁] = 𝐔𝐺𝑀−𝐔𝐺𝑁+ 𝐑 𝑀(𝑃−𝐺𝑀) −𝐑 𝑁(𝑃−𝐺𝑁) ( 1 ) 𝑢𝑥 𝑢𝑥𝐸 0 −Φ𝑦𝐸 Φ𝑧𝐸 𝑥𝑃−𝑥𝐺 𝐔𝑃𝐸= [𝑢𝑦 ] = [ 𝑢𝑦𝐸 ] + [ Φ𝑦𝐸 0 −Φ𝑥𝐸 ] [𝑦𝑃−𝑦𝐺 ] = 𝐔𝐺𝐸+ 𝐑 𝐸(𝑃−𝐺) 𝑢𝑧 𝑧𝑃−𝑧𝐺 𝑢𝑧𝐸 −Φ𝑧𝐸 Φ𝑥𝐸 0 must be written in the local coordinate system of the interface as where and are the velocity jumps (two tangential𝐼 and[𝐔(𝑃)] 𝐫1𝐼−𝐫2𝐼−𝐬mutually orthogonal and one perpendicular to the interface, see Fig. 4Fig. 4) in the local coordinate systemΔ𝐔(𝑃) = [Δr1 Δr2 Δs]𝑇 = 𝐑𝐼[𝐔(𝑃)], Δr1, Δr2 Δsand is the rotation matrix of the local frame of reference with respect to the global one.Let’s𝐑𝐼 denotes the stress vector with normal and tangential components acting along localaxes 𝐼 𝐼 and see Fig. 4Fig. 4. 𝐭𝐼𝑇= [𝜏1 𝜏2 𝜎𝑠𝐼]On the𝐫1𝐼(𝜏1interface𝐼), 𝐫2𝐼(𝜏2𝐼)of the𝐬 𝐼(𝜎𝑠𝐼),area connecting nodes 1-2-3 (Fig. 4Fig. 4), assuming for the masonry material a
linearized strength domain in the local coordinate system constituted by planes plane of equation 𝐼 Ω
see Fig. 5Fig. 5, and introducing fields of plastic multipliers at 𝑚𝐼 (𝑞𝐼 𝑞𝐼the interface (one for each linearization plane), it can be easily shown that power dissipated is the following:𝐴𝑟1𝑞𝐼𝜏1𝐼+ 𝐴𝑠𝑞𝐼𝜎𝑠𝐼+ 𝐴𝑟2𝑞𝐼𝜏2𝐼= 𝐶𝐼 1 ≤𝑞𝐼≤𝑚𝐼),
𝐼,1 𝐼,2 𝑞𝐼 ( 2 ) Ω 𝑚𝐼 𝑃𝐼= ∑(𝜆̇𝑞𝐼 + 𝜆̇𝑞𝐼 + 𝜆̇𝑞𝐼𝐼,3) 𝐶𝐼 3 𝑞𝐼
where is the plastic multiplier of node 𝐼,𝑗Associated𝜆̇𝑞𝐼 flow 𝑞𝐼rule constraints are imposed 𝑗.again on interface nodes in the following form:
𝑚𝐼 𝑇 𝑞𝐼 𝑞𝐼 ( 3 ) Δ𝐔(𝑃𝑗) = ∑𝜆̇𝑞𝐼𝐼,𝑗[𝐴𝑟1 𝐴𝑟2 𝐴𝜎𝑠𝐼] 𝑞𝐼

10

<!-- p. 12 -->

The external power dissipated can be written as where is the vector of permanent
loads, is the load multiplier for the structure examined, is the vector of variable loads and is the vector 𝑃 𝑒𝑥= (𝐏0𝑇+ 𝜆𝐏1𝑇)𝒗, 𝐏0of assembled centroid elements velocities. As the amplitude of the failure mechanism is arbitrary, the 𝜆 𝐏1 𝒗additional classic normalization condition is also added, reducing thus the external power to linearity.Formally, the linear programming problem𝐏1obtained𝑇𝐯= 1 is classic, and relies into the constrained minimization of
the total internal power dissipated minus the power dissipated by external loads which do not depend by 𝜆:
min{𝑷𝐼𝑖𝑛,𝑎𝑠𝑠𝝀̇𝐼,𝑎𝑠𝑠𝑇−𝑷0𝑇𝒗} ( 4 ) { 𝐛𝑒𝑞 such that {𝐀𝑒𝑞𝐔=where is the vector𝝀̇𝐼,𝑎𝑠𝑠≥0of global unknowns which collects the vector of elements centroids velocities and
rotations of masonry elements and the vector of assembled interface plastic multiplier rates 𝐔 (𝒗)is the vector of assembled plastic multipliers of the interfaces. Also, and are the overall constraints (𝚽) (𝝀̇𝐼,𝑎𝑠𝑠). 𝝀̇𝐼,𝑎𝑠𝑠matrix and vector and collect normalization condition, velocity boundary conditions and plasticity normalityrules on interfaces. 𝐀𝑒𝑞 𝐛𝑒𝑞

interface I N M-N interface I
z
uzNelement N I 1 r21 2
element M 2P N r2 2 r2
y
I sI s 1 r11 2
1 N uyN I s 2 ux N r1 r1 P x P
I 1P r1 I
2 I z P
I I 2 3 r23 I t sI r2I 1I y 3P s 3 r13
x stress action on a point P of interface I

Fig. 4 – Interface between two adjoining elements and stress acting on the interface and local frame of reference
(left); jump of velocities of nodes of the same interface in the local frame of reference (right). 𝐼 𝑀 𝑁,

3.2.2 Master-Slave elements: How to manage problems with over one million degrees of freedom (dof)

Aiming at reducing the numerous amount of optimization variables involved in the limit analysis
computations, a master-slave approach is herein proposed. Indeed, considering that the FE model studied is
constituted by 145,893 elements and approximately 170,000 interfaces and assuming rigid elements (i.e. those
with six degrees of freedom to determine) and interfaces obeying a rough linearization of the Mohr-Coulomb
failure criterion with tension cut-off with only 5 plastic multipliers (at least in the first step, as it will be
explained later on), the limit analysis problem derived would be characterized by slightly less than 2 million
variables. This is certainly a linear programming problem which requires the utilization of either supercomputers or parallelization, with considerably long computational times or out-of-memory issues to tackle.
In order to circumvent such problems and reduce the huge computational effort required, the two-step
procedure shown in Fig. 5Fig. 5 is adopted. Substantially, a rough approximation of the Mohr-Coulomb failure
surface with tension cut-off is utilized in Step 1 to reduce the computational burden. This approximation is
constituted by only 5 planes. Step 1 is used to roughly identify the active failure mechanism and to proceed to
Step 2 using a new active zone band, closer to the actual one. In Step 2, a more refined discretization of the
failure domain is utilized to determine with higher accuracy the active failure surfaces inside each interface.

In the Step 1, a processing zone is a-priori established, assuming only active interfaces between two distances
and from the ground. All elements with centroids inside such region are assumed potentially active and
11𝑧1 𝑧2

<!-- p. 13 -->

any interface involving at least one of such elements is also considered active. Regions outside the interval
are assumed to behave kinematically as a rigid block, fully characterized by the knowledge of the position 𝑧1-of the centroid and six degrees of freedom (3 rotations around the centroid and 3 velocities of the centroid).All𝑧2 interfaces outside the established processing zone are indeed not active and contiguous elements cannot
separate in any manner. Being rigid elements, they are therefore constrained to move as part of the same rigid
body. Therefore, the slave region is treated as the assemblage of few single rigid elements with complex
geometry, so the finite element nodes on the edges between the meshed region and the rigid bodies are the
slave nodes being dependent on the degrees of freedom expressed at the centroids of the rigid bodies.

Although this assumption is arbitrary, the user generally knows in advance the nature of the expected failure
mechanism. For the problem under investigation, a failure mechanism characterized by a shear-flexural hinge
located near the base is expected. The exclusion of the mesh on the upper part does not preclude in any manner
a correct estimation of failure loads and collapse mechanisms. In Step 1, there is also no need to refine the
linearization of the failure surface assumed for the interfaces, because the aim is only to identify possible subregions of active interfaces. In this manner, the obtained linear programming problem contains a reasonable
total number of optimization unknowns. The width of the active region can be properly tuned to obtain
problems that are computationally more sustainable for the available computers.

Once the exact regions of active interfaces are known (from the solution of the linear programming problem
in Step 1), the processing zone is again reduced in Step 2 to further drop-down the optimization variables.
Generally, authors experienced that such new processing zone found in Step 1 should be slightly enlarged
including 2 or 3 rows of neighbouring inactive elements with the aim of compensating potential inaccuracies
of the procedure due to, for example, the rough discretization adopted for the failure surfaces of the interfaces
in Step 1. The strong reduction of the active interfaces in Step 2 allows for a refinement of the linearization of
the interfaces failure surfaces, with the possible inclusion of a compression cut-off, although this is not
essential for such kind of problems.

Step 1 I
1 FM
rigid block 1
Mohr-Coulomb c: cohesion
with tension
cutoff
rigid block 3 & 4 (5 linearization I
z2 planes

first attempt ft: tension cutoff
processing I
zone 2
z1 meshed
I
1

rigid block 2

I
I 2
Step 2
I
1 FM
rigid block 1
c: cohesion
rigid block 1 2

rigid block 2 I
rigid block 3 & 4
rigid block 3

ft: tension cutoff
fc: compression cutoff
Processing I
zone after 2
initial iteration Processing zone Mohr-Coulomb with
increse of 2-3 rows of tension cutoff and
elements compression cap
rigid block 2

Fig. 5 – Two-step master-slave approach adopted.

12

<!-- p. 14 -->

In Step 1, computations are performed assuming 129,872 slave elements, 4 master regions of rigid blocks and
a total number of active elements equal to 16,021, as depicted in Fig. 6Fig. 6 (active elements are indicated in
orange in the picture). Such a choice leads to tackle a linear programming problem constituted by about 14,000
interfaces and around 160,000 optimization variables. As it will be discussed later on in the paper, the
evaluation of the ultimate inclination can be assimilated to the study at collapse of the same structure resting
on a tilting plane. Such problem becomes nonlinear, due to the presence of a few nonlinearities. A sequential
linear programming (SLP) strategy is therefore adopted, linearizing the nonlinear constraints and repeating a
sequence of few linear programming iterations, typically 4-5. On a work station equipped with 32 in-parallel
processors and CPLEX solver [59], Step 1 within the SLP procedure is solved in less than 3 hours. The rough
identification of the processing zone reduces further the number of active elements to about 4,000, with less
than 5,000 active interfaces. Assuming a quite refined linearization of the failure surface for the interfaces with
25 planes, the total number of optimization variables involved is roughly 150,000, comparable with those
utilized in Step 1 and hence, with similar processing times needed.

Fig. 6 – Slave elements: 129,872, Master regions: 4, Total #elements: 16,021.

3.2.3 Limit analyses on a tilting plane

The limit inclination angle of a masonry structure (i.e. the angle which leads the collapse of the structure under
gravity loads only) can be computed within a mathematical programming FE procedure. This is a particular
type of limit state problem, where the collapse of a structure resting on a tilting plane is determined by
progressively increasing the inclination of the base plane from the horizontal direction (i.e. by increasing the
angle see Fig. 7Fig. 7) up to collapse. In this framework, the collapse multiplier adopted is i.e. the limit
inclination angle of the tilting base. 𝜗, 𝜗,
External loads (due exclusively to gravity) are the components of the gravity load which act perpendicularl
and tangential to the tilting base. The progressive rotation of the tilting plane results into a decrease of the
vertical load and an increase of the horizontal one, according to the decomposition of the gravity loads into
the horizontal component and the vertical component respectively, Fig. 7Fig. 7. If the 𝐖inclination angle of the tilting plane is assumed to play the role of the collapse multiplier in the limit analysis (𝐖sin 𝜗) (𝐖cos 𝜗)problem ( 4( 4 ), it is worth noting that there is no way to deal with it using linear programming routines,because the normalization condition𝜗 becomes nonlinear. Obviously, the external power dissipated (which
contains only loads dependent upon the collapse multiplier) is nonlinear. In limit analysis, loads are applied
contemporarily at the same time and a snapshot of the situation is provided at failure via the solution of a
constrained minimization problem.

13

<!-- p. 15 -->

In such a particular case, where again stands for the vector of loads not dependent 𝑷1𝑇(𝜗)
on is the vector of all loads dependent on and is the vector of assembled velocities at the centroid of 𝑃𝑒𝑥= (𝑷0𝑇+ 𝜗 𝜗) 𝒗, 𝑷0 𝑇
the elements. The normalization condition is obviously which is clearly a nonlinear function. 𝜗, 𝑷1 𝜗 𝒗 𝑷1𝑇(𝜗)Such nonlinearity has the consequence that the obtained𝜗mathematical𝒗= 1, programming problem is nonlinear.
Almost identical to ( 4( 4 ), such nonlinear programming problem -where the nonlinear normalization condition
is put in evidence-, can be written as follows:
min{𝑷𝐼𝑖𝑛,𝑎𝑠𝑠𝝀̇𝐼,𝑎𝑠𝑠𝑇−𝑷0𝑇𝒗} 𝐀𝑒𝑞𝐔= 𝐛𝑒𝑞 𝑷1𝑇(𝜗) ( 5 ) such that { 𝒗−1 = 0 𝜗The{ nonlinear programming𝝀̇𝐼,𝑎𝑠𝑠≥0 problem ( 5( 5 ) can be solved by means of two distinct possible approaches: a)
using a standard non-linear programming (NLP) routines, and b) implementing a sequential linear
programming SLP procedure, linearizing the nonlinear normalization condition. This last approach is preferred
here, and it is worth mentioningd𝑷1𝑇(𝜗) that the linearization of the nonlinear equation can be written as follows: 𝑇(𝜗0) 𝜗𝒗 −𝑷1𝑇(𝜗)𝒗 d𝜗 (𝑷1 𝒗0 −1) + | 𝜗= 0 ( 6 ) 𝜗0 𝜗2 𝜗=𝜗0 𝒗 =𝒗0
Where subscript 0 indicates the solution of the previous iteration. The starting point selected at the beginning
of the SLP procedure when linearizing Eq. ( 6 )( 6 ) coincides with an inclination angle of the tilting plane
equal to Therefore, the limit inclination angle of the structure is evaluated as the sum of the limit
inclination angle of the tilting plane and of the actual inclination of the structure. As a matter of fact, the 𝜗= 0.evaluation of the actual inclination of the structure is not an easy task, because it depends on the in-planedirection along which the inclination 𝜗is evaluated. For the case study at hand, plotting the in-plane position of
nodes belonging to two horizontal planes as shown in Fig. 8Fig. 8, and assuming that the vertical distance
between the two planes is known, it is possible to estimate easily the out-of-plane inclination of the tower
along the different in-plane directions considered. Such inclination, as it will be explained later on in the paper,
varies typically between about 10° to about 2°, passing from a direction almost parallel to y to the horizontal
direction, respectively. Authors experienced that the SLP approach converges very quickly, with stabilization
of the collapse inclination angle of the tilting plane after few iterations (3-5).

lateral view on plane plane view
vertical axis plane
of the tower direction of the
cylindrical hinge C

Wsin

x
Wsin

x
W Wcos direction of the
y Wsin plane cylindrical hinge C
tilting plane W Wcos

cylindrical hinge C

14

<!-- p. 16 -->

Fig. 7 –Limit analysis strategy for evaluating the collapse inclination of the 3D structure.

Plane

C1
0.52965 m
0.73035 m
0.92639 m
C2
Plane 1.1117 m
1.2803 m
1.545 m
1.6982 m
1.4264 m
Ground Plane 1.6756 m
1.6317 m
1.6834 m

Axonometric view Planar view
Fig. 8 – Evaluation of the actual inclination of the structure along different in-plane directions.

A final issue to tackle is the choice of the in-plan direction of the horizontal load, namely the angle shown
in Fig. 7Fig. 7. In general, the angle cannot coincide with the angle identifying the direction of plane Ψ′(the angle 90°- identifies on the other hand the direction of the cylindrical hinge around which the tower Ψ′ Ψ, Πrotates during the collapse under self-weight). Ψ
Authors experienced that it is necessary to scan angles within the range -10°-100° to obtain in output angles
between 0° and 90°. Then, the identification of the associated with the minimum of the collapse Ψ′inclination of the tower can be obtained by a simple spline interpolation of the different angles obtained byΨ Ψlimit analysis computations. Ψ

4 Results and discussion

Limit analyses are performed on the actual 3D geometry of the structure (Fig. 3Fig. 3h) which is derived from
the laser scanning survey. The material of the tower, or more precisely all interfaces between adjoining
tetrahedrons, is was assumed to obey a Mohr-Coulomb criterion with tension cut-off, with mechanical
properties approximating reasonably a continuum almost unable to withstand tensile stresses. In particular,
considering that the tower is severally deteriorated and in agreement with consolidated literature [60], cohesion
and tensile strength were kept constant through the tower and equal to 0.02 MPa. The assumption of small
but non-zero values of cohesion and tensile strength improves the numerical stability of the linear programming𝑐solver and at the same𝑓𝑡time does not drastically increase failure multipliers. In such problems, indeed, almost
all the stabilizing contribution is provided by gravity loads and internal dissipation turns out to play a negligible
role on the increase of the collapse multiplier. Stability problems, such as the leaning historic masonry
structures, are governed by geometry. Mechanical properties of the masonry tower were not available. Material
properties assumed based on authors experience and from codes of practice. Thus, the friction angle of
masonry has been set equal to 25°, a value very similar to that assumed in the Italian code in for the evaluationof the ultimate base-sliding shear for piers. Such value of the friction angle allows avoiding the formation𝜙 of
failure mechanisms due to sliding of macro-blocks, which are unlike in such kind of limit analysis problems.
The choice to remove the cap in compression (see Fig. 5Fig. 5) has been made for a twofold reason: first of
all, to limit as close as possible the optimization variables and second because the collapse of a tower after
having reached the limit inclination angle occurs without evidence of crushing near the compressed toe.
According to the two-step master-slave procedure proposed in the previous Sections, in Step 1 a rough
linearization with 5 planes (and hence 5 plastic multipliers is adopted), whereas in Step 2 a piecewise linear
15

<!-- p. 17 -->

approximation with 25 planes (24 for the pure Mohr-Coulomb strength domain, 6 per quadrant and 1 for the
tension cut-off) is assumed. The SLP procedure is here utilized to deal with the nonlinearity presented in such
special limit analysis problem.

The resultant limit inclination angles of the structure so obtained varying the direction of the tilting plane are
depicted in Fig. 9Fig. 9 and compared with its actual inclination (thick black line), computed as shown in Fig.
8Fig. 8. The collapse mechanism of the structure for a horizontal direction corresponding to the smallest limit
inclination is highlighted in Fig. 10Fig. 10.From a careful(Ψ =analysis60°) of the numerical results obtained, the following considerations can be drawn:

\1) The tower is at present in a state not far from its collapse state. In particular, for a direction of the
rocking plane roughly within the range: an additional inclination of would
lead to the collapse of the structure, see Fig. 9Fig. 9. Considering the recent wetting-drying cycles which the structureΠ has been subjected to, 60°a careful≤Ψ ≤75°,analysis of the most suitable interventions1.5° to
preclude rocking failure would be needed.
\2) Crack pattern found by means of the limit analysis simulation corresponding to (Fig. 10Fig.
\10) shows the clear formation of a cylindrical rotational hinge near the base. The plasticization band is relatively narrow and tends to follow the geometric irregularities of the structureΨ = 60°near the base,
passing through the weakest transversal sections. The definition of a cylindrical hinge is therefore in
principle not proper, because of both the finite thickness of the band and the not straight configuration
of the plasticization zone.
\3) The concentration of all the plastic flow near the base, in agreement with intuition, indirectly confirms
that the master-slave approach proposed is fully consistent with the real behaviour.
\4) Once the exact shape of the crack at the base is known, the failure mechanism is clearly identified and
hand calculations (or assisted by a CAD program) can be performed to evaluate the position of the
center of gravity of the macro-block subjected to rocking. In this way, the estimation of the collapse
inclination angle is very straightforward and provides a further validation of the procedure proposed,
as well as a ready to use instrument by common practitioners involved in the safety assessment of
leaning historic masonry structures.

16

<!-- p. 18 -->

Fig. 9 – Comparison between actual inclination and limit inclination of the structure for several horizontal
directions of the rocking direction.

17

<!-- p. 19 -->

Direction of the
plastic hinge

Direction of
rocking planeFig. 10 – Collapse mechanism (with indication of the plastic processing zones) in the horizontal directionΠ
corresponding to the smallest limit inclination (Ψ=60°).

18

<!-- p. 20 -->

4.1 Verification of the procedure: Enlarged active volume and single-step analysis

Additional limit analyses have been conducted to show the reliability of the assumption of rigid bodies (masterslave approach) by employing different sizes of the processing zones (Step 1), in order to check the
convergence of the limit analysis solution (see Mesh #1 and Mesh #2 in Fig. 11Fig. 11). Particularly, Mesh #1
is characterized by an enlargement of the processing zone, with respect to the one employed in the previous
sections (Present Mesh in Fig. 11Fig. 11), which represents the largest active volume faceable for the
computers at disposal. Conversely, Mesh #2 (Fig. 11Fig. 11) represents a restriction of the previous processing
zone, which also excludes interfaces where plastic dissipation occurred in the Present Mesh (Fig. 10Fig. 10).
In addition, the mesh obtained through retopology (Coarse Mesh in Fig. 11Fig. 11) has been utilized to solve
the LP problem in the framework of a single-step analysis, i.e. without master-slave approach.

Fig. 12Fig. 12 shows the comparison among collapse inclinations of the structure at several horizontal
directions of the rocking direction, with different meshes/processing zones tested. Furthermore, Fig. 13Fig. 13
shows the comparison between the collapse deformed shapes of the coarse mesh (top) and Mesh #1 (bottom)
in the horizontal direction Ψ=60°. For the sake of brevity, the failure mechanism of Mesh #2, which is
completely different from the others (characterized by a sub-horizontal crack surface), is not reported.

As can be noted in Fig. 12Fig. 12, a very good agreement is achieved in terms of collapse inclinations between
Mesh #1 and the Present Mesh. Conversely, Mesh #2 radically overestimates the collapse inclinations of the
structure. Indeed, the excessive restriction of the active volume, i.e. the exclusion of interfaces where plastic
dissipation occurs, is responsible for the increase of the load carrying capacity of the structure, as well as a
different failure mechanism. Moreover, the collapse inclinations evaluated through the Coarse Mesh (singlestep analysis), although slightly overestimated due to the coarser mesh adopted, are in a reasonable agreement
with the ones obtained with Mesh #1 and the Present Mesh, confirming the reliability of the two-step approach
proposed.

Additionally, the failure mechanisms collected in Fig. 13Fig. 13 further validate the one obtained with the
Present Mesh (Fig. 10Fig. 10). Indeed, they substantially show the same failure mechanism with plastic
dissipation essentially in the same zones (compare Fig. 13Fig. 13 with Fig. 10Fig. 10), although the failure
mechanism obtained with the Coarse Mesh (Fig. 13Fig. 13, top) is computed through a single-step approach
(fully active volume). Therefore, this outcome further confirms the effectiveness of the master-slave approach
proposed and the choice of the processing zone adopted for the Present Mesh (Fig. 6Fig. 6).

Finally, Table 1Table 1 collects the computational times required to solve the limit analysis problems. The
following considerations can be drawn:

\1) The time needed to solve the problem with the Present Mesh is around 18 hours, considerably less
than the time needed by Mesh #1. Therefore, the Present Mesh, which is more accurate than the Coarse
mesh (Fig. 11Fig. 11), appears a suitable compromise to speed up computations with a precise
geometric and mechanical approximation of the real situation.

\2) Step 2 requires generally more time to be performed, because of the utilization of several planes to
approximate interfaces failure surface. Mesh #2 requires the same time for Step 1 and Step 2 because
of the too restricted processing zone in Step 1, which does not allow to find a plausible failure
mechanism.

19

<!-- p. 21 -->

Fig. 11 – Different sizes of the processing zones (Step 1) tested to check the convergence of the limit
analysis solution (middle and right) and coarse mesh (left) utilized to solve the LP problem (single-step
approach). Present Mesh refers to the processing zone depicted in Fig. 6Fig. 6.

Fig. 12 – Comparison among collapse inclinations of the structure at several horizontal directions of the
rocking direction and with the different meshes/processing zones tested.

20

<!-- p. 22 -->

Fig. 13 – Comparison between collapse deformed shapes (with indication of the plastic processing zones) for
the coarse mesh (top) and Mesh #1 (bottom), in the horizontal direction corresponding to the smallest limit
inclination (Ψ=60°).

Table 1. Times required to solve the limit analysis problems.

Solution of the LA problem(x) hh:mm:ss
Step 1 Step 2
Present Mesh 06:12:44 12:01:05
Mesh 1 15:48:09 33:19:52
Mesh 2 03:31:28 03:27:02
Coarse Mesh (single-step analysis) 21:25:13
(x) CPLEX solver on a work station equipped with 64bit 2x16GB DDR4 RAM (16 slots). Computations are referred
to the evaluation of the collapse inclination for 7 tilting directions. Computations include also pre-processing phases,
such as identification of the interfaces and assemblage of the equality and inequality constraints.

21

<!-- p. 23 -->

4.2 Verification of the procedure: Nonlinear finite element analysis

A further verification of the proposed structural analysis approach is achieved by means of the comparison
with the results of a nonlinear finite element tilting plane incremental analysis. In this analysis, isotropic
plastic-damage behaviour [61] is adopted for masonry. Although masonry is a complex material typically
characterized by anisotropic behaviour, the hypothesis of isotropic nonlinear material generally appears
suitable for historic masonries, as they usually present chaotic and random textures [33, 32, 28].

The adopted continuum plastic-damage model [61, 49] is characterized by a yielding function with multiplehardening variables and two independent scalar damage variables, one for the tensile damage and the other
for compressive damage Being the model formulated in the context of nonassociated plasticity [61], the 𝑑𝑡plastic potential is defined by the dilatancy angle generally assumed equal to 10° for masonry [62], as well 𝑑𝑐.as by a smoothing parameter usually assumed equal to 0.1 [63]. In addition, the strength domain is specified 𝜓,by the ratio between the biaxial and uniaxial initial compressive strengths, typically assumed 𝜖equal to 1.16 [64], and by the shape constant normally assumed equal to 2/3 [63]. 𝑓𝑏0/𝑓𝑐0 𝑓𝑏0 𝑓𝑐0Reference to the Italian code has been made 𝜌,to set the mechanical properties of the material (cluttered stone
masonry), which are collected in Table 2Table 2. The tensile strength has been kept equal to the value used in
the FELA, whereas the evolution of the scalar damage variables and has been kept substantially
proportional to the decay of the uniaxial stresses, as adopted in several numerical campaigns [32, 63, 33] (Table2Table 2). 𝑑𝑡 𝑑𝑐

Dead load is initially applied to the structure through an incremental procedure, considering clamped boundary
conditions at the base. Then, a pattern of imposed displacements, which simulates a tilting plane, is
incrementally applied at the base of the structure. Abaqus Standard [49] has been used to conduct the
simulation. Geometric nonlinearity has been considered to account for large-displacement effects, which, in
this case, are expected to play a fundamental role.

Fig. 14Fig. 14 shows the tensile damage contour plot obtained with a nonlinear finite element tilting plane
incremental analysis. In particular, Fig. 14Fig. 14 refers to the condition in which the base inclination of thetower equals the limit inclination computed(𝑑𝑡)through FELA, in the horizontal direction with the smallest limit
inclination As can be noted, the crack pattern in Fig. 14Fig. 14 is in good agreement with the
collapse mechanism observed with FELA (Fig. 10Fig. 10 and Fig. 13Fig. 13). Indeed, all of the failuremechanisms(Ψare= governed60°). by the overturning of the highest part of the tower with a detachment from the
remaining part, which pseudo-horizontally runs from one side of the tower to the opposite one. Although the
crack pattern in Fig. 14Fig. 14 also shows a pseudo-vertical crack along the central part of the tower’s trunk,
it does not cross the thickness of the wall (Fig. 14Fig. 14). Therefore, such crack does not appear essential in
the main failure mechanism of the tower. Rather, this vertical crack develops after the formation of the
horizontal main fissure, being the result of large-displacement effects.

Finally, it should be pointed out that the evaluation of the limit inclination angle by means of the standard
nonlinear finite element tilting plane analysis herein adopted is non-trivial and, in facts, requires specific
interpretation of the results. Therefore, further studies on this topic are needed. Consequently, the proposed
FELA approach appears more robust than standard nonlinear FE methods, being able to directly compute the
limit inclination angle of a masonry structure.

22

<!-- p. 24 -->

Fig. 14 – Tensile damage contour plot obtained with a nonlinear finite element tilting plane analysis, in the
condition of a base inclination of the tower equal to the limit inclination computed through FELA, in the
horizontal direction with the smallest limit inclination (Ψ = 60°).

Table 2. Mechanical properties adopted for masonry in the FELA and in the continuum plastic-damage
models.

FELA model
Tensile strength [MPa] Cohesion [MPa] Friction angle
0.02 0.02 25° 𝑓𝑡 𝑐 𝜙
Continuum plastic-damage model
Young’s modulus[MPa] Poisson’s ratio Density [kg/m3] [\] [\] [\] [\]
870 0.15 1900 0.1 10° 1.16 2/3 Tensile uniaxial nonlinear behaviour Compressive𝜖 uniaxial𝜓 nonlinear𝑓𝑏0/𝑓𝑐0behaviour𝜌
Stress [MPa] Inelastic strain [\] Stress [MPa] Inelastic strain [\]
0.02 0 0 1.0 0 0 0.001 0.0001 𝑑𝑡0.95 1.1 0.001 𝑑𝑐0
0.05 0.007 0.95

5 Conclusions

In this paper, a simplified and rapid procedure for the automatic transformation of point clouds (surveyed on
historic structures) to 3D FE meshes, passing from the concept of watertight mesh, and their utilization in a
multi-step upper bound limit analysis with automatic variables reduction, has been proposed. The level of
approximation introduced in the actual geometry appeared to be included within the engineering tolerance.

Following the Heyman’s intuition, the use of 3D FELA on the generated mesh is implemented to evaluate the
critical condition (i.e. maximum inclination capacity) of a leaning historic masonry structure. In this way, the
structural health condition of a historic structure is evaluated by comparing the maximum critical inclination
angle against the current one. Considering that FE meshes obtained from detailed laser scanner surveys would
consist of many variables to make the limit analysis impossible to solve even with powerful workstations, a
recursive identification of the processing zone has been proposed, excluding from computations all those
elements which do not undergo plastic deformation. The automatic procedure adjusts iteratively the processing
zone, progressively restricting the analysis to the few elements interested by the failure mechanism and

23

<!-- p. 25 -->

considering the other portions outside the processing zone as rigid blocks. Also, a sequential linear
programming kernel has been adopted to linearize the normalization condition, which becomes nonlinear if
the inclination angle at failure is considered as collapse multiplier.

To demonstrate the effectiveness of the automated procedure, the southwest leaning ruined tower of the
Caerphilly castle (Wales, UK) has been employed as a case study. It emerged that the tower in its actual
condition is not far from its collapse. Indeed, an additional inclination of the structure by appears to be
critical. In this limit condition, the collapse mechanism of the structure has been found in agreement withintuition, i.e. it consists in the overturning of the main leaning part of the structure. The 1.5°results have been
further validated by means of the comparison with the outcomes of single-step analyses (fully active volume)
and nonlinear FE analyses.

The procedure proposed herein is characterized by a high degree of automation at each operational level. Such
approach could be effectively utilised to assess the stability of historic structures at a national scale and provide
useful information to engineers and managers to classify the structural health condition of historic assets in
their care.

Although the procedure proposed represents a novel solution for evaluating the stability of extant masonry
structures, it could be enriched with an adaptive mesh enhancement in the framework of a multi-step strategy.

Acknowledgements

The authors gratefully acknowledge Dr Oriel Priezman for providing the point cloud of the southwest tower
of the Caerphilly castle. Financial support by the Italian Ministry of Education, Universities and Research
MIUR is gratefully acknowledged (PRIN2015 “Advanced mechanical modeling of new materials and
structures for the solution of 2020 Horizon challenges” prot. 2015JW9NJT_018).

References

[1] M. Como, Statics of Historic Masonry Constructions, Springer Series in Solid and Structural Mechanics,
\2013.

[2] J. B. Burland, M. Jamiolkowski and C. Viggiani, “The Stabilisation of the Leaning Tower of Pisa,” Soil
and Foundations, vol. 43, no. 5, p. 63–80, 2003 doi:10.3208/sandf.43.5_63.

[3] F. Pisanò, C. G. Di Prisco and R. Lancellotta, “Soil–foundation Modelling in Laterally Loaded Historical
Towers,” Géotechnique, vol. 64, no. 1, p. 1–15, 2014 doi:10.1680/geot.12.p.141.

[4] M. Marchi, R. Butterfield, G. Gottardi and R. Lancellotta, “Stability and Strength Analysis of Leaning
Towers,” Géotechnique, vol. 61, no. 12, p. 1069–1079, 2011 doi:10.1680/geot.9.p.054.

[5] E. C. Hambly, “Soil buckling and the leaning instability of tall structures,” The Structural, vol. 63A, no.
3, 1985.

[6] D. Abruzzese, L. Miccoli and J. Yuan, “Mechanical Behavior of Leaning Masonry Huzhu Pagoda,”
Journal of Cultural Heritage, vol. 10, no. 4, p. 480–486, 2009 doi:10.1016/j.culher.2009.02.004.

[7] G. Milani, R. Shehu and M. Valente, “Role of Inclination in the Seismic Vulnerability of Bell Towers:
FE Models and Simplified Approaches,” Bulletin of Earthquake Engineering, vol. 15, no. 4, p. 1707–
1737, 2016 doi:10.1007/s10518-016-0043-0.

24

<!-- p. 26 -->

[8] J. Heyman, “Leaning Towers,” Meccanica, vol. 27, no. 3, p. 153–159, 1992 doi:10.1007/bf00430041.

[9] W. Addis, Building: 3000 years of design engineering and construction, Phaidon Press, 2007.

[10] K. Martini, “Ancient Structures and Modern Analysis: Investigating Damage and Reconstruction at
Pompeii,” Automation in Construction, vol. 8, no. 1, p. 125–137, 1998 doi:10.1016/s0926-
5805(98)00070-3.

[11] J. Martínez, A. Soria-Medina, P. Arias and A. F. Buffara-Antunes, “Automatic Processing of Terrestrial
Laser Scanning Data of Building Façades,” Automation in Construction, vol. 22, p. 298–305, 2012
doi:10.1016/j.autcon.2011.09.005.

[12] J. Armesto, I. Lubowiecka, C. Ordóñez and F. I. Rial, “FEM Modeling of Structures Based on Close
Range Digital Photogrammetry,” Automation in Construction, vol. 18, no. 5, p. 559–569, 2009
doi:10.1016/j.autcon.2008.11.006.

[13] A. D. Styliadis, “Digital documentation of historical buildings with 3-d modeling functionality,”
Automation in Construction, vol. 16, no. 4, p. 498–510, 2007 doi:10.1016/j.autcon.2006.09.003.

[14] F. Zvietcovich, B. Castaneda and R. Perucchio, “3D Solid Model Updating of Complex Ancient
Monumental Structures Based on Local Geometrical Meshes,” Digital Applications in Archaeology and
Cultural Heritage, vol. 2, no. 1, p. 12–27, 2015 doi:10.1016/j.daach.2015.02.001.

[15] A. Pesci, G. Casula and E. Boschi, “Laser Scanning the Garisenda and Asinelli Towers in Bologna
(Italy): Detailed Deformation Patterns of Two Ancient Leaning Buildings,” Journal of Cultural
Heritage, vol. 12, no. 2, p. 117–127, 2011 doi:10.1016/j.culher.2011.01.002.

[16] H. K. Dhonju, W. Xiao, V. Sarhosis, J. P. Mills, S. Wilkinson, Z. Wang, L. Thapa and U. S. Panday,
“Feasibility study of low-cost image-based heritage documentation in Nepal,” in ISPRS - International
Archives of the Photogrammetry, Remote Sensing and Spatial Information Sciences XLII–2/W3
(February 23, 2017): 237–242, 2017.

[17] C. Ordóñez, J. Martínez, P. Arias and J. Armesto, “Measuring Building Façades with a Low-Cost Close-
Range Photogrammetry System,” Automation in Construction, vol. 19, no. 6, p. 742–749, 2010
doi:10.1016/j.autcon.2010.03.002.

[18] B. Riveiro, M. J. DeJong and B. Conde, “Automated Processing of Large Point Clouds for Structural
Health Monitoring of Masonry Arch Bridges,” Automation in Construction, vol. 72, p. 258–268, 2016
doi:10.1016/j.autcon.2016.02.009.

[19] D. F. Laefer and L. Truong-Hong, “Toward automatic generation of 3D steel structures for building
information modelling,” Automation in Construction, vol. 74, pp. 66-77, 2017
doi:10.1016/j.autcon.2016.11.011.

[20] H. Dhonju, W. Xiao, V. Sarhosis, J. Mills, S. Wilkinson, Z. Wang, L. Thapa and U. Panday, “Feasibility
study of low-cost image-based heritage documentation in Nepal,” in 3D ARCH - 3D Virtual

25

<!-- p. 27 -->

Reconstruction and Visualization of Complex Architectures: 7th International Workshop ISPRS,
Nafplio, Greece, 2017.

[21] H. Dhonju, W. Xiao, B. Shakya, J. Mills and V. Sarhosis, “Documentation of Heritage Structures
Through Geo-Crowdsourcing and Web-Mapping,” in WebMGS 2017. 2017, 19-20 Sept. during ISPRS
Geospatial Week, 18-22 September 2017, Wuhan, China, 2017.

[22] J. L. Sánchez-Aparicio, S. Del Pozo, L. F. Ramos, A. Arce and F. M. Fernandes, “Heritage Site
Preservation with Combined Radiometric and Geometric Analysis of TLS Data,” Automation in
Construction, vol. 85, p. 24–39, 2018 doi:10.1016/j.autcon.2017.09.023.

[23] C. Biagini, P. Capone, V. Donato and N. Facchini, “Towards the BIM Implementation for Historical
Building Restoration Sites,” Automation in Construction, vol. 71, p. 74–86, 2016
doi:10.1016/j.autcon.2016.03.003.

[24] L. Truong-Hong and D. F. Laefer, “Validating Computational Models from Laser Scanning Data for
Historic Facades,” Journal of Testing and Evaluation, vol. 41, no. 3, p. 481–496, 2013
doi:10.1520/jte20120243.

[25] T. Hinks, H. Carr, L. Truong-Hong and D. F. Laefer, “Point Cloud Data Conversion into Solid Models
via Point-Based Voxelization,” Journal of Surveying Engineering, vol. 139, no. 2, p. 72–83, 2013
doi:10.1061/(asce)su.1943-5428.0000097.

[26] G. Castellazzi, A. M. D’Altri, G. Bitelli, I. Selvaggi and A. Lambertini, “From Laser Scanning to Finite
Element Analysis of Complex Buildings by Using a Semi-Automatic Procedure,” Sensors, vol. 15, no.
8, p. 18360–18380, 2015 doi:10.3390/s150818360.

[27] G. Castellazzi, A. M. D'Altri, S. de Miranda, F. Ubertini, G. Bitelli, A. Lambertini, I. Selvaggi and A.
Tralli, “A mesh generation method for historical monumental buildings: An innovative approach,” in
Proceedings of the VII European Congress on Computational Methods in Applied Sciences and
Engineering (ECCOMAS Congress 2016), Crete Island, 2016 doi:10.7712/100016.1823.11948.

[28] G. Castellazzi, A. M. D’Altri, S. de Miranda and F. Ubertini, “An Innovative Numerical Modeling
Strategy for the Structural Analysis of Historical Monumental Buildings,” Engineering Structures, vol.
132, p. 229–248, 2017 doi:10.1016/j.engstruct.2016.11.032.

[29] Ł. Bednarz, A. Górski, J. Jasieńko and E. Rusiński, “Simulations and Analyses of Arched Brick
Structures,” Automation in Construction, vol. 20, no. 7, p. 741–754, 2011
doi:10.1016/j.autcon.2011.01.005.

[30] L. Truong-Hong and D. F. Laefer, “Impact of Modeling Architectural Detailing for Predicting
Unreinforced Masonry Response to Subsidence,” Automation in Construction, vol. 30, p. 191–204, 2013
doi:10.1016/j.autcon.2012.11.004.

[31] M. Solla, H. Lorenzo, A. Novo and J. Caamaño, “Structural Analysis of the Roman Bibei Bridge (Spain)
Based on GPR Data and Numerical Modelling,” Automation in Construction, vol. 22, p. 334–339, 2012
doi:10.1016/j.autcon.2011.09.010.

26

<!-- p. 28 -->

[32] G. Castellazzi, A. M. D’Altri, S. de Miranda, A. Chiozzi and A. Tralli, “Numerical Insights on the
Seismic Behavior of a Non-Isolated Historical Masonry Tower,” Bulletin of Earthquake Engineering,
vol. 16, no. 2, p. 933–961, 2018 doi.org/10.1007/s10518-017-0231-6.

[33] A. M. D’Altri, G. Castellazzi, S. de Miranda and A. Tralli, “Seismic-Induced Damage in Historical
Masonry Vaults: A Case-Study in the 2012 Emilia Earthquake-Stricken Area,” Journal of Building
Engineering, vol. 13, p. 224–243, 2017 doi:10.1016/j.jobe.2017.08.005.

[34] S. Tiberti, M. Acito and G. Milani, “Comprehensive FE Numerical Insight into Finale Emilia Castle
Behavior Under 2012 Emilia Romagna Seismic Sequence: Damage Causes and Seismic Vulnerability
Mitigation Hypothesis,” Engineering Structures, vol. 117, p. 397–421, 2016
doi:10.1016/j.engstruct.2016.02.048.

[35] E. Bassoli, L. Vincenzi, A. M. D'Altri, S. de Miranda, M. Forghieri and G. Castellazzi, “Ambient
vibration-based finite element model updating of an earthquake-damaged masonry tower,” Structural
Control and Health Monitoring, 2018 (in press) doi.org/10.1002/stc.2150.

[36] T. Bui, A. Limam, V. Sarhosis and M. Hjiaj., “Discrete Element Modelling of the in-Plane and Out-of-
Plane Behaviour of Dry-Joint Masonry Wall Constructions,” Engineering Structures, vol. 136, p. 277–
294, 2017 doi:10.1016/j.engstruct.2017.01.020.

[37] V. Giamundo, V. Sarhosis, G. Lignola, Y. Sheng and G. Manfredi, “Evaluation of Different
Computational Modelling Strategies for the Analysis of Low Strength Masonry Structures,” Engineering
Structures, vol. 73, p. 160–169, 2014 doi:10.1016/j.engstruct.2014.05.007.

[38] G. Milani, P. Lourenço and A. Tralli, “3D Homogenized Limit Analysis of Masonry Buildings Under
Horizontal Loads,” Engineering Structures, vol. 29, no. 11, p. 3134–3148, 2007
doi:10.1016/j.engstruct.2007.03.003.

[39] B. Riveiro, M. Solla, I. de Arteaga, P. Arias and P. Morer., “A Novel Approach to Evaluate Masonry
Arch Stability on the Basis of Limit Analysis Theory and Non-Destructive Geometric Characterization,”
Automation in Construction, vol. 31, p. 140–148, 2013 doi:10.1016/j.autcon.2012.11.035.

[40] E. Moradabadi and D. Laefer, “Opportunities in Numerical Modelling of Pre-existing Damage of
Historical Masonry Buildings,” in 9th International Masonry Conference, Guimarães, Portugal, 2014.

[41] V. Sarhosis, “Micro-modelling options for masonry structures,” in Computational Modelling of Masonry
Structures Using the Discrete Element Method, IGI Global, 2016.

[42] P. G. Asteris, V. Sarhosis, A. Mohebkhah, V. Plevris, L. Papaloizou, P. Komodromos and J. V. Lemos,
“Numerical Modeling of Historic Masonry Structures,” in Handbook of Research on Seismic Assessment
and Rehabilitation of Historic Structures, IGI Global, 2015, pp. 213-256.

[43] D. Renn, Caerphilly Castle, Cardiff, UK: Cadw., 2002.

[44] O. E. C. Prizeman, V. Sarhosis, A. M. D’Altri, C. J. Whitman and G. Muratore, “Modelling from the
past: The leaning Southwest tower of Caerphilly Castle 1539-2015,” in ISPRS Annals of

27

<!-- p. 29 -->

Photogrammetry, Remote Sensing and Spatial Information Sciences IV–2/W2 (August 16, 2017), Ottawa,
2017 doi:10.5194/isprs-annals-iv-2-w2-221-2017.

[45] J. Xu, L. Ding and P. E. Love, “Digital Reproduction of Historical Building Ornamental Components:
From 3D Scanning to 3D Printing,” Automation in Construction, vol. 76, p. 85–96, 2017
doi:10.1016/j.autcon.2017.01.010.

[46] M. Corsini, P. Cignoni and R. Scopigno., “Efficient and Flexible Sampling with Blue Noise Properties
of Triangular Meshes,” IEEE Transactions on Visualization and Computer Graphics, vol. 18, no. 6, p.
914–924, 2012 doi:10.1109/tvcg.2012.34.

[47] Y.-P. Huang, “Triangular Irregular Network Generation and Topographical Modeling,” Computers in
Industry, vol. 12, no. 3, p. 203–213, 1989 doi:10.1016/0166-3615(89)90067-5.

[48] M. Kazhdan, M. Bolitho and H. Hoppe, “Poisson Surface Reconstruction,” in Symposium on Geometry
Processing, 2006.

[49] Abaqus®. Theory manual, version 6.14, 2014.

[50] S. Fang and H. Chen, “Hardware Accelerated Voxelization,” Computers & Graphics, vol. 24, no. 3, p.
433–442, 2000 doi:10.1016/s0097-8493(00)00038-8.

[51] W. Jakob, M. Tarini, D. Panozzo and O. Sorkine-Hornung, “Instant field-aligned meshes,” ACM
Transactions on Graphics, vol. 34, no. 6, pp. 1-15, 2015 doi:10.1145/2816795.2818078.

[52] S. Gonizzi Barsanti and G. Guidi, “Geometric Processing Workflow for Transforming Reality- Based
3D Models in Volumetric Meshes Suitable for FEA,” in ISPRS - International Archives of the
Photogrammetry, Remote Sensing and Spatial Information Sciences, 2017 doi:10.5194/isprs-archives-
xlii-2-w3-331-2017.

[53] T. Apel and N. Düvelmeyer, “Transformation of Hexaedral Finite Element Meshes into Tetrahedral
Meshes According to Quality Criteria,” Computing, vol. 71, no. 4, p. 293–304, 2003
doi:10.1007/s00607-003-0031-5.

[54] P. Cignoni, M. Callieri, M. Corsini, M. Dellepiane, F. Ganovelli and G. Ranzuglia, “Meshlab: an open-
source mesh processing tool,” in Eurographics Italian Chapter Conference, 2008.

[55] G. Milani, P. Lourenço and A. Tralli, “Homogenised Limit Analysis of Masonry Walls, Part I: Failure
Surfaces,” Computers & Structures, vol. 84, no. 3-4, p. 166–180, 2006
doi:10.1016/j.compstruc.2005.09.005.

[56] G. Milani, P. Lourenço and A. Tralli, “Homogenised Limit Analysis of Masonry Walls, Part II: Structural
Examples,” Computers & Structures, vol. 84, no. 3-4, p. 181–195, 2006
doi:10.1016/j.compstruc.2005.09.004.

[57] K. Krabbenhoft, A. V. Lyamin, M. Hjiaj and S. W. Sloan, “A New Discontinuous Upper Bound Limit
Analysis Formulation,” International Journal for Numerical Methods in Engineering, vol. 63, no. 7, p.
1069–1088, 2005 doi:10.1002/nme.1314.

28

<!-- p. 30 -->

[58] S. Sloan and P. Kleeman, “Upper Bound Limit Analysis Using Discontinuous Velocity Fields,”
Computer Methods in Applied Mechanics and Engineering, vol. 127, no. 1-4, p. 293–314, 1995
doi:10.1016/0045-7825(95)00868-1.

[59] “Studio, IBM ILOG CPLEX Optimizer,” [Online]. Available: https://www-
01.ibm.com/software/commerce/optimization/cplex-optimizer/.

[60] G. Milani, S. Casolo, A. Naliato and A. Tralli, “Seismic assessment of a medieval masonry tower in
Northern Italy by limit, nonlinear static, and full dynamic analyses,” International Journal of
Architectural Heritage, vol. 6, no. 5, pp. 489-524, 2012 doi:10.1080/15583058.2011.588987.

[61] J. Lee and G. L. Fenves, “Plastic-Damage Model for Cyclic Loading of Concrete Structures,” Journal
of Engineering Mechanics, vol. 124, no. 8, p. 892–900, 1998 doi:10.1061/(asce)0733-
9399(1998)124:8(892).

[62] R. van der Pluijm, “Shear behaviour of bed joints,” in 6th North American Masonry Conference, 6-9
June 1993, Philadelphia, Pennysylvania, USA, 1993.

[63] G. Milani, M. Valente and C. Alessandri, “The Narthex of the Church of the Nativity in Bethlehem: A
Non-Linear Finite Element Approach to Predict the Structural Damage,” Computers & Structures, 2017
doi:10.1016/j.compstruc.2017.03.010.

[64] A. W. Page, “The biaxial compressive strength of brick masonry,” in Proceedings of the Institution of
Civil Engineers, 1981.

29
