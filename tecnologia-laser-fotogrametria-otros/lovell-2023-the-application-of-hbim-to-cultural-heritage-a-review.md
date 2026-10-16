---
type: libro
title: "Lovell 2023 - The application of HBIM to cultural heritage - a review"
author: ""
categoria: "Tecnología láser, fotogrametría, otros"
paginas: 28
extraccion: "texto"
fuente: "local:E:/Biblioteca digital/Tecnología láser, fotogrametría, otros/Lovell 2023 - The application of HBIM to cultural heritage - a review.pdf"
convertido: 2026-10-14
---

# Lovell 2023 - The application of HBIM to cultural heritage - a review

> Texto extraído de `Tecnología láser, fotogrametría, otros/Lovell 2023 - The application of HBIM to cultural heritage - a review.pdf` (28 páginas, texto). El PDF original está en el disco E: (Biblioteca digital); `<!-- p. N -->` marca el inicio de cada página.

<!-- p. 1 -->

University of Birmingham

The Application of Historic Building Information
Modelling (HBIM) to Cultural Heritage
Lovell, Lucy; Davies, Richard; Hunt, Dexter

DOI:
10.3390/heritage6100350
License:
Creative Commons: Attribution (CC BY)

Document Version
Publisher's PDF, also known as Version of record
Citation for published version (Harvard):
Lovell, L, Davies, R & Hunt, D 2023, 'The Application of Historic Building Information Modelling (HBIM) to
Cultural Heritage: A Review', Heritage, vol. 6, no. 10, pp. 6691-6717. https://doi.org/10.3390/heritage6100350

Link to publication on Research at Birmingham portal

General rights
Unless a licence is specified above, all rights (including copyright and moral rights) in this document are retained by the authors and/or the
copyright holders. The express permission of the copyright holder must be obtained for any use of this material other than for purposes
permitted by law.

•Users may freely distribute the URL that is used to identify this publication.
•Users may download and/or print one copy of the publication from the University of Birmingham research portal for the purpose of private
study or non-commercial research.
•User may use extracts from the document in line with the concept of ‘fair dealing’ under the Copyright, Designs and Patents Act 1988 (?)
•Users may not further distribute the material nor use it for the purposes of commercial gain.

Where a licence is displayed above, please note the terms and conditions of the licence govern your use of this document.

When citing, please reference the published version.
Take down policy
While the University of Birmingham exercises care and attention in making items available there are rare occasions when an item has been
uploaded in error or has been deemed to be commercially or otherwise sensitive.
If you believe that this is the case for this document, please contact UBIRA@lists.bham.ac.uk providing details and we will remove access to
the work immediately and investigate.

Download date: 15. Oct. 2026

<!-- p. 2 -->

heritage

Review
The Application of Historic Building Information Modelling
(HBIM) to Cultural Heritage: A Review

Lucy J. Lovell *, Richard J. Davies and Dexter V. L. Hunt

School of Civil Engineering, University of Birmingham, Edgbaston, Birmingham B15 2TT, UK;
r.j.davies.1@bham.ac.uk (R.J.D.); d.hunt@bham.ac.uk (D.V.L.H.)
\* Correspondence: ljl848@student.bham.ac.uk; Tel.: +44-7780720439

Abstract: Historic Building Information Modelling (HBIM) is the application of BIM, a digital
modelling and information management technique, to assets of historical signiﬁcance, otherwise
known as Cultural Heritage (CH). The adoption of BIM for CH is justiﬁed by government mandates
and acknowledgement by leading heritage institutions that there is a need to utilise digital tools for
heritage management. This paper establishes the current state of HBIM implementation within CH
as well as research trends to date via a review of the existing literature. Geometric modelling was
found to be the topic of very early research into HBIM, with particular focus given to improving
the accuracy and efﬁciency of modelling. Thus, methods for improving modelling were evaluated.
HBIM as an information management tool is discussed including the issues encountered, such as
data storage and insufﬁcient existing tools, as well as key information requirements proposed in the
literature. An evaluation of key HBIM case studies found limited evidence of the created models being
used in practice and an overall lack of consideration of the information needs. It was determined
that the implementation of HBIM is limited by a lack of deﬁned information requirements, and
standardisation regarding the method of implementation.

Keywords: HBIM; cultural heritage; BIM; built heritage

Citation: Lovell, L.J.; Davies, R.J.;

Hunt, D.V.L. The Application of
Historic Building Information 1. Introduction
Modelling (HBIM) to Cultural 1.1. Historic Building Information Modelling
Heritage: A Review. Heritage 2023, 6,
Building Information Modelling (BIM) is a standardised procedure (ISO 19650) [1]
6691–6717. https://doi.org/10.3390/
developed by the Architecture, Engineering and Construction (AEC) industry for the digital
heritage6100350
management of assets. BIM is the process of creating an intelligent 3D model of an asset
Academic Editors: Mila Koeva, which also contains extra information about ‘objects’ within the asset. This information
Mauro Lo Brutto and Marcello La includes geometric information (e.g., dimensions of a window) and non-geometric informaGuardia tion (e.g., details of the materials that make up a structure, or manufacturers handbooks).
Received: 24 August 2023 Traditionally, BIM models are created for new build projects using construction drawings
Revised: 2 October 2023 and are updated as the project progresses. Heritage or Historic BIM (HBIM) is an evolution
Accepted: 7 October 2023 of BIM, ﬁrst suggested by [2], regarding assets of historical signiﬁcance herein referred to as
Published: 12 October 2023 Cultural Heritage (CH). CH is deﬁned by UNESCO as “artefacts, monuments, a group of
buildings and sites, museums that have a diversity of values including symbolic, historic,
artistic, aesthetic, ethnological or anthropological, scientiﬁc and social signiﬁcance” [3].
Subsequently, this paper will use ‘BIM’ to refer to BIM for new assets only. Contrary to BIM,
Copyright: © 2023 by the authors. where the asset is built according to the model, an HBIM is retrospectively created from
Licensee MDPI, Basel, Switzerland.
survey data and then enriched. By deﬁnition, CH is in the Operation and Maintenance
This article is an open access article
(O&M) lifecycle phase, a phase already underrepresented by BIM standards [4] and further
distributed under the terms and
limited by ad hoc approaches to Facilities Management (FM) [5].
conditions of the Creative Commons
There is currently no standard for HBIM, nor comprehensive identiﬁcation of the
Attribution (CC BY) license (https://
information requirements for HBIM. However, the justiﬁcation for its adoption is two-fold.creativecommons.org/licenses/by/
4.0/). In 2016, the UK government mandated that BIM was required for all centrally funded

Heritage 2023, 6, 6691–6717. https://doi.org/10.3390/heritage6100350 https://www.mdpi.com/journal/heritage

<!-- p. 3 -->

Heritage 2023, 6 6692

projects and consequently many companies choose to implement BIM on all their projects
regardless as it is increasingly becoming a client requirement. The UK BIM mandate
does not distinguish between new build assets and assets of historical signiﬁcance [5].
Furthermore, if correctly developed, HBIM could assist with the sustainable management
of heritage for future generations. Ref. [6] suggests that effective management systems
allow the coordination of activities from different stakeholders and also allow the allocation
of resources, both of which are known functionalities of BIM. There is an argument that the
subjective nature of heritage makes it unsuitable for BIM applications. However, the World
Heritage List (WHL), an internationally respected convention managed by UNESCO, is a
property-based convention [7], a format easily translatable to parametric BIM modelling.
Ref. [8] successfully applied HBIM concepts to a UNESCO site in Marrakech, providing
proof of concept. The barriers to HBIM include a lack of technical skills and existing
culture for digitisation in the ﬁeld of CH [9–11] as well as the associated costs of model
creation [12]. A known beneﬁt of HBIM is its ability to bring together multiple sources
of disparate information [13]. However, the “current lack of appropriate information
(regarding CH) provides both the need for HBIM and a barrier to it’s adoption” [9].
The aim of this paper is to establish the current state of HBIM implementation within
CH via a semi-structured scoping review. The objectives are:
• O1—Identify the literature regarding the current implementation of HBIM.
• O2—Review the identiﬁed literature and establish research trends and ﬁndings to date.
• O3—Evaluate the success of key modelling case studies.
• O4—Deﬁne the research gap and areas for future research.

1.2. Exisitng HBIM Reviews

There exists to date a number of literature reviews regarding HBIM; the majority of
which identify and contain a considerable focus on the process of geometric data collection
and modelling [14–17]. Thus, to avoid duplication of discussion, this paper will only
provide an overview of geometric data collection and modelling techniques and will
subsequently only discuss the most recent developments in this area. This will account for
the changes in the available technology since the publication of existing reviews, which is
particularly relevant for [15] who mention several emerging technologies which are now
widely investigated (scan-to-BIM and augmented reality (AR)). Several reviews also discuss
the capabilities of Geographic Information Systems (GISs) and their potential integration
with BIM [14,18] as well as the use of a variety of open source software [19]. These are
identiﬁed within the reviews as still emerging technologies which will be discussed in more
detail in Section 4.2.2.
The requirements of the CH sector are only considered by a few reviews, with some
disparity between them: Refs. [15,20] primarily focus on the use of HBIM for the dissemi-
nation of CH heritage to the public and the role of CH as a public resource whereas [16,21]
consider conservation practice in regards to the analysis and interrogation of CH structures
through historic documentation and condition data. Whilst differing, these approaches
both reﬂect existing agreed international conventions regarding heritage management, with
the latter reﬂecting the advice of the Venice Charter [22] and the former representing the
cocreation principles championed by the Faro Convention [23]. Ref. [16] concluded that
methods for storing the information required for the CH sector are lacking and, within
reviews to date, the only notable consideration of this is [24] who reviewed ontology and
external database methodologies for storing these data. Refs. [24,25] Given the apparent
limited consideration of both information types and storage within the HBIM literature to
date, concluded from published reviews, this paper will provide a detailed discussion in
this area (Section 4).
Whilst limited in scope due to their exclusion of CH, the review of BIM for existing
buildings conducted by [26] concludes that the application of BIM is limited by organi-
sational, cultural and legal considerations. Existing guidance and advice regarding asset
management suggests that these issues can be overcome by ensuring all future asset man-

<!-- p. 4 -->

Heritage 2023, 6 6693

agement approaches having consistent terminology and conceptual processes so even if
a technology becomes obsolete, the information should be able to be maintained [27–29].
Ref. [29] claims it is a lack of standardised procedure which has most severely limited the
ﬁeld of asset management. Whilst it must be acknowledged that CH has unique complexi-
ties, the authors of this paper believe that CH should not ignore the recommendations of the
asset management sector. As such, this review will consider the available HBIM standards.

\2. Methodology
2.1. Literature Identiﬁcation

The literature database ‘Scopus’ was used to search for the literature. The key word
search was “HBIM” AND (“Cultural Heritage” OR “Built Heritage”). Papers written prior
to 2015 were excluded from the initial search. This was for two key reasons. Primarily, it is
evident that the majority of EU BIM mandates came into effect from 2015 onwards [30] and
work before a national BIM mandate is typically undertaken by researchers, thus tends to
be focused on theoretical uses as opposed to end user requirements. The second reason is
that, due to the rate of BIM technology development, older works reviewed in the initial
search experienced technological issues which are now obsolete. As an exception to the
initial exclusion rule, papers considered key to the evolution of HBIM (prior to 2015), such
as [2], which is the ﬁrst to deﬁne HBIM as a concept, were included in the initial search and
review. Following the initial review, additional key papers prior to 2015 [31–33] were then
identiﬁed to remove any potential critical limitations to the work.
Some have sought to distinguish HBIM, referring to more modern CH, and Archaeo-
BIM, referring to ancient CH. There is justiﬁcation for this since the same procedure applied
to newer CH has been shown to encounter fewer issues than with ancient heritage [34].
However, Ref. [35] suggests that there is a tendency within heritage professionals to favour
ancient history over modern history which implies that a site that encompasses both or that
has experienced changes over time may be insufﬁciently modelled by separating these two
disciplines. As such, this paper will refer to BIM for all CH as HBIM.

2.2. Literature Review and Research Trends

The literature review has been grouped into common research trends. The order
corresponds with the commonality of the topic, starting with the most common.

• Geometric Data Collection and Modelling (Section 3);
• BIM for Information Management (Section 4);
• Augmented Reality (AR) vs. Virtual Reality (VR) (Section 5).

2.3. Evaluating the Success of Key Case Studies

From the reviewed literature, an assessment criteria for HBIM models was created and
applied to key case studies (Section 3.2.1). The assessment criteria evaluated the resulting
model based on geometric characteristics (including accuracy and granularity of model
objects) and the amount of information stored in the models. The relative importance of
each characteristic for two common use cases (FM and Conservation) was deﬁned based
on a consensus inferred from the literature reviewed. Sixteen case studies were evaluated
in this way.

2.4. Deﬁning the Research Gap and Areas for Future Research

Section 6 considers the papers reviewed and discusses the areas key to the imple-
mentation of HBIM, which appear as yet undeveloped, and which will be subsequently
addressed in future work by the authors. Conclusions are drawn in Section 7 regarding the
research trends to date and the current implementation of HBIM.

\3. Geometric Data Collection and Modelling

Geometric modelling was the initial challenge associated with HBIM [2]. Its impor-
tance is summarised by [36] which says it is “the basis upon which all other attributes are

<!-- p. 5 -->

Heritage 2023, 6 6694

deﬁned and created” and [37] which claims “adequate graphic documentation can be one
of the most effective means for the conservation of cultural heritage”.

3.1. Data Collection

The most common geometric data collection methods tend to be photogrammetry and
Terrestrial Laser Scanning (TLS). Typically, TLS is used for obtaining data from the ground
and Unmanned Arial Vehicles (UAVs), often equipped with photogrammetry equipment,
are used for unsafe structures [35] or inaccessible areas [38–42]. Ref. [36] compared common
geometric data collection methods and concluded that both TLS and photogrammetry have
a high degree of accuracy, but TLS is limited by cost and mobility considerations. In
some cases, traditional surveying techniques or previous surveys are utilized for model
creation [43] but survey speciﬁcation guidance [44] typically advocates the use of mass
data techniques such as TLS [35,38–42].
There is no formal standard for the scan resolution, however Ref. [36] compared
different resolutions against a range of accuracy criteria and concluded that a resolution of
2 cm or less should be used. Ref. [44] also provided guidance on surveying CH for Historic
England. The number of scans is determined by site characteristics, as demonstrated
by [45] who had to undertake more scans at varying distances from their temple case study
because the curved surfaces of the columns caused data voids. Notable outliers are [46],
who used Optical Scanning (OS) for detailed elements, and [47], who utilised a handheld
laser scanner to collect data for a decorative surface. OS was used because the resolution
was much higher than TLS but was limited by unfeasibly large ﬁle sizes.
Ref. [48] discarded their UAV data due to measured inaccuracies and [38,49] noticed
distortions in their UAV images which questions the validity of the UAV data. Ref. [42]
claimed to be able to create an HBIM using only UAVs that was accurate to approximately
0.16 m. Their work relied on an extensive archive of architectural drawings, rarely available
for CH. Their earlier work, undertaken without archival documents, was only accurate to
0.36 m of the real condition [37]. This number is arguably too high for certain use cases for
an HBIM such as aiding in renovation works. In contrast to this, Refs. [50,51] suggest that
with sufﬁcient geometric validation points, UAVs can be used as an accurate means of data
acquisition. Ref. [51] established the geometric validation points using a total station. The
additional use of equipment may negate the beneﬁt of UAVs being cheaper than TLS [36].
There seems to be little consideration given to survey data after model creation and no
apparent consensus on whether the data should be kept in the HBIM or discarded. However,
the value of survey data as an information source must not be underestimated [52]. Using
just the point cloud, Ref. [53] was able to conduct a material quantiﬁcation of a cathedral, to
estimate its value, and [54] was able to successfully model the behaviour of a tower during
an earthquake. Similarly, Ref. [55] suggests that UAVs could also be used to improve visual
inspection techniques. Ref. [56] was able to automatically identify damage to a structure
from the point cloud. As demonstrated, maintaining up-to-date survey information within
a HBIM, as opposed to considering it as just a tool for model creation, could enable new
analysis that appears to be, as yet, underutilised. Given the consequent importance of
survey data, Refs. [11,57] suggest the necessity of additional meta data about how, and by
whom, surveys were carried out. This meta data about the surveys enable their validity to
be ensured as part of any future quality assurance activities.

