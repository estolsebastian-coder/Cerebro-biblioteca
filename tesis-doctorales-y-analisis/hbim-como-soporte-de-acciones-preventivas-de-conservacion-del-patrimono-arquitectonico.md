---
type: libro
title: "HBIM as Support of Preventive Conservation Actions in Heritage Architecture. Experience of the Renaissance Quadrant Façade of the Cathedral of Seville"
author: "Roque Angulo-Fornos and Manuel Castellano-Román"
categoria: "Tesis doctorales y análisis"
paginas: 34
extraccion: "texto"
fuente: "local:E:/Biblioteca digital/Tesis doctorales y análisis/HBIM como soporte de acciones preventivas de conservación del patrimono arquitectónico.pdf"
convertido: 2026-10-13
---

# HBIM as Support of Preventive Conservation Actions in Heritage Architecture. Experience of the Renaissance Quadrant Façade of the Cathedral of Seville

> Texto extraído de `Tesis doctorales y análisis/HBIM como soporte de acciones preventivas de conservación del patrimono arquitectónico.pdf` (34 páginas, texto). El PDF original está en el disco E: (Biblioteca digital); `<!-- p. N -->` marca el inicio de cada página.

<!-- p. 1 -->

applied
sciences

Article
HBIM as Support of Preventive Conservation Actions
in Heritage Architecture. Experience of the
Renaissance Quadrant Façade of the Cathedral
of Seville

Roque Angulo-Fornos * and Manuel Castellano-Román

Department of Graphic and Architectural Expression, University of Seville, 41012 Seville, Spain; manuelcr@us.es
\* Correspondence: roqueaf@us.es

Received: 21 January 2020; Accepted: 30 March 2020; Published: 2 April 2020

Featured Application: HBIM models generation for managing heritage information, oriented to
preventive conservation of assets of cultural interest.

Abstract: This paper discusses the generation of Historic Building Information Models (HBIM)
for the management of heritage information aimed at the preventive conservation of assets of
cultural interest, through its experimentation in a speciﬁc case study: the façade of the Renaissance
quadrant of the Cathedral of Seville. Two methodological aspects are presented: On the one hand,
the process of modeling the solid entities that compose the digital model of the object of study, based
on the semi-automatic estimation of the generating surfaces of the main faces; on the other hand,
a methodological proposal for the modeling of information on the surface of the model. A series of
images and data tables are shown as a result of the application of these methods. These represent
the process of introducing information related to the current conservation status documentation
and recording the treatments included in the preventive conservation works recently developed
by a specialized company. The implementation of the digital model in the exposed work validates
it as a solvency option, provided from the infographic medium, when facing the need to contain,
manage and visualize all the information generated in preventive conservation actions on heritage
architecture, facilitating, in turn, cross-cutting relationships between the diﬀerent analysis that result
in a deeper knowledge of this type of building.

Keywords: information models; HBIM; preventive conservation; heritage architecture;
Seville Cathedral

\1. Introduction

This article discusses the generation of an Historic Building Information Model (HBIM) aimed at
the preventive conservation of the Renaissance quadrant façade of the Cathedral of Seville. The HBIM
model is designed to support knowledge, management and intervention actions on architectural
heritage, which are the bases of preventive conservation. Speciﬁcally, this work focuses on high
accuracy three-dimensional models integrating HBIM models. In this sense, this article develops a
number of methodological strategies which have produced interesting results. These strategies are the
evolution of the methods followed in previous works, such as those published in [1–6].
Within the general problem faced by the development of HBIM models (always referring to
knowledge, management and intervention in architectural heritage), this work focuses on the resolution
of two very speciﬁc aspects related to the intervention in heritage buildings. The ﬁrst is the need of
having an exhaustive graphic control of the current state of the building in order to adequately support

Appl. Sci. 2020, 10, 2428; doi:10.3390/app10072428 www.mdpi.com/journal/applsci

<!-- p. 2 -->

Appl. Sci. 2020, 10, 2428 2 of 34

any type of decision. Additionally, this aspect aﬀects the resolution of another pressing problem
in heritage documentation: duplicity and loss of information. Funds allocated for the acquisition
of graphic surveys are often associated with single intervention impulses. This information ends
up dispersed or misﬁled, avoiding its proper use in future conservation actions. The uniﬁcation of
all the information, including that related to accurate surveys, in a single container is essential. To
achieve this, the HBIM model must accurately present the reality of the building. In recent years,
many publications have made interesting contributions focused on solving the diﬃculties involved
in this problem. This research deals with an extensive state of the question related to this topic in
Section 2.1, referring to the transformation of the graphic information captured from the heritage object
(by laser scanner or photogrammetry) into HBIM models. In that sense, this work provides a novel
methodology in some aspects, such as the use of reverse engineering applications or innovation in the
modeling process of solid entities in CAD software that are later integrated in the HBIM model.
On the other hand, focusing the discourse on preventive conservation actions, HBIM models face
the need to register and systematize information related to various states of the heritage building.
It is necessary to record in detail the state of the building prior to any intervention on it, as well as
all the information related to the actions executed in those processes. In general, this is information
about building damages and the treatments used to eliminate or alleviate them, which are diﬃcult to
model in HBIM. Even more diﬃcult is the modeling of surface damages, such as humidity, erosion or
chemical transformations of the material.
Despite the great development of HBIM in recent years, few scientiﬁc contributions have focused
on these issues [7–11]. Two strategies can be recognized in them. The ﬁrst option involves the
subdivision of the model into multiple fragments to contain the information about the damages.
Conﬂicts emerge when the damages subdivision does not ﬁt with other subdivisions which attend
to historical chronology or constructive analysis. The second option is the overlay of surface entities
on the model which contain the information about the damages. This second option is usually
invalidated by the modeling diﬃculty in complex heritage buildings. To overcome those diﬃculties,
this research proposes an innovative solution: Modeling a new type of entity, which is easy to generate
and manipulate, and capable of containing the necessary information independently from solid entities
and over any type of geometry.
In reference to the case study, the graphic entities of the model have information adapted to the
work routine used by the company responsible for the preventive conservation of the facades of the
Cathedral of Seville. Thus, the work described and discussed in this research has consisted of modeling
a fragment of the façade of the Renaissance quadrant of the temple for the generation of an HBIM
model that allows the management of the information attached related to its preventive conservation.
Speciﬁcally, the work has focused on the façade section that adjoins the atrium of San Cristóbal, which
was restored in 2017. Once this work was completed, the results were considered by the members of
the conservation company team based on their feasibility, usefulness and relevance to be applied to
other future cases.

Case Study

The so-called Renaissance quadrant of the Cathedral of Seville is a set of spaces that house the
Sacristies and the Sacrum Senatum of its Chapter (Figure 1). Under the denomination of Sacristies,
the spaces dedicated to the preparation for the liturgy include: Oratory, Wardrobe, Lavatories, Treasure
rooms and Sacristans’ rooms [12]. In the case of the Sacrum Senatum, the Chapter Hall, Antecabildo,
accounting oﬃces, restrooms, courtyards and other auxiliary facilities [13] are included. This set is
the result of a long process of projects, reforms and transformations, hidden behind an imposing wall
that gives it the appearance of a unitary whole. Contained between this wall and the southeast façade
of the cathedral, a group of heterogeneous buildings were constructed, one after the other, until the
available space was ﬁlled. In turn, these constructions were progressively amortizing the old defensive
structures that separated the previous Mosque, and later the Gothic cathedral, from the Alcazar [14].

<!-- p. 3 -->

Appl. Sci. 2020, 10, 2428 3 of 34

The construction of this wall and the dependencies enclosed took place between 1528 and 1596, the year
in which the dome of the Chapter Hall was closed and the accounting oﬃces were built on the east
side of the temple. The construction started at the opposite end, on its west façade, after demolishing
the previous buildings and lifting the foundations of the complex [15]. Although not all the buildings
attached to the temple by its southeast façade were demolished, as part of the walls of the sacristy that
Alonso Rodríguez built after closing the dome in 1506 were taken advantage of, unﬁnished after the
unfortunate fall of that structure in 1511. These remains will be the starting point of the building of the
complex, which began with the elevation of the perimeter wall attached to the old sacristy and to the
south front of the cathedral’s transept.

Figure 1. Location and recent photograph of the object of study.

The project and construction of these Chapter facilities have been analyzed in detail in several
monographs, which show the great complexity of the process [13,16–24], resulting in the so-called
Renaissance quadrant or Chapter rooms, depending on the researchers. It has been widely recognized as
a masterpiece of the Hispanic Renaissance and has had an enormous inﬂuence on many buildings
promoted by the Archbishopric of Seville and in the rest of Andalusia [12,22,25]. Its architectonical
solutions were widely repeated, giving rise to the so-called Sevillian school or production center, of
great importance in the Hispanic scenario [21] (pp. 160–161), [26] (pp. 48–55), [27] (pp. 192–194).

\2. Materials and Methods

The research has developed the generation of a digital model of the case study and a database
linked to it. It also includes a working protocol which would enable a company responsible for
preventive conservation to dump data and to obtain reports and graphical visualizations. The essential
aspects of the workﬂow are common to the methodological script of previous experiences and can be
summarized as follows:

<!-- p. 4 -->

Appl. Sci. 2020, 10, 2428 4 of 34

\1. Georeferencing of the façade fragment as a part of the Cathedral. Deﬁnition of a spatial reference
system and a common vocabulary for this element.
\2. Photogrammetric survey of the façade fragment.
\3. Three-dimensional modeling of the façade fragment.
\4. Data structure required by the conservation company.
\5. Generation of the HBIM model.
\6. Data entry to graphic entities.
\7. Start-up and evaluation of results.
\8. Deﬁnition of systematized and standardized input and output information protocols.

Within this scheme, phases (3) and (5) include notable methodological developments regarding
previous experiences and in relation to the current landscape in this ﬁeld of research. This article aims
to focus on these developments through its detailed description throughout this text.

2.1. Three-Dimensional Modeling: Nature of Digital Capture Data and Its Transformation

