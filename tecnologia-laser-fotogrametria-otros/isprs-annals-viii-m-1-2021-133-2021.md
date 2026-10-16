---
type: libro
title: "isprs-annals-VIII-M-1-2021-133-2021"
author: ""
categoria: "Tecnología láser, fotogrametría, otros"
paginas: 7
extraccion: "texto"
fuente: "local:E:/DISCIPLINAS, TEXTOS Y MAPAS/Biblioteca digital/Tecnología láser, fotogrametría, otros/isprs-annals-VIII-M-1-2021-133-2021.pdf"
convertido: 2026-10-13
---

# isprs-annals-VIII-M-1-2021-133-2021

> Texto extraído de `Tecnología láser, fotogrametría, otros/isprs-annals-VIII-M-1-2021-133-2021.pdf` (7 páginas, texto). El PDF original está en el disco E: (DISCIPLINAS, TEXTOS Y MAPAS\Biblioteca digital); `<!-- p. N -->` marca el inicio de cada página.

<!-- p. 1 -->

ISPRS Annals of the Photogrammetry, Remote Sensing and Spatial Information Sciences, Volume VIII-M-1-2021
28th CIPA Symposium “Great Learning & Digital Emotion”, 28 August–1 September 2021, Beijing, China

A 3D POINT CLOUD DEEP LEARNING APPROACH USING LIDAR TO IDENTIFY
ANCIENT MAYA ARCHAEOLOGICAL SITES

Heather Richards-Rissettoa, David Newtonb, Aziza Al Zadjalic

a School of Global Integrative Studies (SGIS), University of Nebraska-Lincoln, Nebraska, USA (richards-rissetto@unl.edu)
b College of Architecture, University of Nebraska-Lincoln, Nebraska, USA (david.newton@unl.edu)
c Department of Computer Science & Engineering, University of Nebraska-Lincoln, Nebraska, USA
(aziza.alzadjali@huskers.unl.edu)

KEY WORDS: Ancient Maya, Archaeology, Deep Learning, LIDAR, Point Clouds, 3D Shape Classification

ABSTRACT:

Airborne light detection and ranging (LIDAR) systems allow archaeologists to capture 3D data of anthropogenic landscapes with a
level of precision that permits the identification of archaeological sites in difficult to reach and inaccessible regions. These benefits
have come with a deluge of LIDAR data that requires significant and costly manual labor to interpret and analyze. In order to address
this challenge, researchers have explored the use of state-of-the-art automated object recognition algorithms from the field of deep
learning with success. This previous research, however, has been limited to the exploration of deep learning processes that work with
only 2D data, which excludes the use of available 3D data. Our research addresses this gap and contributes knowledge on the use of
deep learning-based processes that can classify archaeological sites from LIDAR generated 3D point cloud datasets. LIDAR data
from the UNESCO World Heritage Site of Copan, Honduras is used as the primary dataset to compare the classification accuracy of
deep learning models using 2D and 3D data. The results demonstrate that models using 3D point cloud datasets provide the greatest
classification accuracy in identifying Maya archaeological sites while requiring less data preparation. Further, the research
contributes knowledge on the efficacy of data augmentation strategies when working with small 3D datasets.

\1. INTRODUCTION analysis of 2D remote sensing data in a variety of fields for
tasks as wide ranging as pollution detection to poverty
Remote sensing technologies, such as Light Detection and estimation (Piaggesi et al. 2019, Li et al. 2016). In the field of
Ranging (LIDAR), are transforming archaeology. Airborne archaeology, CNNs have been used to automate the
LIDAR Systems (ALS) use a laser pulse emitted from an identification of archaeological sites from ALS data (Albrecht et
airplane to collect 3D measurements of landscapes by al. 2019, Bundzel et al. 2020, Guyot et al. 2021, Kazimi et al.
calculating Time-of-Flight (ToF); that is, the time it takes light 2018, Somrak, Džeroski, and Kokalj 2020, Verschoof-van der
to hit objects in the landscape and reflect to the scanner. Unlike Vaart et al. 2020). This previous research, however, has been
satellite imagery, ALS can penetrate canopied forests to reveal limited to DL architectures that employ 2D data. This approach
the ground surface below the canopies. This allows researchers excludes a wealth of available 3D data, such as point cloud
to detect and map unknown archaeological sites in areas never datasets, that could aid in the detection and classification of
before possible, and is especially true for surveys in Central archaeological sites.
America that have focused on ancient Maya landscapes in
Guatemala, Honduras, Belize, and Mexico (e.g., Chase and
Chase 2017; Prufer and Thompson 2016; von Schwerin et al.
2016). ALS surveys in these areas have produced massive
amounts of data that archaeologists must manually process to
identify archaeological features. This task is extremely timeconsuming, expensive, and requires a high-level of technical
and archaeological expertise. Consequently, significant amounts
of LIDAR data from this region have not been post-processed.
The development of automated methods to identify
archaeological features in such datasets is therefore a pressing
problem in the field.