3.2. Modelling
3.2.1. Adapting Standard BIM Procedures to HBIM

Previous case studies have attempted to adapt BIM procedures to HBIM [58], but these
have generally been considered failures because BIM was primarily created for construction
use [59]. The clearest example is demonstrated by the deﬁnition of the Level of Detail
(LOD), which refers to the required level of graphical representation. The highest LOD for
BIM refers to as-built, the current state of CH, but achieving that LOD in a heritage project
is not yet feasible. It could be argued that the only standard deﬁnition applicable to HBIM

<!-- p. 6 -->

Heritage 2023, 6 6695

is the recent deﬁnition of the Level of Information Need (LOIN), new to ISO 19650 [60],
which is composed of the level of model detail and level of associated information, positing
that in some instances a low level of model detail can be mitigated via a high level of
associated information [1].
Thus, HBIM projects often deﬁne new LODs [61–63] or entirely new categories more
appropriate to CH [43,64,65]; notable examples include the Level of Knowledge (LOK) [43],
Level of History (LoH) [60,66] and Grades of Generation (GoG) [65]. The frequent creation
of new terminology and deﬁnitions lead [48] to suggest that HBIM workﬂows are only
applicable to the existing asset and cannot be applied to a new addition. Despite the
numerous attempts to redeﬁne LOD for heritage, ISO 19650 [1] does not reﬂect any of the
new proposed deﬁnitions so they will not be adopted herein. However, the burgeoning
shift in practice from LOD to the arguably more useful LOIN suggests future develop-
ments to ISO 19650 and associated BIM standards may be able to encompass some of the
requirements of the CH.
The only international standard for BIM is ISO 19650, which has already been noted to
not encompass CH, and parallel national standards exist. The extension of standardised
procedures to include HBIM have been suggested by some [67], but [63] is one of the only
works that has actually attempted standardisation in practice. Its procedure had eight
phases describing the expected information and suitable LOD at each stage. The limitation
of the work is that it is primarily designed for refurbishments so ﬁve of the eight phases
are ‘interventions’ which are conceptually similar to standard construction. In practice, the
achievable LOD for HBIM is limited by data collection and modelling methodologies [45].

3.2.2. Modelling Methodologies

There are three common modelling approaches: using conventional BIM authoring
tools, using alternative technology and creating bespoke technologies. These approaches
are summarised in Table 1 and their respective advantages and disadvantages discussed in
the subsequent paragraphs.

Table 1. Modelling approaches for HBIM.

Approach Details

Most conventional BIM technique. Objects are created
within a BIM authoring tool with editable parameters
A.1. Parametric
associated with them. Most additional information will be
attributed to these parameters.
A. BIM authoring tools, e.g., Revit
When an object is unique to an asset, it can be modelled
manually within BIM authoring tools similar in principle
A.2. Manual
to Computer Aided Design (CAD) modelling. An
example of this method is included in [68].

B.1. NURBS- Non-Uniform A mathematical modelling technique able to model
Rational B-Splines complex shapes by creating curves from control points.

Software models the entire surface by creating polygons
B.2. Mesh-to-BIM linking individual points in a point cloud. The greater the
B. Alternative technologies number of polygons, the more detailed the surface.

3D model objects are made in generic CAD software and
B.3. CAD
then imported to a BIM authoring tool for enrichment

Development of a new software, often when a model
C. Bespoke Systems needs to fulﬁl a particular use case. There are only a few
instances where this is applied.

A.1. Parametric modelling—Parametric BIM objects can be used multiple times with
slight edits available and the objects can be added to object libraries to enable their reuse
on other projects. Creating new detailed parametric objects requires a large amount of

<!-- p. 7 -->

Heritage 2023, 6 6696

modelling skill and time. There is an argument that the subjective nature of heritage makes
it unsuitable for parametric modelling but the WHL is a property-based convention [7], a
format easily translatable to parametric modelling. Ref. [8] also successfully applied HBIM
concepts to a UNESCO site in Marrakech, providing proof of concept.
A.2. Manual modelling—Modelling within the BIM authoring tool makes it possible
to make edits in the future and other information, such as materials, can be added in
a standard format. BIM authoring tools do not have as many built-in modelling tools
as software created speciﬁcally for CAD. Since heritage is often architecturally complex,
modelling requires greater time and technical skill [69] and BIM tools are not yet accurate
enough for complex modelling [70]. They were also designed for new-build construction
so will not model irregularities which are inherent to CH [9]. Objects modelled ‘in place’
cannot be reused on other projects.
B.1. NURBS—NURBS models are easy and simple to create as they are a well-
established modelling technique. They can model complex shapes to a high degree of
accuracy but they lack depth of information, a secondary modelling software is required
and they cannot be edited once imported into BIM authoring tools [71].
B.2. Mesh-to-BIM—Mesh models are good representations of the point cloud [72] and,
correspondingly, the surface of the structure leading [73] to remark that depending on the
deﬁned LOD for the project it may not be necessary to model, for a speciﬁc object, anything
other than a surface mesh. Furthermore, Refs. [48,74] suggest that mesh-to-BIM is the best
modelling technique for modelling changes over time because it is the most dimensionally
accurate. Having a high-resolution mesh surface can make ﬁles unfeasibly large and having
too many mesh polygons causes issues with other software such as VR technologies [50].
Mesh models cannot be edited once exported to BIM authoring tools [74].
B.3. CAD—CAD typically provides increased modelling capabilities compared to BIM
software meaning that CAD tools are often better equipped to model complex and irregular
shapes and, since they are not designed speciﬁcally for the modelling of buildings, they do
not impose building logic to models. However, there is rarely a bi-directional link between
software (unless they are from the same manufacturer) so edits made in one model will not
be applied to the other. Objects made in the CAD software cannot be added to an object
library and, like NURBS, cannot be edited in BIM tools.
C. Bespoke Systems—Capabilities can be tailored to a speciﬁc project’s needs. How-
ever, speciﬁc advantages are unique to each system and rarely have universal beneﬁts so
cannot be generalised herein. A lack of standardisation results in interoperability issues
with other tools. Furthermore, the complete separation of HBIM and BIM via a bespoke
system fails to acknowledge the interaction of new and old construction. This interaction
is compounded by [75] which utilised lighting simulations, an existing capability of BIM
tools, to design a new lighting system for a basilica in Florence. Similarly, Ref. [53] utilised
‘take off’ capabilities in Revit to conduct a monetary valuation of a Cathedral in Mexico.

3.2.3. Evaluating the Success of Modelling Case Studies

The choice of modelling technique is often dependent on the intended use and as such
there are many disparate approaches. In generic terms, model uses can be split into two
categories: FM, which includes everyday operation of the asset and normal maintenance
tasks, and conservation, which includes restoration and work to upgrade or modify an asset
to survive changing conditions. It is evident that the usefulness of the resulting model for
its intended task is dependent on three parameters: (i) its Geometric Accuracy (GA) (used
here instead of LOD due to the current lack of standard terminology), (ii) the number of
unique Identiﬁable Objects (IO) (sometimes referred to as granularity) and (iii) the amount
of Associated Information (AI).
From the papers reviewed, a new assessment criterion for determining the usefulness
of an HBIM case study was developed. The criterion involves a series of parameters (see
Table 2) applied to an appropriate newly proposed equation (see Table 3) for the intended
use. These equations for the apparent usefulness level for conservation and FM were

<!-- p. 8 -->

Heritage 2023, 6 6697

derived according to the perceived importance of each parameter inferred from the papers
read in this review. For instance, it is generally agreed that for FM purposes, a lower level
of GA is required but AI and IO are key [4,10,11,76,77].

Table 2. Assessment parameters for determining the usefulness of key HBIM case studies.

Geometric Accuracy (GA);
No. Identiﬁable Objects (IO); Intended Use (IU) Successful Implementation for Intended Use (SIIU)
Associated Information (AI).

1 = Low *
C = Conservation 1 = No evidence given or unspeciﬁed use.
2 = Low **
1.5 = Strong argument for why implementation will be 3 = Medium *
FM = Facilities Management successful (either from author or other work) but no
4 = Medium ** evidence given.
5 = High *
U = Unspeciﬁed 2 = Proven successful implementation for speciﬁc use.
6 = High **

\* Assumed, ** Proven.

Table 3. Equations for calculating the usefulness of the HBIM.

Usefulness Level for Conservation (ULC) Usefulness Level for Facilities Management (ULFM)

If intended use is FM,
If intended use is C,
(1) ULFM = ((IO + AI) × SIIU) + (0.5 × (3)
ULC = ((GA + AI) × SIIU) + (0.5 × IO).
GA).

If intended use is FM or U, If intended use is C or U,
(2) (4)
ULC = (GA + AI) + (0.5 × IO). ULFM = (IO + AI) + (0.5 × GA).

Geometric accuracy was evaluated by visually comparing how accurate the model was
to the real condition. Below is an example of how GA would be assessed for the modelling
of an ancient stone wall.

• Wall represented as a regular shape (cuboid) with no deviations. Representation
symbolic of actual object = Low GA.
• Wall depicted using an irregular shape, somewhat representative of actual object =
Medium GA.
• Wall depicted using an irregular shape, representative of actual object. There may be
additional details in the model representing areas of decay, weathering or aging =
High GA.

Whether the GA was ‘proven’ or ‘assumed’ refers to whether the paper makes refer-
ence to an explicit, usually numerical comparison of the deviation of the model from the
real condition.
The number of identiﬁable objects were evaluated by visual assessment of the model
granularity. Below is an example of how IO would be assessed for the modelling of an
interior wall of a residential structure.

• Wall represented as a single object. No individual features including artistic features,
functional elements (e.g., light switches) or distinct building phases are distinguished
\= Low IO.
• Wall depicted as several distinct objects or as one object with sections. Typically, some
individual features will be modelled = Medium IO.
• Wall depicted as several individual objects. This could include modelling each indi-
vidual structural component of the wall (e.g., individual bricks or distinct structural
layers) or including the majority of individual features as separate objects = High IO.

Whether the IO was ‘proven’ or ‘assumed’ refers to whether the paper makes an
explicit reference to the granularity of modelling.

<!-- p. 9 -->

Heritage 2023, 6 6698

The amount of associated information was evaluated by assessing the number of
individual types or sources of information stated to be included in addition to the geometric
model. Below is an example of how AI was assessed.

• None/minimal discussion of any additional information besides the model itself =
Low AI.
• Some discussion of a few other information types or sources to be included with the
model. Generic types or information sources may be given = Medium AI.
• Detailed discussion of numerous additional information types or sources to be in-
cluded with the model. Often an explicit list is provided = High AI.

Whether the AI was ‘proven’ or ‘assumed’ refers to whether the paper makes explicit
reference to the actual inclusion of additional information to the ﬁnished model.
Notable modelling case studies are discussed in Table 4. To avoid duplication of the
results and ensure the concise evaluation of individual methodologies, the case studies
included herein were those deemed to be a good representation of a distinct methodology
(see unique feature column of Table 4 for details). The assessment criterion was applied
informally throughout the review process to all case studies so conclusions drawn from
Table 4 can be considered representative of the whole. The case studies are ordered
according to their assessed usefulness for their intended use where the maximum achievable
score was 27 but the highest score was 16. The main limitation seems to be that whilst
papers appear to brieﬂy mention the AI to be attributed to the model, there is apparently
very little evidence of its detailed inclusion.

Table 4. Key HBIM case studies including their unique feature and usefulness assessment.

Case Unique
Details GA IO AI IU SIIU ULC ULFM
Study Feature

Ref. [11] suggested that the ideal modelling
technique would involve all elements being
manually modelled parametrically, to achieve
the accuracy of a mesh with the editability of a
Hybrid
parametric object, but acknowledged that this
1 approach
had cost and time implications so instead opted 5 5 4 C 1.5 16 11.5
[11] using mesh and
for a hybrid approach. Simple surfaces were
parametric modelling
modelled parametrically and meshes were
created for complex objects. The limited use of
meshes reduced computer processing issues
due to ﬁle sizes.

Part of a 20-year project to model a Roman
Fluvial Port. Ref. [78] was able to model the
Developed a new
structure to a high degree of accuracy and
modelling software
2 include a segmentation tool for classifying
with a 5 5 3 C 1.5 14.5 10.5
[78] decay mechanisms and the potential
focus on modelling
interventions required. Their methodology was
decay.
validated by archaeological experts so was
proven to be successful.

Ref. [13] modelled all the decorative elements
of a Kurdish minaret. The decorative elements
3 Modelling lost were modelled as they would have been
3 3 5 C 1.5 13.5 9.5
[13] heritage for restoration (extrapolated from available data) as opposed
to the as-is condition so that the model could be
used for restoration purposes.

Modelling for Ref. [10] created an HBIM for structural
4
structural condition condition analysis by removing all decorative 2 5 5 C 1.5 13 11
[10]
analysis elements from the model.

Ref. [79] created a model purely for structural
analysis, so deconstructed components into a
Simplifying model
5 series of 3D line elements. This method worked
elements for structural 2 5 3 C 2 12.5 9
[79] as the elements modelled were standard steel
analysis.
components such as I-beams, so were of less
complexity than most historical architecture.

<!-- p. 10 -->

Heritage 2023, 6 6699

Table 4. Cont.

Case Unique
Details GA IO AI IU SIIU ULC ULFM
Study Feature

Ref. [80] examined wall painting as a
representative of decorative surfaces in BIM.
Modelling layers of a
They incorporated layers of the painting as a
6 structure (decorative)
series of photos within the model. They suggest 5 5 1 C 1.5 11.5 8.5
[80] as
that the incorporation of all data within the
individual images.
model, as opposed to an external link, allows
better informed management decisions.