The drawing generated from any type of digital capture, including the point cloud generated
by laser scanning or photogrammetric processing, should be preceded by prior knowledge of the
building through direct contact with it. Therefore, the prior, parallel and subsequent analysis that leads
to continuous object-drawing feedback is considered. Starting from this premise, the next step is to
describe the digital capture phase, the second point (after the proper georeferencing process) of the
architectural survey process following the methodological scheme described.
The ﬁnal objective of the survey will condition the general approach, which will be very diﬀerent
if it is only a ﬁrst approach to the building (for which the methods of direct survey would be perfectly
valid), or if it is a morphological and metric exhaustive knowledge (for which one would have to
resort to topographic or photogrammetric techniques). In any case, the characteristics of the object
(dimensions, formal complexity, conservation status, etc.) will also inﬂuence the strategy.
In this case it is assumed that the scope of the objectives set in this investigation necessarily implies
the generation of a three-dimensional digital model of the object of study. In addition, a maximum
strategy is chosen to support actions that are as general and transversal as possible in relation to
knowledge (in all possible aspects), building analysis and management. Therefore, the speciﬁc purpose
of the capture would be to exhaustively generate the necessary information to conﬁdently face the
integral three-dimensional modeling of the object. Exhaustiveness is understood as metric and formal
accuracy, and as a level of material complexity. That is, the model has to present geometric deformations
of the object that leave the possible theoretical design, whether due to structural damages or defective
execution processes, as well as formal and superﬁcial alterations due to the passage of time (such as
signiﬁcant material losses or stains due to moisture or atmospheric agents). Therefore, the information
captured should be the maximum that current methods allow us to obtain in relation to their geometric
and formal conﬁguration, as well as their physical attributes. This decision is justiﬁed by the need
that the resulting model can convey with solvency the development of described actions on objects of
high complexity, which is unattainable if it is not from transversality, rigor and accuracy. The model
should be accurate enough to allow graphics to be generated with the rigor and detail required by an
architectural heritage intervention project. These requirements are only achievable today starting from
massive capture techniques such as laser scanner or digital photogrammetry based on structure from
motion (SFM), whose results are three-dimensional clouds of points.
On the other hand, the need to solve the problems of duplication and loss of information
(so common in the ﬁeld of knowledge of heritage architecture), would invalidate any strategy that
implies the coexistence, without any link, of various models with diﬀerent levels of accuracy or
containers of diﬀerent plots of information. That is why it was decided to develop a single model of
information for each object of study, which does not prevent also including diﬀerent levels of detail or
information that produce diﬀerent graphic images or diﬀerent alphanumeric transfers.

<!-- p. 5 -->

Appl. Sci. 2020, 10, 2428 5 of 34

Once the capture method is ﬁnalized, it is necessary to consider the methodology for converting
the captured data into solid entities capable of generating information (morphological or geometric,
metric, physical and other), in addition to be able to contain information provided externally. A review
of this ﬁeld implies the consideration of various methods already deﬁned and classiﬁed in a primary
way by [28] in what it is called “as-built” building information modeling (BIM) approaches, or more
recently updated in [29] (pp. 394–396) through the deﬁnition of so-called grade of generation (GOG).
Following these references, it has been made a ﬁrst classiﬁcation based on the type of geometric
genesis of the graphic entities generated, distinguishing between “parametric” and “non-parametric”
generation methods. The ﬁrst can be deﬁned as those in which the genesis of the various entities that
make up the model responds to a series of operations that produces a three-dimensional geometry
controlled by a small number of parameters. The value of each of those parameters for each entity
suppose, in turn, the origin of the information provided by the model itself, and allow the variability
or edition of its geometry at any time. Depending on the degree of automatism used in the modeling
of the parametric entities, several parametric modeling methods have been deﬁned:

• Manual. It implies the manipulation of the captured data through classiﬁcation, hierarchical
organization and simpliﬁcation processes that allow obtaining the necessary references to proceed
with a manual modeling of these entities through the appropriate CAD or BIM software. It explains
a previous analysis for the simpliﬁcation of the starting data, since the complexity of the
graphic entities generated must be reduced in order to use the modeling tools oﬀered by such
programs. This implies rejecting certain irregularities, deformations or defects of the real elements.
This method is followed by most of the experiences in this ﬁeld carried out so far, among which
are [30–40], in addition to author’s works published in [1–3].
• Semi-automatic by NURBs. It consists of manual or automatic tracing, on the reference of the data
obtained by massive capture, of curves or surfaces based on the mathematical model non-uniform
rational B-Spline (NURBs). These, submitted to various manual manipulations, derive parametric
three-dimensional entities (if generated in CAD software) or parametric entities (if generated
directly in BIM software) capable of being part of the information model. In this case the number
of parameters used will be smaller, since much of the geometric control is subject to the NURB
curve or surface. This method cannot be exempt from the necessary previous reﬂection on the
possibilities of discretization of the entities generated. The work published in [3,41–45] follows
this procedure.
• Semi-automatic through parts. Method consisting of the generation of the shape from the
semi-automatic adaptation of the position and rotation of parametric graphic entities directly to
the point cloud for the modeling of complete construction systems from the pieces that make
them up [10,46].
• Automatic. It implies the fully automated generation of BIM parametric entities from the
implementation of a series of algorithms capable of segmenting, hierarchizing and recognizing
geometries in the captured data (usually dense point clouds). These mechanisms are still little
explored, limiting the experiments carried out based on simple geometries (based on plans)
typical of contemporary architecture of rational design [47–49]. There is research dedicated to the
development of methods that, based on the automatic processing of point clouds, are capable
of recognizing and describing more or less complex geometries (from straight lines to quadric
surfaces) using reverse engineering technologies [50–54]. These experiences, even outside the
ﬁeld of research that this work occupies, can be of great applicability in the development of
methodologies focused on both parametric and non-parametric modeling.

On the other hand, included in the group of non-parametric modeling can be those methods in
which the ﬁnal geometry of the resulting entities is not subject to the variability of a series of parameters.
These methods are focused to the generation of graphic models of great accuracy and formal similarity
to the real architectural object, formed by solid entities of geometry complex enough to be able to

<!-- p. 6 -->

Appl. Sci. 2020, 10, 2428 6 of 34

produce ﬁnal graphics of great accuracy and detail. Therefore, they are models lacking the necessary
simpliﬁcation that would involve the parameterization of their geometry, being able to represent
material and structural damages (of great utility in processes of intervention and maintenance). As in
the previous group, depending on the degree of automatism used in the modeling of the entities that
make up the model, several non-parametric modeling methods are deﬁned:

• Manual. It consists of the manipulation of the captured data through classiﬁcation and ranking
processes. It includes the intentional generation of curves and surfaces (adapted to the modeling
method), so that they allow obtaining the necessary references to proceed to a manual modeling
of the entities that make up the three-dimensional model, using the appropriate CAD software.
Subsequently, these entities (generally they must be solids or closed poly-surfaces) are imported
into the BIM platform for their treatment in matters of visualization and associated information.
It should be noted in this group the works [1,4,55].
• Semi-automatic. The procedure generally involves the conversion of a point cloud captured by
massive capture of data techniques into a triangle mesh, whose manipulation with the appropriate
software allows the modeling of CAD entities exportable to a BIM environment. This method is
used by works such as those published in [56,57].

Given the initial objectives set and the nature of the object of study, the latter method
(semi-automatic non-parametric modeling) was chosen for the experience developed on the west
façade of the Renaissance quadrant of the Cathedral of Seville. The results of its implementation are
set forth below.

2.2. Three-Dimensional Modeling: BIM Graphic Entity Management

BIM, in the ﬁeld of architecture analysis, could take the nuance (which Geographic Information
System (GIS) already has at urban and territorial level) of a tool capable of transferring classiﬁed or
ﬁltered information in the form of images that provide new visions or approaches able to inducing
new analysis and producing new knowledge. These would oﬀer new tools with which to translate
realities as complex as the temporary transformation of historical architecture, a challenge that is
always very diﬃcult to achieve with classical methods based on the isolated observation of diﬀerent
types of records and documents.
In that sense, at the practical level, the proposed methodology advocates the consideration of the
information model as a container of interrelated graphic entities in a hierarchical or systematized way,
capable in turn of producing and containing information linked to editable databases in non-graphic
environments. This consideration would make the development of the model viable in any platform,
software or set of digital applications that will guarantee the correct generation, manipulation and
visualization of said entities and their relationships. In general, in the academic ﬁeld, the choice of BIM
technology for this ﬁeld of research has to do with the maturity demonstrated in the application of
such requirements in the ﬁeld of the Architecture, Engineering and Construction Industry (AEC).
Conditions have been established at the beginning of this text that are summarized in formal
and metric precision of the entities that make up the HBIM model, and the integrity and rigor of the
information they support. Therefore, given the situation of having to choose a speciﬁc BIM software to
generate the model, it could be concluded that the ideal would be to work with one that allows more
ease when modeling, on the one hand, and when obtaining information (themed or alphanumeric
graph), on the other. The modeling of graphic entities in BIM commercial applications is based on
parameterization as a generation and control tool, which necessarily implies a certain geometric and
formal simpliﬁcation. This simpliﬁcation facilitates subsequent transformations linked to architectural
ideation processes that require the memorization of their traceability, but usually invalidates the use of
these parametric tools in accurate modeling of historical architecture due to their formal complexity.
However, in this type of architecture, the original construction elements will not undergo
signiﬁcant formal modiﬁcations due to decisions related to possible interventions. In the face of its

<!-- p. 7 -->

Appl. Sci. 2020, 10, 2428 7 of 34

modeling, the path followed to arrive at its geometry (or traceability) using a type of parametric
object designed speciﬁcally for a speciﬁc construction element (e.g., a wall, generally based on a
parametrized parallelepiped) is not relevant. Thus, the modeling of elements through the use of
generic, non-parametric solids, to which the appropriate category is subsequently associated, seems
like a perfectly viable and very adequate procedure based on the requirements.
This last statement leads to a methodological proposal that, although it is not new in its approach
(it has already been partially used in previous work [1,4]), has a greater potential for application in
this ﬁeld. That is thanks to the implementation of technologies such as reverse engineering, novel
in our ﬁeld of study, but widespread in other disciplines. Thus, it is proposed to make the modeling
process independent of the HBIM model creation and management process at the software level, where
the ﬁrst of these uses an application or group of applications that facilitates the transformation of
the data of any type of digital capture into three-dimensional entities complex enough to generate,
once imported into the BIM platform, an accurate and rigorous information model. In that sense, it is
necessary to point out that the purpose is to generate an HBIM model understood as a live drawing of
the building, continuously fed back with information about the object, but it will not be, in any case,
a substitution of reality; it will always be an abstraction based on the partial recording and capture of a
reality of undeniable complexity.

2.3. HBIM Model Structure