Deep learning (DL) is a sub-field of machine learning that has
demonstrated state-of-the-art performance on automated object
recognition tasks involving both 2D and 3D datasets. DL
models use layers of artificial neurons to construct a piecewise
function that can iteratively adjust its weights through
optimization procedures to map a set of inputs to a set of
outputs. The pattern and design of these layers is referred to as Figure 1. Copan ALS survey area illustrating archaeological
the architecture of the DL model. Convolutional Neural sites on LIDAR-derived Digital Elevation Model (DEM).
Networks (CNNs)—a DL architecture developed specifically
for 2D image datasets—have out-performed competing This research addresses this gap in previous work through the
approaches for object recognition. CNNs have been used for the application of DL processes that can classify Maya
archaeological sites from ALS generated 3D point cloud

This contribution has been peer-reviewed. The double-blind peer-review was conducted on the basis of the full paper.
https://doi.org/10.5194/isprs-annals-VIII-M-1-2021-133-2021 | © Author(s) 2021. CC BY 4.0 License. 133

<!-- p. 2 -->

ISPRS Annals of the Photogrammetry, Remote Sensing and Spatial Information Sciences, Volume VIII-M-1-2021
28th CIPA Symposium “Great Learning & Digital Emotion”, 28 August–1 September 2021, Beijing, China

datasets. Specifically, the PointConv (Wu, Qi, and Fuxin 2019) 2.3 Project Data: Archaeological and Lidar
DL architecture is used to identify ancient Maya archaeological
sites from ALS-generated 3D point cloud data taken from 26 In the late 1970s and early 1980s, the Copan Archaeological
square kilometers surrounding the UNESCO World Heritage Project carried out a “100%” pedestrian survey of the Copan
Site of Copan, Honduras (Figure 1). This method is tested Pocket and instrument-mapped almost 600 sites within twentyagainst CNN-based processes that rely on 2D data to determine four square kilometers surrounding the city’s main civicthe most efficacious approach. In addition, data augmentation ceremonial core. This work resulted in a (paper) publication that
strategies for working with small 3D datasets are evaluated. The included 24 one-square kilometer maps that plot archaeological
results of these experiments demonstrate that the PointConv sites, contour lines, and hydrology at a scale 1:2000 (Fash and
architecture provides greater classification accuracy in Long 1983). These paper maps were scanned, georeferenced,
identifying Maya archaeological sites than the CNN-based and digitized to create a shapefile with attributes of Copan’s
approach. This result demonstrates a path for researchers to archaeological structures (n~3500) (Richards-Rissetto 2010).
make use of 3D point cloud data directly in DL models while
improving accuracy and reducing data preparation time. In 2013, the MayaArch3D Project commissioned the
acquisition of LIDAR data (LAS and ASCII) for the Copan
The research is organized into the following sections: study area Pocket (von Schwerin et al. 2016). Watershed Sciences Inc.
and dataset (Section 2); overview of previous research in deep (WSI) from Oregon, USA acquired the data using a Leica
learning and archaeology (Section 3); description of the deep ALS50 Phase II system mounted in a Piper Aztec aircraft. The
learning models, experimental set-ups, and data preparation target point density was ≥ 15 pulses/m2 and all areas were
(Section 4); results and discussion (Section 5); lastly, a surveyed with an opposing flight line sidelap overlap of ≥ 50%.
summary of conclusions and future directions (Section 6). The average first-return density for the LIDAR data was 21.57
points/m2 and ground return density averaged 2.91 points/m2.
\2. CASE STUDY: MAYA SITE OF COPAN, HONDURAS WSI set two permanent survey monuments and used a Trimble
R7 base unit and a roving Trimble R8 GNSS receiver to collect
2.1 Historical Background GPS data across the valley. Following acquisition, this LIDAR
data went through several (time-consuming) stages of postAs early as 1000-800 BCE, the ancient Maya constructed processing that incorporated “standard” bare-earth algorithms,
massive and elaborate ceremonial architecture. In fact, due to semi-automatic, and manual methods to classify 3D points into
ALS, archaeologists recently located the oldest and largest four classes: (1) Vegetation (green), (2) Default/unclassified
construction found in the Maya area (Inomata et al. 2020). (green) , (3) Ground (yellow), (4) Archaeological Features
However, not only is ALS assisting archaeologists in site (red), and (5) Ruin Grounds (purple) (see von Schwerin et al
reconnaissance, but it is also changing our views about the scale 2016 for additional details on post-processing) (Figure 2). The
of the ancient Maya civilization with the identification of classified data overlaid with the structure shapefile served as the
thousands of undocumented sites (Canuto et al. 2018; Garrison 3D training set in this research (Figure 2). The resultant
et al. 2018). Through LIDAR data along with excavation, classified 3D data were used to generate a (2.5D raster) Digital
epigraphic, iconographic, architectural, and other lines of Elevation Model incorporating bare-earth and archaeological
evidence, archaeologists are developing a clearer picture of the mounds that was converted into a hillshade, exported as a TIFF
extent and ways the ancient Maya successfully engineered and for the 2D (image) training set.
transformed the landscape for over two millennia.