Ref. [81] determined that the accurate
modelling of all objects was not possible due to
time constraints (of manual modelling) and
Used placeholder
7 processing requirements (of mesh models).
objects for complex 1 3 5 C 1.5 10.5 8.5
[81] They used placeholder objects (geospatially
objects.
accurate but otherwise arbitrary shapes) and
then associated all other information as meta
data, e.g., photos of the actual condition.

Creating a model for
Ref. [82] initially modelled complex
Finite
architecture using NURBS surfaces but had to
Element
8 later convert the model to a mesh so that it
Modelling (FEM) to 5 1 1 C 1.5 9.5 4.5
[82] could be exported to FEM software (Pro-Sap), a
determine
step that arguably could have been avoided if
seismic
the shapes were modelled as a mesh initially.
stability

Ref. [83] conceded that a fully realistic model
would require a highly specialised technician,
so aimed to create a model using Revit without
spending undue time on the modelling itself.
They acknowledged limitations of Revit for
Including model
modelling as-built deviations, but overcame
accuracy analysis to
9 this by using CloudCompare to compare the
mitigate 4 3 1 C 1 6.5 6
[83] deviation between their model and the point
limitations regarding
cloud. The output of the process was a false
time and modeller skill
colour map that was attached as a JPEG to the
model. Whilst successful, they also suggested
that a similar result could be achieved by
storing the point cloud in Revit and visually
assessing accuracy.

Ref. [84] created an HBIM to be exported to
BEM software (Cypetherm C.E.) to allow for
analysis of the potential renovation options.
They parametrically modelled objects but found
HBIM for Building
10 that the inaccuracies at the modelling stage
Energy Model (BEM) 1 3 1 C 1 3.5 4.5
[84] caused errors in the outputted result when they
analysis
imported the model parameters to BEM
software. They suggested this could be
overcome by BEM calibration from existing
data or by integrating digital twin technology.

Ref. [85] had to create a model using
photogrammetry and NURBS models because
the building primarily consisted of marble and
mosaic surfaces. It is rare that a model is made
without TLS due to its increased accuracy;
however, the marble surfaces partially absorb
Creating a model from
11 lasers and the mosaic surfaces caused huge
orthophotos and 5 3 1 C 1 7.5 6.5
[85] amounts of reﬂection. Orthophotos were also
photogrammetry
included within the model which were of high
enough resolution that individual mosaic tiles
could be distinguished. As such, they were able
to use the images for restoration purposes.
Orthophotos are not typically included as they
are unfeasibly large ﬁles.

<!-- p. 11 -->

Heritage 2023, 6 6700

Table 4. Cont.

Case Unique
Details GA IO AI IU SIIU ULC ULFM
Study Feature

Ref. [86] modelled an underground heritage site
and used the resulting model to design a
non-invasive ventilation system using
Computational Fluid Dynamics (CFD). It was
12 Modelling only from clear from the complexity of the shapes and
5 1 1 FM 2 6.5 6.5
[86] the surface mesh available data that Mesh-to-BIM was the only
suitable method. They experimented with
different mesh sizes and found that reducing
the complexity of the mesh had minimal effect
on the CFD output.

Ref. [87] found from the point cloud that the
Adding
walls of their case study were not straight and
additional parameters
13 had large amounts of tilt. Using Revit, they
to Revit to describe 1 3 3 FM 1 5.5 6.5
[87] were not able to easily model this. They
structural
overcame this by adding additional parameters
irregularities.
to the model to describe wall tilt.

Manually creating a
Whilst the model of [88] was made to a high
3D model of a
level of accuracy, they found the process
cathedral portico in a
14 time-consuming and complex. It seems unclear
single CAD software 5 5 2 U 1 9.5 9.5
[88] what the beneﬁts of their completely accurate
(AutoCAD) and then
model were as no future intended use was
exporting to BIM
speciﬁed.
authoring tools.

Ref. [89] created a 3D model entirely in CAD
software without any associated extra
information or parametric capabilities; i.e., it
Using multiple CAD was not a BIM model. The CAD was then
15
software to create the imported into Revit to add extra information 3 3 3 U 1 7.5 7.5
[89]
3D model. and elevate it to a BIM model. This bypassed
certain modelling limitations of BIM tools with
regards to the number of modelling tools
available (Table 1).

Ref. [90] created a model of a village in Saudi
Applied
Arabia. The aim was to include texture
orthophotography to a
information so that it could provide
16 model created in Revit
information regarding structure condition, 5 3 1 U 1 7.5 6.5
[90] to accurately model
decay of material, decorative variety and
the as-is texture of the
phases of buildings as well as being useful for
structures.
creating virtual environments

Whilst non-exhaustive of all case studies reviewed, it can be seen from Table 4 that
models made using BIM authoring tools generally achieve a lower level of GA. Case studies
that implemented alternative technologies generally achieved a high GA but the use of
additional software further increases the cost of model creation, a pre-existing barrier to
the implementation of HBIM [12]. Whilst its assessed usefulness was limited by a lack
of AI, the approach of [83] (case study 9) may provide the simplest, lowest-cost solution
to modelling limitations. GA is less important when the model is used for numerical
analysis as the analysis software often requires a simpliﬁed model (see case study 5).
Several papers used digital twins [84,86] or sensor integration [91] to overcome modelling
simpliﬁcations. However, Ref. [49] suggests that an accurate model increases conﬁdence in
high-risk developments which could potentially cause damage to an asset, which may be
why many of the models intended for conservation work in Table 4 had a high level of GA.
Ref. [64] states that advanced techniques are rendered obsolete by heritage professionals
not using them; it is notable in Table 4 that of the 16 case studies, 3 were created without
a clearly speciﬁed use and only 2 demonstrated a model being successfully used for its
intended purpose.

<!-- p. 12 -->

Heritage 2023, 6 6701

3.2.4. Increasing Modelling Speed and Quality

As evident in Section 3.2.2, there is no single modelling approach for HBIM which is
without limitations, and the existing methodologies are either time-consuming or produce
inaccurate models. It is worth noting that creating BIM models for new build construction
still requires signiﬁcant investments in terms of cost and time so it is arguably inappropriate
to assume that the creation of an HBIM will ever be instant. That being said, a few method-
ologies for increasing modelling speed and quality have been attempted, summarised in
Table 5. Details of each approach are discussed below.

Table 5. Methodologies for increasing modelling speed and quality.

Approach Success Level

A.1. Point cloud and mesh segmentation Developing
A. Automatic/Semi-Automatic Processes
A.2. Model creation Limited to simple surfaces

B. Creating a Model from Existing
Poor
Documents or traditional surveys

C.1. Creating new parametric models as per
Poor
BIM methodologies

C. HBIM Libraries C.2. Adapting existing objects Limited accuracy

C.3. Creating theoretical objects Limited accuracy

C.4. Increasing the granularity of BIM objects Currently limited to simple shapes

A.1. Point cloud and mesh segmentation—Whilst point clouds will model an entire
surface, they can be segmented into more usable units to reduce processing requirements,
enable meshes of individual objects or more easily model individual elements [64,74,92,93].
Automatic techniques are being developed that can detect which points in a cloud or
sections of a surface mesh correspond with a single object. This is known as semantic
segmentation. Tests of semantic segmentation techniques have had limited success and it is
mostly still a manual process as technology is not advanced enough [64]. Ref. [94] tested a
segmentation algorithm but found that it was only successful for large areas as opposed to
detailed shapes and even in large areas it included many false positives. Ref. [95] was able
to segment a point cloud by ﬁrst deﬁning an extensive ontology of the elements and rules
relating to castles and applying machine learning but the necessity of deﬁning the ontology
mitigates the modelling efﬁciency.
A.2. Model creation—Arguably the next evolution of point cloud segmentation is
where a modelling algorithm detects areas of the point cloud belonging to a single object,
separates the point and then creates a 3D object in that place. This method has been
investigated and applied with some success to individual work [96], but there is yet to be
a fully automated process [97]. Other works have repeatedly concluded that modelling
algorithms are not yet developed enough to model complex architecture or differences due
to aging [73,74,98–100]. Ref. [45] suggests that modelling requires a degree of technical
insight regarding constructive techniques which cannot be automatically determined. The
most successful automatic modelling techniques model geometric primitives [97,101]. Of
these, the accuracy is potentially insufﬁcient for certain use cases, with [97] only achieving
a distance accuracy for columns of approximately 64 mm.
B. Creating a model from existing documents or traditional surveys—The least used
modelling efﬁciency, suggested by [62,74], involves creating a model from existing doc-
umentation and then validating that model with scan data. An alternative approach to
this method is using traditional cartography as a data source for model creation [43]. In
practice, it seems to only be used for instances of lost heritage [102–104] or for when the
model is being used for visualisation purposes only [105]. Refs. [10,41,106] all compared
their resulting models to the point cloud and found signiﬁcant differences in the measured
geometries, arguably invalidating the method.

<!-- p. 13 -->

Heritage 2023, 6 6702

C.1. Creating new parametric models as per BIM methodologies—Manually creating
new parametric objects to be added to a library speciﬁcally for HBIM. Objects should be
true to the as-is condition. Ref. [107] attempted to implement an HBIM library, envisioning
minimal issues, due to the nature of their case study for which there was already an
extensive index of building component information. They encountered difﬁculties at
the modelling stage due the geometrical complexity of the objects and were unable to
implement the HBIM library they proposed. Ref. [108] also attempted to create a library
of objects and encountered issues regarding transferring point clouds to object modelling
platforms and adding additional data. Their method was effort-intensive but successful.
C.2. Adapting existing objects—A common simpliﬁcation which involves the adaption
of existing object libraries by altering the pre-existing parameters of similar objects. The
main assumption is that certain features are regular [100]. Ref. [70] states that the regular
objects of HBIM libraries lead to the normalisation of the complexity of heritage and a loss
of understanding of the real value.
C.3. Creating theoretical object—Rather than modelling from the point cloud, objects
are created from historical documents such as architectural drawings, manuals, treatises
and building guidance. This creates a library of uniform theoretical objects. This alternative
method was trialled by [109,110], who created a series of ideal vault elements, as well
as [111] who created a library of classic architectural elements. Whilst successful, this
process is incredibly time-consuming and relied upon large amounts of existing data and
architectural rules. Its validity is questioned by the work of [100] who created a component
library for a church but noted that the objects did not reﬂect the real condition as per the
point cloud. Similar issues to creating models from existing drawings are encountered.
C.4. Increasing the granularity of BIM objects—Involves splitting objects into smaller
components that are more likely to be reused. The most common example is splitting
columns into shafts and bases, a method previously utilised by [112] who attempted to
create a library of algorithmically modelled columns by splitting them into functional
components. They found that the shaft element of certain columns could be reused for
other, similar columns. Similar methodologies were employed by [73,113] but their work
was manual as opposed to algorithmic. Ref. [114] also split elements into components but
states that, to be able to generate a model sufﬁcient for structural analysis, the components
must be developed with an understanding of their structural interactions.
Object libraries were arguably the ﬁrst [115], and now one of the most commonly
investigated, approaches because they already contribute to the procedural efﬁciency of
BIM. However, they have yet to encompass CH [110]; the generation of new BIM objects
requires a signiﬁcant time investment which is further complicated by the complexity
of CH objects and modelling tools and formats do not account for CH features such
as irregular and tilted walls [87]. As such, there have been many varying attempts to
develop an HBIM library as they are the only proven mechanism for improving modelling
efﬁciency. However, the application tends to be limited to newer heritage [77,84,116],
and to architectural styles where there are known to be common repeating elements
across different assets [40,69,90,107,113,117,118]. It has been suggested that, due to the
uniqueness of CH, each asset requires its own non-transferable library of elements [73].
However, Ref. [119] created a component library for traditional Taiwanese woodwork and
distinguished 4 families with parameters (same shape but varying size) and 23 families
without parameters (same shape and size), exhibiting the effectiveness of an HBIM library.
Ref. [120] is one of very few that suggested that all the objects modelled should be added
to a shareable HBIM library regardless of perceived object commonality.

\4. BIM for Information Management
4.1. Overview of the Issue

As seen in Table 4, HBIM models are often developed without a known use and there
appears to be very limited evidence of them being used in practice. Ref. [121] suggests
that, despite the emerging prevalence of HBIM models, they risk being abandoned post

<!-- p. 14 -->

Heritage 2023, 6 6703

