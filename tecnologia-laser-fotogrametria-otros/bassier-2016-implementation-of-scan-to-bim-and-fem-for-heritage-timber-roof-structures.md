---
type: libro
title: "417736_1_En_7_Chapter 79..90"
author: ""
categoria: "Tecnología láser, fotogrametría, otros"
paginas: 12
extraccion: "texto"
fuente: "local:E:/Biblioteca digital/Tecnología láser, fotogrametría, otros/Bassier 2016 - Implementation of Scan-to-BIM and FEM for heritage timber roof structures.pdf"
convertido: 2026-10-14
---

# 417736_1_En_7_Chapter 79..90

> Texto extraído de `Tecnología láser, fotogrametría, otros/Bassier 2016 - Implementation of Scan-to-BIM and FEM for heritage timber roof structures.pdf` (12 páginas, texto). El PDF original está en el disco E: (Biblioteca digital); `<!-- p. N -->` marca el inicio de cada página.

<!-- p. 1 -->

Implementation of Scan-to-BIM and FEM
for the Documentation and Analysis
of Heritage Timber Roof Structures

Maarten Bassier1(&), George Hadjidemetriou1, Maarten Vergauwen1,
Nathalie Van Roy2, and Els Verstrynge2

1 Department of Civil Engineering, TC Construction – Geomatics, KU Leuven,
Leuven, Belgium
{maarten.bassier,maarten.vergauwen}@kuleuven.be,
georgios.hadjidemetriou@student.kuleuven.be
2 Building Materials and Building Technology Division, Department of Civil
Engineering, KU Leuven, Leuven, Belgium
{nathalie.vanroy,els.verstrynge}@kuleuven.be
http://www.kuleuven.be

Abstract. Current heritage analysis applications and documentation techniques
for timber roof structures rely on manual measurements to provide the spatial
data. Major simpliﬁcations are made to document these structures efﬁciently.
However, these simpliﬁed geometric models provide less reliable results.
Therefore, the need exists for more realistic models. Additionally, the
exchangeability of information between varying parties is paramount. Hence,
the construction elements should be deﬁned in a Building Information Model
(BIM). This allows users to reuse the model, allowing the distribution of
information throughout the project. The goal of our research is to create a
realistic BIM model of a complex heritage roof structure employing dense point
clouds. The comparison of our complex geometric model to a traditional
wire-frame model proves that our approach provides more reliable results in
terms of geometry and structural behaviour. Our work covers the acquisition, the
modelling and the structural analysis of timber roof structures.

Keywords: Cultural heritage BIM Structural analysis Modelling Timber
roof structures

1 Introduction

Built heritage is an integral part of our history and its conservation is important. To
preserve these assets, qualitative as well as quantitative information about the structure
is needed throughout the conservation process. The acquired data is used for the
documentation, analysis and exchange of the cultural heritage. Current heritage projects
are struggling with such data management. For instance, the spatial measurements of
heritage monuments prove problematic due to the complexity of these structures. This
is particularly true for timber roof structures. Subsequently, the metric data is used to

© Springer International Publishing AG 2016
M. Ioannides et al. (Eds.): EuroMed 2016, Part I, LNCS 10058, pp. 79–90, 2016.
DOI: 10.1007/978-3-319-48496-9_7

<!-- p. 2 -->

80 M. Bassier et al.

create geometric models. The quality of these models have a major impact on the
structural analysis of the structure. Less realistic geometry provide less accurate results.
Another major factor in the data management process is data homogeneity. The
information at consecutive stages of the process should be accessible by the varying
stakeholders. However, due to software incompatibility, the data exchange between
parties is ﬂawed or non-existent. As a result, specialists have to revisit the site and
reacquire the scene over and over again.
The goal of our research is to provide the heritage industry with a workﬂow that
will allow for more comprehensive documentation, the creation of more realistic
geometric models and the improvement of interoperability between parties. This paper
is organised as follows. Subsections 1.1, 1.2 and 1.3 give detailed information about
the state of the art of heritage documentation, analysis and data exchange. Section 2
elaborates on the methodology. Sections 3 and 4 respectively discuss the test design
and results. In Sect. 5, the conclusions are presented.

1.1 Data Acquisition

