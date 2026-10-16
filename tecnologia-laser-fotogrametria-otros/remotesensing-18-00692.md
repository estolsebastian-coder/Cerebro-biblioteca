---
type: libro
title: "The Novel Models for Identifying the Vertical Structure of Urban Vegetation from UAV LiDAR Data"
author: "Hang Yang, Rongxin Deng, Xinmeng Jing, Zhen Dong, Xiaoyu Yang, Jingyi Li and Zhiwen Mei"
categoria: "Tecnología láser, fotogrametría, otros"
paginas: 16
extraccion: "texto"
fuente: "local:E:/DISCIPLINAS, TEXTOS Y MAPAS/Biblioteca digital/Tecnología láser, fotogrametría, otros/remotesensing-18-00692.pdf"
convertido: 2026-10-13
---

# The Novel Models for Identifying the Vertical Structure of Urban Vegetation from UAV LiDAR Data

> Texto extraído de `Tecnología láser, fotogrametría, otros/remotesensing-18-00692.pdf` (16 páginas, texto). El PDF original está en el disco E: (DISCIPLINAS, TEXTOS Y MAPAS\Biblioteca digital); `<!-- p. N -->` marca el inicio de cada página.

<!-- p. 1 -->

Article
The Novel Models for Identifying the Vertical Structure of Urban
Vegetation from UAV LiDAR Data

Hang Yang , Rongxin Deng * , Xinmeng Jing, Zhen Dong, Xiaoyu Yang, Jingyi Li and Zhiwen Mei

The School of Surveying and Geo-Informatics, North China University of Water Resources and Electric Power,
Zhengzhou 450046, China; 201904214@stu.ncwu.edu.cn (H.Y.)
\* Correspondence: dengrongxin@ncwu.edu.cn

Highlights

What are the main findings?

• Two automated UAV LiDAR-based models were developed for urban vegetation
vertical structure stratification.
• The models achieve high accuracy and show complementary performance under
different structural conditions.

What are the implications of the main findings?

• The proposed framework improves robustness and reduces empirical threshold dependence.
• It provides a transferable solution for urban vegetation structure mapping using
LiDAR data.

Abstract

Accurate quantification of vegetation vertical structure is crucial for analyzing the ecologi-
cal functions of urban green spaces. However, constrained by the complexity of vegetation
structure and spatial heterogeneity, current approaches for extracting vegetation vertical
structure by airborne LiDAR have limitations in terms of layer boundary identification
stability, threshold dependency, and ecological plausibility. This study developed two
integrated UAV LiDAR-based stratification frameworks for identifying urban riparian
vegetation vertical structure by combining established statistical modeling and signal pro-
cessing techniques: (1) a Gaussian Mixture Model with Bayesian Information Criterion
(GMM-BIC)-based probabilistic stratification framework; (2) a Savitzky–Golay filtering and
Pruned Exact Linear Time (SG-PELT)-based change-point detection framework. Further-
more, the ecological height constraint was incorporated into the model to achieve biological
adjustments. Two models were applied in the study area and compared using reference
data. The results showed that the GMM-BIC method achieved an overall classification
Academic Editors: Jochem Verrelst, accuracy of 91.06%, with a macro-averaged F1-score of 87.77%, while the SG-PELT method
Weiheng Xu, Jincheng Liu, Zhichao attained an overall accuracy of 84.57%, with a macro-averaged F1-score of 79.20%. These
Wang, Jia Wang and Tao Liu
results demonstrate that both models can effectively identify the vertical structure of urban
Received: 21 January 2026 vegetation. In particular, the two models exhibited distinct characteristics across different
Revised: 24 February 2026
scenarios. The GMM-BIC model showed superior stratification accuracy in regions where
Accepted: 25 February 2026
vegetation height distribution displayed pronounced multi-peak characteristics and distinct
Published: 26 February 2026
differences among height segments. In comparison, the SG-PELT model demonstrated
Copyright: © 2026 by the authors.
Licensee MDPI, Basel, Switzerland. greater sensitivity in areas with significant height variation and clearly defined abrupt
This article is an open access article transitions between layers. These models could provide new methodologies for monitordistributed under the terms and ing vegetation vertical structure and offer data support for biodiversity monitoring and
conditions of the Creative Commons ecological function assessment within urban ecosystems.
Attribution (CC BY) license.

Remote Sens. 2026, 18, 692 https://doi.org/10.3390/rs18050692

<!-- p. 2 -->

Remote Sens. 2026, 18, 692 2 of 16

Keywords: urban vegetation; LiDAR; vegetation vertical structure; remote sensing model

\1. Introduction