An essential aspect of the information model generation strategy is the way in which its components
or graphic entities are related. Decisions about the nature of these entities should be as equally important
as those that deﬁne their relationships and, therefore, the conﬁguration of the model structure.
Theoretical guidelines on models in general, and on conceptual models in particular, have
been followed. These are already rooted in the scientiﬁc ﬁeld and superbly synthesized by [58].
Thus, the proposed theoretical model, like any model in general, responds to three basic principles:
It represents a scope of reality, simpliﬁes it and allows us to reﬂect on that representation to obtain
conclusions that can be applied to the knowledge of that reality. This model is considered conceptual
since it is composed of the authors’ own concepts, products of their experience, or shared within
the research group. On the other hand, it responds to a process of simpliﬁcation of reality based on
the selection of those aspects that are considered relevant based on a speciﬁc intentionality towards
the ﬁeld of study and a previous experience acquired regarding the nature and value of the real
object. In a way, the structure of the conceptual model is describing the knowledge about reality
itself. The simpliﬁcation produced by the model facilitates its transmission or communication to other
receivers or agents involved by converting concepts into information.
This conversion or translation is done in this case by building information modeling (BIM),
moving from the theoretical conceptual model to a digital information model through proper coding.
Thus, in order for this conceptual model to carry out its mission, it is necessary that it initially complies
with two basic premises: That the reality it represents is discretized in diﬀerent entities, and that these
are categorized according to a certain intentionality within the area of knowledge to which our work
it is attached. Categorization is nothing other than the establishment of relationships between the
diﬀerent entities that make up the model. In this way, the proposed category scheme arises from
the very nature of architecture, adopting a stratigraphic structure composed of three main layers
or categories: spatial, liminal and material [3] (pp. 412–413). In that way, the scheme ranges from
the immateriality of spaces, containers of other objects (such as movable property) and carriers of
information related to functional, environmental and design aspects or genesis, to the material strata
that, generally composed of constructive elements, contain data on their materiality or information
about their timeline, obtained from historiographic and archaeological studies. This step is produced
through a very thin liminal layer that can contain any surface-type information, measurable or not,
such as that related to the state of preservation or the nature of the patina of the wall.

<!-- p. 8 -->

Appl. Sci. 2020, 10, 2428 8 of 34

Once the conceptual model has been deﬁned, its coding in an HBIM model necessarily involves
deﬁning a strategy that conveniently translates the deﬁnition of its entities and categories into the
organizational system or model structure on which the BIM software used is based.
In this case, for the work carried out in this area, the Autodesk®Revit®application was chosen
due to educational license accessibility, graphic versatility and general use in our geographical area.
As mentioned above, in general, any other BIM application would have successfully supported this
methodological process of translating the method into its speciﬁc tools. Due to time constraints and
operability, the process has been tested only in one commercial software package. This application
bases the organizational scheme of its workﬂow, and the structure of the information model itself,
on the establishment of two global groups of categories of families of entities with various utilities:
model categories and annotation categories. The ﬁrst encompasses all the components of the diﬀerent
construction systems and facilities that make up a building. Among these, the categories of space and
room stand out, as the only possible options for the immaterial stratum deﬁned in the conceptual model.
The insertion of all categories in the model is governed by a hierarchical system of relationships
that determines the way in which parameters intervene in the control of information and the geometric
and formal behavior of the model. Thus, each category is a container of a series of diversiﬁed families,
in turn, in one or several types, and each entity that forms the model or its structure of visualization
and documentation is an instance of one of those types. Then, in a BIM or HBIM model, one or more
copies of each type of family employed will coexist, so that the former will be governed by parameters
of instance, which condition or deﬁne properties of each entity individually, and the latter by parameters
of type, which condition or deﬁne properties of all copies belonging to the same type.
Additionally, the use of the model categories for the construction of the virtual building involves
the implementation of a powerful system of links between the diﬀerent entities that comprise it, so
that the so-called system families are usually hosts of the insertion families, establishing continuous
membership or reference relationships easily presented in thematic tables or views. The former, in
turn, are linked to specimens of family categories of geometric control and positioning, such as levels
and grids.
On the other hand, the general theory of systems (deeply embedded in our methodological
development) states that the characteristics of any system cannot be satisfactorily described through its
separate elements. This premise directly aﬀects the approach developed when coding the conceptual
model described above in the form of an HBIM model. A matrix system of relationships has been
proposed depending on the scale on which the problem is addressed (Figure 2). Starting from the urban
or territorial scale, managed by a GIS model (not developed in this work), it gives way to a ﬁrst level of
architectural scale called a federated model that, conveniently georeferenced, is a binder of partial
models deﬁned by characteristics related to historical, spatial or functional aspects. Both the federated
model and the partial models that constitute it are substantiated as projects in the BIM platform, and are
capable of sustaining complex information structures that, linked to knowledge and management
processes, can give rise to actions of eﬀective protection of the heritage they represent (in the line of
works previously developed [2,5]).
Each partial project of the building is constructed as a set of family type instances of those
categories provided by Revit®that best adapt, by their characteristics, to the systems that constitute
the reality of the object represented. In that sense, it is necessary to classify each of the constructive and
structural systems through an exhaustive taxonomy, which requires basing the work on a suﬃciently
broad lexicological knowledge of the architecture. The problem arises in the lack of contemporary
terminology of some elements between the categories of BIM software (whose genesis is directed to
contemporary architecture). That makes it necessary to include elements within generic categories or
create subcategories within existing ones for which to adapt the necessary family types.

<!-- p. 9 -->

Appl. Sci. 2020, 10, 2428 9 of 34

(a). (b). (c). (d).

Figure 2. Generic scheme of the matrix system of relationships of the HBIM model, focused on the
material stratum of the conceptual model. (a) Federated model. Building. (b) Partial model. Building
Sector. (c) Family instance. Sustaining Element. (d) Piece. Constructive element.

2.4. Information Structure

This section is presented at the end of this chapter on methods for reasons related to the clarity of
the speech. However, many of the aspects discussed in it should be addressed from the beginning
of the process, in the reﬂections aimed at specifying the method to follow in the generation of the
information model. In that sense, it is important to consider the information and its structure from the
beginning of the process, even though, as mentioned in previous sections, the information cannot yet be
considered as such, but as a set of concepts within the theoretical conceptual model. This consideration
will have a decisive inﬂuence on the decisions related to the structuring of the information model and
its relation to the database (or databases) to which it is linked.
The structure of the information associated with the model has been oriented towards its preventive
conservation. In this way, based on the available documentation and the information provided by
the company in charge of the preventive conservation of the façades of the cathedral, an information
structuring strategy in four main areas of work was prepared at the beginning of the process:
• Architectural elements and sectors. Conceptual identiﬁcation of the graphic entities of the model.
• Time factor. Processes. Conceptual identiﬁcation of links of a chronological nature.
• Injuries and treatments. Identiﬁcation of concepts related to preventive conservation associated
with model entities (information provided by the company).
• Database. Relationship structure of the database linked to the model.

The eﬀective introduction of the diﬀerent concepts of the information structure in the model
was carried out by creating custom parameters linked to them within the BIM software. These
parameters were included in a list called shared parameters registered in a text ﬁle that can be linked to
any other partial or federated project. The required parameters were assigned based on three levels of
development contained in the HBIM model, two based on the complete solid entity, on two levels of
detail, and another based on the exploded entities. These levels of development can be considered, for
the purposes of the patrimonial use of BIM, as Levels of Knowledge (LOK) [5] (pp. 6–7).
In this way, the entity constituted by complete volumetric models (instance of wall category)
has associated parameters that refer to the element as a whole: Identiﬁcation, basic patrimonial
information on stylistic ascription and principal authorship, legal protection ﬁgures that aﬀect it, record
of interventions and related dissemination actions. Regardless of its graphic detail (which has become
high level due to representation needs), it is assigned to a level of knowledge LOK300 according to
the classiﬁcation established in [5] (pp. 6–7). In the case of the exploded model of the façade, each
piece is an object of registration and, therefore, parameters related to a higher level of knowledge
can be associated. Each piece is assigned a unique identiﬁer and is characterized with identiﬁcation
parameters, injuries, treatments and actions. Therefore, it is ascribed to a level of knowledge LOK500
according to the classiﬁcation established in [5] (pp. 6–7).

<!-- p. 10 -->

Appl. Sci. 2020, 10, 2428 10 of 34

The values deﬁned in the previous paragraph refer to one LOK per item. Following the criteria
adopted by the working group, it is mandatory to assign a global LOK to both partial and federated
models. In this case, the level of knowledge assigned to the partial model that contains the façade
fragment is LOK200 based on the current development status. In the case of the federated temple
model, since the current level of development consists of a basic volumetric model with the only
insertion of a partial model (the one that concerns us in this experience), it is assigned to LOK100.

\3. Results

The results obtained from the application of the methods presented in the case study are
presented below.

3.1. Three-Dimensional Modeling

The workﬂow developed for three-dimensional modeling started from a massive capture of data
using photogrammetric techniques whose result consisted of a dense cloud of points. This contains
data of the points corresponding to their position, color and orientation (coordinates X, Y and Z, color
(RGB) and normal Nx, Ny and Nz). Some metric and quantitative details about the photogrammetric
survey are reported below:

• Number of control points (topographic survey): 8.
• Number of photographic shots: 150.
• Camera: Canon SLR camera, model EOS 1000D.
• Photogrammetric technique: SFM (Structure from Motion).
• Cloud size: 6,101,352 points.
• Maximum error on control points: 4 mm.
• Maximum residual per photo: 0.2 pix.

Subsequently, a work process was implemented based on the modeling method deﬁned as
non-parametric semiautomatic, as described in the Materials and Methods section, which was
developed in two main phases: surface and solid.

3.1.1. Surface Modeling

The treatment of the captured information was targeted at modeling by means of a set of vector
graphic entities (CAD planes or NURBs) of the shell that surrounds the material volume of the object
studied. For this purpose, which relies on software specialized in reverse engineering, in this work the
version 2016.1.0. of Geomagic Design X © (3D Systems, Inc.) was used.
In that software three diﬀerentiated processes were developed:

• Conversion of the point cloud into an optimized triangle mesh. This process is performed
automatically by the software based on the deﬁnition of a series of parameters related to the
overall size of the mesh and the increase or decrease in density in those areas where the shape of
the object so allows, in order to optimize the result (Figure 3).
• Segmentation of the meshed surface. Automatic process that, depending on variables related to
accuracy parameters, consists of the subdivision of the mesh into regions of recognizable basic
geometry (planes, spherical surfaces, conical surfaces, etc.) or generic (NURBs) (Figure 4).
• Manual conversion of regions into CAD surfaces and their edition by means of manual modiﬁcation
tools to formalize the joints (Figure 5).

<!-- p. 11 -->

Appl. Sci. 2020, 10, 2428 11 of 34