Traditionally, hand measurements and visual inspections are employed to document
cultural heritage. Such measurements, for instance, serve as a basis to create geometric
models used in structural analysis. However, the sparsity and inaccuracy of hand
measurements only allow for the creation of simplistic models. Denser and more
accurate data is required to create more realistic geometric models.
An increasingly popular data acquisition tool is Terrestrial Laser Scanning (TLS).
The static scanning instrument is capable of capturing accurate 3D point measurements
of an entire scene in a matter of minutes. The result is a geometric point cloud containing tens of millions of points with high accuracy. An example of a scanned roof
structure is shown in Fig. 1.
Terrestrial Laser Scanning and point cloud data have been used in several heritage
projects [1]. In addition to TLS data, photogrammetric point clouds are also used [2]. In
our research, we prefer to use TLS data over photogrammetric point clouds because of

Fig. 1. Overview heritage roof structure: image (left), point cloud (right).

<!-- p. 3 -->

Implementation of Scan-to-BIM and FEM 81

the size of the heritage site. Research indicates that Terrestrial Laser Scanning, while
being more expensive, scales better with the size of the project in terms of accuracy and
density [3].

1.2 Geometric Models for Structural Analysis

The analysis of the structural behaviour is crucial to the assessment and preservation of
built heritage [4]. The aim of this analysis is appropriate damage therapy and
strengthening measures. Currently, basic wire-frame models based on hand measurements are employed for the geometric representation. These simplistic models are error
prone and provide only a rough approximation of the real conditions. Therefore, the
analysis is less reliable.
Several researchers have proposed more complex geometric models. A promising
approach is the use of solid models [5]. Castellazzi presented such models based on
voxel elements [6]. Their semi-automated procedure has shown promising results
compared to traditional CAD-based models. Also constructive solid geometry
(CSG) has been considered [7]. They state that solid approaches are to be preferred
over wire-frame models for mass calculations and structural behaviour. In our research,
we also employ a volume based representation of the geometry. This allows for a more
realistic representation of the structural elements.

1.3 Data Exchange

Data heterogeneity is a major obstacle in the heritage industry. During a project, data is
stored in different software speciﬁc formats conform varying data models. The data is
not interoperable with other applications. To facilitate the data transfer throughout the
conservation process, the need exist for a uniform data model and an exchangeable
format. An innovative technology is Building Information Models (BIM). These
models constitute a digital representation of a structure with all its metric, non-metric
and semantic data. The data is stored in a format called Industry Foundation Classes
(IFC), an open standard for the exchange of BIM information between different software. In our research, we employ IFC to store the geometry of structural elements.
Research has been performed on the integration of BIM in the cultural heritage
industry [8–10]. In addition, heritage BIM library projects such as HBIM provide a set
of reusable heritage objects [11–13]. BIM has also been used as a basis for the
structural analysis of heritage buildings [14]. This ﬁeld is still ongoing research.

2 Methodology

In this paper we propose an approach to create realistic BIM objects of structural
elements based on point cloud data and apply these BIM objects as a base for structural
analysis. More speciﬁcally, we create a model for the evaluation of a heritage timber
roof structure. Our approach consists of two phases. The Scan to BIM phase covers the
data acquisition, modelling of the elements and their representation in a BIM

<!-- p. 4 -->

82 M. Bassier et al.

Fig. 2. Workﬂow for Scan-to-BIM and structural analysis.

environment. The structural analysis phase covers the exchange of the model to a
Structural Analysis software and the evaluation of the model’s behaviour. An overview
of the intermediate stages is depicted in Fig. 2. Our model is compared to a traditional
geometric wire-frame model, which functions as a benchmark.

2.1 Scan to BIM

For the data acquisition, we employ a static terrestrial laser scanner to acquire a dense
3D point cloud of the structure. Leica Cyclone is utilized to process the data. First,
cloud-to-cloud constraints are deﬁned for the coarse alignment of each scan. Subsequently, an Iterative Closest Point (ICP) Algorithm computes a ﬁne alignment between
the data sets.
After the registration, the uniﬁed point cloud is exported to 3D Reshaper for further
modelling (Fig. 3a). In this software, watertight meshes are computed for each element
based on the point cloud. The software employs a coarse to ﬁne meshing approach. The
coarse meshing computes a rough shape representation to acquire the initial shape. The
ﬁne meshing reﬁnes the initial geometry to better approximate the point cloud. Both
stages are an implementation of a Poisson meshing algorithm [15] (Fig. 3b). Second,
the mesh is interpolated to create a watertight mesh (Fig. 3c). Third, the mesh is
segmented per element and closed (Fig. 3d). For structural analysis, it is imperative that
the connections between elements are consistent so they are able to transfer forces
correctly. At this stage, the data is deﬁned by a non-parametric representation. While
this representation is adequate for simple evaluations, applications that interact with the
geometry prefer parametric data representations.
The closed meshes serve as a basis for the parametric reconstruction of the beams.
The objects are imported in the SolidWorks software (Fig. 4a). The built-in ScanTo3D
function allows for the semi-automated reverse engineering of closed meshes. This
function operates as follows. First, the mesh is represented by a set of surface patches to
approximate the exact geometry (Fig. 4b). The user can inﬂuence the settings of the
reconstruction algorithm to alter the level of detail. This has a direct impact on the