Urban green spaces serve as vital ecological barriers within the urbanization process,
which plays an irreplaceable role in improving water quality, regulating climate, promoting
biodiversity, mitigating the urban heat island effect, and providing recreational spaces [1–4].
The vertical structure of vegetation typically refers to the distribution characteristics of
tree heights within a forest stand [5], manifesting as the spatial vertical differentiation of
forest communities [6]. This differentiation sequentially divides the canopy from top to
bottom into distinct layers, including the tree layer, shrub layer, and herb layer, constituting
a crucial factor in determining and regulating wetland ecological functions [7,8]. However,
traditional vegetation structure methods based on ground surveys hardly achieve large-
scale and high-resolution quantification [9]. Airborne LiDAR technology, with its ability to
penetrate vegetation canopies and acquire high-precision three-dimensional point clouds,
showed significant potential in extracting the vertical structure of the vegetation [10].
Lefsky et al. first used LiDAR vertical profiles to quantify forest vertical structure [11].
Subsequently, Alonzo et al. identified the urban tree and shrub layers based on statistical
characteristics of LiDAR point cloud density profiles; some difficulties were encountered in
distinguishing the low herb layer [12]. Leiterer et al. classified forest stands into single-layer,
double-layer, and multi-layer by analyzing the vertical distribution of LiDAR returns [13].
John Tasker et al. developed a vertical segmentation method that effectively improved
the identification of subcanopy features [14]; however, the accuracy was decreased in
vegetation areas with complex structures or dense canopies. Similarly, Zhou et al. employed
a 10th-order polynomial to generate vertical canopy profiles for subtropical plantations
and natural forests [15]. Furthermore, Koma et al. employed a random forest classifier to
achieve multi-level stratification by extracting 31 LiDAR indicators [16]. It can be found that
LiDAR technology has made significant progress in quantifying the vertical structure of
forest vegetation, but it still has the following limitations: First, the methods predominantly
rely on peak detection or empirical threshold determination. These algorithms exhibited
a high degree of subjectivity and were highly sensitive to parameter variations. Second,
the accuracy was relatively low in the low-growing herbaceous layer and multi-layered
transition zones. Third, the relevant algorithms were predominantly data-driven, lacking
ecological constraints.
In urban environments, vegetation vertical structure exhibits strong spatial hetero-
geneity due to mixed species composition, artificial planting patterns, and complex canopy
overlap. Compared with natural forest ecosystems, urban vegetation structures are more
fragmented and irregular, which increases the difficulty of reliable vertical stratification
using airborne LiDAR data. However, most existing LiDAR-based stratification studies
primarily focus on natural or plantation forests, while systematic investigations targeting
complex urban vegetation structures remain limited. This research gap highlights the need
for an automated and robust framework specifically applicable to urban vegetation vertical
structure mapping. To solve the above problems, this study proposes to establish a novel
method by mathematically modeling the vertical structural characteristics of vegetation.
Previous research had found that the height distribution of LiDAR point clouds typically
exhibited a multi-peak characteristic, which indicated the different vegetation layers [17,18].
Gaussian Mixture Model (GMM) is highly compatible with simulating multi-peak func-
tions; it can decompose complex functions into several Gaussian components to describe
hierarchical features probabilistically with good stability and interpretability [19]. The

https://doi.org/10.3390/rs18050692

<!-- p. 3 -->

Remote Sens. 2026, 18, 692 3 of 16

vertical distribution of vegetation point clouds similarly exhibits near-normal character-
istics [20–23]: The height distribution of each vegetation layer may be regarded as an
independent Gaussian component, with the superposition of different Gaussian compo-
nents forming the overall multi-peak profile. Therefore, GMM is proposed to hierarchically
analyze the vertical structure of vegetation and model the vertical probability density
curve of vegetation through the weighted superposition of multiple Gaussian components.
Furthermore, the Bayes Information Criterion (BIC) is incorporated into the model to
mitigate the subjectivity inherent in selecting the number of model components. This
approach holistically balances goodness-of-fit with model complexity, enabling adaptive
determination of the optimal number of layers. The GMM-BIC algorithm could automati-
cally and objectively implement the stratification process. Theoretically, the distribution of
vegetation height may exhibit non-normal characteristics or local discontinuities, which
could potentially compromise the stability of GMM fitting and the accuracy of stratification
boundaries. In order to accommodate such non-normal distribution characteristics, another
mathematical model, the Savitzky–Golay (SG) filter, is introduced to simulate the vertical
distribution by utilizing its adjustable window smoothing properties. Correspondingly, the
PELT [24] algorithm is incorporated into this model to achieve non-parametric detection
of layer boundaries. The SG-PELT algorithm is formulated as another model to identify
vertical vegetation structures. Finally, the ecological constraint mechanism was considered
to ensure the biological validity and ecological interpretability.
In summary, this study developed two integrated UAV LiDAR-based stratification
frameworks, namely, the GMM-BIC framework and the SG-PELT framework, for identify-
ing vegetation vertical structure by combining probabilistic modeling and signal processing
techniques into a unified workflow. These frameworks aim to improve the stability of vege-
tation vertical stratification and reduce the subjectivity associated with empirical threshold
selection. Furthermore, an ecological constraint mechanism was incorporated to enhance
the biological interpretability of stratification results. The effectiveness and applicability of
both frameworks were evaluated and compared in the study area using airborne LiDAR
point cloud data. This work is expected to provide a practical and transferable approach
for efficient vegetation vertical structure mapping, which can further support biodiversity
monitoring and ecological function assessment in urban ecosystems.

\2. Study Area and Data

2.1. Study Area

The study area is located in Longzi Lake Wetland Park in Zhengzhou City, Henan
Province, China (Figure 1), which encompasses approximately 96.2 ha of green space.
The park represents a typical example of urban public green space. The regional climate
is characterized by a temperate continental monsoon pattern, with an average annual
temperature of approximately 14.4 ◦C and average annual precipitation of around 630 mm.
The vegetation in the study area has a diverse configuration mode and relatively complex
vertical structures, in which the tree layer mainly includes cultivated species such as
poplar, weeping willow, cedar, and plane tree; the shrub layer mainly consists of common
landscaping shrubs; and the grass layer is artificial cultivated grass.

2.2. Data Source
2.2.1. LiDAR Point Cloud Data

A BB4-type unmanned aerial vehicle equipped with an AA15 laser radar sensor was
employed to acquire LiDAR point cloud data within the study area. The aerial survey
was configured with a forward overlap rate of 80%, a side overlap rate of 60%, and
a flight speed of 8 m/s. Data were acquired on 30 July 2023. The raw UAV LiDAR

https://doi.org/10.3390/rs18050692

<!-- p. 4 -->

Remote Sens. 2026, 18, 692 4 of 16

dataset exhibited an average point density of approximately 441 pts/m2, and the effective
vegetation point density after vegetation point extraction was approximately 121 pts/m2.
The raw point cloud data were pre-processed using LiDAR360 software. Preprocessing
procedures included noise point removal to eliminate isolated outliers, resampling to ensure
uniform point distribution, and height normalization to transform absolute elevation values
into relative height above ground. These steps ensured consistent vertical reference and
improved the reliability of subsequent vegetation vertical structure analysis.

Figure 1. Study area location.

2.2.2. Field Data