.

Figure 3. Partial view of the mesh surface obtained from photogrammetric point cloud. Mesh size:
1,771,241 triangles.

Figure 4. Partial view of mesh segmentation in regions of recognizable geometries. The low quality
of the mesh in areas of high formal complexity (such as decorative elements) due to the diﬃculties
mentioned in the survey process, have produced an excess of regions. This circumstance has not
prevented the implementation of the proposed modeling method for the surfaces that deﬁne the general
shape of the façade.

Figure 5. Exterior and interior views of the CAD model once edited.

This last step is crucial when establishing the level of accuracy or ﬁdelity of the ﬁnal model with
respect to the physical reality of the object treated. This aspect can be controlled by consulting the
deviations produced between the mesh and the resulting CAD model (Figure 6).

<!-- p. 12 -->

Appl. Sci. 2020, 10, 2428 12 of 34

Figure 6. Partial view of the veriﬁcation of deviations between the meshed surface and the CAD model.
The maximum geometric deviations with respect to the surfaces that deﬁne the general shape of the
façade do not exceed 0.005 m. As stated in the text, the decorative elements have been simpliﬁed and
have not been taken into account in the estimation of deviations.

The data collection used for photogrammetric capture was somewhat rugged because there
was still activity in restoration works, so that there was areas of very poor quality in the ﬁnal point
cloud. This circumstance did not prevent executing the process described successfully for most of
the object, extrapolating well-deﬁned geometries to those areas (quite small compared to the total)
lacking suﬃcient information. Since it was a pilot experience, the principal aim was to verify the
proper functioning of the method proposed in general, ruther to obtain rigorous results for the whole
three-dimensional model.
On the other hand, the reverse engineering software used is capable of generating complex
NURB surfaces adapted to the mesh in regions bounded by the user, making it possible to include
ﬁgurative elements in the surface model of the object (in this way the decorative medallions of the
panels were developed). In any case, since the generation of these types of surfaces required more
extensive processing times, it was necessary to make decisions regarding the formal complexity of the
resulting object to optimize the times and resources. In that sense, it was decided to make geometric
simpliﬁcations of certain elements, such as the capitals of the pilasters, the decorative elements of the
frieze or the ﬁgurative elements of the window that illuminates the Sacristía de los Cálices.

3.1.2. Solid Modeling

This modeling phase includes the conversion, by means of CAD editing processes, of the surface
composed in the previous phase into a set of three-dimensional graphic entities, of a solid nature,
exportable to a BIM environment. It was developed through the following process scheme:
• First, the CMD was transformed into a skin composed of multiple three-dimensional surfaces, of
controlled generation, by means of reverse engineering software (as explained in the previous
point).
• Second, the skin was used as a mold to generate a solid-type entity inheriting the exact geometry
and shape of the wall that limits the object of study. This process was performed in conventional
CAD software, speciﬁcally Autodesk®AutoCAD®(Figure 7). The choice of this software had to
do with two fundamental aspects: First, the graphic power that it makes available to the user; and
second, the perfect connection at the export–import level with the BIM software that would be
used for the creation and management of the information model. It is obvious that the selection
process of the BIM software was carried out previously, and that the speciﬁc purpose of many of
the processes followed and the decisions taken in this regard greatly inﬂuence the initial steps

<!-- p. 13 -->

Appl. Sci. 2020, 10, 2428 13 of 34

of the methodological proposal. However, it has been considered that the entire process would
be understood more clearly following a consistent timeline. On the other hand, the obligatory
time limit of this experience prevented the digital capture of the interior spaces that guaranteed
the same level of accuracy on the inside of the wall as on the outside. The interior surfaces were
drawn directly in CAD from the available graphic material (also in CAD format) of previous
topographic and photogrammetric surveys. These were used to model, in the form of additional
solids, a simpliﬁcation of the interior spaces based on the theorization of their trace. These would
be used to establish the necessary matter–space relationships in the BIM platform.
• From the generated solid, a duplicate was carried out without ﬁgurative elements and formal
conﬁgurations of certain complexity. It was necessary in order to guarantee the geometric base of
diﬀerent levels of detail within the BIM platform.
• Finally, the detailed solid was cut using as a trail the ortho-images obtained from the
photogrammetric capture (Figure 8). As previously discussed, the information model should
be a very varied container of information, from brief geometric measurements to the detailed
description of material and surface damages, through the location of stonework marks or the
realization of complex chronological assignments. In that sense, two options were considered
as the minimum unit of information of the model: the course or the ashlar. Both met a priori
with the information requirements raised, but the course was discarded; it would need additional
breaks when an element contained activities of diﬀerent chronology and whose interfaces did not
coincide with separation sores between stone courses.

Figure 7. CAD editing process. Simpliﬁed solid, reference ortho-image, exploded drawing in two
dimensions and its application to the ﬁnal exploded in three-dimensional solid entities.

<!-- p. 14 -->

Appl. Sci. 2020, 10, 2428 14 of 34

Figure 8. Graphic model of complete CAD solids.

The last process described involves implicit decisions of some importance in terms of knowledge
of the object being considered and its impact on the information structure of the model. In this speciﬁc
case, there were not enough records or documents to accurately deduce the thickness of the diﬀerent
layers that make up the structure of the façade and the existence of pieces arranged as keys that,
through the supposed inner layer, join the outer layers of stone. The lack of certainty in this type of
question, both geometric or formal and associated information, does not prevent the possibility of
modeling entities based on well-founded hypotheses. It is possible to assign them relative values
to various levels of knowledge (LOK) through created parameters speciﬁcally in the HBIM model,
and to wait until accurate information is available that allows its update. LOK can be applied in two
diﬀerent ways in the information model: As a concept of standardization that speciﬁes what minimum
information a model or part of a model must contain to be considered as assigned to a LOK [5] (pp.
6–7), or as an intrinsic parameter to all the constituent elements of the model whose value deﬁnes a
certain LOK of that element. In this case we refer to the second option.

<!-- p. 15 -->

Appl. Sci. 2020, 10, 2428 15 of 34

3.2. HBIM Model Generation

As mentioned, the deﬁning geometry of all the graphic entities that make up the model (model
categories) are introduced into the BIM platform by importing from the three-dimensional model
developed in CAD (as result of the process described in previous sections). The import process
necessarily includes the categorization of each entity within one of the categories available on the
platform. A relationship structure is formalized from the beginning. It properly encodes the structure
of the deﬁned conceptual model and satisﬁes the operational requirements of the model of information:
Visualization, thematization, ﬁltering, data management, dumping, etc. It is especially important to
control the way in which the software establishes the relationships between the diﬀerent elements
(belonging or link), which should be present in the external databases linked to the model.
Focusing the problem on the object of study, it is decided to include the entities imported from
the CAD within a family unit of wall category that, generated as model in-place component, will be
the cohesive element of most of the functions related to the visualization and management of that
part of the model. This wall instance is part of the project that will comprise, together with other
partial models, the federated model of the temple. The composition of the specimen is based on the
superposition of the diﬀerent solids imported separately according to their level of detail, which allows,
using a single object, the generation of visualizations at diﬀerent representation scales. This also
implies diﬀerent possibilities in terms of the amount or depth of the information entered. In this way,
each imported solid becomes a part associated with one of the following three levels of detail:

• Low level of detail (Figure 9). It is made up of the complete solid of the wall fragment without
ﬁgurative elements. It allows the generation of graphic documentation at the scale of representation
that can be assimilated to a basic design for a new plant architecture (1/200 to 1/100). It faithfully
reproduces the geometric and formal conﬁguration of the element, the result of the exhaustive
modeling process described above. A sectional view of this element is presented as a single solid
entity, without discrimination of its material layers or real separate pieces.

Figure 9. Instance of wall displayed at low level of detail.

• Medium level of detail (Figure 10). Composed of the complete solid of the fragment including
ﬁgurative elements. It responds to the same characteristics of the previous level, with more
information at the graphic level. It allows the generation of graphic documentation on a scale of
representation that can be assimilated to a basic project for a new plant architecture (1/100).

<!-- p. 16 -->

Appl. Sci. 2020, 10, 2428 16 of 34

Figure 10. Instance of wall displayed at medium level of detail.

• High level of detail (Figure 11). Composed of the set of solids resulting from the ﬁnal cutting
developed in the modeling process. It allows the generation of graphic documentation at the scale
of representation comparable to a new plant architecture execution project (1/50 to 1/20), reaching
from general projections of the object to construction details. In addition to faithfully reproducing
the geometric and formal conﬁguration of the element, it also includes the representation of the
actual parts corresponding to the diﬀerent strata that make up the wall.

Figure 11. Instance of wall displayed in high detail.

<!-- p. 17 -->

Appl. Sci. 2020, 10, 2428 17 of 34

These levels of detail are predeﬁned in the BIM platform, so that it is possible to switch their
display in any generated view of the model. The classiﬁcation of imported solids at these levels is
carried out by modifying their display properties within the family unit. Additionally, due to control
needs of object selection, they are also classiﬁed by inclusion in custom subcategories (in this case
within the wall category). The subcategory allows the subsequent selection of elements in a simple way
for actions related to editing or information adding, overcoming the diﬃculties of having diﬀerent
graphic entities sharing the same location.
An additional level of control allows the switching of any view from showing original to showing
parts, which gives rise to the possibility of independently selecting each three-dimensional solid
included in the family unit (Figure 12). This capacity is derived from the options for grouping instances
provided. They include the concept of assembly, whose function is to enable the grouping into a single
entity of diverse elements with objectives related to information planning and advanced visualization
of details of construction systems. The possibility of selecting pieces individually guarantees the
introduction of detailed information to the minimum unit of discretization of the model, related to
any ﬁeld of knowledge or discipline. The information is entered by creating custom attributes (called
parameters) that are associated with all entities belonging to one or more categories, allowing the
subsequent edition of their values in a particular way, depending on the selection of objects done.

Figure 12. Instance of wall visualized at high level of detail with individual piece selection and detail.

The information associated with the individual piece will necessarily be uniform in relation to the
real object it represents (in this case, stone ashlar or building unit of ceramic or heterogeneous material),
that is, the information related to its identiﬁcation, linking or association, materiality, chronology,
material or structural damages, etc. This condition prevents the association of information regarding
aspects of a superﬁcial nature such as surface damages (humidity, deposits, alterations, material losses,
etc.) or characterizations related to the patina of any face. The inclusion of these aspects in the process
is key to the achievement of the initially set objectives, among which is the use of the model in actions
linked to the conservation and management of heritage.
In that sense, at the beginning of researching works, the possibility of modeling a very thin layer
into the stratiﬁed structure of the conceptual model was considered. Its coding in the HBIM model