<!-- p. 5 -->

Implementation of Scan-to-BIM and FEM 83

Fig. 3. Overview stages of the modelling process in 3D Reshaper: point cloud (a), Poisson mesh (b),
watertight mesh (c), segmented mesh (d).

number of generated patches. Next, the user is able to adjust topological errors present
in the patch representation (Fig. 4c). Finally, the software calculates the parametric
volumetric representation of the given patches (Fig. 4d). After the modelling, the
objects are exported to the IFC 2 × 3 format, which is exchangeable with BIM software such as Revit.

2.2 Structural Analysis

A Finite Element Model (FEM) is deﬁned for the structural analysis. In addition to the
geometry, this model encompasses loads, material properties and joint deﬁnitions.
These parameters are derived from varying standards [16–20]. The Finite Element
Analysis (FEA) is performed in the ANSYS software. Quadratic triangular volume
elements are used to represent the geometry [21]. A 3D solid analysis method is chosen
to perform the evaluation. For comparison purposes, a wire-frame model of the roof
structure is created from manual measurements. The same method is employed to

Fig. 4. Overview stages of the modelling process in SolidWorks: triangulated mesh (a), surface
patches on normal LOD (b), surface patches on high LOD (c), solid parametric model (d).

<!-- p. 6 -->

84 M. Bassier et al.

deﬁne the FEM for this model. The wire-frame model will function as a reference in the
evaluation in Sect. 4.

3 Test Design

Our approach is evaluated using realistic conditions. The test site is a small castle
located in the city of Mechelen, Belgium. The structure is nearly 400 years old and is
heavily deteriorated [22]. The roof itself shows major deﬂections and damaged
structural members. The supporting elements consist of oak beams. The structure was
scanned employing a FARO Focus 3D X330. A total of 54 scans were acquired to map
the building, resulting in a point cloud of approximately 540 million points. The roof
itself was acquired with 16 scans. A scanning resolution of 12.5 mm/10 m was used to
ensure a high density point cloud of the beam elements [23].

3.1 Building Information Model

One section of the roof was modelled and 11 beams were isolated represented by 40
million points. The total beam length is approximately 26 m. After ﬁltering stray
points, the point cloud of the section was uniﬁed with an average spacing of 3 mm,
resulting in 6 million points or 230 thousand points per meter. The Poisson meshing in
3D Reshaper was performed using the two step meshing algorithm explained in
Sect. 2. A sampling size of 5 mm was applied for the meshing. A total of 1.2 million
triangular surfaces were constructed, approximately 40 thousand triangles per meter.
The meshes were manually segmented. For computational efﬁciency, the mesh complexity was reduced. A maximal deviation of 1 mm was allowed on the decimation,
resulting in 50 thousand triangles. An average deviation of 0.35 mm was computed for
the entire data set.
The meshes were reverse engineered to solid models employing the ScanTo3D
function in SolidWorks. On average, the elements were created with a 0.02 mm
deviation from the mesh model. The parametric objects were exported to IFC 2 × 3
without any loss of data. Within this model, additional non-metric properties can be
deﬁned by the user.
For the wire-frame model, hand measurements were acquired at the best suited
location for the accessible elements. For the inaccessible elements, total station measurements were used. Rectangular beams were employed to best approximate the
structural elements. Also, the elements are linear and are located in the same plane.

3.2 Structural FEM-Based Model

A structural analysis model is deﬁned for the evaluation. The varying parameters such
as material properties will be determined based on the European Standards. Both
geometric models will be evaluated with the same parameters.

<!-- p. 7 -->

Implementation of Scan-to-BIM and FEM 85