any restoration work due to a lack of useful information, illustrated by the lack of AI in
Table 4. Whilst arguably true, the issue is exacerbated by the lack of integration between
BIM and FM tools resulting in a large amount of data loss between stages [122] and a lack
of engagement with CH stakeholders both in terms of their awareness and understanding
of BIM [25], and the understanding of their organisational information requirements (OIRs).
Refs. [15,21] conclude that future works need to enable the continuous use of the HBIM for
FM but [4] suggest that BIM and FM are not yet fully integrated because there is insufﬁcient
legislation mandating the use of BIM in FM and, since ISO 19650 [1] was designed for
construction, it does not encompass the breadth required for CH. As previously discussed,
the uses of an HBIM are typically split into conservation and FM and different models
are developed depending on the end use. Without evidence of the models being used
for their intended it purpose, it is consequently unclear whether this is due to the actual
differences in need for FM and conservation or just the limited scope of the speciﬁc project.
It can therefore be concluded that without knowing the OIRs for HBIM, it is impossible to
deﬁne a storage approach. Ref. [6] suggested some requirements for heritage management
systems based on common factors across a diverse range of world heritage sites and some
papers have made attempts to deﬁne the information requirements for HBIM ([8,58,73,99],
but their attempts often seem oversimpliﬁed. Ref. [122] established a more comprehensive
list of requirements but since this work focused on a renovation project, similar to [63],
it primarily included construction activities. Other papers appear to simply identify one
requirement with little regard for other information types, contributing to the numerous
disparate methodologies for implementing HBIM.
The following sections thus present the generic methods commonly employed for in-
formation storage and then discuss more speciﬁc requirements frequently covered: heritage
signiﬁcance, moveable assets, building condition and changes over time.

4.2. Storing Information
4.2.1. Modifying Existing Workﬂows

Extra data are added to BIM models as object parameters. As evident in Table 4,
it is not yet possible to create a fully accurate model using a single software [123] so
models must be in a standard format so they can be exported between programmes with
no loss of data [93]. The Industry Foundation Class (IFC), a vendor neutral tool, is the
most widely used BIM export format [124] and is conceptually beneﬁcial for HBIM as
it enables stakeholder collaboration [13]. However, since the IFC was developed for
BIM, it does not cater for the requirements of heritage [125]. The existing schema do not
encompass common cultural heritage elements such as vaults [71,126,127] and some works
have experienced interoperability issues with FM systems [82,84]. Only [124,125] seem to
suggest the adaption of the existing IFC standard to meet heritage requirements. This has
precedence as the IFC is regularly updated to include new schema. The latest update at
the time of writing, IFC 4.3, was an expansion to include road, rail, ports and waterways
and bridges which were not included previously [128]. This is the issue currently facing
CH; thus, it can concluded that the logical approach is to further develop the IFC for CH.
Ref. [125] tested their suggestion of updating the IFC schema and achieved good results
but did contend that the exact deﬁnitions of the IFC are not suitable for the complete
classiﬁcation of CH. This sentiment is echoed by [71], which suggests that the hierarchal
relationships of the IFC (e.g., window objects are related to wall objects), which relay
structural relationships, may not be true for CH. A key document for looking after heritage
is a conservation plan based on the recommendations of the Burra Charter. Typically, these
are stored separately but there have been attempts at the IFC conversion. Ref. [124] found
that it was possible to convert a conservation plan to the IFC but the actual implementation
of this format would require a concerted effort.
Consequently, many people choose approaches that modify traditional BIM workﬂows.
Ref. [39] chose to assign all their information, including oral history and informative
websites, to the Revit materials as opposed to the objects themselves. This essentially

<!-- p. 15 -->

Heritage 2023, 6 6704

created an HBIM material library. Other works chose to assign information to different
layers or segments [68] of the model as opposed to the whole objects, with [99] splitting
the model into three layers: global, macro (groups of architectural elements structurally
linked) and individual elements. A similar concept was applied by [81] who chose to attach
information to building zones; however, they encountered issues when an object existed
on the peripherals of a zone. Ref. [129] suggests the inclusion of ﬂaggable parameters to
indicate the existence of speciﬁc themes such as historical information and conservation
information which would then be stored externally.
A perhaps simpler solution to the limitations of the IFC is to store data in an external
repository, often a database. The use of external repositories is discussed in numerous
works [11,43,121,122,130–133] but the exact details of how external databases should be
linked to, and interact with, the HBIM is as yet undeﬁned. Ref. [24] compared the use of
ontologies, such as the IFC, with the use of databases and argues that ontologies allow
leaner storage and more complex queries but lack the structure of databases. There remains
no clear consensus on the best approach but it is worth noting that, for FM, most information
will be stored in an external database [25] and there is an existing BIM exchange format
(COBie) to achieve this.
There is a tendency to assume that a single model can meet the needs of all stake-
holders, perhaps because most studies have a single use case. Ref. [134] is an outlier in
this respect, given that they suggest the segregation of a geometric survey, and conceptual
information (attributed to simpliﬁed geometries) into sub-models which then become a
part of the whole federated model. This suggestion has precedence because BIM already
segregates models (e.g., for Mechanical, Electrical and Plumbing (MEP) and structural infor-
mation) due to the different expertise required. This is known as the federation strategy [1].
Whilst conservation guidance, such as the Venice Charter [22], states that records regarding
heritage should be publicly stored and available to researchers, [20,64,101] suggest that
there should be a capability within the HBIM to limit what information is shared with who
for security purposes. This is part of the purpose of a federation strategy.

4.2.2. Alternative Technologies

The proprietary nature of BIM software is another barrier to interoperability [135].
Visual Programming Language (VPL), a user-friendly programming technique, has been
suggested to overcome this [61,113,136–138]. Ref. [139] was able to successfully integrate
Grasshopper (a VPL) to create a bi-directional link between Rhinoceros (modelling software)
and Revit, a BIM authoring tool. Similarly, Ref. [140] created a Revit add-in that aggregated
several modelling steps from external software but the add-in was tailored to terminology
and modelling deﬁnitions speciﬁc to their work so may be inapplicable to others. Another
theorised solution is Free Open-Source Software (FOSS), a low-cost or free platform where
the user is able to manually edit the source code [141,142]. Ref. [19] concluded, from 6
years of research into FOSS, that it was able to be utilised at every stage of HBIM and
cited advantages relating to customisability. Alternatively, many suggested systems are
web-based [55,81,143]. Ref. [144] claimed that a web-based platform is the best approach to
ﬁnd “common ground” for users with varying skills and expertise as they enable semantic
queries and do not require knowledge of BIM [145]. However, the creation of the web
platforms and use of a VPL still requires some programming knowledge [99], which fails to
acknowledge the existing skills gap for heritage professionals.
The integration of BIM and GISs, a tool for modelling at environmental scale, has
been suggested by several works [48,74,146,147]. Ref. [6] states that effective management
systems for heritage must include information regarding the wider setting. It is also
worth considering that many historical places encompass whole cities such as in the work
carried out by [50,118]. Functionally, Ref. [18] suggested some information requirements
for HBIM and compared the capabilities of the BIM and GIS software. They found that BIM
authoring tools are better for modelling and GISs are better for semantic interpretation but
neither software can adequately accomplish all requirements, a reality that may suggest the

<!-- p. 16 -->

Heritage 2023, 6 6705

necessity of BIM-GIS integration. Other theoretical beneﬁts include a shared knowledge
base for maintenance enquiries across sites [61] and the opportunity to create a global
HBIM library by establishing similar features between multiple buildings [84,92]. However,
this fails to acknowledge that, in an urban area, much of the surrounding area is likely
to be privately owned so it may not be possible to garner any meaningful information.
Most papers try to integrate BIM and GISs using a VPL [148,149] but [150] found that it
was possible to integrate HBIM with a GIS without the loss of any parameters using a
combination of multiple pre-existing software. Refs. [59,150] appear to be the only papers
that suggest creating bespoke software for BIM-GIS. Ref. [59] created Chimera which
was subsequently applied to a case study by [151]. Chimera was shown to have good
capabilities for information storage and demonstrating changes over time. On a smaller
scale, Ref. [152] utilised the spatial capabilities of GISs to create thematic maps to accurately
model decay on a façade.
Given the diverse needs of CH, it is arguable that to properly meet all the needs of
CH, you must combine the capabilities of BIM, GISs and game engines to encompass all
the potential information requirements. Only [150] suggests a theoretical framework to
facilitate this.

4.3. Common Information Requirements
4.3.1. Historical Signiﬁcance

The inclusion of heritage speciﬁc information is unique to HBIM. Heritage consists
of both tangible and intangible attributes and “respect for cultural and heritage diversity
requires conscious efforts to avoid imposing mechanistic formulae or standardized pro-
cedures” [153]. A lack of formulaic descripting regarding heritage information makes it
difﬁcult to include in BIM, a parameter-based modelling tool. Whilst [154] were able to
include intangible information as descriptions and images associated with objects (e.g.,
paint colours indicating a link to France), this was the exception to the norm. Thus, ﬁnding
intangible information can require semantic querying, a functionality not native to BIM.
A common solution is to link the data to the model in an external database [121] or by
creating a bespoke ID system for heritage objects [12]. Ref. [155] created an entirely new
system that, by attributing inference rules to objects based on end-user needs, was able to
query heterogeneous information. Whilst their system was bespoke and novel, it arguably
could have been implemented using rule-based ﬁltering already present in BIM authoring
tools such as Revit.
The lack of a standard vocabulary herein causes issues when trying to integrate differ-
ent software because all VPLs become case speciﬁc [147]. A vast amount of standardised
vocabulary could engender the automatic extraction of elements [156]. Hence, it is not
surprising that a number of papers mention the inclusion of ontologies such as CIDOC-
CRM (now ISO 21127 [157]), which is the standard for the cataloguing of data for museum
collections [14,81,124,135,146,158]. The most successful implementation of ontologies for
the structuring of semantic data seems to occur when multiple ontologies are used, as
presented in the work by [95], who combined the Getty Art and Architecture Thesaurus
(AAT), CIDOC-CRM, IFC, CityGML in addition to a castle nomenclature dictionary. On-
tology inclusion usually occurs on web-based software as exampled in the work by [143],
who incorporated the Getty AAT schema, and [158], who converted CIDOC-CRM using
ifcOWL, also known as the IFC web ontology.

4.3.2. Moveable Assets

Modelling moveable assets is a consideration rarely included in BIM. Ref. [35], whilst
modelling an Italian paper mill, suggested that the exclusion of moveable assets, in their
case industrial machines, risked the exclusion of fundamental parts of the asset’s signiﬁ-
cance. Likewise, Ref. [64] modelled moveable and artistic assets so that the model could
also be used for the sustainable management of those assets as opposed to the building
fabric itself. Similarly, Ref. [138] applied HBIM procedures to the modelling of museum

<!-- p. 17 -->

Heritage 2023, 6 6706

artefacts in order to plan exhibit layouts and enable the condition monitoring of artefacts.
Ref. [20] suggests that CH is made for public use or else the value and appreciation of
heritage will be lost, so HBIMs able to assist with this are crucial.

4.3.3. Building Condition

Building Condition Assessments (BCAs) are of crucial importance for CH both for
renovations, restoration and FM. Ref. [137] suggests that integrating manual inspection
methods into BIM could improve cost and efﬁciency whilst reducing the accumulation of
human errors. In parallel, [159], whilst only modelling an isolated wall mural removed
from its architectural setting, found that integrating Non-Destructive Testing (NDT) data
in its corresponding location in a 3D space enabled a multi-disciplinary evaluation of its
condition. Ref. [56] undertook extensive work investigating the different types of damage
that had impacted a Portuguese CH site; notably, material loss, moisture and biological
damage. They carried out a number of NDT tests with the aim of visually integrating the
data into the model. However, Ref. [133] suggests that there is a lack of native capabilities
within BIM tools to store NDT data. Visual BCAs from the point cloud are likewise
discussed by [160].
To counter this, Ref. [57] made a speciﬁc effort to deﬁne how to store BCA data by
storing graphical outputs of the analysis as images that were then overlayed as building
façades in Revit. The methodology was necessary as the analysis software was not IFC-
compatible, but the façades were. This technique was hindered, similarly to the work
by [73], by Revit’s conformity to building logic, where a wall can only have one façade.
Multiple ‘virtual’ walls were required to model the outputs of different tests. Ref. [129]
made a similar attempt to model building condition as a façade and created an algorithm
to model decay as a CAD overlay but the algorithm itself was prone to error. Ref. [132]
also discussed additional external object layers but instead proposed the use of ‘Surface
Information Points’, individual point objects, densely distributed across the surface of the
object containing condition information, which could be ﬁltered according to associated
parameters. Whilst arguably more successful than the use of external object layers, the
process for applying the surface points required a considerable degree of coding ability.
Ref. [161] modelled decay on a bridge as photo panels and created two bespoke parameters
to deﬁne decay. Ref. [162] created bespoke element IDs and then modelled decay using in-
dividual editable objects. The necessity of the IDs could have been mitigated by expanding
IFC to enable the storage of BCAs.
Even contemporary CH was primarily built before the advent of rigorous building
standards [136] so it may be necessary to undertake analysis to check the stability of the
existing structure or the asset’s energy performance [84,91,116,133]. Refs. [93,136] suggest
that HBIM lends itself to structural analysis since it requires extensive knowledge of the
building (contained in historic information) and most analysis software rely on parametric
input. This statement is refuted by the work of [55] which included diagnostic data as
parameters in Revit but were unable to export the data to other software because they
were not in a recognisable format. A lack of pre-existing diagnostic and restoration IFC
categories was also cited as a problem by [159,163]. Refs. [79,82] created work in an IFC
format but had to simplify their model to a dxf format because of compatibility issues
with the IFC and the Finite Element Modelling (FEM) software. Ref. [82] also experienced
issues due to Revit being unable to understand that the vaulted ceilings existed as both an
architectural feature and a structural component. There is not yet exhaustive integration of
numerical simulation software and BIM but [91] were able to develop a custom integration
using a VPL and created a real-time link between the software.

4.3.4. Changes over Time

Effective conservation relies on understanding the changes that have occurred over
time [69]. This is referred to as 4D in BIM and is typically utilised for modelling construc-
tion or demolition planning. For HBIM, several works have suggested repurposing 4D

<!-- p. 18 -->

Heritage 2023, 6 6707

functionalities for modelling large-scale changes over time [31,34,35,68,89,99,102,132], or
for modelling the progress of decay [39]. Ref. [127] categorised model elements based
on their constructive phase claiming that it would allow the identiﬁcation of previous
interventions and thus the evaluation of future risks and vulnerabilities. This claim was
validated by [152], which used construction phases to determine the likely causes of cracks
in the masonry, and by [56] which determined that previous restoration activities were the
cause of subsequent damage. A unique approach was employed by [164] which created a
model of a bridge in an area prone to ground movements. The authors created a model
from new survey data and from data collected in 1860 and then compared the two models
to assess the deformation of the bridge. Ref. [165] differs slightly from the papers previ-
ously mentioned by suggesting the separation of 4D into macro 4D, modelling large-scale
changes, and micro 4D, modelling small changes such as maintenance works. The need for
the latter is also discussed by [132] and the distinction of the two is justiﬁed because much
guidance on conservation work begins with an interrogation of the major changes that
have occurred over time [166] but then relies on the continual monitoring and management
of change [167]. A visual representation of changes at both a small and large scale would
assist with this.
Additionally, 4D could be used for educational purposes. Refs. [20,39] suggest that
by working out the chronological stages of the building’s construction and attributing this
information to the model, it could be used to teach people about historical construction
techniques. This sentiment is echoed by [119] which, whilst not explicitly referring to
4D BIM, discusses surveys teaching people about techniques now obsolete. The exact
timing of interventions is often estimated from existing documentation [102] so some
works have suggested adding a reliability statement regarding whether the date is known
or estimated [10].

4.4. Data Reliability

Data voids are common in HBIM, due to inaccessibility during data collection [39,82]
and a lack of or incompleteness of existing documentation [66,120]. It is also worth noting that
point clouds only provide surface data and the age and restrictions regarding the structure
may prevent invasive tests from occurring. Ref. [168] overcame this issue by utilising expert
interpretation from historical advisors who helped corroborate their assumptions of the
likely construction methods. Ref. [120] mitigated documentation-related data voids by
using any historical source exploring themes related to the construction period of that asset.
Similarly, Ref. [116] suggested using building standards and legislation, as well as patents,
advertisements of products and other information from architectural journals to supplement
surveyed data. This could have implications for the modelling accuracy, especially since
there is minimal knowledge about how actual building practice complied with manuals [58]
and there will have inevitably been degradation to the building with time [73]. Ref. [104]
employed historical surveys and records to supplement a point cloud of a now-damaged
historical asset. Ref. [82] chose to use current building standards to estimate the minimum
structural performance of a material so they could combine their HBIM with FEM tools as
they were unable to undertake invasive tests to determine the real values. There is a risk that
inaccurate judgements will be made if this information is assumed [116].
Ref. [49] suggests that a geometrically accurate model increases conﬁdence in a high-
risk intervention but, whilst undeniably important, the actual geometric reliability of the
models is given minimal consideration, with the exception of a few works that compare the
resulting model to the point cloud or mesh [51,72,83,132,160]. However, there is a tendency
to assume that point cloud surveys and photogrammetry are entirely accurate and only
some works appear to employ additional validation surveys [51,164] or investigations to
ensure this [36,160].
There is a general consensus that the reliability status of data—i.e., whether it is
assumed or known (fact); should be recorded [66,71,145,169]. Ref. [39] decided to extrap-
olate existing data, assuming that future investigations would eventually ﬁll the voids,

<!-- p. 19 -->

Heritage 2023, 6 6708

and colour code it according to whether the data were surveyed or hypothesised. All
of these suggestions arguably contradict the advice of The Venice Charter which states
restoration “must stop at the point where conjecture begins” [22]. Refs. [66,169,170] all
explicitly distinguish the need to deﬁne reliability both for the source of geometric data
and any information stored within the model [170], suggesting that these should be two
independently recorded factors.

\5. AR and VR

AR and VR have been frequently explored as visualisation tools for HBIM to enable
increased collaboration and more inclusive access to heritage [35,40,49,93,105,171]. These
works normally involve the user being able to ‘walk’ around the model and interact with
objects [172] to reveal additional information, often regarding intangible heritage [173].
Ref. [174] created a virtual model for tourists to show the changes over time to a basilica
in Milan. Refs. [55,175] suggest data in a BIM model could be shared via VR to reduce
intervention errors on construction sites and aid future maintenance works. Ref. [176]
utilised game engines to create a holographic HBIM; although, it is unclear what the beneﬁts
of this were as the model was small, non-portable and lacked meaningful information.
Another stream of research has suggested the use of VR to enable the population of the
geometric model with additional data remotely, a development partially instigated by the
COVID-19 pandemic [70,175]. This technique has been successful, with [177] demonstrating
that a VR tour allowed students on their ‘survey education’ course to make meaningful
observations on the condition of a temple in China. Additional data can include heritage
signiﬁcance, a value notoriously hard to deﬁne and entirely dependent on the assessor.
The beneﬁt of VR/AR for populating these data is that all stakeholders can input their
signiﬁcance assessments, a key factor of effective CH management [7]. This utilisation of
VR was successfully employed by [175], who created a model of a church in Belgium and
allowed VR visitors to place colour-coded markers about what they deemed signiﬁcant
and the type of signiﬁcance. The system recorded geospatial data relating to where visitors
were standing in the virtual environment when they placed the markers. The authors
of [175] suggest using the geospatial data to plan future visitor routes, a sentiment echoed
by [20], and go on to suggest the information regarding who attributed value to what could
be used more generally to improve the process for historical signiﬁcance assessments.
Whilst theoretically beneﬁcial, the process for converting HBIM to VR and AR is
not yet sufﬁciently advanced. Ref. [76] implemented current methodologies to convert
the HBIM of two case studies into both AR and VR. They found that the results lacked
interactivity and that the process required a large number of steps. Ref. [178] achieved a
good visual correlation between the real and VR environment but the process reduced the
parametric BIM model to a mesh reducing the associated level of information.

\6. Future Work

From the reviewed papers, it can be seen that the implementation of HBIM is cur-
rently limited by a lack of standard methodology and lack of developed OIRs. Previous
research has investigated different modelling approaches and to a lesser extent information
requirements for speciﬁc use cases; however, it is clear that a standardised approach is
remiss. As such, there is a need to deﬁne the common OIRs for CH and their relative
importance: whether they are critical requirements, non-essential yet value adding or aspi-
rational requirements. Once the OIRs are known, a viable standardised approach should be
deﬁned to include all the critical requirements with additional scope for the non-essential
yet value-adding requirements. The strategy should account for the practical technology
level achievable by CH managers to avoid obsolescence of the model. Ultimately, the
question can be posed—to what extent can HBIM be aligned with the existing and future
developments of ISO 19650?
In order to ﬁll this gap in knowledge, future work by the authors of this paper will
include the comprehensive identiﬁcation of existing OIRs for heritage according to the

<!-- p. 20 -->

Heritage 2023, 6 6709

guidance and standards published by heritage experts and facilities managers. The OIRs
will then be validated by consulting experts within the ﬁeld of heritage management
and maintenance. Once the OIRs are validated, they will be compared to existing BIM
practices for the purposes of identifying which, if any, BIM practices can be applied to
HBIM. This should (and will) look at both BIM tools and exchange formats including IFC.
A comprehensive identiﬁcation of OIRs for HBIM can be used as the foundation for the
standard methodology for the application of HBIM within CH.

\7. Conclusions

This paper carried out a semi-structured literature review to determine the current
implementation of HBIM. It established that existing research areas could be grouped
into three key areas: Geometric Data Collection and Modelling, BIM for Information
Management and AR and VR. Geometric Data Collection and Modelling was determined
to be the primary focus of early HBIM research. An assessment criterion for evaluating
the usefulness level of HBIM models was created and applied to 16 case studies. It was
observed that the HBIM case studies had given minimal consideration or discussion to what
associated information should be included with models and there was minimal evidence
of the models being used in practice for an intended purpose. This was determined to
be a limitation when evaluating the usefulness of models. It was concluded that HBIM
implementation is currently limited by a lack of standard methodology and deﬁned OIRs.
It is suggested that future work should address this limitation by collating and validating
existing OIRs for the management and maintenance of heritage which can then be applied
to deﬁning a future standard HBIM methodology.

Author Contributions: Conceptualisation, L.J.L. and R.J.D.; methodology, L.J.L.; validation, L.J.L.;
formal analysis, L.J.L.; writing—original draft preparation, L.J.L.; writing—review and editing, R.J.D.
and D.V.L.H.; visualisation, L.J.L.; supervision, R.J.D. and D.V.L.H. All authors have read and agreed
to the published version of the manuscript.

Funding: The authors gratefully acknowledge the ﬁnancial support of the UK Engineering and
Physical Sciences Research Council (EPSRC) under grant number EP/W524396/1. The APC was
funded by University of Birmingham.

Data Availability Statement: No new data were created or analysed in this study. Data sharing is
not applicable to this article.

Acknowledgments: The authors would like to thank the School of Engineering at the University of
Birmingham for providing access to its scanning equipment and BIM cave; and the University of
Birmingham Estates for providing access to various assets around campus that helped shape the
formulation of the HBIM problem statement.

Conﬂicts of Interest: The authors declare no conﬂict of interest. The funders had no role in the design
of the study; in the collection, analyses, or interpretation of data; in the writing of the manuscript; or
in the decision to publish the results.

Abbreviations

AEC Architecture, Engineering and Construction
AI Associated Information
AR Augmented Reality
BCA Building Condition Assessment
BEM Building Energy Model
BIM Building Information Modelling
CAD Computer-Aided Design
CFD Computational Fluid Dynamics
CH Cultural Heritage
FEM Finite Element Modelling
FM Facilities Management
FOSS Free Open-Source Software

<!-- p. 21 -->

Heritage 2023, 6 6710

GA Geometric Accuracy
GIS Geographic Information System
GoG Grade of Generation
HBIM Historic Building Information Modelling
IFC Industry Foundation Class
IO Identiﬁable Objects
IU Intended Use
LOD Level of Detail
LOH Level of History
LOIN Level of Information Need
LOK Level of Knowledge
MEP Mechanical, Electrical and Plumbing
NDT Non-Destructive Testing
NURBS Non-Uniform Rational B-Splines
O&M Operation and Maintenance
OIR Organisation Information Requirements
OS Optical Scanning
SIIU Successful Implementation for Intended Use
TLS Terrestrial Laser Scanning
UAV Unmanned Arial Vehicles
ULC Usefulness Level for Conservation
ULFM Usefulness Level for Facilities Management
VPL Visual Programming Language
VR Virtual Reality
WHL World Heritage List

References

\1. ISO 19650-2:2018; Organization and Digitization of Information about Buildings and Civil Engineering Works, Including Building
Information Modelling (BIM)—Information Management using Building Information Modelling—Part 2: Delivery Phase of the
Assets. The British Standards Institute: London, UK, 2018.
\2. Murphy, M.; McGovern, E.; Pavia, S. Historic Building Information Modelling (HBIM). Struct. Surv. 2009, 27, 311–327. [CrossRef]
\3. UNESCO Institute for Statistics Cultural Heritage. Available online: https://uis.unesco.org/en/glossary-term/cultural-heritage
(accessed on 18 April 2023).
\4. Dlesk, A.; Vach, K.; Shults, R.; Doubrava, P. Generalization of BIM Model for Purposes of Facility Management. Int. Arch.
Photogramm. Remote Sens. Spat. Inf. Sci. 2022, XLIII-B4-2022, 309–314. [CrossRef]
\5. Durdyev, S.; Ashour, M.; Connelly, S.; Mahdiyar, A. Barriers to the Implementation of Building Information Modelling (BIM) for
Facility Management. J. Build. Eng. 2022, 46, 103736. [CrossRef]
\6. UNESCO. Operational Guidelines for the Implementation of the World Heritage Convention; UNESCO: Paris, France, 2021.
\7. UNESCO. Preparing World Heritage Nominations; United Nations Educational, Scientiﬁc and Cultural Organization: Paris, France,
2011; ISBN 978-92-3-001029-4.
\8. Gomih, S.; Leporelli, E.; Martino, M.; Santi, G. Sustainable Strategies for the Development of UNESCO Sites: The Medina of
Marrakech. Sustain. Mediterr. Constr. 2021, 13, 153–159.
\9. Charlton, J.; Kelly, K.; Greenwood, D.; Moreton, L. The Complexities of Managing Historic Buildings with BIM. Eng. Constr.
Archit. Manag. 2021, 28, 570–583. [CrossRef]
\10. Barontini, A.; Alarcon, C.; Sousa, H.S.; Oliveira, D.V.; Masciotta, M.G.; Azenha, M. Development and Demonstration of an HBIM
Framework for the Preventive Conservation of Cultural Heritage. Int. J. Archit. Herit. 2022, 16, 1451–1473. [CrossRef]
\11. Bruno, N.; Roncella, R. A Restoration Oriented HBIM System for Cultural Heritage Documentation: The Case Study of Parma
Cathedral. Int. Arch. Photogramm. Remote Sens. Spat. Inf. Sci. 2018, XLII–2, 171–178. [CrossRef]
\12. di Stefano, F.; Malinverni, E.S.; Pierdicca, R.; Fangi, G.; Ejupi, S. HBIM implementation for an ottoman mosque. Case of study:
Sultan mehmet fatih II mosque in Kosovo. In Proceedings of the International Archives of the Photogrammetry, Remote Sensing
and Spatial Information Sciences—ISPRS Archives, Ávila, Spain, 1–5 September 2019; Volume 42.
\13. Wafaei Baneh, K.; Wafaei Baneh, B.; Osman, A.; Mostafapour, O.; Bradosty, Z.R. Regeneration and Documentation of Historic
Geometric Islamic Patterns via HBIM: A Case Study of Choli Minaret, Kurdistan Region. Int. J. Build. Pathol. Adapt. 2021, 41,
347–363. [CrossRef]
\14. Yang, X.; Grussenmeyer, P.; Koehl, M.; Macher, H.; Murtiyoso, A.; Landes, T. Review of Built Heritage Modelling: Integration of
HBIM and Other Information Techniques. J. Cult. Herit. 2020, 46, 350–360. [CrossRef]

<!-- p. 22 -->

Heritage 2023, 6 6711

\15. García-Valldecabres, J.; Pellicer, E.; Jordan-Palomar, I. BIM Scientiﬁc Literature Review for Existing Buildings and a Theoretical
Method: Proposal for Heritage Data Management Using HBIM. In Proceedings of the Construction Research Congress 2016: Old
and New Construction Technologies Converge in Historic San Juan—Proceedings of the 2016 Construction Research Congress,
San Juan, Puerto Rico, 31 May–2 June 2016.
\16. Pocobelli, D.P.; Boehm, J.; Bryan, P.; Still, J.; Grau-Bové, J. BIM for Heritage Science: A Review. Heritage Sci. 2018, 6, 30. [CrossRef]
\17. López, F.; Lerones, P.; Llamas, J.; Gómez-García-Bermejo, J.; Zalama, E.; López, F.; Lerones, P.; Llamas, J.; Gómez-García-Bermejo, J.;
Zalama, E. A Review of Heritage Building Information Modeling (H-BIM). Multimodal Technologies and Interaction. Multimodal
Technol. Interact. 2018, 2, 21. [CrossRef]
\18. Tobiáš, P. BIM, GIS and Semantic Models of Cultural Heritage Buildings. Geoinfor. FCE CTU 2016, 15, 27–42. [CrossRef]
\19. Diara, F. HBIM Open Source: A Review. ISPRS Int. J. Geo-Inf. 2022, 11, 472. [CrossRef]
\20. García, E.S.; García-Valldecabres, J.; Blasco, M.J.V. The Use of HBIM Models as a Tool for Dissemination and Public Use
Management of Historical Architecture: A Review. Int. J. Sustain. Dev. Plan. 2018, 13, 96–107. [CrossRef]
\21. Santos, D.; Sousa, H.S.; Cabaleiro, M.; Branco, J.M. HBIM Application in Historic Timber Structures: A Systematic Review. Int. J.
Archit. Herit. 2022, 17, 1331–1347. [CrossRef]
\22. ICOMOS. International Charter for the Conservation and Restoration of Monuments and Sites (The Venice Charter 1964).
In Proceedings of the IInd International Congress of Architects and Technicians of Historic Monuments, Venice, Italy, 25–31
May 1964.
\23. Council of Europe. Council of Europe Framework Convention on the Value of Cultural Heritage for Society; Council of Europe: London,
UK, 2005.
\24. Cursi, S.; Martinelli, L.; Paraciani, N.; Calcerano, F.; Gigliarelli, E. Linking External Knowledge to Heritage BIM. Autom. Constr.
2022, 141, 104444. [CrossRef]
\25. Tsay, G.S.; Staub-French, S.; Poirier, É. BIM for Facilities Management: An Investigation into the Asset Information Delivery
Process and the Associated Challenges. Appl. Sci. 2022, 12, 9542. [CrossRef]
\26. Volk, R.; Stengel, J.; Schultmann, F. Building Information Modeling (BIM) for Existing Buildings—Literature Review and Future
Needs. Autom. Constr. 2014, 38, 109–127. [CrossRef]
\27. ISO 55000:2014; The International Standards Organisation Asset Management—Overview, Principles and Terminology.
ISO: Geneva, Switzerland, 2014; Volume 1.
\28. IAM. Asset Management—An Anatomy; IAM: Bristol, UK, 2015.
\29. Global Forum on Maintenance and Asset Management. The Asset Management Landscape; Global Forum on Maintenance and
Asset Management: Toronto, ON, Canada, 2014; Volume 2.
\30. Charef, R.; Emmitt, S.; Alaka, H.; Fouchal, F. Building Information Modelling Adoption in the European Union: An Overview.
J. Build. Eng. 2019, 25, 100777. [CrossRef]
\31. Fai, S.; Graham, K.; Duckworth, T.; Wood, N.; Attar, R. Building Information Modelling and Heritage Documentation. In Proceed-
ings of the XXIIIrd International CIPA Symposium, Prague, Czech Republic, 12–16 September 2011.
\32. Angulo Fornos, R. Construcción de La Base Gráﬁca Para Un Sistema de Información y Gestión Del Patrimonio Arquitectónico:
Casa de Hylas. Arqueol. Arquit. 2013, 9, 11–25. [CrossRef]
\33. Nieto Julián, J.E. Generación de Modelos de Información Para La Gestión de Una Intervención: La Cárcel de La Real Fábrica de
Tabacos de Sevilla. Virtual Archaeol. Rev. 2012, 3, 63. [CrossRef]
\34. Attenni, M. Informative Models for Architectural Heritage. Heritage 2019, 2, 2067–2089. [CrossRef]
\35. Currà, E.; D’amico, A.; Angelosanti, M. HBIM between Antiquity and Industrial Archaeology: Former Segrè Papermill and
Sanctuary of Hercules in Tivoli. Sustainability 2022, 14, 1329. [CrossRef]
\36. Fryskowska, A.; Stachelek, J. A No-Reference Method of Geometric Content Quality Analysis of 3D Models Generated from
Laser Scanning Point Clouds for HBIM. J. Cult. Herit. 2018, 34, 95–108. [CrossRef]
\37. Carvajal-Ramírez, F.; Martínez-Carridondo, P.; Yero-Paneque, L.; Agüera-Vega, F. UAV Photogrammetry and HBIM for the Virtual
Reconstruction of Heritage. In Proceedings of the International Archives of the Photogrammetry, Remote Sensing and Spatial
Information Sciences—ISPRS Archives, Ávila, Spain, 1–5 September 2019; Volume 42.
\38. Karachaliou, E.; Georgiou, E.; Psaltis, D.; Stylianidis, E. UAV for mapping historic buildings: From 3D modelling to BIM. In
Proceedings of the ISPRS Annals of the Photogrammetry, Remote Sensing and Spatial Information Sciences, Bergamo, Italy, 6–8
February 2019; Volume 42.
\39. Conti, A.; Fiorini, L.; Massaro, R.; Santoni, C.; Tucci, G. HBIM for the Preservation of a Historic Infrastructure: The Carlo III
Bridge of the Carolino Aqueduct. Appl. Geomat. 2022, 14, 41–51. [CrossRef]
\40. Lin, G.; Giordano, A.; Sang, K. From site survey to HBIM model for the documentation of historic buildings: The case study of
Hexinwu village in China. Conserv. Sci. Cult. Herit. 2020, 20, 111–123.
\41. Bródka, J.; Wałek, M. ‘The modernist refugium’: The heritage of polish post-war residential architecture of Jerzy Zi˛etek’s villa in
Ustro´n in the perspective of documentation techniques. Int. J. Conserv. Sci. 2022, 13, 865–878.
\42. Martínez-Carricondo, P.; Carvajal-Ramírez, F.; Yero-Paneque, L.; Agüera-Vega, F. Combination of Nadiral and Oblique UAV
Photogrammetry and HBIM for the Virtual Reconstruction of Cultural Heritage. Case Study of Cortijo Del Fraile in Níjar, Almería
(Spain). Build. Res. Inf. 2020, 48, 140–159. [CrossRef]

<!-- p. 23 -->

Heritage 2023, 6 6712

\43. Castellano-Román, M.; Pinto-Puerto, F. Dimensions and Levels of Knowledge in Heritage Building Information Modelling, HBIM:
The Model of the Charterhouse of Jerez (Cádiz, Spain). Digit. Appl. Archaeol. Cult. Herit. 2019, 14, e00110. [CrossRef]
\44. Bryan, P.; Blake, B.; Bedford, J. Metric Survey Speciﬁcations for Cultural Heritage; Historic England: London, UK, 2020.
\45. D’Amico, A.; Currà, E. From TSL Survey to HBIM, Issues on Survey and Information Modeling Implementation for the Built
Heritage The Case Study of the Temple Di Bacco Ravello. In Proceedings of the International Conference on Education and
Research in Computer Aided Architectural Design in Europe, Rome, Italy, 20–22 September 2017; pp. 39–48.
\46. Antón, D.; Medjdoub, B.; Shrahily, R.; Moyano, J. Accuracy Evaluation of the Semi-Automatic 3D Modeling for Historical Building
Information Models. Int. J. Archit. Herit. 2018, 12, 790–805. [CrossRef]
\47. Reina Ortiz, M.; Weigert, A.; Dhanda, A.; Yang, C.; Smith, K.; Min, A.; Gyi, M.; Su, S.; Fai, S.; Santana Quintero, M. A theoretical
framework for multi-scale documentation of decorated surface. In Proceedings of the International Archives of the Photogram-
metry, Remote Sensing and Spatial Information Sciences—ISPRS Archives, Ávila, Spain, 1–5 September 2019; Volume 42.
\48. Barrile, V.; Bernardo, E.; Bilotta, G. An Experimental HBIM Processing: Innovative Tool for 3D Model Reconstruction of
Morpho-Typological Phases for the Cultural Heritage. Remote Sens. 2022, 14, 1288. [CrossRef]
\49. Ermenyi, T.; Enegbuma, W.I.; Isaacs, N.; Potangaroa, R. Building Information Modelling Workﬂow for Heritage Maintenance.
In Proceedings of the International Conference of Architectural Science Association, Auckland, New Zealand, 26–27 November
2020; Volume 1.
\50. De la Plata, A.R.M.; Franco, P.A.C.; Franco, J.C.; Bravo, V.G. Protocol Development for Point Clouds, Triangulated Meshes and
Parametric Model Acquisition and Integration in an HBIM Workﬂow for Change Control and Management in a UNESCO’s
World Heritage Site. Sensors 2021, 21, 1083. [CrossRef]
\51. Moyano, J.; Nieto-Julián, J.E.; Bienvenido-Huertas, D.; Marín-García, D. Validation of Close-Range Photogrammetry for Architec-
tural and Archaeological Heritage: Analysis of Point Density and 3d Mesh Geometry. Remote Sens. 2020, 12, 3571. [CrossRef]
\52. Borin, P.; Cavazzini, F. Condition assessment of RC bridges. Integrating machine learning, photogrammetry and BIM. In Proceed-
ings of the International Archives of the Photogrammetry, Remote Sensing and Spatial Information Sciences—ISPRS Archives,
Ávila, Spain, 1–5 September 2019; Volume 42.
\53. Mandujano Rodríguez, M.G. Integration of Historic Building Information Modeling and Valuation Approaches for Managing
Cultural Heritage Sites. In Proceedings of the 27th Annual Conference of the International Group for Lean Construction, IGLC
2019, Dublin, Ireland, 27 July 2019.
\54. Bitelli, G.; Castellazzi, G.; D’Altri, A.M.; de Miranda, S.; Lambertini, A.; Selvaggi, I. On the Generation of Numerical Models from
Point Clouds for the Analysis of Damaged Cultural Heritage. In Proceedings of the IOP Conference Series: Materials Science and
Engineering, Florence, Italy, 16–18 May 2018; Volume 364.
\55. Bruno, S.; Fatiguso, F. Building Conditions Assessment of Built Heritage in Historic Building Information Modeling. Int. J. Sustain.
Dev. Plan. 2018, 13, 36–48. [CrossRef]
\56. Garcia-Gago, J.; Sánchez-Aparicio, L.J.; Soilán, M.; González-Aguilera, D. HBIM for Supporting the Diagnosis of Historical
Buildings: Case Study of the Master Gate of San Francisco in Portugal. Autom. Constr. 2022, 141, 104453. [CrossRef]
\57. Solla, M.; Gonçalves, L.M.S.; Gonçalves, G.; Francisco, C.; Puente, I.; Providência, P.; Gaspar, F.; Rodrigues, H. A Building
Information Modeling Approach to Integrate Geomatic Data for the Documentation and Preservation of Cultural Heritage.
Remote Sens. 2020, 12, 4028. [CrossRef]
\58. Achille, C.; Lombardini, N.; Tommasi, C. BIM and Cultural Heritage: Compatibility Tests in an Archaeological Site. WIT Trans.
Built Environ. 2015, 149, 593–604.
\59. Rechichi, F. Chimera: A BIM+GIS System for Cultural Heritage. In Proceedings of the 2020 XXIV ISPRS Congress, Nice, France,
31 August–2 September 2020; Volume XLIII-B4-2020.
\60. Brusaporci, S.; Tata, A.; Maiezza, P. The “LoH—Level of History” for an Aware HBIM Process. In Proceedings of the 42th
International Conference of Representation Disciplines Teachers, Messina, Italy, 16–18 September 2021.
\61. Colucci, E.; Iacono, E.; Matrone, F.; Ventura, G.M. A BIM-GIS Integrated Database to Support Planned Maintenance Activities
of Historical Built Heritage. In Geomatics and Geospatial Technologies; Communications in Computer and Information Science;
Springer: Cham, Switzerland, 2022; Volume 1507. [CrossRef]
\62. Historic England BIM for Heritage: Developing a Historic Building Information Model; Historic England: Swindon, UK, 2017.
\63. Jordan-Palomar, I.; Tzortzopoulos, P.; García-Valldecabres, J.; Pellicer, E. Protocol to Manage Heritage-Building Interventions
Using Heritage Building Information Modelling (HBIM). Sustainability 2018, 10, 908. [CrossRef]
\64. Nieto-Julián, J.E.; Lara, L.; Moyano, J. Implementation of a Teamwork-HBIM for the Management and Sustainability of Architec-
tural Heritage. Sustainability 2021, 13, 2161. [CrossRef]
\65. Banﬁ, F. BIM Orientation: Grades of Generation and Information for Different Type of Analysis and Management Process.
In Proceedings of the International Archives of the Photogrammetry, Remote Sensing and Spatial Information Sciences—ISPRS
Archives, Ottowa, ON, Canada, 28 August–1 September 2017; Volume 42.
\66. Maiezza, P.; Tata, A. Standard for Geometric and Informative Reliabilities in HBIM Models. DISEGNARECON 2021, 14. [CrossRef]
\67. Inzerillo, L.; lo Turco, M.; Parrinello, S.; Santagati, C.; Valenti, G.M. Bim and Architectural Heritage: Towards an Operational
Methodology for the Knowledge and the Management of Cultural Heritage. DISEGNARECON 2016, 9.
\68. Guerrero Vega, J.M.; Pizzo, A. Análisis Arquitectónico y Aplicación de Metodología Bim En El Santuario Extraurbano de
Tusculum. Archeol. Calc. 2021, 32, 99–116. [CrossRef]

<!-- p. 24 -->

Heritage 2023, 6 6713

\69. Aricò, M.; Lo Brutto, M. From scan-to-BIM to heritage building information modelling for an ancient arab-norman church. Int.
Arch. Photogramm. Remote Sens. Spat. Inf. Sci. 2022, XLIII-B2-2022, 761–768. [CrossRef]
\70. Banﬁ, F. HBIM, 3D Drawing and Virtual Reality for Archaeological Sites and Ancient Ruins. Virtual Archaeol. Rev. 2020, 11, 16–33.
[CrossRef]
\71. Martinelli, L.; Calcerano, F.; Gigliarelli, E. Methodology for an HBIM Workﬂow Focused on the Representation of Construction
Systems of Built Heritage. J. Cult. Herit. 2022, 55, 277–289. [CrossRef]
\72. Martínez-Carricondo, P.; Carvajal-Ramírez, F.; Yero-Paneque, L.; Agüera-Vega, F. Combination of HBIM and UAV Photogramme-
try for Modelling and Documentation of Forgotten Heritage. Case Study: Isabel II Dam in Níjar (Almería, Spain). Herit. Sci. 2021,
9, 95. [CrossRef]
\73. Sztwiertnia, D.; Ochałek, A.; Tama, A.; Lewi´nska, P. HBIM (Heritage Building Information Modell) of the Wang Stave Church in
Karpacz–Case Study. Int. J. Archit. Herit. 2021, 15, 713–727. [CrossRef]
\74. Yang, X.; Lu, Y.C.; Murtiyoso, A.; Koehl, M.; Grussenmeyer, P. HBIM Modeling from the Surface Mesh and Its Extended Capability
of Knowledge Representation. ISPRS Int. J. Geo-Inf. 2019, 8, 301. [CrossRef]
\75. Campari, M.; D’Ufﬁzi, F. BIM Models to Manage and Make Use of Cultural Heritage. In Proceedings of the IMEKO International
Conference on Metrology for Archaeology and Cultural Heritage, MetroArchaeo, Lecce, Italy, 23–25 October 2017.
\76. Banﬁ, F. The Evolution of Interactivity, Immersion and Interoperability in HBIM: Digital Model Uses, VR and AR for Built
Cultural Heritage. ISPRS Int. J. Geo-Inf. 2021, 10, 685. [CrossRef]
\77. Machete, R.; Falcão, A.P.; Gonçalves, A.B.; Godinho, M.; Bento, R. Development of a Manueline Style Object Library for Heritage
BIM. Int. J. Archit. Herit. 2021, 15, 1930–1941. [CrossRef]
\78. Pratali Maffei, S.; Canevese, E.; de Gottardo, T. The real in the virtual. The 3D model in the cultural heritage sector: The TIP of the
iceberg. In Proceedings of the ISPRS Annals of the Photogrammetry, Remote Sensing and Spatial Information Sciences, Bergamo,
Italy, 6–8 February 2019; Volume 42.
\79. Bouzas, Ó.; Cabaleiro, M.; Conde, B.; Cruz, Y.; Riveiro, B. Structural Health Control of Historical Steel Structures Using HBIM.
Autom. Constr. 2022, 140, 104308. [CrossRef]
\80. Reina Ortiz, M.; Yang, C.; Weigert, A.; Dhanda, A.; Min, A.; Gyi, M.; Su, S.; Fai, S.; Santana Quintero, M. Integrating heterogeneous
datasets in HBIM of decorated surfaces. In Proceedings of the International Archives of the Photogrammetry, Remote Sensing
and Spatial Information Sciences—ISPRS Archives, Ávila, Spain, 1–5 September 2019; Volume 42.
\81. Bruno, N.; Roncella, R. HBIM for Conservation: A New Proposal for Information Modeling. Remote Sens. 2019, 11, 1751.
[CrossRef]
\82. Ursini, A.; Grazzini, A.; Matrone, F.; Zerbinatti, M. From Scan-to-BIM to a Structural Finite Elements Model of Built Heritage for
Dynamic Simulation. Autom. Constr. 2022, 142, 104518. [CrossRef]
\83. Adami, A.; Scala, B.; Spezzoni, A. Modelling and Accuracy in a Bim Environment for Planned Conservation: The Apartment
of Troia of Giulio Romano. In Proceedings of the International Archives of the Photogrammetry, Remote Sensing and Spatial
Information Sciences—ISPRS Archives, Nafplio, Greece, 1–3 March 2017; Volume 42.
\84. Massafra, A.; Predari, G.; Gulli, R. Towards digital twin driven cultural heritage management: A HBIM-based workﬂow for
energy improvement of modern buildings. In Proceedings of the International Archives of the Photogrammetry, Remote Sensing
and Spatial Information Sciences—ISPRS Archives, Prague, Czech Republic, 7–8 February 2022; Volume 46.
\85. Fregonese, L.; Taffurelli, L.; Adami, A.; Chiarini, S.; Cremonesi, S.; Helder, J.; Spezzoni, A. Survey and Modelling for the BIM of
Basilica of San Marco in Venice. In Proceedings of the International Archives of the Photogrammetry, Remote Sensing and Spatial
Information Sciences—ISPRS Archives, Nafplio, Greece, 1–3 March 2017; Volume 42.
\86. Zhang, J.; Kwok, H.H.L.; Luo, H.; Tong, J.C.K.; Cheng, J.C.P. Automatic Relative Humidity Optimization in Underground
Heritage Sites through Ventilation System Based on Digital Twins. Build. Environ. 2022, 216, 108999. [CrossRef]
\87. Reinoso-Gordo, J.F.; Rodríguez-Moreno, C.; Gómez-Blanco, A.J.; León-Robles, C. Cultural Heritage Conservation and Sustainabil-
ity Based on Surveying and Modeling: The Case of the 14th Century Building Corral Del Carbón (Granada, Spain). Sustainability
2018, 10, 1370. [CrossRef]
\88. Lo Brutto, M.; Ebolese, D.; Fazio, L.; Dardanelli, G. 3D Survey and Modelling of the Main Portico of the Cathedral of Monreale.
In Proceedings of the 2018 IEEE International Conference on Metrology for Archaeology and Cultural Heritage, MetroArchaeo
2018—Proceedings, Cassino, Italy, 22–24 October 2018.
\89. Rodríguez-Moreno, C.; Reinoso-Gordo, J.F.; Rivas-López, E.; Gómez-Blanco, A.; Ariza-López, F.J.; Ariza-López, I. From Point
Cloud to BIM: An Integrated Workﬂow for Documentation, Research and Modelling of Architectural Heritage. Surv. Rev. 2018,
50, 212–231. [CrossRef]
\90. Alshawabkeh, Y.; Baik, A.; Fallatah, A. As-Textured as-Built Bim Using Sensor Fusion, Zee Ain Historical Village as a Case Study.
Remote Sens. 2021, 13, 5135. [CrossRef]
\91. Gigliarelli, E.; Calcerano, F.; Cessari, L. Heritage Bim, Numerical Simulation and Decision Support Systems: An Integrated
Approach for Historical Buildings Retroﬁt. In Proceedings of the Energy Procedia, Matera, Italy, 12–13 May 2017; Volume 133.
\92. Pepe, M.; Costantino, D.; Alﬁo, V.S.; Restuccia, A.G.; Papalino, N.M. Scan to BIM for the Digital Management and Representation
in 3D GIS Environment of Cultural Heritage Site. J. Cult. Herit. 2021, 50, 115–125. [CrossRef]
\93. Barrile, V.; Fotia, A. A Proposal of a 3D Segmentation Tool for HBIM Management. Appl. Geomat. 2022, 14, 197–209. [CrossRef]

<!-- p. 25 -->

Heritage 2023, 6 6714

\94. Moyano, J.; León, J.; Nieto-Julián, J.E.; Bruno, S. Semantic Interpretation of Architectural and Archaeological Geometries: Point
Cloud Segmentation for HBIM Parameterisation. Autom. Constr. 2021, 130, 103856. [CrossRef]
\95. Colucci, E.; Xing, X.; Kokla, M.; Mostafavi, M.A.; Noardo, F.; Spanò, A. Ontology-Based Semantic Conceptualisation of Historical
Built Heritage to Generate Parametric Structured Models from Point Clouds. Appl. Sci. 2021, 11, 2813. [CrossRef]
\96. Nieto-Julián, J.E.; Farratell, J.; Bouzas Cavada, M.; Moyano, J. Collaborative Workﬂow in an HBIM Project for the Restoration and
Conservation of Cultural Heritage. Int. J. Archit. Herit. 2022, 16, 1–20. [CrossRef]
\97. Román, J.; Lerones, P.M.; Llamas, J.; Zalama, E.; Gómez-García-Bermejo, J. Towards the automatic 3D parametrization of non-
planar surfaces from point clouds in HBIM applications. In Proceedings of the International Archives of the Photogrammetry,
Remote Sensing and Spatial Information Sciences—ISPRS Archives, Ávila, Spain, 1–5 September 2019; Volume 42.
\98. Argiolas, R.; Bagnolo, V.; Cera, S.; Sanna, G. Analytical representation of architectural built heritage. A sketch-to-BIM approach.
In Proceedings of the International Archives of the Photogrammetry, Remote Sensing and Spatial Information Sciences—ISPRS
Archives, Mantua, Italy, 2–4 March 2022; Volume 46.
\99. Quattrini, R.; Pierdicca, R.; Morbidoni, C. Knowledge-Based Data Enrichment for HBIM: Exploring High-Quality Models Using
the Semantic-Web. J. Cult. Herit. 2017, 28, 129–139. [CrossRef]
\100. López, F.J.; Lerones, P.M.; Llamas, J.; Gómez-García-Bermejo, J.; Zalama, E. A Framework for Using Point Cloud Data of Heritage
Buildings toward Geometry Modeling in A BIM Context: A Case Study on Santa Maria La Real De Mave Church. Int. J. Archit.
Herit. 2017, 11, 965–986. [CrossRef]
\101. Kyriakaki-Grammatikaki, S.; Stathopoulou, E.K.; Grilli, E.; Remondino, F.; Georgopoulos, A. Geometric primitive extraction from
semantically enriched point clouds. In Proceedings of the International Archives of the Photogrammetry, Remote Sensing and
Spatial Information Sciences—ISPRS Archives, Mantua, Italy, 2–4 March 2022; Volume 46.
\102. Picone, R. Universal Design and Interoperable Digital Platforms Between Conservation and New Fruition Opportunities. The
Case Study of Arianna’s Domus in Pompeii. In Proceedings of the International Conference on Universal Design: Transforming
our World through Universal Design for Human Development, Brescia, Italy, 7–9 September 2022; pp. 459–466.
\103. Walsh, M.; Bernardello, R.A. Heritage Visualisation and Potential Speculative Reconstructions in Digital Space: The Medieval
Church of St. Anne in Famagusta, Cyprus. DISEGNARECON 2018, 11.
\104. Angulo, R.; Pinto, F.; Rodríguez, J.; Palomino, A. Digital Anastylosis of the Remains of a Portal by Master Builder Hernán Ruiz:
Knowledge Strategies, Methods and Modelling Results. Digit. Appl. Archaeol. Cult. Herit. 2017, 7, 32–41. [CrossRef]
\105. Rufﬁno, P.A.; Permadi, D.; Gandino, E.; Haron, A.; Osello, A.; Wong, C.O. Digital Technologies for Inclusive Cultural Heritage:
The Case Study of Serralunga d’alba Castle. In Proceedings of the ISPRS Annals of the Photogrammetry, Remote Sensing and
Spatial Information Sciences, Ávila, Spain, 1–5 September 2019; Volume 4.
\106. Nieto-Julián, J.E.; Antón, D.; Moyano, J.J. Implementation and Management of Structural Deformations into Historic Building
Information Models. Int. J. Archit. Herit. 2020, 14, 1384–1397. [CrossRef]
\107. Prizeman, O.; Jones, C.B.; Parisi, M.; Pezzica, C. How Can Century-Old Architectural Hierarchies for the Design of Public
Libraries Be Re-Interpreted and Re-Used? J. Cult. Herit. Manag. Sustain. Dev. 2018, 8, 481–494. [CrossRef]
\108. Chiabrando, F.; Lo Turco, M.; Santagati, C. Digital Invasions: From Point Clouds to Historical Building Object Modeling (h-BOM)
of a Unesco WHL Site. In Proceedings of the International Archives of the Photogrammetry, Remote Sensing and Spatial
Information Sciences—ISPRS Archives, Nafplio, Greece, 1–3 March 2017; Volume 42.
\109. Capone, M.; Lanzara, E. Parametric Library for Ribbed Vaults Indexing. In Proceedings of the International Archives of the
Photogrammetry, Remote Sensing and Spatial Information Sciences—ISPRS Archives, Beijing, China, 28 August–1 September
2021; Volume 46.
\110. Capone, M.; Lanzara, E. Scan-to-BIM vs 3D ideal model HBIM: Parametric tools to study domes geometry. In Proceedings of
the ISPRS Annals of the Photogrammetry, Remote Sensing and Spatial Information Sciences, Bergamo, Italy, 6–8 February 2019;
Volume 42.
\111. Murphy, M.; Meegan, E.; Keenaghan, G.; Chenaux, A.; Corns, A.; Fai, S.; Chow, L.; Zheng, Y.; Dore, C.; Scandurra, S.; et al. Shape
Grammar Libraries of European Classical Architectural Elements for Historic Bim. In Proceedings of the International Archives of
the Photogrammetry, Remote Sensing and Spatial Information Sciences—ISPRS Archives, Beijing, China, 28 August–1 September
2021; Volume 46.
\112. Bagnolo, V.; Argiolas, R.; Cuccu, A. Digital Survey and Algorithmic Modeling in HBIM. Towards a Library of Complex
Construction Elements. In Proceedings of the International Archives of the Photogrammetry, Remote Sensing and Spatial
Information Sciences—ISPRS Archives, Casablanca, Morocco, 10–11 October 2018; Volume 42.
\113. di Donato, D.; Morganti, R.; Tosone, A.; Abita, M. Procedural modelling for HBIM of Italian railways iron bridges. In Proceedings
of the International Archives of the Photogrammetry, Remote Sensing and Spatial Information Sciences—ISPRS Archives, Mantua,
Italy, 2–4 March 2022; Volume 46.
\114. Scianna, A.; Gaglio, G.F.; La Guardia, M. BIM Modelling of Ancient Buildings. In Proceedings of the Lecture Notes in Computer
Science (including subseries Lecture Notes in Artiﬁcial Intelligence and Lecture Notes in Bioinformatics), Nicosia, Cyprus, 29
October–3 November 2018; Volume 11196 LNCS, pp. 344–355. [CrossRef]
\115. Oreni, D.; Brumana, R.; Georgopoulos, A.; Cuca, B. HBIM for Conservation and Management of Built Heritage: Towards a
Library of Vaults and Wooden Bean Floors. In Proceedings of the ISPRS Annals of the Photogrammetry, Remote Sensing and
Spatial Information Sciences, Strasbourg, France, 2–6 September 2013; Volume 2.

<!-- p. 26 -->

Heritage 2023, 6 6715

\116. Prizeman, O.E.C. HBIM and Matching Techniques: Considerations for Late Nineteenth- and Early Twentieth-Century Buildings.
J. Archit. Conserv. 2015, 21, 145–159. [CrossRef]
\117. Kontoudaki, A.; Georgopoulos, A. HBIM library development for a doric temple column. Int. Arch. Photogramm. Remote Sens.
Spat. Inf. Sci. 2022, XLIII-B2-2022, 1153–1158. [CrossRef]
\118. Baik, A. Heritage Building Information Modelling for Implementing UNESCO Procedures: Challenges, Potentialities, and Issues; Routledge:
London, UK, 2020.
\119. Cheng, Y.M.; Mou, C.C.; Lu, Y.C.; Yen, Y.N. HBIM in Cultural Heritage Conservation: Component Library for Woodwork in
Historic Buildings in Taiwan. In Proceedings of the Lecture Notes in Computer Science (Including Subseries Lecture Notes in
Artiﬁcial Intelligence and Lecture Notes in Bioinformatics), Nicosia, Cyprus, 29 October–3 November 2018; Volume 11196 LNCS,
pp. 376–385. [CrossRef]
\120. José López, F.; Martin Lerones, P.; Llamas, J.; Gómez-García-Bermejo, J.; Zalama, E. Semi-Automatic Generation of Bim Models
for Cultural Heritage. Int. J. Herit. Archit. Stud. Repairs Maintence 2017, 2, 293–302. [CrossRef]
\121. Brumana, R.; Condoleo, P.; Grimoldi, A.; Previtali, M. Towards a semantic based hub platform of vaulted systems: HBIM meets a
GEODB. In Proceedings of the ISPRS Annals of the Photogrammetry, Remote Sensing and Spatial Information Sciences, Milan,
Italy, 8–10 May 2019; Volume 42.
\122. Pinti, L.; Bonelli, S. A Methodological Framework to Optimize Data Management Costs and the Hand-Over Phase in Cultural
Heritage Projects. Buildings 2022, 12, 1360. [CrossRef]
\123. Chiabrando, F.; Sammartano, G.; Spanò, A. Historical buildings models and their handling via 3D survey: From points clouds to
user-oriented HBIM. Int. Arch. Photogramm. Remote Sens. Spat. Inf. Sci. 2016, XLI-B5, 633–640. [CrossRef]
\124. Oostwegel, L.J.N.; Jaud, Š.; Muhiˇc, S.; Malovrh Rebec, K. Digitalization of Culturally Signiﬁcant Buildings: Ensuring High-Quality
Data Exchanges in the Heritage Domain Using OpenBIM. Herit. Sci. 2022, 10, 10. [CrossRef]
\125. Diara, F.; Rinaudo, F. IFC Classiﬁcation for FOSS HBIM: Open Issues and a Schema Proposal for Cultural Heritage Assets. Appl.
Sci. 2020, 10, 8320. [CrossRef]
\126. Diara, F.; Rinaudo, F. From reality to parametric models of cultural heritage assets for HBIM. In Proceedings of the International
Archives of the Photogrammetry, Remote Sensing and Spatial Information Sciences—ISPRS Archives, Ávila, Spain, 1–5 September
2019; Volume 42.
\127. Beltramo, S.; Diara, F.; Rinaudo, F. Evaluation of an Integrative Approach between HBIM and Architecture History. In Proceedings
of the ISPRS Annals of the Photogrammetry, Remote Sensing and Spatial Information Sciences, Milan, Italy, 8–10 May 2019;
Volume 42.
\128. Richard Petrie IFC 4.3—A Major Milestone Introduction and Overview of the Current Status. Available online: https://www.
buildingsmart.org/ifc-4-3-a-major-milestone-introduction-and-overview-of-the-current-status/ (accessed on 13 February 2023).
\129. Delpozzo, D.; Treccani, D.; Appolonia, L.; Adami, A.; Scala, B. HBIM and thematic mapping: Preliminary results. In Proceedings
of the International Archives of the Photogrammetry, Remote Sensing and Spatial Information Sciences—ISPRS Archives, Mantua,
Italy, 2–4 March 2022; Volume 46.
\130. Hull, J.; Ewart, I.J. Conservation Data Parameters for BIM-Enabled Heritage Asset Management. Autom. Constr. 2020, 119, 103333.
[CrossRef]
\131. England, H. BIM for Heritage: Developing the Asset Information Model; Historic England: London, UK, 2019.
\132. Angulo-Fornos, R.; Castellano-Román, M. HBIM as Support of Preventive Conservation Actions in Heritage Architecture.
Experience of the Renaissance Quadrant Facade of the Cathedral of Seville. Appl. Sci. 2020, 10, 2428. [CrossRef]
\133. Cornaro, C.; Bovesecchi, G.; Calcerano, F.; Martinelli, L.; Gigliarelli, E. An HBIM Integrated Approach Using Non-Destructive
Techniques (NDT) to Support Energy and Environmental Improvement of Built Heritage: The Case Study of Palazzo Maffei
Borghese in Rome. Sustainability 2023, 15, 11389. [CrossRef]
\134. Delpozzo, D.; Appolonia, L.; Scala, B.; Adami, A. Federated HBIM models for cultural heritage: Survey model and conceptual
model. In Proceedings of the International Archives of the Photogrammetry, Remote Sensing and Spatial Information Sciences—
ISPRS Archives, Mantua, Italy, 2–4 March 2022; Volume 46.
\135. Lee, J.; Kim, J.; Ahn, J.; Woo, W. Context-Aware Risk Management for Architectural Heritage Using Historic Building Information
Modeling and Virtual Reality. J. Cult. Herit. 2019, 38, 242–252. [CrossRef]
\136. Croce, P.; Landi, F.; Puccini, B.; Martino, M.; Maneo, A. Parametric HBIM Procedure for the Structural Evaluation of Heritage
Masonry Buildings. Buildings 2022, 12, 194. [CrossRef]
\137. Calvano, M.; Martinelli, L.; Calcerano, F.; Gigliarelli, E. Parametric Processes for the Implementation of HBIM—Visual Program-
ming Language for the Digitisation of the Index of Masonry Quality. ISPRS Int. J. Geo-Inf. 2022, 11, 93. [CrossRef]
\138. Lo Turco, M.; Giovannini, E.C.; Tomalini, A. Parametric and Visual Programming BIM Applied to Museums, Linking Container
and Content. ISPRS Int. J. Geo-Inf. 2022, 11, 411. [CrossRef]
\139. Costantino, D.; Pepe, M.; Restuccia, A.G. Scan-to-HBIM for Conservation and Preservation of Cultural Heritage Building: The
Case Study of San Nicola in Montedoro Church (Italy). Appl. Geomat. 2021, 15, 607–621. [CrossRef]
\140. Banﬁ, F. The Integration of a Scan-To-HBIM Process in BIM Application: The Development of an Add-in to Guide Users in
Autodesk Revit. In Proceedings of the ISPRS Annals of the Photogrammetry, Remote Sensing and Spatial Information Sciences,
Milan, Italy, 8–10 May 2019; Volume 42.

<!-- p. 27 -->

Heritage 2023, 6 6716

\141. Logothetis, S.; Stylianidis, E. BIM Open Source Software (OSS) for the Documentation of Cultural Heritage. Virtual Archaeol. Rev.
2016, 7, 28–35. [CrossRef]
\142. Diara, F.; Rinaudo, F. Open Source HBIM for Cultural Heritage: A Project Proposal. In Proceedings of the International Archives
of the Photogrammetry, Remote Sensing and Spatial Information Sciences—ISPRS Archives, Riva del Garda, Italy, 4–7 June 2018;
Volume 42.
\143. Agustín, L.; Quintilla, M. Virtual reconstruction in BIM technology and digital inventories of heritage. In Proceedings of the
International Archives of the Photogrammetry, Remote Sensing and Spatial Information Sciences—ISPRS Archives, Ávila, Spain,
1–5 September 2019; Volume 42.
\144. Tommasi, C.; Fiorillo, F.; Jiménez Fernández-Palacios, B.; Achille, C. Access and WEB-sharing of 3D digital documentation of
environmental and architectural heritage. In Proceedings of the ISPRS Annals of the Photogrammetry, Remote Sensing and
Spatial Information Sciences, Bergamo, Italy, 6–8 February 2019; Volume 42.
\145. Werbrouck, J.; Pauwels, P.; Bonduel, M.; Beetz, J.; Bekers, W. Scan-to-Graph: Semantic Enrichment of Existing Building Geometry.
Autom. Constr. 2020, 119, 103286. [CrossRef]
\146. Quintilla, M.; Agustín, L. 3D Survey and Virtual Reconstruction of Heritage. The Case Study of the City Council and Lonja of
Alcañiz. Vitruvio 2021, 6, 12–25. [CrossRef]
\147. Gabriele, M.; Previtali, M. HBIM-GIS integration with an IFC-to-shapeﬁle approach: The palazzo trotti vimercate pilot case study.
In Proceedings of the ISPRS Annals of the Photogrammetry, Remote Sensing and Spatial Information Sciences, New York, NY,
USA, 11–14 October 2021; Volume 8.
\148. Colucci, E.; de Ruvo, V.; Lingua, A.; Matrone, F.; Rizzo, G. HBIM-GIS Integration: From IFC to CityGML Standard for Damaged
Cultural Heritage in a Multiscale 3D GIS. Appl. Sci. 2020, 10, 1356. [CrossRef]
\149. Matrone, F.; Colucci, E.; De Ruvo, V.; Lingua, A.; Spanò, A. HBIM in a Semantic 3D GIS Database. In Proceedings of the ISPRS
Annals of the Photogrammetry, Remote Sensing and Spatial Information Sciences, Milan, Italy, 8–10 May 2019; Volume 42.
\150. Murphy, M.; Pavia, S.; Cahill, J.; Lenihan, S.; Corns, A. An Initial Design Framework for Virtual Historic Dublin. In Proceedings
of the ISPRS Annals of the Photogrammetry, Remote Sensing and Spatial Information Sciences, Milan, Italy, 8–10 May 2019;
Volume 42.
\151. Bruno, N.; Rechichi, F.; Achille, C.; Zerbi, A.; Roncella, R.; Fassi, F. Integration of Historical GIS Data in a HBIM System.
In Proceedings of the International Archives of the Photogrammetry, Remote Sensing and Spatial Information Sciences—ISPRS
Archives, XXIV ISPRS Congress, Nice, France, 31 August–2 September2020; Volume XLIII-B4-2020.
\152. Tsilimantou, E.; Delegou, E.T.; Nikitakos, I.A.; Ioannidis, C.; Moropoulou, A. GIS and BIM as Integrated Digital Environments for
Modeling and Monitoring of Historic Buildings. Appl. Sci. 2020, 10, 1078. [CrossRef]
\153. UNESCO; International Centre for the Study of the Preservation and Restoration of Cultural Property. The Nara Document on
Authenticity (1994); UNESCO: Paris, France, 1994.
\154. Esponda, M.; Piraino, F.; Stanga, C.; Mezzino, D. Log houses in les laurentides. From oral tradition to an integrated digital
documentation based on the re-discovery of the traditional constructive-geographical ‘repertoires’ through digital BIM data
archive. ISPRS Ann. Photogramm. Remote Sens. Spat. Inf. Sci. 2017, IV-2/W2, 75–82. [CrossRef]
\155. Gargaro, S.; del Giudice, M.; Rufﬁno, P.A. Towards a Multi-Functional HBIM Model. SCIRES-IT 2018, 8, 49–58. [CrossRef]
\156. Brumana, R.; Ioannides, M.; Previtali, M. Holistic Heritage Building Information Modelling (HBIM): From Nodes to Hub
Networking, Vocabularies and Repositories. In Proceedings of the ISPRS Annals of the Photogrammetry, Remote Sensing and
Spatial Information Sciences, Milan, Italy, 8–10 May 2019; Volume 42.
\157. ISO 21127:2014; Information and Documentation—A Reference Ontology for the Interchange of Cultural Heritage Information.
International Organisation for Standardisation: Geneva, Switzerland, 2020.
\158. Kuo, C.L.; Cheng, Y.M.; Lu, Y.C.; Lin, Y.C.; bin Yang, W.; Yen, Y.N. A Framework for Semantic Interoperability in 3D Tangible
Cultural Heritage in Taiwan. In Proceedings of the Lecture Notes in Computer Science (including subseries Lecture Notes in
Artiﬁcial Intelligence and Lecture Notes in Bioinformatics), Nicosia, Cyprus, 29 October–3 November 2018; Volume 11197 LNCS.
\159. Ciuffreda, A.L.; Coli, M.; Donigaglia, T.; Mariotti, P.I.; Salvatici, T.; Simoni, G. The Tarantola Etruscan Pediment: NDT and 3D
Model Content. In Proceedings of the COMPDYN Proceedings, Athens, Greece, 28–30 June 2021; Volume 1, pp. 1153–1169.
[CrossRef]
\160. Brumana, R.; Banﬁ, F.; Cantini, L.; Previtali, M.; Della Torre, S. HBIM Level of Detail-Geometry-Accuracy and Survey Analysis for
Architectural Preservation. In Proceedings of the ISPRS Annals of the Photogrammetry, Remote Sensing and Spatial Information
Sciences, Milan, Italy, 8–10 May 2019; Volume 42.
\161. Trizio, I.; Marra, A.; Savini, F.; Fabbrocino, G. Survey methodologies and 3D modelling for conservation of historical masonry
bridges. In Proceedings of the ISPRS Annals of the Photogrammetry, Remote Sensing and Spatial Information Sciences, Beijing,
China, 28 August–1 September 2021; Volume 8.
\162. Malinverni, E.S.; Mariano, F.; Di Stefano, F.; Petetta, L.; Onori, F. Modelling in HBIM to Document Materials Decay by a Thematic
Mapping to Manage the Cultural Heritage: The Case of “Chiesa Della Pietà” in Fermo. In Proceedings of the ISPRS Annals of the
Photogrammetry, Remote Sensing and Spatial Information Sciences, Milan, Italy, 8–10 May 2019; Volume 42.
\163. Coli, M.; Ciuffreda, A.L.; Micheloni, M. An Informative Content 3d Model for the Hall Holding the Resurrection of Christ by
Piero Della Francesca Mural Painting at Sansepolcro, Italy. In Proceedings of the ISPRS Annals of the Photogrammetry, Remote
Sensing and Spatial Information Sciences, Milan, Italy, 8–10 May 2019; Volume 42.

<!-- p. 28 -->

Heritage 2023, 6 6717

\164. León-Robles, C.A.; Reinoso-Gordo, J.F.; González-Quiñones, J.J. Heritage Building Information Modeling (H-BIM) Applied to a
Stone Bridge. ISPRS Int. J. Geo-Inf. 2019, 8, 121. [CrossRef]
\165. Heesom, D.; Boden, P.; Hatﬁeld, A.; Rooble, S.; Andrews, K.; Berwari, H. Developing a Collaborative HBIM to Integrate Tangible
and Intangible Cultural Heritage. Int. J. Build. Pathol. Adapt. 2021, 39, 72–95. [CrossRef]
\166. Slocombe, M. The SPAB Approach to the Conservation and Repair of Old Buildings; The Society for the Protection of Ancient Buildings:
London, UK, 2022.
\167. Historic England. Conservation Principles, Policies and Guidance; Historic England: London, UK, 2008.
\168. Adami, A.; Fregonese, L.; Rosignoli, O.; Scala, B.; Taffurelli, L.; Treccani, D. Geometric survey data and historical sources
interpretation for HBIM process: The case of mantua cathedral façade. Int. Arch. Photogramm. Remote Sens. Spat. Inf. Sci. 2019,
XLII-2/W11, 29–35. [CrossRef]
\169. Maiezza, P. As-Built Reliability in Architectural HBIM Modeling. In Proceedings of the ISPRS Annals of the Photogrammetry,
Remote Sensing and Spatial Information Sciences, Bergamo, Italy, 6–8 February 2019; Volume 42.
\170. Parisi, P.; Lo Turco, M.; Giovannini, E.C. The value of knowledge through h-BIM models: Historic documentation with a semantic
approach. In Proceedings of the ISPRS Annals of the Photogrammetry, Remote Sensing and Spatial Information Sciences,
Bergamo, Italy, 6–8 February 2019; Volume 42.
\171. Banﬁ, F.; Bolognesi, C.M.; Bonini, J.A.; Mandelli, A. The Virtual Historical Reconstruction of the Cerchia Dei Navigli of Milan:
From Historical Archives, 3D Survey and HBIM to the Virtual Visual Storytelling. In Proceedings of the International Archives of
the Photogrammetry, Remote Sensing and Spatial Information Sciences—ISPRS Archives, Beijing, China, 28 August–1 September
2021; Volume 46.
\172. Argiolas, R.; Bagnolo, V.; Cera, S.; Cuccu, S. Virtual environments to communicate built cultural heritage: A HBIM based
virtual tour. In Proceedings of the International Archives of the Photogrammetry, Remote Sensing and Spatial Information
Sciences—ISPRS Archives, Prague, Czech Republic, 7–8 February 2022; Volume 46.
\173. Udeaja, C.; Mansuri, L.E.; Makore, B.C.N.; Gyau Baffour Awuah, K.; Patel, D.A.; Trillo, C.; Jha, K.N. Digital Storytelling: The
Integration of Intangible and Tangible Heritage in the City of Surat, India. In Proceedings of the Lecture Notes in Computer
Science (Including subseries Lecture Notes in Artiﬁcial Intelligence and Lecture Notes in Bioinformatics), Virtual Event, 24–29
July 2021; Volume 12794.
\174. Banﬁ, F.; Brumana, R.; Stanga, C. A Content-Based Immersive Experience of Basilica of Sant’ambrogio in Milan: From 3d Survey
to Virtual Reality. In Proceedings of the ISPRS Annals of the Photogrammetry, Remote Sensing and Spatial Information Sciences,
Milan, Italy, 8–10 May 2019; Volume 42.
\175. Jouan, P.; Moray, L.; Hallot, P. Built heritage visualizations in immersive environments to support signiﬁcance assessments
by multiple stakeholders. In Proceedings of the International Archives of the Photogrammetry, Remote Sensing and Spatial
Information Sciences—ISPRS Archives, Mantua, Italy, 2–4 March 2022; Volume 46.
\176. Bolognesi, C.M.; Balin, S.; la Conca, A. Management of h-BIM model in holographic visualization. In Proceedings of the
International Archives of the Photogrammetry, Remote Sensing and Spatial Information Sciences—ISPRS Archives, Prague,
Czech Republic, 7–8 February 2022; Volume 46.
\177. Xi, W.; Cong, W. Remote Practice Methods of Survey Education for HBIM in the Post-Pandemic Era: Case Study of Kuiwen
Pavilion in the Temple of Confucius (Qufu, China). Appl. Sci. 2022, 12, 708. [CrossRef]
\178. Pybus, C.; Graham, K.; Doherty, J.; Arellano, N.; Fai, S. New realities for Canada’s parliament: A workﬂow for preparing heritage
bim for game engines and virtual reality. In Proceedings of the International Archives of the Photogrammetry, Remote Sensing
and Spatial Information Sciences—ISPRS Archives, Ávila, Spain, 1–5 September 2019; Volume 42.

Disclaimer/Publisher’s Note: The statements, opinions and data contained in all publications are solely those of the individual
author(s) and contributor(s) and not of MDPI and/or the editor(s). MDPI and/or the editor(s) disclaim responsibility for any injury to
people or property resulting from any ideas, methods, instructions or products referred to in the content.