<!-- p. 18 -->

Appl. Sci. 2020, 10, 2428 18 of 34

would imply that each construction element would be linked to two thin external layers: One of ﬁnishing
(with all the necessary subdivisions depending on its material and temporal nature) and another
tessellated in pieces of 5×5 cm. that would house all the information related to the state of conservation
of the constructive element. The material nature of the element would condition the existence or not
of the ﬁnishing layer. Each tile of the second layer would have associated several parameters related
to information of various kinds that would allow a subsequent visualization in conjunction with the
element, as well as the quantiﬁcation of its associated values. Materialization experiments of this method
were carried out in partial models on various BIM platforms. In Autodesk®AutoCAD®Architecture®,
the manual modeling of the tiles was proposed using large subdivided surfaces of AEC polygons type,
capable of containing information and linking or containing other objects. This method proved not
to be operative for objects of a certain formal complexity, since modeling was greatly complicated in
its application to certain decorative or ﬁgurative elements. In an attempt to solve these limitations,
we experimented with the generation of the tessellated thin layer automatically, by subdividing the
outer surface of each architectural space (including the bounded outer space) with a meshing software
and its subsequent extrusion to solid in CAD or directly in the BIM environment. This last method
remained very limited in sectors of high formal complexity, where the miscellany of triangles of the
meshed surface prevented its extrusion. Even so, it was introduced in some of the works developed,
such as the one published in [3] (p. 416), applied to walls of a certain geometric simplicity.
The experience in the Renaissance quadrant has allowed the application of an evolution of these
methods through the consideration of the thin layer as a set of elements simpler than the tiles. They are
entities that, assimilated to points located in the center of the cells of a grid adapted to the model, could
contain information and be linked to the parts or to the complete element that brings them together.
There are scientiﬁc contributions that follow this line, but with limited operability in the ﬁeld of heritage
architecture, based directly on clouds of points separated from BIM information models, such as [59].
The formalization of these entities in BIM software has been carried out by modeling what have been
called surface information points (SIP), consisting of family instances without speciﬁc categorization
(generic models). Initially modeled as a simple point, its diﬃcult visualization located on the surface of
three-dimensional entities led us to replace them with a set of three vectors of variable length that are
cut in the shape of a star (Figure 13a). The parameterization of vector lengths allowed the adequate
visualization of the SIP at diﬀerent scales (Figure 13b). Their status as a family instance guarantees the
association of information parameters relative to the areas of knowledge already described.

(a) (b)

Figure 13. (a) Surface Information Points (SIP). Graphic description of parameterized family. (b) SIP
distribution detail on the surface of the model entities.

<!-- p. 19 -->

Appl. Sci. 2020, 10, 2428 19 of 34

The distribution of SIPs on the external surfaces of the wall was carried out by means of the
execution of an algorithm programmed in Dynamo®. This is a graphical edition of algorithmic
software linked to BIM software, already used in previous works such as [3,4]. This plugin allows the
advanced treatment of the information contained in the model, both graphically and alphanumeric,
through graphic programming routines based on the Python language. In this case, the algorithm
developed consisted of two main actions:

• Automatic generation of a regular distributed cloud of points on the outer surfaces of the complete
solid that forms the fragment of the treated wall (Figure 14). In this case, a regular 5×5 cm grid
was chosen.
• Automatic insertion of an instance of the SIP family in each of the constituent points of the
previous cloud (Figure 15).

Figure 14. Workspace in Dynamo®: Location point cloud and SIP instance insert script.

<!-- p. 20 -->

Appl. Sci. 2020, 10, 2428 20 of 34

Figure 15. SIPs over the entire surface of the façade fragment.

The treatment at a level of visualization and management of the inserted SIPs responds to the
same operation as that used for any of the instances of the elements that make up the model, in such a
way that the various values introduced in the associated parameters, as well as linking to other entities,
allow, as will be seen later, the realization of alphanumeric queries or thematic visualizations through
the adequate ﬁltering of information.
The partial project of the sector studied is completed with the necessary entities to properly
contextualize the façade fragment and allow an adequate testing of the methodology followed. For this,
the following elements are conveniently imported and categorized:

• Internal scope of the treated sector, corresponding to the Sacristía de los Cálices and the Patio
de los Óleos, and its annexed dependencies. It was treated as a single element of a low detail
(developable in the future) container of constructive and spatial elements of varied nature, so it
has been introduced as a single family unit of the generic model category. In any case, the entities
that comprise it have been classiﬁed through material and spatial subcategories that take up the
stratiﬁed structure of the conceptual model, and allow the representation of spaces to be isolated,
enabling architectural rigor of a certain complexity (Figure 16).
• South façade section, treated as a wall category specimen at a low and medium level of detail.
• Exterior pavement, treated as a soil category specimen at a low and medium level of detail.
• Exempt columns located in the San Cristóbal Atrium, treated as pillar specimens at a low and
medium level of detail.

On the other hand, it is noteworthy as an assessment of the partial objective achieved that an
adequate structuring and ranking of the diﬀerent entities allows the generation of high-accuracy
graphic images based on rigorous coding (Figure 17). This result is obtained without the need to
use advanced editing tools or the use of any type of additional software. In the following sections
the treatment of these images will be addressed by ﬁltering based on the information contained in
the model.

<!-- p. 21 -->

Appl. Sci. 2020, 10, 2428 21 of 34

Figure 16. Complete model of partial project. View from northeast without interior material layer.

Figure 17. Partial view of the elevation, horizontal section and vertical section projections of the model.
Direct dump from Building Information Modeling (BIM) software. The deformation of the horizontal
entablature and the balustrade line can be observed by comparing it with the auxiliary straight line
(dashed blue).

<!-- p. 22 -->

Appl. Sci. 2020, 10, 2428 22 of 34

3.3. Management Information: Treatment and Consultation

The management properties conferred automatically to each element, as well as the assignment of
the parameters to the diﬀerent entities that make up the model based on their category and the system
of relationships implemented, represent the qualitative leap from a simple three-dimensional graphic
model (developed in any digital drawing software or CAD) to a true information model (BIM or HBIM
in this case) capable of oﬀering all the advantages of a graphic database. Thus, once a value have been
assigned to each parameter for each entity, based on the previously systematized information, it is
possible to request information from the system. This information can consist of queries, information
ﬁltering or conditional searches, in the form of themed graphics (Figures 18 and 19) or alphanumeric
listings, which oﬀer us new starting points when facing various types of analysis. It is also possible to
request updated information, in real time, on certain aspects of the reality of the object being treated
that allow decisions regarding its conservation or management (Figures 20 and 21).

Figure 18. Graphic visualization of materials by ﬁltering “material” parameter assigned to the parts
that comprise the model.

<!-- p. 23 -->

Appl. Sci. 2020, 10, 2428 23 of 34

Figure 19. Graphical display of chronological information by ﬁltering “phase ID” parameter assigned
to the parts that comprise the model. Additionally, each piece is assigned to a construction phase within
the BIM software project, which allows the visibility of each element to be determined according to its
temporary location in relation to the phase assigned to the current view. In this way, it is possible to
control graphically interventions of recessing and replacement of masonry pieces by hiding exploded
conﬁgurations of phases prior to that currently displayed.

<!-- p. 24 -->

Appl. Sci. 2020, 10, 2428 24 of 34

Figure 20. View of the medium detail model including thematic visualization of SIPs by ﬁltering
the parameter corresponding to “biological colonization” in relation to the conservation status prior
to intervention.

Figure 21. View of the medium detail model including thematic visualization of SIPs by ﬁltering the
parameters corresponding to “dirt” (red) and “black crust” (blue), of the material contribution group of
alteration product, in relation to the state of conservation prior to intervention.

<!-- p. 25 -->

Appl. Sci. 2020, 10, 2428 25 of 34

In that sense, the implementation of surface information management through SIPs allows
graphic and quantitative control of relevant data in the ﬁeld of preventive conservation, allowing
consultations on the HBIM model in the form of tables of numerical data. Thus, in the speciﬁc case at
hand, the inclusion of SIPs in a 5×5 cm controlled grid allows the generation of schedule tables with
computation of areas related to certain existing damages or executed treatments. These tables can in
turn be ﬁltered according to parameters related to chronological phases (dates of speciﬁc interventions,
drafting reports on damages status, etc.) or to speciﬁc areas of the model based on identiﬁcation or
membership attributes.
On the other hand, ﬁltered info graphics or thematic graphic queries can be conﬁgured in
combination with conﬁguration tools of the views in which they are represented. In this way,
the intentional visualization from certain points of view (if there are considered axonometric or conical
perspectives) or using dihedral projections allow the contemplation of the relationships between
elements and their associated information from new approaches diﬃcult to reach without using this
tool. The combination of several themed projections from the “phase ID” parameter of the Renaissance
façade model allows certain deformations in the execution of some bodies to be directly related to
speciﬁc construction phases recorded from the information collected and turned into the model itself
(Figure 22).

Figure 22. Partial view of the elevation, horizontal section and vertical section projections of the model.
Direct transfer from BIM software with thematic ﬁltering by “phase ID” parameter.

Regarding the treatment, management and consultation of the model and its contained information,
it is inevitable to talk about the qualiﬁcation of the agents involved in these processes. The development
of an HBIM model with a view to its eﬀective exploitation in the ﬁeld of conservation, intervention and
management of heritage architecture entails (in addition to the work already described) its loading and

<!-- p. 26 -->

Appl. Sci. 2020, 10, 2428 26 of 34