Material. Code-based values are assumed as a ﬁrst approximation since a detailed
assessment of the timber’s strength properties, e.g. by means of non-destructive
techniques (NDT) and minor-destructive testing (MDT), is not the focus of this paper.
Therefore, rheological phenomena in timber are currently not taken into account. The
material properties are derived from the EN 338 standard for the strength categorisation
of structural timber [16]. The roof elements are macroscopically identiﬁed as hardwood
oak with an assumed strength class of D30 and an orthotropic behaviour (Table 1).

Table 1. D30 properties from EN 338 [16]

General Strength properties [N/mm2] Stiffness properties [kN/mm2] Density
[kg/m3]
Material Class fm,k ft,0,k ft,90,k fc,0,k fc,90,k fv,k Em,0,mean Em,0,k Em,90,mean Gmean qk qmean
Hardwood D30 30 18 0.6 24 5.3 3.9 11 9.2 0.73 0.69 530 640
oak

The material properties are affected by the duration of the load and the moisture
content. Factor kmod is introduced to deal with these effects. In our test design, the roof
structure is assumed to be service class 2, which corresponds to an average working
temperature of 20° and a relative humidity more than 85 % for only a few weeks per
year [18]. The matching kmod is 0.6 and 0.9 for the permanent and short-term load
durations respectively. The reduced characteristic strength value Xd is calculated using
Eq. (1). γM is the partial factor for the material property which is 1.3 for solid timber.

Xk
Xd ¼ kmod ð1Þ
cM

Joints. Varying types of connections are present in the roof structure: mortise and
tenon joints, and dovetail half lapped joints. Both are constructed with wooden dowels.
While these connections can resist normal forces, they have limited rotational stiffness.
Therefore, the connections are designed as perfect hinges. The joints that connect the
roof to the building are modelled as ﬁxed joints. This decision is supported by ﬁeld
observations. Also, the use of perfect hinges simpliﬁes the calculations and overestimates the bending moment and deﬂections, resulting in a conservative analysis [24].
Loads. The different loads imposed on the roof structure are the self-weight, the
imposed loads, the wind loads and the snow loads. The self-weight is considered the
dead load of the structure. The permanent load consists of the roof frame (rafters and
battens) and the tiles. The imposed load is neglected because of the inaccessibility of
the roof.
For the snow and wind loads, the angle of the roof is required. From the laser scan
data is derived that the roof has an angle of 58°. The Eurocode EN 1991-1-3 [19]
speciﬁes that snow loads on such steep roofs can be neglected. For the wind load, only
the forces in the plane with the considered roof truss are considered. The wind pressure

<!-- p. 8 -->

86 M. Bassier et al.

is obtained using Eq. (2) [20]. qp is the peak velocity pressure, ze is the reference height
for the external pressure and Cpe is the coefﬁcient for the external pressure. Category III
best ﬁts the terrain category of the test site. The wind pressure on the strong side of the
section mounts up to 0.41 kN/m2. On the weak side a suction force of −0.51 kN/m2 is
calculated.

We ¼ qpðzeÞ Cpe ð2Þ

The roof is connected to the structural elements by purlins. Therefore, the varying
loads are represented by concentrated forces located perpendicular to the purlins at their
respective connections. Figure 5 shows the roofs connections in detail as well as the
location of the varying loads split into the vertical and horizontal components.

Fig. 5. Load model: the forces are transmitted from the rafters to the beams trough the purlins
(left). The wind load and the permanent load of the roof are depicted in red. The self weight of
the structural elements is shown in yellow (right). (Color ﬁgure online)

Structural Analysis. Both structural models are tested in the Serviceability Limit State
(SLS), which calculates the overall deformations of the structure [18]. It applies to
structures, components and connections with the assumption of a linear relationship
between the subjected actions and the corresponding deformations. The total deformation is calculated for the worst combination of the loads.

4 Experimental Results

The comparison between the two models is performed in two stages. First a metric
comparison is made. Second, a structural analysis comparison is made.
Geometry. To compare both geometric models, a million sample points are generated
on the surface of the models. The shortest euclidean distance between the two
geometries is calculated in the CloudCompare software. The results are shown in
Fig. 6. A mean distance of 20 mm with a standard deviation of 40 mm is calculated

<!-- p. 9 -->

Implementation of Scan-to-BIM and FEM 87

between both data sets. This results in a mean difference in proﬁle area of 15 % and in
volume of 12.5 %. These numbers indicate a major discrepancy between both data sets.
The complex model has more weight because the modelling in the wire-frame model is
based on the smallest section. The mass discrepancy both affects the load from self
weight and the structural behaviour of the beams. Figure 6 shows that the largest
deviations are located in the more complex areas. These differences are the result of the
abstractions made by hand measurements. Moreover, the wire-frame model does not
encompass geometries such as complex connections, non-rectangular and varying
sections, non-linear beams and out of the plane elements. The difference in geometry is
expected to have a major impact on the structural analysis.

