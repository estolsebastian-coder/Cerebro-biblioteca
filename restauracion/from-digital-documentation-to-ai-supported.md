---
type: libro
title: "From digital documentation to AI-supported decision making in architectural heritage conservation: k"
author: ""
categoria: "Restauración"
paginas: 24
extraccion: "texto"
fuente: "local:E:/Biblioteca digital/Restauración/From digital documentation to AI-supported.pdf"
convertido: 2026-10-16
---

# From digital documentation to AI-supported decision making in architectural heritage conservation: k

> Texto extraído de `Restauración\From digital documentation to AI-supported.pdf` (24 páginas, texto). El PDF original está en el disco E: (Biblioteca digital); `<!-- p. N -->` marca el inicio de cada página.

<!-- p. 1 -->

Journal of Asian Architecture and Building Engineering

ISSN: 1346-7581 (Print) 1347-2852 (Online) Journal homepage: www.tandfonline.com/journals/tabe20

From digital documentation to AI-supported
decision making in architectural heritage
conservation: knowledge structure, technological
convergence, and an integrated research
roadmap

Lu Xu, Jinhan Ren, Jiaxin Tan, Keyi Wu, Jinhua Liu, Yujie Li, Kun Sang &
Andrea Giordano

To cite this article: Lu Xu, Jinhan Ren, Jiaxin Tan, Keyi Wu, Jinhua Liu, Yujie Li, Kun Sang &
Andrea Giordano (30 Sep 2026): From digital documentation to AI-supported decision making
in architectural heritage conservation: knowledge structure, technological convergence, and
an integrated research roadmap, Journal of Asian Architecture and Building Engineering, DOI:
10.1080/13467581.2026.2739676

To link to this article: https://doi.org/10.1080/13467581.2026.2739676

© 2026 The Author(s). Published by Informa
UK Limited, trading as Taylor & Francis
Group on behalf of the Architectural
Institute of Japan, Architectural Institute of
Korea and Architectural Society of China.

Published online: 30 Sep 2026.

Submit your article to this journal

Article views: 61

View related articles

View Crossmark data

Full Terms & Conditions of access and use can be found at
https://www.tandfonline.com/action/journalInformation?journalCode=tabe20

<!-- p. 2 -->

JOURNAL OF ASIAN ARCHITECTURE AND BUILDING ENGINEERING
https://doi.org/10.1080/13467581.2026.2739676

ARCHITECTURAL HISTORY AND THEORY

From digital documentation to AI-supported decision making in architectural
heritage conservation: knowledge structure, technological convergence, and
an integrated research roadmap

Lu Xu a, Jinhan Rena, Jiaxin Tanb, Keyi Wuc, Jinhua Liua, Yujie Lia, Kun Sang d and Andrea Giordano e

aSchool of Architecture and Civil Engineering, Xihua University, Chengdu, China; bEdinburgh School of Architecture and Landscape
Architecture (ESALA), The University of Edinburgh, Edinburgh, UK; cDepartment of Art and Media Technology, University of Southampton,
Winchester, UK; dSchool of Hospitality, Tourism and Events, Taylor’s University, Subang Jaya, Malaysia; eDepartment of Civil,
Environmental and Architectural Engineering, University of Padua, Padua, Italy

ABSTRACT ARTICLE HISTORY
Architectural heritage conservation increasingly relies on digital records, structured informa Received 16 May 2026
tion management, and computational support for diagnosis, monitoring, and decision-making. Accepted 18 September 2026
However, research remains dispersed across photogrammetry, laser scanning, BIM/HBIM, KEYWORDS
digital twins, sensor monitoring, and artificial intelligence (AI), each serving different functions Architectural heritage
within conservation workflows. This study conducts a bibliometric and visual analysis of 892 conservation; digital
peer-reviewed publications retrieved from the Web of Science Core Collection for 2002–2024. documentation; artificial
Bibliometrix was used to examine publication trends and source characteristics, VOSviewer to intelligence; HBIM;
map collaboration and keyword networks, and CiteSpace to identify co-citation structures, bibliometric analysis
burst terms, and thematic transitions. The results show a shift from documentation-centred
research toward a layered conservation logic linking digital documentation, semantic informa
tion modelling, dynamic monitoring, and AI-supported assessment. BIM/HBIM, laser scanning,
photogrammetry, and 3D modelling remain the dominant knowledge base, while AI applica
tions are emerging in visual inspection, damage recognition, point-cloud classification, struc
tural health monitoring, predictive maintenance, and decision support. The study distinguishes
digitalization from AI and proposes an integrated roadmap from digital documentation to AI-
supported decision-making for evidence-based, preventive, and lifecycle-oriented architectural
heritage conservation.

\1. Introduction
Over the past two decades, digital technologies
Architectural heritage constitutes an irreplaceable have substantially transformed the ways in which
record of historical experience, cultural identity, con architectural heritage is recorded, analysed, inter
struction knowledge, material craftsmanship, and col preted, and managed. Laser scanning and photogram
lective memory. Its conservation is therefore not metry have become widely adopted for geometric
merely a technical undertaking, but also a cultural, survey and three-dimensional documentation, as they
social, and ethical responsibility. Many heritage build enable complex historical forms to be captured with
ings are exposed to progressive deterioration caused high levels of accuracy, density, and detail (Historic
by material ageing, environmental change, inappropri England 2017; Remondino 2011; Remondino and Rizzi
ate use, urban development pressure, and inadequate 2010). Building Information Modelling (BIM) and
maintenance. Previous studies have emphasized that Historic Building Information Modelling (HBIM) have
heritage conservation requires accurate documenta further introduced the possibility of connecting geo
tion, long-term monitoring, and context-sensitive metric models with semantic, historical, material, and
intervention, rather than isolated repair actions or epi maintenance-related information (Dore and Murphy
sodic restoration campaigns (Tejedor et al. 2022). In 2017; Fai et al. 2011; Murphy, McGovern, and Pavia
practice, however, conservation work still often relies 2009; Banfi 2021). More recently, digital twins, the
on manual inspection, fragmented documentation, Internet of Things (IoT), and sensor-based monitoring
and project-based restoration records, which may be have extended the focus of digital heritage research
insufficient when continuous monitoring, systematic from static documentation toward dynamic observa
information management, and timely decision- tion, simulation, and lifecycle management (Boje et al.
making are required. 2020; Rolim et al. 2024; Mazzetto 2024).

CONTACT Kun Sang kun.sang@taylors.edu.my School of Hospitality, Tourism and Events, Taylor’s University, Subang Jaya, Selangor 47500,
Malaysia