implementation within the institution or entity responsible for such activities. The implementation of
training courses in the use and application of that methodology and its tools is necessary in most cases.
Editing the information model in the BIM platform requires a high technical qualiﬁcation, not only
in relation to the tool management itself, but also to the knowledge in the ﬁeld of architecture and related
knowledge areas. However, the conception of this methodology is focused on the implementation
of the HBIM model as administrator of all the information ﬂows necessary for the correct execution
of the actions related to knowledge, conservation, intervention and building management. These
are currently governed by multidisciplinary groups of agents belonging to multiple branches of
knowledge, and not always endowed with that technical qualiﬁcation. It is therefore unavoidable
to approach from this methodological proposal a procedural strategy that is able to withstand the
performance of any type of agent with minimum qualiﬁcation of transversal type. This can be achieved
through the inclusion of generic tools for management, consultation and visualization of data in the
aforementioned processes.
It is proposed to link the information in the graphic model to an external database that allows
editing outside the BIM environment. This database is updated in real time from modiﬁcations in the
model by automatically executing one or more scripts (programmed by graphic editions of algorithms).
The same scripts would trigger the ﬂow of information in the opposite direction, leading to the updating
of the model based on the changes implemented in the database. This ensures, in turn, the dump of
all graphic-based queries or themed images pre-conﬁgured in the BIM environment in the form of
graphic documents (two- or three-dimensional) of universal format. Thus, technicians responsible for
preventive conservation of the studied element do not require speciﬁc knowledge about BIM modeling
software for the consultation or modiﬁcation of information contained in the model. They simply need
basic training to interact with tables and forms previously conﬁgured in the database, and to consult
two-dimensional graphic documents dumped in PDF format or three-dimensional graphics dumped
in Industry Foundation Classes (IFC) format. The latter graphics document format is operable at the
visualization level in any free viewer available on the Network, enabling the consultation of the model
through information ﬁltering and visibility modiﬁcations of the diﬀerent entities that compose it.
Therefore, the HBIM workﬂow is composed of the following elements:

• Graphic model itself produced in the BIM editing platform.
• Information associated with model parameters.
• Linked databases for information management.
• Associated documents collected in document registration processes or transferred from the model
itself in successive updates. These documents are constituted as a documentary repository parallel
to the HBIM model, which will be fed by the research and conservation actions that occur on the
element studied.

As an illustrative example of this strategy, the approach developed for the treatment of the
information hosted in the Renaissance façade model started from the initial assignment of a unique
identiﬁer to each constructive element of the model and the pieces that make it up. For constructive
elements, this identiﬁer consists of an alphanumeric code composed of the spatial coordinates derived
from the position of each constructive element within the structure of alignments of structural planes
identiﬁed in the conceptual model (Figure 23). The identiﬁer is controlled using the custom shared
“ID” parameter. Thus, the element of category wall that represents the enclosure of the Capilla de los
Cálices is identiﬁed as “G-8-11”. For the pieces that comprise it, the identiﬁer is the result of adding a
four-digit number to the identiﬁer of the construction element to which they belong. The generation of
that number was done automatically by programming in Dynamo®a script that performs the complete
task of composing the identiﬁer and assigning it to each of the parts of the model (Figure 24).

<!-- p. 27 -->

Appl. Sci. 2020, 10, 2428 27 of 34

Figure 23. Plan view of the temple with identiﬁcation grids of structural planes alignments. Field
of study.

Figure 24. Partial view of Dynamo®script for the automatic assignment of the “ID” parameter to
model parts.

Once all the entities have been identiﬁed and the classiﬁed information entered through parameters
(according to previous sections), it is possible to generate planning tables that ﬁlter and classify the data
according to any of the parameters involved or any of the relationship conditions between elements
implemented in the model. The dump of these tables in Excel or Access format allows their subsequent
treatment externally and the generation of a link with the model through the corresponding scripts
mentioned above.
This workﬂow allows an unqualiﬁed agent for the BIM environment to operate in the database in
order to update the information contained in the model (for example, the values of parameters related
to preventive conservation actions, such as severity of damages or treatments applied). The automatic
execution of the script coded for transferring information between database and graphic model
guarantees not only the updating of that information in the model but also the updating of all graphic
and alphanumeric dumps in the form of associated documents. That same agent can visualize and

<!-- p. 28 -->

Appl. Sci. 2020, 10, 2428 28 of 34

verify the result of the modiﬁcations made in the associated documents, which automatically become
part of the documentary repository of the HBIM workﬂow. Additionally, it is possible to implement
commands in the scripts that allow visual location (in real time) of the graphic entity linked to a
particular database registration line (Figure 25).

Figure 25. Overview of the HBIM workﬂow with a part selection. From top to bottom: Information
model in BIM Revit®platform, information transfer script between database and model, and vice versa
(in the background), visualization of transferred model in Industry Foundation Classes (IFC) format in
free BIMVision®viewer, and database in Microsoft®Access®.

\4. Discussion

4.1. In Reference to the Survey or Digital Capture Phase

It is necessary to make some points about this phase of the work. The decision to opt for a
technique of massive capture of data is widely justiﬁed at the beginning of Section 2.1. Among the

<!-- p. 29 -->

Appl. Sci. 2020, 10, 2428 29 of 34

available techniques (laser scanner and photogrammetry), photogrammetry is chosen due to economic
and equipment accessibility issues. Many publications have already addressed the comparative study
between both methods of capture, and it is not the objective of this research. The main interest is
the general methodology of transformation of the data captured in an HBIM model with a very
speciﬁc objective.
For the realization of the capture by digital photogrammetry, the usual methodology has been
followed regarding the type of photographic shots, its processing in the appropriate software and the
convenient topographic support by means of the correct orientation and scaling of the resulting point
cloud. It was not an easy job, and the results were not highly accurate because, at the time of the data
collection, work was being undertaken on the restoration of the façade. In any case, the results were
satisfactory and suﬃcient for the objective sought.

4.2. In Reference to Three-Dimensional Modeling

In future development of the model described here, as well as in models developed in future
projects, in addition to deepening the level of knowledge of the entities that already comprise it, it will
be crucial to consider that the model should not only be the reﬂection of its current physical reality
(material and documentary). It must also be a container of all those elements that are hidden or lost
today (from archaeological excavations, documentary ﬁndings, etc.). These provide a diachronic
reading of the building, inﬂuencing the possibility of performing analyzes from points of view
impossible to achieve without the use of these models.
On the other hand, in reference to the modeling process, this work assumes from the beginning the
objective of proposing and applying a method that guarantees the least possible deviation between the
real object and the HBIM model. This objective implies supporting the process in reverse engineering
tools that allow generating surfaces of any nature adapted to the irregular geometry that characterizes
historical buildings such as the case study (irregularity due to defective execution processes, structural
deformations, or other factors).
Thus, the proposal deviates from modeling methods classiﬁed in the research as semi-automatic
parametric using NURBs, considered the most accurate in many of the publications of recent years.
These methods involve theorization or rationalization of the proﬁles and trajectories extracted from the
point cloud, omitting possible variations due to poor execution or decision changes occurred during
the construction of the building, or even due to subsequent structural damages. These variations can
be unavoidable clues for analyzes as important as the original trace of its elements, the transformation
of the building along its history or its structural state. That is why this work proposes a semi-automatic
non-parametric method: Generate the solid entities that make up the model from the ﬁlling of the
space between the two “shells” (interior and exterior) that conﬁne the material elements of the building.
These shells are the result of precise conversion on NURBs surfaces (or on planes or quadrics in possible
cases) of segmented regions of the cloud using reverse engineering tools.
The experience described in the research is a pioneer in the application of this method, and has
allowed the veriﬁcation of its applicability and possible ways of improvement. In this sense, it can be
aﬃrmed that the whole process depends on a capture of high quality data and precise segmentation of
these in the line of work already referred to in Section 2.1 as [49,54].

4.3. In Reference to the Structure of the HBIM Model

As stated in the corresponding section, the structure of the model is subject to decisions on the
nature of the entities that comprise it and on the deﬁnition of their relationships. These decisions would
be endowed with great freedom if the process were to be carried out with a set of open source software
applications (a perfectly valid option, and very interesting for future lines of progress). However,
if commercial applications are chosen, it is necessary to carry out a prior adaptation process: The
conceptual model initially proposed at the theoretical level must be translated into the systematization
and hierarchy of entities and relationships established in the internal software code. This adaptation

<!-- p. 30 -->

Appl. Sci. 2020, 10, 2428 30 of 34

process will be diﬀerent depending on the BIM platform chosen, but it is considered that it is achievable
in any of the currently available platforms, regardless of the initial theoretical model. Thus, the eﬀort
to be used in adaptation will become one of the main variables that would be combined to make a
suitable choice of software.
For the generation of the HBIM model described in this research, a speciﬁc commercial BIM
software was used. It was not been possible to reproduce the methodology proposed in other
commercial software due to time issues. That work is pending for future projects. The successful
translation of the initial theoretical model into the object structure of BIM application is based on
aspects related to categorization of objects and their visualization based on information ﬁltering. These
aspects are developed in all BIM software due to the very nature of this technology. Therefore, although
there are variations in the implementation of such aspects in diﬀerent software, it can be said that the
proposed methodology is transferable to any commercial BIM application.
In another order of things, the authors of this work defend the statement that preventive
conservation should include complete buildings and not just a part. The general methodological
proposal of the authors on the application of BIM in heritage architecture includes not only preventive
conservation but also the set of actions that encompasses the concept of guardianship. This refers,
in general, to knowledge, management and conservation/intervention in these buildings, including
scopes like structural analysis (in the line of works such as those published in [60,61]).
This work refers to a concrete experience of applying new methodological aspects in the modeling
process and information management in an HBIM model, focused on the action of preventive
conservation. This experience arises from a collaboration commitment between the research group of
which the authors are part and the company dedicated to the preventive conservation of the façades of
the Cathedral of Seville. The company provided information on the current state of the building and on
the treatments applied, and the authors provided a method for the documentation and management of
that information. Additionally, a simpliﬁed modeling of the interior spaces and the material elements
that surround them was introduced with the objective of establishing metric and trace relations with
the façade elements, thus supporting new analyses on the historical evolution of this part of the temple.

4.4. In Reference to the Treatment and Consultation of the Information

The implementation of the proposed workﬂow in a continuous process of preventive conservation,
as is the case described, would be a very important advance in the treatment of information. In any
case, it is proposed that the adoption of this system begin in a ﬁrst process of objectiﬁcation of concepts
in three main and related groups:

• A group containing information linked to knowledge that, as a basis for the process of valuing
the managed assets, includes the information collected that is part of the aforementioned
document repository.
• The HBIM information model itself, linked to the concepts of the previous group and container of
all the data associated with each of the elements that make it up, depending on the information
structure already raised, and with the required depth (LOK) for the objectives sought.
• The group formed by the diﬀerent operations that are selected as feasible and convenient based
on analysis derived from the ﬁrst two groups. These operations would consist of previous,
parallel and subsequent works to the very fact of conservation. Its results, once executed, would
nourish relevant information to the ﬁrst group. In this way, the cycle would be closed in a loop
of continuous updating capable of feeding and sustaining the diﬀerent processes linked to the
conservation of the monument.

\5. Conclusions

This work has led to the development and improvement of a methodology capable of supporting
the implementation of HBIM heritage information modeling with guarantees, in the processes

<!-- p. 31 -->

Appl. Sci. 2020, 10, 2428 31 of 34