Four representative sub-zones were selected within the study area (as shown in
Figure 1), covering typical urban green space types such as riparian corridors, urban
parks and shelterbelts. These sub-zones exhibit high structural heterogeneity with mixed
tree–shrub–grass compositions and multi-layer canopy structures, representing common
urban vegetation configurations. They were further subdivided into 10 m × 10 m grid
units. The grid size was selected by considering the statistical stability of LiDAR height
distributions and the spatial heterogeneity of urban vegetation structure. Small grid units
may suffer from insufficient point density and unstable multi-peak patterns dominated
by noise, while excessively large grids tend to mix multiple vegetation structures and blur
vertical boundaries. Therefore, the 10 m × 10 m grid represents a balance between point
density adequacy and structural homogeneity. The vertical vegetation structure type in each
grid was manually determined through visual interpretation based on three-dimensional
LiDAR point cloud information. Classification was performed by jointly considering point
cloud profiles and height distribution characteristics, and ambiguous samples were re-
examined through cross-checking to reduce subjectivity. Seven vegetation structure types
were classified, including trees, shrubs, grassland, tree–shrub mixed, tree–grass mixed,
shrub–grass mixed, and tree–shrub–grass mixed. A total of 1432 reference samples with
clear structural patterns were used for model validation.

\3. Research Methods

A comprehensive technical workflow was established to automatically extract the
vertical structure of urban vegetation, which contained four steps (Figure 2): (1) data

https://doi.org/10.3390/rs18050692

<!-- p. 5 -->

Remote Sens. 2026, 18, 692 5 of 16

pre-processing, including normalization, noise removal, and the generation of height
distribution sequences within regular grids; (2) layer determination using GMM-BIC and
SG-PELT models constrained by ecological thresholds; (3) performance validation based
on confusion matrices and visually interpreted samples; and (4) mapping of regional
vegetation vertical structure for subsequent ecological analysis.

Data pre-processing

Calculation of statistical Merged
measures weight
Normalized plot-level method decision- constraint Merged mean LDAR data preprocessing Model fitting value making after mechanism decision Extraction of vegetation Gaussian-Bayesian Iteration of the EM Bayesian Ecological Combine the point cloud data Data algorithm variance

Merged
Grid division of High-resolution Cost function weight
10m× 10m sequence
assembly
Detection Identifying key constraint Merged mean Vertical distribution plot preprocessing algorithm points value Method of point clouds processing mechanism after filtering for Core Variation SG Determining the Ecological smoothing Combine the Data layer boundaries variance

User precision Data pre-processing

Producer precision Two models evaluation
indicators Overall Accuracy Accuracy assessment Precision
Kappa coefficient Result output

Figure 2. Data processing workflow.

3.1. Data Preparation
3.1.1. Extraction of Vegetation Point Cloud Data

Visible imagery acquired synchronously via unmanned aerial vehicles (UAVs) was
used to extract vegetation point clouds based on the Visible-band Difference Vegetation
Index (VDVI) proposed by Wang et al. [25]. VDVI is suitable for rapidly identifying the
healthy green vegetation information from visible imagery. The formula is as follows:

2G −R −B
VDVI = (1)
2G + R + B

where R, G, and B are the reflectance values of the red, green, and blue bands, respectively.
Point clouds with VDVI values greater than the threshold were classified as vegetation
points, while the remaining points were regarded as non-vegetation objects. Wang et al. [25]
indicated that vegetation features generally exceeded 0.13. Therefore, the VDVI threshold
was set to 0.13.

3.1.2. Point Cloud Voxelization

A 10 m × 10 m grid was shaped as the fundamental analytical unit, which ensured
sufficient point cloud data for the vertical stratification analysis. A height-equidistant
density statistical method was employed to divide the point cloud into 100 layers within
each grid cell.

https://doi.org/10.3390/rs18050692

<!-- p. 6 -->

Remote Sens. 2026, 18, 692 6 of 16

3.2. Vertical Structure Detection Models
3.2.1. GMM-BIC

The GMM-BIC model was developed to adaptively identify vegetation layers and their
vertical boundaries. In this framework, the Gaussian Mixture Model (GMM) is employed
to simulate the vertical height distribution of vegetation point clouds as a superposition
of multiple probabilistic components. Subsequently, the Bayesian Information Criterion
(BIC) is utilized to automatically determine the optimal number of Gaussian components
(i.e., the number of vegetation layers) by balancing model fit with complexity. The specific
implementation steps are as follows:

(a) Hierarchical simulation by GMM

The GMM algorithm was proposed to simulate the changes of vertical structure. Its
core principle involves representing the overall probability distribution as a linear com-
bination of several Gaussian components, which could offer significant advantages in
analyzing complex three-dimensional vegetation structures. Parameters for each Gaussian
component can be determined through the Expectation–Maximization (EM) algorithm,
which can generate target curves by adjusting the parameters of Gaussian functions (mean,
standard deviation, and amplitude). This approach is an ideal tool to analyze complex
three-dimensional vegetation structures, because it is consistent with the multi-layered
characteristics of vertical vegetation structure and enables adaptive fitting of height dis-
tribution histograms. Compared to traditional single-peak Gaussian fitting, GMM can
identify and separate multiple structural layers [26], offering greater explanatory power for
complex multi-layered vegetation distributions. The formula is as follows:

K
p(z) = ∑ πkN z|µ k, σ2k (2)
k=1