The case study, Copan, is a UNESCO World Heritage site in
Honduras, but from the 5th–9th centuries CE, the city was the
cultural and commercial center of a powerful ancient Maya
kingdom. The city has awed explorers, archaeologists, and
visitors since the 1500s and is the most thoroughly excavated
Maya site, providing fundamental data for archaeological
interpretations. In 427 CE, Yax Kuk Mo, became Copan’s first
dynastic ruler founding a dynasty that encompassed sixteen
rulers and spanned almost four-hundred years (Fash 2001).

2.2 Environment
Figure 2. Copan ALS survey 3D Classified Point Clouds.
A key impetus for Maya expansion into the Copan area was its
favourable environment with an abundance of rich, natural 3. PREVIOUS WORK
resources including highly productive soils and sufficient
rainfall for agriculture, localized clay sources for ceramics, and 3.1 Deep Learning: Object Classification and Semantic
plentiful wildlife as well as its location along a critical trade Segmentation
route. The city of Copan is located along the Copan River in the
elongated Copan Pocket with an approximated average width of The field of computer vision has studied the problem of
four kilometers. Within this circumscribed environment, automating object classification and semantic segmentation for
altitude ranges from 569-1408 meters resulting in varied decades (Khurana et al. 2016). Object classification refers to the
topography (flat to steep), diverse vegetation and ecological automated classification of objects in 2D and 3D data. Semantic
zones, and differential landuse practices—in the past and today. segmentation, in contrast, refers to the process of classifying all
This ecologically and topographically diverse landscape leads to pixels, or points, within a 2D image, or 3D, as belonging to one
additional challenges in post processing LIDAR data. object contained in a scene verses other objects in that same
scene. CNNs were first introduced by LeCun et al. (1989) and

This contribution has been peer-reviewed. The double-blind peer-review was conducted on the basis of the full paper.
https://doi.org/10.5194/isprs-annals-VIII-M-1-2021-133-2021 | © Author(s) 2021. CC BY 4.0 License. 134

<!-- p. 3 -->

ISPRS Annals of the Photogrammetry, Remote Sensing and Spatial Information Sciences, Volume VIII-M-1-2021
28th CIPA Symposium “Great Learning & Digital Emotion”, 28 August–1 September 2021, Beijing, China

have emerged as the leading approach for object classification which 2D image formats extracted from LIDAR data improve
and semantic segmentation when working with 2D images model accuracy the most. They find that visualization for
(Krizhevsky, Sutskever, and Hinton 2012; Zhao et al. 2017). archaeological topography (VAT) images without analytical
hillshading provide the best prediction performance.
A challenge in working with CNNs is that they require large
amounts of labeled training data often in the range of millions Previous research has also explored the use of semantic
of images that are pre-labeled and/or segmented by hand. This segmentation to identify archaeological sites. Verschoof-van der
poses a difficulty when working with small datasets. In order to Vaart and Lambers (2019) demonstrate the use of the Faster Raddress this problem, researchers have developed a technique CNN semantic segmentation architecture to identify different
called “transfer learning” (Yosinski et al. 2014). Transfer classes of archaeological structures in the Netherlands from
learning involves repurposing CNN models trained on one Simple Local Relief Model (SLRM) images derived from
image dataset for another image dataset. This is done by LIDAR data. The research provides insight into how small
retraining only a few selected layers of the CNN model on the dataset sizes can pose challenges for training DL models.
new dataset. Transfer learning has demonstrated the ability to Bundzel et al. (2020) tests two different semantic segmentation
improve model accuracy in situations where the available data DL architectures, U-Net and Mask R-CNN, to identify Maya
to train CNN models is small (i.e., thousands of images) archaeological sites of various sizes from digital elevation
(Yosinski et al. 2014). Remote sensing datasets are often small model (DEM) images and find that the U-Net architecture,
and previous research suggests that the application of transfer which does not use transfer learning, preforms best on all sizes
learning in this context improves model accuracy (Pires de of archaeological structures.
Lima and Marfurt 2020).
This previous research touches on several key issues in the
There are also DL architectures specifically designed to work application of DL to identify archaeological structures in
with 3D remote sensing data, such as point clouds. Previous LIDAR data. The first issue is the impact that dataset sizes have
work in this area has explored a variety of DL architectures to on the accuracy of DL models. The LIDAR datasets used in this
perform 3D shape classification and 3D point cloud previous research were all relatively small (i.e., in the hundreds
segmentation tasks (Guo et al. 2020). In terms of 3D shape and thousands of data samples) compared to the dataset sizes
classification, previous research can be organized into three used to get peak accuracy in the training of state-of-the-art CNN
categories: multi-view methods - which use a combination of models (i.e., in the millions of images). To address this issue,
3D point data and 2D image views of objects; volumetric-based previous research investigated the impact of simplifying DL
methods – which use voxels to represent 3D objects; and point- architectures, so they have less trainable parameters; using
based methods. Of these, point-based methods have transfer learning; and/or applying data augmentation strategies.
demonstrated some of the highest accuracy when working with Data augmentation is a process in which additional training
3D point cloud data. Our research, therefore, uses a point-based samples are created by copying and modifying (e.g., through
DL architecture to classify 3D point cloud data in the scaling, rotation, translation, adding noise, zooming, etc.)
identification of archaeological sites. existing data to produce new data instances.