Fig. 6. Overview metric comparison: the smallest euclidean distance between both data sets at
each location (left), and the histogram of the errors (right).

Structural Analysis. Both models are tested with the same material parameters and
external loads speciﬁed in Sect. 3. Figures 7 and 8 depict the results from the SLS
analysis. They show the deformations of the elements for the varying loads on the
structure. The discrepancy in deformation between the models is very noticeable. The
complex model shows deformations up to three times larger than the maximum
deformation in the wire-frame model. This is partially caused by a difference in weight
and section proﬁles, as well as the difference in modelling between the two structural
models. As stated in the geometry comparison, the complex model consists of
non-rectangular beams that connect to the joints in varying angels at different locations.
This causes forces to be transferred sub-optimal. Also, the location of the loads has a
major impact. In the complex model, the loads are placed more accurately, causing a
difference in stress concentration.
In addition to an increased stress in the beams, both models behave differently. For
instance, the main deformation is located elsewhere in both models. In the wire-frame
model it is located on in the left upper beam, while in the complex model it is located in
the right upper beam. This is caused by the behaviour of the central horizontal beam.
From Fig. 7 is derived that in the wire-frame model, the horizontal beam in the middle
of the structure is a crucial component to transfer forces from the right to the upper left
side of the structure. In the complex model, this is not the case. If the deformations are

<!-- p. 10 -->

88 M. Bassier et al.

Fig. 7. Deformation wire-frame model. Largest deformation located in upper left beam.

Fig. 8. Deformation complex model. Largest deformation located in upper right beam.

<!-- p. 11 -->

Implementation of Scan-to-BIM and FEM 89

compared to the deviations in the modelling (Fig. 6), it is revealed that this beam shows
the largest discrepancies. This is caused by a difference in modelling. In the wire-frame
model, this beam was modelled straight and ﬁtted between the vertical beams. In the
complex model, this beam is out of the section plane in accordance with the real
conditions. Hence, the beam cannot transfer forces as efﬁciently in the complex model.
As a result, the peak deformation is located elsewhere in both models (Fig. 8).

5 Conclusion

In this paper we presented a method to create realistic BIM objects of heritage roof
elements and subsequently apply the geometric model as input for structural modelling.
Instead of utilising traditional wire-frame models, we used more complex solid models.
By employing accurate dense point clouds, we were able to construct as-built models of
the structural elements of a building. The test results proved that with our approach,
volumes are estimated 12.5 % more accurately and proﬁle areas 15 % more accurately.
Furthermore, the complex solid model was able to encompass complex geometries
such as complex connections, non-rectangular and varying sections, non-linear beams
and out of the plane elements. The simulation results from the structural analysis
showed that these differences in geometry have a signiﬁcant impact on the structural
behaviour of the timber roof truss. Deformations up to three times larger than the value
of the maximum deformation in the wire-frame model were measured in the complex
models. These observations are crucial in the preservation process. Additionally, our
method provides a solution to deal with data heterogeneity. By creating BIM objects,
we allow the exchange of data between different software and stakeholders in the
heritage process.

Acknowledgement. The research group Geomatics of the Department of Civil Engineering, TC
Construction and the support of the Raymond Lemaire International Center for Conservation, KU
Leuven are gratefully acknowledged.

References

\1. Castagnetti, C., Bertacchini, E., Capra, A., Dubbini, M.: Terrestrial Laser Scanning for
Preserving Cultural Heritage: Analysis of Geometric Anomalies for Ancient Structures,
TS08C-Laser Scanners II, 6031 (2012)
\2. Arias, P., Armesto, J., Lorenzo, H., et al.: Digital photogrammetry, GPR and ﬁnite elements
in heritage documentation: geometry and structural damages. In: ISPRS Commission V
Symposium ‘Image Engineering and Vision Metrology’ DIGITAL (2012)
\3. Bassier, M., Yousefzadeh, M., Van Genechten, B.: Evaluation of data acquisition techniques
and workﬂows for scan to BIM. In: Proceedings of Geobussiness (2015)
\4. Van Roy, N., Verstrynge, E., Brosens, K., Van Balen, K.: Quality management of structural
repair of traditional timber roof structures. In: Structural Analysis of Historical Construc-
tions, Anamnesis, Diagnosis, Therapy, Controls (2016)