© 2026 The Author(s). Published by Informa UK Limited, trading as Taylor & Francis Group on behalf of the Architectural Institute of Japan, Architectural Institute of Korea and
Architectural Society of China.
This is an Open Access article distributed under the terms of the Creative Commons Attribution-NonCommercial License (http://creativecommons.org/licenses/by-nc/4.0/), which
permits unrestricted non-commercial use, distribution, and reproduction in any medium, provided the original work is properly cited. The terms on which this article has been
published allow the posting of the Accepted Manuscript in a repository by the author(s) or with their consent.

<!-- p. 3 -->

2 L. XU ET AL.

Artificial intelligence has introduced a further increasing, but how documentation, information
layer of methodological change. Machine learning, modelling, monitoring, AI-based diagnosis, and con
deep learning, computer vision, and data-driven pre servation decision-making are functionally con
diction are increasingly used to support crack detec nected. Table 1 summarizes the positioning of the
tion, surface deterioration assessment, structural present study in relation to these review streams and
diagnosis, point-cloud classification, semantic seg identifies the specific gap addressed by a workflowmentation, risk evaluation, and preventive mainte oriented bibliometric interpretation.
nance (Cha et al. 2017; Grilli and Remondino 2019). Against this background, this study develops
Recent reviews on machine learning for structural a bibliometric and conceptual review of the transition
health monitoring and AI-assisted visual inspection from digital documentation to AI-supported decisionin cultural heritage demonstrate that AI is becoming making in architectural heritage conservation. The ana
more visible in heritage diagnosis, although its appli lysis does not treat publication growth, keyword fre
cations remain unevenly distributed and often quencies, or software-generated clusters as ends in
depend on limited, heterogeneous, and labour- themselves. Instead, it uses bibliometric evidence to
intensive training datasets (Sony et al. 2021; Mishra clarify how documentation, semantic modelling, mon
2021; Mishra and Lourenco 2024). itoring, diagnosis, prediction, and decision support are
It is therefore important to distinguish between functionally connected in conservation practice.
digitalization and AI. In architectural heritage conser Specifically, this study makes four contributions.
vation, digitalization refers primarily to the acquisition, First, it maps the long-term development of digitaliza
modelling, storage, visualization, and management of tion- and AI-related research in architectural heritage
heritage information. Photogrammetry, laser scanning, conservation using 892 publications retrieved from the
point-cloud processing, BIM/HBIM, and digital archives Web of Science Core Collection. Second, it identifies
mainly belong to this domain. AI, by contrast, refers to major knowledge clusters and research hotspots,
computational methods that learn patterns, classify including BIM/HBIM, laser scanning, photogrammetry,
conditions, predict risks, or support decisions on the 3D reconstruction, digital twins, monitoring systems,
basis of data. The two domains are closely connected, and AI-assisted diagnosis. Third, it provides a more
because AI methods require reliable and structured critical interpretation of the maturity, constraints, and
digital datasets, but they are not equivalent. Treating practical adoption of AI applications in heritage con
them as a single category may obscure their different servation. Fourth, it proposes an integrated research
roles within conservation workflows. roadmap that connects digital documentation, seman
A growing body of reviews and bibliometric stu tic information modelling, IoT-enabled monitoring,
dies has examined digital heritage, HBIM, sensors, digital twins, AI-based diagnosis, and conservation
digital twins, AI, and IoT in cultural heritage contexts decision support.
(Bastem and Cekmis 2022; Harisanty et al. 2024; The study is guided by the following research
Puerto et al. 2024; Yu et al. 2025). These studies questions:
have provided valuable insights into publication
trends, collaboration networks, and thematic clusters. Q1: How has research on digital documentation and
However, many of them focus either on a single AI-supported architectural heritage conservation
technology, such as HBIM or sensor integration, or evolved from 2002 to 2024?
on cultural heritage in a broad sense, including
museums, archaeology, tourism, intangible heritage, Q2: What are the main knowledge clusters, technolo
and digital interpretation. Consequently, the specific gical foundations, and emerging topics in this field?
workflow logic of architectural heritage conservation
has not been sufficiently distinguished. The central Q3: How are digital documentation, information mod
question is not only which technologies are elling, monitoring, and AI-supported analysis

Table 1. Positioning of the present study in relation to existing review streams.

Review stream Typical focus Remaining gap addressed by this study
HBIM and digital Survey-to-HBIM workflows, point clouds, semantic They clarify modelling techniques but often pay less attention to
documentation reviews enrichment, and information management AI-supported diagnosis and decision-making.
AI, visual inspection, and Machine learning, deep learning, damage detection, They deepen AI methods but usually do not map the wider
SHM reviews and structural health monitoring architectural heritage knowledge structure.
IoT, digital twin, and Monitoring, lifecycle data, simulation, and They explain dynamic data systems but may not connect them to
sensor-oriented reviews environmental management bibliometric evidence across the field.
General cultural heritage Publication trends, keyword clusters, and collaboration They often cover cultural heritage broadly and do not distinguish
bibliometrics networks architectural conservation workflows.
Present study Bibliometric mapping interpreted through It links digital documentation, HBIM, IoT/digital twins, AI-
conservation workflow logic supported diagnosis, and conservation decision support.

<!-- p. 4 -->

JOURNAL OF ASIAN ARCHITECTURE AND BUILDING ENGINEERING 3

integrated into architectural heritage conservation applying the English-language restriction, 1,281
workflows? records remained. Finally, manual screening of titles,
abstracts, and keywords was conducted to exclude
Q4: What research gaps, implementation challenges, records that were not directly related to architectural
and future directions remain for the development of heritage conservation, as well as three retracted pub
intelligent and sustainable heritage conservation? lications. A final dataset of 892 publications was
retained for bibliometric and visual analysis.
As shown in Figure 1, the corpus was constructed
through a transparent sequence of retrieval, filtering,
\2. Data and methods and manual relevance screening rather than through
a single keyword query. The reduction from the initial
2.1. Data sources and search strategy Web of Science search to the final analytical dataset
This study used the Web of Science Core Collection as makes explicit the chronological, document-type, lan
the primary data source. The Web of Science Core guage, and relevance criteria that define the evidence
Collection was selected because it provides standar base. This procedure is methodologically important
dized bibliographic records, cited references, citation because the reliability of bibliometric maps, burst
metadata, and export formats that are widely used in detection, and thematic interpretation depends on
bibliometric and science-mapping research (Donthu the defensibility of the underlying corpus. The work
et al. 2021; Mongeon and Paul-Hus 2016). To enhance flow therefore strengthens the reproducibility of the
reliability, comparability, and academic relevance, the study and clarifies why the final dataset is appropriate
search was restricted to the Science Citation Index for examining digital and AI-related research in archi
Expanded, the Social Sciences Citation Index, and the tectural heritage conservation.
Arts & Humanities Citation Index.
The time span was set from 2002 to 2024 to capture
2.2. Bibliometric tools and data processingthe long-term development of digital documentation,
information modelling, monitoring, and AI-related To examine the knowledge structure and developmen
research in architectural heritage conservation. The tal trajectory of the field, this study employed three
search was conducted on 15 February 2025. The search complementary bibliometric tools: CiteSpace,
strategy combined three groups of topic terms: archi VOSviewer, and Bibliometrix. CiteSpace was used to
tectural heritage objects, conservation-related actions, identify intellectual structures, citation bursts, research
and digital or AI-related technologies. The complete fronts, and temporal transitions (Kleinberg 2002; Chen
Web of Science topic-search query and screening pro 2006). VOSviewer was used to construct and visualize
cess are provided in Appendix to improve reproduci co-authorship, citation, and keyword co-occurrence
bility and methodological transparency. networks (Callon et al. 1983; Van Eck and Waltman
The initial search retrieved 1,356 records. After limit 2010). Bibliometrix was used for descriptive statistics,
ing the time span to 2002–2024, 1,333 records performance analysis, thematic mapping, source ana
remained. The dataset was then restricted to articles lysis, and thematic evolution (Aria and Cuccurullo
and review articles, resulting in 1,328 records. After 2017). The three tools were used for methodological

Figure 1. Data retrieval and screening workflow.

<!-- p. 5 -->

4 L. XU ET AL.

triangulation rather than as substitutes for one was still primarily exploratory. During this period, the
another. literature was mainly concerned with digital recording,
The retrieved records were processed in CiteSpace photogrammetry, 3D survey, and early information
v6.2.R4, VOSviewer v1.6.20, and Bibliometrix v4.1.3 in technologies for heritage documentation.
RStudio. Prior to analysis, duplicate records were As shown in Figure 2, publication growth occurred
removed and inconsistent terms were standardized. through identifiable stages rather than through
For example, “building information modelling”, “build a uniform upward trajectory. The sparse output before
ing information modeling”, and “BIM” were checked 2010 indicates an exploratory phase in which digital
and merged when they referred to the same concept. technologies were primarily used to improve recording
Similarly, “Historic Building Information Modelling”, accuracy, visualization, and basic heritage documenta
“Historic Building Information Modeling”, and “HBIM” tion. The gradual increase between 2011 and 2015
were standardized where appropriate. General terms reflects the diffusion of laser scanning, photogramme
with limited analytical value were excluded from key try, 3D modelling, and early BIM/HBIM approaches,
word-based interpretation. which began to shift documentation from
The analysis examined annual publication trends, a representational task toward a data-management
source distribution, country and institutional contribu problem. The acceleration after 2016, and particularly
tions, author productivity, collaboration networks, cita after 2020, corresponds to the wider uptake of HBIM,
tion structures, co-citation clusters, keyword co- digital twins, monitoring systems, sensors, and AIoccurrence, burst terms, and thematic evolution. related methods. This trend suggests that architectural
Network centrality was interpreted with reference to heritage conservation is increasingly organized around
integrated workflows that connect survey, modelling,established betweenness-centrality measures (Freeman
monitoring, analysis, and decision support.1977). Patterns that appeared consistently across multi
The sharp expansion after 2021 is especially meanple tools were treated as more robust evidence. This
ingful because it marks more than a simple increase in
cross-validation reduced overreliance on a single visua
publication volume. It suggests that digital heritage
lization or clustering result and allowed the bibliometric
research has become aligned with broader agendas
outputs to be interpreted in relation to conservation
in smart construction, cultural heritage informatics,
practice.
preventive conservation, and data-driven manage
ment. Publication output reached 207 records in
\3. Results and interpretation 2024, which indicates that digital documentation,
information modelling, monitoring, and AI-supported
3.1. Publication growth and citation dynamics
analysis have moved from peripheral technical topics
Annual publication output was used to trace the to central research concerns. The publication curve
expansion of knowledge production in digital and AI- therefore provides the first empirical indication of
related architectural heritage conservation. As shown a transition from episodic recording toward lifecyclein Figure 2, research activity remained limited between oriented and decision-oriented conservation research.
2002 and 2010. Annual output fluctuated between The two publication phases also indicate different
zero and nine publications, suggesting that the field forms of research maturity. In the earlier stage,

Figure 2. Annual publication output in the final dataset from 2002 to 2024.

<!-- p. 6 -->

JOURNAL OF ASIAN ARCHITECTURE AND BUILDING ENGINEERING 5

Figure 3. Citation distribution and annualized citation impact by publication year.

individual techniques were often discussed as tools for intellectual importance. Considered together, Figures
recording or visualization. In the later stage, the same 2 and 3 indicate that the field has expanded in both
techniques increasingly appear within integrated scale and conceptual density: publication output has
workflows that connect survey, modelling, monitoring, increased rapidly, while citation impact remains con
simulation, and decision-making. This change is central centrated around works that offer transferable meth
to the argument of the article because it shows that ods for documentation, modelling, and data
the field is shifting from technology adoption to work integration. The lower citation values for 2023–2024
flow integration. should therefore not be interpreted as evidence of
As shown in Figure 3, the citation analysis comple declining influence; they mainly reflect the short cita
ments the publication-count trend by examining how tion window of very recent publications.
influence is distributed at the level of individual pub The combined reading of cumulative citations and
lications. Panel A indicates a strongly uneven distribu annualized citation rates is particularly useful for eval
tion: a limited number of studies have accumulated uating recent AI-related work. Many studies on AI,
high citation counts and have helped establish the digital twins, and monitoring are too recent to have
methodological foundations of the field, whereas accumulated large citation counts, yet their position in
most publications have received more modest citation later publication years and their association with burst
attention. This pattern is typical of an emerging inter terms indicate an important emerging research front.
disciplinary domain in which transferable methodolo Citation impact therefore needs to be interpreted
gical contributions on survey, modelling, HBIM, and alongside thematic position, technological relevance,
heritage information management become reference and the recency of the research problem. This com
points for later applied studies. Citation distribution bined perspective avoids a purely retrospective view of
therefore adds an important interpretive layer to the influence and allows newly developing areas of AIoutput trend. Rapid publication growth alone does not supported conservation to be evaluated more fairly.
define the field; influential methodological contribu
tions also shape how later research problems are for
3.2. Country and institutional collaboration
mulated and how digital conservation workflows are
networks
standardized.
Panel B provides a more cautious interpretation by Country-level collaboration analysis reveals the geo
using annualized citation rates. This adjustment is graphical distribution of scientific production and
necessary because recent publications have had international knowledge exchange. The results show
much shorter windows in which to accumulate cita that 88 countries contributed to this research area,
tions, whereas older papers may appear more influen among which 24 produced at least 10 publications.
tial simply because they have been available for China ranks first with 249 publications, followed by
longer. The annualized trend still fluctuates, but it Italy with 199 and Spain with 138. This distribution
reduces the risk of equating citation age with reflects both the long-standing European research

<!-- p. 7 -->

6 L. XU ET AL.

Figure 4. Country collaboration network.

tradition in architectural conservation, photogramme knowledge exchange than their publication counts
try, digital survey, and HBIM, and the rapidly increasing alone would suggest. This difference between productiv
investment in digital heritage and intelligent conserva ity and connectivity shows that the field is unevenly
tion in China. integrated across regions and research communities.
As shown in Figure 4, the geography of research is Countries with high output may provide a large empirical
characterized by both concentration and interconnec base, while countries with high centrality may function as
tion. High-output countries form visible nodes, but the bridges between conservation science, architecture, engi
collaboration links indicate that methodological neering, computer science, and heritage management.
advances in heritage documentation, HBIM, geomatics, This distinction is important because digital and AIconservation engineering, and AI-supported analysis supported conservation requires both local case knowl
often develop through international knowledge edge and cross-border methodological transfer.
exchange. The network also points to differentiated For this reason, the collaboration map should be
regional strengths. European research has contributed read as a map of knowledge circulation rather than
extensively to conservation theory, HBIM, survey stan only a productivity map. Digital heritage research
dards, and architectural heritage documentation, while requires the movement of methods across institutional
recent growth in China reflects large-scale interest in and national boundaries: survey techniques, HBIM pro
digital heritage, intelligent construction, heritage mon tocols, monitoring devices, AI algorithms, and conser
itoring, and data-driven conservation. The country- vation standards are rarely developed within a single
level network therefore reveals not only where national system. The network therefore provides evi
research is produced, but also how different national dence that technological convergence is also organiza
research systems contribute to the methodological tional convergence.
diversification of the field. Figure 5 shifts the focus from national output to
As shown in Table 2, publication volume, however, organizational collaboration. The network shows that
does not fully capture collaborative influence. Network universities and research institutes with expertise in
centrality indicates that the United States and England architecture, geomatics, engineering, conservation
play stronger intermediary roles in international science, computer vision, and digital technologies

Table 2. Top countries by publication output and network centrality.

No. Publications Centrality First year Country
1 249 0.13 2008 China
2 199 0.27 2008 Italy
3 138 0.24 2002 Spain
4 52 0.08 2006 Portugal
5 45 0.56 2009 England
6 27 0.04 2015 South Korea
7 26 0.76 2002 USA
8 19 0.00 2011 Turkey
9 17 0.08 2011 France
10 17 0.24 2015 Egypt

<!-- p. 8 -->

JOURNAL OF ASIAN ARCHITECTURE AND BUILDING ENGINEERING 7

Figure 5. Institutional collaboration network.

Table 3. Top institutions by publication output.

No. Publications Centrality First year Institution
1 37 0.03 2016 University of Sevilla
2 26 0.22 2015 Southeast University - China
3 25 0.05 2016 Polytechnic University of Milan
4 23 0.08 2010 Consiglio Nazionale delle Ricerche (CNR)
5 20 0.07 2016 Polytechnic University of Turin
6 17 0.09 2014 Universidade de Lisboa
7 16 0.00 2018 Universitat Politecnica de Valencia
8 16 0.09 2002 University of Granada
9 16 0.00 2015 Egyptian Knowledge Bank
10 15 0.10 2006 Universidade do Minho

jointly shape the field. This institutional pattern supports therefore reveals a shift from single-discipline con
the view that architectural heritage conservation has servation studies toward multi-institutional plat
become an interdisciplinary research domain rather forms capable of linking field survey, digital
than a narrowly architectural specialty. Institutions that modelling, laboratory diagnosis, algorithmic analy
combine heritage expertise with technical capacity are sis, and policy-oriented conservation planning.
especially important because digital documentation, This institutional configuration also explains why
HBIM, monitoring, and AI-supported analysis cannot implementation remains uneven. Institutions with
be implemented effectively without cooperation strong technical resources may advance modelling or
between survey specialists, conservation professionals, algorithmic methods, while institutions with strong
engineers, computer scientists, and heritage managers. conservation expertise may provide field knowledge,
As shown in Table 3, European institutions such diagnostic criteria, and value-based decision frame
as the University of Sevilla, the Polytechnic works. A mature AI-supported conservation system
University of Milan, the Polytechnic University of requires these capacities to be combined rather than
Turin, and Universidade de Lisboa remain highly developed separately.
influential, especially in HBIM workflows, digital sur
vey, documentation standards, and conservation
3.3. Author collaboration and scholarly influence
management. Several Chinese institutions also
occupy visible positions in the network, reflecting Author-level analysis provides a more fine-grained
the integration of architectural heritage conserva view of research communities and intellectual influ
tion with civil engineering, digital modelling, com ence. Publication productivity and cited-author influ
puter vision, intelligent construction, and urban ence show a dual structure. Contemporary scholars
heritage management. The institutional network contribute to technical innovation in digital survey,

<!-- p. 9 -->

8 L. XU ET AL.

Figure 6. Author collaboration network.

HBIM, monitoring, and AI-supported analysis, while as HBIM, laser scanning, computer vision, and struc
international heritage organizations such as ICOMOS tural monitoring are being developed by partially over
and UNESCO remain central to the normative and lapping research teams with different disciplinary
ethical foundations of conservation research. backgrounds. The pattern helps explain why the field
As shown in Figure 6, author collaboration is dis has produced diverse technical solutions but has not
tributed across several communities rather than domi yet fully converged around shared datasets, evaluation
nated by a single centralized group. This fragmented protocols, or implementation standards. Collaboration
but expanding structure suggests that methods such is therefore both a strength and a challenge: it brings

Figure 7. Cited-author co-citation network.

<!-- p. 10 -->

JOURNAL OF ASIAN ARCHITECTURE AND BUILDING ENGINEERING 9

methodological diversity, while also increasing the how evidence is interpreted, how uncertainty is man
need for stronger cross-community validation, termi aged, and how interventions are justified. This is why
nology alignment, and reproducible workflows. expert supervision and conservation ethics remain
Figure 7 provides a complementary view of intellec central to the article’s interpretation of AI-supported
tual influence. The cited-author structure shows that decision-making.
technical work remains anchored in a broader conser
vation knowledge base that includes heritage charters,
\4. Keyword co-occurrence and thematic
authenticity debates, value assessment, and conserva
structure
tion ethics. AI-supported conservation should there
fore be understood as a human-guided decision- Keyword co-occurrence analysis identifies the concep
support process rather than as a fully automated sub tual structure of the field. Terms such as “cultural heri
stitute for professional judgement. The co-presence of tage”, “architectural heritage”, and “conservation”
technical authors and normative conservation refer occupy central positions, reflecting the disciplinary
ences indicates that the field cannot be assessed foundation of the literature. Technical terms such as
through algorithmic performance alone. It must also BIM, laser scanning, documentation, point cloud, 3D
address authenticity, reversibility, minimum interven model, and digital twin demonstrate the central role of
tion, stakeholder values, and the social meaning of digital technologies in recent research.
heritage places. As shown in Figure 8, the keyword co-occurrence
This result is significant because it shows that digital network identifies the conceptual vocabulary linking
and AI-related heritage conservation is not purely tech different strands of research. Terms such as heritage
nical. The field continues to depend on conservation conservation, BIM, point cloud, laser scanning, docu
charters, value assessment frameworks, authenticity mentation, digital twin, and artificial intelligence
debates, and professional norms (ICOMOS 1964). demonstrate that the field is organized around con
Future technological development therefore needs nected conservation functions: recording, modelling,
closer interaction between conservation theorists, digi monitoring, interpretation, and decision support.
tal technology specialists, structural engineers, heri These terms are not isolated technological labels.
tage managers, and public institutions. They form a sequence of research tasks in which accu
The cited-author network therefore provides rate documentation enables semantic modelling,
a necessary corrective to a purely technocentric read semantic modelling supports monitoring and simula
ing of the results. Even when the literature uses terms tion, and structured data create the conditions for AIsuch as artificial intelligence, digital twin, or computer assisted recognition, prediction, and decision-making.
vision, the ultimate conservation question concerns The co-occurrence structure therefore supports the

Figure 8. Keyword co-occurrence network.

<!-- p. 11 -->

10 L. XU ET AL.

Table 4. Top keywords by co-occurrence frequency.

No. Frequency Centrality First year Keyword
1 153 0.26 2010 cultural heritage
2 109 0.15 2007 architectural heritage
3 87 0.10 2009 conservation
4 75 0.15 2008 buildings
5 65 0.08 2013 built heritage
6 50 0.04 2020 industrial heritage
7 50 0.13 2018 BIM
8 43 0.06 2016 model
9 42 0.32 2017 historic buildings
10 39 0.05 2016 adaptive reuse

article’s central argument that digitalization and AI ecology. Data acquisition, semantic organization, and
should be interpreted through a workflow logic rather computational interpretation increasingly support one
than as separate research fashions. another. The presence of clusters related to laser scan
As shown in Table 4, the most frequent keywords ning, 3D modelling, artificial intelligence, historic build
combine core heritage terms with technical terms ings, and heritage documentation also suggests that the
related to documentation, modelling, and information field has developed through functional specialization.
management. The clustering results should not be Some clusters provide data foundations, some organize
read as a ranking of importance. Cluster labels gener heritage information, and others point toward diagnosis,
ated by CiteSpace summarize groups of strongly asso prediction, and management. This clustering pattern rein
ciated keywords, while cluster numbers indicate forces the need to examine not only individual technolo
software-assigned modular communities. The largest gies, but also their roles within conservation workflows.
clusters include heritage buildings, laser scanning, 3D As shown in Table 5, the presence of an artificial
modelling, artificial intelligence, 3D survey, and heri intelligence cluster does not mean that AI has already
tage documentation. These clusters show that the field become the dominant technology in the field. Rather, it
is organized around heritage objects, reality-based indicates that AI is emerging as a specialized analytical
documentation, semantic modelling, AI-supported layer within a broader knowledge base still led by doc
analysis, and conservation management. umentation, modelling, and information management.
Figure 9 further organizes the keyword structure into This distinction is important because it prevents AI from
thematic communities. The clusters indicate that heritage being treated as an isolated technological label and
objects, digital survey, modelling, AI, and documentation instead situates it within a cumulative conservation
are interdependent topics within a broader technical workflow. In practical terms, AI applications depend on

Figure 9. Keyword clustering network.

<!-- p. 12 -->

JOURNAL OF ASIAN ARCHITECTURE AND BUILDING ENGINEERING 11

Table 5. Main keyword clusters and their interpretive roles.

Cluster Size Silhouette Main keywords Interpretive role
\#0 heritage 30 0.915 adaptive reuse; refurbishment; building energy efficiency Connects conservation with reuse and
buildings sustainability
\#1 laser scanning 23 0.866 laser scanning; point cloud; photogrammetry Provides geometric documentation and survey
evidence
\#2 3D modelling 23 0.860 3D modelling; cultural heritage; industrial heritage; Supports visualization, interpretation, and data
augmented reality integration
\#3 artificial 21 0.807 artificial intelligence; digital heritage; digital twins; Indicates emerging intelligent diagnosis and
intelligence diagnostics; IoT decision support
\#4 historical 21 0.994 structural analysis; finite element methods; virtual testing Connects digital methods to structural assessment
structures
\#5 monuments 20 0.938 masonry structures; preventive conservation; architectural Links object typologies with preventive strategies
conservation

the availability of reliable images, point clouds, material long-term influence, while technical terms such as BIM,
records, monitoring data, and expert annotations. The laser scanning, 3D model, digital heritage, digital twins,
keyword clusters therefore show that the maturity of AI- and digital technology display stronger recent burst
supported conservation is inseparable from the maturity patterns. To make this temporal evidence explicit, the
of the preceding digital infrastructure. visual sequence first presents the keyword cluster time
Consequently, the keyword structure supports line (Figure 10), then an interpretive thematic roadmap
a layered interpretation of technological development. (Figure 11), and finally the keyword burst analysis
Documentation and survey terms identify the data- (Figure 12). This arrangement separates the empirical
capture layer, BIM/HBIM terms identify the semantic- science-mapping output from the conceptual synthesis
management layer, monitoring and digital-twin terms and strengthens the transparency of the interpretation.
identify the dynamic state-awareness layer, and AI- As shown in Figure 10, the keyword cluster timeline
related terms identify the diagnostic and predictive provides direct visual evidence of the temporal organi
layer. This layered reading provides the basis for the zation of research themes. Earlier clusters are anchored
integrated roadmap proposed later in the article. by architectural heritage, conservation, heritage docu
mentation, laser scanning, 3D survey, and 3D modelling,
indicating a documentation- and survey-oriented foun
4.1. Temporal evolution and research fronts dation. More recent clusters include artificial intelli
Temporal analysis shows that “cultural heritage”, “archi gence, digital modelling, built heritage, and decisiontectural heritage”, and “conservation” have maintained making-related terms, suggesting that the field is

Figure 10. Keyword cluster timeline showing thematic evolution from digital documentation to AI-supported conservation.

<!-- p. 13 -->

12 L. XU ET AL.

Figure 11. Thematic evolution from digital documentation to AI-supported conservation.

extending from documentation and modelling toward emerging research fronts and support the interpreta
monitoring, automated diagnosis, and decision-support tion that the field is moving toward more integrated
functions. The value of the timeline lies in connecting and decision-oriented digital conservation.
cluster structure with temporal development. It shows The combined temporal evidence from Figures 10–
not only which themes are present, but also when they 12 suggests that architectural heritage conservation has
gained prominence and how newer themes build on gradually moved from the creation of digital records
earlier data-capture and modelling traditions. toward the integration of dynamic data and decision-
Figure 11 synthesizes the temporal evidence into oriented analytics. Digital twins are especially important
four overlapping development stages. The diagram because they integrate geometric, semantic, diagnostic,
should not be read as a rigid periodization, because monitoring, and operational data. AI becomes relevant
documentation, modelling, monitoring, and AI con when these datasets are sufficiently structured to sup
tinue to coexist. Rather, it shows a cumulative logic in port pattern recognition, anomaly detection, deteriora
which reliable digital records provide the foundation tion prediction, and maintenance prioritization.
for semantic modelling, dynamic monitoring, AI- Therefore, the evidence does not suggest a simple
assisted diagnosis, and conservation decision support. replacement of documentation by AI; rather, it reveals
This synthesis also clarifies the framing of the study as a cumulative transformation in which AI depends on the
a movement from digital documentation to AI- quality, interoperability, and conservation relevance of
supported decision-making. The bibliometric evidence earlier digital infrastructures. This interpretation also
does not suggest that AI replaces earlier technologies; explains why AI appears as a growing but not yet domi
it indicates that AI becomes meaningful when earlier nant topic: the field is still building the data conditions
layers have generated structured, interpretable, and required for robust and accountable AI use.
monitorable heritage data. These three temporal figures also explain why the
As shown in Figure 12, keyword citation bursts offer article avoids presenting AI as a sudden disruption. AIa fine-grained view of research-front dynamics. Earlier related terms gain visibility after a long period in which
bursts such as 3D, methodology, conservation, historic the field developed robust documentation, modelling,
building, and point clouds indicate the consolidation and monitoring methods. The emergence of AI is there
of documentation and survey methods. Later bursts fore better understood as a downstream consequence
such as digital heritage, strategy, digital twins, and of data accumulation and workflow integration than as
digital technology reveal a shift toward integrated an independent technological turn.
platforms, lifecycle thinking, and decision-oriented
digital conservation. Burst intervals are analytically
4.2. Co-cited literature and journal knowledge
useful because they identify periods when particular
base
terms attracted concentrated attention, rather than
simply showing overall frequency. They therefore Co-citation analysis identifies the intellectual base of
help distinguish stable background vocabulary from the field (Small 1973). Highly cited references include

<!-- p. 14 -->

JOURNAL OF ASIAN ARCHITECTURE AND BUILDING ENGINEERING 13

Figure 12. Top 25 keywords with the strongest citation bursts.

works on multimodal technologies, HBIM, semantic modelling, and information integration, even as AIenrichment, heritage documentation, and digital sur related topics become more visible.
vey. These references confirm that the knowledge base Figure 13 shows the intellectual structure underlying
remains strongly grounded in documentation, the field. Co-cited references are concentrated around

Figure 13. Literature co-citation network.

<!-- p. 15 -->

14 L. XU ET AL.

HBIM, semantic enrichment, 3D documentation, survey- As shown in Figure 14, reference citation bursts
to-model workflows, and heritage information manage identify specific studies that experienced concentrated
ment, confirming that current discussions of AI rest on citation attention. These burst references are useful for
a substantial foundation of digital documentation and distinguishing enduring knowledge bases from tem
information modelling. The network also indicates that porary research fronts. The concentration of bursts
influential studies are connected by methodological around HBIM, semantic modelling, and digital survey
concerns rather than by heritage typology alone. In confirms that the movement toward AI-supported con
other words, the shared intellectual base is formed by servation has emerged through earlier advances in
problems of representation, interoperability, data man documentation, modelling, and information integra
agement, semantic modelling, and conservation deci tion. Recent burst references also indicate which meth
sion support. This helps explain why AI-related research odological discussions became influential during the
in heritage conservation must be evaluated in relation field’s expansion phase. Their prominence shows that
to data quality, semantic structure, and domain-specific the research community did not move directly from
interpretability. conservation theory to AI. Rather, it passed through
As summarized in Table 6, the most frequently co- a sequence of methodological developments that
cited documents are concentrated around multimodal made structured heritage data increasingly available
technologies, HBIM, remote sensing, semantic enrich for analysis, monitoring, and decision support.
ment, and heritage information management. This The reference burst analysis was re-exported and
document-level knowledge base provides a basis for cleaned to correct broken labels, improve readability,
interpreting Figure 13 and for understanding why the and align its colour logic with the keyword burst figure.
subsequent burst analysis in Figure 14 is dominated by The strongest bursts concentrate around studies on
methodological studies on documentation and infor HBIM, survey-to-model workflows, semantic enrich
mation integration. ment, heritage information modelling, and integration

Table 6. Frequently co-cited documents.

No. Citation frequency Centrality Year Document
1 36 0.02 2018 Lopez et al. (2018), Multimodal Technologies and Interaction, V2, P21
2 30 0.00 2018 S. Bruno, De Fino, and Fatiguso (2018), Automation in Construction, V86, P256
3 28 0.02 2018 Pocobelli DP, 2018, Heritage Science, V6
4 27 0.00 2020 Yang XC, 2020, Journal of Cultural Heritage, V46, P350
5 23 0.00 2018 Jordan-Palomar et al. (2018), Sustainability, V10
6 21 0.02 2015 Dore C, 2015, International Archives of Photogrammetry
7 20 0.01 2019 N. Bruno and Roncella (2019), Remote Sensing, V11
8 19 0.00 2018 Brumana R, 2018, Applied Geomatics, V10
9 19 0.00 2021 Croce et al. (2021), Remote Sensing, V13
10 18 0.00 2017 Quattrini R, 2017, Journal of Cultural Heritage, V28

Figure 14. Top 25 references with the strongest citation bursts.

<!-- p. 16 -->

JOURNAL OF ASIAN ARCHITECTURE AND BUILDING ENGINEERING 15

of diagnostic data. This reinforces the interpretation that Figure 15 reveals the journal-level knowledge base
AI-related work is emerging from, and depends upon, of the field. Journals associated with cultural heritage,
earlier advances in digital documentation and informa automation in construction, remote sensing, geo
tion modelling. The burst pattern also suggests that matics, and architectural conservation appear
methodological consolidation occurred before the together, demonstrating that the field draws on both
recent expansion of AI terminology: the field first devel heritage-oriented scholarship and technical domains
oped reliable means of capturing and organizing heri concerned with modelling, sensing, simulation, and
tage information, and only later began to explore digital analysis. This journal structure is important
automated interpretation and predictive decision because it shows that architectural heritage conserva
support. tion is not simply importing technologies from exter
The reference bursts also help clarify the relationship nal fields. It is selectively adapting methods from
between knowledge base and research frontier. construction informatics, remote sensing, engineering
Keyword bursts reveal what topics became visible, diagnostics, and digital humanities to address conser
while reference bursts show which publications sup vation-specific problems such as authenticity, dete
plied the conceptual or methodological basis for those rioration, monitoring, and intervention prioritization.
topics. Reading Figures 12 and 14 together therefore As shown in Table 7, the journal distribution shows
strengthens the conclusion that recent AI-oriented work that the field is interdisciplinary, connecting cultural
is grounded in earlier scholarship on digital survey, heritage, architecture, civil engineering, construction
HBIM, semantic enrichment, and heritage information informatics, remote sensing, geomatics, conservation
systems. science, and computational diagnostics. The journal

Figure 15. Journal co-citation network.

Table 7. Main cited journals in the knowledge base.

Citation
No. Cited journal frequency Country/region JCR 2024 IF
1 Journal of Cultural Heritage 468 France 3.5
2 Sustainability 303 Switzerland 3.3
3 International Journal of Architectural Heritage 251 USA 2.3
4 International Archives of Photogrammetry, Remote Sensing and Spatial Information 244 Germany –
Sciences
5 Automation in Construction 186 Netherlands 9.6
6 Remote Sensing 154 Switzerland 4.2
7 Buildings 137 Switzerland 3.1
8 Heritage Science 131 UK 2.5
9 ISPRS Journal of Photogrammetry and Remote Sensing 120 Netherlands 11.1
10 Applied Geomatics 88 Germany 2.2

<!-- p. 17 -->

16 L. XU ET AL.

Table 8. Maturity and challenges of AI applications in architectural heritage conservation.

AI application mode Typical methods Current maturity Main challenges for heritage conservation
Visual inspection and Computer Relatively active research area; Limited labelled datasets; heterogeneous
damage recognition vision, CNNs, object detection, increasing use for cracks and materials; lighting and occlusion; need for
semantic segmentation, UAV surface deterioration expert validation
imagery
Structural health Machine learning on vibration, Moderate maturity in engineering; Sparse monitoring records; sensor placement;
monitoring deformation, temperature, humidity, still context-sensitive for heritage uncertainty; interpretation under
and sensor data buildings conservation constraints
Point-cloud Supervised classification, deep learning, Growing relevance for HBIM Irregular geometry, missing data, non-standard
classification and segmentation, scan-to-HBIM automation and element components, and limited transferability
semantic assistance recognition across typologies
enrichment
Predictive Time-series models, deterioration Emerging; promising but rarely fully Longitudinal data scarcity; model
maintenance and prediction, anomaly detection, implemented in routine practice explainability; integration with maintenance
risk assessment decision support systems budgets and policy decisions
Knowledge integration Knowledge graphs, linked data, rule- Conceptually promising; still Interoperability, data governance, ethical
and decision based reasoning, human-in-the-loop underdeveloped in practice accountability, and alignment with
support AI conservation values

dual-map overlay provides a complementary visualiza adaptation, and domain-specific validation. Such trans
tion of cross-disciplinary citation trajectories. It should fer is not automatic. Methods originally developed for
not be interpreted as a direct classification of the sub medical imaging or engineering diagnostics must be
ject matter of the dataset. Rather, it visualizes citation reinterpreted in relation to heritage materials, surface
flows between disciplinary journal categories and deterioration, structural vulnerability, historical signifi
helps explain why methods from imaging, diagnostics, cance, and conservation ethics before they can inform
monitoring, and computational sciences increasingly decision-making in architectural heritage contexts.
enter architectural heritage conservation. This distinc This interpretation is particularly relevant to the
tion is essential because the presence of medicine- or reviewer concern about medicine-related categories. In
imaging-related categories does not indicate a topical the context of this dataset, these categories should be
deviation from heritage conservation; it indicates read as source domains for diagnostic reasoning, image
methodological borrowing from domains with mature interpretation, and pattern-recognition methods. The
diagnostic and image-analysis traditions. conservation task remains architectural heritage, but
Figure 16 should be interpreted as a citation- some of the analytical tools originate in fields that have
trajectory map rather than as a direct classification of longer experience with automated detection, classifica
the dataset’s subject matter. The appearance of medi tion, and risk assessment.
cine-, imaging-, or diagnostic-related categories reflects
methodological borrowing from adjacent fields, particu
\5. Discussion: from digital documentation to
larly in computer vision, image diagnosis, sensor-based
AI-supported decision making
monitoring, and pattern recognition. This pattern sup
ports the argument that AI-supported heritage conser Taken together, the results suggest that architec
vation develops through cross-disciplinary transfer, tural heritage conservation is not simply becoming

Figure 16. Journal dual-map overlay showing cross-disciplinary citation trajectories.

<!-- p. 18 -->

JOURNAL OF ASIAN ARCHITECTURE AND BUILDING ENGINEERING 17

more digital or more intelligent in a general sense. AI should not be understood as a replacement for
Rather, the field is developing through a layered conservation expertise. Its current value lies mainly
workflow in which each technological domain per in assisting inspection, screening risks, interpreting
forms a different conservation function. Digital monitoring data, and supporting decisions under
documentation produces reliable geometric and expert supervision.
visual evidence; HBIM and semantic modelling
organize that evidence into structured conserva
tion knowledge; IoT systems and digital twins 5.2. Maturity, challenges, and practical adoption
enable dynamic monitoring and lifecycle updates; of AI
AI methods support diagnosis, prediction, screen
The bibliometric results show that BIM/HBIM and
ing, and prioritization; and conservation decision
digital documentation dominate the field, while AI
support links these outputs to intervention plan
remains an emerging and unevenly mature
ning, maintenance governance, and long-term
research area. This does not weaken the relevance
stewardship.
of AI in the title; rather, it clarifies the develop
mental logic revealed by the evidence. AI is not yet
5.1. Why documentation, HBIM, digital twins, and the dominant knowledge base of architectural heri
AI gained prominence tage conservation, but it is becoming an important
decision-support layer built upon digital records
The prominence of digital documentation is driven by
and information models.
the need to record complex heritage forms with accu
Recent AI-related studies in cultural heritage have
racy, repeatability, and minimal physical intervention.
begun to move beyond general statements about digi
Photogrammetry, laser scanning, UAV survey, and
tal transformation and have examined more specific
point-cloud processing provide the geometric founda
diagnostic tasks, data modalities, and implementation
tion for condition mapping, deformation measure
challenges. Beyond building-focused diagnosis,
ment, reconstruction, and archival documentation.
machine-learning approaches have also been explored
Their importance is therefore not merely technological;
for cultural heritage landscape design under sparse-data
it responds to the conservation need for reliable evi
conditions (Goodarzi et al. 2023). Mishra (2021)
dence before intervention.
reviewed machine learning techniques for structural
The rise of HBIM can be explained by the fragmenta
health monitoring of heritage buildings and showed
tion of conservation information. Heritage projects
that ML models can support the interpretation of
often involve drawings, photographs, survey data,
laboratory data, field observations, non-destructive test
material records, damage maps, intervention histories,
ing results, and monitoring data for condition assess
value assessments, and maintenance notes stored in
ment and damage diagnosis. Mishra and Lourenco
separate formats. HBIM offers a platform for linking
(2024) further synthesized AI-assisted visual inspection
geometry with semantic, historical, material, and diag
for cultural heritage, with particular attention to image
nostic information. Its growing centrality reflects the
processing, deep learning, computer vision, UAV-based
need to transform digital records into manageable con
inspection, damage identification, and structural health
servation knowledge.
monitoring. Mishra and Doria (2026) extended this
The emergence of IoT and digital twins is associated
direction by discussing the integration of virtual reality
with a shift from episodic restoration to preventive and
and AI-assisted visual inspection, which is relevant to
lifecycle-oriented conservation. Many deterioration
future immersive inspection workflows and humanprocesses, such as moisture-related decay, salt crystal
machine collaboration.
lization, thermal stress, structural deformation, and
A complementary body of recent scholarship by
biological growth, are dynamic rather than static. IoT-
Sharma and by Colace and collaborators further clari
based monitoring can capture environmental and
fies the scope of AI applications in cultural heritage.
structural conditions over time, while digital twins
Sharma (2026) offers a comprehensive review of AI and
can integrate these data into updated models for inter
machine learning for the preservation and analysis of
pretation, simulation, and decision support
heritage structures, organizing applications around(Laohaviraphap and Waroonkun 2024). This provides
structural analysis, damage detection, monitoring,a practical justification for IoT-based systems in archi
and restoration. Fontanella et al. (2020) highlight thetectural heritage conservation.
AI has gained attention because digital docu relevance of pattern recognition and artificial intelli
mentation, HBIM, and monitoring systems generate gence techniques for cultural heritage, while Casillo
large volumes of images, point clouds, sensor et al. (2022) demonstrate how IoT-based systems and
streams, and structured records. These data create deep learning can be combined to protect cultural
opportunities for automated recognition, classifica heritage buildings. Colace et al. (2025) further empha
tion, anomaly detection, and prediction. However, size new AI challenges for cultural heritage protection,

<!-- p. 19 -->

18 L. XU ET AL.

including predictive maintenance, deep learning, pat agenda for AI-supported architectural heritage
tern recognition, and the need for stronger collabora conservation.
tion between technical experts and conservation As shown in Figure 17, the bibliometric evidence
professionals. As summarized in Table 8, these AI appli can be synthesized into a layered research roadmap for
cations differ considerably in their current maturity, architectural heritage conservation. The roadmap
data requirements, interpretability, and practical chal begins with reliable data capture and semantic infor
mation modelling, incorporates monitoring and digilenges for architectural heritage conservation.
tal-twin updates, and then applies AI to diagnosis, Three limitations are especially important. First,
prediction, prioritization, and decision support. Theheritage datasets are typically smaller, more heteroge
feedback loop highlights that expert validation andneous, and less standardized than datasets used in
conservation outcomes must continually refine data,mainstream computer vision. Second, architectural
models, and decision rules. This structure keeps comheritage objects vary by material, construction techni
putational intelligence accountable to conservationque, age, climate, repair history, and cultural context,
principles, including authenticity, minimum intervenwhich reduces model generalizability. Third, conserva
tion, reversibility, material specificity, and public value.tion decisions involve values, authenticity, reversibility,
The roadmap therefore frames AI not as an autonominimum intervention, stakeholder participation, and
mous replacement for expertise, but as one compolegal responsibilities. For these reasons, AI applications
nent within a wider evidence-based and ethicallyshould be designed as human-in-the-loop systems
governed conservation workflow.that support, rather than replace, expert judgement.
The roadmap emphasizes that AI-supported conser
vation cannot be developed independently of data
quality, semantic interoperability, and conservation
5.3. Integrated research roadmap
governance. Reliable AI requires documented heritage
Based on the bibliometric evidence and the preceding conditions, standardized metadata, interoperable
interpretation, this study proposes an integrated road HBIM or linked-data structures, and feedback from
map for future research. The roadmap is organized monitoring and expert validation. Conversely, the
around five connected layers: digital documentation, results of AI-assisted diagnosis should feed back into
semantic information modelling, dynamic monitoring documentation, maintenance planning, and future
and digital twins, AI-supported diagnosis and predic model training. This cyclical logic is essential for avoid
tion, and conservation decision support. Figure 17 ing a purely tool-driven understanding of AI and for
adds a conceptual element beyond conventional bib ensuring that intelligent systems remain accountable
liometric mapping by translating keyword, burst, and to conservation principles such as authenticity, mini
co-citation patterns into a conservation workflow. In mum intervention, reversibility, and long-term stew
this sense, the figure does not merely summarize the ardship. It also suggests that future studies should
results; it reformulates them as a practical research report not only algorithmic accuracy, but also data

Figure 17. Integrated research roadmap for architectural heritage conservation.

<!-- p. 20 -->

JOURNAL OF ASIAN ARCHITECTURE AND BUILDING ENGINEERING 19

provenance, expert validation procedures, uncertainty, has followed a cumulative trajectory in which digital
interpretability, and the practical consequences of AI- documentation, geometric survey, HBIM-based seman
assisted recommendations. tic modelling, monitoring systems, digital twins, and
The roadmap also identifies a practical research AI-supported analysis increasingly operate as intercon
agenda. Future work should move beyond isolated nected layers within conservation workflows. Figure 2
demonstrations of detection accuracy and should test demonstrates the rapid expansion of publication out
whether AI-supported outputs can improve inspection put, while Figure 3 shows that citation influence
efficiency, risk communication, maintenance schedul remains concentrated around transferable methodolo
ing, and conservation prioritization. In this respect, the gical contributions. Together, these results indicate
value of AI should be evaluated not only by computa that the field is expanding not only in volume but
tional performance, but also by its contribution to also in methodological complexity.
accountable conservation decision-making. The keyword, clustering, timeline, burst, co-citation,
and journal-level analyses further clarify the structure
of this transformation. Figures 8–12 show that the
5.4. Limitations and future directions research front has moved from documentation, survey,
3D modelling, and HBIM toward digital twins, digital
Several limitations should be acknowledged. First, the heritage platforms, and AI-related analysis. Figures 13–
bibliometric dataset was limited to the Web of Science 16 indicate that this development is supported by an
Core Collection. This choice improves data standardi interdisciplinary knowledge base that connects heri
zation and citation comparability, but it may exclude tage conservation with geomatics, construction infor
relevant publications indexed in Scopus, Dimensions, matics, remote sensing, engineering diagnostics,
Google Scholar, conference proceedings, professional imaging, monitoring, and computational analysis.
reports, and non-English literature. Future studies This cross-disciplinary structure explains why AIcould compare multiple databases and include grey supported conservation should not be understood as
literature, especially because heritage conservation a self-contained technological domain. Its practical
practice is often documented in technical reports and value depends on the quality of digital evidence, the
institutional guidelines. semantic organization of conservation knowledge, the
Second, the AI-related analysis remains partly con continuity of monitoring data, and the capacity of
strained by the vocabulary and indexing practices of experts to interpret uncertain computational outputs
bibliographic databases. Some studies may apply within conservation-specific value frameworks.
machine learning or computer vision without using The principal contribution of the study is there
the term “artificial intelligence”, while others may use fore conceptual as well as bibliometric. By distin
AI-related terminology in a broad or rhetorical way. guishing digitalization from AI, the article clarifies
Future research should combine bibliometric analysis their different functions in architectural heritage
with systematic content coding of AI methods, data conservation. Digital documentation provides reli
sets, validation strategies, and practical deployment able geometric and visual evidence; HBIM and
scenarios. semantic information modelling organize materials,
Third, future AI research should pay greater atten damage records, construction history, and interven
tion to culturally adaptive and conservation-sensitive tion information; IoT and digital twins support
models. Because architectural heritage is embedded in dynamic state awareness and lifecycle monitoring;
local materials, construction traditions, environmental and AI contributes to recognition, diagnosis, predic
conditions, and cultural meanings, models trained on tion, prioritization, and decision support. Figure 17
limited or geographically narrow datasets may not synthesizes this layered relationship into an inte
transfer reliably to different heritage contexts. Ethical grated research roadmap for evidence-based, pre
governance, explainability, data ownership, and expert ventive, and lifecycle-oriented conservation. The
accountability should therefore become integral parts roadmap is not intended as a universal technical
of AI-supported heritage conservation research. prescription, but as an analytical framework for con
necting fragmented digital methods with conserva
tion judgement, institutional governance, and
\6. Conclusions
practical intervention processes.
This study examined the evolution of digital documen The findings also indicate that the next stage of
tation and AI-supported decision-making in architec research should move beyond software-centred map
tural heritage conservation through a bibliometric and ping or isolated technical demonstrations. Future stu
visual analysis of 892 Web of Science publications dies need to develop interoperable data frameworks,
published between 2002 and 2024. The results show open and representative heritage datasets, reproduci
that the field has not developed through a simple ble annotation protocols, explainable AI models,
succession of independent technologies. Rather, it human-in-the-loop validation mechanisms, and

<!-- p. 21 -->

20 L. XU ET AL.

evaluation criteria that reflect conservation values Informetrics 11 (4): 959–975. https://doi.org/10.1016/j.joi.
rather than algorithmic accuracy alone. Greater atten 2017.08.007 .
tion should also be given to culturally adaptive models, Banfi, F. 2021. “The Evolution of Interactivity, Immersion and
Interoperability in HBIM: Digital Model Uses, VR and AR for
because architectural heritage is shaped by local mate
Built Cultural Heritage.” ISPRS International Journal of Georials, construction traditions, environmental condi Information 10 (10): 685. https://doi.org/10.3390/
tions, craft knowledge, and social meanings. For AI- ijgi10100685.
supported conservation to become practically cred Bastem, S. S., and A. Cekmis. 2022. “Development of Historic
ible, computational diagnosis must be linked to expert Building Information Modelling: A Systematic Literature
Review.” Building Research & Information 50 (5): 527–558.assessment, uncertainty communication, ethical gov
https://doi.org/10.1080/09613218.2021.1983754 .
ernance, and decision-making procedures that respect Boje, C., A. Guerriero, S. Kubicki, and Y. Rezgui. 2020. “Towards
authenticity, minimum intervention, reversibility, and a Semantic Construction Digital Twin: Directions for Future
long-term stewardship. Research.” Automation in Construction 114:103179. https://
Although the study is limited by its reliance on the doi.org/10.1016/j.autcon.2020.103179 .
Web of Science Core Collection and by the vocabulary Brumana, R., S. Della Torre, M. Previtali, L. Barazzetti, L.
Cantini, D. Oreni, and F. Banfi. 2018. “Generative HBIM
constraints of bibliographic databases, it provides
Modelling to Embody Complexity (LOD, LOG, LOA, LOI):
a structured account of how architectural heritage Surveying, Preservation, Site Intervention—the Basilica di
conservation is moving from digital recording toward Collemaggio (L’Aquila).” Applied Geomatics 10 (4): 545–
integrated, data-informed, and decision-oriented con 567. https://doi.org/10.1007/s12518-018-0233-3
servation. The proposed roadmap offers a basis for Bruno, N., and R. Roncella. 2019. “HBIM for Conservation:
A New Proposal for Information Modeling.” Remotefuture research that treats digital documentation,
Sensing 11 (15): 1751. https://doi.org/10.3390/rs11151751.
semantic modelling, monitoring, AI analytics, and con
Bruno, S., M. De Fino, and F. Fatiguso. 2018. “Historic Building
servation decision support as mutually dependent Information Modelling: Performance Assessment for
components of a broader conservation paradigm. Diagnosis-Aided Information Modelling and
Management.” Automation in Construction 86:256–276.
https://doi.org/10.1016/j.autcon.2017.11.009 .
Author contributions Callon, M., J.-P. Courtial, W. A. Turner, and S. Bauin. 1983.
“From Translations to Problematic Networks: An
CRediT: Kun Sang: Formal analysis, Methodology, Introduction to Co-Word Analysis.” Social Science
Supervision, Writing – original draft, Writing – review & Information 22 (2): 191–235. https://doi.org/10.1177/
editing. 053901883022002003 .
Casillo, M., F. Colace, B. B. Gupta, A. Lorusso, F. Marongiu, and
D. Santaniello. 2022. “A Deep Learning Approach to
Disclosure statement Protecting Cultural Heritage Buildings Through IoT-Based
Systems.” In 2022 IEEE International Conference on Smart
No potential conflict of interest was reported by the Computing (SMARTCOMP), edited by V. Issarny, S. Sigg, C.
author(s). Boldrini, and S. Silvestri, 252–256. Piscataway, NJ: IEEE.
Cha, Y. J., W. Choi, and O. Buyukozturk. 2017. “Deep
Learning-Based Crack Damage Detection Using
Funding Convolutional Neural Networks.” Computer-Aided Civil
and Infrastructure Engineering 32 (5): 361–378. https://doi.
This research was funded by the National Natural Science
org/10.1111/mice.12263 .
Foundation of China (Grant No. 52608065).
Chen, C. 2006. “CiteSpace II: Detecting and Visualizing
Emerging Trends and Transient Patterns in Scientific
Literature.” Journal of the American Society for
ORCID Information Science and Technology 57 (3): 359–377.
https://doi.org/10.1002/asi.20317 .
Lu Xu http://orcid.org/0000-0002-8376-5169
Colace, F., R. Gaeta, A. Lorusso, M. Pellegrino, and
Kun Sang http://orcid.org/0000-0002-3204-1355
D. Santaniello. 2025. “New AI Challenges for Cultural
Andrea Giordano http://orcid.org/0000-0002-9747-133X
Heritage Protection: A General Overview.” Journal of
Cultural Heritage 75:168–193. https://doi.org/10.1016/j.cul
her.2025.07.019 .
Data availability statement
Croce, V., G. Caroti, L. De Luca, K. Jacquot, A. Piemonte, and
P. Veron. 2021. “From the Semantic Point Cloud toThe bibliographic data were retrieved from the Web of
Heritage-Building Information Modeling: A SemiautomaticScience Core Collection. The full search strategy is provided
Approach Exploiting Machine Learning.” Remote Sensingin Appendix before the References, and the cleaned biblio
13 (3): 461. https://doi.org/10.3390/rs13030461 .metric dataset can be made available by the corresponding
Donthu, N., S. Kumar, D. Mukherjee, N. Pandey, andauthor upon reasonable request.
W. M. Lim. 2021. “How to Conduct a Bibliometric
Analysis: An Overview and Guidelines.” The Journal of
References Business Research 133:285–296. https://doi.org/10.1016/j.
jbusres.2021.04.070 .
Aria, M., and C. Cuccurullo. 2017. “Bibliometrix: An R-Tool for Dore, C., and M. Murphy. 2017. “Current State of the Art
Comprehensive Science Mapping Analysis.” Journal of Historic Building Information Modelling. The

<!-- p. 22 -->

JOURNAL OF ASIAN ARCHITECTURE AND BUILDING ENGINEERING 21

International Archives of the Photogrammetry.” Remote Bibliometric Analysis.” Heritage 7 (11): 6432–6479.
Sensing and Spatial Information Sciences 42:185–192. https://doi.org/10.3390/heritage7110300 .
https://doi.org/10.5194/isprs-archives-XLII-2-W5-185-2017 Mishra, M. 2021. “Machine Learning Techniques for Structural
. Health Monitoring of Heritage Buildings: A State-Of-TheDore, C., M. Murphy, S. McCarthy, F. Brechin, C. Casidy, and E. Art Review and Case Studies.” Journal of Cultural Heritage
Dirix. 2015. “Structural Simulations and Conservation 47:227–245. https://doi.org/10.1016/j.culher.2020.09.005 .
Analysis—Historic Building Information Model (HBIM).” Mishra, M., and E. Doria. 2026. “Virtual Reality and Artificial
The International Archives of the Photogrammetry, Remote Intelligence-Assisted Visual Inspections for Cultural
Sensing and Spatial Information Sciences 5 (W4): 351–357. Heritage Structures: A Review.” International Journal of
https://doi.org/10.5194/isprsarchives-XL-5-W4-351-2015 . Architectural Heritage: 1–25. https://doi.org/10.1080/
Fai, S., K. Graham, T. Duckworth, N. Wood, and R. Attar. 2011. 15583058.2026.2625346 .
“Building Information Modelling and Heritage Mishra, M., and P. B. Lourenco. 2024. “Artificial
Documentation.” In Proceedings of the 23rd International Intelligence-Assisted Visual Inspection for Cultural
Symposium, edited by K. Pavelka. Prague: Czech Technical Heritage: State-Of-The-Art Review.” Journal of Cultural
University in Prague. Heritage 66:536–550. https://doi.org/10.1016/j.culher.
Fontanella, F., F. Colace, M. Molinara, A. S. Di Freca, and 2024.01.005 .
F. Stanco. 2020. “Pattern Recognition and Artificial Mongeon, P., and A. Paul-Hus. 2016. “The Journal Coverage
Intelligence Techniques for Cultural Heritage.” Pattern of Web of Science and Scopus: A Comparative Analysis.”
Recognition Letters 138:23–29. https://doi.org/10.1016/j. Scientometrics 106 (1): 213–228. https://doi.org/10.1007/
patrec.2020.06.018 . s11192-015-1765-5 .
Freeman, L. C. 1977. “A Set of Measures of Centrality Based on Murphy, M., E. McGovern, and S. Pavia. 2009. “Historic
Betweenness.” Sociometry 40 (1): 35–41. Building Information Modelling (HBIM).” Structural Survey
Goodarzi, P., M. Ansari, F. P. Rahimian, M. Mahdavinejad, 27 (4): 311–327. https://doi.org/10.1108/
and C. Park. 2023. “Incorporating Sparse 02630800910985108 .
Model Machine Learning in Designing Cultural Pocobelli, D. P., J. Boehm, P. Bryan, J. Still, and J. Grau-Bové.
Heritage Landscapes.” Automation in Construction 2018. “BIM for Heritage Science: A Review.” Heritage
155:105058. https://doi.org/10.1016/j.autcon.2023. Science 6:30. https://doi.org/10.1186/s40494-018-0191-4 .
105058 . Puerto, A., K. Castaneda, O. Sanchez, C. A. Pena, L. Gutierrez,
Grilli, E., and F. Remondino. 2019. “Classification of 3D Digital and P. Saenz. 2024. “Building Information Modeling and
Heritage.” Remote Sensing 11 (7): 847. https://doi.org/10. Complementary Technologies in Heritage Buildings:
3390/rs11070847 . A Bibliometric Analysis.” Results in Engineering 22:102192.
Harisanty, D., K. L. B. Obille, N. E. V. Anna, E. Purwanti, and F. https://doi.org/10.1016/j.rineng.2024.102192 .
Retrialisca. 2024. “Cultural Heritage Preservation in the Quattrini, R., R. Pierdicca, and C. Morbidoni. 2017.
Digital Age, Harnessing Artificial Intelligence for the “Knowledge-Based Data Enrichment for HBIM: Exploring
Future: A Bibliometric Analysis.” Digital Library High-Quality Models Using the Semantic-Web.” Journal of
Perspectives 40 (4): 609–630. https://doi.org/10.1108/DLP- Cultural Heritage 28:129–139. https://doi.org/10.1016/j.cul
01-2024-0018 . her.2017.05.004 .
Historic England. 2017. 3D Laser Scanning for Heritage: Remondino, F. 2011. “Heritage Recording and 3D Modeling
Advice and Guidance on the Use of Laser Scanning in with Photogrammetry and 3D Scanning.” Remote Sensing
Archaeology and Architecture. Historic England. 3 (6): 1104–1138.
ICOMOS. 1964. International Charter for the Conservation and Remondino, F., and A. Rizzi. 2010. “Reality-Based 3D
Restoration of Monuments and Sites (The Venice Charter). Documentation of Natural and Cultural Heritage Sites -
Paris: ICOMOS. Techniques, Problems, and Examples.” Applied Geomatics
Jordan-Palomar, I., P. Tzortzopoulos, J. Garcia-Valldecabres, 2 (3): 85–100.
and E. Pellicer. 2018. “Protocol to Manage Rolim, R., C. Lopez-Gonzalez, and M. J. Vinals. 2024. “Analysis
Heritage-Building Interventions Using Heritage Building of the Current Status of Sensors and HBIM Integration:
Information Modelling (HBIM).” Sustainability 10 (4): 908. A Review Based on Bibliometric Analysis.” Heritage 7 (4):
https://doi.org/10.3390/su10040908 . 2071–2087. https://doi.org/10.3390/heritage7040098 .
Kleinberg, J. 2002. “Bursty and Hierarchical Structure in Sharma, H. 2026. “Applications of Artificial Intelligence and
Streams.” Proceedings of the Eighth ACM SIGKDD Machine Learning in the Preservation and Analysis of
International Conference on Knowledge Discovery and Heritage Structures: A Comprehensive Review.” Archives
Data Mining: 91–101. https://doi.org/10.1145/775047. of Computational Methods in Engineering 33 (2):
775061 . 3001–3033. https://doi.org/10.1007/s11831-025-10393-7 .
Laohaviraphap, N., and T. Waroonkun. 2024. “Integrating Small, H. 1973. “Co-Citation in the Scientific Literature: A New
Artificial Intelligence and the Internet of Things in Measure of the Relationship Between Two Documents.”
Cultural Heritage Preservation: A Systematic Review of Journal of the American Society for Information Science
Risk Management and Environmental Monitoring 24 (4): 265–269. https://doi.org/10.1002/asi.4630240406 .
Strategies.” Buildings 14 (12): 3979. https://doi.org/10. Sony, S., K. Dunphy, A. Sadhu, and M. Capretz. 2021.
3390/buildings14123979 . “A Systematic Review of Convolutional Neural
Lopez, F. J., P. M. Lerones, J. Llamas, J. Gomez-Garcia- Network-Based Structural Condition Assessment
Bermejo, and E. Zalama. 2018. “A Review of Heritage Techniques.” Engineering Structures 226:111347. https://
Building Information Modeling (H-BIM).” Multimodal doi.org/10.1016/j.engstruct.2020.111347 .
Technologies and Interaction 2 (2): 21. Tejedor, B., E. Lucchi, D. Bienvenido-Huertas, and I. Nardi.
Mazzetto, S. 2024. “Integrating Emerging Technologies with 2022. “Non-destructive Techniques (NDT) for the
Digital Twins for Heritage Building Conservation: An Diagnosis of Heritage Buildings: Traditional Procedures
Interdisciplinary Approach with Expert Insights and and Futures Perspectives.” Energy and Buildings

<!-- p. 23 -->

22 L. XU ET AL.

263:112029. https://doi.org/10.1016/j.enbuild.2022. Yang, X., P. Grussenmeyer, M. Koehl, H. Macher, A. Murtiyoso,
112029 . and T. Landes. 2020. “Review of Built Heritage Modelling:
Van Eck, N. J., and L. Waltman. 2010. “Software Survey: Integration of HBIM and Other Information Techniques.”
VOSviewer, a Computer Program for Bibliometric Journal of Cultural Heritage 46: 350–360. https://doi.org/
Mapping.” Scientometrics 84 (2): 523–538. https://doi.org/ 10.1016/j.culher.2020.05.008 .
10.1007/s11192-009-0146-3 . Yu, Y., A. A. Raed, Y. Peng, U. Pottgiesser, E. Verbree, and
Volk, R., J. Stengel, and F. Schultmann. 2014. “Building P. van Oosterom. 2025. “How Digital Technologies Have
Information Modeling (BIM) for Existing Buildings - Been Applied for Architectural Heritage Risk Management:
Literature Review and Future Needs.” Automation in A Systematic Literature Review from 2014 to 2024.” Npj
Construction 38:109–127. https://doi.org/10.1016/j.aut Heritage Science 13 (1): 45. https://doi.org/10.1038/s40494-
con.2013.10.023 . 025-01558-5.

<!-- p. 24 -->

JOURNAL OF ASIAN ARCHITECTURE AND BUILDING ENGINEERING 23

Appendix. Web of science search strategy

The bibliographic dataset was retrieved from the Web of Science Core Collection on 15 February 2025. The search was conducted
in the topic field, including titles, abstracts, author keywords, and Keywords Plus. The selected citation indexes were the Science
Citation Index Expanded, Social Sciences Citation Index, and Arts & Humanities Citation Index. The time span was limited to 2002–
\2024. Only articles and review articles written in English were retained.
Complete search string:
TS=(“architectural cultural heritage” OR “built cultural heritage” OR “architectural heritage” OR “monumental
heritage” OR “built heritage” OR “heritage structure” OR “industrial heritage” OR “tangible cultural heritage” OR
“historic architecture” OR “antique architecture” OR “architectural antiquities” OR “heritage building” OR “vernacular
architecture”) AND TS=(conservation OR maintenance OR preservation OR protection OR retention OR restoration OR
reinforcement) AND TS=(digital OR digitalization OR informationization OR informatization OR intellectualization OR
technology OR online OR cloud OR virtual OR media OR device OR network OR information OR data OR software OR
communication OR multimedia OR interface OR interaction OR automation OR transformation OR optimization OR
visualization OR “predictive modelling” OR “smart technology” OR “virtual assistant” OR VR OR AR OR MR OR XR OR
AIGC OR AI OR AGI OR NLP OR LLM OR CV OR “artificial intelligence” OR “machine learning” OR “deep learning” OR
“reinforcement learning” OR “neural network” OR algorithm OR robotics OR intelligence OR “natural language
processing” OR “computer vision” OR “big data” OR “cognitive computing” OR chatbot OR ChatGPT OR prediction
OR inference OR models OR “speech recognition” OR imaging OR “knowledge graphs” OR archiving OR
documentation).
The initial search returned 1,356 records. After limiting the time span to 2002–2024, 1,333 records remained. After
retaining articles and review articles, 1,328 records remained. After applying the English-language restriction, 1,281 records
remained. Finally, manual screening of titles, abstracts, and keywords was conducted to exclude records not directly related
to architectural heritage conservation, as well as three retracted publications. As a result, 892 publications were retained for
bibliometric and visual analysis.