3.2 Deep Learning Archaeological LIDAR Applications Another important issue involves the translation of LIDAR data
into an image input format for training a selected DL
DL is still a relatively new field and its applications in architecture. That is, all previous research used 2D images
archaeology to identify archaeological sites from remote sensing extracted from 3D LIDAR data. There has been no study of DL
data, such as LIDAR data, have been limited to the use of DL architectures that can work with the 3D point cloud LIDAR data
architectures that work with 2D data. This previous research can directly, nor how efficacious strategies for dealing with small
be organized into two different categories: approaches using DL archaeological datasets used in the context of 2D architectures
architectures for object classification and those that focus on (e.g., transfer learning and data augmentation) might be when
semantic segmentation. The first category provides a probability used for 3D architectures.
as an output as to whether an input image is likely to contain an
archaeological site. The second approach provides pixel-level Our research addresses these gaps through the application of a
probabilities to classify each pixel of the image as belonging to point-based 3D shape classification DL architecture for the
an archaeological structure or not. This method, therefore, classification of 3D point cloud data. Specifically, the
provides the classification and the position of archaeological PointConv (Wu, Qi, and Fuxin 2019) DL architecture is used to
structures within the larger input image. Both approaches can classify LIDAR-based 3D point cloud data in the classification
also provide probabilities that can be used to classify the type of of Maya archaeological sites. The model is used in conjunction
archaeological structures (e.g., mound, platform, building, etc.) with transfer learning and data augmentation techniques to
found in an input image. improve its efficacy on small datasets.

In terms of approaches that investigate DL architectures for 4. METHODS
object classification, Kazimi et al. (2018) test three different
CNN architectures for the classification of four different 4.1 Dataset Pre-Processing
landscape features in the Harz mining Region in Lower Saxony
using 2D height maps extracted from LIDAR data. They find For the experiments, we implemented 3D and 2D DL models
that the simplest CNN model, which did not use transfer and compared their performance. For the 3D model training, we
learning, was more accurate than the VGG-16 and autoencoder used raw laser (LAS) formatted files annotated by the
architectures. Somrak, Džeroski, and Kokalj (2020) test archaeologists as described in section 2. We uniformly sampled
variations of the VGG-19 CNN architecture with transfer 10,024 points for each input data and computed the normal
learning to classify LIDAR data into four different categories of vectors from the point clouds. The primary parameters for our
Maya archaeological structures. The research also explores point cloud data include XYZ coordinates and normal vectors.

This contribution has been peer-reviewed. The double-blind peer-review was conducted on the basis of the full paper.
https://doi.org/10.5194/isprs-annals-VIII-M-1-2021-133-2021 | © Author(s) 2021. CC BY 4.0 License. 135

<!-- p. 4 -->

ISPRS Annals of the Photogrammetry, Remote Sensing and Spatial Information Sciences, Volume VIII-M-1-2021
28th CIPA Symposium “Great Learning & Digital Emotion”, 28 August–1 September 2021, Beijing, China

The normal vectors were calculated using a script in the open- training learning rate was set to 0.001 with 32 inputs at each
source software CloudCompare. training batch. Stochastic gradient descent was used as an
optimizer and the model was trained for 400 steps.
In order to prepare the dataset for the 2D DL model, the
hillshade image was used as shown in Figure 1. The highresolution hillshade image was divided into smaller-size subimages and were labeled according to the shapefile of
archaeological structures described in section 2.3. Each raw
image was divided into sub-images of 299×299 pixels. This size
was chosen because it was large enough to include
archaeological structures with background. To obtain the
negative class, which does not include any archaeological
structures, sub-images of the same size were used and they
included a variety of natural landscape features, such as hills,
mountains, and flat areas.