! 1 −µk)2 −(zi (3) N zi | µk, σ2k = exp q 2σ2k 2πσ2k

where K is the number of Gaussian components, corresponding to the number of potential
vegetation layers; πk is the weight of the kth Gaussian component; N is the probability
density function of the Kth Gaussian distribution.
Model parameters (including the mean, variance, and weights of each component)
are estimated using the EM algorithm to achieve data-adaptive fitting. The EM algorithm
comprises an E step and an M step. The E step is used to compute the posterior probability
of each sample belonging to each Gaussian component, while the M step is used to update
the parameters to maximize the log-likelihood function. The formulas are as follows:

πkN zi |µ k, σ2k E: γik =
∑Kj=1 πjN zi |µ j, σ2j
1 N
M: µnewk = ∑ γikzi Nk i=1 (4)
s 1 N 2 σnew k = ∑ γik zi −µnewk Nk i=1
Nk πnew =
k N
where γik is the responsibility value of point i belonging to component k; πk is the weight
of component k; N is the Gaussian distribution density function.

https://doi.org/10.3390/rs18050692

<!-- p. 7 -->

Remote Sens. 2026, 18, 692 7 of 16

(b) Automatic Identification by BIC

The BIC is introduced to adaptively determine the number of layers. It is a statistical
criterion that comprehensively considers both model fit quality and complexity. Its principle
involves maximizing the likelihood function while imposing a penalty on model complexity,
thereby preventing the inclusion of unnecessary components [27]. It can be defined as:

BIC = −2 ln(L) + k ln(n) (5)

where L is the maximum likelihood value of the model; K is the number of model parame-
ters; n is the sample size.
A lower BIC value indicates a better balance between model fitting accuracy and com-
plexity. Consequently, the optimal number of vegetation layers is automatically determined
by calculating BIC values for a range of components and selecting the model with the
minimum BIC.

3.2.2. SG-PELT

The SG-PELT model employs statistical variations to drive layer boundary detec-
tion by minimizing a global cost function, which exhibits linear time complexity and
global optimality. This method could effectively identify multi-layer complex structures
while maintaining computational efficiency, and demonstrate enhanced robustness and
accuracy, particularly in point cloud data that are characterized by high noise levels or
non-normal distributions.
The model sorts vegetation points in ascending order of height to form a continuous
height sequence. The sequence was smoothed using an SG filter to attenuate noise interfer-
ence and obtain a stable vertical distribution curve. The PELT algorithm was employed
to minimize the global cost function, thereby detecting locations of abrupt changes in
statistical features within the height sequence and delineating potential vegetation layer
boundaries. The details are as follows:

(a) Curve simulation by SG

The parameters of the SG filter were determined based on preliminary experiments
and commonly adopted settings in signal smoothing applications. A moderate window
size (21 points) was selected to preserve the main structural peaks of vegetation height
distributions while suppressing high-frequency noise. A third-order polynomial was used
to capture the nonlinear variation pattern of vegetation height without introducing exces-
sive smoothing effects. When the window size exceeded 15 points, a secondary smoothing
strategy was applied to further reduce residual fluctuations and improve boundary stability.

(b) Automatic Identification by PELT

For the PELT algorithm, the penalty coefficient was selected to balance over-
segmentation and under-segmentation, avoiding excessive fragmentation while retaining
major structural transitions. The kernel parameter γ was determined based on the typical
vertical variability range of urban vegetation observed in the study area and previous
studies, enabling effective detection of intra-layer consistency and inter-layer transitions.
The principle of the PELT algorithm is to identify a number of transition points within
a one-dimensional sequence such that the statistical characteristics remain stable within
each segment [24]. Let the height sequence of the vegetation point cloud be denoted as
Z = z1, z2, . . . , zn. The objective of the algorithm is to determine a set of change points,
τ = τ1, τ2, . . . , τm, that minimizes the overall cost function:

m
C(Z, τ) = ∑ cos t zτi+1:τi+1 +βm (6)
i=0

https://doi.org/10.3390/rs18050692

<!-- p. 8 -->

Remote Sens. 2026, 18, 692 8 of 16

where cos t is the fitting error within each segment; m denotes the number of detected
change points, corresponding to the number of identified vegetation layer boundaries; and
β is the penalty term which controls the number of segments and balances fitting accuracy
against model complexity. In this study, the penalty coefficient was set by point cloud
density and vegetation complexity to achieve stability in layer detection.
The PELT algorithm employs dynamic programming and pruning mechanisms [24]
to reduce computational complexity from O(n2) to O(n) and ensure the global optimum
solution [28]. This characteristic enables efficient processing of high-density point cloud
data to rapidly and precisely identify vertical stratification. The algorithm can automati-
cally identify points of significant change within vegetation height sequences, which are
located at the natural boundaries between different vegetation layers. To evaluate param-
eter robustness, a limited sensitivity analysis was conducted by slightly varying the SG
window size and PELT penalty coefficient around the selected values. The results showed
that the overall stratification patterns and accuracy metrics exhibited only minor varia-
tions, indicating that the SG-PELT framework is relatively stable with respect to moderate
parameter perturbations.

3.3. Ecological Constraint Adjustment

After automated stratification using the GMM-BIC and SG-PELT models, adjacent
layers with similar heights, indistinct boundaries, or ambiguous ecological significance
may occur due to the purely statistical segmentation process. For example, two neighboring
layers may exhibit very small height differences or fall within the same vegetation growth
interval, which may not represent meaningful ecological structural distinctions.
To address this issue, an ecological constraint correction mechanism was introduced.
The ecological height intervals were determined based on a synthesis of relevant literature
and field survey observations, reflecting typical growth characteristics and vertical structure
patterns of urban vegetation. When two adjacent layers were located within the same
ecological height interval and showed limited vertical separation, they were considered
ecologically redundant and merged into a single layer.
Specifically, after merging, the layer parameters, including mean height, variance,
standard deviation and proportion weight, were recalculated using weighted averaging
based on the point cloud distributions of the original layers, ensuring statistical consistency
while improving biological interpretability of the stratification results:

∑ni=1 wiµi µnew = (7)
∑ni=1 wi

∑ni=1 wiσ2i + (µi −µnew)2 σ2new = (8) ∑ni=1 wi

q
σnew = σ2new (9)

n
wnew = ∑ wi (10)
i=1
where µi is the mean height of the i-th layer; σ2i is the variance of the i-th layer; wi is the
point cloud proportion of the i-th layer; µnew, σ2new, and wnew are the parameters of the
newly merged layer.

3.4. Accuracy Verification

A confusion matrix was constructed to assess the precision of the identified results. The
results were quantitatively evaluated using four metrics: user’s accuracy (UA), producer’s

https://doi.org/10.3390/rs18050692

<!-- p. 9 -->

Remote Sens. 2026, 18, 692 9 of 16

accuracy (PA), overall accuracy (OA), and the F1-score. The calculation formulas are
as follows:
∑ri=1 xii
OA = N
(11) UAi = xi+xii
PAi = x+ixii
2 · UA · PA
F1 = (12)
UA + PA

where r is the total number of classes, N is the total number of samples, and xii is the number
of correctly classified samples in class i (the diagonal element of the confusion matrix). xi+
is the sum of row i (total predicted samples for class i), and x+i is the sum of column i (total
actual samples for class i). OA measures the overall correctness of classification results,
while the F1-score provides a balanced evaluation by jointly considering precision (UA) and
recall (PA), thereby reflecting both omission and commission errors. The macro-averaged
F1-score was calculated as the arithmetic mean of class-wise F1-scores, giving equal weight
to each vegetation structure type.

\4. Results and Analysis

4.1. Comparison of Fitting and Stratification Effects

Three representative vegetation structure types, tri-layered (trees, shrubs, grasses),
bi-layered (trees, grasses), and mono-layered (trees), were selected to visually demonstrate
the fitting and layering effects of point cloud data by the two models (Figure 3). The strati-
fication results from the typical sample plots demonstrated that both methods effectively
reflected the vertical height distribution characteristics and stratification differences of the
vegetation. For the three-layer structural sample (Figure 3d or Figure 3g), the point cloud
exhibited distinct peaks across low, medium, and high elevation layers, corresponding to
the herbaceous layer, shrub layer, and tree layer, respectively. Both GMM-BIC and SG-PELT
achieved relatively clear stratification effects. For the double-layer structure sample shown
in Figure 3e or Figure 3h, two models successfully identified the upper and lower primary
vegetation layers, which had consistent boundary locations and height distributions. For
the single-layer structure sample, Figure 3f or Figure 3i, results indicated that both models
reliably identified single-layer vegetation distribution without exhibiting misclassification
of layers.
It can be found that both models accurately depicted the vertical structure characteris-
tics of vegetation and distinguished the distribution patterns of different layers. GMM-BIC
yields smoother fitting curves than SG-PELT, but SG-PELT more intuitively reflects changes
in the layer boundary than GMM-BIC.

4.2. Precision Analysis

The vertical structures of vegetation in the study area were identified using the GMM-
BIC and SG-PELT models, and combining with ecological constraints. A confusion ma-
trix between the measured and identified data was constructed, which was presented
in Tables 1 and 2. The results showed that the GMM-BIC method achieved an overall
accuracy (OA) of 91.06%, while the SG-PELT method achieved an OA of 84.57%. In terms
of macro-averaged F1-score, the GMM-BIC method reached 87.77%, compared to 79.20%
for the SG-PELT method. These results indicate that the GMM-BIC framework exhibited
stronger overall classification performance in identifying vertical vegetation structures.

https://doi.org/10.3390/rs18050692

<!-- p. 10 -->

Remote Sens. 2026, 18, 692 10 of 16

(a) (b) (c)

(d) (e) (f)

(g) (h) (i)

Figure 3. (a–c) Three-dimensional point cloud distributions of representative vegetation structure
types, including tri-layered, bi-layered, and mono-layered vegetation. (d–f) Stratification results of
the three samples generated by the GMM-BIC model. (g–i) Stratification results of the three samples
generated by the SG-PELT model.

The GMM-BIC method showed greater stability and discrimination capability across
both multi-layered composite structures and single-layer vegetation types; however, the
SG-PELT method performed better in simple hierarchies or obvious height variations,
although it exhibited lower recognition efficiency in complex scenarios. Within the primary
composite vegetation structures (Table 1), the GMM-BIC method demonstrated particularly
outstanding performance: For the tree–shrub–grass type, user accuracy reached 97.55%
and producer accuracy was 83.78%; for the tree–grass type, producer accuracy was as
high as 97.25%; and for the shrub–grass type, identification accuracy attained 98.27%.
These results demonstrated that this method can reliably capture differences between peak
heights within multi-layered vegetation, making it suitable for scenarios characterized

https://doi.org/10.3390/rs18050692

<!-- p. 11 -->

Remote Sens. 2026, 18, 692 11 of 16

by multi-peak distributions and distinct vertical structures. In contrast, SG-PELT’s per-
formance within composite structures (Table 2) was generally suboptimal, particularly
in grassland-dominated types where producer accuracy reached only 51.66%, which in-
dicated its inadequate identification capability in areas characterized by highly gradual
transitions and insignificant inter-layer differences. Within single-layer structural types,
the performance of the two methods is relatively comparable: The GMM-BIC model got
reliable recognition for both the tree layer (user precision: 82.81%) and the grass layer
(user precision: 94.09%), whereas SG-PELT achieved higher user precision for the tree layer
(89.06%) but exhibited significant confusion between the shrub and shrub–grass layers.

Table 1. Confusion matrix for GMM-BIC classification results.

Predicted\Actual TSG TG TS SG G S T Total UA F1

TSG 279 6 0 0 0 0 1 286 97.55% 90.16%
TG 19 459 0 0 12 0 6 496 92.54% 94.84%
TS 0 0 28 0 0 0 8 36 77.78% 84.85%
SG 8 0 0 170 12 4 0 194 87.63% 92.36%
G 0 5 0 3 191 0 4 203 94.09% 90.95%
S 0 0 0 0 0 18 7 25 72.00% 76.60%
T 27 2 2 0 2 0 159 192 82.81% 84.36%
Total 333 472 30 173 217 22 185 1432
PA 83.78% 97.25% 93.33% 98.27% 88.02% 81.82% 85.95%
OA 91.06%
Macro F1 87.77%

Note: Abbreviations in the confusion matrix denote: TSG = Trees–Shrubs–Grasses, TG = Trees–Grasses,
TS = Trees–Shrubs, SG = Shrubs–Grasses, G = Herbaceous layer, S = Shrub layer, T = Tree layer.

Table 2. Confusion matrix for SG-PELT classification results.

Predicted\Actual TSG TG TS SG G S T Total UA F1

TSG 235 15 0 30 3 0 3 286 82.17% 89.70%
TG 10 450 2 20 10 0 4 496 90.73% 92.12%
TS 2 3 22 5 0 0 4 36 61.11% 73.33%
SG 20 15 3 140 10 3 3 194 72.16% 60.24%
G 3 8 0 12 175 0 5 203 86.21% 85.37%
S 0 0 0 5 0 18 2 25 72.00% 60.99%
T 3 5 1 10 2 0 171 192 89.06% 92.86%
Total 238 481 24 271 207 34 177 1432
PA 98.74% 93.56% 91.67% 51.66% 84.54% 52.94% 96.61%
OA 84.75%
Macro F1 79.20%

Note: Abbreviations in the confusion matrix denote: TSG = Trees–Shrubs–Grasses, TG = Trees–Grasses,
TS = Trees–Shrubs, SG = Shrubs–Grasses, G = Herbaceous layer, S = Shrub layer, T = Tree layer.

4.3. Mapping of Vertical Vegetation Structure in the Study Area

The comparative results demonstrated that the GMM-BIC method outperformed the
SG-PELT algorithm in both overall accuracy and consistency. Therefore, the GMM-BIC
model integrating with ecological constraints was used to map the vertical structural
distribution of green spaces in the study area (as shown in Figure 4).

https://doi.org/10.3390/rs18050692

<!-- p. 12 -->

Remote Sens. 2026, 18, 692 12 of 16

Figure 4. Vertical Structure Classification Diagram. Note: TSG = Trees–Shrubs–Grasses, TG = Trees–
Grasses, TS = Trees–Shrubs, SG = Shrubs–Grasses, G = Herbaceous layer, S = Shrub layer,
T = Tree layer.

The vertical structure of vegetation in the study area predominantly featured multi-
layered composite types, among which the three-layer structure accounted for the highest
proportion at approximately 39.6%, primarily distributed within the park’s core zone and
lake shore zones. The tree–grass structure accounted for 22.5%, which was predominantly
located in roadside green belts; The shrub–grass structure constituted 13.3%, which was
mainly distributed in green spaces and lake shore buffer zones; The tree–shrub structure
represented 7.3%, which concentrated in avenue trees and ecological isolation strips. For
the single-layered structure, the tree layer (9.0%) and grass layer (7.5%) accounted for a
relatively high proportion, whereas the shrub layer (0.7%) constituted a lower share; this
indicated that shrubs were predominantly located in the middle or understorey layer.

\5. Discussion

5.1. Methodological Comparison

This study presents an automated UAV LiDAR–based framework for vertical stratifica-
tion of urban vegetation by integrating a probabilistic modeling approach (GMM-BIC) and
a signal segmentation strategy (SG-PELT). Unlike threshold-dependent or supervised clas-
sification methods, the proposed framework identifies vertical layers directly from height
distribution characteristics, enabling adaptive and data-driven recognition of multi-layered
vegetation structures.
In terms of classification performance, the GMM-BIC and SG-PELT approaches
achieved overall accuracies of 91.06% and 84.57%, respectively. These results are higher
than those reported for two-dimensional deep learning approaches based on optical im-
agery (78–79%) [29] and conventional peak-based thresholding methods (generally below
80%). While Zhou et al. [15] reported slightly higher accuracy (93.9%) in subtropical forest
environments, their approach relied on complex higher-order function fitting and empirical
parameter configuration. In contrast, the present framework employs statistical model se-
lection (BIC) and change-point detection to achieve adaptive stratification without manual
parameter tuning, thereby reducing methodological subjectivity.

https://doi.org/10.3390/rs18050692

<!-- p. 13 -->

Remote Sens. 2026, 18, 692 13 of 16

Recent studies have increasingly adopted machine learning and deep neural networks
for forest vertical structure mapping [30–32]. Although such methods demonstrate strong
predictive performance, they typically depend on labeled training data and may face chal-
lenges when transferred to structurally heterogeneous urban environments. By directly
modeling three-dimensional height distributions and incorporating ecological height con-
straints, the proposed framework provides a statistically interpretable and ecologically
consistent alternative for urban vegetation analysis.

5.2. Spatial Scale and Structural Representation

Spatial aggregation through grid- or voxel-based representation is widely applied in
vertical structure studies to enhance statistical robustness. For example, Park et al. [30]
employed a 20 m × 20 m voxel size for forest vertical structure mapping using full-
waveform LiDAR. Large-scale mapping efforts in ecologically diverse regions, such as
Colombia [33], similarly rely on spatial aggregation to balance ecological interpretability
and computational feasibility.
However, urban vegetation is characterized by higher spatial heterogeneity and
smaller structural patches compared to natural forests. The 10 m × 10 m grid adopted in
this study was selected to balance point density stability and structural homogeneity while
maintaining sufficient spatial sensitivity to urban canopy variability.
Although this approach does not resolve individual tree crowns, it enables consis-
tent statistical characterization of vertical layering patterns across extensive urban areas.
Importantly, the derived stratification results can serve as structural reference labels for
large-scale mapping using multispectral or satellite imagery [32,34,35], supporting future
cross-sensor integration and model transfer.

5.3. Ecological Implications

Vegetation vertical structure is closely associated with biodiversity, habitat complexity,
and ecosystem functionality. Previous large-scale studies have highlighted the ecological
relevance of vertical stratification in forest ecosystems [33,36]. Extending such structural
assessment frameworks to urban environments is essential for understanding ecosystem
services, habitat quality, and urban biodiversity patterns.
By enabling automated identification of mono-layered, bi-layered, and multi-layered
vegetation structures, the proposed framework provides quantitative descriptors of vertical
complexity in urban green spaces. Compared with two-dimensional canopy classification
approaches, which primarily capture horizontal spectral variability, the three-dimensional
stratification strategy adopted here explicitly represents vertical height distributions and
inter-layer relationships. This structural perspective enhances ecological interpretability
and supports urban green space planning and management.

5.4. Limitations and Future Perspectives

Despite the promising performance of the proposed framework, several limitations
warrant consideration. First, data sensitivity remains a potential constraint. The reliability
of Gaussian mixture fitting and change-point detection is influenced by point cloud density
and data quality. Extremely low-density LiDAR data may reduce model stability and
stratification reliability. Second, the present analysis is based on single-temporal data
acquisition. Seasonal dynamics and vegetation growth patterns were not considered.
Multi-temporal integration, as explored in recent satellite-based vertical structure mapping
studies [32,34], could improve temporal robustness and ecological representativeness.
Third, occlusion effects in densely vegetated areas may limit LiDAR pulse penetration,
potentially reducing understory detection accuracy.

https://doi.org/10.3390/rs18050692

<!-- p. 14 -->

Remote Sens. 2026, 18, 692 14 of 16

Future research should therefore focus on (1) integrating multi-source and multi-
temporal datasets, combining UAV LiDAR with multispectral or hyperspectral time-series
imagery to enhance structural completeness, and (2) coupling statistical stratification
models with deep learning techniques to improve generalization capability and adaptability
across diverse urban scenarios.

\6. Conclusions

In this study, GMM-BIC and SG-PELT models were developed to automatically iden-
tify the vertical vegetation structures. By integrating statistical modelling, adaptive opti-
mization and ecological constraint mechanisms, it achieved high-precision identification
of complex multi-layered vegetation structures. Research findings indicate that both the
proposed GMM-BIC adaptive stratification model and the SG-PELT change point detection
model can accurately delineate multi-layered vegetation structures—including trees, shrubs,
and grasses—without requiring empirical thresholds. Moreover, the overall accuracy of
both models significantly outperforms traditional peak thresholding methods. The stratifi-
cation results align closely with the spatial patterns and ecological structural characteristics
of urban green spaces, validating the ecological soundness and universal applicability of
the methodology. This study provides an efficient, robust, and ecologically interpretable
technical pathway for the refined monitoring of urban vegetation vertical structure, holding
significant theoretical and practical value for urban ecosystem assessment, carbon stock
estimation, and landscape planning.

Author Contributions: H.Y. led the research and carried out the majority of data analysis, model
implementation, and manuscript preparation. R.D. provided overarching supervision and made
substantial contributions to research design, interpretation, and manuscript revision. X.J. and Z.D.
assisted with data collection and validation. X.Y. contributed to software development and visualiza-
tion. J.L. and Z.M. participated in literature review and manuscript editing. All authors have read
and agreed to the published version of the manuscript.

Funding: This work was supported by the Henan Provincial Natural Science Foundation [grant
numbers 252300421471].

Data Availability Statement: Data can be requested from the corresponding author upon request.

Acknowledgments: The authors gratefully acknowledge the valuable comments and sugges-
tions provided by the anonymous reviewers and editors, which greatly improved the quality of
this manuscript.

Conflicts of Interest: The authors declare no conflicts of interest. The funders had no role in the design
of the study; in the collection, analyses, or interpretation of data; in the writing of the manuscript; or
in the decision to publish the results.

References

\1. Chen, X.; Li, L.; Wang, J. Heat island effect mitigation by urban green space system: A case study of taizhou city. Ecol. Environ.
Sci. 2015, 24, 643–649. (In Chinese) [CrossRef]
\2. Xie, L.J.; Bulkeley, H. Nature-based solutions for urban biodiversity governance. Environ. Sci. Policy 2020, 110, 77–87. [CrossRef]
\3. Zhao, J.C.; Wei, W.; Duan, X.W. Response of the runoff and sediment process on loess slope to the vertical structure changes of
three shrub and grass vegetations under simulated rainfall. Acta Ecol. Sin. 2021, 41, 8602–8611. (In Chinese) [CrossRef]
\4. Rao, J.S.; Yang, T.; Tian, X.; Liu, W.C.; Wang, X.F.; Qian, H.J.; Shen, Z.H. Vertical structural characteristics of a semi-humid
evergreen broad-leaved forest and common tree species based on a portable backpack LiDAR. Biodivers. Sci. 2023, 31, 49–59.
(In Chinese) [CrossRef]
\5. Zimble, D.A.; Evans, D.L.; Carlson, G.C.; Parker, R.C.; Grado, S.C.; Gerard, P.D. Characterizing vertical forest structure using
small-footprint airborne LiDAR. Remote Sens. Environ. 2003, 87, 171–182. [CrossRef]
\6. Pommerening, A.; Meador, A.J.S. Tamm review: Tree interactions between myth and reality. For. Ecol. Manage. 2018, 424, 164–176.
[CrossRef]

https://doi.org/10.3390/rs18050692

<!-- p. 15 -->

Remote Sens. 2026, 18, 692 15 of 16

\7. Hui, G.Y.; Zhao, Z.H.; Chen, M.H. Important variables describing forest structure. J. Temp. For. Res. 2020, 3, 14–20. (In Chinese)
[CrossRef]
\8. Fang, H.L. Retrieval of forest vertical leaf area index and clumping index through field measurement and remote sensing
techniques: A review. Sci. Bull. 2021, 66, 3141–3153. (In Chinese) [CrossRef]
\9. Montoya-Sánchez, V.; Camarretta, N.; Ehbrecht, M.; Schlund, M.; Paterno, G.B.; Seidel, D.; Guerrero-Ramírez, N.; Brambach,
F.; Hölscher, D.; Kreft, H.; et al. Comparing airborne and terrestrial LiDAR with ground-based inventory metrics of vegetation
structural complexity in oil palm agroforests. Ecol. Indic. 2024, 166, 112306. [CrossRef]
\10. Hao, H.K. Inversion of Forest Parameters Using Airborne LiDAR. Ph.D. Thesis, Northwest A&F University, Xianyang, China,
\2019. (In Chinese)
\11. Lefsky, M.A.; Cohen, W.B.; Parker, G.G.; Harding, D.J. Lidar remote sensing for ecosystem studies. Bioscience 2002, 52, 19–30.
[CrossRef]
\12. Alonzo, M.; Bookhagen, B.; Roberts, D.A. Urban tree species mapping using hyperspectral and lidar data fusion. Remote Sens.
Environ. 2014, 148, 70–83. [CrossRef]
\13. Leiterer, R.; Torabzadeh, H.; Furrer, R.; Schaepman, M.E.; Morsdorf, F. Towards automated characterization of canopy layering in
mixed temperate forests using airborne laser scanning. Forests 2015, 6, 4146–4167. [CrossRef]
\14. Tasker, J.; Phinn, S. Vertical Segmentation of Airborne Light Detection and Ranging (LiDAR) for Select Australian Vegetation
Communities. Proceedings 2018, 2, 338. [CrossRef]
\15. Zhou, X.B.; Li, C.G.; Yu, Z.; Chen, Z.C.; Su, K. Classification of vertical forest structure of overstory in subtropical forests using
airborne lidar data. For. Resour. Manag. 2022, 106–113. (In Chinese) [CrossRef]
\16. Koma, Z.; Zlinszky, A.; Beko, L.; Burai, P.; Seijmonsbergen, A.C.; Kissling, W.D. Quantifying 3D vegetation structure in wetlands
using differently measured airborne laser scanning data. Ecol. Indic. 2021, 127, 107752. [CrossRef]
\17. Pirotti, F.; Guarnieri, A.; Vettore, A. Vegetation characteristics using multi-return terrestrial laser scanner. In Proceedings of the
ISPRS Workshop on Laser Scanning, Calgary, AB, Canada, 29–31 August 2011; pp. 277–282.
\18. Hese, S.; Thiel, C.; Henkel, A. UAV based multi seasonal deciduous tree species analysis in The Hainich National Park using multi
temporal and point cloud curvature features. Int. Arch. Photogramm. Remote Sens. Spat. Inf. Sci. 2019, 42, 363–370. [CrossRef]
\19. Lu, W.G.; Ding, D.; Wu, F.Y.; Yuan, G.N. An efficient Gaussian mixture model and its application to neural networks. Knowl.
Based Syst. 2025, 310, 112942. [CrossRef]
\20. Hackenberg, J.; Morhart, C.; Sheppard, J.; Spiecker, H.; Disney, M. Highly accurate tree models derived from terrestrial laser scan
data: A method description. Forests 2014, 5, 1069–1105. [CrossRef]
\21. Kargar, A.R.; MacKenzie, R.; Asner, G.P.; van Aardt, J. A density-based approach for leaf area index assessment in a complex
forest environment using a terrestrial laser scanner. Remote Sens. 2019, 11, 211791. [CrossRef]
\22. Gobbi, B.; Van Rompaey, A.; Loto, D.; Gasparri, I.; Vanacker, V. Comparing forest structural attributes derived from UAV-based
point clouds with conventional forest inventories in the dry chaco. Remote Sens. 2020, 12, 234005. [CrossRef]
\23. Mesas-Carrascosa, F.J.; de Castro, A.I.; Torres-Sánchez, J.; Triviño-Tarradas, P.; Jiménez-Brenes, F.M.; García-Ferrer, A.; López-
Granados, F. Classification of 3D point clouds using color vegetation indices for precision viticulture and digitizing applications.
Remote Sens. 2020, 12, 317. [CrossRef]
\24. Killick, R.; Fearnhead, P.; Eckley, I.A. Optimal detection of changepoints with a linear computational cost. J. Am. Stat. Assoc. 2012,
107, 1590–1598. [CrossRef]
\25. Wang, X.Q.; Wang, M.M.; Wang, S.Q.; Wu, Y.D. Extraction of vegetation information from visible unmanned aerial vehicle images.
Trans. Chin. Soc. Agric. Eng. 2015, 31, 152–159. (In Chinese) [CrossRef]
\26. Yang, Y.Z.; Zhu, Q.A.; Peng, C.H.; Wang, H.; Xue, W.; Lin, G.H.; Wen, Z.M.; Chang, J.; Wang, M.; Liu, G.B.; et al. A novel approach
for modelling vegetation distributions and analysing vegetation sensitivity through trait-climate relationships in China. Sci. Rep.
2016, 6, 24110. [CrossRef]
\27. Danks, N.P.; Sharma, P.N.; Sarstedt, M. Model selection uncertainty and multimodel inference in partial least squares structural
equation modeling (PLS-SEM). J. Bus. Res. 2020, 113, 13–24. [CrossRef]
\28. Wambui, G.D.; Waititu, G.A.; Wanjoya, A. The power of the pruned exact linear time (PELT) test in multiple changepoint detection.
Am. J. Theor. Appl. Stat. 2015, 4, 581. [CrossRef]
\29. Ayhan, B.; Kwan, C. Tree, shrub, and grass classification using only RGB images. Remote Sens. 2020, 12, 201333. [CrossRef]
\30. Park, S.H.; Jung, H.S.; Lee, S.; Kim, E.S. Mapping forest vertical structure in Sogwang-ri forest from full-waveform lidar point
clouds using deep neural network. Remote Sens. 2021, 13, 3736. [CrossRef]
\31. Kwon, S.K.; Jung, H.S.; Baek, W.K.; Kim, D. Classification of forest vertical structure in South Korea from Aerial Orthophoto and
lidar data using an artificial neural network. Appl. Sci. 2017, 7, 1046. [CrossRef]
\32. Yu, J.W.; Yoon, Y.W.; Baek, W.K.; Jung, H.S. Forest vertical structure mapping using two-seasonal optic images and LiDAR DSM
acquired from UAV platform through random forest, XGBoost, and support vector machine approaches. Remote Sens. 2021,
13, 4282. [CrossRef]

https://doi.org/10.3390/rs18050692

<!-- p. 16 -->

Remote Sens. 2026, 18, 692 16 of 16

\33. Fagua, J.C.; Jantz, P.; Burns, P.; Jantz, S.M.; Kilbride, J.B.; Goetz, S.J. Maps of forest vertical structure for Colombia, a megadiverse
country. Sci. Data 2025, 13, 1. [CrossRef]
\34. Lee, Y.S.; Lee, S.; Jung, H.S. Mapping forest vertical structure in Gong-ju, Korea using Sentinel-2 satellite images and artificial
neural networks. Appl. Sci. 2020, 10, 1666. [CrossRef]
\35. Lee, Y.S.; Lee, S.; Baek, W.K.; Jung, H.S.; Park, S.H.; Lee, M.J. Mapping forest vertical structure in Jeju island from optical and
radar satellite images using artificial neural network. Remote Sens. 2020, 12, 797. [CrossRef]
\36. Hirschmugl, M.; Lippl, F.; Sobe, C. Assessing the vertical structure of forests using airborne and spaceborne LiDAR data in the
austrian alps. Remote Sens. 2023, 15, 664. [CrossRef]

Disclaimer/Publisher’s Note: The statements, opinions and data contained in all publications are solely those of the individual
author(s) and contributor(s) and not of MDPI and/or the editor(s). MDPI and/or the editor(s) disclaim responsibility for any injury to
people or property resulting from any ideas, methods, instructions or products referred to in the content.

https://doi.org/10.3390/rs18050692