<!-- p. 12 -->

90 M. Bassier et al.

\5. Mngumi, E.A., Ruther, H.: Solid modeling for heritage documentation. In: Workshop –
Archaeological Surveys, WSA2 Modelling and Visualization (2004)
\6. Castellazzi, G., Altri, A.M.D., Bitelli, G., Selvaggi, I., Lambertini, A.: From laser scanning
to ﬁnite element analysis of complex buildings by using a semi-automatic procedure.
Sensors 15, 18360–18380 (2015)
\7. Son, H., Hwang, N., Kim, C., Kim, C.: Rapid and automated determination of rusted surface
areas of a steel bridge for robotic maintenance systems. Autom. Constr. 42, 13–24 (2014)
\8. Saygi, G., Agugiaro, G., Hamamcolu-Turan, M., Remondino, F.: Evaluation of GIS and
BIM roles for the information management of historical buildings. ISPRS Ann.
Photogramm. Remote Sens. Spat. Inf. Sci. 2, 283–288 (2013)
\9. Garagnani, S., Manferdini, M.: Parametric accuracy: building information modelingprocess
applied to the cultural heritage preservation. In: International Archives of the Photogram-
metry, Remote Sensing and Spatial Information Sciences, vol. XL-5/W1 (2013)
\10. Logothetis, S., Delinasiou, A., Stylianidis, E.: Building information modelling for cultural
heritage: a review. ISPRS Ann. Photogramm. Remote Sens. Spat. Inf. Sci. II-5/W3, 177
(2015)
\11. Murphy, M., McGovern, E., Pavia, S.: Historic building information modelling-adding
intelligence to laser and image based surveys of European classical architecture.
ISPRS J. Photogramm. Remote Sens. 76, 89–102 (2013)
\12. Dore, C., Murphy, M., McCarthy, S., Brechin, F., Casidy, C., Dirix, E.: Structural
simulations and conservation analysis-historic building information model (HBIM). ISPRS
Int. Arch. Photogramm. Remote Sens. Spat. Inf. Sci. XL-5/W4, 351–357 (2015)
\13. Oreni, D., Brumana, R., Della Torre, S., Banﬁ, F., Previtali, M.: Survey turned into HBIM:
the restoration and the work involved concerning the Basilica di Collemaggio after the
earthquake (L’Aquila). ISPRS Ann. Photogramm. Remote Sens. Spat. Inf. Sci. 5, 267–273
(2014)
\14. Barazzetti, L., Banﬁ, F., Brumana, R., Gusmeroli, G., Previtali, M., Schiantarelli, G.:
Cloud-to-BIM-to-FEM: structural simulation with accurate historic BIM from laser scans.
Simul. Model. Pract. Theor. 57, 71–87 (2015)
\15. Kazhdan, M., Bolitho, M., Hoppe, H.: Poisson surface reconstruction. ACM Trans. Graph.
32(3), 1–13 (2013)
\16. European Committee for Standardisation, EN 338: Structural timber-Strength classes (2016)
\17. European Committee for Standardisation, EN 1991-1-1: Eurocode 1: Actions on structures -
Part 1-1: General actions - Densities, self-weight, imposed loads for buildings (2002)
\18. European Committee for Standardisation, EN 1995-1-1: Eurocode 5: Design of timber
structures - Part 1-1: General - Common rules and rules for buildings (2014)
\19. European Committee for Standardisation, EN 1991-1-3: Eurocode 1: Actions on structures -
Part 1-3: General actions - Snow loads (2015)
\20. European Committee for Standardisation, EN 1991-1-4: Eurocode 1: Actions on structures -
Part 1-4: General actions - Wind actions (2005)
\21. ANSYS, Inc.: ANSYS Modeling and Meshing Guide (2005)
\22. Verstrynge, E., Kips, G.: Exploitation of 3D laser scanning data to generate FEM structural
models of historical timber roof structures (2016)
\23. Bassier, M., Vergauwen, M., Van Genechten, B.: Standalone terrestrial laser scanning for
Effciently capturing AEC buildings for as-built BIM. ISPRS Ann. Photogramm. Remote
Sens. Spatial. Inf. Sci. III-6, 49–55 (2016). doi:10.5194/isprs-annals-III-6-49-2016
\24. Branco, J., Varum, H.: Behaviour of Traditional Portuguese Timber Roof Structures (2006)