4.2 Data Augmentation

Large amounts of data are needed to train the deep learning
models, but our dataset was not large enough, therefore,
different data augmentation methods were used to create a
larger and more variable dataset. For fair comparison between
the 3D and 2D DL model performances, the same data
augmentation strategies were employed for both models during
training by randomly rotating the data and jittering both points
and image pixels by adding Gaussian noise with a zero mean
and 0.02 standard deviation. Figure 3. 3D PointConv model with input LIDAR data
examples for Maya archaeological site classification is shown.
The 3D model training dataset was composed of 142 positive
class LIDAR data samples containing archaeological features, 4.4 Training the 2D Deep Learning Modeland 142 negative class data samples that contained natural
landscape features, such as vegetation, mountains, and hills. The trained 2D CNN model used for the classification of
The 2D training dataset consisted of 410 positive data samples archaeological sites is based on the Inception-v3 (Szegedy et al.
and 430 negative class data samples with a variety of hills, (2016) pre-trained deep learning model. Inception-v3 can learn
mountains, and flat areas (vegetation was removed). Through the most important features in different kinds of images because
data augmentation, the dataset size was tripled for both 3D and it is pre-trained on a large-scale hierarchical dataset called
2D model training. ImageNet. Given that we had a small dataset, the transfer
learning approach was used to train our model. Figure 4 shows
4.3 Training the 3D Deep Learning Model the Inception-v3 architecture along with archaeological site
images.
For our 3D implementation, the PointConv (Wu, Qi, and Fuxin
\2019) model was used, which has demonstrated state-of-the-art
performance in the classification of 3D point clouds. PointConv
is a type of encoder-decoder framework for feature extraction
and propagation that can efficiently perform convolution
operations on non-uniformly sampled 3D point cloud data. The
core feature extracting model takes a point cloud P =
RL×C0 as its input, which contains L points with
C0 channels, and produces a L×C feature map at the end of its{p1,p2,...,pL}∈last decoder layer. PointConv utilizes a multi-layer perceptron(MLP) to learn the convolution weights on each pointimplicitly as a nonlinear transformation from the pointcoordinates to get a continuous convolution operator onirregular point clouds. Figure 3 shows how PointConvprocesses an example 3D point cloud input of a Mayaarchaeological site. In the PointConv architecture, Cin withtheCout relativerepresentscoordinatesthe dimensionsof the 3D ofpointthe (Plocal),input anddensityoutputandcharacteristicsfeatures from (Fin)the Kandnearestrelativeneighbors.coordinatesTheofinput3D points.consistsAfterof
the continuous function MLP1, the corresponding feature Figure 4. 2D-CNN Inception-v3 architecture is shown along
weight W of each point is obtained, and after MLP2, the inverse with the 2D hillshade images used to train the model.
density coefficient S is obtained. Finally, the input features F Similar to the 3D model, 80% of the annotated sub-images were
and output features Fout are calculated. used as training data for the 2D model training and the
For the 3D model training, 80% of the dataset were used in remaining 20% were used for testing. The training learning rate
training and the remaining 20% were used for testing. The was set to 0.01. The training batch size was 100 and the model

This contribution has been peer-reviewed. The double-blind peer-review was conducted on the basis of the full paper.
https://doi.org/10.5194/isprs-annals-VIII-M-1-2021-133-2021 | © Author(s) 2021. CC BY 4.0 License. 136

<!-- p. 5 -->

ISPRS Annals of the Photogrammetry, Remote Sensing and Spatial Information Sciences, Volume VIII-M-1-2021
28th CIPA Symposium “Great Learning & Digital Emotion”, 28 August–1 September 2021, Beijing, China

was trained for 2000 epochs. The final layer of the model was pedestrian surveys, there is a high likelihood that the mounds no
retrained on our 2D high-resolution hillshade dataset and longer exist, and thus do not occur in the LIDAR data.
labeled using the tfClassifier repository of the Inception-v3 Therefore, in this case the data would not actually be
model (Sourcedexter, 2018). misclassified. As for the right image, the cause(s) of the false
negative are currently unknown.
\5. RESULTS

The 3D and 2D models were evaluated based on the
classification accuracy on the test datasets – which were not
used in the training process. Additionally, we evaluated the
models based on augmentation methods. Figure 5 shows the
classification accuracy of different augmentation methods. The
3D model achieved 88% accuracy on the testing data without
augmentation; 91.7% using a Gaussian noise-based approach;
92.4% using random rotations; and 95% accuracy when two
different augmentation strategies were combined together – Figure 6. Examples of false negatives produced by the 3D
specifically, random rotation and Gaussian noise. In PointConv model. The red shapes show archaeological sites that
comparison, the 2D model was only able to achieve an accuracy the model was unable to detect.
of 87.8% using this same combined augmentation strategy.
Figure 7 shows two examples of misclassifications (i.e., false
negatives) made by the 2D CNN model. These examples
illustrate the limitations of the hillshade data representation,
which failed to capture archaeological ruins that were present in
both of these inputs due to low mound height and/or a low
ground-return density or possibly missing mounds—a subject of
future research and possibly a benefit to using 3D point clouds.

Figure 5. Classification accuracy of different data augmentation
strategies for the 3D and 2D deep learning models.

The trained 3D and 2D model performances were also evaluated
based on the calculation of precision (1) and recall (2).

(1)

(2)

Precision measures the number of positive class predictions that
actually belong to the positive class. Recall measures the
number of positive class predictions made out of all positive Figure 7. Examples of false negatives produced by the 2Dexamples found in the dataset. Using the precision and recall CNN model. The black dots show the archaeological sites that
values, the F1 score is calculated and given in equation (3). The were not detected.
F1 score is the weighted average of precision and recall.
\6. CONCLUSIONS & FUTURE WORK

(3) While LIDAR is revolutionizing archaeological reconnaissance,
archaeologists still spend an inordinate amount of time
The 3D inference model achieved 90.5% precision and 94.1% processing LIDAR data to identify archaeological sites because
recall values on the testing data. Based on those values, the standard filtering algorithms often fail to capture many features
weighted F1 value was calculated to be 92.2%. In comparison, (Magoni et al. 2016; Opitz and Cowley 2013). In the Maya
the 2D inference model achieved 84.6% for precision region, identifying archaeological sites is particularly
and 88.9% for recall. The F1 score was 86.91%. Figure 6 shows challenging because many are hidden below jungle canopy and
two examples of “misclassifications” by the 3D PointConv appear as mounds that are difficult to distinguish from natural
model. For the left image, the false negative probably occurs topography. To date, only a few deep learning projects have
due to landscape changes through time arising from crop been applied to archaeology, and these have employed 2D
cultivation. Given that the 3D training set was annotated using a approaches, and while several have achieved high accuracy
shapefile of archaeological structures derived from early 1980s

This contribution has been peer-reviewed. The double-blind peer-review was conducted on the basis of the full paper.
https://doi.org/10.5194/isprs-annals-VIII-M-1-2021-133-2021 | © Author(s) 2021. CC BY 4.0 License. 137

<!-- p. 6 -->

ISPRS Annals of the Photogrammetry, Remote Sensing and Spatial Information Sciences, Volume VIII-M-1-2021
28th CIPA Symposium “Great Learning & Digital Emotion”, 28 August–1 September 2021, Beijing, China

rates, data preparation is more time-consuming that directly REFERENCES
using raw 3D data.
Albrecht, Conrad M, Chris Fisher, Marcus Freitag, Hendrik F
It is under these circumstances that we designed and performed Hamann, Sharathchandra Pankanti, Florencia Pezzutti, and
this study to compare 3D and 2D deep learning approaches to Francesca Rossi. 2019. Learning and Recognizing
classify Maya archaeological sites. Overall, the 3D model Archaeological Features from LiDAR Data. 2019 IEEE
achieved the highest accuracy. This result is likely because the International Conference on Big Data (Big Data).
model is trained on 3D points, which include the z elevation
(unlike the 2D hillshade images). Moreover, the data Bundzel, Marek, Miroslav Jaščur, Milan Kováč, Tibor
augmentation experiments showed the best accuracy when Lieskovský, Peter Sinčák, and Tomáš Tkáčik. 2020. Semantic
augmentation methods were combined – specifically Gaussian segmentation of airborne lidar data in maya archaeology.
noise and random rotation augmentations. This combined Remote Sensing 12 (22):3685.
augmentation increases the training dataset and the robustness
of the model. Given the small LIDAR dataset for Copan, Canuto, M., Estrada-Belli, F., Garrison, T., Houston, S. et al.
merging different augmentation methods using 3D data has 2018. Ancient lowland Maya complexity as revealed by
significant potential for improving deep learning models. airborne laser scanning of northern Guatemala. Science 28 Vol.
361, Issue 6409; DOI: 10.1126/science.aau0137
While these initial results are promising, they do have some
limitations. First, the DL results are dependent on the precision Chase, A. and Chase, D. 2017. Detection of Maya ruins by
of the LIDAR data—areas with low point-return densities have LiDAR: Applications, case study, and issues. In Sensing the
a higher likelihood of false negatives. Second, because Maya Past, pp. 455-468. Springer, Cham.
sites exhibit diversity in architecture, infrastructure, and
environment, using a small dataset does not capture all Fash, W. 2001. Scribes, Warriors, and Kings: The City of
variation. For example, archaeological site locations range from Copan and the Ancient Maya. Thames and Hudson.
low-lying scrub brush in the Yucatan Peninsula of Mexico to
dense tropical forest sites in the Petén (Maya Heartland) and Garrison,T.,Houston, S., Firpi. O. 2018. Recentering the rural:
mountainous Highlands of Guatemala. Moreover, architectural Lidar and articulated landscapes among the Maya. Journal of
size and style differ based on function, construction materials, Anthropological Archaeology 53:133-146.
and time period. Such diversity necessitates an initial large time doi.org/10.1016/j.jaa.2018.11.005.
investment in the annotation of features. Third, identification of
low-lying archaeological (household) mounds depends not only Girardeau-Montaut, D., 2016. CloudCompare. Retrieved from
on the precision of the original LIDAR data, but also on the CloudCompare: https://www. danielgm.net/cc.
ability to separate mounds from landscape features.
Guo, Yulan, Hanyun Wang, Qingyong Hu, Hao Liu, Li Liu, and
Future work seeks to overcome and/or reduce some of these Mohammed Bennamoun. 2020. Deep learning for 3d point
limitations as well as refine the methods employed in this study. clouds: A survey. IEEE transactions on pattern analysis and
The next phase of research includes several components: (1) machine intelligence.
experimenting with additional augmentation techniques, beyond
random rotation and Gaussian noise, such as applying multi- Guyot, Alexandre, Marc Lennon, Thierry Lorho, and Laurence
directional hillshade, PCA of hillshade, local relief, and Sky- Hubert-Moy. 2021. Combined Detection and Segmentation of
View Factor to the DEM (Štular et al. 2012; Thompson 2020); Archaeological Structures from LiDAR Data Using a Deep
(2), integrating raw and augmented 3D data with various 2D Learning Approach. Journal of Computer Applications in
datasets (3) testing our methods on other Maya LIDAR datasets, Archaeology 4 (1):1.
and (4), identifying causes for inaccurate classification such as
low mound height, vegetation types, and differential Inomata, T., Triadan, D., Vázquez López, V.A. et al. 2020.
topography. Given the diversity in Maya archaeological Monumental architecture at Aguada Fénix and the rise of Maya
landscapes, we plan to investigate the impact of varied civilization. Nature 582, 530–533. doi.org/10.1038/s41586approaches on different feature types in relation to landscape 020-2343-4
factors; it is likely that multiple DL methods may be required to
identify and classify ancient Maya archaeological sites. To Kazimi, Bashir, Frank Thiemann, Katharina Malek, Monika
begin to investigate such differences, we are analysing the DL Sester, and Kourosh Khoshelham. 2018. Deep Learning for
results in relation to other geospatial datasets such as landform Archaeological Object Detection in Airborne Laser Scanning
and vegetation using Geographic Information Systems (GIS). Data. Proceedings of the 2nd Workshop On Computing
Following this analysis, we will test our methods on a larger Techniques for Spatio-Temporal Data in Archaeology and
LIDAR dataset from Belize to evaluate their applicability in Cultural Heritage, Melbourne, Australia.
other Maya regions and refine them for wider-spread use for
Maya archaeology. Khurana, Palak, Anshika Sharma, Shailendra Narayan Singh,
and Pradeep Kumar Singh. 2016. A survey on object
ACKNOWLEDGEMENTS recognition and segmentation techniques. 2016 3rd
International Conference on Computing for Sustainable Global
The Jane Robertson Layman Fund at the University of Nebraska Development (INDIACom).
Foundation funded this pilot research. The MayaArch3D
project provided the lidar data. We thank the Honduran Institute Krizhevsky, Alex, Ilya Sutskever, and Geoffrey E Hinton. 2012.
of Anthropology and History (IHAH) for permission to carry "Imagenet classification with deep convolutional neural
out research at the archaeological site of Copan, Honduras. networks." Advances in neural information processing systems.

This contribution has been peer-reviewed. The double-blind peer-review was conducted on the basis of the full paper.
https://doi.org/10.5194/isprs-annals-VIII-M-1-2021-133-2021 | © Author(s) 2021. CC BY 4.0 License. 138

<!-- p. 7 -->

ISPRS Annals of the Photogrammetry, Remote Sensing and Spatial Information Sciences, Volume VIII-M-1-2021
28th CIPA Symposium “Great Learning & Digital Emotion”, 28 August–1 September 2021, Beijing, China

LeCun, Yann, Bernhard Boser, John S Denker, Donnie Thompson, Amy. 2020. Detecting Classic Maya Settlements
Henderson, Richard E Howard, Wayne Hubbard, and Lawrence with Lidar-Derived Relief Visualizations. Remote Sensing.
Jackel, D. 1989. Backpropagation applied to handwritten zip 2020; 12(17):2838.
code recognition. Neural computation 1 (4):541-551.

Li, Xiang, Ling Peng, Yuan Hu, Jing Shao, and Tianhe Chi. Verschoof-van der Vaart, W. and Lambers, K. 2019. Learning
\2016. Deep learning architecture for air quality predictions. to look at LiDAR: The use of R-CNN in the automated
Environmental Science and Pollution Research 23 (22):22408- detection of archaeological objects in LiDAR data from the
\22417. Netherlands. Journal of Computer Applications in Archaeology
2 (1):31-40
Magoni, Aline, Travis W. Stanton, Nicolas Barth, Juan Carlos
Fernandez-Diaz, José Francisco Osorio León, Francisco Pérez Verschoof-van der Vaart, Wouter B, Karsten Lambers, Wojtek
Ruíz and Jessica A. Wheeler. 2016. Detection Thresholds of Kowalczyk, and Quentin PJ Bourgeois. 2020. Combining deep
Archaeological Features in Airborne Lidar Data from Central learning and location-based ranking for large-scale
Yucatán. Advances in Archaeological Practice 4 (3): 232-248. archaeological prospection of LiDAR data from the
Netherlands. ISPRS International Journal of Geo-Information
Opitz, Rachel and David Cowley (eds). 2013. Interpreting 9 (5):293.
Archaeological Topography: 3D Data, Visualisation and
Observation. Oxbow Books. von Schwerin J., Richards-Rissetto H, Remondino F., Grazia
Spera, M., Auer M., Billen, N., Loos, L., Stelson, L., Reindel,
Piaggesi, Simone, Laetitia Gauvin, Michele Tizzoni, Ciro M. 2016. Airborne LiDAR Acquisition, Post-Processing and
Cattuto, Natalia Adler, Stefaan Verhulst, Andrew Young, Accuracy-Checking for a 3D WebGIS of Copan, Honduras,
Rhiannan Price, Leo Ferres, and Andre Panisson. 2019. Journal of Archaeological Research: Reports (5):85-104.
Predicting City Poverty Using Satellite Imagery. Proceedings of DOI:10.1016/j.jasrep.2015.11.005
the IEEE Conference on Computer Vision and Pattern
Recognition Workshops. Wu, Wenxuan, Zhongang Qi, and Li Fuxin. 2019. Pointconv:
Deep convolutional networks on 3d point clouds. Proceedings
Pires de Lima, Rafael, and Kurt Marfurt. 2020. Convolutional of the IEEE/CVF Conference on Computer Vision and Pattern
neural network for remote-sensing scene classification: Transfer Recognition.
learning analysis. Remote Sensing 12 (1):86.
Yosinski, Jason, Jeff Clune, Yoshua Bengio, and Hod Lipson.
Prufer, K. and Thompson, A. 2016. Lidar-based analyses of 2014. How transferable are features in deep neural networks"
anthropogenic landscape alterations as a component of the built Advances in neural information processing systems.
environment. Advances in Archaeological Practice 4(3): 393409. Cambridge University Press. Zhao, Bo, Jiashi Feng, Xiao Wu, and Shuicheng Yan. 2017. "A
survey on deep learning-based fine-grained object classification
Qi, Charles R, Li Yi, Hao Su, and Leonidas J Guibas. 2017. and semantic segmentation." International Journal of
Pointnet++: Deep hierarchical feature learning on point sets in a Automation and Computing 14 (2):119-135.
metric space. arXiv preprint arXiv:1706.02413.

Richards-Rissetto, H. 2010. Exploring Social Interaction at the
Ancient Maya City of Copan, Honduras: A Multi-Scalar
Geographic Information Systems (GIS) Analysis of Access and
Visibility. PhD. Dissertation, University of New Mexico:
Albuquerque.

Somrak, Maja, Sašo Džeroski, and Žiga Kokalj. 2020. Learning
to classify structures in ALS-derived visualizations of ancient
Maya Settlements with CNN. Remote Sensing 12 (14):2215.

Sourcedexter, 2018. tfClassifier: Tensorflow based training and
classification scripts for text, images. Online:
https://github.com/sourcedexter/tfClassifier

Štular, Benjamin, Žiga Kokalj, Krištof Oštir, Laure Nuninger,
\2012. Visualization of lidar-derived relief models for detection
of archaeological features, Journal of Archaeological Science 39
(11): 3354-3360,

Szegedy, C., Vanhoucke, V., Ioffe, S., Shlens, J. and Wojna, Z.,
\2016. Rethinking the inception architecture for computer
vision. In Proceedings of the IEEE conference on computer
vision and pattern recognition (pp. 2818-2826

This contribution has been peer-reviewed. The double-blind peer-review was conducted on the basis of the full paper.
https://doi.org/10.5194/isprs-annals-VIII-M-1-2021-133-2021 | © Author(s) 2021. CC BY 4.0 License. 139