of knowledge, intervention and management of architectural heritage in general, and preventive
conservation actions in particular. Thus, the contributions to the knowledge and analysis of the
model studied are the result of said methodological innovation. However, as stated before, the main
contribution is not in the heritage use of the BIM, already explored in the many experiences referred to
in the text, but in the approach to it from an integral perspective of the protection of the patrimonial
fact. The issue of the use of BIM in architectural heritage has been placed not only in the partial scope
of the accurate graphic survey but also in its role as a wealth management tool accessible from the
various disciplines involved.
The model was developed with support in digital metric captures analyzed and interpreted with
the methodological keys of architectural survey. The model arises, consequently, from a proposal of
interpretation of the metric data based on archaeological and architectural knowledge of the element
studied. The translation of the raw data of the capture into three-dimensional graphic entities, that
contain and generate information, was based on a conceptual theoretical model. This evolved from
previous work reaching the high levels of complexity required by the studied reality.
For greater viewing and management ﬂexibility, three levels of development were processed in
parallel: Two that, diﬀerentiated into two levels of detail at the formal level, cover the entire element
studied as a single entity, and another, derived from the exploded view of the previous one, where
each building unit of the set was delimited. The single entity models incorporate the information
parameters related to the whole element (whether this is the complete building unit or a fragment
of it). This information is completed with the values of each piece of the exploded model, where
the parameters associated with the various actions that the model has to support are incorporated.
Among these, this research highlighted those of preventive conservation as culmination through the
experience. In the latter case, the implementation of so-called surface information points (SIPs) stands
out as methodological innovation. These entities, of great versatility, allowed the incorporation of
information on the surface of models of great formal complexity.
Systematized and standardized information entry and exit protocols were developed through
external databases linked to the graphic model, as well as data import–export ﬂows. These allow the
visualization of the model through free visors of great usability, allowing interaction with the model
of agents involved without specialized training in BIM methodology. This interaction was tested as
positive for the analysis processes based on graphic queries obtained from the ﬁltering of alphanumeric
information contained by the model and linked to the various databases. This link is considered key
in the conception of the HBIM model as an essential tool in the maintenance and management of
updated information on the object of study. In any case, unlike other academic contributions, this
work does not consider the model as a mere container or receiver of information, but as an active
tool that supports reﬂection and decision making at an analytical level. The model itself is capable of
generating information that channels new knowledge about the complex transformation processes
that characterize historical architecture.

Author Contributions: All authors have read and agree to the published version of the manuscript.
Conceptualization, R.A.-F. and M.C.-R.; Methodology, R.A.-F. and M.C.-R.; Software, R.A.-F.; Validation, M.C.-R.;
Visualization, R.A.-F.; Writing—original draft, R.A.-F.; Writing—review & editing, R.A.-F. and M.C.-R.

Funding: The exposed experience constitutes one of the actions developed in the HAR2016-78113-R Project,
supported by the Ministry of Science, Innovation and Universities of the Government of Spain, R & D & I Plan,
with acronym TUSOSMOD.

Acknowledgments: The authors express their gratitude to their colleagues in the research group HUM799
“Heritage knowledge strategies” and to the company Artyco. S.L.

Conﬂicts of Interest: The authors declare no conﬂict of interest.

References

\1. Angulo Fornos, R. Construcción de la base gráﬁca para un sistema de información y gestión del patrimonio
arquitectónico: Casa de Hylas. Arqueol. la Arquit. 2012, 11–25. [CrossRef]

<!-- p. 32 -->

Appl. Sci. 2020, 10, 2428 32 of 34

\2. Castellano Román, M. Generación de un modelo de información del patrimonio inmueble en el momento de
su protección jurídica. Rev. EGA 2015, 26, 266–277. [CrossRef]
\3. Angulo Fornos, R. Digital models applied to the analysis, intervention and management of architectural
heritage. In Proceedings of the Building Information Modeling (BIM) in Design, Construction and Operations; WIT
Press: Bristol, UK, 2015; Volume 149, pp. 407–418.
\4. Angulo Fornos, R.; Pinto Puerto, F.; Rodríguez Medina, J.; Palomino, A. Digital Anastylosis of the Remains
of a Portal by Master Builder Hernán Ruiz: Knowledge Strategies, Methods and Modeling Results. Digit.
Appl. Archaeol. Cult. Herit. 2017, 7, 32–41.
\5. Castellano Román, M.; Pinto Puerto, F. Dimensions and Levels of Knowledge in Heritage Building Information
Modeling, HBIM: The model of the Charterhouse of Jerez (Cádiz, Spain). Digit. Appl. Archaeol. Cult. Herit.
2019, 14, e00110.
\6. Castellano Román, M.; Pinto Puerto, F. HBIM oriented towards the master plan of the charterhouse of Jerez
(Cádiz, Spain). Int. Arch. Photogramm. Remote Sens. Spat. Inf. Sci. 2019, XLII, 285–290. [CrossRef]
\7. Pocobelli, D.P.; Boehm, J.; Bryan, P.; Still, J.; Grau-Bové, J. Building information models for monitoring and
simulation data in heritage buildings. Int. Arch. Photogramm. Remote Sens. Spat. Inf. Sci. 2018, XLII, 909–916.
[CrossRef]
\8. Fonnet, A.; Alves, N.; Sousa, N.; Guevara, M.; Magalhaes, L. Heritage BIM integration with mixed reality for
building preventive maintenance. In Proceedings of the 2017 24o Encontro Português de Computação Gráﬁca e
Interação (EPCGI); Institute of Electrical and Electronics Engineers (IEEE): Guimarães, Portugal, 2017; pp. 1–7.
\9. Lo Turco, M.; Mattone, M.; Rinaudo, F. Metric survey and BIM technologies to record decay conditions. Int.
Arch. Photogramm. Remote Sens. Spat. Inf. Sci. 2017, XLII-5/W1, 261–268. [CrossRef]
\10. Brumana, R.; Dellatorre, S.; Oreni, D.; Previtali, M.; Cantini, L.; Barazzetti, L.; Franchi, A.; Banﬁ, F.; Della
Torre, S.; Oreni, D.; et al. HBIM challenge among the paradigm of complexity, tools and preservation: The
basilica Di collemaggio 8 years after the earthquake (L’aquila). Int. Arch. Photogramm. Remote Sens. Spat. Inf.
Sci. - ISPRS Arch. 2017, XLII, 97–104. [CrossRef]
\11. Lo Turco, M.; Caputo, F.; Fusaro, G. From integrated survey to the parametric modeling of degradations.
A feasible workﬂow. In Proceedings of the 6th International Confrence EuroMED 2016; Ioannides, M.,
Moropoulou, A., Fresa, A., Rajcic, V., Eds.; Springer International Publishing: Nicosia, Cyprus, 2016;
pp. 579–589.
\12. Carrero Santamaría, E. La sacristía catedralícia en los reinos hispanos. Evolución topográﬁca y tipo
arquitectónico. Liño Rev. Anu. Hist. del arte 2005, 49–75.
\13. Recio Mir, Á. “Sacrum Senatum”: Las Estancias Capitulares de la Catedral de Sevilla; Fundación Focus-Abengoa
y Universidad de Sevilla: Sevilla, Spain, 1999; ISBN 84-472-0469-3.
\14. Arévalo Rodríguez, F. El amurallamiento externo de la mezquita aljama de la Sevilla almohade. In Actas de
XVIII Edición Aula Hernán Ruiz: La catedral sin la catedral; Cabildo Catedral de Sevilla: Sevilla, Spain, 2011;
pp. 7–56. ISBN 978-84-938923-0.
\15. Tabales Rodríguez, M.Á.; Jiménez Sancho, Á. La Cilla de la Catedral y el sector meridional de la mezquita
aljama de Sevilla. In Magna Hispalensis (I) Recuperación de la aljama almohade; Aula Hernán Ruiz, Cabildo
Metropolitano: Granada, Spain, 2002; pp. 229–296. ISBN 84-7170-183-9.
\16. Morales Martínez, A.J. La arquitectura de la catedral de Sevilla en los siglos XVI, XVII y XVIII. In La catedral
de Sevilla; Guadalquivir: Sevilla, Spain, 1984; pp. 173–215.
\17. Morales Martínez, A.J. La Sacristía Mayor de la Catedral de Sevilla; Diputación Provincial de Sevilla: Sevilla,
Spain, 1984; ISBN 84-505-0097-4.
\18. Rodríguez Estévez, J.C. Los canteros de la catedral de Sevilla. Del Gótico al Renacimiento; Diputación Provincial
de Sevilla: Sevilla, Spain, 1998; ISBN 84-7798-143-4.
\19. Rodríguez Estévez, J.C. Martín de Gainza (ca.1505-1556). In Artistas Andaluces y artíﬁces del arte andaluz;
Publicaciones Comunitarias. Grupo Hércules: Sevilla, Spain, 2011; pp. 255–288. ISBN 9788493673673.
\20. Gentil Baldrich, J.M. La traza oval y la sala capitular de la Catedral de Sevilla: Una aproximación geométrica.
In Qvatro. Ediﬁcios sevillanos; Fidas-Demarcación COA Sevilla: Sevilla, Spain, 2008; pp. 75–147.
\21. Gómez Martínez, J. El gótico español de la Edad Moderna: bóvedas de crucería; Arte y Arqueología / Universidad de
Valladolid 14; Secretariado de Publicaciones e Intercambio Cientíﬁco, Universidad de Valladolid: Valladolid,
1998; ISBN 84-7762-845-9.

<!-- p. 33 -->

Appl. Sci. 2020, 10, 2428 33 of 34

\22. Sierra Delgado, R. Diego de Siloé y la nueva fábrica de la Sacristía Mayor de la Catedral de Sevilla; Colección
Arquitectura No 31; Universidad de Sevilla, Secretariado de Publicaciones: Sevilla, Spain, 2012; ISBN
978-84-472-1416-7.
\23. Pinto Puerto, F. La Sacristía de los Cálices: Aportaciones desde el análisis de sus fábricas y los sistemas de control
formal; Cabildo Catedral de Sevilla: Sevilla, Spain, 2013.
\24. Jiménez Martín, A. Anatomía de la Catedral de Sevilla, 1st ed.; Diputación de Sevilla. Servicio de Archivo y
Publicaciones: Sevilla, Spain, 2013; ISBN 978-8477983446.
\25. Morales Martínez, A.J. Sacristías del renacimiento en Andalucía. In Arquitectura religiosa del siglo XVI en
España y Ultramar; del Lacarra Ducay, M.C., Ed.; Institución Fernando el Católico (Excma. Diputación de
Zaragoza): Zaragoza, Spain, 2004.
\26. Pinto Puerto, F. Las esferas de piedra: Sevilla como lugar de encuentro entre arte y ciencia del Renacimiento;
Arte/Diputación de Sevilla. Serie 1a; 36; Diputación de Sevilla, Área de Cultura y Deportes, Servicio de
Archivo y Publicaciones: Sevilla, Spain, 2002; ISBN 84-7798-182-5.
\27. Palacios Gonzalo, J.C. La cantería medieval: La construcción de la bóveda gótica española; ML; 8; Munilla-Lería:
Madrid, Spain, 2009; ISBN 9788489150843.
\28. Hichri, N.; Stefani, C.; De Luca, L.; Veron, P.; Hamon, G. From Point Cloud To Bim: A Survey of Existing
Approaches. ISPRS - Int. Arch. Photogramm. Remote Sens. Spat. Inf. Sci. 2013, XL-5/W2, 343–348. [CrossRef]
\29. Brumana, R.; Oreni, D.; Barazzetti, L.; Cuca, B.; Previtali, M.; Banﬁ, F. Survey and Scan to BIM Model for the
Knowledge of Built Heritage and the Management of Conservation Activities. In Digital Transformation of the
Design, Construction and Management Processes of the Built Environment; Springer: Cham, Switzerland, 2020;
pp. 391–400.
\30. Nieto Julián, J.E. Generación de modelos de información para la gestión de una intervención: La cárcel de la
Real Fábrica de Tabacos de Sevilla. Virtual Archaeol. Rev. 2012, 3, 63–67. [CrossRef]
\31. Buill Pozuelo, F.; Núñez Andrés, A.; Puche Fontanilles, J.M.; Macias, J.M. Geometric analysis of the original
stands of roman amphitheater in Tarragona: Method and results. J. Cult. Herit. 2015, 16, 640–647. [CrossRef]
\32. Rodríguez-Moreno, C.; Reinoso-Gordo, J.F.; Rivas-Lpez, E.; Gmez-Blanco, A.; Ariza-Lpez, F.J.; Ariza-Lpez, I.
From point cloud to BIM: An integrated workﬂow for documentation, research and modeling of architectural
heritage. Surv. Rev. 2018, 50, 1–20. [CrossRef]
\33. Fai, S.; Graham, K.; Duckworth, T.; Wood, N.; Attar, R. Building Information Modeling and Heritage
Documentation. 23rd Int. Symp. Int. Sci. Comm. Doc. Cult. Herit. 2011, 12–13.
\34. Dore, C.; Murphy, M. Integration of Historic Building Information Modeling ( HBIM ) and 3D GIS for
Recording and Managing Cultural Heritage Sites. Proc. 2012 18th Int. Conf. Virtual Syst. Multimedia, VSMM
2012 Virtual Syst. Inf. Soc. 2012, 369–376.
\35. Bregianni, A. BIM Development for Cultural Heritage Management, National Technical University of
Athens—Polytechnic University of Milan. 2013. Available online: http://dspace.lib.ntua.gr/bitstream/
123456789/8297/1/bregianni_thesis_rv.pdf (accessed on 6 February 2015).
\36. Rua, H.; Gil, A. Automation in heritage—Parametric and associative design strategies to model inaccessible
monuments: The case-study of eighteenth-century Lisbon Águas Livres Aqueduct. Digit. Appl. Archaeol.
Cult. Herit. 2014, 1, 82–91. [CrossRef]
\37. Quattrini, R.; Malinverni, E.; Clini, P.; Nespeca, R.; Orlietti, E. From TLS to HBIM. High quality
semantically-aware 3D modeling of complex architecture. In Proceedings of the The International Archives
of the Photogrammetry, Remote Sensing and Spatial Information Sciences, Ávila, España, 25–27 February
2015; Volume XL-5/W4, pp. 367–374.
\38. Lo Turco, M.; Bruno, E. Historic Building Information Modeling: From historical database platform to fully
suitable and multidisciplinary design instruments. In Proceedings of the World Heritage and Degradation.
Smart Design, Planning and Technologies, Naples-Capri, Italy, 16–18 June 2016.
\39. Baik, A. From point cloud to Jeddah Heritage BIM Nasif Historical House—Case study. Digit. Appl. Archaeol.
Cult. Herit. 2017, 4, 1–18. [CrossRef]
\40. Cogima, C.; Paiva, P.; Dezen Kempter, E.; Garcia de Carvalho, M.A.; Soibelman, L. The Role of
Knowledge-Based Information on BIM for Built Heritage. Advances in Informatics and Computing
in Civil and Construction Engineering; Mutis, I., Timo, H., Eds.; Springer: Chicago, IL, USA, 2019.
\41. Garagnani, S. Building Information Modeling and real world knowledge: A methodological approach to
accurate semantic documentation for the built environment. 2013 Digit. Herit. Int. Congr. 2013, 489–496.

<!-- p. 34 -->

Appl. Sci. 2020, 10, 2428 34 of 34

\42. Oreni, D.; Brumana, R.; Banﬁ, F.; Bertola, L.; Barazzetti, L.; Cuca, B.; Previtali, M.; Roncoroni, F. Beyond crude
3D models: From point clouds to historical building information modeling via NURBS. Lect. Notes Comput.
Sci. (including Subser. Lect. Notes Artif. Intell. Lect. Notes Bioinformatics) 2014, 8740, 418–426.
\43. Barazzetti, L.; Banﬁ, F.; Brumana, R.; Previtali, M. Creation of Parametric BIM Objects from Point Clouds
Using Nurbs. Photogramm. Rec. 2015, 30, 339–362. [CrossRef]
\44. Tommasi, C.; Achille, C.; Fassi, F. From point cloud to BIM: A modeling challenge in the cultural heritage
ﬁeld. Int. Arch. Photogramm. Remote Sens. Spat. Inf. Sci. - ISPRS Arch. 2016, 41, 429–436. [CrossRef]
\45. Angjeliu, G.; Cardani, G.; Coronelli, D. A parametric model for ribbed masonry vaults. Autom. Constr. 2019,
\105. [CrossRef]
\46. Oreni, D.; Brumana, R.; Georgopoulos, A.; Cuca, B. HBIM for Conservation and Management of Built
Heritage: Towards a Library of Vaults and Wooden Bean Floors. In Proceedings of the ISPRS Annals of the
Photogrammetry, Remote Sensing and Spatial Information Sciences, Strasbourg, France, 2–6 September 2013;
Volume II-5/W1, pp. 215–221.
\47. Thomson, C.; Boehm, J. Automatic geometry generation from point clouds for BIM. Remote Sens. 2015, 7,
11753–11775. [CrossRef]
\48. Macher, H.; Landes, T.; Grussenmeyer, P. From Point Clouds to Building Information Models: 3D
Semi-Automatic Reconstruction of Indoors of Existing Buildings. Appl. Sci. 2017, 7, 1030. [CrossRef]
\49. Bassier, M.; Klein, R.; Van Genechten, B.; Vergauwen, M. IFCwall reconstruction from unstructured point
clouds. ISPRS Ann. Photogramm. Remote Sens. Spat. Inf. Sci. 2018, 4, 33–39. [CrossRef]
\50. Demarsin, K.; Vanderstraeten, D.; Volodine, T.; Roose, D. Detection of closed sharp edges in point clouds
using normal estimation and graph theory. CAD Comput. Aided Des. 2007, 39, 276–283. [CrossRef]
\51. Weber, C.; Hahmann, S.; Hagen, H. Methods for Feature Detection in Point Clouds. Vis. Large Unstructured
Data Sets IRTG Work. 2010, 19, 90–99.
\52. Xiong, X.; Huber, D. Using Context to Create Semantic 3D Models of Indoor Environments. In Proceedings
of the British Machine Vision Conference, Aberystwyth, UK, 31 August–3 September 2010; Labrosse, F.,
Zwiggelaar, R., Liu, Y., Tiddeman, B., Eds.; BMVA Press: Durham, UK, 2010.
\53. Núñez Andrés, A.; Buill Pozuelo, F.; Regot, J.; de Mesa, A. Use of robust methods to determine quadratic
surfaces: Application to heritage. J. Archaeol. Sci. 2013, 40, 1289–1294. [CrossRef]
\54. Riveiro, B.; DeJong, M.J.; Conde, B. Automated processing of large point clouds for structural health
monitoring of masonry arch bridges. Autom. Constr. 2016, 72, 258–268. [CrossRef]
\55. Palestini, C.; Basso, A.; Graziani, L. Integrated photogrammetric survey and bim modeling for the protection
of school heritage, applications on a case study. In Proceedings of the International Archives of the
Photogrammetry, Remote Sensing and Spatial Information Sciences—ISPRS Archives, Riva del Garda, Italy,
4–7 June 2018; pp. 821–828.
\56. Antón, D.; Medjdoub, B.; Shrahily, R.; Moyano Campos, J.J. Accuracy evaluation of the semi-automatic 3D
modeling for historical building information models. Int. J. Archit. Herit. 2018, 12, 790–805. [CrossRef]
\57. Nieto Julián, J.E.; Moyano, J.J.; García Gascón, Á.; García, Á. Estudio constructivo del palacio de los niños de
Don Gome (Andújar, Jaén), gestionado desde el proyecto HBIM. Virtual Archaeol. Rev. 2019, 10, 84–97.
\58. González Pérez, C. Information Modeling for Archaeology and Anthropology: Software Engineering Principles for
Cultural Heritage, 1st ed.; Springer: Berlin/Heidelberg, Germany, 2018.
\59. Soler, F.; Melero, F.J.; Luzón, M.V. A complete 3D information system for cultural heritage documentation.
J. Cult. Herit. 2017, 23, 49–57. [CrossRef]
\60. Bassier, M.; Hadjidemetriou, G.; Vergauwen, M.; Van Roy, N.; Verstrynge, E. Implementation of scan-to-BIM
and FEM for the documentation and analysis of heritage timber roof structures. Digit. Heritage. Prog. Cult.
Herit. Doc. Preserv. Prot. 2016, 10058 LNCS, 79–90.
\61. Angjeliu, G.; Cardani, G.; Coronelli, D. Digital modeling and analysis of masonry vaults. ISPRS Ann.
Photogramm. Remote Sens. Spat. Inf. Sci. 2019, 42, 83–89. [CrossRef]

© 2020 by the authors. Licensee MDPI, Basel, Switzerland. This article is an open access
article distributed under the terms and conditions of the Creative Commons Attribution
(CC BY) license (http://creativecommons.org/licenses/by/4.0/).
